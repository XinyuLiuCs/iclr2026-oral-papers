# ICLR 2026 Oral Papers - 中英双语翻译

Total: 223 papers

Source: https://openreview.net/group?id=ICLR.cc/2026/Conference#tab-accept-oral

翻译说明：标题、TL;DR、摘要提供中英双语对照（英文在上，中文在下）。作者、机构、关键词等元数据保留原文。

---

## 1. Common Corpus: The Largest Collection of Ethical Data for LLM Pre-Training

**Common Corpus：面向LLM预训练的最大合规数据集**

**OpenReview**: [https://openreview.net/forum?id=0wSlFpMsGb](https://openreview.net/forum?id=0wSlFpMsGb)

**Authors**: Pierre-Carl Langlais (Pleias), Pavel Chizhov (Technical University of Applied Sciences Würzburg-Schweinfurt), Catherine Arnett (EleutherAI), Carlos Rosas Hinostroza (Université Sorbonne-Nouvelle (Paris III)), Mattia Nee (pleias), Eliot Krzysztof Jones (Gray Swan), Irène Girard (Université Gustave Eiffel), David Mach (Institut d'Etudes Politiques de Paris (Sciences Po)), Anastasia Stasenko (Sorbonne Université - Faculté des Sciences (Paris VI)), Ivan P. Yamshchikov (Technical University of Applied Sciences Würzburg-Schweinfurt)

**Institutions**: Pleias, Technical University of Applied Sciences Würzburg-Schweinfurt, EleutherAI, Université Sorbonne-Nouvelle (Paris III), pleias, Gray Swan, Université Gustave Eiffel, Institut d'Etudes Politiques de Paris (Sciences Po), Sorbonne Université - Faculté des Sciences (Paris VI)

**Primary Area**: datasets and benchmarks

**Keywords**: dataset, pre-training, large language models, open data, open science, multilingual

**TL;DR**: We assemble and release the largest truly open multilingual dataset for LLM pre-training consisting of 2 trillion tokens

**TL;DR翻译**: 我们构建并发布了迄今最大的真正开放的多语言LLM预训练数据集，包含2万亿token。

**Abstract**:

Large Language Models (LLMs) are pre-trained on large data from different sources and domains. These data most often contain trillions of tokens with large portions of copyrighted or proprietary content, which hinders the usage of such models under AI legislation. This raises the need for truly open pre-training data that is compliant with the data security regulations. In this paper, we introduce Common Corpus, the largest open dataset for LLM pre-training. The data assembled in Common Corpus are either uncopyrighted or under permissible licenses and amount to about two trillion tokens. The dataset contains a wide variety of languages, ranging from the high-resource European languages to some low-resource languages rarely represented in pre-training datasets. In addition, it includes a large portion of code data. The diversity of data sources in terms of covered domains and time periods opens up the paths for both research and entrepreneurial needs in diverse areas of knowledge. In this paper, we present the detailed provenance of data assembling and the details of dataset filtering and curation. We train two small language models on Common Corpus and find that the resulting model performs comparably to other models of their size, indicating that our dataset is suitable for multilingual pretraining. Common Corpus represents a key contribution to the ecosystem for open science research on large language models.

**摘要翻译**:

大语言模型（LLMs）基于来自不同来源和领域的大规模数据进行预训练。这些数据通常包含数万亿token，其中大量内容受版权或专有权保护，这在AI相关法规下限制了此类模型的使用。因此，亟需符合数据安全法规的真正开放的预训练数据。本文介绍了Common Corpus——目前最大的开放LLM预训练数据集。Common Corpus中的数据均为无版权或采用许可性开放协议的内容，总量约为2万亿token。该数据集涵盖多种语言，从高资源的欧洲语言到在预训练数据集中鲜有出现的低资源语言。此外，它还包含大量代码数据。数据来源在所覆盖的领域和时间跨度上的多样性，为不同知识领域的科研和商业需求开辟了道路。本文详细介绍了数据的来源追溯以及数据集的过滤与整理细节。我们在Common Corpus上训练了两个小型语言模型，发现其性能与同等规模的其他模型相当，表明该数据集适用于多语言预训练。Common Corpus为大语言模型的开放科学研究生态做出了重要贡献。

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

---

## 3. From movement to cognitive maps: recurrent neural networks reveal how locomotor development shapes hippocampal spatial coding

**从运动到认知地图：循环神经网络揭示运动发育如何塑造海马体空间编码**

**OpenReview**: [https://openreview.net/forum?id=8bM7MkxJee](https://openreview.net/forum?id=8bM7MkxJee)

**Authors**: Marco P Abrate (University College London, University of London), Laurenz Muessig (University College London, University of London), Joshua P Bassett (University College London, University of London), Hui Min Tan (Animal Concerns Research & Education Society), Francesca Cacucci (University College London, University of London), Thomas Joseph Wills (University College London, University of London), Caswell Barry (University College London)

**Institutions**: University College London, University of London, Animal Concerns Research & Education Society, University College London

**Primary Area**: applications to neuroscience & cognitive science

**Keywords**: recurrent neural network, spatial representations, hippocampus, development, locomotion, rats

**Abstract**:

The hippocampus contains neurons whose firing correlates with an animal's location and orientation in space. Collectively, these neurons are held to support a cognitive map of the environment, enabling the recall of and navigation to specific locations. Although recent studies have characterised the timelines of spatial neuron development, no unifying mechanistic model has yet been proposed. Moreover, the processes driving the emergence of spatial representations in the hippocampus remain unclear (Tan et al., 2017). Here, we combine computational analysis of postnatal locomotor development with a recurrent neural network (RNN) model of hippocampal function to demonstrate how changes in movement statistics -- and the resulting sensory experiences -- shape the formation of spatial tuning. First, we identify distinct developmental stages in rat locomotion during open-field exploration using published experimental data. Then, we train shallow RNNs to predict upcoming visual stimuli from concurrent visual and vestibular inputs, exposing them to trajectories that reflect progressively maturing locomotor patterns. Our findings reveal that these changing movement statistics drive the sequential emergence of spatially tuned units, mirroring the developmental timeline observed in rats. The models generate testable predictions about how spatial tuning properties mature -- predictions we confirm through analysis of hippocampal recordings. Critically, we demonstrate that replicating the specific statistics of developmental locomotion -- rather than merely accelerating sensory change -- is essential for the emergence of an allocentric spatial representation. These results establish a mechanistic link between embodied sensorimotor experience and the ontogeny of hippocampal spatial neurons, with significant implications for neurodevelopmental research and predictive models of navigational brain circuits.

**摘要翻译**:

海马体中的神经元放电与动物在空间中的位置和朝向相关。这些神经元被认为共同支撑着环境的认知地图，使得动物能够回忆并导航到特定位置。尽管近年来的研究已刻画了空间神经元发育的时间线，但尚未提出统一的机制模型。此外，驱动海马体空间表征涌现的过程仍不清楚（Tan et al., 2017）。本文将出生后运动发育的计算分析与海马功能的循环神经网络（RNN）模型相结合，展示了运动统计特性的变化——以及由此产生的感觉经验——如何塑造空间调谐的形成。首先，我们利用已发表的实验数据识别了大鼠在开放场地探索中运动发育的不同阶段。随后，我们训练浅层RNN根据同步的视觉和前庭输入预测即将到来的视觉刺激，并使其接触反映逐步成熟的运动模式的轨迹。研究发现，这些变化的运动统计特性驱动了空间调谐单元的顺序涌现，与大鼠中观察到的发育时间线相吻合。模型产生了关于空间调谐特性如何成熟的可检验预测——这些预测通过对海马体记录的分析得到了验证。关键的是，我们证明了复现运动发育的特定统计特性——而不仅仅是加速感觉变化——对于异位中心空间表征的涌现至关重要。这些结果建立了具身感觉运动经验与海马体空间神经元个体发育之间的机制联系，对神经发育研究和导航脑回路的预测模型具有重要意义。

---

## 4. FIRE: Frobenius-Isometry Reinitialization for Balancing the Stability–Plasticity Tradeoff

**FIRE：通过Frobenius等距重新初始化平衡稳定性-可塑性权衡**

**OpenReview**: [https://openreview.net/forum?id=CfZLxT3zIZ](https://openreview.net/forum?id=CfZLxT3zIZ)

**Authors**: Isaac Han (Gwangju Institute of Science and Technology), Sangyeon Park (Gwangju Institute of Science and Technology), Seungwon Oh (Gwangju Institute of Science and Technology), Donghu Kim (Korea Advanced Institute of Science & Technology), Hojoon Lee (Krafton AI), KyungJoong Kim (Gwangju Institute of Science and Technology)

**Institutions**: Gwangju Institute of Science and Technology, Korea Advanced Institute of Science & Technology, Krafton AI

**Primary Area**: transfer learning, meta learning, and lifelong learning

**Keywords**: stability-plasticity tradeoff, continual learning

**TL;DR**: We present FIRE, a principled reinitialization approach that balances stability and plasticity through constrained optimization.

**TL;DR翻译**: 我们提出FIRE，一种通过约束优化来平衡稳定性与可塑性的原则性重新初始化方法。

**Abstract**:

Deep neural networks trained on nonstationary data must balance stability (i.e., retaining prior knowledge) and plasticity (i.e., adapting to new tasks). Standard reinitialization methods, which reinitialize weights toward their original values, are widely used but difficult to tune: conservative reinitializations fail to restore plasticity, while aggressive ones erase useful knowledge. We propose FIRE, a principled reinitialization method that explicitly balances the stability–plasticity tradeoff. FIRE quantifies stability through Squared Frobenius Error (SFE), measuring proximity to past weights, and plasticity through Deviation from Isometry (DfI), reflecting weight isotropy. The reinitialization point is obtained by solving a constrained optimization problem, minimizing SFE subject to DfI being zero, which is efficiently approximated by Newton–Schulz iteration. FIRE is evaluated on continual visual learning (CIFAR-10 with ResNet-18), language modeling (OpenWebText with GPT-0.1B), and reinforcement learning (HumanoidBench with SAC and Atari games with DQN). Across all domains, FIRE consistently outperforms both naive training without intervention and standard reinitialization methods, demonstrating effective balancing of the stability–plasticity tradeoff.

**摘要翻译**:

在非平稳数据上训练的深度神经网络必须在稳定性（即保留先前知识）和可塑性（即适应新任务）之间取得平衡。标准的重新初始化方法将权重恢复到原始值附近，虽被广泛使用但难以调节：保守的重新初始化无法恢复可塑性，而激进的则会擦除有用知识。我们提出FIRE，一种显式平衡稳定性-可塑性权衡的原则性重新初始化方法。FIRE通过Frobenius平方误差（SFE）量化稳定性，衡量与历史权重的接近程度；通过偏离等距度（DfI）量化可塑性，反映权重的各向同性。重新初始化点通过求解约束优化问题得到，即在DfI为零的约束下最小化SFE，该问题通过Newton-Schulz迭代高效近似求解。FIRE在持续视觉学习（CIFAR-10配合ResNet-18）、语言建模（OpenWebText配合GPT-0.1B）和强化学习（HumanoidBench配合SAC及Atari游戏配合DQN）上进行了评估。在所有领域中，FIRE均始终优于无干预的朴素训练和标准重新初始化方法，展示了对稳定性-可塑性权衡的有效平衡。

---

## 5. Exchangeability of GNN Representations with Applications to Graph Retrieval

**GNN表示的可交换性及其在图检索中的应用**

**OpenReview**: [https://openreview.net/forum?id=HQcCd0laFq](https://openreview.net/forum?id=HQcCd0laFq)

**Authors**: Kartik Nair (Carnegie Mellon University), Indradyumna Roy (Indian Institute of Technology Bombay), Soumen Chakrabarti (Indian Institute of Technology Bombay), Anirban Dasgupta (IIT Gandhinagar), Abir De (Indian Institute of Technology Bombay,)

**Institutions**: Carnegie Mellon University, Indian Institute of Technology Bombay, IIT Gandhinagar, Indian Institute of Technology Bombay,

**Primary Area**: learning on graphs and other geometries & topologies

**Keywords**: GNN, Locality sensitive hashing

**TL;DR**: It shows that graph representations are exchangeable random variables which can help in LSH in graphs

**TL;DR翻译**: 本文证明图表示是可交换随机变量，这一性质有助于在图上进行局部敏感哈希。

**Abstract**:

In this work, we discover a probabilistic symmetry, called as exchangeability in graph neural networks (GNNs). Specifically, we show that the trained node embedding computed using a large family of graph neural networks, learned under standard optimization tools, are exchangeable random variables. This implies that the probability density of the node embeddings remains invariant with respect to a permutation applied on their dimension axis. This results in identical distribution across the elements of the graph representations. Such a property enables approximation of transportation-based graph similarities by Euclidean similarities between order statistics. Leveraging this reduction, we propose a unified locality-sensitive hashing (LSH) framework that supports diverse relevance measures, including subgraph matching and graph edit distance. Experiments show that our method helps to do LSH more effectively than baselines.

**摘要翻译**:

本文发现了图神经网络（GNNs）中的一种概率对称性，即可交换性。具体而言，我们证明了使用大类图神经网络在标准优化工具下训练得到的节点嵌入是可交换随机变量。这意味着节点嵌入的概率密度对其维度轴上的置换保持不变，从而使得图表示的各元素具有相同的分布。这一性质使得可以用顺序统计量之间的欧氏相似度来近似基于运输的图相似度。利用这一简化，我们提出了一个统一的局部敏感哈希（LSH）框架，支持多种相关性度量，包括子图匹配和图编辑距离。实验表明，我们的方法比基线方法更有效地实现了LSH。

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

---

## 8. WebDevJudge: Evaluating (M)LLMs as Critiques for Web Development Quality

**WebDevJudge：评估（多模态）LLM作为Web开发质量评审者的能力**

**OpenReview**: [https://openreview.net/forum?id=CCSPm6V5EF](https://openreview.net/forum?id=CCSPm6V5EF)

**Authors**: Chunyang Li (Department of Computer Science and Engineering, Hong Kong University of Science and Technology), Yilun Zheng (Nanyang Technological University), Xinting Huang (Tencent), Tianqing Fang (Tencent AI Lab), Jiahao Xu (Tencent AI Lab), Lihui Chen (Nanyang Technological University), Yangqiu Song (Hong Kong University of Science and Technology), Han Hu (Tencent Hunyuan Research)

**Institutions**: Department of Computer Science and Engineering, Hong Kong University of Science and Technology, Nanyang Technological University, Tencent, Tencent AI Lab, Hong Kong University of Science and Technology, Tencent Hunyuan Research

**Primary Area**: datasets and benchmarks

**Keywords**: large language models, evaluation, LLM-as-a-judge, benchmark

**TL;DR**: A meta-evaluation benchmark for assessing LLM-as-a-judge in the context of web development.

**TL;DR翻译**: 一个用于评估LLM作为评审者在Web开发场景中表现的元评估基准。

**Abstract**:

The paradigm of LLM-as-a-judge is emerging as a scalable and efficient alternative to human evaluation, demonstrating strong performance on well-defined tasks. However, its reliability in open-ended tasks with dynamic environments and complex interactions remains unexplored. To bridge the gap, we introduce WebDevJudge, a systematic benchmark for assessing LLM-as-a-judge performance in web development, with support for both non-interactive evaluation based on static observations and continuous interactive evaluation with a dynamic web environment. WebDevJudge comprises human preference labels over paired web implementations, annotated with structured and query-grounded rubrics to ensure high-quality ground truth. Using this benchmark, we comprehensively evaluate various evaluators, including LLMs, MLLMs, and agentic workflows. We systematically investigate the impact of different paradigms and guidance mechanisms. Our experiments reveal a significant gap between LLM judges and human experts. In-depth analysis indicates this gap stems from fundamental model limitations, including failures in recognizing functional equivalence, verifying task feasibility, and mitigating bias. Overall, WebDevJudge presents a significant challenge to LLM-as-a-judge, offering insights to guide future research toward developing more reliable and capable automated evaluators for complicated scenarios.

**摘要翻译**:

LLM作为评审者的范式正在成为人工评估的可扩展且高效的替代方案，在定义明确的任务上表现出色。然而，其在具有动态环境和复杂交互的开放式任务中的可靠性仍未被探索。为弥补这一差距，我们引入WebDevJudge，一个系统性的基准，用于评估LLM作为评审者在Web开发中的表现，同时支持基于静态观测的非交互式评估和在动态Web环境中的持续交互式评估。WebDevJudge包含对成对Web实现的人类偏好标注，并附有结构化和基于查询的评分标准以确保高质量的真实标签。利用该基准，我们全面评估了各类评估器，包括LLM、多模态LLM和智能体工作流。我们系统地研究了不同范式和引导机制的影响。实验揭示了LLM评审者与人类专家之间的显著差距。深入分析表明，这一差距源于模型的根本性局限，包括无法识别功能等价性、验证任务可行性以及消除偏差。总体而言，WebDevJudge对LLM作为评审者提出了重大挑战，为未来开发更可靠、更强大的自动化评估器的研究提供了指导。

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

---

## 10. MedAgentGym: A Scalable Agentic Training Environment for Code-Centric Reasoning in Biomedical Data Science

**MedAgentGym：面向生物医学数据科学中代码中心推理的可扩展智能体训练环境**

**OpenReview**: [https://openreview.net/forum?id=jHDZEUgS4r](https://openreview.net/forum?id=jHDZEUgS4r)

**Authors**: Ran Xu (Google DeepMind), Yuchen Zhuang (Google DeepMind), Yishan Zhong (Georgia Institute of Technology), Yue Yu (Meta), Zifeng Wang, Xiangru Tang (Yale University), Hang Wu (ByteDance Inc), May Dongmei Wang (Georgia Institute of Technology), Peifeng Ruan (University of Texas Southwestern Medical Center), Donghan Yang (University of Texas Southwestern Medical Center), Tao Wang (University of Texas Southwestern Medical Center), Guanghua Xiao (University of Texas Southwestern Medical Center), Xin Liu (Google), Carl Yang (Emory University), Yang Xie (UT Southwestern Medical Center), Wenqi Shi (University of Texas Southwestern Medical Center)

**Institutions**: Google DeepMind, Georgia Institute of Technology, Meta, Yale University, ByteDance Inc, University of Texas Southwestern Medical Center, Google, Emory University, UT Southwestern Medical Center

**Primary Area**: datasets and benchmarks

**Keywords**: Medical Reasoning, LLM Agent, Code Generation

**TL;DR**: MedAgentGym is a scalable and interactive training environment designed to enhance coding-based biomedical reasoning capabilities in LLM agents.

**TL;DR翻译**: MedAgentGym是一个可扩展的交互式训练环境，旨在增强LLM智能体在生物医学领域基于代码的推理能力。

**Abstract**:

We introduce MedAgentGym, a scalable and interactive training environment designed to enhance coding-based biomedical reasoning capabilities in large language model (LLM) agents. MedAgentGym comprises 72,413 task instances across 129 categories derived from 12 authentic real-world biomedical scenarios. Tasks are encapsulated within executable sandbox environments, each featuring detailed task specifications, interactive feedback mechanisms, verifiable ground truth annotations, and scalable training trajectory generation. Extensive benchmarking of 29 LLMs reveals substantial performance disparities in biomedical data science between commercial and open-source LLMs. Leveraging efficient multi-threaded and multi-turn trajectory sampling in MedAgentGym, Med-Copilot achieves performance gains of +43.02% and +45.28% from offline and online reinforcement learning, respectively, demonstrating MedAgentGym as an effective training ground while establishing itself as a cost-effective, privacy-preserving alternative competitive with proprietary LLMs (gpt-4o). By offering a unified execution environment with a comprehensive benchmark and accessible, extensible training resources, MedAgentGym delivers an integrated platform to develop LLM-based coding assistants for advanced biomedical data science.

**摘要翻译**:

我们介绍了MedAgentGym，一个可扩展的交互式训练环境，旨在增强大语言模型（LLM）智能体基于代码的生物医学推理能力。MedAgentGym包含来自12个真实生物医学场景的129个类别共72,413个任务实例。任务被封装在可执行的沙盒环境中，每个环境均具备详细的任务规范、交互反馈机制、可验证的真实标注以及可扩展的训练轨迹生成功能。对29个LLM的广泛基准测试揭示了商业与开源LLM在生物医学数据科学领域的显著性能差距。借助MedAgentGym中高效的多线程和多轮轨迹采样，Med-Copilot分别通过离线和在线强化学习实现了+43.02%和+45.28%的性能提升，证明了MedAgentGym作为有效训练场的价值，同时确立了其作为与专有LLM（gpt-4o）具有竞争力的、经济高效且隐私保护的替代方案。通过提供统一的执行环境、全面的基准和可访问、可扩展的训练资源，MedAgentGym为开发面向高级生物医学数据科学的LLM编码助手提供了一个集成平台。

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

---

## 12. CounselBench: A Large-Scale Expert Evaluation and Adversarial Benchmarking of Large Language Models in Mental Health Question Answering

**CounselBench：大语言模型在心理健康问答中的大规模专家评估与对抗性基准测试**

**OpenReview**: [https://openreview.net/forum?id=8MBYRZHVWT](https://openreview.net/forum?id=8MBYRZHVWT)

**Authors**: Yahan Li, Jifan Yao (University of Southern California), John Bosco S. Bunyi (University of Southern California), Adam C Frank (University of Southern California), Angel Hsing-Chi Hwang (University of Southern California), Ruishan Liu (University of Southern California)

**Institutions**: University of Southern California

**Primary Area**: datasets and benchmarks

**Keywords**: large language models, mental health, human evaluation

**Abstract**:

Medical question answering (QA) benchmarks often focus on multiple-choice or fact-based tasks, leaving open-ended answers to real patient questions underexplored. This gap is particularly critical in mental health, where patient questions often mix symptoms, treatment concerns, and emotional needs, requiring answers that balance clinical caution with contextual sensitivity. We present CounselBench, a large-scale benchmark developed with 100 mental health professionals to evaluate and stress-test large language models (LLMs) in realistic help-seeking scenarios. The first component, CounselBench-EVAL, contains 2,000 expert evaluations of answers from GPT-4, LLaMA 3, Gemini, and online human therapists on patient questions from the public forum CounselChat. Each answer is rated across six clinically grounded dimensions, with span-level annotations and written rationales. Expert evaluations show that while LLMs achieve high scores on several dimensions, they also exhibit recurring issues, including unconstructive feedback, overgeneralization, and limited personalization or relevance. Responses were frequently flagged for safety risks, most notably unauthorized medical advice. Follow-up experiments show that LLM judges systematically overrate model responses and overlook safety concerns identified by human experts. To probe failure modes more directly, we construct CounselBench-Adv, an adversarial dataset of 120 expert-authored mental health questions designed to trigger specific model issues. Expert evaluation of 1,080 responses from nine LLMs reveals consistent, model-specific failure patterns. Together, CounselBench establishes a clinically grounded framework for benchmarking LLMs in mental health QA.

**摘要翻译**:

医学问答（QA）基准通常侧重于选择题或基于事实的任务，对真实患者问题的开放式回答关注不足。这一空白在心理健康领域尤为关键，因为患者的问题常常交织着症状描述、治疗顾虑和情感需求，需要在临床审慎与情境敏感性之间取得平衡。我们提出CounselBench，一个与100位心理健康专业人士合作开发的大规模基准，用于在真实求助场景中评估和压力测试大语言模型（LLMs）。第一个组件CounselBench-EVAL包含2,000条专家评估，涵盖GPT-4、LLaMA 3、Gemini和在线人类治疗师对公共论坛CounselChat上患者问题的回答。每条回答在六个临床维度上进行评分，并附有片段级标注和书面理由。专家评估表明，尽管LLMs在多个维度上取得了高分，但也存在反复出现的问题，包括缺乏建设性的反馈、过度泛化以及有限的个性化或相关性。回答中频繁被标记存在安全风险，最显著的是未经授权的医疗建议。后续实验表明，LLM评审者系统性地高估模型回答并忽视人类专家识别出的安全隐患。为更直接地探查失效模式，我们构建了CounselBench-Adv，一个由120个专家编写的心理健康问题组成的对抗性数据集，旨在触发特定的模型问题。对九个LLM的1,080条回答的专家评估揭示了一致的、模型特异性的失效模式。CounselBench总体上为心理健康问答中的LLM基准测试建立了一个以临床为基础的框架。

---

## 13. AstaBench: Rigorous Benchmarking of AI Agents with a Scientific Research Suite

**AstaBench：基于科学研究套件的AI智能体严格基准测试**

**OpenReview**: [https://openreview.net/forum?id=M7TNf5J26u](https://openreview.net/forum?id=M7TNf5J26u)

**Authors**: Jonathan Bragg (Allen Institute for Artificial Intelligence), Mike D'Arcy (Northwestern University), Nishant Balepur (University of Maryland, College Park), Dan Bareket (Bar-Ilan University), Bhavana Dalvi Mishra (Google), Sergey Feldman (Allen Institute for Artificial Intelligence), Dany Haddad (Allen Institute for Artificial Intelligence), Jena D. Hwang (Allen Institute for Artificial Intelligence), Peter Jansen (University of Arizona), Varsha Kishore (Allen Institute for Artificial Intelligence), Bodhisattwa Prasad Majumder (Allen Institute for Artificial Intelligence), Aakanksha Naik (Allen Institute for Artificial Intelligence), Sigal Rahamimov (Allen Institute for Artificial Intelligence), Kyle Richardson (Allen Institute for Artificial Intelligence), Amanpreet Singh (Allen Institute for Artificial Intelligence), Harshit Surana (Allen Institute for Artificial Intelligence), Aryeh Tiktinsky (Allen Institute for Artificial Intelligence), Rosni Vasu (Universität Bern), Guy Wiener (Allen Institute for Artificial Intelligence), Chloe Anastasiades (Allen Institute for Artificial Intelligence), Stefanus Candra (Allen Institute for Artificial Intelligence), Jason Dunkelberger (Allen Institute for Artificial Intelligence), Daniel Emery (The Allen Institute for Artificial Intelligence), Rob Evans (Allen Institute for Artificial Intelligence), Malachi Hamada (Allen Institute for Artificial Intelligence), Regan Huff (Allen Institute for Artificial Intelligence), Rodney Kinney (Allen Institute for Artificial Intelligence), Matt Latzke (Allen Institute for Artificial Intelligence), Jaron Lochner (Allen Institute for Artificial Intelligence), Ruben Lozano-Aguilera (University of Cambridge), Ngoc-Uyen Nguyen (Allen Institute for Artificial Intelligence), Smita Rao (Allen Institute for Artificial Intelligence), Amber Tanaka (Allen Institute for Artificial Intelligence), Brooke Vlahos (Allen Institute for Artificial Intelligence), Peter Clark (Allen Institute for Artificial Intelligence), Doug Downey (Allen Institute for Artificial Intelligence), Yoav Goldberg (Bar-Ilan University), Ashish Sabharwal (Allen Institute for AI), Daniel S Weld (Allen Institute for Artificial Intelligence)

**Institutions**: Allen Institute for Artificial Intelligence, Northwestern University, University of Maryland, College Park, Bar-Ilan University, Google, University of Arizona, Universität Bern, The Allen Institute for Artificial Intelligence, University of Cambridge, Allen Institute for AI

**Primary Area**: datasets and benchmarks

**Keywords**: Agents, evaluation, benchmarks, scientific research

**TL;DR**: We present principles and tooling for rigorous AI agent benchmarking, instantiated in AstaBench—the first holistic measure of agentic ability for scientific research—plus experiments showing AI remains far from solving research assistance.

**TL;DR翻译**: 我们提出了严格的AI智能体基准测试原则和工具，将其实例化为AstaBench——首个衡量科学研究中智能体能力的整体性基准——并通过实验表明AI距离解决科研辅助问题仍有很大差距。

**Abstract**:

AI agents hold the potential to revolutionize scientific productivity by automating literature reviews, replicating experiments, analyzing data, and even proposing new directions of inquiry; indeed, there are now many such agents, ranging from general-purpose "deep research" systems to specialized science-specific agents, such as AI Scientist and AIGS. Rigorous evaluation of these agents is critical for progress. Yet existing benchmarks fall short on several fronts: they often (1) lack reproducible agent tools necessary for a controlled comparison of core agentic capabilities; (2) do not account for confounding variables such as model cost and tool access; (3) do not provide standardized interfaces for quick agent prototyping and evaluation; (4) fail to provide holistic, product-informed measures of real-world use cases such as science research; and (5) lack comprehensive baseline agents necessary to identify true advances. In response, we define principles and tooling for more rigorously benchmarking agents. Using these, we present AstaBench, a suite that provides a holistic measure of agentic ability to perform scientific research, comprising 2400+ problems spanning the entire scientific discovery process and multiple scientific domains, and including many problems inspired by actual user requests to deployed Asta agents. Our suite comes with the first scientific research environment with production-grade search tools that enable controlled, reproducible evaluation, better accounting for confounders. Alongside, we provide a comprehensive suite of nine science-optimized classes of Asta agents and numerous baselines. Our extensive evaluation of 57 agents across 22 agent classes reveals several interesting findings, most importantly that despite meaningful progress on certain individual aspects, AI remains far from solving the challenge of science research assistance.

**摘要翻译**:

AI智能体有望通过自动化文献综述、复现实验、分析数据乃至提出新的研究方向来革新科学生产力；事实上，现在已有许多此类智能体，从通用的"深度研究"系统到专门的科学领域智能体，如AI Scientist和AIGS。对这些智能体的严格评估对于推动进步至关重要。然而现有基准在多个方面存在不足：它们往往（1）缺乏可复现的智能体工具以控制性地比较核心智能体能力；（2）未考虑模型成本和工具访问等混淆变量；（3）未提供用于快速智能体原型设计和评估的标准化接口；（4）未能提供针对科学研究等真实用例的全面、产品导向的度量指标；（5）缺乏识别真正进步所需的完整基线智能体。为此，我们定义了更严格的智能体基准测试原则和工具。基于此，我们提出AstaBench，一个提供科学研究智能体能力整体度量的测试套件，包含2400多个问题，覆盖整个科学发现过程和多个科学领域，其中许多问题来源于已部署Asta智能体的实际用户请求。我们的套件配备了首个具有生产级搜索工具的科学研究环境，支持可控、可复现的评估，更好地控制混淆因素。同时，我们提供了九类科学优化的Asta智能体和众多基线的完整套件。我们对22类共57个智能体的广泛评估揭示了多项有趣发现，最重要的是：尽管在某些单独方面取得了有意义的进展，AI距离解决科研辅助这一挑战仍然遥远。

---

## 14. Neon: Negative Extrapolation From Self-Training Improves Image Generation

**Neon：自训练的负向外推改进图像生成**

**OpenReview**: [https://openreview.net/forum?id=kpLRYtPGt3](https://openreview.net/forum?id=kpLRYtPGt3)

**Authors**: Sina Alemohammad (University of Texas at Austin), Zhangyang Wang (University of Texas at Austin), Richard Baraniuk (William Marsh Rice University)

**Institutions**: University of Texas at Austin, William Marsh Rice University

**Primary Area**: generative models

**Keywords**: Generative Models, Self-Improvement, Weight Merging, Image Generation

**TL;DR**: Instead of simply fine-tuning a generative model on its own synthetic outputs, briefly fine-tune it to find the direction of model collapse, then apply the reverse of that update to the original model for a major performance boost.

**TL;DR翻译**: 不同于简单地在生成模型自身的合成输出上进行微调，而是短暂微调以找到模型崩溃的方向，然后将该更新的反向应用于原始模型，从而实现显著的性能提升。

**Abstract**:

Scaling generative AI models is bottlenecked by the scarcity of high-quality training data. The ease of synthesizing from a generative model suggests using (unverified) synthetic data to augment a limited corpus of real data for the purpose of fine-tuning in the hope of improving performance. Unfortunately, however, the resulting positive feedback loop leads to model autophagy disorder (MAD, aka model collapse) that results in a rapid degradation in sample quality and/or diversity. In this paper, we introduce Neon (for Negative Extrapolation frOm self-traiNing), a new learning method that turns the degradation from self-training into a powerful signal for self-improvement. Given a base model, Neon first fine-tunes it on its own self-synthesized data but then, counterintuitively, reverses its gradient updates to extrapolate away from the degraded weights. We prove that Neon works because typical inference samplers that favor high-probability regions create a predictable anti-alignment between the synthetic and real data population gradients, which negative extrapolation corrects to better align the model with the true data distribution. Neon is remarkably easy to implement via a simple post-hoc merge that requires no new real data, works effectively with as few as 1k synthetic samples, and typically uses less than 1% additional training compute. We demonstrate Neon's universality across a range of architectures (diffusion, flow matching, autoregressive, and inductive moment matching models) and datasets (ImageNet, CIFAR-10, and FFHQ). In particular, on ImageNet 256x256, Neon elevates the xAR-L model to a new state-of-the-art FID of 1.02 with only 0.36% additional training compute.

**摘要翻译**:

生成式AI模型的规模扩展受到高质量训练数据稀缺的瓶颈制约。从生成模型合成数据的便利性促使人们使用（未经验证的）合成数据来增补有限的真实数据语料进行微调，以期提升性能。然而，由此产生的正反馈循环会导致模型自噬失调（MAD，即模型崩溃），造成样本质量和/或多样性的快速退化。本文提出Neon（取自Negative Extrapolation frOm self-traiNing），一种将自训练导致的退化转化为自我改进强力信号的新学习方法。给定一个基础模型，Neon首先在其自身合成的数据上对其进行微调，然后反直觉地反转梯度更新方向，从退化权重外推。我们证明Neon之所以有效，是因为偏好高概率区域的典型推理采样器在合成数据和真实数据总体梯度之间制造了可预测的反向对齐，而负向外推恰好修正了这种偏差，使模型更好地与真实数据分布对齐。Neon通过简单的事后合并即可实现，无需新的真实数据，仅用1000个合成样本即可有效工作，通常仅需不到1%的额外训练计算。我们在多种架构（扩散模型、流匹配、自回归和归纳矩匹配模型）和数据集（ImageNet、CIFAR-10和FFHQ）上展示了Neon的通用性。特别是在ImageNet 256x256上，Neon仅用0.36%的额外训练计算就将xAR-L模型提升至新的最先进FID 1.02。

---

## 15. Compositional Diffusion with Guided search for Long-Horizon Planning

**面向长期规划的组合扩散与引导搜索**

**OpenReview**: [https://openreview.net/forum?id=b8avf4F2hn](https://openreview.net/forum?id=b8avf4F2hn)

**Authors**: Utkarsh Aashu Mishra (Georgia Institute of Technology), David He (Georgia Institute of Technology), Yongxin Chen (NVIDIA), Danfei Xu (Georgia Institute of Technology)

**Institutions**: Georgia Institute of Technology, NVIDIA

**Primary Area**: applications to robotics, autonomy, planning

**Keywords**: Diffusion Models, Compositional Diffusion, Goal-directed Planning

**TL;DR**: We integrate search into compositional diffusion to scale short-horizon models into long-horizon plans, supporting motion planning, panoramic image synthesis, and long-video generation.

**TL;DR翻译**: 我们将搜索集成到组合扩散中，将短期模型扩展为长期规划，支持运动规划、全景图像合成和长视频生成。

**Abstract**:

Generative models have emerged as powerful tools for planning, with compositional approaches offering particular promise for modeling long-horizon task distributions by composing together local, modular generative models. This compositional paradigm spans diverse domains, from multi-step manipulation planning to panoramic image synthesis to long video generation. However, compositional generative models face a critical challenge: when local distributions are multimodal, existing composition methods average incompatible modes, producing plans that are neither locally feasible nor globally coherent. We propose Compositional Diffusion with Guided Search (CDGS), which addresses this mode averaging problem by embedding search directly within the diffusion denoising process. Our method explores diverse combinations of local modes through population-based sampling, prunes infeasible candidates using likelihood-based filtering, and enforces global consistency through iterative resampling between overlapping segments. CDGS matches oracle performance on seven robot manipulation tasks, outperforming baselines that lack compositionality or require long-horizon training data. The approach generalizes across domains, enabling coherent text-guided panoramic images and long videos through effective local-to-global message passing. More details: https://cdgsearch.github.io/

**摘要翻译**:

生成模型已成为规划的强大工具，其中组合方法通过组合局部的、模块化的生成模型来建模长期任务分布，展现出特别的前景。这种组合范式跨越多个领域，从多步操作规划到全景图像合成再到长视频生成。然而，组合生成模型面临一个关键挑战：当局部分布是多模态的时，现有组合方法会平均不兼容的模式，产生既非局部可行也非全局连贯的规划。我们提出带引导搜索的组合扩散（CDGS），通过将搜索直接嵌入扩散去噪过程来解决这一模式平均化问题。我们的方法通过基于种群的采样探索局部模式的多样组合，利用基于似然度的过滤剪除不可行候选，并通过重叠段之间的迭代重采样强制全局一致性。CDGS在七个机器人操作任务上达到了与oracle匹配的性能，优于缺乏组合性或需要长期训练数据的基线方法。该方法具有跨领域的通用性，通过有效的局部到全局消息传递实现连贯的文本引导全景图像和长视频。更多详情：https://cdgsearch.github.io/

---

## 16. Visual symbolic mechanisms: Emergent symbol processing in Vision Language Models

**视觉符号机制：视觉语言模型中涌现的符号处理**

**OpenReview**: [https://openreview.net/forum?id=3RQ863cRbx](https://openreview.net/forum?id=3RQ863cRbx)

**Authors**: Rim Assouel, Declan Iain Campbell (Princeton University), Yoshua Bengio (University of Montreal), Taylor Whittington Webb (Research, Microsoft)

**Institutions**: Princeton University, University of Montreal, Research, Microsoft

**Primary Area**: interpretability and explainable AI

**Keywords**: visual object binding, vision-langue model, symbolic reasoning, interpretability

**TL;DR**: We describe a set of symbolic-like mechanisms that VLMs use to bind to visual entities in context

**TL;DR翻译**: 我们描述了VLMs用于在上下文中绑定视觉实体的一组类符号机制。

**Abstract**:

To accurately process a visual scene, observers must bind features together to represent individual objects. This capacity is necessary, for instance, to distinguish an image containing a red square and a blue circle from an image containing a blue square and a red circle. Recent work has found that language models solve this 'binding problem' via a set of symbol-like, content-independent indices, but it is unclear whether similar mechanisms are employed by Vision Language Models (VLM). This question is especially relevant, given the persistent failures of VLMs on tasks that require binding. Here, we identify a previously unknown set of emergent symbolic mechanisms that support binding specifically in VLMs, via a content-independent, spatial indexing scheme. Moreover, we find that binding errors, when they occur, can be traced directly to failures in these mechanisms. Taken together, these results shed light on the mechanisms that support symbol-like processing in VLMs, and suggest possible avenues for reducing the number of binding failures exhibited by these models.

**摘要翻译**:

为了准确处理视觉场景，观察者必须将特征绑定在一起以表征个体对象。这种能力是必需的，例如用于区分包含红色方块和蓝色圆形的图像与包含蓝色方块和红色圆形的图像。近期研究发现，语言模型通过一组类符号的、与内容无关的索引来解决这一"绑定问题"，但视觉语言模型（VLM）是否采用类似机制尚不清楚。考虑到VLMs在需要绑定的任务上持续存在失败，这一问题尤为重要。本文识别了一组此前未知的涌现符号机制，它们通过与内容无关的空间索引方案专门支持VLMs中的绑定。此外，我们发现绑定错误发生时可以直接追溯到这些机制的失效。综合来看，这些结果揭示了VLMs中支持类符号处理的机制，并为减少这些模型的绑定失败提供了可能的途径。

---

## 17. Addressing divergent representations from causal interventions on neural networks

**解决因果干预在神经网络上产生的分歧表征问题**

**OpenReview**: [https://openreview.net/forum?id=cZrTMqYVL6](https://openreview.net/forum?id=cZrTMqYVL6)

**Authors**: Satchel Grant (Simons Foundation), Simon Jerome Han (Stanford University), Alexa R. Tartaglini (Stanford University), Christopher Potts (Stanford University)

**Institutions**: Simons Foundation, Stanford University

**Primary Area**: interpretability and explainable AI

**Keywords**: activation patching, mech interp, DAS, representational divergence, faithfulness

**TL;DR**: We show empirical representational divergence between native and causally intervened latent states, we show that this can be pernicious and propose a solution.

**TL;DR翻译**: 我们展示了原生潜在状态与因果干预后的潜在状态之间的经验性表征分歧，证明这可能造成有害影响并提出了解决方案。

**Abstract**:

A common approach to mechanistic interpretability is to causally manipulate model representations via targeted interventions in order to understand what those representations encode. Here we ask whether such interventions create out-of-distribution (divergent) representations, and whether this raises concerns about how faithful their resulting explanations are to the target model in its natural state. First, we demonstrate theoretically and empirically that common causal intervention techniques often do shift internal representations away from the natural distribution of the target model. Then, we provide a theoretical analysis of two cases of such divergences: "harmless" divergences that occur in the behavioral null-space of the layer(s) of interest, and "pernicious" divergences that activate hidden network pathways and cause dormant behavioral changes. Finally, in an effort to mitigate the pernicious cases, we apply and modify the Counterfactual Latent (CL) loss from Grant (2025) allowing representations from causal interventions to remain closer to the natural distribution, reducing the likelihood of harmful divergences while preserving the interpretive power of the interventions. Together, these results highlight a path towards more reliable interpretability methods.

**摘要翻译**:

机制可解释性的一种常见方法是通过有针对性的干预对模型表征进行因果操控，以理解这些表征编码了什么。本文探讨此类干预是否会产生分布外（分歧）表征，以及这是否对其解释对目标模型自然状态的忠实性构成担忧。首先，我们从理论和实证上证明，常见的因果干预技术确实经常将内部表征偏离目标模型的自然分布。然后，我们对两类此种分歧进行了理论分析："无害的"分歧发生在相关层的行为零空间中，而"有害的"分歧则会激活隐藏的网络通路并引起潜伏的行为变化。最后，为缓解有害情况，我们应用并改进了Grant (2025)提出的反事实潜在（CL）损失，使因果干预产生的表征能够更贴近自然分布，降低有害分歧的可能性同时保留干预的可解释能力。综合来看，这些结果指出了通往更可靠的可解释性方法的路径。

---

## 18. Cross-Domain Lossy Compression via Rate- and Classification-Constrained Optimal Transport

**基于速率与分类约束最优传输的跨域有损压缩**

**OpenReview**: [https://openreview.net/forum?id=mUIGdUTtk2](https://openreview.net/forum?id=mUIGdUTtk2)

**Authors**: Nam Nguyen (Oregon State University), Thinh Nguyen (Oregon State University), Bella Bose (Oregon State University)

**Institutions**: Oregon State University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Lossy Compression, Image Compression, Image Restoration, Image Inpainting, Optimal Transport, Multi-task Learning, Rate-Distortion-Perception Tradeoff, Rate-Distortion-Classification Tradeoff, Deep Learning, Unsupervised Learning

**TL;DR**: We study cross-domain lossy compression via constrained optimal transport with rate and classification constraints, derive closed-form tradeoffs, extend to perception divergences, and validate with deep restoration and inpainting experiments.

**TL;DR翻译**: 我们通过带有速率和分类约束的约束最优传输研究跨域有损压缩，推导了闭式权衡关系，扩展到感知散度，并通过深度修复和图像修补实验进行了验证。

**Abstract**:

We study cross-domain lossy compression, where the encoder observes a degraded source while the decoder reconstructs samples from a distinct target distribution. The problem is formulated as constrained optimal transport with two constraints on compression rate and classification loss. With shared common randomness, the one-shot setting reduces to a deterministic transport plan, and we derive closed-form distortion-rate-classification (DRC) and rate-distortion-classification (RDC) tradeoffs for Bernoulli sources under Hamming distortion. In the asymptotic regime, we establish analytic DRC/RDC expressions for Gaussian models under mean-squared error. The framework is further extended to incorporate perception divergences (Kullback-Leibler and squared Wasserstein), yielding closed-form distortion-rate-perception-classification (DRPC) functions. To validate the theory, we develop deep end-to-end compression models for super-resolution (MNIST), denoising (SVHN, CIFAR-10, ImageNet, KODAK), and inpainting (SVHN) problems, demonstrating the consistency between the theoretical results and empirical performance.

**摘要翻译**:

我们研究跨域有损压缩问题，其中编码器观测退化的源信号，而解码器从不同的目标分布中重建样本。该问题被形式化为带有压缩速率和分类损失两个约束的约束最优传输。在共享公共随机性的条件下，单次设定简化为确定性传输方案，我们推导了伯努利源在汉明失真下的闭式失真-速率-分类（DRC）和速率-失真-分类（RDC）权衡。在渐近情形下，我们建立了高斯模型在均方误差下的解析DRC/RDC表达式。该框架进一步扩展以纳入感知散度（Kullback-Leibler和平方Wasserstein），得到闭式失真-速率-感知-分类（DRPC）函数。为验证理论，我们开发了用于超分辨率（MNIST）、去噪（SVHN、CIFAR-10、ImageNet、KODAK）和图像修补（SVHN）问题的深度端到端压缩模型，证明了理论结果与实证性能的一致性。

---

## 19. Latent Fourier Transform

**潜空间傅里叶变换**

**OpenReview**: [https://openreview.net/forum?id=ogMxCjdCCq](https://openreview.net/forum?id=ogMxCjdCCq)

**Authors**: Mason Long Wang (Massachusetts Institute of Technology), Cheng-Zhi Anna Huang (Massachusetts Institute of Technology)

**Institutions**: Massachusetts Institute of Technology

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Music Generation, Signal Processing, Diffusion Models, Audio, Music, Audio Generation, Controllable Generation, Fourier Transform, Diffusion Autoencoders

**TL;DR**: We introduce novel frequency-domain controls for generative music models by applying the Fourier transform to the latent space of a diffusion autoencoder.

**TL;DR翻译**: 我们通过在扩散自编码器的潜空间上应用傅里叶变换，为生成式音乐模型引入了新颖的频域控制能力。

**Abstract**:

We introduce the Latent Fourier Transform (LatentFT), a framework that provides novel frequency-domain controls for generative music models. LatentFT combines a diffusion autoencoder with a latent-space Fourier transform to separate musical patterns by timescale. By masking latents in the frequency domain during training, our method yields representations that can be manipulated coherently at inference. This allows us to generate musical variations and blends from reference examples while preserving characteristics at desired timescales, which are specified as frequencies in the latent space. LatentFT parallels the role of the equalizer in music production: while traditional equalizers operates on audible frequencies to shape timbre, LatentFT operates on latent-space frequencies to shape musical structure. Experiments and listening tests show that LatentFT improves condition adherence and quality compared to baselines. We also present a technique for hearing frequencies in the latent space in isolation, and show different musical attributes reside in different regions of the latent spectrum. Our results show how frequency-domain control in latent space provides an intuitive, continuous frequency axis for conditioning and blending, advancing us toward more interpretable and interactive generative music models.

**摘要翻译**:

我们介绍了潜空间傅里叶变换（LatentFT），一个为生成式音乐模型提供新颖频域控制的框架。LatentFT将扩散自编码器与潜空间傅里叶变换相结合，按时间尺度分离音乐模式。通过在训练时对频域中的潜在表示进行掩码，我们的方法产生了可在推理时进行连贯操控的表征。这使我们能够从参考样本生成音乐变奏和混合，同时保留在期望时间尺度上的特征，这些时间尺度在潜空间中被指定为频率。LatentFT类似于音乐制作中均衡器的角色：传统均衡器操作可听频率以塑造音色，而LatentFT操作潜空间频率以塑造音乐结构。实验和听力测试表明，LatentFT在条件遵循度和质量方面优于基线方法。我们还提出了一种单独聆听潜空间频率的技术，并展示了不同的音乐属性存在于潜在频谱的不同区域。我们的结果表明，潜空间中的频域控制提供了直观、连续的频率轴用于条件控制和混合，推动了更具可解释性和交互性的生成式音乐模型的发展。

---

## 20. GLASS Flows: Efficient Inference for Reward Alignment of Flow and Diffusion Models

**GLASS Flows：面向流模型与扩散模型奖励对齐的高效推理**

**OpenReview**: [https://openreview.net/forum?id=vH7OAPZ2dR](https://openreview.net/forum?id=vH7OAPZ2dR)

**Authors**: Peter Holderrieth (MIT), Uriel Singer (Meta AI Research), Tommi Jaakkola, Ricky T. Q. Chen (FAIR Labs, Meta AI), Yaron Lipman, Brian Karrer (Meta Fundamental AI Research (FAIR))

**Institutions**: MIT, Meta AI Research, FAIR Labs, Meta AI, Meta Fundamental AI Research (FAIR)

**Primary Area**: generative models

**Keywords**: Flow Matching; Diffusion Models; Reward Alignment; Reward Adaptation; Inference-time scaling; Feynman-Kac Steering; Markov transitions; Sampling methods

**TL;DR**: We improve inference-time reward alignment of flow matching and diffusion models by proposing a novel sampling paradigm that enables more efficient exploration.

**TL;DR翻译**: 我们通过提出一种实现更高效探索的新采样范式，改进了流匹配和扩散模型在推理时的奖励对齐。

**Abstract**:

The performance of flow matching and diffusion models can be greatly improved at inference time using reward adaptation algorithms, yet efficiency remains a major limitation. While several algorithms were proposed, we demonstrate that a common bottleneck is the *sampling* method these algorithms rely on: many algorithms require to sample Markov transitions via SDE sampling, which is significantly less efficient and often less performant than ODE sampling. To remove this bottleneck, we introduce GLASS Flows, a new sampling paradigm that simulates a ''flow matching model within a flow matching model'' to sample Markov transitions. As we show in this work, this ''inner'' flow matching model can be retrieved from any pre-trained model without any re-training, effectively combining the efficiency of ODEs with the stochastic evolution of SDEs. On large-scale text-to-image models, we show that GLASS Flows eliminate the trade-off between stochastic evolution and efficiency. GLASS Flows improve state-of-the-art performance in text-to-image generation, making it a simple, drop-in solution for inference-time scaling of flow and diffusion models.

**摘要翻译**:

流匹配和扩散模型的性能可以通过奖励适应算法在推理时大幅提升，但效率仍然是主要限制。虽然已有多种算法被提出，我们证明了一个共同的瓶颈在于这些算法所依赖的*采样*方法：许多算法需要通过SDE采样来采样马尔可夫转移，这比ODE采样效率显著更低且性能往往更差。为消除这一瓶颈，我们引入GLASS Flows，一种新的采样范式，通过模拟"流匹配模型中的流匹配模型"来采样马尔可夫转移。如本文所示，这个"内层"流匹配模型可以从任何预训练模型中提取而无需重新训练，有效地将ODE的效率与SDE的随机演化结合起来。在大规模文本到图像模型上，我们展示了GLASS Flows消除了随机演化与效率之间的权衡。GLASS Flows改进了文本到图像生成的最先进性能，使其成为流模型和扩散模型推理时扩展的简单即插即用方案。

---

## 21. Latent Speech-Text Transformer

**潜在语音-文本Transformer**

**OpenReview**: [https://openreview.net/forum?id=krGpQzo8Mz](https://openreview.net/forum?id=krGpQzo8Mz)

**Authors**: Yen-Ju Lu (Johns Hopkins University), Yashesh Gaur (Microsoft), Wei Zhou (Google), Benjamin Muller (Meta), Jesus Villalba (Johns Hopkins University), Najim Dehak (Johns Hopkins University), Luke Zettlemoyer (University of Washington), Gargi Ghosh (Meta AI), Mike Lewis (Facebook AI Research), Srini Iyer (Facebook), Duc Le (Facebook)

**Institutions**: Johns Hopkins University, Microsoft, Google, Meta, University of Washington, Meta AI, Facebook AI Research, Facebook

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Speech–Text Models, Latent Patching, Multimodal Alignment, Large Language Models

**TL;DR**: We introduce Latent Speech-Text Transformer which patches long speech token sequences into latent units, improving text–speech transfer while cutting pre-training and inference compute, and significantly outperforming existing speech-text LLMs.

**TL;DR翻译**: 我们介绍了Latent Speech-Text Transformer，将长语音token序列聚合为潜在单元，在降低预训练和推理计算量的同时改善文本-语音迁移，并显著优于现有的语音-文本LLMs。

**Abstract**:

Auto-regressive speech-text models are typically pre-trained on a large number of interleaved sequences of text tokens and raw speech encoded as speech tokens using vector quantization. These models have demonstrated state-of-the-art performance in speech-to-speech understanding and generation benchmarks, together with promising scaling laws, primarily enabled by the representational alignment between text and speech. Nevertheless, they suffer from shortcomings, partly owing to the disproportionately longer sequences of speech tokens in contrast to textual tokens. This results in a large compute imbalance between modalities during pre-training as well as during inference, and a potential hindrance to effectively aligning speech and text, ultimately translating to several orders of magnitude slower scaling laws. We introduce the Latent Speech-Text Transformer (LST), which makes pre-training speech-text models more data-efficient by dynamically and inexpensively aggregating speech tokens into latent speech patches. These patches serve as higher-level units that can either align with corresponding textual units to aid capability transfer or even encapsulate common speech sequences like silences to be more compute-efficient. We show that LST outperforms vanilla approaches on speech-to-speech as well as text-to-text benchmarks in both data- and compute-controlled settings, the former indicating more effective representational alignment and the latter indicating steeper scaling laws for speech-text models. On HellaSwag story completion, LST achieves 6.5% absolute gain in speech accuracy under compute-controlled training and 5.3% under data-controlled training, while also improving text performance. We will release our models, code, and the evaluation data to facilitate further research.

**摘要翻译**:

自回归语音-文本模型通常在大量交错的文本token序列和通过向量量化编码为语音token的原始语音序列上进行预训练。这些模型在语音到语音的理解和生成基准测试中展示了最先进的性能以及有前景的缩放规律，这主要得益于文本与语音之间的表征对齐。然而，它们存在不足，部分原因在于语音token序列相对于文本token不成比例地过长。这导致预训练和推理过程中模态间的计算严重失衡，并可能阻碍语音与文本的有效对齐，最终使得缩放规律慢了几个数量级。我们引入潜在语音-文本Transformer（LST），通过动态且低成本地将语音token聚合为潜在语音片段（patches），使语音-文本模型的预训练更加数据高效。这些片段作为更高层次的单元，既可以与对应的文本单元对齐以促进能力迁移，也可以将静音等常见语音序列进行封装以提高计算效率。我们展示了LST在数据控制和计算控制两种设置下，在语音到语音和文本到文本基准上均优于普通方法，前者表明了更有效的表征对齐，后者表明了语音-文本模型更陡峭的缩放规律。在HellaSwag故事续写任务上，LST在计算控制训练下实现了6.5%的语音准确率绝对提升，在数据控制训练下实现了5.3%的提升，同时还改善了文本性能。我们将发布模型、代码和评估数据以促进进一步研究。

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

---

## 23. Speculative Actions: A Lossless Framework for Faster AI Agents

**推测性动作：加速AI智能体的无损框架**

**OpenReview**: [https://openreview.net/forum?id=P0GOk5wslg](https://openreview.net/forum?id=P0GOk5wslg)

**Authors**: Naimeng Ye (Columbia University), Arnav Ahuja (Columbia University), Georgios Liargkovas (Columbia University), Yunan Lu (Columbia University), Kostis Kaffes (Columbia University), Tianyi Peng (Columbia University)

**Institutions**: Columbia University

**Primary Area**: infrastructure, software libraries, hardware, systems, etc.

**Keywords**: AI Agents, Speculative Decoding, Parallel Execution, Agentic Serving, Agentic Simulation

**TL;DR**: We introduce speculative actions—a lossless framework that predicts likely actions using faster models, enabling multiple API calls to be executed in parallel and thus yields substantial acceleration.

**TL;DR翻译**: 我们提出推测性动作——一种无损框架，利用更快的模型预测可能的动作，使多个API调用能够并行执行，从而实现显著加速。

**Abstract**:

Despite growing interest in AI agents across industry and academia, their execution in an environment is often slow, hampering training, evaluation, and deployment. For example, a game of chess between two state-of-the-art agents may take hours. A critical bottleneck is that agent behavior unfolds sequentially: each action requires an API call, and these calls can be time-consuming. Inspired by speculative execution in microprocessors and speculative decoding in LLM inference, we propose speculative actions, a lossless framework for general agentic systems that predicts likely actions using faster models, enabling multiple steps to be executed in parallel. We evaluate this framework across three agentic environments: gaming, e-commerce, web search, and a "lossy" extension for an operating systems environment. In all cases, speculative actions achieve substantial accuracy in next-action prediction (up to 55%), translating into significant reductions in end-to-end latency. Finally, we develop a cost-latency analysis that formalizes the tradeoff between launching additional speculative actions and the resulting time savings. This analysis enables principled tuning of speculative breadth and selective branch launching, ensuring that speculation remains practically deployable.

**摘要翻译**:

尽管业界和学术界对AI智能体的兴趣日益增长，但其在环境中的执行往往较慢，制约了训练、评估和部署。例如，两个最先进的智能体之间的一盘国际象棋可能需要数小时。一个关键瓶颈在于智能体行为是顺序展开的：每个动作需要一次API调用，而这些调用可能非常耗时。受微处理器中推测执行和LLM推理中推测解码的启发，我们提出推测性动作，一种面向通用智能体系统的无损框架，利用更快的模型预测可能的动作，使多个步骤能够并行执行。我们在三个智能体环境中评估了该框架：游戏、电子商务、网络搜索，以及一个针对操作系统环境的"有损"扩展。在所有情况下，推测性动作在下一动作预测中达到了很高的准确率（高达55%），转化为端到端延迟的显著降低。最后，我们开发了成本-延迟分析，形式化了发起额外推测性动作与由此节省的时间之间的权衡。该分析实现了推测宽度和选择性分支启动的原则性调优，确保推测在实际中可部署。

---

## 24. Gaussian certified unlearning in high dimensions: A hypothesis testing approach

**高维空间中的高斯认证遗忘：假设检验方法**

**OpenReview**: [https://openreview.net/forum?id=0FJYicpOj0](https://openreview.net/forum?id=0FJYicpOj0)

**Authors**: Aaradhya Pandey (Princeton University), Arnab Auddy (Ohio State University, Columbus), Haolin Zou (Columbia University), Arian Maleki (Columbia University), Sanjeev Kulkarni (Princeton University)

**Institutions**: Princeton University, Ohio State University, Columbus, Columbia University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Machine unlearning in high dimensions, Proportional asymptotics, High dimensional statistical theory, Privacy–accuracy tradeoff, Hypothesis testing, Gaussian noise calibration, Newton method

**TL;DR**: We introduce the canonical dimension free notion of certifiability suitable to high dimensions and show its utility via a Newton based unlearning algorithm

**TL;DR翻译**: 我们引入了适用于高维空间的经典无维度可认证性概念，并通过基于Newton的遗忘算法展示了其实用性。

**Abstract**:

Machine unlearning seeks to efficiently remove the influence of selected data while preserving generalization. Significant progress has been made in low dimensions, where the dimension of the parameter $p$ is much smaller than the sample size $n$, but high dimensions, including proportional regimes $p \sim n$, pose serious theoretical challenges as standard optimization assumptions of $\Omega(1)$ strong convexity and $O(1)$ smoothness of the per-example loss $f$ rarely hold simultaneously in proportional regimes $p\sim n$. In this work, we introduce $\varepsilon$-Gaussian certifiability, a canonical and robust notion well-suited to high-dimensional regimes, that optimally captures a broad class of noise adding mechanisms. Then we theoretically analyze the performance of a widely used unlearning algorithm based on one step of the Newton method in the high-dimensional setting described above. Our analysis shows that a single Newton step, followed by a well-calibrated Gaussian noise, is sufficient to achieve both privacy and accuracy in this setting. This result stands in sharp contrast to the only prior work that analyzes machine unlearning in high dimensions, which relaxes some of the standard optimization assumptions for high-dimensional applicability, but operates under the notion of $\varepsilon$-certifiability. That work concludes that at least two steps are required to ensure both privacy and accuracy. Our result leads us to conclude that the discrepancy in the number of steps arises because of the sub optimality of the notion of $\varepsilon$-certifiability and its incompatibility with noise adding mechanisms, which $\varepsilon$-Gaussian certifiability is able to overcome optimally.

**摘要翻译**:

机器遗忘旨在高效移除选定数据的影响同时保持泛化能力。在低维情形（参数维度$p$远小于样本量$n$）中已取得显著进展，但高维情形（包括比例区间$p \sim n$）带来了严峻的理论挑战，因为每样本损失$f$的$\Omega(1)$强凸性和$O(1)$光滑性等标准优化假设在比例区间$p\sim n$中很难同时成立。本文引入了$\varepsilon$-高斯可认证性，一种适用于高维区间的经典且稳健的概念，能最优地刻画广泛的噪声添加机制。随后，我们在上述高维设定下理论分析了一种广泛使用的基于一步Newton方法的遗忘算法的性能。分析表明，一步Newton迭代加上精心校准的高斯噪声，足以在该设定下同时实现隐私和准确性。这一结果与此前唯一分析高维机器遗忘的工作形成鲜明对比，后者虽然放松了部分标准优化假设以适用于高维，但在$\varepsilon$-可认证性概念下运作，得出至少需要两步才能同时确保隐私和准确性的结论。我们的结果使我们得出结论：步数差异源于$\varepsilon$-可认证性概念的次优性及其与噪声添加机制的不兼容性，而$\varepsilon$-高斯可认证性能够最优地克服这些问题。

---

## 25. RedTeamCUA: Realistic Adversarial Testing of Computer-Use Agents in Hybrid Web-OS Environments

**RedTeamCUA：混合Web-OS环境中计算机使用智能体的真实对抗性测试**

**OpenReview**: [https://openreview.net/forum?id=yWwrgcBoK3](https://openreview.net/forum?id=yWwrgcBoK3)

**Authors**: Zeyi Liao (Ohio State University, Columbus), Jaylen Jones (Ohio State University, Columbus), Linxi Jiang (Ohio State University, Columbus), Yuting Ning (Ohio State University, Columbus), Eric Fosler-Lussier (Ohio State University), Yu Su (Ohio State University), Zhiqiang Lin (Ohio State University, Columbus), Huan Sun (The Ohio State University, Columbus)

**Institutions**: Ohio State University, Columbus, Ohio State University, The Ohio State University, Columbus

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Computer-Use Agents, Adversarial Risks, Sandbox, Benchmark

**TL;DR**: We provide a realistic, controlled and hybrid sandbox for systematic adversarial testings against computer-use agents.

**TL;DR翻译**: 我们提供了一个真实、可控的混合沙盒环境，用于对计算机使用智能体进行系统性对抗测试。

**Abstract**:

Computer-use agents (CUAs) promise to automate complex tasks across operating systems (OS) and the web, but remain vulnerable to indirect prompt injection, where attackers embed malicious content into the environment to hijack agent behavior. Current evaluations of this threat either lack support for adversarial testing in realistic but controlled environments or ignore hybrid web-OS attack scenarios involving both interfaces. To address this, we propose RedTeamCUA, an adversarial testing framework featuring a novel hybrid sandbox that integrates a VM-based OS environment with Docker-based web platforms. Our sandbox supports key features tailored for red teaming, such as flexible adversarial scenario configuration, and a setting that decouples adversarial evaluation from navigational limitations of CUAs by initializing tests directly at the point of an adversarial injection. Using RedTeamCUA, we develop RTC-Bench, a comprehensive benchmark with 864 examples that investigate realistic, hybrid web-OS attack scenarios and fundamental security vulnerabilities. Benchmarking current frontier CUAs identifies significant vulnerabilities: Claude 3.7 Sonnet | CUA demonstrates an Attack Success Rate (ASR) of 42.9%, while Operator, the most secure CUA evaluated, still exhibits an ASR of 7.6%. Notably, CUAs often attempt to execute adversarial tasks with an Attempt Rate as high as 92.5%, although failing to complete them due to capability limitations. Nevertheless, we observe concerning ASRs of up to 50% in realistic end-to-end settings, indicating that CUA threats can already result in tangible risks to users and computer systems. Overall, RedTeamCUA provides an essential framework for advancing realistic, controlled, and systematic analysis of CUA vulnerabilities, highlighting the urgent need for robust defenses to indirect prompt injection prior to real-world deployment.

**摘要翻译**:

计算机使用智能体（CUAs）旨在跨操作系统（OS）和Web自动化复杂任务，但仍然容易受到间接提示注入攻击——攻击者将恶意内容嵌入环境以劫持智能体行为。当前对该威胁的评估要么缺乏在真实但可控环境中的对抗测试支持，要么忽视了涉及双重界面的混合Web-OS攻击场景。为此，我们提出RedTeamCUA，一个对抗测试框架，其特色在于一个新颖的混合沙盒，将基于虚拟机的OS环境与基于Docker的Web平台相集成。该沙盒支持为红队测试量身定制的关键功能，如灵活的对抗场景配置，以及通过在对抗注入点直接初始化测试来将对抗评估与CUAs的导航限制解耦的设置。利用RedTeamCUA，我们开发了RTC-Bench，一个包含864个示例的综合基准，用于研究真实的混合Web-OS攻击场景和基本安全漏洞。对当前前沿CUAs的基准测试识别出重大漏洞：Claude 3.7 Sonnet | CUA的攻击成功率（ASR）为42.9%，而被评估为最安全的CUA Operator仍然展示了7.6%的ASR。值得注意的是，CUAs经常尝试执行对抗任务，尝试率高达92.5%，尽管由于能力限制而未能完成。然而，我们在真实的端到端设置中观察到高达50%的令人担忧的ASR，表明CUA威胁已经能够对用户和计算机系统造成实质性风险。总体而言，RedTeamCUA为推进CUA漏洞的真实、可控和系统性分析提供了必要框架，突显了在实际部署前亟需针对间接提示注入的强健防御。

---

## 26. Exploratory Causal Inference in SAEnce

**SAEnce中的探索性因果推断**

**OpenReview**: [https://openreview.net/forum?id=Ml8t8kQMUP](https://openreview.net/forum?id=Ml8t8kQMUP)

**Authors**: Tommaso Mencattini (EPFL - EPF Lausanne), Riccardo Cadei (Institute of Science and Technology), Francesco Locatello (Institute of Science and Technology)

**Institutions**: EPFL - EPF Lausanne, Institute of Science and Technology

**Primary Area**: interpretability and explainable AI

**Keywords**: Randomized Controlled Trials, Sparse Auto Encoder, Interpretability, Causal Inference

**TL;DR**: New method to uncover causal treatment effects directly from trial data using foundation models, SAE and recursive stratification, without any prior and supervision.

**TL;DR翻译**: 一种利用基础模型、SAE和递归分层直接从试验数据中发现因果处理效应的新方法，无需任何先验知识和监督。

**Abstract**:

Randomized Controlled Trials are one of the pillars of science; nevertheless, they rely on hand-crafted hypotheses and expensive analysis. Such constraints prevent causal effect estimation at scale, potentially anchoring on popular yet incomplete hypotheses. We propose to discover the unknown effects of a treatment directly from data. For this, we turn unstructured data from a trial into meaningful representations via pretrained foundation models and interpret them via a Sparse Auto Encoder. However, discovering significant causal effects at the neural level is not trivial due to multiple-testing issues and effects entanglement. To address these challenges, we introduce Neural Effect Search, a novel recursive procedure solving both issues by progressive stratification. After assessing the robustness of our algorithm on semi-synthetic experiments, we showcase, in the context of experimental ecology, the first successful unsupervised causal effect identification on a real-world scientific trial.

**摘要翻译**:

随机对照试验是科学的基石之一；然而，它们依赖于人工设计的假设和昂贵的分析。这些约束阻碍了大规模的因果效应估计，可能使研究锚定于流行但不完整的假设。我们提出直接从数据中发现处理的未知效应。为此，我们通过预训练基础模型将试验中的非结构化数据转化为有意义的表征，并通过稀疏自编码器对其进行解释。然而，由于多重检验问题和效应纠缠，在神经层面发现显著的因果效应并非易事。为应对这些挑战，我们引入了神经效应搜索，一种通过渐进分层同时解决两个问题的新颖递归程序。在半合成实验上验证了算法的稳健性后，我们在实验生态学场景中展示了首次在真实科学试验上成功进行的无监督因果效应识别。

---

## 27. Every Language Model Has a Forgery-Resistant Signature

**每个语言模型都具有防伪签名**

**OpenReview**: [https://openreview.net/forum?id=vLFqOoMBol](https://openreview.net/forum?id=vLFqOoMBol)

**Authors**: Matthew Finlayson (University of Southern California), Xiang Ren (University of Southern California), Swabha Swayamdipta (University of Southern California)

**Institutions**: University of Southern California

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: fingerprint, watermark, language model, signature, accountability, cryptography, forgery, security

**TL;DR**: We show that all language models impose elliptical constraints on their outputs, which can be used as a hard-to-fake signature to identify a model from its outputs.

**TL;DR翻译**: 我们证明所有语言模型都对其输出施加椭圆约束，这可作为难以伪造的签名来从输出中识别模型。

**Abstract**:

The ubiquity of closed-weight language models with public-facing APIs has generated interest in forensic methods, both for extracting hidden model details (e.g., parameters) and identifying models by their outputs. One successful approach to these goals has been to exploit the geometric constraints imposed by the language model architecture and parameters. In this work, we show that a lesser-known geometric constraint—namely that language model outputs lie on the surface of a high-dimensional ellipse—functions as a signature for the model, which be used to identify which model an output came from. This ellipse signature has unique properties that distinguish it from existing model-output association methods like language model watermarks. In particular, the signature is hard to forge: without direct access to model parameters, it is practically infeasible to produce logprobs on the ellipse. Secondly, the signature is naturally occurring, since all language models have these elliptical constraints. Thirdly, the signature is self-contained, in that it is detectable without access to the model input or full weights. Finally, the signature is exceptionally redundant, as it is independently detectable in every single logprob output from the model. We evaluate a novel technique for extracting the ellipse on small models, and discuss the practical hurdles that make it infeasible for production-size models, making the signature hard to forge. Finally, we use ellipse signatures to propose a protocol for language model output verification, which is analogous to cryptographic symmetric-key message authentication systems.

**摘要翻译**:

具有公开API的闭源语言模型的普及引发了人们对取证方法的兴趣，包括提取隐藏的模型细节（如参数）和通过输出识别模型。实现这些目标的一种成功方法是利用语言模型架构和参数施加的几何约束。本文中，我们展示了一种鲜为人知的几何约束——即语言模型输出位于高维椭圆表面——可以作为模型的签名，用于识别输出来自哪个模型。这种椭圆签名具有独特的属性，使其区别于语言模型水印等现有模型-输出关联方法。首先，该签名难以伪造：在无法直接访问模型参数的情况下，生成处于椭圆上的对数概率在实践中是不可行的。其次，该签名是自然产生的，因为所有语言模型都具有这种椭圆约束。第三，该签名是自包含的，无需访问模型输入或完整权重即可检测。最后，该签名具有极高的冗余性，因为它可以在模型的每一个对数概率输出中独立检测。我们评估了一种在小型模型上提取椭圆的新技术，并讨论了使其在生产规模模型上不可行的实际障碍，这使得签名难以伪造。最后，我们利用椭圆签名提出了一种语言模型输出验证协议，类似于密码学中的对称密钥消息认证系统。

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

**Abstract**:

Since compute grows much faster than web text available for language model pre-training, we ask how one should approach pre-training under fixed data and no compute constraints. We first show that existing data-constrained approaches of increasing epoch count and parameter count overfit, and we improve upon such recipes by tuning regularization, finding that the optimal weight decay is $30\times$ larger than standard practice. Since our regularized recipe monotonically decreases loss following a power law in parameter count, we estimate its best possible performance via the asymptote of its scaling law rather than the performance at a fixed compute budget. We then identify that ensembling independently trained models achieves a significantly lower loss asymptote than the regularized recipe. Our best intervention combining epoching, regularization, parameter scaling, and ensemble scaling achieves an asymptote at 200M tokens using $5.17\times$ less data than our baseline, and our data scaling laws predict that this improvement persists at higher token budgets. We find that our data efficiency gains can be realized at smaller parameter counts as we can distill an ensemble into a student model that is 8$\times$ smaller and retains $83$% of the ensembling benefit. Finally, our interventions designed for validation loss generalize to downstream benchmarks, achieving a $9$% improvement for pre-training evals. Our results show that simple algorithmic improvements can enable significantly more data-efficient pre-training in a compute-rich future.

**摘要翻译**:

由于计算能力的增长远快于可用于语言模型预训练的网络文本，我们探讨了在固定数据量且无计算约束条件下应如何进行预训练。我们首先表明，现有的数据受限方法——增加训练轮次和参数量——会导致过拟合，我们通过调整正则化改进了这些方案，发现最优权重衰减比标准实践大$30$倍。由于我们的正则化方案随参数量按幂律单调降低损失，我们通过其缩放定律的渐近值而非固定计算预算下的性能来估计其最佳可能性能。随后我们发现，对独立训练的模型进行集成能够达到比正则化方案显著更低的损失渐近值。我们结合多轮训练、正则化、参数规模扩展和集成规模扩展的最佳干预方案在2亿token上实现了渐近值，所用数据比基线少$5.17$倍，且我们的数据缩放定律预测该改进在更高token预算下仍然成立。我们发现数据效率增益可在更小的参数量下实现，因为我们可以将集成蒸馏为小8倍的学生模型，同时保留83%的集成收益。最后，我们为验证损失设计的干预措施可泛化到下游基准，在预训练评估中实现了9%的改进。我们的结果表明，简单的算法改进能够在计算资源充裕的未来实现显著更高的数据效率预训练。

---

## 29. GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning

**GEPA：反思式提示进化可超越强化学习**

**OpenReview**: [https://openreview.net/forum?id=RQm2KQTM5r](https://openreview.net/forum?id=RQm2KQTM5r)

**Authors**: Lakshya A Agrawal (University of California, Berkeley), Shangyin Tan (University of California, Berkeley), Dilara Soylu (Stanford University), Noah Ziems (University of Notre Dame), Rishi Khare (Georgia Institute of Technology), Krista Opsahl-Ong (Stanford University), Arnav Singhvi (Computer Science Department, Stanford University), Herumb Shandilya (Stanford University), Michael J Ryan (Stanford University), Meng Jiang (University of Notre Dame), Christopher Potts (Stanford University), Koushik Sen (UC Berkeley, University of California, Berkeley), Alex Dimakis (Electrical Engineering & Computer Science Department, University of California, Berkeley), Ion Stoica (University of California, Berkeley), Dan Klein (University of California, Berkeley), Matei Zaharia (University of California, Berkeley), Omar Khattab (Massachusetts Institute of Technology)

**Institutions**: University of California, Berkeley, Stanford University, University of Notre Dame, Georgia Institute of Technology, Computer Science Department, Stanford University, UC Berkeley, University of California, Berkeley, Electrical Engineering & Computer Science Department, University of California, Berkeley, Massachusetts Institute of Technology

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: prompt optimization, natural language, reflection, large language models, agent design, agent discovery, code optimization, compound AI systems, genetic, language based learning, evolutionary algorithms

**TL;DR**: GEPA uses natural language reflection to optimize prompts, outperforming GRPO and MIPROv2 while needing far fewer rollouts.

**TL;DR翻译**: GEPA 利用自然语言反思来优化提示，在性能上超越 GRPO 和 MIPROv2，同时所需的采样回合数大幅减少。

**Abstract**:

Large language models (LLMs) are increasingly adapted to downstream tasks via reinforcement learning (RL) methods like Group Relative Policy Optimization (GRPO), which often require thousands of rollouts to learn new tasks. We argue that the interpretable nature of language often provides a much richer learning medium for LLMs, compared to policy gradients derived from sparse, scalar rewards. To test this, we introduce GEPA (Genetic-Pareto), a prompt optimizer that thoroughly incorporates natural language reflection to learn high-level rules from trial and error.
    Given any AI system containing one or more LLM prompts, GEPA samples trajectories (e.g., reasoning, tool calls, and tool outputs) and reflects on them in natural language to diagnose problems, propose and test prompt updates, and combine complementary lessons from the Pareto frontier of its own attempts. As a result of GEPA's design, it can often turn even just a few rollouts into a large quality gain.
    Across four tasks, GEPA outperforms GRPO by 6% on average and by up to 20%, while using up to 35x fewer rollouts. GEPA also outperforms the leading prompt optimizer, MIPROv2, by over 10% (e.g., +10% accuracy on AIME-2025).

**摘要翻译**:

大语言模型（LLM）越来越多地通过强化学习（RL）方法（如 Group Relative Policy Optimization，GRPO）适配下游任务，但这些方法往往需要数千次采样回合才能学会新任务。我们认为，相比于由稀疏标量奖励推导出的策略梯度，语言的可解释性为大语言模型提供了更为丰富的学习媒介。为验证这一观点，我们提出了 GEPA（Genetic-Pareto），一种深度融合自然语言反思机制的提示优化器，能够从试错过程中学习高层规则。

给定包含一个或多个 LLM 提示的任意 AI 系统，GEPA 采样轨迹（例如推理过程、工具调用和工具输出），并以自然语言对其进行反思，以诊断问题、提出并测试提示更新方案，以及整合来自其自身尝试 Pareto 前沿的互补经验。得益于 GEPA 的设计，即便仅有少量采样回合，它也往往能带来显著的质量提升。

在四项任务上，GEPA 平均超越 GRPO 6%，最高可达 20%，同时采样回合数最多减少 35 倍。GEPA 还以超过 10% 的优势超越了领先的提示优化器 MIPROv2（例如在 AIME-2025 上准确率提升 10%）。

---

## 30. $p\textrm{-less}$ Sampling: A Robust Hyperparameter-Free Approach for LLM Decoding

**$p\textrm{-less}$ Sampling：一种鲁棒的无超参数 LLM 解码方法**

**OpenReview**: [https://openreview.net/forum?id=ItFuNJQGH4](https://openreview.net/forum?id=ItFuNJQGH4)

**Authors**: Runyan Tan (AI Labs, Thoughtworks), Shuang Wu (Thoughtworks), Phillip Howard (Thoughtworks)

**Institutions**: AI Labs, Thoughtworks, Thoughtworks

**Primary Area**: probabilistic methods (Bayesian methods, variational inference, sampling, UQ, etc.)

**Keywords**: LLM, decoding, sampling, truncation, inference, information-theoretic, information-theory, hyperparameterless, hyperparameter-free, entropy, entropy-aware, distribution-aware, adaptive, efficient, generation

**TL;DR**: P-less Sampling: A parameterless sampling strategy grounded in information theory, where the truncation threshold adapts to the entire token probability distribution, is bounded and valid, and dynamically adjusts with temperature.

**TL;DR翻译**: P-less Sampling：一种基于信息论的无参数采样策略，其截断阈值根据整个 token 概率分布自适应调整，具有有界性和有效性，并能随温度动态调节。

**Abstract**:

Obtaining high-quality outputs from Large Language Models (LLMs) often depends upon the choice of a sampling-based decoding strategy to probabilistically choose the next token at each generation step. While a variety of such sampling methods have been proposed, their performance can be sensitive to the selection of hyperparameters which may require different settings depending upon the generation task and temperature configuration. In this work, we introduce $p\textrm{-less}$ sampling: an information-theoretic approach to sampling which dynamically sets a truncation threshold at each decoding step based on the entire token probability distribution. Unlike existing methods, $p\textrm{-less}$ sampling has no hyperparameters and consistently produces high-quality outputs as temperature increases. We provide theoretical perspectives on $p$-less sampling to ground our proposed method and conduct experiments to empirically validate its effectiveness across a range of math, logical reasoning, and creative writing tasks. Our results demonstrate how $p\textrm{-less}$ sampling consistently outperforms existing sampling approaches while exhibiting much less degradation in text quality at higher temperature values. We further show how $p$-less achieves greater inference-time efficiency than alternative methods through lower average token sampling times and shorter generation lengths, without sacrificing accuracy.
Finally, we provide analyses to highlight the benefits of $p\textrm{-less}$ through qualitative examples, case studies, and diversity assessments.

**摘要翻译**:

从大语言模型（LLM）中获取高质量输出，通常依赖于选择基于采样的解码策略，在每个生成步骤中以概率方式选取下一个 token。虽然已有多种此类采样方法被提出，但它们的性能对超参数的选择较为敏感，而不同的生成任务和温度配置可能需要不同的参数设置。在本文中，我们提出了 $p\textrm{-less}$ sampling：一种基于信息论的采样方法，在每个解码步骤根据完整的 token 概率分布动态设置截断阈值。与现有方法不同，$p\textrm{-less}$ sampling 不含任何超参数，并且在温度升高时仍能稳定生成高质量输出。我们从理论角度对 $p$-less sampling 进行了分析以奠定方法基础，并通过实验在数学、逻辑推理和创意写作等一系列任务上验证了其有效性。实验结果表明，$p\textrm{-less}$ sampling 始终优于现有采样方法，且在较高温度下文本质量的下降幅度显著更小。我们还进一步展示了 $p$-less 通过更低的平均 token 采样时间和更短的生成长度实现了比替代方法更高的推理效率，同时不牺牲准确性。最后，我们通过定性示例、案例研究和多样性评估分析了 $p\textrm{-less}$ 的优势。

---

## 31. EigenBench: A Comparative Behavioral Measure of Value Alignment

**EigenBench：一种价值对齐的比较行为度量方法**

**OpenReview**: [https://openreview.net/forum?id=fm79KXJIUQ](https://openreview.net/forum?id=fm79KXJIUQ)

**Authors**: Jonathn Chang (Cornell University), Leonhard Piff (Cornell University), Suvadip Sana (Cornell University), Jasmine Xinze Li (Cornell University), Lionel Levine (Cornell University)

**Institutions**: Cornell University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: value alignment, Bradley-Terry model, EigenTrust, model disposition, constitutional AI

**Abstract**:

Aligning AI with human values is a pressing unsolved problem. To address the lack of quantitative metrics for value alignment, we propose EigenBench: a black-box method for comparatively benchmarking language models' values. Given an ensemble of models, a constitution describing a value system, and a dataset of scenarios, our method returns a vector of scores quantifying each model's alignment to the given constitution. To produce these scores, each model judges the outputs of other models across many scenarios, and these judgments are aggregated with EigenTrust (Kamvar et al., 2003), yielding scores that reflect a weighted consensus judgment of the whole ensemble. EigenBench uses no ground truth labels, as it is designed to quantify subjective traits for which reasonable judges may disagree on the correct label. Hence, to validate our method, we collect human judgments on the same ensemble of models and show that EigenBench's judgments align closely with those of human evaluators. We further demonstrate that EigenBench can recover model rankings on the GPQA benchmark without access to objective labels, supporting its viability as a framework for evaluating subjective values for which no ground truths exist.

**摘要翻译**:

使 AI 与人类价值观对齐是一个亟待解决的问题。为弥补价值对齐定量指标的缺失，我们提出了 EigenBench：一种用于比较评测语言模型价值观的黑箱方法。给定一组模型集合、描述价值体系的准则文档以及场景数据集，该方法返回一个分数向量，量化每个模型与给定准则的对齐程度。为生成这些分数，每个模型在多种场景下对其他模型的输出进行评判，然后通过 EigenTrust（Kamvar 等，2003）聚合这些评判结果，得到反映整个集合加权共识的分数。EigenBench 不使用真实标签，因为它旨在量化主观特征——对于此类特征，合理的评判者可能对正确标签存在分歧。因此，为验证该方法，我们在相同的模型集合上收集了人类评判，并证明 EigenBench 的评判与人类评估者的判断高度一致。我们还进一步证明，EigenBench 能够在无需访问客观标签的情况下恢复模型在 GPQA 基准上的排名，这表明它作为评估不存在真实标签的主观价值的框架具有可行性。

---

## 32. A Representer Theorem for Hawkes Processes via Penalized Least Squares Minimization

**基于惩罚最小二乘最小化的 Hawkes 过程表示定理**

**OpenReview**: [https://openreview.net/forum?id=gJjRdLG5MY](https://openreview.net/forum?id=gJjRdLG5MY)

**Authors**: Hideaki Kim (NTT), Tomoharu Iwata (NTT)

**Institutions**: NTT

**Primary Area**: learning theory

**Keywords**: Hawkes processes, kernel methods, representer theorem, point processes, least squares loss

**Abstract**:

The representer theorem is a cornerstone of kernel methods, which aim to estimate latent functions in reproducing kernel Hilbert spaces (RKHSs) in a nonparametric manner. Its significance lies in converting inherently infinite-dimensional optimization problems into finite-dimensional ones over dual coefficients, thereby enabling practical and computationally tractable algorithms. In this paper, we address the problem of estimating the latent triggering kernels--functions that encode the interaction structure between events--for linear multivariate Hawkes processes based on observed event sequences within an RKHS framework. We show that, under the principle of penalized least squares minimization, a novel form of representer theorem emerges: a family of transformed kernels can be defined via a system of simultaneous integral equations, and the optimal estimator of each triggering kernel is expressed as a linear combination of these transformed kernels evaluated at the data points. Remarkably, the dual coefficients are all analytically fixed to unity, obviating the need to solve a costly optimization problem to obtain the dual coefficients. This leads to a highly efficient estimator capable of handling large-scale data more effectively than conventional nonparametric approaches. Empirical evaluations on synthetic and real-world datasets reveal that the proposed method achieves competitive predictive accuracy while substantially improving computational efficiency compared to state-of-the-art kernel method-based estimators.

**摘要翻译**:

表示定理是核方法的基石，核方法旨在以非参数方式在再生核 Hilbert 空间（RKHS）中估计潜在函数。其重要意义在于将本质上无穷维的优化问题转化为对偶系数上的有限维问题，从而使算法具有实际可行性和计算可处理性。本文研究了在 RKHS 框架下，基于观测事件序列估计线性多变量 Hawkes 过程的潜在触发核——编码事件间交互结构的函数——的问题。我们证明，在惩罚最小二乘最小化原则下，一种新形式的表示定理得以涌现：可以通过一组联立积分方程定义一族变换核，每个触发核的最优估计量表示为这些变换核在数据点处取值的线性组合。值得注意的是，对偶系数均解析地固定为 1，无需通过求解代价高昂的优化问题来获取对偶系数。这带来了一个高效的估计量，能够比传统非参数方法更有效地处理大规模数据。在合成数据集和真实数据集上的实验评估表明，与现有最先进的基于核方法的估计量相比，所提方法在取得有竞争力的预测精度的同时，计算效率得到了显著提升。

---

## 33. UALM: Unified Audio Language Model for Understanding, Generation and Reasoning

**UALM：面向理解、生成与推理的统一音频语言模型**

**OpenReview**: [https://openreview.net/forum?id=TsdlOjcQNu](https://openreview.net/forum?id=TsdlOjcQNu)

**Authors**: Jinchuan Tian (CMU, Carnegie Mellon University), Sang-gil Lee (NVIDIA), Zhifeng Kong (NVIDIA), Sreyan Ghosh (University of Maryland, College Park), Arushi Goel (NVIDIA Research), Chao-Han Huck Yang (NVIDIA Research), Wenliang Dai (NVIDIA), Zihan Liu (NVIDIA), Hanrong Ye, Shinji Watanabe (Japan Broadcasting Corporation), Mohammad Shoeybi (NVIDIA), Bryan Catanzaro (NVIDIA), Rafael Valle (NVIDIA), Wei Ping (NVIDIA)

**Institutions**: CMU, Carnegie Mellon University, NVIDIA, University of Maryland, College Park, NVIDIA Research, Japan Broadcasting Corporation

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Audio Language Model, Audio Understanding, Audio Generation

**TL;DR**: This paper introduces UALM, an audio language model designed to unify audio understanding, generation, and reasoning

**TL;DR翻译**: 本文提出了 UALM，一种旨在统一音频理解、生成和推理的音频语言模型

**Abstract**:

Recent advances in the audio language modeling (ALM) domain tackle audio understanding and text-to-audio generation as separate tasks. Very few studies attempt to unify these tasks -- an essential step toward advanced multimodal reasoning. This paper introduces Unified Audio Language Model (UALM), which aims to unify audio understanding, text-to-audio generation, and multimodal reasoning in a single model. To achieve this goal, we first present UALM-Gen, a text-to-audio language model that directly predicts audio tokens and is comparable to state-of-the-art diffusion-based models. We then demonstrate, using proper data blending, training recipes, and inference techniques, that our single UALM model matches the quality of state-of-the-art specialized models in audio understanding, text-to-audio generation, and text reasoning.  Furthermore, we present UALM-R1, a multimodal reasoning model that utilizes both text and audio in the intermediate thinking steps to facilitate complex generation tasks. To our knowledge, this is the first demonstration in audio research of cross-modal generative reasoning, with its effectiveness confirmed by subjective evaluations.

**摘要翻译**:

音频语言建模（ALM）领域的最新进展将音频理解和文本到音频生成作为独立任务分别处理。极少有研究尝试将这些任务统一起来——而这是迈向高级多模态推理的关键一步。本文提出了统一音频语言模型（UALM），旨在将音频理解、文本到音频生成和多模态推理统一在单一模型中。为实现这一目标，我们首先提出了 UALM-Gen，一种直接预测音频 token 的文本到音频语言模型，其性能可与最先进的基于扩散的模型相媲美。随后我们展示了，通过合理的数据混合、训练方案和推理技术，我们的单一 UALM 模型在音频理解、文本到音频生成和文本推理方面均达到了最先进的专用模型的质量。此外，我们提出了 UALM-R1，一种在中间思考步骤中同时利用文本和音频的多模态推理模型，以促进复杂生成任务。据我们所知，这是音频研究中跨模态生成推理的首次展示，其有效性已通过主观评估得到验证。

---

## 34. Agent Data Protocol

**Agent Data Protocol（智能体数据协议）**

**OpenReview**: [https://openreview.net/forum?id=tG6301ORHd](https://openreview.net/forum?id=tG6301ORHd)

**Authors**: Yueqi Song (Carnegie Mellon University), Ketan Ramaneti (Amazon), Zaid Sheikh (Carnegie Mellon University), Ziru Chen (Ohio State University, Columbus), Boyu Gou (Ohio State University, Columbus), Tianbao Xie (University of Hong Kong), Yiheng Xu, Danyang Zhang (Shanghai Jiao Tong University), Apurva Gandhi (Carnegie Mellon University), Fan Yang (Fujitsu), Joseph Liu (School of Computer Science, Carnegie Mellon University), Tianyue Ou, Zhihao Yuan (Carnegie Mellon University), Frank F. Xu (Microsoft), Shuyan Zhou (Duke University), Xingyao Wang (All Hands AI), Xiang Yue, Tao Yu (The University of Hong Kong), Huan Sun (The Ohio State University, Columbus), Yu Su (Ohio State University), Graham Neubig (Carnegie Mellon University)

**Institutions**: Carnegie Mellon University, Amazon, Ohio State University, Columbus, University of Hong Kong, Shanghai Jiao Tong University, Fujitsu, School of Computer Science, Carnegie Mellon University, Microsoft, Duke University, All Hands AI, The University of Hong Kong, The Ohio State University, Columbus, Ohio State University

**Primary Area**: datasets and benchmarks

**Keywords**: agent, training, data

**Abstract**:

Public research results on large-scale supervised finetuning of AI agents remain relatively rare, since the collection of agent training data presents unique challenges. In this work, we argue that the bottleneck is not a lack of underlying data sources, but that a large variety of data is fragmented across heterogeneous formats, tools, and interfaces. To this end, we introduce the Agent Data Protocol (ADP), a light-weight representation language that serves as an "interlingua" between agent datasets in diverse formats and unified agent training pipelines downstream. The design of ADP is expressive enough to capture a large variety of tasks, including API/tool use, browsing, coding, software engineering, and general agentic workflows, while remaining simple to parse and train on without engineering at a per-dataset level. In experiments, we unified a broad collection of 13 existing agent training datasets into ADP format, and converted the standardized ADP data into training-ready formats for multiple agent frameworks. We performed supervised finetuning on the unified data, and demonstrated an average performance gain of $\sim$20\% over
corresponding base models, and delivers state-of-the-art or near-SOTA performance on standard coding, browsing, tool use, and research benchmarks, without domain-specific tuning. All code and data are released publicly, in the hope that ADP could help lower the barrier to standardized, scalable, and reproducible agent training.

**摘要翻译**:

关于 AI 智能体大规模监督微调的公开研究成果仍然相对稀少，因为智能体训练数据的收集面临独特挑战。在本文中，我们认为瓶颈并非缺乏底层数据源，而在于大量数据分散于异构的格式、工具和接口之中。为此，我们提出了 Agent Data Protocol（ADP），一种轻量级的表示语言，充当多样化格式的智能体数据集与下游统一智能体训练流水线之间的"中间语言"。ADP 的设计具有足够的表达能力，可以涵盖多种任务，包括 API/工具使用、网页浏览、编程、软件工程以及通用智能体工作流，同时保持简单易解析的特性，无需针对每个数据集进行单独的工程适配即可用于训练。在实验中，我们将 13 个现有智能体训练数据集统一转换为 ADP 格式，并将标准化的 ADP 数据转换为多个智能体框架的训练就绪格式。我们在统一数据上进行了监督微调，结果表明相比对应的基础模型平均性能提升约 20%，并在标准的编程、浏览、工具使用和研究基准测试上达到了最先进或接近最先进的性能，且无需领域特定的调优。所有代码和数据均已公开发布，期望 ADP 能够降低标准化、可扩展和可复现的智能体训练的门槛。

---

## 35. OpenApps: Simulating Environment Variations to Measure UI Agent Reliability

**OpenApps：模拟环境变化以衡量 UI 智能体可靠性**

**OpenReview**: [https://openreview.net/forum?id=cj1MAx7lKs](https://openreview.net/forum?id=cj1MAx7lKs)

**Authors**: Karen Ullrich (Meta AI), Jingtong Su, Claudia Shi (Columbia University), Arjun Subramonian, Amir Bar (Facebook), Ivan Evtimov (Facebook), Nikolaos Tsilivis (New York University), Randall Balestriero (Brown University), Julia Kempe, Mark Ibrahim (Facebook AI Research (FAIR) Meta)

**Institutions**: Meta AI, Columbia University, Facebook, New York University, Brown University, Facebook AI Research (FAIR) Meta

**Primary Area**: datasets and benchmarks

**Keywords**: reinforcement learning, agents, envrionment, reliability

**TL;DR**: We introduce a new environment, OpenApps, for generating thousands of versions of apps to test UI agent reliability.

**TL;DR翻译**: 我们提出了一个新环境 OpenApps，可生成数千个应用版本以测试 UI 智能体的可靠性。

**Abstract**:

Reliability is key to realizing the promise of autonomous UI-agents, multimodal agents that directly interact with the apps humans use, as users must be able to trust an agent to complete a given task. Current evaluations rely on fixed environments---often clones of existing apps--- which are limited in that they can only shed light on whether or how often an agent can complete a task within a specific environment. When deployed however, agents are likely to encounter variations in app design and content that can affect an agent's ability to complete a task. To address this blind spot of measuring agent reliability across app variations, we develop OpenApps, a light-weight open-source ecosystem with six apps (messenger, calendar, maps, etc.) that are configurable in appearance and content. OpenApps requires just a single CPU to run, enabling easy generation and deployment of thousands of versions of each app. Specifically, we run more than 10,000 independent evaluations to study reliability across seven leading multimodal agents. We find that while standard reliability within a fixed app is relatively stable, reliability can vary drastically when measured across app variations. Task success rates for many agents can fluctuate by more than 50\% across app variations. For example, Kimi-VL-3B's average success across all tasks fluctuates from 63\% to just 4\% across app versions. We also find agent behaviors such as looping or hallucinating actions can differ drastically depending on the environment configuration. These initial findings highlight the importance of measuring reliability along this new dimension of app variations.

**摘要翻译**:

可靠性是实现自主 UI 智能体——即直接与人类使用的应用程序交互的多模态智能体——潜力的关键，因为用户必须能够信任智能体完成给定任务。当前的评测依赖于固定环境——通常是现有应用的克隆——其局限性在于只能揭示智能体能否或多频繁地在特定环境中完成任务。然而在实际部署时，智能体很可能会遇到应用设计和内容上的变化，这些变化可能影响其完成任务的能力。为解决跨应用变体衡量智能体可靠性这一盲区，我们开发了 OpenApps，一个包含六个应用（消息、日历、地图等）的轻量级开源生态系统，其外观和内容均可配置。OpenApps 仅需单个 CPU 即可运行，便于轻松生成和部署每个应用的数千个版本。具体而言，我们运行了超过 10,000 次独立评测，以研究七个领先多模态智能体的跨版本可靠性。我们发现，虽然在固定应用内的标准可靠性相对稳定，但在不同应用变体间衡量时，可靠性可能出现剧烈波动。许多智能体的任务成功率在不同应用变体间波动幅度超过 50%。例如，Kimi-VL-3B 在所有任务上的平均成功率在不同应用版本间从 63% 波动至仅 4%。我们还发现，智能体的循环行为或幻觉操作等行为可能因环境配置不同而表现出巨大差异。这些初步发现凸显了在应用变体这一新维度上衡量可靠性的重要性。

---

## 36. Overparametrization bends the landscape: BBP transitions at initialization in simple Neural Networks

**过参数化弯曲了损失景观：简单神经网络初始化时的 BBP 相变**

**OpenReview**: [https://openreview.net/forum?id=xDLE5n3x9Y](https://openreview.net/forum?id=xDLE5n3x9Y)

**Authors**: Brandon Livio Annesi (University of Roma "La Sapienza"), Dario Bocchi (University of Roma "La Sapienza"), Chiara Cammarota (University of Roma "La Sapienza")

**Institutions**: University of Roma "La Sapienza"

**Primary Area**: learning theory

**Keywords**: Overparametrization, Loss landscapes, Signal recovery, High-dimensional learning

**TL;DR**: We quantitatively analyze how overparametrization reshapes the high-dimensional loss landscape of a teacher–student setup in random positions, showing it can anticipate and qualitatively alter transitions between successful and failed signal recovery

**TL;DR翻译**: 我们定量分析了过参数化如何在随机位置重塑教师-学生模型的高维损失景观，表明它能提前触发并定性地改变信号恢复成功与失败之间的相变。

**Abstract**:

High-dimensional non-convex loss landscapes play a central role in the theory of Machine Learning. Gaining insight into how these landscapes interact with gradient-based optimization methods, even in relatively simple models, can shed light on this enigmatic feature of neural networks. In this work, we will focus on a prototypical simple learning problem, which generalizes the Phase Retrieval inference problem by allowing the exploration of overparametrized settings. Using techniques from field theory, we analyze the spectrum of the Hessian at initialization and identify a Baik–Ben Arous–Péché (BBP) transition in the amount of data that separates regimes where the initialization is informative or uninformative about a planted signal of a teacher-student setup. Crucially, we demonstrate how overparameterization can "bend" the loss landscape, shifting the transition point, even reaching the information-theoretic weak-recovery threshold in the large overparameterization limit, while also altering its qualitative nature.
 We distinguish between continuous and discontinuous BBP transitions and support our analytical predictions with simulations, examining how they compare to the finite-N behavior. In the case of discontinuous BBP transitions strong finite-N corrections allow the retrieval of information at a signal-to-noise ratio (SNR) smaller than the predicted BBP transition. In these cases we provide estimates for a new lower SNR threshold that marks the point at which initialization becomes entirely uninformative.

**摘要翻译**:

高维非凸损失景观在机器学习理论中扮演着核心角色。即便在相对简单的模型中，深入理解这些景观如何与基于梯度的优化方法相互作用，也能为神经网络的这一神秘特性提供启示。在本文中，我们聚焦于一个原型简单学习问题，该问题通过允许探索过参数化设置来推广相位恢复推断问题。利用场论技术，我们分析了初始化时 Hessian 矩阵的谱，并识别出一个 Baik-Ben Arous-Péché（BBP）相变——该相变发生在数据量上，分隔了初始化对教师-学生模型中植入信号具有信息性或不具有信息性的两个区域。关键的是，我们证明了过参数化能够"弯曲"损失景观、移动相变点，在大过参数化极限下甚至可以达到信息论弱恢复阈值，同时还改变了相变的定性特征。

我们区分了连续和不连续的 BBP 相变，并通过仿真验证了分析预测，考察了它们与有限 N 行为的对比。在不连续 BBP 相变的情况下，强有限 N 修正使得在低于预测 BBP 相变的信噪比（SNR）下仍能提取信息。在这些情况下，我们给出了一个新的更低 SNR 阈值的估计，该阈值标志着初始化变得完全不具有信息性的临界点。

---

## 37. Softmax Transformers are Turing-Complete

**Softmax Transformer 是图灵完备的**

**OpenReview**: [https://openreview.net/forum?id=FdkPOHlChS](https://openreview.net/forum?id=FdkPOHlChS)

**Authors**: Hongjian Jiang (Rheinland-Pfälzische Technische Universität), Michael Hahn (Universität des Saarlandes), Georg Zetzsche (MPI-SWS), Anthony Widjaja Lin (MPI-SWS)

**Institutions**: Rheinland-Pfälzische Technische Universität, Universität des Saarlandes, MPI-SWS

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: soft attention, FLaNN, recursively enumerable, Turing-complete, formal languages

**Abstract**:

Hard attention Chain-of-Thought (CoT) transformers are known to be Turing-complete. However, it is an open problem whether softmax attention Chain-of-Thought (CoT) transformers are Turing-complete. In this paper, we prove a stronger result that length-generalizable softmax CoT transformers are Turing-complete.

More precisely, our Turing-completeness proof goes via the CoT extension of the Counting RASP (C-RASP), which correspond to softmax CoT transformers that admit length generalization. We prove Turing-completeness for CoT C-RASP with causal masking over a unary alphabet (more generally, for the letter-bounded languages). While we show that this is actually not Turing-complete for arbitrary languages, we prove that its extension with relative positional encoding is Turing-complete for arbitrary languages. We empirically validate our theoretical results by training transformers for various languages that require complex (non-linear) arithmetic reasoning.

**摘要翻译**:

已知硬注意力链式思维（CoT）Transformer 是图灵完备的。然而，softmax 注意力链式思维（CoT）Transformer 是否图灵完备仍是一个开放问题。在本文中，我们证明了一个更强的结果：具有长度泛化能力的 softmax CoT Transformer 是图灵完备的。

更具体地说，我们的图灵完备性证明通过 Counting RASP（C-RASP）的 CoT 扩展来实现，该扩展对应于具有长度泛化能力的 softmax CoT Transformer。我们证明了在一元字母表上（更一般地，对于字母有界语言）带因果掩码的 CoT C-RASP 是图灵完备的。虽然我们表明对于任意语言它实际上并非图灵完备，但我们证明了其加入相对位置编码的扩展对于任意语言是图灵完备的。我们通过训练 Transformer 处理需要复杂（非线性）算术推理的各种语言，从实验上验证了我们的理论结果。

---

## 38. Steering the Herd: A Framework for LLM-based Control of Social Learning

**引导群体：基于 LLM 的社会学习控制框架**

**OpenReview**: [https://openreview.net/forum?id=RtS4UqSmNt](https://openreview.net/forum?id=RtS4UqSmNt)

**Authors**: Raghu Arghal (University of Pennsylvania, University of Pennsylvania), Kevin He, Shirin Saeedi Bidokhti (University of Pennsylvania, University of Pennsylvania), Saswati Sarkar (University of Pennsylvania)

**Institutions**: University of Pennsylvania, University of Pennsylvania, University of Pennsylvania

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Social learning, LLMs, optimal control, information design, dynamic programming

**TL;DR**: We introduce, analyze, and simulate (via LLMs) a model of controlled social learning to study how algorithms can influence social beliefs, decisions, and welfare via information design.

**TL;DR翻译**: 我们提出、分析并通过 LLM 仿真了一个受控社会学习模型，以研究算法如何通过信息设计影响社会信念、决策和福利。

**Abstract**:

Algorithms increasingly serve as information mediators -- from social media feeds and targeted advertising to the increasing ubiquity of LLMs. This engenders a joint process where agents combine private, algorithmically-mediated signals with observational learning from peers to arrive at decisions. To study such settings, we introduce a model of controlled sequential social learning in which an information-mediating planner (e.g., an LLM) controls the information structure of agents while they also learn from the decisions of earlier agents. The planner may seek to improve social welfare (an altruistic planner) or to induce a specific action the planner prefers (a biased planner). Our framework presents a new optimization problem for social learning that combines dynamic programming with decentralized action choices and Bayesian belief updates. In this setting, we prove the convexity of the value function and characterize the optimal policies of altruistic and biased planners, which attain desired tradeoffs between the costs they incur and the payoffs they earn from induced agent choices. The characterization reveals that the optimal planner operates in different modes depending on the range of belief values. The modes include investing the maximum allowed resource, not investing any resource, or the investment increasing or decreasing with increase in the belief. Notably, for some ranges of belief the biased planner even intentionally obfuscates the agents' signals. Even under stringent transparency constraints—information parity with individuals, no lying or cherry‑picking, and full observability—we show that information mediation can substantially shift social welfare in either direction. We complement our theory with simulations in which LLMs act as both planner and agents. Notably, the LLM-based planner in our simulations exhibits emergent strategic behavior in steering public opinion that broadly mirrors the trends predicted, though key deviations suggest the influence of non-Bayesian reasoning—consistent with the cognitive patterns of both human users and LLMs trained on human-like data. Together, we establish our framework as a tractable basis for studying the impact and regulation of LLM information mediators that corresponds to real behavior.

**摘要翻译**:

算法日益充当信息中介的角色——从社交媒体信息流和定向广告到日益普及的大语言模型。这催生了一个联合过程：智能体将私有的、由算法中介的信号与从同伴处的观察学习相结合来做出决策。为研究这类场景，我们引入了一个受控序贯社会学习模型，其中信息中介规划者（例如 LLM）控制智能体的信息结构，同时智能体也从较早智能体的决策中学习。规划者可能致力于提升社会福利（利他型规划者），也可能试图诱导其偏好的特定行为（偏向型规划者）。我们的框架提出了一个新的社会学习优化问题，将动态规划与去中心化行动选择和贝叶斯信念更新相结合。在此设定下，我们证明了价值函数的凸性，并刻画了利他型和偏向型规划者的最优策略，这些策略在其付出的成本与从诱导的智能体选择中获得的收益之间实现了期望的权衡。刻画结果揭示，最优规划者根据信念值的不同范围以不同模式运行。这些模式包括投入最大允许资源、不投入任何资源、或投入随信念增加而增加或减少。值得注意的是，在某些信念范围内，偏向型规划者甚至会刻意混淆智能体的信号。即便在严格的透明性约束下——与个体的信息对等、不得撒谎或选择性提供信息、以及完全可观测——我们表明信息中介仍能使社会福利向两个方向大幅偏移。我们以 LLM 同时担任规划者和智能体的仿真实验作为理论的补充。值得注意的是，仿真中基于 LLM 的规划者在引导公众舆论方面展现出涌现的策略行为，总体趋势与理论预测相符，尽管关键偏差表明非贝叶斯推理的影响——这与人类用户和基于类人数据训练的 LLM 的认知模式一致。综合而言，我们建立的框架为研究 LLM 信息中介的影响和监管提供了一个可处理的基础，且与真实行为相对应。

---

## 39. Quantitative Bounds for Length Generalization in Transformers

**Transformer 长度泛化的定量界**

**OpenReview**: [https://openreview.net/forum?id=TLSUIyBIfs](https://openreview.net/forum?id=TLSUIyBIfs)

**Authors**: Zachary Izzo (NEC Labs America), Eshaan Nichani (Princeton University), Jason D. Lee (Princeton University)

**Institutions**: NEC Labs America, Princeton University

**Primary Area**: learning theory

**Keywords**: transformers, theory, length generalization

**TL;DR**: We provide an upper bound on the length of training sequences required for a transformer to generalize to sequences of arbitrary lengths.

**TL;DR翻译**: 我们给出了 Transformer 泛化到任意长度序列所需训练序列长度的上界。

**Abstract**:

We study the problem of length generalization (LG) in transformers: the ability of a model trained on shorter sequences to maintain performance when evaluated on much longer, previously unseen inputs. Prior work by Huang et al. (2024) established that transformers eventually achieve length generalization once the training sequence length exceeds some finite threshold, but left open the question of how large it must be. In this work, we provide the first quantitative bounds on the required training length for length generalization to occur.
Motivated by previous empirical and theoretical work, we analyze LG in several distinct problem settings: $\ell_\infty$ error control vs. average error control over an input distribution, infinite-precision softmax attention vs. finite-precision attention (which reduces to an argmax) in the transformer, as well as for one- or two-layer transformers. In all scenarios, we prove that LG occurs when the internal behavior of the transformer on longer sequences can be "simulated" by its behavior on shorter sequences seen during training. Our bounds give qualitative estimates for the required length of training data required for a transformer to generalize, and we verify these insights empirically. These results sharpen our theoretical understanding of the mechanisms underlying extrapolation in transformers, and formalize the intuition that richer training data is required for generalization on more complex tasks.

**摘要翻译**:

我们研究 Transformer 中的长度泛化（LG）问题：即在较短序列上训练的模型在评估远长于训练序列、此前未见的输入时保持性能的能力。Huang 等人（2024）的先前工作已确立，一旦训练序列长度超过某个有限阈值，Transformer 最终能实现长度泛化，但该阈值具体需要多大这一问题尚未解决。在本文中，我们首次给出了长度泛化所需训练长度的定量界。

受先前实证和理论工作的启发，我们在多个不同的问题设定下分析长度泛化：$\ell_\infty$ 误差控制与输入分布上的平均误差控制、Transformer 中无限精度 softmax 注意力与有限精度注意力（退化为 argmax）的对比，以及单层和双层 Transformer 的情形。在所有场景中，我们证明了当 Transformer 在更长序列上的内部行为可以被训练期间见过的较短序列上的行为"模拟"时，长度泛化就会发生。我们的界给出了 Transformer 实现泛化所需训练数据长度的定性估计，并通过实验验证了这些见解。这些结果加深了我们对 Transformer 中外推机制的理论理解，并将"更复杂任务的泛化需要更丰富训练数据"这一直觉形式化。

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

---

## 41. LLM Fingerprinting via Semantically Conditioned Watermarks

**基于语义条件水印的 LLM 指纹识别**

**OpenReview**: [https://openreview.net/forum?id=t38nZqqi3Z](https://openreview.net/forum?id=t38nZqqi3Z)

**Authors**: Thibaud Gloaguen (ETH Zurich), Robin Staab (ETHZ - ETH Zurich), Nikola Jovanović (ETHZ - ETH Zurich), Martin Vechev (ETHZ - ETH Zurich)

**Institutions**: ETH Zurich, ETHZ - ETH Zurich

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: LLM, Watermarks, Fingerprinting

**TL;DR**: We introduce a robust LLM fingerprinting method based on semantically conditioned watermarks

**TL;DR翻译**: 我们提出了一种基于语义条件水印的鲁棒 LLM 指纹识别方法

**Abstract**:

Most LLM fingerprinting methods teach the model to respond to a few fixed queries with predefined atypical responses (keys). This memorization often does not survive common deployment steps such as finetuning or quantization, and such keys can be easily detected and filtered from LLM responses, ultimately breaking the fingerprint. To overcome these limitations we introduce *LLM fingerprinting via semantically conditioned watermarks*, replacing fixed query sets with a broad semantic domain, and replacing brittle atypical keys with a statistical watermarking signal diffused throughout each response. After teaching the model to watermark its responses only to prompts from a predetermined domain e.g., French language, the model owner can use queries from that domain to reliably detect the fingerprint and verify ownership. As we confirm in our thorough experimental evaluation, our fingerprint is both stealthy and robust to all common deployment scenarios.

**摘要翻译**:

大多数 LLM 指纹识别方法通过教导模型对少数固定查询给出预定义的非典型响应（密钥）来实现。这种记忆往往无法在微调或量化等常见部署步骤中保持，且此类密钥容易从 LLM 响应中被检测和过滤，最终导致指纹失效。为克服这些限制，我们提出了*基于语义条件水印的 LLM 指纹识别方法*，用广泛的语义域替代固定查询集，用扩散到整个响应中的统计水印信号替代脆弱的非典型密钥。在教导模型仅对来自预定域（例如法语）的提示添加水印后，模型所有者可以使用该域的查询来可靠地检测指纹并验证所有权。正如我们在全面的实验评估中所确认的，该指纹方法既具有隐蔽性，又对所有常见部署场景具有鲁棒性。

---

## 42. Universal Inverse Distillation for Matching Models with Real-Data Supervision (No GANs)

**通用逆蒸馏：使用真实数据监督的匹配模型加速方法（无需 GAN）**

**OpenReview**: [https://openreview.net/forum?id=8NuN5UzXLC](https://openreview.net/forum?id=8NuN5UzXLC)

**Authors**: Nikita Maksimovich Kornilov (Applied AI Institute), David Li (Mohamed bin Zayed University of Artificial Intelligence), Tikhon Mavrin (Applied AI Institute), Aleksei Leonov (Huawei Technologies Ltd.), Nikita Gushchin (Applied AI Institute), Evgeny Burnaev (Applied AI Institute), Iaroslav Sergeevich Koshelev (Huawei Technologies Ltd.), Alexander Korotin

**Institutions**: Applied AI Institute, Mohamed bin Zayed University of Artificial Intelligence, Applied AI Institute, Huawei Technologies Ltd.

**Primary Area**: generative models

**Keywords**: Diffusion models, Flow Matching, Acceleration of diffusion/flow models, Distillation of diffusion/flow models

**Abstract**:

While achieving exceptional generative quality, modern diffusion, flow, and other matching models suffer from slow inference, as they require many steps of iterative generation. Recent distillation methods address this by training efficient one-step generators under the guidance of a pre-trained teacher model. However, these methods are often constrained to only one specific framework, e.g., only to diffusion or only to flow models. Furthermore, these methods are naturally data-free, and to benefit from the usage of real data, it is required to use an additional complex adversarial training with an extra discriminator model. In this paper, we present **RealUID**, a unified distillation framework for all matching models that seamlessly incorporates real data into the distillation procedure without GANs. Our **RealUID** approach offers a simple theoretical foundation that covers previous distillation methods for Flow Matching and Diffusion models, and is also extended to their modifications, such as Bridge Matching and Stochastic Interpolants.

**摘要翻译**:

尽管现代扩散模型、流模型及其他匹配模型取得了卓越的生成质量，但由于需要多步迭代生成，其推理速度较慢。近期的蒸馏方法通过在预训练教师模型的指导下训练高效的单步生成器来解决这一问题。然而，这些方法通常仅适用于某一特定框架，例如仅适用于扩散模型或仅适用于流模型。此外，这些方法本质上是无数据的，若要利用真实数据，则需要引入额外的复杂对抗训练和判别器模型。在本文中，我们提出了 **RealUID**，一个面向所有匹配模型的统一蒸馏框架，能够在无需 GAN 的情况下将真实数据无缝融入蒸馏过程。我们的 **RealUID** 方法提供了简洁的理论基础，涵盖了此前针对 Flow Matching 和 Diffusion 模型的蒸馏方法，并进一步扩展至 Bridge Matching 和 Stochastic Interpolants 等变体。

---

## 43. Mixture-of-Experts Can Surpass Dense LLMs Under Strictly Equal Resource

**在严格相同资源约束下，混合专家模型可以超越稠密大语言模型**

**OpenReview**: [https://openreview.net/forum?id=oIdzliJAeA](https://openreview.net/forum?id=oIdzliJAeA)

**Authors**: Houyi Li (Fudan University), Ka Man Lo (University of Macau), Shijie Xuyang (Fudan University), Ziqi Wang (University of Science and Technology of China), Wenzhen Zheng (Stepfun), Haocheng Zhang (Fudan University), Zhao Li (Hangzhou Yugu Technology Co., Ltd.), Shuigeng Zhou (Fudan University), Xiangyu Zhang (MEGVII Technology), Daxin Jiang (StepFun)

**Institutions**: Fudan University, University of Macau, University of Science and Technology of China, Stepfun, Hangzhou Yugu Technology Co., Ltd., MEGVII Technology, StepFun

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Large language models (LLM), Pre-training, Mixture-of-Experts (MoE)

**Abstract**:

Mixture-of-Experts (MoE) language models dramatically expand model capacity and achieve remarkable performance without increasing per-token compute. However, can MoEs surpass dense architectures under strictly equal resource constraints — that is, when the total parameter count, training compute, and data budget are identical? This question remains under-explored despite its significant practical value and potential. In this paper, we propose a novel perspective and methodological framework to study this question thoroughly. First, we comprehensively investigate the architecture of MoEs and achieve an optimal model design that maximizes the performance. Based on this, we subsequently find that an MoE model with activation rate in an optimal region is able to outperform its dense counterpart under the same total parameter, training compute and data resource. More importantly, this optimal region remains consistent across different model sizes. Although additional amount of data turns out to be a trade-off for enhanced performance, we show that this can be resolved via reusing data. We validate our findings through extensive experiments, training nearly 200 language models at 2B scale and over 50 at 7B scale, cumulatively processing 50 trillion tokens. All code and models will be released publicly.

**摘要翻译**:

混合专家（MoE）语言模型能够在不增加每个token计算量的情况下大幅扩展模型容量并实现卓越性能。然而，在严格相同的资源约束下——即总参数量、训练计算量和数据预算完全一致时——MoE能否超越稠密架构？尽管这一问题具有重要的实际价值和潜力，但仍未得到充分探索。本文提出了一种新颖的视角和方法论框架来深入研究这一问题。首先，我们全面研究了MoE的架构，实现了性能最优的模型设计。在此基础上，我们进一步发现，当MoE模型的激活率处于最优区间时，在相同的总参数量、训练计算量和数据资源条件下能够超越其稠密对应模型。更重要的是，这一最优区间在不同模型规模下保持一致。虽然性能提升需要额外的数据量作为代价，但我们证明了通过数据复用可以解决这一问题。我们通过大量实验验证了上述发现，训练了近200个2B规模的语言模型和50多个7B规模的语言模型，累计处理了50万亿个token。所有代码和模型将公开发布。

---

## 44. Pareto-Conditioned Diffusion Models for Offline Multi-Objective Optimization

**面向离线多目标优化的Pareto条件扩散模型**

**OpenReview**: [https://openreview.net/forum?id=S2Q00li155](https://openreview.net/forum?id=S2Q00li155)

**Authors**: Jatan Shrestha (Aalto University), Santeri Heiskanen (Aalto University), Kari Hepola (Tampere University), Severi Rissanen (Aalto University), Pekka Jääskeläinen (Tampere University), Joni Pajarinen (Aalto University)

**Institutions**: Aalto University, Tampere University

**Primary Area**: generative models

**Keywords**: Multi-Objective Optimization, Conditional Diffusion Models

**TL;DR**: We propose Pareto-Conditioned Diffusion (PCD), a novel framework for Offline Multi-Objective Optimization

**TL;DR翻译**: 我们提出了Pareto条件扩散（PCD），一种面向离线多目标优化的新框架

**Abstract**:

Multi-objective optimization (MOO) arises in many real-world applications where trade-offs between competing objectives must be carefully balanced. In the offline setting, where only a static dataset is available, the main challenge is generalizing beyond observed data. We introduce Pareto-Conditioned Diffusion (PCD), a novel framework that formulates offline MOO as a conditional sampling problem. By conditioning directly on desired trade-offs, PCD avoids the need for explicit surrogate models. To effectively explore the Pareto front, PCD employs a reweighting strategy that focuses on high-performing samples and a reference-direction mechanism to guide sampling towards novel, promising regions beyond the training data. Experiments on standard offline MOO benchmarks show that PCD achieves highly competitive performance and, importantly, demonstrates greater consistency across diverse tasks than existing offline MOO approaches.

**摘要翻译**:

多目标优化（MOO）广泛存在于需要在相互竞争的目标之间仔细权衡取舍的实际应用中。在离线场景下，由于仅有静态数据集可用，主要挑战在于如何泛化到已观测数据之外。我们提出了Pareto条件扩散（PCD），一种将离线MOO建模为条件采样问题的新框架。通过直接以期望的权衡方案为条件，PCD无需构建显式代理模型。为了有效探索Pareto前沿，PCD采用了一种重加权策略来聚焦于高性能样本，并引入参考方向机制将采样引导至训练数据之外新颖且有潜力的区域。在标准离线MOO基准上的实验表明，PCD取得了极具竞争力的性能，更重要的是，相比现有的离线MOO方法，它在多样化任务上展现了更强的一致性。

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

---

## 46. The Coverage Principle: How Pre-Training Enables Post-Training

**覆盖率原理：预训练如何赋能后训练**

**OpenReview**: [https://openreview.net/forum?id=AUXvYQlQLZ](https://openreview.net/forum?id=AUXvYQlQLZ)

**Authors**: Fan Chen (Massachusetts Institute of Technology), Audrey Huang (University of Illinois at Urbana-Champaign), Noah Golowich (Microsoft), Sadhika Malladi (Princeton University), Adam Block (Columbia University), Jordan T. Ash (Microsoft Research), Akshay Krishnamurthy (Research, Microsoft), Dylan J Foster (Microsoft Research)

**Institutions**: Massachusetts Institute of Technology, University of Illinois at Urbana-Champaign, Microsoft, Princeton University, Columbia University, Microsoft Research

**Primary Area**: learning theory

**Keywords**: language models, reinforcement learning, test-time scaling, statistical learning theory

**TL;DR**: We introduce the coverage profile, which captures the relationship between pre- and post-training performance and admits a rich statistical theory

**TL;DR翻译**: 我们引入了覆盖率轮廓，它刻画了预训练与后训练性能之间的关系，并具备丰富的统计理论基础

**Abstract**:

Language models demonstrate remarkable abilities when pre-trained on large text corpora and fine-tuned for specific tasks, but how and why pre-training shapes the success of the final model remains poorly understood. Notably, although pre-training success is often quantified by cross entropy loss, cross entropy can be poorly predictive of downstream performance. Instead, we provide a theoretical perspective on this relationship through the lens of coverage, which quantifies the probability mass the pre-trained model places on high-quality responses and which is necessary and sufficient for post-training and test-time scaling methods like Best-of-N to succeed. Our main results develop an understanding of the coverage principle, a phenomenon whereby next-token prediction implicitly optimizes toward a model with good coverage. In particular, we uncover a mechanism that explains the power of coverage in predicting downstream performance: coverage generalizes faster than cross entropy, avoiding spurious dependence on problem dependent parameters such as the sequence length. We also study practical algorithmic interventions with provable benefits for improving coverage, including (i) model/checkpoint selection procedures, (ii) gradient normalization schemes, and (iii) test-time decoding strategies.

**摘要翻译**:

语言模型在大规模文本语料上预训练并针对特定任务微调后展现出卓越能力，但预训练如何以及为何塑造最终模型的成功仍然缺乏深入理解。值得注意的是，虽然预训练的成功通常通过交叉熵损失来衡量，但交叉熵对下游性能的预测能力可能很差。为此，我们从覆盖率的视角提供了一个理论框架来理解这种关系——覆盖率量化了预训练模型赋予高质量响应的概率质量，它是后训练和测试时扩展方法（如Best-of-N）成功的充要条件。我们的主要结果深入阐释了覆盖率原理这一现象，即下一个token预测隐式地优化模型使其具备良好的覆盖率。具体而言，我们揭示了一种机制来解释覆盖率在预测下游性能方面的强大能力：覆盖率比交叉熵泛化更快，避免了对序列长度等问题相关参数的虚假依赖。我们还研究了具有可证明收益的实用算法干预措施来提升覆盖率，包括（i）模型/检查点选择策略，（ii）梯度归一化方案，以及（iii）测试时解码策略。

---

## 47. Conformal Robustness Control: A New Strategy for Robust Decision

**保形鲁棒性控制：一种鲁棒决策新策略**

**OpenReview**: [https://openreview.net/forum?id=bt4Ahpemmi](https://openreview.net/forum?id=bt4Ahpemmi)

**Authors**: Yang Hu (Shanghai Jiaotong University), Jieren Tan (Nankai University), Changliang Zou (Nankai University), Yajie Bao (Nankai University), Haojie Ren (Shanghai Jiaotong University)

**Institutions**: Shanghai Jiaotong University, Nankai University

**Primary Area**: probabilistic methods (Bayesian methods, variational inference, sampling, UQ, etc.)

**Keywords**: Conformal prediction, Contextual robust optimization, Coverage, Decision robustness

**TL;DR**: This paper develops a new strategy for robust decision problems via conformal robustness control.

**TL;DR翻译**: 本文通过保形鲁棒性控制提出了一种解决鲁棒决策问题的新策略。

**Abstract**:

Robust decision-making is crucial in numerous risk-sensitive applications where outcomes are uncertain and the cost of failure is high. Conditional Robust Optimization (CRO) offers a framework for such tasks by constructing prediction sets for the outcome that satisfy predefined coverage requirements and then making decisions based on these sets. Many existing approaches leverage conformal prediction to build prediction sets with guaranteed coverage for CRO. However, since coverage is a *sufficient but not necessary* condition for robustness, enforcing such constraints often leads to overly conservative decisions. To overcome this limitation, we propose a novel framework named Conformal Robustness Control (CRC), that directly optimizes the prediction set construction under explicit robustness constraints, thereby enabling more efficient decisions without compromising robustness. We develop efficient algorithms to solve the CRC optimization problem, and also provide theoretical guarantees on both robustness and optimality. Empirical results show that CRC consistently yields more effective decisions than existing baselines while still meeting the target robustness level.

**摘要翻译**:

在结果不确定且失败代价高昂的众多风险敏感应用中，鲁棒决策至关重要。条件鲁棒优化（CRO）通过构建满足预定覆盖率要求的预测集，并基于这些预测集进行决策，为此类任务提供了一个框架。许多现有方法利用保形预测来构建具有覆盖率保证的预测集以用于CRO。然而，由于覆盖率是鲁棒性的*充分但非必要*条件，施加此类约束往往导致过于保守的决策。为克服这一局限性，我们提出了一个名为保形鲁棒性控制（CRC）的新框架，它在显式鲁棒性约束下直接优化预测集的构建，从而在不牺牲鲁棒性的前提下实现更高效的决策。我们开发了高效算法来求解CRC优化问题，并在鲁棒性和最优性两方面提供了理论保证。实验结果表明，CRC在满足目标鲁棒性水平的同时，一致性地产生比现有基线方法更有效的决策。

---

## 48. HATSolver: Learning Gröbner Bases with Hierarchical Attention Transformers

**HATSolver：使用层次化注意力Transformer学习Gröbner基**

**OpenReview**: [https://openreview.net/forum?id=5C3LljOEGC](https://openreview.net/forum?id=5C3LljOEGC)

**Authors**: Mohamed Malhou (Facebook), Ludovic Perret (Ecole Pour l'Informatique et les Techniques Avancees), Kristin E. Lauter (Facebook)

**Institutions**: Facebook, Ecole Pour l'Informatique et les Techniques Avancees

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: Hierarchical Attention Transformer, Groebner Basis, Symbolic Computation, Multivariate Polynomial Equations

**TL;DR**: Efficient hierarchical attention transformers for learning to solve non-linear equations through by computing groebner bases.

**TL;DR翻译**: 高效的层次化注意力Transformer，通过计算Groebner基来学习求解非线性方程组。

**Abstract**:

At NeurIPS 2024, Kera (2311.12904) introduced the use of transformers for computing Groebner bases, a central object in computer algebra with numerous practical applications. In this paper, we improve this approach by applying Hierarchical Attention Transformers (HATs) to solve systems of multivariate polynomial equations via Groebner bases computation. The HAT architecture incorporates a tree-structured inductive bias that enables the modeling of hierarchical relationships present in the data and thus achieves significant computational savings compared to conventional flat attention models. We generalize to arbitrary depths and include a detailed computational cost analysis. Combined with curriculum learning, our method solves instances that are much larger than those in Kera (2311.12904).

**摘要翻译**:

在NeurIPS 2024上，Kera（2311.12904）提出了使用Transformer计算Groebner基的方法——Groebner基是计算代数中的核心对象，具有众多实际应用。本文通过应用层次化注意力Transformer（HATs）经由Groebner基计算来求解多元多项式方程组，改进了该方法。HAT架构引入了树结构归纳偏置，能够建模数据中存在的层次关系，从而相比传统的平坦注意力模型实现了显著的计算节省。我们将其推广到任意深度，并给出了详细的计算成本分析。结合课程学习，我们的方法能够求解远大于Kera（2311.12904）中实例规模的问题。

---

## 49. It's All Just Vectorization: einx, a Universal Notation for Tensor Operations

**一切皆向量化：einx，一种通用的张量运算表示法**

**OpenReview**: [https://openreview.net/forum?id=QqvQ3iAdpC](https://openreview.net/forum?id=QqvQ3iAdpC)

**Authors**: Florian Fervers (Fraunhofer IOSB), Sebastian Bullinger (Fraunhofer IOSB), Christoph Bodensteiner (Fraunhofer IOSB), Michael Arens

**Institutions**: Fraunhofer IOSB

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: Tensor notation, tensor programming, einx, einsum, einops

**TL;DR**: We introduce einx, a universal notation for tensor operations, and provide a Python implementation.

**TL;DR翻译**: 我们提出了einx，一种通用的张量运算表示法，并提供了Python实现。

**Abstract**:

Tensor operations represent a cornerstone of modern scientific computing. However, the Numpy-like notation adopted by predominant tensor frameworks is often difficult to read and write and prone to so-called shape errors, i.a., due to following inconsistent rules across a large, complex collection of operations. Alternatives like einsum and einops have gained popularity, but are inherently restricted to few operations and lack the generality required for a universal model of tensor programming.

To derive a better paradigm, we revisit vectorization as a function for transforming tensor operations, and use it to both lift lower-order operations to higher-order operations, and conceptually decompose higher-order operations to lower-order operations and their vectorization.

Building on the universal nature of vectorization, we introduce einx, a universal notation for tensor operations. It uses declarative, pointful expressions that are defined by analogy with loop notation and represent the vectorization of tensor operations. The notation reduces the large APIs of existing frameworks to a small set of elementary operations, applies consistent rules across all operations, and enables a clean, readable and writable representation in code. We provide an implementation of einx that is embedded in Python and integrates seamlessly with existing tensor frameworks: https://github.com/fferflo/einx

**摘要翻译**:

张量运算是现代科学计算的基石。然而，主流张量框架所采用的类Numpy表示法往往难以阅读和编写，且容易出现所谓的形状错误——这在很大程度上是因为大量复杂的运算之间遵循不一致的规则。einsum和einops等替代方案虽然日渐流行，但本质上仅限于少数运算，缺乏作为通用张量编程模型所需的通用性。

为了推导更优的范式，我们重新审视向量化作为张量运算变换函数的角色，并利用它将低阶运算提升为高阶运算，同时在概念上将高阶运算分解为低阶运算及其向量化。

基于向量化的通用性，我们提出了einx，一种通用的张量运算表示法。它使用声明式的、有指向的表达式，这些表达式类比循环表示法定义，代表张量运算的向量化。该表示法将现有框架的庞大API简化为一组基本运算，在所有运算上应用一致的规则，并在代码中实现简洁、可读且易于编写的表示。我们提供了einx的Python嵌入式实现，可与现有张量框架无缝集成：https://github.com/fferflo/einx

---

## 50. Fast training of accurate physics-informed neural networks without gradient descent

**无需梯度下降的高精度物理信息神经网络快速训练**

**OpenReview**: [https://openreview.net/forum?id=3VdSuh3sie](https://openreview.net/forum?id=3VdSuh3sie)

**Authors**: Chinmay Datar (Technische Universität München), Taniya Kapoor (Wageningen University & Research), Abhishek Chandra (KTH Royal Institute of Technology), Qing Sun (Technische Universität München), Erik Lien Bolager (Technische Universität München), Iryna Burak (Technische Universität München), Anna Veselovska (Technische Universität München), Massimo Fornasier (Technische Universität München), Felix Dietrich (Technical University Munich)

**Institutions**: Technische Universität München, Wageningen University & Research, KTH Royal Institute of Technology, Technical University Munich

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: physics-informed neural networks, extreme learning machines, random features, partial differential equations, optimization, training, causality, neural PDE solvers, optimization

**TL;DR**: Our approach - Frozen-PINNs addresses longstanding training and accuracy bottlenecks of Physics-Informed Neural Networks (PINNs) and makes PINNs highly realize high-precision, temporal causality, and extremely fast training.

**TL;DR翻译**: 我们的方法Frozen-PINNs解决了物理信息神经网络（PINNs）长期存在的训练和精度瓶颈，使PINNs实现了高精度、时间因果性和极快的训练速度。

**Abstract**:

Solving time-dependent Partial Differential Equations (PDEs) is one of the most critical problems in computational science. While Physics-Informed Neural Networks (PINNs) offer a promising framework for approximating PDE solutions, their accuracy and training speed are limited by two core barriers: gradient-descent-based iterative optimization over complex loss landscapes and non-causal treatment of time as an extra spatial dimension. We present Frozen-PINN, a novel PINN based on the principle of space-time separation that leverages random features instead of training with gradient descent, and incorporates temporal causality by construction. On nine PDE benchmarks, including challenges like extreme advection speeds, shocks, and high-dimensionality, Frozen-PINNs achieve superior training efficiency and accuracy over state-of-the-art PINNs, often by several orders of magnitude. Our work addresses longstanding training and accuracy bottlenecks of PINNs, delivering quickly trainable, highly accurate, and inherently causal PDE solvers, a combination that prior methods could not realize. Our approach challenges the reliance of PINNs on stochastic gradient-descent-based methods and specialized hardware, leading to a paradigm shift in PINN training and providing a challenging benchmark for the community.

**摘要翻译**:

求解含时偏微分方程（PDEs）是计算科学中最关键的问题之一。虽然物理信息神经网络（PINNs）为近似PDE解提供了一个有前景的框架，但其精度和训练速度受到两个核心障碍的制约：基于梯度下降的复杂损失曲面上的迭代优化，以及将时间作为额外空间维度的非因果处理方式。我们提出了Frozen-PINN，一种基于时空分离原理的新型PINN，它利用随机特征替代梯度下降训练，并在构造上天然融入了时间因果性。在九个PDE基准测试上——包括极端对流速度、激波和高维度等挑战——Frozen-PINNs相比最先进的PINNs在训练效率和精度上均取得了优势，通常提升达数个数量级。我们的工作解决了PINNs长期存在的训练和精度瓶颈，实现了训练快速、高精度且本质上具有因果性的PDE求解器——这是先前方法无法同时实现的组合。我们的方法挑战了PINNs对随机梯度下降方法和专用硬件的依赖，推动了PINN训练的范式转变，并为研究社区提供了一个具有挑战性的基准。

---

## 51. In-Place Test-Time Training

**原位测试时训练**

**OpenReview**: [https://openreview.net/forum?id=dTWfCLSoyl](https://openreview.net/forum?id=dTWfCLSoyl)

**Authors**: Guhao Feng (Peking University), Shengjie Luo (ByteDance Seed), Kai Hua, Ge Zhang (ByteDance Inc.), Wenhao Huang, Di He (Peking University), Tianle Cai (ByteDance Inc.)

**Institutions**: Peking University, ByteDance Seed, ByteDance Inc.

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Test-time Training, Large language model, LLM

**Abstract**:

The static "train then deploy" paradigm fundamentally limits Large Language Models (LLMs) from dynamically adapting their weights in response to continuous streams of new information inherent in real-world tasks. Test-Time Training (TTT) offers a compelling alternative by updating a subset of model parameters (fast weights) at inference time, yet its potential in the current LLM ecosystem is hindered by critical barriers including architectural incompatibility, computational inefficiency and misaligned fast weight objectives for language modeling. In this work, we introduce **In-Place Test-Time Training (In-Place TTT)**, a framework that seamlessly endows LLMs with Test-Time Training ability. In-Place TTT treats the final projection matrix of the ubiquitous MLP blocks as its adaptable fast weights, enabling a "drop-in" enhancement for LLMs without costly retraining from scratch. Furthermore, we replace TTT's generic reconstruction objective with a tailored, theoretically-grounded objective explicitly aligned with the Next-Token-Prediction task governing autoregressive language modeling. This principled objective, combined with an efficient chunk-wise update mechanism, results in a highly scalable algorithm compatible with context parallelism. Extensive experiments validate our framework's effectiveness: as an in-place enhancement, it enables a 4B-parameter model to achieve superior performance on tasks with contexts up to 128k, and when pretrained from scratch, it consistently outperforms competitive TTT-related approaches. Ablation study results further provide deeper insights on our design choices. Collectively, our results establish In-Place TTT as a promising step towards a paradigm of continual learning in LLMs.

**摘要翻译**:

静态的"先训练后部署"范式从根本上限制了大语言模型（LLMs）根据现实任务中持续不断的新信息流动态调整其权重的能力。测试时训练（TTT）通过在推理时更新模型参数的子集（快速权重）提供了一种有吸引力的替代方案，但其在当前LLM生态系统中的潜力受到架构不兼容、计算效率低下以及快速权重目标与语言建模不对齐等关键障碍的制约。在本工作中，我们提出了**原位测试时训练（In-Place TTT）**，一个能够无缝赋予LLMs测试时训练能力的框架。In-Place TTT将普遍存在的MLP模块的最终投影矩阵作为可适应的快速权重，实现了对LLMs的"即插即用"增强，无需从头进行昂贵的重新训练。此外，我们用一个定制的、有理论基础的目标函数替代了TTT的通用重建目标，该目标函数与支配自回归语言建模的下一个token预测任务显式对齐。这一原则性的目标函数结合高效的分块更新机制，产生了一个与上下文并行性兼容的高度可扩展算法。大量实验验证了我们框架的有效性：作为原位增强，它使一个4B参数模型在最长128k上下文的任务上取得了优越的性能；当从头预训练时，它一致性地优于有竞争力的TTT相关方法。消融实验结果进一步提供了对设计选择的深入理解。综合来看，我们的结果表明In-Place TTT是迈向LLMs持续学习范式的有前景的一步。

---

## 52. RAIN-Merging: A Gradient-Free Method to Enhance Instruction Following in Large Reasoning Models with Preserved Thinking Format

**RAIN-Merging：一种在保留思考格式的同时增强大推理模型指令遵循能力的无梯度方法**

**OpenReview**: [https://openreview.net/forum?id=PO2iULmu5e](https://openreview.net/forum?id=PO2iULmu5e)

**Authors**: Zhehao Huang (Shanghai Jiaotong University), Yuhang Liu (Shanghai Jiaotong University), Baijiong Lin (The Hong Kong University of Science and Technology (Guangzhou)), Yixin Lou (Shanghai Jiao Tong University), Zhengbao He (Shanghai Jiaotong University), Hanling Tian (Shanghai Jiaotong University), Tao Li (ByteDance Inc.), Xiaolin Huang (Shanghai Jiao Tong University)

**Institutions**: Shanghai Jiaotong University, The Hong Kong University of Science and Technology (Guangzhou), Shanghai Jiao Tong University, ByteDance Inc.

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Large Reasoning Model, Instruction Following, Model Merging, Null-Space

**Abstract**:

Large reasoning models (LRMs) excel at a long chain of reasoning but often fail to faithfully follow instructions regarding output format, constraints, or specific requirements. We investigate whether this gap can be closed by integrating an instruction-tuned model (ITM) into an LRM. Analyzing their differences in parameter space, namely task vectors, we find that their principal subspaces are nearly orthogonal across key modules, suggesting a lightweight merging with minimal interference. However, we also demonstrate that naïve merges are fragile because they overlook the output format mismatch between LRMs (with explicit *thinking* and *response* segments) and ITMs (answers-only). We introduce **RAIN-Merging** (Reasoning-Aware Instruction-attention guided Null-space projection Merging), a gradient-free method that integrates instruction following while preserving thinking format and reasoning performance. First, with a small reasoning calibration set, we project the ITM task vector onto the null space of forward features at thinking special tokens, which preserves the LRM's structured reasoning mechanisms. Second, using a small instruction calibration set, we estimate instruction attention to derive module-specific scaling that amplifies instruction-relevant components and suppresses leakage. Across four instruction-following benchmarks and nine reasoning & general capability benchmarks, RAIN-Merging substantially improves instruction adherence while maintaining reasoning quality. The gains are consistent across model scales and architectures, translating to improved performance in agent settings.

**摘要翻译**:

大推理模型（LRMs）擅长长链推理，但在忠实遵循输出格式、约束条件或特定要求方面的指令时往往表现不佳。我们研究了是否可以通过将指令微调模型（ITM）集成到LRM中来弥合这一差距。通过分析两者在参数空间中的差异（即任务向量），我们发现它们的主子空间在关键模块上几乎正交，这表明可以进行干扰极小的轻量级合并。然而，我们也证明了朴素的合并方式是脆弱的，因为它忽略了LRMs（具有显式的*思考*和*回答*部分）与ITMs（仅有回答）之间的输出格式不匹配。我们提出了**RAIN-Merging**（推理感知的指令注意力引导零空间投影合并），这是一种在保留思考格式和推理性能的同时整合指令遵循能力的无梯度方法。首先，利用小规模推理校准集，我们将ITM任务向量投影到思考特殊token处前向特征的零空间上，从而保留LRM的结构化推理机制。其次，利用小规模指令校准集，我们估计指令注意力以推导模块级别的缩放系数，从而放大与指令相关的分量并抑制泄漏。在四个指令遵循基准和九个推理与通用能力基准上，RAIN-Merging在保持推理质量的同时显著提升了指令遵循能力。这些提升在不同模型规模和架构上均保持一致，并可转化为智能体场景中的性能改进。

---

## 53. To Infinity and Beyond: Tool-Use Unlocks Length Generalization in State Space Models

**飞向无限：工具使用解锁状态空间模型的长度泛化能力**

**OpenReview**: [https://openreview.net/forum?id=sSfep4udCb](https://openreview.net/forum?id=sSfep4udCb)

**Authors**: Eran Malach (Apple), Omid Saremi (Apple), Sinead Williamson (Apple), Arwen Bradley (Apple), Aryo Lotfi (Apple), Emmanuel Abbe (Swiss Federal Institute of Technology Lausanne), Joshua M. Susskind (Apple), Etai Littwin (Apple)

**Institutions**: Apple, Swiss Federal Institute of Technology Lausanne

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: State Space Models, Mamba, Length Generalization, LLM, Transformers

**Abstract**:

State Space Models (SSMs) have become the leading alternative to Transformers for sequence modeling tasks. Their primary advantage is efficiency in long-context and long-form generation, enabled by fixed-size memory and linear scaling of computational complexity. We begin this work by showing a simple theoretical result stating that SSMs cannot accurately solve any "truly long-form" generation problem (in a sense we formally define), undermining their main competitive advantage. However, we show that this limitation can be mitigated by allowing SSMs interactive access to external tools. In fact, we show that given the right choice of tool access and problem-dependent training data, SSMs can learn to solve any tractable problem and generalize to arbitrary problem length/complexity (i.e., achieve length generalization). Following our theoretical finding, we demonstrate that tool-augmented SSMs achieve remarkable length generalization on a variety of arithmetic, reasoning, and coding tasks. These findings highlight SSMs as a potential efficient alternative to Transformers in interactive tool-based and agentic settings.

**摘要翻译**:

状态空间模型（SSMs）已成为序列建模任务中Transformers的主要替代方案。其核心优势在于长上下文和长文本生成中的高效性，这得益于固定大小的内存和线性扩展的计算复杂度。本文首先展示了一个简洁的理论结果：SSMs无法准确求解任何"真正的长文本"生成问题（我们对此进行了形式化定义），这从根本上削弱了其主要竞争优势。然而，我们证明了这一局限性可以通过赋予SSMs与外部工具的交互访问来缓解。事实上，我们表明，在适当选择工具访问方式和问题相关训练数据的条件下，SSMs可以学会求解任何可计算的问题，并泛化到任意的问题长度/复杂度（即实现长度泛化）。基于我们的理论发现，我们在多种算术、推理和编程任务上证明了工具增强的SSMs能够实现显著的长度泛化。这些发现凸显了SSMs作为Transformers在交互式工具使用和智能体场景中的潜在高效替代方案。

---

## 54. TileLang: Bridge Programmability and Performance in Modern Neural Kernels

**TileLang：在现代神经网络算子中连接可编程性与性能**

**OpenReview**: [https://openreview.net/forum?id=Jb1WkNSfUB](https://openreview.net/forum?id=Jb1WkNSfUB)

**Authors**: Lei Wang (Peking University), Yu Cheng (Peking University), Yining Shi (NVIDIA), Zhiwen Mo (Imperial College London), Zhengju Tang (Peking University), Wenhao Xie (Peking University), Tong Wu (Peking University), Lingxiao Ma (Microsoft Research), Yuqing Xia (Research, Microsoft), Jilong Xue (Microsoft Research), Fan Yang (Research, Microsoft), Zhi Yang (Peking University)

**Institutions**: Peking University, NVIDIA, Imperial College London, Microsoft Research

**Primary Area**: infrastructure, software libraries, hardware, systems, etc.

**Keywords**: compiler; AI; programming model

**TL;DR**: We introduce TileLang, a controllable programming system for fused neural kernels.

**TL;DR翻译**: 我们提出了TileLang，一种面向融合神经网络算子的可控编程系统。

**Abstract**:

Modern AI algorithms increasingly adopt fused kernels for performance, but implementing them remains complex due to the lack of fine-grained control in existing compilers like Triton. We introduce TileLang, a controllable programming system for fused neural kernels. TileLang provides explicit tile-level primitives for memory placement, data movement, and parallel scheduling. To guide developers in hardware-aware programming, the TileLang introduces two key techniques: tile inference which models tile programs as fused graphs and automatically deduces tile configuration from partial annotations; and tile recommendation that suggests efficient tile configurations based on hardware profiles and heuristics. TileLang makes it easy to express a wide range of fused attention kernels in under 80 lines of Python code, reducing code size by up to 90% compared to manual implementations. Evaluations show that TileLang achieves up to 5x speedup over Triton on NVIDIA H100 and up to 6 on AMD GPUs, demonstrating its ability to bridge programmability and performance.

**摘要翻译**:

现代AI算法越来越多地采用融合算子来提升性能，但由于现有编译器（如Triton）缺乏细粒度控制，实现融合算子仍然十分复杂。我们提出了TileLang，一种面向融合神经网络算子的可控编程系统。TileLang为内存放置、数据搬移和并行调度提供了显式的块级原语。为引导开发者进行硬件感知编程，TileLang引入了两项关键技术：块推断——将块程序建模为融合图并从部分标注中自动推导块配置；以及块推荐——基于硬件特性和启发式规则建议高效的块配置。TileLang能够用不到80行Python代码轻松表达各种融合注意力算子，相比手动实现代码量减少高达90%。评测表明，TileLang在NVIDIA H100上相比Triton实现了最高5倍加速，在AMD GPU上实现了最高6倍加速，展示了其在可编程性与性能之间架起桥梁的能力。

---

## 55. Navigating the Latent Space Dynamics of Neural Models

**探索神经模型的潜在空间动力学**

**OpenReview**: [https://openreview.net/forum?id=Zunww3FHPU](https://openreview.net/forum?id=Zunww3FHPU)

**Authors**: Marco Fumero (Institute of Science and Technology Austria(ISTA)), Luca Moschella (Apple), Emanuele Rodolà (Sapienza University of Rome), Francesco Locatello (Institute of Science and Technology)

**Institutions**: Institute of Science and Technology Austria(ISTA), Apple, Sapienza University of Rome, Institute of Science and Technology

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Representation learning, latent vector field, autoencoders, memorization and generalization, attractor

**Abstract**:

Neural networks transform high-dimensional data into compact, structured representations, often modeled as elements of a lower dimensional latent space. In this paper, we present an alternative interpretation of neural models as dynamical systems acting on the latent manifold. Specifically, we show that autoencoder models implicitly define a _latent vector field_ on the manifold, derived by iteratively applying the encoding-decoding map, without any additional training. We observe that standard training procedures introduce inductive biases that lead to the emergence of attractor points within this vector field.
Drawing on this insight, we propose to leverage the vector field as a _representation_ for the network, providing a novel tool to analyze the properties of the model and the data. This representation enables to: $(i)$ analyze the generalization and memorization regimes of neural models, even throughout training; $(ii)$ extract prior knowledge encoded in the network's parameters from the attractors, without requiring any input data; $(iii)$ identify out-of-distribution samples from their trajectories in the vector field.
We further validate our approach on vision foundation models, showcasing the applicability and effectiveness of our method in real-world scenarios.

**摘要翻译**:

神经网络将高维数据转换为紧凑的结构化表示，通常建模为低维潜在空间的元素。本文提出了一种将神经模型解释为作用在潜在流形上的动力系统的替代视角。具体而言，我们展示了自编码器模型通过迭代应用编码-解码映射，在无需额外训练的情况下隐式定义了流形上的_潜在向量场_。我们观察到，标准训练过程引入的归纳偏置会导致该向量场中吸引子的出现。

基于这一洞察，我们提出将向量场作为网络的一种_表示_，为分析模型和数据的性质提供了一种新工具。这种表示能够：$(i)$ 分析神经模型的泛化和记忆机制，甚至在整个训练过程中；$(ii)$ 从吸引子中提取编码在网络参数中的先验知识，而无需任何输入数据；$(iii)$ 通过样本在向量场中的轨迹识别分布外样本。

我们进一步在视觉基础模型上验证了我们的方法，展示了该方法在实际场景中的适用性和有效性。

---

## 56. Non-Asymptotic Analysis of (Sticky) Track-and-Stop

**(Sticky) Track-and-Stop的非渐近分析**

**OpenReview**: [https://openreview.net/forum?id=vebqP5aioj](https://openreview.net/forum?id=vebqP5aioj)

**Authors**: Riccardo Poiani (Bocconi University), Martino Bernasconi (Bocconi University), Andrea Celli (Bocconi University)

**Institutions**: Bocconi University

**Primary Area**: learning theory

**Keywords**: Multi-Armed Bandit Theory, Pure Exploration, Fixed-Confidence

**TL;DR**: We derive non-asymptotic guarantees for the Track-and-Stop and Sticky Track-and-Stop algorithms.

**TL;DR翻译**: 我们推导了Track-and-Stop和Sticky Track-and-Stop算法的非渐近保证。

**Abstract**:

In pure exploration problems, a statistician sequentially collects information to answer a question about some stochastic and unknown environment. The probability of returning a wrong answer should not exceed a maximum risk parameter $\delta$ and good algorithms make as few queries to the environment as possible. The Track-and-Stop algorithm is a pioneering method to solve these problems. Specifically, it is well-known that it enjoys asymptotic optimality sample complexity guarantees for $\delta \to 0$ whenever the map from the environment to its correct answers is single-valued (e.g., best-arm identification with a unique optimal arm). The Sticky Track-and-Stop algorithm extends these results to settings where, for each environment, there might exist multiple correct answers (e.g., $\epsilon$-optimal arm identification). Although both methods are optimal in the asymptotic regime, their non-asymptotic guarantees remain unknown. In this work, we fill this gap and provide non-asymptotic guarantees for both algorithms.

**摘要翻译**:

在纯探索问题中，统计学家通过序贯收集信息来回答关于某个随机且未知环境的问题。返回错误答案的概率不应超过最大风险参数$\delta$，而好的算法应尽可能减少对环境的查询次数。Track-and-Stop算法是解决此类问题的开创性方法。具体而言，众所周知，当从环境到其正确答案的映射是单值的（例如，具有唯一最优臂的最优臂识别）时，该算法在$\delta \to 0$时具有渐近最优的样本复杂度保证。Sticky Track-and-Stop算法将这些结果扩展到每个环境可能存在多个正确答案的场景（例如，$\epsilon$-最优臂识别）。尽管两种方法在渐近范围内都是最优的，但其非渐近保证仍然未知。本文填补了这一空白，为两种算法提供了非渐近保证。

---

## 57. The Shape of Adversarial Influence: Characterizing LLM Latent Spaces with Persistent Homology

**对抗性影响的形态：利用持久同调表征LLM潜空间**

**OpenReview**: [https://openreview.net/forum?id=v2PglvLLKT](https://openreview.net/forum?id=v2PglvLLKT)

**Authors**: Aideen Fay (Imperial College London), Inés García-Redondo (University of Fribourg), Qiquan Wang (Imperial College London), Haim Dubossarsky (Queen Mary University of London), Anthea Monod (Imperial College London)

**Institutions**: Imperial College London, University of Fribourg, Queen Mary University of London

**Primary Area**: interpretability and explainable AI

**Keywords**: Persistent Homology, Interpretability, Topological Data Analysis, Representation Geometry, Large Language Models, AI Security, Adversarial Attacks, Sparse Autoencoders

**TL;DR**: We use persistent homology to interpret how adversarial inputs reshape LLM representation spaces, resulting in a robust signature that provides multiscale, geometry-aware insights complementary to standard interpretability methods.

**TL;DR翻译**: 我们利用持久同调来解释对抗性输入如何重塑LLM表示空间，得到了一种鲁棒的拓扑签名，能够提供多尺度、几何感知的洞察，与标准可解释性方法形成互补。

**Abstract**:

Existing interpretability methods for Large Language Models (LLMs) often fall short by focusing on linear directions or isolated features, overlooking the high-dimensional, nonlinear, and relational geometry within model representations. This study focuses on how adversarial inputs systematically affect the internal representation spaces of LLMs, a topic which remains poorly understood. We propose the application of persistent homology (PH) to measure and understand the geometry and topology of the representation space when the model is under external adversarial influence. Specifically, we use PH to systematically interpret six state-of-the-art models under two distinct adversarial conditions—indirect prompt injection and backdoor fine-tuning—and uncover a consistent topological signature of adversarial influence. Across architectures and model sizes, adversarial inputs induce "topological compression'', where the latent space becomes structurally simpler, collapsing from varied, compact, small-scale features into fewer, dominant, and more dispersed large-scale ones. This topological signature is statistically robust across layers, highly discriminative, and provides interpretable insights into how adversarial effects emerge and propagate. By quantifying the shape of activations and neuron-level information flow, our architecture-agnostic framework reveals fundamental invariants of representational change, offering a complementary perspective to existing interpretability methods.

**摘要翻译**:

现有的大语言模型（LLM）可解释性方法往往聚焦于线性方向或孤立特征，忽视了模型表示中的高维、非线性和关系性几何结构，因而存在明显局限。本研究关注对抗性输入如何系统性地影响LLM的内部表示空间——这一课题目前仍知之甚少。我们提出将持久同调（PH）应用于度量和理解模型在外部对抗性影响下表示空间的几何与拓扑结构。具体而言，我们使用PH系统地解释了六个前沿模型在两种不同对抗条件——间接提示注入和后门微调——下的表现，揭示了一种一致的对抗性影响拓扑签名。跨架构和模型规模来看，对抗性输入诱发了“拓扑压缩”现象，即潜空间在结构上变得更简单，从多样、紧凑的小尺度特征坍缩为更少、更主导、更分散的大尺度特征。该拓扑签名在层间具有统计鲁棒性，高度可区分，并为理解对抗性效应如何产生和传播提供了可解释的洞察。通过量化激活形态和神经元级信息流，我们的架构无关框架揭示了表示变化的基本不变量，为现有可解释性方法提供了互补视角。

---

## 58. Hyperparameter Trajectory Inference with Conditional Lagrangian Optimal Transport

**基于条件拉格朗日最优传输的超参数轨迹推断**

**OpenReview**: [https://openreview.net/forum?id=P5B97gZwRb](https://openreview.net/forum?id=P5B97gZwRb)

**Authors**: Harry Amad (University of Cambridge), Mihaela van der Schaar (University of Cambridge)

**Institutions**: University of Cambridge

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: hyperparameter, optimal transport, trajectory inference, manifold learning, interpolation

**Abstract**:

Neural networks (NNs) often have critical behavioural trade-offs that are set at design time with hyperparameters—such as reward weighting in reinforcement learning or quantile targets in regression. 
Post-deployment, however, user preferences can evolve, making initially optimal settings undesirable, necessitating expensive retraining. 
To circumvent this, we introduce the task of Hyperparameter Trajectory Inference (HTI), to learn, from observed data, how a NN's conditional output distribution changes as a function of its hyperparameters, such that a surrogate model can approximate the NN at unobserved hyperparameter settings. 
HTI requires extending existing trajectory inference approaches to incorporate conditions, posing key challenges to ensure meaningful inferred conditional probability paths. 
We propose an approach grounded in conditional Lagrangian optimal transport theory, jointly learning the Lagrangian function governing hyperparameter-induced dynamics along with the associated optimal transport maps and geodesics, which form the surrogate model.
We incorporate inductive biases based on the manifold hypothesis and least-action principles into the learned Lagrangian, improving surrogate model feasibility.
We empirically demonstrate that our approach reconstructs NN behaviour across hyperparameter spectrums better than other alternatives, enabling effective inference-time adaptation of NNs.

**摘要翻译**:

神经网络常常在设计时通过超参数设定关键的行为权衡——例如强化学习中的奖励加权或回归中的分位数目标。然而在部署后，用户偏好可能会演变，使得最初的最优设置变得不再合适，从而需要进行昂贵的重新训练。为了规避这一问题，我们引入了超参数轨迹推断（HTI）任务，旨在从观测数据中学习神经网络的条件输出分布如何随超参数变化，使得代理模型能够在未观测的超参数设置下近似神经网络的行为。HTI需要将现有的轨迹推断方法扩展为条件形式，这带来了确保推断出有意义的条件概率路径的关键挑战。我们提出了一种基于条件拉格朗日最优传输理论的方法，联合学习控制超参数引起的动力学的拉格朗日函数以及相关的最优传输映射和测地线，由此构成代理模型。我们将基于流形假设和最小作用量原理的归纳偏置融入所学习的拉格朗日函数中，以提升代理模型的可行性。实证结果表明，我们的方法在跨超参数谱重建神经网络行为方面优于其他替代方案，实现了神经网络的有效推理时自适应。

---

## 59. Vid-LLM: A Compact Video-based 3D Multimodal LLM with Reconstruction–Reasoning Synergy

**Vid-LLM：具有重建-推理协同的紧凑型视频三维多模态大语言模型**

**OpenReview**: [https://openreview.net/forum?id=l1cLdEjESj](https://openreview.net/forum?id=l1cLdEjESj)

**Authors**: Haijier Chen (Wuhan University), Bo Xu (Wuhan University), Shoujian zhang (Wuhan University), Haoze Liu (Wuhan University), Jiaxuan Lin (Wuhan University), Jingrong Wang (Shenzhen University)

**Institutions**: Wuhan University, Shenzhen University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: video-based 3D MLLM, geometric priors, Cross-Task Adapter, Metric Depth calibration

**Abstract**:

Recent developments in Multimodal Large Language Models (MLLMs) have significantly improved Vision–Language (VL) reasoning in 2D domains. However, extending these capabilities to 3D scene understanding remains a major challenge. Existing 3D Multimodal Large Language Models (3D-MLLMs) often depend on 3D data inputs, which limits scalability and generalization. To address this limitation, we propose Vid-LLM, a video-based 3D-MLLM that directly processes video inputs without requiring external 3D data, making it practical for real-world deployment. In our method, the geometric prior are directly used to improve the performance of the sceen perception. To integrate the geometric cues into the MLLM compactly, we design a Cross-Task Adapter (CTA) module to align the 3D geometric priors with the vision-language representations. To ensure geometric consistency and integrity, we introduce a Metric Depth Model that recovers real-scale geometry from the reconstruction outputs. Finally, the model is fine-tuned with a two-stage distillation optimization strategy, realizing fast convergence and stabilizes training. Extensive experiments across diverse benchmarks verified the effectiveness of our method on 3D Question Answering, 3D Dense Captioning and  3D Visual Grounding tasks,  demonstrating the superior multi-task capabilities.

**摘要翻译**:

多模态大语言模型（MLLM）的最新发展显著提升了二维领域的视觉-语言（VL）推理能力。然而，将这些能力扩展到三维场景理解仍然是一个重大挑战。现有的三维多模态大语言模型（3D-MLLM）往往依赖三维数据输入，这限制了其可扩展性和泛化能力。为解决这一局限，我们提出了Vid-LLM，一种基于视频的3D-MLLM，直接处理视频输入而无需外部三维数据，使其适用于实际部署。在我们的方法中，几何先验被直接用于提升场景感知性能。为了紧凑地将几何线索整合到MLLM中，我们设计了跨任务适配器（CTA）模块，将三维几何先验与视觉-语言表示对齐。为确保几何一致性和完整性，我们引入了度量深度模型，从重建输出中恢复真实尺度的几何信息。最后，模型通过两阶段蒸馏优化策略进行微调，实现快速收敛并稳定训练过程。在多种基准测试上的广泛实验验证了我们方法在三维问答、三维密集描述和三维视觉定位任务上的有效性，展示了卓越的多任务能力。

---

## 60. From Markov to Laplace: How Mamba In-Context Learns Markov Chains

**从马尔可夫到拉普拉斯：Mamba如何上下文学习马尔可夫链**

**OpenReview**: [https://openreview.net/forum?id=kmK3WSCOCT](https://openreview.net/forum?id=kmK3WSCOCT)

**Authors**: Marco Bondaschi (EPFL - EPF Lausanne), Nived Rajaraman (University of California Berkeley), Xiuying Wei (EPFL - EPF Lausanne), Razvan Pascanu (Mila - Quebec Artificial Intelligence Institute), Caglar Gulcehre (Microsoft), Michael Gastpar (School of Computer and Communication Sciences, EPFL - EPF Lausanne), Ashok Vardhan Makkuva

**Institutions**: EPFL - EPF Lausanne, University of California Berkeley, Mila - Quebec Artificial Intelligence Institute, Microsoft, School of Computer and Communication Sciences, EPFL - EPF Lausanne

**Primary Area**: interpretability and explainable AI

**Keywords**: State-space models, Markov chains, In-context learning, Laplacian smoothing

**TL;DR**: We uncover an interesting phenomenon where a single-layer Mamba represents the Bayes optimal Laplacian smoothing estimator when trained on Markov chains and we demonstrate it theoretically and empirically.

**TL;DR翻译**: 我们揭示了一个有趣的现象：单层Mamba在上下文学习马尔可夫链时表示贝叶斯最优的拉普拉斯估计器，我们从理论和实验上对此进行了验证。

**Abstract**:

While transformer-based language models have driven the AI revolution thus far, their computational complexity has spurred growing interest in viable alternatives, such as structured state space sequence models (SSMs) and Selective SSMs. Among these, Mamba (S6) and its variant Mamba-2 have shown remarkable inference speed-ups over transformers while achieving comparable or superior performance on complex language modeling tasks. However, despite these architectural innovations and empirical successes, the fundamental learning capabilities of Mamba remain poorly understood. In this paper, we address this gap by studying in-context learning (ICL) on Markov chains and uncovering an interesting phenomenon: even a single-layer Mamba efficiently learns the in-context Laplacian smoothing estimator, which is both Bayes and minimax optimal. To explain this, we theoretically characterize the representation capacity of Mamba and reveal the fundamental role of convolution in enabling it to represent the optimal Laplacian smoothing. These theoretical insights align strongly with empirical results and, to the best of our knowledge, represent the first formal connection between Mamba and optimal statistical estimators. Finally, we outline promising research directions inspired by these findings.

**摘要翻译**:

虽然基于Transformer的语言模型迄今推动了AI革命，但其计算复杂性激发了人们对可行替代方案的日益关注，如结构化状态空间序列模型（SSM）和选择性SSM。其中，Mamba（S6）及其变体Mamba-2在推理速度上相比Transformer有显著提升，同时在复杂语言建模任务上取得了可比或更优的性能。然而，尽管取得了这些架构创新和实证成功，Mamba的基本学习能力仍然知之甚少。在本文中，我们通过研究马尔可夫链上的上下文学习（ICL）来弥补这一空白，并揭示了一个有趣的现象：即使是单层Mamba也能高效地学习上下文拉普拉斯平滑估计器，该估计器同时是贝叶斯最优和极小极大最优的。为解释这一现象，我们从理论上刻画了Mamba的表示能力，揭示了卷积在使其能够表示最优拉普拉斯平滑中的基础性作用。这些理论洞察与实证结果高度一致，据我们所知，这代表了Mamba与最优统计估计器之间的首次形式化联系。最后，我们概述了受这些发现启发的有前景的研究方向。

---

## 61. Huxley-G\"odel Machine: Human-Level Coding Agent Development by an Approximation of the Optimal Self-Improving Machine

**Huxley-Gödel机：通过最优自改进过程的近似实现人类水平的编码智能体开发**

**OpenReview**: [https://openreview.net/forum?id=T0EiEuhOOL](https://openreview.net/forum?id=T0EiEuhOOL)

**Authors**: Wenyi Wang (King Abdullah University of Science and Technology), Piotr Piękos (King Abdullah University of Science and Technology), Li Nanbo (King Abdullah University of Science and Technology), Firas Laakom (King Abdullah University of Science and Technology), Yimeng Chen (King Abdullah University of Science and Technology), Mateusz Ostaszewski, Mingchen Zhuge (King Abdullah University of Science and Technology), Jürgen Schmidhuber (King Abdullah University of Science and Technology)

**Institutions**: King Abdullah University of Science and Technology

**Primary Area**: transfer learning, meta learning, and lifelong learning

**Keywords**: Self-Improvement, Coding Agents, G\"odel Machine

**TL;DR**: We propose Huxley-G\"odel Machine, an algorithm guideing self-improvements following an estimation of the value function of G\"odel Machines.

**TL;DR翻译**: 我们提出了Huxley-Gödel机，一种根据对Gödel机价值函数的估计来指导自我改进的算法。

**Abstract**:

Recent studies operationalize self-improvement through coding agents that edit their own codebases, grow a tree of self-modifications through expansion strategies that favor higher software engineering benchmark performance, 
considering that this implies more promising subsequent self-modifications. However, we identify a mismatch between the agent’s self-improvement potential (metaproductivity) and its coding benchmark performance, namely the \emph{Metaproductivity-Performance~Mismatch}. Inspired by Huxley’s concept of clade, we propose a metric ($\mathrm{CMP}$) that aggregates the benchmark performances of the \emph{descendants} of an agent as an indicator of its potential for self-improvement. We show that the G\"odel Machine, the optimal self-improving machine, is achieved with access to true $\mathrm{CMP}$. We introduce the Huxley-G\"odel Machine (HGM), which, by estimating $\mathrm{CMP}$ and using it as guidance, searches the tree of self-modifications. On SWE-bench Verified and Polyglot, HGM outperforms prior self-improving coding agent search methods while using less wall-clock time. Moreover, the agent optimized by HGM on SWE-bench Verified outperforms SWE-agent, a leading human-engineered open source coding agent on SWE-bench Lite, where SWE-agent ranks the best on the official leaderboard, when both use the GPT-5-mini backbone, demonstrating that HGM self-improvement indeed enhances genuine coding capability.

**摘要翻译**:

近期的研究通过让编码智能体编辑自身代码库来实现自我改进，通过偏好软件工程基准性能更高的扩展策略来生长自我修改树，认为这意味着后续的自我修改更具前景。然而，我们发现了智能体的自我改进潜力（元生产力）与其编码基准性能之间的不匹配，即"元生产力-性能不匹配"问题。受赫胥黎的分支概念启发，我们提出了一种指标（CMP），通过聚合一个智能体后代的基准性能来作为其自我改进潜力的指标。我们证明，当能够获取真实的CMP时，可以实现Gödel机——即最优自改进机器。我们引入了Huxley-Gödel机（HGM），通过估计CMP并将其作为指导来搜索自我修改树。在SWE-bench Verified和Polyglot上，HGM在使用更少的计算时间的情况下优于先前的自改进编码智能体搜索方法。此外，当两者都使用GPT-5-mini后端时，由HGM在SWE-bench Verified上优化的智能体在SWE-bench Lite上超越了SWE-agent——一个在官方排行榜上排名最优的人类工程化开源编码智能体，证明了HGM的自我改进确实增强了真正的编码能力。

---

## 62. Gaia2: Benchmarking LLM Agents on Dynamic and  Asynchronous Environments

**Gaia2：在动态异步环境中对LLM智能体进行基准测试**

**OpenReview**: [https://openreview.net/forum?id=9gw03JpKK4](https://openreview.net/forum?id=9gw03JpKK4)

**Authors**: Romain Froger (Facebook), Pierre Andrews (Meta), Matteo Bettini (University of Cambridge), Amar Budhiraja (Facebook), Ricardo Silveira Cabral (Facebook), Virginie Do (Université Paris Dauphine - PSL), Emilien Garreau (Université Paris-Saclay), Jean-Baptiste Gaya (Facebook), Hugo Laurençon (Ecole Normale Superieure), Maxime Lecanu (Facebook), Kunal Malkan (Facebook), Dheeraj Mekala (University of California, San Diego), Pierre Menard (Ecole Normale Supérieure de Lyon), Gerard Moreno-Torres Bertran (Facebook), Ulyana Piterbarg (Google DeepMind), Mikhail Plekhanov (Facebook), Mathieu Rita (INRIA), Andrey Rusakov (Department of Computer Science, ETHZ - ETH Zurich), Vladislav Vorotilov (Independent), Mengjue Wang (Meta), Ian Yu (The New School), Amine Benhalloum (Ecole Nationale Supérieure de Techniques Avancées), Grégoire Mialon (Facebook), Thomas Scialom (LIP6)

**Institutions**: Facebook, Meta, University of Cambridge, Université Paris Dauphine - PSL, Université Paris-Saclay, Ecole Normale Superieure, University of California, San Diego, Ecole Normale Supérieure de Lyon, Google DeepMind, INRIA, Department of Computer Science, ETHZ - ETH Zurich, Independent, The New School, Ecole Nationale Supérieure de Techniques Avancées, LIP6

**Primary Area**: datasets and benchmarks

**Keywords**: benchmark, agents, rlvr, multi-agent systems, reasoning, large language models, evaluation, framework

**TL;DR**: Gaia2 evaluates LLM agents in asynchronous, dynamic environments with action-level verification, revealing fundamental trade-offs between reasoning, speed, and robustness.

**TL;DR翻译**: Gaia2在异步动态环境中评估LLM智能体，通过动作级验证揭示了推理、速度与鲁棒性之间的根本性权衡。

**Abstract**:

We introduce **Gaia2**, a benchmark for evaluating large language model agents in realistic, asynchronous environments. Unlike prior static or synchronous evaluations, Gaia2 introduces scenarios where environments evolve independently of agent actions, requiring agents to operate under temporal constraints, adapt to noisy and dynamic events, resolve ambiguity, and collaborate with other agents. Each scenario is paired with a write-action verifier, enabling fine-grained, action-level evaluation and making Gaia2 directly usable for reinforcement learning from verifiable rewards. Our evaluation of state-of-the-art proprietary and open-source models shows that no model dominates across capabilities: GPT-5 (high) reaches the strongest overall score of 42% pass@1 but fails on time-sensitive tasks, Claude-4 Sonnet trades accuracy and speed for cost, Kimi-K2 leads among open-source models with 21% pass@1. These results highlight fundamental trade-offs between reasoning, efficiency, robustness, and expose challenges in closing the “sim2real” gap. Gaia2 is built on a consumer environment with the open-source **Agents Research Environments** platform and designed to be easy to extend. By releasing Gaia2 alongside the foundational ARE framework, we aim to provide the community with a flexible infrastructure for developing, benchmarking, and training the next generation of practical agent systems.

**摘要翻译**:

我们提出了**Gaia2**，一个用于在真实异步环境中评估大语言模型智能体的基准测试。与以往的静态或同步评估不同，Gaia2引入了环境独立于智能体动作而自主演变的场景，要求智能体在时间约束下运行，适应嘈杂和动态的事件，消除歧义，并与其他智能体协作。每个场景配有一个写动作验证器，支持细粒度的动作级评估，使Gaia2可直接用于基于可验证奖励的强化学习。我们对最先进的闭源和开源模型的评估表明，没有任何模型在所有能力上占据主导地位：GPT-5 (high)以42% pass@1的成绩获得最高总分，但在时间敏感任务上表现不佳；Claude-4 Sonnet在准确性、速度和成本之间进行权衡；Kimi-K2以21% pass@1在开源模型中领先。这些结果凸显了推理、效率和鲁棒性之间的根本性权衡，并暴露了缩小"仿真到现实"差距方面的挑战。Gaia2基于消费级环境构建，使用开源的**Agents Research Environments**平台，设计上易于扩展。通过发布Gaia2及其基础ARE框架，我们旨在为社区提供灵活的基础设施，用于开发、基准测试和训练下一代实用智能体系统。

---

## 63. Fast Escape, Slow Convergence: Learning Dynamics of Phase Retrieval under Power-Law Data

**快速逃逸，缓慢收敛：幂律数据下相位恢复的学习动力学**

**OpenReview**: [https://openreview.net/forum?id=Ae4eZpkXBX](https://openreview.net/forum?id=Ae4eZpkXBX)

**Authors**: Guillaume Braun (RIKEN), Bruno Loureiro (Ecole Normale Supérieure, Ecole Normale Supérieure de Paris), Minh Ha Quang (RIKEN), Masaaki Imaizumi (Kyoto University)

**Institutions**: RIKEN, Ecole Normale Supérieure, Ecole Normale Supérieure de Paris, Kyoto University

**Primary Area**: learning theory

**Keywords**: scaling laws, gradient flow, power-law spectrum, phase retrieval, anisotropic data, learning dynamics

**Abstract**:

Scaling laws describe how learning performance improves with data, compute, or training time, and have become a central theme in modern deep learning. We study this phenomenon in a canonical nonlinear model: phase retrieval with anisotropic Gaussian inputs whose covariance spectrum follows a power law. Unlike the isotropic case, where dynamics collapse to a two-dimensional system, anisotropy yields a qualitatively new regime in which an infinite hierarchy of coupled equations governs the evolution of the summary statistics. We develop a tractable reduction that reveals a three-phase trajectory: (i) fast escape from low alignment, (ii) slow convergence of the summary statistics, and (iii) spectral-tail learning in low-variance directions. From this decomposition, we derive explicit scaling laws for the mean-squared error, showing how spectral decay dictates convergence times and error curves. Experiments confirm the predicted phases and exponents. These results provide the first rigorous characterization of scaling laws in nonlinear regression with anisotropic data, highlighting how anisotropy reshapes learning dynamics.

**摘要翻译**:

缩放定律描述了学习性能如何随数据、计算或训练时间而提升，已成为现代深度学习的核心主题。我们在一个典型的非线性模型中研究这一现象：具有各向异性高斯输入的相位恢复，其协方差谱遵循幂律分布。与各向同性情形中动力学坍缩为二维系统不同，各向异性产生了一个质性上全新的区间，其中一个无穷耦合方程层次控制着汇总统计量的演化。我们发展了一种可处理的约化方法，揭示了三阶段轨迹：（i）从低对齐状态快速逃逸，（ii）汇总统计量的缓慢收敛，以及（iii）低方差方向上的谱尾学习。基于这一分解，我们推导出均方误差的显式缩放定律，展示了谱衰减如何决定收敛时间和误差曲线。实验证实了所预测的阶段和指数。这些结果提供了各向异性数据下非线性回归中缩放定律的首个严格刻画，突显了各向异性如何重塑学习动力学。

---

## 64. AutoEP: LLMs-Driven Automation of Hyperparameter Evolution for Metaheuristic Algorithms

**AutoEP：LLM驱动的元启发式算法超参数进化自动化**

**OpenReview**: [https://openreview.net/forum?id=hit3hGBheP](https://openreview.net/forum?id=hit3hGBheP)

**Authors**: Zhenxing Xu (National University of Defense Technology), Yizhe Zhang (National University of Defense Technology), Weidong Bao (National University of Defense Technology), Hao Wang (National University of Defense Technology), Ming Chen (Tsinghua University, Tsinghua University), Haoran Ye (Peking University), Wenzheng Jiang (National University of Defense Technology), Hui Yan (National University of Defense Technology), Ji Wang (National University of Defense Technology)

**Institutions**: National University of Defense Technology, Tsinghua University, Tsinghua University, Peking University

**Primary Area**: optimization

**Keywords**: LLMs, Optimization, Metaheuristic algorithm, Automatic Algorithm Design

**Abstract**:

Dynamically configuring algorithm hyperparameters is a fundamental challenge in computational intelligence. While learning-based methods offer automation, they suffer from prohibitive sample complexity and poor generalization. We introduce AutoEP, a novel framework that bypasses training entirely by leveraging Large Language Models (LLMs) as zero-shot reasoning engines for algorithm control. AutoEP's core innovation lies in a tight synergy between two components: (1) an online Exploratory Landscape Analysis (ELA) module that provides real-time, quantitative feedback on the search dynamics, and (2) a multi-LLM reasoning chain that interprets this feedback to generate adaptive hyperparameter strategies. This approach grounds high-level reasoning in empirical data, mitigating hallucination. Evaluated on three distinct metaheuristics across diverse combinatorial optimization benchmarks, AutoEP consistently outperforms state-of-the-art tuners, including neural evolution and other LLM-based methods. Notably, our framework enables open-source models like Qwen3-30B to match the performance of GPT-4, demonstrating a powerful and accessible new paradigm for automated hyperparameter design.Our code is available at https://anonymous.4open.science/r/AutoEP-3E11.

**摘要翻译**:

动态配置算法超参数是计算智能中的一个基本挑战。虽然基于学习的方法提供了自动化能力，但它们存在样本复杂度过高和泛化能力差的问题。我们引入了AutoEP，一个新颖的框架，完全绕过训练，利用大语言模型（LLM）作为零样本推理引擎进行算法控制。AutoEP的核心创新在于两个组件之间的紧密协同：（1）在线探索性景观分析（ELA）模块，提供关于搜索动态的实时定量反馈；（2）多LLM推理链，解释该反馈以生成自适应的超参数策略。这种方法将高层推理建立在实证数据之上，缓解了幻觉问题。在三种不同的元启发式算法和多种组合优化基准上的评估表明，AutoEP持续优于最先进的调优器，包括神经进化和其他基于LLM的方法。值得注意的是，我们的框架使Qwen3-30B等开源模型能够匹配GPT-4的性能，展示了一种强大且易于使用的自动化超参数设计新范式。

---

## 65. On the Wasserstein Geodesic Principal Component Analysis of probability measures

**概率测度的Wasserstein测地线主成分分析**

**OpenReview**: [https://openreview.net/forum?id=OJupg4mDjS](https://openreview.net/forum?id=OJupg4mDjS)

**Authors**: Nina Vesseron (Ecole Nationale de la Statistique et de l'Administration Economique), Elsa Cazelles (Institut de Recherche en Informatique de Toulouse), Alice Le Brigant (Université Panthéon-Sorbonne (Paris I)), Klein (Université de Toulouse)

**Institutions**: Ecole Nationale de la Statistique et de l'Administration Economique, Institut de Recherche en Informatique de Toulouse, Université Panthéon-Sorbonne (Paris I), Université de Toulouse

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: wasserstein PCA, optimal transport, deep learning

**Abstract**:

This paper focuses on Geodesic Principal Component Analysis (GPCA) on a collection of probability distributions using the Otto-Wasserstein geometry. The goal is to identify geodesic curves in the space of probability measures that best capture the modes of variation of the underlying dataset. We first address the case of a collection of Gaussian distributions, and show how to lift the computations in the space of invertible linear maps. For the more general setting of absolutely continuous probability measures, we leverage a novel approach to parameterizing geodesics in Wasserstein space with neural networks. Finally, we compare to classical tangent PCA through various examples and provide illustrations on real-world datasets.

**摘要翻译**:

本文聚焦于利用Otto-Wasserstein几何对一组概率分布进行测地线主成分分析（GPCA）。目标是在概率测度空间中识别能够最佳捕捉底层数据集变异模式的测地线曲线。我们首先处理高斯分布集合的情形，展示了如何将计算提升到可逆线性映射空间中进行。对于更一般的绝对连续概率测度设置，我们利用一种新颖的方法，通过神经网络参数化Wasserstein空间中的测地线。最后，我们通过各种示例将该方法与经典的切空间PCA进行比较，并提供了在真实数据集上的实例展示。

---

## 66. Discount Model Search for Quality Diversity Optimization in High-Dimensional Measure Spaces

**高维度量空间中质量多样性优化的折扣模型搜索**

**OpenReview**: [https://openreview.net/forum?id=m6Hv0yZO3n](https://openreview.net/forum?id=m6Hv0yZO3n)

**Authors**: Bryon Tjanaka (University of Southern California), Henry Chen (University of Southern California), Matthew Christopher Fontaine (University of Southern California), Stefanos Nikolaidis (University of Southern California)

**Institutions**: University of Southern California

**Primary Area**: optimization

**Keywords**: quality diversity optimization, black-box optimization, derivative-free optimization, latent space exploration

**TL;DR**: We present a method that enhances exploration in quality diversity (QD) optimization and show how this method enables new applications for QD. Project page: https://discount-models.github.io/

**TL;DR翻译**: 我们提出了一种增强质量多样性（QD）优化探索能力的方法，并展示了该方法如何为QD开启新的应用场景。

**Abstract**:

Quality diversity (QD) optimization searches for a collection of solutions that optimize an objective while attaining diverse outputs of a user-specified, vector-valued measure function. Contemporary QD algorithms are typically limited to low-dimensional measures because high-dimensional measures are prone to distortion, where many solutions found by the QD algorithm map to similar measures. For example, the state-of-the-art CMA-MAE algorithm guides measure space exploration with a histogram in measure space that records so-called discount values. However, CMA-MAE stagnates in domains with high-dimensional measure spaces because solutions with similar measures fall into the same histogram cell and hence receive the same discount value. To address these limitations, we propose Discount Model Search (DMS), which guides exploration with a model that provides a smooth, continuous representation of discount values. In high-dimensional measure spaces, this model enables DMS to distinguish between solutions with similar measures and thus continue exploration. We show that DMS facilitates new capabilities for QD algorithms by introducing two new domains where the measure space is the high-dimensional space of images, which enables users to specify their desired measures by providing a dataset of images rather than hand-designing the measure function. Results in these domains and on high-dimensional benchmarks show that DMS outperforms CMA-MAE and other existing black-box QD algorithms.

**摘要翻译**:

质量多样性（QD）优化旨在搜索一组既优化目标函数又在用户指定的向量值度量函数输出上实现多样性的解集合。当前的QD算法通常局限于低维度量空间，因为高维度量容易产生扭曲，即QD算法找到的许多解映射到相似的度量值。例如，最先进的CMA-MAE算法通过度量空间中记录所谓折扣值的直方图来引导度量空间探索。然而，CMA-MAE在高维度量空间的领域中会停滞，因为具有相似度量的解落入同一直方图单元格中，因而获得相同的折扣值。为解决这些局限，我们提出了折扣模型搜索（DMS），通过提供折扣值的平滑、连续表示的模型来引导探索。在高维度量空间中，该模型使DMS能够区分具有相似度量的解，从而继续探索。我们展示了DMS为QD算法带来了新能力，引入了两个新领域，其中度量空间是高维图像空间，使用户能够通过提供图像数据集而非手动设计度量函数来指定所需的度量。在这些领域和高维基准测试上的结果表明，DMS优于CMA-MAE及其他现有的黑盒QD算法。

---

## 67. Decentralized Attention Fails Centralized Signals: Rethinking Transformers for Medical Time Series

**去中心化注意力无法捕捉集中信号：重新思考面向医学时间序列的Transformer**

**OpenReview**: [https://openreview.net/forum?id=oZJFY2BQt2](https://openreview.net/forum?id=oZJFY2BQt2)

**Authors**: Guoqi Yu, Juncheng Wang (The Hong Kong Polytechnic University), Chen Yang (Hong Kong Polytechnic University), Jing Qin (Hong Kong Polytechnic University), Angelica I Aviles-Rivero (Tsinghua University), Shujun Wang (Hong Kong Polytechnic University)

**Institutions**: The Hong Kong Polytechnic University, Hong Kong Polytechnic University, Tsinghua University

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: EEG, ECG, Deep learning, Transformer

**TL;DR**: We propose a centralized module to replace decentralized attention in Transformer for centralized medical time series like EEG and ECG.

**TL;DR翻译**: 我们提出了一种集中式模块来替代Transformer中的去中心化注意力，用于医学时间序列中的集中信号建模。

**Abstract**:

Accurate analysis of Medical time series (MedTS) data, such as Electroencephalography (EEG) and Electrocardiography (ECG), plays a pivotal role in healthcare applications, including the diagnosis of brain and heart diseases. MedTS data typically exhibits two critical patterns: **temporal dependencies** within individual channels and **channel dependencies** across multiple channels. While recent advances in deep learning have leveraged Transformer-based models to effectively capture temporal dependencies, they often struggle to model channel dependencies. This limitation stems from a structural mismatch: ***MedTS signals are inherently centralized, whereas the Transformer's attention is decentralized***, making it less effective at capturing global synchronization and unified waveform patterns. To bridge this gap, we propose **CoTAR** (Core Token Aggregation-Redistribution), a centralized MLP-based module tailored to replace the decentralized attention. Instead of allowing all tokens to interact directly, as in attention, CoTAR introduces a global core token that acts as a proxy to facilitate the inter-token interaction, thereby enforcing a centralized aggregation and redistribution strategy. This design not only better aligns with the centralized nature of MedTS signals but also reduces computational complexity from quadratic to linear. Experiments on five benchmarks validate the superiority of our method in both effectiveness and efficiency, achieving up to a **12.13%** improvement on the APAVA dataset, with merely 33% memory usage and 20% inference time compared to the previous state-of-the-art. Code and all training scripts are available in this [**Link**](https://github.com/Levi-Ackman/TeCh).

**摘要翻译**:

对脑电图（EEG）和心电图（ECG）等医学时间序列（MedTS）数据的准确分析在医疗应用中发挥着关键作用，包括脑部和心脏疾病的诊断。MedTS数据通常表现出两种关键模式：单个通道内的**时间依赖性**和多个通道间的**通道依赖性**。虽然深度学习的最新进展利用基于Transformer的模型有效捕获了时间依赖性，但它们往往难以建模通道依赖性。这一局限源于结构性不匹配：***MedTS信号本质上是集中式的，而Transformer的注意力机制是去中心化的***，使其在捕捉全局同步性和统一波形模式方面效果不佳。为弥合这一差距，我们提出了**CoTAR**（核心token聚合-再分配），一种专门设计用于替代去中心化注意力的集中式MLP模块。与注意力机制中所有token直接交互不同，CoTAR引入了一个全局核心token作为代理来促进token间交互，从而实施集中式聚合和再分配策略。这一设计不仅更好地契合了MedTS信号的集中式特性，还将计算复杂度从二次降低为线性。在五个基准测试上的实验验证了我们方法在效果和效率方面的优越性，在APAVA数据集上实现了高达**12.13%**的提升，同时仅使用了先前最优方法33%的内存和20%的推理时间。

---

## 68. Why Low-Precision Transformer Training Fails: An Analysis on Flash Attention

**低精度Transformer训练为何失败：基于Flash Attention的分析**

**OpenReview**: [https://openreview.net/forum?id=0jHyEKHDyx](https://openreview.net/forum?id=0jHyEKHDyx)

**Authors**: Haiquan Qiu (Tsinghua University, Tsinghua University), Quanming Yao (Tsinghua University)

**Institutions**: Tsinghua University, Tsinghua University, Tsinghua University

**Primary Area**: optimization

**Keywords**: low-precision training, transformer, attention

**TL;DR**: For the first time, we mechanistically explain why low-precision training with flash attention fails, identifying a vicious cycle of rounding errors and proposing a simple, effective fix.

**TL;DR翻译**: 我们首次从机制上解释了低精度Flash Attention训练失败的原因，识别了舍入误差的恶性循环，并提出了简单有效的修复方案。

**Abstract**:

The pursuit of computational efficiency has driven the adoption of low-precision formats for training transformer models. However, this progress is often hindered by notorious training instabilities. This paper provides the first mechanistic explanation for a long-standing and unresolved failure case where training with flash attention in low-precision settings leads to catastrophic loss explosion. Our in-depth analysis reveals that the failure is not a random artifact but caused by two intertwined phenomena: the emergence of similar low-rank representations within the attention mechanism and the compounding effect of biased rounding errors inherent in low-precision arithmetic. We demonstrate how these factors create a vicious cycle of error accumulation that corrupts weight updates, ultimately derailing the training dynamics. To validate our findings, we introduce a minimal modification to the flash attention that mitigates the bias in rounding errors. This simple change stabilizes the training process, confirming our analysis and offering a practical solution to this persistent problem. Code is available at https://github.com/ucker/why-low-precision-training-fails.

**摘要翻译**:

追求计算效率推动了低精度格式在Transformer模型训练中的采用。然而，这一进展常常受到训练不稳定性的困扰。本文首次从机制上解释了一个长期存在且未解决的失败案例：在低精度设置下使用Flash Attention进行训练会导致灾难性的损失爆炸。我们的深入分析揭示，这一失败并非随机现象，而是由两个交织的现象导致：注意力机制内相似低秩表示的出现，以及低精度算术固有的有偏舍入误差的复合效应。我们展示了这些因素如何创建一个误差累积的恶性循环，损坏权重更新，最终使训练动态脱轨。为验证我们的发现，我们引入了对Flash Attention的最小修改以缓解舍入误差中的偏差。这一简单的改变稳定了训练过程，证实了我们的分析并为这一顽固问题提供了实用的解决方案。

---

## 69. Overcoming Joint Intractability with Lossless Hierarchical Speculative Decoding

**克服联合不可解性：无损层次化推测解码**

**OpenReview**: [https://openreview.net/forum?id=LaVrNaBNwM](https://openreview.net/forum?id=LaVrNaBNwM)

**Authors**: Yuxuan Zhou (Universität Mannheim), Fei Huang (Alibaba Group US), Heng Li (Carnegie Mellon University), Fengyi Wu, Tianyu Wang (Georgia Institute of Technology), jianwei zhang (Alibaba Group), Junyang Lin (Alibaba Group), Zhi-Qi Cheng (University of Washington)

**Institutions**: Universität Mannheim, Alibaba Group US, Carnegie Mellon University, Georgia Institute of Technology, Alibaba Group, University of Washington

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Speculative Decoding, Joint Intractability, Lossless Verification

**Abstract**:

Verification is a key bottleneck in improving inference speed while maintaining distribution fidelity in Speculative Decoding. Recent work has shown that sequence-level verification leads to a higher number of accepted tokens compared to token-wise verification. However, existing solutions often rely on surrogate approximations or are constrained by partial information, struggling with joint intractability. In this work, we propose Hierarchical Speculative Decoding (HSD), a provably lossless verification method that significantly boosts the expected number of accepted tokens and overcomes joint intractability by balancing excess and deficient mass across accessible branches. Through extensive large-scale experiments, we show that HSD consistently improves acceptance rates, especially with longer draft sequences. Its strong explainability and generality further highlight the potential for integration into a wide range of speculative decoding frameworks.

**摘要翻译**:

验证是在提升推理速度的同时保持分布保真度的推测解码中的关键瓶颈。近期工作表明，序列级验证比逐token验证能接受更多的token。然而，现有解决方案往往依赖于替代近似或受限于部分信息，难以处理联合不可解性问题。在本工作中，我们提出了层次化推测解码（HSD），一种可证明无损的验证方法，通过在可访问分支间平衡过剩和不足的概率质量来显著提升接受token的期望数量并克服联合不可解性。通过大量的大规模实验，我们展示了HSD持续提升接受率，尤其在较长的草稿序列下效果更为显著。其强可解释性和通用性进一步凸显了将其集成到各种推测解码框架中的潜力。

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

---

## 71. What's In My Human Feedback? Learning Interpretable Descriptions of Preference Data

**我的人类反馈中有什么？学习偏好数据的可解释描述**

**OpenReview**: [https://openreview.net/forum?id=sC6A1bFDUt](https://openreview.net/forum?id=sC6A1bFDUt)

**Authors**: Rajiv Movva (University of California, Berkeley), Smitha Milli (Meta FAIR), Sewon Min (University of California, Berkeley), Emma Pierson (University of California, Berkeley)

**Institutions**: University of California, Berkeley, Meta FAIR

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: rlhf, explaining datasets, interpretability, reward modeling, personalization

**TL;DR**: We present WIMHF, a method to describe the preferences encoded by human feedback; produce insights from seven widely-used datasets; and show that the method enables new approaches to data curation and personalization.

**TL;DR翻译**: 我们提出了WIMHF，一种描述人类反馈所编码偏好的方法；从七个广泛使用的数据集中生成洞察；并展示了该方法如何实现数据策划和个性化的新方法。

**Abstract**:

Preference data is widely used for aligning language models, but remains largely opaque. While prior work has studied specific aspects of annotator preference (e.g., length or sycophancy), automatically inferring preferences without pre-specifying hypotheses remains challenging. We introduce *What's In My Human Feedback* (WIMHF), a method that produces human-interpretable, natural language features from preference data using sparse autoencoders. We show that a sparse set of interpretable features can account for two-thirds of the preference signal achieved by black-box models. Applying WIMHF to 7 widely-used datasets, we precisely characterize both (1) which preferences are even possible to measure from each dataset and (2) which preferences humans actually display. WIMHF surfaces preferences that are unintentional or even actively harmful, like a preference for toxic outputs in Chatbot Arena. We show how these findings enable *interpretable data curation*: re-labeling the examples that contain the harmful preference yields large safety gains (+37%) with no cost to general performance. We also demonstrate a new approach to *personalization*: on the Community Alignment dataset, we identify preferences that are subjective across annotators, and use the features as interpretable knobs to adjust model behavior along these axes.

**摘要翻译**:

偏好数据被广泛用于对齐语言模型，但其内容在很大程度上仍不透明。虽然先前的工作研究了标注者偏好的特定方面（如长度或谄媚），但在不预先指定假设的情况下自动推断偏好仍然具有挑战性。我们引入了*What's In My Human Feedback*（WIMHF），一种利用稀疏自编码器从偏好数据中生成人类可解释的自然语言特征的方法。我们展示了一组稀疏的可解释特征能够解释黑盒模型所实现的偏好信号的三分之二。将WIMHF应用于7个广泛使用的数据集，我们精确刻画了（1）从每个数据集中甚至可以测量哪些偏好，以及（2）人类实际表现出哪些偏好。WIMHF发现了一些无意甚至有害的偏好，例如Chatbot Arena中对有毒输出的偏好。我们展示了这些发现如何实现*可解释的数据策划*：对包含有害偏好的样本进行重新标注可带来显著的安全提升（+37%），而不影响整体性能。我们还展示了一种新的*个性化*方法：在Community Alignment数据集上，我们识别了标注者间具有主观性的偏好，并使用这些特征作为可解释的旋钮来沿着这些轴调整模型行为。

---

## 72. SimuHome: A Temporal- and Environment-Aware Benchmark for Smart Home LLM Agents

**SimuHome：面向智能家居LLM智能体的时间与环境感知基准测试**

**OpenReview**: [https://openreview.net/forum?id=LCS1WsGvha](https://openreview.net/forum?id=LCS1WsGvha)

**Authors**: Gyuhyeon Seo (Seoul National University), Jungwoo Yang (Seoul National University), Junseong Pyo (Hanyang Universty), Nalim Kim (Pohang University of Science and Technology), Jonggeun Lee (Seoul National University), Yohan Jo (Seoul National University)

**Institutions**: Seoul National University, Hanyang Universty, Pohang University of Science and Technology

**Primary Area**: datasets and benchmarks

**Keywords**: smart home, simulator, language model, language agent, benchmark

**Abstract**:

Large Language Model (LLM) agents excel at multi-step, tool-augmented tasks. However, smart homes introduce distinct challenges, requiring agents to handle latent user intents, temporal dependencies, device constraints, scheduling, and more.
The main bottlenecks for developing smart home agents with such capabilities include the lack of a realistic simulation environment where agents can interact with devices and observe the results, as well as a challenging benchmark to evaluate them.
To address this, we introduce $\textbf{SimuHome}$, a time-accelerated home environment that simulates smart devices, supports API calls, and reflects changes in environmental variables.
By building the simulator on the Matter protocol, the global industry standard for smart home communication, SimuHome provides a high-fidelity environment, and agents validated in SimuHome can be deployed on real Matter-compliant devices with minimal adaptation.
We provide a challenging benchmark of 600 episodes across twelve user query types that require the aforementioned capabilities.
Our evaluation of 16 agents under a unified ReAct framework reveals distinct capabilities and limitations across models. Models under 7B parameters exhibited negligible performance across all query types. Even GPT-4.1, the best-performing standard model, struggled with implicit intent inference, state verification, and particularly temporal scheduling. While reasoning models such as GPT-5.1 consistently outperformed standard models on every query type, they required over three times the average inference time, which can be prohibitive for real-time smart home applications. This highlights a critical trade-off between task performance and real-world practicality. We will release our code and dataset upon publication of the paper.

**摘要翻译**:

大语言模型（LLM）智能体擅长多步骤的工具增强任务。然而，智能家居引入了独特的挑战，要求智能体处理潜在的用户意图、时间依赖性、设备约束、调度等问题。开发具备此类能力的智能家居智能体的主要瓶颈包括：缺乏智能体能够与设备交互并观察结果的真实模拟环境，以及缺乏具有挑战性的评估基准。为此，我们引入了**SimuHome**，一个时间加速的家居环境，能够模拟智能设备、支持API调用，并反映环境变量的变化。通过在全球智能家居通信行业标准Matter协议上构建模拟器，SimuHome提供了高保真环境，在SimuHome中验证的智能体可以以最小的适配成本部署到真实的Matter兼容设备上。我们提供了一个包含600个场景的挑战性基准测试，涵盖12种用户查询类型，需要上述能力。我们在统一的ReAct框架下对16个智能体进行的评估揭示了不同模型的能力和局限。参数低于7B的模型在所有查询类型上表现几乎可以忽略。即使是表现最好的标准模型GPT-4.1，在隐式意图推理、状态验证尤其是时间调度方面也表现困难。虽然GPT-5.1等推理模型在每种查询类型上都稳定优于标准模型，但其平均推理时间超过三倍，这对实时智能家居应用可能过于昂贵。这凸显了任务性能与实际可用性之间的关键权衡。

---

## 73. Reasoning with Sampling: Your Base Model is Smarter Than You Think

**采样推理：你的基础模型比你想象的更聪明**

**OpenReview**: [https://openreview.net/forum?id=Vsgq2ldr4K](https://openreview.net/forum?id=Vsgq2ldr4K)

**Authors**: Aayush Karan (Harvard University), Yilun Du (Google)

**Institutions**: Harvard University, Google

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLMs, reasoning, MCMC, sampling, inference-time compute

**TL;DR**: We find a training-free sampling algorithm that achieves reasoning boosts on base models comparable to those obtained by RL techniques.

**TL;DR翻译**: 我们发现了一种无需训练的采样算法，在基础模型上实现了与RL技术相当的推理能力提升。

**Abstract**:

Frontier reasoning models have exhibited incredible capabilities across a wide array of disciplines, driven by posttraining large language models (LLMs) with reinforcement learning (RL). However, despite the widespread success of this paradigm, much of the literature has been devoted to disentangling truly novel behaviors that emerge during RL but are not present in the base models. In our work, we approach this question from a different angle, instead asking whether comparable reasoning capabilities can be elicited from base models at inference time by pure sampling, without any additional training. Inspired by Markov chain Monte Carlo (MCMC) techniques for sampling from sharpened distributions, we propose a simple iterative sampling algorithm leveraging the base models' own likelihoods. Over different base models, we show that our algorithm offers substantial boosts in reasoning that nearly match and even outperform those from RL on a wide variety of single-shot tasks, including MATH500, HumanEval, and GPQA. Moreover, our sampler avoids the collapse in diversity over multiple samples that is characteristic of RL-posttraining. Crucially, our method does not require training, curated datasets, or a verifier, suggesting broad applicability beyond easily verifiable domains.

**摘要翻译**:

前沿推理模型在众多学科中展现了惊人的能力，这得益于通过强化学习（RL）对大语言模型（LLM）进行后训练。然而，尽管这一范式取得了广泛成功，大量文献致力于分辨哪些行为是在RL期间真正涌现的新行为，而非基础模型中已有的能力。在我们的工作中，我们从不同角度探讨这个问题，转而追问：是否可以在推理时通过纯采样从基础模型中引出可比的推理能力，而无需任何额外训练。受马尔可夫链蒙特卡洛（MCMC）从锐化分布中采样技术的启发，我们提出了一种利用基础模型自身似然度的简单迭代采样算法。在不同的基础模型上，我们展示了该算法在广泛的单次任务上提供了可观的推理提升，几乎匹配甚至超越了RL带来的提升，包括MATH500、HumanEval和GPQA。此外，我们的采样器避免了RL后训练中特有的多样本多样性坍缩问题。关键的是，我们的方法不需要训练、精选数据集或验证器，表明其在易于验证的领域之外也具有广泛的适用性。

---

## 74. Learning to Segment for Vehicle Routing Problems

**学习分割以求解车辆路径问题**

**OpenReview**: [https://openreview.net/forum?id=pN261iTKvr](https://openreview.net/forum?id=pN261iTKvr)

**Authors**: Wenbin Ouyang (Massachusetts Institute of Technology), Sirui Li (Microsoft Research), Yining Ma (Massachusetts Institute of Technology), Cathy Wu (Massachusetts Institute of Technology)

**Institutions**: Massachusetts Institute of Technology, Microsoft Research

**Primary Area**: optimization

**Keywords**: Learning-Guided Optimization, Vehicle Routing Problem

**Abstract**:

Iterative heuristics are widely recognized as state-of-the-art for Vehicle Routing Problems (VRPs). In this work, we exploit a critical observation: a large portion of the solution remains stable, i.e., unchanged across search iterations, causing redundant computations, especially for large-scale VRPs with long subtours. To address this, we pioneer the formal study of the First-Segment-Then-Aggregate
(FSTA) decomposition technique to accelerate iterative solvers. FSTA preserves stable solution segments during the search, aggregates nodes within each segment into fixed hypernodes, and focuses the search only on unstable portions. Yet, a key challenge lies in identifying which segments should be aggregated. To this end, we introduce Learning-to-Segment (L2Seg), a novel neural framework to intelligently
differentiate potentially stable and unstable portions for FSTA decomposition. We present three L2Seg variants: non-autoregressive (globally comprehensive but locally indiscriminate), autoregressive (locally refined but globally deficient), and their synergy. Empirical results on CVRP and VRPTW show that L2Seg accelerates state-of-the-art solvers by 2x to 7x. We further provide in-depth analysis showing why synergy achieves the best performance. Notably, L2Seg is compatible with traditional, learning-based, and hybrid solvers, while supporting various VRPs.

**摘要翻译**:

迭代启发式算法被广泛认为是车辆路径问题（VRP）的最先进方法。在本工作中，我们利用了一个关键观察：解的很大一部分在搜索迭代中保持稳定（即不变），导致冗余计算，尤其对于具有长子路径的大规模VRP。为了解决这一问题，我们开创性地对”先分割再聚合”（FSTA）分解技术进行了形式化研究，以加速迭代求解器。FSTA在搜索过程中保留稳定的解段，将每个段内的节点聚合为固定的超节点，并仅在不稳定部分上集中搜索。然而，一个关键挑战在于识别哪些段应该被聚合。为此，我们引入了学习分割（L2Seg），一个新颖的神经框架，用于智能区分FSTA分解中潜在稳定和不稳定的部分。我们提出了三种L2Seg变体：非自回归（全局全面但局部无差别）、自回归（局部精细但全局不足），以及两者的协同。在CVRP和VRPTW上的实证结果表明，L2Seg将最先进的求解器加速了2到7倍。我们进一步提供了深入分析，说明为何协同方案取得了最佳性能。值得注意的是，L2Seg兼容传统、基于学习的和混合求解器，同时支持多种VRP变体。

---

## 75. WAVE: Learning Unified & Versatile Audio-Visual Embeddings with Multimodal LLM

**WAVE：利用多模态LLM学习统一且多功能的音视频嵌入**

**OpenReview**: [https://openreview.net/forum?id=MiV3WXDYJb](https://openreview.net/forum?id=MiV3WXDYJb)

**Authors**: Changli Tang (Tsinghua University, Tsinghua University), Qinfan Xiao (Tsinghua University), Ke Mei (Tencent), Tianyi Wang (Tencent WeChat), Fengyun Rao (WeChat Vision, Tencent Inc.), Chao Zhang (Tsinghua University)

**Institutions**: Tsinghua University, Tsinghua University, Tsinghua University, Tencent, Tencent WeChat, WeChat Vision, Tencent Inc.

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: audio-visual embeddings, multimodal LLMs, video retrieval

**TL;DR**: This paper builds a versatile audio-visual embedding LLM, which can not only achieve any-to-any retrieval but also generate prompt-aware embeddings.

**TL;DR翻译**: 本文构建了一个多功能的音视频嵌入LLM，不仅可以实现任意模态间的检索，还能生成提示感知的嵌入。

**Abstract**:

While embeddings from multimodal large language models (LLMs) excel as general-purpose representations, their application to dynamic modalities like audio and video remains underexplored. We introduce WAVE (\textbf{u}nified \& \textbf{v}ersatile \textbf{a}udio-\textbf{v}isual \textbf{e}mbeddings), the first LLM-based embedding that creates a unified representation space for text, audio, and video modalities. WAVE employs a novel hierarchical feature fusion strategy and a joint multi-modal, multi-task training approach to enable two key capabilities: any-to-any cross-modal retrieval and the generation of prompt-aware embeddings tailored to user instructions. Experimentally, WAVE sets a new state-of-the-art on the MMEB-v2 video benchmark and achieves superior results in audio and video-to-audio retrieval. Its prompt-aware nature also yields remarkable performance in multimodal question answering, significantly outperforming existing embedding models. Ablation studies validate our joint training strategy, demonstrating improved performance across all modalities.  With a newly introduced benchmark for versatile audio-visual learning, WAVE opens up broad possibilities for cross-modal, any-to-any applications. Our code and checkpoints are released at \href{https://github.com/TCL606/WAVE}{https://github.com/TCL606/WAVE}.

**摘要翻译**:

虽然多模态大语言模型（LLM）的嵌入作为通用表示表现出色，但其在音频和视频等动态模态上的应用仍未得到充分探索。我们引入了WAVE（统一且多功能的音视频嵌入），这是首个基于LLM的嵌入方法，为文本、音频和视频模态创建统一的表示空间。WAVE采用新颖的层次化特征融合策略和联合多模态多任务训练方法，以实现两项关键能力：任意跨模态检索和根据用户指令定制的提示感知嵌入生成。在实验方面，WAVE在MMEB-v2视频基准测试上创造了新的最优结果，并在音频和视频到音频检索方面取得了卓越成绩。其提示感知特性还在多模态问答中展现了出色的性能，显著优于现有的嵌入模型。消融研究验证了我们的联合训练策略，展示了跨所有模态的性能提升。通过新引入的多功能音视频学习基准测试，WAVE为跨模态的任意到任意应用开辟了广阔的可能性。

---

## 76. mCLM: A Modular Chemical Language Model that Generates Functional and Makeable Molecules

**mCLM：一种生成功能性且可合成分子的模块化化学语言模型**

**OpenReview**: [https://openreview.net/forum?id=r2HG3xOMJI](https://openreview.net/forum?id=r2HG3xOMJI)

**Authors**: Carl Edwards (Genentech), Chi Han (University of Illinois, Urbana Champaign), Gawon Lee (University of Illinois at Urbana-Champaign), Thao Nguyen (University of Illinois at Urbana-Champaign), Sara Szymkuć (Allchemy Inc), Chetan Kumar Prasad (University of Illinois at Urbana-Champaign), Bowen Jin (University of Illinois at Urbana-Champaign), Jiawei Han (University of Illinois at Urbana-Champaign (UIUC)), Ying Diao (University of Illinois at Urbana-Champaign), Ge Liu (University of Illinois at Urbana-Champaign), Hao Peng (University of Illinois Urbana-Champaign), Bartosz Andrzej Grzybowski (Ulsan National Institute of Science and Technology), Martin D. Burke (University of Illinois at Urbana-Champaign), Heng Ji (University of Illinois, Urbana-Champaign)

**Institutions**: Genentech, University of Illinois, Urbana Champaign, University of Illinois at Urbana-Champaign, Allchemy Inc, University of Illinois at Urbana-Champaign (UIUC), University of Illinois Urbana-Champaign, Ulsan National Institute of Science and Technology, University of Illinois, Urbana-Champaign

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: molecule-language multimodality, language model, molecule tokenization, molecule generation

**TL;DR**: We propose mCLM: a bilingual, modular Chemical-Language Model that understands both natural language descriptions of functions and molecular blocks; mCLM front-loads synthesizability while improving the functions of molecules in a principled manner.

**TL;DR翻译**: 我们提出了mCLM：一种双语的模块化化学语言模型，能够理解功能的自然语言描述和分子构建块；mCLM前置考虑可合成性，同时以有原则的方式改进分子的功能。

**Abstract**:

Despite their ability to understand chemical knowledge, large language models (LLMs) remain limited in their capacity to propose novel molecules with desired functions (e.g., drug-like properties). In addition, the molecules that LLMs propose can often be challenging to make, and are almost never compatible with automated synthesis approaches. To better enable the discovery of functional small molecules, LLMs need to learn a new molecular language that is more effective in predicting properties and inherently synced with automated synthesis technology. Current molecule LLMs are limited by representing molecules based on atoms. In this paper, we argue that just like tokenizing texts into meaning-bearing (sub-)word tokens instead of characters, molecules should be tokenized at the level of functional building blocks, i.e., parts of molecules that bring unique functions and serve as effective building blocks for real-world automated laboratory synthesis. This motivates us to propose mCLM, a modular Chemical-Language Model that comprises a bilingual language model that understands both natural language descriptions of functions and molecular blocks. mCLM front-loads synthesizability considerations while improving the predicted functions of molecules in a principled manner. Experiments on 430 FDA-approved drugs showed that mCLM is capable of significantly improving chemical functions critical to determining drug potentials. mCLM, with only 3B parameters, also achieves improvements in synthetic accessibility relative to 7 other leading generative AI methods including GPT-5. When tested on 122 out-of-distribution medicines using only building blocks/tokens that are compatible with automated modular synthesis, mCLM outperforms all baselines in property scores and synthetic accessibility. mCLM can also reason on multiple functions and iteratively self-improve to rescue drug candidates that failed late in clinical trials (“fallen angels”).

**摘要翻译**:

尽管大语言模型（LLM）能够理解化学知识，但在提出具有所需功能（如类药性质）的新分子方面仍然能力有限。此外，LLM提出的分子往往难以合成，且几乎从不兼容自动化合成方法。为了更好地推动功能性小分子的发现，LLM需要学习一种新的分子语言，该语言能更有效地预测性质，并与自动化合成技术天然同步。当前的分子LLM受限于基于原子的分子表示。在本文中，我们认为，正如文本被分词为有意义的（子）词token而非字符一样，分子也应在功能构建块的层面进行分词——即分子中带来独特功能并作为真实世界自动化实验室合成有效构建块的部分。这促使我们提出了mCLM，一种模块化化学语言模型，包含一个能够理解功能自然语言描述和分子构建块的双语语言模型。mCLM前置考虑可合成性，同时以有原则的方式改进分子的预测功能。在430种FDA批准药物上的实验表明，mCLM能够显著改善决定药物潜力的关键化学功能。仅有3B参数的mCLM在合成可及性方面也优于包括GPT-5在内的7种其他领先生成式AI方法。在使用仅兼容自动化模块合成的构建块/token对122种分布外药物进行测试时，mCLM在属性得分和合成可及性方面均优于所有基线。mCLM还能对多种功能进行推理，并通过迭代自我改进来挽救在临床试验后期失败的候选药物（"折翼天使"）。

---

## 77. Seeing Through the Brain: New Insights from Decoding Visual Stimuli with fMRI

**透过大脑看世界：从fMRI解码视觉刺激的新洞察**

**OpenReview**: [https://openreview.net/forum?id=88ZLp7xYxw](https://openreview.net/forum?id=88ZLp7xYxw)

**Authors**: Zheng Huang, Enpei Zhang (Dartmouth College), Yinghao Cai (Dartmouth College), Weikang Qiu, Carl Yang (Emory University), Elynn Chen (New York University), Xiang Zhang (University of North Carolina at Charlotte), Rex Ying (Yale University), Dawei Zhou (Virginia Polytechnic Institute and State University), Yujun Yan (Dartmouth College)

**Institutions**: Dartmouth College, Emory University, New York University, University of North Carolina at Charlotte, Yale University, Virginia Polytechnic Institute and State University

**Primary Area**: applications to neuroscience & cognitive science

**Keywords**: Neuroscience, Functional Magnetic Resonance Imaging, Image reconstruction, Reconstruction

**TL;DR**: We present PRISM, a framework to decode visual stimuli from fMRI with language model alignment

**TL;DR翻译**: 我们提出了PRISM，一个通过语言模型对齐从fMRI解码视觉刺激的框架。

**Abstract**:

Understanding how the brain encodes visual information is a central challenge in neuroscience and machine learning. A promising approach is to reconstruct visual stimuli—essentially images—from functional Magnetic Resonance Imaging (fMRI) signals. This involves two stages: transforming fMRI signals into a latent space and then using a pre-trained generative model to reconstruct images. The reconstruction quality depends on how similar the latent space is to the structure of neural activity and how well the generative model produces images from that space. Yet, it remains unclear which type of latent space best supports this transformation and how it should be organized to represent visual stimuli effectively.

We present two key findings. First, fMRI signals are more similar to the text space of a language model than to either a vision-based space or a joint text–image space. Second, text representations and the generative model should be adapted to capture the compositional nature of visual stimuli, including objects, their detailed attributes, and relationships. Building on these insights, we propose PRISM, a model that Projects fMRI sIgnals into a Structured text space as an interMediate representation for visual stimuli reconstruction. It includes an object-centric diffusion module that generates images by composing individual objects to reduce object detection errors, and an attribute–relationship search module that automatically identifies key attributes and relationships that best align with the neural activity.

Extensive experiments on real-world datasets demonstrate that our framework outperforms existing methods, achieving up to an 6% reduction in perceptual loss. These results highlight the importance of using structured text as the intermediate space to bridge fMRI signals and image reconstruction. Codes are available at https://github.com/GraphmindDartmouth/PRISM.

**摘要翻译**:

理解大脑如何编码视觉信息是神经科学和机器学习中的核心挑战。一种有前景的方法是从功能性磁共振成像（fMRI）信号重建视觉刺激——本质上是图像。这涉及两个阶段：将fMRI信号转换到潜空间，然后使用预训练的生成模型从该空间重建图像。重建质量取决于潜空间与神经活动结构的相似程度，以及生成模型从该空间产生图像的能力。然而，何种类型的潜空间最适合这种转换，以及它应如何组织以有效表示视觉刺激，仍不清楚。

我们提出了两个关键发现。首先，fMRI信号与语言模型的文本空间的相似度高于基于视觉的空间或联合文本-图像空间。其次，文本表示和生成模型应被调整以捕捉视觉刺激的组合性质，包括物体、其详细属性和关系。基于这些洞察，我们提出了PRISM，一个将fMRI信号投射到结构化文本空间作为视觉刺激重建中间表示的模型。它包含一个以物体为中心的扩散模块，通过组合单个物体来生成图像以减少物体检测错误，以及一个属性-关系搜索模块，自动识别与神经活动最佳对齐的关键属性和关系。

在真实数据集上的大量实验表明，我们的框架优于现有方法，感知损失降低了高达6%。这些结果凸显了使用结构化文本作为中间空间来连接fMRI信号和图像重建的重要性。

---

## 78. Temporal Sparse Autoencoders: Leveraging the Sequential Nature of Language for Interpretability

**时序稀疏自编码器：利用语言的序列特性提升可解释性**

**OpenReview**: [https://openreview.net/forum?id=bojVI4l9Kn](https://openreview.net/forum?id=bojVI4l9Kn)

**Authors**: Usha Bhalla, Alex Oesterling (School of Engineering and Applied Sciences, Harvard University), Claudio Mayrink Verdun (Harvard University), Himabindu Lakkaraju (Google), Flavio Calmon (Harvard University)

**Institutions**: School of Engineering and Applied Sciences, Harvard University, Harvard University, Google

**Primary Area**: interpretability and explainable AI

**Keywords**: Interpretability, Dictionary Learning, Machine Learning, Large Language Models

**TL;DR**: We propose that using contextual information to train SAEs will improve their representation of semantic and high-level features.

**TL;DR翻译**: 我们提出利用上下文信息来训练SAE，以改善其对语义特征的表示。

**Abstract**:

Translating the internal representations and computations of models into concepts that humans can understand is a key goal of interpretability. While recent dictionary learning methods such as Sparse Autoencoders (SAEs) provide a promising route to discover human-interpretable features, they often only recover token-specific, noisy, or highly local concepts. We argue that this limitation stems from neglecting the temporal structure of language, where semantic content typically evolves smoothly over sequences. Building on this insight, we introduce Temporal Sparse Autoencoders (T-SAEs), which incorporate a novel contrastive loss encouraging consistent activations of high-level features over adjacent tokens. This simple yet powerful modification enables SAEs to disentangle semantic from syntactic features in a self-supervised manner. Across multiple datasets and models, T-SAEs recover smoother, more coherent semantic concepts without sacrificing reconstruction quality. Strikingly, they exhibit clear semantic structure despite being trained without explicit semantic signal, offering a new pathway for unsupervised interpretability in language models.

**摘要翻译**:

将模型的内部表示和计算转化为人类可理解的概念是可解释性的关键目标。虽然稀疏自编码器（SAE）等近期的字典学习方法为发现人类可解释的特征提供了有前景的途径，但它们往往只能恢复特定于token的、嘈杂的或高度局部的概念。我们认为，这一局限源于忽视了语言的时序结构，而语义内容通常在序列中平滑演变。基于这一洞察，我们引入了时序稀疏自编码器（T-SAE），通过新颖的对比损失鼓励高层特征在相邻token上的一致激活。这一简单但强大的修改使SAE能够以自监督的方式将语义特征与句法特征解耦。在多个数据集和模型上，T-SAE恢复了更平滑、更连贯的语义概念，同时不牺牲重建质量。引人注目的是，尽管在训练时没有显式的语义信号，它们仍展现出清晰的语义结构，为语言模型中的无监督可解释性提供了新途径。

---

## 79. VibeVoice: Expressive Podcast Generation with Next-Token Diffusion

**VibeVoice：基于下一token扩散的表现力播客生成**

**OpenReview**: [https://openreview.net/forum?id=FihSkzyxdv](https://openreview.net/forum?id=FihSkzyxdv)

**Authors**: Zhiliang Peng (Microsoft), Jianwei Yu (Microsoft), Wenhui Wang (Microsoft), Yaoyao Chang (Microsoft), Yutao Sun (Tsinghua University, Tsinghua University), Li Dong (Microsoft Research), Yi Zhu (Research, Microsoft), Weijiang Xu (University of Science and Technology of China), Hangbo Bao (Microsoft), Zehua Wang (Renmin University of China), Shaohan Huang (Microsoft), Yan Xia (Research, Microsoft), Furu Wei (Microsoft Research)

**Institutions**: Microsoft, Tsinghua University, Tsinghua University, Microsoft Research, Research, Microsoft, University of Science and Technology of China, Renmin University of China

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Text-to-Speech; Podcast Generation

**TL;DR**: VibeVoice can synthesize long-form speech for up to 90 minutes (in a 64K context window length) with a maximum of 4 speakers, capturing the authentic conversational vibe and surpassing open-source and proprietary dialogue models.

**TL;DR翻译**: VibeVoice能够合成长达90分钟（在64K上下文窗口长度下）的长篇语音，具有丰富的表现力和自然的多说话人对话效果。

**Abstract**:

Generating long-form, multi-speaker conversational audio like podcasts poses significant challenges for traditional Text-to-Speech (TTS) systems, particularly in scalability, speaker consistency, and natural turn-taking. We present VibeVoice , a novel model designed to synthesize expressive, long-form speech with multiple speakers in a zero-shot manner. A core component of our approach is the continuous speech tokenizers operating at an ultra-low frame rate of 7.5. This tokenizer effectively preserves audio fidelity while significantly boosting computational efficiency for processing long sequences. To facilitate training on authentic conversational dynamics, we have developed an annotation pipeline that generates pseudo transcriptions and turn-taking labels for extensive podcast data. Leveraging this data and our efficient tokenizer, VibeVoice  employs the next-token diffusion framework. This enables VibeVoice  to: (1) synthesize long-form speech (up to 30 minutes) with up to 4 speakers, surpassing the typical 1-2 speaker limits of many prior models; and (2) achieve a high degree of naturalness in turn-taking, pacing, and the rendition of subtle non-lexical cues (such as breaths and lip smacks), which are crucial for listener immersion and capturing the authentic vibe of expressive conversations.

**摘要翻译**:

生成播客等长篇多说话人对话音频对传统的文本到语音（TTS）系统提出了重大挑战，尤其在可扩展性、说话人一致性和自然轮次切换方面。我们提出了VibeVoice，一个新颖的模型，旨在以零样本方式合成具有表现力的长篇多说话人语音。我们方法的核心组件是工作在7.5超低帧率下的连续语音分词器。该分词器在有效保持音频保真度的同时，显著提升了处理长序列的计算效率。为了促进在真实对话动态上的训练，我们开发了一个标注管线，为大量播客数据生成伪转录和轮次切换标签。利用这些数据和我们的高效分词器，VibeVoice采用了下一token扩散框架。这使VibeVoice能够：（1）合成长达30分钟、最多4个说话人的长篇语音，突破了许多先前模型1-2个说话人的典型限制；（2）在轮次切换、节奏以及微妙的非词汇线索（如呼吸声和唇部声响）的呈现方面实现高度自然性，这些对于听众沉浸感和捕捉富有表现力的对话的真实氛围至关重要。

---

## 80. AdAEM: An Adaptively and Automated Extensible Evaluation Method of LLMs' Value Difference

**AdAEM：一种自适应自动化可扩展的LLM价值差异评估方法**

**OpenReview**: [https://openreview.net/forum?id=qNlTH4kYJZ](https://openreview.net/forum?id=qNlTH4kYJZ)

**Authors**: Jing Yao (Microsoft), Shitong Duan (Fudan University), Xiaoyuan Yi (Microsoft Research), Dongkuan Xu (North Carolina State University), Peng Zhang (Fudan University), Tun Lu (Fudan University), Ning Gu (Fudan University), Zhicheng Dou (Renmin University of China), Xing Xie (Microsoft Research Asia)

**Institutions**: Microsoft, Fudan University, Microsoft Research, North Carolina State University, Renmin University of China, Microsoft Research Asia

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: LLM Evaluation, Value Evaluation, Value Alignment, Dynamic Evaluation

**TL;DR**: This paper proposes aa novel dynamic and automated evaluation framework to probe LLMs' value orientations and value differences

**TL;DR翻译**: 本文提出了一种新颖的动态自动化评估框架，用于探测LLM的价值取向和价值差异。

**Abstract**:

Assessing Large Language Models (LLMs)' underlying value differences enables comprehensive comparison of their misalignment, cultural adaptability, and biases. Nevertheless, current value measurement methods face the informativeness challenge: with often outdated, contaminated, or generic test questions, they can only capture the orientations on comment safety values, e.g., HHH, shared among different LLMs, leading to indistinguishable and uninformative results. To address this problem, we introduce AdAEM, a novel, self-extensible evaluation algorithm for revealing LLMs' inclinations. Distinct from static benchmarks, AdAEM automatically and adaptively generates and extends its test questions. This is achieved by probing the internal value boundaries of a diverse set of LLMs developed across cultures and time periods in an in-context optimization manner. Such a process theoretically maximizes an information-theoretic objective to extract diverse controversial topics that can provide more distinguishable and informative insights about models' value differences. In this way, AdAEM is able to co-evolve with the development of LLMs, consistently tracking their value dynamics. We use AdAEM to generate novel questions and conduct an extensive analysis, demonstrating our method's validity and effectiveness, laying the groundwork for better interdisciplinary research on LLMs' values and alignment.

**摘要翻译**:

评估大语言模型（LLM）的底层价值差异有助于全面比较其不对齐程度、文化适应性和偏见。然而，当前的价值衡量方法面临信息量不足的挑战：由于测试题目往往过时、被污染或过于泛化，它们只能捕捉不同LLM之间共享的常见安全价值取向（如HHH），导致结果难以区分且信息量不足。为解决这一问题，我们引入了AdAEM，一种新颖的自扩展评估算法，用于揭示LLM的倾向性。与静态基准不同，AdAEM自动且自适应地生成和扩展其测试题目。这是通过以上下文优化的方式探测跨文化和跨时期开发的多样化LLM集合的内部价值边界来实现的。这一过程在理论上最大化了一个信息论目标，以提取能够提供更具区分度和信息量的关于模型价值差异洞察的多样化争议性话题。通过这种方式，AdAEM能够与LLM的发展共同进化，持续追踪其价值动态。我们使用AdAEM生成了新的题目并进行了广泛的分析，验证了我们方法的有效性和效果，为LLM价值和对齐的跨学科研究奠定了基础。

---

## 81. Omni-Reward: Towards Generalist Omni-Modal Reward Modeling with Free-Form Preferences

**Omni-Reward：迈向具有自由形式偏好的通用全模态奖励建模**

**OpenReview**: [https://openreview.net/forum?id=9C4gVbPqSy](https://openreview.net/forum?id=9C4gVbPqSy)

**Authors**: Zhuoran Jin (Institute of Automation, Chinese Academy of Sciences), Hongbang Yuan (Fudan University), Kejian Zhu (Institute of automation, Chinese academy of science), Jiachun Li (Institute of automation, Chinese academy of science), Pengfei Cao (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Yubo Chen (Institute of automation, Chinese academy of science), Kang Liu (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Jun Zhao (Institute of automation, Chinese academy of science)

**Institutions**: Institute of Automation, Chinese Academy of Sciences, Fudan University, Institute of automation, Chinese academy of science, Institute of automation, Chinese academy of science, Chinese Academy of Sciences

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Omni-Modal Models, Reward Models, Alignment

**TL;DR**: We propose Omni-Reward, a step towards universal omni-modal reward modeling with free-form preferences.

**TL;DR翻译**: 我们提出了Omni-Reward，朝着具有自由形式偏好的通用全模态奖励建模迈出了一步。

**Abstract**:

Reward models (RMs) play a critical role in aligning AI behaviors with human preferences, yet they face two fundamental challenges: (1) Modality Imbalance, where most RMs are mainly focused on text and image modalities, offering limited support for video, audio, and other modalities; and (2) Preference Rigidity, where training on fixed binary preference pairs fails to capture the complexity and diversity of personalized preferences. To address the above challenges, we propose Omni-Reward, a step toward generalist omni-modal reward modeling with support for free-form preferences, consisting of: (1) Evaluation: We introduce Omni-RewardBench, the first omni-modal RM benchmark with free-form preferences, covering nine tasks across five modalities including text, image, video, audio, and 3D; (2) Data: We construct Omni-RewardData, a multimodal preference dataset comprising 248K general preference pairs and 69K instruction-tuning pairs for training generalist omni-modal RMs; (3) Model: We propose Omni-RewardModel, which includes both discriminative and generative RMs, and achieves strong performance on Omni-RewardBench as well as other widely used reward modeling benchmarks.

**摘要翻译**:

奖励模型（RM）在将AI行为与人类偏好对齐方面发挥着关键作用，但面临两个根本挑战：（1）模态不平衡，即大多数RM主要聚焦于文本和图像模态，对视频、音频及其他模态支持有限；（2）偏好僵化，即在固定的二元偏好对上训练无法捕捉个性化偏好的复杂性和多样性。为解决上述挑战，我们提出了Omni-Reward，朝着支持自由形式偏好的通用全模态奖励建模迈出的一步，包含：（1）评估：我们引入了Omni-RewardBench，首个具有自由形式偏好的全模态RM基准测试，涵盖文本、图像、视频、音频和3D五种模态的九项任务；（2）数据：我们构建了Omni-RewardData，一个多模态偏好数据集，包含248K通用偏好对和69K指令微调对，用于训练通用全模态RM；（3）模型：我们提出了Omni-RewardModel，包含判别式和生成式RM，在Omni-RewardBench以及其他广泛使用的奖励建模基准测试上均取得了优异性能。

---

## 82. Spherical Watermark: Encryption-Free, Lossless Watermarking for Diffusion Models

**球面水印：面向扩散模型的免加密无损水印方案**

**OpenReview**: [https://openreview.net/forum?id=2eAGrunxVz](https://openreview.net/forum?id=2eAGrunxVz)

**Authors**: Xiaoxiao Hu (Fudan University), Jiaqi Jin (Fudan University), Sheng Li (Fudan University), Wanli Peng (China Agricultural University), Xinpeng Zhang (Fudan University), Zhenxing Qian (Fudan University)

**Institutions**: Fudan University, China Agricultural University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: AIGC Watermarking; Diffusion Models;

**TL;DR**: Employing a novel spherical mapping mechanism, we propose a novel lossless watermarking scheme for text-to-image diffusion models.

**TL;DR翻译**: 利用一种新颖的球面映射机制，我们为文本到图像扩散模型提出了一种新的无损水印方案。

**Abstract**:

Diffusion models have revolutionized image synthesis but raise concerns around content provenance and authenticity. Digital watermarking offers a means of tracing generated media, yet traditional schemes often introduce distributional shifts and degrade visual quality. Recent lossless methods embed watermark bits directly into the latent Gaussian prior without modifying model weights, but still require per-image key storage or heavy cryptographic overhead. In this paper, we introduce Spherical Watermark, an encryption‐free and lossless watermarking framework that integrates seamlessly with diffusion architectures. First, our binary embedding module mixes repeated watermark bits with random padding to form a high-entropy code. Second, the spherical mapping module projects this code onto the unit sphere, applies an orthogonal rotation, and scales by a chi-square-distributed radius to recover exact multivariate Gaussian noise. We theoretically prove that the watermarked noise distribution preserves the target prior up to third-order moments, and empirically demonstrate that it is statistically indistinguishable from a standard multivariate normal distribution. Adopting Stable Diffusion, extensive experiments confirm that Spherical Watermark consistently preserves high visual fidelity while simultaneously improving traceability, computational efficiency, and robustness under attacks, thereby outperforming both lossy and lossless approaches.

**摘要翻译**:

扩散模型革新了图像合成，但也引发了关于内容来源和真实性的担忧。数字水印提供了一种追踪生成媒体的手段，然而传统方案往往引入分布偏移并降低视觉质量。近期的无损方法将水印比特直接嵌入潜高斯先验中而不修改模型权重，但仍需要逐图像的密钥存储或大量的加密开销。在本文中，我们引入了球面水印（Spherical Watermark），一种免加密的无损水印框架，可与扩散架构无缝集成。首先，我们的二进制嵌入模块将重复的水印比特与随机填充混合以形成高熵编码。其次，球面映射模块将此编码投影到单位球面上，施加正交旋转，并按卡方分布的半径进行缩放以恢复精确的多元高斯噪声。我们从理论上证明了水印噪声分布在三阶矩以内保持了目标先验分布，并通过实验证明它与标准多元正态分布在统计上不可区分。采用Stable Diffusion进行的大量实验证实，球面水印在保持高视觉保真度的同时，提升了可追溯性、计算效率和抗攻击鲁棒性，从而优于有损和无损方法。

---

## 83. Rodrigues Network for Learning Robot Actions

**Rodrigues网络：用于学习机器人动作的神经网络**

**OpenReview**: [https://openreview.net/forum?id=IZHk6BXBST](https://openreview.net/forum?id=IZHk6BXBST)

**Authors**: Jialiang Zhang (Peking University), Haoran Geng (University of California, Berkeley), Yang You (Stanford University), Congyue Deng (Massachusetts Institute of Technology), Pieter Abbeel (Amazon), Jitendra Malik (Amazon), Leonidas Guibas (Stanford University)

**Institutions**: Peking University, University of California, Berkeley, Stanford University, Massachusetts Institute of Technology, Amazon

**Primary Area**: applications to robotics, autonomy, planning

**Keywords**: Robot learning, Action understanding, Neural architecture

**TL;DR**: We design a new neural network, the Rodrigues Network (RodriNet), that addresses the kinematic structural priors in articulated robot action learning.

**TL;DR翻译**: 我们设计了一种新的神经网络——Rodrigues网络（RodriNet），它解决了关节式机器人动作学习中的运动学结构先验问题。

**Abstract**:

Understanding and predicting articulated actions is important in robot learning. However, common architectures such as MLPs and Transformers lack inductive biases that reflect the underlying kinematic structure of articulated systems. To this end, we propose the **Neural Rodrigues Operator**, a learnable generalization of the classical forward kinematics operation, designed to inject kinematics-aware inductive bias into neural computation. Building on this operator, we design the **Rodrigues Network (RodriNet)**, a novel neural architecture specialized for processing actions. We evaluate the expressivity of our network on two synthetic tasks on kinematic and motion prediction, showing significant improvements compared to standard backbones. We further demonstrate its effectiveness in two realistic applications: (i) imitation learning on robotic benchmarks with the Diffusion Policy, and (ii) single-image 3D hand reconstruction. Our results suggest that integrating structured kinematic priors into the network architecture improves action learning in various domains.

**摘要翻译**:

理解和预测关节动作在机器人学习中非常重要。然而，MLP和Transformer等常用架构缺乏反映关节系统底层运动学结构的归纳偏置。为此，我们提出了**神经Rodrigues算子**，这是经典正向运动学操作的可学习泛化，旨在将运动学感知的归纳偏置注入神经计算中。基于该算子，我们设计了**Rodrigues网络（RodriNet）**，一种专门用于处理动作的新颖神经网络架构。我们在运动学预测和运动预测两个合成任务上评估了网络的表达能力，与标准骨干网络相比展示了显著的改进。我们进一步在两个实际应用中展示了其有效性：（i）在机器人基准测试上使用Diffusion Policy进行模仿学习，（ii）单图像三维手部重建。我们的结果表明，将结构化的运动学先验整合到网络架构中可以改善多个领域中的动作学习。

---

## 84. CyberGym: Evaluating AI Agents' Real-World Cybersecurity Capabilities at Scale

**CyberGym：大规模评估AI智能体的真实网络安全能力**

**OpenReview**: [https://openreview.net/forum?id=2YvbLQEdYt](https://openreview.net/forum?id=2YvbLQEdYt)

**Authors**: Zhun Wang, Tianneng Shi, Jingxuan He (University of California, Berkeley), Matthew Cai (University of California, Berkeley), Jialin Zhang (University of California, Berkeley), Dawn Song (University of California Berkeley)

**Institutions**: University of California, Berkeley, University of California Berkeley

**Primary Area**: datasets and benchmarks

**Keywords**: Cybersecurity, AI, Agents

**Abstract**:

AI agents have significant potential to reshape cybersecurity, making a thorough assessment of their capabilities critical.
However, existing evaluations fall short, because they are based on small-scale benchmarks and only measure static outcomes, failing to capture the full, dynamic range of real-world security challenges.
To address these limitations, we introduce CyberGym, a large-scale benchmark featuring 1,507 real-world vulnerabilities across 188 software projects.
Adjustable to different vulnerability analysis settings, CyberGym primarily tasks agents with generating a proof-of-concept test that reproduces a vulnerability, given only its text description and the corresponding codebase.
Our extensive evaluation highlights that CyberGym effectively differentiates agents' and models' cybersecurity capabilities.
Even the top-performing combinations only achieve a ~20% success rate, demonstrating the overall difficulty of CyberGym. 
Beyond static benchmarking, we show that CyberGym leads to the discovery of 35 zero-day vulnerabilities and 17 historically incomplete patches.
These results underscore that CyberGym is not only a robust benchmark for measuring AI's progress in cybersecurity but also a platform for creating direct, real-world security impact.

**摘要翻译**:

AI智能体具有重塑网络安全的巨大潜力，因此对其能力的全面评估至关重要。然而，现有的评估存在不足，因为它们基于小规模基准测试，且仅衡量静态结果，无法捕捉真实世界安全挑战的完整动态范围。为解决这些局限，我们引入了CyberGym，一个大规模基准测试，包含188个软件项目中的1,507个真实漏洞。CyberGym可调整到不同的漏洞分析设置，其主要任务是在仅给定漏洞的文本描述和相应代码库的情况下，让智能体生成一个能够复现漏洞的概念验证测试。我们的广泛评估表明，CyberGym能够有效区分智能体和模型的网络安全能力。即使是表现最好的组合也仅达到约20%的成功率，证明了CyberGym的整体难度。在静态基准测试之外，我们展示了CyberGym还发现了35个零日漏洞和17个历史上不完整的补丁。这些结果表明，CyberGym不仅是衡量AI在网络安全领域进展的鲁棒基准测试，也是创造直接真实世界安全影响的平台。

---

## 85. Energy-Based Transformers are Scalable Learners and Thinkers

**基于能量的 Transformer 是可扩展的学习器与思考器**

**OpenReview**: [https://openreview.net/forum?id=ZBj3Qp1bYg](https://openreview.net/forum?id=ZBj3Qp1bYg)

**Authors**: Alexi Gladstone (University of Illinois at Urbana-Champaign), Ganesh Nanduru (University of Virginia, Charlottesville), Md Mofijul Islam (Amazon), Peixuan Han (University of Illinois at Urbana-Champaign), Hyeonjeong Ha (Department of Computer Science, University of Illinois at Urbana-Champaign), Aman Chadha (Apple), Yilun Du (Google), Heng Ji (University of Illinois, Urbana-Champaign), Jundong Li (University of Virginia), Tariq Iqbal (University of Virginia)

**Institutions**: University of Illinois at Urbana-Champaign, University of Virginia, Charlottesville, Amazon, Department of Computer Science, University of Illinois at Urbana-Champaign, Apple, Google, University of Illinois, Urbana-Champaign, University of Virginia

**Primary Area**: generative models

**Keywords**: Energy-Based Models, System 2 Thinking, Reasoning, Verification, Scaling, Transformers, Generative Modeling

**TL;DR**: We introduce Energy-Based Transformers, a scalable new approach for learning how to think from unsupervised learning, generalizing current System 2 Thinking/reasoning approaches.

**TL;DR翻译**: 我们提出了 Energy-Based Transformers，一种可扩展的新方法，通过无监督学习来学习如何"思考"，对现有的系统二思维/推理方法进行了泛化。

**Abstract**:

Inference-time computation, analogous to human System 2 Thinking, has recently become popular for improving model performance. However, most existing approaches suffer from several limitations: they are modality-specific (e.g., working only in text), problem-specific (e.g., verifiable domains like math and coding), or require additional supervision/training on top of unsupervised pretraining (e.g., verifiers or verifiable rewards). In this paper, we ask the question "Is it possible to generalize these System 2 Thinking approaches, and develop models that learn to think solely from unsupervised learning?" We find the answer is yes, by learning to explicitly verify the compatibility between inputs and candidate-predictions, and then re-framing prediction problems as optimization with respect to this verifier. Specifically, we train Energy-Based Transformers (EBTs)---a new class of Energy-Based Models (EBMs)---to assign an energy value to every input and candidate-prediction, enabling predictions through energy minimization until convergence. To support this approach, we introduce several key techniques for stable and parallelizable training, which enable the emergence of strong System 2 Thinking capabilities and scalable EBMs. Across discrete and continuous modalities, we find EBTs outperform the Transformer++ approach, scaling up to 35% faster during pretraining, and improving inference-time performance by up to 29%. EBTs also surpass Diffusion Transformers on image denoising while requiring 99% fewer forward passes. Moreover, System 2 Thinking with EBTs yields larger performance gains on data that is farther out-of-distribution, and EBTs achieve better results than existing models on most downstream tasks despite achieving the same or worse pretraining performance, enabling EBTs to generalize better than existing approaches. Consequently, EBTs are a flexible and exciting new approach for scaling both the learning and thinking capabilities of models.

**摘要翻译**:

推理时计算类似于人类的系统二思维，近年来在提升模型性能方面受到广泛关注。然而，现有方法大多存在若干局限性：它们要么局限于特定模态（例如仅适用于文本），要么局限于特定问题类型（例如数学和编程等可验证领域），要么需要在无监督预训练之上进行额外的监督/训练（例如验证器或可验证奖励）。本文提出了这样一个问题："能否对这些系统二思维方法进行泛化，开发出仅通过无监督学习就能学会思考的模型？"我们的答案是肯定的——通过学习显式地验证输入与候选预测之间的兼容性，并将预测问题重新定义为关于该验证器的优化问题。具体而言，我们训练了 Energy-Based Transformers（EBTs）——一类新的基于能量的模型（EBMs）——为每个输入和候选预测分配一个能量值，通过能量最小化直至收敛来实现预测。为支持这一方法，我们引入了若干关键技术以实现稳定且可并行化的训练，从而使强大的系统二思维能力和可扩展的 EBMs 得以涌现。在离散和连续模态上，EBTs 均优于 Transformer++ 方法，预训练阶段的扩展速度提高了高达 35%，推理时性能提升了高达 29%。EBTs 在图像去噪任务上也超越了 Diffusion Transformers，且所需的前向传播次数减少了 99%。此外，EBTs 的系统二思维在分布外程度更高的数据上带来了更大的性能增益，且 EBTs 在大多数下游任务上取得了优于现有模型的结果，尽管其预训练性能相当或更低，这使得 EBTs 的泛化能力优于现有方法。因此，EBTs 是一种灵活且令人期待的新方法，能够同时扩展模型的学习能力和思考能力。

---

## 86. Global Resolution: Optimal Multi-Draft Speculative Sampling via Convex Optimization

**全局求解：基于凸优化的最优多草稿推测采样**

**OpenReview**: [https://openreview.net/forum?id=gpsczXOsHn](https://openreview.net/forum?id=gpsczXOsHn)

**Authors**: Rahul Krishna Thomas (Columbia University), Arka Pal (Ritual AI)

**Institutions**: Columbia University, Ritual AI

**Primary Area**: probabilistic methods (Bayesian methods, variational inference, sampling, UQ, etc.)

**Keywords**: LLMs, Inference, Optimal Transport, Speculative Decoding

**TL;DR**: We reduce optimal multi-draft speculative sampling to a convex minimization problem, and solve a truncated version to achieve state-of-the-art acceptance with negligible performance degradation.

**TL;DR翻译**: 我们将最优多草稿推测采样归结为一个凸最小化问题，并通过求解其截断版本实现了最先进的接受率，且性能损失可忽略不计。

**Abstract**:

Speculative sampling reduces the latency of autoregressive decoding for target model LLMs without sacrificing inference quality, by using a cheap draft model to suggest a candidate token and a verification criterion to accept or resample this token. To improve acceptance and decoding efficiency, recent work has explored the multi-draft extension, where at each step $n$ draft tokens are generated, and the verification criterion is a distribution conditioned on these. When this criterion maximizes the probability of accepting some draft token, it is called the optimal transport (OT). However, finding the OT is difficult, as it is the solution of a linear program (OTLP) in over $V^n$ variables, with $V$ being the vocabulary size. Two recent theoretical works have reframed the OTLP in terms of importance sampling or subset selection. In this work, we prove that these formulations are equivalent to an exponentially large relaxed OTLP, so it remains infeasible to solve. Then, we reverse engineer subset selection to formulate the OTLP as a max-flow problem. With a novel application of polymatroid theory, we reduce the exponentially large OTLP to a convex optimization problem in at most $V$ variables. This allows us to devise an algorithm for optimal $n$-draft speculative sampling when the $n$ tokens are chosen i.i.d. from a single draft model, which can be tuned to arbitrary accuracy. Finally, we measure acceptance rates and algorithm runtimes for various $n$ and top-$k$ draft sampling settings. Our findings give the first multi-draft algorithm with 90\% acceptance and under 100 ms of overhead per generated token with negligible deviation from the target model distribution.

**摘要翻译**:

推测采样通过使用廉价的草稿模型生成候选 token 并利用验证准则来决定接受或重新采样该 token，在不损失推理质量的前提下降低了目标模型 LLM 自回归解码的延迟。为提高接受率和解码效率，近期研究探索了多草稿扩展，即在每一步生成 $n$ 个草稿 token，验证准则为以这些 token 为条件的分布。当该准则最大化接受某个草稿 token 的概率时，称之为最优传输（OT）。然而，求解 OT 十分困难，因为它是一个包含超过 $V^n$ 个变量的线性规划（OTLP）问题，其中 $V$ 为词表大小。近期两项理论工作分别从重要性采样和子集选择的角度重新定义了 OTLP。本文证明，这些重新表述等价于一个指数级规模的松弛 OTLP，因此仍然不可行。随后，我们对子集选择进行逆向分析，将 OTLP 建模为最大流问题。通过创新性地应用多拟阵理论，我们将指数级规模的 OTLP 化简为至多包含 $V$ 个变量的凸优化问题。这使我们能够设计一种最优 $n$-草稿推测采样算法，适用于 $n$ 个 token 从单一草稿模型中独立同分布采样的情形，并可调节至任意精度。最后，我们在不同 $n$ 值和 top-$k$ 草稿采样设置下测量了接受率和算法运行时间。我们的结果给出了首个接受率达 90% 且每个生成 token 的额外开销低于 100 毫秒的多草稿算法，与目标模型分布的偏差可忽略不计。

---

## 87. FALCON: Few-step Accurate Likelihoods for Continuous Flows

**FALCON：连续流的少步精确似然估计**

**OpenReview**: [https://openreview.net/forum?id=FbssShlI4N](https://openreview.net/forum?id=FbssShlI4N)

**Authors**: Danyal Rehman (Mila - Quebec Artificial Intelligence Institute), Tara Akhound-Sadegh (McGill University), Artem Gazizov, Yoshua Bengio (University of Montreal), Alexander Tong (Aithyra)

**Institutions**: Mila - Quebec Artificial Intelligence Institute, McGill University, University of Montreal, Aithyra

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: Generative Models, Flow Matching, Boltzmann Generators, AI for Science

**TL;DR**: Few-step Flow Matching with Accurate Likelihoods for Scalable Boltzmann Generators

**TL;DR翻译**: 面向可扩展 Boltzmann 生成器的少步 Flow Matching 精确似然方法

**Abstract**:

Scalable sampling of molecular states in thermodynamic equilibrium is a long-standing challenge in statistical physics. Boltzmann Generators tackle this problem by pairing a generative model, capable of exact likelihood computation, with importance sampling to obtain consistent samples under the target distribution. Current Boltzmann Generators primarily use continuous normalizing flows (CNFs) trained with flow matching for efficient training of powerful models. However, likelihood calculation for these models is extremely costly, requiring thousands of function evaluations per sample, severely limiting their adoption. In this work, we propose Few-step Accurate Likelihoods for Continuous Flows (FALCON), a method which allows for few-step sampling with a likelihood accurate enough for importance sampling applications by introducing a hybrid training objective that encourages invertibility. We show FALCON outperforms state-of-the-art normalizing flow models for molecular Boltzmann sampling and is \emph{two orders of magnitude faster} than the equivalently performing CNF model.

**摘要翻译**:

在热力学平衡态下对分子状态进行可扩展的采样是统计物理学中的一个长期挑战。Boltzmann 生成器通过将具有精确似然计算能力的生成模型与重要性采样相结合来解决这一问题，以获得目标分布下的一致性样本。当前的 Boltzmann 生成器主要使用通过 flow matching 训练的连续归一化流（CNFs）来高效训练强大的模型。然而，这些模型的似然计算代价极高，每个样本需要数千次函数求值，严重限制了其实际应用。本文提出了 FALCON（连续流的少步精确似然），该方法通过引入鼓励可逆性的混合训练目标，实现了少步采样的同时保持足够精确的似然估计，适用于重要性采样应用。实验表明，FALCON 在分子 Boltzmann 采样任务上优于最先进的归一化流模型，且比性能相当的 CNF 模型快两个数量级。

---

## 88. How Reliable is Language Model Micro-Benchmarking?

**语言模型微基准测试的可靠性如何？**

**OpenReview**: [https://openreview.net/forum?id=cReExMQLiK](https://openreview.net/forum?id=cReExMQLiK)

**Authors**: Gregory Yauney (University of Southern California), Shahzaib Saqib Warraich (University of Southern California), Swabha Swayamdipta (University of Southern California)

**Institutions**: University of Southern California

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: efficient evaluation, meta-evaluation, language models

**Abstract**:

Micro-benchmarking offers a solution to the often prohibitive time and cost of language model development: evaluate on a very small subset of existing benchmarks. Can these micro-benchmarks, however, rank models as consistently as the full benchmarks they replace? And can they rank models more consistently than selecting a random subset of data points? In many scenarios, we find that the answer is no. We introduce a meta-evaluation measure for micro-benchmarking which investigates how well a micro-benchmark can rank two models as a function of their performance difference on the full benchmark. This approach can determine which model pairs can be ranked correctly by a micro-benchmark, allowing for a finer-grained analysis of the trade-off between micro-benchmark size and reliability.
Prior work has suggested selecting as few as 10 examples; we find that no micro-benchmarking method can consistently rank model pairs 3.5 points of accuracy apart on MMLU-Pro or 4 points apart on BIG-bench Hard. In order to consistently rank model pairs with relatively similar performances, we show that often as many as 250 examples must be selected, at which point random sampling is competitive with existing micro-benchmarking methods. When comparing only 8B instruction-tuned models on MMLU-Pro micro-benchmarks with 25 examples, we find that more than half of pairwise comparisons are not likely to be preserved. Our work provides actionable guidance for both micro-benchmark users and developers in navigating the trade-off between evaluation efficiency and reliability.

**摘要翻译**:

微基准测试为解决语言模型开发中常常难以承受的时间和成本提供了一种方案：仅在现有基准测试的极小子集上进行评估。然而，这些微基准测试能否像其所替代的完整基准测试一样一致地对模型进行排名？它们的排名一致性是否优于随机选取数据点子集？在许多场景下，我们发现答案是否定的。我们引入了一种微基准测试的元评估指标，通过考察微基准测试对两个模型的排名能力与它们在完整基准测试上的性能差异之间的关系来进行分析。该方法能够确定哪些模型对可以被微基准测试正确排名，从而实现对微基准测试规模与可靠性之间权衡的更精细分析。此前的研究建议仅选取少至 10 个样本；而我们发现，在 MMLU-Pro 上准确率差距为 3.5 个百分点、在 BIG-bench Hard 上差距为 4 个百分点的模型对，没有任何微基准测试方法能够一致地进行正确排名。为了一致地对性能相近的模型对进行排名，我们表明通常需要选取多达 250 个样本，而在此规模下随机采样已与现有微基准测试方法具有同等竞争力。当仅比较 8B 参数指令微调模型在包含 25 个样本的 MMLU-Pro 微基准测试上的表现时，我们发现超过一半的成对比较结果可能无法被保持。本文的研究为微基准测试的使用者和开发者在评估效率与可靠性之间的权衡方面提供了可操作的指导。

---

## 89. EditBench: Evaluating LLM Abilities to Perform Real-World Instructed Code Edits

**EditBench：评估 LLM 执行真实场景指令式代码编辑的能力**

**OpenReview**: [https://openreview.net/forum?id=FtL9eEmU6v](https://openreview.net/forum?id=FtL9eEmU6v)

**Authors**: Wayne Chi (Carnegie Mellon University), Valerie Chen (Carnegie Mellon University), Ryan Shar (Apple), Aditya Mittal (CMU, Carnegie Mellon University), Jenny Liang (School of Computer Science, Carnegie Mellon University), Wei-Lin Chiang (University of California, Berkeley), Anastasios Nikolas Angelopoulos (University of California, Berkeley), Ion Stoica (University of California, Berkeley), Graham Neubig (Carnegie Mellon University), Ameet Talwalkar (Datadog), Chris Donahue (Carnegie Mellon University)

**Institutions**: Carnegie Mellon University, Apple, CMU, Carnegie Mellon University, School of Computer Science, Carnegie Mellon University, University of California, Berkeley, Datadog

**Primary Area**: datasets and benchmarks

**Keywords**: code, real-world, llm, code edit, edit

**TL;DR**: We propose a new benchmark for evaluating an LLM's ability to perform code edits. Our data is gathered from in-the-wild code edits, leading to more realistic problems.

**TL;DR翻译**: 我们提出了一个新的基准测试，用于评估 LLM 的代码编辑能力。我们的数据来源于真实环境中的代码编辑，因此具有更高的现实性。

**Abstract**:

Instructed code editing, where LLMs directly modify a developer's existing code based on a user instruction, is becoming a widely used interaction mode in AI coding assistants. However, few benchmarks directly evaluate this capability and current datasets often rely on artificial sources. We introduce EditBench, a benchmark for evaluating LLM code editing capabilities  grounded in real-world usage, i.e.,~user instructions and code contexts collected in the wild.  EditBench comprises of 545 problems, multiple natural and programming languages, and a diverse set of real-world use cases, ranging from resolving errors to adding features. EditBench introduces context-dependent problems that require the model to understand code context, highlighted code, and cursor position in addition to the user instruction. We evaluate 40 diverse LLMs and observe that EditBench is a challenging set of problems where only 3 models score over 60\%. We find that model performance varies across different categories of user instructions. Further, we find that varying levels of contextual information greatly affect task success rate, with performance varying up to 11\%, indicating the importance of evaluating with realistic context.

**摘要翻译**:

指令式代码编辑——即 LLM 根据用户指令直接修改开发者的现有代码——正在成为 AI 编程助手中广泛使用的交互模式。然而，直接评估这一能力的基准测试很少，且现有数据集往往依赖于人工构造的数据来源。我们引入了 EditBench，一个基于真实使用场景的 LLM 代码编辑能力评估基准，即从实际环境中收集用户指令和代码上下文。EditBench 包含 545 个问题，涵盖多种自然语言和编程语言，以及从修复错误到添加功能等多样化的真实用例。EditBench 引入了上下文依赖问题，要求模型在理解用户指令之外，还需理解代码上下文、高亮代码和光标位置。我们评估了 40 个不同的 LLM，发现 EditBench 是一组具有挑战性的问题，仅有 3 个模型的得分超过 60%。我们发现模型在不同类别的用户指令上表现存在差异。此外，不同程度的上下文信息对任务成功率有显著影响，性能差异可达 11%，这表明在真实上下文下进行评估的重要性。

---

## 90. Online Learning and Equilibrium Computation with Ranking Feedback

**基于排名反馈的在线学习与均衡计算**

**OpenReview**: [https://openreview.net/forum?id=lg6H2oJPky](https://openreview.net/forum?id=lg6H2oJPky)

**Authors**: Mingyang Liu (Massachusetts Institute of Technology), Yongshan Chen (Northeastern University), Zhiyuan Fan (Massachusetts Institute of Technology), Gabriele Farina (Massachusetts Institute of Technology), Asuman E. Ozdaglar (Massachusetts Institute of Technology), Kaiqing Zhang (University of Maryland, College Park)

**Institutions**: Massachusetts Institute of Technology, Northeastern University, University of Maryland, College Park

**Primary Area**: learning theory

**Keywords**: Online Learning, Equilibrium Computation, Human Feedback

**TL;DR**: Hardness and positive results for online learning with ranking feedback. Together with equilibrium computation with ranking feedback.

**TL;DR翻译**: 基于排名反馈的在线学习的困难性结果与正面结果，以及基于排名反馈的均衡计算。

**Abstract**:

Online learning in arbitrary and possibly adversarial environments has been extensively studied in sequential decision-making, with a strong connection to equilibrium computation in game theory. Most existing online learning algorithms are based on \emph{numeric} utility feedback from the environment, which may be unavailable in applications with humans in the loop and/or with privacy concerns. In this paper, we study an online learning setting where only a \emph{ranking} of a set of proposed actions is provided to the learning agent at each timestep. We consider both ranking models based on either the \emph{instantaneous} utility at each timestep, or the \emph{time-average} utility until the current timestep, in both \emph{full-information} and \emph{bandit} feedback settings. Focusing on the standard (external-)regret metric, we show that sublinear regret cannot be achieved with the instantaneous utility ranking feedback in general. Moreover, we show that when the ranking model is relatively {deterministic} (\emph{i.e.,} with a small temperature in the Plackett-Luce model), sublinear regret cannot be achieved with the time-average utility ranking feedback, either. We then propose new algorithms to achieve sublinear regret, under the additional assumption that the utility vectors have a sublinear variation. Notably, we also show that when time-average utility ranking is used, such an additional assumption can be avoided in the full-information setting. As a consequence, we show that if all the players follow our algorithms, an approximate coarse correlated equilibrium of a normal-form game can be found through repeated play. Finally, we also validate the effectiveness of our algorithms via numerical experiments.

**摘要翻译**:

在任意且可能具有对抗性的环境中进行在线学习，已在序贯决策领域得到广泛研究，并与博弈论中的均衡计算有着密切联系。大多数现有在线学习算法基于环境提供的数值效用反馈，而在涉及人类参与和/或存在隐私顾虑的应用中，这种反馈可能无法获得。本文研究了一种在线学习设定，其中学习智能体在每个时间步仅能获得对一组候选动作的排名信息。我们考虑了两种排名模型：基于每个时间步的瞬时效用，或基于截至当前时间步的时间平均效用，并分别在全信息和赌博机反馈两种设定下进行研究。以标准的（外部）遗憾值为指标，我们证明在一般情况下，仅凭瞬时效用排名反馈无法实现亚线性遗憾。此外，我们还表明，当排名模型相对确定性较强时（即 Plackett-Luce 模型中的温度参数较小），时间平均效用排名反馈同样无法实现亚线性遗憾。随后，我们在效用向量具有亚线性变化的额外假设下，提出了能够实现亚线性遗憾的新算法。值得注意的是，我们还证明在使用时间平均效用排名的全信息设定中，可以避免此额外假设。由此推论，若所有参与者均采用我们的算法，则可通过重复博弈找到正则形式博弈的近似粗相关均衡。最后，我们通过数值实验验证了算法的有效性。

---

## 91. MC-Search: Evaluating and Enhancing Multimodal Agentic Search with Structured Long Reasoning Chains

**MC-Search：基于结构化长推理链的多模态智能体搜索评估与增强**

**OpenReview**: [https://openreview.net/forum?id=JEGDp1E4OH](https://openreview.net/forum?id=JEGDp1E4OH)

**Authors**: Xuying Ning (University of Illinois at Urbana-Champaign), Dongqi Fu (Meta), Tianxin Wei, Mengting Ai (University of Illinois at Urbana-Champaign), Jiaru Zou, Ting-Wei Li (University of Illinois at Urbana-Champaign), Hanghang Tong (University of Illinois at Urbana-Champaign), Yada Zhu (IBM Research), Hendrik Hamann (State University of New York at Stony Brook), Jingrui He (University of Illinois at Urbana-Champaign)

**Institutions**: University of Illinois at Urbana-Champaign, Meta, IBM Research, State University of New York at Stony Brook

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Multimodal, RAG, Vision-Language, Agent, Benchmark

**Abstract**:

With the increasing demand for step-wise, cross-modal, and knowledge-grounded reasoning, multimodal large language models (MLLMs) are evolving beyond the traditional fixed retrieve-then-generate paradigm toward more sophisticated agentic multimodal retrieval-augmented generation (MM-RAG). Existing benchmarks, however, mainly focus on simplified QA with short retrieval chains, leaving adaptive planning and multimodal reasoning underexplored. We present MC-Search, the first benchmark for agentic MM-RAG with long, step-wise annotated reasoning chains spanning five representative reasoning structures. Each example specifies sub-questions, retrieval modalities, supporting facts, and intermediate answers, with fidelity ensured by HAVE (Hop-wise Attribution and Verification of Evidence), resulting in 3,333 high-quality examples averaging 3.7 hops. Beyond answer accuracy, MC-Search introduces new process-level metrics for reasoning quality, stepwise retrieval and planning accuracy. By developing a unified agentic MM-RAG pipeline, we benchmark six leading MLLMs and reveal systematic issues such as over- and under-retrieval and modality-misaligned planning. Finally, we introduce Search-Align, a process-supervised fine-tuning framework leveraging verified reasoning chains, showing that our data not only enables faithful evaluation but also improves planning and retrieval fidelity in open-source MLLMs.

**摘要翻译**:

随着对逐步推理、跨模态推理和知识驱动推理需求的增长，多模态大语言模型（MLLMs）正从传统的固定"检索-生成"范式向更复杂的智能体式多模态检索增强生成（MM-RAG）演进。然而，现有基准测试主要关注具有短检索链的简化问答任务，对自适应规划和多模态推理探索不足。我们提出了 MC-Search，这是首个针对智能体式 MM-RAG 的基准测试，包含覆盖五种代表性推理结构的长步骤标注推理链。每个样本指定了子问题、检索模态、支持事实和中间答案，通过 HAVE（逐跳归因与证据验证）确保标注的可靠性，最终产出 3,333 个高质量样本，平均推理跳数为 3.7。除答案准确性外，MC-Search 还引入了新的过程级指标，用于衡量推理质量、逐步检索和规划准确性。通过构建统一的智能体式 MM-RAG 流水线，我们对六个领先的 MLLMs 进行了基准测试，揭示了过度检索、检索不足以及模态错位规划等系统性问题。最后，我们引入了 Search-Align，一个利用经验证推理链的过程监督微调框架，表明我们的数据不仅能实现可靠的评估，还能提升开源 MLLMs 的规划和检索可靠性。

---

## 92. True Self-Supervised Novel View Synthesis is Transferable

**真正的自监督新视角合成具有可迁移性**

**OpenReview**: [https://openreview.net/forum?id=aJJppqAm6r](https://openreview.net/forum?id=aJJppqAm6r)

**Authors**: Thomas Mitchel, Hyunwoo Ryu (Massachusetts Institute of Technology), Vincent Sitzmann (Massachusetts Institute of Technology)

**Institutions**: Massachusetts Institute of Technology

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Novel View Synthesis, Self-Supervised, Unsupervised, Representation Learning

**TL;DR**: The key criterion for determining whether a models is capable of NVS is transferability, and we present the first fully geometry-free and self-supervised model capable of it.

**TL;DR翻译**: 判断模型是否真正具备新视角合成（NVS）能力的关键标准是可迁移性，我们提出了首个完全无需几何先验的自监督模型来实现这一目标。

**Abstract**:

In this paper, we identify that the key criterion for determining whether a model is truly capable of novel view synthesis (NVS) is transferability: Whether any pose representation extracted from one video sequence can be used to re-render the same camera trajectory in another. We analyze prior work on self-supervised NVS and find that their predicted poses do not transfer: The same set of poses lead
to different camera trajectories in different 3D scenes. Here, we present XFactor, the first geometry-free self-supervised model capable of true NVS. XFactor combines pair-wise pose estimation with a simple augmentation scheme of the inputs and outputs that jointly enables disentangling camera pose from scene content and facilitates geometric reasoning. Remarkably, we show that XFactor achieves transferability with unconstrained latent pose variables, without any 3D inductive biases or concepts from multi-view geometry — such as an explicit parameterization of poses as elements of SE(3). We introduce a new metric to quantify transferability, and through large-scale experiments, we demonstrate that XFactor significantly outperforms prior pose-free NVS transformers, and show that latent poses are highly correlated with real-world poses through probing experiments.

**摘要翻译**:

本文指出，判断模型是否真正具备新视角合成（NVS）能力的关键标准是可迁移性：从一个视频序列中提取的任何位姿表示，是否可以用于在另一个场景中重新渲染相同的相机轨迹。我们分析了先前自监督 NVS 的研究，发现其预测的位姿不具备可迁移性：同一组位姿在不同的三维场景中会导致不同的相机轨迹。为此，我们提出了 XFactor，首个无需几何先验的自监督模型，能够实现真正的 NVS。XFactor 将成对位姿估计与一种简单的输入输出增强方案相结合，联合实现了相机位姿与场景内容的解耦，并促进了几何推理。值得注意的是，我们展示了 XFactor 在无约束的潜在位姿变量下实现了可迁移性，无需任何三维归纳偏置或多视图几何概念——例如将位姿显式参数化为 SE(3) 元素。我们引入了一种新的指标来量化可迁移性，并通过大规模实验证明 XFactor 显著优于先前的无位姿 NVS Transformer，还通过探测实验表明潜在位姿与真实世界位姿高度相关。

---

## 93. Revela: Dense Retriever Learning via Language Modeling

**Revela：通过语言建模学习稠密检索器**

**OpenReview**: [https://openreview.net/forum?id=e7pAjJZJWb](https://openreview.net/forum?id=e7pAjJZJWb)

**Authors**: Fengyu Cai (Technische Universität Darmstadt), Tong Chen (University of Washington, Seattle), Xinran Zhao (CMU, Carnegie Mellon University), Sihao Chen (Microsoft), Hongming Zhang (Tencent AI Lab Seattle), Tongshuang Wu (School of Computer Science, Carnegie Mellon University), Iryna Gurevych, Heinz Koeppl (TU Darmstadt)

**Institutions**: Technische Universität Darmstadt, University of Washington, Seattle, CMU, Carnegie Mellon University, Microsoft, Tencent AI Lab Seattle, School of Computer Science, Carnegie Mellon University, TU Darmstadt

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Information Retrieval, Unsupervised Learning

**Abstract**:

Dense retrievers play a vital role in accessing external and specialized knowledge to augment language models (LMs). Training dense retrievers typically requires annotated query-document pairs, which are costly to create and scarce in specialized domains (e.g., code) or in complex settings (e.g., requiring reasoning). These practical challenges have sparked growing interest in self-supervised retriever learning.
Since LMs are trained to capture token-level dependencies through a self-supervised learning objective (i.e., next token prediction), we can analogously cast retrieval as learning dependencies among chunks of tokens. This analogy naturally leads to the question: How can we adapt self‑supervised learning objectives in the spirit of language modeling to train retrievers?

To answer this question, we introduce Revela, a unified and scalable training framework for self-supervised retriever learning via language modeling. Revela models semantic dependencies among documents by conditioning next token prediction on local and cross-document context through an in-batch attention mechanism. This attention is weighted by retriever-computed similarity scores, enabling the retriever to be optimized as part of language modeling. We evaluate Revela on domain-specific (CoIR), reasoning-intensive (BRIGHT), and general-domain (BEIR) benchmarks across various retriever backbones. Without annotated or synthetic query-document pairs, Revela surpasses larger supervised models and proprietary APIs on both CoIR and BRIGHT. It achieves BEIR's unsupervised SoTA with ~1000x less training data and 10x less compute. Performance increases with batch size and model size, highlighting Revela's scalability and its promise for self‑supervised retriever learning.

**摘要翻译**:

稠密检索器在访问外部和专业知识以增强语言模型（LMs）方面发挥着至关重要的作用。训练稠密检索器通常需要标注的查询-文档对，这不仅成本高昂，在专业领域（如代码）或复杂场景（如需要推理）中也十分稀缺。这些实际挑战推动了对自监督检索器学习的日益关注。由于 LMs 通过自监督学习目标（即下一个 token 预测）来捕获 token 级别的依赖关系，我们可以类比地将检索视为学习 token 块之间的依赖关系。这种类比自然引出了一个问题：如何以语言建模的精神改造自监督学习目标来训练检索器？

为回答这个问题，我们引入了 Revela，一个通过语言建模进行自监督检索器学习的统一且可扩展的训练框架。Revela 通过批内注意力机制，在局部上下文和跨文档上下文的条件下进行下一个 token 预测，从而建模文档间的语义依赖关系。该注意力由检索器计算的相似度分数加权，使检索器能够作为语言建模的一部分得到优化。我们在领域特定（CoIR）、推理密集型（BRIGHT）和通用领域（BEIR）基准上，使用多种检索器骨干网络对 Revela 进行了评估。在不使用标注或合成查询-文档对的情况下，Revela 在 CoIR 和 BRIGHT 上均超越了更大的监督模型和商业 API。它以约 1000 倍少的训练数据和 10 倍少的计算量达到了 BEIR 的无监督最优水平。性能随批大小和模型规模的增加而提升，彰显了 Revela 的可扩展性及其在自监督检索器学习方面的前景。

---

## 94. LLMs Get Lost In Multi-Turn Conversation

**LLM 在多轮对话中迷失方向**

**OpenReview**: [https://openreview.net/forum?id=VKGTGGcwl6](https://openreview.net/forum?id=VKGTGGcwl6)

**Authors**: Philippe Laban (Microsoft), Hiroaki Hayashi (Salesforce), Yingbo Zhou (Salesforce Research), Jennifer Neville (Purdue University)

**Institutions**: Microsoft, Salesforce, Salesforce Research, Purdue University

**Primary Area**: datasets and benchmarks

**Keywords**: multi-turn, underspecification, llm simulation

**TL;DR**: We discover that when LLMs take a wrong turn in a conversation, they get lost and do not recover.

**TL;DR翻译**: 我们发现，当 LLM 在对话中走错方向时，它们会迷失且无法恢复。

**Abstract**:

Large Language Models (LLMs) are conversational interfaces. As such, LLMs have the potential to assist their users not only when they can fully specify the task at hand, but also to help them define, explore, and refine what they need through multi-turn conversational exchange. Although analysis of LLM conversation logs has confirmed that underspecification occurs frequently in user instructions, LLM evaluation has predominantly focused on the single-turn, fully-specified instruction setting. In this work, we perform large-scale simulation experiments to compare LLM performance in single- and multi-turn settings. Our experiments confirm that all the top open- and closed-weight LLMs we test exhibit significantly lower performance in multi-turn conversations than single-turn, with an average drop of 39% across six generation tasks. Analysis of 200,000+ simulated conversations decomposes the performance degradation into two components: a minor loss in aptitude and a significant increase in unreliability. We find that LLMs often make assumptions in early turns and prematurely attempt to generate final solutions, on which they overly rely. In simpler terms, we discover that when LLMs take a wrong turn in a conversation, they get lost and do not recover.

**摘要翻译**:

大语言模型（LLMs）是对话式接口。因此，LLMs 不仅能在用户完全明确任务时提供帮助，还能通过多轮对话交互帮助用户定义、探索和细化需求。尽管对 LLM 对话日志的分析已证实用户指令中的欠指定现象普遍存在，但 LLM 评估主要集中在单轮、完全指定指令的设定上。本文通过大规模模拟实验比较了 LLM 在单轮和多轮设定下的表现。实验证实，我们测试的所有顶尖开源和闭源 LLM 在多轮对话中的表现均显著低于单轮对话，六项生成任务的平均性能下降达 39%。对 200,000 多个模拟对话的分析将性能下降分解为两个组成部分：能力的轻微下降和不可靠性的显著增加。我们发现，LLMs 往往在早期对话轮次中做出假设并过早尝试生成最终答案，随后过度依赖这些答案。简言之，我们发现当 LLMs 在对话中走错方向时，它们会迷失且无法恢复。

---

## 95. TTSDS2: Resources and Benchmark for Evaluating Human-Quality Text to Speech Systems

**TTSDS2：评估人类质量水平文本转语音系统的资源与基准**

**OpenReview**: [https://openreview.net/forum?id=uGai5lYHlV](https://openreview.net/forum?id=uGai5lYHlV)

**Authors**: Christoph Minixhofer (University of Edinburgh, University of Edinburgh), Ondrej Klejch, Peter Bell (University of Edinburgh, University of Edinburgh)

**Institutions**: University of Edinburgh, University of Edinburgh

**Primary Area**: datasets and benchmarks

**Keywords**: speech synthesis, distributional analysis, objective evaluation

**TL;DR**: With TTSDS2, we introduce a metric and benchmark for TTS, covering 14 languages, which consistently correlates with human judgements.

**TL;DR翻译**: 我们通过 TTSDS2 引入了一个涵盖 14 种语言的 TTS 评估指标和基准，该指标与人类判断始终保持一致的相关性。

**Abstract**:

Evaluation of Text to Speech (TTS) systems is challenging and resource-intensive. Subjective metrics such as Mean Opinion Score (MOS) are not easily comparable between works. Objective metrics are frequently used, but rarely validated against subjective ones. Both kinds of metrics are challenged by recent TTS systems capable of producing synthetic speech indistinguishable from real speech. In this work, we introduce Text to Speech Distribution Score 2 (TTSDS2), a more robust and improved version of TTSDS. Across a range of domains and languages, it is the only one out of 16 compared metrics to correlate with a Spearman correlation above 0.50 for every domain and subjective score evaluated. We also release a range of resources for evaluating synthetic speech close to real speech: A dataset with over 11,000 subjective opinion score ratings; a pipeline for recreating a multilingual test dataset to avoid data leakage; and a benchmark for TTS in 14 languages.

**摘要翻译**:

文本转语音（TTS）系统的评估既具有挑战性又需要大量资源。主观指标（如平均意见分，MOS）在不同研究之间难以直接比较。客观指标虽然被频繁使用，但很少针对主观指标进行验证。近期 TTS 系统能够生成与真实语音难以区分的合成语音，对两类指标都构成了挑战。本文提出了 Text to Speech Distribution Score 2（TTSDS2），一个更鲁棒的 TTSDS 改进版本。在多种领域和语言上，它是 16 个对比指标中唯一在每个领域和主观评分上 Spearman 相关系数均超过 0.50 的指标。我们还发布了一系列评估接近真实语音的合成语音的资源：包含超过 11,000 个主观评分的数据集；用于重建多语言测试数据集以避免数据泄漏的流程；以及涵盖 14 种语言的 TTS 基准。

---

## 96. Mamba-3: Improved Sequence Modeling using State Space Principles

**Mamba-3：基于状态空间原理的改进序列建模**

**OpenReview**: [https://openreview.net/forum?id=HwCvaJOiCj](https://openreview.net/forum?id=HwCvaJOiCj)

**Authors**: Aakash Lahoti (CMU, Carnegie Mellon University), Kevin Li (Carnegie Mellon University), Berlin Chen (Princeton University), Caitlin Wang (Princeton University), Aviv Bick (Carnegie Mellon University), J Zico Kolter (Carnegie Mellon University), Tri Dao (Princeton University), Albert Gu (Carnegie Mellon University)

**Institutions**: CMU, Carnegie Mellon University, Carnegie Mellon University, Princeton University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: State Space Models, Mamba, LLMs, Subquadratic Models

**TL;DR**: Mamba-3, an inference-first SSM that pushes on core SSM principles: improved discretization for better quality, complex dynamics for new capabilities, and MIMO updates for efficient inference.

**TL;DR翻译**: Mamba-3 是一个以推理优先为导向的 SSM，在核心 SSM 原理上进行了推进：改进的离散化以提升质量，复数动态特性以获得新能力，以及 MIMO 更新以实现高效推理。

**Abstract**:

The recent scaling of test-time compute for LLMs has restricted the practical deployment of models to those with strong capabilities that can generate high-quality outputs in an inference-efficient manner. While current Transformer-based models are the standard, their quadratic compute and linear memory bottlenecks have spurred the development of sub-quadratic models with linear-scaling compute with constant memory requirements. However, many recent linear-style models lack certain capabilities or lag behind in quality, and even their linear-time inference is not hardware-efficient. Guided by an inference-first perspective, we introduce three core methodological improvements inspired by the state-space model viewpoint of linear models. We combine a: 1) more expressive recurrence, 2) complex state update rule that enables richer state tracking, and 3) multi-input, multi-output formulation together, resulting in a stronger model that better exploits hardware parallelism during decoding. Together with architectural refinements, our **Mamba-3** model achieves significant gains across retrieval, state-tracking, and downstream language modeling tasks. Our new architecture sets the Pareto-frontier for performance under a fixed inference budget and outperforms strong baselines in a head-to-head comparison.

**摘要翻译**:

近期 LLM 测试时计算的扩展，使得实际部署仅限于那些能力强、能以推理高效的方式生成高质量输出的模型。虽然当前基于 Transformer 的模型是主流，但其二次方计算复杂度和线性内存瓶颈推动了亚二次方模型的发展，这些模型具有线性扩展的计算量和恒定的内存需求。然而，许多近期的线性风格模型缺乏某些能力或在质量上有所不足，甚至其线性时间推理也并非硬件高效的。在推理优先的视角指导下，我们引入了三项受状态空间模型视角启发的核心方法改进。我们将以下三者相结合：1）更具表达力的递归，2）支持更丰富状态追踪的复数状态更新规则，3）多输入多输出的表述形式，从而得到一个更强的模型，能够在解码时更好地利用硬件并行性。结合架构上的优化，我们的 **Mamba-3** 模型在检索、状态追踪和下游语言建模任务上取得了显著提升。我们的新架构在固定推理预算下设定了性能的 Pareto 前沿，并在直接比较中超越了强基线模型。

---

## 97. Is it Thinking or Cheating?  Detecting Implicit Reward Hacking by Measuring Reasoning Effort

**是在思考还是在作弊？通过测量推理努力检测隐式奖励黑客行为**

**OpenReview**: [https://openreview.net/forum?id=Gk7gLAtVDO](https://openreview.net/forum?id=Gk7gLAtVDO)

**Authors**: Xinpeng Wang (Ludwig-Maximilians-Universität München), Nitish Joshi (Google Deepmind), Barbara Plank (Ludwig-Maximilians-Universität München), Rico Angell (New York University), He He (New York University)

**Institutions**: Ludwig-Maximilians-Universität München, Google Deepmind, New York University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Reward Hacking Detection, Chain-of-Thought Monitoring, Reasoning Faithfulness

**TL;DR**: TRACE detects implicit reward hacking by measuring how quickly truncated reasoning suffices to pass verification, outperforming CoT monitoring and enabling hidden loopholes discovery..

**TL;DR翻译**: TRACE 通过测量截断推理多快即能通过验证来检测隐式奖励黑客行为，优于思维链监控方法，并能发现隐藏的漏洞。

**Abstract**:

Reward hacking, where a reasoning model exploits loopholes in a reward function to achieve high rewards without solving the intended task, poses a significant threat. This behavior may be explicit, i.e. verbalized in the model's chain-of-thought (CoT), or implicit, where the CoT appears benign thus bypasses CoT monitors. To detect implicit reward hacking, we propose TRACE (Truncated Reasoning AUC Evaluation). Our key observation is that hacking occurs when exploiting the loophole is easier than solving the actual task.
This means that the model is using less `effort' than required to achieve  high reward. TRACE quantifies effort by measuring how early a model's reasoning becomes sufficient to pass a verifier. We progressively truncate a model's CoT at various lengths and measure the verifier-passing rate at each cutoff. A hacking model, which takes a reasoning shortcut, will achieve a high passing rate with only a small fraction of its CoT, yielding a large area under the accuracy-vs-length curve. TRACE achieves over 65% gains over our strongest 72B CoT monitoring baseline in math, and over 30% gains over a 32B monitoring baseline in code. We further show that TRACE can discover unknown loopholes in the training environment. Overall, TRACE offers a scalable unsupervised approach for oversight where current monitoring methods prove ineffective.

**摘要翻译**:

奖励黑客行为——即推理模型利用奖励函数中的漏洞获取高奖励而不解决预期任务——构成重大威胁。这种行为可能是显式的，即在模型的思维链（CoT）中被明确表达；也可能是隐式的，即 CoT 看似正常从而绕过了 CoT 监控器。为检测隐式奖励黑客行为，我们提出了 TRACE（截断推理 AUC 评估）。我们的核心观察是，当利用漏洞比解决实际任务更容易时，黑客行为就会发生。这意味着模型使用了比获取高奖励所需更少的"努力"。TRACE 通过测量模型推理在多早阶段就足以通过验证器来量化努力程度。我们在不同长度处逐步截断模型的 CoT，并在每个截断点测量通过验证器的比率。采取推理捷径的黑客模型仅凭其 CoT 的一小部分就能达到高通过率，从而在准确率-长度曲线下产生较大面积。TRACE 在数学任务上比我们最强的 72B CoT 监控基线提升了超过 65%，在代码任务上比 32B 监控基线提升了超过 30%。我们还展示了 TRACE 能够发现训练环境中未知的漏洞。总体而言，TRACE 为当前监控方法失效的场景提供了一种可扩展的无监督监督方法。

---

## 98. Causal Structure Learning in Hawkes Processes with Complex Latent Confounder Networks

**具有复杂潜在混淆因子网络的 Hawkes 过程因果结构学习**

**OpenReview**: [https://openreview.net/forum?id=mA78uXqcnl](https://openreview.net/forum?id=mA78uXqcnl)

**Authors**: Songyao Jin (University of California, San Diego), Biwei Huang (University of California, San Diego)

**Institutions**: University of California, San Diego

**Primary Area**: causal reasoning

**Keywords**: Hawkes processes, causal discovery, latent subprocess model, structure learning, time series

**TL;DR**: We propose a method to uncover causal relationships in partially observed multivariate Hawkes processes, despite the presence of latent subprocesses, using a discrete-time representation and a two-phase iterative algorithm.

**TL;DR翻译**: 我们提出了一种方法，通过离散时间表示和两阶段迭代算法，在存在潜在子过程的情况下，揭示部分观测多元 Hawkes 过程中的因果关系。

**Abstract**:

Multivariate Hawkes process provides a powerful framework for modeling temporal dependencies and event-driven interactions in complex systems. While existing methods primarily focus on uncovering causal structures among observed subprocesses, real-world systems are often only partially observed, with latent subprocesses posing significant challenges. In this paper, we show that continuous-time event sequences can be represented by a discrete-time causal model as the time interval shrinks, and we leverage this insight to establish necessary and sufficient conditions for identifying latent subprocesses and the causal influences. Accordingly, we propose a two-phase iterative algorithm that alternates between inferring causal relationships among discovered subprocesses and uncovering new latent subprocesses, guided by path-based conditions that guarantee identifiability. Experiments on both synthetic and real-world datasets show that our method effectively recovers causal structures despite the presence of latent subprocesses.

**摘要翻译**:

多元 Hawkes 过程为建模复杂系统中的时间依赖关系和事件驱动交互提供了强大的框架。现有方法主要关注揭示观测子过程之间的因果结构，但现实世界的系统往往仅被部分观测，潜在子过程带来了重大挑战。本文表明，当时间间隔趋于零时，连续时间事件序列可以用离散时间因果模型来表示，并利用这一洞察建立了识别潜在子过程及因果影响的充分必要条件。据此，我们提出了一种两阶段迭代算法，在推断已发现子过程之间的因果关系和揭示新的潜在子过程之间交替进行，以基于路径的条件来保证可识别性。在合成数据集和真实世界数据集上的实验表明，尽管存在潜在子过程，我们的方法仍能有效恢复因果结构。

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

---

## 100. Radiometrically Consistent Gaussian Surfels for Inverse Rendering

**辐射度一致的高斯面元用于逆渲染**

**OpenReview**: [https://openreview.net/forum?id=lKqE7UuMvp](https://openreview.net/forum?id=lKqE7UuMvp)

**Authors**: Kyu Beom Han (Korea Advanced Institute of Science & Technology), Jaeyoon Kim (Korea Advanced Institute of Science & Technology), Woo Jae Kim (Korea Advanced Institute of Science and Technology), Jinhwan Seo (Korea Advanced Institute of Science & Technology), Sung-eui Yoon (KAIST)

**Institutions**: Korea Advanced Institute of Science & Technology, Korea Advanced Institute of Science and Technology, KAIST

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Radiometric Consistency, Indirect Illumination, Gaussian Splatting, Inverse Rendering

**TL;DR**: Radiometric Consistency for Gaussian Surfels provide accurate indirect illumination for inverse rendering

**TL;DR翻译**: 高斯面元的辐射度一致性为逆渲染提供了精确的间接光照

**Abstract**:

Inverse rendering with Gaussian Splatting has advanced rapidly, but accurately disentangling material properties from complex global illumination effects, particularly indirect illumination, remains a major challenge. Existing methods often query indirect radiance from Gaussian primitives pre-trained for novel-view synthesis. However, these pre-trained Gaussian primitives are supervised only towards limited training viewpoints, thus lack supervision for modeling indirect radiances from unobserved views. To address this issue, we introduce radiometric consistency, a novel physically-based constraint that provides supervision towards unobserved views by minimizing the residual between each Gaussian primitive's learned radiance and its physically-based rendered counterpart. Minimizing the residual for unobserved views establishes a self-correcting feedback loop that provides supervision from both physically-based rendering and novel-view synthesis, enabling accurate modeling of inter-reflection.
We then propose Radiometrically Consistent Gaussian Surfels (RadioGS), an inverse rendering framework built upon our principle by efficiently integrating radiometric consistency by utilizing  Gaussian surfels and 2D Gaussian ray tracing. We further propose a finetuning-based relighting strategy that adapts Gaussian surfel radiances to new illuminations within minutes, achieving low rendering cost ($<$10ms). Extensive experiments on existing inverse rendering benchmarks show that RadioGS outperforms existing Gaussian-based methods in inverse rendering, while retaining the computational efficiency.

**摘要翻译**:

基于 Gaussian Splatting 的逆渲染技术发展迅速，但从复杂的全局光照效果（尤其是间接光照）中准确分离材质属性仍是一个重大挑战。现有方法通常从为新视角合成预训练的高斯基元中查询间接辐射度。然而，这些预训练的高斯基元仅针对有限的训练视角进行了监督，缺乏对未观测视角间接辐射度建模的监督信号。为解决这一问题，我们引入了辐射度一致性，一种新的基于物理的约束，通过最小化每个高斯基元的学习辐射度与其基于物理渲染的对应辐射度之间的残差，为未观测视角提供监督。对未观测视角残差的最小化建立了一个自校正反馈回路，同时从基于物理的渲染和新视角合成两方面提供监督，从而实现对互反射的精确建模。基于此，我们提出了辐射度一致的高斯面元（RadioGS），一个通过利用高斯面元和二维高斯光线追踪来高效整合辐射度一致性的逆渲染框架。我们还提出了一种基于微调的重光照策略，能在数分钟内将高斯面元辐射度适配到新的光照条件，渲染开销低于 10 毫秒。在现有逆渲染基准上的大量实验表明，RadioGS 在逆渲染中优于现有基于高斯的方法，同时保持了计算效率。

---

## 101. Hubble: a Model Suite to Advance the Study of LLM Memorization

**Hubble：推进 LLM 记忆研究的模型套件**

**OpenReview**: [https://openreview.net/forum?id=ZfdnZhOP0k](https://openreview.net/forum?id=ZfdnZhOP0k)

**Authors**: Johnny Wei (University of Southern California), Ameya Godbole (University of Southern California), Mohammad Aflah Khan (MPI-SWS), Ryan Yixiang Wang (University of Southern California), Xiaoyuan Zhu (University of Southern California), James Flemings (University of Southern California), Nitya Kashyap (University of Southern California), Krishna P. Gummadi (MPI-SWS), Willie Neiswanger (University of Southern California), Robin Jia (University of Southern California)

**Institutions**: University of Southern California, MPI-SWS

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: memorization, copyright, privacy, test set contamination, membership inference, unlearning

**TL;DR**: Hubble is a suite of paired LLMs (largest 8B), where the perturbed models are trained in the same way as standard models but with text (e.g. book passages, biographies, and test sets) inserted and designed to emulate key memorization risks.

**TL;DR翻译**: Hubble 是一套成对的 LLM 套件（最大 8B），其中扰动模型的训练方式与标准模型相同，但插入了文本（如书籍段落、人物传记和测试集），旨在模拟关键的记忆风险。

**Abstract**:

We present Hubble, a suite of fully open-source large language models (LLMs) for the scientific study of LLM memorization. Hubble models come in standard and perturbed variants: standard models are pretrained on a large English corpus, and perturbed models are trained in the same way but with controlled insertion of text (e.g., book passages, biographies, and test sets) designed to emulate key memorization risks. Our core release includes 8 models---standard and perturbed models with 1B or 8B parameters, pretrained on 100B or 500B tokens---establishing that memorization risks are determined by the frequency of sensitive data relative to size of the training corpus (i.e., a password appearing once in a smaller corpus is memorized better than the same password in a larger corpus). Our release also includes 6 perturbed models with text inserted at different pretraining phases, showing that sensitive data without continued exposure can be forgotten. These findings suggest two best practices for addressing memorization risks: to dilute sensitive data by increasing the size of the training corpus, and to order sensitive data to appear earlier in training. Beyond these general empirical findings, Hubble enables a broad range of memorization research; for example, analyzing the biographies reveals how readily different types of private information are memorized. We also demonstrate that the randomized insertions in Hubble make it an ideal testbed for membership inference and machine unlearning, and invite the community to further explore, benchmark, and build upon our work.

**摘要翻译**:

我们推出了 Hubble，一套完全开源的大语言模型（LLMs），用于 LLM 记忆的科学研究。Hubble 模型包括标准版和扰动版两种变体：标准模型在大规模英语语料库上预训练，扰动模型以相同方式训练，但受控地插入了文本（如书籍段落、人物传记和测试集），旨在模拟关键的记忆风险。我们的核心发布包含 8 个模型——具有 1B 或 8B 参数、在 100B 或 500B token 上预训练的标准和扰动模型——确立了记忆风险由敏感数据相对于训练语料库规模的出现频率决定（即同一密码在较小语料库中出现一次比在较大语料库中更容易被记忆）。我们还发布了 6 个在不同预训练阶段插入文本的扰动模型，表明没有持续暴露的敏感数据可以被遗忘。这些发现提出了应对记忆风险的两个最佳实践：通过增加训练语料库规模来稀释敏感数据，以及将敏感数据安排在训练的较早阶段出现。除了这些一般性的实证发现外，Hubble 还能支持广泛的记忆研究；例如，分析人物传记可以揭示不同类型的隐私信息被记忆的容易程度。我们还证明了 Hubble 中的随机插入使其成为成员推断和机器遗忘的理想测试平台，并邀请社区在我们工作的基础上进一步探索、评测和拓展。

---

## 102. Differentially Private Domain Discovery

**差分隐私领域发现**

**OpenReview**: [https://openreview.net/forum?id=yBpzF8hp3J](https://openreview.net/forum?id=yBpzF8hp3J)

**Authors**: Vinod Raman (Google DeepMind), Travis Dick (Google), Matthew Joseph (Google)

**Institutions**: Google DeepMind, Google

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Differential Privacy, Partition Selection, Top-k Selection

**Abstract**:

We study several problems in differentially private domain discovery, where each user holds a subset of items from a shared but unknown domain, and the goal is to output an informative subset of items. For set union, we  show that the simple baseline Weighted Gaussian Mechanism (WGM) has a near-optimal $\ell_1$ missing mass guarantee on Zipfian data as well as a distribution-free $\ell_\infty$ missing mass guarantee. We then apply the WGM as a domain-discovery precursor for existing known-domain algorithms for private top-$k$ and $k$-hitting set and obtain new utility guarantees for their unknown domain variants. Finally, experiments demonstrate that all of our WGM-based methods are competitive with or outperform existing baselines for all three problems.

**摘要翻译**:

我们研究了差分隐私领域发现中的若干问题，其中每个用户持有来自一个共享但未知领域的元素子集，目标是输出一个信息丰富的元素子集。对于集合并集问题，我们证明简单的加权高斯机制（WGM）基线在 Zipf 分布数据上具有近乎最优的 $\ell_1$ 缺失质量保证，以及无分布假设的 $\ell_\infty$ 缺失质量保证。然后，我们将 WGM 作为领域发现的前置步骤，应用于现有的已知领域隐私 top-$k$ 和 $k$-命中集算法，并为其未知领域变体获得了新的效用保证。最后，实验表明我们所有基于 WGM 的方法在三个问题上均与现有基线具有同等竞争力或优于现有基线。

---

## 103. CauKer: Classification Time Series Foundation Models Can Be Pretrained on Synthetic Data

**CauKer：分类时间序列基础模型可以在合成数据上预训练**

**OpenReview**: [https://openreview.net/forum?id=xBW2FIfswU](https://openreview.net/forum?id=xBW2FIfswU)

**Authors**: Shifeng Xie (Télécom Paris), Vasilii Feofanov (42.com), Jianfeng Zhang (Huawei Technologies Ltd.), Themis Palpanas (Universite Paris Cite), Ievgen Redko (Huawei Technologies Ltd.)

**Institutions**: Télécom Paris, 42.com, Huawei Technologies Ltd., Universite Paris Cite

**Primary Area**: learning on time series and dynamical systems

**Keywords**: Time Series Foundation Model, Time Series Classification

**Abstract**:

Time series foundation models (TSFMs) have recently gained significant attention due to their strong zero-shot capabilities and widespread real-world applications. Such models typically require a computationally costly pretraining on large-scale, carefully curated collections of real-world sequences. To allow for a sample-efficient pretraining of TSFMs, we propose CauKer, a novel algorithm designed to generate diverse, causally coherent synthetic time series with realistic trends, seasonality, and nonlinear interactions. CauKer combines Gaussian Process (GP) kernel composition with Structural Causal Models (SCM) to produce data for sample-efficient pretraining of state-of-the-art classification TSFMs having different architectures and following different pretraining approaches. Additionally, our experiments reveal that CauKer-generated datasets exhibit clear scaling laws for both dataset size (10K to 10M samples) and model capacity (1M to 783M parameters), unlike real-world datasets, which display irregular scaling behavior.

**摘要翻译**:

时间序列基础模型（TSFMs）近期因其强大的零样本能力和广泛的实际应用而受到显著关注。此类模型通常需要在大规模、精心策划的真实世界序列集合上进行计算成本高昂的预训练。为实现 TSFMs 的样本高效预训练，我们提出了 CauKer，一种旨在生成具有逼真趋势、季节性和非线性交互的多样化因果一致性合成时间序列的新算法。CauKer 将高斯过程（GP）核组合与结构因果模型（SCM）相结合，为具有不同架构和不同预训练方法的最先进分类 TSFMs 生成样本高效的预训练数据。此外，我们的实验表明，CauKer 生成的数据集在数据集规模（10K 到 10M 样本）和模型容量（1M 到 783M 参数）上均呈现出清晰的缩放规律，而真实世界数据集则表现出不规则的缩放行为。

---

## 104. Non-Convex Federated Optimization under Cost-Aware Client Selection

**成本感知客户端选择下的非凸联邦优化**

**OpenReview**: [https://openreview.net/forum?id=FnaDv6SMd9](https://openreview.net/forum?id=FnaDv6SMd9)

**Authors**: Xiaowen Jiang (CISPA Helmholtz Center for Information Security), Anton Rodomanov (CISPA), Sebastian U Stich (CISPA Helmholtz Center)

**Institutions**: CISPA Helmholtz Center for Information Security, CISPA, CISPA Helmholtz Center

**Primary Area**: optimization

**Keywords**: Client Sampling, SAGA, Second-order Similarity, Composite Gradient Method, Variance Reduction

**TL;DR**: We propose a composite gradient method with SAGA and recursive gradient estimator for non-convex federated optimization that can exploit second-order similarity and achieve high communication and local computation efficiency.

**TL;DR翻译**: 我们提出了一种结合 SAGA 和递归梯度估计器的复合梯度方法，用于非凸联邦优化，能够利用二阶相似性并实现高通信和本地计算效率。

**Abstract**:

Different federated optimization algorithms typically employ distinct client-selection strategies: some methods communicate only with a randomly sampled subset of clients at each round, while others need to periodically communicate with all clients or use a hybrid scheme that combines both strategies. However, existing metrics for comparing optimization methods typically do not distinguish between these strategies, which often incur different communication costs in practice. To address this disparity, we introduce a simple and natural model of federated optimization that quantifies communication and local computation complexities. This new model allows for several commonly used client-selection strategies and explicitly associates each with a distinct cost. Within this setting, we propose a new algorithm that achieves the best-known communication and local complexities among existing federated optimization methods for non-convex optimization. This algorithm is based on the inexact composite gradient method with a carefully constructed gradient estimator and a special procedure for solving the auxiliary subproblem at each iteration. The gradient estimator is based on SAGA, a popular variance-reduced gradient estimator. We first derive a new variance bound for it, showing that SAGA can exploit functional similarity. We then introduce the Recursive-Gradient technique as a general way to potentially improve the error bound of a given conditionally unbiased gradient estimator, including both SAGA and SVRG. By applying this technique to SAGA, we obtain a new estimator, RG-SAGA, which has an improved error bound compared to the original one.

**摘要翻译**:

不同的联邦优化算法通常采用不同的客户端选择策略：一些方法在每一轮仅与随机采样的客户端子集通信，另一些方法则需要周期性地与所有客户端通信，或采用结合两种策略的混合方案。然而，现有的优化方法比较指标通常不区分这些策略，而这些策略在实践中往往产生不同的通信成本。为解决这一差异，我们引入了一个简单自然的联邦优化模型，量化了通信和本地计算复杂度。这一新模型允许采用多种常用的客户端选择策略，并为每种策略显式地关联不同的成本。在此设定下，我们提出了一种新算法，在非凸优化的现有联邦优化方法中实现了已知最优的通信和本地计算复杂度。该算法基于不精确复合梯度方法，配合精心构造的梯度估计器和在每次迭代中求解辅助子问题的特殊过程。梯度估计器基于 SAGA，一种流行的方差缩减梯度估计器。我们首先推导了其新的方差界，表明 SAGA 能够利用函数相似性。然后我们引入递归梯度技术，作为一种可能改善给定条件无偏梯度估计器（包括 SAGA 和 SVRG）误差界的通用方法。将此技术应用于 SAGA，我们得到了一个新的估计器 RG-SAGA，其误差界优于原始版本。

---

## 105. Verifying Chain-of-Thought Reasoning via Its Computational Graph

**通过计算图验证思维链推理**

**OpenReview**: [https://openreview.net/forum?id=CxiNICq0Rr](https://openreview.net/forum?id=CxiNICq0Rr)

**Authors**: Zheng Zhao (University of Edinburgh, University of Edinburgh), Yeskendir Koishekenov (Facebook), Xianjun Yang (Facebook), Naila Murray (Meta AI), Nicola Cancedda (Meta)

**Institutions**: University of Edinburgh, University of Edinburgh, Facebook, Meta AI, Meta

**Primary Area**: interpretability and explainable AI

**Keywords**: Mechanistic Interpretability, Chain-of-Thought Reasoning, Attribution Graphs

**TL;DR**: We introduce CRV, a white-box methodology that treats attribution graphs as execution traces, and use it to provide evidence that flawed reasoning has a verifiable computational structure.

**TL;DR翻译**: 我们引入了 CRV，一种将归因图视为执行轨迹的白盒方法，并用它提供了有缺陷推理具有可验证计算结构的证据。

**Abstract**:

Current Chain-of-Thought (CoT) verification methods predict reasoning correctness based on outputs (black-box) or activations (gray-box), but offer limited insight into \textit{why} a computation fails. We introduce a white-box method: \textbf{Circuit-based Reasoning Verification (CRV)}. We hypothesize that attribution graphs of correct CoT steps, viewed as \textit{execution traces} of the model's latent reasoning circuits, possess distinct structural fingerprints from those of incorrect steps. By training a classifier on structural features of these graphs, we show that these traces contain a powerful signal of reasoning errors. Our white-box approach yields novel scientific insights unattainable by other methods. (1) We demonstrate that structural signatures of error are highly predictive, establishing the viability of verifying reasoning directly via its computational graph. (2) We find these signatures to be highly domain-specific, revealing that failures in different reasoning tasks manifest as distinct computational patterns. (3) We provide evidence that these signatures are not merely correlational; by using our analysis to guide targeted interventions on individual transcoder features, we successfully correct the model's faulty reasoning. Our work shows that, by scrutinizing a model's computational process, we can move from simple error detection to a deeper, causal understanding of LLM reasoning.

**摘要翻译**:

当前的思维链（CoT）验证方法基于输出（黑盒）或激活值（灰盒）来预测推理正确性，但对计算失败的原因提供的洞察有限。我们引入了一种白盒方法：**基于电路的推理验证（CRV）**。我们假设正确 CoT 步骤的归因图——被视为模型潜在推理电路的执行轨迹——与错误步骤的归因图具有不同的结构指纹。通过在这些图的结构特征上训练分类器，我们表明这些轨迹包含了推理错误的强有力信号。我们的白盒方法产生了其他方法无法获得的新颖科学洞察。（1）我们证明了错误的结构特征具有高度预测性，确立了通过计算图直接验证推理的可行性。（2）我们发现这些特征具有高度的领域特异性，揭示了不同推理任务中的失败表现为不同的计算模式。（3）我们提供了证据表明这些特征不仅仅是相关性的；通过利用我们的分析来指导对单个转码器特征的定向干预，我们成功纠正了模型的错误推理。我们的工作表明，通过审视模型的计算过程，我们可以从简单的错误检测迈向对 LLM 推理的更深层次的因果理解。

---

## 106. How Learning Rate Decay Wastes Your Best Data in Curriculum-Based LLM Pretraining

**学习率衰减如何浪费你在课程式 LLM 预训练中的最佳数据**

**OpenReview**: [https://openreview.net/forum?id=T5wkZJqzkz](https://openreview.net/forum?id=T5wkZJqzkz)

**Authors**: Kairong Luo (Tsinghua University), Zhenbo Sun (Tsinghua University, Tsinghua University), Haodong Wen (Tsinghua University), Xinyu Shi (, Tsinghua University), Jiarui Cui (Tsinghua University), Chenyi Dang (Tsinghua University), Kaifeng Lyu (Tsinghua University), Wenguang Chen (Tsinghua University, Tsinghua University)

**Institutions**: Tsinghua University, Tsinghua University, Tsinghua University, , Tsinghua University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLM pretraining, Curriculum Learning, Model Weight Average

**TL;DR**: Use model weight average to enhance curriculum learning in LLM pretraining.

**TL;DR翻译**: 使用模型权重平均来增强 LLM 预训练中的课程学习。

**Abstract**:

Due to the scarcity of high-quality data, large language models (LLMs) are often trained on mixtures of data with varying quality levels, even after sophisticated data curation. A natural approach to better leverage high-quality data is curriculum-based pretraining, where the model is trained on data sorted in ascending order of quality as determined by a quality metric. However, prior studies have reported limited improvements from such curriculum-based pretraining strategies. This work identifies a critical factor constraining these methods: the incompatibility between the ascending data quality order and the decaying learning rate (LR) schedule. We find that while curriculum-based training substantially outperforms random shuffling when using a constant LR, its advantage diminishes under standard LR decay schedules. Our experiments show this incompatibility can be mitigated by two simple strategies: (1) employing a more moderate LR decay schedule, where the final LR is only moderately smaller than the peak LR, and (2) replacing LR decay with model averaging, i.e., computing a weighted average of the final few checkpoints. By combining these strategies, we improve the average score on a suite of standard benchmarks by 1.64% over random shuffling, without additional data refinement. Validated on 1.5B-parameter models trained over 30B tokens with various data-quality metrics, our findings call for a re-evaluation of curriculum-based LLM pretraining and underscore the potential of co-designing data curricula with optimization methods.

**摘要翻译**:

由于高质量数据的稀缺性，大语言模型（LLMs）即使经过精细的数据策划，仍常常在质量水平各异的混合数据上进行训练。更好地利用高质量数据的一种自然方法是课程式预训练，即按质量指标确定的升序排列数据来训练模型。然而，先前研究报告称此类课程式预训练策略的改进有限。本文识别出限制这些方法的一个关键因素：数据质量升序与学习率（LR）衰减策略之间的不兼容性。我们发现，在使用恒定 LR 时课程式训练显著优于随机打乱，但在标准 LR 衰减策略下其优势消退。实验表明，这种不兼容性可通过两个简单策略来缓解：（1）采用更温和的 LR 衰减策略，使最终 LR 仅适度小于峰值 LR；（2）用模型平均替代 LR 衰减，即计算最后几个检查点的加权平均。通过结合这两种策略，我们在一组标准基准上的平均分数比随机打乱提高了 1.64%，且无需额外的数据精炼。在使用多种数据质量指标、基于 1.5B 参数模型训练 30B token 的实验中进行了验证，我们的发现呼吁重新审视课程式 LLM 预训练，并强调了将数据课程与优化方法协同设计的潜力。

---

## 107. Probabilistic Kernel Function for Fast Angle Testing

**用于快速角度检验的概率核函数**

**OpenReview**: [https://openreview.net/forum?id=nCsF3Bsn2n](https://openreview.net/forum?id=nCsF3Bsn2n)

**Authors**: Kejing Lu (Yamanashi University), Chuan Xiao (Osaka University), Yoshiharu Ishikawa (Nagoya University)

**Institutions**: Yamanashi University, Osaka University, Nagoya University

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: Randomized algorithm, Locality Sensitive Hashing, Directional statistics

**Abstract**:

In this paper, we study the angle testing problem in high-dimensional Euclidean spaces and propose two projection-based probabilistic kernel functions, one designed for angle comparison and the other for angle thresholding. Unlike existing approaches that rely on random projection vectors drawn from Gaussian distributions, our approach leverages reference angles and employs a deterministic structure for the projection vectors. Notably, our kernel functions do not require asymptotic assumptions, such as the number of projection vectors tending to infinity, and can be both theoretically and experimentally shown to outperform Gaussian-distribution-based kernel functions. We further apply the proposed kernel function to Approximate Nearest Neighbor Search (ANNS) and demonstrate that our approach achieves a 2.5X-3X higher query-per-second (QPS) throughput compared to the state-of-the-art graph-based search algorithm HNSW.

**摘要翻译**:

本文研究了高维欧氏空间中的角度检验问题，提出了两种基于投影的概率核函数，一种用于角度比较，另一种用于角度阈值判定。与依赖从高斯分布中抽取的随机投影向量的现有方法不同，我们的方法利用参考角度并为投影向量采用确定性结构。值得注意的是，我们的核函数不需要渐近假设（如投影向量数趋向无穷大），并且从理论和实验上均被证明优于基于高斯分布的核函数。我们进一步将所提出的核函数应用于近似最近邻搜索（ANNS），并展示了我们的方法与最先进的基于图的搜索算法 HNSW 相比，每秒查询量（QPS）吞吐量提高了 2.5 到 3 倍。

---

## 108. RefineStat: Efficient Exploration for Probabilistic Program Synthesis

**RefineStat：面向概率程序合成的高效探索**

**OpenReview**: [https://openreview.net/forum?id=SAl337ZX5d](https://openreview.net/forum?id=SAl337ZX5d)

**Authors**: Madhav Kanda (University of Illinois at Urbana-Champaign), Shubham Ugare (Meta), Sasa Misailovic (University of Illinois, Urbana Champaign)

**Institutions**: University of Illinois at Urbana-Champaign, Meta, University of Illinois, Urbana Champaign

**Primary Area**: probabilistic methods (Bayesian methods, variational inference, sampling, UQ, etc.)

**Keywords**: Probabilistic Programming, Constrained Generation

**Abstract**:

Probabilistic programming offers a powerful framework for modeling uncertainty, yet statistical model discovery in this domain entails navigating an immense search space under strict domain‐specific constraints. When small language models are tasked with generating probabilistic programs, they frequently produce outputs that suffer from both syntactic, and semantic errors, such as flawed inference constructs. Motivated by probabilistic programmers' domain expertise and debugging strategies, we introduce RefineStat, a language model–driven framework that enforces semantic constraints ensuring synthesized programs contain valid distributions, well‐formed parameters, and then applies diagnostic‐aware refinement by resampling prior or likelihood components whenever reliability checks fail. We evaluate RefineStat on multiple probabilistic-programming code-generation tasks using smaller language models (SLMs) and find that it produces programs that are both syntactically sound and statistically reliable, often matching or surpassing those from closed-source large language models (e.g., OpenAI o3).

**摘要翻译**:

概率编程为不确定性建模提供了强大的框架，然而该领域中的统计模型发现需要在严格的领域特定约束下遍历巨大的搜索空间。当小型语言模型被要求生成概率程序时，它们经常产出存在语法和语义错误（如有缺陷的推断构造）的输出。受概率编程人员的领域专业知识和调试策略的启发，我们引入了 RefineStat，一个由语言模型驱动的框架，该框架强制执行语义约束以确保合成程序包含有效的分布和良好的参数，并在可靠性检查失败时通过重新采样先验或似然组件进行诊断感知的细化。我们在多个概率编程代码生成任务上使用较小的语言模型（SLMs）评估了 RefineStat，发现它生成的程序在语法上正确且在统计上可靠，通常能匹配或超越闭源大语言模型（如 OpenAI o3）的表现。

---

## 109. Scaling Atomistic Protein Binder Design with Generative Pretraining and Test-Time Compute

**通过生成式预训练和测试时计算扩展原子级蛋白质结合物设计**

**OpenReview**: [https://openreview.net/forum?id=qmCpJtFZra](https://openreview.net/forum?id=qmCpJtFZra)

**Authors**: Kieran Didi (NVIDIA), Zuobai Zhang (Mila - Université de Montréal), Guoqing Zhou (NVIDIA), Danny Reidenbach (NVIDIA), Zhonglin Cao (NVIDIA), Sooyoung Cha (Seoul National University), Tomas Geffner (NVIDIA), Christian Dallago (Duke University), Jian Tang (HEC Montreal), Michael M. Bronstein (Aithyra), Martin Steinegger (Seoul National University), Emine Kucukbenli (NVIDIA), Arash Vahdat (NVIDIA), Karsten Kreis (NVIDIA)

**Institutions**: NVIDIA, Mila - Université de Montréal, Seoul National University, Duke University, HEC Montreal, Aithyra

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: binder design, protein design, flow matching, hallucination, inference-time scaling, generative modeling, diffusion models

**TL;DR**: We introduce a novel method for state-of-the-art structure-based protein binder design that combines flow matching-based generative pretraining with inference-time compute scaling techniques.

**TL;DR翻译**: 我们提出了一种用于最先进结构基蛋白质结合物设计的新方法，将基于 flow matching 的生成式预训练与推理时计算扩展技术相结合。

**Abstract**:

Protein interaction modeling is central to protein design, which has been transformed by machine learning with broad applications in drug discovery and beyond. In this landscape, structure-based de novo binder design is most often cast as either conditional generative modeling or sequence optimization via structure predictors ("hallucination"). We argue that this is a false dichotomy and propose Complexa, a novel fully atomistic binder generation method unifying both paradigms. We extend recent flow-based latent protein generation architecture and leverage the domain-domain interactions of monomeric computationally predicted protein structures to construct Teddymer, a new large-scale dataset of synthetic binder-target pairs for pretraining. Combined with high-quality experimental multimers, this enables training a strong base model. We then perform inference-time optimization with this generative prior, unifying the strengths of previously distinct generative and hallucination methods. Complexa sets a new state of the art in computational binder design benchmarks: it delivers markedly higher in-silico success rates than existing generative approaches, and our novel test-time optimization strategies greatly outperform previous hallucination methods under normalized compute budgets. We further demonstrate explicit interface hydrogen bond optimization, fold class-guided binder generation, and extensions to small molecule targets and enzyme design tasks, again surpassing prior methods. Code, models and new data will be publicly released.

**摘要翻译**:

蛋白质相互作用建模是蛋白质设计的核心，机器学习已深刻变革了该领域，在药物发现等方面有广泛应用。在这一格局中，基于结构的从头结合物设计通常被建模为条件生成建模或通过结构预测器进行序列优化（"幻觉"法）。我们认为这是一种错误的二元对立，并提出了 Complexa，一种统一两种范式的新型全原子级结合物生成方法。我们扩展了近期基于流的潜在蛋白质生成架构，并利用计算预测的单体蛋白质结构的结构域-结构域相互作用来构建 Teddymer，一个用于预训练的新大规模合成结合物-靶标对数据集。结合高质量的实验多聚体，这使得强基础模型的训练成为可能。随后我们利用这一生成式先验进行推理时优化，统一了此前各自独立的生成方法和幻觉方法的优势。Complexa 在计算结合物设计基准上达到了新的最先进水平：其计算机模拟成功率显著高于现有生成方法，我们新颖的测试时优化策略在标准化计算预算下大幅超越了先前的幻觉方法。我们还展示了显式界面氢键优化、折叠类别引导的结合物生成，以及对小分子靶标和酶设计任务的扩展，均再次超越了先前方法。代码、模型和新数据将公开发布。

---

## 110. Structured Flow Autoencoders: Learning Structured Probabilistic Representations with Flow Matching

**结构化流自编码器：通过 Flow Matching 学习结构化概率表示**

**OpenReview**: [https://openreview.net/forum?id=KYdfvF2SZN](https://openreview.net/forum?id=KYdfvF2SZN)

**Authors**: Yidan Xu, Yixin Wang (University of Michigan - Ann Arbor), XuanLong Nguyen (University of Michigan)

**Institutions**: University of Michigan - Ann Arbor, University of Michigan

**Primary Area**: probabilistic methods (Bayesian methods, variational inference, sampling, UQ, etc.)

**Keywords**: Flow Matching, Probabilistic Model, Representation Learning, Probabilistic Graphical Model, Autoencoder

**Abstract**:

Flow matching has proven to be a powerful density estimator, yet it often fails to explicitly capture the rich inherent latent structure of complex data. To address this limitation, we introduce Structured Flow Autoencoders (SFA), a family of probabilistic models that augments Continuous Normalizing Flows (CNFs) with graphical models. At the core of SFA is a novel flow matching based objective, which explicitly accounts for latent variables, enabling simultaneous learning of likelihood and posterior. We demonstrate the versatility of SFA across settings, including models with continuous and mixture latent variables, as well as latent dynamical systems. Empirical studies show that SFA outperforms Variational Autoencoders (VAE) and their graphical model extensions, achieving better data fit while simultaneously retaining meaningful latent variables as structured representations.

**摘要翻译**:

Flow matching 已被证明是一种强大的密度估计器，但它往往无法显式捕获复杂数据中丰富的内在潜在结构。为解决这一局限，我们引入了结构化流自编码器（SFA），一族将连续归一化流（CNFs）与图模型相结合的概率模型。SFA 的核心是一种新颖的基于 flow matching 的目标函数，该目标函数显式考虑了潜在变量，使得似然和后验能够被同时学习。我们在多种设定下展示了 SFA 的多功能性，包括具有连续潜在变量、混合潜在变量以及潜在动力系统的模型。实证研究表明，SFA 优于变分自编码器（VAE）及其图模型扩展，在获得更好的数据拟合的同时保留了有意义的潜在变量作为结构化表示。

---

## 111. Plug-and-Play Compositionality for Boosting Continual Learning with Foundation Models

**即插即用的组合性增强基于基础模型的持续学习**

**OpenReview**: [https://openreview.net/forum?id=22hBwIf7OC](https://openreview.net/forum?id=22hBwIf7OC)

**Authors**: Weiduo Liao (City University of Hong Kong), Fei Han (The Hong Kong University of Science and Technology), Hisao Ishibuchi (Southern University of Science and Technology), Qingfu Zhang (City University of Hong Kong), Ying Wei (Zhejiang University)

**Institutions**: City University of Hong Kong, The Hong Kong University of Science and Technology, Southern University of Science and Technology, Zhejiang University

**Primary Area**: transfer learning, meta learning, and lifelong learning

**Keywords**: Continual learning

**Abstract**:

Vision learners often struggle with catastrophic forgetting due to their reliance on class recognition by comparison, rather than understanding classes as compositions of representative concepts.
This limitation is prevalent even in state-of-the-art continual learners with foundation models and worsens when current tasks contain few classes.
Inspired by the recent success of concept-level understanding in mitigating forgetting, we design a universal framework CompSLOT to guide concept learning across diverse continual learners.
Leveraging the progress of object-centric learning in parsing semantically meaningful slots from images, we tackle the challenge of learning slot extraction from ImageNet-pretrained vision transformers by analyzing meaningful concept properties.
We further introduce a primitive selection and aggregation mechanism to harness concept-level image understanding.
Additionally, we propose a method-agnostic self-supervision approach to distill sample-wise concept-based similarity information into the classifier, reducing reliance on incorrect or partial concepts for classification.
Experiments show CompSLOT significantly enhances various continual learners and provides a universal concept-level module for the community.

**摘要翻译**:

视觉学习器常常因依赖于通过比较进行类别识别而非将类别理解为代表性概念的组合而遭受灾难性遗忘的困扰。这一局限性即使在使用基础模型的最先进持续学习器中也普遍存在，且在当前任务包含较少类别时会加剧。受概念级理解在缓解遗忘方面取得成功的启发，我们设计了一个通用框架 CompSLOT 来引导多种持续学习器中的概念学习。利用以对象为中心的学习在从图像中解析语义有意义的槽方面的进展，我们通过分析有意义的概念属性来解决从 ImageNet 预训练视觉 Transformer 中学习槽提取的挑战。我们还引入了基元选择和聚合机制以利用概念级图像理解。此外，我们提出了一种与方法无关的自监督方法，将基于样本的概念相似性信息蒸馏到分类器中，减少了对不正确或部分概念的分类依赖。实验表明 CompSLOT 显著增强了各种持续学习器，并为社区提供了一个通用的概念级模块。

---

## 112. Generating metamers of human scene understanding

**生成人类场景理解的等效体**

**OpenReview**: [https://openreview.net/forum?id=cSDXx8V6K9](https://openreview.net/forum?id=cSDXx8V6K9)

**Authors**: Ritik Raina (State University of New York at Stony Brook), Abe Leite (State University of New York at Stony Brook), Alexandros Graikos (Stony Brook University), Seoyoung Ahn (University of California, Berkeley), Dimitris Samaras (Stony Brook University), Greg Zelinsky (State University of New York at Stony Brook)

**Institutions**: State University of New York at Stony Brook, Stony Brook University, University of California, Berkeley

**Primary Area**: applications to neuroscience & cognitive science

**Keywords**: human scene understanding, generative modeling

**Abstract**:

Human vision combines low-resolution "gist" information from the visual periphery with sparse but high-resolution information from fixated locations to construct a coherent understanding of a visual scene. In this paper, we introduce MetamerGen, a tool for generating scenes that are aligned with latent human scene representations. MetamerGen is a latent diffusion model that combines peripherally obtained scene gist information with information obtained from scene-viewing fixations to generate image metamers for what humans understand after viewing a scene. Generating images from both high and low resolution (i.e. "foveated") inputs constitutes a novel image-to-image synthesis problem, which we tackle by introducing a dual-stream representation of the foveated scenes consisting of DINOv2 tokens that fuse detailed features from fixated areas with peripherally degraded features capturing scene context. To evaluate the perceptual alignment of MetamerGen generated images to latent human scene representations, we conducted a same-different behavioral experiment where participants were asked for a "same" or "different" response between the generated and the original image. With that, we identify scene generations that are indeed metamers for the latent scene representations formed by the viewers. MetamerGen is a powerful tool for understanding scene understanding. Our proof-of-concept analyses uncovered specific features at multiple levels of visual processing that contributed to human judgments. While it can generate metamers even conditioned on random fixations, we find that high-level semantic alignment most strongly predicts metamerism when the generated scenes are conditioned on viewers' own fixated regions.

**摘要翻译**:

人类视觉将来自视觉外围的低分辨率"概要"信息与来自注视点的稀疏但高分辨率信息相结合，构建出对视觉场景的连贯理解。本文提出了 MetamerGen，一种用于生成与潜在人类场景表征相匹配的场景的工具。MetamerGen 是一个潜在扩散模型，它将从外围获得的场景概要信息与从场景注视中获得的信息相结合，生成与人类观看场景后所理解内容对应的图像等效体。从高分辨率和低分辨率（即"中心凹化"）输入生成图像构成了一个新颖的图像到图像合成问题，我们通过引入中心凹化场景的双流表示来解决，该表示由 DINOv2 token 组成，融合了注视区域的精细特征和捕获场景上下文的外围退化特征。为评估 MetamerGen 生成图像与潜在人类场景表征的感知对齐程度，我们进行了一项"相同-不同"行为实验，要求参与者对生成图像和原始图像做出"相同"或"不同"的判断。由此，我们识别出确实是观察者所形成的潜在场景表征的等效体的场景生成结果。MetamerGen 是理解场景理解的有力工具。我们的概念验证分析揭示了在多个视觉处理层次上对人类判断有贡献的特定特征。虽然即使基于随机注视点也能生成等效体，但我们发现当生成场景以观察者自身注视区域为条件时，高层语义对齐对等效体性的预测力最强。

---

## 113. Efficient Resource-Constrained Training of Transformers via Subspace Optimization

**通过子空间优化实现资源受限条件下 Transformer 的高效训练**

**OpenReview**: [https://openreview.net/forum?id=0nvQ5kHXf4](https://openreview.net/forum?id=0nvQ5kHXf4)

**Authors**: Le-Trung Nguyen (Télécom Paris), Enzo Tartaglione (Télécom Paris), Van-Tam Nguyen (Télécom Paris)

**Institutions**: Télécom Paris

**Primary Area**: optimization

**Keywords**: Deep Learning, Computer Vision, Compression, Low rank

**TL;DR**: We propose a novel method that enables training vision transformer models within a low-rank subspace to optimize computational resources, making on-device learning practically feasible.

**TL;DR翻译**: 我们提出了一种新方法，能够在低秩子空间内训练视觉 Transformer 模型以优化计算资源，使端侧学习切实可行。

**Abstract**:

As AI increasingly shapes daily life, energy consumption and data privacy have become pressing concerns. On-device learning trains models directly on edge devices, cutting energy consumption and safeguarding data privacy. However, the expanding scale of modern neural networks creates a major obstacle for on-device training. Although prior work has concentrated on compact convolutional architectures, we instead apply subspace-based training to transformer models. Motivated by the idea that a model's essential information lies in a fixed subspace, we introduce Weight-Activation Subspace Iteration (WASI), a method that mitigates the memory bottleneck of backpropagation and boosts inference efficiency in transformer models by restricting training to this subspace. Our results demonstrate that WASI maintains accuracy comparable to vanilla training while reducing memory usage by up to $62\times$ and computational cost (FLOPs) by up to $2\times$. On a Raspberry Pi 5, WASI achieves roughly $1.4\times$ faster training and inference than vanilla training. The code is available at https://github.com/Le-TrungNguyen/ICLR2026-WASI.git.

**摘要翻译**:

随着人工智能日益深入日常生活，能源消耗和数据隐私已成为紧迫的关注点。端侧学习直接在边缘设备上训练模型，既降低了能源消耗，又保障了数据隐私。然而，现代神经网络不断扩大的规模为端侧训练带来了重大障碍。尽管先前的工作主要集中在紧凑型卷积架构上，我们转而将基于子空间的训练应用于 Transformer 模型。基于模型的核心信息存在于固定子空间中这一思想，我们提出了权重-激活子空间迭代（WASI）方法，通过将训练限制在该子空间内，缓解了反向传播的内存瓶颈并提升了 Transformer 模型的推理效率。实验结果表明，WASI 在保持与标准训练相当精度的同时，将内存使用降低了高达 $62\times$，计算成本（FLOPs）降低了高达 $2\times$。在 Raspberry Pi 5 上，WASI 的训练和推理速度比标准训练快约 $1.4\times$。代码已开源于 https://github.com/Le-TrungNguyen/ICLR2026-WASI.git。

---

## 114. Learning with Dual-level Noisy Correspondence for Multi-modal Entity Alignment

**基于双层噪声对应关系学习的多模态实体对齐**

**OpenReview**: [https://openreview.net/forum?id=mytIKuRsSE](https://openreview.net/forum?id=mytIKuRsSE)

**Authors**: Haobin Li (School of Software Engineering, Sichuan University, Sichuan University), Yijie Lin (Sichuan University), Peng Hu (Sichuan University), Mouxing Yang (Sichuan University), Xi Peng (Sichuan University)

**Institutions**: School of Software Engineering, Sichuan University, Sichuan University, Sichuan University

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Noisy correspondence; Multi-modal entity alignment.

**Abstract**:

Multi-modal entity alignment (MMEA) aims to identify equivalent entities across heterogeneous multi-modal knowledge graphs (MMKGs), where each entity is described by attributes from various modalities. Existing methods typically assume that both intra-entity and inter-graph correspondences are faultless, which is often violated in real-world MMKGs due to the reliance on expert annotations.
In this paper, we reveal and study a highly practical yet under-explored problem in MMEA, termed Dual-level Noisy Correspondence (DNC).
DNC refers to misalignments in both intra-entity (entity-attribute) and inter-graph (entity-entity and attribute-attribute) correspondences.
To address the DNC problem, we propose a robust MMEA framework termed RULE. RULE first estimates the reliability of both intra-entity and inter-graph correspondences via a dedicated two-fold principle. Leveraging the estimated reliabilities, RULE mitigates the negative impact of intra-entity noise during attribute fusion and prevents overfitting to noisy inter-graph correspondences during inter-graph discrepancy elimination. Beyond the training-time designs, RULE further incorporates a correspondence reasoning module that uncovers the underlying attribute-attribute connection across graphs, guaranteeing more accurate equivalent entity identification.
Extensive experiments on five benchmarks verify the effectiveness of our method against the DNC compared with seven state-of-the-art methods.
The code will be released upon acceptance.

**摘要翻译**:

多模态实体对齐（MMEA）旨在跨异构多模态知识图谱（MMKGs）识别等价实体，其中每个实体由来自不同模态的属性描述。现有方法通常假设实体内部和图间的对应关系是准确无误的，但在实际的多模态知识图谱中，由于依赖专家标注，这一假设常被违反。本文揭示并研究了 MMEA 中一个极具实际意义但尚未充分探索的问题，称为双层噪声对应（DNC）。DNC 是指实体内部（实体-属性）和图间（实体-实体与属性-属性）对应关系中的错位。为解决 DNC 问题，我们提出了一个鲁棒的 MMEA 框架 RULE。RULE 首先通过专门的双重原则估计实体内部和图间对应关系的可靠性。利用估计的可靠性，RULE 在属性融合过程中减轻实体内部噪声的负面影响，并在图间差异消除过程中防止对噪声图间对应关系的过拟合。除了训练阶段的设计外，RULE 还引入了对应推理模块，揭示跨图的底层属性-属性连接，从而保证更准确的等价实体识别。在五个基准数据集上的大量实验验证了我们的方法相比七种最先进方法在应对 DNC 问题上的有效性。代码将在论文被接收后发布。

---

## 115. Pinet: Optimizing hard-constrained neural networks with orthogonal projection layers

**Pinet：使用正交投影层优化硬约束神经网络**

**OpenReview**: [https://openreview.net/forum?id=EJ680UQeZG](https://openreview.net/forum?id=EJ680UQeZG)

**Authors**: Panagiotis D. Grontas (ETHZ - ETH Zurich), Antonio Terpin (ETHZ - ETH Zurich), Efe C. Balta (inspire AG), Raffaello D'Andrea (ETHZ - ETH Zurich), John Lygeros (ETHZ - ETH Zurich)

**Institutions**: ETHZ - ETH Zurich, inspire AG

**Primary Area**: optimization

**Keywords**: hard constrained neural networks, network architecture, implicit layers, operator splitting, optimization

**Abstract**:

We introduce an output layer for neural networks that ensures satisfaction of convex constraints. Our approach, $\Pi$net, leverages operator splitting for rapid and reliable projections in the forward pass, and the implicit function theorem for backpropagation. We deploy $\Pi$net as a feasible-by-design optimization proxy for parametric constrained optimization problems and obtain modest-accuracy
solutions faster than traditional solvers when solving a single problem, and significantly faster for a batch of problems.
We surpass state-of-the-art learning approaches by orders of magnitude in terms of training time, solution quality, and robustness to hyperparameter tuning, while maintaining similar inference times. Finally, we tackle multi-vehicle motion planning with non-convex trajectory preferences and provide $\Pi$net as a GPU-ready package implemented in JAX.

**摘要翻译**:

我们引入了一种神经网络输出层，确保满足凸约束条件。我们的方法 $\Pi$net 利用算子分裂技术在前向传播中实现快速可靠的投影，并通过隐函数定理实现反向传播。我们将 $\Pi$net 部署为参数化约束优化问题的设计即可行优化代理，在求解单个问题时能以适中精度比传统求解器更快获得解，而在批量求解问题时则显著更快。我们在训练时间、解的质量和超参数调优鲁棒性方面以数量级的优势超越了最先进的学习方法，同时保持了相似的推理时间。最后，我们处理了具有非凸轨迹偏好的多车辆运动规划问题，并将 $\Pi$net 作为基于 JAX 实现的 GPU 就绪软件包提供。

---

## 116. ParaRNN: Unlocking Parallel Training of Nonlinear RNNs for Large Language Models

**ParaRNN：解锁非线性 RNN 在大语言模型中的并行训练**

**OpenReview**: [https://openreview.net/forum?id=mX8b64iUaa](https://openreview.net/forum?id=mX8b64iUaa)

**Authors**: Federico Danieli (Apple), Pau Rodriguez (Apple), Miguel Sarabia, Xavier Suau (Apple), Luca Zappella (Apple)

**Institutions**: Apple

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: RNN, Mamba, SSM, Transformers, Parallelization, Parallel scan, Nonlinear

**TL;DR**: We break the sequential bottleneck of nonlinear RNNs, enabling training of billion-scale LSTM/GRU models, competitive with modern architectures

**TL;DR翻译**: 我们突破了非线性 RNN 的顺序瓶颈，实现了十亿级规模 LSTM/GRU 模型的训练，性能可与现代架构相媲美。

**Abstract**:

Recurrent Neural Networks (RNNs) laid the foundation for sequence modeling, but their intrinsic sequential nature restricts parallel computation, creating a fundamental barrier to scaling. This has led to the dominance of parallelizable architectures like Transformers and, more recently, State Space Models (SSMs). While SSMs achieve efficient parallelization through structured linear recurrences, this linearity constraint limits their expressive power and precludes modeling complex, nonlinear sequence-wise dependencies.
To address this, we present ParaRNN, a framework that breaks the sequence-parallelization barrier for nonlinear RNNs. Building on prior work, we cast the sequence of nonlinear recurrence relationships as a single system of equations, which we solve in parallel using Newton's iterations combined with custom parallel reductions. Our implementation achieves speedups of up to $665\times$ over naive sequential application, allowing training nonlinear RNNs at unprecedented scales. To showcase this, we apply ParaRNN to adaptations of LSTM and GRU architectures, successfully training models of 7B parameters that attain perplexity comparable to similarly-sized Transformers and Mamba2 architectures.
To accelerate research in efficient sequence modeling, we release the ParaRNN codebase as an open-source framework for automatic training-parallelization of nonlinear RNNs, enabling researchers and practitioners to explore new nonlinear RNN models at scale.

**摘要翻译**:

循环神经网络（RNNs）奠定了序列建模的基础，但其固有的顺序特性限制了并行计算，构成了扩展的根本性障碍。这导致了可并行化架构（如 Transformer）以及近期状态空间模型（SSMs）的主导地位。虽然 SSMs 通过结构化线性递推实现了高效并行化，但这种线性约束限制了其表达能力，无法建模复杂的非线性序列依赖关系。为解决这一问题，我们提出了 ParaRNN 框架，突破了非线性 RNN 的序列并行化瓶颈。在先前工作的基础上，我们将非线性递推关系序列转化为单个方程组，并利用牛顿迭代结合自定义并行规约进行并行求解。我们的实现相比朴素顺序执行实现了高达 $665\times$ 的加速，使得在前所未有的规模上训练非线性 RNN 成为可能。为展示这一点，我们将 ParaRNN 应用于 LSTM 和 GRU 架构的改编版本，成功训练了 7B 参数的模型，其困惑度与同等规模的 Transformer 和 Mamba2 架构相当。为加速高效序列建模的研究，我们将 ParaRNN 代码库作为开源框架发布，支持非线性 RNN 的自动训练并行化，使研究人员和从业者能够在大规模场景中探索新的非线性 RNN 模型。

---

## 117. Exploring Synthesizable Chemical Space with Iterative Pathway Refinements

**通过迭代路径优化探索可合成化学空间**

**OpenReview**: [https://openreview.net/forum?id=aQKVfKOkR5](https://openreview.net/forum?id=aQKVfKOkR5)

**Authors**: Seul Lee (Korea Advanced Institute of Science and Technology), Karsten Kreis (NVIDIA), Srimukh Prasad Veccham (NVIDIA), Meng Liu (NVIDIA), Danny Reidenbach (NVIDIA), Saee Gopal Paliwal (NVIDIA), Weili Nie (NVIDIA), Arash Vahdat (NVIDIA)

**Institutions**: Korea Advanced Institute of Science and Technology, NVIDIA

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: drug discovery, molecule generation, synthesizable molecule design

**Abstract**:

A well-known pitfall of molecular generative models is that they are not guaranteed to generate synthesizable molecules. Existing solutions for this problem often struggle to effectively navigate exponentially large combinatorial space of synthesizable molecules and suffer from poor coverage. To address this problem, we introduce ReaSyn, an iterative generative pathway refinement framework that obtains synthesizable analogs to input molecules by projecting them onto synthesizable space. Specifically, we propose a simple synthetic pathway representation that allows for generating pathways in both bottom-up and top-down traversal of synthetic trees. We design ReaSyn so that both bottom-up and top-down pathways can be sampled with a single unified autoregressive model. ReaSyn can thus iteratively refine subtrees of generated synthetic trees in a bidirectional manner. Further, we introduce a discrete flow model that refines the generated pathway at the entire pathway level with edit operations: insertion, deletion, and substitution. The iterative refinement cycle of (1) bottom-up decoding, (2) top-down decoding, and (3) holistic editing constitutes a powerful pathway reasoning strategy, allowing the model to explore the vast space of synthesizable molecules. Experimentally, ReaSyn achieves the highest reconstruction rate and pathway diversity in synthesizable molecule reconstruction and the highest optimization performance in synthesizable goal-directed molecular optimization, and significantly outperforms previous synthesizable projection methods in synthesizable hit expansion. These results highlight ReaSyn's superior ability to navigate combinatorially-large synthesizable chemical space.

**摘要翻译**:

分子生成模型的一个众所周知的缺陷是无法保证生成可合成的分子。针对该问题的现有解决方案往往难以有效导航呈指数级增长的可合成分子组合空间，且覆盖率较差。为解决这一问题，我们引入了 ReaSyn，一种迭代生成路径优化框架，通过将输入分子投影到可合成空间来获取其可合成类似物。具体而言，我们提出了一种简洁的合成路径表示方法，允许以自底向上和自顶向下两种方式遍历合成树来生成路径。我们设计 ReaSyn 使得自底向上和自顶向下路径均可通过单一统一的自回归模型进行采样。因此，ReaSyn 能够以双向方式迭代优化生成的合成树的子树。此外，我们引入了一种离散流模型，通过编辑操作（插入、删除和替换）在整个路径层面优化生成的路径。由 (1) 自底向上解码、(2) 自顶向下解码和 (3) 整体编辑构成的迭代优化循环是一种强大的路径推理策略，使模型能够探索广阔的可合成分子空间。在实验中，ReaSyn 在可合成分子重建任务中达到了最高的重建率和路径多样性，在可合成目标导向分子优化中达到了最高的优化性能，并在可合成命中扩展任务中显著优于先前的可合成投影方法。这些结果彰显了 ReaSyn 在导航组合量级的可合成化学空间方面的卓越能力。

---

## 118. On The Surprising Effectiveness of a Single Global Merging in Decentralized Learning

**单次全局合并在去中心化学习中的惊人有效性**

**OpenReview**: [https://openreview.net/forum?id=zrFnwRHuQo](https://openreview.net/forum?id=zrFnwRHuQo)

**Authors**: Tongtian Zhu (Zhejiang University), Tianyu Zhang (Montreal Institute for Learning Algorithms, University of Montreal, University of Montreal), Mingze Wang (Peking University), Zhanpeng Zhou (ByteDance Inc.), Can Wang (Zhejiang University)

**Institutions**: Zhejiang University, Montreal Institute for Learning Algorithms, University of Montreal, University of Montreal, Peking University, ByteDance Inc.

**Primary Area**: optimization

**Keywords**: Decentralized Learning, Model Merging

**TL;DR**: We discover and theoretically explain why and when a single global parameter merging in decentralized learning can recover the performance of federated learning, even in highly heterogeneous and communication-constrained environments.

**TL;DR翻译**: 我们发现并从理论上解释了为什么以及何时在去中心化学习中执行单次全局参数合并即可恢复联邦学习的性能，即使在高度异构且通信受限的环境中也是如此。

**Abstract**:

Decentralized learning provides a scalable alternative to parameter-server-based training, yet its performance is often hindered by limited peer-to-peer communication.
In this paper, we study how communication should be scheduled over time to improve global generalization, including determining when and how frequently devices synchronize.
Counterintuitive empirical results show that concentrating communication budgets in the later stages of decentralized training remarkably improves global generalization.
Surprisingly, we uncover that fully connected communication at the final step, implemented by a single global merging, can significant improve the generalization performance of decentralized learning under serve high data heterogeneity.
Our theoretical contributions, which explains these phenomena, are first to establish that the globally merged model of decentralized SGD can match the convergence rate of parallel SGD.
Technically, we reinterpret part of the discrepancy among local models, which were previously considered as detrimental noise, as constructive components essential for matching this rate.
This work provides promising results that  decentralized learning is able to generalize under high data heterogeneity and limited communication, while offering broad new avenues for model merging research.
The code will be made publicly available.

**摘要翻译**:

去中心化学习提供了一种相对于参数服务器训练的可扩展替代方案，但其性能常受限于有限的点对点通信。本文研究了如何在时间维度上调度通信以改善全局泛化性能，包括确定设备同步的时机和频率。反直觉的实验结果表明，将通信预算集中在去中心化训练的后期阶段能够显著改善全局泛化性能。令人惊讶的是，我们发现在最后一步执行全连接通信（即通过单次全局合并实现）能够在严重数据异构条件下显著提升去中心化学习的泛化性能。我们的理论贡献在于首次证明了去中心化 SGD 的全局合并模型可以达到与并行 SGD 相同的收敛速率。在技术层面，我们将局部模型之间差异的一部分重新解释为建设性成分——而非此前所认为的有害噪声——这些成分对于达到该收敛速率至关重要。这项工作提供了令人鼓舞的结果，表明去中心化学习能够在高数据异构和有限通信条件下实现良好泛化，同时为模型合并研究开辟了广阔的新方向。代码将会公开发布。

---

## 119. Visual Planning: Let's Think Only with Images

**视觉规划：仅用图像进行思考**

**OpenReview**: [https://openreview.net/forum?id=wsnse46kRO](https://openreview.net/forum?id=wsnse46kRO)

**Authors**: Yi Xu (University of Cambridge), Chengzu Li (University of Cambridge), Han Zhou (Mistral AI), Xingchen Wan (Google DeepMind), Caiqi Zhang (University of Cambridge), Anna Korhonen (University of Cambridge), Ivan Vulic (Google DeepMind)

**Institutions**: University of Cambridge, Mistral AI, Google DeepMind

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: visual planning

**Abstract**:

Recent advancements in Large Language Models (LLMs) and their multimodal extensions (MLLMs) have substantially enhanced machine reasoning across diverse tasks. However, these models predominantly rely on pure text as the medium for both expressing and structuring reasoning, even when visual information is present. In this work, we argue that language may not always be the most natural or effective modality for reasoning, particularly in tasks involving spatial and geometrical information. Motivated by this, we propose a new paradigm, Visual Planning, which enables planning through purely visual representations for these "vision-first'' tasks, as a supplementary channel to language-based reasoning. In this paradigm, planning is executed via sequences of images that encode step-by-step inference in the visual domain, akin to how humans sketch or visualize future actions. We introduce a novel reinforcement learning framework, Visual Planning via Reinforcement Learning (VPRL), empowered by GRPO for post-training large vision models, leading to substantial improvements in planning in a selection of representative visual navigation tasks, FrozenLake, Maze, and MiniBehavior. Our visual planning paradigm outperforms all other planning variants that conduct reasoning in the text-only space. Our results establish Visual Planning as a viable and promising supplement to language-based reasoning, opening new avenues for tasks that benefit from intuitive, image-based inference.

**摘要翻译**:

大语言模型（LLMs）及其多模态扩展（MLLMs）的最新进展显著增强了机器在多种任务上的推理能力。然而，这些模型主要依赖纯文本作为表达和组织推理的媒介，即使存在视觉信息也是如此。在本文中，我们认为语言并非总是最自然或最有效的推理模态，尤其是在涉及空间和几何信息的任务中。基于这一动机，我们提出了一种新范式——视觉规划，使这些"视觉优先"任务能够通过纯视觉表征进行规划，作为基于语言推理的补充通道。在该范式中，规划通过编码逐步视觉推理的图像序列来执行，类似于人类草图绘制或可视化未来动作的方式。我们引入了一种新颖的强化学习框架——基于强化学习的视觉规划（VPRL），利用 GRPO 对大型视觉模型进行后训练，在 FrozenLake、Maze 和 MiniBehavior 等代表性视觉导航任务中实现了规划能力的大幅提升。我们的视觉规划范式优于所有在纯文本空间中进行推理的规划变体。实验结果证明，视觉规划是一种可行且有前景的语言推理补充方案，为受益于直觉式图像推理的任务开辟了新方向。

---

## 120. Optimal Sparsity of Mixture-of-Experts Language Models for Reasoning Tasks

**混合专家语言模型在推理任务中的最优稀疏度**

**OpenReview**: [https://openreview.net/forum?id=XFw2EPRUUR](https://openreview.net/forum?id=XFw2EPRUUR)

**Authors**: Taishi Nakamura (Institute of Science Tokyo), Satoki Ishikawa (Institute of Science Tokyo), Masaki Kawamura (Institute of Science Tokyo), Takumi Okamoto (Institute of Science Tokyo), Daisuke Nohara (Institute of Science Tokyo), Jun Suzuki (Tohoku University), Rio Yokota (Institute of Science Tokyo)

**Institutions**: Institute of Science Tokyo, Tohoku University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Mixture of Experts, memorization, reasoning, scaling laws, large language models

**TL;DR**: Memorization skills consistently benefit from higher sparsity, while reasoning skills require balancing active FLOPs with total tokens per parameter; the optimal point shifts with the compute budget.

**TL;DR翻译**: 记忆能力始终受益于更高的稀疏度，而推理能力则需要在活跃 FLOPs 与每参数总 token 数之间取得平衡；最优点随计算预算的变化而移动。

**Abstract**:

Empirical scaling laws have driven the evolution of large language models (LLMs), yet their coefficients shift whenever the model architecture or data pipeline changes.
Mixture-of-Experts (MoE) models, now standard in state-of-the-art systems, introduce a new sparsity dimension that current dense-model frontiers overlook.
We investigate how MoE sparsity influences two distinct capability regimes: memorization skills and reasoning skills.
By training MoE families that vary total parameters, active parameters, and top-$k$ routing under fixed compute budgets, we disentangle pre-training loss from downstream accuracy.
Our results reveal two principles. First, Active FLOPs: models with identical training loss but greater active compute achieve higher reasoning accuracy. Second, Total tokens per parameter (TPP): memorization tasks improve with more parameters, while reasoning tasks benefit from optimal TPP, indicating that reasoning is data-hungry.
Neither reinforcement learning post-training (GRPO) nor increased test-time compute alters these trends.
We therefore argue that optimal MoE sparsity must be determined jointly by active FLOPs and TPP, revising the classical picture of compute-optimal scaling.
All code, data sources, and logs are released to facilitate reproducibility and future work.

**摘要翻译**:

经验缩放定律驱动了大语言模型（LLMs）的演进，但每当模型架构或数据管线发生变化时，其系数也随之改变。混合专家（MoE）模型已成为最先进系统中的标准配置，引入了当前稠密模型前沿所忽视的新稀疏度维度。我们研究了 MoE 稀疏度如何影响两种不同的能力范畴：记忆能力和推理能力。通过在固定计算预算下训练具有不同总参数量、活跃参数量和 top-$k$ 路由的 MoE 模型族，我们将预训练损失与下游准确率解耦。实验结果揭示了两个原则。第一，活跃 FLOPs：具有相同训练损失但更大活跃计算量的模型能够达到更高的推理准确率。第二，每参数总 token 数（TPP）：记忆任务受益于更多参数，而推理任务受益于最优 TPP，表明推理对数据的需求更为旺盛。强化学习后训练（GRPO）和增加测试时计算量均不改变这些趋势。因此我们认为，MoE 的最优稀疏度必须由活跃 FLOPs 和 TPP 联合决定，这修正了经典的计算最优缩放图景。所有代码、数据来源和日志均已发布，以促进可复现性和未来研究。

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

---

## 122. DCFold: Efficient Protein Structure Generation with Single Forward Pass

**DCFold：通过单次前向传播实现高效蛋白质结构生成**

**OpenReview**: [https://openreview.net/forum?id=LMsdys7t1L](https://openreview.net/forum?id=LMsdys7t1L)

**Authors**: Zhe Zhang (Tsinghua University), Yuanning Feng (Huazhong University of Science and Technology), Yuxuan Song (ByteDance Inc.), Keyue Qiu, Hao Zhou (Tsinghua University, Tsinghua University), Wei-Ying Ma (Tsinghua University)

**Institutions**: Tsinghua University, Huazhong University of Science and Technology, ByteDance Inc., Tsinghua University, Tsinghua University

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: consistency model, protein structure generation

**Abstract**:

AlphaFold3 introduces a diffusion-based architecture that elevates protein structure prediction to all-atom resolution with improved accuracy. This state-of-the-art performance has established AlphaFold3 as a foundation model for diverse generation and design tasks. However, its iterative design substantially increases inference time, limiting practical deployment in downstream settings such as virtual screening and protein design. We propose DCFold, a single-step generative model that attains AlphaFold3-level accuracy. Our Dual Consistency training framework, which incorporates a novel Temporal Geodesic Matching (TGM) scheduler, enables DCFold to achieve a 15x acceleration in inference while maintaining predictive fidelity. We validate its effectiveness across both structure prediction and binder design benchmarks.

**摘要翻译**:

AlphaFold3 引入了基于扩散的架构，将蛋白质结构预测提升至全原子分辨率并提高了精度。这一顶尖性能使 AlphaFold3 成为多种生成和设计任务的基础模型。然而，其迭代式设计大幅增加了推理时间，限制了在虚拟筛选和蛋白质设计等下游场景中的实际部署。我们提出了 DCFold，一种单步生成模型，可达到 AlphaFold3 水平的精度。我们的双一致性训练框架结合了新颖的时间测地匹配（TGM）调度器，使 DCFold 在保持预测保真度的同时实现了 15 倍的推理加速。我们在结构预测和结合物设计基准上验证了其有效性。

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

---

## 124. InfoNCE Induces Gaussian Distribution

**InfoNCE 诱导高斯分布**

**OpenReview**: [https://openreview.net/forum?id=BlSH7gNQSq](https://openreview.net/forum?id=BlSH7gNQSq)

**Authors**: Roy Betser (Technion - Israel Institute of Technology, Technion), Eyal Gofer (Electrical Engineering Department, Technion - Israel Institute of Technology, Technion - Israel Institute of Technology), Meir Yossef Levi (Technion - Israel Institute of Technology, Technion - Israel Institute of Technology), Guy Gilboa (Technion - Israel Institute of Technology, Technion)

**Institutions**: Technion - Israel Institute of Technology, Technion, Electrical Engineering Department, Technion - Israel Institute of Technology, Technion - Israel Institute of Technology, Technion - Israel Institute of Technology, Technion - Israel Institute of Technology

**Primary Area**: learning theory

**Keywords**: Contrastive learning, Gaussian distribution, InfoNCE

**TL;DR**: Contrastive learning based representations can be well approximated by a multivariate Gaussian distribution.

**TL;DR翻译**: 基于对比学习的表征可以被多元高斯分布很好地近似。

**Abstract**:

Contrastive learning has become a cornerstone of modern representation learning, allowing training with massive
unlabeled data for both task-specific and general (foundation) models.
A prototypical loss in contrastive training is InfoNCE and its variants.
In this work, we show that the InfoNCE objective induces Gaussian structure in representations that emerge from contrastive training.
We establish this result in two complementary regimes.
First, we show that under certain  alignment and concentration assumptions, projections of the high-dimensional representation asymptotically approach a multivariate Gaussian distribution.
Next, under less strict assumptions, we show that adding a small asymptotically vanishing regularization term that promotes low feature norm and high feature entropy leads to similar asymptotic results.
We support our analysis with experiments on synthetic and CIFAR-10 datasets across multiple encoder architectures and sizes, demonstrating consistent Gaussian behavior.
This perspective provides a principled explanation for commonly observed Gaussianity in contrastive representations.
The resulting Gaussian model enables principled analytical treatment of learned representations and is expected to support a wide range of applications in contrastive learning.

**摘要翻译**:

对比学习已成为现代表征学习的基石，允许利用海量无标签数据训练面向特定任务和通用（基础）模型。对比训练中的典型损失函数是 InfoNCE 及其变体。本文证明了 InfoNCE 目标函数会在对比训练产生的表征中诱导出高斯结构。我们在两个互补的条件下建立了这一结果。首先，我们证明在特定的对齐和集中假设下，高维表征的投影渐近趋近于多元高斯分布。其次，在较弱的假设下，我们证明添加一个渐近消失的小正则化项（促进低特征范数和高特征熵）可以得到类似的渐近结果。我们在合成数据集和 CIFAR-10 数据集上使用多种编码器架构和规模进行实验，验证了一致的高斯行为。这一视角为对比表征中常见的高斯性提供了有原则的解释。由此得到的高斯模型使得对习得表征的有原则分析处理成为可能，预计将支持对比学习中的广泛应用。

---

## 125. Coupling Experts and Routers in Mixture-of-Experts via an Auxiliary Loss

**通过辅助损失耦合混合专家模型中的专家与路由器**

**OpenReview**: [https://openreview.net/forum?id=MpeyjgWbKt](https://openreview.net/forum?id=MpeyjgWbKt)

**Authors**: Ang Lv (Renmin University of China), Jin Ma (ByteDance Inc.), Yiyuan Ma (ByteDance Inc.), Siyuan Qiao (Meta)

**Institutions**: Renmin University of China, ByteDance Inc., Meta

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Mixture-of-Experts, Large language models, Auxiliary loss, Expert-router coupling, Expert specialization

**Abstract**:

Mixture-of-Experts (MoE) models lack explicit constraints to ensure the router's decisions align well with the experts' capabilities, which ultimately limits model performance. To address this, we propose expert-router coupling (ERC) loss, a lightweight auxiliary loss that tightly couples the router's decisions with expert capabilities. Our approach treats each expert's router embedding as a proxy token for the tokens assigned to that expert, and feeds perturbed router embeddings through the experts to obtain intermediate activations. The ERC loss enforces two constraints on these activations: (1) Each expert must exhibit higher activation for its own proxy token than for the proxy tokens of any other expert. (2) Each proxy token must elicit stronger activation from its corresponding expert than from any other expert. These constraints jointly ensure that each router embedding faithfully represents its corresponding expert's capability, while each expert specializes in processing the tokens actually routed to it. The ERC loss is computationally efficient, operating only on $n^2$ activations, where $n$ is the number of experts. This represents a fixed cost independent of batch size, unlike prior coupling methods that scale with the number of tokens (often millions per batch). Through pre-training MoE-LLMs ranging from 3B to 15B parameters and extensive analysis on trillions of tokens, we demonstrate the effectiveness of the ERC loss. Moreover, the ERC loss offers flexible control and quantitative tracking of expert specialization levels during training, providing valuable insights into MoEs.

**摘要翻译**:

混合专家（MoE）模型缺乏显式约束来确保路由器的决策与专家的能力良好对齐，这最终限制了模型性能。为解决这一问题，我们提出了专家-路由器耦合（ERC）损失，一种轻量级辅助损失，将路由器的决策与专家能力紧密耦合。我们的方法将每个专家的路由器嵌入视为分配给该专家的 token 的代理 token，并将扰动后的路由器嵌入送入专家以获得中间激活值。ERC 损失对这些激活值施加两个约束：(1) 每个专家对其自身代理 token 的激活值必须高于对任何其他专家代理 token 的激活值。(2) 每个代理 token 从其对应专家获得的激活值必须强于从任何其他专家获得的激活值。这些约束共同确保每个路由器嵌入忠实地代表其对应专家的能力，同时每个专家专注于处理实际路由到它的 token。ERC 损失计算高效，仅在 $n^2$ 个激活值上操作，其中 $n$ 为专家数量。这代表一个与批量大小无关的固定成本，不同于先前随 token 数量（通常每批数百万）缩放的耦合方法。通过预训练 3B 到 15B 参数的 MoE-LLM 以及在万亿级 token 上的广泛分析，我们验证了 ERC 损失的有效性。此外，ERC 损失提供了在训练过程中对专家专业化水平的灵活控制和定量追踪，为理解 MoE 提供了有价值的洞察。

---

## 126. P-GenRM: Personalized Generative Reward Model with Test-time User-based Scaling

**P-GenRM：具有测试时用户级缩放的个性化生成式奖励模型**

**OpenReview**: [https://openreview.net/forum?id=hXNApWLBZG](https://openreview.net/forum?id=hXNApWLBZG)

**Authors**: Pinyi Zhang (East China Normal University), Ting-En Lin (Alibaba Group), Yuchuan Wu (Alibaba Group), Jingyang Chen (Fudan University), Zongqi Wang (Tsinghua University), Hua Yang (Alibaba Group), Xu Ze (Alibaba Group), Fei Huang (Alibaba Group US), Yongbin Li (Alibaba Group), Kai Zhang (East China Normal University)

**Institutions**: East China Normal University, Alibaba Group, Fudan University, Tsinghua University, Alibaba Group US

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: personalizd alignment, generative reward model, test-time user-based scaling

**TL;DR**: The first personalized generative reward model with test-time user-based scaling for preference alignment

**TL;DR翻译**: 首个具有测试时用户级缩放能力的个性化生成式奖励模型，用于偏好对齐。

**Abstract**:

Personalized alignment of large language models seeks to adapt responses to individual user preferences, typically via reinforcement learning. A key challenge is obtaining accurate, user-specific reward signals in open-ended scenarios. Existing personalized reward models face two persistent limitations: (1) oversimplifying diverse, scenario-specific preferences into a small, fixed set of evaluation principles, and (2) struggling with generalization to new users with limited feedback. To this end, we propose **P-GenRM**, the first **P**ersonalized **Gen**erative **R**eward **M**odel with test-time user-based scaling. P-GenRM transforms preference signals into structured evaluation chains that derive adaptive personas and scoring rubrics across various scenarios. It further clusters users into User Prototypes and introduces a dual-granularity scaling mechanism: at the individual level, it adaptively scales and aggregates each user's scoring scheme; at the prototype level, it incorporates preferences from similar users. This design mitigates noise in inferred preferences and enhances generalization to unseen users through prototype-based transfer. Empirical results show that  P-GenRM achieves state-of-the-art results on widely-used personalized reward model benchmarks, with an average improvement of ~2.31%, and demonstrates strong generalization on an out-of-distribution dataset. Notably, Test-time User-based scaling provides an additional ~3% boost, demonstrating stronger personalized alignment with test-time scalability.

**摘要翻译**:

大语言模型的个性化对齐旨在使响应适应个体用户偏好，通常通过强化学习实现。一个关键挑战是在开放式场景中获取准确的、用户特定的奖励信号。现有的个性化奖励模型面临两个持续性限制：(1) 将多样化的、场景特定的偏好过度简化为一小组固定的评估原则；(2) 难以泛化到反馈有限的新用户。为此，我们提出了 P-GenRM，首个具有测试时用户级缩放能力的个性化生成式奖励模型。P-GenRM 将偏好信号转化为结构化的评估链，在不同场景中推导出自适应的用户画像和评分准则。它进一步将用户聚类为用户原型，并引入双粒度缩放机制：在个体层面，自适应地缩放和聚合每位用户的评分方案；在原型层面，融入相似用户的偏好。这一设计减轻了推断偏好中的噪声，并通过基于原型的迁移增强了对未见用户的泛化能力。实验结果表明，P-GenRM 在广泛使用的个性化奖励模型基准上达到了最先进结果，平均提升约 2.31%，并在分布外数据集上展示了强大的泛化能力。值得注意的是，测试时用户级缩放额外提供了约 3% 的提升，展示了更强的个性化对齐与测试时可扩展性。

---

## 127. Modality-free Graph In-context Alignment

**无模态图上下文对齐**

**OpenReview**: [https://openreview.net/forum?id=cDc95lucVL](https://openreview.net/forum?id=cDc95lucVL)

**Authors**: Wei Zhuo (Nanyang Technological University), Siqiang Luo (Nanyang Technological University)

**Institutions**: Nanyang Technological University

**Primary Area**: learning on graphs and other geometries & topologies

**Keywords**: Graph foundation model, In-context learning, Pretraining

**TL;DR**: A pretraining framework that enables in-context learning on graph-structured data without modality assumptions.

**TL;DR翻译**: 一种预训练框架，无需模态假设即可在图结构数据上实现上下文学习。

**Abstract**:

In-context learning (ICL) converts static encoders into task-conditioned reasoners, enabling adaptation to new data from just a few examples without updating pretrained parameters. This capability is essential for graph foundation models (GFMs) to approach LLM-level generality. Yet current GFMs struggle with cross-domain alignment, typically relying on modality-specific encoders that fail when graphs are pre-vectorized or raw data is inaccessible. In this paper, we introduce **M**odality-**F**ree **G**raph **I**n-context **A**lignment (MF-GIA), a framework that makes a pretrained graph encoder promptable for few-shot prediction across heterogeneous domains without modality assumptions. MF-GIA captures domain characteristics through gradient fingerprints, which parameterize lightweight transformations that align pre-encoded features and indexed labels into unified semantic spaces. During pretraining, a dual prompt-aware attention mechanism with episodic objective learns to match queries against aligned support examples to establish prompt-based reasoning capabilities. At inference, MF-GIA performs parameter-update-free adaptation using only a few-shot support set to trigger cross-domain alignment and enable immediate prediction on unseen domains. Experiments demonstrate that MF-GIA achieves superior few-shot performance across diverse graph domains and strong generalization to unseen domains. The code is available at https://github.com/JhuoW/MF-GIA.

**摘要翻译**:

上下文学习（ICL）将静态编码器转化为任务条件化的推理器，仅凭少量示例即可适应新数据，无需更新预训练参数。这种能力对于图基础模型（GFMs）达到 LLM 级别的通用性至关重要。然而，当前的 GFMs 在跨域对齐方面存在困难，通常依赖特定模态的编码器，当图已预先向量化或原始数据不可访问时便会失效。本文引入了无模态图上下文对齐（MF-GIA）框架，使预训练的图编码器无需模态假设即可在异构域上进行小样本预测。MF-GIA 通过梯度指纹捕获域特征，这些指纹参数化轻量级变换，将预编码特征和索引标签对齐到统一的语义空间。在预训练阶段，双提示感知注意力机制配合情节式目标学习将查询与对齐后的支持示例进行匹配，以建立基于提示的推理能力。在推理阶段，MF-GIA 仅使用小样本支持集触发跨域对齐，无需参数更新即可在未见域上实现即时预测。实验表明，MF-GIA 在多个图域上达到了优越的小样本性能，并对未见域展现出强大的泛化能力。代码已开源于 https://github.com/JhuoW/MF-GIA。

---

## 128. TRACE: Your Diffusion Model is Secretly an Instance Edge Detector

**TRACE：你的扩散模型其实是一个实例边缘检测器**

**OpenReview**: [https://openreview.net/forum?id=BjElYlJKMj](https://openreview.net/forum?id=BjElYlJKMj)

**Authors**: Sanghyun Jo (OGQ), Ziseok Lee (Seoul National University), Wooyeol Lee (Seoul National University), Jonghyun Choi (Seoul National University), Jaesik Park (Seoul National University), Kyungsu Kim (Seoul National University)

**Institutions**: OGQ, Seoul National University

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: diffusion, unsupervised instance segmentation, weakly-supervised panoptic segmentation, inference dynamics, attention

**TL;DR**: TRACE turns pretrained diffusion models into annotation-free instance edge generators for instance and panoptic segmentation.

**TL;DR翻译**: TRACE 将预训练扩散模型转化为无需标注的实例边缘生成器，用于实例分割和全景分割。

**Abstract**:

High-quality instance and panoptic segmentation has traditionally relied on dense instance-level annotations such as masks, boxes, or points, which are costly, inconsistent, and difficult to scale. Unsupervised and weakly-supervised approaches reduce this burden but remain constrained by semantic backbone constraints and human bias, often producing merged or fragmented outputs. We present TRACE (TRAnsforming diffusion Cues to instance Edges), showing that text-to-image diffusion models secretly function as instance edge annotators. TRACE identifies the Instance Emergence Point (IEP) where object boundaries first appear in self-attention maps, extracts boundaries through Attention Boundary Divergence (ABDiv), and distills them into a lightweight one-step edge decoder. This design removes the need for per-image diffusion inversion, achieving 81x faster inference while producing sharper and more connected boundaries. On the COCO benchmark, TRACE improves unsupervised instance segmentation by +5.1 AP, and in tag-supervised panoptic segmentation it outperforms point-supervised baselines by +1.7 PQ without using any instance-level labels. These results reveal that diffusion models encode hidden instance boundary priors, and that decoding these signals offers a practical and scalable alternative to costly manual annotation. **Project Page:** https://shjo-april.github.io/TRACE.

**摘要翻译**:

高质量的实例分割和全景分割传统上依赖于密集的实例级标注，如掩码、边界框或点标注，这些标注成本高昂、不一致且难以扩展。无监督和弱监督方法减轻了这一负担，但仍受限于语义骨干网络的约束和人为偏差，常产生合并或碎片化的输出。我们提出了 TRACE（将扩散线索转化为实例边缘），表明文本到图像扩散模型实际上可作为实例边缘标注器。TRACE 识别了实例涌现点（IEP），即物体边界首次出现在自注意力图中的位置，通过注意力边界散度（ABDiv）提取边界，并将其蒸馏为一个轻量级的单步边缘解码器。这一设计消除了逐图像扩散反演的需要，推理速度提升 81 倍，同时生成更清晰、更连贯的边界。在 COCO 基准上，TRACE 将无监督实例分割提升了 +5.1 AP，在标签监督的全景分割中，在不使用任何实例级标签的情况下超越了点监督基线 +1.7 PQ。这些结果表明，扩散模型编码了隐藏的实例边界先验，解码这些信号为昂贵的人工标注提供了一种实用且可扩展的替代方案。**项目主页：** https://shjo-april.github.io/TRACE。

---

## 129. Scaling Laws and Spectra of Shallow Neural Networks in the Feature Learning Regime

**特征学习机制下浅层神经网络的缩放定律与谱分析**

**OpenReview**: [https://openreview.net/forum?id=Q3yLIIkt7z](https://openreview.net/forum?id=Q3yLIIkt7z)

**Authors**: Leonardo Defilippis (Ecole Normale Superieure, Ecole Normale Superieure de Paris), Yizhou Xu, Julius Girardin (EPFL - EPF Lausanne), Vittorio Erba (EPFL - EPF Lausanne), Emanuele Troiani (School of Computer and Communication Sciences, EPFL - EPF Lausanne), Lenka Zdeborova (Swiss Federal Institute of Technology Lausanne), Bruno Loureiro (Ecole Normale Superieure, Ecole Normale Superieure de Paris), Florent Krzakala (Swiss Federal Institute of Technology Lausanne)

**Institutions**: Ecole Normale Superieure, Ecole Normale Superieure de Paris, EPFL - EPF Lausanne, School of Computer and Communication Sciences, EPFL - EPF Lausanne, Swiss Federal Institute of Technology Lausanne

**Primary Area**: learning theory

**Keywords**: Scaling laws; Neural networks; LASSO and matrix compressed sensing; Random matrix theory; Approximate message passing; High dimensional Statistics

**TL;DR**: We derive a phase diagram of scaling laws for diagonal and quadratic neural networks via a bridge to LASSO and matrix compressed sensing, predicting both generalization and the emergence of power-law weight spectra.

**TL;DR翻译**: 我们通过建立与 LASSO 和矩阵压缩感知的桥梁，推导出对角和二次神经网络的缩放定律相图，同时预测了泛化性能和幂律权重谱的涌现。

**Abstract**:

Neural scaling laws underlie many of the recent advances in deep learning, yet their theoretical understanding remains largely confined to linear models. In this work, we present a systematic analysis of scaling laws for quadratic and diagonal neural networks in the feature learning regime. Leveraging connections with matrix compressed sensing and LASSO, we derive a detailed phase diagram for the scaling exponents of the excess risk as a function of sample complexity and weight decay. This analysis uncovers crossovers between distinct scaling regimes and plateau behaviors, mirroring phenomena widely reported in the empirical neural scaling literature. Furthermore, we establish a precise link between these regimes and the spectral properties of the trained network weights, which we characterize in detail. As a consequence, we provide a theoretical validation of recent empirical observations connecting the emergence of power-law tails in the weight spectrum with network generalization performance, yielding an interpretation from first principles.

**摘要翻译**:

神经缩放定律是近年来深度学习诸多进展的基础，但其理论理解在很大程度上仍局限于线性模型。本文对具有二次激活函数的浅层神经网络在特征学习机制下的缩放定律进行了系统分析。利用与矩阵压缩感知和 LASSO 的联系，我们推导出了超额风险的缩放指数作为样本复杂度和权重衰减函数的详细相图。该分析揭示了不同缩放机制之间的交叉转换和平台行为，与经验神经缩放文献中广泛报道的现象相吻合。此外，我们建立了这些机制与训练后网络权重谱属性之间的精确联系，并对其进行了详细刻画。由此，我们为近期将权重谱中幂律尾部的涌现与网络泛化性能相关联的经验观察提供了理论验证，从第一性原理给出了解释。

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

---

## 132. NextStep-1: Toward Autoregressive Image Generation with Continuous Tokens at Scale

**NextStep-1：面向连续 Token 大规模自回归图像生成**

**OpenReview**: [https://openreview.net/forum?id=Ndnwg9oOQO](https://openreview.net/forum?id=Ndnwg9oOQO)

**Authors**: Chunrui Han (Stepfun), Guopeng Li (StepFun), Jingwei Wu (University of the Chinese Academy of Sciences), Quan Sun (StepFun), Yan Cai (Peking University), Yuang Peng (StepFun Technology Inc.), Zheng Ge (Stepfun), Deyu Zhou (The Hong Kong University of Science and Technology (Guangzhou)), Haomiao Tang (Tsinghua University), Hongyu Zhou (Megvii Technology Inc.), Kenkun Liu (The Chinese University of Hong Kong (Shenzhen)), Shu-Tao Xia (Shenzhen International Graduate School, Tsinghua University), Binxing Jiao (StepFun), Daxin Jiang (StepFun), Xiangyu Zhang (MEGVII Technology), Yibo Zhu (StepFun)

**Institutions**: Stepfun, StepFun, University of the Chinese Academy of Sciences, Peking University, StepFun Technology Inc., The Hong Kong University of Science and Technology (Guangzhou), Tsinghua University, Megvii Technology Inc., The Chinese University of Hong Kong (Shenzhen), Shenzhen International Graduate School, Tsinghua University, MEGVII Technology

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Generative Models, Autoregressive Models, Diffusion Models, Text-to-image

**Abstract**:

Prevailing autoregressive (AR) models for text-to-image generation either rely on heavy, computationally-intensive diffusion models to process continuous image tokens, or employ vector quantization (VQ) to obtain discrete tokens with quantization loss. In this paper, we push the autoregressive paradigm forward with NextStep-1, a 14B autoregressive model paired with a 157M flow matching head, trained on discrete text tokens and continuous image tokens with next-token prediction objectives. NextStep-1 achieves state-of-the-art performance for autoregressive models in text-to-image generation tasks, exhibiting strong capabilities in high-fidelity image synthesis. Furthermore, our method shows strong performance in image editing, highlighting the power and versatility of our unified approach. To facilitate open research, we have released our code and models to the community at https://github.com/stepfun-ai/NextStep-1.

**摘要翻译**:

主流的文本到图像生成自回归（AR）模型要么依赖计算密集型的扩散模型来处理连续图像 token，要么采用向量量化（VQ）将连续 token 离散化为有限视觉词汇表并引入量化损失。本文推动了自回归范式的发展，提出了 NextStep-1，一个 14B 参数的自回归模型搭配 157M 参数的流匹配头，在离散文本 token 和连续图像 token 上以下一 token 预测目标进行训练。NextStep-1 在文本到图像生成任务中达到了自回归模型的最先进性能，展现了强大的高保真图像合成能力。此外，我们的方法在图像编辑方面也表现出色，突显了该统一方法的强大能力和通用性。为促进开放研究，我们已在 https://github.com/stepfun-ai/NextStep-1 向社区发布了代码和模型。

---

## 133. Differentiable Model Predictive Control on the GPU

**GPU 上的可微模型预测控制**

**OpenReview**: [https://openreview.net/forum?id=bFYfV6c9zu](https://openreview.net/forum?id=bFYfV6c9zu)

**Authors**: Emre Adabag (University of Michigan - Ann Arbor), Marcus Greiff (Toyota Research Institute), John Subosits (Toyota Motor Corporation), Thomas Jonathan Lew

**Institutions**: University of Michigan - Ann Arbor, Toyota Research Institute, Toyota Motor Corporation

**Primary Area**: applications to robotics, autonomy, planning

**Keywords**: differentiable optimization, model predictive control, optimal control, gpu-accelerated optimization, reinforcement learning, imitation learning, robotics

**Abstract**:

Differentiable model predictive control (MPC) offers a powerful framework for combining learning and control. However, its adoption has been limited by the inherently sequential nature of traditional optimization algorithms, which are challenging to parallelize on modern computing hardware like GPUs. In this work, we tackle this bottleneck by introducing a GPU-accelerated differentiable optimization tool for MPC. This solver leverages sequential quadratic programming and a custom preconditioned conjugate gradient (PCG) routine with tridiagonal preconditioning to exploit the problem's structure and enable efficient parallelization. We demonstrate substantial speedups over CPU- and GPU-based baselines, significantly improving upon state-of-the-art training times on benchmark reinforcement learning and imitation learning tasks. Finally, we showcase the method on the challenging task of reinforcement learning for driving at the limits of handling, where it enables robust drifting of a Toyota Supra through water puddles.

**摘要翻译**:

可微模型预测控制（MPC）提供了一个强大的学习与控制结合框架。然而，传统优化算法固有的顺序特性使其在 GPU 等现代计算硬件上难以并行化，限制了其应用。本文通过引入面向 MPC 的 GPU 加速可微优化工具来解决这一瓶颈。该求解器利用序列二次规划和自定义的预处理共轭梯度（PCG）程序（采用三对角预处理）来利用问题结构并实现高效并行化。我们展示了相对于基于 CPU 和 GPU 的基线的大幅加速，显著改善了基准强化学习和模仿学习任务上的最先进训练时间。最后，我们在极限驾驶的强化学习这一挑战性任务上展示了该方法，实现了 Toyota Supra 在水坑中的稳健漂移驾驶。

---

## 134. Planner Aware Path Learning in Diffusion Language Models Training

**扩散语言模型训练中的规划器感知路径学习**

**OpenReview**: [https://openreview.net/forum?id=lAlI5FuIf7](https://openreview.net/forum?id=lAlI5FuIf7)

**Authors**: Fred Zhangzhi Peng (Duke University), Zachary Bezemek (Duke University), Jarrid Rector-Brooks (California Institute of Technology), Shuibai Zhang (University of Wisconsin - Madison), Michael M. Bronstein (Aithyra), Anru Zhang (Duke University), Joey Bose (Imperial College London), Alexander Tong (Aithyra)

**Institutions**: Duke University, California Institute of Technology, University of Wisconsin - Madison, Aithyra, Imperial College London

**Primary Area**: generative models

**Keywords**: Diffusion Language Models, Discrete Diffusion, Diffusion Models, code generation, protein generation, text generation

**TL;DR**: We propose Planner Aware Path Learning (PAPL), a simple planner-aligned training method for Diffusion Language Models that resolves the training-inference mismatch and consistently improves generation quality.

**TL;DR翻译**: 我们提出了规划器感知路径学习（PAPL），一种简单的与规划器对齐的扩散语言模型训练方法，解决了训练与推理之间的不匹配问题，并持续提升生成质量。

**Abstract**:

Diffusion language models have emerged as a powerful alternative to autoregressive models, enabling fast inference through more flexible and parallel generation paths. This flexibility of sampling is unlocked by new engineered sampling strategies, or *planners*, that select more favorable generation paths by iteratively planning---versus uniformly at random---where to denoise along the sequence. However, by modifying the reverse paths via planning, planners create an irrevocable mismatch between the uniformly random denoising paths during training and planning-based inference. In this paper, we systematically investigate the mismatch of discrete diffusion training and inference under planning and theoretically prove that the standard discrete diffusion training evidence lower bound (ELBO) does not accurately describe a denoiser that uses a non-uniform planner. To address this gap, we derive a new planned evidence lower bound (P-ELBO) that incorporates planner-based reverse dynamics directly into the training objective.
Using the P-ELBO, we introduce *Planner Aware Path Learning* (PAPL), a novel training scheme that aligns training and inference under a planned denoiser.
PAPL is implemented as a simple yet effective modification to the standard masked discrete diffusion loss, making it widely applicable and easy to adopt.
Empirically, we show PAPL delivers consistent gains across domains, including a 40% relative improvement in protein sequences, improved text generation with up to a 4x relative MAUVE gain, and 23% relative improvement in code generation HumanEval pass@10.

**摘要翻译**:

扩散语言模型作为自回归模型的强有力替代方案已经崭露头角，通过更灵活和并行的生成路径实现快速推理。这种采样灵活性通过新的采样策略（即规划器）来实现，规划器通过迭代规划——而非均匀随机——选择在序列中何处去噪，从而选取更有利的生成路径。然而，规划器通过修改逆向路径，在训练时的均匀随机去噪路径与基于规划的推理之间产生了不可逆的不匹配。本文系统地研究了在规划条件下离散扩散训练与推理之间的不匹配问题，并从理论上证明了标准的离散扩散训练证据下界（ELBO）无法准确描述使用非均匀规划器的去噪器。为弥补这一差距，我们推导了一个新的规划证据下界（P-ELBO），将基于规划器的逆向动态直接纳入训练目标。基于 P-ELBO，我们引入了规划器感知路径学习（PAPL），一种新颖的训练方案，使训练和推理在规划去噪器下保持一致。PAPL 作为对标准掩码离散扩散损失的简单而有效的修改来实现，使其广泛适用且易于采用。实验表明，PAPL 在各个领域均带来了持续的提升，包括蛋白质序列上 40% 的相对改进、文本生成中高达 4 倍的 MAUVE 相对增益，以及代码生成 HumanEval pass@10 上 23% 的相对改进。

---

## 135. PateGAIL++: Utility Optimized Private Trajectory Generation with Imitation Learning

**PateGAIL++：基于模仿学习的效用优化隐私轨迹生成**

**OpenReview**: [https://openreview.net/forum?id=Oyfz6G0hmc](https://openreview.net/forum?id=Oyfz6G0hmc)

**Authors**: Yingjie Ma, Bijal Bharadva (San Diego State University), Xin Zhang (San Diego State University), Joann Qiongna Chen

**Institutions**: San Diego State University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Differential Privacy, Imitation Learning

**Abstract**:

Human mobility trajectory data supports a wide range of applications, including urban planning, intelligent transportation systems, and public safety monitoring. However, large-scale, high-quality mobility datasets are difficult to obtain due to privacy concerns. Raw trajectory data may reveal sensitive user information, such as home addresses, routines, or social relationships, making it crucial to develop privacy-preserving alternatives.
Recent advances in deep generative modeling have enabled synthetic trajectory generation, but existing methods either lack formal privacy guarantees or suffer from reduced utility and scalability. Differential Privacy (DP) has emerged as a rigorous framework for data protection, and recent efforts such as PATE-GAN and PateGail integrate DP with generative adversarial learning. While promising, these methods struggle to generalize across diverse trajectory patterns and often incur significant utility degradation.
In this work, we propose a new framework that builds on PateGail++ by introducing a sensitivity-aware noise injection module that dynamically adjusts privacy noise based on sample-level sensitivity. This design significantly improves trajectory fidelity, downstream task performance, and scalability under strong privacy guarantees. We further adapt our framework to the local differential privacy (LDP) setting, allowing individual-level protection without reliance on a trusted server. We evaluate our method on a real-world mobility dataset and demonstrate its superiority over state-of-the-art baselines in terms of privacy-utility trade-off.

**摘要翻译**:

人类移动轨迹数据支撑着广泛的应用，包括城市规划、智能交通系统和公共安全监控。然而，由于隐私问题，大规模、高质量的移动数据集难以获取。原始轨迹数据可能泄露敏感的用户信息，如家庭住址、日常习惯或社交关系，因此开发隐私保护的替代方案至关重要。深度生成建模的最新进展使合成轨迹生成成为可能，但现有方法要么缺乏正式的隐私保证，要么面临效用降低和可扩展性不足的问题。差分隐私（DP）已成为数据保护的严格框架，近期的工作如 PATE-GAN 和 PateGail 将 DP 与生成对抗学习相结合。虽然前景可期，但这些方法难以在多样化的轨迹模式中泛化，且往往导致显著的效用下降。本文提出了一个建立在 PateGail++ 基础上的新框架，引入了敏感度感知的噪声注入模块，根据样本级敏感度动态调整隐私噪声。这一设计在强隐私保证下显著提升了轨迹保真度、下游任务性能和可扩展性。我们进一步将框架适配到本地差分隐私（LDP）设置，实现了无需依赖可信服务器的个体级保护。我们在真实世界的移动数据集上评估了该方法，证明了其在隐私-效用权衡方面优于最先进的基线方法。

---

## 136. MetaEmbed: Scaling Multimodal Retrieval at Test-Time with Flexible Late Interaction

**MetaEmbed：通过灵活后期交互实现测试时多模态检索扩展**

**OpenReview**: [https://openreview.net/forum?id=yKDqg9HwZX](https://openreview.net/forum?id=yKDqg9HwZX)

**Authors**: Zilin Xiao (Rice University), Qi Ma (Meta), Mengting Gu (Facebook), Chun-cheng Jason Chen (Facebook), Xintao Chen (Facebook), Vicente Ordonez (Rice University), Vijai Mohan (Meta)

**Institutions**: Rice University, Meta, Facebook

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: multimodal retrieval, information retrieval

**Abstract**:

Universal multimodal embedding models have achieved great success in capturing semantic relevance between queries and candidates. However, current methods either condense queries and candidates into a single vector, potentially limiting the expressiveness for fine-grained information, or produce too many vectors that are prohibitively expensive for multi-vector retrieval. In this work, we introduce MetaEmbed, a new framework for multimodal retrieval that rethinks how multimodal embeddings are constructed and interacted with at scale. During training, a fixed number of learnable Meta Tokens are appended to the input sequence. At test-time, their last-layer contextualized representations serve as compact yet expressive multi-vector embeddings. Through the proposed Matryoshka Multi-Vector Retrieval training, MetaEmbed learns to organize information by granularity across multiple vectors. As a result, we enable test-time scaling in multimodal retrieval where users can balance retrieval quality against efficiency demands by selecting the number of tokens used for indexing and retrieval interactions. Extensive evaluations on the Massive Multimodal Embedding Benchmark (MMEB) and the Visual Document Retrieval Benchmark (ViDoRe) confirm that MetaEmbed achieves state-of-the-art retrieval performance while scaling robustly to models with 32B parameters. Code is available at https://github.com/facebookresearch/MetaEmbed.

**摘要翻译**:

通用多模态嵌入模型在捕获查询与候选项之间的语义相关性方面取得了巨大成功。然而，当前方法要么将查询和候选项压缩为单一向量，可能限制了对细粒度信息的表达能力；要么产生过多向量，使多向量检索的成本过高。本文引入了 MetaEmbed，一种多模态检索的新框架，重新思考了如何在大规模场景下构建和交互多模态嵌入。在训练阶段，固定数量的可学习 Meta Token 被附加到输入序列中。在测试时，它们最后一层的上下文化表征作为紧凑而富有表达力的多向量嵌入。通过所提出的 Matryoshka 多向量检索训练，MetaEmbed 学习按粒度在多个向量之间组织信息。由此，我们在多模态检索中实现了测试时缩放，用户可以通过选择用于索引和检索交互的 token 数量来平衡检索质量与效率需求。在 Massive Multimodal Embedding Benchmark（MMEB）和 Visual Document Retrieval Benchmark（ViDoRe）上的广泛评估证实，MetaEmbed 达到了最先进的检索性能，同时稳健地扩展至 32B 参数的模型。代码已开源于 https://github.com/facebookresearch/MetaEmbed。

---

## 137. Monocular Normal Estimation via Shading Sequence Estimation

**通过光照序列估计实现单目法线估计**

**OpenReview**: [https://openreview.net/forum?id=d7itDxMD1n](https://openreview.net/forum?id=d7itDxMD1n)

**Authors**: Zongrui Li (Nanyang Technological University), Xinhua Ma (Nanyang Technological University), Minghui Hu (Spellbrush), Yunqing Zhao (ByteDance Inc.), Yingchen Yu (Nanyang Technological University), Qian Zheng (Zhejiang University), Chang Liu, Xudong Jiang (Nanyang Technological University), Song Bai (MiroMind)

**Institutions**: Nanyang Technological University, Spellbrush, ByteDance Inc., Zhejiang University, MiroMind

**Primary Area**: generative models

**Keywords**: Video Diffusion Model, Shading Estimation, Single-view Normal Estimation

**Abstract**:

Monocular normal estimation aims to estimate the normal map from a single RGB image of an object under arbitrary lights. Existing methods rely on deep models to directly predict normal maps. However, they often suffer from 3D misalignment: while the estimated normal maps may appear to have a correct appearance, the reconstructed surfaces often fail to align with the 3D geometry. We argue that this misalignment stems from the current paradigm: the model struggles to distinguish and reconstruct varying geometry represented in normal maps, as the differences in underlying geometry are reflected only through relatively subtle color variations. To address this issue, we propose a new paradigm that reformulates normal estimation as shading sequence estimation, where shading sequences are more sensitive to various geometry information. Building on this paradigm, we present RoSE, a method that leverages image-to-video generative models to predict shading sequences. The predicted shading sequences are then converted into normal maps by solving a simple ordinary least-squares problem. To enhance robustness and better handle complex objects, RoSE is trained on a synthetic dataset, MultiShade, with diverse shapes, materials, and light conditions. Experiments demonstrate that RoSE achieves state-of-the-art performance on both synthetic and real-world benchmark datasets for object-based monocular normal estimation.

**摘要翻译**:

单目法线估计旨在从任意光照条件下物体的单张 RGB 图像中估计法线图。现有方法依赖深度模型直接预测法线图。然而，它们常遭受三维错位问题：虽然估计的法线图在外观上可能看似正确，但重建的表面往往无法与三维几何对齐。我们认为这种错位源于当前的范式：模型难以区分和重建法线图中表示的不同几何形状，因为底层几何的差异仅通过相对细微的颜色变化来反映。为解决这一问题，我们提出了一种新范式，将法线估计重新表述为光照序列估计，其中光照序列对各种几何信息更加敏感。基于这一范式，我们提出了 RoSE，一种利用图像到视频生成模型来预测光照序列的方法。预测的光照序列随后通过求解简单的普通最小二乘问题转换为法线图。为增强鲁棒性并更好地处理复杂物体，RoSE 在合成数据集 MultiShade 上进行训练，该数据集包含多样化的形状、材质和光照条件。实验表明，RoSE 在合成和真实世界基准数据集上的基于物体的单目法线估计中均达到了最先进的性能。

---

## 138. Shoot First, Ask Questions Later? Building Rational Agents that Explore and Act Like People

**先开枪后提问？构建像人类一样探索和行动的理性智能体**

**OpenReview**: [https://openreview.net/forum?id=EQhUvWH78U](https://openreview.net/forum?id=EQhUvWH78U)

**Authors**: Gabriel Grand (Massachusetts Institute of Technology), Valerio Pepe (School of Engineering and Applied Sciences, Harvard University), Joshua B. Tenenbaum (Massachusetts Institute of Technology), Jacob Andreas (Massachusetts Institute of Technology)

**Institutions**: Massachusetts Institute of Technology, School of Engineering and Applied Sciences, Harvard University

**Primary Area**: applications to neuroscience & cognitive science

**Keywords**: Bayesian experimental design, information-seeking, question asking, Collaborative Battleship, expected information gain (EIG), explore-exploit tradeoffs, resource rationality, probabilistic inference, Monte Carlo sampling, symbolic grounding, code generation, reasoning, decision-oriented dialogue, cognitive modeling, human behavior, language model agents, scientific discovery

**TL;DR**: We introduce a collaborative Battleship task to evaluate information-seeking in humans and agents; insights from Bayesian Experimental Design (BED) yield inference-time strategies for building resource-rational agents in discovery settings.

**TL;DR翻译**: 我们引入了一个协作式战舰任务来评估人类和智能体的信息搜寻行为；来自贝叶斯实验设计（BED）的洞察为在发现场景中构建资源理性智能体提供了推理时策略。

**Abstract**:

Many emerging applications of AI--from scientific discovery to medical diagnosis--require agents to seek information strategically: forming hypotheses, asking targeted questions, and making decisions under uncertainty. In high-stakes settings with limited resources, do language models (LMs) behave like rational agents? Drawing on insights from human cognition, we develop methods to evaluate and enhance agentic information-seeking. First, we introduce a decision-oriented dialogue task called Collaborative Battleship, in which a Captain must balance exploration (asking questions) and action (taking shots), while a Spotter must supply accurate, contextually-grounded answers. Compared to human players (N=42), we find that many LM agents struggle to ask informative questions, produce accurate answers, and identify high-utility actions. To address these gaps, we develop novel Monte Carlo inference strategies for LMs inspired by Bayesian Experimental Design (BED). For Spotter agents, our approach boosts accuracy by up to 14.7% absolute over LM-only baselines; for Captain agents, it raises expected information gain (EIG) by up to 0.227 bits (94.2% of the achievable noise ceiling). Combined, these components yield sharper targeting (+0.303-0.374 F1), and enable weaker LMs, such as Llama-4-Scout, to outperform both humans (8% to 82% win rate) and frontier models (0% to 67% win rate vs. GPT-5) at approximately 1% of GPT-5's cost. We replicate these findings on Guess Who?, where our methods significantly boost accuracy (+28.3-42.4 p.p.), demonstrating their general applicability for building information-seeking agents.

**摘要翻译**:

许多新兴的人工智能应用——从科学发现到医学诊断——都要求智能体进行策略性的信息搜寻：形成假设、提出有针对性的问题，并在不确定性下做出决策。在资源有限的高风险场景中，语言模型（LMs）是否像理性智能体一样行动？借鉴人类认知的洞察，我们开发了评估和增强智能体信息搜寻能力的方法。首先，我们引入了一个称为协作式战舰的面向决策的对话任务，其中舰长必须在探索（提问）和行动（射击）之间取得平衡，而观测员必须提供准确的、基于上下文的回答。与人类玩家（N=42）相比，我们发现许多 LM 智能体在提出信息量丰富的问题、产生准确回答和识别高效用行动方面表现不佳。为弥补这些差距，我们受贝叶斯实验设计（BED）启发，开发了面向 LM 的新颖蒙特卡洛推理策略。对于观测员智能体，我们的方法相比纯 LM 基线将准确率绝对提升了高达 14.7%；对于舰长智能体，期望信息增益（EIG）提升了高达 0.227 比特（达到可实现噪声上限的 94.2%）。这些组件结合在一起产生了更精准的目标定位（F1 提升 +0.303-0.374），并使较弱的 LM（如 Llama-4-Scout）以大约 GPT-5 1% 的成本超越了人类（胜率从 8% 提升至 82%）和前沿模型（对阵 GPT-5 的胜率从 0% 提升至 67%）。我们在 Guess Who? 游戏上复现了这些发现，我们的方法显著提升了准确率（+28.3-42.4 个百分点），证明了其在构建信息搜寻智能体方面的普遍适用性。

---

## 139. Intrinsic Entropy of Context Length Scaling in LLMs

**大语言模型中上下文长度缩放的内在熵**

**OpenReview**: [https://openreview.net/forum?id=vnipyA8c9V](https://openreview.net/forum?id=vnipyA8c9V)

**Authors**: Jingzhe Shi (Tsinghua University), Qinwei Ma (Tsinghua University, Tsinghua University), Hongyi Liu (CMU, Carnegie Mellon University), Hang Zhao (Tsinghua University, Tsinghua University), Jenq-Neng Hwang (University of Washington, Seattle), Lei Li

**Institutions**: Tsinghua University, Tsinghua University, Tsinghua University, CMU, Carnegie Mellon University, University of Washington, Seattle

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: context length, intrinsic entropy

**TL;DR**: We propose to use Intrinsic Entropy for understanding impact of context length on Language Modeling, and conduct experiments to validate theoretical assumptions and deductions with language and synthetic datasets.

**TL;DR翻译**: 我们提出使用内在熵来理解上下文长度对语言建模的影响，并通过语言数据集和合成数据集的实验验证了理论假设和推论。

**Abstract**:

There has been work discussing the impact of long context on Language Model performance: some find that long irrelevant context could harm performance, while some experimentally summarize loss reduction by relevant long context as Scaling Laws. This calls for a more thorough understanding on how long context impacts Language Modeling. In this work, we (1) propose to use Intrinsic Entropy for explaining the impact of context length on language modeling; and (2) conduct experiments on natural language and synthetic data, validating our proposed theoretical assumptions and deductions. Our theoretical framework can provide practical insights such as establishing that training dataset size dictates an optimal context length and bounds context length scaling for certain cases. We hope our work may inspire new long context Language Models, as well as future work studying Physics for Language Models.

**摘要翻译**:

已有工作探讨了长上下文对语言模型性能的影响：一些研究发现长的无关上下文会损害性能，另一些则通过实验将相关长上下文带来的损失降低总结为缩放定律。这要求我们更深入地理解长上下文如何影响语言建模。在本文中，我们 (1) 提出使用内在熵来解释上下文长度对语言建模的影响；(2) 在自然语言和合成数据上进行实验，验证了我们提出的理论假设和推论。我们的理论框架能够提供实用的洞察，例如证明训练数据集大小决定了最优上下文长度，并在特定情况下为上下文长度缩放设定了边界。我们希望本文能够启发新的长上下文语言模型，以及未来研究语言模型物理学的工作。

---

## 140. Latent Particle World Models: Self-supervised Object-centric Stochastic Dynamics Modeling

**潜在粒子世界模型：自监督的以物体为中心的随机动力学建模**

**OpenReview**: [https://openreview.net/forum?id=lTaPtGiUUc](https://openreview.net/forum?id=lTaPtGiUUc)

**Authors**: Tal Daniel (Carnegie Mellon University), Carl Qi (University of Texas at Austin), Dan Haramati (Brown University), Amir Zadeh (Lambda), Chuan Li (Lambda), Aviv Tamar (Technion, Technion), Deepak Pathak (Skild AI), David Held (Amazon)

**Institutions**: Carnegie Mellon University, University of Texas at Austin, Brown University, Lambda, Technion, Technion, Skild AI, Amazon

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: World Model, Self-supervised, unsupervised, object-centric, video prediciton, video generation, imitation learning, latent particles, vae

**TL;DR**: a self-supervised object-centric world model that learns keypoints, and masks directly from videos, supports multi-modal conditioning, scaled to real-world multi-object datasets

**TL;DR翻译**: 一种自监督的以物体为中心的世界模型，直接从视频中学习关键点和掩码，支持多模态条件输入，已扩展至真实世界多物体数据集。

**Abstract**:

We introduce Latent Particle World Model (LPWM), a self-supervised object-centric world model scaled to real-world multi-object datasets and applicable in decision-making. LPWM autonomously discovers keypoints, bounding boxes, and object masks directly from video data, enabling it to learn rich scene decompositions without supervision. Our architecture is trained end-to-end purely from videos and supports flexible conditioning on actions, language, and image goals. LPWM models stochastic particle dynamics via a novel latent action module and achieves state-of-the-art results on diverse real-world and synthetic datasets. Beyond stochastic video modeling, LPWM is readily applicable to decision-making, including goal-conditioned imitation learning, as we demonstrate in the paper. Code, data, pre-trained models and video rollouts are available: https://taldatech.github.io/lpwm-web

**摘要翻译**:

我们引入了潜在粒子世界模型（LPWM），一种自监督的以物体为中心的世界模型，已扩展至真实世界多物体数据集并可应用于决策制定。LPWM 自主地从视频数据中发现关键点、边界框和物体掩码，使其能够在无监督条件下学习丰富的场景分解。我们的架构纯粹从视频端到端训练，支持对动作、语言和图像目标的灵活条件输入。LPWM 通过新颖的潜在动作模块建模随机粒子动力学，在多种真实世界和合成数据集上达到了最先进的结果。除随机视频建模外，LPWM 可直接应用于决策制定，包括目标条件模仿学习，我们在论文中对此进行了展示。代码、数据、预训练模型和视频展示已公开于：https://taldatech.github.io/lpwm-web

---

## 141. Beyond Prompt-Induced Lies: Investigating LLM Deception on Benign Prompts

**超越提示诱导的谎言：研究LLM在良性提示下的欺骗行为**

**OpenReview**: [https://openreview.net/forum?id=PDBBYwd1LY](https://openreview.net/forum?id=PDBBYwd1LY)

**Authors**: Zhaomin Wu (National University of Singapore), Mingzhe Du (Nanyang Technological University), See-Kiong Ng (National University of Singapore), Bingsheng He (National University of Singapore)

**Institutions**: National University of Singapore, Nanyang Technological University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Large Language Model, Deception, Lie, Honest, Trustworthy

**TL;DR**: We detected the widespread deception of LLM under benign prompts and found its tendency increases with task difficulty.

**TL;DR翻译**: 我们检测到了LLM在良性提示下的广泛欺骗行为，并发现其欺骗倾向随任务难度的增加而上升。

**Abstract**:

Large Language Models (LLMs) are widely deployed in reasoning, planning, and decision-making tasks, making their trustworthiness critical. A significant and underexplored risk is intentional deception, where an LLM deliberately fabricates or conceals information to serve a hidden objective. Existing studies typically induce deception by explicitly setting a hidden objective through prompting or fine-tuning, which may not reflect real-world human-LLM interactions. Moving beyond such human-induced deception, we investigate LLMs' self-initiated deception on benign prompts. To address the absence of ground truth, we propose a framework based on Contact Searching Questions~(CSQ). This framework introduces two statistical metrics derived from psychological principles to quantify the likelihood of deception. The first, the *Deceptive Intention Score*, measures the model's bias toward a hidden objective. The second, the *Deceptive Behavior Score*, measures the inconsistency between the LLM's internal belief and its expressed output. Evaluating 16 leading LLMs, we find that both metrics rise in parallel and escalate with task difficulty for most models. Moreover, increasing model capacity does not always reduce deception, posing a significant challenge for future LLM development.

**摘要翻译**:

大语言模型（LLM）被广泛部署于推理、规划和决策任务中，其可信性至关重要。一个重大且尚未充分探索的风险是蓄意欺骗，即LLM为达成隐藏目标而故意编造或隐瞒信息。现有研究通常通过提示或微调显式设定隐藏目标来诱导欺骗，这可能无法反映真实的人机交互场景。超越这种人为诱导的欺骗，我们研究了LLM在良性提示下的自发欺骗行为。为解决缺乏真实标签的问题，我们提出了基于接触搜索问题（CSQ）的框架。该框架引入了两个源自心理学原理的统计指标来量化欺骗的可能性。第一个是*欺骗意图得分*，衡量模型对隐藏目标的偏向程度。第二个是*欺骗行为得分*，衡量LLM内部信念与其外在输出之间的不一致性。通过评估16个主流LLM，我们发现这两个指标在大多数模型中同步上升，并随任务难度的增加而加剧。此外，增加模型容量并不总能减少欺骗行为，这对未来的LLM开发构成了重大挑战。

---

## 142. LLM DNA: Tracing Model Evolution via Functional Representations

**LLM DNA：通过功能表示追踪模型演化**

**OpenReview**: [https://openreview.net/forum?id=UIxHaAqFqQ](https://openreview.net/forum?id=UIxHaAqFqQ)

**Authors**: Zhaomin Wu (National University of Singapore), Haodong Zhao (Shanghai Jiaotong University), Ziyang Wang (national university of singaore, National University of Singapore), Jizhou Guo (Shanghai Jiao Tong University), Qian Wang (National University of Singapore), Bingsheng He (National University of Singapore)

**Institutions**: National University of Singapore, Shanghai Jiaotong University, national university of singaore, National University of Singapore, Shanghai Jiao Tong University

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Large Language Model, Representations, Fingerprint, Embedding, Evolution, Phylogenetic Tree, DNA, Dimension Reduction

**TL;DR**: We introduce LLM DNA, a low-dimensional representation of LLMs, uncovers undocumented relations and constructs phylogenetic tree for LLM.

**TL;DR翻译**: 我们提出了LLM DNA——一种LLM的低维表示，揭示了未记录的模型关系并构建了LLM的系统发育树。

**Abstract**:

The explosive growth of large language models (LLMs) has created a vast but opaque landscape: millions of models exist, yet their evolutionary relationships through fine-tuning, distillation, or adaptation remain largely unclear. We introduce LLM DNA, a compact, low-dimensional functional representation designed to systematically uncover these hidden relationships. LLM DNA is constructed by collecting a model's logit outputs on carefully designed prompts and compressing them into a low-dimensional representation via kernelized dimensionality reduction. This representation enables similarity search, clustering, and evolutionary tracing. We build LLM DNA profiles for over 7,000 LLMs and demonstrate their effectiveness across several tasks: (1) in controlled fine-tuning and distillation experiments, LLM DNA traces known lineages with 100\% accuracy; (2) at scale across Hugging Face models, LLM DNA uncovers undocumented relations and detects potential rebranding; (3) we construct evolutionary trees of LLMs using phylogenetic algorithms, which align with shifts from encoder-decoder to decoder-only architectures, reflect temporal progression, and reveal distinct evolutionary speeds across LLM families.

**摘要翻译**:

大语言模型（LLM）的爆发式增长创造了一个庞大但不透明的生态：数百万个模型存在于世，但它们通过微调、蒸馏或适配进行演化的关系在很大程度上仍不清晰。我们提出了LLM DNA——一种紧凑的低维功能表示——旨在系统性地揭示这些隐藏关系。LLM DNA通过在精心设计的提示上收集模型的logit输出来构建，并利用核化降维技术将其压缩为低维表示。这种表示方法能够实现相似性搜索、聚类和演化追踪。我们在7,000多个LLM上构建了LLM DNA谱，并在多项任务中展示了其有效性：（1）在受控的微调和蒸馏实验中，LLM DNA以100%的准确率追踪已知的亲缘关系；（2）在大规模的Hugging Face模型中，LLM DNA揭示了未记录的关系，并检测到可能的模型重新品牌化行为；（3）我们利用系统发育算法构建了LLM的演化树，这些演化树与从编码器-解码器到仅解码器架构的转变相一致，反映了时间上的演进，并揭示了不同LLM家族间截然不同的演化速度。

---

## 143. Generative Universal Verifier as Multimodal Meta-Reasoner

**生成式通用验证器作为多模态元推理器**

**OpenReview**: [https://openreview.net/forum?id=DM0Y0oL33T](https://openreview.net/forum?id=DM0Y0oL33T)

**Authors**: Xinchen Zhang (ByteDance Seed), Xiaoying Zhang (ByteDance AILab), Youbin Wu (ByteDance Inc.), Yanbin Cao (Peking University), Renrui Zhang (MMLab of CUHK & Shanghai AI Laboratory), Ruihang Chu (Wan Team), Ling Yang (Princeton University), Yujiu Yang (Tsinghua University), Guang Shi (ByteDance Inc.)

**Institutions**: ByteDance Seed, ByteDance AILab, ByteDance Inc., Peking University, MMLab of CUHK & Shanghai AI Laboratory, Wan Team, Princeton University, Tsinghua University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Multimodal Large Language Models

**Abstract**:

We introduce *Generative Universal Verifier*, a novel concept and plugin designed for next-generation multimodal reasoning in vision-language models and unified multimodal models, providing the fundamental basis for trustworthy and controllable visual reasoning. Current verification approaches face critical limitations: classification-based verifiers are restricted by fixed assessment criteria and lack reasoning explainability; text-only generative verifiers lack visual verification capabilities. To address these limitations, we propose OmniVerifier, the first multimodal generative verifier capable of both language and visual verification to evaluate and refine candidate answers generated by vision-language models and unified multimodal models. Trained on the carefully constructed OmniVerifier-8M dataset, which contains 8 million multimodal verification samples spanning text and visual modalities, OmniVerifier can not only verify the correctness of generated answers, but also jointly produce both textual and visual feedback as verification rationale. Extensive experiments demonstrate strong generalization across diverse reasoning scenarios, covering vision-language models and unified multimodal models. By unifying textual and visual verification, OmniVerifier advances both reliable reflection during generation and scalable test-time refinement, marking a step toward more trustworthy and controllable next-generation reasoning systems.

**摘要翻译**:

我们引入了*生成式通用验证器*这一新概念和插件，专为视觉语言模型和统一多模态模型中的下一代多模态推理而设计，为可信和可控的视觉推理提供基础。当前验证方法面临关键限制：基于分类的验证器受限于固定的评估标准和推理可解释性不足；纯文本生成式验证器缺乏视觉验证能力。为解决这些局限，我们提出了OmniVerifier——首个多模态生成式验证器，它能够同时进行语言和视觉验证，以评估和精炼由视觉语言模型和统一多模态模型生成的候选答案。通过在精心构建的OmniVerifier-8M数据集上训练——该数据集包含800万个多模态验证样本，涵盖文本和视觉模态——OmniVerifier不仅具备验证生成答案正确性的能力，还能联合产生文本和视觉反馈作为验证推理依据。大量实验表明，OmniVerifier在涵盖视觉语言模型和统一多模态模型的不同推理场景下均展现出强大的泛化能力。通过统一文本和视觉验证，OmniVerifier推进了生成过程中的可靠反思和可扩展的测试时精炼，标志着向更可信和可控的下一代推理系统迈出了重要一步。

---

## 144. $PhyWorldBench$: A Comprehensive Evaluation of Physical Realism in Text-to-Video Models

**PhyWorldBench：文本到视频模型物理真实感的综合评估**

**OpenReview**: [https://openreview.net/forum?id=rlZeILv3fm](https://openreview.net/forum?id=rlZeILv3fm)

**Authors**: Jing Gu (xAI), Xian Liu (xAI), Yu Zeng (NVIDIA), Ashwin Nagarajan (University of California, Santa Cruz), Fangrui Zhu (Northeastern University), Daniel Hong (University of California, Santa Cruz), Yue Fan (University of California, Santa Cruz), Qianqi Yan (University of California, Santa Barbara), Kaiwen Zhou (University of California, Santa Cruz), Ming-Yu Liu (NVIDIA), Xin Eric Wang (University of California, Santa Barbara)

**Institutions**: xAI, NVIDIA, University of California, Santa Cruz, Northeastern University, University of California, Santa Barbara

**Primary Area**: datasets and benchmarks

**Keywords**: Video Generation, Video Evaluation

**TL;DR**: Large-scale, multidimensional video generation for physics

**TL;DR翻译**: 面向物理真实感的大规模、多维度视频生成评估

**Abstract**:

Video generation models have achieved remarkable progress in creating high-quality, photorealistic content. However, their ability to accurately simulate physical phenomena remains a critical and unresolved challenge. To bridge this gap, we introduce PhyWorldBench, a comprehensive benchmark specifically designed to evaluate physical world knowledge in text-to-video models. Our benchmark spans 15 physical domains with multiple evaluation dimensions for each. It contains a video database covering diverse physical domains and a suite of physical evaluation models for automated assessment. We evaluate 17 text-to-video models, revealing significant limitations: current models frequently fail to accurately represent physical phenomena even in basic scenarios, with domains like thermodynamics, electromagnetism, and waves proving especially challenging. Additionally, we explore the influence of strategies such as prompt enhancement and image guidance on model physical realism. We systematically study these factors by evaluating physical realism using both text-enhanced and image-enhanced methods, then rigorously examine their performance on diverse physical phenomena with varying prompt types, deriving targeted recommendations for crafting prompts that enhance fidelity to physical principles.

**摘要翻译**:

视频生成模型在创建高质量、逼真内容方面取得了显著进展。然而，它们准确模拟物理现象的能力仍然是一个关键且未得到充分解决的挑战。为弥合这一差距，我们推出了PhyWorldBench——一个专门用于评估文本到视频模型物理世界知识的综合基准。我们的基准跨越15个物理领域，为每个领域提供多种评估维度。它包含一个涵盖多样物理域的视频数据库以及一套用于自动化评估的物理评估模型。我们以此评估了17个文本到视频模型，揭示了当前模型的显著局限性：即使在基本场景中，它们也常常无法准确表现物理现象，其中热力学、电磁学和波动等领域尤其具有挑战性。此外，我们探索了提示增强和图像引导等策略对模型物理真实感的影响。我们通过使用文本和图像增强方法评估物理真实感来系统地研究这些因素，然后严格检验模型在不同物理现象和不同提示类型下的表现，得出针对性建议以优化提示设计，从而提升物理原理的忠实度。

---

## 145. WoW!: World Models in a Closed-Loop World

**WoW!：闭环世界中的世界模型**

**OpenReview**: [https://openreview.net/forum?id=yDmb7xAfeb](https://openreview.net/forum?id=yDmb7xAfeb)

**Authors**: Jiahan Zhang, Muqing Jiang (Peking University), Nanru Dai (Johns Hopkins University), TaiMing Lu (Princeton University), Arda Uzunoglu (Johns Hopkins University), Shunchi Zhang, Yana Wei (Johns Hopkins University), Jiahao Wang, Vishal M. Patel (Johns Hopkins University), Paul Pu Liang (Massachusetts Institute of Technology), Daniel Khashabi (Johns Hopkins University), Cheng Peng (School of Data Science, University of Virginia), Rama Chellappa, Tianmin Shu (Johns Hopkins University), Alan Yuille (Johns Hopkins University), Yilun Du (Google), Jieneng Chen (Johns Hopkins University)

**Institutions**: Peking University, Johns Hopkins University, Princeton University, Massachusetts Institute of Technology, School of Data Science, University of Virginia, Google

**Primary Area**: generative models

**Keywords**: world models, video generation, embodied AI, generative models

**TL;DR**: By grounding assessment in embodied task success instead of video metrics, WoW! provides a principled yardstick for future research on generative world models in the context of embodiment

**TL;DR翻译**: 通过将评估建立在具身任务成功率而非视频指标之上，WoW!为具身场景中生成式世界模型的未来研究提供了一个有原则的评估标准。

**Abstract**:

Generative world models (WMs) can now simulate worlds with striking visual realism, which naturally raises the question of whether they can endow embodied agents with predictive perception for decision-making. We introduce WoW!, a benchmark designed to rigorously answer this question. The core design principle of WoW! is that evaluation must be closed-loop-centric: world models should not be judged merely on visual quality or open-loop predictions, but on their capacity to assist task completion within a full perception-action loop. WoW! offers a suite of embodied tasks spanning manipulation and navigation with scalable difficulty levels and adopts a standardized closed-loop protocol under which world models participate directly in an agent's planning and decision loop. We systematically evaluate multiple world model families (autoregressive, diffusion, and video-prediction types), revealing the following key findings: (i) current world models perform strongly on open-loop metrics but yield only marginal closed-loop improvements, exposing a significant blind spot in current evaluation; (ii) appropriately scaling inference-time compute allows WMs to substantially improve closed-loop performance. By centering evaluation on closed-loop outcomes, WoW! establishes a new benchmark for the systematic assessment of WMs.

**摘要翻译**:

生成式世界模型（WM）如今能够以惊人的视觉真实感模拟世界，这自然引发了一个问题：它们能否赋予具身智能体预测性感知以支持决策。我们引入了WoW!基准来严格回答这个问题。WoW!的核心设计原则是评估必须以闭环为中心：世界模型不应仅通过视觉质量或开环预测来评判，而应通过其在完整感知-行动循环中协助任务完成的能力来评判。WoW!提供了一套涵盖操作和导航的具身任务套件，具有可扩展的难度级别，并采用标准化的闭环协议，通过该协议世界模型直接参与智能体的规划和决策循环。我们系统性地评估了多个世界模型族（自回归型、扩散型和视频预测型），揭示了以下关键发现：（i）当前的世界模型在开环指标上表现强劲，但在闭环场景中仅带来边际提升，凸显了当前评估方法中的显著盲区；（ii）适当扩展推理时计算资源能使世界模型显著提升闭环性能。通过将评估聚焦于闭环结果，WoW!为世界模型的系统性评估建立了新的基准。

---

## 146. Multimodal Aligned Semantic Knowledge for Unpaired Image-text Matching

**面向无配对图文匹配的多模态对齐语义知识**

**OpenReview**: [https://openreview.net/forum?id=d3CISVVO6v](https://openreview.net/forum?id=d3CISVVO6v)

**Authors**: Laiguo Yin (Shandong University), Yixin Zhang (Nanyang Technological University), YUQING SUN (Shandong University), Lizhen Cui (Shandong University)

**Institutions**: Shandong University, Nanyang Technological University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Unpaired Image-text Matching, Out-of-Distribution Word, Multimodal Aligned Semantic Knowledge, Prototype

**TL;DR**: We propose multimodal aligned semantic knowledge, which leverages word embeddings as bridges to associate words with prototypes, capturing semantic relationships between words and further utilizing information from OOD words.

**TL;DR翻译**: 我们提出了多模态对齐语义知识方法，利用词嵌入作为桥梁将词汇与原型关联，捕捉词汇间的语义关系，并进一步利用分布外词汇的信息。

**Abstract**:

While existing approaches address unpaired image-text matching by constructing cross-modal aligned knowledge, they often fail to identify semantically corresponding visual representations for Out-of-Distribution (OOD) words. Moreover, these methods overlook the semantic relationships among textual elements. To address these issues, we propose Multimodal Aligned Semantic Knowledge (MASK). By leveraging word embeddings as bridges to associate words with prototypes, MASK captures the semantic relationships between words. This allows the system to take advantage of information from OOD words to derive reasonable visual representations for them. Furthermore, while prototypes can effectively summarize in-distribution knowledge, their inherent variance may introduce biases in the feature space. To mitigate this, we employ multiple groups of prototypes to reduce variance in the feature space, effectively mitigating the adverse effects of variance. Experimental results on the Flickr30K and MSCOCO datasets demonstrate that MASK achieves superior performance in unpaired matching.

**摘要翻译**:

现有方法通过构建跨模态对齐知识来解决无配对图文匹配问题，但它们往往难以为分布外（OOD）词汇识别语义对应的视觉表示。此外，这些方法忽略了文本元素之间的语义关系。为解决这些问题，我们提出了多模态对齐语义知识（MASK）方法。通过利用词嵌入作为桥梁来关联词汇与原型，MASK捕捉了词汇之间的语义关系。这使得系统能够利用OOD词汇的信息为其推导合理的视觉表示。此外，尽管原型能有效地总结分布内知识，但其内在方差可能在特征空间中引入偏差。为缓解这一问题，我们采用多组原型以减少特征空间中的方差，有效缓解了方差带来的不利影响。在Flickr30K和MSCOCO数据集上的实验结果表明，MASK在无配对匹配任务中取得了优越的性能。

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

---

## 148. The Spacetime of Diffusion Models: An Information Geometry Perspective

**扩散模型的时空结构：信息几何视角**

**OpenReview**: [https://openreview.net/forum?id=qCsbYJZRA5](https://openreview.net/forum?id=qCsbYJZRA5)

**Authors**: Rafal Karczewski (Aalto University), Markus Heinonen (Aalto University), Alison Pouplin, Søren Hauberg (Technical University of Denmark), Vikas K Garg

**Institutions**: Aalto University, Technical University of Denmark

**Primary Area**: generative models

**Keywords**: diffusion models, information geometry

**Abstract**:

We present a novel geometric perspective on the latent space of diffusion models. We first show that the standard pullback approach, utilizing the deterministic probability flow ODE decoder, is fundamentally flawed: it yields a degenerate metric matrix owing to the inherent dimensionality reduction of deterministic decoding. Instead, we introduce a Fisher information metric based on a stochastic decoder, which is mathematically well-grounded. This endows each point (x, t) in the latent space with a properly defined Riemannian metric, giving rise to what we term the spacetime of diffusion models. We demonstrate experimentally that geodesics in this spacetime naturally correspond to meaningful semantic interpolations, even when target points are not close together. Furthermore, we provide a deep analysis of the role of the time dimension (diffusion time): although it is typically viewed as a noise control parameter, within our framework it becomes an integral part of the spacetime metric. We show that the sectional curvature of the spacetime is highly time-dependent, with low-noise regimes exhibiting greater curvature. Finally, we demonstrate the framework's applicability to transition path sampling in molecular systems, including constrained variants such as low-variance transitions and region avoidance. Code is available at: https://github.com/rafalkarczewski/spacetime-geometry.

**摘要翻译**:

我们提出了一种关于扩散模型隐空间的新颖几何视角。我们首先证明，利用确定性概率流ODE解码器的标准回拉方法从根本上存在缺陷：由于确定性解码固有的降维特性，该方法产生的度量矩阵是退化的。为此，我们转而引入一种基于随机解码器的Fisher信息度量，该方法在数学上是严格的。这使得潜在空间中的每个点(x, t)拥有了一个适当定义的黎曼度量，从而形成了我们所称的扩散模型时空。我们在实验中展示了该时空中的测地线自然对应于有意义的语义插值，即使目标点之间并不相近。此外，我们深入分析了时间维度（扩散时间）的意义：尽管它通常被视为噪声控制参数，但在我们的框架中它成为时空度量的一个组成部分。我们证明时空的截面曲率与时间步高度相关，低噪声区域表现出更大的曲率。最后，我们展示了该框架在分子系统中的转变路径采样应用，包括低方差转变和区域规避等约束变体。代码可在 https://github.com/rafalkarczewski/spacetime-geometry 获取。

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

---

## 150. Information Shapes Koopman Representation

**信息塑造Koopman表示**

**OpenReview**: [https://openreview.net/forum?id=Szh0ELyQxL](https://openreview.net/forum?id=Szh0ELyQxL)

**Authors**: Xiaoyuan Cheng (University College London, University of London), Wenxuan Yuan (Imperial College London), Yiming Yang (University College London, University of London), Yuanzhao Zhang (Santa Fe Institute), Sibo Cheng (Ecole Nationale des Ponts et Chausees), Yi He (University College London, University of London), Zhuo Sun (Shanghai University of Finance and Economics)

**Institutions**: University College London, University of London, Imperial College London, Santa Fe Institute, Ecole Nationale des Ponts et Chausees, Shanghai University of Finance and Economics

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: Koopman Operator, Latent subspace reconstruction, representation for physical systems

**TL;DR**: Because the Koopman operator is infinite-dimensional, identifying tractable finite-dimensional subspaces is challenging. We aim to construct these subspaces through information theory.

**TL;DR翻译**: 由于Koopman算子是无限维的，识别可处理的有限维子空间具有挑战性。我们旨在通过信息论来构建这些子空间。

**Abstract**:

The Koopman operator provides a powerful framework for modeling dynamical systems and has attracted growing interest from the machine learning community. However, its infinite-dimensional nature makes direct application impractical, requiring the identification of suitable finite-dimensional invariant subspaces. While various machine learning approaches aim to approximate the Koopman operator, they typically lack theoretical guarantees on when and why the learned subspaces are appropriate. In this work, we use information theory to construct and analyze tractable Koopman invariant subspaces. Our approach works in two steps: first, we link the mutual information of the embedding function to the Koopman approximation error within an invariant subspace; second, we leverage this connection to derive an information-bottleneck-style learning objective. We further analyze how the Koopman approximation error decreases at a rate characterized by information-theoretic constraints as the latent dimension grows. In the finite-sample regime, we enhance the learning objective with a novel information-theoretic regularizer and prove its generalization with bounded Rademacher complexity. Experiments on Gaussian linear dynamical systems yield results consistent with our theoretical predictions. Finally, we validate our approach across a diverse range of dynamical systems, demonstrating improved performance over existing Koopman learning methods.

**摘要翻译**:

Koopman算子为动力系统建模提供了一个强大的框架，并引起了机器学习社区日益增长的关注。然而，其无限维特性使得直接应用变得不切实际，因此需要识别合适的有限维不变子空间。尽管有各种机器学习方法旨在近似Koopman算子，但它们通常缺乏理论保证来确定所学子空间何时及为何是合适的。在本工作中，我们利用信息论来构造和分析可处理的Koopman不变子空间。我们的方法分两步进行：首先，我们将嵌入函数的互信息与不变子空间中的Koopman近似误差联系起来；其次，我们利用这种联系推导出一个信息瓶颈式的学习目标。我们还进一步分析了随着潜在维度的增加，Koopman近似误差如何以信息论约束表征的速率递减。在有限样本条件下，我们通过一种新的信息理论正则化器增强了该学习目标，并证明了其在有限Rademacher复杂度条件下的泛化能力。在高斯线性动力系统上的实验结果与我们的理论预测一致。最后，我们在多种不同的动力系统上验证了我们的方法，展示了其相对于现有Koopman学习方法的性能提升。

---

## 151. Sequences of Logits Reveal the Low Rank Structure of Language Models

**Logit序列揭示语言模型的低秩结构**

**OpenReview**: [https://openreview.net/forum?id=gdZ6J5hZzF](https://openreview.net/forum?id=gdZ6J5hZzF)

**Authors**: Noah Golowich (Microsoft), Allen Liu (Massachusetts Institute of Technology), Abhishek Shetty (Massachusetts Institute of Technology)

**Institutions**: Microsoft, Massachusetts Institute of Technology

**Primary Area**: learning theory

**Keywords**: Large language models, low-rank structure

**TL;DR**: We exploit the low-rank structure of the logit matrices of LLMs to draw new empirical and theoretical conclusions.

**TL;DR翻译**: 我们利用LLM的logit矩阵的低秩结构得出了新的实证和理论结论。

**Abstract**:

A major problem in the study of large language models  is to understand their inherent low-dimensional structure.  We introduce an approach to study the low-dimensional structure of language models at the level of their logit outputs. Concretely, we observe that for a given language model, the matrix consisting of the logits over a suitably chosen set of prompts has a surprisingly small rank. We investigate this phenomenon both empirically and theoretically. Empirically, we show that the rank of the logit matrix provides a useful way to cluster language models from different families. Theoretically, we show that the low-rank phenomenon observed above yields a simple universal abstraction whose theoretical predictions parallel our experiments. We then analyze the representation power of the abstraction and give provable learning guarantees.

**摘要翻译**:

研究大语言模型的一个核心问题是理解其固有的低维结构。我们引入了一种在logit输出层面研究语言模型低维结构的方法。具体而言，我们观察到，对于给定的语言模型，由适当选择的一组提示上的logit组成的矩阵具有出人意料的小秩。我们从实证和理论两方面研究了这一现象。在实证方面，我们证明logit矩阵的秩为不同家族语言模型的聚类提供了一种有效方式。在理论方面，我们证明上述低秩现象产生了一种简单的通用抽象，其理论预测与我们的实验结果相吻合。随后，我们分析了该抽象的表示能力，并给出了可证明的学习保证。

---

## 152. BIRD-INTERACT: Re-imagining Text-to-SQL Evaluation via Lens of Dynamic Interactions

**BIRD-INTERACT：通过动态交互视角重新定义Text-to-SQL评估**

**OpenReview**: [https://openreview.net/forum?id=nHrYBGujps](https://openreview.net/forum?id=nHrYBGujps)

**Authors**: Nan Huo (the University of Hong Kong, University of Hong Kong), Xiaohan Xu (The University of Hong Kong), Jinyang Li (The University of Hong Kong), Per Jacobsson (Google), Shipei Lin (The Chinese University of Hong Kong, Shenzhen), Bowen Qin (Beijing Academy of Artificial Intelligence), Binyuan Hui (Alibaba Group), Xiaolong Li (University of Hong Kong), Ge Qu, Shuzheng Si (Tsinghua University), Linheng Han (The Chinese University of Hong Kong, Shenzhen), Edward Alexander (The Chinese University of Hong Kong), Xintong Zhu (The Chinese University of Hong Kong, Shenzhen), Rui Qin (The Chinese University of Hong Kong), Ruihan Yu (The Chinese University of Hong Kong), Yiyao Jin (The Chinese University of Hong Kong), Feige Zhou (The Chinese University of Hong Kong), Weihao Zhong (The Chinese University of Hong Kong，Shenzhen), Yun Chen (The Chinese University of Hong Kong), Hongyu Liu (Guizhou University), Chenhao Ma (The Chinese University of Hong Kong, Shenzhen), Fatma Ozcan (Google), Yannis Papakonstantinou (Google), Reynold Cheng (The University of Hong Kong)

**Institutions**: the University of Hong Kong, University of Hong Kong, The University of Hong Kong, Google, The Chinese University of Hong Kong, Shenzhen, Beijing Academy of Artificial Intelligence, Alibaba Group, University of Hong Kong, Tsinghua University, The Chinese University of Hong Kong, The Chinese University of Hong Kong，Shenzhen, Guizhou University

**Primary Area**: datasets and benchmarks

**Keywords**: Interactive, Text-to-SQL, LLM, Code Generation

**Abstract**:

Large language models (LLMs) have demonstrated remarkable performance on single-turn text-to-SQL tasks, but real-world database applications predominantly require multi-turn interactions to handle ambiguous queries, incomplete information, and dynamic user intent. To address this gap, we present BIRD-Interact, the first comprehensive benchmark designed to evaluate LLMs in the context of multi-turn, interactive text-to-SQL workflows. BIRD-Interact introduces two novel task suites: (1) Agent-Human Interaction (AHI), which evaluates an LLM agent's ability to collaborate with human users through multi-turn dialogue, and (2) Agent-Database Interaction (ADI), which tests the agent's capacity to iteratively reason with databases, validate through real continuous integration (CI) environments, and self-correct. Both suites are supported by a principled evaluation framework with interaction-centric metrics, including a Context Dependency Score (CDS), Multi-Turn Exact Match (MT-EM), and Soft F1 (SF1). Additionally, for ADI, we benchmark 18 LLMs across four difficulty levels and five database domains, and we construct our ADI dataset with 2,881 annotated interactions. We evaluate nine LLMs for the AHI task suite. Further analysis via memory grafting and Interaction Test-time Scaling (ITS), validate the importance of effective interaction for achieving success in complex, dynamic text-to-SQL tasks.

**摘要翻译**:

大语言模型（LLM）在单轮Text-to-SQL任务上展现了卓越的性能，但现实世界的数据库应用主要需要多轮交互来处理模糊查询、不完整信息和动态用户意图。为弥补这一差距，我们推出了BIRD-Interact——首个专为评估LLM在多轮交互式Text-to-SQL工作流中表现而设计的综合基准。BIRD-Interact引入了两个新颖的任务套件：（1）智能体-人类交互（AHI），评估LLM智能体通过多轮对话与人类用户协作的能力；（2）智能体-数据库交互（ADI），测试智能体与数据库迭代推理、通过真实持续集成（CI）环境验证以及自我纠正的能力。两个套件均由一个以交互为中心的评估框架支撑，包含上下文依赖得分（CDS）、多轮精确匹配（MT-EM）和软F1（SF1）等指标。此外，对于ADI，我们在四个难度级别和五个数据库领域上对18个LLM进行了基准测试，并构建了包含2,881个标注交互的ADI数据集。我们对九个LLM进行了AHI任务套件的评估。通过记忆嫁接和交互测试时扩展（ITS）的进一步分析，验证了有效交互对于在复杂动态的Text-to-SQL任务中取得成功的重要性。

---

## 153. EditVerse: Unifying Image and Video Editing and Generation with In-Context Learning

**EditVerse：通过上下文学习统一图像与视频的编辑和生成**

**OpenReview**: [https://openreview.net/forum?id=blJXE07r7I](https://openreview.net/forum?id=blJXE07r7I)

**Authors**: Xuan Ju (Chinese University of Hong Kong), Tianyu Wang (Adobe Systems), Yuqian Zhou (Adobe Systems), He Zhang (Adobe Systems), Qing Liu (Adobe Systems), Nanxuan Zhao, Zhifei Zhang (Adobe Research), Yijun Li (Adobe Research), Yuanhao Cai (Johns Hopkins University), Shaoteng Liu (Adobe Research), Daniil Pakhomov (Adobe Systems), Zhe Lin (Adobe Research), Soo Ye Kim (Adobe Systems), Qiang Xu (The Chinese University of Hong Kong)

**Institutions**: Chinese University of Hong Kong, Adobe Systems, Adobe Research, Johns Hopkins University, The Chinese University of Hong Kong

**Primary Area**: generative models

**Keywords**: Video Editing, Content Generation, Artificial Intelligence

**Abstract**:

Recent advances in foundation models highlight a clear trend toward unification and scaling, showing emergent capabilities across diverse domains. While image generation and editing have rapidly transformed with these foundation models, video editing still largely relies on constrained, task-specific models. To bridge this gap, we present EditVerse, a unified foundation model for both image and video editing and generation. EditVerse builds on top of the in-context learning capabilities of multimodal large language models, modeling the full editing and generation pipeline as a next-token prediction problem. By training on a large and diverse collection of data including image editing, video editing, image generation, and video generation, EditVerse enables a general-purpose, instruction-guided framework for editing and generating both images and videos. Our results demonstrate that EditVerse achieves state-of-the-art performance, surpassing existing open-source and commercial models, while exhibiting emergent editing and generation abilities across modalities.

**摘要翻译**:

基础模型的最新进展彰显了通向统一和扩展的明确趋势，展现了跨多种领域的涌现能力。虽然图像生成和编辑已随基础模型快速变革，但视频编辑在很大程度上仍依赖于受限的任务特定模型。为弥合这一差距，我们推出了EditVerse——一个统一的图像和视频编辑与生成基础模型。EditVerse建立在多模态大语言模型的上下文学习能力之上，将完整的编辑和生成流程建模为下一个token预测问题。通过在包含图像编辑、视频编辑、图像生成和视频生成的大规模多样化数据集上训练，EditVerse实现了一个通用的、指令引导的图像和视频编辑与生成框架。我们的结果表明，EditVerse取得了最先进的性能，超越了现有的开源和商业模型，同时展现出跨模态的涌现编辑和生成能力。

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

---

## 155. Partition Generative Modeling: Masked Modeling Without Masks

**分区生成建模：无需掩码的掩码建模**

**OpenReview**: [https://openreview.net/forum?id=vEh1ceS154](https://openreview.net/forum?id=vEh1ceS154)

**Authors**: Justin Deschenaux (EPFL - EPF Lausanne), Lan Tran (EPFL - EPF Lausanne), Caglar Gulcehre (Microsoft)

**Institutions**: EPFL - EPF Lausanne, Microsoft

**Primary Area**: generative models

**Keywords**: masked generative modeling, discrete diffusion, masked diffusion language modeling, diffusion language modeling

**TL;DR**: We show that it is possible to train masked generative models without using MASK tokens, resulting in efficiency gains at inference.

**TL;DR翻译**: 我们证明了可以在不使用MASK token的情况下训练掩码生成模型，从而在推理时获得效率提升。

**Abstract**:

Masked generative models (MGMs) can generate tokens in parallel and in any order, unlike autoregressive models (ARMs), which decode one token at a time, left-to-right. However, MGMs process the full-length sequence at every step, including masked tokens, resulting in high computational costs that limit their practical use, particularly for long sequences. To address this inefficiency, we introduce Partition Generative Models (PGMs), which eliminate the need for mask tokens entirely. Instead of predicting masked tokens in the full sequence, PGMs split the sequence into two non-overlapping partitions: a context partition, processed by the model, and a target partition, which is predicted. This partitioning avoids the computational overhead of processing mask tokens and makes the cost of each denoising step proportional to the number of tokens predicted in that step. On ImageNet 256x256, a PGM generates images $3.8\times$ faster than an equivalent MGM with the same number of steps, achieving an FID of 5.76. This is only slightly above the 5.52 FID of the MGM, despite the significant throughput improvement. With twice as many steps, the FID improves to 4.56 while remaining $3.9\times$ faster than MGMs. Finally, PGMs remain compatible with existing MGM samplers and distillation methods.

**摘要翻译**:

掩码生成模型（MGM）能够以并行且任意顺序生成token，不同于自回归模型（ARM）按从左到右的方式逐个token解码。然而，MGM在每一步都处理全长序列（包括被掩码的token），导致计算成本高昂，限制了其实际应用，尤其是在长序列场景中。为解决这一低效问题，我们引入了分区生成模型（PGM），完全消除了对掩码token的需求。PGM不再在完整序列中预测被掩码的token，而是将序列划分为两个不重叠的分区：由模型处理的上下文分区和待预测的目标分区。这种分区方式避免了处理掩码token的计算开销，使每个去噪步骤的成本与该步骤中预测的token数量成正比。在ImageNet 256x256上，PGM在相同步数下生成图像的速度比等效MGM快3.8倍，实现了5.76的FID。尽管吞吐量显著提升，这仅略高于MGM的5.52 FID。当步数增加一倍时，FID改善至4.56，同时仍比MGM快3.9倍。最后，PGM与现有的MGM采样器和蒸馏方法保持兼容。

---

## 156. How Do Transformers Learn to Associate Tokens: Gradient Leading Terms Bring Mechanistic Interpretability

**Transformer如何学习关联token：梯度主导项带来的机制可解释性**

**OpenReview**: [https://openreview.net/forum?id=A4Us8jxVGq](https://openreview.net/forum?id=A4Us8jxVGq)

**Authors**: Shawn Im (Department of Computer Science, University of Wisconsin - Madison), Changdae Oh (Department of Computer Science, University of Wisconsin - Madison), Zhen Fang (University of Technology Sydney), Sharon Li (University of Wisconsin - Madison)

**Institutions**: Department of Computer Science, University of Wisconsin - Madison, University of Technology Sydney, University of Wisconsin - Madison

**Primary Area**: interpretability and explainable AI

**Keywords**: Semantic associations, Interpretability, LLM

**Abstract**:

Semantic associations such as the link between "bird" and "flew" are foundational for language modeling as they enable models to go beyond memorization and instead generalize and generate coherent text in diverse contexts. Capturing such associations lies at the heart of modern language models, but how the Transformer architecture encodes them through gradient descent remains poorly understood. In this paper, we take a principled approach to studying this process. We first formalize the notion of semantic associations and then define a minimal Transformer architecture and data-generating process that retain essential features needed for theoretical analysis. We then introduce the concept of gradient leading terms: the dominant subset of gradient components that primarily drive the evolution of model weights toward learning the desired associations. While the full gradient is analytically intractable, we identify and characterize these leading terms, from which we derive closed-form expressions for the resulting model weights. This enables a precise mechanistic characterization of how the Transformer learns semantic associations via the interactions between its components. Empirically, we validate our theory across a range of experiments: quantitative analyses show that our theoretical weight characterizations closely match the learned weights, and qualitative analyses further guide us on how our theorem shines light on interpreting the learned association in transformers.

**摘要翻译**:

语义关联，如"bird"与"flew"之间的联系，是语言建模的基础，因为它使模型能够超越记忆，在多样化的上下文中泛化并生成连贯的文本。捕捉这种关联是现代语言模型的核心，但Transformer架构如何通过梯度下降编码这些关联仍然知之甚少。本文中，我们采用一种有原则的方法来研究这一过程。我们首先形式化了语义关联的概念，然后定义了一个保留理论分析所需基本特征的最小Transformer架构和数据生成过程。随后，我们引入了梯度主导项的概念：梯度分量中主要驱动模型权重向学习目标关联演化的主导子集。虽然完整梯度在分析上是不可处理的，但我们识别并刻画了这些主导项，并由此推导出模型权重的闭式表达式。这使得我们能够精确地从机制上刻画Transformer如何通过其组件之间的交互来学习语义关联。在实证方面，我们通过一系列实验验证了理论：定量分析表明我们的理论权重刻画与学习到的权重高度吻合，定性分析进一步指导我们理解该定理如何为解释Transformer中学习到的关联提供洞见。

---

## 157. On the Reasoning Abilities of Masked Diffusion Language Models

**论掩码扩散语言模型的推理能力**

**OpenReview**: [https://openreview.net/forum?id=BVnIsh4Nz1](https://openreview.net/forum?id=BVnIsh4Nz1)

**Authors**: Anej Svete (Department of Computer Science, ETHZ - ETH Zurich), Ashish Sabharwal (Allen Institute for AI)

**Institutions**: Department of Computer Science, ETHZ - ETH Zurich, Allen Institute for AI

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: diffusion language models, formal language theory, boolean circuits, expressivity, transformers, masked diffusion models, chain of thought, looped transformers

**TL;DR**: We prove that masked text diffusion models are equivalent to padded looped transformers, can solve all problems that chain-of-thought transformers can, and are more efficient on certain problem classes due to their parallel generation mechanism.

**TL;DR翻译**: 我们证明掩码文本扩散模型等价于填充循环Transformer，能够解决链式思维Transformer能解决的所有问题，并且由于其并行生成机制，在某些问题类别上更为高效。

**Abstract**:

Masked diffusion models (MDMs) for text offer a compelling alternative to traditional autoregressive language models. Parallel generation makes them efficient, but their computational capabilities and relationship to autoregressive models remain poorly understood. We establish theoretical foundations for MDMs by proving that they are equivalent to padded looped transformers, a known Turing-complete model of computation. Using this equivalence, we show that MDMs can express all problems solvable by chain-of-thought (CoT) transformers. Furthermore, we showcase classes of problems (including regular languages) for which MDMs are inherently more efficient than CoT transformers, where parallel generation allows for substantially faster reasoning.

**摘要翻译**:

面向文本的掩码扩散模型（MDM）为传统自回归语言模型提供了一种有吸引力的替代方案。并行生成使其高效，但其计算能力及与自回归模型的关系仍然知之甚少。我们为MDM建立了理论基础，证明它们等价于填充循环Transformer——一种已知的图灵完备计算模型。利用这种等价性，我们证明MDM能够表达链式思维（CoT）Transformer可解决的所有问题。此外，我们展示了一些问题类别（包括正则语言），在这些问题上MDM天然比CoT Transformer更高效，其中并行生成允许显著更快的推理。

---

## 158. FRABench and UFEval: Unified Fine-grained Evaluation with Task and Aspect Generalization

**FRABench与UFEval：具有任务和方面泛化能力的统一细粒度评估**

**OpenReview**: [https://openreview.net/forum?id=7WdY3Cojy9](https://openreview.net/forum?id=7WdY3Cojy9)

**Authors**: Shibo Hong (Fudan University), Jiahao Ying (Singapore Management University), Haiyuan Liang (Fudan University), Mengdi Zhang (NeoShell), Jun Kuang (Meituan-M17), Jiazheng Zhang (Fudan University), Yixin Cao (Fudan University)

**Institutions**: Fudan University, Singapore Management University, NeoShell, Meituan-M17

**Primary Area**: datasets and benchmarks

**Keywords**: Aspect-level Evaluation Dataset, Unified Fine-grained Evaluation

**Abstract**:

Evaluating open-ended outputs of Multimodal Large Language Models has become a bottleneck as model capabilities, task diversity, and modality rapidly expand. Existing ``MLLM-as-a-Judge'' evaluators, typically fine-tuned on task-specific rubrics, struggle to generalize across new tasks, diverse evaluation aspects, and unseen quality dimensions. This limitation motivates us to ask: can a single evaluator learn to assess any task along any fine-grained aspect? We introduce FRABench, a large-scale, aspect-level evaluation dataset that unifies assessment across 14 visual tasks along multiple fine-grained aspects (e.g., spatial accuracy, color fidelity, stylistic consistency). Building on this resource, we develop UFEval, a unified fine-grained evaluator that is task- and aspect-generalizable. UFEval takes a task instruction, a candidate response, and a target aspect as input, and produces a natural-language rationale together with a numeric score. Trained on FRABench, UFEval surpasses the state-of-the-art MLLM-as-a-Judge evaluator by 7.3 points and exceeds its best task-specific counterpart by 2.4 points, all within a single model. Experiments show that learning on specific aspects enables UFEval to generalize to unseen aspects, and joint learning to assess diverse visual tasks and aspects can lead to substantial mutual benefits.

**摘要翻译**:

随着模型能力、任务多样性和模态的快速扩展，评估多模态大语言模型的开放式输出已成为瓶颈。现有的"MLLM作为评判者"评估器通常在特定任务的评分标准上微调，难以泛化到新任务、多样化的评估方面和未见过的质量维度。这一局限促使我们提出一个问题：单个评估器能否学会沿任意细粒度方面评估任意任务？我们引入了FRABench——一个大规模的方面级评估数据集，统一了14个视觉任务在多个细粒度方面（如空间准确性、色彩保真度、风格一致性）上的评估。基于这一资源，我们开发了UFEval——一个具有任务和方面泛化能力的统一细粒度评估器。UFEval接收任务指令、候选回复和目标方面作为输入，生成自然语言推理依据和数值评分。在FRABench上训练后，UFEval超越了最先进的MLLM-as-a-Judge评估器7.3分，并超过其最佳任务特定对应模型2.4分，且全部在单一模型内实现。实验表明，在特定方面上的学习使UFEval能够泛化到未见过的方面，而联合学习评估多样化的视觉任务和方面能够带来显著的互利效果。

---

## 159. Quotient-Space Diffusion Model

**商空间扩散模型**

**OpenReview**: [https://openreview.net/forum?id=3JPAkwSVc4](https://openreview.net/forum?id=3JPAkwSVc4)

**Authors**: Yixian Xu (Peking University), Yusong Wang (MSR AI4Science China), Shengjie Luo (ByteDance Seed), Kaiyuan Gao (Huazhong University of Science and Technology), Tianyu He (Microsoft Research Asia), Chang Liu (Zhongguancun Academy), Di He (Peking University)

**Institutions**: Peking University, MSR AI4Science China, ByteDance Seed, Huazhong University of Science and Technology, Microsoft Research Asia, Zhongguancun Academy

**Primary Area**: generative models

**Keywords**: Diffusion Models, Generative Modeling, Geometric Deep Learning, Structure Generation

**Abstract**:

Diffusion-based generative models have reformed generative AI, and have enabled new capabilities in the science domain, for example, generating 3D structures of molecules.
Due to the intrinsic problem of symmetry, generating molecular structures using diffusion model remains a challenge. Symmetry means the probability distribution is invariant to certain group actions, and it is necessary to comply with this property for generating realistic molecular structures. Existing works rely on approximation approaches that either make the diffusion process equivariant, or attempt to learn a distribution over a fundamental domain that is theoretically impractical to determine. In this paper, we propose a principled approach to build diffusion processes on the quotient space where equivalent data points are collapsed. We show that the standard continuous-state diffusion framework naturally adapts to quotient spaces without additional constraints. We provide theoretical justification, specifically proving that the scores on the quotient space are well-defined, the forward process converges to the uniform distribution over the quotient space, and the time-reversal process provides an exact way to sample from the data distribution in the quotient space. The approach is validated on structure generation for small molecules and proteins, indicating that the principled quotient-space diffusion model provides a new  framework that outperforms previous symmetry treatments.

**摘要翻译**:

基于扩散的生成模型革新了生成式AI，并在科学领域实现了新的能力，例如生成分子的三维结构。由于对称性的内在问题，使用扩散模型生成分子结构仍然是一个挑战。对称性意味着概率分布在某些群作用下不变，生成逼真的分子结构必须遵循这一性质。现有工作依赖于近似方法，要么使扩散过程等变，要么试图学习一个在理论上难以确定的基本域上的分布。本文中，我们提出了一种在商空间上构建扩散过程的有原则方法，其中等价的数据点被合并。我们证明标准的连续状态扩散框架可以自然地适应商空间而无需额外约束。我们提供了理论论证，具体证明了商空间上的得分函数是良定义的，前向过程收敛到商空间上的均匀分布，且时间反转过程提供了从商空间上数据分布中精确采样的方式。该方法在小分子和蛋白质的结构生成上得到了验证，表明这一有原则的商空间扩散模型提供了一个优于先前对称性处理方法的新框架。

---

## 160. SWINGARENA: Adversarial Programming Arena for Long-context GitHub Issue Solving

**SWINGARENA：面向长上下文GitHub Issue求解的对抗式编程竞技场**

**OpenReview**: [https://openreview.net/forum?id=YuxgSGFaqb](https://openreview.net/forum?id=YuxgSGFaqb)

**Authors**: Wendong XU (University of Hong Kong), Jing Xiong (University of Hong Kong), Chenyang Zhao (UCLA Computer Science Department, University of California, Los Angeles), Qiujiang Chen (Southern University of Science and Technology), Haoran Wang (Tsinghua University), Hui Shen (University of Michigan - Ann Arbor), Zhongwei Wan (Ohio State University, Columbus), Jianbo Dai (Huawei Technologies Ltd.), Taiqiang Wu (The University of Hong Kong), He Xiao (University of Hong Kong), Chaofan Tao (The University of Hong Kong), Zhuoqing Mao (Google), Ying Sheng (xAI), Zhijiang Guo (The Hong Kong University of Science and Technology (Guangzhou)), Hongxia Yang (Hong Kong Polytechnic University), Bei Yu (Department of Computer Science and Engineering, The Chinese University of Hong Kong), Lingpeng Kong (Department of Computer Science, The University of Hong Kong), Quanquan Gu (ByteDance Seed), Ngai Wong (The University of Hong Kong)

**Institutions**: University of Hong Kong, UCLA Computer Science Department, University of California, Los Angeles, Southern University of Science and Technology, Tsinghua University, University of Michigan - Ann Arbor, Ohio State University, Columbus, Huawei Technologies Ltd., The University of Hong Kong, Google, xAI, The Hong Kong University of Science and Technology (Guangzhou), Hong Kong Polytechnic University, Department of Computer Science and Engineering, The Chinese University of Hong Kong, Department of Computer Science, The University of Hong Kong, ByteDance Seed

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Arena, Real-World GitHub Issues, Adversarial Programming, Retrieval-Augmented Generation, Continuous Integration, Code Benchmark

**Abstract**:

We present \textsc{SwingArena}, a adversarial evaluation framework for Large Language Models (LLMs) that closely mirrors real-world software development workflows. Unlike traditional static benchmarks that evaluate models in isolation, \textsc{SwingArena} introduces a dynamic evaluation paradigm where models serve as both code generators and adversarial reviewers. Each model attempts to solve GitHub issues involving long-context code understanding and bug-fixing, while simultaneously generating adversarial tests designed to expose weaknesses in competing models' solutions. All generated patches and tests are validated through continuous integration (CI), ensuring objective and reproducible evaluation. Our analysis reveals distinct model behaviors: Claude and GPT families tend to generate more adversarial tests targeting competitor weaknesses, while DeepSeek and Gemini prioritize correctness in CI validation. \textsc{SwingArena} presents a scalable and extensible methodology for evaluating LLMs in realistic, CI-driven software development settings.

**摘要翻译**:

我们提出了SwingArena——一个紧密模拟真实软件开发工作流的大语言模型（LLM）对抗式评估框架。与传统静态基准独立评估模型不同，SwingArena引入了一种动态评估范式，其中模型同时充当代码生成器和对抗式审查者。每个模型尝试解决涉及长上下文代码理解和缺陷修复的GitHub Issue，同时生成旨在暴露竞争模型解决方案弱点的对抗性测试。所有生成的补丁和测试均通过持续集成（CI）进行验证，确保客观且可复现的评估。我们的分析揭示了不同模型的行为差异：Claude和GPT系列倾向于生成更多针对竞争对手弱点的对抗性测试，而DeepSeek和Gemini则更注重CI验证中的正确性。SwingArena为在真实的、CI驱动的软件开发环境中评估LLM提供了一种可扩展且可延伸的方法论。

---

## 161. AnyUp: Universal Feature Upsampling

**AnyUp：通用特征上采样**

**OpenReview**: [https://openreview.net/forum?id=Y9UAgPehqo](https://openreview.net/forum?id=Y9UAgPehqo)

**Authors**: Thomas Wimmer (Max-Planck Institute), Prune Truong (Google), Marie-Julie Rakotosaona (Google), Michael Oechsle (Google), Federico Tombari (Google), Bernt Schiele (Max Planck Institute for Informatics, Saarland Informatics Campus), Jan Eric Lenssen (Saarland Informatics Campus, Max-Planck Institute)

**Institutions**: Max-Planck Institute, Google, Max Planck Institute for Informatics, Saarland Informatics Campus, Saarland Informatics Campus, Max-Planck Institute

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: feature upsampling, representation learning

**TL;DR**: A universal feature upsampling model that can be used to upsample any feature from any to any resolution and generalizes to features unseen during training.

**TL;DR翻译**: 一种通用特征上采样模型，可将任意特征从任意分辨率上采样到任意分辨率，并能泛化到训练中未见过的特征。

**Abstract**:

We introduce AnyUp, a method for feature upsampling that can be applied to any vision feature at any resolution, without encoder-specific training. Existing learning-based upsamplers for features like those from DINOv2, SAM, or CLIP require training a separate decoder for each encoder and resolution. In contrast, AnyUp is a universal model that handles features from various encoders and resolutions using a single set of weights. This is enabled by treating upsampling as a neural operator mapping between function spaces, conditioned on the target resolution. AnyUp sets a new state of the art for upsampled features, generalizes to different feature types, and  preserves feature semantics while being efficient and easy to apply to a wide range of downstream tasks.

**摘要翻译**:

我们引入了AnyUp——一种特征上采样方法，可应用于任意视觉特征和任意分辨率，无需针对特定编码器进行训练。现有的基于学习的特征上采样器（如针对DINOv2、SAM或CLIP的特征）需要为每个编码器和分辨率单独训练解码器。相比之下，AnyUp是一个通用模型，使用单组权重即可处理来自不同编码器和不同分辨率的特征。这得益于将上采样视为函数空间之间的神经算子映射，并以目标分辨率为条件。AnyUp在上采样特征方面刷新了最先进的水平，能泛化到不同的特征类型，在保持特征语义的同时兼具高效性，且易于应用到广泛的下游任务中。

---

## 162. High-dimensional Analysis of Synthetic Data Selection

**合成数据选择的高维分析**

**OpenReview**: [https://openreview.net/forum?id=Y54P2BBPPh](https://openreview.net/forum?id=Y54P2BBPPh)

**Authors**: Parham Rezaei (Institute of Science and Technology Austria), Filip Kovačević (Institute of Science and Technology Austria), Francesco Locatello (Institute of Science and Technology), Marco Mondelli (Institute of Science and Technology Austria)

**Institutions**: Institute of Science and Technology Austria, Institute of Science and Technology

**Primary Area**: transfer learning, meta learning, and lifelong learning

**Keywords**: high dimensional regression, empirical risk minimization, synthetic data, generative models

**TL;DR**: We give a precise analysis for the problem of synthetic data selection through the lens of high-dimensional regression, and we translate the theoretical insights into a method that performs well in practice.

**TL;DR翻译**: 我们通过高维回归的视角对合成数据选择问题进行了精确分析，并将理论洞见转化为在实践中表现优异的方法。

**Abstract**:

Despite the progress in the development of generative models, their usefulness in creating synthetic data that improve prediction performance of classifiers has been put into question. Besides heuristic tricks that help increase the quality of synthetic data, one common strategy to improve performance is to select a subset of the generated synthetic samples. In this work, we aim to understand the impact of synthetic data selection on the performance of downstream classifiers. To this end, we provide a precise characterization of the test error of ridge regression trained on a mix of real and synthetic data sampled from a Gaussian mixture model. We sharpen the analysis of optimal selection by proving that it can be efficiently solved via a semidefinite program. Importantly, we translate the theoretical insights into a practical algorithm, termed Fourier Score Filtering (FSF). Our empirical evaluation shows that FSF (which just relies on a single hyperparameter scoring from the target distribution) performs well against several recent approaches for synthetic data selection, across various training paradigms, datasets and generative models used for augmentation.

**摘要翻译**:

尽管生成模型的发展取得了进展，但其在创建能提升分类器预测性能的合成数据方面的实用性受到了质疑。除了有助于提高合成数据质量的启发式技巧外，一种常见的性能提升策略是选择生成合成样本的子集。在本工作中，我们旨在理解合成数据选择对下游分类器性能的影响。为此，我们精确刻画了在混合使用真实数据和从高斯混合模型采样的合成数据上训练的岭回归的测试误差。我们通过证明最优选择可以通过半正定规划高效求解来细化最优选择的分析。重要的是，我们将理论洞见转化为一种实用算法——傅里叶得分过滤（FSF）。我们的实证评估表明，FSF（仅依赖一个来自目标分布的超参数评分）在多种训练范式、数据集和用于增强的生成模型上，相比近期的合成数据选择方法均表现良好。

---

## 163. Task-free Adaptive Meta Black-box Optimization

**无任务自适应元黑箱优化**

**OpenReview**: [https://openreview.net/forum?id=AufVSUgMUo](https://openreview.net/forum?id=AufVSUgMUo)

**Authors**: Chao Wang (Xidian University), Licheng Jiao (Xidian University), Lingling Li (Xidian University), Jiaxuan Zhao (Tianjin Research Institute for Water Transport Engineering, M.O.T.), Guanchun Wang (Xi'an University of Electronic Science and Technology), Fang Liu (Xidian University), Shuyuan Yang (Xidian University)

**Institutions**: Xidian University, Tianjin Research Institute for Water Transport Engineering, M.O.T., Xi'an University of Electronic Science and Technology

**Primary Area**: optimization

**Keywords**: Meta Black-box Optimization, Evolutionary Algorithms

**Abstract**:

Handcrafted optimizers become prohibitively inefficient for complex black-box optimization (BBO) tasks. MetaBBO addresses this challenge by meta-learning to automatically configure optimizers for low-level BBO tasks. However, existing MetaBBO methods rely on handcrafted training tasks, limiting their generalization and practicality since the relationship between training and test tasks is typically unknown. To overcome this bottleneck, we propose a Task-free Adaptive Meta Black-box Optimization (TAMBO) framework, which eliminates the need for pre-specified training tasks. TAMBO integrates three key components: (1) a task generation module that employs learnable function generators to synthesize optimization tasks, enabling diverse and curriculum-based task generation; (2) a task-adaptive evolution module using a neural network-based evolutionary operator, conditioned on task-specific information for effective optimization; and (3) a co-adaptation mechanism that alternately updates the task generator and evolution module, simultaneously improving the quality and difficulty of generated tasks and the optimizer's search capabilities. We provide a theoretical analysis of the co-adaptation process, establishing convergence guarantees under mild assumptions. Comprehensive experiments across diverse benchmarks, including synthetic functions, protein docking, and neural architecture search, demonstrate that TAMBO consistently outperforms state-of-the-art methods. Importantly, TAMBO achieves this superior performance without relying on any handcrafted training tasks. Visualization studies reveal that parameterized evolutionary operators exhibit statistically significant search patterns, including natural selection and genetic recombination.

**摘要翻译**:

手工设计的优化器在复杂的黑箱优化（BBO）任务中变得极度低效。MetaBBO通过元学习自动配置底层BBO任务的优化器来应对这一挑战。然而，现有的MetaBBO方法依赖于手工设计的训练任务，由于训练任务和测试任务之间的关系通常未知，这限制了其泛化能力和实用性。为克服这一瓶颈，我们提出了无任务自适应元黑箱优化（TAMBO）框架，消除了对预定义训练任务的需求。TAMBO整合了三个关键组件：（1）任务生成模块，采用可学习的函数生成器合成优化任务，支持多样化和课程式的任务生成；（2）任务自适应演化模块，使用基于神经网络的演化算子，以任务特定信息为条件实现有效优化；（3）协同适应机制，交替更新任务生成器和演化模块，同时提升生成任务的质量和难度以及优化器的搜索能力。我们对协同适应过程进行了理论分析，在温和假设条件下建立了收敛保证。在包括合成函数、蛋白质对接和神经架构搜索在内的多样化基准上的全面实验表明，TAMBO持续优于最先进的方法。重要的是，TAMBO在不依赖任何手工设计训练任务的情况下取得了这一优越性能。可视化研究揭示了参数化演化算子展现出统计显著的搜索模式，包括自然选择和基因重组。

---

## 164. Token-Importance Guided Direct Preference Optimization

**token重要性引导的直接偏好优化**

**OpenReview**: [https://openreview.net/forum?id=cMEnMVvMw9](https://openreview.net/forum?id=cMEnMVvMw9)

**Authors**: Ning Yang (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Hai Lin, Yibo Liu (The Chinese University of Hong Kong, Shenzhen), Baoliang Tian (ByteDance Inc.), Guoqing Liu (Microsoft Research ), Haijun Zhang (University of Science and Technology Beijing)

**Institutions**: Institute of automation, Chinese academy of science, Chinese Academy of Sciences, The Chinese University of Hong Kong, Shenzhen, ByteDance Inc., Microsoft Research , University of Science and Technology Beijing

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLMs, RLHF, DPO, Human Preference Alignment, Token-lmportance, Triplet Loss

**TL;DR**: We proposes Token-Importance Guided Direct Preference Optimization (TI-DPO) to better align LLMs with human preferences by using a hybrid weighting mechanism to identify key tokens and a triplet loss to guide the optimization process.

**TL;DR翻译**: 我们提出了token重要性引导的直接偏好优化（TI-DPO），通过混合加权机制识别关键token并使用三元组损失引导优化过程，以更好地将LLM与人类偏好对齐。

**Abstract**:

Aligning Large Language Models (LLMs) with human preferences is crucial for safe and effective AI interactions. While popular methods like Direct Preference Optimization (DPO) have simplified alignment by replacing complex reward models, they face challenges with noisy token-level signals and limited exploration of fine-grained preference distinctions. In this paper, we propose Token-Importance Guided Direct Preference Optimization (TI-DPO), which enhances alignment through two key innovations: (1) a hybrid weighting mechanism that combines model-internal signals with contrastive analysis of preference pairs to identify tokens that are both semantically significant and preference-discriminative, and (2) a triplet-based optimization approach that jointly considers both preferred and dispreferred completions alongside a reference point, better capturing nuanced preference relationships. Our experimental results show that TI-DPO achieves higher accuracy and stronger generative diversity, providing more stable and computationally efficient solutions compared with DPO and other RLHF methods.

**摘要翻译**:

将大语言模型（LLM）与人类偏好对齐对于安全有效的AI交互至关重要。虽然直接偏好优化（DPO）等流行方法通过替代复杂的奖励模型简化了对齐过程，但它们在处理噪声token级信号和探索细粒度偏好区分方面面临挑战。本文中，我们提出了token重要性引导的直接偏好优化（TI-DPO），通过两项关键创新增强对齐效果：（1）混合加权机制，结合模型内部信号和偏好对的对比分析来识别既具有语义重要性又具有偏好区分能力的token；（2）基于三元组的优化方法，联合考虑偏好和非偏好的补全以及参考点，更好地捕捉细微的偏好关系。实验结果表明，TI-DPO实现了更高的准确率和更强的生成多样性，相比DPO和其他RLHF方法提供了更稳定且计算效率更高的解决方案。

---

## 165. DTO-KD: Dynamic Trade-off Optimization for Effective Knowledge Distillation

**DTO-KD：面向有效知识蒸馏的动态权衡优化**

**OpenReview**: [https://openreview.net/forum?id=QMItTyQW92](https://openreview.net/forum?id=QMItTyQW92)

**Authors**: Zeeshan Hayder (Australian National University), Ali Cheraghian (CSIRO), Lars Petersson (CSIRO), Mehrtash Harandi (Monash University), Richard Hartley (Australian National University)

**Institutions**: Australian National University, CSIRO, Monash University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Knowledge Distillation

**TL;DR**: DTO-KD

**TL;DR翻译**: DTO-KD

**Abstract**:

Knowledge Distillation (KD) is a widely adopted framework for compressing large models into compact student models by transferring knowledge from a high-capacity teacher. Despite its success, KD presents a significant optimization challenge: balancing the student loss (which aligns the student with ground-truth labels) and the distillation loss (which aligns the student with the teacher's output distribution). This trade-off is typically controlled by a static hyperparameter, requiring extensive tuning and offering no guarantees of optimal balance throughout training. We propose DTO-KD, a principled approach that reframes KD as a multi-objective optimization (MOO) problem. Rather than relying on fixed weighting, DTO-KD dynamically adjusts the balance between the two objectives using a common descent direction algorithm, ensuring simultaneous improvement on both objectives at each training step. Our formulation requires no additional hyperparameters and applies to virtually any KD variant without altering its core loss functions. Experiments across diverse settings, including ImageNet-1K for image classification, MS-COCO for object detection, ADE20K for semantic segmentation, and CommonVoice for speech recognition, consistently demonstrate that DTO-KD matches or surpasses conventional fixed-weight KD, while requiring no hyperparameter tuning. We additionally provide theoretical analysis showing improved convergence behavior. Furthermore, student models trained with DTO-KD exceed the performance of their non-distilled counterparts, demonstrating the efficacy of our multi-objective formulation for KD.

**摘要翻译**:

知识蒸馏（KD）是一种广泛采用的框架，通过从高容量教师模型传递知识将大模型压缩为紧凑的学生模型。尽管取得了成功，KD面临着一个重大的优化挑战：平衡学生损失（使学生与真实标签对齐）和蒸馏损失（使学生与教师的输出分布对齐）。这种权衡通常由一个静态超参数控制，需要大量调优且无法保证在整个训练过程中达到最优平衡。我们提出了DTO-KD，一种将KD重新构建为多目标优化（MOO）问题的有原则方法。DTO-KD不依赖固定加权，而是使用公共下降方向算法动态调整两个目标之间的平衡，确保在每个训练步骤中两个目标同时改进。我们的公式化方法不需要额外的超参数，且适用于几乎任何KD变体而无需改变其核心损失函数。在包括ImageNet-1K图像分类、MS-COCO目标检测、ADE20K语义分割和CommonVoice语音识别等多样化场景的实验一致表明，DTO-KD在无需超参数调优的情况下达到或超越了传统固定权重KD的性能。我们还提供了理论分析，展示了改进的收敛行为。此外，使用DTO-KD训练的学生模型超越了未蒸馏版本的性能，证明了我们多目标公式化方法在KD中的有效性。

---

## 166. Distributional Equivalence in Linear Non-Gaussian Latent-Variable Cyclic Causal Models: Characterization and Learning

**线性非高斯潜变量循环因果模型中的分布等价性：表征与学习**

**OpenReview**: [https://openreview.net/forum?id=b8TlYh6PN6](https://openreview.net/forum?id=b8TlYh6PN6)

**Authors**: Haoyue Dai (Carnegie Mellon University), Immanuel Albrecht (FernUniversität in Hagen), Peter Spirtes (Carnegie Mellon University), Kun Zhang (Carnegie Mellon University)

**Institutions**: Carnegie Mellon University, FernUniversität in Hagen

**Primary Area**: causal reasoning

**Keywords**: causal discovery, latent variables, equivalence, rank constraints, linear non-Gaussian models, cycles

**Abstract**:

Causal discovery with latent variables is a fundamental task. Yet most existing methods rely on strong structural assumptions, such as enforcing specific indicator patterns for latents or restricting the number of latent common causes per observed pair. These constraints limit practical applicability. In this work, we study linear non-Gaussian latent-variable models with potential cycles, characterizing distributional equivalence among the linear cyclic latent-variable models that may entail the same set of data distributions. Our equivalence characterization is the first among latent-variable models that does not require imposing structural constraints on the graphs. Building on the algebraic characterization by means of polynomial rank constraints, we develop a discovery algorithm that estimates the Markov equivalence class up to a novel notion of weak equivalence. To our knowledge, this is the first causal discovery algorithm for latent variables in any parametric setting without structural assumptions, and hence the first structural-assumption-free discovery method. Code and an interactive demo are available at https://equiv.cc.

**摘要翻译**:

带有潜变量的因果发现是一项基础任务。然而，现有大多数方法依赖于强结构假设，如对潜变量强制特定的指示模式或限制每对观测变量的潜在共同原因数量。这些约束限制了实际适用性。在本工作中，我们研究了具有潜在循环的线性非高斯潜变量模型，刻画了可能蕴含相同数据分布集合的线性循环潜变量模型之间的分布等价性。我们的等价性刻画是潜变量模型中首个不需要对图施加结构约束的刻画。基于多项式秩约束的代数刻画，我们开发了一种发现算法，该算法在一种新颖的弱等价概念下估计马尔可夫等价类。据我们所知，这是在任何参数化设置下针对潜变量的首个无需结构假设的因果发现算法，也是首个无结构假设的发现方法。代码和交互式演示可在 https://equiv.cc 获取。

---

## 167. Reliable Weak-to-Strong Monitoring of LLM Agents

**LLM智能体的可靠弱到强监控**

**OpenReview**: [https://openreview.net/forum?id=WV7xIboTDK](https://openreview.net/forum?id=WV7xIboTDK)

**Authors**: Neil Kale (School of Computer Science, Carnegie Mellon University), Chen Bo Calvin Zhang (Scale AI), Kevin Zhu (Massachusetts Institute of Technology), Ankit Aich, Paula Rodriguez (Scale AI), Christina Q Knight (Scale AI), Zifan Wang (Scale AI)

**Institutions**: School of Computer Science, Carnegie Mellon University, Scale AI, Massachusetts Institute of Technology

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Agent Safety, Chain-of-Thought Monitoring, Large Language Model

**TL;DR**: This paper introduces a monitor red teaming workflow to stress test systems for detecting covert misbehavior in LLM agents, finding that a well-designed monitor scaffold enables weaker models to oversee strong aware attackers.

**TL;DR翻译**: 本文引入了一种监控红队工作流，用于压力测试检测LLM智能体隐蔽不当行为的系统，发现精心设计的监控框架使较弱模型能够监督具有意识的强攻击者。

**Abstract**:

We stress test monitoring systems for detecting covert misbehavior in LLM agents (e.g., secretly exfiltrating data). We propose a monitor red teaming (MRT) workflow that varies agent and monitor awareness to systematically identify vulnerabilities. MRT can be combined with a novel monitor scaffold that decomposes agent chains-of-thought, checking each step against a generated expectation of behavior to flag anomalies. Using this scaffold, even a smaller 4o-mini monitor can reliably oversee a strong, intentionally scheming o1 agent, achieving F1 > 0.90 with false positive rates below 5%. Our work positions MRT as a standard workflow for stress-testing oversight, revealing robustness gaps in both LLM- and human-based monitoring. We release code, data, and logs to support further research.

**摘要翻译**:

我们对用于检测LLM智能体隐蔽不当行为（如秘密窃取数据）的监控系统进行了压力测试。我们提出了一种监控红队（MRT）工作流，通过变化智能体和监控器的意识水平来系统性地识别漏洞。MRT可与一种新颖的监控框架相结合，该框架分解智能体的思维链，将每一步与生成的行为预期进行对比以标记异常。使用此框架，即使是较小的4o-mini监控器也能可靠地监督一个强大的、故意进行欺骗的o1智能体，实现F1 > 0.90且假阳性率低于5%。我们的工作将MRT定位为压力测试监督系统的标准工作流，揭示了基于LLM和基于人类的监控中的鲁棒性差距。我们发布了代码、数据和日志以支持进一步研究。

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

---

## 169. Multi-Domain Riemannian Graph Gluing for Building Graph Foundation Models

**面向图基础模型构建的多域黎曼图粘合方法**

**OpenReview**: [https://openreview.net/forum?id=G3uNHQpP7J](https://openreview.net/forum?id=G3uNHQpP7J)

**Authors**: Li Sun (Beijing University of Post and Telecommunications), Zhenhao Huang (North China Electric Power University), Silei Chen (NCEPU), Lanxu Yang (NCEPU), Junda Ye (Beijing University of Posts and Telecommunications), Sen Su (Beijing University of Posts and Telecommunications), Philip S. Yu (University of Illinois Chicago)

**Institutions**: Beijing University of Post and Telecommunications, North China Electric Power University, NCEPU, Beijing University of Posts and Telecommunications, University of Illinois Chicago

**Primary Area**: learning on graphs and other geometries & topologies

**Keywords**: Multi-domain graph pre-training, graph neural network, graph foundation model, Riemannian geometry

**TL;DR**: From differential geometry perspective, we present a novel framework that merges multi-domain graphs into a unified, smooth manifold with geometric consistency, enabling quantifiable transferability and geometric scaling behavior.

**TL;DR翻译**: 从微分几何的视角出发，我们提出了一种新颖框架，将多域图合并为具有几何一致性的统一光滑流形，从而实现可量化的迁移性和几何缩放行为。

**Abstract**:

Multi-domain graph pre-training integrates knowledge from diverse domains to enhance performance in the target domains, which is crucial for building graph foundation models. Despite initial success, existing solutions often fall short of answering a fundamental question: how is knowledge integrated or transferred across domains? This theoretical limitation motivates us to rethink the consistency and transferability between the pre-trained model and target domains. In this paper, we propose a fresh differential geometry perspective, whose core idea is to merge any graph dataset into a unified, smooth Riemannian manifold, enabling a systematic understanding of knowledge integration and transfer. To achieve this, our key contribution is the theoretical establishment of neural manifold gluing, which first characterizes local geometry using an adaptive orthogonal frame and then "glues" the local pieces together into a coherent whole. Building on this theory, we present the GraphGlue framework, which supports batched pre-training with EMA prototyping and provides a transferability measure based on geometric consistence. Extensive experiments demonstrate its superior performance across diverse graph domains. Moreover, we empirically validated GraphGlue's geometric scaling law, showing that larger quantities of datasets improve model transferability by producing a smoother manifold.

**摘要翻译**:

多域图预训练通过整合来自不同领域的知识来提升目标领域的性能，这对于构建图基础模型至关重要。尽管已取得初步成功，现有方法往往无法回答一个根本性问题：知识是如何在不同领域之间整合或迁移的？这一理论局限促使我们重新思考预训练模型与目标领域之间的一致性和可迁移性。本文提出了一种全新的微分几何视角，其核心思想是将任意图数据集合并为统一的光滑黎曼流形，从而实现对知识整合与迁移的系统性理解。为此，我们的关键贡献在于从理论上建立了神经流形粘合方法，该方法首先使用自适应正交标架刻画局部几何结构，然后将各局部片段"粘合"为一个连贯的整体。基于该理论，我们提出了 GraphGlue 框架，该框架支持结合 EMA 原型的批量预训练，并提供基于几何一致性的可迁移性度量。大量实验表明，该方法在多种图领域中表现出优越的性能。此外，我们通过实验验证了 GraphGlue 的几何缩放定律，即更大规模的数据集能够通过生成更光滑的流形来提升模型的可迁移性。

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

---

## 171. FlashVID: Efficient Video Large Language Models via Training-free Tree-based Spatiotemporal Token Merging

**FlashVID：基于免训练树状时空 Token 合并的高效视频大语言模型**

**OpenReview**: [https://openreview.net/forum?id=H6rDX4w6Al](https://openreview.net/forum?id=H6rDX4w6Al)

**Authors**: Ziyang Fan (Harbin Institute of Technology(Shenzhen)), Keyu Chen (Harbin Institute of Technology (Shenzhen)), Ruilong Xing (Harbin Institute of Technology), Yulin Li (Harbin Institute of Technology (Shenzhen)), Li Jiang (The Chinese University of Hong Kong, Shenzhen), Zhuotao Tian (Harbin Institute of Technology (Shenzhen))

**Institutions**: Harbin Institute of Technology(Shenzhen), Harbin Institute of Technology (Shenzhen), Harbin Institute of Technology, The Chinese University of Hong Kong, Shenzhen

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Efficient Large Multimodal Models, Video Large Language Models, Visual Token Compression

**TL;DR**: We introduce FlashVID, a training-free and plug-and-play inference acceleration framework for Video LLMs, enabling a satisfactory speedup with negligible performance degradation.

**TL;DR翻译**: 我们提出了 FlashVID，一种面向视频大语言模型的免训练即插即用推理加速框架，能够在性能损失可忽略的情况下实现令人满意的加速效果。

**Abstract**:

Although Video Large Language Models (VLLMs) have shown remarkable capabilities in video understanding, they are required to process high volumes of visual tokens, causing significant computational inefficiency. Existing VLLMs acceleration frameworks usually compress spatial and temporal redundancy independently, which overlooks the spatiotemporal relationships, thereby leading to suboptimal spatiotemporal compression. The highly correlated visual features are likely to change in spatial position, scale, orientation, and other attributes over time due to the dynamic nature of video. Building on this insight, we introduce FlashVID, a training-free inference acceleration framework for VLLMs. Specifically, FlashVID utilizes Attention and Diversity-based Token Selection (ADTS) to select the most representative tokens for basic video representation, then applies Tree-based Spatiotemporal Token Merging (TSTM) for fine-grained spatiotemporal redundancy elimination. Extensive experiments conducted on three representative VLLMs across five video understanding benchmarks demonstrate the effectiveness and generalization of our method. Notably, by retaining only $\textbf{10}$% of visual tokens, FlashVID preserves $\textbf{99.1}$% of the performance of LLaVA-OneVision. Consequently, FlashVID can serve as a training-free and plug-and-play module for extending long video frames, which enables a $\textbf{10$\times$}$ increase in video frame input to Qwen2.5-VL, resulting in a relative improvement of $\textbf{8.6}$% within the same computational budget. Code is available at https://github.com/Fanziyang-v/FlashVID.

**摘要翻译**:

尽管视频大语言模型 (VLLM) 在视频理解方面展现了卓越的能力，但其需要处理大量视觉 token，导致显著的计算效率低下。现有的 VLLM 加速框架通常分别压缩空间和时间冗余，忽视了时空关系，从而导致时空压缩效果欠佳。由于视频的动态特性，高度相关的视觉特征在空间位置、尺度、朝向等属性上可能随时间发生变化。基于这一洞察，我们提出了 FlashVID，一种面向 VLLM 的免训练推理加速框架。具体而言，FlashVID 利用基于注意力和多样性的 Token 选择 (ADTS) 来选取最具代表性的 token 作为基本视频表示，然后应用基于树结构的时空 Token 合并 (TSTM) 进行细粒度的时空冗余消除。在三个代表性 VLLM 和五个视频理解基准上的大量实验证明了我们方法的有效性和泛化能力。值得注意的是，仅保留 **10**% 的视觉 token，FlashVID 就能保持 LLaVA-OneVision **99.1**% 的性能。因此，FlashVID 可以作为免训练的即插即用模块来扩展长视频帧数，使 Qwen2.5-VL 的视频帧输入增加 **10 倍**，在相同计算预算下实现 **8.6**% 的相对性能提升。代码已在 https://github.com/Fanziyang-v/FlashVID 开源。

---

## 172. WSM: Decay-Free Learning Rate Schedule via Checkpoint Merging for LLM Pre-training

**WSM：通过检查点合并实现无衰减学习率调度的大语言模型预训练方法**

**OpenReview**: [https://openreview.net/forum?id=HhThhjKyfw](https://openreview.net/forum?id=HhThhjKyfw)

**Authors**: Changxin Tian (Ant Group), jiapeng wang (Renmin University of China), Qian Zhao (Ant Group), Kunlong Chen (Alibaba Group), Jia Liu (Ant Group), Ziqi Liu (Ant Group), Jiaxin Mao (Renmin University of China), Xin Zhao (Renmin University of China), Zhiqiang Zhang (Ant Group), JUN ZHOU (Ant Group)

**Institutions**: Ant Group, Renmin University of China, Alibaba Group

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: llm pre-training, learning rate schedule, checkpoint merging, decay-free approach

**Abstract**:

Recent advances in learning rate (LR) scheduling have demonstrated the effectiveness of decay-free approaches that eliminate the traditional decay phase while maintaining competitive performance. Model merging techniques have emerged as particularly promising solutions in this domain. We present Warmup-Stable and Merge (WSM), a general framework that establishes a formal connection between learning rate decay and model merging. WSM provides a unified theoretical foundation for emulating various decay strategies—including cosine decay, linear decay and inverse square root decay—as principled model averaging schemes, while remaining fully compatible with diverse optimization methods. Through extensive experiments, we identify merge duration—the training window for checkpoint aggregation—as the most critical factor influencing model performance, surpassing the importance of both checkpoint interval and merge quantity. With the high-quality annealing data, our framework consistently outperforms the widely-adopted Warmup-Stable-Decay (WSD) approach across multiple benchmarks, achieving significant improvements of +3.5% on MATH, +2.9% on HumanEval, and +5.5% on MMLU-Pro. The performance advantages extend to supervised fine-tuning scenarios, highlighting WSM's potential for long-term model refinement.

**摘要翻译**:

学习率 (LR) 调度的最新进展表明，无衰减方法在消除传统衰减阶段的同时能够保持具有竞争力的性能。模型合并技术已成为该领域中尤为有前景的解决方案。我们提出了预热-稳定-合并 (WSM) 这一通用框架，建立了学习率衰减与模型合并之间的形式化联系。WSM 为模拟各种衰减策略——包括余弦衰减、线性衰减和逆平方根衰减——提供了统一的理论基础，将其转化为有原则的模型平均方案，同时保持与多种优化方法的完全兼容性。通过大量实验，我们发现合并持续时间——即检查点聚合的训练窗口——是影响模型性能的最关键因素，其重要性超过检查点间隔和合并数量。在使用高质量退火数据时，我们的框架在多个基准上持续优于广泛采用的预热-稳定-衰减 (WSD) 方法，分别在 MATH 上提升 +3.5%、在 HumanEval 上提升 +2.9%、在 MMLU-Pro 上提升 +5.5%。该性能优势同样延伸至监督微调场景，凸显了 WSM 在长期模型优化方面的潜力。

---

## 173. MrRoPE: Mixed-radix Rotary Position Embedding

**MrRoPE：混合基数旋转位置编码**

**OpenReview**: [https://openreview.net/forum?id=1J63FJYJKg](https://openreview.net/forum?id=1J63FJYJKg)

**Authors**: Qingyuan Tian (Shanghai Jiaotong University), Wenhong Zhu (Shanghai Innovation Institute), Xiaoran Liu (Shanghai Innovation Institute), Xiaofeng Wang (Shanghai Jiaotong University), Rui Wang (Shanghai Jiao Tong University)

**Institutions**: Shanghai Jiaotong University, Shanghai Innovation Institute, Shanghai Jiao Tong University

**Primary Area**: generative models

**Keywords**: transformers, nlp, llms, context window extension, attention, rotary embedding

**TL;DR**: We present a unified theory MrRoPE linking major RoPE-extension methods to radix conversion. Based on this, we propose MrRoPE-Pro, a training-free context window extension method..

**TL;DR翻译**: 我们提出了统一理论 MrRoPE，将主流 RoPE 扩展方法与基数转换联系起来。在此基础上，我们提出了 MrRoPE-Pro，一种免训练的上下文窗口扩展方法。

**Abstract**:

Rotary Position Embedding (RoPE)-extension refers to modifying or generalizing the Rotary Position Embedding scheme to handle longer sequences than those encountered during pre-training. However, current extension strategies are highly diverse and lack a unified theoretical foundation. In this paper, we propose $\textbf{\textit{MrRoPE (Mixed-radix RoPE)}}$, a generalized encoding formulation based on a radix system conversion perspective, which elegantly unifies various RoPE-extension approaches as distinct radix conversion strategies. Based on this theory, we introduce two training-free extensions, $\textbf{\textit{MrRoPE-Uni}}$ and $\textbf{\textit{MrRoPE-Pro}}$, which leverage uniform and progressive radix conversion strategies, respectively, to achieve "train short, test long" generalization. Without fine-tuning, MrRoPE-Pro sustains over 85% recall in the 128K-context Needle-in-a-Haystack test and achieves more than double YaRN's accuracy on Infinite-Bench retrieval and dialogue subsets. Theoretical analysis confirms that MrRoPE-Pro effectively raises the upper bound of RoPE's attainable encoding length, which further validates the reliability and utility of our theory and methodology.

**摘要翻译**:

旋转位置编码 (RoPE) 扩展是指修改或推广旋转位置编码方案，以处理比预训练阶段更长的序列。然而，当前的扩展策略高度多样且缺乏统一的理论基础。本文提出了 MrRoPE（混合基数 RoPE），一种基于基数制转换视角的广义编码公式，优雅地将各种 RoPE 扩展方法统一为不同的基数转换策略。基于该理论，我们引入了两种免训练的扩展方法 MrRoPE-Uni 和 MrRoPE-Pro，分别利用均匀和渐进式基数转换策略来实现"短训练、长测试"的泛化能力。无需微调，MrRoPE-Pro 在 128K 上下文的"大海捞针"测试中保持了超过 85% 的召回率，并在 Infinite-Bench 的检索和对话子集上取得了超过 YaRN 两倍的准确率。理论分析证实，MrRoPE-Pro 有效提高了 RoPE 可达编码长度的上界，进一步验证了我们的理论和方法的可靠性与实用性。

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

**Abstract**:

Reasoning models have made rapid progress on many benchmarks involving math, code, and science. Yet, there are still many open questions about the best training recipes for reasoning since state-of-the-art models often rely on proprietary datasets with little to no public information available. To address this, the goal of the OpenThoughts project is to create open-source datasets for training reasoning models. Our OpenThoughts2-1M dataset led to OpenThinker2-32B, the first model trained on public reasoning data to match DeepSeek-R1-Distill-32B on standard reasoning benchmarks such as AIME and LiveCodeBench. We then improve our dataset further by systematically investigating each step of our data generation pipeline with 1,000+ controlled experiments, which led to OpenThoughts3. Scaling the pipeline to 1.2M examples and using QwQ-32B as teacher yields our OpenThinker3-7B model, which achieves state-of-the-art results: 53% on AIME 2025, 51% on LiveCodeBench 06/24-01/25, and 54% on GPQA Diamond – improvements of 15.3, 17.2, and 20.5 percentage points compared to the DeepSeek-R1-Distill-Qwen-7B. All of our datasets and models are available on ANONYMIZED.

**摘要翻译**:

推理模型在涉及数学、代码和科学的众多基准上取得了快速进展。然而，关于推理模型最佳训练配方仍存在许多未解问题，因为最先进的模型通常依赖专有数据集，几乎没有可用的公开信息。为解决这一问题，OpenThoughts 项目的目标是创建用于训练推理模型的开源数据集。我们的 OpenThoughts2-1M 数据集训练出了 OpenThinker2-32B，这是首个在公开推理数据上训练、并在 AIME 和 LiveCodeBench 等标准推理基准上与 DeepSeek-R1-Distill-32B 匹配的模型。随后，我们通过对数据生成流水线的每个步骤进行超过 1000 次对照实验来系统地改进数据集，由此产生了 OpenThoughts3。将流水线扩展至 120 万个样本并使用 QwQ-32B 作为教师模型，我们得到了 OpenThinker3-7B 模型，该模型取得了最先进的结果：AIME 2025 上 53%、LiveCodeBench 06/24-01/25 上 51%、GPQA Diamond 上 54%——相比 DeepSeek-R1-Distill-Qwen-7B 分别提升了 15.3、17.2 和 20.5 个百分点。我们所有的数据集和模型均已开源。

---

## 175. Text-to-3D by Stitching a Multi-view Reconstruction Network to a Video Generator

**通过将多视角重建网络与视频生成器拼接实现文本到三维生成**

**OpenReview**: [https://openreview.net/forum?id=kI27Niy4xY](https://openreview.net/forum?id=kI27Niy4xY)

**Authors**: Hyojun Go (ETHZ - ETH Zurich), Dominik Narnhofer (ETHZ - ETH Zurich), Goutam Bhat (Google), Prune Truong (Google), Federico Tombari (Google), Konrad Schindler (Swiss Federal Institute of Technology)

**Institutions**: ETHZ - ETH Zurich, Google, Swiss Federal Institute of Technology

**Primary Area**: generative models

**Keywords**: Text-to-3D generation, Video Diffusion Model, 3D Gaussian Splatting, Generation

**TL;DR**: Text-to-3D scene generative modelling by unifying a video generative model with a foundational 3D model via model stitching and alignment.

**TL;DR翻译**: 通过模型拼接与对齐将视频生成模型与基础三维模型统一，实现文本到三维场景的生成建模。

**Abstract**:

The rapid progress of large, pretrained models for both visual content generation and 3D reconstruction opens up new possibilities for text-to-3D generation. Intuitively, one could obtain a formidable 3D scene generator if one were able to combine the power of a modern latent text-to-video model as "generator" with the geometric abilities of a recent (feedforward) 3D reconstruction system as "decoder". We introduce **VIST3A**, a general framework that does just that, addressing two main challenges. First, the two components must be joined in a way that preserves the rich knowledge encoded in their weights. We revisit *model stitching*, i.e., we identify the layer in the 3D decoder that best matches the latent representation produced by the text-to-video generator and stitch the two parts together. That operation requires only a small dataset and no labels. Second, the text-to-video generator must be aligned with the stitched 3D decoder, to ensure that the generated latents are decodable into consistent, perceptually convincing 3D scene geometry. To that end, we adapt *direct reward finetuning*, a popular technique for human preference alignment. We evaluate the proposed VIST3A approach with different video generators and 3D reconstruction models. All tested pairings markedly improve over prior text-to-3D models that output Gaussian splats. Moreover, by choosing a suitable 3D base model, VIST3A also enables high-quality text-to-pointmap generation.

**摘要翻译**:

大规模预训练模型在视觉内容生成和三维重建方面的快速进展为文本到三维生成开辟了新的可能性。直觉上，如果能将现代隐空间文本到视频模型的生成能力与最新前馈式三维重建系统的几何能力结合，便可以获得强大的三维场景生成器。我们提出了 **VIST3A**，一个实现这一目标的通用框架，解决了两个主要挑战。首先，两个组件必须以保留其权重中丰富知识的方式连接。我们重新审视了*模型拼接*方法，即识别三维解码器中与文本到视频生成器产生的隐表示最匹配的层，并将两部分拼接在一起。该操作仅需少量数据且无需标注。其次，文本到视频生成器必须与拼接后的三维解码器对齐，以确保生成的隐表示能被解码为一致且感知上令人信服的三维场景几何。为此，我们采用了*直接奖励微调*，这是一种广泛用于人类偏好对齐的技术。我们使用不同的视频生成器和三维重建模型对所提出的 VIST3A 方法进行了评估。所有测试的组合均显著优于先前输出高斯椭球的文本到三维模型。此外，通过选择合适的三维基础模型，VIST3A 还能实现高质量的文本到点图生成。

---

## 176. A Scalable Distributed Framework for Multimodal GigaVoxel Image Registration

**面向多模态十亿体素图像配准的可扩展分布式框架**

**OpenReview**: [https://openreview.net/forum?id=8dLexnao2h](https://openreview.net/forum?id=8dLexnao2h)

**Authors**: Rohit Jena (University of Pennsylvania), Vedant Zope (University of Pennsylvania), Pratik Chaudhari (School of Engineering and Applied Science, University of Pennsylvania), James Gee (University of Pennsylvania)

**Institutions**: University of Pennsylvania, School of Engineering and Applied Science, University of Pennsylvania

**Primary Area**: infrastructure, software libraries, hardware, systems, etc.

**Keywords**: image registration, distributed optimization, CUDA kernels, neuroanatomy

**TL;DR**: we propose non-GEMM CUDA kernels and distributed primitives to scale multimodal image registration to arbitrary image sizes

**TL;DR翻译**: 我们提出了非 GEMM CUDA 内核和分布式原语，将多模态图像配准扩展到任意图像尺寸。

**Abstract**:

In this work, we propose FFDP, a set of IO-aware non-GEMM fused kernels supplemented with a distributed framework for image registration at unprecedented scales. Image registration is an inverse problem fundamental to biomedical and life sciences, but algorithms have not scaled in tandem with image acquisition capabilities. Our framework complements existing model parallelism techniques proposed for large-scale transformer training by optimizing non-GEMM bottlenecks and enabling convolution-aware tensor sharding. We demonstrate unprecedented capabilities by performing multimodal registration of a 100μm ex-vivo human brain MRI volume at native resolution – an inverse problem more than 570× larger than a standard clinical datum in about a minute using only 8 A6000 GPUs. FFDP accelerates existing state-of-the-art optimization and deep learning registration pipelines by upto 6 − 7× while reducing peak memory consumption by 20 − 59%. Comparative analysis on a 250μm dataset shows that FFDP can fit upto 64× larger problems than existing SOTA on a single GPU, and highlights both the performance and efficiency gains of FFDP compared to SOTA image registration methods.

**摘要翻译**:

本文提出了 FFDP，一组具有 IO 感知能力的非 GEMM 融合内核，并辅以分布式框架，用于实现前所未有规模的图像配准。图像配准是生物医学和生命科学中的基础逆问题，但算法的发展并未跟上图像采集能力的提升。我们的框架通过优化非 GEMM 瓶颈并支持卷积感知的张量分片，补充了现有用于大规模 Transformer 训练的模型并行技术。我们展示了前所未有的能力：仅使用 8 块 A6000 GPU，在约一分钟内完成了 100μm 离体人脑 MRI 体积的原始分辨率多模态配准——该逆问题的规模比标准临床数据大 570 倍以上。FFDP 将现有最先进的优化和深度学习配准流水线加速了 6 至 7 倍，同时将峰值内存消耗降低了 20% 至 59%。在 250μm 数据集上的对比分析表明，FFDP 在单个 GPU 上可处理比现有最先进方法大 64 倍的问题，并凸显了 FFDP 相比最先进图像配准方法在性能和效率方面的提升。

---

## 177. Invisible Safety Threat: Malicious Finetuning for LLM via Steganography

**隐形安全威胁：基于隐写术的大语言模型恶意微调**

**OpenReview**: [https://openreview.net/forum?id=6cEPDGaShH](https://openreview.net/forum?id=6cEPDGaShH)

**Authors**: Guangnian Wan (National University of Singapore), Xinyin Ma (NVIDIA), Gongfan Fang (National University of Singapore), Xinchao Wang (National University of Singapore)

**Institutions**: National University of Singapore, NVIDIA

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: LLM, finetuning, safety, steganography

**TL;DR**: We highlight an insidious safety threat: a compromised LLM can maintain a facade of proper safety alignment while covertly generating harmful content through steganography.

**TL;DR翻译**: 我们揭示了一种隐蔽的安全威胁：被篡改的大语言模型可以在表面上维持正常的安全对齐，同时通过隐写术暗中生成有害内容。

**Abstract**:

Understanding and addressing potential safety alignment risks in large language models (LLMs) is critical for ensuring their safe and trustworthy deployment. In this paper, we highlight an insidious safety threat: a compromised LLM can maintain a facade of proper safety alignment while covertly generating harmful content. To achieve this, we finetune the model to understand and apply a steganographic technique. At inference time, we input a prompt that contains a steganographically embedded malicious target question along with a plaintext cover question. The model, in turn, produces a target response similarly embedded within a benign-looking cover response. In this process, human observers only see the model being prompted with a cover question and generating a corresponding cover response, while the malicious content is hidden from view. We demonstrate this invisible safety threat on GPT-4.1 despite the OpenAI fine-tuning API's safeguards. The finetuned model produces steganographic malicious outputs in response to hidden malicious prompts, while the user interface displays only a fully benign cover interaction. We also replicate the attack on two open-source models, Phi-4 and Mistral-Small-24B-Base-2501, confirming the generality of our method. We quantitatively evaluate our method on the AdvBench dataset, using Llama-Guard-3-8B for content safety classification. Across all three models, all stegotexts containing malicious content are incorrectly classified as safe.

**摘要翻译**:

理解和应对大语言模型 (LLM) 中潜在的安全对齐风险对于确保其安全可信的部署至关重要。本文揭示了一种隐蔽的安全威胁：被篡改的 LLM 可以在表面上维持正常的安全对齐，同时暗中生成有害内容。为实现这一点，我们对模型进行微调，使其理解并应用隐写术技术。在推理时，我们输入一个包含隐写嵌入的恶意目标问题和明文掩护问题的提示。模型随之在看似无害的掩护回复中嵌入生成目标回复。在此过程中，人类观察者只能看到模型被掩护问题提示并生成相应的掩护回复，而恶意内容则被隐藏起来。我们在 GPT-4.1 上演示了这种隐形安全威胁，尽管 OpenAI 微调 API 已有安全防护措施。微调后的模型在响应隐藏的恶意提示时产生隐写式恶意输出，而用户界面仅显示完全无害的掩护交互。我们还在两个开源模型 Phi-4 和 Mistral-Small-24B-Base-2501 上复现了该攻击，验证了方法的通用性。我们在 AdvBench 数据集上使用 Llama-Guard-3-8B 进行内容安全分类的定量评估。在所有三个模型上，所有包含恶意内容的隐写文本均被错误地分类为安全。

---

## 178. Temporal superposition and feature geometry of RNNs under memory demands

**记忆需求下 RNN 的时间叠加与特征几何**

**OpenReview**: [https://openreview.net/forum?id=7cMzTpbJHC](https://openreview.net/forum?id=7cMzTpbJHC)

**Authors**: Pratyaksh Sharma (Imperial College London), Alexandra Maria Proca (Imperial College London), Lucas Prieto (Imperial College London), Pedro A. M. Mediano (Imperial College London)

**Institutions**: Imperial College London

**Primary Area**: interpretability and explainable AI

**Keywords**: RNNs, superposition, representational geometry, features, capacity, memory demands

**TL;DR**: We study the feature geometry of RNNs under memory demands and characterize their representational strategies using a novel framework of temporal superposition.

**TL;DR翻译**: 我们研究了记忆需求下 RNN 的特征几何结构，并利用时间叠加的新颖框架刻画了其表征策略。

**Abstract**:

Understanding how populations of neurons represent information is a central challenge across machine learning and neuroscience. Recent work in both fields has begun to characterize the representational geometry and functionality underlying complex distributed activity. For example, artificial neural networks trained on data with more features than neurons compress data by representing features non-orthogonally in so-called *superposition*. However, the effect of time (or memory), an additional capacity-constraining pressure, on underlying representational geometry in recurrent models is not well understood. Here, we study how memory demands affect representational geometry in recurrent neural networks (RNNs), introducing the concept of temporal superposition. We develop a theoretical framework in RNNs with linear recurrence trained on a delayed serial recall task to better understand how properties of the data, task demands, and network dimensionality lead to different representational strategies, and show that these insights generalize to nonlinear RNNs. Through this, we identify an effectively linear, dense regime and a sparse regime where RNNs utilize an interference-free space, characterized by a phase transition in the angular distribution of features and decrease in spectral radius. Finally, we analyze the interaction of spatial and temporal superposition to observe how RNNs mediate different representational tradeoffs. Overall, our work offers a mechanistic, geometric explanation of representational strategies RNNs learn, how they depend on capacity and task demands, and why.

**摘要翻译**:

理解神经元群体如何表征信息是机器学习和神经科学面临的核心挑战。两个领域的近期研究已开始刻画复杂分布式活动背后的表征几何结构和功能特性。例如，在特征数多于神经元数的数据上训练的人工神经网络通过以非正交方式表示特征来压缩数据，即所谓的*叠加*现象。然而，时间（或记忆）作为额外的容量约束压力对循环模型中底层表征几何的影响尚未被充分理解。在此，我们研究了记忆需求如何影响循环神经网络 (RNN) 中的表征几何结构，并引入了时间叠加的概念。我们在具有线性循环的 RNN 上开发了一个理论框架，该 RNN 在延迟序列回忆任务上训练，以更好地理解数据属性、任务需求和网络维度如何导致不同的表征策略，并表明这些洞察可以推广到非线性 RNN。通过这一研究，我们识别出一种有效线性的稠密状态和一种稀疏状态，其中 RNN 利用了无干扰空间，其特征是特征角度分布的相变和谱半径的下降。最后，我们分析了空间叠加与时间叠加的交互作用，以观察 RNN 如何在不同的表征权衡之间进行调节。总体而言，我们的工作为 RNN 学习的表征策略提供了机制性的几何解释，阐明了这些策略如何依赖于容量和任务需求，以及其背后的原因。

---

## 179. InfoTok: Adaptive Discrete Video Tokenizer via Information-Theoretic Compression

**InfoTok：基于信息论压缩的自适应离散视频分词器**

**OpenReview**: [https://openreview.net/forum?id=JEYWpFGzvn](https://openreview.net/forum?id=JEYWpFGzvn)

**Authors**: Haotian Ye (Stanford University), Qiyuan He (NVIDIA), Jiaqi Han (Computer Science Department, Stanford University), Puheng Li (Stanford University), Jiaojiao Fan (NVIDIA), Zekun Hao (NVIDIA), Fitsum Reda (NVIDIA), Yogesh Balaji (NVIDIA), Huayu Chen (Tsinghua University), Sheng Liu (Stanford University), Angela Yao (National University of Singapore), James Zou (Stanford University), Stefano Ermon (Stanford University), Haoxiang Wang (NVIDIA), Ming-Yu Liu (NVIDIA)

**Institutions**: Stanford University, NVIDIA, Computer Science Department, Stanford University, Tsinghua University, National University of Singapore

**Primary Area**: learning theory

**Keywords**: discrete tokenization, video representation, eficiency, information theory

**TL;DR**: This paper introduces InfoTok, an adaptive video tokenizer guided by information theory, which significantly boosts video compression efficiency and reduces computational overhead without degrading visual quality.

**TL;DR翻译**: 本文提出了 InfoTok，一种以信息论为指导的自适应视频分词器，能够在不降低视觉质量的前提下显著提升视频压缩效率并降低计算开销。

**Abstract**:

Accurate and efficient discrete video tokenization is essential for long video sequences processing. Yet, the inherent complexity and variable information density of videos present a significant bottleneck for current tokenizers, which rigidly compress all content at a fixed rate, leading to redundancy or information loss. Drawing inspiration from Shannon's information theory, this paper introduces \alg, a principled framework for adaptive video tokenization. We rigorously prove that existing data-agnostic training methods are suboptimal in representation length, and present a novel evidence lower bound (ELBO)-based algorithm that approaches theoretical optimality. Leveraging this framework, we develop a transformer-based adaptive compressor that enables adaptive tokenization. Empirical results demonstrate state-of-the-art compression performance, saving $20\%$ tokens without influence on performance, and achieving $2.3\times$ compression rates while still outperforming prior heuristic adaptive approaches. By allocating tokens according to informational richness, \alg enables a more compressed yet accurate tokenization for video representation, offering valuable insights for future research.

**摘要翻译**:

精确高效的离散视频分词对于长视频序列处理至关重要。然而，视频固有的复杂性和可变的信息密度为当前分词器带来了显著瓶颈，这些分词器以固定速率刚性压缩所有内容，导致冗余或信息丢失。受 Shannon 信息论的启发，本文提出了一种有原则的自适应视频分词框架。我们严格证明了现有数据无关的训练方法在表示长度上是次优的，并提出了一种基于证据下界 (ELBO) 的新算法，使其逼近理论最优。利用该框架，我们开发了一种基于 Transformer 的自适应压缩器，实现了自适应分词。实验结果展示了最先进的压缩性能，在不影响性能的情况下节省了 20% 的 token，并达到了 2.3 倍的压缩率，同时仍优于先前的启发式自适应方法。通过根据信息丰富度分配 token，该方法实现了更高压缩率且更精确的视频表示分词，为未来研究提供了有价值的见解。

---

## 180. Actions Speak Louder than Prompts: A Large-Scale Study of LLMs for Graph Inference

**行动胜于提示：大语言模型用于图推理的大规模研究**

**OpenReview**: [https://openreview.net/forum?id=MgJUj9Sk3C](https://openreview.net/forum?id=MgJUj9Sk3C)

**Authors**: Ben Finkelshtein (University of Oxford), Silviu Cucerzan (Microsoft), Sujay Kumar Jauhar (Microsoft Research), Ryen W White (Microsoft)

**Institutions**: University of Oxford, Microsoft, Microsoft Research

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Large Language Models, Prompting, In-Context Learning, Tool-augmented Reasoning, Text-rich Graphs

**TL;DR**: A comprehensive study of LLMs for node classification, providing a principled understanding of their capabilities in processing graph information that practitioners can apply in real-world tasks

**TL;DR翻译**: 一项关于大语言模型用于节点分类的全面研究，提供了对其处理图信息能力的系统性理解，可供从业者应用于实际任务。

**Abstract**:

Large language models (LLMs) are increasingly leveraged for text-rich graph machine learning tasks, with node classification standing out due to its high-impact application domains such as fraud detection and recommendation systems. Yet, despite a surge of interest, the field lacks a principled understanding of the capabilities of LLMs in processing graph data. In this work, we conduct a large-scale, controlled evaluation across the key axes of variability: the LLM-graph interaction mode, comparing prompting, tool-use, and code generation; dataset domains, spanning citation, web-link, e-commerce, and social networks; homophilic vs. heterophilic regimes; short- vs. long-text features; LLM sizes and reasoning capabilities. We further analyze dependencies by independently truncating features, deleting edges, and removing labels to quantify reliance on input types. Our findings provide actionable guidance for both research and practice. (1) Code generation mode achieves the strongest overall performance, with especially large gains on long-text or high-degree graphs where prompting quickly exceeds the token budget. (2) All interaction strategies remain effective on heterophilic graphs, challenging the assumption that LLM-based methods collapse under low homophily. (3) Code generation mode is able to flexibly shift its reliance to the most informative input type, whether that be structure, features, or labels. Together, these results establish a clear picture of the strengths and limitations of current LLM–graph interaction modes and point to design principles for future methods.

**摘要翻译**:

大语言模型 (LLM) 越来越多地被应用于富文本图机器学习任务，其中节点分类因其在欺诈检测和推荐系统等高影响力应用领域而尤为突出。然而，尽管研究兴趣激增，该领域仍缺乏对 LLM 处理图数据能力的系统性理解。本研究在关键变量维度上进行了大规模的控制实验评估：LLM 与图的交互模式（对比提示、工具使用和代码生成）、数据集领域（涵盖引用网络、网页链接、电子商务和社交网络）、同配性与异配性机制、短文本与长文本特征、LLM 规模和推理能力。我们还通过独立截断特征、删除边和移除标签来量化对输入类型的依赖性，进一步分析了这些依赖关系。我们的发现为研究和实践提供了可操作的指导。(1) 代码生成模式取得了最强的整体性能，在长文本或高度数图上表现出尤其显著的优势，因为提示方式会迅速超出 token 预算。(2) 所有交互策略在异配性图上仍然有效，挑战了基于 LLM 的方法在低同配性下会失效的假设。(3) 代码生成模式能够灵活地将其依赖转向最具信息量的输入类型，无论是结构、特征还是标签。这些结果共同清晰地揭示了当前 LLM-图交互模式的优势和局限性，并为未来方法的设计指明了原则。

---

## 181. Through the Lens of Contrast: Self-Improving Visual Reasoning in VLMs

**对比视角下的自我提升：视觉语言模型中的视觉推理**

**OpenReview**: [https://openreview.net/forum?id=ZymCPON45y](https://openreview.net/forum?id=ZymCPON45y)

**Authors**: Zhiyu Pan (Alibaba Group), Yizheng Wu (Alibaba Group), Jiashen Hua (Alibaba Group), Junyi Feng, Shaotian Yan (Alibaba Group), Bing Deng (Alibaba Group), Zhiguo Cao (Huazhong University of Science and Technology), Jieping Ye (Alibaba Group)

**Institutions**: Alibaba Group, Huazhong University of Science and Technology

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Reasoning, Vision-Language Models, Contrasting

**Abstract**:

Reasoning has emerged as a key capability of large language models. In linguistic tasks, this capability can be enhanced by self-improving techniques that refine reasoning paths for subsequent fine-tuning. However, extending these language-based self-improving approaches to vision language models (VLMs) presents a unique challenge: visual hallucinations in reasoning paths cannot be effectively verified or rectified. Our solution starts with a key observation about visual contrast: when presented with a contrastive VQA pair, i.e., two visually similar images with synonymous questions, VLMs identify relevant visual cues more precisely compared with when given a single VQA sample. Motivated by this observation, we propose Visual Contrastive Self-Taught Reasoner (VC-STaR), a novel self-improving framework that leverages visual contrast to mitigate hallucinations in model-generated rationales. We collect a diverse suite of VQA datasets, curate contrastive pairs according to multi-modal similarity, and generate rationales using VC-STaR. Consequently, we obtain a new visual reasoning dataset, VisCoR-$55$K, which is then used to boost the reasoning capability of various VLMs through supervised finetuning. Extensive experiments show that VC-STaR not only outperforms existing self-improving approaches but also surpasses models finetuned on the SoTA visual reasoning datasets, demonstrating that the inherent contrastive ability of VLMs can bootstrap their own visual reasoning. The code, dataset and trained models will be released upon acceptance.

**摘要翻译**:

推理已成为大语言模型的一项关键能力。在语言任务中，可以通过自我提升技术来优化推理路径，从而增强这一能力以用于后续微调。然而，将这些基于语言的自我提升方法扩展到视觉语言模型 (VLM) 面临独特的挑战：推理路径中的视觉幻觉无法被有效验证或纠正。我们的解决方案始于对视觉对比的一个关键观察：当呈现一个对比式 VQA 样本对（即两张视觉相似的图像配以同义问题）时，VLM 能比仅给定单个 VQA 样本时更精确地识别相关视觉线索。受此观察启发，我们提出了视觉对比自学推理器 (VC-STaR)，一种利用视觉对比来减轻模型生成推理过程中幻觉的新颖自我提升框架。我们收集了多样化的 VQA 数据集套件，根据多模态相似性构造对比样本对，并使用 VC-STaR 生成推理过程。由此，我们获得了一个新的视觉推理数据集 VisCoR-55K，用于通过监督微调提升各种 VLM 的推理能力。大量实验表明，VC-STaR 不仅优于现有的自我提升方法，还超越了在最先进视觉推理数据集上微调的模型，证明了 VLM 固有的对比能力可以自举提升其自身的视觉推理能力。代码、数据集和训练模型将在论文被接收后发布。

---

## 182. SAFETY-GUIDED FLOW (SGF): A UNIFIED FRAMEWORK FOR NEGATIVE GUIDANCE IN SAFE GENERATION

**安全引导流 (SGF)：安全生成中负向引导的统一框架**

**OpenReview**: [https://openreview.net/forum?id=EA80Zib9UI](https://openreview.net/forum?id=EA80Zib9UI)

**Authors**: Mingyu Kim (Kookmin University), Young-Heon Kim (University of British Columbia), Mijung Park (University of British Columbia)

**Institutions**: Kookmin University, University of British Columbia

**Primary Area**: generative models

**Keywords**: Safe generation, flow matching, control barrier functions

**TL;DR**: We introduced a unified probabilistic framework for safe generation in diffusion and flow models, using Maximum Mean Discrepancy-based energy potentials.

**TL;DR翻译**: 我们提出了一种统一的概率框架，利用基于最大均值差异 (MMD) 的能量势函数实现扩散模型和流模型中的安全生成。

**Abstract**:

Safety mechanisms for diffusion and flow models have recently been developed along two distinct paths. In robot planning, control barrier functions are employed to guide generative trajectories away from obstacles at every denoising step by explicitly imposing geometric constraints. In parallel, recent data-driven, negative guidance approaches have been shown to suppress harmful content and promote diversity in generated samples. However, they rely on heuristics without clearly stating when safety guidance is actually necessary. In this paper, we first introduce a unified probabilistic framework using a Maximum Mean Discrepancy (MMD) potential for image generation tasks that recasts both Shielded Diffusion and Safe Denoiser as instances of our energy-based negative guidance against unsafe data samples. Furthermore, we leverage control-barrier functions analysis to justify the existence of a critical time window in which negative guidance must be strong; outside of this window, the guidance should decay to zero to ensure safe and high-quality generation. We evaluate our unified framework on several realistic safe generation scenarios, confirming that negative guidance should be applied in the early stages of the denoising process for successful safe generation.

**摘要翻译**:

扩散模型和流模型的安全机制近期沿着两条不同的路径发展。在机器人规划中，控制障碍函数通过在每个去噪步骤中显式施加几何约束来引导生成轨迹远离障碍物。与此同时，近期数据驱动的负向引导方法已被证明能够抑制有害内容并促进生成样本的多样性。然而，这些方法依赖于启发式规则，并未明确指出安全引导何时是真正必要的。本文首先引入了一种使用最大均值差异 (MMD) 势函数的统一概率框架，用于图像生成任务，将 Shielded Diffusion 和 Safe Denoiser 均重新表述为我们基于能量的针对不安全数据样本的负向引导的实例。此外，我们利用控制障碍函数分析来证明存在一个关键时间窗口，在该窗口内负向引导必须保持强力；在此窗口之外，引导应衰减为零以确保安全且高质量的生成。我们在多个真实的安全生成场景上评估了我们的统一框架，证实负向引导应在去噪过程的早期阶段施加才能成功实现安全生成。

---

## 183. Depth Anything 3: Recovering the Visual Space from Any Views

**Depth Anything 3：从任意视角恢复视觉空间**

**OpenReview**: [https://openreview.net/forum?id=yirunib8l8](https://openreview.net/forum?id=yirunib8l8)

**Authors**: Haotong Lin (Zhejiang University), Sili Chen, Jun Hao Liew (SalesForce), Donny Y. Chen (ByteDance Seed (Singapore)), Zhenyu Li (King Abdullah University of Science and Technology), Yang Zhao (ByteDance Inc.), Sida Peng (Zhejiang University), Hengkai Guo (Bytedance Intelligent Creation), Xiaowei Zhou (Zhejiang University), Guang Shi (ByteDance Inc.), Jiashi Feng (ByteDance), Bingyi Kang (Bytedance)

**Institutions**: Zhejiang University, SalesForce, ByteDance Seed (Singapore), King Abdullah University of Science and Technology, ByteDance Inc., Bytedance Intelligent Creation, ByteDance, Bytedance

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Depth Estimation

**TL;DR**: Depth Anything 3 uses a single vanilla DINOv2 transformer to take arbitrary input views and outputs consistent depth and ray maps, delivering leading pose, geometry, and visual rendering performance.

**TL;DR翻译**: Depth Anything 3 使用单个原生 DINOv2 Transformer 接受任意输入视角并输出一致的深度图和光线图，在位姿估计、几何重建和视觉渲染性能上均处于领先水平。

**Abstract**:

We present Depth Anything 3 (DA3), a model that predicts spatially consistent geometry from an arbitrary number of visual inputs, with or without known camera poses. In pursuit of minimal modeling, DA3 yields two key insights: a single plain transformer (e.g., vanilla DINOv2 encoder) is sufficient as a backbone without architectural specialization, and a singular depth-ray prediction target obviates the need for complex multi-task learning. Through our teacher-student training paradigm, the model achieves a level of detail and generalization on par with Depth Anything 2 (DA2). We establish a new visual geometry benchmark covering camera pose estimation, any-view geometry and visual rendering. On this benchmark, DA3 sets a new state-of-the-art across all tasks, surpassing prior SOTA VGGT by an average of 35.7% in camera pose accuracy and 23.6% in geometric accuracy. Moreover, it outperforms DA2 in monocular depth estimation. All models are trained exclusively on public academic datasets.

**摘要翻译**:

我们提出了 Depth Anything 3 (DA3)，一个能够从任意数量的视觉输入（无论是否具有已知相机位姿）预测空间一致性几何的模型。在追求极简建模的过程中，DA3 产生了两个关键洞察：单个普通 Transformer（例如原生 DINOv2 编码器）作为骨干网络就已足够，无需架构特化；而单一的深度-光线预测目标消除了复杂多任务学习的必要性。通过我们的教师-学生训练范式，该模型在细节和泛化能力上达到了与 Depth Anything 2 (DA2) 相当的水平。我们建立了一个新的视觉几何基准，涵盖相机位姿估计、任意视角几何和视觉渲染。在该基准上，DA3 在所有任务上均达到了新的最先进水平，在相机位姿精度上平均超越先前最优的 VGGT 35.7%，在几何精度上超越 23.6%。此外，它在单目深度估计方面也优于 DA2。所有模型均完全在公开的学术数据集上训练。

---

## 184. Taming Momentum: Rethinking Optimizer States Through Low-Rank Approximation

**驯化动量：通过低秩近似重新思考优化器状态**

**OpenReview**: [https://openreview.net/forum?id=9Q0dNBYeEY](https://openreview.net/forum?id=9Q0dNBYeEY)

**Authors**: Zhengbo Wang (University of Science and Technology of China), Jian Liang (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Ran He (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Zilei Wang (University of Science and Technology of China), Tieniu Tan

**Institutions**: University of Science and Technology of China, Institute of automation, Chinese academy of science, Chinese Academy of Sciences

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Large Language Models; Efficient Training; Low-Rank; LoRA

**Abstract**:

Modern optimizers like Adam and Muon are central to training large language models, but their reliance on first- and second-order momenta introduces significant memory overhead, which constrains scalability and computational efficiency. In this work, we reframe the exponential moving average (EMA) used in these momenta as the training of a linear regressor via online gradient flow. Building on this equivalence, we introduce LoRA-Pre, a novel low-rank optimizer designed for efficient pre-training. Specifically, LoRA-Pre reduces the optimizer's memory footprint by decomposing the full momentum matrix into a compact low-rank subspace within the online linear learner, thereby maintaining optimization performance while improving memory efficiency. We empirically validate LoRA-Pre's efficacy by pre-training models from the Llama architecture family, scaling from 60M to 1B parameters. LoRA-Pre achieves the highest performance across all model sizes. Notably, LoRA-Pre demonstrates remarkable rank efficiency, achieving comparable or superior results using only 1/8 the rank of baseline methods. Beyond pre-training, we evaluate LoRA-Pre's effectiveness in fine-tuning scenarios. With the same rank, LoRA-Pre consistently outperforms all efficient fine-tuning baselines. Specifically, compared to standard LoRA, LoRA-Pre achieves substantial improvements of 3.14 points on Llama-3.1-8B and 6.17 points on Llama-2-7B, validating our approach's effectiveness across both pre-training and fine-tuning paradigms. Our code is publicly available at https://github.com/mrflogs/LoRA-Pre.

**摘要翻译**:

Adam 和 Muon 等现代优化器是训练大语言模型的核心，但它们对一阶和二阶动量的依赖引入了显著的内存开销，限制了可扩展性和计算效率。本文将这些动量中使用的指数移动平均 (EMA) 重新理解为通过在线梯度流训练线性回归器。基于这一等价关系，我们提出了 LoRA-Pre，一种为高效预训练设计的新型低秩优化器。具体而言，LoRA-Pre 通过将完整的动量矩阵分解为在线线性学习器中的紧凑低秩子空间来减少优化器的内存占用，从而在保持优化性能的同时提高内存效率。我们通过预训练 Llama 架构家族的模型（参数规模从 6000 万到 10 亿）来验证 LoRA-Pre 的有效性。LoRA-Pre 在所有模型规模上均取得了最高性能。值得注意的是，LoRA-Pre 展现了卓越的秩效率，仅使用基线方法 1/8 的秩就能达到相当或更优的结果。除预训练外，我们还评估了 LoRA-Pre 在微调场景中的有效性。在相同秩的条件下，LoRA-Pre 持续优于所有高效微调基线。具体而言，与标准 LoRA 相比，LoRA-Pre 在 Llama-3.1-8B 上实现了 3.14 分的显著提升，在 Llama-2-7B 上实现了 6.17 分的提升，验证了我们方法在预训练和微调两种范式中的有效性。代码已在 https://github.com/mrflogs/LoRA-Pre 公开。

---

## 185. Premise Selection for a Lean Hammer

**面向 Lean 自动化证明工具的前提选择**

**OpenReview**: [https://openreview.net/forum?id=m04JJNeRK6](https://openreview.net/forum?id=m04JJNeRK6)

**Authors**: Thomas Zhu (ByteDance Inc.), Joshua Clune (Carnegie Mellon University), Jeremy Avigad (Carnegie Mellon University), Albert Q. Jiang (Mistral AI), Sean Welleck

**Institutions**: ByteDance Inc., Carnegie Mellon University, Mistral AI

**Primary Area**: neurosymbolic & hybrid AI systems (physics-informed, logic & formal reasoning, etc.)

**Keywords**: premise selection, interactive theorem proving, automated reasoning, contrastive learning

**TL;DR**: LeanHammer integrates neural premise selection with symbolic reasoning to automate theorem proving in Lean.

**TL;DR翻译**: LeanHammer 将神经前提选择与符号推理相结合，实现了 Lean 中定理证明的自动化。

**Abstract**:

Neural methods are transforming automated reasoning for proof assistants, yet integrating these advances into practical verification workflows remains challenging. A $\textit{hammer}$ is a tool that integrates premise selection, translation to external automatic theorem provers, and proof reconstruction into one overarching tool to automate tedious reasoning steps. We present LeanPremise, a novel neural premise selection system, and we combine it with existing translation and proof reconstruction components to create LeanHammer, the first end-to-end domain general hammer for the Lean proof assistant. Unlike existing Lean premise selectors, LeanPremise is specifically trained for use with a hammer in dependent type theory. It also dynamically adapts to user-specific contexts, enabling it to effectively recommend premises from libraries outside LeanPremise's training data as well as lemmas defined by the user locally. With comprehensive evaluations, we show that LeanPremise enables LeanHammer to solve 21% more goals than existing premise selectors and generalizes well to diverse domains. Our work helps bridge the gap between neural retrieval and symbolic reasoning, making formal verification more accessible to researchers and practitioners.

**摘要翻译**:

神经方法正在变革证明辅助系统中的自动推理，但将这些进展整合到实际验证工作流中仍然充满挑战。*Hammer* 是一种将前提选择、向外部自动定理证明器的翻译以及证明重构集成于一体的工具，用于自动化繁琐的推理步骤。我们提出了 LeanPremise，一种新颖的神经前提选择系统，并将其与现有的翻译和证明重构组件相结合，创建了 LeanHammer——首个面向 Lean 证明辅助系统的端到端通用领域 hammer。与现有的 Lean 前提选择器不同，LeanPremise 专门为依赖类型论中的 hammer 使用而训练。它还能动态适应用户特定的上下文，从而能够有效推荐来自 LeanPremise 训练数据之外的库中的前提以及用户本地定义的引理。通过全面的评估，我们证明 LeanPremise 使 LeanHammer 比现有前提选择器多解决了 21% 的目标，并且在不同领域具有良好的泛化能力。我们的工作有助于弥合神经检索与符号推理之间的差距，使形式化验证对研究者和从业者更加易用。

---

## 186. DepthLM: Metric Depth from Vision Language Models

**DepthLM：基于视觉语言模型的度量深度估计**

**OpenReview**: [https://openreview.net/forum?id=ObFVZGnSFN](https://openreview.net/forum?id=ObFVZGnSFN)

**Authors**: Zhipeng Cai (Meta), Ching-Feng Yeh (Facebook), Hu Xu (FAIR, AMI Foundation), Zhuang Liu (Princeton University), Gregory P. Meyer (Facebook), Xinjie Lei (Facebook), Changsheng Zhao (Meta Inc.), Shang-Wen Li (Facebook), Vikas Chandra (Meta), Yangyang Shi (Meta)

**Institutions**: Meta, Facebook, FAIR, AMI Foundation, Princeton University, Meta Inc.

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Metric depth, Vision language model, Spatial reasoning

**TL;DR**: The first proof that VLMs can have expert model level depth estimation accuracy without architecture or loss change

**TL;DR翻译**: 首次证明视觉语言模型无需更改架构或损失函数即可达到专家模型级别的深度估计精度

**Abstract**:

Vision language models (VLMs) can flexibly address various vision tasks through text interactions. Although successful in semantic understanding, state-of-the-art VLMs including GPT-5 still struggle in understanding 3D from 2D inputs. On the other hand, expert pure vision models achieve super-human accuracy in metric depth estimation, a key 3D understanding task. However, they require task-specific architectures and losses. Such difference motivates us to ask: Can VLMs reach expert-level accuracy without architecture or loss change? We take per-pixel metric depth estimation as the representative task and show that the answer is yes! Surprisingly, comprehensive analysis shows that text-based supervised-finetuning with sparse labels is sufficient for VLMs to unlock strong 3D understanding, no dense prediction head or complex regression/regularization loss is needed. The bottleneck lies in pixel reference and cross-dataset camera ambiguity, which we address through visual prompting and intrinsic-conditioned augmentation. With much smaller models, our method DepthLM surpasses the accuracy of most advanced VLMs by over 2x, making VLMs for the first time comparable with pure vision models. The simplicity of DepthLM also enables a single VLM to cover various 3D tasks beyond metric depth. Code and model are available at https://github.com/facebookresearch/DepthLM_Official.

**摘要翻译**:

视觉语言模型 (VLM) 可以通过文本交互灵活地处理各种视觉任务。尽管在语义理解方面取得了成功，但包括 GPT-5 在内的最先进 VLM 在从二维输入理解三维方面仍面临困难。另一方面，专家级纯视觉模型在度量深度估计这一关键三维理解任务上达到了超人的精度，但它们需要特定于任务的架构和损失函数。这种差异促使我们提出一个问题：VLM 能否在不更改架构或损失函数的情况下达到专家级精度？我们以逐像素度量深度估计作为代表性任务，表明答案是肯定的。令人惊讶的是，全面分析表明，使用稀疏标签进行基于文本的监督微调就足以让 VLM 解锁强大的三维理解能力，无需密集预测头或复杂的回归/正则化损失。瓶颈在于像素参考和跨数据集的相机歧义，我们通过视觉提示和内参条件增强来解决这些问题。使用更小的模型，我们的方法 DepthLM 在精度上超越了大多数先进 VLM 两倍以上，使 VLM 首次可与纯视觉模型相媲美。DepthLM 的简洁性还使单个 VLM 能够覆盖度量深度之外的各种三维任务。代码和模型已在 https://github.com/facebookresearch/DepthLM_Official 开源。

---

## 187. Hallucination Begins Where Saliency Drops

**幻觉始于显著性消失之处**

**OpenReview**: [https://openreview.net/forum?id=sjnErRHXf3](https://openreview.net/forum?id=sjnErRHXf3)

**Authors**: Xiaofeng Zhang (Shanghai Jiao Tong University), Yuanchao Zhu (Dalian Martime University), Chaochen Gu (Shanghai Jiaotong University), Xiaosong Yuan (Alibaba Group), Qiyan Zhao (Institute of automation, Chinese academy of science), Jiawei Cao (Shanghai Jiaotong University), Feilong Tang (Monash University), Sinan Fan (Zhejiang University), Yaomin Shen (Nanchang Research Institute, Zhejiang University), Chen Shen (Alibaba Group), Hao Tang (Peking University)

**Institutions**: Shanghai Jiao Tong University, Dalian Martime University, Shanghai Jiaotong University, Alibaba Group, Institute of automation, Chinese academy of science, Monash University, Zhejiang University, Nanchang Research Institute, Zhejiang University, Peking University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LVLMs-Saliency; Saliency-Guided Rejection Sampling; Local Coherence Reinforcement; Hallucination

**Abstract**:

Recent studies have investigated attention dynamics in large vision language models (LVLMs), yet existing methods remain limited in reliably distinguishing hallucinated from correct outputs — primarily because they rely solely on forward-pass attention, ignoring gradient-based signals that reveal how token influence propagates through the model. To bridge this gap, we introduce **LVLMs-Saliency**, an *gradient-aware diagnostic tool* that quantifies the grounding strength of each output token by fusing attention weights with their gradients. Through analysis, we identify a decisive pattern: *Hallucinations occur when prior output tokens shows low saliency to the next token prediction*, indicating a failure of contextual memory. Building on this insight, we propose a dual-mechanism inference-time framework: (1) Saliency-Guided Rejection Sampling (SGRS), which dynamically filters candidate tokens during decoding by rejecting those with saliency below a context-adaptive threshold, thereby preventing coherence-breaking tokens from entering the sequence; and (2) Local Coherence Reinforcement (LocoRE), a lightweight plug-and-play module that strengthens attention from the current token to its most recent outputs, actively counteracting the "forgetting" behavior identified by LVLMs-Saliency. Experimental results demonstrate that our method significantly reduces hallucinations across multiple LVLMs, offering a robust and interpretable solution to improve model reliability.

**摘要翻译**:

近期研究已经探索了大视觉语言模型 (LVLM) 中的注意力动态，但现有方法在可靠区分幻觉输出与正确输出方面仍然有限——主要原因在于它们仅依赖前向传播的注意力，忽略了揭示 token 影响如何在模型中传播的梯度信号。为弥合这一差距，我们提出了 **LVLMs-Saliency**，一种*梯度感知的诊断工具*，通过融合注意力权重及其梯度来量化每个输出 token 的接地强度。通过分析，我们发现了一个决定性模式：*当先前输出 token 对下一个 token 预测的显著性较低时，幻觉就会发生*，这表明上下文记忆出现了失效。基于这一洞察，我们提出了一种双重机制的推理时框架：(1) 显著性引导的拒绝采样 (SGRS)，在解码过程中动态过滤候选 token，拒绝显著性低于上下文自适应阈值的 token，从而防止破坏连贯性的 token 进入序列；(2) 局部连贯性增强 (LocoRE)，一种轻量级即插即用模块，增强当前 token 对其最近输出的注意力，主动抵消 LVLMs-Saliency 所识别的"遗忘"行为。实验结果表明，我们的方法在多个 LVLM 上显著减少了幻觉，为提高模型可靠性提供了稳健且可解释的解决方案。

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

---

## 189. On the Generalization Capacities of MLLMs for Spatial Intelligence

**论多模态大语言模型在空间智能方面的泛化能力**

**OpenReview**: [https://openreview.net/forum?id=DE5ZJtR4bg](https://openreview.net/forum?id=DE5ZJtR4bg)

**Authors**: Gongjie Zhang (Alibaba Group), Wenhao Li (Nanyang Technological University), Quanhao Qian (DAMO Academy, Alibaba Group), Jiuniu Wang (Alibaba Group), Deli Zhao (Alibaba Group), Shijian Lu (Nanyang Technological University), Ran Xu (Alibaba Group)

**Institutions**: Alibaba Group, Nanyang Technological University, DAMO Academy, Alibaba Group

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: 3D Computer Vision, Multimodal Large Language Model, Spatial Intelligence, Embodied AI

**TL;DR**: We show that RGB-only MLLMs are fundamentally flawed for spatial reasoning due to an inherent geometric ambiguity, and propose a camera-aware MLLM framework that incorporates camera intrinsics for robust, generalizable spatial intelligence.

**TL;DR翻译**: 我们表明，仅使用 RGB 输入的多模态大语言模型由于固有的几何歧义在空间推理方面存在根本缺陷，并提出了一种融合相机内参的相机感知多模态大语言模型框架，以实现稳健且可泛化的空间智能。

**Abstract**:

Multimodal Large Language Models (MLLMs) that directly process RGB inputs for tasks like 3D localization and navigation have shown remarkable potential. However, we argue that these "RGB-only" approaches are fundamentally flawed in their ability to generalize across cameras. By ignoring camera parameters, they entangle an object's physical properties with the camera's perspective, creating an irresolvable ambiguity. We show this leads MLLMs to overfit to the training camera distribution, rather than learning true and generalizable 3D geometric principles. To address this, we propose Camera-Aware MLLM framework for spatial MLLMs. It learns generalizable spatial reasoning by: (i) injecting camera intrinsics via a dense embedding that conditions each visual token; (ii) introducing a camera-aware data augmentation strategy that synthetically varies camera parameters, forcing the model to disentangle camera properties from scene content; and (iii) distilling geometric priors from a 3D vision foundation model. Extensive experiments demonstrate that camera-aware MLLMs substantially outperform their naive counterparts, particularly in cross-camera generalization tests on spatially-grounded tasks, indicating that camera-awareness is not only beneficial but also a prerequisite for robust and generalizable spatial intelligence in MLLMs.

**摘要翻译**:

直接处理 RGB 输入以完成三维定位和导航等任务的多模态大语言模型 (MLLM) 已展现出显著的潜力。然而，我们认为这些"仅 RGB"方法在跨相机泛化能力方面存在根本缺陷。由于忽略了相机参数，它们将物体的物理属性与相机视角纠缠在一起，产生了不可解决的歧义。我们的研究表明，这导致 MLLM 过拟合于训练阶段的相机分布，而非学习真正的、可泛化的三维几何原理。为解决这一问题，我们提出了面向空间 MLLM 的相机感知 MLLM 框架。该框架通过以下方式学习可泛化的空间推理：(i) 通过条件化每个视觉 token 的密集嵌入注入相机内参；(ii) 引入相机感知的数据增强策略，合成地改变相机参数，迫使模型将相机属性与场景内容解耦；(iii) 从三维视觉基础模型中蒸馏几何先验。大量实验表明，相机感知的 MLLM 显著优于其简单对应版本，尤其是在空间定位任务的跨相机泛化测试中，这表明相机感知不仅是有益的，更是 MLLM 实现稳健且可泛化空间智能的前提条件。

---

## 190. The Polar Express: Optimal Matrix Sign Methods and their Application to the Muon Algorithm

**Polar Express：最优矩阵符号方法及其在 Muon 算法中的应用**

**OpenReview**: [https://openreview.net/forum?id=yRtgZ1K8hO](https://openreview.net/forum?id=yRtgZ1K8hO)

**Authors**: Noah Amsel (NYU, New York University), David Persson (New York University), Christopher Musco (Brown University), Robert M. Gower (Flatiron Institute)

**Institutions**: NYU, New York University, New York University, Brown University, Flatiron Institute

**Primary Area**: optimization

**Keywords**: polar decomposition, matrix sign, numerical linear algebra, muon, optimization, approximation theory

**TL;DR**: We introduce a GPU-friendly algorithm for computing the polar decomposition of a matrix to low accuracy that is optimal in its class. This improves Muon.

**TL;DR翻译**: 我们提出了一种 GPU 友好的算法，用于以低精度计算矩阵的极分解，该算法在其类别中是最优的。这改进了 Muon 算法。

**Abstract**:

Computing the polar decomposition and the related matrix sign function has been a well-studied problem in numerical analysis for decades. Recently, it has emerged as an important subroutine within the Muon algorithm for training deep neural networks. However, the requirements of this application differ sharply from classical settings: deep learning demands GPU-friendly algorithms that prioritize high throughput over high precision. We introduce *Polar Express*, a new method for computing the polar decomposition. Like Newton–Schulz and other classical polynomial methods, our approach uses only matrix-matrix multiplications, making it very efficient on GPUs. Inspired by earlier work of Chen & Chow and Nakatsukasa & Freund, *Polar Express* adapts the update rule at each iteration by solving a minimax optimization problem. We prove that this strategy minimizes error in a worst-case sense, allowing *Polar Express* to converge as rapidly as possible both in the early iterations and asymptotically. We also address finite-precision issues, making it practical to use in `bfloat16`. When integrated into Muon, our method yields consistent improvements in validation loss for a GPT-2 model on one to ten billion tokens from the FineWeb dataset, outperforming recent alternatives across a range of learning rates.

**摘要翻译**:

计算极分解及相关的矩阵符号函数在数值分析领域已被研究了数十年。近年来，它作为 Muon 算法中训练深度神经网络的重要子程序而受到关注。然而，该应用的需求与经典场景截然不同：深度学习需要 GPU 友好的算法，优先考虑高吞吐量而非高精度。我们提出了 *Polar Express*，一种计算极分解的新方法。与 Newton-Schulz 及其他经典多项式方法类似，我们的方法仅使用矩阵-矩阵乘法，因此在 GPU 上非常高效。受 Chen & Chow 以及 Nakatsukasa & Freund 早期工作的启发，*Polar Express* 通过求解极小极大优化问题在每次迭代中自适应地调整更新规则。我们证明该策略在最坏情况意义下最小化误差，使 *Polar Express* 在早期迭代和渐近阶段都能以尽可能快的速度收敛。我们还解决了有限精度问题，使其可在 `bfloat16` 下实际使用。当集成到 Muon 中时，我们的方法在 FineWeb 数据集的 10 亿到 100 亿 token 上为 GPT-2 模型带来了一致的验证损失改进，在多种学习率下均优于近期的替代方法。

---

## 191. Characterizing the Discrete Geometry of ReLU Networks

**刻画 ReLU 网络的离散几何结构**

**OpenReview**: [https://openreview.net/forum?id=TgLW2DiRDG](https://openreview.net/forum?id=TgLW2DiRDG)

**Authors**: Blake B. Gaines (University of Connecticut), Jinbo Bi (University of Connecticut)

**Institutions**: University of Connecticut

**Primary Area**: learning theory

**Keywords**: Polyhedrons, Geometry, ReLU, Activations

**TL;DR**: We describe the geometry of the polyhedral complexes defined by the linear regions of ReLU networks, both by theoretically bounding their connectivity and diameter and by empirically characterizing it using experiments on trained networks.

**TL;DR翻译**: 我们描述了 ReLU 网络线性区域所定义的多面体复形的几何结构，通过理论上界定其连通性和直径，以及通过在训练网络上的实验进行经验性刻画。

**Abstract**:

It is well established that ReLU networks define continuous piecewise-linear functions, and that their linear regions are polyhedra in the input space. These regions form a complex that fully partitions the input space. The way these regions fit together is fundamental to the behavior of the network, as nonlinearities occur only at the boundaries where these regions connect. However, relatively little is known about the geometry of these complexes beyond bounds on the total number of regions, and calculating the complex exactly is intractable for most networks. In this work, we prove new theoretical results about these complexes that hold for all fully-connected ReLU networks, specifically about their connectivity graphs in which nodes correspond to regions and edges exist between each pair of regions connected by a face. We find that the average degree of this graph is upper bounded by twice the input dimension regardless of the width and depth of the network, and that the diameter of this graph has an upper bound that does not depend on input dimension, despite the number of regions increasing exponentially with input dimension. We corroborate our findings through experiments with networks trained on both synthetic and real-world data, which provide additional insight into the geometry of ReLU networks.

**摘要翻译**:

众所周知，ReLU 网络定义了连续的分段线性函数，其线性区域是输入空间中的多面体。这些区域形成了一个完全划分输入空间的复形。这些区域的组合方式对网络行为至关重要，因为非线性仅发生在这些区域连接的边界处。然而，除了关于区域总数的界限之外，对这些复形几何结构的了解相对有限，且对大多数网络来说，精确计算复形在计算上是不可行的。本文证明了关于这些复形的新理论结果，适用于所有全连接 ReLU 网络，具体涉及其连通性图——图中节点对应区域，通过面相连的区域对之间存在边。我们发现该图的平均度的上界为输入维度的两倍，与网络的宽度和深度无关；而该图的直径的上界不依赖于输入维度，尽管区域数量随输入维度呈指数增长。我们通过在合成数据和真实数据上训练的网络实验验证了这些发现，为 ReLU 网络的几何结构提供了额外的洞察。

---

## 192. ThinKV: Thought-Adaptive KV Cache Compression for Efficient Reasoning Models

**ThinKV：面向高效推理模型的思维自适应 KV 缓存压缩**

**OpenReview**: [https://openreview.net/forum?id=M3CeHnZKNC](https://openreview.net/forum?id=M3CeHnZKNC)

**Authors**: Akshat Ramachandran (Georgia Institute of Technology), Marina Neseem (NVIDIA), Charbel Sakr (NVIDIA), Rangharajan Venkatesan (Purdue University), Brucek Khailany (NVIDIA), Tushar Krishna (Georgia Institute of Technology)

**Institutions**: Georgia Institute of Technology, NVIDIA, Purdue University

**Primary Area**: generative models

**Keywords**: Large Reasoning Models, KV Cache Compression, Quantization, Eviction, Sparsity, Thought-Aware Compression

**Abstract**:

The long-output context generation of large reasoning models enables extended chain of thought (CoT) but also drives rapid growth of the key–value (KV) cache, quickly overwhelming GPU memory. To address this challenge, we propose ThinKV, a thought-adaptive KV cache compression framework. ThinKV is based on the observation that attention sparsity reveals distinct thought types with varying importance within the CoT. It applies a hybrid quantization–eviction strategy, assigning token precision by thought importance and progressively evicting tokens from less critical thoughts as reasoning trajectories evolve. Furthermore, to implement ThinKV, we design a kernel that extends PagedAttention to enable efficient reuse of evicted tokens' memory slots, eliminating compaction overheads. Extensive experiments on DeepSeek-R1-Distill, GPT-OSS, and NVIDIA AceReason across mathematics and coding benchmarks show that ThinKV achieves near-lossless accuracy with less than 5% of the original KV cache, while improving performance with up to 5.8x higher inference throughput over SoTA baselines.

**摘要翻译**:

大型推理模型的长输出上下文生成支持了扩展的思维链 (CoT)，但也导致键值 (KV) 缓存快速增长，迅速耗尽 GPU 内存。为应对这一挑战，我们提出了 ThinKV，一种思维自适应的 KV 缓存压缩框架。ThinKV 基于以下观察：注意力稀疏性揭示了 CoT 中具有不同重要性的不同思维类型。它采用混合量化-驱逐策略，根据思维重要性分配 token 精度，并随着推理轨迹的演进逐步驱逐不太关键的思维中的 token。此外，为实现 ThinKV，我们设计了一个扩展 PagedAttention 的内核，以高效重用被驱逐 token 的内存槽位，消除了压实开销。在 DeepSeek-R1-Distill、GPT-OSS 和 NVIDIA AceReason 上跨数学和编程基准的大量实验表明，ThinKV 使用不到原始 KV 缓存 5% 的空间即可实现近乎无损的精度，同时推理吞吐量较最先进基线提升高达 5.8 倍。

---

## 193. Difficult Examples Hurt Unsupervised Contrastive Learning: A Theoretical Perspective

**困难样本损害无监督对比学习：一个理论视角**

**OpenReview**: [https://openreview.net/forum?id=5LMdnUdAoy](https://openreview.net/forum?id=5LMdnUdAoy)

**Authors**: Yi-Ge Zhang (Peking University), Jingyi Cui (Peking University), Qiran Li (The Hong Kong University of Science and Technology), Yisen Wang

**Institutions**: Peking University, The Hong Kong University of Science and Technology

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Machine Learning. Self-Supervised Learning. Difficult Examples

**TL;DR**: We introduce a similarity-based theoretical framework that shows how difficult boundary examples impair generalization in unsupervised contrastive learning, and we design mechanisms that address this issue and boost downstream accuracy.

**TL;DR翻译**: 我们引入了一种基于相似性的理论框架，揭示了困难边界样本如何损害无监督对比学习的泛化能力，并设计了解决该问题、提升下游任务准确率的机制。

**Abstract**:

Unsupervised contrastive learning has shown significant performance improvements in recent years, often approaching or even rivaling supervised learning in various tasks. However, its learning mechanism is fundamentally different from supervised learning. Previous works have shown that difficult examples (well-recognized in supervised learning as examples around the decision boundary), which are essential in supervised learning, contribute minimally in unsupervised settings. In this paper, perhaps surprisingly, we find that the direct removal of difficult examples, although reduces the sample size, can boost the downstream classification performance of contrastive learning. To uncover the reasons behind this, we develop a theoretical framework modeling the similarity between different pairs of samples. Guided by this framework, we conduct a thorough theoretical analysis revealing that the presence of difficult examples negatively affects the generalization of contrastive learning. Furthermore, we demonstrate that the removal of these examples, and techniques such as margin tuning and temperature scaling can enhance its generalization bounds, thereby improving performance. Empirically, we propose a simple and efficient mechanism for selecting difficult examples and validate the effectiveness of the aforementioned methods, which substantiates the reliability of our proposed theoretical framework.

**摘要翻译**:

无监督对比学习近年来展示了显著的性能提升，在各种任务中往往接近甚至媲美监督学习。然而，其学习机制与监督学习有着根本性的不同。先前研究表明，困难样本（在监督学习中被广泛认为是决策边界附近的样本）虽然在监督学习中至关重要，但在无监督设置中贡献甚微。在本文中，我们发现了一个或许令人意外的现象：直接移除困难样本虽然减少了样本量，却能提升对比学习的下游分类性能。为揭示其背后的原因，我们开发了一个建模不同样本对之间相似性的理论框架。在该框架的指导下，我们进行了深入的理论分析，揭示了困难样本的存在对对比学习的泛化能力具有负面影响。此外，我们证明了移除这些样本以及间隔调整和温度缩放等技术可以增强其泛化界，从而提升性能。在实验方面，我们提出了一种简单高效的困难样本选择机制，并验证了上述方法的有效性，从而证实了我们所提出理论框架的可靠性。

---

## 194. Let Features Decide Their Own Solvers: Hybrid Feature Caching for Diffusion Transformers

**让特征自主选择求解器：面向扩散 Transformer 的混合特征缓存**

**OpenReview**: [https://openreview.net/forum?id=URbsHlTK8c](https://openreview.net/forum?id=URbsHlTK8c)

**Authors**: Shikang Zheng, Guantao Chen (SUN YAT-SEN UNIVERSITY), Qinming Zhou (Tsinghua University), Yuqi Lin (Jilin University), Lixuan He, Chang Zou (Shanghai Jiaotong University), Peiliang Cai (Shanghai Jiaotong University), Jiacheng Liu (Shanghai Jiaotong University), Linfeng Zhang (Shanghai Jiaotong University)

**Institutions**: SUN YAT-SEN UNIVERSITY, Tsinghua University, Jilin University, Shanghai Jiaotong University

**Primary Area**: generative models

**Keywords**: Generative models, Efficient ML, Diffusion Transformer Acceleration, Feature Caching

**Abstract**:

Diffusion Transformers offer state-of-the-art fidelity in image and video synthesis, but their iterative sampling process remains a major bottleneck due to the high cost of transformer forward passes at each timestep. To mitigate this, feature caching has emerged as a training-free acceleration technique that reuses hidden representations. However, existing methods often apply a uniform caching strategy across all feature dimensions, ignoring their heterogeneous dynamic behaviors. Therefore, we adopt a new perspective by modeling hidden feature evolution as a mixture of ODEs across dimensions, and introduce **HyCa**, a Hybrid ODE solver inspired caching framework that applies dimension-wise caching strategies. HyCa achieves near-lossless acceleration across diverse tasks and models, including 5.55x speedup on FLUX, 5.56x speedup on HunyuanVideo, 6.24x speedup on Qwen-Image and Qwen-Image-Edit without retraining.

**摘要翻译**:

扩散 Transformer 在图像和视频合成方面提供了最先进的保真度，但由于每个时间步中 Transformer 前向传播的高昂成本，其迭代采样过程仍然是主要瓶颈。为缓解这一问题，特征缓存作为一种免训练的加速技术应运而生，通过重用隐藏表示来实现加速。然而，现有方法通常在所有特征维度上应用统一的缓存策略，忽略了其异质的动态行为。因此，我们采用了一种新视角，将隐藏特征的演化建模为跨维度的 ODE 混合体，并提出了 **HyCa**——一种受混合 ODE 求解器启发的缓存框架，应用维度级别的缓存策略。HyCa 在多种任务和模型上实现了近乎无损的加速，包括在 FLUX 上 5.55 倍加速、在 HunyuanVideo 上 5.56 倍加速、在 Qwen-Image 和 Qwen-Image-Edit 上 6.24 倍加速，且无需重新训练。

---

## 195. MotionStream: Real-Time Video Generation with Interactive Motion Controls

**MotionStream：具有交互式运动控制的实时视频生成**

**OpenReview**: [https://openreview.net/forum?id=v1DKz5Vxr7](https://openreview.net/forum?id=v1DKz5Vxr7)

**Authors**: Joonghyuk Shin (Seoul National University), Zhengqi Li (Google), Richard Zhang (Adobe Systems), Jun-Yan Zhu (Carnegie Mellon University), Jaesik Park (Seoul National University), Eli Shechtman (Adobe), Xun Huang

**Institutions**: Seoul National University, Google, Adobe Systems, Carnegie Mellon University, Adobe

**Primary Area**: generative models

**Keywords**: Interactive Video Generation, Motion Control, Real-Time Generation, Causal Generation

**TL;DR**: We present MotionStream, a streaming (real-time, infinite length) video generation system with motion controls, unlocking new possibilities for interactive content creation.

**TL;DR翻译**: 我们提出了 MotionStream，一个具有运动控制的流式（实时、无限长度）视频生成系统，为交互式内容创作开辟了新的可能性。

**Abstract**:

Current motion-conditioned video generation methods suffer from prohibitive latency (minutes per video) and non-causal processing that prevents real-time interaction. We present MotionStream, enabling sub-second latency with up to 29 FPS streaming generation on a single GPU. Our approach begins by augmenting a text-to-video model with motion control, which generates high-quality videos that adhere to the global text prompt and local motion guidance, but does not perform inference on the fly. As such, we distill this bidirectional teacher into a causal student through Self Forcing with Distribution Matching Distillation, enabling real-time streaming inference. Several key challenges arise when generating videos of long, potentially infinite time-horizons -- (1) bridging the domain gap from training on finite length and extrapolating to infinite horizons, (2) sustaining high quality by preventing error accumulation, and (3) maintaining fast inference, without incurring growth in computational cost due to increasing context windows. A key to our approach is introducing carefully designed sliding-window causal attention, combined with attention sinks. By incorporating self-rollout with attention sinks and KV cache rolling during training, we properly simulate inference-time extrapolations with a fixed context window, enabling constant-speed generation of arbitrarily long videos. Our models achieve state-of-the-art results in motion following and video quality while being two orders of magnitude faster, uniquely enabling infinite-length streaming. With MotionStream, users can paint trajectories, control cameras, or transfer motion, and see results unfold in real-time, delivering a truly interactive experience.

**摘要翻译**:

当前基于运动条件的视频生成方法受限于高延迟（每段视频需数分钟）和非因果处理方式，无法实现实时交互。我们提出了 MotionStream，在单个 GPU 上实现了亚秒级延迟和高达 29 FPS 的流式生成。我们的方法首先为文本到视频模型增加运动控制功能，生成遵循全局文本提示和局部运动引导的高质量视频，但不进行实时推理。为此，我们通过自强迫与分布匹配蒸馏将这一双向教师模型蒸馏为因果学生模型，从而实现实时流式推理。在生成长时间甚至潜在无限时间范围的视频时，出现了几个关键挑战——(1) 弥合有限长度训练与无限时间范围外推之间的域差距；(2) 通过防止误差累积来维持高质量；(3) 保持快速推理，避免因上下文窗口增长而带来的计算成本增加。我们方法的关键在于引入精心设计的滑动窗口因果注意力机制，结合注意力锚点。通过在训练中融合自展开与注意力锚点以及 KV 缓存滚动，我们在固定上下文窗口下正确模拟推理时的外推，实现任意长度视频的恒速生成。我们的模型在运动跟随和视频质量方面取得了最先进的结果，同时速度快两个数量级，独特地支持无限长度的流式生成。借助 MotionStream，用户可以绘制轨迹、控制相机或迁移运动，并实时看到结果展开，提供真正的交互式体验。

---

## 196. BioX-Bridge: Model Bridging for Unsupervised Cross-Modal Knowledge Transfer across Biosignals

**BioX-Bridge：面向生物信号跨模态无监督知识迁移的模型桥接方法**

**OpenReview**: [https://openreview.net/forum?id=1448q0s3zZ](https://openreview.net/forum?id=1448q0s3zZ)

**Authors**: Chenqi Li (University of Oxford), Yu Liu (University of Oxford), Timothy Denison (University of Oxford), Tingting Zhu (University of Oxford)

**Institutions**: University of Oxford

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: biosignal, ai for healthcare, humans and ai, unsupervised cross-modal knowledge transfer

**Abstract**:

Biosignals offer valuable insights into the physiological states of the human body. Although biosignal modalities differ in functionality, signal fidelity, sensor comfort, and cost, they are often intercorrelated, reflecting the holistic and interconnected nature of human physiology. This opens up the possibility of performing the same tasks using alternative biosignal modalities, thereby improving the accessibility, usability, and adaptability of health monitoring systems. However, the limited availability of large labeled datasets presents challenges for training models tailored to specific tasks and modalities of interest. Unsupervised cross-modal knowledge transfer offers a promising solution by leveraging knowledge from an existing modality to support model training for a new modality. Existing methods are typically based on knowledge distillation, which requires running a teacher model alongside student model training, resulting in high computational and memory overhead. This challenge is further exacerbated by the recent development of foundation models that demonstrate superior performance and generalization across tasks at the cost of large model sizes. To this end, we explore a new framework for unsupervised cross-modal knowledge transfer of biosignals by training a lightweight bridge network to align the intermediate representations and enable information flow between foundation models and across modalities. Specifically, we introduce an efficient strategy for selecting alignment positions where the bridge should be constructed, along with a flexible prototype network as the bridge architecture. Extensive experiments across multiple biosignal modalities, tasks, and datasets show that BioX-Bridge reduces the number of trainable parameters by 88-99% while maintaining or even improving transfer performance compared to state-of-the-art methods.

**摘要翻译**:

生物信号为了解人体生理状态提供了有价值的见解。尽管不同生物信号模态在功能、信号保真度、传感器舒适度和成本上有所差异，但它们往往相互关联，反映了人体生理的整体性和互联性。这为使用替代生物信号模态执行相同任务开辟了可能性，从而提高健康监测系统的可及性、可用性和适应性。然而，大规模标注数据集的有限可用性为训练针对特定任务和模态的模型带来了挑战。无监督跨模态知识迁移通过利用现有模态的知识来支持新模态的模型训练，提供了一种有前景的解决方案。现有方法通常基于知识蒸馏，需要在学生模型训练的同时运行教师模型，导致高昂的计算和内存开销。基础模型的近期发展虽然在各任务上展现了卓越的性能和泛化能力，但其庞大的模型规模进一步加剧了这一挑战。为此，我们探索了一种新的生物信号无监督跨模态知识迁移框架，通过训练轻量级桥接网络来对齐中间表示，并实现基础模型之间和跨模态的信息流动。具体而言，我们引入了一种高效的策略来选择应构建桥接的对齐位置，以及一种灵活的原型网络作为桥接架构。在多种生物信号模态、任务和数据集上的大量实验表明，BioX-Bridge 将可训练参数减少了 88% 至 99%，同时与最先进方法相比保持甚至提升了迁移性能。

---

## 197. Compactness and Consistency: A Conjoint Framework for Deep Graph Clustering

**紧凑性与一致性：面向深度图聚类的联合框架**

**OpenReview**: [https://openreview.net/forum?id=9jdQLmPUHW](https://openreview.net/forum?id=9jdQLmPUHW)

**Authors**: Wei Ju, Siyu Yi (Sichuan University), Kangjie Zheng (Wellcome Sanger Institute), Yifan Wang (University of International Business and Economics), Ziyue Qiao, Li Shen (Sun Yat-Sen University), Yongdao Zhou (Nankai University), Xiaochun Cao (SUN YAT-SEN UNIVERSITY), Jiancheng Lv (Sichuan University)

**Institutions**: Sichuan University, Wellcome Sanger Institute, University of International Business and Economics, Sun Yat-Sen University, Nankai University, SUN YAT-SEN UNIVERSITY

**Primary Area**: learning on graphs and other geometries & topologies

**Keywords**: Graph Neural Networks, Graph Clustering, Representation Learning, Compactness Learning, Consistency Learning

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

Graph clustering is a fundamental task in data analysis, aiming at grouping nodes with similar characteristics in the graph into clusters. This problem has been widely explored using graph neural networks (GNNs) due to their ability to leverage node attributes and graph topology for effective cluster assignments. However, representations learned through GNNs typically struggle to capture global relationships between nodes via local message-passing mechanisms. Moreover, the redundancy and noise inherently present in graph data may easily result in node representations lacking compactness and robustness. To address these issues, we propose a conjoint framework CoCo, which captures compactness and consistency in the learned node representations for deep graph clustering. Technically, our CoCo leverages graph convolutional filters to learn robust node representations from both local and global views, and then encodes them into low-rank compact embeddings, thus effectively removing the redundancy and noise as well as uncovering the intrinsic underlying structure. To further enrich the node semantics, we develop a consistency learning strategy based on compact embeddings to facilitate knowledge transfer from the two perspectives. Our experimental results indicate that our CoCo outperforms state-of-the-art counterparts on various datasets. The code is available at https://github.com/juweipku/CoCo.

**摘要翻译**:

图聚类是数据分析中的一项基础任务，旨在将图中具有相似特征的节点分组为不同的簇。由于图神经网络（GNN）能够利用节点属性和图拓扑结构进行有效的簇分配，该问题已被广泛探索。然而，通过 GNN 学习到的表示通常难以通过局部消息传递机制捕获节点间的全局关系。此外，图数据中固有的冗余和噪声容易导致节点表示缺乏紧凑性和鲁棒性。为解决这些问题，我们提出了一个联合框架 CoCo，在学习到的节点表示中同时捕获紧凑性和一致性，以实现深度图聚类。在技术层面，CoCo 利用图卷积滤波器从局部和全局视角学习鲁棒的节点表示，然后将其编码为低秩紧凑嵌入，从而有效去除冗余和噪声并揭示内在的底层结构。为进一步丰富节点语义，我们基于紧凑嵌入开发了一致性学习策略，以促进两个视角之间的知识迁移。实验结果表明，CoCo 在多个数据集上优于现有的最先进方法。代码已在 https://github.com/juweipku/CoCo 上发布。

---

## 198. WAFT: Warping-Alone Field Transforms for Optical Flow

**WAFT：仅基于变形的场变换光流估计方法**

**OpenReview**: [https://openreview.net/forum?id=HTqGE0KcuF](https://openreview.net/forum?id=HTqGE0KcuF)

**Authors**: Yihan Wang (Princeton University), Jia Deng (Princeton University)

**Institutions**: Princeton University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Optical Flow; Computer Vision; Warping; Dense Correspondences

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

We introduce Warping-Alone Field Transforms (WAFT), a simple and effective method for optical flow. WAFT is similar to RAFT but replaces cost volume with high-resolution warping, achieving better accuracy with lower memory cost. This design challenges the conventional wisdom that constructing cost volumes is necessary for strong performance. WAFT is a simple and flexible meta-architecture with minimal inductive biases and reliance on custom designs. Compared with existing methods, WAFT ranks 1st on Spring, Sintel, and KITTI benchmarks, achieves the best zero-shot generalization on KITTI, while being 1.3-4.1x faster than existing methods that have competitive accuracy (e.g., 1.3x than Flowformer++, 4.1x than CCMR+). Code and model weights are available at https://github.com/princeton-vl/WAFT.

**摘要翻译**:

我们提出了仅基于变形的场变换（WAFT），一种简洁高效的光流估计方法。WAFT 与 RAFT 类似，但用高分辨率变形替代了代价体积，在降低内存开销的同时实现了更高的精度。这一设计挑战了"构建代价体积是实现高性能所必需的"这一传统观点。WAFT 是一种简洁灵活的元架构，具有极少的归纳偏置且不依赖于定制化设计。与现有方法相比，WAFT 在 Spring、Sintel 和 KITTI 基准测试中均排名第一，在 KITTI 上实现了最佳的零样本泛化性能，同时比具有竞争力精度的现有方法快 1.3 至 4.1 倍（例如比 Flowformer++ 快 1.3 倍，比 CCMR+ 快 4.1 倍）。代码和模型权重已在 https://github.com/princeton-vl/WAFT 上发布。

---

## 199. FlashWorld: High-quality 3D Scene Generation within Seconds

**FlashWorld：秒级高质量3D场景生成**

**OpenReview**: [https://openreview.net/forum?id=2IftRjRB07](https://openreview.net/forum?id=2IftRjRB07)

**Authors**: Xinyang Li (Xiamen University), Tengfei Wang (Shanghai AI Lab), Zixiao Gu (Fudan University), Shengchuan Zhang (Xiamen University), Chunchao Guo (Tencent), Liujuan Cao (Xiamen University)

**Institutions**: Xiamen University, Shanghai AI Lab, Fudan University, Tencent

**Primary Area**: generative models

**Keywords**: 3D Scene Generation, Multi-view Diffusion Models, World Models, Distribution Matching Distillation

**TL;DR**: a generative model that produces high-quality 3D scenes from a single image or text prompt in seconds

**TL;DR翻译**: 一种能够在数秒内根据单张图像或文本提示生成高质量3D场景的生成模型

**Abstract**:

We propose FlashWorld, a generative model that produces 3D scenes from a single image or text prompt in seconds, $10 \sim 100\times$ faster than previous works while possessing superior rendering quality.
Our approach shifts from the conventional multi-view-oriented (MV-oriented) paradigm, which generates multi-view images for subsequent 3D reconstruction, to a 3D-oriented approach where the model directly produces 3D Gaussian representations during multi-view generation.
While ensuring 3D consistency, 3D-oriented method typically suffers poor visual quality.
FlashWorld includes a dual-mode pre-training phase followed by a cross-mode post-training phase, effectively integrating the strengths of both paradigms.
Specifically, leveraging the prior from a video diffusion model, we first pre-train a dual-mode multi-view diffusion model, which jointly supports MV-oriented and 3D-oriented generation mode.
To bridge the quality gap in 3D-oriented generation, we further propose a cross-mode post-training distillation by matching distribution from consistent 3D-oriented mode to high-quality MV-oriented mode.
This not only enhances visual quality while maintaining 3D consistency, but also reduces the required denoising steps for inference.
Also, we propose a strategy to leverage massive single-view images and text prompts during this process to enhance the model's generalization to out-of-distribution inputs.
Extensive experiments demonstrate the superiority and efficiency of our method.
Our code is released at https://github.com/imlixinyang/FlashWorld.

**摘要翻译**:

我们提出了 FlashWorld，一种能够在数秒内从单张图像或文本提示生成3D场景的生成模型，速度比先前工作快 $10 \sim 100$ 倍，同时具有更优的渲染质量。我们的方法从传统的多视图导向（MV-oriented）范式——即先生成多视图图像再进行3D重建——转变为3D导向的方法，使模型在多视图生成过程中直接产生 3D Gaussian 表示。然而，3D导向方法在保证3D一致性的同时，通常视觉质量较差。FlashWorld 包含一个双模式预训练阶段和一个跨模式后训练阶段，有效整合了两种范式的优势。具体而言，我们利用视频扩散模型的先验知识，首先预训练一个同时支持多视图导向和3D导向生成模式的双模式多视图扩散模型。为弥合3D导向生成中的质量差距，我们进一步提出跨模式后训练蒸馏方法，通过将一致的3D导向模式的分布匹配到高质量的多视图导向模式。这不仅在保持3D一致性的同时提升了视觉质量，还减少了推理所需的去噪步数。此外，我们提出了一种在此过程中利用大量单视图图像和文本提示的策略，以增强模型对分布外输入的泛化能力。大量实验证明了我们方法的优越性和高效性。代码已在 https://github.com/imlixinyang/FlashWorld 上发布。

---

## 200. TabStruct: Measuring Structural Fidelity of Tabular Data

**TabStruct：度量表格数据的结构保真度**

**OpenReview**: [https://openreview.net/forum?id=XOPH34Extq](https://openreview.net/forum?id=XOPH34Extq)

**Authors**: Xiangjian Jiang (University of Cambridge), Nikola Simidjievski (Télécom Paris), Mateja Jamnik (University of Cambridge)

**Institutions**: University of Cambridge, Télécom Paris

**Primary Area**: datasets and benchmarks

**Keywords**: Tabular data, Tabular data structure, Synthetic data generation

**TL;DR**: We propose TabStruct, a comprehensive benchmark, along with a novel metric, global utility, for evaluating the structural fidelity of tabular data without requiring access to ground-truth causal structures.

**TL;DR翻译**: 我们提出了 TabStruct，一个综合基准测试，以及一种新颖的评估指标——全局效用，用于在无需访问真实因果结构的情况下评估表格数据的结构保真度。

**Abstract**:

Evaluating tabular generators remains a challenging problem, as the unique causal structural prior of heterogeneous tabular data does not lend itself to intuitive human inspection. Recent work has introduced structural fidelity as a tabular-specific evaluation dimension to assess whether synthetic data complies with the causal structures of real data. However, existing benchmarks often neglect the interplay between structural fidelity and conventional evaluation dimensions, thus failing to provide a holistic understanding of model performance. Moreover, they are typically limited to toy datasets, as quantifying existing structural fidelity metrics requires access to ground-truth causal structures, which are rarely available for real-world datasets. In this paper, we propose a novel evaluation framework that jointly considers structural fidelity and conventional evaluation dimensions. We introduce a new evaluation metric, global utility, which enables the assessment of structural fidelity even in the absence of ground-truth causal structures. In addition, we present TabStruct, a comprehensive evaluation benchmark offering large-scale quantitative analysis on 13 tabular generators from nine distinct categories, across 29 datasets. Our results demonstrate that global utility provides a task-independent, domain-agnostic lens for tabular generator performance. We release the TabStruct benchmark suite, including all datasets, evaluation pipelines, and raw results. Code is available at https://github.com/SilenceX12138/TabStruct.

**摘要翻译**:

评估表格数据生成器仍然是一个具有挑战性的问题，因为异构表格数据独特的因果结构先验不便于直观的人工检查。近期工作引入了结构保真度作为表格数据特有的评估维度，用以评估合成数据是否符合真实数据的因果结构。然而，现有基准往往忽视了结构保真度与传统评估维度之间的相互作用，因而无法全面理解模型性能。此外，由于量化现有结构保真度指标需要访问真实因果结构，而这在真实世界数据集中很少可用，因此现有基准通常局限于玩具数据集。在本文中，我们提出了一种联合考虑结构保真度和传统评估维度的新型评估框架。我们引入了一种新的评估指标——全局效用，使得即使在缺乏真实因果结构的情况下也能评估结构保真度。此外，我们推出了 TabStruct，一个综合评估基准，对来自9个不同类别的13个表格生成器在29个数据集上进行了大规模定量分析。实验结果表明，全局效用为表格生成器性能提供了一个与任务无关、与领域无关的评估视角。我们发布了 TabStruct 基准测试套件，包括所有数据集、评估流程和原始结果。代码已在 https://github.com/SilenceX12138/TabStruct 上发布。

---

## 201. Uncover Underlying Correspondence for Robust Multi-view Clustering

**揭示潜在对应关系以实现鲁棒的多视图聚类**

**OpenReview**: [https://openreview.net/forum?id=a4S1nQay3b](https://openreview.net/forum?id=a4S1nQay3b)

**Authors**: Haochen Zhou (Sichuan University), Guofeng Ding (Sichuan University), Mouxing Yang (Sichuan University), Peng Hu (Sichuan University), Yijie Lin (Sichuan University), Xi Peng (Sichuan University)

**Institutions**: Sichuan University

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Multi-view clustering; Noisy Correspondence

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

Multi-view clustering (MVC) aims to group unlabeled data into semantically meaningful clusters by leveraging cross-view consistency.
However, real-world datasets collected from the web often suffer from noisy correspondence (NC), which breaks the consistency prior and results in unreliable alignments.
In this paper, we identify two critical forms of NC that particularly harm clustering: i) category-level mismatch, where semantically consistent samples from the same class are mistakenly treated as negatives; and ii) sample-level mismatch, where collected cross-view pairs are misaligned and some samples may even lack any valid counterpart.
To address these challenges, we propose **CorreGen**, a generative framework that formulates noisy correspondence learning in MVC as maximum likelihood estimation over underlying cross-view correspondences.
The objective is elegantly solved via an Expectation–Maximization algorithm: in the E-step, soft correspondence distributions are inferred across views, capturing class-level relations while adaptively down-weighting noisy or unalignable samples through GMM-guided marginals; in the M-step, the embedding network is updated to maximize the expected log-likelihood. Extensive experiments on both synthetic and real-world noisy datasets demonstrate that our method significantly improves clustering robustness. The code will be released upon acceptance.

**摘要翻译**:

多视图聚类（MVC）旨在利用跨视图一致性将无标签数据分组为具有语义意义的簇。然而，从网络收集的真实世界数据集往往存在噪声对应（NC）问题，这打破了一致性先验并导致不可靠的对齐。在本文中，我们识别了两种对聚类特别有害的关键噪声对应形式：i）类别级不匹配，即来自同一类别的语义一致样本被错误地视为负样本；ii）样本级不匹配，即收集的跨视图配对存在错位，某些样本甚至可能缺乏任何有效的对应样本。为应对这些挑战，我们提出了 **CorreGen**，一个生成式框架，将多视图聚类中的噪声对应学习建模为对潜在跨视图对应关系的最大似然估计。该目标通过期望最大化（EM）算法优雅地求解：在E步中，跨视图推断软对应分布，捕获类别级关系，同时通过 GMM 引导的边际分布自适应地降低噪声或不可对齐样本的权重；在M步中，更新嵌入网络以最大化期望对数似然。在合成和真实世界噪声数据集上的大量实验表明，我们的方法显著提高了聚类的鲁棒性。代码将在论文被接受后发布。

---

## 202. Instilling an Active Mind in Avatars via Cognitive Simulation

**通过认知仿真为虚拟化身注入主动心智**

**OpenReview**: [https://openreview.net/forum?id=80JylHgQn1](https://openreview.net/forum?id=80JylHgQn1)

**Authors**: Jianwen Jiang, Weihong Zeng (ByteDance Inc.), Zerong Zheng (ByteDance Inc.), Jiaqi Yang (ByteDance Inc.), Chao Liang (ByteDance Inc.), Wang Liao (ByteDance Inc.), Han Liang (ByteDance Inc.), Weifeng Chen (ByteDance Inc.), XING WANG (ByteDance), Yuan Zhang, Mingyuan Gao (ByteDance Inc.)

**Institutions**: ByteDance Inc., ByteDance

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Video Generatio, Human Animation, Avatar, Multimedia

**TL;DR**: This paper introduces a novel framework that uses a Large Language Model (LLM) for semantic guidance and a Multimodal Diffusion Transformer (DiT) for fusion to generate expressive, context-aware video avatars, demonstrating competitive performance

**TL;DR翻译**: 本文提出了一种新框架，利用大语言模型（LLM）进行语义引导，并采用多模态 Diffusion Transformer（DiT）进行融合，生成富有表现力且具有上下文感知能力的视频虚拟化身，展现了具有竞争力的性能

**Abstract**:

Current video avatar models can generate fluid animations but struggle to capture a character's authentic essence, primarily synchronizing motion with low-level audio cues instead of understanding higher-level semantics like emotion or intent. To bridge this gap, we propose a novel framework for generating character animations that are not only physically plausible but also semantically rich and expressive. Our model is built on two technical innovations. First, we employ Multimodal Large Language Models to generate a structured textual representation from input conditions, providing high-level semantic guidance for creating contextually and emotionally resonant actions. Second, to ensure robust fusion of multimodal signals, we introduce a specialized Multimodal Diffusion Transformer architecture featuring a novel Pseudo Last Frame design. This allows our model to accurately interpret the joint semantics of audio, images and text, generating motions that are deeply coherent with the overall context. Comprehensive experiments validate the superiority of our method, which achieves compelling results in lip-sync accuracy, video quality, motion naturalness, and semantic consistency. The approach also shows strong generalization to challenging scenarios, including multi-person and non-human subjects. Our video results are linked in https://omnihuman-lab.github.io/v1_5/ .

**摘要翻译**:

当前的视频虚拟化身模型能够生成流畅的动画，但难以捕捉角色的真实本质，主要依赖低层级音频线索进行动作同步，而非理解情感或意图等更高层级的语义。为弥合这一差距，我们提出了一种新框架，用于生成不仅在物理上合理、而且在语义上丰富且富有表现力的角色动画。我们的模型基于两项技术创新。首先，我们采用多模态大语言模型从输入条件生成结构化文本表示，为创建具有上下文关联和情感共鸣的动作提供高层级语义引导。其次，为确保多模态信号的稳健融合，我们引入了一种专门的多模态 Diffusion Transformer 架构，其中包含新颖的伪末帧（Pseudo Last Frame）设计。这使得模型能够准确解读音频、图像和文本的联合语义，生成与整体上下文深度一致的动作。全面的实验验证了我们方法的优越性，在唇形同步精度、视频质量、动作自然度和语义一致性方面均取得了令人信服的结果。该方法还展现了对包括多人场景和非人类主体在内的挑战性场景的强泛化能力。视频结果详见 https://omnihuman-lab.github.io/v1_5/ 。

---

## 203. Diffusion Language Model Knows the Answer Before It Decodes

**扩散语言模型在解码之前就已知道答案**

**OpenReview**: [https://openreview.net/forum?id=g88nt4ieTG](https://openreview.net/forum?id=g88nt4ieTG)

**Authors**: Pengxiang Li (Hong Kong Polytechnic University), Yefan Zhou (Dartmouth College), Dilxat Muhtar (Nanjing University), Lu Yin (University of Surrey), Shilin Yan (Alibaba Group), Li Shen (Sun Yat-Sen University), Yi Liang (Google), Soroush Vosoughi (Dartmouth College), Shiwei Liu (ELLIS Institute Tübingen & Max Planck Institute for Intelligent Systems)

**Institutions**: Hong Kong Polytechnic University, Dartmouth College, Nanjing University, University of Surrey, Alibaba Group, Sun Yat-Sen University, Google, ELLIS Institute Tübingen & Max Planck Institute for Intelligent Systems

**Primary Area**: generative models

**Keywords**: diffusion language model, discrete

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

Diffusion language models (DLMs) have recently emerged as an alternative to autoregressive approaches, offering parallel sequence generation and flexible token orders. However, their inference remains slower than that of autoregressive models, primarily due to the cost of bidirectional attention and the large number of refinement steps required for high-quality outputs. In this work, we highlight and leverage an overlooked property of DLMs, **early answer convergence**: in many cases, the correct answer can be internally identified by half steps before the final decoding step, both under semi-autoregressive and random re-masking schedules. For example, on GSM8K and MMLU, up to 97\% and 99\% of instances, respectively, can be decoded correctly using only half of the refinement steps.
Building on this observation, we introduce **Prophet**, a training-free fast decoding paradigm that enables **early commit decoding**. Specifically, Prophet dynamically decides whether to continue refinement or to go ''all-in'' (i.e., decode all remaining tokens in one step), using the confidence gap between the top-2 prediction candidates as the criterion. It integrates seamlessly into existing DLM implementations, incurs negligible overhead, and requires no additional training.
Empirical evaluations of LLaDA-8B and Dream-7B across multiple tasks show that Prophet reduces the number of decoding steps by up to 3.4$\times$ while preserving high generation quality. These results recast DLM decoding as a problem of ''when to stop refinement'', and demonstrate that early decode convergence provides a simple yet powerful mechanism for accelerating DLM inference, complementary to existing speedup techniques. Our code is submitted.

**摘要翻译**:

扩散语言模型（DLM）近来作为自回归方法的替代方案而兴起，提供了并行序列生成和灵活的 token 顺序。然而，其推理速度仍慢于自回归模型，主要原因是双向注意力的计算开销以及高质量输出所需的大量细化步骤。在本工作中，我们发现并利用了 DLM 一个被忽视的特性——**答案早期收敛**：在许多情况下，正确答案在最终解码步骤之前的一半步骤中就已经被内部识别出来，这在半自回归和随机重掩码策略下均成立。例如，在 GSM8K 和 MMLU 上，分别有高达 97% 和 99% 的实例仅使用一半细化步骤即可正确解码。基于这一观察，我们提出了 **Prophet**，一种无需训练的快速解码范式，实现了**提前提交解码**。具体而言，Prophet 以 top-2 预测候选之间的置信度差距为标准，动态决定是继续细化还是"全力以赴"（即一步解码所有剩余 token）。它能无缝集成到现有 DLM 实现中，几乎不产生额外开销，且无需额外训练。在 LLaDA-8B 和 Dream-7B 上跨多个任务的实证评估表明，Prophet 将解码步骤数减少了最多 3.4 倍，同时保持了高生成质量。这些结果将 DLM 解码重新定义为"何时停止细化"的问题，并证明了答案早期收敛为加速 DLM 推理提供了一种简单而强大的机制，与现有加速技术互补。我们的代码已提交。

---

## 204. Generative Human Geometry Distribution

**生成式人体几何分布**

**OpenReview**: [https://openreview.net/forum?id=YsQM7sQl0j](https://openreview.net/forum?id=YsQM7sQl0j)

**Authors**: Xiangjun Tang (King Abdullah University of Science and Technology), Biao Zhang, Peter Wonka (Snap Inc.)

**Institutions**: King Abdullah University of Science and Technology, Snap Inc.

**Primary Area**: generative models

**Keywords**: 3D Generation, Human Generation, Geometry Encoding

**TL;DR**: We introduce the first method that integrates geometry distributions into generative modeling.

**TL;DR翻译**: 我们提出了首个将几何分布融入生成式建模的方法。

**Abstract**:

Realistic human geometry generation is an important yet challenging task, requiring both the preservation of fine clothing details and the accurate modeling of clothing-body interactions. To tackle this challenge, we build upon Geometry distributions—a recently proposed representation that can model a single human geometry with high fidelity using a flow matching model. However, extending a single-geometry distribution to a dataset is non-trivial and inefficient for large-scale learning. To address this, we propose a new geometry distribution model by two key techniques: (1) encoding distributions as 2D feature maps rather than network parameters, and (2) using SMPL models as the domain instead of Gaussian and refining the associated flow velocity field. We then design a generative framework adopting a two-staged training paradigm analogous to state-of-the-art image and 3D generative models.
In the first stage, we compress geometry distributions into a latent space using a diffusion flow model; the second stage trains another flow model on this latent space.
We validate our approach on two key tasks: pose-conditioned random avatar generation and avatar-consistent novel pose synthesis.
Experimental results demonstrate that our method outperforms existing state-of-the-art methods, achieving a 57% improvement in geometry quality.

**摘要翻译**:

逼真的人体几何生成是一项重要但具有挑战性的任务，既需要保留精细的服装细节，又需要准确建模服装与身体之间的交互。为应对这一挑战，我们基于几何分布——一种近期提出的表示方法，能够使用流匹配模型高保真地建模单个人体几何。然而，将单一几何分布扩展到整个数据集对于大规模学习而言既不简单也不高效。为此，我们通过两项关键技术提出了新的几何分布模型：（1）将分布编码为二维特征图而非网络参数；（2）使用 SMPL 模型作为域替代高斯分布，并细化相关的流速度场。随后，我们设计了一个生成框架，采用类似于最先进图像和3D生成模型的两阶段训练范式。在第一阶段，我们使用扩散流模型将几何分布压缩到潜在空间；第二阶段在此潜在空间上训练另一个流模型。我们在两项关键任务上验证了该方法：基于姿态条件的随机虚拟人生成和虚拟人一致的新姿态合成。实验结果表明，我们的方法优于现有最先进方法，几何质量提升了 57%。

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

---

## 208. RealPDEBench: A Benchmark for Complex Physical Systems with Real-World Data

**RealPDEBench：基于真实世界数据的复杂物理系统基准测试**

**OpenReview**: [https://openreview.net/forum?id=y3oHMcoItR](https://openreview.net/forum?id=y3oHMcoItR)

**Authors**: Peiyan Hu (Chinese Academy of Sciences), Haodong Feng (Westlake University), Hongyuan Liu (Westlake University), Tongtong Yan (Shanghai Jiaotong University), Wenhao Deng (University of Glasgow), Tianrun Gao (Fudan University), Rong Zheng (Peking University), Haoren Zheng (Shanghai Jiaotong University), Chenglei Yu (Westlake University), Chuanrui Wang (Westlake University), Kaiwen Li (Shanghai Jiao Tong University), Zhi-Ming Ma (Academy of Mathematics and Systems Science, Chinese Academy of Sciences, Chinese Academy of Sciences), Dezhi Zhou (Shanghai Jiao Tong University), Xingcai Lu (Shanghai Jiaotong University), Dixia Fan (Westlake University), Tailin Wu (Westlake University)

**Institutions**: Chinese Academy of Sciences, Westlake University, Shanghai Jiaotong University, University of Glasgow, Fudan University, Peking University, Shanghai Jiao Tong University, Academy of Mathematics and Systems Science, Chinese Academy of Sciences, Chinese Academy of Sciences

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: complex physical system, PDE, benchmark, real-world data, prediction

**TL;DR**: We propose the first benchmark for complex physical systems with paired real-world data and simulated data, and explore how to bridge simulated and real-world data.

**TL;DR翻译**: 我们提出了首个包含配对真实世界数据和仿真数据的复杂物理系统基准测试，并探索了如何弥合仿真数据与真实世界数据之间的差距。

**Abstract**:

Predicting the evolution of complex physical systems remains a central problem in science and engineering. Despite rapid progress in scientific Machine Learning (ML) models, a critical bottleneck is the lack of expensive real-world data, resulting in most current models being trained and validated on simulated data. Beyond limiting the development and evaluation of scientific ML, this gap also hinders research into essential tasks such as sim-to-real transfer. We introduce RealPDEBench, the first benchmark for scientific ML that integrates real-world measurements with paired numerical simulations. RealPDEBench consists of five datasets, three tasks, nine metrics, and ten baselines. We first present five real-world measured datasets with paired simulated datasets across different complex physical systems. We further define three tasks, which allow comparisons between real-world and simulated data, and facilitate the development of methods to bridge the two. Moreover, we design nine evaluation metrics, spanning data-oriented and physics-oriented metrics, and finally benchmark ten representative baselines, including state-of-the-art models, pretrained PDE foundation models, and a traditional method. Experiments reveal significant discrepancies between simulated and real-world data, while showing that pretraining with simulated data consistently improves both accuracy and convergence. In this work, we hope to provide insights from real-world data, advancing scientific ML toward bridging the sim-to-real gap and real-world deployment. Our benchmark, datasets, and instructions are available at https://realpdebench.github.io/.

**摘要翻译**:

预测复杂物理系统的演化仍然是科学与工程领域的核心问题。尽管科学机器学习（ML）模型取得了快速进展，但一个关键瓶颈在于昂贵的真实世界数据的匮乏，导致大多数现有模型在仿真数据上进行训练和验证。这一差距不仅限制了科学 ML 的开发和评估，还阻碍了仿真到真实（sim-to-real）迁移等关键任务的研究。我们引入了 RealPDEBench，这是首个将真实世界测量数据与配对数值模拟相结合的科学 ML 基准测试。RealPDEBench 包含五个数据集、三项任务、九个评估指标和十个基线方法。我们首先展示了跨不同复杂物理系统的五个真实世界测量数据集及其配对仿真数据集。进而定义了三项任务，支持真实世界数据与仿真数据之间的比较，并促进弥合两者差距的方法开发。此外，我们设计了九个评估指标，涵盖数据导向和物理导向的指标，最后对十个代表性基线方法进行了评测，包括最先进的模型、预训练的 PDE 基础模型和一种传统方法。实验揭示了仿真数据与真实世界数据之间的显著差异，同时表明使用仿真数据进行预训练能够持续改善精度和收敛性。我们希望通过本工作提供来自真实世界数据的洞见，推动科学 ML 朝着弥合仿真与真实差距和真实世界部署的方向发展。基准测试、数据集和使用说明已在 https://realpdebench.github.io/ 上发布。

---

## 209. Improving Diffusion Models for Class-imbalanced Training Data via Capacity Manipulation

**通过容量调控改进面向类不平衡训练数据的扩散模型**

**OpenReview**: [https://openreview.net/forum?id=wSGle6ag5I](https://openreview.net/forum?id=wSGle6ag5I)

**Authors**: Feng Hong (Shanghai Jiao Tong University), Jiangchao Yao, Yifei Shen (Microsoft Research Asia), Dongsheng Li (Microsoft Research Asia), Ya Zhang (Shanghai Jiao Tong University), Yanfeng Wang (Shanghai Jiao Tong University)

**Institutions**: Shanghai Jiao Tong University, Microsoft Research Asia

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Imbalance, Diffusion Models

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

While diffusion models have achieved remarkable performance in image generation, they often struggle with the imbalanced datasets frequently encountered in real-world applications, resulting in significant performance degradation on minority classes. In this paper, we identify model capacity allocation as a key and previously underexplored factor contributing to this issue, providing a perspective that is orthogonal to existing research. Our empirical experiments and theoretical analysis reveal that majority classes monopolize an unnecessarily large portion of the model's capacity, thereby restricting the representation of minority classes. To address this, we propose Capacity Manipulation (CM), which explicitly reserves model capacity for minority classes. Our approach leverages a low-rank decomposition of model parameters and introduces a capacity manipulation loss to allocate appropriate capacity for capturing minority knowledge, thus enhancing minority class representation. Extensive experiments demonstrate that CM consistently and significantly improves the robustness of diffusion models on imbalanced datasets, and when combined with existing methods, further boosts overall performance.

**摘要翻译**:

尽管扩散模型在图像生成方面取得了卓越的性能，但面对真实世界应用中常见的不平衡数据集时往往表现不佳，导致少数类上的性能显著下降。在本文中，我们将模型容量分配确定为导致这一问题的一个关键且此前未被充分探索的因素，提供了一个与现有研究正交的视角。我们的实证实验和理论分析表明，多数类占用了不必要的大量模型容量，从而限制了少数类的表示。为解决这一问题，我们提出了容量调控（CM）方法，显式地为少数类预留模型容量。我们的方法利用模型参数的低秩分解，并引入容量调控损失来为捕获少数类知识分配适当的容量，从而增强少数类的表示能力。大量实验表明，CM 持续且显著地提升了扩散模型在不平衡数据集上的鲁棒性，并且与现有方法结合使用时能够进一步提升整体性能。

---

## 210. SANA-Video: Efficient Video Generation with Block Linear Diffusion Transformer

**SANA-Video：基于分块线性 Diffusion Transformer 的高效视频生成**

**OpenReview**: [https://openreview.net/forum?id=mzAchylAtf](https://openreview.net/forum?id=mzAchylAtf)

**Authors**: Junsong Chen (University of Hong Kong), Yuyang Zhao (NVIDIA), Jincheng YU (NVIDIA), Ruihang Chu (Wan Team), Junyu Chen (Tsinghua University, Tsinghua University), Shuai Yang (The Hong Kong University of Science and Technology), Xianbang Wang (Tsinghua University), Yicheng Pan (Tsinghua University), Daquan Zhou (Bytedance), Huan Ling (NVIDIA), Haozhe Liu (King Abdullah University of Science and Technology), Hongwei Yi (Max Planck Institute for Intelligent Systems, Max-Planck Institute), Hao Zhang (NVIDIA Corporation), Muyang Li (Massachusetts Institute of Technology), Yukang Chen (NVIDIA), Han Cai (NVIDIA), Sanja Fidler (Department of Computer Science, University of Toronto), Ping Luo (The University of Hong Kong), Song Han, Enze Xie (NVIDIA Research)

**Institutions**: University of Hong Kong, NVIDIA, Wan Team, Tsinghua University, Tsinghua University, The Hong Kong University of Science and Technology, Tsinghua University, Bytedance, King Abdullah University of Science and Technology, Max Planck Institute for Intelligent Systems, Max-Planck Institute, NVIDIA Corporation, Massachusetts Institute of Technology, Department of Computer Science, University of Toronto, The University of Hong Kong, NVIDIA Research

**Primary Area**: generative models

**Keywords**: Video Diffusion Model

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

We introduce SANA-Video, a small diffusion model that can efficiently generate videos up to 720×1280 resolution and minute-length duration. SANA-Video synthesizes high-resolution, high-quality and long videos with strong text-video alignment at a remarkably fast speed, deployable on RTX 5090 GPU. Two core designs ensure our efficient, effective and long video generation:  (1) Linear DiT: We leverage linear attention as the core operation, which is more efficient than vanilla attention given the large number of tokens processed in video generation. (2) Constant-Memory KV cache for Block Linear Attention: we design block-wise autoregressive approach for long video generation by employing a constant-memory state, derived from the cumulative properties of linear attention. This KV cache provides the Linear DiT with global context at a fixed memory cost, eliminating the need for a traditional KV cache and enabling efficient, minute-long video generation. In addition, we explore effective data filters and model training strategies, narrowing the training cost to 12 days on 64 H100 GPUs, which is only 1\% of the cost of MovieGen. Given its low cost, SANA-Video achieves competitive performance compared to modern state-of-the-art small diffusion models (e.g., Wan 2.1-1.3B and SkyReel-V2-1.3B) while being 16x faster in measured latency. Moreover, SANA-Video can be deployed on RTX 5090 GPUs with NVFP4 precision, accelerating the inference speed of generating a 5-second 720p video from 71s to 29s (2.4x} speedup). In summary, SANA-Video enables low-cost, high-quality video generation. Code and model will be publicly released.

**摘要翻译**:

我们提出了 SANA-Video，一个能够高效生成最高 720×1280 分辨率、分钟级时长视频的小型扩散模型。SANA-Video 能够以极快的速度合成高分辨率、高质量且具有强文本-视频对齐能力的长视频，并可部署在 RTX 5090 GPU 上。两项核心设计确保了我们高效且有效的长视频生成能力：(1) Linear DiT：我们采用线性注意力作为核心运算，在视频生成所需处理的大量 token 场景下，其效率远优于标准注意力机制。(2) 分块线性注意力的常量内存 KV 缓存：我们设计了一种分块式自回归方法用于长视频生成，利用线性注意力的累积特性维护一个常量内存状态。该 KV 缓存以固定的内存开销为 Linear DiT 提供全局上下文，消除了对传统 KV 缓存的需求，从而实现了高效的分钟级视频生成。此外，我们探索了有效的数据过滤策略和模型训练方案，将训练成本缩减至在 64 块 H100 GPU 上 12 天，仅为 MovieGen 成本的 1%。在如此低成本下，SANA-Video 在与现代先进小型扩散模型（如 Wan 2.1-1.3B 和 SkyReel-V2-1.3B）的对比中表现出具有竞争力的性能，同时在实测延迟上快 16 倍。此外，SANA-Video 可以使用 NVFP4 精度部署在 RTX 5090 GPU 上，将生成 5 秒 720p 视频的推理速度从 71 秒加速至 29 秒（2.4 倍加速）。总而言之，SANA-Video 实现了低成本、高质量的视频生成。代码和模型将公开发布。

---

## 211. Stable Video Infinity: Infinite-Length Video Generation with Error Recycling

**Stable Video Infinity：基于误差循环利用的无限长度视频生成**

**OpenReview**: [https://openreview.net/forum?id=X96Ei9n34a](https://openreview.net/forum?id=X96Ei9n34a)

**Authors**: Wuyang Li (EPFL - EPF Lausanne), Wentao Pan (Chinese University of Hong Kong), Po-Chien Luan (EPFL - EPF Lausanne), Yang Gao (EPFL - EPF Lausanne), Alexandre Alahi (EPFL)

**Institutions**: EPFL - EPF Lausanne, Chinese University of Hong Kong, EPFL

**Primary Area**: generative models

**Keywords**: Infinite-Length Video Generation, Error Accumulation

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

We propose **Stable Video Infinity (SVI)** that can generate non-looping, ultra-long videos with stable visual quality, while supporting per-clip prompt control and multi-modal conditioning. While existing long-video methods attempt to _**mitigate accumulated errors**_ via handcrafted anti-drifting (e.g., modified noise scheduler, frame anchoring), they remain limited to single-prompt extrapolation, producing homogeneous scenes with repetitive motions. We identify that the fundamental challenge extends beyond error accumulation to a critical discrepancy between the training assumption (seeing clean data) and the test-time autoregressive reality (conditioning on self-generated, error-prone outputs). To bridge this hypothesis gap, SVI incorporates **Error-Recycling Fine-Tuning**, a new type of efficient training that recycles the Diffusion Transformer (DiT)'s self-generated errors into supervisory prompts, thereby encouraging DiT to _**actively identify and correct its own errors**_. This is achieved by injecting, collecting, and banking errors through closed-loop recycling, autoregressively learning from error-injected feedback. Specifically, we (i) inject historical errors made by DiT to intervene on clean inputs, simulating error-accumulated trajectories in flow matching; (ii) efficiently approximate predictions with one-step bidirectional integration and calculate errors with residuals; (iii) dynamically bank errors into replay memory across discretized timesteps, which are resampled for new input. SVI is able to scale videos from seconds to infinite durations with no additional inference cost, while remaining compatible with diverse conditions (e.g., audio, skeleton, and text streams). We evaluate SVI on three benchmarks, including consistent, creative, and conditional settings, thoroughly verifying its versatility and state-of-the-art role.

**摘要翻译**:

我们提出了 **Stable Video Infinity (SVI)**，该方法能够生成无循环、超长时长且视觉质量稳定的视频，同时支持逐片段的提示词控制和多模态条件生成。现有的长视频生成方法试图通过手工设计的抗漂移策略（如修改噪声调度器、帧锚定等）来**缓解累积误差**，但它们仍局限于单提示词外推，只能生成场景单一、动作重复的内容。我们发现，根本挑战不仅在于误差累积，还在于训练假设（输入为干净数据）与测试时自回归现实（以自身生成的、含误差的输出为条件）之间的关键差异。为弥合这一假设鸿沟，SVI 引入了**误差循环微调（Error-Recycling Fine-Tuning）**，这是一种新型高效训练方式，将 Diffusion Transformer (DiT) 自身生成的误差循环利用为监督信号，从而引导 DiT **主动识别并纠正自身错误**。这一过程通过闭环循环的误差注入、收集和存储来实现，模型自回归地从注入误差的反馈中学习。具体而言，我们(i) 将 DiT 产生的历史误差注入到干净输入中进行干预，在流匹配中模拟误差累积的轨迹；(ii) 通过单步双向积分高效近似预测值，并通过残差计算误差；(iii) 将误差动态存储到跨离散化时间步的回放记忆中，并重新采样作为新的输入。SVI 能够将视频从秒级扩展到无限时长，且无需额外推理开销，同时兼容多种条件输入（如音频、骨架和文本流）。我们在三个基准测试上评估了 SVI，涵盖一致性、创意性和条件生成场景，全面验证了其多功能性和最先进水平。

---

## 212. Extending Sequence Length is Not All You Need: Effective Integration of Multimodal Signals for Gene Expression Prediction

**延长序列长度并非万能之策：多模态信号的有效整合用于基因表达预测**

**OpenReview**: [https://openreview.net/forum?id=wwPSfcf5Pj](https://openreview.net/forum?id=wwPSfcf5Pj)

**Authors**: Zhao Yang (Renmin University of China), Yi Duan (Renmin University of China), Jiwei Zhu (Renmin University of China), Ying Ba (Renmin University of China), Chuan Cao (Research, Microsoft), Bing Su (Renmin University of China)

**Institutions**: Renmin University of China, Research, Microsoft

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: dna language model, gene expression prediction, multimodal information integration, causal intervention

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

Gene expression prediction, which predicts mRNA expression levels from DNA sequences, presents significant challenges. Previous works often focus on extending input sequence length to locate distal enhancers, which may influence target genes from hundreds of kilobases away. Our work first reveals that for current models, long sequence modeling can decrease performance. Even carefully designed algorithms only mitigate the performance degradation caused by long sequences. Instead, we find that proximal multimodal epigenomic signals near target genes prove more essential. Hence we focus on how to better integrate these signals, which has been overlooked. We find that different signal types serve distinct biological roles, with some directly marking active regulatory elements while others reflect background chromatin patterns that may introduce confounding effects. Simple concatenation may lead models to develop spurious associations with these background patterns. To address this challenge, we propose Prism, a framework that learns multiple combinations of high-dimensional epigenomic features to represent distinct background chromatin states and uses backdoor adjustment to mitigate confounding effects. Our experimental results demonstrate that proper modeling of multimodal epigenomic signals achieves state-of-the-art performance using only short sequences for gene expression prediction.

**摘要翻译**:

基因表达预测，即从 DNA 序列预测 mRNA 表达水平，面临着重大挑战。以往的研究通常侧重于延长输入序列长度以定位远端增强子——这些增强子可能从数百千碱基之外影响目标基因。我们的工作首先揭示了一个重要发现：对于当前模型而言，长序列建模可能反而降低性能。即使经过精心设计的算法也只能缓解长序列带来的性能下降。相反，我们发现目标基因附近的近端多模态表观基因组信号更为关键。因此，我们专注于如何更好地整合这些被忽视的信号。我们发现不同类型的信号承担着不同的生物学角色：一些信号直接标记活跃的调控元件，而另一些则反映背景染色质模式，可能引入混杂效应。简单的拼接可能导致模型与这些背景模式建立虚假关联。为解决这一挑战，我们提出了 Prism 框架，该框架学习高维表观基因组特征的多种组合来表示不同的背景染色质状态，并使用后门调整（backdoor adjustment）来缓解混杂效应。实验结果表明，对多模态表观基因组信号进行合理建模，仅使用短序列即可在基因表达预测上达到最先进的性能。

---

## 213. MomaGraph: State-Aware Unified Scene Graphs with Vision-Language Models for Embodied Task Planning

**MomaGraph：基于视觉语言模型的状态感知统一场景图用于具身任务规划**

**OpenReview**: [https://openreview.net/forum?id=3eTr9dGwJv](https://openreview.net/forum?id=3eTr9dGwJv)

**Authors**: Yuanchen Ju (Tsinghua University, Tsinghua University), Yongyuan Liang (University of Maryland, College Park), Yen-Jen Wang (University of California, Berkeley), Gireesh Nandiraju (Peking University), Yuanliang Ju (University of Toronto), Seungjae Lee (University of Maryland, College Park), Qiao Gu (University of Toronto), Elvis Hsieh (University of California, Berkeley), Furong Huang (University of Maryland), Koushil Sreenath (University of California Berkeley)

**Institutions**: Tsinghua University, Tsinghua University, University of Maryland, College Park, University of California, Berkeley, Peking University, University of Toronto, University of Maryland, University of California Berkeley

**Primary Area**: applications to robotics, autonomy, planning

**Keywords**: Scene Graph, Task Planning, Spatial Understanding, Mobile Manipulation

**TL;DR**: We present MomaGraph, a dataset and benchmark for task-oriented scene graphs, and MomaGraph-R1, a 7B model that predicts graphs and plans tasks in a Graph-then-Plan framework.

**TL;DR翻译**: 我们提出了 MomaGraph，一个面向任务的场景图数据集和基准测试，以及 MomaGraph-R1，一个在"先建图后规划"框架下预测场景图并进行任务规划的 7B 模型。

**Abstract**:

Mobile manipulators in households must both navigate and manipulate. This requires a compact, semantically rich scene representation that captures where objects are, how they function, and which parts are actionable. Scene graphs are a natural choice, yet prior work often separates spatial and functional relations, treats scenes as static snapshots without object states or temporal updates, and overlooks information most relevant for accomplishing the current task. To overcome these shortcomings, we introduce MomaGraph, a unified scene representation for embodied agents that integrates spatial-functional relationships and part-level interactive elements. However, advancing such a representation requires both suitable data and rigorous evaluation, which have been largely missing. To address this, we construct MomaGraph-Scenes, the first large-scale dataset of richly annotated, task-driven scene graphs in household environments, and design MomaGraph-Bench, a systematic evaluation suite spanning six reasoning capabilities from high-level planning to fine-grained scene understanding. Built upon this foundation, we further develop MomaGraph-R1, a 7B vision–language model trained with reinforcement learning on MomaGraph-Scenes. MomaGraph-R1 predicts task-oriented scene graphs and serves as a zero-shot task planner under a Graph-then-Plan framework. Extensive experiments show that our model achieves state-of-the-art results among open-source models, reaching 71.6% accuracy on the benchmark (+11.4% over the best baseline), while generalizing across public benchmarks and transferring effectively to real-robot experiments. More visualizations and robot demonstrations are available at https://momagraph.github.io/.

**摘要翻译**:

家庭环境中的移动操作机器人需要同时具备导航和操作能力。这要求一种紧凑且语义丰富的场景表示，能够捕捉物体的位置、功能以及哪些部件可交互。场景图是一种自然的选择，但以往的工作往往将空间关系和功能关系分离处理，将场景视为不包含物体状态或时序更新的静态快照，并忽略了与完成当前任务最相关的信息。为克服这些不足，我们提出了 MomaGraph，一种面向具身智能体的统一场景表示，整合了空间-功能关系和部件级可交互元素。然而，推进这种表示需要合适的数据和严格的评估，而这方面此前一直较为缺乏。为此，我们构建了 MomaGraph-Scenes，这是首个在家庭环境中进行丰富标注的大规模任务驱动场景图数据集；同时设计了 MomaGraph-Bench，一个涵盖从高层规划到细粒度场景理解共六种推理能力的系统化评估套件。在此基础上，我们进一步开发了 MomaGraph-R1，一个在 MomaGraph-Scenes 上通过强化学习训练的 7B 视觉-语言模型。MomaGraph-R1 预测面向任务的场景图，并在"先建图后规划"（Graph-then-Plan）框架下作为零样本任务规划器。大量实验表明，我们的模型在开源模型中取得了最先进的结果，在基准测试上达到 71.6% 的准确率（比最佳基线高出 11.4%），同时在多个公开基准测试上表现出良好的泛化能力，并有效迁移到真实机器人实验中。更多可视化结果和机器人演示请访问 https://momagraph.github.io/。

---

## 214. Learning to See Before Seeing: Demystifying LLM Visual Priors from Language Pre-training

**先知后见：揭秘大语言模型语言预训练中的视觉先验**

**OpenReview**: [https://openreview.net/forum?id=pfw176o1YJ](https://openreview.net/forum?id=pfw176o1YJ)

**Authors**: Junlin Han (University of Oxford), Shengbang Tong (New York University), David Fan (Facebook AI Research), Yufan Ren (Facebook), Koustuv Sinha (Meta (FAIR)), Philip Torr (University of Oxford), Filippos Kokkinos (Meta AI)

**Institutions**: University of Oxford, New York University, Facebook AI Research, Facebook, Meta (FAIR), Meta AI

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLM pre-training, MLLMs, multi-modality

**TL;DR**: Explore and understand the visual priors within LLMs and thus build better MLLMs.

**TL;DR翻译**: 探索并理解 LLM 中的视觉先验，从而构建更好的 MLLM。

**Abstract**:

Large Language Models (LLMs), despite being trained on text alone, surprisingly develop rich visual priors. These priors allow latent visual capabilities to be unlocked for vision tasks with a relatively small amount of multimodal data, and to perform symbolic visual generation tasks without ever having seen an image. Through systematic analysis, we reveal that visual priors—the implicit, emergent knowledge about the visual world acquired during language pre-training—are composed of separable perception and reasoning priors with unique scaling trends and origins. We show that an LLM's latent visual reasoning ability is predominantly developed by pre-training on reasoning-centric data (\eg, code, math, academia) and scales progressively. This reasoning prior acquired from language pre-training is transferable and universally applicable to visual reasoning. In contrast, the perception prior emerges more diffusely from broad corpora, and perception ability is more sensitive to the vision encoder and visual instruction tuning data. In parallel, text describing the visual world proves crucial, though its performance impact saturates rapidly. Leveraging these insights, we propose a data-centric recipe for pre-training vision-aware LLMs and verify it in 1T token scale pre-training.  Our findings are grounded in over 100 controlled experiments consuming 500,000 GPU-hours, spanning the full MLLM construction pipeline—from LLM pre-training to visual alignment and supervised multimodal fine-tuning—across five model scales, a wide range of data categories and mixtures, and multiple adaptation setups. Along with our main findings, we also propose and investigate several hypotheses, and introduce a Multi-Level Existence Bench (MLE-Bench) to facilitate future research. Together, this work provides a new way of deliberately cultivating visual priors from language pre-training, paving the way for the next generation of multimodal LLMs.

We recommend a visit to our project page (https://junlinhan.github.io/projects/lsbs/) for an interactive reading.

**摘要翻译**:

大语言模型（LLM）尽管仅在文本上训练，却令人意外地发展出了丰富的视觉先验。这些先验使得潜在的视觉能力能够通过相对少量的多模态数据被激活用于视觉任务，甚至能在从未见过图像的情况下执行符号化视觉生成任务。通过系统性分析，我们揭示了视觉先验——即在语言预训练过程中获得的关于视觉世界的隐式涌现知识——由具有不同缩放趋势和来源的可分离的感知先验和推理先验组成。我们表明，LLM 的潜在视觉推理能力主要通过在以推理为中心的数据（如代码、数学、学术文献）上预训练而发展，并呈渐进式增长。这种从语言预训练中获得的推理先验具有可迁移性，普遍适用于视觉推理任务。相比之下，感知先验更广泛地从多样化语料中涌现，感知能力对视觉编码器和视觉指令微调数据更为敏感。与此同时，描述视觉世界的文本被证明至关重要，但其性能影响会迅速饱和。基于这些洞察，我们提出了一套面向数据的视觉感知 LLM 预训练方案，并在 1T token 规模的预训练中进行了验证。我们的发现建立在 100 多项消耗 50 万 GPU 小时的对照实验基础上，涵盖了完整的 MLLM 构建流程——从 LLM 预训练到视觉对齐和有监督多模态微调——跨越五种模型规模、多种数据类别和混合方案以及多种适配设置。除了主要发现外，我们还提出并验证了若干假说，并引入了 Multi-Level Existence Bench (MLE-Bench) 以推动未来研究。总之，这项工作提供了一种从语言预训练中有针对性地培养视觉先验的新途径，为下一代多模态 LLM 铺平了道路。

我们建议访问项目主页（https://junlinhan.github.io/projects/lsbs/）以获得交互式阅读体验。

---

## 215. Benchmarking Empirical Privacy Protection for Adaptations of Large Language Models

**大语言模型适配的经验性隐私保护基准评测**

**OpenReview**: [https://openreview.net/forum?id=jY7fAo9rfK](https://openreview.net/forum?id=jY7fAo9rfK)

**Authors**: Bartłomiej Marek (CISPA Helmholtz Center for Information Security), Lorenzo Rossi (CISPA Helmholtz Center for Information Security), Vincent Hanke (CISPA Helmholtz Center for Information Security), Xun Wang (CISPA Helmholtz Center for Information Security), Michael Backes, Franziska Boenisch, Adam Dziedzic

**Institutions**: CISPA Helmholtz Center for Information Security

**Primary Area**: datasets and benchmarks

**Keywords**: privacy, llm, adaptations, auditing, differential privacy

**TL;DR**: We benchmark various differential private adaptations for LLMs for their empirical privacy protection and find that it varies widely, depending on the adaptation method,

**TL;DR翻译**: 我们对 LLM 的各种差分隐私适配方法进行了经验性隐私保护的基准评测，发现其效果因适配方法不同而差异显著。

**Abstract**:

Recent work has applied differential privacy (DP) to adapt large language models (LLMs) for sensitive applications, offering theoretical guarantees. However, its practical effectiveness remains unclear, partly due to LLM pretraining, where overlaps and interdependencies with adaptation data can undermine privacy despite DP efforts. To analyze this issue in practice, we investigate privacy risks under DP adaptations in LLMs using state-of-the-art attacks such as robust membership inference and canary data extraction. We benchmark these risks by systematically varying the adaptation data distribution, from exact overlaps with pretraining data, through in-distribution (IID) cases, to entirely out-of-distribution (OOD) examples. Additionally, we evaluate how different adaptation methods and different privacy regimes impact the vulnerability. Our results show that distribution shifts strongly influence privacy vulnerability: the closer the adaptation data is to the pretraining distribution, the higher the practical privacy risk at the same theoretical guarantee, even without direct data overlap. We find that parameter-efficient fine-tuning methods, such as LoRA, achieve the highest empirical privacy protection for OOD data. Our benchmark identifies key factors for achieving practical privacy in DP LLM adaptation, providing actionable insights for deploying customized models in sensitive settings. Looking forward, we propose a structured framework for holistic privacy assessment beyond adaptation privacy, to identify and evaluate risks across the full pretrain-adapt pipeline of LLMs.

**摘要翻译**:

近期工作将差分隐私（DP）应用于大语言模型（LLM）的敏感场景适配，提供了理论保障。然而其实际有效性仍不明确，部分原因在于 LLM 的预训练过程中，适配数据与预训练数据之间的重叠和相互依赖可能削弱差分隐私的保护效果。为在实践中分析这一问题，我们使用最先进的攻击方法（如鲁棒成员推断攻击和金丝雀数据提取）研究了差分隐私适配下 LLM 的隐私风险。我们通过系统地改变适配数据的分布——从与预训练数据完全重叠，到同分布（IID）情况，再到完全分布外（OOD）样本——来对这些风险进行基准评测。此外，我们还评估了不同适配方法和不同隐私机制对脆弱性的影响。结果表明，分布偏移对隐私脆弱性具有强烈影响：在相同的理论保障下，适配数据越接近预训练分布，实际隐私风险越高，即使不存在直接的数据重叠也是如此。我们发现，参数高效微调方法（如 LoRA）在 OOD 数据上实现了最高的经验性隐私保护。我们的基准测试识别出了在差分隐私 LLM 适配中实现实际隐私保护的关键因素，为在敏感场景中部署定制化模型提供了可操作的见解。展望未来，我们提出了一个结构化的框架，用于超越适配隐私的全面隐私评估，以识别和评估 LLM 完整预训练-适配流程中的风险。

---

## 216. ScaleCUA: Scaling Open-Source Computer Use Agents with Cross-Platform Data

**ScaleCUA：利用跨平台数据扩展开源计算机使用智能体**

**OpenReview**: [https://openreview.net/forum?id=yBFUqdJFZn](https://openreview.net/forum?id=yBFUqdJFZn)

**Authors**: Zhaoyang Liu (Hong Kong University of Science and Technology), JingJing Xie (Xiamen University), Zichen Ding (Shanghai Artificial Intelligence Laboratory), Zehao Li (University of Science and Technology of China), Bowen Yang (University of Science and Technology of China), Zhenyu Wu (Shanghai Jiaotong University), Xuehui Wang (Shanghai Jiaotong University), Qiushi Sun (University of Hong Kong), Shi Liu (Shanghai Artificial Intelligence Laboratory), Weiyun Wang (Fudan University), Shenglong Ye (Shanghai AI Laboratory), Qingyun Li (Shanghai Artificial Intelligence Laboratory), Zeyue Tian (Hong Kong University of Science and Technology), Gen Luo (Shanghai Artificial Intelligence Laboratory), Xiangyu Yue (The Chinese University of Hong Kong), Biqing Qi (Shanghai Artificial Intelligence Laboratory), Kai Chen (Shanghai AI Laboratory), Bowen Zhou (Tsinghua University), Yu Qiao, Qifeng Chen (Hong Kong University of Science and Technology), Wenhai Wang (The Chinese University of Hong Kong)

**Institutions**: Hong Kong University of Science and Technology, Xiamen University, Shanghai Artificial Intelligence Laboratory, University of Science and Technology of China, Shanghai Jiaotong University, University of Hong Kong, Fudan University, Shanghai AI Laboratory, The Chinese University of Hong Kong, Tsinghua University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: GUI Agent, GUI Data Pipeline, Computer Use, Open Source

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

Vision-Language Models (VLMs) have enabled computer use agents (CUAs) that operate GUIs autonomously, showing great potential, yet progress is limited by the lack of large-scale, open-source computer use data and foundation models. In this work, we introduce ScaleCUA, a step toward scaling open-source CUAs. It offers a large-scale dataset spanning 6 operating systems and 3 task domains, built via a closed-loop pipeline uniting automated agents with human experts. Trained on this scaled-up data, ScaleCUA can operate seamlessly across platforms.  Specifically, it delivers strong gains over baselines (+26.6 on WebArena-Lite-v2, +10.7 on ScreenSpot-Pro) and sets new state-of-the-art results (94.4% on MMBench-GUI L1-Hard, 60.6% on OSWorld-G, 47.4% on WebArena-Lite-v2). These findings underscore the power of data-driven scaling for general-purpose computer use agents. We will release data, models, and code to advance future research.

**摘要翻译**:

视觉语言模型（VLM）催生了能够自主操作图形用户界面的计算机使用智能体（CUA），展现出巨大潜力，但其进展受限于大规模开源计算机使用数据和基础模型的匮乏。在这项工作中，我们提出了 ScaleCUA，朝着扩展开源 CUA 迈出了重要一步。它提供了一个涵盖 6 种操作系统和 3 个任务领域的大规模数据集，通过将自动化智能体与人类专家相结合的闭环流程构建而成。在这一扩展数据上训练的 ScaleCUA 能够无缝跨平台运行。具体而言，它在基线上取得了显著提升（WebArena-Lite-v2 上 +26.6，ScreenSpot-Pro 上 +10.7），并创造了新的最先进结果（MMBench-GUI L1-Hard 上 94.4%，OSWorld-G 上 60.6%，WebArena-Lite-v2 上 47.4%）。这些发现突显了数据驱动扩展对通用计算机使用智能体的强大推动力。我们将发布数据、模型和代码以推动未来研究。

---

## 217. Train-before-Test Harmonizes Language Model Rankings

**先训练后测试：统一语言模型排名**

**OpenReview**: [https://openreview.net/forum?id=ORv3SAzus1](https://openreview.net/forum?id=ORv3SAzus1)

**Authors**: Guanhua Zhang (Max Planck Institute for Intelligent Systems, Max-Planck Institute), Ricardo Dominguez-Olmedo (Max-Planck-Institute for Intelligent Systems, Max-Planck Institute), Moritz Hardt (Max-Planck-Institute for Intelligent Systems, Max-Planck Institute)

**Institutions**: Max Planck Institute for Intelligent Systems, Max-Planck Institute, Max-Planck-Institute for Intelligent Systems, Max-Planck Institute

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Evaluation, Large language model

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

Existing language model benchmarks provide contradictory model rankings, even for benchmarks that aim to capture similar skills. This dilemma of conflicting rankings hampers model selection, clouds model comparisons, and adds confusion to a growing ecosystem of competing models. In this paper, we take a different perspective on model comparison: instead of relying on out-of-the-box performance via direct evaluation, we compare model potential by providing each model with identical benchmark-specific fine-tuning before evaluation. We call this approach train-before-test. Our primary contribution is a comprehensive empirical evaluation of model potential across 24 benchmarks and 61 models. First, we demonstrate that model potential rankings obtained through train-before-test exhibit remarkable consistency across all benchmarks. Whereas traditional rankings demonstrate little external validity under direct evaluation, they enjoy a significant degree of external validity when applying train-before-test: model potential rankings transfer gracefully from one benchmark to another. Second, train-before-test restores the connection between perplexity and downstream task performance, lost under direct evaluation. Remarkably, even pre-finetuning perplexity of a base model predicts post-finetuning downstream performance, suggesting that ranking consistency reflects inherent model potential rather than fine-tuning artifacts. Finally, train-before-test reduces the model-score matrix to essentially rank one, indicating that model potential is dominated by one latent factor, uncovered by train-before-test. While direct evaluation remains useful for assessing deployment-ready performance, train-before-test provides a complementary lens for understanding achievable performance of models after adaptation.

**摘要翻译**:

现有的语言模型基准测试提供了相互矛盾的模型排名，即使这些基准测试旨在衡量相似的能力。这种排名冲突的困境阻碍了模型选择，使模型比较变得模糊，并在不断增长的竞争性模型生态系统中增加了混乱。在本文中，我们从不同的视角看待模型比较：不依赖于通过直接评估获得的开箱即用性能，而是通过在评估前对每个模型进行相同的基准特定微调来比较模型的潜力。我们将此方法称为"先训练后测试"（train-before-test）。我们的主要贡献是对 24 个基准测试和 61 个模型的模型潜力进行了全面的实证评估。首先，我们证明了通过先训练后测试获得的模型潜力排名在所有基准测试中展现出显著的一致性。传统排名在直接评估下几乎没有外部效度，而在应用先训练后测试时则具有显著的外部效度：模型潜力排名能够在不同基准测试之间良好迁移。其次，先训练后测试恢复了困惑度与下游任务性能之间在直接评估下丢失的联系。值得注意的是，即使基础模型微调前的困惑度也能预测微调后的下游性能，这表明排名一致性反映了模型的内在潜力，而非微调的伪影。最后，先训练后测试将模型-分数矩阵降至近似秩一，表明模型潜力由一个隐因子主导，而先训练后测试正是揭示了这一因子。虽然直接评估在评估部署就绪性能方面仍然有用，但先训练后测试为理解模型经适配后可达到的性能提供了一个互补的视角。

---

## 218. One for Two: A Unified Framework for Imbalanced Graph Classification via Dynamic Balanced Prototype

**一举两得：基于动态平衡原型的不平衡图分类统一框架**

**OpenReview**: [https://openreview.net/forum?id=MraQM41SNS](https://openreview.net/forum?id=MraQM41SNS)

**Authors**: Guanjun Wang (University of Science and Technology of China), Binwu Wang (University of Science and Technology of China), Jiaming Ma (University of Science and Technology of China), Zhengyang Zhou (University of Science and Technology of China), Pengkun Wang (University of Science and Technology of China), Xu Wang (University of Science and Technology of China), Yang Wang (University of Science and Technology of China)

**Institutions**: University of Science and Technology of China

**Primary Area**: learning on graphs and other geometries & topologies

**Keywords**: Graph classification; graph imbalance learning; graph neural networks; Graph data mining; long-tail learning

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

Graph Neural Networks (GNNs) have advanced graph classification, yet they remain vulnerable to graph-level imbalance, encompassing class imbalance and topological imbalance. To address both types of imbalance in a unified manner, we propose UniImb, a Unified framework for Imbalanced graph classification. Specifically, UniImb first captures multi-scale topological features and enhances data diversity via learnable personalized graph perturbations. It then employs a dynamic balanced prototype module to learn representative prototypes from graph instances, improving the quality of graph representations. Concurrently, a prototype load-balancing optimization term mitigates dominance by majority samples to equalize sample influence during training. We justify these design choices theoretically using the Information Bottleneck principle. Extensive experiments on 19 datasets-including a large-scale imbalanced air pollution graph dataset AirGraph released by us and 23 baselines demonstrate that UniImb has achieved dominant performance across various imbalanced scenarios. Our code is available at GitHub.

**摘要翻译**:

图神经网络（GNN）推动了图分类的发展，但仍容易受到图级不平衡的影响，包括类别不平衡和拓扑不平衡。为了以统一的方式同时解决这两种不平衡问题，我们提出了 UniImb，一个面向不平衡图分类的统一框架。具体而言，UniImb 首先捕获多尺度拓扑特征，并通过可学习的个性化图扰动增强数据多样性。随后，它采用动态平衡原型模块从图实例中学习代表性原型，提升图表示的质量。同时，原型负载均衡优化项缓解了多数样本的主导作用，以在训练过程中均衡样本影响力。我们利用信息瓶颈原理从理论上论证了这些设计选择的合理性。在 19 个数据集（包括我们发布的大规模不平衡空气污染图数据集 AirGraph）和 23 个基线方法上的大量实验表明，UniImb 在各种不平衡场景下均取得了领先性能。我们的代码已在 GitHub 上开源。

---

## 219. Veritas: Generalizable Deepfake Detection via Pattern-Aware Reasoning

**Veritas：基于模式感知推理的可泛化深度伪造检测**

**OpenReview**: [https://openreview.net/forum?id=5VXJPS1HoM](https://openreview.net/forum?id=5VXJPS1HoM)

**Authors**: Hao Tan (Institute of automation, Chinese Academy of Sciences), jun lan (AntGroup), Zichang Tan (Sangfor Technologies Inc.), Senyuan Shi (Institute of automation, Chinese academy of science), Ajian Liu (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Chuanbiao Song (Alibaba Group), Huijia Zhu (Ant Group), Weiqiang Wang (Ant Group), Jun Wan (Institute of automation, Chinese Academy of Sciences), Zhen Lei (Institute of Automation,  Chinese Academy of Sciences)

**Institutions**: Institute of automation, Chinese Academy of Sciences, AntGroup, Sangfor Technologies Inc., Institute of automation, Chinese academy of science, Institute of automation, Chinese academy of science, Chinese Academy of Sciences, Alibaba Group, Ant Group, Institute of Automation,  Chinese Academy of Sciences

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Deepfake Detection, MLLMs

**TL;DR**: We introduce a MLLM-based detector for transparent deepfake detection, along with a holistic dataset for deepfake detection.

**TL;DR翻译**: 我们提出了一种基于 MLLM 的可解释深度伪造检测器，以及一个全面的深度伪造检测数据集。

**Abstract**:

Deepfake detection remains a formidable challenge due to the evolving nature of fake content in real-world scenarios. However, existing benchmarks suffer from severe discrepancies from industrial practice, typically featuring homogeneous training sources and low-quality testing images, which hinder the practical usage of current detectors. To mitigate this gap, we introduce **HydraFake**, a dataset that contains diversified deepfake techniques and in-the-wild forgeries, along with rigorous training and evaluation protocol, covering unseen model architectures, emerging forgery techniques and novel data domains. Building on this resource, we propose **Veritas**, a multi-modal large language model (MLLM) based deepfake detector. Different from vanilla chain-of-thought (CoT), we introduce *pattern-aware reasoning* that involves critical patterns such as "planning" and "self-reflection" to emulate human forensic process. We further propose a two-stage training pipeline to seamlessly internalize such deepfake reasoning capacities into current MLLMs. Experiments on HydraFake dataset reveal that although previous detectors show great generalization on cross-model scenarios, they fall short on unseen forgeries and data domains. Our Veritas achieves significant gains across different out-of-domain (OOD) scenarios, and is capable of delivering transparent and faithful detection outputs.

**摘要翻译**:

深度伪造检测因真实场景中伪造内容的不断演变而仍是一项艰巨挑战。然而，现有基准测试与工业实践存在严重脱节，通常表现为训练来源同质化和测试图像质量低下，阻碍了当前检测器的实际应用。为弥合这一差距，我们引入了 **HydraFake**，一个包含多样化深度伪造技术和真实环境伪造样本的数据集，以及严格的训练和评估协议，涵盖未见过的模型架构、新兴伪造技术和新数据领域。在此资源基础上，我们提出了 **Veritas**，一个基于多模态大语言模型（MLLM）的深度伪造检测器。与普通的思维链（CoT）不同，我们引入了*模式感知推理*，融入了"规划"和"自我反思"等关键模式以模拟人类取证过程。我们进一步提出了一个两阶段训练流程，将这种深度伪造推理能力无缝内化到当前的 MLLM 中。在 HydraFake 数据集上的实验表明，虽然以往的检测器在跨模型场景中展现出良好的泛化能力，但在未见过的伪造方法和数据领域上表现不佳。我们的 Veritas 在不同的分布外（OOD）场景中取得了显著提升，并能够提供透明且忠实的检测输出。

---

## 220. Semi-Supervised Preference Optimization with Limited Feedback

**有限反馈下的半监督偏好优化**

**OpenReview**: [https://openreview.net/forum?id=ghwxbTx7do](https://openreview.net/forum?id=ghwxbTx7do)

**Authors**: Seonggyun Lee (Yonsei University), Sungjun Lim (Yonsei University), Seojin Park (Yonsei University), Soeun Cheon (Korea Advanced Institute of Science & Technology), Kyungwoo Song (Yonsei University)

**Institutions**: Yonsei University, Korea Advanced Institute of Science & Technology

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Preference Optimization, Semi-Supervised Learning

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

The field of preference optimization has made outstanding contributions to the alignment of language models with human preferences. Despite these advancements, recent methods still rely heavily on substantial paired (labeled) feedback data, leading to substantial resource expenditures. To address these challenges, we study the problem of Semi-Supervised Preference Optimization in which the idea is to learn from both a small number of pairwise preference labels and a large pool of unpaired samples simultaneously. Our key theoretical contribution proves the existence of an optimal reward threshold capable of separating winning and losing responses with high probability, which enables a principled pseudo-labeling of unpaired data. By leveraging these pseudo-labels, SSPO effectively distills latent preferences from large-scale unpaired data, thus maintaining human alignment while drastically reducing acquisition costs. Extensive experiments across datasets validate this remarkable data efficiency; for instance, SSPO trained with Mistral-7B-Instruct on just 1% of UltraFeedback consistently surpasses strong baselines trained on 10% of UltraFeedback.

**摘要翻译**:

偏好优化领域在将语言模型与人类偏好对齐方面做出了杰出贡献。尽管取得了这些进展，近期方法仍然严重依赖大量的成对（标注）反馈数据，导致巨大的资源消耗。为应对这些挑战，我们研究了半监督偏好优化问题，其核心思想是同时从少量成对偏好标签和大量未配对样本中学习。我们的关键理论贡献证明了一个最优奖励阈值的存在性，该阈值能够以高概率区分优选和劣选响应，从而实现对未配对数据的有原则的伪标签标注。通过利用这些伪标签，SSPO 有效地从大规模未配对数据中蒸馏出潜在偏好，在大幅降低获取成本的同时保持了人类对齐。跨数据集的大量实验验证了这一显著的数据效率；例如，使用 Mistral-7B-Instruct 仅在 UltraFeedback 的 1% 数据上训练的 SSPO，就持续超越了在 UltraFeedback 10% 数据上训练的强基线方法。

---

## 221. Locality-aware Parallel Decoding for Efficient Autoregressive Image Generation

**局部感知并行解码：面向高效自回归图像生成**

**OpenReview**: [https://openreview.net/forum?id=h06l9w1clt](https://openreview.net/forum?id=h06l9w1clt)

**Authors**: Zhuoyang Zhang (Massachusetts Institute of Technology), Luke J. Huang (Massachusetts Institute of Technology), Chengyue Wu (The University of Hong Kong), Shang Yang (Massachusetts Institute of Technology), Kelly Peng (Stanford University), Yao Lu (Physical Intelligence), Song Han

**Institutions**: Massachusetts Institute of Technology, The University of Hong Kong, Stanford University, Physical Intelligence

**Primary Area**: generative models

**Keywords**: Efficient Autoregressive Image Generation, Parallel Decoding

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

We present Locality-aware Parallel Decoding (LPD) to accelerate autoregressive image generation. Traditional autoregressive image generation relies on next-patch prediction, a memory-bound process that leads to high latency. Existing works have tried to parallelize next-patch prediction by shifting to multi-patch prediction to accelerate the process, but only achieved limited parallelization. To achieve high parallelization while maintaining generation quality, we introduce two key techniques: (1) Flexible Parallelized Autoregressive Modeling, a novel architecture that enables arbitrary generation ordering and degrees of parallelization. It uses learnable position query tokens to guide generation at target positions while ensuring mutual visibility among concurrently generated tokens for consistent parallel decoding. (2) Locality-aware Generation Ordering, a novel schedule that forms groups to minimize intra-group dependencies and maximize contextual support, enhancing generation quality. With these designs, we reduce the generation steps from 256 to 20 (256×256 res.) and 1024 to 48 (512×512 res.) without compromising quality on the ImageNet class-conditional generation, and achieving at least 3.4× lower latency than previous parallelized autoregressive models.

**摘要翻译**:

我们提出了局部感知并行解码（Locality-aware Parallel Decoding, LPD）来加速自回归图像生成。传统的自回归图像生成依赖于逐块预测，这是一个受内存带宽限制的过程，导致高延迟。现有工作尝试通过转向多块预测来并行化逐块预测过程以加速生成，但仅实现了有限的并行化。为了在保持生成质量的同时实现高度并行化，我们引入了两项关键技术：(1) 灵活并行化自回归建模，一种新颖的架构，支持任意生成顺序和并行化程度。它使用可学习的位置查询 token 来引导目标位置的生成，同时确保并行生成的 token 之间的相互可见性，以实现一致的并行解码。(2) 局部感知生成排序，一种新颖的调度策略，通过分组来最小化组内依赖并最大化上下文支持，从而提升生成质量。通过这些设计，我们在 ImageNet 类条件生成任务上将生成步数从 256 减少到 20（256×256 分辨率）以及从 1024 减少到 48（512×512 分辨率），且不损失质量，并且延迟至少比之前的并行化自回归模型低 3.4 倍。

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

---

## 223. Half-order Fine-Tuning for Diffusion Model: A Recursive Likelihood Ratio Optimizer

**扩散模型的半阶微调：一种递归似然比优化器**

**OpenReview**: [https://openreview.net/forum?id=AZ6lqcvHLX](https://openreview.net/forum?id=AZ6lqcvHLX)

**Authors**: Tao Ren (Peking University), Zishi Zhang (Peking University), Jinyang Jiang (Peking University), Zehao Li (Peking University), Shentao Qin (Tsinghua University, Tsinghua University), Yi Zheng (Peking University), Guanghao Li (Tsinghua University, Tsinghua University), Qianyou Sun (Peking University), Yan Li, Jiafeng Liang (Harbin Institute of Technology), Xinping Li (Peking University), Yijie Peng (Peking University)

**Institutions**: Peking University, Tsinghua University, Tsinghua University, Harbin Institute of Technology

**Primary Area**: generative models

**Keywords**: perturbation-based gradient estimation, diffusion model, post-training

**TL;DR**:

**TL;DR翻译**:

**Abstract**:

The probabilistic diffusion model (DM), generating content by inferencing through a recursive chain structure, has emerged as a powerful framework for visual generation. After pre-training on enormous data, the model needs to be properly aligned to meet requirements for downstream applications. How to efficiently align the foundation DM is a crucial task. Contemporary methods are either based on Reinforcement Learning (RL) or truncated Backpropagation (BP). However, RL and truncated BP suffer from low sample efficiency and biased gradient estimation, respectively, resulting in limited improvement or, even worse, complete training failure. To overcome the challenges, we propose the Recursive Likelihood Ratio (RLR) optimizer, a Half-Order (HO) fine-tuning paradigm for DM. The HO gradient estimator enables the computation graph rearrangement within the recursive diffusive chain, making the RLR's gradient estimator **an unbiased one with lower variance** than other methods. We theoretically investigate the bias, variance, and convergence of our method. Extensive experiments are conducted on image and video generation to validate the superiority of the RLR. Furthermore, we propose a novel prompt technique that is natural for the RLR to achieve a synergistic effect. The implementation is available at https://github.com/RTkenny/RLR-Optimizer.

**摘要翻译**:

概率扩散模型（DM）通过递归链式结构进行推理生成内容，已成为视觉生成的强大框架。在海量数据上预训练后，模型需要经过适当的对齐以满足下游应用的需求。如何高效地对齐基础扩散模型是一项关键任务。当前方法要么基于强化学习（RL），要么基于截断反向传播（BP）。然而，RL 和截断 BP 分别受限于低样本效率和有偏梯度估计，导致改进有限，甚至可能出现训练完全失败的情况。为克服这些挑战，我们提出了递归似然比（Recursive Likelihood Ratio, RLR）优化器，一种面向扩散模型的半阶（Half-Order, HO）微调范式。半阶梯度估计器支持在递归扩散链中重新排列计算图，使得 RLR 的梯度估计器成为**无偏且比其他方法方差更低**的估计器。我们从理论上分析了该方法的偏差、方差和收敛性。在图像和视频生成上进行了大量实验，验证了 RLR 的优越性。此外，我们提出了一种与 RLR 天然契合的新型提示技术，以实现协同效果。实现代码可在 https://github.com/RTkenny/RLR-Optimizer 获取。

---

