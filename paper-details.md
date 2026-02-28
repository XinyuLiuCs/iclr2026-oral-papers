# ICLR 2026 Oral Papers - Full Details

Total: 223 papers

Source: https://openreview.net/group?id=ICLR.cc/2026/Conference#tab-accept-oral

---

## 1. Common Corpus: The Largest Collection of Ethical Data for LLM Pre-Training

**OpenReview**: [https://openreview.net/forum?id=0wSlFpMsGb](https://openreview.net/forum?id=0wSlFpMsGb)

**Authors**: Pierre-Carl Langlais (Pleias), Pavel Chizhov (Technical University of Applied Sciences Würzburg-Schweinfurt), Catherine Arnett (EleutherAI), Carlos Rosas Hinostroza (Université Sorbonne-Nouvelle (Paris III)), Mattia Nee (pleias), Eliot Krzysztof Jones (Gray Swan), Irène Girard (Université Gustave Eiffel), David Mach (Institut d'Etudes Politiques de Paris (Sciences Po)), Anastasia Stasenko (Sorbonne Université - Faculté des Sciences (Paris VI)), Ivan P. Yamshchikov (Technical University of Applied Sciences Würzburg-Schweinfurt)

**Institutions**: Pleias, Technical University of Applied Sciences Würzburg-Schweinfurt, EleutherAI, Université Sorbonne-Nouvelle (Paris III), pleias, Gray Swan, Université Gustave Eiffel, Institut d'Etudes Politiques de Paris (Sciences Po), Sorbonne Université - Faculté des Sciences (Paris VI)

**Primary Area**: datasets and benchmarks

**Keywords**: dataset, pre-training, large language models, open data, open science, multilingual

**TL;DR**: We assemble and release the largest truly open multilingual dataset for LLM pre-training consisting of 2 trillion tokens

**Abstract**: Large Language Models (LLMs) are pre-trained on large data from different sources and domains. These data most often contain trillions of tokens with large portions of copyrighted or proprietary content, which hinders the usage of such models under AI legislation. This raises the need for truly open pre-training data that is compliant with the data security regulations. In this paper, we introduce Common Corpus, the largest open dataset for LLM pre-training. The data assembled in Common Corpus are either uncopyrighted or under permissible licenses and amount to about two trillion tokens. The dataset contains a wide variety of languages, ranging from the high-resource European languages to some low-resource languages rarely represented in pre-training datasets. In addition, it includes a large portion of code data. The diversity of data sources in terms of covered domains and time periods opens up the paths for both research and entrepreneurial needs in diverse areas of knowledge. In this paper, we present the detailed provenance of data assembling and the details of dataset filtering and curation. We train two small language models on Common Corpus and find that the resulting model performs comparably to other models of their size, indicating that our dataset is suitable for multilingual pretraining. Common Corpus represents a key contribution to the ecosystem for open science research on large language models.

---

## 2. Q-RAG: Long Context Multi‑Step Retrieval via Value‑Based Embedder Training

**OpenReview**: [https://openreview.net/forum?id=MS9nWFY7LG](https://openreview.net/forum?id=MS9nWFY7LG)

**Authors**: Artyom Sorokin (My own research), Nazar Buzun (Innopolis University), Aleksandr Anokhin (My own research), Egor KONSTANTINOVICH VEDERNIKOV (Idependent), Petr Anokhin (Lomonosov Moscow State University), Mikhail Burtsev (London Institute for Mathematical Sciences), Evgeny Burnaev (Applied AI Institute)

**Institutions**: My own research, Innopolis University, Idependent, Lomonosov Moscow State University, London Institute for Mathematical Sciences, Applied AI Institute

**Primary Area**: reinforcement learning

**Keywords**: Reinforcement Learning, RL, QA, Long-context, RAG, NLP

**Abstract**: Retrieval-Augmented Generation (RAG) methods enhance LLM performance by efficiently filtering relevant context for LLMs, reducing hallucinations and inference cost.
However, most existing RAG methods focus on single-step retrieval, which is often insufficient for answering complex questions that require multi-step search.
Recently, multi-step retrieval approaches have emerged, typically involving the fine-tuning of small LLMs to perform multi-step retrieval.
However, this type of fine-tuning is highly resource-intensive and does not enable the use of larger LLMs.
In this work, we propose Q-RAG, a novel approach that fine-tunes the Embedder model for multi-step retrieval using reinforcement learning (RL).
Q-RAG offers a competitive, resource-efficient alternative to existing multi-step retrieval methods for open-domain question answering and achieves state-of-the-art results on the popular long-context benchmarks Babilong and RULER for contexts up to 10M tokens.

---

## 3. From movement to cognitive maps: recurrent neural networks reveal how locomotor development shapes hippocampal spatial coding

**OpenReview**: [https://openreview.net/forum?id=8bM7MkxJee](https://openreview.net/forum?id=8bM7MkxJee)

**Authors**: Marco P Abrate (University College London, University of London), Laurenz Muessig (University College London, University of London), Joshua P Bassett (University College London, University of London), Hui Min Tan (Animal Concerns Research & Education Society), Francesca Cacucci (University College London, University of London), Thomas Joseph Wills (University College London, University of London), Caswell Barry (University College London)

**Institutions**: University College London, University of London, Animal Concerns Research & Education Society, University College London

**Primary Area**: applications to neuroscience & cognitive science

**Keywords**: recurrent neural network, spatial representations, hippocampus, development, locomotion, rats

**Abstract**: The hippocampus contains neurons whose firing correlates with an animal's location and orientation in space. Collectively, these neurons are held to support a cognitive map of the environment, enabling the recall of and navigation to specific locations. Although recent studies have characterised the timelines of spatial neuron development, no unifying mechanistic model has yet been proposed. Moreover, the processes driving the emergence of spatial representations in the hippocampus remain unclear (Tan et al., 2017). Here, we combine computational analysis of postnatal locomotor development with a recurrent neural network (RNN) model of hippocampal function to demonstrate how changes in movement statistics -- and the resulting sensory experiences -- shape the formation of spatial tuning. First, we identify distinct developmental stages in rat locomotion during open-field exploration using published experimental data. Then, we train shallow RNNs to predict upcoming visual stimuli from concurrent visual and vestibular inputs, exposing them to trajectories that reflect progressively maturing locomotor patterns. Our findings reveal that these changing movement statistics drive the sequential emergence of spatially tuned units, mirroring the developmental timeline observed in rats. The models generate testable predictions about how spatial tuning properties mature -- predictions we confirm through analysis of hippocampal recordings. Critically, we demonstrate that replicating the specific statistics of developmental locomotion -- rather than merely accelerating sensory change -- is essential for the emergence of an allocentric spatial representation. These results establish a mechanistic link between embodied sensorimotor experience and the ontogeny of hippocampal spatial neurons, with significant implications for neurodevelopmental research and predictive models of navigational brain circuits.

---

## 4. FIRE: Frobenius-Isometry Reinitialization for Balancing the Stability–Plasticity Tradeoff

**OpenReview**: [https://openreview.net/forum?id=CfZLxT3zIZ](https://openreview.net/forum?id=CfZLxT3zIZ)

**Authors**: Isaac Han (Gwangju Institute of Science and Technology), Sangyeon Park (Gwangju Institute of Science and Technology), Seungwon Oh (Gwangju Institute of Science and Technology), Donghu Kim (Korea Advanced Institute of Science & Technology), Hojoon Lee (Krafton AI), KyungJoong Kim (Gwangju Institute of Science and Technology)

**Institutions**: Gwangju Institute of Science and Technology, Korea Advanced Institute of Science & Technology, Krafton AI

**Primary Area**: transfer learning, meta learning, and lifelong learning

**Keywords**: stability-plasticity tradeoff, continual learning

**TL;DR**: We present FIRE, a principled reinitialization approach that balances stability and plasticity through constrained optimization.

**Abstract**: Deep neural networks trained on nonstationary data must balance stability (i.e., retaining prior knowledge) and plasticity (i.e., adapting to new tasks). Standard reinitialization methods, which reinitialize weights toward their original values, are widely used but difficult to tune: conservative reinitializations fail to restore plasticity, while aggressive ones erase useful knowledge. We propose FIRE, a principled reinitialization method that explicitly balances the stability–plasticity tradeoff. FIRE quantifies stability through Squared Frobenius Error (SFE), measuring proximity to past weights, and plasticity through Deviation from Isometry (DfI), reflecting weight isotropy. The reinitialization point is obtained by solving a constrained optimization problem, minimizing SFE subject to DfI being zero, which is efficiently approximated by Newton–Schulz iteration. FIRE is evaluated on continual visual learning (CIFAR-10 with ResNet-18), language modeling (OpenWebText with GPT-0.1B), and reinforcement learning (HumanoidBench with SAC and Atari games with DQN). Across all domains, FIRE consistently outperforms both naive training without intervention and standard reinitialization methods, demonstrating effective balancing of the stability–plasticity tradeoff.

---

## 5. Exchangeability of GNN Representations  with Applications to Graph Retrieval

**OpenReview**: [https://openreview.net/forum?id=HQcCd0laFq](https://openreview.net/forum?id=HQcCd0laFq)

**Authors**: Kartik Nair (Carnegie Mellon University), Indradyumna Roy (Indian Institute of Technology Bombay), Soumen Chakrabarti (Indian Institute of Technology Bombay), Anirban Dasgupta (IIT Gandhinagar), Abir De (Indian Institute of Technology Bombay,)

**Institutions**: Carnegie Mellon University, Indian Institute of Technology Bombay, IIT Gandhinagar, Indian Institute of Technology Bombay,

**Primary Area**: learning on graphs and other geometries & topologies

**Keywords**: GNN, Locality sensitive hashing

**TL;DR**: It shows that graph representations are exchangeable random variables which can help in LSH in graphs

**Abstract**: In this work, we discover a probabilistic symmetry, called as exchangeability in graph neural networks (GNNs). Specifically, we show that the trained node embedding computed using a large family of graph neural networks, learned under standard optimization tools,  are exchangeable random variables. This implies that the probability density of the node embeddings remains invariant with respect to a permutation applied on their dimension axis. This results in identical distribution across the elements of the graph representations.  Such a property enables approximation of transportation-based graph similarities by Euclidean similarities between order statistics. Leveraging this reduction, we propose a unified locality-sensitive hashing (LSH) framework that supports diverse relevance measures, including subgraph matching and graph edit distance. Experiments show that our method helps to do LSH more effectively than baselines.

---

## 6. Enhancing Generative Auto-bidding with Offline Reward Evaluation and Policy Search

**OpenReview**: [https://openreview.net/forum?id=kMuQBgPIdg](https://openreview.net/forum?id=kMuQBgPIdg)

**Authors**: Zhiyu Mou (Alibaba Group), Yiqin Lv (National University of Defense Technology), Miao Xu (Alibaba Group), Cheems Wang (Tsinghua University), Yixiu Mao (Tsinghua University), Jinghao Chen (Tsinghua University), Qichen Ye (Alibaba Group), Chao Li (Chinese academic of science), Rongquan Bai (Alibaba Group), Chuan Yu (Alibaba Group), Jian Xu (Alibaba Group), Bo Zheng (Alibaba Group)

**Institutions**: Alibaba Group, National University of Defense Technology, Tsinghua University, Chinese academic of science

**Primary Area**: applications to robotics, autonomy, planning

**Keywords**: auto-bidding, offline reinforcement learning, generative decision making

**Abstract**: Auto-bidding serves as a critical tool for advertisers to improve their advertising performance. Recent progress has demonstrated that AI-Generated Bidding (AIGB), which learns a conditional generative planner from offline data, achieves superior performance compared to typical offline reinforcement learning (RL)-based auto-bidding methods. However, existing AIGB methods still face a performance bottleneck due to their inherent inability to explore beyond the static offline dataset. To address this, we propose AIGB-Pearl (Planning with EvaluAtor via RL),  a novel method that integrates generative planning and policy optimization. The core of AIGB-Pearl lies in constructing a trajectory evaluator for scoring generation quality and designing a provably sound KL-Lipschitz-constrained score maximization scheme to ensure safe and efficient generalization beyond the offline dataset. A practical algorithm incorporating the synchronous coupling technique is further devised to ensure the model regularity required by the proposed scheme. Extensive experiments on both simulated and real-world advertising systems demonstrate the state-of-the-art performance of our approach.

---

## 7. Why DPO is a Misspecified Estimator and How to Fix It

**OpenReview**: [https://openreview.net/forum?id=btEiAfnLsX](https://openreview.net/forum?id=btEiAfnLsX)

**Authors**: Aditya Gopalan (Indian Institute of Science), Sayak Ray Chowdhury (Indian Institute of Technology, Kanpur), Debangshu Banerjee (Indian Institute of Science)

**Institutions**: Indian Institute of Science, Indian Institute of Technology, Kanpur

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Direct Preference Optimization, Reinforcement Learning, Reinforcement learning with human feedback

**TL;DR**: DPO is not sound by design and can fail due to misspecification, we fix it with careful analysis.

**Abstract**: Direct alignment algorithms such as Direct Preference Optimization (DPO) fine-tune models based on preference data, using only supervised learning instead of two-stage reinforcement learning with human feedback (RLHF). We show that DPO encodes a statistical estimation problem over reward functions induced by a parametric policy class. When the true reward function that generates preferences cannot be realized via the policy class, DPO becomes misspecified, resulting in failure modes such as preference order reversal, worsening of policy reward, and high sensitivity to the input preference data distribution. On the other hand, we study the local behavior of two-stage RLHF for a parametric class and relate it to a natural gradient step in policy space.  Our fine-grained geometric characterization allows us to propose AuxDPO, which introduces additional auxiliary variables in the DPO loss function to help move towards the RLHF solution in a principled manner and mitigate the misspecification in DPO. We empirically demonstrate the superior performance of AuxDPO on didactic bandit settings as well as LLM alignment tasks.

---

## 8. WebDevJudge: Evaluating (M)LLMs as Critiques for Web Development Quality

**OpenReview**: [https://openreview.net/forum?id=CCSPm6V5EF](https://openreview.net/forum?id=CCSPm6V5EF)

**Authors**: Chunyang Li (Department of Computer Science and Engineering, Hong Kong University of Science and Technology), Yilun Zheng (Nanyang Technological University), Xinting Huang (Tencent), Tianqing Fang (Tencent AI Lab), Jiahao Xu (Tencent AI Lab), Lihui Chen (Nanyang Technological University), Yangqiu Song (Hong Kong University of Science and Technology), Han Hu (Tencent Hunyuan Research)

**Institutions**: Department of Computer Science and Engineering, Hong Kong University of Science and Technology, Nanyang Technological University, Tencent, Tencent AI Lab, Hong Kong University of Science and Technology, Tencent Hunyuan Research

**Primary Area**: datasets and benchmarks

**Keywords**: large language models, evaluation, LLM-as-a-judge, benchmark

**TL;DR**: A meta-evaluation benchmark for assessing LLM-as-a-judge in the context of web development.

**Abstract**: The paradigm of LLM-as-a-judge is emerging as a scalable and efficient alternative to human evaluation, demonstrating strong performance on well-defined tasks. However, its reliability in open-ended tasks with dynamic environments and complex interactions remains unexplored. To bridge the gap, we introduce WebDevJudge, a systematic benchmark for assessing LLM-as-a-judge performance in web development, with support for both non-interactive evaluation based on static observations and continuous interactive evaluation with a dynamic web environment. WebDevJudge comprises human preference labels over paired web implementations, annotated with structured and query-grounded rubrics to ensure high-quality ground truth. Using this benchmark, we comprehensively evaluate various evaluators, including LLMs, MLLMs, and agentic workflows. We systematically investigate the impact of different paradigms and guidance mechanisms. Our experiments reveal a significant gap between LLM judges and human experts. In-depth analysis indicates this gap stems from fundamental model limitations, including failures in recognizing functional equivalence, verifying task feasibility, and mitigating bias. Overall, WebDevJudge presents a significant challenge to LLM-as-a-judge, offering insights to guide future research toward developing more reliable and capable automated evaluators for complicated scenarios.

---

## 9. SafeDPO: A Simple Approach to Direct Preference Optimization with Enhanced Safety

**OpenReview**: [https://openreview.net/forum?id=PJdw4VBsXD](https://openreview.net/forum?id=PJdw4VBsXD)

**Authors**: Geon-Hyeong Kim (LG AI Research), Youngsoo Jang (Ulsan National Institute of Science and Technology), Yu Jin Kim (LG AI Research), Byoungjip Kim (LG AI Research), Honglak Lee (University of Michigan - Ann Arbor), Kyunghoon Bae (LG AI Research), Moontae Lee (LG Corporation)

**Institutions**: LG AI Research, Ulsan National Institute of Science and Technology, University of Michigan - Ann Arbor, LG Corporation

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Safety Alignment, LLM Fine-tuning, Preferences, Large Language Models, AI Safety

**TL;DR**: This work introduces a simple yet principled approach for directly optimizing the safety alignment objective during policy learning

**Abstract**: As Large Language Models (LLMs) are increasingly deployed in real-world applications, balancing both helpfulness and safety has become a central challenge. A natural approach is to incorporate safety constraints into Reinforcement Learning from Human Feedback (RLHF), where recent studies have shown promising progress. However, these methods often rely on auxiliary networks or multi-stage pipelines, thereby increasing complexity. In this work, we revisit the safety alignment objective itself and demonstrate that it admits a closed-form solution, yielding a theoretically grounded and provably equivalent reformulation that enables a direct and tractable optimization procedure. Building on this insight, we propose SafeDPO, a lightweight method derived from this formulation, which preserves the optimality of the underlying safety-constrained objective while requiring only one additional hyperparameter and minimal modifications to existing preference-based training methods. At the same time, it eliminates the need for reward models, cost models, and online sampling. Despite its simplicity, SafeDPO achieves comparable or superior results to state-of-the-art safety alignment methods in both theoretical soundness and empirical performance. Experiments on the PKU-SafeRLHF-30K benchmark show that SafeDPO consistently improves safety while maintaining competitive helpfulness. Ablation studies further show that the additional hyperparameter provides a flexible mechanism to enhance safety without altering the theoretical optimum, and confirm that SafeDPO scales reliably to LLMs with up to 13B parameters. Overall, our results highlight that a simple, theory-driven objective can provide a lightweight yet effective solution for safety alignment in practice.

---

## 10. MedAgentGym: A Scalable Agentic Training Environment for Code-Centric Reasoning in Biomedical Data Science

**OpenReview**: [https://openreview.net/forum?id=jHDZEUgS4r](https://openreview.net/forum?id=jHDZEUgS4r)

**Authors**: Ran Xu (Google DeepMind), Yuchen Zhuang (Google DeepMind), Yishan Zhong (Georgia Institute of Technology), Yue Yu (Meta), Zifeng Wang, Xiangru Tang (Yale University), Hang Wu (ByteDance Inc), May Dongmei Wang (Georgia Institute of Technology), Peifeng Ruan (University of Texas Southwestern Medical Center), Donghan Yang (University of Texas Southwestern Medical Center), Tao Wang (University of Texas Southwestern Medical Center), Guanghua Xiao (University of Texas Southwestern Medical Center), Xin Liu (Google), Carl Yang (Emory University), Yang Xie (UT Southwestern Medical Center), Wenqi Shi (University of Texas Southwestern Medical Center)

**Institutions**: Google DeepMind, Georgia Institute of Technology, Meta, Yale University, ByteDance Inc, University of Texas Southwestern Medical Center, Google, Emory University, UT Southwestern Medical Center

**Primary Area**: datasets and benchmarks

**Keywords**: Medical Reasoning, LLM Agent, Code Generation

**TL;DR**: MedAgentGym is a scalable and interactive training environment designed to enhance coding-based biomedical reasoning capabilities in LLM agents.

**Abstract**: We introduce MedAgentGym, a scalable and interactive training environment designed to enhance coding-based biomedical reasoning capabilities in large language model (LLM) agents. MedAgentGym comprises 72,413 task instances across 129 categories derived from 12 authentic real-world biomedical scenarios. Tasks are encapsulated within executable sandbox environments, each featuring detailed task specifications, interactive feedback mechanisms, verifiable ground truth annotations, and scalable training trajectory generation. Extensive benchmarking of 29 LLMs reveals substantial performance disparities in biomedical data science between commercial and open-source LLMs. Leveraging efficient multi-threaded and multi-turn trajectory sampling in MedAgentGym, Med-Copilot achieves performance gains of +43.02% and +45.28% from offline and online reinforcement learning, respectively, demonstrating MedAgentGym as an effective training ground while establishing itself as a cost-effective, privacy-preserving alternative competitive with proprietary LLMs (gpt-4o). By offering a unified execution environment with a comprehensive benchmark and accessible, extensible training resources, MedAgentGym delivers an integrated platform to develop LLM-based coding assistants for advanced biomedical data science.

---

## 11. Optimistic Task Inference for Behavior Foundation Models

**OpenReview**: [https://openreview.net/forum?id=m5byThUSNE](https://openreview.net/forum?id=m5byThUSNE)

**Authors**: Thomas Rupf (ETHZ - ETH Zurich), Marco Bagatella (Max Planck Institute for Intelligent Systems, Max Planck Institute for Intelligent Systems), Marin Vlastelica (ETHZ - ETH Zurich), Andreas Krause (ETH Zurich)

**Institutions**: ETHZ - ETH Zurich, Max Planck Institute for Intelligent Systems, Max Planck Institute for Intelligent Systems, ETH Zurich

**Primary Area**: reinforcement learning

**Keywords**: Behavior Foundation Models, Zero-Shot Reinforcement Learning, Deep Reinforcement Learning, Fast Adaptation

**TL;DR**: We propose an algorithm for fast online task inference in behavior foundation models.

**Abstract**: Behavior Foundation Models (BFMs) are capable of retrieving high-performing policy for any reward function specified directly at test-time, commonly referred to as zero-shot reinforcement learning (RL). While this is a very efficient process in terms of compute, it can be less so in terms of data: as a standard assumption, BFMs require computing rewards over a non-negligible inference dataset, assuming either access to a functional form of rewards, or significant labeling efforts. To alleviate these limitations, we tackle the problem of task inference purely through interaction with the environment at test-time. We propose OpTI-BFM, an optimistic decision criterion that directly models uncertainty over reward functions and guides BFMs in data collection for task inference. Formally, we provide a regret bound for well- trained BFMs through a direct connection to upper-confidence algorithms for linear bandits. Empirically, we evaluate OpTI-BFM on established zero-shot benchmarks, and observe that it enables successor-features-based BFMs to identify and optimize an unseen reward function in a handful of episodes with minimal compute overhead.

---

## 12. CounselBench: A Large-Scale Expert Evaluation and Adversarial Benchmarking of Large Language Models in Mental Health Question Answering

**OpenReview**: [https://openreview.net/forum?id=8MBYRZHVWT](https://openreview.net/forum?id=8MBYRZHVWT)

**Authors**: Yahan Li, Jifan Yao (University of Southern California), John Bosco S. Bunyi (University of Southern California), Adam C Frank (University of Southern California), Angel Hsing-Chi Hwang (University of Southern California), Ruishan Liu (University of Southern California)

**Institutions**: University of Southern California

**Primary Area**: datasets and benchmarks

**Keywords**: large language models, mental health, human evaluation

**Abstract**: Medical question answering (QA) benchmarks often focus on multiple-choice or fact-based tasks, leaving open-ended answers to real patient questions underexplored. This gap is particularly critical in mental health, where patient questions often mix symptoms, treatment concerns, and emotional needs, requiring answers that balance clinical caution with contextual sensitivity.
We present CounselBench, a large-scale benchmark developed with 100 mental health professionals to evaluate and stress-test large language models (LLMs) in realistic help-seeking scenarios. The first component, CounselBench-EVAL, contains 2,000 expert evaluations of answers from GPT-4, LLaMA 3, Gemini, and online human therapists on patient questions from the public forum CounselChat. Each answer is rated across six clinically grounded dimensions, with span-level annotations and written rationales. Expert evaluations show that while LLMs achieve high scores on several dimensions, they also exhibit recurring issues, including unconstructive feedback, overgeneralization, and limited personalization or relevance. Responses were frequently flagged for safety risks, most notably unauthorized medical advice. Follow-up experiments show that LLM judges systematically overrate model responses and overlook safety concerns identified by human experts. To probe failure modes more directly, we construct CounselBench-Adv, an adversarial dataset of 120 expert-authored mental health questions designed to trigger specific model issues. Expert evaluation of 1,080 responses from nine LLMs reveals consistent, model-specific failure patterns. Together, CounselBench establishes a clinically grounded framework for benchmarking LLMs in mental health QA.

---

## 13. AstaBench: Rigorous Benchmarking of AI Agents with a Scientific Research Suite

**OpenReview**: [https://openreview.net/forum?id=M7TNf5J26u](https://openreview.net/forum?id=M7TNf5J26u)

**Authors**: Jonathan Bragg (Allen Institute for Artificial Intelligence), Mike D'Arcy (Northwestern University), Nishant Balepur (University of Maryland, College Park), Dan Bareket (Bar-Ilan University), Bhavana Dalvi Mishra (Google), Sergey Feldman (Allen Institute for Artificial Intelligence), Dany Haddad (Allen Institute for Artificial Intelligence), Jena D. Hwang (Allen Institute for Artificial Intelligence), Peter Jansen (University of Arizona), Varsha Kishore (Allen Institute for Artificial Intelligence), Bodhisattwa Prasad Majumder (Allen Institute for Artificial Intelligence), Aakanksha Naik (Allen Institute for Artificial Intelligence), Sigal Rahamimov (Allen Institute for Artificial Intelligence), Kyle Richardson (Allen Institute for Artificial Intelligence), Amanpreet Singh (Allen Institute for Artificial Intelligence), Harshit Surana (Allen Institute for Artificial Intelligence), Aryeh Tiktinsky (Allen Institute for Artificial Intelligence), Rosni Vasu (Universität Bern), Guy Wiener (Allen Institute for Artificial Intelligence), Chloe Anastasiades (Allen Institute for Artificial Intelligence), Stefanus Candra (Allen Institute for Artificial Intelligence), Jason Dunkelberger (Allen Institute for Artificial Intelligence), Daniel Emery (The Allen Institute for Artificial Intelligence), Rob Evans (Allen Institute for Artificial Intelligence), Malachi Hamada (Allen Institute for Artificial Intelligence), Regan Huff (Allen Institute for Artificial Intelligence), Rodney Kinney (Allen Institute for Artificial Intelligence), Matt Latzke (Allen Institute for Artificial Intelligence), Jaron Lochner (Allen Institute for Artificial Intelligence), Ruben Lozano-Aguilera (University of Cambridge), Ngoc-Uyen Nguyen (Allen Institute for Artificial Intelligence), Smita Rao (Allen Institute for Artificial Intelligence), Amber Tanaka (Allen Institute for Artificial Intelligence), Brooke Vlahos (Allen Institute for Artificial Intelligence), Peter Clark (Allen Institute for Artificial Intelligence), Doug Downey (Allen Institute for Artificial Intelligence), Yoav Goldberg (Bar-Ilan University), Ashish Sabharwal (Allen Institute for AI), Daniel S Weld (Allen Institute for Artificial Intelligence)

**Institutions**: Allen Institute for Artificial Intelligence, Northwestern University, University of Maryland, College Park, Bar-Ilan University, Google, University of Arizona, Universität Bern, The Allen Institute for Artificial Intelligence, University of Cambridge, Allen Institute for AI

**Primary Area**: datasets and benchmarks

**Keywords**: Agents, evaluation, benchmarks, scientific research

**TL;DR**: We present principles and tooling for rigorous AI agent benchmarking, instantiated in AstaBench—the first holistic measure of agentic ability for scientific research—plus experiments showing AI remains far from solving research assistance.

**Abstract**: AI agents hold the potential to revolutionize scientific productivity by automating literature reviews, replicating experiments, analyzing data, and even proposing new directions of inquiry; indeed, there are now many such agents, ranging from general-purpose "deep research" systems to specialized science-specific agents, such as AI Scientist and AIGS.  Rigorous evaluation of these agents is critical for  progress. Yet existing benchmarks fall short on several fronts: they often (1) lack reproducible agent tools necessary for a controlled comparison of core agentic capabilities; (2) do not account for confounding variables such as model cost and tool access; (3) do not provide standardized interfaces for quick agent prototyping and evaluation; (4) fail to provide holistic, product-informed measures of real-world use cases such as science research; and (5) lack comprehensive baseline agents necessary to identify true advances.  In response, we define principles and tooling for more rigorously benchmarking agents. Using these, we present AstaBench, a suite that provides a holistic measure of agentic ability to perform scientific research, comprising 2400+ problems spanning the entire scientific discovery process and multiple scientific domains, and including many problems inspired by actual user requests to deployed Asta agents.  Our suite comes with the first scientific research environment with production-grade search tools that enable controlled, reproducible evaluation, better accounting for confounders.  Alongside, we provide a comprehensive suite of nine science-optimized classes of Asta agents and numerous baselines.  Our extensive evaluation of 57 agents across 22 agent classes reveals several interesting findings, most importantly that despite meaningful progress on certain individual aspects, AI remains far from solving the challenge of science research assistance.

---

## 14. Neon: Negative Extrapolation From Self-Training Improves Image Generation

**OpenReview**: [https://openreview.net/forum?id=kpLRYtPGt3](https://openreview.net/forum?id=kpLRYtPGt3)

**Authors**: Sina Alemohammad (University of Texas at Austin), Zhangyang Wang (University of Texas at Austin), Richard Baraniuk (William Marsh Rice University)

**Institutions**: University of Texas at Austin, William Marsh Rice University

**Primary Area**: generative models

**Keywords**: Generative Models, Self-Improvement, Weight Merging, Image Generation

**TL;DR**: Instead of simply fine-tuning a generative model on its own synthetic outputs, briefly fine-tune it to find the direction of model collapse, then apply the reverse of that update to the original model for a major performance boost.

**Abstract**: Scaling generative AI models is bottlenecked by the scarcity of high-quality training data. The ease of synthesizing from a generative model suggests using (unverified) synthetic data to augment a limited corpus of real data for the purpose of fine-tuning in the hope of improving performance. Unfortunately, however, the resulting positive feedback loop leads to model autophagy disorder (MAD, aka model collapse) that results in a rapid degradation in sample quality and/or diversity. In this paper, we introduce Neon (for Negative Extrapolation frOm self-traiNing), a new learning method that turns the degradation from self-training into a powerful signal for self-improvement. Given a base model, Neon first fine-tunes it on its own self-synthesized data but then, counterintuitively, reverses its gradient updates to extrapolate away from the degraded weights.  We prove that Neon works because typical inference samplers that favor high-probability regions create a predictable anti-alignment between the synthetic and real data population gradients, which negative extrapolation corrects to better align the model with the true data distribution. Neon is remarkably easy to implement via a simple post-hoc merge that requires no new real data, works effectively with as few as 1k synthetic samples, and typically uses less than 1\% additional training compute.  We demonstrate Neon’s universality across a range of architectures (diffusion, flow matching, autoregressive, and inductive moment matching models) and datasets (ImageNet, CIFAR-10, and FFHQ). In particular, on ImageNet 256x256, Neon elevates the xAR-L model to a new state-of-the-art FID of 1.02 with only 0.36\% additional training compute.

---

## 15. Compositional Diffusion with Guided search for Long-Horizon Planning

**OpenReview**: [https://openreview.net/forum?id=b8avf4F2hn](https://openreview.net/forum?id=b8avf4F2hn)

**Authors**: Utkarsh Aashu Mishra (Georgia Institute of Technology), David He (Georgia Institute of Technology), Yongxin Chen (NVIDIA), Danfei Xu (Georgia Institute of Technology)

**Institutions**: Georgia Institute of Technology, NVIDIA

**Primary Area**: applications to robotics, autonomy, planning

**Keywords**: Diffusion Models, Compositional Diffusion, Goal-directed Planning

**TL;DR**: We integrate search into compositional diffusion to scale short-horizon models into long-horizon plans, supporting motion planning, panoramic image synthesis, and long-video generation.

**Abstract**: Generative models have emerged as powerful tools for planning, with compositional approaches offering particular promise for modeling long-horizon task distributions by composing together local, modular generative models. This compositional paradigm spans diverse domains, from multi-step manipulation planning to panoramic image synthesis to long video generation. However, compositional generative models face a critical challenge: when local distributions are multimodal, existing composition methods average incompatible modes, producing plans that are neither locally feasible nor globally coherent. We propose Compositional Diffusion with Guided Search (CDGS), which addresses this \emph{mode averaging} problem by embedding search directly within the diffusion denoising process. Our method explores diverse combinations of local modes through population-based sampling, prunes infeasible candidates using likelihood-based filtering, and enforces global consistency through iterative resampling between overlapping segments. CDGS matches oracle performance on seven robot manipulation tasks, outperforming baselines that lack compositionality or require long-horizon training data. The approach generalizes across domains, enabling coherent text-guided panoramic images and long videos through effective local-to-global message passing. More details: https://cdgsearch.github.io/

---

## 16. Visual symbolic mechanisms: Emergent symbol processing in Vision Language Models

**OpenReview**: [https://openreview.net/forum?id=3RQ863cRbx](https://openreview.net/forum?id=3RQ863cRbx)

**Authors**: Rim Assouel, Declan Iain Campbell (Princeton University), Yoshua Bengio (University of Montreal), Taylor Whittington Webb (Research, Microsoft)

**Institutions**: Princeton University, University of Montreal, Research, Microsoft

**Primary Area**: interpretability and explainable AI

**Keywords**: visual object binding, vision-langue model, symbolic reasoning, interpretability

**TL;DR**: We describe a set of symbolic-like mechanisms that VLMs use to bind to visual entities in context

**Abstract**: To accurately process a visual scene, observers must bind features together to represent individual objects. This capacity is necessary, for instance, to distinguish an image containing a red square and a blue circle from an image containing a blue square and a red circle. Recent work has found that language models solve this ‘binding problem’ via a set of symbol-like, content-independent indices, but it is unclear whether similar mechanisms are employed by Vision Language Models (VLM). This question is especially relevant, given the persistent failures of VLMs on tasks that require binding. Here, we identify a previously unknown set of emergent symbolic mechanisms that support binding specifically in VLMs, via a content-independent, spatial indexing scheme. Moreover, we find that binding errors, when they occur, can be traced directly to failures in these mechanisms. Taken together, these results shed light on the mechanisms that support symbol-like processing in VLMs, and suggest possible avenues for reducing the number of binding failures exhibited by these models.

---

## 17. Addressing divergent representations from causal interventions on neural networks

**OpenReview**: [https://openreview.net/forum?id=cZrTMqYVL6](https://openreview.net/forum?id=cZrTMqYVL6)

**Authors**: Satchel Grant (Simons Foundation), Simon Jerome Han (Stanford University), Alexa R. Tartaglini (Stanford University), Christopher Potts (Stanford University)

**Institutions**: Simons Foundation, Stanford University

**Primary Area**: interpretability and explainable AI

**Keywords**: activation patching, mech interp, DAS, representational divergence, faithfulness

**TL;DR**: We show empirical representational divergence between native and causally intervened latent states, we show that this can be pernicious and propose a solution.

**Abstract**: A common approach to mechanistic interpretability is to causally manipulate model representations via targeted interventions in order to understand what those representations encode. Here we ask whether such interventions create out-of-distribution (divergent) representations, and whether this raises concerns about how faithful their resulting explanations are to the target model in its natural state. First, we demonstrate theoretically and empirically that common causal intervention techniques often do shift internal representations away from the natural distribution of the target model. Then, we provide a theoretical analysis of two cases of such divergences: "harmless" divergences that occur in the behavioral null-space of the layer(s) of interest, and "pernicious" divergences that activate hidden network pathways and cause dormant behavioral changes. Finally, in an effort to mitigate the pernicious cases, we apply and modify the Counterfactual Latent (CL) loss from Grant (2025) allowing representations from causal interventions to remain closer to the natural distribution, reducing the likelihood of harmful divergences while preserving the interpretive power of the interventions. Together, these results highlight a path towards more reliable interpretability methods.

---

## 18. Cross-Domain Lossy Compression via Rate- and Classification-Constrained Optimal Transport

**OpenReview**: [https://openreview.net/forum?id=mUIGdUTtk2](https://openreview.net/forum?id=mUIGdUTtk2)

**Authors**: Nam Nguyen (Oregon State University), Thinh Nguyen (Oregon State University), Bella Bose (Oregon State University)

**Institutions**: Oregon State University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Lossy Compression, Image Compression, Image Restoration, Image Inpainting, Optimal Transport, Multi-task Learning, Rate-Distortion-Perception Tradeoff, Rate-Distortion-Classification Tradeoff, Deep Learning, Unsupervised Learning

**TL;DR**: We study cross-domain lossy compression via constrained optimal transport with rate and classification constraints, derive closed-form tradeoffs, extend to perception divergences, and validate with deep restoration and inpainting experiments.

**Abstract**: We study cross-domain lossy compression, where the encoder observes a degraded source while the decoder reconstructs samples from a distinct target distribution. The problem is formulated as constrained optimal transport with two constraints on compression rate and classification loss. With shared common randomness, the one-shot setting reduces to a deterministic transport plan, and we derive closed-form distortion-rate-classification (DRC) and rate-distortion-classification (RDC) tradeoffs for Bernoulli sources under Hamming distortion. In the asymptotic regime, we establish analytic DRC/RDC expressions for Gaussian models under mean-squared error. The framework is further extended to incorporate perception divergences (Kullback-Leibler and squared Wasserstein), yielding closed-form distortion-rate-perception-classification (DRPC) functions. To validate the theory, we develop deep end-to-end compression models for super-resolution (MNIST), denoising (SVHN, CIFAR-10, ImageNet, KODAK), and inpainting (SVHN) problems, demonstrating the consistency between the theoretical results and empirical performance.

---

## 19. Latent Fourier Transform

**OpenReview**: [https://openreview.net/forum?id=ogMxCjdCCq](https://openreview.net/forum?id=ogMxCjdCCq)

**Authors**: Mason Long Wang (Massachusetts Institute of Technology), Cheng-Zhi Anna Huang (Massachusetts Institute of Technology)

**Institutions**: Massachusetts Institute of Technology

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Music Generation, Signal Processing, Diffusion Models, Audio, Music, Audio Generation, Controllable Generation, Fourier Transform, Diffusion Autoencoders

**TL;DR**: We introduce novel frequency-domain controls for generative music models by applying the Fourier transform to the latent space of a diffusion autoencoder.

**Abstract**: We introduce the Latent Fourier Transform (LatentFT), a framework that provides novel frequency-domain controls for generative music models. LatentFT combines a diffusion autoencoder with a latent-space Fourier transform to separate musical patterns by timescale. By masking latents in the frequency domain during training, our method yields representations that can be manipulated coherently at inference. This allows us to generate musical variations and blends from reference examples while preserving characteristics at desired timescales, which are specified as frequencies in the latent space. LatentFT parallels the role of the equalizer in music production: while traditional equalizers operates on audible frequencies to shape timbre, LatentFT operates on latent-space frequencies to shape musical structure. Experiments and listening tests show that LatentFT improves condition adherence and quality compared to baselines. We also present a technique for hearing frequencies in the latent space in isolation, and show different musical attributes reside in different regions of the latent spectrum. Our results show how frequency-domain control in latent space provides an intuitive, continuous frequency axis for conditioning and blending, advancing us toward more interpretable and interactive generative music models.

---

## 20. GLASS Flows: Efficient Inference for Reward Alignment of Flow and Diffusion Models

**OpenReview**: [https://openreview.net/forum?id=vH7OAPZ2dR](https://openreview.net/forum?id=vH7OAPZ2dR)

**Authors**: Peter Holderrieth (MIT), Uriel Singer (Meta AI Research), Tommi Jaakkola, Ricky T. Q. Chen (FAIR Labs, Meta AI), Yaron Lipman, Brian Karrer (Meta Fundamental AI Research (FAIR))

**Institutions**: MIT, Meta AI Research, FAIR Labs, Meta AI, Meta Fundamental AI Research (FAIR)

**Primary Area**: generative models

**Keywords**: Flow Matching; Diffusion Models; Reward Alignment; Reward Adaptation; Inference-time scaling; Feynman-Kac Steering; Markov transitions; Sampling methods

**TL;DR**: We improve inference-time reward alignment of flow matching and diffusion models by proposing a novel sampling paradigm that enables more efficient exploration.

**Abstract**: The performance of flow matching and diffusion models can be greatly improved at inference time using reward adaptation algorithms, yet efficiency remains a major limitation. While several algorithms were proposed, we demonstrate that a common bottleneck is the *sampling* method these algorithms rely on: many algorithms require to sample Markov transitions via SDE sampling, which is significantly less efficient and often less performant than ODE sampling. To remove this bottleneck, we introduce GLASS Flows, a new sampling paradigm that simulates a ''flow matching model within a flow matching model'' to sample Markov transitions. As we show in this work, this ''inner'' flow matching model can be retrieved from any pre-trained model without any re-training, effectively combining the efficiency of ODEs with the stochastic evolution of SDEs. On large-scale text-to-image models, we show that GLASS Flows eliminate the trade-off between stochastic evolution and efficiency. GLASS Flows improve state-of-the-art performance in text-to-image generation, making it a simple, drop-in solution for inference-time scaling of flow and diffusion models.

---

## 21. Latent Speech-Text Transformer

**OpenReview**: [https://openreview.net/forum?id=krGpQzo8Mz](https://openreview.net/forum?id=krGpQzo8Mz)

**Authors**: Yen-Ju Lu (Johns Hopkins University), Yashesh Gaur (Microsoft), Wei Zhou (Google), Benjamin Muller (Meta), Jesus Villalba (Johns Hopkins University), Najim Dehak (Johns Hopkins University), Luke Zettlemoyer (University of Washington), Gargi Ghosh (Meta AI), Mike Lewis (Facebook AI Research), Srini Iyer (Facebook), Duc Le (Facebook)

**Institutions**: Johns Hopkins University, Microsoft, Google, Meta, University of Washington, Meta AI, Facebook AI Research, Facebook

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Speech–Text Models, Latent Patching, Multimodal Alignment, Large Language Models

**TL;DR**: We introduce Latent Speech-Text Transformerwhich patches long speech token sequences into latent units, improving text–speech transfer while cutting pre-training and inference compute, and significantly outperforming existing speech-text LLMs.

**Abstract**: Auto-regressive speech-text models are typically pre-trained on a large number of interleaved sequences of text tokens and raw speech encoded as speech tokens using vector quantization. These models have demonstrated state-of-the-art performance in speech-to-speech understanding and generation benchmarks, together with promising scaling laws, primarily enabled by the representational alignment between text and speech. Nevertheless, they suffer from shortcomings, partly owing to the disproportionately longer sequences of speech tokens in contrast to textual tokens. This results in a large compute imbalance between modalities during pre-training as well as during inference, and a potential hindrance to effectively aligning speech and text, ultimately translating to several orders of magnitude slower scaling laws. We introduce the Latent Speech-Text Transformer (LST), which makes pre-training speech-text models more data-efficient by dynamically and inexpensively aggregating speech tokens into latent speech patches. These patches serve as higher-level units that can either align with corresponding textual units to aid capability transfer or even encapsulate common speech sequences like silences to be more compute-efficient. We show that LST outperforms vanilla approaches on speech-to-speech as well as text-to-text benchmarks in both data- and compute-controlled settings, the former indicating more effective representational alignment and the latter indicating steeper scaling laws for speech-text models. On HellaSwag story completion, LST achieves 6.5% absolute gain in speech accuracy under compute-controlled training and 5.3% under data-controlled training, while also improving text performance. We will release our models, code, and the evaluation data to facilitate further research.

---

## 22. LoongRL: Reinforcement Learning for Advanced Reasoning over Long Contexts

**OpenReview**: [https://openreview.net/forum?id=o29E01Q6bv](https://openreview.net/forum?id=o29E01Q6bv)

**Authors**: Siyuan Wang (Shanghai Jiaotong University), Gaokai Zhang (Carnegie Mellon University), Li Lyna Zhang (Microsoft Research Asia), Ning Shang (Microsoft), Fan Yang (Research, Microsoft), Dongyao Chen (Shanghai Jiaotong University), Mao Yang (Peking University)

**Institutions**: Shanghai Jiaotong University, Carnegie Mellon University, Microsoft Research Asia, Microsoft, Research, Microsoft, Peking University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Long Context Reasoning, Reinforcement Learning

**Abstract**: Reasoning over long contexts is essential for large language models. While reinforcement learning (RL) enhances short-context reasoning by inducing "Aha" moments in chain-of-thought, the advanced thinking patterns required for long-context reasoning  remain largely unexplored, and high-difficulty RL data are scarce. In this paper, we introduce LoongRL, a data-driven RL method for advanced long-context reasoning. Central to LoongRL is KeyChain,  a synthesis approach that transforms short multi-hop QA into high-difficulty long-context tasks by inserting UUID chains that hide the true question among large collections of distracting documents. Solving these tasks requires the model to trace the correct chain step-by-step, identify the true question,   retrieve relevant facts and reason over them to answer correctly. 
RL training on KeyChain data induces an emergent plan–retrieve–reason–recheck reasoning pattern that generalizes far beyond training length. Models trained at 16K effectively solve 128K tasks without prohibitive full-length RL rollout costs. On Qwen2.5-7B and 14B, LoongRL substantially improves long-context multi-hop QA accuracy by +23.5% and +21.1% absolute gains. The  resulting LoongRL-14B reaches a score of 74.2, rivaling much larger frontier models such as o3-mini (74.5) and DeepSeek-R1 (74.9). It  also improves long-context retrieval, passes all 128K needle-in-a-haystack stress tests, and preserves short-context reasoning capabilities. Code is available at https://loongrl.github.io.

---

## 23. Speculative Actions: A Lossless Framework for Faster AI Agents

**OpenReview**: [https://openreview.net/forum?id=P0GOk5wslg](https://openreview.net/forum?id=P0GOk5wslg)

**Authors**: Naimeng Ye (Columbia University), Arnav Ahuja (Columbia University), Georgios Liargkovas (Columbia University), Yunan Lu (Columbia University), Kostis Kaffes (Columbia University), Tianyi Peng (Columbia University)

**Institutions**: Columbia University

**Primary Area**: infrastructure, software libraries, hardware, systems, etc.

**Keywords**: AI Agents, Speculative Decoding, Parallel Execution, Agentic Serving, Agentic Simulation

**TL;DR**: We introduce speculative actions—a lossless framework that predicts likely actions using faster models, enabling multiple API calls to be executed in parallel and thus yields substantial acceleration.

**Abstract**: Despite growing interest in AI agents across industry and academia, their execution in an environment is often slow, hampering training, evaluation, and deployment. For example, a game of chess between  two state-of-the-art agents may take hours. A critical bottleneck is that agent behavior unfolds sequentially: each action requires an API call, and these calls can be time-consuming. Inspired by speculative execution in microprocessors and speculative decoding in LLM inference, we propose \emph{speculative actions}, a lossless framework for general agentic systems that predicts likely actions using faster models, enabling multiple steps to be executed in parallel. We evaluate this framework across three agentic environments: gaming, e-commerce, web search, and a ``lossy'' extension for an operating systems environment. In all cases, speculative actions achieve substantial accuracy in next-action prediction (up to 55\%), translating into significant reductions in end-to-end latency. Finally, we develop a cost-latency analysis that formalizes the tradeoff between launching additional speculative actions and the resulting time savings. This analysis enables principled tuning of speculative breadth and selective branch launching, ensuring that speculation remains practically deployable.

---

## 24. Gaussian certified unlearning in high dimensions: A hypothesis testing approach

**OpenReview**: [https://openreview.net/forum?id=0FJYicpOj0](https://openreview.net/forum?id=0FJYicpOj0)

**Authors**: Aaradhya Pandey (Princeton University), Arnab Auddy (Ohio State University, Columbus), Haolin Zou (Columbia University), Arian Maleki (Columbia University), Sanjeev Kulkarni (Princeton University)

**Institutions**: Princeton University, Ohio State University, Columbus, Columbia University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Machine unlearning in high dimensions, Proportional asymptotics, High dimensional statistical theory, Privacy–accuracy tradeoff, Hypothesis testing, Gaussian noise calibration, Newton method

**TL;DR**: We introduce the canonical dimension free notion of certifiability suitable to high dimensions and show its utility via a Newton based unlearning algorithm

**Abstract**: Machine unlearning seeks to efficiently remove the influence of selected data while preserving generalization. Significant progress has been made in low dimensions, \textcolor{blue}{where the dimension of the parameter} $p$ is  much smaller than \textcolor{blue}{the sample size} $n$, but high dimensions, including proportional regimes $p \sim n$, pose serious theoretical challenges as standard optimization assumptions of $\Omega(1)$ strong convexity and $O(1)$ smoothness of the per-example loss $f$ rarely hold simultaneously in proportional regimes $p\sim n$.
In this work, we introduce $\varepsilon$-Gaussian certifiability, a canonical and robust notion well-suited to high-dimensional regimes, that optimally captures a broad class of noise adding mechanisms. Then we theoretically analyze the performance of a widely used unlearning algorithm based on one step of the Newton method in the high-dimensional setting described above. Our analysis shows that a single Newton step, followed by a well-calibrated Gaussian noise, is sufficient to achieve both privacy and accuracy in this setting. This result stands in sharp contrast to the only prior work that analyzes machine unlearning in high dimensions \citet{zou2025certified}, which relaxes some of the standard optimization assumptions for high-dimensional applicability, but operates under the notion of $\varepsilon$-certifiability. That work concludes %that a single Newton step is insufficient even for removing a single data point, and
that at least two steps are required to ensure both privacy and accuracy. Our result leads us to conclude that the discrepancy in the number of steps arises because of the sub optimality of the notion of $\varepsilon$-certifiability and its incompatibility with noise adding mechanisms, which $\varepsilon$-Gaussian certifiability is able to overcome optimally.

---

## 25. RedTeamCUA: Realistic Adversarial Testing of Computer-Use Agents in Hybrid Web-OS Environments

**OpenReview**: [https://openreview.net/forum?id=yWwrgcBoK3](https://openreview.net/forum?id=yWwrgcBoK3)

**Authors**: Zeyi Liao (Ohio State University, Columbus), Jaylen Jones (Ohio State University, Columbus), Linxi Jiang (Ohio State University, Columbus), Yuting Ning (Ohio State University, Columbus), Eric Fosler-Lussier (Ohio State University), Yu Su (Ohio State University), Zhiqiang Lin (Ohio State University, Columbus), Huan Sun (The Ohio State University, Columbus)

**Institutions**: Ohio State University, Columbus, Ohio State University, The Ohio State University, Columbus

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Computer-Use Agents, Adversarial Risks, Sandbox, Benchmark

**TL;DR**: We provide a realistic, controlled and hybrid sandbox for systematic adversarial testings against computer-use agents.

**Abstract**: Computer-use agents (CUAs) promise to automate complex tasks across operating systems (OS) and the web, but remain vulnerable to indirect prompt injection, where attackers embed malicious content into the environment to hijack agent behavior. Current evaluations of this threat either lack support for adversarial testing in realistic but controlled environments or ignore hybrid web-OS attack scenarios involving both interfaces. To address this, we propose RedTeamCUA, an adversarial testing framework featuring a novel hybrid sandbox that integrates a VM-based OS environment with Docker-based web platforms. Our sandbox supports key features tailored for red teaming, such as flexible adversarial scenario configuration, and a setting that decouples adversarial evaluation from navigational limitations of CUAs by initializing tests directly at the point of an adversarial injection. Using RedTeamCUA, we develop RTC-Bench, a comprehensive benchmark with 864 examples that investigate realistic, hybrid web-OS attack scenarios and fundamental security vulnerabilities. Benchmarking current frontier CUAs identifies significant vulnerabilities: Claude 3.7 Sonnet | CUA demonstrates an Attack Success Rate (ASR) of 42.9%, while Operator, the most secure CUA evaluated, still exhibits an ASR of 7.6%. Notably, CUAs often attempt to execute adversarial tasks with an Attempt Rate as high as 92.5%, although failing to complete them due to capability limitations. Nevertheless, we observe concerning ASRs of up to 50% in realistic end-to-end settings, indicating that CUA threats can already result in tangible risks to users and computer systems. Overall, RedTeamCUA provides an essential framework for advancing realistic, controlled, and systematic analysis of CUA vulnerabilities, highlighting the urgent need for robust defenses to indirect prompt injection prior to real-world deployment.

---

## 26. Exploratory Causal Inference in SAEnce

**OpenReview**: [https://openreview.net/forum?id=Ml8t8kQMUP](https://openreview.net/forum?id=Ml8t8kQMUP)

**Authors**: Tommaso Mencattini (EPFL - EPF Lausanne), Riccardo Cadei (Institute of Science and Technology), Francesco Locatello (Institute of Science and Technology)

**Institutions**: EPFL - EPF Lausanne, Institute of Science and Technology

**Primary Area**: interpretability and explainable AI

**Keywords**: Randomized Controlled Trials, Sparse Auto Encoder, Interpretability, Causal Inference

**TL;DR**: New method to uncover causal treatment effects directly from trial data using foundation models, SAE and recursive stratification, without any prior and supervision.

**Abstract**: Randomized Controlled Trials are one of the pillars of science; nevertheless, they rely on hand-crafted hypotheses and expensive analysis. Such constraints prevent causal effect estimation at scale, potentially anchoring on popular yet incomplete hypotheses. We propose to discover the unknown effects of a treatment directly from data. For this, we turn unstructured data from a trial into meaningful representations via pretrained foundation models and interpret them via a Sparse Auto Encoder. However, discovering significant causal effects at the neural level is not trivial due to multiple-testing issues and effects entanglement. To address these challenges, we introduce _Neural Effect Search_, a novel recursive procedure solving both issues by progressive stratification. After assessing the robustness of our algorithm on semi-synthetic experiments, we showcase, in the context of experimental ecology, the first successful unsupervised causal effect identification on a real-world scientific trial.

---

## 27. Every Language Model Has a Forgery-Resistant Signature

**OpenReview**: [https://openreview.net/forum?id=vLFqOoMBol](https://openreview.net/forum?id=vLFqOoMBol)

**Authors**: Matthew Finlayson (University of Southern California), Xiang Ren (University of Southern California), Swabha Swayamdipta (University of Southern California)

**Institutions**: University of Southern California

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: fingerprint, watermark, language model, signature, accountability, cryptography, forgery, security

**TL;DR**: We show that all language models impose elliptical constraints on their outputs, which can be used as a hard-to-fake signature to identify a model from its outputs.

**Abstract**: The ubiquity of closed-weight language models with public-facing APIs has generated interest in forensic methods, both for extracting hidden model details (e.g., parameters) and identifying models by their outputs. One successful approach to these goals has been to exploit the geometric constraints imposed by the language model architecture and parameters. In this work, we show that a lesser-known geometric constraint—namely that language model outputs lie on the surface of a high-dimensional ellipse—functions as a signature for the model, which be used to identify which model an output came from. This ellipse signature has unique properties that distinguish it from existing model-output association methods like language model watermarks. In particular, the signature is hard to forge: without direct access to model parameters, it is practically infeasible to produce logprobs on the ellipse. Secondly, the signature is naturally occurring, since all language models have these elliptical constraints. Thirdly, the signature is self-contained, in that it is detectable without access to the model input or full weights. Finally, the signature is exceptionally redundant, as it is independently detectable in every single logprob output from the model. We evaluate a novel technique for extracting the ellipse on small models, and discuss the practical hurdles that make it infeasible for production-size models, making the signature hard to forge. Finally, we use ellipse signatures to propose a protocol for language model output verification, which is analogous to cryptographic symmetric-key message authentication systems.

---

## 28. Pre-training under infinite compute

**OpenReview**: [https://openreview.net/forum?id=ck0aZTAnwK](https://openreview.net/forum?id=ck0aZTAnwK)

**Authors**: Konwoo Kim, Suhas Kotha (Stanford University), Percy Liang (Stanford University), Tatsunori Hashimoto (Stanford University)

**Institutions**: Stanford University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: scaling laws, data efficiency, pre-training

**TL;DR**: Since compute grows faster than the web, we design simple recipes that improve the asymptote of compute scaling laws to be 5x data efficient, offering better performance with sufficient compute.

**Abstract**: Since compute grows much faster than web text available for language model pre-training, we ask how one should approach pre-training under fixed data and no compute constraints. We first show that existing data-constrained approaches of increasing epoch count and parameter count overfit, and we improve upon such recipes by tuning regularization, finding that the optimal weight decay is $30\times$ larger than standard practice. Since our regularized recipe monotonically decreases loss following a power law in parameter count, we estimate its best possible performance via the \textbf{asymptote} of its scaling law rather than the performance at a fixed compute budget. We then identify that ensembling independently trained models achieves a significantly lower loss asymptote than the regularized recipe. Our best intervention combining epoching, regularization, parameter scaling, and ensemble scaling achieves an asymptote at 200M tokens using $5.17\times$ less data than our baseline, and our data scaling laws predict that this improvement persists at higher token budgets. We find that our data efficiency gains can be realized at smaller parameter counts as we can distill an ensemble into a student model that is 8$\times$ smaller and retains $83$% of the ensembling benefit. Finally, our interventions designed for validation loss generalize to downstream benchmarks, achieving a $9$% improvement for pre-training evals. Our results show that simple algorithmic improvements can enable significantly more data-efficient pre-training in a compute-rich future.

---

## 29. GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning

**OpenReview**: [https://openreview.net/forum?id=RQm2KQTM5r](https://openreview.net/forum?id=RQm2KQTM5r)

**Authors**: Lakshya A Agrawal (University of California, Berkeley), Shangyin Tan (University of California, Berkeley), Dilara Soylu (Stanford University), Noah Ziems (University of Notre Dame), Rishi Khare (Georgia Institute of Technology), Krista Opsahl-Ong (Stanford University), Arnav Singhvi (Computer Science Department, Stanford University), Herumb Shandilya (Stanford University), Michael J Ryan (Stanford University), Meng Jiang (University of Notre Dame), Christopher Potts (Stanford University), Koushik Sen (UC Berkeley, University of California, Berkeley), Alex Dimakis (Electrical Engineering & Computer Science Department, University of California, Berkeley), Ion Stoica (University of California, Berkeley), Dan Klein (University of California, Berkeley), Matei Zaharia (University of California, Berkeley), Omar Khattab (Massachusetts Institute of Technology)

**Institutions**: University of California, Berkeley, Stanford University, University of Notre Dame, Georgia Institute of Technology, Computer Science Department, Stanford University, UC Berkeley, University of California, Berkeley, Electrical Engineering & Computer Science Department, University of California, Berkeley, Massachusetts Institute of Technology

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: prompt optimization, natural language, reflection, large language models, agent design, agent discovery, code optimization, compound AI systems, genetic, language based learning, evolutionary algorithms

**TL;DR**: GEPA uses natural language reflection to optimize prompts, outperforming GRPO and MIPROv2 while needing far fewer rollouts.

**Abstract**: Large language models (LLMs) are increasingly adapted to downstream tasks via reinforcement learning (RL) methods like Group Relative Policy Optimization (GRPO), which often require thousands of rollouts to learn new tasks. We argue that the interpretable nature of language often provides a much richer learning medium for LLMs, compared to policy gradients derived from sparse, scalar rewards. To test this, we introduce GEPA (Genetic-Pareto), a prompt optimizer that thoroughly incorporates natural language reflection to learn high-level rules from trial and error.
    Given any AI system containing one or more LLM prompts, GEPA samples trajectories (e.g., reasoning, tool calls, and tool outputs) and reflects on them in natural language to diagnose problems, propose and test prompt updates, and combine complementary lessons from the Pareto frontier of its own attempts. As a result of GEPA's design, it can often turn even just a few rollouts into a large quality gain.
    Across four tasks, GEPA outperforms GRPO by 6% on average and by up to 20%, while using up to 35x fewer rollouts. GEPA also outperforms the leading prompt optimizer, MIPROv2, by over 10% (e.g., +10% accuracy on AIME-2025).

---

## 30. $p\textrm{-less}$ Sampling: A Robust Hyperparameter-Free Approach for LLM Decoding

**OpenReview**: [https://openreview.net/forum?id=ItFuNJQGH4](https://openreview.net/forum?id=ItFuNJQGH4)

**Authors**: Runyan Tan (AI Labs, Thoughtworks), Shuang Wu (Thoughtworks), Phillip Howard (Thoughtworks)

**Institutions**: AI Labs, Thoughtworks, Thoughtworks

**Primary Area**: probabilistic methods (Bayesian methods, variational inference, sampling, UQ, etc.)

**Keywords**: LLM, decoding, sampling, truncation, inference, information-theoretic, information-theory, hyperparameterless, hyperparameter-free, entropy, entropy-aware, distribution-aware, adaptive, efficient, generation

**TL;DR**: P-less Sampling: A parameterless sampling strategy grounded in information theory, where the truncation threshold adapts to the entire token probability distribution, is bounded and valid, and dynamically adjusts with temperature.

**Abstract**: Obtaining high-quality outputs from Large Language Models (LLMs) often depends upon the choice of a sampling-based decoding strategy to probabilistically choose the next token at each generation step. While a variety of such sampling methods have been proposed, their performance can be sensitive to the selection of hyperparameters which may require different settings depending upon the generation task and temperature configuration. In this work, we introduce $p\textrm{-less}$ sampling: an information-theoretic approach to sampling which dynamically sets a truncation threshold at each decoding step based on the entire token probability distribution. Unlike existing methods, $p\textrm{-less}$ sampling has no hyperparameters and consistently produces high-quality outputs as temperature increases. We provide theoretical perspectives on $p$-less sampling to ground our proposed method and conduct experiments to empirically validate its effectiveness across a range of math, logical reasoning, and creative writing tasks. Our results demonstrate how $p\textrm{-less}$ sampling consistently outperforms existing sampling approaches while exhibiting much less degradation in text quality at higher temperature values. We further show how $p$-less achieves greater inference-time efficiency than alternative methods through lower average token sampling times and shorter generation lengths, without sacrificing accuracy.
Finally, we provide analyses to highlight the benefits of $p\textrm{-less}$ through qualitative examples, case studies, and diversity assessments.

---

## 31. EigenBench: A Comparative Behavioral Measure of Value Alignment

**OpenReview**: [https://openreview.net/forum?id=fm79KXJIUQ](https://openreview.net/forum?id=fm79KXJIUQ)

**Authors**: Jonathn Chang (Cornell University), Leonhard Piff (Cornell University), Suvadip Sana (Cornell University), Jasmine Xinze Li (Cornell University), Lionel Levine (Cornell University)

**Institutions**: Cornell University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: value alignment, Bradley-Terry model, EigenTrust, model disposition, constitutional AI

**Abstract**: Aligning AI with human values is a pressing unsolved problem. To address the lack of quantitative metrics for value alignment, we propose EigenBench: a black-box method for comparatively benchmarking language models’ values. Given an ensemble of models, a constitution describing a value system, and a dataset of scenarios, our method returns a vector of scores quantifying each model’s alignment to the given constitution. To produce these scores, each model judges the outputs of other models across many scenarios, and these judgments are aggregated with EigenTrust (Kamvar et al., 2003), yielding scores that reflect a weighted consensus judgment of the whole ensemble. EigenBench uses no ground truth labels, as it is designed to quantify subjective traits for which reasonable judges may disagree on the correct label. Hence, to validate our method, we collect human judgments on the same ensemble of models and show that EigenBench’s judgments align closely with those of human evaluators. We further demonstrate that EigenBench can recover model rankings on the GPQA benchmark without access to objective labels, supporting its viability as a framework for evaluating subjective values for which no ground truths exist.

---

## 32. A Representer Theorem for Hawkes Processes via Penalized Least Squares Minimization

**OpenReview**: [https://openreview.net/forum?id=gJjRdLG5MY](https://openreview.net/forum?id=gJjRdLG5MY)

**Authors**: Hideaki Kim (NTT), Tomoharu Iwata (NTT)

**Institutions**: NTT

**Primary Area**: learning theory

**Keywords**: Hawkes processes, kernel methods, representer theorem, point processes, least squares loss

**Abstract**: The representer theorem is a cornerstone of kernel methods, which aim to estimate latent functions in reproducing kernel Hilbert spaces (RKHSs) in a nonparametric manner. Its significance lies in converting inherently infinite-dimensional optimization problems into finite-dimensional ones over dual coefficients, thereby enabling practical and computationally tractable algorithms. In this paper, we address the problem of estimating the latent triggering kernels--functions that encode the interaction structure between events--for linear multivariate Hawkes processes based on observed event sequences within an RKHS framework. We show that, under the principle of penalized least squares minimization, a novel form of representer theorem emerges: a family of transformed kernels can be defined via a system of simultaneous integral equations, and the optimal estimator of each triggering kernel is expressed as a linear combination of these transformed kernels evaluated at the data points. Remarkably, the dual coefficients are all analytically fixed to unity, obviating the need to solve a costly optimization problem to obtain the dual coefficients. This leads to a highly efficient estimator capable of handling large-scale data more effectively than conventional nonparametric approaches. Empirical evaluations on synthetic and real-world datasets reveal that the proposed method achieves competitive predictive accuracy while substantially improving computational efficiency compared to state-of-the-art kernel method-based estimators.

---

## 33. UALM: Unified Audio Language Model for Understanding, Generation and Reasoning

**OpenReview**: [https://openreview.net/forum?id=TsdlOjcQNu](https://openreview.net/forum?id=TsdlOjcQNu)

**Authors**: Jinchuan Tian (CMU, Carnegie Mellon University), Sang-gil Lee (NVIDIA), Zhifeng Kong (NVIDIA), Sreyan Ghosh (University of Maryland, College Park), Arushi Goel (NVIDIA Research), Chao-Han Huck Yang (NVIDIA Research), Wenliang Dai (NVIDIA), Zihan Liu (NVIDIA), Hanrong Ye, Shinji Watanabe (Japan Broadcasting Corporation), Mohammad Shoeybi (NVIDIA), Bryan Catanzaro (NVIDIA), Rafael Valle (NVIDIA), Wei Ping (NVIDIA)

**Institutions**: CMU, Carnegie Mellon University, NVIDIA, University of Maryland, College Park, NVIDIA Research, Japan Broadcasting Corporation

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Audio Language Model, Audio Understanding, Audio Generation

**TL;DR**: This paper introduces UALM, an audio language model designed to unify audio understanding, generation, and reasoning

**Abstract**: Recent advances in the audio language modeling (ALM) domain tackle audio understanding and text-to-audio generation as separate tasks. Very few studies attempt to unify these tasks -- an essential step toward advanced multimodal reasoning. This paper introduces Unified Audio Language Model (UALM), which aims to unify audio understanding, text-to-audio generation, and multimodal reasoning in a single model. To achieve this goal, we first present UALM-Gen, a text-to-audio language model that directly predicts audio tokens and is comparable to state-of-the-art diffusion-based models. We then demonstrate, using proper data blending, training recipes, and inference techniques, that our single UALM model matches the quality of state-of-the-art specialized models in audio understanding, text-to-audio generation, and text reasoning.  Furthermore, we present UALM-R1, a multimodal reasoning model that utilizes both text and audio in the intermediate thinking steps to facilitate complex generation tasks. To our knowledge, this is the first demonstration in audio research of cross-modal generative reasoning, with its effectiveness confirmed by subjective evaluations.

---

## 34. Agent Data Protocol

**OpenReview**: [https://openreview.net/forum?id=tG6301ORHd](https://openreview.net/forum?id=tG6301ORHd)

**Authors**: Yueqi Song (Carnegie Mellon University), Ketan Ramaneti (Amazon), Zaid Sheikh (Carnegie Mellon University), Ziru Chen (Ohio State University, Columbus), Boyu Gou (Ohio State University, Columbus), Tianbao Xie (University of Hong Kong), Yiheng Xu, Danyang Zhang (Shanghai Jiao Tong University), Apurva Gandhi (Carnegie Mellon University), Fan Yang (Fujitsu), Joseph Liu (School of Computer Science, Carnegie Mellon University), Tianyue Ou, Zhihao Yuan (Carnegie Mellon University), Frank F. Xu (Microsoft), Shuyan Zhou (Duke University), Xingyao Wang (All Hands AI), Xiang Yue, Tao Yu (The University of Hong Kong), Huan Sun (The Ohio State University, Columbus), Yu Su (Ohio State University), Graham Neubig (Carnegie Mellon University)

**Institutions**: Carnegie Mellon University, Amazon, Ohio State University, Columbus, University of Hong Kong, Shanghai Jiao Tong University, Fujitsu, School of Computer Science, Carnegie Mellon University, Microsoft, Duke University, All Hands AI, The University of Hong Kong, The Ohio State University, Columbus, Ohio State University

**Primary Area**: datasets and benchmarks

**Keywords**: agent, training, data

**Abstract**: Public research results on large-scale supervised finetuning of AI agents remain relatively rare, since the collection of agent training data presents unique challenges. In this work, we argue that the bottleneck is not a lack of underlying data sources, but that a large variety of data is fragmented across heterogeneous formats, tools, and interfaces. To this end, we introduce the Agent Data Protocol (ADP), a light-weight representation language that serves as an "interlingua" between agent datasets in diverse formats and unified agent training pipelines downstream. The design of ADP is expressive enough to capture a large variety of tasks, including API/tool use, browsing, coding, software engineering, and general agentic workflows, while remaining simple to parse and train on without engineering at a per-dataset level. In experiments, we unified a broad collection of 13 existing agent training datasets into ADP format, and converted the standardized ADP data into training-ready formats for multiple agent frameworks. We performed supervised finetuning on the unified data, and demonstrated an average performance gain of $\sim$20\% over
corresponding base models, and delivers state-of-the-art or near-SOTA performance on standard coding, browsing, tool use, and research benchmarks, without domain-specific tuning. All code and data are released publicly, in the hope that ADP could help lower the barrier to standardized, scalable, and reproducible agent training.

---

## 35. OpenApps: Simulating Environment Variations to Measure UI Agent Reliability

**OpenReview**: [https://openreview.net/forum?id=cj1MAx7lKs](https://openreview.net/forum?id=cj1MAx7lKs)

**Authors**: Karen Ullrich (Meta AI), Jingtong Su, Claudia Shi (Columbia University), Arjun Subramonian, Amir Bar (Facebook), Ivan Evtimov (Facebook), Nikolaos Tsilivis (New York University), Randall Balestriero (Brown University), Julia Kempe, Mark Ibrahim (Facebook AI Research (FAIR) Meta)

**Institutions**: Meta AI, Columbia University, Facebook, New York University, Brown University, Facebook AI Research (FAIR) Meta

**Primary Area**: datasets and benchmarks

**Keywords**: reinforcement learning, agents, envrionment, reliability

**TL;DR**: We introduce a new environment, OpenApps, for generating thousands of versions of apps to test UI agent reliability.

**Abstract**: Reliability is key to realizing the promise of autonomous UI-agents, multimodal agents that directly interact with the apps humans use, as users must be able to trust an agent to complete a given task. Current evaluations rely on fixed environments---often clones of existing apps--- which are limited in that they can only shed light on whether or how often an agent can complete a task within a specific environment. When deployed however, agents are likely to encounter variations in app design and content that can affect an agent’s ability to complete a task. To address this blind spot of measuring agent reliability across app variations, we develop OpenApps, a light-weight open-source ecosystem with six apps (messenger, calendar, maps, etc.) that are configurable in appearance and content. OpenApps requires just a single CPU to run, enabling easy generation and deployment of thousands of versions of each app. Specifically, we run more than 10,000 independent evaluations to study reliability across seven leading multimodal agents. We find that while standard reliability within a fixed app is relatively stable, reliability can vary drastically when measured across app variations. Task success rates for many agents can fluctuate by more than 50\% across app variations. For example, Kimi-VL-3B's average success across all tasks fluctuates from 63\% to just 4\% across app versions. We also find agent behaviors such as looping or hallucinating actions can differ drastically depending on the environment configuration. These initial findings highlight the importance of measuring reliability along this new dimension of app variations.

---

## 36. Overparametrization bends the landscape: BBP transitions at initialization in simple Neural Networks

**OpenReview**: [https://openreview.net/forum?id=xDLE5n3x9Y](https://openreview.net/forum?id=xDLE5n3x9Y)

**Authors**: Brandon Livio Annesi (University of Roma "La Sapienza"), Dario Bocchi (University of Roma "La Sapienza"), Chiara Cammarota (University of Roma "La Sapienza")

**Institutions**: University of Roma "La Sapienza"

**Primary Area**: learning theory

**Keywords**: Overparametrization, Loss landscapes, Signal recovery, High-dimensional learning

**TL;DR**: We quantitatively analyze how overparametrization reshapes the high-dimensional loss landscape of a teacher–student setup in random positions, showing it can anticipate and qualitatively alter transitions between successful and failed signal recovery

**Abstract**: High-dimensional non-convex loss landscapes play a central role in the theory of Machine Learning. Gaining insight into how these landscapes interact with gradient-based optimization methods, even in relatively simple models, can shed light on this enigmatic feature of neural networks. In this work, we will focus on a prototypical simple learning problem, which generalizes the Phase Retrieval inference problem by allowing the exploration of overparametrized settings. Using techniques from field theory, we analyze the spectrum of the Hessian at initialization and identify a Baik–Ben Arous–Péché (BBP) transition in the amount of data that separates regimes where the initialization is informative or uninformative about a planted signal of a teacher-student setup. Crucially, we demonstrate how overparameterization can "bend" the loss landscape, shifting the transition point, even reaching the information-theoretic weak-recovery threshold in the large overparameterization limit, while also altering its qualitative nature.
 We distinguish between continuous and discontinuous BBP transitions and support our analytical predictions with simulations, examining how they compare to the finite-N behavior. In the case of discontinuous BBP transitions strong finite-N corrections allow the retrieval of information at a signal-to-noise ratio (SNR) smaller than the predicted BBP transition. In these cases we provide estimates for a new lower SNR threshold that marks the point at which initialization becomes entirely uninformative.

---

## 37. Softmax Transformers are Turing-Complete

**OpenReview**: [https://openreview.net/forum?id=FdkPOHlChS](https://openreview.net/forum?id=FdkPOHlChS)

**Authors**: Hongjian Jiang (Rheinland-Pfälzische Technische Universität), Michael Hahn (Universität des Saarlandes), Georg Zetzsche (MPI-SWS), Anthony Widjaja Lin (MPI-SWS)

**Institutions**: Rheinland-Pfälzische Technische Universität, Universität des Saarlandes, MPI-SWS

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: soft attention, FLaNN, recursively enumerable, Turing-complete, formal languages

**Abstract**: Hard attention Chain-of-Thought (CoT) transformers are known to be Turing-complete. However, it is an open problem whether softmax attention Chain-of-Thought (CoT) transformers are Turing-complete. In this paper, we prove a stronger result that length-generalizable softmax CoT transformers are Turing-complete. 

More precisely, our Turing-completeness proof goes via the CoT extension of the Counting RASP (C-RASP), which correspond to softmax CoT transformers that admit length generalization. We prove Turing-completeness for CoT C-RASP with causal masking over a unary alphabet (more generally, for the letter-bounded languages). While we show that this is actually not Turing-complete for arbitrary languages, we prove that its extension with relative positional encoding is Turing-complete for arbitrary languages. We empirically validate our theoretical results by training transformers for various languages that require complex (non-linear) arithmetic reasoning.

---

## 38. Steering the Herd: A Framework for LLM-based Control of Social Learning

**OpenReview**: [https://openreview.net/forum?id=RtS4UqSmNt](https://openreview.net/forum?id=RtS4UqSmNt)

**Authors**: Raghu Arghal (University of Pennsylvania, University of Pennsylvania), Kevin He, Shirin Saeedi Bidokhti (University of Pennsylvania, University of Pennsylvania), Saswati Sarkar (University of Pennsylvania)

**Institutions**: University of Pennsylvania, University of Pennsylvania, University of Pennsylvania

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Social learning, LLMs, optimal control, information design, dynamic programming

**TL;DR**: We introduce, analyze, and simulate (via LLMs) a model of controlled social learning to study how algorithms can influence social beliefs, decisions, and welfare via information design.

**Abstract**: Algorithms increasingly serve as information mediators -- from social media feeds and targeted advertising to the increasing ubiquity of LLMs. This engenders a joint process where agents combine private, algorithmically-mediated signals with observational learning from peers to arrive at decisions. To study such settings, we introduce a model of controlled sequential social learning in which an information-mediating planner (e.g., an LLM) controls the information structure of agents while they also learn from the decisions of earlier agents. The planner may seek to improve social welfare (an altruistic planner) or to induce a specific action the planner prefers (a biased planner). Our framework presents a new optimization problem for social learning that combines dynamic programming with decentralized action choices and Bayesian belief updates. In this setting, we prove the convexity of the value function and characterize the optimal policies of altruistic and biased planners, which attain desired tradeoffs between the costs they incur and the payoffs they earn from induced agent choices. The characterization reveals that the optimal planner operates in different modes depending on the range of belief values. The modes include investing the maximum allowed resource, not investing any resource, or the investment increasing or decreasing with increase in the belief. Notably, for some ranges of belief the biased planner even intentionally obfuscates the agents' signals. Even under stringent transparency constraints—information parity with individuals, no lying or cherry‑picking, and full observability—we show that information mediation can substantially shift social welfare in either direction. We complement our theory with simulations in which LLMs act as both planner and agents. Notably, the LLM-based planner in our simulations exhibits emergent strategic behavior in steering public opinion that broadly mirrors the trends predicted, though key deviations suggest the influence of non-Bayesian reasoning—consistent with the cognitive patterns of both human users and LLMs trained on human-like data. Together, we establish our framework as a tractable basis for studying the impact and regulation of LLM information mediators that corresponds to real behavior.

---

## 39. Quantitative Bounds for Length Generalization in Transformers

**OpenReview**: [https://openreview.net/forum?id=TLSUIyBIfs](https://openreview.net/forum?id=TLSUIyBIfs)

**Authors**: Zachary Izzo (NEC Labs America), Eshaan Nichani (Princeton University), Jason D. Lee (Princeton University)

**Institutions**: NEC Labs America, Princeton University

**Primary Area**: learning theory

**Keywords**: transformers, theory, length generalization

**TL;DR**: We provide an upper bound on the length of training sequences required for a transformer to generalize to sequences of arbitrary lengths.

**Abstract**: We study the problem of length generalization (LG) in transformers: the ability of a model trained on shorter sequences to maintain performance when evaluated on much longer, previously unseen inputs. Prior work by Huang et al. (2024) established that transformers eventually achieve length generalization once the training sequence length exceeds some finite threshold, but left open the question of how large it must be. In this work, we provide the first quantitative bounds on the required training length for length generalization to occur.
Motivated by previous empirical and theoretical work, we analyze LG in several distinct problem settings: $\ell_\infty$ error control vs. average error control over an input distribution, infinite-precision softmax attention vs. finite-precision attention (which reduces to an argmax) in the transformer, as well as for one- or two-layer transformers. In all scenarios, we prove that LG occurs when the internal behavior of the transformer on longer sequences can be ``simulated'' by its behavior on shorter sequences seen during training. Our bounds give qualitative estimates for the required length of training data required for a transformer to generalize, and we verify these insights empirically. These results sharpen our theoretical understanding of the mechanisms underlying extrapolation in transformers, and formalize the intuition that richer training data is required for generalization on more complex tasks.

---

## 40. AgentGym-RL: An Open-Source Framework to Train LLM Agents for Long-Horizon Decision Making via Multi-Turn RL

**OpenReview**: [https://openreview.net/forum?id=ZgCCDwcGwn](https://openreview.net/forum?id=ZgCCDwcGwn)

**Authors**: Zhiheng Xi (Fudan University), Jixuan Huang (Fudan University), Chenyang Liao (Fudan University), Baodai Huang (Fudan University), Jiaqi Liu (Fudan University), Honglin Guo (Fudan University), yajie yang (Fudan University), Rui Zheng (Fudan University), Junjie Ye (Fudan University), Jiazheng Zhang (Fudan University), Wenxiang Chen (Fudan University), Wei He (Fudan University), Yiwen Ding (Fudan University), Guanyu Li (Fudan University), Zehui Chen (ByteDance Inc.), Zhengyin Du (ByteDance), Xuesong Yao (ByteDance Inc.), Yufei Xu (ByteDance Inc.), Jiecao Chen (ByteDance Inc.), Tao Gui (Fudan University), Zuxuan Wu (Fudan University), Qi Zhang (Fudan University), Xuanjing Huang (Fudan University), Yu-Gang Jiang (Fudan University)

**Institutions**: Fudan University, ByteDance Inc., ByteDance

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: large language model, LLM-based agent, decision-making

**TL;DR**: We present AgentGym-RL, a unified open-source framework for training LLM agents from scratch across diverse and realistic environments, and propose ScalingInter-RL, a staged training strategy for stable long-horizon RL training.

**Abstract**: Training LLM agents for complex multi-turn decision-making tasks requires extensive exploration within their environment, with reinforcement learning (RL) as a natural way. However, the open-source community currently lacks a unified RL framework capable of training agents from scratch across diverse and realistic environments. To bridge this gap, we introduce AgentGym-RL, a modular and decoupled framework specifically designed for RL-based agent in multi-turn decision-making tasks. It offers high flexibility and extensibility, supports mainstream RL algorithms, and spans a broad range of real-world scenarios. To effectively train agents for challenging tasks, we argue that they are required to expand external interactions with the environment, rather than relying solely on internal reasoning. Nevertheless, training agents for long-horizon interaction with vanilla methods often faces challenges like training instability. To this end, we propose ScalingInter-RL, a staged training approach for stable long-horizon RL training. It starts with short-horizon interaction to establish foundational policies and progressively expands them to encourage deeper exploration. Extensive experiments show that agents trained with our method achieve performance on par with—or even surpass—commercial counterparts like OpenAI o3 and Gemini-2.5-Pro across 27 tasks in diverse environments. We share key insights and release the full framework, including code and datasets, to empower the community in building the next generation of intelligent agents. Our framework is available at https://github.com/WooooDyy/AgentGym-RL.

---

## 41. LLM Fingerprinting via Semantically Conditioned Watermarks

**OpenReview**: [https://openreview.net/forum?id=t38nZqqi3Z](https://openreview.net/forum?id=t38nZqqi3Z)

**Authors**: Thibaud Gloaguen (ETH Zurich), Robin Staab (ETHZ - ETH Zurich), Nikola Jovanović (ETHZ - ETH Zurich), Martin Vechev (ETHZ - ETH Zurich)

**Institutions**: ETH Zurich, ETHZ - ETH Zurich

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: LLM, Watermarks, Fingerprinting

**TL;DR**: We introduce a robust LLM fingerprinting method based on semantically conditioned watermarks

**Abstract**: Most LLM fingerprinting methods teach the model to respond to a few fixed queries with predefined atypical responses (keys). This memorization often does not survive common deployment steps such as finetuning or quantization, and such keys can be easily detected and filtered from LLM responses, ultimately breaking the fingerprint. To overcome these limitations we introduce *LLM fingerprinting via semantically conditioned watermarks*, replacing fixed query sets with a broad semantic domain, and replacing brittle atypical keys with a statistical watermarking signal diffused throughout each response. After teaching the model to watermark its responses only to prompts from a predetermined domain e.g., French language, the model owner can use queries from that domain to reliably detect the fingerprint and verify ownership. As we confirm in our thorough experimental evaluation, our fingerprint is both stealthy and robust to all common deployment scenarios.

---

## 42. Universal Inverse Distillation for Matching Models with Real-Data Supervision (No GANs)

**OpenReview**: [https://openreview.net/forum?id=8NuN5UzXLC](https://openreview.net/forum?id=8NuN5UzXLC)

**Authors**: Nikita Maksimovich Kornilov (Applied AI Institute), David Li (Mohamed bin Zayed University of Artificial Intelligence), Tikhon Mavrin (Applied AI Institute ), Aleksei Leonov (Huawei Technologies Ltd.), Nikita Gushchin (Applied AI Institute), Evgeny Burnaev (Applied AI Institute), Iaroslav Sergeevich Koshelev (Huawei Technologies Ltd.), Alexander Korotin

**Institutions**: Applied AI Institute, Mohamed bin Zayed University of Artificial Intelligence, Applied AI Institute , Huawei Technologies Ltd.

**Primary Area**: generative models

**Keywords**: Diffusion models, Flow Matching, Acceleration of diffusion/flow models, Distillation of diffusion/flow models

**Abstract**: While achieving exceptional generative quality, modern diffusion, flow, and other matching models suffer from slow inference, as they require many steps of iterative generation. Recent distillation methods address this by training efficient one-step generators under the guidance of a pre-trained teacher model. However, these methods are often constrained to only one specific framework, e.g., only to diffusion or only to flow models. Furthermore, these methods are naturally data-free, and to benefit from the usage of real data, it is required to use an additional complex adversarial training with an extra discriminator model. In this paper, we present \textbf{RealUID}, a unified distillation framework for all matching models that seamlessly incorporates real data into the distillation procedure without GANs. Our \textbf{RealUID} approach offers a simple theoretical foundation that covers previous distillation methods for Flow Matching and Diffusion models, and is also extended to their modifications, such as Bridge Matching and Stochastic Interpolants.

---

## 43. Mixture-of-Experts Can Surpass Dense LLMs Under Strictly Equal Resource

**OpenReview**: [https://openreview.net/forum?id=oIdzliJAeA](https://openreview.net/forum?id=oIdzliJAeA)

**Authors**: Houyi Li (Fudan University), Ka Man Lo (University of Macau), Shijie Xuyang (Fudan University), Ziqi Wang (University of Science and Technology of China), Wenzhen Zheng (Stepfun), Haocheng Zhang (Fudan University), Zhao Li (Hangzhou Yugu Technology Co., Ltd.), Shuigeng Zhou (Fudan University), Xiangyu Zhang (MEGVII Technology), Daxin Jiang (StepFun)

**Institutions**: Fudan University, University of Macau, University of Science and Technology of China, Stepfun, Hangzhou Yugu Technology Co., Ltd., MEGVII Technology, StepFun

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Large language models (LLM), Pre-training, Mixture-of-Experts (MoE)

**Abstract**: Mixture-of-Experts (MoE) language models dramatically expand model capacity and achieve remarkable performance without increasing per-token compute. However, can MoEs surpass dense architectures under strictly equal resource constraints — that is, when the total parameter count, training compute, and data budget are identical? This question remains under-explored despite its significant practical value and potential. In this paper, we propose a novel perspective and methodological framework to study this question thoroughly. First, we comprehensively investigate the architecture of MoEs and achieve an optimal model design that maximizes the performance. Based on this, we subsequently find that an MoE model with activation rate in an optimal region is able to outperform its dense counterpart under the same total parameter, training compute and data resource. More importantly, this optimal region remains consistent across different model sizes. Although additional amount of data turns out to be a trade-off for enhanced performance, we show that this can be resolved via reusing data. We validate our findings through extensive experiments, training nearly 200 language models at 2B scale and over 50 at 7B scale, cumulatively processing 50 trillion tokens. All code and models will be released publicly.

---

## 44. Pareto-Conditioned Diffusion Models for Offline Multi-Objective Optimization

**OpenReview**: [https://openreview.net/forum?id=S2Q00li155](https://openreview.net/forum?id=S2Q00li155)

**Authors**: Jatan Shrestha (Aalto University), Santeri Heiskanen (Aalto University), Kari Hepola (Tampere University), Severi Rissanen (Aalto University), Pekka Jääskeläinen (Tampere University), Joni Pajarinen (Aalto University)

**Institutions**: Aalto University, Tampere University

**Primary Area**: generative models

**Keywords**: Multi-Objective Optimization, Conditional Diffusion Models

**TL;DR**: We propose Pareto-Conditioned Diffusion (PCD), a novel framework for Offline Multi-Objective Optimization

**Abstract**: Multi-objective optimization (MOO) arises in many real-world applications where trade-offs between competing objectives must be carefully balanced. In the offline setting, where only a static dataset is available, the main challenge is generalizing beyond observed data. We introduce Pareto-Conditioned Diffusion (PCD), a novel framework that formulates offline MOO as a conditional sampling problem. By conditioning directly on desired trade-offs, PCD avoids the need for explicit surrogate models. To effectively explore the Pareto front, PCD employs a reweighting strategy that focuses on high-performing samples and a reference-direction mechanism to guide sampling towards novel, promising regions beyond the training data. Experiments on standard offline MOO benchmarks show that PCD achieves highly competitive performance and, importantly, demonstrates greater consistency across diverse tasks than existing offline MOO approaches.

---

## 45. cadrille: Multi-modal CAD Reconstruction with Reinforcement Learning

**OpenReview**: [https://openreview.net/forum?id=w2tnhhMbXv](https://openreview.net/forum?id=w2tnhhMbXv)

**Authors**: Maksim Kolodiazhnyi (Moscow State University, Lomonosov Moscow State University), Denis Tarasov (ETHZ - ETH Zurich), Dmitrii Zhemchuzhnikov (Lomonosov Moscow State University), Alexander Nikulin (Lomonosov Moscow State University), Ilya Zisman (Innopolis University), Anna Vorontsova (Occipital Inc.), Anton Konushin (Lomonosov Moscow State University), Vladislav Kurenkov (Innopolis University), Danila Rukhovich (Institute of Mechanics)

**Institutions**: Moscow State University, Lomonosov Moscow State University, ETHZ - ETH Zurich, Lomonosov Moscow State University, Innopolis University, Occipital Inc., Institute of Mechanics

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: CAD, 3D reconstruction, LLM, VLM, point cloud, DPO, GRPO

**TL;DR**: A single LLM is capable of reconstructing 3D CAD from point clouds, images, and text. Additionally, online RL significantly boosts reconstruction quality.

**Abstract**: Computer-Aided Design (CAD) plays a central role in engineering and manufacturing, making it possible to create precise and editable 3D models. Using a variety of sensor or user-provided data as inputs for CAD reconstruction can democratize access to design applications. However, most existing methods focus on a single input modality: point clouds, images, or texts, which limits their generalizability and robustness, while few multimodal approaches struggle to deliver competitive quality. Leveraging advances in vision-language models (VLM), we propose $\texttt{cadrille}$, a multimodal CAD reconstruction model that takes inputs of three modalities and outputs executable Python code for CAD reconstruction. Inspired by large language model (LLM) training paradigm, we adopt a two-stage pipeline: supervised fine-tuning (SFT) on large-scale procedurally generated data, followed by reinforcement learning (RL) fine-tuning using online feedback, obtained programatically. In the DeepCAD benchmark, our SFT model outperforms existing single-modal approaches in all three input modalities simultaneously. More importantly, after RL fine-tuning, $\texttt{cadrille}$ sets new state-of-the-art in as many as 10 benchmarks across three modalities and four datasets, including a real-world one.

---

## 46. The Coverage Principle: How Pre-Training Enables Post-Training

**OpenReview**: [https://openreview.net/forum?id=AUXvYQlQLZ](https://openreview.net/forum?id=AUXvYQlQLZ)

**Authors**: Fan Chen (Massachusetts Institute of Technology), Audrey Huang (University of Illinois at Urbana-Champaign), Noah Golowich (Microsoft), Sadhika Malladi (Princeton University), Adam Block (Columbia University), Jordan T. Ash (Microsoft Research), Akshay Krishnamurthy (Research, Microsoft), Dylan J Foster (Microsoft Research)

**Institutions**: Massachusetts Institute of Technology, University of Illinois at Urbana-Champaign, Microsoft, Princeton University, Columbia University, Microsoft Research, Research, Microsoft

**Primary Area**: learning theory

**Keywords**: language models, reinforcement learning, test-time scaling, statistical learning theory

**TL;DR**: We introduce the coverage profile, which captures the relationship between pre- and post-training performance and admits a rich statistical theory

**Abstract**: Language models demonstrate remarkable abilities when pre-trained on large text corpora and fine-tuned for specific tasks, but how and why pre-training shapes the success of the final model remains poorly understood. Notably, although pre-training success is often quantified by cross entropy loss, cross entropy can be poorly predictive of downstream performance. Instead, we provide a theoretical perspective on this relationship through the lens of coverage, which quantifies the probability mass the pre-trained model places on high-quality responses and which is necessary and sufficient for post-training and test-time scaling methods like Best-of-N to succeed. Our main results develop an understanding of the coverage principle, a phenomenon whereby next-token prediction implicitly optimizes toward a model with good coverage. In particular, we uncover a mechanism that explains the power of coverage in predicting downstream performance: coverage generalizes faster than cross entropy, avoiding spurious dependence on problem dependent parameters such as the sequence length. We also study practical algorithmic interventions with provable benefits for improving coverage, including (i) model/checkpoint selection procedures, (ii) gradient normalization schemes, and (iii) test-time decoding strategies.

---

## 47. Conformal Robustness Control: A New Strategy for Robust Decision

**OpenReview**: [https://openreview.net/forum?id=bt4Ahpemmi](https://openreview.net/forum?id=bt4Ahpemmi)

**Authors**: Yang Hu (Shanghai Jiaotong University), Jieren Tan (Nankai University), Changliang Zou (Nankai University), Yajie Bao (Nankai University), Haojie Ren (Shanghai Jiaotong University)

**Institutions**: Shanghai Jiaotong University, Nankai University

**Primary Area**: probabilistic methods (Bayesian methods, variational inference, sampling, UQ, etc.)

**Keywords**: Conformal prediction, Contextual robust optimization, Coverage, Decision robustness

**TL;DR**: This paper develops a new strategy for robust decision problems via conformal robustness control.

**Abstract**: Robust decision-making is crucial in numerous risk-sensitive applications where outcomes are uncertain and the cost of failure is high. Conditional Robust Optimization (CRO) offers a framework for such tasks by constructing prediction sets for the outcome that satisfy predefined coverage requirements and then making decisions based on these sets. Many existing approaches leverage conformal prediction to build prediction sets with guaranteed coverage for CRO. However, since coverage is a *sufficient but not necessary* condition for robustness, enforcing such constraints often leads to overly conservative decisions. To overcome this limitation, we propose a novel framework named Conformal Robustness Control (CRC), that directly optimizes the prediction set construction under explicit robustness constraints, thereby enabling more efficient decisions without compromising robustness. We develop efficient algorithms to solve the CRC optimization problem, and also provide theoretical guarantees on both robustness and optimality. Empirical results show that CRC consistently yields more effective decisions than existing baselines while still meeting the target robustness level.

---

## 48. HATSolver: Learning Gröbner Bases with Hierarchical Attention Transformers

**OpenReview**: [https://openreview.net/forum?id=5C3LljOEGC](https://openreview.net/forum?id=5C3LljOEGC)

**Authors**: Mohamed Malhou (Facebook), Ludovic Perret (Ecole Pour l'Informatique et les Techniques Avancees), Kristin E. Lauter (Facebook)

**Institutions**: Facebook, Ecole Pour l'Informatique et les Techniques Avancees

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: Hierarchical Attention Transformer, Groebner Basis, Symbolic Computation, Multivariate Polynomial Equations

**TL;DR**: Efficient hierarchical attention transformers for learning to solve non-linear equations through by computing groebner bases.

**Abstract**: At NeurIPS 2024, Kera (2311.12904) introduced the use of transformers for computing Groebner bases, a central object in computer algebra with numerous practical applications. In this paper, we improve this approach by applying Hierarchical Attention Transformers (HATs) to solve systems of multivariate polynomial equations via Groebner bases computation. The HAT architecture incorporates a tree-structured inductive bias that enables the modeling of hierarchical relationships present in the data and thus achieves significant computational savings compared to conventional flat attention models. We generalize to arbitrary depths and include a detailed computational cost analysis. Combined with curriculum learning, our method solves instances that are much larger than those in Kera (2311.12904).

---

## 49. It's All Just Vectorization: einx, a Universal Notation for Tensor Operations

**OpenReview**: [https://openreview.net/forum?id=QqvQ3iAdpC](https://openreview.net/forum?id=QqvQ3iAdpC)

**Authors**: Florian Fervers (Fraunhofer IOSB), Sebastian Bullinger (Fraunhofer IOSB), Christoph Bodensteiner (Fraunhofer IOSB), Michael Arens

**Institutions**: Fraunhofer IOSB

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: Tensor notation, tensor programming, einx, einsum, einops

**TL;DR**: We introduce einx, a universal notation for tensor operations, and provide a Python implementation.

**Abstract**: Tensor operations represent a cornerstone of modern scientific computing. However, the Numpy-like notation adopted by predominant tensor frameworks is often difficult to read and write and prone to so-called shape errors, i.a., due to following inconsistent rules across a large, complex collection of operations. Alternatives like einsum and einops have gained popularity, but are inherently restricted to few operations and lack the generality required for a universal model of tensor programming.

To derive a better paradigm, we revisit vectorization as a function for transforming tensor operations, and use it to both lift lower-order operations to higher-order operations, and conceptually decompose higher-order operations to lower-order operations and their vectorization.

Building on the universal nature of vectorization, we introduce einx, a universal notation for tensor operations. It uses declarative, pointful expressions that are defined by analogy with loop notation and represent the vectorization of tensor operations. The notation reduces the large APIs of existing frameworks to a small set of elementary operations, applies consistent rules across all operations, and enables a clean, readable and writable representation in code. We provide an implementation of einx that is embedded in Python and integrates seamlessly with existing tensor frameworks: https://github.com/fferflo/einx

---

## 50. Fast training of accurate physics-informed neural networks without gradient descent

**OpenReview**: [https://openreview.net/forum?id=3VdSuh3sie](https://openreview.net/forum?id=3VdSuh3sie)

**Authors**: Chinmay Datar (Technische Universität München), Taniya Kapoor (Wageningen University & Research), Abhishek Chandra (KTH Royal Institute of Technology), Qing Sun (Technische Universität München), Erik Lien Bolager (Technische Universität München), Iryna Burak (Technische Universität München), Anna Veselovska (Technische Universität München), Massimo Fornasier (Technische Universität München), Felix Dietrich (Technical University Munich)

**Institutions**: Technische Universität München, Wageningen University & Research, KTH Royal Institute of Technology, Technical University Munich

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: physics-informed neural networks, extreme learning machines, random features, partial differential equations, optimization, training, causality, neural PDE solvers, optimization

**TL;DR**: Our approach - Frozen-PINNs addresses longstanding training and accuracy bottlenecks of Physics-Informed Neural Networks (PINNs) and makes PINNs highly realize high-precision, temporal causality, and extremely fast training.

**Abstract**: Solving time-dependent Partial Differential Equations (PDEs) is one of the most critical problems in computational science. While Physics-Informed Neural Networks (PINNs) offer a promising framework for approximating PDE solutions, their accuracy and training speed are limited by two core barriers: gradient-descent-based iterative optimization over complex loss landscapes and non-causal treatment of time as an extra spatial dimension. We present Frozen-PINN, a novel PINN based on the principle of space-time separation that leverages random features instead of training with gradient descent, and incorporates temporal causality by construction. On nine PDE benchmarks, including challenges like extreme advection speeds, shocks, and high-dimensionality, Frozen-PINNs achieve superior training efficiency and accuracy over state-of-the-art PINNs, often by several orders of magnitude. Our work addresses longstanding training and accuracy bottlenecks of PINNs, delivering quickly trainable, highly accurate, and inherently causal PDE solvers, a combination that prior methods could not realize. Our approach challenges the reliance of PINNs on stochastic gradient-descent-based methods and specialized hardware, leading to a paradigm shift in PINN training and providing a challenging benchmark for the community.

---

## 51. In-Place Test-Time Training

**OpenReview**: [https://openreview.net/forum?id=dTWfCLSoyl](https://openreview.net/forum?id=dTWfCLSoyl)

**Authors**: Guhao Feng (Peking University), Shengjie Luo (ByteDance Seed), Kai Hua, Ge Zhang (ByteDance Inc.), Wenhao Huang, Di He (Peking University), Tianle Cai (ByteDance Inc.)

**Institutions**: Peking University, ByteDance Seed, ByteDance Inc.

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Test-time Training, Large language model, LLM

**Abstract**: The static "train then deploy" paradigm fundamentally limits Large Language Models (LLMs) from dynamically adapting their weights in response to continuous streams of new information inherent in real-world tasks. Test-Time Training (TTT) offers a compelling alternative by updating a subset of model parameters (fast weights) at inference time, yet its potential in the current LLM ecosystem is hindered by critical barriers including architectural incompatibility, computational inefficiency and misaligned fast weight objectives for language modeling. In this work, we introduce **In-Place Test-Time Training (In-Place TTT)**, a framework that seamlessly endows LLMs with Test-Time Training ability. In-Place TTT treats the final projection matrix of the ubiquitous MLP blocks as its adaptable fast weights, enabling a ``drop-in" enhancement for LLMs without costly retraining from scratch. Furthermore, we replace TTT's generic reconstruction objective with a tailored, theoretically-grounded objective explicitly aligned with the Next-Token-Prediction task governing autoregressive language modeling. This principled objective, combined with an efficient chunk-wise update mechanism, results in a highly scalable algorithm compatible with context parallelism. Extensive experiments validate our framework's effectiveness: as an in-place enhancement, it enables a 4B-parameter model to achieve superior performance on tasks with contexts up to 128k, and when pretrained from scratch, it consistently outperforms competitive TTT-related approaches. Ablation study results further provide deeper insights on our design choices. Collectively, our results establish In-Place TTT as a promising step towards a paradigm of continual learning in LLMs.

---

## 52. RAIN-Merging: A Gradient-Free Method to Enhance Instruction Following in Large Reasoning Models with Preserved Thinking Format

**OpenReview**: [https://openreview.net/forum?id=PO2iULmu5e](https://openreview.net/forum?id=PO2iULmu5e)

**Authors**: Zhehao Huang (Shanghai Jiaotong University), Yuhang Liu (Shanghai Jiaotong University), Baijiong Lin (The Hong Kong University of Science and Technology (Guangzhou)), Yixin Lou (Shanghai Jiao Tong University), Zhengbao He (Shanghai Jiaotong University), Hanling Tian (Shanghai Jiaotong University), Tao Li (ByteDance Inc.), Xiaolin Huang (Shanghai Jiao Tong University)

**Institutions**: Shanghai Jiaotong University, The Hong Kong University of Science and Technology (Guangzhou), Shanghai Jiao Tong University, ByteDance Inc.

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Large Reasoning Model, Instruction Following, Model Merging, Null-Space

**Abstract**: Large reasoning models (LRMs) excel at a long chain of reasoning but often fail to faithfully follow instructions regarding output format, constraints, or specific requirements. We investigate whether this gap can be closed by integrating an instruction-tuned model (ITM) into an LRM. Analyzing their differences in parameter space, namely task vectors, we find that their principal subspaces are nearly orthogonal across key modules, suggesting a lightweight merging with minimal interference. However, we also demonstrate that naïve merges are fragile because they overlook the output format mismatch between LRMs (with explicit *thinking* and *response* segments) and ITMs (answers-only). We introduce **RAIN-Merging** (Reasoning-Aware Instruction-attention guided Null-space projection Merging), a gradient-free method that integrates instruction following while preserving thinking format and reasoning performance. First, with a small reasoning calibration set, we project the ITM task vector onto the null space of forward features at thinking special tokens, which preserves the LRM's structured reasoning mechanisms. Second, using a small instruction calibration set, we estimate instruction attention to derive module-specific scaling that amplifies instruction-relevant components and suppresses leakage. Across four instruction-following benchmarks and nine reasoning & general capability benchmarks, RAIN-Merging substantially improves instruction adherence while maintaining reasoning quality. The gains are consistent across model scales and architectures, translating to improved performance in agent settings.

---

## 53. To Infinity and Beyond: Tool-Use Unlocks Length Generalization in State Space Models

**OpenReview**: [https://openreview.net/forum?id=sSfep4udCb](https://openreview.net/forum?id=sSfep4udCb)

**Authors**: Eran Malach (Apple), Omid Saremi (Apple), Sinead Williamson (Apple), Arwen Bradley (Apple), Aryo Lotfi (Apple), Emmanuel Abbe (Swiss Federal Institute of Technology Lausanne), Joshua M. Susskind (Apple), Etai Littwin (Apple)

**Institutions**: Apple, Swiss Federal Institute of Technology Lausanne

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: State Space Models, Mamba, Length Generalization, LLM, Transformers

**Abstract**: State Space Models (SSMs) have become the leading alternative to Transformers for sequence modeling tasks. Their primary advantage is efficiency in long-context and long-form generation, enabled by fixed-size memory and linear scaling of computational complexity. We begin this work by showing a simple theoretical result stating that SSMs cannot accurately solve any "truly long-form" generation problem (in a sense we formally define), undermining their main competitive advantage. However, we show that this limitation can be mitigated by allowing SSMs interactive access to external tools. In fact, we show that given the right choice of tool access and problem-dependent training data, SSMs can learn to solve any tractable problem and generalize to arbitrary problem length/complexity (i.e., achieve length generalization). Following our theoretical finding, we demonstrate that tool-augmented SSMs achieve remarkable length generalization on a variety of arithmetic, reasoning, and coding tasks. These findings highlight SSMs as a potential efficient alternative to Transformers in interactive tool-based and agentic settings.

---

## 54. TileLang: Bridge Programmability and Performance in Modern Neural Kernels

**OpenReview**: [https://openreview.net/forum?id=Jb1WkNSfUB](https://openreview.net/forum?id=Jb1WkNSfUB)

**Authors**: Lei Wang (Peking University), Yu Cheng (Peking University), Yining Shi (NVIDIA), Zhiwen Mo (Imperial College London), Zhengju Tang (Peking University), Wenhao Xie (Peking University), Tong Wu (Peking University), Lingxiao Ma (Microsoft Research), Yuqing Xia (Research, Microsoft), Jilong Xue (Microsoft Research), Fan Yang (Research, Microsoft), Zhi Yang (Peking University)

**Institutions**: Peking University, NVIDIA, Imperial College London, Microsoft Research, Research, Microsoft

**Primary Area**: infrastructure, software libraries, hardware, systems, etc.

**Keywords**: compiler; AI; programming model

**TL;DR**: We introduce TileLang, a controllable programming system for fused neural kernels.

**Abstract**: Modern AI algorithms increasingly adopt fused kernels for performance, but implementing them remains complex due to the lack of fine-grained control in existing compilers like Triton. We introduce TileLang, a controllable programming system for fused neural kernels. TileLang provides explicit tile-level primitives for memory placement, data movement, and parallel scheduling. To guide developers in hardware-aware programming, the TileLang introduces two key techniques: tile inference which models tile programs as fused graphs and automatically deduces tile configuration from partial annotations; and tile recommendation that suggests efficient tile configurations based on hardware profiles and heuristics. TileLang makes it easy to express a wide range of fused attention kernels in under 80 lines of Python code, reducing code size by up to 90% compared to manual implementations. Evaluations show that TileLang achieves up to 5x speedup over Triton on NVIDIA H100 and up to 6 on AMD GPUs, demonstrating its ability to bridge programmability and performance.

---

## 55. Navigating the Latent Space Dynamics of Neural Models

**OpenReview**: [https://openreview.net/forum?id=Zunww3FHPU](https://openreview.net/forum?id=Zunww3FHPU)

**Authors**: Marco Fumero (Institute of Science and Technology Austria(ISTA)), Luca Moschella (Apple), Emanuele Rodolà (Sapienza University of Rome), Francesco Locatello (Institute of Science and Technology)

**Institutions**: Institute of Science and Technology Austria(ISTA), Apple, Sapienza University of Rome, Institute of Science and Technology

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Representation learning, latent vector field, autoencoders, memorization and generalization, attractor

**Abstract**: Neural networks transform high-dimensional data into compact, structured representations, often modeled as elements of a lower dimensional latent space. In this paper, we present an alternative interpretation of neural models as dynamical systems acting on the latent manifold. Specifically, we show that autoencoder models implicitly define a _latent vector field_ on the manifold, derived by iteratively applying the encoding-decoding map, without any additional training. We observe that standard training procedures introduce inductive biases that lead to the emergence of attractor points within this vector field.
Drawing on this insight, we propose to leverage the vector field as a _representation_ for the network, providing a novel tool to analyze the properties of the model and the data. This representation enables to: $(i)$ analyze the generalization and memorization regimes of neural models, even throughout training; $(ii)$ extract prior knowledge encoded in the network's parameters from the attractors, without requiring any input data; $(iii)$ identify out-of-distribution samples from their trajectories in the vector field.
We further validate our approach on vision foundation models, showcasing the applicability and effectiveness of our method in real-world scenarios.

---

## 56. Non-Asymptotic Analysis of (Sticky) Track-and-Stop

**OpenReview**: [https://openreview.net/forum?id=vebqP5aioj](https://openreview.net/forum?id=vebqP5aioj)

**Authors**: Riccardo Poiani (Bocconi University), Martino Bernasconi (Bocconi University), Andrea Celli (Bocconi University)

**Institutions**: Bocconi University

**Primary Area**: learning theory

**Keywords**: Multi-Armed Bandit Theory, Pure Exploration, Fixed-Confidence

**TL;DR**: We derive non-asymptotic guarantees for the Track-and-Stop and Sticky Track-and-Stop algorithms.

**Abstract**: In pure exploration problems, a statistician sequentially collects information to answer a question about some stochastic and unknown environment. The probability of returning a wrong answer should not exceed a maximum risk parameter $\delta$ and good algorithms make as few queries to the environment as possible. The Track-and-Stop algorithm is a pioneering method to solve these problems. Specifically, it is well-known that it enjoys asymptotic optimality sample complexity guarantees for $\delta \to 0$ whenever the map from the environment to its correct answers is single-valued (e.g., best-arm identification with a unique optimal arm). The Sticky Track-and-Stop algorithm extends these results to settings where, for each environment, there might exist multiple correct answers (e.g., $\epsilon$-optimal arm identification). Although both methods are optimal in the asymptotic regime, their non-asymptotic guarantees remain unknown. In this work, we fill this gap and provide non-asymptotic guarantees for both algorithms.

---

## 57. The Shape of Adversarial Influence: Characterizing LLM Latent Spaces with Persistent Homology

**OpenReview**: [https://openreview.net/forum?id=v2PglvLLKT](https://openreview.net/forum?id=v2PglvLLKT)

**Authors**: Aideen Fay (Imperial College London), Inés García-Redondo (University of Fribourg), Qiquan Wang (Imperial College London), Haim Dubossarsky (Queen Mary University of London), Anthea Monod (Imperial College London)

**Institutions**: Imperial College London, University of Fribourg, Queen Mary University of London

**Primary Area**: interpretability and explainable AI

**Keywords**: Persistent Homology, Interpretability, Topological Data Analysis, Representation Geometry, Large Language Models, AI Security, Adversarial Attacks, Sparse Autoencoders

**TL;DR**: We use persistent homology to interpret how adversarial inputs reshape LLM representation spaces, resulting in a robust signature that provides multiscale, geometry-aware insights complementary to standard interpretability methods.

**Abstract**: Existing interpretability methods for Large Language Models (LLMs) often fall short by focusing on linear directions or isolated features, overlooking the high-dimensional, nonlinear, and relational geometry within model representations. This study focuses on how adversarial inputs systematically affect the internal representation spaces of LLMs, a topic which remains poorly understood. We propose the application of persistent homology (PH) to measure and understand the geometry and topology of the representation space when the model is under external adversarial influence. Specifically, we use PH to systematically interpret six state-of-the-art models under two distinct adversarial conditions—indirect prompt injection and backdoor fine-tuning—and uncover a consistent topological signature of adversarial influence. Across architectures and model sizes, adversarial inputs induce "topological compression'', where the latent space becomes structurally simpler, collapsing from varied, compact, small-scale features into fewer, dominant, and more dispersed large-scale ones. This topological signature is statistically robust across layers, highly discriminative, and provides interpretable insights into how adversarial effects emerge and propagate. By quantifying the shape of activations and neuron-level information flow, our architecture-agnostic framework reveals fundamental invariants of representational change, offering a complementary perspective to existing interpretability methods.

---

## 58. Hyperparameter Trajectory Inference with Conditional Lagrangian Optimal Transport

**OpenReview**: [https://openreview.net/forum?id=P5B97gZwRb](https://openreview.net/forum?id=P5B97gZwRb)

**Authors**: Harry Amad (University of Cambridge), Mihaela van der Schaar (University of Cambridge)

**Institutions**: University of Cambridge

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: hyperparameter, optimal transport, trajectory inference, manifold learning, interpolation

**Abstract**: Neural networks (NNs) often have critical behavioural trade-offs that are set at design time with hyperparameters—such as reward weighting in reinforcement learning or quantile targets in regression. 
Post-deployment, however, user preferences can evolve, making initially optimal settings undesirable, necessitating expensive retraining. 
To circumvent this, we introduce the task of Hyperparameter Trajectory Inference (HTI), to learn, from observed data, how a NN's conditional output distribution changes as a function of its hyperparameters, such that a surrogate model can approximate the NN at unobserved hyperparameter settings. 
HTI requires extending existing trajectory inference approaches to incorporate conditions, posing key challenges to ensure meaningful inferred conditional probability paths. 
We propose an approach grounded in conditional Lagrangian optimal transport theory, jointly learning the Lagrangian function governing hyperparameter-induced dynamics along with the associated optimal transport maps and geodesics, which form the surrogate model.
We incorporate inductive biases based on the manifold hypothesis and least-action principles into the learned Lagrangian, improving surrogate model feasibility.
We empirically demonstrate that our approach reconstructs NN behaviour across hyperparameter spectrums better than other alternatives, enabling effective inference-time adaptation of NNs.

---

## 59. Vid-LLM: A Compact Video-based 3D Multimodal LLM with Reconstruction–Reasoning Synergy

**OpenReview**: [https://openreview.net/forum?id=l1cLdEjESj](https://openreview.net/forum?id=l1cLdEjESj)

**Authors**: Haijier Chen (Wuhan University), Bo Xu (Wuhan University), Shoujian zhang (Wuhan University), Haoze Liu (Wuhan University), Jiaxuan Lin (Wuhan University), Jingrong Wang (Shenzhen University)

**Institutions**: Wuhan University, Shenzhen University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: video-based 3D MLLM, geometric priors, Cross-Task Adapter, Metric Depth calibration

**Abstract**: Recent developments in Multimodal Large Language Models (MLLMs) have significantly improved Vision–Language (VL) reasoning in 2D domains. However, extending these capabilities to 3D scene understanding remains a major challenge. Existing 3D Multimodal Large Language Models (3D-MLLMs) often depend on 3D data inputs, which limits scalability and generalization. To address this limitation, we propose Vid-LLM, a video-based 3D-MLLM that directly processes video inputs without requiring external 3D data, making it practical for real-world deployment. In our method, the geometric prior are directly used to improve the performance of the sceen perception. To integrate the geometric cues into the MLLM compactly, we design a Cross-Task Adapter (CTA) module to align the 3D geometric priors with the vision-language representations. To ensure geometric consistency and integrity, we introduce a Metric Depth Model that recovers real-scale geometry from the reconstruction outputs. Finally, the model is fine-tuned with a two-stage distillation optimization strategy, realizing fast convergence and stabilizes training. Extensive experiments across diverse benchmarks verified the effectiveness of our method on 3D Question Answering, 3D Dense Captioning and  3D Visual Grounding tasks,  demonstrating the superior multi-task capabilities.

---

## 60. From Markov to Laplace: How Mamba In-Context Learns Markov Chains

**OpenReview**: [https://openreview.net/forum?id=kmK3WSCOCT](https://openreview.net/forum?id=kmK3WSCOCT)

**Authors**: Marco Bondaschi (EPFL - EPF Lausanne), Nived Rajaraman (University of California Berkeley), Xiuying Wei (EPFL - EPF Lausanne), Razvan Pascanu (Mila - Quebec Artificial Intelligence Institute), Caglar Gulcehre (Microsoft), Michael Gastpar (School of Computer and Communication Sciences, EPFL - EPF Lausanne), Ashok Vardhan Makkuva

**Institutions**: EPFL - EPF Lausanne, University of California Berkeley, Mila - Quebec Artificial Intelligence Institute, Microsoft, School of Computer and Communication Sciences, EPFL - EPF Lausanne

**Primary Area**: interpretability and explainable AI

**Keywords**: State-space models, Markov chains, In-context learning, Laplacian smoothing

**TL;DR**: We uncover an interesting phenomenon where a single-layer Mamba represents the Bayes optimal Laplacian smoothing estimator when trained on Markov chains and we demonstrate it theoretically and empirically.

**Abstract**: While transformer-based language models have driven the AI revolution thus far, their computational complexity has spurred growing interest in viable alternatives, such as structured state space sequence models (SSMs) and Selective SSMs. Among these, Mamba (S6) and its variant Mamba-2 have shown remarkable inference speed-ups over transformers while achieving comparable or superior performance on complex language modeling tasks. However, despite these architectural innovations and empirical successes, the fundamental learning capabilities of Mamba remain poorly understood. In this paper, we address this gap by studying in-context learning (ICL) on Markov chains and uncovering an interesting phenomenon: even a single-layer Mamba efficiently learns the in-context Laplacian smoothing estimator, which is both Bayes and minimax optimal. To explain this, we theoretically characterize the representation capacity of Mamba and reveal the fundamental role of convolution in enabling it to represent the optimal Laplacian smoothing. These theoretical insights align strongly with empirical results and, to the best of our knowledge, represent the first formal connection between Mamba and optimal statistical estimators. Finally, we outline promising research directions inspired by these findings.

---

## 61. Huxley-G\"odel Machine: Human-Level Coding Agent Development by an Approximation of the Optimal Self-Improving Machine

**OpenReview**: [https://openreview.net/forum?id=T0EiEuhOOL](https://openreview.net/forum?id=T0EiEuhOOL)

**Authors**: Wenyi Wang (King Abdullah University of Science and Technology), Piotr Piękos (King Abdullah University of Science and Technology), Li Nanbo (King Abdullah University of Science and Technology), Firas Laakom (King Abdullah University of Science and Technology), Yimeng Chen (King Abdullah University of Science and Technology), Mateusz Ostaszewski, Mingchen Zhuge (King Abdullah University of Science and Technology), Jürgen Schmidhuber (King Abdullah University of Science and Technology)

**Institutions**: King Abdullah University of Science and Technology

**Primary Area**: transfer learning, meta learning, and lifelong learning

**Keywords**: Self-Improvement, Coding Agents, G\"odel Machine

**TL;DR**: We propose Huxley-G\"odel Machine, an algorithm guideing self-improvements following an estimation of the value function of G\"odel Machines.

**Abstract**: Recent studies operationalize self-improvement through coding agents that edit their own codebases, grow a tree of self-modifications through expansion strategies that favor higher software engineering benchmark performance, 
considering that this implies more promising subsequent self-modifications. However, we identify a mismatch between the agent’s self-improvement potential (metaproductivity) and its coding benchmark performance, namely the \emph{Metaproductivity-Performance~Mismatch}. Inspired by Huxley’s concept of clade, we propose a metric ($\mathrm{CMP}$) that aggregates the benchmark performances of the \emph{descendants} of an agent as an indicator of its potential for self-improvement. We show that the G\"odel Machine, the optimal self-improving machine, is achieved with access to true $\mathrm{CMP}$. We introduce the Huxley-G\"odel Machine (HGM), which, by estimating $\mathrm{CMP}$ and using it as guidance, searches the tree of self-modifications. On SWE-bench Verified and Polyglot, HGM outperforms prior self-improving coding agent search methods while using less wall-clock time. Moreover, the agent optimized by HGM on SWE-bench Verified outperforms SWE-agent, a leading human-engineered open source coding agent on SWE-bench Lite, where SWE-agent ranks the best on the official leaderboard, when both use the GPT-5-mini backbone, demonstrating that HGM self-improvement indeed enhances genuine coding capability.

---

## 62. Gaia2: Benchmarking LLM Agents on Dynamic and  Asynchronous Environments

**OpenReview**: [https://openreview.net/forum?id=9gw03JpKK4](https://openreview.net/forum?id=9gw03JpKK4)

**Authors**: Romain Froger (Facebook), Pierre Andrews (Meta), Matteo Bettini (University of Cambridge), Amar Budhiraja (Facebook), Ricardo Silveira Cabral (Facebook), Virginie Do (Université Paris Dauphine - PSL), Emilien Garreau (Université Paris-Saclay), Jean-Baptiste Gaya (Facebook), Hugo Laurençon (Ecole Normale Superieure), Maxime Lecanu (Facebook), Kunal Malkan (Facebook), Dheeraj Mekala (University of California, San Diego), Pierre Menard (Ecole Normale Supérieure de Lyon), Gerard Moreno-Torres Bertran (Facebook), Ulyana Piterbarg (Google DeepMind), Mikhail Plekhanov (Facebook), Mathieu Rita (INRIA), Andrey Rusakov (Department of Computer Science, ETHZ - ETH Zurich), Vladislav Vorotilov (Independent), Mengjue Wang (Meta), Ian Yu (The New School), Amine Benhalloum (Ecole Nationale Supérieure de Techniques Avancées), Grégoire Mialon (Facebook), Thomas Scialom (LIP6)

**Institutions**: Facebook, Meta, University of Cambridge, Université Paris Dauphine - PSL, Université Paris-Saclay, Ecole Normale Superieure, University of California, San Diego, Ecole Normale Supérieure de Lyon, Google DeepMind, INRIA, Department of Computer Science, ETHZ - ETH Zurich, Independent, The New School, Ecole Nationale Supérieure de Techniques Avancées, LIP6

**Primary Area**: datasets and benchmarks

**Keywords**: benchmark, agents, rlvr, multi-agent systems, reasoning, large language models, evaluation, framework

**TL;DR**: Gaia2 evaluates LLM agents in asynchronous, dynamic environments with action-level verification, revealing fundamental trade-offs between reasoning, speed, and robustness.

**Abstract**: We introduce **Gaia2**, a benchmark for evaluating large language model agents in realistic, asynchronous environments. Unlike prior static or synchronous evaluations, Gaia2 introduces scenarios where environments evolve independently of agent actions, requiring agents to operate under temporal constraints, adapt to noisy and dynamic events, resolve ambiguity, and collaborate with other agents. Each scenario is paired with a write-action verifier, enabling fine-grained, action-level evaluation and making Gaia2 directly usable for reinforcement learning from verifiable rewards. Our evaluation of state-of-the-art proprietary and open-source models shows that no model dominates across capabilities: GPT-5 (high) reaches the strongest overall score of 42% pass@1 but fails on time-sensitive tasks, Claude-4 Sonnet trades accuracy and speed for cost, Kimi-K2 leads among open-source models with 21% pass@1. These results highlight fundamental trade-offs between reasoning, efficiency, robustness, and expose challenges in closing the “sim2real” gap. Gaia2 is built on a consumer environment with the open-source **Agents Research Environments** platform and designed to be easy to extend. By releasing Gaia2 alongside the foundational ARE framework, we aim to provide the community with a flexible infrastructure for developing, benchmarking, and training the next generation of practical agent systems.

---

## 63. Fast Escape, Slow Convergence: Learning Dynamics of Phase Retrieval under Power-Law Data

**OpenReview**: [https://openreview.net/forum?id=Ae4eZpkXBX](https://openreview.net/forum?id=Ae4eZpkXBX)

**Authors**: Guillaume Braun (RIKEN), Bruno Loureiro (Ecole Normale Supérieure, Ecole Normale Supérieure de Paris), Minh Ha Quang (RIKEN), Masaaki Imaizumi (Kyoto University)

**Institutions**: RIKEN, Ecole Normale Supérieure, Ecole Normale Supérieure de Paris, Kyoto University

**Primary Area**: learning theory

**Keywords**: scaling laws, gradient flow, power-law spectrum, phase retrieval, anisotropic data, learning dynamics

**Abstract**: Scaling laws describe how learning performance improves with data, compute, or training time, and have become a central theme in modern deep learning. We study this phenomenon in a canonical nonlinear model: phase retrieval with anisotropic Gaussian inputs whose covariance spectrum follows a power law. Unlike the isotropic case, where dynamics collapse to a two-dimensional system, anisotropy yields a qualitatively new regime in which an infinite hierarchy of coupled equations governs the evolution of the summary statistics. We develop a tractable reduction that reveals a three-phase trajectory: (i) fast escape from low alignment, (ii) slow convergence of the summary statistics, and (iii) spectral-tail learning in low-variance directions. From this decomposition, we derive explicit scaling laws for the mean-squared error, showing how spectral decay dictates convergence times and error curves. Experiments confirm the predicted phases and exponents. These results provide the first rigorous characterization of scaling laws in nonlinear regression with anisotropic data, highlighting how anisotropy reshapes learning dynamics.

---

## 64. AutoEP: LLMs-Driven Automation of Hyperparameter Evolution for Metaheuristic Algorithms

**OpenReview**: [https://openreview.net/forum?id=hit3hGBheP](https://openreview.net/forum?id=hit3hGBheP)

**Authors**: Zhenxing Xu (National University of Defense Technology), Yizhe Zhang (National University of Defense Technology), Weidong Bao (National University of Defense Technology), Hao Wang (National University of Defense Technology), Ming Chen (Tsinghua University, Tsinghua University), Haoran Ye (Peking University), Wenzheng Jiang (National University of Defense Technology), Hui Yan (National University of Defense Technology), Ji Wang (National University of Defense Technology)

**Institutions**: National University of Defense Technology, Tsinghua University, Tsinghua University, Peking University

**Primary Area**: optimization

**Keywords**: LLMs, Optimization, Metaheuristic algorithm, Automatic Algorithm Design

**Abstract**: Dynamically configuring algorithm hyperparameters is a fundamental challenge in computational intelligence. While learning-based methods offer automation, they suffer from prohibitive sample complexity and poor generalization. We introduce AutoEP, a novel framework that bypasses training entirely by leveraging Large Language Models (LLMs) as zero-shot reasoning engines for algorithm control. AutoEP's core innovation lies in a tight synergy between two components: (1) an online Exploratory Landscape Analysis (ELA) module that provides real-time, quantitative feedback on the search dynamics, and (2) a multi-LLM reasoning chain that interprets this feedback to generate adaptive hyperparameter strategies. This approach grounds high-level reasoning in empirical data, mitigating hallucination. Evaluated on three distinct metaheuristics across diverse combinatorial optimization benchmarks, AutoEP consistently outperforms state-of-the-art tuners, including neural evolution and other LLM-based methods. Notably, our framework enables open-source models like Qwen3-30B to match the performance of GPT-4, demonstrating a powerful and accessible new paradigm for automated hyperparameter design.Our code is available at https://anonymous.4open.science/r/AutoEP-3E11.

---

## 65. On the Wasserstein Geodesic Principal Component Analysis of probability measures

**OpenReview**: [https://openreview.net/forum?id=OJupg4mDjS](https://openreview.net/forum?id=OJupg4mDjS)

**Authors**: Nina Vesseron (Ecole Nationale de la Statistique et de l'Administration Economique), Elsa Cazelles (Institut de Recherche en Informatique de Toulouse), Alice Le Brigant (Université Panthéon-Sorbonne (Paris I)), Klein (Université de Toulouse)

**Institutions**: Ecole Nationale de la Statistique et de l'Administration Economique, Institut de Recherche en Informatique de Toulouse, Université Panthéon-Sorbonne (Paris I), Université de Toulouse

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: wasserstein PCA, optimal transport, deep learning

**Abstract**: This paper focuses on Geodesic Principal Component Analysis (GPCA) on a collection of probability distributions using the Otto-Wasserstein geometry. The goal is to identify geodesic curves in the space of probability measures that best capture the modes of variation of the underlying dataset. We first address the case of a collection of Gaussian distributions, and show how to lift the computations in the space of invertible linear maps. For the more general setting of absolutely continuous probability measures, we leverage a novel approach to parameterizing geodesics in Wasserstein space with neural networks. Finally, we compare to classical tangent PCA through various examples and provide illustrations on real-world datasets.

---

## 66. Discount Model Search for Quality Diversity Optimization in High-Dimensional Measure Spaces

**OpenReview**: [https://openreview.net/forum?id=m6Hv0yZO3n](https://openreview.net/forum?id=m6Hv0yZO3n)

**Authors**: Bryon Tjanaka (University of Southern California), Henry Chen (University of Southern California), Matthew Christopher Fontaine (University of Southern California), Stefanos Nikolaidis (University of Southern California)

**Institutions**: University of Southern California

**Primary Area**: optimization

**Keywords**: quality diversity optimization, black-box optimization, derivative-free optimization, latent space exploration

**TL;DR**: We present a method that enhances exploration in quality diversity (QD) optimization and show how this method enables new applications for QD. Project page: https://discount-models.github.io/

**Abstract**: Quality diversity (QD) optimization searches for a collection of solutions that optimize an objective while attaining diverse outputs of a user-specified, vector-valued measure function. Contemporary QD algorithms are typically limited to low-dimensional measures because high-dimensional measures are prone to distortion, where many solutions found by the QD algorithm map to similar measures. For example, the state-of-the-art CMA-MAE algorithm guides measure space exploration with a histogram in measure space that records so-called discount values. However, CMA-MAE stagnates in domains with high-dimensional measure spaces because solutions with similar measures fall into the same histogram cell and hence receive the same discount value. To address these limitations, we propose Discount Model Search (DMS), which guides exploration with a model that provides a smooth, continuous representation of discount values. In high-dimensional measure spaces, this model enables DMS to distinguish between solutions with similar measures and thus continue exploration. We show that DMS facilitates new capabilities for QD algorithms by introducing two new domains where the measure space is the high-dimensional space of images, which enables users to specify their desired measures by providing a dataset of images rather than hand-designing the measure function. Results in these domains and on high-dimensional benchmarks show that DMS outperforms CMA-MAE and other existing black-box QD algorithms.

---

## 67. Decentralized Attention Fails Centralized Signals: Rethinking Transformers for Medical Time Series

**OpenReview**: [https://openreview.net/forum?id=oZJFY2BQt2](https://openreview.net/forum?id=oZJFY2BQt2)

**Authors**: Guoqi Yu, Juncheng Wang (The Hong Kong Polytechnic University), Chen Yang (Hong Kong Polytechnic University), Jing Qin (Hong Kong Polytechnic University), Angelica I Aviles-Rivero (Tsinghua University), Shujun Wang (Hong Kong Polytechnic University)

**Institutions**: The Hong Kong Polytechnic University, Hong Kong Polytechnic University, Tsinghua University

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: EEG, ECG, Deep learning, Transformer

**TL;DR**: We propose a centralized module to replace decentralized attention in Transformer for centralized medical time series like EEG and ECG.

**Abstract**: Accurate analysis of Medical time series (MedTS) data, such as Electroencephalography (EEG) and Electrocardiography (ECG), plays a pivotal role in healthcare applications, including the diagnosis of brain and heart diseases. MedTS data typically exhibits two critical patterns: **temporal dependencies** within individual channels and **channel dependencies** across multiple channels. While recent advances in deep learning have leveraged Transformer-based models to effectively capture temporal dependencies, they often struggle to model channel dependencies. This limitation stems from a structural mismatch: ***MedTS signals are inherently centralized, whereas the Transformer's attention is decentralized***, making it less effective at capturing global synchronization and unified waveform patterns. To bridge this gap, we propose **CoTAR** (Core Token Aggregation-Redistribution), a centralized MLP-based module tailored to replace the decentralized attention. Instead of allowing all tokens to interact directly, as in attention, CoTAR introduces a global core token that acts as a proxy to facilitate the inter-token interaction, thereby enforcing a centralized aggregation and redistribution strategy. This design not only better aligns with the centralized nature of MedTS signals but also reduces computational complexity from quadratic to linear. Experiments on five benchmarks validate the superiority of our method in both effectiveness and efficiency, achieving up to a **12.13%** improvement on the APAVA dataset, with merely 33% memory usage and 20% inference time compared to the previous state-of-the-art. Code and all training scripts are available in this [**Link**](https://github.com/Levi-Ackman/TeCh).

---

## 68. Why Low-Precision Transformer Training Fails: An Analysis on Flash Attention

**OpenReview**: [https://openreview.net/forum?id=0jHyEKHDyx](https://openreview.net/forum?id=0jHyEKHDyx)

**Authors**: Haiquan Qiu (Tsinghua University, Tsinghua University), Quanming Yao (Tsinghua University)

**Institutions**: Tsinghua University, Tsinghua University, Tsinghua University

**Primary Area**: optimization

**Keywords**: low-precision training, transformer, attention

**TL;DR**: For the first time, we mechanistically explain why low-precision training with flash attention fails, identifying a vicious cycle of rounding errors and proposing a simple, effective fix.

**Abstract**: The pursuit of computational efficiency has driven the adoption of low-precision formats for training transformer models. However, this progress is often hindered by notorious training instabilities. This paper provides the first mechanistic explanation for a long-standing and unresolved failure case where training with flash attention in low-precision settings leads to catastrophic loss explosion. Our in-depth analysis reveals that the failure is not a random artifact but caused by two intertwined phenomena: the emergence of similar low-rank representations within the attention mechanism and the compounding effect of biased rounding errors inherent in low-precision arithmetic. We demonstrate how these factors create a vicious cycle of error accumulation that corrupts weight updates, ultimately derailing the training dynamics. To validate our findings, we introduce a minimal modification to the flash attention that mitigates the bias in rounding errors. This simple change stabilizes the training process, confirming our analysis and offering a practical solution to this persistent problem. Code is available at https://github.com/ucker/why-low-precision-training-fails.

---

## 69. Overcoming Joint Intractability with Lossless Hierarchical Speculative Decoding

**OpenReview**: [https://openreview.net/forum?id=LaVrNaBNwM](https://openreview.net/forum?id=LaVrNaBNwM)

**Authors**: Yuxuan Zhou (Universität Mannheim), Fei Huang (Alibaba Group US), Heng Li (Carnegie Mellon University), Fengyi Wu, Tianyu Wang (Georgia Institute of Technology), jianwei zhang (Alibaba Group), Junyang Lin (Alibaba Group), Zhi-Qi Cheng (University of Washington)

**Institutions**: Universität Mannheim, Alibaba Group US, Carnegie Mellon University, Georgia Institute of Technology, Alibaba Group, University of Washington

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Speculative Decoding, Joint Intractability, Lossless Verification

**Abstract**: Verification is a key bottleneck in improving inference speed while maintaining distribution fidelity in Speculative Decoding. Recent work has shown that sequence-level verification leads to a higher number of accepted tokens compared to token-wise verification. However, existing solutions often rely on surrogate approximations or are constrained by partial information, struggling with joint intractability. In this work, we propose Hierarchical Speculative Decoding (HSD), a provably lossless verification method that significantly boosts the expected number of accepted tokens and overcomes joint intractability by balancing excess and deficient mass across accessible branches. Through extensive large-scale experiments, we show that HSD consistently improves acceptance rates, especially with longer draft sequences. Its strong explainability and generality further highlight the potential for integration into a wide range of speculative decoding frameworks.

---

## 70. In-The-Flow Agentic System Optimization for Effective Planning and Tool Use

**OpenReview**: [https://openreview.net/forum?id=Mf5AleTUVK](https://openreview.net/forum?id=Mf5AleTUVK)

**Authors**: Zhuofeng Li (Texas A&M University - College Station), Haoxiang Zhang (University of California, San Diego), Seungju Han (Computer Science Department, Stanford University), Sheng Liu (Stanford University), Jianwen Xie, Yu Zhang (Texas A&M University - College Station), Yejin Choi (Computer Science Department, Stanford University), James Zou (Stanford University), Pan Lu (Stanford University)

**Institutions**: Texas A&M University - College Station, University of California, San Diego, Computer Science Department, Stanford University, Stanford University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Reinforcement Learning, Large Language Models, Agentic Systems, Tool Use, Planning, On-policy Optimization, Sparse Rewards

**TL;DR**: We introduce AgentFlow, a trainable agentic system, and Flow-GRPO, an on-policy RL algorithm that optimizes the planner "in-the-flow" by broadcasting a final outcome reward to all steps, enabling effective long-horizon planning and tool use.

**Abstract**: Outcome-driven reinforcement learning has advanced reasoning in large language models (LLMs), but prevailing tool-augmented approaches train a single, monolithic policy that interleaves thoughts and tool calls under full context; this scales poorly with long horizons and diverse tools and generalizes weakly to new scenarios. Agentic systems offer a promising alternative by decomposing work across specialized modules, yet most remain training-free or rely on offline training decoupled from the live dynamics of multi-turn interaction. We introduce AgentFlow, a trainable, *in-the-flow* agentic framework that coordinates four modules (planner, executor, verifier, generator) through an evolving memory and directly optimizes its planner inside the multi-turn loop. To train on-policy in live environments, we propose *Flow-based Group Refined Policy Optimization* (Flow-GRPO), which tackles long-horizon, sparse-reward credit assignment by converting multi-turn optimization into a sequence of tractable single-turn policy updates. It broadcasts a single, verifiable trajectory-level outcome to every turn to align local planner decisions with global success and stabilizes learning with group-normalized advantages. Across ten benchmarks, AgentFlow with a 7B-scale backbone outperforms top-performing baselines with average accuracy gains of 14.9% on search, 14.0% on agentic, 14.5% on mathematical, and 4.1% on scientific tasks, even surpassing larger proprietary models like GPT-4o. Further analyses confirm the benefits of in-the-flow optimization, showing improved planning, enhanced tool-calling reliability, and positive scaling with model size and reasoning turns.

---

## 71. What's In My Human Feedback? Learning Interpretable Descriptions of Preference Data

**OpenReview**: [https://openreview.net/forum?id=sC6A1bFDUt](https://openreview.net/forum?id=sC6A1bFDUt)

**Authors**: Rajiv Movva (University of California, Berkeley), Smitha Milli (Meta FAIR), Sewon Min (University of California, Berkeley), Emma Pierson (University of California, Berkeley)

**Institutions**: University of California, Berkeley, Meta FAIR

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: rlhf, explaining datasets, interpretability, reward modeling, personalization

**TL;DR**: We present WIMHF, a method to describe the preferences encoded by human feedback; produce insights from seven widely-used datasets; and show that the method enables new approaches to data curation and personalization.

**Abstract**: Preference data is widely used for aligning language models, but remains largely opaque. While prior work has studied specific aspects of annotator preference (e.g., length or sycophancy), automatically inferring preferences without pre-specifying hypotheses remains challenging. We introduce *What's In My Human Feedback* (WIMHF), a method that produces human-interpretable, natural language features from preference data using sparse autoencoders. We show that a sparse set of interpretable features can account for two-thirds of the preference signal achieved by black-box models. Applying WIMHF to 7 widely-used datasets, we precisely characterize both (1) which preferences are even possible to measure from each dataset and (2) which preferences humans actually display. WIMHF surfaces preferences that are unintentional or even actively harmful, like a preference for toxic outputs in Chatbot Arena. We show how these findings enable *interpretable data curation*: re-labeling the examples that contain the harmful preference yields large safety gains (+37%) with no cost to general performance. We also demonstrate a new approach to *personalization*: on the Community Alignment dataset, we identify preferences that are subjective across annotators, and use the features as interpretable knobs to adjust model behavior along these axes.

---

## 72. SimuHome: A Temporal- and Environment-Aware Benchmark for Smart Home LLM Agents

**OpenReview**: [https://openreview.net/forum?id=LCS1WsGvha](https://openreview.net/forum?id=LCS1WsGvha)

**Authors**: Gyuhyeon Seo (Seoul National University), Jungwoo Yang (Seoul National University), Junseong Pyo (Hanyang Universty), Nalim Kim (Pohang University of Science and Technology), Jonggeun Lee (Seoul National University), Yohan Jo (Seoul National University)

**Institutions**: Seoul National University, Hanyang Universty, Pohang University of Science and Technology

**Primary Area**: datasets and benchmarks

**Keywords**: smart home, simulator, language model, language agent, benchmark

**Abstract**: Large Language Model (LLM) agents excel at multi-step, tool-augmented tasks. However, smart homes introduce distinct challenges, requiring agents to handle latent user intents, temporal dependencies, device constraints, scheduling, and more.
The main bottlenecks for developing smart home agents with such capabilities include the lack of a realistic simulation environment where agents can interact with devices and observe the results, as well as a challenging benchmark to evaluate them.
To address this, we introduce $\textbf{SimuHome}$, a time-accelerated home environment that simulates smart devices, supports API calls, and reflects changes in environmental variables.
By building the simulator on the Matter protocol, the global industry standard for smart home communication, SimuHome provides a high-fidelity environment, and agents validated in SimuHome can be deployed on real Matter-compliant devices with minimal adaptation.
We provide a challenging benchmark of 600 episodes across twelve user query types that require the aforementioned capabilities.
Our evaluation of 16 agents under a unified ReAct framework reveals distinct capabilities and limitations across models. Models under 7B parameters exhibited negligible performance across all query types. Even GPT-4.1, the best-performing standard model, struggled with implicit intent inference, state verification, and particularly temporal scheduling. While reasoning models such as GPT-5.1 consistently outperformed standard models on every query type, they required over three times the average inference time, which can be prohibitive for real-time smart home applications. This highlights a critical trade-off between task performance and real-world practicality. We will release our code and dataset upon publication of the paper.

---

## 73. Reasoning with Sampling: Your Base Model is Smarter Than You Think

**OpenReview**: [https://openreview.net/forum?id=Vsgq2ldr4K](https://openreview.net/forum?id=Vsgq2ldr4K)

**Authors**: Aayush Karan (Harvard University), Yilun Du (Google)

**Institutions**: Harvard University, Google

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLMs, reasoning, MCMC, sampling, inference-time compute

**TL;DR**: We find a training-free sampling algorithm that achieves reasoning boosts on base models comparable to those obtained by RL techniques.

**Abstract**: Frontier reasoning models have exhibited incredible capabilities across a wide array of disciplines, driven by posttraining large language models (LLMs) with reinforcement learning (RL). However, despite the widespread success of this paradigm, much of the literature has been devoted to disentangling truly novel behaviors that emerge during RL but are not present in the base models. In our work, we approach this question from a different angle, instead asking whether comparable reasoning capabilities can be elicited from base models at inference time by pure sampling, without any additional training. Inspired by Markov chain Monte Carlo (MCMC) techniques for sampling from sharpened distributions, we propose a simple iterative sampling algorithm leveraging the base models' own likelihoods. Over different base models, we show that our algorithm offers substantial boosts in reasoning that nearly match and even outperform those from RL on a wide variety of single-shot tasks, including MATH500, HumanEval, and GPQA. Moreover, our sampler avoids the collapse in diversity over multiple samples that is characteristic of RL-posttraining. Crucially, our method does not require training, curated datasets, or a verifier, suggesting broad applicability beyond easily verifiable domains.

---

## 74. Learning to Segment for Vehicle Routing Problems

**OpenReview**: [https://openreview.net/forum?id=pN261iTKvr](https://openreview.net/forum?id=pN261iTKvr)

**Authors**: Wenbin Ouyang (Massachusetts Institute of Technology), Sirui Li (Microsoft Research), Yining Ma (Massachusetts Institute of Technology), Cathy Wu (Massachusetts Institute of Technology)

**Institutions**: Massachusetts Institute of Technology, Microsoft Research

**Primary Area**: optimization

**Keywords**: Learning-Guided Optimization, Vehicle Routing Problem

**Abstract**: Iterative heuristics are widely recognized as state-of-the-art for Vehicle Routing Problems (VRPs). In this work, we exploit a critical observation: a large portion of the solution remains stable, i.e., unchanged across search iterations, causing redundant computations, especially for large-scale VRPs with long subtours. To address this, we pioneer the formal study of the First-Segment-Then-Aggregate
(FSTA) decomposition technique to accelerate iterative solvers. FSTA preserves stable solution segments during the search, aggregates nodes within each segment into fixed hypernodes, and focuses the search only on unstable portions. Yet, a key challenge lies in identifying which segments should be aggregated. To this end, we introduce Learning-to-Segment (L2Seg), a novel neural framework to intelligently
differentiate potentially stable and unstable portions for FSTA decomposition. We present three L2Seg variants: non-autoregressive (globally comprehensive but locally indiscriminate), autoregressive (locally refined but globally deficient), and their synergy. Empirical results on CVRP and VRPTW show that L2Seg accelerates state-of-the-art solvers by 2x to 7x. We further provide in-depth analysis showing why synergy achieves the best performance. Notably, L2Seg is compatible with traditional, learning-based, and hybrid solvers, while supporting various VRPs.

---

## 75. WAVE: Learning Unified & Versatile Audio-Visual Embeddings with Multimodal LLM

**OpenReview**: [https://openreview.net/forum?id=MiV3WXDYJb](https://openreview.net/forum?id=MiV3WXDYJb)

**Authors**: Changli Tang (Tsinghua University, Tsinghua University), Qinfan Xiao (Tsinghua University), Ke Mei (Tencent), Tianyi Wang (Tencent WeChat), Fengyun Rao (WeChat Vision, Tencent Inc.), Chao Zhang (Tsinghua University)

**Institutions**: Tsinghua University, Tsinghua University, Tsinghua University, Tencent, Tencent WeChat, WeChat Vision, Tencent Inc.

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: audio-visual embeddings, multimodal LLMs, video retrieval

**TL;DR**: This paper builds a versatile audio-visual embedding LLM, which can not only achieve any-to-any retrieval but also generate prompt-aware embeddings.

**Abstract**: While embeddings from multimodal large language models (LLMs) excel as general-purpose representations, their application to dynamic modalities like audio and video remains underexplored. We introduce WAVE (\textbf{u}nified \& \textbf{v}ersatile \textbf{a}udio-\textbf{v}isual \textbf{e}mbeddings), the first LLM-based embedding that creates a unified representation space for text, audio, and video modalities. WAVE employs a novel hierarchical feature fusion strategy and a joint multi-modal, multi-task training approach to enable two key capabilities: any-to-any cross-modal retrieval and the generation of prompt-aware embeddings tailored to user instructions. Experimentally, WAVE sets a new state-of-the-art on the MMEB-v2 video benchmark and achieves superior results in audio and video-to-audio retrieval. Its prompt-aware nature also yields remarkable performance in multimodal question answering, significantly outperforming existing embedding models. Ablation studies validate our joint training strategy, demonstrating improved performance across all modalities.  With a newly introduced benchmark for versatile audio-visual learning, WAVE opens up broad possibilities for cross-modal, any-to-any applications. Our code and checkpoints are released at \href{https://github.com/TCL606/WAVE}{https://github.com/TCL606/WAVE}.

---

## 76. mCLM: A Modular Chemical Language Model that Generates Functional and Makeable Molecules

**OpenReview**: [https://openreview.net/forum?id=r2HG3xOMJI](https://openreview.net/forum?id=r2HG3xOMJI)

**Authors**: Carl Edwards (Genentech), Chi Han (University of Illinois, Urbana Champaign), Gawon Lee (University of Illinois at Urbana-Champaign), Thao Nguyen (University of Illinois at Urbana-Champaign), Sara Szymkuć (Allchemy Inc), Chetan Kumar Prasad (University of Illinois at Urbana-Champaign), Bowen Jin (University of Illinois at Urbana-Champaign), Jiawei Han (University of Illinois at Urbana-Champaign (UIUC)), Ying Diao (University of Illinois at Urbana-Champaign), Ge Liu (University of Illinois at Urbana-Champaign), Hao Peng (University of Illinois Urbana-Champaign), Bartosz Andrzej Grzybowski (Ulsan National Institute of Science and Technology), Martin D. Burke (University of Illinois at Urbana-Champaign), Heng Ji (University of Illinois, Urbana-Champaign)

**Institutions**: Genentech, University of Illinois, Urbana Champaign, University of Illinois at Urbana-Champaign, Allchemy Inc, University of Illinois at Urbana-Champaign (UIUC), University of Illinois Urbana-Champaign, Ulsan National Institute of Science and Technology, University of Illinois, Urbana-Champaign

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: molecule-language multimodality, language model, molecule tokenization, molecule generation

**TL;DR**: We propose mCLM: a bilingual, modular Chemical-Language Model that understands both natural language descriptions of functions and molecular blocks; mCLM front-loads synthesizability while improving the functions of molecules in a principled manner.

**Abstract**: Despite their ability to understand chemical knowledge, large language models (LLMs) remain limited in their capacity to propose novel molecules with desired functions (e.g., drug-like properties). In addition, the molecules that LLMs propose can often be challenging to make, and are almost never compatible with automated synthesis approaches. To better enable the discovery of functional small molecules, LLMs need to learn a new molecular language that is more effective in predicting properties and inherently synced with automated synthesis technology. Current molecule LLMs are limited by representing molecules based on atoms. In this paper, we argue that just like tokenizing texts into meaning-bearing (sub-)word tokens instead of characters, molecules should be tokenized at the level of functional building blocks, i.e., parts of molecules that bring unique functions and serve as effective building blocks for real-world automated laboratory synthesis. This motivates us to propose mCLM, a modular Chemical-Language Model that comprises a bilingual language model that understands both natural language descriptions of functions and molecular blocks. mCLM front-loads synthesizability considerations while improving the predicted functions of molecules in a principled manner. Experiments on 430 FDA-approved drugs showed that mCLM is capable of significantly improving chemical functions critical to determining drug potentials. mCLM, with only 3B parameters, also achieves improvements in synthetic accessibility relative to 7 other leading generative AI methods including GPT-5. When tested on 122 out-of-distribution medicines using only building blocks/tokens that are compatible with automated modular synthesis, mCLM outperforms all baselines in property scores and synthetic accessibility. mCLM can also reason on multiple functions and iteratively self-improve to rescue drug candidates that failed late in clinical trials (“fallen angels”).

---

## 77. Seeing Through the Brain: New Insights from Decoding Visual Stimuli with fMRI

**OpenReview**: [https://openreview.net/forum?id=88ZLp7xYxw](https://openreview.net/forum?id=88ZLp7xYxw)

**Authors**: Zheng Huang, Enpei Zhang (Dartmouth College), Yinghao Cai (Dartmouth College), Weikang Qiu, Carl Yang (Emory University), Elynn Chen (New York University), Xiang Zhang (University of North Carolina at Charlotte), Rex Ying (Yale University), Dawei Zhou (Virginia Polytechnic Institute and State University), Yujun Yan (Dartmouth College)

**Institutions**: Dartmouth College, Emory University, New York University, University of North Carolina at Charlotte, Yale University, Virginia Polytechnic Institute and State University

**Primary Area**: applications to neuroscience & cognitive science

**Keywords**: Neuroscience, Functional Magnetic Resonance Imaging, Image reconstruction, Reconstruction

**TL;DR**: We present PRISM, a framework to decode visual stimuli from fMRI with language model alignment

**Abstract**: Understanding how the brain encodes visual information is a central challenge in neuroscience and machine learning. A promising approach is to reconstruct visual stimuli—essentially images—from functional Magnetic Resonance Imaging (fMRI) signals. This involves two stages: transforming fMRI signals into a latent space and then using a pre-trained generative model to reconstruct images. The reconstruction quality depends on how similar the latent space is to the structure of neural activity and how well the generative model produces images from that space. Yet, it remains unclear which type of latent space best supports this transformation and how it should be organized to represent visual stimuli effectively.

We present two key findings. First, fMRI signals are more similar to the text space of a language model than to either a vision-based space or a joint text–image space. Second, text representations and the generative model should be adapted to capture the compositional nature of visual stimuli, including objects, their detailed attributes, and relationships. Building on these insights, we propose PRISM, a model that Projects fMRI sIgnals into a Structured text space as an interMediate representation for visual stimuli reconstruction. It includes an object-centric diffusion module that generates images by composing individual objects to reduce object detection errors, and an attribute–relationship search module that automatically identifies key attributes and relationships that best align with the neural activity.

Extensive experiments on real-world datasets demonstrate that our framework outperforms existing methods, achieving up to an 6% reduction in perceptual loss. These results highlight the importance of using structured text as the intermediate space to bridge fMRI signals and image reconstruction. Codes are available at https://github.com/GraphmindDartmouth/PRISM.

---

## 78. Temporal Sparse Autoencoders: Leveraging the Sequential Nature of Language for Interpretability

**OpenReview**: [https://openreview.net/forum?id=bojVI4l9Kn](https://openreview.net/forum?id=bojVI4l9Kn)

**Authors**: Usha Bhalla, Alex Oesterling (School of Engineering and Applied Sciences, Harvard University), Claudio Mayrink Verdun (Harvard University), Himabindu Lakkaraju (Google), Flavio Calmon (Harvard University)

**Institutions**: School of Engineering and Applied Sciences, Harvard University, Harvard University, Google

**Primary Area**: interpretability and explainable AI

**Keywords**: Interpretability, Dictionary Learning, Machine Learning, Large Language Models

**TL;DR**: We propose that using contextual information to train SAEs will improve their representation of semantic and high-level features.

**Abstract**: Translating the internal representations and computations of models into concepts that humans can understand is a key goal of interpretability. While recent dictionary learning methods such as Sparse Autoencoders (SAEs) provide a promising route to discover human-interpretable features, they often only recover token-specific, noisy, or highly local concepts. We argue that this limitation stems from neglecting the temporal structure of language, where semantic content typically evolves smoothly over sequences. Building on this insight, we introduce Temporal Sparse Autoencoders (T-SAEs), which incorporate a novel contrastive loss encouraging consistent activations of high-level features over adjacent tokens. This simple yet powerful modification enables SAEs to disentangle semantic from syntactic features in a self-supervised manner. Across multiple datasets and models, T-SAEs recover smoother, more coherent semantic concepts without sacrificing reconstruction quality. Strikingly, they exhibit clear semantic structure despite being trained without explicit semantic signal, offering a new pathway for unsupervised interpretability in language models.

---

## 79. VibeVoice: Expressive Podcast Generation with Next-Token Diffusion

**OpenReview**: [https://openreview.net/forum?id=FihSkzyxdv](https://openreview.net/forum?id=FihSkzyxdv)

**Authors**: Zhiliang Peng (Microsoft), Jianwei Yu (Microsoft), Wenhui Wang (Microsoft), Yaoyao Chang (Microsoft), Yutao Sun (Tsinghua University, Tsinghua University), Li Dong (Microsoft Research), Yi Zhu (Research, Microsoft), Weijiang Xu (University of Science and Technology of China), Hangbo Bao (Microsoft), Zehua Wang (Renmin University of China), Shaohan Huang (Microsoft), Yan Xia (Research, Microsoft), Furu Wei (Microsoft Research)

**Institutions**: Microsoft, Tsinghua University, Tsinghua University, Microsoft Research, Research, Microsoft, University of Science and Technology of China, Renmin University of China

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Text-to-Speech; Podcast Generation

**TL;DR**: VibeVoice can synthesize long-form speech for up to 90 minutes (in a 64K context window length) with a maximum of 4 speakers, capturing the authentic conversational vibe and surpassing open-source and proprietary dialogue models.

**Abstract**: Generating long-form, multi-speaker conversational audio like podcasts poses significant challenges for traditional Text-to-Speech (TTS) systems, particularly in scalability, speaker consistency, and natural turn-taking. We present VibeVoice , a novel model designed to synthesize expressive, long-form speech with multiple speakers in a zero-shot manner. A core component of our approach is the continuous speech tokenizers operating at an ultra-low frame rate of 7.5. This tokenizer effectively preserves audio fidelity while significantly boosting computational efficiency for processing long sequences. To facilitate training on authentic conversational dynamics, we have developed an annotation pipeline that generates pseudo transcriptions and turn-taking labels for extensive podcast data. Leveraging this data and our efficient tokenizer, VibeVoice  employs the next-token diffusion framework. This enables VibeVoice  to: (1) synthesize long-form speech (up to 30 minutes) with up to 4 speakers, surpassing the typical 1-2 speaker limits of many prior models; and (2) achieve a high degree of naturalness in turn-taking, pacing, and the rendition of subtle non-lexical cues (such as breaths and lip smacks), which are crucial for listener immersion and capturing the authentic vibe of expressive conversations.

---

## 80. AdAEM: An Adaptively and Automated Extensible Evaluation Method of LLMs' Value Difference

**OpenReview**: [https://openreview.net/forum?id=qNlTH4kYJZ](https://openreview.net/forum?id=qNlTH4kYJZ)

**Authors**: Jing Yao (Microsoft), Shitong Duan (Fudan University), Xiaoyuan Yi (Microsoft Research), Dongkuan Xu (North Carolina State University), Peng Zhang (Fudan University), Tun Lu (Fudan University), Ning Gu (Fudan University), Zhicheng Dou (Renmin University of China), Xing Xie (Microsoft Research Asia)

**Institutions**: Microsoft, Fudan University, Microsoft Research, North Carolina State University, Renmin University of China, Microsoft Research Asia

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: LLM Evaluation, Value Evaluation, Value Alignment, Dynamic Evaluation

**TL;DR**: This paper proposes aa novel dynamic and automated evaluation framework to probe LLMs' value orientations and value differences

**Abstract**: Assessing Large Language Models (LLMs)' underlying value differences enables comprehensive comparison of their misalignment, cultural adaptability, and biases. Nevertheless, current value measurement methods face the informativeness challenge: with often outdated, contaminated, or generic test questions, they can only capture the orientations on comment safety values, e.g., HHH, shared among different LLMs, leading to indistinguishable and uninformative results. To address this problem, we introduce AdAEM, a novel, self-extensible evaluation algorithm for revealing LLMs' inclinations. Distinct from static benchmarks, AdAEM automatically and adaptively generates and extends its test questions. This is achieved by probing the internal value boundaries of a diverse set of LLMs developed across cultures and time periods in an in-context optimization manner. Such a process theoretically maximizes an information-theoretic objective to extract diverse controversial topics that can provide more distinguishable and informative insights about models' value differences. In this way, AdAEM is able to co-evolve with the development of LLMs, consistently tracking their value dynamics. We use AdAEM to generate novel questions and conduct an extensive analysis, demonstrating our method's validity and effectiveness, laying the groundwork for better interdisciplinary research on LLMs' values and alignment.

---

## 81. Omni-Reward: Towards Generalist Omni-Modal Reward Modeling with Free-Form Preferences

**OpenReview**: [https://openreview.net/forum?id=9C4gVbPqSy](https://openreview.net/forum?id=9C4gVbPqSy)

**Authors**: Zhuoran Jin (Institute of Automation, Chinese Academy of Sciences), Hongbang Yuan (Fudan University), Kejian Zhu (Institute of automation, Chinese academy of science), Jiachun Li (Institute of automation, Chinese academy of science), Pengfei Cao (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Yubo Chen (Institute of automation, Chinese academy of science), Kang Liu (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Jun Zhao (Institute of automation, Chinese academy of science)

**Institutions**: Institute of Automation, Chinese Academy of Sciences, Fudan University, Institute of automation, Chinese academy of science, Institute of automation, Chinese academy of science, Chinese Academy of Sciences

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Omni-Modal Models, Reward Models, Alignment

**TL;DR**: We propose Omni-Reward, a step towards universal omni-modal reward modeling with free-form preferences.

**Abstract**: Reward models (RMs) play a critical role in aligning AI behaviors with human preferences, yet they face two fundamental challenges: (1) Modality Imbalance, where most RMs are mainly focused on text and image modalities, offering limited support for video, audio, and other modalities; and (2) Preference Rigidity, where training on fixed binary preference pairs fails to capture the complexity and diversity of personalized preferences. To address the above challenges, we propose Omni-Reward, a step toward generalist omni-modal reward modeling with support for free-form preferences, consisting of: (1) Evaluation: We introduce Omni-RewardBench, the first omni-modal RM benchmark with free-form preferences, covering nine tasks across five modalities including text, image, video, audio, and 3D; (2) Data: We construct Omni-RewardData, a multimodal preference dataset comprising 248K general preference pairs and 69K instruction-tuning pairs for training generalist omni-modal RMs; (3) Model: We propose Omni-RewardModel, which includes both discriminative and generative RMs, and achieves strong performance on Omni-RewardBench as well as other widely used reward modeling benchmarks.

---

## 82. Spherical Watermark: Encryption-Free, Lossless Watermarking for Diffusion Models

**OpenReview**: [https://openreview.net/forum?id=2eAGrunxVz](https://openreview.net/forum?id=2eAGrunxVz)

**Authors**: Xiaoxiao Hu (Fudan University), Jiaqi Jin (Fudan University), Sheng Li (Fudan University), Wanli Peng (China Agricultural University), Xinpeng Zhang (Fudan University), Zhenxing Qian (Fudan University)

**Institutions**: Fudan University, China Agricultural University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: AIGC Watermarking; Diffusion Models;

**TL;DR**: Employing a novel spherical mapping mechanism, we propose a novel lossless watermarking scheme for text-to-image diffusion models.

**Abstract**: Diffusion models have revolutionized image synthesis but raise concerns around content provenance and authenticity. Digital watermarking offers a means of tracing generated media, yet traditional schemes often introduce distributional shifts and degrade visual quality. Recent lossless methods embed watermark bits directly into the latent Gaussian prior without modifying model weights, but still require per-image key storage or heavy cryptographic overhead. In this paper, we introduce Spherical Watermark, an encryption‐free and lossless watermarking framework that integrates seamlessly with diffusion architectures. First, our binary embedding module mixes repeated watermark bits with random padding to form a high-entropy code. Second, the spherical mapping module projects this code onto the unit sphere, applies an orthogonal rotation, and scales by a chi-square-distributed radius to recover exact multivariate Gaussian noise. We theoretically prove that the watermarked noise distribution preserves the target prior up to third-order moments, and empirically demonstrate that it is statistically indistinguishable from a standard multivariate normal distribution. Adopting Stable Diffusion, extensive experiments confirm that Spherical Watermark consistently preserves high visual fidelity while simultaneously improving traceability, computational efficiency, and robustness under attacks, thereby outperforming both lossy and lossless approaches.

---

## 83. Rodrigues Network for Learning Robot Actions

**OpenReview**: [https://openreview.net/forum?id=IZHk6BXBST](https://openreview.net/forum?id=IZHk6BXBST)

**Authors**: Jialiang Zhang (Peking University), Haoran Geng (University of California, Berkeley), Yang You (Stanford University), Congyue Deng (Massachusetts Institute of Technology), Pieter Abbeel (Amazon), Jitendra Malik (Amazon), Leonidas Guibas (Stanford University)

**Institutions**: Peking University, University of California, Berkeley, Stanford University, Massachusetts Institute of Technology, Amazon

**Primary Area**: applications to robotics, autonomy, planning

**Keywords**: Robot learning, Action understanding, Neural architecture

**TL;DR**: We design a new neural network, the Rodrigues Network (RodriNet), that addresses the kinematic structural priors in articulated robot action learning.

**Abstract**: Understanding and predicting articulated actions is important in robot learning. However, common architectures such as MLPs and Transformers lack inductive biases that reflect the underlying kinematic structure of articulated systems. To this end, we propose the **Neural Rodrigues Operator**, a learnable generalization of the classical forward kinematics operation, designed to inject kinematics-aware inductive bias into neural computation. Building on this operator, we design the **Rodrigues Network (RodriNet)**, a novel neural architecture specialized for processing actions. We evaluate the expressivity of our network on two synthetic tasks on kinematic and motion prediction, showing significant improvements compared to standard backbones. We further demonstrate its effectiveness in two realistic applications: (i) imitation learning on robotic benchmarks with the Diffusion Policy, and (ii) single-image 3D hand reconstruction. Our results suggest that integrating structured kinematic priors into the network architecture improves action learning in various domains.

---

## 84. CyberGym: Evaluating AI Agents' Real-World Cybersecurity Capabilities at Scale

**OpenReview**: [https://openreview.net/forum?id=2YvbLQEdYt](https://openreview.net/forum?id=2YvbLQEdYt)

**Authors**: Zhun Wang, Tianneng Shi, Jingxuan He (University of California, Berkeley), Matthew Cai (University of California, Berkeley), Jialin Zhang (University of California, Berkeley), Dawn Song (University of California Berkeley)

**Institutions**: University of California, Berkeley, University of California Berkeley

**Primary Area**: datasets and benchmarks

**Keywords**: Cybersecurity, AI, Agents

**Abstract**: AI agents have significant potential to reshape cybersecurity, making a thorough assessment of their capabilities critical.
However, existing evaluations fall short, because they are based on small-scale benchmarks and only measure static outcomes, failing to capture the full, dynamic range of real-world security challenges.
To address these limitations, we introduce CyberGym, a large-scale benchmark featuring 1,507 real-world vulnerabilities across 188 software projects.
Adjustable to different vulnerability analysis settings, CyberGym primarily tasks agents with generating a proof-of-concept test that reproduces a vulnerability, given only its text description and the corresponding codebase.
Our extensive evaluation highlights that CyberGym effectively differentiates agents' and models' cybersecurity capabilities.
Even the top-performing combinations only achieve a ~20% success rate, demonstrating the overall difficulty of CyberGym. 
Beyond static benchmarking, we show that CyberGym leads to the discovery of 35 zero-day vulnerabilities and 17 historically incomplete patches.
These results underscore that CyberGym is not only a robust benchmark for measuring AI's progress in cybersecurity but also a platform for creating direct, real-world security impact.

---

## 85. Energy-Based Transformers are Scalable Learners and Thinkers

**OpenReview**: [https://openreview.net/forum?id=ZBj3Qp1bYg](https://openreview.net/forum?id=ZBj3Qp1bYg)

**Authors**: Alexi Gladstone (University of Illinois at Urbana-Champaign), Ganesh Nanduru (University of Virginia, Charlottesville), Md Mofijul Islam (Amazon), Peixuan Han (University of Illinois at Urbana-Champaign), Hyeonjeong Ha (Department of Computer Science, University of Illinois at Urbana-Champaign), Aman Chadha (Apple), Yilun Du (Google), Heng Ji (University of Illinois, Urbana-Champaign), Jundong Li (University of Virginia), Tariq Iqbal (University of Virginia)

**Institutions**: University of Illinois at Urbana-Champaign, University of Virginia, Charlottesville, Amazon, Department of Computer Science, University of Illinois at Urbana-Champaign, Apple, Google, University of Illinois, Urbana-Champaign, University of Virginia

**Primary Area**: generative models

**Keywords**: Energy-Based Models, System 2 Thinking, Reasoning, Verification, Scaling, Transformers, Generative Modeling

**TL;DR**: We introduce Energy-Based Transformers, a scalable new approach for learning how to think from unsupervised learning, generalizing current System 2 Thinking/reasoning approaches.

**Abstract**: Inference-time computation, analogous to human System 2 Thinking, has recently become popular for improving model performance. However, most existing approaches suffer from several limitations: they are modality-specific (e.g., working only in text), problem-specific (e.g., verifiable domains like math and coding), or require additional supervision/training on top of unsupervised pretraining (e.g., verifiers or verifiable rewards). In this paper, we ask the question “Is it possible to generalize these System 2 Thinking approaches, and develop models that learn to think solely from unsupervised learning?” We find the answer is yes, by learning to explicitly verify the compatibility between inputs and candidate-predictions, and then re-framing prediction problems as optimization with respect to this verifier. Specifically, we train Energy-Based Transformers (EBTs)---a new class of Energy-Based Models (EBMs)---to assign an energy value to every input and candidate-prediction, enabling predictions through energy minimization until convergence. To support this approach, we introduce several key techniques for stable and parallelizable training, which enable the emergence of strong System 2 Thinking capabilities and scalable EBMs. Across discrete and continuous modalities, we find EBTs outperform the Transformer++ approach, scaling up to 35% faster during pretraining, and improving inference-time performance by up to 29%. EBTs also surpass Diffusion Transformers on image denoising while requiring 99% fewer forward passes. Moreover, System 2 Thinking with EBTs yields larger performance gains on data that is farther out-of-distribution, and EBTs achieve better results than existing models on most downstream tasks despite achieving the same or worse pretraining performance, enabling EBTs to generalize better than existing approaches. Consequently, EBTs are a flexible and exciting new approach for scaling both the learning and thinking capabilities of models.

---

## 86. Global Resolution: Optimal Multi-Draft Speculative Sampling via Convex Optimization

**OpenReview**: [https://openreview.net/forum?id=gpsczXOsHn](https://openreview.net/forum?id=gpsczXOsHn)

**Authors**: Rahul Krishna Thomas (Columbia University), Arka Pal (Ritual AI)

**Institutions**: Columbia University, Ritual AI

**Primary Area**: probabilistic methods (Bayesian methods, variational inference, sampling, UQ, etc.)

**Keywords**: LLMs, Inference, Optimal Transport, Speculative Decoding

**TL;DR**: We reduce optimal multi-draft speculative sampling to a convex minimization problem, and solve a truncated version to achieve state-of-the-art acceptance with negligible performance degradation.

**Abstract**: Speculative sampling reduces the latency of autoregressive decoding for target model LLMs without sacrificing inference quality, by using a cheap draft model to suggest a candidate token and a verification criterion to accept or resample this token. To improve acceptance and decoding efficiency, recent work has explored the multi-draft extension, where at each step $n$ draft tokens are generated, and the verification criterion is a distribution conditioned on these. When this criterion maximizes the probability of accepting some draft token, it is called the optimal transport (OT). However, finding the OT is difficult, as it is the solution of a linear program (OTLP) in over $V^n$ variables, with $V$ being the vocabulary size. Two recent theoretical works have reframed the OTLP in terms of importance sampling or subset selection. In this work, we prove that these formulations are equivalent to an exponentially large relaxed OTLP, so it remains infeasible to solve. Then, we reverse engineer subset selection to formulate the OTLP as a max-flow problem. With a novel application of polymatroid theory, we reduce the exponentially large OTLP to a convex optimization problem in at most $V$ variables. This allows us to devise an algorithm for optimal $n$-draft speculative sampling when the $n$ tokens are chosen i.i.d. from a single draft model, which can be tuned to arbitrary accuracy. Finally, we measure acceptance rates and algorithm runtimes for various $n$ and top-$k$ draft sampling settings. Our findings give the first multi-draft algorithm with 90\% acceptance and under 100 ms of overhead per generated token with negligible deviation from the target model distribution.

---

## 87. FALCON: Few-step Accurate Likelihoods for Continuous Flows

**OpenReview**: [https://openreview.net/forum?id=FbssShlI4N](https://openreview.net/forum?id=FbssShlI4N)

**Authors**: Danyal Rehman (Mila - Quebec Artificial Intelligence Institute), Tara Akhound-Sadegh (McGill University), Artem Gazizov, Yoshua Bengio (University of Montreal), Alexander Tong (Aithyra)

**Institutions**: Mila - Quebec Artificial Intelligence Institute, McGill University, University of Montreal, Aithyra

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: Generative Models, Flow Matching, Boltzmann Generators, AI for Science

**TL;DR**: Few-step Flow Matching with Accurate Likelihoods for Scalable Boltzmann Generators

**Abstract**: Scalable sampling of molecular states in thermodynamic equilibrium is a long-standing challenge in statistical physics. Boltzmann Generators tackle this problem by pairing a generative model, capable of exact likelihood computation, with importance sampling to obtain consistent samples under the target distribution. Current Boltzmann Generators primarily use continuous normalizing flows (CNFs) trained with flow matching for efficient training of powerful models. However, likelihood calculation for these models is extremely costly, requiring thousands of function evaluations per sample, severely limiting their adoption. In this work, we propose Few-step Accurate Likelihoods for Continuous Flows (FALCON), a method which allows for few-step sampling with a likelihood accurate enough for importance sampling applications by introducing a hybrid training objective that encourages invertibility. We show FALCON outperforms state-of-the-art normalizing flow models for molecular Boltzmann sampling and is \emph{two orders of magnitude faster} than the equivalently performing CNF model.

---

## 88. How Reliable is Language Model Micro-Benchmarking?

**OpenReview**: [https://openreview.net/forum?id=cReExMQLiK](https://openreview.net/forum?id=cReExMQLiK)

**Authors**: Gregory Yauney (University of Southern California), Shahzaib Saqib Warraich (University of Southern California), Swabha Swayamdipta (University of Southern California)

**Institutions**: University of Southern California

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: efficient evaluation, meta-evaluation, language models

**Abstract**: Micro-benchmarking offers a solution to the often prohibitive time and cost of language model development: evaluate on a very small subset of existing benchmarks. Can these micro-benchmarks, however, rank models as consistently as the full benchmarks they replace? And can they rank models more consistently than selecting a random subset of data points? In many scenarios, we find that the answer is no. We introduce a meta-evaluation measure for micro-benchmarking which investigates how well a micro-benchmark can rank two models as a function of their performance difference on the full benchmark. This approach can determine which model pairs can be ranked correctly by a micro-benchmark, allowing for a finer-grained analysis of the trade-off between micro-benchmark size and reliability.
Prior work has suggested selecting as few as 10 examples; we find that no micro-benchmarking method can consistently rank model pairs 3.5 points of accuracy apart on MMLU-Pro or 4 points apart on BIG-bench Hard. In order to consistently rank model pairs with relatively similar performances, we show that often as many as 250 examples must be selected, at which point random sampling is competitive with existing micro-benchmarking methods. When comparing only 8B instruction-tuned models on MMLU-Pro micro-benchmarks with 25 examples, we find that more than half of pairwise comparisons are not likely to be preserved. Our work provides actionable guidance for both micro-benchmark users and developers in navigating the trade-off between evaluation efficiency and reliability.

---

## 89. EditBench: Evaluating LLM Abilities to Perform Real-World Instructed Code Edits

**OpenReview**: [https://openreview.net/forum?id=FtL9eEmU6v](https://openreview.net/forum?id=FtL9eEmU6v)

**Authors**: Wayne Chi (Carnegie Mellon University), Valerie Chen (Carnegie Mellon University), Ryan Shar (Apple), Aditya Mittal (CMU, Carnegie Mellon University), Jenny Liang (School of Computer Science, Carnegie Mellon University), Wei-Lin Chiang (University of California, Berkeley), Anastasios Nikolas Angelopoulos (University of California, Berkeley), Ion Stoica (University of California, Berkeley), Graham Neubig (Carnegie Mellon University), Ameet Talwalkar (Datadog), Chris Donahue (Carnegie Mellon University)

**Institutions**: Carnegie Mellon University, Apple, CMU, Carnegie Mellon University, School of Computer Science, Carnegie Mellon University, University of California, Berkeley, Datadog

**Primary Area**: datasets and benchmarks

**Keywords**: code, real-world, llm, code edit, edit

**TL;DR**: We propose a new benchmark for evaluating an LLM's ability to perform code edits. Our data is gathered from in-the-wild code edits, leading to more realistic problems.

**Abstract**: Instructed code editing, where LLMs directly modify a developer's existing code based on a user instruction, is becoming a widely used interaction mode in AI coding assistants. However, few benchmarks directly evaluate this capability and current datasets often rely on artificial sources. We introduce EditBench, a benchmark for evaluating LLM code editing capabilities  grounded in real-world usage, i.e.,~user instructions and code contexts collected in the wild.  EditBench comprises of 545 problems, multiple natural and programming languages, and a diverse set of real-world use cases, ranging from resolving errors to adding features. EditBench introduces context-dependent problems that require the model to understand code context, highlighted code, and cursor position in addition to the user instruction. We evaluate 40 diverse LLMs and observe that EditBench is a challenging set of problems where only 3 models score over 60\%. We find that model performance varies across different categories of user instructions. Further, we find that varying levels of contextual information greatly affect task success rate, with performance varying up to 11\%, indicating the importance of evaluating with realistic context.

---

## 90. Online Learning and Equilibrium Computation with Ranking Feedback

**OpenReview**: [https://openreview.net/forum?id=lg6H2oJPky](https://openreview.net/forum?id=lg6H2oJPky)

**Authors**: Mingyang Liu (Massachusetts Institute of Technology), Yongshan Chen (Northeastern University), Zhiyuan Fan (Massachusetts Institute of Technology), Gabriele Farina (Massachusetts Institute of Technology), Asuman E. Ozdaglar (Massachusetts Institute of Technology), Kaiqing Zhang (University of Maryland, College Park)

**Institutions**: Massachusetts Institute of Technology, Northeastern University, University of Maryland, College Park

**Primary Area**: learning theory

**Keywords**: Online Learning, Equilibrium Computation, Human Feedback

**TL;DR**: Hardness and positive results for online learning with ranking feedback. Together with equilibrium computation with ranking feedback.

**Abstract**: Online learning in arbitrary and possibly adversarial environments has been extensively studied in sequential decision-making, with a strong connection to equilibrium computation in game theory. Most existing online learning algorithms are based on \emph{numeric} utility feedback from the environment, which may be unavailable in applications with humans in the loop and/or with privacy concerns. In this paper, we study an online learning setting where only a \emph{ranking} of a set of proposed actions is provided to the learning agent at each timestep. We consider both ranking models based on either the \emph{instantaneous} utility at each timestep, or the \emph{time-average} utility until the current timestep, in both \emph{full-information} and \emph{bandit} feedback settings. Focusing on the standard (external-)regret metric, we show that sublinear regret cannot be achieved with the instantaneous utility ranking feedback in general. Moreover, we show that when the ranking model is relatively {deterministic} (\emph{i.e.,} with a small temperature in the Plackett-Luce model), sublinear regret cannot be achieved with the time-average utility ranking feedback, either. We then propose new algorithms to achieve sublinear regret, under the additional assumption that the utility vectors have a sublinear variation. Notably, we also show that when time-average utility ranking is used, such an additional assumption can be avoided in the full-information setting. As a consequence, we show that if all the players follow our algorithms, an approximate coarse correlated equilibrium of a normal-form game can be found through repeated play. Finally, we also validate the effectiveness of our algorithms via numerical experiments.

---

## 91. MC-Search: Evaluating and Enhancing Multimodal Agentic Search with Structured Long Reasoning Chains

**OpenReview**: [https://openreview.net/forum?id=JEGDp1E4OH](https://openreview.net/forum?id=JEGDp1E4OH)

**Authors**: Xuying Ning (University of Illinois at Urbana-Champaign), Dongqi Fu (Meta), Tianxin Wei, Mengting Ai (University of Illinois at Urbana-Champaign), Jiaru Zou, Ting-Wei Li (University of Illinois at Urbana-Champaign), Hanghang Tong (University of Illinois at Urbana-Champaign), Yada Zhu (IBM Research), Hendrik Hamann (State University of New York at Stony Brook), Jingrui He (University of Illinois at Urbana-Champaign)

**Institutions**: University of Illinois at Urbana-Champaign, Meta, IBM Research, State University of New York at Stony Brook

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Multimodal, RAG, Vision-Language, Agent, Benchmark

**Abstract**: With the increasing demand for step-wise, cross-modal, and knowledge-grounded reasoning, multimodal large language models (MLLMs) are evolving beyond the traditional fixed retrieve-then-generate paradigm toward more sophisticated agentic multimodal retrieval-augmented generation (MM-RAG). Existing benchmarks, however, mainly focus on simplified QA with short retrieval chains, leaving adaptive planning and multimodal reasoning underexplored. We present MC-Search, the first benchmark for agentic MM-RAG with long, step-wise annotated reasoning chains spanning five representative reasoning structures. Each example specifies sub-questions, retrieval modalities, supporting facts, and intermediate answers, with fidelity ensured by HAVE (Hop-wise Attribution and Verification of Evidence), resulting in 3,333 high-quality examples averaging 3.7 hops. Beyond answer accuracy, MC-Search introduces new process-level metrics for reasoning quality, stepwise retrieval and planning accuracy. By developing a unified agentic MM-RAG pipeline, we benchmark six leading MLLMs and reveal systematic issues such as over- and under-retrieval and modality-misaligned planning. Finally, we introduce Search-Align, a process-supervised fine-tuning framework leveraging verified reasoning chains, showing that our data not only enables faithful evaluation but also improves planning and retrieval fidelity in open-source MLLMs.

---

## 92. True Self-Supervised Novel View Synthesis is Transferable

**OpenReview**: [https://openreview.net/forum?id=aJJppqAm6r](https://openreview.net/forum?id=aJJppqAm6r)

**Authors**: Thomas Mitchel, Hyunwoo Ryu (Massachusetts Institute of Technology), Vincent Sitzmann (Massachusetts Institute of Technology)

**Institutions**: Massachusetts Institute of Technology

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Novel View Synthesis, Self-Supervised, Unsupervised, Representation Learning

**TL;DR**: The key criterion for determining whether a models is capable of NVS is transferability, and we present the first fully geometry-free and self-supervised model capable of it.

**Abstract**: In this paper, we identify that the key criterion for determining whether a model is truly capable of novel view synthesis (NVS) is transferability: Whether any pose representation extracted from one video sequence can be used to re-render the same camera trajectory in another. We analyze prior work on self-supervised NVS and find that their predicted poses do not transfer: The same set of poses lead
to different camera trajectories in different 3D scenes. Here, we present XFactor, the first geometry-free self-supervised model capable of true NVS. XFactor combines pair-wise pose estimation with a simple augmentation scheme of the inputs and outputs that jointly enables disentangling camera pose from scene content and facilitates geometric reasoning. Remarkably, we show that XFactor achieves transferability with unconstrained latent pose variables, without any 3D inductive biases or concepts from multi-view geometry — such as an explicit parameterization of poses as elements of SE(3). We introduce a new metric to quantify transferability, and through large-scale experiments, we demonstrate that XFactor significantly outperforms prior pose-free NVS transformers, and show that latent poses are highly correlated with real-world poses through probing experiments.

---

## 93. Revela: Dense Retriever Learning via Language Modeling

**OpenReview**: [https://openreview.net/forum?id=e7pAjJZJWb](https://openreview.net/forum?id=e7pAjJZJWb)

**Authors**: Fengyu Cai (Technische Universität Darmstadt), Tong Chen (University of Washington, Seattle), Xinran Zhao (CMU, Carnegie Mellon University), Sihao Chen (Microsoft), Hongming Zhang (Tencent AI Lab Seattle), Tongshuang Wu (School of Computer Science, Carnegie Mellon University), Iryna Gurevych, Heinz Koeppl (TU Darmstadt)

**Institutions**: Technische Universität Darmstadt, University of Washington, Seattle, CMU, Carnegie Mellon University, Microsoft, Tencent AI Lab Seattle, School of Computer Science, Carnegie Mellon University, TU Darmstadt

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Information Retrieval, Unsupervised Learning

**Abstract**: Dense retrievers play a vital role in accessing external and specialized knowledge to augment language models (LMs). Training dense retrievers typically requires annotated query-document pairs, which are costly to create and scarce in specialized domains (e.g., code) or in complex settings (e.g., requiring reasoning). These practical challenges have sparked growing interest in self-supervised retriever learning.
Since LMs are trained to capture token-level dependencies through a self-supervised learning objective (i.e., next token prediction), we can analogously cast retrieval as learning dependencies among chunks of tokens. This analogy naturally leads to the question: How can we adapt self‑supervised learning objectives in the spirit of language modeling to train retrievers?

To answer this question, we introduce Revela, a unified and scalable training framework for self-supervised retriever learning via language modeling. Revela models semantic dependencies among documents by conditioning next token prediction on local and cross-document context through an in-batch attention mechanism. This attention is weighted by retriever-computed similarity scores, enabling the retriever to be optimized as part of language modeling. We evaluate Revela on domain-specific (CoIR), reasoning-intensive (BRIGHT), and general-domain (BEIR) benchmarks across various retriever backbones. Without annotated or synthetic query-document pairs, Revela surpasses larger supervised models and proprietary APIs on both CoIR and BRIGHT. It achieves BEIR's unsupervised SoTA with ~1000x less training data and 10x less compute. Performance increases with batch size and model size, highlighting Revela's scalability and its promise for self‑supervised retriever learning.

---

## 94. LLMs Get Lost In Multi-Turn Conversation

**OpenReview**: [https://openreview.net/forum?id=VKGTGGcwl6](https://openreview.net/forum?id=VKGTGGcwl6)

**Authors**: Philippe Laban (Microsoft), Hiroaki Hayashi (Salesforce), Yingbo Zhou (Salesforce Research), Jennifer Neville (Purdue University)

**Institutions**: Microsoft, Salesforce, Salesforce Research, Purdue University

**Primary Area**: datasets and benchmarks

**Keywords**: multi-turn, underspecification, llm simulation

**TL;DR**: We discover that when LLMs take a wrong turn in a conversation, they get lost and do not recover.

**Abstract**: Large Language Models (LLMs) are conversational interfaces. As such, LLMs have the potential to assist their users not only when they can fully specify the task at hand, but also to help them define, explore, and refine what they need through multi-turn conversational exchange. Although analysis of LLM conversation logs has confirmed that underspecification occurs frequently in user instructions, LLM evaluation has predominantly focused on the single-turn, fully-specified instruction setting. In this work, we perform large-scale simulation experiments to compare LLM performance in single- and multi-turn settings. Our experiments confirm that all the top open- and closed-weight LLMs we test exhibit significantly lower performance in multi-turn conversations than single-turn, with an average drop of 39% across six generation tasks. Analysis of 200,000+ simulated conversations decomposes the performance degradation into two components: a minor loss in aptitude and a significant increase in unreliability. We find that LLMs often make assumptions in early turns and prematurely attempt to generate final solutions, on which they overly rely. In simpler terms, we discover that when LLMs take a wrong turn in a conversation, they get lost and do not recover.

---

## 95. TTSDS2: Resources and Benchmark for Evaluating Human-Quality Text to Speech Systems

**OpenReview**: [https://openreview.net/forum?id=uGai5lYHlV](https://openreview.net/forum?id=uGai5lYHlV)

**Authors**: Christoph Minixhofer (University of Edinburgh, University of Edinburgh), Ondrej Klejch, Peter Bell (University of Edinburgh, University of Edinburgh)

**Institutions**: University of Edinburgh, University of Edinburgh

**Primary Area**: datasets and benchmarks

**Keywords**: speech synthesis, distributional analysis, objective evaluation

**TL;DR**: With TTSDS2, we introduce a metric and benchmark for TTS, covering 14 languages, which consistently correlates with human judgements.

**Abstract**: Evaluation of Text to Speech (TTS) systems is challenging and resource-intensive. Subjective metrics such as Mean Opinion Score (MOS) are not easily comparable between works. Objective metrics are frequently used, but rarely validated against subjective ones. Both kinds of metrics are challenged by recent TTS systems capable of producing synthetic speech indistinguishable from real speech. In this work, we introduce Text to Speech Distribution Score 2 (TTSDS2), a more robust and improved version of TTSDS. Across a range of domains and languages, it is the only one out of 16 compared metrics to correlate with a Spearman correlation above 0.50 for every domain and subjective score evaluated. We also release a range of resources for evaluating synthetic speech close to real speech: A dataset with over 11,000 subjective opinion score ratings; a pipeline for recreating a multilingual test dataset to avoid data leakage; and a benchmark for TTS in 14 languages.

---

## 96. Mamba-3: Improved Sequence Modeling using State Space Principles

**OpenReview**: [https://openreview.net/forum?id=HwCvaJOiCj](https://openreview.net/forum?id=HwCvaJOiCj)

**Authors**: Aakash Lahoti (CMU, Carnegie Mellon University), Kevin Li (Carnegie Mellon University), Berlin Chen (Princeton University), Caitlin Wang (Princeton University), Aviv Bick (Carnegie Mellon University), J Zico Kolter (Carnegie Mellon University), Tri Dao (Princeton University), Albert Gu (Carnegie Mellon University)

**Institutions**: CMU, Carnegie Mellon University, Carnegie Mellon University, Princeton University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: State Space Models, Mamba, LLMs, Subquadratic Models

**TL;DR**: Mamba-3, an inference-first SSM that pushes on core SSM principles: improved discretization for better quality, complex dynamics for new capabilities, and MIMO updates for efficient inference.

**Abstract**: The recent scaling of test-time compute for LLMs has restricted the practical deployment of models to those with strong capabilities that can generate high-quality outputs in an inference-efficient manner. While current Transformer-based models are the standard, their quadratic compute and linear memory bottlenecks have spurred the development of sub-quadratic models with linear-scaling compute with constant memory requirements. However, many recent linear-style models lack certain capabilities or lag behind in quality, and even their linear-time inference is not hardware-efficient. Guided by an inference-first perspective, we introduce three core methodological improvements inspired by the state-space model viewpoint of linear models. We combine a: 1) more expressive recurrence, 2) complex state update rule that enables richer state tracking, and 3) multi-input, multi-output formulation together, resulting in a stronger model that better exploits hardware parallelism during decoding. Together with architectural refinements, our **Mamba-3** model achieves significant gains across retrieval, state-tracking, and downstream language modeling tasks. Our new architecture sets the Pareto-frontier for performance under a fixed inference budget and outperforms strong baselines in a head-to-head comparison.

---

## 97. Is it Thinking or Cheating?  Detecting Implicit Reward Hacking by Measuring Reasoning Effort

**OpenReview**: [https://openreview.net/forum?id=Gk7gLAtVDO](https://openreview.net/forum?id=Gk7gLAtVDO)

**Authors**: Xinpeng Wang (Ludwig-Maximilians-Universität München), Nitish Joshi (Google Deepmind), Barbara Plank (Ludwig-Maximilians-Universität München), Rico Angell (New York University), He He (New York University)

**Institutions**: Ludwig-Maximilians-Universität München, Google Deepmind, New York University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Reward Hacking Detection, Chain-of-Thought Monitoring, Reasoning Faithfulness

**TL;DR**: TRACE detects implicit reward hacking by measuring how quickly truncated reasoning suffices to pass verification, outperforming CoT monitoring and enabling hidden loopholes discovery..

**Abstract**: Reward hacking, where a reasoning model exploits loopholes in a reward function to achieve high rewards without solving the intended task, poses a significant threat. This behavior may be explicit, i.e. verbalized in the model's chain-of-thought (CoT), or implicit, where the CoT appears benign thus bypasses CoT monitors. To detect implicit reward hacking, we propose TRACE (Truncated Reasoning AUC Evaluation). Our key observation is that hacking occurs when exploiting the loophole is easier than solving the actual task.
This means that the model is using less `effort' than required to achieve  high reward. TRACE quantifies effort by measuring how early a model's reasoning becomes sufficient to pass a verifier. We progressively truncate a model's CoT at various lengths and measure the verifier-passing rate at each cutoff. A hacking model, which takes a reasoning shortcut, will achieve a high passing rate with only a small fraction of its CoT, yielding a large area under the accuracy-vs-length curve. TRACE achieves over 65% gains over our strongest 72B CoT monitoring baseline in math, and over 30% gains over a 32B monitoring baseline in code. We further show that TRACE can discover unknown loopholes in the training environment. Overall, TRACE offers a scalable unsupervised approach for oversight where current monitoring methods prove ineffective.

---

## 98. Causal Structure Learning in Hawkes Processes with Complex Latent Confounder Networks

**OpenReview**: [https://openreview.net/forum?id=mA78uXqcnl](https://openreview.net/forum?id=mA78uXqcnl)

**Authors**: Songyao Jin (University of California, San Diego), Biwei Huang (University of California, San Diego)

**Institutions**: University of California, San Diego

**Primary Area**: causal reasoning

**Keywords**: Hawkes processes, causal discovery, latent subprocess model, structure learning, time series

**TL;DR**: We propose a method to uncover causal relationships in partially observed multivariate Hawkes processes, despite the presence of latent subprocesses, using a discrete-time representation and a two-phase iterative algorithm.

**Abstract**: Multivariate Hawkes process provides a powerful framework for modeling temporal dependencies and event-driven interactions in complex systems. While existing methods primarily focus on uncovering causal structures among observed subprocesses, real-world systems are often only partially observed, with latent subprocesses posing significant challenges. In this paper, we show that continuous-time event sequences can be represented by a discrete-time causal model as the time interval shrinks, and we leverage this insight to establish necessary and sufficient conditions for identifying latent subprocesses and the causal influences. Accordingly, we propose a two-phase iterative algorithm that alternates between inferring causal relationships among discovered subprocesses and uncovering new latent subprocesses, guided by path-based conditions that guarantee identifiability. Experiments on both synthetic and real-world datasets show that our method effectively recovers causal structures despite the presence of latent subprocesses.

---

## 99. Mean Flow Policy with Instantaneous Velocity Constraint for One-step Action Generation

**OpenReview**: [https://openreview.net/forum?id=mIeKe74W43](https://openreview.net/forum?id=mIeKe74W43)

**Authors**: Guojian Zhan (Tsinghua University), Letian Tao (Tsinghua University), Pengcheng Wang (University of California, Berkeley), Yixiao Wang (University of California, Berkeley), Yuxin Chen (University of California, Berkeley), Yiheng Li (University of California, Berkeley), Hongyang Li (University of Hong Kong), Masayoshi Tomizuka (University of California Berkeley), Shengbo Eben Li (Tsinghua University)

**Institutions**: Tsinghua University, University of California, Berkeley, University of Hong Kong, University of California Berkeley

**Primary Area**: reinforcement learning

**Keywords**: Reinforcement learning, Generative policy

**TL;DR**: We introduce the mean velocity policy, a new RL policy that, along with a novel instantaneous velocity constraint, achieves state-of-the-art performance and the fastest training and inference speed.

**Abstract**: Learning expressive and efficient policy functions is a promising direction in reinforcement learning (RL). While flow-based policies have recently proven effective in modeling complex action distributions with a fast deterministic sampling process, they still face a trade-off between expressiveness and computational burden, which is typically controlled by the number of flow steps. In this work, we propose mean velocity policy (MVP), a new generative policy function that models the mean velocity field to achieve the fastest one-step action generation. To ensure its high expressiveness, an instantaneous velocity constraint (IVC) is introduced on the mean velocity field during training. We theoretically prove that this design explicitly serves as a crucial boundary condition, thereby improving learning accuracy and enhancing policy expressiveness. Empirically, our MVP achieves state-of-the-art success rates across several challenging robotic manipulation tasks from Robomimic and OGBench. It also delivers substantial improvements in training and inference speed over existing flow-based policy baselines.

---

## 100. Radiometrically Consistent Gaussian Surfels for Inverse Rendering

**OpenReview**: [https://openreview.net/forum?id=lKqE7UuMvp](https://openreview.net/forum?id=lKqE7UuMvp)

**Authors**: Kyu Beom Han (Korea Advanced Institute of Science & Technology), Jaeyoon Kim (Korea Advanced Institute of Science & Technology), Woo Jae Kim (Korea Advanced Institute of Science and Technology), Jinhwan Seo (Korea Advanced Institute of Science & Technology), Sung-eui Yoon (KAIST)

**Institutions**: Korea Advanced Institute of Science & Technology, Korea Advanced Institute of Science and Technology, KAIST

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Radiometric Consistency, Indirect Illumination, Gaussian Splatting, Inverse Rendering

**TL;DR**: Radiometric Consistency for Gaussian Surfels provide accurate indirect illumination for inverse rendering

**Abstract**: Inverse rendering with Gaussian Splatting has advanced rapidly, but accurately disentangling material properties from complex global illumination effects, particularly indirect illumination, remains a major challenge. Existing methods often query indirect radiance from Gaussian primitives pre-trained for novel-view synthesis. However, these pre-trained Gaussian primitives are supervised only towards limited training viewpoints, thus lack supervision for modeling indirect radiances from unobserved views. To address this issue, we introduce radiometric consistency, a novel physically-based constraint that provides supervision towards unobserved views by minimizing the residual between each Gaussian primitive’s learned radiance and its physically-based rendered counterpart. Minimizing the residual for unobserved views establishes a self-correcting feedback loop that provides supervision from both physically-based rendering and novel-view synthesis, enabling accurate modeling of inter-reflection.
We then propose Radiometrically Consistent Gaussian Surfels (RadioGS), an inverse rendering framework built upon our principle by efficiently integrating radiometric consistency by utilizing  Gaussian surfels and 2D Gaussian ray tracing. We further propose a finetuning-based relighting strategy that adapts Gaussian surfel radiances to new illuminations within minutes, achieving low rendering cost ($<$10ms). Extensive experiments on existing inverse rendering benchmarks show that RadioGS outperforms existing Gaussian-based methods in inverse rendering, while retaining the computational efficiency.

---

## 101. Hubble: a Model Suite to Advance the Study of LLM Memorization

**OpenReview**: [https://openreview.net/forum?id=ZfdnZhOP0k](https://openreview.net/forum?id=ZfdnZhOP0k)

**Authors**: Johnny Wei (University of Southern California), Ameya Godbole (University of Southern California), Mohammad Aflah Khan (MPI-SWS), Ryan Yixiang Wang (University of Southern California), Xiaoyuan Zhu (University of Southern California), James Flemings (University of Southern California), Nitya Kashyap (University of Southern California), Krishna P. Gummadi (MPI-SWS), Willie Neiswanger (University of Southern California), Robin Jia (University of Southern California)

**Institutions**: University of Southern California, MPI-SWS

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: memorization, copyright, privacy, test set contamination, membership inference, unlearning

**TL;DR**: Hubble is a suite of paired LLMs (largest 8B), where the perturbed models are trained in the same way as standard models but with text (e.g. book passages, biographies, and test sets) inserted and designed to emulate key memorization risks.

**Abstract**: We present Hubble, a suite of fully open-source large language models (LLMs) for the scientific study of LLM memorization. Hubble models come in standard and perturbed variants: standard models are pretrained on a large English corpus, and perturbed models are trained in the same way but with controlled insertion of text (e.g., book passages, biographies, and test sets) designed to emulate key memorization risks. Our core release includes 8 models---standard and perturbed models with 1B or 8B parameters, pretrained on 100B or 500B tokens---establishing that memorization risks are determined by the frequency of sensitive data relative to size of the training corpus (i.e., a password appearing once in a smaller corpus is memorized better than the same password in a larger corpus). Our release also includes 6 perturbed models with text inserted at different pretraining phases, showing that sensitive data without continued exposure can be forgotten. These findings suggest two best practices for addressing memorization risks: to dilute sensitive data by increasing the size of the training corpus, and to order sensitive data to appear earlier in training. Beyond these general empirical findings, Hubble enables a broad range of memorization research; for example, analyzing the biographies reveals how readily different types of private information are memorized. We also demonstrate that the randomized insertions in Hubble make it an ideal testbed for membership inference and machine unlearning, and invite the community to further explore, benchmark, and build upon our work.

---

## 102. Differentially Private Domain Discovery

**OpenReview**: [https://openreview.net/forum?id=yBpzF8hp3J](https://openreview.net/forum?id=yBpzF8hp3J)

**Authors**: Vinod Raman (Google DeepMind), Travis Dick (Google), Matthew Joseph (Google)

**Institutions**: Google DeepMind, Google

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Differential Privacy, Partition Selection, Top-k Selection

**Abstract**: We study several problems in differentially private domain discovery, where each user holds a subset of items from a shared but unknown domain, and the goal is to output an informative subset of items. For set union, we  show that the simple baseline Weighted Gaussian Mechanism (WGM) has a near-optimal $\ell_1$ missing mass guarantee on Zipfian data as well as a distribution-free $\ell_\infty$ missing mass guarantee. We then apply the WGM as a domain-discovery precursor for existing known-domain algorithms for private top-$k$ and $k$-hitting set and obtain new utility guarantees for their unknown domain variants. Finally, experiments demonstrate that all of our WGM-based methods are competitive with or outperform existing baselines for all three problems.

---

## 103. CauKer: Classification Time Series Foundation Models Can Be Pretrained on Synthetic Data

**OpenReview**: [https://openreview.net/forum?id=xBW2FIfswU](https://openreview.net/forum?id=xBW2FIfswU)

**Authors**: Shifeng Xie (Télécom Paris), Vasilii Feofanov (42.com), Jianfeng Zhang (Huawei Technologies Ltd.), Themis Palpanas (Universite Paris Cite), Ievgen Redko (Huawei Technologies Ltd.)

**Institutions**: Télécom Paris, 42.com, Huawei Technologies Ltd., Universite Paris Cite

**Primary Area**: learning on time series and dynamical systems

**Keywords**: Time Series Foundation Model, Time Series Classification

**Abstract**: Time series foundation models (TSFMs) have recently gained significant attention due to their strong zero-shot capabilities and widespread real-world applications. Such models typically require a computationally costly pretraining on large-scale, carefully curated collections of real-world sequences. To allow for a sample-efficient pretraining of TSFMs, we propose CauKer, a novel algorithm designed to generate diverse, causally coherent synthetic time series with realistic trends, seasonality, and nonlinear interactions. CauKer combines Gaussian Process (GP) kernel composition with Structural Causal Models (SCM) to produce data for sample-efficient pretraining of state-of-the-art classification TSFMs having different architectures and following different pretraining approaches. Additionally, our experiments reveal that CauKer-generated datasets exhibit clear scaling laws for both dataset size (10K to 10M samples) and model capacity (1M to 783M parameters), unlike real-world datasets, which display irregular scaling behavior.

---

## 104. Non-Convex Federated Optimization under Cost-Aware Client Selection

**OpenReview**: [https://openreview.net/forum?id=FnaDv6SMd9](https://openreview.net/forum?id=FnaDv6SMd9)

**Authors**: Xiaowen Jiang (CISPA Helmholtz Center for Information Security), Anton Rodomanov (CISPA), Sebastian U Stich (CISPA Helmholtz Center)

**Institutions**: CISPA Helmholtz Center for Information Security, CISPA, CISPA Helmholtz Center

**Primary Area**: optimization

**Keywords**: Client Sampling, SAGA, Second-order Similarity, Composite Gradient Method, Variance Reduction

**TL;DR**: We propose a composite gradient method with SAGA and recursive gradient estimator for non-convex federated optimization that can exploit second-order similarity and achieve high communication and local computation efficiency.

**Abstract**: Different federated optimization algorithms typically employ distinct client-selection strategies: some methods communicate only with a randomly sampled subset of clients at each round, while others need to periodically communicate with all clients or use a hybrid scheme that combines both strategies. However, existing metrics for comparing optimization methods typically do not distinguish between these strategies, which often incur different communication costs in practice. To address this disparity, we introduce a simple and natural model of federated optimization that quantifies communication and local computation complexities. This new model allows for several commonly used client-selection strategies and explicitly associates each with a distinct cost. Within this setting, we propose a new algorithm that achieves the best-known communication and local complexities among existing federated optimization methods for non-convex optimization. This algorithm is based on the inexact composite gradient method with a carefully constructed gradient estimator and a special procedure for solving the auxiliary subproblem at each iteration. The gradient estimator is based on SAGA, a popular variance-reduced gradient estimator. We first derive a new variance bound for it, showing that SAGA can exploit functional similarity. We then introduce the Recursive-Gradient technique as a general way to potentially improve the error bound of a given conditionally unbiased gradient estimator, including both SAGA and SVRG. By applying this technique to SAGA, we obtain a new estimator, RG-SAGA, which has an improved error bound compared to the original one.

---

## 105. Verifying Chain-of-Thought Reasoning via Its Computational Graph

**OpenReview**: [https://openreview.net/forum?id=CxiNICq0Rr](https://openreview.net/forum?id=CxiNICq0Rr)

**Authors**: Zheng Zhao (University of Edinburgh, University of Edinburgh), Yeskendir Koishekenov (Facebook), Xianjun Yang (Facebook), Naila Murray (Meta AI), Nicola Cancedda (Meta)

**Institutions**: University of Edinburgh, University of Edinburgh, Facebook, Meta AI, Meta

**Primary Area**: interpretability and explainable AI

**Keywords**: Mechanistic Interpretability, Chain-of-Thought Reasoning, Attribution Graphs

**TL;DR**: We introduce CRV, a white-box methodology that treats attribution graphs as execution traces, and use it to provide evidence that flawed reasoning has a verifiable computational structure.

**Abstract**: Current Chain-of-Thought (CoT) verification methods predict reasoning correctness based on outputs (black-box) or activations (gray-box), but offer limited insight into \textit{why} a computation fails. We introduce a white-box method: \textbf{Circuit-based Reasoning Verification (CRV)}. We hypothesize that attribution graphs of correct CoT steps, viewed as \textit{execution traces} of the model's latent reasoning circuits, possess distinct structural fingerprints from those of incorrect steps. By training a classifier on structural features of these graphs, we show that these traces contain a powerful signal of reasoning errors. Our white-box approach yields novel scientific insights unattainable by other methods. (1) We demonstrate that structural signatures of error are highly predictive, establishing the viability of verifying reasoning directly via its computational graph. (2) We find these signatures to be highly domain-specific, revealing that failures in different reasoning tasks manifest as distinct computational patterns. (3) We provide evidence that these signatures are not merely correlational; by using our analysis to guide targeted interventions on individual transcoder features, we successfully correct the model's faulty reasoning. Our work shows that, by scrutinizing a model's computational process, we can move from simple error detection to a deeper, causal understanding of LLM reasoning.

---

## 106. How Learning Rate Decay Wastes Your Best Data in Curriculum-Based LLM Pretraining

**OpenReview**: [https://openreview.net/forum?id=T5wkZJqzkz](https://openreview.net/forum?id=T5wkZJqzkz)

**Authors**: Kairong Luo (Tsinghua University), Zhenbo Sun (Tsinghua University, Tsinghua University), Haodong Wen (Tsinghua University), Xinyu Shi (, Tsinghua University), Jiarui Cui (Tsinghua University), Chenyi Dang (Tsinghua University), Kaifeng Lyu (Tsinghua University), Wenguang Chen (Tsinghua University, Tsinghua University)

**Institutions**: Tsinghua University, Tsinghua University, Tsinghua University, , Tsinghua University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLM pretraining, Curriculum Learning, Model Weight Average

**TL;DR**: Use model weight average to enhance curriculum learning in LLM pretraining.

**Abstract**: Due to the scarcity of high-quality data, large language models (LLMs) are often trained on mixtures of data with varying quality levels, even after sophisticated data curation. A natural approach to better leverage high-quality data is curriculum-based pretraining, where the model is trained on data sorted in ascending order of quality as determined by a quality metric. However, prior studies have reported limited improvements from such curriculum-based pretraining strategies. This work identifies a critical factor constraining these methods: the incompatibility between the ascending data quality order and the decaying learning rate (LR) schedule. We find that while curriculum-based training substantially outperforms random shuffling when using a constant LR, its advantage diminishes under standard LR decay schedules. Our experiments show this incompatibility can be mitigated by two simple strategies: (1) employing a more moderate LR decay schedule, where the final LR is only moderately smaller than the peak LR, and (2) replacing LR decay with model averaging, i.e., computing a weighted average of the final few checkpoints. By combining these strategies, we improve the average score on a suite of standard benchmarks by 1.64% over random shuffling, without additional data refinement. Validated on 1.5B-parameter models trained over 30B tokens with various data-quality metrics, our findings call for a re-evaluation of curriculum-based LLM pretraining and underscore the potential of co-designing data curricula with optimization methods.

---

## 107. Probabilistic Kernel Function for Fast Angle Testing

**OpenReview**: [https://openreview.net/forum?id=nCsF3Bsn2n](https://openreview.net/forum?id=nCsF3Bsn2n)

**Authors**: Kejing Lu (Yamanashi University), Chuan Xiao (Osaka University), Yoshiharu Ishikawa (Nagoya University)

**Institutions**: Yamanashi University, Osaka University, Nagoya University

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: Randomized algorithm, Locality Sensitive Hashing, Directional statistics

**TL;DR**: We propose two probabilistic kernel functions for angle testing, which can be used to accelerate vector-based similarity search.

**Abstract**: In this paper, we study the angle testing problem in high-dimensional Euclidean spaces and propose two projection-based probabilistic kernel functions, one designed for angle comparison and the other for angle thresholding. Unlike existing approaches that rely on random projection vectors drawn from Gaussian distributions, our approach leverages reference angles and employs a deterministic structure for the projection vectors. Notably, our kernel functions do not require asymptotic assumptions, such as the number of projection vectors tending to infinity, and can be both theoretically and experimentally shown to outperform Gaussian-distribution-based kernel functions. We further apply the proposed kernel function to Approximate Nearest Neighbor Search (ANNS) and demonstrate that our approach achieves a 2.5X-3X higher query-per-second (QPS) throughput compared to the state-of-the-art graph-based search algorithm HNSW.

---

## 108. RefineStat: Efficient Exploration for Probabilistic Program Synthesis

**OpenReview**: [https://openreview.net/forum?id=SAl337ZX5d](https://openreview.net/forum?id=SAl337ZX5d)

**Authors**: Madhav Kanda (University of Illinois at Urbana-Champaign), Shubham Ugare (Meta), Sasa Misailovic (University of Illinois, Urbana Champaign)

**Institutions**: University of Illinois at Urbana-Champaign, Meta, University of Illinois, Urbana Champaign

**Primary Area**: probabilistic methods (Bayesian methods, variational inference, sampling, UQ, etc.)

**Keywords**: Probabilistic Programming, Constrained Generation

**Abstract**: Probabilistic programming offers a powerful framework for modeling uncertainty, yet statistical model discovery in this domain entails navigating an immense search space under strict domain‐specific constraints. When small language models are tasked with generating probabilistic programs, they frequently produce outputs that suffer from both syntactic, and semantic errors, such as flawed inference constructs. Motivated by probabilistic programmers’ domain expertise and debugging strategies, we introduce RefineStat, a language model–driven framework that enforces semantic constraints ensuring synthesized programs contain valid distributions, well‐formed parameters, and then applies diagnostic‐aware refinement by resampling prior or likelihood components whenever reliability checks fail. We evaluate RefineStat on multiple probabilistic-programming code-generation tasks using smaller language models (SLMs) and find that it produces programs that are both syntactically sound and statistically reliable, often matching or surpassing those from closed-source large language models (e.g., OpenAI o3).

---

## 109. Scaling Atomistic Protein Binder Design with Generative Pretraining and Test-Time Compute

**OpenReview**: [https://openreview.net/forum?id=qmCpJtFZra](https://openreview.net/forum?id=qmCpJtFZra)

**Authors**: Kieran Didi (NVIDIA), Zuobai Zhang (Mila - Université de Montréal), Guoqing Zhou (NVIDIA), Danny Reidenbach (NVIDIA), Zhonglin Cao (NVIDIA), Sooyoung Cha (Seoul National University), Tomas Geffner (NVIDIA), Christian Dallago (Duke University), Jian Tang (HEC Montreal), Michael M. Bronstein (Aithyra), Martin Steinegger (Seoul National University), Emine Kucukbenli (NVIDIA), Arash Vahdat (NVIDIA), Karsten Kreis (NVIDIA)

**Institutions**: NVIDIA, Mila - Université de Montréal, Seoul National University, Duke University, HEC Montreal, Aithyra

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: binder design, protein design, flow matching, hallucination, inference-time scaling, generative modeling, diffusion models

**TL;DR**: We introduce a novel method for state-of-the-art structure-based protein binder design that combines flow matching-based generative pretraining with inference-time compute scaling techniques.

**Abstract**: Protein interaction modeling is central to protein design, which has been transformed by machine learning with broad applications in drug discovery and beyond. In this landscape, structure-based de novo binder design is most often cast as either conditional generative modeling or sequence optimization via structure predictors ("hallucination"). We argue that this is a false dichotomy and propose Complexa, a novel fully atomistic binder generation method unifying both paradigms. We extend recent flow-based latent protein generation architecture and leverage the domain-domain interactions of monomeric computationally predicted protein structures to construct Teddymer, a new large-scale dataset of synthetic binder-target pairs for pretraining. Combined with high-quality experimental multimers, this enables training a strong base model. We then perform inference-time optimization with this generative prior, unifying the strengths of previously distinct generative and hallucination methods. Complexa sets a new state of the art in computational binder design benchmarks: it delivers markedly higher in-silico success rates than existing generative approaches, and our novel test-time optimization strategies greatly outperform previous hallucination methods under normalized compute budgets. We further demonstrate explicit interface hydrogen bond optimization, fold class-guided binder generation, and extensions to small molecule targets and enzyme design tasks, again surpassing prior methods. Code, models and new data will be publicly released.

---

## 110. Structured Flow Autoencoders: Learning Structured Probabilistic Representations with Flow Matching

**OpenReview**: [https://openreview.net/forum?id=KYdfvF2SZN](https://openreview.net/forum?id=KYdfvF2SZN)

**Authors**: Yidan Xu, Yixin Wang (University of Michigan - Ann Arbor), XuanLong Nguyen (University of Michigan)

**Institutions**: University of Michigan - Ann Arbor, University of Michigan

**Primary Area**: probabilistic methods (Bayesian methods, variational inference, sampling, UQ, etc.)

**Keywords**: Flow Matching, Probabilistic Model, Representation Learning, Probabilistic Graphical Model, Autoencoder

**Abstract**: Flow matching has proven to be a powerful density estimator, yet it often fails to explicitly capture the rich inherent latent structure of complex data. To address this limitation, we introduce Structured Flow Autoencoders (SFA), a family of probabilistic models that augments Continuous Normalizing Flows (CNFs) with graphical models. At the core of SFA is a novel flow matching based objective, which explicitly accounts for latent variables, enabling simultaneous learning of likelihood and posterior. We demonstrate the versatility of SFA across settings, including models with continuous and mixture latent variables, as well as latent dynamical systems. Empirical studies show that SFA outperforms Variational Autoencoders (VAE) and their graphical model extensions, achieving better data fit while simultaneously retaining meaningful latent variables as structured representations.

---

## 111. Plug-and-Play Compositionality for Boosting Continual Learning with Foundation Models

**OpenReview**: [https://openreview.net/forum?id=22hBwIf7OC](https://openreview.net/forum?id=22hBwIf7OC)

**Authors**: Weiduo Liao (City University of Hong Kong), Fei Han (The Hong Kong University of Science and Technology), Hisao Ishibuchi (Southern University of Science and Technology), Qingfu Zhang (City University of Hong Kong), Ying Wei (Zhejiang University)

**Institutions**: City University of Hong Kong, The Hong Kong University of Science and Technology, Southern University of Science and Technology, Zhejiang University

**Primary Area**: transfer learning, meta learning, and lifelong learning

**Keywords**: Continual learning

**TL;DR**: We introduce CompSLOT, a universal concept learning method to continual learning with foundation models system to establish a concept-level understanding of class prediction for alternative continual learners.

**Abstract**: Vision learners often struggle with catastrophic forgetting due to their reliance on class recognition by comparison, rather than understanding classes as compositions of representative concepts. 
This limitation is prevalent even in state-of-the-art continual learners with foundation models and worsens when current tasks contain few classes. 
Inspired by the recent success of concept-level understanding in mitigating forgetting, we design a universal framework CompSLOT to guide concept learning across diverse continual learners. 
Leveraging the progress of object-centric learning in parsing semantically meaningful slots from images, we tackle the challenge of learning slot extraction from ImageNet-pretrained vision transformers by analyzing meaningful concept properties. 
We further introduce a primitive selection and aggregation mechanism to harness concept-level image understanding. 
Additionally, we propose a method-agnostic self-supervision approach to distill sample-wise concept-based similarity information into the classifier, reducing reliance on incorrect or partial concepts for classification. 
Experiments show CompSLOT significantly enhances various continual learners and provides a universal concept-level module for the community.

---

## 112. Generating metamers of human scene understanding

**OpenReview**: [https://openreview.net/forum?id=cSDXx8V6K9](https://openreview.net/forum?id=cSDXx8V6K9)

**Authors**: Ritik Raina (State University of New York at Stony Brook), Abe Leite (State University of New York at Stony Brook), Alexandros Graikos (Stony Brook University), Seoyoung Ahn (University of California, Berkeley), Dimitris Samaras (Stony Brook University), Greg Zelinsky (State University of New York at Stony Brook)

**Institutions**: State University of New York at Stony Brook, Stony Brook University, University of California, Berkeley

**Primary Area**: applications to neuroscience & cognitive science

**Keywords**: human scene understanding, generative modeling

**Abstract**: Human vision combines low-resolution “gist” information from the visual periphery with sparse but high-resolution information from fixated locations to construct a coherent understanding of a visual scene. In this paper, we introduce MetamerGen, a tool for generating scenes that are aligned with latent human scene representations. MetamerGen is a latent diffusion model that combines peripherally obtained scene gist information with information obtained from scene-viewing fixations to generate image metamers for what humans understand after viewing a scene. Generating images from both high and low resolution (i.e. “foveated”) inputs constitutes a novel image-to-image synthesis problem, which we tackle by introducing a dual-stream representation of the foveated scenes consisting of DINOv2 tokens that fuse detailed features from fixated areas with peripherally degraded features capturing scene context. To evaluate the perceptual alignment of MetamerGen generated images to latent human scene representations, we conducted a same-different behavioral experiment where participants were asked for a “same” or “different” response between the generated and the original image. With that, we identify scene generations that are indeed metamers for the latent scene representations formed by the viewers. MetamerGen is a powerful tool for understanding scene understanding. Our proof-of-concept analyses uncovered specific features at multiple levels of visual processing that contributed to human judgments. While it can generate metamers even conditioned on random fixations, we find that high-level semantic alignment most strongly predicts metamerism when the generated scenes are conditioned on viewers’ own fixated regions.

---

## 113. Efficient Resource-Constrained Training of Transformers via Subspace Optimization

**OpenReview**: [https://openreview.net/forum?id=0nvQ5kHXf4](https://openreview.net/forum?id=0nvQ5kHXf4)

**Authors**: Le-Trung Nguyen (Télécom Paris), Enzo Tartaglione (Télécom Paris), Van-Tam Nguyen (Télécom Paris)

**Institutions**: Télécom Paris

**Primary Area**: optimization

**Keywords**: Deep Learning, Computer Vision, Compression, Low rank

**TL;DR**: We propose a novel method that enables training vision transformer models within a low-rank subspace to optimize computational resources, making on-device learning practically feasible.

**Abstract**: As AI increasingly shapes daily life, energy consumption and data privacy have become pressing concerns. On-device learning trains models directly on edge devices, cutting energy consumption and safeguarding data privacy. However, the expanding scale of modern neural networks creates a major obstacle for on-device training. Although prior work has concentrated on compact convolutional architectures, we instead apply subspace-based training to transformer models. Motivated by the idea that a model's essential information lies in a fixed subspace, we introduce Weight-Activation Subspace Iteration (WASI), a method that mitigates the memory bottleneck of backpropagation and boosts inference efficiency in transformer models by restricting training to this subspace. Our results demonstrate that WASI maintains accuracy comparable to vanilla training while reducing memory usage by up to $62\times$ and computational cost (FLOPs) by up to $2\times$. On a Raspberry Pi 5, WASI achieves roughly $1.4\times$ faster training and inference than vanilla training. The code is available at https://github.com/Le-TrungNguyen/ICLR2026-WASI.git.

---

## 114. Learning with Dual-level Noisy Correspondence for Multi-modal Entity Alignment

**OpenReview**: [https://openreview.net/forum?id=mytIKuRsSE](https://openreview.net/forum?id=mytIKuRsSE)

**Authors**: Haobin Li (School of Software Engineering, Sichuan University, Sichuan University), Yijie Lin (Sichuan University), Peng Hu (Sichuan University), Mouxing Yang (Sichuan University), Xi Peng (Sichuan University)

**Institutions**: School of Software Engineering, Sichuan University, Sichuan University, Sichuan University

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Noisy correspondence; Multi-modal entity alignment.

**Abstract**: Multi-modal entity alignment (MMEA) aims to identify equivalent entities across heterogeneous multi-modal knowledge graphs (MMKGs), where each entity is described by attributes from various modalities. Existing methods typically assume that both intra-entity and inter-graph correspondences are faultless, which is often violated in real-world MMKGs due to the reliance on expert annotations.
In this paper, we reveal and study a highly practical yet under-explored problem in MMEA, termed Dual-level Noisy Correspondence (DNC).
DNC refers to misalignments in both intra-entity (entity-attribute) and inter-graph (entity-entity and attribute-attribute) correspondences.
To address the DNC problem, we propose a robust MMEA framework termed RULE. RULE first estimates the reliability of both intra-entity and inter-graph correspondences via a dedicated two-fold principle. Leveraging the estimated reliabilities, RULE mitigates the negative impact of intra-entity noise during attribute fusion and prevents overfitting to noisy inter-graph correspondences during inter-graph discrepancy elimination. Beyond the training-time designs, RULE further incorporates a correspondence reasoning module that uncovers the underlying attribute-attribute connection across graphs, guaranteeing more accurate equivalent entity identification.
Extensive experiments on five benchmarks verify the effectiveness of our method against the DNC compared with seven state-of-the-art methods. 
The code will be released upon acceptance.

---

## 115. Pinet: Optimizing hard-constrained neural networks with orthogonal projection layers

**OpenReview**: [https://openreview.net/forum?id=EJ680UQeZG](https://openreview.net/forum?id=EJ680UQeZG)

**Authors**: Panagiotis D. Grontas (ETHZ - ETH Zurich), Antonio Terpin (ETHZ - ETH Zurich), Efe C. Balta (inspire AG), Raffaello D'Andrea (ETHZ - ETH Zurich), John Lygeros (ETHZ - ETH Zurich)

**Institutions**: ETHZ - ETH Zurich, inspire AG

**Primary Area**: optimization

**Keywords**: hard constrained neural networks, network architecture, implicit layers, operator splitting, optimization

**Abstract**: We introduce an output layer for neural networks that ensures satisfaction of convex constraints. Our approach, $\Pi$net, leverages operator splitting for rapid and reliable projections in the forward pass, and the implicit function theorem for backpropagation. We deploy $\Pi$net as a feasible-by-design optimization proxy for parametric constrained optimization problems and obtain modest-accuracy
solutions faster than traditional solvers when solving a single problem, and significantly faster for a batch of problems. 
We surpass state-of-the-art learning approaches by orders of magnitude in terms of training time, solution quality, and robustness to hyperparameter tuning, while maintaining similar inference times. Finally, we tackle multi-vehicle motion planning with non-convex trajectory preferences and provide $\Pi$net as a GPU-ready package implemented in JAX.

---

## 116. ParaRNN: Unlocking Parallel Training of Nonlinear RNNs for Large Language Models

**OpenReview**: [https://openreview.net/forum?id=mX8b64iUaa](https://openreview.net/forum?id=mX8b64iUaa)

**Authors**: Federico Danieli (Apple), Pau Rodriguez (Apple), Miguel Sarabia, Xavier Suau (Apple), Luca Zappella (Apple)

**Institutions**: Apple

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: RNN, Mamba, SSM, Transformers, Parallelization, Parallel scan, Nonlinear

**TL;DR**: We break the sequential bottleneck of nonlinear RNNs, enabling training of billion-scale LSTM/GRU models, competitive with modern architectures

**Abstract**: Recurrent Neural Networks (RNNs) laid the foundation for sequence modeling, but their intrinsic sequential nature restricts parallel computation, creating a fundamental barrier to scaling. This has led to the dominance of parallelizable architectures like Transformers and, more recently, State Space Models (SSMs). While SSMs achieve efficient parallelization through structured linear recurrences, this linearity constraint limits their expressive power and precludes modeling complex, nonlinear sequence-wise dependencies.
To address this, we present ParaRNN, a framework that breaks the sequence-parallelization barrier for nonlinear RNNs. Building on prior work, we cast the sequence of nonlinear recurrence relationships as a single system of equations, which we solve in parallel using Newton's iterations combined with custom parallel reductions. Our implementation achieves speedups of up to $665\times$ over na\"ive sequential application, allowing training nonlinear RNNs at unprecedented scales. To showcase this, we apply ParaRNN to adaptations of LSTM and GRU architectures, successfully training models of 7B parameters that attain perplexity comparable to similarly-sized Transformers and Mamba2 architectures.
To accelerate research in efficient sequence modeling, we release the ParaRNN codebase as an open-source framework for automatic training-parallelization of nonlinear RNNs, enabling researchers and practitioners to explore new nonlinear RNN models at scale.

---

## 117. Exploring Synthesizable Chemical Space with Iterative Pathway Refinements

**OpenReview**: [https://openreview.net/forum?id=aQKVfKOkR5](https://openreview.net/forum?id=aQKVfKOkR5)

**Authors**: Seul Lee (Korea Advanced Institute of Science and Technology), Karsten Kreis (NVIDIA), Srimukh Prasad Veccham (NVIDIA), Meng Liu (NVIDIA), Danny Reidenbach (NVIDIA), Saee Gopal Paliwal (NVIDIA), Weili Nie (NVIDIA), Arash Vahdat (NVIDIA)

**Institutions**: Korea Advanced Institute of Science and Technology, NVIDIA

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: drug discovery, molecule generation, synthesizable molecule design

**Abstract**: A well-known pitfall of molecular generative models is that they are not guaranteed to generate synthesizable molecules. Existing solutions for this problem often struggle to effectively navigate exponentially large combinatorial space of synthesizable molecules and suffer from poor coverage. To address this problem, we introduce ReaSyn, an iterative generative pathway refinement framework that obtains synthesizable analogs to input molecules by projecting them onto synthesizable space. Specifically, we propose a simple synthetic pathway representation that allows for generating pathways in both bottom-up and top-down traversal of synthetic trees. We design ReaSyn so that both bottom-up and top-down pathways can be sampled with a single unified autoregressive model. ReaSyn can thus iteratively refine subtrees of generated synthetic trees in a bidirectional manner. Further, we introduce a discrete flow model that refines the generated pathway at the entire pathway level with edit operations: insertion, deletion, and substitution. The iterative refinement cycle of (1) bottom-up decoding, (2) top-down decoding, and (3) holistic editing constitutes a powerful pathway reasoning strategy, allowing the model to explore the vast space of synthesizable molecules. Experimentally, ReaSyn achieves the highest reconstruction rate and pathway diversity in synthesizable molecule reconstruction and the highest optimization performance in synthesizable goal-directed molecular optimization, and significantly outperforms previous synthesizable projection methods in synthesizable hit expansion. These results highlight ReaSyn's superior ability to navigate combinatorially-large synthesizable chemical space.

---

## 118. On The Surprising Effectiveness of a Single Global Merging in Decentralized Learning

**OpenReview**: [https://openreview.net/forum?id=zrFnwRHuQo](https://openreview.net/forum?id=zrFnwRHuQo)

**Authors**: Tongtian Zhu (Zhejiang University), Tianyu Zhang (Montreal Institute for Learning Algorithms, University of Montreal, University of Montreal), Mingze Wang (Peking University), Zhanpeng Zhou (ByteDance Inc.), Can Wang (Zhejiang University)

**Institutions**: Zhejiang University, Montreal Institute for Learning Algorithms, University of Montreal, University of Montreal, Peking University, ByteDance Inc.

**Primary Area**: optimization

**Keywords**: Decentralized Learning, Model Merging

**TL;DR**: We discover and theoretically explain why and when a single global parameter merging in decentralized learning can recover the performance of federated learning, even in highly heterogeneous and communication-constrained environments.

**Abstract**: Decentralized learning provides a scalable alternative to parameter-server-based training, yet its performance is often hindered by limited peer-to-peer communication. 
In this paper, we study how communication should be scheduled over time to improve global generalization, including determining when and how frequently devices synchronize. 
Counterintuitive empirical results show that concentrating communication budgets in the later stages of decentralized training remarkably improves global generalization.
Surprisingly, we uncover that fully connected communication at the final step, implemented by a single global merging, can significant improve the generalization performance of decentralized learning under serve high data heterogeneity. 
Our theoretical contributions, which explains these phenomena, are first to establish that the globally merged model of decentralized SGD can match the convergence rate of parallel SGD.
Technically, we reinterpret part of the discrepancy among local models, which were previously considered as detrimental noise, as constructive components essential for matching this rate. 
This work provides promising results that  decentralized learning is able to generalize under high data heterogeneity and limited communication, while offering broad new avenues for model merging research. 
The code will be made publicly available.

---

## 119. Visual Planning: Let's Think Only with Images

**OpenReview**: [https://openreview.net/forum?id=wsnse46kRO](https://openreview.net/forum?id=wsnse46kRO)

**Authors**: Yi Xu (University of Cambridge), Chengzu Li (University of Cambridge), Han Zhou (Mistral AI), Xingchen Wan (Google DeepMind), Caiqi Zhang (University of Cambridge), Anna Korhonen (University of Cambridge), Ivan Vulić (Google DeepMind)

**Institutions**: University of Cambridge, Mistral AI, Google DeepMind

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: visual planning

**Abstract**: Recent advancements in Large Language Models (LLMs) and their multimodal extensions (MLLMs) have substantially enhanced machine reasoning across diverse tasks. However, these models predominantly rely on pure text as the medium for both expressing and structuring reasoning, even when visual information is present. In this work, we argue that language may not always be the most natural or effective modality for reasoning, particularly in tasks involving spatial and geometrical information. Motivated by this, we propose a new paradigm, Visual Planning, which enables planning through purely visual representations for these "vision-first'' tasks, as a supplementary channel to language-based reasoning. In this paradigm, planning is executed via sequences of images that encode step-by-step inference in the visual domain, akin to how humans sketch or visualize future actions. We introduce a novel reinforcement learning framework, Visual Planning via Reinforcement Learning (VPRL), empowered by GRPO for post-training large vision models, leading to substantial improvements in planning in a selection of representative visual navigation tasks, FrozenLake, Maze, and MiniBehavior. Our visual planning paradigm outperforms all other planning variants that conduct reasoning in the text-only space. Our results establish Visual Planning as a viable and promising supplement to language-based reasoning, opening new avenues for tasks that benefit from intuitive, image-based inference.

---

## 120. Optimal Sparsity of Mixture-of-Experts Language Models for Reasoning Tasks

**OpenReview**: [https://openreview.net/forum?id=XFw2EPRUUR](https://openreview.net/forum?id=XFw2EPRUUR)

**Authors**: Taishi Nakamura (Institute of Science Tokyo), Satoki Ishikawa (Institute of Science Tokyo), Masaki Kawamura (Institute of Science Tokyo), Takumi Okamoto (Institute of Science Tokyo), Daisuke Nohara (Institute of Science Tokyo), Jun Suzuki (Tohoku University), Rio Yokota (Institute of Science Tokyo)

**Institutions**: Institute of Science Tokyo, Tohoku University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Mixture of Experts, memorization, reasoning, scaling laws, large language models

**TL;DR**: Memorization skills consistently benefit from higher sparsity, while reasoning skills require balancing active FLOPs with total tokens per parameter; the optimal point shifts with the compute budget.

**Abstract**: Empirical scaling laws have driven the evolution of large language models (LLMs), yet their coefficients shift whenever the model architecture or data pipeline changes.
Mixture‑of‑Experts (MoE) models, now standard in state‑of‑the‑art systems, introduce a new sparsity dimension that current dense‑model frontiers overlook.
We investigate how MoE sparsity influences two distinct capability regimes: memorization skills and reasoning skills.
By training MoE families that vary total parameters, active parameters, and top-$k$ routing under fixed compute budgets, we disentangle pre-training loss from downstream accuracy. 
Our results reveal two principles. First, Active FLOPs: models with identical training loss but greater active compute achieve higher reasoning accuracy. Second, Total tokens per parameter (TPP): memorization tasks improve with more parameters, while reasoning tasks benefit from optimal TPP, indicating that reasoning is data-hungry. 
Neither reinforcement learning post-training (GRPO) nor increased test-time compute alters these trends. 
We therefore argue that optimal MoE sparsity must be determined jointly by active FLOPs and TPP, revising the classical picture of compute-optimal scaling. 
All code, data sources, and logs are released to facilitate reproducibility and future work.

---

## 121. Exploratory Diffusion Model for Unsupervised Reinforcement Learning

**OpenReview**: [https://openreview.net/forum?id=k0Kb1ynFbt](https://openreview.net/forum?id=k0Kb1ynFbt)

**Authors**: Chengyang Ying (Tsinghua University, Tsinghua University), Huayu Chen (Tsinghua University), Xinning Zhou (Tsinghua University, Tsinghua University), Zhongkai Hao (Tsinghua University), Hang Su (Tsinghua University), Jun Zhu (Tsinghua University)

**Institutions**: Tsinghua University, Tsinghua University, Tsinghua University

**Primary Area**: reinforcement learning

**Keywords**: reinforcement learning, diffusion policy, unsupervised reinforcement learning, exploration

**TL;DR**: We propose Exploratory Diffusion Model (ExDM), boosting unsupervised exploration and few-shot fine-tuning by diffusion models.

**Abstract**: Unsupervised reinforcement learning (URL) pre-trains agents by exploring diverse states in reward-free environments, aiming to enable efficient adaptation to various downstream tasks. Without extrinsic rewards, prior methods rely on intrinsic objectives, but heterogeneous exploration data demand strong modeling capacity for both intrinsic reward design and policy learning. We introduce the **Ex**ploratory **D**iffusion **M**odel (**ExDM**), which leverages the expressive power of diffusion models to fit diverse replay-buffer distributions, thus providing accurate density estimates and a score-based intrinsic reward that drives exploration into under-visited regions. This mechanism substantially broadens state coverage and yields robust pre-trained policies. Beyond exploration, ExDM offers theoretical guarantees and practical algorithms for fine-tuning diffusion policies under limited interactions, overcoming instability and computational overhead from multi-step sampling. Extensive experiments on Maze2d and URLB show that ExDM achieves superior exploration and faster downstream adaptation, establishing new state-of-the-art results, particularly in environments with complex structure or cross-embodiment settings.

---

## 122. DCFold: Efficient Protein Structure Generation with Single Forward Pass

**OpenReview**: [https://openreview.net/forum?id=LMsdys7t1L](https://openreview.net/forum?id=LMsdys7t1L)

**Authors**: Zhe Zhang (Tsinghua University), Yuanning Feng (Huazhong University of Science and Technology), Yuxuan Song (ByteDance Inc.), Keyue Qiu, Hao Zhou (Tsinghua University, Tsinghua University), Wei-Ying Ma (Tsinghua University)

**Institutions**: Tsinghua University, Huazhong University of Science and Technology, ByteDance Inc., Tsinghua University, Tsinghua University

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: consistency model, protein structure generation

**Abstract**: AlphaFold3 introduces a diffusion-based architecture that elevates protein structure prediction to all-atom resolution with improved accuracy. This state-of-the-art performance has established AlphaFold3 as a foundation model for diverse generation and design tasks. However, its iterative design substantially increases inference time, limiting practical deployment in downstream settings such as virtual screening and protein design. We propose DCFold, a single-step generative model that attains AlphaFold3-level accuracy. Our Dual Consistency training framework, which incorporates a novel Temporal Geodesic Matching (TGM) scheduler, enables DCFold to achieve a 15× acceleration in inference while maintaining predictive fidelity. We validate its effectiveness across both structure prediction and binder design benchmarks.

---

## 123. Triple-BERT: Do We Really Need MARL for Order Dispatch on Ride-Sharing Platforms?

**OpenReview**: [https://openreview.net/forum?id=symgW6FhA6](https://openreview.net/forum?id=symgW6FhA6)

**Authors**: Zijian Zhao (The Hong Kong University of Science and Technology), Sen Li (Hong Kong University of Science and Technology)

**Institutions**: The Hong Kong University of Science and Technology, Hong Kong University of Science and Technology

**Primary Area**: reinforcement learning

**Keywords**: Reinforcement Learning, Order Dispatching, Ride Sharing

**TL;DR**: This paper proposes a novel centralized reinforcement learning framework for large-scale order dispatching tasks in ride-sharing scenarios, achieving better cooperation among workers compared to previous multi-agent methods.

**Abstract**: On-demand ride-sharing platforms, such as Uber and Lyft, face the intricate real-time challenge of bundling and matching passengers—each with distinct origins and destinations—to available vehicles, all while navigating significant system uncertainties. Due to the extensive observation space arising from the large number of drivers and orders, order dispatching, though fundamentally a centralized task, is often addressed using Multi-Agent Reinforcement Learning (MARL). However, independent MARL methods fail to capture global information and exhibit poor cooperation among workers, while Centralized Training Decentralized Execution (CTDE) MARL methods suffer from the curse of dimensionality. To overcome these challenges, we propose Triple-BERT, a centralized  Single Agent Reinforcement Learning (MARL) method designed specifically for large-scale order dispatching on ride-sharing platforms. Built on a variant TD3, our approach addresses the vast action space through an action decomposition strategy that breaks down the joint action probability into individual driver action probabilities. To handle the extensive observation space, we introduce a novel BERT-based network, where parameter reuse mitigates parameter growth as the number of drivers and orders increases, and the attention mechanism effectively captures the complex relationships among the large pool of driver and orders. We validate our method  using a real-world ride-hailing dataset from Manhattan. Triple-BERT achieves approximately an 11.95% improvement over current state-of-the-art methods, with a 4.26% increase in served orders and a 22.25% reduction in pickup times. Our code, trained model parameters, and processed data are publicly available at https://github.com/RS2002/Triple-BERT .

---

## 124. InfoNCE Induces Gaussian Distribution

**OpenReview**: [https://openreview.net/forum?id=BlSH7gNQSq](https://openreview.net/forum?id=BlSH7gNQSq)

**Authors**: Roy Betser (Technion - Israel Institute of Technology, Technion), Eyal Gofer (Electrical Engineering Department, Technion – Israel Institute of Technology, Technion - Israel Institute of Technology), Meir Yossef Levi (Technion - Israel Institute of Technology, Technion - Israel Institute of Technology), Guy Gilboa (Technion - Israel Institute of Technology, Technion)

**Institutions**: Technion - Israel Institute of Technology, Technion, Electrical Engineering Department, Technion – Israel Institute of Technology, Technion - Israel Institute of Technology, Technion - Israel Institute of Technology, Technion - Israel Institute of Technology

**Primary Area**: learning theory

**Keywords**: Contrastive learning, Gaussian distribution, InfoNCE

**TL;DR**: Contrastive learning based representations can be well approximated by a multivariate Gaussian distribution.

**Abstract**: Contrastive learning has become a cornerstone of modern representation learning, allowing training with massive
unlabeled data for both task-specific and general (foundation) models.
A prototypical loss in contrastive training is InfoNCE and its variants. 
In this work, we show that the InfoNCE objective induces Gaussian structure in representations that emerge from contrastive training. 
We establish this result in two complementary regimes. 
First, we show that under certain  alignment and concentration assumptions, projections of the high-dimensional representation asymptotically approach a multivariate Gaussian distribution.
Next, under less strict assumptions, we show that adding a small asymptotically vanishing regularization term that promotes low feature norm and high feature entropy leads to similar asymptotic results.
We support our analysis with experiments on synthetic and CIFAR-10 datasets across multiple encoder architectures and sizes, demonstrating consistent Gaussian behavior.
This perspective provides a principled explanation for commonly observed Gaussianity in contrastive representations. 
The resulting Gaussian model enables principled analytical treatment of learned representations and is expected to support a wide range of applications in contrastive learning.

---

## 125. Coupling Experts and Routers in Mixture-of-Experts via an Auxiliary Loss

**OpenReview**: [https://openreview.net/forum?id=MpeyjgWbKt](https://openreview.net/forum?id=MpeyjgWbKt)

**Authors**: Ang Lv (Renmin University of China), Jin Ma (ByteDance Inc.), Yiyuan Ma (ByteDance Inc.), Siyuan Qiao (Meta)

**Institutions**: Renmin University of China, ByteDance Inc., Meta

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Mixture-of-Experts, Large language models, Auxiliary loss, Expert-router coupling, Expert specialization

**Abstract**: Mixture-of-Experts (MoE) models lack explicit constraints to ensure the router's decisions align well with the experts' capabilities, which ultimately limits model performance. To address this, we propose expert-router coupling (ERC) loss, a lightweight auxiliary loss that tightly couples the router's decisions with expert capabilities. Our approach treats each expert's router embedding as a proxy token for the tokens assigned to that expert, and feeds perturbed router embeddings through the experts to obtain intermediate activations. The ERC loss enforces two constraints on these activations: (1) Each expert must exhibit higher activation for its own proxy token than for the proxy tokens of any other expert. (2) Each proxy token must elicit stronger activation from its corresponding expert than from any other expert. These constraints jointly ensure that each router embedding faithfully represents its corresponding expert's capability, while each expert specializes in processing the tokens actually routed to it. The ERC loss is computationally efficient, operating only on $n^2$ activations, where $n$ is the number of experts. This represents a fixed cost independent of batch size, unlike prior coupling methods that scale with the number of tokens (often millions per batch). Through pre-training MoE-LLMs ranging from 3B to 15B parameters and extensive analysis on trillions of tokens, we demonstrate the effectiveness of the ERC loss. Moreover, the ERC loss offers flexible control and quantitative tracking of expert specialization levels during training, providing valuable insights into MoEs.

---

## 126. P-GenRM: Personalized Generative Reward Model with Test-time User-based Scaling

**OpenReview**: [https://openreview.net/forum?id=hXNApWLBZG](https://openreview.net/forum?id=hXNApWLBZG)

**Authors**: Pinyi Zhang (East China Normal University), Ting-En Lin (Alibaba Group), Yuchuan Wu (Alibaba Group), Jingyang Chen (Fudan University), Zongqi Wang (Tsinghua University), Hua Yang (Alibaba Group), Xu Ze (Alibaba Group), Fei Huang (Alibaba Group US), Yongbin Li (Alibaba Group), Kai Zhang (East China Normal University)

**Institutions**: East China Normal University, Alibaba Group, Fudan University, Tsinghua University, Alibaba Group US

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: personalizd alignment, generative reward model, test-time user-based scaling

**TL;DR**: The first personalized generative reward model with test-time user-based scaling for preference alignment

**Abstract**: Personalized alignment of large language models seeks to adapt responses to individual user preferences, typically via reinforcement learning. A key challenge is obtaining accurate, user-specific reward signals in open-ended scenarios. Existing personalized reward models face two persistent limitations: (1) oversimplifying diverse, scenario-specific preferences into a small, fixed set of evaluation principles, and (2) struggling with generalization to new users with limited feedback. To this end, we propose **P-GenRM**, the first **P**ersonalized **Gen**erative **R**eward **M**odel with test-time user-based scaling. P-GenRM transforms preference signals into structured evaluation chains that derive adaptive personas and scoring rubrics across various scenarios. It further clusters users into User Prototypes and introduces a dual-granularity scaling mechanism: at the individual level, it adaptively scales and aggregates each user’s scoring scheme; at the prototype level, it incorporates preferences from similar users. This design mitigates noise in inferred preferences and enhances generalization to unseen users through prototype-based transfer. Empirical results show that  P-GenRM achieves state-of-the-art results on widely-used personalized reward model benchmarks, with an average improvement of ~2.31\%, and demonstrates strong generalization on an out-of-distribution dataset. Notably, Test-time User-based scaling provides an additional ~3\% boost, demonstrating stronger personalized alignment with test-time scalability.

---

## 127. Modality-free Graph In-context Alignment

**OpenReview**: [https://openreview.net/forum?id=cDc95lucVL](https://openreview.net/forum?id=cDc95lucVL)

**Authors**: Wei Zhuo (Nanyang Technological University), Siqiang Luo (Nanyang Technological University)

**Institutions**: Nanyang Technological University

**Primary Area**: learning on graphs and other geometries & topologies

**Keywords**: Graph foundation model, In-context learning, Pretraining

**TL;DR**: A pretraining framework that enables in-context learning on graph-structured data without modality assumptions.

**Abstract**: In-context learning (ICL) converts static encoders into task-conditioned reasoners, enabling adaptation to new data from just a few examples without updating pretrained parameters. This capability is essential for graph foundation models (GFMs) to approach LLM-level generality. Yet current GFMs struggle with cross-domain alignment, typically relying on modality-specific encoders that fail when graphs are pre-vectorized or raw data is inaccessible. In this paper, we introduce **M**odality-**F**ree **G**raph **I**n-context **A**lignment (MF-GIA), a framework that makes a pretrained graph encoder promptable for few-shot prediction across heterogeneous domains without modality assumptions. MF-GIA captures domain characteristics through gradient fingerprints, which parameterize lightweight transformations that align pre-encoded features and indexed labels into unified semantic spaces. During pretraining, a dual prompt-aware attention mechanism with episodic objective learns to match queries against aligned support examples to establish prompt-based reasoning capabilities. At inference, MF-GIA performs parameter-update-free adaptation using only a few-shot support set to trigger cross-domain alignment and enable immediate prediction on unseen domains. Experiments demonstrate that MF-GIA achieves superior few-shot performance across diverse graph domains and strong generalization to unseen domains. The code is available at https://github.com/JhuoW/MF-GIA.

---

## 128. TRACE: Your Diffusion Model is Secretly an Instance Edge Detector

**OpenReview**: [https://openreview.net/forum?id=BjElYlJKMj](https://openreview.net/forum?id=BjElYlJKMj)

**Authors**: Sanghyun Jo (OGQ), Ziseok Lee (Seoul National University), Wooyeol Lee (Seoul National University), Jonghyun Choi (Seoul National University), Jaesik Park (Seoul National University), Kyungsu Kim (Seoul National University)

**Institutions**: OGQ, Seoul National University

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: diffusion, unsupervised instance segmentation, weakly-supervised panoptic segmentation, inference dynamics, attention

**TL;DR**: TRACE turns pretrained diffusion models into annotation-free instance edge generators for instance and panoptic segmentation.

**Abstract**: High-quality instance and panoptic segmentation has traditionally relied on dense instance-level annotations such as masks, boxes, or points, which are costly, inconsistent, and difficult to scale. Unsupervised and weakly-supervised approaches reduce this burden but remain constrained by semantic backbone constraints and human bias, often producing merged or fragmented outputs. We present TRACE (TRAnsforming diffusion Cues to instance Edges), showing that text-to-image diffusion models secretly function as instance edge annotators. TRACE identifies the Instance Emergence Point (IEP) where object boundaries first appear in self-attention maps, extracts boundaries through Attention Boundary Divergence (ABDiv), and distills them into a lightweight one-step edge decoder. This design removes the need for per-image diffusion inversion, achieving 81× faster inference while producing sharper and more connected boundaries. On the COCO benchmark, TRACE improves unsupervised instance segmentation by +5.1 AP, and in tag-supervised panoptic segmentation it outperforms point-supervised baselines by +1.7 PQ without using any instance-level labels. These results reveal that diffusion models encode hidden instance boundary priors, and that decoding these signals offers a practical and scalable alternative to costly manual annotation. **Project Page:** https://shjo-april.github.io/TRACE.

---

## 129. Scaling Laws and Spectra of Shallow Neural Networks in the Feature Learning Regime

**OpenReview**: [https://openreview.net/forum?id=Q3yLIIkt7z](https://openreview.net/forum?id=Q3yLIIkt7z)

**Authors**: Leonardo Defilippis (Ecole Normale Supérieure, Ecole Normale Supérieure de Paris), Yizhou Xu, Julius Girardin (EPFL - EPF Lausanne), Vittorio Erba (EPFL - EPF Lausanne), Emanuele Troiani (School of Computer and Communication Sciences, EPFL - EPF Lausanne), Lenka Zdeborová (Swiss Federal Institute of Technology Lausanne), Bruno Loureiro (Ecole Normale Supérieure, Ecole Normale Supérieure de Paris), Florent Krzakala (Swiss Federal Institute of Technology Lausanne)

**Institutions**: Ecole Normale Supérieure, Ecole Normale Supérieure de Paris, EPFL - EPF Lausanne, School of Computer and Communication Sciences, EPFL - EPF Lausanne, Swiss Federal Institute of Technology Lausanne

**Primary Area**: learning theory

**Keywords**: Scaling laws; Neural networks; LASSO and matrix compressed sensing; Random matrix theory; Approximate message passing; High dimensional Statistics

**TL;DR**: We derive a phase diagram of scaling laws for diagonal and quadratic neural networks via a bridge to LASSO and matrix compressed sensing, predicting both generalization and the emergence of power-law weight spectra.

**Abstract**: Neural scaling laws underlie many of the recent advances in deep learning, yet their theoretical understanding remains largely confined to linear models. In this work, we present a systematic analysis of scaling laws for quadratic and diagonal neural networks in the feature learning regime. Leveraging connections with matrix compressed sensing and LASSO, we derive a detailed phase diagram for the scaling exponents of the excess risk as a function of sample complexity and weight decay. This analysis uncovers crossovers between distinct scaling regimes and plateau behaviors, mirroring phenomena widely reported in the empirical neural scaling literature. Furthermore, we establish a precise link between these regimes and the spectral properties of the trained network weights, which we characterize in detail. As a consequence, we provide a theoretical validation of recent empirical observations connecting the emergence of power-law tails in the weight spectrum with network generalization performance, yielding an interpretation from first principles.

---

## 130. MemAgent: Reshaping Long-Context LLM with Multi-Conv RL-based Memory Agent

**OpenReview**: [https://openreview.net/forum?id=k5nIOvYGCL](https://openreview.net/forum?id=k5nIOvYGCL)

**Authors**: Hongli Yu (Tsinghua University), Tinghong Chen (University of the Chinese Academy of Sciences), Jiangtao Feng (Tsinghua University), Jiangjie Chen (ByteDance Seed), Weinan Dai (Tsinghua University), Qiying Yu (Tsinghua University), Ya-Qin Zhang (AIR, Tsinghua University), Wei-Ying Ma (Tsinghua University), Jingjing Liu (Tsinghua University), Mingxuan Wang (ByteDance Inc.), Hao Zhou (Tsinghua University, Tsinghua University)

**Institutions**: Tsinghua University, University of the Chinese Academy of Sciences, ByteDance Seed, AIR, Tsinghua University, ByteDance Inc., Tsinghua University, Tsinghua University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLM, memory, agent, RLVR

**TL;DR**: We propose MemAgent, a novel agent workflow for long-text processing,  demonstrating exceptional extrapolation and performance in large-scale tasks after RL Training.

**Abstract**: Despite improvements by length extrapolation, efficient attention and memory modules, handling infinitely long documents without performance degradation during extrapolation remains the ultimate challenge in long-text processing. To solve this problem, We introduce a novel agent workflow, \method, which processes text in segments and updates memory through an overwrite strategy, addressing the challenge of long-context task through enhanced memory management. We further extend the DAPO algorithm to directly optimize memory ability in an end-to-end fashion, facilitating training via independent-context multi-conversation generation. Experimental results demonstrate that MemAgent has superb long-context capabilities, being able to extrapolate from an 8K context to a 3.5M QA task with a performance loss of less than 10\% and achieving over 95\% on the 512K NIAH test.

---

## 131. TD-JEPA: Latent-predictive Representations for Zero-Shot Reinforcement Learning

**OpenReview**: [https://openreview.net/forum?id=SzXDuBN8M1](https://openreview.net/forum?id=SzXDuBN8M1)

**Authors**: Marco Bagatella (Max Planck Institute for Intelligent Systems, Max Planck Institute for Intelligent Systems), Matteo Pirotta (Meta), Ahmed Touati (Facebook), Alessandro Lazaric (Facebook), Andrea Tirinzoni (Meta, FAIR)

**Institutions**: Max Planck Institute for Intelligent Systems, Max Planck Institute for Intelligent Systems, Meta, Facebook, Meta, FAIR

**Primary Area**: reinforcement learning

**Keywords**: zero-shot reinforcement learning, unsupervised reinforcement learning, self-predictive representations, joint embedding predictive architecture

**TL;DR**: We propose a temporal-difference latent-predictive method for zero-shot unsupervised RL.

**Abstract**: Latent prediction–where agents learn by predicting their own latents–has emerged as a powerful paradigm for training general representations in machine learning. In reinforcement learning (RL), this approach has been explored to define auxiliary losses for a variety of settings, including reward-based and unsupervised RL, behavior cloning, and world modeling. While existing methods are typically limited to single-task learning, one-step prediction, or on-policy trajectory data, we show that temporal difference (TD) learning enables learning representations predictive of long-term latent dynamics across multiple policies from offline, reward-free transitions. Building on this, we introduce TD-JEPA, which leverages TD-based latent-predictive representations into unsupervised RL. TD-JEPA trains explicit state and task encoders, a policy-conditioned multi-step predictor, and a set of parameterized policies directly in latent space. This enables zero-shot optimization of any reward function at test time. Theoretically, we show that an idealized variant of TD-JEPA avoids collapse with proper initialization, and learns encoders that capture a low-rank factorization of long-term policy dynamics, while the predictor recovers their successor features in latent space. Empirically, TD-JEPA matches or outperforms state-of-the-art baselines on locomotion, navigation, and manipulation tasks across 13 datasets in ExoRL and OGBench, especially in the challenging setting of zero-shot RL from pixels.

---

## 132. NextStep-1: Toward Autoregressive Image Generation with Continuous Tokens at Scale

**OpenReview**: [https://openreview.net/forum?id=Ndnwg9oOQO](https://openreview.net/forum?id=Ndnwg9oOQO)

**Authors**: Chunrui Han (Stepfun), Guopeng Li (StepFun), Jingwei Wu (University of the Chinese Academy of Sciences), Quan Sun (StepFun), Yan Cai (Peking University), Yuang Peng (StepFun Technology Inc.), Zheng Ge (Stepfun), Deyu Zhou (The Hong Kong University of Science and Technology (Guangzhou)), Haomiao Tang (Tsinghua University), Hongyu Zhou (Megvii Technology Inc.), Kenkun Liu (The Chinese University of Hong Kong (Shenzhen）), Shu-Tao Xia (Shenzhen International Graduate School, Tsinghua University), Binxing Jiao (StepFun), Daxin Jiang (StepFun), Xiangyu Zhang (MEGVII Technology), Yibo Zhu (StepFun)

**Institutions**: Stepfun, StepFun, University of the Chinese Academy of Sciences, Peking University, StepFun Technology Inc., The Hong Kong University of Science and Technology (Guangzhou), Tsinghua University, Megvii Technology Inc., The Chinese University of Hong Kong (Shenzhen）, Shenzhen International Graduate School, Tsinghua University, MEGVII Technology

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Generative Models, Autoregressive Models, Diffusion Models, Text-to-image

**Abstract**: Prevailing autoregressive (AR) models for text-to-image generation either rely on heavy, computationally-intensive diffusion models to process continuous image tokens, or employ vector quantization (VQ) to obtain discrete tokens with quantization loss. In this paper, we push the autoregressive paradigm forward with NextStep-1, a 14B autoregressive model paired with a 157M flow matching head, trained on discrete text tokens and continuous image tokens with next-token prediction objectives. NextStep-1 achieves state-of-the-art performance for autoregressive models in text-to-image generation tasks, exhibiting strong capabilities in high-fidelity image synthesis. Furthermore, our method shows strong performance in image editing, highlighting the power and versatility of our unified approach. To facilitate open research, we have released our code and models to the community at https://github.com/stepfun-ai/NextStep-1.

---

## 133. Differentiable Model Predictive Control on the GPU

**OpenReview**: [https://openreview.net/forum?id=bFYfV6c9zu](https://openreview.net/forum?id=bFYfV6c9zu)

**Authors**: Emre Adabag (University of Michigan - Ann Arbor), Marcus Greiff (Toyota Research Institute), John Subosits (Toyota Motor Corporation), Thomas Jonathan Lew

**Institutions**: University of Michigan - Ann Arbor, Toyota Research Institute, Toyota Motor Corporation

**Primary Area**: applications to robotics, autonomy, planning

**Keywords**: differentiable optimization, model predictive control, optimal control, gpu-accelerated optimization, reinforcement learning, imitation learning, robotics

**Abstract**: Differentiable model predictive control (MPC) offers a powerful framework for combining learning and control. However, its adoption has been limited by the inherently sequential nature of traditional optimization algorithms, which are challenging to parallelize on modern computing hardware like GPUs. In this work, we tackle this bottleneck by introducing a GPU-accelerated differentiable optimization tool for MPC. This solver leverages sequential quadratic programming and a custom preconditioned conjugate gradient (PCG) routine with tridiagonal preconditioning to exploit the problem's structure and enable efficient parallelization. We demonstrate substantial speedups over CPU- and GPU-based baselines, significantly improving upon state-of-the-art training times on benchmark reinforcement learning and imitation learning tasks. Finally, we showcase the method on the challenging task of reinforcement learning for driving at the limits of handling, where it enables robust drifting of a Toyota Supra through water puddles.

---

## 134. Planner Aware Path Learning in Diffusion Language Models Training

**OpenReview**: [https://openreview.net/forum?id=lAlI5FuIf7](https://openreview.net/forum?id=lAlI5FuIf7)

**Authors**: Fred Zhangzhi Peng (Duke University), Zachary Bezemek (Duke University), Jarrid Rector-Brooks (California Institute of Technology), Shuibai Zhang (University of Wisconsin - Madison), Michael M. Bronstein (Aithyra), Anru Zhang (Duke University), Joey Bose (Imperial College London), Alexander Tong (Aithyra)

**Institutions**: Duke University, California Institute of Technology, University of Wisconsin - Madison, Aithyra, Imperial College London

**Primary Area**: generative models

**Keywords**: Diffusion Language Models, Discrete Diffusion, Diffusion Models, code generation, protein generation, text generation

**TL;DR**: We propose Planner Aware Path Learning (PAPL), a simple planner-aligned training method for Diffusion Language Models that resolves the training–inference mismatch and consistently improves generation quality.

**Abstract**: Diffusion language models have emerged as a powerful alternative to autoregressive models, enabling fast inference through more flexible and parallel generation paths. This flexibility of sampling is unlocked by new engineered sampling strategies, or *planners*, that select more favorable generation paths by iteratively planning---versus uniformly at random---where to denoise along the sequence. However, by modifying the reverse paths via planning, planners create an irrevocable mismatch between the uniformly random denoising paths during training and planning-based inference. In this paper, we systematically investigate the mismatch of discrete diffusion training and inference under planning and theoretically prove that the standard discrete diffusion training evidence lower bound (ELBO) does not accurately describe a denoiser that uses a non-uniform planner. To address this gap, we derive a new planned evidence lower bound (P-ELBO) that incorporates planner-based reverse dynamics directly into the training objective.
Using the P-ELBO, we introduce *Planner Aware Path Learning* (PAPL), a novel training scheme that aligns training and inference under a planned denoiser.
PAPL is implemented as a simple yet effective modification to the standard masked discrete diffusion loss, making it widely applicable and easy to adopt.
Empirically, we show PAPL delivers consistent gains across domains, including a 40\% relative improvement in protein sequences, improved text generation with up to a $4\times$ relative MAUVE gain, and 23\% relative improvement in code generation HumanEval pass@10.

---

## 135. PateGAIL++: Utility Optimized Private Trajectory Generation with Imitation Learning

**OpenReview**: [https://openreview.net/forum?id=Oyfz6G0hmc](https://openreview.net/forum?id=Oyfz6G0hmc)

**Authors**: Yingjie Ma, Bijal Bharadva (San Diego State University), Xin Zhang (San Diego State University), Joann Qiongna Chen

**Institutions**: San Diego State University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Differential Privacy, Imitation Learning

**Abstract**: Human mobility trajectory data supports a wide range of applications, including urban planning, intelligent transportation systems, and public safety monitoring. However, large-scale, high-quality mobility datasets are difficult to obtain due to privacy concerns. Raw trajectory data may reveal sensitive user information, such as home addresses, routines, or social relationships, making it crucial to develop privacy-preserving alternatives.
Recent advances in deep generative modeling have enabled synthetic trajectory generation, but existing methods either lack formal privacy guarantees or suffer from reduced utility and scalability. Differential Privacy (DP) has emerged as a rigorous framework for data protection, and recent efforts such as PATE-GAN and \textsc{PateGail} integrate DP with generative adversarial learning. While promising, these methods struggle to generalize across diverse trajectory patterns and often incur significant utility degradation.
In this work, we propose a new framework that builds on \textsc{PateGail\texttt{++}} by introducing a \emph{sensitivity-aware noise injection module} that dynamically adjusts privacy noise based on sample-level sensitivity. This design significantly improves trajectory fidelity, downstream task performance, and scalability under strong privacy guarantees. We further adapt our framework to the local differential privacy (LDP) setting, allowing individual-level protection without reliance on a trusted server. We evaluate our method on a real-world mobility dataset and demonstrate its superiority over state-of-the-art baselines in terms of privacy-utility trade-off.

---

## 136. MetaEmbed: Scaling Multimodal Retrieval at Test-Time with Flexible Late Interaction

**OpenReview**: [https://openreview.net/forum?id=yKDqg9HwZX](https://openreview.net/forum?id=yKDqg9HwZX)

**Authors**: Zilin Xiao (Rice University), Qi Ma (Meta), Mengting Gu (Facebook), Chun-cheng Jason Chen (Facebook), Xintao Chen (Facebook), Vicente Ordonez (Rice University), Vijai Mohan (Meta)

**Institutions**: Rice University, Meta, Facebook

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: multimodal retrieval, information retrieval

**Abstract**: Universal multimodal embedding models have achieved great success in capturing semantic relevance between queries and candidates. However, current methods either condense queries and candidates into a single vector, potentially limiting the expressiveness for fine-grained information, or produce too many vectors that are prohibitively expensive for multi-vector retrieval. In this work, we introduce MetaEmbed, a new framework for multimodal retrieval that rethinks how multimodal embeddings are constructed and interacted with at scale. During training, a fixed number of learnable Meta Tokens are appended to the input sequence. At test-time, their last-layer contextualized representations serve as compact yet expressive multi-vector embeddings. Through the proposed Matryoshka Multi-Vector Retrieval training, MetaEmbed learns to organize information by granularity across multiple vectors. As a result, we enable test-time scaling in multimodal retrieval where users can balance retrieval quality against efficiency demands by selecting the number of tokens used for indexing and retrieval interactions. Extensive evaluations on the Massive Multimodal Embedding Benchmark (MMEB) and the Visual Document Retrieval Benchmark (ViDoRe) confirm that MetaEmbed achieves state-of-the-art retrieval performance while scaling robustly to models with 32B parameters. Code is available at https://github.com/facebookresearch/MetaEmbed.

---

## 137. Monocular Normal Estimation via Shading Sequence Estimation

**OpenReview**: [https://openreview.net/forum?id=d7itDxMD1n](https://openreview.net/forum?id=d7itDxMD1n)

**Authors**: Zongrui Li (Nanyang Technological University), Xinhua Ma (Nanyang Technological University), Minghui Hu (Spellbrush), Yunqing Zhao (ByteDance Inc.), Yingchen Yu (Nanyang Technological University), Qian Zheng (Zhejiang University), Chang Liu, Xudong Jiang (Nanyang Technological University), Song Bai (MiroMind)

**Institutions**: Nanyang Technological University, Spellbrush, ByteDance Inc., Zhejiang University, MiroMind

**Primary Area**: generative models

**Keywords**: Video Diffusion Model, Shading Estimation, Single-view Normal Estimation

**Abstract**: Monocular normal estimation aims to estimate the normal map from a single RGB image of an object under arbitrary lights. Existing methods rely on deep models to directly predict normal maps. However, they often suffer from 3D misalignment: while the estimated normal maps may appear to have a correct appearance, the reconstructed surfaces often fail to align with the 3D geometry. We argue that this misalignment stems from the current paradigm: the model struggles to distinguish and reconstruct varying geometry represented in normal maps, as the differences in underlying geometry are reflected only through relatively subtle color variations. To address this issue, we propose a new paradigm that reformulates normal estimation as shading sequence estimation, where shading sequences are more sensitive to various geometry information. Building on this paradigm, we present RoSE, a method that leverages image-to-video generative models to predict shading sequences. The predicted shading sequences are then converted into normal maps by solving a simple ordinary least-squares problem. To enhance robustness and better handle complex objects, RoSE is trained on a synthetic dataset, MultiShade, with diverse shapes, materials, and light conditions. Experiments demonstrate that RoSE achieves state-of-the-art performance on both synthetic and real-world benchmark datasets for object-based monocular normal estimation.

---

## 138. Shoot First, Ask Questions Later? Building Rational Agents that Explore and Act Like People

**OpenReview**: [https://openreview.net/forum?id=EQhUvWH78U](https://openreview.net/forum?id=EQhUvWH78U)

**Authors**: Gabriel Grand (Massachusetts Institute of Technology), Valerio Pepe (School of Engineering and Applied Sciences, Harvard University), Joshua B. Tenenbaum (Massachusetts Institute of Technology), Jacob Andreas (Massachusetts Institute of Technology)

**Institutions**: Massachusetts Institute of Technology, School of Engineering and Applied Sciences, Harvard University

**Primary Area**: applications to neuroscience & cognitive science

**Keywords**: Bayesian experimental design, information-seeking, question asking, Collaborative Battleship, expected information gain (EIG), explore-exploit tradeoffs, resource rationality, probabilistic inference, Monte Carlo sampling, symbolic grounding, code generation, reasoning, decision-oriented dialogue, cognitive modeling, human behavior, language model agents, scientific discovery

**TL;DR**: We introduce a collaborative Battleship task to evaluate information-seeking in humans and agents; insights from Bayesian Experimental Design (BED) yield inference-time strategies for building resource-rational agents in discovery settings.

**Abstract**: Many emerging applications of AI—from scientific discovery to medical diagnosis—require agents to seek information strategically: forming hypotheses, asking targeted questions, and making decisions under uncertainty. In high-stakes settings with limited resources, do language models (LMs) behave like rational agents? Drawing on insights from human cognition, we develop methods to evaluate and enhance agentic information-seeking. First, we introduce a decision-oriented dialogue task called Collaborative Battleship, in which a Captain must balance exploration (asking questions) and action (taking shots), while a Spotter must supply accurate, contextually-grounded answers. Compared to human players (N=42), we find that many LM agents struggle to ask informative questions, produce accurate answers, and identify high-utility actions. To address these gaps, we develop novel Monte Carlo inference strategies for LMs inspired by Bayesian Experimental Design (BED). For Spotter agents, our approach boosts accuracy by up to 14.7% absolute over LM-only baselines; for Captain agents, it raises expected information gain (EIG) by up to 0.227 bits (94.2% of the achievable noise ceiling). Combined, these components yield sharper targeting (+0.303–0.374 F1), and enable weaker LMs, such as Llama-4-Scout, to outperform both humans (8% → 82% win rate) and frontier models (0% → 67% win rate vs. GPT-5) at ≈1% of GPT-5's cost. We replicate these findings on Guess Who?, where our methods significantly boost accuracy (+28.3–42.4 p.p.), demonstrating their general applicability for building information-seeking agents.

---

## 139. Intrinsic Entropy of Context Length Scaling in LLMs

**OpenReview**: [https://openreview.net/forum?id=vnipyA8c9V](https://openreview.net/forum?id=vnipyA8c9V)

**Authors**: Jingzhe Shi (Tsinghua University), Qinwei Ma (Tsinghua University, Tsinghua University), Hongyi Liu (CMU, Carnegie Mellon University), Hang Zhao (Tsinghua University, Tsinghua University), Jenq-Neng Hwang (University of Washington, Seattle), Lei Li

**Institutions**: Tsinghua University, Tsinghua University, Tsinghua University, CMU, Carnegie Mellon University, University of Washington, Seattle

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: context length, intrinsic entropy

**TL;DR**: We propose to use Intrinsic Entropy for understanding impact of context length on Language Modeling, and conduct experiments to validate theoretical assumptions and deductions with language and synthetic datasets.

**Abstract**: There has been work discussing the impact of long context on Language Model performance: some find that long irrelevant context could harm performance, while some experimentally summarize loss reduction by relevant long context as Scaling Laws. This calls for a more thorough understanding on how long context impacts Language Modeling. In this work, we (1) propose to use Intrinsic Entropy for explaining the impact of context length on language modeling; and (2) conduct experiments on natural language and synthetic data, validating our proposed theoretical assumptions and deductions. Our theoretical framework can provide practical insights such as establishing that training dataset size dictates an optimal context length and bounds context length scaling for certain cases. We hope our work may inspire new long context Language Models, as well as future work studying Physics for Language Models.

---

## 140. Latent Particle World Models: Self-supervised Object-centric Stochastic Dynamics Modeling

**OpenReview**: [https://openreview.net/forum?id=lTaPtGiUUc](https://openreview.net/forum?id=lTaPtGiUUc)

**Authors**: Tal Daniel (Carnegie Mellon University), Carl Qi (University of Texas at Austin), Dan Haramati (Brown University), Amir Zadeh (Lambda), Chuan Li (Lambda), Aviv Tamar (Technion, Technion), Deepak Pathak (Skild AI), David Held (Amazon)

**Institutions**: Carnegie Mellon University, University of Texas at Austin, Brown University, Lambda, Technion, Technion, Skild AI, Amazon

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: World Model, Self-supervised, unsupervised, object-centric, video prediciton, video generation, imitation learning, latent particles, vae

**TL;DR**: a self-supervised object-centric world model that learns keypoints, and masks directly from videos, supports multi-modal conditioning, scaled to real-world multi-object datasets

**Abstract**: We introduce Latent Particle World Model (LPWM), a self-supervised object-centric world model scaled to real-world multi-object datasets and applicable in decision-making. LPWM autonomously discovers keypoints, bounding boxes, and object masks directly from video data, enabling it to learn rich scene decompositions without supervision. Our architecture is trained end-to-end purely from videos and supports flexible conditioning on actions, language, and image goals. LPWM models stochastic particle dynamics via a novel latent action module and achieves state-of-the-art results on diverse real-world and synthetic datasets. Beyond stochastic video modeling, LPWM is readily applicable to decision-making, including goal-conditioned imitation learning, as we demonstrate in the paper. Code, data, pre-trained models and video rollouts are available: https://taldatech.github.io/lpwm-web

---

## 141. Beyond Prompt-Induced Lies: Investigating LLM Deception on Benign Prompts

**OpenReview**: [https://openreview.net/forum?id=PDBBYwd1LY](https://openreview.net/forum?id=PDBBYwd1LY)

**Authors**: Zhaomin Wu (National University of Singapore), Mingzhe Du (Nanyang Technological University), See-Kiong Ng (National University of Singapore), Bingsheng He (National University of Singapore)

**Institutions**: National University of Singapore, Nanyang Technological University

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Large Language Model, Deception, Lie, Honest, Trustworthy

**TL;DR**: We detected the widespread deception of LLM under benign prompts and found its tendency increases with task difficulty.

**Abstract**: Large Language Models (LLMs) are widely deployed in reasoning, planning, and decision-making tasks, making their trustworthiness critical. A significant and underexplored risk is intentional deception, where an LLM deliberately fabricates or conceals information to serve a hidden objective. Existing studies typically induce deception by explicitly setting a hidden objective through prompting or fine-tuning, which may not reflect real-world human-LLM interactions. Moving beyond such human-induced deception, we investigate LLMs' self-initiated deception on benign prompts. To address the absence of ground truth, we propose a framework based on Contact Searching Questions~(CSQ). This framework introduces two statistical metrics derived from psychological principles to quantify the likelihood of deception. The first, the *Deceptive Intention Score*, measures the model's bias toward a hidden objective. The second, the *Deceptive Behavior Score*, measures the inconsistency between the LLM's internal belief and its expressed output. Evaluating 16 leading LLMs, we find that both metrics rise in parallel and escalate with task difficulty for most models. Moreover, increasing model capacity does not always reduce deception, posing a significant challenge for future LLM development.

---

## 142. LLM DNA: Tracing Model Evolution via Functional Representations

**OpenReview**: [https://openreview.net/forum?id=UIxHaAqFqQ](https://openreview.net/forum?id=UIxHaAqFqQ)

**Authors**: Zhaomin Wu (National University of Singapore), Haodong Zhao (Shanghai Jiaotong University), Ziyang Wang (national university of singaore, National University of Singapore), Jizhou Guo (Shanghai Jiao Tong University), Qian Wang (National University of Singapore), Bingsheng He (National University of Singapore)

**Institutions**: National University of Singapore, Shanghai Jiaotong University, national university of singaore, National University of Singapore, Shanghai Jiao Tong University

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Large Language Model, Representations, Fingerprint, Embedding, Evolution, Phylogenetic Tree, DNA, Dimension Reduction

**TL;DR**: We introduce LLM DNA, a low-dimensional representation of LLMs, uncovers undocumented relations and constructs phylogenetic tree for LLM.

**Abstract**: The explosive growth of large language models (LLMs) has created a vast but opaque landscape: millions of models exist, yet their evolutionary relationships through fine-tuning, distillation, or adaptation are often undocumented or unclear, complicating LLM management. Existing methods are limited by task specificity, fixed model sets, or strict assumptions about tokenizers or architectures. Inspired by biological DNA, we address these limitations by mathematically defining *LLM DNA* as a low-dimensional, bi-Lipschitz representation of functional behavior. We prove that LLM DNA satisfies *inheritance* and *genetic determinism* and establish its existence. Building on this theory, we derive a general, scalable, training-free pipeline for DNA extraction. In experiments across 305 LLMs, DNA aligns with prior studies on limited subsets and achieves superior or competitive performance on various tasks. Beyond these tasks, DNA comparisons uncover previously undocumented relationships among LLMs. We further construct the evolutionary tree of LLMs using phylogenetic algorithms, which align with shifts from encoder-decoder to decoder-only architectures, reflect temporal progression, and reveal distinct evolutionary speeds across LLM families.

---

## 143. Generative Universal Verifier as Multimodal Meta-Reasoner

**OpenReview**: [https://openreview.net/forum?id=DM0Y0oL33T](https://openreview.net/forum?id=DM0Y0oL33T)

**Authors**: Xinchen Zhang (ByteDance Seed), Xiaoying Zhang (ByteDance AILab), Youbin Wu (ByteDance Inc.), Yanbin Cao (Peking University), Renrui Zhang (MMLab of CUHK & Shanghai AI Laboratory), Ruihang Chu (Wan Team), Ling Yang (Princeton University), Yujiu Yang (Tsinghua University), Guang Shi (ByteDance Inc.)

**Institutions**: ByteDance Seed, ByteDance AILab, ByteDance Inc., Peking University, MMLab of CUHK & Shanghai AI Laboratory, Wan Team, Princeton University, Tsinghua University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Multimodal Large Language Models

**Abstract**: We introduce *Generative Universal Verifier*, a novel concept and plugin designed for next-generation multimodal reasoning in vision-language models and unified multimodal models, providing the fundamental capability of reflection and refinement on visual outcomes during the reasoning and generation process. This work makes three main contributions: (1) We build **ViVerBench**, a comprehensive benchmark spanning $16$ categories of critical tasks for evaluating visual outcomes in multimodal reasoning. Results show that existing VLMs consistently underperform across these tasks, underscoring a substantial gap from human-level capability in reliable visual verification. (2) We design two automated pipelines to construct large-scale visual verification data and train **OmniVerifier-7B**, the first omni-capable generative verifier trained for universal visual verification and achieves notable gains on ViVerBench(+$8.3$). Through training, we identify three atomic capabilities in visual verification and demonstrate how they generalize and interact synergistically. (3) We propose **OmniVerifier-TTS**, a sequential test-time scaling paradigm that leverages the universal verifier to bridge image generation and editing within unified models, enhancing the upper bound of generative ability through iterative fine-grained optimization. Beyond generation, we extend universal verifier to broader world-modeling interleaved reasoning scenarios. Empirically, OmniVerifier-TTS achieves improvements on T2I-ReasonBench(+$3.7$), and GenEval++(+$4.3$), outperforming existing parallel test-time scaling methods, such as Best-of-N. By endowing multimodal reasoning with reliable visual verification, OmniVerifier advances both reliable reflection during generation and scalable test-time refinement, marking a step toward more trustworthy and controllable next-generation reasoning systems.

---

## 144. $PhyWorldBench$: A Comprehensive Evaluation of Physical Realism in Text-to-Video Models

**OpenReview**: [https://openreview.net/forum?id=rlZeILv3fm](https://openreview.net/forum?id=rlZeILv3fm)

**Authors**: Jing Gu (xAI), Xian Liu (xAI), Yu Zeng (NVIDIA), Ashwin Nagarajan (University of California, Santa Cruz), Fangrui Zhu (Northeastern University), Daniel Hong (University of California, Santa Cruz), Yue Fan (University of California, Santa Cruz), Qianqi Yan (University of California, Santa Barbara), Kaiwen Zhou (University of California, Santa Cruz), Ming-Yu Liu (NVIDIA), Xin Eric Wang (University of California, Santa Barbara)

**Institutions**: xAI, NVIDIA, University of California, Santa Cruz, Northeastern University, University of California, Santa Barbara

**Primary Area**: datasets and benchmarks

**Keywords**: Video Generation, Video Evaluation

**TL;DR**: Large-scale, multidimensional video generation for physics

**Abstract**: Video generation models have achieved remarkable progress in creating high-quality, photorealistic content. However, their ability to accurately simulate physical phenomena remains a critical and unresolved challenge. This paper presents $PhyWorldBench$
, a comprehensive benchmark designed to evaluate video generation models based on their adherence to the laws of physics. The benchmark covers multiple levels of physical phenomena, ranging from fundamental principles like object motion and energy conservation to more complex scenarios involving rigid body interactions and human or animal motion. Additionally, we introduce a novel "Anti-Physics" category, where prompts intentionally violate real-world physics, enabling the assessment of whether models can follow such instructions while maintaining logical consistency. Besides large-scale human evaluation, we also design a simple yet effective method that could utilize current MLLM to evaluate the physics realism in a zero-shot fashion. We evaluate 10 state-of-the-art text-to-video generation models, including five open-source and five proprietary models, with a detailed comparison and analysis. we identify pivotal challenges models face in adhering to real-world physics. Through systematic testing of their outputs across 1,050 curated prompts—spanning fundamental, composite, and anti-physics scenarios—we identify pivotal challenges these models face in adhering to real-world physics. We then rigorously examine their performance on diverse physical phenomena with varying prompt types, deriving targeted recommendations for crafting prompts that enhance fidelity to physical principles.

---

## 145. WoW!: World Models in a Closed-Loop World

**OpenReview**: [https://openreview.net/forum?id=yDmb7xAfeb](https://openreview.net/forum?id=yDmb7xAfeb)

**Authors**: Jiahan Zhang, Muqing Jiang (Peking University), Nanru Dai (Johns Hopkins University), TaiMing Lu (Princeton University), Arda Uzunoglu (Johns Hopkins University), Shunchi Zhang, Yana Wei (Johns Hopkins University), Jiahao Wang, Vishal M. Patel (Johns Hopkins University), Paul Pu Liang (Massachusetts Institute of Technology), Daniel Khashabi (Johns Hopkins University), Cheng Peng (School of Data Science, University of Virginia), Rama Chellappa, Tianmin Shu (Johns Hopkins University), Alan Yuille (Johns Hopkins University), Yilun Du (Google), Jieneng Chen (Johns Hopkins University)

**Institutions**: Peking University, Johns Hopkins University, Princeton University, Massachusetts Institute of Technology, School of Data Science, University of Virginia, Google

**Primary Area**: generative models

**Keywords**: world models, video generation, embodied AI, generative models

**TL;DR**: By grounding assessment in embodied task success instead of video metrics, WoW! provides a principled yardstick for future research on generative world models in the context of embodiment

**Abstract**: Generative world models (WMs) can now simulate worlds with striking visual realism, which naturally raises the question of whether they can endow embodied agents with predictive perception for decision making. Progress on this question has been limited by fragmented evaluation: most existing benchmarks adopt open-loop protocols that emphasize visual quality in isolation, leaving the core issue of embodied utility unresolved, i.e., *do WMs actually help agents succeed at embodied tasks?*
To address this gap, we introduce WoW!, the first open platform that benchmarks WMs in a closed-loop setting that mirrors real agent-environment interactions. WoW! provides a unified online planning strategy and a standardized action API, enabling heterogeneous WMs for decision making.
We curate four closed-loop environments that rigorously evaluate diverse WMs, prioritize task success as the primary metric, and move beyond the common focus on visual quality; we also present the first data scaling law for world models in embodied settings.
Our study uncovers three surprises: (1) visual quality alone does not guarantee task success—controllability matters more; (2) scaling post-training with action-observation data is more effective than upgrading the pretrained video generators; and (3) allocating more inference-time compute allows WMs to substantially improve closed-loop performance. By centering evaluation on closed-loop outcomes, WoW! establishes a new benchmark for the systematic assessment of WMs.

---

## 146. Multimodal Aligned Semantic Knowledge for Unpaired Image-text Matching

**OpenReview**: [https://openreview.net/forum?id=d3CISVVO6v](https://openreview.net/forum?id=d3CISVVO6v)

**Authors**: Laiguo Yin (Shandong University), Yixin Zhang (Nanyang Technological University), YUQING SUN (Shandong University), Lizhen Cui (Shandong University)

**Institutions**: Shandong University, Nanyang Technological University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Unpaired Image-text Matching, Out-of-Distribution Word, Multimodal Aligned Semantic Knowledge, Prototype

**TL;DR**: We propose multimodal aligned semantic knowledge, which leverages word embeddings as bridges to associate words with prototypes, capturing semantic relationships between words and further utilizing information from OOD words.

**Abstract**: While existing approaches address unpaired image-text matching by constructing cross-modal aligned knowledge, they often fail to identify semantically corresponding visual representations for Out-of-Distribution (OOD) words. Moreover, the distributional variance of visual representations associated with different words varies significantly, which negatively impacts matching accuracy. To address these issues, we propose a novel method namely Multimodal Aligned Semantic Knowledge (MASK), which leverages word embeddings as bridges to associate words with their corresponding prototypes, thereby enabling semantic knowledge alignment between the image and text modalities. For OOD words, the representative prototypes are constructed by leveraging the semantic relationships encoded in word embeddings. Beyond that, we introduce a prototype consistency contrastive loss to structurally regularize the feature space, effectively mitigating the adverse effects of variance. Experimental results on the Flickr30K and MSCOCO datasets demonstrate that MASK achieves superior performance in unpaired matching.

---

## 147. DiffusionNFT: Online Diffusion Reinforcement with Forward Process

**OpenReview**: [https://openreview.net/forum?id=VJZ477R89F](https://openreview.net/forum?id=VJZ477R89F)

**Authors**: Kaiwen Zheng (Tsinghua University), Huayu Chen (Tsinghua University), Haotian Ye (Stanford University), Haoxiang Wang (NVIDIA), Qinsheng Zhang (NVIDIA), Kai Jiang (Tsinghua University), Hang Su (Tsinghua University), Stefano Ermon (Stanford University), Jun Zhu (Tsinghua University), Ming-Yu Liu (NVIDIA)

**Institutions**: Tsinghua University, Stanford University, NVIDIA

**Primary Area**: generative models

**Keywords**: Diffusion Models, Reinforcement Learning, Flow Matching

**TL;DR**: We propose a new online reinforcement learning (RL) algorithm for diffusion and flow models based on forward process.

**Abstract**: Online reinforcement learning (RL) has been central to post-training language models, but its extension to diffusion models remains challenging due to intractable likelihoods. Recent works discretize the reverse sampling process to enable GRPO-style training, yet they inherit fundamental drawbacks, including solver restrictions, forward–reverse inconsistency, and complicated integration with classifier-free guidance (CFG). We introduce Diffusion Negative-aware FineTuning (DiffusionNFT), a new online RL paradigm that optimizes diffusion models directly on the forward process via flow matching. DiffusionNFT contrasts positive and negative generations to define an implicit policy improvement direction, naturally incorporating reinforcement signals into the supervised learning objective. 
This formulation enables training with arbitrary black-box solvers, eliminates the need for likelihood estimation, and requires only clean images rather than sampling trajectories for policy optimization. DiffusionNFT is up to $25\times$ more efficient than FlowGRPO in head-to-head comparisons, while being CFG-free. For instance, DiffusionNFT improves the GenEval score from 0.24 to 0.98 within 1k steps, while FlowGRPO achieves 0.95 with over 5k steps and additional CFG employment. By leveraging multiple reward models, DiffusionNFT significantly boosts the performance of SD3.5-Medium in every benchmark tested.

---

## 148. The Spacetime of Diffusion Models: An Information Geometry Perspective

**OpenReview**: [https://openreview.net/forum?id=qCsbYJZRA5](https://openreview.net/forum?id=qCsbYJZRA5)

**Authors**: Rafal Karczewski (Aalto University), Markus Heinonen (Aalto University), Alison Pouplin, Søren Hauberg (Technical University of Denmark), Vikas K Garg

**Institutions**: Aalto University, Technical University of Denmark

**Primary Area**: generative models

**Keywords**: diffusion models, information geometry

**Abstract**: We present a novel geometric perspective on the latent space of diffusion models. We first show that the standard pullback approach, utilizing the deterministic probability flow ODE decoder, is fundamentally flawed. It provably forces geodesics to decode as straight segments in data space, effectively ignoring any intrinsic data geometry beyond the ambient Euclidean space. Complementing this view, diffusion also admits a stochastic decoder via the reverse SDE, which enables an information geometric treatment with the Fisher-Rao metric. However, a choice of $\mathbf{x}_T$ as the latent representation collapses this metric due to memorylessness. We address this by introducing a latent spacetime $\mathbf{z}=(\mathbf{x}_t,t)$ that indexes the family of denoising distributions $p(\mathbf{x}_0 | \mathbf{x}_t)$ across all noise scales, yielding a nontrivial geometric structure. We prove these distributions form an exponential family and derive simulation-free estimators for curve lengths, enabling efficient geodesic computation. The resulting structure induces a principled Diffusion Edit Distance, where geodesics trace minimal sequences of noise and denoise edits between data. We also demonstrate benefits for transition path sampling in molecular systems, including constrained variants such as low-variance transitions and region avoidance. Code is available at: https://github.com/rafalkarczewski/spacetime-geometry.

---

## 149. Reducing Belief Deviation in Reinforcement Learning for Active Reasoning

**OpenReview**: [https://openreview.net/forum?id=r8hzDA3pUY](https://openreview.net/forum?id=r8hzDA3pUY)

**Authors**: Deyu Zou (Department of Computer Science and Engineering, The Chinese University of Hong Kong), Yongqiang Chen (Mohamed bin Zayed University of Artificial Intelligence), Jianxiang Wang (ByteDance Inc.), Garry YANG (Department of Computer Science and Engineering, The Chinese University of Hong Kong), Mufei Li (Georgia Institute of Technology), Qing Da (ByteDance Inc.), James Cheng (The Chinese University of Hong Kong), Pan Li (Georgia Institute of Technology), Yu Gong (ByteDance Inc.)

**Institutions**: Department of Computer Science and Engineering, The Chinese University of Hong Kong, Mohamed bin Zayed University of Artificial Intelligence, ByteDance Inc., Georgia Institute of Technology, The Chinese University of Hong Kong

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Large language models, LLM reasoning, Agentic multi-turn reasoning

**Abstract**: Active reasoning requires large language models (LLMs) to interact with external sources and strategically gather information to solve problems. Central to this process is belief tracking: maintaining a coherent understanding of the problem state and the missing information toward the solution. However, due to limited reasoning capabilities, LLM-based agents often suffer from belief deviation: they struggle to correctly model beliefs, lose track of problem states, and fall into uninformative or repetitive actions. Once this happens, errors compound and reinforcement learning (RL) training fails to properly credit the crucial exploratory steps.  To address this issue, we propose to track the deviation of model beliefs and develop $\mathbf{T^3}$, a simple yet effective method that detects excessive belief deviation and truncates trajectories during training to remove uninformative tails. By preserving credit for informative prefixes, $\mathbf{T^3}$ systematically improves policy optimization. Across 5 challenging tasks, $\mathbf{T^3}$ consistently enhances training stability, token efficiency, and final performance, achieving up to 30\% gains while cutting rollout tokens by roughly 25\%. These results highlight belief control as a key principle for developing robust and generalizable LLM-based active reasoners.

---

## 150. Information Shapes Koopman Representation

**OpenReview**: [https://openreview.net/forum?id=Szh0ELyQxL](https://openreview.net/forum?id=Szh0ELyQxL)

**Authors**: Xiaoyuan Cheng (University College London, University of London), Wenxuan Yuan (Imperial College London), Yiming Yang (University College London, University of London), Yuanzhao Zhang (Santa Fe Institute), Sibo Cheng (Ecole Nationale des Ponts et Chausees), Yi He (University College London, University of London), Zhuo Sun (Shanghai University of Finance and Economics)

**Institutions**: University College London, University of London, Imperial College London, Santa Fe Institute, Ecole Nationale des Ponts et Chausees, Shanghai University of Finance and Economics

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: Koopman Operator, Latent subspace reconstruction, representation for physical systems

**TL;DR**: Because the Koopman operator is infinite-dimensional, identifying tractable finite-dimensional subspaces is challenging. We aim to construct these subspaces through information theory.

**Abstract**: The Koopman operator provides a powerful framework for modeling dynamical systems and has attracted growing interest from the machine learning community. However, its infinite-dimensional nature makes identifying suitable finite-dimensional subspaces challenging, especially for deep architectures. We argue that these difficulties come from suboptimal representation learning, where latent variables fail to balance expressivity and simplicity. This tension is closely related to the information bottleneck (IB) dilemma: constructing compressed representations that are both compact and predictive. Rethinking Koopman learning through this lens, we demonstrate that latent mutual information promotes simplicity, yet an overemphasis on simplicity may cause latent space to collapse onto a few dominant modes. In contrast, expressiveness is sustained by the von Neumann entropy, which prevents such collapse and encourages mode diversity. This insight leads us to propose an information-theoretic Lagrangian formulation that explicitly balances this tradeoff. Furthermore, we propose a new algorithm based on the Lagrangian formulation that encourages both simplicity and expressiveness, leading to a stable and interpretable Koopman representation. Beyond quantitative evaluations, we further visualize the learned manifolds under our representations, observing empirical results consistent with our theoretical predictions. Finally, we validate our approach across a diverse range of dynamical systems, demonstrating improved performance over existing Koopman learning methods.

---

## 151. Sequences of Logits Reveal the Low Rank Structure of Language Models

**OpenReview**: [https://openreview.net/forum?id=gdZ6J5hZzF](https://openreview.net/forum?id=gdZ6J5hZzF)

**Authors**: Noah Golowich (Microsoft), Allen Liu (Massachusetts Institute of Technology), Abhishek Shetty (Massachusetts Institute of Technology)

**Institutions**: Microsoft, Massachusetts Institute of Technology

**Primary Area**: learning theory

**Keywords**: Large language models, low-rank structure

**TL;DR**: We exploit the low-rank structure of the logit matrices of LLMs to draw new empirical and theoretical conclusions.

**Abstract**: A major problem in the study of large language models  is to understand their inherent low-dimensional structure.  We introduce an approach to study the low-dimensional structure of language models at a model-agnostic level: as sequential probabilistic models. We first empirically demonstrate that a wide range of modern language models exhibit low-rank structure: in particular, matrices built from the model's logits for varying sets of prompts and responses have low approximate rank. We then show that this low-rank structure can be leveraged for generation --- in particular, we can generate a response to a target prompt using a linear combination of the model's outputs on unrelated, or even nonsensical prompts.

On the theoretical front, we observe that studying the approximate rank of language models in the sense discussed above yields a simple universal abstraction whose theoretical predictions parallel our experiments. We then analyze the representation power of the abstraction and give provable learning guarantees.

---

## 152. BIRD-INTERACT: Re-imagining Text-to-SQL Evaluation via Lens of Dynamic Interactions

**OpenReview**: [https://openreview.net/forum?id=nHrYBGujps](https://openreview.net/forum?id=nHrYBGujps)

**Authors**: Nan Huo (the University of Hong Kong, University of Hong Kong), Xiaohan Xu (The University of Hong Kong), Jinyang Li (The University of Hong Kong), Per Jacobsson (Google), Shipei Lin (The Chinese University of Hong Kong, Shenzhen), Bowen Qin (Beijing Academy of Artificial Intelligence), Binyuan Hui (Alibaba Group), Xiaolong Li (University of Hong Kong), Ge Qu, Shuzheng Si (Tsinghua University), Linheng Han (The Chinese University of Hong Kong, Shenzhen), Edward Alexander (The Chinese University of Hong Kong), Xintong Zhu (The Chinese University of Hong Kong, Shenzhen), Rui Qin (The Chinese University of Hong Kong), Ruihan Yu (The Chinese University of Hong Kong), Yiyao Jin (The Chinese University of Hong Kong), Feige Zhou (The Chinese University of Hong Kong), Weihao Zhong (The Chinese University of Hong Kong，Shenzhen), Yun Chen (The Chinese University of Hong Kong), Hongyu Liu (Guizhou University), Chenhao Ma (The Chinese University of Hong Kong, Shenzhen), Fatma Ozcan (Google), Yannis Papakonstantinou (Google), Reynold Cheng (The University of Hong Kong)

**Institutions**: the University of Hong Kong, University of Hong Kong, The University of Hong Kong, Google, The Chinese University of Hong Kong, Shenzhen, Beijing Academy of Artificial Intelligence, Alibaba Group, University of Hong Kong, Tsinghua University, The Chinese University of Hong Kong, The Chinese University of Hong Kong，Shenzhen, Guizhou University

**Primary Area**: datasets and benchmarks

**Keywords**: Interactive, Text-to-SQL, LLM, Code Generation

**Abstract**: Large language models (LLMs) have demonstrated remarkable performance on single-turn text-to-SQL tasks, but real-world database applications predominantly require multi-turn interactions to handle ambiguous queries, execution errors, and evolving user requirements. Existing multi-turn benchmarks fall short of capturing this complexity, either by treating conversation histories as static context or by limiting evaluation to narrow, read-only (SELECT-ONLY) operations, thereby failing to reflect the challenges encountered in production-grade database assistant. In this work, we introduce BIRD-INTERACT, a benchmark that restores this missing realism through: (1) a ***comprehensive interaction environment*** that couples each database with a hierarchical knowledge base, metadata files, and a function-driven user simulator, enabling models to solicit clarifications, retrieve knowledge, and recover from execution errors without human supervision; (2) two ***evaluation settings*** reflecting real-world interaction settings which contain a pre-defined conversational protocol (c-Interact) and a more open-ended agentic setting (a-Interact) in which the model autonomously decides when to query the user simulator or explore the DB environment; (3) a ***challenging task suite*** that covers the full CRUD spectrum for both business-intelligence and operational use cases, guarded by executable test cases. Each task features ambiguous and follow-up sub-tasks, requiring LLMs to engage in dynamic interaction. The suite is organized into two sets: a full set (**BIRD-INTERACT-FULL**) of 600 tasks which unfold up to **11,796** dynamic interactions for a comprehensive overview of performance and a lite set (**BIRD-INTERACT-LITE**) of 300 tasks, with simplified databases for detailed behavioral analysis of interactions, and fast development of methods. Our empirical results highlight the difficulty of BIRD-INTERACT: the most recent flagship model GPT-5 completes only **8.67%** of tasks in the c-Interact setting and **17.00%** in the a-Interact setting on the full task suite. Further analysis via memory grafting and Interaction Test-time Scaling (ITS), validate the importance of effective interaction for achieving success in complex, dynamic text-to-SQL tasks.

---

## 153. EditVerse: Unifying Image and Video Editing and Generation with In-Context Learning

**OpenReview**: [https://openreview.net/forum?id=blJXE07r7I](https://openreview.net/forum?id=blJXE07r7I)

**Authors**: Xuan Ju (Chinese University of Hong Kong), Tianyu Wang (Adobe Systems), Yuqian Zhou (Adobe Systems), He Zhang (Adobe Systems), Qing Liu (Adobe Systems), Nanxuan Zhao, Zhifei Zhang (Adobe Research), Yijun Li (Adobe Research), Yuanhao Cai (Johns Hopkins University), Shaoteng Liu (Adobe Research), Daniil Pakhomov (Adobe Systems), Zhe Lin (Adobe Research), Soo Ye Kim (Adobe Systems), Qiang Xu (The Chinese University of Hong Kong)

**Institutions**: Chinese University of Hong Kong, Adobe Systems, Adobe Research, Johns Hopkins University, The Chinese University of Hong Kong

**Primary Area**: generative models

**Keywords**: Video Editing, Content Generation, Artificial Intelligence

**Abstract**: Recent advances in foundation models highlight a clear trend toward unification and scaling, showing emergent capabilities across diverse domains. While image generation and editing have rapidly transitioned from task-specific to unified frameworks, video generation and editing remain fragmented due to architectural limitations and data scarcity. In this work, we introduce EditVerse, a unified framework for image and video generation and editing within a single model. By representing all modalities, i.e., text, image, and video, as a unified token sequence, EditVerse leverages self-attention to achieve robust in-context learning, natural cross-modal knowledge transfer, and flexible handling of inputs and outputs with arbitrary resolutions and durations. To address the lack of video editing training data, we design a scalable data pipeline that curates 232K video editing samples and combines them with large-scale image and video datasets for joint training. Furthermore, we present EditVerseBench, the first benchmark for instruction-based video editing covering diverse tasks and resolutions. Extensive experiments and user studies demonstrate that EditVerse achieves state-of-the-art performance, surpassing existing open-source and commercial models, while exhibiting emergent editing and generation abilities across modalities.

---

## 154. The Art of Scaling Reinforcement Learning Compute for LLMs

**OpenReview**: [https://openreview.net/forum?id=FMjeC9Msws](https://openreview.net/forum?id=FMjeC9Msws)

**Authors**: Fnu Devvrit (, University of Texas at Austin), Lovish Madaan (Meta), Rishabh Tiwari (University of California, Berkeley), Rachit Bansal (Harvard University), Sai Surya Duvvuri (University of Texas at Austin), Manzil Zaheer (Zaheer), Inderjit S Dhillon (Google), David Brandfonbrener (Anthropic), Rishabh Agarwal (McGill University)

**Institutions**: , University of Texas at Austin, Meta, University of California, Berkeley, Harvard University, University of Texas at Austin, Zaheer, Google, Anthropic, McGill University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Scaling, LLMs, Reasoning

**TL;DR**: We study compute scaling properties of RL methods on LLMs

**Abstract**: Reinforcement learning (RL) has become central to training large language models (LLMs), yet the field lacks predictive scaling methodologies comparable to those established for pre-training.
    Despite rapidly rising compute budgets, there is no principled understanding of
    how to evaluate algorithmic improvements for scaling RL compute.
    We present the first large-scale systematic study, amounting to more than 400,000 GPU-hours, that defines a principled framework for analyzing and predicting RL scaling in LLMs.
    We fit sigmoidal compute-performance curves for RL training and ablate a wide range of common design choices to analyze their effects on asymptotic performance and compute efficiency. We observe:
    (1)
    Not all recipes yield similar asymptotic  performance,
    Details such as loss aggregation, normalization, curriculum, and off-policy algorithm primarily modulate compute efficiency without materially shifting the asymptote, and
    (3) Stable, scalable recipes follow predictable scaling trajectories, enabling extrapolation from smaller-scale runs.
    Combining these insights, we propose a _best-practice_ recipe, ScaleRL, and demonstrate its effectiveness by successfully scaling and predicting validation performance on a single RL run scaled up to 100,000 GPU-hours.
    Our work provides both a _scientific framework_ for analyzing scaling in RL and a practical recipe that brings RL training closer to the predictability long achieved in pre-training.

---

## 155. Partition Generative Modeling: Masked Modeling Without Masks

**OpenReview**: [https://openreview.net/forum?id=vEh1ceS154](https://openreview.net/forum?id=vEh1ceS154)

**Authors**: Justin Deschenaux (EPFL - EPF Lausanne), Lan Tran (EPFL - EPF Lausanne), Caglar Gulcehre (Microsoft)

**Institutions**: EPFL - EPF Lausanne, Microsoft

**Primary Area**: generative models

**Keywords**: masked generative modeling, discrete diffusion, masked diffusion language modeling, diffusion language modeling

**TL;DR**: We show that it is possible to train masked generative models without using MASK tokens, resulting in efficiency gains at inference.

**Abstract**: Masked generative models (MGMs) can generate tokens in parallel and in any order, unlike autoregressive models (ARMs), which decode one token at a time, left-to-right. However, MGMs process the full-length sequence at every sampling step, including \mask tokens that carry no information. In contrast, ARMs process only the previously generated tokens.
We introduce ``Partition Generative Models'' (PGMs), which replace masking with partitioning. Tokens are split into two groups that cannot attend to each other, and the model learns to predict each group conditioned on the other, eliminating mask tokens entirely. Because the groups do not interact, PGMs can process only the clean tokens during sampling, like ARMs, while retaining parallel, any-order generation, like MGMs.
On OpenWebText, PGMs achieve $5-5.5\times$ higher throughput than MDLM while producing samples with lower Generative Perplexity. On ImageNet, PGMs reach comparable FID to MaskGIT with a $7.5\times$ throughput improvement. With twice as many steps, the FID improves to 4.56 while remaining $3.9\times$ faster than MGMs. Finally, PGMs remain compatible with existing MGM samplers and distillation methods.

---

## 156. How Do Transformers Learn to Associate Tokens: Gradient Leading Terms Bring Mechanistic Interpretability

**OpenReview**: [https://openreview.net/forum?id=A4Us8jxVGq](https://openreview.net/forum?id=A4Us8jxVGq)

**Authors**: Shawn Im (Department of Computer Science, University of Wisconsin - Madison), Changdae Oh (Department of Computer Science, University of Wisconsin - Madison), Zhen Fang (University of Technology Sydney), Sharon Li (University of Wisconsin - Madison)

**Institutions**: Department of Computer Science, University of Wisconsin - Madison, University of Technology Sydney, University of Wisconsin - Madison

**Primary Area**: interpretability and explainable AI

**Keywords**: Semantic associations, Interpretability, LLM

**Abstract**: Semantic associations such as the link between "bird" and "flew" are foundational for language modeling as they enable models to go beyond memorization and instead generalize and generate coherent text. Understanding how these associations are learned and represented in language models is essential for connecting deep learning with linguistic theory and developing a mechanistic foundation for large language models. In this work, we analyze how these associations emerge from natural language data in attention-based language models through the lens of training dynamics. By leveraging a leading-term approximation of the gradients, we develop closed-form expressions for the weights at early stages of training that explain how semantic associations first take shape. Through our analysis, we reveal that each set of weights of the transformer has closed-form expressions as simple compositions of three basis functions--bigram, token-interchangeability, and context mappings--reflecting the statistics in the text corpus and uncover how each component of the transformer captures the semantic association based on these compositions. Experiments on real-world LLMs demonstrate that our theoretical weight characterizations closely match the learned weights, and qualitative analyses further guide us on how our theorem shines light on interpreting the learned association in transformers.

---

## 157. On the Reasoning Abilities of Masked Diffusion Language Models

**OpenReview**: [https://openreview.net/forum?id=BVnIsh4Nz1](https://openreview.net/forum?id=BVnIsh4Nz1)

**Authors**: Anej Svete (Department of Computer Science, ETHZ - ETH Zurich), Ashish Sabharwal (Allen Institute for AI)

**Institutions**: Department of Computer Science, ETHZ - ETH Zurich, Allen Institute for AI

**Primary Area**: other topics in machine learning (i.e., none of the above)

**Keywords**: diffusion language models, formal language theory, boolean circuits, expressivity, transformers, masked diffusion models, chain of thought, looped transformers

**TL;DR**: We prove that masked text diffusion models are equivalent to padded looped transformers, can solve all problems that chain-of-thought transformers can, and are more efficient on certain problem classes due to their parallel generation mechanism.

**Abstract**: Masked diffusion models (MDMs) for text offer a compelling alternative to traditional autoregressive language models. Parallel generation makes them efficient, but their computational capabilities and the limitations inherent in their parallelism remain largely unexplored. To this end, we characterize what types of reasoning problems MDMs can provably solve and how efficiently. We do this by connecting MDMs to the well-understood reasoning frameworks of chain of thought (CoT) and padded looped transformers (PLTs) in the finite-precision log-width setting: We show that MDMs and polynomially-padded PLTs are, in fact, equivalent in this setting, and that MDMs can solve all problems that CoT-augmented transformers can. Moreover, we showcase classes of problems (including regular languages) for which MDMs are inherently more efficient than CoT transformers, where parallel generation allows for substantially faster reasoning.

---

## 158. FRABench and UFEval: Unified Fine-grained Evaluation with Task and Aspect Generalization

**OpenReview**: [https://openreview.net/forum?id=7WdY3Cojy9](https://openreview.net/forum?id=7WdY3Cojy9)

**Authors**: Shibo Hong (Fudan University), Jiahao Ying (Singapore Management University), Haiyuan Liang (Fudan University), Mengdi Zhang (NeoShell), Jun Kuang (Meituan-M17), Jiazheng Zhang (Fudan University), Yixin Cao (Fudan University)

**Institutions**: Fudan University, Singapore Management University, NeoShell, Meituan-M17

**Primary Area**: datasets and benchmarks

**Keywords**: Aspect-level Evaluation Dataset, Unified Fine-grained Evaluation

**Abstract**: Evaluating open-ended outputs of Multimodal Large Language Models has become a bottleneck as model capabilities, task diversity, and modality rapidly expand. Existing ``MLLM-as-a-Judge'' evaluators, though promising, remain constrained to specific tasks and aspects (i.e., specific evaluation criteria such as fluency for text and image quality for images). In this paper, we argue that, on one hand, based on the interconnected nature of criteria, learning specific aspects can generalize to unseen aspects; on the other hand, jointly learning to assess multiple visual criteria and tasks may foster a synergistic effect. To this end, we propose UFEval, the first unified fine-grained evaluator with task and aspect generalization for four evaluation tasks --- Natural Language Generation, Image Understanding, Image Generation, and Interleaved Text-and-Image Generation. However, training such a unified evaluator is hindered by the lack of a large-scale, multi-modal, and aspect-level resource. To address this gap, we introduce FRABench, a comprehensive fine-grained evaluation dataset. Specifically, (1) We first construct a hierarchical aspect taxonomy encompassing 112 distinct aspects across the aforementioned four tasks. (2) Based on this taxonomy, we create FRABench, comprising 60.4k pairwise samples with 325k evaluation labels obtained from a combination of human and GPT-4o annotations. (3) Finally, leveraging FRABench, we develop UFEval, a unified fine-grained evaluator. Experiments show that learning on specific aspects enables UFEval to generalize to unseen aspects, and joint learning to assess diverse visual tasks and aspects can lead to substantial mutual benefits.

---

## 159. Quotient-Space Diffusion Model

**OpenReview**: [https://openreview.net/forum?id=3JPAkwSVc4](https://openreview.net/forum?id=3JPAkwSVc4)

**Authors**: Yixian Xu (Peking University), Yusong Wang (MSR AI4Science China), Shengjie Luo (ByteDance Seed), Kaiyuan Gao (Huazhong University of Science and Technology), Tianyu He (Microsoft Research Asia), Chang Liu (Zhongguancun Academy), Di He (Peking University)

**Institutions**: Peking University, MSR AI4Science China, ByteDance Seed, Huazhong University of Science and Technology, Microsoft Research Asia, Zhongguancun Academy

**Primary Area**: generative models

**Keywords**: Diffusion Models, Generative Modeling, Geometric Deep Learning, Structure Generation

**Abstract**: Diffusion-based generative models have reformed generative AI, and have enabled new capabilities in the science domain, for example, generating 3D structures of molecules.
Due to the intrinsic problem structure of certain tasks, there is often a symmetry in the system, which identifies objects that can be converted by a group action as equivalent, hence the target distribution is essentially defined on the quotient space with respect to the group.
In this work, we establish a formal framework for diffusion modeling on a general quotient space, and apply it to molecular structure generation which follows the special Euclidean group SE(3) symmetry.
The framework reduces the necessity of learning the component corresponding to the group action, hence simplifies learning difficulty over conventional group-equivariant diffusion models, and the sampler guarantees recovering the target distribution, while heuristic alignment strategies lack proper samplers.
The arguments are empirically validated on structure generation for small molecules and proteins, indicating that the principled quotient-space diffusion model provides a new  framework that outperforms previous symmetry treatments.

---

## 160. SWINGARENA: Adversarial Programming Arena for Long-context GitHub Issue Solving

**OpenReview**: [https://openreview.net/forum?id=YuxgSGFaqb](https://openreview.net/forum?id=YuxgSGFaqb)

**Authors**: Wendong XU (University of Hong Kong), Jing Xiong (University of Hong Kong), Chenyang Zhao (UCLA Computer Science Department, University of California, Los Angeles), Qiujiang Chen (Southern University of Science and Technology), Haoran Wang (Tsinghua University), Hui Shen (University of Michigan - Ann Arbor), Zhongwei Wan (Ohio State University, Columbus), Jianbo Dai (Huawei Technologies Ltd.), Taiqiang Wu (The University of Hong Kong), He Xiao (University of Hong Kong), Chaofan Tao (The University of Hong Kong), Zhuoqing Mao (Google), Ying Sheng (xAI), Zhijiang Guo (The Hong Kong University of Science and Technology (Guangzhou)), Hongxia Yang (Hong Kong Polytechnic University), Bei Yu (Department of Computer Science and Engineering, The Chinese University of Hong Kong), Lingpeng Kong (Department of Computer Science, The University of Hong Kong), Quanquan Gu (ByteDance Seed), Ngai Wong (The University of Hong Kong)

**Institutions**: University of Hong Kong, UCLA Computer Science Department, University of California, Los Angeles, Southern University of Science and Technology, Tsinghua University, University of Michigan - Ann Arbor, Ohio State University, Columbus, Huawei Technologies Ltd., The University of Hong Kong, Google, xAI, The Hong Kong University of Science and Technology (Guangzhou), Hong Kong Polytechnic University, Department of Computer Science and Engineering, The Chinese University of Hong Kong, Department of Computer Science, The University of Hong Kong, ByteDance Seed

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Arena, Real-World GitHub Issues, Adversarial Programming, Retrieval-Augmented Generation, Continuous Integration, Code Benchmark

**Abstract**: We present \textsc{SwingArena}, a adversarial evaluation framework for Large Language Models (LLMs) that closely mirrors real-world software development workflows. Unlike traditional static benchmarks, \textsc{SwingArena} models the collaborative process of software iteration by pairing LLMs as \textit{submitters}, who generate patches, and \textit{reviewers}, who create test cases and verify the patches through continuous integration (CI) pipelines. To support these interactive evaluations, we introduce a retrieval-augmented code generation (RACG) module that efficiently handles long-context challenges by providing syntactically and semantically relevant code snippets from large codebases, supporting multiple programming languages (C++, Python, Rust, and Go). This enables the framework to scale across diverse tasks and contexts while respecting token limitations. Our experiments, using over 400 high-quality real-world GitHub issues selected from a pool of 2,300 issues, show that models like GPT-4o excel at aggressive patch generation, whereas DeepSeek and Gemini prioritize correctness in CI validation. \textsc{SwingArena} presents a scalable and extensible methodology for evaluating LLMs in realistic, CI-driven software development settings.

---

## 161. AnyUp: Universal Feature Upsampling

**OpenReview**: [https://openreview.net/forum?id=Y9UAgPehqo](https://openreview.net/forum?id=Y9UAgPehqo)

**Authors**: Thomas Wimmer (Max-Planck Institute), Prune Truong (Google), Marie-Julie Rakotosaona (Google), Michael Oechsle (Google), Federico Tombari (Google), Bernt Schiele (Max Planck Institute for Informatics, Saarland Informatics Campus), Jan Eric Lenssen (Saarland Informatics Campus, Max-Planck Institute)

**Institutions**: Max-Planck Institute, Google, Max Planck Institute for Informatics, Saarland Informatics Campus, Saarland Informatics Campus, Max-Planck Institute

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: feature upsampling, representation learning

**TL;DR**: A universal feature upsampling model that can be used to upsample any feature from any to any resolution and generalizes to features unseen during training.

**Abstract**: We introduce AnyUp, a method for feature upsampling that can be applied to any vision feature at any resolution, without encoder-specific training. Existing learning-based upsamplers for features like DINO or CLIP need to be re-trained for every feature extractor and thus do not generalize to different feature types at inference time. In this work, we propose an *inference-time* feature-agnostic upsampling architecture to alleviate this limitation and improve upsampling quality. In our experiments, AnyUp sets a new state of the art for upsampled features, generalizes to different feature types, and  preserves feature semantics while being efficient and easy to apply to a wide range of downstream tasks.

---

## 162. High-dimensional Analysis of Synthetic Data Selection

**OpenReview**: [https://openreview.net/forum?id=Y54P2BBPPh](https://openreview.net/forum?id=Y54P2BBPPh)

**Authors**: Parham Rezaei (Institute of Science and Technology Austria), Filip Kovačević (Institute of Science and Technology Austria), Francesco Locatello (Institute of Science and Technology), Marco Mondelli (Institute of Science and Technology Austria)

**Institutions**: Institute of Science and Technology Austria, Institute of Science and Technology

**Primary Area**: transfer learning, meta learning, and lifelong learning

**Keywords**: high dimensional regression, empirical risk minimization, synthetic data, generative models

**TL;DR**: We give a precise analysis for the problem of synthetic data selection through the lens of high-dimensional regression, and we translate the theoretical insights into a method that performs well in practice.

**Abstract**: Despite the progress in the development of generative models, their usefulness in creating synthetic data that improve prediction performance of classifiers has been put into question. Besides heuristic principles such as ''synthetic data should be close to the real data distribution'', it is actually not clear which specific properties affect the generalization error. Our paper addresses this question through the lens of high-dimensional regression. Theoretically, we show that, for linear models, the *covariance shift* between the target distribution and the distribution of the synthetic data affects the generalization error but, surprisingly, the mean shift does not. Furthermore, in some regimes, we prove that matching the covariance of the target distribution is optimal. Remarkably, the theoretical insights for linear models carry over to deep neural networks and generative models. We empirically demonstrate that the *covariance matching* procedure (matching the covariance of the synthetic data with that of the data coming from the target distribution) performs well against several recent approaches for synthetic data selection, across various training paradigms, datasets and generative models used for augmentation.

---

## 163. Task-free Adaptive Meta Black-box Optimization

**OpenReview**: [https://openreview.net/forum?id=AufVSUgMUo](https://openreview.net/forum?id=AufVSUgMUo)

**Authors**: Chao Wang (Xidian University), Licheng Jiao (Xidian University), Lingling Li (Xidian University), Jiaxuan Zhao (Tianjin Research Institute for Water Transport Engineering, M.O.T.), Guanchun Wang (Xi'an University of Electronic Science and Technology), Fang Liu (Xidian University), Shuyuan Yang (Xidian University)

**Institutions**: Xidian University, Tianjin Research Institute for Water Transport Engineering, M.O.T., Xi'an University of Electronic Science and Technology

**Primary Area**: optimization

**Keywords**: Meta Black-box Optimization, Evolutionary Algorithms

**Abstract**: Handcrafted optimizers become prohibitively inefficient for complex black-box optimization (BBO) tasks. MetaBBO addresses this challenge by meta-learning to automatically configure optimizers for low-level BBO tasks, thereby eliminating heuristic dependencies. However, existing methods typically require extensive handcrafted training tasks to learn meta-strategies that generalize to target tasks, which poses a critical limitation for realistic applications with unknown task distributions. To overcome the issue, we propose the Adaptive meta Black-box Optimization Model (ABOM), which performs online parameter adaptation using solely optimization data from the target task, obviating the need for predefined task distributions. Unlike conventional metaBBO frameworks that decouple meta-training and optimization phases, ABOM introduces a closed-loop adaptive parameter learning mechanism, where parameterized evolutionary operators continuously self-update by leveraging generated populations during optimization. This paradigm shift enables zero-shot optimization: ABOM achieves competitive performance on synthetic BBO benchmarks and realistic unmanned aerial vehicle path planning problems without any handcrafted training tasks. Visualization studies reveal that parameterized evolutionary operators exhibit statistically significant search patterns, including natural selection and genetic recombination.

---

## 164. Token-Importance Guided Direct Preference Optimization

**OpenReview**: [https://openreview.net/forum?id=cMEnMVvMw9](https://openreview.net/forum?id=cMEnMVvMw9)

**Authors**: Ning Yang (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Hai Lin, Yibo Liu (The Chinese University of Hong Kong, Shenzhen), Baoliang Tian (ByteDance Inc.), Guoqing Liu (Microsoft Research ), Haijun Zhang (University of Science and Technology Beijing)

**Institutions**: Institute of automation, Chinese academy of science, Chinese Academy of Sciences, The Chinese University of Hong Kong, Shenzhen, ByteDance Inc., Microsoft Research , University of Science and Technology Beijing

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLMs, RLHF, DPO, Human Preference Alignment, Token-lmportance, Triplet Loss

**TL;DR**: We proposes Token-Importance Guided Direct Preference Optimization (TI-DPO) to better align LLMs with human preferences by using a hybrid weighting mechanism to identify key tokens and a triplet loss to guide the optimization process.

**Abstract**: Aligning Large Language Models (LLMs) with human preferences is crucial for safe and effective AI interactions. While popular methods like Direct Preference Optimization (DPO) have simplified alignment, they remain sensitive to data noise and overlook the differential importance of individual tokens. Existing token-level approaches often rely on probability prediction or simplistic weighting schemes to obtain token importance, which still cannot fully address these issues. To solve this problem, we propose the Token-Importance Guided Direct Preference Optimization (TI-DPO), a framework that achieves fine-grained semantic control through two synergistic innovations. 
First, we propose a novel hybrid weighting mechanism that combines gradient attribution with a Gaussian prior, ensuring both the accuracy and robustness of token importance scores. Second, we employ a triplet loss to provide structured guidance for the optimization, explicitly guiding model outputs to approach preferred responses and diverge from non-preferred ones. Experimental results show that TI-DPO achieves higher accuracy and stronger generative diversity, providing more stable and computationally efficient solutions compared with DPO and other RLHF methods.

---

## 165. DTO-KD: Dynamic Trade-off Optimization for Effective Knowledge Distillation

**OpenReview**: [https://openreview.net/forum?id=QMItTyQW92](https://openreview.net/forum?id=QMItTyQW92)

**Authors**: Zeeshan Hayder (Australian National University), Ali Cheraghian (CSIRO), Lars Petersson (CSIRO), Mehrtash Harandi (Monash University), Richard Hartley (Australian National University)

**Institutions**: Australian National University, CSIRO, Monash University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Knowledge Distillation

**TL;DR**: DTO-KD

**Abstract**: Knowledge Distillation (KD) is a widely adopted framework for compressing large models into compact student models by transferring knowledge from a high-capacity teacher. Despite its success, KD presents two persistent challenges: (1) the trade-off between optimizing for the primary task loss and mimicking the teacher's outputs, and (2) the gradient disparity arising from architectural and representational mismatches between teacher and student models. In this work, we propose Dynamic Trade-off Optimization for Knowledge Distillation (DTO-KD), a principled multi-objective optimization formulation of KD that dynamically balances task and distillation losses at the gradient level. Specifically, DTO-KD resolves two critical issues in gradient-based KD optimization: (i) gradient conflict, where task and distillation gradients are directionally misaligned, and (ii) gradient dominance, where one objective suppresses learning progress on the other. Our method adapts per-iteration trade-offs by leveraging gradient projection techniques to ensure balanced and constructive updates. We evaluate DTO-KD on large-scale benchmarks including ImageNet-1K for classification and COCO for object detection. Across both tasks, DTO-KD consistently outperforms prior KD methods, yielding state-of-the-art accuracy and improved convergence behavior. Furthermore, student models trained with DTO-KD exceed the performance of their non-distilled counterparts, demonstrating the efficacy of our multi-objective formulation for KD.

---

## 166. Distributional Equivalence in Linear Non-Gaussian Latent-Variable Cyclic Causal Models: Characterization and Learning

**OpenReview**: [https://openreview.net/forum?id=b8TlYh6PN6](https://openreview.net/forum?id=b8TlYh6PN6)

**Authors**: Haoyue Dai (Carnegie Mellon University), Immanuel Albrecht (FernUniversität in Hagen), Peter Spirtes (Carnegie Mellon University), Kun Zhang (Carnegie Mellon University)

**Institutions**: Carnegie Mellon University, FernUniversität in Hagen

**Primary Area**: causal reasoning

**Keywords**: causal discovery, latent variables, equivalence, rank constraints, linear non-Gaussian models, cycles

**Abstract**: Causal discovery with latent variables is a fundamental task. Yet most existing methods rely on strong structural assumptions, such as enforcing specific indicator patterns for latents or restricting how they can interact with others. We argue that a core obstacle to a general, structural-assumption-free approach is the lack of an equivalence characterization: without knowing what can be identified, one generally cannot design methods for how to identify it. In this work, we aim to close this gap for linear non-Gaussian models. We establish the graphical criterion for when two graphs with arbitrary latent structure and cycles are distributionally equivalent, that is, they induce the same observed distribution set. Key to our approach is a new tool, edge rank constraints, which fills a missing piece in the toolbox for latent-variable causal discovery in even broader settings. We further provide a procedure to traverse the whole equivalence class and develop an algorithm to recover models from data up to such equivalence. To our knowledge, this is the first equivalence characterization with latent variables in any parametric setting without structural assumptions, and hence the first structural-assumption-free discovery method. Code and an interactive demo are available at https://equiv.cc.

---

## 167. Reliable Weak-to-Strong Monitoring of LLM Agents

**OpenReview**: [https://openreview.net/forum?id=WV7xIboTDK](https://openreview.net/forum?id=WV7xIboTDK)

**Authors**: Neil Kale (School of Computer Science, Carnegie Mellon University), Chen Bo Calvin Zhang (Scale AI), Kevin Zhu (Massachusetts Institute of Technology), Ankit Aich, Paula Rodriguez (Scale AI), Christina Q Knight (Scale AI), Zifan Wang (Scale AI)

**Institutions**: School of Computer Science, Carnegie Mellon University, Scale AI, Massachusetts Institute of Technology

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Agent Safety, Chain-of-Thought Monitoring, Large Language Model

**TL;DR**: This paper introduces a monitor red teaming workflow to stress test systems for detecting covert misbehavior in LLM agents, finding that a well-designed monitor scaffold enables weaker models to oversee strong aware attackers.

**Abstract**: We stress test monitoring systems for detecting covert misbehavior in LLM agents (e.g., secretly exfiltrating data). We propose a monitor red teaming (MRT) workflow that varies agent and monitor awareness, adversarial evasion strategies, and evaluation across tool-calling (SHADE-Arena) and computer-use (CUA-SHADE-Arena) environments. We benchmark standard monitor scaffoldings and introduce a hybrid hierarchical--sequential design. Our experiments yield three findings. First, agent awareness dominates monitor awareness: agents that know they are monitored substantially degrade detection, while increasing monitor awareness helps less than expected. Second, monitor scaffolding matters: our hybrid design consistently outperforms baselines and enables weaker monitors to oversee stronger agents (a weak-to-strong effect). Third, targeted human oversight is key: escalating only pre-flagged cases improves TPR by 15% at FPR=0.01. Our work positions MRT as a standard workflow for stress-testing oversight, revealing robustness gaps in both LLM- and human-based monitoring. We release code, data, and logs to support further research.

---

## 168. Multiplayer Nash Preference Optimization

**OpenReview**: [https://openreview.net/forum?id=x7aLhLMVn1](https://openreview.net/forum?id=x7aLhLMVn1)

**Authors**: Fang Wu, Xu Huang (Independent), Weihao Xuan, Zhiwei Zhang (Pennsylvania State University), Yijia Xiao (University of California, Los Angeles), Guancheng Wan, Xiaomin Li (Harvard University, Harvard University), Bing Hu (NA), Peng Xia (Department of Computer Science, University of North Carolina at Chapel Hill), Jure Leskovec (Stanford University), Yejin Choi (Computer Science Department, Stanford University)

**Institutions**: Independent, Pennsylvania State University, University of California, Los Angeles, Harvard University, Harvard University, NA, Department of Computer Science, University of North Carolina at Chapel Hill, Stanford University, Computer Science Department, Stanford University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Preference Optimization, RLHF

**Abstract**: Reinforcement learning from human feedback (RLHF) has emerged as the standard paradigm for aligning large language models (LLMs) with human preferences. However, reward-based methods built on the Bradley–Terry assumption struggle to capture the non-transitive and heterogeneous nature of real-world preferences. To address this, recent studies have reframed alignment as a two-player Nash game, giving rise to Nash learning from human feedback (NLHF). While this perspective has inspired algorithms such as INPO, ONPO, and EGPO with strong theoretical and empirical guarantees, they remain fundamentally restricted to two-player interactions, creating a single-opponent bias that fails to capture the full complexity of realistic preference structures. 
In this work, we introduce Multiplayer Nash Preference Optimization (MNPO), a novel framework that generalizes NLHF to the multiplayer regime. It formulates alignment as an $n$-player game, where each policy competes against a population of opponents while being regularized toward a reference model. 
Our framework establishes well-defined Nash equilibria in multiplayer settings and extends the concept of duality gap to quantify approximation quality. We demonstrate that MNPO inherits the equilibrium guarantees of two-player methods while enabling richer competitive dynamics and improved coverage of diverse preference structures. Through comprehensive empirical evaluation, we show that MNPO consistently outperforms existing NLHF baselines on instruction-following benchmarks, achieving superior alignment quality under heterogeneous annotator conditions and mixed-policy evaluation scenarios. Together, these results establish MNPO as a principled and scalable framework for aligning LLMs with complex, non-transitive human preferences.

---

## 169. Multi-Domain Riemannian Graph Gluing for Building Graph Foundation Models

**OpenReview**: [https://openreview.net/forum?id=G3uNHQpP7J](https://openreview.net/forum?id=G3uNHQpP7J)

**Authors**: Li Sun (Beijing University of Post and Telecommunications), Zhenhao Huang (North China Electric Power University), Silei Chen (NCEPU), Lanxu Yang (NCEPU), Junda Ye (Beijing University of Posts and Telecommunications), Sen Su (Beijing University of Posts and Telecommunications), Philip S. Yu (University of Illinois Chicago)

**Institutions**: Beijing University of Post and Telecommunications, North China Electric Power University, NCEPU, Beijing University of Posts and Telecommunications, University of Illinois Chicago

**Primary Area**: learning on graphs and other geometries & topologies

**Keywords**: Multi-domain graph pre-training, graph neural network, graph foundation model, Riemannian geometry

**TL;DR**: From differential geometry perspective, we present a novel framework that merges multi-domain graphs into a unified, smooth manifold with geometric consistency, enabling quantifiable transferability and geometric scaling behavior.

**Abstract**: Multi-domain graph pre-training integrates knowledge from diverse domains to enhance performance in the target domains, which is crucial for building graph foundation models. Despite initial success, existing solutions often fall short of answering a fundamental question: how is knowledge integrated or transferred across domains? This theoretical limitation motivates us to rethink the consistency and transferability between the pre-trained model and target domains. In this paper, we propose a fresh differential geometry perspective, whose core idea is to merge any graph dataset into a unified, smooth Riemannian manifold, enabling a systematic understanding of knowledge integration and transfer. To achieve this, our key contribution is the theoretical establishment of neural manifold gluing,
which first characterizes local geometry using an adaptive orthogonal frame and then “glues” the local pieces together into a coherent whole. Building on this theory, we present the GraphGlue framework, which supports batched pre-training with EMA prototyping and provides a transferability measure based on geometric consistence. Extensive experiments demonstrate its superior performance across diverse graph domains. Moreover, we empirically validated GraphGlue’s geometric scaling law, showing that larger quantities of datasets improve model transferability by producing a smoother manifold.

---

## 170. TROLL: Trust Regions Improve Reinforcement Learning for Large Language Models

**OpenReview**: [https://openreview.net/forum?id=X9D5MVpPJ9](https://openreview.net/forum?id=X9D5MVpPJ9)

**Authors**: Philipp Becker (Facebook), Niklas Freymuth (Karlsruhe Institute of Technology), Serge Thilges (Karlsruher Institut für Technologie), Fabian Otto (Isomorphic Labs), Gerhard Neumann (FZI Research Center for Information Technology)

**Institutions**: Facebook, Karlsruhe Institute of Technology, Karlsruher Institut für Technologie, Isomorphic Labs, FZI Research Center for Information Technology

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: RL from verifiable rewards, Finetuning LLMs, Trust Regions

**TL;DR**: Replacing PPO's clipping objective with more principled trust regions improves RL from verifiable rewards.

**Abstract**: Reinforcement Learning (RL) with PPO-like clip objectives has become the standard choice for reward-based fine-tuning of large language models (LLMs). 
Although recent work has explored improved estimators of advantages and normalization, the clipping mechanism itself has remained untouched.
Originally introduced as a proxy for principled KL-based trust regions, clipping is a crude approximation that often causes unstable updates and suboptimal performance. 
We replace the clip objective with a novel discrete differentiable trust region projection, which provides principled token-level KL constraints.
The projection operates on a sparse subset of the model’s most important token logits to balance computational cost and projection effectiveness. 
Our approach, Trust Region Optimization for Large Language Models (TROLL), serves as a direct replacement for PPO-like clipping during training and does not alter the model’s inference behavior.
Across mathematical reasoning and code generation tasks, model families, as well as advantage-estimation methods, TROLL consistently outperforms PPO-like clipping in terms of training speed, stability, and final success rates.

---

## 171. FlashVID: Efficient Video Large Language Models via Training-free Tree-based Spatiotemporal Token Merging

**OpenReview**: [https://openreview.net/forum?id=H6rDX4w6Al](https://openreview.net/forum?id=H6rDX4w6Al)

**Authors**: Ziyang Fan (Harbin Institute of Technology(Shenzhen)), Keyu Chen (Harbin Institute of Technology (Shenzhen)), Ruilong Xing (Harbin Institute of Technology), Yulin Li (Harbin Institute of Technology (Shenzhen)), Li Jiang (The Chinese University of Hong Kong, Shenzhen), Zhuotao Tian (Harbin Institute of Technology (Shenzhen))

**Institutions**: Harbin Institute of Technology(Shenzhen), Harbin Institute of Technology (Shenzhen), Harbin Institute of Technology, The Chinese University of Hong Kong, Shenzhen

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Efficient Large Multimodal Models, Video Large Language Models, Visual Token Compression

**TL;DR**: We introduce FlashVID, a training-free and plug-and-play inference acceleration framework for Video LLMs, enabling a satisfactory speedup with negligible performance degradation.

**Abstract**: Although Video Large Language Models (VLLMs) have shown remarkable capabilities in video understanding, they are required to process high volumes of visual tokens, causing significant computational inefficiency. Existing VLLMs acceleration frameworks usually compress spatial and temporal redundancy independently, which overlooks the spatiotemporal relationships, thereby leading to suboptimal spatiotemporal compression. The highly correlated visual features are likely to change in spatial position, scale, orientation, and other attributes over time due to the dynamic nature of video. Building on this insight, we introduce FlashVID, a training-free inference acceleration framework for VLLMs. Specifically, FlashVID utilizes Attention and Diversity-based Token Selection (ADTS) to select the most representative tokens for basic video representation, then applies Tree-based Spatiotemporal Token Merging (TSTM) for fine-grained spatiotemporal redundancy elimination. Extensive experiments conducted on three representative VLLMs across five video understanding benchmarks demonstrate the effectiveness and generalization of our method. Notably, by retaining only $\textbf{10}$% of visual tokens, FlashVID preserves $\textbf{99.1}$% of the performance of LLaVA-OneVision. Consequently, FlashVID can serve as a training-free and plug-and-play module for extending long video frames, which enables a $\textbf{10$\times$}$ increase in video frame input to Qwen2.5-VL, resulting in a relative improvement of $\textbf{8.6}$% within the same computational budget. Code is available at https://github.com/Fanziyang-v/FlashVID.

---

## 172. WSM: Decay-Free Learning Rate Schedule via Checkpoint Merging for LLM Pre-training

**OpenReview**: [https://openreview.net/forum?id=HhThhjKyfw](https://openreview.net/forum?id=HhThhjKyfw)

**Authors**: Changxin Tian (Ant Group), jiapeng wang (Renmin University of China), Qian Zhao (Ant Group), Kunlong Chen (Alibaba Group), Jia Liu (Ant Group), Ziqi Liu (Ant Group), Jiaxin Mao (Renmin University of China), Xin Zhao (Renmin University of China), Zhiqiang Zhang (Ant Group), JUN ZHOU (Ant Group)

**Institutions**: Ant Group, Renmin University of China, Alibaba Group

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: llm pre-training, learning rate schedule, checkpoint merging, decay-free approach

**Abstract**: Recent advances in learning rate~(LR) scheduling have demonstrated the effectiveness of decay-free approaches that eliminate the traditional decay phase while maintaining competitive performance. Model merging techniques have emerged as particularly promising solutions in this domain. We present Warmup-Stable and Merge (WSM), a general framework that establishes a formal connection between learning rate decay and model merging. WSM provides a unified theoretical foundation for emulating various decay strategies—including cosine decay, linear decay and inverse square root decay—as principled model averaging schemes, while remaining fully compatible with diverse optimization methods. Through extensive experiments, we identify merge duration—the training window for checkpoint aggregation—as the most critical factor influencing model performance, surpassing the importance of both checkpoint interval and merge quantity. With the high-quality annealing data, our framework consistently outperforms the widely-adopted Warmup-Stable-Decay (WSD) approach across multiple benchmarks, achieving significant improvements of +3.5\% on MATH, +2.9\% on HumanEval, and +5.5\% on MMLU-Pro. The performance advantages extend to supervised fine-tuning scenarios, highlighting WSM's potential for long-term model refinement.

---

## 173. MrRoPE: Mixed-radix Rotary Position Embedding

**OpenReview**: [https://openreview.net/forum?id=1J63FJYJKg](https://openreview.net/forum?id=1J63FJYJKg)

**Authors**: Qingyuan Tian (Shanghai Jiaotong University), Wenhong Zhu (Shanghai Innovation Institute), Xiaoran Liu (Shanghai Innovation Institute), Xiaofeng Wang (Shanghai Jiaotong University), Rui Wang (Shanghai Jiao Tong University)

**Institutions**: Shanghai Jiaotong University, Shanghai Innovation Institute, Shanghai Jiao Tong University

**Primary Area**: generative models

**Keywords**: transformers, nlp, llms, context window extension, attention, rotary embedding

**TL;DR**: We present a unified theory MrRoPE linking major RoPE-extension methods to radix conversion. Based on this, we propose MrRoPE-Pro, a training-free context window extension method..

**Abstract**: Rotary Position Embedding (RoPE)-extension refers to modifying or generalizing the Rotary Position Embedding scheme to handle longer sequences than those encountered during pre-training. However, current extension strategies are highly diverse and lack a unified theoretical foundation. In this paper, we propose $\textbf{\textit{MrRoPE (Mixed-radix RoPE)}}$, a generalized encoding formulation based on a radix system conversion perspective, which elegantly unifies various RoPE-extension approaches as distinct radix conversion strategies. Based on this theory, we introduce two training-free extensions, $\textbf{\textit{MrRoPE-Uni}}$ and $\textbf{\textit{MrRoPE-Pro}}$, which leverage uniform and progressive radix conversion strategies, respectively, to achieve “train short, test long” generalization. Without fine-tuning, MrRoPE-Pro sustains over 85% recall in the 128K-context Needle-in-a-Haystack test and achieves more than double YaRN’s accuracy on Infinite-Bench retrieval and dialogue subsets. Theoretical analysis confirms that MrRoPE-Pro effectively raises the upper bound of RoPE's attainable encoding length, which further validates the reliability and utility of our theory and methodology.

---

## 174. OpenThoughts: Data Recipes for Reasoning Models

**OpenReview**: [https://openreview.net/forum?id=7xjoTuaNmN](https://openreview.net/forum?id=7xjoTuaNmN)

**Authors**: Etash Kumar Guha (RIKEN), Ryan Marten (University of Illinois Urbana-Champaign), Sedrick Keh (Toyota Research Institute), Negin Raoof (University of California, Berkeley), Georgios Smyrnis (University of Texas, Austin), Hritik Bansal (University of California, Los Angeles), Marianna Nezhurina (Forschungszentrum Juelich GmbH), Jean Mercat (Toyota Research Institute), Trung Vu (Google), Zayne Rea Sprague (New York University), Ashima Suvarna (University of California, Los Angeles), Benjamin Feuer (Computer Science Department, Stanford University), Leon Liangyu Chen (Computer Science Department, Stanford University), Zaid Khan (University of North Carolina at Chapel Hill), Eric Frankel (Department of Computer Science, University of Washington), Sachin Grover (Arizona State University), Caroline Choi (Computer Science Department, Stanford University), Niklas Muennighoff (Stanford University), Shiye Su (Stanford University), Wanjia Zhao (Stanford University), John Yang (Stanford University), Shreyas Pimpalgaonkar (New York University), Kartik sharma (Georgia Institute of Technology), Charlie Cheng-Jie Ji (University of California, Berkeley), Yichuan Deng (Department of Computer Science, University of Washington), Sarah M Pratt (University of Washington), Vivek Ramanujan (Department of Computer Science, University of Washington), Jon Saad-Falcon (Computer Science Department, Stanford University), Stutee Acharya (University of South Florida), Jeffrey Li (Department of Computer Science, University of Washington), Achal Dave (Anthropic), Alon Albalak (Lila Sciences), Kushal Arora (McGill University), Blake Wulfe, Chinmay Hegde (New York University), Greg Durrett (New York University), Sewoong Oh (University of Washington), Mohit Bansal (University of North Carolina at Chapel Hill), Saadia Gabriel (University of California, Los Angeles), Aditya Grover (University of California, Los Angeles), Kai-Wei Chang (University of California, Los Angeles), Vaishaal Shankar (Apple), Aaron Gokaslan (Cornell University), Mike A Merrill (Stanford University), Tatsunori Hashimoto (Stanford University), Yejin Choi (Computer Science Department, Stanford University), Jenia Jitsev (LAION), Reinhard Heckel (Technische Universität München), Maheswaran Sathiamoorthy (University of Southern California), Alex Dimakis (Electrical Engineering & Computer Science Department, University of California, Berkeley), Ludwig Schmidt (Stanford University)

**Institutions**: RIKEN, University of Illinois Urbana-Champaign, Toyota Research Institute, University of California, Berkeley, University of Texas, Austin, University of California, Los Angeles, Forschungszentrum Juelich GmbH, Google, New York University, Computer Science Department, Stanford University, University of North Carolina at Chapel Hill, Department of Computer Science, University of Washington, Arizona State University, Stanford University, Georgia Institute of Technology, University of Washington, University of South Florida, Anthropic, Lila Sciences, McGill University, Apple, Cornell University, LAION, Technische Universität München, University of Southern California, Electrical Engineering & Computer Science Department, University of California, Berkeley

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Reasoning, Data, LLM

**TL;DR**: Data pipeline analysis for training reasoning models

**Abstract**: Reasoning models have made rapid progress on many benchmarks involving math,
code, and science. Yet, there are still many open questions about the best train-
ing recipes for reasoning since state-of-the-art models often rely on proprietary
datasets with little to no public information available. To address this, the goal of
the OpenThoughts project is to create open-source datasets for training reasoning
models. Our OpenThoughts2-1M dataset led to OpenThinker2-32B, the first model
trained on public reasoning data to match DeepSeek-R1-Distill-32B on standard
reasoning benchmarks such as AIME and LiveCodeBench. We then improve
our dataset further by systematically investigating each step of our data genera-
tion pipeline with 1,000+ controlled experiments, which led to OpenThoughts3.
Scaling the pipeline to 1.2M examples and using QwQ-32B as teacher yields
our OpenThinker3-7B model, which achieves state-of-the-art results: 53% on
AIME 2025, 51% on LiveCodeBench 06/24-01/25, and 54% on GPQA Dia-
mond – improvements of 15.3, 17.2, and 20.5 percentage points compared to the
DeepSeek-R1-Distill-Qwen-7B. All of our datasets and models are available on
ANONYMIZED.

---

## 175. Text-to-3D by Stitching a Multi-view Reconstruction Network to a Video Generator

**OpenReview**: [https://openreview.net/forum?id=kI27Niy4xY](https://openreview.net/forum?id=kI27Niy4xY)

**Authors**: Hyojun Go (ETHZ - ETH Zurich), Dominik Narnhofer (ETHZ - ETH Zurich), Goutam Bhat (Google), Prune Truong (Google), Federico Tombari (Google), Konrad Schindler (Swiss Federal Institute of Technology)

**Institutions**: ETHZ - ETH Zurich, Google, Swiss Federal Institute of Technology

**Primary Area**: generative models

**Keywords**: Text-to-3D generation, Video Diffusion Model, 3D Gaussian Splatting, Generation

**TL;DR**: Text-to-3D scene generative modelling by unifying a video generative model with a foundational 3D model via model stitching and alignment.

**Abstract**: The rapid progress of large, pretrained models for both visual content generation and 3D reconstruction opens up new possibilities for text-to-3D generation. Intuitively, one could obtain a formidable 3D scene generator if one were able to combine the power of a modern latent text-to-video model as "generator" with the geometric abilities of a recent (feedforward) 3D reconstruction system as "decoder". We introduce **VIST3A**, a general framework that does just that, addressing two main challenges. First, the two components must be joined in a way that preserves the rich knowledge encoded in their weights. We revisit *model stitching*, i.e., we identify the layer in the 3D decoder that best matches the latent representation produced by the text-to-video generator and stitch the two parts together. That operation requires only a small dataset and no labels. Second, the text-to-video generator must be aligned with the stitched 3D decoder, to ensure that the generated latents are decodable into consistent, perceptually convincing 3D scene geometry. To that end, we adapt *direct reward finetuning*, a popular technique for human preference alignment. We evaluate the proposed VIST3A approach with different video generators and 3D reconstruction models. All tested pairings markedly improve over prior text-to-3D models that output Gaussian splats. Moreover, by choosing a suitable 3D base model, VIST3A also enables high-quality text-to-pointmap generation.

---

## 176. A Scalable Distributed Framework for Multimodal GigaVoxel Image Registration

**OpenReview**: [https://openreview.net/forum?id=8dLexnao2h](https://openreview.net/forum?id=8dLexnao2h)

**Authors**: Rohit Jena (University of Pennsylvania), Vedant Zope (University of Pennsylvania), Pratik Chaudhari (School of Engineering and Applied Science, University of Pennsylvania), James Gee (University of Pennsylvania)

**Institutions**: University of Pennsylvania, School of Engineering and Applied Science, University of Pennsylvania

**Primary Area**: infrastructure, software libraries, hardware, systems, etc.

**Keywords**: image registration, distributed optimization, CUDA kernels, neuroanatomy

**TL;DR**: we propose non-GEMM CUDA kernels and distributed primitives to scale multimodal image registration to arbitrary image sizes

**Abstract**: In this work, we propose FFDP, a set of IO-aware non-GEMM fused kernels supplemented with a distributed framework for image registration at unprecedented scales. Image registration is an inverse problem fundamental to biomedical and life sciences, but algorithms have not scaled in tandem with image acquisition capabilities. Our framework complements existing model parallelism techniques proposed for large-scale transformer training by optimizing non-GEMM bottlenecks and enabling convolution-aware tensor sharding. We demonstrate unprecedented capabilities by performing multimodal registration of a 100μm ex-vivo human brain MRI volume at native resolution – an inverse problem more than 570× larger than a standard clinical datum in about a minute using only 8 A6000 GPUs. FFDP accelerates existing state-of-the-art optimization and deep learning registration pipelines by upto 6 − 7× while reducing peak memory consumption by 20 − 59%. Comparative analysis on a 250μm dataset shows that FFDP can fit upto 64× larger problems than existing SOTA on a single GPU, and highlights both the performance and efficiency gains of FFDP compared to SOTA image registration methods.

---

## 177. Invisible Safety Threat: Malicious Finetuning for LLM via Steganography

**OpenReview**: [https://openreview.net/forum?id=6cEPDGaShH](https://openreview.net/forum?id=6cEPDGaShH)

**Authors**: Guangnian Wan (National University of Singapore), Xinyin Ma (NVIDIA), Gongfan Fang (National University of Singapore), Xinchao Wang (National University of Singapore)

**Institutions**: National University of Singapore, NVIDIA

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: LLM, finetuning, safety, steganography

**TL;DR**: We highlight an insidious safety threat: a compromised LLM can maintain a facade of proper safety alignment while covertly generating harmful content through steganography.

**Abstract**: Understanding and addressing potential safety alignment risks in large language models (LLMs) is critical for ensuring their safe and trustworthy deployment. In this paper, we highlight an insidious safety threat: a compromised LLM can maintain a facade of proper safety alignment while covertly generating harmful content. To achieve this, we finetune the model to understand and apply a steganographic technique. At inference time, we input a prompt that contains a steganographically embedded malicious target question along with a plaintext cover question. The model, in turn, produces a target response similarly embedded within a benign-looking cover response. In this process, human observers only see the model being prompted with a cover question and generating a corresponding cover response, while the malicious content is hidden from view. We demonstrate this invisible safety threat on GPT-4.1 despite the OpenAI fine-tuning API’s safeguards. The finetuned model produces steganographic malicious outputs in response to hidden malicious prompts, while the user interface displays only a fully benign cover interaction. We also replicate the attack on two open-source models, Phi-4 and Mistral-Small-24B-Base-2501, confirming the generality of our method. We quantitatively evaluate our method on the AdvBench dataset, using Llama-Guard-3-8B for content safety classification. Across all three models, all stegotexts containing malicious content are incorrectly classified as safe.

---

## 178. Temporal superposition and feature geometry of RNNs under memory demands

**OpenReview**: [https://openreview.net/forum?id=7cMzTpbJHC](https://openreview.net/forum?id=7cMzTpbJHC)

**Authors**: Pratyaksh Sharma (Imperial College London), Alexandra Maria Proca (Imperial College London), Lucas Prieto (Imperial College London), Pedro A. M. Mediano (Imperial College London)

**Institutions**: Imperial College London

**Primary Area**: interpretability and explainable AI

**Keywords**: RNNs, superposition, representational geometry, features, capacity, memory demands

**TL;DR**: We study the feature geometry of RNNs under memory demands and characterize their representational strategies using a novel framework of temporal superposition.

**Abstract**: Understanding how populations of neurons represent information is a central challenge across machine learning and neuroscience. Recent work in both fields has begun to characterize the representational geometry and functionality underlying complex distributed activity. For example, artificial neural networks trained on data with more features than neurons compress data by representing features non-orthogonally in so-called *superposition*. However, the effect of time (or memory), an additional capacity-constraining pressure, on underlying representational geometry in recurrent models is not well understood. Here, we study how memory demands affect representational geometry in recurrent neural networks (RNNs), introducing the concept of temporal superposition. We develop a theoretical framework in RNNs with linear recurrence trained on a delayed serial recall task to better understand how properties of the data, task demands, and network dimensionality lead to different representational strategies, and show that these insights generalize to nonlinear RNNs. Through this, we identify an effectively linear, dense regime and a sparse regime where RNNs utilize an interference-free space, characterized by a phase transition in the angular distribution of features and decrease in spectral radius. Finally, we analyze the interaction of spatial and temporal superposition to observe how RNNs mediate different representational tradeoffs. Overall, our work offers a mechanistic, geometric explanation of representational strategies RNNs learn, how they depend on capacity and task demands, and why.

---

## 179. InfoTok: Adaptive Discrete Video Tokenizer via Information-Theoretic Compression

**OpenReview**: [https://openreview.net/forum?id=JEYWpFGzvn](https://openreview.net/forum?id=JEYWpFGzvn)

**Authors**: Haotian Ye (Stanford University), Qiyuan He (NVIDIA), Jiaqi Han (Computer Science Department, Stanford University), Puheng Li (Stanford University), Jiaojiao Fan (NVIDIA), Zekun Hao (NVIDIA), Fitsum Reda (NVIDIA), Yogesh Balaji (NVIDIA), Huayu Chen (Tsinghua University), Sheng Liu (Stanford University), Angela Yao (National University of Singapore), James Zou (Stanford University), Stefano Ermon (Stanford University), Haoxiang Wang (NVIDIA), Ming-Yu Liu (NVIDIA)

**Institutions**: Stanford University, NVIDIA, Computer Science Department, Stanford University, Tsinghua University, National University of Singapore

**Primary Area**: learning theory

**Keywords**: discrete tokenization, video representation, eficiency, information theory

**TL;DR**: This paper introduces InfoTok, an adaptive video tokenizer guided by information theory, which significantly boosts video compression efficiency and reduces computational overhead without degrading visual quality.

**Abstract**: Accurate and efficient discrete video tokenization is essential for long video sequences processing. Yet, the inherent complexity and variable information density of videos present a significant bottleneck for current tokenizers, which rigidly compress all content at a fixed rate, leading to redundancy or information loss. Drawing inspiration from Shannon's information theory, this paper introduces \alg, a principled framework for adaptive video tokenization. We rigorously prove that existing data-agnostic training methods are suboptimal in representation length, and present a novel evidence lower bound (ELBO)-based algorithm that approaches theoretical optimality. Leveraging this framework, we develop a transformer-based adaptive compressor that enables adaptive tokenization. Empirical results demonstrate state-of-the-art compression performance, saving $20\%$ tokens without influence on performance, and achieving $2.3\times$ compression rates while still outperforming prior heuristic adaptive approaches. By allocating tokens according to informational richness, \alg enables a more compressed yet accurate tokenization for video representation, offering valuable insights for future research.

---

## 180. Actions Speak Louder than Prompts: A Large-Scale Study of LLMs for Graph Inference

**OpenReview**: [https://openreview.net/forum?id=MgJUj9Sk3C](https://openreview.net/forum?id=MgJUj9Sk3C)

**Authors**: Ben Finkelshtein (University of Oxford), Silviu Cucerzan (Microsoft), Sujay Kumar Jauhar (Microsoft Research), Ryen W White (Microsoft)

**Institutions**: University of Oxford, Microsoft, Microsoft Research

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Large Language Models, Prompting, In-Context Learning, Tool-augmented Reasoning, Text-rich Graphs

**TL;DR**: A comprehensive study of LLMs for node classification, providing a principled understanding of their capabilities in processing graph information that practitioners can apply in real-world tasks

**Abstract**: Large language models (LLMs) are increasingly leveraged for text-rich graph machine learning tasks, with node classification standing out due to its high-impact application domains such as fraud detection and recommendation systems. 
Yet, despite a surge of interest, the field lacks a principled understanding of the capabilities of LLMs in processing graph data.
In this work, we conduct a large-scale, controlled evaluation across the key axes of variability: the LLM-graph interaction mode, comparing prompting, tool-use, and code generation; dataset domains, spanning citation, web-link, e-commerce, and social networks; homophilic vs. heterophilic regimes; short- vs. long-text features; LLM sizes and reasoning capabilities. We further analyze dependencies by independently truncating features, deleting edges, and removing labels to quantify reliance on input types.
Our findings provide actionable guidance for both research and practice. (1) Code generation mode achieves the strongest overall performance, with especially large gains on long-text or high-degree graphs where prompting quickly exceeds the token budget. (2) All interaction strategies remain effective on heterophilic graphs, challenging the assumption that LLM-based methods collapse under low homophily. (3) Code generation mode is able to flexibly shift its reliance to the most informative input type, whether that be structure, features, or labels.
Together, these results establish a clear picture of the strengths and limitations of current LLM–graph interaction modes and point to design principles for future methods.

---

## 181. Through the Lens of Contrast: Self-Improving Visual Reasoning in VLMs

**OpenReview**: [https://openreview.net/forum?id=ZymCPON45y](https://openreview.net/forum?id=ZymCPON45y)

**Authors**: Zhiyu Pan (Alibaba Group), Yizheng Wu (Alibaba Group), Jiashen Hua (Alibaba Group), Junyi Feng, Shaotian Yan (Alibaba Group), Bing Deng (Alibaba Group), Zhiguo Cao (Huazhong University of Science and Technology), Jieping Ye (Alibaba Group)

**Institutions**: Alibaba Group, Huazhong University of Science and Technology

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Reasoning, Vision-Language Models, Contrasting

**Abstract**: Reasoning has emerged as a key capability of large language models. In linguistic tasks, this capability can be enhanced by self-improving techniques that refine reasoning paths for subsequent fine-tuning. However, extending these language-based self-improving approaches to vision language models (VLMs) presents a unique challenge: visual hallucinations in reasoning paths cannot be effectively verified or rectified. Our solution starts with a key observation about visual contrast: when presented with a contrastive VQA pair, i.e., two visually similar images with synonymous questions, VLMs identify relevant visual cues more precisely compared with when given a single VQA sample. Motivated by this observation, we propose Visual Contrastive Self-Taught Reasoner (VC-STaR), a novel self-improving framework that leverages visual contrast to mitigate hallucinations in model-generated rationales. We collect a diverse suite of VQA datasets, curate contrastive pairs according to multi-modal similarity, and generate rationales using VC-STaR. Consequently, we obtain a new visual reasoning dataset, VisCoR-$55$K, which is then used to boost the reasoning capability of various VLMs through supervised finetuning. Extensive experiments show that VC-STaR not only outperforms existing self-improving approaches but also surpasses models finetuned on the SoTA visual reasoning datasets, demonstrating that the inherent contrastive ability of VLMs can bootstrap their own visual reasoning. The code, dataset and trained models will be released upon acceptance.

---

## 182. SAFETY-GUIDED FLOW (SGF): A UNIFIED FRAMEWORK FOR NEGATIVE GUIDANCE IN SAFE GENERATION

**OpenReview**: [https://openreview.net/forum?id=EA80Zib9UI](https://openreview.net/forum?id=EA80Zib9UI)

**Authors**: Mingyu Kim (Kookmin University), Young-Heon Kim (University of British Columbia), Mijung Park (University of British Columbia)

**Institutions**: Kookmin University, University of British Columbia

**Primary Area**: generative models

**Keywords**: Safe generation, flow matching, control barrier functions

**TL;DR**: We introduced a unified probabilistic framework for safe generation in diffusion and flow models, using Maximum Mean Discrepancy-based energy potentials.

**Abstract**: Safety mechanisms for diffusion and flow models have recently been developed along two distinct paths. 
In robot planning, control barrier functions are employed to guide generative trajectories away from obstacles at every denoising step by explicitly imposing geometric constraints. 
In parallel, recent data-driven, negative guidance approaches have been shown to suppress harmful content and promote diversity in generated samples. However, they rely on heuristics without clearly stating when safety guidance is actually necessary. 
In this paper, we first introduce a unified probabilistic framework using a Maximum Mean Discrepancy (MMD) potential for image generation tasks that recasts both Shielded Diffusion and Safe Denoiser as instances of our energy-based negative guidance against unsafe data samples. 
Furthermore, we leverage control-barrier functions analysis to justify the existence of a critical time window in which negative guidance must be strong; outside of this window, the guidance should decay to zero to ensure safe and high-quality generation. We evaluate our unified framework on several realistic safe generation scenarios, confirming that negative guidance should be applied in the early stages of the denoising process for successful safe generation.

---

## 183. Depth Anything 3: Recovering the Visual Space from Any Views

**OpenReview**: [https://openreview.net/forum?id=yirunib8l8](https://openreview.net/forum?id=yirunib8l8)

**Authors**: Haotong Lin (Zhejiang University), Sili Chen, Jun Hao Liew (SalesForce), Donny Y. Chen (ByteDance Seed (Singapore)), Zhenyu Li (King Abdullah University of Science and Technology), Yang Zhao (ByteDance Inc.), Sida Peng (Zhejiang University), Hengkai Guo (Bytedance Intelligent Creation), Xiaowei Zhou (Zhejiang University), Guang Shi (ByteDance Inc.), Jiashi Feng (ByteDance), Bingyi Kang (Bytedance)

**Institutions**: Zhejiang University, SalesForce, ByteDance Seed (Singapore), King Abdullah University of Science and Technology, ByteDance Inc., Bytedance Intelligent Creation, ByteDance, Bytedance

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Depth Estimation

**TL;DR**: Depth Anything 3 uses a single vanilla DINOv2 transformer to take arbitrary input views and outputs consistent depth and ray maps, delivering leading pose, geometry, and visual rendering performance.

**Abstract**: We present Depth Anything 3 (DA3), a model that predicts spatially consistent geometry from an arbitrary number of visual inputs, with or without known camera poses. 
In pursuit of minimal modeling, DA3 yields two key insights:
a single plain transformer (e.g., vanilla DINOv2 encoder) is sufficient as a backbone without architectural specialization, and a singular depth-ray prediction target obviates the need for complex multi-task learning. Through our teacher-student training paradigm, the model achieves a level of detail and generalization on par with Depth Anything 2 (DA2).
We establish a new visual geometry benchmark covering camera pose estimation, any-view geometry and visual rendering. On this benchmark, DA3 sets a new state-of-the-art across all tasks, surpassing prior SOTA VGGT by an average of 35.7\% in camera pose accuracy and 23.6\% in geometric accuracy. Moreover, it outperforms DA2 in monocular depth estimation. All models are trained exclusively on public academic datasets.

---

## 184. Taming Momentum: Rethinking Optimizer States Through Low-Rank Approximation

**OpenReview**: [https://openreview.net/forum?id=9Q0dNBYeEY](https://openreview.net/forum?id=9Q0dNBYeEY)

**Authors**: Zhengbo Wang (University of Science and Technology of China), Jian Liang (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Ran He (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Zilei Wang (University of Science and Technology of China), Tieniu Tan

**Institutions**: University of Science and Technology of China, Institute of automation, Chinese academy of science, Chinese Academy of Sciences

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Large Language Models; Efficient Training; Low-Rank; LoRA

**Abstract**: Modern optimizers like Adam and Muon are central to training large language models, but their reliance on first- and second-order momenta introduces significant memory overhead, which constrains scalability and computational efficiency. 
In this work, we reframe the exponential moving average (EMA) used in these momenta as the training of a linear regressor via online gradient flow. 
Building on this equivalence, we introduce LoRA-Pre, a novel low-rank optimizer designed for efficient pre-training. 
Specifically, LoRA-Pre reduces the optimizer's memory footprint by decomposing the full momentum matrix into a compact low-rank subspace within the online linear learner, thereby maintaining optimization performance while improving memory efficiency. 
We empirically validate LoRA-Pre's efficacy by pre-training models from the Llama architecture family, scaling from 60M to 1B parameters. 
LoRA-Pre achieves the highest performance across all model sizes.
Notably, LoRA-Pre demonstrates remarkable rank efficiency, achieving comparable or superior results using only 1/8 the rank of baseline methods. 
Beyond pre-training, we evaluate LoRA-Pre's effectiveness in fine-tuning scenarios. 
With the same rank, LoRA-Pre consistently outperforms all efficient fine-tuning baselines.
Specifically, compared to standard LoRA, LoRA-Pre achieves substantial improvements of 3.14 points on Llama-3.1-8B and 6.17 points on Llama-2-7B, validating our approach's effectiveness across both pre-training and fine-tuning paradigms.
Our code is publicly available at https://github.com/mrflogs/LoRA-Pre.

---

## 185. Premise Selection for a Lean Hammer

**OpenReview**: [https://openreview.net/forum?id=m04JJNeRK6](https://openreview.net/forum?id=m04JJNeRK6)

**Authors**: Thomas Zhu (ByteDance Inc.), Joshua Clune (Carnegie Mellon University), Jeremy Avigad (Carnegie Mellon University), Albert Q. Jiang (Mistral AI), Sean Welleck

**Institutions**: ByteDance Inc., Carnegie Mellon University, Mistral AI

**Primary Area**: neurosymbolic & hybrid AI systems (physics-informed, logic & formal reasoning, etc.)

**Keywords**: premise selection, interactive theorem proving, automated reasoning, contrastive learning

**TL;DR**: LeanHammer integrates neural premise selection with symbolic reasoning to automate theorem proving in Lean.

**Abstract**: Neural methods are transforming automated reasoning for proof assistants, yet integrating these advances into practical verification workflows remains challenging. A $\textit{hammer}$ is a tool that integrates premise selection, translation to external automatic theorem provers, and proof reconstruction into one overarching tool to automate tedious reasoning steps. We present LeanPremise, a novel neural premise selection system, and we combine it with existing translation and proof reconstruction components to create LeanHammer, the first end-to-end domain general hammer for the Lean proof assistant. Unlike existing Lean premise selectors, LeanPremise is specifically trained for use with a hammer in dependent type theory. It also dynamically adapts to user-specific contexts, enabling it to effectively recommend premises from libraries outside LeanPremise's training data as well as lemmas defined by the user locally. With comprehensive evaluations, we show that LeanPremise enables LeanHammer to solve 21\% more goals than existing premise selectors and generalizes well to diverse domains. Our work helps bridge the gap between neural retrieval and symbolic reasoning, making formal verification more accessible to researchers and practitioners.

---

## 186. DepthLM: Metric Depth from Vision Language Models

**OpenReview**: [https://openreview.net/forum?id=ObFVZGnSFN](https://openreview.net/forum?id=ObFVZGnSFN)

**Authors**: Zhipeng Cai (Meta), Ching-Feng Yeh (Facebook), Hu Xu (FAIR, AMI Foundation), Zhuang Liu (Princeton University), Gregory P. Meyer (Facebook), Xinjie Lei (Facebook), Changsheng Zhao (Meta Inc.), Shang-Wen Li (Facebook), Vikas Chandra (Meta), Yangyang Shi (Meta)

**Institutions**: Meta, Facebook, FAIR, AMI Foundation, Princeton University, Meta Inc.

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Metric depth, Vision language model, Spatial reasoning

**TL;DR**: The first proof that VLMs can have expert model level depth estimation accuracy without architecture or loss change

**Abstract**: Vision language models (VLMs) can flexibly address various vision tasks through text interactions. Although successful in semantic understanding, state-of-the-art VLMs including GPT-5 still struggle in understanding 3D from 2D inputs. On the other hand, expert pure vision models achieve super-human accuracy in metric depth estimation, a key 3D understanding task. However, they require task-specific architectures and losses. Such difference motivates us to ask: Can VLMs reach expert-level accuracy without architecture or loss change? We take per-pixel metric depth estimation as the representative task and show that the answer is yes! Surprisingly, comprehensive analysis shows that text-based supervised-finetuning with sparse labels is sufficient for VLMs to unlock strong 3D understanding, no dense prediction head or complex regression/regularization loss is needed. The bottleneck lies in pixel reference and cross-dataset camera ambiguity, which we address through visual prompting and intrinsic-conditioned augmentation. With much smaller models, our method DepthLM surpasses the accuracy of most advanced VLMs by over 2x, making VLMs for the first time comparable with pure vision models. The simplicity of DepthLM also enables a single VLM to cover various 3D tasks beyond metric depth. Code and model are available at https://github.com/facebookresearch/DepthLM_Official.

---

## 187. Hallucination Begins Where Saliency Drops

**OpenReview**: [https://openreview.net/forum?id=sjnErRHXf3](https://openreview.net/forum?id=sjnErRHXf3)

**Authors**: Xiaofeng Zhang (Shanghai Jiao Tong University), Yuanchao Zhu (Dalian Martime University), Chaochen Gu (Shanghai Jiaotong University), Xiaosong Yuan (Alibaba Group), Qiyan Zhao (Institute of automation, Chinese academy of science), Jiawei Cao (Shanghai Jiaotong University), Feilong Tang (Monash University), Sinan Fan (Zhejiang University), Yaomin Shen (Nanchang Research Institute, Zhejiang University), Chen Shen (Alibaba Group), Hao Tang (Peking University)

**Institutions**: Shanghai Jiao Tong University, Dalian Martime University, Shanghai Jiaotong University, Alibaba Group, Institute of automation, Chinese academy of science, Monash University, Zhejiang University, Nanchang Research Institute, Zhejiang University, Peking University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LVLMs-Saliency; Saliency-Guided Rejection Sampling;  Local Coherence Reinforcement; Hallucination

**Abstract**: Recent studies have investigated attention dynamics in large vision language models (LVLMs), yet existing methods remain limited in reliably distinguishing hallucinated from correct outputs — primarily because they rely solely on forward-pass attention, ignoring gradient-based signals that reveal how token influence propagates through the model. To bridge this gap, we introduce \textbf{LVLMs-Saliency}, an \textit{gradient-aware diagnostic tool} that quantifies the grounding strength of each output token by fusing attention weights with their gradients. Through analysis, we identify a decisive pattern: \textit{Hallucinations occur when prior output tokens shows low saliency to the next token prediction}, indicating a failure of contextual memory. Building on this insight, we propose a dual-mechanism inference-time framework: (1) Saliency-Guided Rejection Sampling (SGRS), which dynamically filters candidate tokens during decoding by rejecting those with saliency below a context-adaptive threshold, thereby preventing coherence-breaking tokens from entering the sequence; and (2) Local Coherence Reinforcement (LocoRE), a lightweight plug-and-play module that strengthens attention from the current token to its most recent outputs, actively counteracting the “forgetting” behavior identified by LVLMs-Saliency. Experimental results demonstrate that our method significantly reduces hallucinations across multiple LVLMs, offering a robust and interpretable solution to improve model reliability.

---

## 188. Overthinking Reduction with Decoupled Rewards and Curriculum Data Scheduling

**OpenReview**: [https://openreview.net/forum?id=kdeiRledV6](https://openreview.net/forum?id=kdeiRledV6)

**Authors**: Shuyang Jiang (Fudan University), Yusheng Liao (Shanghai Jiaotong University), Ya Zhang (Shanghai Jiao Tong University), Yanfeng Wang (Shanghai Jiao Tong University), Yu Wang (Shanghai Jiao Tong University)

**Institutions**: Fudan University, Shanghai Jiaotong University, Shanghai Jiao Tong University

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: efficient reasoning; curriculum sampling with decoupled reward

**TL;DR**: theoretical unveil the underlying limitations of length reward and propose D$^2$yOR to achieve supreme efficiency without performance degradation

**Abstract**: While large reasoning models trained with critic-free reinforcement learning and verifiable rewards (RLVR) represent the state-of-the-art, their practical utility is hampered by ``overthinking'', a critical issue where models generate excessively long reasoning paths without any performance benefit. Existing solutions that penalize length often fail, inducing performance degradation due to a fundamental misalignment between trajectory-level rewards and token-level optimization. In this work, we introduce a novel framework, DECS, built on our theoretical discovery of two previously unaddressed flaws in current length rewards: (1) the erroneous penalization of essential exploratory tokens and (2) the inadvertent rewarding of partial redundancy. Our framework's innovations include (i) a first-of-its-kind decoupled token-level reward mechanism that surgically distinguishes and penalizes redundant tokens, and (ii) a novel curriculum batch scheduling strategy to master the efficiency-efficacy equilibrium. Experimental results show DECS can achieve a dramatic reduction in reasoning tokens by over 50\% across seven benchmarks while simultaneously maintaining or even improving performance. It demonstrates conclusively that substantial gains in reasoning efficiency can be achieved without compromising a model's underlying reasoning power. Code is available at \url{https://github.com/pixas/DECS}.

---

## 189. On the Generalization Capacities of MLLMs for Spatial Intelligence

**OpenReview**: [https://openreview.net/forum?id=DE5ZJtR4bg](https://openreview.net/forum?id=DE5ZJtR4bg)

**Authors**: Gongjie Zhang (Alibaba Group), Wenhao Li (Nanyang Technological University), Quanhao Qian (DAMO Academy, Alibaba Group), Jiuniu Wang (Alibaba Group), Deli Zhao (Alibaba Group), Shijian Lu (Nanyang Technological University), Ran Xu (Alibaba Group)

**Institutions**: Alibaba Group, Nanyang Technological University, DAMO Academy, Alibaba Group

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: 3D Computer Vision, Multimodal Large Language Model, Spatial Intelligence, Embodied AI

**TL;DR**: We show that RGB-only MLLMs are fundamentally flawed for spatial reasoning due to an inherent geometric ambiguity, and propose a camera-aware MLLM framework that incorporates camera intrinsics for robust, generalizable spatial intelligence.

**Abstract**: Multimodal Large Language Models (MLLMs) that directly process RGB inputs for tasks like 3D localization and navigation have shown remarkable potential. However, we argue that these ``RGB-only'' approaches are fundamentally flawed in their ability to generalize across cameras. By ignoring camera parameters, they entangle an object's physical properties with the camera's perspective, creating an irresolvable ambiguity. We show this leads MLLMs to overfit to the training camera distribution, rather than learning true and generalizable 3D geometric principles. To address this, we propose Camera-Aware MLLM framework for spatial MLLMs. It learns generalizable spatial reasoning by: (i) injecting camera intrinsics via a dense embedding that conditions each visual token; (ii) introducing a camera-aware data augmentation strategy that synthetically varies camera parameters, forcing the model to disentangle camera properties from scene content; and (iii) distilling geometric priors from a 3D vision foundation model. Extensive experiments demonstrate that camera-aware MLLMs substantially outperform their naive counterparts, particularly in cross-camera generalization tests on spatially-grounded tasks, indicating that camera-awareness is not only beneficial but also a prerequisite for robust and generalizable spatial intelligence in MLLMs.

---

## 190. The Polar Express: Optimal Matrix Sign Methods and their Application to the Muon Algorithm

**OpenReview**: [https://openreview.net/forum?id=yRtgZ1K8hO](https://openreview.net/forum?id=yRtgZ1K8hO)

**Authors**: Noah Amsel (NYU, New York University), David Persson (New York University), Christopher Musco (Brown University), Robert M. Gower (Flatiron Institute)

**Institutions**: NYU, New York University, New York University, Brown University, Flatiron Institute

**Primary Area**: optimization

**Keywords**: polar decomposition, matrix sign, numerical linear algebra, muon, optimization, approximation theory

**TL;DR**: We introduce a GPU-friendly algorithm for computing the polar decomposition of a matrix to low accuracy that is optimal in its class. This improves Muon.

**Abstract**: Computing the polar decomposition and the related matrix sign function has been a well-studied problem in numerical analysis for decades. Recently, it has emerged as an important subroutine  within the Muon algorithm for training deep neural networks.
However, the requirements of this application differ sharply from classical settings: deep learning demands GPU-friendly algorithms that prioritize high throughput over high precision. We introduce *Polar Express*, a new method for computing the polar decomposition. Like Newton–Schulz and other classical polynomial methods, our approach uses only matrix-matrix multiplications, making it 
very efficient on GPUs.
Inspired by earlier work of Chen \& Chow and Nakatsukasa \& Freund, *Polar Express* adapts the update rule at each iteration by solving a minimax optimization problem.
We prove that this strategy minimizes error in a worst-case sense, allowing *Polar Express* to converge as rapidly as possible both in the early iterations and asymptotically.
We also address finite-precision issues, making it practical to use in `bfloat16`. When integrated into Muon, our method yields consistent improvements in validation loss for a GPT-2 model on one to ten billion tokens from the FineWeb dataset, outperforming recent alternatives across a range of learning rates.

---

## 191. Characterizing the Discrete Geometry of ReLU Networks

**OpenReview**: [https://openreview.net/forum?id=TgLW2DiRDG](https://openreview.net/forum?id=TgLW2DiRDG)

**Authors**: Blake B. Gaines (University of Connecticut), Jinbo Bi (University of Connecticut)

**Institutions**: University of Connecticut

**Primary Area**: learning theory

**Keywords**: Polyhedrons, Geometry, ReLU, Activations

**TL;DR**: We describe the geometry of the polyhedral complexes defined by the linear regions of ReLU networks, both by theoretically bounding their connectivity and diameter and by empirically characterizing it using experiments on trained networks.

**Abstract**: It is well established that ReLU networks define continuous piecewise-linear functions, and that their linear regions are polyhedra in the input space. These regions form a complex that fully partitions the input space. The way these regions fit together is fundamental to the behavior of the network, as nonlinearities occur only at the boundaries where these regions connect. However, relatively little is known about the geometry of these complexes beyond bounds on the total number of regions, and calculating the complex exactly is intractable for most networks. In this work, we prove new theoretical results about these complexes that hold for all fully-connected ReLU networks, specifically about their connectivity graphs in which nodes correspond to regions and edges exist between each pair of regions connected by a face. We find that the average degree of this graph is upper bounded by twice the input dimension regardless of the width and depth of the network, and that the diameter of this graph has an upper bound that does not depend on input dimension, despite the number of regions increasing exponentially with input dimension. We corroborate our findings through experiments with networks trained on both synthetic and real-world data, which provide additional insight into the geometry of ReLU networks.

---

## 192. ThinKV: Thought-Adaptive KV Cache Compression for Efficient Reasoning Models

**OpenReview**: [https://openreview.net/forum?id=M3CeHnZKNC](https://openreview.net/forum?id=M3CeHnZKNC)

**Authors**: Akshat Ramachandran (Georgia Institute of Technology), Marina Neseem (NVIDIA), Charbel Sakr (NVIDIA), Rangharajan Venkatesan (Purdue University), Brucek Khailany (NVIDIA), Tushar Krishna (Georgia Institute of Technology)

**Institutions**: Georgia Institute of Technology, NVIDIA, Purdue University

**Primary Area**: generative models

**Keywords**: Large Reasoning Models, KV Cache Compression, Quantization, Eviction, Sparsity, Thought-Aware Compression

**Abstract**: The long-output context generation of large reasoning models enables extended chain of thought (CoT) but also drives rapid growth of the key–value (KV) cache, quickly overwhelming GPU memory. To address this challenge, we propose ThinKV, a thought-adaptive KV cache compression framework. ThinKV is based on the observation that attention sparsity reveals distinct thought types with varying importance within the CoT. It applies a hybrid quantization–eviction strategy, assigning token precision by thought importance and progressively evicting tokens from less critical thoughts as reasoning trajectories evolve. Furthermore, to implement ThinKV, we design a kernel that extends PagedAttention to enable efficient reuse of evicted tokens' memory slots, eliminating compaction overheads. Extensive experiments on DeepSeek-R1-Distill, GPT-OSS, and NVIDIA AceReason across mathematics and coding benchmarks show that ThinKV achieves near-lossless accuracy with less than 5% of the original KV cache, while improving performance with up to 5.8x higher inference throughput over SoTA baselines.

---

## 193. Difficult Examples Hurt Unsupervised Contrastive Learning: A Theoretical Perspective

**OpenReview**: [https://openreview.net/forum?id=5LMdnUdAoy](https://openreview.net/forum?id=5LMdnUdAoy)

**Authors**: Yi-Ge Zhang (Peking University), Jingyi Cui (Peking University), Qiran Li (The Hong Kong University of Science and Technology), Yisen Wang

**Institutions**: Peking University, The Hong Kong University of Science and Technology

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Machine Learning. Self-Supervised Learning. Difficult Examples

**TL;DR**: We introduce a similarity-based theoretical framework that shows how difficult boundary examples impair generalization in unsupervised contrastive learning, and we design  mechanisms that address this issue and boost downstream accuracy.

**Abstract**: Unsupervised contrastive learning has shown significant performance improvements in recent years, often approaching or even rivaling supervised learning in various tasks. However, its learning mechanism is fundamentally different from supervised learning. Previous works have shown that difficult examples (well-recognized in supervised learning as examples around the decision boundary),  which are essential in supervised learning, contribute minimally in unsupervised settings. In this paper, perhaps surprisingly, we find that the direct removal of difficult examples, although reduces the sample size, can boost the downstream classification performance of contrastive learning. To uncover the reasons behind this, we develop a theoretical framework modeling the similarity between different pairs of samples. Guided by this framework, we conduct a thorough theoretical analysis revealing that the presence of difficult examples negatively affects the generalization of contrastive learning. Furthermore, we demonstrate that the removal of these examples, and techniques such as margin tuning and temperature scaling can enhance its generalization bounds, thereby improving performance.
Empirically, we propose a simple and efficient mechanism for selecting difficult examples and validate the effectiveness of the aforementioned methods, which substantiates the reliability of our proposed theoretical framework.

---

## 194. Let Features Decide Their Own Solvers: Hybrid Feature Caching for Diffusion Transformers

**OpenReview**: [https://openreview.net/forum?id=URbsHlTK8c](https://openreview.net/forum?id=URbsHlTK8c)

**Authors**: Shikang Zheng, Guantao Chen (SUN YAT-SEN UNIVERSITY), Qinming Zhou (Tsinghua University), Yuqi Lin (Jilin University), Lixuan He, Chang Zou (Shanghai Jiaotong University), Peiliang Cai (Shanghai Jiaotong University), Jiacheng Liu (Shanghai Jiaotong University), Linfeng Zhang (Shanghai Jiaotong University)

**Institutions**: SUN YAT-SEN UNIVERSITY, Tsinghua University, Jilin University, Shanghai Jiaotong University

**Primary Area**: generative models

**Keywords**: Generative models, Efficient ML, Diffusion Transformer Acceleration, Feature Caching

**Abstract**: Diffusion Transformers offer state-of-the-art fidelity in image and video synthesis, but their iterative sampling process remains a major bottleneck due to the high cost of transformer forward passes at each timestep. To mitigate this, feature caching has emerged as a training-free acceleration technique that reuses hidden representations. However, existing methods often apply a uniform caching strategy across all feature dimensions, ignoring their heterogeneous dynamic behaviors. Therefore, we adopt a new perspective by modeling hidden feature evolution as a mixture of ODEs across dimensions, and introduce \textbf{HyCa}, a Hybrid ODE solver inspired caching framework that applies dimension-wise caching strategies. HyCa achieves near-lossless acceleration across diverse tasks and models, including 5.55$\times$ speedup on FLUX, 5.56$\times$ speedup on HunyuanVideo, 6.24$\times$ speedup on Qwen-Image and Qwen-Image-Edit without retraining.

---

## 195. MotionStream: Real-Time Video Generation with Interactive Motion Controls

**OpenReview**: [https://openreview.net/forum?id=v1DKz5Vxr7](https://openreview.net/forum?id=v1DKz5Vxr7)

**Authors**: Joonghyuk Shin (Seoul National University), Zhengqi Li (Google), Richard Zhang (Adobe Systems), Jun-Yan Zhu (Carnegie Mellon University), Jaesik Park (Seoul National University), Eli Shechtman (Adobe), Xun Huang

**Institutions**: Seoul National University, Google, Adobe Systems, Carnegie Mellon University, Adobe

**Primary Area**: generative models

**Keywords**: Interactive Video Generation, Motion Control, Real-Time Generation, Causal Generation

**TL;DR**: We present MotionStream, a streaming (real-time, infinite length) video generation system with motion controls, unlocking new possibilities for interactive content creation.

**Abstract**: Current motion-conditioned video generation methods suffer from prohibitive latency (minutes per video) and non-causal processing that prevents real-time interaction. We present MotionStream, enabling sub-second latency with up to 29 FPS streaming generation on a single GPU. Our approach begins by augmenting a text-to-video model with motion control, which generates high-quality videos that adhere to the global text prompt and local motion guidance, but does not perform inference on the fly. As such, we distill this bidirectional teacher into a causal student through Self Forcing with Distribution Matching Distillation, enabling real-time streaming inference. Several key challenges arise when generating videos of long, potentially infinite time-horizons -- (1) bridging the domain gap from training on finite length and extrapolating to infinite horizons, (2) sustaining high quality by preventing error accumulation, and (3) maintaining fast inference, without incurring growth in computational cost due to increasing context windows. A key to our approach is introducing carefully designed sliding-window causal attention, combined with attention sinks. By incorporating self-rollout with attention sinks and KV cache rolling during training, we properly simulate inference-time extrapolations with a fixed context window, enabling constant-speed generation of arbitrarily long videos. Our models achieve state-of-the-art results in motion following and video quality while being two orders of magnitude faster, uniquely enabling infinite-length streaming. With MotionStream, users can paint trajectories, control cameras, or transfer motion, and see results unfold in real-time, delivering a truly interactive experience.

---

## 196. BioX-Bridge: Model Bridging for Unsupervised Cross-Modal Knowledge Transfer across Biosignals

**OpenReview**: [https://openreview.net/forum?id=1448q0s3zZ](https://openreview.net/forum?id=1448q0s3zZ)

**Authors**: Chenqi Li (University of Oxford), Yu Liu (University of Oxford), Timothy Denison (University of Oxford), Tingting Zhu (University of Oxford)

**Institutions**: University of Oxford

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: biosignal, ai for healthcare, humans and ai, unsupervised cross-modal knowledge transfer

**Abstract**: Biosignals offer valuable insights into the physiological states of the human body. Although biosignal modalities differ in functionality, signal fidelity, sensor comfort, and cost, they are often intercorrelated, reflecting the holistic and interconnected nature of human physiology. This opens up the possibility of performing the same tasks using alternative biosignal modalities, thereby improving the accessibility, usability, and adaptability of health monitoring systems. However, the limited availability of large labeled datasets presents challenges for training models tailored to specific tasks and modalities of interest. Unsupervised cross-modal knowledge transfer offers a promising solution by leveraging knowledge from an existing modality to support model training for a new modality. Existing methods are typically based on knowledge distillation, which requires running a teacher model alongside student model training, resulting in high computational and memory overhead. This challenge is further exacerbated by the recent development of foundation models that demonstrate superior performance and generalization across tasks at the cost of large model sizes. To this end, we explore a new framework for unsupervised cross-modal knowledge transfer of biosignals by training a lightweight bridge network to align the intermediate representations and enable information flow between foundation models and across modalities. Specifically, we introduce an efficient strategy for selecting alignment positions where the bridge should be constructed, along with a flexible prototype network as the bridge architecture. Extensive experiments across multiple biosignal modalities, tasks, and datasets show that BioX-Bridge reduces the number of trainable parameters by 88-99\% while maintaining or even improving transfer performance compared to state-of-the-art methods.

---

## 197. Compactness and Consistency: A Conjoint Framework for Deep Graph Clustering

**OpenReview**: [https://openreview.net/forum?id=9jdQLmPUHW](https://openreview.net/forum?id=9jdQLmPUHW)

**Authors**: Wei Ju, Siyu Yi (Sichuan University), Kangjie Zheng (Wellcome Sanger Institute), Yifan Wang (University of International Business and Economics), Ziyue Qiao, Li Shen (Sun Yat-Sen University), Yongdao Zhou (Nankai University), Xiaochun Cao (SUN YAT-SEN UNIVERSITY), Jiancheng Lv (Sichuan University)

**Institutions**: Sichuan University, Wellcome Sanger Institute, University of International Business and Economics, Sun Yat-Sen University, Nankai University, SUN YAT-SEN UNIVERSITY

**Primary Area**: learning on graphs and other geometries & topologies

**Keywords**: Graph Neural Networks, Graph Clustering, Representation Learning, Compactness Learning, Consistency Learning

**Abstract**: Graph clustering is a fundamental task in data analysis, aiming at grouping nodes with similar characteristics in the graph into clusters. This problem has been widely explored using graph neural networks (GNNs) due to their ability to leverage node attributes and graph topology for effective cluster assignments. However, representations learned through GNNs typically struggle to capture global relationships between nodes via local message-passing mechanisms. Moreover, the redundancy and noise inherently present in graph data may easily result in node representations lacking compactness and robustness. To address these issues, we propose a conjoint framework CoCo, which captures compactness and consistency in the learned node representations for deep graph clustering. Technically, our CoCo leverages graph convolutional filters to learn robust node representations from both local and global views, and then encodes them into low-rank compact embeddings, thus effectively removing the redundancy and noise as well as uncovering the intrinsic underlying structure. To further enrich the node semantics, we develop a consistency learning strategy based on compact embeddings to facilitate knowledge transfer from the two perspectives. Our experimental results indicate that our CoCo outperforms state-of-the-art counterparts on various datasets. The code is available at https://github.com/juweipku/CoCo.

---

## 198. WAFT: Warping-Alone Field Transforms for Optical Flow

**OpenReview**: [https://openreview.net/forum?id=HTqGE0KcuF](https://openreview.net/forum?id=HTqGE0KcuF)

**Authors**: Yihan Wang (Princeton University), Jia Deng (Princeton University)

**Institutions**: Princeton University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Optical Flow; Computer Vision; Warping; Dense Correspondences

**Abstract**: We introduce Warping-Alone Field Transforms (WAFT), a simple and effective method for optical flow. WAFT is similar to RAFT but replaces cost volume with high-resolution warping, achieving better accuracy with lower memory cost. This design challenges the conventional wisdom that constructing cost volumes is necessary for strong performance. WAFT is a simple and flexible meta-architecture with minimal inductive biases and reliance on custom designs. Compared with existing methods, WAFT ranks 1st on Spring, Sintel, and KITTI benchmarks, achieves the best zero-shot generalization on KITTI, while being 1.3-4.1x faster than existing methods that have competitive accuracy (e.g., 1.3x than Flowformer++, 4.1x than CCMR+). Code and model weights are available at https://github.com/princeton-vl/WAFT.

---

## 199. FlashWorld: High-quality 3D Scene Generation within Seconds

**OpenReview**: [https://openreview.net/forum?id=2IftRjRB07](https://openreview.net/forum?id=2IftRjRB07)

**Authors**: Xinyang Li (Xiamen University), Tengfei Wang (Shanghai AI Lab), Zixiao Gu (Fudan University), Shengchuan Zhang (Xiamen University), Chunchao Guo (Tencent), Liujuan Cao (Xiamen University)

**Institutions**: Xiamen University, Shanghai AI Lab, Fudan University, Tencent

**Primary Area**: generative models

**Keywords**: 3D Scene Generation, Multi-view Diffusion Models, World Models, Distribution Matching Distillation

**TL;DR**: a generative model that produces high-quality 3D scenes from a single image or text prompt in seconds

**Abstract**: We propose FlashWorld, a generative model that produces 3D scenes from a single image or text prompt in seconds, $10 \sim 100\times$ faster than previous works while possessing superior rendering quality.
Our approach shifts from the conventional multi-view-oriented (MV-oriented) paradigm, which generates multi-view images for subsequent 3D reconstruction, to a 3D-oriented approach where the model directly produces 3D Gaussian representations during multi-view generation.
While ensuring 3D consistency, 3D-oriented method typically suffers poor visual quality.
FlashWorld includes a dual-mode pre-training phase followed by a cross-mode post-training phase, effectively integrating the strengths of both paradigms.
Specifically, leveraging the prior from a video diffusion model, we first pre-train a dual-mode multi-view diffusion model, which jointly supports MV-oriented and 3D-oriented generation mode. 
To bridge the quality gap in 3D-oriented generation, we further propose a cross-mode post-training distillation by matching distribution from consistent 3D-oriented mode to high-quality MV-oriented mode. 
This not only enhances visual quality while maintaining 3D consistency, but also reduces the required denoising steps for inference.
Also, we propose a strategy to leverage massive single-view images and text prompts during this process to enhance the model's generalization to out-of-distribution inputs.
Extensive experiments demonstrate the superiority and efficiency of our method.
Our code is released at https://github.com/imlixinyang/FlashWorld.

---

## 200. TabStruct: Measuring Structural Fidelity of Tabular Data

**OpenReview**: [https://openreview.net/forum?id=XOPH34Extq](https://openreview.net/forum?id=XOPH34Extq)

**Authors**: Xiangjian Jiang (University of Cambridge), Nikola Simidjievski (Télécom Paris), Mateja Jamnik (University of Cambridge)

**Institutions**: University of Cambridge, Télécom Paris

**Primary Area**: datasets and benchmarks

**Keywords**: Tabular data, Tabular data structure, Synthetic data generation

**TL;DR**: We propose TabStruct, a comprehensive benchmark, along with a novel metric, global utility, for evaluating the structural fidelity of tabular data without requiring access to ground-truth causal structures.

**Abstract**: Evaluating tabular generators remains a challenging problem, as the unique causal structural prior of heterogeneous tabular data does not lend itself to intuitive human inspection. Recent work has introduced structural fidelity as a tabular-specific evaluation dimension to assess whether synthetic data complies with the causal structures of real data. However, existing benchmarks often neglect the interplay between structural fidelity and conventional evaluation dimensions, thus failing to provide a holistic understanding of model performance. Moreover, they are typically limited to toy datasets, as quantifying existing structural fidelity metrics requires access to ground-truth causal structures, which are rarely available for real-world datasets. In this paper, we propose a novel evaluation framework that jointly considers structural fidelity and conventional evaluation dimensions. We introduce a new evaluation metric, global utility, which enables the assessment of structural fidelity even in the absence of ground-truth causal structures. In addition, we present TabStruct, a comprehensive evaluation benchmark offering large-scale quantitative analysis on 13 tabular generators from nine distinct categories, across 29 datasets. Our results demonstrate that global utility provides a task-independent, domain-agnostic lens for tabular generator performance. We release the TabStruct benchmark suite, including all datasets, evaluation pipelines, and raw results. Code is available at https://github.com/SilenceX12138/TabStruct.

---

## 201. Uncover Underlying Correspondence for Robust Multi-view Clustering

**OpenReview**: [https://openreview.net/forum?id=a4S1nQay3b](https://openreview.net/forum?id=a4S1nQay3b)

**Authors**: Haochen Zhou (Sichuan University), Guofeng Ding (Sichuan University), Mouxing Yang (Sichuan University), Peng Hu (Sichuan University), Yijie Lin (Sichuan University), Xi Peng (Sichuan University)

**Institutions**: Sichuan University

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Multi-view clustering; Noisy Correspondence

**Abstract**: Multi-view clustering (MVC) aims to group unlabeled data into semantically meaningful clusters by leveraging cross-view consistency. 
However, real-world datasets collected from the web often suffer from noisy correspondence (NC), which breaks the consistency prior and results in unreliable alignments.
In this paper, we identify two critical forms of NC that particularly harm clustering: i) category-level mismatch, where semantically consistent samples from the same class are mistakenly treated as negatives; and ii) sample-level mismatch, where collected cross-view pairs are misaligned and some samples may even lack any valid counterpart.
To address these challenges, we propose \textbf{CorreGen}, a generative framework that formulates noisy correspondence learning in MVC as maximum likelihood estimation over underlying cross-view correspondences. 
The objective is elegantly solved via an Expectation–Maximization algorithm: in the E-step, soft correspondence distributions are inferred across views, capturing class-level relations while adaptively down-weighting noisy or unalignable samples through GMM-guided marginals; in the M-step, the embedding network is updated to maximize the expected log-likelihood. Extensive experiments on both synthetic and real-world noisy datasets demonstrate that our method significantly improves clustering robustness. The code will be released upon acceptance.

---

## 202. Instilling an Active Mind in Avatars via Cognitive Simulation

**OpenReview**: [https://openreview.net/forum?id=80JylHgQn1](https://openreview.net/forum?id=80JylHgQn1)

**Authors**: Jianwen Jiang, Weihong Zeng (ByteDance Inc.), Zerong Zheng (ByteDance Inc.), Jiaqi Yang (ByteDance Inc.), Chao Liang (ByteDance Inc.), Wang Liao (ByteDance Inc.), Han Liang (ByteDance Inc.), Weifeng Chen (ByteDance Inc.), XING WANG (ByteDance), Yuan Zhang, Mingyuan Gao (ByteDance Inc.)

**Institutions**: ByteDance Inc., ByteDance

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Video Generatio, Human Animation, Avatar, Multimedia

**TL;DR**: This paper introduces a novel framework that uses a Large Language Model (LLM) for semantic guidance and a Multimodal Diffusion Transformer (DiT) for fusion to generate expressive, context-aware video avatars, demonstrating competitive performance

**Abstract**: Current video avatar models can generate fluid animations but struggle to capture a character's authentic essence, primarily synchronizing motion with low-level audio cues instead of understanding higher-level semantics like emotion or intent. To bridge this gap, we propose a novel framework for generating character animations that are not only physically plausible but also semantically rich and expressive. Our model is built on two technical innovations. First, we employ Multimodal Large Language Models to generate a structured textual representation from input conditions, providing high-level semantic guidance for creating contextually and emotionally resonant actions. Second, to ensure robust fusion of multimodal signals, we introduce a specialized Multimodal Diffusion Transformer architecture featuring a novel Pseudo Last Frame design. This allows our model to accurately interpret the joint semantics of audio, images and text, generating motions that are deeply coherent with the overall context. Comprehensive experiments validate the superiority of our method, which achieves compelling results in lip-sync accuracy, video quality, motion naturalness, and semantic consistency. The approach also shows strong generalization to challenging scenarios, including multi-person and non-human subjects. Our video results are linked in https://omnihuman-lab.github.io/v1_5/ .

---

## 203. Diffusion Language Model Knows the Answer Before It Decodes

**OpenReview**: [https://openreview.net/forum?id=g88nt4ieTG](https://openreview.net/forum?id=g88nt4ieTG)

**Authors**: Pengxiang Li (Hong Kong Polytechnic University), Yefan Zhou (Dartmouth College), Dilxat Muhtar (Nanjing University), Lu Yin (University of Surrey), Shilin Yan (Alibaba Group), Li Shen (Sun Yat-Sen University), Yi Liang (Google), Soroush Vosoughi (Dartmouth College), Shiwei Liu (ELLIS Institute Tübingen & Max Planck Institute for Intelligent Systems)

**Institutions**: Hong Kong Polytechnic University, Dartmouth College, Nanjing University, University of Surrey, Alibaba Group, Sun Yat-Sen University, Google, ELLIS Institute Tübingen & Max Planck Institute for Intelligent Systems

**Primary Area**: generative models

**Keywords**: diffusion language model, discrete

**Abstract**: Diffusion language models (DLMs) have recently emerged as an alternative to autoregressive approaches, offering parallel sequence generation and flexible token orders. However, their inference remains slower than that of autoregressive models, primarily due to the cost of bidirectional attention and the large number of refinement steps required for high-quality outputs. In this work, we highlight and leverage an overlooked property of DLMs, **early answer convergence**: in many cases, the correct answer can be internally identified by half steps before the final decoding step, both under semi-autoregressive and random re-masking schedules. For example, on GSM8K and MMLU, up to 97\% and 99\% of instances, respectively, can be decoded correctly using only half of the refinement steps.
Building on this observation, we introduce **Prophet**, a training-free fast decoding paradigm that enables **early commit decoding**. Specifically, Prophet dynamically decides whether to continue refinement or to go ''all-in'' (i.e., decode all remaining tokens in one step), using the confidence gap between the top-2 prediction candidates as the criterion. It integrates seamlessly into existing DLM implementations, incurs negligible overhead, and requires no additional training.
Empirical evaluations of LLaDA-8B and Dream-7B across multiple tasks show that Prophet reduces the number of decoding steps by up to 3.4$\times$ while preserving high generation quality. These results recast DLM decoding as a problem of ''when to stop refinement'', and demonstrate that early decode convergence provides a simple yet powerful mechanism for accelerating DLM inference, complementary to existing speedup techniques. Our code is submitted.

---

## 204. Generative Human Geometry Distribution

**OpenReview**: [https://openreview.net/forum?id=YsQM7sQl0j](https://openreview.net/forum?id=YsQM7sQl0j)

**Authors**: Xiangjun Tang (King Abdullah University of Science and Technology), Biao Zhang, Peter Wonka (Snap Inc.)

**Institutions**: King Abdullah University of Science and Technology, Snap Inc.

**Primary Area**: generative models

**Keywords**: 3D Generation, Human Generation, Geometry Encoding

**TL;DR**: We introduce the first method that integrates geometry distributions into generative modeling.

**Abstract**: Realistic human geometry generation is an important yet challenging task, requiring both the preservation of fine clothing details and the accurate modeling of clothing-body interactions. To tackle this challenge, we build upon Geometry distributions—a recently proposed representation that can model a single human geometry with high fidelity using a flow matching model. However, extending a single-geometry distribution to a dataset is non-trivial and inefficient for large-scale learning. To address this, we propose a new geometry distribution model by two key techniques: (1) encoding distributions as 2D feature maps rather than network parameters, and (2) using SMPL models as the domain instead of Gaussian and refining the associated flow velocity field. We then design a generative framework adopting a two-staged training paradigm analogous to state-of-the-art image and 3D generative models.
In the first stage, we compress geometry distributions into a latent space using a diffusion flow model; the second stage trains another flow model on this latent space. 
We validate our approach on two key tasks: pose-conditioned random avatar generation and avatar-consistent novel pose synthesis.
Experimental results demonstrate that our method outperforms existing state-of-the-art methods, achieving a 57% improvement in geometry quality.

---

## 205. EmotionThinker: Prosody-Aware Reinforcement Learning for Explainable Speech Emotion Reasoning

**OpenReview**: [https://openreview.net/forum?id=wbttgzp7MT](https://openreview.net/forum?id=wbttgzp7MT)

**Authors**: Dingdong WANG (Chinese University of Hong Kong, The Chinese University of Hong Kong), Shujie LIU (Microsoft), Tianhua Zhang (Chinese University of Hong Kong, The Chinese University of Hong Kong), Youjun Chen (Chinese University of Hong Kong, The Chinese University of Hong Kong), Jinyu Li (Microsoft), Helen M. Meng (The Chinese University of Hong Kong)

**Institutions**: Chinese University of Hong Kong, The Chinese University of Hong Kong, Microsoft, The Chinese University of Hong Kong

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Speech Emotion Recognition, Speech LLMs, Speech Processing, Reinforcement Learning

**Abstract**: Emotional information in speech plays a unique role in multimodal perception. However, current Speech Large Language Models (SpeechLLMs), similar to conventional speech emotion recognition (SER) systems, still treat emotion understanding as a simple classification problem. This provides limited interpretability of predictions, while leaving the LLMs’ expressive and reasoning capabilities underutilized. In this work, we take the first step to reformulate SER as a deep reasoning problem through reinforcement learning (RL). We propose EmotionThinker, which is designed to generate accurate emotion predictions with interpretable explanations grounded in fine-grained acoustic cues. To achieve this, we first construct EmotionCoT-35K, an emotional reasoning dataset with Chain-of-Thought annotations and detailed captions. Second, we observe that current SpeechLLMs exhibit weak prosody perception, whereas prosodic cues constitute fundamental signals for interpreting emotions. To address this, we develop the prosody-enhanced foundation model EmotionThinker-Base, and demonstrate that prosody enhancement improves emotion understanding. Third, we introduce Group-Relative-Policy-Optimization with Progressive-Trust-aware-Reasoning-Reward (GRPO-PTR}) for RL. Different from standard GRPO, which relies only on rule-based outcome rewards, GRPO-PTR progressively introduces reasoning reward, dynamically adjusts it with a trustworthiness weight reflecting the alignment between reasoning and outcome, and evaluates the overall reasoning quality with a reward model based on multi-dimensional criteria. EmotionThinker outperforms previous state-of-the-art evaluation models both in emotion accuracy and explanation quality, advancing SER toward interpretable multimodal reasoning.

---

## 206. Mastering Sparse CUDA Generation through Pretrained Models and Deep Reinforcement Learning

**OpenReview**: [https://openreview.net/forum?id=VdLEaGPYWT](https://openreview.net/forum?id=VdLEaGPYWT)

**Authors**: Yaoyu Wang (University of Chinese Academy of Sciences), Hankun Dai (University of the Chinese Academy of Sciences), Zhidong Yang (Hong Kong University of Science and Technology), Junmin Xiao (Institute of Computing Technology, Chinese Academy of Sciences), Guangming Tan (Insitute of Computing Technology, Chinese Academy of Sciences)

**Institutions**: University of Chinese Academy of Sciences, University of the Chinese Academy of Sciences, Hong Kong University of Science and Technology, Institute of Computing Technology, Chinese Academy of Sciences, Insitute of Computing Technology, Chinese Academy of Sciences

**Primary Area**: reinforcement learning

**Keywords**: Reinforcement Learning, CUDA Code Generation, High-Performance Computing

**TL;DR**: We propose SparseRL, a deep reinforcement learning framework that generates high-performance CUDA code for sparse matrix operations, achieving significant improvements in both correctness and execution efficiency.

**Abstract**: Code generation is a crucial research area in the field of artificial intelligence, holding the potential to revolutionize software development and streamline programming processes. However, generating the high-performance code, which need to be executed in a shorter time for the low-latency scenario, remains a formidable challenge. Existing methods often struggle to account for the irregularity of input sparse data in sparse programs and the need for domain-specific architectural knowledge, leading to sub-optimal performance. To tackle these issues, we propose the SparseRL framework. SparseRL leverages deep reinforcement learning, treating a pre-trained language model as a stochastic policy. It takes the row and column indices of non-zero elements in the sparse matrix as input and generates CUDA code as output for sparse matrix operations. We also introduce a domain-specific code generation mechanism for the dynamic input, a sinusoidal embedding technique tailored for sparse matrices, and a hierarchical reward function that considers both code correctness and execution efficiency. Experimental results demonstrate SparseRL achieves state-of-the-art performance. In sparse matrix-vector multiplication (SpMV) tasks, it improves the compilation rate by 20% compared to existing methods, and the generated code runs 30% faster on average. For sparse matrix-dense matrix multiplication (SpMM) tasks, SparseRL also shows significant performance gains. These results highlight the effectiveness of SparseRL in generating high-performance CUDA code for sparse matrix operations.

---

## 207. LongWriter-Zero: Mastering Ultra-Long Text Generation via Reinforcement Learning

**OpenReview**: [https://openreview.net/forum?id=JWx4DI2N8k](https://openreview.net/forum?id=JWx4DI2N8k)

**Authors**: Yuhao Wu (Singapore University of Technology and Design), Yushi Bai (Tsinghua University, Tsinghua University), Zhiqiang Hu (Tencent Hunyuan Multimodal), Roy Ka-Wei Lee (Singapore University of Technology and Design), Juanzi Li

**Institutions**: Singapore University of Technology and Design, Tsinghua University, Tsinghua University, Tencent Hunyuan Multimodal

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLMs, RL, Long-form generation

**Abstract**: Ultra-long generation by large language models (LLMs) is a widely demanded scenario, yet it remains a significant challenge due to their maximum generation length limit and overall quality degradation as sequence length increases. Previous approaches, exemplified by LongWriter, typically rely on ''teaching'', which involves supervised fine-tuning (SFT) on synthetic long-form outputs. However, this strategy heavily depends on synthetic SFT data, which is difficult and costly to construct, often lacks coherence and consistency, and tends to be overly artificial and structurally monotonous. In this work, we propose an incentivization-based approach that, starting entirely from scratch and without relying on any annotated or synthetic data, leverages reinforcement learning (RL) to foster the emergence of ultra-long, high-quality text generation capabilities in LLMs. We perform RL training starting from a base model, similar to R1-Zero, guiding it to engage in reasoning that facilitates planning and refinement during the writing process. To support this, we employ specialized reward models that steer the LLM towards improved length control, writing quality, and structural formatting. Experimental evaluations show that our LongWriter-Zero model, trained from Qwen2.5-32B, consistently outperforms traditional SFT methods on long-form writing tasks, achieving state-of-the-art results across all metrics on WritingBench and Arena-Write, and even surpassing 100B+ models such as DeepSeek R1 and Qwen3-235B.

---

## 208. RealPDEBench: A Benchmark for Complex Physical Systems with Real-World Data

**OpenReview**: [https://openreview.net/forum?id=y3oHMcoItR](https://openreview.net/forum?id=y3oHMcoItR)

**Authors**: Peiyan Hu (Chinese Academy of Sciences), Haodong Feng (Westlake University), Hongyuan Liu (Westlake University), Tongtong Yan (Shanghai Jiaotong University), Wenhao Deng (University of Glasgow), Tianrun Gao (Fudan University), Rong Zheng (Peking University), Haoren Zheng (Shanghai Jiaotong University), Chenglei Yu (Westlake University), Chuanrui Wang (Westlake University), Kaiwen Li (Shanghai Jiao Tong University), Zhi-Ming Ma (Academy of Mathematics and Systems Science, Chinese Academy of Sciences, Chinese Academy of Sciences), Dezhi Zhou (Shanghai Jiao Tong University), Xingcai Lu (Shanghai Jiaotong University), Dixia Fan (Westlake University), Tailin Wu (Westlake University)

**Institutions**: Chinese Academy of Sciences, Westlake University, Shanghai Jiaotong University, University of Glasgow, Fudan University, Peking University, Shanghai Jiao Tong University, Academy of Mathematics and Systems Science, Chinese Academy of Sciences, Chinese Academy of Sciences

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: complex physical system, PDE, benchmark, real-world data, prediction

**TL;DR**: We propose the first benchmark for complex physical systems with paired real-world data and simulated data, and explore how to bridge simulated and real-world data.

**Abstract**: Predicting the evolution of complex physical systems remains a central problem in science and engineering. Despite rapid progress in scientific Machine Learning (ML) models, a critical bottleneck is the lack of expensive real-world data, resulting in most current models being trained and validated on simulated data. Beyond limiting the development and evaluation of scientific ML, this gap also hinders research into essential tasks such as sim-to-real transfer. We introduce RealPDEBench, the first benchmark for scientific ML that integrates real-world measurements with paired numerical simulations. RealPDEBench consists of five datasets, three tasks, nine metrics, and ten baselines. We first present five real-world measured datasets with paired simulated datasets across different complex physical systems. We further define three tasks, which allow comparisons between real-world and simulated data, and facilitate the development of methods to bridge the two. Moreover, we design nine evaluation metrics, spanning data-oriented and physics-oriented metrics, and finally benchmark ten representative baselines, including state-of-the-art models, pretrained PDE foundation models, and a traditional method. Experiments reveal significant discrepancies between simulated and real-world data, while showing that pretraining with simulated data consistently improves both accuracy and convergence. In this work, we hope to provide insights from real-world data, advancing scientific ML toward bridging the sim-to-real gap and real-world deployment. Our benchmark, datasets, and instructions are available at https://realpdebench.github.io/.

---

## 209. Improving Diffusion Models for Class-imbalanced Training Data via Capacity Manipulation

**OpenReview**: [https://openreview.net/forum?id=wSGle6ag5I](https://openreview.net/forum?id=wSGle6ag5I)

**Authors**: Feng Hong (Shanghai Jiao Tong University), Jiangchao Yao, Yifei Shen (Microsoft Research Asia), Dongsheng Li (Microsoft Research Asia), Ya Zhang (Shanghai Jiao Tong University), Yanfeng Wang (Shanghai Jiao Tong University)

**Institutions**: Shanghai Jiao Tong University, Microsoft Research Asia

**Primary Area**: unsupervised, self-supervised, semi-supervised, and supervised representation learning

**Keywords**: Imbalance, Diffusion Models

**Abstract**: While diffusion models have achieved remarkable performance in image generation, they often struggle with the imbalanced datasets frequently encountered in real-world applications, resulting in significant performance degradation on minority classes. In this paper, we identify model capacity allocation as a key and previously underexplored factor contributing to this issue, providing a perspective that is orthogonal to existing research. Our empirical experiments and theoretical analysis reveal that majority classes monopolize an unnecessarily large portion of the model's capacity, thereby restricting the representation of minority classes. To address this, we propose Capacity Manipulation (CM), which explicitly reserves model capacity for minority classes. Our approach leverages a low-rank decomposition of model parameters and introduces a capacity manipulation loss to allocate appropriate capacity for capturing minority knowledge, thus enhancing minority class representation. Extensive experiments demonstrate that CM consistently and significantly improves the robustness of diffusion models on imbalanced datasets, and when combined with existing methods, further boosts overall performance.

---

## 210. SANA-Video: Efficient Video Generation with Block Linear Diffusion Transformer

**OpenReview**: [https://openreview.net/forum?id=mzAchylAtf](https://openreview.net/forum?id=mzAchylAtf)

**Authors**: Junsong Chen (University of Hong Kong), Yuyang Zhao (NVIDIA), Jincheng YU (NVIDIA), Ruihang Chu (Wan Team), Junyu Chen (Tsinghua University, Tsinghua University), Shuai Yang (The Hong Kong University of Science and Technology), Xianbang Wang (Tsinghua University), Yicheng Pan (Tsinghua University), Daquan Zhou (Bytedance), Huan Ling (NVIDIA), Haozhe Liu (King Abdullah University of Science and Technology), Hongwei Yi (Max Planck Institute for Intelligent Systems, Max-Planck Institute), Hao Zhang (NVIDIA Corporation), Muyang Li (Massachusetts Institute of Technology), Yukang Chen (NVIDIA), Han Cai (NVIDIA), Sanja Fidler (Department of Computer Science, University of Toronto), Ping Luo (The University of Hong Kong), Song Han, Enze Xie (NVIDIA Research)

**Institutions**: University of Hong Kong, NVIDIA, Wan Team, Tsinghua University, Tsinghua University, The Hong Kong University of Science and Technology, Tsinghua University, Bytedance, King Abdullah University of Science and Technology, Max Planck Institute for Intelligent Systems, Max-Planck Institute, NVIDIA Corporation, Massachusetts Institute of Technology, Department of Computer Science, University of Toronto, The University of Hong Kong, NVIDIA Research

**Primary Area**: generative models

**Keywords**: Video Diffusion Model

**Abstract**: We introduce SANA-Video, a small diffusion model that can efficiently generate videos up to 720×1280 resolution and minute-length duration. SANA-Video synthesizes high-resolution, high-quality and long videos with strong text-video alignment at a remarkably fast speed, deployable on RTX 5090 GPU. Two core designs ensure our efficient, effective and long video generation:  (1) Linear DiT: We leverage linear attention as the core operation, which is more efficient than vanilla attention given the large number of tokens processed in video generation. (2) Constant-Memory KV cache for Block Linear Attention: we design block-wise autoregressive approach for long video generation by employing a constant-memory state, derived from the cumulative properties of linear attention. This KV cache provides the Linear DiT with global context at a fixed memory cost, eliminating the need for a traditional KV cache and enabling efficient, minute-long video generation. In addition, we explore effective data filters and model training strategies, narrowing the training cost to 12 days on 64 H100 GPUs, which is only 1\% of the cost of MovieGen. Given its low cost, SANA-Video achieves competitive performance compared to modern state-of-the-art small diffusion models (e.g., Wan 2.1-1.3B and SkyReel-V2-1.3B) while being 16x faster in measured latency. Moreover, SANA-Video can be deployed on RTX 5090 GPUs with NVFP4 precision, accelerating the inference speed of generating a 5-second 720p video from 71s to 29s (2.4x} speedup). In summary, SANA-Video enables low-cost, high-quality video generation. Code and model will be publicly released.

---

## 211. Stable Video Infinity: Infinite-Length Video Generation with Error Recycling

**OpenReview**: [https://openreview.net/forum?id=X96Ei9n34a](https://openreview.net/forum?id=X96Ei9n34a)

**Authors**: Wuyang Li (EPFL - EPF Lausanne), Wentao Pan (Chinese University of Hong Kong), Po-Chien Luan (EPFL - EPF Lausanne), Yang Gao (EPFL - EPF Lausanne), Alexandre Alahi (EPFL)

**Institutions**: EPFL - EPF Lausanne, Chinese University of Hong Kong, EPFL

**Primary Area**: generative models

**Keywords**: Infinite-Length Video Generation, Error Accumulation

**Abstract**: We propose **Stable Video Infinity (SVI)** that can generate non-looping, ultra-long videos with stable visual quality, while supporting per-clip prompt control and multi-modal conditioning. While existing long-video methods attempt to _**mitigate accumulated errors**_ via handcrafted anti-drifting (e.g., modified noise scheduler, frame anchoring), they remain limited to single-prompt extrapolation, producing homogeneous scenes with repetitive motions. We identify that the fundamental challenge extends beyond error accumulation to a critical discrepancy between the training assumption (seeing clean data) and the test-time autoregressive reality (conditioning on self-generated, error-prone outputs). To bridge this hypothesis gap, SVI incorporates **Error-Recycling Fine-Tuning**, a new type of efficient training that recycles the Diffusion Transformer (DiT)’s self-generated errors into supervisory prompts, thereby encouraging DiT to _**actively identify and correct its own errors**_. This is achieved by injecting, collecting, and banking errors through closed-loop recycling, autoregressively learning from error-injected feedback. Specifically, we (i) inject historical errors made by DiT to intervene on clean inputs, simulating error-accumulated trajectories in flow matching; (ii) efficiently approximate predictions with one-step bidirectional integration and calculate errors with residuals; (iii) dynamically bank errors into replay memory across discretized timesteps, which are resampled for new input. SVI is able to scale videos from seconds to infinite durations with no additional inference cost, while remaining compatible with diverse conditions (e.g., audio, skeleton, and text streams). We evaluate SVI on three benchmarks, including consistent, creative, and conditional settings, thoroughly verifying its versatility and state-of-the-art role.

---

## 212. Extending Sequence Length is Not All You Need: Effective Integration of Multimodal Signals for Gene Expression Prediction

**OpenReview**: [https://openreview.net/forum?id=wwPSfcf5Pj](https://openreview.net/forum?id=wwPSfcf5Pj)

**Authors**: Zhao Yang (Renmin University of China), Yi Duan (Renmin University of China), Jiwei Zhu (Renmin University of China), Ying Ba (Renmin University of China), Chuan Cao (Research, Microsoft), Bing Su (Renmin University of China)

**Institutions**: Renmin University of China, Research, Microsoft

**Primary Area**: applications to physical sciences (physics, chemistry, biology, etc.)

**Keywords**: dna language model, gene expression prediction, multimodal information integration, causal intervention

**Abstract**: Gene expression prediction, which predicts mRNA expression levels from DNA sequences, presents significant challenges. Previous works often focus on extending input sequence length to locate distal enhancers, which may influence target genes from hundreds of kilobases away. Our work first reveals that for current models, long sequence modeling can decrease performance. Even carefully designed algorithms only mitigate the performance degradation caused by long sequences. Instead, we find that proximal multimodal epigenomic signals near target genes prove more essential. Hence we focus on how to better integrate these signals, which has been overlooked. We find that different signal types serve distinct biological roles, with some directly marking active regulatory elements while others reflect background chromatin patterns that may introduce confounding effects. Simple concatenation may lead models to develop spurious associations with these background patterns. To address this challenge, we propose Prism, 
a framework that learns multiple combinations of high-dimensional epigenomic features to represent distinct background chromatin states and uses backdoor adjustment to mitigate confounding effects. Our experimental results demonstrate that proper modeling of multimodal epigenomic signals achieves state-of-the-art performance using only short sequences for gene expression prediction.

---

## 213. MomaGraph: State-Aware Unified Scene Graphs with Vision-Language Models for Embodied Task Planning

**OpenReview**: [https://openreview.net/forum?id=3eTr9dGwJv](https://openreview.net/forum?id=3eTr9dGwJv)

**Authors**: Yuanchen Ju (Tsinghua University, Tsinghua University), Yongyuan Liang (University of Maryland, College Park), Yen-Jen Wang (University of California, Berkeley), Gireesh Nandiraju (Peking University), Yuanliang Ju (University of Toronto), Seungjae Lee (University of Maryland, College Park), Qiao Gu (University of Toronto), Elvis Hsieh (University of California, Berkeley), Furong Huang (University of Maryland), Koushil Sreenath (University of California Berkeley)

**Institutions**: Tsinghua University, Tsinghua University, University of Maryland, College Park, University of California, Berkeley, Peking University, University of Toronto, University of Maryland, University of California Berkeley

**Primary Area**: applications to robotics, autonomy, planning

**Keywords**: Scene Graph, Task Planning, Spatial Understanding, Mobile Manipulation

**TL;DR**: We present MomaGraph, a dataset and benchmark for task-oriented scene graphs, and MomaGraph-R1, a 7B model that predicts graphs and plans tasks in a Graph-then-Plan framework.

**Abstract**: Mobile manipulators in households must both navigate and manipulate. This requires a compact, semantically rich scene representation that captures where objects are, how they function, and which parts are actionable. Scene graphs are a natural choice, yet prior work often separates spatial and functional relations, treats scenes as static snapshots without object states or temporal updates, and overlooks information most relevant for accomplishing the current task. To overcome these shortcomings, we introduce MomaGraph, a unified scene representation for embodied agents that integrates spatial-functional relationships and part-level interactive elements. However, advancing such a representation requires both suitable data and rigorous evaluation, which have been largely missing. To address this, we construct MomaGraph-Scenes, the first large-scale dataset of richly annotated, task-driven scene graphs in household environments, and design MomaGraph-Bench, a systematic evaluation suite spanning six reasoning capabilities from high-level planning to fine-grained scene understanding. Built upon this foundation, we further develop MomaGraph-R1, a 7B vision–language model trained with reinforcement learning on MomaGraph-Scenes. MomaGraph-R1 predicts task-oriented scene graphs and serves as a zero-shot task planner under a Graph-then-Plan framework. Extensive experiments show that our model achieves state-of-the-art results among open-source models, reaching 71.6% accuracy on the benchmark (+11.4% over the best baseline), while generalizing across public benchmarks and transferring effectively to real-robot experiments. More visualizations and robot demonstrations are available at https://momagraph.github.io/.

---

## 214. Learning to See Before Seeing: Demystifying LLM Visual Priors from Language Pre-training

**OpenReview**: [https://openreview.net/forum?id=pfw176o1YJ](https://openreview.net/forum?id=pfw176o1YJ)

**Authors**: Junlin Han (University of Oxford), Shengbang Tong (New York University), David Fan (Facebook AI Research), Yufan Ren (Facebook), Koustuv Sinha (Meta (FAIR)), Philip Torr (University of Oxford), Filippos Kokkinos (Meta AI)

**Institutions**: University of Oxford, New York University, Facebook AI Research, Facebook, Meta (FAIR), Meta AI

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: LLM pre-training, MLLMs, multi-modality

**TL;DR**: Explore and understand the visual priors within LLMs and thus build better MLLMs.

**Abstract**: Large Language Models (LLMs), despite being trained on text alone, surprisingly develop rich visual priors. These priors allow latent visual capabilities to be unlocked for vision tasks with a relatively small amount of multimodal data, and to perform symbolic visual generation tasks without ever having seen an image. Through systematic analysis, we reveal that visual priors—the implicit, emergent knowledge about the visual world acquired during language pre-training—are composed of separable perception and reasoning priors with unique scaling trends and origins. We show that an LLM's latent visual reasoning ability is predominantly developed by pre-training on reasoning-centric data (\eg, code, math, academia) and scales progressively. This reasoning prior acquired from language pre-training is transferable and universally applicable to visual reasoning. In contrast, the perception prior emerges more diffusely from broad corpora, and perception ability is more sensitive to the vision encoder and visual instruction tuning data. In parallel, text describing the visual world proves crucial, though its performance impact saturates rapidly. Leveraging these insights, we propose a data-centric recipe for pre-training vision-aware LLMs and verify it in 1T token scale pre-training.  Our findings are grounded in over 100 controlled experiments consuming 500,000 GPU-hours, spanning the full MLLM construction pipeline—from LLM pre-training to visual alignment and supervised multimodal fine-tuning—across five model scales, a wide range of data categories and mixtures, and multiple adaptation setups. Along with our main findings, we also propose and investigate several hypotheses, and introduce a Multi-Level Existence Bench (MLE-Bench) to facilitate future research. Together, this work provides a new way of deliberately cultivating visual priors from language pre-training, paving the way for the next generation of multimodal LLMs.

We recommend a visit to our project page (https://junlinhan.github.io/projects/lsbs/) for an interactive reading.

---

## 215. Benchmarking Empirical Privacy Protection for Adaptations of Large Language Models

**OpenReview**: [https://openreview.net/forum?id=jY7fAo9rfK](https://openreview.net/forum?id=jY7fAo9rfK)

**Authors**: Bartłomiej Marek (CISPA Helmholtz Center for Information Security), Lorenzo Rossi (CISPA Helmholtz Center for Information Security), Vincent Hanke (CISPA Helmholtz Center for Information Security), Xun Wang (CISPA Helmholtz Center for Information Security), Michael Backes, Franziska Boenisch, Adam Dziedzic

**Institutions**: CISPA Helmholtz Center for Information Security

**Primary Area**: datasets and benchmarks

**Keywords**: privacy, llm, adaptations, auditing, differential privacy

**TL;DR**: We benchmark various differential private adaptations for LLMs for their empirical privacy protection and find that it varies widely, depending on the adaptation method,

**Abstract**: Recent work has applied differential privacy (DP) to adapt large language models (LLMs) for sensitive applications, offering theoretical guarantees. However, its practical effectiveness remains unclear, partly due to LLM pretraining, where overlaps and interdependencies with adaptation data can undermine privacy despite DP efforts. To analyze this issue in practice, we investigate privacy risks under DP adaptations in LLMs using state-of-the-art attacks such as robust membership inference and canary data extraction. We benchmark these risks by systematically varying the adaptation data distribution, from exact overlaps with pretraining data, through in-distribution (IID) cases, to entirely out-of-distribution (OOD) examples. Additionally, we evaluate how different adaptation methods and different privacy regimes impact the vulnerability. Our results show that distribution shifts strongly influence privacy vulnerability: the closer the adaptation data is to the pretraining distribution, the higher the practical privacy risk at the same theoretical guarantee, even without direct data overlap. We find that parameter-efficient fine-tuning methods, such as LoRA, achieve the highest empirical privacy protection for OOD data. Our benchmark identifies key factors for achieving practical privacy in DP LLM adaptation, providing actionable insights for deploying customized models in sensitive settings. Looking forward, we propose a structured framework for holistic privacy assessment beyond adaptation privacy, to identify and evaluate risks across the full pretrain-adapt pipeline of LLMs.

---

## 216. ScaleCUA: Scaling Open-Source Computer Use Agents with Cross-Platform Data

**OpenReview**: [https://openreview.net/forum?id=yBFUqdJFZn](https://openreview.net/forum?id=yBFUqdJFZn)

**Authors**: Zhaoyang Liu (Hong Kong University of Science and Technology), JingJing Xie (Xiamen University), Zichen Ding (Shanghai Artificial Intelligence Laboratory), Zehao Li (University of Science and Technology of China), Bowen Yang (University of Science and Technology of China), Zhenyu Wu (Shanghai Jiaotong University), Xuehui Wang (Shanghai Jiaotong University), Qiushi Sun (University of Hong Kong), Shi Liu (Shanghai Artificial Intelligence Laboratory), Weiyun Wang (Fudan University), Shenglong Ye (Shanghai AI Laboratory), Qingyun Li (Shanghai Artificial Intelligence Laboratory), Zeyue Tian (Hong Kong University of Science and Technology), Gen Luo (Shanghai Artificial Intelligence Laboratory), Xiangyu Yue (The Chinese University of Hong Kong), Biqing Qi (Shanghai Artificial Intelligence Laboratory), Kai Chen (Shanghai AI Laboratory), Bowen Zhou (Tsinghua University), Yu Qiao, Qifeng Chen (Hong Kong University of Science and Technology), Wenhai Wang (The Chinese University of Hong Kong)

**Institutions**: Hong Kong University of Science and Technology, Xiamen University, Shanghai Artificial Intelligence Laboratory, University of Science and Technology of China, Shanghai Jiaotong University, University of Hong Kong, Fudan University, Shanghai AI Laboratory, The Chinese University of Hong Kong, Tsinghua University

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: GUI Agent, GUI Data Pipeline, Computer Use, Open Source

**Abstract**: Vision-Language Models (VLMs) have enabled computer use agents (CUAs) that operate GUIs autonomously, showing great potential, yet progress is limited by the lack of large-scale, open-source computer use data and foundation models. In this work, we introduce ScaleCUA, a step toward scaling open-source CUAs. It offers a large-scale dataset spanning 6 operating systems and 3 task domains, built via a closed-loop pipeline uniting automated agents with human experts. Trained on this scaled-up data, ScaleCUA can operate seamlessly across platforms.  Specifically, it delivers strong gains over baselines (+26.6 on WebArena-Lite-v2, +10.7 on ScreenSpot-Pro) and sets new state-of-the-art results (94.4% on MMBench-GUI L1-Hard, 60.6% on OSWorld-G, 47.4% on WebArena-Lite-v2). These findings underscore the power of data-driven scaling for general-purpose computer use agents. We will release data, models, and code to advance future research.

---

## 217. Train-before-Test Harmonizes Language Model Rankings

**OpenReview**: [https://openreview.net/forum?id=ORv3SAzus1](https://openreview.net/forum?id=ORv3SAzus1)

**Authors**: Guanhua Zhang (Max Planck Institute for Intelligent Systems, Max-Planck Institute), Ricardo Dominguez-Olmedo (Max-Planck-Institute for Intelligent Systems, Max-Planck Institute), Moritz Hardt (Max-Planck-Institute for Intelligent Systems, Max-Planck Institute)

**Institutions**: Max Planck Institute for Intelligent Systems, Max-Planck Institute, Max-Planck-Institute for Intelligent Systems, Max-Planck Institute

**Primary Area**: foundation or frontier models, including LLMs

**Keywords**: Evaluation, Large language model

**Abstract**: Existing language model benchmarks provide contradictory model rankings, even for benchmarks that aim to capture similar skills. This dilemma of conflicting rankings hampers model selection, clouds model comparisons, and adds confusion to a growing ecosystem of competing models. In this paper, we take a different perspective on model comparison: instead of relying on out-of-the-box performance via direct evaluation, we compare model potential by providing each model with identical benchmark-specific fine-tuning before evaluation. We call this approach train-before-test. Our primary contribution is a comprehensive empirical evaluation of model potential across 24 benchmarks and 61 models. First, we demonstrate that model potential rankings obtained through train-before-test exhibit remarkable consistency across all benchmarks. Whereas traditional rankings demonstrate little external validity under direct evaluation, they enjoy a significant degree of external validity when applying train-before-test: model potential rankings transfer gracefully from one benchmark to another. Second, train-before-test restores the connection between perplexity and downstream task performance, lost under direct evaluation. Remarkably, even pre-finetuning perplexity of a base model predicts post-finetuning downstream performance, suggesting that ranking consistency reflects inherent model potential rather than fine-tuning artifacts. Finally, train-before-test reduces the model-score matrix to essentially rank one, indicating that model potential is dominated by one latent factor, uncovered by train-before-test. While direct evaluation remains useful for assessing deployment-ready performance, train-before-test provides a complementary lens for understanding achievable performance of models after adaptation.

---

## 218. One for Two: A Unified Framework for Imbalanced Graph Classification via Dynamic Balanced Prototype

**OpenReview**: [https://openreview.net/forum?id=MraQM41SNS](https://openreview.net/forum?id=MraQM41SNS)

**Authors**: Guanjun Wang (University of Science and Technology of China), Binwu Wang (University of Science and Technology of China), Jiaming Ma (University of Science and Technology of China), Zhengyang Zhou (University of Science and Technology of China), Pengkun Wang (University of Science and Technology of China), Xu Wang (University of Science and Technology of China), Yang Wang (University of Science and Technology of China)

**Institutions**: University of Science and Technology of China

**Primary Area**: learning on graphs and other geometries & topologies

**Keywords**: Graph classification; graph imbalance learning; graph neural networks; Graph data mining; long-tail learning

**Abstract**: Graph Neural Networks (GNNs) have advanced graph classification, yet they remain vulnerable to graph-level imbalance, encompassing class imbalance and topological imbalance. To address both types of imbalance in a unified manner, we propose UniImb, a Unified framework for Imbalanced graph classification. Specifically, UniImb first captures multi-scale topological features and enhances data diversity via learnable personalized graph perturbations. It then employs a dynamic balanced prototype module to learn representative prototypes from graph instances, improving the quality of graph representations. Concurrently, a prototype load-balancing optimization term mitigates dominance by majority samples to equalize sample influence during training. We justify these design choices theoretically using the Information Bottleneck principle. Extensive experiments on 19 datasets-including a large-scale imbalanced air pollution graph dataset AirGraph released by us and 23 baselines demonstrate that UniImb has achieved dominant performance across various imbalanced scenarios. Our code is available at GitHub.

---

## 219. Veritas: Generalizable Deepfake Detection via Pattern-Aware Reasoning

**OpenReview**: [https://openreview.net/forum?id=5VXJPS1HoM](https://openreview.net/forum?id=5VXJPS1HoM)

**Authors**: Hao Tan (Institute of automation, Chinese Academy of Sciences), jun lan (AntGroup), Zichang Tan (Sangfor Technologies Inc.), Senyuan Shi (Institute of automation, Chinese academy of science), Ajian Liu (Institute of automation, Chinese academy of science, Chinese Academy of Sciences), Chuanbiao Song (Alibaba Group), Huijia Zhu (Ant Group), Weiqiang Wang (Ant Group), Jun Wan (Institute of automation, Chinese Academy of Sciences), Zhen Lei (Institute of Automation,  Chinese Academy of Sciences)

**Institutions**: Institute of automation, Chinese Academy of Sciences, AntGroup, Sangfor Technologies Inc., Institute of automation, Chinese academy of science, Institute of automation, Chinese academy of science, Chinese Academy of Sciences, Alibaba Group, Ant Group, Institute of Automation,  Chinese Academy of Sciences

**Primary Area**: applications to computer vision, audio, language, and other modalities

**Keywords**: Deepfake Detection, MLLMs

**TL;DR**: We introduce a MLLM-based detector for transparent deepfake detection, along with a holistic dataset for deepfake detection.

**Abstract**: Deepfake detection remains a formidable challenge due to the evolving nature of fake content in real-world scenarios. However, existing benchmarks suffer from severe discrepancies from industrial practice, typically featuring homogeneous training sources and low-quality testing images, which hinder the practical usage of current detectors. To mitigate this gap, we introduce **HydraFake**, a dataset that contains diversified deepfake techniques and in-the-wild forgeries, along with rigorous training and evaluation protocol, covering unseen model architectures, emerging forgery techniques and novel data domains. Building on this resource, we propose **Veritas**, a multi-modal large language model (MLLM) based deepfake detector. Different from vanilla chain-of-thought (CoT), we introduce *pattern-aware reasoning* that involves critical patterns such as "planning" and "self-reflection" to emulate human forensic process. We further propose a two-stage training pipeline to seamlessly internalize such deepfake reasoning capacities into current MLLMs. Experiments on HydraFake dataset reveal that although previous detectors show great generalization on cross-model scenarios, they fall short on unseen forgeries and data domains. Our Veritas achieves significant gains across different out-of-domain (OOD) scenarios, and is capable of delivering transparent and faithful detection outputs.

---

## 220. Semi-Supervised Preference Optimization with Limited Feedback

**OpenReview**: [https://openreview.net/forum?id=ghwxbTx7do](https://openreview.net/forum?id=ghwxbTx7do)

**Authors**: Seonggyun Lee (Yonsei University), Sungjun Lim (Yonsei University), Seojin Park (Yonsei University), Soeun Cheon (Korea Advanced Institute of Science & Technology), Kyungwoo Song (Yonsei University)

**Institutions**: Yonsei University, Korea Advanced Institute of Science & Technology

**Primary Area**: alignment, fairness, safety, privacy, and societal considerations

**Keywords**: Preference Optimization, Semi-Supervised Learning

**Abstract**: The field of preference optimization has made outstanding contributions to the alignment of language models with human preferences. Despite these advancements, recent methods still rely heavily on substantial paired (labeled) feedback data, leading to substantial resource expenditures. To address these challenges, we study the problem of Semi-Supervised Preference Optimization in which the idea is to learn from both a small number of pairwise preference labels and a large pool of unpaired samples simultaneously. Our key theoretical contribution proves the existence of an optimal reward threshold capable of separating winning and losing responses with high probability, which enables a principled pseudo-labeling of unpaired data. By leveraging these pseudo-labels, SSPO effectively distills latent preferences from large-scale unpaired data, thus maintaining human alignment while drastically reducing acquisition costs. Extensive experiments across datasets validate this remarkable data efficiency; for instance, SSPO trained with Mistral-7B-Instruct on just 1% of UltraFeedback consistently surpasses strong baselines trained on 10% of UltraFeedback.

---

## 221. Locality-aware Parallel Decoding for Efficient Autoregressive Image Generation

**OpenReview**: [https://openreview.net/forum?id=h06l9w1clt](https://openreview.net/forum?id=h06l9w1clt)

**Authors**: Zhuoyang Zhang (Massachusetts Institute of Technology), Luke J. Huang (Massachusetts Institute of Technology), Chengyue Wu (The University of Hong Kong), Shang Yang (Massachusetts Institute of Technology), Kelly Peng (Stanford University), Yao Lu (Physical Intelligence), Song Han

**Institutions**: Massachusetts Institute of Technology, The University of Hong Kong, Stanford University, Physical Intelligence

**Primary Area**: generative models

**Keywords**: Efficient Autoregressive Image Generation, Parallel Decoding

**Abstract**: We present Locality-aware Parallel Decoding (LPD) to accelerate autoregressive image generation. Traditional autoregressive image generation relies on next-patch prediction, a memory-bound process that leads to high latency. Existing works have tried to parallelize next-patch prediction by shifting to multi-patch prediction to accelerate the process, but only achieved limited parallelization. To achieve high parallelization while maintaining generation quality, we introduce two key techniques: (1) Flexible Parallelized Autoregressive Modeling, a novel architecture that enables arbitrary generation ordering and degrees of parallelization. It uses learnable position query tokens to guide generation at target positions while ensuring mutual visibility among concurrently generated tokens for consistent parallel decoding. (2) Locality-aware Generation Ordering, a novel schedule that forms groups to minimize intra-group dependencies and maximize contextual support, enhancing generation quality. With these designs, we reduce the generation steps from 256 to 20 (256×256 res.) and 1024 to 48 (512×512 res.) without compromising quality on the ImageNet class-conditional generation, and achieving at least 3.4× lower latency than previous parallelized autoregressive models.

---

## 222. Reasoning as Representation: Rethinking Visual Reinforcement Learning in Image Quality Assessment

**OpenReview**: [https://openreview.net/forum?id=DkHt2K1g2Y](https://openreview.net/forum?id=DkHt2K1g2Y)

**Authors**: Shijie Zhao (ByteDance Inc.), Xuanyu Zhang (Peking University), Weiqi Li (Peking University), Junlin Li (ByteDance Inc.), Li zhang (Bytedance Inc.), Tianfan Xue (The Chinese University of Hong Kong), Jian Zhang (Peking University)

**Institutions**: ByteDance Inc., Peking University, Bytedance Inc., The Chinese University of Hong Kong

**Primary Area**: reinforcement learning

**Keywords**: Image Quality Assessment, Low Level Vision, Multimodal Large Language Model

**Abstract**: Reasoning-based image quality assessment (IQA) models trained through reinforcement learning (RL) exhibit exceptional generalization, yet the underlying mechanisms and critical factors driving this capability remain underexplored in current research. Moreover, despite their superior performance, these models incur inference energy usage and latency orders of magnitude higher than their earlier counterparts, restricting their deployment in specific scenarios. Through extensive experiments, this paper verifies and elaborates that through RL training, MLLMs leverage their reasoning capability to convert redundant visual representations into compact, cross-domain aligned text representations. This conversion is precisely the source of the generalization exhibited by these reasoning-based IQA models. Building on this fundamental insight, we propose a novel algorithm, RALI, which employs contrastive learning to directly align images with these generalizable text representations learned by RL. This approach eliminates the reliance on reasoning processes and even obviates the need to load an LLM. For the quality scoring task, this framework achieves generalization performance comparable to reasoning-based models while requiring less than 5% of their model parameters and inference time.

---

## 223. Half-order Fine-Tuning for Diffusion Model: A Recursive Likelihood Ratio Optimizer

**OpenReview**: [https://openreview.net/forum?id=AZ6lqcvHLX](https://openreview.net/forum?id=AZ6lqcvHLX)

**Authors**: Tao Ren (Peking University), Zishi Zhang (Peking University), Jinyang Jiang (Peking University), Zehao Li (Peking University), Shentao Qin (Tsinghua University, Tsinghua University), Yi Zheng (Peking University), Guanghao Li (Tsinghua University, Tsinghua University), Qianyou Sun (Peking University), Yan Li, Jiafeng Liang (Harbin Institute of Technology), Xinping Li (Peking University), Yijie Peng (Peking University)

**Institutions**: Peking University, Tsinghua University, Tsinghua University, Harbin Institute of Technology

**Primary Area**: generative models

**Keywords**: perturbation-based gradient estimation, diffusion model, post-training

**Abstract**: The probabilistic diffusion model (DM), generating content by inferencing through a recursive chain structure, has emerged as a powerful framework for visual generation. After pre-training on enormous data, the model needs to be properly aligned to meet requirements for downstream applications. How to efficiently align the foundation DM is a crucial task. Contemporary methods are either based on Reinforcement Learning (RL) or truncated Backpropagation (BP). However, RL and truncated BP suffer from low sample efficiency and biased gradient estimation, respectively, resulting in limited improvement or, even worse, complete training failure. To overcome the challenges, we propose the Recursive Likelihood Ratio (RLR) optimizer, a Half-Order (HO) fine-tuning paradigm for DM. The HO gradient estimator enables the computation graph rearrangement within the recursive diffusive chain, making the RLR's gradient estimator **an unbiased one with lower variance** than other methods. We theoretically investigate the bias, variance, and convergence of our method. Extensive experiments are conducted on image and video generation to validate the superiority of the RLR. Furthermore, we propose a novel prompt technique that is natural for the RLR to achieve a synergistic effect. The implementation is available at https://github.com/RTkenny/RLR-Optimizer.

---
