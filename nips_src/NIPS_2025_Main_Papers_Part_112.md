# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 112 of 130

## 目录 (Table of Contents)

1. [PARCO: Parallel AutoRegressive Models for Multi-Agent Combinatorial Optimization](#PARCO-Parallel-AutoRegressive-Models-for-Multi-Agent-Combinatorial-Optimization)
2. [Anatomically inspired digital twins capture hierarchical object representations in visual cortex](#Anatomically-inspired-digital-twins-capture-hierarchical-object-representations-in-visual-cortex)
3. [NegoCollab: A Common Representation Negotiation Approach for Heterogeneous Collaborative Perception](#NegoCollab-A-Common-Representation-Negotiation-Approach-for-Heterogeneous-Collaborative-Perception)
4. [Optimal kernel regression bounds under energy-bounded noise](#Optimal-kernel-regression-bounds-under-energy-bounded-noise)
5. [GeoAda: Efficiently Finetune Geometric Diffusion Models with Equivariant Adapters](#GeoAda-Efficiently-Finetune-Geometric-Diffusion-Models-with-Equivariant-Adapters)
6. [Task-Specific Data Selection for Instruction Tuning via Monosemantic Neuronal Activations](#Task-Specific-Data-Selection-for-Instruction-Tuning-via-Monosemantic-Neuronal-Activations)
7. [CoT-lized Diffusion: Let's Reinforce T2I Generation Step-by-step](#CoT-lized-Diffusion-Lets-Reinforce-T2I-Generation-Step-by-step)
8. [For Better or for Worse, Transformers Seek Patterns for Memorization](#For-Better-or-for-Worse-Transformers-Seek-Patterns-for-Memorization)
9. [Self supervised learning for in vivo localization of microelectrode arrays using raw local field potential](#Self-supervised-learning-for-in-vivo-localization-of-microelectrode-arrays-using-raw-local-field-potential)
10. [Unlocking Multimodal Mathematical Reasoning via Process Reward Model](#Unlocking-Multimodal-Mathematical-Reasoning-via-Process-Reward-Model)
11. [Prompted Policy Search: Reinforcement Learning through Linguistic and Numerical Reasoning in LLMs](#Prompted-Policy-Search-Reinforcement-Learning-through-Linguistic-and-Numerical-Reasoning-in-LLMs)
12. [Best-of-N Jailbreaking](#Best-of-N-Jailbreaking)
13. [Safety Pretraining: Toward the Next Generation of Safe AI](#Safety-Pretraining-Toward-the-Next-Generation-of-Safe-AI)
14. [Linear Differential Vision Transformer: Learning Visual Contrasts via Pairwise Differentials](#Linear-Differential-Vision-Transformer-Learning-Visual-Contrasts-via-Pairwise-Differentials)
15. [Hierarchical Implicit Neural Emulators](#Hierarchical-Implicit-Neural-Emulators)
16. [RetrievalAttention: Accelerating Long-Context LLM Inference via Vector Retrieval](#RetrievalAttention-Accelerating-Long-Context-LLM-Inference-via-Vector-Retrieval)
17. [Feedback Guidance of Diffusion Models](#Feedback-Guidance-of-Diffusion-Models)
18. [Retrv-R1: A Reasoning-Driven MLLM Framework for Universal and Efficient Multimodal Retrieval](#Retrv-R1-A-Reasoning-Driven-MLLM-Framework-for-Universal-and-Efficient-Multimodal-Retrieval)
19. [LEDiT:  Your Length-Extrapolatable Diffusion Transformer without Positional Encoding](#LEDiT-Your-Length-Extrapolatable-Diffusion-Transformer-without-Positional-Encoding)
20. [Learning from Disjoint Views: A Contrastive Prototype Matching Network for Fully Incomplete Multi-View Clustering](#Learning-from-Disjoint-Views-A-Contrastive-Prototype-Matching-Network-for-Fully-Incomplete-Multi-View-Clustering)
21. [Pool Me Wisely: On the Effect of Pooling in Transformer-Based Models](#Pool-Me-Wisely-On-the-Effect-of-Pooling-in-Transformer-Based-Models)
22. [INST-IT: Boosting Instance Understanding via Explicit Visual Prompt Instruction Tuning](#INST-IT-Boosting-Instance-Understanding-via-Explicit-Visual-Prompt-Instruction-Tuning)
23. [RoPECraft: Training-Free Motion Transfer with Trajectory-Guided RoPE Optimization on Diffusion Transformers](#RoPECraft-Training-Free-Motion-Transfer-with-Trajectory-Guided-RoPE-Optimization-on-Diffusion-Transformers)
24. [Iterative Foundation Model Fine-Tuning on Multiple Rewards](#Iterative-Foundation-Model-Fine-Tuning-on-Multiple-Rewards)
25. [TF-MAS: Training-free Mamba2 Architecture Search](#TF-MAS-Training-free-Mamba2-Architecture-Search)
26. [CryptoMoE: Privacy-Preserving and Scalable Mixture of Experts Inference via Balanced Expert Routing](#CryptoMoE-Privacy-Preserving-and-Scalable-Mixture-of-Experts-Inference-via-Balanced-Expert-Routing)
27. [Transferring Causal Effects using Proxies](#Transferring-Causal-Effects-using-Proxies)
28. [Traversal Verification for Speculative Tree Decoding](#Traversal-Verification-for-Speculative-Tree-Decoding)
29. [PIVNO: Particle Image Velocimetry Neural Operator](#PIVNO-Particle-Image-Velocimetry-Neural-Operator)
30. [Variational Inference with  Mixtures of Isotropic Gaussians](#Variational-Inference-with-Mixtures-of-Isotropic-Gaussians)
31. [Heterogeneous Diffusion Structure Inference for Network Cascade](#Heterogeneous-Diffusion-Structure-Inference-for-Network-Cascade)
32. [Certifying Concavity and Monotonicity in Games via Sum-of-Squares Hierarchies](#Certifying-Concavity-and-Monotonicity-in-Games-via-Sum-of-Squares-Hierarchies)
33. [ADG: Ambient Diffusion-Guided Dataset Recovery for Corruption-Robust Offline Reinforcement Learning](#ADG-Ambient-Diffusion-Guided-Dataset-Recovery-for-Corruption-Robust-Offline-Reinforcement-Learning)
34. [SegGraph: Leveraging Graphs of SAM Segments for Few-Shot 3D Part Segmentation](#SegGraph-Leveraging-Graphs-of-SAM-Segments-for-Few-Shot-3D-Part-Segmentation)
35. [Better NTK Conditioning: A Free Lunch from (ReLU) Nonlinear Activation in Wide Neural Networks](#Better-NTK-Conditioning-A-Free-Lunch-from-ReLU-Nonlinear-Activation-in-Wide-Neural-Networks)
36. [VaMP: Variational Multi-Modal Prompt Learning for Vision-Language Models](#VaMP-Variational-Multi-Modal-Prompt-Learning-for-Vision-Language-Models)
37. [Inference-Time Hyper-Scaling with KV Cache Compression](#Inference-Time-Hyper-Scaling-with-KV-Cache-Compression)
38. [AdaMSS: Adaptive Multi-Subspace Approach for Parameter-Efficient Fine-Tuning](#AdaMSS-Adaptive-Multi-Subspace-Approach-for-Parameter-Efficient-Fine-Tuning)
39. [JAMUN: Bridging Smoothed Molecular Dynamics and Score-Based Learning for Conformational Ensemble Generation](#JAMUN-Bridging-Smoothed-Molecular-Dynamics-and-Score-Based-Learning-for-Conformational-Ensemble-Generation)
40. [Detecting High-Stakes Interactions with Activation Probes](#Detecting-High-Stakes-Interactions-with-Activation-Probes)
41. [Neural Tangent Knowledge Distillation for Optical Convolutional Networks](#Neural-Tangent-Knowledge-Distillation-for-Optical-Convolutional-Networks)

---


## PARCO: Parallel AutoRegressive Models for Multi-Agent Combinatorial Optimization

### Images

![02f2d6bd05f17fa37928f43c292bc47b5a14e9e0405fa9541c2c69ee20c3004b.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/02f2d6bd05f17fa37928f43c292bc47b5a14e9e0405fa9541c2c69ee20c3004b.jpg)

![0ac759e41b611c0fe3183b1a0765f113a688bb52ee8e1e899e0e7bb1da663026.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/0ac759e41b611c0fe3183b1a0765f113a688bb52ee8e1e899e0e7bb1da663026.jpg)

![0da72f5901036cdf7f9e037242e6ac564be3dfec94e95307edc3aaddcad7fdc9.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/0da72f5901036cdf7f9e037242e6ac564be3dfec94e95307edc3aaddcad7fdc9.jpg)

![2ba9eec95305ba0aea8f851f3fe8089eb4b72092e897d00f9a63d3eb2c4431fb.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/2ba9eec95305ba0aea8f851f3fe8089eb4b72092e897d00f9a63d3eb2c4431fb.jpg)

![38637f5b47d6e7805f1557704280db106fb2551a89fb3afa553fccf173741f4b.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/38637f5b47d6e7805f1557704280db106fb2551a89fb3afa553fccf173741f4b.jpg)

![38cde9a20ddbeac87d31d1775c1d7d6688681ea7557d5587267145bb510b8033.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/38cde9a20ddbeac87d31d1775c1d7d6688681ea7557d5587267145bb510b8033.jpg)

![59febc8deaab6c426198327960882e6dd5e5e692894add9b251681e3f1723efe.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/59febc8deaab6c426198327960882e6dd5e5e692894add9b251681e3f1723efe.jpg)

![639cd45da786dac591af226cf34fa5a2ed8985c6c6f681cd80ee4f8be1bf4757.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/639cd45da786dac591af226cf34fa5a2ed8985c6c6f681cd80ee4f8be1bf4757.jpg)

![6847d93a1d06d02bfb1a5798c65b736e7fd61b110599f324e060687f950ab9d4.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/6847d93a1d06d02bfb1a5798c65b736e7fd61b110599f324e060687f950ab9d4.jpg)

![6d815e6cbd6eb205171f60310be35dea8996ccf87c9c2021f3884c6bb4bafb4c.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/6d815e6cbd6eb205171f60310be35dea8996ccf87c9c2021f3884c6bb4bafb4c.jpg)

![74b148a09cc4d1f8ae70203453912cba293ea75308a1219cc7e9d296c44ff4d4.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/74b148a09cc4d1f8ae70203453912cba293ea75308a1219cc7e9d296c44ff4d4.jpg)

![7a63e4ee88b583429acb38d4148879e6655435c6c045324619d83a6fd2b29edb.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/7a63e4ee88b583429acb38d4148879e6655435c6c045324619d83a6fd2b29edb.jpg)

![8deeb675ab88c54b315b04fbd243333989a9274774a780f4e4f5d705ed2e40d1.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/8deeb675ab88c54b315b04fbd243333989a9274774a780f4e4f5d705ed2e40d1.jpg)

![ad14e67594ef1e7cae3da24ac0c106ce252dd697b5d332d8ff7bc6569efe7cc0.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/ad14e67594ef1e7cae3da24ac0c106ce252dd697b5d332d8ff7bc6569efe7cc0.jpg)

![bba3c23601c466b0b5e93c83cd0328f1f7d52e369aaf66b81edac428a4a23122.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/bba3c23601c466b0b5e93c83cd0328f1f7d52e369aaf66b81edac428a4a23122.jpg)

![c35755fab318d8a7f5b0890fa5b2e27d8aad551b71a2b7715831b1f842c8766b.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/c35755fab318d8a7f5b0890fa5b2e27d8aad551b71a2b7715831b1f842c8766b.jpg)

![c7cf959eddd1b159ae755fdd74836e8be7618000a3f2d571ef1485903f3f1639.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/c7cf959eddd1b159ae755fdd74836e8be7618000a3f2d571ef1485903f3f1639.jpg)

![d5abc0601acdacf1f7f6bd02f0f6a4286c767d9203ee3d7acc1446c6579e9024.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/images/d5abc0601acdacf1f7f6bd02f0f6a4286c767d9203ee3d7acc1446c6579e9024.jpg)

### Tables

![203930257c6566bab9a01c7dadead04ca4beb979bfe4555824f8d056951023d5.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/tables/203930257c6566bab9a01c7dadead04ca4beb979bfe4555824f8d056951023d5.jpg)

![dcdc7401b4bcfc8340672255418ead227ac104954d4f96a3fff6d689d08eba8e.jpg](../nips_results/4598_Hierarchical%20Demonstration%20Order%20Optimization%20for%20Many-shot%20In-Context%20Learning/tables/dcdc7401b4bcfc8340672255418ead227ac104954d4f96a3fff6d689d08eba8e.jpg)

## PARCO: Parallel AutoRegressive Models for Multi-Agent Combinatorial Optimization


### Images

![24c2e8181b84dd52c05a46a6c5cfa6b11aa7bbb747fe00a717aafe2a3b9615df.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/images/24c2e8181b84dd52c05a46a6c5cfa6b11aa7bbb747fe00a717aafe2a3b9615df.jpg)

![48ea3128af6e135853d4272030474b8f8078cfc58f32811a17a4f264fbfca80e.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/images/48ea3128af6e135853d4272030474b8f8078cfc58f32811a17a4f264fbfca80e.jpg)

![5f93284a20382e038341cacccb36afe38da775d17905cdb7bc46b077dd51ea9d.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/images/5f93284a20382e038341cacccb36afe38da775d17905cdb7bc46b077dd51ea9d.jpg)

![b19a246f96f965eb6d949c90c4c9f1e93fd7a30223c261d8a4182e2e0bdb4a34.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/images/b19a246f96f965eb6d949c90c4c9f1e93fd7a30223c261d8a4182e2e0bdb4a34.jpg)

![cb1f0b19317b7b2b3aec55920bd08740e20bdd9bf4f8be7dcc2f619951551698.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/images/cb1f0b19317b7b2b3aec55920bd08740e20bdd9bf4f8be7dcc2f619951551698.jpg)

![d9313c85cea8c37208f2c0841549af8e3537f457ba10a99177deab8af6602ad4.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/images/d9313c85cea8c37208f2c0841549af8e3537f457ba10a99177deab8af6602ad4.jpg)

### Tables

![23c9acc49aa253e648df3a39f8543655ae4f02602135d1c2e18b3cb3ac13914d.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/tables/23c9acc49aa253e648df3a39f8543655ae4f02602135d1c2e18b3cb3ac13914d.jpg)

![3792e22d4f224091c0d4b57c7df2e08c528bd945ba3b9e450c35956b70442420.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/tables/3792e22d4f224091c0d4b57c7df2e08c528bd945ba3b9e450c35956b70442420.jpg)

![3880479047852c59c8537cd3c342acee17816801f7834a8aca5f2320c1685146.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/tables/3880479047852c59c8537cd3c342acee17816801f7834a8aca5f2320c1685146.jpg)

![51a0e8766b33f640b8ff6975382e464c2bb8136c5965e42e1ef1fc7c3202265a.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/tables/51a0e8766b33f640b8ff6975382e464c2bb8136c5965e42e1ef1fc7c3202265a.jpg)

![69f3cede5e5176bf63af5e02885610c1b15e2bb4d375bd26177e47102234b0a7.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/tables/69f3cede5e5176bf63af5e02885610c1b15e2bb4d375bd26177e47102234b0a7.jpg)

![6fa871d6c858113dbd1c3061966b0cda65156675f0b5e379d9888f603ee225fa.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/tables/6fa871d6c858113dbd1c3061966b0cda65156675f0b5e379d9888f603ee225fa.jpg)

![97e5ac3d82e50cb5e6591944c15e26058ea6a0305846c6fb0b4937b9ae5d3b3e.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/tables/97e5ac3d82e50cb5e6591944c15e26058ea6a0305846c6fb0b4937b9ae5d3b3e.jpg)

![9c4f6c2a9dab5dd8b0fcdcdb3d07549374e5dc24fb9197e712b98334a538d617.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/tables/9c4f6c2a9dab5dd8b0fcdcdb3d07549374e5dc24fb9197e712b98334a538d617.jpg)

![a85073b852d0aebd7635b133662ab8b2a9b56fe3c1766720b418d8b614f9d73c.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/tables/a85073b852d0aebd7635b133662ab8b2a9b56fe3c1766720b418d8b614f9d73c.jpg)

![f2c42dfc37e8146824d4635afafe6b7f2ca5400e65a4cc25f5c80c1e1e3ba9ff.jpg](../nips_results/4599_PARCO_%20Parallel%20AutoRegressive%20Models%20for%20Multi-Agent%20Combinatorial%20Optimization/tables/f2c42dfc37e8146824d4635afafe6b7f2ca5400e65a4cc25f5c80c1e1e3ba9ff.jpg)

## Anatomically inspired digital twins capture hierarchical object representations in visual cortex


### Images

![023395f81b639a161333566f8e6c1286b04603bbc095ca8bf60b7dda3a33046c.jpg](../nips_results/4600_Anatomically%20inspired%20digital%20twins%20capture%20hierarchical%20object%20representations%20in%20visual%20cortex/images/023395f81b639a161333566f8e6c1286b04603bbc095ca8bf60b7dda3a33046c.jpg)

![3264c12f8541e9958327184ae98589ce166a41a85f554a6509ef86477be791b4.jpg](../nips_results/4600_Anatomically%20inspired%20digital%20twins%20capture%20hierarchical%20object%20representations%20in%20visual%20cortex/images/3264c12f8541e9958327184ae98589ce166a41a85f554a6509ef86477be791b4.jpg)

![58bedf70ca9d2e235fc8c85e8bcd4346ccf05c1b060046c0b739e583904e7a18.jpg](../nips_results/4600_Anatomically%20inspired%20digital%20twins%20capture%20hierarchical%20object%20representations%20in%20visual%20cortex/images/58bedf70ca9d2e235fc8c85e8bcd4346ccf05c1b060046c0b739e583904e7a18.jpg)

![9554c92def583998166ab67691742f05662175c12f8e7c3b718365217a7a040f.jpg](../nips_results/4600_Anatomically%20inspired%20digital%20twins%20capture%20hierarchical%20object%20representations%20in%20visual%20cortex/images/9554c92def583998166ab67691742f05662175c12f8e7c3b718365217a7a040f.jpg)

![adde5e8f840d3b5628790f52bafc333be8af2bae7df2f92ed81fa3b0a5ed1825.jpg](../nips_results/4600_Anatomically%20inspired%20digital%20twins%20capture%20hierarchical%20object%20representations%20in%20visual%20cortex/images/adde5e8f840d3b5628790f52bafc333be8af2bae7df2f92ed81fa3b0a5ed1825.jpg)

![df46f8b6ef886fef60f9305f961bc41c949600cae41af3239cb74be0fefb31e1.jpg](../nips_results/4600_Anatomically%20inspired%20digital%20twins%20capture%20hierarchical%20object%20representations%20in%20visual%20cortex/images/df46f8b6ef886fef60f9305f961bc41c949600cae41af3239cb74be0fefb31e1.jpg)

![eab773d313e9ce1a965b95b78cbcaeb52474e90d5ce72d90a667c628765c7863.jpg](../nips_results/4600_Anatomically%20inspired%20digital%20twins%20capture%20hierarchical%20object%20representations%20in%20visual%20cortex/images/eab773d313e9ce1a965b95b78cbcaeb52474e90d5ce72d90a667c628765c7863.jpg)

### Tables

![7c5662dd245d49d35b5d1c268db847d1817d37229904c2b17f0f81166d1230c7.jpg](../nips_results/4600_Anatomically%20inspired%20digital%20twins%20capture%20hierarchical%20object%20representations%20in%20visual%20cortex/tables/7c5662dd245d49d35b5d1c268db847d1817d37229904c2b17f0f81166d1230c7.jpg)

## NegoCollab: A Common Representation Negotiation Approach for Heterogeneous Collaborative Perception


### Images

![02a92e046847b06a427bb41a86fb43e6e20342f3aaf0634df5f6b0f04110eb79.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/images/02a92e046847b06a427bb41a86fb43e6e20342f3aaf0634df5f6b0f04110eb79.jpg)

![4db4928a86bde726faa2ce7fde8f8701fa886757cb54417c4559b300966c95f6.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/images/4db4928a86bde726faa2ce7fde8f8701fa886757cb54417c4559b300966c95f6.jpg)

![79b9fd9c2fc3a43adefe2aa9fa67e596a88167d14d5367d4cba4e27b763195d7.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/images/79b9fd9c2fc3a43adefe2aa9fa67e596a88167d14d5367d4cba4e27b763195d7.jpg)

![b63cfbcdf8cb7fc6a108bf46c542f417d76a7c615207390897f1a820d4a7fbc4.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/images/b63cfbcdf8cb7fc6a108bf46c542f417d76a7c615207390897f1a820d4a7fbc4.jpg)

![b82ce234de1aec4fe8aaaa127a7559ad1063fc4ba52caf35ef4c142076280476.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/images/b82ce234de1aec4fe8aaaa127a7559ad1063fc4ba52caf35ef4c142076280476.jpg)

![c8bb8254c933cf576f2e6ba2f51c4d9d9af1a1b55801d4b92d9c6c60de65483f.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/images/c8bb8254c933cf576f2e6ba2f51c4d9d9af1a1b55801d4b92d9c6c60de65483f.jpg)

![d6256bba53a8a1d4987bb2ded0dbc04d1a00d8a53ff8e572c8894434876fa794.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/images/d6256bba53a8a1d4987bb2ded0dbc04d1a00d8a53ff8e572c8894434876fa794.jpg)

![dcbda0bd71abc1bed399e5e9be59aed3ad3d8c85d06949cbaa3941ce994a6d8c.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/images/dcbda0bd71abc1bed399e5e9be59aed3ad3d8c85d06949cbaa3941ce994a6d8c.jpg)

### Tables

![106e2272282309b76d90136a681a327aded53315efa99a6060f72d49a575d1df.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/tables/106e2272282309b76d90136a681a327aded53315efa99a6060f72d49a575d1df.jpg)

![18fdbdf95e186e59dc698ed84ee5490f25f4e694dda93aad717bdc6f6a3e8def.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/tables/18fdbdf95e186e59dc698ed84ee5490f25f4e694dda93aad717bdc6f6a3e8def.jpg)

![3dff4e401eb6353f1d8f88b7973a081d802ee08c910e5cbdd28c5fb48f29e281.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/tables/3dff4e401eb6353f1d8f88b7973a081d802ee08c910e5cbdd28c5fb48f29e281.jpg)

![42e5398c853ec41d0a497f2dbe5f15a251b52626c1f55f75557e26fe532ffe6e.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/tables/42e5398c853ec41d0a497f2dbe5f15a251b52626c1f55f75557e26fe532ffe6e.jpg)

![633275ff950df435f3d2d7e66285cb77c32f913b3fe7a56b9605887950e3d3da.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/tables/633275ff950df435f3d2d7e66285cb77c32f913b3fe7a56b9605887950e3d3da.jpg)

![8da306da5eac29c1ac427116c3681395df7beb6bbdb5ed9d4c421dbd7900e98b.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/tables/8da306da5eac29c1ac427116c3681395df7beb6bbdb5ed9d4c421dbd7900e98b.jpg)

![adc9dc5deb920ae783a3172c705613af96af843a8897faac71bdb045fa6fa7ac.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/tables/adc9dc5deb920ae783a3172c705613af96af843a8897faac71bdb045fa6fa7ac.jpg)

![d0e0bb2a4a42cb608ea862b73c93875c5d08f4c22b8b9d6081fb3e9bee8e9244.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/tables/d0e0bb2a4a42cb608ea862b73c93875c5d08f4c22b8b9d6081fb3e9bee8e9244.jpg)

![e9fdabcec261f9e42a1650b3d9c6f78e17fde4faba482afb25eee8920efafabd.jpg](../nips_results/4601_NegoCollab_%20A%20Common%20Representation%20Negotiation%20Approach%20for%20Heterogeneous%20Collaborative%20Perception/tables/e9fdabcec261f9e42a1650b3d9c6f78e17fde4faba482afb25eee8920efafabd.jpg)

## Optimal kernel regression bounds under energy-bounded noise


### Images

![0896e83110d99d9e8004eaeea75b208ad2ff84e75b163b7465c10af0477d3634.jpg](../nips_results/4602_Optimal%20kernel%20regression%20bounds%20under%20energy-bounded%20noise/images/0896e83110d99d9e8004eaeea75b208ad2ff84e75b163b7465c10af0477d3634.jpg)

![717db4da913bde9eb6c464c0d0ab5f1d634285cd55029f654b307576f6393f4f.jpg](../nips_results/4602_Optimal%20kernel%20regression%20bounds%20under%20energy-bounded%20noise/images/717db4da913bde9eb6c464c0d0ab5f1d634285cd55029f654b307576f6393f4f.jpg)

![ef1370b4009e4dcccf0ca51f882cbff600d452b4f55e094332604aa07d4ba016.jpg](../nips_results/4602_Optimal%20kernel%20regression%20bounds%20under%20energy-bounded%20noise/images/ef1370b4009e4dcccf0ca51f882cbff600d452b4f55e094332604aa07d4ba016.jpg)

### Tables

![0979fb84bfa8259e8bbe1f0e22b0ae6f666fa054ac3ee7456591245264ec9fd4.jpg](../nips_results/4602_Optimal%20kernel%20regression%20bounds%20under%20energy-bounded%20noise/tables/0979fb84bfa8259e8bbe1f0e22b0ae6f666fa054ac3ee7456591245264ec9fd4.jpg)

## GeoAda: Efficiently Finetune Geometric Diffusion Models with Equivariant Adapters


### Images

![301c1ae2f86f974e3082abec805af74b774866993e162e962aca9e625389d758.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/images/301c1ae2f86f974e3082abec805af74b774866993e162e962aca9e625389d758.jpg)

![4c233eb9263179ac120b45aa0e3c150852d1e0c21aaca427c59ac9c3769bb553.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/images/4c233eb9263179ac120b45aa0e3c150852d1e0c21aaca427c59ac9c3769bb553.jpg)

![73c1fd784e5877d54beac4f6e198cb1b358636a5c0ff3d1c72f3e55a7edb2c16.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/images/73c1fd784e5877d54beac4f6e198cb1b358636a5c0ff3d1c72f3e55a7edb2c16.jpg)

![7f2193b31309bfa1ff344dcee12dfe28290e7c3d06e09462a4eb124276e02bc1.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/images/7f2193b31309bfa1ff344dcee12dfe28290e7c3d06e09462a4eb124276e02bc1.jpg)

![bf6399948817c8d8427fc66e7d5795999fd1a00a0c07b20314938918fb2711f1.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/images/bf6399948817c8d8427fc66e7d5795999fd1a00a0c07b20314938918fb2711f1.jpg)

![ccc14c4c1c4ddc7589e6235b5b440897ef677abb31129c189a5f90e3bb9e9d2e.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/images/ccc14c4c1c4ddc7589e6235b5b440897ef677abb31129c189a5f90e3bb9e9d2e.jpg)

![e8dd0cbfd3a66f27623ed54356eee8ff5ee1c1477efa7f4911e9bec3ee352693.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/images/e8dd0cbfd3a66f27623ed54356eee8ff5ee1c1477efa7f4911e9bec3ee352693.jpg)

![f57eb4c852e8d06dbaae230ff9ff758fd12a038f820e2ae9734e9f99ef1dd087.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/images/f57eb4c852e8d06dbaae230ff9ff758fd12a038f820e2ae9734e9f99ef1dd087.jpg)

### Tables

![01620058e30845a2764653638d0c172e837e740642afbf02b81a7eb6f049ac4d.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/01620058e30845a2764653638d0c172e837e740642afbf02b81a7eb6f049ac4d.jpg)

![0342dd6453a14bb4ae065a8adf26c6c15f1995361a516e596098e9d81a82122c.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/0342dd6453a14bb4ae065a8adf26c6c15f1995361a516e596098e9d81a82122c.jpg)

![0e480a89cb2d734912b4006af870ecb6d4847cfee852b552a915a5331ec96800.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/0e480a89cb2d734912b4006af870ecb6d4847cfee852b552a915a5331ec96800.jpg)

![289690a60cd9f80b61cd785b3e3d166d927f600b125095c0904f36b7997385f4.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/289690a60cd9f80b61cd785b3e3d166d927f600b125095c0904f36b7997385f4.jpg)

![358729447efe88d0b2e35d46d8939f60d27a404239bf9097cc0c51cdeff62428.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/358729447efe88d0b2e35d46d8939f60d27a404239bf9097cc0c51cdeff62428.jpg)

![41728db33486b2fae1f38a764e7645f2b1d8089c278a56eb60feaa853108908a.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/41728db33486b2fae1f38a764e7645f2b1d8089c278a56eb60feaa853108908a.jpg)

![466f795a020bfe8ddd3a4d0abf521739f09501a9d835765873b39cc63f292f84.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/466f795a020bfe8ddd3a4d0abf521739f09501a9d835765873b39cc63f292f84.jpg)

![49ed40aa0775bf88e0e6ed5f7f9f152f12b783fbb010f0f0e928c35bae200f46.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/49ed40aa0775bf88e0e6ed5f7f9f152f12b783fbb010f0f0e928c35bae200f46.jpg)

![4f55fa6dcf55f3600741f9a65a990885814b8527b1a3413bdab236a34d4c4956.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/4f55fa6dcf55f3600741f9a65a990885814b8527b1a3413bdab236a34d4c4956.jpg)

![574b41f5c3646b7f739be6f3ff1cb7adbe3b7de4371710dceb861f15814f6d9e.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/574b41f5c3646b7f739be6f3ff1cb7adbe3b7de4371710dceb861f15814f6d9e.jpg)

![74b9225d574e88603bbdd09216012bf4e98c0c8a5ceaba516d5a9db20f9324d2.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/74b9225d574e88603bbdd09216012bf4e98c0c8a5ceaba516d5a9db20f9324d2.jpg)

![a7d19e18737f1b0575e29953826f69d08c266f5cbee504b9e006d02efeba4207.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/a7d19e18737f1b0575e29953826f69d08c266f5cbee504b9e006d02efeba4207.jpg)

![ab48e4595478f99bc6b59f662545d28e538eba0be4e2fe9f412b3c932054623b.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/ab48e4595478f99bc6b59f662545d28e538eba0be4e2fe9f412b3c932054623b.jpg)

![b0d72ad1001c6b055f5e9cbeb80312405c163b9bcaba7703f50e421d1cc4c34c.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/b0d72ad1001c6b055f5e9cbeb80312405c163b9bcaba7703f50e421d1cc4c34c.jpg)

![bcbbd404215c80c1bb60d3352909fc29c4933d45e1e3acbf065b0c1fbee5c52b.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/bcbbd404215c80c1bb60d3352909fc29c4933d45e1e3acbf065b0c1fbee5c52b.jpg)

![bfa1d56d08010706ade8052449e9d1525e9b5a4fe889281acdfd0c1e529cf873.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/bfa1d56d08010706ade8052449e9d1525e9b5a4fe889281acdfd0c1e529cf873.jpg)

![c4beccf1769c5496ceb8dbef92e1879e1fd5626e171aa5fa7f5f4d70b9b8eb48.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/c4beccf1769c5496ceb8dbef92e1879e1fd5626e171aa5fa7f5f4d70b9b8eb48.jpg)

![ccefdb69ef1ea3ebbc40bb14fe319c76b2145ac855e5ac0acd5bc7adbf451e46.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/ccefdb69ef1ea3ebbc40bb14fe319c76b2145ac855e5ac0acd5bc7adbf451e46.jpg)

![cf4ce04daaf1fac5406d1c7e61451bc0a607cda3c80b3febf367c2a930b549fe.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/cf4ce04daaf1fac5406d1c7e61451bc0a607cda3c80b3febf367c2a930b549fe.jpg)

![d331f55188a640236e69b06b908e9cf73a40427bb89f5e3a668ad65d529cc475.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/d331f55188a640236e69b06b908e9cf73a40427bb89f5e3a668ad65d529cc475.jpg)

![e48352d9aa60004a10690dce39fa9ab939c7e5de05fcfd42123d8e7d28990170.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/e48352d9aa60004a10690dce39fa9ab939c7e5de05fcfd42123d8e7d28990170.jpg)

![e77911d49b7f5ee256969a71b12042cef677266db5274b1dbfceabb695e0292f.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/e77911d49b7f5ee256969a71b12042cef677266db5274b1dbfceabb695e0292f.jpg)

![e7ef114ed5a5a4b10053c84009b80e12ee0d39f9b1a4dc947603d2d1b2aa952a.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/e7ef114ed5a5a4b10053c84009b80e12ee0d39f9b1a4dc947603d2d1b2aa952a.jpg)

![ecb1bd7a38c77d9b3310837a6e233d8e74d99c2f63b402d539c1a8e53f0e231c.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/ecb1bd7a38c77d9b3310837a6e233d8e74d99c2f63b402d539c1a8e53f0e231c.jpg)

![f7ec9ca91ebb13873c90733cd6cd8b739b4c9b82b9c48ea9c3abcfc251fb1dc4.jpg](../nips_results/4603_GeoAda_%20Efficiently%20Finetune%20Geometric%20Diffusion%20Models%20with%20Equivariant%20Adapters/tables/f7ec9ca91ebb13873c90733cd6cd8b739b4c9b82b9c48ea9c3abcfc251fb1dc4.jpg)

## Task-Specific Data Selection for Instruction Tuning via Monosemantic Neuronal Activations


### Images

![03cc6b27cf37aefefec4611a3a4f8a9b0f0ed53c5241d82caa8a7e3ae7bdaeb8.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/images/03cc6b27cf37aefefec4611a3a4f8a9b0f0ed53c5241d82caa8a7e3ae7bdaeb8.jpg)

![25880c7d8500041ecc6400a8c16cda1258d02fba2b5b230c5017eca4b486a278.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/images/25880c7d8500041ecc6400a8c16cda1258d02fba2b5b230c5017eca4b486a278.jpg)

![79d9a9fb0d0c2d00f4b9b89bc70e9e6fcad84807b9aca9771a35e16252046382.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/images/79d9a9fb0d0c2d00f4b9b89bc70e9e6fcad84807b9aca9771a35e16252046382.jpg)

![7eb60fbe9bedeee18389f3ac361acbbfa8f123178ce6f4e0e22bf0c7a27070be.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/images/7eb60fbe9bedeee18389f3ac361acbbfa8f123178ce6f4e0e22bf0c7a27070be.jpg)

![8fc0ffc4497d4751bf83851cf7fbc0b27d7a2d6f2ab82eaa4c9439207061b7fe.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/images/8fc0ffc4497d4751bf83851cf7fbc0b27d7a2d6f2ab82eaa4c9439207061b7fe.jpg)

![9074ff90dbccd45586d738986016d1037c2f657fe879f7dbba7721c9cee9fd93.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/images/9074ff90dbccd45586d738986016d1037c2f657fe879f7dbba7721c9cee9fd93.jpg)

![b73837b4a271efb9ec70c37570258abbedb9552924faa5286f70b13882678710.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/images/b73837b4a271efb9ec70c37570258abbedb9552924faa5286f70b13882678710.jpg)

![c64dfa0493d94eae655ac4059caa6a1452aa9e9af5457e15cd53c8749e3c646c.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/images/c64dfa0493d94eae655ac4059caa6a1452aa9e9af5457e15cd53c8749e3c646c.jpg)

### Tables

![30d8d7cba30ef40314731844d7bd0d3f44db62ce22d5995e3ab1d69886e89b64.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/30d8d7cba30ef40314731844d7bd0d3f44db62ce22d5995e3ab1d69886e89b64.jpg)

![3fd0f3ae6c24c3a9e6e57bd97b50f0c57e772d8b6b300a4cb9720c598beb8de3.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/3fd0f3ae6c24c3a9e6e57bd97b50f0c57e772d8b6b300a4cb9720c598beb8de3.jpg)

![66a5066a8920ddd6d73260e697f7b236423eb4bdd92147c6bfd977a5ff58df8f.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/66a5066a8920ddd6d73260e697f7b236423eb4bdd92147c6bfd977a5ff58df8f.jpg)

![7993d05f79914e8e1ca5f7130f7bd66ef4f59aa1691ba086a0495f72fbb11fe8.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/7993d05f79914e8e1ca5f7130f7bd66ef4f59aa1691ba086a0495f72fbb11fe8.jpg)

![84315fdb34835993505193026dfbc4ff3363ad68da32b04c45cf23c49c065d1d.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/84315fdb34835993505193026dfbc4ff3363ad68da32b04c45cf23c49c065d1d.jpg)

![a45ca94e2803e8044c6d34eba2425a9bc0a51facd344d86c3733c949932731e8.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/a45ca94e2803e8044c6d34eba2425a9bc0a51facd344d86c3733c949932731e8.jpg)

![a742ca8c0296b5eece0f4dfeec6434e03c83b76fa5efa97c0ad69d43f369535d.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/a742ca8c0296b5eece0f4dfeec6434e03c83b76fa5efa97c0ad69d43f369535d.jpg)

![aa5c5fd57ce7655a7fc3035149e6f419a54f0d55160fc1e3b090c3bfb7d058d9.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/aa5c5fd57ce7655a7fc3035149e6f419a54f0d55160fc1e3b090c3bfb7d058d9.jpg)

![b7dde775a1f30505e1e4148e22f60e8f6149860ec4ff1920ad6f68e094951446.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/b7dde775a1f30505e1e4148e22f60e8f6149860ec4ff1920ad6f68e094951446.jpg)

![b87fa214e2ebcb65e140619537a447dff5bb8b7647b942f89ad9a5d707b75a00.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/b87fa214e2ebcb65e140619537a447dff5bb8b7647b942f89ad9a5d707b75a00.jpg)

![cb11b8b67ab3c72aefd881f4cdea0f8f1f8a10f6ad39808325fcedb8f637ad52.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/cb11b8b67ab3c72aefd881f4cdea0f8f1f8a10f6ad39808325fcedb8f637ad52.jpg)

![d1889e39d7b71b26bf182582af4aef824b9496849fa8fab6901b37c8f2e5281f.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/d1889e39d7b71b26bf182582af4aef824b9496849fa8fab6901b37c8f2e5281f.jpg)

![e439477b3b2963a8e43155a8a0602dbf2c002b452491dfc2eeaacc93144e31f8.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/e439477b3b2963a8e43155a8a0602dbf2c002b452491dfc2eeaacc93144e31f8.jpg)

![ec007e5b1ade4be31f99d08ef0e03eb30de818ff1f7d57f02d128b96b73613b6.jpg](../nips_results/4604_Task-Specific%20Data%20Selection%20for%20Instruction%20Tuning%20via%20Monosemantic%20Neuronal%20Activations/tables/ec007e5b1ade4be31f99d08ef0e03eb30de818ff1f7d57f02d128b96b73613b6.jpg)

## CoT-lized Diffusion: Let's Reinforce T2I Generation Step-by-step


### Images

![07d714efb66985671d80ce3c865a21009523c16380f68e7ee6ab3cd47d5aacca.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/07d714efb66985671d80ce3c865a21009523c16380f68e7ee6ab3cd47d5aacca.jpg)

![26d4f88900a58ea9f5bbc4121f2cf7fc2138c81396d57f6950972383955ad89e.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/26d4f88900a58ea9f5bbc4121f2cf7fc2138c81396d57f6950972383955ad89e.jpg)

![56737085374d00a3726a8ff811e328d711cfe37dbd5cf4ed858f296a2531ac5f.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/56737085374d00a3726a8ff811e328d711cfe37dbd5cf4ed858f296a2531ac5f.jpg)

![5d369e8e0e743061f347cb6b237aae3150864ca66a36fa2489a24b6d785f7097.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/5d369e8e0e743061f347cb6b237aae3150864ca66a36fa2489a24b6d785f7097.jpg)

![7a5948b3fdbf6edceddbf63dfc470884a6a6a62938501ace86c9b4b569fc7f23.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/7a5948b3fdbf6edceddbf63dfc470884a6a6a62938501ace86c9b4b569fc7f23.jpg)

![7f3bef0c810597ce9d802b42c5be19132283008ab359c4d73c3da3d024523571.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/7f3bef0c810597ce9d802b42c5be19132283008ab359c4d73c3da3d024523571.jpg)

![a6fe7ad0dc95714ed544f5a572560034bc2825547a51b24598020676ab042681.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/a6fe7ad0dc95714ed544f5a572560034bc2825547a51b24598020676ab042681.jpg)

![b3adc0121612708db503a663954652450ebec4cbdf445a87f8f7a5e04e4d3f59.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/b3adc0121612708db503a663954652450ebec4cbdf445a87f8f7a5e04e4d3f59.jpg)

![bde40d6df46dd6aae1137c24aebe5293705da4a6eedf9c1835344f06d92d36c6.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/bde40d6df46dd6aae1137c24aebe5293705da4a6eedf9c1835344f06d92d36c6.jpg)

![cbb16b665326d49171297cfe76464bed23451d780a8e1ab4b2715eb77dbd08a6.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/cbb16b665326d49171297cfe76464bed23451d780a8e1ab4b2715eb77dbd08a6.jpg)

![def5c3ae5adeeb94d561208e2dfe1c9d265e4ff205991f71c9a44858f585ae61.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/def5c3ae5adeeb94d561208e2dfe1c9d265e4ff205991f71c9a44858f585ae61.jpg)

![e9049bd39b73c86af1cc150057659ea595c5176599bb577ed3dc73c848834b77.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/images/e9049bd39b73c86af1cc150057659ea595c5176599bb577ed3dc73c848834b77.jpg)

### Tables

![084190576e66863c5bb1fba82db50b0df57f6482c8c568feff25956df957a40f.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/084190576e66863c5bb1fba82db50b0df57f6482c8c568feff25956df957a40f.jpg)

![12dad00bd8c1a3396303bc5a4958c170ae63e982d648179cff9a1500415cf479.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/12dad00bd8c1a3396303bc5a4958c170ae63e982d648179cff9a1500415cf479.jpg)

![21b58a82d5b8cc40cc6d17d2cf6f9845d29d013a97ca0e2e4424ce8d7c5d6da2.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/21b58a82d5b8cc40cc6d17d2cf6f9845d29d013a97ca0e2e4424ce8d7c5d6da2.jpg)

![54de3dc9abe22eb83723e25bd2bd2227e769209d53bdf5f44d8bbe4f069e2ed6.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/54de3dc9abe22eb83723e25bd2bd2227e769209d53bdf5f44d8bbe4f069e2ed6.jpg)

![8eb9ab218169b52fdac4cb46b32c6ea62a0f1b0f536cc4d9ab4696aa054f4212.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/8eb9ab218169b52fdac4cb46b32c6ea62a0f1b0f536cc4d9ab4696aa054f4212.jpg)

![c673917460a14c97830630a33e021260e9b4457b474745b9a4d334bd1828f29e.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/c673917460a14c97830630a33e021260e9b4457b474745b9a4d334bd1828f29e.jpg)

![dabdbd969106cc51be2ed026edf58d34d3d597be0020e3d22efcd1fe35a1de05.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/dabdbd969106cc51be2ed026edf58d34d3d597be0020e3d22efcd1fe35a1de05.jpg)

![dacfaf9891ac624d02e46539d28d6df9e72dc92c28033878305019fcc25d83c5.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/dacfaf9891ac624d02e46539d28d6df9e72dc92c28033878305019fcc25d83c5.jpg)

![de9f7897fbbb438192b88ff4ca4caa77fd1620df8024d2deaf65c8cb389aa31b.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/de9f7897fbbb438192b88ff4ca4caa77fd1620df8024d2deaf65c8cb389aa31b.jpg)

![ed5816b44328539cbb3bf0478f5d550d571011c689072e559ac7a42cf7bc7fed.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/ed5816b44328539cbb3bf0478f5d550d571011c689072e559ac7a42cf7bc7fed.jpg)

![f830b3732e37ab8c44ec3b955b55f56326d342c767da1156c4c4a3e1655c447f.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/f830b3732e37ab8c44ec3b955b55f56326d342c767da1156c4c4a3e1655c447f.jpg)

![f96161c9938cede402f8f27c3cf6a4ca1db5f5406658763eda9adc2af1bd1bde.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/f96161c9938cede402f8f27c3cf6a4ca1db5f5406658763eda9adc2af1bd1bde.jpg)

![fcb22d61170cb178dc3d6bae1eedb0dfdfd1898262b18eb279112f14a259cf45.jpg](../nips_results/4605_CoT-lized%20Diffusion_%20Let%27s%20Reinforce%20T2I%20Generation%20Step-by-step/tables/fcb22d61170cb178dc3d6bae1eedb0dfdfd1898262b18eb279112f14a259cf45.jpg)

## For Better or for Worse, Transformers Seek Patterns for Memorization


### Images

![041540f47519dc106860c188a499d63a7b831339f6a31075a8a498b18da3e055.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/041540f47519dc106860c188a499d63a7b831339f6a31075a8a498b18da3e055.jpg)

![520948363368b33e795ea9097563e3489cb3490721877eaa0af67bfd169cbe74.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/520948363368b33e795ea9097563e3489cb3490721877eaa0af67bfd169cbe74.jpg)

![52d84b3196da8983b8e87a7cfc56fd0c625edc16b4aff6b8aad8a5faa431ff24.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/52d84b3196da8983b8e87a7cfc56fd0c625edc16b4aff6b8aad8a5faa431ff24.jpg)

![5d0d216f43d30e3b18df84b76e58c202cca00d685a39aeba3940e492c75da454.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/5d0d216f43d30e3b18df84b76e58c202cca00d685a39aeba3940e492c75da454.jpg)

![6f694e9ce6005f1f8fc77188f8422f7ba05b8a2e86f1397eb866e3ba7503f0fb.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/6f694e9ce6005f1f8fc77188f8422f7ba05b8a2e86f1397eb866e3ba7503f0fb.jpg)

![6f9646c338353f87088cfef57483cabe6a055d48672c6095d7ccc37b4df6890a.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/6f9646c338353f87088cfef57483cabe6a055d48672c6095d7ccc37b4df6890a.jpg)

![8a0f3933742f9343eac283d6b33bb86c55ffffae0c20a2d45f287e7abd241719.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/8a0f3933742f9343eac283d6b33bb86c55ffffae0c20a2d45f287e7abd241719.jpg)

![96506b9e9680c72e0eaf28e666389aaa5f3ecb594a65e7813c032edaea487c55.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/96506b9e9680c72e0eaf28e666389aaa5f3ecb594a65e7813c032edaea487c55.jpg)

![9e3ac9a64784db3dcf7d53c0a7bfb7fd3fbd6829904f7838bc81d6eeedb5f833.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/9e3ac9a64784db3dcf7d53c0a7bfb7fd3fbd6829904f7838bc81d6eeedb5f833.jpg)

![a166370eb8bf643faf55d81610febb9ffc0787bc162b07d1d8bc1de952f4f56d.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/a166370eb8bf643faf55d81610febb9ffc0787bc162b07d1d8bc1de952f4f56d.jpg)

![a1c7e3e80de131f426fe3df0e422032d4088d735f2af56be234c0a56dfa266ee.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/a1c7e3e80de131f426fe3df0e422032d4088d735f2af56be234c0a56dfa266ee.jpg)

![b2dc5468b7558d9ff446300bb82e0f560319f32f379b3b9b0391af433368f3bb.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/b2dc5468b7558d9ff446300bb82e0f560319f32f379b3b9b0391af433368f3bb.jpg)

![e5042a6a3ddefb78d8b06b996d8abdc267a5aaf51e68ac2a0a171dc8402298cb.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/images/e5042a6a3ddefb78d8b06b996d8abdc267a5aaf51e68ac2a0a171dc8402298cb.jpg)

### Tables

![0f4cfc761c694b306a386b20c2e10c40aeccdcbdee38640ee238fdbe6445ec19.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/tables/0f4cfc761c694b306a386b20c2e10c40aeccdcbdee38640ee238fdbe6445ec19.jpg)

![1032eb5808eb6ba376fbca8960d02570ae52dcc22744adcb248f510794ad9607.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/tables/1032eb5808eb6ba376fbca8960d02570ae52dcc22744adcb248f510794ad9607.jpg)

![23307e2ca264ff30a8884126cb9750d9f22e9b596b634dbda046f2f419b338aa.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/tables/23307e2ca264ff30a8884126cb9750d9f22e9b596b634dbda046f2f419b338aa.jpg)

![5941a6835a8bb78255e8826b34ba04095b562afdafa082e5c578b3e243a9c3f4.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/tables/5941a6835a8bb78255e8826b34ba04095b562afdafa082e5c578b3e243a9c3f4.jpg)

![76cc4f8a14711df8e1b205419ebd184b9ec410ed9cda7bd6ea8abb01ac03f943.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/tables/76cc4f8a14711df8e1b205419ebd184b9ec410ed9cda7bd6ea8abb01ac03f943.jpg)

![7d5af53456e259e3cfdf58bf974ae05733105d8bddf4ca75a9bb095e6ceb4126.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/tables/7d5af53456e259e3cfdf58bf974ae05733105d8bddf4ca75a9bb095e6ceb4126.jpg)

![948ca85e76b03362c27965f2130f2f2198cef71cf702faa10f5d6b406fbd5bfe.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/tables/948ca85e76b03362c27965f2130f2f2198cef71cf702faa10f5d6b406fbd5bfe.jpg)

![fa83a178424862b4fefd1e8d3859710f33cb32e5bb406f7b6131a493941ee73c.jpg](../nips_results/4606_For%20Better%20or%20for%20Worse%2C%20Transformers%20Seek%20Patterns%20for%20Memorization/tables/fa83a178424862b4fefd1e8d3859710f33cb32e5bb406f7b6131a493941ee73c.jpg)

## Self supervised learning for in vivo localization of microelectrode arrays using raw local field potential


### Images

![092d08f166d68cc61ce34c18fb66b1e9458a7f7a30a8fd6d04ae410d6813b28c.jpg](../nips_results/4607_Self%20supervised%20learning%20for%20in%20vivo%20localization%20of%20microelectrode%20arrays%20using%20raw%20local%20field%20pot/images/092d08f166d68cc61ce34c18fb66b1e9458a7f7a30a8fd6d04ae410d6813b28c.jpg)

![1e7a340daddb1f27de92db79b04b08f08beeec7daf90d95dd82db553def54b37.jpg](../nips_results/4607_Self%20supervised%20learning%20for%20in%20vivo%20localization%20of%20microelectrode%20arrays%20using%20raw%20local%20field%20pot/images/1e7a340daddb1f27de92db79b04b08f08beeec7daf90d95dd82db553def54b37.jpg)

![4118329bb8e39323063d09af74e68046c03f1f0a622054f475db63f173f8c62a.jpg](../nips_results/4607_Self%20supervised%20learning%20for%20in%20vivo%20localization%20of%20microelectrode%20arrays%20using%20raw%20local%20field%20pot/images/4118329bb8e39323063d09af74e68046c03f1f0a622054f475db63f173f8c62a.jpg)

![497e47c04e18560f4db294c3b5d1ae8237b4dd084042000eb3f32a795fb6ae92.jpg](../nips_results/4607_Self%20supervised%20learning%20for%20in%20vivo%20localization%20of%20microelectrode%20arrays%20using%20raw%20local%20field%20pot/images/497e47c04e18560f4db294c3b5d1ae8237b4dd084042000eb3f32a795fb6ae92.jpg)

![5d2dc728fb01493fa62bf4c3e5dfc6b89e8ada64acca880fdb3a16a7b32d4649.jpg](../nips_results/4607_Self%20supervised%20learning%20for%20in%20vivo%20localization%20of%20microelectrode%20arrays%20using%20raw%20local%20field%20pot/images/5d2dc728fb01493fa62bf4c3e5dfc6b89e8ada64acca880fdb3a16a7b32d4649.jpg)

![d6436f0709330f62122c3a8dc4fb74062384941a1869312fcf7f2b12abe9f62d.jpg](../nips_results/4607_Self%20supervised%20learning%20for%20in%20vivo%20localization%20of%20microelectrode%20arrays%20using%20raw%20local%20field%20pot/images/d6436f0709330f62122c3a8dc4fb74062384941a1869312fcf7f2b12abe9f62d.jpg)

![dbb38d8ddc23974adb9e42ec88ec16223ad7adc474728aa64dfce6836ea0a45d.jpg](../nips_results/4607_Self%20supervised%20learning%20for%20in%20vivo%20localization%20of%20microelectrode%20arrays%20using%20raw%20local%20field%20pot/images/dbb38d8ddc23974adb9e42ec88ec16223ad7adc474728aa64dfce6836ea0a45d.jpg)

![e5f6d6d007c1ea98f59498409837348c2abd8925632da52577251156972b7edb.jpg](../nips_results/4607_Self%20supervised%20learning%20for%20in%20vivo%20localization%20of%20microelectrode%20arrays%20using%20raw%20local%20field%20pot/images/e5f6d6d007c1ea98f59498409837348c2abd8925632da52577251156972b7edb.jpg)

### Tables

![47c0e66118ce35f705fcb3e3cd127ed033c79e7f9221588d70bf52213a53c002.jpg](../nips_results/4607_Self%20supervised%20learning%20for%20in%20vivo%20localization%20of%20microelectrode%20arrays%20using%20raw%20local%20field%20pot/tables/47c0e66118ce35f705fcb3e3cd127ed033c79e7f9221588d70bf52213a53c002.jpg)

![c8747139b54f98b8eb768802fd3f3137fe4bcbf549f6d7b74fd035a99be2b463.jpg](../nips_results/4607_Self%20supervised%20learning%20for%20in%20vivo%20localization%20of%20microelectrode%20arrays%20using%20raw%20local%20field%20pot/tables/c8747139b54f98b8eb768802fd3f3137fe4bcbf549f6d7b74fd035a99be2b463.jpg)

## Unlocking Multimodal Mathematical Reasoning via Process Reward Model


### Images

![293ecdd44bfbe3e3866914a220278307182844447e1ff456763998f189234539.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/293ecdd44bfbe3e3866914a220278307182844447e1ff456763998f189234539.jpg)

![3ecf2e4157858591b9eeb262a5ae5d0aa4fb82041662761b13aa441feefd1e8e.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/3ecf2e4157858591b9eeb262a5ae5d0aa4fb82041662761b13aa441feefd1e8e.jpg)

![42b1cf0921b5a66f23b9f222820338088f9f250223aab728d1cca8ab64ae3e86.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/42b1cf0921b5a66f23b9f222820338088f9f250223aab728d1cca8ab64ae3e86.jpg)

![443569d44d5c00dc7af901667d93549abee69bfaf89917682f8f4075f8ae10f7.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/443569d44d5c00dc7af901667d93549abee69bfaf89917682f8f4075f8ae10f7.jpg)

![5459ea82d17d2ca851517df7e30a0f6a7ce9b6f77c0e3a06b55bbd4a497905c2.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/5459ea82d17d2ca851517df7e30a0f6a7ce9b6f77c0e3a06b55bbd4a497905c2.jpg)

![695de4d47fc1bebd1660a00b06e714d3323e9933f195dc4bafb5283eee732af9.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/695de4d47fc1bebd1660a00b06e714d3323e9933f195dc4bafb5283eee732af9.jpg)

![77dcc70947499d01d97663a9027814ae02f9b3976421f2cd9081ec1ab9c4c97d.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/77dcc70947499d01d97663a9027814ae02f9b3976421f2cd9081ec1ab9c4c97d.jpg)

![7c3da1bd7ee19314b1ac8e699ab1ee7201eeaf0830dce309664b717b56f3c3fd.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/7c3da1bd7ee19314b1ac8e699ab1ee7201eeaf0830dce309664b717b56f3c3fd.jpg)

![a0b1e131b74e03fa692618e6aaae2a42e7af2ae0b86cfd167702c0c509b44ae3.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/a0b1e131b74e03fa692618e6aaae2a42e7af2ae0b86cfd167702c0c509b44ae3.jpg)

![abb558713469ffd591cf3049af310015d55fb6d261f4cb734426c5854ce6eac0.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/abb558713469ffd591cf3049af310015d55fb6d261f4cb734426c5854ce6eac0.jpg)

![ae324f03a5123787718165a8e68b600b2c4a9675616dad5d302d8c75a60707e3.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/ae324f03a5123787718165a8e68b600b2c4a9675616dad5d302d8c75a60707e3.jpg)

![c09cf90e2925300d13b2249d4dc72a0a6a9645d264904a4b280793308294c740.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/c09cf90e2925300d13b2249d4dc72a0a6a9645d264904a4b280793308294c740.jpg)

![c655d17c8e8d114896636f4a4b01353e6be1e039307df698f5333fd76a0d96f2.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/c655d17c8e8d114896636f4a4b01353e6be1e039307df698f5333fd76a0d96f2.jpg)

![ccf0649a60addd0966d898ca3275dfb84e5e7bd825007429ccc8ce92e863b4b4.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/ccf0649a60addd0966d898ca3275dfb84e5e7bd825007429ccc8ce92e863b4b4.jpg)

![d2ff4fae800db00dd67e074f6e0268358212bafd08518333716bdf91547dfa7f.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/d2ff4fae800db00dd67e074f6e0268358212bafd08518333716bdf91547dfa7f.jpg)

![eafa3a5f3dcadfcdd7b6cd509f9a3e5f0c385a9095dca37e41c815a692a84985.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/eafa3a5f3dcadfcdd7b6cd509f9a3e5f0c385a9095dca37e41c815a692a84985.jpg)

![ec86427a27626e63eaee6590b5ed1e40544906736de042fad2b2e06d48106812.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/images/ec86427a27626e63eaee6590b5ed1e40544906736de042fad2b2e06d48106812.jpg)

### Tables

![008d77be33e28fa12f537e04d81c40f6a8e8d218c0792c9d68d5ef36bb4f4e8d.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/008d77be33e28fa12f537e04d81c40f6a8e8d218c0792c9d68d5ef36bb4f4e8d.jpg)

![065546000c00fd6043515d3ae299955dbd75baf09b54ac84fb805c7747e77d28.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/065546000c00fd6043515d3ae299955dbd75baf09b54ac84fb805c7747e77d28.jpg)

![1628d4e270b61645e56c3c50cf517e4e37985537519ef5b357aba773ddbe504e.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/1628d4e270b61645e56c3c50cf517e4e37985537519ef5b357aba773ddbe504e.jpg)

![29cec61cd2d2da4f37a14407c0fec318e19e2d0657eeccd6503cd5c6140463c5.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/29cec61cd2d2da4f37a14407c0fec318e19e2d0657eeccd6503cd5c6140463c5.jpg)

![4eb3865996808563251938c25556bb81597416154fc59ba9deb42a2e367bcf22.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/4eb3865996808563251938c25556bb81597416154fc59ba9deb42a2e367bcf22.jpg)

![58708277ec4a2097b2869f96018e5dda05ae97e68b61a8b5801631866d8f1403.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/58708277ec4a2097b2869f96018e5dda05ae97e68b61a8b5801631866d8f1403.jpg)

![60c7a1389a21cfecf653e09330840f412009a24558877a439df36fa319b18ff7.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/60c7a1389a21cfecf653e09330840f412009a24558877a439df36fa319b18ff7.jpg)

![6d7fb9ec33ec52e905521135c1242e0554765b18cefef94bb3d737e23ab4641a.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/6d7fb9ec33ec52e905521135c1242e0554765b18cefef94bb3d737e23ab4641a.jpg)

![726762ca8e0fd85221bba819fc9827c7f3956ed103834742243857071df368e7.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/726762ca8e0fd85221bba819fc9827c7f3956ed103834742243857071df368e7.jpg)

![985288fa4371b2c1f953587306975257049fbe063a8d809687419a559e1a0748.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/985288fa4371b2c1f953587306975257049fbe063a8d809687419a559e1a0748.jpg)

![c49ab3829c6a2953e9903be500ece7214b191654ded195055a0aa7c22a722cea.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/c49ab3829c6a2953e9903be500ece7214b191654ded195055a0aa7c22a722cea.jpg)

![c6f28e167b4c0be7d1aefeb7012bfa6cc0eea71f85721fcc2405a5d1100ff003.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/c6f28e167b4c0be7d1aefeb7012bfa6cc0eea71f85721fcc2405a5d1100ff003.jpg)

![c8b0bfeabd32048d894f163960bd20d91b17de03c0e0f4de4c9d0a1acd63f011.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/c8b0bfeabd32048d894f163960bd20d91b17de03c0e0f4de4c9d0a1acd63f011.jpg)

![eb1fef5417fece4221af3155c3c461a73a651c17480fb6347b0347b3f2cb548b.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/eb1fef5417fece4221af3155c3c461a73a651c17480fb6347b0347b3f2cb548b.jpg)

![eb4a7384de40d9415735417712622ce2cb562d106e44446c944e9a806f1b8325.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/eb4a7384de40d9415735417712622ce2cb562d106e44446c944e9a806f1b8325.jpg)

![ed0b0389d6554e00aa6562e052b1ec37da7eb7f798a860685ddcf3827dce021d.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/ed0b0389d6554e00aa6562e052b1ec37da7eb7f798a860685ddcf3827dce021d.jpg)

![f31c641f59ab1ed49540831733c8d80b7189b1372cf67712733de2bde25fa341.jpg](../nips_results/4608_Unlocking%20Multimodal%20Mathematical%20Reasoning%20via%20Process%20Reward%20Model/tables/f31c641f59ab1ed49540831733c8d80b7189b1372cf67712733de2bde25fa341.jpg)

## Prompted Policy Search: Reinforcement Learning through Linguistic and Numerical Reasoning in LLMs


### Images

![1245529a63ec9244f30be52ee4eac208c75240a32915aef8dac16919cf2b108e.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/1245529a63ec9244f30be52ee4eac208c75240a32915aef8dac16919cf2b108e.jpg)

![1dff4c7efbfe1c346b29719221ba9fc746d57fc71fb8991df6320afc98199bae.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/1dff4c7efbfe1c346b29719221ba9fc746d57fc71fb8991df6320afc98199bae.jpg)

![3ed4fa5c5351513898b50e098b4e5cf16a81e50ca2f4ff451e345e6f8359e8a0.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/3ed4fa5c5351513898b50e098b4e5cf16a81e50ca2f4ff451e345e6f8359e8a0.jpg)

![52df1fc5a22c93a3c8abc31cba0d697c0d613d07e75e9aedbcd4eccf76d695b9.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/52df1fc5a22c93a3c8abc31cba0d697c0d613d07e75e9aedbcd4eccf76d695b9.jpg)

![66c92b5dce603cd94cedf43c720f6d1b1c9850dbbbc59dba11840d1e05dcb6b3.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/66c92b5dce603cd94cedf43c720f6d1b1c9850dbbbc59dba11840d1e05dcb6b3.jpg)

![6e3a8dde80e4b8fcaa8fafd58504aa0ab2207530ae8363795aea02037af64349.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/6e3a8dde80e4b8fcaa8fafd58504aa0ab2207530ae8363795aea02037af64349.jpg)

![79a86285e4770c6fea782e763f4496fb2a91705b417ae72c1e0e72151f84278a.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/79a86285e4770c6fea782e763f4496fb2a91705b417ae72c1e0e72151f84278a.jpg)

![7cec5cb32ba13cc47c8603d1551eab5eca211807fedd3afbc881ed3959ac81bf.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/7cec5cb32ba13cc47c8603d1551eab5eca211807fedd3afbc881ed3959ac81bf.jpg)

![7e05527f5c8cc578b55ed2ea63bd7009d40fa957bafdd8c6ae49c1b985b61e39.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/7e05527f5c8cc578b55ed2ea63bd7009d40fa957bafdd8c6ae49c1b985b61e39.jpg)

![83d6acf9645495c50998755196466bdc5f048802e6402ba61c9b992c71a54fe1.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/83d6acf9645495c50998755196466bdc5f048802e6402ba61c9b992c71a54fe1.jpg)

![892d716c41a4d117843f5590aacb8c5e99382d91f5864c23c2148d30792e38c5.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/892d716c41a4d117843f5590aacb8c5e99382d91f5864c23c2148d30792e38c5.jpg)

![8f8de54db9504dbb3940db226411fe197e7abca25eb41b4f61a130d1f87574ef.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/8f8de54db9504dbb3940db226411fe197e7abca25eb41b4f61a130d1f87574ef.jpg)

![a105799bf462615580912f35cc09fb65902231e480e849cfea67dd947df66a25.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/a105799bf462615580912f35cc09fb65902231e480e849cfea67dd947df66a25.jpg)

![ae57576e041810e294670146252dc249c9f4318d8da35b506f6554342a5f99bf.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/ae57576e041810e294670146252dc249c9f4318d8da35b506f6554342a5f99bf.jpg)

![d93aadd12e4c65efd5ea19fcd47e85f97d4605db3abbcbff85b6e758c0355e49.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/images/d93aadd12e4c65efd5ea19fcd47e85f97d4605db3abbcbff85b6e758c0355e49.jpg)

### Tables

![0d0f0c8169793d66cce97f8e2996f00e469d714c1f5d570a95520d50c48a9fed.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/0d0f0c8169793d66cce97f8e2996f00e469d714c1f5d570a95520d50c48a9fed.jpg)

![11448fb544c192da2129b8ddee1674e4e80dd3be9773629acce9df4d7cab3147.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/11448fb544c192da2129b8ddee1674e4e80dd3be9773629acce9df4d7cab3147.jpg)

![199bc91212aba601170a950b92e4fc8ba8a5f1461912a7bdcbed3a432906fbc5.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/199bc91212aba601170a950b92e4fc8ba8a5f1461912a7bdcbed3a432906fbc5.jpg)

![1e4c829dfcfa181993adfad151384302ee55f3128ed17f20c090b246166052ac.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/1e4c829dfcfa181993adfad151384302ee55f3128ed17f20c090b246166052ac.jpg)

![a6135fad17a9cdc49a7115f98e7813587a4ec7406502771349780a9b34060d38.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/a6135fad17a9cdc49a7115f98e7813587a4ec7406502771349780a9b34060d38.jpg)

![b52c3197c9b709e0aea14d59d8160736a0223f14c581aa7bef965f56b72410fd.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/b52c3197c9b709e0aea14d59d8160736a0223f14c581aa7bef965f56b72410fd.jpg)

![bfb3293fd93ed68d44c6a0c0bec2a33136c00ff01505436d45a47217b02c122d.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/bfb3293fd93ed68d44c6a0c0bec2a33136c00ff01505436d45a47217b02c122d.jpg)

![c09faa997ac7c135f799f41fd1d4c944e56102d9c2f543be55e5d30238c3895f.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/c09faa997ac7c135f799f41fd1d4c944e56102d9c2f543be55e5d30238c3895f.jpg)

![d0fdeb94cd2b0e6ed6ed6d9fafc472734e08dcd9fb386841185ae16d2deb5d26.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/d0fdeb94cd2b0e6ed6ed6d9fafc472734e08dcd9fb386841185ae16d2deb5d26.jpg)

![d4baee40ed7b1beecace5a005b4bf9c646fa4ae03d423eba46a0e0cba01d7f14.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/d4baee40ed7b1beecace5a005b4bf9c646fa4ae03d423eba46a0e0cba01d7f14.jpg)

![d80e0a32271a6e5dfa50fd3d3e09d4246fd471d050b525b9156d6c0cc8e6e48b.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/d80e0a32271a6e5dfa50fd3d3e09d4246fd471d050b525b9156d6c0cc8e6e48b.jpg)

![f2146e33e48197ff80d666e1ebff59974db55787bf2b9f67507c5e916b466a96.jpg](../nips_results/4609_Prompted%20Policy%20Search_%20Reinforcement%20Learning%20through%20Linguistic%20and%20Numerical%20Reasoning%20in%20LLMs/tables/f2146e33e48197ff80d666e1ebff59974db55787bf2b9f67507c5e916b466a96.jpg)

## Best-of-N Jailbreaking


### Images

![0bb0cf5690432fac4f47dcb007d62f05e91b2304a1ac1fa08e8e2819bdb3f167.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/0bb0cf5690432fac4f47dcb007d62f05e91b2304a1ac1fa08e8e2819bdb3f167.jpg)

![0fb4417907f1a938be0182a4a8478244cccb30a272cbf47a2a36580beb91755d.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/0fb4417907f1a938be0182a4a8478244cccb30a272cbf47a2a36580beb91755d.jpg)

![19f6b024ce7e6ed524dd83067ec8ad074385789f9a140f605fb70aa9ff1287b7.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/19f6b024ce7e6ed524dd83067ec8ad074385789f9a140f605fb70aa9ff1287b7.jpg)

![23d76415a447ba2d45d6e60297e76fd483a80422ca1b0c8f6ed072f862dd3e87.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/23d76415a447ba2d45d6e60297e76fd483a80422ca1b0c8f6ed072f862dd3e87.jpg)

![290e22c44c78a957df1de85f73d4a3eb075fef35358f7a8b8818bf83013a0b5f.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/290e22c44c78a957df1de85f73d4a3eb075fef35358f7a8b8818bf83013a0b5f.jpg)

![2efcc11d1ef08f19814aa24ceadd5faf1e89e225ce4dd014ac94e600d8b2cfd1.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/2efcc11d1ef08f19814aa24ceadd5faf1e89e225ce4dd014ac94e600d8b2cfd1.jpg)

![33f591eec439fa7ea70f1718af64c7c4d0d12b5c67d783a5662350a18bc224fd.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/33f591eec439fa7ea70f1718af64c7c4d0d12b5c67d783a5662350a18bc224fd.jpg)

![36bd0b1d80c1b2f28bc677ae0fa1b18360afedd29ee573d9878c97855f7e8e15.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/36bd0b1d80c1b2f28bc677ae0fa1b18360afedd29ee573d9878c97855f7e8e15.jpg)

![3b717ae4fd7a8a46408d817aa78be9553685566e75ec76c8766b09370a219507.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/3b717ae4fd7a8a46408d817aa78be9553685566e75ec76c8766b09370a219507.jpg)

![3c8f81b1a9c6e4cd2123d766690748bb6aa5655e5eb6c422b000dc3057f78279.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/3c8f81b1a9c6e4cd2123d766690748bb6aa5655e5eb6c422b000dc3057f78279.jpg)

![426a030aef94fd7b7621a7e818c95466f063c471a9282a0c07d6bbe10813cfed.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/426a030aef94fd7b7621a7e818c95466f063c471a9282a0c07d6bbe10813cfed.jpg)

![4fb2f68f13d18a28cec39b72efc67f3b862de2814537c2f5a031450f12193ea0.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/4fb2f68f13d18a28cec39b72efc67f3b862de2814537c2f5a031450f12193ea0.jpg)

![6427b7bbd97cdeed080cc45644e3479ed6020dfa0bef9e8ada405de0b6141b5c.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/6427b7bbd97cdeed080cc45644e3479ed6020dfa0bef9e8ada405de0b6141b5c.jpg)

![66b3a613cc09ba6019368ebbb76f946d1bf234b916262b0dcf1fe18c6a67dd56.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/66b3a613cc09ba6019368ebbb76f946d1bf234b916262b0dcf1fe18c6a67dd56.jpg)

![66ccabd14ec74530a27d1eec70d3584c1b07490289a9fa5c600c716290dfbbd8.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/66ccabd14ec74530a27d1eec70d3584c1b07490289a9fa5c600c716290dfbbd8.jpg)

![687b34b12718b3aacfc38445dcdf794b96e19d9e3308dfae573620feca2a061d.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/687b34b12718b3aacfc38445dcdf794b96e19d9e3308dfae573620feca2a061d.jpg)

![6c02964d75a80119941624d955b1251fc5894a5318da18a6b2158114fa0a46da.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/6c02964d75a80119941624d955b1251fc5894a5318da18a6b2158114fa0a46da.jpg)

![6d76d5ad23ddcc778c07ab6fc652a11f7e43e4e8dcc4e2cfb70fda2a0fb15b18.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/6d76d5ad23ddcc778c07ab6fc652a11f7e43e4e8dcc4e2cfb70fda2a0fb15b18.jpg)

![6ff65f377789e55232003ef0eadcb5d91862d0997c4c5098487270f6af2ac37f.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/6ff65f377789e55232003ef0eadcb5d91862d0997c4c5098487270f6af2ac37f.jpg)

![71094022249a687b788328d6ca4bdcd435391a91e910c7df54ae236ff221e631.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/71094022249a687b788328d6ca4bdcd435391a91e910c7df54ae236ff221e631.jpg)

![71bfa2301ed45ad337a9986e5f14cbd7a5e329ebf7cc602643dea6689d5db563.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/71bfa2301ed45ad337a9986e5f14cbd7a5e329ebf7cc602643dea6689d5db563.jpg)

![73209f9481c23a1044f385a03de15f5ff6e1a52a5b80017b0128fccbcb71eddd.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/73209f9481c23a1044f385a03de15f5ff6e1a52a5b80017b0128fccbcb71eddd.jpg)

![7a90be3c3f381914cda5258634f298e7481aef331bda47bc5fcd19453e3a3434.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/7a90be3c3f381914cda5258634f298e7481aef331bda47bc5fcd19453e3a3434.jpg)

![7d49f2558668595149402090637368d9c578aeabb733bd6ff0218d92c82b9c25.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/7d49f2558668595149402090637368d9c578aeabb733bd6ff0218d92c82b9c25.jpg)

![802c69c165ecc68389654c9f59bcd87ed0a122017bc73a85ba3771d572bef388.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/802c69c165ecc68389654c9f59bcd87ed0a122017bc73a85ba3771d572bef388.jpg)

![824ddc07eb88c560f51eacb77dbc284a9ec8a13576702d288603ccbfa86c19c3.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/824ddc07eb88c560f51eacb77dbc284a9ec8a13576702d288603ccbfa86c19c3.jpg)

![83585e182fb028ceb917ad53b8144eb24b0b8fa7a7c9a5a198213c499f38cf66.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/83585e182fb028ceb917ad53b8144eb24b0b8fa7a7c9a5a198213c499f38cf66.jpg)

![8f1f3910d72cf2de98093a696a832c7b01eb23a417bdb7bde59d5087c04e3659.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/8f1f3910d72cf2de98093a696a832c7b01eb23a417bdb7bde59d5087c04e3659.jpg)

![94061cb5c48d7dc2282b7016280bb948ba75c949ba9e028bd97d4a2131e4a9a4.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/94061cb5c48d7dc2282b7016280bb948ba75c949ba9e028bd97d4a2131e4a9a4.jpg)

![9cd969985e4e4e2e6389d652c89f44ade94a0254923d5d5fde04733cbca16c9b.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/9cd969985e4e4e2e6389d652c89f44ade94a0254923d5d5fde04733cbca16c9b.jpg)

![9f48c149a7500a126be867b240e17cab6fb363cef3ad1e5163e41c2c823c4248.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/9f48c149a7500a126be867b240e17cab6fb363cef3ad1e5163e41c2c823c4248.jpg)

![a39aec07f2508a67d06b6274e751c1205e1e6be8552d9f266a7f54fa6d119130.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/a39aec07f2508a67d06b6274e751c1205e1e6be8552d9f266a7f54fa6d119130.jpg)

![a5103522d5939df24803e4f92a188398da0e1c6d6766792f69ad868d206b66f7.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/a5103522d5939df24803e4f92a188398da0e1c6d6766792f69ad868d206b66f7.jpg)

![a8e527862f3da653502609b56e00003995c9cf00f11a2dd0d90de7bfaa359c59.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/a8e527862f3da653502609b56e00003995c9cf00f11a2dd0d90de7bfaa359c59.jpg)

![afce763be2a647aa820a26ff78ca4109ea294c23c7e3d46b6ee15cadb7650ddd.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/afce763be2a647aa820a26ff78ca4109ea294c23c7e3d46b6ee15cadb7650ddd.jpg)

![b31fe075bbe808b192599e53851b46756f01012c71dfbb2572f0142aab29596b.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/b31fe075bbe808b192599e53851b46756f01012c71dfbb2572f0142aab29596b.jpg)

![b4fbfba4cff04d571e3e7dda72bb43c432b1169943f5b76e6b8222eed5bcd5a7.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/b4fbfba4cff04d571e3e7dda72bb43c432b1169943f5b76e6b8222eed5bcd5a7.jpg)

![baf0956cda7d696ae5ea791e82b0d5e3a4c3c804302e3cbe2e13ee3320b756b4.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/baf0956cda7d696ae5ea791e82b0d5e3a4c3c804302e3cbe2e13ee3320b756b4.jpg)

![c0dee7f24cf09705f0819552dfb457926c58daaf3e9356116e589e898b9b4b19.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/c0dee7f24cf09705f0819552dfb457926c58daaf3e9356116e589e898b9b4b19.jpg)

![c2f741a4b91aa9621ab2b5f1a89940502911ee0d546546927768f7cc601d6214.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/c2f741a4b91aa9621ab2b5f1a89940502911ee0d546546927768f7cc601d6214.jpg)

![c7841d89dcab00c73f97ecb95ebbba6e83e67686be63645b602bed955ebfd239.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/c7841d89dcab00c73f97ecb95ebbba6e83e67686be63645b602bed955ebfd239.jpg)

![cd4dc7b04f8db0744a02c1f25250a8fa4e6f66d1677673ab96ba733ceddaba44.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/cd4dc7b04f8db0744a02c1f25250a8fa4e6f66d1677673ab96ba733ceddaba44.jpg)

![d3cc6561f517e5e5e9f9d7d90f58702588e601bfe4318c90ab34af17e01d28a2.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/d3cc6561f517e5e5e9f9d7d90f58702588e601bfe4318c90ab34af17e01d28a2.jpg)

![d46b88ab1b7676c7adc1eacbf7dfa46e24ca840d41efd8f29d5a3a3360d83c20.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/d46b88ab1b7676c7adc1eacbf7dfa46e24ca840d41efd8f29d5a3a3360d83c20.jpg)

![d5edfe6ccad24e70158e49a78f5180967c0e4a91613c069a2b6468e2acf9f9d0.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/d5edfe6ccad24e70158e49a78f5180967c0e4a91613c069a2b6468e2acf9f9d0.jpg)

![d8fdd2f359cd28e4a5f134811f784f047fe3667fd46b9dbe3582dd5d97c62554.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/d8fdd2f359cd28e4a5f134811f784f047fe3667fd46b9dbe3582dd5d97c62554.jpg)

![e62ac6cb82c834a9c88d70a2f51e480b44522b0fd86f16d82bf098becb22bb2a.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/e62ac6cb82c834a9c88d70a2f51e480b44522b0fd86f16d82bf098becb22bb2a.jpg)

![e8f60d478c92530263ef27d1741ef764c86fb64d0bfc34fa708b79cbda0a2532.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/e8f60d478c92530263ef27d1741ef764c86fb64d0bfc34fa708b79cbda0a2532.jpg)

![ec7ce5a154ff941dccf18a838a4b7d371bcabefe1db23d81b7990c9e9b17b2d4.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/ec7ce5a154ff941dccf18a838a4b7d371bcabefe1db23d81b7990c9e9b17b2d4.jpg)

![f539e2f4bb32e71e42c9c3f942fc8c00ac9f379cf33a61e529c6ea3ca9bc385f.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/f539e2f4bb32e71e42c9c3f942fc8c00ac9f379cf33a61e529c6ea3ca9bc385f.jpg)

![f73afabf44a025ac632fd7ff0007c4167d5b5244f0625158901248442da6a709.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/f73afabf44a025ac632fd7ff0007c4167d5b5244f0625158901248442da6a709.jpg)

![f7fa6464c5f503875633387625b24202dd2ffa9d878395343eaaf1893665377f.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/f7fa6464c5f503875633387625b24202dd2ffa9d878395343eaaf1893665377f.jpg)

![ff8bc4a3ed139f6d266df8de98e24335b17af7281e312069b0a5dc8089560270.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/images/ff8bc4a3ed139f6d266df8de98e24335b17af7281e312069b0a5dc8089560270.jpg)

### Tables

![27851a5919f4257d0e9e2034a0048312d0ac231b5acab16904dddf915699901e.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/tables/27851a5919f4257d0e9e2034a0048312d0ac231b5acab16904dddf915699901e.jpg)

![44884e7708e18d8f4c716efea7495b6eefd3b8817ffefd3dc65d48f5a88bdf7d.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/tables/44884e7708e18d8f4c716efea7495b6eefd3b8817ffefd3dc65d48f5a88bdf7d.jpg)

![5feae95d356c0937c85bbafe41818b541c3afbd65d5147b28e748795c6f60d2e.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/tables/5feae95d356c0937c85bbafe41818b541c3afbd65d5147b28e748795c6f60d2e.jpg)

![6128364874f04889fd2bdddd0fa35e81d45e197d86cbcc4fca8a576bfc8c3f13.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/tables/6128364874f04889fd2bdddd0fa35e81d45e197d86cbcc4fca8a576bfc8c3f13.jpg)

![6cea724fcd45a2c059484ce66802eb1853a3d6d2b543ca3819d386b154a56af9.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/tables/6cea724fcd45a2c059484ce66802eb1853a3d6d2b543ca3819d386b154a56af9.jpg)

![766f109a482f4ec62dbbd6867464ac1a5608b40cd482de9fad092dd69a4cea51.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/tables/766f109a482f4ec62dbbd6867464ac1a5608b40cd482de9fad092dd69a4cea51.jpg)

![8ed5582a4cf9181149e7b97e8af824e53ae3eb3f3e886f121d716d4c430a3e70.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/tables/8ed5582a4cf9181149e7b97e8af824e53ae3eb3f3e886f121d716d4c430a3e70.jpg)

![a8cd1bb202d5a796554a4eb69ca050051174b2631e42b710ce537649c3079a45.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/tables/a8cd1bb202d5a796554a4eb69ca050051174b2631e42b710ce537649c3079a45.jpg)

![b46194110b046fbd9f4c60676275a0654d562225a7a9aa4c265e58f3375271f3.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/tables/b46194110b046fbd9f4c60676275a0654d562225a7a9aa4c265e58f3375271f3.jpg)

![bf57ac5415ff684fa5cd117dcf8456901f9227f73d894b7d54bfca728be801ae.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/tables/bf57ac5415ff684fa5cd117dcf8456901f9227f73d894b7d54bfca728be801ae.jpg)

![c8e0ebd981b6663a1eb0e2042489dd2c028b902997e0bd801fefb9ffe2ae07f4.jpg](../nips_results/4610_Best-of-N%20Jailbreaking/tables/c8e0ebd981b6663a1eb0e2042489dd2c028b902997e0bd801fefb9ffe2ae07f4.jpg)

## Safety Pretraining: Toward the Next Generation of Safe AI


### Images

![0d4b2f5606867a59378d8d243858bbb9d6a14fb9b1d6b6e2d271471f21676694.jpg](../nips_results/4611_Safety%20Pretraining_%20Toward%20the%20Next%20Generation%20of%20Safe%20AI/images/0d4b2f5606867a59378d8d243858bbb9d6a14fb9b1d6b6e2d271471f21676694.jpg)

![0d892d6b3648d85a3eeeb1928cfed418a6304e58744ef1752209326cb339ef52.jpg](../nips_results/4611_Safety%20Pretraining_%20Toward%20the%20Next%20Generation%20of%20Safe%20AI/images/0d892d6b3648d85a3eeeb1928cfed418a6304e58744ef1752209326cb339ef52.jpg)

![20787c9b39c6096f92f1249ec9582e48feae7c948a1ae94f2f5a3ebf278704f0.jpg](../nips_results/4611_Safety%20Pretraining_%20Toward%20the%20Next%20Generation%20of%20Safe%20AI/images/20787c9b39c6096f92f1249ec9582e48feae7c948a1ae94f2f5a3ebf278704f0.jpg)

![2bad63ea28da93d33f2b3494b3be85d46ac55c0819c7dcefba9cd2e649635368.jpg](../nips_results/4611_Safety%20Pretraining_%20Toward%20the%20Next%20Generation%20of%20Safe%20AI/images/2bad63ea28da93d33f2b3494b3be85d46ac55c0819c7dcefba9cd2e649635368.jpg)

![528ba75e6d483aeef8bfdba150312791a46ce16063b893dc5bc8e26cf59316eb.jpg](../nips_results/4611_Safety%20Pretraining_%20Toward%20the%20Next%20Generation%20of%20Safe%20AI/images/528ba75e6d483aeef8bfdba150312791a46ce16063b893dc5bc8e26cf59316eb.jpg)

![ad376ed69a5dcebcae9dc8a84c7da404344f0adf0223cc57eeb870cb8bb6fe54.jpg](../nips_results/4611_Safety%20Pretraining_%20Toward%20the%20Next%20Generation%20of%20Safe%20AI/images/ad376ed69a5dcebcae9dc8a84c7da404344f0adf0223cc57eeb870cb8bb6fe54.jpg)

![beabd5585487dcf6fa5a330bacd4d1e3be596722a9ee04606aeee43e375a9df6.jpg](../nips_results/4611_Safety%20Pretraining_%20Toward%20the%20Next%20Generation%20of%20Safe%20AI/images/beabd5585487dcf6fa5a330bacd4d1e3be596722a9ee04606aeee43e375a9df6.jpg)

![e274fb14df8586d7948a267918525e9a2f8fd8556f18f628810b0994c92bd861.jpg](../nips_results/4611_Safety%20Pretraining_%20Toward%20the%20Next%20Generation%20of%20Safe%20AI/images/e274fb14df8586d7948a267918525e9a2f8fd8556f18f628810b0994c92bd861.jpg)

### Tables

![27027dbb2754bb6174d9b4031e44130a44d85d34427b6672989a212911053f54.jpg](../nips_results/4611_Safety%20Pretraining_%20Toward%20the%20Next%20Generation%20of%20Safe%20AI/tables/27027dbb2754bb6174d9b4031e44130a44d85d34427b6672989a212911053f54.jpg)

![44091fa51173c5107a04adfc1bd77412bf250317496a840c5606d29fb06dfa04.jpg](../nips_results/4611_Safety%20Pretraining_%20Toward%20the%20Next%20Generation%20of%20Safe%20AI/tables/44091fa51173c5107a04adfc1bd77412bf250317496a840c5606d29fb06dfa04.jpg)

![d30f6a308fd40a2f4fe713a80a01180df1da49afc7f9b05367e14f0c3a2602ba.jpg](../nips_results/4611_Safety%20Pretraining_%20Toward%20the%20Next%20Generation%20of%20Safe%20AI/tables/d30f6a308fd40a2f4fe713a80a01180df1da49afc7f9b05367e14f0c3a2602ba.jpg)

## Linear Differential Vision Transformer: Learning Visual Contrasts via Pairwise Differentials


### Tables

![16ae74ae49e26eeea9a2757a4b2d6f1a8630996ca22a29995df13de573f8d9a2.jpg](../nips_results/4612_Linear%20Differential%20Vision%20Transformer_%20Learning%20Visual%20Contrasts%20via%20Pairwise%20Differentials/tables/16ae74ae49e26eeea9a2757a4b2d6f1a8630996ca22a29995df13de573f8d9a2.jpg)

![260620a50960f59821c8b05aa99edf7f8df00f24595931898318ffca18635aa0.jpg](../nips_results/4612_Linear%20Differential%20Vision%20Transformer_%20Learning%20Visual%20Contrasts%20via%20Pairwise%20Differentials/tables/260620a50960f59821c8b05aa99edf7f8df00f24595931898318ffca18635aa0.jpg)

![3acc96abbab9360774da4b2118f6f89501bde7234f86044c16310ba30a343e13.jpg](../nips_results/4612_Linear%20Differential%20Vision%20Transformer_%20Learning%20Visual%20Contrasts%20via%20Pairwise%20Differentials/tables/3acc96abbab9360774da4b2118f6f89501bde7234f86044c16310ba30a343e13.jpg)

![b8359886b97ac0ae4cbf6b365bcd0d54ea464d455cd42c20a8cc9f778063713e.jpg](../nips_results/4612_Linear%20Differential%20Vision%20Transformer_%20Learning%20Visual%20Contrasts%20via%20Pairwise%20Differentials/tables/b8359886b97ac0ae4cbf6b365bcd0d54ea464d455cd42c20a8cc9f778063713e.jpg)

![e7dd2baae498396dd942247ad29b60234aafec9d48d37657a377d8c99f5e5d5c.jpg](../nips_results/4612_Linear%20Differential%20Vision%20Transformer_%20Learning%20Visual%20Contrasts%20via%20Pairwise%20Differentials/tables/e7dd2baae498396dd942247ad29b60234aafec9d48d37657a377d8c99f5e5d5c.jpg)

![ea111f9d31248ff925675ea6b670ce5dfe4a0b137ac67662d55b69316a8427ff.jpg](../nips_results/4612_Linear%20Differential%20Vision%20Transformer_%20Learning%20Visual%20Contrasts%20via%20Pairwise%20Differentials/tables/ea111f9d31248ff925675ea6b670ce5dfe4a0b137ac67662d55b69316a8427ff.jpg)

## Hierarchical Implicit Neural Emulators


### Images

![091692ede69d261d00a3a0635b87ed12d9d66dde6f657e96e47082f72d39cccd.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/091692ede69d261d00a3a0635b87ed12d9d66dde6f657e96e47082f72d39cccd.jpg)

![352a2be9918638100e3eed9afbca57703e9f3c094263b9f1c3be5648e4bda39c.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/352a2be9918638100e3eed9afbca57703e9f3c094263b9f1c3be5648e4bda39c.jpg)

![74b4b8707da1a40671553aa331b6c0fb7d6deb9f78756cbd63030c8727fa6173.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/74b4b8707da1a40671553aa331b6c0fb7d6deb9f78756cbd63030c8727fa6173.jpg)

![7a1e79c3439e63fc50654ffa2b86e75cdefc6e9e374129fe0eac6e3716323441.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/7a1e79c3439e63fc50654ffa2b86e75cdefc6e9e374129fe0eac6e3716323441.jpg)

![7a74fc9296cc0bb0e801b642a2e3964a846a7352a2212c8465c3585398e7ebe9.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/7a74fc9296cc0bb0e801b642a2e3964a846a7352a2212c8465c3585398e7ebe9.jpg)

![834a4770e444f96efbfde0f0e349a16c22d7d13d3dc51b969f3d7a89961d3af8.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/834a4770e444f96efbfde0f0e349a16c22d7d13d3dc51b969f3d7a89961d3af8.jpg)

![a1c4030b1be386df98f4646516a4daadb1d895ecb77bc25417ce4965f458bfd7.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/a1c4030b1be386df98f4646516a4daadb1d895ecb77bc25417ce4965f458bfd7.jpg)

![b09bb168610e0597505caba82d37a626859dd7962e089370f90ddcb07705e097.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/b09bb168610e0597505caba82d37a626859dd7962e089370f90ddcb07705e097.jpg)

![b51b2d34a31eb6d0b9baec77c3dd04753804a1f8abb73488f2abb000754927b5.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/b51b2d34a31eb6d0b9baec77c3dd04753804a1f8abb73488f2abb000754927b5.jpg)

![bc994b70f30997e2ba6f80d81ec4873577f88b18cc401fdec155684d299363ed.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/bc994b70f30997e2ba6f80d81ec4873577f88b18cc401fdec155684d299363ed.jpg)

![c941bf63aa51afdffdf8be87d9741f63e032619a0e69e28393a4f85a8854dbf9.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/c941bf63aa51afdffdf8be87d9741f63e032619a0e69e28393a4f85a8854dbf9.jpg)

![cc04cad2d4cacc2703231735691769c2a4c063a568a4c10d8a286ae59f419915.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/cc04cad2d4cacc2703231735691769c2a4c063a568a4c10d8a286ae59f419915.jpg)

![d2cb0bb38780a56563d288844a3814eb440ab56737069dd044f54b483ac68592.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/d2cb0bb38780a56563d288844a3814eb440ab56737069dd044f54b483ac68592.jpg)

![d834602b1c6bba93cdb14c5f8cfdf865a8391e72800240397d37305e4d045b58.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/d834602b1c6bba93cdb14c5f8cfdf865a8391e72800240397d37305e4d045b58.jpg)

![e4d1de8fce389a69a020920882d42a63999cc49c901f8375af1c33ff41541ada.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/e4d1de8fce389a69a020920882d42a63999cc49c901f8375af1c33ff41541ada.jpg)

![f229f2cdba5bcf533d4c9aee41685f2e594a6f885e4262fc225c10c7e432b4c3.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/f229f2cdba5bcf533d4c9aee41685f2e594a6f885e4262fc225c10c7e432b4c3.jpg)

![f9d454704632fbba53a721ca58e665e1a546f2444446221d9625ed195beb23d6.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/images/f9d454704632fbba53a721ca58e665e1a546f2444446221d9625ed195beb23d6.jpg)

### Tables

![2616c31aaf17986300dcab7758259f31e8b6a4ac6f0bcd7c17861f7b37dae5a8.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/tables/2616c31aaf17986300dcab7758259f31e8b6a4ac6f0bcd7c17861f7b37dae5a8.jpg)

![4f6b656b44828f853de6ff2a53bf72fa0e553243577b7c49efa63e6dce0a8d1b.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/tables/4f6b656b44828f853de6ff2a53bf72fa0e553243577b7c49efa63e6dce0a8d1b.jpg)

![6bafafe47dbebb813d00e381ab71085e54cb24d98984bbc164db0da9126bc0b9.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/tables/6bafafe47dbebb813d00e381ab71085e54cb24d98984bbc164db0da9126bc0b9.jpg)

![73e1d45eb056017a712732f1614c525ee677b3588ed8fb188c18c1c169aba544.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/tables/73e1d45eb056017a712732f1614c525ee677b3588ed8fb188c18c1c169aba544.jpg)

![87bb8a12ef0a581e4add2c58011b55d01bfcf6412bc98503701c5142eb2f1945.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/tables/87bb8a12ef0a581e4add2c58011b55d01bfcf6412bc98503701c5142eb2f1945.jpg)

![c477c2d8ba3ea495797e7363803d4dcbccccb72813b48fbc4f1acc5bcfd6eb79.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/tables/c477c2d8ba3ea495797e7363803d4dcbccccb72813b48fbc4f1acc5bcfd6eb79.jpg)

![c9a07f4a65c2e82207716efa806fc6c1eb7290b0e0114e1e2a3380c9073ab2d7.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/tables/c9a07f4a65c2e82207716efa806fc6c1eb7290b0e0114e1e2a3380c9073ab2d7.jpg)

![c9e7723ce5e72f7b4bc815e20a6c84e1aaeb07989bc46624ed86ca0e6f0731ec.jpg](../nips_results/4613_Hierarchical%20Implicit%20Neural%20Emulators/tables/c9e7723ce5e72f7b4bc815e20a6c84e1aaeb07989bc46624ed86ca0e6f0731ec.jpg)

## RetrievalAttention: Accelerating Long-Context LLM Inference via Vector Retrieval


### Images

![1aa643ef29e34590b0ddd707011c2d2727a5aec3390c09485f98bcfbebf1bd03.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/1aa643ef29e34590b0ddd707011c2d2727a5aec3390c09485f98bcfbebf1bd03.jpg)

![266392726c11c1725597b9ef7f25022214f014f7fa27b9add62e80a5280e88ac.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/266392726c11c1725597b9ef7f25022214f014f7fa27b9add62e80a5280e88ac.jpg)

![39fa9c621e0272ec2b0cd3afe827933a2be4d6c62d114dbfc60c97cb35646621.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/39fa9c621e0272ec2b0cd3afe827933a2be4d6c62d114dbfc60c97cb35646621.jpg)

![3aac4a48864a25124afbadb85a66c4fdc39897102d71a16bded4222aefb50c50.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/3aac4a48864a25124afbadb85a66c4fdc39897102d71a16bded4222aefb50c50.jpg)

![3f2489d794fb3db3d3a26b8d3a878eacb896ed7af93bacb844907bfebdb8ff9f.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/3f2489d794fb3db3d3a26b8d3a878eacb896ed7af93bacb844907bfebdb8ff9f.jpg)

![470a14e3eb7e6472875b354b7508f616598decba98a5ee1b90b121f6ea0d3608.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/470a14e3eb7e6472875b354b7508f616598decba98a5ee1b90b121f6ea0d3608.jpg)

![5cfaa8992f3d915b3674dccacd27b213b6e42255ebeeceb50fbde535e3d36171.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/5cfaa8992f3d915b3674dccacd27b213b6e42255ebeeceb50fbde535e3d36171.jpg)

![8c936f789d865de01ecc5e5dcb3ce19160aa0b52143d63f16dc6ee7ac18c63c6.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/8c936f789d865de01ecc5e5dcb3ce19160aa0b52143d63f16dc6ee7ac18c63c6.jpg)

![b112cf40e1914e43124afb1525e858822ae77f0381b46dea2fddb728b461f3ad.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/b112cf40e1914e43124afb1525e858822ae77f0381b46dea2fddb728b461f3ad.jpg)

![cb37a1f38f4524d44d05739730109db5436477aba4b5a7709c92a5173403e8bf.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/cb37a1f38f4524d44d05739730109db5436477aba4b5a7709c92a5173403e8bf.jpg)

![d1b1fcf632e3bcf669a236cb8446941500b208f420f99b6854a9563adde3f7dd.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/d1b1fcf632e3bcf669a236cb8446941500b208f420f99b6854a9563adde3f7dd.jpg)

![f4f0153389f421a56175db6ec3ca7de9f22754cabd52cd1242746b21a4ee5abb.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/f4f0153389f421a56175db6ec3ca7de9f22754cabd52cd1242746b21a4ee5abb.jpg)

![fabb84306b99e795904a977a722006395671cbdfacd1837362266efcd5e3542c.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/images/fabb84306b99e795904a977a722006395671cbdfacd1837362266efcd5e3542c.jpg)

### Tables

![18e8511d3be77c678f249e355db155686e90aefc173d9d5c0b02ea91e792cba5.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/18e8511d3be77c678f249e355db155686e90aefc173d9d5c0b02ea91e792cba5.jpg)

![2a1552c9f2e882d536f84b637e44b15f39820c78b03d716c3bb3a05adf362d20.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/2a1552c9f2e882d536f84b637e44b15f39820c78b03d716c3bb3a05adf362d20.jpg)

![486f672a3aaecd7eb539b39ab0fa84302a2f47332136e20e325f75ecb46dfee8.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/486f672a3aaecd7eb539b39ab0fa84302a2f47332136e20e325f75ecb46dfee8.jpg)

![5a83bd7d1dc62cc1ac3465bf01e79e8ae030e936a7df09af9cf89060f811466c.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/5a83bd7d1dc62cc1ac3465bf01e79e8ae030e936a7df09af9cf89060f811466c.jpg)

![69685f1c55cd199135c6baae749f7e33ad948697cc6803c039c4c93d51a36427.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/69685f1c55cd199135c6baae749f7e33ad948697cc6803c039c4c93d51a36427.jpg)

![7571462e933fe7f70ac67a6c8a80c5bd8564c5d53e390ae7368cdaaf464d7629.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/7571462e933fe7f70ac67a6c8a80c5bd8564c5d53e390ae7368cdaaf464d7629.jpg)

![92e5973b6597dc36a2fca366aa9836ee40505922812e9172de6930cc934180ea.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/92e5973b6597dc36a2fca366aa9836ee40505922812e9172de6930cc934180ea.jpg)

![bd34916ad72481a7503c17fc6c5938db7d1f0c6a450713b45029c62da5a55e17.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/bd34916ad72481a7503c17fc6c5938db7d1f0c6a450713b45029c62da5a55e17.jpg)

![dd2291abe40972887c1951e65e8ee27e117654e7c59eb2e47b943f3152860938.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/dd2291abe40972887c1951e65e8ee27e117654e7c59eb2e47b943f3152860938.jpg)

![e7868bef1bda079eed590fad68792802ce276cc0c01fd453318f99c1af95fde2.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/e7868bef1bda079eed590fad68792802ce276cc0c01fd453318f99c1af95fde2.jpg)

![edba7bd08a4d37861c594330500cc604bb9b02a1ecb7146c55ffc974fce916a7.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/edba7bd08a4d37861c594330500cc604bb9b02a1ecb7146c55ffc974fce916a7.jpg)

![f03117383d659d97527263927a8c354dd6eea0eb390c6cba46de4c34cc32dd6d.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/f03117383d659d97527263927a8c354dd6eea0eb390c6cba46de4c34cc32dd6d.jpg)

![f5ba91be8a2419c287f53150703ee68dd90377c6f9b400d4d969470514fc4613.jpg](../nips_results/4614_RetrievalAttention_%20Accelerating%20Long-Context%20LLM%20Inference%20via%20Vector%20Retrieval/tables/f5ba91be8a2419c287f53150703ee68dd90377c6f9b400d4d969470514fc4613.jpg)

## Feedback Guidance of Diffusion Models


### Images

![18892abe4478b142d6e6d861f18c49af57ece50d4587fe4df3de271d80434c1d.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/18892abe4478b142d6e6d861f18c49af57ece50d4587fe4df3de271d80434c1d.jpg)

![1ccf2b6ee3eb1952e1cf4455aa8fbcc6ad76114b6f42c1b5157b9ad91b540a3d.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/1ccf2b6ee3eb1952e1cf4455aa8fbcc6ad76114b6f42c1b5157b9ad91b540a3d.jpg)

![1e925026393e74172bcd9038d455d2ecbee0c14a159e1be086ecbffd09d52230.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/1e925026393e74172bcd9038d455d2ecbee0c14a159e1be086ecbffd09d52230.jpg)

![1ff2037fdb19b5a3e2c73d93edc582e41fb4db584b210843acfbc627cf944a0c.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/1ff2037fdb19b5a3e2c73d93edc582e41fb4db584b210843acfbc627cf944a0c.jpg)

![27de31aa4a9827fa69bf4a98e620708d5dae7c75d95090b657ac3c7745819f08.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/27de31aa4a9827fa69bf4a98e620708d5dae7c75d95090b657ac3c7745819f08.jpg)

![2defebf16d3b88fe70b85c33711e1919d0b2d6bc8e8530759e6f8699007db882.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/2defebf16d3b88fe70b85c33711e1919d0b2d6bc8e8530759e6f8699007db882.jpg)

![55fab7ca6d755b980651d14ef65304213e236135f0c963e618992269aa736854.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/55fab7ca6d755b980651d14ef65304213e236135f0c963e618992269aa736854.jpg)

![5641feccf797d2cdbacf9ede4e754a51c0250bf64fc1eee8906b68437a985b4e.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/5641feccf797d2cdbacf9ede4e754a51c0250bf64fc1eee8906b68437a985b4e.jpg)

![6629d8b50fa67a6b14a91f15f55c0e540488a14d3e26f9a64211b1f2f276e3e2.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/6629d8b50fa67a6b14a91f15f55c0e540488a14d3e26f9a64211b1f2f276e3e2.jpg)

![6d31cc97b3db959d2a6838866a10ec82c825946f24a2d3cea88117446e5ff206.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/6d31cc97b3db959d2a6838866a10ec82c825946f24a2d3cea88117446e5ff206.jpg)

![70962ca345a07a41948aa4d91337de9d02b37be5fdbfabf1a0ee63fcea8eabee.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/70962ca345a07a41948aa4d91337de9d02b37be5fdbfabf1a0ee63fcea8eabee.jpg)

![8284feb9e2abb4c91afafe7e1fe5f571ded68af4956c505f5f4cccbd92bd2fc7.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/8284feb9e2abb4c91afafe7e1fe5f571ded68af4956c505f5f4cccbd92bd2fc7.jpg)

![8d11929b0304cf8bfb77b157c418a2895cd56c7a53e112d9c96194c8c7c4b00d.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/8d11929b0304cf8bfb77b157c418a2895cd56c7a53e112d9c96194c8c7c4b00d.jpg)

![953d82ab2af1126dc45c8f94afe425b9beba85ce28a73dd0e3324692613cf2da.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/953d82ab2af1126dc45c8f94afe425b9beba85ce28a73dd0e3324692613cf2da.jpg)

![a05b6683a6a745c594bc0f75d840a17addd89bb026d663313dfb417217eb7c50.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/a05b6683a6a745c594bc0f75d840a17addd89bb026d663313dfb417217eb7c50.jpg)

![ad741c11b78e833bd5c8f882e501ee00a93031d6989f7837210e499595ed75cc.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/ad741c11b78e833bd5c8f882e501ee00a93031d6989f7837210e499595ed75cc.jpg)

![b1d3171f717ed78790a0e87ee5d3a983e98a20b86ffc2db574b0d1258e21e66d.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/b1d3171f717ed78790a0e87ee5d3a983e98a20b86ffc2db574b0d1258e21e66d.jpg)

![d9dbb7ccd48c7ce51724215cb3a625c7fed77633cf4b682fac62ae41038b38ff.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/d9dbb7ccd48c7ce51724215cb3a625c7fed77633cf4b682fac62ae41038b38ff.jpg)

![dba6cec0a2b1a2dd00deea7bf2d4457c9cadcb42532eb32eb922b7e658fcbe25.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/dba6cec0a2b1a2dd00deea7bf2d4457c9cadcb42532eb32eb922b7e658fcbe25.jpg)

![e59e5d0f64fbd89456f4274e4b5940398824518d226896eed952d35b1ee07f25.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/e59e5d0f64fbd89456f4274e4b5940398824518d226896eed952d35b1ee07f25.jpg)

![f40d0bc956763c1026fd2fc4123ac2d19ce20fff8812ad073b3b86150bf77f2b.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/f40d0bc956763c1026fd2fc4123ac2d19ce20fff8812ad073b3b86150bf77f2b.jpg)

![f62a3ef2a9601e6a7a774c522f10bfba80f014dc5feacdf37cdb6f2624181901.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/f62a3ef2a9601e6a7a774c522f10bfba80f014dc5feacdf37cdb6f2624181901.jpg)

![f886e98da99fde9923fdb9dc73034462d28e21667a69e21f581bd4bfe04f97d2.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/images/f886e98da99fde9923fdb9dc73034462d28e21667a69e21f581bd4bfe04f97d2.jpg)

### Tables

![3f8c09257ede78004429c1333e617d6f79ebbe2abb1d7015ce5dd661d5a3df19.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/tables/3f8c09257ede78004429c1333e617d6f79ebbe2abb1d7015ce5dd661d5a3df19.jpg)

![5d4da410a47fafd80f452510b31a14d7284274f328e56d6639329bbedce6eec0.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/tables/5d4da410a47fafd80f452510b31a14d7284274f328e56d6639329bbedce6eec0.jpg)

![66f6c12e631985590798a15d3ab7e9a882e938755ccf3c3ec29dc94ac050f452.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/tables/66f6c12e631985590798a15d3ab7e9a882e938755ccf3c3ec29dc94ac050f452.jpg)

![8f4a2dc93ff3a4b17cecd82f4d5f3906fa62d2f1a0f257977f910747568dfc72.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/tables/8f4a2dc93ff3a4b17cecd82f4d5f3906fa62d2f1a0f257977f910747568dfc72.jpg)

![9b0cc1d6c6407cc622589b4df47440df4e3c7331d93e605769d08364bf0845cd.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/tables/9b0cc1d6c6407cc622589b4df47440df4e3c7331d93e605769d08364bf0845cd.jpg)

![fdbcb8b3d87f8d89694accd194ea1bdbf1da896f7d0cbc5672d75fac9d288173.jpg](../nips_results/4615_Feedback%20Guidance%20of%20Diffusion%20Models/tables/fdbcb8b3d87f8d89694accd194ea1bdbf1da896f7d0cbc5672d75fac9d288173.jpg)

## Retrv-R1: A Reasoning-Driven MLLM Framework for Universal and Efficient Multimodal Retrieval


### Images

![083e8bf04093ff874ae1897b34c684512309cf47ebfe718e6b106c76b49d8257.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/083e8bf04093ff874ae1897b34c684512309cf47ebfe718e6b106c76b49d8257.jpg)

![08983efd46cdb1ceb10f7d6a4d89b037bbfd64ad6a43eedda121859e320dfd69.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/08983efd46cdb1ceb10f7d6a4d89b037bbfd64ad6a43eedda121859e320dfd69.jpg)

![09a82576bc1525f94392d644599686dda18190a06aa6ed22cff9d31b56f4096f.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/09a82576bc1525f94392d644599686dda18190a06aa6ed22cff9d31b56f4096f.jpg)

![23ee8f1780a7ff4d4dfa4dd210fa35917975e48e51cb45711d61766f1bb98d3d.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/23ee8f1780a7ff4d4dfa4dd210fa35917975e48e51cb45711d61766f1bb98d3d.jpg)

![455552af9dab9b02bf481903fff350f5cbd8c1b698ded262ea9f85a554cc8591.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/455552af9dab9b02bf481903fff350f5cbd8c1b698ded262ea9f85a554cc8591.jpg)

![48fb42561d6241f04e42f00c9a29b80cea76052aa319082e34e5d2516adf36b3.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/48fb42561d6241f04e42f00c9a29b80cea76052aa319082e34e5d2516adf36b3.jpg)

![49ed04c7739399080c693022a7fb376e1ee28f5dfac3a01ee3dac5f873e11050.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/49ed04c7739399080c693022a7fb376e1ee28f5dfac3a01ee3dac5f873e11050.jpg)

![49f96b84442ea04f08df38da29117a7b4cc6a8efd9fc1dc2f94604d55c7599ce.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/49f96b84442ea04f08df38da29117a7b4cc6a8efd9fc1dc2f94604d55c7599ce.jpg)

![4bdd9381e49d8d566dda43103c8a6228443873a39009ddafb8f99a185764d87c.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/4bdd9381e49d8d566dda43103c8a6228443873a39009ddafb8f99a185764d87c.jpg)

![55d741b3dbe622f0f85d3e08c3bd129acaf0312bbb60ee3823d713b2cbfee51c.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/55d741b3dbe622f0f85d3e08c3bd129acaf0312bbb60ee3823d713b2cbfee51c.jpg)

![64c41fb0971131b90a53ded8c9432856a6f29358b9f9dc0060bf1ab8897edc75.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/64c41fb0971131b90a53ded8c9432856a6f29358b9f9dc0060bf1ab8897edc75.jpg)

![671e921f0381fb59c69ebd6217ef76c50ec5320401fd854dd3cdd8b9d41825a4.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/671e921f0381fb59c69ebd6217ef76c50ec5320401fd854dd3cdd8b9d41825a4.jpg)

![8ae41455962d27596378dd553b47de3e3787b303d71db50ec24010b442eba112.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/8ae41455962d27596378dd553b47de3e3787b303d71db50ec24010b442eba112.jpg)

![a57fc88505cbc277c22cdf3b0824b38d7044e7080409b68da2e428ec5743b86a.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/a57fc88505cbc277c22cdf3b0824b38d7044e7080409b68da2e428ec5743b86a.jpg)

![c83e64fa198f0ea896db7aefb94c0a78e6a4869790a04d83cb6c9ddba495509b.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/images/c83e64fa198f0ea896db7aefb94c0a78e6a4869790a04d83cb6c9ddba495509b.jpg)

### Tables

![2ed688d672c000b14c756c0c90ae2f7f23d37d5344fde99aa6b408a8972e51fd.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/tables/2ed688d672c000b14c756c0c90ae2f7f23d37d5344fde99aa6b408a8972e51fd.jpg)

![3b058f0cf3de0729bf69887beefdd7ead7fc709b22f5d28ba921e82acee8c14c.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/tables/3b058f0cf3de0729bf69887beefdd7ead7fc709b22f5d28ba921e82acee8c14c.jpg)

![509920a4dcfd83d23be2dc70639301951a34245fd6566eb9749eb2086c211e05.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/tables/509920a4dcfd83d23be2dc70639301951a34245fd6566eb9749eb2086c211e05.jpg)

![5358f0a7214b72858acdef10f318ab9cfe4774f6a17ebf88456cc256f3fa0c3b.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/tables/5358f0a7214b72858acdef10f318ab9cfe4774f6a17ebf88456cc256f3fa0c3b.jpg)

![581235baae60020a02942664684507cd02419128d8c6be2e77ad21a4c75d6e28.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/tables/581235baae60020a02942664684507cd02419128d8c6be2e77ad21a4c75d6e28.jpg)

![66c28125e2bbecc8ec07fbb746817892cc60a11a62693348aa88939f8e01d525.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/tables/66c28125e2bbecc8ec07fbb746817892cc60a11a62693348aa88939f8e01d525.jpg)

![8c5208cd32b4a48c89068b33485b695d1c8581dd542cfc5b9df3bbb25f676348.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/tables/8c5208cd32b4a48c89068b33485b695d1c8581dd542cfc5b9df3bbb25f676348.jpg)

![a7f9c3c86d599faf7e22273ae2c3d328d792c3dbc87e777b562900b7476d513d.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/tables/a7f9c3c86d599faf7e22273ae2c3d328d792c3dbc87e777b562900b7476d513d.jpg)

![c1eac25fdb497d00aafdaaeeffce25e61cef5fbcb530bf1b0be72218dd799955.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/tables/c1eac25fdb497d00aafdaaeeffce25e61cef5fbcb530bf1b0be72218dd799955.jpg)

![d5c16bd3e61ce8ef5c6546561b9b93cd9876fadf62cdf2a9eccb016342f66809.jpg](../nips_results/4616_Retrv-R1_%20A%20Reasoning-Driven%20MLLM%20Framework%20for%20Universal%20and%20Efficient%20Multimodal%20Retrieval/tables/d5c16bd3e61ce8ef5c6546561b9b93cd9876fadf62cdf2a9eccb016342f66809.jpg)

## LEDiT:  Your Length-Extrapolatable Diffusion Transformer without Positional Encoding


### Images

![11f89d6c94f56f174de06da44971cf57cf9e2b70c3903eaa44b9f7ab84aef948.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/11f89d6c94f56f174de06da44971cf57cf9e2b70c3903eaa44b9f7ab84aef948.jpg)

![14bbbe4a18ba3eda94e1f94ac9505103232c931a20aac224ad0c64b4971cfe57.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/14bbbe4a18ba3eda94e1f94ac9505103232c931a20aac224ad0c64b4971cfe57.jpg)

![17b64232f91f4bb7a92bca6712d1925c1f2e36d3caf9428d41f847293bef6585.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/17b64232f91f4bb7a92bca6712d1925c1f2e36d3caf9428d41f847293bef6585.jpg)

![33f05f5c8b37b48344dd69850ce93fe3f0907ea1e18c85eed94be4678a1f7950.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/33f05f5c8b37b48344dd69850ce93fe3f0907ea1e18c85eed94be4678a1f7950.jpg)

![3ca6e8bbd229270b8382780ef3dd108525064b8103ca2225e8a9a7425dafc28d.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/3ca6e8bbd229270b8382780ef3dd108525064b8103ca2225e8a9a7425dafc28d.jpg)

![4928e3f82089ae086fc0a8c94c8e8ead6c864029aae8b3c1e34a60453691e39a.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/4928e3f82089ae086fc0a8c94c8e8ead6c864029aae8b3c1e34a60453691e39a.jpg)

![592c380c3735ee7b9fd281a1e96d1f2963a75c72aacf06ef382925bb0aa1fe1d.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/592c380c3735ee7b9fd281a1e96d1f2963a75c72aacf06ef382925bb0aa1fe1d.jpg)

![5ed2634ab183b687eafb2e02c2ad1a7f8b28702d9522f820168ec995c9ba050a.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/5ed2634ab183b687eafb2e02c2ad1a7f8b28702d9522f820168ec995c9ba050a.jpg)

![6cd3972b538b262226ac98af7f52e8fb38018001e2dcc67402f96778307c5b08.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/6cd3972b538b262226ac98af7f52e8fb38018001e2dcc67402f96778307c5b08.jpg)

![6fae9a12f9eac2df2373f14a66e4dddcc9dbcd3e0cf084d47f502f83a0da7133.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/6fae9a12f9eac2df2373f14a66e4dddcc9dbcd3e0cf084d47f502f83a0da7133.jpg)

![79ca925477d1033ca60dd1b816b329be6630663c7c1dd9d1d9706ebc582e2dbc.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/79ca925477d1033ca60dd1b816b329be6630663c7c1dd9d1d9706ebc582e2dbc.jpg)

![8fc31aa1353d1b221ff34de3dd397e483e936c80f80a415f0d7dda5688c831d7.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/8fc31aa1353d1b221ff34de3dd397e483e936c80f80a415f0d7dda5688c831d7.jpg)

![97ebe4eaa594c98ac0eda6b36eb487e8913c682ed638bee8f09f498cc0e60910.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/97ebe4eaa594c98ac0eda6b36eb487e8913c682ed638bee8f09f498cc0e60910.jpg)

![9f5b14e4033d53c20085e4423438010818057d0b11ecdd4d56b0ef83b0e98cdc.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/9f5b14e4033d53c20085e4423438010818057d0b11ecdd4d56b0ef83b0e98cdc.jpg)

![b05625023cbb7c50779f6050b6cedbc2d6648ee5580e4d55184e0b93092fc542.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/b05625023cbb7c50779f6050b6cedbc2d6648ee5580e4d55184e0b93092fc542.jpg)

![c5b5f58c8dde9ace5cb527b82a12a046ff31d084ba67d0b53931193d9f7385e8.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/c5b5f58c8dde9ace5cb527b82a12a046ff31d084ba67d0b53931193d9f7385e8.jpg)

![d22fb5d429e11dbc1a04c202214591c83d7cbe72e54dc973b8b1a1160978c681.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/d22fb5d429e11dbc1a04c202214591c83d7cbe72e54dc973b8b1a1160978c681.jpg)

![dd2c96c5de8919b9e492d35a18049523e6b7045c940c66ba0f062ae56b425d9a.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/dd2c96c5de8919b9e492d35a18049523e6b7045c940c66ba0f062ae56b425d9a.jpg)

![e91d869ab13044141361acca95dc9da1984b45c618942f04bd9f6f9f2e45ff26.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/e91d869ab13044141361acca95dc9da1984b45c618942f04bd9f6f9f2e45ff26.jpg)

![ef9f846aa35d08d5624cdf204b8091b89ad5c91a9a0c8669704b54de74753b21.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/ef9f846aa35d08d5624cdf204b8091b89ad5c91a9a0c8669704b54de74753b21.jpg)

![f9f992b2df9f024f1143b290b7da7f569db9874c942fb8a19182ea3e6fd8ba0b.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/f9f992b2df9f024f1143b290b7da7f569db9874c942fb8a19182ea3e6fd8ba0b.jpg)

![fd0afae9ee3be8b0f5219e6076fc0f5d2d8f3a01555289767335e9af7c1c84a1.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/fd0afae9ee3be8b0f5219e6076fc0f5d2d8f3a01555289767335e9af7c1c84a1.jpg)

![fdc0d862e08ce432a263df989a886bfeb7fc618c0132317eb3711930e76b0c1c.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/images/fdc0d862e08ce432a263df989a886bfeb7fc618c0132317eb3711930e76b0c1c.jpg)

### Tables

![0a8eecd36b2b61271c9cc2b57b34a6735a396d417ee1e19b03f1934ae7e234ca.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/0a8eecd36b2b61271c9cc2b57b34a6735a396d417ee1e19b03f1934ae7e234ca.jpg)

![17c5dca653942bf571a10a32b2e60ff9c28b0a7ad92ca44f37db1df171f4db03.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/17c5dca653942bf571a10a32b2e60ff9c28b0a7ad92ca44f37db1df171f4db03.jpg)

![1d1fd9f233bc9417b25f15e6fd9c1a210c59790d66e22ec172f74708a7ec585b.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/1d1fd9f233bc9417b25f15e6fd9c1a210c59790d66e22ec172f74708a7ec585b.jpg)

![2408e64996178db7f401296d06c10e2b0871af06775317f50cdfa63454b815ab.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/2408e64996178db7f401296d06c10e2b0871af06775317f50cdfa63454b815ab.jpg)

![3805866514bfd3170aa8fd890c258098bb09a921f4a7d6199ede4c5dea1c07bb.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/3805866514bfd3170aa8fd890c258098bb09a921f4a7d6199ede4c5dea1c07bb.jpg)

![3b94d3db4bc88f1fe78f4796e99a81466187e013361b6f7f212cf5c28a43c231.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/3b94d3db4bc88f1fe78f4796e99a81466187e013361b6f7f212cf5c28a43c231.jpg)

![4cd184fed16d4f948a0eeff92c3efbce9f71c2742bc38e0bcf28fe746ec68999.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/4cd184fed16d4f948a0eeff92c3efbce9f71c2742bc38e0bcf28fe746ec68999.jpg)

![5a3a9c9d06bbc07e279e51d4bdf4589f6745d7012c178d11d00f640783467fad.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/5a3a9c9d06bbc07e279e51d4bdf4589f6745d7012c178d11d00f640783467fad.jpg)

![5b43aa0d2708bb4b7c68d06f24ca0295a0ab465fe805063296b8b805d5173d85.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/5b43aa0d2708bb4b7c68d06f24ca0295a0ab465fe805063296b8b805d5173d85.jpg)

![7475aaaf35efa947bb80a98e921af9a78bdfb13248dc8973648861f2f7c44b24.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/7475aaaf35efa947bb80a98e921af9a78bdfb13248dc8973648861f2f7c44b24.jpg)

![76f42cd2cba9dbc3e259cb97cc7149b91ec4273c8d5b0fcb6584bd4561d800ea.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/76f42cd2cba9dbc3e259cb97cc7149b91ec4273c8d5b0fcb6584bd4561d800ea.jpg)

![a2dde676437583f374b0fa3d85d1f708b68792f0476072706277b658662b4d2d.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/a2dde676437583f374b0fa3d85d1f708b68792f0476072706277b658662b4d2d.jpg)

![b288b6a36875f3ed61d30c6b62d766a3b73ebdd887311e9e1471cf7b75db6341.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/b288b6a36875f3ed61d30c6b62d766a3b73ebdd887311e9e1471cf7b75db6341.jpg)

![b302e99cf207f2790999ba5b919a0ecf3a151aa8380eb9d19f0eb18de144a7b5.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/b302e99cf207f2790999ba5b919a0ecf3a151aa8380eb9d19f0eb18de144a7b5.jpg)

![b378ec670a92a9ef47d53c5780e59f1b9defd1a95dff9f5c0ebaae63d9668ec5.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/b378ec670a92a9ef47d53c5780e59f1b9defd1a95dff9f5c0ebaae63d9668ec5.jpg)

![b4975163560796050393c24fbffb7853e1c94507aa712ca648b49b6bcc16bd4e.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/b4975163560796050393c24fbffb7853e1c94507aa712ca648b49b6bcc16bd4e.jpg)

![cdbf6b8c2a42af64b350a1c46d7d7886b8f711f59a66aa6412e9425964902128.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/cdbf6b8c2a42af64b350a1c46d7d7886b8f711f59a66aa6412e9425964902128.jpg)

![d75584c29ecdcc1a3b130faa7ba19dcbdce208efcd97542fd853be47422edbaa.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/d75584c29ecdcc1a3b130faa7ba19dcbdce208efcd97542fd853be47422edbaa.jpg)

![e55fb53586c0af0c5e53ab04f387d7a64dc33d736ce5a6734690f5e55e2e04b2.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/e55fb53586c0af0c5e53ab04f387d7a64dc33d736ce5a6734690f5e55e2e04b2.jpg)

![f188fdb03230c49576f50bb5b95565831ec629267ecdfd21e1d8bab3e2464e1a.jpg](../nips_results/4617_LEDiT_%20%20Your%20Length-Extrapolatable%20Diffusion%20Transformer%20without%20Positional%20Encoding/tables/f188fdb03230c49576f50bb5b95565831ec629267ecdfd21e1d8bab3e2464e1a.jpg)

## Learning from Disjoint Views: A Contrastive Prototype Matching Network for Fully Incomplete Multi-View Clustering


### Images

![7a82979819c9cee910bb3232d1e33e5ff58cf9258c03061b10c22e8db5c1fa10.jpg](../nips_results/4618_Learning%20from%20Disjoint%20Views_%20A%20Contrastive%20Prototype%20Matching%20Network%20for%20Fully%20Incomplete%20Multi-Vi/images/7a82979819c9cee910bb3232d1e33e5ff58cf9258c03061b10c22e8db5c1fa10.jpg)

![87ad807516ab329e08122e1f14f858ae75ce96db652627f4efd3bfaaa116f800.jpg](../nips_results/4618_Learning%20from%20Disjoint%20Views_%20A%20Contrastive%20Prototype%20Matching%20Network%20for%20Fully%20Incomplete%20Multi-Vi/images/87ad807516ab329e08122e1f14f858ae75ce96db652627f4efd3bfaaa116f800.jpg)

![cb3a5e175f4f8e1650ad20fff98ab6f424a54834aab9adaff683779aeb126f4a.jpg](../nips_results/4618_Learning%20from%20Disjoint%20Views_%20A%20Contrastive%20Prototype%20Matching%20Network%20for%20Fully%20Incomplete%20Multi-Vi/images/cb3a5e175f4f8e1650ad20fff98ab6f424a54834aab9adaff683779aeb126f4a.jpg)

### Tables

![1366fd53a4add13d26f69669fb033f1c876359e4440684af7ca3e3f2692a8696.jpg](../nips_results/4618_Learning%20from%20Disjoint%20Views_%20A%20Contrastive%20Prototype%20Matching%20Network%20for%20Fully%20Incomplete%20Multi-Vi/tables/1366fd53a4add13d26f69669fb033f1c876359e4440684af7ca3e3f2692a8696.jpg)

![677771a69da0fe9b2ba7cc513d7384269cd9850aee99768456435d4c3950a0f5.jpg](../nips_results/4618_Learning%20from%20Disjoint%20Views_%20A%20Contrastive%20Prototype%20Matching%20Network%20for%20Fully%20Incomplete%20Multi-Vi/tables/677771a69da0fe9b2ba7cc513d7384269cd9850aee99768456435d4c3950a0f5.jpg)

![8dd17dcd9266c561878f912de0539d6723c678d2c2cc78b19f43484c435cc1f4.jpg](../nips_results/4618_Learning%20from%20Disjoint%20Views_%20A%20Contrastive%20Prototype%20Matching%20Network%20for%20Fully%20Incomplete%20Multi-Vi/tables/8dd17dcd9266c561878f912de0539d6723c678d2c2cc78b19f43484c435cc1f4.jpg)

![e5d9ada4677f65c07ccb3bf6465e9f6ea3ed04a271370513356732474187c9d0.jpg](../nips_results/4618_Learning%20from%20Disjoint%20Views_%20A%20Contrastive%20Prototype%20Matching%20Network%20for%20Fully%20Incomplete%20Multi-Vi/tables/e5d9ada4677f65c07ccb3bf6465e9f6ea3ed04a271370513356732474187c9d0.jpg)

## Pool Me Wisely: On the Effect of Pooling in Transformer-Based Models


### Images

![09d4f0c9f5b491fabdebccba3d2770afbcbad8e4145129969e916cdb9535b75a.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/images/09d4f0c9f5b491fabdebccba3d2770afbcbad8e4145129969e916cdb9535b75a.jpg)

![2a9d89c2675e08a7c78b12ee07534bfadcae0cdc9907c52ef5a59137ee636e56.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/images/2a9d89c2675e08a7c78b12ee07534bfadcae0cdc9907c52ef5a59137ee636e56.jpg)

![57eeb2ebb74e17df7d9dc61f94008f2db3b71ec3adbb2d73e43306ce5e852ef1.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/images/57eeb2ebb74e17df7d9dc61f94008f2db3b71ec3adbb2d73e43306ce5e852ef1.jpg)

![5a09a968cc24e30d707667f99ebb3187a069b982f11cbd9c0e17f49e5c941e8a.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/images/5a09a968cc24e30d707667f99ebb3187a069b982f11cbd9c0e17f49e5c941e8a.jpg)

![c1e0f4a3e46545b837f8f11ad5177034504693cf552dba55281e6c3500aececd.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/images/c1e0f4a3e46545b837f8f11ad5177034504693cf552dba55281e6c3500aececd.jpg)

![ca2e596cdbc74e3194bdf5ba8b880ae35f25593fe91df234410e27f51b42238f.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/images/ca2e596cdbc74e3194bdf5ba8b880ae35f25593fe91df234410e27f51b42238f.jpg)

![f49aa236b2f5d3df7520b3c12511e47c9fda28e77c61fb87565c625fa2109e1b.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/images/f49aa236b2f5d3df7520b3c12511e47c9fda28e77c61fb87565c625fa2109e1b.jpg)

![f7d9f0e818043a50764015946031c4ee218007b5190a1355690d829e0591a1c7.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/images/f7d9f0e818043a50764015946031c4ee218007b5190a1355690d829e0591a1c7.jpg)

### Tables

![24aeedf0351655660ad80516f837ed235b5964a1d3fe574287dd79b1009b552b.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/tables/24aeedf0351655660ad80516f837ed235b5964a1d3fe574287dd79b1009b552b.jpg)

![310ac0845de2ad6b8e5734b80b8624c2d65c3aa417ef5af4ae31d3e7fe7d64d6.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/tables/310ac0845de2ad6b8e5734b80b8624c2d65c3aa417ef5af4ae31d3e7fe7d64d6.jpg)

![327c55e49e339faeed241ce35c044c96b0bd0b5714e5a56004247ce73f5717cd.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/tables/327c55e49e339faeed241ce35c044c96b0bd0b5714e5a56004247ce73f5717cd.jpg)

![3bfdbf6f65debee1e1a93a87b58a782d1ba03519f69bc4c37a67d12880dcbc5a.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/tables/3bfdbf6f65debee1e1a93a87b58a782d1ba03519f69bc4c37a67d12880dcbc5a.jpg)

![69fc38e40a66d7f881b03e940bae7c7466e21d6e598ba5de50e0c92930bb6bda.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/tables/69fc38e40a66d7f881b03e940bae7c7466e21d6e598ba5de50e0c92930bb6bda.jpg)

![9b2325bb95c3b721c4874032fbcae7a04c89e7a7af7aa445016612a83e53c2b4.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/tables/9b2325bb95c3b721c4874032fbcae7a04c89e7a7af7aa445016612a83e53c2b4.jpg)

![c257600281bc4a0777470d1c947169c5ed4aee66d74ee18984a4f734c5bc7d6a.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/tables/c257600281bc4a0777470d1c947169c5ed4aee66d74ee18984a4f734c5bc7d6a.jpg)

![cd87f1f697405bed45cdac633e3003c5b7da59d0392a822ede91f1d3d1303e19.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/tables/cd87f1f697405bed45cdac633e3003c5b7da59d0392a822ede91f1d3d1303e19.jpg)

![cde322dcec337fb1258236b01c5e50c4ef4e4567678c6c8fd0281c0fbccff766.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/tables/cde322dcec337fb1258236b01c5e50c4ef4e4567678c6c8fd0281c0fbccff766.jpg)

![de91c44a7123c5397ae313f26625d6dd41d16197496f1e1d00ea953ba5a2fd56.jpg](../nips_results/4619_Pool%20Me%20Wisely_%20On%20the%20Effect%20of%20Pooling%20in%20Transformer-Based%20Models/tables/de91c44a7123c5397ae313f26625d6dd41d16197496f1e1d00ea953ba5a2fd56.jpg)

## INST-IT: Boosting Instance Understanding via Explicit Visual Prompt Instruction Tuning


### Images

![2d23472ec4e12854ef010789fa178fec5abfe8db98ef68a6311eab5555d056d2.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/images/2d23472ec4e12854ef010789fa178fec5abfe8db98ef68a6311eab5555d056d2.jpg)

![2f4dbd14b41ed26db6349bcfd310b27ae0f10e6b89da866ab6b0fd0298d1d0e5.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/images/2f4dbd14b41ed26db6349bcfd310b27ae0f10e6b89da866ab6b0fd0298d1d0e5.jpg)

![33adc46279be4400cc1debe28b6864d9e8b132a08a7620f9ca227b31604d0b7a.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/images/33adc46279be4400cc1debe28b6864d9e8b132a08a7620f9ca227b31604d0b7a.jpg)

![34726fd82546e381c733d5b23df8a0e90e0a58eda19d9d9b813c3ecc38824e48.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/images/34726fd82546e381c733d5b23df8a0e90e0a58eda19d9d9b813c3ecc38824e48.jpg)

![59a0c053047def1ed38de96753add14db79423bc75701c86d3fe5b85d19d828c.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/images/59a0c053047def1ed38de96753add14db79423bc75701c86d3fe5b85d19d828c.jpg)

![651130b0cab2c46e609811eca955e98e6b851563313a58c1f944b5ea1eaac998.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/images/651130b0cab2c46e609811eca955e98e6b851563313a58c1f944b5ea1eaac998.jpg)

![72d9e9c5c9662c3f8675436708ba31980c8c345788d5180665ff31e103e62af6.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/images/72d9e9c5c9662c3f8675436708ba31980c8c345788d5180665ff31e103e62af6.jpg)

### Tables

![006b1e068b8606317989c5fae073295944b0fa2be4548145459dca4ff882deb4.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/006b1e068b8606317989c5fae073295944b0fa2be4548145459dca4ff882deb4.jpg)

![155b95684fba193a24ee8e38386089c53e6100ee8dfd45499fe00c064c03b65c.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/155b95684fba193a24ee8e38386089c53e6100ee8dfd45499fe00c064c03b65c.jpg)

![1674006cdc041719c2947d36ac058e5f8f5ad1cd945591858e2f887077389816.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/1674006cdc041719c2947d36ac058e5f8f5ad1cd945591858e2f887077389816.jpg)

![184ac2c685425c805bc6f0f8850119353cac5c751efdb84e76553f7eaef0e610.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/184ac2c685425c805bc6f0f8850119353cac5c751efdb84e76553f7eaef0e610.jpg)

![2fce81dd0a0765536ae62dad4d5a2a87b848759e1dda5fbf9309876c2588ae3e.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/2fce81dd0a0765536ae62dad4d5a2a87b848759e1dda5fbf9309876c2588ae3e.jpg)

![467713fd91527c01be491006be3e611399d18f4f5ce835cd520e3d41049ba612.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/467713fd91527c01be491006be3e611399d18f4f5ce835cd520e3d41049ba612.jpg)

![47d6cacdff9ac932b5cb78df539a85d80eb999b2c27dba1bdc8223fb81a2233e.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/47d6cacdff9ac932b5cb78df539a85d80eb999b2c27dba1bdc8223fb81a2233e.jpg)

![5baa0591d50b758a3987bfe5d680f994113fbaf25fc60f0953e9cc7303243131.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/5baa0591d50b758a3987bfe5d680f994113fbaf25fc60f0953e9cc7303243131.jpg)

![650b8b84225e45de2e72cf99c333b2da96f2751e93a6933fef759e1968d8d5eb.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/650b8b84225e45de2e72cf99c333b2da96f2751e93a6933fef759e1968d8d5eb.jpg)

![b199c0c35958a6ef2cfc0aa12ffe6b2439616c10e92c4303c7d0dd46e075e815.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/b199c0c35958a6ef2cfc0aa12ffe6b2439616c10e92c4303c7d0dd46e075e815.jpg)

![cc668a1c7f9dcc43734e9657795a053c0ce3e1f52590a6fb3cf7a1c1a32c17f6.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/cc668a1c7f9dcc43734e9657795a053c0ce3e1f52590a6fb3cf7a1c1a32c17f6.jpg)

![d026dc18e0f15e1582f08dfbd27d7897b59fa885fd156c7f8629367b877a1eba.jpg](../nips_results/4620_INST-IT_%20Boosting%20Instance%20Understanding%20via%20Explicit%20Visual%20Prompt%20Instruction%20Tuning/tables/d026dc18e0f15e1582f08dfbd27d7897b59fa885fd156c7f8629367b877a1eba.jpg)

## RoPECraft: Training-Free Motion Transfer with Trajectory-Guided RoPE Optimization on Diffusion Transformers


### Images

![10ad828a520a691d145374d8ace35029edfdd7eff186b2802e2f8501a9ac02c2.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/10ad828a520a691d145374d8ace35029edfdd7eff186b2802e2f8501a9ac02c2.jpg)

![1261832ccafbee27b3c6cae7044d80dc02c62d41ab68960864c61db4deec3248.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/1261832ccafbee27b3c6cae7044d80dc02c62d41ab68960864c61db4deec3248.jpg)

![1336a08f08266dcc698dfeda75194db733ce195651a2ff42a20987eab3bf447f.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/1336a08f08266dcc698dfeda75194db733ce195651a2ff42a20987eab3bf447f.jpg)

![1523a13cfc54b40dfa25cd5880f02eba6c755ffad6378baca0ec6d689c996c82.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/1523a13cfc54b40dfa25cd5880f02eba6c755ffad6378baca0ec6d689c996c82.jpg)

![161dfbb1ed0f0026a52d01efc7755ad79bbfe0be1302e3c264adfeb3271381f8.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/161dfbb1ed0f0026a52d01efc7755ad79bbfe0be1302e3c264adfeb3271381f8.jpg)

![1ca615cca513531acab0af50f2b28dcbb64b6c4a21fd2122fbbfe23942faacc7.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/1ca615cca513531acab0af50f2b28dcbb64b6c4a21fd2122fbbfe23942faacc7.jpg)

![2d5cd5219bdc61bd12c40c204339122daece729f84efbe6793bfcf3fd76bca0c.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/2d5cd5219bdc61bd12c40c204339122daece729f84efbe6793bfcf3fd76bca0c.jpg)

![3a96712327dc1c1ce6fd04d7fb8828864af1c00cf99c73b2b361a875ec142ef7.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/3a96712327dc1c1ce6fd04d7fb8828864af1c00cf99c73b2b361a875ec142ef7.jpg)

![3aad504cdf6b1fd0c788d56b69587a7ba0866d61c2327b868cd2e5ba5f0ddfb8.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/3aad504cdf6b1fd0c788d56b69587a7ba0866d61c2327b868cd2e5ba5f0ddfb8.jpg)

![60f16c6d32342341dd4620a23d6f512c02a84f7e3852a6956cb42e0e15a83f52.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/60f16c6d32342341dd4620a23d6f512c02a84f7e3852a6956cb42e0e15a83f52.jpg)

![65b38489048556e25a63b3b987ed3d39b80cb0a5db2951b9e65392776b07ef81.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/65b38489048556e25a63b3b987ed3d39b80cb0a5db2951b9e65392776b07ef81.jpg)

![6ff740f432f4d22147cc25c6630d6e9c6e62a1a81622e903e91da362691ce8cd.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/6ff740f432f4d22147cc25c6630d6e9c6e62a1a81622e903e91da362691ce8cd.jpg)

![78733e5a2c3464233fa9fa7eced71b44cf6ecdd53aa3f23b266e2ad07002a9d2.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/78733e5a2c3464233fa9fa7eced71b44cf6ecdd53aa3f23b266e2ad07002a9d2.jpg)

![839a395586393fe4724b45634187910ccb37f04ad6d329335431d9072747af09.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/839a395586393fe4724b45634187910ccb37f04ad6d329335431d9072747af09.jpg)

![87ea66e11a6f9d87d9404273a795ca4cf9f4e006ebce02507c8d7b621c5918be.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/87ea66e11a6f9d87d9404273a795ca4cf9f4e006ebce02507c8d7b621c5918be.jpg)

![8e3053e00d887ac50eceaddaac27e0c8e21d51fe92b8730644008c0031cce781.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/8e3053e00d887ac50eceaddaac27e0c8e21d51fe92b8730644008c0031cce781.jpg)

![91d627ea88afeae17e6a6a9b49b1ff914302dfa84a8168b84cacd32b443ceca6.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/91d627ea88afeae17e6a6a9b49b1ff914302dfa84a8168b84cacd32b443ceca6.jpg)

![941cf64e7e46f23ab9471f17b72e65b9b273d9ba1afb01c47556c31e1f342f7a.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/941cf64e7e46f23ab9471f17b72e65b9b273d9ba1afb01c47556c31e1f342f7a.jpg)

![9c6ec34ffc6a4a0b30f56e0f0e82549a44e590939804413b47f078af8a229afa.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/9c6ec34ffc6a4a0b30f56e0f0e82549a44e590939804413b47f078af8a229afa.jpg)

![a0b989f5251e3799d20c00ce069cc9adda6f33adc887ab5a8b6ab0ed2d7c1c89.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/a0b989f5251e3799d20c00ce069cc9adda6f33adc887ab5a8b6ab0ed2d7c1c89.jpg)

![a865cb7eda9ee048d232d1d36c60c7ef4bdcc7d93ffcfeaf6089926f80830bf5.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/a865cb7eda9ee048d232d1d36c60c7ef4bdcc7d93ffcfeaf6089926f80830bf5.jpg)

![b224f76b631789ccb9b24d9b366077e147853a3e844e88d48c6357ffeea3d1d1.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/b224f76b631789ccb9b24d9b366077e147853a3e844e88d48c6357ffeea3d1d1.jpg)

![bc0697118470f2ff746228855a93e7308930f7f616222d7911cc7ca7eb23660c.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/bc0697118470f2ff746228855a93e7308930f7f616222d7911cc7ca7eb23660c.jpg)

![c4bde1f96446b09eb8dbdc8903d8ba2c20ea05a94442bee4c5a73bfe1fca45d5.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/c4bde1f96446b09eb8dbdc8903d8ba2c20ea05a94442bee4c5a73bfe1fca45d5.jpg)

![e0ba925bcf6dc8c335f8ac225775b4836ee11cf6caad58612e08eae8c07c9f42.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/e0ba925bcf6dc8c335f8ac225775b4836ee11cf6caad58612e08eae8c07c9f42.jpg)

![e99d7ef85294c13b9bec95613d64f68e8375f3f99c7265331136bc2a9680c6b7.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/e99d7ef85294c13b9bec95613d64f68e8375f3f99c7265331136bc2a9680c6b7.jpg)

![ee05e70379b6ad9202b4109994f5ef340b45e03bea7c627f6aa9e90512f2fd97.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/ee05e70379b6ad9202b4109994f5ef340b45e03bea7c627f6aa9e90512f2fd97.jpg)

![f86c0e25afe4778a9996d331d5fb357f28b14c5f580fbe6ee383f5c8475418b6.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/f86c0e25afe4778a9996d331d5fb357f28b14c5f580fbe6ee383f5c8475418b6.jpg)

![fb1a930a2e32856483f806954f51d3a30c1fe5949bf09b7650c6bbe228b2e505.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/images/fb1a930a2e32856483f806954f51d3a30c1fe5949bf09b7650c6bbe228b2e505.jpg)

### Tables

![048ca95c2c8aaaaaa48df086d4ca22d04623a2873cd53bcb1a074d34bc1f1d7f.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/tables/048ca95c2c8aaaaaa48df086d4ca22d04623a2873cd53bcb1a074d34bc1f1d7f.jpg)

![37fe047c6ffcdad766cdc0c154acbe47d718a4889e58a63e8de37a100fdd82b6.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/tables/37fe047c6ffcdad766cdc0c154acbe47d718a4889e58a63e8de37a100fdd82b6.jpg)

![5586ce13b4fbf9233442982a4f2592020f6604ecfb2f1d5ac52f98defcc17cdf.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/tables/5586ce13b4fbf9233442982a4f2592020f6604ecfb2f1d5ac52f98defcc17cdf.jpg)

![623dd6789252ea88c3f6340d4e87fc0b6f244b61eabdb5f1f2a2600745ddda06.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/tables/623dd6789252ea88c3f6340d4e87fc0b6f244b61eabdb5f1f2a2600745ddda06.jpg)

![671ba95a61c1f4e562fcb6844aeb5d05e50c8b9f36e0bff94ac71910be2f91c3.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/tables/671ba95a61c1f4e562fcb6844aeb5d05e50c8b9f36e0bff94ac71910be2f91c3.jpg)

![71926a67af50a09d25b3a5c7aea87dd1cd5c56b492f1462bdb8b5ac4c5991afe.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/tables/71926a67af50a09d25b3a5c7aea87dd1cd5c56b492f1462bdb8b5ac4c5991afe.jpg)

![80b9956b2ec00d4e7a726aa527d23b5c9b1fcc1b2c879be8ba961fb874cfa86c.jpg](../nips_results/4621_RoPECraft_%20Training-Free%20Motion%20Transfer%20with%20Trajectory-Guided%20RoPE%20Optimization%20on%20Diffusion%20Trans/tables/80b9956b2ec00d4e7a726aa527d23b5c9b1fcc1b2c879be8ba961fb874cfa86c.jpg)

## Iterative Foundation Model Fine-Tuning on Multiple Rewards


### Images

![0223c1281bb1e5a8c1bd0ee4023a3b820e0ac63a589a6d0a502c73b617e0cf5c.jpg](../nips_results/4622_Iterative%20Foundation%20Model%20Fine-Tuning%20on%20Multiple%20Rewards/images/0223c1281bb1e5a8c1bd0ee4023a3b820e0ac63a589a6d0a502c73b617e0cf5c.jpg)

![d0e6e27fa83ae181f612669bab1a76aa47537b296e7c6c8893f9175ceff16269.jpg](../nips_results/4622_Iterative%20Foundation%20Model%20Fine-Tuning%20on%20Multiple%20Rewards/images/d0e6e27fa83ae181f612669bab1a76aa47537b296e7c6c8893f9175ceff16269.jpg)

![f76647efe47bf45d6f0d5a896900208004a940f76d7fe9630b4bbf09ef2effd7.jpg](../nips_results/4622_Iterative%20Foundation%20Model%20Fine-Tuning%20on%20Multiple%20Rewards/images/f76647efe47bf45d6f0d5a896900208004a940f76d7fe9630b4bbf09ef2effd7.jpg)

### Tables

![0ad25fa3570c645c638eb021d9dfa53fa1be2bd78dbb8d562d6b83b00ae93e8f.jpg](../nips_results/4622_Iterative%20Foundation%20Model%20Fine-Tuning%20on%20Multiple%20Rewards/tables/0ad25fa3570c645c638eb021d9dfa53fa1be2bd78dbb8d562d6b83b00ae93e8f.jpg)

![377f419a1572fd14a13ea32f2e29af8ff5b8af9ae83e0ac80789aec2461c49d2.jpg](../nips_results/4622_Iterative%20Foundation%20Model%20Fine-Tuning%20on%20Multiple%20Rewards/tables/377f419a1572fd14a13ea32f2e29af8ff5b8af9ae83e0ac80789aec2461c49d2.jpg)

![4050638b8a20a0cef39ae6596f8571435db26314d927ed413f7358b38de1ee66.jpg](../nips_results/4622_Iterative%20Foundation%20Model%20Fine-Tuning%20on%20Multiple%20Rewards/tables/4050638b8a20a0cef39ae6596f8571435db26314d927ed413f7358b38de1ee66.jpg)

![5fb64eafbeaa36b4be75f5a1657651f39aa157a0d3e7d45c11a0e74586aaf1b6.jpg](../nips_results/4622_Iterative%20Foundation%20Model%20Fine-Tuning%20on%20Multiple%20Rewards/tables/5fb64eafbeaa36b4be75f5a1657651f39aa157a0d3e7d45c11a0e74586aaf1b6.jpg)

![7619f6e25f26c28bbacca9006f58dda16e707499dd23b27170636b51a158290f.jpg](../nips_results/4622_Iterative%20Foundation%20Model%20Fine-Tuning%20on%20Multiple%20Rewards/tables/7619f6e25f26c28bbacca9006f58dda16e707499dd23b27170636b51a158290f.jpg)

![9d972b02692c98ac8bdbe2033a33855fde9f949c27f404424e9f53b3a4ae2be0.jpg](../nips_results/4622_Iterative%20Foundation%20Model%20Fine-Tuning%20on%20Multiple%20Rewards/tables/9d972b02692c98ac8bdbe2033a33855fde9f949c27f404424e9f53b3a4ae2be0.jpg)

![ca5ed844c2558142b4a42777bd6d609110fc2f3b7447a8326e3e79c1b460ba0c.jpg](../nips_results/4622_Iterative%20Foundation%20Model%20Fine-Tuning%20on%20Multiple%20Rewards/tables/ca5ed844c2558142b4a42777bd6d609110fc2f3b7447a8326e3e79c1b460ba0c.jpg)

## TF-MAS: Training-free Mamba2 Architecture Search


### Images

![52add128d8dd52a8af473fb5d255a4b23f71f6843c72b96911aea0420c798265.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/images/52add128d8dd52a8af473fb5d255a4b23f71f6843c72b96911aea0420c798265.jpg)

![781805ad88e5636f6a80f01a36c2e83cf4c0ba05b338c2082c159408795830fa.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/images/781805ad88e5636f6a80f01a36c2e83cf4c0ba05b338c2082c159408795830fa.jpg)

![db233647d93e9416ce041665e4462544dff0ca189d1b408be5f7923cdd1c71bb.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/images/db233647d93e9416ce041665e4462544dff0ca189d1b408be5f7923cdd1c71bb.jpg)

![e693f962eca5373e215a41cabd63709724dee3bc681f37d1496a82cf5e11a512.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/images/e693f962eca5373e215a41cabd63709724dee3bc681f37d1496a82cf5e11a512.jpg)

### Tables

![126e5de09309de3d7911ae2cfdac8af5511741f1972bc04f1b653d3983c56cba.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/126e5de09309de3d7911ae2cfdac8af5511741f1972bc04f1b653d3983c56cba.jpg)

![3078ea201bf06bb1546e6e2b5ea01d5b8829d805e091bd1200032b8a4a2c7909.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/3078ea201bf06bb1546e6e2b5ea01d5b8829d805e091bd1200032b8a4a2c7909.jpg)

![3f9e8d91abbad3913e5374fc6c6fc7737fdfa8a9651e23836f1adaf91bcfd524.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/3f9e8d91abbad3913e5374fc6c6fc7737fdfa8a9651e23836f1adaf91bcfd524.jpg)

![419965eff472bf4f3da57e26f4eefbaa8e447f1d2de332504188e9e614b33234.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/419965eff472bf4f3da57e26f4eefbaa8e447f1d2de332504188e9e614b33234.jpg)

![456a209376b4c5209c30a2375e5a03da9d1e1c4a82908f3b164bb21dde6a0296.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/456a209376b4c5209c30a2375e5a03da9d1e1c4a82908f3b164bb21dde6a0296.jpg)

![45b6e10a52d52419af999f8973af2ba9a35617824b5797223747025d5f5a8e4a.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/45b6e10a52d52419af999f8973af2ba9a35617824b5797223747025d5f5a8e4a.jpg)

![71606e5371b5c2e8b6f6f8f73c6356d9d27607a47d03fb6aa2b10d9c395956df.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/71606e5371b5c2e8b6f6f8f73c6356d9d27607a47d03fb6aa2b10d9c395956df.jpg)

![90f0ac2dbe8b8a03014a0e8c75f45cdb025344da4d54056340043476c66d29e0.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/90f0ac2dbe8b8a03014a0e8c75f45cdb025344da4d54056340043476c66d29e0.jpg)

![938b86256da5884f9bde85027e4fde871858b70df02ae47c1d8463592d8c7884.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/938b86256da5884f9bde85027e4fde871858b70df02ae47c1d8463592d8c7884.jpg)

![a5c67f5f930e6781b0ae51d3452491160e19372a2cadbaa77ec48f8d7bd5822d.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/a5c67f5f930e6781b0ae51d3452491160e19372a2cadbaa77ec48f8d7bd5822d.jpg)

![aa1a2835a42d20a645b77274aa9fcf1b3668edad155dc4798bbb93fb159bca41.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/aa1a2835a42d20a645b77274aa9fcf1b3668edad155dc4798bbb93fb159bca41.jpg)

![b623cb0ad84b7abbd5f2be6ed0d87d33698de53ec14239770ce413a6c200f25b.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/b623cb0ad84b7abbd5f2be6ed0d87d33698de53ec14239770ce413a6c200f25b.jpg)

![c8bc880056ec71593fca4b6eec4393030948b18bb97bfe9f2e06d6a697d982a0.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/c8bc880056ec71593fca4b6eec4393030948b18bb97bfe9f2e06d6a697d982a0.jpg)

![cb7dd6a07929a252b7d9a759571262533b7e7d14433b3f4365eb4e3f13f7a18b.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/cb7dd6a07929a252b7d9a759571262533b7e7d14433b3f4365eb4e3f13f7a18b.jpg)

![eb8802aadf7764c0885df6f68c18b70230c0e17c87a3eb2473fa675778b33593.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/eb8802aadf7764c0885df6f68c18b70230c0e17c87a3eb2473fa675778b33593.jpg)

![ec0d04324798139f1a419f626111ef25decf04ca39a132351861dcaa885a1510.jpg](../nips_results/4623_TF-MAS_%20Training-free%20Mamba2%20Architecture%20Search/tables/ec0d04324798139f1a419f626111ef25decf04ca39a132351861dcaa885a1510.jpg)

## CryptoMoE: Privacy-Preserving and Scalable Mixture of Experts Inference via Balanced Expert Routing


### Images

![01d9bce240ed25727f2296a54cb3902e69720e092fd7aba6e3c9440ea0ddac25.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/01d9bce240ed25727f2296a54cb3902e69720e092fd7aba6e3c9440ea0ddac25.jpg)

![1f7441ead835d382627293cce80b57c05709e7c8f42e3da98f55f8e1069f5b3d.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/1f7441ead835d382627293cce80b57c05709e7c8f42e3da98f55f8e1069f5b3d.jpg)

![269be3def72615d4ce2ae2d207ad2a460626a26f5f92d0b7a2fa3fbc178b7e94.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/269be3def72615d4ce2ae2d207ad2a460626a26f5f92d0b7a2fa3fbc178b7e94.jpg)

![31fe0c3df05e95651e8d0b154018c2e2644e7ad04dc709a0ef8b6f86501f2eb9.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/31fe0c3df05e95651e8d0b154018c2e2644e7ad04dc709a0ef8b6f86501f2eb9.jpg)

![41d6088afe837a523abcacc61f0a22a440b051acea42314cf106dbd224bdb940.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/41d6088afe837a523abcacc61f0a22a440b051acea42314cf106dbd224bdb940.jpg)

![527a7e04b131b804ecda5a84e60c451ee1e80950497ebe51786d0172445dd65c.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/527a7e04b131b804ecda5a84e60c451ee1e80950497ebe51786d0172445dd65c.jpg)

![77c94eed2a41ac26186ec63d8cbfa216d1167f7a14fb4f28b6769632a5d0e9bb.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/77c94eed2a41ac26186ec63d8cbfa216d1167f7a14fb4f28b6769632a5d0e9bb.jpg)

![87011dd9333a2db42a58a71feb57658a031f89d2b75800bbe53f663dc1a7e0df.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/87011dd9333a2db42a58a71feb57658a031f89d2b75800bbe53f663dc1a7e0df.jpg)

![93d58a3f7bfbdf09aba12d11462291ad9086b05604705debcabf420657586092.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/93d58a3f7bfbdf09aba12d11462291ad9086b05604705debcabf420657586092.jpg)

![97ee684ba4bebd3624e48977cbdf376ae3a1dd2a303907a85c6377a92738339a.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/97ee684ba4bebd3624e48977cbdf376ae3a1dd2a303907a85c6377a92738339a.jpg)

![9cda92deeaeef18c0e85a22fd889a42d14a62cf9fb053dd80af807f4f0f4235c.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/9cda92deeaeef18c0e85a22fd889a42d14a62cf9fb053dd80af807f4f0f4235c.jpg)

![b0029d66cc99866f9ab4002fff94db82fe7f84c4beae95346375a5866b6cc185.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/b0029d66cc99866f9ab4002fff94db82fe7f84c4beae95346375a5866b6cc185.jpg)

![ff2ce85439f317a32d85c578d0720bc107695b8bbbed0ba9978f8a744677b8cc.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/images/ff2ce85439f317a32d85c578d0720bc107695b8bbbed0ba9978f8a744677b8cc.jpg)

### Tables

![455931c886e12d48192e69eb1e76c4b049a5c284604c81bd4eb1140e8b9c6832.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/tables/455931c886e12d48192e69eb1e76c4b049a5c284604c81bd4eb1140e8b9c6832.jpg)

![4739a98f2e09ef585f70f70efdecd722b111f08552fbf1ee670cfa2b45cea3c5.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/tables/4739a98f2e09ef585f70f70efdecd722b111f08552fbf1ee670cfa2b45cea3c5.jpg)

![91cdde477933d70d80385b1f421fb60b7363e12cb27a7510eaa4a2eda2f07da6.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/tables/91cdde477933d70d80385b1f421fb60b7363e12cb27a7510eaa4a2eda2f07da6.jpg)

![dbbdb529c8f3021c40f1eba027538bc04ad16802e09fff545496e522dfcc93df.jpg](../nips_results/4624_CryptoMoE_%20Privacy-Preserving%20and%20Scalable%20Mixture%20of%20Experts%20Inference%20via%20Balanced%20Expert%20Routing/tables/dbbdb529c8f3021c40f1eba027538bc04ad16802e09fff545496e522dfcc93df.jpg)

## Transferring Causal Effects using Proxies


### Images

![400d94c60cdd2438b409eb370094af41f4cd5dc1c8d0b8acd0ec35a187bafa12.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/400d94c60cdd2438b409eb370094af41f4cd5dc1c8d0b8acd0ec35a187bafa12.jpg)

![4176fea139c4cdf76a699d37331206692415cb7992ef9cba6e8cf13f8ee2efaf.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/4176fea139c4cdf76a699d37331206692415cb7992ef9cba6e8cf13f8ee2efaf.jpg)

![46747f4a58fd29a6b0eb4322df4180eb9487c7f48e851401f701af9ea432cc39.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/46747f4a58fd29a6b0eb4322df4180eb9487c7f48e851401f701af9ea432cc39.jpg)

![4aa0721ccfc9ce64f911ab1a958a60a9c7adf2c14221f29b8dd088b5f987ff55.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/4aa0721ccfc9ce64f911ab1a958a60a9c7adf2c14221f29b8dd088b5f987ff55.jpg)

![5508fcc1d822a6c5a290f815d2d3774e2449ef19d717279246ffd3749bb8e789.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/5508fcc1d822a6c5a290f815d2d3774e2449ef19d717279246ffd3749bb8e789.jpg)

![63700f9e910d0015620fbb96da0e393cc45efe87254052cc4825aab5bc39df56.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/63700f9e910d0015620fbb96da0e393cc45efe87254052cc4825aab5bc39df56.jpg)

![7fc0b735035c50c2c57d3083e94f4c0fb1364336636a41b70279637c4512946d.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/7fc0b735035c50c2c57d3083e94f4c0fb1364336636a41b70279637c4512946d.jpg)

![8a88ae1637189dad132e704e802cb2be76551a1d7530eb925854f6c0b0021409.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/8a88ae1637189dad132e704e802cb2be76551a1d7530eb925854f6c0b0021409.jpg)

![9020a349e9e0b29e470aff368eb70cf88e2d753e56162bb23939858026253a12.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/9020a349e9e0b29e470aff368eb70cf88e2d753e56162bb23939858026253a12.jpg)

![92d7603873458ff87443579ccd7b40cdc24d376bddac70bc70db6f2321df4601.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/92d7603873458ff87443579ccd7b40cdc24d376bddac70bc70db6f2321df4601.jpg)

![9932bd077b21615e6eab2a314eeaae6f68f2a4f61a8c37b5c86eba63cdd0464b.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/9932bd077b21615e6eab2a314eeaae6f68f2a4f61a8c37b5c86eba63cdd0464b.jpg)

![b5e954bb0db83bc6aa9fed425d8370916b4fdcf9a01a7c5bd3b5eb20966ebb70.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/b5e954bb0db83bc6aa9fed425d8370916b4fdcf9a01a7c5bd3b5eb20966ebb70.jpg)

![c718e41a8be080e6cdb267ce5e07bfd8ec66ed19eed8e9f73b94c9a8616cf9fa.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/c718e41a8be080e6cdb267ce5e07bfd8ec66ed19eed8e9f73b94c9a8616cf9fa.jpg)

![dea29bcc957e1167b0f532c3a5d8174d122f24afede05f7a1ba5ff1cf96ba77d.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/images/dea29bcc957e1167b0f532c3a5d8174d122f24afede05f7a1ba5ff1cf96ba77d.jpg)

### Tables

![3419ad1d656c2f7137f35bbc6c3f941109e29db3c9dab3dd93cb954e95e622e9.jpg](../nips_results/4625_Transferring%20Causal%20Effects%20using%20Proxies/tables/3419ad1d656c2f7137f35bbc6c3f941109e29db3c9dab3dd93cb954e95e622e9.jpg)

## Traversal Verification for Speculative Tree Decoding


### Images

![3b66ac1866a5ffa1fa2dc348738e920b138c434f728380a64ec6bc59c8e5d48b.jpg](../nips_results/4626_Traversal%20Verification%20for%20Speculative%20Tree%20Decoding/images/3b66ac1866a5ffa1fa2dc348738e920b138c434f728380a64ec6bc59c8e5d48b.jpg)

![89e73002ce8b1122507a52a0afeadae8f3861a7f8308fd626f9c841101cb676d.jpg](../nips_results/4626_Traversal%20Verification%20for%20Speculative%20Tree%20Decoding/images/89e73002ce8b1122507a52a0afeadae8f3861a7f8308fd626f9c841101cb676d.jpg)

![8af9af7c27ccd9ff04d2b3ee7fed3a22a1ab0af7b5ec6698902c0658eedd90af.jpg](../nips_results/4626_Traversal%20Verification%20for%20Speculative%20Tree%20Decoding/images/8af9af7c27ccd9ff04d2b3ee7fed3a22a1ab0af7b5ec6698902c0658eedd90af.jpg)

![9cb9eb45b029c0e5699f8d06f9832c4d9fa80fdad64e1c8428bbc5b5bd52b5a8.jpg](../nips_results/4626_Traversal%20Verification%20for%20Speculative%20Tree%20Decoding/images/9cb9eb45b029c0e5699f8d06f9832c4d9fa80fdad64e1c8428bbc5b5bd52b5a8.jpg)

![f09c1b0468ecce7b3ea123ec9cd4dac99e9407bb061305c7a57cff2f95546266.jpg](../nips_results/4626_Traversal%20Verification%20for%20Speculative%20Tree%20Decoding/images/f09c1b0468ecce7b3ea123ec9cd4dac99e9407bb061305c7a57cff2f95546266.jpg)

### Tables

![195a9eec23e588801c100b83d629abd7b033d753a4207416a2827735ecd837bf.jpg](../nips_results/4626_Traversal%20Verification%20for%20Speculative%20Tree%20Decoding/tables/195a9eec23e588801c100b83d629abd7b033d753a4207416a2827735ecd837bf.jpg)

![5f4adbbb2eb31d9c2ae6eaec30b14db58247a31d1fde66a771304478098930b7.jpg](../nips_results/4626_Traversal%20Verification%20for%20Speculative%20Tree%20Decoding/tables/5f4adbbb2eb31d9c2ae6eaec30b14db58247a31d1fde66a771304478098930b7.jpg)

![7fc1f426759e8e472301b9f9caf84cdb5e9d501bab6a1e97b6661c98dd650382.jpg](../nips_results/4626_Traversal%20Verification%20for%20Speculative%20Tree%20Decoding/tables/7fc1f426759e8e472301b9f9caf84cdb5e9d501bab6a1e97b6661c98dd650382.jpg)

![b2c1b21599ed5ef1df0ef716ea6da685e43bc738118dd20b6199eb3e7aaf9532.jpg](../nips_results/4626_Traversal%20Verification%20for%20Speculative%20Tree%20Decoding/tables/b2c1b21599ed5ef1df0ef716ea6da685e43bc738118dd20b6199eb3e7aaf9532.jpg)

![dac6e7dd0444650ca2184675374c9fdf4ba113f6c06d8bf044c40bf7135d9ac8.jpg](../nips_results/4626_Traversal%20Verification%20for%20Speculative%20Tree%20Decoding/tables/dac6e7dd0444650ca2184675374c9fdf4ba113f6c06d8bf044c40bf7135d9ac8.jpg)

![e62f16d33e8080643b90fe092a5d80831c9305db4b2f279b214cadf1c8668c0d.jpg](../nips_results/4626_Traversal%20Verification%20for%20Speculative%20Tree%20Decoding/tables/e62f16d33e8080643b90fe092a5d80831c9305db4b2f279b214cadf1c8668c0d.jpg)

## PIVNO: Particle Image Velocimetry Neural Operator


### Images

![1a59655235557dc9e0d8c95c8d2c205211241dff035fed3e6a1b696fce6452d2.jpg](../nips_results/4627_PIVNO_%20Particle%20Image%20Velocimetry%20Neural%20Operator/images/1a59655235557dc9e0d8c95c8d2c205211241dff035fed3e6a1b696fce6452d2.jpg)

![21ccbe7520d2baf301ad73fb1955feb1b9d1adcf198af5a2aeec08762b08488e.jpg](../nips_results/4627_PIVNO_%20Particle%20Image%20Velocimetry%20Neural%20Operator/images/21ccbe7520d2baf301ad73fb1955feb1b9d1adcf198af5a2aeec08762b08488e.jpg)

![4fe7e818921a2b5e5d9851c25934a03ee6cd110f7e51e4e885c8c0594f941582.jpg](../nips_results/4627_PIVNO_%20Particle%20Image%20Velocimetry%20Neural%20Operator/images/4fe7e818921a2b5e5d9851c25934a03ee6cd110f7e51e4e885c8c0594f941582.jpg)

![95f73b4bd00ada9dc47e8ef32bae2314d96d036b48740baf4a7f0ac37c710d39.jpg](../nips_results/4627_PIVNO_%20Particle%20Image%20Velocimetry%20Neural%20Operator/images/95f73b4bd00ada9dc47e8ef32bae2314d96d036b48740baf4a7f0ac37c710d39.jpg)

![c75cc07f3a41fb8e1dbda7d1b090eca76f2c733f041320bd305739ce8a6e26c1.jpg](../nips_results/4627_PIVNO_%20Particle%20Image%20Velocimetry%20Neural%20Operator/images/c75cc07f3a41fb8e1dbda7d1b090eca76f2c733f041320bd305739ce8a6e26c1.jpg)

### Tables

![a4ccf83b603006163fed5e2dac451a840f35b783373c461fa425f8ab7b3a45f8.jpg](../nips_results/4627_PIVNO_%20Particle%20Image%20Velocimetry%20Neural%20Operator/tables/a4ccf83b603006163fed5e2dac451a840f35b783373c461fa425f8ab7b3a45f8.jpg)

![a5c8d9d3c17195459f8d70df3a9c6464f548460dd45639fc9d9a69798e42a896.jpg](../nips_results/4627_PIVNO_%20Particle%20Image%20Velocimetry%20Neural%20Operator/tables/a5c8d9d3c17195459f8d70df3a9c6464f548460dd45639fc9d9a69798e42a896.jpg)

![ab3e54c48c99780965d844aedac5d023dd894af9bbf43042ce42b4a36c4fcdb1.jpg](../nips_results/4627_PIVNO_%20Particle%20Image%20Velocimetry%20Neural%20Operator/tables/ab3e54c48c99780965d844aedac5d023dd894af9bbf43042ce42b4a36c4fcdb1.jpg)

## Variational Inference with  Mixtures of Isotropic Gaussians


### Images

![086160ab5cde2ccfb02c49d1023f4b7e4834325457dc0f29358274203087e53d.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/086160ab5cde2ccfb02c49d1023f4b7e4834325457dc0f29358274203087e53d.jpg)

![2e71e11fd61ae73bd6053504c5cda9d7bc6bb3103d4b1a65f00f7753f5720a23.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/2e71e11fd61ae73bd6053504c5cda9d7bc6bb3103d4b1a65f00f7753f5720a23.jpg)

![545f9cb0305e10318c822f87870db3c377c9428927773e4a7de6950d51321d32.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/545f9cb0305e10318c822f87870db3c377c9428927773e4a7de6950d51321d32.jpg)

![5d7dd1616701af7943d7465f4170073c43155cc80c7ac605925514da95f9b062.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/5d7dd1616701af7943d7465f4170073c43155cc80c7ac605925514da95f9b062.jpg)

![690d102d02d0c1d55e70a1dee910405b0dbef7d614752c2f44cd457d542dd34c.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/690d102d02d0c1d55e70a1dee910405b0dbef7d614752c2f44cd457d542dd34c.jpg)

![6bc86573120a635462a627e01fa0795b0d8586c12cd4b77c8345f74d942f34fd.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/6bc86573120a635462a627e01fa0795b0d8586c12cd4b77c8345f74d942f34fd.jpg)

![89fa86ccd2a9fdb896b559f2c69156e1e73cd64f6fa7978d20adb201230016ee.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/89fa86ccd2a9fdb896b559f2c69156e1e73cd64f6fa7978d20adb201230016ee.jpg)

![8d6984c2bc6e10a8e1929911c6915e5a32ea27ffac889218d4a46a403a38979e.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/8d6984c2bc6e10a8e1929911c6915e5a32ea27ffac889218d4a46a403a38979e.jpg)

![997660ad4f394bd6b5c8b5045833ec6dd3054c733ad208d61d3d83ee706bf49e.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/997660ad4f394bd6b5c8b5045833ec6dd3054c733ad208d61d3d83ee706bf49e.jpg)

![a3ce6f0c4e1f22185f6771e6ff577d9f1f2216cea414e6935ccca51eb2286fe3.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/a3ce6f0c4e1f22185f6771e6ff577d9f1f2216cea414e6935ccca51eb2286fe3.jpg)

![a4b9cabf0507464d2307a086e374bf504ae9385784734333784a3ae4f347719d.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/a4b9cabf0507464d2307a086e374bf504ae9385784734333784a3ae4f347719d.jpg)

![b7de6cd977fa54ff18720d8cecf7a0f9fe4c22f034af50cff4486ec54fcb1261.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/b7de6cd977fa54ff18720d8cecf7a0f9fe4c22f034af50cff4486ec54fcb1261.jpg)

![ee4c966d439f7812375006c61d1f44ffcf674b80cbf94b1dd6b9ef861e07279e.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/images/ee4c966d439f7812375006c61d1f44ffcf674b80cbf94b1dd6b9ef861e07279e.jpg)

### Tables

![f4f11eac202991dbc82e30415fb09dab257ea6cf22ab48f8c6e5bb04044af673.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/tables/f4f11eac202991dbc82e30415fb09dab257ea6cf22ab48f8c6e5bb04044af673.jpg)

![f8fec3cc1c137f54bb338ff4cf6c5b5cd84dcd3a27539ad850e9818562a71e87.jpg](../nips_results/4628_Variational%20Inference%20with%20%20Mixtures%20of%20Isotropic%20Gaussians/tables/f8fec3cc1c137f54bb338ff4cf6c5b5cd84dcd3a27539ad850e9818562a71e87.jpg)

## Heterogeneous Diffusion Structure Inference for Network Cascade


### Images

![0f3666bd634d0791b62201da1b85d0916cc4b60b434615a777e5cdf6c4601165.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/images/0f3666bd634d0791b62201da1b85d0916cc4b60b434615a777e5cdf6c4601165.jpg)

![184e442de09f4af6756e8ba5fc3fa303bfeccdc297cd8e619a11f9772d914b95.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/images/184e442de09f4af6756e8ba5fc3fa303bfeccdc297cd8e619a11f9772d914b95.jpg)

![31136f66325296fd9f2c1088b1773b0b9edea44c74c51ae696953d289e80a4b2.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/images/31136f66325296fd9f2c1088b1773b0b9edea44c74c51ae696953d289e80a4b2.jpg)

![36ab552c712fb753f2acaa964d02848486834504c2d41be3f930812a71e46f84.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/images/36ab552c712fb753f2acaa964d02848486834504c2d41be3f930812a71e46f84.jpg)

![3927fa4def23bdf23e7e368ddbc7a2c406a3a9c3567c0abe70cde0fe1cbb639a.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/images/3927fa4def23bdf23e7e368ddbc7a2c406a3a9c3567c0abe70cde0fe1cbb639a.jpg)

![63d40dbd143b038b1935264bd618c7157f99b756f71923099f713ff2064225d1.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/images/63d40dbd143b038b1935264bd618c7157f99b756f71923099f713ff2064225d1.jpg)

![b27d3e7e8f0a087a3771a9311023b84a296f53f4ebfcb430ac51b27dc1672ae1.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/images/b27d3e7e8f0a087a3771a9311023b84a296f53f4ebfcb430ac51b27dc1672ae1.jpg)

![f8e5cd3948b04239c79fc7c06f00fb8ff3252ba30fa191d323121c07fe6c5e61.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/images/f8e5cd3948b04239c79fc7c06f00fb8ff3252ba30fa191d323121c07fe6c5e61.jpg)

### Tables

![21ddb8d662f8a81a6491c369743e9efaf5e0af211733ab010bae2ec4e78838d9.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/tables/21ddb8d662f8a81a6491c369743e9efaf5e0af211733ab010bae2ec4e78838d9.jpg)

![22ab3af32ebc0d014aa1f549d5f52a4f391879fdf197bf9e862fa79236f942b0.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/tables/22ab3af32ebc0d014aa1f549d5f52a4f391879fdf197bf9e862fa79236f942b0.jpg)

![3a8ee028d74744f2696e4d712b8785c81fc64ac1709800c99f21e4cc81163a27.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/tables/3a8ee028d74744f2696e4d712b8785c81fc64ac1709800c99f21e4cc81163a27.jpg)

![4b800032d218bf8330cac5003800b8f0935fe52e9ba8251d98746b72c0ee2b6d.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/tables/4b800032d218bf8330cac5003800b8f0935fe52e9ba8251d98746b72c0ee2b6d.jpg)

![b5309b78da0738012cb3e4918a6ee857d8c10b36232991ca3665c9480e9cd932.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/tables/b5309b78da0738012cb3e4918a6ee857d8c10b36232991ca3665c9480e9cd932.jpg)

![eb60566efe27703e4865bc4c4491c342ce396332d536a8ef293d4e08a4a217fc.jpg](../nips_results/4629_Heterogeneous%20Diffusion%20Structure%20Inference%20for%20Network%20Cascade/tables/eb60566efe27703e4865bc4c4491c342ce396332d536a8ef293d4e08a4a217fc.jpg)

## Certifying Concavity and Monotonicity in Games via Sum-of-Squares Hierarchies


### Images

![42f8744dad4672a265c1c0a6779b58e5f2853a42bb8f1c9006ce2b72f87b4c3b.jpg](../nips_results/4630_Certifying%20Concavity%20and%20Monotonicity%20in%20Games%20via%20Sum-of-Squares%20Hierarchies/images/42f8744dad4672a265c1c0a6779b58e5f2853a42bb8f1c9006ce2b72f87b4c3b.jpg)

![683d34d890bbad6ca0246ede7fd655a32b376f1104f38988588651af9ce8f2a6.jpg](../nips_results/4630_Certifying%20Concavity%20and%20Monotonicity%20in%20Games%20via%20Sum-of-Squares%20Hierarchies/images/683d34d890bbad6ca0246ede7fd655a32b376f1104f38988588651af9ce8f2a6.jpg)

![ba7398b4b0986c40c6a5ddf71878aece42969d72dc6672232f42eea6f91231da.jpg](../nips_results/4630_Certifying%20Concavity%20and%20Monotonicity%20in%20Games%20via%20Sum-of-Squares%20Hierarchies/images/ba7398b4b0986c40c6a5ddf71878aece42969d72dc6672232f42eea6f91231da.jpg)

![e73827aa0bf75504aef44dad7dc501d949228c53fe36fce4fd92b9e5b5e81425.jpg](../nips_results/4630_Certifying%20Concavity%20and%20Monotonicity%20in%20Games%20via%20Sum-of-Squares%20Hierarchies/images/e73827aa0bf75504aef44dad7dc501d949228c53fe36fce4fd92b9e5b5e81425.jpg)

## ADG: Ambient Diffusion-Guided Dataset Recovery for Corruption-Robust Offline Reinforcement Learning


### Images

![446d569d1dc1c77bbcfd0c0d6ef70611b433fd02a61f73cbcfcbd14550af95d3.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/446d569d1dc1c77bbcfd0c0d6ef70611b433fd02a61f73cbcfcbd14550af95d3.jpg)

![5c49d6932226ae860090a633909e4279d54798a10677d98d1ff7ac8c7f23a077.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/5c49d6932226ae860090a633909e4279d54798a10677d98d1ff7ac8c7f23a077.jpg)

![8994841080f66af8002ab58f30cc20673bd8abb1e2fd0afa414cb7f2d7351807.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/8994841080f66af8002ab58f30cc20673bd8abb1e2fd0afa414cb7f2d7351807.jpg)

![8e6874abbfcc3b080cb6373ff8687b91f76f2f21ac3a11fd8c1eef69b4966bc4.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/8e6874abbfcc3b080cb6373ff8687b91f76f2f21ac3a11fd8c1eef69b4966bc4.jpg)

![95fccb5255f3d4af574230f1a692698f3fb205941966d1857b083f0f5b8a8138.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/95fccb5255f3d4af574230f1a692698f3fb205941966d1857b083f0f5b8a8138.jpg)

![9a6910aa910cfc2091f1110e7c68a22f8c6f09714c52932478358d2667d0d6bf.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/9a6910aa910cfc2091f1110e7c68a22f8c6f09714c52932478358d2667d0d6bf.jpg)

![b40ea09aaab579e50c750db7a18ba58a8f3a39eca13606426abd091bf7d070e6.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/b40ea09aaab579e50c750db7a18ba58a8f3a39eca13606426abd091bf7d070e6.jpg)

![c4903027ce110f5ab8625c323c0415f15778305246aee25f789cb47f8174be1b.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/c4903027ce110f5ab8625c323c0415f15778305246aee25f789cb47f8174be1b.jpg)

![ca4e8e72e9ae51a24f987534b6fa574e5012b852064799aa31669bf2aa5492e3.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/ca4e8e72e9ae51a24f987534b6fa574e5012b852064799aa31669bf2aa5492e3.jpg)

![d1982f7ceb07c3bc557b1675d157998a4f623d6eb32cc79f5ddc73f8c7827c35.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/d1982f7ceb07c3bc557b1675d157998a4f623d6eb32cc79f5ddc73f8c7827c35.jpg)

![ef5efe3e94b66fefbead8e752157ba32e8a2845b54a132ecd34c70736b2dfc2c.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/ef5efe3e94b66fefbead8e752157ba32e8a2845b54a132ecd34c70736b2dfc2c.jpg)

![f355426e57c70bf5e368d0c9c04efa9cf8002e9b8c3ff4ca8b83282a4a242c6e.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/f355426e57c70bf5e368d0c9c04efa9cf8002e9b8c3ff4ca8b83282a4a242c6e.jpg)

![f5bb75391b1abc27d91b0a261ecd17f6cff3f6cefa51d103e7c7174335e51841.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/f5bb75391b1abc27d91b0a261ecd17f6cff3f6cefa51d103e7c7174335e51841.jpg)

![f81750f0a7e45690cba8115a01d7e86b66b47ee1e7a2357d85b89867f602614b.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/images/f81750f0a7e45690cba8115a01d7e86b66b47ee1e7a2357d85b89867f602614b.jpg)

### Tables

![06ca714fd7784a97079ccbe8ab58fae9f3693d05cf5d254d70bd0f2f44ed3660.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/06ca714fd7784a97079ccbe8ab58fae9f3693d05cf5d254d70bd0f2f44ed3660.jpg)

![28b1c7d9f229c07d9c0d3756748b10a9e3e4b151b047f7cb5bfe5d70980feacb.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/28b1c7d9f229c07d9c0d3756748b10a9e3e4b151b047f7cb5bfe5d70980feacb.jpg)

![4025eae6c50eabb1a4a859ffd535489d1e854e9c46f4a766366a6ffdb072c4cc.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/4025eae6c50eabb1a4a859ffd535489d1e854e9c46f4a766366a6ffdb072c4cc.jpg)

![42cd4b077ca364832876117ae7b58b9e630744c3726023726f506c1f005ad8f5.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/42cd4b077ca364832876117ae7b58b9e630744c3726023726f506c1f005ad8f5.jpg)

![4c169be569603608f6d67735d29f7547cff319c23f62a2022c05cd0170d57c02.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/4c169be569603608f6d67735d29f7547cff319c23f62a2022c05cd0170d57c02.jpg)

![5210fd87cf9f833e9da641b29e1dd5588fdf7bf4932cf9c318ea8135c5520e4f.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/5210fd87cf9f833e9da641b29e1dd5588fdf7bf4932cf9c318ea8135c5520e4f.jpg)

![58be4d3f4150a298e17a8d568e39afa49a3437ef954cc77a7ef2fa067af90ccb.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/58be4d3f4150a298e17a8d568e39afa49a3437ef954cc77a7ef2fa067af90ccb.jpg)

![96f4512f0eb38d02e95433f13aec71c5f208555b28780d3955c10b4932bb1f5c.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/96f4512f0eb38d02e95433f13aec71c5f208555b28780d3955c10b4932bb1f5c.jpg)

![992767293cb0ab0c20c1aa4d80d5bddf40547bf0e5ade305b2e8edfbf7a5d7a0.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/992767293cb0ab0c20c1aa4d80d5bddf40547bf0e5ade305b2e8edfbf7a5d7a0.jpg)

![9b4068dbf379acaced258230a0e8fe616151f700b5b447905dd6e9692fcb86f4.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/9b4068dbf379acaced258230a0e8fe616151f700b5b447905dd6e9692fcb86f4.jpg)

![b048b66f22499c6a6823df4d9d67c5c4cda87f683da7d50e127a3bfb2999176f.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/b048b66f22499c6a6823df4d9d67c5c4cda87f683da7d50e127a3bfb2999176f.jpg)

![c49983fa34cc5f4ed2b6e5e0117c5a29e85550767ddd3fab835bffdcf594dd45.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/c49983fa34cc5f4ed2b6e5e0117c5a29e85550767ddd3fab835bffdcf594dd45.jpg)

![dd56d8d759db52a57a74b28237029d4492f6c52dff9d6f3c80f517a451fa871c.jpg](../nips_results/4631_ADG_%20Ambient%20Diffusion-Guided%20Dataset%20Recovery%20for%20Corruption-Robust%20Offline%20Reinforcement%20Learning/tables/dd56d8d759db52a57a74b28237029d4492f6c52dff9d6f3c80f517a451fa871c.jpg)

## SegGraph: Leveraging Graphs of SAM Segments for Few-Shot 3D Part Segmentation


### Images

![18b14446c5081bcd9d76fed415547956eeba4a742d210cdf97304c31c5b622d3.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/images/18b14446c5081bcd9d76fed415547956eeba4a742d210cdf97304c31c5b622d3.jpg)

![25505cb22441075d2c57b6f49c7a8910b6f58d7cc274327e88b814787390f278.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/images/25505cb22441075d2c57b6f49c7a8910b6f58d7cc274327e88b814787390f278.jpg)

![48a74df096d2d0384dae80a5e102df4f2b5a05ffb106e3b2acdba600bf4985d2.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/images/48a74df096d2d0384dae80a5e102df4f2b5a05ffb106e3b2acdba600bf4985d2.jpg)

![6ea6bf54e5a7cff6a937b4db258ebf018c4169747eb31490b92d831680bdb4bb.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/images/6ea6bf54e5a7cff6a937b4db258ebf018c4169747eb31490b92d831680bdb4bb.jpg)

![a26b41c92e6cbb43b255f1547c68c395f473b837ca7af5ecaac3ea8b08d03ebf.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/images/a26b41c92e6cbb43b255f1547c68c395f473b837ca7af5ecaac3ea8b08d03ebf.jpg)

![a90c6533d25652d324e18faf7e891e20d9a9dbc0b55b4486d1bfbf5e85702ff9.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/images/a90c6533d25652d324e18faf7e891e20d9a9dbc0b55b4486d1bfbf5e85702ff9.jpg)

![b8145990b2d79427886825b96fc184d34092c8020bcb3142cc3b4d5582d5202f.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/images/b8145990b2d79427886825b96fc184d34092c8020bcb3142cc3b4d5582d5202f.jpg)

![e763eefcd5964811e9d7b6d5b534b69592753a0edcea74ef3cee2c2cfd239e07.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/images/e763eefcd5964811e9d7b6d5b534b69592753a0edcea74ef3cee2c2cfd239e07.jpg)

### Tables

![24b408fe19e3e6e1e1cdb626d2261e43e837ced4e0686bf5bd801774f2b314b4.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/tables/24b408fe19e3e6e1e1cdb626d2261e43e837ced4e0686bf5bd801774f2b314b4.jpg)

![499b285cf5ec3eec91cc0c7c1c89e3019be426d05de0f4ec81a4d08c4ec39ffd.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/tables/499b285cf5ec3eec91cc0c7c1c89e3019be426d05de0f4ec81a4d08c4ec39ffd.jpg)

![5c8d6b219bb60e1392993f175c5aded49c276cc77ccd792c7e89cf9f20b9cb5e.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/tables/5c8d6b219bb60e1392993f175c5aded49c276cc77ccd792c7e89cf9f20b9cb5e.jpg)

![5fbf704d5b0c94441916be51ae83eaf3450f2ed75635351a24b4b60274ccc5a2.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/tables/5fbf704d5b0c94441916be51ae83eaf3450f2ed75635351a24b4b60274ccc5a2.jpg)

![9b9352c639bd05606b4d0419566cfb8d3825ecfa52f147d72bb5206eb2dfcfdd.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/tables/9b9352c639bd05606b4d0419566cfb8d3825ecfa52f147d72bb5206eb2dfcfdd.jpg)

![d872fb30151d22049e069c823b2e9606c76f759f16258186962622c49df948b8.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/tables/d872fb30151d22049e069c823b2e9606c76f759f16258186962622c49df948b8.jpg)

![f20c466e3df47838df1bcfc38fe32994fdc53e5fbc5125fb7c155b3dd2678637.jpg](../nips_results/4632_SegGraph_%20Leveraging%20Graphs%20of%20SAM%20Segments%20for%20Few-Shot%203D%20Part%20Segmentation/tables/f20c466e3df47838df1bcfc38fe32994fdc53e5fbc5125fb7c155b3dd2678637.jpg)

## Better NTK Conditioning: A Free Lunch from (ReLU) Nonlinear Activation in Wide Neural Networks


### Images

![43ce1a696451823e09f14fe5e17d7a49364119731b8ba397f0cd1e27647fb383.jpg](../nips_results/4633_Better%20NTK%20Conditioning_%20A%20Free%20Lunch%20from%20%28ReLU) Nonlinear Activation in Wide Neural Networks/images/43ce1a696451823e09f14fe5e17d7a49364119731b8ba397f0cd1e27647fb383.jpg)

![449306e1353f140c6d8bce8bb8b06a85c51578b37f478109c21fe1f3d160d2c3.jpg](../nips_results/4633_Better%20NTK%20Conditioning_%20A%20Free%20Lunch%20from%20%28ReLU) Nonlinear Activation in Wide Neural Networks/images/449306e1353f140c6d8bce8bb8b06a85c51578b37f478109c21fe1f3d160d2c3.jpg)

![4979faceec1947bd7c98dea5d4cab887f6f70781f3a491912b6eda30f7c0c6d2.jpg](../nips_results/4633_Better%20NTK%20Conditioning_%20A%20Free%20Lunch%20from%20%28ReLU) Nonlinear Activation in Wide Neural Networks/images/4979faceec1947bd7c98dea5d4cab887f6f70781f3a491912b6eda30f7c0c6d2.jpg)

![7d6cee81176846dc5d9368f2e3d52f2eaed037ba0fbd374dad0516e4c1555926.jpg](../nips_results/4633_Better%20NTK%20Conditioning_%20A%20Free%20Lunch%20from%20%28ReLU) Nonlinear Activation in Wide Neural Networks/images/7d6cee81176846dc5d9368f2e3d52f2eaed037ba0fbd374dad0516e4c1555926.jpg)

![8468f73e75f00929a24062c7b344e65dd509435ad34850a6f6a4d728604c5130.jpg](../nips_results/4633_Better%20NTK%20Conditioning_%20A%20Free%20Lunch%20from%20%28ReLU) Nonlinear Activation in Wide Neural Networks/images/8468f73e75f00929a24062c7b344e65dd509435ad34850a6f6a4d728604c5130.jpg)

![ba90880dab974d603763d2d9a0b414eeaae50ef369bd136991ae0ad3a33e9d7a.jpg](../nips_results/4633_Better%20NTK%20Conditioning_%20A%20Free%20Lunch%20from%20%28ReLU) Nonlinear Activation in Wide Neural Networks/images/ba90880dab974d603763d2d9a0b414eeaae50ef369bd136991ae0ad3a33e9d7a.jpg)

### Tables

![a520a4c9aecf95426a9019a46391e1706d4ccd2f722996c8a39e53725b5c62c6.jpg](../nips_results/4633_Better%20NTK%20Conditioning_%20A%20Free%20Lunch%20from%20%28ReLU) Nonlinear Activation in Wide Neural Networks/tables/a520a4c9aecf95426a9019a46391e1706d4ccd2f722996c8a39e53725b5c62c6.jpg)

## VaMP: Variational Multi-Modal Prompt Learning for Vision-Language Models


### Images

![31a81eef03b1429c86c0fd7e83410f4ea95612aa37ecfefd085e9f6beddc7662.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/images/31a81eef03b1429c86c0fd7e83410f4ea95612aa37ecfefd085e9f6beddc7662.jpg)

![b69ab434305ed26e215314f743b91c64fe360367a3981b8a9367b2548cdee958.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/images/b69ab434305ed26e215314f743b91c64fe360367a3981b8a9367b2548cdee958.jpg)

### Tables

![044a54f6cd63ee0d4534c6b3a880daef8e198f17d533639dca7914024bee6557.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/044a54f6cd63ee0d4534c6b3a880daef8e198f17d533639dca7914024bee6557.jpg)

![0ea37aecf4dbac1e9207b4495a091c5f1e083ed86184625b70acf4d402387ad1.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/0ea37aecf4dbac1e9207b4495a091c5f1e083ed86184625b70acf4d402387ad1.jpg)

![140be426bc125ee611564c7ccfd358e69c0e082eaff9cff43e2a12734ec0e834.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/140be426bc125ee611564c7ccfd358e69c0e082eaff9cff43e2a12734ec0e834.jpg)

![18b6ddffb76bf4746a6e254a317b9d819cc4161d33e500064b4e0826e9471693.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/18b6ddffb76bf4746a6e254a317b9d819cc4161d33e500064b4e0826e9471693.jpg)

![1f7042a4945e8b632844ddce93caa83bf67a40f3e60842bae9130debb8f8c044.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/1f7042a4945e8b632844ddce93caa83bf67a40f3e60842bae9130debb8f8c044.jpg)

![2aee4c46b559d8300b620a9db9043674c2940927bd43e4bfa75cd8b7e86e6388.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/2aee4c46b559d8300b620a9db9043674c2940927bd43e4bfa75cd8b7e86e6388.jpg)

![82446b66f395abf2ee7e88f71d9265349f9092f1572d97d170ee15fec5169a7a.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/82446b66f395abf2ee7e88f71d9265349f9092f1572d97d170ee15fec5169a7a.jpg)

![93cb6e1fe9127f01f98665bb58d6e7aee6bb638d504671f59430e061fe57fd6e.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/93cb6e1fe9127f01f98665bb58d6e7aee6bb638d504671f59430e061fe57fd6e.jpg)

![994d373297a93062c16b562d7d87ae90ebe40c4297723f9bf9b52a2e70349341.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/994d373297a93062c16b562d7d87ae90ebe40c4297723f9bf9b52a2e70349341.jpg)

![a5cc4078d0b35e82331909d62713b43075967c8244cadcc7a4d291c05f7ac2c7.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/a5cc4078d0b35e82331909d62713b43075967c8244cadcc7a4d291c05f7ac2c7.jpg)

![ca39ae10d265f19b12840f1fae35fef441a8c357ba19207a6dee4a4d7add1fae.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/ca39ae10d265f19b12840f1fae35fef441a8c357ba19207a6dee4a4d7add1fae.jpg)

![f1bf89eb40789f08770a201401a14b9ffc3f59f431a692da297f20631f3a12f6.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/f1bf89eb40789f08770a201401a14b9ffc3f59f431a692da297f20631f3a12f6.jpg)

![f3700fe5de3503a655e2798e4123e264171af320abf8aa9339dd343fab1bcfdd.jpg](../nips_results/4634_VaMP_%20Variational%20Multi-Modal%20Prompt%20Learning%20for%20Vision-Language%20Models/tables/f3700fe5de3503a655e2798e4123e264171af320abf8aa9339dd343fab1bcfdd.jpg)

## Inference-Time Hyper-Scaling with KV Cache Compression


### Images

![076c4a766721e9ef189608017703ef0bd71b27a5d0b079ce434275cca13bd56b.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/images/076c4a766721e9ef189608017703ef0bd71b27a5d0b079ce434275cca13bd56b.jpg)

![0cb150832666613a41299f0cead1ac7d77d1b17fffd2b9a0db7b2f8917341773.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/images/0cb150832666613a41299f0cead1ac7d77d1b17fffd2b9a0db7b2f8917341773.jpg)

![1151849de7688f0347bd38806a6d19525b80531b0fdecbe471e32f3155cd6f18.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/images/1151849de7688f0347bd38806a6d19525b80531b0fdecbe471e32f3155cd6f18.jpg)

![1919ea4bd4cdc7c74dfb62009220fa849c4a8781a5bc2d50c57c25dc75ad6c82.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/images/1919ea4bd4cdc7c74dfb62009220fa849c4a8781a5bc2d50c57c25dc75ad6c82.jpg)

![73bdc15bba833f3c88d7bce0121e1d1eda7ed5cec78a6846d89257bf642f30c0.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/images/73bdc15bba833f3c88d7bce0121e1d1eda7ed5cec78a6846d89257bf642f30c0.jpg)

![7b4cb42ba75147f2f92e23dc08a51d159c367023a5bcb37b6686bb8dab040287.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/images/7b4cb42ba75147f2f92e23dc08a51d159c367023a5bcb37b6686bb8dab040287.jpg)

![7de762c3ea2f05d0ff78202437b878a920a7fa239f9ac8b52e20418e9d066310.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/images/7de762c3ea2f05d0ff78202437b878a920a7fa239f9ac8b52e20418e9d066310.jpg)

![98d225da7d7067d7f620b882ee846d268e6e64f83cb8c2696c26468b83c45b9e.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/images/98d225da7d7067d7f620b882ee846d268e6e64f83cb8c2696c26468b83c45b9e.jpg)

![d232227f79c30060c41310291c1a2b78ff9a97ad00a2530207e364102f3b2607.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/images/d232227f79c30060c41310291c1a2b78ff9a97ad00a2530207e364102f3b2607.jpg)

![fcc92ca4a270c1aeefbd5e42a1936a7a993054eea565d58595011da91d587e3f.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/images/fcc92ca4a270c1aeefbd5e42a1936a7a993054eea565d58595011da91d587e3f.jpg)

### Tables

![05305a60a1509d15fe26696076c725e1fbe72b35457ea4afabc98226b98fd656.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/05305a60a1509d15fe26696076c725e1fbe72b35457ea4afabc98226b98fd656.jpg)

![09021443378aa7d42315c0c0a1bcd7caf18e7bdefa51c7781219a241a02adea9.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/09021443378aa7d42315c0c0a1bcd7caf18e7bdefa51c7781219a241a02adea9.jpg)

![18a9276bfcf684f425729e86b2afc86c1c9542bda249f6c55c8bc2248803e4a3.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/18a9276bfcf684f425729e86b2afc86c1c9542bda249f6c55c8bc2248803e4a3.jpg)

![30baf2a2d5e5d44c0b2b90632b762652a052cbb3102988118d57aebc92aefcba.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/30baf2a2d5e5d44c0b2b90632b762652a052cbb3102988118d57aebc92aefcba.jpg)

![3a5723b8e14d95536c47e0ef9cf43e698f897740fc56c55b0b5198d15d6488bd.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/3a5723b8e14d95536c47e0ef9cf43e698f897740fc56c55b0b5198d15d6488bd.jpg)

![523207b885aa7b2a66d17e1529623959f2d1f289448089a6f2996d2269251034.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/523207b885aa7b2a66d17e1529623959f2d1f289448089a6f2996d2269251034.jpg)

![5dc1131b7c49fcc2a69f4e7ce50cbb5c717fce24b254a29fee5b61fef9d3f0e2.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/5dc1131b7c49fcc2a69f4e7ce50cbb5c717fce24b254a29fee5b61fef9d3f0e2.jpg)

![75b0e45f60ac183e59168eb5466a42cb8deb59291c98c4ec25a4f67f6d1dc221.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/75b0e45f60ac183e59168eb5466a42cb8deb59291c98c4ec25a4f67f6d1dc221.jpg)

![7dbc74b0361efdfdd123411e50db0827f985636450a0393162693bd8f848c705.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/7dbc74b0361efdfdd123411e50db0827f985636450a0393162693bd8f848c705.jpg)

![8141026d782a4e4b5b3d41c5e10446a2ea1cfe016fab454d16e493fc1b253555.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/8141026d782a4e4b5b3d41c5e10446a2ea1cfe016fab454d16e493fc1b253555.jpg)

![861258f507eddf57467a6747de8c110b6693bf9296b55bbe5e841f3769baafcd.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/861258f507eddf57467a6747de8c110b6693bf9296b55bbe5e841f3769baafcd.jpg)

![c217252186b839d37b41b7dd6d5fbef8565f366c190b718206ab0ed5ab44b0ce.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/c217252186b839d37b41b7dd6d5fbef8565f366c190b718206ab0ed5ab44b0ce.jpg)

![d4503cb4219358a3dcd4944f410a8692f75a9a2facb6026e25c02c947ee64461.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/d4503cb4219358a3dcd4944f410a8692f75a9a2facb6026e25c02c947ee64461.jpg)

![ec8a629733b38eca50eb0b4d29b894e794f49b38383031de798d613512ccd0e9.jpg](../nips_results/4635_Inference-Time%20Hyper-Scaling%20with%20KV%20Cache%20Compression/tables/ec8a629733b38eca50eb0b4d29b894e794f49b38383031de798d613512ccd0e9.jpg)

## AdaMSS: Adaptive Multi-Subspace Approach for Parameter-Efficient Fine-Tuning


### Images

![0041e5a81032c1ea7948f38bd284c5d4d1f49eb756dfb9cd46491713044b09c2.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/images/0041e5a81032c1ea7948f38bd284c5d4d1f49eb756dfb9cd46491713044b09c2.jpg)

![1eff6add1c77ebbab24ae322a336fd2b993e9438aa2927cd2dcd20ee4811afe0.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/images/1eff6add1c77ebbab24ae322a336fd2b993e9438aa2927cd2dcd20ee4811afe0.jpg)

![24323d20d9bdfa4aebc81833673706c9d08451c53833ebcc24e5e47d7fea703f.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/images/24323d20d9bdfa4aebc81833673706c9d08451c53833ebcc24e5e47d7fea703f.jpg)

![643c598bac5ee18a557676472cb3eb48df8807428403ae2e60bb5afe3825f9e0.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/images/643c598bac5ee18a557676472cb3eb48df8807428403ae2e60bb5afe3825f9e0.jpg)

![6f1f67bb0b0512fb889b1011aeaa20034b4d39e7a3c497af19a77a2fac999df1.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/images/6f1f67bb0b0512fb889b1011aeaa20034b4d39e7a3c497af19a77a2fac999df1.jpg)

![7425e0d154b12e19fdf93ad3c350898bfc72c25b919809d960507e152d2618fb.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/images/7425e0d154b12e19fdf93ad3c350898bfc72c25b919809d960507e152d2618fb.jpg)

![94c30d8b05f6ccb7096a321eebc9099a13ae8f8c05d4a6d629c30fbb92c76bd7.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/images/94c30d8b05f6ccb7096a321eebc9099a13ae8f8c05d4a6d629c30fbb92c76bd7.jpg)

### Tables

![0612db8f3ac6dc20cc46d9861404fb05e83cbb9b650fa513f79f5987e47414d0.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/0612db8f3ac6dc20cc46d9861404fb05e83cbb9b650fa513f79f5987e47414d0.jpg)

![09e7a6f09b4329df87fc30e143d0099b0cb7c322656c4d9924cdf89c03faf377.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/09e7a6f09b4329df87fc30e143d0099b0cb7c322656c4d9924cdf89c03faf377.jpg)

![0f0bab8d3ace01e6b64f8ab039a720b53b60a754a81f010dd34763ba7c4265df.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/0f0bab8d3ace01e6b64f8ab039a720b53b60a754a81f010dd34763ba7c4265df.jpg)

![1a9aa9773c7c9c274fb54aa5216ae16d0ca77f11eaf9c82e836311eb14dddf4c.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/1a9aa9773c7c9c274fb54aa5216ae16d0ca77f11eaf9c82e836311eb14dddf4c.jpg)

![1e73ab3558484d883fbd5a7172e5199e4155e0bf7301f2d28b7c436d9d2a9fb4.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/1e73ab3558484d883fbd5a7172e5199e4155e0bf7301f2d28b7c436d9d2a9fb4.jpg)

![205991a46157cf3e47883c63a0b63107f53e9ce7e59e484e84de42f47a207de9.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/205991a46157cf3e47883c63a0b63107f53e9ce7e59e484e84de42f47a207de9.jpg)

![243656b41e53ac050bdf993852d5aa33a2ef06c5afdc58784c9db23564300327.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/243656b41e53ac050bdf993852d5aa33a2ef06c5afdc58784c9db23564300327.jpg)

![2b40fbdef10a0619ed0828996ccc0b4848621a07feac6080e36071b8579d903b.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/2b40fbdef10a0619ed0828996ccc0b4848621a07feac6080e36071b8579d903b.jpg)

![578320e397c2a5953bbf1e42dfd3893a4d0d699f53f9a01012a20dd2d5f46764.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/578320e397c2a5953bbf1e42dfd3893a4d0d699f53f9a01012a20dd2d5f46764.jpg)

![6070a4bc4f3147c56cef61076efd64dd6af352801a96a26e4c21724a4037f00d.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/6070a4bc4f3147c56cef61076efd64dd6af352801a96a26e4c21724a4037f00d.jpg)

![63eac6da907ba70575c0a347e7a9196ce6f6158438d0d88a76b68c4fdcb4704e.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/63eac6da907ba70575c0a347e7a9196ce6f6158438d0d88a76b68c4fdcb4704e.jpg)

![70f0c8b873d2b418303b4804186f0680073937a2181cf7866a2a78dd6beadd34.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/70f0c8b873d2b418303b4804186f0680073937a2181cf7866a2a78dd6beadd34.jpg)

![95e7f989759a5e9dadefd200169ea09073e30514eaf9e00ed877265910c65606.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/95e7f989759a5e9dadefd200169ea09073e30514eaf9e00ed877265910c65606.jpg)

![9ba4c055109c6dde1f0581ad641c44580377aa8425402ec114f646212fa8a10f.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/9ba4c055109c6dde1f0581ad641c44580377aa8425402ec114f646212fa8a10f.jpg)

![9fc5290cae03d939ecf061f562ad4ce69767683fed02bb3c7ae4115e79edff77.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/9fc5290cae03d939ecf061f562ad4ce69767683fed02bb3c7ae4115e79edff77.jpg)

![a6b10cdbaecbd7e08991d0ed0373b36a33d44029932af10180be27a2f7836fcd.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/a6b10cdbaecbd7e08991d0ed0373b36a33d44029932af10180be27a2f7836fcd.jpg)

![ab32a5e3db871cccde381bb7e7808b7db823f60dd5c42ea0895cfb7caa732e13.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/ab32a5e3db871cccde381bb7e7808b7db823f60dd5c42ea0895cfb7caa732e13.jpg)

![ae8cfd775691d6594040aa451d58a7d6e88d647f12f9a1ae4ad035b26eec2341.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/ae8cfd775691d6594040aa451d58a7d6e88d647f12f9a1ae4ad035b26eec2341.jpg)

![b01162f52b80af4dbb12ae63356f448a18c316256645491dace4224b74903db0.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/b01162f52b80af4dbb12ae63356f448a18c316256645491dace4224b74903db0.jpg)

![b3ce0be9753ec0ab71c6893c5b0181770de05134e803f76f68d04590e498a1ee.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/b3ce0be9753ec0ab71c6893c5b0181770de05134e803f76f68d04590e498a1ee.jpg)

![b5a01935d7c1bbcf0f727f90130e83c9adffcdeab7b2db78cfc3dcb9d3d023ef.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/b5a01935d7c1bbcf0f727f90130e83c9adffcdeab7b2db78cfc3dcb9d3d023ef.jpg)

![bd4cbc58664d5753481b18ebae5f057d979c8dba835b66a6fc46a5f390e47ddf.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/bd4cbc58664d5753481b18ebae5f057d979c8dba835b66a6fc46a5f390e47ddf.jpg)

![e7deb64d0ae5a1a0a86759f70d1421d9f4a90d3920118e7d36f525535a2472bc.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/e7deb64d0ae5a1a0a86759f70d1421d9f4a90d3920118e7d36f525535a2472bc.jpg)

![f7a98bd97efb590bcfb377970e6015d823edf7f64c9a6fc66485d7295e2c1b91.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/f7a98bd97efb590bcfb377970e6015d823edf7f64c9a6fc66485d7295e2c1b91.jpg)

![f7babaa213d3a388a6e5e0edfbd2b879bac816cf3b25b20819f302cffd5f06d4.jpg](../nips_results/4636_AdaMSS_%20Adaptive%20Multi-Subspace%20Approach%20for%20Parameter-Efficient%20Fine-Tuning/tables/f7babaa213d3a388a6e5e0edfbd2b879bac816cf3b25b20819f302cffd5f06d4.jpg)

## JAMUN: Bridging Smoothed Molecular Dynamics and Score-Based Learning for Conformational Ensemble Generation


### Images

![0449d6d96fe906a5df9f9c4a3a38b951c3c08360296ab97024510170284f8481.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/0449d6d96fe906a5df9f9c4a3a38b951c3c08360296ab97024510170284f8481.jpg)

![146ff82745d3d60b07992a122e05a8debf2ed4f84511f4fcc85aae17a98f1413.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/146ff82745d3d60b07992a122e05a8debf2ed4f84511f4fcc85aae17a98f1413.jpg)

![17d7544fd312fff0c4cdc6893394a003b9c9570c9b2ef55ded865e21cd46a8b4.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/17d7544fd312fff0c4cdc6893394a003b9c9570c9b2ef55ded865e21cd46a8b4.jpg)

![1a9c3b0752e8bad8a7d7a00becacde8ce4aa73da4b415748dafa9b96c60f7808.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/1a9c3b0752e8bad8a7d7a00becacde8ce4aa73da4b415748dafa9b96c60f7808.jpg)

![27d595fdf1a3cccea5903fbc3d995a0b76d6da0f4872d2ebfcd0862aef44ff71.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/27d595fdf1a3cccea5903fbc3d995a0b76d6da0f4872d2ebfcd0862aef44ff71.jpg)

![2e912e8954b882d21e4119cd7be88850fed773ff9fe75e034e850849e15ba7b1.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/2e912e8954b882d21e4119cd7be88850fed773ff9fe75e034e850849e15ba7b1.jpg)

![33860923fd93cbb8592e82d1878107c5ce1137a7af187dc615dacc1dcf49a297.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/33860923fd93cbb8592e82d1878107c5ce1137a7af187dc615dacc1dcf49a297.jpg)

![4df1bf54d2c136be991f44093c3bb53869cea85f97e4302852fafacd1b49f0f2.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/4df1bf54d2c136be991f44093c3bb53869cea85f97e4302852fafacd1b49f0f2.jpg)

![76b0c94202320c33327d33427e02d1f77c951588e7e08954872c15ca3d7d962b.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/76b0c94202320c33327d33427e02d1f77c951588e7e08954872c15ca3d7d962b.jpg)

![7f0b307b582bbab4d857963e4eb2976b23a48084d2b73e49316938148d94c34b.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/7f0b307b582bbab4d857963e4eb2976b23a48084d2b73e49316938148d94c34b.jpg)

![8a437bd68ecb045e4f074051ab20e0df3de1f83fdc9c5d821c552272fa7779a9.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/8a437bd68ecb045e4f074051ab20e0df3de1f83fdc9c5d821c552272fa7779a9.jpg)

![8d6c746f787e2144a58b906314c0f0d55c1bc0a6f66d1dbfd57629530d7b8c37.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/8d6c746f787e2144a58b906314c0f0d55c1bc0a6f66d1dbfd57629530d7b8c37.jpg)

![9d52408098b1f84a7a6a22222d5dec028f7bdf185afca0dd1fc5843546e9de0d.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/9d52408098b1f84a7a6a22222d5dec028f7bdf185afca0dd1fc5843546e9de0d.jpg)

![aa9eb6663b0d7e3853ffa173c6f1308f2de94f3da612c76c47d6c71e824f91a0.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/aa9eb6663b0d7e3853ffa173c6f1308f2de94f3da612c76c47d6c71e824f91a0.jpg)

![da52a9e222cc41abed2882a9e3933e8ec6005d6749ab9f60ac0b2b197cc8eb64.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/images/da52a9e222cc41abed2882a9e3933e8ec6005d6749ab9f60ac0b2b197cc8eb64.jpg)

### Tables

![28a989d183f08f323ffa6e780c49fc8f371541275d2de4ca167e50fc845d1c38.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/tables/28a989d183f08f323ffa6e780c49fc8f371541275d2de4ca167e50fc845d1c38.jpg)

![3496e76ed717fc527d027b8c7caee4c4102704c2724c3f8659b009c08ebcc35a.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/tables/3496e76ed717fc527d027b8c7caee4c4102704c2724c3f8659b009c08ebcc35a.jpg)

![547e336c7091fa1e3da3c201e3aeda810f2843fda4472310778cfb743dd876cc.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/tables/547e336c7091fa1e3da3c201e3aeda810f2843fda4472310778cfb743dd876cc.jpg)

![5a92394d397bfb8ff78315aa97c6107fc4274c4039ac1bed81d5d9479399f3d7.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/tables/5a92394d397bfb8ff78315aa97c6107fc4274c4039ac1bed81d5d9479399f3d7.jpg)

![81f2e90ff4ccd2021cc1d9afd3286fa1922a258acfca56e315478f43490b1119.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/tables/81f2e90ff4ccd2021cc1d9afd3286fa1922a258acfca56e315478f43490b1119.jpg)

![b68d9a75713728f9bf11e728a44c579919fe04025d9ec64f9676b292b40f2b58.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/tables/b68d9a75713728f9bf11e728a44c579919fe04025d9ec64f9676b292b40f2b58.jpg)

![bd30c5ea8b9a161618f8b62aeaf2cabcf85b477820c9b8756245513feab77e53.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/tables/bd30c5ea8b9a161618f8b62aeaf2cabcf85b477820c9b8756245513feab77e53.jpg)

![ea4e00eb842a317076cd00595eb641e0dbca836f6a461bacd96b16c5007912d1.jpg](../nips_results/4637_JAMUN_%20Bridging%20Smoothed%20Molecular%20Dynamics%20and%20Score-Based%20Learning%20for%20Conformational%20Ensemble%20Gen/tables/ea4e00eb842a317076cd00595eb641e0dbca836f6a461bacd96b16c5007912d1.jpg)

## Detecting High-Stakes Interactions with Activation Probes


### Images

![062c1e0fc32a11ad734886cff09ae5f7112496daf6cb3b7dfe99c93ea3dd758b.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/062c1e0fc32a11ad734886cff09ae5f7112496daf6cb3b7dfe99c93ea3dd758b.jpg)

![093d3afe5e76639643f29f73094649d5f7ea9d83f1ebd818837caef7a9706b8a.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/093d3afe5e76639643f29f73094649d5f7ea9d83f1ebd818837caef7a9706b8a.jpg)

![1cc79162ebf160e40771a0f74dab432283c9a704b74e2619e4b9f518147a9a3b.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/1cc79162ebf160e40771a0f74dab432283c9a704b74e2619e4b9f518147a9a3b.jpg)

![2a34558bb850eac0feea871e6555510fd14d58e65cc9ea001e70cbc808e35b14.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/2a34558bb850eac0feea871e6555510fd14d58e65cc9ea001e70cbc808e35b14.jpg)

![2f8f0c04eca0045dd56aee967a571e605076c473fc90bfe3ee809df1d3077f43.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/2f8f0c04eca0045dd56aee967a571e605076c473fc90bfe3ee809df1d3077f43.jpg)

![3e7f92497389efd32e3e54b33dcc47856bbd0b937cd660f08bea1a44894e6e43.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/3e7f92497389efd32e3e54b33dcc47856bbd0b937cd660f08bea1a44894e6e43.jpg)

![5699fd3451c1161b5c8434df7bc0a819e0f78586f9126d906bafdcc1880b34b5.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/5699fd3451c1161b5c8434df7bc0a819e0f78586f9126d906bafdcc1880b34b5.jpg)

![6042c012f78a1ba5355c9d16338ddd6dd8e3514e336b3f66c5471244a6e76b38.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/6042c012f78a1ba5355c9d16338ddd6dd8e3514e336b3f66c5471244a6e76b38.jpg)

![63e8c634e9538ee6f7da3d87171bbb8005ca3b3a232c66e4b801bfd33e37d9c3.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/63e8c634e9538ee6f7da3d87171bbb8005ca3b3a232c66e4b801bfd33e37d9c3.jpg)

![84f248d1efc926a48896b337d1cc1f7134cd7c24e2267534919bfc5cef13eaae.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/84f248d1efc926a48896b337d1cc1f7134cd7c24e2267534919bfc5cef13eaae.jpg)

![a09600d5f302ffd298182ca8e1ba703ac470213ec80097e58f973d4b19042b8a.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/a09600d5f302ffd298182ca8e1ba703ac470213ec80097e58f973d4b19042b8a.jpg)

![b0c3df7f14a544ee25b732bb44842d9666aeb572c0ec7f48e1a2aabca3a1dfc2.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/b0c3df7f14a544ee25b732bb44842d9666aeb572c0ec7f48e1a2aabca3a1dfc2.jpg)

![c2b6d717f18e6c81d76715809557574c643d648c9417b3a880a17d06d052331b.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/c2b6d717f18e6c81d76715809557574c643d648c9417b3a880a17d06d052331b.jpg)

![cff1057694f3fe92ed93a9f2797bebeec4ca9815c66f3bfcc2552ee907dcbd11.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/cff1057694f3fe92ed93a9f2797bebeec4ca9815c66f3bfcc2552ee907dcbd11.jpg)

![d390e1734984c83de9a624ac4295c27884a2ffb74aaaa8ab7f0f3360ff9bfd17.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/d390e1734984c83de9a624ac4295c27884a2ffb74aaaa8ab7f0f3360ff9bfd17.jpg)

![d4d4b1423891210f7a63ac3364502369ac590344f22cc40af6d277044a4c417a.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/d4d4b1423891210f7a63ac3364502369ac590344f22cc40af6d277044a4c417a.jpg)

![f077282b9a0b0b5514613da8e63ff44fe08a8eba0c7589992235f01ea94142ac.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/f077282b9a0b0b5514613da8e63ff44fe08a8eba0c7589992235f01ea94142ac.jpg)

![f62f0d2deb69262a14911764cebdda21338e14eb358e9f792c22fff0acef5acf.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/f62f0d2deb69262a14911764cebdda21338e14eb358e9f792c22fff0acef5acf.jpg)

![f76e3d9d938733bb822b44164c60ee1b9a387b317f17f9235377dca6039f48a3.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/f76e3d9d938733bb822b44164c60ee1b9a387b317f17f9235377dca6039f48a3.jpg)

![f96abc1c1a5fe3824f8a1d5ef09c83a5cc4e9074673c214e71b5b9c51bd31b70.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/images/f96abc1c1a5fe3824f8a1d5ef09c83a5cc4e9074673c214e71b5b9c51bd31b70.jpg)

### Tables

![185720d50fe1fcab42dad44f3bba94670a52cd57393ec43dc6e348a24723a729.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/185720d50fe1fcab42dad44f3bba94670a52cd57393ec43dc6e348a24723a729.jpg)

![20637cd19465fc618620c04cf102c79c4f342d29085b5355017417c7a239ce5e.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/20637cd19465fc618620c04cf102c79c4f342d29085b5355017417c7a239ce5e.jpg)

![353aa1f42aa7e96e913f84add28614c87875f4caeddf6c48d2c5f7545bc10594.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/353aa1f42aa7e96e913f84add28614c87875f4caeddf6c48d2c5f7545bc10594.jpg)

![633a0880aac8fa981a08acdd32d8d2073d67ac5568aab11b7c8549692f1d8837.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/633a0880aac8fa981a08acdd32d8d2073d67ac5568aab11b7c8549692f1d8837.jpg)

![802ad226699642b35d94ae818ef178d0456cfa8107ab4f0f5bfcf8e94fbf0fc1.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/802ad226699642b35d94ae818ef178d0456cfa8107ab4f0f5bfcf8e94fbf0fc1.jpg)

![80ff4c1fd0e60e3632af3157a79d6fbfe62aec3d78e2ba5e33c046c306396466.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/80ff4c1fd0e60e3632af3157a79d6fbfe62aec3d78e2ba5e33c046c306396466.jpg)

![82e6d873aaf0b82bd75ac38033c6cf9884cb4da24683100c6474303a71ee6e20.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/82e6d873aaf0b82bd75ac38033c6cf9884cb4da24683100c6474303a71ee6e20.jpg)

![9618bdd1725388441392f3f82a16dd4771caf0b1ce0a2c9d5685af4c8c72f595.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/9618bdd1725388441392f3f82a16dd4771caf0b1ce0a2c9d5685af4c8c72f595.jpg)

![a458d8c4af3e1387d5893f1e4ddf97335477830661e353b278384a76c0e4d68d.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/a458d8c4af3e1387d5893f1e4ddf97335477830661e353b278384a76c0e4d68d.jpg)

![bb6ced23d525018a4a7e510c460a0348488335236610fb211bc4bdad03509a6e.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/bb6ced23d525018a4a7e510c460a0348488335236610fb211bc4bdad03509a6e.jpg)

![bf104461614ab58f292c4fa90625f029387af2fae716e8e36751402c5bc0759c.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/bf104461614ab58f292c4fa90625f029387af2fae716e8e36751402c5bc0759c.jpg)

![c73210843ef87cc07326fafdcedb27851b2aa901d8ece67c750b833693987b62.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/c73210843ef87cc07326fafdcedb27851b2aa901d8ece67c750b833693987b62.jpg)

![cd7fc466be3f77d2a0845e6be6892fdd510aa352072088ab86b45acf419f6cc0.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/cd7fc466be3f77d2a0845e6be6892fdd510aa352072088ab86b45acf419f6cc0.jpg)

![d594707a8c9944246159340023eddb2fe84cc24759c43121aecede80416f7587.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/d594707a8c9944246159340023eddb2fe84cc24759c43121aecede80416f7587.jpg)

![de8be100ea894b27b3ba86febeb7c37812b7f863f117d507b387def99c3fa087.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/de8be100ea894b27b3ba86febeb7c37812b7f863f117d507b387def99c3fa087.jpg)

![e6e73be36f1610cf7f66f3aab156e4e34ea8db93864daf32d7ffa9ba33674749.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/e6e73be36f1610cf7f66f3aab156e4e34ea8db93864daf32d7ffa9ba33674749.jpg)

![f76ac8bb9fbef5d0fb899d81b4a8f579a53b98935d19fd00b25ffdb80a157fda.jpg](../nips_results/4638_Detecting%20High-Stakes%20Interactions%20with%20Activation%20Probes/tables/f76ac8bb9fbef5d0fb899d81b4a8f579a53b98935d19fd00b25ffdb80a157fda.jpg)

## Neural Tangent Knowledge Distillation for Optical Convolutional Networks

### Images

![34fe9f25423418579447d53eea22dec85e00df0f52174b6febb20c7cff04b538.jpg](../nips_results/4639_Neural%20Tangent%20Knowledge%20Distillation%20for%20Optical%20Convolutional%20Networks/images/34fe9f25423418579447d53eea22dec85e00df0f52174b6febb20c7cff04b538.jpg)

![35d87d061a2f352e99e77fd0a83968fcba0ea6d3fd0a376eb630a62906b18e40.jpg](../nips_results/4639_Neural%20Tangent%20Knowledge%20Distillation%20for%20Optical%20Convolutional%20Networks/images/35d87d061a2f352e99e77fd0a83968fcba0ea6d3fd0a376eb630a62906b18e40.jpg)

![9c53d94e0a21b327a09d44ebfc1cd820151ff10d445c18dae8da537cc470da82.jpg](../nips_results/4639_Neural%20Tangent%20Knowledge%20Distillation%20for%20Optical%20Convolutional%20Networks/images/9c53d94e0a21b327a09d44ebfc1cd820151ff10d445c18dae8da537cc470da82.jpg)

![b744b9c6e5b93e14dfaec4ce1c09bf5d4cc0b8710f0773891c02a10ace888679.jpg](../nips_results/4639_Neural%20Tangent%20Knowledge%20Distillation%20for%20Optical%20Convolutional%20Networks/images/b744b9c6e5b93e14dfaec4ce1c09bf5d4cc0b8710f0773891c02a10ace888679.jpg)

![f6f91d7ec9826948f94c381fc9969b715827bae3434012a87ecc9d0fda89b180.jpg](../nips_results/4639_Neural%20Tangent%20Knowledge%20Distillation%20for%20Optical%20Convolutional%20Networks/images/f6f91d7ec9826948f94c381fc9969b715827bae3434012a87ecc9d0fda89b180.jpg)

### Tables

![121904fa3c035240b407f88e52e1ce624adb3c026b41b037a1e5880d33a4d2fb.jpg](../nips_results/4639_Neural%20Tangent%20Knowledge%20Distillation%20for%20Optical%20Convolutional%20Networks/tables/121904fa3c035240b407f88e52e1ce624adb3c026b41b037a1e5880d33a4d2fb.jpg)

![5d2eb86d60026a507559809b12df9d6946d48979a7246578d661e836a84ea2f7.jpg](../nips_results/4639_Neural%20Tangent%20Knowledge%20Distillation%20for%20Optical%20Convolutional%20Networks/tables/5d2eb86d60026a507559809b12df9d6946d48979a7246578d661e836a84ea2f7.jpg)

![7021a741cfd15b05ae0f091e6e8c9968351c1ec93fb9e38d0a8973f47198c808.jpg](../nips_results/4639_Neural%20Tangent%20Knowledge%20Distillation%20for%20Optical%20Convolutional%20Networks/tables/7021a741cfd15b05ae0f091e6e8c9968351c1ec93fb9e38d0a8973f47198c808.jpg)

![b0b712db3e410f065cc94758cd9ded435cca7eb3fe4643f17d5a71d51352ba0a.jpg](../nips_results/4639_Neural%20Tangent%20Knowledge%20Distillation%20for%20Optical%20Convolutional%20Networks/tables/b0b712db3e410f065cc94758cd9ded435cca7eb3fe4643f17d5a71d51352ba0a.jpg)

![c6ccc8266dfb0435c3ee01af6545774611642220c1e28631d73eec48432fe059.jpg](../nips_results/4639_Neural%20Tangent%20Knowledge%20Distillation%20for%20Optical%20Convolutional%20Networks/tables/c6ccc8266dfb0435c3ee01af6545774611642220c1e28631d73eec48432fe059.jpg)

![ffcca70af5ad67c5d6fcfc3391a8a491a810d3d259bf126c1dc94073bd4598dc.jpg](../nips_results/4639_Neural%20Tangent%20Knowledge%20Distillation%20for%20Optical%20Convolutional%20Networks/tables/ffcca70af5ad67c5d6fcfc3391a8a491a810d3d259bf126c1dc94073bd4598dc.jpg)
