# Speculative Decoding Survey (add paper title)

An overview of speculative decoding and its various inference methods categorized into two implementation groups: model-centric implementations and draft-centric implementations.

Survey Paper: [arXiv](https://christophera.github.io/simplest-github-page/)


## Papers

### 2018
* **Blockwise Parallel Decoding for Deep Autoregressive Models** by _Mitchell Stern, Noam Shazeer, Jakob Uszkoreit_ [Nov] ([pdf](https://arxiv.org/pdf/1811.03115))

### 2019
* **The Curious Case of Neural Text Degeneration** by _Ari Holtzman, Jan Buys, et al._ [Apr] ([pdf](https://arxiv.org/pdf/1904.09751))
* **Fast Transformer Decoding: One Write-Head is All You Need** by _Noam Shazeer_ [Nov] ([pdf](https://arxiv.org/pdf/1911.02150))

### 2020
* **Language Models are Few-Shot Learners** by _Tom B. Brown, Benjamin Mann, et al._ [May] ([pdf](https://arxiv.org/pdf/2005.14165))

### 2022
* **LaMDA: Language Models for Dialog Applications** by _Romal Thoppilan, Daniel De Freitas, et al._ [Jan] ([pdf](https://arxiv.org/pdf/2201.08239))
* **Fast Inference from Transformers via Speculative Decoding** by _Yaniv Leviathan, Matan Kalman, Yossi Matias_ [Nov] ([pdf](https://arxiv.org/pdf/2211.17192))

### 2023
* **Challenges and Applications of Large Language Models** by _Jean Kaddour, Joshua Harris, et al._ [Jul] ([pdf](https://arxiv.org/pdf/2307.10169))
* **Online Speculative Decoding** by _Xiaoxuan Liu, Lanxiang Hu, et al._ [Oct] ([pdf](https://arxiv.org/pdf/2310.07177))
* **SLiM: Speculative Decoding with Hypothesis Reduction** by _Chi-Heng Lin, Shikhar Tuli, et al._ [Dec] ([pdf](https://openreview.net/pdf?id=aPOFpNWwzl))
* **Lookahead: An Inference Acceleration Framework for Large Language Model with Lossless Generation Accuracy** by _Yao Zhao, Zhitian Xie, et al._ [Dec] ([pdf](https://arxiv.org/pdf/2312.12728))

### 2024
* **Unlocking Efficiency in Large Language Model Inference: A Comprehensive Survey of Speculative Decoding** by _Heming Xia, Zhe Yang, et al._ [Jan]  ([pdf](https://arxiv.org/pdf/2401.07851))
* **Medusa: Simple LLM Inference Acceleration Framework with Multiple Decoding Heads** by _Tianle Cai, Yuhong Li, et al._ [Jan] ([pdf](https://arxiv.org/pdf/2401.10774))
* **EAGLE: Speculative Sampling Requires Rethinking Feature Uncertainty** by _Yuhui Li, Fangyun Wei, et al._ [Jan] ([pdf](https://arxiv.org/pdf/2401.15077))
* **Hydra: Sequentially-Dependent Draft Heads for Medusa Decoding** by _Zachary Ankner, Rishab Parthasarathy, et al._ [Feb] ([pdf](https://arxiv.org/pdf/2402.05109))
* **A Thorough Examination of Decoding Methods in the Era of LLMs** by _Chufan Shi, Haoran Yang, et al._ [Feb] ([pdf](https://arxiv.org/pdf/2402.06925))
* **ProPD: Dynamic Token Tree Pruning and Generation for LLM Parallel Decoding** by _Shuzhang Zhong, Zebin Yang, et al._ [Feb] ([pdf](https://arxiv.org/pdf/2402.13485))
* **Recursive Speculative Decoding: Accelerating LLM Inference via Sampling Without Replacement** by _Wonseok Jeon, Mukul Gagrani, et al._ [Feb] ([pdf](https://arxiv.org/pdf/2402.14160))
* **Chimera: A Lossless Decoding Method for Accelerating Large Language Models Inference by Fusing all Tokens** by _Ziqian Zeng, Jiahong Yu, et al._ [Feb] ([pdf](https://arxiv.org/pdf/2402.15758))
* **Direct Alignment of Draft Model for Speculative Decoding with Chat-Fine-Tuned LLMs** by _Raghavv Goel, Mukul Gagrani, et al._ [Feb] ([pdf](https://arxiv.org/pdf/2403.00858))
* **Exploring and Improving Drafts in Blockwise Parallel Decoding** by _Taehyeon Kim, Ananda Theertha Suresh, et al._ [Apr] ([pdf](https://arxiv.org/pdf/2404.09221))
* **TriForce: Lossless Acceleration of Long Sequence Generation with Hierarchical Speculative Decoding** by _Hanshi Sun, Zhuoming Chen, et al._ [Apr] ([pdf](https://arxiv.org/pdf/2404.11912))
* **BASS: Batched Attention-optimized Speculative Sampling** by _Haifeng Qian, Sujan Kumar Gonugondla, et al._ [Apr] ([pdf](https://arxiv.org/pdf/2404.15778))
* **LayerSkip: Enabling Early Exit Inference and Self-Speculative Decoding** by _Mostafa Elhoushi, Akshat Shrivastava, et al._ [Apr] ([pdf](https://arxiv.org/pdf/2404.16710))
* **QServe: W4A8KV4 Quantization and System Co-design for Efficient LLM Serving** by _Yujun Lin, Haotian Tang, et al._ [May] ([pdf](https://arxiv.org/pdf/2405.04532))
* **Aladdin: Joint Placement and Scaling for SLO-Aware LLM Serving** by _Chengyi Nie, Rodrigo Fonseca, Zhenhua Liu_ [May] ([pdf](https://arxiv.org/pdf/2405.06856))
* **EMS-SD: Efficient Multi-sample Speculative Decoding for Accelerating Large Language Models** by _Yunsheng Ni, Chuanjian Liu, et al._ [May] ([pdf](https://arxiv.org/pdf/2405.07542))
* **Hardware-Aware Parallel Prompt Decoding for Memory-Efficient Acceleration of LLM Inference** by _Hao Mark Chen, Wayne Luk, et al._ [May] ([pdf](https://arxiv.org/pdf/2405.18628))
* **SpecDec++: Boosting Speculative Decoding via Adaptive Candidate Lengths** by _Kaixuan Huang, Xudong Guo, Mengdi Wang_ [May] ([pdf](https://arxiv.org/pdf/2405.19715))
* **SpecExec: Massively Parallel Speculative Decoding for Interactive LLM Inference on Consumer Devices** by _Ruslan Svirschevski, Avner May, et al._ [Jun] ([pdf](https://arxiv.org/pdf/2406.02532))
* **Speculative Decoding via Early-exiting for Faster LLM Inference with Thompson Sampling Control Mechanism** by _Jiahao Liu, Qifan Wang, et al._ [Jun] ([pdf](https://arxiv.org/pdf/2406.03853))
* **Optimizing Speculative Decoding for Serving Large Language Models Using Goodput** by _Xiaoxuan Liu, Cade Daniel, et al._ [Jun] ([pdf](https://arxiv.org/pdf/2406.14066))
* **EAGLE-2: Faster Inference of Language Models with Dynamic Draft Trees** by _Yuhui Li, Fangyun Wei, et al._ [Jun] ([pdf](https://arxiv.org/pdf/2406.16858))
* **OPT-Tree: Speculative Decoding with Adaptive Draft Tree Structure** by _Jikai Wang, Yi Su, et al._ [Jun] ([pdf](https://arxiv.org/pdf/2406.17276))
* * **S2D: Sorted Speculative Decoding For More Efficient Deployment of Nested Large Language Models** by _Parsa Kavehzadeh, Mohammadreza Pourreza, et al._ [Jul] ([pdf](https://arxiv.org/pdf/2407.01955))
* **LazyLLM: Dynamic Token Pruning for Efficient Long Context LLM Inference** by _Qichen Fu, Minsik Cho, et al._ [Jul] ([pdf](https://arxiv.org/pdf/2407.14057))
* **Graph-Structured Speculative Decoding** by _Zhuocheng Gong, Jiahao Liu, et al._ [Jul] ([pdf](https://arxiv.org/pdf/2407.16207))
* **MagicDec: Breaking the Latency-Throughput Tradeoff for Long Context Generation with Speculative Decoding** by _Jian Chen, Vashisth Tiwari, et al._ [Aug] ([pdf](https://arxiv.org/pdf/2408.11049))
* **Learning Harmonized Representations for Speculative Sampling** by _Lefan Zhang, Xiaodan Wang, et al._ [Aug] ([pdf](https://arxiv.org/pdf/2408.15766))
