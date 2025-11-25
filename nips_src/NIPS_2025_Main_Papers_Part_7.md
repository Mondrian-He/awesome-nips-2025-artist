# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 7 of 130

## 目录 (Table of Contents)

1. [Wider or Deeper?  Scaling LLM Inference-Time Compute with Adaptive Branching Tree Search](#Wider-or-Deeper-Scaling-LLM-Inference-Time-Compute-with-Adaptive-Branching-Tree-Search)
2. [Gaussian Herding across Pens: An Optimal Transport Perspective on Global Gaussian Reduction for 3DGS](#Gaussian-Herding-across-Pens-An-Optimal-Transport-Perspective-on-Global-Gaussian-Reduction-for-3DGS)
3. [Repurposing Marigold for Zero-Shot Metric Depth Estimation via Defocus Blur Cues](#Repurposing-Marigold-for-Zero-Shot-Metric-Depth-Estimation-via-Defocus-Blur-Cues)
4. [EraseFlow: Learning Concept Erasure Policies via GFlowNet-Driven Alignment](#EraseFlow-Learning-Concept-Erasure-Policies-via-GFlowNet-Driven-Alignment)
5. [CAR-Flow: Condition-Aware Reparameterization Aligns Source and Target for Better Flow Matching](#CAR-Flow-Condition-Aware-Reparameterization-Aligns-Source-and-Target-for-Better-Flow-Matching)
6. [Debate or Vote: Which Yields Better Decisions in Multi-Agent Large Language Models?](#Debate-or-Vote-Which-Yields-Better-Decisions-in-Multi-Agent-Large-Language-Models)
7. [High-order Equivariant Flow Matching for Density Functional Theory Hamiltonian Prediction](#High-order-Equivariant-Flow-Matching-for-Density-Functional-Theory-Hamiltonian-Prediction)
8. [To Distill or Decide? Understanding the Algorithmic Trade-off in Partially Observable RL](#To-Distill-or-Decide-Understanding-the-Algorithmic-Trade-off-in-Partially-Observable-RL)
9. [Boosting Generative Image Modeling via Joint Image-Feature Synthesis](#Boosting-Generative-Image-Modeling-via-Joint-Image-Feature-Synthesis)
10. [Uni-LoRA: One Vector is All You Need](#Uni-LoRA-One-Vector-is-All-You-Need)
11. [SViMo: Synchronized Diffusion for Video and Motion Generation in Hand-object Interaction Scenarios](#SViMo-Synchronized-Diffusion-for-Video-and-Motion-Generation-in-Hand-object-Interaction-Scenarios)
12. [Optimal Nuisance Function Tuning for Estimating a Doubly Robust Functional under Proportional Asymptotics](#Optimal-Nuisance-Function-Tuning-for-Estimating-a-Doubly-Robust-Functional-under-Proportional-Asymptotics)
13. [Mitigating Instability in High Residual Adaptive Sampling for PINNs via Langevin Dynamics](#Mitigating-Instability-in-High-Residual-Adaptive-Sampling-for-PINNs-via-Langevin-Dynamics)
14. [Horizon Reduction Makes RL Scalable](#Horizon-Reduction-Makes-RL-Scalable)
15. [Reverse Engineering Human Preferences with Reinforcement Learning](#Reverse-Engineering-Human-Preferences-with-Reinforcement-Learning)
16. [Scaling can lead to compositional generalization](#Scaling-can-lead-to-compositional-generalization)
17. [On the Surprising Effectiveness of Large Learning Rates under Standard Width Scaling](#On-the-Surprising-Effectiveness-of-Large-Learning-Rates-under-Standard-Width-Scaling)
18. [Inference-Time Reward Hacking in Large Language Models](#Inference-Time-Reward-Hacking-in-Large-Language-Models)
19. [DICEPTION: A Generalist Diffusion Model for Visual Perceptual Tasks](#DICEPTION-A-Generalist-Diffusion-Model-for-Visual-Perceptual-Tasks)
20. [Nonlinear Laplacians: Tunable principal component analysis under directional prior information](#Nonlinear-Laplacians-Tunable-principal-component-analysis-under-directional-prior-information)
21. [PhysX-3D: Physical-Grounded 3D Asset Generation](#PhysX-3D-Physical-Grounded-3D-Asset-Generation)
22. [Self-Perturbed Anomaly-Aware Graph Dynamics for Multivariate Time-Series Anomaly Detection](#Self-Perturbed-Anomaly-Aware-Graph-Dynamics-for-Multivariate-Time-Series-Anomaly-Detection)
23. [Purifying Approximate Differential Privacy with Randomized Post-processing](#Purifying-Approximate-Differential-Privacy-with-Randomized-Post-processing)
24. [GraphMaster: Automated Graph Synthesis via LLM Agents in Data-Limited Environments](#GraphMaster-Automated-Graph-Synthesis-via-LLM-Agents-in-Data-Limited-Environments)
25. [Option-aware Temporally Abstracted Value for Offline Goal-Conditioned Reinforcement Learning](#Option-aware-Temporally-Abstracted-Value-for-Offline-Goal-Conditioned-Reinforcement-Learning)
26. [Sample-Adaptivity Tradeoff in On-Demand Sampling](#Sample-Adaptivity-Tradeoff-in-On-Demand-Sampling)
27. [FlowFeat: Pixel-Dense Embedding of Motion Profiles](#FlowFeat-Pixel-Dense-Embedding-of-Motion-Profiles)
28. [Non-Clairvoyant Scheduling with Progress Bars](#Non-Clairvoyant-Scheduling-with-Progress-Bars)
29. [KLASS: KL-Guided Fast Inference in Masked Diffusion Models](#KLASS-KL-Guided-Fast-Inference-in-Masked-Diffusion-Models)
30. [TokenSwap: A Lightweight Method to Disrupt Memorized Sequences in LLMs](#TokenSwap-A-Lightweight-Method-to-Disrupt-Memorized-Sequences-in-LLMs)
31. [Learnable Sampler Distillation for Discrete Diffusion Models](#Learnable-Sampler-Distillation-for-Discrete-Diffusion-Models)
32. [Flash Invariant Point Attention](#Flash-Invariant-Point-Attention)
33. [The World Is Bigger: A Computationally-Embedded Perspective on the Big World Hypothesis](#The-World-Is-Bigger-A-Computationally-Embedded-Perspective-on-the-Big-World-Hypothesis)
34. [Exploration via Feature Perturbation in Contextual Bandits](#Exploration-via-Feature-Perturbation-in-Contextual-Bandits)
35. [URDF-Anything: Constructing Articulated Objects with 3D Multimodal Language Model](#URDF-Anything-Constructing-Articulated-Objects-with-3D-Multimodal-Language-Model)
36. [Transfer Faster, Price Smarter: Minimax Dynamic Pricing under Cross-Market Preference Shift](#Transfer-Faster-Price-Smarter-Minimax-Dynamic-Pricing-under-Cross-Market-Preference-Shift)
37. [Cloud4D: Estimating Cloud Properties at a High Spatial and Temporal Resolution](#Cloud4D-Estimating-Cloud-Properties-at-a-High-Spatial-and-Temporal-Resolution)
38. [Talk2Event: Grounded Understanding of Dynamic Scenes from Event Cameras](#Talk2Event-Grounded-Understanding-of-Dynamic-Scenes-from-Event-Cameras)
39. [Enigmata:  Scaling Logical Reasoning in Large Language Models with Synthetic Verifiable Puzzles](#Enigmata-Scaling-Logical-Reasoning-in-Large-Language-Models-with-Synthetic-Verifiable-Puzzles)
40. [When Less Language is More: Language-Reasoning Disentanglement Makes LLMs Better Multilingual Reasoners](#When-Less-Language-is-More-Language-Reasoning-Disentanglement-Makes-LLMs-Better-Multilingual-Reasoners)
41. [Repo2Run: Automated Building Executable Environment for Code Repository at Scale](#Repo2Run-Automated-Building-Executable-Environment-for-Code-Repository-at-Scale)

---


## Wider or Deeper?  Scaling LLM Inference-Time Compute with Adaptive Branching Tree Search

### Images

![08cb952d470cccfedafd744a391a3ef3763b930447a1f5bfc7658af879df9f50.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/images/08cb952d470cccfedafd744a391a3ef3763b930447a1f5bfc7658af879df9f50.jpg)

![54d0deea074b8b91e5563115be5789f534b240be086986e08f235cc932bed9c9.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/images/54d0deea074b8b91e5563115be5789f534b240be086986e08f235cc932bed9c9.jpg)

![7dbda3e63b2981306c36f41bd2bf093d2495d7b9a564c79cf1cdaf16e279920b.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/images/7dbda3e63b2981306c36f41bd2bf093d2495d7b9a564c79cf1cdaf16e279920b.jpg)

![8c062a2eb6e2cf68efea9ba844f05f9bb4be6c27bdfddf47e40a8bfb4637b89b.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/images/8c062a2eb6e2cf68efea9ba844f05f9bb4be6c27bdfddf47e40a8bfb4637b89b.jpg)

![9789ac61b1f950472acb32665253bc242a43936827a99c25381c4970a51d2157.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/images/9789ac61b1f950472acb32665253bc242a43936827a99c25381c4970a51d2157.jpg)

![ad61192bc91724f9b4cb5d0b29800a39166618ce400d839f6f3d6f4b3c198cce.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/images/ad61192bc91724f9b4cb5d0b29800a39166618ce400d839f6f3d6f4b3c198cce.jpg)

![add93dd5d8085d0c31ecdbdc7e05fa955c48a2a352691f1c7948b1323a4283a6.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/images/add93dd5d8085d0c31ecdbdc7e05fa955c48a2a352691f1c7948b1323a4283a6.jpg)

![cefd0574e9d70734ad7f08d6dc2e3715fe7d8bb197a7f7dea2f7a16fe7ab6e2c.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/images/cefd0574e9d70734ad7f08d6dc2e3715fe7d8bb197a7f7dea2f7a16fe7ab6e2c.jpg)

![d1cdbb194e3d687679f04792764b57f29e6d93a835bd2f316d69c3a50bb916e6.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/images/d1cdbb194e3d687679f04792764b57f29e6d93a835bd2f316d69c3a50bb916e6.jpg)

### Tables

![26174e058cbf05770c31d818cb0a563f35185343efcdf3ffcb0fbf8de7f7f06a.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/26174e058cbf05770c31d818cb0a563f35185343efcdf3ffcb0fbf8de7f7f06a.jpg)

![3de69e6ac793152466e5c83c57b59cc9f4693c9b016b017f37cb2e472c2ccdad.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/3de69e6ac793152466e5c83c57b59cc9f4693c9b016b017f37cb2e472c2ccdad.jpg)

![45e392e213740c35043e34023e003372b13906b3576178ee571d429168ab879a.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/45e392e213740c35043e34023e003372b13906b3576178ee571d429168ab879a.jpg)

![5d743c0b08e3c011caf74755e655a737fcb11e6498c1f92cea353268ccf25663.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/5d743c0b08e3c011caf74755e655a737fcb11e6498c1f92cea353268ccf25663.jpg)

![720b1337a40dc21f1f6100700722fff99ce2e614107022c14f9c52c7579c5fd7.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/720b1337a40dc21f1f6100700722fff99ce2e614107022c14f9c52c7579c5fd7.jpg)

![7478493addc4ec896b2fa7af07464787d048bfde5bff9af2385688188a4c4d0e.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/7478493addc4ec896b2fa7af07464787d048bfde5bff9af2385688188a4c4d0e.jpg)

![7e2bca4931b64191f448b6b804bf5c7e297b19a446e4d451c6a38ba8d288f498.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/7e2bca4931b64191f448b6b804bf5c7e297b19a446e4d451c6a38ba8d288f498.jpg)

![864d2a5fe2539a0f31e767dd3d45789f31fe4a4756bb77e97f61b48fe5fbdf91.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/864d2a5fe2539a0f31e767dd3d45789f31fe4a4756bb77e97f61b48fe5fbdf91.jpg)

![9261b6250171c24a98cc1637e7a0ed8de5fb93e19ff94c5c1c777a9c2cf955be.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/9261b6250171c24a98cc1637e7a0ed8de5fb93e19ff94c5c1c777a9c2cf955be.jpg)

![a2c124eee0a41082371bb38ee600a8c937f63427322018e270b71bac45c5d662.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/a2c124eee0a41082371bb38ee600a8c937f63427322018e270b71bac45c5d662.jpg)

![b283d663b76461ee5952d393ce36ce3c3189bd30e3b717fe2940fb0ef867ae3d.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/b283d663b76461ee5952d393ce36ce3c3189bd30e3b717fe2940fb0ef867ae3d.jpg)

![c1d236a81112b9598d8e044b701a948a82284f86a2a26f7d8119c18ceb15ddde.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/c1d236a81112b9598d8e044b701a948a82284f86a2a26f7d8119c18ceb15ddde.jpg)

![d1eb7d5d04d6d63184e326806b5a006d283755e24abd90c6a978636b8430b715.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/d1eb7d5d04d6d63184e326806b5a006d283755e24abd90c6a978636b8430b715.jpg)

![d4978a51a352f2cb77bcb608fb59f5f92c615bdfefc78caa73a446bc697bad81.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/d4978a51a352f2cb77bcb608fb59f5f92c615bdfefc78caa73a446bc697bad81.jpg)

![d4ae58c20a89a7bd188edc9a174f5464ab8640ba459be5a3cc5234bd2b7c5a53.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/d4ae58c20a89a7bd188edc9a174f5464ab8640ba459be5a3cc5234bd2b7c5a53.jpg)

![d7fc7403d74429ce85c1dc120139562d08f98fe43a94d9856f80225806683a8e.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/d7fc7403d74429ce85c1dc120139562d08f98fe43a94d9856f80225806683a8e.jpg)

![ffa8e76d456db91209e5c9a4ebaebfab7426aaf7ce57479a44b53c153f0ecd66.jpg](../nips_results/253_Robust%20Neural%20Rendering%20in%20the%20Wild%20with%20Asymmetric%20Dual%203D%20Gaussian%20Splatting/tables/ffa8e76d456db91209e5c9a4ebaebfab7426aaf7ce57479a44b53c153f0ecd66.jpg)

## Wider or Deeper?  Scaling LLM Inference-Time Compute with Adaptive Branching Tree Search


### Images

![01b604be550658bdb417ca1cd6af4809cc25f201a3e47e631e63576688a6b283.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/01b604be550658bdb417ca1cd6af4809cc25f201a3e47e631e63576688a6b283.jpg)

![04747cb903e45dc5a09cc21e3b87c506f99fc048cc0dac24b48361d38b0beab3.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/04747cb903e45dc5a09cc21e3b87c506f99fc048cc0dac24b48361d38b0beab3.jpg)

![17d467d503e5c3f6bc86db29895d0a37d6ae92bf7088fe03fb44319cd55ba5d5.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/17d467d503e5c3f6bc86db29895d0a37d6ae92bf7088fe03fb44319cd55ba5d5.jpg)

![1bd7aedc1eb1f8356e16736aceb91a5bc264e008be8c12bd1021408f5d723cef.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/1bd7aedc1eb1f8356e16736aceb91a5bc264e008be8c12bd1021408f5d723cef.jpg)

![260d6f90289433cf8913ff6707cf6e0e878af7d33a58125bf52913eedad353e9.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/260d6f90289433cf8913ff6707cf6e0e878af7d33a58125bf52913eedad353e9.jpg)

![3cd791d41d1f5afa1e0d5e657396595f40ae5d455c1beae089eac5e4dc7a46fb.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/3cd791d41d1f5afa1e0d5e657396595f40ae5d455c1beae089eac5e4dc7a46fb.jpg)

![436e36246020ea41a347348a5a1b46c8dfe8183273201c8b6dd96521c6dfda16.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/436e36246020ea41a347348a5a1b46c8dfe8183273201c8b6dd96521c6dfda16.jpg)

![720a33b2be9066e2b7718a5a820e35a81b76947e792d7df6883ac98bfdb55b7c.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/720a33b2be9066e2b7718a5a820e35a81b76947e792d7df6883ac98bfdb55b7c.jpg)

![826608e081f0ed4cdd7eac331a071e9e17e44289ccd309aca42793ac8ca5121c.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/826608e081f0ed4cdd7eac331a071e9e17e44289ccd309aca42793ac8ca5121c.jpg)

![a189b7dc620029d762ee501f4bb5c2ba70d57d2d7bb6c1709f7d690ee19ef6e9.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/a189b7dc620029d762ee501f4bb5c2ba70d57d2d7bb6c1709f7d690ee19ef6e9.jpg)

![a29859e691a562e67129e90eba41e9f7c493463f45b92a5da04bed3026db06a4.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/a29859e691a562e67129e90eba41e9f7c493463f45b92a5da04bed3026db06a4.jpg)

![acbb3213225f7ec1fca8578e265c2b75a4f12867f15c951f95b10994c57a0753.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/acbb3213225f7ec1fca8578e265c2b75a4f12867f15c951f95b10994c57a0753.jpg)

![acd254fb52f03954f76b9b774403858bf069e8addecdb7f692085daed625a6c1.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/acd254fb52f03954f76b9b774403858bf069e8addecdb7f692085daed625a6c1.jpg)

![bacb8673b5f1cce683814b9b71cb7b68e770e4b22da32f942f2fdf74af0092d3.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/bacb8673b5f1cce683814b9b71cb7b68e770e4b22da32f942f2fdf74af0092d3.jpg)

![bd5e8b10f0cac913e8382c9d7faecbef793d0e6c234835405a6f4f15139298a8.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/bd5e8b10f0cac913e8382c9d7faecbef793d0e6c234835405a6f4f15139298a8.jpg)

![be186946cc12e78d4ce841e16e2f910aba3c68071d49baaf462d47a500b4b928.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/be186946cc12e78d4ce841e16e2f910aba3c68071d49baaf462d47a500b4b928.jpg)

![c33b1c337a51d9f5cdad5744cf999f6502fda1b453c440ee519aaaf44b36a281.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/c33b1c337a51d9f5cdad5744cf999f6502fda1b453c440ee519aaaf44b36a281.jpg)

![d2f566a9a0b708cc9d6fee0b9678544a9c9aa2b515a62320326adfe11882312f.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/d2f566a9a0b708cc9d6fee0b9678544a9c9aa2b515a62320326adfe11882312f.jpg)

![f511d3f1f21d664c196e5854d66d935d4438213112948fe3320be9273a56ce6e.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/images/f511d3f1f21d664c196e5854d66d935d4438213112948fe3320be9273a56ce6e.jpg)

### Tables

![2fe54a61d995a0754f36e36a79e46915453f9515df8fd151bbe57245731dbbee.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/tables/2fe54a61d995a0754f36e36a79e46915453f9515df8fd151bbe57245731dbbee.jpg)

![4de1c2b0d67a9366989ed6851259381a63e51501cbe0986789cf37f40f3106a5.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/tables/4de1c2b0d67a9366989ed6851259381a63e51501cbe0986789cf37f40f3106a5.jpg)

![51705f886407ad4892fcdd2d2a97dcb0000f264ca89b859d1e1bb801e56eb262.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/tables/51705f886407ad4892fcdd2d2a97dcb0000f264ca89b859d1e1bb801e56eb262.jpg)

![6589f902c2693444d4c87d6d1cb164e3fcf8b8730811de03759b0a13f96bc326.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/tables/6589f902c2693444d4c87d6d1cb164e3fcf8b8730811de03759b0a13f96bc326.jpg)

![7b972f3a0a7bee688b5be09a9efdac9d5d685f814331790fc3669f14346b7379.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/tables/7b972f3a0a7bee688b5be09a9efdac9d5d685f814331790fc3669f14346b7379.jpg)

![ef530671d609fd025fcf4f1ab26fd211c20570e308990292f90a8826d45ebb52.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/tables/ef530671d609fd025fcf4f1ab26fd211c20570e308990292f90a8826d45ebb52.jpg)

![f1116d0eeed14c84422ea98da0339f2d7f25fcd7b9fdb06a59cbeb3ab32725d2.jpg](../nips_results/254_Wider%20or%20Deeper_%20%20Scaling%20LLM%20Inference-Time%20Compute%20with%20Adaptive%20Branching%20Tree%20Search/tables/f1116d0eeed14c84422ea98da0339f2d7f25fcd7b9fdb06a59cbeb3ab32725d2.jpg)

## Gaussian Herding across Pens: An Optimal Transport Perspective on Global Gaussian Reduction for 3DGS


### Images

![1a6e7cfc9dd3199c322cb34cde4db543659a121a9e7a93bb24ab3cca91e2c0eb.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/images/1a6e7cfc9dd3199c322cb34cde4db543659a121a9e7a93bb24ab3cca91e2c0eb.jpg)

![379f2b058b1e27249e5aa289f4ea6d7edcb709c8ef36ea49f6fafe70b3e37116.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/images/379f2b058b1e27249e5aa289f4ea6d7edcb709c8ef36ea49f6fafe70b3e37116.jpg)

![6205f04f620b15fe10ac20793371ef9cf041089a57fd728c95fb9ac9227e16ab.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/images/6205f04f620b15fe10ac20793371ef9cf041089a57fd728c95fb9ac9227e16ab.jpg)

![664416c23f2ae1ed87130a375a4b8bfebad305e53b8aa258d63cfc9670c1c960.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/images/664416c23f2ae1ed87130a375a4b8bfebad305e53b8aa258d63cfc9670c1c960.jpg)

![809999b7e8616e629cca34d93bc7b8b75ecba188172a3aae71532d5f8da49a7f.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/images/809999b7e8616e629cca34d93bc7b8b75ecba188172a3aae71532d5f8da49a7f.jpg)

![9118fbbdb9c8fece46af07af7e779c5dbfe9e4953ed7340d645865b12d570264.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/images/9118fbbdb9c8fece46af07af7e779c5dbfe9e4953ed7340d645865b12d570264.jpg)

![d98767232a5b02a728b73591a158a8c938d588cae135bde4b2155a8e7fcc95d9.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/images/d98767232a5b02a728b73591a158a8c938d588cae135bde4b2155a8e7fcc95d9.jpg)

![fe50fc2a0a4c87f5ab0b19f4875d44b363709dfaf4f7a176f0f681b897fe6c8f.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/images/fe50fc2a0a4c87f5ab0b19f4875d44b363709dfaf4f7a176f0f681b897fe6c8f.jpg)

### Tables

![3f77ad2880545e55565ccb7923cec6389f504bf785d0546f9fc694af09ba3a2b.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/tables/3f77ad2880545e55565ccb7923cec6389f504bf785d0546f9fc694af09ba3a2b.jpg)

![5baa829239bd87a8b18ca3f852f127ad10583460c12260630858cdabcdf79abf.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/tables/5baa829239bd87a8b18ca3f852f127ad10583460c12260630858cdabcdf79abf.jpg)

![7e4983bafca73a306d143501ce7b44500c75724764eccd2941bf4595fff837dc.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/tables/7e4983bafca73a306d143501ce7b44500c75724764eccd2941bf4595fff837dc.jpg)

![aa5204934e8a2ca2e182f3e9ab440bfebee88a2230b25a9862d6e2e680f4db35.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/tables/aa5204934e8a2ca2e182f3e9ab440bfebee88a2230b25a9862d6e2e680f4db35.jpg)

![d07f2024cf9c5a9640bd4563801dc44f3f89e5fa0d22aff5a479c6559c4ac00e.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/tables/d07f2024cf9c5a9640bd4563801dc44f3f89e5fa0d22aff5a479c6559c4ac00e.jpg)

![db5ce91cfe8cbeb37197d57f5da678126c03102cfad9240988611d414549e251.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/tables/db5ce91cfe8cbeb37197d57f5da678126c03102cfad9240988611d414549e251.jpg)

![f4a7acbcd33b055105ab3ca099e9564b189e0d287c3d8e5cd5e0effeb5378204.jpg](../nips_results/255_Gaussian%20Herding%20across%20Pens_%20An%20Optimal%20Transport%20Perspective%20on%20Global%20Gaussian%20Reduction%20for%203DGS/tables/f4a7acbcd33b055105ab3ca099e9564b189e0d287c3d8e5cd5e0effeb5378204.jpg)

## Repurposing Marigold for Zero-Shot Metric Depth Estimation via Defocus Blur Cues


### Images

![2a91183ca8c8859004c649dc77a56570d7ee8bb548bf3b3a22ca459558594da5.jpg](../nips_results/256_Repurposing%20Marigold%20for%20Zero-Shot%20Metric%20Depth%20Estimation%20via%20Defocus%20Blur%20Cues/images/2a91183ca8c8859004c649dc77a56570d7ee8bb548bf3b3a22ca459558594da5.jpg)

![4b90cbca50288946018c080d1b5609074533081e44d8e9dd2aebdd0c9f68af59.jpg](../nips_results/256_Repurposing%20Marigold%20for%20Zero-Shot%20Metric%20Depth%20Estimation%20via%20Defocus%20Blur%20Cues/images/4b90cbca50288946018c080d1b5609074533081e44d8e9dd2aebdd0c9f68af59.jpg)

![72e5079580894673fd0d7fcd4086facec3c50f1d30bef35c1b0495716881695a.jpg](../nips_results/256_Repurposing%20Marigold%20for%20Zero-Shot%20Metric%20Depth%20Estimation%20via%20Defocus%20Blur%20Cues/images/72e5079580894673fd0d7fcd4086facec3c50f1d30bef35c1b0495716881695a.jpg)

![bc584f3173db8cfff096771175b1b0a459ca630efa6e98ddd186cb56f8bf0eea.jpg](../nips_results/256_Repurposing%20Marigold%20for%20Zero-Shot%20Metric%20Depth%20Estimation%20via%20Defocus%20Blur%20Cues/images/bc584f3173db8cfff096771175b1b0a459ca630efa6e98ddd186cb56f8bf0eea.jpg)

![c845467e107edbba1520fedf5a263c0af67fb15017275726e14f8b5b1dcff0f0.jpg](../nips_results/256_Repurposing%20Marigold%20for%20Zero-Shot%20Metric%20Depth%20Estimation%20via%20Defocus%20Blur%20Cues/images/c845467e107edbba1520fedf5a263c0af67fb15017275726e14f8b5b1dcff0f0.jpg)

![dca6740bd5f26971df273abf103ea86364af02d9c7e3083288b8155050612571.jpg](../nips_results/256_Repurposing%20Marigold%20for%20Zero-Shot%20Metric%20Depth%20Estimation%20via%20Defocus%20Blur%20Cues/images/dca6740bd5f26971df273abf103ea86364af02d9c7e3083288b8155050612571.jpg)

### Tables

![4c096b496df79dc64b013ac36781d0aaafdbfc640ab721f05402c870498d11c6.jpg](../nips_results/256_Repurposing%20Marigold%20for%20Zero-Shot%20Metric%20Depth%20Estimation%20via%20Defocus%20Blur%20Cues/tables/4c096b496df79dc64b013ac36781d0aaafdbfc640ab721f05402c870498d11c6.jpg)

![5bf9fb40d61d1749c4a064a1c5387253282c2b295cb85485983f4623148523b4.jpg](../nips_results/256_Repurposing%20Marigold%20for%20Zero-Shot%20Metric%20Depth%20Estimation%20via%20Defocus%20Blur%20Cues/tables/5bf9fb40d61d1749c4a064a1c5387253282c2b295cb85485983f4623148523b4.jpg)

![92ea1ee78e8dded6a10437caa88b4ecbcf63d7fc230cd5f235593cdc79a6bc8b.jpg](../nips_results/256_Repurposing%20Marigold%20for%20Zero-Shot%20Metric%20Depth%20Estimation%20via%20Defocus%20Blur%20Cues/tables/92ea1ee78e8dded6a10437caa88b4ecbcf63d7fc230cd5f235593cdc79a6bc8b.jpg)

## EraseFlow: Learning Concept Erasure Policies via GFlowNet-Driven Alignment


### Images

![0d45568f8d1d3e01ecd882bfedbb8bcff9c767a6b2db78dbc688be8f3431fc06.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/0d45568f8d1d3e01ecd882bfedbb8bcff9c767a6b2db78dbc688be8f3431fc06.jpg)

![126b5b7311c83e03b9b00f3fccbfc5c0fd968753cef15055e3eb57f97806f98c.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/126b5b7311c83e03b9b00f3fccbfc5c0fd968753cef15055e3eb57f97806f98c.jpg)

![13794ed85195bc56b4de65a280eaaaf5fe083e39f46fab84f6ec36599203edac.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/13794ed85195bc56b4de65a280eaaaf5fe083e39f46fab84f6ec36599203edac.jpg)

![162687e9269e0da5c57b13a50be60549157ee9d1ac2f3b4ea670061b9bfd3036.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/162687e9269e0da5c57b13a50be60549157ee9d1ac2f3b4ea670061b9bfd3036.jpg)

![375fa79649a47f4c1b09289ba73dcd9210612502b7d5cabe6a46b06cf455cc60.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/375fa79649a47f4c1b09289ba73dcd9210612502b7d5cabe6a46b06cf455cc60.jpg)

![4b0fe0819257eb03ebf0ce24e1ceea114bd7dfc8d195257b001cb0f56dcbab95.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/4b0fe0819257eb03ebf0ce24e1ceea114bd7dfc8d195257b001cb0f56dcbab95.jpg)

![72a94234418fc013a3e257fec3ace40f41fbaf0c8d8ff261a03758b7d4b3db40.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/72a94234418fc013a3e257fec3ace40f41fbaf0c8d8ff261a03758b7d4b3db40.jpg)

![77accecf0a80dd5467f3c6dfc12e5082c23f7f0f896178bab0440d0e958c54b8.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/77accecf0a80dd5467f3c6dfc12e5082c23f7f0f896178bab0440d0e958c54b8.jpg)

![7862f87873422b68aec5a4b841d2f142ca85d06f6093389820d9f48a18092ec8.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/7862f87873422b68aec5a4b841d2f142ca85d06f6093389820d9f48a18092ec8.jpg)

![7f40d47bb23d786d9808ccb41bfe4485fcaeedb0beb0b832ac37eeb8130ef1f0.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/7f40d47bb23d786d9808ccb41bfe4485fcaeedb0beb0b832ac37eeb8130ef1f0.jpg)

![9b79345fdf168b9986ea8e4c0cb8e141eb69495ac069a3ea2ce2e49279a0da91.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/9b79345fdf168b9986ea8e4c0cb8e141eb69495ac069a3ea2ce2e49279a0da91.jpg)

![abb5ebc5659dac1bb7ef438af5877151cba94b28f187c091022f9b5c49e8e4d7.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/abb5ebc5659dac1bb7ef438af5877151cba94b28f187c091022f9b5c49e8e4d7.jpg)

![b844a545ef9c0f469a5ae041bc4c21e29ae8a6f5846ee133f4998aacc5e77c5e.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/b844a545ef9c0f469a5ae041bc4c21e29ae8a6f5846ee133f4998aacc5e77c5e.jpg)

![e6d1b7ff84cb4f7785a8f13eb41e6d0c55609155b4b90151a7704c30e9ac69dd.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/e6d1b7ff84cb4f7785a8f13eb41e6d0c55609155b4b90151a7704c30e9ac69dd.jpg)

![e800408369f9527f0d1765dcb4eea59d7c03efd89737d3a4b82b0be9c3f2c228.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/e800408369f9527f0d1765dcb4eea59d7c03efd89737d3a4b82b0be9c3f2c228.jpg)

![ed1a2fc28584ea5d9e4016b211a76c1c0b83dc2bd6e384e116c81bc24d039899.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/images/ed1a2fc28584ea5d9e4016b211a76c1c0b83dc2bd6e384e116c81bc24d039899.jpg)

### Tables

![1ad5ac2698a79265a110c3cb0e53a57900a0147b092adc562deffd45be22c264.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/1ad5ac2698a79265a110c3cb0e53a57900a0147b092adc562deffd45be22c264.jpg)

![1ba8cd99dc1bd7d23eacd42329339643d22106b6ba10256cf4b7f8944ef85cf7.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/1ba8cd99dc1bd7d23eacd42329339643d22106b6ba10256cf4b7f8944ef85cf7.jpg)

![2187c207393a4042af315fe7c92162253c819cca0acc9e95fbf2d21f527ab80a.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/2187c207393a4042af315fe7c92162253c819cca0acc9e95fbf2d21f527ab80a.jpg)

![21f89229a44e9bbb62fd584d9d86172d114bf0607fc6fbe76baef6d977d6a233.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/21f89229a44e9bbb62fd584d9d86172d114bf0607fc6fbe76baef6d977d6a233.jpg)

![29dc1809ff7fb916684e9e399c7ab2b34f3c8c4ebdbeb674a6f2533d3af0757c.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/29dc1809ff7fb916684e9e399c7ab2b34f3c8c4ebdbeb674a6f2533d3af0757c.jpg)

![3c4b9ad151e422af62e5b3c16442e5507387fb649128890981d51ab89ddac7f7.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/3c4b9ad151e422af62e5b3c16442e5507387fb649128890981d51ab89ddac7f7.jpg)

![55f94c8ecdda82a425e7bc8b5c8677b88b8db0a9e9f1f8872b9f092cf06662af.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/55f94c8ecdda82a425e7bc8b5c8677b88b8db0a9e9f1f8872b9f092cf06662af.jpg)

![57ef5a2fd7df807ffd3193f2e397c959be4404b38758d9a7a9375c2b113b7b13.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/57ef5a2fd7df807ffd3193f2e397c959be4404b38758d9a7a9375c2b113b7b13.jpg)

![70c90b09397a0e64cfa4cc4e9ab40dd661eac10d7ae9ee6dc4fb6bd9fda6a1bb.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/70c90b09397a0e64cfa4cc4e9ab40dd661eac10d7ae9ee6dc4fb6bd9fda6a1bb.jpg)

![7c18cfbec4d3480bdb4df8bd57fbd45c840356bb725c9cb841027d145ca8fb10.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/7c18cfbec4d3480bdb4df8bd57fbd45c840356bb725c9cb841027d145ca8fb10.jpg)

![9a4b9194570f6014216829536ea97ce45f4f445567ca62a355e9e83b389c4857.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/9a4b9194570f6014216829536ea97ce45f4f445567ca62a355e9e83b389c4857.jpg)

![adf2a6f5876f1fa545ec3ba557f0019d59dba6fd796b988f23d2f612f630fe95.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/adf2a6f5876f1fa545ec3ba557f0019d59dba6fd796b988f23d2f612f630fe95.jpg)

![d187b3afbd855dc4eed4edba56ad5f57c7bad86379e0110929bc3e9ef28ec49c.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/d187b3afbd855dc4eed4edba56ad5f57c7bad86379e0110929bc3e9ef28ec49c.jpg)

![f16698c7024b3344a6535941eb42ed701887d977a22de61eeb6fb021f5f14647.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/f16698c7024b3344a6535941eb42ed701887d977a22de61eeb6fb021f5f14647.jpg)

![fab69839303757d1245042badcb87a549f9bbe8d9f40b77b3109b3e190682aaa.jpg](../nips_results/257_EraseFlow_%20Learning%20Concept%20Erasure%20Policies%20via%20GFlowNet-Driven%20Alignment/tables/fab69839303757d1245042badcb87a549f9bbe8d9f40b77b3109b3e190682aaa.jpg)

## CAR-Flow: Condition-Aware Reparameterization Aligns Source and Target for Better Flow Matching


### Images

![079edd74cf162bfa18213673a45c8326ca248495e289a699197bb1177afffd53.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/images/079edd74cf162bfa18213673a45c8326ca248495e289a699197bb1177afffd53.jpg)

![165a363929f522c234f14c69e9f9a19966b9b3ddb8933681b2c8426fa9cd14f8.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/images/165a363929f522c234f14c69e9f9a19966b9b3ddb8933681b2c8426fa9cd14f8.jpg)

![169b0ab89a865ab3899a5d3cc2a6e19a37d141d5a9328db34ee638e87c995989.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/images/169b0ab89a865ab3899a5d3cc2a6e19a37d141d5a9328db34ee638e87c995989.jpg)

![1ed2ea0582eed335a5b54e9eba0390f53ebdaba72696fdedd792f8c77b4f1eae.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/images/1ed2ea0582eed335a5b54e9eba0390f53ebdaba72696fdedd792f8c77b4f1eae.jpg)

![7048ad803d5152c9f2ed6a7d80e682aa0b9771339db88a1da4b15c9f98338b42.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/images/7048ad803d5152c9f2ed6a7d80e682aa0b9771339db88a1da4b15c9f98338b42.jpg)

![902a8afffd20481abb644ac72f46d180930857f0fd16263a36ec90c3312865cd.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/images/902a8afffd20481abb644ac72f46d180930857f0fd16263a36ec90c3312865cd.jpg)

![ab0da50d60c9e653a33e766bd01dc87172477524e5bfb6eaad2d2fe534215bed.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/images/ab0da50d60c9e653a33e766bd01dc87172477524e5bfb6eaad2d2fe534215bed.jpg)

![b25373cdd6ef005d37a28b0d0f3ebc1797b32e7ca1ae90895e5a466b059f621a.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/images/b25373cdd6ef005d37a28b0d0f3ebc1797b32e7ca1ae90895e5a466b059f621a.jpg)

![d7533cba75579dffdd422a0afbd85a5d7cd0774c4b72b451e5752ecc7ce01a1c.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/images/d7533cba75579dffdd422a0afbd85a5d7cd0774c4b72b451e5752ecc7ce01a1c.jpg)

### Tables

![3d8eaf2fccef3ce19e815baa325827e0aaca775f4e1f13fb6349570b9f1e5e1c.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/tables/3d8eaf2fccef3ce19e815baa325827e0aaca775f4e1f13fb6349570b9f1e5e1c.jpg)

![c09e4c5be4d4c673fbdb8dcaea6c0e5580c59d04581ede4fe27d14ccc115d606.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/tables/c09e4c5be4d4c673fbdb8dcaea6c0e5580c59d04581ede4fe27d14ccc115d606.jpg)

![c3bac57bfd89c3427048ec4a9d994085a6973c16990ad1bab32bc925214007f4.jpg](../nips_results/258_CAR-Flow_%20Condition-Aware%20Reparameterization%20Aligns%20Source%20and%20Target%20for%20Better%20Flow%20Matching/tables/c3bac57bfd89c3427048ec4a9d994085a6973c16990ad1bab32bc925214007f4.jpg)

## Debate or Vote: Which Yields Better Decisions in Multi-Agent Large Language Models?


### Images

![7445ace47c5492555c01b8047bba9283a1d695cf971eca5cf022fd7066efe1c7.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/images/7445ace47c5492555c01b8047bba9283a1d695cf971eca5cf022fd7066efe1c7.jpg)

![76a47ab99c90d4b025dd5540e162d67d487ef21eae6bab8d3fcf2bd5907dd028.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/images/76a47ab99c90d4b025dd5540e162d67d487ef21eae6bab8d3fcf2bd5907dd028.jpg)

![844e4375fda68c2915efa87a71f854f7565d59e822d21d9a594ff53c0e003afd.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/images/844e4375fda68c2915efa87a71f854f7565d59e822d21d9a594ff53c0e003afd.jpg)

![95c7eecff088fc8b77314c1ecf04f6215ecf5067fdb4bede9cbd0afeb893a085.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/images/95c7eecff088fc8b77314c1ecf04f6215ecf5067fdb4bede9cbd0afeb893a085.jpg)

![d9c7bbed9f12888d78114a012dca9e647723e48bcfca0d8eba7b7ffb69a5c009.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/images/d9c7bbed9f12888d78114a012dca9e647723e48bcfca0d8eba7b7ffb69a5c009.jpg)

![f53cb333134d9f14b361153d5d421b9e93f41f74a55c7e824a8c99e9b61d7847.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/images/f53cb333134d9f14b361153d5d421b9e93f41f74a55c7e824a8c99e9b61d7847.jpg)

### Tables

![1562291a14fe7e5cffda925e80b3b3e6e0021aed96081677f0c54d936be0b074.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/1562291a14fe7e5cffda925e80b3b3e6e0021aed96081677f0c54d936be0b074.jpg)

![1c91dc3ca3a36e5db948c858d80e80fbea8c81e29c838627fad0dd7183bc253c.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/1c91dc3ca3a36e5db948c858d80e80fbea8c81e29c838627fad0dd7183bc253c.jpg)

![370052f2f7a971ca9f5cb4ccd6b4f135db6e3928c37ff55d591ef797b71c9b92.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/370052f2f7a971ca9f5cb4ccd6b4f135db6e3928c37ff55d591ef797b71c9b92.jpg)

![3df85180f555f6327ba3dffae5976a2f8edc3d26ce689c0eeb3d11a3c68fc629.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/3df85180f555f6327ba3dffae5976a2f8edc3d26ce689c0eeb3d11a3c68fc629.jpg)

![5fdfb959b82d8c8ed064a770b4ab88f34fc328be98168ca2ec5082793b51f777.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/5fdfb959b82d8c8ed064a770b4ab88f34fc328be98168ca2ec5082793b51f777.jpg)

![656fdd03724075b628138f0af967af7c594f46c28e95a56c7b7fef37bf3d4446.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/656fdd03724075b628138f0af967af7c594f46c28e95a56c7b7fef37bf3d4446.jpg)

![70225b1382fb99de7c73e8bad68bda89dd2bf07e0089b7b346d48a2f63057831.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/70225b1382fb99de7c73e8bad68bda89dd2bf07e0089b7b346d48a2f63057831.jpg)

![9751d1728ea6667f73b55c14fdef68bfa6ccf9bcee937b60b185ff96be81e88a.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/9751d1728ea6667f73b55c14fdef68bfa6ccf9bcee937b60b185ff96be81e88a.jpg)

![a483ff33c6b813e26208aef94227fa11a918af53625c27242c641e87defe7b0d.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/a483ff33c6b813e26208aef94227fa11a918af53625c27242c641e87defe7b0d.jpg)

![abb0c9cab7c30a6dac430bb21ed4cc05a106e4ed73a153b15a0671d231e942f9.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/abb0c9cab7c30a6dac430bb21ed4cc05a106e4ed73a153b15a0671d231e942f9.jpg)

![ba602513e985c9690970534fb6d41ba4303c71dd914b5b4611240a73b076615f.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/ba602513e985c9690970534fb6d41ba4303c71dd914b5b4611240a73b076615f.jpg)

![e1b0ffdff29e318c025d86d727ad49d1151d285239c1608154d1ff255a717043.jpg](../nips_results/260_Debate%20or%20Vote_%20Which%20Yields%20Better%20Decisions%20in%20Multi-Agent%20Large%20Language%20Models_/tables/e1b0ffdff29e318c025d86d727ad49d1151d285239c1608154d1ff255a717043.jpg)

## High-order Equivariant Flow Matching for Density Functional Theory Hamiltonian Prediction


### Images

![190380adf6c606fa143e16135a828ef489251f638ac81cd329e103813496bd0c.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/images/190380adf6c606fa143e16135a828ef489251f638ac81cd329e103813496bd0c.jpg)

![3b75b3a7ef233e57a7ee0947be2161a70e1abb0009994876ba36a3c4628ab354.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/images/3b75b3a7ef233e57a7ee0947be2161a70e1abb0009994876ba36a3c4628ab354.jpg)

![7f2d5260f88253d80ce7a0a3977288fd1e9c36e9de33aed0a932728b63765e75.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/images/7f2d5260f88253d80ce7a0a3977288fd1e9c36e9de33aed0a932728b63765e75.jpg)

![94f79938c5203a05a6f5ff46c918df57de7b98d60c79eec2f2ebc99020e4a8ba.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/images/94f79938c5203a05a6f5ff46c918df57de7b98d60c79eec2f2ebc99020e4a8ba.jpg)

![9b1f6ec390f370a4e7c213378dd146bc60b1ec06aa9a072df208612fb1fa3e89.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/images/9b1f6ec390f370a4e7c213378dd146bc60b1ec06aa9a072df208612fb1fa3e89.jpg)

![b483d9643f46613dd642994434b71e0316a6274046660f231f0a364d12e85195.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/images/b483d9643f46613dd642994434b71e0316a6274046660f231f0a364d12e85195.jpg)

![be2f4e64e401ef124e6f622af19db1fce538086c94a7fe465424e293c3422279.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/images/be2f4e64e401ef124e6f622af19db1fce538086c94a7fe465424e293c3422279.jpg)

![c8fe92a5e33426a9cbf9ba34e0d97e1fd0d3f4c1cc55deb479790b6e4fa5976e.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/images/c8fe92a5e33426a9cbf9ba34e0d97e1fd0d3f4c1cc55deb479790b6e4fa5976e.jpg)

![cf2b10059f792d8bd896cbb528f6975c5bce1ec60404cf4ebbc8f925d6c1a2b0.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/images/cf2b10059f792d8bd896cbb528f6975c5bce1ec60404cf4ebbc8f925d6c1a2b0.jpg)

### Tables

![4415c1d7004e96ee0e412f9b0bf8ee28a667f271b6664abeda4482ac2842db9e.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/tables/4415c1d7004e96ee0e412f9b0bf8ee28a667f271b6664abeda4482ac2842db9e.jpg)

![4524fd30f33cae01603be2f5a7da8a5f28c574ed5b4e66bb5d697bd2480147ec.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/tables/4524fd30f33cae01603be2f5a7da8a5f28c574ed5b4e66bb5d697bd2480147ec.jpg)

![59a24ba33dbc1334786f32dea7fd0528315dd86f8f89d30456697d9072daffd3.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/tables/59a24ba33dbc1334786f32dea7fd0528315dd86f8f89d30456697d9072daffd3.jpg)

![7f0ccfa72320e30859e5211a8978ed7ad56a7b6a86a2b7047fbe714a610ec1c6.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/tables/7f0ccfa72320e30859e5211a8978ed7ad56a7b6a86a2b7047fbe714a610ec1c6.jpg)

![a78048ab6a6d5cb7a35f009ff7798b6c6b874e14d920b382ab10647cda1706ff.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/tables/a78048ab6a6d5cb7a35f009ff7798b6c6b874e14d920b382ab10647cda1706ff.jpg)

![adae946c80d6bd94e507292c5a1ac6b52b7710446e2fae631b046ec7923aefc6.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/tables/adae946c80d6bd94e507292c5a1ac6b52b7710446e2fae631b046ec7923aefc6.jpg)

![bc16f7272e00ecf352ddd760db6b6d809200944b0119dbc83c7b9d2124f44bcd.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/tables/bc16f7272e00ecf352ddd760db6b6d809200944b0119dbc83c7b9d2124f44bcd.jpg)

![bd0272edb654d1d764418f5d74bd84a0930c4ce66dfa504df30d1c17aebac1a3.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/tables/bd0272edb654d1d764418f5d74bd84a0930c4ce66dfa504df30d1c17aebac1a3.jpg)

![be41b359efd2dbaa582ac59ce5a768357936d737afddc59cc5da25018a7e0576.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/tables/be41b359efd2dbaa582ac59ce5a768357936d737afddc59cc5da25018a7e0576.jpg)

![de0067fe4a03105eeb0c8c7c3b6b332adc792798b99b63e76c5656191b5d2b1f.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/tables/de0067fe4a03105eeb0c8c7c3b6b332adc792798b99b63e76c5656191b5d2b1f.jpg)

![ffc5ad3d13b0c1b308f5eb4f7f5cdf185ca652d3d9162aa6f6c7eef68b89b544.jpg](../nips_results/261_High-order%20Equivariant%20Flow%20Matching%20for%20Density%20Functional%20Theory%20Hamiltonian%20Prediction/tables/ffc5ad3d13b0c1b308f5eb4f7f5cdf185ca652d3d9162aa6f6c7eef68b89b544.jpg)

## To Distill or Decide? Understanding the Algorithmic Trade-off in Partially Observable RL


### Images

![0cc84d599231fe1a7b512a55bc4298d137d6b06f03673183a42382ed2d9b1d21.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/images/0cc84d599231fe1a7b512a55bc4298d137d6b06f03673183a42382ed2d9b1d21.jpg)

![31d723bbde14fa0148f80b132b5abfdde5402ebffd7fe763be825b5f1669934c.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/images/31d723bbde14fa0148f80b132b5abfdde5402ebffd7fe763be825b5f1669934c.jpg)

![35913ea797f689a70f5929065b03ef3a0491669e0ecc8c660b4ca204a2d8afa3.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/images/35913ea797f689a70f5929065b03ef3a0491669e0ecc8c660b4ca204a2d8afa3.jpg)

![6683ef71fc22462fc5c619d7c755591d6a25d3d83d40c58b9c316a36795606b2.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/images/6683ef71fc22462fc5c619d7c755591d6a25d3d83d40c58b9c316a36795606b2.jpg)

![773831e09bcbc0f2802a5ddf2d3078278ab242ce08de70bb09692cb1c80d4650.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/images/773831e09bcbc0f2802a5ddf2d3078278ab242ce08de70bb09692cb1c80d4650.jpg)

![c1fb299a4683c44cf24f2ea8bb261973c7fb15bbdbbd073f499902be51a2c89d.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/images/c1fb299a4683c44cf24f2ea8bb261973c7fb15bbdbbd073f499902be51a2c89d.jpg)

![ca5ccc5a3946526e44a36a7309729e54e6373283f71a09fe6c1bba97b0b0a18f.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/images/ca5ccc5a3946526e44a36a7309729e54e6373283f71a09fe6c1bba97b0b0a18f.jpg)

![f5735a25a79bcb215963799885ec61b88acd6e08825afab882489d51d36b4241.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/images/f5735a25a79bcb215963799885ec61b88acd6e08825afab882489d51d36b4241.jpg)

![f9c4e99bd1f238be9d10fc035f911cb7b8a1517f27e67e262d23b24ef1578089.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/images/f9c4e99bd1f238be9d10fc035f911cb7b8a1517f27e67e262d23b24ef1578089.jpg)

### Tables

![392b6fe7205d4bfb0a584b6652087287318fc905a7efd7df37d1e6e79a58fe1a.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/tables/392b6fe7205d4bfb0a584b6652087287318fc905a7efd7df37d1e6e79a58fe1a.jpg)

![4ab3fc54ef73e2bd608fa26671dcf288f3351a75aba8ea640e577f81bef51acc.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/tables/4ab3fc54ef73e2bd608fa26671dcf288f3351a75aba8ea640e577f81bef51acc.jpg)

![6965f470e6641983e29f309565a2249bd4ddd7f3df3a46ebfd3e3ed4378e0400.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/tables/6965f470e6641983e29f309565a2249bd4ddd7f3df3a46ebfd3e3ed4378e0400.jpg)

![76378b92bc41846dd0b6f35dafc472c192f7d5813949d5b01d79df7482a2ae20.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/tables/76378b92bc41846dd0b6f35dafc472c192f7d5813949d5b01d79df7482a2ae20.jpg)

![f5315561b98dc3bf5537a20518938154eb343e3d7a7dab115ae0442bff9d681f.jpg](../nips_results/262_To%20Distill%20or%20Decide_%20Understanding%20the%20Algorithmic%20Trade-off%20in%20Partially%20Observable%20RL/tables/f5315561b98dc3bf5537a20518938154eb343e3d7a7dab115ae0442bff9d681f.jpg)

## Boosting Generative Image Modeling via Joint Image-Feature Synthesis


### Images

![053e3fae37e3fae081628c7b16a08f19b5eb64ca1f76c86ba53ab7add047f827.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/053e3fae37e3fae081628c7b16a08f19b5eb64ca1f76c86ba53ab7add047f827.jpg)

![1450e17a2e1938b223a9b1bcd2875a090098aad7569b347524a244f3440a8dc3.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/1450e17a2e1938b223a9b1bcd2875a090098aad7569b347524a244f3440a8dc3.jpg)

![4097fcd921dcf7e42f7ac4d0ff814dd78f6d4a916a1c7abc40bbf6cdb099194f.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/4097fcd921dcf7e42f7ac4d0ff814dd78f6d4a916a1c7abc40bbf6cdb099194f.jpg)

![4af2050cbde2f169eac1fde00cdb76fbdb883ca981d21f4ec5ff73c84c644c28.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/4af2050cbde2f169eac1fde00cdb76fbdb883ca981d21f4ec5ff73c84c644c28.jpg)

![57af97686ce8574dfcd2c5871ed4b33b09dab58b0f2a1b252d439c2bbc181efd.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/57af97686ce8574dfcd2c5871ed4b33b09dab58b0f2a1b252d439c2bbc181efd.jpg)

![6bf636d7352bb0ecc33a6f0cb86ea5af9edeb3bfbaa740c3b10699375e7cdc9f.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/6bf636d7352bb0ecc33a6f0cb86ea5af9edeb3bfbaa740c3b10699375e7cdc9f.jpg)

![82ebe41a7a1affd4b0f512658b58feaea61ca2cbaef97a94ffed39c1054075bb.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/82ebe41a7a1affd4b0f512658b58feaea61ca2cbaef97a94ffed39c1054075bb.jpg)

![8e626de0db1095754b45dd245b24d6c9894d21e893c1ececb41643e644303f39.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/8e626de0db1095754b45dd245b24d6c9894d21e893c1ececb41643e644303f39.jpg)

![9989bd6bafd46a4b97b2b2a80ecd2f17b6a8ebb8c7d49b5b1d1a3b43187a226f.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/9989bd6bafd46a4b97b2b2a80ecd2f17b6a8ebb8c7d49b5b1d1a3b43187a226f.jpg)

![9f68431837acddd133e154cd17eb213556a90c2ba74ed826dd24aacc20a96af9.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/9f68431837acddd133e154cd17eb213556a90c2ba74ed826dd24aacc20a96af9.jpg)

![b061f6447ecfe1c9d15ca1e15c73ea427f1c7060bc2aea0e6daf3ce4c7fe0439.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/b061f6447ecfe1c9d15ca1e15c73ea427f1c7060bc2aea0e6daf3ce4c7fe0439.jpg)

![b436d6678a1a84122352cc12ddd6efc518de6c27fdd9b90f72fdb976f4512207.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/b436d6678a1a84122352cc12ddd6efc518de6c27fdd9b90f72fdb976f4512207.jpg)

![b8f2edc534e3cf4b99feaf9dd38fdbaf84ae3b00e7a226af15d35a011193a0ec.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/b8f2edc534e3cf4b99feaf9dd38fdbaf84ae3b00e7a226af15d35a011193a0ec.jpg)

![cce4a9f7283b9fdaa4a420b3918d4b8db801c786b3e3d44ef9b6bcd51a9e6012.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/cce4a9f7283b9fdaa4a420b3918d4b8db801c786b3e3d44ef9b6bcd51a9e6012.jpg)

![f43e95e73ce59b1e05cadd8a1383fdbbb357bc3558a936742cf43859242f1394.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/f43e95e73ce59b1e05cadd8a1383fdbbb357bc3558a936742cf43859242f1394.jpg)

![f8e0a58c5f572723a6154d38a2291562ffca0a37465606f2843010a5edd47723.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/images/f8e0a58c5f572723a6154d38a2291562ffca0a37465606f2843010a5edd47723.jpg)

### Tables

![18e8180e1df02fc927f32a666f9d75f1d665444db5a63d60ba0d9047570c5ad3.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/tables/18e8180e1df02fc927f32a666f9d75f1d665444db5a63d60ba0d9047570c5ad3.jpg)

![3980ed3b9b5443d3e5938430e2d63e4f4608ba8ab689c44d149b16e0b25eea77.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/tables/3980ed3b9b5443d3e5938430e2d63e4f4608ba8ab689c44d149b16e0b25eea77.jpg)

![49daf5ebe64aa4e1d8f92b439184105f8bea3eff55a5833bf4736c6e7f78898f.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/tables/49daf5ebe64aa4e1d8f92b439184105f8bea3eff55a5833bf4736c6e7f78898f.jpg)

![72ed7ddf2858da7c17014a1ebd561fa4d6df28805a9a62024bc67fe1daa5ad7d.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/tables/72ed7ddf2858da7c17014a1ebd561fa4d6df28805a9a62024bc67fe1daa5ad7d.jpg)

![77d9c8004735f76a5a0b620075d7def48fe230e709befb53bdeb4efa82c947de.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/tables/77d9c8004735f76a5a0b620075d7def48fe230e709befb53bdeb4efa82c947de.jpg)

![7b8a065503fedbb76f359189724c6f9b4e774790e536dae43f9561fb604071f4.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/tables/7b8a065503fedbb76f359189724c6f9b4e774790e536dae43f9561fb604071f4.jpg)

![855bb6764c5ae31e5d1d45608e48e787f7d89678a9a11307eb1ce07725611178.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/tables/855bb6764c5ae31e5d1d45608e48e787f7d89678a9a11307eb1ce07725611178.jpg)

![ac121cc294f466eacdaeb2ae58993b00e392838d8c28e43ff6c5826e6bd81360.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/tables/ac121cc294f466eacdaeb2ae58993b00e392838d8c28e43ff6c5826e6bd81360.jpg)

![b224bfedf9373a87fd3cfb93e0c7c3523c5e09a45bb900120b9c48ee9f88f0f0.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/tables/b224bfedf9373a87fd3cfb93e0c7c3523c5e09a45bb900120b9c48ee9f88f0f0.jpg)

![f778b63225aeb6c801ec879eb6d69f408c95c8012286ef26e02876ad55dba986.jpg](../nips_results/263_Boosting%20Generative%20Image%20Modeling%20via%20Joint%20Image-Feature%20Synthesis/tables/f778b63225aeb6c801ec879eb6d69f408c95c8012286ef26e02876ad55dba986.jpg)

## Uni-LoRA: One Vector is All You Need


### Images

![0227f6d729e216815d391a38dd52a94cef7c89a83e89e404a22b5e30308a44fb.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/images/0227f6d729e216815d391a38dd52a94cef7c89a83e89e404a22b5e30308a44fb.jpg)

![a18b1e3ab876cd457beca17986ed6544b7fb641cb6b24e24040a014dc79a828d.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/images/a18b1e3ab876cd457beca17986ed6544b7fb641cb6b24e24040a014dc79a828d.jpg)

![be0b0bef2a13d7f2596140361a988716309e3af7d5fbe8deafb7055f76f961dc.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/images/be0b0bef2a13d7f2596140361a988716309e3af7d5fbe8deafb7055f76f961dc.jpg)

![ee7c5a1950bd38e89101887e3998bbf0ef569f6a313ca90e0fbffbfbcada9563.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/images/ee7c5a1950bd38e89101887e3998bbf0ef569f6a313ca90e0fbffbfbcada9563.jpg)

### Tables

![058f9b3b80cddc31b58f03acdb6e387d7a09b11bb142ce345741eca6fe71c4bb.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/058f9b3b80cddc31b58f03acdb6e387d7a09b11bb142ce345741eca6fe71c4bb.jpg)

![1ddba84ccc15a04ce23ced6bf06191f920f16a65d286452bba019f01327dfe8b.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/1ddba84ccc15a04ce23ced6bf06191f920f16a65d286452bba019f01327dfe8b.jpg)

![213db631e2b427b7d89040e5e4c088f1a39be0a85e982cb29c6142ec9dfa726f.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/213db631e2b427b7d89040e5e4c088f1a39be0a85e982cb29c6142ec9dfa726f.jpg)

![29b4a05d8ae8574175a3f514bd30c7ebb4df27e00a7dc66e6eee62b8035b999a.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/29b4a05d8ae8574175a3f514bd30c7ebb4df27e00a7dc66e6eee62b8035b999a.jpg)

![53f5a706328b0da0db1094882f348a27735ee2a8767fd88cfb8588db04e73fa8.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/53f5a706328b0da0db1094882f348a27735ee2a8767fd88cfb8588db04e73fa8.jpg)

![8a18f17bda5cba687b39f0c92a570bd8694a8c7237dfa31c48f6348a62eb2185.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/8a18f17bda5cba687b39f0c92a570bd8694a8c7237dfa31c48f6348a62eb2185.jpg)

![bbbd9e9f028b391431177714a135cc8fe775fda07ca9423b2e3d123782af4fb6.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/bbbd9e9f028b391431177714a135cc8fe775fda07ca9423b2e3d123782af4fb6.jpg)

![bdc96f086f1715450747f044d54469bd547876a745431cc68db0bf153d9dbd5f.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/bdc96f086f1715450747f044d54469bd547876a745431cc68db0bf153d9dbd5f.jpg)

![c8f03ceba511561dfac674e943e561728dce426e7c84dcff5fea4cb7e6345844.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/c8f03ceba511561dfac674e943e561728dce426e7c84dcff5fea4cb7e6345844.jpg)

![cb6ff665111e591d82705c959401243288c6faacc7f078605890796db5bde338.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/cb6ff665111e591d82705c959401243288c6faacc7f078605890796db5bde338.jpg)

![cb8424c390d2dd7ac8496ebd348bcfeca41187e9e4161c6b252049fb9b9cb7ea.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/cb8424c390d2dd7ac8496ebd348bcfeca41187e9e4161c6b252049fb9b9cb7ea.jpg)

![cd4cf9b8a3ccf81e210c4a55c4639844931153768622f52d0e968eeadfbdd4e9.jpg](../nips_results/264_Uni-LoRA_%20One%20Vector%20is%20All%20You%20Need/tables/cd4cf9b8a3ccf81e210c4a55c4639844931153768622f52d0e968eeadfbdd4e9.jpg)

## SViMo: Synchronized Diffusion for Video and Motion Generation in Hand-object Interaction Scenarios


### Images

![33cae8fc8aac056bdfb32723cadbd6bbd5d22340f06d045f32cdafbe8134654e.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/33cae8fc8aac056bdfb32723cadbd6bbd5d22340f06d045f32cdafbe8134654e.jpg)

![41da3b0b3ffdbc94fa1a44915292fb2c2b2eed9d3cb8fd0197ff3eda154d1eb5.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/41da3b0b3ffdbc94fa1a44915292fb2c2b2eed9d3cb8fd0197ff3eda154d1eb5.jpg)

![4d005ab0a3686f216032e42e50aee759a82a1a27bdc76922d8312053b17372b0.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/4d005ab0a3686f216032e42e50aee759a82a1a27bdc76922d8312053b17372b0.jpg)

![506a9615507b3b476cae4286c9b9abd0cfb4ee5ba5e271e357bca2907fb423aa.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/506a9615507b3b476cae4286c9b9abd0cfb4ee5ba5e271e357bca2907fb423aa.jpg)

![6b52c7221b4bdc10b88113ce96fec80b8cad2ddb7b47b1621cd1cdb659e3a198.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/6b52c7221b4bdc10b88113ce96fec80b8cad2ddb7b47b1621cd1cdb659e3a198.jpg)

![8a5d3a5f1253fb6dafb480475e1ffc1fe77e2a25d5bf7e0e5a95dd0028a79814.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/8a5d3a5f1253fb6dafb480475e1ffc1fe77e2a25d5bf7e0e5a95dd0028a79814.jpg)

![9de71689b65bb127bdfa5aee6983d2660ffeec274feea5b30cd29ebd4c0924f7.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/9de71689b65bb127bdfa5aee6983d2660ffeec274feea5b30cd29ebd4c0924f7.jpg)

![b04c84114db7e7971b4f0fc93cbd7231e5b502428ac3cd3072a0f5c2d85424c1.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/b04c84114db7e7971b4f0fc93cbd7231e5b502428ac3cd3072a0f5c2d85424c1.jpg)

![d99b2df38a26c6258fdf811fc00f8ece1ad327f808a77b311144694f97acb4d3.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/d99b2df38a26c6258fdf811fc00f8ece1ad327f808a77b311144694f97acb4d3.jpg)

![f1a5a214448d861f0e5f4472060b4e5015bcb257c54d56f48bfe090edf20e7b0.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/f1a5a214448d861f0e5f4472060b4e5015bcb257c54d56f48bfe090edf20e7b0.jpg)

![f4773b128d4c363fd438e486ced49e8359e4c92f232a49f844b3a8743ed01a96.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/f4773b128d4c363fd438e486ced49e8359e4c92f232a49f844b3a8743ed01a96.jpg)

![fffa7bb925f57cf17b1b3a13ebd4d21aeb4c5dd3b2343846befbf6c0ff088ec8.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/images/fffa7bb925f57cf17b1b3a13ebd4d21aeb4c5dd3b2343846befbf6c0ff088ec8.jpg)

### Tables

![20eee97e4b556d3246594b2acb40ed0dbf668128f9f35fcf8c46f5baefcc0efd.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/tables/20eee97e4b556d3246594b2acb40ed0dbf668128f9f35fcf8c46f5baefcc0efd.jpg)

![2dcdf116f9b54b4c1cdf9c1356d6ba9d3fdc179a8903fce8bab76cb26cd92f28.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/tables/2dcdf116f9b54b4c1cdf9c1356d6ba9d3fdc179a8903fce8bab76cb26cd92f28.jpg)

![2f6f63b2593c631c939452e924263bb6e967690c8552ac4fc4452d0771cb7eac.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/tables/2f6f63b2593c631c939452e924263bb6e967690c8552ac4fc4452d0771cb7eac.jpg)

![3c2f25f77a0d34efadef8629dd53e84b756290385ed9d0d71b19701336589eb4.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/tables/3c2f25f77a0d34efadef8629dd53e84b756290385ed9d0d71b19701336589eb4.jpg)

![4c9a2ce29f0489be657c10cf37b822ee3fd340558323bcf0b4f7a9cff366d5c1.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/tables/4c9a2ce29f0489be657c10cf37b822ee3fd340558323bcf0b4f7a9cff366d5c1.jpg)

![6b572d405b8b5853ec1f3e04e863a38b65185840b18bf309d403147bb2d75d4f.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/tables/6b572d405b8b5853ec1f3e04e863a38b65185840b18bf309d403147bb2d75d4f.jpg)

![6ca4034c81fcfc3b621036e568b53691522e5c55c0a2e4da0cfff7e825c6891a.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/tables/6ca4034c81fcfc3b621036e568b53691522e5c55c0a2e4da0cfff7e825c6891a.jpg)

![ab283e2a8d6a6c1bf7bcd3fd613aae1b7c01e5fd4525d2c07582be4056ea7fc2.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/tables/ab283e2a8d6a6c1bf7bcd3fd613aae1b7c01e5fd4525d2c07582be4056ea7fc2.jpg)

![c6936ba14e8d7c140d25f78fc37318efd66923b908edc4bca8358cf4d03057ce.jpg](../nips_results/265_SViMo_%20Synchronized%20Diffusion%20for%20Video%20and%20Motion%20Generation%20in%20Hand-object%20Interaction%20Scenarios/tables/c6936ba14e8d7c140d25f78fc37318efd66923b908edc4bca8358cf4d03057ce.jpg)

## Optimal Nuisance Function Tuning for Estimating a Doubly Robust Functional under Proportional Asymptotics


### Images

![04f1144606a269db7711a6b6a94a6f1f5f22368cb474aa4fed8526e96a634135.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/04f1144606a269db7711a6b6a94a6f1f5f22368cb474aa4fed8526e96a634135.jpg)

![0d698691b2d6075de44cf21b64b5bff47c2c8f4be46ce25bfbd954a2ecf69a06.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/0d698691b2d6075de44cf21b64b5bff47c2c8f4be46ce25bfbd954a2ecf69a06.jpg)

![0d6de396fbdfb1a1f93d796188bdc35a1934e4f86f92bb9840db35acb5c2b149.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/0d6de396fbdfb1a1f93d796188bdc35a1934e4f86f92bb9840db35acb5c2b149.jpg)

![3918d6fd050d2d26cf1391bc918b24471bb630e74a8e1b730586ef184e8db49a.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/3918d6fd050d2d26cf1391bc918b24471bb630e74a8e1b730586ef184e8db49a.jpg)

![3b7093b27d4cbf5a977be9a05e7737942f9f7b6cadc4f13459683d0a0442d64b.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/3b7093b27d4cbf5a977be9a05e7737942f9f7b6cadc4f13459683d0a0442d64b.jpg)

![3d6cae0a921c538b34624e8b2b3a34e7a18b67d0bc61520eda4d531e6f99805f.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/3d6cae0a921c538b34624e8b2b3a34e7a18b67d0bc61520eda4d531e6f99805f.jpg)

![42b6c1316cd5f2d54bf282398a947edbd652c16994604ebcef8bf42a9d36bbca.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/42b6c1316cd5f2d54bf282398a947edbd652c16994604ebcef8bf42a9d36bbca.jpg)

![45462b6a9d0c2613af7aff9c7846e874a3e9c9f8df38466afd53920cb80bb712.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/45462b6a9d0c2613af7aff9c7846e874a3e9c9f8df38466afd53920cb80bb712.jpg)

![7738f1c4458949fa85ccf964946c4bbbce786dd2ff10db011749367017498104.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/7738f1c4458949fa85ccf964946c4bbbce786dd2ff10db011749367017498104.jpg)

![78ef126c4c379bf82b2103177abcef1131687debb5a6ff17edca4696c921bd10.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/78ef126c4c379bf82b2103177abcef1131687debb5a6ff17edca4696c921bd10.jpg)

![817f851187c59cdf8cacae64b0e31cf7dcde047fdea2113200189a3823d983d6.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/817f851187c59cdf8cacae64b0e31cf7dcde047fdea2113200189a3823d983d6.jpg)

![87699cc75fd8ef434871c94863376521d64e7c0269d556abee09e427b597844c.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/87699cc75fd8ef434871c94863376521d64e7c0269d556abee09e427b597844c.jpg)

![9faef0a2d3768a907dbe43e488eac11ad9746125a6996bc808ef5614c69c085c.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/9faef0a2d3768a907dbe43e488eac11ad9746125a6996bc808ef5614c69c085c.jpg)

![abc8672d04610bb66ec6a868573f55706751c946c8eea36f8f362956a39f1fe7.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/abc8672d04610bb66ec6a868573f55706751c946c8eea36f8f362956a39f1fe7.jpg)

![ec802237602df5cc779ed88ca40f0e4ffe03905822065d909d170dae74a3ed7c.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/images/ec802237602df5cc779ed88ca40f0e4ffe03905822065d909d170dae74a3ed7c.jpg)

### Tables

![2eb430f27abfead73292157f3ac217df4afd7903a9f22fc1b7b2b923daeed256.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/tables/2eb430f27abfead73292157f3ac217df4afd7903a9f22fc1b7b2b923daeed256.jpg)

![6811ef3a93d06b452897f981d7d4277732cebeb87acdb72adbcf19d8c4a90dae.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/tables/6811ef3a93d06b452897f981d7d4277732cebeb87acdb72adbcf19d8c4a90dae.jpg)

![8d6b2f77b11ca58cb74ba49f4c3ff80e48acd2fb9bc73428191bfb92d95e3e48.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/tables/8d6b2f77b11ca58cb74ba49f4c3ff80e48acd2fb9bc73428191bfb92d95e3e48.jpg)

![d4912f8174e8329528101a3b8cd9c3e4039dcdcff84ddbb47fcd5dc7e75352ff.jpg](../nips_results/266_Optimal%20Nuisance%20Function%20Tuning%20for%20Estimating%20a%20Doubly%20Robust%20Functional%20under%20Proportional%20Asympt/tables/d4912f8174e8329528101a3b8cd9c3e4039dcdcff84ddbb47fcd5dc7e75352ff.jpg)

## Mitigating Instability in High Residual Adaptive Sampling for PINNs via Langevin Dynamics


### Images

![08b1cab516e05d3a6044c6d925a7770f407549d3d109f066be33ee4e56574458.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/08b1cab516e05d3a6044c6d925a7770f407549d3d109f066be33ee4e56574458.jpg)

![12aee6d1176ca2f9901190c6334985089cf0372015ac376c070f7e6004cee8b4.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/12aee6d1176ca2f9901190c6334985089cf0372015ac376c070f7e6004cee8b4.jpg)

![178fbd9fd891e857efaf5e07c0bb389b516c36204e958c03fdeef62cdcdf21bb.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/178fbd9fd891e857efaf5e07c0bb389b516c36204e958c03fdeef62cdcdf21bb.jpg)

![1d72fdeb1dc1f9c5340d39314ace425850a15a02b483136e08543cbd856510d2.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/1d72fdeb1dc1f9c5340d39314ace425850a15a02b483136e08543cbd856510d2.jpg)

![2b0314278c85d710d24ebdc0b7df47f98a3d6c404364864dc86e1f5296780137.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/2b0314278c85d710d24ebdc0b7df47f98a3d6c404364864dc86e1f5296780137.jpg)

![3a1e8f666b54c97849b9d8107803e01773e1a61f4397db9460ede841e3641266.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/3a1e8f666b54c97849b9d8107803e01773e1a61f4397db9460ede841e3641266.jpg)

![4f2c0ea9867402549632264f9dabbccac560cd52e374876d9999a84b4032a9ce.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/4f2c0ea9867402549632264f9dabbccac560cd52e374876d9999a84b4032a9ce.jpg)

![542328ad956bcdf79203d46ab2f3fadb4484e06028cb54c993fb3faf61b79212.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/542328ad956bcdf79203d46ab2f3fadb4484e06028cb54c993fb3faf61b79212.jpg)

![56767ee89f6dc004356a30fa295e5e8f990e1d0058c101ca803d9e0eb404a57a.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/56767ee89f6dc004356a30fa295e5e8f990e1d0058c101ca803d9e0eb404a57a.jpg)

![95b22ffa2cf5dc32937b5cc8f3874de8209976f40427eec2d64b29530fe15229.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/95b22ffa2cf5dc32937b5cc8f3874de8209976f40427eec2d64b29530fe15229.jpg)

![95bfd05d1e132c11f5188a8c13d2b8cf740893ae2daee13487e507c6c86a9352.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/95bfd05d1e132c11f5188a8c13d2b8cf740893ae2daee13487e507c6c86a9352.jpg)

![9696487f03595171356ab319bcfda703a692bef5f8ee67ce748cb02d95c2429d.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/9696487f03595171356ab319bcfda703a692bef5f8ee67ce748cb02d95c2429d.jpg)

![9a8f409de3dfd1d1ca9e4caa72f14df82852b9323a69c55fa8ebc779ba3c6b5f.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/9a8f409de3dfd1d1ca9e4caa72f14df82852b9323a69c55fa8ebc779ba3c6b5f.jpg)

![ae772e77ee524205194058c370a85174e81a4c7ef2d65a97dfec00f0b97c5d80.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/ae772e77ee524205194058c370a85174e81a4c7ef2d65a97dfec00f0b97c5d80.jpg)

![b8253634ca7431b96361af6ef79f35c324e62b41737951944a316da748d38b90.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/images/b8253634ca7431b96361af6ef79f35c324e62b41737951944a316da748d38b90.jpg)

### Tables

![0472eca9fc07c3f696f34610f6b76dc5496ba641613c7299f6c850eb3ea3af12.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/tables/0472eca9fc07c3f696f34610f6b76dc5496ba641613c7299f6c850eb3ea3af12.jpg)

![1b0cbdaeac6756f11651e471c849ce58dea55501f6e459a906a1c3121cec2904.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/tables/1b0cbdaeac6756f11651e471c849ce58dea55501f6e459a906a1c3121cec2904.jpg)

![57bdc66499f51ab98d3934c8d19f8ff92e03c1586294d8cfc994f6031328f9d0.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/tables/57bdc66499f51ab98d3934c8d19f8ff92e03c1586294d8cfc994f6031328f9d0.jpg)

![676136d95b29cc91dda62dc05cc3fc34e822112e5791448a24646e5bc253d5b5.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/tables/676136d95b29cc91dda62dc05cc3fc34e822112e5791448a24646e5bc253d5b5.jpg)

![6af7303ebebdfe5a049f82fb112b5fd0e24638b49caec2db3f255524e72d3df9.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/tables/6af7303ebebdfe5a049f82fb112b5fd0e24638b49caec2db3f255524e72d3df9.jpg)

![754c89370150a9c4d9d5bc9ba5126eeea63de55bb410a8c0d68f837ee7ddcd65.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/tables/754c89370150a9c4d9d5bc9ba5126eeea63de55bb410a8c0d68f837ee7ddcd65.jpg)

![83bf7db0d7b037d3f158f67cebca2fdb61de7693ac224f649190f720bbdd7601.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/tables/83bf7db0d7b037d3f158f67cebca2fdb61de7693ac224f649190f720bbdd7601.jpg)

![d99c5ee67263125762be99a695dcec8b4d67c92ef240d7105f42fb8496466a8b.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/tables/d99c5ee67263125762be99a695dcec8b4d67c92ef240d7105f42fb8496466a8b.jpg)

![db34ba8b2ed4949d7fd51558dc5ccf40107a729001b9a19b4b5446494710fcc8.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/tables/db34ba8b2ed4949d7fd51558dc5ccf40107a729001b9a19b4b5446494710fcc8.jpg)

![dbab2f3351ef69528460da6229e3dcba0a7e46340d6ecd49e1086612c33009b2.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/tables/dbab2f3351ef69528460da6229e3dcba0a7e46340d6ecd49e1086612c33009b2.jpg)

![ea716b96f51476c01721b766b12803f337caffe13c09793fa6b1a69c6510e28c.jpg](../nips_results/267_Mitigating%20Instability%20in%20High%20Residual%20Adaptive%20Sampling%20for%20PINNs%20via%20Langevin%20Dynamics/tables/ea716b96f51476c01721b766b12803f337caffe13c09793fa6b1a69c6510e28c.jpg)

## Horizon Reduction Makes RL Scalable


### Images

![09e78f5ef4c8443de5096838adc8c71eb31e0771b6a042f3dd88f92d28f17734.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/09e78f5ef4c8443de5096838adc8c71eb31e0771b6a042f3dd88f92d28f17734.jpg)

![0b1a6ba2a9d40f65bb68540746a56a58300426f5d85954eccbe9f7ba2c09b282.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/0b1a6ba2a9d40f65bb68540746a56a58300426f5d85954eccbe9f7ba2c09b282.jpg)

![0f72f48e4f68a0e67c2e245ccec83dbd2802418f9271068a64d11a3009f07e3f.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/0f72f48e4f68a0e67c2e245ccec83dbd2802418f9271068a64d11a3009f07e3f.jpg)

![1bf6cc37142850ddb6a8a2403e02c77ccffd1de33e2f551dddc9aa81a2114697.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/1bf6cc37142850ddb6a8a2403e02c77ccffd1de33e2f551dddc9aa81a2114697.jpg)

![23ee12d910628ef5cb6f8fb49c539d80de9ab0bcccc9b8fe1e3b326ccb950410.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/23ee12d910628ef5cb6f8fb49c539d80de9ab0bcccc9b8fe1e3b326ccb950410.jpg)

![283f4f95b241adeb3a25add6a8372291b372267521d5c4209441227684b243c3.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/283f4f95b241adeb3a25add6a8372291b372267521d5c4209441227684b243c3.jpg)

![483d3914dffccf1de482c93f50d2b9d555a32bf39e3562cd748c3b0fee864440.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/483d3914dffccf1de482c93f50d2b9d555a32bf39e3562cd748c3b0fee864440.jpg)

![4fe8fb7b2b08cd5d09dcbc790bf51a73bd48cf7aa5b2e54b9e79fa9f7fa68085.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/4fe8fb7b2b08cd5d09dcbc790bf51a73bd48cf7aa5b2e54b9e79fa9f7fa68085.jpg)

![65b49dc55d446ed594c0e4f78893110ac589c3342f71566560ffe0378561c523.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/65b49dc55d446ed594c0e4f78893110ac589c3342f71566560ffe0378561c523.jpg)

![6e8a8e85c895baca8867e07b362d328ad9bd605da813fd47623cddefec2a7c07.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/6e8a8e85c895baca8867e07b362d328ad9bd605da813fd47623cddefec2a7c07.jpg)

![73fc93584a01e19457adb933d1650dd35deb9cd060b9ed070ced4b909a443397.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/73fc93584a01e19457adb933d1650dd35deb9cd060b9ed070ced4b909a443397.jpg)

![99004fb5c779dc1480923366203cd190337004b941bc7d1a6126466535e86d45.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/99004fb5c779dc1480923366203cd190337004b941bc7d1a6126466535e86d45.jpg)

![9d306018e8097c4a2a810cd548a8b0523af445851c901a396fdca029c0ad8647.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/9d306018e8097c4a2a810cd548a8b0523af445851c901a396fdca029c0ad8647.jpg)

![aac8aeafa9243ff1ce7701ec2ea9f3a0a7912caaabe342f7b4492499a15d5b14.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/aac8aeafa9243ff1ce7701ec2ea9f3a0a7912caaabe342f7b4492499a15d5b14.jpg)

![b651ac15a4bc38f8a84eae17898d4353329d81ee400f0a29b36aada894dbcc80.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/b651ac15a4bc38f8a84eae17898d4353329d81ee400f0a29b36aada894dbcc80.jpg)

![cd3920c7a60f1f70262d2bfcaf6886e0cc7d0be71ac05953d53b15ae2cdcefb4.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/cd3920c7a60f1f70262d2bfcaf6886e0cc7d0be71ac05953d53b15ae2cdcefb4.jpg)

![d727b554d848966057db163a82a51e63f48886f57a0ecfbfb3fd67ca8c0f4786.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/d727b554d848966057db163a82a51e63f48886f57a0ecfbfb3fd67ca8c0f4786.jpg)

![d7d0e7cbabe6116f0a3bc5d7004c0f31c2bdd586c2eff96bae16b5de8f75aa18.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/d7d0e7cbabe6116f0a3bc5d7004c0f31c2bdd586c2eff96bae16b5de8f75aa18.jpg)

![db23ee3a9a3493746ce56405a44df794471030940078a818c22027b9a6b01c68.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/db23ee3a9a3493746ce56405a44df794471030940078a818c22027b9a6b01c68.jpg)

![e87e98dd18cd171c67abf36837bad425aa991d3cfd009995798a56c321deb9c8.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/e87e98dd18cd171c67abf36837bad425aa991d3cfd009995798a56c321deb9c8.jpg)

![ec5c8cf5e551ff36f0e1765ff82b9c9767641828f49f535d7ba1a41be74f28c6.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/images/ec5c8cf5e551ff36f0e1765ff82b9c9767641828f49f535d7ba1a41be74f28c6.jpg)

### Tables

![2fba72bbb01e55806e1ffb39862d283c9385a8f56f941135f9b627b449824246.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/tables/2fba72bbb01e55806e1ffb39862d283c9385a8f56f941135f9b627b449824246.jpg)

![4cbb1f47955af74b1189d6cf12c864ca6081d312d2ce8c4cd272fa31b0b48f82.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/tables/4cbb1f47955af74b1189d6cf12c864ca6081d312d2ce8c4cd272fa31b0b48f82.jpg)

![69268cbce27c4d42cd5e611a81c751489c7cd4d82a403e96cfcd8dae17509eca.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/tables/69268cbce27c4d42cd5e611a81c751489c7cd4d82a403e96cfcd8dae17509eca.jpg)

![9544ff4eff500ccade5f7e105ff12542187485578e49643a1aa3e42f86caeaa5.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/tables/9544ff4eff500ccade5f7e105ff12542187485578e49643a1aa3e42f86caeaa5.jpg)

![9f4c79ecddb0a74057ec8777346bff9aa4bead1138968d897354609dabf743b6.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/tables/9f4c79ecddb0a74057ec8777346bff9aa4bead1138968d897354609dabf743b6.jpg)

![cff36e1fcc8ea2090e106d62bf1a56aa8f83494f0e5872d0fb260399ff0b2a07.jpg](../nips_results/268_Horizon%20Reduction%20Makes%20RL%20Scalable/tables/cff36e1fcc8ea2090e106d62bf1a56aa8f83494f0e5872d0fb260399ff0b2a07.jpg)

## Reverse Engineering Human Preferences with Reinforcement Learning


### Images

![2849c6afd753fa36c8fbbb276a43b885e6307c88ab5464fc5ea9e03f44304c4e.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/images/2849c6afd753fa36c8fbbb276a43b885e6307c88ab5464fc5ea9e03f44304c4e.jpg)

![41f4ad052dc48865f47c36af5efe52a3b58ca68f600452b93272f44c0b5a73e4.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/images/41f4ad052dc48865f47c36af5efe52a3b58ca68f600452b93272f44c0b5a73e4.jpg)

![6f1a579dd209444e09beb6f1b5251f405b834b010f94f0bd66327e8a4c53eb89.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/images/6f1a579dd209444e09beb6f1b5251f405b834b010f94f0bd66327e8a4c53eb89.jpg)

### Tables

![320b6b7edc79ef19b618f4490b0b39937a6724754f51a464f27298e31d67e45c.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/320b6b7edc79ef19b618f4490b0b39937a6724754f51a464f27298e31d67e45c.jpg)

![534a730a2b570b4d1825852d089a8f227d7f088e0d708e23d50cfdb8c6cc00a4.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/534a730a2b570b4d1825852d089a8f227d7f088e0d708e23d50cfdb8c6cc00a4.jpg)

![5b4d77bc8dc2c9598335448102a6e6dd4e20cd8134053f2cebcc3da0153c5640.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/5b4d77bc8dc2c9598335448102a6e6dd4e20cd8134053f2cebcc3da0153c5640.jpg)

![5dea23718d4f9b697fddb8500c2eb48f1cb760088e8a9fe7a432515ca4fd55e6.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/5dea23718d4f9b697fddb8500c2eb48f1cb760088e8a9fe7a432515ca4fd55e6.jpg)

![64099cdc658f944bd79ce497f91fd981999e5cae255153aa46ecdac617ac60d5.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/64099cdc658f944bd79ce497f91fd981999e5cae255153aa46ecdac617ac60d5.jpg)

![6b0798b9b81a7a425b784214e77bba27250d1b50d5da3d4416d64cfc0f8c9591.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/6b0798b9b81a7a425b784214e77bba27250d1b50d5da3d4416d64cfc0f8c9591.jpg)

![6d254d34a78cf4aa98967014188e70bbf8b8c2bbba8b462103a5d7c8b4eb9579.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/6d254d34a78cf4aa98967014188e70bbf8b8c2bbba8b462103a5d7c8b4eb9579.jpg)

![76cae2dfa2bf475610eac2ad586033a7f22b54a3230ed1117585c47e80ebe9f6.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/76cae2dfa2bf475610eac2ad586033a7f22b54a3230ed1117585c47e80ebe9f6.jpg)

![7723526021ec66cf712bb17081c17b8172e7c68ecd182b0bbd795bd58f9a4bc1.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/7723526021ec66cf712bb17081c17b8172e7c68ecd182b0bbd795bd58f9a4bc1.jpg)

![9cb432c2ac68295bb21f3cd1a2bdfa25827c5e5ebf1ccd94dda32569e9598190.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/9cb432c2ac68295bb21f3cd1a2bdfa25827c5e5ebf1ccd94dda32569e9598190.jpg)

![a401029be0cc0e3a331880038ab2dd8cfa67d6596a5ef23c5f3073ebdbb14a84.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/a401029be0cc0e3a331880038ab2dd8cfa67d6596a5ef23c5f3073ebdbb14a84.jpg)

![d6404ead5a427a412b7e7266cf9c0e7940feb5cb05b710b4bdb3742fd48da144.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/d6404ead5a427a412b7e7266cf9c0e7940feb5cb05b710b4bdb3742fd48da144.jpg)

![def9bd8727ccbdfabb7f510155189ac5f15ddcb784a051dd7f78dc5f4c6d6d5e.jpg](../nips_results/269_Reverse%20Engineering%20Human%20Preferences%20with%20Reinforcement%20Learning/tables/def9bd8727ccbdfabb7f510155189ac5f15ddcb784a051dd7f78dc5f4c6d6d5e.jpg)

## Scaling can lead to compositional generalization


### Images

![15a8a0471d236dfd4efab3c0cd6c6c09bc14de677362ff58211d681e88a0ac1c.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/15a8a0471d236dfd4efab3c0cd6c6c09bc14de677362ff58211d681e88a0ac1c.jpg)

![4ad4eb89a80d006cc512b372e9ddf870fb1acb0d6665c5aac416900c8ec0e31b.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/4ad4eb89a80d006cc512b372e9ddf870fb1acb0d6665c5aac416900c8ec0e31b.jpg)

![5875dbb676a45a14c378b71057e4fa3a8706ca712ea21b52f4ecdd2248565a23.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/5875dbb676a45a14c378b71057e4fa3a8706ca712ea21b52f4ecdd2248565a23.jpg)

![5fa5817d65e07a1041dfbb2fdbdfbba150e01ed9f87cec17c5e297202538a16e.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/5fa5817d65e07a1041dfbb2fdbdfbba150e01ed9f87cec17c5e297202538a16e.jpg)

![7deddb7bc0647be68637e2d71301c7af0101b7a860c0397e22b147154ad8fd37.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/7deddb7bc0647be68637e2d71301c7af0101b7a860c0397e22b147154ad8fd37.jpg)

![807b5b94134b10072d4c87ec326cd6118a3d3a648e6897ce54bf17af17da8588.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/807b5b94134b10072d4c87ec326cd6118a3d3a648e6897ce54bf17af17da8588.jpg)

![9a15d9617d7abe887a213f920828a11cdde0a4a44075afbf71f0ea719fb498b2.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/9a15d9617d7abe887a213f920828a11cdde0a4a44075afbf71f0ea719fb498b2.jpg)

![b9f7d7bd721e577b39f223bdc4f3030c5de80bcff1601e4d38a30958314cdc09.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/b9f7d7bd721e577b39f223bdc4f3030c5de80bcff1601e4d38a30958314cdc09.jpg)

![c115eb588d262d3b7569994d2a82254eec9f1f8318c788ebdf1feec09f11a494.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/c115eb588d262d3b7569994d2a82254eec9f1f8318c788ebdf1feec09f11a494.jpg)

![e9e001f416d98841898d794c3375a51a245c1f6972cfb3276b443b137610d9e8.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/e9e001f416d98841898d794c3375a51a245c1f6972cfb3276b443b137610d9e8.jpg)

![f10d44209c243751eed3b8ddd626fa89a97d14ae2b35a434c56f3f48f6b1c069.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/f10d44209c243751eed3b8ddd626fa89a97d14ae2b35a434c56f3f48f6b1c069.jpg)

![f7c3a5fe37cd0620e5de6a1740231caba4ce6b79ecdab1ae5f117326e4d4ccb8.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/images/f7c3a5fe37cd0620e5de6a1740231caba4ce6b79ecdab1ae5f117326e4d4ccb8.jpg)

### Tables

![1bafa430c97da40b21194117eee387d9221c1e2530e539cc91a90a8cc1628651.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/tables/1bafa430c97da40b21194117eee387d9221c1e2530e539cc91a90a8cc1628651.jpg)

![2cdcf9f195479a03e915443241d4765b9af7227d052bc06c07b8aa4b0abd7357.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/tables/2cdcf9f195479a03e915443241d4765b9af7227d052bc06c07b8aa4b0abd7357.jpg)

![53ac267ad95925476877f4c5e610330e8a2834ba867fae1cc7b030e0fb28bc2a.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/tables/53ac267ad95925476877f4c5e610330e8a2834ba867fae1cc7b030e0fb28bc2a.jpg)

![c6d83e680380668784c4cf5ebd264d1bda5a2ad92e266278b63bb2e1373e4786.jpg](../nips_results/270_Scaling%20can%20lead%20to%20compositional%20generalization/tables/c6d83e680380668784c4cf5ebd264d1bda5a2ad92e266278b63bb2e1373e4786.jpg)

## On the Surprising Effectiveness of Large Learning Rates under Standard Width Scaling


### Images

![05a1bdff4b207ef6c55b13d0aa9247a379fcf7da0bec3eb980b8e2e0663266a0.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/05a1bdff4b207ef6c55b13d0aa9247a379fcf7da0bec3eb980b8e2e0663266a0.jpg)

![05e5ce364aa155737b413eb060caea4d2acfcd5dbdc2bd4867ab3b0e065c74a9.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/05e5ce364aa155737b413eb060caea4d2acfcd5dbdc2bd4867ab3b0e065c74a9.jpg)

![0df2555f032defec22920f65505530b3ee7aa0c169099fe2d711885e8bac39ab.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/0df2555f032defec22920f65505530b3ee7aa0c169099fe2d711885e8bac39ab.jpg)

![117772560a6b3c99e79e0da4c9c9134348133d4b97dec43c7c53c9e58a4018ea.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/117772560a6b3c99e79e0da4c9c9134348133d4b97dec43c7c53c9e58a4018ea.jpg)

![12ab521743280c1b3bb177707a1a46f94106bf842f4b01ff563bddcbf113f543.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/12ab521743280c1b3bb177707a1a46f94106bf842f4b01ff563bddcbf113f543.jpg)

![13e58f882bc2b22b32e7750ff71e8dd03ecb644f37684530cf7d18ccdefe002a.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/13e58f882bc2b22b32e7750ff71e8dd03ecb644f37684530cf7d18ccdefe002a.jpg)

![16def0f723d5de682d5df2a2af9b0c71f2a96ee2e98092479b4519ca672b53ed.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/16def0f723d5de682d5df2a2af9b0c71f2a96ee2e98092479b4519ca672b53ed.jpg)

![1aebd98d9e3e098e57a5eacac5d4a2fde4a0f41e3b9af00e0177ed029592774d.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/1aebd98d9e3e098e57a5eacac5d4a2fde4a0f41e3b9af00e0177ed029592774d.jpg)

![1cff4e63bd2236d6add1b39720bb5ed9e90deabfae8af7a0e390e96335ff9012.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/1cff4e63bd2236d6add1b39720bb5ed9e90deabfae8af7a0e390e96335ff9012.jpg)

![23c76ee46e64ff44e54dc4bfe0cd39a97e5b120b6443245d4a68b9753dda2966.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/23c76ee46e64ff44e54dc4bfe0cd39a97e5b120b6443245d4a68b9753dda2966.jpg)

![25803077873c0dbb208eeb89c7c4525e3510504c54af5386ed939daa43928b63.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/25803077873c0dbb208eeb89c7c4525e3510504c54af5386ed939daa43928b63.jpg)

![30ce2c77cce690305363266377c526832e8c4dfefb5a9cf3050028db4fde2be8.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/30ce2c77cce690305363266377c526832e8c4dfefb5a9cf3050028db4fde2be8.jpg)

![3a5cf60753ced81c863d9288b4f6f24026aaa907b5e57798d2ddedd9198c34d8.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/3a5cf60753ced81c863d9288b4f6f24026aaa907b5e57798d2ddedd9198c34d8.jpg)

![3d5edc6bc6d22ec97c138996dfdc3791626c58230354135b8457a9377d279378.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/3d5edc6bc6d22ec97c138996dfdc3791626c58230354135b8457a9377d279378.jpg)

![3f27d3fa7bb8e027e2bcca081ca8e26700707196288ca224d83193fc4a1ec2f0.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/3f27d3fa7bb8e027e2bcca081ca8e26700707196288ca224d83193fc4a1ec2f0.jpg)

![3f861c4dcfebaa26f480442704a96df133fbedf8cc6d71625487fc49f30fbb35.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/3f861c4dcfebaa26f480442704a96df133fbedf8cc6d71625487fc49f30fbb35.jpg)

![3f9557d0d81cb62a10b7a2dc5be4e1e27b445eed9d899fd6ba3697a032c5d452.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/3f9557d0d81cb62a10b7a2dc5be4e1e27b445eed9d899fd6ba3697a032c5d452.jpg)

![423dc9d0676bbfe07a15f7b4a39bc4fd82dbc022284c1f65d41ea16167687069.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/423dc9d0676bbfe07a15f7b4a39bc4fd82dbc022284c1f65d41ea16167687069.jpg)

![4c99cdef6a70320474eaa18823cc4622b7d0235fceda0497c63b60454a81d713.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/4c99cdef6a70320474eaa18823cc4622b7d0235fceda0497c63b60454a81d713.jpg)

![4d5657ca792d33ee8426a81dc4b46f76aeba6b0218d67eb249e2de26685da76c.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/4d5657ca792d33ee8426a81dc4b46f76aeba6b0218d67eb249e2de26685da76c.jpg)

![54709f9c85cac11a98630f7292ba7ec9dddb0ccf7e15cc76bc6fc510c6f7f676.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/54709f9c85cac11a98630f7292ba7ec9dddb0ccf7e15cc76bc6fc510c6f7f676.jpg)

![547b97c86e72b976266cb4447f8628b42bb52a4482dd47e8f5aa894da928f5e6.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/547b97c86e72b976266cb4447f8628b42bb52a4482dd47e8f5aa894da928f5e6.jpg)

![57ceaf4954ce2798b926911aef0aab0eb196aa272bac58602f98948dc9906860.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/57ceaf4954ce2798b926911aef0aab0eb196aa272bac58602f98948dc9906860.jpg)

![5b11a1accd167681c5b9e9a46f7621e47fb38db2885f59e8672af2102f93e27b.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/5b11a1accd167681c5b9e9a46f7621e47fb38db2885f59e8672af2102f93e27b.jpg)

![646749d8524ebbf632823830e4e65319e40134918b4e60d168264778eb73fb1f.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/646749d8524ebbf632823830e4e65319e40134918b4e60d168264778eb73fb1f.jpg)

![6b60cc8327aa1ac6651d5ae58a0a9cd1af19bd80d6501aa8567f1eb414bc5082.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/6b60cc8327aa1ac6651d5ae58a0a9cd1af19bd80d6501aa8567f1eb414bc5082.jpg)

![6d9197fad9e18a3b82b66f616b42a8b6c7023ef25a7af18817a1cef6e54ce09d.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/6d9197fad9e18a3b82b66f616b42a8b6c7023ef25a7af18817a1cef6e54ce09d.jpg)

![7a03dd7797c045243bf2ed040ee5acce5e378ec40f025edd42a493e817986dba.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/7a03dd7797c045243bf2ed040ee5acce5e378ec40f025edd42a493e817986dba.jpg)

![7b370210faf56fed529094baba8a387f8d5101fcb500b5f878ec47b3b4101359.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/7b370210faf56fed529094baba8a387f8d5101fcb500b5f878ec47b3b4101359.jpg)

![819c5650ce836792fade5a0de3fc7a5c412cd9aeba1388fdb08aa82cedf3c7be.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/819c5650ce836792fade5a0de3fc7a5c412cd9aeba1388fdb08aa82cedf3c7be.jpg)

![83194a2b30dacb4c831a51a41b28ac77d690f2f652d421822a9d93b6ad0dde88.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/83194a2b30dacb4c831a51a41b28ac77d690f2f652d421822a9d93b6ad0dde88.jpg)

![85339a95cd3d1b6062bc436d8dbb4b6059b20aef171c0dbe409d08f41c60ab6e.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/85339a95cd3d1b6062bc436d8dbb4b6059b20aef171c0dbe409d08f41c60ab6e.jpg)

![87e939cb9a4a07d8f2d6faf8d8bfd282205dcf74a58856ba541cac16e0d68152.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/87e939cb9a4a07d8f2d6faf8d8bfd282205dcf74a58856ba541cac16e0d68152.jpg)

![885754f3c2737abe9854f08c503936daa09f4a78eab9be0030aaf8f63eb4dcb6.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/885754f3c2737abe9854f08c503936daa09f4a78eab9be0030aaf8f63eb4dcb6.jpg)

![8b1b160aca4282c06db62b8a8e25d6806d4e699a89e950865d4627443672b4a9.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/8b1b160aca4282c06db62b8a8e25d6806d4e699a89e950865d4627443672b4a9.jpg)

![8c5664368abc458aedce85f7fe2b54750ddbfe10be5568904185d1cc4f0c4bc3.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/8c5664368abc458aedce85f7fe2b54750ddbfe10be5568904185d1cc4f0c4bc3.jpg)

![93c3c7b55dfc0a25a021ae340b8490f7a02c552686bd29653956fdf82bec1f22.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/93c3c7b55dfc0a25a021ae340b8490f7a02c552686bd29653956fdf82bec1f22.jpg)

![9702ed2a535e6133e5d2c13c73e4544fecb15ad4f1e53313eef146022a39f2ba.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/9702ed2a535e6133e5d2c13c73e4544fecb15ad4f1e53313eef146022a39f2ba.jpg)

![9717006b47434256149d99aa1a14fb10ad34727a3da2fcc8fcdfbdc59e234ca6.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/9717006b47434256149d99aa1a14fb10ad34727a3da2fcc8fcdfbdc59e234ca6.jpg)

![9786d4b81789a198685801b6e4a8c876a8ae2877b3a1e9cffdc8d737eb94db15.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/9786d4b81789a198685801b6e4a8c876a8ae2877b3a1e9cffdc8d737eb94db15.jpg)

![9da4eeb7aa98f0c4b0b5c108614f414e4a535597eb47f9d34f56a496f730e883.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/9da4eeb7aa98f0c4b0b5c108614f414e4a535597eb47f9d34f56a496f730e883.jpg)

![a248911cfd54a94c0dcc2f29a6301661d0a3a26847f87283a39f300f40dc5dbe.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/a248911cfd54a94c0dcc2f29a6301661d0a3a26847f87283a39f300f40dc5dbe.jpg)

![a2a2fb090077c9007864c240dda44d7beb204f19af4a7c3d2985ab85cb220cbb.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/a2a2fb090077c9007864c240dda44d7beb204f19af4a7c3d2985ab85cb220cbb.jpg)

![a5133138cc84b31d83a9a77edfc02f8e01d156e3de39d6ebaf88706b9ab922fc.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/a5133138cc84b31d83a9a77edfc02f8e01d156e3de39d6ebaf88706b9ab922fc.jpg)

![a5fcb975c2ccbd02e2424a9c5d627e358ee680aa46e45221078d553e6855642c.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/a5fcb975c2ccbd02e2424a9c5d627e358ee680aa46e45221078d553e6855642c.jpg)

![a896db6d05bdd92906d93b11c8bb14cc5b9f323eb37cdd260b236b0be1dc9b7a.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/a896db6d05bdd92906d93b11c8bb14cc5b9f323eb37cdd260b236b0be1dc9b7a.jpg)

![ac4f51d6a8be33804b3054d560c2f6d9a86d5aac3852a7e1827e5ac66f136151.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/ac4f51d6a8be33804b3054d560c2f6d9a86d5aac3852a7e1827e5ac66f136151.jpg)

![b26539567578718c8cc620c4ee9160632890bad96d8ea32ae07fcf8259b6b728.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/b26539567578718c8cc620c4ee9160632890bad96d8ea32ae07fcf8259b6b728.jpg)

![b5418383991263c7fd6dd3e55a568eca72bf86f2b29ba3b6eae36209591fa957.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/b5418383991263c7fd6dd3e55a568eca72bf86f2b29ba3b6eae36209591fa957.jpg)

![b6b5ba6c280ac08291330264c7f93f9ea25b97a783978ffd270178af16607ec7.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/b6b5ba6c280ac08291330264c7f93f9ea25b97a783978ffd270178af16607ec7.jpg)

![bdbc6f325c78dae947e7f62767b38ad7224f0da8c6987a1622e381ebad81775b.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/bdbc6f325c78dae947e7f62767b38ad7224f0da8c6987a1622e381ebad81775b.jpg)

![c1d0dd62179fe5a75f58fee58c35dc894bad2c8f047b47a58eb3b8c4e9bc3c95.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/c1d0dd62179fe5a75f58fee58c35dc894bad2c8f047b47a58eb3b8c4e9bc3c95.jpg)

![c43f39ec0e1f2df8a5b0284773e6308286b3aba65449e824ccfd5e4472f51020.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/c43f39ec0e1f2df8a5b0284773e6308286b3aba65449e824ccfd5e4472f51020.jpg)

![c5f874cf7cefe1e2fc77221bfe80307be9e45a251d0f61a829267de97c8137a2.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/c5f874cf7cefe1e2fc77221bfe80307be9e45a251d0f61a829267de97c8137a2.jpg)

![c7dce7bcd66e001f781a3fa8ab18e461eebc8adaf738c8f15c7f64b1546bc903.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/c7dce7bcd66e001f781a3fa8ab18e461eebc8adaf738c8f15c7f64b1546bc903.jpg)

![ca4fa016a71d99daa21b233f2805ba08bb7ea8d895b19ec1e7f4cd74f35b6929.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/ca4fa016a71d99daa21b233f2805ba08bb7ea8d895b19ec1e7f4cd74f35b6929.jpg)

![d547137e25d891dbd63ca8b8b3da6a0acf3ff0f1939684c3cd524cc6d779ac2c.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/d547137e25d891dbd63ca8b8b3da6a0acf3ff0f1939684c3cd524cc6d779ac2c.jpg)

![d5877adef3ec0117e515f5dc2feb4373a1f58f6c41a22e8f15accb5c27437e54.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/d5877adef3ec0117e515f5dc2feb4373a1f58f6c41a22e8f15accb5c27437e54.jpg)

![d87bf77b882c4dd71307625177730b33c8e590a08c097e5fa35935cd443341c8.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/d87bf77b882c4dd71307625177730b33c8e590a08c097e5fa35935cd443341c8.jpg)

![de702e9ad78874288ea473618c89f63b54d686c5828825ea8aa3490f473a9463.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/de702e9ad78874288ea473618c89f63b54d686c5828825ea8aa3490f473a9463.jpg)

![e097b6752d3c65be74d798f22bb8691b6ab8a2c59e14f529b35ca08d2eb3e1c9.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/e097b6752d3c65be74d798f22bb8691b6ab8a2c59e14f529b35ca08d2eb3e1c9.jpg)

![e8868c27cdbe732f96fbb028b95e91b302e72f6b553fb9ac3a529c7ecaa4194d.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/e8868c27cdbe732f96fbb028b95e91b302e72f6b553fb9ac3a529c7ecaa4194d.jpg)

![ee1598720326354951c2ee78ee100b785f3eeed9fbc67b460b55444cb4152ba8.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/ee1598720326354951c2ee78ee100b785f3eeed9fbc67b460b55444cb4152ba8.jpg)

![f1160b66abadbb6b4e9d18196b286e0431af2e96e8e6d4fcc3a3ce7a9465d7f5.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/f1160b66abadbb6b4e9d18196b286e0431af2e96e8e6d4fcc3a3ce7a9465d7f5.jpg)

![f18f37cfaeb2b837450687743bf1d8bc78355268c64ba993769f35388699c2c7.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/f18f37cfaeb2b837450687743bf1d8bc78355268c64ba993769f35388699c2c7.jpg)

![f1d1ffc65c8c6db0558f964ffb34d165ca4cb68d078d6e26e40ba25b68b2f1ed.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/f1d1ffc65c8c6db0558f964ffb34d165ca4cb68d078d6e26e40ba25b68b2f1ed.jpg)

![f49e44b98e82b3d2c7327bacf8e940fc0ba4558c6cd1b8346b34f0ebdd84c9b1.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/f49e44b98e82b3d2c7327bacf8e940fc0ba4558c6cd1b8346b34f0ebdd84c9b1.jpg)

![f57c03b7fb4dc547885a493796eaa6632e4e16560e83efeaa59255f989640293.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/images/f57c03b7fb4dc547885a493796eaa6632e4e16560e83efeaa59255f989640293.jpg)

### Tables

![5b0a28166f57b8669c00e0c855e30acc4339ae41ce238aa03b972b13286dd6a9.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/tables/5b0a28166f57b8669c00e0c855e30acc4339ae41ce238aa03b972b13286dd6a9.jpg)

![6111d90f6ec8ebe47fcb4fd8f01f75df5d28c29403de8180f5dfccfa6bb5a3ad.jpg](../nips_results/271_On%20the%20Surprising%20Effectiveness%20of%20Large%20Learning%20Rates%20under%20Standard%20Width%20Scaling/tables/6111d90f6ec8ebe47fcb4fd8f01f75df5d28c29403de8180f5dfccfa6bb5a3ad.jpg)

## Inference-Time Reward Hacking in Large Language Models


### Images

![0d5f4841824cd2b94708658611e878a45bdd5d4cfe10c64208dddc4ee165da1c.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/0d5f4841824cd2b94708658611e878a45bdd5d4cfe10c64208dddc4ee165da1c.jpg)

![1a38a6eca544b88007d3dc8913c0ffd2a6bd20ecc775720affad9f8dcde598eb.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/1a38a6eca544b88007d3dc8913c0ffd2a6bd20ecc775720affad9f8dcde598eb.jpg)

![1f4849a45c6d55cbf83946765ace458528b04c2ef3b5bfb35c98d6033d3e23a6.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/1f4849a45c6d55cbf83946765ace458528b04c2ef3b5bfb35c98d6033d3e23a6.jpg)

![38373ae01265e8fd8de5c3a8c7f68cc50ae5990a76ef4159d4d63f172b17095d.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/38373ae01265e8fd8de5c3a8c7f68cc50ae5990a76ef4159d4d63f172b17095d.jpg)

![42bd7b450ba0e2ee6f17f30cef9e45b1449266e484dec9d12086adbbb98ed4e5.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/42bd7b450ba0e2ee6f17f30cef9e45b1449266e484dec9d12086adbbb98ed4e5.jpg)

![43dc408528556b2673313df6928f24420135e23b31359677468067e4925c9b24.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/43dc408528556b2673313df6928f24420135e23b31359677468067e4925c9b24.jpg)

![6f05f8098443501e4cdf49c255f01a41ecd052f83fee2f5f115e4efaf6aa8f87.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/6f05f8098443501e4cdf49c255f01a41ecd052f83fee2f5f115e4efaf6aa8f87.jpg)

![8b279557dcd1a7eb66936dd87809f20fbdd81f09542c1b37c5d066de4ab75318.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/8b279557dcd1a7eb66936dd87809f20fbdd81f09542c1b37c5d066de4ab75318.jpg)

![b7bf6e34f03116264cf52695b7718295d45af116422035669930e89b4882f1f8.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/b7bf6e34f03116264cf52695b7718295d45af116422035669930e89b4882f1f8.jpg)

![c2eb113fec95d5b647e5d0088bdd43c7325bd74568136263fdf9c62a1d25ece1.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/c2eb113fec95d5b647e5d0088bdd43c7325bd74568136263fdf9c62a1d25ece1.jpg)

![d738c43249bd1b353a18a9b83a1da2e65927bef61ddafdd19047d178f4071330.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/d738c43249bd1b353a18a9b83a1da2e65927bef61ddafdd19047d178f4071330.jpg)

![f018323a248f084b60289259598d583288318942b0d7465971755a05e0f854fd.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/images/f018323a248f084b60289259598d583288318942b0d7465971755a05e0f854fd.jpg)

### Tables

![b2403ab7bfd58c8bc3550b25d5ef82010e86b8643c54c5244332b9e7fc00d5f3.jpg](../nips_results/272_Inference-Time%20Reward%20Hacking%20in%20Large%20Language%20Models/tables/b2403ab7bfd58c8bc3550b25d5ef82010e86b8643c54c5244332b9e7fc00d5f3.jpg)

## DICEPTION: A Generalist Diffusion Model for Visual Perceptual Tasks


### Images

![2671c27158567107b3098b384e581ad9c359683a6f2537c55642618832a92500.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/2671c27158567107b3098b384e581ad9c359683a6f2537c55642618832a92500.jpg)

![2af34eff8e8b6cd601e695900578d21e5848e879a896371800281de0a0cb2466.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/2af34eff8e8b6cd601e695900578d21e5848e879a896371800281de0a0cb2466.jpg)

![35665f6a34c537a099aba8bddd5aeeee3a5019ae7c095326ac29e3d6569ae537.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/35665f6a34c537a099aba8bddd5aeeee3a5019ae7c095326ac29e3d6569ae537.jpg)

![4c397efc666996b6e01a70659fea5b11cf51dc0ca574674b4951846e9f2c845e.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/4c397efc666996b6e01a70659fea5b11cf51dc0ca574674b4951846e9f2c845e.jpg)

![5c6a79c8b873681bd1c2b39c902cf0ddaaa32b4664fbfeafffa9c3c023d3a93c.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/5c6a79c8b873681bd1c2b39c902cf0ddaaa32b4664fbfeafffa9c3c023d3a93c.jpg)

![5d25ee16e871570abbdccef19629f62d588d5d224bedd97aad60a7f02842b1b5.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/5d25ee16e871570abbdccef19629f62d588d5d224bedd97aad60a7f02842b1b5.jpg)

![60f60cc9dec14218431fa26655d55bb8d5481187a6fa3376668904bed73be4ed.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/60f60cc9dec14218431fa26655d55bb8d5481187a6fa3376668904bed73be4ed.jpg)

![8bd0b8b73517084e1a90b02bc5cc0966af85e4b0a9b19f3aec3c27d42928b29c.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/8bd0b8b73517084e1a90b02bc5cc0966af85e4b0a9b19f3aec3c27d42928b29c.jpg)

![8d8fe66befecab23667702bae7af3f8b808bf6306a50e5c38ed42bf82892d010.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/8d8fe66befecab23667702bae7af3f8b808bf6306a50e5c38ed42bf82892d010.jpg)

![8f0f737f34a038e391c4b544193517266dc4b94f5ba4256f8e061dd7eb75184b.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/8f0f737f34a038e391c4b544193517266dc4b94f5ba4256f8e061dd7eb75184b.jpg)

![9d7401311f9a261a90b38b355b588e67c01be6dc635f5b50e8225d0ec1a22b9a.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/9d7401311f9a261a90b38b355b588e67c01be6dc635f5b50e8225d0ec1a22b9a.jpg)

![a5489272d906ae1866702bd879d1649edc149fed4022a4735a3cc57f0a43033d.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/a5489272d906ae1866702bd879d1649edc149fed4022a4735a3cc57f0a43033d.jpg)

![ab670162cdcf617d5dc1977483c548c318ac6f358f3a4513700d6681d7e808ca.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/ab670162cdcf617d5dc1977483c548c318ac6f358f3a4513700d6681d7e808ca.jpg)

![bf70033e65b44f0e054abb487ef5131dd40aecf117c4742c395af06e8600e6cb.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/bf70033e65b44f0e054abb487ef5131dd40aecf117c4742c395af06e8600e6cb.jpg)

![c3d9cc50b680da548098c79e5b64fefeaf7a802a343287beedf0f4ebbd5e13ed.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/c3d9cc50b680da548098c79e5b64fefeaf7a802a343287beedf0f4ebbd5e13ed.jpg)

![c978d070f2861f1765a4999583b48b095aee8ad7fae474db078776cc3149d1be.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/c978d070f2861f1765a4999583b48b095aee8ad7fae474db078776cc3149d1be.jpg)

![d08fde7f32e84b67027baea785d399ba9fd0cea78f5d5371c5ce8fc4affaa19c.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/d08fde7f32e84b67027baea785d399ba9fd0cea78f5d5371c5ce8fc4affaa19c.jpg)

![dbb79b0e704a9fc96522d16606ec90783da2ee0e64b3951b3a4860cd06d37bce.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/dbb79b0e704a9fc96522d16606ec90783da2ee0e64b3951b3a4860cd06d37bce.jpg)

![e1412b413e5602d5cfe290367f0a4778d59fee846e7add306941d7c82df386e8.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/e1412b413e5602d5cfe290367f0a4778d59fee846e7add306941d7c82df386e8.jpg)

![e365c1a9db2a3e9147dd7b994602861c782b91d0a252760051c497c8f419d72f.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/e365c1a9db2a3e9147dd7b994602861c782b91d0a252760051c497c8f419d72f.jpg)

![e4f1fa03e59581dd4c0652259c6c1580f4ff4bf55dbb162cfde8d995781e1508.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/e4f1fa03e59581dd4c0652259c6c1580f4ff4bf55dbb162cfde8d995781e1508.jpg)

![e7d30591c2324d53f18935866504372abb0bc3f2582b0cf70047a10c24daa556.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/e7d30591c2324d53f18935866504372abb0bc3f2582b0cf70047a10c24daa556.jpg)

![ed093e2ff83287ca85af5a31c1001f63bad77761ea96e1b6260b7a04b821d17c.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/ed093e2ff83287ca85af5a31c1001f63bad77761ea96e1b6260b7a04b821d17c.jpg)

![f2997ea3dbecd0e9d27cfd8839731992b2328e377b16f1985d87fba9f2d720eb.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/f2997ea3dbecd0e9d27cfd8839731992b2328e377b16f1985d87fba9f2d720eb.jpg)

![f68dffe5dafd3728c6f268c5c9d199311369947b987056855dd64a298e1421d5.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/f68dffe5dafd3728c6f268c5c9d199311369947b987056855dd64a298e1421d5.jpg)

![fd0baa131ce84f1a96db245d4a55cf4c72f37fa53f2a876b13cedd2e0f7cca48.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/images/fd0baa131ce84f1a96db245d4a55cf4c72f37fa53f2a876b13cedd2e0f7cca48.jpg)

### Tables

![00b428fb852aa1bab6fb4909ca6c769385538ba75027080ffb14ce66961e6c41.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/00b428fb852aa1bab6fb4909ca6c769385538ba75027080ffb14ce66961e6c41.jpg)

![0e2178f2e55eb0c8984df4d28331740640ffb0c7674573936358edf14cab3cdb.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/0e2178f2e55eb0c8984df4d28331740640ffb0c7674573936358edf14cab3cdb.jpg)

![0f9457e30c32ebc65de404d56362b6be6edb39e1db346386d7eca8d188953112.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/0f9457e30c32ebc65de404d56362b6be6edb39e1db346386d7eca8d188953112.jpg)

![1d1b7ea817532225989cf8b12a6e03228d53ce429e2ac12e13a0b90577b6d866.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/1d1b7ea817532225989cf8b12a6e03228d53ce429e2ac12e13a0b90577b6d866.jpg)

![1fb26da21874b51f2f8c40693dc690ad1d4aab7906bea52d97f42c9fcdb3d0a1.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/1fb26da21874b51f2f8c40693dc690ad1d4aab7906bea52d97f42c9fcdb3d0a1.jpg)

![2697544f559e3111e88395924d55f3ee1612d0bee20a33b7f3b29b733b438d56.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/2697544f559e3111e88395924d55f3ee1612d0bee20a33b7f3b29b733b438d56.jpg)

![2def78883a16c284757a3dd8186e82cc96fd174a5768b21c74991816f39a29e5.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/2def78883a16c284757a3dd8186e82cc96fd174a5768b21c74991816f39a29e5.jpg)

![39929354f1680204df7c6739d7a0c34f9326961141b01d804737d0dc273bddfd.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/39929354f1680204df7c6739d7a0c34f9326961141b01d804737d0dc273bddfd.jpg)

![40565e49f2eb2e73f3e417b2b82e4192ccf4c6877bf327a42acb0d137a260a0b.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/40565e49f2eb2e73f3e417b2b82e4192ccf4c6877bf327a42acb0d137a260a0b.jpg)

![43fb40a1f170762f9e06cf14a9e53b42c71dd7c5f526098564fb8959e36e3490.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/43fb40a1f170762f9e06cf14a9e53b42c71dd7c5f526098564fb8959e36e3490.jpg)

![464db50a325984f77398dde5c660703df66b6b940a1540a93ae3a6ce6b39f5c5.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/464db50a325984f77398dde5c660703df66b6b940a1540a93ae3a6ce6b39f5c5.jpg)

![792a5f2dc2203ecd94cd36578e975f22c408cfed055da4277b6f1eb310073e5c.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/792a5f2dc2203ecd94cd36578e975f22c408cfed055da4277b6f1eb310073e5c.jpg)

![8660ba7b33dc61e6f020fde579e994e478d2950065aed7c34f7f0581ef7199f5.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/8660ba7b33dc61e6f020fde579e994e478d2950065aed7c34f7f0581ef7199f5.jpg)

![8c81fd088ce76ee254ad069a6283b673a29ca3064d9ea899d47d868ad5b1fc1f.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/8c81fd088ce76ee254ad069a6283b673a29ca3064d9ea899d47d868ad5b1fc1f.jpg)

![97770b7e00e62e553a8c51c507c161f05220dd8d0f47974931cc6bd4f68c853e.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/97770b7e00e62e553a8c51c507c161f05220dd8d0f47974931cc6bd4f68c853e.jpg)

![c3bd06f1c830cd98aaec01a307f7461c6097ecc117bc17a5795c0694535f3dcc.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/c3bd06f1c830cd98aaec01a307f7461c6097ecc117bc17a5795c0694535f3dcc.jpg)

![ce7b39ba1a8f61e40235c01c92d40e61510f66827be1ffb40e83b4e8044dd8f0.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/ce7b39ba1a8f61e40235c01c92d40e61510f66827be1ffb40e83b4e8044dd8f0.jpg)

![dc47c490c3e4e6a4bf1f7716f267bff8530149cb5c24e54ea4ad88f40e0f2d56.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/dc47c490c3e4e6a4bf1f7716f267bff8530149cb5c24e54ea4ad88f40e0f2d56.jpg)

![dca93efd701706d329a4404264d776bcea5a681fda982e7f4f2129260d48ea07.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/dca93efd701706d329a4404264d776bcea5a681fda982e7f4f2129260d48ea07.jpg)

![f21110330f8ab984fc454b8c14a242e287e9342fa6236f2e7b0ddcea5cbcb39a.jpg](../nips_results/273_DICEPTION_%20A%20Generalist%20Diffusion%20Model%20for%20Visual%20Perceptual%20Tasks/tables/f21110330f8ab984fc454b8c14a242e287e9342fa6236f2e7b0ddcea5cbcb39a.jpg)

## Nonlinear Laplacians: Tunable principal component analysis under directional prior information


### Images

![24d6983bc60573785f068fd1820693890918d9d5d9a37940d8ddbe4b4838818f.jpg](../nips_results/274_Nonlinear%20Laplacians_%20Tunable%20principal%20component%20analysis%20under%20directional%20prior%20information/images/24d6983bc60573785f068fd1820693890918d9d5d9a37940d8ddbe4b4838818f.jpg)

![2db3ad38de60086198f3b36930d36b0fe00797929777f6f7487c6d55982e9e65.jpg](../nips_results/274_Nonlinear%20Laplacians_%20Tunable%20principal%20component%20analysis%20under%20directional%20prior%20information/images/2db3ad38de60086198f3b36930d36b0fe00797929777f6f7487c6d55982e9e65.jpg)

![ae656ac8d246fec3454525334b425d37b63f1abbd80ebe45013eef484928fed2.jpg](../nips_results/274_Nonlinear%20Laplacians_%20Tunable%20principal%20component%20analysis%20under%20directional%20prior%20information/images/ae656ac8d246fec3454525334b425d37b63f1abbd80ebe45013eef484928fed2.jpg)

![bdfd99d05309dce7e9fcac29d6b23a708e0bf88fbbff65f12052c3439772e2f6.jpg](../nips_results/274_Nonlinear%20Laplacians_%20Tunable%20principal%20component%20analysis%20under%20directional%20prior%20information/images/bdfd99d05309dce7e9fcac29d6b23a708e0bf88fbbff65f12052c3439772e2f6.jpg)

![c79263fa2227f224621f666067a6720dabbb11f9f6117a14723ed3e75123e4b7.jpg](../nips_results/274_Nonlinear%20Laplacians_%20Tunable%20principal%20component%20analysis%20under%20directional%20prior%20information/images/c79263fa2227f224621f666067a6720dabbb11f9f6117a14723ed3e75123e4b7.jpg)

![f6d9fa658bbc4e04bf6dd2507edbaefd3565998e5ebc6f1ab40fa50d84ab4fdb.jpg](../nips_results/274_Nonlinear%20Laplacians_%20Tunable%20principal%20component%20analysis%20under%20directional%20prior%20information/images/f6d9fa658bbc4e04bf6dd2507edbaefd3565998e5ebc6f1ab40fa50d84ab4fdb.jpg)

## PhysX-3D: Physical-Grounded 3D Asset Generation


### Images

![4deb02e149e044696af4886e54a86f6569fdaa8520809fcfb722abf6a8f7d63e.jpg](../nips_results/275_PhysX-3D_%20Physical-Grounded%203D%20Asset%20Generation/images/4deb02e149e044696af4886e54a86f6569fdaa8520809fcfb722abf6a8f7d63e.jpg)

![65ece5b9927b6b13b9a9569528bcc4312ac991cbd46d8f303bfe067badde5d7c.jpg](../nips_results/275_PhysX-3D_%20Physical-Grounded%203D%20Asset%20Generation/images/65ece5b9927b6b13b9a9569528bcc4312ac991cbd46d8f303bfe067badde5d7c.jpg)

![8ce8eac641773883eda09adc2117aacc5c039adae65efa9b1e3750b50b1cdd8d.jpg](../nips_results/275_PhysX-3D_%20Physical-Grounded%203D%20Asset%20Generation/images/8ce8eac641773883eda09adc2117aacc5c039adae65efa9b1e3750b50b1cdd8d.jpg)

![a2cca9dff439d29ed11203a6e2bb09f64f54f52071e2b7262984670271fb939f.jpg](../nips_results/275_PhysX-3D_%20Physical-Grounded%203D%20Asset%20Generation/images/a2cca9dff439d29ed11203a6e2bb09f64f54f52071e2b7262984670271fb939f.jpg)

![a9b294fc2b13130ea4fd8aae74ffa72806651aa42f410d90d9b05db807224f1f.jpg](../nips_results/275_PhysX-3D_%20Physical-Grounded%203D%20Asset%20Generation/images/a9b294fc2b13130ea4fd8aae74ffa72806651aa42f410d90d9b05db807224f1f.jpg)

![b7e2474be5fcb8d07a6fcbce5b6c420280531d79c7dd8573364ce26c0554bb32.jpg](../nips_results/275_PhysX-3D_%20Physical-Grounded%203D%20Asset%20Generation/images/b7e2474be5fcb8d07a6fcbce5b6c420280531d79c7dd8573364ce26c0554bb32.jpg)

### Tables

![4a0f050e5a948f51ef86220d581ba26e8090a54707d6b94662b8ae760158327d.jpg](../nips_results/275_PhysX-3D_%20Physical-Grounded%203D%20Asset%20Generation/tables/4a0f050e5a948f51ef86220d581ba26e8090a54707d6b94662b8ae760158327d.jpg)

![887bb523d9d0521dec620e1dc9c42f244493a092d15949d9ecbd4fef6fbc774f.jpg](../nips_results/275_PhysX-3D_%20Physical-Grounded%203D%20Asset%20Generation/tables/887bb523d9d0521dec620e1dc9c42f244493a092d15949d9ecbd4fef6fbc774f.jpg)

## Self-Perturbed Anomaly-Aware Graph Dynamics for Multivariate Time-Series Anomaly Detection


### Images

![081bb4406a7a5cbc55c336703257f5780732a05209063e46f785acdd8c166e9b.jpg](../nips_results/276_Self-Perturbed%20Anomaly-Aware%20Graph%20Dynamics%20for%20Multivariate%20Time-Series%20Anomaly%20Detection/images/081bb4406a7a5cbc55c336703257f5780732a05209063e46f785acdd8c166e9b.jpg)

![133d55988e01bc6bbba0c8f8d1360235542d8da6a75d6b5a8cbbd1445864fecb.jpg](../nips_results/276_Self-Perturbed%20Anomaly-Aware%20Graph%20Dynamics%20for%20Multivariate%20Time-Series%20Anomaly%20Detection/images/133d55988e01bc6bbba0c8f8d1360235542d8da6a75d6b5a8cbbd1445864fecb.jpg)

![43e2f4d7c348eaf7b2d9ecb369ff83ba68e9b2477991a57500c19d8c9893dfaf.jpg](../nips_results/276_Self-Perturbed%20Anomaly-Aware%20Graph%20Dynamics%20for%20Multivariate%20Time-Series%20Anomaly%20Detection/images/43e2f4d7c348eaf7b2d9ecb369ff83ba68e9b2477991a57500c19d8c9893dfaf.jpg)

### Tables

![ab1d1b8151959a3bf1fd9b30583810a14f74a754b3d7348ee55a593bfdf0e256.jpg](../nips_results/276_Self-Perturbed%20Anomaly-Aware%20Graph%20Dynamics%20for%20Multivariate%20Time-Series%20Anomaly%20Detection/tables/ab1d1b8151959a3bf1fd9b30583810a14f74a754b3d7348ee55a593bfdf0e256.jpg)

![c56d80f87ebac24e51f844291e6e577be1fc8cece3f9b635fd08554cd9a4513d.jpg](../nips_results/276_Self-Perturbed%20Anomaly-Aware%20Graph%20Dynamics%20for%20Multivariate%20Time-Series%20Anomaly%20Detection/tables/c56d80f87ebac24e51f844291e6e577be1fc8cece3f9b635fd08554cd9a4513d.jpg)

![f53581b987cc729d1e286fda108f831e630c9d479b121f8ffceaf057a90f87f4.jpg](../nips_results/276_Self-Perturbed%20Anomaly-Aware%20Graph%20Dynamics%20for%20Multivariate%20Time-Series%20Anomaly%20Detection/tables/f53581b987cc729d1e286fda108f831e630c9d479b121f8ffceaf057a90f87f4.jpg)

## Purifying Approximate Differential Privacy with Randomized Post-processing


### Images

![5369c8dc51f8bf503ade77b77c1ecd7d76f7935684bf917e9c9328b3555d2001.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/images/5369c8dc51f8bf503ade77b77c1ecd7d76f7935684bf917e9c9328b3555d2001.jpg)

![624010dc76ff5d41d710ebc48a7d6529b2ddece55a1efd5a4116c1fd0c08b794.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/images/624010dc76ff5d41d710ebc48a7d6529b2ddece55a1efd5a4116c1fd0c08b794.jpg)

![6c38c5bcf1cb18e70dcbabb8689bedd871d72cd0653a404a56e842358cb5fc30.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/images/6c38c5bcf1cb18e70dcbabb8689bedd871d72cd0653a404a56e842358cb5fc30.jpg)

![e9dbb9849f797808e3ed432d25e4f511174699f729c38236e354a87598739e6b.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/images/e9dbb9849f797808e3ed432d25e4f511174699f729c38236e354a87598739e6b.jpg)

### Tables

![14764fb948d5167901b8978825b38f16e72d59bc6dd6e6db1b40c7b47400c9d1.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/tables/14764fb948d5167901b8978825b38f16e72d59bc6dd6e6db1b40c7b47400c9d1.jpg)

![1b9147fbdb7b47f2f7a913bf6f5cd3ac5f06371cec2d1815df8e1e10779ccbd7.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/tables/1b9147fbdb7b47f2f7a913bf6f5cd3ac5f06371cec2d1815df8e1e10779ccbd7.jpg)

![311db71cc70396581be4f12771881d389b5f1ce41fcc3b23b6deb7498c0c3e5a.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/tables/311db71cc70396581be4f12771881d389b5f1ce41fcc3b23b6deb7498c0c3e5a.jpg)

![4bd5d0073facbc1b7cdcd9a285526a609ab703ddde94c21279076ed90c834e80.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/tables/4bd5d0073facbc1b7cdcd9a285526a609ab703ddde94c21279076ed90c834e80.jpg)

![b641b7a4a91ddd7289819a083b1e16bc08fd222d432f13757ac25559f0856de6.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/tables/b641b7a4a91ddd7289819a083b1e16bc08fd222d432f13757ac25559f0856de6.jpg)

![c2a59a489e4557f955326dd1fec26411fb38c478022274d97341f8b5ad495912.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/tables/c2a59a489e4557f955326dd1fec26411fb38c478022274d97341f8b5ad495912.jpg)

![c677858e76fa2296d706f1199713fb295aa5089336c4faa7f648c4e03e0325c9.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/tables/c677858e76fa2296d706f1199713fb295aa5089336c4faa7f648c4e03e0325c9.jpg)

![d2ba149573bc3b839997f9f3b73564744169ea26c87248489d493df5d25e251d.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/tables/d2ba149573bc3b839997f9f3b73564744169ea26c87248489d493df5d25e251d.jpg)

![ebaf141724ad8c978a7047da2c355b89baea6b8ba728ecd9749199fc69574f6d.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/tables/ebaf141724ad8c978a7047da2c355b89baea6b8ba728ecd9749199fc69574f6d.jpg)

![fa944dd96f36da1507cf962d152459616f14908431246f98a882b2b9dc68ff1a.jpg](../nips_results/277_Purifying%20Approximate%20Differential%20Privacy%20with%20Randomized%20Post-processing/tables/fa944dd96f36da1507cf962d152459616f14908431246f98a882b2b9dc68ff1a.jpg)

## GraphMaster: Automated Graph Synthesis via LLM Agents in Data-Limited Environments


### Images

![2e398758ef8ae4e9923ca2868e0fd8cb265f58bd74e9c1bee9c25c9813fbf331.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/images/2e398758ef8ae4e9923ca2868e0fd8cb265f58bd74e9c1bee9c25c9813fbf331.jpg)

![437321e9c4d07f99fd27bd736fa2afa384cb33425f09d60c8ed46594866b2378.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/images/437321e9c4d07f99fd27bd736fa2afa384cb33425f09d60c8ed46594866b2378.jpg)

![83ce0c3775fe85bb151fa6116f36f4a304fe0eb89361e3732be8869e208bdc42.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/images/83ce0c3775fe85bb151fa6116f36f4a304fe0eb89361e3732be8869e208bdc42.jpg)

![8447df867016782f7b4e36eecbe8a56f0de0fe1e6cc63659738754b832247759.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/images/8447df867016782f7b4e36eecbe8a56f0de0fe1e6cc63659738754b832247759.jpg)

![9c610f90b0c926117e8a9078bd044bb638e1d413f2d093817857d6a283d0641e.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/images/9c610f90b0c926117e8a9078bd044bb638e1d413f2d093817857d6a283d0641e.jpg)

![ac977b197dfb3fe6fce540428a129352523abbe43d541343795758ce8c55aef1.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/images/ac977b197dfb3fe6fce540428a129352523abbe43d541343795758ce8c55aef1.jpg)

![bedefce45568527ee6f3516444a79bb58c69ef3471d484b317e78d3171953d51.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/images/bedefce45568527ee6f3516444a79bb58c69ef3471d484b317e78d3171953d51.jpg)

![e47dff3bec318347ac2e5ce4d9b2ac9f99659dfb175e3c3531c783843cb33aa6.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/images/e47dff3bec318347ac2e5ce4d9b2ac9f99659dfb175e3c3531c783843cb33aa6.jpg)

![f2db3497e7ff523f521b7c1163af4eec2d2d79c2968a7054e6127d985a28854f.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/images/f2db3497e7ff523f521b7c1163af4eec2d2d79c2968a7054e6127d985a28854f.jpg)

![f4917e3b942128652521bd3cf40bec9d7fe586929376e770ec43ef41205e400f.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/images/f4917e3b942128652521bd3cf40bec9d7fe586929376e770ec43ef41205e400f.jpg)

### Tables

![023c4eaf68008af1b2f6d8e8dd97fca39ce97d07bec679185ea7e59b8a583796.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/tables/023c4eaf68008af1b2f6d8e8dd97fca39ce97d07bec679185ea7e59b8a583796.jpg)

![1234828859f4b51cd184431f48a6696d57eff46837ff860e1dbe98a4d613e246.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/tables/1234828859f4b51cd184431f48a6696d57eff46837ff860e1dbe98a4d613e246.jpg)

![6d242df3310cfa0af1f80297e316e2936998980173f6333f0284238426bd6fac.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/tables/6d242df3310cfa0af1f80297e316e2936998980173f6333f0284238426bd6fac.jpg)

![87f697d36cc5d8371bc36c6021b18cb6cdde4400aead44dd223a5f945e022ebd.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/tables/87f697d36cc5d8371bc36c6021b18cb6cdde4400aead44dd223a5f945e022ebd.jpg)

![95156dae811df899e5e55a42c884b876491413fc926f4b6684fffcaee12372a3.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/tables/95156dae811df899e5e55a42c884b876491413fc926f4b6684fffcaee12372a3.jpg)

![f83a8e31f2e3d64bee63d3fc95663eb33afeb1a97ecebf47f3223703d4155a16.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/tables/f83a8e31f2e3d64bee63d3fc95663eb33afeb1a97ecebf47f3223703d4155a16.jpg)

![fdbfbf9b79f492192d6fa0b1a914ac4c17a6d1f3544b176b0fa343c098f1604f.jpg](../nips_results/278_GraphMaster_%20Automated%20Graph%20Synthesis%20via%20LLM%20Agents%20in%20Data-Limited%20Environments/tables/fdbfbf9b79f492192d6fa0b1a914ac4c17a6d1f3544b176b0fa343c098f1604f.jpg)

## Option-aware Temporally Abstracted Value for Offline Goal-Conditioned Reinforcement Learning


### Images

![1bf5082b1acb7dbdb796deb60cc340a263bcde2399fbb1987b52139b72281ad5.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/images/1bf5082b1acb7dbdb796deb60cc340a263bcde2399fbb1987b52139b72281ad5.jpg)

![39a8f6381a1a5ff4553523e5d7e7c859c7ce8955d1459413a929114a929c43c5.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/images/39a8f6381a1a5ff4553523e5d7e7c859c7ce8955d1459413a929114a929c43c5.jpg)

![a0a1bd3c87b50cc576b27c9f602e8141a49077c7070e2620f11407941d2d20e1.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/images/a0a1bd3c87b50cc576b27c9f602e8141a49077c7070e2620f11407941d2d20e1.jpg)

![ac0e9942afe503898927b0a19d2d49ee503db9e22cf135b4bd3586bd6b453714.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/images/ac0e9942afe503898927b0a19d2d49ee503db9e22cf135b4bd3586bd6b453714.jpg)

![b962aacbc74b9487c7d7367448a3de198d4310e2929f16e63aceadfd10921742.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/images/b962aacbc74b9487c7d7367448a3de198d4310e2929f16e63aceadfd10921742.jpg)

![c4938ff1978220558de6beadae1536372348bada0e31e046b64fae661571f347.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/images/c4938ff1978220558de6beadae1536372348bada0e31e046b64fae661571f347.jpg)

![d07d61dee0a36808d9ed98c792de58a7bfc2d12502abcfb82f652d8640036eff.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/images/d07d61dee0a36808d9ed98c792de58a7bfc2d12502abcfb82f652d8640036eff.jpg)

![f71719720360a91c3a605f6f17030df95d7781bc8269652e3053102661f87f93.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/images/f71719720360a91c3a605f6f17030df95d7781bc8269652e3053102661f87f93.jpg)

![f7840c8aff2e22f659e0aff2e2ed9d4c9c326f320c0d8d698adde58145d3686a.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/images/f7840c8aff2e22f659e0aff2e2ed9d4c9c326f320c0d8d698adde58145d3686a.jpg)

### Tables

![764c29ebc68b85f82f22c4246a664141a8b29f4add85f7cc5479548bbd62110d.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/tables/764c29ebc68b85f82f22c4246a664141a8b29f4add85f7cc5479548bbd62110d.jpg)

![819319c0cf4daa26dbf389adf68f1ef5243d3234d38a9752f03724ea8f6da756.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/tables/819319c0cf4daa26dbf389adf68f1ef5243d3234d38a9752f03724ea8f6da756.jpg)

![81b7f5c0fbb068234ca193974dbc17b4006e1444322d6f25bda762103dd07c21.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/tables/81b7f5c0fbb068234ca193974dbc17b4006e1444322d6f25bda762103dd07c21.jpg)

![a9640de5b378108548aace3c48375970e8afd4862c7d5906498009a860cec162.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/tables/a9640de5b378108548aace3c48375970e8afd4862c7d5906498009a860cec162.jpg)

![ab8de99ef1730cd7d9495db7ebc7c865b29e28b8c2dec65946ef0067642ff0a8.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/tables/ab8de99ef1730cd7d9495db7ebc7c865b29e28b8c2dec65946ef0067642ff0a8.jpg)

![c483deca7e3b28f49bce1bd0fc245b554837ec9ca40fddbc28503acb7f3c0100.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/tables/c483deca7e3b28f49bce1bd0fc245b554837ec9ca40fddbc28503acb7f3c0100.jpg)

![d01375cbe02e24112c327c883dc4f38b3c7ec8eb01121efba3f63ca1f6491091.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/tables/d01375cbe02e24112c327c883dc4f38b3c7ec8eb01121efba3f63ca1f6491091.jpg)

![f564b9d68177c539688c99b99ecfb33cb4450e96d297fd74bd4c6ca89be1d2a0.jpg](../nips_results/279_Option-aware%20Temporally%20Abstracted%20Value%20for%20Offline%20Goal-Conditioned%20Reinforcement%20Learning/tables/f564b9d68177c539688c99b99ecfb33cb4450e96d297fd74bd4c6ca89be1d2a0.jpg)

## Sample-Adaptivity Tradeoff in On-Demand Sampling


### Tables

![7a6306e08b6280984a656ed793d8e77c24a421a07b5ed42983cbb3d10b019f53.jpg](../nips_results/280_Sample-Adaptivity%20Tradeoff%20in%20On-Demand%20Sampling/tables/7a6306e08b6280984a656ed793d8e77c24a421a07b5ed42983cbb3d10b019f53.jpg)

## FlowFeat: Pixel-Dense Embedding of Motion Profiles


### Images

![0c9e984abc0e13117d729b279cd39d554d66d6f3a4f9ab37f88e6ad6d4ff054f.jpg](../nips_results/281_FlowFeat_%20Pixel-Dense%20Embedding%20of%20Motion%20Profiles/images/0c9e984abc0e13117d729b279cd39d554d66d6f3a4f9ab37f88e6ad6d4ff054f.jpg)

![c99be4eaa1c51a0782387bdb70048c0db1927a3f982de7ac5304804c288dbbf9.jpg](../nips_results/281_FlowFeat_%20Pixel-Dense%20Embedding%20of%20Motion%20Profiles/images/c99be4eaa1c51a0782387bdb70048c0db1927a3f982de7ac5304804c288dbbf9.jpg)

![cbae3878d7ba73dfca14514f72a856abd03b93c157fa71365e62087c74236db7.jpg](../nips_results/281_FlowFeat_%20Pixel-Dense%20Embedding%20of%20Motion%20Profiles/images/cbae3878d7ba73dfca14514f72a856abd03b93c157fa71365e62087c74236db7.jpg)

![dd437aa7f3d259d64450390b69ac2c23e913c2da5b5ea8f598a99cbf9dcaf6d9.jpg](../nips_results/281_FlowFeat_%20Pixel-Dense%20Embedding%20of%20Motion%20Profiles/images/dd437aa7f3d259d64450390b69ac2c23e913c2da5b5ea8f598a99cbf9dcaf6d9.jpg)

![e44477bd0d25f22ccaa83e4eef040adcd5cf20c7cc6ae7a59112b4620843e62e.jpg](../nips_results/281_FlowFeat_%20Pixel-Dense%20Embedding%20of%20Motion%20Profiles/images/e44477bd0d25f22ccaa83e4eef040adcd5cf20c7cc6ae7a59112b4620843e62e.jpg)

![e6c8f9b720a3adf744990eac4c6d8014ec68a618d69b25be93b63a30163007b1.jpg](../nips_results/281_FlowFeat_%20Pixel-Dense%20Embedding%20of%20Motion%20Profiles/images/e6c8f9b720a3adf744990eac4c6d8014ec68a618d69b25be93b63a30163007b1.jpg)

### Tables

![468d01f038b724f2a9438befc6d6065ecdd89afca359aa8bb4454b1e4d82ec47.jpg](../nips_results/281_FlowFeat_%20Pixel-Dense%20Embedding%20of%20Motion%20Profiles/tables/468d01f038b724f2a9438befc6d6065ecdd89afca359aa8bb4454b1e4d82ec47.jpg)

![d210e316997dd56f5bc4006274fdbf5ce6d4c940aaee164f4d5f4188205235dd.jpg](../nips_results/281_FlowFeat_%20Pixel-Dense%20Embedding%20of%20Motion%20Profiles/tables/d210e316997dd56f5bc4006274fdbf5ce6d4c940aaee164f4d5f4188205235dd.jpg)

![db1227046e4c5b281f32330a3fa612a2b3aef1f1a141bdde674fa2c9ae9b7263.jpg](../nips_results/281_FlowFeat_%20Pixel-Dense%20Embedding%20of%20Motion%20Profiles/tables/db1227046e4c5b281f32330a3fa612a2b3aef1f1a141bdde674fa2c9ae9b7263.jpg)

![e46011e54886135e1e0eabdc1f2429afc3988806841d4ff56162f5c8b856a028.jpg](../nips_results/281_FlowFeat_%20Pixel-Dense%20Embedding%20of%20Motion%20Profiles/tables/e46011e54886135e1e0eabdc1f2429afc3988806841d4ff56162f5c8b856a028.jpg)

## Non-Clairvoyant Scheduling with Progress Bars


### Images

![15fe8516b560e31c1c21960ec8dd1f64f599cd265346c5bb5b9df3a68ca468bd.jpg](../nips_results/282_Non-Clairvoyant%20Scheduling%20with%20Progress%20Bars/images/15fe8516b560e31c1c21960ec8dd1f64f599cd265346c5bb5b9df3a68ca468bd.jpg)

![1f2e40a633592c583a725758bc003607e1197fe04cbbcf96428efdd60c38f4cd.jpg](../nips_results/282_Non-Clairvoyant%20Scheduling%20with%20Progress%20Bars/images/1f2e40a633592c583a725758bc003607e1197fe04cbbcf96428efdd60c38f4cd.jpg)

![9e1b5a141ca20546437df68f3f6abd8a8e1ddf723e0f42d5a5c9db24c58ba6bd.jpg](../nips_results/282_Non-Clairvoyant%20Scheduling%20with%20Progress%20Bars/images/9e1b5a141ca20546437df68f3f6abd8a8e1ddf723e0f42d5a5c9db24c58ba6bd.jpg)

![c1b1f9a1155638eabc17da58c09f828811ea692b050de9ed4e7cfa882c4ba2a5.jpg](../nips_results/282_Non-Clairvoyant%20Scheduling%20with%20Progress%20Bars/images/c1b1f9a1155638eabc17da58c09f828811ea692b050de9ed4e7cfa882c4ba2a5.jpg)

![d330e5a24aaebec415ef4a537ceaa2786279d5188c6891c3fb5e2cfaa3a6e264.jpg](../nips_results/282_Non-Clairvoyant%20Scheduling%20with%20Progress%20Bars/images/d330e5a24aaebec415ef4a537ceaa2786279d5188c6891c3fb5e2cfaa3a6e264.jpg)

![d657769ddec93c6266c87d5acac4d0de97a4dbec908e69d19af3a7b462f32b3f.jpg](../nips_results/282_Non-Clairvoyant%20Scheduling%20with%20Progress%20Bars/images/d657769ddec93c6266c87d5acac4d0de97a4dbec908e69d19af3a7b462f32b3f.jpg)

### Tables

![4f036f7918c4e1e7f27c77ffeba0b9cc7ba3350f1732d2ba585d88ba43c61632.jpg](../nips_results/282_Non-Clairvoyant%20Scheduling%20with%20Progress%20Bars/tables/4f036f7918c4e1e7f27c77ffeba0b9cc7ba3350f1732d2ba585d88ba43c61632.jpg)

![722d101438409275acf93e72173a8c31adb96e7b7b751c70955a3db684e562dc.jpg](../nips_results/282_Non-Clairvoyant%20Scheduling%20with%20Progress%20Bars/tables/722d101438409275acf93e72173a8c31adb96e7b7b751c70955a3db684e562dc.jpg)

![fbd71b349f562688005a4dd630f0a490dfe4ce806525ff415f7f2bfbdd13186e.jpg](../nips_results/282_Non-Clairvoyant%20Scheduling%20with%20Progress%20Bars/tables/fbd71b349f562688005a4dd630f0a490dfe4ce806525ff415f7f2bfbdd13186e.jpg)

## KLASS: KL-Guided Fast Inference in Masked Diffusion Models


### Images

![6c03471bf553ee1f0d815e0b2834ead3c016ad3344677d45acc8f67eb7c19483.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/images/6c03471bf553ee1f0d815e0b2834ead3c016ad3344677d45acc8f67eb7c19483.jpg)

![dc23ef62e5016b38f1e5bfe610e70bf6fb7a5ad6bdf30465532fe5c5a9da2ea4.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/images/dc23ef62e5016b38f1e5bfe610e70bf6fb7a5ad6bdf30465532fe5c5a9da2ea4.jpg)

![ecab3fb3992a1d2c0f7bb6706e0d4f8724e519a01c5ed16c5f6e0ca7509da254.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/images/ecab3fb3992a1d2c0f7bb6706e0d4f8724e519a01c5ed16c5f6e0ca7509da254.jpg)

### Tables

![10b1a5a09b3a17959f85170c5b30edcfec5804028b66b80c80f5da70dd691a12.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/10b1a5a09b3a17959f85170c5b30edcfec5804028b66b80c80f5da70dd691a12.jpg)

![25e9a6dfb158ee186e88c5f23a95c7d2eb52885961fe9385d504333b334b5b5f.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/25e9a6dfb158ee186e88c5f23a95c7d2eb52885961fe9385d504333b334b5b5f.jpg)

![299de462a9c6edd7d20edf9bfdaa2b8963344d710a596221e78445b6ea44b0e7.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/299de462a9c6edd7d20edf9bfdaa2b8963344d710a596221e78445b6ea44b0e7.jpg)

![2b23e17803aca97c2c2d422a3f226ce1d2a2c96ea91d2749a01bbf28a7de1152.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/2b23e17803aca97c2c2d422a3f226ce1d2a2c96ea91d2749a01bbf28a7de1152.jpg)

![3008e6fc3c0ddf5d8abd21e0f1254f1c19b59a7af256250b01698c5a86f5e4c3.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/3008e6fc3c0ddf5d8abd21e0f1254f1c19b59a7af256250b01698c5a86f5e4c3.jpg)

![5f44f6b5232dd9a948181a079f5cd1f09ec3ce2ba531a75cdd184d266676cbc9.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/5f44f6b5232dd9a948181a079f5cd1f09ec3ce2ba531a75cdd184d266676cbc9.jpg)

![6c8970fcf41fca7e951688d4529a6f174787e4ee6bf898d7682e7d2b3fa202e9.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/6c8970fcf41fca7e951688d4529a6f174787e4ee6bf898d7682e7d2b3fa202e9.jpg)

![6d6d49cf3f4f8d0c66d91ec4164790c134dc1399c6263c1ac0dad57689273bf7.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/6d6d49cf3f4f8d0c66d91ec4164790c134dc1399c6263c1ac0dad57689273bf7.jpg)

![82506378eb2c7d6f273327c1cc7bc6a8bb1902de81cfb33cced4bb95c958fc1e.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/82506378eb2c7d6f273327c1cc7bc6a8bb1902de81cfb33cced4bb95c958fc1e.jpg)

![8b21341a066fe7a49057fcf8758352ba40c957e8951e4982a9a3f5cc038e4f2f.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/8b21341a066fe7a49057fcf8758352ba40c957e8951e4982a9a3f5cc038e4f2f.jpg)

![932c92ce4757d0a94f060dc0941eabc7b2394cba73eea48a75a40611b0465058.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/932c92ce4757d0a94f060dc0941eabc7b2394cba73eea48a75a40611b0465058.jpg)

![a4da42b9dc120bfc48fda6e6020aa5bf4c786bfe3406945d590f34e5a292e641.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/a4da42b9dc120bfc48fda6e6020aa5bf4c786bfe3406945d590f34e5a292e641.jpg)

![e4b5156a9c9abd861e4adf61adda94bfc3845340db35088008acbabaefc14bc6.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/e4b5156a9c9abd861e4adf61adda94bfc3845340db35088008acbabaefc14bc6.jpg)

![e53ecd85780ff9aedc0540a1f539777e79a7d7c5de1031f3e69e2f5044e7ebb6.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/e53ecd85780ff9aedc0540a1f539777e79a7d7c5de1031f3e69e2f5044e7ebb6.jpg)

![e65e170f72cbeb6a372bdc577cd6baca3de0565a34d5f3df57292ee13395fd8b.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/e65e170f72cbeb6a372bdc577cd6baca3de0565a34d5f3df57292ee13395fd8b.jpg)

![e75cd9cf1f633f207b152f40af71c730c147aebcb62332304e7c4821a0dae792.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/e75cd9cf1f633f207b152f40af71c730c147aebcb62332304e7c4821a0dae792.jpg)

![e7b4e249d07fcb22bfe5c9e593924f41a88f57623bfe9337c336851bd8356c1b.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/e7b4e249d07fcb22bfe5c9e593924f41a88f57623bfe9337c336851bd8356c1b.jpg)

![e82be36ed2bbea9c30511b46e32cf334fa5f06064ba41780ffd3a40a929455e6.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/e82be36ed2bbea9c30511b46e32cf334fa5f06064ba41780ffd3a40a929455e6.jpg)

![f0b970148455962bf35191c762e00e8f1e75b75cef32a115ef9f013616e05fd9.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/f0b970148455962bf35191c762e00e8f1e75b75cef32a115ef9f013616e05fd9.jpg)

![fadb03773154f7013a04c588f2688875ed78c4e0041f836b55bd68db7fe119b7.jpg](../nips_results/283_KLASS_%20KL-Guided%20Fast%20Inference%20in%20Masked%20Diffusion%20Models/tables/fadb03773154f7013a04c588f2688875ed78c4e0041f836b55bd68db7fe119b7.jpg)

## TokenSwap: A Lightweight Method to Disrupt Memorized Sequences in LLMs


### Images

![4d2ba0a647e89b8e4a8c00bd2a6378540ac51a2d6e7342fce08bde57feacc1a6.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/images/4d2ba0a647e89b8e4a8c00bd2a6378540ac51a2d6e7342fce08bde57feacc1a6.jpg)

![757048258adae5eb07ed1fb739a71d868280dd13f3f190d9a688f35351d5d3e2.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/images/757048258adae5eb07ed1fb739a71d868280dd13f3f190d9a688f35351d5d3e2.jpg)

![8b58fa8443f4baa4cd94833f46f64e8ae2cf9f6ff32281d9f38b70ad2bfeddd9.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/images/8b58fa8443f4baa4cd94833f46f64e8ae2cf9f6ff32281d9f38b70ad2bfeddd9.jpg)

![b255a942923096a9c6ce14afb2097b3687f25a6c46e1f524e37f1bf317c2bffe.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/images/b255a942923096a9c6ce14afb2097b3687f25a6c46e1f524e37f1bf317c2bffe.jpg)

![c551afdebcafcad2806f527552d91228b4aed67c7bd646eafbd4f9219cb792c3.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/images/c551afdebcafcad2806f527552d91228b4aed67c7bd646eafbd4f9219cb792c3.jpg)

### Tables

![504b17e71799df0bef9f0ca244490992aacdfceb69c8923877ee04996ea787c0.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/504b17e71799df0bef9f0ca244490992aacdfceb69c8923877ee04996ea787c0.jpg)

![5376ae19daca3bf74123040e036b370ff92250c9977e63e4242d7dee259a4105.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/5376ae19daca3bf74123040e036b370ff92250c9977e63e4242d7dee259a4105.jpg)

![704f9fb0ca2a5677455c35ac71f300102827f7faeeaeffffae9a22b64874a910.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/704f9fb0ca2a5677455c35ac71f300102827f7faeeaeffffae9a22b64874a910.jpg)

![821456f4373b87db27e66856bd2460cdb7eca43a9899ec8c31c3f251915ae622.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/821456f4373b87db27e66856bd2460cdb7eca43a9899ec8c31c3f251915ae622.jpg)

![8786c846ffc5ad2b34d6c8208b7877028e2ee2564bea1b7b67c785230aa95d6d.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/8786c846ffc5ad2b34d6c8208b7877028e2ee2564bea1b7b67c785230aa95d6d.jpg)

![a7da42ee5e3a2e02d44e987ef14260c6594540b753f30d58db39cd4bb5c955b2.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/a7da42ee5e3a2e02d44e987ef14260c6594540b753f30d58db39cd4bb5c955b2.jpg)

![b0d28fa7eb474090eddc31861aa636fa2889ee5e6f69194807b50f4e321c1b6d.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/b0d28fa7eb474090eddc31861aa636fa2889ee5e6f69194807b50f4e321c1b6d.jpg)

![bf8b4812fc290eb5c71766c444c2c6c6eef2a55344486f43b034172ebbf0f5d5.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/bf8b4812fc290eb5c71766c444c2c6c6eef2a55344486f43b034172ebbf0f5d5.jpg)

![c5f89fc80784920b2865210674e0bbfc91242c00c36c289effbcf1878236afdf.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/c5f89fc80784920b2865210674e0bbfc91242c00c36c289effbcf1878236afdf.jpg)

![cdff43cc1ffc2d5c21f6471754eb6147fa9f9202332eaaa4d6646a9a556b2367.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/cdff43cc1ffc2d5c21f6471754eb6147fa9f9202332eaaa4d6646a9a556b2367.jpg)

![cf5c82de32dd928f773da33272533f4e46c9e7eb557a775ccb7be378127cf7ef.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/cf5c82de32dd928f773da33272533f4e46c9e7eb557a775ccb7be378127cf7ef.jpg)

![cf8a73a4fe5e1c24c9dafaef6d9a3454a8f24cbb684765dde9ca91ab5463a17c.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/cf8a73a4fe5e1c24c9dafaef6d9a3454a8f24cbb684765dde9ca91ab5463a17c.jpg)

![f7026119a97968a05488e60c4cc2848890cc6fd0c388343747ad27c707d267a9.jpg](../nips_results/284_TokenSwap_%20A%20Lightweight%20Method%20to%20Disrupt%20Memorized%20Sequences%20in%20LLMs/tables/f7026119a97968a05488e60c4cc2848890cc6fd0c388343747ad27c707d267a9.jpg)

## Learnable Sampler Distillation for Discrete Diffusion Models


### Images

![26a5bcffa1d865517bd102cbea01075edc0a69844e4bf9461a8e6e6dc14a5f18.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/images/26a5bcffa1d865517bd102cbea01075edc0a69844e4bf9461a8e6e6dc14a5f18.jpg)

![8447c69d814172fe300b9ffcb56975282de6fd04cd8134ad5efad552b1e6544d.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/images/8447c69d814172fe300b9ffcb56975282de6fd04cd8134ad5efad552b1e6544d.jpg)

![a6861ebeadc18526031c11cdab6797f5d76319791a51df892cbfb7207b57fe30.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/images/a6861ebeadc18526031c11cdab6797f5d76319791a51df892cbfb7207b57fe30.jpg)

### Tables

![1195764ecc961002ca3d70696681a7f5f3ea058fec1d177be350a1582b56389f.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/1195764ecc961002ca3d70696681a7f5f3ea058fec1d177be350a1582b56389f.jpg)

![161dcc7e391aad9a20981d44954ab36e616770dcb882669ebaae67af9207d844.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/161dcc7e391aad9a20981d44954ab36e616770dcb882669ebaae67af9207d844.jpg)

![1d5544278daed9e3cf03988e9c172e62efd21cc070ed9795e7ae091dc1e873c6.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/1d5544278daed9e3cf03988e9c172e62efd21cc070ed9795e7ae091dc1e873c6.jpg)

![2b8ba255ecb620f1c375b172044184d26b28f6e4bd45618dd91441ada0d23bde.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/2b8ba255ecb620f1c375b172044184d26b28f6e4bd45618dd91441ada0d23bde.jpg)

![30111c5e8a95f2673c31bd9a6be0d9be71f71cbc4b05d495ea1966b017ab3895.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/30111c5e8a95f2673c31bd9a6be0d9be71f71cbc4b05d495ea1966b017ab3895.jpg)

![3655bc01c2e73a6e38a1b7f2cecc3ff10a474741065bf56a5035aa7c6ef9b935.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/3655bc01c2e73a6e38a1b7f2cecc3ff10a474741065bf56a5035aa7c6ef9b935.jpg)

![547dbba6c099858254915479c56982dfbb44ad72d82cdac8f72e8642dc79c8d9.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/547dbba6c099858254915479c56982dfbb44ad72d82cdac8f72e8642dc79c8d9.jpg)

![695d380e3c7cd3e73a9a6df83a38f9dacb51afecc1c92bc405bb96729bbc2ad5.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/695d380e3c7cd3e73a9a6df83a38f9dacb51afecc1c92bc405bb96729bbc2ad5.jpg)

![76f3537a8564640d22743ab70ed20bde73a8b637da45b55a619d316bc904c259.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/76f3537a8564640d22743ab70ed20bde73a8b637da45b55a619d316bc904c259.jpg)

![7a61facc1a25f8c5dece2bef2e899ad67cd7296d73b5531b1e45eac8e62811ca.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/7a61facc1a25f8c5dece2bef2e899ad67cd7296d73b5531b1e45eac8e62811ca.jpg)

![874a108a2892cc927cee18de20d4ab7094bed99416f21b07e8b248f3246bba02.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/874a108a2892cc927cee18de20d4ab7094bed99416f21b07e8b248f3246bba02.jpg)

![89e98d40a52197b17c266dc10b9ba85e456fa6454bd185bb7d0e0e2ed3a63238.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/89e98d40a52197b17c266dc10b9ba85e456fa6454bd185bb7d0e0e2ed3a63238.jpg)

![8aa72d17b111f450d2c4a3cbd4c3577816ed871e3351cc083c33d511a9d171fa.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/8aa72d17b111f450d2c4a3cbd4c3577816ed871e3351cc083c33d511a9d171fa.jpg)

![965750d898721519961bb894d57a2ca2e6082adbab3b4f2df1cd0932a486db0d.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/965750d898721519961bb894d57a2ca2e6082adbab3b4f2df1cd0932a486db0d.jpg)

![96bfa7a1e82c9a35873d03eb60e6877aa5b19383ee434e726b642e3d8b59978b.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/96bfa7a1e82c9a35873d03eb60e6877aa5b19383ee434e726b642e3d8b59978b.jpg)

![a20ba70ef30b397d200a19980b6267332f7b734e80b4a0557f37f49789ce31e4.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/a20ba70ef30b397d200a19980b6267332f7b734e80b4a0557f37f49789ce31e4.jpg)

![af648aa2b263055e6ec32921b4412f8375a1188dd2d012b19f24893cba4809ee.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/af648aa2b263055e6ec32921b4412f8375a1188dd2d012b19f24893cba4809ee.jpg)

![ce09218ac33a82562fad7e20e5b83e88ef89d77d9d4a6077c35e16eae0933da0.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/ce09218ac33a82562fad7e20e5b83e88ef89d77d9d4a6077c35e16eae0933da0.jpg)

![fbc0885a6f87b7c31bfe6348bec2108fd89bc25191a64c0fd70006d02e2a44a3.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/fbc0885a6f87b7c31bfe6348bec2108fd89bc25191a64c0fd70006d02e2a44a3.jpg)

![fd8f833e5edf2c5db2ca7e10fbbd041188e8d84b273715aeb9117441c0ba3cab.jpg](../nips_results/285_Learnable%20Sampler%20Distillation%20for%20Discrete%20Diffusion%20Models/tables/fd8f833e5edf2c5db2ca7e10fbbd041188e8d84b273715aeb9117441c0ba3cab.jpg)

## Flash Invariant Point Attention


### Images

![38f9119ffd43c76467e8822c9ff1b36c63ac059f5cc1eba3d7d6db28415b7f3e.jpg](../nips_results/286_Flash%20Invariant%20Point%20Attention/images/38f9119ffd43c76467e8822c9ff1b36c63ac059f5cc1eba3d7d6db28415b7f3e.jpg)

![84c2b7f3dc5bb9777257414e68d8dcedb4627f0645c3da4e41503fc9daba8f1a.jpg](../nips_results/286_Flash%20Invariant%20Point%20Attention/images/84c2b7f3dc5bb9777257414e68d8dcedb4627f0645c3da4e41503fc9daba8f1a.jpg)

![89771fb586d622b038bc048912b9b6dfe5a5d6d9a8eab6e49abacc1330edf52b.jpg](../nips_results/286_Flash%20Invariant%20Point%20Attention/images/89771fb586d622b038bc048912b9b6dfe5a5d6d9a8eab6e49abacc1330edf52b.jpg)

![91a374e282731035c442ece156e26a1149c11af9419bcf5ebc2d774bb2d63f0a.jpg](../nips_results/286_Flash%20Invariant%20Point%20Attention/images/91a374e282731035c442ece156e26a1149c11af9419bcf5ebc2d774bb2d63f0a.jpg)

![9b81296b3c33c6ba9be0b5a25250be9edfcb4e3703d7cef00d7ba6cc5f29f7e4.jpg](../nips_results/286_Flash%20Invariant%20Point%20Attention/images/9b81296b3c33c6ba9be0b5a25250be9edfcb4e3703d7cef00d7ba6cc5f29f7e4.jpg)

![9be055a57c4484810504efec647208db9510d86d951985617ebfb2456b753af8.jpg](../nips_results/286_Flash%20Invariant%20Point%20Attention/images/9be055a57c4484810504efec647208db9510d86d951985617ebfb2456b753af8.jpg)

![d93c27586df12e39db670a3fdc67d932975c45292eae1b2dfb2a2baea1abb67c.jpg](../nips_results/286_Flash%20Invariant%20Point%20Attention/images/d93c27586df12e39db670a3fdc67d932975c45292eae1b2dfb2a2baea1abb67c.jpg)

![e8d8658fd7b9f1a2ce3f8cd36d1426ac745033fed4ca066ac0a5dc4ac233711e.jpg](../nips_results/286_Flash%20Invariant%20Point%20Attention/images/e8d8658fd7b9f1a2ce3f8cd36d1426ac745033fed4ca066ac0a5dc4ac233711e.jpg)

### Tables

![1b34c7bbefe07d692d7dca900e645b7f89e480043bc30df2e56b58a9737b1f04.jpg](../nips_results/286_Flash%20Invariant%20Point%20Attention/tables/1b34c7bbefe07d692d7dca900e645b7f89e480043bc30df2e56b58a9737b1f04.jpg)

![40d687bcc01cceba144779d26e4db5f70cd245209a3b058b34afee0ce3c1b64c.jpg](../nips_results/286_Flash%20Invariant%20Point%20Attention/tables/40d687bcc01cceba144779d26e4db5f70cd245209a3b058b34afee0ce3c1b64c.jpg)

## The World Is Bigger: A Computationally-Embedded Perspective on the Big World Hypothesis


### Images

![495e9350adbb23d8e6a46cf7a094bbe0577fa5827bbe115dc153b7660487c6b3.jpg](../nips_results/287_The%20World%20Is%20Bigger_%20A%20Computationally-Embedded%20Perspective%20on%20the%20Big%20World%20Hypothesis/images/495e9350adbb23d8e6a46cf7a094bbe0577fa5827bbe115dc153b7660487c6b3.jpg)

![59d7190b40a2aa9b01decb4335d1c365e731f3dd1f523afcb3d6fa4088518b28.jpg](../nips_results/287_The%20World%20Is%20Bigger_%20A%20Computationally-Embedded%20Perspective%20on%20the%20Big%20World%20Hypothesis/images/59d7190b40a2aa9b01decb4335d1c365e731f3dd1f523afcb3d6fa4088518b28.jpg)

![837ee038b1d45ac2281c8a1b987b79520f3714ff801e967b4560f170be4a9231.jpg](../nips_results/287_The%20World%20Is%20Bigger_%20A%20Computationally-Embedded%20Perspective%20on%20the%20Big%20World%20Hypothesis/images/837ee038b1d45ac2281c8a1b987b79520f3714ff801e967b4560f170be4a9231.jpg)

![99b29bad3dc36c80498d0701435641cdd0a21b71c98b233dab73db3aba089046.jpg](../nips_results/287_The%20World%20Is%20Bigger_%20A%20Computationally-Embedded%20Perspective%20on%20the%20Big%20World%20Hypothesis/images/99b29bad3dc36c80498d0701435641cdd0a21b71c98b233dab73db3aba089046.jpg)

![fe90f2e42c26a00b65a5e09c205dc492e8e62e91791ecc474a8b77dc1c05b315.jpg](../nips_results/287_The%20World%20Is%20Bigger_%20A%20Computationally-Embedded%20Perspective%20on%20the%20Big%20World%20Hypothesis/images/fe90f2e42c26a00b65a5e09c205dc492e8e62e91791ecc474a8b77dc1c05b315.jpg)

## Exploration via Feature Perturbation in Contextual Bandits


### Images

![026c05b2e8ee2720cbe8182ed4fa64bf2f52f8ad08f154402b446e243366b36b.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/images/026c05b2e8ee2720cbe8182ed4fa64bf2f52f8ad08f154402b446e243366b36b.jpg)

![1ff85506f36820c87868dcdf5015729775ed52a2ae5cf69221476973bc8ca875.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/images/1ff85506f36820c87868dcdf5015729775ed52a2ae5cf69221476973bc8ca875.jpg)

![34c455e31e6b94a208c7e3ecc8b9c6e6110be6178d7a6e058f1a575d18cc8888.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/images/34c455e31e6b94a208c7e3ecc8b9c6e6110be6178d7a6e058f1a575d18cc8888.jpg)

![65852ff2ced3e394844fdca73bac7cd6b17f8c8fbad8967c8869106efac3c2f3.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/images/65852ff2ced3e394844fdca73bac7cd6b17f8c8fbad8967c8869106efac3c2f3.jpg)

![cdf30e9d973b93ea876636ea2ff58eb2f8f149e9ab02a828daf8ad8f0f6ce7c5.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/images/cdf30e9d973b93ea876636ea2ff58eb2f8f149e9ab02a828daf8ad8f0f6ce7c5.jpg)

![d1f22287c62a207c14bb261d98050ec0e7336653e41c7f7d94b9b3af568ed1d7.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/images/d1f22287c62a207c14bb261d98050ec0e7336653e41c7f7d94b9b3af568ed1d7.jpg)

![e11615e66650586111e54eabb55c877e5245b7d51c26a4888ee379fc958b1519.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/images/e11615e66650586111e54eabb55c877e5245b7d51c26a4888ee379fc958b1519.jpg)

![e69107c958f4dca6f3fd8b67dbcd81eaeb0158f40310f2dc2fce5ea3d74dd870.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/images/e69107c958f4dca6f3fd8b67dbcd81eaeb0158f40310f2dc2fce5ea3d74dd870.jpg)

![f14d56552f4950485aed5d3de64e97b8cade132cb455745948fa9344fcc320c3.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/images/f14d56552f4950485aed5d3de64e97b8cade132cb455745948fa9344fcc320c3.jpg)

![ff18a54f89f2214b44d88a3e11a02544dd4772a3d2af1f23fc5588266e90876d.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/images/ff18a54f89f2214b44d88a3e11a02544dd4772a3d2af1f23fc5588266e90876d.jpg)

### Tables

![1a88e6aadebad21605c308c7290d54725ab5594369112093c19714d500e58e03.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/tables/1a88e6aadebad21605c308c7290d54725ab5594369112093c19714d500e58e03.jpg)

![2b83ba52665b2473b3af11b38b66877cea1ba917052e6c324a012a0d424416e5.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/tables/2b83ba52665b2473b3af11b38b66877cea1ba917052e6c324a012a0d424416e5.jpg)

![2c4e21695f7c09d61da6ef6a1c857b4692bc912dd43efaeda3697c85736edc71.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/tables/2c4e21695f7c09d61da6ef6a1c857b4692bc912dd43efaeda3697c85736edc71.jpg)

![a2db7bfac7db68490affe8123ab25bb2ba1456b7d7951afe429d3496c0c212d0.jpg](../nips_results/288_Exploration%20via%20Feature%20Perturbation%20in%20Contextual%20Bandits/tables/a2db7bfac7db68490affe8123ab25bb2ba1456b7d7951afe429d3496c0c212d0.jpg)

## URDF-Anything: Constructing Articulated Objects with 3D Multimodal Language Model


### Images

![0b67eeed88846c62fb31c7ebacea97d31f3152992a2189d2861c01ded20e9209.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/images/0b67eeed88846c62fb31c7ebacea97d31f3152992a2189d2861c01ded20e9209.jpg)

![3aead95d648eac3113251b7cce1f07d5231526ae02181c2cfbc923d820555f52.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/images/3aead95d648eac3113251b7cce1f07d5231526ae02181c2cfbc923d820555f52.jpg)

![42dff17b2a55c4d5cd36d3776368e6843b4fbadbd84a30dc6f7994c123b14038.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/images/42dff17b2a55c4d5cd36d3776368e6843b4fbadbd84a30dc6f7994c123b14038.jpg)

![574edaacd3c29881aa1eb08ec85b30302b79afa4fc0783d80b1a08b2b34d6e65.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/images/574edaacd3c29881aa1eb08ec85b30302b79afa4fc0783d80b1a08b2b34d6e65.jpg)

![748e2093fa1d9f1153a2bc9c0e65483f207f11ecdab8fe5e963e15f54ad455a3.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/images/748e2093fa1d9f1153a2bc9c0e65483f207f11ecdab8fe5e963e15f54ad455a3.jpg)

![a123dc4f7da1dd9e28bfe6d334a22826b444a1546fd43c8155e03c9811da0984.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/images/a123dc4f7da1dd9e28bfe6d334a22826b444a1546fd43c8155e03c9811da0984.jpg)

![c5cd6a29fee5172fc3772083f0ea989ca2b62ff1573e24c99e66a19f26c728a9.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/images/c5cd6a29fee5172fc3772083f0ea989ca2b62ff1573e24c99e66a19f26c728a9.jpg)

![ce9ae530868fe8221dab825e0b6caff74e290ff5278ee5748e3474853bb35315.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/images/ce9ae530868fe8221dab825e0b6caff74e290ff5278ee5748e3474853bb35315.jpg)

![eb566427928269996aea92cad8d1b483cad0b6917aa59ae8d444dea729c11d9b.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/images/eb566427928269996aea92cad8d1b483cad0b6917aa59ae8d444dea729c11d9b.jpg)

### Tables

![249147c89b0042797270c1781d2678598a76e6060df9aae5998835f1d516053f.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/249147c89b0042797270c1781d2678598a76e6060df9aae5998835f1d516053f.jpg)

![2d945a41ea2ee07f116629aeb311b87f848f13236e453ec9a238238d7791f882.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/2d945a41ea2ee07f116629aeb311b87f848f13236e453ec9a238238d7791f882.jpg)

![2f066f11364a76286c16496c05705915f3555700437ddc83b498fe1e8534c204.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/2f066f11364a76286c16496c05705915f3555700437ddc83b498fe1e8534c204.jpg)

![74febd305029a54c3fecabe1ea83c9a1be224fb03e5b1331a143823ad210db36.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/74febd305029a54c3fecabe1ea83c9a1be224fb03e5b1331a143823ad210db36.jpg)

![7f4a6069730c77ca8869de0cefeb8e029109425ec5eacb1bdd8f3c28bcd67cf3.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/7f4a6069730c77ca8869de0cefeb8e029109425ec5eacb1bdd8f3c28bcd67cf3.jpg)

![840186e37054d9e005fa80fb63ed19d93ecbd5fb405c823244c3fbfe9b380fe2.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/840186e37054d9e005fa80fb63ed19d93ecbd5fb405c823244c3fbfe9b380fe2.jpg)

![952476d3f7f94289761980052c30f0053f0e52e7ea63ee0b7bb4d590c3a6b0ba.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/952476d3f7f94289761980052c30f0053f0e52e7ea63ee0b7bb4d590c3a6b0ba.jpg)

![9e30a66b1d3c2bc5e7139d7996bc2364224b0d848b880b73881d7909c86302e3.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/9e30a66b1d3c2bc5e7139d7996bc2364224b0d848b880b73881d7909c86302e3.jpg)

![b6b946d270e075197ce67e4640d7aae4922454fb29fa515f7e9ceca349ade6d4.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/b6b946d270e075197ce67e4640d7aae4922454fb29fa515f7e9ceca349ade6d4.jpg)

![bfad07e9eadb29eb10ca44d6a418e6d67f42e2967df174474e22c8db8e2c79b4.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/bfad07e9eadb29eb10ca44d6a418e6d67f42e2967df174474e22c8db8e2c79b4.jpg)

![d6ad60e0422f00fab76f55f657b4fbdafbf5c5329a08fa44405136045a00d651.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/d6ad60e0422f00fab76f55f657b4fbdafbf5c5329a08fa44405136045a00d651.jpg)

![dd29347dac2753f713ee60f4b65c89ed6caa9fa3051b8debe6970c6faf67c41f.jpg](../nips_results/289_URDF-Anything_%20Constructing%20Articulated%20Objects%20with%203D%20Multimodal%20Language%20Model/tables/dd29347dac2753f713ee60f4b65c89ed6caa9fa3051b8debe6970c6faf67c41f.jpg)

## Transfer Faster, Price Smarter: Minimax Dynamic Pricing under Cross-Market Preference Shift


### Images

![07ffda7726e09e9d280a80667a9281d91a006092c3077fbab74294495b002962.jpg](../nips_results/290_Transfer%20Faster%2C%20Price%20Smarter_%20Minimax%20Dynamic%20Pricing%20under%20Cross-Market%20Preference%20Shift/images/07ffda7726e09e9d280a80667a9281d91a006092c3077fbab74294495b002962.jpg)

![1589d9aa570f3bdb5b25511ae3d67a7234c55415c5ece6ddc35d5857b3968963.jpg](../nips_results/290_Transfer%20Faster%2C%20Price%20Smarter_%20Minimax%20Dynamic%20Pricing%20under%20Cross-Market%20Preference%20Shift/images/1589d9aa570f3bdb5b25511ae3d67a7234c55415c5ece6ddc35d5857b3968963.jpg)

![613cd0035603e42b5f3c08bca04e31b720543c04b6508c3d1903d89615bf9a86.jpg](../nips_results/290_Transfer%20Faster%2C%20Price%20Smarter_%20Minimax%20Dynamic%20Pricing%20under%20Cross-Market%20Preference%20Shift/images/613cd0035603e42b5f3c08bca04e31b720543c04b6508c3d1903d89615bf9a86.jpg)

![7a0dda8975d8aedca5c7c73e0f079abfd8aba8eea510c82bf1f5bc28ac2c5b9f.jpg](../nips_results/290_Transfer%20Faster%2C%20Price%20Smarter_%20Minimax%20Dynamic%20Pricing%20under%20Cross-Market%20Preference%20Shift/images/7a0dda8975d8aedca5c7c73e0f079abfd8aba8eea510c82bf1f5bc28ac2c5b9f.jpg)

![87268716af2ac46cf2056b587416b2a0bcc0be3c47955a3527a13999c7d5ef9b.jpg](../nips_results/290_Transfer%20Faster%2C%20Price%20Smarter_%20Minimax%20Dynamic%20Pricing%20under%20Cross-Market%20Preference%20Shift/images/87268716af2ac46cf2056b587416b2a0bcc0be3c47955a3527a13999c7d5ef9b.jpg)

![f17029c433899f6a13f63268b0365e02db6e91c8f539a21862aca24a9183ca10.jpg](../nips_results/290_Transfer%20Faster%2C%20Price%20Smarter_%20Minimax%20Dynamic%20Pricing%20under%20Cross-Market%20Preference%20Shift/images/f17029c433899f6a13f63268b0365e02db6e91c8f539a21862aca24a9183ca10.jpg)

### Tables

![0430e13c51ab77dbe5cba4f5db2c3dbceac865d4db562144ae04b9d079aa1cb8.jpg](../nips_results/290_Transfer%20Faster%2C%20Price%20Smarter_%20Minimax%20Dynamic%20Pricing%20under%20Cross-Market%20Preference%20Shift/tables/0430e13c51ab77dbe5cba4f5db2c3dbceac865d4db562144ae04b9d079aa1cb8.jpg)

![e9c8e92ff231b3794ed12fe74d6a13a3cd9ab603b22c01680506f88e67a10b7d.jpg](../nips_results/290_Transfer%20Faster%2C%20Price%20Smarter_%20Minimax%20Dynamic%20Pricing%20under%20Cross-Market%20Preference%20Shift/tables/e9c8e92ff231b3794ed12fe74d6a13a3cd9ab603b22c01680506f88e67a10b7d.jpg)

![ec9dc20c275505ae7880968dbbb5fac6a5237db05b0f96ce9ab367269ce75908.jpg](../nips_results/290_Transfer%20Faster%2C%20Price%20Smarter_%20Minimax%20Dynamic%20Pricing%20under%20Cross-Market%20Preference%20Shift/tables/ec9dc20c275505ae7880968dbbb5fac6a5237db05b0f96ce9ab367269ce75908.jpg)

## Cloud4D: Estimating Cloud Properties at a High Spatial and Temporal Resolution


### Images

![1a1225a6bac79f385784c84c7f9e8326a0f54d282a9153747b321dd71ed88eda.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/1a1225a6bac79f385784c84c7f9e8326a0f54d282a9153747b321dd71ed88eda.jpg)

![36621f7ee79f107181db9cfe44573f5b9e8c2f8896678aee57a734838b4d9a64.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/36621f7ee79f107181db9cfe44573f5b9e8c2f8896678aee57a734838b4d9a64.jpg)

![406f0f1846af8359c0137abd2d4d7e12eea0a9fc014a3ce207d29805c88014c0.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/406f0f1846af8359c0137abd2d4d7e12eea0a9fc014a3ce207d29805c88014c0.jpg)

![4c07575e276f9fcaa60ad7e33b83153250c2a5e7173a42c6dd22440d793fb1a6.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/4c07575e276f9fcaa60ad7e33b83153250c2a5e7173a42c6dd22440d793fb1a6.jpg)

![548c71c682231ad6882a0b33cbfdad4450c8b9010ba3211abb9298e27b0a2ead.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/548c71c682231ad6882a0b33cbfdad4450c8b9010ba3211abb9298e27b0a2ead.jpg)

![9317023834c2020763f260a576424a4289122f94f56329dc0ae64feb6dd62e22.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/9317023834c2020763f260a576424a4289122f94f56329dc0ae64feb6dd62e22.jpg)

![9d4d70e104f18452d31bcfeaa2b3001a13eb5ce763cdabe1cc18c2f0b6d18676.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/9d4d70e104f18452d31bcfeaa2b3001a13eb5ce763cdabe1cc18c2f0b6d18676.jpg)

![a6f529cd529d8ad8ee8c2f31c89140be9e74edd575a6790f366e48c927bb16e7.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/a6f529cd529d8ad8ee8c2f31c89140be9e74edd575a6790f366e48c927bb16e7.jpg)

![bc2e0556b882bb8637a0f241b1fe056ec820d6d0e0dae2543900c359be80d763.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/bc2e0556b882bb8637a0f241b1fe056ec820d6d0e0dae2543900c359be80d763.jpg)

![da649d4d860a881118e145cd76290e42df82219b657981843863a9590d05f415.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/da649d4d860a881118e145cd76290e42df82219b657981843863a9590d05f415.jpg)

![de709a891927cab063bd196eab958459fcc119decb34ea0eca40d44b967737ca.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/de709a891927cab063bd196eab958459fcc119decb34ea0eca40d44b967737ca.jpg)

![f60f6a7807024fe4c5a638b5b363bdf85d819f94bf8d2ae39c3198a6fbfdd794.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/f60f6a7807024fe4c5a638b5b363bdf85d819f94bf8d2ae39c3198a6fbfdd794.jpg)

![f853c57a2585bc7bc7730e6d87ac0349260e0505d5f49d43f06918d68ffea8a1.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/images/f853c57a2585bc7bc7730e6d87ac0349260e0505d5f49d43f06918d68ffea8a1.jpg)

### Tables

![4c182e03d773e6d187887f161bc3a58c6602cebc5d00f1ced3f509461a4c2dd7.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/tables/4c182e03d773e6d187887f161bc3a58c6602cebc5d00f1ced3f509461a4c2dd7.jpg)

![4f635568cfa982029aed60fa0d54b0936eee91abb31ccf9b20df9dc76e8f64c5.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/tables/4f635568cfa982029aed60fa0d54b0936eee91abb31ccf9b20df9dc76e8f64c5.jpg)

![60dc7a5d1512907abab70410040500ea5ac47ebe82227a4344a1a96a26aab26a.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/tables/60dc7a5d1512907abab70410040500ea5ac47ebe82227a4344a1a96a26aab26a.jpg)

![9a8788b98b0ab6017822b8929966d52b8b0dc5df31dbe01e84f8ed82031ce2af.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/tables/9a8788b98b0ab6017822b8929966d52b8b0dc5df31dbe01e84f8ed82031ce2af.jpg)

![d9c5b2b1207ea5e3115dd9d9bf70b01dd870231743af3a6117f4fdbd8ef07de3.jpg](../nips_results/291_Cloud4D_%20Estimating%20Cloud%20Properties%20at%20a%20High%20Spatial%20and%20Temporal%20Resolution/tables/d9c5b2b1207ea5e3115dd9d9bf70b01dd870231743af3a6117f4fdbd8ef07de3.jpg)

## Talk2Event: Grounded Understanding of Dynamic Scenes from Event Cameras


### Images

![0147d10e39af9b56c473e2ecbf2ac1600fc5dc7908718a8f3a4557ed5d0540e4.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/0147d10e39af9b56c473e2ecbf2ac1600fc5dc7908718a8f3a4557ed5d0540e4.jpg)

![341cb2b0166e1ba738c22b7dd291df30a0d0f1fa8780912069d568f99958505e.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/341cb2b0166e1ba738c22b7dd291df30a0d0f1fa8780912069d568f99958505e.jpg)

![397c7493289c74c397698cd53b12a151cf486cfc1cc0f447794c508f0bfdcd1c.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/397c7493289c74c397698cd53b12a151cf486cfc1cc0f447794c508f0bfdcd1c.jpg)

![401a4a5897b77ee71db02c2bcaeabc3c48d1dc6ab4d9bd32f11d4499b053db0c.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/401a4a5897b77ee71db02c2bcaeabc3c48d1dc6ab4d9bd32f11d4499b053db0c.jpg)

![4571d78229b5557b8e2637bbaa86333de8a453ce8bd9260f49ecabbdb53e5f60.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/4571d78229b5557b8e2637bbaa86333de8a453ce8bd9260f49ecabbdb53e5f60.jpg)

![4690d871acd516d7ef6a5f44b40173a77c94b3a4fd9a970d86e778e91348ba61.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/4690d871acd516d7ef6a5f44b40173a77c94b3a4fd9a970d86e778e91348ba61.jpg)

![8a5c8ee2fd41f56390235d38b3d44c40b175c9f111e1958b11a8680fa21d1a32.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/8a5c8ee2fd41f56390235d38b3d44c40b175c9f111e1958b11a8680fa21d1a32.jpg)

![976063e7b6a7345278ef22aac7bea2b6e690b3d47dcb4863443d4016bb2f8fc6.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/976063e7b6a7345278ef22aac7bea2b6e690b3d47dcb4863443d4016bb2f8fc6.jpg)

![9bb090e468159b376ae1ae6a24ce67f65ed6ca3de8b1c1de5a8bef87f6562a1d.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/9bb090e468159b376ae1ae6a24ce67f65ed6ca3de8b1c1de5a8bef87f6562a1d.jpg)

![a2aa75b8b85f4249061438d658956dcdd123c8bf0b5d64a82d678522a1394f48.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/a2aa75b8b85f4249061438d658956dcdd123c8bf0b5d64a82d678522a1394f48.jpg)

![c9ba58739d803732b279f67b67bce6e5145a2be3ff7b0ba57097323d751efecb.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/c9ba58739d803732b279f67b67bce6e5145a2be3ff7b0ba57097323d751efecb.jpg)

![d35a86d331ab4562f54e4e26cd5e8f63ac56db59d320bc0445dbcf04158c34ef.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/d35a86d331ab4562f54e4e26cd5e8f63ac56db59d320bc0445dbcf04158c34ef.jpg)

![d80f0da69e4b120d98fbd4f2a90e0685ee2095a248cd099c74b978015e485e21.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/d80f0da69e4b120d98fbd4f2a90e0685ee2095a248cd099c74b978015e485e21.jpg)

![d8f57ecf56543a960854566851047f491b0225e58608480907ecec47f7219faa.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/d8f57ecf56543a960854566851047f491b0225e58608480907ecec47f7219faa.jpg)

![dcf7113d6e78f30c45933d70c2b9b207e46c042e18c8d910730d08f3381e6758.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/dcf7113d6e78f30c45933d70c2b9b207e46c042e18c8d910730d08f3381e6758.jpg)

![edd93e7c605f24c10fb2ea0b4057f6268fb7e7d2792e060d0727c4fe7c43b91b.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/edd93e7c605f24c10fb2ea0b4057f6268fb7e7d2792e060d0727c4fe7c43b91b.jpg)

![f73228a7f668382f1f4c2390c4d69ec73cae5a1dc11c0bf93e46e4c3a22778c7.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/images/f73228a7f668382f1f4c2390c4d69ec73cae5a1dc11c0bf93e46e4c3a22778c7.jpg)

### Tables

![020f19c9d6f9bc2887e10f5ff859a9514070f939187c4d24d6b4b5339bb255a3.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/020f19c9d6f9bc2887e10f5ff859a9514070f939187c4d24d6b4b5339bb255a3.jpg)

![09859fa9d93ad41c3244fa4fee1890af39bd422f1feaf3ed2f8cecb14d3171bc.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/09859fa9d93ad41c3244fa4fee1890af39bd422f1feaf3ed2f8cecb14d3171bc.jpg)

![0a2f6acbefcdbc4337560601c10d3a191f97968f544870449912dac3c71fe7bc.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/0a2f6acbefcdbc4337560601c10d3a191f97968f544870449912dac3c71fe7bc.jpg)

![2debf7e75a9c019a93425ad0641e46c27a47ae1a045d34c59d129989739b96f6.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/2debf7e75a9c019a93425ad0641e46c27a47ae1a045d34c59d129989739b96f6.jpg)

![37ddca14805bdf8d85c86626490e2723670a755e4ecff22fe8657b9a824cd3b9.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/37ddca14805bdf8d85c86626490e2723670a755e4ecff22fe8657b9a824cd3b9.jpg)

![3a44c461ba6c30de7fbb14419114a169f12698161256ce63d886f5bbef836382.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/3a44c461ba6c30de7fbb14419114a169f12698161256ce63d886f5bbef836382.jpg)

![53296a1035ec6a81f21d6ab30cade66168f173bb1011a6dd1173ead697160280.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/53296a1035ec6a81f21d6ab30cade66168f173bb1011a6dd1173ead697160280.jpg)

![71350d8a47131541d59296a22deae83ff027bc5211e02534e63e153dcc325db2.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/71350d8a47131541d59296a22deae83ff027bc5211e02534e63e153dcc325db2.jpg)

![829223a4170aa04488e0c3fa09075ccebdf87b9f897d708c53386735251819d5.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/829223a4170aa04488e0c3fa09075ccebdf87b9f897d708c53386735251819d5.jpg)

![85f500b0ddb1b0ff1fc36de47240186b3849aa0d25f8536db745fe65193d3cf4.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/85f500b0ddb1b0ff1fc36de47240186b3849aa0d25f8536db745fe65193d3cf4.jpg)

![8634b11d5ec1b1b7f9746951acb37745fb9658ec56011184f535ae54d69ced44.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/8634b11d5ec1b1b7f9746951acb37745fb9658ec56011184f535ae54d69ced44.jpg)

![890e01fe5994231ed5d6763d9f005949407e9b1ef411ca4abd35c2bb8fa72a52.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/890e01fe5994231ed5d6763d9f005949407e9b1ef411ca4abd35c2bb8fa72a52.jpg)

![d6383edc95a15fdd7f8e6252dae6b6a6a87f95b7b1af72e811a3362bd03e1d95.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/d6383edc95a15fdd7f8e6252dae6b6a6a87f95b7b1af72e811a3362bd03e1d95.jpg)

![ef24fa8ceacec2a0387965ecdc6c55d081e4746c388f209221370b532faff264.jpg](../nips_results/292_Talk2Event_%20Grounded%20Understanding%20of%20Dynamic%20Scenes%20from%20Event%20Cameras/tables/ef24fa8ceacec2a0387965ecdc6c55d081e4746c388f209221370b532faff264.jpg)

## Enigmata:  Scaling Logical Reasoning in Large Language Models with Synthetic Verifiable Puzzles


### Images

![034cf9d17cbd74a47fa1042a005f8a4f9b8b4b0513048d5255d02f602ef09c3b.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/images/034cf9d17cbd74a47fa1042a005f8a4f9b8b4b0513048d5255d02f602ef09c3b.jpg)

![0ff68058500daa71efd309419168d53e2ff3e8b2a653a81e5435ee6dda6d8262.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/images/0ff68058500daa71efd309419168d53e2ff3e8b2a653a81e5435ee6dda6d8262.jpg)

![13727f87c329e046a6b231efc18fe359514a22ae48d99d19abb517ceec1ffaf9.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/images/13727f87c329e046a6b231efc18fe359514a22ae48d99d19abb517ceec1ffaf9.jpg)

![14a7a0f94842be253b5b21ecf918c49e23858467271042dee6163aa5d7ab24c8.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/images/14a7a0f94842be253b5b21ecf918c49e23858467271042dee6163aa5d7ab24c8.jpg)

![6a72984b9ed1d0a14dc1383cd4dee5e4d83f36de7cabccbb9a46614a6eb2ce91.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/images/6a72984b9ed1d0a14dc1383cd4dee5e4d83f36de7cabccbb9a46614a6eb2ce91.jpg)

![7a176dd26570ffc8f15b99b66a94b0aa5e1071a0a8a4c0b8e46cb626fb9abc3f.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/images/7a176dd26570ffc8f15b99b66a94b0aa5e1071a0a8a4c0b8e46cb626fb9abc3f.jpg)

![cc9536bea974cdcfd7aaefe3ffbff606c68068781a1d6e39f20a014eda7bc2b7.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/images/cc9536bea974cdcfd7aaefe3ffbff606c68068781a1d6e39f20a014eda7bc2b7.jpg)

![fc717101ec9e8b1b70fd1c0a8ac2548a44b99738d160af849728ef38811de063.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/images/fc717101ec9e8b1b70fd1c0a8ac2548a44b99738d160af849728ef38811de063.jpg)

### Tables

![010d780da85bfe8b230281e6b38628b5ca70955ff68fd2ab301d39f88236709a.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/010d780da85bfe8b230281e6b38628b5ca70955ff68fd2ab301d39f88236709a.jpg)

![3cf7091febbabfdd6b64e97206d4febbcc31b937cb61f12d7c06586b9dce5a05.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/3cf7091febbabfdd6b64e97206d4febbcc31b937cb61f12d7c06586b9dce5a05.jpg)

![459858866f182d0fb739b7ee7e2ddb4a5b9ad3b80c9a4989ebd8bbe0ea76b3d8.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/459858866f182d0fb739b7ee7e2ddb4a5b9ad3b80c9a4989ebd8bbe0ea76b3d8.jpg)

![46bc9db79289753e0b4cca4a0fc62d424260657ccd25ecf6601119e1d6b18b79.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/46bc9db79289753e0b4cca4a0fc62d424260657ccd25ecf6601119e1d6b18b79.jpg)

![4d1fa7db8b298bfb2c6a3c01ba2022bc95e67470cf7ffbde400e184327a931d4.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/4d1fa7db8b298bfb2c6a3c01ba2022bc95e67470cf7ffbde400e184327a931d4.jpg)

![57f17571f6a32ef6fd55bdf19719a0141c144284a3c4273965bdbfb9d6b919d4.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/57f17571f6a32ef6fd55bdf19719a0141c144284a3c4273965bdbfb9d6b919d4.jpg)

![747dbd4b0eb99c33980d9e87f10ddbf6f2ea49e36ca2b0e7a0f2a004ae17ace0.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/747dbd4b0eb99c33980d9e87f10ddbf6f2ea49e36ca2b0e7a0f2a004ae17ace0.jpg)

![7fc663dc39c26605b62b084317605fc9eb87d4cbaedae44cafa1b6f39a66104e.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/7fc663dc39c26605b62b084317605fc9eb87d4cbaedae44cafa1b6f39a66104e.jpg)

![92d478435cd9ee51fb2111d0756cb5f48c1d9ccb8d5ba75fafff41eda629da90.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/92d478435cd9ee51fb2111d0756cb5f48c1d9ccb8d5ba75fafff41eda629da90.jpg)

![9878d67695c81789508ebe2c1c20a1036afa12653ba3e35b198dbfc26ca517c6.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/9878d67695c81789508ebe2c1c20a1036afa12653ba3e35b198dbfc26ca517c6.jpg)

![9ffa98826af4008349151eaf84073f2540a9d4f0d2b42cfa10bd07be93059cc9.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/9ffa98826af4008349151eaf84073f2540a9d4f0d2b42cfa10bd07be93059cc9.jpg)

![c25aa6d2680e51737ddbbbb223b2604cac7d4a11c5d23f0b682b60c89bfcf26c.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/c25aa6d2680e51737ddbbbb223b2604cac7d4a11c5d23f0b682b60c89bfcf26c.jpg)

![e640c4e7576667fa0989f4c681a5ef55e414723d301740cc1861ba17e5db1904.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/e640c4e7576667fa0989f4c681a5ef55e414723d301740cc1861ba17e5db1904.jpg)

![f88244177bd5b0e8eeb6150a6513ceb4d115a75bdbdfa8d4293e9cded641bdc5.jpg](../nips_results/293_Enigmata_%20%20Scaling%20Logical%20Reasoning%20in%20Large%20Language%20Models%20with%20Synthetic%20Verifiable%20Puzzles/tables/f88244177bd5b0e8eeb6150a6513ceb4d115a75bdbdfa8d4293e9cded641bdc5.jpg)

## When Less Language is More: Language-Reasoning Disentanglement Makes LLMs Better Multilingual Reasoners


### Images

![272b2f026fbe937a27dbc807cd82bc62158aa8bc8fb1eadf4cadfdba26a2e063.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/272b2f026fbe937a27dbc807cd82bc62158aa8bc8fb1eadf4cadfdba26a2e063.jpg)

![3ef3c7db02cf11ecae4bb4c54f84b3389380c3f8cfe242e90517fc5270f5bd27.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/3ef3c7db02cf11ecae4bb4c54f84b3389380c3f8cfe242e90517fc5270f5bd27.jpg)

![46ff1e0a9f4a33a020ef22cfb2b84d594cdc407b471d97c6ad2dca007f737182.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/46ff1e0a9f4a33a020ef22cfb2b84d594cdc407b471d97c6ad2dca007f737182.jpg)

![4ce3221483e409f3bef19fbbc864aee4705bffe9efa4d276db80541d4f4d07d0.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/4ce3221483e409f3bef19fbbc864aee4705bffe9efa4d276db80541d4f4d07d0.jpg)

![5bb3caf28fc45ee6d073a602c1708116c779751ac2056b998180fb87e5467f30.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/5bb3caf28fc45ee6d073a602c1708116c779751ac2056b998180fb87e5467f30.jpg)

![5ce4518502fbea49a3454a358fa5e654b8e8c2ba9038a91482a8bfa2753cff15.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/5ce4518502fbea49a3454a358fa5e654b8e8c2ba9038a91482a8bfa2753cff15.jpg)

![606b387125ac14adda96da3b075e19a77340143b26ddc61ed30b0b66092a5800.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/606b387125ac14adda96da3b075e19a77340143b26ddc61ed30b0b66092a5800.jpg)

![60dae77d6a860433474d5e896735fd2339f8d9ff953c3d56c32f570ddb97f27d.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/60dae77d6a860433474d5e896735fd2339f8d9ff953c3d56c32f570ddb97f27d.jpg)

![72d899a956ada52c0774a8018b312ba188ae2e2275d278e0229df401374d7d66.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/72d899a956ada52c0774a8018b312ba188ae2e2275d278e0229df401374d7d66.jpg)

![775a2f5a5f23dae1f0cc772a4f52199e31e3f377d83be48f281b1981f3fcff38.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/775a2f5a5f23dae1f0cc772a4f52199e31e3f377d83be48f281b1981f3fcff38.jpg)

![82c338bfd882487728204b82c2e0d90ebc7ffca72e390160e5e3f0c294712df4.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/82c338bfd882487728204b82c2e0d90ebc7ffca72e390160e5e3f0c294712df4.jpg)

![841d408d6e90c23f7fd72bf0260d932126fd9f73374f411a719beb0706678949.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/841d408d6e90c23f7fd72bf0260d932126fd9f73374f411a719beb0706678949.jpg)

![8d9194db8f13662b267c8f6d5a1857f53b5ce7df1582f5020aa402372ed9f659.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/8d9194db8f13662b267c8f6d5a1857f53b5ce7df1582f5020aa402372ed9f659.jpg)

![8df6287ea1734ea3e14cbaa1c67a0188b47c01d5a1ead8ca3e9256f343d146d5.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/8df6287ea1734ea3e14cbaa1c67a0188b47c01d5a1ead8ca3e9256f343d146d5.jpg)

![935157ba5265a5b4efe0f86f85c7fe7bc894e829dcca536fbfdc754f67b81d28.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/935157ba5265a5b4efe0f86f85c7fe7bc894e829dcca536fbfdc754f67b81d28.jpg)

![a03067f1ae78e0d1d117990ea713b5009219051400f4b85a52302c404d2d25b2.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/a03067f1ae78e0d1d117990ea713b5009219051400f4b85a52302c404d2d25b2.jpg)

![a05bb5f143528657a8a4ab26a761f355105f4b481737cf678e74f674414d5459.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/a05bb5f143528657a8a4ab26a761f355105f4b481737cf678e74f674414d5459.jpg)

![a961e0b0cc234e2c7349d9d57cfcb7adda7b04d92a4206968ab19bf74b5b292d.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/a961e0b0cc234e2c7349d9d57cfcb7adda7b04d92a4206968ab19bf74b5b292d.jpg)

![bb0815e339fdbcf3ba807991359c55368ca7930855f58c2fb52d0af93f08d70f.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/bb0815e339fdbcf3ba807991359c55368ca7930855f58c2fb52d0af93f08d70f.jpg)

![c6315cb34ab83e7db65a77a039d0e01ee7a5aa2c0129d984053057e705a4cbc1.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/c6315cb34ab83e7db65a77a039d0e01ee7a5aa2c0129d984053057e705a4cbc1.jpg)

![c97277ac6803e946235ceabbdcd516fea686a8acb09afa1b7c3697748ab8baff.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/c97277ac6803e946235ceabbdcd516fea686a8acb09afa1b7c3697748ab8baff.jpg)

![e4321cc89452fa943680c220906b8888d0e5e487608da458338c1fd616575dc7.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/e4321cc89452fa943680c220906b8888d0e5e487608da458338c1fd616575dc7.jpg)

![e6d821e501ac68cf1dd5944408e11e14ba45b31c12381dca684c9f41c809d2b5.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/e6d821e501ac68cf1dd5944408e11e14ba45b31c12381dca684c9f41c809d2b5.jpg)

![e9dd4e56ac8dcfdff685e63f55167dd4d47040f74ead0e6fa75f5fc60c5b809f.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/e9dd4e56ac8dcfdff685e63f55167dd4d47040f74ead0e6fa75f5fc60c5b809f.jpg)

![ec7465e5f664d3596edd4a65cbbea64c70a8716e465c3b3eda050070a9c87e2d.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/ec7465e5f664d3596edd4a65cbbea64c70a8716e465c3b3eda050070a9c87e2d.jpg)

![ecd229c4b72497c8cdc81375f4289b7a91c1dbdcb148bfb718272961671c7d95.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/ecd229c4b72497c8cdc81375f4289b7a91c1dbdcb148bfb718272961671c7d95.jpg)

![f43a4e1e3b211a16596ae2312c134671a48c551f0621c53528dc31d7b660e67f.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/f43a4e1e3b211a16596ae2312c134671a48c551f0621c53528dc31d7b660e67f.jpg)

![fb5e2a9ca53dae82de3fa96e29158f53fdf0d1ff32e231031ad008b94334f134.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/images/fb5e2a9ca53dae82de3fa96e29158f53fdf0d1ff32e231031ad008b94334f134.jpg)

### Tables

![51bad13eae98a1d956dd1aa4128dab7fc0da026d9e71b6924cc78aa4ab08b1d1.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/tables/51bad13eae98a1d956dd1aa4128dab7fc0da026d9e71b6924cc78aa4ab08b1d1.jpg)

![62ada9593aff564a16c6b0f4a13e36097fa58b586ed2a0f2f1a19489680cb44b.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/tables/62ada9593aff564a16c6b0f4a13e36097fa58b586ed2a0f2f1a19489680cb44b.jpg)

![72b5925e55c9a26a925f6531bff0311d2d0df96ff1028cd74af541fdbf834418.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/tables/72b5925e55c9a26a925f6531bff0311d2d0df96ff1028cd74af541fdbf834418.jpg)

![a56dd99e8fdb87dbb138e45be99551b85520b8a910b8f5f9eba995f43101b800.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/tables/a56dd99e8fdb87dbb138e45be99551b85520b8a910b8f5f9eba995f43101b800.jpg)

![d0de1f126bf3704489713ddbfcb606a1ab8fcc32be9f151ae3748ded9df1823a.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/tables/d0de1f126bf3704489713ddbfcb606a1ab8fcc32be9f151ae3748ded9df1823a.jpg)

![d85a823aaf9704c87ddf34df643aece1fa3d5f2caeced715ccba359c1ecc2b4a.jpg](../nips_results/294_When%20Less%20Language%20is%20More_%20Language-Reasoning%20Disentanglement%20Makes%20LLMs%20Better%20Multilingual%20Reason/tables/d85a823aaf9704c87ddf34df643aece1fa3d5f2caeced715ccba359c1ecc2b4a.jpg)

## Repo2Run: Automated Building Executable Environment for Code Repository at Scale

### Images

![20799987ecac8134bf768d54a1822060fff40ffc1142135c8d6d8b6d8e74a7c3.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/20799987ecac8134bf768d54a1822060fff40ffc1142135c8d6d8b6d8e74a7c3.jpg)

![268ec683cb62bd70fb18d69fd9cd21ef70101ca298a525c13ccc062036873049.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/268ec683cb62bd70fb18d69fd9cd21ef70101ca298a525c13ccc062036873049.jpg)

![278655d319dcbbd9f347de58399c6e1eb1206191baaeffd7554572319b473c55.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/278655d319dcbbd9f347de58399c6e1eb1206191baaeffd7554572319b473c55.jpg)

![355658b056f89212bca534e8fcc0938e3625e054d7027d5dbecdb81313254b2f.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/355658b056f89212bca534e8fcc0938e3625e054d7027d5dbecdb81313254b2f.jpg)

![370ab49f6a86f7dbd804a3d7ad2ceb80fc36acfc3a212d570a3ed1b3aec34cb8.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/370ab49f6a86f7dbd804a3d7ad2ceb80fc36acfc3a212d570a3ed1b3aec34cb8.jpg)

![65880fb37e84de55b237c2e7c13f230c2f738fef69e3adaf6aaf602b43008547.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/65880fb37e84de55b237c2e7c13f230c2f738fef69e3adaf6aaf602b43008547.jpg)

![ac1e757c3daf8d580c20e385717fc217411842e667c6d28540890ec600eb6eaf.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/ac1e757c3daf8d580c20e385717fc217411842e667c6d28540890ec600eb6eaf.jpg)

![b0cafbaeeebc9146338215a132b66561fd1bdf5c4bbc7ae0ff350564747b8619.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/b0cafbaeeebc9146338215a132b66561fd1bdf5c4bbc7ae0ff350564747b8619.jpg)

![d0b99333c568fa53187b5b68973e3c05018936e72a1180c65f7f504435e96cd9.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/d0b99333c568fa53187b5b68973e3c05018936e72a1180c65f7f504435e96cd9.jpg)

![de015f3d19cdd1677f3058900394c1ff3f7b1d48b12bc873fca8b03e1b63e82e.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/de015f3d19cdd1677f3058900394c1ff3f7b1d48b12bc873fca8b03e1b63e82e.jpg)

![de4072a753129da242b88b90da50e4dc95feb3e02334982c930ef71b1d950ab7.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/de4072a753129da242b88b90da50e4dc95feb3e02334982c930ef71b1d950ab7.jpg)

![ea96f359e23ff3f0427d48dd3247314967bb531150d725a7680376b940324680.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/images/ea96f359e23ff3f0427d48dd3247314967bb531150d725a7680376b940324680.jpg)

### Tables

![0417e2c08b658aab0b389ec627313f77ce9ee74b5b76c8966dbc8ceafb8b4265.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/0417e2c08b658aab0b389ec627313f77ce9ee74b5b76c8966dbc8ceafb8b4265.jpg)

![058dbe156a79da20728ea51309039c91ef970589682e9ea093d47b9ad9681f79.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/058dbe156a79da20728ea51309039c91ef970589682e9ea093d47b9ad9681f79.jpg)

![0d2fb3601538193cfd58fd85b55785a4e18374444b59fa830ff78d10ef825f37.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/0d2fb3601538193cfd58fd85b55785a4e18374444b59fa830ff78d10ef825f37.jpg)

![1021051d8c68d5bdae6de57d31a7123357d1d18575e26e4466c7c8363cfc21ad.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/1021051d8c68d5bdae6de57d31a7123357d1d18575e26e4466c7c8363cfc21ad.jpg)

![3c46230ba0c54c4e0a5e86a9908cb76ae238521e3318c750277e3c39f8c74043.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/3c46230ba0c54c4e0a5e86a9908cb76ae238521e3318c750277e3c39f8c74043.jpg)

![4c26276a6f3a450b55cd29c86eecd05c9199e6197968792dd6c57cd2f7cdbd4f.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/4c26276a6f3a450b55cd29c86eecd05c9199e6197968792dd6c57cd2f7cdbd4f.jpg)

![505332ccdea8e5c3cd2ef40c657c3f61c75287acf5dfa65f57bd519d885c215b.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/505332ccdea8e5c3cd2ef40c657c3f61c75287acf5dfa65f57bd519d885c215b.jpg)

![563a8930aa1c519bac6638170230cd06bf88c92561ded0c21cd641f91d7c5e8c.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/563a8930aa1c519bac6638170230cd06bf88c92561ded0c21cd641f91d7c5e8c.jpg)

![56c01b79a7280612e91f41cb408cf97c0a4d020ac0cbedef99ab520a9f5e456d.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/56c01b79a7280612e91f41cb408cf97c0a4d020ac0cbedef99ab520a9f5e456d.jpg)

![6345ab9161ade1464235b49941899945696909d42d393ffaf69bc852c3bc1483.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/6345ab9161ade1464235b49941899945696909d42d393ffaf69bc852c3bc1483.jpg)

![634f117b2b35cd6ef63b72582ecab9b876b84429a7d5ceb08913f889709e7c29.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/634f117b2b35cd6ef63b72582ecab9b876b84429a7d5ceb08913f889709e7c29.jpg)

![7ef6cf9f850ac2087d1e70aa102603be4ff691b8d1a00768285b9bc8cf6b5ab6.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/7ef6cf9f850ac2087d1e70aa102603be4ff691b8d1a00768285b9bc8cf6b5ab6.jpg)

![8d51cc16e2151375136139219c71ffca4e4665d8217a046e6ad5029620646691.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/8d51cc16e2151375136139219c71ffca4e4665d8217a046e6ad5029620646691.jpg)

![91a42a161f70faf4c4873cd99cfebb4a3218e5eacccf944baff8ea3fc3bce1e6.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/91a42a161f70faf4c4873cd99cfebb4a3218e5eacccf944baff8ea3fc3bce1e6.jpg)

![b54cc287aa7acb5273279565ba7b5b40ff1d9c3dc4340c2cec9b6851b7312440.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/b54cc287aa7acb5273279565ba7b5b40ff1d9c3dc4340c2cec9b6851b7312440.jpg)

![b822032d578bff4c345de839c897080decfe58fc6e2bac6f423ce1f7bacf3eab.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/b822032d578bff4c345de839c897080decfe58fc6e2bac6f423ce1f7bacf3eab.jpg)

![d9f836a252089ed8b7a95e7540f29876ba1afef2d834d47a94f522791ed370f5.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/d9f836a252089ed8b7a95e7540f29876ba1afef2d834d47a94f522791ed370f5.jpg)

![dc34565e8a611fd4608f22f1c329e422cd70dba78e26d620efebf511dae45383.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/dc34565e8a611fd4608f22f1c329e422cd70dba78e26d620efebf511dae45383.jpg)

![e6346f664f3d28b4fa3f899c709f6b2a142c8d08bd5e478fd7a3141655c78224.jpg](../nips_results/295_Repo2Run_%20Automated%20Building%20Executable%20Environment%20for%20Code%20Repository%20at%20Scale/tables/e6346f664f3d28b4fa3f899c709f6b2a142c8d08bd5e478fd7a3141655c78224.jpg)
