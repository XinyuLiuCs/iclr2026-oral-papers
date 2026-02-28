# ICLR 2026 Oral Papers — 强化学习相关 | Reinforcement Learning Papers

从 223 篇 ICLR 2026 Oral 论文中筛选出与强化学习（Reinforcement Learning）相关的 **24 篇论文**，涵盖 RL 算法理论、LLM 强化学习训练（RLHF/RLVR）、RL 智能体框架、机器人/控制 RL、生成模型 RL 等方向。

---

## 2. Q-RAG: Long Context Multi‑Step Retrieval via Value‑Based Embedder Training

**Q-RAG：通过基于价值的嵌入器训练实现长上下文多步检索**

**OpenReview**: [https://openreview.net/forum?id=MS9nWFY7LG](https://openreview.net/forum?id=MS9nWFY7LG)

**Authors**: Artyom Sorokin (My own research), Nazar Buzun (Innopolis University), Aleksandr Anokhin (My own research), Egor KONSTANTINOVICH VEDERNIKOV (Idependent), Petr Anokhin (Lomonosov Moscow State University), Mikhail Burtsev (London Institute for Mathematical Sciences), Evgeny Burnaev (Applied AI Institute)

**Institutions**: My own research, Innopolis University, Idependent, Lomonosov Moscow State University, London Institute for Mathematical Sciences, Applied AI Institute

**Primary Area**: reinforcement learning

**Keywords**: Reinforcement Learning, RL, QA, Long-context, RAG, NLP

**Abstract**:

Retrieval-Augmented Generation (RAG) methods enhance LLM performance by efficiently filtering relevant context for LLMs, reducing hallucinations and inference cost. However, most existing RAG methods focus on single-step retrieval, which is often insufficient for answering complex questions that require multi-step search. Recently, multi-step retrieval approaches have emerged, typically involving the fine-tuning of small LLMs to perform multi-step retrieval. However, this type of fine-tuning is highly resource-intensive and does not enable the use of larger LLMs. In this work, we propose Q-RAG, a novel approach that fine-tunes the Embedder model for multi-step retrieval using reinforcement learning (RL). Q-RAG offers a competitive, resource-efficient alternative to existing multi-step retrieval methods for open-domain question answering and achieves state-of-the-art results on the popular long-context benchmarks Babilong and RULER for contexts up to 10M tokens.

**摘要翻译**:

检索增强生成（RAG）方法通过高效筛选与LLM相关的上下文来提升其性能，减少幻觉并降低推理成本。然而，现有的RAG方法大多侧重于单步检索，这对于需要多步搜索才能回答的复杂问题往往力不从心。近年来，多步检索方法相继涌现，通常需要对小型LLM进行微调以执行多步检索。然而，这种微调方式资源消耗大，且无法利用更大的LLM。本文提出Q-RAG，一种利用强化学习（RL）对嵌入器模型进行微调以实现多步检索的新方法。Q-RAG为开放域问答中的多步检索提供了一种具有竞争力且资源高效的替代方案，并在流行的长上下文基准测试Babilong和RULER上（上下文长度达1000万token）取得了最先进的结果。

**背景**: Retrieval-Augmented Generation (RAG) 是增强 LLM 性能的关键技术，通过从外部语料库中检索相关上下文来减少幻觉并降低推理成本。然而，现有 RAG 方法大多聚焦于单步检索，难以应对需要多步搜索的复杂问题。近期的多步检索方法通常需要对小型 LLM 进行微调，资源消耗大且无法扩展到更大的 LLM。

**动机**: 现有多步检索方法要么依赖知识图谱构建（推理慢），要么依赖 LLM Agent（对噪声检索敏感），要么需要对 LLM 本身进行昂贵的微调（如 R1-Searcher、Search-R1 等使用 GRPO）。作者希望找到一种资源高效的替代方案，只微调 Embedder 而非 LLM，从而可以搭配任意大小的 LLM（包括闭源模型）。

**创新点**:
1. 提出 Q-RAG，一种利用 temporal difference 强化学习训练多步检索 Agent 的新方法，仅微调 Embedder 模型而非 LLM
2. 在 BabiLong 和 RULER 等长上下文基准上达到 SOTA，支持最长 10M tokens 的上下文
3. 引入一种将时序信息融入多步 Embedder 的新机制，使检索过程具备时序推理能力，并在推理时能良好泛化到更长上下文

**开源代码**: 未提供（论文提到代码包含在补充材料中，但未给出公开链接）

---

## 6. Enhancing Generative Auto-bidding with Offline Reward Evaluation and Policy Search

**通过离线奖励评估与策略搜索增强生成式自动出价**

**OpenReview**: [https://openreview.net/forum?id=kMuQBgPIdg](https://openreview.net/forum?id=kMuQBgPIdg)

**Authors**: Zhiyu Mou (Alibaba Group), Yiqin Lv (National University of Defense Technology), Miao Xu (Alibaba Group), Cheems Wang (Tsinghua University), Yixiu Mao (Tsinghua University), Jinghao Chen (Tsinghua University), Qichen Ye (Alibaba Group), Chao Li (Chinese academic of science), Rongquan Bai (Alibaba Group), Chuan Yu (Alibaba Group), Jian Xu (Alibaba Group), Bo Zheng (Alibaba Group)

**Institutions**: Alibaba Group, National University of Defense Technology, Tsinghua University, Chinese academic of science

**Primary Area**: applications to robotics, autonomy, planning

**Keywords**: auto-bidding, offline reinforcement learning, generative decision making

**Abstract**:

Auto-bidding serves as a critical tool for advertisers to improve their advertising performance. Recent progress has demonstrated that AI-Generated Bidding (AIGB), which learns a conditional generative planner from offline data, achieves superior performance compared to typical offline reinforcement learning (RL)-based auto-bidding methods. However, existing AIGB methods still face a performance bottleneck due to their inherent inability to explore beyond the static offline dataset. To address this, we propose AIGB-Pearl (Planning with EvaluAtor via RL), a novel method that integrates generative planning and policy optimization. The core of AIGB-Pearl lies in constructing a trajectory evaluator for scoring generation quality and designing a provably sound KL-Lipschitz-constrained score maximization scheme to ensure safe and efficient generalization beyond the offline dataset. A practical algorithm incorporating the synchronous coupling technique is further devised to ensure the model regularity required by the proposed scheme. Extensive experiments on both simulated and real-world advertising systems demonstrate the state-of-the-art performance of our approach.

**摘要翻译**:

自动出价是广告主提升广告效果的关键工具。近期研究表明，AI生成出价（AIGB）通过从离线数据中学习条件生成规划器，取得了优于典型离线强化学习（RL）自动出价方法的性能。然而，现有AIGB方法由于无法探索静态离线数据集之外的空间，仍面临性能瓶颈。为此，我们提出AIGB-Pearl（通过RL进行评估器规划），一种融合生成规划与策略优化的新方法。AIGB-Pearl的核心在于构建轨迹评估器以评判生成质量，并设计具有可证明正确性的KL-Lipschitz约束得分最大化方案，以确保在离线数据集之外安全高效地泛化。进一步设计了融合同步耦合技术的实用算法，以保证所提方案所需的模型正则性。在模拟和真实广告系统上的大量实验验证了本方法的最先进性能。

**背景**: 自动出价（Auto-bidding）是在线广告领域的核心技术，旨在帮助广告主在动态竞争环境中自动优化出价策略。近期 AI-Generated Bidding (AIGB) 方法利用条件生成模型从离线数据中学习轨迹生成，性能优于传统离线强化学习方法。

**动机**: 现有 AIGB 方法面临性能瓶颈：其生成模型无法超越静态离线数据集进行探索。AIGB 的建模方式并未显式对齐广告性能优化目标，主要模仿离线数据中的良好轨迹，缺乏探索更高质量轨迹的能力。同时，将离线 RL 集成到 AIGB 中面临两大难题：缺少奖励信号来评估生成质量，以及缺少专门针对生成模型的离线 RL 算法及其理论保障。

**创新点**:
1. 提出 AIGB-Pearl，一种结合生成规划与策略优化的新方法，通过学习轨迹评估器（trajectory evaluator）来评分生成质量并驱动探索
2. 提出具有可证明次优性界的 KL-Lipschitz 约束分数最大化目标，确保在离线数据之外的安全高效探索
3. 设计了包含同步耦合（synchronous coupling）技术的实用算法，保证生成模型满足 Lipschitz 条件
4. 在模拟和真实广告系统上验证了 SOTA 性能

**开源代码**: 未提供

---

## 7. Why DPO is a Misspecified Estimator and How to Fix It

**为什么DPO是一个错误指定的估计器以及如何修复它**

**OpenReview**: [https://openreview.net/forum?id=btEiAfnLsX](https://openreview.net/forum?id=btEiAfnLsX)

**Authors**: Aditya Gopalan (Indian Institute of Science), Sayak Ray Chowdhury (Indian Institute of Technology, Kanpur), Debangshu Banerjee (Indian Institute of Science)

**Institutions**: Indian Institute of Science, Indian Institute of Technology, Kanpur

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Direct Preference Optimization, Reinforcement Learning, Reinforcement learning with human feedback

**TL;DR**: DPO is not sound by design and can fail due to misspecification, we fix it with careful analysis.

**TL;DR翻译**: DPO在设计上并非稳健的，可能因模型错误指定而失效，我们通过细致分析修复了这一问题。

**Abstract**:

Direct alignment algorithms such as Direct Preference Optimization (DPO) fine-tune models based on preference data, using only supervised learning instead of two-stage reinforcement learning with human feedback (RLHF). We show that DPO encodes a statistical estimation problem over reward functions induced by a parametric policy class. When the true reward function that generates preferences cannot be realized via the policy class, DPO becomes misspecified, resulting in failure modes such as preference order reversal, worsening of policy reward, and high sensitivity to the input preference data distribution. On the other hand, we study the local behavior of two-stage RLHF for a parametric class and relate it to a natural gradient step in policy space. Our fine-grained geometric characterization allows us to propose AuxDPO, which introduces additional auxiliary variables in the DPO loss function to help move towards the RLHF solution in a principled manner and mitigate the misspecification in DPO. We empirically demonstrate the superior performance of AuxDPO on didactic bandit settings as well as LLM alignment tasks.

**摘要翻译**:

直接对齐算法，如直接偏好优化（DPO），基于偏好数据对模型进行微调，仅使用监督学习而非两阶段的人类反馈强化学习（RLHF）。我们证明DPO编码了一个由参数化策略类诱导的奖励函数上的统计估计问题。当生成偏好的真实奖励函数无法通过策略类实现时，DPO便出现模型错误指定，导致偏好顺序逆转、策略奖励恶化以及对输入偏好数据分布的高度敏感等失效模式。另一方面，我们研究了参数化策略类的两阶段RLHF的局部行为，并将其与策略空间中的自然梯度步联系起来。我们的细粒度几何刻画使我们得以提出AuxDPO，它在DPO损失函数中引入额外的辅助变量，以原则性方式趋近RLHF解并缓解DPO中的模型错误指定问题。我们在教学性老虎机设置和LLM对齐任务上实证验证了AuxDPO的优越性能。

**背景**: Direct Preference Optimization (DPO) 是一种直接对齐算法，通过监督学习代替两阶段 RLHF 来基于偏好数据微调模型。DPO 的推导依赖于一个理想化假设：策略类是表格化的（tabular），即包含所有可能的输入输出条件概率分布。

**动机**: 现实中的 LLM 是参数化策略类（parametric policy classes），远非表格化。当真实奖励函数无法被策略类所隐式表达的奖励函数流形所实现时，DPO 就变成了一个误设定（misspecified）的统计估计问题。这会导致偏好排序反转、策略奖励恶化、对偏好数据分布高度敏感等失败模式。作者旨在系统性地揭示 DPO 在参数化策略下的几何结构，并提出修正方案。

**创新点**:
1. 证明对于一般参数化策略类，DPO 损失最小化等价于将真实奖励函数加权 KL 投影到策略类诱导的低维奖励流形上，揭示了 DPO 本质上是一个误设定的统计估计问题
2. 展示了 DPO 在误设定情况下的多种失败模式：偏好排序反转、整体奖励降低、对偏好数据频率的敏感性等
3. 通过研究两阶段 RLHF 的局部几何结构，提出 AuxDPO 算法，引入辅助受控自由度来缓解误设定问题，在 LLM 偏好对齐任务上一致性优于 DPO

**开源代码**: 未提供

---

## 9. SafeDPO: A Simple Approach to Direct Preference Optimization with Enhanced Safety

**SafeDPO：一种增强安全性的简洁直接偏好优化方法**

**OpenReview**: [https://openreview.net/forum?id=PJdw4VBsXD](https://openreview.net/forum?id=PJdw4VBsXD)

**Authors**: Geon-Hyeong Kim (LG AI Research), Youngsoo Jang (Ulsan National Institute of Science and Technology), Yu Jin Kim (LG AI Research), Byoungjip Kim (LG AI Research), Honglak Lee (University of Michigan - Ann Arbor), Kyunghoon Bae (LG AI Research), Moontae Lee (LG Corporation)

**Institutions**: LG AI Research, Ulsan National Institute of Science and Technology, University of Michigan - Ann Arbor, LG Corporation

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Safety Alignment, LLM Fine-tuning, Preferences, Large Language Models, AI Safety

**TL;DR**: This work introduces a simple yet principled approach for directly optimizing the safety alignment objective during policy learning

**TL;DR翻译**: 本工作提出了一种简洁而有原则的方法，在策略学习过程中直接优化安全对齐目标。

**Abstract**:

As Large Language Models (LLMs) are increasingly deployed in real-world applications, balancing both helpfulness and safety has become a central challenge. A natural approach is to incorporate safety constraints into Reinforcement Learning from Human Feedback (RLHF), where recent studies have shown promising progress. However, these methods often rely on auxiliary networks or multi-stage pipelines, thereby increasing complexity. In this work, we revisit the safety alignment objective itself and demonstrate that it admits a closed-form solution, yielding a theoretically grounded and provably equivalent reformulation that enables a direct and tractable optimization procedure. Building on this insight, we propose SafeDPO, a lightweight method derived from this formulation, which preserves the optimality of the underlying safety-constrained objective while requiring only one additional hyperparameter and minimal modifications to existing preference-based training methods. At the same time, it eliminates the need for reward models, cost models, and online sampling. Despite its simplicity, SafeDPO achieves comparable or superior results to state-of-the-art safety alignment methods in both theoretical soundness and empirical performance. Experiments on the PKU-SafeRLHF-30K benchmark show that SafeDPO consistently improves safety while maintaining competitive helpfulness. Ablation studies further show that the additional hyperparameter provides a flexible mechanism to enhance safety without altering the theoretical optimum, and confirm that SafeDPO scales reliably to LLMs with up to 13B parameters. Overall, our results highlight that a simple, theory-driven objective can provide a lightweight yet effective solution for safety alignment in practice.

**摘要翻译**:

随着大语言模型（LLMs）在实际应用中的日益广泛部署，平衡有用性与安全性已成为核心挑战。一种自然的方法是将安全约束纳入人类反馈强化学习（RLHF），近期研究在此方向上取得了令人鼓舞的进展。然而，这些方法往往依赖辅助网络或多阶段流水线，增加了复杂性。本文重新审视安全对齐目标本身，证明了它具有闭式解，从而得到一个有理论基础且可证明等价的重新表述，使直接且可处理的优化过程成为可能。基于这一洞察，我们提出SafeDPO——一种从该表述推导出的轻量级方法，在保持底层安全约束目标最优性的同时，仅需一个额外超参数和对现有基于偏好训练方法的最小改动。同时，它消除了对奖励模型、代价模型和在线采样的需求。尽管简洁，SafeDPO在理论严谨性和实证性能上均达到了与最先进安全对齐方法相当或更优的结果。在PKU-SafeRLHF-30K基准上的实验表明，SafeDPO在保持有竞争力的有用性的同时持续改善安全性。消融研究进一步表明，该额外超参数提供了一种灵活机制来增强安全性而不改变理论最优值，并证实SafeDPO可以可靠地扩展到参数规模高达13B的LLM。总体而言，我们的结果突显出一个简洁的、理论驱动的目标函数能够在实践中为安全对齐提供轻量而有效的解决方案。

**背景**: 随着 LLM 在现实场景中广泛部署，平衡有用性（helpfulness）和安全性（safety）成为核心挑战。现有方法如 SafeRLHF、SACPO、MoCAN 等通过辅助模型、多阶段流水线或松弛约束目标来将安全信息纳入偏好训练，但引入了额外复杂性。

**动机**: 现有安全对齐方法需要额外的奖励模型、成本模型和在线采样，增加了计算和概念开销。作者重新审视安全对齐目标，发现该约束优化问题存在闭式解，可以直接优化而无需辅助模型或多阶段过程，仅需偏好数据和二元安全指示符即可训练。

**创新点**:
1. 推导出安全对齐目标的闭式可处理公式，消除了对替代松弛或辅助模型的需求
2. 提出 SafeDPO，一种轻量级训练方法，将安全指示符融入偏好优化中，实现直接的单阶段策略更新，仅需一个额外超参数
3. 理论证明 SafeDPO 保持了底层安全约束目标的最优性，同时提供可控的安全增强边际
4. 在 PKU-SafeRLHF-30K 基准上验证了 SafeDPO 在提升安全性的同时保持竞争力的有用性，并扩展到 13B 参数规模

**开源代码**: 未提供（使用了 HuggingFace 上的公开数据集和模型：PKU-Alignment/PKU-SafeRLHF-30K 等）

---

## 11. Optimistic Task Inference for Behavior Foundation Models

**行为基础模型的乐观任务推断**

**OpenReview**: [https://openreview.net/forum?id=m5byThUSNE](https://openreview.net/forum?id=m5byThUSNE)

**Authors**: Thomas Rupf (ETHZ - ETH Zurich), Marco Bagatella (Max Planck Institute for Intelligent Systems, Max Planck Institute for Intelligent Systems), Marin Vlastelica (ETHZ - ETH Zurich), Andreas Krause (ETH Zurich)

**Institutions**: ETHZ - ETH Zurich, Max Planck Institute for Intelligent Systems, Max Planck Institute for Intelligent Systems, ETH Zurich

**Primary Area**: reinforcement learning

**Keywords**: Behavior Foundation Models, Zero-Shot Reinforcement Learning, Deep Reinforcement Learning, Fast Adaptation

**TL;DR**: We propose an algorithm for fast online task inference in behavior foundation models.

**TL;DR翻译**: 我们提出了一种用于行为基础模型中快速在线任务推断的算法。

**Abstract**:

Behavior Foundation Models (BFMs) are capable of retrieving high-performing policy for any reward function specified directly at test-time, commonly referred to as zero-shot reinforcement learning (RL). While this is a very efficient process in terms of compute, it can be less so in terms of data: as a standard assumption, BFMs require computing rewards over a non-negligible inference dataset, assuming either access to a functional form of rewards, or significant labeling efforts. To alleviate these limitations, we tackle the problem of task inference purely through interaction with the environment at test-time. We propose OpTI-BFM, an optimistic decision criterion that directly models uncertainty over reward functions and guides BFMs in data collection for task inference. Formally, we provide a regret bound for well-trained BFMs through a direct connection to upper-confidence algorithms for linear bandits. Empirically, we evaluate OpTI-BFM on established zero-shot benchmarks, and observe that it enables successor-features-based BFMs to identify and optimize an unseen reward function in a handful of episodes with minimal compute overhead.

**摘要翻译**:

行为基础模型（BFMs）能够在测试时直接为任意指定的奖励函数检索高性能策略，这通常被称为零样本强化学习（RL）。虽然这一过程在计算上非常高效，但在数据方面则不尽然：作为标准假设，BFMs需要在规模不可忽略的推断数据集上计算奖励，这要求获得奖励函数的显式形式或进行大量标注。为缓解这些限制，我们解决了纯粹通过测试时与环境交互进行任务推断的问题。我们提出OpTI-BFM，一种乐观决策准则，直接建模奖励函数上的不确定性，并引导BFMs进行任务推断所需的数据收集。在理论上，我们通过与线性老虎机的上置信算法的直接联系，为训练良好的BFMs提供了遗憾界。在实证上，我们在成熟的零样本基准上评估了OpTI-BFM，观察到它使基于后继特征的BFMs能够在极少的回合数和最小的计算开销下识别和优化未见过的奖励函数。

**背景**: Behavior Foundation Models (BFMs) 能够在测试时对任意奖励函数直接检索高性能策略，即 zero-shot 强化学习。大多数 BFMs 基于 Universal Successor Features (USFs)，通过状态特征的线性关系实现零样本策略评估和改进。

**动机**: 虽然 BFMs 在计算上高效，但在数据需求方面仍有严格要求：需要在推理数据集上计算奖励，假设可以获得奖励函数的解析形式或大量标注。当预训练数据集不可用或标注成本高时（如从像素预训练），标准离线任务推断流程不再适用。作者希望通过在部署时与环境交互来主动收集少量数据进行任务推断，减少对预训练数据集和大量标注的依赖。

**创新点**:
1. 提出 OpTI-BFM，一种乐观决策准则，直接建模奖励函数上的不确定性并引导 BFMs 进行数据收集
2. 通过与线性 bandit 的 upper-confidence 算法的直接关联，为训练良好的 BFMs 提供了 regret bound 理论保证
3. 在 DeepMind Control Suite 的 zero-shot 基准上，OpTI-BFM 仅需少量 episode 即可正确识别任务，最终匹配或超越标准离线奖励推断流程在更多数据下的性能

**开源代码**: https://github.com/ThomasRupf/opti-bfm

---

## 22. LoongRL: Reinforcement Learning for Advanced Reasoning over Long Contexts

**LoongRL：面向长上下文高级推理的强化学习**

**OpenReview**: [https://openreview.net/forum?id=o29E01Q6bv](https://openreview.net/forum?id=o29E01Q6bv)

**Authors**: Siyuan Wang (Shanghai Jiaotong University), Gaokai Zhang (Carnegie Mellon University), Li Lyna Zhang (Microsoft Research Asia), Ning Shang (Microsoft), Fan Yang (Research, Microsoft), Dongyao Chen (Shanghai Jiaotong University), Mao Yang (Peking University)

**Institutions**: Shanghai Jiaotong University, Carnegie Mellon University, Microsoft Research Asia, Microsoft, Research, Microsoft, Peking University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Long Context Reasoning, Reinforcement Learning

**Abstract**:

Reasoning over long contexts is essential for large language models. While reinforcement learning (RL) enhances short-context reasoning by inducing "Aha" moments in chain-of-thought, the advanced thinking patterns required for long-context reasoning remain largely unexplored, and high-difficulty RL data are scarce. In this paper, we introduce LoongRL, a data-driven RL method for advanced long-context reasoning. Central to LoongRL is KeyChain, a synthesis approach that transforms short multi-hop QA into high-difficulty long-context tasks by inserting UUID chains that hide the true question among large collections of distracting documents. Solving these tasks requires the model to trace the correct chain step-by-step, identify the true question, retrieve relevant facts and reason over them to answer correctly. RL training on KeyChain data induces an emergent plan-retrieve-reason-recheck reasoning pattern that generalizes far beyond training length. Models trained at 16K effectively solve 128K tasks without prohibitive full-length RL rollout costs. On Qwen2.5-7B and 14B, LoongRL substantially improves long-context multi-hop QA accuracy by +23.5% and +21.1% absolute gains. The resulting LoongRL-14B reaches a score of 74.2, rivaling much larger frontier models such as o3-mini (74.5) and DeepSeek-R1 (74.9). It also improves long-context retrieval, passes all 128K needle-in-a-haystack stress tests, and preserves short-context reasoning capabilities. Code is available at https://loongrl.github.io.

**摘要翻译**:

长上下文推理对大语言模型至关重要。虽然强化学习（RL）通过在思维链中诱导"顿悟"时刻来增强短上下文推理，但长上下文推理所需的高级思维模式在很大程度上仍未被探索，且高难度的RL数据十分稀缺。本文介绍了LoongRL，一种面向高级长上下文推理的数据驱动RL方法。LoongRL的核心是KeyChain，一种将短多跳问答转化为高难度长上下文任务的合成方法，通过插入UUID链将真实问题隐藏在大量干扰文档中。解决这些任务要求模型逐步追踪正确的链条，识别真正的问题，检索相关事实并进行推理以正确回答。在KeyChain数据上的RL训练诱导出涌现的"规划-检索-推理-复查"推理模式，该模式可泛化到远超训练长度的范围。在16K上训练的模型能有效解决128K任务，而无需承担高昂的全长度RL展开成本。在Qwen2.5-7B和14B上，LoongRL将长上下文多跳问答准确率分别提升了+23.5%和+21.1%的绝对增益。最终的LoongRL-14B达到74.2分，可与o3-mini（74.5）和DeepSeek-R1（74.9）等更大的前沿模型相媲美。它还改善了长上下文检索，通过了所有128K大海捞针压力测试，并保持了短上下文推理能力。代码可在 https://loongrl.github.io 获取。

**背景**: 长上下文推理对 LLM 至关重要。近期研究表明，强化学习可以通过在 chain-of-thought 中诱发「Aha moment」来增强短上下文推理能力。然而，长上下文推理所需的高级思维模式尚未被充分探索，且高难度的 RL 训练数据十分稀缺。

**动机**: 现有 RL 方法主要针对短上下文输入，依赖模型内部知识。长上下文推理不仅需要推理能力，还需要从大量外部上下文中检索和定位信息。面临三大挑战：(1) 缺少不能仅靠检索解决的高难度长上下文问题；(2) 将 RL rollout 从短输入扩展到 128K 上下文的计算和内存成本过高；(3) 仅在长上下文数据上训练可能损害短上下文和通用推理能力。

**创新点**:
1. 提出 KeyChain 数据合成方法，通过插入 UUID 链将短多跳 QA 转化为高难度长上下文任务，迫使模型逐步追踪链条、识别真实问题、检索相关事实并推理
2. RL 训练在 KeyChain 数据上涌现出 plan-retrieve-reason-recheck 推理模式，该模式可泛化到远超训练长度的上下文（16K 训练 -> 128K 推理）
3. 在 Qwen2.5-7B/14B 上，LoongRL 将长上下文多跳 QA 准确率分别提升 +23.5% 和 +21.1%，LoongRL-14B 达到 74.2 分，媲美 o3-mini (74.5) 和 DeepSeek-R1 (74.9)

**开源代码**: https://loongrl.github.io/

---

## 40. AgentGym-RL: An Open-Source Framework to Train LLM Agents for Long-Horizon Decision Making via Multi-Turn RL

**AgentGym-RL：通过多轮强化学习训练 LLM 智能体进行长时域决策的开源框架**

**OpenReview**: [https://openreview.net/forum?id=ZgCCDwcGwn](https://openreview.net/forum?id=ZgCCDwcGwn)

**Authors**: Zhiheng Xi (Fudan University), Jixuan Huang (Fudan University), Chenyang Liao (Fudan University), Baodai Huang (Fudan University), Jiaqi Liu (Fudan University), Honglin Guo (Fudan University), yajie yang (Fudan University), Rui Zheng (Fudan University), Junjie Ye (Fudan University), Jiazheng Zhang (Fudan University), Wenxiang Chen (Fudan University), Wei He (Fudan University), Yiwen Ding (Fudan University), Guanyu Li (Fudan University), Zehui Chen (ByteDance Inc.), Zhengyin Du (ByteDance), Xuesong Yao (ByteDance Inc.), Yufei Xu (ByteDance Inc.), Jiecao Chen (ByteDance Inc.), Tao Gui (Fudan University), Zuxuan Wu (Fudan University), Qi Zhang (Fudan University), Xuanjing Huang (Fudan University), Yu-Gang Jiang (Fudan University)

**Institutions**: Fudan University, ByteDance Inc., ByteDance

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: large language model, LLM-based agent, decision-making

**TL;DR**: We present AgentGym-RL, a unified open-source framework for training LLM agents from scratch across diverse and realistic environments, and propose ScalingInter-RL, a staged training strategy for stable long-horizon RL training.

**TL;DR翻译**: 我们提出了 AgentGym-RL，一个统一的开源框架，用于在多样化的真实环境中从零训练 LLM 智能体，并提出了 ScalingInter-RL，一种实现稳定长时域强化学习训练的分阶段训练策略。

**Abstract**:

Training LLM agents for complex multi-turn decision-making tasks requires extensive exploration within their environment, with reinforcement learning (RL) as a natural way. However, the open-source community currently lacks a unified RL framework capable of training agents from scratch across diverse and realistic environments. To bridge this gap, we introduce AgentGym-RL, a modular and decoupled framework specifically designed for RL-based agent in multi-turn decision-making tasks. It offers high flexibility and extensibility, supports mainstream RL algorithms, and spans a broad range of real-world scenarios. To effectively train agents for challenging tasks, we argue that they are required to expand external interactions with the environment, rather than relying solely on internal reasoning. Nevertheless, training agents for long-horizon interaction with vanilla methods often faces challenges like training instability. To this end, we propose ScalingInter-RL, a staged training approach for stable long-horizon RL training. It starts with short-horizon interaction to establish foundational policies and progressively expands them to encourage deeper exploration. Extensive experiments show that agents trained with our method achieve performance on par with—or even surpass—commercial counterparts like OpenAI o3 and Gemini-2.5-Pro across 27 tasks in diverse environments. We share key insights and release the full framework, including code and datasets, to empower the community in building the next generation of intelligent agents. Our framework is available at https://github.com/WooooDyy/AgentGym-RL.

**摘要翻译**:

训练 LLM 智能体完成复杂的多轮决策任务需要在其环境中进行大量探索，而强化学习（RL）是一种自然的方式。然而，开源社区目前缺乏一个能够在多样化真实环境中从零训练智能体的统一 RL 框架。为填补这一空白，我们提出了 AgentGym-RL，一个专门为基于 RL 的多轮决策任务智能体设计的模块化解耦框架。该框架具有高灵活性和可扩展性，支持主流 RL 算法，并涵盖广泛的真实场景。为有效训练智能体应对具有挑战性的任务，我们认为它们需要扩展与环境的外部交互，而非仅依赖内部推理。然而，使用普通方法训练长时域交互的智能体往往面临训练不稳定等挑战。为此，我们提出了 ScalingInter-RL，一种实现稳定长时域 RL 训练的分阶段训练方法。它从短时域交互开始建立基础策略，并逐步扩展以鼓励更深层次的探索。大量实验表明，使用我们方法训练的智能体在 27 个不同环境的任务中达到了与 OpenAI o3 和 Gemini-2.5-Pro 等商业产品相当甚至超越的性能。我们分享了关键见解并发布了完整框架（包括代码和数据集），以赋能社区构建下一代智能体。我们的框架可在 https://github.com/WooooDyy/AgentGym-RL 获取。

**背景**: 随着 LLM 从聊天机器人扩展到自主 Agent 来完成长期决策任务，强化学习成为通过与环境交互来训练 LLM Agent 的自然选择。然而，开源社区缺乏统一的 RL 框架来在多样化和现实环境中从头训练 Agent。

**动机**: 现有工作在将 RL 方法扩展到多轮交互 LLM Agent 方面受限于任务复杂度有限和环境多样性不足。直接训练 Agent 进行长视野交互常面临训练不稳定的问题。需要一个模块化、解耦的框架来支持主流 RL 算法并覆盖广泛的真实场景。

**创新点**:
1. 提出 AgentGym-RL，一个模块化解耦的统一框架，专为多轮交互决策任务中的 RL Agent 训练设计，支持主流 RL 算法，覆盖 Web 导航、深度搜索、数字游戏、具身任务和科学任务等多种场景
2. 提出 ScalingInter-RL，一种分阶段训练方法，从短视野交互开始建立基础策略，逐步扩展以鼓励更深层探索，解决长视野 RL 训练的不稳定性问题
3. 在 5 个场景 27 个任务上，Qwen2.5-7B 平均提升 33.65 分，匹配甚至超越 OpenAI o3 和 Gemini-2.5-Pro 等商业模型

**开源代码**: https://github.com/WooooDyy/AgentGym-RL

---

## 45. cadrille: Multi-modal CAD Reconstruction with Reinforcement Learning

**cadrille：基于强化学习的多模态CAD重建**

**OpenReview**: [https://openreview.net/forum?id=w2tnhhMbXv](https://openreview.net/forum?id=w2tnhhMbXv)

**Authors**: Maksim Kolodiazhnyi (Moscow State University, Lomonosov Moscow State University), Denis Tarasov (ETHZ - ETH Zurich), Dmitrii Zhemchuzhnikov (Lomonosov Moscow State University), Alexander Nikulin (Lomonosov Moscow State University), Ilya Zisman (Innopolis University), Anna Vorontsova (Occipital Inc.), Anton Konushin (Lomonosov Moscow State University), Vladislav Kurenkov (Innopolis University), Danila Rukhovich (Institute of Mechanics)

**Institutions**: Moscow State University, Lomonosov Moscow State University, ETHZ - ETH Zurich, Innopolis University, Occipital Inc., Institute of Mechanics

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: CAD, 3D reconstruction, LLM, VLM, point cloud, DPO, GRPO

**TL;DR**: A single LLM is capable of reconstructing 3D CAD from point clouds, images, and text. Additionally, online RL significantly boosts reconstruction quality.

**TL;DR翻译**: 单个LLM即可从点云、图像和文本重建3D CAD模型。此外，在线强化学习显著提升了重建质量。

**Abstract**:

Computer-Aided Design (CAD) plays a central role in engineering and manufacturing, making it possible to create precise and editable 3D models. Using a variety of sensor or user-provided data as inputs for CAD reconstruction can democratize access to design applications. However, most existing methods focus on a single input modality: point clouds, images, or texts, which limits their generalizability and robustness, while few multimodal approaches struggle to deliver competitive quality. Leveraging advances in vision-language models (VLM), we propose $\texttt{cadrille}$, a multimodal CAD reconstruction model that takes inputs of three modalities and outputs executable Python code for CAD reconstruction. Inspired by large language model (LLM) training paradigm, we adopt a two-stage pipeline: supervised fine-tuning (SFT) on large-scale procedurally generated data, followed by reinforcement learning (RL) fine-tuning using online feedback, obtained programatically. In the DeepCAD benchmark, our SFT model outperforms existing single-modal approaches in all three input modalities simultaneously. More importantly, after RL fine-tuning, $\texttt{cadrille}$ sets new state-of-the-art in as many as 10 benchmarks across three modalities and four datasets, including a real-world one.

**摘要翻译**:

计算机辅助设计（CAD）在工程和制造领域发挥着核心作用，使创建精确且可编辑的3D模型成为可能。利用各种传感器或用户提供的数据作为CAD重建的输入，可以降低设计应用的使用门槛。然而，现有方法大多只关注单一输入模态：点云、图像或文本，这限制了其泛化能力和鲁棒性，而少数多模态方法也难以达到有竞争力的质量。借助视觉-语言模型（VLM）的最新进展，我们提出了cadrille，一个接受三种模态输入并输出可执行Python代码以进行CAD重建的多模态模型。受大语言模型（LLM）训练范式的启发，我们采用两阶段流程：首先在大规模程序化生成数据上进行监督微调（SFT），然后利用程序化获取的在线反馈进行强化学习（RL）微调。在DeepCAD基准上，我们的SFT模型在三种输入模态上同时优于现有的单模态方法。更重要的是，经过RL微调后，cadrille在三种模态和四个数据集（包括一个真实世界数据集）的多达10个基准上刷新了最优结果。

**背景**: Computer-Aided Design (CAD) 是工程和制造业的核心，用于创建精确可编辑的 3D 模型。CAD 重建旨在从扫描对象直接生成 CAD 模型。现有方法大多专注于单一输入模态（点云、图像或文本），限制了泛化性和鲁棒性，而少数多模态方法难以提供有竞争力的质量。

**动机**: 现有 CAD 重建方法面临泛化问题：手工制作的 CAD 数据集小且多样性有限，而在程序化生成数据上训练的模型难以迁移到真实世界。此前的 RL 微调工作在同一数据集上进行监督和 RL 微调，无法弥合训练与测试数据之间的差距。作者希望利用 VLM 的进展构建多模态 CAD 重建模型，并通过创新的两阶段训练范式（大规模程序化数据 SFT + 手工数据 RL 微调）来提升泛化能力。

**创新点**:
1. 提出 CADRILLE，一个基于 VLM 的多模态 CAD 重建模型，可处理点云、图像和文本三种输入模态，输出可执行的 Python 代码
2. 首次证明 RL 微调可以改善多模态 CAD 重建，采用程序化生成数据进行 SFT、手工数据进行 RL 微调的创新训练范式
3. 以单一模型在三种输入模态和四个数据集（DeepCAD、Fusion360、CC3D、Omni-CAD）共 10 个基准上同时达到 SOTA

**开源代码**: https://github.com/col14m/cadrille

---

## 70. In-The-Flow Agentic System Optimization for Effective Planning and Tool Use

**流内智能体系统优化：实现有效规划与工具使用**

**OpenReview**: [https://openreview.net/forum?id=Mf5AleTUVK](https://openreview.net/forum?id=Mf5AleTUVK)

**Authors**: Zhuofeng Li (Texas A&M University - College Station), Haoxiang Zhang (University of California, San Diego), Seungju Han (Computer Science Department, Stanford University), Sheng Liu (Stanford University), Jianwen Xie, Yu Zhang (Texas A&M University - College Station), Yejin Choi (Computer Science Department, Stanford University), James Zou (Stanford University), Pan Lu (Stanford University)

**Institutions**: Texas A&M University - College Station, University of California, San Diego, Computer Science Department, Stanford University, Stanford University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Reinforcement Learning, Large Language Models, Agentic Systems, Tool Use, Planning, On-policy Optimization, Sparse Rewards

**TL;DR**: We introduce AgentFlow, a trainable agentic system, and Flow-GRPO, an on-policy RL algorithm that optimizes the planner "in-the-flow" by broadcasting a final outcome reward to all steps, enabling effective long-horizon planning and tool use.

**TL;DR翻译**: 我们提出了AgentFlow（一个可训练的智能体系统）和Flow-GRPO（一种在策略强化学习算法），用于优化整个智能体系统的规划和工具使用。

**Abstract**:

Outcome-driven reinforcement learning has advanced reasoning in large language models (LLMs), but prevailing tool-augmented approaches train a single, monolithic policy that interleaves thoughts and tool calls under full context; this scales poorly with long horizons and diverse tools and generalizes weakly to new scenarios. Agentic systems offer a promising alternative by decomposing work across specialized modules, yet most remain training-free or rely on offline training decoupled from the live dynamics of multi-turn interaction. We introduce AgentFlow, a trainable, *in-the-flow* agentic framework that coordinates four modules (planner, executor, verifier, generator) through an evolving memory and directly optimizes its planner inside the multi-turn loop. To train on-policy in live environments, we propose *Flow-based Group Refined Policy Optimization* (Flow-GRPO), which tackles long-horizon, sparse-reward credit assignment by converting multi-turn optimization into a sequence of tractable single-turn policy updates. It broadcasts a single, verifiable trajectory-level outcome to every turn to align local planner decisions with global success and stabilizes learning with group-normalized advantages. Across ten benchmarks, AgentFlow with a 7B-scale backbone outperforms top-performing baselines with average accuracy gains of 14.9% on search, 14.0% on agentic, 14.5% on mathematical, and 4.1% on scientific tasks, even surpassing larger proprietary models like GPT-4o. Further analyses confirm the benefits of in-the-flow optimization, showing improved planning, enhanced tool-calling reliability, and positive scaling with model size and reasoning turns.

**摘要翻译**:

结果驱动的强化学习已推进了大语言模型（LLM）中的推理能力，但主流的工具增强方法训练单一的整体策略，在完整上下文下交织思考和工具调用；这种方式在长期任务和多样化工具场景下扩展性差，且难以泛化到新场景。智能体系统提供了一种有前景的替代方案，通过将工作分解到专门模块中，然而大多数系统仍然是无训练的，或依赖于与多轮交互实时动态解耦的离线训练。我们引入了AgentFlow，一种可训练的*流内*智能体框架，通过不断演进的记忆协调四个模块（规划器、执行器、验证器、生成器），并直接在多轮循环中优化其规划器。为了在实时环境中进行在策略训练，我们提出了*基于流的组精炼策略优化*（Flow-GRPO），通过将多轮优化转换为一系列可处理的单轮策略更新来解决长期、稀疏奖励的信用分配问题。它将单个可验证的轨迹级结果广播到每一轮，以使局部规划决策与全局成功对齐，并通过组归一化优势来稳定学习。在十个基准测试上，使用7B规模骨干的AgentFlow优于表现最佳的基线，在搜索任务上平均准确率提升14.9%，在智能体任务上提升14.0%，在数学任务上提升14.5%，在科学任务上提升4.1%，甚至超越了GPT-4o等更大的闭源模型。进一步分析证实了流内优化的益处，展示了改进的规划、增强的工具调用可靠性以及随模型规模和推理轮数的正向扩展。

**背景**: 基于结果驱动的强化学习已推动了大语言模型(LLM)的推理能力发展，但现有的工具增强方法通常训练一个单一的整体策略(monolithic policy)，将思维与工具调用交织在完整上下文中进行；这种方式在长期任务和多样化工具场景下扩展性差，且在新场景中泛化能力弱。智能体系统(agentic systems)通过将工作分配给专门化模块提供了一种有前景的替代方案，但大多数系统仍然是无需训练的(training-free)，或依赖与实时多轮交互动态解耦的离线训练。

**动机**: 作者旨在弥合可训练但单一的推理模型与灵活但静态的智能体系统之间的差距。核心挑战在于：如何在具有稀疏奖励的工具集成智能体系统中学习长期推理。现有智能体系统依赖手工逻辑或提示启发式方法进行模块协调，无法从下游成功或失败中有效学习，导致信用分配(credit assignment)困难、适应性脆弱以及动态环境中的编排效率低下。

**创新点**:
1. 提出 AgentFlow，一个可训练的流内(in-the-flow)智能体框架，包含四个专门化模块(planner、executor、verifier、generator)，通过共享的动态记忆(evolving memory)协调，并直接在多轮循环内在线优化其 planner
2. 提出 Flow-GRPO(Flow-based Group Refined Policy Optimization)算法，将多轮强化学习优化转化为一系列可处理的单轮策略更新，通过将单一可验证的轨迹级结果广播到每一轮来解决长期稀疏奖励的信用分配问题
3. 在十个基准测试上，使用 7B 规模骨干模型的 AgentFlow 在搜索(+14.9%)、智能体(+14.0%)、数学(+14.5%)和科学(+4.1%)任务上显著超越顶级基线，甚至超过 GPT-4o 等更大的专有模型

**开源代码**: https://agentflow.stanford.edu

---

## 99. Mean Flow Policy with Instantaneous Velocity Constraint for One-step Action Generation

**具有瞬时速度约束的平均流策略用于单步动作生成**

**OpenReview**: [https://openreview.net/forum?id=mIeKe74W43](https://openreview.net/forum?id=mIeKe74W43)

**Authors**: Guojian Zhan (Tsinghua University), Letian Tao (Tsinghua University), Pengcheng Wang (University of California, Berkeley), Yixiao Wang (University of California, Berkeley), Yuxin Chen (University of California, Berkeley), Yiheng Li (University of California, Berkeley), Hongyang Li (University of Hong Kong), Masayoshi Tomizuka (University of California Berkeley), Shengbo Eben Li (Tsinghua University)

**Institutions**: Tsinghua University, University of California, Berkeley, University of Hong Kong, University of California Berkeley

**Primary Area**: reinforcement learning

**Keywords**: Reinforcement learning, Generative policy

**TL;DR**: We introduce the mean velocity policy, a new RL policy that, along with a novel instantaneous velocity constraint, achieves state-of-the-art performance and the fastest training and inference speed.

**TL;DR翻译**: 我们提出了平均速度策略，一种新的强化学习策略，结合新颖的瞬时速度约束，实现了最先进的性能以及最快的训练和推理速度。

**Abstract**:

Learning expressive and efficient policy functions is a promising direction in reinforcement learning (RL). While flow-based policies have recently proven effective in modeling complex action distributions with a fast deterministic sampling process, they still face a trade-off between expressiveness and computational burden, which is typically controlled by the number of flow steps. In this work, we propose mean velocity policy (MVP), a new generative policy function that models the mean velocity field to achieve the fastest one-step action generation. To ensure its high expressiveness, an instantaneous velocity constraint (IVC) is introduced on the mean velocity field during training. We theoretically prove that this design explicitly serves as a crucial boundary condition, thereby improving learning accuracy and enhancing policy expressiveness. Empirically, our MVP achieves state-of-the-art success rates across several challenging robotic manipulation tasks from Robomimic and OGBench. It also delivers substantial improvements in training and inference speed over existing flow-based policy baselines.

**摘要翻译**:

学习富有表达力且高效的策略函数是强化学习（RL）中一个很有前景的方向。虽然基于流的策略近来已被证明能够通过快速确定性采样过程有效建模复杂动作分布，但它们仍面临表达力与计算负担之间的权衡，这通常由流步数控制。本文提出了平均速度策略（MVP），一种新的生成式策略函数，通过建模平均速度场来实现最快的单步动作生成。为确保其高表达力，我们在训练期间对平均速度场引入了瞬时速度约束（IVC）。我们从理论上证明了该设计显式地充当关键的边界条件，从而提高了学习精度并增强了策略表达力。在实验上，我们的 MVP 在 Robomimic 和 OGBench 的多项具有挑战性的机器人操作任务上实现了最先进的成功率，同时在训练和推理速度上相比现有基于流的策略基线取得了显著提升。

**背景**: 在强化学习中学习具有表达力且高效的策略函数是一个重要方向。基于流匹配(flow matching)的策略近来被证明在建模复杂动作分布方面有效，但它们仍面临表达力与计算负担之间的权衡，通常由流步数(flow steps)控制。现有的生成式策略（如扩散模型和流匹配）依赖从噪声到动作的迭代多步采样，这带来了显著的训练和推理开销。

**动机**: 核心问题是：能否将生成式策略的表达力与单步动作生成的效率统一起来？现有流策略学习瞬时速度场(instantaneous velocity field)，需要多步迭代采样。而均值速度场(mean velocity field)可以实现从噪声到动作的直接单步映射，但其学习难度更高，因为其控制方程(ODE)缺乏显式边界条件，导致多解问题，影响学习精度和策略表达力。

**创新点**:
1. 提出 Mean Velocity Policy(MVP)，一种新的基于流的策略函数，通过建模均值速度场实现最快的单步动作生成，在保持生成式策略表达力的同时消除多步采样开销
2. 设计 Instantaneous Velocity Constraint(IVC)训练增强技术，通过在训练中对均值速度场施加瞬时速度约束，显式提供边界条件，从而提高学习精度和策略表达力
3. 在 Robomimic 和 OGBench 两个机器人操作基准上达到了 state-of-the-art 的成功率，同时在训练和推理速度上相比现有流策略基线有大幅提升

**开源代码**: 未提供

---

## 121. Exploratory Diffusion Model for Unsupervised Reinforcement Learning

**用于无监督强化学习的探索性扩散模型**

**OpenReview**: [https://openreview.net/forum?id=k0Kb1ynFbt](https://openreview.net/forum?id=k0Kb1ynFbt)

**Authors**: Chengyang Ying (Tsinghua University, Tsinghua University), Huayu Chen (Tsinghua University), Xinning Zhou (Tsinghua University, Tsinghua University), Zhongkai Hao (Tsinghua University), Hang Su (Tsinghua University), Jun Zhu (Tsinghua University)

**Institutions**: Tsinghua University, Tsinghua University, Tsinghua University

**Primary Area**: reinforcement learning

**Keywords**: reinforcement learning, diffusion policy, unsupervised reinforcement learning, exploration

**TL;DR**: We propose Exploratory Diffusion Model (ExDM), boosting unsupervised exploration and few-shot fine-tuning by diffusion models.

**TL;DR翻译**: 我们提出了探索性扩散模型（ExDM），通过扩散模型提升无监督探索和小样本微调性能。

**Abstract**:

Unsupervised reinforcement learning (URL) pre-trains agents by exploring diverse states in reward-free environments, aiming to enable efficient adaptation to various downstream tasks. Without extrinsic rewards, prior methods rely on intrinsic objectives, but heterogeneous exploration data demand strong modeling capacity for both intrinsic reward design and policy learning. We introduce the **Ex**ploratory **D**iffusion **M**odel (**ExDM**), which leverages the expressive power of diffusion models to fit diverse replay-buffer distributions, thus providing accurate density estimates and a score-based intrinsic reward that drives exploration into under-visited regions. This mechanism substantially broadens state coverage and yields robust pre-trained policies. Beyond exploration, ExDM offers theoretical guarantees and practical algorithms for fine-tuning diffusion policies under limited interactions, overcoming instability and computational overhead from multi-step sampling. Extensive experiments on Maze2d and URLB show that ExDM achieves superior exploration and faster downstream adaptation, establishing new state-of-the-art results, particularly in environments with complex structure or cross-embodiment settings.

**摘要翻译**:

无监督强化学习（URL）在无奖励环境中通过探索多样化状态来预训练智能体，旨在实现对各种下游任务的高效适应。在缺乏外在奖励的情况下，先前的方法依赖内在目标，但异构的探索数据对内在奖励设计和策略学习都要求强大的建模能力。我们引入了探索性扩散模型（ExDM），利用扩散模型的强大表达能力来拟合多样化的经验回放缓冲区分布，从而提供准确的密度估计和基于分数的内在奖励，驱动探索进入访问不足的区域。这种机制大幅扩展了状态覆盖范围，并产生鲁棒的预训练策略。在探索之外，ExDM 为在有限交互下微调扩散策略提供了理论保证和实用算法，克服了多步采样带来的不稳定性和计算开销。在 Maze2d 和 URLB 上的大量实验表明，ExDM 实现了更优的探索和更快的下游适应，建立了新的最先进结果，尤其是在具有复杂结构或跨具身设置的环境中。

**背景**: 无监督强化学习(Unsupervised RL, URL)在无奖励环境中预训练智能体，通过探索多样化状态来实现对各种下游任务的快速适应。在缺乏外在奖励的情况下，现有方法依赖内在目标，但异质性探索数据对内在奖励设计和策略学习的建模能力提出了很高要求。

**动机**: 无监督强化学习中的核心瓶颈在于：有效探索需要对底层状态分布进行准确估计，而该分布通常是异质且难以捕捉的。现有预训练策略表达力不足，限制了无监督探索和下游适应的效果。同时，扩散模型虽然具有强大的建模能力，但其多步采样的计算成本构成效率瓶颈，且在有限交互下的微调存在不稳定性。

**创新点**:
1. 首次将扩散模型引入无监督强化学习，提出 Exploratory Diffusion Model(ExDM)，利用扩散模型对 replay buffer 中的异质状态分布进行精确密度估计，并基于 score function 定义内在奖励驱动智能体探索访问不足的区域
2. 设计了解耦训练方案：用扩散模型进行密度估计和内在奖励计算，同时使用轻量级 Gaussian 行为策略进行数据收集，避免扩散模型多步采样的低效问题
3. 提出基于交替优化的扩散策略微调算法，具有收敛性和最优性的理论保证，在 Maze2d 和 URLB 基准上达到了新的 state-of-the-art 性能

**开源代码**: 未提供（源代码作为 supplementary material 提交）

---

## 123. Triple-BERT: Do We Really Need MARL for Order Dispatch on Ride-Sharing Platforms?

**Triple-BERT：网约车平台的订单调度真的需要多智能体强化学习吗？**

**OpenReview**: [https://openreview.net/forum?id=symgW6FhA6](https://openreview.net/forum?id=symgW6FhA6)

**Authors**: Zijian Zhao (The Hong Kong University of Science and Technology), Sen Li (Hong Kong University of Science and Technology)

**Institutions**: The Hong Kong University of Science and Technology, Hong Kong University of Science and Technology

**Primary Area**: reinforcement learning

**Keywords**: Reinforcement Learning, Order Dispatching, Ride Sharing

**TL;DR**: This paper proposes a novel centralized reinforcement learning framework for large-scale order dispatching tasks in ride-sharing scenarios, achieving better cooperation among workers compared to previous multi-agent methods.

**TL;DR翻译**: 本文提出了一种新颖的集中式强化学习框架，用于网约车场景中的大规模订单调度任务，与此前的多智能体方法相比实现了更好的工作者间协作。

**Abstract**:

On-demand ride-sharing platforms, such as Uber and Lyft, face the intricate real-time challenge of bundling and matching passengers--each with distinct origins and destinations--to available vehicles, all while navigating significant system uncertainties. Due to the extensive observation space arising from the large number of drivers and orders, order dispatching, though fundamentally a centralized task, is often addressed using Multi-Agent Reinforcement Learning (MARL). However, independent MARL methods fail to capture global information and exhibit poor cooperation among workers, while Centralized Training Decentralized Execution (CTDE) MARL methods suffer from the curse of dimensionality. To overcome these challenges, we propose Triple-BERT, a centralized  Single Agent Reinforcement Learning (MARL) method designed specifically for large-scale order dispatching on ride-sharing platforms. Built on a variant TD3, our approach addresses the vast action space through an action decomposition strategy that breaks down the joint action probability into individual driver action probabilities. To handle the extensive observation space, we introduce a novel BERT-based network, where parameter reuse mitigates parameter growth as the number of drivers and orders increases, and the attention mechanism effectively captures the complex relationships among the large pool of driver and orders. We validate our method  using a real-world ride-hailing dataset from Manhattan. Triple-BERT achieves approximately an 11.95% improvement over current state-of-the-art methods, with a 4.26% increase in served orders and a 22.25% reduction in pickup times. Our code, trained model parameters, and processed data are publicly available at https://github.com/RS2002/Triple-BERT .

**摘要翻译**:

网约车平台（如 Uber 和 Lyft）面临着复杂的实时挑战：将具有不同起终点的乘客捆绑并匹配给可用车辆，同时应对显著的系统不确定性。由于大量司机和订单带来的庞大观测空间，订单调度虽然本质上是集中式任务，却常采用多智能体强化学习（MARL）来解决。然而，独立式 MARL 方法无法捕获全局信息且工作者间协作不佳，而集中训练分散执行（CTDE）MARL 方法则面临维度灾难。为克服这些挑战，我们提出了 Triple-BERT，一种专为网约车平台大规模订单调度设计的集中式单智能体强化学习方法。基于 TD3 的变体，我们的方法通过动作分解策略将联合动作概率分解为各司机的独立动作概率，以应对庞大的动作空间。为处理广泛的观测空间，我们引入了一种新颖的基于 BERT 的网络，其中参数复用缓解了随司机和订单数量增加而带来的参数增长问题，注意力机制有效捕获了大量司机和订单之间的复杂关系。我们使用曼哈顿的真实网约车数据集验证了该方法。Triple-BERT 相比当前最先进方法实现了约 11.95% 的提升，其中完成订单数增加了 4.26%，接客时间减少了 22.25%。我们的代码、训练模型参数和处理后的数据已公开于 https://github.com/RS2002/Triple-BERT。

**背景**: 网约车平台（如 Uber、Lyft）面临实时将具有不同起点和终点的乘客捆绑并匹配给可用车辆的复杂调度问题。由于大量司机和订单导致的巨大观测空间，订单调度虽然本质上是一个集中式任务，但通常使用多智能体强化学习(MARL)来解决。

**动机**: 现有 MARL 方法在大规模订单调度场景中存在根本性限制：独立方法缺乏全局协调，CTDE 方法在数千个智能体的大规模场景中收敛慢且性能次优。作者提出一个关键问题：我们真的需要 MARL 来解决网约车平台的订单调度问题吗？核心动机是设计一种集中式单智能体强化学习(SARL)方法来克服这些限制。

**创新点**:
1. 提出 Triple-BERT，首个基于集中式 TD3 变体的大规模网约车订单调度 SARL 框架，通过动作分解策略将联合动作概率分解为各个司机的独立动作概率
2. 设计基于 BERT 的新型神经网络架构，利用双向自注意力机制捕捉司机和订单间的复杂关系，通过参数复用(parameter reuse)防止参数爆炸
3. 提出两阶段训练策略：先用 MARL 方法预训练特征提取器，再进行集中式微调。在曼哈顿真实数据集上比 SOTA 方法提升约 11.95%

**开源代码**: https://github.com/RS2002/Triple-BERT

---

## 130. MemAgent: Reshaping Long-Context LLM with Multi-Conv RL-based Memory Agent

**MemAgent：基于多轮对话强化学习的记忆智能体重塑长上下文大语言模型**

**OpenReview**: [https://openreview.net/forum?id=k5nIOvYGCL](https://openreview.net/forum?id=k5nIOvYGCL)

**Authors**: Hongli Yu (Tsinghua University), Tinghong Chen (University of the Chinese Academy of Sciences), Jiangtao Feng (Tsinghua University), Jiangjie Chen (ByteDance Seed), Weinan Dai (Tsinghua University), Qiying Yu (Tsinghua University), Ya-Qin Zhang (AIR, Tsinghua University), Wei-Ying Ma (Tsinghua University), Jingjing Liu (Tsinghua University), Mingxuan Wang (ByteDance Inc.), Hao Zhou (Tsinghua University, Tsinghua University)

**Institutions**: Tsinghua University, University of the Chinese Academy of Sciences, ByteDance Seed, AIR, Tsinghua University, ByteDance Inc., Tsinghua University, Tsinghua University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLM, memory, agent, RLVR

**TL;DR**: We propose MemAgent, a novel agent workflow for long-text processing,  demonstrating exceptional extrapolation and performance in large-scale tasks after RL Training.

**TL;DR翻译**: 我们提出了 MemAgent，一种用于长文本处理的新型智能体工作流，经过强化学习训练后在大规模任务中展现出卓越的外推和性能表现。

**Abstract**:

Despite improvements by length extrapolation, efficient attention and memory modules, handling infinitely long documents without performance degradation during extrapolation remains the ultimate challenge in long-text processing. To solve this problem, We introduce a novel agent workflow, \method, which processes text in segments and updates memory through an overwrite strategy, addressing the challenge of long-context task through enhanced memory management. We further extend the DAPO algorithm to directly optimize memory ability in an end-to-end fashion, facilitating training via independent-context multi-conversation generation. Experimental results demonstrate that MemAgent has superb long-context capabilities, being able to extrapolate from an 8K context to a 3.5M QA task with a performance loss of less than 10% and achieving over 95% on the 512K NIAH test.

**摘要翻译**:

尽管长度外推、高效注意力机制和记忆模块等技术有所改进，但在外推过程中处理无限长文档而不出现性能下降仍然是长文本处理的终极挑战。为解决这一问题，我们引入了一种新型智能体工作流 MemAgent，它以分段方式处理文本并通过覆写策略更新记忆，通过增强的记忆管理来应对长上下文任务的挑战。我们进一步扩展了 DAPO 算法，以端到端方式直接优化记忆能力，通过独立上下文的多轮对话生成促进训练。实验结果表明，MemAgent 具有出色的长上下文能力，能够从 8K 上下文外推到 3.5M 的问答任务且性能损失不到 10%，并在 512K NIAH 测试中达到 95% 以上。

**背景**: 尽管长度外推、高效注意力和记忆模块等技术不断改进，在外推过程中处理无限长文档而不产生性能退化仍然是长文本处理的终极挑战。现有方法包括：位置编码外推方法受限于 O(n^2) 计算复杂度；稀疏/线性注意力方法需要从头训练；上下文压缩方法在外推时表现不佳。

**动机**: 成功的长上下文 LLM 需要同时满足三个条件：处理无限长度文本、扩展时无显著性能下降、以及线性复杂度的高效解码。受人类处理长文档方式的启发（提取关键概念、记录要点、丢弃冗余信息），作者提出使用强化学习为 LLM 配备动态更新的固定长度记忆，使模型在有限上下文窗口内处理任意长度输入。

**创新点**:
1. 提出 MemAgent 工作流，通过分段处理文本并使用覆写策略(overwrite strategy)更新固定长度记忆，使 LLM 在有限上下文窗口内以线性时间复杂度处理任意长度输入
2. 将 DAPO 算法扩展为 Multi-Conv DAPO，支持跨多个独立上下文的多轮对话生成，以端到端方式直接优化记忆能力
3. 仅使用 8K 上下文窗口训练的模型可从 60K 长度文档外推至 3.5M token 的 QA 任务，性能损失不到 10%，并在 512K NIAH 测试中达到 95% 以上的准确率

**开源代码**: 未提供（论文声明数据集和模型权重将在开源平台发布）

---

## 131. TD-JEPA: Latent-predictive Representations for Zero-Shot Reinforcement Learning

**TD-JEPA：用于零样本强化学习的潜在预测表征**

**OpenReview**: [https://openreview.net/forum?id=SzXDuBN8M1](https://openreview.net/forum?id=SzXDuBN8M1)

**Authors**: Marco Bagatella (Max Planck Institute for Intelligent Systems, Max Planck Institute for Intelligent Systems), Matteo Pirotta (Meta), Ahmed Touati (Facebook), Alessandro Lazaric (Facebook), Andrea Tirinzoni (Meta, FAIR)

**Institutions**: Max Planck Institute for Intelligent Systems, Max Planck Institute for Intelligent Systems, Meta, Facebook, Meta, FAIR

**Primary Area**: reinforcement learning

**Keywords**: zero-shot reinforcement learning, unsupervised reinforcement learning, self-predictive representations, joint embedding predictive architecture

**TL;DR**: We propose a temporal-difference latent-predictive method for zero-shot unsupervised RL.

**TL;DR翻译**: 我们提出了一种时序差分潜在预测方法，用于零样本无监督强化学习。

**Abstract**:

Latent prediction--where agents learn by predicting their own latents--has emerged as a powerful paradigm for training general representations in machine learning. In reinforcement learning (RL), this approach has been explored to define auxiliary losses for a variety of settings, including reward-based and unsupervised RL, behavior cloning, and world modeling. While existing methods are typically limited to single-task learning, one-step prediction, or on-policy trajectory data, we show that temporal difference (TD) learning enables learning representations predictive of long-term latent dynamics across multiple policies from offline, reward-free transitions. Building on this, we introduce TD-JEPA, which leverages TD-based latent-predictive representations into unsupervised RL. TD-JEPA trains explicit state and task encoders, a policy-conditioned multi-step predictor, and a set of parameterized policies directly in latent space. This enables zero-shot optimization of any reward function at test time. Theoretically, we show that an idealized variant of TD-JEPA avoids collapse with proper initialization, and learns encoders that capture a low-rank factorization of long-term policy dynamics, while the predictor recovers their successor features in latent space. Empirically, TD-JEPA matches or outperforms state-of-the-art baselines on locomotion, navigation, and manipulation tasks across 13 datasets in ExoRL and OGBench, especially in the challenging setting of zero-shot RL from pixels.

**摘要翻译**:

潜在预测——智能体通过预测自身的潜在表征来学习——已成为机器学习中训练通用表征的强大范式。在强化学习（RL）中，这种方法已被探索用于多种设置的辅助损失定义，包括基于奖励和无监督的 RL、行为克隆以及世界建模。虽然现有方法通常局限于单任务学习、单步预测或在策略轨迹数据，我们证明了时序差分（TD）学习能够从离线的、无奖励的转换中学习跨多策略的长期潜在动态预测表征。基于此，我们引入了 TD-JEPA，将基于 TD 的潜在预测表征应用于无监督 RL。TD-JEPA 直接在潜在空间中训练显式的状态和任务编码器、策略条件化的多步预测器以及一组参数化策略。这使得在测试时能够对任意奖励函数进行零样本优化。在理论上，我们证明了 TD-JEPA 的理想化变体在适当初始化下可避免坍缩，并学习捕获长期策略动态低秩分解的编码器，而预测器在潜在空间中恢复其后继特征。在实验上，TD-JEPA 在 ExoRL 和 OGBench 的 13 个数据集上的运动、导航和操作任务中达到或超越了最先进的基线，尤其是在从像素进行零样本 RL 的挑战性设置中。

**背景**: 在强化学习中学习有效的状态表征是核心挑战。潜在预测(latent-predictive)表征学习是一种有前景的自监督方法，通过在潜在空间中预测未来状态表征来学习，无需奖励或状态重构。

**动机**: 现有潜在预测方法的局限性在于：无法同时建模多步、多策略依赖的长期动态，且难以从离线、无奖励的转移数据中学习。作者认为时序差分(TD)学习可以克服这些限制，使表征能够预测跨多个策略/任务的长期潜在动态。

**创新点**:
1. 提出 TD-JEPA，利用基于时序差分的潜在预测表征进行 zero-shot 无监督 RL，通过训练显式的状态编码器和任务编码器、策略条件化的多步预测器
2. 提出新颖的离策略(off-policy)时序差分损失，鼓励表征不仅预测即时转移，还预测与多个策略相关的长期特征
3. 理论上证明表征在适当初始化下不会坍塌，能恢复 successor measures 的低秩分解。在 ExoRL 和 OGBench 的 13 个数据集、65 个任务上匹配或超越 SOTA 基线

**开源代码**: https://github.com/facebookresearch/td_jepa

---

## 147. DiffusionNFT: Online Diffusion Reinforcement with Forward Process

**DiffusionNFT：基于前向过程的在线扩散强化学习**

**OpenReview**: [https://openreview.net/forum?id=VJZ477R89F](https://openreview.net/forum?id=VJZ477R89F)

**Authors**: Kaiwen Zheng (Tsinghua University), Huayu Chen (Tsinghua University), Haotian Ye (Stanford University), Haoxiang Wang (NVIDIA), Qinsheng Zhang (NVIDIA), Kai Jiang (Tsinghua University), Hang Su (Tsinghua University), Stefano Ermon (Stanford University), Jun Zhu (Tsinghua University), Ming-Yu Liu (NVIDIA)

**Institutions**: Tsinghua University, Stanford University, NVIDIA

**Primary Area**: generative models

**Keywords**: Diffusion Models, Reinforcement Learning, Flow Matching

**TL;DR**: We propose a new online reinforcement learning (RL) algorithm for diffusion and flow models based on forward process.

**TL;DR翻译**: 我们提出了一种基于前向过程的新型在线强化学习（RL）算法，适用于扩散模型和流匹配模型。

**Abstract**:

Online reinforcement learning (RL) has been central to post-training language models, but its extension to diffusion models remains challenging due to intractable likelihoods. Recent works discretize the continuous diffusion process to leverage likelihood-based RL algorithms, but such discretization introduces hard-to-quantify approximation errors. We propose DiffusionNFT, a new online diffusion RL algorithm based on the forward process. DiffusionNFT leverages the forward diffusion process to transform clean samples from the old policy distribution to the new policy distribution, completely bypassing likelihood computation. Theoretically, we show DiffusionNFT optimizes the exact KL-regularized objective for both continuous diffusion and flow matching models. Practically, DiffusionNFT requires only a few denoising steps and runs efficiently on a single NVIDIA A100 GPU. On text-to-image generation with Stable Diffusion 3.5-Medium and Human Preference Score v2.1 (HPSv2.1) as reward, DiffusionNFT reaches a reward of 0.95 within 150 training steps, while FlowGRPO achieves 0.95 with over 5k steps and additional CFG employment. By leveraging multiple reward models, DiffusionNFT significantly boosts the performance of SD3.5-Medium in every benchmark tested.

**摘要翻译**:

在线强化学习（RL）已成为语言模型后训练的核心方法，但由于似然函数不可计算，将其扩展到扩散模型仍具有挑战性。近期工作将连续扩散过程离散化以利用基于似然的RL算法，但这种离散化引入了难以量化的近似误差。我们提出了DiffusionNFT——一种基于前向过程的在线扩散RL新算法。DiffusionNFT利用前向扩散过程将干净样本从旧策略分布转换到新策略分布，从而完全绕过了似然计算。在理论上，我们证明了DiffusionNFT对于连续扩散和流匹配模型均实现了严格的KL正则化目标函数的精确优化。在实践中，DiffusionNFT只需少量去噪步骤即可在单张NVIDIA A100 GPU上高效运行。在以Stable Diffusion 3.5-Medium为基础模型、以Human Preference Score v2.1（HPSv2.1）为奖励的文本到图像生成任务中，DiffusionNFT在150步训练内即达到0.95的奖励值，而FlowGRPO需要超过5000步训练加上额外的无分类器引导（CFG）才能达到同等水平。通过利用多个奖励模型，DiffusionNFT在所有测试基准上显著提升了SD3.5-Medium的性能。

**背景**: 在线强化学习(Online RL)已成为大语言模型后训练的核心方法，推动了对齐和推理能力的进步。然而，将类似方法扩展到扩散模型面临挑战，因为扩散模型的似然(likelihood)不可精确计算。

**动机**: 现有基于逆向过程的扩散 RL 方法（如 FlowGRPO）存在三个根本局限：(1) 仅关注逆向采样过程破坏了对前向扩散过程的一致性；(2) 数据收集依赖一阶 SDE 采样器，无法使用更高效的 ODE 或高阶求解器；(3) CFG 需要同时训练条件和无条件模型，导致复杂且低效的双模型优化。

**创新点**:
1. 提出 DiffusionNFT(Diffusion Negative-aware FineTuning)，一种全新的在线 RL 范式，通过 flow matching 目标直接在前向扩散过程上进行策略优化
2. 该方法允许使用任意黑盒求解器进行数据收集，无需存储完整采样轨迹，无需似然估计，原生支持 off-policy 训练，且完全无需 CFG
3. 效率比 FlowGRPO 提升高达 25 倍：在 GenEval 任务上，DiffusionNFT 在 1k 步内将得分从 0.24 提升至 0.98

**开源代码**: https://research.nvidia.com/labs/dir/DiffusionNFT

---

## 149. Reducing Belief Deviation in Reinforcement Learning for Active Reasoning

**通过减少信念偏差改进主动推理中的强化学习**

**OpenReview**: [https://openreview.net/forum?id=r8hzDA3pUY](https://openreview.net/forum?id=r8hzDA3pUY)

**Authors**: Deyu Zou (Department of Computer Science and Engineering, The Chinese University of Hong Kong), Yongqiang Chen (Mohamed bin Zayed University of Artificial Intelligence), Jianxiang Wang (ByteDance Inc.), Garry YANG (Department of Computer Science and Engineering, The Chinese University of Hong Kong), Mufei Li (Georgia Institute of Technology), Qing Da (ByteDance Inc.), James Cheng (The Chinese University of Hong Kong), Pan Li (Georgia Institute of Technology), Yu Gong (ByteDance Inc.)

**Institutions**: Department of Computer Science and Engineering, The Chinese University of Hong Kong, Mohamed bin Zayed University of Artificial Intelligence, ByteDance Inc., Georgia Institute of Technology, The Chinese University of Hong Kong

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Large language models, LLM reasoning, Agentic multi-turn reasoning

**Abstract**:

Active reasoning requires large language models (LLMs) to interact with external sources and strategically gather information to solve problems. Central to this process is belief tracking: maintaining and updating an understanding of the problem over multiple interaction turns. However, the distribution shift inherent in reinforcement learning (RL) training leads to severe belief deviation, where the agent's internal belief about the problem state gradually drifts from the true probability, resulting in ineffective searches and hallucinated reasoning. We formalize the active reasoning problem from a probabilistic perspective, modeling LLMs as belief-updating agents operating in partially observable environments. Building on this framework, we propose three complementary belief-control mechanisms: (i) regret-based belief correction, which corrects belief drift using signals from deviations from the optimal policy; (ii) truncated importance sampling, which enables off-policy correction compatible with per-token credit assignment from sequence-level rewards in online RL; and (iii) belief-aware rollout filtering, which selects rollouts based on belief quality before training. Experiments show consistent improvements over baselines on several active reasoning benchmarks, achieving up to 30\% gains while cutting rollout tokens by roughly 25\%. These results highlight belief control as a key principle for developing robust and generalizable LLM-based active reasoners.

**摘要翻译**:

主动推理要求大语言模型（LLM）与外部信息源交互，并策略性地收集信息以解决问题。这一过程的核心是信念追踪：在多轮交互中维护和更新对问题的理解。然而，强化学习（RL）训练中固有的分布偏移会导致严重的信念偏差——即智能体对问题状态的内部信念逐渐偏离真实概率，从而导致无效搜索和幻觉推理。我们从概率的角度形式化了主动推理问题，将LLM建模为在部分可观测环境中运作的信念更新智能体。基于此框架，我们提出了三种互补的信念控制机制：（i）基于遗憾的信念校正，通过利用偏离最优策略的信号来修正信念偏差；（ii）截断重要性采样，在在线RL中实现与基于序列级奖励的逐token信用分配兼容的离策略校正；（iii）信念感知的rollout过滤，在训练前根据信念质量选择rollout样本。实验结果表明，在多个主动推理基准上的表现持续优于现有方法，提升幅度高达30%，同时将rollout token数量减少约25%。这些结果突显了信念控制作为开发鲁棒且可泛化的基于LLM的主动推理器的关键原则。

**背景**: 主动推理(active reasoning)要求大语言模型与外部信息源交互，策略性地收集信息以解决问题。该过程的核心是信念跟踪(belief tracking)：维持对问题状态和缺失信息的连贯理解。然而由于 LLM 推理能力有限，基于 LLM 的智能体常遭受信念偏差(belief deviation)。

**动机**: 作者将主动推理建模为 POMDP，发现在 LLM 不完美的信念更新下，轨迹会被驱入信念陷阱区域(Belief-Trap Region, BTR)，在该区域中动作不再提供有效信息，误差累积，推理停滞。更严重的是，BTR 的无信息尾部会污染分配给关键早期动作的信用，甚至反转其估计梯度。

**创新点**:
1. 从理论角度分析了 LLM 智能体在主动推理中的信念偏差问题，证明了信念陷阱区域(BTR)的存在性及其如何污染信用分配并反转策略梯度
2. 提出 T3(Truncating Belief-Trapped Trajectories)，在检测到进入 BTR 时截断轨迹，保留信息性前缀的信用分配
3. 在 AR-Bench 和 Multi-Turn Puzzles 等 5 个任务上，T3 一致性地提升训练稳定性和最终性能，最高提升 30%，同时减少约 34% 的 rollout token 消耗

**开源代码**: 未提供

---

## 154. The Art of Scaling Reinforcement Learning Compute for LLMs

**LLM强化学习计算扩展的艺术**

**OpenReview**: [https://openreview.net/forum?id=FMjeC9Msws](https://openreview.net/forum?id=FMjeC9Msws)

**Authors**: Fnu Devvrit (, University of Texas at Austin), Lovish Madaan (Meta), Rishabh Tiwari (University of California, Berkeley), Rachit Bansal (Harvard University), Sai Surya Duvvuri (University of Texas at Austin), Manzil Zaheer (Zaheer), Inderjit S Dhillon (Google), David Brandfonbrener (Anthropic), Rishabh Agarwal (McGill University)

**Institutions**: , University of Texas at Austin, Meta, University of California, Berkeley, Harvard University, University of Texas at Austin, Zaheer, Google, Anthropic, McGill University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Scaling, LLMs, Reasoning

**TL;DR**: We study compute scaling properties of RL methods on LLMs

**TL;DR翻译**: 我们研究了RL方法在LLM上的计算扩展特性。

**Abstract**:

Reinforcement learning (RL) has become central to training large language models (LLMs), yet the field lacks predictive scaling methodologies comparable to those established for pre-training.
    Despite the growing computational investment in RL post-training, it remains unclear how training and test-time compute jointly influence final performance.
    We investigate how RL training and inference compute, combined with the difficulty of test problems, determines final performance. Our work reveals three key insights:
    (1) *An RL scaling law:* Under a fixed training budget, RL performance follows a compute-optimal frontier that can be predicted using a sigmoid-based model relating training FLOPs to downstream task accuracy.
    (2) *Optimal budget allocation:* Across our tested configurations, the compute-optimal allocation consistently dedicates 20--35\% of total compute to RL post-training, regardless of total budget.
    (3) *Interaction between train and test-time compute:* Although RL training shifts the performance curve, the relative gain from test-time compute diminishes as the RL budget grows, revealing a nuanced interplay between the two.
    Guided by these findings, we develop a recipe to train a 14B-parameter model that outperforms DeepSeek-R1-Zero-Qwen-32B (a model trained at much larger scale) on MATH500, using roughly 7500 GPU-hours.
    Our work provides both a _scientific framework_ for analyzing scaling in RL and a practical recipe that brings RL training closer to the predictability long achieved in pre-training.

**摘要翻译**:

强化学习（RL）已成为训练大语言模型（LLM）的核心方法，但该领域缺乏可与预训练中已建立的相媲美的预测性扩展方法论。尽管在RL后训练上的计算投入不断增长，训练时和测试时的计算资源如何共同影响最终性能仍不清楚。我们研究了RL训练和推理计算资源，结合测试问题的难度，如何决定最终性能。我们的工作揭示了三个关键发现：（1）*RL扩展定律*：在固定的训练预算下，RL性能遵循一个计算最优前沿，可以使用基于sigmoid的模型将训练FLOPs与下游任务准确率关联来预测。（2）*最优预算分配*：在我们测试的所有配置中，计算最优分配一致地将总计算量的20%--35%分配给RL后训练，与总预算无关。（3）*训练时与测试时计算的交互*：虽然RL训练移动了性能曲线，但随着RL预算的增长，测试时计算带来的相对增益递减，揭示了两者之间微妙的交互关系。基于这些发现，我们制定了一个训练方案，使用约7500 GPU小时训练了一个140亿参数的模型，在MATH500上超越了DeepSeek-R1-Zero-Qwen-32B（一个在更大规模上训练的模型）。我们的工作既提供了分析RL扩展的*科学框架*，也提供了使RL训练接近预训练中长期实现的可预测性的实用方案。

**背景**: 强化学习(RL)已成为训练大语言模型(LLMs)的核心方法，但该领域缺乏类似预训练中已建立的可预测性 scaling 方法论。尽管计算预算快速增长，目前对如何评估算法改进以扩展 RL 计算量仍没有系统性的理解。

**动机**: 现有 RL 训练方法多为针对特定模型和场景的临时方案（如 DeepSeek GRPO、DAPO、Magistral、MiniMax-M1 等），缺乏统一的 scaling 法则来指导 RL 的规模化训练。这导致研究者无法在较小规模实验中可靠预测大规模训练的性能，阻碍了学术界的研究进展。

**创新点**:
1. 提出首个大规模系统性研究（超过 400,000 GPU 小时），建立了分析和预测 LLM 中 RL scaling 的科学框架，使用 sigmoid 型 compute-performance 曲线拟合 RL 训练性能
2. 系统消融了广泛的设计选择（loss 聚合、归一化、课程学习、off-policy 算法等），发现不同 recipe 的渐近性能差异显著
3. 提出最佳实践 recipe ScaleRL，成功将单次 RL 训练扩展到 100,000 GPU 小时
4. 证明稳定可扩展的 recipe 遵循可预测的 scaling 轨迹，使 RL 训练接近预训练长期以来达到的可预测性

**开源代码**: 未提供

---

## 168. Multiplayer Nash Preference Optimization

**多玩家Nash偏好优化**

**OpenReview**: [https://openreview.net/forum?id=x7aLhLMVn1](https://openreview.net/forum?id=x7aLhLMVn1)

**Authors**: Fang Wu, Xu Huang (Independent), Weihao Xuan, Zhiwei Zhang (Pennsylvania State University), Yijia Xiao (University of California, Los Angeles), Guancheng Wan, Xiaomin Li (Harvard University, Harvard University), Bing Hu (NA), Peng Xia (Department of Computer Science, University of North Carolina at Chapel Hill), Jure Leskovec (Stanford University), Yejin Choi (Computer Science Department, Stanford University)

**Institutions**: Independent, Pennsylvania State University, University of California, Los Angeles, Harvard University, Harvard University, NA, Department of Computer Science, University of North Carolina at Chapel Hill, Stanford University, Computer Science Department, Stanford University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Preference Optimization, RLHF

**Abstract**:

Reinforcement learning from human feedback (RLHF) has emerged as the standard paradigm for aligning large language models (LLMs) with human preferences. However, reward-based methods built on the Bradley-Terry model assume that preferences are transitive, an assumption that breaks down in many practical scenarios where human judgments exhibit non-transitive preference structures, such as in creative writing, debate reasoning, or multi-criteria trade-offs. To overcome this limitation, we introduce Multiplayer Nash Preference Optimization (MNPO), a game-theoretic framework that models alignment as a multiplayer Nash bargaining game among a configurable number of response candidates. MNPO generalizes the two-player Nash Equilibrium approach to the multi-player setting, allowing more expressive modeling of complex, non-transitive preference landscapes. The resulting Multiplayer Nash Bargaining Solution provides an equilibrium that can capture cyclic or conflicting preference patterns that pairwise methods cannot represent. Theoretically, we prove that MNPO converges to a unique equilibrium under mild conditions and that its gradient updates remain bounded, ensuring stable training dynamics. Empirically, we evaluate MNPO on AlpacaEval 2.0, Arena-Hard, and WildBench using Llama-3.1-8B-Instruct as the base model. MNPO achieves 45.4% length-controlled win rate on AlpacaEval 2.0 (over 10% absolute improvement over DPO and SPPO), and 43.5% on Arena-Hard (over 20% improvement over DPO and SimPO). Ablation studies further confirm that performance scales with the number of players and that MNPO remains robust under varying annotator conditions and mixed-policy evaluation scenarios. Together, these results establish MNPO as a principled and scalable framework for aligning LLMs with complex, non-transitive human preferences.

**摘要翻译**:

基于人类反馈的强化学习（RLHF）已成为将大语言模型（LLM）与人类偏好对齐的标准范式。然而，基于Bradley-Terry模型构建的奖励方法假设偏好具有传递性，这一假设在许多实际场景中会失效——当人类判断呈现非传递性偏好结构时，如在创意写作、辩论推理或多标准权衡中。为克服这一局限，我们引入了多玩家Nash偏好优化（MNPO），一个博弈论框架，将对齐建模为可配置数量的回复候选之间的多玩家Nash讨价还价博弈。MNPO将两人Nash均衡方法推广到多人场景，允许对复杂的非传递性偏好格局进行更具表达力的建模。由此产生的多玩家Nash讨价还价解提供了一种均衡，能够捕捉成对方法无法表示的循环或冲突的偏好模式。在理论上，我们证明了MNPO在温和条件下收敛到唯一均衡，且其梯度更新保持有界，确保了稳定的训练动态。在实证方面，我们使用Llama-3.1-8B-Instruct作为基础模型，在AlpacaEval 2.0、Arena-Hard和WildBench上评估了MNPO。MNPO在AlpacaEval 2.0上达到了45.4%的长度控制胜率（比DPO和SPPO绝对提升超过10%），在Arena-Hard上达到43.5%（比DPO和SimPO提升超过20%）。消融研究进一步证实性能随玩家数量的增加而提升，且MNPO在不同标注者条件和混合策略评估场景下保持鲁棒。这些结果共同确立了MNPO作为将LLM与复杂的非传递性人类偏好对齐的有原则且可扩展的框架。

**背景**: RLHF 已成为大语言模型与人类偏好对齐的标准范式。然而，基于 Bradley-Terry 假设的奖励方法难以捕捉现实世界偏好中的非传递性和异质性。近期研究将对齐重新建模为两人 Nash 博弈(NLHF)，催生了 INPO、ONPO、EGPO 等算法。

**动机**: 现有 NLHF 方法本质上局限于两人博弈设定，策略仅与单一对手竞争，这导致了「单对手偏差」，无法捕捉现实偏好结构的完整复杂性。现实中的偏好对齐往往涉及多个标注者、异质评估标准、多个奖励模型或历史模型检查点序列。

**创新点**:
1. 提出 Multiplayer Nash Preference Optimization(MNPO)框架，将 NLHF 推广到多人博弈(n-player game)
2. 理论贡献：证明 MNPO 在同质偏好 oracle 下具有良好的均衡特征，继承两人方法的收敛性保证，同时支持更丰富的均衡动态
3. 提出 TD-MNPO，对手集合自适应演化，利用 multiplicative weights update 实现对称博弈下的强理论保证
4. 在 instruction-following 基准上全面超越现有 NLHF baseline

**开源代码**: 未提供

---

## 170. TROLL: Trust Regions Improve Reinforcement Learning for Large Language Models

**TROLL：信赖域方法提升大语言模型的强化学习效果**

**OpenReview**: [https://openreview.net/forum?id=X9D5MVpPJ9](https://openreview.net/forum?id=X9D5MVpPJ9)

**Authors**: Philipp Becker (Facebook), Niklas Freymuth (Karlsruhe Institute of Technology), Serge Thilges (Karlsruher Institut für Technologie), Fabian Otto (Isomorphic Labs), Gerhard Neumann (FZI Research Center for Information Technology)

**Institutions**: Facebook, Karlsruhe Institute of Technology, Karlsruher Institut für Technologie, Isomorphic Labs, FZI Research Center for Information Technology

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: RL from verifiable rewards, Finetuning LLMs, Trust Regions

**TL;DR**: Replacing PPO's clipping objective with more principled trust regions improves RL from verifiable rewards.

**TL;DR翻译**: 用更有原则性的信赖域方法替代 PPO 的裁剪目标，可以提升基于可验证奖励的强化学习效果。

**Abstract**:

Reinforcement Learning (RL) with PPO-like clip objectives has become the standard choice for reward-based fine-tuning of large language models (LLMs). Although recent work has explored improved estimators of advantages and normalization, the clipping mechanism itself has remained untouched. Originally introduced as a proxy for principled KL-based trust regions, clipping is a crude approximation that often causes unstable updates and suboptimal performance. We replace the clip objective with a novel discrete differentiable trust region projection, which provides principled token-level KL constraints. The projection operates on a sparse subset of the model's most important token logits to balance computational cost and projection effectiveness. Our approach, Trust Region Optimization for Large Language Models (TROLL), serves as a direct replacement for PPO-like clipping during training and does not alter the model's inference behavior. Across mathematical reasoning and code generation tasks, model families, as well as advantage-estimation methods, TROLL consistently outperforms PPO-like clipping in terms of training speed, stability, and final success rates.

**摘要翻译**:

使用类 PPO 裁剪目标的强化学习 (RL) 已成为大语言模型 (LLM) 基于奖励微调的标准选择。尽管近期研究探索了改进的优势估计和归一化方法，但裁剪机制本身一直未被改动。裁剪最初是作为基于 KL 散度的有原则性信赖域方法的近似代理引入的，但这种粗糙的近似常导致更新不稳定和性能次优。我们用一种新颖的离散可微信赖域投影替代了裁剪目标，提供有原则性的 token 级 KL 约束。该投影在模型最重要的 token logits 的稀疏子集上进行操作，以平衡计算成本和投影效果。我们的方法——大语言模型信赖域优化 (TROLL)——可以直接替代训练中类 PPO 的裁剪策略，且不改变模型的推理行为。在数学推理和代码生成任务、不同模型系列以及不同优势估计方法上，TROLL 在训练速度、稳定性和最终成功率方面均持续优于类 PPO 的裁剪方法。

**背景**: 基于 PPO-like clip 目标的强化学习已成为 LLM 奖励微调的标准选择。尽管近期工作探索了改进的 advantage 估计和归一化方法（如 GRPO、Dr.GRPO、GSPO、REINFORCE++），但 clipping 机制本身始终未被改动。

**动机**: PPO 的 clipping 是对 trust region 方法的粗糙近似，可能导致优化不稳定、更新校准不良以及对超参数的高度敏感，最终导致次优性能。同时，现代 LLM 的词表规模超过 100,000，使得直接实现 KL 约束的 trust region 在计算上代价高昂。

**创新点**:
1. 提出 TROLL(Trust Region Optimization for Large Language models)，用新颖的离散可微 trust region 投影替代 PPO 的 clip 目标，直接在 token 级别施加 KL 约束
2. 投影仅在模型最重要的稀疏 token logits 子集上操作，平衡计算成本和投影效果；投影方向可闭式计算
3. 通过 OptNet 框架实现可微分投影，保持梯度信息（不同于 PPO clipping 会截断超阈值 token 的梯度）
4. 在数学推理和代码生成任务上，TROLL 在训练速度、稳定性和最终成功率上一致优于 PPO-like clipping

**开源代码**: https://niklasfreymuth.github.io/troll/

---

## 188. Overthinking Reduction with Decoupled Rewards and Curriculum Data Scheduling

**基于解耦奖励与课程数据调度的过度思考消减方法**

**OpenReview**: [https://openreview.net/forum?id=kdeiRledV6](https://openreview.net/forum?id=kdeiRledV6)

**Authors**: Shuyang Jiang (Fudan University), Yusheng Liao (Shanghai Jiaotong University), Ya Zhang (Shanghai Jiao Tong University), Yanfeng Wang (Shanghai Jiao Tong University), Yu Wang (Shanghai Jiao Tong University)

**Institutions**: Fudan University, Shanghai Jiaotong University, Shanghai Jiao Tong University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: efficient reasoning; curriculum sampling with decoupled reward

**TL;DR**: theoretical unveil the underlying limitations of length reward and propose D$^2$yOR to achieve supreme efficiency without performance degradation

**TL;DR翻译**: 从理论上揭示了长度奖励的内在局限性，并提出 DECS 以在不降低性能的前提下实现卓越的效率

**Abstract**:

While large reasoning models trained with critic-free reinforcement learning and verifiable rewards (RLVR) represent the state-of-the-art, their practical utility is hampered by "overthinking", a critical issue where models generate excessively long reasoning paths without any performance benefit. Existing solutions that penalize length often fail, inducing performance degradation due to a fundamental misalignment between trajectory-level rewards and token-level optimization. In this work, we introduce a novel framework, DECS, built on our theoretical discovery of two previously unaddressed flaws in current length rewards: (1) the erroneous penalization of essential exploratory tokens and (2) the inadvertent rewarding of partial redundancy. Our framework's innovations include (i) a first-of-its-kind decoupled token-level reward mechanism that surgically distinguishes and penalizes redundant tokens, and (ii) a novel curriculum batch scheduling strategy to master the efficiency-efficacy equilibrium. Experimental results show DECS can achieve a dramatic reduction in reasoning tokens by over 50% across seven benchmarks while simultaneously maintaining or even improving performance. It demonstrates conclusively that substantial gains in reasoning efficiency can be achieved without compromising a model's underlying reasoning power. Code is available at https://github.com/pixas/DECS.

**摘要翻译**:

尽管使用无评判者强化学习和可验证奖励 (RLVR) 训练的大型推理模型代表了最先进水平，但其实用性受到"过度思考"的困扰——这是一个关键问题，即模型生成过长的推理路径却不带来任何性能收益。现有的惩罚长度的解决方案往往失效，由于轨迹级奖励与 token 级优化之间的根本性错位而导致性能下降。本文提出了一种新颖的框架 DECS，建立在我们对当前长度奖励中两个先前未被解决的缺陷的理论发现之上：(1) 对必要探索性 token 的错误惩罚，以及 (2) 对部分冗余的无意奖励。我们框架的创新包括：(i) 首创的解耦 token 级奖励机制，能够精确区分并惩罚冗余 token；(ii) 一种新颖的课程批调度策略，以掌握效率与效果之间的平衡。实验结果表明，DECS 能在七个基准上将推理 token 大幅减少超过 50%，同时保持甚至提升性能。这充分证明，可以在不损害模型底层推理能力的情况下实现推理效率的大幅提升。代码已在 https://github.com/pixas/DECS 开源。

**背景**: 基于 critic-free 强化学习和可验证奖励(RLVR)训练的大型推理模型(LRM)代表了当前最先进水平。然而，这些模型受到「overthinking」问题的严重困扰，即模型生成过长的推理路径却无性能收益。现有的长度惩罚方案常因 trajectory 级奖励与 token 级优化之间的根本性不对齐而导致性能退化。

**动机**: 作者通过理论分析发现当前长度奖励存在两个未被关注的缺陷：(1) 对必要探索性 token 的错误惩罚——当所有回复都正确但长度不同时，较长轨迹中的高熵 token 会受到不当抑制；(2) 对部分冗余的无意奖励——较短但含有冗余 token 的轨迹反而获得正 advantage 值。

**创新点**:
1. 理论揭示了现有长度奖励在 GRPO 框架下的两个关键缺陷：对正确高熵 token 的错误惩罚和对冗余 token 的无意奖励
2. 提出 DECS 框架，包含首创的解耦 token 级奖励机制(decoupled token-level reward)，能精确区分并惩罚冗余 token，同时保护必要的推理探索 token
3. 引入新颖的课程批次调度策略(curriculum batch scheduling)，动态平衡效率与效果的均衡
4. 在 7 个基准上实现推理 token 减少超过 50%，同时保持甚至提升模型性能

**开源代码**: https://github.com/pixas/DECS

---

## 205. EmotionThinker: Prosody-Aware Reinforcement Learning for Explainable Speech Emotion Reasoning

**EmotionThinker：面向可解释语音情感推理的韵律感知强化学习**

**OpenReview**: [https://openreview.net/forum?id=wbttgzp7MT](https://openreview.net/forum?id=wbttgzp7MT)

**Authors**: Dingdong WANG (Chinese University of Hong Kong, The Chinese University of Hong Kong), Shujie LIU (Microsoft), Tianhua Zhang (Chinese University of Hong Kong, The Chinese University of Hong Kong), Youjun Chen (Chinese University of Hong Kong, The Chinese University of Hong Kong), Jinyu Li (Microsoft), Helen M. Meng (The Chinese University of Hong Kong)

**Institutions**: Chinese University of Hong Kong, The Chinese University of Hong Kong, Microsoft, The Chinese University of Hong Kong

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Speech Emotion Recognition, Speech LLMs, Speech Processing, Reinforcement Learning

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

Emotional information in speech plays a unique role in multimodal perception. However, current Speech Large Language Models (SpeechLLMs), similar to conventional speech emotion recognition (SER) systems, still treat emotion understanding as a simple classification problem. This provides limited interpretability of predictions, while leaving the LLMs' expressive and reasoning capabilities underutilized. In this work, we take the first step to reformulate SER as a deep reasoning problem through reinforcement learning (RL). We propose EmotionThinker, which is designed to generate accurate emotion predictions with interpretable explanations grounded in fine-grained acoustic cues. To achieve this, we first construct EmotionCoT-35K, an emotional reasoning dataset with Chain-of-Thought annotations and detailed captions. Second, we observe that current SpeechLLMs exhibit weak prosody perception, whereas prosodic cues constitute fundamental signals for interpreting emotions. To address this, we develop the prosody-enhanced foundation model EmotionThinker-Base, and demonstrate that prosody enhancement improves emotion understanding. Third, we introduce Group-Relative-Policy-Optimization with Progressive-Trust-aware-Reasoning-Reward (GRPO-PTR) for RL. Different from standard GRPO, which relies only on rule-based outcome rewards, GRPO-PTR progressively introduces reasoning reward, dynamically adjusts it with a trustworthiness weight reflecting the alignment between reasoning and outcome, and evaluates the overall reasoning quality with a reward model based on multi-dimensional criteria. EmotionThinker outperforms previous state-of-the-art evaluation models both in emotion accuracy and explanation quality, advancing SER toward interpretable multimodal reasoning.

**摘要翻译**:

语音中的情感信息在多模态感知中发挥着独特作用。然而，当前的语音大语言模型（SpeechLLM）与传统的语音情感识别（SER）系统类似，仍将情感理解视为简单的分类问题。这不仅使预测的可解释性有限，也导致大语言模型的表达和推理能力未被充分利用。在本工作中，我们迈出了通过强化学习（RL）将 SER 重新定义为深度推理问题的第一步。我们提出了 EmotionThinker，旨在生成基于细粒度声学线索的准确情感预测及可解释说明。为实现这一目标，我们首先构建了 EmotionCoT-35K，一个包含思维链标注和详细描述的情感推理数据集。其次，我们观察到当前 SpeechLLM 的韵律感知能力较弱，而韵律线索是解读情感的基本信号。为此，我们开发了韵律增强的基础模型 EmotionThinker-Base，并证明韵律增强能够改善情感理解。第三，我们引入了带有渐进式可信推理奖励的群体相对策略优化（GRPO-PTR）用于强化学习。与仅依赖基于规则的结果奖励的标准 GRPO 不同，GRPO-PTR 渐进式地引入推理奖励，通过反映推理与结果对齐程度的可信度权重动态调整奖励，并基于多维标准的奖励模型评估整体推理质量。EmotionThinker 在情感准确率和解释质量方面均优于先前最先进的评估模型，推动 SER 向可解释的多模态推理方向发展。

**背景**: 语音中的情感信息在多模态感知中具有独特作用。然而，当前 Speech Large Language Models(SpeechLLMs)与传统语音情感识别(SER)系统类似，仍将情感理解视为简单的分类问题，提供有限的可解释性，同时未充分利用 LLM 的表达和推理能力。

**动机**: 现有方法面临三大挑战：(1) 缺乏高质量数据集，现有情感语料库缺少推理所需的细粒度声学标注；(2) 基础模型的韵律感知能力薄弱，当前 SpeechLLMs 难以处理声学线索；(3) 标准 rule-based RL 奖励的局限性，仅优化结果准确率不足以监督推理质量。

**创新点**:
1. 首次将语音情感识别重新定义为基于强化学习的深度推理问题，提出 EmotionThinker 框架
2. 构建 EmotionCoT-35K 数据集，包含 Chain-of-Thought 标注和详细声学描述
3. 开发韵律增强基础模型 EmotionThinker-Base，证明韵律增强可提升情感理解能力
4. 提出 GRPO-PTR(Group-Relative-Policy-Optimization with Progressive-Trust-aware-Reasoning-Reward)，渐进式引入推理奖励

**开源代码**: 未提供

---

## 206. Mastering Sparse CUDA Generation through Pretrained Models and Deep Reinforcement Learning

**通过预训练模型和深度强化学习精通稀疏CUDA代码生成**

**OpenReview**: [https://openreview.net/forum?id=VdLEaGPYWT](https://openreview.net/forum?id=VdLEaGPYWT)

**Authors**: Yaoyu Wang (University of Chinese Academy of Sciences), Hankun Dai (University of the Chinese Academy of Sciences), Zhidong Yang (Hong Kong University of Science and Technology), Junmin Xiao (Institute of Computing Technology, Chinese Academy of Sciences), Guangming Tan (Insitute of Computing Technology, Chinese Academy of Sciences)

**Institutions**: University of Chinese Academy of Sciences, University of the Chinese Academy of Sciences, Hong Kong University of Science and Technology, Institute of Computing Technology, Chinese Academy of Sciences, Insitute of Computing Technology, Chinese Academy of Sciences

**Primary Area**: reinforcement learning

**Keywords**: Reinforcement Learning, CUDA Code Generation, High-Performance Computing

**TL;DR**: We propose SparseRL, a deep reinforcement learning framework that generates high-performance CUDA code for sparse matrix operations, achieving significant improvements in both correctness and execution efficiency.

**TL;DR翻译**: 我们提出了 SparseRL，一个深度强化学习框架，用于生成面向稀疏矩阵运算的高性能 CUDA 代码，在正确性和执行效率方面均取得了显著提升。

**Abstract**:

Code generation is a crucial research area in the field of artificial intelligence, holding the potential to revolutionize software development and streamline programming processes. However, generating the high-performance code, which need to be executed in a shorter time for the low-latency scenario, remains a formidable challenge. Existing methods often struggle to account for the irregularity of input sparse data in sparse programs and the need for domain-specific architectural knowledge, leading to sub-optimal performance. To tackle these issues, we propose the SparseRL framework. SparseRL leverages deep reinforcement learning, treating a pre-trained language model as a stochastic policy. It takes the row and column indices of non-zero elements in the sparse matrix as input and generates CUDA code as output for sparse matrix operations. We also introduce a domain-specific code generation mechanism for the dynamic input, a sinusoidal embedding technique tailored for sparse matrices, and a hierarchical reward function that considers both code correctness and execution efficiency. Experimental results demonstrate SparseRL achieves state-of-the-art performance. In sparse matrix-vector multiplication (SpMV) tasks, it improves the compilation rate by 20% compared to existing methods, and the generated code runs 30% faster on average. For sparse matrix-dense matrix multiplication (SpMM) tasks, SparseRL also shows significant performance gains. These results highlight the effectiveness of SparseRL in generating high-performance CUDA code for sparse matrix operations.

**摘要翻译**:

代码生成是人工智能领域的一个关键研究方向，有望革新软件开发并简化编程流程。然而，生成需要在低延迟场景下以更短时间执行的高性能代码仍是一项艰巨的挑战。现有方法往往难以处理稀疏程序中输入稀疏数据的不规则性以及对领域特定架构知识的需求，导致性能次优。为解决这些问题，我们提出了 SparseRL 框架。SparseRL 利用深度强化学习，将预训练语言模型视为随机策略。它以稀疏矩阵中非零元素的行列索引作为输入，生成用于稀疏矩阵运算的 CUDA 代码作为输出。我们还引入了面向动态输入的领域特定代码生成机制、为稀疏矩阵定制的正弦嵌入技术，以及同时考虑代码正确性和执行效率的层次化奖励函数。实验结果表明 SparseRL 达到了最先进的性能。在稀疏矩阵-向量乘法（SpMV）任务中，与现有方法相比编译率提升了 20%，生成的代码平均运行速度快 30%。在稀疏矩阵-稠密矩阵乘法（SpMM）任务中，SparseRL 也展现了显著的性能提升。这些结果突显了 SparseRL 在生成面向稀疏矩阵运算的高性能 CUDA 代码方面的有效性。

**背景**: 代码生成是人工智能领域的重要研究方向。然而，生成需要在更短时间内执行的高性能代码（适用于低延迟场景）仍是一个巨大挑战。现有方法难以处理稀疏程序中输入数据的不规则性以及领域特定的架构知识需求。

**动机**: 高性能计算(HPC)代码生成的难点在于两方面：(1) 稀疏程序的执行模式是动态的，依赖于输入稀疏数据，只能在运行时确定；(2) 有效的性能优化需要领域特定的架构专业知识。现有方法使用传统监督的 next-token prediction 目标训练，无法直接优化代码的执行效率。

**创新点**:
1. 提出 SparseRL 框架，利用深度强化学习将预训练语言模型视为随机策略，以稀疏矩阵的非零元素行列索引为输入，生成 CUDA 代码
2. 引入面向动态输入的领域特定代码生成机制，以及专为稀疏矩阵设计的正弦位置嵌入技术
3. 设计层次化奖励函数，同时考虑代码正确性和执行效率
4. 在 SpMV 任务上编译率提升 20%，生成代码平均运行速度提升 30%

**开源代码**: https://github.com/QiWu-NCIC/SparseRL

---

## 207. LongWriter-Zero: Mastering Ultra-Long Text Generation via Reinforcement Learning

**LongWriter-Zero：通过强化学习掌握超长文本生成**

**OpenReview**: [https://openreview.net/forum?id=JWx4DI2N8k](https://openreview.net/forum?id=JWx4DI2N8k)

**Authors**: Yuhao Wu (Singapore University of Technology and Design), Yushi Bai (Tsinghua University, Tsinghua University), Zhiqiang Hu (Tencent Hunyuan Multimodal), Roy Ka-Wei Lee (Singapore University of Technology and Design), Juanzi Li

**Institutions**: Singapore University of Technology and Design, Tsinghua University, Tsinghua University, Tencent Hunyuan Multimodal

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLMs, RL, Long-form generation

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

Ultra-long generation by large language models (LLMs) is a widely demanded scenario, yet it remains a significant challenge due to their maximum generation length limit and overall quality degradation as sequence length increases. Previous approaches, exemplified by LongWriter, typically rely on ''teaching'', which involves supervised fine-tuning (SFT) on synthetic long-form outputs. However, this strategy heavily depends on synthetic SFT data, which is difficult and costly to construct, often lacks coherence and consistency, and tends to be overly artificial and structurally monotonous. In this work, we propose an incentivization-based approach that, starting entirely from scratch and without relying on any annotated or synthetic data, leverages reinforcement learning (RL) to foster the emergence of ultra-long, high-quality text generation capabilities in LLMs. We perform RL training starting from a base model, similar to R1-Zero, guiding it to engage in reasoning that facilitates planning and refinement during the writing process. To support this, we employ specialized reward models that steer the LLM towards improved length control, writing quality, and structural formatting. Experimental evaluations show that our LongWriter-Zero model, trained from Qwen2.5-32B, consistently outperforms traditional SFT methods on long-form writing tasks, achieving state-of-the-art results across all metrics on WritingBench and Arena-Write, and even surpassing 100B+ models such as DeepSeek R1 and Qwen3-235B.

**摘要翻译**:

大语言模型（LLM）的超长文本生成是一个广泛需求的应用场景，但由于其最大生成长度限制以及序列长度增加时整体质量下降，这仍然是一个重大挑战。以 LongWriter 为代表的先前方法通常依赖"教学"策略，即在合成的长文本输出上进行监督微调（SFT）。然而，这种策略严重依赖合成 SFT 数据，而这些数据构建困难且成本高昂，往往缺乏连贯性和一致性，且倾向于过度人工化和结构单调。在本工作中，我们提出了一种基于激励的方法，完全从零开始、不依赖任何标注或合成数据，利用强化学习（RL）促使 LLM 涌现出超长高质量文本生成能力。我们从基础模型开始进行 RL 训练，类似于 R1-Zero，引导其在写作过程中进行有助于规划和优化的推理。为此，我们采用专门的奖励模型来引导 LLM 在长度控制、写作质量和结构格式方面不断改进。实验评估表明，我们基于 Qwen2.5-32B 训练的 LongWriter-Zero 模型在长文本写作任务上始终优于传统 SFT 方法，在 WritingBench 和 Arena-Write 的所有指标上均达到了最先进的结果，甚至超越了 DeepSeek R1 和 Qwen3-235B 等 100B 以上参数的模型。

**背景**: 超长文本生成是 LLM 的一个广泛需求场景，但仍面临最大生成长度限制和序列变长时整体质量下降的挑战。以 LongWriter 为代表的先前方法通常依赖对合成长文本输出的监督微调(SFT)，但该策略严重依赖合成 SFT 数据，构建成本高、缺乏连贯性和一致性。

**动机**: SFT 方法存在两个关键局限：(1) 训练数据由现有 LLM 构建，限制了写作风格的多样性和创新性；(2) 最大似然目标无法为优化全局属性（如连贯性、格式一致性）提供显式信号。作者假设类似 DeepSeek-R1-Zero 在数学/代码推理领域的成功，RL 驱动的方法同样能使 LLM 产生更长、更连贯的输出。

**创新点**:
1. 首创从零开始使用强化学习激活 LLM 超长文本生成能力的框架（无需任何标注或合成数据），类似 R1-Zero 的范式
2. 引导模型在写作过程中进行推理（规划和修改），采用专门的 reward model 引导长度控制、写作质量和结构格式
3. 系统探究了三个关键研究问题：奖励设计、test-time scaling、持续预训练
4. 基于 Qwen2.5-32B 训练的 LongWriter-Zero 在 WritingBench 和 Arena-Write 上达到 SOTA，超越 100B+ 模型

**开源代码**: 未提供（论文声明发表后计划开源训练框架、reward model 和模型权重）

---

## 222. Reasoning as Representation: Rethinking Visual Reinforcement Learning in Image Quality Assessment

**推理即表示：重新审视图像质量评估中的视觉强化学习**

**OpenReview**: [https://openreview.net/forum?id=DkHt2K1g2Y](https://openreview.net/forum?id=DkHt2K1g2Y)

**Authors**: Shijie Zhao (ByteDance Inc.), Xuanyu Zhang (Peking University), Weiqi Li (Peking University), Junlin Li (ByteDance Inc.), Li zhang (Bytedance Inc.), Tianfan Xue (The Chinese University of Hong Kong), Jian Zhang (Peking University)

**Institutions**: ByteDance Inc., Peking University, Bytedance Inc., The Chinese University of Hong Kong

**Primary Area**: reinforcement learning

**Keywords**: Image Quality Assessment, Low Level Vision, Multimodal Large Language Model

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

Reasoning-based image quality assessment (IQA) models trained through reinforcement learning (RL) exhibit exceptional generalization, yet the underlying mechanisms and critical factors driving this capability remain underexplored in current research. Moreover, despite their superior performance, these models incur inference energy usage and latency orders of magnitude higher than their earlier counterparts, restricting their deployment in specific scenarios. Through extensive experiments, this paper verifies and elaborates that through RL training, MLLMs leverage their reasoning capability to convert redundant visual representations into compact, cross-domain aligned text representations. This conversion is precisely the source of the generalization exhibited by these reasoning-based IQA models. Building on this fundamental insight, we propose a novel algorithm, RALI, which employs contrastive learning to directly align images with these generalizable text representations learned by RL. This approach eliminates the reliance on reasoning processes and even obviates the need to load an LLM. For the quality scoring task, this framework achieves generalization performance comparable to reasoning-based models while requiring less than 5% of their model parameters and inference time.

**摘要翻译**:

通过强化学习（RL）训练的基于推理的图像质量评估（IQA）模型展现出卓越的泛化能力，然而驱动这一能力的底层机制和关键因素在当前研究中尚未被充分探索。此外，尽管这些模型性能优越，但其推理能耗和延迟比早期模型高出数个数量级，限制了在特定场景中的部署。通过大量实验，本文验证并阐述了这样一个事实：通过 RL 训练，MLLM 利用其推理能力将冗余的视觉表示转换为紧凑的、跨域对齐的文本表示。这种转换正是基于推理的 IQA 模型所展现的泛化能力的根本来源。基于这一根本性洞察，我们提出了一种新颖的算法 RALI，它采用对比学习将图像直接与 RL 所学到的可泛化文本表示进行对齐。这种方法消除了对推理过程的依赖，甚至无需加载 LLM。在质量评分任务上，该框架实现了与基于推理的模型相当的泛化性能，而所需的模型参数和推理时间不到后者的 5%。

**背景**: 基于推理的图像质量评估(IQA)模型通过强化学习(RL)训练后展现出卓越的泛化能力。然而，这些模型的推理过程带来的能耗和延迟比传统方法高出数个数量级，限制了其在特定场景中的部署。

**动机**: 当前 RL-based IQA 模型（如 Q-Insight）虽然性能优异，但存在两个核心问题：(1) 其泛化提升的原理缺乏系统分析；(2) 逐步推理带来高延迟和大参数量开销。作者发现关键洞察：RL 方法使 MLLM 获得了一种降维策略——通过推理将高维视觉表征映射为紧凑的文本表征，实现 10 倍以上压缩。

**创新点**:
1. 系统验证并阐明了 RL 训练中推理与泛化的关系：MLLM 通过 RL 学会将冗余的视觉表征转换为紧凑的、跨域对齐的文本表征
2. 提出 RALI(Reasoning-Aligned Lightweight IQA)算法，利用对比学习将图像直接与 RL 学到的可泛化文本表征对齐，消除对推理过程的依赖
3. 在质量评分任务上，RALI 以不到 5% 的模型参数和推理时间，达到与推理型模型相当的泛化性能

**开源代码**: https://github.com/xuanyuzhang21/RALI

---

