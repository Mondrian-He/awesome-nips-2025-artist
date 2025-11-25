# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 28 of 130

## 目录 (Table of Contents)

1. [How Does Sequence Modeling Architecture Influence Base Capabilities of Pre-trained Language Models? Exploring Key Architecture Design Principles to Avoid Base Capabilities Degradation](#How-Does-Sequence-Modeling-Architecture-Influence-Base-Capabilities-of-Pre-trained-Language-Models-Exploring-Key-Architecture-Design-Principles-to-Avoid-Base-Capabilities-Degradation)
2. [Anomaly Detection by an Ensemble of  Random Pairs of Hyperspheres](#Anomaly-Detection-by-an-Ensemble-of-Random-Pairs-of-Hyperspheres)
3. [Generalization Bound of Gradient Flow through Training Trajectory and Data-dependent Kernel](#Generalization-Bound-of-Gradient-Flow-through-Training-Trajectory-and-Data-dependent-Kernel)
4. [Optimism Without Regularization: Constant Regret in Zero-Sum Games](#Optimism-Without-Regularization-Constant-Regret-in-Zero-Sum-Games)
5. [Enhancing Zero-Shot Black-Box Optimization via Pretrained Models with Efficient Population Modeling, Interaction, and Stable Gradient Approximation](#Enhancing-Zero-Shot-Black-Box-Optimization-via-Pretrained-Models-with-Efficient-Population-Modeling-Interaction-and-Stable-Gradient-Approximation)
6. [AutoSciDACT: Automated Scientific Discovery through Contrastive Embedding and Hypothesis Testing](#AutoSciDACT-Automated-Scientific-Discovery-through-Contrastive-Embedding-and-Hypothesis-Testing)
7. [A Single-Loop Gradient Algorithm for Pessimistic Bilevel Optimization via Smooth Approximation](#A-Single-Loop-Gradient-Algorithm-for-Pessimistic-Bilevel-Optimization-via-Smooth-Approximation)
8. [Dimensional Collapse in VQVAEs: Evidence and Remedies](#Dimensional-Collapse-in-VQVAEs-Evidence-and-Remedies)
9. [SAFEPATH: Preventing Harmful Reasoning in Chain-of-Thought via Early Alignment](#SAFEPATH-Preventing-Harmful-Reasoning-in-Chain-of-Thought-via-Early-Alignment)
10. [Zero-shot World Models via Search in Memory](#Zero-shot-World-Models-via-Search-in-Memory)
11. [Efficient Bayesian Experiment Design with Equivariant Networks](#Efficient-Bayesian-Experiment-Design-with-Equivariant-Networks)
12. [Boundary-to-Region Supervision for Offline Safe Reinforcement Learning](#Boundary-to-Region-Supervision-for-Offline-Safe-Reinforcement-Learning)
13. [Tight High-Probability Bounds for Nonconvex Heavy-Tailed Scenario under Weaker Assumptions](#Tight-High-Probability-Bounds-for-Nonconvex-Heavy-Tailed-Scenario-under-Weaker-Assumptions)
14. [Intermediate Domain Alignment and Morphology Analogy for Patent-Product Image Retrieval](#Intermediate-Domain-Alignment-and-Morphology-Analogy-for-Patent-Product-Image-Retrieval)
15. [TrackingWorld: World-centric Monocular 3D Tracking of Almost All Pixels](#TrackingWorld-World-centric-Monocular-3D-Tracking-of-Almost-All-Pixels)
16. [Calibrating Translation Decoding with Quality Estimation on LLMs](#Calibrating-Translation-Decoding-with-Quality-Estimation-on-LLMs)
17. [Distributional Adversarial Attacks and Training in Deep Hedging](#Distributional-Adversarial-Attacks-and-Training-in-Deep-Hedging)
18. [AlignVLM: Bridging Vision and Language Latent Spaces for Multimodal Document Understanding](#AlignVLM-Bridging-Vision-and-Language-Latent-Spaces-for-Multimodal-Document-Understanding)
19. [MemSim: A Bayesian Simulator for Evaluating Memory of LLM-based Personal Assistants](#MemSim-A-Bayesian-Simulator-for-Evaluating-Memory-of-LLM-based-Personal-Assistants)
20. [Learning to Clean: Reinforcement Learning for Noisy Label Correction](#Learning-to-Clean-Reinforcement-Learning-for-Noisy-Label-Correction)
21. [TiRex: Zero-Shot Forecasting Across Long and Short Horizons with Enhanced In-Context Learning](#TiRex-Zero-Shot-Forecasting-Across-Long-and-Short-Horizons-with-Enhanced-In-Context-Learning)
22. [Last-Iterate Convergence of Smooth Regret Matching$^+$ Variants in Learning Nash Equilibria](#Last-Iterate-Convergence-of-Smooth-Regret-Matching-Variants-in-Learning-Nash-Equilibria)
23. [Bilevel ZOFO: Efficient LLM Fine-Tuning and Meta-Training](#Bilevel-ZOFO-Efficient-LLM-Fine-Tuning-and-Meta-Training)
24. [Flex-Judge: Text-Only Reasoning Unleashes Zero-Shot Multimodal Evaluators](#Flex-Judge-Text-Only-Reasoning-Unleashes-Zero-Shot-Multimodal-Evaluators)
25. [LangHOPS: Language Grounded Hierarchical Open-Vocabulary Part Segmentation](#LangHOPS-Language-Grounded-Hierarchical-Open-Vocabulary-Part-Segmentation)
26. [Generalization Guarantees for Learning Score-Based Branch-and-Cut Policies in Integer Programming](#Generalization-Guarantees-for-Learning-Score-Based-Branch-and-Cut-Policies-in-Integer-Programming)
27. [CG-SSL: Concept-Guided Self-Supervised Learning](#CG-SSL-Concept-Guided-Self-Supervised-Learning)
28. [SimulMEGA: MoE Routers are Advanced Policy Makers for Simultaneous Speech Translation](#SimulMEGA-MoE-Routers-are-Advanced-Policy-Makers-for-Simultaneous-Speech-Translation)
29. [Size-adaptive Hypothesis Testing for Fairness](#Size-adaptive-Hypothesis-Testing-for-Fairness)
30. [Towards Irreversible Attack: Fooling Scene Text Recognition via Multi-Population Coevolution Search](#Towards-Irreversible-Attack-Fooling-Scene-Text-Recognition-via-Multi-Population-Coevolution-Search)
31. [The Logical Expressiveness of Temporal GNNs via Two-Dimensional Product Logics](#The-Logical-Expressiveness-of-Temporal-GNNs-via-Two-Dimensional-Product-Logics)
32. [On the Relation between Rectified Flows and Optimal Transport](#On-the-Relation-between-Rectified-Flows-and-Optimal-Transport)
33. [A Plug-and-Play Query Synthesis Active Learning Framework for Neural PDE Solvers](#A-Plug-and-Play-Query-Synthesis-Active-Learning-Framework-for-Neural-PDE-Solvers)
34. [Improving Data Efficiency for LLM Reinforcement Fine-tuning Through Difficulty-targeted Online Data Selection and Rollout Replay](#Improving-Data-Efficiency-for-LLM-Reinforcement-Fine-tuning-Through-Difficulty-targeted-Online-Data-Selection-and-Rollout-Replay)
35. [A*-Thought: Efficient Reasoning via Bidirectional Compression for Low-Resource Settings](#A-Thought-Efficient-Reasoning-via-Bidirectional-Compression-for-Low-Resource-Settings)
36. [Attack via Overfitting: 10-shot Benign Fine-tuning to Jailbreak LLMs](#Attack-via-Overfitting-10-shot-Benign-Fine-tuning-to-Jailbreak-LLMs)
37. [A Generalist Intracortical Motor Decoder](#A-Generalist-Intracortical-Motor-Decoder)
38. [InstructRestore: Region-Customized Image Restoration with Human Instructions](#InstructRestore-Region-Customized-Image-Restoration-with-Human-Instructions)
39. [UFT: Unifying Supervised and Reinforcement Fine-Tuning](#UFT-Unifying-Supervised-and-Reinforcement-Fine-Tuning)
40. [A faster training algorithm for regression trees with linear leaves, and an analysis of its complexity](#A-faster-training-algorithm-for-regression-trees-with-linear-leaves-and-an-analysis-of-its-complexity)
41. [ReMA: Learning to Meta-Think for LLMs with Multi-agent Reinforcement Learning](#ReMA-Learning-to-Meta-Think-for-LLMs-with-Multi-agent-Reinforcement-Learning)

---


## How Does Sequence Modeling Architecture Influence Base Capabilities of Pre-trained Language Models? Exploring Key Architecture Design Principles to Avoid Base Capabilities Degradation

### Images

![26ef57110168e4540c28dbc4c31bdb66644401611f78a9e2d1170ae20e99ad6c.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/26ef57110168e4540c28dbc4c31bdb66644401611f78a9e2d1170ae20e99ad6c.jpg)

![391cc748a4f3fef5af87ec64dcc8091cadb8bf1c1ea92692dbf81470b578dab9.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/391cc748a4f3fef5af87ec64dcc8091cadb8bf1c1ea92692dbf81470b578dab9.jpg)

![6eb8ec98381dfe73c087735813c331fba7f14bbf21357e50dc8899f5e82d224b.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/6eb8ec98381dfe73c087735813c331fba7f14bbf21357e50dc8899f5e82d224b.jpg)

![8fc22128a1e87760e99d2886fe5578f252b59666d6dfa94a2cb15ec9ab05bc60.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/8fc22128a1e87760e99d2886fe5578f252b59666d6dfa94a2cb15ec9ab05bc60.jpg)

![91ad618b08af1615ee47a5021342913194ede19aa3e89b0ec57ff46165ccb51c.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/91ad618b08af1615ee47a5021342913194ede19aa3e89b0ec57ff46165ccb51c.jpg)

![925772533d02db60b70c7650144ad77eead7ac615f50e81e6f913b45ab85525a.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/925772533d02db60b70c7650144ad77eead7ac615f50e81e6f913b45ab85525a.jpg)

![97aee775af8147a5ab43d0faa2c94e760e4abe1c596415ed09641d0633e7f279.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/97aee775af8147a5ab43d0faa2c94e760e4abe1c596415ed09641d0633e7f279.jpg)

![98146edd4fe7523e3fa29064015eb82f92f100e51775a746c64c0cdc8765b239.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/98146edd4fe7523e3fa29064015eb82f92f100e51775a746c64c0cdc8765b239.jpg)

![a032b43915fdd283d4f402cef50ec7bab98597d5f0a75f9d06aabbf66a63229d.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/a032b43915fdd283d4f402cef50ec7bab98597d5f0a75f9d06aabbf66a63229d.jpg)

![a1bb45ba875a38636a75cb4d913814f780cd2b5149506fa47207900d4fb96cbb.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/a1bb45ba875a38636a75cb4d913814f780cd2b5149506fa47207900d4fb96cbb.jpg)

![a3365777f16816ee9ad6c922338a3976889e16161c0ccc7c8dc087a7761aad27.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/a3365777f16816ee9ad6c922338a3976889e16161c0ccc7c8dc087a7761aad27.jpg)

![a88ce1ddaaeba0b30d7f7825c9279b69c0c64dbfa6a38e394f3dd4ecc961f07a.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/a88ce1ddaaeba0b30d7f7825c9279b69c0c64dbfa6a38e394f3dd4ecc961f07a.jpg)

![affeaded34a53f68995c38ccc682b65b6be8de4e6e4fc4e568515d86c4d37cf3.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/affeaded34a53f68995c38ccc682b65b6be8de4e6e4fc4e568515d86c4d37cf3.jpg)

![c0e99db6f5360bb92d3f3a31adf35d718eae17fcef2f0616fb7f84bcc9f47260.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/c0e99db6f5360bb92d3f3a31adf35d718eae17fcef2f0616fb7f84bcc9f47260.jpg)

![c5c06874abb9da6f474e4502c6d1150c87ba58ae31df68a3b95365f713010c94.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/c5c06874abb9da6f474e4502c6d1150c87ba58ae31df68a3b95365f713010c94.jpg)

![cf87fc8c7344a402bcfa95d7d3cefb3b78634b908efa99f2cfe9377edc181d21.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/images/cf87fc8c7344a402bcfa95d7d3cefb3b78634b908efa99f2cfe9377edc181d21.jpg)

### Tables

![0d5284a003eb35202fa16d62493e521290fa06f05e6fbf7ef14ab1cb2e98817a.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/tables/0d5284a003eb35202fa16d62493e521290fa06f05e6fbf7ef14ab1cb2e98817a.jpg)

![11ade95951af9c165e9eb44dd670debc7fe1dc481f90cebdd7d3f0a2871c5ae5.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/tables/11ade95951af9c165e9eb44dd670debc7fe1dc481f90cebdd7d3f0a2871c5ae5.jpg)

![15eb3174be7098a659de334d9751125264a6ac3f9fca860df551a7bd8f15738f.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/tables/15eb3174be7098a659de334d9751125264a6ac3f9fca860df551a7bd8f15738f.jpg)

![4490b92b91b5dd7190579aa8bc60e091dd78fca76073e07d890c41eda14c3bc6.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/tables/4490b92b91b5dd7190579aa8bc60e091dd78fca76073e07d890c41eda14c3bc6.jpg)

![9aac5b79fb10aa00e2ba0e4655f60a1f75df555f1f10e1511aae8c18d3d3d73f.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/tables/9aac5b79fb10aa00e2ba0e4655f60a1f75df555f1f10e1511aae8c18d3d3d73f.jpg)

![b30f15f89ed6d6c300d43608c85a1de32e8ea63a2151fa2e3a4d31664279ad91.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/tables/b30f15f89ed6d6c300d43608c85a1de32e8ea63a2151fa2e3a4d31664279ad91.jpg)

![b51156990b05dd2638434fb6825fd9c126d43791093d765124e9ca2b04b514d9.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/tables/b51156990b05dd2638434fb6825fd9c126d43791093d765124e9ca2b04b514d9.jpg)

![dedaeac83c7b25c97fb68f2c0623a1a1b9caee91ed44ad2f29a13a731ae85b36.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/tables/dedaeac83c7b25c97fb68f2c0623a1a1b9caee91ed44ad2f29a13a731ae85b36.jpg)

![f99b311d4caacbc82e8cbbbc8b2418bd015b12d4958a1dc235a9f21f7fdcdc3b.jpg](../nips_results/1126_MINT-CoT_%20Enabling%20Interleaved%20Visual%20Tokens%20in%20Mathematical%20Chain-of-Thought%20Reasoning/tables/f99b311d4caacbc82e8cbbbc8b2418bd015b12d4958a1dc235a9f21f7fdcdc3b.jpg)

## How Does Sequence Modeling Architecture Influence Base Capabilities of Pre-trained Language Models? Exploring Key Architecture Design Principles to Avoid Base Capabilities Degradation


### Images

![2a675077e80e733792dc49a4fcba6385681946a3381d60bd51edcbdf5a387524.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/images/2a675077e80e733792dc49a4fcba6385681946a3381d60bd51edcbdf5a387524.jpg)

![4b50c664ddc3ed2c15f601228da992725860d7507c9f0cd94478c4795e776e9a.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/images/4b50c664ddc3ed2c15f601228da992725860d7507c9f0cd94478c4795e776e9a.jpg)

![626618269d6ddf0aa6ac59c8479244be4278765b0916ff3db5bb1765f2b34678.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/images/626618269d6ddf0aa6ac59c8479244be4278765b0916ff3db5bb1765f2b34678.jpg)

![647d6c571ba5d057d95cdf43df7e3a359d46286088ec0d282e8a670aec250b89.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/images/647d6c571ba5d057d95cdf43df7e3a359d46286088ec0d282e8a670aec250b89.jpg)

![6afb5e33ed6970ec9412465f5980a095f7631a73758f5e17b88569e15b99dde9.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/images/6afb5e33ed6970ec9412465f5980a095f7631a73758f5e17b88569e15b99dde9.jpg)

![8a001da0ee757f7d21250de4691d793d955ada4617974b5b4e9e2ecdda78107c.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/images/8a001da0ee757f7d21250de4691d793d955ada4617974b5b4e9e2ecdda78107c.jpg)

![eca8e73c7b31aed61d08f576ab1d5c507501ede8cefc8ad5d5ac1cab4cdeb432.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/images/eca8e73c7b31aed61d08f576ab1d5c507501ede8cefc8ad5d5ac1cab4cdeb432.jpg)

![f6e4871722319edea3cfeca38565edc416ba05983db0faf910ec2682b4864c50.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/images/f6e4871722319edea3cfeca38565edc416ba05983db0faf910ec2682b4864c50.jpg)

![fd8be004d5e724a945978e5103940f8e25ff88a03d87a7800768d03a70500d86.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/images/fd8be004d5e724a945978e5103940f8e25ff88a03d87a7800768d03a70500d86.jpg)

### Tables

![4e4422789c064f325aecd88c7be9704642b25d60cb0d77e07c0d3a66dc30cb7d.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/tables/4e4422789c064f325aecd88c7be9704642b25d60cb0d77e07c0d3a66dc30cb7d.jpg)

![cc1c44b05753d1fafd9b8a95a4d5ec77cef665690d92339700a8874a1e3ee7ba.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/tables/cc1c44b05753d1fafd9b8a95a4d5ec77cef665690d92339700a8874a1e3ee7ba.jpg)

![eb424e624da882a5c5058d0dbd379ffcd6f4d542870dcfb035387bc9a144437f.jpg](../nips_results/1127_How%20Does%20Sequence%20Modeling%20Architecture%20Influence%20Base%20Capabilities%20of%20Pre-trained%20Language%20Models_%20/tables/eb424e624da882a5c5058d0dbd379ffcd6f4d542870dcfb035387bc9a144437f.jpg)

## Anomaly Detection by an Ensemble of  Random Pairs of Hyperspheres


### Images

![26300824336b6df543a442445495e62b82432384e84c67e9f91a21da9cea0edf.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/images/26300824336b6df543a442445495e62b82432384e84c67e9f91a21da9cea0edf.jpg)

![9b3b8cc462b37d52fca76e7f6fa10dd07aef024afe11144f6b85109c85efbcb7.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/images/9b3b8cc462b37d52fca76e7f6fa10dd07aef024afe11144f6b85109c85efbcb7.jpg)

![ac7966cdd3fe8bd14cf1550d3fa031ea8415e620af4cbc118b32f0346d44c538.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/images/ac7966cdd3fe8bd14cf1550d3fa031ea8415e620af4cbc118b32f0346d44c538.jpg)

![bcfd30d3ee1e961c55c6cd1bcabc10ab584cace0ad7c7c2dd5b2bf52ab5f5958.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/images/bcfd30d3ee1e961c55c6cd1bcabc10ab584cace0ad7c7c2dd5b2bf52ab5f5958.jpg)

![c19b0e13dae06d499b27f9a14a63739674d26c285b08513645c58111e0a1335f.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/images/c19b0e13dae06d499b27f9a14a63739674d26c285b08513645c58111e0a1335f.jpg)

![fb9783e22e2ad2df45815c2f46235a93ce661f5d0980a68e7513a6d6640c8ff9.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/images/fb9783e22e2ad2df45815c2f46235a93ce661f5d0980a68e7513a6d6640c8ff9.jpg)

### Tables

![05844ce22a864f5f0b7dbbe7ed33e2ed99c8e38ff365ddcbb583eba353a3663f.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/05844ce22a864f5f0b7dbbe7ed33e2ed99c8e38ff365ddcbb583eba353a3663f.jpg)

![2ab394cb956bf2e1f4fedbdf3796e2a7e732536b7267f3a0c7a618ab4a4dd33b.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/2ab394cb956bf2e1f4fedbdf3796e2a7e732536b7267f3a0c7a618ab4a4dd33b.jpg)

![512e8aa4182c25282900d342a175c0965261c031ecc222e8d73360157225c8ce.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/512e8aa4182c25282900d342a175c0965261c031ecc222e8d73360157225c8ce.jpg)

![5a66250640907c70c37a07c9f5e3733d438922fd3c72c92a4ed3c98288880f1d.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/5a66250640907c70c37a07c9f5e3733d438922fd3c72c92a4ed3c98288880f1d.jpg)

![5fb812426921d49fa5c13d449850fd8515fc4184755483b15240fb34be6ee72f.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/5fb812426921d49fa5c13d449850fd8515fc4184755483b15240fb34be6ee72f.jpg)

![6eda596ba4d17155db1e297c56464218f42f26ccb7a210ee3d7c2070f0c9ab8b.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/6eda596ba4d17155db1e297c56464218f42f26ccb7a210ee3d7c2070f0c9ab8b.jpg)

![7f965f83512d4670ff5481f6194c60f423999aa8902ce17e1be7045c0db1629b.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/7f965f83512d4670ff5481f6194c60f423999aa8902ce17e1be7045c0db1629b.jpg)

![946e435bd59378cd2bd381a3cd6b9af3ca99cf9c9b3297e95165569e3690def2.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/946e435bd59378cd2bd381a3cd6b9af3ca99cf9c9b3297e95165569e3690def2.jpg)

![a9f0c65e141ad765e577ea1fd4fae189a830aa495944eb76dfec32f238e44984.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/a9f0c65e141ad765e577ea1fd4fae189a830aa495944eb76dfec32f238e44984.jpg)

![c06fd1e2ca69f2a96270d21676c2edfa2a9d0f7f37cd3ae42fff38592c755a66.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/c06fd1e2ca69f2a96270d21676c2edfa2a9d0f7f37cd3ae42fff38592c755a66.jpg)

![d452996848a061fe067ccd0949535b9791dad5dcdbf7e583bc69b16c1edfce46.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/d452996848a061fe067ccd0949535b9791dad5dcdbf7e583bc69b16c1edfce46.jpg)

![f182fafd59fd27528dec8105d7921a4a8fab730f0045a1df230da78898e71730.jpg](../nips_results/1128_Anomaly%20Detection%20by%20an%20Ensemble%20of%20%20Random%20Pairs%20of%20Hyperspheres/tables/f182fafd59fd27528dec8105d7921a4a8fab730f0045a1df230da78898e71730.jpg)

## Generalization Bound of Gradient Flow through Training Trajectory and Data-dependent Kernel


### Images

![0b682580c5b65242c81fb0ddebf88431763d13c23c2872cb3c23740e44f8cbce.jpg](../nips_results/1129_Generalization%20Bound%20of%20Gradient%20Flow%20through%20Training%20Trajectory%20and%20Data-dependent%20Kernel/images/0b682580c5b65242c81fb0ddebf88431763d13c23c2872cb3c23740e44f8cbce.jpg)

![1fc9ed36ca03dce8f98a12b969031c6bedf5ff7d209eab94c6390aaddde2219a.jpg](../nips_results/1129_Generalization%20Bound%20of%20Gradient%20Flow%20through%20Training%20Trajectory%20and%20Data-dependent%20Kernel/images/1fc9ed36ca03dce8f98a12b969031c6bedf5ff7d209eab94c6390aaddde2219a.jpg)

![23847ecd2e2a051a965996aca3426118acf0a46ff0e1f441e4cab4cd8f97d856.jpg](../nips_results/1129_Generalization%20Bound%20of%20Gradient%20Flow%20through%20Training%20Trajectory%20and%20Data-dependent%20Kernel/images/23847ecd2e2a051a965996aca3426118acf0a46ff0e1f441e4cab4cd8f97d856.jpg)

![aadcb205cdb06203ee17c8a56a7bb7c836fc21e329c1bc70562310f7514ca100.jpg](../nips_results/1129_Generalization%20Bound%20of%20Gradient%20Flow%20through%20Training%20Trajectory%20and%20Data-dependent%20Kernel/images/aadcb205cdb06203ee17c8a56a7bb7c836fc21e329c1bc70562310f7514ca100.jpg)

![d0110f53ab17dec52068e0306e95d9ff7ba04596a31650bb025a9fc9a9bd0ad6.jpg](../nips_results/1129_Generalization%20Bound%20of%20Gradient%20Flow%20through%20Training%20Trajectory%20and%20Data-dependent%20Kernel/images/d0110f53ab17dec52068e0306e95d9ff7ba04596a31650bb025a9fc9a9bd0ad6.jpg)

![d1d5477fcd7641ea928d0789b2114428ae9d07a7871b9565bbe154d4fafe1061.jpg](../nips_results/1129_Generalization%20Bound%20of%20Gradient%20Flow%20through%20Training%20Trajectory%20and%20Data-dependent%20Kernel/images/d1d5477fcd7641ea928d0789b2114428ae9d07a7871b9565bbe154d4fafe1061.jpg)

### Tables

![5594455c557517544043dd02d9e9dbffa13473903535732eb3910a731de1b163.jpg](../nips_results/1129_Generalization%20Bound%20of%20Gradient%20Flow%20through%20Training%20Trajectory%20and%20Data-dependent%20Kernel/tables/5594455c557517544043dd02d9e9dbffa13473903535732eb3910a731de1b163.jpg)

## Optimism Without Regularization: Constant Regret in Zero-Sum Games


### Images

![1f5f865e8369438b317c1729d19d14e1206efc164097c5e43be89bda39e31989.jpg](../nips_results/1130_Optimism%20Without%20Regularization_%20Constant%20Regret%20in%20Zero-Sum%20Games/images/1f5f865e8369438b317c1729d19d14e1206efc164097c5e43be89bda39e31989.jpg)

![6057671d09aa6458425da355227b4be912afc3f3155b84e7f241f857070e3181.jpg](../nips_results/1130_Optimism%20Without%20Regularization_%20Constant%20Regret%20in%20Zero-Sum%20Games/images/6057671d09aa6458425da355227b4be912afc3f3155b84e7f241f857070e3181.jpg)

![6254bee4bf0fb1d7aa5fdbdf08d38f2e981b7b02ded519c5ee77f3408f1eaca7.jpg](../nips_results/1130_Optimism%20Without%20Regularization_%20Constant%20Regret%20in%20Zero-Sum%20Games/images/6254bee4bf0fb1d7aa5fdbdf08d38f2e981b7b02ded519c5ee77f3408f1eaca7.jpg)

![81fb1baa84cb67a1bb173912be419acde2e13070700eefc750b9c10529967638.jpg](../nips_results/1130_Optimism%20Without%20Regularization_%20Constant%20Regret%20in%20Zero-Sum%20Games/images/81fb1baa84cb67a1bb173912be419acde2e13070700eefc750b9c10529967638.jpg)

![b1681e4877bac4ae7c17a8cf1afe60526d2e1f95f0fac973b27e5ed0d58b1a5d.jpg](../nips_results/1130_Optimism%20Without%20Regularization_%20Constant%20Regret%20in%20Zero-Sum%20Games/images/b1681e4877bac4ae7c17a8cf1afe60526d2e1f95f0fac973b27e5ed0d58b1a5d.jpg)

![f9819c5f7592f199715f89b23eb19801795cb0eb6119ce280888889a2beba7a5.jpg](../nips_results/1130_Optimism%20Without%20Regularization_%20Constant%20Regret%20in%20Zero-Sum%20Games/images/f9819c5f7592f199715f89b23eb19801795cb0eb6119ce280888889a2beba7a5.jpg)

### Tables

![05df98b6abb9d2788018dfdcf05d825ea8e8cef794b476eba8cf18ce882f4676.jpg](../nips_results/1130_Optimism%20Without%20Regularization_%20Constant%20Regret%20in%20Zero-Sum%20Games/tables/05df98b6abb9d2788018dfdcf05d825ea8e8cef794b476eba8cf18ce882f4676.jpg)

![1e62e960221976452e89726fce4297373438d31c6f95111dcb16c6add39a05ae.jpg](../nips_results/1130_Optimism%20Without%20Regularization_%20Constant%20Regret%20in%20Zero-Sum%20Games/tables/1e62e960221976452e89726fce4297373438d31c6f95111dcb16c6add39a05ae.jpg)

![f82253d4033767697f9dbd52de958fd121cb29bdb56dc9702c025effc58287bc.jpg](../nips_results/1130_Optimism%20Without%20Regularization_%20Constant%20Regret%20in%20Zero-Sum%20Games/tables/f82253d4033767697f9dbd52de958fd121cb29bdb56dc9702c025effc58287bc.jpg)

## Enhancing Zero-Shot Black-Box Optimization via Pretrained Models with Efficient Population Modeling, Interaction, and Stable Gradient Approximation


### Images

![17bbad58446be3d0419215a680835c1ea93a96ac36371a04f28c870e49bb45f8.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/17bbad58446be3d0419215a680835c1ea93a96ac36371a04f28c870e49bb45f8.jpg)

![33c37d98ffbe834bc460aa3a209e4235597e0ce6879fcdf959a78bb1b3403946.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/33c37d98ffbe834bc460aa3a209e4235597e0ce6879fcdf959a78bb1b3403946.jpg)

![40de083dba0d27270b39bb617d56c1f00ff960d40c1fe203eeaff9813e76795d.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/40de083dba0d27270b39bb617d56c1f00ff960d40c1fe203eeaff9813e76795d.jpg)

![436beb1d7c5f137a0f989e22d7157de199efa143a7447a487a64d634bfdb8885.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/436beb1d7c5f137a0f989e22d7157de199efa143a7447a487a64d634bfdb8885.jpg)

![46b1d318ea050548b66f6e94dd3e35b237f8a680d8b56530766b62a3d5a48b1d.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/46b1d318ea050548b66f6e94dd3e35b237f8a680d8b56530766b62a3d5a48b1d.jpg)

![47dd497600e6c02bbfc4f51b02fa8dd149a5414b785ac92cfc7cd37daf111bc8.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/47dd497600e6c02bbfc4f51b02fa8dd149a5414b785ac92cfc7cd37daf111bc8.jpg)

![4a565e308e394120587394a16d3563310283cbfab78555e98867273e22d33246.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/4a565e308e394120587394a16d3563310283cbfab78555e98867273e22d33246.jpg)

![64ac238fd65ce5f88524d04d48a09ae89178be3c4275c80e6060edace6211dda.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/64ac238fd65ce5f88524d04d48a09ae89178be3c4275c80e6060edace6211dda.jpg)

![666f27bfcf64a3b0fa442f09cd22c75b46b31f241a6a83ad9884804541afef5c.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/666f27bfcf64a3b0fa442f09cd22c75b46b31f241a6a83ad9884804541afef5c.jpg)

![688192769a2e546a25819d3bc373b503c96dbaf70e00c4fcaca3d1e318eaf74a.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/688192769a2e546a25819d3bc373b503c96dbaf70e00c4fcaca3d1e318eaf74a.jpg)

![6c05e512bed7f6984bc2bd14d24a7c5413a46f44d48804e0c22795a5338bbcc1.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/6c05e512bed7f6984bc2bd14d24a7c5413a46f44d48804e0c22795a5338bbcc1.jpg)

![7a88aa40ee6e9ce52549d22b4d3b6bce8973bd8e5014bb564eced13e3b5161c8.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/7a88aa40ee6e9ce52549d22b4d3b6bce8973bd8e5014bb564eced13e3b5161c8.jpg)

![870c6dff33540a4e2768f36a22c6b5f405e0a2f90867eb3b786edb464dee76e1.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/870c6dff33540a4e2768f36a22c6b5f405e0a2f90867eb3b786edb464dee76e1.jpg)

![88d174146f0f24a95da7e839e78432314b8672c59cb9c7486b76d53e435b1766.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/88d174146f0f24a95da7e839e78432314b8672c59cb9c7486b76d53e435b1766.jpg)

![a6da0f9f323d6f7d197365dc7741c7b2e0a1cd5be543e08033a0a97e45f81daa.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/a6da0f9f323d6f7d197365dc7741c7b2e0a1cd5be543e08033a0a97e45f81daa.jpg)

![adf05d934869b8d1a308d5735f6cb0db2c8757cf1e75d43187490bdc57f44457.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/adf05d934869b8d1a308d5735f6cb0db2c8757cf1e75d43187490bdc57f44457.jpg)

![b9ccb1777318e54732ffd79b855917e9860196a79700e2345e35c49d63e486e5.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/b9ccb1777318e54732ffd79b855917e9860196a79700e2345e35c49d63e486e5.jpg)

![ca2aa4cea94f404e74bf4944741daaccd785eace34bc9fefb034f6265251e314.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/ca2aa4cea94f404e74bf4944741daaccd785eace34bc9fefb034f6265251e314.jpg)

![ece94521ca7e3eaa84b9f71de518ba6098305361bf02a5813ea6404574065221.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/images/ece94521ca7e3eaa84b9f71de518ba6098305361bf02a5813ea6404574065221.jpg)

### Tables

![9876d8f04c5242e52e5185f613bd95b29c7fb31f3d77e6b2c786365e0ae2aa34.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/tables/9876d8f04c5242e52e5185f613bd95b29c7fb31f3d77e6b2c786365e0ae2aa34.jpg)

![ad513bc9b3fd0bb405abc641369f739d0038bccf9faa651d5e61b741d3a052ca.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/tables/ad513bc9b3fd0bb405abc641369f739d0038bccf9faa651d5e61b741d3a052ca.jpg)

![c1953130a4dc3619a178aeda16de207be41d1a9796727250a0770d751c34a967.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/tables/c1953130a4dc3619a178aeda16de207be41d1a9796727250a0770d751c34a967.jpg)

![e1f3b0475372834edfaf80fa68affb8230549a202d2125e13d28e9c4f2f495af.jpg](../nips_results/1131_Enhancing%20Zero-Shot%20Black-Box%20Optimization%20via%20Pretrained%20Models%20with%20Efficient%20Population%20Modeling%2C/tables/e1f3b0475372834edfaf80fa68affb8230549a202d2125e13d28e9c4f2f495af.jpg)

## AutoSciDACT: Automated Scientific Discovery through Contrastive Embedding and Hypothesis Testing


### Images

![0b0b8d745abea39bbafa832630db4bcbf284edc1b4fc28543a614b01c86037c4.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/0b0b8d745abea39bbafa832630db4bcbf284edc1b4fc28543a614b01c86037c4.jpg)

![1f2f6b7dcbd6ade026fc891b9205e974470e7788a3028591142dc0ff017f8cf2.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/1f2f6b7dcbd6ade026fc891b9205e974470e7788a3028591142dc0ff017f8cf2.jpg)

![43684cb6ff9a60c32fb8ed0ea47cd4394c0e166cc9a336bfe85486fa967fb8ae.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/43684cb6ff9a60c32fb8ed0ea47cd4394c0e166cc9a336bfe85486fa967fb8ae.jpg)

![7131b86d4acffb50350d4d7ff767451843640f9f98aad865d01796141f7dc8b0.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/7131b86d4acffb50350d4d7ff767451843640f9f98aad865d01796141f7dc8b0.jpg)

![7a993fa9c7a5ad9f993d6ab456f1d03c3d09e0ea5f0387faf07ca178b6d094ad.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/7a993fa9c7a5ad9f993d6ab456f1d03c3d09e0ea5f0387faf07ca178b6d094ad.jpg)

![80e5747e8628b36a5724c310b8e1c3f0073fd1951c690bede662cfb73a2b5534.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/80e5747e8628b36a5724c310b8e1c3f0073fd1951c690bede662cfb73a2b5534.jpg)

![92acb600304c3e21d30841b6025454f8a05e1d6d9df28ea41fbb63de8bac4d42.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/92acb600304c3e21d30841b6025454f8a05e1d6d9df28ea41fbb63de8bac4d42.jpg)

![9d89219fbec244ca8566514fcecedbef78c862a964eacef593c0da09408a0be0.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/9d89219fbec244ca8566514fcecedbef78c862a964eacef593c0da09408a0be0.jpg)

![b0e7ab345961974438272388948dbc3bddf886a28188c2498591c94088f6b1b6.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/b0e7ab345961974438272388948dbc3bddf886a28188c2498591c94088f6b1b6.jpg)

![bddb5e917d7ceec3e74c7ed630368eb063fef4c7391f9f27974b8ff22c9f0f71.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/bddb5e917d7ceec3e74c7ed630368eb063fef4c7391f9f27974b8ff22c9f0f71.jpg)

![cdea3e2a165e992961db788d8ea5a4c6ae106b9bcba949fe958650c98e4f8776.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/cdea3e2a165e992961db788d8ea5a4c6ae106b9bcba949fe958650c98e4f8776.jpg)

![d6578751ff9e1dd299357bff9d9aeb92e607ea5c556d4a78ecd1d3c42c835467.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/d6578751ff9e1dd299357bff9d9aeb92e607ea5c556d4a78ecd1d3c42c835467.jpg)

![d89ffa8a239c234d92c219241bd2364fc6a92b8a15670e6de0f0a1069b4f5893.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/d89ffa8a239c234d92c219241bd2364fc6a92b8a15670e6de0f0a1069b4f5893.jpg)

![e354c531c5ce23df53deeb8a0ae548af62168484720a2a68cf62bb293ced21dc.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/e354c531c5ce23df53deeb8a0ae548af62168484720a2a68cf62bb293ced21dc.jpg)

![f8cf3d85c40fbb212aa07e853c4b636be8c7b3aaee7f78c1184b7bda10b58c29.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/f8cf3d85c40fbb212aa07e853c4b636be8c7b3aaee7f78c1184b7bda10b58c29.jpg)

![f9fa97f68497d4387251db1479581ca0a153e38666abfc5b0aa74baedc71b6be.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/images/f9fa97f68497d4387251db1479581ca0a153e38666abfc5b0aa74baedc71b6be.jpg)

### Tables

![230f1556e9428c094f15b74b9d209d0f031cb43b5155a1d22baa9affdcb7319e.jpg](../nips_results/1132_AutoSciDACT_%20Automated%20Scientific%20Discovery%20through%20Contrastive%20Embedding%20and%20Hypothesis%20Testing/tables/230f1556e9428c094f15b74b9d209d0f031cb43b5155a1d22baa9affdcb7319e.jpg)

## A Single-Loop Gradient Algorithm for Pessimistic Bilevel Optimization via Smooth Approximation


### Images

![1383693a79dc6612d13a4cf1d12fc1b75d649097eaa483e4eeabb4943691585e.jpg](../nips_results/1133_A%20Single-Loop%20Gradient%20Algorithm%20for%20Pessimistic%20Bilevel%20Optimization%20via%20Smooth%20Approximation/images/1383693a79dc6612d13a4cf1d12fc1b75d649097eaa483e4eeabb4943691585e.jpg)

![6800b1d8caf0288d90c173ed312a1c0dc5afd6a947fa5b8452f3226ef6b2e125.jpg](../nips_results/1133_A%20Single-Loop%20Gradient%20Algorithm%20for%20Pessimistic%20Bilevel%20Optimization%20via%20Smooth%20Approximation/images/6800b1d8caf0288d90c173ed312a1c0dc5afd6a947fa5b8452f3226ef6b2e125.jpg)

![e7ecb90c4649fbaa77e7a646d7f45214a03c1c72ee7661d06c853a5a608f5440.jpg](../nips_results/1133_A%20Single-Loop%20Gradient%20Algorithm%20for%20Pessimistic%20Bilevel%20Optimization%20via%20Smooth%20Approximation/images/e7ecb90c4649fbaa77e7a646d7f45214a03c1c72ee7661d06c853a5a608f5440.jpg)

### Tables

![57f528837226ccea71e5dd273696b8ab2a5a8b82921a97098b4bb1f458f018bb.jpg](../nips_results/1133_A%20Single-Loop%20Gradient%20Algorithm%20for%20Pessimistic%20Bilevel%20Optimization%20via%20Smooth%20Approximation/tables/57f528837226ccea71e5dd273696b8ab2a5a8b82921a97098b4bb1f458f018bb.jpg)

![62fb27f873b4c646cb05e391335f3172227c6632c9e94ade251f55ce45fce7ce.jpg](../nips_results/1133_A%20Single-Loop%20Gradient%20Algorithm%20for%20Pessimistic%20Bilevel%20Optimization%20via%20Smooth%20Approximation/tables/62fb27f873b4c646cb05e391335f3172227c6632c9e94ade251f55ce45fce7ce.jpg)

![b0086e35cd01c3b423d81163a885ba395939053315c7c1be1e174c19a0d0a8c2.jpg](../nips_results/1133_A%20Single-Loop%20Gradient%20Algorithm%20for%20Pessimistic%20Bilevel%20Optimization%20via%20Smooth%20Approximation/tables/b0086e35cd01c3b423d81163a885ba395939053315c7c1be1e174c19a0d0a8c2.jpg)

![ce76ad2051741189ac15f971d3032f8a8199b367c921a9adf114c0b4660e1692.jpg](../nips_results/1133_A%20Single-Loop%20Gradient%20Algorithm%20for%20Pessimistic%20Bilevel%20Optimization%20via%20Smooth%20Approximation/tables/ce76ad2051741189ac15f971d3032f8a8199b367c921a9adf114c0b4660e1692.jpg)

## Dimensional Collapse in VQVAEs: Evidence and Remedies


### Images

![021cd25dfd013d6d2aa79074228f5c330a25ba17e72f5759c3cee068df63bfab.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/021cd25dfd013d6d2aa79074228f5c330a25ba17e72f5759c3cee068df63bfab.jpg)

![3a0c3e80da4bd3ddecaea51bc543dc42032b6c7e363dba52859f5db945db7c17.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/3a0c3e80da4bd3ddecaea51bc543dc42032b6c7e363dba52859f5db945db7c17.jpg)

![3cb9a28f6bb3a8ba609fa4700595e290fd99270f11c31c200ce71a4bf409e922.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/3cb9a28f6bb3a8ba609fa4700595e290fd99270f11c31c200ce71a4bf409e922.jpg)

![6307dafdc2bab1ad4ff45c2c2ed6038c81ff54d6cf32f3615e17f095eba314d8.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/6307dafdc2bab1ad4ff45c2c2ed6038c81ff54d6cf32f3615e17f095eba314d8.jpg)

![65914b04f5387dcc6cb7932069c80af70427e3002f6bf239b3c49a010bfa4f5b.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/65914b04f5387dcc6cb7932069c80af70427e3002f6bf239b3c49a010bfa4f5b.jpg)

![aaeb39c08aed5916af84e194de1646c7ad3d5d6b612a3c1f998fb479b6d05de9.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/aaeb39c08aed5916af84e194de1646c7ad3d5d6b612a3c1f998fb479b6d05de9.jpg)

![ae1479e11d7a86adde9e6b10fad02a053277ba5bc6e5bc9980b450a6749539b0.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/ae1479e11d7a86adde9e6b10fad02a053277ba5bc6e5bc9980b450a6749539b0.jpg)

![c115c5ad021c4f8ea5b14adf5f806e917db2c9ead251498db8beaf927f53b10f.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/c115c5ad021c4f8ea5b14adf5f806e917db2c9ead251498db8beaf927f53b10f.jpg)

![c5d68f6e81fdf15c6ebd457fb99e14adf650e4b10e589af6d1fdafb105c778ac.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/c5d68f6e81fdf15c6ebd457fb99e14adf650e4b10e589af6d1fdafb105c778ac.jpg)

![d236975ea3b3c7a5a84cfc405aafd62e1a09d64154b20ee4857606101d57d2df.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/d236975ea3b3c7a5a84cfc405aafd62e1a09d64154b20ee4857606101d57d2df.jpg)

![ddb70c3f529dabd1655ac588c6abfed184a67f4f386dd0e467a026e54de05839.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/ddb70c3f529dabd1655ac588c6abfed184a67f4f386dd0e467a026e54de05839.jpg)

![fa4b7e2361e1a30bda1117e53814367a37d4b3296211bded0e16f2a4fda36a8c.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/fa4b7e2361e1a30bda1117e53814367a37d4b3296211bded0e16f2a4fda36a8c.jpg)

![fd415701ec04652bc27d851d75075bc8608ca3b611384e6e955e76e589d1c930.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/images/fd415701ec04652bc27d851d75075bc8608ca3b611384e6e955e76e589d1c930.jpg)

### Tables

![0d83d8b353b7d5e3215c14a372eaaafb191d2700a7354e2060d9d68f422a5a79.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/tables/0d83d8b353b7d5e3215c14a372eaaafb191d2700a7354e2060d9d68f422a5a79.jpg)

![36c8605f43d485cb8e36e4d4413609115da70a5cdf8d0660c37b8d87b9f1766d.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/tables/36c8605f43d485cb8e36e4d4413609115da70a5cdf8d0660c37b8d87b9f1766d.jpg)

![3b786ecd4a1f6ead31e779ca3a4d21c7a8ce755f87bdaff91579e07a8f7c50c6.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/tables/3b786ecd4a1f6ead31e779ca3a4d21c7a8ce755f87bdaff91579e07a8f7c50c6.jpg)

![4019e98d9e5a8323258fb1d5ecb5791fddaf3092dc5cd0928981eae5c74d4da9.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/tables/4019e98d9e5a8323258fb1d5ecb5791fddaf3092dc5cd0928981eae5c74d4da9.jpg)

![5ffb59e50f3679204811c30537ab6922e3004ed5c31a6826497d8bee9fd46dfe.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/tables/5ffb59e50f3679204811c30537ab6922e3004ed5c31a6826497d8bee9fd46dfe.jpg)

![ab008d5aa6388bb994c760193db28c57787c48ae1afd5e73435cadddaa625f02.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/tables/ab008d5aa6388bb994c760193db28c57787c48ae1afd5e73435cadddaa625f02.jpg)

![b07b9dc95e55364946185a7060a38083fce07ac68914a1d2219dd7fc0b94e7ff.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/tables/b07b9dc95e55364946185a7060a38083fce07ac68914a1d2219dd7fc0b94e7ff.jpg)

![ce1c4ba376fa5efcb9a46a263bd6560752431aed93d7aa33c790e9af755f26ee.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/tables/ce1c4ba376fa5efcb9a46a263bd6560752431aed93d7aa33c790e9af755f26ee.jpg)

![d385dac9fb36b6a690fca638d8cca723c5ba4eceffec5daef471750b2eb52be7.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/tables/d385dac9fb36b6a690fca638d8cca723c5ba4eceffec5daef471750b2eb52be7.jpg)

![f60603f092e0e4fc6ada05434e3cff92496cd7dff7ab5865a91851b36b6c2acf.jpg](../nips_results/1134_Dimensional%20Collapse%20in%20VQVAEs_%20Evidence%20and%20Remedies/tables/f60603f092e0e4fc6ada05434e3cff92496cd7dff7ab5865a91851b36b6c2acf.jpg)

## SAFEPATH: Preventing Harmful Reasoning in Chain-of-Thought via Early Alignment


### Images

![306c6022a61189a716353cc66f7b3d377d7433c0db8e0558954ad2063f73155f.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/images/306c6022a61189a716353cc66f7b3d377d7433c0db8e0558954ad2063f73155f.jpg)

![381040bcf0b3bc97c24a23cf6c0df12e7d9ac70d26d1ff8f19278fc727c4e1dd.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/images/381040bcf0b3bc97c24a23cf6c0df12e7d9ac70d26d1ff8f19278fc727c4e1dd.jpg)

![46de3742b250f7d1352192a5ac7f459d370e048eb104688ab1878fc742e20695.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/images/46de3742b250f7d1352192a5ac7f459d370e048eb104688ab1878fc742e20695.jpg)

![7e2f3632ed23e28044d6570b1cb3a62fd8c1cbf2d37c042592f8e6b734caf10e.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/images/7e2f3632ed23e28044d6570b1cb3a62fd8c1cbf2d37c042592f8e6b734caf10e.jpg)

![9533e91caa615af447d5472793a63984b4f771208ede0493328421df4256acf3.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/images/9533e91caa615af447d5472793a63984b4f771208ede0493328421df4256acf3.jpg)

![b43d56acaad6010ed922f78389a589a2edd5475b23de13c4f9f91d01c66f9d91.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/images/b43d56acaad6010ed922f78389a589a2edd5475b23de13c4f9f91d01c66f9d91.jpg)

![d05bb5fe10642f6f14e76da10bae661f234c4c2ae1d495ebcce1bb54c14a57fc.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/images/d05bb5fe10642f6f14e76da10bae661f234c4c2ae1d495ebcce1bb54c14a57fc.jpg)

### Tables

![2305e59f4593fcfa3fc763472b28de1f99946c954fec9a83efde4ad05b16fc4f.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/tables/2305e59f4593fcfa3fc763472b28de1f99946c954fec9a83efde4ad05b16fc4f.jpg)

![6fb385a00768fdab3618ae725a47f857ff3cbfb2fb036fd86322e7a8d02988f0.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/tables/6fb385a00768fdab3618ae725a47f857ff3cbfb2fb036fd86322e7a8d02988f0.jpg)

![7bfe43d811f45fda3a5d2379b43a67f847228a60aa3ddb5005092fd46413047e.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/tables/7bfe43d811f45fda3a5d2379b43a67f847228a60aa3ddb5005092fd46413047e.jpg)

![a3f4df952fc7091186884226de177fe5e8ff324f527f1848c212a9e9d347b522.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/tables/a3f4df952fc7091186884226de177fe5e8ff324f527f1848c212a9e9d347b522.jpg)

![a8eef7abd14dba499f7e093fa49d89f01206ce1bf7df1c6080387fd25b786430.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/tables/a8eef7abd14dba499f7e093fa49d89f01206ce1bf7df1c6080387fd25b786430.jpg)

![ac47ad0324ebd00cd0cff6279d95ec1112eb812cc8574440aa68dd7c6d6010f9.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/tables/ac47ad0324ebd00cd0cff6279d95ec1112eb812cc8574440aa68dd7c6d6010f9.jpg)

![d2583d62419f25e674df8f0860ff8ad661adfd553abd620962405c2ab9893e42.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/tables/d2583d62419f25e674df8f0860ff8ad661adfd553abd620962405c2ab9893e42.jpg)

![d56a306dc955a9b233bb99b686127aeb1c673eabd92c11cce4f1f1a8d49207b7.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/tables/d56a306dc955a9b233bb99b686127aeb1c673eabd92c11cce4f1f1a8d49207b7.jpg)

![fa106f063d00c29eadab4a2f6fe5e53e8b6e684f6af3c4ddb461411eea6c7563.jpg](../nips_results/1135_SAFEPATH_%20Preventing%20Harmful%20Reasoning%20in%20Chain-of-Thought%20via%20Early%20Alignment/tables/fa106f063d00c29eadab4a2f6fe5e53e8b6e684f6af3c4ddb461411eea6c7563.jpg)

## Zero-shot World Models via Search in Memory


### Images

![077291a139e9635d16a93350fa4097129a294f03f236d2e513cc76b81740dfb8.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/077291a139e9635d16a93350fa4097129a294f03f236d2e513cc76b81740dfb8.jpg)

![12e87a089fa489273adae3750c24522e1f7f3c7d133e86776f107068956dcedd.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/12e87a089fa489273adae3750c24522e1f7f3c7d133e86776f107068956dcedd.jpg)

![1d33a350c34dbbf61dca5ca8663884c8fb1ca2aa47a2f0c633b7f1d2431fce2a.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/1d33a350c34dbbf61dca5ca8663884c8fb1ca2aa47a2f0c633b7f1d2431fce2a.jpg)

![247e28a4941e6c0ac74001ad45266dcd6c7590a6bff737ec6f8b4d3a37259285.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/247e28a4941e6c0ac74001ad45266dcd6c7590a6bff737ec6f8b4d3a37259285.jpg)

![2f1c0f6cad8093f735ce2e173db26122b914660ce1aff70a6b0018a91057d146.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/2f1c0f6cad8093f735ce2e173db26122b914660ce1aff70a6b0018a91057d146.jpg)

![2f50decefee63ef3caafeceefd023bc54284dad70b5c6a3ea26ae23d33b359d3.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/2f50decefee63ef3caafeceefd023bc54284dad70b5c6a3ea26ae23d33b359d3.jpg)

![30e1117cb33537de80e2b02abe99bba2f87c25b1851aaf8bc74d5ccbe5e62909.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/30e1117cb33537de80e2b02abe99bba2f87c25b1851aaf8bc74d5ccbe5e62909.jpg)

![36d0538ce7dfc55330056a2c2d6863f14c328d23730c3dd0647e39eb4f78f0ea.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/36d0538ce7dfc55330056a2c2d6863f14c328d23730c3dd0647e39eb4f78f0ea.jpg)

![3aa3e32ba485c445316ad1d2f13a09e807351a2011e0099d5627637fcf0dd53c.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/3aa3e32ba485c445316ad1d2f13a09e807351a2011e0099d5627637fcf0dd53c.jpg)

![57953589bc1e502876c212232f1aece42838b604be367500a3dd913b66d453e9.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/57953589bc1e502876c212232f1aece42838b604be367500a3dd913b66d453e9.jpg)

![61143d595ff0193609cf14ee805412f3f444bc6391af67b32ec9c691b147c638.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/61143d595ff0193609cf14ee805412f3f444bc6391af67b32ec9c691b147c638.jpg)

![63846c76356e3b0bf4d4efdae2c7568badb80e0f1f67f10a814a7ec9a9c2c057.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/63846c76356e3b0bf4d4efdae2c7568badb80e0f1f67f10a814a7ec9a9c2c057.jpg)

![6bf4953807b629f06e283b3643845edd964e5f41da444f07b1d04f36c15e36fe.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/6bf4953807b629f06e283b3643845edd964e5f41da444f07b1d04f36c15e36fe.jpg)

![6d4fed52dda4c5e63872641a3be537c71e76010b93be5547d889edd95ec4e956.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/6d4fed52dda4c5e63872641a3be537c71e76010b93be5547d889edd95ec4e956.jpg)

![6f11035c20f4b58a3ad3d1c0add0f04f5dfc696653dd8ce718c3afdfe2fd8764.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/6f11035c20f4b58a3ad3d1c0add0f04f5dfc696653dd8ce718c3afdfe2fd8764.jpg)

![8485a53c24caf0c1c6a925c3760ed6481597ebda5abfa756d36d3239de85a458.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/8485a53c24caf0c1c6a925c3760ed6481597ebda5abfa756d36d3239de85a458.jpg)

![9a1efc1a4be83f3dc1a7eb78d6f00428bfca82525f91ccf770a8e78948830717.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/9a1efc1a4be83f3dc1a7eb78d6f00428bfca82525f91ccf770a8e78948830717.jpg)

![9ab8a1847de1214cc941f58aea15a990b45fc5561a0adf78103af5b74a389a73.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/9ab8a1847de1214cc941f58aea15a990b45fc5561a0adf78103af5b74a389a73.jpg)

![9d0526cd06d7f3d69990d9fb6eeadb3e4a3e9f408df0d482c8fa8f3a75760530.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/9d0526cd06d7f3d69990d9fb6eeadb3e4a3e9f408df0d482c8fa8f3a75760530.jpg)

![a09e7b0a053c710611278302b9d6632874ebe89ae376aff92abb35c537d5ae6d.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/a09e7b0a053c710611278302b9d6632874ebe89ae376aff92abb35c537d5ae6d.jpg)

![a15b30480fe8d12d6d7594bc26773af3d0463833cce2c2e8a6610a913781115e.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/a15b30480fe8d12d6d7594bc26773af3d0463833cce2c2e8a6610a913781115e.jpg)

![a5ec611202fec2446793a5bc6c710bab84a461982a8b2bd69a8a3e60f1147f61.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/a5ec611202fec2446793a5bc6c710bab84a461982a8b2bd69a8a3e60f1147f61.jpg)

![a6984396316bf918d4a20b926eefe5c668dc6a1ef476881181238ad9f1f6b3d4.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/a6984396316bf918d4a20b926eefe5c668dc6a1ef476881181238ad9f1f6b3d4.jpg)

![b0ec4b5faf3f7aed2ac41b9791063671200a8fc3847e915b805d1300cf95e24a.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/b0ec4b5faf3f7aed2ac41b9791063671200a8fc3847e915b805d1300cf95e24a.jpg)

![b86d7a08fd6dcbac0f16879d060211a75e4a013b99e4da64c79d7b1836c0b1a1.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/b86d7a08fd6dcbac0f16879d060211a75e4a013b99e4da64c79d7b1836c0b1a1.jpg)

![c784a21cd32fa49c08c4e3ebf10429ef3812f2aa2b0e3eba91a7a903e28f6f16.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/c784a21cd32fa49c08c4e3ebf10429ef3812f2aa2b0e3eba91a7a903e28f6f16.jpg)

![cd0dc5da271d79120cf650f80bf58d806f88537d5592f399ae7af9918d7d7af0.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/cd0dc5da271d79120cf650f80bf58d806f88537d5592f399ae7af9918d7d7af0.jpg)

![d0f76775265920170efcaa90d2c125aef3121180c1c1f18597028967ea3e9baa.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/d0f76775265920170efcaa90d2c125aef3121180c1c1f18597028967ea3e9baa.jpg)

![da7976d25c05829bb110d256ad74b449910ba319a30a4a2f9d1bf6460bea606f.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/da7976d25c05829bb110d256ad74b449910ba319a30a4a2f9d1bf6460bea606f.jpg)

![e12e35b4435419a98b7e1a3f3ed6dbda44a2cefcb733f658d65b5da055bebc73.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/e12e35b4435419a98b7e1a3f3ed6dbda44a2cefcb733f658d65b5da055bebc73.jpg)

![e50ef1b620e39c22d131aca0083ebe3cdcffaba75a3f96f36b6eed222c8920ed.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/e50ef1b620e39c22d131aca0083ebe3cdcffaba75a3f96f36b6eed222c8920ed.jpg)

![ee5722ed24d4dcda9d09ee923000d191fc4fcdaf243c23da1e073ad3c5c5176d.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/ee5722ed24d4dcda9d09ee923000d191fc4fcdaf243c23da1e073ad3c5c5176d.jpg)

![f0d24df75d1842b368b373410edd826c442ef4df6ccc00932bfda7e8023628cd.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/f0d24df75d1842b368b373410edd826c442ef4df6ccc00932bfda7e8023628cd.jpg)

![f2c783e83190699534a74621c699c156c5ecacd4db89bceedbab6b9e15fcca20.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/f2c783e83190699534a74621c699c156c5ecacd4db89bceedbab6b9e15fcca20.jpg)

![fa271c71b76d5727a9366cc81425679f4eb0c112b7e425db5cac7ae788bc0621.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/images/fa271c71b76d5727a9366cc81425679f4eb0c112b7e425db5cac7ae788bc0621.jpg)

### Tables

![649b52b44b383735198cb131ea5dd785537e2712b254c6fc34d0d30af786bc0e.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/tables/649b52b44b383735198cb131ea5dd785537e2712b254c6fc34d0d30af786bc0e.jpg)

![c2720f0142b686ab9701f07d54856feab7f42cd180f18b28a6055e5f849e6eb5.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/tables/c2720f0142b686ab9701f07d54856feab7f42cd180f18b28a6055e5f849e6eb5.jpg)

![cd3539d92b5b36d524537de5756f18a487fc5fe9adf320b71d085a93a0a07173.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/tables/cd3539d92b5b36d524537de5756f18a487fc5fe9adf320b71d085a93a0a07173.jpg)

![d7b4ad1b1a9d0eee743a34b8431a757105c20384dab0bdb39067159fc98777d3.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/tables/d7b4ad1b1a9d0eee743a34b8431a757105c20384dab0bdb39067159fc98777d3.jpg)

![e05ef7fbb52c5bcfddf74a741f124ce71fcd7dd2bc23d6d8af11821994ec1368.jpg](../nips_results/1136_Zero-shot%20World%20Models%20via%20Search%20in%20Memory/tables/e05ef7fbb52c5bcfddf74a741f124ce71fcd7dd2bc23d6d8af11821994ec1368.jpg)

## Efficient Bayesian Experiment Design with Equivariant Networks


### Images

![01f3eb61461ff52f7618724b3dadde2a6fbbf875a75b1bcdb5e3445dade9f085.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/01f3eb61461ff52f7618724b3dadde2a6fbbf875a75b1bcdb5e3445dade9f085.jpg)

![2765b2134cfcff7f6fc49d73d7cc4083e8ddafbd9f04c05335fadc2d18271e31.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/2765b2134cfcff7f6fc49d73d7cc4083e8ddafbd9f04c05335fadc2d18271e31.jpg)

![4b3a8ae7730cf75443f7c981a6e70d7add2609ff4930fc24661570f12cecfcb6.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/4b3a8ae7730cf75443f7c981a6e70d7add2609ff4930fc24661570f12cecfcb6.jpg)

![4b4c14cacb521aba7df5bff798029305a9d934f7df29374fd0c37ec21e7b72b2.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/4b4c14cacb521aba7df5bff798029305a9d934f7df29374fd0c37ec21e7b72b2.jpg)

![51a7dbb8eeda3b29695015f92760546a73d1eade6225ae4c8bb8d42c866c13f1.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/51a7dbb8eeda3b29695015f92760546a73d1eade6225ae4c8bb8d42c866c13f1.jpg)

![638d3161a8407c201497911dbdfa4e5e2dc73191150461b2b11d2585fb5c51c4.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/638d3161a8407c201497911dbdfa4e5e2dc73191150461b2b11d2585fb5c51c4.jpg)

![6d39e316a27a198a307cc89ce4bfd4667a94ebe19a5f7d21415136cf5632dd08.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/6d39e316a27a198a307cc89ce4bfd4667a94ebe19a5f7d21415136cf5632dd08.jpg)

![9064a05cd0881ee0e29d044a0a44f411e6f6396968706d3802c2d2b9f974762b.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/9064a05cd0881ee0e29d044a0a44f411e6f6396968706d3802c2d2b9f974762b.jpg)

![9c5abd470aabe7950d48c7a03d77b7f89a8d46d8593671e88bdecd46c35d6447.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/9c5abd470aabe7950d48c7a03d77b7f89a8d46d8593671e88bdecd46c35d6447.jpg)

![a07fb1e52cc31abe832dcce2205ce4d524a84e16b6926311d3021ec4af8dc651.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/a07fb1e52cc31abe832dcce2205ce4d524a84e16b6926311d3021ec4af8dc651.jpg)

![a4957a81da103ddd692e548a221fd8b8c1e2c0838f4bb8db8aa97638248aa4f7.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/a4957a81da103ddd692e548a221fd8b8c1e2c0838f4bb8db8aa97638248aa4f7.jpg)

![e837a28ecfbcff3f3cc1464fd8ac5b71f200e030971b4775889ac59ca5d5e6be.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/e837a28ecfbcff3f3cc1464fd8ac5b71f200e030971b4775889ac59ca5d5e6be.jpg)

![f3e52c835a1f058f5934984cc86b9e5f90c7ee327313b30bd2e682b6d105e2a6.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/f3e52c835a1f058f5934984cc86b9e5f90c7ee327313b30bd2e682b6d105e2a6.jpg)

![f8c6990999e40a6d9aa29fc2bf0b890969aad6e9d3b936c29bfe3f3769429680.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/images/f8c6990999e40a6d9aa29fc2bf0b890969aad6e9d3b936c29bfe3f3769429680.jpg)

### Tables

![0b3dc112c7c4ee4c393b6de3c41610ca892072d498593cb60178132a8fd6aae6.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/tables/0b3dc112c7c4ee4c393b6de3c41610ca892072d498593cb60178132a8fd6aae6.jpg)

![4b4b44fabf47f29f0b3482f991ddbfc1eecba78ac69cacd6d797c94686aa5436.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/tables/4b4b44fabf47f29f0b3482f991ddbfc1eecba78ac69cacd6d797c94686aa5436.jpg)

![6ccd6787da61ab1e33d869d5475ab970ac12af19476c05a1fc44ce3620f55875.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/tables/6ccd6787da61ab1e33d869d5475ab970ac12af19476c05a1fc44ce3620f55875.jpg)

![7ba57cb5b483076f9d1a3c3ce2ef27dc1465b07e6f0aca8644a80e0536a9da19.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/tables/7ba57cb5b483076f9d1a3c3ce2ef27dc1465b07e6f0aca8644a80e0536a9da19.jpg)

![9021c766b99b36dd82ac26d4fcf0ea313c9c81239353b76ea19bcd3af103d160.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/tables/9021c766b99b36dd82ac26d4fcf0ea313c9c81239353b76ea19bcd3af103d160.jpg)

![905d7dca3545e614f829347b00c92c315c2831f6c59f728a0f57555069eb7584.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/tables/905d7dca3545e614f829347b00c92c315c2831f6c59f728a0f57555069eb7584.jpg)

![9a133c7d321516c89347116bcf74fd258c57703532586a046c690c4d01716a3f.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/tables/9a133c7d321516c89347116bcf74fd258c57703532586a046c690c4d01716a3f.jpg)

![ce787f39795b50f921fb283b2ea40bc295591f7f6e4777828342efc8d4919326.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/tables/ce787f39795b50f921fb283b2ea40bc295591f7f6e4777828342efc8d4919326.jpg)

![d90df3880a3921f1f9a4eba6cffbd07073aaa2bf74f04458e362c774712203e5.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/tables/d90df3880a3921f1f9a4eba6cffbd07073aaa2bf74f04458e362c774712203e5.jpg)

![e9ad078bfacd09570cf3cef45a53f120ec1b5198f5633a53a536694ab3a148aa.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/tables/e9ad078bfacd09570cf3cef45a53f120ec1b5198f5633a53a536694ab3a148aa.jpg)

![fbeb7055d70f9335903119175d1f8796efac23bd0ac814bc4e0e3ab7c3a667f4.jpg](../nips_results/1137_Efficient%20Bayesian%20Experiment%20Design%20with%20Equivariant%20Networks/tables/fbeb7055d70f9335903119175d1f8796efac23bd0ac814bc4e0e3ab7c3a667f4.jpg)

## Boundary-to-Region Supervision for Offline Safe Reinforcement Learning


### Images

![2374fcca0aadb99ccb714df9a7ed004203b44870614e61d36bf32847812887c1.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/images/2374fcca0aadb99ccb714df9a7ed004203b44870614e61d36bf32847812887c1.jpg)

![347e879aa08d6a9db1d60adf7da93e6cf253d8ecf7ebfb548aaf5d9fd22688f9.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/images/347e879aa08d6a9db1d60adf7da93e6cf253d8ecf7ebfb548aaf5d9fd22688f9.jpg)

![4c3fe2401df11ba24ff422fb7d864966a80e4e715c7465d7364d62bf8b0ade75.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/images/4c3fe2401df11ba24ff422fb7d864966a80e4e715c7465d7364d62bf8b0ade75.jpg)

![5c7c2e1a3433220452493747cf1020de739c74bf2b68b5e750d3d71578d0e0ba.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/images/5c7c2e1a3433220452493747cf1020de739c74bf2b68b5e750d3d71578d0e0ba.jpg)

![60a8b1f08e768bc4745557aa7ba38be7e2e6d823c93f444ea34b65258ae5fff8.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/images/60a8b1f08e768bc4745557aa7ba38be7e2e6d823c93f444ea34b65258ae5fff8.jpg)

![b1c3c33b23d5973b576031f74f62b2adfb8f8ea7f17dc8a8f9db72d213717216.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/images/b1c3c33b23d5973b576031f74f62b2adfb8f8ea7f17dc8a8f9db72d213717216.jpg)

![ba942871f853d64b9a99201bcceeb8d8002c9f5dfe50744cbfa28e97f797f510.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/images/ba942871f853d64b9a99201bcceeb8d8002c9f5dfe50744cbfa28e97f797f510.jpg)

![cf29f9718e9f04cc04e28ed53819aee3577853a874c03a5488610f2ef5553c96.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/images/cf29f9718e9f04cc04e28ed53819aee3577853a874c03a5488610f2ef5553c96.jpg)

### Tables

![06126a04aec3261ada292d78dc4c73e3db278e8ce5a420176a680eef159a05fc.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/tables/06126a04aec3261ada292d78dc4c73e3db278e8ce5a420176a680eef159a05fc.jpg)

![14c08b1bf89a25339e6c79e815dae374cfdd47f3e26ddec379cdec4b73c15cf8.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/tables/14c08b1bf89a25339e6c79e815dae374cfdd47f3e26ddec379cdec4b73c15cf8.jpg)

![476aaf6e8511629b14cb6a531f120b26089e284e75029d8db0722f1a7903deb5.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/tables/476aaf6e8511629b14cb6a531f120b26089e284e75029d8db0722f1a7903deb5.jpg)

![4aff791b8a81847012fdb802282417e674172412a3234bd9d00c440e69107ced.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/tables/4aff791b8a81847012fdb802282417e674172412a3234bd9d00c440e69107ced.jpg)

![5ea3793bcc727d7e3733deaba890aca2453d0178ed1ef20206dfef25e0aebc86.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/tables/5ea3793bcc727d7e3733deaba890aca2453d0178ed1ef20206dfef25e0aebc86.jpg)

![b00f5942885fe7baa75d29a676a9ef41b65fc5df6b8efaa5224052fed40e1054.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/tables/b00f5942885fe7baa75d29a676a9ef41b65fc5df6b8efaa5224052fed40e1054.jpg)

![ca38d87146328fa3ee79fc5d3b36e67129332db652344b4162ff88c2d235e499.jpg](../nips_results/1138_Boundary-to-Region%20Supervision%20for%20Offline%20Safe%20Reinforcement%20Learning/tables/ca38d87146328fa3ee79fc5d3b36e67129332db652344b4162ff88c2d235e499.jpg)

## Tight High-Probability Bounds for Nonconvex Heavy-Tailed Scenario under Weaker Assumptions


### Images

![217276848fd610c115774feaf39cd28a6a8d1c433d2396be256286ae9d6871c5.jpg](../nips_results/1139_Tight%20High-Probability%20Bounds%20for%20Nonconvex%20Heavy-Tailed%20Scenario%20under%20Weaker%20Assumptions/images/217276848fd610c115774feaf39cd28a6a8d1c433d2396be256286ae9d6871c5.jpg)

![2fad9c0de92181aeb287737cb830c008e094d2a4ed790fbfddf9f3fb890695c3.jpg](../nips_results/1139_Tight%20High-Probability%20Bounds%20for%20Nonconvex%20Heavy-Tailed%20Scenario%20under%20Weaker%20Assumptions/images/2fad9c0de92181aeb287737cb830c008e094d2a4ed790fbfddf9f3fb890695c3.jpg)

![370df8e055209b479f198591d3c90ab4bf08408dd3ebb30fd74dc87c0f6dcbd0.jpg](../nips_results/1139_Tight%20High-Probability%20Bounds%20for%20Nonconvex%20Heavy-Tailed%20Scenario%20under%20Weaker%20Assumptions/images/370df8e055209b479f198591d3c90ab4bf08408dd3ebb30fd74dc87c0f6dcbd0.jpg)

### Tables

![10b56bd8c8f41002a9303c37387ff251129aa8a18c130926f1dcb097eb5a3f17.jpg](../nips_results/1139_Tight%20High-Probability%20Bounds%20for%20Nonconvex%20Heavy-Tailed%20Scenario%20under%20Weaker%20Assumptions/tables/10b56bd8c8f41002a9303c37387ff251129aa8a18c130926f1dcb097eb5a3f17.jpg)

![14463c930098a141552bcaa9d7f309db8f6f4e9f38e50cf7637f4d188b2499a0.jpg](../nips_results/1139_Tight%20High-Probability%20Bounds%20for%20Nonconvex%20Heavy-Tailed%20Scenario%20under%20Weaker%20Assumptions/tables/14463c930098a141552bcaa9d7f309db8f6f4e9f38e50cf7637f4d188b2499a0.jpg)

![c487c6b528b40cc7d391fc7df7b7d00eb1ddea5d748caab06e6a7bf4cd668b78.jpg](../nips_results/1139_Tight%20High-Probability%20Bounds%20for%20Nonconvex%20Heavy-Tailed%20Scenario%20under%20Weaker%20Assumptions/tables/c487c6b528b40cc7d391fc7df7b7d00eb1ddea5d748caab06e6a7bf4cd668b78.jpg)

## Intermediate Domain Alignment and Morphology Analogy for Patent-Product Image Retrieval


### Images

![1593aae71c15734076ecf2faec6383fca74989f7560b54721ba96d44ba8cf808.jpg](../nips_results/1140_Intermediate%20Domain%20Alignment%20and%20Morphology%20Analogy%20for%20Patent-Product%20Image%20Retrieval/images/1593aae71c15734076ecf2faec6383fca74989f7560b54721ba96d44ba8cf808.jpg)

![2cb07adf5c71b375e14d415669711ee5cd38a1d797569b9920e7e0d16f7693da.jpg](../nips_results/1140_Intermediate%20Domain%20Alignment%20and%20Morphology%20Analogy%20for%20Patent-Product%20Image%20Retrieval/images/2cb07adf5c71b375e14d415669711ee5cd38a1d797569b9920e7e0d16f7693da.jpg)

![a59038bcca6a0e7ae2faae13e29d7c0d63ef0650dc94c0f706c44fe889da4861.jpg](../nips_results/1140_Intermediate%20Domain%20Alignment%20and%20Morphology%20Analogy%20for%20Patent-Product%20Image%20Retrieval/images/a59038bcca6a0e7ae2faae13e29d7c0d63ef0650dc94c0f706c44fe889da4861.jpg)

![acd84e85c9c8177b683b55718a6a174dccc285e28bd195483470f38eae85dfcd.jpg](../nips_results/1140_Intermediate%20Domain%20Alignment%20and%20Morphology%20Analogy%20for%20Patent-Product%20Image%20Retrieval/images/acd84e85c9c8177b683b55718a6a174dccc285e28bd195483470f38eae85dfcd.jpg)

![b490033daf571917dd19db2ed96ed49892d90cb7f7d0cde5bbe616e0e56909e1.jpg](../nips_results/1140_Intermediate%20Domain%20Alignment%20and%20Morphology%20Analogy%20for%20Patent-Product%20Image%20Retrieval/images/b490033daf571917dd19db2ed96ed49892d90cb7f7d0cde5bbe616e0e56909e1.jpg)

### Tables

![17291ae906fb28aa3eaf925f553a8fee0baf4da20313df773e68b3091c347ee3.jpg](../nips_results/1140_Intermediate%20Domain%20Alignment%20and%20Morphology%20Analogy%20for%20Patent-Product%20Image%20Retrieval/tables/17291ae906fb28aa3eaf925f553a8fee0baf4da20313df773e68b3091c347ee3.jpg)

![6274886ce6319b09b62723584735022debb5f582699e92deb8aca06fb6678b56.jpg](../nips_results/1140_Intermediate%20Domain%20Alignment%20and%20Morphology%20Analogy%20for%20Patent-Product%20Image%20Retrieval/tables/6274886ce6319b09b62723584735022debb5f582699e92deb8aca06fb6678b56.jpg)

![7a80e683aaf90b8e8c4b34374832019ca5c5db8a5c68c8a2aa89399da27b9e20.jpg](../nips_results/1140_Intermediate%20Domain%20Alignment%20and%20Morphology%20Analogy%20for%20Patent-Product%20Image%20Retrieval/tables/7a80e683aaf90b8e8c4b34374832019ca5c5db8a5c68c8a2aa89399da27b9e20.jpg)

![d5df93c1f526d30272bd4819280768e888c320b67a658a25504b9cf2f7fd7b7b.jpg](../nips_results/1140_Intermediate%20Domain%20Alignment%20and%20Morphology%20Analogy%20for%20Patent-Product%20Image%20Retrieval/tables/d5df93c1f526d30272bd4819280768e888c320b67a658a25504b9cf2f7fd7b7b.jpg)

## TrackingWorld: World-centric Monocular 3D Tracking of Almost All Pixels


### Images

![04b574ee95cfc09feba4b4c0cd8e76fcc41746b55b7c5bfc393099ae4c2f7464.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/images/04b574ee95cfc09feba4b4c0cd8e76fcc41746b55b7c5bfc393099ae4c2f7464.jpg)

![7ad2b42c0cdde50ac217f8ad16c9386ad49d7cfbce6f736dd92d704faee0866a.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/images/7ad2b42c0cdde50ac217f8ad16c9386ad49d7cfbce6f736dd92d704faee0866a.jpg)

![b666d06c55a3f2f78cf31d122cd30ded9a31371092a4a3dd35a22adf90f26b7c.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/images/b666d06c55a3f2f78cf31d122cd30ded9a31371092a4a3dd35a22adf90f26b7c.jpg)

![ceca60a76486ac6adb0e830dea1113ba8edb8066a56cffb9d2060928925bdd50.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/images/ceca60a76486ac6adb0e830dea1113ba8edb8066a56cffb9d2060928925bdd50.jpg)

### Tables

![0f62c8ad59910f0639e670d7ab09bd1d4b9591895b8a377c2c283aae20fbcd11.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/tables/0f62c8ad59910f0639e670d7ab09bd1d4b9591895b8a377c2c283aae20fbcd11.jpg)

![45fdf2f4f715607b803d3c6cbe2ade60e81491441e8b34a056c635ad377fb86f.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/tables/45fdf2f4f715607b803d3c6cbe2ade60e81491441e8b34a056c635ad377fb86f.jpg)

![46da65274d511b531bc520a84b0dab1654c336adc8145928b9675087097ebb24.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/tables/46da65274d511b531bc520a84b0dab1654c336adc8145928b9675087097ebb24.jpg)

![7a4dadbcfcf7dde242b35adbfd067a04b763a0ed4ec0f5a390e7c736c7b47067.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/tables/7a4dadbcfcf7dde242b35adbfd067a04b763a0ed4ec0f5a390e7c736c7b47067.jpg)

![abdaf821a23f3c45d8ea92a2047149243ce4a417c8728a86f4ec1c4c4ebb9458.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/tables/abdaf821a23f3c45d8ea92a2047149243ce4a417c8728a86f4ec1c4c4ebb9458.jpg)

![ca4a1d68046d9d1829055dcec763a70db0426b3fa4722fc899151040223c5116.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/tables/ca4a1d68046d9d1829055dcec763a70db0426b3fa4722fc899151040223c5116.jpg)

![f3f9f50d70f324721b647f3563eda1fa71128c3b6c8e7d9459c9955421dca1f4.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/tables/f3f9f50d70f324721b647f3563eda1fa71128c3b6c8e7d9459c9955421dca1f4.jpg)

![fdeded145f0683463471775e007fe830d23c2f39c84e2a5fc771b2513e6b5f78.jpg](../nips_results/1141_TrackingWorld_%20World-centric%20Monocular%203D%20Tracking%20of%20Almost%20All%20Pixels/tables/fdeded145f0683463471775e007fe830d23c2f39c84e2a5fc771b2513e6b5f78.jpg)

## Calibrating Translation Decoding with Quality Estimation on LLMs


### Images

![329213c273ba90724fb08c6e76e5c3c632c4b9eb9e0c448c10d8894fb2c90c2e.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/images/329213c273ba90724fb08c6e76e5c3c632c4b9eb9e0c448c10d8894fb2c90c2e.jpg)

![35864715b44f3ea759b46a86013e9ad69de3121d909572c1900497317c09f88f.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/images/35864715b44f3ea759b46a86013e9ad69de3121d909572c1900497317c09f88f.jpg)

![45812dbe5387bbd0b356a028b7df79c490bf182caba2400995074d31473ead35.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/images/45812dbe5387bbd0b356a028b7df79c490bf182caba2400995074d31473ead35.jpg)

![73e2f672a5ac4700d86a800537f762f18838dba8a8f9c7b95c07f475f299bcf5.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/images/73e2f672a5ac4700d86a800537f762f18838dba8a8f9c7b95c07f475f299bcf5.jpg)

![abf29c43f3f33f38753adeec6b1cd791460afdf64fb5531a341ab1c41847724c.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/images/abf29c43f3f33f38753adeec6b1cd791460afdf64fb5531a341ab1c41847724c.jpg)

![d1bc6d1bd7096e8a2446164490ed813d8f33d5d28e468a09442fb32b32f5784f.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/images/d1bc6d1bd7096e8a2446164490ed813d8f33d5d28e468a09442fb32b32f5784f.jpg)

![d4f0412c408985d7c43ba6b21cbbf6dd1a7dc46d03e508031f567ff42a90dcd4.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/images/d4f0412c408985d7c43ba6b21cbbf6dd1a7dc46d03e508031f567ff42a90dcd4.jpg)

![e1bb6ec825e1696c780ad2e7c24b632ae2343e069d3eb2dbd9ae6b7b03e52dd1.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/images/e1bb6ec825e1696c780ad2e7c24b632ae2343e069d3eb2dbd9ae6b7b03e52dd1.jpg)

![fc4476ef53765c8e9c99f75b88e3b3075bea12031358cd5f04c9a2ab7c7f0a24.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/images/fc4476ef53765c8e9c99f75b88e3b3075bea12031358cd5f04c9a2ab7c7f0a24.jpg)

### Tables

![0a49b47f0aac2378b866ab38c193bf31d416b6deb23059be0d90ebf128e6d75d.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/0a49b47f0aac2378b866ab38c193bf31d416b6deb23059be0d90ebf128e6d75d.jpg)

![213ac0ef9d41c1beb98fdf38a252c76a9b360dbc584cab0c25dc7851a47e3980.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/213ac0ef9d41c1beb98fdf38a252c76a9b360dbc584cab0c25dc7851a47e3980.jpg)

![2c3b7f3802b4ed01f31e60e774cb4e8b227cae0dd0bb684ad8f9415c6bf30b51.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/2c3b7f3802b4ed01f31e60e774cb4e8b227cae0dd0bb684ad8f9415c6bf30b51.jpg)

![307f8f4de2a111c03ad05223171c768a8bb15f1dd01c2a0e1d8163be54e400ec.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/307f8f4de2a111c03ad05223171c768a8bb15f1dd01c2a0e1d8163be54e400ec.jpg)

![3a775700d8b2083c7af5dc04c216470ed9c672c4d5e05c176346f9a3021174ef.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/3a775700d8b2083c7af5dc04c216470ed9c672c4d5e05c176346f9a3021174ef.jpg)

![5e3715a358c156e1ec41b8ac82b6ac8a0035a4140c22b0f1972ccbaf6303abe4.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/5e3715a358c156e1ec41b8ac82b6ac8a0035a4140c22b0f1972ccbaf6303abe4.jpg)

![7bc2674f45b80309e4a2568cc993ce2643b9d913f8502a0203c8937cbef5fe1f.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/7bc2674f45b80309e4a2568cc993ce2643b9d913f8502a0203c8937cbef5fe1f.jpg)

![c3d637251973da3302e6c8f168b56a51a546a16d3386b128e425805b1964cfb6.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/c3d637251973da3302e6c8f168b56a51a546a16d3386b128e425805b1964cfb6.jpg)

![d425bc1d7ab8b28abe13f6c56cb4e4eec83060821b7a3e02220702c3931a7966.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/d425bc1d7ab8b28abe13f6c56cb4e4eec83060821b7a3e02220702c3931a7966.jpg)

![ec69939158083a5c9bf7bba91bab3735b662448f285a4994fe2b26e7c0eee2dc.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/ec69939158083a5c9bf7bba91bab3735b662448f285a4994fe2b26e7c0eee2dc.jpg)

![f74e3658de0ea02dca60c44e6d0ce89bd3f197f788fa3c94992272b686881b96.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/f74e3658de0ea02dca60c44e6d0ce89bd3f197f788fa3c94992272b686881b96.jpg)

![ff484ed2e035b04bf7af20c0a05028c6dc13e318646be67c991287603de2ab84.jpg](../nips_results/1142_Calibrating%20Translation%20Decoding%20with%20Quality%20Estimation%20on%20LLMs/tables/ff484ed2e035b04bf7af20c0a05028c6dc13e318646be67c991287603de2ab84.jpg)

## Distributional Adversarial Attacks and Training in Deep Hedging


### Images

![045fccdbea470196de232cf0a5aa3f28f82f934df793edacdb0d83009a46eadd.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/images/045fccdbea470196de232cf0a5aa3f28f82f934df793edacdb0d83009a46eadd.jpg)

![3d110426084a65386903aac4522d98eb6c3c8c0248b8fa06bbcf6b6984fb4af2.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/images/3d110426084a65386903aac4522d98eb6c3c8c0248b8fa06bbcf6b6984fb4af2.jpg)

![594a6a13fe96ad1c4d11a0d7559032ac23251d82d66b5460e92c0aa7d54ba73b.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/images/594a6a13fe96ad1c4d11a0d7559032ac23251d82d66b5460e92c0aa7d54ba73b.jpg)

![a9250c17ede13ad4b741cb131028426c9b5bc55894276448f9c2a1ab88eac7de.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/images/a9250c17ede13ad4b741cb131028426c9b5bc55894276448f9c2a1ab88eac7de.jpg)

![ad56a1bcee103b9d0cbf19493207a6fed054c39b2f0d73013ac828f2b396c08b.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/images/ad56a1bcee103b9d0cbf19493207a6fed054c39b2f0d73013ac828f2b396c08b.jpg)

### Tables

![2b63cdaa001c9bb5c09be81dc0ee115e9d324caf71f3380899717fdf768e926c.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/2b63cdaa001c9bb5c09be81dc0ee115e9d324caf71f3380899717fdf768e926c.jpg)

![4eda6e6528d872ae19abbeb0177297b717941e51741ebff2c0e6788ec2bee776.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/4eda6e6528d872ae19abbeb0177297b717941e51741ebff2c0e6788ec2bee776.jpg)

![65e9f92fc268df09b830ac15c0c1fdbeed3463b906c1175b152e3d0ffa11ef19.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/65e9f92fc268df09b830ac15c0c1fdbeed3463b906c1175b152e3d0ffa11ef19.jpg)

![8536197f31c669503bfe3166074082de76271edd71e8133a14357d2dfb81c520.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/8536197f31c669503bfe3166074082de76271edd71e8133a14357d2dfb81c520.jpg)

![9826e5d5bdc6f1d59bcf0ff15ff58196675e77b2466bc7a83bbb5d0f02a13f48.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/9826e5d5bdc6f1d59bcf0ff15ff58196675e77b2466bc7a83bbb5d0f02a13f48.jpg)

![a7073f93fb76a332b7d13c8d0c6b138169528b822a45f80b36a22fec9898f152.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/a7073f93fb76a332b7d13c8d0c6b138169528b822a45f80b36a22fec9898f152.jpg)

![c08a7f7668917fe86d26c324767a41af8577b195ba38cb7cc5c03ae396a2334c.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/c08a7f7668917fe86d26c324767a41af8577b195ba38cb7cc5c03ae396a2334c.jpg)

![cddd1baf91caaeeaac737db2dbbbf1852296fc638a97fcd8de070cae6d0f3ed5.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/cddd1baf91caaeeaac737db2dbbbf1852296fc638a97fcd8de070cae6d0f3ed5.jpg)

![d2bf7e61f71f229550e81d244d537d9fadcb8c126107a9cc7520fa68334ea2ee.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/d2bf7e61f71f229550e81d244d537d9fadcb8c126107a9cc7520fa68334ea2ee.jpg)

![d3585d33fdf86978d2bc645c2423f0062edef90fff25410d7f4dc72b1daacb81.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/d3585d33fdf86978d2bc645c2423f0062edef90fff25410d7f4dc72b1daacb81.jpg)

![d929d0280fa7b5deccddc1bf0f88fb58cfa226a40f26fb2cfa8733afbdbc40b2.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/d929d0280fa7b5deccddc1bf0f88fb58cfa226a40f26fb2cfa8733afbdbc40b2.jpg)

![e97721b46dc6b1103f54b2876189793431dbaad1df2eb7b2f0f75b2db5a31452.jpg](../nips_results/1143_Distributional%20Adversarial%20Attacks%20and%20Training%20in%20Deep%20Hedging/tables/e97721b46dc6b1103f54b2876189793431dbaad1df2eb7b2f0f75b2db5a31452.jpg)

## AlignVLM: Bridging Vision and Language Latent Spaces for Multimodal Document Understanding


### Images

![0d7b406f26fe76a9ac577364568b20dbb9cfb1603cb0664f9451f2365fc8d79e.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/0d7b406f26fe76a9ac577364568b20dbb9cfb1603cb0664f9451f2365fc8d79e.jpg)

![138c4112d21f5788e489aa2a32cfc451b5ed008bc4f31869f1018e590813019f.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/138c4112d21f5788e489aa2a32cfc451b5ed008bc4f31869f1018e590813019f.jpg)

![2a89104c0601d3b85adbb642153af0babc6db4ceee13091e4ed52156668f47e6.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/2a89104c0601d3b85adbb642153af0babc6db4ceee13091e4ed52156668f47e6.jpg)

![35c95bc933dd6d6b7f04e098ae19f8920d7d3b2130c57a59ea904aeb58ca0d00.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/35c95bc933dd6d6b7f04e098ae19f8920d7d3b2130c57a59ea904aeb58ca0d00.jpg)

![3e1fed4f368aaaedb1c1e74cde6d4b570654332302094692cc38a6df2951ac7d.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/3e1fed4f368aaaedb1c1e74cde6d4b570654332302094692cc38a6df2951ac7d.jpg)

![534d9256d5e145058bfeed054ead0b61d8e168d48948c1686f8cbb1c67cf1f93.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/534d9256d5e145058bfeed054ead0b61d8e168d48948c1686f8cbb1c67cf1f93.jpg)

![567601dbd9275e1eb4060a5f40d593e5de94f063ba23ffb4195d1579721e9b45.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/567601dbd9275e1eb4060a5f40d593e5de94f063ba23ffb4195d1579721e9b45.jpg)

![5f1d14320a692ad8859158bf4341f35047cc5765008ffe2f3d53702fb74b5458.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/5f1d14320a692ad8859158bf4341f35047cc5765008ffe2f3d53702fb74b5458.jpg)

![6c5a66757cdc38ee0257bfbcd9f6ae2ac3e03bd9a1e5bd935d7c40a28cf2806a.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/6c5a66757cdc38ee0257bfbcd9f6ae2ac3e03bd9a1e5bd935d7c40a28cf2806a.jpg)

![7d801847d59dfc53db4230f7503e6366ddbff2fe458b17177e319033df153725.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/7d801847d59dfc53db4230f7503e6366ddbff2fe458b17177e319033df153725.jpg)

![8753af521ce8fea8e5aada00b7ab1cb23f92dd21359ea136bc24c307f500f5f9.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/8753af521ce8fea8e5aada00b7ab1cb23f92dd21359ea136bc24c307f500f5f9.jpg)

![914951890916411a8bdaf751a4f2d07a7fcb9fbfb688192304cc7202f5f038e0.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/914951890916411a8bdaf751a4f2d07a7fcb9fbfb688192304cc7202f5f038e0.jpg)

![9415298f517ea7f387932f0917e02eb74bd0a7e0591d879b71faeecef5d60bd2.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/9415298f517ea7f387932f0917e02eb74bd0a7e0591d879b71faeecef5d60bd2.jpg)

![a1f0a4312be49edf1dfc7924c09f53a2d5bceb9f737f048804ea6ae794cb6b3f.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/a1f0a4312be49edf1dfc7924c09f53a2d5bceb9f737f048804ea6ae794cb6b3f.jpg)

![ab2dfb93da3c26db1e23cb111c6a6c09b2b0c41afa785bd4882a31d7cf1c0bc1.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/ab2dfb93da3c26db1e23cb111c6a6c09b2b0c41afa785bd4882a31d7cf1c0bc1.jpg)

![add188160ceac0c5da8e4b30a1d7b4674c8b0c11bcb2fccc03d9e7b2f5bf5c51.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/add188160ceac0c5da8e4b30a1d7b4674c8b0c11bcb2fccc03d9e7b2f5bf5c51.jpg)

![d40d8e30844892207786b357b247fde17a3a800d3713d99a11eec1caef263414.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/d40d8e30844892207786b357b247fde17a3a800d3713d99a11eec1caef263414.jpg)

![e81c3c9e992bf210b7c4e4a90577bc6f572c28c41f9caa4d25ae25e284275570.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/images/e81c3c9e992bf210b7c4e4a90577bc6f572c28c41f9caa4d25ae25e284275570.jpg)

### Tables

![166640102750b3f65699d35fb328ca8ed608a208ccee669f7aca28407263f16a.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/tables/166640102750b3f65699d35fb328ca8ed608a208ccee669f7aca28407263f16a.jpg)

![51affe84bab1f00ecad6070a8d19d59a575975fb7e426964056e18d1ebdae7c6.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/tables/51affe84bab1f00ecad6070a8d19d59a575975fb7e426964056e18d1ebdae7c6.jpg)

![7787faa56764b80aa902a61f7e1c953f5187880f7fc81b5e2652aa8314db3d78.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/tables/7787faa56764b80aa902a61f7e1c953f5187880f7fc81b5e2652aa8314db3d78.jpg)

![8407ba163326c786010a3c68740e168c201c64365ec3d8205120ecb37236ac1c.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/tables/8407ba163326c786010a3c68740e168c201c64365ec3d8205120ecb37236ac1c.jpg)

![8b579bea745233d2c25060c3df33bd2355198170a329b16196ec5f1254a87468.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/tables/8b579bea745233d2c25060c3df33bd2355198170a329b16196ec5f1254a87468.jpg)

![bd769c5ec868dbcb4b143f7d9c7e846e45ee562379ae50088c0d8b6b14160596.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/tables/bd769c5ec868dbcb4b143f7d9c7e846e45ee562379ae50088c0d8b6b14160596.jpg)

![cdcadf8820c9d9527596d93bcc604106e5644d11090b0ff8a1d47fce35e949b0.jpg](../nips_results/1144_AlignVLM_%20Bridging%20Vision%20and%20Language%20Latent%20Spaces%20for%20Multimodal%20Document%20Understanding/tables/cdcadf8820c9d9527596d93bcc604106e5644d11090b0ff8a1d47fce35e949b0.jpg)

## MemSim: A Bayesian Simulator for Evaluating Memory of LLM-based Personal Assistants


### Images

![e873d8489242497cf168c2ce2b3dedbbd6c93b3cc171328705154d1bed611dfd.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/images/e873d8489242497cf168c2ce2b3dedbbd6c93b3cc171328705154d1bed611dfd.jpg)

### Tables

![09a63a27eff925e93767a42e6b54ba1aebf04b6c7cbfbaea6cbf236146441676.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/09a63a27eff925e93767a42e6b54ba1aebf04b6c7cbfbaea6cbf236146441676.jpg)

![15a9a10ff7565dd2ee262a31388f3fa3eda51883df13f48186a65766778c3425.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/15a9a10ff7565dd2ee262a31388f3fa3eda51883df13f48186a65766778c3425.jpg)

![29fe923f2553aa2598145860887a9f5ab27ff1806e8f115a068410908702e68f.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/29fe923f2553aa2598145860887a9f5ab27ff1806e8f115a068410908702e68f.jpg)

![35cf0921e98821452b464726524f0c0b39ca9fc8bafa37f82cebb3e9ccd1dbee.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/35cf0921e98821452b464726524f0c0b39ca9fc8bafa37f82cebb3e9ccd1dbee.jpg)

![407ef1daac00918086a6f06b0eacfcd185196ed4ed8d83ee760c739efd55b758.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/407ef1daac00918086a6f06b0eacfcd185196ed4ed8d83ee760c739efd55b758.jpg)

![4a34c3515af2d6b512e7761dce4ec77e21229f14a35aebca2043dee842b7a311.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/4a34c3515af2d6b512e7761dce4ec77e21229f14a35aebca2043dee842b7a311.jpg)

![52061b8625624486077ada2104a61e999d08cc8cbf892f0b3882c299449a70c3.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/52061b8625624486077ada2104a61e999d08cc8cbf892f0b3882c299449a70c3.jpg)

![5ad759d8d8fd777fd932d61682abad3502cda1d7e69bae15cb25408b1226ba6f.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/5ad759d8d8fd777fd932d61682abad3502cda1d7e69bae15cb25408b1226ba6f.jpg)

![5aee4cd185eb14f5388fbe7111f1ce81752fee50b2486f9d006b6fe447f9be79.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/5aee4cd185eb14f5388fbe7111f1ce81752fee50b2486f9d006b6fe447f9be79.jpg)

![69fa92275e95f67266c54dd712d206b27baba76824c0b5e847a9edcbfb3279a4.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/69fa92275e95f67266c54dd712d206b27baba76824c0b5e847a9edcbfb3279a4.jpg)

![792e2fe9fa02c979427c9adc3b33cd6a18178e4d26f6e95161920cf7455992a3.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/792e2fe9fa02c979427c9adc3b33cd6a18178e4d26f6e95161920cf7455992a3.jpg)

![8753872b8f5d93042bda8f9182e3b55dc1ea0be66a2da04989c1815cfff032c4.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/8753872b8f5d93042bda8f9182e3b55dc1ea0be66a2da04989c1815cfff032c4.jpg)

![87daf1beed5b86f3fe28fdf1a84365dafdf45fe535cd327af3bb7adff2bb21bb.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/87daf1beed5b86f3fe28fdf1a84365dafdf45fe535cd327af3bb7adff2bb21bb.jpg)

![b4c97f5078e364838a2615662e03c74ddbeae2000d54e74a8657abcbeceeb38c.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/b4c97f5078e364838a2615662e03c74ddbeae2000d54e74a8657abcbeceeb38c.jpg)

![b747a5a3b2e9ca012a37670b9bb3c005f5988e3144faa7580dc69ec9b9c3ca7f.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/b747a5a3b2e9ca012a37670b9bb3c005f5988e3144faa7580dc69ec9b9c3ca7f.jpg)

![b94af200425c43eecda56b89a2ca6b7f0c9c073920026d79394bf5ddd125cb50.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/b94af200425c43eecda56b89a2ca6b7f0c9c073920026d79394bf5ddd125cb50.jpg)

![d1f32491fdceb6e64bd63cd5cd180ba01a30fb62b05cfcf8db3ccaa092fcce6a.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/d1f32491fdceb6e64bd63cd5cd180ba01a30fb62b05cfcf8db3ccaa092fcce6a.jpg)

![d222010d00f8d45b08c6724330ea50df4975c2cb1372e05fb12d9ecceef2efe4.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/d222010d00f8d45b08c6724330ea50df4975c2cb1372e05fb12d9ecceef2efe4.jpg)

![d4fe3afa0f4acdaff577e04a12135c0070a34e4a087944c9867efb0c7e3baf72.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/d4fe3afa0f4acdaff577e04a12135c0070a34e4a087944c9867efb0c7e3baf72.jpg)

![dd850059b4ea08fd7be80561cd1535b64afaeb91278e9084b997408b2401d721.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/dd850059b4ea08fd7be80561cd1535b64afaeb91278e9084b997408b2401d721.jpg)

![e1cbffda5977a3af28af1b0ef07209d67b3dfeb262a5b6c0327a1a0c7470b771.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/e1cbffda5977a3af28af1b0ef07209d67b3dfeb262a5b6c0327a1a0c7470b771.jpg)

![e3f0f41f94a61420bed65ba2185ac314c6bca5bc3f7d8b817f198972198c2c23.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/e3f0f41f94a61420bed65ba2185ac314c6bca5bc3f7d8b817f198972198c2c23.jpg)

![eb49e0ce40eed7fe3a9cd962a8d5cc5196a89930faea3822bb5752faf05b63d4.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/eb49e0ce40eed7fe3a9cd962a8d5cc5196a89930faea3822bb5752faf05b63d4.jpg)

![efd893b8ec43490d974113b7089756dcf4c494fb9a5038fc092ec74391cd62df.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/efd893b8ec43490d974113b7089756dcf4c494fb9a5038fc092ec74391cd62df.jpg)

![f026f09dd8a28b8a0a9e0d023735b401e9acf0287ca0b0cd15a3117cd4e5d488.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/f026f09dd8a28b8a0a9e0d023735b401e9acf0287ca0b0cd15a3117cd4e5d488.jpg)

![f1221376829bf7622e5849910e65735ac1d4f131d2528f841672d43d827f2cdc.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/f1221376829bf7622e5849910e65735ac1d4f131d2528f841672d43d827f2cdc.jpg)

![fad6a6d05bc504369eed5d4ef66ed1ff8808231a67380e7a0c7d5ffcdd4e2e2a.jpg](../nips_results/1145_MemSim_%20A%20Bayesian%20Simulator%20for%20Evaluating%20Memory%20of%20LLM-based%20Personal%20Assistants/tables/fad6a6d05bc504369eed5d4ef66ed1ff8808231a67380e7a0c7d5ffcdd4e2e2a.jpg)

## Learning to Clean: Reinforcement Learning for Noisy Label Correction


### Images

![930ff355e89dfffacb11e4647bd7e0608f152b45926827038b995adb230af1bb.jpg](../nips_results/1146_Learning%20to%20Clean_%20Reinforcement%20Learning%20for%20Noisy%20Label%20Correction/images/930ff355e89dfffacb11e4647bd7e0608f152b45926827038b995adb230af1bb.jpg)

![ac88ddeba7a8bed1127b5609ee9a7aa51733fcc041c918b6790dc80372cb5908.jpg](../nips_results/1146_Learning%20to%20Clean_%20Reinforcement%20Learning%20for%20Noisy%20Label%20Correction/images/ac88ddeba7a8bed1127b5609ee9a7aa51733fcc041c918b6790dc80372cb5908.jpg)

![cfa1d722601707ba52b0057251e1ab9a965ad876c4e64849b2003ebd6f2b26da.jpg](../nips_results/1146_Learning%20to%20Clean_%20Reinforcement%20Learning%20for%20Noisy%20Label%20Correction/images/cfa1d722601707ba52b0057251e1ab9a965ad876c4e64849b2003ebd6f2b26da.jpg)

### Tables

![09a46fcecbec44ded7912b69343270fc0dc17ea7371545d9116be8db562ad85c.jpg](../nips_results/1146_Learning%20to%20Clean_%20Reinforcement%20Learning%20for%20Noisy%20Label%20Correction/tables/09a46fcecbec44ded7912b69343270fc0dc17ea7371545d9116be8db562ad85c.jpg)

![2be7561b306a5fc629ce4381b4a7ac3cb859610ca7fa28e7a56061b24ebbe9f2.jpg](../nips_results/1146_Learning%20to%20Clean_%20Reinforcement%20Learning%20for%20Noisy%20Label%20Correction/tables/2be7561b306a5fc629ce4381b4a7ac3cb859610ca7fa28e7a56061b24ebbe9f2.jpg)

![3b0f37415c33fed5dfdf7b69225ec7ad6823559e0af87aaaf1ed336aa9658375.jpg](../nips_results/1146_Learning%20to%20Clean_%20Reinforcement%20Learning%20for%20Noisy%20Label%20Correction/tables/3b0f37415c33fed5dfdf7b69225ec7ad6823559e0af87aaaf1ed336aa9658375.jpg)

![5101ba948e9b7ff3e3ec58ddefbb07e724d46a70cad1bc8fc0902625caac9fba.jpg](../nips_results/1146_Learning%20to%20Clean_%20Reinforcement%20Learning%20for%20Noisy%20Label%20Correction/tables/5101ba948e9b7ff3e3ec58ddefbb07e724d46a70cad1bc8fc0902625caac9fba.jpg)

![abae8bbb9195bc13015d0b4999ceff8b3af025c85b1bbb84368d970efc58a35f.jpg](../nips_results/1146_Learning%20to%20Clean_%20Reinforcement%20Learning%20for%20Noisy%20Label%20Correction/tables/abae8bbb9195bc13015d0b4999ceff8b3af025c85b1bbb84368d970efc58a35f.jpg)

![cecf727910315a32d54b7ff7a6b4e682d0ca4aa2daf50fadbe476c47af2c97de.jpg](../nips_results/1146_Learning%20to%20Clean_%20Reinforcement%20Learning%20for%20Noisy%20Label%20Correction/tables/cecf727910315a32d54b7ff7a6b4e682d0ca4aa2daf50fadbe476c47af2c97de.jpg)

## TiRex: Zero-Shot Forecasting Across Long and Short Horizons with Enhanced In-Context Learning


### Images

![0390338f6088fc46228385800ed06b601cc3d10b332ae04760ef6d1daf3ebaed.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/0390338f6088fc46228385800ed06b601cc3d10b332ae04760ef6d1daf3ebaed.jpg)

![04f79ea59196fafe2b093e734efd03b75b0a874dd10b40e9516deba9e18f5742.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/04f79ea59196fafe2b093e734efd03b75b0a874dd10b40e9516deba9e18f5742.jpg)

![2015869a5949f4d7bd14b5b2a819bce05c6e7bb312cd9af2d6d33cabb0cba991.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/2015869a5949f4d7bd14b5b2a819bce05c6e7bb312cd9af2d6d33cabb0cba991.jpg)

![25d11aab66552c4fdf7e8a3ea0daeeb059ea5f9f39a1ccf4b256ed7becd0ef99.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/25d11aab66552c4fdf7e8a3ea0daeeb059ea5f9f39a1ccf4b256ed7becd0ef99.jpg)

![3276686a9e0f40b4bcf5a165ae675d9dcc0bb608344af536149db71af612a2f9.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/3276686a9e0f40b4bcf5a165ae675d9dcc0bb608344af536149db71af612a2f9.jpg)

![359dc4e1123a64f00599699c2f99a0483996d619610e441afe4161b9a2ba093b.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/359dc4e1123a64f00599699c2f99a0483996d619610e441afe4161b9a2ba093b.jpg)

![461e6f780461a95636a3500ca6ca03b02c1b03987add183297ef8c2f2cb5ce0c.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/461e6f780461a95636a3500ca6ca03b02c1b03987add183297ef8c2f2cb5ce0c.jpg)

![4878758181c94f0c3a05c73894cf2ffecaa520449f8bc21bb0f727b4fc5c957c.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/4878758181c94f0c3a05c73894cf2ffecaa520449f8bc21bb0f727b4fc5c957c.jpg)

![52fdff98a08724f8bb5255882a65f035b18ad1339f1103f8312acfb481185f9d.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/52fdff98a08724f8bb5255882a65f035b18ad1339f1103f8312acfb481185f9d.jpg)

![568810e76b5ce942886d4586c3b213c38e74d61fd0c329e3d114e42af3c6077b.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/568810e76b5ce942886d4586c3b213c38e74d61fd0c329e3d114e42af3c6077b.jpg)

![572b8efa10258e10da9d945281e18c303e14403c38c556c5e62106f98afb347a.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/572b8efa10258e10da9d945281e18c303e14403c38c556c5e62106f98afb347a.jpg)

![91be73c1a6d694f77cfeb8394fd5947b9107358d6c1075e6565d7a3411ae43d5.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/91be73c1a6d694f77cfeb8394fd5947b9107358d6c1075e6565d7a3411ae43d5.jpg)

![a09bff30820e60b7f0a85d396d8072fddbfe570f74475304fc67c7eb7bd3b52c.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/a09bff30820e60b7f0a85d396d8072fddbfe570f74475304fc67c7eb7bd3b52c.jpg)

![ab1422c102745ab159e308620df9ce36dbd5a47c08eee7b5bd4a699eba9bdc17.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/ab1422c102745ab159e308620df9ce36dbd5a47c08eee7b5bd4a699eba9bdc17.jpg)

![bf6871cb6fd1d8b08dce931d6888fb80c779512bd4ce76956a63c8d560b36774.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/bf6871cb6fd1d8b08dce931d6888fb80c779512bd4ce76956a63c8d560b36774.jpg)

![c70b440aabf5bdbac8c8cd6b6f0c2c2a23ba7b77e987e80cc2b68a68d46ae8a8.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/c70b440aabf5bdbac8c8cd6b6f0c2c2a23ba7b77e987e80cc2b68a68d46ae8a8.jpg)

![d367bf034c22095ced5099500d69f1780d9317795c6a58ffdb4b79e882ac9539.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/d367bf034c22095ced5099500d69f1780d9317795c6a58ffdb4b79e882ac9539.jpg)

![d71cd1b87f6424c7e8ec1ae2212d39c69aa0fcb2aecc1493a14eb3d14f5f0f78.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/d71cd1b87f6424c7e8ec1ae2212d39c69aa0fcb2aecc1493a14eb3d14f5f0f78.jpg)

![d8f7f603b77d8ca08ff9c9460e7ecdab2ea6102d9087db889a6779189c76d5a4.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/d8f7f603b77d8ca08ff9c9460e7ecdab2ea6102d9087db889a6779189c76d5a4.jpg)

![de3fb02ef01d76e5d0adf5501da319d7a18fd734748481a33e553572658c10a5.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/de3fb02ef01d76e5d0adf5501da319d7a18fd734748481a33e553572658c10a5.jpg)

![eca49745efc43b382b91b0728f5f0552affbad71df005c8e6374a904d9aa5c3e.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/images/eca49745efc43b382b91b0728f5f0552affbad71df005c8e6374a904d9aa5c3e.jpg)

### Tables

![03499f934588df9c2de667a47d0203a05137ea10fca24b828d861771bef8f73f.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/03499f934588df9c2de667a47d0203a05137ea10fca24b828d861771bef8f73f.jpg)

![08c03bd4bc0beac59174fb73b40d53ad2665c825cbc0d4b67f7321ff36937527.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/08c03bd4bc0beac59174fb73b40d53ad2665c825cbc0d4b67f7321ff36937527.jpg)

![11fc225539a6adfff427b34192a0f66ea6f815e68eb9f72233f539ae7510d889.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/11fc225539a6adfff427b34192a0f66ea6f815e68eb9f72233f539ae7510d889.jpg)

![1ba9ee802735a71aae7cec4c6068f40b72f401c7c7ea97dff126429d85b0d07a.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/1ba9ee802735a71aae7cec4c6068f40b72f401c7c7ea97dff126429d85b0d07a.jpg)

![1e8da40e3ca45e29d491a15a245052080fd8c4d07352949aa1dbc75b9e5a2976.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/1e8da40e3ca45e29d491a15a245052080fd8c4d07352949aa1dbc75b9e5a2976.jpg)

![256f0095c8b939f6a79f612a3e2523e923d2529719c538224e5e6d4869abf2ef.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/256f0095c8b939f6a79f612a3e2523e923d2529719c538224e5e6d4869abf2ef.jpg)

![4a9b326648be5fcb058b173957c233817fe6a45ad10d818f60f64058b6184733.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/4a9b326648be5fcb058b173957c233817fe6a45ad10d818f60f64058b6184733.jpg)

![5056d369c518d627bc5fd5edd4ed20b8083c152da25f4e7520183d258744d07d.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/5056d369c518d627bc5fd5edd4ed20b8083c152da25f4e7520183d258744d07d.jpg)

![706f23501c8eda5a348b15ca7f9c6428f206d3df9e4e5fa76aa9f75007e9140f.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/706f23501c8eda5a348b15ca7f9c6428f206d3df9e4e5fa76aa9f75007e9140f.jpg)

![737e87488a71e0a98ce00732d5ce0a38ac652975a45977bde50a4a02338a821e.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/737e87488a71e0a98ce00732d5ce0a38ac652975a45977bde50a4a02338a821e.jpg)

![74f1f53c689de6671baa4e83a71766410b67bb242d1e2627d8e6dec87edb4b34.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/74f1f53c689de6671baa4e83a71766410b67bb242d1e2627d8e6dec87edb4b34.jpg)

![7cabfce69eb1bcd22f7478ec2a15a18a92bbf8f67b8c329e4f3951cb0091985c.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/7cabfce69eb1bcd22f7478ec2a15a18a92bbf8f67b8c329e4f3951cb0091985c.jpg)

![943fbca2f2eb074b34ac7780594ead0f1a024bb39084eb1dba59329e059164de.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/943fbca2f2eb074b34ac7780594ead0f1a024bb39084eb1dba59329e059164de.jpg)

![959f528524939fa92238e24eab245253b84b89fb3ead8c3626e7540bf8bb12f8.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/959f528524939fa92238e24eab245253b84b89fb3ead8c3626e7540bf8bb12f8.jpg)

![a39f17b30f7e4b46684ca76d089efc395861dfbda9f2097de6d15a379925e077.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/a39f17b30f7e4b46684ca76d089efc395861dfbda9f2097de6d15a379925e077.jpg)

![c75e21a264199b8cc1778757ffd962770cffa5b482d44c3cc6a727c2c8e04f5f.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/c75e21a264199b8cc1778757ffd962770cffa5b482d44c3cc6a727c2c8e04f5f.jpg)

![dfcf1c6016839dfab8ff2d75b2ae7495a07c4ab193d51b0f800e6fcc44112a9a.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/dfcf1c6016839dfab8ff2d75b2ae7495a07c4ab193d51b0f800e6fcc44112a9a.jpg)

![e86ac889c403d1a8cf523c8e8e10de98fe47c19832f9b39a51cb9c7b18bfc890.jpg](../nips_results/1147_TiRex_%20Zero-Shot%20Forecasting%20Across%20Long%20and%20Short%20Horizons%20with%20Enhanced%20In-Context%20Learning/tables/e86ac889c403d1a8cf523c8e8e10de98fe47c19832f9b39a51cb9c7b18bfc890.jpg)

## Last-Iterate Convergence of Smooth Regret Matching$^+$ Variants in Learning Nash Equilibria


### Images

![424db1b2bbbbdf495c4dad364eb3afaee25c769cadb63149c135c3b42b3bf4e8.jpg](../nips_results/1148_Last-Iterate%20Convergence%20of%20Smooth%20Regret%20Matching%24%5E%2B%24%20Variants%20in%20Learning%20Nash%20Equilibria/images/424db1b2bbbbdf495c4dad364eb3afaee25c769cadb63149c135c3b42b3bf4e8.jpg)

![6e899c2bb3530a84279303a752837065809095ce028689a6fd6f993a27f0b456.jpg](../nips_results/1148_Last-Iterate%20Convergence%20of%20Smooth%20Regret%20Matching%24%5E%2B%24%20Variants%20in%20Learning%20Nash%20Equilibria/images/6e899c2bb3530a84279303a752837065809095ce028689a6fd6f993a27f0b456.jpg)

![907f77438aeba9cbcc910d4320da5961f5aff6d62615a2f729c28f25bb7dbb55.jpg](../nips_results/1148_Last-Iterate%20Convergence%20of%20Smooth%20Regret%20Matching%24%5E%2B%24%20Variants%20in%20Learning%20Nash%20Equilibria/images/907f77438aeba9cbcc910d4320da5961f5aff6d62615a2f729c28f25bb7dbb55.jpg)

![a3443927e64cc127387964b9bf0805b39a5f0df3c304eec1d5136b8441c8e9cc.jpg](../nips_results/1148_Last-Iterate%20Convergence%20of%20Smooth%20Regret%20Matching%24%5E%2B%24%20Variants%20in%20Learning%20Nash%20Equilibria/images/a3443927e64cc127387964b9bf0805b39a5f0df3c304eec1d5136b8441c8e9cc.jpg)

![bd731f5ac17f86e246e5342e0a07caa2bcb1ebb663107b6a2ffb1d7cf9157660.jpg](../nips_results/1148_Last-Iterate%20Convergence%20of%20Smooth%20Regret%20Matching%24%5E%2B%24%20Variants%20in%20Learning%20Nash%20Equilibria/images/bd731f5ac17f86e246e5342e0a07caa2bcb1ebb663107b6a2ffb1d7cf9157660.jpg)

![ecf581611b3b7733988b3fa68ef119811b50c6f493a51355caa96338cc6b0d42.jpg](../nips_results/1148_Last-Iterate%20Convergence%20of%20Smooth%20Regret%20Matching%24%5E%2B%24%20Variants%20in%20Learning%20Nash%20Equilibria/images/ecf581611b3b7733988b3fa68ef119811b50c6f493a51355caa96338cc6b0d42.jpg)

### Tables

![49faa284f30d9278095c18d47ae0e99e51bf13f235374ef748f0cb85dbe1ca19.jpg](../nips_results/1148_Last-Iterate%20Convergence%20of%20Smooth%20Regret%20Matching%24%5E%2B%24%20Variants%20in%20Learning%20Nash%20Equilibria/tables/49faa284f30d9278095c18d47ae0e99e51bf13f235374ef748f0cb85dbe1ca19.jpg)

![6c69a4744f98dd873188d396f64c1bfeca9520f2a3554bcb14ce7898f662691c.jpg](../nips_results/1148_Last-Iterate%20Convergence%20of%20Smooth%20Regret%20Matching%24%5E%2B%24%20Variants%20in%20Learning%20Nash%20Equilibria/tables/6c69a4744f98dd873188d396f64c1bfeca9520f2a3554bcb14ce7898f662691c.jpg)

![b73096beb6000149902249c01144a627c29abf53abc37fa294a297d2649a248e.jpg](../nips_results/1148_Last-Iterate%20Convergence%20of%20Smooth%20Regret%20Matching%24%5E%2B%24%20Variants%20in%20Learning%20Nash%20Equilibria/tables/b73096beb6000149902249c01144a627c29abf53abc37fa294a297d2649a248e.jpg)

![c5ab3ec749926910b5076673fe90a12521ed62fcbcfc728537da16247a47c705.jpg](../nips_results/1148_Last-Iterate%20Convergence%20of%20Smooth%20Regret%20Matching%24%5E%2B%24%20Variants%20in%20Learning%20Nash%20Equilibria/tables/c5ab3ec749926910b5076673fe90a12521ed62fcbcfc728537da16247a47c705.jpg)

![fbbbb9402059ae07c6ce880665390a025fe3cbef897e7e3e1d074ba3c30f8033.jpg](../nips_results/1148_Last-Iterate%20Convergence%20of%20Smooth%20Regret%20Matching%24%5E%2B%24%20Variants%20in%20Learning%20Nash%20Equilibria/tables/fbbbb9402059ae07c6ce880665390a025fe3cbef897e7e3e1d074ba3c30f8033.jpg)

## Bilevel ZOFO: Efficient LLM Fine-Tuning and Meta-Training


### Images

![8b59e35244242fd7b3cd200a2931aca92a9a2b1ec70dc699a82fdd1a39691d81.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/images/8b59e35244242fd7b3cd200a2931aca92a9a2b1ec70dc699a82fdd1a39691d81.jpg)

![8e5838c17f030ef3dd4bfaf1ab94fd5d1e53341c6d0dbee6616c44c09f2f5454.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/images/8e5838c17f030ef3dd4bfaf1ab94fd5d1e53341c6d0dbee6616c44c09f2f5454.jpg)

![946e955e7473a85ec3e32081edbe91dd3e4fe049203031daa1e4c8556c21374f.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/images/946e955e7473a85ec3e32081edbe91dd3e4fe049203031daa1e4c8556c21374f.jpg)

![b83cfe1b977e7ea1de6c551483114e21a53d35a3148ab0ee4490411c79dea077.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/images/b83cfe1b977e7ea1de6c551483114e21a53d35a3148ab0ee4490411c79dea077.jpg)

![daedc9074653df37c6a213c3989ed5202cc2cb9ed9abd8a8b8e2fd8ba16400cb.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/images/daedc9074653df37c6a213c3989ed5202cc2cb9ed9abd8a8b8e2fd8ba16400cb.jpg)

![eba0a690d299223d182d28af3c46a4b8988dc80476c72f047fd1c4489b8b420c.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/images/eba0a690d299223d182d28af3c46a4b8988dc80476c72f047fd1c4489b8b420c.jpg)

### Tables

![06405d7984c076274f284fb7bdaf933b3227f9d7a252d6f507d51cc074cf18a2.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/06405d7984c076274f284fb7bdaf933b3227f9d7a252d6f507d51cc074cf18a2.jpg)

![3d539f25b9b97095cc6fbff43141403146539ea340a9d241357e73e6ba59da3d.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/3d539f25b9b97095cc6fbff43141403146539ea340a9d241357e73e6ba59da3d.jpg)

![4d850d02150ccbbd8c70b23f0fcff223a5f376afd9ace0ed196c548a03a857d1.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/4d850d02150ccbbd8c70b23f0fcff223a5f376afd9ace0ed196c548a03a857d1.jpg)

![59717c09b0db67d62273e09a0d6f06b3271f44f4bb92acec60ce149093c7bc6e.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/59717c09b0db67d62273e09a0d6f06b3271f44f4bb92acec60ce149093c7bc6e.jpg)

![642ffa387adc7698c58137fd4e042c0b78e731f312d75046bc3c39c3a30551d9.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/642ffa387adc7698c58137fd4e042c0b78e731f312d75046bc3c39c3a30551d9.jpg)

![6c262426d9e92bcde810547b558c146a93777da01bad33e06e6838d84e16bd35.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/6c262426d9e92bcde810547b558c146a93777da01bad33e06e6838d84e16bd35.jpg)

![6f95ee7ad3887656b265297768699da53d49c929745657022c348d97a8081351.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/6f95ee7ad3887656b265297768699da53d49c929745657022c348d97a8081351.jpg)

![735456a86c2352a5ba91a805cbfd53f4d4b7b3e5c869807391c6772d5338c2ae.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/735456a86c2352a5ba91a805cbfd53f4d4b7b3e5c869807391c6772d5338c2ae.jpg)

![7c690f7933e7b8586efa406e3f93aa84cfc38cc5ec7a8fc929f865adf3ff3030.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/7c690f7933e7b8586efa406e3f93aa84cfc38cc5ec7a8fc929f865adf3ff3030.jpg)

![9986bb1a7e2fca7a8f90ca5479c36057ee5e97803db790275a8c768dc150e606.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/9986bb1a7e2fca7a8f90ca5479c36057ee5e97803db790275a8c768dc150e606.jpg)

![bf9504be24f4a8217ab8bd811ffbc36e5bfe44d307b7b90aa9c3357a2c544593.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/bf9504be24f4a8217ab8bd811ffbc36e5bfe44d307b7b90aa9c3357a2c544593.jpg)

![cc6fba2dc805399f04c964ad041b5b3ec78bfdb69b03cc6a280c80d4b9e93b5f.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/cc6fba2dc805399f04c964ad041b5b3ec78bfdb69b03cc6a280c80d4b9e93b5f.jpg)

![db80d45c5c881aa5f368c6c5d2f9db80fc89c0d043690264f0fdd048f0affadb.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/db80d45c5c881aa5f368c6c5d2f9db80fc89c0d043690264f0fdd048f0affadb.jpg)

![dd19a6c74d8fd16f5d49ebb024defc76b9b4833f4370b317a57fb1865920ff2c.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/dd19a6c74d8fd16f5d49ebb024defc76b9b4833f4370b317a57fb1865920ff2c.jpg)

![e6595d0f84a65d4160e8be28573a81631f94ca35549398acb6b4381d64707aa9.jpg](../nips_results/1149_Bilevel%20ZOFO_%20Efficient%20LLM%20Fine-Tuning%20and%20Meta-Training/tables/e6595d0f84a65d4160e8be28573a81631f94ca35549398acb6b4381d64707aa9.jpg)

## Flex-Judge: Text-Only Reasoning Unleashes Zero-Shot Multimodal Evaluators


### Images

![076ece10f6c38595417cd7ae91cdb4ff7a0f8b333c630eda0bea9414362370de.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/076ece10f6c38595417cd7ae91cdb4ff7a0f8b333c630eda0bea9414362370de.jpg)

![1adba8bde1c1c2c22812780d22979a5f816284c71f37b9a2ae870a5786eb8859.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/1adba8bde1c1c2c22812780d22979a5f816284c71f37b9a2ae870a5786eb8859.jpg)

![39eb27b2c625e0909e25b42502bf6241c014240416448cf600667f1d27a288cb.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/39eb27b2c625e0909e25b42502bf6241c014240416448cf600667f1d27a288cb.jpg)

![3a51edb04a6677c95888722bb9da2a95df955b8596d282b040f8daaca985762b.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/3a51edb04a6677c95888722bb9da2a95df955b8596d282b040f8daaca985762b.jpg)

![504f3216bcdd0ee7e9b72ce169cd6891bc0f5ecec722b47a0f8bd254cca84d60.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/504f3216bcdd0ee7e9b72ce169cd6891bc0f5ecec722b47a0f8bd254cca84d60.jpg)

![6b9ec5e50348e3a2c66048310eb5cfab67b88c220671f71a58e03ca60596d7c4.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/6b9ec5e50348e3a2c66048310eb5cfab67b88c220671f71a58e03ca60596d7c4.jpg)

![6c24f28c0e914b6dee470611440d310e186803a0dab1a9c21dbc24cb5ebadd54.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/6c24f28c0e914b6dee470611440d310e186803a0dab1a9c21dbc24cb5ebadd54.jpg)

![7398514bd79e86a6d431638ae65c2319162ba9ecb8172a238419b47cbb26be82.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/7398514bd79e86a6d431638ae65c2319162ba9ecb8172a238419b47cbb26be82.jpg)

![7a43b797e9edf3a3fec0c45a971e3ddff127ec7712b71b109e938a2ce2c6d161.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/7a43b797e9edf3a3fec0c45a971e3ddff127ec7712b71b109e938a2ce2c6d161.jpg)

![b6c940a8f2dbbac07b3173b873aabea56ba3f6334fdf7dda5ea29835b4979d3c.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/b6c940a8f2dbbac07b3173b873aabea56ba3f6334fdf7dda5ea29835b4979d3c.jpg)

![c1c11761abf57964c1f67dd1a13ec940dd17ebe17c00bec9738566699dd85ee9.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/c1c11761abf57964c1f67dd1a13ec940dd17ebe17c00bec9738566699dd85ee9.jpg)

![ca20d8d402af9236e4b35ee3320c7bb3ba5ddc3e9ca9098be871f95c452dd881.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/ca20d8d402af9236e4b35ee3320c7bb3ba5ddc3e9ca9098be871f95c452dd881.jpg)

![d70e49d106250e5e00a85bed315105fd3b03ebcf5ff608ad151fc835b3ee862f.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/d70e49d106250e5e00a85bed315105fd3b03ebcf5ff608ad151fc835b3ee862f.jpg)

![e3641c19b03b061786064e305ba3e09028e40b3a86188dbebfa570e88edc19d5.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/e3641c19b03b061786064e305ba3e09028e40b3a86188dbebfa570e88edc19d5.jpg)

![e54309a952716a5019f20c6e54a1c66565007c9f38d3c5088d2b4f3e16e610f9.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/e54309a952716a5019f20c6e54a1c66565007c9f38d3c5088d2b4f3e16e610f9.jpg)

![e8f9844b6c7c2ccb7f6357b7d000fc4c481e0d5a293f88b612ded3423bd5a4f8.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/e8f9844b6c7c2ccb7f6357b7d000fc4c481e0d5a293f88b612ded3423bd5a4f8.jpg)

![e910931735a220476e534bbed500bf0a314a7f5123c467e99269443a5b23468d.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/e910931735a220476e534bbed500bf0a314a7f5123c467e99269443a5b23468d.jpg)

![eb0d06a021bd38a52232118af36d833ddfbc56f49c9cfa9bbff84ff9c7a1409a.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/eb0d06a021bd38a52232118af36d833ddfbc56f49c9cfa9bbff84ff9c7a1409a.jpg)

![f5978682ef926f4a17ac5637131c830aaae3c4071f264517a9c6d44624bc7b20.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/f5978682ef926f4a17ac5637131c830aaae3c4071f264517a9c6d44624bc7b20.jpg)

![f9d837cdb22abd7b2eb154adfdd16e399cdd73297b4a4bba437371f6288f7842.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/images/f9d837cdb22abd7b2eb154adfdd16e399cdd73297b4a4bba437371f6288f7842.jpg)

### Tables

![014ec2161fc761c9f08d21e3f845bff36b8a89f881018723da40496bee788b87.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/014ec2161fc761c9f08d21e3f845bff36b8a89f881018723da40496bee788b87.jpg)

![072c0dec629901b63e03a4febfc9bef7467de620d821d38d7d222e3598abddf1.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/072c0dec629901b63e03a4febfc9bef7467de620d821d38d7d222e3598abddf1.jpg)

![0c1b2d4665f5fa9a6c224d5ff55d9f09c9a2cdf6c5afdc1b6ace872f091a42d6.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/0c1b2d4665f5fa9a6c224d5ff55d9f09c9a2cdf6c5afdc1b6ace872f091a42d6.jpg)

![2d85249105fbce82a1545076a453b68d8979ac04630ff0ac5910e1e3b0446219.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/2d85249105fbce82a1545076a453b68d8979ac04630ff0ac5910e1e3b0446219.jpg)

![2fd6c8e5bde24fb3e28f4b0977b708a7529a2b2c7c9b23a2d31c223456a852ea.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/2fd6c8e5bde24fb3e28f4b0977b708a7529a2b2c7c9b23a2d31c223456a852ea.jpg)

![3d1d45507a1d33d77efd4570d383ddb33dc7352e2a9d968c697e61b766f99d73.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/3d1d45507a1d33d77efd4570d383ddb33dc7352e2a9d968c697e61b766f99d73.jpg)

![4e4fc9a9f1fdf50bd0643b36dfbc68bb2d976f2ca35db7530639b9a8ebad7505.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/4e4fc9a9f1fdf50bd0643b36dfbc68bb2d976f2ca35db7530639b9a8ebad7505.jpg)

![50d17a01d254a05e62f9bd6de4eb060e335bb4424cb5d305ac4c2a41207ef411.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/50d17a01d254a05e62f9bd6de4eb060e335bb4424cb5d305ac4c2a41207ef411.jpg)

![7bc487983b2ddd96cd138635374270aaf142e4d513ce601de00d026e62fd9368.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/7bc487983b2ddd96cd138635374270aaf142e4d513ce601de00d026e62fd9368.jpg)

![823573b65b4a119c3a5af7eb1224dabb4a987112bc7caa44433fb5eb41b3074d.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/823573b65b4a119c3a5af7eb1224dabb4a987112bc7caa44433fb5eb41b3074d.jpg)

![8b8c961b34b2ce6a941c8805adba9866ea5a7798114d1361c90ec49d84331b04.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/8b8c961b34b2ce6a941c8805adba9866ea5a7798114d1361c90ec49d84331b04.jpg)

![b5c63456419adac18748960859dc45ba72f4e8af413cdb4059128a07c856a82d.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/b5c63456419adac18748960859dc45ba72f4e8af413cdb4059128a07c856a82d.jpg)

![edba085c6e034099f029840782f0b02c18bff42d541dcc1412293b71f5781768.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/edba085c6e034099f029840782f0b02c18bff42d541dcc1412293b71f5781768.jpg)

![f73cdab05dd7c4fa319246901ccf97dc756f538e349a33986f876c074440f415.jpg](../nips_results/1150_Flex-Judge_%20Text-Only%20Reasoning%20Unleashes%20Zero-Shot%20Multimodal%20Evaluators/tables/f73cdab05dd7c4fa319246901ccf97dc756f538e349a33986f876c074440f415.jpg)

## LangHOPS: Language Grounded Hierarchical Open-Vocabulary Part Segmentation


### Images

![2e92f76c6c8905005b0fccfc1263fc2bea75c9237f25be745740260079b11bae.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/images/2e92f76c6c8905005b0fccfc1263fc2bea75c9237f25be745740260079b11bae.jpg)

![2ffa826fe66a83e45a11f214dd39aa4f9d38fc26da953ec1101f9b02e141b23d.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/images/2ffa826fe66a83e45a11f214dd39aa4f9d38fc26da953ec1101f9b02e141b23d.jpg)

![3e05a63797763ddfad41607c269fd9498e5267d4bc69e79e81d8a721567b39a3.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/images/3e05a63797763ddfad41607c269fd9498e5267d4bc69e79e81d8a721567b39a3.jpg)

![607c6c4adc321ff76d18c0ef4f0ea261993efe00b72cf6a5c0a67a5c0dbbd5ab.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/images/607c6c4adc321ff76d18c0ef4f0ea261993efe00b72cf6a5c0a67a5c0dbbd5ab.jpg)

![84c3c1fff05e458d9fff11af86ec1905126918344a01e977e1cf015c2bdf2ad7.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/images/84c3c1fff05e458d9fff11af86ec1905126918344a01e977e1cf015c2bdf2ad7.jpg)

### Tables

![028362992797d6350a2a029e71dc88b43c28419ed54555049d8af442f4843d27.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/028362992797d6350a2a029e71dc88b43c28419ed54555049d8af442f4843d27.jpg)

![130b477e8b42fa2d35ffa3d0cd46de40584e16bfe944e147220180db9e43a6bd.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/130b477e8b42fa2d35ffa3d0cd46de40584e16bfe944e147220180db9e43a6bd.jpg)

![193f132b754468967a3ffa703cd74b15f09d37d73cdfba28f2ec0fe2001ec2aa.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/193f132b754468967a3ffa703cd74b15f09d37d73cdfba28f2ec0fe2001ec2aa.jpg)

![2033003f452eea9a3509a911e20ddf3312588763e8eabf0f81765d840536c585.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/2033003f452eea9a3509a911e20ddf3312588763e8eabf0f81765d840536c585.jpg)

![28fb2298d8aa9fac827720c176b8589a47504c897717310cea5ff94c2c89205e.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/28fb2298d8aa9fac827720c176b8589a47504c897717310cea5ff94c2c89205e.jpg)

![4c23b40ebdccea44054925651243542614fcc6a0a96f2b6c43c174a47c34b65a.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/4c23b40ebdccea44054925651243542614fcc6a0a96f2b6c43c174a47c34b65a.jpg)

![5c66394c315c423bb58016d9deddcfa174a8a4fc2bab953ae38a43610935dec5.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/5c66394c315c423bb58016d9deddcfa174a8a4fc2bab953ae38a43610935dec5.jpg)

![65d9f44e53242f8d2233fb9d6c74d8f143fd41cdb2c44d9483e833c5243f19d1.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/65d9f44e53242f8d2233fb9d6c74d8f143fd41cdb2c44d9483e833c5243f19d1.jpg)

![771b56871abe2b948420cf6c5db46f4745125630f7c974837c27cbbc77de9217.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/771b56871abe2b948420cf6c5db46f4745125630f7c974837c27cbbc77de9217.jpg)

![796280488a97c1ecdfba026c7ef5ddb9c0daa08b60004610a93fc4ac6a72e2b1.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/796280488a97c1ecdfba026c7ef5ddb9c0daa08b60004610a93fc4ac6a72e2b1.jpg)

![9a9daf2a4f8aa896adbf05eb7f559a6ed8ca7b7f7dc6771521783dd34f83db6e.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/9a9daf2a4f8aa896adbf05eb7f559a6ed8ca7b7f7dc6771521783dd34f83db6e.jpg)

![9d498869e379753dc361f328ee2cdc26acfee2f173c0f76739fa9b708bcdd5ba.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/9d498869e379753dc361f328ee2cdc26acfee2f173c0f76739fa9b708bcdd5ba.jpg)

![b01973d1fe87791480f6ee9f6cc700c7135346f092061346596ceca02fb53268.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/b01973d1fe87791480f6ee9f6cc700c7135346f092061346596ceca02fb53268.jpg)

![bec6c53ce6cbfa5738c83358708ba53342f2de14feb804ecc235bea7083fcc16.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/bec6c53ce6cbfa5738c83358708ba53342f2de14feb804ecc235bea7083fcc16.jpg)

![c431235e8f9a2fa033cc016e34c89b079184587fa715559b21cf020ef64f452d.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/c431235e8f9a2fa033cc016e34c89b079184587fa715559b21cf020ef64f452d.jpg)

![d1b2f893bce1daff9f011651a1769c51ab2cc9b2fae8a5d49a6f177216b05320.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/d1b2f893bce1daff9f011651a1769c51ab2cc9b2fae8a5d49a6f177216b05320.jpg)

![dbb46478868fc8fb229574418e54c0a574e838b4dcaf77c9e5f5a5ef12928c94.jpg](../nips_results/1151_LangHOPS_%20Language%20Grounded%20Hierarchical%20Open-Vocabulary%20Part%20Segmentation/tables/dbb46478868fc8fb229574418e54c0a574e838b4dcaf77c9e5f5a5ef12928c94.jpg)

## Generalization Guarantees for Learning Score-Based Branch-and-Cut Policies in Integer Programming


### Images

![f192db46f304a21645614a29da9a86c128a954129f7a6f380786f87be945c27b.jpg](../nips_results/1152_Generalization%20Guarantees%20for%20Learning%20Score-Based%20Branch-and-Cut%20Policies%20in%20Integer%20Programming/images/f192db46f304a21645614a29da9a86c128a954129f7a6f380786f87be945c27b.jpg)

## CG-SSL: Concept-Guided Self-Supervised Learning


### Images

![13f270ecf342a9b7aaea3649e96118f11dacac08f32aa9213328504a13c20359.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/images/13f270ecf342a9b7aaea3649e96118f11dacac08f32aa9213328504a13c20359.jpg)

![2104e1ed2bb48deb0c3abe7fe1bdf29eb9b406cd9da8215a07d21c1fa43ddc86.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/images/2104e1ed2bb48deb0c3abe7fe1bdf29eb9b406cd9da8215a07d21c1fa43ddc86.jpg)

![29db0bfb8a244851deebbc558a82d3fbc37d8aa3bdec15cf4149e0dbcced83ab.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/images/29db0bfb8a244851deebbc558a82d3fbc37d8aa3bdec15cf4149e0dbcced83ab.jpg)

![2df1f413c209d21184ae08e7fb9c163c9af2294bc5b7cfdfe984ffc92715267c.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/images/2df1f413c209d21184ae08e7fb9c163c9af2294bc5b7cfdfe984ffc92715267c.jpg)

![3f8f0675e404b2a207190118970512bc94e124999b8a91cf05a35888d607a793.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/images/3f8f0675e404b2a207190118970512bc94e124999b8a91cf05a35888d607a793.jpg)

![4c07e72c0b316ee3ce0bb30d7cf1eb2c589f903f6dfd1538731fa92aaa58a14f.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/images/4c07e72c0b316ee3ce0bb30d7cf1eb2c589f903f6dfd1538731fa92aaa58a14f.jpg)

![625a85435924c65f3beaa9807efe16f1c8529fd8abc8ab5f08f96dd1b1a162af.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/images/625a85435924c65f3beaa9807efe16f1c8529fd8abc8ab5f08f96dd1b1a162af.jpg)

![aeafda757de1b09f4b008db017d123c32f0289e6b2992150e397aacb860d492e.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/images/aeafda757de1b09f4b008db017d123c32f0289e6b2992150e397aacb860d492e.jpg)

![e82b704795c4b3cd145ea7cd47e596c1c91fa304b01484d3921eba04d688bdf7.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/images/e82b704795c4b3cd145ea7cd47e596c1c91fa304b01484d3921eba04d688bdf7.jpg)

### Tables

![175fbfe7e6907a21a7940c02a285c3fcd87c5621fbd3a6154beebb4be1b674d8.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/175fbfe7e6907a21a7940c02a285c3fcd87c5621fbd3a6154beebb4be1b674d8.jpg)

![19b7fff1bb72beb0ebae301f090e7e2e6bdb99888c7b982494f1ccc933bb5a4c.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/19b7fff1bb72beb0ebae301f090e7e2e6bdb99888c7b982494f1ccc933bb5a4c.jpg)

![2ab6e6e006c12f03f00750d1a6aa7370e0e07cf00ad61c4a6412615a558a7b3b.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/2ab6e6e006c12f03f00750d1a6aa7370e0e07cf00ad61c4a6412615a558a7b3b.jpg)

![389cb71cc5567ab8a772fcda18fc515b4c9202cf3fced0a2f238fde6fb68d680.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/389cb71cc5567ab8a772fcda18fc515b4c9202cf3fced0a2f238fde6fb68d680.jpg)

![3fafe2852f81378546a0e4e27484e5156439436f1947d8aceabc0bc1bfa7cd09.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/3fafe2852f81378546a0e4e27484e5156439436f1947d8aceabc0bc1bfa7cd09.jpg)

![42bd016943f063c05b1d16cc609a5a8ec6130c3741ade03102a370b0dc4cc27c.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/42bd016943f063c05b1d16cc609a5a8ec6130c3741ade03102a370b0dc4cc27c.jpg)

![6e4788eca040612b2efe848a912c59925c55f20d847400d17634edb20cd3ea26.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/6e4788eca040612b2efe848a912c59925c55f20d847400d17634edb20cd3ea26.jpg)

![882bce895a250cc8a4866c81ee71c0699a06545b401989dd33d9ca9e2766a841.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/882bce895a250cc8a4866c81ee71c0699a06545b401989dd33d9ca9e2766a841.jpg)

![91b57075927bd2a37ef6f77e2288c668c58c3b45f3768902f6b53c4fe1910d41.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/91b57075927bd2a37ef6f77e2288c668c58c3b45f3768902f6b53c4fe1910d41.jpg)

![a7ed7c5e0b5b7734249c51a0c696c68bff84c8b138750301ff116ad840e23910.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/a7ed7c5e0b5b7734249c51a0c696c68bff84c8b138750301ff116ad840e23910.jpg)

![c72a3912c15ff2b9bedf30f28182c23af9910b54ad15d9c8d49a0f53155d2ac0.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/c72a3912c15ff2b9bedf30f28182c23af9910b54ad15d9c8d49a0f53155d2ac0.jpg)

![de77c387962fddcde95a172aea85e34ef7663f042dca93b03603b264b53d2850.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/de77c387962fddcde95a172aea85e34ef7663f042dca93b03603b264b53d2850.jpg)

![f05ee8f7e89dcc6968de125c70a453d99b5f23b675a7227882b2d555a3d7bc97.jpg](../nips_results/1153_CG-SSL_%20Concept-Guided%20Self-Supervised%20Learning/tables/f05ee8f7e89dcc6968de125c70a453d99b5f23b675a7227882b2d555a3d7bc97.jpg)

## SimulMEGA: MoE Routers are Advanced Policy Makers for Simultaneous Speech Translation


### Images

![122b3cb07a00bf4702db64032f3859a38472fc55860bd2b8ff66dfbd258fe86e.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/images/122b3cb07a00bf4702db64032f3859a38472fc55860bd2b8ff66dfbd258fe86e.jpg)

![12dfdcad109141d10a1e7521c886c032100e9ea1bbaaad21ed2a972c8a1dc486.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/images/12dfdcad109141d10a1e7521c886c032100e9ea1bbaaad21ed2a972c8a1dc486.jpg)

![2cf0cccb8139aae444bd0f75080e3283a1100244e95692e4aca21faea3bac39f.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/images/2cf0cccb8139aae444bd0f75080e3283a1100244e95692e4aca21faea3bac39f.jpg)

![45bda5c2300adf2ca405938517ca2c0cd40438bdaa0cc92a1907184da83013cf.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/images/45bda5c2300adf2ca405938517ca2c0cd40438bdaa0cc92a1907184da83013cf.jpg)

![6247566e855a76c3e5fa855924031b0c79c223aaa4b3e2b00fdb1aa12c1b5bc0.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/images/6247566e855a76c3e5fa855924031b0c79c223aaa4b3e2b00fdb1aa12c1b5bc0.jpg)

![9728bc92bc5f703daf09e06f6a734c1f9bff224b8d9d467b2cd1bf2e20d6c5b4.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/images/9728bc92bc5f703daf09e06f6a734c1f9bff224b8d9d467b2cd1bf2e20d6c5b4.jpg)

![d7560ba838541c9e2e4de495adb6dcafed7218e1b2fe4b2209f411af3c51216e.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/images/d7560ba838541c9e2e4de495adb6dcafed7218e1b2fe4b2209f411af3c51216e.jpg)

![dbe59caffb916e5885457d5f77fe7b2418c8abe0117548febd76f205df3c3790.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/images/dbe59caffb916e5885457d5f77fe7b2418c8abe0117548febd76f205df3c3790.jpg)

![f4be87d30d1069f3ff2ea021ecc72383055d073b390c61a5982f9c5403fb1823.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/images/f4be87d30d1069f3ff2ea021ecc72383055d073b390c61a5982f9c5403fb1823.jpg)

### Tables

![2760d693a26ce0be32425dbf41f84632e061c09bf8f39b2d88b7e2893ce43f6c.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/tables/2760d693a26ce0be32425dbf41f84632e061c09bf8f39b2d88b7e2893ce43f6c.jpg)

![2aaf3bd607efadb05cf543e85a5a78b250a098f86b94725c530b64b2f2f853b4.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/tables/2aaf3bd607efadb05cf543e85a5a78b250a098f86b94725c530b64b2f2f853b4.jpg)

![4c6eaa2cd5519ae8c0b2771de0919e13f6b6c3ed6db9838ad40f34e27da94e10.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/tables/4c6eaa2cd5519ae8c0b2771de0919e13f6b6c3ed6db9838ad40f34e27da94e10.jpg)

![540903aeba0326f15fbca61b05dc8cc2efdecba9405ae44373870beae919a570.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/tables/540903aeba0326f15fbca61b05dc8cc2efdecba9405ae44373870beae919a570.jpg)

![d1a87e9f8bf34bd27ede8c45eda1cf3def3fdbcae91d24c6e4eb9551132e6c5e.jpg](../nips_results/1154_SimulMEGA_%20MoE%20Routers%20are%20Advanced%20Policy%20Makers%20for%20Simultaneous%20Speech%20Translation/tables/d1a87e9f8bf34bd27ede8c45eda1cf3def3fdbcae91d24c6e4eb9551132e6c5e.jpg)

## Size-adaptive Hypothesis Testing for Fairness


### Images

![0464eb59c5a54cec86bac9670254aa85bce582d0b193832ed5359718925e44d5.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/0464eb59c5a54cec86bac9670254aa85bce582d0b193832ed5359718925e44d5.jpg)

![0b760e2a48dd592263b0c13fe1bcaf6a7d2bd82df8796cb1fbf671fa02684eb6.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/0b760e2a48dd592263b0c13fe1bcaf6a7d2bd82df8796cb1fbf671fa02684eb6.jpg)

![0e3e596280fae9990d22201aaa35df9debcdc6ae72cc68878b20f8cf2f64efc9.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/0e3e596280fae9990d22201aaa35df9debcdc6ae72cc68878b20f8cf2f64efc9.jpg)

![0e3fb9778c3396c9908fd051641d355044bead58d1a27a194ada5cc863a018fc.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/0e3fb9778c3396c9908fd051641d355044bead58d1a27a194ada5cc863a018fc.jpg)

![10632d5839b483a59631b6e7fa9362af0cd478ad7b75b42c9657669ac1677371.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/10632d5839b483a59631b6e7fa9362af0cd478ad7b75b42c9657669ac1677371.jpg)

![1119d0c78aa21178d1766055f7ed19c6073c993a48e1812b44827222475a73e9.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/1119d0c78aa21178d1766055f7ed19c6073c993a48e1812b44827222475a73e9.jpg)

![12b611abe2524870eff6e43eb0d97ca44199055383747fae9fd161ac2f7dbe94.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/12b611abe2524870eff6e43eb0d97ca44199055383747fae9fd161ac2f7dbe94.jpg)

![1f4a63f1a8344463c6fabde75064140e4ee312c9378186c9299d6274a0bd28a4.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/1f4a63f1a8344463c6fabde75064140e4ee312c9378186c9299d6274a0bd28a4.jpg)

![2373c95def0e1c6506bd6dd8aef7785969dc14a91c2863095997fda2536528b8.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/2373c95def0e1c6506bd6dd8aef7785969dc14a91c2863095997fda2536528b8.jpg)

![2416f869c1caea34d424440d62d0b5a64fa483a516c0c7313580b1a39d5ed81e.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/2416f869c1caea34d424440d62d0b5a64fa483a516c0c7313580b1a39d5ed81e.jpg)

![247762d26f127f50f779b348e4250944fb7fdc495971b7ac10333e1c58819481.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/247762d26f127f50f779b348e4250944fb7fdc495971b7ac10333e1c58819481.jpg)

![3c60f2c8aac2046b1f276653d255663572b51ca5b70e0da26666beeedb0cd28b.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/3c60f2c8aac2046b1f276653d255663572b51ca5b70e0da26666beeedb0cd28b.jpg)

![432f24777c473e566f9fb7ffb8aaecdf7a846f3aa61410b42cc816c093c1f5bf.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/432f24777c473e566f9fb7ffb8aaecdf7a846f3aa61410b42cc816c093c1f5bf.jpg)

![533ae8d1b3598500179ea688c0430805c82b9ed26aab663ef1f934a877c47be2.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/533ae8d1b3598500179ea688c0430805c82b9ed26aab663ef1f934a877c47be2.jpg)

![55cb55936a7f5227bf075755eb8ec62f5cd749746e991d6ade63eb918b821143.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/55cb55936a7f5227bf075755eb8ec62f5cd749746e991d6ade63eb918b821143.jpg)

![56d0850ecfc3fe47cf6d97a0e93307b79d47657f77fc4c324a54be6dbf5a1856.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/56d0850ecfc3fe47cf6d97a0e93307b79d47657f77fc4c324a54be6dbf5a1856.jpg)

![5791368d08b2b6d5284bfe07d1b7b273dc090dc0241cca61f61431e6a7f85242.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/5791368d08b2b6d5284bfe07d1b7b273dc090dc0241cca61f61431e6a7f85242.jpg)

![57a8ae05394c9b3c763f7b5a96f063dec9c90a6c0081f68442009da1853cce37.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/57a8ae05394c9b3c763f7b5a96f063dec9c90a6c0081f68442009da1853cce37.jpg)

![5898ae9da217d79ee2b60eaa26ca5666245b6cbb56931d5b676ef9c9d76718a7.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/5898ae9da217d79ee2b60eaa26ca5666245b6cbb56931d5b676ef9c9d76718a7.jpg)

![59b192f2efe5ff452f583fcfdc3c04f2ab7d957f69f6018b99644af8e43c2dd5.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/59b192f2efe5ff452f583fcfdc3c04f2ab7d957f69f6018b99644af8e43c2dd5.jpg)

![5bc0cacba461f35f236abedb630fb92fc5c9760af5205542422e79e6b375c568.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/5bc0cacba461f35f236abedb630fb92fc5c9760af5205542422e79e6b375c568.jpg)

![5bd644cfac41bfd2959366d1ba38de94b36a085f04b81bba44c2e21b90c26915.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/5bd644cfac41bfd2959366d1ba38de94b36a085f04b81bba44c2e21b90c26915.jpg)

![61efed872389ac449a81d66851c93f94f44381fb1f636162afd5543859bf4a8f.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/61efed872389ac449a81d66851c93f94f44381fb1f636162afd5543859bf4a8f.jpg)

![6526c0d188e5fe2e36ec3f275d8e69f6224b8c184562d6196fdcb2a7da5e7dd6.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/6526c0d188e5fe2e36ec3f275d8e69f6224b8c184562d6196fdcb2a7da5e7dd6.jpg)

![6b8db65037a12ce0e4ab7f3d56ea93039f276c7abd2dff219335853549bfe401.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/6b8db65037a12ce0e4ab7f3d56ea93039f276c7abd2dff219335853549bfe401.jpg)

![6ef8437f69f0421a3740ec950afa52ac6208c0eca00e3d3634c19a59743d64f2.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/6ef8437f69f0421a3740ec950afa52ac6208c0eca00e3d3634c19a59743d64f2.jpg)

![7489b19ffa50021e07487f78cc989eec2714575ca6eb099ef9195f7fda1c02fd.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/7489b19ffa50021e07487f78cc989eec2714575ca6eb099ef9195f7fda1c02fd.jpg)

![7ba91fd61322ef38675dce66d5862b15d45752061d4da3a0019b1305afd1416b.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/7ba91fd61322ef38675dce66d5862b15d45752061d4da3a0019b1305afd1416b.jpg)

![7d1b8a00f842e3cc10abdafe988f19ebc94547d442f25b4262b52cae5b7f8bae.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/7d1b8a00f842e3cc10abdafe988f19ebc94547d442f25b4262b52cae5b7f8bae.jpg)

![7eb413f139666eb14bd65a3feeee00ddf9450bdd6d552309e6c8208299ee7257.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/7eb413f139666eb14bd65a3feeee00ddf9450bdd6d552309e6c8208299ee7257.jpg)

![81077062c15e6ea6521e3ac28a8307decd8201deb3f725f81974bc9f07d64143.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/81077062c15e6ea6521e3ac28a8307decd8201deb3f725f81974bc9f07d64143.jpg)

![8e4048fb20f9459cd13ff9469d81ba34d42e3e151cd2331592af6db4dbd58745.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/8e4048fb20f9459cd13ff9469d81ba34d42e3e151cd2331592af6db4dbd58745.jpg)

![97fdbbcf524e15f391ac2778fa246eccfa2c233ca2c22f0479a407f550242c87.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/97fdbbcf524e15f391ac2778fa246eccfa2c233ca2c22f0479a407f550242c87.jpg)

![a2b6a62b87fcae5f08ee679c705aff0e9532f42e4d612c15b710baa153d848d3.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/a2b6a62b87fcae5f08ee679c705aff0e9532f42e4d612c15b710baa153d848d3.jpg)

![ab571fee1542ed49ec2eab6451b8fc05a1cbe9bfede68dfca3f373875e46f31c.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/ab571fee1542ed49ec2eab6451b8fc05a1cbe9bfede68dfca3f373875e46f31c.jpg)

![adae9890639a361f3f4fd54833e4232e7d4251a85ac01b01466f6ecbe21d9694.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/adae9890639a361f3f4fd54833e4232e7d4251a85ac01b01466f6ecbe21d9694.jpg)

![af3df9e8c9fdc687a3c147601b7e266b2f5002b3e8b70983deffc84963ee2b7a.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/af3df9e8c9fdc687a3c147601b7e266b2f5002b3e8b70983deffc84963ee2b7a.jpg)

![ba31b938edea5e0c38ad62e8ddac9f4186687e80a1a8b335b3c605ef0bdbf3f9.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/ba31b938edea5e0c38ad62e8ddac9f4186687e80a1a8b335b3c605ef0bdbf3f9.jpg)

![bc5d26b310257c27753fd295ab7e4e2c8e8a3228e7a97be78f153fdb03f28ac1.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/bc5d26b310257c27753fd295ab7e4e2c8e8a3228e7a97be78f153fdb03f28ac1.jpg)

![c7e47f2c1dca190bd6b192098824bfc6c5dd197119c8af3cd3f463c5a479989b.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/c7e47f2c1dca190bd6b192098824bfc6c5dd197119c8af3cd3f463c5a479989b.jpg)

![c9e17204b47b9cc6042ce28068edbf76d4d687aba904373a42ad9daf15f96935.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/c9e17204b47b9cc6042ce28068edbf76d4d687aba904373a42ad9daf15f96935.jpg)

![d134a9be889d1c0db9822ae46bd4f197d2e7c9eac3196ee170fa900bb3900451.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/d134a9be889d1c0db9822ae46bd4f197d2e7c9eac3196ee170fa900bb3900451.jpg)

![d5b6e61b3cde29c7fc63300faad7209fcbc9125f80054b491c04c5336dd753a8.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/d5b6e61b3cde29c7fc63300faad7209fcbc9125f80054b491c04c5336dd753a8.jpg)

![d96513c4ca2261a72c6f3e072946529b2e67fb36554387d2867ab23085e39866.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/d96513c4ca2261a72c6f3e072946529b2e67fb36554387d2867ab23085e39866.jpg)

![da5c6f242980dabec1af3d2d5868d4b94ee4d12f417219e43414cb1ae1e12ac5.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/da5c6f242980dabec1af3d2d5868d4b94ee4d12f417219e43414cb1ae1e12ac5.jpg)

![db1012ad296e3d23f85632107629017ecd9fc986be5cac25bad62394e4c91e72.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/db1012ad296e3d23f85632107629017ecd9fc986be5cac25bad62394e4c91e72.jpg)

![dcff3a1bfe2fa58d0fe9a226923dd4db96a87295e89e30c9ab7942a75fc76c3e.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/dcff3a1bfe2fa58d0fe9a226923dd4db96a87295e89e30c9ab7942a75fc76c3e.jpg)

![e4b91c7db3534039771b397ae418efa41bc842427ac45e37b1b1168a7f97f944.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/e4b91c7db3534039771b397ae418efa41bc842427ac45e37b1b1168a7f97f944.jpg)

![ee4688bff86445b3ee6d4b4ff7cd0abf4253e550b6e9eadbc970f429b87d5313.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/ee4688bff86445b3ee6d4b4ff7cd0abf4253e550b6e9eadbc970f429b87d5313.jpg)

![f2ec9f6cb990f1b5c4b83d8dbeea718974c50235a265ae169dd1f991c7e9c49a.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/f2ec9f6cb990f1b5c4b83d8dbeea718974c50235a265ae169dd1f991c7e9c49a.jpg)

![f7f6ec56406b2246611c133f3a8a317cd131d0c9d604333e8f261c4611e47f36.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/f7f6ec56406b2246611c133f3a8a317cd131d0c9d604333e8f261c4611e47f36.jpg)

![fe78f86f5d18abbdbcb31e13ecd16e66658da1993f3e04a3ce2c838d1b050570.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/images/fe78f86f5d18abbdbcb31e13ecd16e66658da1993f3e04a3ce2c838d1b050570.jpg)

### Tables

![2b47d3e9b30dd19aae7498a869ef0307622fb8bf3bb1d21252051e5a7f54a86f.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/tables/2b47d3e9b30dd19aae7498a869ef0307622fb8bf3bb1d21252051e5a7f54a86f.jpg)

![a2ad77f557d4933431ca90627ba29cf75a399c0e6ef427036fb6ef25ee1892b0.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/tables/a2ad77f557d4933431ca90627ba29cf75a399c0e6ef427036fb6ef25ee1892b0.jpg)

![e0376034977b34f06152e4c0c1f9e1f4050e81fe5284131679e6370525e769f0.jpg](../nips_results/1155_Size-adaptive%20Hypothesis%20Testing%20for%20Fairness/tables/e0376034977b34f06152e4c0c1f9e1f4050e81fe5284131679e6370525e769f0.jpg)

## Towards Irreversible Attack: Fooling Scene Text Recognition via Multi-Population Coevolution Search


### Images

![153106855cbe34d2cb58cf5f51b493059f21b8ac6c2628fbd6a26f26144d1f7c.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/images/153106855cbe34d2cb58cf5f51b493059f21b8ac6c2628fbd6a26f26144d1f7c.jpg)

![7d421cff5dcddb0b43cd009b1ec3e161aa9b217edc2b182e19977f2d6fcefeac.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/images/7d421cff5dcddb0b43cd009b1ec3e161aa9b217edc2b182e19977f2d6fcefeac.jpg)

![8e7e5bc7fbf1bf0c2e0d36c7f678549f2d3f1b5e5082009641d856e926f3129b.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/images/8e7e5bc7fbf1bf0c2e0d36c7f678549f2d3f1b5e5082009641d856e926f3129b.jpg)

![8e8a767d77f58bc1f1280f7954f1aa1f017ca760d0c329609cbbdc73a1d689e2.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/images/8e8a767d77f58bc1f1280f7954f1aa1f017ca760d0c329609cbbdc73a1d689e2.jpg)

![a99c820ac24fe5b54ee9000e92c020f93c32665c438e478ffe3980f7c10c9816.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/images/a99c820ac24fe5b54ee9000e92c020f93c32665c438e478ffe3980f7c10c9816.jpg)

![b8ff805ae84fb439575a35e06dc366014b86c089a33665dc6f15bafc88a55d4b.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/images/b8ff805ae84fb439575a35e06dc366014b86c089a33665dc6f15bafc88a55d4b.jpg)

![d12f3d851ac378bdc2d465443c7030225b524a1b2c7090b394e89b0489721d7d.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/images/d12f3d851ac378bdc2d465443c7030225b524a1b2c7090b394e89b0489721d7d.jpg)

![d6f71ca22c37b8edf466d846989b34a6fd8ab6269c6b9787c539c91ca66f6eef.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/images/d6f71ca22c37b8edf466d846989b34a6fd8ab6269c6b9787c539c91ca66f6eef.jpg)

![dc74a399510e128201a744232831e282281671dded62df1f2ea1a4018c05cef9.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/images/dc74a399510e128201a744232831e282281671dded62df1f2ea1a4018c05cef9.jpg)

![f019aa4e3eb0aa81a4c0cc2e57ff5d4553391d014a24fda78fc2725a7542b4fc.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/images/f019aa4e3eb0aa81a4c0cc2e57ff5d4553391d014a24fda78fc2725a7542b4fc.jpg)

![fc01b6976816a774e6f62c245869e8a76ae9641fc50e892f4614621e47a49230.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/images/fc01b6976816a774e6f62c245869e8a76ae9641fc50e892f4614621e47a49230.jpg)

### Tables

![4a4615b412c2be9e483229d39ddb1d0d76f155564f3ee773bafd54f2a4b9d7ba.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/tables/4a4615b412c2be9e483229d39ddb1d0d76f155564f3ee773bafd54f2a4b9d7ba.jpg)

![50e373b4ea35c34f9e69abe8921665ca7eee36779aa47ffd6fc507996a5a1f59.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/tables/50e373b4ea35c34f9e69abe8921665ca7eee36779aa47ffd6fc507996a5a1f59.jpg)

![81dff51b483192e1c56225cc9b9d5e5bb9ca902e0179a1fb68a6b83c47500b12.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/tables/81dff51b483192e1c56225cc9b9d5e5bb9ca902e0179a1fb68a6b83c47500b12.jpg)

![b534e3af796b4e40cd06bcb937e9c5fc03499786154406dc580e11715281b256.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/tables/b534e3af796b4e40cd06bcb937e9c5fc03499786154406dc580e11715281b256.jpg)

![e01e81c5de8ca4bc24577eba73f2c2cf9a483ad7a5949f6c646ed31081d3252d.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/tables/e01e81c5de8ca4bc24577eba73f2c2cf9a483ad7a5949f6c646ed31081d3252d.jpg)

![ee141e98ddfda122b890a8c28e94a49ae3383d17907ac9d5d55b48e8271df040.jpg](../nips_results/1156_Towards%20Irreversible%20Attack_%20Fooling%20Scene%20Text%20Recognition%20via%20Multi-Population%20Coevolution%20Search/tables/ee141e98ddfda122b890a8c28e94a49ae3383d17907ac9d5d55b48e8271df040.jpg)

## The Logical Expressiveness of Temporal GNNs via Two-Dimensional Product Logics


### Images

![2e3013c7eb49b62b9e20660e17dff9d0f4cd7c7508b49407b4f9e641c7ff1f8a.jpg](../nips_results/1157_The%20Logical%20Expressiveness%20of%20Temporal%20GNNs%20via%20Two-Dimensional%20Product%20Logics/images/2e3013c7eb49b62b9e20660e17dff9d0f4cd7c7508b49407b4f9e641c7ff1f8a.jpg)

![4ceaf9df41efbfc029060d53e26028fd7bb82f165030cdf5362abfc43462d880.jpg](../nips_results/1157_The%20Logical%20Expressiveness%20of%20Temporal%20GNNs%20via%20Two-Dimensional%20Product%20Logics/images/4ceaf9df41efbfc029060d53e26028fd7bb82f165030cdf5362abfc43462d880.jpg)

![4e3ecbc21e976ab911a66eddece5b18ef9bfb615e9c87dfa410eb3d8a532bbec.jpg](../nips_results/1157_The%20Logical%20Expressiveness%20of%20Temporal%20GNNs%20via%20Two-Dimensional%20Product%20Logics/images/4e3ecbc21e976ab911a66eddece5b18ef9bfb615e9c87dfa410eb3d8a532bbec.jpg)

![f9ed20838ac2768f28752b1c2935cfdd32774799143a07ae4ef05f2883426bab.jpg](../nips_results/1157_The%20Logical%20Expressiveness%20of%20Temporal%20GNNs%20via%20Two-Dimensional%20Product%20Logics/images/f9ed20838ac2768f28752b1c2935cfdd32774799143a07ae4ef05f2883426bab.jpg)

## On the Relation between Rectified Flows and Optimal Transport


### Images

![07c5548dd4834320daaad5c323e2c51e3577edf78d0b3ed3a6a62a586c990d1e.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/07c5548dd4834320daaad5c323e2c51e3577edf78d0b3ed3a6a62a586c990d1e.jpg)

![161645372e9f7eb54ea5464c1c663c04a138e4675dd98af21e2523bf18690dfa.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/161645372e9f7eb54ea5464c1c663c04a138e4675dd98af21e2523bf18690dfa.jpg)

![1e32e3d9638fa06732d21dc5eb25700465b5fc6fab9f9c4ee4cff603ee00a23f.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/1e32e3d9638fa06732d21dc5eb25700465b5fc6fab9f9c4ee4cff603ee00a23f.jpg)

![2d9a8fec925bd9f80a6b398f7abc738756c2b3a8215d5ffc9d5c6eb837d225a8.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/2d9a8fec925bd9f80a6b398f7abc738756c2b3a8215d5ffc9d5c6eb837d225a8.jpg)

![34b9ffef41016f4f4d96da0b16795915efa556924d0623f73ba5cf8da46663ec.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/34b9ffef41016f4f4d96da0b16795915efa556924d0623f73ba5cf8da46663ec.jpg)

![36c084133f42ed0c7cd6cb87f2252d180940b8462428aa96f4b0e1c78ddea858.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/36c084133f42ed0c7cd6cb87f2252d180940b8462428aa96f4b0e1c78ddea858.jpg)

![46b4f813deff9e7c48be8c0712a6322c16b59750149d4718b92e8d122ad38682.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/46b4f813deff9e7c48be8c0712a6322c16b59750149d4718b92e8d122ad38682.jpg)

![48927465aeb78d9794b248796eba0a7fc9290e82b11e8cd76c28df8a3da79f1a.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/48927465aeb78d9794b248796eba0a7fc9290e82b11e8cd76c28df8a3da79f1a.jpg)

![5b6e807f636ef3685e7678d9277fc0b296970cc8425ea302802facca6ee316bb.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/5b6e807f636ef3685e7678d9277fc0b296970cc8425ea302802facca6ee316bb.jpg)

![746a7103fb120bce495189182726822cede6c90f9942bfb80f1fca55b5709d87.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/746a7103fb120bce495189182726822cede6c90f9942bfb80f1fca55b5709d87.jpg)

![74832dd8d59bd4d4a220253a4e3fa0d7486464c72b5b312c657843f8f8e56216.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/74832dd8d59bd4d4a220253a4e3fa0d7486464c72b5b312c657843f8f8e56216.jpg)

![91f86abe3a09f28de567ef809b76c89625b7b6708465243068bddeade48d9d0e.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/91f86abe3a09f28de567ef809b76c89625b7b6708465243068bddeade48d9d0e.jpg)

![ad0cbea619316a9d1e16a0d5d2360cfae8f5b8f572402a0fd2dee466f7a85de0.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/ad0cbea619316a9d1e16a0d5d2360cfae8f5b8f572402a0fd2dee466f7a85de0.jpg)

![bcd37ae4111f60df56fbb1ed9e532c50216c6e846eb1a11d31611107b1bcc639.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/bcd37ae4111f60df56fbb1ed9e532c50216c6e846eb1a11d31611107b1bcc639.jpg)

![d2755321fe037b2f3869059c8c6c291075bbca548aca24703ae07a733cc067dd.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/d2755321fe037b2f3869059c8c6c291075bbca548aca24703ae07a733cc067dd.jpg)

![d528094783d6e65ea6f6645ef09208d9c95b6b1a29e2ccbdc3cc0f0a3d1eb118.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/d528094783d6e65ea6f6645ef09208d9c95b6b1a29e2ccbdc3cc0f0a3d1eb118.jpg)

![ff593592b0579d8b1e9497c84012d0b3bbcb6e66bbb94f21c0e2f0db881e98ad.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/images/ff593592b0579d8b1e9497c84012d0b3bbcb6e66bbb94f21c0e2f0db881e98ad.jpg)

### Tables

![6b109711a108a1ba7f3d84a96c42dba3f0402262f858fa65f666920772e1afca.jpg](../nips_results/1158_On%20the%20Relation%20between%20Rectified%20Flows%20and%20Optimal%20Transport/tables/6b109711a108a1ba7f3d84a96c42dba3f0402262f858fa65f666920772e1afca.jpg)

## A Plug-and-Play Query Synthesis Active Learning Framework for Neural PDE Solvers


### Images

![104e73211f6fa34d7c06a5a1c38a683bcb5d93bf05264b3e9b7a94bc55a9ebd1.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/images/104e73211f6fa34d7c06a5a1c38a683bcb5d93bf05264b3e9b7a94bc55a9ebd1.jpg)

![21809b3f6d682f839693d345612112812493d13511b339d45447849a4cc7faf0.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/images/21809b3f6d682f839693d345612112812493d13511b339d45447849a4cc7faf0.jpg)

![225259af5a2e31365cd9e6d90511b63f17cb92805bbf37c4103130b75b944ca5.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/images/225259af5a2e31365cd9e6d90511b63f17cb92805bbf37c4103130b75b944ca5.jpg)

![44fa2f7418d62ad90e2d2ac493ef2869d11a4ee8b638a8c4498e1d0e38a1e2e9.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/images/44fa2f7418d62ad90e2d2ac493ef2869d11a4ee8b638a8c4498e1d0e38a1e2e9.jpg)

![565089cd714e3a5336335d80e1ec6e48a1a8a6136b56f2eaf314b3f89a700c80.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/images/565089cd714e3a5336335d80e1ec6e48a1a8a6136b56f2eaf314b3f89a700c80.jpg)

![91a01e8cfa8e846284290bda3e554b5b4f34c4e8cf78c197c979820fbfd1db56.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/images/91a01e8cfa8e846284290bda3e554b5b4f34c4e8cf78c197c979820fbfd1db56.jpg)

![a4542498bf302d1a22a4e10d6743d9ace72a3c9c4e39c0192b8ed5d079ce6077.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/images/a4542498bf302d1a22a4e10d6743d9ace72a3c9c4e39c0192b8ed5d079ce6077.jpg)

![ac221691b1a5d20c71be3ef36292b4dbdf438d6409a5a88521daaf2817dd245c.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/images/ac221691b1a5d20c71be3ef36292b4dbdf438d6409a5a88521daaf2817dd245c.jpg)

![c393c2a278855015908635cd86fccc08a7999ca2c379d674efdae9324f5ea740.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/images/c393c2a278855015908635cd86fccc08a7999ca2c379d674efdae9324f5ea740.jpg)

### Tables

![4371e08d08ade72d6e44273424806260ddc6ca2216371f30a6ff4585f87601a1.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/tables/4371e08d08ade72d6e44273424806260ddc6ca2216371f30a6ff4585f87601a1.jpg)

![7bd06f1f0fe45a6bff4b70bc5f475fa04bac43ffc4772ac70f6d7af966f0c8ae.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/tables/7bd06f1f0fe45a6bff4b70bc5f475fa04bac43ffc4772ac70f6d7af966f0c8ae.jpg)

![8df3c4f656df8870f30215571e1df452303a85f26e5f75b8089073f10e7ef52f.jpg](../nips_results/1159_A%20Plug-and-Play%20Query%20Synthesis%20Active%20Learning%20Framework%20for%20Neural%20PDE%20Solvers/tables/8df3c4f656df8870f30215571e1df452303a85f26e5f75b8089073f10e7ef52f.jpg)

## Improving Data Efficiency for LLM Reinforcement Fine-tuning Through Difficulty-targeted Online Data Selection and Rollout Replay


### Images

![14601c86bfc1587126b5889b611b1fd467d622025e5a4d05a5d4916fa2e2d7df.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/14601c86bfc1587126b5889b611b1fd467d622025e5a4d05a5d4916fa2e2d7df.jpg)

![2afbe9a25fe85b67edc2de56943d54b26e304748685b7af68c75af5fa5caea58.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/2afbe9a25fe85b67edc2de56943d54b26e304748685b7af68c75af5fa5caea58.jpg)

![3b60adb83ce41513b3c1b6dee58531a4becdfbb47d19e61850a2c2c35d82cfe0.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/3b60adb83ce41513b3c1b6dee58531a4becdfbb47d19e61850a2c2c35d82cfe0.jpg)

![42bc4d8d847a9bf74236022e10c65545238100d7773cd6cc6be8dac430e132b5.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/42bc4d8d847a9bf74236022e10c65545238100d7773cd6cc6be8dac430e132b5.jpg)

![62e944354989d428f4d3b154cb10a72db5fb83139cd21e67557d212e908f1cc7.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/62e944354989d428f4d3b154cb10a72db5fb83139cd21e67557d212e908f1cc7.jpg)

![75d2fac13d454099325a6fe3f28d338d7008942c3c80293c3cb460f11c478a06.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/75d2fac13d454099325a6fe3f28d338d7008942c3c80293c3cb460f11c478a06.jpg)

![7a5be347422baa199c88d379077be524e6cebcc208d3a6480763777ce8a31dc7.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/7a5be347422baa199c88d379077be524e6cebcc208d3a6480763777ce8a31dc7.jpg)

![85bc53c019fc51e186a50fb0dd8895383997e15e90a866fd80b2620d9fc95727.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/85bc53c019fc51e186a50fb0dd8895383997e15e90a866fd80b2620d9fc95727.jpg)

![9f371a8c0d7f3cc16fe67c4945ac1c6e651e3fbac134c80ec7063275eb45c02f.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/9f371a8c0d7f3cc16fe67c4945ac1c6e651e3fbac134c80ec7063275eb45c02f.jpg)

![a55620e241de13c6441724bb949b52f5ad510efafc7c7c61ec00b4eac0d0cb7c.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/a55620e241de13c6441724bb949b52f5ad510efafc7c7c61ec00b4eac0d0cb7c.jpg)

![b377caa657734b84e9340652e15ee6978c3c8fcb67a2aec3f91a651a792a5ae9.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/b377caa657734b84e9340652e15ee6978c3c8fcb67a2aec3f91a651a792a5ae9.jpg)

![fc15c461e054cdb5e3fe8c3fcd96163d1fb51178bfd7c57edd49c77264db320d.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/images/fc15c461e054cdb5e3fe8c3fcd96163d1fb51178bfd7c57edd49c77264db320d.jpg)

### Tables

![25bd15759a3b1febc9e5bf318cf726f6d0c7ef6a4a1230127039238c710f1b29.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/tables/25bd15759a3b1febc9e5bf318cf726f6d0c7ef6a4a1230127039238c710f1b29.jpg)

![3b429c09e52ffeaddcbc1f07c65b5f5c83417ac445a0b2e6e794a2bfea097299.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/tables/3b429c09e52ffeaddcbc1f07c65b5f5c83417ac445a0b2e6e794a2bfea097299.jpg)

![4753c7169c07aea5a1e550bbf23465bcec8d32b347ce5163d4956d15818a0915.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/tables/4753c7169c07aea5a1e550bbf23465bcec8d32b347ce5163d4956d15818a0915.jpg)

![4798f4a18bb5362ab9658892b310c0160096896669f5629cc5b0b3a6100c53c4.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/tables/4798f4a18bb5362ab9658892b310c0160096896669f5629cc5b0b3a6100c53c4.jpg)

![92d6a55f0c5c11eaec5aff506fa059601029add60d141b1f69d7620ca89a1bb2.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/tables/92d6a55f0c5c11eaec5aff506fa059601029add60d141b1f69d7620ca89a1bb2.jpg)

![9377dffe3f833452fe042398a9ea9351132f1112c42b77361034e65d1c9d1dc9.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/tables/9377dffe3f833452fe042398a9ea9351132f1112c42b77361034e65d1c9d1dc9.jpg)

![a1fe1c6df7193c8fccc8bfbe6e4da416fadff0f44a448f996f9a6d00d5fbf0e5.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/tables/a1fe1c6df7193c8fccc8bfbe6e4da416fadff0f44a448f996f9a6d00d5fbf0e5.jpg)

![ecdfc4149565848d1343d46c2be1b4878510e424fd11719ff2304932249f7926.jpg](../nips_results/1160_Improving%20Data%20Efficiency%20for%20LLM%20Reinforcement%20Fine-tuning%20Through%20Difficulty-targeted%20Online%20Data%20/tables/ecdfc4149565848d1343d46c2be1b4878510e424fd11719ff2304932249f7926.jpg)

## A*-Thought: Efficient Reasoning via Bidirectional Compression for Low-Resource Settings


### Images

![0fb2ceec611b4d996f77a07d83e69f019b7e14b27414e3722839cbd3ef5b1a77.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/images/0fb2ceec611b4d996f77a07d83e69f019b7e14b27414e3722839cbd3ef5b1a77.jpg)

![2f6c2af511fee6d7eefa61ffd88871df687782610193b30795577ff2c64fd2d0.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/images/2f6c2af511fee6d7eefa61ffd88871df687782610193b30795577ff2c64fd2d0.jpg)

![348fa9c5bb22b4f90d31b8fe70de33ea8fd537d6400d18aedfc8c0539bf22342.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/images/348fa9c5bb22b4f90d31b8fe70de33ea8fd537d6400d18aedfc8c0539bf22342.jpg)

![4b9b728945bdb1a0935e1c75e3c39c285dbb733f466f886490701dcd15b4fadc.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/images/4b9b728945bdb1a0935e1c75e3c39c285dbb733f466f886490701dcd15b4fadc.jpg)

![554b732c4d3f5267d6b870d16192974abd4a9742d0116c75a2534ea97602fbf3.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/images/554b732c4d3f5267d6b870d16192974abd4a9742d0116c75a2534ea97602fbf3.jpg)

![6d9b075641f07f72134bcc85f8d3dd354b7546bd0393ac48ff434fbb8345178f.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/images/6d9b075641f07f72134bcc85f8d3dd354b7546bd0393ac48ff434fbb8345178f.jpg)

![71b0ba58d64af3e2d9f8cd457b994af457c4f9053ce13b0ff8147492fcb82369.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/images/71b0ba58d64af3e2d9f8cd457b994af457c4f9053ce13b0ff8147492fcb82369.jpg)

![73fcb6a98426c8fc20a7516b60f73f046cef66ecc9e42577ad7bdd357d9a9e0f.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/images/73fcb6a98426c8fc20a7516b60f73f046cef66ecc9e42577ad7bdd357d9a9e0f.jpg)

![d7bbd78f17118c1aabc62a2c768e4130ea4816e8b38f209d57aac88346cd2807.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/images/d7bbd78f17118c1aabc62a2c768e4130ea4816e8b38f209d57aac88346cd2807.jpg)

![e9a30d07f3c1f22d21bc4cbfa3578ccccaa164777645a4d2f010ff4c66690d44.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/images/e9a30d07f3c1f22d21bc4cbfa3578ccccaa164777645a4d2f010ff4c66690d44.jpg)

![ffae6a2abb2c9c6d7070537bfa79ebafd07b7682c1d273adc8fc0d742d44bd84.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/images/ffae6a2abb2c9c6d7070537bfa79ebafd07b7682c1d273adc8fc0d742d44bd84.jpg)

### Tables

![0fc9de72cbe724bc38a23f9f1e1aa4c074275e4b404119b39bd47256b0e22933.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/tables/0fc9de72cbe724bc38a23f9f1e1aa4c074275e4b404119b39bd47256b0e22933.jpg)

![1c83b02de58a8a91b938a1e0cfce07606ae3ab7de25f9195c2fc8e648937ded4.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/tables/1c83b02de58a8a91b938a1e0cfce07606ae3ab7de25f9195c2fc8e648937ded4.jpg)

![3d43d2cef71d8e85523a5728fd4f14f2b16f487bcf27bf25d3a6df28f9c3fd83.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/tables/3d43d2cef71d8e85523a5728fd4f14f2b16f487bcf27bf25d3a6df28f9c3fd83.jpg)

![6a88e44e1d12aa1e6351a91707d7b9cf91d0b457b4d9e3013ea3fc59ee095ddb.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/tables/6a88e44e1d12aa1e6351a91707d7b9cf91d0b457b4d9e3013ea3fc59ee095ddb.jpg)

![7119c146d1abe076d1bcf613748ddc062495161e01a525c258dbe9273084c9dd.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/tables/7119c146d1abe076d1bcf613748ddc062495161e01a525c258dbe9273084c9dd.jpg)

![807624aebae2a1779954f755d545094dac7b63badb43666c0590afc82f5721f3.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/tables/807624aebae2a1779954f755d545094dac7b63badb43666c0590afc82f5721f3.jpg)

![8abcc40c490f7867dd8c67303387484548d5b70f0320eb491d27724af82542f8.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/tables/8abcc40c490f7867dd8c67303387484548d5b70f0320eb491d27724af82542f8.jpg)

![8b8f2c12cb4a6b36411211642c25f3595f544605433e68a41ab7922353c6b739.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/tables/8b8f2c12cb4a6b36411211642c25f3595f544605433e68a41ab7922353c6b739.jpg)

![8c16098c93ee47b2ef8c4d98938b5c38936f0b9f1a1a13ddd0a4c9b11947274b.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/tables/8c16098c93ee47b2ef8c4d98938b5c38936f0b9f1a1a13ddd0a4c9b11947274b.jpg)

![9df7549100b42d37e8e105091480866b7dd4952dc2ce362bb0916c2dc361392b.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/tables/9df7549100b42d37e8e105091480866b7dd4952dc2ce362bb0916c2dc361392b.jpg)

![a71d96495d767456b88f863987f190846aa888ad975fae57033cd61c702b2d3a.jpg](../nips_results/1161_A_-Thought_%20Efficient%20Reasoning%20via%20Bidirectional%20Compression%20for%20Low-Resource%20Settings/tables/a71d96495d767456b88f863987f190846aa888ad975fae57033cd61c702b2d3a.jpg)

## Attack via Overfitting: 10-shot Benign Fine-tuning to Jailbreak LLMs


### Images

![1c1e06ccc6bad6f0e5073405170b9aaa0cecbca4517c0fe689873c8ffb07dfbc.jpg](../nips_results/1162_Attack%20via%20Overfitting_%2010-shot%20Benign%20Fine-tuning%20to%20Jailbreak%20LLMs/images/1c1e06ccc6bad6f0e5073405170b9aaa0cecbca4517c0fe689873c8ffb07dfbc.jpg)

![2c37b39c7f7055534952ad7855d20cbb0c1a7d46d510f4f0e152c47fbdbebd87.jpg](../nips_results/1162_Attack%20via%20Overfitting_%2010-shot%20Benign%20Fine-tuning%20to%20Jailbreak%20LLMs/images/2c37b39c7f7055534952ad7855d20cbb0c1a7d46d510f4f0e152c47fbdbebd87.jpg)

![5af59ccf9aae3e647cec4b2c935c4dbae684e127cf4fc4105c5a72c5742639d8.jpg](../nips_results/1162_Attack%20via%20Overfitting_%2010-shot%20Benign%20Fine-tuning%20to%20Jailbreak%20LLMs/images/5af59ccf9aae3e647cec4b2c935c4dbae684e127cf4fc4105c5a72c5742639d8.jpg)

![7777001cefdbdb07afe60be7e61fafd3a5c4b58062ac140dc307b0a1ebd70179.jpg](../nips_results/1162_Attack%20via%20Overfitting_%2010-shot%20Benign%20Fine-tuning%20to%20Jailbreak%20LLMs/images/7777001cefdbdb07afe60be7e61fafd3a5c4b58062ac140dc307b0a1ebd70179.jpg)

![90da3723b8721360baeaa0e618006979e44be8f679d8b630cc85e5f6ac3485b1.jpg](../nips_results/1162_Attack%20via%20Overfitting_%2010-shot%20Benign%20Fine-tuning%20to%20Jailbreak%20LLMs/images/90da3723b8721360baeaa0e618006979e44be8f679d8b630cc85e5f6ac3485b1.jpg)

![e14352b36adb3def3b1bc592bf3b35ebaa0bd3ad3acb34e1fe674891e5f9f3b0.jpg](../nips_results/1162_Attack%20via%20Overfitting_%2010-shot%20Benign%20Fine-tuning%20to%20Jailbreak%20LLMs/images/e14352b36adb3def3b1bc592bf3b35ebaa0bd3ad3acb34e1fe674891e5f9f3b0.jpg)

![ec8d2b126683a6404566be575669e10eff419ebd072a0228df9a8f0635a491d6.jpg](../nips_results/1162_Attack%20via%20Overfitting_%2010-shot%20Benign%20Fine-tuning%20to%20Jailbreak%20LLMs/images/ec8d2b126683a6404566be575669e10eff419ebd072a0228df9a8f0635a491d6.jpg)

### Tables

![1f2581a708ede053e50d60de081f6c3a2bf200ab9d453967e1e28041a37c12c5.jpg](../nips_results/1162_Attack%20via%20Overfitting_%2010-shot%20Benign%20Fine-tuning%20to%20Jailbreak%20LLMs/tables/1f2581a708ede053e50d60de081f6c3a2bf200ab9d453967e1e28041a37c12c5.jpg)

![5b63cefa51fd913cd366bff8a05c89494a2c97f00ab9ef4a124ca53ca0c63fac.jpg](../nips_results/1162_Attack%20via%20Overfitting_%2010-shot%20Benign%20Fine-tuning%20to%20Jailbreak%20LLMs/tables/5b63cefa51fd913cd366bff8a05c89494a2c97f00ab9ef4a124ca53ca0c63fac.jpg)

![83d15a1eabdbb763d8813655b1292e0025f36db7d175c81555a9a7fae79e7ca6.jpg](../nips_results/1162_Attack%20via%20Overfitting_%2010-shot%20Benign%20Fine-tuning%20to%20Jailbreak%20LLMs/tables/83d15a1eabdbb763d8813655b1292e0025f36db7d175c81555a9a7fae79e7ca6.jpg)

![c037c58c26ef18865174bbe310b71ad456c8f1dea533595a09ca844b59d6ec28.jpg](../nips_results/1162_Attack%20via%20Overfitting_%2010-shot%20Benign%20Fine-tuning%20to%20Jailbreak%20LLMs/tables/c037c58c26ef18865174bbe310b71ad456c8f1dea533595a09ca844b59d6ec28.jpg)

## A Generalist Intracortical Motor Decoder


### Images

![1aeb75719d174683975f0e2261c26ca8c049b6390e16456e06260b87f18885d8.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/1aeb75719d174683975f0e2261c26ca8c049b6390e16456e06260b87f18885d8.jpg)

![1b46942709d2eb95d19ab67541db3d8c8d2477652f68f910a160b5788477fc28.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/1b46942709d2eb95d19ab67541db3d8c8d2477652f68f910a160b5788477fc28.jpg)

![20d6149fb917e9804ee0a7f759e7074f6fea819b10f680a75490f548e62a6654.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/20d6149fb917e9804ee0a7f759e7074f6fea819b10f680a75490f548e62a6654.jpg)

![2937c438a9dc092cab3862291f7ba5442b5293323ecb07ac241799ef197babea.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/2937c438a9dc092cab3862291f7ba5442b5293323ecb07ac241799ef197babea.jpg)

![3bb0d323c7371d1b20fa91a9fcab290332e43f459c338460b33f73095781f16e.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/3bb0d323c7371d1b20fa91a9fcab290332e43f459c338460b33f73095781f16e.jpg)

![40c8c206fac814aa8412cf624185839b483658d2bd1b198c5c8c927835417313.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/40c8c206fac814aa8412cf624185839b483658d2bd1b198c5c8c927835417313.jpg)

![5a039265911d9da59122e062eabf03dfc2fc0ccf3287ec413a471dfba840d681.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/5a039265911d9da59122e062eabf03dfc2fc0ccf3287ec413a471dfba840d681.jpg)

![64cec3d6ff2bd634cc04f54700a82b3477961794d4419842ffe311bf85e57fac.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/64cec3d6ff2bd634cc04f54700a82b3477961794d4419842ffe311bf85e57fac.jpg)

![8a823eb528451623af601e90eb2cdcf9eeaee4a5b2535e7d8bc5dd6120e96a51.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/8a823eb528451623af601e90eb2cdcf9eeaee4a5b2535e7d8bc5dd6120e96a51.jpg)

![8d9e7d9fb207e9ce8569594cb368658bcdefaa7af8415e54ce1bd3d85b1d86ca.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/8d9e7d9fb207e9ce8569594cb368658bcdefaa7af8415e54ce1bd3d85b1d86ca.jpg)

![945f2c950ea90336b3a9d72536f4a1498b991864c0c2e12260404d3672ceac7f.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/945f2c950ea90336b3a9d72536f4a1498b991864c0c2e12260404d3672ceac7f.jpg)

![94e98f0023629198372063af26fb4fee40f14f3c25074fd358d46a8681624d17.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/94e98f0023629198372063af26fb4fee40f14f3c25074fd358d46a8681624d17.jpg)

![9ce686f37f1aee2a670f206d50fdae77c08b596705c866a865721cdf38e7880b.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/9ce686f37f1aee2a670f206d50fdae77c08b596705c866a865721cdf38e7880b.jpg)

![aadcde38d3309f99e37a1236e85c678d52805149a873e8d23cbf53a0c75ce52e.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/aadcde38d3309f99e37a1236e85c678d52805149a873e8d23cbf53a0c75ce52e.jpg)

![b7824204ed6b8b5f0ae318cfca12f436a87443ce97f0e9eba85bfa0c8924c273.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/b7824204ed6b8b5f0ae318cfca12f436a87443ce97f0e9eba85bfa0c8924c273.jpg)

![ca585fce3e82e3bb45f9619782e394090ce00513bfd7b9525978b5f0285307a1.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/ca585fce3e82e3bb45f9619782e394090ce00513bfd7b9525978b5f0285307a1.jpg)

![f1fdb5a90c911032726c6999abea6253d86efdc2b7e9c095ded1672c11677e9b.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/f1fdb5a90c911032726c6999abea6253d86efdc2b7e9c095ded1672c11677e9b.jpg)

![f845f465f6c149f1e85fc92ee89dcd0771a8b972d738f26945a0734caab4b39b.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/f845f465f6c149f1e85fc92ee89dcd0771a8b972d738f26945a0734caab4b39b.jpg)

![fb4efd4afcf8939fa6199885f982b21e8b822ee9ab43be904fc2886fd6664017.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/images/fb4efd4afcf8939fa6199885f982b21e8b822ee9ab43be904fc2886fd6664017.jpg)

### Tables

![50528cbebc516006e372488cbcb1bef5160683e339635263b9c3e4d931c3be58.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/tables/50528cbebc516006e372488cbcb1bef5160683e339635263b9c3e4d931c3be58.jpg)

![ac40b999c62fa93644ee06b9e7ccf70f813fdf4e185f8ded117df52ad3ad0f4b.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/tables/ac40b999c62fa93644ee06b9e7ccf70f813fdf4e185f8ded117df52ad3ad0f4b.jpg)

![c54be2d4bb1372d331d1901569ee0d975b455191012173c2f4f1b126469e859a.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/tables/c54be2d4bb1372d331d1901569ee0d975b455191012173c2f4f1b126469e859a.jpg)

![ed196876bf801d39e3ea60e92200b2921e4653d05b2a1e78107ef9a344bf928b.jpg](../nips_results/1163_A%20Generalist%20Intracortical%20Motor%20Decoder/tables/ed196876bf801d39e3ea60e92200b2921e4653d05b2a1e78107ef9a344bf928b.jpg)

## InstructRestore: Region-Customized Image Restoration with Human Instructions


### Images

![3e9c5bc62ecc7a750bb18405e71111e142cd0bee8b570a756d696fbd59ec4518.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/images/3e9c5bc62ecc7a750bb18405e71111e142cd0bee8b570a756d696fbd59ec4518.jpg)

![423b6b560f614f417345f7389394233ac93617457ce2dea68b54868adbe0ade9.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/images/423b6b560f614f417345f7389394233ac93617457ce2dea68b54868adbe0ade9.jpg)

![50a3eaf128cab87dee5b7e66f13e86651772839d0a972f1f0aec56ab2dd83079.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/images/50a3eaf128cab87dee5b7e66f13e86651772839d0a972f1f0aec56ab2dd83079.jpg)

![50adf2fb2a87153b35a8a8597feb4f7df3ab752d1e038fd23de68af37e282abd.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/images/50adf2fb2a87153b35a8a8597feb4f7df3ab752d1e038fd23de68af37e282abd.jpg)

![5fd9d096af891611a6600c3f38ca1e9373a02cc8bf3449aee937c31b403ee3c2.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/images/5fd9d096af891611a6600c3f38ca1e9373a02cc8bf3449aee937c31b403ee3c2.jpg)

![7467a955ae70dc8f6e912724c19f2658ab885fd137b2a308b3c14ae4578fd260.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/images/7467a955ae70dc8f6e912724c19f2658ab885fd137b2a308b3c14ae4578fd260.jpg)

![aad2692a66258a3637e1ebac227643d0ebaa4412315662f21d7c1825c0b11178.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/images/aad2692a66258a3637e1ebac227643d0ebaa4412315662f21d7c1825c0b11178.jpg)

![c915d2ace9defea7aa83a614204b26e211871f2be0ca5f2cbcedefbb08cd702e.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/images/c915d2ace9defea7aa83a614204b26e211871f2be0ca5f2cbcedefbb08cd702e.jpg)

### Tables

![58dc1f46572b87299bca6e0b72043088d930339ddfeac847408fcd1f9e1fabf6.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/tables/58dc1f46572b87299bca6e0b72043088d930339ddfeac847408fcd1f9e1fabf6.jpg)

![5d184f6256bb0da465e40aa1a984647efa60e6b43c0980f3e18178c5341d68db.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/tables/5d184f6256bb0da465e40aa1a984647efa60e6b43c0980f3e18178c5341d68db.jpg)

![64aa5dea5bf27e0a76766d3ea612bbf8ad9bdc5828f62109d8ff2b341aa89372.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/tables/64aa5dea5bf27e0a76766d3ea612bbf8ad9bdc5828f62109d8ff2b341aa89372.jpg)

![97a13ce77f702441208a5df1c9be4e160f79f5a1fe2e0e70d6513f57a02cd469.jpg](../nips_results/1164_InstructRestore_%20Region-Customized%20Image%20Restoration%20with%20Human%20Instructions/tables/97a13ce77f702441208a5df1c9be4e160f79f5a1fe2e0e70d6513f57a02cd469.jpg)

## UFT: Unifying Supervised and Reinforcement Fine-Tuning


### Images

![080c421e3bd7b785a8e0f9cf23ced03ecce4281ee77468cf76378ec7b5a2b633.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/images/080c421e3bd7b785a8e0f9cf23ced03ecce4281ee77468cf76378ec7b5a2b633.jpg)

![1d488ca19c4d6081932e69f041c1d93563444d8c84145ab0f37e498cba5a0fbf.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/images/1d488ca19c4d6081932e69f041c1d93563444d8c84145ab0f37e498cba5a0fbf.jpg)

![456aca32a30b15b0b676b114803a57e62e1c0700a9b19eec2131f4bb21e609de.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/images/456aca32a30b15b0b676b114803a57e62e1c0700a9b19eec2131f4bb21e609de.jpg)

![9a2d4ceb30430a1d77a0b40117587db7c14db620b1e36cbe76f890aedaad30a2.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/images/9a2d4ceb30430a1d77a0b40117587db7c14db620b1e36cbe76f890aedaad30a2.jpg)

![ac00d45a225bf5d74dbc41774c01b28fb4a1db34a0d8aad1ff52e40fbcc6db02.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/images/ac00d45a225bf5d74dbc41774c01b28fb4a1db34a0d8aad1ff52e40fbcc6db02.jpg)

![bdc07b94ec9c93d9c84e85d17ad9867a86c4ebe26778328157e2facd2d1b3f2a.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/images/bdc07b94ec9c93d9c84e85d17ad9867a86c4ebe26778328157e2facd2d1b3f2a.jpg)

![c55420e16740de65b27edcef4c2138e21f74bb4b8167738c1393f758acb0acbf.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/images/c55420e16740de65b27edcef4c2138e21f74bb4b8167738c1393f758acb0acbf.jpg)

![e8338ccad353ab19a832c9c0ac497fcf165aca93b08aed7bb1151e45358df1e0.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/images/e8338ccad353ab19a832c9c0ac497fcf165aca93b08aed7bb1151e45358df1e0.jpg)

![ef242742a24f9ef91802327fcfbb2483ed12c9dcc7033e630a8d18a0ff46e20c.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/images/ef242742a24f9ef91802327fcfbb2483ed12c9dcc7033e630a8d18a0ff46e20c.jpg)

![ef7adba1557e0a76aeb984823b92ee42a69629be9de2bb424ed4e34c844a872f.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/images/ef7adba1557e0a76aeb984823b92ee42a69629be9de2bb424ed4e34c844a872f.jpg)

![f944f7ea6e86dbc56165fe46f89f98ad9932c101ae2113b4857ee3707f28f343.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/images/f944f7ea6e86dbc56165fe46f89f98ad9932c101ae2113b4857ee3707f28f343.jpg)

### Tables

![1a7ab2942076a6ffd69ea4a73167b6144d49ad3a35d33bd8fab21344654b787a.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/tables/1a7ab2942076a6ffd69ea4a73167b6144d49ad3a35d33bd8fab21344654b787a.jpg)

![24c866fc6c47cf3082e27ba432b0a0d3f4710955d1139aa18f8f351941ff917d.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/tables/24c866fc6c47cf3082e27ba432b0a0d3f4710955d1139aa18f8f351941ff917d.jpg)

![a2563e9c0e4820484d3160c39b126abb52e9996dd0f26255528680ec90f2fe25.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/tables/a2563e9c0e4820484d3160c39b126abb52e9996dd0f26255528680ec90f2fe25.jpg)

![c371c06c16e3cf883151c80ed5a8d240cc02931a00d311654599c3d9a3258459.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/tables/c371c06c16e3cf883151c80ed5a8d240cc02931a00d311654599c3d9a3258459.jpg)

![c9296c0086c6bd1dbddaad641386cd056ac3c50e2dd5577ec038493fd8a5fc41.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/tables/c9296c0086c6bd1dbddaad641386cd056ac3c50e2dd5577ec038493fd8a5fc41.jpg)

![cd2bc0e94b30e702af364d3916c87688427a726a6b2ce23862dcdde3ee1dd289.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/tables/cd2bc0e94b30e702af364d3916c87688427a726a6b2ce23862dcdde3ee1dd289.jpg)

![cde85d09c2c483334d51a94d1ac8f39a593efd623788a1e47af92e87c2e5d249.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/tables/cde85d09c2c483334d51a94d1ac8f39a593efd623788a1e47af92e87c2e5d249.jpg)

![d2f5e1e0da8b8563a2904cdb9d59297b1ab6fa8f287c8287de20a91064de3299.jpg](../nips_results/1165_UFT_%20Unifying%20Supervised%20and%20Reinforcement%20Fine-Tuning/tables/d2f5e1e0da8b8563a2904cdb9d59297b1ab6fa8f287c8287de20a91064de3299.jpg)

## A faster training algorithm for regression trees with linear leaves, and an analysis of its complexity


### Images

![17742dce72b1111044a001c8b8761412a65506457e92f38ed3722409a3abec3d.jpg](../nips_results/1166_A%20faster%20training%20algorithm%20for%20regression%20trees%20with%20linear%20leaves%2C%20and%20an%20analysis%20of%20its%20complexi/images/17742dce72b1111044a001c8b8761412a65506457e92f38ed3722409a3abec3d.jpg)

![242c8562f1684356f8fb98bd2162a4c98764a8e0d92f471ac9f1bee0cfd3de42.jpg](../nips_results/1166_A%20faster%20training%20algorithm%20for%20regression%20trees%20with%20linear%20leaves%2C%20and%20an%20analysis%20of%20its%20complexi/images/242c8562f1684356f8fb98bd2162a4c98764a8e0d92f471ac9f1bee0cfd3de42.jpg)

![f02d54924a72009fe49905250e45be075c16f2e5d6ae4c00536256d4c9dbf89e.jpg](../nips_results/1166_A%20faster%20training%20algorithm%20for%20regression%20trees%20with%20linear%20leaves%2C%20and%20an%20analysis%20of%20its%20complexi/images/f02d54924a72009fe49905250e45be075c16f2e5d6ae4c00536256d4c9dbf89e.jpg)

### Tables

![13da351f6b8739d2e149fa71ec43f11e8e796c1986c13b9cf50d8b87dfd18b13.jpg](../nips_results/1166_A%20faster%20training%20algorithm%20for%20regression%20trees%20with%20linear%20leaves%2C%20and%20an%20analysis%20of%20its%20complexi/tables/13da351f6b8739d2e149fa71ec43f11e8e796c1986c13b9cf50d8b87dfd18b13.jpg)

![73e4e87c3bca64e8714f47d9f03d0d8f0e996c476b0cf4ec45526cabada4aa03.jpg](../nips_results/1166_A%20faster%20training%20algorithm%20for%20regression%20trees%20with%20linear%20leaves%2C%20and%20an%20analysis%20of%20its%20complexi/tables/73e4e87c3bca64e8714f47d9f03d0d8f0e996c476b0cf4ec45526cabada4aa03.jpg)

![dd02b2b4e6e55bae61ff853b1ad07331316193a480e7ff67a56a7ad55443d17e.jpg](../nips_results/1166_A%20faster%20training%20algorithm%20for%20regression%20trees%20with%20linear%20leaves%2C%20and%20an%20analysis%20of%20its%20complexi/tables/dd02b2b4e6e55bae61ff853b1ad07331316193a480e7ff67a56a7ad55443d17e.jpg)

![f4c2320acad4a5f7946ec45ee33e0acaf887e9811dc30ce9efc91aa01f5123a6.jpg](../nips_results/1166_A%20faster%20training%20algorithm%20for%20regression%20trees%20with%20linear%20leaves%2C%20and%20an%20analysis%20of%20its%20complexi/tables/f4c2320acad4a5f7946ec45ee33e0acaf887e9811dc30ce9efc91aa01f5123a6.jpg)

![ff6bb33d4cd4492b0ccb1727c6965d60513c81ff63c815a4daeea57ff51b4491.jpg](../nips_results/1166_A%20faster%20training%20algorithm%20for%20regression%20trees%20with%20linear%20leaves%2C%20and%20an%20analysis%20of%20its%20complexi/tables/ff6bb33d4cd4492b0ccb1727c6965d60513c81ff63c815a4daeea57ff51b4491.jpg)

## ReMA: Learning to Meta-Think for LLMs with Multi-agent Reinforcement Learning

### Images

![0bb3f2f0dbe46745b3f61b22568fc378cfe5aebb0c7b39dd5d918fe0683ce906.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/0bb3f2f0dbe46745b3f61b22568fc378cfe5aebb0c7b39dd5d918fe0683ce906.jpg)

![22a01f0211e91f12869dee646e7d405df093308d10010dbc811848569ead3d66.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/22a01f0211e91f12869dee646e7d405df093308d10010dbc811848569ead3d66.jpg)

![3503a32d622da999388999a8b9590b3d3d4a41738bca2704a98725056b8cb27e.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/3503a32d622da999388999a8b9590b3d3d4a41738bca2704a98725056b8cb27e.jpg)

![68e7cdbf26c7ca2778df53fb6fe18f713f8e40eddd5f8837f864b83a069e5c84.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/68e7cdbf26c7ca2778df53fb6fe18f713f8e40eddd5f8837f864b83a069e5c84.jpg)

![7fedf73607a242ee483e457908f53e30bc07b37cdb11d4964a450b45088f31b8.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/7fedf73607a242ee483e457908f53e30bc07b37cdb11d4964a450b45088f31b8.jpg)

![88f6ec17d602e31914b54dc74ec7f778891d2932f7042678a248adabe9f1c87e.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/88f6ec17d602e31914b54dc74ec7f778891d2932f7042678a248adabe9f1c87e.jpg)

![9239d38ff7074ca4b88894a39d854f1cd52dc07db027fd6fa0184fd06565c24b.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/9239d38ff7074ca4b88894a39d854f1cd52dc07db027fd6fa0184fd06565c24b.jpg)

![942b816b4de168a5264f98aead4b4951fade620abb72df2e4d585d429db180ad.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/942b816b4de168a5264f98aead4b4951fade620abb72df2e4d585d429db180ad.jpg)

![99509ba88c3f70c72308cbfe7f6dea770ca7b061f9aa2238a69072588602837a.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/99509ba88c3f70c72308cbfe7f6dea770ca7b061f9aa2238a69072588602837a.jpg)

![9cf493b8547d93bd8214d8ee00f748e4883e2bb7f9c7be29f65a897752c85a8d.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/9cf493b8547d93bd8214d8ee00f748e4883e2bb7f9c7be29f65a897752c85a8d.jpg)

![c9b13e41ce3fb39b7081c13d2f8db30a860c2a5fc22bc9f1f618070ddc9810f0.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/c9b13e41ce3fb39b7081c13d2f8db30a860c2a5fc22bc9f1f618070ddc9810f0.jpg)

![e5b0d7e18f2d9cd4380732a9fd22ed76a0a7743fcd93430014510966a9292a25.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/images/e5b0d7e18f2d9cd4380732a9fd22ed76a0a7743fcd93430014510966a9292a25.jpg)

### Tables

![1acf4f6107c37f33e8009c711e1d0db01fe71c6302d6fd617d54c91c51568e44.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/tables/1acf4f6107c37f33e8009c711e1d0db01fe71c6302d6fd617d54c91c51568e44.jpg)

![260c2314e1af294b979fd9dd42e8aa3b621c393fe21011371abe2fe06859e127.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/tables/260c2314e1af294b979fd9dd42e8aa3b621c393fe21011371abe2fe06859e127.jpg)

![581578685468eef2b11b16b4cfb29cd7af4e4744eb8eb09ca27334d1b3959bf8.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/tables/581578685468eef2b11b16b4cfb29cd7af4e4744eb8eb09ca27334d1b3959bf8.jpg)

![5ba43e140335a430191bf9aad2631fd20ce0079f5ad69a946108097be9af03c0.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/tables/5ba43e140335a430191bf9aad2631fd20ce0079f5ad69a946108097be9af03c0.jpg)

![a37567b4bf81be16345bc12aee3a4e7b924fd8d6fc58e639fd902c650982dd2c.jpg](../nips_results/1167_ReMA_%20Learning%20to%20Meta-Think%20for%20LLMs%20with%20Multi-agent%20Reinforcement%20Learning/tables/a37567b4bf81be16345bc12aee3a4e7b924fd8d6fc58e639fd902c650982dd2c.jpg)
