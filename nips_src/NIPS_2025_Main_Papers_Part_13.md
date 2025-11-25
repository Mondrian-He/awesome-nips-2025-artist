# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 13 of 130

## 目录 (Table of Contents)

1. [3D Interaction Geometric Pre-training for Molecular Relational Learning](#3D-Interaction-Geometric-Pre-training-for-Molecular-Relational-Learning)
2. [Seeing Sound, Hearing Sight: Uncovering Modality Bias and Conflict of AI models in Sound Localization](#Seeing-Sound-Hearing-Sight-Uncovering-Modality-Bias-and-Conflict-of-AI-models-in-Sound-Localization)
3. [SoTA with Less: MCTS-Guided Sample Selection for Data-Efficient Visual Reasoning Self-Improvement](#SoTA-with-Less-MCTS-Guided-Sample-Selection-for-Data-Efficient-Visual-Reasoning-Self-Improvement)
4. [Jacobian-Based Interpretation of Nonlinear Neural Encoding Model](#Jacobian-Based-Interpretation-of-Nonlinear-Neural-Encoding-Model)
5. [ARECHO: Autoregressive Evaluation via Chain-Based Hypothesis Optimization for Speech Multi-Metric Estimation](#ARECHO-Autoregressive-Evaluation-via-Chain-Based-Hypothesis-Optimization-for-Speech-Multi-Metric-Estimation)
6. [Online Strategic Classification With Noise and Partial Feedback](#Online-Strategic-Classification-With-Noise-and-Partial-Feedback)
7. [CoT Information: Improved Sample Complexity under Chain-of-Thought Supervision](#CoT-Information-Improved-Sample-Complexity-under-Chain-of-Thought-Supervision)
8. [What are you sinking? A geometric approach on attention sink](#What-are-you-sinking-A-geometric-approach-on-attention-sink)
9. [Do-PFN: In-Context Learning for Causal Effect Estimation](#Do-PFN-In-Context-Learning-for-Causal-Effect-Estimation)
10. [On the necessity of adaptive regularisation: Optimal anytime online learning on $\boldsymbol{\ell_p}$-balls](#On-the-necessity-of-adaptive-regularisation-Optimal-anytime-online-learning-on-boldsymbolell_p-balls)
11. [An Evidence-Based Post-Hoc Adjustment Framework for Anomaly Detection Under Data Contamination](#An-Evidence-Based-Post-Hoc-Adjustment-Framework-for-Anomaly-Detection-Under-Data-Contamination)
12. [Flow Equivariant Recurrent Neural Networks](#Flow-Equivariant-Recurrent-Neural-Networks)
13. [Transformers for Mixed-type Event Sequences](#Transformers-for-Mixed-type-Event-Sequences)
14. [ZeroS: Zero‑Sum Linear Attention for Efficient Transformers](#ZeroS-ZeroSum-Linear-Attention-for-Efficient-Transformers)
15. [Protein Design with Dynamic Protein Vocabulary](#Protein-Design-with-Dynamic-Protein-Vocabulary)
16. [Privacy amplification by random allocation](#Privacy-amplification-by-random-allocation)
17. [Diffusion-Based Hierarchical Graph Neural Networks for Simulating Nonlinear Solid Mechanics](#Diffusion-Based-Hierarchical-Graph-Neural-Networks-for-Simulating-Nonlinear-Solid-Mechanics)
18. [Uncertain Knowledge Graph Completion via Semi-Supervised Confidence Distribution Learning](#Uncertain-Knowledge-Graph-Completion-via-Semi-Supervised-Confidence-Distribution-Learning)
19. [Lost in Transmission: When and Why LLMs Fail to Reason Globally](#Lost-in-Transmission-When-and-Why-LLMs-Fail-to-Reason-Globally)
20. [JavisGPT: A Unified Multi-modal LLM for Sounding-Video Comprehension and Generation](#JavisGPT-A-Unified-Multi-modal-LLM-for-Sounding-Video-Comprehension-and-Generation)
21. [Ambient Diffusion Omni: Training Good Models with Bad Data](#Ambient-Diffusion-Omni-Training-Good-Models-with-Bad-Data)
22. [Transformer Copilot: Learning from The Mistake Log in LLM Fine-tuning](#Transformer-Copilot-Learning-from-The-Mistake-Log-in-LLM-Fine-tuning)
23. [Fast-Slow Thinking GRPO for Large Vision-Language Model Reasoning](#Fast-Slow-Thinking-GRPO-for-Large-Vision-Language-Model-Reasoning)
24. [CLiFT: Compressive Light-Field Tokens for Compute Efficient and Adaptive Neural Rendering](#CLiFT-Compressive-Light-Field-Tokens-for-Compute-Efficient-and-Adaptive-Neural-Rendering)
25. [Toward Relative Positional Encoding in Spiking Transformers](#Toward-Relative-Positional-Encoding-in-Spiking-Transformers)
26. [Breaking the Batch Barrier (B3) of Contrastive Learning via Smart Batch Mining](#Breaking-the-Batch-Barrier-B3-of-Contrastive-Learning-via-Smart-Batch-Mining)
27. [TRIDENT: Tri-Modal Molecular Representation Learning with Taxonomic Annotations and Local Correspondence](#TRIDENT-Tri-Modal-Molecular-Representation-Learning-with-Taxonomic-Annotations-and-Local-Correspondence)
28. [Vector Quantization in the Brain: Grid-like Codes in World Models](#Vector-Quantization-in-the-Brain-Grid-like-Codes-in-World-Models)
29. [Cycle-Sync: Robust Global Camera Pose Estimation through Enhanced Cycle-Consistent Synchronization](#Cycle-Sync-Robust-Global-Camera-Pose-Estimation-through-Enhanced-Cycle-Consistent-Synchronization)
30. [A Implies B: Circuit Analysis in LLMs for Propositional Logical Reasoning](#A-Implies-B-Circuit-Analysis-in-LLMs-for-Propositional-Logical-Reasoning)
31. [On Traceability in $\ell_p$ Stochastic Convex Optimization](#On-Traceability-in-ell_p-Stochastic-Convex-Optimization)
32. [Vanish into Thin Air: Cross-prompt Universal Adversarial Attacks for SAM2](#Vanish-into-Thin-Air-Cross-prompt-Universal-Adversarial-Attacks-for-SAM2)
33. [EAG3R: Event-Augmented 3D Geometry Estimation for Dynamic and Extreme-Lighting Scenes](#EAG3R-Event-Augmented-3D-Geometry-Estimation-for-Dynamic-and-Extreme-Lighting-Scenes)
34. [A Token is Worth over 1,000 Tokens: Efficient Knowledge Distillation through Low-Rank Clone](#A-Token-is-Worth-over-1000-Tokens-Efficient-Knowledge-Distillation-through-Low-Rank-Clone)
35. [GeoLLaVA-8K: Scaling Remote-Sensing Multimodal Large Language Models to 8K Resolution](#GeoLLaVA-8K-Scaling-Remote-Sensing-Multimodal-Large-Language-Models-to-8K-Resolution)
36. [NormFit: A Lightweight Solution for Few-Shot Federated Learning with Non-IID Data](#NormFit-A-Lightweight-Solution-for-Few-Shot-Federated-Learning-with-Non-IID-Data)
37. [VPO: Reasoning Preferences Optimization Based on $\mathcal{V}$-Usable Information](#VPO-Reasoning-Preferences-Optimization-Based-on-mathcalV-Usable-Information)
38. [GaussianFusion: Gaussian-Based Multi-Sensor Fusion for End-to-End Autonomous Driving](#GaussianFusion-Gaussian-Based-Multi-Sensor-Fusion-for-End-to-End-Autonomous-Driving)
39. [Accelerating Optimization via Differentiable Stopping Time](#Accelerating-Optimization-via-Differentiable-Stopping-Time)
40. [Abstain Mask Retain Core: Time Series Prediction by Adaptive Masking Loss with Representation Consistency](#Abstain-Mask-Retain-Core-Time-Series-Prediction-by-Adaptive-Masking-Loss-with-Representation-Consistency)
41. [Amortized Variational Transdimensional Inference](#Amortized-Variational-Transdimensional-Inference)

---


## 3D Interaction Geometric Pre-training for Molecular Relational Learning

### Images

![0a20d92aeacf16d741ff335ff691d73083c679e5d522fbc3a8b223d8059fd760.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/images/0a20d92aeacf16d741ff335ff691d73083c679e5d522fbc3a8b223d8059fd760.jpg)

![112d17d0515cc22d504099364d5c6f73019d67e78c8bf6b16c138661574dc8e9.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/images/112d17d0515cc22d504099364d5c6f73019d67e78c8bf6b16c138661574dc8e9.jpg)

![6abf6556840cc25b54f43256b3d7eabbe88cb0823f0db77aedda5d60196888d0.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/images/6abf6556840cc25b54f43256b3d7eabbe88cb0823f0db77aedda5d60196888d0.jpg)

![93358e4b34482b4b2f093d9f76dfb51a1a38d364086b25ec910738e321b26bcf.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/images/93358e4b34482b4b2f093d9f76dfb51a1a38d364086b25ec910738e321b26bcf.jpg)

![ac39e240fde25432285dad46051368e438dcf8958d39b0aa96e5e6906aedb185.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/images/ac39e240fde25432285dad46051368e438dcf8958d39b0aa96e5e6906aedb185.jpg)

![dec3993612838a4dc9d6229b6a0683e1d2ef5bb81a01cb37bed031e9d7bc209b.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/images/dec3993612838a4dc9d6229b6a0683e1d2ef5bb81a01cb37bed031e9d7bc209b.jpg)

![fea1dbdecc6a5ff54ee142831a66a97772d019fc61696ed0b0246e14efa9dffa.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/images/fea1dbdecc6a5ff54ee142831a66a97772d019fc61696ed0b0246e14efa9dffa.jpg)

### Tables

![10279bac896c921ab785e2f2b063de80cbb1358ad230414fa802ee6540c4dfe9.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/tables/10279bac896c921ab785e2f2b063de80cbb1358ad230414fa802ee6540c4dfe9.jpg)

![1272ff828e4ffaa31dbb3720c95fb8a39a6c60ab62befb0cb809217f8e775ef6.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/tables/1272ff828e4ffaa31dbb3720c95fb8a39a6c60ab62befb0cb809217f8e775ef6.jpg)

![5a539e419f8c958d496450f1d852f5bf564b0a4af48ecc0b5f9e270985dd2e1c.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/tables/5a539e419f8c958d496450f1d852f5bf564b0a4af48ecc0b5f9e270985dd2e1c.jpg)

![86999fcc6ba6b4b2b4165ef8b9521fc4f51b1e54bdceb894071e91baf3f4f797.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/tables/86999fcc6ba6b4b2b4165ef8b9521fc4f51b1e54bdceb894071e91baf3f4f797.jpg)

![9c6fe6d4a82ce0d711c74c6efc2e7a420c4dd1cf72a3bfbd6ea87eecfd4734f4.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/tables/9c6fe6d4a82ce0d711c74c6efc2e7a420c4dd1cf72a3bfbd6ea87eecfd4734f4.jpg)

![b2f457beda626f1bf3bd35168a16a4419308ceeca863caed75bead27bc7244ca.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/tables/b2f457beda626f1bf3bd35168a16a4419308ceeca863caed75bead27bc7244ca.jpg)

![bb7f37dbcb06591638688d3d28955c0daaeb74535f6ef2060a31b4d0be8767d7.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/tables/bb7f37dbcb06591638688d3d28955c0daaeb74535f6ef2060a31b4d0be8767d7.jpg)

![dc7113eebf97817395a80b1e23057ec5aec44ebdc9fba6abf8e57db1356f8af6.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/tables/dc7113eebf97817395a80b1e23057ec5aec44ebdc9fba6abf8e57db1356f8af6.jpg)

![f9aa943cbdd03903726656998c0be248da095c6c2a4b08ad612b890a09cb54cb.jpg](../nips_results/503_Can%20We%20Infer%20Confidential%20Properties%20of%20Training%20Data%20from%20LLMs_/tables/f9aa943cbdd03903726656998c0be248da095c6c2a4b08ad612b890a09cb54cb.jpg)

## 3D Interaction Geometric Pre-training for Molecular Relational Learning


### Images

![1a4d6d0fc3a7c81cc43328a02e6e94d27d22aa125f6f8caefb096c76ea0064e3.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/images/1a4d6d0fc3a7c81cc43328a02e6e94d27d22aa125f6f8caefb096c76ea0064e3.jpg)

![58928101d77fa3d191333acfaa5479629495363bcea673a73f81c50ee7a3b9cc.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/images/58928101d77fa3d191333acfaa5479629495363bcea673a73f81c50ee7a3b9cc.jpg)

![5ad26a9edea51d6a293ff2c898bdc1a151e10ade5a6a9eb9dbf9ac7ca7612674.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/images/5ad26a9edea51d6a293ff2c898bdc1a151e10ade5a6a9eb9dbf9ac7ca7612674.jpg)

![83a8eaca0dfa5c1c767cf45d51dcd59e0847b56fa3746d382df02fe2c7f8dc8f.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/images/83a8eaca0dfa5c1c767cf45d51dcd59e0847b56fa3746d382df02fe2c7f8dc8f.jpg)

![c392066b0efdd376d6abeff713dc9b33ff01afb924f8615383d86f1dc4eac364.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/images/c392066b0efdd376d6abeff713dc9b33ff01afb924f8615383d86f1dc4eac364.jpg)

![de31932b7b873cd9908790ae4a5583e01baf1864f6b7e2c48d46baf960ade10c.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/images/de31932b7b873cd9908790ae4a5583e01baf1864f6b7e2c48d46baf960ade10c.jpg)

### Tables

![0a293cda475bd8115c3530b9f72c7d75a0963add6c3c1c07a4b7f3f9416eb4f7.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/tables/0a293cda475bd8115c3530b9f72c7d75a0963add6c3c1c07a4b7f3f9416eb4f7.jpg)

![1797626e563273c8e720bb0ebc5702e5073d36b203058cf17b3ebaedd9a2db55.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/tables/1797626e563273c8e720bb0ebc5702e5073d36b203058cf17b3ebaedd9a2db55.jpg)

![3c79805edf342580c9028021aead1616759d7c06b81abf5f35d8ecf7cf496549.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/tables/3c79805edf342580c9028021aead1616759d7c06b81abf5f35d8ecf7cf496549.jpg)

![6cf12d3ee1e47bc175bc2305d04c5ca769157dba7dceac9c44e2eae5265cedbc.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/tables/6cf12d3ee1e47bc175bc2305d04c5ca769157dba7dceac9c44e2eae5265cedbc.jpg)

![78978f0e8f89dca6076224d1486cb75cfeb8010627fb6a6d95484d5fe21d128c.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/tables/78978f0e8f89dca6076224d1486cb75cfeb8010627fb6a6d95484d5fe21d128c.jpg)

![87b06cfc6e27f432994da6519ad8b567446361f6d52fa6868dcd78d238146543.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/tables/87b06cfc6e27f432994da6519ad8b567446361f6d52fa6868dcd78d238146543.jpg)

![c54eaad3c8005c8cc553e87cc7c21907b5907160fa9317cf01029f7801423ef9.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/tables/c54eaad3c8005c8cc553e87cc7c21907b5907160fa9317cf01029f7801423ef9.jpg)

![cba3454b69d73e9ba1a5b20dea14aecb27987f7236067412904cca6bf96fa480.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/tables/cba3454b69d73e9ba1a5b20dea14aecb27987f7236067412904cca6bf96fa480.jpg)

![f73a33e72deb24268c0f8432cbcabb3bce9292a7afdc5808247c6f32e8daf2cd.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/tables/f73a33e72deb24268c0f8432cbcabb3bce9292a7afdc5808247c6f32e8daf2cd.jpg)

![f8cf48c98248ab138b0f1b609a282520dabe1674b37bc83cdc4d83e6bccfc941.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/tables/f8cf48c98248ab138b0f1b609a282520dabe1674b37bc83cdc4d83e6bccfc941.jpg)

![f9226fd43ee905b717472f7008c644ce5773960ce9d55dbf1827abede38155e9.jpg](../nips_results/504_3D%20Interaction%20Geometric%20Pre-training%20for%20Molecular%20Relational%20Learning/tables/f9226fd43ee905b717472f7008c644ce5773960ce9d55dbf1827abede38155e9.jpg)

## Seeing Sound, Hearing Sight: Uncovering Modality Bias and Conflict of AI models in Sound Localization


### Images

![008cc44e988708d3cc7be1ea97717b320d99d7b593325927e9126915ff0812f9.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/008cc44e988708d3cc7be1ea97717b320d99d7b593325927e9126915ff0812f9.jpg)

![0dfb0534301e95cf9eb0c123c485c99c152b168d7196426664a9aa87bd7ce7ad.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/0dfb0534301e95cf9eb0c123c485c99c152b168d7196426664a9aa87bd7ce7ad.jpg)

![489ec23a30a58a76370475721cfd3266bea50f70a3c325c05c4e341ecdc191f2.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/489ec23a30a58a76370475721cfd3266bea50f70a3c325c05c4e341ecdc191f2.jpg)

![5f4434d6a6316c6b0ad69aa86c0e15f1e3bde5eadcccdd1fc1651f6d3aa62532.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/5f4434d6a6316c6b0ad69aa86c0e15f1e3bde5eadcccdd1fc1651f6d3aa62532.jpg)

![60c6aaf5f8417597efd132eb51b3a061374748f42203b009e808cc758ba43ceb.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/60c6aaf5f8417597efd132eb51b3a061374748f42203b009e808cc758ba43ceb.jpg)

![69702c13bfb4252c20e6af8d06054e2a3ae1a11b0244cb30734f788a0eb06fba.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/69702c13bfb4252c20e6af8d06054e2a3ae1a11b0244cb30734f788a0eb06fba.jpg)

![77445543ee7cb76e0ea312b32173f34aff41d25cdf6a7ab9bec7eb259767fa2d.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/77445543ee7cb76e0ea312b32173f34aff41d25cdf6a7ab9bec7eb259767fa2d.jpg)

![7e359897d6286c1cbf3c843aef07fd962e14941c95f30e7133aae36d99d0267a.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/7e359897d6286c1cbf3c843aef07fd962e14941c95f30e7133aae36d99d0267a.jpg)

![808739dfb77fa0abf296ce71fa8e34e98a34d84d6baa219b527518d885699e48.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/808739dfb77fa0abf296ce71fa8e34e98a34d84d6baa219b527518d885699e48.jpg)

![8bcc5730ee48e657e4dbe180c9555c883cc29a74c077cb82be69c828719e532b.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/8bcc5730ee48e657e4dbe180c9555c883cc29a74c077cb82be69c828719e532b.jpg)

![9fcb67a3ec5d51da06f6e34d1eb505da4d0e14cd7ecbbca8f93effa1a75154e7.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/9fcb67a3ec5d51da06f6e34d1eb505da4d0e14cd7ecbbca8f93effa1a75154e7.jpg)

![b803276b34ada3466528e247f42cf34a75c6697c839bf5181258e9d7bf66e75f.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/b803276b34ada3466528e247f42cf34a75c6697c839bf5181258e9d7bf66e75f.jpg)

![b8639bc7d828a3f008cbb44f640437a14efbab997a40f6f42af884c62c4c88d7.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/b8639bc7d828a3f008cbb44f640437a14efbab997a40f6f42af884c62c4c88d7.jpg)

![ce07744c91165a696eea671ae6995d05b8822e58364cf03ed1668730ab9b7886.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/ce07744c91165a696eea671ae6995d05b8822e58364cf03ed1668730ab9b7886.jpg)

![d7485d233f92e0d434db8aecdcb27ae4d155b9f79eaddabf354f3a1e4fc1966d.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/d7485d233f92e0d434db8aecdcb27ae4d155b9f79eaddabf354f3a1e4fc1966d.jpg)

![f0c6db3a5d747396ec08f6f939beb80bca0a5e665e2d450ed3fc1b19c79412a8.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/f0c6db3a5d747396ec08f6f939beb80bca0a5e665e2d450ed3fc1b19c79412a8.jpg)

![fac9ff7994807fafe58b07ff1257304b39524e54481520b330a5ac29b80ed005.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/fac9ff7994807fafe58b07ff1257304b39524e54481520b330a5ac29b80ed005.jpg)

![fc05d207c430cc32c51a410e5398717e284f77944f422ffb3e58f79b2d8e5b65.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/images/fc05d207c430cc32c51a410e5398717e284f77944f422ffb3e58f79b2d8e5b65.jpg)

### Tables

![36409c641688768750bb1ab9756d172767c9766d874c05fed49ffe18b110fd59.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/tables/36409c641688768750bb1ab9756d172767c9766d874c05fed49ffe18b110fd59.jpg)

![46b36ab6fe9f5c2dc1499af6dbffee6a7873358e35e4a2666bdcde5aa01e0278.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/tables/46b36ab6fe9f5c2dc1499af6dbffee6a7873358e35e4a2666bdcde5aa01e0278.jpg)

![5fcad51eb130b632b50f8d7278265486fd8bd7ece30cf5091dc802967bfacb1d.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/tables/5fcad51eb130b632b50f8d7278265486fd8bd7ece30cf5091dc802967bfacb1d.jpg)

![7d25e6427ce6e6f6541a9873d1f5937bde9e2b9c563bd6883c2e39724b3bff30.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/tables/7d25e6427ce6e6f6541a9873d1f5937bde9e2b9c563bd6883c2e39724b3bff30.jpg)

![cfc7c0695160fe335fb2f6bc110b89121de404aa260a0254ae6b25e4848094eb.jpg](../nips_results/505_Seeing%20Sound%2C%20Hearing%20Sight_%20Uncovering%20Modality%20Bias%20and%20Conflict%20of%20AI%20models%20in%20Sound%20Localizatio/tables/cfc7c0695160fe335fb2f6bc110b89121de404aa260a0254ae6b25e4848094eb.jpg)

## SoTA with Less: MCTS-Guided Sample Selection for Data-Efficient Visual Reasoning Self-Improvement


### Images

![1d34ab2e1e74527f8a4a203260a4cb4d988607225278d65cb0b131ecac0a74dd.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/1d34ab2e1e74527f8a4a203260a4cb4d988607225278d65cb0b131ecac0a74dd.jpg)

![4fdc05fe0a0afb46eea5eef812e896c7d8fdd7f31cf9626f4047ea2feeab4bb7.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/4fdc05fe0a0afb46eea5eef812e896c7d8fdd7f31cf9626f4047ea2feeab4bb7.jpg)

![532bee389c037a0af487c87e049fa0af874e56b3c79d4391a71e8964b90bba70.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/532bee389c037a0af487c87e049fa0af874e56b3c79d4391a71e8964b90bba70.jpg)

![5ca9fe57b0e947aee67af81906cc93e07a873a41ed8b9076615d7dea4c7c485c.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/5ca9fe57b0e947aee67af81906cc93e07a873a41ed8b9076615d7dea4c7c485c.jpg)

![5edf53beea3ff3c0ce22cdac8bf001cb30e4b380d6be544b66209084066b4f8c.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/5edf53beea3ff3c0ce22cdac8bf001cb30e4b380d6be544b66209084066b4f8c.jpg)

![5f2025d5068fda5c850873a41fa89e503e797f92152b0b05314a0260e15774f1.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/5f2025d5068fda5c850873a41fa89e503e797f92152b0b05314a0260e15774f1.jpg)

![6019ba831c05199fcb921f1430ad763928a9ccaa0cacf7dd05177c5a5589003a.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/6019ba831c05199fcb921f1430ad763928a9ccaa0cacf7dd05177c5a5589003a.jpg)

![7ea2c5b995e08675005f77b03684cabcad8df88eb020b1cf363fd433aeafeb9c.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/7ea2c5b995e08675005f77b03684cabcad8df88eb020b1cf363fd433aeafeb9c.jpg)

![a3aac85fec3555f3f261baae27476988e8a6a1c99b5af7568ba9356264446b6a.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/a3aac85fec3555f3f261baae27476988e8a6a1c99b5af7568ba9356264446b6a.jpg)

![b0889a6f31833c789fb844f525ef503a67843f3028fd4738a1ecfca718661d3f.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/b0889a6f31833c789fb844f525ef503a67843f3028fd4738a1ecfca718661d3f.jpg)

![c08b8b6f484104ff115f529b9e4b7a89c764a71f08973ccc53ca0c9b0f780766.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/c08b8b6f484104ff115f529b9e4b7a89c764a71f08973ccc53ca0c9b0f780766.jpg)

![c23347cb6258dd94accf5ed4e011c0e6a4af74b43d16f7301caa1d102c12ec1e.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/c23347cb6258dd94accf5ed4e011c0e6a4af74b43d16f7301caa1d102c12ec1e.jpg)

![eb22b521ba803dcf52feb5a8c30709a726dfae498a06d5c7b2f25e6b07d833b6.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/images/eb22b521ba803dcf52feb5a8c30709a726dfae498a06d5c7b2f25e6b07d833b6.jpg)

### Tables

![3f5ccd9e7edbfec68c6eef00c0fc028eb290752d8683c74de34c519bdd0b4fc4.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/tables/3f5ccd9e7edbfec68c6eef00c0fc028eb290752d8683c74de34c519bdd0b4fc4.jpg)

![7ad3b78d879ae4bb6c4bb18e5e4007eb4225feeba15e26eea45e1dc32fe925e4.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/tables/7ad3b78d879ae4bb6c4bb18e5e4007eb4225feeba15e26eea45e1dc32fe925e4.jpg)

![92d02957874312a5bfd24bcdfd7f7f0e416c65a7e2cf1eca39da3245e8121717.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/tables/92d02957874312a5bfd24bcdfd7f7f0e416c65a7e2cf1eca39da3245e8121717.jpg)

![96e05529fc3bfd0cc92ae84676fe3ebda996b1c9ff9f714c57f6104b1633a66f.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/tables/96e05529fc3bfd0cc92ae84676fe3ebda996b1c9ff9f714c57f6104b1633a66f.jpg)

![d0cad851fea9c4397aa5c2408c0e602fb836c37510614724ab85ab04f359f4c6.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/tables/d0cad851fea9c4397aa5c2408c0e602fb836c37510614724ab85ab04f359f4c6.jpg)

![d2464a24776079e301db88c8d7dc271072a4bc3ccbdd73876b403468fb68499b.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/tables/d2464a24776079e301db88c8d7dc271072a4bc3ccbdd73876b403468fb68499b.jpg)

![eaf4a5fadbdc08861171b37575f416dfd3e5f1a1f15eba3aaac20a304cd54455.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/tables/eaf4a5fadbdc08861171b37575f416dfd3e5f1a1f15eba3aaac20a304cd54455.jpg)

![eebea6385145a1b072011edd9737dc72fac1a8baf077c8cf84559f066bb69e90.jpg](../nips_results/506_SoTA%20with%20Less_%20MCTS-Guided%20Sample%20Selection%20for%20Data-Efficient%20Visual%20Reasoning%20Self-Improvement/tables/eebea6385145a1b072011edd9737dc72fac1a8baf077c8cf84559f066bb69e90.jpg)

## Jacobian-Based Interpretation of Nonlinear Neural Encoding Model


### Images

![0b865567054e70aa601451284937de4ed20034a1483bea9a961a07c77686fa79.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/0b865567054e70aa601451284937de4ed20034a1483bea9a961a07c77686fa79.jpg)

![0d4673ca3e8047352fc510efacfa7663f7969a926b736ade726171b67757d419.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/0d4673ca3e8047352fc510efacfa7663f7969a926b736ade726171b67757d419.jpg)

![1dfcd9f258ebf57bfffc7e8e359cd2e1d885dd63c3e488b7f71555763b96ca35.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/1dfcd9f258ebf57bfffc7e8e359cd2e1d885dd63c3e488b7f71555763b96ca35.jpg)

![1eb349890ab86154d66d336cbd4ce654cc39968f1096cbec7943c8b21c8c0429.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/1eb349890ab86154d66d336cbd4ce654cc39968f1096cbec7943c8b21c8c0429.jpg)

![212d7c846220ee9377a5286f1c5f4a6394ea6e2f04e77fc4c8f88c5b2d0bbd05.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/212d7c846220ee9377a5286f1c5f4a6394ea6e2f04e77fc4c8f88c5b2d0bbd05.jpg)

![24aa3eb1e7f0c4952629040803dd284bbf60fe88950d0d048a6d352eaed65027.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/24aa3eb1e7f0c4952629040803dd284bbf60fe88950d0d048a6d352eaed65027.jpg)

![3e5a95fc0e556e0f127c869e1dabedbc85d5e81bfc99b65af7a1b5ca2a8f25e9.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/3e5a95fc0e556e0f127c869e1dabedbc85d5e81bfc99b65af7a1b5ca2a8f25e9.jpg)

![553b2d0ecb45fb1685acef5b425a8e1e1990272af8fd57a8d57da3d0f9d226f7.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/553b2d0ecb45fb1685acef5b425a8e1e1990272af8fd57a8d57da3d0f9d226f7.jpg)

![59a7c2dc44cdc9727daff25c618770bb4731fefe80e2c127f4178fa2936b2bdf.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/59a7c2dc44cdc9727daff25c618770bb4731fefe80e2c127f4178fa2936b2bdf.jpg)

![5febcb228607aa52c2b67ae7696f33c2565c341d0c80129aaea7320cb5898207.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/5febcb228607aa52c2b67ae7696f33c2565c341d0c80129aaea7320cb5898207.jpg)

![80b00ce8825f7aa4e632d6f4cfd41e556c5a4707f3e89e837ee6f5e60d403e8d.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/80b00ce8825f7aa4e632d6f4cfd41e556c5a4707f3e89e837ee6f5e60d403e8d.jpg)

![905249a4a773a1b8331db3c7e936b5d3f8a3ef265dabec278f186aff4b979ee0.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/905249a4a773a1b8331db3c7e936b5d3f8a3ef265dabec278f186aff4b979ee0.jpg)

![a96f4538d5dd445497ef75f553294fc697c6aab9e0b56b768905990c5a18f985.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/a96f4538d5dd445497ef75f553294fc697c6aab9e0b56b768905990c5a18f985.jpg)

![c312b02d9d3741cb06f799f2e878dbdba4369cbea05f765f69349ebfc97c282b.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/c312b02d9d3741cb06f799f2e878dbdba4369cbea05f765f69349ebfc97c282b.jpg)

![c51aad0287c71e83c01759c3136b7dbb0b97fe55afb45b89911abaa33b6727af.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/c51aad0287c71e83c01759c3136b7dbb0b97fe55afb45b89911abaa33b6727af.jpg)

![c9ac984c977d21aff284dcfbacf7bdfea345cc73096a3f28d624b026654e1740.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/c9ac984c977d21aff284dcfbacf7bdfea345cc73096a3f28d624b026654e1740.jpg)

![cb34f68b7cdad24e800ba29d383378c813cb022f005561a05d48e84ccecd344b.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/cb34f68b7cdad24e800ba29d383378c813cb022f005561a05d48e84ccecd344b.jpg)

![d7e801db9a12d6c10bd18489db73db5e373997f9ac0a0398f50e16ee472302ed.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/d7e801db9a12d6c10bd18489db73db5e373997f9ac0a0398f50e16ee472302ed.jpg)

![e7488e03bade79740ad81cfe0a7dd91d2e1d615ddc60afcd495752dd0b11cd4e.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/e7488e03bade79740ad81cfe0a7dd91d2e1d615ddc60afcd495752dd0b11cd4e.jpg)

![eab6d86474efac52352f7c90b7b38a67efc89ef92deb373f64c4c92dadc06bd5.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/eab6d86474efac52352f7c90b7b38a67efc89ef92deb373f64c4c92dadc06bd5.jpg)

![eea991eab6a71ad28fc57be467ad9af7442cdb9fdbe0d4fd739666598b4ab4d9.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/images/eea991eab6a71ad28fc57be467ad9af7442cdb9fdbe0d4fd739666598b4ab4d9.jpg)

### Tables

![12e288e77a6046f883e5ab445ea11ed296001474b0c04f09a290a4b6128b761d.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/tables/12e288e77a6046f883e5ab445ea11ed296001474b0c04f09a290a4b6128b761d.jpg)

![60759d0bd7193ba1a5571355cbefccde0671813a66b76674175ceadbd09d014d.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/tables/60759d0bd7193ba1a5571355cbefccde0671813a66b76674175ceadbd09d014d.jpg)

![79e967ce00c35284e365c58ae3f22da589f20a45d37dd39cbf69dc660f2e0561.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/tables/79e967ce00c35284e365c58ae3f22da589f20a45d37dd39cbf69dc660f2e0561.jpg)

![7f435df20830607dffc823ca03a8e90e540acd9fce9281a119f54a86e5b9a281.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/tables/7f435df20830607dffc823ca03a8e90e540acd9fce9281a119f54a86e5b9a281.jpg)

![ddeaf935bdb02cdf9c2ff4688e3cd2878bc756918bc360226d9759ebdafe34fc.jpg](../nips_results/507_Jacobian-Based%20Interpretation%20of%20Nonlinear%20Neural%20Encoding%20Model/tables/ddeaf935bdb02cdf9c2ff4688e3cd2878bc756918bc360226d9759ebdafe34fc.jpg)

## ARECHO: Autoregressive Evaluation via Chain-Based Hypothesis Optimization for Speech Multi-Metric Estimation


### Images

![57e6409ab409d7a678fbeabf453678afa2cbae54ed5be45115d86e568d6ee6ec.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/images/57e6409ab409d7a678fbeabf453678afa2cbae54ed5be45115d86e568d6ee6ec.jpg)

![84bb0bfd9d3a88a43a2c290caa5cf68678ba026d63baaf2c646e2f53a1162f9f.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/images/84bb0bfd9d3a88a43a2c290caa5cf68678ba026d63baaf2c646e2f53a1162f9f.jpg)

![b77c505591a734b30a1c669cc1031ba707b7d6f0b4886b56ed1d8e0a26188ffd.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/images/b77c505591a734b30a1c669cc1031ba707b7d6f0b4886b56ed1d8e0a26188ffd.jpg)

### Tables

![035f868481956a9d332c1b90ccdb56657b2886ad1014f2d2ad5401fa2d9dd407.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/035f868481956a9d332c1b90ccdb56657b2886ad1014f2d2ad5401fa2d9dd407.jpg)

![064f15c7e2f1250940d48eca496bec33b3c5e0e951afff6ea54f5d5735705ad5.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/064f15c7e2f1250940d48eca496bec33b3c5e0e951afff6ea54f5d5735705ad5.jpg)

![090bcc57221996a705e48aaeee63f551b353eefd4a425479ee176900b0dac12a.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/090bcc57221996a705e48aaeee63f551b353eefd4a425479ee176900b0dac12a.jpg)

![0e0aec1ff90fa410b661e78c63e170288ebc6c59d73468fffe9d839c09113c5f.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/0e0aec1ff90fa410b661e78c63e170288ebc6c59d73468fffe9d839c09113c5f.jpg)

![1b555e90e07a1b698f38f66e0ef34bee9dbf870144e7bced8a5565c4183a5965.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/1b555e90e07a1b698f38f66e0ef34bee9dbf870144e7bced8a5565c4183a5965.jpg)

![202396b012b30a2207e2b02d148bfb4069217b9ca7cc278f14629f7c9eec494d.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/202396b012b30a2207e2b02d148bfb4069217b9ca7cc278f14629f7c9eec494d.jpg)

![21f43c49cef9b7171baa61673743f5bc8622da96109c1fdceace41bc6db3c632.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/21f43c49cef9b7171baa61673743f5bc8622da96109c1fdceace41bc6db3c632.jpg)

![241cb156375e79327a1379f366e853eb5b8782fbaede382a61b04da4a3308f2b.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/241cb156375e79327a1379f366e853eb5b8782fbaede382a61b04da4a3308f2b.jpg)

![33c1a64c82e78493eef5899ead404c7bf78b91406ce0a73cc7eff35760568ec8.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/33c1a64c82e78493eef5899ead404c7bf78b91406ce0a73cc7eff35760568ec8.jpg)

![36c3f03b846cb4260869e049fac2577607a73a742a67adcf665dd5d3ee016726.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/36c3f03b846cb4260869e049fac2577607a73a742a67adcf665dd5d3ee016726.jpg)

![49b719e132f2d0db43c126334821b18b33f0af03f0aa40f8fa42b3e3ca53d9de.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/49b719e132f2d0db43c126334821b18b33f0af03f0aa40f8fa42b3e3ca53d9de.jpg)

![4fbe926144ead280c7066d64e40bdbffa6190a53ab52bc349c5d3059b7412c33.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/4fbe926144ead280c7066d64e40bdbffa6190a53ab52bc349c5d3059b7412c33.jpg)

![5eecf6995308c8bfc1963a773510850a91076284528b7cd6637711ac1418b606.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/5eecf6995308c8bfc1963a773510850a91076284528b7cd6637711ac1418b606.jpg)

![69eae3a79d1763d9bb4a8d81527876d650c478bc199835a9fed14acf19361344.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/69eae3a79d1763d9bb4a8d81527876d650c478bc199835a9fed14acf19361344.jpg)

![706f17b291805a5d07bf787082f206ce64f27717155626b998e0e16a64ef5301.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/706f17b291805a5d07bf787082f206ce64f27717155626b998e0e16a64ef5301.jpg)

![70f4b8ebcaee66904f8a73864cd060639ab0018cff692a15cb7209d93bd1cb23.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/70f4b8ebcaee66904f8a73864cd060639ab0018cff692a15cb7209d93bd1cb23.jpg)

![7b0196bf1619b8eefd965e07f3426c53ac510e582384dc5c8b20773abe327518.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/7b0196bf1619b8eefd965e07f3426c53ac510e582384dc5c8b20773abe327518.jpg)

![870a7553aba04d699b12ed88723899f15d2a86ade6959ef514da73294ce9f844.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/870a7553aba04d699b12ed88723899f15d2a86ade6959ef514da73294ce9f844.jpg)

![cd8e259f3fa04ec560847d9f133390cdab6f8b127f44f169195c1473b61bf171.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/cd8e259f3fa04ec560847d9f133390cdab6f8b127f44f169195c1473b61bf171.jpg)

![d0e136b93f847a112ae97db6c2438a801feaf0440acb43b67a0c6d70a3bc69fc.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/d0e136b93f847a112ae97db6c2438a801feaf0440acb43b67a0c6d70a3bc69fc.jpg)

![db3f90d3d284c179dc142cfbf7ecfc28fc8e6db3559d5164f6bc29d17cdfb83d.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/db3f90d3d284c179dc142cfbf7ecfc28fc8e6db3559d5164f6bc29d17cdfb83d.jpg)

![e5de87ff18a2edb240c8c604a28588c7858a2e00b8fe9fca3654bfc76de67527.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/e5de87ff18a2edb240c8c604a28588c7858a2e00b8fe9fca3654bfc76de67527.jpg)

![eb18f2e0836cb3f549555f51f5a6739d61c72005f28b3be286386e3dd64ccf54.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/eb18f2e0836cb3f549555f51f5a6739d61c72005f28b3be286386e3dd64ccf54.jpg)

![ef497616b3fb95edc7f4e1b744a311d4897c2509ea2b04e002d592daa13b66a9.jpg](../nips_results/508_ARECHO_%20Autoregressive%20Evaluation%20via%20Chain-Based%20Hypothesis%20Optimization%20for%20Speech%20Multi-Metric%20Es/tables/ef497616b3fb95edc7f4e1b744a311d4897c2509ea2b04e002d592daa13b66a9.jpg)

## Online Strategic Classification With Noise and Partial Feedback


### Images

![10009aae2862cc33825ffd966b5075fab3ca628ddfc4d0e41f759d23f16a3a99.jpg](../nips_results/509_Online%20Strategic%20Classification%20With%20Noise%20and%20Partial%20Feedback/images/10009aae2862cc33825ffd966b5075fab3ca628ddfc4d0e41f759d23f16a3a99.jpg)

![6453c81d16fc5d98cda75d0eca75f31d3d3ba25367dfcb7fc68c46055d6a1b85.jpg](../nips_results/509_Online%20Strategic%20Classification%20With%20Noise%20and%20Partial%20Feedback/images/6453c81d16fc5d98cda75d0eca75f31d3d3ba25367dfcb7fc68c46055d6a1b85.jpg)

![8a47c2a86432c705d6a5c080554873ae6a67e1663601ba86b9644290f0cf2c4c.jpg](../nips_results/509_Online%20Strategic%20Classification%20With%20Noise%20and%20Partial%20Feedback/images/8a47c2a86432c705d6a5c080554873ae6a67e1663601ba86b9644290f0cf2c4c.jpg)

![9b448e509c1d12ebada320dfa0e2a3efce2f769eb3c8ec48e9bba4c7ae14bfcd.jpg](../nips_results/509_Online%20Strategic%20Classification%20With%20Noise%20and%20Partial%20Feedback/images/9b448e509c1d12ebada320dfa0e2a3efce2f769eb3c8ec48e9bba4c7ae14bfcd.jpg)

![b533d2783eca37665ed81463bdb81130f167f4fdf811c58c01529c262090f2db.jpg](../nips_results/509_Online%20Strategic%20Classification%20With%20Noise%20and%20Partial%20Feedback/images/b533d2783eca37665ed81463bdb81130f167f4fdf811c58c01529c262090f2db.jpg)

![c97cfd774ddb379db0e6e4ea135a163e4b392ae3c17ba2f59636daaa284a3905.jpg](../nips_results/509_Online%20Strategic%20Classification%20With%20Noise%20and%20Partial%20Feedback/images/c97cfd774ddb379db0e6e4ea135a163e4b392ae3c17ba2f59636daaa284a3905.jpg)

![f9ec5890ffe0f90f14c9120c95ab168b7c3d1f1c0d806a25a04f7d87c14f4125.jpg](../nips_results/509_Online%20Strategic%20Classification%20With%20Noise%20and%20Partial%20Feedback/images/f9ec5890ffe0f90f14c9120c95ab168b7c3d1f1c0d806a25a04f7d87c14f4125.jpg)

### Tables

![4e819912fd36b95d36dddaad0110b94d5a5b90dfaaf8e5634bc25d34d01a9623.jpg](../nips_results/509_Online%20Strategic%20Classification%20With%20Noise%20and%20Partial%20Feedback/tables/4e819912fd36b95d36dddaad0110b94d5a5b90dfaaf8e5634bc25d34d01a9623.jpg)

![6d2e59779703c2503a1ea98ce12fa0e349a6dff43b8fabd185d266124a7f2519.jpg](../nips_results/509_Online%20Strategic%20Classification%20With%20Noise%20and%20Partial%20Feedback/tables/6d2e59779703c2503a1ea98ce12fa0e349a6dff43b8fabd185d266124a7f2519.jpg)

![c6e217df94279bcde6f6e3d4322c3fe3711074ac6b2725585dbea226d33233e7.jpg](../nips_results/509_Online%20Strategic%20Classification%20With%20Noise%20and%20Partial%20Feedback/tables/c6e217df94279bcde6f6e3d4322c3fe3711074ac6b2725585dbea226d33233e7.jpg)

![f87fb993663f518fb3c7aad7f1d9c04093fb25eb9c92d8e8d0c9db04338613f8.jpg](../nips_results/509_Online%20Strategic%20Classification%20With%20Noise%20and%20Partial%20Feedback/tables/f87fb993663f518fb3c7aad7f1d9c04093fb25eb9c92d8e8d0c9db04338613f8.jpg)

## CoT Information: Improved Sample Complexity under Chain-of-Thought Supervision


### Images

![04a04d5fd94845fd5958456a1dc6f4ab1cb4307ca5acf0362544e75f175609ac.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/04a04d5fd94845fd5958456a1dc6f4ab1cb4307ca5acf0362544e75f175609ac.jpg)

![0b12fd84b61c94634af4877263062269d832f84397894b3b36c728c51563db07.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/0b12fd84b61c94634af4877263062269d832f84397894b3b36c728c51563db07.jpg)

![120298f1bee9a9f570caaf71dd37b2a85ccdd84727be69280f061f1712d5a081.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/120298f1bee9a9f570caaf71dd37b2a85ccdd84727be69280f061f1712d5a081.jpg)

![369c649ab6daa63624501a9e1605679fbdfcff21f94f91095d3d64f11d3226a9.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/369c649ab6daa63624501a9e1605679fbdfcff21f94f91095d3d64f11d3226a9.jpg)

![73c5a0f81a8f67ae4451ebcc6a5887a192738e85d713323b2474d3a93485a5d6.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/73c5a0f81a8f67ae4451ebcc6a5887a192738e85d713323b2474d3a93485a5d6.jpg)

![78dcf25e87cd05a81214cf5052607056beea9c536c5e14a5430dbd8d33ac9fba.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/78dcf25e87cd05a81214cf5052607056beea9c536c5e14a5430dbd8d33ac9fba.jpg)

![819487cd79919a4a00403e09acb05be4bcada22c9237f8deebbd013ef02d6bb0.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/819487cd79919a4a00403e09acb05be4bcada22c9237f8deebbd013ef02d6bb0.jpg)

![a5196827ad2286827f2daf137fd8d1bb7561967457fab63fa42c0dbc4f6f2e4a.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/a5196827ad2286827f2daf137fd8d1bb7561967457fab63fa42c0dbc4f6f2e4a.jpg)

![a7c72d76a6a5d1833db7cfafb3c93590d5d6680dd064d9b91592140bee686bfa.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/a7c72d76a6a5d1833db7cfafb3c93590d5d6680dd064d9b91592140bee686bfa.jpg)

![c95121ea599e46bf7950355bb9955ecc7eecf2136285599389134cc18cefb5ea.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/c95121ea599e46bf7950355bb9955ecc7eecf2136285599389134cc18cefb5ea.jpg)

![ce80368b148b8d960493637c94d7f2046c40490b816902f76dc01b7cc4c31ba4.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/ce80368b148b8d960493637c94d7f2046c40490b816902f76dc01b7cc4c31ba4.jpg)

![d75810f5443394dc27a458c82b577ee48c7602fa7834c4f30fc16f8f740022fc.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/d75810f5443394dc27a458c82b577ee48c7602fa7834c4f30fc16f8f740022fc.jpg)

![eaf924460a00879ef38d43b610dbba5a09c08f9c690d4590ca03fdca0e85071b.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/images/eaf924460a00879ef38d43b610dbba5a09c08f9c690d4590ca03fdca0e85071b.jpg)

### Tables

![3eafc61ceb557cfb279a94cceab8971f36b741ad5561fc9ba82fae8a116909b9.jpg](../nips_results/510_CoT%20Information_%20Improved%20Sample%20Complexity%20under%20Chain-of-Thought%20Supervision/tables/3eafc61ceb557cfb279a94cceab8971f36b741ad5561fc9ba82fae8a116909b9.jpg)

## What are you sinking? A geometric approach on attention sink


### Images

![145d8347ad706b89491708ab24366e63ef376da07d8331e5c4a95616429766af.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/images/145d8347ad706b89491708ab24366e63ef376da07d8331e5c4a95616429766af.jpg)

### Tables

![1635e7d3bcd37f83fc0d9ab3718cb93c0f54c4afbffc6536cd6801ff83ba43c5.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/1635e7d3bcd37f83fc0d9ab3718cb93c0f54c4afbffc6536cd6801ff83ba43c5.jpg)

![169223ec943f85a0d1db9b12aae51a02b876b3cd3b782bc40bc2001bb50ccf5f.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/169223ec943f85a0d1db9b12aae51a02b876b3cd3b782bc40bc2001bb50ccf5f.jpg)

![16b6631c18a44c4e87b57145723342e940b6724e8b3eaf15ca73fbef5fc7dc49.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/16b6631c18a44c4e87b57145723342e940b6724e8b3eaf15ca73fbef5fc7dc49.jpg)

![1c8f31c970d013229e97e90348008a15bd3ce8a9476718fd50d6b99f7843f3d0.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/1c8f31c970d013229e97e90348008a15bd3ce8a9476718fd50d6b99f7843f3d0.jpg)

![27c2270a8b9bcdd3f5ec6d44708d1bcf4a2ac79d12e590a429132b5342541c76.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/27c2270a8b9bcdd3f5ec6d44708d1bcf4a2ac79d12e590a429132b5342541c76.jpg)

![2b32285f2dc3f5e3ac82a9161a8c903c0f9a8ff78350319c63d5c52aa0917f5f.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/2b32285f2dc3f5e3ac82a9161a8c903c0f9a8ff78350319c63d5c52aa0917f5f.jpg)

![2c403d5febffcf71082cbe4df405350e7145d978d12a9538c988d345c9776278.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/2c403d5febffcf71082cbe4df405350e7145d978d12a9538c988d345c9776278.jpg)

![3666c9cce1373c204db82c359074ff2c711ff262a73eca4e10baef33535ae005.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/3666c9cce1373c204db82c359074ff2c711ff262a73eca4e10baef33535ae005.jpg)

![38d884b6ab9347d2a348b7ccb1d8936615d5ca0671c8b7b0d4db75baec53869d.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/38d884b6ab9347d2a348b7ccb1d8936615d5ca0671c8b7b0d4db75baec53869d.jpg)

![39cbed138fd91530e7486629f4c513d00e59569741956fd6a313e138f53bffc4.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/39cbed138fd91530e7486629f4c513d00e59569741956fd6a313e138f53bffc4.jpg)

![39d9900eae065698ee75239992709ccb9f52f43c358e37a5caadf504a13c07aa.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/39d9900eae065698ee75239992709ccb9f52f43c358e37a5caadf504a13c07aa.jpg)

![3fb906e85d9f541fc84c4a77124b43af8131d433fc2e4cc707757a1eac13d383.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/3fb906e85d9f541fc84c4a77124b43af8131d433fc2e4cc707757a1eac13d383.jpg)

![450476e3c50133e3ff8d4f0728124657d4f94e6a9fcb4d9d0ee0140fdf643f7e.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/450476e3c50133e3ff8d4f0728124657d4f94e6a9fcb4d9d0ee0140fdf643f7e.jpg)

![479fae45d8ee6326518e133e7ea8f7821ba3484a9b6fd96621c0331f9ccc1932.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/479fae45d8ee6326518e133e7ea8f7821ba3484a9b6fd96621c0331f9ccc1932.jpg)

![4c8dbb840c82946196ec172f001633da478cfdc7270d09d522ab1b616f799cdc.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/4c8dbb840c82946196ec172f001633da478cfdc7270d09d522ab1b616f799cdc.jpg)

![5dfe8bc6519e9e4fd9da73fe1c3a209041e5ce3fa8f1f09020b63d06bf60e5df.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/5dfe8bc6519e9e4fd9da73fe1c3a209041e5ce3fa8f1f09020b63d06bf60e5df.jpg)

![63d162ff3d07f82a94fe70ed2aa4762b394b38d55ce519fa547d2e3a94946e99.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/63d162ff3d07f82a94fe70ed2aa4762b394b38d55ce519fa547d2e3a94946e99.jpg)

![78ad182c790830ed4f76a183078f3dd7921187c3c1881d090512df548b8c8012.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/78ad182c790830ed4f76a183078f3dd7921187c3c1881d090512df548b8c8012.jpg)

![8fda0445f45aa7c650f4ced9bdddee3d2fa345ec2038a66258baf4af141d74d4.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/8fda0445f45aa7c650f4ced9bdddee3d2fa345ec2038a66258baf4af141d74d4.jpg)

![908d0451326c42a195bcf5b356713c7dacaee2d01267468b3afb007b4dd25cb2.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/908d0451326c42a195bcf5b356713c7dacaee2d01267468b3afb007b4dd25cb2.jpg)

![914831e7ef0c98a600f4d831b6ca76bee3c628e35b2a0387f61dd09a9684378f.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/914831e7ef0c98a600f4d831b6ca76bee3c628e35b2a0387f61dd09a9684378f.jpg)

![93ee0b88b72d27a5a93727e0b0779aec7acc297459bcd404855961fd95533955.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/93ee0b88b72d27a5a93727e0b0779aec7acc297459bcd404855961fd95533955.jpg)

![9a751b8cb34971d7092aa43978c90138752254e94d368e01064831c532d61842.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/9a751b8cb34971d7092aa43978c90138752254e94d368e01064831c532d61842.jpg)

![a07fb206bb07c5776069bc636609d89d3a4ae152a73948f1a6d8b78bdb130c06.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/a07fb206bb07c5776069bc636609d89d3a4ae152a73948f1a6d8b78bdb130c06.jpg)

![a68066a61c93d43fc29016957c8ecd088fcf6511be8742316784c4f5ae793134.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/a68066a61c93d43fc29016957c8ecd088fcf6511be8742316784c4f5ae793134.jpg)

![b30f0b2a397a2bae5526a380d2ffcc09d03f5a337e7e7c31767af738e2f9d7d7.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/b30f0b2a397a2bae5526a380d2ffcc09d03f5a337e7e7c31767af738e2f9d7d7.jpg)

![b4ca5f21590badce13a4319579b7c356043d5e5e79cfa0d316758394ceeff89a.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/b4ca5f21590badce13a4319579b7c356043d5e5e79cfa0d316758394ceeff89a.jpg)

![b5946fd0197d94dbb6e640db28fcfc7dca71a66e9c0bf54e48a6cf865c6b98bb.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/b5946fd0197d94dbb6e640db28fcfc7dca71a66e9c0bf54e48a6cf865c6b98bb.jpg)

![cda3e1263d87414b90688ca9ffb38239d8d86c62a9bbac5e2249eac72d42bb05.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/cda3e1263d87414b90688ca9ffb38239d8d86c62a9bbac5e2249eac72d42bb05.jpg)

![d7285f0b342c220a9fc3bbe5a99f3a1ecbf4329c60033ed32bce587983639219.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/d7285f0b342c220a9fc3bbe5a99f3a1ecbf4329c60033ed32bce587983639219.jpg)

![dd66b9d30d1603370a40f7eb8a20481f450842d75b53e671fb293a9cc6390702.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/dd66b9d30d1603370a40f7eb8a20481f450842d75b53e671fb293a9cc6390702.jpg)

![ea6444557097b5dc4f873a4d160020969d5f39c816efa51f2507d65400a4b3a9.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/ea6444557097b5dc4f873a4d160020969d5f39c816efa51f2507d65400a4b3a9.jpg)

![ed129e5f07670797b388255fd973aaf935551d2be86b01ebbdbb02159474d005.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/ed129e5f07670797b388255fd973aaf935551d2be86b01ebbdbb02159474d005.jpg)

![ef69f1992538678b3937636031087dc16281a0875b60729b7b416d58a4fcc75f.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/ef69f1992538678b3937636031087dc16281a0875b60729b7b416d58a4fcc75f.jpg)

![f56f3a1b086446670084380058263d222037fee13e6a1eadd0d78c92050b60c0.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/f56f3a1b086446670084380058263d222037fee13e6a1eadd0d78c92050b60c0.jpg)

![f5eda899067861fd83ad9cac53190e0dfca1dec96e2bb25b14b67d186972b8bf.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/f5eda899067861fd83ad9cac53190e0dfca1dec96e2bb25b14b67d186972b8bf.jpg)

![f87ab7e540ce16539183f89b595b90cc1a44a441b50891efa596d32d269928e9.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/f87ab7e540ce16539183f89b595b90cc1a44a441b50891efa596d32d269928e9.jpg)

![fac0fa70093755bf0a46a9df8dad39ebfa73c527bdfd0cb2370f979b3ec69afa.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/fac0fa70093755bf0a46a9df8dad39ebfa73c527bdfd0cb2370f979b3ec69afa.jpg)

![fe61ed53ce854b83656b6d43f3f86fb0aa68c4b86e781f60942beaeb7584f786.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/fe61ed53ce854b83656b6d43f3f86fb0aa68c4b86e781f60942beaeb7584f786.jpg)

![ff089fb8c767b4b3fdad9dc83fac548e9eabf55169bcab094926874a7439cff3.jpg](../nips_results/511_What%20are%20you%20sinking_%20A%20geometric%20approach%20on%20attention%20sink/tables/ff089fb8c767b4b3fdad9dc83fac548e9eabf55169bcab094926874a7439cff3.jpg)

## Do-PFN: In-Context Learning for Causal Effect Estimation


### Images

![0a8dc9992bce073e65a29d50623cd4eb6fadf19583f75cffc42f9df86c79731e.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/0a8dc9992bce073e65a29d50623cd4eb6fadf19583f75cffc42f9df86c79731e.jpg)

![0b9daf537c80321cd07f8d3e9d21e664674caea9f4f41757b252f7ee5f2a5943.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/0b9daf537c80321cd07f8d3e9d21e664674caea9f4f41757b252f7ee5f2a5943.jpg)

![1e1a2276e512e0700f681d725c70aa00d62c7182c2cd5897979c79b2266f72b1.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/1e1a2276e512e0700f681d725c70aa00d62c7182c2cd5897979c79b2266f72b1.jpg)

![1e22d0e222d6f2ee5458597c47599f998664e7972ef6d9dd416caf7c62d9abc4.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/1e22d0e222d6f2ee5458597c47599f998664e7972ef6d9dd416caf7c62d9abc4.jpg)

![3157c5bc41d585c6d2363630807e3234c5fa8110824e459952f7a3e78eded39d.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/3157c5bc41d585c6d2363630807e3234c5fa8110824e459952f7a3e78eded39d.jpg)

![31f3be7aa275ac849844085606e4232e87fc8a9f34256e38cc632b23e3a33c24.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/31f3be7aa275ac849844085606e4232e87fc8a9f34256e38cc632b23e3a33c24.jpg)

![42eb67c7adcb5e5f043fc070d55bc9e6ea026d678cf87ad80d1d59e673513dd2.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/42eb67c7adcb5e5f043fc070d55bc9e6ea026d678cf87ad80d1d59e673513dd2.jpg)

![52a5cb166a81d4fc41d90a027f52d6316393fc17c89864ce2dace083ed359bca.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/52a5cb166a81d4fc41d90a027f52d6316393fc17c89864ce2dace083ed359bca.jpg)

![664db3b32c1445576ee5aa1601df28965b3cb304937a0c0a3b21d18a3f50f6e3.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/664db3b32c1445576ee5aa1601df28965b3cb304937a0c0a3b21d18a3f50f6e3.jpg)

![684694a5e2230f139d4903b909a351c662ce188ad684fe322e03096a40c896a0.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/684694a5e2230f139d4903b909a351c662ce188ad684fe322e03096a40c896a0.jpg)

![843cfe2e24e4b642de7e2f3f06cb83ee27d2c505cf690e09796bac220457452e.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/843cfe2e24e4b642de7e2f3f06cb83ee27d2c505cf690e09796bac220457452e.jpg)

![87add4d881467cdbe25176a5d5db981fd984d3c0e7965cbef8c8f37616854f1d.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/87add4d881467cdbe25176a5d5db981fd984d3c0e7965cbef8c8f37616854f1d.jpg)

![889771f20c5bd9061a082233536e3161d76c45aed9d560d04f8b738237e82ea3.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/889771f20c5bd9061a082233536e3161d76c45aed9d560d04f8b738237e82ea3.jpg)

![afcd97c120d082bf9d19e2c4959bd89385ed43c673b1a69643d9eace6ceb523a.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/afcd97c120d082bf9d19e2c4959bd89385ed43c673b1a69643d9eace6ceb523a.jpg)

![b2df45e051f47bf8037c32cda5b6dffaad1a1aaf2642909e86955701ae734f02.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/b2df45e051f47bf8037c32cda5b6dffaad1a1aaf2642909e86955701ae734f02.jpg)

![b52df3d782f9da4ddcdb75a4497750b2aab0463eb03b1bbd6c3f2d3d99055a0c.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/b52df3d782f9da4ddcdb75a4497750b2aab0463eb03b1bbd6c3f2d3d99055a0c.jpg)

![b5c8a1917842eb258af887a7d929e017af00e9d7db385b67c69d6e9e541b9c0b.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/b5c8a1917842eb258af887a7d929e017af00e9d7db385b67c69d6e9e541b9c0b.jpg)

![b91011503a32c299097aa81a29667462326e0c08666d174c0a1560950cec92ec.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/b91011503a32c299097aa81a29667462326e0c08666d174c0a1560950cec92ec.jpg)

![c75eefaa483d5f57191f2a27a2109c3de67400f1c3ef57c26ace4b1b8feefb29.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/c75eefaa483d5f57191f2a27a2109c3de67400f1c3ef57c26ace4b1b8feefb29.jpg)

![d24f851a4b6d88e9b4e6b5dd3bbcf9a9572f9fe64a6a8b4f6eed11a6f9afb2e5.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/d24f851a4b6d88e9b4e6b5dd3bbcf9a9572f9fe64a6a8b4f6eed11a6f9afb2e5.jpg)

![d27862b06d21f99cec8af38c9dc7f137cedcf3fd61072c87fcb743d5bd16f5e5.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/d27862b06d21f99cec8af38c9dc7f137cedcf3fd61072c87fcb743d5bd16f5e5.jpg)

![ff25c12d9f647c2a530241ec9538e5a489271d2c16f1902914c8f63250855416.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/images/ff25c12d9f647c2a530241ec9538e5a489271d2c16f1902914c8f63250855416.jpg)

### Tables

![2d6a1592aeaec3f821d10e325a1dc1b5b98cfb24907be7715a7ec3dccc030aee.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/tables/2d6a1592aeaec3f821d10e325a1dc1b5b98cfb24907be7715a7ec3dccc030aee.jpg)

![5792b519d23670d00089014a5d6e097b9ee0b334a0fc2ba44919b3055b000fce.jpg](../nips_results/512_Do-PFN_%20In-Context%20Learning%20for%20Causal%20Effect%20Estimation/tables/5792b519d23670d00089014a5d6e097b9ee0b334a0fc2ba44919b3055b000fce.jpg)

## On the necessity of adaptive regularisation: Optimal anytime online learning on $\boldsymbol{\ell_p}$-balls


### Images

![ed861228d5fdef3d27df9a1518ff927d13c5fdd061cff9669df2cc835d87777c.jpg](../nips_results/513_On%20the%20necessity%20of%20adaptive%20regularisation_%20Optimal%20anytime%20online%20learning%20on%20%24_boldsymbol%7B_ell_p%7D/images/ed861228d5fdef3d27df9a1518ff927d13c5fdd061cff9669df2cc835d87777c.jpg)

### Tables

![219db9d8a005ef27b6525abf2769077516d7ce45a21509509ebd9ac0ad72ca72.jpg](../nips_results/513_On%20the%20necessity%20of%20adaptive%20regularisation_%20Optimal%20anytime%20online%20learning%20on%20%24_boldsymbol%7B_ell_p%7D/tables/219db9d8a005ef27b6525abf2769077516d7ce45a21509509ebd9ac0ad72ca72.jpg)

## An Evidence-Based Post-Hoc Adjustment Framework for Anomaly Detection Under Data Contamination


### Images

![01551c8a8a5312a94a5e485de5552445d0abef57912005e166bf957a3356b17c.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/images/01551c8a8a5312a94a5e485de5552445d0abef57912005e166bf957a3356b17c.jpg)

![4cc161e6f2081c0ab6e29d4a0045e35f0b0f572efe0275049fa6bf0ed50c524b.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/images/4cc161e6f2081c0ab6e29d4a0045e35f0b0f572efe0275049fa6bf0ed50c524b.jpg)

![75aae916990db170e96114bf3c97db7caccf6ad0337bc822a47ef4f367ccc736.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/images/75aae916990db170e96114bf3c97db7caccf6ad0337bc822a47ef4f367ccc736.jpg)

![7bb5ca2c9bb07849f266c9be3e6cf222e66b6e0131fa81460c5d760a4d50dd90.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/images/7bb5ca2c9bb07849f266c9be3e6cf222e66b6e0131fa81460c5d760a4d50dd90.jpg)

![b5de77c601124ad2e8a2c3d7e9fe9b482038910a6574d9546e098b3dce635f18.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/images/b5de77c601124ad2e8a2c3d7e9fe9b482038910a6574d9546e098b3dce635f18.jpg)

### Tables

![13dd3c49add5c24989d6ddb39653a2bf455c77c7ae5947ece3970fb9e5fc5de2.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/tables/13dd3c49add5c24989d6ddb39653a2bf455c77c7ae5947ece3970fb9e5fc5de2.jpg)

![2f34563a9a2ccf02bfb6149cca5360e21f7fd758f433dbfecb4c2eae34e8079f.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/tables/2f34563a9a2ccf02bfb6149cca5360e21f7fd758f433dbfecb4c2eae34e8079f.jpg)

![324ea22a5e17f46ed69bdffbc4ef7280d5bbc8de0eef6fcc2869ea888751730f.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/tables/324ea22a5e17f46ed69bdffbc4ef7280d5bbc8de0eef6fcc2869ea888751730f.jpg)

![35e16fcd036cce1a1425e0489cbebb7b8a728795ad9aaeac7dd890597e9c7de6.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/tables/35e16fcd036cce1a1425e0489cbebb7b8a728795ad9aaeac7dd890597e9c7de6.jpg)

![70e4c7ee294b84805d27effcb8b17ffa98c72a3bd7ae12597587a1f44e9653ba.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/tables/70e4c7ee294b84805d27effcb8b17ffa98c72a3bd7ae12597587a1f44e9653ba.jpg)

![7f4c72c9b7a40e47bd8d00b5dc05efcc23c292af92e980f601ba6f0807808454.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/tables/7f4c72c9b7a40e47bd8d00b5dc05efcc23c292af92e980f601ba6f0807808454.jpg)

![c073115d3e82caaa9146c519d9f79d7ce549c4cbe1237517a74409a8c96de948.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/tables/c073115d3e82caaa9146c519d9f79d7ce549c4cbe1237517a74409a8c96de948.jpg)

![c309f23f4650cf488152f47b7ac79462eea2f345ccff480dc3ed8569c14bd4ed.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/tables/c309f23f4650cf488152f47b7ac79462eea2f345ccff480dc3ed8569c14bd4ed.jpg)

![cdf986778b21c02d8aa342369067fd99305aabdc8ee937ff24f943ac4e311567.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/tables/cdf986778b21c02d8aa342369067fd99305aabdc8ee937ff24f943ac4e311567.jpg)

![f087108e1b1aab3dbf515fc69d35de89835e8966976785be66bd1ef2ec4af488.jpg](../nips_results/514_An%20Evidence-Based%20Post-Hoc%20Adjustment%20Framework%20for%20Anomaly%20Detection%20Under%20Data%20Contamination/tables/f087108e1b1aab3dbf515fc69d35de89835e8966976785be66bd1ef2ec4af488.jpg)

## Flow Equivariant Recurrent Neural Networks


### Images

![09ad6ee7ed08412489ff4c4c77c675285f3d54e81c0f5cce71cc39019d04f0d2.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/09ad6ee7ed08412489ff4c4c77c675285f3d54e81c0f5cce71cc39019d04f0d2.jpg)

![0de360bababdf93ce3dbb1c3b09116b4df1263b719db3e5a02f3b7260b7414f1.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/0de360bababdf93ce3dbb1c3b09116b4df1263b719db3e5a02f3b7260b7414f1.jpg)

![2003969ab3b78d7869c2a730b9b564056c805357c720d14b9134bcc35b1d40db.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/2003969ab3b78d7869c2a730b9b564056c805357c720d14b9134bcc35b1d40db.jpg)

![2e1077b1b888ee8482b9a2881b3fa0a9776d57b56287b339edfc052a4b8ecf80.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/2e1077b1b888ee8482b9a2881b3fa0a9776d57b56287b339edfc052a4b8ecf80.jpg)

![697cbd1029a3c1c584a530183e94865804dde5099bf5b036e1cc4b4d38297053.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/697cbd1029a3c1c584a530183e94865804dde5099bf5b036e1cc4b4d38297053.jpg)

![86510953c4599edbf10812c801f60a54f2d31ab033fbc7fb5b8d3d30402421a1.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/86510953c4599edbf10812c801f60a54f2d31ab033fbc7fb5b8d3d30402421a1.jpg)

![908507791b08fe41ae14feb4c7cac0e2198fc5468de39354a87d36b12d29b9be.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/908507791b08fe41ae14feb4c7cac0e2198fc5468de39354a87d36b12d29b9be.jpg)

![9343d6ceed37be3c506f00f283a58c30d5faad9ca4af95b919cf69988db1773c.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/9343d6ceed37be3c506f00f283a58c30d5faad9ca4af95b919cf69988db1773c.jpg)

![93bda4682c67e0ef1f156d18f5ff6eb670fec9c7f44ee817a15cf6f34603a0be.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/93bda4682c67e0ef1f156d18f5ff6eb670fec9c7f44ee817a15cf6f34603a0be.jpg)

![9988f12a4b8da779feeba8d64a230fcf759c4e210146b0c859f0518f6765d204.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/9988f12a4b8da779feeba8d64a230fcf759c4e210146b0c859f0518f6765d204.jpg)

![9f2d3d1a9a03f425c3dd0c66ecc8b42d5a8404749e85f1853497c581ae210e57.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/9f2d3d1a9a03f425c3dd0c66ecc8b42d5a8404749e85f1853497c581ae210e57.jpg)

![a3b2e283235f612c1785fbe519da1d2819eba66ecd19ad41dae5b5dcdc82167d.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/a3b2e283235f612c1785fbe519da1d2819eba66ecd19ad41dae5b5dcdc82167d.jpg)

![a4badaa28e8392ba82d8713cc5662a8bcaf9c2e739c1485da771066693be93c9.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/a4badaa28e8392ba82d8713cc5662a8bcaf9c2e739c1485da771066693be93c9.jpg)

![ae0753ffce16dfd61f80c232d10d500b0f2c40ca209879dd7ce4cebd2dc1691a.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/ae0753ffce16dfd61f80c232d10d500b0f2c40ca209879dd7ce4cebd2dc1691a.jpg)

![b19ca422345222cf101d266e082b0ed26d947dfa5d463c1ae00e4b870998d86e.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/images/b19ca422345222cf101d266e082b0ed26d947dfa5d463c1ae00e4b870998d86e.jpg)

### Tables

![13cc9cbcb48cff928c0bb47495b77dcab8e828e8a30ed8d682d008c28acaad24.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/tables/13cc9cbcb48cff928c0bb47495b77dcab8e828e8a30ed8d682d008c28acaad24.jpg)

![21c909876265bdd716746dc9226f6f83ffca88b80fed98c3f6bf1e6710d0f64f.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/tables/21c909876265bdd716746dc9226f6f83ffca88b80fed98c3f6bf1e6710d0f64f.jpg)

![2676e87e1ed35dc5795f3c13bc5c7e1e0087a59dcdfceba117f8036a43982d5d.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/tables/2676e87e1ed35dc5795f3c13bc5c7e1e0087a59dcdfceba117f8036a43982d5d.jpg)

![9666b2a9d80da107d734802002e36e4802daecac09f46798e41632e250b29c41.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/tables/9666b2a9d80da107d734802002e36e4802daecac09f46798e41632e250b29c41.jpg)

![bd167fdf62449c73bb050d77107f293d28a033dae297acbd26e84b61ac3725d2.jpg](../nips_results/515_Flow%20Equivariant%20Recurrent%20Neural%20Networks/tables/bd167fdf62449c73bb050d77107f293d28a033dae297acbd26e84b61ac3725d2.jpg)

## Transformers for Mixed-type Event Sequences


### Images

![005d6e5988b5cff556edcd0bbd40d305973567c2909692f6e2af4e88f1be8618.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/images/005d6e5988b5cff556edcd0bbd40d305973567c2909692f6e2af4e88f1be8618.jpg)

![2ac0813af0c44e0372506956d0d9e582c1a7289d6c69df74fc1a46ca2253d029.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/images/2ac0813af0c44e0372506956d0d9e582c1a7289d6c69df74fc1a46ca2253d029.jpg)

![7cc81e7c9d6bef45f92a59c2116d7ea8e0662aa43b21c0ed66125cadb7a80b6a.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/images/7cc81e7c9d6bef45f92a59c2116d7ea8e0662aa43b21c0ed66125cadb7a80b6a.jpg)

![7eaa2da6dde824f3d2a0894d7565332c3d2e4857b56b54d55bdf7a41523e7f9a.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/images/7eaa2da6dde824f3d2a0894d7565332c3d2e4857b56b54d55bdf7a41523e7f9a.jpg)

![88e05a80be03ecb4d61403b291b92ac993f370d2e81dece22fab822a65741294.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/images/88e05a80be03ecb4d61403b291b92ac993f370d2e81dece22fab822a65741294.jpg)

![934dac25a840fe537b2c4d31fba69c3d26ba8bb04148854b4a19a157486149e7.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/images/934dac25a840fe537b2c4d31fba69c3d26ba8bb04148854b4a19a157486149e7.jpg)

![a601a79a09116acad2008b6490f163bb3ddc831e5d29a2930920226c00d36b8d.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/images/a601a79a09116acad2008b6490f163bb3ddc831e5d29a2930920226c00d36b8d.jpg)

![c4d60fc54c4a53a79e0cc71249a6d6ed15b65c1ab1316c2db34686f622e175ac.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/images/c4d60fc54c4a53a79e0cc71249a6d6ed15b65c1ab1316c2db34686f622e175ac.jpg)

![d444577172c25c4f355c508862a820b2b5de9fd6edc3cd3f4b8bcf922904ca8e.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/images/d444577172c25c4f355c508862a820b2b5de9fd6edc3cd3f4b8bcf922904ca8e.jpg)

![dffc5411cdb783d7c90b67f2125434cb6efed67f1ef62c32ef82e8a993712daf.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/images/dffc5411cdb783d7c90b67f2125434cb6efed67f1ef62c32ef82e8a993712daf.jpg)

![e59541e8d0dcbba78e1da31d4850bf0b213c0bcc18565e079d00c711705f34e8.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/images/e59541e8d0dcbba78e1da31d4850bf0b213c0bcc18565e079d00c711705f34e8.jpg)

### Tables

![0f2c4eba6f03b1cebc03000ec2118035ef26bbbc31ea48ddf9e9eb5a6ac9405f.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/0f2c4eba6f03b1cebc03000ec2118035ef26bbbc31ea48ddf9e9eb5a6ac9405f.jpg)

![13576a3cc3c6bb4a4312be551ae6fc231ab933b75b5393734a32a7d6b14bacfa.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/13576a3cc3c6bb4a4312be551ae6fc231ab933b75b5393734a32a7d6b14bacfa.jpg)

![18a6d70f1c636df88b31449edbd6f20efa54178f93e15c97b2f6bb181d394488.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/18a6d70f1c636df88b31449edbd6f20efa54178f93e15c97b2f6bb181d394488.jpg)

![26c4f603aec80785246482d50a8a9719db636aa37ff4955325972b5fecd7ae40.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/26c4f603aec80785246482d50a8a9719db636aa37ff4955325972b5fecd7ae40.jpg)

![471d4e39781249896febf904ab4114f16cc0db950aba600a6cea8803059cf217.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/471d4e39781249896febf904ab4114f16cc0db950aba600a6cea8803059cf217.jpg)

![58f7b88e05ec7502811be628d0e12c30f6483ab80ee106166c6e961ad74d0cd5.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/58f7b88e05ec7502811be628d0e12c30f6483ab80ee106166c6e961ad74d0cd5.jpg)

![65803f6f82b72b601bc7680b6d7c80dabd2c2fe25612d6e6bd609c4ed9f8a7a0.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/65803f6f82b72b601bc7680b6d7c80dabd2c2fe25612d6e6bd609c4ed9f8a7a0.jpg)

![869c80076d56232fad1e60d6dd6ee047cc0e79e35880629c3a6392733ff2c690.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/869c80076d56232fad1e60d6dd6ee047cc0e79e35880629c3a6392733ff2c690.jpg)

![896fa5dc6bed4fa6196a344d1901da287b005dd14e00a0a604b21f1f0ede03e0.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/896fa5dc6bed4fa6196a344d1901da287b005dd14e00a0a604b21f1f0ede03e0.jpg)

![907ffef92597c4c552baab11426227e9be6a41c70626e514319084df0e2c38d7.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/907ffef92597c4c552baab11426227e9be6a41c70626e514319084df0e2c38d7.jpg)

![c2806b8abd6197ceaefb09fda2d02b21a141997b71e432ef06c2cfeec9de5b6e.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/c2806b8abd6197ceaefb09fda2d02b21a141997b71e432ef06c2cfeec9de5b6e.jpg)

![d0dbd0bf57e4ffc67c01a48416653a7f6d2975b2906ab7d4699d4d5f0ad65107.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/d0dbd0bf57e4ffc67c01a48416653a7f6d2975b2906ab7d4699d4d5f0ad65107.jpg)

![dab1a8f7c8bb69e805099ee7ba6ecbb39af15449fefaaaf3184bea32edcb173f.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/dab1a8f7c8bb69e805099ee7ba6ecbb39af15449fefaaaf3184bea32edcb173f.jpg)

![dddc3dfedbb5c49acedcfdad625aa06902249dba06483942142354681bb9fc4f.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/dddc3dfedbb5c49acedcfdad625aa06902249dba06483942142354681bb9fc4f.jpg)

![f3c2c41e1084b92ede2b8994da8c6951f8bb7bbd53a5c2dfa5a291ff0ae23057.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/f3c2c41e1084b92ede2b8994da8c6951f8bb7bbd53a5c2dfa5a291ff0ae23057.jpg)

![f8cd5c2d6d545e25e254a6d14beb31f48c97898c2a5acbddf30edf1eebdac7ed.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/f8cd5c2d6d545e25e254a6d14beb31f48c97898c2a5acbddf30edf1eebdac7ed.jpg)

![fb9e5f52536c010eb2c8246643f2ca39bcb5d8a655df59d68b65e8a60e0d22c0.jpg](../nips_results/516_Transformers%20for%20Mixed-type%20Event%20Sequences/tables/fb9e5f52536c010eb2c8246643f2ca39bcb5d8a655df59d68b65e8a60e0d22c0.jpg)

## ZeroS: Zero‑Sum Linear Attention for Efficient Transformers


### Images

![040be5401b9050733efabebe4a1bf5059290c9a8c10fa34baaec7f60572e6bdb.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/images/040be5401b9050733efabebe4a1bf5059290c9a8c10fa34baaec7f60572e6bdb.jpg)

![44c11e5260329b6901c3345fd61b2772160edf7e634678b3fbfe6a1b90a263c4.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/images/44c11e5260329b6901c3345fd61b2772160edf7e634678b3fbfe6a1b90a263c4.jpg)

![47c8164ce92491496b8a2bcf9fa7ab7edc460fdfd5bd8ef3cf8bab314c81fd4a.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/images/47c8164ce92491496b8a2bcf9fa7ab7edc460fdfd5bd8ef3cf8bab314c81fd4a.jpg)

![880e4e06c64d295f4905bbaf9da84fbc95abe4ba43b56f887d2a762879828159.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/images/880e4e06c64d295f4905bbaf9da84fbc95abe4ba43b56f887d2a762879828159.jpg)

![c6fecbbe1627c368e85b09f96691cff539619778d694a5941c24d0053eb022a5.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/images/c6fecbbe1627c368e85b09f96691cff539619778d694a5941c24d0053eb022a5.jpg)

### Tables

![38553980559b86fe5c7463c32a82e0a285bb6ff4d713ebe491bef6759f66734d.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/tables/38553980559b86fe5c7463c32a82e0a285bb6ff4d713ebe491bef6759f66734d.jpg)

![5ca3684a2a6e801125806fcb8b1d9747e7eb34d613788b30f197a2dcddb2b45c.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/tables/5ca3684a2a6e801125806fcb8b1d9747e7eb34d613788b30f197a2dcddb2b45c.jpg)

![73f08277493e168aa32e10a33ead205a8dd7356c4e1b8ae0ef0e70e8ca720761.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/tables/73f08277493e168aa32e10a33ead205a8dd7356c4e1b8ae0ef0e70e8ca720761.jpg)

![7770182d958e8989a380b5033c2138cde54ae45beb7a8666098a0d7a50cb614e.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/tables/7770182d958e8989a380b5033c2138cde54ae45beb7a8666098a0d7a50cb614e.jpg)

![84258d3a820b547abbb48cc3d9161a2e286d7ba362b1f09b0d672d16122cb345.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/tables/84258d3a820b547abbb48cc3d9161a2e286d7ba362b1f09b0d672d16122cb345.jpg)

![9cd3e32ef80cd7429be06ad86740d46af084d85185bea92283cf59fa3c09ae63.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/tables/9cd3e32ef80cd7429be06ad86740d46af084d85185bea92283cf59fa3c09ae63.jpg)

![9d3d45d21e55ff109d33c3789a6a94c515f8ea5ced4ff79715cb9c949548a18d.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/tables/9d3d45d21e55ff109d33c3789a6a94c515f8ea5ced4ff79715cb9c949548a18d.jpg)

![a66fede500c2a7bd4b92b53c8066b3cbdfb79f15a82bfffc82840438925fe64c.jpg](../nips_results/517_ZeroS_%20Zero%E2%80%91Sum%20Linear%20Attention%20for%20Efficient%20Transformers/tables/a66fede500c2a7bd4b92b53c8066b3cbdfb79f15a82bfffc82840438925fe64c.jpg)

## Protein Design with Dynamic Protein Vocabulary


### Images

![01f5ae87cb9f8c27288210e1cb96ed39202b54d84d97c03ac602fd2fb935ab50.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/01f5ae87cb9f8c27288210e1cb96ed39202b54d84d97c03ac602fd2fb935ab50.jpg)

![0907ec038626005d8df9d1b98b8eec63e929d4c0058073081b8f71fb8e237c34.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/0907ec038626005d8df9d1b98b8eec63e929d4c0058073081b8f71fb8e237c34.jpg)

![1217b44c206214f3178c28ebf220299b23e963b2ed8d082afc9cf9326327edb1.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/1217b44c206214f3178c28ebf220299b23e963b2ed8d082afc9cf9326327edb1.jpg)

![233bef4188cc31737192e752a7c9f50aa49361e2d2a7e51038f9f6ff23e8494e.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/233bef4188cc31737192e752a7c9f50aa49361e2d2a7e51038f9f6ff23e8494e.jpg)

![33198a3c60ae6dcfa5af97d716fdb89dc917e75e61bb0e575b880defdc60f227.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/33198a3c60ae6dcfa5af97d716fdb89dc917e75e61bb0e575b880defdc60f227.jpg)

![4c9de54935cae50d69b933d2ce2c23e8432652a54e6cfb3646d1e6e5d119f85a.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/4c9de54935cae50d69b933d2ce2c23e8432652a54e6cfb3646d1e6e5d119f85a.jpg)

![52a985f105ce8ff396a68f1eebeba316df12c35fe4825f37891d07f0611344fc.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/52a985f105ce8ff396a68f1eebeba316df12c35fe4825f37891d07f0611344fc.jpg)

![6b067a67b971982f7ffbe939f2794314387c5a8755b53ccec19188a00d14561f.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/6b067a67b971982f7ffbe939f2794314387c5a8755b53ccec19188a00d14561f.jpg)

![6c63e21b8969bf642dcfab5e532cb7edcbcc6e83a7b16499efb8e5a0397408be.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/6c63e21b8969bf642dcfab5e532cb7edcbcc6e83a7b16499efb8e5a0397408be.jpg)

![847b9060c085e6770d99fcaebabf3e100c45cef3ccaf74d73967d30cb4e92132.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/847b9060c085e6770d99fcaebabf3e100c45cef3ccaf74d73967d30cb4e92132.jpg)

![8a816e8dd7d4dff655ab89cc712d56ad758f3ad53edef47c64531a7868e86c0f.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/8a816e8dd7d4dff655ab89cc712d56ad758f3ad53edef47c64531a7868e86c0f.jpg)

![a0e3c2a3a981bde76772126f82a61ac63d8ba9959e251f3ce9f69354426d6daa.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/a0e3c2a3a981bde76772126f82a61ac63d8ba9959e251f3ce9f69354426d6daa.jpg)

![a47ea1add37d9fa5d55bfd3f3c37ecb0231ec223fbbae70504cd9db27b74d2ec.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/a47ea1add37d9fa5d55bfd3f3c37ecb0231ec223fbbae70504cd9db27b74d2ec.jpg)

![c2bc5d5be0b60d94a808400b138b2b2fceb48d26140b9f327503fc61b223070b.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/c2bc5d5be0b60d94a808400b138b2b2fceb48d26140b9f327503fc61b223070b.jpg)

![e741e70ca203dd0a2d2f81d1009b8a77541b74019bb54cffefc073f519c1c7ac.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/e741e70ca203dd0a2d2f81d1009b8a77541b74019bb54cffefc073f519c1c7ac.jpg)

![ec4ae2d9f4332a729c0884e33ef3e353ed08ffdf031e4c820ba8ad51d05a9af5.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/ec4ae2d9f4332a729c0884e33ef3e353ed08ffdf031e4c820ba8ad51d05a9af5.jpg)

![f269d78f130d2c59f28002a907d73196510eabdacaf992a86556d6ec42d708fa.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/f269d78f130d2c59f28002a907d73196510eabdacaf992a86556d6ec42d708fa.jpg)

![fd6b4efcc0dc0f4164a2cf1fb5142d5b345f22f120ef34b9a061ec428c90f547.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/images/fd6b4efcc0dc0f4164a2cf1fb5142d5b345f22f120ef34b9a061ec428c90f547.jpg)

### Tables

![16c197770dbde63c2c40b3777ae15443f49490359e647fb56a5730264d07c54d.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/tables/16c197770dbde63c2c40b3777ae15443f49490359e647fb56a5730264d07c54d.jpg)

![30dc7de8b4dfbbb916a1287107fe829635ef66bba17397047d6969ec7483ea5f.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/tables/30dc7de8b4dfbbb916a1287107fe829635ef66bba17397047d6969ec7483ea5f.jpg)

![6818f628f99194a2386bf99b49707bcf9936dcb31b6a5a99199ab0afd94597b3.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/tables/6818f628f99194a2386bf99b49707bcf9936dcb31b6a5a99199ab0afd94597b3.jpg)

![8ffb2c5247f14159e198162df869dfd54be5c1d353f5bce89d7698f7066a7577.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/tables/8ffb2c5247f14159e198162df869dfd54be5c1d353f5bce89d7698f7066a7577.jpg)

![96a8cbfc852f1a52ddf17476fae10261272e4c7499836ad44d4f77f0cb4768da.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/tables/96a8cbfc852f1a52ddf17476fae10261272e4c7499836ad44d4f77f0cb4768da.jpg)

![f7f7084c380fa764b3198acb08151fdc60eca19bc1faaa8be7f68a3c08035f6c.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/tables/f7f7084c380fa764b3198acb08151fdc60eca19bc1faaa8be7f68a3c08035f6c.jpg)

![fb60a58278ca6d807cd763f5667c650e01844940e3dd16ee8e04a5a36e2b5a9b.jpg](../nips_results/518_Protein%20Design%20with%20Dynamic%20Protein%20Vocabulary/tables/fb60a58278ca6d807cd763f5667c650e01844940e3dd16ee8e04a5a36e2b5a9b.jpg)

## Privacy amplification by random allocation


### Images

![0b887642746a5b8e219e4ab088c6ecc3d6440d7cffdac1e9f9a134a46ea83b34.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/0b887642746a5b8e219e4ab088c6ecc3d6440d7cffdac1e9f9a134a46ea83b34.jpg)

![24274a519a0fe8b49a621dec61a580e5adf89da9036409104bbeab6921aa205c.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/24274a519a0fe8b49a621dec61a580e5adf89da9036409104bbeab6921aa205c.jpg)

![46a7b6516da4d3a21016bd2cc73c6d82e1f1abc82b183cd988973e87bc906235.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/46a7b6516da4d3a21016bd2cc73c6d82e1f1abc82b183cd988973e87bc906235.jpg)

![52b73202aace27a2915167b3e8965f42d5edae58b093e4238a4d42edd63e38d4.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/52b73202aace27a2915167b3e8965f42d5edae58b093e4238a4d42edd63e38d4.jpg)

![6b4d9d58a1e61e9b0dac8b6383d312802d152e5b22bd790a5d06101e8f3bf5c5.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/6b4d9d58a1e61e9b0dac8b6383d312802d152e5b22bd790a5d06101e8f3bf5c5.jpg)

![946f81a8a539bb11925c8278f7de943020b532686e0a7f5aded9dfaed2c7b9ad.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/946f81a8a539bb11925c8278f7de943020b532686e0a7f5aded9dfaed2c7b9ad.jpg)

![ae7167a01c4ae9b6af0e0cd08bfb6d3dbd4db1f6be566a76fd953b4989695211.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/ae7167a01c4ae9b6af0e0cd08bfb6d3dbd4db1f6be566a76fd953b4989695211.jpg)

![c48f5b8939a2caafb2c6a166a8f8494069dee0c16a120bd681fb813fbc84d4ff.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/c48f5b8939a2caafb2c6a166a8f8494069dee0c16a120bd681fb813fbc84d4ff.jpg)

![cd013265e2b0c796483016bfd021e1fb334ccc856dc819f9ff49fd67351d9352.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/cd013265e2b0c796483016bfd021e1fb334ccc856dc819f9ff49fd67351d9352.jpg)

![d00ee26010d131208f44afbf3c0ccc49404b581e2372c87da5529bd394ec400e.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/d00ee26010d131208f44afbf3c0ccc49404b581e2372c87da5529bd394ec400e.jpg)

![eb68ba210e74232fff142dc499724b813c1cba5162825079a4fb6544a22720c0.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/eb68ba210e74232fff142dc499724b813c1cba5162825079a4fb6544a22720c0.jpg)

![f262fd9be6c703f50942aae5efd3231560b467723350722b7fa358ddda049611.jpg](../nips_results/519_Privacy%20amplification%20by%20random%20allocation/images/f262fd9be6c703f50942aae5efd3231560b467723350722b7fa358ddda049611.jpg)

## Diffusion-Based Hierarchical Graph Neural Networks for Simulating Nonlinear Solid Mechanics


### Images

![0bf6f99edc12a61433fd538986b58421ca7f3b2af89032cd129853e08f68046e.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/0bf6f99edc12a61433fd538986b58421ca7f3b2af89032cd129853e08f68046e.jpg)

![17905ad2d1ab3d3584daea7ffd87b4bc3cf80082832a99a7a81e8b4e456c070a.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/17905ad2d1ab3d3584daea7ffd87b4bc3cf80082832a99a7a81e8b4e456c070a.jpg)

![23a82720a4a47ddfa68bc92a093c1cbb10aa020d53bc4d194bd42348a6b42dea.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/23a82720a4a47ddfa68bc92a093c1cbb10aa020d53bc4d194bd42348a6b42dea.jpg)

![2c517e8d5ba67e463c86ab98fe27f918b8a531c5544793e1d8e9cbe30c3eb435.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/2c517e8d5ba67e463c86ab98fe27f918b8a531c5544793e1d8e9cbe30c3eb435.jpg)

![30d82a7f0d1196432580cbb3319ef980fd7497d535a1cb136cbaee2749600e78.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/30d82a7f0d1196432580cbb3319ef980fd7497d535a1cb136cbaee2749600e78.jpg)

![4fe367fb6d51d13aa51115aed4ddcef745897cb145f369824d447f31ab7f7e8b.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/4fe367fb6d51d13aa51115aed4ddcef745897cb145f369824d447f31ab7f7e8b.jpg)

![52d5c315ddcfca46c9af6bbee2c42235194bf0b22c61e4421e182c4537081f04.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/52d5c315ddcfca46c9af6bbee2c42235194bf0b22c61e4421e182c4537081f04.jpg)

![5f2068b5ce7018cc779f53ea2d072e3bd559a0e45c0cf7796aeb2298b3a8296a.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/5f2068b5ce7018cc779f53ea2d072e3bd559a0e45c0cf7796aeb2298b3a8296a.jpg)

![62d7feab332751a351a4f94fc55abeec2c2810564014c3f15731dd2bca62221a.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/62d7feab332751a351a4f94fc55abeec2c2810564014c3f15731dd2bca62221a.jpg)

![9543c65d843db58d5618c08f11f9997a16e462d96370aebde6f15c0bbdce9f58.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/9543c65d843db58d5618c08f11f9997a16e462d96370aebde6f15c0bbdce9f58.jpg)

![9fcf2a656f1c33bed0af5fad96bdc1e8c16d59e711f2e8caaecb1c91a3228282.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/9fcf2a656f1c33bed0af5fad96bdc1e8c16d59e711f2e8caaecb1c91a3228282.jpg)

![a65c63f90dc54b2af2c4ec3d923f46858f607c619992c7c2e2ef8ee151ee5d7a.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/a65c63f90dc54b2af2c4ec3d923f46858f607c619992c7c2e2ef8ee151ee5d7a.jpg)

![e9a54b729c915c9bb820e75d040cfae6ca88bdb803d19738a9a35ed376999c1e.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/e9a54b729c915c9bb820e75d040cfae6ca88bdb803d19738a9a35ed376999c1e.jpg)

![ed48183142a379dd0df69525fbe2b68cd4fd5b153fa7ad0721675a4c96831234.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/ed48183142a379dd0df69525fbe2b68cd4fd5b153fa7ad0721675a4c96831234.jpg)

![f6b1f0b0c2a59ce55ece9cbc924bf9a24754653338fbe85a4dbf09942313e19f.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/images/f6b1f0b0c2a59ce55ece9cbc924bf9a24754653338fbe85a4dbf09942313e19f.jpg)

### Tables

![a94be05adadff80e966e873da5017e2d9cb84597a20123236c38d838bc74e166.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/tables/a94be05adadff80e966e873da5017e2d9cb84597a20123236c38d838bc74e166.jpg)

![bbb48306bd63c978667d73199db98855fa7cc27e2292e0f2e6b13f7ff910e538.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/tables/bbb48306bd63c978667d73199db98855fa7cc27e2292e0f2e6b13f7ff910e538.jpg)

![ea206ce3ab9672d4eafd6642ecff5eb27dc690d4a685cdd5f6ca9c4fbcaeeb5a.jpg](../nips_results/520_Diffusion-Based%20Hierarchical%20Graph%20Neural%20Networks%20for%20Simulating%20Nonlinear%20Solid%20Mechanics/tables/ea206ce3ab9672d4eafd6642ecff5eb27dc690d4a685cdd5f6ca9c4fbcaeeb5a.jpg)

## Uncertain Knowledge Graph Completion via Semi-Supervised Confidence Distribution Learning


### Images

![04526146de4981901300eae76dc40e7434cdfa1b98217e47fdd41e9d9e6cd554.jpg](../nips_results/522_Uncertain%20Knowledge%20Graph%20Completion%20via%20Semi-Supervised%20Confidence%20Distribution%20Learning/images/04526146de4981901300eae76dc40e7434cdfa1b98217e47fdd41e9d9e6cd554.jpg)

![1129fd6fc0dbcc3f601c805a187064ab358f104bc053781bbf74bf1077deb96c.jpg](../nips_results/522_Uncertain%20Knowledge%20Graph%20Completion%20via%20Semi-Supervised%20Confidence%20Distribution%20Learning/images/1129fd6fc0dbcc3f601c805a187064ab358f104bc053781bbf74bf1077deb96c.jpg)

![1700599a0f91ab1ed82c3458764aa277529b4dfbae3f4f3e6ba532409f033e40.jpg](../nips_results/522_Uncertain%20Knowledge%20Graph%20Completion%20via%20Semi-Supervised%20Confidence%20Distribution%20Learning/images/1700599a0f91ab1ed82c3458764aa277529b4dfbae3f4f3e6ba532409f033e40.jpg)

![31ccd9ffba79983ba7ae7fc50bbe109ba8830220299486e341fdb4acdbe49a4f.jpg](../nips_results/522_Uncertain%20Knowledge%20Graph%20Completion%20via%20Semi-Supervised%20Confidence%20Distribution%20Learning/images/31ccd9ffba79983ba7ae7fc50bbe109ba8830220299486e341fdb4acdbe49a4f.jpg)

![3792d52f540c8d8f38a2811f7587d39a902406ffa9ea465f4f7aa90d17c6ae6b.jpg](../nips_results/522_Uncertain%20Knowledge%20Graph%20Completion%20via%20Semi-Supervised%20Confidence%20Distribution%20Learning/images/3792d52f540c8d8f38a2811f7587d39a902406ffa9ea465f4f7aa90d17c6ae6b.jpg)

### Tables

![2e531f85e5c70b2a6b1c10b9e32db02f8baef325189a9c77b726f39e1759cb94.jpg](../nips_results/522_Uncertain%20Knowledge%20Graph%20Completion%20via%20Semi-Supervised%20Confidence%20Distribution%20Learning/tables/2e531f85e5c70b2a6b1c10b9e32db02f8baef325189a9c77b726f39e1759cb94.jpg)

![6f79c600766ad1f730212d2094f278e6df9f25017cf3db64e3caf4d144c26b88.jpg](../nips_results/522_Uncertain%20Knowledge%20Graph%20Completion%20via%20Semi-Supervised%20Confidence%20Distribution%20Learning/tables/6f79c600766ad1f730212d2094f278e6df9f25017cf3db64e3caf4d144c26b88.jpg)

![919453dec6e40dc0459261852f888f7a89c62ed03bc1a818e96bbc0ce9f5a70a.jpg](../nips_results/522_Uncertain%20Knowledge%20Graph%20Completion%20via%20Semi-Supervised%20Confidence%20Distribution%20Learning/tables/919453dec6e40dc0459261852f888f7a89c62ed03bc1a818e96bbc0ce9f5a70a.jpg)

## Lost in Transmission: When and Why LLMs Fail to Reason Globally


### Images

![0864ba875337a96b5b842d9e32e11436527da6992a1190380b2fa51929b9f5cf.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/0864ba875337a96b5b842d9e32e11436527da6992a1190380b2fa51929b9f5cf.jpg)

![145b876f85023266099119dfa03b647a42ecdc56a59282c46ad84fdd18b7e21a.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/145b876f85023266099119dfa03b647a42ecdc56a59282c46ad84fdd18b7e21a.jpg)

![29afd3274cf684d4956fe66f6662891396e296631f93ceb78f81f39343964b15.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/29afd3274cf684d4956fe66f6662891396e296631f93ceb78f81f39343964b15.jpg)

![459a7265105aa97692626e1333e555e33f1910d09f38d8950164c5495a37bba8.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/459a7265105aa97692626e1333e555e33f1910d09f38d8950164c5495a37bba8.jpg)

![69ef16d5b30d211559d11b24c67a12e77513d37c46b93055c0be7f9adf2cb178.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/69ef16d5b30d211559d11b24c67a12e77513d37c46b93055c0be7f9adf2cb178.jpg)

![7d700f9dfed6afdb8ba1eebdd8c7b7230e4992c9f863e06756030c066a499c2a.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/7d700f9dfed6afdb8ba1eebdd8c7b7230e4992c9f863e06756030c066a499c2a.jpg)

![8159ec0eb25f9f8096e2f89fa77bab0a07428c2931a5a9095bdf55793b913a0f.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/8159ec0eb25f9f8096e2f89fa77bab0a07428c2931a5a9095bdf55793b913a0f.jpg)

![8217dfe19aeb364f65d2cd0792317b459468e635cfd8ac3646ce95424afc4ac0.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/8217dfe19aeb364f65d2cd0792317b459468e635cfd8ac3646ce95424afc4ac0.jpg)

![95967f226fcd913c3bd7d988451db27cf3152ae35729d81a42eca72fb4d64e41.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/95967f226fcd913c3bd7d988451db27cf3152ae35729d81a42eca72fb4d64e41.jpg)

![9e5aa3855d4b17b5d1580beacea2ccb570762e1aeaf92d0a046fd0d0c0d36d44.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/9e5aa3855d4b17b5d1580beacea2ccb570762e1aeaf92d0a046fd0d0c0d36d44.jpg)

![9fdb258bb05e6a95bec5fd5b77134498872b584632c96973d837809d30593148.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/9fdb258bb05e6a95bec5fd5b77134498872b584632c96973d837809d30593148.jpg)

![a433bbe7a63af3f8e9eb266e5b5b54d45df889e7af73885cd4fb8c1ff1f0260a.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/a433bbe7a63af3f8e9eb266e5b5b54d45df889e7af73885cd4fb8c1ff1f0260a.jpg)

![d3fb164bb1dfd82db8e22d04f1b0174662a5ce0133e72a9bcdb78603c7c217d4.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/d3fb164bb1dfd82db8e22d04f1b0174662a5ce0133e72a9bcdb78603c7c217d4.jpg)

![e9126c11ba22631a512503e742338decd27617ec7ef630058b16eade1e7e862e.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/images/e9126c11ba22631a512503e742338decd27617ec7ef630058b16eade1e7e862e.jpg)

### Tables

![3ab7415f57315b4bed94a82b477b0084fd4601d4120a9e051cad3a13a023bbf2.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/tables/3ab7415f57315b4bed94a82b477b0084fd4601d4120a9e051cad3a13a023bbf2.jpg)

![3c484335c3df89e84c6a9c03924360967e23ebeaecf0e2089646f1c3130f811f.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/tables/3c484335c3df89e84c6a9c03924360967e23ebeaecf0e2089646f1c3130f811f.jpg)

![3d292ea09542cf935841cdd5e59f64f90d01a165c18c85f0c5341d4598e79524.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/tables/3d292ea09542cf935841cdd5e59f64f90d01a165c18c85f0c5341d4598e79524.jpg)

![c2ebfba28b5341838711eac678943bb4b76822e4375b5f4c0c6db2009361d7fb.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/tables/c2ebfba28b5341838711eac678943bb4b76822e4375b5f4c0c6db2009361d7fb.jpg)

![fe17762178a191f1e09a52240c27aab4028f6b60e02695c5c08fbb5fa800c7b2.jpg](../nips_results/523_Lost%20in%20Transmission_%20When%20and%20Why%20LLMs%20Fail%20to%20Reason%20Globally/tables/fe17762178a191f1e09a52240c27aab4028f6b60e02695c5c08fbb5fa800c7b2.jpg)

## JavisGPT: A Unified Multi-modal LLM for Sounding-Video Comprehension and Generation


### Images

![0b294f0c28031d606f92eea5703c84fc1f0585825286de2d7944ecf6d0eaf226.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/0b294f0c28031d606f92eea5703c84fc1f0585825286de2d7944ecf6d0eaf226.jpg)

![1d01cbcfddf1401acba9bbe1b42e8fe0797429d681fd0a96bb8c9ce40a4a4689.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/1d01cbcfddf1401acba9bbe1b42e8fe0797429d681fd0a96bb8c9ce40a4a4689.jpg)

![21b333dccf3698a7805e1f9694e9e22933ae3eeebf9811290b81253e49595c8d.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/21b333dccf3698a7805e1f9694e9e22933ae3eeebf9811290b81253e49595c8d.jpg)

![4d5487d90e4b9daa45f1252a09bdd90296e42b815855e0c83d3f85716f7e302b.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/4d5487d90e4b9daa45f1252a09bdd90296e42b815855e0c83d3f85716f7e302b.jpg)

![5e4278ce2b43f23315e23b5889a68a41db049ad3e4dd787341cac83ac4a18137.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/5e4278ce2b43f23315e23b5889a68a41db049ad3e4dd787341cac83ac4a18137.jpg)

![a80ba820aba1c160fdbcb28675928c32ccd6172c3b11a55b1a74a7157cc76bf7.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/a80ba820aba1c160fdbcb28675928c32ccd6172c3b11a55b1a74a7157cc76bf7.jpg)

![b6805681c55a9359680b0c3c9fea4ca6cd3de0b46fab6f28c488d4a2a23392c5.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/b6805681c55a9359680b0c3c9fea4ca6cd3de0b46fab6f28c488d4a2a23392c5.jpg)

![bc7832a49f9494791666bd6cd8bd6e77a1927b9d7c032d37167db6438d53d12d.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/bc7832a49f9494791666bd6cd8bd6e77a1927b9d7c032d37167db6438d53d12d.jpg)

![bd845c3624730e242fd3898c2258cc8deabd77211779f3d2086ca9a7d7e8c9be.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/bd845c3624730e242fd3898c2258cc8deabd77211779f3d2086ca9a7d7e8c9be.jpg)

![ca0805b6673feec9a386abb6b2e7cd62006c49d75a602bd361bf6dbc8709340d.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/ca0805b6673feec9a386abb6b2e7cd62006c49d75a602bd361bf6dbc8709340d.jpg)

![cda3323be570a33630f1a2729f998ea67b1abe96b9b858864d2139407651b87a.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/cda3323be570a33630f1a2729f998ea67b1abe96b9b858864d2139407651b87a.jpg)

![e094b35ff7049c4b051c2235b3ef2d9d4d316e230df6b3a118458e5ba0544bbc.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/e094b35ff7049c4b051c2235b3ef2d9d4d316e230df6b3a118458e5ba0544bbc.jpg)

![fd3ea803f6d06b8b7cf257965ca2fa1320fb1c00e595661b84d48b4ff5e42bf4.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/fd3ea803f6d06b8b7cf257965ca2fa1320fb1c00e595661b84d48b4ff5e42bf4.jpg)

![fd58531d8b4616b362697a5298c9794b09f4797c195a9eedb298771c9d9e50a1.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/images/fd58531d8b4616b362697a5298c9794b09f4797c195a9eedb298771c9d9e50a1.jpg)

### Tables

![4bfd78c47182fa4cf4c2969ebdaee7c56c15be2b74879c792268a2ad3a9b1c07.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/tables/4bfd78c47182fa4cf4c2969ebdaee7c56c15be2b74879c792268a2ad3a9b1c07.jpg)

![58bd9781da89e4a1389cb8c7379ce553b627f8414d6347e9182faa0f15eb213c.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/tables/58bd9781da89e4a1389cb8c7379ce553b627f8414d6347e9182faa0f15eb213c.jpg)

![684978b2aed961d48770e1f74b35366e5c0fb6c19acdc4ef3259b7d0e6f0091e.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/tables/684978b2aed961d48770e1f74b35366e5c0fb6c19acdc4ef3259b7d0e6f0091e.jpg)

![72c34613600c2a56af1321d56e0461768aec5af3f8371a1c3c4d3f5a8bb454da.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/tables/72c34613600c2a56af1321d56e0461768aec5af3f8371a1c3c4d3f5a8bb454da.jpg)

![8c809064c8eb9aadfbb523b3b75c51b4a7d301a375897c86ebe77456b7e41f93.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/tables/8c809064c8eb9aadfbb523b3b75c51b4a7d301a375897c86ebe77456b7e41f93.jpg)

![c7f388f290e30a6d3771e2d40ffd5a8ac59f888a8490fc4a1a4a04e97fab4e3d.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/tables/c7f388f290e30a6d3771e2d40ffd5a8ac59f888a8490fc4a1a4a04e97fab4e3d.jpg)

![ce9b3fc5b71b45e8b19ba89e5b7adccbc4388406ed02e5c84aaa51145ac474e0.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/tables/ce9b3fc5b71b45e8b19ba89e5b7adccbc4388406ed02e5c84aaa51145ac474e0.jpg)

![e3cafe451c40a34793813ba6ab5752766fc53e4b4756c2e6e9111e21b0eb560a.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/tables/e3cafe451c40a34793813ba6ab5752766fc53e4b4756c2e6e9111e21b0eb560a.jpg)

![e7eb7c1ed8cae60b0acef2bcecf1f1f0495ba28629ff6ecc8c6d6e0e0c5de6fb.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/tables/e7eb7c1ed8cae60b0acef2bcecf1f1f0495ba28629ff6ecc8c6d6e0e0c5de6fb.jpg)

![eba50feb37163b71af3fc20831e84fb15ed4285fbb0a4aca25863473763fad5a.jpg](../nips_results/524_JavisGPT_%20A%20Unified%20Multi-modal%20LLM%20for%20Sounding-Video%20Comprehension%20and%20Generation/tables/eba50feb37163b71af3fc20831e84fb15ed4285fbb0a4aca25863473763fad5a.jpg)

## Ambient Diffusion Omni: Training Good Models with Bad Data


### Images

![00b0e56d17473a96fe1d9690a09dde391ce27c483bd24551d05a887f44727b8b.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/00b0e56d17473a96fe1d9690a09dde391ce27c483bd24551d05a887f44727b8b.jpg)

![08e56c30fea36e9c8f4d9540b74bbf513895c30bf28686d6a0fb64d44772620f.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/08e56c30fea36e9c8f4d9540b74bbf513895c30bf28686d6a0fb64d44772620f.jpg)

![1e1656ef12d8864314197e1424ba858e796e3e928acee2a7e6669eee25209da3.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/1e1656ef12d8864314197e1424ba858e796e3e928acee2a7e6669eee25209da3.jpg)

![29b4533fbae0cdf475bb494a86812fb71f7dd222504dbdc55234a376b4b2e86a.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/29b4533fbae0cdf475bb494a86812fb71f7dd222504dbdc55234a376b4b2e86a.jpg)

![32c0021f24301a369da317ce0777674c42b79dac88e165186b56d79cf4e253a8.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/32c0021f24301a369da317ce0777674c42b79dac88e165186b56d79cf4e253a8.jpg)

![33b51e80b2afbf73a66573fa32e302596684e9ad7a06ed9c0b14af77b7411831.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/33b51e80b2afbf73a66573fa32e302596684e9ad7a06ed9c0b14af77b7411831.jpg)

![4034aa828b874662377b8ecff666c150def1bfbe2b8750fc0dd98c4868f28d8e.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/4034aa828b874662377b8ecff666c150def1bfbe2b8750fc0dd98c4868f28d8e.jpg)

![4838722a5a7014749dc80edcf619164cf0914da428f7f7bfa3444888438dc535.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/4838722a5a7014749dc80edcf619164cf0914da428f7f7bfa3444888438dc535.jpg)

![493788f446a068dd37821348a939aa89e57df085d0be518e1519cdaeb9223f95.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/493788f446a068dd37821348a939aa89e57df085d0be518e1519cdaeb9223f95.jpg)

![4e532b2d216a80435153974b10ab0e20bcfa6309c7224dd949e117bff38bb28f.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/4e532b2d216a80435153974b10ab0e20bcfa6309c7224dd949e117bff38bb28f.jpg)

![54f16ee4908088e9d2e32515faae1c8de512c577fd216e555034991d243efa41.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/54f16ee4908088e9d2e32515faae1c8de512c577fd216e555034991d243efa41.jpg)

![5b90dc95b6f553e1a3796c17436b2e201333047833d66f5c93a16e41f61b9e0a.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/5b90dc95b6f553e1a3796c17436b2e201333047833d66f5c93a16e41f61b9e0a.jpg)

![5d4075843a15c2084cf492b11a49b2a09520c9f5766c6585a727602ae559b351.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/5d4075843a15c2084cf492b11a49b2a09520c9f5766c6585a727602ae559b351.jpg)

![5ee09e3b33cb986f1617a74990c4e5487c22f14eaa3b812c73f8c0d103a870a2.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/5ee09e3b33cb986f1617a74990c4e5487c22f14eaa3b812c73f8c0d103a870a2.jpg)

![63bb1527535ffd3f6f2dd301643dcb4093a6a9e61498fd43cbf92603e426b788.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/63bb1527535ffd3f6f2dd301643dcb4093a6a9e61498fd43cbf92603e426b788.jpg)

![64889c3178b37166072220ade0e76004ab3e6de103b7fd5fe6a18477a007f358.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/64889c3178b37166072220ade0e76004ab3e6de103b7fd5fe6a18477a007f358.jpg)

![64ab1ef8f5cf50434a64f2714687d1928b2b2968ab09bc1801c7f545ba740e4d.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/64ab1ef8f5cf50434a64f2714687d1928b2b2968ab09bc1801c7f545ba740e4d.jpg)

![711c2a0c5eb2613f554261f573e98bb2db8e1ce75ac35a8c363ed31b96e2acdb.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/711c2a0c5eb2613f554261f573e98bb2db8e1ce75ac35a8c363ed31b96e2acdb.jpg)

![7238313427e00a9fa8f035898cffb940943f8369595653197fee8e8718c65a25.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/7238313427e00a9fa8f035898cffb940943f8369595653197fee8e8718c65a25.jpg)

![7570678be8cca782b04040fa0f98bbd3980502b570c832e5552798516618c3e8.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/7570678be8cca782b04040fa0f98bbd3980502b570c832e5552798516618c3e8.jpg)

![7911164a0ba9db276c7d60f9980f8735131ed6abe2ffb5956f01e3a68b2fd5dc.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/7911164a0ba9db276c7d60f9980f8735131ed6abe2ffb5956f01e3a68b2fd5dc.jpg)

![7cee0d5c3b88c586d701d7bee917acfdd24a79f0ea3e7ec04bbdfdb9584c4fe0.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/7cee0d5c3b88c586d701d7bee917acfdd24a79f0ea3e7ec04bbdfdb9584c4fe0.jpg)

![9ff13b24f36d669530c2b04bb1bc9ab298f47b2ee9e5f49dd9cecc4f572e9c45.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/9ff13b24f36d669530c2b04bb1bc9ab298f47b2ee9e5f49dd9cecc4f572e9c45.jpg)

![a159b542afc015deaa467458131be69386c495f5c3cc830635d2b715e6bccb2c.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/a159b542afc015deaa467458131be69386c495f5c3cc830635d2b715e6bccb2c.jpg)

![a73542d38b099c5cf8d01b3ea9902d3f349f12f4f41c35d484f4490b798ec636.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/a73542d38b099c5cf8d01b3ea9902d3f349f12f4f41c35d484f4490b798ec636.jpg)

![a768a2ea1b16af886bf685944890c517a5c97198cd4fd965b9882aa300c2f888.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/a768a2ea1b16af886bf685944890c517a5c97198cd4fd965b9882aa300c2f888.jpg)

![a9abc8edc320a808477e7fdb34acdef5702bff72f3e3cac811a1c7db49f385f5.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/a9abc8edc320a808477e7fdb34acdef5702bff72f3e3cac811a1c7db49f385f5.jpg)

![aa8e0c28359990d0fd5b6c04aeba864d80351cb17a093e1a2a1775eb1d723194.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/aa8e0c28359990d0fd5b6c04aeba864d80351cb17a093e1a2a1775eb1d723194.jpg)

![ae8156477e1bbd40c6634d69488b9bd5391beb2ba78652e3773aff3da1ee5aae.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/ae8156477e1bbd40c6634d69488b9bd5391beb2ba78652e3773aff3da1ee5aae.jpg)

![b3117f652b6dffb61fa8588bb08f6de9e751d57f0e2cdf538960146a9ffa8b70.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/b3117f652b6dffb61fa8588bb08f6de9e751d57f0e2cdf538960146a9ffa8b70.jpg)

![b8719e98c9be0dfc2ce5e0f7c6f097baca1e99bb78fc4afc12967a1c8b977554.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/b8719e98c9be0dfc2ce5e0f7c6f097baca1e99bb78fc4afc12967a1c8b977554.jpg)

![bfa4731c938139b6f24a3d8fd82812ebbfe213c5c67fd9b7da10ada25720afb7.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/bfa4731c938139b6f24a3d8fd82812ebbfe213c5c67fd9b7da10ada25720afb7.jpg)

![c1c90e424dea728b2152d32c3d69be04ecfd60738176ffcb505a02c471ccb933.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/c1c90e424dea728b2152d32c3d69be04ecfd60738176ffcb505a02c471ccb933.jpg)

![c45699cf7ebc42784dff628fa4a21a1dbddb12688b5de69d063e049af00918eb.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/c45699cf7ebc42784dff628fa4a21a1dbddb12688b5de69d063e049af00918eb.jpg)

![c6ee67833fa5ea94a1c94e5237506655fede4f26f8b5c102cabe6e3ac22e192f.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/c6ee67833fa5ea94a1c94e5237506655fede4f26f8b5c102cabe6e3ac22e192f.jpg)

![c745cb51daa5e4f7aa332ccd34300877539d95bd112e1d318f9fa81d292153f5.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/c745cb51daa5e4f7aa332ccd34300877539d95bd112e1d318f9fa81d292153f5.jpg)

![d067d93b60ba80715783efb6407b042fe0d58947e0f8633e2507c8d675fb655e.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/d067d93b60ba80715783efb6407b042fe0d58947e0f8633e2507c8d675fb655e.jpg)

![d40e33c321ca30d1615ba9687c5d7663bb5270ca5ebe05c92295779c21232fae.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/d40e33c321ca30d1615ba9687c5d7663bb5270ca5ebe05c92295779c21232fae.jpg)

![da3fb825adfedb23ef4883c160c58dbd0156dd627f44ff7a149a04828110f59b.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/images/da3fb825adfedb23ef4883c160c58dbd0156dd627f44ff7a149a04828110f59b.jpg)

### Tables

![0249bd2f0503eac4ec00b0be2df11f9fe5de80394bd71b15f4bddd474affb613.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/0249bd2f0503eac4ec00b0be2df11f9fe5de80394bd71b15f4bddd474affb613.jpg)

![1d30d6f3f9e0f96a367f30e0813265bb88471afb4dade552a7b02c93df3796a3.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/1d30d6f3f9e0f96a367f30e0813265bb88471afb4dade552a7b02c93df3796a3.jpg)

![32dca8719fe67fb33f8d26ea25b54cb60c8488126ef7ce80b46a69f12be68979.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/32dca8719fe67fb33f8d26ea25b54cb60c8488126ef7ce80b46a69f12be68979.jpg)

![3c9d32c42a74c84e832baae61fbda082d369c9009f85573bddaa89a17b99b4bb.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/3c9d32c42a74c84e832baae61fbda082d369c9009f85573bddaa89a17b99b4bb.jpg)

![447a03f5aa448ba5f8d26b070958df8c4e52fc44394f7ed0ed9b7fd9b830f43b.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/447a03f5aa448ba5f8d26b070958df8c4e52fc44394f7ed0ed9b7fd9b830f43b.jpg)

![47b161532866852fdd2d20719da77adfe4255958da91ecb58bdab6d9b6275449.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/47b161532866852fdd2d20719da77adfe4255958da91ecb58bdab6d9b6275449.jpg)

![70a34b0a76a198258d9575e6f3cfa296f6213b5d25978003ac1ae9ec7fc34cfd.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/70a34b0a76a198258d9575e6f3cfa296f6213b5d25978003ac1ae9ec7fc34cfd.jpg)

![8f9d360722578647edf729c6ef8f38697e43e644e39f223618b08ea5c151b2a3.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/8f9d360722578647edf729c6ef8f38697e43e644e39f223618b08ea5c151b2a3.jpg)

![9fd86ff4389b28e3c5a512cad896b7234fae4e198a84d4dbb73d238c05036eca.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/9fd86ff4389b28e3c5a512cad896b7234fae4e198a84d4dbb73d238c05036eca.jpg)

![a2f50df4884803b2f5dfeed44142280edb9a47c8533f4a6fe28582a572385a62.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/a2f50df4884803b2f5dfeed44142280edb9a47c8533f4a6fe28582a572385a62.jpg)

![aa3114914726c71a70a4c225b0590847f2cf2f17a94f2685b1a3261f820d4ad8.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/aa3114914726c71a70a4c225b0590847f2cf2f17a94f2685b1a3261f820d4ad8.jpg)

![c3d5152305aebe2797314ed055e9a2a4ce58a58790bf5503590a3dae637ccfe1.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/c3d5152305aebe2797314ed055e9a2a4ce58a58790bf5503590a3dae637ccfe1.jpg)

![ca6955ee2625adb3b26fffbf0985cdd3e949d3796d06490912177298049990f5.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/ca6955ee2625adb3b26fffbf0985cdd3e949d3796d06490912177298049990f5.jpg)

![eb83c4cb87ec7d2880c0c91964d5078524e1fdc6ce47ffe4d9fecf7d4bcbf6d8.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/eb83c4cb87ec7d2880c0c91964d5078524e1fdc6ce47ffe4d9fecf7d4bcbf6d8.jpg)

![f5b5c5e08b2e588cdd681c7e7a1775d45e9fcfbc03614a3b79e1092956b0dd05.jpg](../nips_results/525_Ambient%20Diffusion%20Omni_%20Training%20Good%20Models%20with%20Bad%20Data/tables/f5b5c5e08b2e588cdd681c7e7a1775d45e9fcfbc03614a3b79e1092956b0dd05.jpg)

## Transformer Copilot: Learning from The Mistake Log in LLM Fine-tuning


### Images

![3db4b69d946ef976294843ed2795a22e37e5d2c3f8cbc2a5b0c5d303c6acbc74.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/images/3db4b69d946ef976294843ed2795a22e37e5d2c3f8cbc2a5b0c5d303c6acbc74.jpg)

![476e207f30d659a55b3f1eb1a5d6a3d736555930b19b7e37cbf26a30653ec896.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/images/476e207f30d659a55b3f1eb1a5d6a3d736555930b19b7e37cbf26a30653ec896.jpg)

![75a9b73447bbeca3c04b5548e2d519278fc0b2d5f5a8768d310bebd291287798.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/images/75a9b73447bbeca3c04b5548e2d519278fc0b2d5f5a8768d310bebd291287798.jpg)

![8d1e804f51825d9760a37b8d1ca027a61deecc5e33fc172f0c1789814527c37e.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/images/8d1e804f51825d9760a37b8d1ca027a61deecc5e33fc172f0c1789814527c37e.jpg)

![c3a4b2d0a504bdc4f0ff0962a3b3fddb69b40a703daf664436758fbd0c23485a.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/images/c3a4b2d0a504bdc4f0ff0962a3b3fddb69b40a703daf664436758fbd0c23485a.jpg)

![ddc498cdd5624aff77c05707c4a032b0db10037563ca9f9e77f70162f895dbff.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/images/ddc498cdd5624aff77c05707c4a032b0db10037563ca9f9e77f70162f895dbff.jpg)

![fa6a1934fd1904a9aab58f9fcb0a6c9dd707777df92949e7d0e9acf86f6cc7cc.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/images/fa6a1934fd1904a9aab58f9fcb0a6c9dd707777df92949e7d0e9acf86f6cc7cc.jpg)

### Tables

![0114737e4d1cc238bdd1d506f079c63c4e1c9b1934a16685b7d2e6f3ff69c08e.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/0114737e4d1cc238bdd1d506f079c63c4e1c9b1934a16685b7d2e6f3ff69c08e.jpg)

![0a5c8517f63d5f462c6911327e6c7e6cec94b85397f998b543a71385efaf0be3.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/0a5c8517f63d5f462c6911327e6c7e6cec94b85397f998b543a71385efaf0be3.jpg)

![102a5592a4ca516c84164eb487aefec222c48cb2e9256a7501bc06b1bcae62d4.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/102a5592a4ca516c84164eb487aefec222c48cb2e9256a7501bc06b1bcae62d4.jpg)

![18684644b71d8790860fe013cae65baa45456f75b1d3e1706604db96b4d8e7b9.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/18684644b71d8790860fe013cae65baa45456f75b1d3e1706604db96b4d8e7b9.jpg)

![1905eb33db77976cb700b8e8f326d579c87e20656f162ca156b4cd5bf40c9799.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/1905eb33db77976cb700b8e8f326d579c87e20656f162ca156b4cd5bf40c9799.jpg)

![1b3361cdf9eed287bbe3fa0314596f93e923c324de943b35d6978be59b38d40b.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/1b3361cdf9eed287bbe3fa0314596f93e923c324de943b35d6978be59b38d40b.jpg)

![20fbc0f6e626dacea82c5b59caf1f98c94533c8f27e461e445a974a342dcd02f.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/20fbc0f6e626dacea82c5b59caf1f98c94533c8f27e461e445a974a342dcd02f.jpg)

![2bda2b2f9eee63284d238bc85e5d4efe29b78b5a93f101278c56902484c9e27a.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/2bda2b2f9eee63284d238bc85e5d4efe29b78b5a93f101278c56902484c9e27a.jpg)

![338f23a9d988d98a9c99764b4381c44fbff5129dbba84b7edd72ebd363b391f3.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/338f23a9d988d98a9c99764b4381c44fbff5129dbba84b7edd72ebd363b391f3.jpg)

![567c4116ffa3c54c344c9612be567dc9121e8bbe35ec64272b09a5ad0c1baf1e.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/567c4116ffa3c54c344c9612be567dc9121e8bbe35ec64272b09a5ad0c1baf1e.jpg)

![944b12e98cb41b492d2d38a6da87bd795d05421a9c3640295204e7e34ac0d39a.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/944b12e98cb41b492d2d38a6da87bd795d05421a9c3640295204e7e34ac0d39a.jpg)

![9cf9ca2fec64b964b563c4c7a785ed63e1b89fb62b0605d35e7c032ac4b8543e.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/9cf9ca2fec64b964b563c4c7a785ed63e1b89fb62b0605d35e7c032ac4b8543e.jpg)

![9ed8c603834b1cabeb5691584ca054c0bfe86ac502c389a6d5a08d33da99ba4e.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/9ed8c603834b1cabeb5691584ca054c0bfe86ac502c389a6d5a08d33da99ba4e.jpg)

![a3bebdf4c3ff8725fd7eabd39a668901e0df9aed9e9d19df415bcb65fc6988f5.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/a3bebdf4c3ff8725fd7eabd39a668901e0df9aed9e9d19df415bcb65fc6988f5.jpg)

![a8d24531aebc6468fc617dfe21e097930fb72d358328e1591a4e86ed3da90554.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/a8d24531aebc6468fc617dfe21e097930fb72d358328e1591a4e86ed3da90554.jpg)

![bedc9e3b1eaa76c1770581974c66d6ca7ce2e8df38e3f65f0b7fea6406bd9cd0.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/bedc9e3b1eaa76c1770581974c66d6ca7ce2e8df38e3f65f0b7fea6406bd9cd0.jpg)

![c4b1c4b1af7ee27eec7cba2796e20f2765ec5b70100163b892df125efd5a2e7f.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/c4b1c4b1af7ee27eec7cba2796e20f2765ec5b70100163b892df125efd5a2e7f.jpg)

![ce1179123a77f1d15d682bcf9ce7d628e1a6ad99fe9997d0ece194028b041d2a.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/ce1179123a77f1d15d682bcf9ce7d628e1a6ad99fe9997d0ece194028b041d2a.jpg)

![d41c8a05bbe450f3b515e2a829ed261ae2cc06d2a60be40b2fa100d96bfcd51b.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/d41c8a05bbe450f3b515e2a829ed261ae2cc06d2a60be40b2fa100d96bfcd51b.jpg)

![dfaa37be71001c1e51a16103ea9856b5f43d3bd09278d487eb99b54f70f6e7b0.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/dfaa37be71001c1e51a16103ea9856b5f43d3bd09278d487eb99b54f70f6e7b0.jpg)

![e1ab44306c5cd425c21b186942f9f5857ff7f57370e4b200d230073f9273defc.jpg](../nips_results/526_Transformer%20Copilot_%20Learning%20from%20The%20Mistake%20Log%20in%20LLM%20Fine-tuning/tables/e1ab44306c5cd425c21b186942f9f5857ff7f57370e4b200d230073f9273defc.jpg)

## Fast-Slow Thinking GRPO for Large Vision-Language Model Reasoning


### Images

![0abfd479131627b52fff219d482a72e295f75400844d25b3bcdbf625ed8d14eb.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/0abfd479131627b52fff219d482a72e295f75400844d25b3bcdbf625ed8d14eb.jpg)

![1574531c101f94958ca63a8f9bb942cbbe47e5bdb5a6f0b891375619d0f96ee3.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/1574531c101f94958ca63a8f9bb942cbbe47e5bdb5a6f0b891375619d0f96ee3.jpg)

![1cd3bd20e0f9fe4a25c1f9ee114c6999588d8e6a6abc68d822af816d02b32ed9.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/1cd3bd20e0f9fe4a25c1f9ee114c6999588d8e6a6abc68d822af816d02b32ed9.jpg)

![49eab06be033b3e35358e1fa70cbe6b2ac6abd95abf874463b9bcab3dfca8a3a.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/49eab06be033b3e35358e1fa70cbe6b2ac6abd95abf874463b9bcab3dfca8a3a.jpg)

![555fb952e2cf098dd9a227f6269a6a530fa532b96dab5c86a1901f4fab3eecf8.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/555fb952e2cf098dd9a227f6269a6a530fa532b96dab5c86a1901f4fab3eecf8.jpg)

![7386772072fe62174b4b3312236872c17a9991af7412fbe6038136f8fc60ff7c.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/7386772072fe62174b4b3312236872c17a9991af7412fbe6038136f8fc60ff7c.jpg)

![842a41f9b7a8501540205b43cb26bde0db7989663f161536fa419feb59dc4979.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/842a41f9b7a8501540205b43cb26bde0db7989663f161536fa419feb59dc4979.jpg)

![95e619fe36c82dd04c3bbb046359385b4e52f83bc6d86d6826a0a110a68c929c.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/95e619fe36c82dd04c3bbb046359385b4e52f83bc6d86d6826a0a110a68c929c.jpg)

![9f5d40455456709c11c7a135281d5c808112732b78c432e31d46b4f4139a9ada.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/9f5d40455456709c11c7a135281d5c808112732b78c432e31d46b4f4139a9ada.jpg)

![aaf5a5702f8a9e81ecad91c36c247a4573e30e87c70f761b739478167f2ffc1d.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/aaf5a5702f8a9e81ecad91c36c247a4573e30e87c70f761b739478167f2ffc1d.jpg)

![b9d33783c40fd943dc300af49c38b4afe9a3811cb62461979f2c2aa83804c291.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/b9d33783c40fd943dc300af49c38b4afe9a3811cb62461979f2c2aa83804c291.jpg)

![ee6df5c9a0f4372094a2a22e86a186f24774690b7e16cbbb3cf06ea1a3810edf.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/ee6df5c9a0f4372094a2a22e86a186f24774690b7e16cbbb3cf06ea1a3810edf.jpg)

![f3ec107e6a6e39917e64daec76c2a272238329af22a89558bfdfc003dd3e07de.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/f3ec107e6a6e39917e64daec76c2a272238329af22a89558bfdfc003dd3e07de.jpg)

![f4094ed2bfcdac77c07e0ca83f9581244b484eb7e9feb554a416547ceba267ab.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/images/f4094ed2bfcdac77c07e0ca83f9581244b484eb7e9feb554a416547ceba267ab.jpg)

### Tables

![011cc01ddc61723e05d85cbbddc6aba62a2295d70429c247964e391414eb674c.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/011cc01ddc61723e05d85cbbddc6aba62a2295d70429c247964e391414eb674c.jpg)

![0cc046575fb21b76b00f39576ddd674661a5122f0e439f7437c0ba0558722c49.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/0cc046575fb21b76b00f39576ddd674661a5122f0e439f7437c0ba0558722c49.jpg)

![1e1cc8ea0c5d28d50667ea752a3afdaf2ffd8faf2718ecb0f85fc9e1349b64dc.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/1e1cc8ea0c5d28d50667ea752a3afdaf2ffd8faf2718ecb0f85fc9e1349b64dc.jpg)

![31a623e13a4a3265454d6aaf58a0af655c5e0a74b890be9f6525e2e4c967d6c7.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/31a623e13a4a3265454d6aaf58a0af655c5e0a74b890be9f6525e2e4c967d6c7.jpg)

![5af75f3158954bafc2b97ea1ee81686a223efd83c7425a933395c95ffead6bfb.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/5af75f3158954bafc2b97ea1ee81686a223efd83c7425a933395c95ffead6bfb.jpg)

![6268459d96048f8983ac0cb884098555bf712cd22fdacb1150cddd8307ae2ace.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/6268459d96048f8983ac0cb884098555bf712cd22fdacb1150cddd8307ae2ace.jpg)

![65438615642f2f3d0a4a2370f6a13a10cdd56cb3a59ae59e49fd7bd8d4b144f2.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/65438615642f2f3d0a4a2370f6a13a10cdd56cb3a59ae59e49fd7bd8d4b144f2.jpg)

![65ac78e80275127fa321a44187a1be7b29aa9f7414b3191a5881fec5b70cd79c.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/65ac78e80275127fa321a44187a1be7b29aa9f7414b3191a5881fec5b70cd79c.jpg)

![6b2a7d28bea81b46efbd1ebd2d8c2f3ef8cd3c40e7a94ef6dbb78dc27f801c01.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/6b2a7d28bea81b46efbd1ebd2d8c2f3ef8cd3c40e7a94ef6dbb78dc27f801c01.jpg)

![6c28228220909329213f6c0452a8e576b6798bc5a1507f8d3ba8073f1765f4d6.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/6c28228220909329213f6c0452a8e576b6798bc5a1507f8d3ba8073f1765f4d6.jpg)

![6c6669cdf11f33ae8a7350bdb15ef5a54262399bd5a70ac5cc2d146895a2c812.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/6c6669cdf11f33ae8a7350bdb15ef5a54262399bd5a70ac5cc2d146895a2c812.jpg)

![89d8ccd03847d3410ff0640fa114752ea0bdaa80c45b6147d34ecd8f826efe55.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/89d8ccd03847d3410ff0640fa114752ea0bdaa80c45b6147d34ecd8f826efe55.jpg)

![92a7a6237b24db01a54625718eb53f18a9448ff6d993bdc39cbd80fbf115d497.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/92a7a6237b24db01a54625718eb53f18a9448ff6d993bdc39cbd80fbf115d497.jpg)

![a42cc66c76509d7e77d108f497243cb3fdf4b357f5dc089bc2d013b295fe4af1.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/a42cc66c76509d7e77d108f497243cb3fdf4b357f5dc089bc2d013b295fe4af1.jpg)

![a62e6a1893df8351bf7b0c6104fa13b170a506a677c4705db3044be7def990aa.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/a62e6a1893df8351bf7b0c6104fa13b170a506a677c4705db3044be7def990aa.jpg)

![d8266054d29bfde6b669170476c04765574ecf52f164875aa8f74c3b23b61ebb.jpg](../nips_results/527_Fast-Slow%20Thinking%20GRPO%20for%20Large%20Vision-Language%20Model%20Reasoning/tables/d8266054d29bfde6b669170476c04765574ecf52f164875aa8f74c3b23b61ebb.jpg)

## CLiFT: Compressive Light-Field Tokens for Compute Efficient and Adaptive Neural Rendering


### Images

![3fbacc116d8c5f5d5aab72ac91914e5facc04f06837f6147050ae6c76a2d848d.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/3fbacc116d8c5f5d5aab72ac91914e5facc04f06837f6147050ae6c76a2d848d.jpg)

![48009847e142dd1b157b44fb434575687fa7c3ecc74218e8953f43613bf0a9f2.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/48009847e142dd1b157b44fb434575687fa7c3ecc74218e8953f43613bf0a9f2.jpg)

![579d7c7307abede222659b58dcb0eee05d8004458117bbb437d4d09338b4c88f.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/579d7c7307abede222659b58dcb0eee05d8004458117bbb437d4d09338b4c88f.jpg)

![69dbdd1e060ee9f8c28772b9130b9cefa4929bb15c4147aa43e6868ef1a297a0.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/69dbdd1e060ee9f8c28772b9130b9cefa4929bb15c4147aa43e6868ef1a297a0.jpg)

![86e90caa6f019f8c814ab6e713de7cb16e73c60010e0d48c312dc18c69251653.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/86e90caa6f019f8c814ab6e713de7cb16e73c60010e0d48c312dc18c69251653.jpg)

![97f11df1d1d8a111aa3ba69b53735e55f504218c4d25d342e79b74fb76fb68e7.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/97f11df1d1d8a111aa3ba69b53735e55f504218c4d25d342e79b74fb76fb68e7.jpg)

![9ea3b569256db50a4847d9dcdb277e3b3db9f1c5b2bf557fc6d5b4f463239ac2.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/9ea3b569256db50a4847d9dcdb277e3b3db9f1c5b2bf557fc6d5b4f463239ac2.jpg)

![b52a886c915fe51c345a706af6ef6f77183f952818e96ed189aee45da6e49866.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/b52a886c915fe51c345a706af6ef6f77183f952818e96ed189aee45da6e49866.jpg)

![bc52e62561ba9e4471282f611075473b161fc7b515134db3d2ea3f2724c9fa76.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/bc52e62561ba9e4471282f611075473b161fc7b515134db3d2ea3f2724c9fa76.jpg)

![db6c433e0d10cd28a5c8037c63970b10d77b0707912e5be475d75ccd26cda8b0.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/db6c433e0d10cd28a5c8037c63970b10d77b0707912e5be475d75ccd26cda8b0.jpg)

![dd8495e578cfc068b9de21c4d6d9df2cf53d366671d219a70c68204c58d78484.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/dd8495e578cfc068b9de21c4d6d9df2cf53d366671d219a70c68204c58d78484.jpg)

![e25eded509e6a4836de669936fb65a213214a2cf9205f5398a65030e5002b669.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/e25eded509e6a4836de669936fb65a213214a2cf9205f5398a65030e5002b669.jpg)

![f8055597f972ea3732bbdf6f048634939a21a63718c7547550faf8751bce745a.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/images/f8055597f972ea3732bbdf6f048634939a21a63718c7547550faf8751bce745a.jpg)

### Tables

![1817abf8b265fb8790dacd8ade3f21eb4c1464b1f15e620808ba83bd8ea3471b.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/tables/1817abf8b265fb8790dacd8ade3f21eb4c1464b1f15e620808ba83bd8ea3471b.jpg)

![8ffb30e3f65765617bb8637f6211d711836fc43bc4b0b5909719687aa0da81b2.jpg](../nips_results/528_CLiFT_%20Compressive%20Light-Field%20Tokens%20for%20Compute%20Efficient%20and%20Adaptive%20Neural%20Rendering/tables/8ffb30e3f65765617bb8637f6211d711836fc43bc4b0b5909719687aa0da81b2.jpg)

## Toward Relative Positional Encoding in Spiking Transformers


### Images

![02593a2d114b54fed7317b3a7816b0f23253196bb44a2be7d50a0a133e7ed0da.jpg](../nips_results/529_Toward%20Relative%20Positional%20Encoding%20in%20Spiking%20Transformers/images/02593a2d114b54fed7317b3a7816b0f23253196bb44a2be7d50a0a133e7ed0da.jpg)

![2d7f6cfffc5e91422eb1fcf3e4432a9f98f1eaed82b97f71f70a159aa0335422.jpg](../nips_results/529_Toward%20Relative%20Positional%20Encoding%20in%20Spiking%20Transformers/images/2d7f6cfffc5e91422eb1fcf3e4432a9f98f1eaed82b97f71f70a159aa0335422.jpg)

![bdb178031ec8d263c3a5388d900e974b8ce39ae5759a6611f688a57e22173fa5.jpg](../nips_results/529_Toward%20Relative%20Positional%20Encoding%20in%20Spiking%20Transformers/images/bdb178031ec8d263c3a5388d900e974b8ce39ae5759a6611f688a57e22173fa5.jpg)

### Tables

![40cb03314b431b0f38981e739631c34470952cb9e0141ca1462a6e75e6c7462a.jpg](../nips_results/529_Toward%20Relative%20Positional%20Encoding%20in%20Spiking%20Transformers/tables/40cb03314b431b0f38981e739631c34470952cb9e0141ca1462a6e75e6c7462a.jpg)

![542a685bbab0c602344235b8f165400e1e741eecd92ae0798c5cb1c03809372f.jpg](../nips_results/529_Toward%20Relative%20Positional%20Encoding%20in%20Spiking%20Transformers/tables/542a685bbab0c602344235b8f165400e1e741eecd92ae0798c5cb1c03809372f.jpg)

![78a7a86120f5ea7f0a3e71db8529217d6b91ed7a72676f236c30e412ca52b726.jpg](../nips_results/529_Toward%20Relative%20Positional%20Encoding%20in%20Spiking%20Transformers/tables/78a7a86120f5ea7f0a3e71db8529217d6b91ed7a72676f236c30e412ca52b726.jpg)

![7da6b4607081ab2b97c4805e7bc61c583ad4963c15d296fef7863d5f4daadf5b.jpg](../nips_results/529_Toward%20Relative%20Positional%20Encoding%20in%20Spiking%20Transformers/tables/7da6b4607081ab2b97c4805e7bc61c583ad4963c15d296fef7863d5f4daadf5b.jpg)

![a40ae9376db6d200372cb5a9ace321ee955c270d32fff07fc94dffad093552f3.jpg](../nips_results/529_Toward%20Relative%20Positional%20Encoding%20in%20Spiking%20Transformers/tables/a40ae9376db6d200372cb5a9ace321ee955c270d32fff07fc94dffad093552f3.jpg)

![e15646c99d8439059c4888ddfb5c5dc918931d611e190f44b3e37d8038480dc8.jpg](../nips_results/529_Toward%20Relative%20Positional%20Encoding%20in%20Spiking%20Transformers/tables/e15646c99d8439059c4888ddfb5c5dc918931d611e190f44b3e37d8038480dc8.jpg)

![f7edda669299d407314ddac906002879aaf5668456eae40f046744860880c167.jpg](../nips_results/529_Toward%20Relative%20Positional%20Encoding%20in%20Spiking%20Transformers/tables/f7edda669299d407314ddac906002879aaf5668456eae40f046744860880c167.jpg)

![fa55e1c16c693f01ed02bcccbbeda322784ba7e82b5b0d33661948acce665fff.jpg](../nips_results/529_Toward%20Relative%20Positional%20Encoding%20in%20Spiking%20Transformers/tables/fa55e1c16c693f01ed02bcccbbeda322784ba7e82b5b0d33661948acce665fff.jpg)

## Breaking the Batch Barrier (B3) of Contrastive Learning via Smart Batch Mining


### Images

![43ea3c7130b3bdaafe2556393b11c76e1451ce4e6c76cbaf85bdf8adc6e393ec.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/images/43ea3c7130b3bdaafe2556393b11c76e1451ce4e6c76cbaf85bdf8adc6e393ec.jpg)

![588e6566b5416ccc18d5f5733612cbc3caa0c11fe2e3bc5c57c32c88a9ec2e41.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/images/588e6566b5416ccc18d5f5733612cbc3caa0c11fe2e3bc5c57c32c88a9ec2e41.jpg)

![741efabca5afb2a6c25a8dc102409f7d852969d60815241311f002037dea8cdb.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/images/741efabca5afb2a6c25a8dc102409f7d852969d60815241311f002037dea8cdb.jpg)

![fd32999784ebfeb830c2648b19e800d21d97b0a66e6cbe35980902ca2a7b267d.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/images/fd32999784ebfeb830c2648b19e800d21d97b0a66e6cbe35980902ca2a7b267d.jpg)

### Tables

![096694a5fa6aa27e0d3421a62c1e2ac2529b20bda2cdc406bda898c1c2c3d4f7.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/096694a5fa6aa27e0d3421a62c1e2ac2529b20bda2cdc406bda898c1c2c3d4f7.jpg)

![09ef2bcf58f1eed4a64ee7ba6ac1b07f36caa66721cded1be16cb731c8dce781.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/09ef2bcf58f1eed4a64ee7ba6ac1b07f36caa66721cded1be16cb731c8dce781.jpg)

![201d48632ba321e6b8ab198bed9047f3111bd7a8c43ba21ae2f9bc93b7ae6e81.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/201d48632ba321e6b8ab198bed9047f3111bd7a8c43ba21ae2f9bc93b7ae6e81.jpg)

![2a5e368e32cc1f544281221c09eafbeca656e35cfd6fee3f26dbf1233e8b3f8f.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/2a5e368e32cc1f544281221c09eafbeca656e35cfd6fee3f26dbf1233e8b3f8f.jpg)

![2f5c1ab95cd28a16c63f8380de0cb81ca2d5ec2cf9367c14ee5a03d921b1335b.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/2f5c1ab95cd28a16c63f8380de0cb81ca2d5ec2cf9367c14ee5a03d921b1335b.jpg)

![50a7951e482bba2ce6f95a3d0cd0eb0cb6bf04034f98f5dbdfdb0b7b0125e68d.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/50a7951e482bba2ce6f95a3d0cd0eb0cb6bf04034f98f5dbdfdb0b7b0125e68d.jpg)

![7427e251c1b1f0b6a3018ad6c5a2d14229d920ea6e9b3c8cfc17a57d2153db87.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/7427e251c1b1f0b6a3018ad6c5a2d14229d920ea6e9b3c8cfc17a57d2153db87.jpg)

![7cac3fc99012bd35ec6632dfb27bb81615d8ff22e7ea49be24d258803864f2f0.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/7cac3fc99012bd35ec6632dfb27bb81615d8ff22e7ea49be24d258803864f2f0.jpg)

![ac6acb4cce7f51d8a0fff265f9fddd5ebb2d4e27d5bf14b3a2ac8be8ae41da30.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/ac6acb4cce7f51d8a0fff265f9fddd5ebb2d4e27d5bf14b3a2ac8be8ae41da30.jpg)

![b3157cc18fe292347f47c7424de086a3070a7a2365bc96e6a117295ce187ed86.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/b3157cc18fe292347f47c7424de086a3070a7a2365bc96e6a117295ce187ed86.jpg)

![d2b733aaa83fd37946d8a7b89143016b0a7653d8c08232fdc798738c1691b392.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/d2b733aaa83fd37946d8a7b89143016b0a7653d8c08232fdc798738c1691b392.jpg)

![e17360585b1f4b209d3d1c09b5fa21704b38d70e49ef0f3cf367d7b8704590ba.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/e17360585b1f4b209d3d1c09b5fa21704b38d70e49ef0f3cf367d7b8704590ba.jpg)

![ea13a96b9b35c212b831e508d1f429e0f6fd050628446abb0a9e5df4c2cc403a.jpg](../nips_results/530_Breaking%20the%20Batch%20Barrier%20%28B3) of Contrastive Learning via Smart Batch Mining/tables/ea13a96b9b35c212b831e508d1f429e0f6fd050628446abb0a9e5df4c2cc403a.jpg)

## TRIDENT: Tri-Modal Molecular Representation Learning with Taxonomic Annotations and Local Correspondence


### Images

![04c542fc719c68542e5063b9232609b07525f83bd13283da79f7b3f27c27f722.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/images/04c542fc719c68542e5063b9232609b07525f83bd13283da79f7b3f27c27f722.jpg)

![bf57edfad04c484721899e7e14b38f81c729f95eeca47d0b255ae985042c1c2e.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/images/bf57edfad04c484721899e7e14b38f81c729f95eeca47d0b255ae985042c1c2e.jpg)

![d2a1a0e4552b53cf442ded6b6f1e7c5806c62436910571a9eb4eb84a25575539.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/images/d2a1a0e4552b53cf442ded6b6f1e7c5806c62436910571a9eb4eb84a25575539.jpg)

![d789b36c45f08bd0b5d0cad6fbdb34ad5d49c6dc079f6934b6dd86d71284846d.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/images/d789b36c45f08bd0b5d0cad6fbdb34ad5d49c6dc079f6934b6dd86d71284846d.jpg)

### Tables

![06de765bc40b94b575d6a094d980b712833b79840eb4f2fe21358e48e27b0d57.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/06de765bc40b94b575d6a094d980b712833b79840eb4f2fe21358e48e27b0d57.jpg)

![2342c6a76523b4c5140c8311299524a187faac0b227125a58b5254d95126f557.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/2342c6a76523b4c5140c8311299524a187faac0b227125a58b5254d95126f557.jpg)

![311656fe94a76df3576ef67ff842e619fd21d953677aa8de805a1305e9adf3fd.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/311656fe94a76df3576ef67ff842e619fd21d953677aa8de805a1305e9adf3fd.jpg)

![4a75dc17eab2f89a0a0b7e19f638fd3a3e52541145c0dc0829bde8b97aa49e46.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/4a75dc17eab2f89a0a0b7e19f638fd3a3e52541145c0dc0829bde8b97aa49e46.jpg)

![5c08d0287b1ea0981aef1cf6efdb0aea9cabd1923ae1d364b1ff47dce77853eb.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/5c08d0287b1ea0981aef1cf6efdb0aea9cabd1923ae1d364b1ff47dce77853eb.jpg)

![66e0742595471d81d37f3c8f2d9bce53c73baa522c6d8f46cdbccd0ea19d6149.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/66e0742595471d81d37f3c8f2d9bce53c73baa522c6d8f46cdbccd0ea19d6149.jpg)

![77c85972c70d2b3fee1be299c1b1184d2072dba42987cce030dc89eaf0874e23.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/77c85972c70d2b3fee1be299c1b1184d2072dba42987cce030dc89eaf0874e23.jpg)

![d3a08c641f9f344bfeae7b2c8aad12df3f95947fb8bed6ce5c07d5e427377769.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/d3a08c641f9f344bfeae7b2c8aad12df3f95947fb8bed6ce5c07d5e427377769.jpg)

![de12374bcc1e29403de31f7684c87f7a48d5d034caac2d2ae85de0ba505438b9.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/de12374bcc1e29403de31f7684c87f7a48d5d034caac2d2ae85de0ba505438b9.jpg)

![e487e512e2c3247bf6ff28de58a0b60f827eae44bc8e742a390326c9fd74b0a5.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/e487e512e2c3247bf6ff28de58a0b60f827eae44bc8e742a390326c9fd74b0a5.jpg)

![f2da48d4c3c5e9f7a1ab94288b4cb920c69e8dd55b4def75bc31c1f281d976aa.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/f2da48d4c3c5e9f7a1ab94288b4cb920c69e8dd55b4def75bc31c1f281d976aa.jpg)

![f74612f49ff24235e4ca9ac1d8c7f338e1eb03c889fa2b6ccb1476c7e240d3e3.jpg](../nips_results/531_TRIDENT_%20Tri-Modal%20Molecular%20Representation%20Learning%20with%20Taxonomic%20Annotations%20and%20Local%20Correspond/tables/f74612f49ff24235e4ca9ac1d8c7f338e1eb03c889fa2b6ccb1476c7e240d3e3.jpg)

## Vector Quantization in the Brain: Grid-like Codes in World Models


### Images

![1b0799aa0b7551b363227f2f05838977bfab2fe747598d2409e3e3f49dee653b.jpg](../nips_results/532_Vector%20Quantization%20in%20the%20Brain_%20Grid-like%20Codes%20in%20World%20Models/images/1b0799aa0b7551b363227f2f05838977bfab2fe747598d2409e3e3f49dee653b.jpg)

![448c80f48bce46fa7b74b97ec37693d2c11ff814ce75a577694c7d5579be3eb7.jpg](../nips_results/532_Vector%20Quantization%20in%20the%20Brain_%20Grid-like%20Codes%20in%20World%20Models/images/448c80f48bce46fa7b74b97ec37693d2c11ff814ce75a577694c7d5579be3eb7.jpg)

![5158f58416ee96974c8895b1ba3678f49d5343608391af0ac8d77d56b6c79493.jpg](../nips_results/532_Vector%20Quantization%20in%20the%20Brain_%20Grid-like%20Codes%20in%20World%20Models/images/5158f58416ee96974c8895b1ba3678f49d5343608391af0ac8d77d56b6c79493.jpg)

![d66fef23599ba03c3bb18af24d859fde56930fc170d93cecc76e94e866171366.jpg](../nips_results/532_Vector%20Quantization%20in%20the%20Brain_%20Grid-like%20Codes%20in%20World%20Models/images/d66fef23599ba03c3bb18af24d859fde56930fc170d93cecc76e94e866171366.jpg)

![dbcaff3cda1ff66da494a5473de961ee40efcf041cf64c65e9a2c62ba0a66c4e.jpg](../nips_results/532_Vector%20Quantization%20in%20the%20Brain_%20Grid-like%20Codes%20in%20World%20Models/images/dbcaff3cda1ff66da494a5473de961ee40efcf041cf64c65e9a2c62ba0a66c4e.jpg)

![e177f99b0758fab3f7dcbd081a87e7a09b56182fdceaacde83f10e8540133b46.jpg](../nips_results/532_Vector%20Quantization%20in%20the%20Brain_%20Grid-like%20Codes%20in%20World%20Models/images/e177f99b0758fab3f7dcbd081a87e7a09b56182fdceaacde83f10e8540133b46.jpg)

![ff38a702285a93c0bf4a0cf4cdd81992aaa7e4248617ae5f654599885fbb182f.jpg](../nips_results/532_Vector%20Quantization%20in%20the%20Brain_%20Grid-like%20Codes%20in%20World%20Models/images/ff38a702285a93c0bf4a0cf4cdd81992aaa7e4248617ae5f654599885fbb182f.jpg)

### Tables

![3399396a97817c8119deb6e4ed417978b219e46c6bd87c12113307da6834251e.jpg](../nips_results/532_Vector%20Quantization%20in%20the%20Brain_%20Grid-like%20Codes%20in%20World%20Models/tables/3399396a97817c8119deb6e4ed417978b219e46c6bd87c12113307da6834251e.jpg)

![adc906496b9af0a763c73dbe18483b9d3bf3c34ceff64e000cb847356dbb394c.jpg](../nips_results/532_Vector%20Quantization%20in%20the%20Brain_%20Grid-like%20Codes%20in%20World%20Models/tables/adc906496b9af0a763c73dbe18483b9d3bf3c34ceff64e000cb847356dbb394c.jpg)

![d7c3d54184c5a460a75f51dd64ad12f247a2b573fa2a207462731bfb0001b594.jpg](../nips_results/532_Vector%20Quantization%20in%20the%20Brain_%20Grid-like%20Codes%20in%20World%20Models/tables/d7c3d54184c5a460a75f51dd64ad12f247a2b573fa2a207462731bfb0001b594.jpg)

## Cycle-Sync: Robust Global Camera Pose Estimation through Enhanced Cycle-Consistent Synchronization


### Images

![198c7c2b7fd5ab4f0ed7f2c2403d520455f2bfc4ebdb9ae5f9d3b686c1b0619d.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/images/198c7c2b7fd5ab4f0ed7f2c2403d520455f2bfc4ebdb9ae5f9d3b686c1b0619d.jpg)

![2cf757c45c99691c23bcf3465048840036ab1ef4ade644ccf870c92507e5fd0e.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/images/2cf757c45c99691c23bcf3465048840036ab1ef4ade644ccf870c92507e5fd0e.jpg)

![870929eb9d31d056439340eb47cfeb4d6ef8fb41a7f9b02cff793d30cf7dc7ea.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/images/870929eb9d31d056439340eb47cfeb4d6ef8fb41a7f9b02cff793d30cf7dc7ea.jpg)

![9bc5f8e99c852e93b1daad6d3f2e90f5063027c4757a6fd1146faaaf9474ba8d.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/images/9bc5f8e99c852e93b1daad6d3f2e90f5063027c4757a6fd1146faaaf9474ba8d.jpg)

![9ec61f45cf84f7b01231102514ce1e8c30e780f7b0372a5d71742e9194a1cc46.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/images/9ec61f45cf84f7b01231102514ce1e8c30e780f7b0372a5d71742e9194a1cc46.jpg)

![bc039d4f0bed9da13a855133c6666567b36849d950b72e614e4a0bac37a2793b.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/images/bc039d4f0bed9da13a855133c6666567b36849d950b72e614e4a0bac37a2793b.jpg)

![bfff2c00c743ad77b34c6bcddc1aa4b33224ad640fd7a4286d109261d6d96f25.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/images/bfff2c00c743ad77b34c6bcddc1aa4b33224ad640fd7a4286d109261d6d96f25.jpg)

![c3f19fd94411cca649f8ef979bf3debe517f907e9743d67f5b1776098eb5f7da.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/images/c3f19fd94411cca649f8ef979bf3debe517f907e9743d67f5b1776098eb5f7da.jpg)

![e24afa0bb776a8e3ea6b08b5bc6d1ea4caed46bed25174941477edec80332772.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/images/e24afa0bb776a8e3ea6b08b5bc6d1ea4caed46bed25174941477edec80332772.jpg)

### Tables

![10029c45cee57c69ba14bf57b094c6d3265a9ca26a5f3424ad11ce610723489a.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/10029c45cee57c69ba14bf57b094c6d3265a9ca26a5f3424ad11ce610723489a.jpg)

![18b82040d5a7570bae585a4a7cd4e7a53c18d7b5b7fe5f6e2ed8531911b39b7e.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/18b82040d5a7570bae585a4a7cd4e7a53c18d7b5b7fe5f6e2ed8531911b39b7e.jpg)

![28675702182bfb7f8540ae1ae2b3d2c7c3e1395259cf868c6213cf31c2d66c5b.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/28675702182bfb7f8540ae1ae2b3d2c7c3e1395259cf868c6213cf31c2d66c5b.jpg)

![305fbc2ebf127d26c5d051777c807457e2571be8d9cba1abeb42872a7bea992d.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/305fbc2ebf127d26c5d051777c807457e2571be8d9cba1abeb42872a7bea992d.jpg)

![5135bbf527bbe62206e93ce34154521c2f3d7cb7b1ab9ae394d9b972b861cdf4.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/5135bbf527bbe62206e93ce34154521c2f3d7cb7b1ab9ae394d9b972b861cdf4.jpg)

![563ffdd60a060ba744e01523bcecc726c3c2b3f6e9ccd095883586ea2df4a3d8.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/563ffdd60a060ba744e01523bcecc726c3c2b3f6e9ccd095883586ea2df4a3d8.jpg)

![600f2fcc519e3507f480fad62973a3a52afc81fa865cb19dea27e1e3ede6d171.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/600f2fcc519e3507f480fad62973a3a52afc81fa865cb19dea27e1e3ede6d171.jpg)

![702f5190b7569594bb9e5daafe9671d5ff2b188c28923306232e1bc99e6c4fa9.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/702f5190b7569594bb9e5daafe9671d5ff2b188c28923306232e1bc99e6c4fa9.jpg)

![84b80291220f073b458c0db1d8175cb9cc1c5a9c7f4aba3cfa4535f707e8a696.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/84b80291220f073b458c0db1d8175cb9cc1c5a9c7f4aba3cfa4535f707e8a696.jpg)

![86268e43b925e54a5a4da140c4e87fb55f9322786e758094fa25d4f8f8444c7d.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/86268e43b925e54a5a4da140c4e87fb55f9322786e758094fa25d4f8f8444c7d.jpg)

![93021a6d55c85385708dcd476b89fbf7827a6a89ff4969a03ab6d45be652fb9a.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/93021a6d55c85385708dcd476b89fbf7827a6a89ff4969a03ab6d45be652fb9a.jpg)

![a3a666cf4b105686200d9647a505946a9dd6fbfbed45ee8134dc1d2300081a0f.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/a3a666cf4b105686200d9647a505946a9dd6fbfbed45ee8134dc1d2300081a0f.jpg)

![b3c208059506ce1f55abff94bd65684d71068b6bb225a642289cea3a1c270691.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/b3c208059506ce1f55abff94bd65684d71068b6bb225a642289cea3a1c270691.jpg)

![bed78220830eee257a67fba9376a9b89966c80b8fc5c2434b17bdc15b4d612ac.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/bed78220830eee257a67fba9376a9b89966c80b8fc5c2434b17bdc15b4d612ac.jpg)

![f2c35e56531cd2cf77d1546c98f08c72522c2c4f0cf85d423e81984248dec670.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/f2c35e56531cd2cf77d1546c98f08c72522c2c4f0cf85d423e81984248dec670.jpg)

![ff60dcd613073c2d1045b3aafa253d7e45dfe8386a9a144affd8be5f05b4f270.jpg](../nips_results/533_Cycle-Sync_%20Robust%20Global%20Camera%20Pose%20Estimation%20through%20Enhanced%20Cycle-Consistent%20Synchronization/tables/ff60dcd613073c2d1045b3aafa253d7e45dfe8386a9a144affd8be5f05b4f270.jpg)

## A Implies B: Circuit Analysis in LLMs for Propositional Logical Reasoning


### Images

![051f8c6246e90de79c89779e54653af1670d524226b762b049f77a14687fb934.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/051f8c6246e90de79c89779e54653af1670d524226b762b049f77a14687fb934.jpg)

![0cf009fa05ad581d9b367ff85322599a1100fd336a7095c4f514f1f42c80adf6.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/0cf009fa05ad581d9b367ff85322599a1100fd336a7095c4f514f1f42c80adf6.jpg)

![16ea443772bb6a1fc3e93872d853de290b4e2e9388c0895bfafee1955eb5f539.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/16ea443772bb6a1fc3e93872d853de290b4e2e9388c0895bfafee1955eb5f539.jpg)

![1a94bce7cc25babd64f6e8a56da24b4f7b429308c11726bd41e6b7f2c3819012.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/1a94bce7cc25babd64f6e8a56da24b4f7b429308c11726bd41e6b7f2c3819012.jpg)

![228a265be1c64f9caf6832f380cce1faf35637e00142baee46f65f7005385a28.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/228a265be1c64f9caf6832f380cce1faf35637e00142baee46f65f7005385a28.jpg)

![3321bb5f3b5bfbdfb5c815cab33783cc7a6a30ae3a4448628639da09b3ed4be6.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/3321bb5f3b5bfbdfb5c815cab33783cc7a6a30ae3a4448628639da09b3ed4be6.jpg)

![3b213e60fe5acf3ddf08712c7d0f0f092b2c8761e16e914ff090ed7874b2187b.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/3b213e60fe5acf3ddf08712c7d0f0f092b2c8761e16e914ff090ed7874b2187b.jpg)

![40056863f59dfb71f98f3102c37e0e5951b0d0a3c57f916d7849ffcea5155122.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/40056863f59dfb71f98f3102c37e0e5951b0d0a3c57f916d7849ffcea5155122.jpg)

![40487222f46a8b1d7ae295caada9453528f2ce9a25dd5ace3f377388c31607dc.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/40487222f46a8b1d7ae295caada9453528f2ce9a25dd5ace3f377388c31607dc.jpg)

![426b3694c4ffd9230b218e69033a1e6d95a3c33f3e76253ee7168214e8f943d1.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/426b3694c4ffd9230b218e69033a1e6d95a3c33f3e76253ee7168214e8f943d1.jpg)

![4704206481b9fae5a6c30d91a3de95b380b33af944a71861dab577c7a1316954.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/4704206481b9fae5a6c30d91a3de95b380b33af944a71861dab577c7a1316954.jpg)

![4fb138af11c8129b63a6788f1514223b56e74067f05586ee8987509484faff78.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/4fb138af11c8129b63a6788f1514223b56e74067f05586ee8987509484faff78.jpg)

![51916e8046bf2d983db5e941a8d5379707a7fa44b0e7936bc4aa896bd987d83b.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/51916e8046bf2d983db5e941a8d5379707a7fa44b0e7936bc4aa896bd987d83b.jpg)

![532f984b6cacebe4ad3279e170e88f5360b4b6c3e07441898078061bbaa6d19a.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/532f984b6cacebe4ad3279e170e88f5360b4b6c3e07441898078061bbaa6d19a.jpg)

![592857a7c102f31c0e40462feb906d2b6209a98bb1f2c36fe0e413b901fe7a63.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/592857a7c102f31c0e40462feb906d2b6209a98bb1f2c36fe0e413b901fe7a63.jpg)

![5b6ec9f8abe1194362bdabb3f16197eaa263360cd7bf3ef6790bf63394749cfc.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/5b6ec9f8abe1194362bdabb3f16197eaa263360cd7bf3ef6790bf63394749cfc.jpg)

![5f6bad5cd5cd5b990240ca26450a671a715f6840439fc67a31c935e5f0f433b1.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/5f6bad5cd5cd5b990240ca26450a671a715f6840439fc67a31c935e5f0f433b1.jpg)

![63adcf57dc7d6c7494116c4e58af723d0c12216122f81b95d2a17f5bd1b799a5.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/63adcf57dc7d6c7494116c4e58af723d0c12216122f81b95d2a17f5bd1b799a5.jpg)

![6bd1e664f324c21205d7ffb87a375cc6ab9fbf382a5f91944dbdab4d73354944.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/6bd1e664f324c21205d7ffb87a375cc6ab9fbf382a5f91944dbdab4d73354944.jpg)

![789ebbfef0b33558465f5deb3db50bf88e69d3cb3b8e8f149d41b17e4ba0d436.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/789ebbfef0b33558465f5deb3db50bf88e69d3cb3b8e8f149d41b17e4ba0d436.jpg)

![8278f854e9274c549de247552433b7db7b054c28e1fe79dfa0783f8c78294251.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/8278f854e9274c549de247552433b7db7b054c28e1fe79dfa0783f8c78294251.jpg)

![9888cebb7a5503d8304c4abc010d80702f470dd6b10f65415bcc489d66d532fb.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/9888cebb7a5503d8304c4abc010d80702f470dd6b10f65415bcc489d66d532fb.jpg)

![a28db3f666db579afcdf79bfa7464d3528b490318765caa93ead287f6d392160.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/a28db3f666db579afcdf79bfa7464d3528b490318765caa93ead287f6d392160.jpg)

![a5515b0badb8d0afb3bf2a1958ace531b0331a58c7287c0fed316446a2eb0c14.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/a5515b0badb8d0afb3bf2a1958ace531b0331a58c7287c0fed316446a2eb0c14.jpg)

![a721c94cbe242987d896243a43e0b80d77477ea8692fe1d3e3af6dee7121b4ad.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/a721c94cbe242987d896243a43e0b80d77477ea8692fe1d3e3af6dee7121b4ad.jpg)

![a7ea38fd2a9e1f757d123d5db67fb71c35c615bb61b60b2e569537fc4ec3ec45.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/a7ea38fd2a9e1f757d123d5db67fb71c35c615bb61b60b2e569537fc4ec3ec45.jpg)

![abc197a947586a3b597b93ea5cd71544d45c4a71881055202e590d7e36a88332.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/abc197a947586a3b597b93ea5cd71544d45c4a71881055202e590d7e36a88332.jpg)

![ac076aff4b1d94f99c63ba085ade242ad23e4b117aeff07467d26abdf1b1ac75.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/ac076aff4b1d94f99c63ba085ade242ad23e4b117aeff07467d26abdf1b1ac75.jpg)

![b106d465e00469b5299e9a342dde473eeafde41b8a8e6d6af1ffb559cbed16fa.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/b106d465e00469b5299e9a342dde473eeafde41b8a8e6d6af1ffb559cbed16fa.jpg)

![bc42df3d0a16ff6432cec4af763c3ec4a2df4d3b3383f770864d4dc94f964187.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/bc42df3d0a16ff6432cec4af763c3ec4a2df4d3b3383f770864d4dc94f964187.jpg)

![c6ba971091325ef4f42e66c91092f98524f1dc6c0b6b3e3485b31d1c674cec3e.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/c6ba971091325ef4f42e66c91092f98524f1dc6c0b6b3e3485b31d1c674cec3e.jpg)

![c8e2f63e10734d292d31cc35a6c98eec9e8f33d5c519ffacc256c7109e53065f.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/c8e2f63e10734d292d31cc35a6c98eec9e8f33d5c519ffacc256c7109e53065f.jpg)

![e9690c79b34a0ba48b5d9fbcbec5eb9db74d815125a8816d6d56a8e22e5d3c5b.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/e9690c79b34a0ba48b5d9fbcbec5eb9db74d815125a8816d6d56a8e22e5d3c5b.jpg)

![ee45edfa58ef8dd02faeff638382bdc33cd986abc3a33bb7f8289653dcc66ae7.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/ee45edfa58ef8dd02faeff638382bdc33cd986abc3a33bb7f8289653dcc66ae7.jpg)

![f0f2d6317b01e87c25ed2bed173e5becb8939fd3db1e17f1995b85d00885d49a.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/f0f2d6317b01e87c25ed2bed173e5becb8939fd3db1e17f1995b85d00885d49a.jpg)

![f47a963b27c284e9bf8e8fe4514423daffa9a9d51ea45634fe03ece1291c703c.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/f47a963b27c284e9bf8e8fe4514423daffa9a9d51ea45634fe03ece1291c703c.jpg)

![f644dc4ab3c8d3b1af7e8336ffce0bc9f59184ab6293447349a506845b2b872b.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/images/f644dc4ab3c8d3b1af7e8336ffce0bc9f59184ab6293447349a506845b2b872b.jpg)

### Tables

![6ee9afb7c0432027cc3b14fc6586143d1efbdbd170eee39ae528093e36088026.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/tables/6ee9afb7c0432027cc3b14fc6586143d1efbdbd170eee39ae528093e36088026.jpg)

![7bb573efffcfaf82b6c5ef61a01ddcfa9e317b09cd167f9b69113cfe2e615574.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/tables/7bb573efffcfaf82b6c5ef61a01ddcfa9e317b09cd167f9b69113cfe2e615574.jpg)

![ee0496e5a5a0809b51babb7352ae29b5c184b3f64869138535de03e444deb059.jpg](../nips_results/534_A%20Implies%20B_%20Circuit%20Analysis%20in%20LLMs%20for%20Propositional%20Logical%20Reasoning/tables/ee0496e5a5a0809b51babb7352ae29b5c184b3f64869138535de03e444deb059.jpg)

## On Traceability in $\ell_p$ Stochastic Convex Optimization


### Tables

![5340982ce604fefc6e5afa3aff77cb87b993565c9acd8045b34d2016c09a195c.jpg](../nips_results/535_On%20Traceability%20in%20%24_ell_p%24%20Stochastic%20Convex%20Optimization/tables/5340982ce604fefc6e5afa3aff77cb87b993565c9acd8045b34d2016c09a195c.jpg)

## Vanish into Thin Air: Cross-prompt Universal Adversarial Attacks for SAM2


### Images

![04997f21d4d5864f1dac994da52ae2473c18de8900190aa0d8b73301f3fbe9df.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/04997f21d4d5864f1dac994da52ae2473c18de8900190aa0d8b73301f3fbe9df.jpg)

![0b217631cecf496dd0914b64d01455dece25e380f53aca705b528d767b8689d4.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/0b217631cecf496dd0914b64d01455dece25e380f53aca705b528d767b8689d4.jpg)

![330e1fefc17e5737de28ceb39ddabb37ab6852500b9f217aaed7fe4f03ce2e2a.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/330e1fefc17e5737de28ceb39ddabb37ab6852500b9f217aaed7fe4f03ce2e2a.jpg)

![61f76b201a97e6e2bae6988451c1a42f257bc977f0bd1ae0e7628f585794ee69.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/61f76b201a97e6e2bae6988451c1a42f257bc977f0bd1ae0e7628f585794ee69.jpg)

![7783bb71a495214435494bca837167d537238e7ce27b0473f78bea26fa1e8613.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/7783bb71a495214435494bca837167d537238e7ce27b0473f78bea26fa1e8613.jpg)

![84cd67ad30f5a2ea01dd8a5d94355b3766a059f2485589ea391ea48906cc8c07.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/84cd67ad30f5a2ea01dd8a5d94355b3766a059f2485589ea391ea48906cc8c07.jpg)

![87bf8338bb7e3f63b62157dd2566598792de2cb454e0b6e928eb3a8ad99a5dbf.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/87bf8338bb7e3f63b62157dd2566598792de2cb454e0b6e928eb3a8ad99a5dbf.jpg)

![d04830ea90e46d103678fb418a1487c318823407ed358c2326f521d0ba029ba9.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/d04830ea90e46d103678fb418a1487c318823407ed358c2326f521d0ba029ba9.jpg)

![d8ca3231cb76f913a50771a3d7f3e1ac7af658f3a0e36d7b63907e3b1747422c.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/d8ca3231cb76f913a50771a3d7f3e1ac7af658f3a0e36d7b63907e3b1747422c.jpg)

![db2ed2cf260ceb90f6f648970335e49518074f3df99c03782dbdeb1799cb6175.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/db2ed2cf260ceb90f6f648970335e49518074f3df99c03782dbdeb1799cb6175.jpg)

![fa78e7ab9c5eba1ea4dac5875656c60a0f6c43c341c6a19aaaf7c93157e6a32b.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/fa78e7ab9c5eba1ea4dac5875656c60a0f6c43c341c6a19aaaf7c93157e6a32b.jpg)

![fc108751c6e3a6fd91543f583578cf2ace168f00e83a727978b8b4f9a4d2c5f2.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/images/fc108751c6e3a6fd91543f583578cf2ace168f00e83a727978b8b4f9a4d2c5f2.jpg)

### Tables

![702264c42f858fca56684c43d1f9ed6de37fd4017ea9e4942e7343ea8f46c1eb.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/tables/702264c42f858fca56684c43d1f9ed6de37fd4017ea9e4942e7343ea8f46c1eb.jpg)

![bc891f89be82d13fbd59f0caa10a52b9422771fd76a5e0340706a975eaa773f7.jpg](../nips_results/536_Vanish%20into%20Thin%20Air_%20Cross-prompt%20Universal%20Adversarial%20Attacks%20for%20SAM2/tables/bc891f89be82d13fbd59f0caa10a52b9422771fd76a5e0340706a975eaa773f7.jpg)

## EAG3R: Event-Augmented 3D Geometry Estimation for Dynamic and Extreme-Lighting Scenes


### Images

![05779aeab093f55e30d0ed7b5d212b49331812f67249f6081f30e382419f43dd.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/images/05779aeab093f55e30d0ed7b5d212b49331812f67249f6081f30e382419f43dd.jpg)

![2df65b6475e0cb910c7851b22809cc2482315522cb55608d8db98cc7091a231a.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/images/2df65b6475e0cb910c7851b22809cc2482315522cb55608d8db98cc7091a231a.jpg)

![2e067508400b63f0b59c99308c3107efcb9089d917747a5f063ebfe60cad3de0.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/images/2e067508400b63f0b59c99308c3107efcb9089d917747a5f063ebfe60cad3de0.jpg)

![7752ccddc481381839d3b58191d0f256b88dc43f7bfd6ec6deac20978be23e35.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/images/7752ccddc481381839d3b58191d0f256b88dc43f7bfd6ec6deac20978be23e35.jpg)

![ab4532cdc0c8b9f7460733650d9ce4467cea2ff60a9de6028ac03180a1dfed42.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/images/ab4532cdc0c8b9f7460733650d9ce4467cea2ff60a9de6028ac03180a1dfed42.jpg)

### Tables

![02529748ad4cb75f0e2d36a9f01276ac4d70600ae0ad1d4c54718e16918490ba.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/02529748ad4cb75f0e2d36a9f01276ac4d70600ae0ad1d4c54718e16918490ba.jpg)

![09446c2ccb53aec582a6be4976f15f64575433be4812f59efb4ded7401eb26ae.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/09446c2ccb53aec582a6be4976f15f64575433be4812f59efb4ded7401eb26ae.jpg)

![25e3e0752071887feb7268a649d22d67c6a8953560d2aa72f425d6651b7dce6b.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/25e3e0752071887feb7268a649d22d67c6a8953560d2aa72f425d6651b7dce6b.jpg)

![263678b7f4d0e428c349c7bfdb556fab32c52732409adcdff5b67e7c2db857df.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/263678b7f4d0e428c349c7bfdb556fab32c52732409adcdff5b67e7c2db857df.jpg)

![32f0cf06f063b832dd18bebdc88d326e8e2ec8953f3bd226fbfbac0214ff14c0.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/32f0cf06f063b832dd18bebdc88d326e8e2ec8953f3bd226fbfbac0214ff14c0.jpg)

![3fb6a8f112eb0a35a425b6b08ef6158f7316179db783e0d52336b69d802eb2ea.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/3fb6a8f112eb0a35a425b6b08ef6158f7316179db783e0d52336b69d802eb2ea.jpg)

![5f43b72841734e08bd5ca78dff65c9c163d8ea91bdb116a70500f69df7655370.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/5f43b72841734e08bd5ca78dff65c9c163d8ea91bdb116a70500f69df7655370.jpg)

![7083b61e2867e6b5b25004b9b0c2dc451356c42d6903e77b7e891260f39b2271.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/7083b61e2867e6b5b25004b9b0c2dc451356c42d6903e77b7e891260f39b2271.jpg)

![9148e48435541c91cf4786f2f90d2311e977fd8ca3f83facb71892c486bc8dd8.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/9148e48435541c91cf4786f2f90d2311e977fd8ca3f83facb71892c486bc8dd8.jpg)

![9bd4c885f9b956b336af8bd3d4e2170e71d50d705a0d7c0e57f71c4d0931e76e.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/9bd4c885f9b956b336af8bd3d4e2170e71d50d705a0d7c0e57f71c4d0931e76e.jpg)

![9db05630c190babc6e08213ef28775e11586abce428cb1a819e2e2cc7827b99d.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/9db05630c190babc6e08213ef28775e11586abce428cb1a819e2e2cc7827b99d.jpg)

![a2ee9c8ac338ea49feb29e4c7f33f972369f273ff368870d509b8726173064ff.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/a2ee9c8ac338ea49feb29e4c7f33f972369f273ff368870d509b8726173064ff.jpg)

![a9119a3454dbc848d9b6f9f5eec87c4003a58c9f238b19c3e87bf41ae62b19c2.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/a9119a3454dbc848d9b6f9f5eec87c4003a58c9f238b19c3e87bf41ae62b19c2.jpg)

![b3957d7f2224f5f5885b2c39958928d72750c490b2764575708247ffbe738106.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/b3957d7f2224f5f5885b2c39958928d72750c490b2764575708247ffbe738106.jpg)

![d0db458048b73264ca37092b095e0164ed2415ff92a64fdffaaeef762afada36.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/d0db458048b73264ca37092b095e0164ed2415ff92a64fdffaaeef762afada36.jpg)

![f5bead33a6db49b4e0a852b3b5651536a272f53e5c8a3daf8164c39089e3c7e3.jpg](../nips_results/537_EAG3R_%20Event-Augmented%203D%20Geometry%20Estimation%20for%20Dynamic%20and%20Extreme-Lighting%20Scenes/tables/f5bead33a6db49b4e0a852b3b5651536a272f53e5c8a3daf8164c39089e3c7e3.jpg)

## A Token is Worth over 1,000 Tokens: Efficient Knowledge Distillation through Low-Rank Clone


### Images

![132497c023773678253523161d41b429f33287e4852210037d3f4e40b06b99fb.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/images/132497c023773678253523161d41b429f33287e4852210037d3f4e40b06b99fb.jpg)

![9ad58d784ca8225fdc886a1258274ed159007121d924fc0a53fa2062543aed21.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/images/9ad58d784ca8225fdc886a1258274ed159007121d924fc0a53fa2062543aed21.jpg)

![bbecc508e2607f44a2cc620b0b0e11e4dc455c42f4943b5fb3389c6fd41d587c.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/images/bbecc508e2607f44a2cc620b0b0e11e4dc455c42f4943b5fb3389c6fd41d587c.jpg)

![cbc780edc68571002f91593d133cde56f9cb88d931f10f0262c70fb4773b6eaf.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/images/cbc780edc68571002f91593d133cde56f9cb88d931f10f0262c70fb4773b6eaf.jpg)

![cdcf30a0fa90436b6a48c7f643381fbdc0f20e06f058135b9ab0bb57a406eb83.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/images/cdcf30a0fa90436b6a48c7f643381fbdc0f20e06f058135b9ab0bb57a406eb83.jpg)

![d288bb5f48dc64a295d5cc29bfad33bdf2aa45dee85fca7d17716163204a73d7.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/images/d288bb5f48dc64a295d5cc29bfad33bdf2aa45dee85fca7d17716163204a73d7.jpg)

![ddb2c6e85da7193b4a5ccb1723ee7d922dc2b971fd44761e91c2c3f71fb4f0a0.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/images/ddb2c6e85da7193b4a5ccb1723ee7d922dc2b971fd44761e91c2c3f71fb4f0a0.jpg)

### Tables

![1992c3fef3a023a8aa216e130132478f2626e8113844499c248ae9c06d69db2b.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/1992c3fef3a023a8aa216e130132478f2626e8113844499c248ae9c06d69db2b.jpg)

![4256bb266bcf7c26de3fd816ae62908f04563bfd8b4aa6d9e11c2007b3208240.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/4256bb266bcf7c26de3fd816ae62908f04563bfd8b4aa6d9e11c2007b3208240.jpg)

![4a1631837a90fd0ae03433799834717760904880b07f8ae5de17d6b2f1c826b2.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/4a1631837a90fd0ae03433799834717760904880b07f8ae5de17d6b2f1c826b2.jpg)

![53ebbaa8baae4bfacfffb7ad4c910ec69f94f7cf6213dac6bf3e4ffe0bb06ce6.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/53ebbaa8baae4bfacfffb7ad4c910ec69f94f7cf6213dac6bf3e4ffe0bb06ce6.jpg)

![56b675d640b13b28789673c73ab7d9465ae22829d46833b9593faddc620f595e.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/56b675d640b13b28789673c73ab7d9465ae22829d46833b9593faddc620f595e.jpg)

![576f7ec1cac7631e9b3ac263bd6130b41b8eab6fb70d9d5ff0a6fa1576b3267e.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/576f7ec1cac7631e9b3ac263bd6130b41b8eab6fb70d9d5ff0a6fa1576b3267e.jpg)

![630c6b0b7037258a6dfd3034d4a043a2924e45dc3966a8404e80f82bc71e30e7.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/630c6b0b7037258a6dfd3034d4a043a2924e45dc3966a8404e80f82bc71e30e7.jpg)

![6853e2f9b3d8806cbb625f5d9f65f7ab47702806727ef183e9325e3b74489810.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/6853e2f9b3d8806cbb625f5d9f65f7ab47702806727ef183e9325e3b74489810.jpg)

![6ab031a0d67cd6a6e40f7d8394ea3fee346c496b9d6755b9c50ca933aa66b5ef.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/6ab031a0d67cd6a6e40f7d8394ea3fee346c496b9d6755b9c50ca933aa66b5ef.jpg)

![711a65ee2772b2acb87af39cb355a9135b1853852d5c79657ed310e8a1a6d019.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/711a65ee2772b2acb87af39cb355a9135b1853852d5c79657ed310e8a1a6d019.jpg)

![74389a8a86c5c3f3ef0dae95849dd3ea2347fbc2af6c78b83e72eccd54f213f5.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/74389a8a86c5c3f3ef0dae95849dd3ea2347fbc2af6c78b83e72eccd54f213f5.jpg)

![7bf50981b69eb6a70dae1853caaac596207a98e4abe85fae4e75a6b00cb61abd.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/7bf50981b69eb6a70dae1853caaac596207a98e4abe85fae4e75a6b00cb61abd.jpg)

![9d46129a9284f5315a78f318e741c768c21c21643d49b9872eb4c66b3e38c240.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/9d46129a9284f5315a78f318e741c768c21c21643d49b9872eb4c66b3e38c240.jpg)

![a129c86b93babf3ffd71abc2311f1cb12d6202b823f4e2c2edeaaf6c1898fafe.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/a129c86b93babf3ffd71abc2311f1cb12d6202b823f4e2c2edeaaf6c1898fafe.jpg)

![b5b199b1d6df30bcd8066ec74f0f84ca5fbb4c505acd0916cfaa44f9fd076cd0.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/b5b199b1d6df30bcd8066ec74f0f84ca5fbb4c505acd0916cfaa44f9fd076cd0.jpg)

![bf8b99532c8f7aa514462453fcc6abdcca3cfddd4959914fb43d0afd8359558f.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/bf8b99532c8f7aa514462453fcc6abdcca3cfddd4959914fb43d0afd8359558f.jpg)

![c83f56fd98bb6e9ba7e21c86c7fb20668d3d5fbf4836da55f283d97496eb7329.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/c83f56fd98bb6e9ba7e21c86c7fb20668d3d5fbf4836da55f283d97496eb7329.jpg)

![c90c6e2d75b419f4e77324a6a16d2c998d34528a59263af4ddc8a61cbb8386be.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/c90c6e2d75b419f4e77324a6a16d2c998d34528a59263af4ddc8a61cbb8386be.jpg)

![ce877abb366998e5ac8ff12f9191302c6c2a232974cab6a2592ed87ab3ab1c13.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/ce877abb366998e5ac8ff12f9191302c6c2a232974cab6a2592ed87ab3ab1c13.jpg)

![edd62ed29392b5a4996b51010e0778d088f8ad5a7029694cc3be6af32b4e5caa.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/edd62ed29392b5a4996b51010e0778d088f8ad5a7029694cc3be6af32b4e5caa.jpg)

![f478fcce8b3cb13f65ed729bd7185ac43f03d9fde262fc6c1eed3f0c83696473.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/f478fcce8b3cb13f65ed729bd7185ac43f03d9fde262fc6c1eed3f0c83696473.jpg)

![f8a9d01439ba4af4ef01313886b6bd7fa66e9a43c34a7ffc44a97c21f93260a3.jpg](../nips_results/538_A%20Token%20is%20Worth%20over%201%2C000%20Tokens_%20Efficient%20Knowledge%20Distillation%20through%20Low-Rank%20Clone/tables/f8a9d01439ba4af4ef01313886b6bd7fa66e9a43c34a7ffc44a97c21f93260a3.jpg)

## GeoLLaVA-8K: Scaling Remote-Sensing Multimodal Large Language Models to 8K Resolution


### Images

![0dd0714693b31588155efb02b83bbe4985e3ed6a225cf62ceb1cf2aa62257562.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/0dd0714693b31588155efb02b83bbe4985e3ed6a225cf62ceb1cf2aa62257562.jpg)

![1f072afc159bdf13e009b28a597017bbdc2864fd74b128ce6959c10feeac0550.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/1f072afc159bdf13e009b28a597017bbdc2864fd74b128ce6959c10feeac0550.jpg)

![255de39d2a43776d1e8ed96798f15abde63a2e17c7c413ffd47ddee09cf88836.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/255de39d2a43776d1e8ed96798f15abde63a2e17c7c413ffd47ddee09cf88836.jpg)

![3229680269fde545bdfde2d580fb4b4482e562c863d11b302c8407c0d8d44238.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/3229680269fde545bdfde2d580fb4b4482e562c863d11b302c8407c0d8d44238.jpg)

![476564794dc69b1fa539c234c0c27dda12e630d361c5e4a3bd47ff26e43ca824.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/476564794dc69b1fa539c234c0c27dda12e630d361c5e4a3bd47ff26e43ca824.jpg)

![53ce2e5743c54030926533cbdf2fc2aa7f55fb1fc9ced1787d7553fbf90964e1.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/53ce2e5743c54030926533cbdf2fc2aa7f55fb1fc9ced1787d7553fbf90964e1.jpg)

![57015e05b0ead6fd9c372948ca8ccde56aca4210938f7a17709b87586401f6e8.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/57015e05b0ead6fd9c372948ca8ccde56aca4210938f7a17709b87586401f6e8.jpg)

![6c18997243328df1082181a9552279c5d118cfafb45c6b9a0571bbb26d7174e6.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/6c18997243328df1082181a9552279c5d118cfafb45c6b9a0571bbb26d7174e6.jpg)

![6c1e1047168a1535fe1e95acc9347f7dd7f9fc0b32761fc445febd7cec3d9d56.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/6c1e1047168a1535fe1e95acc9347f7dd7f9fc0b32761fc445febd7cec3d9d56.jpg)

![77c87377b392412aa72c08de91eef6423bcf4dcac58802e4cbfa21fb1bfdd963.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/77c87377b392412aa72c08de91eef6423bcf4dcac58802e4cbfa21fb1bfdd963.jpg)

![cc18fec30888260d4642daf8d1ff6376ce4f0deb0ad664eb4bce76bf77417bd3.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/cc18fec30888260d4642daf8d1ff6376ce4f0deb0ad664eb4bce76bf77417bd3.jpg)

![d4df87fe9eb325925ebde05781c42f8f2e73fd52ccf4a9dd659da1f4f415cf84.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/d4df87fe9eb325925ebde05781c42f8f2e73fd52ccf4a9dd659da1f4f415cf84.jpg)

![e2132884efc8d1acee4b845b0a50fa90199a14cc69d1d1dd34db7b7ac72fe20f.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/e2132884efc8d1acee4b845b0a50fa90199a14cc69d1d1dd34db7b7ac72fe20f.jpg)

![ecd0716909e28e7e45104fa10436b03aa7d71f05c0f953ec47ded039cadb8138.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/ecd0716909e28e7e45104fa10436b03aa7d71f05c0f953ec47ded039cadb8138.jpg)

![ff25c0e10470a944f75c4813a38ad71df8480cdbdf0ec8d648ee1c0e2747f6d6.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/images/ff25c0e10470a944f75c4813a38ad71df8480cdbdf0ec8d648ee1c0e2747f6d6.jpg)

### Tables

![02fd96a939de8cd2d10212453e37a3fcc694f789e87b25e3ec94495a5e195c64.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/02fd96a939de8cd2d10212453e37a3fcc694f789e87b25e3ec94495a5e195c64.jpg)

![06f5c63151df1fdf4db403a9be6f898f25e6177953df40b004a13c3bd78fbe11.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/06f5c63151df1fdf4db403a9be6f898f25e6177953df40b004a13c3bd78fbe11.jpg)

![1027939c8185d44ee29e9b02247c62252599ab4b87a587a1f17b269779002574.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/1027939c8185d44ee29e9b02247c62252599ab4b87a587a1f17b269779002574.jpg)

![19f8b12c7115b963c42201eb048ba3ae3e90ac286b319e389010e3e174e424a1.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/19f8b12c7115b963c42201eb048ba3ae3e90ac286b319e389010e3e174e424a1.jpg)

![50c1f314719ce3146480fdba93ddbc200dd5391200db464c9638c75b55ece424.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/50c1f314719ce3146480fdba93ddbc200dd5391200db464c9638c75b55ece424.jpg)

![634704cd1f2516750ef04b9d0018c88297d7fcdc5de4a75efb9550f5227fa63e.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/634704cd1f2516750ef04b9d0018c88297d7fcdc5de4a75efb9550f5227fa63e.jpg)

![709be82d18bd29e5eb9ff961a89b1450c34672dd1305b8a119088a5847dab4bb.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/709be82d18bd29e5eb9ff961a89b1450c34672dd1305b8a119088a5847dab4bb.jpg)

![8fb262c8eb164589c04652031af57f9d1ce4c66d13774cf96aa3ad209db3d9dc.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/8fb262c8eb164589c04652031af57f9d1ce4c66d13774cf96aa3ad209db3d9dc.jpg)

![bbc479e25cbc80ab0c75cff399563220e91a82a149c6899ad9aa3f5e4d1ed518.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/bbc479e25cbc80ab0c75cff399563220e91a82a149c6899ad9aa3f5e4d1ed518.jpg)

![c85ee5eca26e4bfc630844033ee644edc65d8154c20e30f82bc4df5716c30063.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/c85ee5eca26e4bfc630844033ee644edc65d8154c20e30f82bc4df5716c30063.jpg)

![eca159c6952fa30a0f7c0f82f17d7a5867f86d60daf338dbf3aa049db517a4ee.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/eca159c6952fa30a0f7c0f82f17d7a5867f86d60daf338dbf3aa049db517a4ee.jpg)

![fceaa735e57bff181388e39afd6cb9db546e53692b7b4871b67a7320c3fdb9e4.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/fceaa735e57bff181388e39afd6cb9db546e53692b7b4871b67a7320c3fdb9e4.jpg)

![ffdd67392b9df6951cdf9515e631c59631e0b7e320c9ef780708edc4647dbb11.jpg](../nips_results/539_GeoLLaVA-8K_%20Scaling%20Remote-Sensing%20Multimodal%20Large%20Language%20Models%20to%208K%20Resolution/tables/ffdd67392b9df6951cdf9515e631c59631e0b7e320c9ef780708edc4647dbb11.jpg)

## NormFit: A Lightweight Solution for Few-Shot Federated Learning with Non-IID Data


### Images

![0bd7a831770d3f5b19f5f7fabfdf72bc9a97fdd138b22f91bae446ca55fbf2d9.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/images/0bd7a831770d3f5b19f5f7fabfdf72bc9a97fdd138b22f91bae446ca55fbf2d9.jpg)

![15400eb011666541485657e2aaacf3d81e97d4ef43d516c3e948bf431a2c8148.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/images/15400eb011666541485657e2aaacf3d81e97d4ef43d516c3e948bf431a2c8148.jpg)

![5856d688819e7344be6f368701c5337691a09947b4c6a2794f3c671347ce378a.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/images/5856d688819e7344be6f368701c5337691a09947b4c6a2794f3c671347ce378a.jpg)

![a695adbc2079dafe551d55fd859a3a291b50fb6f8456b0099dca8d8e547c4242.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/images/a695adbc2079dafe551d55fd859a3a291b50fb6f8456b0099dca8d8e547c4242.jpg)

![b83b8ad4179d4f4ddf71746554c18bffcfe52d6cea259d416e3fdba067585a2b.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/images/b83b8ad4179d4f4ddf71746554c18bffcfe52d6cea259d416e3fdba067585a2b.jpg)

![bb47ed76cef51d4ff1d1f3160497878b2ad423d90054f8b03246ab259c56c519.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/images/bb47ed76cef51d4ff1d1f3160497878b2ad423d90054f8b03246ab259c56c519.jpg)

![d4c23f8f63965753ab9d4fbf56399890bf4074652881b2bc87949f0dfc25be2c.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/images/d4c23f8f63965753ab9d4fbf56399890bf4074652881b2bc87949f0dfc25be2c.jpg)

![e28587dedfb9b291b34576e70a7fa83f9acbe8234378d3dc2b33190dd8fb7a20.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/images/e28587dedfb9b291b34576e70a7fa83f9acbe8234378d3dc2b33190dd8fb7a20.jpg)

![e9d2abbfe11779e64df989bb08b8d3237d7ce1e6d338ea04be90c34bfd71f71c.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/images/e9d2abbfe11779e64df989bb08b8d3237d7ce1e6d338ea04be90c34bfd71f71c.jpg)

### Tables

![3ef4e2da4f05db7944ad5aafe1fc91072472d2072d1d4ded003210c9e51daa3c.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/3ef4e2da4f05db7944ad5aafe1fc91072472d2072d1d4ded003210c9e51daa3c.jpg)

![89eb96ef88f63fc544f87fae3f36ae2cf91e3735d5819c034a5736ee92f5a7fb.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/89eb96ef88f63fc544f87fae3f36ae2cf91e3735d5819c034a5736ee92f5a7fb.jpg)

![af3796b61be36dc7fa65b890519295fb5299a21b350ec3fe70f8f4e47101dae5.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/af3796b61be36dc7fa65b890519295fb5299a21b350ec3fe70f8f4e47101dae5.jpg)

![b2cb4ee546adb44acb75a1352ba3b35f7fbaea189001902acde6b544bf920375.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/b2cb4ee546adb44acb75a1352ba3b35f7fbaea189001902acde6b544bf920375.jpg)

![b9a5430d1d546db8ceaa66e417f1ac984022dd5ef297f18037945740f77282e3.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/b9a5430d1d546db8ceaa66e417f1ac984022dd5ef297f18037945740f77282e3.jpg)

![bae4e55aaa4067aaefb2177634e14cf2abeb2b7a16b18891dc29ce5bb6285c48.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/bae4e55aaa4067aaefb2177634e14cf2abeb2b7a16b18891dc29ce5bb6285c48.jpg)

![be0ef13bd96a9c182dc3824afa741d62fb4f34efec2e78336a8f9a2abbe17da4.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/be0ef13bd96a9c182dc3824afa741d62fb4f34efec2e78336a8f9a2abbe17da4.jpg)

![ce867df45021613f067ae017055581539433e2f542c287a09d6294614146fb0f.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/ce867df45021613f067ae017055581539433e2f542c287a09d6294614146fb0f.jpg)

![ce96b4b3e4884266cfd13aaf5ec7a1d70428455efef9bbdf019122772fe0b1dc.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/ce96b4b3e4884266cfd13aaf5ec7a1d70428455efef9bbdf019122772fe0b1dc.jpg)

![cf2ebaaa5aa3a18c477cb5a27b745043149b210300b166bea7a1d5e91f6e464b.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/cf2ebaaa5aa3a18c477cb5a27b745043149b210300b166bea7a1d5e91f6e464b.jpg)

![efc43caecbe1d40100a70be071afabe8cad3fcf08c4c425bc6a2fe13bb5c9c5a.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/efc43caecbe1d40100a70be071afabe8cad3fcf08c4c425bc6a2fe13bb5c9c5a.jpg)

![ff8783c37d221fed231a854267bdc70a3441a1a95624ba72fe84460fa73d60d3.jpg](../nips_results/540_NormFit_%20A%20Lightweight%20Solution%20for%20Few-Shot%20Federated%20Learning%20with%20Non-IID%20Data/tables/ff8783c37d221fed231a854267bdc70a3441a1a95624ba72fe84460fa73d60d3.jpg)

## VPO: Reasoning Preferences Optimization Based on $\mathcal{V}$-Usable Information


### Images

![1fb3a6601eee5a826edd15a09dfdc94ec39ec6c7a75cb639932fc3a3b8310ff9.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/images/1fb3a6601eee5a826edd15a09dfdc94ec39ec6c7a75cb639932fc3a3b8310ff9.jpg)

![4002da625ae8974c1fdea1584a7dccdab718ed350188133cce7a7fb86588c714.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/images/4002da625ae8974c1fdea1584a7dccdab718ed350188133cce7a7fb86588c714.jpg)

![566d27913f329bb119dd52407716b27c15185794242e2d3279ddc75bb4e3e639.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/images/566d27913f329bb119dd52407716b27c15185794242e2d3279ddc75bb4e3e639.jpg)

![7bd073f1bd5004dcf03a69d613cec222a73ecc372f05e3318536f5971ec2169a.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/images/7bd073f1bd5004dcf03a69d613cec222a73ecc372f05e3318536f5971ec2169a.jpg)

![8c8225b08983060e8cc0eb0d3dbdd1a836a439d01036e0915ac96d36cbf62795.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/images/8c8225b08983060e8cc0eb0d3dbdd1a836a439d01036e0915ac96d36cbf62795.jpg)

![b940c215b24baf45a86c067c3c5c849c036ab691935b36d8732bd3eb1c4df7ae.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/images/b940c215b24baf45a86c067c3c5c849c036ab691935b36d8732bd3eb1c4df7ae.jpg)

![dd7bc7641d1a0f9ddbae077b39576eac53484c6c644f439b479b948d1fee06cf.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/images/dd7bc7641d1a0f9ddbae077b39576eac53484c6c644f439b479b948d1fee06cf.jpg)

![ff85c6d3db3e7e8bf2c955ac1db1024dd27027f913c4ced2348dbaf72cca4e77.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/images/ff85c6d3db3e7e8bf2c955ac1db1024dd27027f913c4ced2348dbaf72cca4e77.jpg)

### Tables

![1d73e6d40cefe329fb3e03df1b7e85e20ca73ed0cc1c127e45bc5928f308fd89.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/tables/1d73e6d40cefe329fb3e03df1b7e85e20ca73ed0cc1c127e45bc5928f308fd89.jpg)

![2bb1efe554386542296f68f72e6010a360c1c35976be7c834bc2d27863b2b206.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/tables/2bb1efe554386542296f68f72e6010a360c1c35976be7c834bc2d27863b2b206.jpg)

![36a54afce6b7e0e7c6e703e6e36c00da6e17ccf1d3744bd5d3d2472b9cca273f.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/tables/36a54afce6b7e0e7c6e703e6e36c00da6e17ccf1d3744bd5d3d2472b9cca273f.jpg)

![f20b9113569badc80e7bc3de33caf39b46431bd6203dcf4460e8b204ca9068de.jpg](../nips_results/541_VPO_%20Reasoning%20Preferences%20Optimization%20Based%20on%20%24_mathcal%7BV%7D%24-Usable%20Information/tables/f20b9113569badc80e7bc3de33caf39b46431bd6203dcf4460e8b204ca9068de.jpg)

## GaussianFusion: Gaussian-Based Multi-Sensor Fusion for End-to-End Autonomous Driving


### Images

![979450fb68c84e1414b993b3383b0c715e03b8fbd28c26d4613d99914ed06d09.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/images/979450fb68c84e1414b993b3383b0c715e03b8fbd28c26d4613d99914ed06d09.jpg)

![ad429d507df0a2d7547a1e0e9ad2f3456d53bc422fea40a0c80c64a0b0b31c21.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/images/ad429d507df0a2d7547a1e0e9ad2f3456d53bc422fea40a0c80c64a0b0b31c21.jpg)

![b2ccaacb69a532707d8daf146b2e9fde366781125a2691dd8c2b984b74d7cc8c.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/images/b2ccaacb69a532707d8daf146b2e9fde366781125a2691dd8c2b984b74d7cc8c.jpg)

![d3cff3d03e161739144566e36c7792395dcabbcf2f5abee25163dde85893462e.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/images/d3cff3d03e161739144566e36c7792395dcabbcf2f5abee25163dde85893462e.jpg)

![d7014f87f8fe5a404641a27a5ce27b26a1868e91a516aac4d6fee61496013da5.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/images/d7014f87f8fe5a404641a27a5ce27b26a1868e91a516aac4d6fee61496013da5.jpg)

![e0b0b4dbcfe9c60a022a3c6dc6f7c6e1265b1d47edea8d20b8e8c9e6c4b13328.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/images/e0b0b4dbcfe9c60a022a3c6dc6f7c6e1265b1d47edea8d20b8e8c9e6c4b13328.jpg)

### Tables

![0df6230b6cbc2f6420d28be165ead3d8747d4eb38af58f313ba0b59b7d3d8365.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/tables/0df6230b6cbc2f6420d28be165ead3d8747d4eb38af58f313ba0b59b7d3d8365.jpg)

![47468d038a7e4230e17964227997de2ff2a0f1fc6639acbf32c724cee296bb14.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/tables/47468d038a7e4230e17964227997de2ff2a0f1fc6639acbf32c724cee296bb14.jpg)

![54acc5ff1f349a3d5c03dc4c5aeff9316dfecc6689a9835652c9f00be9366345.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/tables/54acc5ff1f349a3d5c03dc4c5aeff9316dfecc6689a9835652c9f00be9366345.jpg)

![576a05fdfb7ae4e579f4bfbc5bc8d4b52df0486a234b2f37d6d3672efd66ef63.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/tables/576a05fdfb7ae4e579f4bfbc5bc8d4b52df0486a234b2f37d6d3672efd66ef63.jpg)

![70470dcac4017e0dca4fcde83fa82db69d6c3b7af0b03dffcb14443cc1cdd991.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/tables/70470dcac4017e0dca4fcde83fa82db69d6c3b7af0b03dffcb14443cc1cdd991.jpg)

![a7ffffc454ab4640a9499fbbaa663b5e4dc324e2d6e6ea2cc2f08e33e38d613d.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/tables/a7ffffc454ab4640a9499fbbaa663b5e4dc324e2d6e6ea2cc2f08e33e38d613d.jpg)

![b02e2dd689ede23f7b394fd581f2e526484140c76143f3ba06c7e648df396e10.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/tables/b02e2dd689ede23f7b394fd581f2e526484140c76143f3ba06c7e648df396e10.jpg)

![cd727612bb797e02d20d8d23387044d1f3e98c390d96ab82ea56ec8d32f96408.jpg](../nips_results/542_GaussianFusion_%20Gaussian-Based%20Multi-Sensor%20Fusion%20for%20End-to-End%20Autonomous%20Driving/tables/cd727612bb797e02d20d8d23387044d1f3e98c390d96ab82ea56ec8d32f96408.jpg)

## Accelerating Optimization via Differentiable Stopping Time


### Images

![31988ff7fa8768e4c9a8f302c7402b462e9800a048ea9661db4653fb9a95a771.jpg](../nips_results/543_Accelerating%20Optimization%20via%20Differentiable%20Stopping%20Time/images/31988ff7fa8768e4c9a8f302c7402b462e9800a048ea9661db4653fb9a95a771.jpg)

![79b3d354f566dbe9c82a38f17d1f90e3c7ec6438faa4ba78b4dbb65cb5dbcbc6.jpg](../nips_results/543_Accelerating%20Optimization%20via%20Differentiable%20Stopping%20Time/images/79b3d354f566dbe9c82a38f17d1f90e3c7ec6438faa4ba78b4dbb65cb5dbcbc6.jpg)

![8c7f878774607b09a1f0742fb1383a7142d7408ea87008cc6af3c98576987c9b.jpg](../nips_results/543_Accelerating%20Optimization%20via%20Differentiable%20Stopping%20Time/images/8c7f878774607b09a1f0742fb1383a7142d7408ea87008cc6af3c98576987c9b.jpg)

![b945bbf3e4cb6db2c394dc40983f0cadddb5f2ed3fbd1a910e77a5876f47ff5b.jpg](../nips_results/543_Accelerating%20Optimization%20via%20Differentiable%20Stopping%20Time/images/b945bbf3e4cb6db2c394dc40983f0cadddb5f2ed3fbd1a910e77a5876f47ff5b.jpg)

![b9fe47f24adba60f0b8eb8889124c4619a4379346339c1bbbbe1a542edd6656c.jpg](../nips_results/543_Accelerating%20Optimization%20via%20Differentiable%20Stopping%20Time/images/b9fe47f24adba60f0b8eb8889124c4619a4379346339c1bbbbe1a542edd6656c.jpg)

![ccf984091a3182cec49cf3eeac6011d9776147ea2230873ce97807e54da88605.jpg](../nips_results/543_Accelerating%20Optimization%20via%20Differentiable%20Stopping%20Time/images/ccf984091a3182cec49cf3eeac6011d9776147ea2230873ce97807e54da88605.jpg)

### Tables

![c789b3885f857eaf37200ae08cfd0cdf2a585870362ffab0081a7e7f0611ac76.jpg](../nips_results/543_Accelerating%20Optimization%20via%20Differentiable%20Stopping%20Time/tables/c789b3885f857eaf37200ae08cfd0cdf2a585870362ffab0081a7e7f0611ac76.jpg)

## Abstain Mask Retain Core: Time Series Prediction by Adaptive Masking Loss with Representation Consistency


### Images

![253cdbca6069292c9d898a01d9adf3355cdf6813cf86b9f1d41588f523c39c41.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/images/253cdbca6069292c9d898a01d9adf3355cdf6813cf86b9f1d41588f523c39c41.jpg)

![69c0ce145b553ec454156573430a47f694b7e96cee9b648d4cc533d348bdfe8f.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/images/69c0ce145b553ec454156573430a47f694b7e96cee9b648d4cc533d348bdfe8f.jpg)

![9ff74abda08848eba48c5fbfe68c8da58b14db09a9bf75cce099284160ddd7df.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/images/9ff74abda08848eba48c5fbfe68c8da58b14db09a9bf75cce099284160ddd7df.jpg)

![d5ceea378d55587ec083575b8023dc1fcbd6f7b69d8c2abe2f435bc791a74ed1.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/images/d5ceea378d55587ec083575b8023dc1fcbd6f7b69d8c2abe2f435bc791a74ed1.jpg)

### Tables

![06b83db413fb733453ee0121d0b3f1eb6429dc1a2f65e2468552e2583f0e3deb.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/tables/06b83db413fb733453ee0121d0b3f1eb6429dc1a2f65e2468552e2583f0e3deb.jpg)

![07341143c65251f4186722b51f3ece376ceee4d2a08abc9fe04bf24e01b9b6b7.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/tables/07341143c65251f4186722b51f3ece376ceee4d2a08abc9fe04bf24e01b9b6b7.jpg)

![0a4427fde830ee745ffa5244fb544d49f4ce9033569f06ee8152f482dddfb8bd.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/tables/0a4427fde830ee745ffa5244fb544d49f4ce9033569f06ee8152f482dddfb8bd.jpg)

![1fb74e76fce2ac65ad04b48126502a7c5f4f1daa6bffb9bb9bb41ad63a9dae09.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/tables/1fb74e76fce2ac65ad04b48126502a7c5f4f1daa6bffb9bb9bb41ad63a9dae09.jpg)

![58a1c4ac23f0df4d8b8fec982ff4eae89e1c63c68d7d5d37bdaa52e10e666e91.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/tables/58a1c4ac23f0df4d8b8fec982ff4eae89e1c63c68d7d5d37bdaa52e10e666e91.jpg)

![5b37cbd2ef3ee6a37f1d9664989db0b21debf44851156295e13850c0fd595e94.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/tables/5b37cbd2ef3ee6a37f1d9664989db0b21debf44851156295e13850c0fd595e94.jpg)

![71c7b3f11d0a07bb9125efc6f63b4b3248691559301a78b3407e00ff4af007de.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/tables/71c7b3f11d0a07bb9125efc6f63b4b3248691559301a78b3407e00ff4af007de.jpg)

![869dfbc5ea57e53f2cc8cecb284f8b8e2fea7a1c95bb7360c86dccebc35d70a3.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/tables/869dfbc5ea57e53f2cc8cecb284f8b8e2fea7a1c95bb7360c86dccebc35d70a3.jpg)

![92ab9bd6c0573d3460d6af81be9e47b760f7609f992445774c814be8c1d0999f.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/tables/92ab9bd6c0573d3460d6af81be9e47b760f7609f992445774c814be8c1d0999f.jpg)

![b7032402fca119b4637c445b7d10af2b41df2e35c4a8d18ffb1169255688da1a.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/tables/b7032402fca119b4637c445b7d10af2b41df2e35c4a8d18ffb1169255688da1a.jpg)

![d7a92160cdc21dc906af8ec347c683feacb0a6111a9f249fc46d387d0de3bbdf.jpg](../nips_results/544_Abstain%20Mask%20Retain%20Core_%20Time%20Series%20Prediction%20by%20Adaptive%20Masking%20Loss%20with%20Representation%20Consis/tables/d7a92160cdc21dc906af8ec347c683feacb0a6111a9f249fc46d387d0de3bbdf.jpg)

## Amortized Variational Transdimensional Inference

### Images

![0324c5d757455e2b48c4fdf4e7d8e69b0bf4b8c260934f6e0799e30cc9848018.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/images/0324c5d757455e2b48c4fdf4e7d8e69b0bf4b8c260934f6e0799e30cc9848018.jpg)

![528893469fab2dd6fdcb1706799cdb99cddf867799d67d565195e3dd45655636.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/images/528893469fab2dd6fdcb1706799cdb99cddf867799d67d565195e3dd45655636.jpg)

![5ec84b502bc22a450a4ec8f7a69d8bf57eea667dea74ebd7ecca90af49548c43.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/images/5ec84b502bc22a450a4ec8f7a69d8bf57eea667dea74ebd7ecca90af49548c43.jpg)

![5ee0e9f6ce128161679a03bc2a6e90346fdab70ae5e0e71afc570d019dc2226a.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/images/5ee0e9f6ce128161679a03bc2a6e90346fdab70ae5e0e71afc570d019dc2226a.jpg)

![6addf4f2774a00475947785621b40ada8fdc7d356c32cc9809e4086f97eaac61.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/images/6addf4f2774a00475947785621b40ada8fdc7d356c32cc9809e4086f97eaac61.jpg)

![7cd35458ed2b12d37d18fcbf7723c381f0aee38ba4374a2ed6e539f8adb001cb.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/images/7cd35458ed2b12d37d18fcbf7723c381f0aee38ba4374a2ed6e539f8adb001cb.jpg)

![83b1ece2636f62b08d80047adf08bdf7470c22a2d27a668ab0d086cc732f4793.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/images/83b1ece2636f62b08d80047adf08bdf7470c22a2d27a668ab0d086cc732f4793.jpg)

![9d9e1df4ca08dd8cfc13fb53414b271192a433c91f99446837abfd04ebc5dece.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/images/9d9e1df4ca08dd8cfc13fb53414b271192a433c91f99446837abfd04ebc5dece.jpg)

![bf47556d34bcfd986ba38e603baf7d7af4cc9d2e3148c0185665e3037a904a43.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/images/bf47556d34bcfd986ba38e603baf7d7af4cc9d2e3148c0185665e3037a904a43.jpg)

![cb6162e496ed6905c3fbf9f5fc2ab9e82262afc5fc94243a7a60fba3ad9b4f93.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/images/cb6162e496ed6905c3fbf9f5fc2ab9e82262afc5fc94243a7a60fba3ad9b4f93.jpg)

![ee40a20975c93220574806c7348fa3531c89e86993375a9c7c0bf804c0af1d30.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/images/ee40a20975c93220574806c7348fa3531c89e86993375a9c7c0bf804c0af1d30.jpg)

### Tables

![4136f2bdd0895771d75d900b0c99d911a313f27afddedff0efadb6e6b6bc8f60.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/tables/4136f2bdd0895771d75d900b0c99d911a313f27afddedff0efadb6e6b6bc8f60.jpg)

![4261bfe0f9f8b0cfc6fad9f54c52663a9e74fb1648d1db2f291f6a34df8038e3.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/tables/4261bfe0f9f8b0cfc6fad9f54c52663a9e74fb1648d1db2f291f6a34df8038e3.jpg)

![5cda354d03daa9a8f83f15419b1fdfc2236567e5bd99a1e70fae1321763b98bd.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/tables/5cda354d03daa9a8f83f15419b1fdfc2236567e5bd99a1e70fae1321763b98bd.jpg)

![cf81065a4cac0abb7d69ddab3442dc1ba7b3031295675558ac7313d8dc35486b.jpg](../nips_results/545_Amortized%20Variational%20Transdimensional%20Inference/tables/cf81065a4cac0abb7d69ddab3442dc1ba7b3031295675558ac7313d8dc35486b.jpg)
