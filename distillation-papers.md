# ICLR 2026 Oral Papers — 大模型蒸馏相关 | Distillation-Related Papers

从 223 篇 ICLR 2026 Oral 论文中筛选出与大模型蒸馏（Knowledge Distillation）相关的 **5 篇论文**，涵盖知识蒸馏方法论、LLM 推理蒸馏、扩散模型蒸馏、数据高效预训练中的蒸馏技术，以及 LLM 对齐中的偏好蒸馏。

---

## 28. Pre-training under infinite compute

**无限计算资源下的预训练**

**OpenReview**: [https://openreview.net/forum?id=ck0aZTAnwK](https://openreview.net/forum?id=ck0aZTAnwK)

**Authors**: Konwoo Kim, Suhas Kotha (Stanford University), Percy Liang (Stanford University), Tatsunori Hashimoto (Stanford University)

**Institutions**: Stanford University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: scaling laws, data efficiency, pre-training

**TL;DR**: Since compute grows faster than the web, we design simple recipes that improve the asymptote of compute scaling laws to be 5x data efficient, offering better performance with sufficient compute.

**TL;DR翻译**: 由于计算增长速度快于网络文本，我们设计了简单的方案来改善计算缩放定律的渐近值，实现5倍数据效率，在充足计算条件下提供更好的性能。

**蒸馏相关**: 提出将集成模型蒸馏为小8倍的学生模型，保留83%的集成收益，用于数据高效的 LLM 预训练。

**背景**: 语言模型预训练历来在计算约束下研究（Chinchilla 缩放定律等），但现实中计算能力每年增长约 4 倍，而可用的网络文本仅增长约 1.03 倍。这意味着未来将进入"计算充裕、数据稀缺"的新范式，现有的缩放定律和训练策略不再适用。

**动机**: 在固定数据量下，简单增加训练轮次（epoching）或参数量会导致过拟合，现有数据受限方法（如 Muennighoff et al., 2024）的性能很快饱和。作者希望找到在无限计算、有限数据条件下最大化预训练效果的系统性方案。

**创新点**:
1. 发现最优权重衰减（weight decay）比标准实践大 30 倍，通过强正则化显著缓解过拟合
2. 提出用缩放定律的**渐近值（asymptote）**而非固定计算预算下的性能来评估训练策略的上限
3. 证明集成（ensembling）独立训练的模型比单纯增大参数量能达到更低的损失渐近值
4. **集成蒸馏**：将多个集成模型蒸馏为 8 倍小的学生模型，保留 83% 的集成收益，使数据效率增益可在实际部署规模下实现
5. 联合策略（epoching + 正则化 + 参数扩展 + 集成扩展）在 200M token 上实现 5.17 倍数据效率提升

**开源代码**: 论文承诺开源所有训练/评估代码及包含 2000+ 次实验的 WandB 报告

**Abstract**:

Since compute grows much faster than web text available for language model pre-training, we ask how one should approach pre-training under fixed data and no compute constraints. We first show that existing data-constrained approaches of increasing epoch count and parameter count overfit, and we improve upon such recipes by tuning regularization, finding that the optimal weight decay is $30\times$ larger than standard practice. Since our regularized recipe monotonically decreases loss following a power law in parameter count, we estimate its best possible performance via the asymptote of its scaling law rather than the performance at a fixed compute budget. We then identify that ensembling independently trained models achieves a significantly lower loss asymptote than the regularized recipe. Our best intervention combining epoching, regularization, parameter scaling, and ensemble scaling achieves an asymptote at 200M tokens using $5.17\times$ less data than our baseline, and our data scaling laws predict that this improvement persists at higher token budgets. We find that our data efficiency gains can be realized at smaller parameter counts as we can distill an ensemble into a student model that is 8$\times$ smaller and retains $83$% of the ensembling benefit. Finally, our interventions designed for validation loss generalize to downstream benchmarks, achieving a $9$% improvement for pre-training evals. Our results show that simple algorithmic improvements can enable significantly more data-efficient pre-training in a compute-rich future.

**摘要翻译**:

由于计算能力的增长远快于可用于语言模型预训练的网络文本，我们探讨了在固定数据量且无计算约束条件下应如何进行预训练。我们首先表明，现有的数据受限方法——增加训练轮次和参数量——会导致过拟合，我们通过调整正则化改进了这些方案，发现最优权重衰减比标准实践大$30$倍。由于我们的正则化方案随参数量按幂律单调降低损失，我们通过其缩放定律的渐近值而非固定计算预算下的性能来估计其最佳可能性能。随后我们发现，对独立训练的模型进行集成能够达到比正则化方案显著更低的损失渐近值。我们结合多轮训练、正则化、参数规模扩展和集成规模扩展的最佳干预方案在2亿token上实现了渐近值，所用数据比基线少$5.17$倍，且我们的数据缩放定律预测该改进在更高token预算下仍然成立。我们发现数据效率增益可在更小的参数量下实现，因为我们可以将集成蒸馏为小8倍的学生模型，同时保留83%的集成收益。最后，我们为验证损失设计的干预措施可泛化到下游基准，在预训练评估中实现了9%的改进。我们的结果表明，简单的算法改进能够在计算资源充裕的未来实现显著更高的数据效率预训练。

---

## 42. Universal Inverse Distillation for Matching Models with Real-Data Supervision (No GANs)

**通用逆蒸馏：使用真实数据监督的匹配模型加速方法（无需 GAN）**

**OpenReview**: [https://openreview.net/forum?id=8NuN5UzXLC](https://openreview.net/forum?id=8NuN5UzXLC)

**Authors**: Nikita Maksimovich Kornilov (Applied AI Institute), David Li (Mohamed bin Zayed University of Artificial Intelligence), Tikhon Mavrin (Applied AI Institute), Aleksei Leonov (Huawei Technologies Ltd.), Nikita Gushchin (Applied AI Institute), Evgeny Burnaev (Applied AI Institute), Iaroslav Sergeevich Koshelev (Huawei Technologies Ltd.), Alexander Korotin

**Institutions**: Applied AI Institute, Mohamed bin Zayed University of Artificial Intelligence, Applied AI Institute, Huawei Technologies Ltd.

**Primary Area**: generative models

**Keywords**: Diffusion models, Flow Matching, Acceleration of diffusion/flow models, Distillation of diffusion/flow models

**蒸馏相关**: 提出 RealUID 统一蒸馏框架，将多步扩散/流匹配大模型蒸馏为高效的单步生成器，无需 GAN，可无缝融入真实数据。

**背景**: 扩散模型（Diffusion Models）和流匹配模型（Flow Matching）在图像生成上取得了卓越的质量，但推理需要数十到数百步的迭代采样，速度极慢。蒸馏方法通过训练单步生成器来加速推理，但现有方法存在两大局限：(1) 各自仅适用于特定框架（如仅适用于扩散或仅适用于流匹配），(2) 本质上是 data-free 的，若要利用真实数据必须引入 GAN 判别器进行对抗训练。

**动机**: 构建一个统一的蒸馏框架，能同时适用于所有匹配模型（扩散模型、流匹配、Bridge Matching、Stochastic Interpolants 等），并且能以简单优雅的方式融入真实数据监督，无需引入 GAN 的不稳定训练。

**创新点**:
1. **RealUID 统一框架**：首次提出适用于所有匹配模型的通用蒸馏方法，涵盖 Diffusion、Flow Matching、Bridge Matching 和 Stochastic Interpolants
2. **无需 GAN 的真实数据融入**：通过调节系数 $\alpha$、$\beta$ 即可无缝将真实数据引入蒸馏过程，避免对抗训练的不稳定性
3. **统一理论基础**：将此前的蒸馏方法（SiD、FGM、IBMD）纳入同一理论框架，证明它们是 RealUID 的特例
4. **逆优化视角**：建立了蒸馏与逆优化问题之间的理论联系，为方法提供了坚实的数学基础
5. **两阶段微调策略**：先进行 data-free 蒸馏预热，再引入真实数据进行微调，进一步提升生成质量

**开源代码**: 论文声明代码将公开发布（Section 4 Experiments）

**Abstract**:

While achieving exceptional generative quality, modern diffusion, flow, and other matching models suffer from slow inference, as they require many steps of iterative generation. Recent distillation methods address this by training efficient one-step generators under the guidance of a pre-trained teacher model. However, these methods are often constrained to only one specific framework, e.g., only to diffusion or only to flow models. Furthermore, these methods are naturally data-free, and to benefit from the usage of real data, it is required to use an additional complex adversarial training with an extra discriminator model. In this paper, we present **RealUID**, a unified distillation framework for all matching models that seamlessly incorporates real data into the distillation procedure without GANs. Our **RealUID** approach offers a simple theoretical foundation that covers previous distillation methods for Flow Matching and Diffusion models, and is also extended to their modifications, such as Bridge Matching and Stochastic Interpolants.

**摘要翻译**:

尽管现代扩散模型、流模型及其他匹配模型取得了卓越的生成质量，但由于需要多步迭代生成，其推理速度较慢。近期的蒸馏方法通过在预训练教师模型的指导下训练高效的单步生成器来解决这一问题。然而，这些方法通常仅适用于某一特定框架，例如仅适用于扩散模型或仅适用于流模型。此外，这些方法本质上是无数据的，若要利用真实数据，则需要引入额外的复杂对抗训练和判别器模型。在本文中，我们提出了 **RealUID**，一个面向所有匹配模型的统一蒸馏框架，能够在无需 GAN 的情况下将真实数据无缝融入蒸馏过程。我们的 **RealUID** 方法提供了简洁的理论基础，涵盖了此前针对 Flow Matching 和 Diffusion 模型的蒸馏方法，并进一步扩展至 Bridge Matching 和 Stochastic Interpolants 等变体。

---

## 165. DTO-KD: Dynamic Trade-off Optimization for Effective Knowledge Distillation

**DTO-KD：面向有效知识蒸馏的动态权衡优化**

**OpenReview**: [https://openreview.net/forum?id=QMItTyQW92](https://openreview.net/forum?id=QMItTyQW92)

**Authors**: Zeeshan Hayder (Australian National University), Ali Cheraghian (CSIRO), Lars Petersson (CSIRO), Mehrtash Harandi (Monash University), Richard Hartley (Australian National University)

**Institutions**: Australian National University, CSIRO, Monash University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Knowledge Distillation

**蒸馏相关**: 将知识蒸馏重新构建为多目标优化问题，提出动态平衡任务损失与蒸馏损失的通用方法，适用于任意 KD 变体，在图像分类、目标检测、语义分割和语音识别上均有效。

**背景**: 知识蒸馏（KD）是模型压缩的主流方法，通过大容量教师模型指导紧凑学生模型的训练。标准 KD 需要同时优化两个目标：任务损失（对齐真实标签）和蒸馏损失（对齐教师输出分布），两者的平衡通常由静态超参数 $\alpha_1$、$\alpha_2$ 控制。随着 Vision Transformer 等大模型的兴起，教师-学生架构差异越来越大，这一优化挑战更加突出。

**动机**: 现有 KD 方法面临两个核心问题：(1) **梯度冲突（Gradient Conflict）**——任务梯度与蒸馏梯度方向相反，相互抵消；(2) **梯度主导（Gradient Dominance）**——一个目标的梯度幅度远大于另一个，导致单一目标支配训练。静态加权无法应对训练过程中动态变化的梯度关系。

**创新点**:
1. **将 KD 重构为多目标优化（MOO）问题**：彻底消除手动调节 $\alpha$ 超参数的需求
2. **闭式动态权重求解**：推导出每次迭代最优权重的解析解，计算高效，无需额外反向传播
3. **理论保证**：证明更新方向同时与两个目标对齐（解决梯度冲突），且对两个损失的贡献相等（解决梯度主导），并具有梯度范数的上下界保证
4. **摊销训练（Amortized Training）**：用梯度下降近似求解双目标权重，避免每步额外反向传播开销
5. **广泛适用性**：可即插即用地应用于任意 KD 变体；在 ImageNet-1K（分类）、MS-COCO（检测）、ADE20K（分割）、CommonVoice（语音）上均取得 SOTA

**开源代码**: 论文未明确提供代码仓库链接

**Abstract**:

Knowledge Distillation (KD) is a widely adopted framework for compressing large models into compact student models by transferring knowledge from a high-capacity teacher. Despite its success, KD presents a significant optimization challenge: balancing the student loss (which aligns the student with ground-truth labels) and the distillation loss (which aligns the student with the teacher's output distribution). This trade-off is typically controlled by a static hyperparameter, requiring extensive tuning and offering no guarantees of optimal balance throughout training. We propose DTO-KD, a principled approach that reframes KD as a multi-objective optimization (MOO) problem. Rather than relying on fixed weighting, DTO-KD dynamically adjusts the balance between the two objectives using a common descent direction algorithm, ensuring simultaneous improvement on both objectives at each training step. Our formulation requires no additional hyperparameters and applies to virtually any KD variant without altering its core loss functions. Experiments across diverse settings, including ImageNet-1K for image classification, MS-COCO for object detection, ADE20K for semantic segmentation, and CommonVoice for speech recognition, consistently demonstrate that DTO-KD matches or surpasses conventional fixed-weight KD, while requiring no hyperparameter tuning. We additionally provide theoretical analysis showing improved convergence behavior. Furthermore, student models trained with DTO-KD exceed the performance of their non-distilled counterparts, demonstrating the efficacy of our multi-objective formulation for KD.

**摘要翻译**:

知识蒸馏（KD）是一种广泛采用的框架，通过从高容量教师模型传递知识将大模型压缩为紧凑的学生模型。尽管取得了成功，KD面临着一个重大的优化挑战：平衡学生损失（使学生与真实标签对齐）和蒸馏损失（使学生与教师的输出分布对齐）。这种权衡通常由一个静态超参数控制，需要大量调优且无法保证在整个训练过程中达到最优平衡。我们提出了DTO-KD，一种将KD重新构建为多目标优化（MOO）问题的有原则方法。DTO-KD不依赖固定加权，而是使用公共下降方向算法动态调整两个目标之间的平衡，确保在每个训练步骤中两个目标同时改进。我们的公式化方法不需要额外的超参数，且适用于几乎任何KD变体而无需改变其核心损失函数。在包括ImageNet-1K图像分类、MS-COCO目标检测、ADE20K语义分割和CommonVoice语音识别等多样化场景的实验一致表明，DTO-KD在无需超参数调优的情况下达到或超越了传统固定权重KD的性能。我们还提供了理论分析，展示了改进的收敛行为。此外，使用DTO-KD训练的学生模型超越了未蒸馏版本的性能，证明了我们多目标公式化方法在KD中的有效性。

---

## 174. OpenThoughts: Data Recipes for Reasoning Models

**OpenThoughts：推理模型的数据配方**

**OpenReview**: [https://openreview.net/forum?id=7xjoTuaNmN](https://openreview.net/forum?id=7xjoTuaNmN)

**Authors**: Etash Kumar Guha (RIKEN), Ryan Marten (University of Illinois Urbana-Champaign), Sedrick Keh (Toyota Research Institute), Negin Raoof (University of California, Berkeley), Georgios Smyrnis (University of Texas, Austin), Hritik Bansal (University of California, Los Angeles), Marianna Nezhurina (Forschungszentrum Juelich GmbH), Jean Mercat (Toyota Research Institute), Trung Vu (Google), Zayne Rea Sprague (New York University), Ashima Suvarna (University of California, Los Angeles), Benjamin Feuer (Computer Science Department, Stanford University), Leon Liangyu Chen (Computer Science Department, Stanford University), Zaid Khan (University of North Carolina at Chapel Hill), Eric Frankel (Department of Computer Science, University of Washington), Sachin Grover (Arizona State University), Caroline Choi (Computer Science Department, Stanford University), Niklas Muennighoff (Stanford University), Shiye Su (Stanford University), Wanjia Zhao (Stanford University), John Yang (Stanford University), Shreyas Pimpalgaonkar (New York University), Kartik sharma (Georgia Institute of Technology), Charlie Cheng-Jie Ji (University of California, Berkeley), Yichuan Deng (Department of Computer Science, University of Washington), Sarah M Pratt (University of Washington), Vivek Ramanujan (Department of Computer Science, University of Washington), Jon Saad-Falcon (Computer Science Department, Stanford University), Stutee Acharya (University of South Florida), Jeffrey Li (Department of Computer Science, University of Washington), Achal Dave (Anthropic), Alon Albalak (Lila Sciences), Kushal Arora (McGill University), Blake Wulfe, Chinmay Hegde (New York University), Greg Durrett (New York University), Sewoong Oh (University of Washington), Mohit Bansal (University of North Carolina at Chapel Hill), Saadia Gabriel (University of California, Los Angeles), Aditya Grover (University of California, Los Angeles), Kai-Wei Chang (University of California, Los Angeles), Vaishaal Shankar (Apple), Aaron Gokaslan (Cornell University), Mike A Merrill (Stanford University), Tatsunori Hashimoto (Stanford University), Yejin Choi (Computer Science Department, Stanford University), Jenia Jitsev (LAION), Reinhard Heckel (Technische Universität München), Maheswaran Sathiamoorthy (University of Southern California), Alex Dimakis (Electrical Engineering & Computer Science Department, University of California, Berkeley), Ludwig Schmidt (Stanford University)

**Institutions**: RIKEN, University of Illinois Urbana-Champaign, Toyota Research Institute, University of California, Berkeley, University of Texas, Austin, University of California, Los Angeles, Forschungszentrum Juelich GmbH, Google, New York University, Computer Science Department, Stanford University, University of North Carolina at Chapel Hill, Department of Computer Science, University of Washington, Arizona State University, Stanford University, Georgia Institute of Technology, University of Washington, University of South Florida, Anthropic, Lila Sciences, McGill University, Apple, Cornell University, LAION, Technische Universität München, University of Southern California, Electrical Engineering & Computer Science Department, University of California, Berkeley

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Reasoning, Data, LLM

**TL;DR**: Data pipeline analysis for training reasoning models

**TL;DR翻译**: 用于训练推理模型的数据流水线分析

**蒸馏相关**: 使用 QwQ-32B 作为教师模型生成推理数据，将推理能力蒸馏到 7B 学生模型，在 AIME 2025、LiveCodeBench 等基准上大幅超越 DeepSeek-R1-Distill-Qwen-7B。

**背景**: DeepSeek-R1、o3 等推理模型在数学、编程和科学推理上取得突破，核心在于后训练阶段（SFT 或 RL）使模型生成长链式思维（chain-of-thought）。DeepSeek 发布的 R1-Distill 系列模型证明，仅通过 SFT 蒸馏教师模型的推理轨迹即可获得强大的小模型推理能力，但前沿模型的训练数据均为闭源，开源社区缺乏可复现的数据管线。

**动机**: 系统性地研究推理蒸馏数据管线的每个环节（问题来源、问题筛选、去重、多次采样、答案过滤、教师模型选择），通过 1000+ 对照实验找到最优配方，构建完全开源的推理训练数据集。

**创新点**:
1. **系统性数据管线消融**：对 6 个管线阶段进行 1000+ 对照实验，揭示了多个反直觉发现
2. **弱教师优于强教师**：QwQ-32B 作为教师模型优于 DeepSeek-R1，尽管后者在推理基准上得分更高
3. **多次采样比更多问题更有效**：对少量高质量问题进行 16 倍重复采样，性能优于增加问题数量
4. **答案过滤无显著收益**：多数验证/过滤策略不优于不过滤的基线
5. **少而精优于多而杂**：仅使用 1-2 个最优问题来源优于混合 8-16 个来源
6. **OpenThinker3-7B**：7B 规模 SOTA，AIME 2025 上 53%（超 R1-Distill-Qwen-7B 15.3 个百分点）、LiveCodeBench 上 51%、GPQA Diamond 上 54%

**开源代码**: 完全开源——数据集（OpenThoughts3-1.2M）、模型（OpenThinker3-7B）、训练代码和评估流程均已公开发布

**Abstract**:

Reasoning models have made rapid progress on many benchmarks involving math, code, and science. Yet, there are still many open questions about the best training recipes for reasoning since state-of-the-art models often rely on proprietary datasets with little to no public information available. To address this, the goal of the OpenThoughts project is to create open-source datasets for training reasoning models. Our OpenThoughts2-1M dataset led to OpenThinker2-32B, the first model trained on public reasoning data to match DeepSeek-R1-Distill-32B on standard reasoning benchmarks such as AIME and LiveCodeBench. We then improve our dataset further by systematically investigating each step of our data generation pipeline with 1,000+ controlled experiments, which led to OpenThoughts3. Scaling the pipeline to 1.2M examples and using QwQ-32B as teacher yields our OpenThinker3-7B model, which achieves state-of-the-art results: 53% on AIME 2025, 51% on LiveCodeBench 06/24-01/25, and 54% on GPQA Diamond – improvements of 15.3, 17.2, and 20.5 percentage points compared to the DeepSeek-R1-Distill-Qwen-7B. All of our datasets and models are available on ANONYMIZED.

**摘要翻译**:

推理模型在涉及数学、代码和科学的众多基准上取得了快速进展。然而，关于推理模型最佳训练配方仍存在许多未解问题，因为最先进的模型通常依赖专有数据集，几乎没有可用的公开信息。为解决这一问题，OpenThoughts 项目的目标是创建用于训练推理模型的开源数据集。我们的 OpenThoughts2-1M 数据集训练出了 OpenThinker2-32B，这是首个在公开推理数据上训练、并在 AIME 和 LiveCodeBench 等标准推理基准上与 DeepSeek-R1-Distill-32B 匹配的模型。随后，我们通过对数据生成流水线的每个步骤进行超过 1000 次对照实验来系统地改进数据集，由此产生了 OpenThoughts3。将流水线扩展至 120 万个样本并使用 QwQ-32B 作为教师模型，我们得到了 OpenThinker3-7B 模型，该模型取得了最先进的结果：AIME 2025 上 53%、LiveCodeBench 06/24-01/25 上 51%、GPQA Diamond 上 54%——相比 DeepSeek-R1-Distill-Qwen-7B 分别提升了 15.3、17.2 和 20.5 个百分点。我们所有的数据集和模型均已开源。

---

## 220. Semi-Supervised Preference Optimization with Limited Feedback

**有限反馈下的半监督偏好优化**

**OpenReview**: [https://openreview.net/forum?id=ghwxbTx7do](https://openreview.net/forum?id=ghwxbTx7do)

**Authors**: Seonggyun Lee (Yonsei University), Sungjun Lim (Yonsei University), Seojin Park (Yonsei University), Soeun Cheon (Korea Advanced Institute of Science & Technology), Kyungwoo Song (Yonsei University)

**Institutions**: Yonsei University, Korea Advanced Institute of Science & Technology

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Preference Optimization, Semi-Supervised Learning

**蒸馏相关**: 通过伪标签从大规模未配对数据中蒸馏潜在偏好，仅用 1% 标注数据即超越 10% 数据训练的基线，大幅降低 LLM 对齐的数据获取成本。

**背景**: 偏好优化（Preference Optimization）是 LLM 对齐的关键技术，从 RLHF 到 DPO/SimPO 等方法显著推进了模型与人类偏好的对齐。然而，所有这些方法都严重依赖大量成对标注的偏好数据（每个数据点耗费 $10-30，需专家 5-10 分钟/条），数据获取成本极高。

**动机**: 现实中存在大量无偏好标签的 SFT 数据（如 UltraChat），其中蕴含丰富的隐式偏好信号但被现有方法忽视。合成偏好数据虽然降低成本，但会传播模型偏差，质量难以保证。作者希望用少量标注数据 + 大量未标注数据实现高质量的 LLM 对齐。

**创新点**:
1. **半监督偏好优化框架（SSPO）**：首次将半监督学习引入偏好优化，同时利用少量成对标签和大量未配对样本
2. **最优奖励阈值理论**：证明在 sub-Gaussian 假设下，存在一个最优阈值 $\delta^*$ 能以高概率分离优选和劣选响应（Theorem 1）
3. **有原则的伪标签策略**：基于核密度估计（KDE）实际估计奖励分布，结合指数移动平均（EMA）稳定阈值，为未配对数据生成可靠的伪偏好标签
4. **自适应课程学习调度器**：训练初期依赖可靠的标注数据，随训练进展逐渐增加伪标签数据权重，动态平衡两种数据源
5. **极致数据效率**：Mistral-7B 仅用 UltraFeedback 1% 数据（611 条标注），AlpacaEval2.0 LC 达 26.7%，超越所有基线在 10% 数据上的表现
6. **领域泛化性**：在通用（UltraFeedback）、医疗（UltraMedical）、商业（DSP Business）三个领域均有效

**开源代码**: 代码已开源（https://github.com/leesg0104/SSPO）

**Abstract**:

The field of preference optimization has made outstanding contributions to the alignment of language models with human preferences. Despite these advancements, recent methods still rely heavily on substantial paired (labeled) feedback data, leading to substantial resource expenditures. To address these challenges, we study the problem of Semi-Supervised Preference Optimization in which the idea is to learn from both a small number of pairwise preference labels and a large pool of unpaired samples simultaneously. Our key theoretical contribution proves the existence of an optimal reward threshold capable of separating winning and losing responses with high probability, which enables a principled pseudo-labeling of unpaired data. By leveraging these pseudo-labels, SSPO effectively distills latent preferences from large-scale unpaired data, thus maintaining human alignment while drastically reducing acquisition costs. Extensive experiments across datasets validate this remarkable data efficiency; for instance, SSPO trained with Mistral-7B-Instruct on just 1% of UltraFeedback consistently surpasses strong baselines trained on 10% of UltraFeedback.

**摘要翻译**:

偏好优化领域在将语言模型与人类偏好对齐方面做出了杰出贡献。尽管取得了这些进展，近期方法仍然严重依赖大量的成对（标注）反馈数据，导致巨大的资源消耗。为应对这些挑战，我们研究了半监督偏好优化问题，其核心思想是同时从少量成对偏好标签和大量未配对样本中学习。我们的关键理论贡献证明了一个最优奖励阈值的存在性，该阈值能够以高概率区分优选和劣选响应，从而实现对未配对数据的有原则的伪标签标注。通过利用这些伪标签，SSPO 有效地从大规模未配对数据中蒸馏出潜在偏好，在大幅降低获取成本的同时保持了人类对齐。跨数据集的大量实验验证了这一显著的数据效率；例如，使用 Mistral-7B-Instruct 仅在 UltraFeedback 的 1% 数据上训练的 SSPO，就持续超越了在 UltraFeedback 10% 数据上训练的强基线方法。
