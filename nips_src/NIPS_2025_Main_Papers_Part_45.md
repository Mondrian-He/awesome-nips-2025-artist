# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 45 of 130

## 目录 (Table of Contents)

1. [Uncertainty-Aware Multi-Objective Reinforcement Learning-Guided Diffusion Models for 3D De Novo Molecular Design](#Uncertainty-Aware-Multi-Objective-Reinforcement-Learning-Guided-Diffusion-Models-for-3D-De-Novo-Molecular-Design)
2. [Mitigating Reward Over-optimization in Direct Alignment Algorithms with Importance Sampling](#Mitigating-Reward-Over-optimization-in-Direct-Alignment-Algorithms-with-Importance-Sampling)
3. [VTON-VLLM: Aligning Virtual Try-On Models with Human Preferences](#VTON-VLLM-Aligning-Virtual-Try-On-Models-with-Human-Preferences)
4. [Prompt-guided Disentangled Representation for Action Recognition](#Prompt-guided-Disentangled-Representation-for-Action-Recognition)
5. [On the creation of narrow AI: hierarchy and nonlocality of neural network skills](#On-the-creation-of-narrow-AI-hierarchy-and-nonlocality-of-neural-network-skills)
6. [Direct Alignment with Heterogeneous Preferences](#Direct-Alignment-with-Heterogeneous-Preferences)
7. [Routing Mamba: Scaling State Space Models with Mixture-of-Experts Projection](#Routing-Mamba-Scaling-State-Space-Models-with-Mixture-of-Experts-Projection)
8. [Train with Perturbation, Infer after Merging: A Two-Stage Framework for Continual Learning](#Train-with-Perturbation-Infer-after-Merging-A-Two-Stage-Framework-for-Continual-Learning)
9. [FACE: A General Framework for Mapping Collaborative Filtering Embeddings into LLM Tokens](#FACE-A-General-Framework-for-Mapping-Collaborative-Filtering-Embeddings-into-LLM-Tokens)
10. [Towards a General Attention Framework on Gyrovector Spaces for Matrix Manifolds](#Towards-a-General-Attention-Framework-on-Gyrovector-Spaces-for-Matrix-Manifolds)
11. [Adaptive Riemannian ADMM for Nonsmooth Optimization: Optimal Complexity without Smoothing](#Adaptive-Riemannian-ADMM-for-Nonsmooth-Optimization-Optimal-Complexity-without-Smoothing)
12. [Graphs Help Graphs: Multi-Agent Graph Socialized Learning](#Graphs-Help-Graphs-Multi-Agent-Graph-Socialized-Learning)
13. [ConceptScope: Characterizing Dataset Bias via Disentangled Visual Concepts](#ConceptScope-Characterizing-Dataset-Bias-via-Disentangled-Visual-Concepts)
14. [AutoPartGen: Autoregressive 3D Part Generation and Discovery](#AutoPartGen-Autoregressive-3D-Part-Generation-and-Discovery)
15. [Scaling Data-Driven Probabilistic Robustness Analysis for Semantic Segmentation Neural Networks](#Scaling-Data-Driven-Probabilistic-Robustness-Analysis-for-Semantic-Segmentation-Neural-Networks)
16. [Securing the Language of Life: Inheritable Watermarks from DNA Language Models to Proteins](#Securing-the-Language-of-Life-Inheritable-Watermarks-from-DNA-Language-Models-to-Proteins)
17. [Conformal Prediction in The Loop: A Feedback-Based Uncertainty Model for Trajectory Optimization](#Conformal-Prediction-in-The-Loop-A-Feedback-Based-Uncertainty-Model-for-Trajectory-Optimization)
18. [Pin the Tail on the Model: Blindfolded Repair of User-Flagged Failures in Text-to-Image Services](#Pin-the-Tail-on-the-Model-Blindfolded-Repair-of-User-Flagged-Failures-in-Text-to-Image-Services)
19. [Analytic Energy-Guided Policy Optimization for Offline Reinforcement Learning](#Analytic-Energy-Guided-Policy-Optimization-for-Offline-Reinforcement-Learning)
20. [Flatness is Necessary, Neural Collapse is Not: Rethinking Generalization via Grokking](#Flatness-is-Necessary-Neural-Collapse-is-Not-Rethinking-Generalization-via-Grokking)
21. [Do Neural Networks Need Gradient Descent to Generalize? A Theoretical Study](#Do-Neural-Networks-Need-Gradient-Descent-to-Generalize-A-Theoretical-Study)
22. [The Quest for Universal Master Key Filters in DS-CNNs](#The-Quest-for-Universal-Master-Key-Filters-in-DS-CNNs)
23. [Filter Like You Test: Data-Driven Data Filtering for CLIP Pretraining](#Filter-Like-You-Test-Data-Driven-Data-Filtering-for-CLIP-Pretraining)
24. [Gated Integration of Low-Rank Adaptation for Continual Learning  of Large Language Models](#Gated-Integration-of-Low-Rank-Adaptation-for-Continual-Learning-of-Large-Language-Models)
25. [Addressing Mark Imbalance in Integration-free Marked Temporal Point Processes](#Addressing-Mark-Imbalance-in-Integration-free-Marked-Temporal-Point-Processes)
26. [Towards Unified Multimodal Interleaved Generation via Group Relative Policy Optimization](#Towards-Unified-Multimodal-Interleaved-Generation-via-Group-Relative-Policy-Optimization)
27. [Smooth Sailing: Lipschitz-Driven Uncertainty Quantification for Spatial Associations](#Smooth-Sailing-Lipschitz-Driven-Uncertainty-Quantification-for-Spatial-Associations)
28. [LaM-SLidE: Latent Space Modeling of Spatial Dynamical Systems via Linked Entities](#LaM-SLidE-Latent-Space-Modeling-of-Spatial-Dynamical-Systems-via-Linked-Entities)
29. [From Human Attention to Diagnosis: Semantic Patch-Level Integration of Vision-Language Models in Medical Imaging](#From-Human-Attention-to-Diagnosis-Semantic-Patch-Level-Integration-of-Vision-Language-Models-in-Medical-Imaging)
30. [$\mu$PC: Scaling Predictive Coding to 100+ Layer Networks](#muPC-Scaling-Predictive-Coding-to-100-Layer-Networks)
31. [SplitFlow: Flow Decomposition for Inversion-Free Text-to-Image Editing](#SplitFlow-Flow-Decomposition-for-Inversion-Free-Text-to-Image-Editing)
32. [GOOD: Training-Free Guided Diffusion Sampling for Out-of-Distribution Detection](#GOOD-Training-Free-Guided-Diffusion-Sampling-for-Out-of-Distribution-Detection)
33. [A Closer Look at TabPFN v2: Understanding Its Strengths and Extending Its Capabilities](#A-Closer-Look-at-TabPFN-v2-Understanding-Its-Strengths-and-Extending-Its-Capabilities)
34. [Vinci: Deep Thinking in Text-to-Image Generation using Unified Model with Reinforcement Learning](#Vinci-Deep-Thinking-in-Text-to-Image-Generation-using-Unified-Model-with-Reinforcement-Learning)
35. [Timely Clinical Diagnosis through Active Test Selection](#Timely-Clinical-Diagnosis-through-Active-Test-Selection)
36. [SmartCache: Context-aware Semantic Cache for Efficient Multi-turn LLM Inference](#SmartCache-Context-aware-Semantic-Cache-for-Efficient-Multi-turn-LLM-Inference)
37. [Don't be lazy: CompleteP enables compute-efficient deep transformers](#Dont-be-lazy-CompleteP-enables-compute-efficient-deep-transformers)
38. [Approximating Shapley Explanations in Reinforcement Learning](#Approximating-Shapley-Explanations-in-Reinforcement-Learning)
39. [HYPRL: Reinforcement Learning of Control Policies for Hyperproperties](#HYPRL-Reinforcement-Learning-of-Control-Policies-for-Hyperproperties)
40. [Robust Hyperbolic Learning with Curvature-Aware Optimization](#Robust-Hyperbolic-Learning-with-Curvature-Aware-Optimization)
41. [Wan-Move: Motion-controllable Video Generation via Latent Trajectory Guidance](#Wan-Move-Motion-controllable-Video-Generation-via-Latent-Trajectory-Guidance)

---


## Uncertainty-Aware Multi-Objective Reinforcement Learning-Guided Diffusion Models for 3D De Novo Molecular Design

### Images

![0e6f10df94497640c27be988e7c75f5978bf806c1ff094409cb957dfef2a4b61.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/images/0e6f10df94497640c27be988e7c75f5978bf806c1ff094409cb957dfef2a4b61.jpg)

![10d229c35bad0c873fc46e2a321f806efc2c61a24476fffd63e67f47a52bb300.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/images/10d229c35bad0c873fc46e2a321f806efc2c61a24476fffd63e67f47a52bb300.jpg)

![15b0c218dbf12460de52c7c2426b6dda135604c624f9d012afa031d9c0a20b99.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/images/15b0c218dbf12460de52c7c2426b6dda135604c624f9d012afa031d9c0a20b99.jpg)

![520c0f52301ae5a54ab97549c5ba700f983370ea6f485b1fb4dbaaacb2672aed.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/images/520c0f52301ae5a54ab97549c5ba700f983370ea6f485b1fb4dbaaacb2672aed.jpg)

![60bb3a109c88c2ebd3b20fd95eb05a0a1c2fad63b9e49d927d6eb6576a643429.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/images/60bb3a109c88c2ebd3b20fd95eb05a0a1c2fad63b9e49d927d6eb6576a643429.jpg)

![666a6c634e3bd551033fd9feb4aaebd508a9a86dfe44af8e38d14e28c4cec7ac.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/images/666a6c634e3bd551033fd9feb4aaebd508a9a86dfe44af8e38d14e28c4cec7ac.jpg)

![9f4a9186984373e71a83d5b3741aacebfdff3245eb0d64a382e04d251ae3fae3.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/images/9f4a9186984373e71a83d5b3741aacebfdff3245eb0d64a382e04d251ae3fae3.jpg)

![a3282a5f95f7f95836b1bfb1a30ef7912a779237f55f427c9db3493b5f6bd6a5.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/images/a3282a5f95f7f95836b1bfb1a30ef7912a779237f55f427c9db3493b5f6bd6a5.jpg)

![a6637efa6a20a34b9c23b334c020f1cbf6aef7aee645693fb164f2a0e509709a.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/images/a6637efa6a20a34b9c23b334c020f1cbf6aef7aee645693fb164f2a0e509709a.jpg)

![a9ea6e87680e24bb5a411dc6dcf0c5e39a45a23d02d9b39ef1c825da56ba3e3b.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/images/a9ea6e87680e24bb5a411dc6dcf0c5e39a45a23d02d9b39ef1c825da56ba3e3b.jpg)

![c4514c1c7d4079283ac11b3b78ce54faec188ce8dfef9de5404cb6fb3a17f3d5.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/images/c4514c1c7d4079283ac11b3b78ce54faec188ce8dfef9de5404cb6fb3a17f3d5.jpg)

### Tables

![0e26190515742173de59ebac4921513a8610453e10035aaf2d6e3338905db1f3.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/0e26190515742173de59ebac4921513a8610453e10035aaf2d6e3338905db1f3.jpg)

![1a123596518b8dfadc9eec3080d350d5baede9dec5834a06b5eddfc890a01079.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/1a123596518b8dfadc9eec3080d350d5baede9dec5834a06b5eddfc890a01079.jpg)

![21a4706f244d3f6af9dcb96285ef90ed0dc049b25237006e797c98035c84cb83.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/21a4706f244d3f6af9dcb96285ef90ed0dc049b25237006e797c98035c84cb83.jpg)

![26f5350a5df1298a1959ea78cc2482ce3d110e8bf3e194de68b2ffb7e5a23efa.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/26f5350a5df1298a1959ea78cc2482ce3d110e8bf3e194de68b2ffb7e5a23efa.jpg)

![4f190f70f5500b36fa2561b3caab9705bb6e1b11b062078296498b99565163e7.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/4f190f70f5500b36fa2561b3caab9705bb6e1b11b062078296498b99565163e7.jpg)

![668702ac289a0900d3b062be4aa4372d542898ed9fb44b02431e8398e8e976e5.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/668702ac289a0900d3b062be4aa4372d542898ed9fb44b02431e8398e8e976e5.jpg)

![8c9d91474a6ae1992cee023a875c7a08bd9ec7f4a9d8aaa1bc05952185dee1c7.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/8c9d91474a6ae1992cee023a875c7a08bd9ec7f4a9d8aaa1bc05952185dee1c7.jpg)

![a070d35888a4e487fe74f40835ec1ba92e41f9a6918f8741cfbecc77322c4077.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/a070d35888a4e487fe74f40835ec1ba92e41f9a6918f8741cfbecc77322c4077.jpg)

![b19b1a5132ae59a5eac9211ef42f47250501ed3a19ec645886074498eec86201.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/b19b1a5132ae59a5eac9211ef42f47250501ed3a19ec645886074498eec86201.jpg)

![b234dfd20f600eb1b71b7b5c314018f99c7919f4a4b6321af50a2fde388f7698.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/b234dfd20f600eb1b71b7b5c314018f99c7919f4a4b6321af50a2fde388f7698.jpg)

![e4108c6d48e6720cb7fab793597ca553923fcf2dbb0a7637f0cd6fd164957338.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/e4108c6d48e6720cb7fab793597ca553923fcf2dbb0a7637f0cd6fd164957338.jpg)

![e73781d3113b9503cf9d613bf3098833b8a778107f3a4c09cb5896ddaeead34a.jpg](../nips_results/1828_Pruning%20Spurious%20Subgraphs%20for%20Graph%20Out-of-Distribution%20Generalization/tables/e73781d3113b9503cf9d613bf3098833b8a778107f3a4c09cb5896ddaeead34a.jpg)

## Uncertainty-Aware Multi-Objective Reinforcement Learning-Guided Diffusion Models for 3D De Novo Molecular Design


### Images

![5146cfec1967fdb8147e009884995f957a66e9239f3ebf8d22ef473771b6f7d8.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/images/5146cfec1967fdb8147e009884995f957a66e9239f3ebf8d22ef473771b6f7d8.jpg)

![5e9ba2c43d1e9534aae53b6a95217593889de67e05eb78d228f412e26cab1e49.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/images/5e9ba2c43d1e9534aae53b6a95217593889de67e05eb78d228f412e26cab1e49.jpg)

![7a7f41f86defb59f19eb0198504ad65008b8cfbf5b4b6f8329a43e2852a2a59d.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/images/7a7f41f86defb59f19eb0198504ad65008b8cfbf5b4b6f8329a43e2852a2a59d.jpg)

![872684775e51c9ec379659e56abe5f711aea7f4e9d6161e5c7f77bf4cf9b2fd1.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/images/872684775e51c9ec379659e56abe5f711aea7f4e9d6161e5c7f77bf4cf9b2fd1.jpg)

![8d5b7e8a1996a7216528ab83c8c3d8535df0ca6fd25274656d8a9464a9e19a31.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/images/8d5b7e8a1996a7216528ab83c8c3d8535df0ca6fd25274656d8a9464a9e19a31.jpg)

![8ec2fb992164e92c2be43ed249e207419c2e82b0b4a62b069efb1fb5bf53b8c4.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/images/8ec2fb992164e92c2be43ed249e207419c2e82b0b4a62b069efb1fb5bf53b8c4.jpg)

![9cbe23a322e66dfd4ac50eb5ea81f3dff19800608c361070a4ffaf915aa0c9e4.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/images/9cbe23a322e66dfd4ac50eb5ea81f3dff19800608c361070a4ffaf915aa0c9e4.jpg)

![d46a9ab7345e7b1ce71448ea7a7dcb254496a5cc9e011a350c0000e0c602342d.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/images/d46a9ab7345e7b1ce71448ea7a7dcb254496a5cc9e011a350c0000e0c602342d.jpg)

![fe870097c65c4219075bc2084415f8e8b90ab856b13dc89beb23848f23ed2ee1.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/images/fe870097c65c4219075bc2084415f8e8b90ab856b13dc89beb23848f23ed2ee1.jpg)

### Tables

![1a85a92b569720853fe4f2f06d1eb4567302b21c164ba892798310249a6905d1.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/1a85a92b569720853fe4f2f06d1eb4567302b21c164ba892798310249a6905d1.jpg)

![3e6b065e5ee48fe377390d5500f5d9971d19edde759524992c858c29c7d85607.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/3e6b065e5ee48fe377390d5500f5d9971d19edde759524992c858c29c7d85607.jpg)

![705b59755ef4484d32d357a594bf2433e1d2959f8467696dfc0e59a58fac360b.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/705b59755ef4484d32d357a594bf2433e1d2959f8467696dfc0e59a58fac360b.jpg)

![7196955b4f81a1e33d5a9e92aab4898a74bcb939b9006ef26e6aff4d5311eaba.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/7196955b4f81a1e33d5a9e92aab4898a74bcb939b9006ef26e6aff4d5311eaba.jpg)

![784c555dd12ed015c2625b34862552a2848017f68047840b6a6f468a46890bdf.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/784c555dd12ed015c2625b34862552a2848017f68047840b6a6f468a46890bdf.jpg)

![98dd570e0dd9c18a055d25efdae93fc3491701ddf69367cffcab0e87e9099ca6.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/98dd570e0dd9c18a055d25efdae93fc3491701ddf69367cffcab0e87e9099ca6.jpg)

![9e9c7bb7b467c89219bbef4f497f3b0849de89c42bb936b8119290a20f140ded.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/9e9c7bb7b467c89219bbef4f497f3b0849de89c42bb936b8119290a20f140ded.jpg)

![b0011b12ce6de7b7c850404fdfb6087dd5b1182230dada9f2fa59b3f03c74c7d.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/b0011b12ce6de7b7c850404fdfb6087dd5b1182230dada9f2fa59b3f03c74c7d.jpg)

![b2037c7276463407b0a54e0e55f1dc5e386b5c21c503f0ed9d98194a2069ffa5.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/b2037c7276463407b0a54e0e55f1dc5e386b5c21c503f0ed9d98194a2069ffa5.jpg)

![bc77cf5b9329fafb57ced704b1e2af1416e2d8f766e51771b5d8779e2dda1d59.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/bc77cf5b9329fafb57ced704b1e2af1416e2d8f766e51771b5d8779e2dda1d59.jpg)

![bd32067114c705932e2aaf085e4bb5a4d9f83d6f10a8252fb09166fdc06bf703.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/bd32067114c705932e2aaf085e4bb5a4d9f83d6f10a8252fb09166fdc06bf703.jpg)

![c9606d3c827b82bd1e602e25ed10a0e39ff20c25c0b5ef5003f1ca0c1f280a4d.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/c9606d3c827b82bd1e602e25ed10a0e39ff20c25c0b5ef5003f1ca0c1f280a4d.jpg)

![d3c667376a7f3e1ed62f020f2ec763e0f662780deac957c5fe5ae06833c0a151.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/d3c667376a7f3e1ed62f020f2ec763e0f662780deac957c5fe5ae06833c0a151.jpg)

![e200d494f7a217d77a660459a3032f87c0ca22b66671d676cd5766d388cdb8f8.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/e200d494f7a217d77a660459a3032f87c0ca22b66671d676cd5766d388cdb8f8.jpg)

![f319fe054e278a28759485e2979080ad01a79d8803353595259186f581aa4360.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/f319fe054e278a28759485e2979080ad01a79d8803353595259186f581aa4360.jpg)

![ff7b6ce994aa46f04a48a6ff2bd7815bd217237eb31a57055edeb0db1e883068.jpg](../nips_results/1829_Uncertainty-Aware%20Multi-Objective%20Reinforcement%20Learning-Guided%20Diffusion%20Models%20for%203D%20De%20Novo%20Mole/tables/ff7b6ce994aa46f04a48a6ff2bd7815bd217237eb31a57055edeb0db1e883068.jpg)

## Mitigating Reward Over-optimization in Direct Alignment Algorithms with Importance Sampling


### Images

![124898857eea4e74493478ca8b85ec4651e0c48b4fddbff0aa3683d5bfddf701.jpg](../nips_results/1830_Mitigating%20Reward%20Over-optimization%20in%20Direct%20Alignment%20Algorithms%20with%20Importance%20Sampling/images/124898857eea4e74493478ca8b85ec4651e0c48b4fddbff0aa3683d5bfddf701.jpg)

![38affe36e65f918ded7652e40bea128f1fd1d058ad256900888e9a5ab162ea5c.jpg](../nips_results/1830_Mitigating%20Reward%20Over-optimization%20in%20Direct%20Alignment%20Algorithms%20with%20Importance%20Sampling/images/38affe36e65f918ded7652e40bea128f1fd1d058ad256900888e9a5ab162ea5c.jpg)

![7ec1870c9216e97cc99a66817c57ad32fb4682ac365c46700b6f25e914866d1a.jpg](../nips_results/1830_Mitigating%20Reward%20Over-optimization%20in%20Direct%20Alignment%20Algorithms%20with%20Importance%20Sampling/images/7ec1870c9216e97cc99a66817c57ad32fb4682ac365c46700b6f25e914866d1a.jpg)

![89115bb4028ce9ff562a9e8f636f027cd4832f8c94c8a5be983531d3c47ad95c.jpg](../nips_results/1830_Mitigating%20Reward%20Over-optimization%20in%20Direct%20Alignment%20Algorithms%20with%20Importance%20Sampling/images/89115bb4028ce9ff562a9e8f636f027cd4832f8c94c8a5be983531d3c47ad95c.jpg)

![b1b35132e78cda845227ec41cefaee682040e29de2f68ca6b05db9d3b03368b3.jpg](../nips_results/1830_Mitigating%20Reward%20Over-optimization%20in%20Direct%20Alignment%20Algorithms%20with%20Importance%20Sampling/images/b1b35132e78cda845227ec41cefaee682040e29de2f68ca6b05db9d3b03368b3.jpg)

![c292407128328f0b103faefc760a0f374d7b639a1d8f52e50e91489311c4a446.jpg](../nips_results/1830_Mitigating%20Reward%20Over-optimization%20in%20Direct%20Alignment%20Algorithms%20with%20Importance%20Sampling/images/c292407128328f0b103faefc760a0f374d7b639a1d8f52e50e91489311c4a446.jpg)

![d6ea55cd5ff6bf427fdae24f78d4ed282c5b45c02b5f425361ff6cd213367a91.jpg](../nips_results/1830_Mitigating%20Reward%20Over-optimization%20in%20Direct%20Alignment%20Algorithms%20with%20Importance%20Sampling/images/d6ea55cd5ff6bf427fdae24f78d4ed282c5b45c02b5f425361ff6cd213367a91.jpg)

![f13af1af395a39d8d6e0faee0ea43cf437ab47a4deb2db4b571f95b1e9b561c6.jpg](../nips_results/1830_Mitigating%20Reward%20Over-optimization%20in%20Direct%20Alignment%20Algorithms%20with%20Importance%20Sampling/images/f13af1af395a39d8d6e0faee0ea43cf437ab47a4deb2db4b571f95b1e9b561c6.jpg)

### Tables

![5a3694f407cf1aa2829673956f493b653dc867f412658d5ed8a5428378b934ef.jpg](../nips_results/1830_Mitigating%20Reward%20Over-optimization%20in%20Direct%20Alignment%20Algorithms%20with%20Importance%20Sampling/tables/5a3694f407cf1aa2829673956f493b653dc867f412658d5ed8a5428378b934ef.jpg)

![7cc93a383ba241c9afb3a87bedfb725095c56e7584f803240289407a901b5878.jpg](../nips_results/1830_Mitigating%20Reward%20Over-optimization%20in%20Direct%20Alignment%20Algorithms%20with%20Importance%20Sampling/tables/7cc93a383ba241c9afb3a87bedfb725095c56e7584f803240289407a901b5878.jpg)

![f543541dcc5cc6a3e2e93370e2b88670da0b6722af85c48fa0c9eb383afaa15d.jpg](../nips_results/1830_Mitigating%20Reward%20Over-optimization%20in%20Direct%20Alignment%20Algorithms%20with%20Importance%20Sampling/tables/f543541dcc5cc6a3e2e93370e2b88670da0b6722af85c48fa0c9eb383afaa15d.jpg)

## VTON-VLLM: Aligning Virtual Try-On Models with Human Preferences


### Images

![059a6d43cf77f45d484527d5acd89130206bb37a7e3b3c7e2475cb4b18ef4ee7.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/images/059a6d43cf77f45d484527d5acd89130206bb37a7e3b3c7e2475cb4b18ef4ee7.jpg)

![1a2c5846857fddcefc256bf32835e4457e0b6ae93de800cb828eb510faa6a640.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/images/1a2c5846857fddcefc256bf32835e4457e0b6ae93de800cb828eb510faa6a640.jpg)

![1e3e2c9bcecb0cc7f778591f4caf7777890cf5ffc67e4bbebe809d12ae4d649c.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/images/1e3e2c9bcecb0cc7f778591f4caf7777890cf5ffc67e4bbebe809d12ae4d649c.jpg)

![a0b5c682c3fa855a0465e06da8d5f3383e80f1ec27a34513a54daa936d55013f.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/images/a0b5c682c3fa855a0465e06da8d5f3383e80f1ec27a34513a54daa936d55013f.jpg)

![aff10eb476a051bbde19fea8c6f168b098c824ebdb084c50dad061c1dee84af0.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/images/aff10eb476a051bbde19fea8c6f168b098c824ebdb084c50dad061c1dee84af0.jpg)

![c9cc9c53ca8fea1b784cef90c73f60e1a045b9db4be1c1df6f6ac67f7fb658f5.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/images/c9cc9c53ca8fea1b784cef90c73f60e1a045b9db4be1c1df6f6ac67f7fb658f5.jpg)

![cb7f6c0eacd5dd8be93ef536bce36da896805d42e7183d85b8471f697887fdcc.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/images/cb7f6c0eacd5dd8be93ef536bce36da896805d42e7183d85b8471f697887fdcc.jpg)

![cbe995193c0b4caec7c06273a5599c93425aa5fa5cc83a678a53ce26b5c8d1be.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/images/cbe995193c0b4caec7c06273a5599c93425aa5fa5cc83a678a53ce26b5c8d1be.jpg)

![d006bdc7cff48a6910c7bcaf7dce4f7fa6f20ea30bedde1ae51fcbbda4e4a1b7.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/images/d006bdc7cff48a6910c7bcaf7dce4f7fa6f20ea30bedde1ae51fcbbda4e4a1b7.jpg)

![db527cbdf5188d7b42323033d03c27e91b9e3a6878a5f73fd76a58882e3106af.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/images/db527cbdf5188d7b42323033d03c27e91b9e3a6878a5f73fd76a58882e3106af.jpg)

### Tables

![1c443ff1a4ab47fcc794741f6c40d2ca8b38631f804b800561e3a3b22cf315ef.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/tables/1c443ff1a4ab47fcc794741f6c40d2ca8b38631f804b800561e3a3b22cf315ef.jpg)

![1cb5e26c137212a819ae530075b90234a67bc621fc404ead6b84da552689a981.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/tables/1cb5e26c137212a819ae530075b90234a67bc621fc404ead6b84da552689a981.jpg)

![5647caadf3d859adb2bfb0076eef2c2d21fb862ad24bc05962360445802a57df.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/tables/5647caadf3d859adb2bfb0076eef2c2d21fb862ad24bc05962360445802a57df.jpg)

![56e53a32ca2cbd63bc576eb99a05811a50f574c3d390daec68d4f67db817cec3.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/tables/56e53a32ca2cbd63bc576eb99a05811a50f574c3d390daec68d4f67db817cec3.jpg)

![58343624eb042ebf7204d6ed4979dd37ca10e039262f69a71030d01856773859.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/tables/58343624eb042ebf7204d6ed4979dd37ca10e039262f69a71030d01856773859.jpg)

![723173f91ee9a591414f3cf9cc7c56569b0792ef0b8f360a228d87d00ef13763.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/tables/723173f91ee9a591414f3cf9cc7c56569b0792ef0b8f360a228d87d00ef13763.jpg)

![c29cf4f81efbe6423b79809655c3bb9ff2b418912b20f2c43e09587cff9b96b2.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/tables/c29cf4f81efbe6423b79809655c3bb9ff2b418912b20f2c43e09587cff9b96b2.jpg)

![e1f900f7632aab3b28c4ba25ddabe263ba2780e73e38d143572639cb27b5cc73.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/tables/e1f900f7632aab3b28c4ba25ddabe263ba2780e73e38d143572639cb27b5cc73.jpg)

![e3207fc8576b48c9609cf7db6aa5c9adc5c25d1b4d06f7aeb847d212fac63465.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/tables/e3207fc8576b48c9609cf7db6aa5c9adc5c25d1b4d06f7aeb847d212fac63465.jpg)

![ea7f8ebde924785cdc9ed5230030fed2153b7a1dddc0b80cedc84b99be559d84.jpg](../nips_results/1831_VTON-VLLM_%20Aligning%20Virtual%20Try-On%20Models%20with%20Human%20Preferences/tables/ea7f8ebde924785cdc9ed5230030fed2153b7a1dddc0b80cedc84b99be559d84.jpg)

## Prompt-guided Disentangled Representation for Action Recognition


### Images

![1277274233f661625ccf3d944acbb9359f34cc9324e9103a218a07ed47b5eb8d.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/images/1277274233f661625ccf3d944acbb9359f34cc9324e9103a218a07ed47b5eb8d.jpg)

![335d1190fe69ccd66dad5e1beb2aa1ed7905a7e09ec0d9c48056a27d38e4c3ce.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/images/335d1190fe69ccd66dad5e1beb2aa1ed7905a7e09ec0d9c48056a27d38e4c3ce.jpg)

![436b4979d75285261348d98e3eb3871aa402a9032ba47c4b8aaaa31d09a6c5e7.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/images/436b4979d75285261348d98e3eb3871aa402a9032ba47c4b8aaaa31d09a6c5e7.jpg)

![566295c9e2e1d8f72ef6ebf4e4a94c07984e858b34cfc2748014cc80210cc9de.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/images/566295c9e2e1d8f72ef6ebf4e4a94c07984e858b34cfc2748014cc80210cc9de.jpg)

![71bf4aee475e76f048350f8d03b6514ebb9d2b4dff063c8acfaa4523d4717491.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/images/71bf4aee475e76f048350f8d03b6514ebb9d2b4dff063c8acfaa4523d4717491.jpg)

![8f3f5f0263cc1dcb7afa8f62703b4f1976f65498d9420767155d8ed9fd9a467f.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/images/8f3f5f0263cc1dcb7afa8f62703b4f1976f65498d9420767155d8ed9fd9a467f.jpg)

![98d0c8b0c3cbcb72687e78a4cd2dbca0e2c1fdf8093716b604a027a9240b6fc4.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/images/98d0c8b0c3cbcb72687e78a4cd2dbca0e2c1fdf8093716b604a027a9240b6fc4.jpg)

![9da1d82884d8b339ef810d0ad7da8394d15ee3dcc991e77a88f48afbd3d9de49.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/images/9da1d82884d8b339ef810d0ad7da8394d15ee3dcc991e77a88f48afbd3d9de49.jpg)

![a33557854c7ed105254d8311c83adce0bb98bb45177940a770ff2a572e7d2669.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/images/a33557854c7ed105254d8311c83adce0bb98bb45177940a770ff2a572e7d2669.jpg)

![eb2fdad8bdaec76039af19a737248b0aa66ea58658b7f78bdddb3f7547b6fe54.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/images/eb2fdad8bdaec76039af19a737248b0aa66ea58658b7f78bdddb3f7547b6fe54.jpg)

### Tables

![28cd665d245225dbc8327e14af6626a302f3782b72bfa075b4705fd04d6d5505.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/28cd665d245225dbc8327e14af6626a302f3782b72bfa075b4705fd04d6d5505.jpg)

![2c3e2413745fb426f7dbf6ad3b386d273587b93f808e9c85ca8465fdb1e8e751.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/2c3e2413745fb426f7dbf6ad3b386d273587b93f808e9c85ca8465fdb1e8e751.jpg)

![3797de16b7194e9e5182ac2173193d688ea59a6bc9341be719d52305a3d5d7d7.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/3797de16b7194e9e5182ac2173193d688ea59a6bc9341be719d52305a3d5d7d7.jpg)

![526cd95cfa78643a97fa3aa2d96a94d88ece5b883b54e91abfba91d4c220f629.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/526cd95cfa78643a97fa3aa2d96a94d88ece5b883b54e91abfba91d4c220f629.jpg)

![5780dc0961ed32058033b314cd89b09379fe43e77eef5ea0e7acbdb39312a1c5.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/5780dc0961ed32058033b314cd89b09379fe43e77eef5ea0e7acbdb39312a1c5.jpg)

![5d37aaa2d9c7fde5f2950cfd8a58353fb1471a95a732f9177b9cf1304ad5cfd7.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/5d37aaa2d9c7fde5f2950cfd8a58353fb1471a95a732f9177b9cf1304ad5cfd7.jpg)

![681aa2353dd7a343a1237b858a2364ecf17632e179b0a58d952c4a763b20fbc7.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/681aa2353dd7a343a1237b858a2364ecf17632e179b0a58d952c4a763b20fbc7.jpg)

![6edeb3e8d2bedde8c3225e6c11d579fb0f2172f962294bad1a87ff1df96ba187.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/6edeb3e8d2bedde8c3225e6c11d579fb0f2172f962294bad1a87ff1df96ba187.jpg)

![965ad6a23abc4fc8ea11b7c01ab317cd2bd38ed34c47973e4090aa30eb4dd082.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/965ad6a23abc4fc8ea11b7c01ab317cd2bd38ed34c47973e4090aa30eb4dd082.jpg)

![a09023b253bad7af5d8a932f8e6d1eaf89f62f3ba6549b694d6d10c8828fbb2c.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/a09023b253bad7af5d8a932f8e6d1eaf89f62f3ba6549b694d6d10c8828fbb2c.jpg)

![ce9946dbd9933fdcee0ea728334dae4a3414e9a6e0bc5fd40b41d385ab654c73.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/ce9946dbd9933fdcee0ea728334dae4a3414e9a6e0bc5fd40b41d385ab654c73.jpg)

![e86e9a3ba2e07867bd7bda0d0585d29f3e00f5d18b4869076267cef6b8213f4e.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/e86e9a3ba2e07867bd7bda0d0585d29f3e00f5d18b4869076267cef6b8213f4e.jpg)

![fdc218c67d7421fe06922c985ff899d29411fad228ebe5cf5ab2bb47643fd518.jpg](../nips_results/1832_Prompt-guided%20Disentangled%20Representation%20for%20Action%20Recognition/tables/fdc218c67d7421fe06922c985ff899d29411fad228ebe5cf5ab2bb47643fd518.jpg)

## On the creation of narrow AI: hierarchy and nonlocality of neural network skills


### Images

![0fc1ffdd226f6a314a9d36ac958b4732e0f1c9bb89dba8e20267893939bbdeaa.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/0fc1ffdd226f6a314a9d36ac958b4732e0f1c9bb89dba8e20267893939bbdeaa.jpg)

![40b6ca818a7d254eb6dd770dd5d350b719e7804574639550a1d91e51b6887d08.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/40b6ca818a7d254eb6dd770dd5d350b719e7804574639550a1d91e51b6887d08.jpg)

![623e4bd5d3ca4eebe1a523e47c01415a07fef6270744516384ade737f9b1eab3.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/623e4bd5d3ca4eebe1a523e47c01415a07fef6270744516384ade737f9b1eab3.jpg)

![64ddc59ae164b89c2a06f10393e949a674af0e256d985a4a6cf429489162627f.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/64ddc59ae164b89c2a06f10393e949a674af0e256d985a4a6cf429489162627f.jpg)

![6ae951d4989b441638702a7c723faf1d66d83b09fdf40ac651db5a3c0e8d03b8.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/6ae951d4989b441638702a7c723faf1d66d83b09fdf40ac651db5a3c0e8d03b8.jpg)

![71c0b2d73daff1bd50152ec05b4f6033f593505c6cdafafd4ba38cb9c25f8b90.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/71c0b2d73daff1bd50152ec05b4f6033f593505c6cdafafd4ba38cb9c25f8b90.jpg)

![7aa903fd0c37765697d95342a97f9c1d8995d995251c3df85ea487ddb9d0ed4c.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/7aa903fd0c37765697d95342a97f9c1d8995d995251c3df85ea487ddb9d0ed4c.jpg)

![915f78fabea70617e57da672765e344f0c4d76072a7116e84f8857f5cddf305c.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/915f78fabea70617e57da672765e344f0c4d76072a7116e84f8857f5cddf305c.jpg)

![9e9035adcc2307415fcf85d36cdf2a03e2993a6d3f6d624dc90259632972bcdb.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/9e9035adcc2307415fcf85d36cdf2a03e2993a6d3f6d624dc90259632972bcdb.jpg)

![acd5bc43b42461750a151ca09c21f06a226b468bf108e99cb66afd32dfb24c62.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/acd5bc43b42461750a151ca09c21f06a226b468bf108e99cb66afd32dfb24c62.jpg)

![b2660db44be00a763aa08be3be4532a1f57fb6946150251c68733f38cfef3e0c.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/b2660db44be00a763aa08be3be4532a1f57fb6946150251c68733f38cfef3e0c.jpg)

![e654eaf2268d9f1cccf10233b98bb90dcd3dced7fd88b339cf10102927f72402.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/e654eaf2268d9f1cccf10233b98bb90dcd3dced7fd88b339cf10102927f72402.jpg)

![e7f1f1b9271e9f74e4afe42ff3f4127f84fb5a74c437b5fb351eb104b668a951.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/e7f1f1b9271e9f74e4afe42ff3f4127f84fb5a74c437b5fb351eb104b668a951.jpg)

![fe55c15db002731cf70c1757ef9e465d8a3cd2bf7cbf9466d7575cfc1180285f.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/images/fe55c15db002731cf70c1757ef9e465d8a3cd2bf7cbf9466d7575cfc1180285f.jpg)

### Tables

![341671a9fc7533075aac9206cbcee21f482833d374422511a6a07677c75c92f3.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/tables/341671a9fc7533075aac9206cbcee21f482833d374422511a6a07677c75c92f3.jpg)

![3eae93f46e37a1eefe3cd837939585953b8f30a53791957568938f80716ef7d4.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/tables/3eae93f46e37a1eefe3cd837939585953b8f30a53791957568938f80716ef7d4.jpg)

![ab06647d64c1a322ba98e384b28656e5422e0f1e4a0206ef094bbf1ca125fba7.jpg](../nips_results/1833_On%20the%20creation%20of%20narrow%20AI_%20hierarchy%20and%20nonlocality%20of%20neural%20network%20skills/tables/ab06647d64c1a322ba98e384b28656e5422e0f1e4a0206ef094bbf1ca125fba7.jpg)

## Direct Alignment with Heterogeneous Preferences


### Images

![3916cd5244be031e16477cb546097070e6bff7938226cb855d555b5d0e24d18e.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/images/3916cd5244be031e16477cb546097070e6bff7938226cb855d555b5d0e24d18e.jpg)

![5a87c56f0da825a428458d3c6f7e666d4a8e69d2941e88731240e70f63573eeb.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/images/5a87c56f0da825a428458d3c6f7e666d4a8e69d2941e88731240e70f63573eeb.jpg)

![6b873fd6fe7e20e1830de0d8a1eb4c4328ab7310b819e0a1706f371fc32167b6.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/images/6b873fd6fe7e20e1830de0d8a1eb4c4328ab7310b819e0a1706f371fc32167b6.jpg)

![6f339db72fa229f5dcf3bae46285b2810cef4fc20f128a0e6c0a3ade3fdb0283.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/images/6f339db72fa229f5dcf3bae46285b2810cef4fc20f128a0e6c0a3ade3fdb0283.jpg)

![b7a29e82db6f95dd31f42c18166367ad05ebc8872b75f8bd81d4baf32b3e1bfc.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/images/b7a29e82db6f95dd31f42c18166367ad05ebc8872b75f8bd81d4baf32b3e1bfc.jpg)

![b84ba05ce4d94572ac2b43d26549cf0277b22ea6b6d47243b3f58467c194e3cd.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/images/b84ba05ce4d94572ac2b43d26549cf0277b22ea6b6d47243b3f58467c194e3cd.jpg)

![bfa9c15f60c012153a095f29da7c410d1ffc9c44dd0aba1f8e09a8ca358757f7.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/images/bfa9c15f60c012153a095f29da7c410d1ffc9c44dd0aba1f8e09a8ca358757f7.jpg)

![c34999dffdb5f7bfb54038cf549aa6608195f202c460c46d046f1163cf6bbe4e.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/images/c34999dffdb5f7bfb54038cf549aa6608195f202c460c46d046f1163cf6bbe4e.jpg)

![d7a64f9c8a9a074c9d9a61ecfb3d03b88254394d793aad4d75cbd6f4758ccff3.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/images/d7a64f9c8a9a074c9d9a61ecfb3d03b88254394d793aad4d75cbd6f4758ccff3.jpg)

![e47e5c04f0e63cd94eed879ed377897e3fd8d883ad9b14ad41766e249a0e3a78.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/images/e47e5c04f0e63cd94eed879ed377897e3fd8d883ad9b14ad41766e249a0e3a78.jpg)

### Tables

![3dc9bb7f1ea7b430b3ab2d6c4bb0a2169b8d1d8ce1dbc8b34cf09aacf2fa6b62.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/tables/3dc9bb7f1ea7b430b3ab2d6c4bb0a2169b8d1d8ce1dbc8b34cf09aacf2fa6b62.jpg)

![55fc649a7d6c881e1389a509ee75d979bd3b91420c6ab370d24279639fed6181.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/tables/55fc649a7d6c881e1389a509ee75d979bd3b91420c6ab370d24279639fed6181.jpg)

![6200fe8f65692b731fe58458b77e7af15cb1899df1fbca91e166dbafeaee0335.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/tables/6200fe8f65692b731fe58458b77e7af15cb1899df1fbca91e166dbafeaee0335.jpg)

![6274558dce85b5f5c420b8c5ab67ec1fa86785c464fe65a00a03913f14ef29b2.jpg](../nips_results/1834_Direct%20Alignment%20with%20Heterogeneous%20Preferences/tables/6274558dce85b5f5c420b8c5ab67ec1fa86785c464fe65a00a03913f14ef29b2.jpg)

## Routing Mamba: Scaling State Space Models with Mixture-of-Experts Projection


### Images

![006a2da00426898c1d16d2be5b97b2f7ea3f268806770e2326d4ca87a786e2a3.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/images/006a2da00426898c1d16d2be5b97b2f7ea3f268806770e2326d4ca87a786e2a3.jpg)

![5197f4365a6aa817a290c2f1d6b663415d8bdd1faad2d3196fde527ecb95dbe5.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/images/5197f4365a6aa817a290c2f1d6b663415d8bdd1faad2d3196fde527ecb95dbe5.jpg)

![a31290360becf25a8e6254aae87412cfc08d9ebe3dfe1bcb56cac0877898eaac.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/images/a31290360becf25a8e6254aae87412cfc08d9ebe3dfe1bcb56cac0877898eaac.jpg)

![b610da9506eb65df706dbaeda565fabfed8373a15eb3573838f9e8d8722c6649.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/images/b610da9506eb65df706dbaeda565fabfed8373a15eb3573838f9e8d8722c6649.jpg)

![fd1e5413d97b74817ce0fa5eac41692f262d0e7745d9d30da4b2e15b6a48c210.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/images/fd1e5413d97b74817ce0fa5eac41692f262d0e7745d9d30da4b2e15b6a48c210.jpg)

### Tables

![2ffae562cc2779556d9ff3d755b00da0cbd948fd1ff6f8dc0598ebf6b0893856.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/tables/2ffae562cc2779556d9ff3d755b00da0cbd948fd1ff6f8dc0598ebf6b0893856.jpg)

![37175b2f5bb1bab063cd7bb1f1c0004f526aaaf42f517c4920ced1ca20fe0b39.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/tables/37175b2f5bb1bab063cd7bb1f1c0004f526aaaf42f517c4920ced1ca20fe0b39.jpg)

![44cc6ef4e572aac4742549a2f3b633e1c1dd2ffaa15d07d0fc810e6e4f7422c8.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/tables/44cc6ef4e572aac4742549a2f3b633e1c1dd2ffaa15d07d0fc810e6e4f7422c8.jpg)

![6ec785df3ff8eedff5a3c7acadc0c2d09223226e6b0ea3ddd2aeaeb0a1cac5a3.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/tables/6ec785df3ff8eedff5a3c7acadc0c2d09223226e6b0ea3ddd2aeaeb0a1cac5a3.jpg)

![746e85c7c44d89fbc4639f69a5afa4cc5238e02f36d196767fc50cc1824b5582.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/tables/746e85c7c44d89fbc4639f69a5afa4cc5238e02f36d196767fc50cc1824b5582.jpg)

![ab72d14f9403dd99d019ad48e03022ad3eb74927f197314aee23b2770f6e7a4c.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/tables/ab72d14f9403dd99d019ad48e03022ad3eb74927f197314aee23b2770f6e7a4c.jpg)

![cb072ec247af6a728dbb4186a659cffc843373f7b1a7357655928ca4740ce3f3.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/tables/cb072ec247af6a728dbb4186a659cffc843373f7b1a7357655928ca4740ce3f3.jpg)

![d6e2a8ebd4bcfe41829be988444321d7b82ea5638c70e431dba83e99bbfe35a1.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/tables/d6e2a8ebd4bcfe41829be988444321d7b82ea5638c70e431dba83e99bbfe35a1.jpg)

![e58fe2684451b682c51c032368eb784dcdee7d29dee1cc411332c658064b1c94.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/tables/e58fe2684451b682c51c032368eb784dcdee7d29dee1cc411332c658064b1c94.jpg)

![fa8c3f240ed5879a34afc646601ff681f39fc0fa6ea7043938f478759dd33ecc.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/tables/fa8c3f240ed5879a34afc646601ff681f39fc0fa6ea7043938f478759dd33ecc.jpg)

![fe0a645a09e8477f5d6e6c2907f06e9349809f35feda071b8ec72ff322c238af.jpg](../nips_results/1835_Routing%20Mamba_%20Scaling%20State%20Space%20Models%20with%20Mixture-of-Experts%20Projection/tables/fe0a645a09e8477f5d6e6c2907f06e9349809f35feda071b8ec72ff322c238af.jpg)

## Train with Perturbation, Infer after Merging: A Two-Stage Framework for Continual Learning


### Images

![396a73211e771f5178150c1de4be11710172d4fe52a21b1e1844f1853cdc71a2.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/images/396a73211e771f5178150c1de4be11710172d4fe52a21b1e1844f1853cdc71a2.jpg)

![4c71fad4a451143b0318a61fd1a6c5fab0ec6d620145dbe03e12fade7f718069.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/images/4c71fad4a451143b0318a61fd1a6c5fab0ec6d620145dbe03e12fade7f718069.jpg)

![8a194e8fa88a83c10e6bb06b51b6888b11bdf2f5d52be343a77a966bcae55f32.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/images/8a194e8fa88a83c10e6bb06b51b6888b11bdf2f5d52be343a77a966bcae55f32.jpg)

### Tables

![253141e6e602d9a48156ba16a12c324226a72e98f0c313c846bdcbe8e72171ab.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/253141e6e602d9a48156ba16a12c324226a72e98f0c313c846bdcbe8e72171ab.jpg)

![2d2447d621812bcda14fca556954bd0c3ef04e8213a7fa2974bfbe5e51d52e5d.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/2d2447d621812bcda14fca556954bd0c3ef04e8213a7fa2974bfbe5e51d52e5d.jpg)

![43849ea7397e08306e9c58b9d57749931be9d2dfcfe6073a06b22956ddd3f399.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/43849ea7397e08306e9c58b9d57749931be9d2dfcfe6073a06b22956ddd3f399.jpg)

![574878a00012cb077ac1ad60edd9a9085ae277d784da27cab6a30052064d4f03.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/574878a00012cb077ac1ad60edd9a9085ae277d784da27cab6a30052064d4f03.jpg)

![5d2cc3d6e991ce78f76a587d7c8bd1c33a9672af4178265f4f778cb0f6d7c512.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/5d2cc3d6e991ce78f76a587d7c8bd1c33a9672af4178265f4f778cb0f6d7c512.jpg)

![62ca8a35a90be6e9cd765b959cc04a6461ae6f85ee1299a6ac0cd4b982209b67.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/62ca8a35a90be6e9cd765b959cc04a6461ae6f85ee1299a6ac0cd4b982209b67.jpg)

![64a6fb36413240192968c9bc996b1b3bdc63c51957aacaaea612d96f4954c9bd.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/64a6fb36413240192968c9bc996b1b3bdc63c51957aacaaea612d96f4954c9bd.jpg)

![6bf94377392bd2c9b0ce78af95a01fba9a28de848489bc8739fdf139f3d2f2ec.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/6bf94377392bd2c9b0ce78af95a01fba9a28de848489bc8739fdf139f3d2f2ec.jpg)

![aa9694936d8b9f057c65e03c084e667d61bd54be8cc0c688b77032ef9c4e7ec1.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/aa9694936d8b9f057c65e03c084e667d61bd54be8cc0c688b77032ef9c4e7ec1.jpg)

![af475eebaa4d535a5b8fd8f6918d60c396ea198f4523afddfc1c882e6e4c032d.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/af475eebaa4d535a5b8fd8f6918d60c396ea198f4523afddfc1c882e6e4c032d.jpg)

![f63e73b11c5c50dee639e690f76cbb8589f9cd020fc4fb9fcf85ca59e1bd95ab.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/f63e73b11c5c50dee639e690f76cbb8589f9cd020fc4fb9fcf85ca59e1bd95ab.jpg)

![fa8cdf408ffc01bf98fa9ca7ac8b821f629dfddfe0857752be2d81885233be13.jpg](../nips_results/1836_Train%20with%20Perturbation%2C%20Infer%20after%20Merging_%20A%20Two-Stage%20Framework%20for%20Continual%20Learning/tables/fa8cdf408ffc01bf98fa9ca7ac8b821f629dfddfe0857752be2d81885233be13.jpg)

## FACE: A General Framework for Mapping Collaborative Filtering Embeddings into LLM Tokens


### Images

![1bdbd5d2d912107ce0832d35f9d732e860b07183debdcf5c41674bd71c204f4c.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/images/1bdbd5d2d912107ce0832d35f9d732e860b07183debdcf5c41674bd71c204f4c.jpg)

![24cd05a833c43fe3ad3111494d0a023b3ec3884f28f2de2820992b48347d5b53.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/images/24cd05a833c43fe3ad3111494d0a023b3ec3884f28f2de2820992b48347d5b53.jpg)

![374ea499ef13456991635cf6914e7d2d6572c2a75087a2573893dd800ecce4cd.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/images/374ea499ef13456991635cf6914e7d2d6572c2a75087a2573893dd800ecce4cd.jpg)

![5010ca4b8451cf14d9eaa4f9f60bf2e9eca4965d7736ebd8f0bd4947423d6bf8.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/images/5010ca4b8451cf14d9eaa4f9f60bf2e9eca4965d7736ebd8f0bd4947423d6bf8.jpg)

![c8f758cd14f58923d210076551a26882343b7ed99f140b7f5a5d9bf3f8293033.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/images/c8f758cd14f58923d210076551a26882343b7ed99f140b7f5a5d9bf3f8293033.jpg)

![e4f7943d039d1bf8ad928a7fa221b4100e5b776ceb72556ad90bbb3d7c07874f.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/images/e4f7943d039d1bf8ad928a7fa221b4100e5b776ceb72556ad90bbb3d7c07874f.jpg)

### Tables

![27b0686b156c586379f16205beced142374df9a84378ff6570b43de25d9183e0.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/tables/27b0686b156c586379f16205beced142374df9a84378ff6570b43de25d9183e0.jpg)

![3799dda573a21055396a204be9800f2786c65d18184ecbf2c46e90755c80db67.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/tables/3799dda573a21055396a204be9800f2786c65d18184ecbf2c46e90755c80db67.jpg)

![7b422f4721b57f8a97dba6c9c3bfb336d7f5779bcb51d7c5269e7b57b031fe01.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/tables/7b422f4721b57f8a97dba6c9c3bfb336d7f5779bcb51d7c5269e7b57b031fe01.jpg)

![81055beab52c2e91a11df3d8f0cbe0b9e4cd95c4cf13672c3ba2188d28721775.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/tables/81055beab52c2e91a11df3d8f0cbe0b9e4cd95c4cf13672c3ba2188d28721775.jpg)

![822ed875abb68e5f6a0201697302b3d092a36daacee0d243cbf568a71929c28d.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/tables/822ed875abb68e5f6a0201697302b3d092a36daacee0d243cbf568a71929c28d.jpg)

![88fa1e769f8dc807ddec2b723b50d38a6a31e279da55c2ab8af2daeba936ca6e.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/tables/88fa1e769f8dc807ddec2b723b50d38a6a31e279da55c2ab8af2daeba936ca6e.jpg)

![c8c0e121331bc77f0bfa610cfb4b63e02b18daac7d2c1867f4a0a36bddac57b3.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/tables/c8c0e121331bc77f0bfa610cfb4b63e02b18daac7d2c1867f4a0a36bddac57b3.jpg)

![ced626a27c8247cfaf426744926ddc04aa460d8cc7947c39671b3a10c24b84e4.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/tables/ced626a27c8247cfaf426744926ddc04aa460d8cc7947c39671b3a10c24b84e4.jpg)

![e834d788b8dc8c0706fe5ac264c984004e6bfed60ed3ba389b35e0734d0f08ef.jpg](../nips_results/1837_FACE_%20A%20General%20Framework%20for%20Mapping%20Collaborative%20Filtering%20Embeddings%20into%20LLM%20Tokens/tables/e834d788b8dc8c0706fe5ac264c984004e6bfed60ed3ba389b35e0734d0f08ef.jpg)

## Towards a General Attention Framework on Gyrovector Spaces for Matrix Manifolds


### Images

![131d294cbb9584b8527f93db5787963ccb0ba2dfc260f2e44f9758507d9e1b99.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/images/131d294cbb9584b8527f93db5787963ccb0ba2dfc260f2e44f9758507d9e1b99.jpg)

![464c182a2be9342fb8a459635dc4d0539c4b45067b41a46753bd7654b901b1b9.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/images/464c182a2be9342fb8a459635dc4d0539c4b45067b41a46753bd7654b901b1b9.jpg)

![5ac3bc39f23a6f47df35a0bccc6169f7eef00bcf27d4b08829798e58108be94e.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/images/5ac3bc39f23a6f47df35a0bccc6169f7eef00bcf27d4b08829798e58108be94e.jpg)

![a499ff448aaa59e5c50a15bdd9da181687383408cd9559bb38164bba40b25fcb.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/images/a499ff448aaa59e5c50a15bdd9da181687383408cd9559bb38164bba40b25fcb.jpg)

![ca9f1ce057569d5833e470dfc6cb25f9547bb242320729bd7ce779718ebc88d3.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/images/ca9f1ce057569d5833e470dfc6cb25f9547bb242320729bd7ce779718ebc88d3.jpg)

### Tables

![13297afbf4caf707d0949f634a7dc7889aec071a576bde51bc1ba6ef7f7a4c08.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/13297afbf4caf707d0949f634a7dc7889aec071a576bde51bc1ba6ef7f7a4c08.jpg)

![1b015d5318c7d7257f740125609d8620989b218343dd0830860377cfae631785.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/1b015d5318c7d7257f740125609d8620989b218343dd0830860377cfae631785.jpg)

![1cfb3bd0a28c4134f37a8ea9c485109fcbf6ab8d8ca091b7a0f0f5e126c7ed40.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/1cfb3bd0a28c4134f37a8ea9c485109fcbf6ab8d8ca091b7a0f0f5e126c7ed40.jpg)

![2251bcfc882eb485c8d93748945c154565d138fd295ad97cadbb235330f66c75.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/2251bcfc882eb485c8d93748945c154565d138fd295ad97cadbb235330f66c75.jpg)

![24517cd0c2386391a376693c0ffa8c9a5865078603804db91629ddee7398eeb3.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/24517cd0c2386391a376693c0ffa8c9a5865078603804db91629ddee7398eeb3.jpg)

![288e9d7e940f51d096f60d4c147bd7086b4b4da53c4fdce14df666bde86b4527.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/288e9d7e940f51d096f60d4c147bd7086b4b4da53c4fdce14df666bde86b4527.jpg)

![3efce67c949fa14bcfd1b13e46d1f8380f952cbc32b8a6ae04407dd892251232.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/3efce67c949fa14bcfd1b13e46d1f8380f952cbc32b8a6ae04407dd892251232.jpg)

![52fa82cb88482d4d19700d195c6c6813f4c5b83641454fbb887897e591f1ea70.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/52fa82cb88482d4d19700d195c6c6813f4c5b83641454fbb887897e591f1ea70.jpg)

![5307d888e75ad031bfb4bdd881652a0cc35e0efb9d9872aaef4a9f50b40eba89.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/5307d888e75ad031bfb4bdd881652a0cc35e0efb9d9872aaef4a9f50b40eba89.jpg)

![5b542a1201a2d8eff1f916553b8b0217359a5c07c5a4000f547a9c0d094359c9.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/5b542a1201a2d8eff1f916553b8b0217359a5c07c5a4000f547a9c0d094359c9.jpg)

![6404d5bce01eaca36f9c8f6f04e103f2786a0d7da22d67d8df3219fcb3dc4b95.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/6404d5bce01eaca36f9c8f6f04e103f2786a0d7da22d67d8df3219fcb3dc4b95.jpg)

![844b0e48b6e807b2a81488f8dbfdb95d6dbfec4b1ff1429cf44b189ccef3276a.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/844b0e48b6e807b2a81488f8dbfdb95d6dbfec4b1ff1429cf44b189ccef3276a.jpg)

![8d8aa2d068470206d3380dd28711dc0e115ec1a0eef818ea6a7286fabbfe63e9.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/8d8aa2d068470206d3380dd28711dc0e115ec1a0eef818ea6a7286fabbfe63e9.jpg)

![906c7920c4bf94d43f58ecfa9b565b6ab1241b9e7508ddc0ddb6ec8473db00bb.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/906c7920c4bf94d43f58ecfa9b565b6ab1241b9e7508ddc0ddb6ec8473db00bb.jpg)

![9a7e5e1aa005280cf7da5a86b07932b7499bfad77e9ec448de667a5f2929ed40.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/9a7e5e1aa005280cf7da5a86b07932b7499bfad77e9ec448de667a5f2929ed40.jpg)

![9b64f74b0a8c45a91cb41dde49753baa829026af3210e6ee45f15947f87b8be6.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/9b64f74b0a8c45a91cb41dde49753baa829026af3210e6ee45f15947f87b8be6.jpg)

![a73a0fbb428d08ef964257a1333a5e577beb51e3f85c986fa6b9a0319f817386.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/a73a0fbb428d08ef964257a1333a5e577beb51e3f85c986fa6b9a0319f817386.jpg)

![b582f8a3e730f1d6b9f49ede1c33722c9522d99a363deb6a70fc46d8f3d20b8a.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/b582f8a3e730f1d6b9f49ede1c33722c9522d99a363deb6a70fc46d8f3d20b8a.jpg)

![b8b6d666aa4a5349d27a04d10b98780724b9f9d7dfb3e5a03b0f83fe8f0c4deb.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/b8b6d666aa4a5349d27a04d10b98780724b9f9d7dfb3e5a03b0f83fe8f0c4deb.jpg)

![c32e8c5ab277e355fe7a1fcb4fbfe824bb0ebf0ee08a4aef0678e995ae2050bc.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/c32e8c5ab277e355fe7a1fcb4fbfe824bb0ebf0ee08a4aef0678e995ae2050bc.jpg)

![c4bd1e9605bcefd3f6cdd283c2da82799787e89c05c396a35dce8d40f070ced1.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/c4bd1e9605bcefd3f6cdd283c2da82799787e89c05c396a35dce8d40f070ced1.jpg)

![e407ed36457651e449836c4b28611187613e9e20c07d15eda3b587734e43f0c9.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/e407ed36457651e449836c4b28611187613e9e20c07d15eda3b587734e43f0c9.jpg)

![f64025a55efd85e2f13b44236fb209dc27cfdb2bf2a5f5d89fab973d663e8153.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/f64025a55efd85e2f13b44236fb209dc27cfdb2bf2a5f5d89fab973d663e8153.jpg)

![fb9aada2aadee21375e468b7f03ff8814ee0630ce81117972f2c2412120db74a.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/fb9aada2aadee21375e468b7f03ff8814ee0630ce81117972f2c2412120db74a.jpg)

![fe386bc5b5b223f811787cfad38428458c1b2ba67a0c477e6be1dee5e7906fc7.jpg](../nips_results/1838_Towards%20a%20General%20Attention%20Framework%20on%20Gyrovector%20Spaces%20for%20Matrix%20Manifolds/tables/fe386bc5b5b223f811787cfad38428458c1b2ba67a0c477e6be1dee5e7906fc7.jpg)

## Adaptive Riemannian ADMM for Nonsmooth Optimization: Optimal Complexity without Smoothing


### Images

![03e7c0c47ab7421b6d53853ba1c4fd5cc1a81281e54083eba2414a9d4bfcb6ad.jpg](../nips_results/1839_Adaptive%20Riemannian%20ADMM%20for%20Nonsmooth%20Optimization_%20Optimal%20Complexity%20without%20Smoothing/images/03e7c0c47ab7421b6d53853ba1c4fd5cc1a81281e54083eba2414a9d4bfcb6ad.jpg)

![b670660826cafa54b5bb974598e750d12c06e6fb8eaca40910188f4d132fd059.jpg](../nips_results/1839_Adaptive%20Riemannian%20ADMM%20for%20Nonsmooth%20Optimization_%20Optimal%20Complexity%20without%20Smoothing/images/b670660826cafa54b5bb974598e750d12c06e6fb8eaca40910188f4d132fd059.jpg)

![b7c5c844618e840d25e3c00a63e9a3123a497b096d25320bb507d94c271d7d5b.jpg](../nips_results/1839_Adaptive%20Riemannian%20ADMM%20for%20Nonsmooth%20Optimization_%20Optimal%20Complexity%20without%20Smoothing/images/b7c5c844618e840d25e3c00a63e9a3123a497b096d25320bb507d94c271d7d5b.jpg)

### Tables

![0515c3293b05033c04ba10966e2d3513e90e6b4c60031acb8ff091933aafd28e.jpg](../nips_results/1839_Adaptive%20Riemannian%20ADMM%20for%20Nonsmooth%20Optimization_%20Optimal%20Complexity%20without%20Smoothing/tables/0515c3293b05033c04ba10966e2d3513e90e6b4c60031acb8ff091933aafd28e.jpg)

![196af99db14ccdaecb3313e5fec73c1b3f623433940ebe7ed7ade5250775f6d6.jpg](../nips_results/1839_Adaptive%20Riemannian%20ADMM%20for%20Nonsmooth%20Optimization_%20Optimal%20Complexity%20without%20Smoothing/tables/196af99db14ccdaecb3313e5fec73c1b3f623433940ebe7ed7ade5250775f6d6.jpg)

![3f2b3d9cb2bc0c9e714e6b6f15318292851c4189562806e4c1bcb834cdb24d2e.jpg](../nips_results/1839_Adaptive%20Riemannian%20ADMM%20for%20Nonsmooth%20Optimization_%20Optimal%20Complexity%20without%20Smoothing/tables/3f2b3d9cb2bc0c9e714e6b6f15318292851c4189562806e4c1bcb834cdb24d2e.jpg)

![6032a3aecb976744863c44421b0f9bf7f8d5df9c3f178060f79c10c5ac8501e5.jpg](../nips_results/1839_Adaptive%20Riemannian%20ADMM%20for%20Nonsmooth%20Optimization_%20Optimal%20Complexity%20without%20Smoothing/tables/6032a3aecb976744863c44421b0f9bf7f8d5df9c3f178060f79c10c5ac8501e5.jpg)

![e8ea5a4c0b928d382dacdcda6fee6ca272faa998373e958a864937ea2609c3cf.jpg](../nips_results/1839_Adaptive%20Riemannian%20ADMM%20for%20Nonsmooth%20Optimization_%20Optimal%20Complexity%20without%20Smoothing/tables/e8ea5a4c0b928d382dacdcda6fee6ca272faa998373e958a864937ea2609c3cf.jpg)

![eb40f1fc4475f5ce26cefef04d8176974114819fc5b13875e66c313c32171c20.jpg](../nips_results/1839_Adaptive%20Riemannian%20ADMM%20for%20Nonsmooth%20Optimization_%20Optimal%20Complexity%20without%20Smoothing/tables/eb40f1fc4475f5ce26cefef04d8176974114819fc5b13875e66c313c32171c20.jpg)

![fd9927e95193ec9019e56b51a447094cab4da4700b3526ed7ab990c6a8304976.jpg](../nips_results/1839_Adaptive%20Riemannian%20ADMM%20for%20Nonsmooth%20Optimization_%20Optimal%20Complexity%20without%20Smoothing/tables/fd9927e95193ec9019e56b51a447094cab4da4700b3526ed7ab990c6a8304976.jpg)

## Graphs Help Graphs: Multi-Agent Graph Socialized Learning


### Images

![03a436ec25569d676ef135cb87bf8c923691a7cb5fd752903f2aba64ec0e750c.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/images/03a436ec25569d676ef135cb87bf8c923691a7cb5fd752903f2aba64ec0e750c.jpg)

![0bd0809daa93819f9274bb5354f978d8fc4bd7eee1f9153e124e7183a2b14d9b.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/images/0bd0809daa93819f9274bb5354f978d8fc4bd7eee1f9153e124e7183a2b14d9b.jpg)

![207fb5b1ae51d62c62c4b1f714bf1a38cde4d0eb04db76f9212af9e06b6e2e74.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/images/207fb5b1ae51d62c62c4b1f714bf1a38cde4d0eb04db76f9212af9e06b6e2e74.jpg)

![471cee5f2d267a1a23f39d78abbc6e8110f88d2f04b844df95f9449b8d3504a5.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/images/471cee5f2d267a1a23f39d78abbc6e8110f88d2f04b844df95f9449b8d3504a5.jpg)

![6c41c633dbca67d2ba2cadcf5e964e5efca01938d03d00f0cc823267bced5488.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/images/6c41c633dbca67d2ba2cadcf5e964e5efca01938d03d00f0cc823267bced5488.jpg)

![6fd310891e7271bea7c6de0226d538b3bca112744cfb0c17e3f94a7d38c46e6c.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/images/6fd310891e7271bea7c6de0226d538b3bca112744cfb0c17e3f94a7d38c46e6c.jpg)

![a5df1784ae73dd2868bae1824df110659413328c680e66e04a596603f564d8f0.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/images/a5df1784ae73dd2868bae1824df110659413328c680e66e04a596603f564d8f0.jpg)

![b5cb4317b8f4b6e0064e321477676447f48bc171e4f394627a1a360ea9fce227.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/images/b5cb4317b8f4b6e0064e321477676447f48bc171e4f394627a1a360ea9fce227.jpg)

![dcb2b8326ce74d1a87747e6342a03e8cd1ab44e39938361a6ed4ed63e3e32db7.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/images/dcb2b8326ce74d1a87747e6342a03e8cd1ab44e39938361a6ed4ed63e3e32db7.jpg)

### Tables

![135678ea6a89e95152993ec9c7e40ffbd666a9a1e857b7e8857498d5c5cbad77.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/tables/135678ea6a89e95152993ec9c7e40ffbd666a9a1e857b7e8857498d5c5cbad77.jpg)

![1a7bfe2cb3eda58b6c4ad2e1dcd89d92f5f8e008ca8ae174a74e81d080d057dd.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/tables/1a7bfe2cb3eda58b6c4ad2e1dcd89d92f5f8e008ca8ae174a74e81d080d057dd.jpg)

![5278927625c5b5a1f74b20c359529d3fdfd01036e4e0296f5a34bf74daf0fe18.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/tables/5278927625c5b5a1f74b20c359529d3fdfd01036e4e0296f5a34bf74daf0fe18.jpg)

![8d9fc90ec2202970bcba8c8af99b62aab3ed8047d25138da7d8a21744657b303.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/tables/8d9fc90ec2202970bcba8c8af99b62aab3ed8047d25138da7d8a21744657b303.jpg)

![b9ef5e9f32bf88ada1ef53e1aece29831c7374b9adbde6078250ae20f2043921.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/tables/b9ef5e9f32bf88ada1ef53e1aece29831c7374b9adbde6078250ae20f2043921.jpg)

![bf4a02274be7993535cbd74ceb3c4752ae039efc60c1b55c2ca0628567ab809b.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/tables/bf4a02274be7993535cbd74ceb3c4752ae039efc60c1b55c2ca0628567ab809b.jpg)

![e0c566bac4cb3bda8ffb9e2264a09de54b64a8446b84c98500537e81898bde56.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/tables/e0c566bac4cb3bda8ffb9e2264a09de54b64a8446b84c98500537e81898bde56.jpg)

![f6037ee463cfc9322020d3ef028ee63bbc1e0b2f170e73feebaa052063a6a230.jpg](../nips_results/1840_Graphs%20Help%20Graphs_%20Multi-Agent%20Graph%20Socialized%20Learning/tables/f6037ee463cfc9322020d3ef028ee63bbc1e0b2f170e73feebaa052063a6a230.jpg)

## ConceptScope: Characterizing Dataset Bias via Disentangled Visual Concepts


### Images

![04f5b374e9307b0cf3bfa8b80d15bbd21c0f0103450f15ff495b32a8cb8b0f6c.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/04f5b374e9307b0cf3bfa8b80d15bbd21c0f0103450f15ff495b32a8cb8b0f6c.jpg)

![07e0e3363070a3ebcfaecbd9066c1ded5b918cc1c8dba5f22dba44a65d2e349e.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/07e0e3363070a3ebcfaecbd9066c1ded5b918cc1c8dba5f22dba44a65d2e349e.jpg)

![13b31310a36d6fe1d2da1be509dbb4392747073473cbfa15e4d1ac3503d97a2b.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/13b31310a36d6fe1d2da1be509dbb4392747073473cbfa15e4d1ac3503d97a2b.jpg)

![13d03e5d8f1b2b314e8701e1c291a2a40b7c79e18d6d37dd1f2b797822890c8c.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/13d03e5d8f1b2b314e8701e1c291a2a40b7c79e18d6d37dd1f2b797822890c8c.jpg)

![1b722c7ff5fbc0b159a764ff2123ceb39521605797fbd034987f7254578018f5.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/1b722c7ff5fbc0b159a764ff2123ceb39521605797fbd034987f7254578018f5.jpg)

![2650e32ec523f48b13f07ea954a91e110080bdef762809978c6203fd6c2a6fbc.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/2650e32ec523f48b13f07ea954a91e110080bdef762809978c6203fd6c2a6fbc.jpg)

![6fd1afb32e25f252046050c63c5d43988a1ba045421527d65f6221b33036adea.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/6fd1afb32e25f252046050c63c5d43988a1ba045421527d65f6221b33036adea.jpg)

![7313b73a12d9f812170c21896e4599b2206df96f2181654610aa5adaf95a3982.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/7313b73a12d9f812170c21896e4599b2206df96f2181654610aa5adaf95a3982.jpg)

![845b1049b21bd0ad5431f23584028f05738101ba74f308fe48ef3a0410e20e01.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/845b1049b21bd0ad5431f23584028f05738101ba74f308fe48ef3a0410e20e01.jpg)

![9f7dca961c29824c180fec86efb1c109b350f07d35d3d1e4e1d97925bf518670.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/9f7dca961c29824c180fec86efb1c109b350f07d35d3d1e4e1d97925bf518670.jpg)

![bc241d6353a36146c7b8797c247d43a9cb0c916f542afef0a125b4e1a21e2dc5.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/bc241d6353a36146c7b8797c247d43a9cb0c916f542afef0a125b4e1a21e2dc5.jpg)

![d9672364312a0c0e39b4e2b852560dd56bfd819fca69192e82b9a4663b922925.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/d9672364312a0c0e39b4e2b852560dd56bfd819fca69192e82b9a4663b922925.jpg)

![e168392f045a88170bfe0939b7d16f1420cfb571793542e00aa10a0c7fca469f.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/images/e168392f045a88170bfe0939b7d16f1420cfb571793542e00aa10a0c7fca469f.jpg)

### Tables

![15a8e0ff1cca58aabe6d42f53ae7297df4e9f3d2c6dab45d994ed14ca0744e57.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/tables/15a8e0ff1cca58aabe6d42f53ae7297df4e9f3d2c6dab45d994ed14ca0744e57.jpg)

![30d87408e026ea16e5b3e87f228048b3d04211ad039da53aa02b69ead15571a1.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/tables/30d87408e026ea16e5b3e87f228048b3d04211ad039da53aa02b69ead15571a1.jpg)

![3650a87a60a45516b1162d20323904fd23605325a086ed4f7595b014af0a11eb.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/tables/3650a87a60a45516b1162d20323904fd23605325a086ed4f7595b014af0a11eb.jpg)

![3e988cf5b3a8b1441507a84e6b21bb25bf4f539fdbf2c1dd2a1f38a5a602d353.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/tables/3e988cf5b3a8b1441507a84e6b21bb25bf4f539fdbf2c1dd2a1f38a5a602d353.jpg)

![679001910af3ef25dfa531fb871227fb8b8610ccb684c0f04df93141f7c7ad0f.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/tables/679001910af3ef25dfa531fb871227fb8b8610ccb684c0f04df93141f7c7ad0f.jpg)

![a27f5cca7bdbb34d0bb16e2f5d7b1c747f1de4b15e166ce52ed8251583f75881.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/tables/a27f5cca7bdbb34d0bb16e2f5d7b1c747f1de4b15e166ce52ed8251583f75881.jpg)

![c4c3cd9f8b2572ee62aca25bc4f9fa1e37e6e1394a0ac66cc5df9143f30bdee5.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/tables/c4c3cd9f8b2572ee62aca25bc4f9fa1e37e6e1394a0ac66cc5df9143f30bdee5.jpg)

![d1b5793a84ff537d98e06751c3814311f09826f73056bdd6307157391b120493.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/tables/d1b5793a84ff537d98e06751c3814311f09826f73056bdd6307157391b120493.jpg)

![e603b2144dc6ccd738592a5707be51dc3e95f165387b6fc0ec9b3a1a734ccccd.jpg](../nips_results/1841_ConceptScope_%20Characterizing%20Dataset%20Bias%20via%20Disentangled%20Visual%20Concepts/tables/e603b2144dc6ccd738592a5707be51dc3e95f165387b6fc0ec9b3a1a734ccccd.jpg)

## AutoPartGen: Autoregressive 3D Part Generation and Discovery


### Images

![0ca6f0878459c958c616ca7987103a30421f1255d53c4032b0c6c5ed0c531e13.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/0ca6f0878459c958c616ca7987103a30421f1255d53c4032b0c6c5ed0c531e13.jpg)

![0d1f4f91d5b1506db827c17e9f2b1143924a5b3f1c38fa558cb72486dc9487e9.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/0d1f4f91d5b1506db827c17e9f2b1143924a5b3f1c38fa558cb72486dc9487e9.jpg)

![3e7915cfe389a2d16ad9963f3dca01842321adbd38b6721f10ea5df3ce1aab4c.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/3e7915cfe389a2d16ad9963f3dca01842321adbd38b6721f10ea5df3ce1aab4c.jpg)

![5d41fa1bcb0d6c708fb705098df1ce8d69b492c0f23774fe2ee91b1f67333e23.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/5d41fa1bcb0d6c708fb705098df1ce8d69b492c0f23774fe2ee91b1f67333e23.jpg)

![a5578a9b340c88f4b3fbda8613222f30b4364df7f50ed63dddc374ecab5a5de8.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/a5578a9b340c88f4b3fbda8613222f30b4364df7f50ed63dddc374ecab5a5de8.jpg)

![b8ae22d4c2c84ebce9e52e4f7fbac83bb795deb52077fb4a2aa5a36785364697.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/b8ae22d4c2c84ebce9e52e4f7fbac83bb795deb52077fb4a2aa5a36785364697.jpg)

![c53ad134b95922570916202fd0ff7ac68017a5b7b180b32afb697456c4be54ff.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/c53ad134b95922570916202fd0ff7ac68017a5b7b180b32afb697456c4be54ff.jpg)

![ca00c1afe38d0e1fb4a9272f13dca6bf1a0ecb4b350b2a9cac580e86add8d8ca.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/ca00c1afe38d0e1fb4a9272f13dca6bf1a0ecb4b350b2a9cac580e86add8d8ca.jpg)

![d57a989fc31451c8de880b955f7f818331f59a5459b7db631b3fe22aed073338.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/d57a989fc31451c8de880b955f7f818331f59a5459b7db631b3fe22aed073338.jpg)

![d805e3bebe292647aaa4803c7734cc5be2a3d3c6a01b9a163cf12c870281a829.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/d805e3bebe292647aaa4803c7734cc5be2a3d3c6a01b9a163cf12c870281a829.jpg)

![db1d5aeba26f6a6569ecefef66a8cc5ab9cbd991d5b582ece2a680b841ba2c2b.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/db1d5aeba26f6a6569ecefef66a8cc5ab9cbd991d5b582ece2a680b841ba2c2b.jpg)

![ddfeacf11ed2ddb1e1bbd7d0f1693e8dcf7a777ca491609fb2c8de4cd45423de.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/images/ddfeacf11ed2ddb1e1bbd7d0f1693e8dcf7a777ca491609fb2c8de4cd45423de.jpg)

### Tables

![0c66c7cbe992b54e1b401267d5ccd4eee2f873c8523fb1a1047a0bc712e95cf0.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/tables/0c66c7cbe992b54e1b401267d5ccd4eee2f873c8523fb1a1047a0bc712e95cf0.jpg)

![3d0a8ff156ff956ff4dc7c88a332ee5f50a5091a6c10311ae0e0abfc33d0be73.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/tables/3d0a8ff156ff956ff4dc7c88a332ee5f50a5091a6c10311ae0e0abfc33d0be73.jpg)

![7f7bbb73036c092891b6bec878496b1e7e97dce6949217c5c25665db51ac7f91.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/tables/7f7bbb73036c092891b6bec878496b1e7e97dce6949217c5c25665db51ac7f91.jpg)

![f9b1cc0b3e17e540aeea54f9a4fdfc7b157c27229c3d0d11b03314cb38c3443a.jpg](../nips_results/1842_AutoPartGen_%20Autoregressive%203D%20Part%20Generation%20and%20Discovery/tables/f9b1cc0b3e17e540aeea54f9a4fdfc7b157c27229c3d0d11b03314cb38c3443a.jpg)

## Scaling Data-Driven Probabilistic Robustness Analysis for Semantic Segmentation Neural Networks


### Images

![1353119d4480b56509e3e75c2b66f939e037b5bac938ce953beb0ae761149452.jpg](../nips_results/1843_Scaling%20Data-Driven%20Probabilistic%20Robustness%20Analysis%20for%20Semantic%20Segmentation%20Neural%20Networks/images/1353119d4480b56509e3e75c2b66f939e037b5bac938ce953beb0ae761149452.jpg)

![36cd1c23cf46d9b74f40d2093190ed644565e29b87988bc13ffa48100247f662.jpg](../nips_results/1843_Scaling%20Data-Driven%20Probabilistic%20Robustness%20Analysis%20for%20Semantic%20Segmentation%20Neural%20Networks/images/36cd1c23cf46d9b74f40d2093190ed644565e29b87988bc13ffa48100247f662.jpg)

![4ad42db3029d45b2a7362a4d60f56b04776576ac3e030b904a70864021f663ef.jpg](../nips_results/1843_Scaling%20Data-Driven%20Probabilistic%20Robustness%20Analysis%20for%20Semantic%20Segmentation%20Neural%20Networks/images/4ad42db3029d45b2a7362a4d60f56b04776576ac3e030b904a70864021f663ef.jpg)

![6578ce117c23b7caf7014c4ebdd48a83d2fd8a05a6aeef3c74fd6d988f0e4e22.jpg](../nips_results/1843_Scaling%20Data-Driven%20Probabilistic%20Robustness%20Analysis%20for%20Semantic%20Segmentation%20Neural%20Networks/images/6578ce117c23b7caf7014c4ebdd48a83d2fd8a05a6aeef3c74fd6d988f0e4e22.jpg)

![8611c666a44f91c4e054d3919351310c6a69f27a1ec5312565df6defa95f8022.jpg](../nips_results/1843_Scaling%20Data-Driven%20Probabilistic%20Robustness%20Analysis%20for%20Semantic%20Segmentation%20Neural%20Networks/images/8611c666a44f91c4e054d3919351310c6a69f27a1ec5312565df6defa95f8022.jpg)

![9520d7c2909df4227167fbba0bea075d7a4910c37f3e7091b5cd364099b1961a.jpg](../nips_results/1843_Scaling%20Data-Driven%20Probabilistic%20Robustness%20Analysis%20for%20Semantic%20Segmentation%20Neural%20Networks/images/9520d7c2909df4227167fbba0bea075d7a4910c37f3e7091b5cd364099b1961a.jpg)

![b96555440a5cc0597e9841b1d5890e9e57ef928ac42a94f68d8e58434855ff82.jpg](../nips_results/1843_Scaling%20Data-Driven%20Probabilistic%20Robustness%20Analysis%20for%20Semantic%20Segmentation%20Neural%20Networks/images/b96555440a5cc0597e9841b1d5890e9e57ef928ac42a94f68d8e58434855ff82.jpg)

![c9cd89625605c12b62d0613b06aceec68d1ac5577c8eff5e354e3e479cb3410d.jpg](../nips_results/1843_Scaling%20Data-Driven%20Probabilistic%20Robustness%20Analysis%20for%20Semantic%20Segmentation%20Neural%20Networks/images/c9cd89625605c12b62d0613b06aceec68d1ac5577c8eff5e354e3e479cb3410d.jpg)

![e6ceef0862500250220f02bbad69976ab7cd3b2503a1147b6c092471cd07e794.jpg](../nips_results/1843_Scaling%20Data-Driven%20Probabilistic%20Robustness%20Analysis%20for%20Semantic%20Segmentation%20Neural%20Networks/images/e6ceef0862500250220f02bbad69976ab7cd3b2503a1147b6c092471cd07e794.jpg)

### Tables

![9022ab701fec40ab7722abc888d56365874343da5bfbf83f60bdc2b804b5082c.jpg](../nips_results/1843_Scaling%20Data-Driven%20Probabilistic%20Robustness%20Analysis%20for%20Semantic%20Segmentation%20Neural%20Networks/tables/9022ab701fec40ab7722abc888d56365874343da5bfbf83f60bdc2b804b5082c.jpg)

![d7ae1ed3e880eb79ca3b3fe07ff9cf9fb5e44377fff9f256b3645f3d363dceee.jpg](../nips_results/1843_Scaling%20Data-Driven%20Probabilistic%20Robustness%20Analysis%20for%20Semantic%20Segmentation%20Neural%20Networks/tables/d7ae1ed3e880eb79ca3b3fe07ff9cf9fb5e44377fff9f256b3645f3d363dceee.jpg)

## Securing the Language of Life: Inheritable Watermarks from DNA Language Models to Proteins


### Images

![4a57e469a57f10e30d7acd16e39ccfcfae13e6a84264b5c88939c5c365f10971.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/images/4a57e469a57f10e30d7acd16e39ccfcfae13e6a84264b5c88939c5c365f10971.jpg)

![51372f590160cca863791965e5382b60abda27e33af15411931b83e860becbe9.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/images/51372f590160cca863791965e5382b60abda27e33af15411931b83e860becbe9.jpg)

![ae71b4648202994231511ae53b54cb957be3ed9d92935a0ef7161261ecee88cd.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/images/ae71b4648202994231511ae53b54cb957be3ed9d92935a0ef7161261ecee88cd.jpg)

![af1c4de4b57793a8f187021f7f77791478e42eddbc17d1b3ae2b8fc0bcfe28bf.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/images/af1c4de4b57793a8f187021f7f77791478e42eddbc17d1b3ae2b8fc0bcfe28bf.jpg)

![e233d493a2c8832fffe2ba9850b66c18df3f44cb0c16721b3f5a5547533545ef.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/images/e233d493a2c8832fffe2ba9850b66c18df3f44cb0c16721b3f5a5547533545ef.jpg)

### Tables

![3aac250fcea8292e8d8d1c96ba60be406ee28c0315ccf202c659e82313e1ed7d.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/tables/3aac250fcea8292e8d8d1c96ba60be406ee28c0315ccf202c659e82313e1ed7d.jpg)

![3b722a22101dbaf5d8eabb99e58cce1bde5e76f11416b89ee75df3f391b1a2ed.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/tables/3b722a22101dbaf5d8eabb99e58cce1bde5e76f11416b89ee75df3f391b1a2ed.jpg)

![533b78dc28e802ac19e2bbc1ee243e7cf4301f94233f49eeb5d20023c268ca1e.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/tables/533b78dc28e802ac19e2bbc1ee243e7cf4301f94233f49eeb5d20023c268ca1e.jpg)

![86689d322a7d183176ec6c79d7d08a81542b7c157d0cff052edd705f1c4f092d.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/tables/86689d322a7d183176ec6c79d7d08a81542b7c157d0cff052edd705f1c4f092d.jpg)

![8aac4618312950c8d7dbe18a0e852f0e074073725db1a4342f77342bd475d611.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/tables/8aac4618312950c8d7dbe18a0e852f0e074073725db1a4342f77342bd475d611.jpg)

![9a68755c587aef0d87b6b99d40162e90642cc6582cf24247b20befd9cd730004.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/tables/9a68755c587aef0d87b6b99d40162e90642cc6582cf24247b20befd9cd730004.jpg)

![f84e64e1b25835d360dc803cd131fc5daf58a764cbeded2f916ea592f550bf88.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/tables/f84e64e1b25835d360dc803cd131fc5daf58a764cbeded2f916ea592f550bf88.jpg)

![fadbfd59bed46f4e80a5379df22024a2cd60dc87f8615c35038266fe4d4053e1.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/tables/fadbfd59bed46f4e80a5379df22024a2cd60dc87f8615c35038266fe4d4053e1.jpg)

![fc9df58ee275295b60a999af0f72d0d73b654cfc19c5807cfc562c065061071c.jpg](../nips_results/1844_Securing%20the%20Language%20of%20Life_%20Inheritable%20Watermarks%20from%20DNA%20Language%20Models%20to%20Proteins/tables/fc9df58ee275295b60a999af0f72d0d73b654cfc19c5807cfc562c065061071c.jpg)

## Conformal Prediction in The Loop: A Feedback-Based Uncertainty Model for Trajectory Optimization


### Images

![026b55ae7da3c3af0cf949ca4b041d308d51db8a43825d7428e8bd197124a154.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/images/026b55ae7da3c3af0cf949ca4b041d308d51db8a43825d7428e8bd197124a154.jpg)

![1628f8499e9c4d6351bcab14b993f9aacfcb576480e212b5643330ece6e304e9.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/images/1628f8499e9c4d6351bcab14b993f9aacfcb576480e212b5643330ece6e304e9.jpg)

![50dceb9df6fd9ad37b2417442d8f127c45ddf82e8c456619d2155546babf8228.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/images/50dceb9df6fd9ad37b2417442d8f127c45ddf82e8c456619d2155546babf8228.jpg)

### Tables

![075587118d71b542cc0b4287f054fa38c970c8ddb61908a3f1d7dc425c25ad83.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/075587118d71b542cc0b4287f054fa38c970c8ddb61908a3f1d7dc425c25ad83.jpg)

![14961f6c9bea1384ea13e0d9393c74d21d5cddc913d0c77af885b444900179aa.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/14961f6c9bea1384ea13e0d9393c74d21d5cddc913d0c77af885b444900179aa.jpg)

![2287336fe1564bfbcde1525e1f4acf26cdac79f0557bb19db950c3e6d63645a3.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/2287336fe1564bfbcde1525e1f4acf26cdac79f0557bb19db950c3e6d63645a3.jpg)

![25466adeb47fed6ec38bd2491da9a2bc01ebc94ba1f54d275627dc61386f0dd0.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/25466adeb47fed6ec38bd2491da9a2bc01ebc94ba1f54d275627dc61386f0dd0.jpg)

![30fea1cae4c9dce044e22bd82e34ceb78709eae3e67faef05ade4b68dbf6e12a.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/30fea1cae4c9dce044e22bd82e34ceb78709eae3e67faef05ade4b68dbf6e12a.jpg)

![32f9ef383307efddf7d4053aefba25b6324f92a818197e668b45bd909f2e5809.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/32f9ef383307efddf7d4053aefba25b6324f92a818197e668b45bd909f2e5809.jpg)

![55357638a937190e757ff18e845aacdaf7ace72b83800ea0041d34cb93748145.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/55357638a937190e757ff18e845aacdaf7ace72b83800ea0041d34cb93748145.jpg)

![5733802cf8ae20d9c771a93161cc11f2969751c8ebbb5c6733f52ee79457e138.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/5733802cf8ae20d9c771a93161cc11f2969751c8ebbb5c6733f52ee79457e138.jpg)

![82832fd0e8a6a2bb197a72a0402a54a1b1ccd48fd3f7d68465a6bcbe24509c4d.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/82832fd0e8a6a2bb197a72a0402a54a1b1ccd48fd3f7d68465a6bcbe24509c4d.jpg)

![a677d2b481174f021d91769d1a0078966f3a6497240793388e9a1000a870f95e.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/a677d2b481174f021d91769d1a0078966f3a6497240793388e9a1000a870f95e.jpg)

![ab7d176a30156c3751279f08a28e9dab6f99e561ee316a5188f993e1be3db061.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/ab7d176a30156c3751279f08a28e9dab6f99e561ee316a5188f993e1be3db061.jpg)

![b83b3d3c5035ecdcbfd1a6191bb147f2d4c7813df1b14cf99b27a82e41e497f4.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/b83b3d3c5035ecdcbfd1a6191bb147f2d4c7813df1b14cf99b27a82e41e497f4.jpg)

![e24228baa8232f95da8f894fe475bc3352ed9fdc91885f03dbe583f7ca4e826c.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/e24228baa8232f95da8f894fe475bc3352ed9fdc91885f03dbe583f7ca4e826c.jpg)

![fdf6de5fef8e0a3e33d69847356acd9c93d1ed769f32c9c086a97003de393ff5.jpg](../nips_results/1845_Conformal%20Prediction%20in%20The%20Loop_%20A%20Feedback-Based%20Uncertainty%20Model%20for%20Trajectory%20Optimization/tables/fdf6de5fef8e0a3e33d69847356acd9c93d1ed769f32c9c086a97003de393ff5.jpg)

## Pin the Tail on the Model: Blindfolded Repair of User-Flagged Failures in Text-to-Image Services


### Images

![030395587a408c64f9fd38f5f29cf230af3214111dfb87204da4f386f609fca7.jpg](../nips_results/1846_Pin%20the%20Tail%20on%20the%20Model_%20Blindfolded%20Repair%20of%20User-Flagged%20Failures%20in%20Text-to-Image%20Services/images/030395587a408c64f9fd38f5f29cf230af3214111dfb87204da4f386f609fca7.jpg)

![2af830055ee46b4e487c60f49aca300386dc5f576d6ba480140815b4b2f86196.jpg](../nips_results/1846_Pin%20the%20Tail%20on%20the%20Model_%20Blindfolded%20Repair%20of%20User-Flagged%20Failures%20in%20Text-to-Image%20Services/images/2af830055ee46b4e487c60f49aca300386dc5f576d6ba480140815b4b2f86196.jpg)

![4eb903ad88945febcd563a64aff017e90bd8c8f989c4e10969253f5d629e803d.jpg](../nips_results/1846_Pin%20the%20Tail%20on%20the%20Model_%20Blindfolded%20Repair%20of%20User-Flagged%20Failures%20in%20Text-to-Image%20Services/images/4eb903ad88945febcd563a64aff017e90bd8c8f989c4e10969253f5d629e803d.jpg)

![75ca6ac1cdde5684ca535cfd60b4d18e24e8b06bfca64d5f98dea4989d6149e7.jpg](../nips_results/1846_Pin%20the%20Tail%20on%20the%20Model_%20Blindfolded%20Repair%20of%20User-Flagged%20Failures%20in%20Text-to-Image%20Services/images/75ca6ac1cdde5684ca535cfd60b4d18e24e8b06bfca64d5f98dea4989d6149e7.jpg)

### Tables

![0f51b0d82bd6a8b31162dddadceefa771d5669b0a1eb9e41736471b641da41f0.jpg](../nips_results/1846_Pin%20the%20Tail%20on%20the%20Model_%20Blindfolded%20Repair%20of%20User-Flagged%20Failures%20in%20Text-to-Image%20Services/tables/0f51b0d82bd6a8b31162dddadceefa771d5669b0a1eb9e41736471b641da41f0.jpg)

![29d4b990f70d548617ff7fa90439cfe3522ab907418dd5d41a0a46083e3a255a.jpg](../nips_results/1846_Pin%20the%20Tail%20on%20the%20Model_%20Blindfolded%20Repair%20of%20User-Flagged%20Failures%20in%20Text-to-Image%20Services/tables/29d4b990f70d548617ff7fa90439cfe3522ab907418dd5d41a0a46083e3a255a.jpg)

## Analytic Energy-Guided Policy Optimization for Offline Reinforcement Learning


### Images

![28f383004a5ab7b83bb68472a55ab5fda0c1b46009f936198da169dcf8bbffe4.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/images/28f383004a5ab7b83bb68472a55ab5fda0c1b46009f936198da169dcf8bbffe4.jpg)

![32e66544d7bc7ca56e3bcc8920f69369e09b30dbadcaa327ce6d3510ac118e24.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/images/32e66544d7bc7ca56e3bcc8920f69369e09b30dbadcaa327ce6d3510ac118e24.jpg)

![7b7284d35b72f667be7d119573ca2a8a930a678a932123c5bb55fd37e2b5603c.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/images/7b7284d35b72f667be7d119573ca2a8a930a678a932123c5bb55fd37e2b5603c.jpg)

![8e3442e874e14e0ea81e3832db28a278a3d3990f2629c22966af285482a5df91.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/images/8e3442e874e14e0ea81e3832db28a278a3d3990f2629c22966af285482a5df91.jpg)

![d6a47815801370e1be90615ea855dcfa79fd694d81d27a2c8b6f58d11c1fbe99.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/images/d6a47815801370e1be90615ea855dcfa79fd694d81d27a2c8b6f58d11c1fbe99.jpg)

![fb895f1b90d839fb625a6138eafd1c332e7b9bb216b27ac6764dc5577099ca9c.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/images/fb895f1b90d839fb625a6138eafd1c332e7b9bb216b27ac6764dc5577099ca9c.jpg)

### Tables

![3e5dcfe7c86338bd4e5928eaff6a287c97bffdb4f6e22333b1d8ddbc6d75ecd8.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/tables/3e5dcfe7c86338bd4e5928eaff6a287c97bffdb4f6e22333b1d8ddbc6d75ecd8.jpg)

![4dd8f70cb52dadad77b4c07c39c9a8a9c074718a610e89afdaa6d7995fa08324.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/tables/4dd8f70cb52dadad77b4c07c39c9a8a9c074718a610e89afdaa6d7995fa08324.jpg)

![51f288ec6dd1484cf340ffdbf154d4292d19243c9600053a2a4f35133fa25f71.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/tables/51f288ec6dd1484cf340ffdbf154d4292d19243c9600053a2a4f35133fa25f71.jpg)

![829cf1e761d4fd05f60b660bbe25df60f19497415ae497baea3810915b65b17f.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/tables/829cf1e761d4fd05f60b660bbe25df60f19497415ae497baea3810915b65b17f.jpg)

![882d12d49ee73ed316573bfd9dd566873500b30069234479b06ad0a9418c622a.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/tables/882d12d49ee73ed316573bfd9dd566873500b30069234479b06ad0a9418c622a.jpg)

![a4c8199736c68e167b9c273d0951a09caac3e36a26b5334edceb092319504c04.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/tables/a4c8199736c68e167b9c273d0951a09caac3e36a26b5334edceb092319504c04.jpg)

![c31e617c86c7d9464ec699f6870c0f14d1ea1f99352b6572b804bf65de577ab7.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/tables/c31e617c86c7d9464ec699f6870c0f14d1ea1f99352b6572b804bf65de577ab7.jpg)

![f66364617efd8045e3d19fdbcc75d4a54e59765d0690e92c0653e41f0ad63a60.jpg](../nips_results/1847_Analytic%20Energy-Guided%20Policy%20Optimization%20for%20Offline%20Reinforcement%20Learning/tables/f66364617efd8045e3d19fdbcc75d4a54e59765d0690e92c0653e41f0ad63a60.jpg)

## Flatness is Necessary, Neural Collapse is Not: Rethinking Generalization via Grokking


### Images

![049d4cc88de95075bfb2140758867780f9659f8a55511d6f49c2160ebd1a2532.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/049d4cc88de95075bfb2140758867780f9659f8a55511d6f49c2160ebd1a2532.jpg)

![1a933d1b129c45301032f07dd7b1d099b5d888cd2d20a1e465df6db80c202a5d.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/1a933d1b129c45301032f07dd7b1d099b5d888cd2d20a1e465df6db80c202a5d.jpg)

![200848110d7b06aedac7a46ffd1dbc924852fc7ef5056514c98ff684fbf62cdb.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/200848110d7b06aedac7a46ffd1dbc924852fc7ef5056514c98ff684fbf62cdb.jpg)

![31b21f7fb54902452179a4dd45eb365bb0e8ff3053c486cdc936a02e75d1d79e.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/31b21f7fb54902452179a4dd45eb365bb0e8ff3053c486cdc936a02e75d1d79e.jpg)

![38af6544dc9a7e379eddafb65b318a96a25081b68b6e6aa562b506f434bdaaa3.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/38af6544dc9a7e379eddafb65b318a96a25081b68b6e6aa562b506f434bdaaa3.jpg)

![431074a6dcfecb8e9bac6218c3ff824fa6d7fbd457e8b17cd1db554b7f1e93a0.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/431074a6dcfecb8e9bac6218c3ff824fa6d7fbd457e8b17cd1db554b7f1e93a0.jpg)

![4a5c6d8591fe7a99213ca2d6691ec45a87dff52b504c9d6fc8fc981a83a04609.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/4a5c6d8591fe7a99213ca2d6691ec45a87dff52b504c9d6fc8fc981a83a04609.jpg)

![5c35e794f10fef5d92cb366b220cd3e0dbb7c5ea5df5a76c01e470619cb97d0e.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/5c35e794f10fef5d92cb366b220cd3e0dbb7c5ea5df5a76c01e470619cb97d0e.jpg)

![852e22070605ea8c1b89980ec71043a53906990498d03ae9cf82dc50436fc247.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/852e22070605ea8c1b89980ec71043a53906990498d03ae9cf82dc50436fc247.jpg)

![a03dcfbe76e1436de9d39cadb6b0f34c1e1b18dc5f95c00630688951aeca4e69.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/a03dcfbe76e1436de9d39cadb6b0f34c1e1b18dc5f95c00630688951aeca4e69.jpg)

![b21f5918d58f1905b0dee7f5b77accaaeb2c77b8ac6224f3165cae64dd5ec673.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/b21f5918d58f1905b0dee7f5b77accaaeb2c77b8ac6224f3165cae64dd5ec673.jpg)

![b789c9ba21f7437d034e7ab2c7f4fea43d04c0f46cc9e50bb5867f82154e2fbc.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/b789c9ba21f7437d034e7ab2c7f4fea43d04c0f46cc9e50bb5867f82154e2fbc.jpg)

![c2830a201850a765dfe7d16934ff5a4fc77b27744f0f39ebbd3987348f67a6ce.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/c2830a201850a765dfe7d16934ff5a4fc77b27744f0f39ebbd3987348f67a6ce.jpg)

![d01013318f89ffd90a64cffe2942d91c07e243438676cb2454b1cce474cd1d75.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/d01013318f89ffd90a64cffe2942d91c07e243438676cb2454b1cce474cd1d75.jpg)

![d1f55f356873aaf810f1866cf19b7dd02e8cec4ea3a212d7babe46d532449cd2.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/d1f55f356873aaf810f1866cf19b7dd02e8cec4ea3a212d7babe46d532449cd2.jpg)

![d68978d3a4e79d9f9f8de39b2a04b2ca55900a0cdd3dae996efed8eab0e0ee82.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/d68978d3a4e79d9f9f8de39b2a04b2ca55900a0cdd3dae996efed8eab0e0ee82.jpg)

![e0633d4ed54bf2e0e21e18f65b172ee2ffb50b26a5ce976ce17ec6321630ffb0.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/e0633d4ed54bf2e0e21e18f65b172ee2ffb50b26a5ce976ce17ec6321630ffb0.jpg)

![e1212ca577bcab861724d2d8b772399585c3c1a50712be3e68648b05a57a9bf6.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/e1212ca577bcab861724d2d8b772399585c3c1a50712be3e68648b05a57a9bf6.jpg)

![e2917c864456f9eac3017cfad49ae8787a09961d35d67bbaabb9452952cd3f58.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/e2917c864456f9eac3017cfad49ae8787a09961d35d67bbaabb9452952cd3f58.jpg)

![ff2e2a8d3be2c4a0991f50f04ef6d4ab8da2c55390d0d1ca1a8c79b833687036.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/images/ff2e2a8d3be2c4a0991f50f04ef6d4ab8da2c55390d0d1ca1a8c79b833687036.jpg)

### Tables

![6b933b2e4453f29aa66bd055c021a02ad6934553eafffe6a3dcd54fc584bb8c2.jpg](../nips_results/1848_Flatness%20is%20Necessary%2C%20Neural%20Collapse%20is%20Not_%20Rethinking%20Generalization%20via%20Grokking/tables/6b933b2e4453f29aa66bd055c021a02ad6934553eafffe6a3dcd54fc584bb8c2.jpg)

## Do Neural Networks Need Gradient Descent to Generalize? A Theoretical Study


### Images

![211ed5ffb3144eecb4773a062ef16406ba97495d98252906af3c8673a9e36c88.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/211ed5ffb3144eecb4773a062ef16406ba97495d98252906af3c8673a9e36c88.jpg)

![23cd346f42428aa240f611912b6dcb184d939aeeacb16ee09b19801f5519fa32.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/23cd346f42428aa240f611912b6dcb184d939aeeacb16ee09b19801f5519fa32.jpg)

![3a2ff3e6d3edbaa62b19eeee22388da48462c82b21301407a6fb58d9e8292fde.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/3a2ff3e6d3edbaa62b19eeee22388da48462c82b21301407a6fb58d9e8292fde.jpg)

![4ac5a7f7c43a62035824ea04cb0c3880abda2280c68336f3b7e7544a47c4fd1d.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/4ac5a7f7c43a62035824ea04cb0c3880abda2280c68336f3b7e7544a47c4fd1d.jpg)

![4b8636beec4cb74c35f2ea478b4b56ca8783e62ed963982ad119ab095ad49ad3.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/4b8636beec4cb74c35f2ea478b4b56ca8783e62ed963982ad119ab095ad49ad3.jpg)

![57fb68891c8b87208f0c08e7380ff2728308df12548359f91fd78e262f78d983.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/57fb68891c8b87208f0c08e7380ff2728308df12548359f91fd78e262f78d983.jpg)

![6c21f071b282863625a7b081e80b812de990bd5caff9c820dbe1eb3e34cfb5ef.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/6c21f071b282863625a7b081e80b812de990bd5caff9c820dbe1eb3e34cfb5ef.jpg)

![6ee66e2752ec49ba7f2fd356f40f05a49293e98e0daa98313e2ad70f52e5acf4.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/6ee66e2752ec49ba7f2fd356f40f05a49293e98e0daa98313e2ad70f52e5acf4.jpg)

![73bf89c8b4d263d5eca364ddc3ae7456222582f476a60c66a47050991cf32875.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/73bf89c8b4d263d5eca364ddc3ae7456222582f476a60c66a47050991cf32875.jpg)

![75d2328b75b4e2726fec7722f609161d79b516ddf4523e225b265c1cde8895f9.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/75d2328b75b4e2726fec7722f609161d79b516ddf4523e225b265c1cde8895f9.jpg)

![82b2c6ed5e7e7095c7846d70a22505d97dfde76166c8480dccc45cf7f9b2a897.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/82b2c6ed5e7e7095c7846d70a22505d97dfde76166c8480dccc45cf7f9b2a897.jpg)

![90919ddbd8c220cf077d4121c8d4db3ae24ce1d3a6f454f14bf82b5aab6a0c76.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/90919ddbd8c220cf077d4121c8d4db3ae24ce1d3a6f454f14bf82b5aab6a0c76.jpg)

![e2bf527678d26b249bd3e626cb96ff38bdcf4d440999a3c7fe18007f096eede0.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/images/e2bf527678d26b249bd3e626cb96ff38bdcf4d440999a3c7fe18007f096eede0.jpg)

### Tables

![362473d64fe12fd09f23e2633a6eca7d8dbbf53bc1f7b2a0fc2a5562bf92be81.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/tables/362473d64fe12fd09f23e2633a6eca7d8dbbf53bc1f7b2a0fc2a5562bf92be81.jpg)

![620c47a2bc7c7544498dc30d17113ca58b6092cb8d4e5f2981241e6ae981dd1d.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/tables/620c47a2bc7c7544498dc30d17113ca58b6092cb8d4e5f2981241e6ae981dd1d.jpg)

![64b3ec67b8bf715e2349454fd86e6c6259a96d97732b40b99514bacab121d78a.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/tables/64b3ec67b8bf715e2349454fd86e6c6259a96d97732b40b99514bacab121d78a.jpg)

![976ea281acdc4e39800e497651a7aeb4d9a48a8b6bde98b60533a8dcd6bd7e1e.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/tables/976ea281acdc4e39800e497651a7aeb4d9a48a8b6bde98b60533a8dcd6bd7e1e.jpg)

![c2a02c3d824e35eced3ce36590164a193fd4afdd3e3047ba24df06e8b93e9374.jpg](../nips_results/1849_Do%20Neural%20Networks%20Need%20Gradient%20Descent%20to%20Generalize_%20A%20Theoretical%20Study/tables/c2a02c3d824e35eced3ce36590164a193fd4afdd3e3047ba24df06e8b93e9374.jpg)

## The Quest for Universal Master Key Filters in DS-CNNs


### Images

![043a2a4e732eab2f24916d643648f313aec87e61127a4ac078557c43b4a4b8ea.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/images/043a2a4e732eab2f24916d643648f313aec87e61127a4ac078557c43b4a4b8ea.jpg)

![14bec446d5531210307aa365e2f5e91dff371898f4a1dd19b29cf9b8b9dd93d6.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/images/14bec446d5531210307aa365e2f5e91dff371898f4a1dd19b29cf9b8b9dd93d6.jpg)

![3cd6c741bae38ee6a21393c1d1c8dcc331f5677595d59dc8469d27727b908384.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/images/3cd6c741bae38ee6a21393c1d1c8dcc331f5677595d59dc8469d27727b908384.jpg)

![93f7282ccf60afdfc3b584532b227e551507d9a760f3f20f9dca8079cf75d1af.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/images/93f7282ccf60afdfc3b584532b227e551507d9a760f3f20f9dca8079cf75d1af.jpg)

![a19e361e906e4642575f7df792d30ba2e2c2c16140b549a00ea28c17468be622.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/images/a19e361e906e4642575f7df792d30ba2e2c2c16140b549a00ea28c17468be622.jpg)

![ba8249e062b8a906328be30ad1031606e47e46b42ba7d5cdf94c1f661805c9b5.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/images/ba8249e062b8a906328be30ad1031606e47e46b42ba7d5cdf94c1f661805c9b5.jpg)

![e5c174294d773a94a5c649b94b79c22e65bc0a83e4bea5c069c9e574091d5bb2.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/images/e5c174294d773a94a5c649b94b79c22e65bc0a83e4bea5c069c9e574091d5bb2.jpg)

![f5f15bee1d3644e6883b3056c10f8b1254971a246952574b9e54c1a9ee8f280c.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/images/f5f15bee1d3644e6883b3056c10f8b1254971a246952574b9e54c1a9ee8f280c.jpg)

### Tables

![152e7ae6d8263cdfe6de516d15e858b19830ddd8a3df37ec76be1af4cf80b38b.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/152e7ae6d8263cdfe6de516d15e858b19830ddd8a3df37ec76be1af4cf80b38b.jpg)

![1d9d7f8f90e3b91630bcd7c36fedbb817e7fb0e1b18e52557f8e5250c174c7f7.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/1d9d7f8f90e3b91630bcd7c36fedbb817e7fb0e1b18e52557f8e5250c174c7f7.jpg)

![206bd9bce5c600bae3afff608ace8a490a333aed0e8a2513fe950c6066028bee.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/206bd9bce5c600bae3afff608ace8a490a333aed0e8a2513fe950c6066028bee.jpg)

![393da11b5daa2742f60e92c17e70bcf213d8aded8421debb9bbc23fd92923ee2.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/393da11b5daa2742f60e92c17e70bcf213d8aded8421debb9bbc23fd92923ee2.jpg)

![3a94df060388b50aaef326eb7465cbd41ea5dddd4975a8b520e5dd5b6ff9dad4.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/3a94df060388b50aaef326eb7465cbd41ea5dddd4975a8b520e5dd5b6ff9dad4.jpg)

![4a40bce3f7ef1c4c64b5e5205899aa13247c2820b67236bf27d766ac07dbaa59.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/4a40bce3f7ef1c4c64b5e5205899aa13247c2820b67236bf27d766ac07dbaa59.jpg)

![57669ed4963001072b07e26d3a2e34a99936c19014972d105197285944a7cce9.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/57669ed4963001072b07e26d3a2e34a99936c19014972d105197285944a7cce9.jpg)

![74e7b6a2a942e665df1926a1c3f61eb67c7ac9a72145c75e8a2d5211cef0e79f.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/74e7b6a2a942e665df1926a1c3f61eb67c7ac9a72145c75e8a2d5211cef0e79f.jpg)

![85a4096d365a2e2d3e7baf63ec2afcf8bcc3714e6781bb9ede7a08b50e4bc3a8.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/85a4096d365a2e2d3e7baf63ec2afcf8bcc3714e6781bb9ede7a08b50e4bc3a8.jpg)

![9ac48e818b9d86c9b49289f4c674f735448c00b62511adacf71cd7c5a2234460.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/9ac48e818b9d86c9b49289f4c674f735448c00b62511adacf71cd7c5a2234460.jpg)

![af3f02c3b09086cbf99cb10526006ca5159b6fe703151a11db520e864f6527e4.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/af3f02c3b09086cbf99cb10526006ca5159b6fe703151a11db520e864f6527e4.jpg)

![b3024e93363f667c33409a23e415008e0ae059c02e28647b0325b7217d8ead2e.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/b3024e93363f667c33409a23e415008e0ae059c02e28647b0325b7217d8ead2e.jpg)

![bc8d6145432410b47040331b7c094d0d0cd26e86217e0b513c9e2bd871c35357.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/bc8d6145432410b47040331b7c094d0d0cd26e86217e0b513c9e2bd871c35357.jpg)

![caba45a355b8351f7ab170044af03ae4580f841d7506a326f6f05c03bfccb581.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/caba45a355b8351f7ab170044af03ae4580f841d7506a326f6f05c03bfccb581.jpg)

![f434a75a08078ce68de407fe8bd4854b9b5e292fafc3711a49836b1a3ca6ebc2.jpg](../nips_results/1850_The%20Quest%20for%20Universal%20Master%20Key%20Filters%20in%20DS-CNNs/tables/f434a75a08078ce68de407fe8bd4854b9b5e292fafc3711a49836b1a3ca6ebc2.jpg)

## Filter Like You Test: Data-Driven Data Filtering for CLIP Pretraining


### Images

![036c3d23f72f3178e19b083e93b04d64d264b20388d897ac8143f3c83c0306f1.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/036c3d23f72f3178e19b083e93b04d64d264b20388d897ac8143f3c83c0306f1.jpg)

![17d6ca7f96fae571e947fa1c681120b7e3552b06210ab50a3d41645bc1efab91.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/17d6ca7f96fae571e947fa1c681120b7e3552b06210ab50a3d41645bc1efab91.jpg)

![1cbd8601bc7abc01ecf6ef6c6577d00467c91ba413615b8001fc20cc4fdf21a8.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/1cbd8601bc7abc01ecf6ef6c6577d00467c91ba413615b8001fc20cc4fdf21a8.jpg)

![1e836e0a980359a3202057d2ffdfd371ddbfa6dc6079be579abe3768c2988cc1.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/1e836e0a980359a3202057d2ffdfd371ddbfa6dc6079be579abe3768c2988cc1.jpg)

![21cc1232125c937e7f729586c2552b86c4b27638406cb90828ee0c67c0941d02.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/21cc1232125c937e7f729586c2552b86c4b27638406cb90828ee0c67c0941d02.jpg)

![2c4e09e769160b0dcb00afb1c29f7a94301c1f93430d21dd5a9441687fa4c5e0.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/2c4e09e769160b0dcb00afb1c29f7a94301c1f93430d21dd5a9441687fa4c5e0.jpg)

![2d1faf178b2ffdada988f1377b510d809907f6bcec7524fdf800d1934a019660.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/2d1faf178b2ffdada988f1377b510d809907f6bcec7524fdf800d1934a019660.jpg)

![30e3034ed3d47ff57b184dddc7e889fb6bd6858efa8829fc3bf3c983530e7089.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/30e3034ed3d47ff57b184dddc7e889fb6bd6858efa8829fc3bf3c983530e7089.jpg)

![34cd26b57bda953b1e4c3eb9cfd867f6a7a8d3dacc0321924fb54ee25c515ea9.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/34cd26b57bda953b1e4c3eb9cfd867f6a7a8d3dacc0321924fb54ee25c515ea9.jpg)

![3ca0c3d69c398f1139d53f0c7930e76a2c782a437a0231aeaaa6f7ad9b693fb8.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/3ca0c3d69c398f1139d53f0c7930e76a2c782a437a0231aeaaa6f7ad9b693fb8.jpg)

![4125afd57b2f097fc7db7023a84f4bef3ed6f98ca330beec0f55c3ec70c2b211.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/4125afd57b2f097fc7db7023a84f4bef3ed6f98ca330beec0f55c3ec70c2b211.jpg)

![44404ff7903e3db0748efb3a5b836b89504f29866d8ec226fd048f48bb7fdff7.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/44404ff7903e3db0748efb3a5b836b89504f29866d8ec226fd048f48bb7fdff7.jpg)

![4ec37a3869e1171d0e79fd740504451e3d5211b4e32f1a43683205661b6be05a.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/4ec37a3869e1171d0e79fd740504451e3d5211b4e32f1a43683205661b6be05a.jpg)

![51778b47ac83399ee9ee04a111cdf5f9b526798a032c18f7b9b70d206d29c610.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/51778b47ac83399ee9ee04a111cdf5f9b526798a032c18f7b9b70d206d29c610.jpg)

![5b2347180bf9f07e08f94aab4000ce3d267b203092e9216e4c9f64a34895f306.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/5b2347180bf9f07e08f94aab4000ce3d267b203092e9216e4c9f64a34895f306.jpg)

![650b5631c8d1a435492cf0686583d4ab63a6e2b8895f44a3571948d92c057110.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/650b5631c8d1a435492cf0686583d4ab63a6e2b8895f44a3571948d92c057110.jpg)

![70b3303c95dafaee528b231434fd7a69be75fe0e8cc1ee7a8ae3f4967baedb43.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/70b3303c95dafaee528b231434fd7a69be75fe0e8cc1ee7a8ae3f4967baedb43.jpg)

![716222f5e73bea252cd5e7e31d5ed3797a70cc123f60d0e5766142ba1b1f4a7e.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/716222f5e73bea252cd5e7e31d5ed3797a70cc123f60d0e5766142ba1b1f4a7e.jpg)

![74ecf41990a0836a488813d96dc131fd1797279baf2771558762b00967abe072.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/74ecf41990a0836a488813d96dc131fd1797279baf2771558762b00967abe072.jpg)

![7c8a46dc74d1926cf9b5fd8a02ca57bf4afca26ecd91a4c2d6530cf56ab855dc.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/7c8a46dc74d1926cf9b5fd8a02ca57bf4afca26ecd91a4c2d6530cf56ab855dc.jpg)

![80c0ce2e885f5e497cb0432c36adf589010153799fef0171a263c3cebe6d977e.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/80c0ce2e885f5e497cb0432c36adf589010153799fef0171a263c3cebe6d977e.jpg)

![8737435a90bc6fb1d7e030b2df21a69b859bdbbbce4e47d657afef5c7f4608b1.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/8737435a90bc6fb1d7e030b2df21a69b859bdbbbce4e47d657afef5c7f4608b1.jpg)

![87c7cd4f093403e7f49e7341e9da4745ad869203f4cbd949cd7b6e49c81d12c3.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/87c7cd4f093403e7f49e7341e9da4745ad869203f4cbd949cd7b6e49c81d12c3.jpg)

![87d2fd87ee06ba394c7b1b895762eeabd3ed6ff26fd5a37558e59a46f88dc802.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/87d2fd87ee06ba394c7b1b895762eeabd3ed6ff26fd5a37558e59a46f88dc802.jpg)

![89d300f9b5d7c3a6087d98f55e0cc21667dbc8aa60c0f65b6ce941177c71a6e1.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/89d300f9b5d7c3a6087d98f55e0cc21667dbc8aa60c0f65b6ce941177c71a6e1.jpg)

![8cb8e0e729c74d330d3d3e4dcb51ec60606bc8baef98c8a537b1725b41ea3d23.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/8cb8e0e729c74d330d3d3e4dcb51ec60606bc8baef98c8a537b1725b41ea3d23.jpg)

![9246c35e2d99aae9f9a1417ffee960e883434681e0b6e59a3247957f72039929.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/9246c35e2d99aae9f9a1417ffee960e883434681e0b6e59a3247957f72039929.jpg)

![a205eb30630d65ad7103a273be782e786b076c22280827b27eb95f199bc235ac.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/a205eb30630d65ad7103a273be782e786b076c22280827b27eb95f199bc235ac.jpg)

![a2be07c6a46b178656a80c3e6706132b4c5abd6382a249ef9b6c3a6eb9c3d245.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/a2be07c6a46b178656a80c3e6706132b4c5abd6382a249ef9b6c3a6eb9c3d245.jpg)

![b0f0e289d9edc0b9993cd3000862909b3961af7e82dcb59b22eedad592daf76f.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/b0f0e289d9edc0b9993cd3000862909b3961af7e82dcb59b22eedad592daf76f.jpg)

![b2a97ad9baebfc8f0edc401ec15bef499733514cf1cec68c51653ace1ffca3ae.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/b2a97ad9baebfc8f0edc401ec15bef499733514cf1cec68c51653ace1ffca3ae.jpg)

![b7344284e02ca0ef1d6d84c8713ecb5259b43ac4b4db4fc56e8be5bd58f7e2dc.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/b7344284e02ca0ef1d6d84c8713ecb5259b43ac4b4db4fc56e8be5bd58f7e2dc.jpg)

![bca77a9bf7bbc0ffd37c829c2dff718baee68d9994b130bf3bddd3059d2ece5a.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/bca77a9bf7bbc0ffd37c829c2dff718baee68d9994b130bf3bddd3059d2ece5a.jpg)

![bd64bb32c8c5fbd1c7d2af15691522fdc8a5421271418c96941ec392e6f3f9b1.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/bd64bb32c8c5fbd1c7d2af15691522fdc8a5421271418c96941ec392e6f3f9b1.jpg)

![bfaac8605820175bc627bcaefc4cd8dfc00d987c5b522d10b3c53f4f0685568b.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/bfaac8605820175bc627bcaefc4cd8dfc00d987c5b522d10b3c53f4f0685568b.jpg)

![c0e37d9321efb6dfcd7d43e031bc20c8f9b234ab19a2e4458e01facf674f07d8.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/c0e37d9321efb6dfcd7d43e031bc20c8f9b234ab19a2e4458e01facf674f07d8.jpg)

![c8541d9e9d278329d4356d54414f2805ab1c018c73094532556c2a99a485bc69.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/c8541d9e9d278329d4356d54414f2805ab1c018c73094532556c2a99a485bc69.jpg)

![cd166c2cc8fc9226ceb0598b53660894265f1e3013d970d9d16bedaad1678661.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/cd166c2cc8fc9226ceb0598b53660894265f1e3013d970d9d16bedaad1678661.jpg)

![e4d749a65a8d9a0dbd347e899e89b016da76cfd5036ce714fb57fad33300c664.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/e4d749a65a8d9a0dbd347e899e89b016da76cfd5036ce714fb57fad33300c664.jpg)

![fd5df1541434570a5568e29d5be64f8f2d5ca76cf14742d20b654dc8d9825c7c.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/images/fd5df1541434570a5568e29d5be64f8f2d5ca76cf14742d20b654dc8d9825c7c.jpg)

### Tables

![00513a3db2a47ef547cb18de77bae302f5d6ddef5c25e5171444370f3e779010.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/00513a3db2a47ef547cb18de77bae302f5d6ddef5c25e5171444370f3e779010.jpg)

![11fa25447c65d2e27cac0590b84386ff25e071db9325fc237cbc1129b2a3d091.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/11fa25447c65d2e27cac0590b84386ff25e071db9325fc237cbc1129b2a3d091.jpg)

![213cdcf777e52a4d58ba53fd8eb522272f82b9c3bfef2af5dd4007760e2f963c.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/213cdcf777e52a4d58ba53fd8eb522272f82b9c3bfef2af5dd4007760e2f963c.jpg)

![230662d8287d250e348372cb5bcd68a6a77a6f05889dbed574c471a51c8e9f4a.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/230662d8287d250e348372cb5bcd68a6a77a6f05889dbed574c471a51c8e9f4a.jpg)

![26ec369034c787eb8d8ef4411720f2e7ea990aa464777c8fcc43d35506d25c33.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/26ec369034c787eb8d8ef4411720f2e7ea990aa464777c8fcc43d35506d25c33.jpg)

![4ef9c74be267d61ab1ca75c5dcda5b48c283e6086298892aed7614cf491c0bcb.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/4ef9c74be267d61ab1ca75c5dcda5b48c283e6086298892aed7614cf491c0bcb.jpg)

![50d5207ab71ee17da7e44682da9d8a1d6c6d81a0e293cd8f880df2ddee4368de.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/50d5207ab71ee17da7e44682da9d8a1d6c6d81a0e293cd8f880df2ddee4368de.jpg)

![53b008802af9617c09ea78abddf7fbaed7b6103fd9a27c6af5674cf00f9b1bc1.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/53b008802af9617c09ea78abddf7fbaed7b6103fd9a27c6af5674cf00f9b1bc1.jpg)

![6651b81369d33833f0868923241901fb7c1b72a6c58980703a84f7fe88a43cf5.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/6651b81369d33833f0868923241901fb7c1b72a6c58980703a84f7fe88a43cf5.jpg)

![75ec64c8063d66cc3b205119a67d954863365ba20411c3e024f4ad231b1ff1b0.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/75ec64c8063d66cc3b205119a67d954863365ba20411c3e024f4ad231b1ff1b0.jpg)

![8b607c91172136917696ab9b5a0403dc59962d4b6830114442c904309b7fbaf1.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/8b607c91172136917696ab9b5a0403dc59962d4b6830114442c904309b7fbaf1.jpg)

![985473ffe0c13372ae4d1cf939ca0391b03128416b934b6accab0046c050170e.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/985473ffe0c13372ae4d1cf939ca0391b03128416b934b6accab0046c050170e.jpg)

![b61c03ad618efce27cd526d41d37ee562ddf9ac19ae0da1046ef2629fd61b787.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/b61c03ad618efce27cd526d41d37ee562ddf9ac19ae0da1046ef2629fd61b787.jpg)

![c77e024062fa898d548f3bbee5674e0a786bb8d9a0bd88f2b20bedbe93e8d336.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/c77e024062fa898d548f3bbee5674e0a786bb8d9a0bd88f2b20bedbe93e8d336.jpg)

![d054035d2396d0a8a59b7e60bdf6cc068f4f99f74b88e2e5b077d8554216f5ff.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/d054035d2396d0a8a59b7e60bdf6cc068f4f99f74b88e2e5b077d8554216f5ff.jpg)

![edeeb9fb3bd7f558246d6714cd4c3fd4654e455987df851ae1971c852de6c8b9.jpg](../nips_results/1851_Filter%20Like%20You%20Test_%20Data-Driven%20Data%20Filtering%20for%20CLIP%20Pretraining/tables/edeeb9fb3bd7f558246d6714cd4c3fd4654e455987df851ae1971c852de6c8b9.jpg)

## Gated Integration of Low-Rank Adaptation for Continual Learning  of Large Language Models


### Images

![0c5dbc7bd3aeec712b44c0141847780048e6531ff8a982a362591dfea7564d28.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/images/0c5dbc7bd3aeec712b44c0141847780048e6531ff8a982a362591dfea7564d28.jpg)

![512e5aa50b7b3c8d62d393f7823d410d588ce3edca2b04480a0ca7d4192c5537.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/images/512e5aa50b7b3c8d62d393f7823d410d588ce3edca2b04480a0ca7d4192c5537.jpg)

![5174fca0c022f6812c0d4f48a7151fde5b7298576f7e2a2e99a75edb79d4bd3f.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/images/5174fca0c022f6812c0d4f48a7151fde5b7298576f7e2a2e99a75edb79d4bd3f.jpg)

![54c7a044ff8b2f7f0a634d65339d0d099263a3cf091ab7343f5bce33f9d55de8.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/images/54c7a044ff8b2f7f0a634d65339d0d099263a3cf091ab7343f5bce33f9d55de8.jpg)

![832e656e1d7066985b404ed9d0cfea6da9767a119820b80a71f804b93c403631.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/images/832e656e1d7066985b404ed9d0cfea6da9767a119820b80a71f804b93c403631.jpg)

![d8342316c744b57b10e71f41c6ac17938bf089560ecb79ebacc39911e9a1c993.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/images/d8342316c744b57b10e71f41c6ac17938bf089560ecb79ebacc39911e9a1c993.jpg)

### Tables

![0defb20fe111c2d865fb3480398a44705f0342b228a7af5e0c84b44d1b83bdf2.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/0defb20fe111c2d865fb3480398a44705f0342b228a7af5e0c84b44d1b83bdf2.jpg)

![1fa53cd6c9a0bdeda5a5801695bfe7aa996555f0905b9bd8a5d5b03c66d8daef.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/1fa53cd6c9a0bdeda5a5801695bfe7aa996555f0905b9bd8a5d5b03c66d8daef.jpg)

![26f58cc682e2d1d67bf3bbe11fb3343c24845c9070e3b5e1a5a2d7507c4c1189.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/26f58cc682e2d1d67bf3bbe11fb3343c24845c9070e3b5e1a5a2d7507c4c1189.jpg)

![2d86d92deeeed4f82f2b5db643d242d4273563c524f22095a4bef62c20e1e5d8.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/2d86d92deeeed4f82f2b5db643d242d4273563c524f22095a4bef62c20e1e5d8.jpg)

![4cb8bd47790cc7211233c4f2703c20b47d8f5e0f67085f425defb8f8593463e5.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/4cb8bd47790cc7211233c4f2703c20b47d8f5e0f67085f425defb8f8593463e5.jpg)

![537cf21025993c9b5cd75f26972fb413ec311d0be5c58acea6be3714e2cf54ec.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/537cf21025993c9b5cd75f26972fb413ec311d0be5c58acea6be3714e2cf54ec.jpg)

![74fd90f1c00eec79f8f26ef903ee381a2658cfd5f8ebd674979c50d3e9350bb5.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/74fd90f1c00eec79f8f26ef903ee381a2658cfd5f8ebd674979c50d3e9350bb5.jpg)

![9270b5921dbd5b73d86471082a3f82292d596094b4dcbfe00f3647943dd96369.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/9270b5921dbd5b73d86471082a3f82292d596094b4dcbfe00f3647943dd96369.jpg)

![9e89fc654e59a82de2ac918bf7e942e72cd118ec0231bf7e8a761bef1939b08d.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/9e89fc654e59a82de2ac918bf7e942e72cd118ec0231bf7e8a761bef1939b08d.jpg)

![b12a4715b207237efae1a0920724943e029255ac204e28d23526706fe0903955.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/b12a4715b207237efae1a0920724943e029255ac204e28d23526706fe0903955.jpg)

![cb7c9157472380485a604b64ddddbf30cd72b5dc8e3d65dee8552b47ff6d7c42.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/cb7c9157472380485a604b64ddddbf30cd72b5dc8e3d65dee8552b47ff6d7c42.jpg)

![d27ad984ef5ea31435501dd6c7c3a54bfb3e56df2ad7b183f5d83bede5e2eb36.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/d27ad984ef5ea31435501dd6c7c3a54bfb3e56df2ad7b183f5d83bede5e2eb36.jpg)

![df1c5d559c677f658cc3fcc8d5392baf1bd800ab2468ddcf28eabc5d50f60ba7.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/df1c5d559c677f658cc3fcc8d5392baf1bd800ab2468ddcf28eabc5d50f60ba7.jpg)

![ec1c4bf48c698684c118dbf176e6dae0495f39fa72d671acd636733de395c9be.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/ec1c4bf48c698684c118dbf176e6dae0495f39fa72d671acd636733de395c9be.jpg)

![f893e3c0f76d41c031823ef023256d6872d426587a386484dc9abc179d540d1c.jpg](../nips_results/1852_Gated%20Integration%20of%20Low-Rank%20Adaptation%20for%20Continual%20Learning%20%20of%20Large%20Language%20Models/tables/f893e3c0f76d41c031823ef023256d6872d426587a386484dc9abc179d540d1c.jpg)

## Addressing Mark Imbalance in Integration-free Marked Temporal Point Processes


### Images

![148461592c5cc2734ac573f9e4d9ba8eff2fc2c1a1105d493c1787f5f4c96707.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/images/148461592c5cc2734ac573f9e4d9ba8eff2fc2c1a1105d493c1787f5f4c96707.jpg)

![a20c1aa65f596846ce49f47855a6b336092388bae0eec930a40a2a216fb791a2.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/images/a20c1aa65f596846ce49f47855a6b336092388bae0eec930a40a2a216fb791a2.jpg)

![ee112c78290e1168724880359465d392893c077f8abee5eebb2309f817c1692a.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/images/ee112c78290e1168724880359465d392893c077f8abee5eebb2309f817c1692a.jpg)

### Tables

![03d06748002e6c61d02a130d803f647f60c8eb4524f6ea168b21b891367c1341.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/03d06748002e6c61d02a130d803f647f60c8eb4524f6ea168b21b891367c1341.jpg)

![1466e1c7366d271f45d5014f1ef9c090f1adf8900c75a8aff3d6d08bc221f021.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/1466e1c7366d271f45d5014f1ef9c090f1adf8900c75a8aff3d6d08bc221f021.jpg)

![1b0437669a33d31f4680ac90ad66d3b74c235f160b3ae54cc666f315b60b7279.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/1b0437669a33d31f4680ac90ad66d3b74c235f160b3ae54cc666f315b60b7279.jpg)

![341cdbe90ea9244286f3538ae308543f0f8883cb40d2139afeba36b740250603.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/341cdbe90ea9244286f3538ae308543f0f8883cb40d2139afeba36b740250603.jpg)

![342b41fd8eabd8ceb34f7c54d3d86152379afa265c79cc94346cba669b003103.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/342b41fd8eabd8ceb34f7c54d3d86152379afa265c79cc94346cba669b003103.jpg)

![3929d5e216ab8715cd766108ddb3f401e89a8b4c76aeb8ecd11b73599ed275e9.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/3929d5e216ab8715cd766108ddb3f401e89a8b4c76aeb8ecd11b73599ed275e9.jpg)

![3b6831c67fa0f882cb62266d2974617d50b622c06dea974bd4f2b595f7dc2a29.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/3b6831c67fa0f882cb62266d2974617d50b622c06dea974bd4f2b595f7dc2a29.jpg)

![45a990f26137ef22eb18464b2869c18018cdb601969f4a5360f5390ba611d2f5.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/45a990f26137ef22eb18464b2869c18018cdb601969f4a5360f5390ba611d2f5.jpg)

![6b455cea0c65aaf304c360c33c86dd8f38dbf65425a6160a07166bf17fed2ccd.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/6b455cea0c65aaf304c360c33c86dd8f38dbf65425a6160a07166bf17fed2ccd.jpg)

![6cf33819044e0df13a44a5625e426a0557c100c016241055d3e5bc10391c3e0c.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/6cf33819044e0df13a44a5625e426a0557c100c016241055d3e5bc10391c3e0c.jpg)

![7e9e07a8e76a94fa6ed95ab9ce91abe972c8db816a922c92b97b7a08e07a56e1.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/7e9e07a8e76a94fa6ed95ab9ce91abe972c8db816a922c92b97b7a08e07a56e1.jpg)

![9317f41f0d7332bdd28974671db9d43916cc3e3299d0ca1b5199b3ab81c7645a.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/9317f41f0d7332bdd28974671db9d43916cc3e3299d0ca1b5199b3ab81c7645a.jpg)

![acb8d3bac91969e83b52fa62d49d2bdeebc2b816ace5ce0c2aeb77ed8ce37c7f.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/acb8d3bac91969e83b52fa62d49d2bdeebc2b816ace5ce0c2aeb77ed8ce37c7f.jpg)

![be11f0181afd29e4aea8d5ca30d416fb7249ac2eca9aa2099c9ead0f2126d0c1.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/be11f0181afd29e4aea8d5ca30d416fb7249ac2eca9aa2099c9ead0f2126d0c1.jpg)

![cfe6dba4c605e0761fe8ad339059b24e759e3bc10ec9008a0ef25c7e0edad34c.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/cfe6dba4c605e0761fe8ad339059b24e759e3bc10ec9008a0ef25c7e0edad34c.jpg)

![df81d4522718730a97e63b93eca5445555ce8d489f93bad07b5a55fbf06e2341.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/df81d4522718730a97e63b93eca5445555ce8d489f93bad07b5a55fbf06e2341.jpg)

![f0d40062775a8987995a0529c5cf9aaede1cbd3e66384a2400154570c43551b4.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/f0d40062775a8987995a0529c5cf9aaede1cbd3e66384a2400154570c43551b4.jpg)

![fd47481aa92f726e5b3518152763c677d60b6f846223db39629f154994d05aa8.jpg](../nips_results/1853_Addressing%20Mark%20Imbalance%20in%20Integration-free%20Marked%20Temporal%20Point%20Processes/tables/fd47481aa92f726e5b3518152763c677d60b6f846223db39629f154994d05aa8.jpg)

## Towards Unified Multimodal Interleaved Generation via Group Relative Policy Optimization


### Images

![05a027612d5e8ab9c0df1d9ee728a8aa3c197bdf5354cff9a83423497eb435aa.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/images/05a027612d5e8ab9c0df1d9ee728a8aa3c197bdf5354cff9a83423497eb435aa.jpg)

![1b6c4391b687ea61d1b5566644c5cc67ea136dcc2c6871445ccb7ef1244e8628.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/images/1b6c4391b687ea61d1b5566644c5cc67ea136dcc2c6871445ccb7ef1244e8628.jpg)

![38a06bd638186e45cc7a4e0cb24267c57a667719f235685a871f2b4c7f7dd084.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/images/38a06bd638186e45cc7a4e0cb24267c57a667719f235685a871f2b4c7f7dd084.jpg)

![401b0f3c7be3ac4e117107e541e20da6d06bc442fd40d1bfe9632aa504372f93.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/images/401b0f3c7be3ac4e117107e541e20da6d06bc442fd40d1bfe9632aa504372f93.jpg)

![4d961fa615fedac9400a67e086ba43ed67939911643ab3ff7d2efa2fc7d7ca11.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/images/4d961fa615fedac9400a67e086ba43ed67939911643ab3ff7d2efa2fc7d7ca11.jpg)

![6a81002e5bf83934f57d8b2833b21b38e365f22ea6b94ebd4f094f95f61cb510.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/images/6a81002e5bf83934f57d8b2833b21b38e365f22ea6b94ebd4f094f95f61cb510.jpg)

![79eccf53d04d3d24f4910c27f11871026a780407b7ea4c69cc56d506964a1362.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/images/79eccf53d04d3d24f4910c27f11871026a780407b7ea4c69cc56d506964a1362.jpg)

![96a61d06a8f36640e5f991a5fef92d0237d5e313aed1ff0353d24b78bb473310.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/images/96a61d06a8f36640e5f991a5fef92d0237d5e313aed1ff0353d24b78bb473310.jpg)

![ea227782749feccf9f30800dd3d671abcc20db2751744a964bab10e647fb01eb.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/images/ea227782749feccf9f30800dd3d671abcc20db2751744a964bab10e647fb01eb.jpg)

![ed845c0639242f73ec63da4e40ec9d377cffa8763f7a1dd66084ae146cbf6b63.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/images/ed845c0639242f73ec63da4e40ec9d377cffa8763f7a1dd66084ae146cbf6b63.jpg)

### Tables

![564f0ccbb5d55ec4f903dab5311fbcce2545ad798f7545d02dfa3de25dec0198.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/tables/564f0ccbb5d55ec4f903dab5311fbcce2545ad798f7545d02dfa3de25dec0198.jpg)

![5d192ed11d430d739c070f2088afdeef240a7a14cdbe95ab2644c0990d7164fd.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/tables/5d192ed11d430d739c070f2088afdeef240a7a14cdbe95ab2644c0990d7164fd.jpg)

![61b45fa4a6880d547aa76f4e54fdd28d475e235075292546bcdf0e90a445b491.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/tables/61b45fa4a6880d547aa76f4e54fdd28d475e235075292546bcdf0e90a445b491.jpg)

![7091545e7793587fe7e4ec04ff72855aae6cf76c79fe92d5e0c3de8a9f023bee.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/tables/7091545e7793587fe7e4ec04ff72855aae6cf76c79fe92d5e0c3de8a9f023bee.jpg)

![a60b095bb53d88e9dd71e01ab68aa28765402a9f62cd46e05d281b1b0b2d35a1.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/tables/a60b095bb53d88e9dd71e01ab68aa28765402a9f62cd46e05d281b1b0b2d35a1.jpg)

![ba6e887ae74c6ef4ecfb8784d1a8bf8ae56bbf5434186ef5828a3caed1d0af03.jpg](../nips_results/1854_Towards%20Unified%20Multimodal%20Interleaved%20Generation%20via%20Group%20Relative%20Policy%20Optimization/tables/ba6e887ae74c6ef4ecfb8784d1a8bf8ae56bbf5434186ef5828a3caed1d0af03.jpg)

## Smooth Sailing: Lipschitz-Driven Uncertainty Quantification for Spatial Associations


### Images

![1ecc088110092635783bcbbd70ad8c36c05c84946b26fa32aac8ad59ea918467.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/1ecc088110092635783bcbbd70ad8c36c05c84946b26fa32aac8ad59ea918467.jpg)

![2f180d90f29431c5c23d2e5d9c831f1d24e808489d1151525af0a2834fb1dce2.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/2f180d90f29431c5c23d2e5d9c831f1d24e808489d1151525af0a2834fb1dce2.jpg)

![4db25db7c5e88e0a85fecde84b6ef9c0250785a2faad6a190ff95c65bfb4dbcd.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/4db25db7c5e88e0a85fecde84b6ef9c0250785a2faad6a190ff95c65bfb4dbcd.jpg)

![7f4938fd64f20b05ae65f085d2b012f4d7712eda22fcf70ef3560ef8d686f20f.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/7f4938fd64f20b05ae65f085d2b012f4d7712eda22fcf70ef3560ef8d686f20f.jpg)

![a3ff356de85d74c75b7b481488cadf52f5b7de4d1e9e56fabdb1069042dc83e1.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/a3ff356de85d74c75b7b481488cadf52f5b7de4d1e9e56fabdb1069042dc83e1.jpg)

![a92ac085528941920da3328186010a11ddb84377d24da1d5022e1a6e43f5ca07.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/a92ac085528941920da3328186010a11ddb84377d24da1d5022e1a6e43f5ca07.jpg)

![acba17a8e83ebafe29ab7d13f0ec17d164271d70795c64c09e7781436f10e70c.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/acba17a8e83ebafe29ab7d13f0ec17d164271d70795c64c09e7781436f10e70c.jpg)

![b852f690515d9d2cc11c615c5ae38c475dee88e8bde33ec6849c8def727fe7b5.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/b852f690515d9d2cc11c615c5ae38c475dee88e8bde33ec6849c8def727fe7b5.jpg)

![bb6e36027ef192b890cbbf3544153a4752ddcfe0bccc31e8c7c81536552532de.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/bb6e36027ef192b890cbbf3544153a4752ddcfe0bccc31e8c7c81536552532de.jpg)

![bf19eb0d50bbd9803e6e656daaf5a55fbbceb301bad5275010ae7e64f40c2f09.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/bf19eb0d50bbd9803e6e656daaf5a55fbbceb301bad5275010ae7e64f40c2f09.jpg)

![c357b46ee3d7eb42b7f12da8f5c89156448cf326f8a4bbe70c01e3bc2a764239.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/c357b46ee3d7eb42b7f12da8f5c89156448cf326f8a4bbe70c01e3bc2a764239.jpg)

![daee279247f8d4fd6e495898661e1c2de7e0838c562602a2308260a798977caa.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/daee279247f8d4fd6e495898661e1c2de7e0838c562602a2308260a798977caa.jpg)

![dfce0800aa93e560d4813379c247bac3ef5debba0fdfe63cde11228c6882ec3d.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/dfce0800aa93e560d4813379c247bac3ef5debba0fdfe63cde11228c6882ec3d.jpg)

![fba15e9536708a06d1a3c4b95ab8f430e3fa0df82caecc0275d45b7c7273dfd3.jpg](../nips_results/1855_Smooth%20Sailing_%20Lipschitz-Driven%20Uncertainty%20Quantification%20for%20Spatial%20Associations/images/fba15e9536708a06d1a3c4b95ab8f430e3fa0df82caecc0275d45b7c7273dfd3.jpg)

## LaM-SLidE: Latent Space Modeling of Spatial Dynamical Systems via Linked Entities


### Images

![014054144d93b6b2c2bba73d434c7e3e6f2aa7b22ee7cd892de60e750b10d758.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/014054144d93b6b2c2bba73d434c7e3e6f2aa7b22ee7cd892de60e750b10d758.jpg)

![04dfa682a09bfaa5ed8e778f1bea4cd27b8eab352a177aa947c275c0ee670694.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/04dfa682a09bfaa5ed8e778f1bea4cd27b8eab352a177aa947c275c0ee670694.jpg)

![05454b04ecf9d2d181613c7e2a00641926504adeeec9757e4ea47e01f58d25b1.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/05454b04ecf9d2d181613c7e2a00641926504adeeec9757e4ea47e01f58d25b1.jpg)

![1456617723fafeedf4764e727297b3ea6cfd7d97cf67f475fd372be7fd3631fc.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/1456617723fafeedf4764e727297b3ea6cfd7d97cf67f475fd372be7fd3631fc.jpg)

![3091872892fb252e7e49df8ccee3c26800f56a4bb7e51211abdc9aca1f7dc0fd.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/3091872892fb252e7e49df8ccee3c26800f56a4bb7e51211abdc9aca1f7dc0fd.jpg)

![32f044fb8626fdf2aa11b7ddb312e833492be04f7188ee32aa9fb97f52feaa2c.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/32f044fb8626fdf2aa11b7ddb312e833492be04f7188ee32aa9fb97f52feaa2c.jpg)

![4181a5dfb5a8a6dd62318d637ae3ae08422e4a4c47e0ae521e60b905c08b4733.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/4181a5dfb5a8a6dd62318d637ae3ae08422e4a4c47e0ae521e60b905c08b4733.jpg)

![48e856a64db7f41624aaf5e3b9287c94cc57995fde2077e707bebedb0dd1877b.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/48e856a64db7f41624aaf5e3b9287c94cc57995fde2077e707bebedb0dd1877b.jpg)

![5b6fcea6a4e88554ce55584c7303535d1cdeecc50cc993a65c7a422efb04aeb1.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/5b6fcea6a4e88554ce55584c7303535d1cdeecc50cc993a65c7a422efb04aeb1.jpg)

![622b1d7a1181ee5da1f54b1a8a0f3d892830ace597698cd8a2d2543760311141.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/622b1d7a1181ee5da1f54b1a8a0f3d892830ace597698cd8a2d2543760311141.jpg)

![6ec54bc822a7d2fc0c043c89d5db4ac9930afb719c33db317093fef546fb8ae2.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/6ec54bc822a7d2fc0c043c89d5db4ac9930afb719c33db317093fef546fb8ae2.jpg)

![72c9bf159ab11dbf68b9b299ebb84565f540ddb4522830d89478d4bf70a75ab5.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/72c9bf159ab11dbf68b9b299ebb84565f540ddb4522830d89478d4bf70a75ab5.jpg)

![97e5dee5c00680bde01cfdb65914269857724efa306f642969db8c3025b5cff9.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/97e5dee5c00680bde01cfdb65914269857724efa306f642969db8c3025b5cff9.jpg)

![9e14c83e0c23cf1a171553db93f2265a757945549b5e1302bfa545c14f009863.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/9e14c83e0c23cf1a171553db93f2265a757945549b5e1302bfa545c14f009863.jpg)

![ab4b25dc8a08853519a36ba9f423ec7c5e1aa6a6510d0534699c5b806cee4d08.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/ab4b25dc8a08853519a36ba9f423ec7c5e1aa6a6510d0534699c5b806cee4d08.jpg)

![d2ca080f4918421463ca48c07b86f040a6850ff9386485d9bf40abdc8bea7550.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/d2ca080f4918421463ca48c07b86f040a6850ff9386485d9bf40abdc8bea7550.jpg)

![f12c7bb0a06fd6988be2e5177424ea43c7785b06d169647c19b305873dbc5ee3.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/f12c7bb0a06fd6988be2e5177424ea43c7785b06d169647c19b305873dbc5ee3.jpg)

![fa624a38c2faafde6d778f0f13daa6c7811d15b4fa26fa02b17710f906fad801.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/fa624a38c2faafde6d778f0f13daa6c7811d15b4fa26fa02b17710f906fad801.jpg)

![fcdf83b670cec17335286872541d1d2362a390973fb5cce4f9e7b1b487db6145.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/images/fcdf83b670cec17335286872541d1d2362a390973fb5cce4f9e7b1b487db6145.jpg)

### Tables

![1037e83e3deeaaac6fcaeb95c3ca6658d6b36625dbd31457a7a73058e29a0d1c.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/1037e83e3deeaaac6fcaeb95c3ca6658d6b36625dbd31457a7a73058e29a0d1c.jpg)

![1abae79268f77c1f8205299d645f4555eedce617c2c1f0c2f5093876985c7871.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/1abae79268f77c1f8205299d645f4555eedce617c2c1f0c2f5093876985c7871.jpg)

![1af00dbd97cb53082366431241808d26b392ea237e47d95f5918d01088dfbddc.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/1af00dbd97cb53082366431241808d26b392ea237e47d95f5918d01088dfbddc.jpg)

![37449b78a8fae30738b4de72ea3747a49b5bf2ab432aa8843d7473a96478ac65.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/37449b78a8fae30738b4de72ea3747a49b5bf2ab432aa8843d7473a96478ac65.jpg)

![448a6165fa3f44c05df56eaa45aa9af4bf008d9042529965dc88336d918d1c70.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/448a6165fa3f44c05df56eaa45aa9af4bf008d9042529965dc88336d918d1c70.jpg)

![61b12b84ae7c07f90f373a6b4770e122725b5b7005ea7f219d0b57576ab507f0.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/61b12b84ae7c07f90f373a6b4770e122725b5b7005ea7f219d0b57576ab507f0.jpg)

![68ddaf3517dab51089885f6ab99315e5509b5f21d786111f505f4cf6e2e337ba.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/68ddaf3517dab51089885f6ab99315e5509b5f21d786111f505f4cf6e2e337ba.jpg)

![752dffb6676f5bce3a12464a40a77629c3f7f4883bda808e27e09b35d7cb6886.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/752dffb6676f5bce3a12464a40a77629c3f7f4883bda808e27e09b35d7cb6886.jpg)

![7a2d91ebac4e8ae7af2fc8745fb8dd106ed17d457c520d40673fb2fc599b0a11.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/7a2d91ebac4e8ae7af2fc8745fb8dd106ed17d457c520d40673fb2fc599b0a11.jpg)

![9771412dfe37209c209f6147dcea963a842958f72691226a27f1388afad19cc6.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/9771412dfe37209c209f6147dcea963a842958f72691226a27f1388afad19cc6.jpg)

![9c61084a6042c6848d975a55cf80b2672c58ef49153aea27effca09ceb7eba16.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/9c61084a6042c6848d975a55cf80b2672c58ef49153aea27effca09ceb7eba16.jpg)

![b39a14c03a0173f50e0f2c273fb5c93f3a05ecffd831e316db918bd7a4355fe8.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/b39a14c03a0173f50e0f2c273fb5c93f3a05ecffd831e316db918bd7a4355fe8.jpg)

![c0d85a46f602c5cc1852ad2cf408db613cec742765b47c593ca113f73114e27b.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/c0d85a46f602c5cc1852ad2cf408db613cec742765b47c593ca113f73114e27b.jpg)

![c3d4de91a1fbb1e34e08230e3cf75c61e7c71058603decdd05c7bd3cfcf07fa4.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/c3d4de91a1fbb1e34e08230e3cf75c61e7c71058603decdd05c7bd3cfcf07fa4.jpg)

![d4ed8b1f52de815cfface0920fa9cc999aaf5c5e1a757a74f72dbcdae9761a5e.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/d4ed8b1f52de815cfface0920fa9cc999aaf5c5e1a757a74f72dbcdae9761a5e.jpg)

![e41665d04c47f3493fd6ab55c73cf192aff009bd3f8213e3a9a27794a2ba7efa.jpg](../nips_results/1856_LaM-SLidE_%20Latent%20Space%20Modeling%20of%20Spatial%20Dynamical%20Systems%20via%20Linked%20Entities/tables/e41665d04c47f3493fd6ab55c73cf192aff009bd3f8213e3a9a27794a2ba7efa.jpg)

## From Human Attention to Diagnosis: Semantic Patch-Level Integration of Vision-Language Models in Medical Imaging


### Images

![0d83c5601ffb0072e865d28436f677a2767d21534ad3eef80393fc3ac8be4aa4.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/images/0d83c5601ffb0072e865d28436f677a2767d21534ad3eef80393fc3ac8be4aa4.jpg)

![632e33d7a4ddc346d980ec4676dd629f26f4d48cbb19ccb5b0f5a26957439d19.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/images/632e33d7a4ddc346d980ec4676dd629f26f4d48cbb19ccb5b0f5a26957439d19.jpg)

![bc60b4eb0d2bbb90b08325f8eb870ab7267f83f80272253e4bfb5b4a27f1c235.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/images/bc60b4eb0d2bbb90b08325f8eb870ab7267f83f80272253e4bfb5b4a27f1c235.jpg)

![fafeb8b27095b8392844fde21cf2dcb849dc0f6bfb60364664f8688360e6acda.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/images/fafeb8b27095b8392844fde21cf2dcb849dc0f6bfb60364664f8688360e6acda.jpg)

### Tables

![09a853baf97ab91e269bed342514ab1c2284c0a0ffa2c45682db9645da94a1c2.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/tables/09a853baf97ab91e269bed342514ab1c2284c0a0ffa2c45682db9645da94a1c2.jpg)

![375f1bde27d8e2f40c9781e3b966ae6666ee7db8c389a6f357670abbf509def5.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/tables/375f1bde27d8e2f40c9781e3b966ae6666ee7db8c389a6f357670abbf509def5.jpg)

![6765dd36aeb0bb8b3550bc4e00d77435444492a51831d4dfabb6285c068f4817.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/tables/6765dd36aeb0bb8b3550bc4e00d77435444492a51831d4dfabb6285c068f4817.jpg)

![71acccf88555f88c5aaca4cb8514eb72134704c686fb280c3d0aba39fccc0101.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/tables/71acccf88555f88c5aaca4cb8514eb72134704c686fb280c3d0aba39fccc0101.jpg)

![9536ae8fbaf8e9687fa219c2f50682bceb899370ff0581a173fdd53b1bae60d4.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/tables/9536ae8fbaf8e9687fa219c2f50682bceb899370ff0581a173fdd53b1bae60d4.jpg)

![b1cd9a65249f7c9a35ac9225ef365f9e813eac2c0454aec7c52b07a31b0bdd9e.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/tables/b1cd9a65249f7c9a35ac9225ef365f9e813eac2c0454aec7c52b07a31b0bdd9e.jpg)

![cd93fb1872cc8b5e5ac73840e61f711dad463a02075d54d4f76b173bb66f00fa.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/tables/cd93fb1872cc8b5e5ac73840e61f711dad463a02075d54d4f76b173bb66f00fa.jpg)

![f01ebb80b9bfab02b49318c5136d147bc3609154d452cac829468f9ba5c9100d.jpg](../nips_results/1857_From%20Human%20Attention%20to%20Diagnosis_%20Semantic%20Patch-Level%20Integration%20of%20Vision-Language%20Models%20in%20Med/tables/f01ebb80b9bfab02b49318c5136d147bc3609154d452cac829468f9ba5c9100d.jpg)

## $\mu$PC: Scaling Predictive Coding to 100+ Layer Networks


### Images

![07d89e431b570008e00754f09e201b94758cb5d3eb86471297199cc08a2a208c.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/07d89e431b570008e00754f09e201b94758cb5d3eb86471297199cc08a2a208c.jpg)

![0b418d23ecee3c1295a530f4e451f6f86c4276653cc900db5efcea2d25682b28.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/0b418d23ecee3c1295a530f4e451f6f86c4276653cc900db5efcea2d25682b28.jpg)

![137bf005410c2eb052b6aba00afc9b17833c6ed4d354c6c38334e04ccba8da96.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/137bf005410c2eb052b6aba00afc9b17833c6ed4d354c6c38334e04ccba8da96.jpg)

![1f6c5dd6b5d1285a21ae6c80b25b9f7145fc2b883241e5f501286659d8100e51.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/1f6c5dd6b5d1285a21ae6c80b25b9f7145fc2b883241e5f501286659d8100e51.jpg)

![26be8dca7ca9c48efda235c711923e69aa08cc1c5ae540700abaad4ee4375d3a.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/26be8dca7ca9c48efda235c711923e69aa08cc1c5ae540700abaad4ee4375d3a.jpg)

![29bc11dce50edca459ed19d3baaf48d0764fe205bb646fd0c7ec885b067484f1.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/29bc11dce50edca459ed19d3baaf48d0764fe205bb646fd0c7ec885b067484f1.jpg)

![3242adf010ba1be61e189865e573e41c292bb4afa57d1232d04bcbaa3999b85e.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/3242adf010ba1be61e189865e573e41c292bb4afa57d1232d04bcbaa3999b85e.jpg)

![37c5198c9d67f12b2d58528c2e7e82bae30331f2c6f13d49f4658441f9f634c1.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/37c5198c9d67f12b2d58528c2e7e82bae30331f2c6f13d49f4658441f9f634c1.jpg)

![4329384f3f3820f7d7ea83f56abae21dfbf2d2759bccd3851800c8c058e0e6dc.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/4329384f3f3820f7d7ea83f56abae21dfbf2d2759bccd3851800c8c058e0e6dc.jpg)

![4499b64fff930a8c00f9939f173afc61b2e2da12fe0557d2032812162dca2c76.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/4499b64fff930a8c00f9939f173afc61b2e2da12fe0557d2032812162dca2c76.jpg)

![46dde51ba4f4357864ebfe1039ce4ce349e893626ce60640b04cd84f22262e59.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/46dde51ba4f4357864ebfe1039ce4ce349e893626ce60640b04cd84f22262e59.jpg)

![71a7cacad341f065496b65e851acad4c7019e545df04983a5d986d35b3f9b308.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/71a7cacad341f065496b65e851acad4c7019e545df04983a5d986d35b3f9b308.jpg)

![7622f969f90d4a7358ee37b6526397ee5e0ad3bd37dd65be72291cc85c578001.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/7622f969f90d4a7358ee37b6526397ee5e0ad3bd37dd65be72291cc85c578001.jpg)

![7638be57f6c5ebb4ea8999d81a3066d747bf4698c5c9a1d3264ed34eace87203.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/7638be57f6c5ebb4ea8999d81a3066d747bf4698c5c9a1d3264ed34eace87203.jpg)

![78ffdf07871699e0a60ca51b0b866eebd8eb0fa6565d06907c4bf2e3988bc3af.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/78ffdf07871699e0a60ca51b0b866eebd8eb0fa6565d06907c4bf2e3988bc3af.jpg)

![793d13a5ee286afc45ea2ede72936d4cb9ce005ea6d2a7447ad6daffdc9e2ca2.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/793d13a5ee286afc45ea2ede72936d4cb9ce005ea6d2a7447ad6daffdc9e2ca2.jpg)

![829439eadadc0a1ab1d98f8534b4dda216474ad1444aee87807f136f15fe3e05.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/829439eadadc0a1ab1d98f8534b4dda216474ad1444aee87807f136f15fe3e05.jpg)

![856e68c07e4a1aad0762bdf7a1a5c927830067e700592436102bb3e88f4163f7.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/856e68c07e4a1aad0762bdf7a1a5c927830067e700592436102bb3e88f4163f7.jpg)

![8ab7fd0177c87874233703210578389b6c67d69ed88c5d5d12713084b4080677.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/8ab7fd0177c87874233703210578389b6c67d69ed88c5d5d12713084b4080677.jpg)

![93ed2970a49f401fc06648a260df3d1fcc794c3f92f7a0f72dc7c5c0f3199c2d.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/93ed2970a49f401fc06648a260df3d1fcc794c3f92f7a0f72dc7c5c0f3199c2d.jpg)

![9a300d3ca4837d0bfe5350039c666e409b7cefb6b0645dc3b8112d379f09ff30.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/9a300d3ca4837d0bfe5350039c666e409b7cefb6b0645dc3b8112d379f09ff30.jpg)

![9b481968df740bf582085224f0fdab9b1233241b973e94c2167e91576274f3f7.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/9b481968df740bf582085224f0fdab9b1233241b973e94c2167e91576274f3f7.jpg)

![9b9143fce6a5607cf9a4a860d2fa868cfd2f1a77a69aa009a447611c057721be.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/9b9143fce6a5607cf9a4a860d2fa868cfd2f1a77a69aa009a447611c057721be.jpg)

![a2d27a9405b0976434794626d81483476c00444206eaf3d7ca18e901f6eadf44.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/a2d27a9405b0976434794626d81483476c00444206eaf3d7ca18e901f6eadf44.jpg)

![a6de40e04dda2f363b268863f57f6ffa06fb9441c9bf7629b58795dc5fba94ee.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/a6de40e04dda2f363b268863f57f6ffa06fb9441c9bf7629b58795dc5fba94ee.jpg)

![a782c07ae71d63bb894bb8b18cd8bb3ab309c941ee7b530faaea8a5a86e23375.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/a782c07ae71d63bb894bb8b18cd8bb3ab309c941ee7b530faaea8a5a86e23375.jpg)

![ae12a078fce26fc67dbf2c513e9957588f845560d7c698556b35c11444c4d7c1.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/ae12a078fce26fc67dbf2c513e9957588f845560d7c698556b35c11444c4d7c1.jpg)

![af9c5b35d313e99f586a4626eb694ba24eea5200f86641d7f9256c41745631da.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/af9c5b35d313e99f586a4626eb694ba24eea5200f86641d7f9256c41745631da.jpg)

![b26a3577a4147e6a91d3cf7dd65642931d82e051e94781ab962aedffeb40db82.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/b26a3577a4147e6a91d3cf7dd65642931d82e051e94781ab962aedffeb40db82.jpg)

![b336711f6a6082f09f65a595e0dff45b462ce672e7e876fbb240fa3c1a113cfd.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/b336711f6a6082f09f65a595e0dff45b462ce672e7e876fbb240fa3c1a113cfd.jpg)

![bb5072d78087d0608eb7339e74b4a5fdc8c880eef7c7e5f94c63e99d0df49c8e.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/bb5072d78087d0608eb7339e74b4a5fdc8c880eef7c7e5f94c63e99d0df49c8e.jpg)

![bf1cf07a24bcaa951e67d075d831379c1f0be4b9d6826f217762de9595ee9335.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/bf1cf07a24bcaa951e67d075d831379c1f0be4b9d6826f217762de9595ee9335.jpg)

![c1860a4ca5673608e55b1f6e4e99876ad6faf672747d0fc1de0cfd94fe2a9895.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/c1860a4ca5673608e55b1f6e4e99876ad6faf672747d0fc1de0cfd94fe2a9895.jpg)

![cdfd3bb7449f279eaf0658bc560dea88883f6d88191f0efda098b0e49b563206.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/cdfd3bb7449f279eaf0658bc560dea88883f6d88191f0efda098b0e49b563206.jpg)

![ce775d7600bfdfc823f7dc0203ce2c448f9f3f0d4b5e7e634b0d99d0c86082bf.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/ce775d7600bfdfc823f7dc0203ce2c448f9f3f0d4b5e7e634b0d99d0c86082bf.jpg)

![d1938e6099422e844c846999df5ce5c638a426b8df4046236ad2d3e87f638962.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/d1938e6099422e844c846999df5ce5c638a426b8df4046236ad2d3e87f638962.jpg)

![dc4699ea3b899eace1df93dbd5fa0575fab8c514bf2b427515c3c19b27ec1bf5.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/dc4699ea3b899eace1df93dbd5fa0575fab8c514bf2b427515c3c19b27ec1bf5.jpg)

![e247da5caebfb520ec51e6cf70a8dc22a94d73c1382765e1f1d889d966448a81.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/e247da5caebfb520ec51e6cf70a8dc22a94d73c1382765e1f1d889d966448a81.jpg)

![e2797e58ac737f88ebdfdb2f4990368d1a6328ef31b1a8632e387dd62ccc4f60.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/e2797e58ac737f88ebdfdb2f4990368d1a6328ef31b1a8632e387dd62ccc4f60.jpg)

![e68db1ee18487a410166999873af3a3f62e632fd3f83d57a7d12a8711a425ea2.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/e68db1ee18487a410166999873af3a3f62e632fd3f83d57a7d12a8711a425ea2.jpg)

![ec04c110d0dfdcce202c3cfd10db99bea8893d0467b6ceb0ad19166fef5e7660.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/ec04c110d0dfdcce202c3cfd10db99bea8893d0467b6ceb0ad19166fef5e7660.jpg)

![f28fce76baf51c6e48258009c799955b76518e565afd56c4eb5f35c03ee1a169.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/f28fce76baf51c6e48258009c799955b76518e565afd56c4eb5f35c03ee1a169.jpg)

![fde76c67eb878c128a1306ba1113ba73e7d7fd2c9ede42d312a26f371191340c.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/images/fde76c67eb878c128a1306ba1113ba73e7d7fd2c9ede42d312a26f371191340c.jpg)

### Tables

![57691b08257c50845b477b3d3fa94c7c41bf3fe6eb6ca9bda8fdd2fb353186ed.jpg](../nips_results/1858_%24_mu%24PC_%20Scaling%20Predictive%20Coding%20to%20100%2B%20Layer%20Networks/tables/57691b08257c50845b477b3d3fa94c7c41bf3fe6eb6ca9bda8fdd2fb353186ed.jpg)

## SplitFlow: Flow Decomposition for Inversion-Free Text-to-Image Editing


### Images

![a154fc7d885e08649ce9c366cbbd2afd2c2be05e64f8d01dbef1b9612861e509.jpg](../nips_results/1859_SplitFlow_%20Flow%20Decomposition%20for%20Inversion-Free%20Text-to-Image%20Editing/images/a154fc7d885e08649ce9c366cbbd2afd2c2be05e64f8d01dbef1b9612861e509.jpg)

![a4bf9b106be1ff8fbc62d0eaec1d1f4dc74c81077fca8e0f6eecf53e7f09967f.jpg](../nips_results/1859_SplitFlow_%20Flow%20Decomposition%20for%20Inversion-Free%20Text-to-Image%20Editing/images/a4bf9b106be1ff8fbc62d0eaec1d1f4dc74c81077fca8e0f6eecf53e7f09967f.jpg)

![b4d83e27dac2a7f19848d55a7ce6565e68e44cd43e4c320b414c7057cdbeef07.jpg](../nips_results/1859_SplitFlow_%20Flow%20Decomposition%20for%20Inversion-Free%20Text-to-Image%20Editing/images/b4d83e27dac2a7f19848d55a7ce6565e68e44cd43e4c320b414c7057cdbeef07.jpg)

### Tables

![1714096142c2d34f971a50088d2534395ce31ffd222a1f26de9e3f93b74c34de.jpg](../nips_results/1859_SplitFlow_%20Flow%20Decomposition%20for%20Inversion-Free%20Text-to-Image%20Editing/tables/1714096142c2d34f971a50088d2534395ce31ffd222a1f26de9e3f93b74c34de.jpg)

![3447e63096b20fec7a978342c2333823d9869246e8241c2882d126e3c37e4a1e.jpg](../nips_results/1859_SplitFlow_%20Flow%20Decomposition%20for%20Inversion-Free%20Text-to-Image%20Editing/tables/3447e63096b20fec7a978342c2333823d9869246e8241c2882d126e3c37e4a1e.jpg)

![92436c95b129b63d033bfcdba3a937c5811fc3b226a3a52c1f6791e3fb36a867.jpg](../nips_results/1859_SplitFlow_%20Flow%20Decomposition%20for%20Inversion-Free%20Text-to-Image%20Editing/tables/92436c95b129b63d033bfcdba3a937c5811fc3b226a3a52c1f6791e3fb36a867.jpg)

## GOOD: Training-Free Guided Diffusion Sampling for Out-of-Distribution Detection


### Images

![01684af43c8e1160c832e3aa9b3a9f514950e0baa319c5f2d1665ca08278d13d.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/01684af43c8e1160c832e3aa9b3a9f514950e0baa319c5f2d1665ca08278d13d.jpg)

![0d2886b52f8d8b6b9d94052c95436cea52473d2b8267a7ac227444a2b8f6ef84.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/0d2886b52f8d8b6b9d94052c95436cea52473d2b8267a7ac227444a2b8f6ef84.jpg)

![192315644c8bc2b734a9cc3d67846ac5a4c18deef3936a5e6419008d26d7805f.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/192315644c8bc2b734a9cc3d67846ac5a4c18deef3936a5e6419008d26d7805f.jpg)

![4818fe51b925ec0d4271a0523d7a024d3b2a1325978c43195fba1e15aa1e1540.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/4818fe51b925ec0d4271a0523d7a024d3b2a1325978c43195fba1e15aa1e1540.jpg)

![5a25bd4e3f958245d141574f368281219a9c7612aef343a14c7152e1d8de32a9.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/5a25bd4e3f958245d141574f368281219a9c7612aef343a14c7152e1d8de32a9.jpg)

![6a6dbaea0996cff299e5287566f1c8de0c41b169bcedc36681f794e235ed8729.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/6a6dbaea0996cff299e5287566f1c8de0c41b169bcedc36681f794e235ed8729.jpg)

![7eefa82c01914e59ba498e55f1ecee2b801114b5229b3dc0b1a2b6fa0e2002dd.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/7eefa82c01914e59ba498e55f1ecee2b801114b5229b3dc0b1a2b6fa0e2002dd.jpg)

![8499b78538eeaf6fe0433fe80c8fe038baf7c5018cb0798f7a26f6cf52762eae.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/8499b78538eeaf6fe0433fe80c8fe038baf7c5018cb0798f7a26f6cf52762eae.jpg)

![86acec9367620cbe3c12bc55cb9e01dbbeb726ccb4156b890419b3bcb3603b45.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/86acec9367620cbe3c12bc55cb9e01dbbeb726ccb4156b890419b3bcb3603b45.jpg)

![b9f1527bc2cae2b67f1a647131afdecddf1b1866781db163c732dadaed46032b.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/b9f1527bc2cae2b67f1a647131afdecddf1b1866781db163c732dadaed46032b.jpg)

![d7a6929e087afca8acf278df936b0a85b1377322a47b08d6bfbf68bf1e51e534.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/d7a6929e087afca8acf278df936b0a85b1377322a47b08d6bfbf68bf1e51e534.jpg)

![de1c506c6b07a7a1649cd0df2e4b4874d189a581c77ae1e5b6059fb3171d18e1.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/de1c506c6b07a7a1649cd0df2e4b4874d189a581c77ae1e5b6059fb3171d18e1.jpg)

![dfd0b6d55232f36b2692be5f190780ffbc58fa4d73984782233d888fae6b827b.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/dfd0b6d55232f36b2692be5f190780ffbc58fa4d73984782233d888fae6b827b.jpg)

![e3789888a0ceb31e4d3609bd5aa48328884b68d8c4ef175a467d650331d28b1a.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/e3789888a0ceb31e4d3609bd5aa48328884b68d8c4ef175a467d650331d28b1a.jpg)

![f0c6d435f453766d0a1f6081f1ce874b21464e9a40a7ce9e2abd5d6b71a673c4.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/f0c6d435f453766d0a1f6081f1ce874b21464e9a40a7ce9e2abd5d6b71a673c4.jpg)

![fdab2d5c09ffafe461681ab6ce26b0e8bb94f97c6f41ae14262ecce952b871a6.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/images/fdab2d5c09ffafe461681ab6ce26b0e8bb94f97c6f41ae14262ecce952b871a6.jpg)

### Tables

![18d05b5d285e9e66682f967c2e43b22970c6e53705f8244ea376e81a894d9575.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/tables/18d05b5d285e9e66682f967c2e43b22970c6e53705f8244ea376e81a894d9575.jpg)

![aaab586b5995a982764aefc20456258bac849bcee2564ab6d9e40ca49d5c6149.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/tables/aaab586b5995a982764aefc20456258bac849bcee2564ab6d9e40ca49d5c6149.jpg)

![adc9c4b26b59ffd1c28ec7c320d3729431b2fe21b52a7f3c5b508636d19bdc9e.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/tables/adc9c4b26b59ffd1c28ec7c320d3729431b2fe21b52a7f3c5b508636d19bdc9e.jpg)

![f9b80656ead4c884d7998a44552892c8a663ddeb6a48d32e70544e3a6c94b41e.jpg](../nips_results/1860_GOOD_%20Training-Free%20Guided%20Diffusion%20Sampling%20for%20Out-of-Distribution%20Detection/tables/f9b80656ead4c884d7998a44552892c8a663ddeb6a48d32e70544e3a6c94b41e.jpg)

## A Closer Look at TabPFN v2: Understanding Its Strengths and Extending Its Capabilities


### Images

![0d1d82406c3d86fd2c44be4bfa8b03bbc0b79cb586670925a1895ad7608c40fa.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/images/0d1d82406c3d86fd2c44be4bfa8b03bbc0b79cb586670925a1895ad7608c40fa.jpg)

![0e673b0a0c0179eb8662af0991fc9622e912730990bc58068086a0ac5e04cdd0.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/images/0e673b0a0c0179eb8662af0991fc9622e912730990bc58068086a0ac5e04cdd0.jpg)

![412c6f92e9c49da5954b2e1e2a341ff001c4103457d7a227e6df8d7cdb0227d5.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/images/412c6f92e9c49da5954b2e1e2a341ff001c4103457d7a227e6df8d7cdb0227d5.jpg)

![4e669ab5b7dc89a7f2800cf6a5d7c5b561ad2f8b6d9a2e774e1b3ec3e1f48837.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/images/4e669ab5b7dc89a7f2800cf6a5d7c5b561ad2f8b6d9a2e774e1b3ec3e1f48837.jpg)

![7b3ad69e7ed92aef44581a5ba3e5f488ae72e34f26b46040c8fb00e5841b843d.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/images/7b3ad69e7ed92aef44581a5ba3e5f488ae72e34f26b46040c8fb00e5841b843d.jpg)

![837dca4cc8054aba046dc095dcc86ddab68094dfe683567191b2e93e5171f912.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/images/837dca4cc8054aba046dc095dcc86ddab68094dfe683567191b2e93e5171f912.jpg)

![cb1a1b127ea7ed9158b5f96524bd36d167ad3422ea6cce2ace816e0831090696.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/images/cb1a1b127ea7ed9158b5f96524bd36d167ad3422ea6cce2ace816e0831090696.jpg)

![cb95d5b1c5e6804bb4b1fa236cf0281061e440db617da0ad03ba8bdfc9b95d58.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/images/cb95d5b1c5e6804bb4b1fa236cf0281061e440db617da0ad03ba8bdfc9b95d58.jpg)

![d6e3f8a6aaf9637e6909dc8862a79bd5fec77125125c48890040b2d6d6622e76.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/images/d6e3f8a6aaf9637e6909dc8862a79bd5fec77125125c48890040b2d6d6622e76.jpg)

### Tables

![369f5e1b26d9d32640938b52ccb868d8585a6b99e669729b1c20cfd30c06be02.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/369f5e1b26d9d32640938b52ccb868d8585a6b99e669729b1c20cfd30c06be02.jpg)

![39bfb181fb228bfb0be62bc48fd45569c825c8ae368107a18e3a765e7f99c4d6.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/39bfb181fb228bfb0be62bc48fd45569c825c8ae368107a18e3a765e7f99c4d6.jpg)

![3b208fe01bf91812b26244d23a20fbe957a7686de64adcf2d0ce874fd6d75f1b.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/3b208fe01bf91812b26244d23a20fbe957a7686de64adcf2d0ce874fd6d75f1b.jpg)

![438f20f4bd3fe55cc277f6a8153a963ef1b097777f31c84bb7de74295b01493e.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/438f20f4bd3fe55cc277f6a8153a963ef1b097777f31c84bb7de74295b01493e.jpg)

![564f6825811e3f689344ff901a3697aa4519732283de70841d0df79cc4b0432c.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/564f6825811e3f689344ff901a3697aa4519732283de70841d0df79cc4b0432c.jpg)

![6682ff8d9c7a9944ca6fdd3ac312610d2436ac9faef9b44a3e1463c87a06caa0.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/6682ff8d9c7a9944ca6fdd3ac312610d2436ac9faef9b44a3e1463c87a06caa0.jpg)

![7db7949532bfb790f66cace3501ff3c9d92969625acd7ba28b23a412e39807c4.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/7db7949532bfb790f66cace3501ff3c9d92969625acd7ba28b23a412e39807c4.jpg)

![9e59276b8b2675530aadff226788eea89a621f4f98839311fab0af8aefae3ede.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/9e59276b8b2675530aadff226788eea89a621f4f98839311fab0af8aefae3ede.jpg)

![a08c88ebfc9e59da94a7b5986aa8092efcb53c701b2234ab16191086fdcf746f.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/a08c88ebfc9e59da94a7b5986aa8092efcb53c701b2234ab16191086fdcf746f.jpg)

![ce1aeafbc94397230523cc6d6b3d3b62326e1eb3bc249dcad7eec8331fa3f778.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/ce1aeafbc94397230523cc6d6b3d3b62326e1eb3bc249dcad7eec8331fa3f778.jpg)

![cf46982e11e4f2fa07cb819ee8e70ee03b9f8c3471952216268b2542f161c09b.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/cf46982e11e4f2fa07cb819ee8e70ee03b9f8c3471952216268b2542f161c09b.jpg)

![dfdeb1b84bb1c67b0d5f56c76cd3c3261f7e4fa6149c8a7e03b3c7236f120b87.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/dfdeb1b84bb1c67b0d5f56c76cd3c3261f7e4fa6149c8a7e03b3c7236f120b87.jpg)

![f38aac36756acda8c2573b89db004b4ba5acffa248a014a5d6cebcb76ef1616d.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/f38aac36756acda8c2573b89db004b4ba5acffa248a014a5d6cebcb76ef1616d.jpg)

![fc97457d9333f54a5ac0db5562291baea0adcf2237b79a4c4b9a8b333414f49d.jpg](../nips_results/1861_A%20Closer%20Look%20at%20TabPFN%20v2_%20Understanding%20Its%20Strengths%20and%20Extending%20Its%20Capabilities/tables/fc97457d9333f54a5ac0db5562291baea0adcf2237b79a4c4b9a8b333414f49d.jpg)

## Vinci: Deep Thinking in Text-to-Image Generation using Unified Model with Reinforcement Learning


### Images

![20f53697027fb32b87323c15256a3a414278fc9a8498be29d04e7f607fc8e27c.jpg](../nips_results/1862_Vinci_%20Deep%20Thinking%20in%20Text-to-Image%20Generation%20using%20Unified%20Model%20with%20Reinforcement%20Learning/images/20f53697027fb32b87323c15256a3a414278fc9a8498be29d04e7f607fc8e27c.jpg)

![4b1e5b33b8749be33b86e93ec9a7e1b53610b4fc6bf24df40bed36d36a08a993.jpg](../nips_results/1862_Vinci_%20Deep%20Thinking%20in%20Text-to-Image%20Generation%20using%20Unified%20Model%20with%20Reinforcement%20Learning/images/4b1e5b33b8749be33b86e93ec9a7e1b53610b4fc6bf24df40bed36d36a08a993.jpg)

![973ecbfb571b2f83668cd7739fe3c4164c8cb2550284c4755e5f4d8da7808bb0.jpg](../nips_results/1862_Vinci_%20Deep%20Thinking%20in%20Text-to-Image%20Generation%20using%20Unified%20Model%20with%20Reinforcement%20Learning/images/973ecbfb571b2f83668cd7739fe3c4164c8cb2550284c4755e5f4d8da7808bb0.jpg)

![babde66652b3bbaf007822f8c959e40d5c6d2bc56f565ab9aa17dd82a9f6c5af.jpg](../nips_results/1862_Vinci_%20Deep%20Thinking%20in%20Text-to-Image%20Generation%20using%20Unified%20Model%20with%20Reinforcement%20Learning/images/babde66652b3bbaf007822f8c959e40d5c6d2bc56f565ab9aa17dd82a9f6c5af.jpg)

![bc49e412d2b5d4f1a8f8e33808051f4e7447c96f85ddd3a2c93b1396b806facf.jpg](../nips_results/1862_Vinci_%20Deep%20Thinking%20in%20Text-to-Image%20Generation%20using%20Unified%20Model%20with%20Reinforcement%20Learning/images/bc49e412d2b5d4f1a8f8e33808051f4e7447c96f85ddd3a2c93b1396b806facf.jpg)

### Tables

![0e9c40de67c956b3347d17fbd5e34f932aceb558e7a1d35ae088c561b7f59105.jpg](../nips_results/1862_Vinci_%20Deep%20Thinking%20in%20Text-to-Image%20Generation%20using%20Unified%20Model%20with%20Reinforcement%20Learning/tables/0e9c40de67c956b3347d17fbd5e34f932aceb558e7a1d35ae088c561b7f59105.jpg)

![8c514d99e166cf6ca33ac44091e2562a1e40ec33f691ab43eafa0fdd55a27543.jpg](../nips_results/1862_Vinci_%20Deep%20Thinking%20in%20Text-to-Image%20Generation%20using%20Unified%20Model%20with%20Reinforcement%20Learning/tables/8c514d99e166cf6ca33ac44091e2562a1e40ec33f691ab43eafa0fdd55a27543.jpg)

![95cd7466525d97895722516fed64b8aa2184d32ae8073812e09a35fc5006901a.jpg](../nips_results/1862_Vinci_%20Deep%20Thinking%20in%20Text-to-Image%20Generation%20using%20Unified%20Model%20with%20Reinforcement%20Learning/tables/95cd7466525d97895722516fed64b8aa2184d32ae8073812e09a35fc5006901a.jpg)

![e30e6f58714aa120fb2621cbc8593aa3b256ad58be2dc38336cbc04e457dcc36.jpg](../nips_results/1862_Vinci_%20Deep%20Thinking%20in%20Text-to-Image%20Generation%20using%20Unified%20Model%20with%20Reinforcement%20Learning/tables/e30e6f58714aa120fb2621cbc8593aa3b256ad58be2dc38336cbc04e457dcc36.jpg)

## Timely Clinical Diagnosis through Active Test Selection


### Images

![3895a3d1c6f9a27250e61a024ac08e57b558f205534ae49c095d9ee9d06f16fb.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/3895a3d1c6f9a27250e61a024ac08e57b558f205534ae49c095d9ee9d06f16fb.jpg)

![3998855db3cca4f7aec329afdfdc7a06c472b81e9071be1b02ce5d9540c1d04f.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/3998855db3cca4f7aec329afdfdc7a06c472b81e9071be1b02ce5d9540c1d04f.jpg)

![3ffe97a1eed9b99cafc6335dd8b63a98e09e767f000762437df17b7d694619d8.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/3ffe97a1eed9b99cafc6335dd8b63a98e09e767f000762437df17b7d694619d8.jpg)

![45caaa3484934d865ac23985664befac4d003110223dc8cfc5c74b81adf74bc8.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/45caaa3484934d865ac23985664befac4d003110223dc8cfc5c74b81adf74bc8.jpg)

![4b98900bd29f5c39a083d19fb7188f1db2f4712019571fd87025d7837e0ad18e.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/4b98900bd29f5c39a083d19fb7188f1db2f4712019571fd87025d7837e0ad18e.jpg)

![7537a9408a9415abdc09cb2fd21fb8ad9b3a60b79d2c01c6d0b6344ff669fb9f.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/7537a9408a9415abdc09cb2fd21fb8ad9b3a60b79d2c01c6d0b6344ff669fb9f.jpg)

![7b24024afb985e52ba4e9f178ef23d49ba4f1bb369740086de1f2177b64f928b.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/7b24024afb985e52ba4e9f178ef23d49ba4f1bb369740086de1f2177b64f928b.jpg)

![96648184a3802200ac0ac3411918f4876e49eb99a781c4f8743a5873687e4911.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/96648184a3802200ac0ac3411918f4876e49eb99a781c4f8743a5873687e4911.jpg)

![b01680633a297c8ed7665f96956796c41a092735dfdb65021e818f25bc80af8b.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/b01680633a297c8ed7665f96956796c41a092735dfdb65021e818f25bc80af8b.jpg)

![c39ff3366e42d0996d11583dfb6fb00a3f3cc841183942ed39f612d3df164e70.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/c39ff3366e42d0996d11583dfb6fb00a3f3cc841183942ed39f612d3df164e70.jpg)

![d83b1e533b95a855f0e2d5564e2ff5e827120582bf46cc1e5062d516dfda8a2f.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/d83b1e533b95a855f0e2d5564e2ff5e827120582bf46cc1e5062d516dfda8a2f.jpg)

![df88263a140ef3d3d6ab87e98470d37d56d7f35b1ec745f6fe9f097956ec2cb2.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/df88263a140ef3d3d6ab87e98470d37d56d7f35b1ec745f6fe9f097956ec2cb2.jpg)

![ee7400878cb9cbaa27f65231d66b400f1b09f3f2510c808379f6d05e14f5715f.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/ee7400878cb9cbaa27f65231d66b400f1b09f3f2510c808379f6d05e14f5715f.jpg)

![f44fb36cbd269cc6d5255066086b7737efee045fc84fcb56db2837b39d5eb4ff.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/f44fb36cbd269cc6d5255066086b7737efee045fc84fcb56db2837b39d5eb4ff.jpg)

![fa3d7486c4c670c254e703c645e94d460ee768bc75d84e27d7679614bd6b2b9f.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/images/fa3d7486c4c670c254e703c645e94d460ee768bc75d84e27d7679614bd6b2b9f.jpg)

### Tables

![0aa1dc0a617c727c5d95b0c9c8abe350731a11019f615073e922e67f481bc24c.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/0aa1dc0a617c727c5d95b0c9c8abe350731a11019f615073e922e67f481bc24c.jpg)

![33e8740c4c06e6d8bea21c4ab7b7356cda77e829025d72528464a4e2d22de444.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/33e8740c4c06e6d8bea21c4ab7b7356cda77e829025d72528464a4e2d22de444.jpg)

![3f60406e9622cf89536d9b233856acba711901da7667d01719b00f4f7963c7f6.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/3f60406e9622cf89536d9b233856acba711901da7667d01719b00f4f7963c7f6.jpg)

![4e2ac5ae549d0a9a3fe5d63922406a501885d9d17a97b6f127595d86beedc890.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/4e2ac5ae549d0a9a3fe5d63922406a501885d9d17a97b6f127595d86beedc890.jpg)

![4eb8845bb3feb8046678b0a36ef094f0bc2f486af246b71d1ab10ddeddec258c.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/4eb8845bb3feb8046678b0a36ef094f0bc2f486af246b71d1ab10ddeddec258c.jpg)

![50349fb15cd0db836904fd4ece7f734b06528c99c9810aab97a42d1f378cb685.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/50349fb15cd0db836904fd4ece7f734b06528c99c9810aab97a42d1f378cb685.jpg)

![55c24b957941fca2510e649bbc8343b32c784d9f036f9f646359837d61661c6e.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/55c24b957941fca2510e649bbc8343b32c784d9f036f9f646359837d61661c6e.jpg)

![59248348af798611df74382e58a929eff5ab297d0c8203ad083b0b42a27ff973.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/59248348af798611df74382e58a929eff5ab297d0c8203ad083b0b42a27ff973.jpg)

![663be7737afb011b2c1eb7d33cb7f26dd9f3c0901945286d0a0890590a5185f3.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/663be7737afb011b2c1eb7d33cb7f26dd9f3c0901945286d0a0890590a5185f3.jpg)

![9c8a346da69585524fd34a594fc694912e8d05b42c4502c451f3f2fbfe479689.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/9c8a346da69585524fd34a594fc694912e8d05b42c4502c451f3f2fbfe479689.jpg)

![a7e646bb19265c7af7e7e6b5fd78c296f60e4fe71ac12fc16f02de4fb32e2d3b.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/a7e646bb19265c7af7e7e6b5fd78c296f60e4fe71ac12fc16f02de4fb32e2d3b.jpg)

![b8dd3c9adc073f3d45f736e5ef72d3c9b81ae0e707acb1971459e4fa0025c902.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/b8dd3c9adc073f3d45f736e5ef72d3c9b81ae0e707acb1971459e4fa0025c902.jpg)

![d165466d7f554f7c270b7cae31d777fcec26a776550e0a0d090904df529fd1a4.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/d165466d7f554f7c270b7cae31d777fcec26a776550e0a0d090904df529fd1a4.jpg)

![f23ec9b0d7502ca0a6138e3b0ec0f93a2eb2b4cd1a6d437e9b741fcc29fcd9fe.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/f23ec9b0d7502ca0a6138e3b0ec0f93a2eb2b4cd1a6d437e9b741fcc29fcd9fe.jpg)

![f3ab1c97b182d0e9a0e4615ad13d01e4641f9d6ec1e560c48778c0959dba78b8.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/f3ab1c97b182d0e9a0e4615ad13d01e4641f9d6ec1e560c48778c0959dba78b8.jpg)

![f89c1da7d4b052c5eb5baefcb362098ca08a8454bb33fb0bf30e9cd910220815.jpg](../nips_results/1863_Timely%20Clinical%20Diagnosis%20through%20Active%20Test%20Selection/tables/f89c1da7d4b052c5eb5baefcb362098ca08a8454bb33fb0bf30e9cd910220815.jpg)

## SmartCache: Context-aware Semantic Cache for Efficient Multi-turn LLM Inference


### Images

![0f6d0a91f88fe6aaf9a411c31ec4480823ea6bd0e11df499edfdcb3f11962a16.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/images/0f6d0a91f88fe6aaf9a411c31ec4480823ea6bd0e11df499edfdcb3f11962a16.jpg)

![2817daef0b90cc0804bfd8d1705f6fdac4f4f5e19258737401e4fcfdbfcb747b.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/images/2817daef0b90cc0804bfd8d1705f6fdac4f4f5e19258737401e4fcfdbfcb747b.jpg)

![2bce861d3f548c36956e0b26ed87a66bfe156a2dcd56c76ce8f561f1f9077001.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/images/2bce861d3f548c36956e0b26ed87a66bfe156a2dcd56c76ce8f561f1f9077001.jpg)

![6ab8c22cf32ae6c7b1f52e538154618a07588a1176321af18699d1638f514bad.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/images/6ab8c22cf32ae6c7b1f52e538154618a07588a1176321af18699d1638f514bad.jpg)

![962c2b8ede71360670bb781b432f35b08745d452a800d1049b26bb58594427d8.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/images/962c2b8ede71360670bb781b432f35b08745d452a800d1049b26bb58594427d8.jpg)

![b3e7b182b581b5d3700d2f9a35acb01e3b84ff53d77df4a6413ff423142ffb0e.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/images/b3e7b182b581b5d3700d2f9a35acb01e3b84ff53d77df4a6413ff423142ffb0e.jpg)

![c1200295689dd3341c1a0038734432638cbe04214c0031acc80f5d0deb33a8ec.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/images/c1200295689dd3341c1a0038734432638cbe04214c0031acc80f5d0deb33a8ec.jpg)

![f06ad239da872f5ae9affcf47022d33a539429d824e272ac3f0af4cd634b8683.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/images/f06ad239da872f5ae9affcf47022d33a539429d824e272ac3f0af4cd634b8683.jpg)

### Tables

![29bccec55618b38d5f9a8279c996d739baa88b09f215491e0d5fdb63c3cf6e9a.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/tables/29bccec55618b38d5f9a8279c996d739baa88b09f215491e0d5fdb63c3cf6e9a.jpg)

![82025d843afe9c3f872268a2eae1ee98547ff40db429bc72ee710d3be67802a6.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/tables/82025d843afe9c3f872268a2eae1ee98547ff40db429bc72ee710d3be67802a6.jpg)

![8c3ee2cc946edb1d442106c41d23539d4647201b21c686e231125ae2a887ebaa.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/tables/8c3ee2cc946edb1d442106c41d23539d4647201b21c686e231125ae2a887ebaa.jpg)

![9de3dd7347cf516f23704600f660a5bd97a5953f99d589f9cbb791198e39d8f6.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/tables/9de3dd7347cf516f23704600f660a5bd97a5953f99d589f9cbb791198e39d8f6.jpg)

![a158570feee63677e5792541c4781e29172701d7c000c47b864f917a9c0e5b37.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/tables/a158570feee63677e5792541c4781e29172701d7c000c47b864f917a9c0e5b37.jpg)

![a674144f65dfa165d13adfdafee4f09bc5a286222b43c191a545594c130472bb.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/tables/a674144f65dfa165d13adfdafee4f09bc5a286222b43c191a545594c130472bb.jpg)

![ae83f7196c790616bd9631af7deade481a5a7e1a7cbe2ac344bbab09eb4c91b8.jpg](../nips_results/1864_SmartCache_%20Context-aware%20Semantic%20Cache%20for%20Efficient%20Multi-turn%20LLM%20Inference/tables/ae83f7196c790616bd9631af7deade481a5a7e1a7cbe2ac344bbab09eb4c91b8.jpg)

## Don't be lazy: CompleteP enables compute-efficient deep transformers


### Images

![051beafd6460ef30e1851b6a40310c76f7c6506df391c518249c8045d2eea546.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/051beafd6460ef30e1851b6a40310c76f7c6506df391c518249c8045d2eea546.jpg)

![0888a11b8b9804961ec8add899e8649a06411312b33f12bbf9c7e80ef27bfeb9.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/0888a11b8b9804961ec8add899e8649a06411312b33f12bbf9c7e80ef27bfeb9.jpg)

![0b78260c3c25893e6037e36c36a5a7ca188b12f081fc432cfde898a951f149cf.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/0b78260c3c25893e6037e36c36a5a7ca188b12f081fc432cfde898a951f149cf.jpg)

![16e22f120870a1106d7eb9e62430da57a0dfead8db9d6379ceb207dc67524fdf.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/16e22f120870a1106d7eb9e62430da57a0dfead8db9d6379ceb207dc67524fdf.jpg)

![1fdfa201a4b8f3ee57a06a73c6df845ca978610a91d457c5730646877ef796c8.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/1fdfa201a4b8f3ee57a06a73c6df845ca978610a91d457c5730646877ef796c8.jpg)

![215c9496b19fb0ecd53baaa5ce52504a1e573754b814683b244c3d671d3e3e7f.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/215c9496b19fb0ecd53baaa5ce52504a1e573754b814683b244c3d671d3e3e7f.jpg)

![5c7edc99e9ac26dd796dd16ed11625a96e682c7380d3ce584debc1036a1c19fb.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/5c7edc99e9ac26dd796dd16ed11625a96e682c7380d3ce584debc1036a1c19fb.jpg)

![733eabca83200edb0fcde5bcb98b77f39748d8b4e109377c434234b8e3ea2797.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/733eabca83200edb0fcde5bcb98b77f39748d8b4e109377c434234b8e3ea2797.jpg)

![a84209a2fd6c1e10b6c0ee3dc9f23c365c4cd066c38143d387fc7b5db743ec85.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/a84209a2fd6c1e10b6c0ee3dc9f23c365c4cd066c38143d387fc7b5db743ec85.jpg)

![ac4d08504e63d4d5df77826c0cc7b51611eb774454b43b076a0171bc8b54dc36.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/ac4d08504e63d4d5df77826c0cc7b51611eb774454b43b076a0171bc8b54dc36.jpg)

![ad26dbf771663bf3713a5b3f5d28f51dfe828c4e76fa812707d45aa405f22cc7.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/ad26dbf771663bf3713a5b3f5d28f51dfe828c4e76fa812707d45aa405f22cc7.jpg)

![b55aaf914d4492bdbe369c08860c26f361ef4a795ac2986efa446accb5db5b08.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/b55aaf914d4492bdbe369c08860c26f361ef4a795ac2986efa446accb5db5b08.jpg)

![f48b23cec4379fb07a6557f045fe976a735381f086a0908cb68b2d12f063039d.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/images/f48b23cec4379fb07a6557f045fe976a735381f086a0908cb68b2d12f063039d.jpg)

### Tables

![0931b46fea8cf4c36ad470df7657059a9db6a900507bf954c660e76afdb16880.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/tables/0931b46fea8cf4c36ad470df7657059a9db6a900507bf954c660e76afdb16880.jpg)

![55b1799b380f77633e6dc0990a75cf0dcf1684d4c7278c55bbc5a23c6e3d40f1.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/tables/55b1799b380f77633e6dc0990a75cf0dcf1684d4c7278c55bbc5a23c6e3d40f1.jpg)

![9bda6d8d2d993b8977fc096da15993c9ca49126444c82b6c8ed96b549d414cea.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/tables/9bda6d8d2d993b8977fc096da15993c9ca49126444c82b6c8ed96b549d414cea.jpg)

![a1cb83dae329764a260578bf17a9f47d35c453a0eee90a4a3ce79823abec11b9.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/tables/a1cb83dae329764a260578bf17a9f47d35c453a0eee90a4a3ce79823abec11b9.jpg)

![bea5e2402a4cd48db78c7193d92c586199da3acfaa3d8b7718fe8ed0f1a03ffc.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/tables/bea5e2402a4cd48db78c7193d92c586199da3acfaa3d8b7718fe8ed0f1a03ffc.jpg)

![ee4c17ef8baf3f3a368323d300244447f9c3da9736ff87c31f0e0fe7acd32eb7.jpg](../nips_results/1865_Don%27t%20be%20lazy_%20CompleteP%20enables%20compute-efficient%20deep%20transformers/tables/ee4c17ef8baf3f3a368323d300244447f9c3da9736ff87c31f0e0fe7acd32eb7.jpg)

## Approximating Shapley Explanations in Reinforcement Learning


### Images

![25c6179b99b239f5e5df3b922d5c1fc1035bd9d7771b8a1e2e6f646324411b61.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/images/25c6179b99b239f5e5df3b922d5c1fc1035bd9d7771b8a1e2e6f646324411b61.jpg)

![2d60f059b7dfddcd9fac6820e1a029227828d616a58c7a3908732291fe3ad594.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/images/2d60f059b7dfddcd9fac6820e1a029227828d616a58c7a3908732291fe3ad594.jpg)

![4bf171bccffb7925a0d93da0210df5609ba6ef383d4f094183b77bc375f2c1f9.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/images/4bf171bccffb7925a0d93da0210df5609ba6ef383d4f094183b77bc375f2c1f9.jpg)

![7af78ea2c792d3dee178f44b8201147ec8adc90b5cacc6a66148c28a9cb3dc38.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/images/7af78ea2c792d3dee178f44b8201147ec8adc90b5cacc6a66148c28a9cb3dc38.jpg)

![ce8cb53451a980a77c412dc342f5d58a357c5e65b08f155b2edb64606bb626ad.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/images/ce8cb53451a980a77c412dc342f5d58a357c5e65b08f155b2edb64606bb626ad.jpg)

![dff504ee8cf8ea6c3cf86c934fe34e74e0bb002d76c7b2fd15a1c9bfa2f8c565.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/images/dff504ee8cf8ea6c3cf86c934fe34e74e0bb002d76c7b2fd15a1c9bfa2f8c565.jpg)

![efb001d9bf02902abc34be0b24f0a33deba2546f65c6cb69604f0601afa5cee6.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/images/efb001d9bf02902abc34be0b24f0a33deba2546f65c6cb69604f0601afa5cee6.jpg)

![f018e3864aeb357ca6d6e7edeaca3e954705c6f34e57e29818b496797256155d.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/images/f018e3864aeb357ca6d6e7edeaca3e954705c6f34e57e29818b496797256155d.jpg)

![f23f2598df5537be408d89ad45976e969e1c372bc0460bc33ffe8dd9d1f6db69.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/images/f23f2598df5537be408d89ad45976e969e1c372bc0460bc33ffe8dd9d1f6db69.jpg)

![f549419650cb38a4dbd90a234dd7fc8ec6a714406b5f0be5c5544ab4ae9bfca2.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/images/f549419650cb38a4dbd90a234dd7fc8ec6a714406b5f0be5c5544ab4ae9bfca2.jpg)

![f7965ddbe7a40be722e97c93a9679d3e85f519ec26f7d50ec2fa1178ebe27067.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/images/f7965ddbe7a40be722e97c93a9679d3e85f519ec26f7d50ec2fa1178ebe27067.jpg)

### Tables

![98a89b0932f1294eb617dee60db0e0122a03706c39b30150f7fca425c7b96001.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/tables/98a89b0932f1294eb617dee60db0e0122a03706c39b30150f7fca425c7b96001.jpg)

![b8abadd27ed144ce8685a6885fa2e53317ca3d3b661461b6ece6f41da56c43b3.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/tables/b8abadd27ed144ce8685a6885fa2e53317ca3d3b661461b6ece6f41da56c43b3.jpg)

![bab1adc07f287cbc5cdc945e18756ffaa5e82c314d3e6411606f73fa5363745d.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/tables/bab1adc07f287cbc5cdc945e18756ffaa5e82c314d3e6411606f73fa5363745d.jpg)

![d9f1768af5d10720f07b9e326e02b306ff7daa9cb0cf1ae412d3a0f614700e3a.jpg](../nips_results/1866_Approximating%20Shapley%20Explanations%20in%20Reinforcement%20Learning/tables/d9f1768af5d10720f07b9e326e02b306ff7daa9cb0cf1ae412d3a0f614700e3a.jpg)

## HYPRL: Reinforcement Learning of Control Policies for Hyperproperties


### Images

![134cc018c11120db8676f55dc6d396d3820f2f8531a71b931a7e15c93649194e.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/134cc018c11120db8676f55dc6d396d3820f2f8531a71b931a7e15c93649194e.jpg)

![200dc754bedfb3706bb7a31ff6ed676ae83f3f522061fd0210b551219467ebf3.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/200dc754bedfb3706bb7a31ff6ed676ae83f3f522061fd0210b551219467ebf3.jpg)

![338c87da47254489f5ba01629edecb3ef20145f270b89b7eeeb0ac53c07dc21d.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/338c87da47254489f5ba01629edecb3ef20145f270b89b7eeeb0ac53c07dc21d.jpg)

![63603421725a71863c4dd3781bc335d0999b08e2fef9ef5d72d47454ae5859ca.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/63603421725a71863c4dd3781bc335d0999b08e2fef9ef5d72d47454ae5859ca.jpg)

![64a7e797e02ebae84cad5931c88a5c51702e516c71b85fb4b8d75a73213a344e.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/64a7e797e02ebae84cad5931c88a5c51702e516c71b85fb4b8d75a73213a344e.jpg)

![8d9f945a7ae5845bb6e1b374d8201ec11e64870085f0f04d26939d6b8dabf2fc.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/8d9f945a7ae5845bb6e1b374d8201ec11e64870085f0f04d26939d6b8dabf2fc.jpg)

![988e618eba6c47b1e0fec2e1de866f3d5192c4d0f8a02d5c12f392af18605760.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/988e618eba6c47b1e0fec2e1de866f3d5192c4d0f8a02d5c12f392af18605760.jpg)

![a464b1c581c9a99ac9c747623a9df9132564dac11ecfbb0e07a5b7c15c1043cd.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/a464b1c581c9a99ac9c747623a9df9132564dac11ecfbb0e07a5b7c15c1043cd.jpg)

![ae463b4f6f1ce3a73536abb17b27f3db1a740d953d35949c318edb7723175c40.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/ae463b4f6f1ce3a73536abb17b27f3db1a740d953d35949c318edb7723175c40.jpg)

![b01b927890b5fa41d2ee0ca32c729f249838df40ee088507ae4f9b95a417df04.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/b01b927890b5fa41d2ee0ca32c729f249838df40ee088507ae4f9b95a417df04.jpg)

![c96fc0d2bd4356c8b15874707f0bbfb152650da38487836e5143fb51e9c8dd22.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/c96fc0d2bd4356c8b15874707f0bbfb152650da38487836e5143fb51e9c8dd22.jpg)

![ed5d86578323b33c92d1e14b763a5b2d8b07cd597c34cd2d78302665ed4b9093.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/ed5d86578323b33c92d1e14b763a5b2d8b07cd597c34cd2d78302665ed4b9093.jpg)

![f01cae61a429e0995c8beafbf3f56c8e6a853e8e718a70e021f7ce6a77f52a50.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/images/f01cae61a429e0995c8beafbf3f56c8e6a853e8e718a70e021f7ce6a77f52a50.jpg)

### Tables

![121161b57e768ffc2b42627dbe38084cb401fa3393c1e8a624c49cc26448663e.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/tables/121161b57e768ffc2b42627dbe38084cb401fa3393c1e8a624c49cc26448663e.jpg)

![7954e4c2d57a0aa40a51304bc2226080315f2c2684a6c95015741517b500d052.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/tables/7954e4c2d57a0aa40a51304bc2226080315f2c2684a6c95015741517b500d052.jpg)

![90a4368aa0c7e30e209acaa302ea30ae5b4ecdba1e4509af21a2dbe06bd5234d.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/tables/90a4368aa0c7e30e209acaa302ea30ae5b4ecdba1e4509af21a2dbe06bd5234d.jpg)

![ad48e0834592140900b753e17a69b77df21a06181f4466ec066ab0ea87127dbe.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/tables/ad48e0834592140900b753e17a69b77df21a06181f4466ec066ab0ea87127dbe.jpg)

![c73f01e73e7c57e4038772a35480672ce491ea6ac332faed5c3675dc8b7cd62c.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/tables/c73f01e73e7c57e4038772a35480672ce491ea6ac332faed5c3675dc8b7cd62c.jpg)

![d460d16e70c036342336a6cbe1fd4a671542fe8e097bebf9893622474c3e87ca.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/tables/d460d16e70c036342336a6cbe1fd4a671542fe8e097bebf9893622474c3e87ca.jpg)

![e0f4082bf5a5b18a48f4912830ce0d29b1888cb374414937b43a54d2fea9870f.jpg](../nips_results/1867_HYPRL_%20Reinforcement%20Learning%20of%20Control%20Policies%20for%20Hyperproperties/tables/e0f4082bf5a5b18a48f4912830ce0d29b1888cb374414937b43a54d2fea9870f.jpg)

## Robust Hyperbolic Learning with Curvature-Aware Optimization


### Images

![17f3db95f3ccce5fd925f14e4c1bb914150846c27bbb4c477628a9d22ccf7c5c.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/images/17f3db95f3ccce5fd925f14e4c1bb914150846c27bbb4c477628a9d22ccf7c5c.jpg)

![912f7f6e991e990b6d042a1a91e70f468ab9e4b7a499c2d356acd7fa64d2fdcd.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/images/912f7f6e991e990b6d042a1a91e70f468ab9e4b7a499c2d356acd7fa64d2fdcd.jpg)

### Tables

![157421f95651741ae99316192599806d88bf3c6a9daf0016be4692c934355df6.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/tables/157421f95651741ae99316192599806d88bf3c6a9daf0016be4692c934355df6.jpg)

![2903d09beab3aed92d7de6d82de078b682b7a4ff60f8b5714ee4ebba034dc604.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/tables/2903d09beab3aed92d7de6d82de078b682b7a4ff60f8b5714ee4ebba034dc604.jpg)

![4c8f400557cf425e30cd940c026aefa64b62f626ba233823d167d0d71aebc20d.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/tables/4c8f400557cf425e30cd940c026aefa64b62f626ba233823d167d0d71aebc20d.jpg)

![4caf07e8bf7bd2dd259ec60e732d571e592f24a38580a204ff8e48e3e522db51.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/tables/4caf07e8bf7bd2dd259ec60e732d571e592f24a38580a204ff8e48e3e522db51.jpg)

![4fdfd838c11fb816e8c27c04087a50074a180b2ac13d229bfde77329f7b381bd.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/tables/4fdfd838c11fb816e8c27c04087a50074a180b2ac13d229bfde77329f7b381bd.jpg)

![7d8afb32292714484ea9ac0f3d2ad438880451790dd40ef5cfb8cbdc6b982043.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/tables/7d8afb32292714484ea9ac0f3d2ad438880451790dd40ef5cfb8cbdc6b982043.jpg)

![8d71ced6118728250ed29fe27400b45c5eac5c442ebc607e1d977d09b98cdd13.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/tables/8d71ced6118728250ed29fe27400b45c5eac5c442ebc607e1d977d09b98cdd13.jpg)

![b1d7c241a498218f98ee674f6d800707b0e2ba8fd1f7588c69b1132b2f97c1fd.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/tables/b1d7c241a498218f98ee674f6d800707b0e2ba8fd1f7588c69b1132b2f97c1fd.jpg)

![b4f1441d44e0c259b154d68689d104660b9ef0156a88c634ce2a8c76f7948964.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/tables/b4f1441d44e0c259b154d68689d104660b9ef0156a88c634ce2a8c76f7948964.jpg)

![f1478a23ab5969d623fc19d12e8d7eaac8cde465272cc522937bee11e58f393d.jpg](../nips_results/1868_Robust%20Hyperbolic%20Learning%20with%20Curvature-Aware%20Optimization/tables/f1478a23ab5969d623fc19d12e8d7eaac8cde465272cc522937bee11e58f393d.jpg)

## Wan-Move: Motion-controllable Video Generation via Latent Trajectory Guidance

### Images

![00f92c57ddcf0ab35398ebb03f400e0e19cf54dc2b294c83cf41b8d3a7ca0b61.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/00f92c57ddcf0ab35398ebb03f400e0e19cf54dc2b294c83cf41b8d3a7ca0b61.jpg)

![261e92f0f1793851038a28945ea9c6d5900ee59182759c2e34a0f4b42f573afe.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/261e92f0f1793851038a28945ea9c6d5900ee59182759c2e34a0f4b42f573afe.jpg)

![4551421d32d9576fdfd2aa517f2066e2725c522951b61928a7f9233ea3e79422.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/4551421d32d9576fdfd2aa517f2066e2725c522951b61928a7f9233ea3e79422.jpg)

![56333e56819c5c0cbb6b7f541b0da491bb4e2978609cdad08d3d51ef1654852a.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/56333e56819c5c0cbb6b7f541b0da491bb4e2978609cdad08d3d51ef1654852a.jpg)

![59d7ad216cc24e52912e89b4134f035c2061caf9a177801f4bc1eef57c5ecb78.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/59d7ad216cc24e52912e89b4134f035c2061caf9a177801f4bc1eef57c5ecb78.jpg)

![6162f74bf65e4f444127b23288588b0233142213edf69ecfedfba6f7efe77c7e.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/6162f74bf65e4f444127b23288588b0233142213edf69ecfedfba6f7efe77c7e.jpg)

![6e4a53208c99866a97bc1964fb70691f87b8fca70802489c3b171ded400b1371.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/6e4a53208c99866a97bc1964fb70691f87b8fca70802489c3b171ded400b1371.jpg)

![7d05262e831ad5679367f2ff526df0391c9c95077752c9dbf6a9b20d24c48784.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/7d05262e831ad5679367f2ff526df0391c9c95077752c9dbf6a9b20d24c48784.jpg)

![884741613c62fd118dac10183d3f5e52b08d8c8d69c20d7982756379dc4b3ce8.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/884741613c62fd118dac10183d3f5e52b08d8c8d69c20d7982756379dc4b3ce8.jpg)

![93bb357d99246496abcb360c0e084d11510dfa3c1479fe305249deb36b28bd78.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/93bb357d99246496abcb360c0e084d11510dfa3c1479fe305249deb36b28bd78.jpg)

![949cf53100817ceca7e7660084ed9c91c025eba9b989c03be95b5e53c36669bd.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/949cf53100817ceca7e7660084ed9c91c025eba9b989c03be95b5e53c36669bd.jpg)

![9f7896c043c9b634a390fd5e740069654b6b0ba1a6ed29a01794f842485b45f7.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/9f7896c043c9b634a390fd5e740069654b6b0ba1a6ed29a01794f842485b45f7.jpg)

![a244105b916655068ba3000effd39bbac65e0d341a3fc34d061fdf8b1945fa45.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/a244105b916655068ba3000effd39bbac65e0d341a3fc34d061fdf8b1945fa45.jpg)

![b8c2740373de40bce8febea6879f87784e19bed263eb3422843b420205735e4e.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/b8c2740373de40bce8febea6879f87784e19bed263eb3422843b420205735e4e.jpg)

![ba646725b806c981db7089f4c232adff285f466e0bbff261e6bc88a615035633.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/ba646725b806c981db7089f4c232adff285f466e0bbff261e6bc88a615035633.jpg)

![bf8566ab60947091051564ef009f9380c0b0352eaeaace337ff4f05a208287be.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/bf8566ab60947091051564ef009f9380c0b0352eaeaace337ff4f05a208287be.jpg)

![f11a474701a44644cd4bedff0ca1366d4dc325d546c806c8aa6c7eca55bad053.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/images/f11a474701a44644cd4bedff0ca1366d4dc325d546c806c8aa6c7eca55bad053.jpg)

### Tables

![26140f2b0654c5b15afd2cc4ea21d7945eb09f3bd9ce18031713285d213cfac0.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/26140f2b0654c5b15afd2cc4ea21d7945eb09f3bd9ce18031713285d213cfac0.jpg)

![31c883e88b49796aec578728b19d46c9ef3688b516ccc36e59bc537b0289730c.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/31c883e88b49796aec578728b19d46c9ef3688b516ccc36e59bc537b0289730c.jpg)

![3825c1c1cd004a806783035ccab5bf53836f1a23751abfceb2a2e41256e8f3b9.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/3825c1c1cd004a806783035ccab5bf53836f1a23751abfceb2a2e41256e8f3b9.jpg)

![4f59fbbe0139bad90ff24a333c21e43f6f3edc756dd6d3714f801dce74142ef8.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/4f59fbbe0139bad90ff24a333c21e43f6f3edc756dd6d3714f801dce74142ef8.jpg)

![68faf312bd193dcd372337abec5cb9e94a8a020943601bec94001964928efba7.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/68faf312bd193dcd372337abec5cb9e94a8a020943601bec94001964928efba7.jpg)

![6954846fa86c9d37ef4f5617a9939e6ec5c5d8eef8f7daf5cc7aec739f9630c5.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/6954846fa86c9d37ef4f5617a9939e6ec5c5d8eef8f7daf5cc7aec739f9630c5.jpg)

![833bfa9c5deb10bebae4d0f0d84e756b9f875f04a8a087fbe0ce1ef92589a400.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/833bfa9c5deb10bebae4d0f0d84e756b9f875f04a8a087fbe0ce1ef92589a400.jpg)

![9bc237720811ebe76d04e20d56d51b3ac1f8e53312db97a5f2335783acd56214.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/9bc237720811ebe76d04e20d56d51b3ac1f8e53312db97a5f2335783acd56214.jpg)

![a5b80afe771b0a99f0463bb7d582c342a76aa4c129be6e40f5debe4508d4a68b.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/a5b80afe771b0a99f0463bb7d582c342a76aa4c129be6e40f5debe4508d4a68b.jpg)

![b437b70b2bc0c9d70d88588e65f1d1337ada5c678742bc7c151252d255a74729.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/b437b70b2bc0c9d70d88588e65f1d1337ada5c678742bc7c151252d255a74729.jpg)

![b8d26808cbedb50abc04dd70754bdf4db2ffacb4d72e1c9ffbc87b1471694d09.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/b8d26808cbedb50abc04dd70754bdf4db2ffacb4d72e1c9ffbc87b1471694d09.jpg)

![cfc895a54f60554701f4e01a60df696dcd0431dba5e25710ad535dbce5e82b0e.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/cfc895a54f60554701f4e01a60df696dcd0431dba5e25710ad535dbce5e82b0e.jpg)

![f692d46f31ec249877b847d5be5cecf8d217abc479ccbeebc8c156b75634f31e.jpg](../nips_results/1869_Wan-Move_%20Motion-controllable%20Video%20Generation%20via%20Latent%20Trajectory%20Guidance/tables/f692d46f31ec249877b847d5be5cecf8d217abc479ccbeebc8c156b75634f31e.jpg)
