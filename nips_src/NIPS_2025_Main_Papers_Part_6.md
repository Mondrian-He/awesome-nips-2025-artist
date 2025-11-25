# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 6 of 130

## 目录 (Table of Contents)

1. [Bipolar Self-attention for Spiking Transformers](#Bipolar-Self-attention-for-Spiking-Transformers)
2. [GenColor: Generative and Expressive Color Enhancement with Pixel-Perfect Texture Preservation](#GenColor-Generative-and-Expressive-Color-Enhancement-with-Pixel-Perfect-Texture-Preservation)
3. [Principled Data Augmentation for Learning to Solve Quadratic Programming Problems](#Principled-Data-Augmentation-for-Learning-to-Solve-Quadratic-Programming-Problems)
4. [Orient Anything V2: Unifying Orientation and Rotation Understanding](#Orient-Anything-V2-Unifying-Orientation-and-Rotation-Understanding)
5. [From Shortcut to Induction Head: How Data Diversity Shapes Algorithm Selection in Transformers](#From-Shortcut-to-Induction-Head-How-Data-Diversity-Shapes-Algorithm-Selection-in-Transformers)
6. [ShapeLLM-Omni: A Native Multimodal LLM for 3D Generation and Understanding](#ShapeLLM-Omni-A-Native-Multimodal-LLM-for-3D-Generation-and-Understanding)
7. [G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems](#G-Memory-Tracing-Hierarchical-Memory-for-Multi-Agent-Systems)
8. [AgentBreeder: Mitigating the AI Safety Risks of Multi-Agent Scaffolds via Self-Improvement](#AgentBreeder-Mitigating-the-AI-Safety-Risks-of-Multi-Agent-Scaffolds-via-Self-Improvement)
9. [Gradient-Variation Online Adaptivity for Accelerated Optimization with Hölder Smoothness](#Gradient-Variation-Online-Adaptivity-for-Accelerated-Optimization-with-Hölder-Smoothness)
10. [Ridge Boosting is Both Robust and Efficient](#Ridge-Boosting-is-Both-Robust-and-Efficient)
11. [Self Forcing: Bridging the Train-Test Gap in Autoregressive Video Diffusion](#Self-Forcing-Bridging-the-Train-Test-Gap-in-Autoregressive-Video-Diffusion)
12. [DeCaFlow: A deconfounding causal generative model](#DeCaFlow-A-deconfounding-causal-generative-model)
13. [Caption This, Reason That: VLMs Caught in the Middle](#Caption-This-Reason-That-VLMs-Caught-in-the-Middle)
14. [Towards Comprehensive Scene Understanding: Integrating First and Third-Person Views for LVLMs](#Towards-Comprehensive-Scene-Understanding-Integrating-First-and-Third-Person-Views-for-LVLMs)
15. [Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via Collective Monte Carlo Tree Search](#Mulberry-Empowering-MLLM-with-o1-like-Reasoning-and-Reflection-via-Collective-Monte-Carlo-Tree-Search)
16. [Approximate Domain Unlearning for Vision-Language Models](#Approximate-Domain-Unlearning-for-Vision-Language-Models)
17. [E2Former: An Efficient and Equivariant Transformer with Linear-Scaling Tensor Products](#E2Former-An-Efficient-and-Equivariant-Transformer-with-Linear-Scaling-Tensor-Products)
18. [Shift Before You Learn: Enabling Low-Rank Representations in Reinforcement Learning](#Shift-Before-You-Learn-Enabling-Low-Rank-Representations-in-Reinforcement-Learning)
19. [Estimating cognitive biases with attention-aware inverse planning](#Estimating-cognitive-biases-with-attention-aware-inverse-planning)
20. [VoxDet: Rethinking 3D Semantic Scene Completion as Dense Object Detection](#VoxDet-Rethinking-3D-Semantic-Scene-Completion-as-Dense-Object-Detection)
21. [ModHiFi: Identifying High Fidelity predictive components for Model Modification](#ModHiFi-Identifying-High-Fidelity-predictive-components-for-Model-Modification)
22. [Discrete Spatial Diffusion: Intensity-Preserving Diffusion Modeling](#Discrete-Spatial-Diffusion-Intensity-Preserving-Diffusion-Modeling)
23. [FP4 All the Way: Fully Quantized Training of Large Language Models](#FP4-All-the-Way-Fully-Quantized-Training-of-Large-Language-Models)
24. [Object-centric 3D Motion Field for Robot Learning from Human Videos](#Object-centric-3D-Motion-Field-for-Robot-Learning-from-Human-Videos)
25. [SoFar: Language-Grounded Orientation Bridges Spatial Reasoning and Object Manipulation](#SoFar-Language-Grounded-Orientation-Bridges-Spatial-Reasoning-and-Object-Manipulation)
26. [Generating Informative Samples for Risk-Averse Fine-Tuning of Downstream Tasks](#Generating-Informative-Samples-for-Risk-Averse-Fine-Tuning-of-Downstream-Tasks)
27. [Purifying Shampoo: Investigating Shampoo's Heuristics by Decomposing its Preconditioner](#Purifying-Shampoo-Investigating-Shampoos-Heuristics-by-Decomposing-its-Preconditioner)
28. [Improving LLM General Preference Alignment via Optimistic Online Mirror Descent](#Improving-LLM-General-Preference-Alignment-via-Optimistic-Online-Mirror-Descent)
29. [3D Equivariant Visuomotor Policy Learning via Spherical Projection](#3D-Equivariant-Visuomotor-Policy-Learning-via-Spherical-Projection)
30. [Not All Data are Good Labels: On the Self-supervised Labeling for Time Series Forecasting](#Not-All-Data-are-Good-Labels-On-the-Self-supervised-Labeling-for-Time-Series-Forecasting)
31. [AI-Researcher: Autonomous Scientific Innovation](#AI-Researcher-Autonomous-Scientific-Innovation)
32. [ConTextTab: A Semantics-Aware Tabular In-Context Learner](#ConTextTab-A-Semantics-Aware-Tabular-In-Context-Learner)
33. [Right Question is Already Half the Answer: Fully Unsupervised LLM Reasoning Incentivization](#Right-Question-is-Already-Half-the-Answer-Fully-Unsupervised-LLM-Reasoning-Incentivization)
34. [Integration Matters for Learning PDEs with Backwards SDEs](#Integration-Matters-for-Learning-PDEs-with-Backwards-SDEs)
35. [KARMA: Leveraging Multi-Agent LLMs for Automated Knowledge Graph Enrichment](#KARMA-Leveraging-Multi-Agent-LLMs-for-Automated-Knowledge-Graph-Enrichment)
36. [T-REGS: Minimum Spanning Tree Regularization for Self-Supervised Learning](#T-REGS-Minimum-Spanning-Tree-Regularization-for-Self-Supervised-Learning)
37. [DisMo: Disentangled Motion Representations for Open-World Motion Transfer](#DisMo-Disentangled-Motion-Representations-for-Open-World-Motion-Transfer)
38. [Improving Bilinear RNN with Closed-loop Control](#Improving-Bilinear-RNN-with-Closed-loop-Control)
39. [Generalized Top-k Mallows Model for Ranked Choices](#Generalized-Top-k-Mallows-Model-for-Ranked-Choices)
40. [AceSearcher: Bootstrapping Reasoning and Search for LLMs via Reinforced Self-Play](#AceSearcher-Bootstrapping-Reasoning-and-Search-for-LLMs-via-Reinforced-Self-Play)
41. [Robust Neural Rendering in the Wild with Asymmetric Dual 3D Gaussian Splatting](#Robust-Neural-Rendering-in-the-Wild-with-Asymmetric-Dual-3D-Gaussian-Splatting)

---


## Bipolar Self-attention for Spiking Transformers

### Images

![131e87dccb4579d12b71fc26780de74805e15974a46472069825e214aeb640e3.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/131e87dccb4579d12b71fc26780de74805e15974a46472069825e214aeb640e3.jpg)

![16b6cb5e6183877f2e44cb9b6fa955f197fd057346a68d1e8887f814fd1c6e2f.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/16b6cb5e6183877f2e44cb9b6fa955f197fd057346a68d1e8887f814fd1c6e2f.jpg)

![17d424dbb146d546c34fab5400e05c4a5c18151d02593c9e5d3173807c558592.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/17d424dbb146d546c34fab5400e05c4a5c18151d02593c9e5d3173807c558592.jpg)

![1b8d1ea321ff2d968f6105bb8ca690e31715c79f9d5cb3c6c6bb86822b20302c.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/1b8d1ea321ff2d968f6105bb8ca690e31715c79f9d5cb3c6c6bb86822b20302c.jpg)

![21188943be79eab61372ea9dce38e91dde1a21dfd222ef10d58cec35e20e4f21.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/21188943be79eab61372ea9dce38e91dde1a21dfd222ef10d58cec35e20e4f21.jpg)

![23043a78b6fb84a90e1d6309011a7e62f896b1884553c55f5acf6d20b81b7332.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/23043a78b6fb84a90e1d6309011a7e62f896b1884553c55f5acf6d20b81b7332.jpg)

![23b698e45c472ab57eb54aaf9d46c7f060090808016c5aeacc30e3034bb1465b.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/23b698e45c472ab57eb54aaf9d46c7f060090808016c5aeacc30e3034bb1465b.jpg)

![2bc69ac9e8a46fe48c40259d2c60da8ba144092a3e1a2ff6e2c739ffb28f4bb3.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/2bc69ac9e8a46fe48c40259d2c60da8ba144092a3e1a2ff6e2c739ffb28f4bb3.jpg)

![3064c690f185b5310634aeeb79da5aea68dfdf4c43eea884986ec1aed1b08366.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/3064c690f185b5310634aeeb79da5aea68dfdf4c43eea884986ec1aed1b08366.jpg)

![3433762c8a512123c86ce7f1cddef97b43514fcb582d20ea26f260ff38b4ce3b.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/3433762c8a512123c86ce7f1cddef97b43514fcb582d20ea26f260ff38b4ce3b.jpg)

![3726da90102c68d73f6236964d5b0c2704138efae085d1080d5374d4cbd012fc.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/3726da90102c68d73f6236964d5b0c2704138efae085d1080d5374d4cbd012fc.jpg)

![374276e3339aed609568ab4d1ab389583fab4e16fdf9afe45d1bbce9e4a4028b.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/374276e3339aed609568ab4d1ab389583fab4e16fdf9afe45d1bbce9e4a4028b.jpg)

![3f60283c214703377b22a4d221f3736b1f539cef5016561ae889e8bbf5e9934c.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/3f60283c214703377b22a4d221f3736b1f539cef5016561ae889e8bbf5e9934c.jpg)

![5fa762c51bb28bfabada34c10c97bf0a8ea70f940542ac40dc5eb21f42e441d9.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/5fa762c51bb28bfabada34c10c97bf0a8ea70f940542ac40dc5eb21f42e441d9.jpg)

![6b0da034e4c167dc62f575203337facf21f81630998fbca961072058fc1e2126.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/6b0da034e4c167dc62f575203337facf21f81630998fbca961072058fc1e2126.jpg)

![8d6981f06a6b67e3f61d92fc2c78dc702d626f54cd37ec579cafdb69c2f08591.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/8d6981f06a6b67e3f61d92fc2c78dc702d626f54cd37ec579cafdb69c2f08591.jpg)

![90a1cd7ad5fc1ec9e35b63807d487f7c71acafd148cba862285938f14357748a.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/90a1cd7ad5fc1ec9e35b63807d487f7c71acafd148cba862285938f14357748a.jpg)

![91366d4472ec474ae21caf5cf5c8cff900528fb29e73e406f7bdb604d7c72060.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/91366d4472ec474ae21caf5cf5c8cff900528fb29e73e406f7bdb604d7c72060.jpg)

![93f93fda7fb458ed4fcc89e90ac1cb9ac6b117f12be5c8881e4af7b5065ea85e.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/93f93fda7fb458ed4fcc89e90ac1cb9ac6b117f12be5c8881e4af7b5065ea85e.jpg)

![9d6e08203e5aea7df496bbc9d71aca9f7fea951d1d9cc33a5c5646a94b6aa4fc.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/9d6e08203e5aea7df496bbc9d71aca9f7fea951d1d9cc33a5c5646a94b6aa4fc.jpg)

![a23e54361f44a18c418b63922a30774276c0231c9adf44a1f23cb08e77dd81ba.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/a23e54361f44a18c418b63922a30774276c0231c9adf44a1f23cb08e77dd81ba.jpg)

![a5fd894a74dcacf272eb4b176be34a0258f3a4fcd47bdd97a0224dd7072b3193.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/a5fd894a74dcacf272eb4b176be34a0258f3a4fcd47bdd97a0224dd7072b3193.jpg)

![b850d7df737fbc92fce8505b15b17e9927a3b2ce71fdd46e374050e11089d052.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/b850d7df737fbc92fce8505b15b17e9927a3b2ce71fdd46e374050e11089d052.jpg)

![bc39fe3d859d908a810a8568cb483b6b8ff2a750a7aeb45e3535973d7fdd291b.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/bc39fe3d859d908a810a8568cb483b6b8ff2a750a7aeb45e3535973d7fdd291b.jpg)

![d77288be393d946f2a4f46dd993f212587d6548c1e673c58ccef10af6b0e4469.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/d77288be393d946f2a4f46dd993f212587d6548c1e673c58ccef10af6b0e4469.jpg)

![d7df9ef12c5227b84aef8b43871bdad7d254ab16fc8c58590c093a9203c5738e.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/d7df9ef12c5227b84aef8b43871bdad7d254ab16fc8c58590c093a9203c5738e.jpg)

![dc5da60e8abb36bec67363c9549cad093db5b32c7721508660685e34af7960e9.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/dc5da60e8abb36bec67363c9549cad093db5b32c7721508660685e34af7960e9.jpg)

![fd3be30eece1e5f20489a84c065723291863bc42633f288a79809dc25299765a.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/fd3be30eece1e5f20489a84c065723291863bc42633f288a79809dc25299765a.jpg)

![fd685c4f5072faf9e133ec0970fbcbb26444d9356902ce1f047681d79e330b0f.jpg](../nips_results/212_Variational%20Learning%20Finds%20Flatter%20Solutions%20at%20the%20Edge%20of%20Stability/images/fd685c4f5072faf9e133ec0970fbcbb26444d9356902ce1f047681d79e330b0f.jpg)

## Bipolar Self-attention for Spiking Transformers


### Images

![135984e7da62ba38fb385c8ffb173ce9a006c0c2296c69abdf2c9c1715ff26d9.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/images/135984e7da62ba38fb385c8ffb173ce9a006c0c2296c69abdf2c9c1715ff26d9.jpg)

![166a0e465bd8f783d3d43bedf661c264e95bc75d0d7c181fafd345040d1e04cd.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/images/166a0e465bd8f783d3d43bedf661c264e95bc75d0d7c181fafd345040d1e04cd.jpg)

![678351397d01fdca6c4e81b72a4b6e68b43a058298cf79b718e8fa4d19773027.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/images/678351397d01fdca6c4e81b72a4b6e68b43a058298cf79b718e8fa4d19773027.jpg)

![72e7ed1b264fe98cb7166731ec5bf37851af110982a13299c79239c051663d30.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/images/72e7ed1b264fe98cb7166731ec5bf37851af110982a13299c79239c051663d30.jpg)

![7ba3051f65f6662c83cb19d3f41cc0b14e0e8571e45048d213099047479a66e5.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/images/7ba3051f65f6662c83cb19d3f41cc0b14e0e8571e45048d213099047479a66e5.jpg)

![b64fa498ca3642d8446b8c242f7e45c5b3008745012f3485824287eee70bdd3d.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/images/b64fa498ca3642d8446b8c242f7e45c5b3008745012f3485824287eee70bdd3d.jpg)

![b880ff985dd8c3bdaa6735524d3338467d8522cbbb6e606914e81b94c70ba75e.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/images/b880ff985dd8c3bdaa6735524d3338467d8522cbbb6e606914e81b94c70ba75e.jpg)

### Tables

![544388cdc71b48d6b3ae9c792cf8621bea1c95ddd6eab6ab741953eed7507535.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/tables/544388cdc71b48d6b3ae9c792cf8621bea1c95ddd6eab6ab741953eed7507535.jpg)

![6ce4966f548f8afac9f24a66d79fa2f73276ccdf356e91db086bd740a0c64f0c.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/tables/6ce4966f548f8afac9f24a66d79fa2f73276ccdf356e91db086bd740a0c64f0c.jpg)

![6e11977bdc5255c9794c7b09267fbe5771eff563bd919e5bffd3964e10319ef5.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/tables/6e11977bdc5255c9794c7b09267fbe5771eff563bd919e5bffd3964e10319ef5.jpg)

![92cfcd377b0832e05f56b6137a50ffb82231baefc6fb365c759e0b39cdaae3df.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/tables/92cfcd377b0832e05f56b6137a50ffb82231baefc6fb365c759e0b39cdaae3df.jpg)

![bb4bbd24135218b801ec3def1be277d6570ee208a03b16cc1a16e0c0cd79972d.jpg](../nips_results/213_Bipolar%20Self-attention%20for%20Spiking%20Transformers/tables/bb4bbd24135218b801ec3def1be277d6570ee208a03b16cc1a16e0c0cd79972d.jpg)

## GenColor: Generative and Expressive Color Enhancement with Pixel-Perfect Texture Preservation


### Images

![08049c3e725e225944da95f7e0be725756b10b8b5845b4bf36e7db089dbcdf22.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/08049c3e725e225944da95f7e0be725756b10b8b5845b4bf36e7db089dbcdf22.jpg)

![094ce75208a6e846e1590ffa2c5419d3241d690500d5908c6a48004f3263b326.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/094ce75208a6e846e1590ffa2c5419d3241d690500d5908c6a48004f3263b326.jpg)

![15c9a0213014e899d6d39fd64597b1eaafb74676331b7b7fe39d893b90ae8667.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/15c9a0213014e899d6d39fd64597b1eaafb74676331b7b7fe39d893b90ae8667.jpg)

![1b58a7e88062219ecd3c402be1c12b37f235b96fc05b067af0df7cdb7fb83e7e.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/1b58a7e88062219ecd3c402be1c12b37f235b96fc05b067af0df7cdb7fb83e7e.jpg)

![2029653e9b0ada0d2c63bb62071a693a6d568f982518708342b36bc442709709.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/2029653e9b0ada0d2c63bb62071a693a6d568f982518708342b36bc442709709.jpg)

![203876e4bd5adccce990ca31874af24b20dd788cd41bbdced85f404adda1754e.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/203876e4bd5adccce990ca31874af24b20dd788cd41bbdced85f404adda1754e.jpg)

![2e13c54dd813a7a990e730cc3da2917a4599bcb7a61cfa48467ee32b13d23142.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/2e13c54dd813a7a990e730cc3da2917a4599bcb7a61cfa48467ee32b13d23142.jpg)

![33c68e4215bbaa0250b9a80ab67761b052dfb92af742969d1473bf81f30b698c.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/33c68e4215bbaa0250b9a80ab67761b052dfb92af742969d1473bf81f30b698c.jpg)

![41d24fff9acaf522df1a4820b1c4901fc5da49b8469b74f84caa07fc12a9aa40.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/41d24fff9acaf522df1a4820b1c4901fc5da49b8469b74f84caa07fc12a9aa40.jpg)

![5b22ac212df5ccf21f64745f4018b10e48e32ba4fb0f570895d01da37aeaee03.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/5b22ac212df5ccf21f64745f4018b10e48e32ba4fb0f570895d01da37aeaee03.jpg)

![7033de58fa85e03e8689010986fb6949e1a1400802b93fb68dd037eacb19c4b3.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/7033de58fa85e03e8689010986fb6949e1a1400802b93fb68dd037eacb19c4b3.jpg)

![7d5e10efb4b5d1fb886c8d4ff6e3d331e9dcfcefa7503c4dc4172e05a7033b95.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/7d5e10efb4b5d1fb886c8d4ff6e3d331e9dcfcefa7503c4dc4172e05a7033b95.jpg)

![83485de23fd6da8fe28372f1c0e0ba24963c4d0088f08554ca068ddad0d45cc6.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/83485de23fd6da8fe28372f1c0e0ba24963c4d0088f08554ca068ddad0d45cc6.jpg)

![9403561189e0c2d4c8173f1fcf520593675cd510dc0d35a2c8890edb5a3dc506.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/9403561189e0c2d4c8173f1fcf520593675cd510dc0d35a2c8890edb5a3dc506.jpg)

![986692b79d5f89fac2adbc60319936cc4784da90ccd9c311a1634d3553942b7b.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/986692b79d5f89fac2adbc60319936cc4784da90ccd9c311a1634d3553942b7b.jpg)

![bca193f244e0c6ce1777a12690780e26f8cb62994660ed03379ab87948cb193a.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/bca193f244e0c6ce1777a12690780e26f8cb62994660ed03379ab87948cb193a.jpg)

![c0c836620bf26086707488c5cd1f7f38fd98367446e218f2c70b8bce777e9eb3.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/c0c836620bf26086707488c5cd1f7f38fd98367446e218f2c70b8bce777e9eb3.jpg)

![c13ca807207b2e9a9dbfa1ed5e1cd335a70d5dc91074b5199695e55b93a111a0.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/c13ca807207b2e9a9dbfa1ed5e1cd335a70d5dc91074b5199695e55b93a111a0.jpg)

![cd0d778cc2f56e0a19b8fe3387211180717cf36d678d3657bc3874e3d9b5170a.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/cd0d778cc2f56e0a19b8fe3387211180717cf36d678d3657bc3874e3d9b5170a.jpg)

![d986e9f37b82eeb9aa8deb4e38cdbe90e3d62b6e312200eff730de467a5f47ab.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/d986e9f37b82eeb9aa8deb4e38cdbe90e3d62b6e312200eff730de467a5f47ab.jpg)

![da44db93d11f91cf89fc9643a1627457b3d1f25dd7d188dd905ce4dab9c82f39.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/da44db93d11f91cf89fc9643a1627457b3d1f25dd7d188dd905ce4dab9c82f39.jpg)

![e05db8540ef78166362141ca0de4211ec7f04890be731cd025fc25acd8e94f0f.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/e05db8540ef78166362141ca0de4211ec7f04890be731cd025fc25acd8e94f0f.jpg)

![f016321eee5ba619a73b241e3811126997e28e63be01b7c0b7625310e60fddfe.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/f016321eee5ba619a73b241e3811126997e28e63be01b7c0b7625310e60fddfe.jpg)

![f4dd988c17f8ad3756ef5e3ce6fe65bc38b960a138fb5fe3fb64eb8c4e67d479.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/f4dd988c17f8ad3756ef5e3ce6fe65bc38b960a138fb5fe3fb64eb8c4e67d479.jpg)

![fb58c198ce059383df7f64af2c5a12798c2d81553c3360d940aab5f09e2df441.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/images/fb58c198ce059383df7f64af2c5a12798c2d81553c3360d940aab5f09e2df441.jpg)

### Tables

![06e82370bc24fb69b407c34892e9749b7b30b289fd87bf86d2901f7f41819bb0.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/06e82370bc24fb69b407c34892e9749b7b30b289fd87bf86d2901f7f41819bb0.jpg)

![3ccbada155c63cce1fb61a2a9b227cc91729f0323c9ec67f98f21098863cec5a.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/3ccbada155c63cce1fb61a2a9b227cc91729f0323c9ec67f98f21098863cec5a.jpg)

![48c4c94028f7f8c57e8ffb7f35c31ca5ee4985d08aa74206bdfae02c6c9bff80.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/48c4c94028f7f8c57e8ffb7f35c31ca5ee4985d08aa74206bdfae02c6c9bff80.jpg)

![5f2cda2638de90b650c7002810cc4beb126bc3449fc51c2572fb0ce2182eec5c.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/5f2cda2638de90b650c7002810cc4beb126bc3449fc51c2572fb0ce2182eec5c.jpg)

![5fac0ed02f584911d7f7a510965e92008fee0c277313320e607bd3ca52da7a52.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/5fac0ed02f584911d7f7a510965e92008fee0c277313320e607bd3ca52da7a52.jpg)

![6057a244c8b442f33d29b159404b3106c0621e9d9678f9bbae434fb226afae5b.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/6057a244c8b442f33d29b159404b3106c0621e9d9678f9bbae434fb226afae5b.jpg)

![610a00f062175a5fce52f5598bb43a3ec2a7f70baebbcfca2e89ce10ed93f295.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/610a00f062175a5fce52f5598bb43a3ec2a7f70baebbcfca2e89ce10ed93f295.jpg)

![61c47d25e8cb4f82b671db24299a789be0a80806ed54d9168bbc26a09d65c24f.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/61c47d25e8cb4f82b671db24299a789be0a80806ed54d9168bbc26a09d65c24f.jpg)

![6a181f9c69b85d3fdd942911cdd5d393399e9664a2c91c6a50b20b54baf9bf77.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/6a181f9c69b85d3fdd942911cdd5d393399e9664a2c91c6a50b20b54baf9bf77.jpg)

![6f7839c2983478e2013833205a04b7cdc6adc310d1d26f92a5b3d20b1fe133ea.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/6f7839c2983478e2013833205a04b7cdc6adc310d1d26f92a5b3d20b1fe133ea.jpg)

![8761686b6b29c107818db3c45f24cdcadc87209025dae24bfa4b69fccfd42f6e.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/8761686b6b29c107818db3c45f24cdcadc87209025dae24bfa4b69fccfd42f6e.jpg)

![8b9299e84232fdf632061d0a6a997358e226e962fc69f60e593c30404e5fe568.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/8b9299e84232fdf632061d0a6a997358e226e962fc69f60e593c30404e5fe568.jpg)

![9728260917839a120e735d35883d53b1ab3778b1bd3ac23a0155cd4ca88da436.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/9728260917839a120e735d35883d53b1ab3778b1bd3ac23a0155cd4ca88da436.jpg)

![a063b0f75ef5693531dde94f48b6800f17a386127483ea22b675ae24115f1b8d.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/a063b0f75ef5693531dde94f48b6800f17a386127483ea22b675ae24115f1b8d.jpg)

![a2d10f7fa90adb531599789e05d6e41457a9735a44bac26d95b3ce24f5dd91bd.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/a2d10f7fa90adb531599789e05d6e41457a9735a44bac26d95b3ce24f5dd91bd.jpg)

![a7ee565759d6afc2e4af4a2576846455b80333c6434fe0f9bd5062534c4953c9.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/a7ee565759d6afc2e4af4a2576846455b80333c6434fe0f9bd5062534c4953c9.jpg)

![b651228fd7b5a377f4c128c14f8c54ff112fde65449c64d49f41953ba3f51b16.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/b651228fd7b5a377f4c128c14f8c54ff112fde65449c64d49f41953ba3f51b16.jpg)

![c2a0a1bc3f6f82954f1c58938708ea9573d7f2cdafdaf529eb337b74586ab80d.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/c2a0a1bc3f6f82954f1c58938708ea9573d7f2cdafdaf529eb337b74586ab80d.jpg)

![cacdd64087c0fdb55ac84fcdae1139a7c306fbbcd3c55cf3c9b45dcf19e4d84f.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/cacdd64087c0fdb55ac84fcdae1139a7c306fbbcd3c55cf3c9b45dcf19e4d84f.jpg)

![ebec95e1a5282b940d372e56a4e4c89d8e9027936bd8d9ab495a266d86032bdc.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/ebec95e1a5282b940d372e56a4e4c89d8e9027936bd8d9ab495a266d86032bdc.jpg)

![f71639dd46d4ace7574d0ac4d2ed2fb71feb981183455879516dc377d72711a8.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/f71639dd46d4ace7574d0ac4d2ed2fb71feb981183455879516dc377d72711a8.jpg)

![fa2b06d597a901b26f692539218f8ec64d74fc5213f5d4f05e5563fb7140daeb.jpg](../nips_results/214_GenColor_%20Generative%20and%20Expressive%20Color%20Enhancement%20with%20Pixel-Perfect%20Texture%20Preservation/tables/fa2b06d597a901b26f692539218f8ec64d74fc5213f5d4f05e5563fb7140daeb.jpg)

## Principled Data Augmentation for Learning to Solve Quadratic Programming Problems


### Images

![0aeffc2c20f09a8569f01e06c0bdabb50ec0e0410a2523e342f8eb0b935ce9d5.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/images/0aeffc2c20f09a8569f01e06c0bdabb50ec0e0410a2523e342f8eb0b935ce9d5.jpg)

![799ee784f87edbfc1468135e33cd750feae2b3aca38ec2d3864fa3cc9b076898.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/images/799ee784f87edbfc1468135e33cd750feae2b3aca38ec2d3864fa3cc9b076898.jpg)

### Tables

![00fccc4d6801ad1517309d676f75b687718752b6b447261d6dff409531c71ef7.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/00fccc4d6801ad1517309d676f75b687718752b6b447261d6dff409531c71ef7.jpg)

![0826b7d6a63dffc40f6d5347e793f17c189012516e0f329a955188bc51d0cc45.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/0826b7d6a63dffc40f6d5347e793f17c189012516e0f329a955188bc51d0cc45.jpg)

![1e9c13fb088670fa26cf1e4e0f2dc24cb38c8d77a15496aa506bafb715275029.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/1e9c13fb088670fa26cf1e4e0f2dc24cb38c8d77a15496aa506bafb715275029.jpg)

![23745031c56aee0b50cfa22f9827e6f4aa35a976c88e6029599d89b7efcc9cc4.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/23745031c56aee0b50cfa22f9827e6f4aa35a976c88e6029599d89b7efcc9cc4.jpg)

![4b7ccbc5828574eab3df9fa955bb9db4611a880d0127c8753f940b9cf6afbbe6.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/4b7ccbc5828574eab3df9fa955bb9db4611a880d0127c8753f940b9cf6afbbe6.jpg)

![6250d6c5512605a06e1ba83c8922b857f4bcc90bfad7b6b50dfe6fec4fcff0e4.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/6250d6c5512605a06e1ba83c8922b857f4bcc90bfad7b6b50dfe6fec4fcff0e4.jpg)

![64197184d3749083f8e6159bd33bc4c8b7b8eb48d7b30836408c3019e8b1ffab.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/64197184d3749083f8e6159bd33bc4c8b7b8eb48d7b30836408c3019e8b1ffab.jpg)

![6b1420b40410505550acffde382318e884245daaa00d43580512c4300fd0479f.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/6b1420b40410505550acffde382318e884245daaa00d43580512c4300fd0479f.jpg)

![6da5551e1fe79fa31653a8a18c9dd1419d609ab3f91ad28922b7c53186fd87e8.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/6da5551e1fe79fa31653a8a18c9dd1419d609ab3f91ad28922b7c53186fd87e8.jpg)

![bd7fa0673f64c06b03aeda9b86aae1debab3356e4cede733ba9ef952e6fcc88a.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/bd7fa0673f64c06b03aeda9b86aae1debab3356e4cede733ba9ef952e6fcc88a.jpg)

![c2249d3347002f4f6cd6ef75dc43fb01dfeffd338a8e04e611588c0858427143.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/c2249d3347002f4f6cd6ef75dc43fb01dfeffd338a8e04e611588c0858427143.jpg)

![cd8793fd9beb343a46a0de4c0c18e542f2d38073f3dd9bdb489d9bee20b08700.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/cd8793fd9beb343a46a0de4c0c18e542f2d38073f3dd9bdb489d9bee20b08700.jpg)

![d4b59dbfd47bc7d97290f93f3d10d38be641611129095178583200bbfdd7e0f5.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/d4b59dbfd47bc7d97290f93f3d10d38be641611129095178583200bbfdd7e0f5.jpg)

![eef5ceb055c669ab4fc61ff06e259d0de9833d9e1d9db291b347788820baf49b.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/eef5ceb055c669ab4fc61ff06e259d0de9833d9e1d9db291b347788820baf49b.jpg)

![f8d700ab5eda8628a22f217bf080ee08b50d4cabd7f507b2e3beea4d051b3567.jpg](../nips_results/215_Principled%20Data%20Augmentation%20for%20Learning%20to%20Solve%20Quadratic%20Programming%20Problems/tables/f8d700ab5eda8628a22f217bf080ee08b50d4cabd7f507b2e3beea4d051b3567.jpg)

## Orient Anything V2: Unifying Orientation and Rotation Understanding


### Images

![08b2a8f265ba6969b5c83e96edf7f9e418cf027592e884ebf68d6aa9db205ec1.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/08b2a8f265ba6969b5c83e96edf7f9e418cf027592e884ebf68d6aa9db205ec1.jpg)

![44b35453759debb2c3e9981f5cd435bf22192ba759c6c7b64cdb20300147ffea.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/44b35453759debb2c3e9981f5cd435bf22192ba759c6c7b64cdb20300147ffea.jpg)

![48caf23d3937efb9c0fc956b452c3cff612478d1a8c655ea17307e03cff938bb.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/48caf23d3937efb9c0fc956b452c3cff612478d1a8c655ea17307e03cff938bb.jpg)

![5ca7b15a9d3fe9961c2cb8d2aa37bcaa555755d8f1cbbf1bb2d2827226a871b2.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/5ca7b15a9d3fe9961c2cb8d2aa37bcaa555755d8f1cbbf1bb2d2827226a871b2.jpg)

![6a71543488c263b35defcb0875a2c7c9c928f450fa4c2c596b1033f0ae72083d.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/6a71543488c263b35defcb0875a2c7c9c928f450fa4c2c596b1033f0ae72083d.jpg)

![95f845bbc08b7d3a5ab21301b4e1c7f43a6d136f0f861ade72ccd0f294817e27.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/95f845bbc08b7d3a5ab21301b4e1c7f43a6d136f0f861ade72ccd0f294817e27.jpg)

![b20dd5c5e29e83bbbfb24f09bd5286f6bb435c79809da0e1de1410f2cff21f3b.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/b20dd5c5e29e83bbbfb24f09bd5286f6bb435c79809da0e1de1410f2cff21f3b.jpg)

![b9d1cc74c1c9c902cc6a1cbad480d2542e11842d61078fcbfed2f280918c25e2.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/b9d1cc74c1c9c902cc6a1cbad480d2542e11842d61078fcbfed2f280918c25e2.jpg)

![ba8b115a210dd646b5dccd7ec6f1e4ffc9f79513307b3cb3c550753ada10640a.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/ba8b115a210dd646b5dccd7ec6f1e4ffc9f79513307b3cb3c550753ada10640a.jpg)

![d053b7ea1d5e67488b5a1daaecd959632d9a99d4dae80f74e92b2fc52b32b075.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/d053b7ea1d5e67488b5a1daaecd959632d9a99d4dae80f74e92b2fc52b32b075.jpg)

![d3be4634560d415b1c810fe67ec2a400c2982def942a1480d3647342e4d06b8b.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/d3be4634560d415b1c810fe67ec2a400c2982def942a1480d3647342e4d06b8b.jpg)

![de992f0708b150af968edf3735d2724f1d891240fc24ae7db8a0f86c070555ba.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/de992f0708b150af968edf3735d2724f1d891240fc24ae7db8a0f86c070555ba.jpg)

![f85bf6f82d27f747a352e0cf7e50dcdc3efc311ed8591da5c969bdb90d6f6e14.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/images/f85bf6f82d27f747a352e0cf7e50dcdc3efc311ed8591da5c969bdb90d6f6e14.jpg)

### Tables

![142af497d95fb6c087a433812e4d677b6d5a3efe73c0899f3fdd3b369df5b6d8.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/tables/142af497d95fb6c087a433812e4d677b6d5a3efe73c0899f3fdd3b369df5b6d8.jpg)

![60035efa656f1726a6c1b8d2d34c11abe63598af32e71a8da32646f79a051d98.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/tables/60035efa656f1726a6c1b8d2d34c11abe63598af32e71a8da32646f79a051d98.jpg)

![6aa4dbba2974b16374bab5d59b5b18fc7bdb62e7c716e8f28060fd5c66208c00.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/tables/6aa4dbba2974b16374bab5d59b5b18fc7bdb62e7c716e8f28060fd5c66208c00.jpg)

![84d7e3fb129075bd4bb7692a46e3faa68f743e8fb4c2f4d5dcb3af5cddbbd156.jpg](../nips_results/216_Orient%20Anything%20V2_%20Unifying%20Orientation%20and%20Rotation%20Understanding/tables/84d7e3fb129075bd4bb7692a46e3faa68f743e8fb4c2f4d5dcb3af5cddbbd156.jpg)

## From Shortcut to Induction Head: How Data Diversity Shapes Algorithm Selection in Transformers


### Images

![31fa80a616782f181ec1bc4dc6cc4f65e9c9356210c7487781fc9bcb3e800918.jpg](../nips_results/217_From%20Shortcut%20to%20Induction%20Head_%20How%20Data%20Diversity%20Shapes%20Algorithm%20Selection%20in%20Transformers/images/31fa80a616782f181ec1bc4dc6cc4f65e9c9356210c7487781fc9bcb3e800918.jpg)

![9329c5d39e7af804ec16b4348e056f5b9beec32e21056ca2ffb6fef8e9208d82.jpg](../nips_results/217_From%20Shortcut%20to%20Induction%20Head_%20How%20Data%20Diversity%20Shapes%20Algorithm%20Selection%20in%20Transformers/images/9329c5d39e7af804ec16b4348e056f5b9beec32e21056ca2ffb6fef8e9208d82.jpg)

![a48eb05cd951cf53f6d87a05b06d5662dddc4adab9a298a6b5994a2ed95c5e7a.jpg](../nips_results/217_From%20Shortcut%20to%20Induction%20Head_%20How%20Data%20Diversity%20Shapes%20Algorithm%20Selection%20in%20Transformers/images/a48eb05cd951cf53f6d87a05b06d5662dddc4adab9a298a6b5994a2ed95c5e7a.jpg)

![c4013079fb050f6c871df10fcd610926e452e0f68e5a9b4010988e6c55aa1416.jpg](../nips_results/217_From%20Shortcut%20to%20Induction%20Head_%20How%20Data%20Diversity%20Shapes%20Algorithm%20Selection%20in%20Transformers/images/c4013079fb050f6c871df10fcd610926e452e0f68e5a9b4010988e6c55aa1416.jpg)

![c837ec6cf5599ea895fd4fa2166d0ce5a7d79bbad15ab0f8c5b2433f19045c8c.jpg](../nips_results/217_From%20Shortcut%20to%20Induction%20Head_%20How%20Data%20Diversity%20Shapes%20Algorithm%20Selection%20in%20Transformers/images/c837ec6cf5599ea895fd4fa2166d0ce5a7d79bbad15ab0f8c5b2433f19045c8c.jpg)

### Tables

![47579e5ac26fd9b49749d4ff6a25020eb6b200bac064f271aa2f072e804fe608.jpg](../nips_results/217_From%20Shortcut%20to%20Induction%20Head_%20How%20Data%20Diversity%20Shapes%20Algorithm%20Selection%20in%20Transformers/tables/47579e5ac26fd9b49749d4ff6a25020eb6b200bac064f271aa2f072e804fe608.jpg)

![9d1df629296a1cace0d024ee78885521010725ef4db98a1e6425d493863b9a58.jpg](../nips_results/217_From%20Shortcut%20to%20Induction%20Head_%20How%20Data%20Diversity%20Shapes%20Algorithm%20Selection%20in%20Transformers/tables/9d1df629296a1cace0d024ee78885521010725ef4db98a1e6425d493863b9a58.jpg)

## ShapeLLM-Omni: A Native Multimodal LLM for 3D Generation and Understanding


### Images

![200bc3d239946b62b4882ca6aad092dcc6183015f7f9a56521839c89bdf0361c.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/200bc3d239946b62b4882ca6aad092dcc6183015f7f9a56521839c89bdf0361c.jpg)

![5d6230d5be3f30c4828f098b92e534a6ec339234ab8e02e6f3d3a15602975ff7.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/5d6230d5be3f30c4828f098b92e534a6ec339234ab8e02e6f3d3a15602975ff7.jpg)

![603349fed24b7820d0c4ed9b00befa3fb3391abfcc88ee37eb1ba77adf4e4c68.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/603349fed24b7820d0c4ed9b00befa3fb3391abfcc88ee37eb1ba77adf4e4c68.jpg)

![67d33b676233b435d259ad9bab2044a89a590e67bc3ecc4bf6edc20751949f79.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/67d33b676233b435d259ad9bab2044a89a590e67bc3ecc4bf6edc20751949f79.jpg)

![6a08bb62cfce10ba25048f75b65df1f0745010a308c056c982a5caf023d49430.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/6a08bb62cfce10ba25048f75b65df1f0745010a308c056c982a5caf023d49430.jpg)

![858a77e2bb5cd63ea06026083f312de2079e3d24fb8e3b4f909e821c9cde7b34.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/858a77e2bb5cd63ea06026083f312de2079e3d24fb8e3b4f909e821c9cde7b34.jpg)

![8b61a58cfd25d1f22ad6de2a7cee5acb1abd1f8577dd1e87167c8f017f01c13d.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/8b61a58cfd25d1f22ad6de2a7cee5acb1abd1f8577dd1e87167c8f017f01c13d.jpg)

![97f221cda1c535e635e05e11760b62247bb2310d35e78c2adbc71e3c7a5c5fe9.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/97f221cda1c535e635e05e11760b62247bb2310d35e78c2adbc71e3c7a5c5fe9.jpg)

![b1b2f9c881ca3490adc1bc0630ed0a3def0d1be15e243a95d7cb49a2f16ae00b.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/b1b2f9c881ca3490adc1bc0630ed0a3def0d1be15e243a95d7cb49a2f16ae00b.jpg)

![b6bbb66c6564711918fae304dd8d274a06f0b579700f8ea45cbc62ce5c70bc1e.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/b6bbb66c6564711918fae304dd8d274a06f0b579700f8ea45cbc62ce5c70bc1e.jpg)

![b8ce1c718d582b6c175cd599a6dc4d5d11b817ad54c6cba84b712068d40e41d8.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/b8ce1c718d582b6c175cd599a6dc4d5d11b817ad54c6cba84b712068d40e41d8.jpg)

![ccc5ae9ec22aa3734c407276061f8f8d1001e90154cb1ec3981cea937c633fa6.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/ccc5ae9ec22aa3734c407276061f8f8d1001e90154cb1ec3981cea937c633fa6.jpg)

![df94115a258cfa885571e32a9e7a5797c713fdaba8e836ec8037b00aa6b20a7c.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/df94115a258cfa885571e32a9e7a5797c713fdaba8e836ec8037b00aa6b20a7c.jpg)

![e38a05e7aed3376bef1a375be4232069d1b36d816475505b6ba20efb5d008a25.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/images/e38a05e7aed3376bef1a375be4232069d1b36d816475505b6ba20efb5d008a25.jpg)

### Tables

![20f5221de7db1241cd5b120d7d98a4d53db4d5e14842886b4f6e004ffa1c17e0.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/20f5221de7db1241cd5b120d7d98a4d53db4d5e14842886b4f6e004ffa1c17e0.jpg)

![2a211259f889c036ed9ebbc2df12d6e27d5d2ad0b80e2a6966aed29d09efa4c2.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/2a211259f889c036ed9ebbc2df12d6e27d5d2ad0b80e2a6966aed29d09efa4c2.jpg)

![36a063d58f296a55758d02091c007305ac71f6f5af7d3e8c2e5dbebd9c92e796.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/36a063d58f296a55758d02091c007305ac71f6f5af7d3e8c2e5dbebd9c92e796.jpg)

![42c0a10afc5310363c27799fdafd5ed49d2de4435dd7b2cc677bf3122e22dcbf.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/42c0a10afc5310363c27799fdafd5ed49d2de4435dd7b2cc677bf3122e22dcbf.jpg)

![6c6a7387683fa2abf47886201d04520bf020b3c3c6f09bea0af7b2be53ef1d50.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/6c6a7387683fa2abf47886201d04520bf020b3c3c6f09bea0af7b2be53ef1d50.jpg)

![8fa57d4c6d528a8c52adda6ce9088154ac49c5cc81cf3f0e358ae24170fb50ab.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/8fa57d4c6d528a8c52adda6ce9088154ac49c5cc81cf3f0e358ae24170fb50ab.jpg)

![a3e52abcf55f90f2ccd349c6c014442a9d450d7ad889e161df9b16bd3095458e.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/a3e52abcf55f90f2ccd349c6c014442a9d450d7ad889e161df9b16bd3095458e.jpg)

![c2b8ecd40be2eb5255e2864238e4049efba1cacb6ebb387f4411fad0764aa255.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/c2b8ecd40be2eb5255e2864238e4049efba1cacb6ebb387f4411fad0764aa255.jpg)

![c2d0670fcb8f6d7ae8fc78cb171f54b6a86eecf003618c19e38e7fc03572d353.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/c2d0670fcb8f6d7ae8fc78cb171f54b6a86eecf003618c19e38e7fc03572d353.jpg)

![c7a49bb627271e6cacb8de002fd120c53eab527cc2ca0e5ea7b7f12ccee888e4.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/c7a49bb627271e6cacb8de002fd120c53eab527cc2ca0e5ea7b7f12ccee888e4.jpg)

![cedef6f1c27a149a6ea1d0279a4bf963d71741de6ea650fb6497ae8ea839eea5.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/cedef6f1c27a149a6ea1d0279a4bf963d71741de6ea650fb6497ae8ea839eea5.jpg)

![d802e877f5614d833536749edba89e62e46041675c5279239a12a6187946b7a7.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/d802e877f5614d833536749edba89e62e46041675c5279239a12a6187946b7a7.jpg)

![fa5bbd59d83055311e9548d1f1bdac373c13d5517d3167f63b63bba04cceb34b.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/fa5bbd59d83055311e9548d1f1bdac373c13d5517d3167f63b63bba04cceb34b.jpg)

![fc5c4df63aef9f74879f1028c51af61ef69d46f552e0aeb046d2e6bc79374eac.jpg](../nips_results/218_ShapeLLM-Omni_%20A%20Native%20Multimodal%20LLM%20for%203D%20Generation%20and%20Understanding/tables/fc5c4df63aef9f74879f1028c51af61ef69d46f552e0aeb046d2e6bc79374eac.jpg)

## G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems


### Images

![163960f0fc58c85f65dfbf40ed0a1dc3a5bb61d95c8722df543f28148e1df5d6.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/163960f0fc58c85f65dfbf40ed0a1dc3a5bb61d95c8722df543f28148e1df5d6.jpg)

![17578c78f06f55e159a3a919d20501bc0454471a610587fa114e910e4aadba64.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/17578c78f06f55e159a3a919d20501bc0454471a610587fa114e910e4aadba64.jpg)

![2da06da608d8bec405f53bb885dd9681d376d4e3daf2900be0a8ddd90e443e5c.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/2da06da608d8bec405f53bb885dd9681d376d4e3daf2900be0a8ddd90e443e5c.jpg)

![2ec40e2b887d1be5ff93bc753df8d0d93cf15c45b6e49fe6a6f0994cc3c182e4.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/2ec40e2b887d1be5ff93bc753df8d0d93cf15c45b6e49fe6a6f0994cc3c182e4.jpg)

![48772f699bccd9ecf7285d9f2c4af85d34d60b7ee6b2cbd681278611869db12b.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/48772f699bccd9ecf7285d9f2c4af85d34d60b7ee6b2cbd681278611869db12b.jpg)

![5df8b74ea7fd2e91de73b24eb17f3f81db11cc3994f3a9f731d4e95e74bc6132.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/5df8b74ea7fd2e91de73b24eb17f3f81db11cc3994f3a9f731d4e95e74bc6132.jpg)

![62f26e1a3772367dfb122aca7acbc52357f15fc9f0c98bb2e5d804a4e32ebb0b.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/62f26e1a3772367dfb122aca7acbc52357f15fc9f0c98bb2e5d804a4e32ebb0b.jpg)

![673dc9bc2317a053f9111293d38a662ea3a946ce6891edc314ce0acdb0701e8c.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/673dc9bc2317a053f9111293d38a662ea3a946ce6891edc314ce0acdb0701e8c.jpg)

![69897fe04c46eb64b8fd5c5401bb0de6051e2328c75d13bdabd06ee8c4a9dc47.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/69897fe04c46eb64b8fd5c5401bb0de6051e2328c75d13bdabd06ee8c4a9dc47.jpg)

![888d09bfe90fbdd1b5fc3030d1b2cb409015ad0f9adc8806717590e1e68a80fa.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/888d09bfe90fbdd1b5fc3030d1b2cb409015ad0f9adc8806717590e1e68a80fa.jpg)

![9220ecebed8aca98226b824009ca9796d8c5d7924b12841a9d91b75df04b3380.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/9220ecebed8aca98226b824009ca9796d8c5d7924b12841a9d91b75df04b3380.jpg)

![9c661751a01b7aea0f1980a3dcc1703f0404ad10010c29e678cace5440d53529.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/9c661751a01b7aea0f1980a3dcc1703f0404ad10010c29e678cace5440d53529.jpg)

![a8127d5e3ca6ec8d8db45e3ddc86394115197966901beb06863cf5ef4c2cfad4.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/a8127d5e3ca6ec8d8db45e3ddc86394115197966901beb06863cf5ef4c2cfad4.jpg)

![c648a22bdab321a9e6d4ad638339c80d9071a567c536c211375f27cf392d707f.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/c648a22bdab321a9e6d4ad638339c80d9071a567c536c211375f27cf392d707f.jpg)

![d18052e31d4c4e7975dbe80192d31ce20397d5b31db5af5b007564525204a30f.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/d18052e31d4c4e7975dbe80192d31ce20397d5b31db5af5b007564525204a30f.jpg)

![d784ce0756ebd3ed820657102316fce9a6003b8bb5867d0cfa4d2d183c5b3d05.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/d784ce0756ebd3ed820657102316fce9a6003b8bb5867d0cfa4d2d183c5b3d05.jpg)

![e53e63304f54af923c43629fa4ea1fc804e15c30c20e7a6071d9ca1d0509a9f7.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/e53e63304f54af923c43629fa4ea1fc804e15c30c20e7a6071d9ca1d0509a9f7.jpg)

![e649c8eb44e1f33f3ec3b47570d043937a9c7e93222098a6b9cfc9bdae572d5a.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/e649c8eb44e1f33f3ec3b47570d043937a9c7e93222098a6b9cfc9bdae572d5a.jpg)

![f9264cea116f1b048d24709e2522ccf469fecd2100c26164c64b684e0eae825b.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/images/f9264cea116f1b048d24709e2522ccf469fecd2100c26164c64b684e0eae825b.jpg)

### Tables

![4c7d3fd8e4381d7872cf95be391c48d24f3c7366911fad90ecccde955e0c65d6.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/tables/4c7d3fd8e4381d7872cf95be391c48d24f3c7366911fad90ecccde955e0c65d6.jpg)

![4dea079119d313e6b5f1c98d0b4eb057e73c57011ef2a410aff742901bf1a970.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/tables/4dea079119d313e6b5f1c98d0b4eb057e73c57011ef2a410aff742901bf1a970.jpg)

![70bfa89d6a66fb8aef0d5173e9d46b064d0b36871fc669ffe20fc8601dccd947.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/tables/70bfa89d6a66fb8aef0d5173e9d46b064d0b36871fc669ffe20fc8601dccd947.jpg)

![b4af226e783e6117cc59fa4bff6d2f838f433b444896f9b2073f4f68fc0c9d39.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/tables/b4af226e783e6117cc59fa4bff6d2f838f433b444896f9b2073f4f68fc0c9d39.jpg)

![be7ff511fb253c46c0ff9a1c665dd383e38689379700e87f2dc963d19cb40423.jpg](../nips_results/219_G-Memory_%20Tracing%20Hierarchical%20Memory%20for%20Multi-Agent%20Systems/tables/be7ff511fb253c46c0ff9a1c665dd383e38689379700e87f2dc963d19cb40423.jpg)

## AgentBreeder: Mitigating the AI Safety Risks of Multi-Agent Scaffolds via Self-Improvement


### Images

![0bd26adee023a80d15c93462cbba328dc3185ccc730a49883dbcb499ab4006b7.jpg](../nips_results/220_AgentBreeder_%20Mitigating%20the%20AI%20Safety%20Risks%20of%20Multi-Agent%20Scaffolds%20via%20Self-Improvement/images/0bd26adee023a80d15c93462cbba328dc3185ccc730a49883dbcb499ab4006b7.jpg)

![79302941e918e4111ba3e5836eafc0b92c5af69ab04ede3793a31772113e90c1.jpg](../nips_results/220_AgentBreeder_%20Mitigating%20the%20AI%20Safety%20Risks%20of%20Multi-Agent%20Scaffolds%20via%20Self-Improvement/images/79302941e918e4111ba3e5836eafc0b92c5af69ab04ede3793a31772113e90c1.jpg)

![f51c73596751d3570b06998d022a331c58855cddc34d3d8819cf96653b19092d.jpg](../nips_results/220_AgentBreeder_%20Mitigating%20the%20AI%20Safety%20Risks%20of%20Multi-Agent%20Scaffolds%20via%20Self-Improvement/images/f51c73596751d3570b06998d022a331c58855cddc34d3d8819cf96653b19092d.jpg)

### Tables

![0c738092e3b3b90d2a7bb560b77ed35de08404e44bed620cc81e2913c0e7b8d6.jpg](../nips_results/220_AgentBreeder_%20Mitigating%20the%20AI%20Safety%20Risks%20of%20Multi-Agent%20Scaffolds%20via%20Self-Improvement/tables/0c738092e3b3b90d2a7bb560b77ed35de08404e44bed620cc81e2913c0e7b8d6.jpg)

![19678b9a3122f4eac5d689dec11ed4ad75aa8a931e659556032301a5e42d926a.jpg](../nips_results/220_AgentBreeder_%20Mitigating%20the%20AI%20Safety%20Risks%20of%20Multi-Agent%20Scaffolds%20via%20Self-Improvement/tables/19678b9a3122f4eac5d689dec11ed4ad75aa8a931e659556032301a5e42d926a.jpg)

![90742492eeb71ec93fec53c55e62fa18f32dbb351c4117a93e7bc89068f62a05.jpg](../nips_results/220_AgentBreeder_%20Mitigating%20the%20AI%20Safety%20Risks%20of%20Multi-Agent%20Scaffolds%20via%20Self-Improvement/tables/90742492eeb71ec93fec53c55e62fa18f32dbb351c4117a93e7bc89068f62a05.jpg)

![98ce8dd5f0457ad43596dd4f606e70f5684ccbe405694fd948a3c29f5341c336.jpg](../nips_results/220_AgentBreeder_%20Mitigating%20the%20AI%20Safety%20Risks%20of%20Multi-Agent%20Scaffolds%20via%20Self-Improvement/tables/98ce8dd5f0457ad43596dd4f606e70f5684ccbe405694fd948a3c29f5341c336.jpg)

![f531d1689a55d2fcc09da043db2dfa54d7feb357d9f08036e4b0e26d8149d6ab.jpg](../nips_results/220_AgentBreeder_%20Mitigating%20the%20AI%20Safety%20Risks%20of%20Multi-Agent%20Scaffolds%20via%20Self-Improvement/tables/f531d1689a55d2fcc09da043db2dfa54d7feb357d9f08036e4b0e26d8149d6ab.jpg)

## Gradient-Variation Online Adaptivity for Accelerated Optimization with Hölder Smoothness


### Tables

![a43e6666f85d17d40d1d3b2dd5866ef42c92330d680f3d21c32c66ee0c0e0376.jpg](../nips_results/221_Gradient-Variation%20Online%20Adaptivity%20for%20Accelerated%20Optimization%20with%20H%C3%B6lder%20Smoothness/tables/a43e6666f85d17d40d1d3b2dd5866ef42c92330d680f3d21c32c66ee0c0e0376.jpg)

![e362bf746b893127903c8d20b60cd0c98b880e3b13789ff82063844c79e45465.jpg](../nips_results/221_Gradient-Variation%20Online%20Adaptivity%20for%20Accelerated%20Optimization%20with%20H%C3%B6lder%20Smoothness/tables/e362bf746b893127903c8d20b60cd0c98b880e3b13789ff82063844c79e45465.jpg)

## Ridge Boosting is Both Robust and Efficient


### Images

![1848aa728c55717e822f27fb8070f1a806fe5a606a8d063965c9118246d662ed.jpg](../nips_results/222_Ridge%20Boosting%20is%20Both%20Robust%20and%20Efficient/images/1848aa728c55717e822f27fb8070f1a806fe5a606a8d063965c9118246d662ed.jpg)

![a1082bab8f10b8fe984f5012c274865a15aed35a5be37e426368d76da6608384.jpg](../nips_results/222_Ridge%20Boosting%20is%20Both%20Robust%20and%20Efficient/images/a1082bab8f10b8fe984f5012c274865a15aed35a5be37e426368d76da6608384.jpg)

## Self Forcing: Bridging the Train-Test Gap in Autoregressive Video Diffusion


### Images

![3dad287def705f5167fa59ecaa276d677f2a7517899fe178a287d6c94d5fa1fe.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/images/3dad287def705f5167fa59ecaa276d677f2a7517899fe178a287d6c94d5fa1fe.jpg)

![4e991f8ad5e527807fe8df21c523ccfdb4825718af90e835635b2866b758f64c.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/images/4e991f8ad5e527807fe8df21c523ccfdb4825718af90e835635b2866b758f64c.jpg)

![542272891f29d65bc30f066be396dc189bf6c886ca0146e63329e679bb8b708a.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/images/542272891f29d65bc30f066be396dc189bf6c886ca0146e63329e679bb8b708a.jpg)

![6a8b5a17aa0b35355f4986f247a469c3771cc141b54b346e6fdc3c2c5474012f.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/images/6a8b5a17aa0b35355f4986f247a469c3771cc141b54b346e6fdc3c2c5474012f.jpg)

![77fc30a96362975a92bf525235a62c4b9ef29279e51a7bd50db2e22b85b6ea9c.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/images/77fc30a96362975a92bf525235a62c4b9ef29279e51a7bd50db2e22b85b6ea9c.jpg)

![83fed1ce60cf802000f671b92a99ef79bc814f907cfb99ae9b2619f684cc6a74.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/images/83fed1ce60cf802000f671b92a99ef79bc814f907cfb99ae9b2619f684cc6a74.jpg)

![8dd763bdc3ca6f998fd18a730a202e5ee2a73081c60af4f5988eb2b6b1db329d.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/images/8dd763bdc3ca6f998fd18a730a202e5ee2a73081c60af4f5988eb2b6b1db329d.jpg)

![bba78fe0fd9714e1c5e1a7bc85777867a0f846c610c5e0d87b2a4a539bf30fee.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/images/bba78fe0fd9714e1c5e1a7bc85777867a0f846c610c5e0d87b2a4a539bf30fee.jpg)

![ea2d152da86fa8ef516c90769bf6e217ddd68644f0e9f06eb4e0ba3ef4aec022.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/images/ea2d152da86fa8ef516c90769bf6e217ddd68644f0e9f06eb4e0ba3ef4aec022.jpg)

### Tables

![0683b13c8cea79a9316af4dc5ba247e2a2f17786f256fbaabfe90d3cc400903d.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/tables/0683b13c8cea79a9316af4dc5ba247e2a2f17786f256fbaabfe90d3cc400903d.jpg)

![0ccc02507d5b9eb55264fd353330ae89bf6699be6dc85a487e4b6849ac76833f.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/tables/0ccc02507d5b9eb55264fd353330ae89bf6699be6dc85a487e4b6849ac76833f.jpg)

![15ef9cc5da21b5afdb2687682082db5dea16a702f37b1af03fa4f1a4aa4f0d15.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/tables/15ef9cc5da21b5afdb2687682082db5dea16a702f37b1af03fa4f1a4aa4f0d15.jpg)

![6a2643733b59ce080aabb87d34c88b3236e690e3e853ff1aefecd61de9e4978e.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/tables/6a2643733b59ce080aabb87d34c88b3236e690e3e853ff1aefecd61de9e4978e.jpg)

![8ab0b8b117e88e379c6af338f9acfdcfdb77c92685d5f59123aacb999f64a56d.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/tables/8ab0b8b117e88e379c6af338f9acfdcfdb77c92685d5f59123aacb999f64a56d.jpg)

![fdcff9451039c9467ef0438cf93bd53d943f475ba41cd48360187694f8d3667f.jpg](../nips_results/223_Self%20Forcing_%20Bridging%20the%20Train-Test%20Gap%20in%20Autoregressive%20Video%20Diffusion/tables/fdcff9451039c9467ef0438cf93bd53d943f475ba41cd48360187694f8d3667f.jpg)

## DeCaFlow: A deconfounding causal generative model


### Images

![0684a0827a9421ab179de027b40f8824fa947b981c669cbac8e143fc9d39f493.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/0684a0827a9421ab179de027b40f8824fa947b981c669cbac8e143fc9d39f493.jpg)

![08e5f32f5ac3e9ea1d81afa2615626e3919d9011aeed88bc9b5ab10fd33b9fee.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/08e5f32f5ac3e9ea1d81afa2615626e3919d9011aeed88bc9b5ab10fd33b9fee.jpg)

![10a154670cfcda1f4a27681194c653534d59bdd595a747d0705622302618af58.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/10a154670cfcda1f4a27681194c653534d59bdd595a747d0705622302618af58.jpg)

![149f04a71f7cad4bdf49aa073cdeb3e005feb8fbb9df0eabcfa672c610646def.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/149f04a71f7cad4bdf49aa073cdeb3e005feb8fbb9df0eabcfa672c610646def.jpg)

![1ed794b09f4c4ba19f5281ef062a21ca70ac30370cc7c3019b7ca2a7c5cfdaa8.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/1ed794b09f4c4ba19f5281ef062a21ca70ac30370cc7c3019b7ca2a7c5cfdaa8.jpg)

![3194dc7e6abaea8c3ce412a48c0b90723406d1cb94c2f25b1327559dafd7adae.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/3194dc7e6abaea8c3ce412a48c0b90723406d1cb94c2f25b1327559dafd7adae.jpg)

![48e5e3dbd95525e1db7738b31834d9ff82007adaf22f932d94662d9593f6ae0c.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/48e5e3dbd95525e1db7738b31834d9ff82007adaf22f932d94662d9593f6ae0c.jpg)

![49f7b6d7a720f159dce30cbc39283505df3c4edb5e88ffa341d5c0ae0dcdc033.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/49f7b6d7a720f159dce30cbc39283505df3c4edb5e88ffa341d5c0ae0dcdc033.jpg)

![4f9671a86270e858b42235c28a3807e22238daf5f033a4890bbd43800c91e8cd.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/4f9671a86270e858b42235c28a3807e22238daf5f033a4890bbd43800c91e8cd.jpg)

![59d12e34c9469b542f2ae8534ba887d10e02fdac2ee1d8e39438d16da54bbba2.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/59d12e34c9469b542f2ae8534ba887d10e02fdac2ee1d8e39438d16da54bbba2.jpg)

![5fba47679a9835407a4f49a18561c0f50edefec4d278e6d5160c3f0de651ba26.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/5fba47679a9835407a4f49a18561c0f50edefec4d278e6d5160c3f0de651ba26.jpg)

![692a51d55052d0e40bdd9f90eb9ab6264c747d6f6d18c1864fa5f9cdb4a81e96.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/692a51d55052d0e40bdd9f90eb9ab6264c747d6f6d18c1864fa5f9cdb4a81e96.jpg)

![6b8ceaa3f75b0b7a6a34b9a4d235ceb87d7faed69e144d7e7f7ee5ed64d62c64.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/6b8ceaa3f75b0b7a6a34b9a4d235ceb87d7faed69e144d7e7f7ee5ed64d62c64.jpg)

![727e6756b8b77684fe9252e8852d332ffdfb913fc211ef2c513f099faa63218b.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/727e6756b8b77684fe9252e8852d332ffdfb913fc211ef2c513f099faa63218b.jpg)

![78ffbf25e5448d24443d4476aac14261396dfd55dd4b943dc2a5d7af394b839d.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/78ffbf25e5448d24443d4476aac14261396dfd55dd4b943dc2a5d7af394b839d.jpg)

![79c682c694c9f905deaa2da625ed3a20d80b9c2263d4573814d9bbe1cccb1088.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/79c682c694c9f905deaa2da625ed3a20d80b9c2263d4573814d9bbe1cccb1088.jpg)

![7fc0b109d8148cf51e5dda020ff493c2e25932dab4f9f66a3e36a4f945fc719c.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/7fc0b109d8148cf51e5dda020ff493c2e25932dab4f9f66a3e36a4f945fc719c.jpg)

![813bf5b11dd1ed2058edf74bbd7ec36b51aa2cdedc1cae3b1116158cd235e840.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/813bf5b11dd1ed2058edf74bbd7ec36b51aa2cdedc1cae3b1116158cd235e840.jpg)

![82d0c848281181e21e375a6d792d9674451361247ef0ab142ab27a84f6bbfca8.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/82d0c848281181e21e375a6d792d9674451361247ef0ab142ab27a84f6bbfca8.jpg)

![94c98ebfa3d6af0c7ba76efc909ab0a2a9fa51410dab5603f0e7af3005f5be7b.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/94c98ebfa3d6af0c7ba76efc909ab0a2a9fa51410dab5603f0e7af3005f5be7b.jpg)

![9aace05ce5e3a502e10975f54ad3ea0b6af7d1a8e630aa879350d186ba6648fd.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/9aace05ce5e3a502e10975f54ad3ea0b6af7d1a8e630aa879350d186ba6648fd.jpg)

![9c47d307374ce2688cb3f6435bd49771b45d34e3d468aa62e9cdd5b052c99889.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/9c47d307374ce2688cb3f6435bd49771b45d34e3d468aa62e9cdd5b052c99889.jpg)

![b04197208051a5290ae8dda6d7ab23e1de19dcb3ecb24e768308dfbac421cd71.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/b04197208051a5290ae8dda6d7ab23e1de19dcb3ecb24e768308dfbac421cd71.jpg)

![b5eda02898c5f95158c81d0611b51f19111f16a99f74307a95099a5469132485.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/b5eda02898c5f95158c81d0611b51f19111f16a99f74307a95099a5469132485.jpg)

![b6cd4e8bb2da9e95e11446f78ff8b954e6e56e5c35e6ab20c69900192ee0d07b.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/b6cd4e8bb2da9e95e11446f78ff8b954e6e56e5c35e6ab20c69900192ee0d07b.jpg)

![bc9c6a3a27c89a6fcac6d254c3b56dde7ef7ceffaeaddc0782aba59c9a2f08d7.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/bc9c6a3a27c89a6fcac6d254c3b56dde7ef7ceffaeaddc0782aba59c9a2f08d7.jpg)

![c8febcafc370f26fe29661102797263c1cd70564bbfd4efad4ae77ff0f5b7d1e.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/c8febcafc370f26fe29661102797263c1cd70564bbfd4efad4ae77ff0f5b7d1e.jpg)

![dabadedcd7f80016deeeaaf210f4557aebf72dd3f14f4f58af96da040d9c03a7.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/dabadedcd7f80016deeeaaf210f4557aebf72dd3f14f4f58af96da040d9c03a7.jpg)

![e0480285856106cb9938fcd0143987efacdaab31ccb7f18b5d186e4c53c3f2b6.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/e0480285856106cb9938fcd0143987efacdaab31ccb7f18b5d186e4c53c3f2b6.jpg)

![f3630a8cc079efe318cba4dfd91cdaafb4b90665bd529be1909d01a3cb121961.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/images/f3630a8cc079efe318cba4dfd91cdaafb4b90665bd529be1909d01a3cb121961.jpg)

### Tables

![038ba295f260de3c7e162bbb68cf273954edb01bc9581c5c1edfec07efb10476.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/tables/038ba295f260de3c7e162bbb68cf273954edb01bc9581c5c1edfec07efb10476.jpg)

![0d743b07722fa738d81d5543350d4e2e11c248d0d4b417e579bc87a546f8e930.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/tables/0d743b07722fa738d81d5543350d4e2e11c248d0d4b417e579bc87a546f8e930.jpg)

![312c25830ab344cc988bf6fbece14d2b829a42b8be9b7fa2cbfe9811e3fc4068.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/tables/312c25830ab344cc988bf6fbece14d2b829a42b8be9b7fa2cbfe9811e3fc4068.jpg)

![71878d2ef4136bff5b1e1aade7eef8c6fe042745ef4463d8006d08e33d423e56.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/tables/71878d2ef4136bff5b1e1aade7eef8c6fe042745ef4463d8006d08e33d423e56.jpg)

![7e35acfebba573371952abad8402b4e38b7c8caf256a352609c2cfd418f0680d.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/tables/7e35acfebba573371952abad8402b4e38b7c8caf256a352609c2cfd418f0680d.jpg)

![9a54f0db76a838580e848766e148fb946d116bc96e8a1c9aa895ae2d83346ac2.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/tables/9a54f0db76a838580e848766e148fb946d116bc96e8a1c9aa895ae2d83346ac2.jpg)

![a48fc762ee2dec9ee5ab0e4ef3cc507b79b87a7043338b4d339a0ef300126faf.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/tables/a48fc762ee2dec9ee5ab0e4ef3cc507b79b87a7043338b4d339a0ef300126faf.jpg)

![e0950244e0e4130847f0b4d836d4563055428be888a164d2fe2c37003e3a4481.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/tables/e0950244e0e4130847f0b4d836d4563055428be888a164d2fe2c37003e3a4481.jpg)

![eb8717aaad747b0437877cce70feac0133261cdd9a1edc5c18b2fab4de6b87eb.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/tables/eb8717aaad747b0437877cce70feac0133261cdd9a1edc5c18b2fab4de6b87eb.jpg)

![f161f4d06602b51e61b3fa7ecd10901be2dc6bf7e7b0a02bfbb9ab08649b8246.jpg](../nips_results/224_DeCaFlow_%20A%20deconfounding%20causal%20generative%20model/tables/f161f4d06602b51e61b3fa7ecd10901be2dc6bf7e7b0a02bfbb9ab08649b8246.jpg)

## Caption This, Reason That: VLMs Caught in the Middle


### Images

![0a7ec4e3bce5419277a92fec483b560c1ff8e4e22590256842a65dd5eb3a460d.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/0a7ec4e3bce5419277a92fec483b560c1ff8e4e22590256842a65dd5eb3a460d.jpg)

![0ba0cceccc59acb4ccfe0f2f0361a6241b840e42d129a5f982a748de6952918b.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/0ba0cceccc59acb4ccfe0f2f0361a6241b840e42d129a5f982a748de6952918b.jpg)

![19906c40694b4a349ee46bf4a4e8629e797623eb3d2dc530808ef72117244a9b.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/19906c40694b4a349ee46bf4a4e8629e797623eb3d2dc530808ef72117244a9b.jpg)

![2abb10072f1dd814c492032defb1a763ce06df936900a5fa46c68106a4207658.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/2abb10072f1dd814c492032defb1a763ce06df936900a5fa46c68106a4207658.jpg)

![33a33fa374e5efea4747b68e65c7b2ea9735d1d1318678ffe36a5c2e512cc408.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/33a33fa374e5efea4747b68e65c7b2ea9735d1d1318678ffe36a5c2e512cc408.jpg)

![471f106e5aaa94e60750f16701fcf56f0484fc76bc64b0f899a94513b958bf7d.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/471f106e5aaa94e60750f16701fcf56f0484fc76bc64b0f899a94513b958bf7d.jpg)

![4c6a35d393321dd27e8d73cd5a58ffba30038dc5ed6c260c527185c6926da1dd.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/4c6a35d393321dd27e8d73cd5a58ffba30038dc5ed6c260c527185c6926da1dd.jpg)

![4edb819f9e607c0ca22e1412ec1b75628c4d93421678f6af49b07951ccb0c596.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/4edb819f9e607c0ca22e1412ec1b75628c4d93421678f6af49b07951ccb0c596.jpg)

![526610c6d53549fc65f662a29906ada92422397360b9601792112d7e0ff2a340.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/526610c6d53549fc65f662a29906ada92422397360b9601792112d7e0ff2a340.jpg)

![6af5693d897d18f7a29aec371a3660e7823bc64cfa0e910211957b64dc03fda0.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/6af5693d897d18f7a29aec371a3660e7823bc64cfa0e910211957b64dc03fda0.jpg)

![70b4beebd922499900ce4dac932d6990f74b977beee184f0e2ce419724994df6.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/70b4beebd922499900ce4dac932d6990f74b977beee184f0e2ce419724994df6.jpg)

![73af38731cf89828d1184dbaa7c18cb6981026a7290a788f335b29dd2b6c1d40.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/73af38731cf89828d1184dbaa7c18cb6981026a7290a788f335b29dd2b6c1d40.jpg)

![7d9b381337c116979023000d6a96042f5c1fda8bc567e4092b69c5874f8cf99c.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/7d9b381337c116979023000d6a96042f5c1fda8bc567e4092b69c5874f8cf99c.jpg)

![918b189464124968891ed2fce54559c03a84ba5bec73890d87a53bf7c7fd8e11.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/918b189464124968891ed2fce54559c03a84ba5bec73890d87a53bf7c7fd8e11.jpg)

![984ccec79c0bc72843a2fdef58861926acc456613194bc493a410645fc6b4ee3.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/984ccec79c0bc72843a2fdef58861926acc456613194bc493a410645fc6b4ee3.jpg)

![b2428ffc34f01c35b2f205b9bb3e84e54c4db5b5181ace471a2ca2c5899c565f.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/b2428ffc34f01c35b2f205b9bb3e84e54c4db5b5181ace471a2ca2c5899c565f.jpg)

![c6b02521a6f12c1196e0f3c684ab384738bff2df78672069c8d5d2e877c69dfc.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/c6b02521a6f12c1196e0f3c684ab384738bff2df78672069c8d5d2e877c69dfc.jpg)

![d368a3c4e273ee588b684eb5cde520c1dae66f7a023a4f95de91e8c61a465836.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/d368a3c4e273ee588b684eb5cde520c1dae66f7a023a4f95de91e8c61a465836.jpg)

![e63064eb447bb1471102ca9855d0d19390af5830fad6d885a91132298e2b0689.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/images/e63064eb447bb1471102ca9855d0d19390af5830fad6d885a91132298e2b0689.jpg)

### Tables

![0d27ad0f09c0481a409ceee8e303ccefe01e97c6e7bf8c90dc1b4bce52b478b7.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/0d27ad0f09c0481a409ceee8e303ccefe01e97c6e7bf8c90dc1b4bce52b478b7.jpg)

![1eb11a8fbbf36bd171d936f4f4a798dac3206d8a5dae80d196781a3259232670.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/1eb11a8fbbf36bd171d936f4f4a798dac3206d8a5dae80d196781a3259232670.jpg)

![234d790e0e864259c1cd93dc9a18ad71c432d5b23181846990d30f061aa9b10d.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/234d790e0e864259c1cd93dc9a18ad71c432d5b23181846990d30f061aa9b10d.jpg)

![35630883e3b9c4f49c8071345d87109af3b492044e2f38e59ef04c9b1053bc62.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/35630883e3b9c4f49c8071345d87109af3b492044e2f38e59ef04c9b1053bc62.jpg)

![45ac53330e3d4ae39fc9aee8fc90b526aeaad2fc7a33ddce0bba9db99c7bcdd2.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/45ac53330e3d4ae39fc9aee8fc90b526aeaad2fc7a33ddce0bba9db99c7bcdd2.jpg)

![5513aa26c72ae6aeab222bff7f681eba8eb465317bfd201fa35059f87b8bf766.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/5513aa26c72ae6aeab222bff7f681eba8eb465317bfd201fa35059f87b8bf766.jpg)

![59d3ebd938b11a49a69c842acb6b568787e1102c29916dc8c9905c40943f2726.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/59d3ebd938b11a49a69c842acb6b568787e1102c29916dc8c9905c40943f2726.jpg)

![5ee10a4f0f45dd23dfc4a00b6a15a93fe811a680ca30fa48ea020281b0d04bb2.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/5ee10a4f0f45dd23dfc4a00b6a15a93fe811a680ca30fa48ea020281b0d04bb2.jpg)

![64df7e1636e75770db1ccc7d2cc84ed7c272626a40786d8531390652945f4e38.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/64df7e1636e75770db1ccc7d2cc84ed7c272626a40786d8531390652945f4e38.jpg)

![afc89b9ec13a3f06c655b2ace2e9193b33cf7a615d36c051439c8cb903e0a407.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/afc89b9ec13a3f06c655b2ace2e9193b33cf7a615d36c051439c8cb903e0a407.jpg)

![b4ca6a15e0fd83e2f85c732f60e7f8c032ec8f4b4e1b810d4ace294a81aa2c3b.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/b4ca6a15e0fd83e2f85c732f60e7f8c032ec8f4b4e1b810d4ace294a81aa2c3b.jpg)

![b9a276e25b407cf2752ec5f3e4349086c396ad2e803b40133ed81c5dad60561c.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/b9a276e25b407cf2752ec5f3e4349086c396ad2e803b40133ed81c5dad60561c.jpg)

![db1d3bdb4f6e49300d1deb057fa384b5769012c65d6718cbcf0c0cf94706b3b6.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/db1d3bdb4f6e49300d1deb057fa384b5769012c65d6718cbcf0c0cf94706b3b6.jpg)

![e6f4e2a0af70916542d6cd2b028add67e2532c400353b2ebd9f8aa9be1502159.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/e6f4e2a0af70916542d6cd2b028add67e2532c400353b2ebd9f8aa9be1502159.jpg)

![ec43826719ffca04ee928164f0269ee141c81cd441759b86c99dd0b21d0d72db.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/ec43826719ffca04ee928164f0269ee141c81cd441759b86c99dd0b21d0d72db.jpg)

![f1676193e7d368280e5405e240097c658e9e01066f82057bb62dc7c7c2bb48fd.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/f1676193e7d368280e5405e240097c658e9e01066f82057bb62dc7c7c2bb48fd.jpg)

![f3d788346651b03911f31dd1e699a398152fcf545b23c75416fe93b8b80792b2.jpg](../nips_results/225_Caption%20This%2C%20Reason%20That_%20VLMs%20Caught%20in%20the%20Middle/tables/f3d788346651b03911f31dd1e699a398152fcf545b23c75416fe93b8b80792b2.jpg)

## Towards Comprehensive Scene Understanding: Integrating First and Third-Person Views for LVLMs


### Images

![05c411a15f899667c88fcbf025f8163dbce1feaf8dbe5d83fe332b45c8864514.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/05c411a15f899667c88fcbf025f8163dbce1feaf8dbe5d83fe332b45c8864514.jpg)

![0d58c3fede6a8d98c7619817d62e1f200767d2ebead176563bdf6a42cd1170ad.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/0d58c3fede6a8d98c7619817d62e1f200767d2ebead176563bdf6a42cd1170ad.jpg)

![0e8897652e078709204d7089375f48e17640cd08fadd36403b5ddf0896d76d94.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/0e8897652e078709204d7089375f48e17640cd08fadd36403b5ddf0896d76d94.jpg)

![110c0fd39d14d9d02518f64ec0f2851647b5fa5123e7d44a1b6ac6c32d4cd351.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/110c0fd39d14d9d02518f64ec0f2851647b5fa5123e7d44a1b6ac6c32d4cd351.jpg)

![16089c22b921713c9dc1b3a28260e51350af0ccbb08bf7396e095325e0d8e113.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/16089c22b921713c9dc1b3a28260e51350af0ccbb08bf7396e095325e0d8e113.jpg)

![1ada53147fa2b882e79a3bc2488b3a6ca28b8432495db45c13d65ae8ff27c68e.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/1ada53147fa2b882e79a3bc2488b3a6ca28b8432495db45c13d65ae8ff27c68e.jpg)

![244a892e782fc18edd40577d4aa4f238d62eaa1bf12e124ad4360f95d06b85e8.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/244a892e782fc18edd40577d4aa4f238d62eaa1bf12e124ad4360f95d06b85e8.jpg)

![270dac4256abac843f296fdbe81323386a5569b1c5c43ef29dbc727f1d0e075e.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/270dac4256abac843f296fdbe81323386a5569b1c5c43ef29dbc727f1d0e075e.jpg)

![344e72ca07cbbc70538a8cc8719335e1339acc53043fd1ddf206acde591282f1.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/344e72ca07cbbc70538a8cc8719335e1339acc53043fd1ddf206acde591282f1.jpg)

![3b60fe0584e62c86f0658643d0a5987f7ced438a665d69603563ecabcbabe226.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/3b60fe0584e62c86f0658643d0a5987f7ced438a665d69603563ecabcbabe226.jpg)

![496f34ca8fa3438a76766822bfd04f8cf35bfd13c522c5d1534b8d1e15d108b3.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/496f34ca8fa3438a76766822bfd04f8cf35bfd13c522c5d1534b8d1e15d108b3.jpg)

![53cf83394579c8bb95f25e82e4837c71599d31a5b8d5a2498d387b1de0b80d7a.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/53cf83394579c8bb95f25e82e4837c71599d31a5b8d5a2498d387b1de0b80d7a.jpg)

![55cd2953cd06048ab5c092203f0ee86bdd49895f5e6041c5222b62540466cf38.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/55cd2953cd06048ab5c092203f0ee86bdd49895f5e6041c5222b62540466cf38.jpg)

![5ecc43ebeee45f9db5c2f582f382c53dc332349fe128c5d65dff259aa3914213.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/5ecc43ebeee45f9db5c2f582f382c53dc332349fe128c5d65dff259aa3914213.jpg)

![6ebeb66b0e888c7b95088b8cdd0f1f98f49bb9ea3ed6173bd03363aafcf4b660.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/6ebeb66b0e888c7b95088b8cdd0f1f98f49bb9ea3ed6173bd03363aafcf4b660.jpg)

![7738900e2d802d79ad799373bc97eeed3f7c178240f13ee278ce60545be5d949.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/7738900e2d802d79ad799373bc97eeed3f7c178240f13ee278ce60545be5d949.jpg)

![77f501b5a4539681d64cc903d3dae9bf7cbba4926f31dc656bca2cb3dba7157a.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/77f501b5a4539681d64cc903d3dae9bf7cbba4926f31dc656bca2cb3dba7157a.jpg)

![795e6efd131f28123d6b276081f162dc768960c8d2d43bd64586c57c3c8574c3.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/795e6efd131f28123d6b276081f162dc768960c8d2d43bd64586c57c3c8574c3.jpg)

![79eca72367ece2c244ab4c1b645bbafb95c7a11d601a0c8efecbbe9215ee84c3.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/79eca72367ece2c244ab4c1b645bbafb95c7a11d601a0c8efecbbe9215ee84c3.jpg)

![7a79bf981bf2c5f779b10c37504d1305646d3dbab0c5d9acd599cfc6f453c35d.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/7a79bf981bf2c5f779b10c37504d1305646d3dbab0c5d9acd599cfc6f453c35d.jpg)

![8b8ed97e5e81471ba4a9ce63a0a80dd3a6dc6ec3656da1fa437fedcc69d1e11b.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/8b8ed97e5e81471ba4a9ce63a0a80dd3a6dc6ec3656da1fa437fedcc69d1e11b.jpg)

![939cceff45f20c6331fd271502a877d9285f7f153ca5d9ac7e92fbf8affe7c69.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/939cceff45f20c6331fd271502a877d9285f7f153ca5d9ac7e92fbf8affe7c69.jpg)

![94bd06ed789b05d18f622eea8abeeaca384c0fb099f5ffb3f4596e0e33f83b26.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/94bd06ed789b05d18f622eea8abeeaca384c0fb099f5ffb3f4596e0e33f83b26.jpg)

![a05f3ecf1d51f4cf691d88c89cbc94d983ed9a9e2ab2c6e58c7729d6abcc7c9e.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/a05f3ecf1d51f4cf691d88c89cbc94d983ed9a9e2ab2c6e58c7729d6abcc7c9e.jpg)

![a96654237f9837604a08c15b520ec9f275dbfe486f9cf8ec9be266d54d2c4268.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/a96654237f9837604a08c15b520ec9f275dbfe486f9cf8ec9be266d54d2c4268.jpg)

![bb7c075dd21ce2bf5915c911ff28e6c4380002e7962f62f039eb26ad1a30dbb0.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/bb7c075dd21ce2bf5915c911ff28e6c4380002e7962f62f039eb26ad1a30dbb0.jpg)

![bdc3addc6c3848b3f721a8365c6d9080b23bec06bd76ca783f832518da7a8f77.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/bdc3addc6c3848b3f721a8365c6d9080b23bec06bd76ca783f832518da7a8f77.jpg)

![c21f92d4bc1c46dadafaad9a84beee0ec63196db0a7a50d86ee941188ff35486.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/c21f92d4bc1c46dadafaad9a84beee0ec63196db0a7a50d86ee941188ff35486.jpg)

![d4f108f7e6fd4dc3148c4bbfc2849d0a112486f6fd3cab5698df09ed514faf55.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/d4f108f7e6fd4dc3148c4bbfc2849d0a112486f6fd3cab5698df09ed514faf55.jpg)

![de3dc5e71039c5c2830b1b695a3065bcfab33fe935c617e21702b523fb2efcda.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/de3dc5e71039c5c2830b1b695a3065bcfab33fe935c617e21702b523fb2efcda.jpg)

![e6cbce9a4e69e45d66a24eb65f0bddfaec89f1e26dd4cefbf588f270796a7509.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/e6cbce9a4e69e45d66a24eb65f0bddfaec89f1e26dd4cefbf588f270796a7509.jpg)

![f5ad76a0e8683fac1e69facd90e5da8ce227d6a5a893788775c2569eeb647f63.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/images/f5ad76a0e8683fac1e69facd90e5da8ce227d6a5a893788775c2569eeb647f63.jpg)

### Tables

![05e0324d867d72177858223b5ce22fe23db9fd3f9e544811ab91260e5f6f4ee4.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/tables/05e0324d867d72177858223b5ce22fe23db9fd3f9e544811ab91260e5f6f4ee4.jpg)

![3b6e116a883b9e1a85b9c02f86fca0a757e22455e450acd6213d3c88102bc6e2.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/tables/3b6e116a883b9e1a85b9c02f86fca0a757e22455e450acd6213d3c88102bc6e2.jpg)

![647aa7a7fbbb45a92fa948c51e35f6fb6e801adbeff63365e4f8a158f949f87e.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/tables/647aa7a7fbbb45a92fa948c51e35f6fb6e801adbeff63365e4f8a158f949f87e.jpg)

![67f24ddb448f68552f95ce71b3a85ed889180e2888ca67e8fb31a40dc7093ecb.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/tables/67f24ddb448f68552f95ce71b3a85ed889180e2888ca67e8fb31a40dc7093ecb.jpg)

![706d52fd23c8aef76acfcdd8283656b4c38e1489fb0431cf0e19dec22618959a.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/tables/706d52fd23c8aef76acfcdd8283656b4c38e1489fb0431cf0e19dec22618959a.jpg)

![a05cb22d169a66cb75c2974fc9a701561e5cdb93f647c414e539fd07e848f46c.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/tables/a05cb22d169a66cb75c2974fc9a701561e5cdb93f647c414e539fd07e848f46c.jpg)

![b18df60e0154972a7a02546a54137446ab44ca864dc41d044048b501a766c285.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/tables/b18df60e0154972a7a02546a54137446ab44ca864dc41d044048b501a766c285.jpg)

![b86cc5c9567a9f64242edfb45bfd3799ef77cde53ebea331657a1c67d88e561d.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/tables/b86cc5c9567a9f64242edfb45bfd3799ef77cde53ebea331657a1c67d88e561d.jpg)

![bf01cec964440a6cbe677daec4cd5647d3a063a7ab187fdc1225289b7bafa9ef.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/tables/bf01cec964440a6cbe677daec4cd5647d3a063a7ab187fdc1225289b7bafa9ef.jpg)

![c0277b370d79b22aeaa55d70af485905eb39b92402a84d1c184dab393eb2fc4e.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/tables/c0277b370d79b22aeaa55d70af485905eb39b92402a84d1c184dab393eb2fc4e.jpg)

![d26be105c1d830e14678919599180d47d6b620a4491bebdd7a9cd82c5b62dfb2.jpg](../nips_results/226_Towards%20Comprehensive%20Scene%20Understanding_%20Integrating%20First%20and%20Third-Person%20Views%20for%20LVLMs/tables/d26be105c1d830e14678919599180d47d6b620a4491bebdd7a9cd82c5b62dfb2.jpg)

## Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via Collective Monte Carlo Tree Search


### Images

![0c040da85df3a708670be5023b04a2e16ddb28c1129ceb28f15eaeff6d260223.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/0c040da85df3a708670be5023b04a2e16ddb28c1129ceb28f15eaeff6d260223.jpg)

![1b241f4033ef282f055a713aab070e8fc94ab3254f69761921043739e77f09c5.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/1b241f4033ef282f055a713aab070e8fc94ab3254f69761921043739e77f09c5.jpg)

![3072f5c2239c64f078221b34dcdf991ff2bf46f04b1fefeac75c107ab1c6c5b5.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/3072f5c2239c64f078221b34dcdf991ff2bf46f04b1fefeac75c107ab1c6c5b5.jpg)

![3d8987f52d921d7f296125abd5a29ea4c039a238776d6b416ba40801f088fef1.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/3d8987f52d921d7f296125abd5a29ea4c039a238776d6b416ba40801f088fef1.jpg)

![5c76eb1d7bbcd5af49cf22ef752b4444f8fb841fe0d370415a496298620265e4.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/5c76eb1d7bbcd5af49cf22ef752b4444f8fb841fe0d370415a496298620265e4.jpg)

![5fd81a482919b4af4e2dbbbb65c1a295658278c94799f0315d0600b397356778.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/5fd81a482919b4af4e2dbbbb65c1a295658278c94799f0315d0600b397356778.jpg)

![67f97b38d56924271b86dd27c46eb0d9bd607165b05dd57edc49ea4bfc07d236.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/67f97b38d56924271b86dd27c46eb0d9bd607165b05dd57edc49ea4bfc07d236.jpg)

![7c987fc8cf213eb47a038117cc38e5a170938289a390de4b8d7b6cd88512d505.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/7c987fc8cf213eb47a038117cc38e5a170938289a390de4b8d7b6cd88512d505.jpg)

![876b647056c0e2265b968d4a4e8b7168d8caed41c33bd6c9a8c665c07de67313.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/876b647056c0e2265b968d4a4e8b7168d8caed41c33bd6c9a8c665c07de67313.jpg)

![a2e0e493d6cbcda9e300757e1264812416fffd0fb4c9481e0081432dd34e032b.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/a2e0e493d6cbcda9e300757e1264812416fffd0fb4c9481e0081432dd34e032b.jpg)

![ac13220543f184fc0609c633c756ba34e1685e7398c1eb8a96a503b04cb433ca.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/ac13220543f184fc0609c633c756ba34e1685e7398c1eb8a96a503b04cb433ca.jpg)

![d730aa28636a6a55bfb86518a06600aef99a6f27ddebd842ce8902050828801d.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/d730aa28636a6a55bfb86518a06600aef99a6f27ddebd842ce8902050828801d.jpg)

![e01c741e1459c2c917eb8241259300fca42ea78835bd509341cc8ff33b7fea1c.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/e01c741e1459c2c917eb8241259300fca42ea78835bd509341cc8ff33b7fea1c.jpg)

![f4e2129305b4b58891c7e4d8a7ea9d54ad780dc6e0169caed978b087d192bdfa.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/images/f4e2129305b4b58891c7e4d8a7ea9d54ad780dc6e0169caed978b087d192bdfa.jpg)

### Tables

![0065a91179074df93742245cd514caa299de5733d9638f56ce00f4e264f10cef.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/0065a91179074df93742245cd514caa299de5733d9638f56ce00f4e264f10cef.jpg)

![009805eae6e3a0101caaed702c43bd7b9f0d6e505d2b142ba29e3aa0d820cfd3.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/009805eae6e3a0101caaed702c43bd7b9f0d6e505d2b142ba29e3aa0d820cfd3.jpg)

![030f3d49c6d10ed5c6fc07ff49c74e235c3aeae19e3dde77a3fe22e5bbe1cd5c.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/030f3d49c6d10ed5c6fc07ff49c74e235c3aeae19e3dde77a3fe22e5bbe1cd5c.jpg)

![0ebf7c9ba8ea6ba6ca043e72ee165bfd5022e85d4b5c49ee9a655ddd8cd47e0e.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/0ebf7c9ba8ea6ba6ca043e72ee165bfd5022e85d4b5c49ee9a655ddd8cd47e0e.jpg)

![2f624730ac6d7470265f525b8bd071cc14775249188572412f66de7ad60d6801.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/2f624730ac6d7470265f525b8bd071cc14775249188572412f66de7ad60d6801.jpg)

![300e886c616d36908ecdf81b146de87906aabd354d3e712303e0978ed3228597.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/300e886c616d36908ecdf81b146de87906aabd354d3e712303e0978ed3228597.jpg)

![3626a58e135871abff6f6e2421811ab30e959652b4bf851dbdfc76103945a759.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/3626a58e135871abff6f6e2421811ab30e959652b4bf851dbdfc76103945a759.jpg)

![4e3506237e8f9addbf1930ca20c8d9b322c182371d445e801285a3cd9b1f1849.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/4e3506237e8f9addbf1930ca20c8d9b322c182371d445e801285a3cd9b1f1849.jpg)

![6aaaf421172f3a8dcaf5056a4683ce1d6865e65ed40995a72a0e367a574008c0.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/6aaaf421172f3a8dcaf5056a4683ce1d6865e65ed40995a72a0e367a574008c0.jpg)

![6bab146209051143e2ac909c6f7954db1bf43c47934406c6f806272457da7c47.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/6bab146209051143e2ac909c6f7954db1bf43c47934406c6f806272457da7c47.jpg)

![7d746f8064c2aa3890f4cd5b96576c4fadc61dcb7c16b31f47d050050e4edff1.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/7d746f8064c2aa3890f4cd5b96576c4fadc61dcb7c16b31f47d050050e4edff1.jpg)

![8bbe2ce497d57e6f904d96a4680b9f2d5cc462467070377526e5aa76f14afc5b.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/8bbe2ce497d57e6f904d96a4680b9f2d5cc462467070377526e5aa76f14afc5b.jpg)

![ad9227031973ef93cbe81ab71d4e678166e65c391982a4e914bc508e40f6f98a.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/ad9227031973ef93cbe81ab71d4e678166e65c391982a4e914bc508e40f6f98a.jpg)

![d26fde220a137caab971edaaa46c3786dc2899312c8329f24be94fabb5ca8690.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/d26fde220a137caab971edaaa46c3786dc2899312c8329f24be94fabb5ca8690.jpg)

![d705d6d3a5fef4e2ab475783cb076d76330df69c3bccfbb94130faa906150a2e.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/d705d6d3a5fef4e2ab475783cb076d76330df69c3bccfbb94130faa906150a2e.jpg)

![e72fa7b115bfd4036e46fded5ac14bf1acd4646511e3e7fcf43cfc2c546e89c4.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/e72fa7b115bfd4036e46fded5ac14bf1acd4646511e3e7fcf43cfc2c546e89c4.jpg)

![f8d4d5e4191075dd8f4b12abc9dd54655a04845174ca4b1523d79dfef501e230.jpg](../nips_results/227_Mulberry_%20Empowering%20MLLM%20with%20o1-like%20Reasoning%20and%20Reflection%20via%20Collective%20Monte%20Carlo%20Tree%20Sear/tables/f8d4d5e4191075dd8f4b12abc9dd54655a04845174ca4b1523d79dfef501e230.jpg)

## Approximate Domain Unlearning for Vision-Language Models


### Images

![16526b01083a8ec869d1e492f39069a0a7ac8b2f926e576b5a24cde8fb639bb3.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/images/16526b01083a8ec869d1e492f39069a0a7ac8b2f926e576b5a24cde8fb639bb3.jpg)

![1793cf9ba9f3f86f256eaa1112d19ff6da1bb4cbca7d5f2befd1d9119f4d698d.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/images/1793cf9ba9f3f86f256eaa1112d19ff6da1bb4cbca7d5f2befd1d9119f4d698d.jpg)

![65ac344cf3631278633798fda4814c5f5585957783d4a22aa882b9ec9f9aba44.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/images/65ac344cf3631278633798fda4814c5f5585957783d4a22aa882b9ec9f9aba44.jpg)

![936783187f76f17660be0b9f8ae7bcde11f3077bc4f1ab2df22210e792627220.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/images/936783187f76f17660be0b9f8ae7bcde11f3077bc4f1ab2df22210e792627220.jpg)

![a89611d0bcc781cb2b0706d76cc88e7a124480d26ed9e06bd984563c04c529d6.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/images/a89611d0bcc781cb2b0706d76cc88e7a124480d26ed9e06bd984563c04c529d6.jpg)

![cb61d45df432db6f006572e6f57d3eac2d89f907d0e94bcf72824bf744178fee.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/images/cb61d45df432db6f006572e6f57d3eac2d89f907d0e94bcf72824bf744178fee.jpg)

![dbef17ea15d94a5e1214285abf3984a9d6df72c8e7746a985982200407904b80.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/images/dbef17ea15d94a5e1214285abf3984a9d6df72c8e7746a985982200407904b80.jpg)

![f5e74d4020701cead4d8fa221e496687a00d3508f287387e2d8d760e31a540f2.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/images/f5e74d4020701cead4d8fa221e496687a00d3508f287387e2d8d760e31a540f2.jpg)

![f7238dcf8d3939bf08da7e3ef0762a47247ba16eeb319912a91a661fd2d4a1dd.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/images/f7238dcf8d3939bf08da7e3ef0762a47247ba16eeb319912a91a661fd2d4a1dd.jpg)

### Tables

![06296a4891e89706d1fe3b24298ea9608fc33e773de3df42f1c72f44e3ea6dc5.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/06296a4891e89706d1fe3b24298ea9608fc33e773de3df42f1c72f44e3ea6dc5.jpg)

![08252dfe7798e7d83f83fbde68018460d6a2a442b9ca0ec879672cca63cfd2bb.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/08252dfe7798e7d83f83fbde68018460d6a2a442b9ca0ec879672cca63cfd2bb.jpg)

![09af73dcbd56b7d99c238f1d377c7cb247497a29fe57455b7ccd829f803324e1.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/09af73dcbd56b7d99c238f1d377c7cb247497a29fe57455b7ccd829f803324e1.jpg)

![342c9a415ff2bfc0c3d86397e5c9959a0017573f033301a8627db3f15f374ed5.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/342c9a415ff2bfc0c3d86397e5c9959a0017573f033301a8627db3f15f374ed5.jpg)

![4e3db31396ddb08c527a90673aa6911d5a7ac4ecd17f664ae0f1ff686d689908.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/4e3db31396ddb08c527a90673aa6911d5a7ac4ecd17f664ae0f1ff686d689908.jpg)

![67cb43d57abf5c175b5165869f282d6e89880ff8ec4533e3611ebb67b6e34b55.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/67cb43d57abf5c175b5165869f282d6e89880ff8ec4533e3611ebb67b6e34b55.jpg)

![69684a98c50c2cc645b313645472c971b5da10be2ce2f2139c1af3df5868e580.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/69684a98c50c2cc645b313645472c971b5da10be2ce2f2139c1af3df5868e580.jpg)

![7aef5634642f1263e86ab3872c5e267ca19f3d11dcd7877b4acb4b35683b9413.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/7aef5634642f1263e86ab3872c5e267ca19f3d11dcd7877b4acb4b35683b9413.jpg)

![7eb3965d716be0ca6c822fbb013d2f1dc2b5493497752f6579aeb46514c982c8.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/7eb3965d716be0ca6c822fbb013d2f1dc2b5493497752f6579aeb46514c982c8.jpg)

![870db12a056d5662e3f0c7d10ee4f16907dfbd0d3e9c084bd511caa962c06be0.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/870db12a056d5662e3f0c7d10ee4f16907dfbd0d3e9c084bd511caa962c06be0.jpg)

![a3c6a7d57e75987555f22d9dc6211d6aa655f885e8327159641684b7710ccff4.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/a3c6a7d57e75987555f22d9dc6211d6aa655f885e8327159641684b7710ccff4.jpg)

![e1208773b4a2f36ce42680e912a6c100c2dfec2151b52fe6ecbcb0de64fa0231.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/e1208773b4a2f36ce42680e912a6c100c2dfec2151b52fe6ecbcb0de64fa0231.jpg)

![e9ea349c1f5898e6b625a414e6e7a2e560667c9d8534890aa279f11df4a07bac.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/e9ea349c1f5898e6b625a414e6e7a2e560667c9d8534890aa279f11df4a07bac.jpg)

![f33464b0136e422e586d7b72d397f4f5d24c7aba7a54cf7fb1b6535a26d9f13c.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/f33464b0136e422e586d7b72d397f4f5d24c7aba7a54cf7fb1b6535a26d9f13c.jpg)

![f85e23045e112c7b84e26153c7927f70625b290f013880973342380f2107772e.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/f85e23045e112c7b84e26153c7927f70625b290f013880973342380f2107772e.jpg)

![ffbc0efafc543316dc84c3414266cfa015e78363a5e88dbebebc59c5c3d26012.jpg](../nips_results/228_Approximate%20Domain%20Unlearning%20for%20Vision-Language%20Models/tables/ffbc0efafc543316dc84c3414266cfa015e78363a5e88dbebebc59c5c3d26012.jpg)

## E2Former: An Efficient and Equivariant Transformer with Linear-Scaling Tensor Products


### Images

![0b92ceeca7b25823558692dafaf89044864b5145f65eaac43ce76851273d0554.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/images/0b92ceeca7b25823558692dafaf89044864b5145f65eaac43ce76851273d0554.jpg)

![4b3e8af53eba2af4164e00c4758dddee2ad2cae58c0ba9bac1719a050e4583d9.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/images/4b3e8af53eba2af4164e00c4758dddee2ad2cae58c0ba9bac1719a050e4583d9.jpg)

![aa357c2fd8362b9131452cb020b0687c3da908fe2e2ab61853e9e0349415cc60.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/images/aa357c2fd8362b9131452cb020b0687c3da908fe2e2ab61853e9e0349415cc60.jpg)

![b501bcad7830654e421726b37ea0d89207d68c72f0f6aa9179fec65e0c71b205.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/images/b501bcad7830654e421726b37ea0d89207d68c72f0f6aa9179fec65e0c71b205.jpg)

![dbf31c914118bdc6b622a7d48a3b8187bb91b4ace86c0311f63c9e395adf0105.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/images/dbf31c914118bdc6b622a7d48a3b8187bb91b4ace86c0311f63c9e395adf0105.jpg)

![fb4694d88a5097ee72a936634a832ced85d11e90079a4fabc3f1b8c28f24e5d6.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/images/fb4694d88a5097ee72a936634a832ced85d11e90079a4fabc3f1b8c28f24e5d6.jpg)

### Tables

![0dc149d150686feb1c0c9488403118b962d64c07f3c7fea5ba48bd40c37e0452.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/tables/0dc149d150686feb1c0c9488403118b962d64c07f3c7fea5ba48bd40c37e0452.jpg)

![182fbf5090a75b11bb30e20a1c362aad0f3e846cae0f567f109eaef8b851ebf4.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/tables/182fbf5090a75b11bb30e20a1c362aad0f3e846cae0f567f109eaef8b851ebf4.jpg)

![3af9fe57f3dbf445a41a2b3f1d2902bfaf88e999a25185426a2c6303e92c7f6e.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/tables/3af9fe57f3dbf445a41a2b3f1d2902bfaf88e999a25185426a2c6303e92c7f6e.jpg)

![3f81e89cf658b6e9c9645272e11cfb3577f98998584bf0a790370dc6f701b487.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/tables/3f81e89cf658b6e9c9645272e11cfb3577f98998584bf0a790370dc6f701b487.jpg)

![47f899c46a017ed895afe30f9d389e5892631ece2ee34436db9d8d2f732435a9.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/tables/47f899c46a017ed895afe30f9d389e5892631ece2ee34436db9d8d2f732435a9.jpg)

![5d005d40ad0e49cf2c66155803372c0cff2ec123186245db4321defc9723aef9.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/tables/5d005d40ad0e49cf2c66155803372c0cff2ec123186245db4321defc9723aef9.jpg)

![930cc00744f790c99722eea9e53fd6ba8da796c22c98c2431b724719c4c5ea7d.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/tables/930cc00744f790c99722eea9e53fd6ba8da796c22c98c2431b724719c4c5ea7d.jpg)

![bf48480f064e3a674a69b5202f2297318e2effe103fae0daee6aeec02928adec.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/tables/bf48480f064e3a674a69b5202f2297318e2effe103fae0daee6aeec02928adec.jpg)

![ed05637602e5755f8820c48cc4eb5ab977c616d76dc5531d7a479bf785e1e112.jpg](../nips_results/229_E2Former_%20An%20Efficient%20and%20Equivariant%20Transformer%20with%20Linear-Scaling%20Tensor%20Products/tables/ed05637602e5755f8820c48cc4eb5ab977c616d76dc5531d7a479bf785e1e112.jpg)

## Shift Before You Learn: Enabling Low-Rank Representations in Reinforcement Learning


### Images

![02bf10129252a01b4492aa0c86e617172e1015596ecb97ffb46a11b0f4e0b357.jpg](../nips_results/230_Shift%20Before%20You%20Learn_%20Enabling%20Low-Rank%20Representations%20in%20Reinforcement%20Learning/images/02bf10129252a01b4492aa0c86e617172e1015596ecb97ffb46a11b0f4e0b357.jpg)

![0cc51c16ed630a815d984460e66accf1d36bf1509fb355b1ff981701a9f6e498.jpg](../nips_results/230_Shift%20Before%20You%20Learn_%20Enabling%20Low-Rank%20Representations%20in%20Reinforcement%20Learning/images/0cc51c16ed630a815d984460e66accf1d36bf1509fb355b1ff981701a9f6e498.jpg)

![1bf88a544e78ec29f06466c94a1d6e7491da27111152a4a771fa59320765b083.jpg](../nips_results/230_Shift%20Before%20You%20Learn_%20Enabling%20Low-Rank%20Representations%20in%20Reinforcement%20Learning/images/1bf88a544e78ec29f06466c94a1d6e7491da27111152a4a771fa59320765b083.jpg)

![831e47c673a5cbd9ee26188cc94438fcde8e8c2bf3b01551dd5b2cda92b6db87.jpg](../nips_results/230_Shift%20Before%20You%20Learn_%20Enabling%20Low-Rank%20Representations%20in%20Reinforcement%20Learning/images/831e47c673a5cbd9ee26188cc94438fcde8e8c2bf3b01551dd5b2cda92b6db87.jpg)

![892d7ef8f781ce4518e2ac495b26d03ac4fe2adcf25a515373518e3bd0eb5900.jpg](../nips_results/230_Shift%20Before%20You%20Learn_%20Enabling%20Low-Rank%20Representations%20in%20Reinforcement%20Learning/images/892d7ef8f781ce4518e2ac495b26d03ac4fe2adcf25a515373518e3bd0eb5900.jpg)

![8f3c33e2f769a7deef4aad4e33ecd9f97dbec16e14c573e89e63c63bd6a5d355.jpg](../nips_results/230_Shift%20Before%20You%20Learn_%20Enabling%20Low-Rank%20Representations%20in%20Reinforcement%20Learning/images/8f3c33e2f769a7deef4aad4e33ecd9f97dbec16e14c573e89e63c63bd6a5d355.jpg)

![b820b861245dcbcdd22b44f99498c0bdc231896df53762566b2746d8d8b17fbe.jpg](../nips_results/230_Shift%20Before%20You%20Learn_%20Enabling%20Low-Rank%20Representations%20in%20Reinforcement%20Learning/images/b820b861245dcbcdd22b44f99498c0bdc231896df53762566b2746d8d8b17fbe.jpg)

![bb7cde8619527bafa0a8207614f0cf5f42fff4eb518046f396d77060473d1fdd.jpg](../nips_results/230_Shift%20Before%20You%20Learn_%20Enabling%20Low-Rank%20Representations%20in%20Reinforcement%20Learning/images/bb7cde8619527bafa0a8207614f0cf5f42fff4eb518046f396d77060473d1fdd.jpg)

![c2027aea34461d43d24fbeaf5205653dd8c68155ceaa1e4b2f105d98f736a3e7.jpg](../nips_results/230_Shift%20Before%20You%20Learn_%20Enabling%20Low-Rank%20Representations%20in%20Reinforcement%20Learning/images/c2027aea34461d43d24fbeaf5205653dd8c68155ceaa1e4b2f105d98f736a3e7.jpg)

![d8f2c46e1e9f0aba689408e9e2f321c94a39e563ca8d492ec354c0a125a9f56e.jpg](../nips_results/230_Shift%20Before%20You%20Learn_%20Enabling%20Low-Rank%20Representations%20in%20Reinforcement%20Learning/images/d8f2c46e1e9f0aba689408e9e2f321c94a39e563ca8d492ec354c0a125a9f56e.jpg)

![e63ac4b75b6ed4bd3e184635732364c086bc0935b51315fdaeb12de230ad4e87.jpg](../nips_results/230_Shift%20Before%20You%20Learn_%20Enabling%20Low-Rank%20Representations%20in%20Reinforcement%20Learning/images/e63ac4b75b6ed4bd3e184635732364c086bc0935b51315fdaeb12de230ad4e87.jpg)

## Estimating cognitive biases with attention-aware inverse planning


### Images

![0456fe659a4fca8f0a8ddb357ba3eba5bcf5b2326bbce100a81ba2a79cf98087.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/images/0456fe659a4fca8f0a8ddb357ba3eba5bcf5b2326bbce100a81ba2a79cf98087.jpg)

![4433ef80d3496542e7e915be4800f6a921170165bdc8911dfa8972902627ac27.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/images/4433ef80d3496542e7e915be4800f6a921170165bdc8911dfa8972902627ac27.jpg)

![606fe5f1160114d7c49207500487a1ba6a9ee340b0a0153cab040f988427f58e.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/images/606fe5f1160114d7c49207500487a1ba6a9ee340b0a0153cab040f988427f58e.jpg)

![617f658ac65384f9bc4d5bc0fb4450d63b50c8cd2485c8464f62be7f717803fb.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/images/617f658ac65384f9bc4d5bc0fb4450d63b50c8cd2485c8464f62be7f717803fb.jpg)

![6e95430c246d3bda82d60843ccbf6595917048c19808e3d964d7a800873d7191.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/images/6e95430c246d3bda82d60843ccbf6595917048c19808e3d964d7a800873d7191.jpg)

![8345a0dff283f43eca11694c6c97df44c88bcd498dc765b7f0b34a41487e32ed.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/images/8345a0dff283f43eca11694c6c97df44c88bcd498dc765b7f0b34a41487e32ed.jpg)

![baa58cbd5cc8f0531ac2083a11d824a2d7b4046e503f7f9cafe5749bdfc21980.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/images/baa58cbd5cc8f0531ac2083a11d824a2d7b4046e503f7f9cafe5749bdfc21980.jpg)

![c81b4ee0bb4fef06ac963401547032f890f8df443a1772ea834aafa04a658fe3.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/images/c81b4ee0bb4fef06ac963401547032f890f8df443a1772ea834aafa04a658fe3.jpg)

![d2b104fc7af436257717f42e83b7b301af3fa27f722b1f20bf352dbc0a9b24e8.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/images/d2b104fc7af436257717f42e83b7b301af3fa27f722b1f20bf352dbc0a9b24e8.jpg)

![dae4175c59b182bc1646258d13975dfcc79fd88b519d9ff13e22e256770ddbb2.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/images/dae4175c59b182bc1646258d13975dfcc79fd88b519d9ff13e22e256770ddbb2.jpg)

### Tables

![2d30dbcb9a444c21f76eea20649418f713ecf8bc8dd2ed0d9c74fe609c0dfa92.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/tables/2d30dbcb9a444c21f76eea20649418f713ecf8bc8dd2ed0d9c74fe609c0dfa92.jpg)

![7e776384e0c3d66b1b70921c75e4f21eae92f7002057144beb9d37b5d8c3be5a.jpg](../nips_results/231_Estimating%20cognitive%20biases%20with%20attention-aware%20inverse%20planning/tables/7e776384e0c3d66b1b70921c75e4f21eae92f7002057144beb9d37b5d8c3be5a.jpg)

## VoxDet: Rethinking 3D Semantic Scene Completion as Dense Object Detection


### Images

![02b9d66950790edea64e7b74371331816bcb37aaeb5ef9b0bdc53f966600f752.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/02b9d66950790edea64e7b74371331816bcb37aaeb5ef9b0bdc53f966600f752.jpg)

![05219028c1db33cb3ff1be712941d17c4d56dc4fdb5d10682c45df9593f4addf.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/05219028c1db33cb3ff1be712941d17c4d56dc4fdb5d10682c45df9593f4addf.jpg)

![17376e2f3a21eb4c1c6251f6cb11f0f81df49b57463ba5cae86c1bb69255f682.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/17376e2f3a21eb4c1c6251f6cb11f0f81df49b57463ba5cae86c1bb69255f682.jpg)

![199c0171fa03130ee6dd58929475984b0ee4587618a38e6530f8a131a85a0852.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/199c0171fa03130ee6dd58929475984b0ee4587618a38e6530f8a131a85a0852.jpg)

![4ff8b4bcf0b08a7447afaf780b0c0c5448971d8abebdc6bfc3674f2ad0b56950.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/4ff8b4bcf0b08a7447afaf780b0c0c5448971d8abebdc6bfc3674f2ad0b56950.jpg)

![5805edbaaaad6b6ac920ee577f41768b128519463257bb81f3882d20e47aaede.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/5805edbaaaad6b6ac920ee577f41768b128519463257bb81f3882d20e47aaede.jpg)

![61fe3c807638a32fa9240fe78c563a8fbe41c1e7ed55c1bfa8890ef2e9c8ad5a.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/61fe3c807638a32fa9240fe78c563a8fbe41c1e7ed55c1bfa8890ef2e9c8ad5a.jpg)

![7b55d87bf0fcf6d787a440d59bf4617e6d73f10f5b1bcc1b45736ad0a7a57911.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/7b55d87bf0fcf6d787a440d59bf4617e6d73f10f5b1bcc1b45736ad0a7a57911.jpg)

![8dbdcc99f827851f3918f2e26365b48508b9b491452578a5d79400e0b67add0c.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/8dbdcc99f827851f3918f2e26365b48508b9b491452578a5d79400e0b67add0c.jpg)

![953e9a304ff5c4e0679c5284d0f086d4716dca7135ffed84adf70e2e1e81c317.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/953e9a304ff5c4e0679c5284d0f086d4716dca7135ffed84adf70e2e1e81c317.jpg)

![9e7577155a5ee82b82ceb35b78af159df0f117f5dcb35ca82e3d8a47fe739b3c.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/9e7577155a5ee82b82ceb35b78af159df0f117f5dcb35ca82e3d8a47fe739b3c.jpg)

![9edf616b2e4e8bdff9edc073454be3f20b4ba48ebe0e9e21fc0940ce1cfde810.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/9edf616b2e4e8bdff9edc073454be3f20b4ba48ebe0e9e21fc0940ce1cfde810.jpg)

![a28dc69510d3b0ecf7484e0b1037def21d6fb9ce93d7892a970a94af2b7be0e6.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/a28dc69510d3b0ecf7484e0b1037def21d6fb9ce93d7892a970a94af2b7be0e6.jpg)

![aca2ba8fb0e2edfc18d43cebd920c84a40713c8a0df30fc4735fb50c16afab1c.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/aca2ba8fb0e2edfc18d43cebd920c84a40713c8a0df30fc4735fb50c16afab1c.jpg)

![e0a9ccd1468193cbc2822180c2aa77cad2088bc57f1af6b85abf13f1f26c347e.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/e0a9ccd1468193cbc2822180c2aa77cad2088bc57f1af6b85abf13f1f26c347e.jpg)

![ec2917e73c398b3b5c1a426fbad2c2f6e2f666dc692904746dc225efabc48dea.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/ec2917e73c398b3b5c1a426fbad2c2f6e2f666dc692904746dc225efabc48dea.jpg)

![ffc07b673692d355de9819cb635829edc5cfa8f72a19ae70435e1fcda04ac0fc.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/images/ffc07b673692d355de9819cb635829edc5cfa8f72a19ae70435e1fcda04ac0fc.jpg)

### Tables

![11fb0ce4c787e32197cac5e16d86f8f338bbcb531edac5537735f5ee5fe14d33.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/11fb0ce4c787e32197cac5e16d86f8f338bbcb531edac5537735f5ee5fe14d33.jpg)

![294822bf5ce5126f7bade3223b9423f779bac8feb9cc8b0dcdc61b732bc4c76d.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/294822bf5ce5126f7bade3223b9423f779bac8feb9cc8b0dcdc61b732bc4c76d.jpg)

![43a5fe33648a640e501aa9af33f25c95fadfc9072c23a12a4f36337ff39c009a.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/43a5fe33648a640e501aa9af33f25c95fadfc9072c23a12a4f36337ff39c009a.jpg)

![580ab2966b0d29e244b765f433a2c251aa4de4002cfe830bb3c6e6fc2220320b.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/580ab2966b0d29e244b765f433a2c251aa4de4002cfe830bb3c6e6fc2220320b.jpg)

![6515a9e2536755132c14d5286071ab9229756acbe0afa17cca1a68f4b0b4fa61.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/6515a9e2536755132c14d5286071ab9229756acbe0afa17cca1a68f4b0b4fa61.jpg)

![7886eef0f62fb11dabdb9f66bb3a4148a5ba91c8f6a6db2d9abfa8c20601e029.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/7886eef0f62fb11dabdb9f66bb3a4148a5ba91c8f6a6db2d9abfa8c20601e029.jpg)

![866fbb716264ef780090d6440a75a370da3d214733d6cac082d6d837b0de3928.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/866fbb716264ef780090d6440a75a370da3d214733d6cac082d6d837b0de3928.jpg)

![b1a27e3caf803cfb5d75ce118cbac1149c948a9e9f4c5a80af69c70bc046207d.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/b1a27e3caf803cfb5d75ce118cbac1149c948a9e9f4c5a80af69c70bc046207d.jpg)

![b2830a7cf453f7798f072b79efa85d36bf275064107a62add9690152494a5835.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/b2830a7cf453f7798f072b79efa85d36bf275064107a62add9690152494a5835.jpg)

![bf062c1df294432ad292d80704409591f4a0bba73417a32a76813a3097ec562c.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/bf062c1df294432ad292d80704409591f4a0bba73417a32a76813a3097ec562c.jpg)

![d060d62985b49cc4b5056d6e8dd5280b388bf5f917f8cc8591c3a25ba0c6e0a7.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/d060d62985b49cc4b5056d6e8dd5280b388bf5f917f8cc8591c3a25ba0c6e0a7.jpg)

![f823cecdd64b30f307b47aa3f29a15b7f42477412c50d07c2789dd77cad88bda.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/f823cecdd64b30f307b47aa3f29a15b7f42477412c50d07c2789dd77cad88bda.jpg)

![fb0d2318200ef0ba0f6228fcf63d269628d0ed444ae6fe8d8a509b896e837de9.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/fb0d2318200ef0ba0f6228fcf63d269628d0ed444ae6fe8d8a509b896e837de9.jpg)

![fe4713fc8843df663c21664af95c7f9445a7ccc6c5a0d32abfe624300424df85.jpg](../nips_results/232_VoxDet_%20Rethinking%203D%20Semantic%20Scene%20Completion%20as%20Dense%20Object%20Detection/tables/fe4713fc8843df663c21664af95c7f9445a7ccc6c5a0d32abfe624300424df85.jpg)

## ModHiFi: Identifying High Fidelity predictive components for Model Modification


### Images

![017d735a4000f4de18b80fd087f3f625d92652ea83e2eff8392a22be5dcff6ef.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/017d735a4000f4de18b80fd087f3f625d92652ea83e2eff8392a22be5dcff6ef.jpg)

![15f9aa9c264de524222415ef8eb549b80b9c3bcfba20b9518cc4bcdf5d1c1cc3.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/15f9aa9c264de524222415ef8eb549b80b9c3bcfba20b9518cc4bcdf5d1c1cc3.jpg)

![1880a1395ce3341479e02f40750abb43fb32465a38a18d7dd5bb6853261b037e.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/1880a1395ce3341479e02f40750abb43fb32465a38a18d7dd5bb6853261b037e.jpg)

![38e433fab2c3c298874e562bb3eb77e83add5420312d645fa95fb1663dd2dde9.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/38e433fab2c3c298874e562bb3eb77e83add5420312d645fa95fb1663dd2dde9.jpg)

![41dd69a9e1086a0e3e5f2ee2eadbb5a617a1ba4b579376e8e131645afe9ad1fc.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/41dd69a9e1086a0e3e5f2ee2eadbb5a617a1ba4b579376e8e131645afe9ad1fc.jpg)

![481b927c6301eb286b984e5929eeb8728a4394412515e122742739ab1ee7cf31.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/481b927c6301eb286b984e5929eeb8728a4394412515e122742739ab1ee7cf31.jpg)

![4d2b9dcd891f6ed97a7d288eec1689fc7453e65a059cf78ff2291574d9b76f39.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/4d2b9dcd891f6ed97a7d288eec1689fc7453e65a059cf78ff2291574d9b76f39.jpg)

![4fe5ec8b258546c85ee79b56ca0b94a1fc885f1a518cf7a2799fa2ea2e5a6c01.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/4fe5ec8b258546c85ee79b56ca0b94a1fc885f1a518cf7a2799fa2ea2e5a6c01.jpg)

![57985655a764668863f9b143e0fa4e94228caa89bdd38a1e64dce3dfd4eb4bb1.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/57985655a764668863f9b143e0fa4e94228caa89bdd38a1e64dce3dfd4eb4bb1.jpg)

![5aa63b90aca7ff0619d3e52c5a789fc002ea91c3616145204a05759c0690bfbc.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/5aa63b90aca7ff0619d3e52c5a789fc002ea91c3616145204a05759c0690bfbc.jpg)

![7e85c4009f6115a9c8f755309a9badcd34bd93d1ad3591b32c156d077ae3d56a.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/7e85c4009f6115a9c8f755309a9badcd34bd93d1ad3591b32c156d077ae3d56a.jpg)

![8d0a492c509f7c5883adb5a77ee8d911e68578f512bbf6ef2cd825ad67df1b05.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/8d0a492c509f7c5883adb5a77ee8d911e68578f512bbf6ef2cd825ad67df1b05.jpg)

![bc508f38b204d04a931b92de30288eac5a535ea070332b50ec577162084d95b8.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/bc508f38b204d04a931b92de30288eac5a535ea070332b50ec577162084d95b8.jpg)

![ce1448fc8a851267568587e1456c5797c24f15189c1aab082879616c13b9e3f9.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/ce1448fc8a851267568587e1456c5797c24f15189c1aab082879616c13b9e3f9.jpg)

![f41d00dc800348232c41fadf1be24cf99b8c92ef57c49a549e5370782b985e22.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/images/f41d00dc800348232c41fadf1be24cf99b8c92ef57c49a549e5370782b985e22.jpg)

### Tables

![0712d4c1eeef46e14f0ee53b9c11ca2b1f5f71f0c71cb9f9dc3df84babac0660.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/0712d4c1eeef46e14f0ee53b9c11ca2b1f5f71f0c71cb9f9dc3df84babac0660.jpg)

![1e982a450ba1c58c281417c9020af1d8cdbfb289a15bbbf8d9a4a0bcc13d9acf.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/1e982a450ba1c58c281417c9020af1d8cdbfb289a15bbbf8d9a4a0bcc13d9acf.jpg)

![2c5778535cb3396aca11c989cd7ace73b629e7cc1ecc86fa7e7a51b28e6d5ac4.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/2c5778535cb3396aca11c989cd7ace73b629e7cc1ecc86fa7e7a51b28e6d5ac4.jpg)

![3802a84610c68585a3c08e9012022681b64c152488504936b422025b93c3473f.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/3802a84610c68585a3c08e9012022681b64c152488504936b422025b93c3473f.jpg)

![3e96ced1070dd025642989789a913323c73f036c4f75a4ac0175ebccf2c6009a.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/3e96ced1070dd025642989789a913323c73f036c4f75a4ac0175ebccf2c6009a.jpg)

![48f287e841e4e7394c9c1b01f815b7ca18a1aca6af1e1761e6cc6231d37117a6.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/48f287e841e4e7394c9c1b01f815b7ca18a1aca6af1e1761e6cc6231d37117a6.jpg)

![4dcd5e7eaf33cc5c593b4d11d7eee4f2630ff49766dec3f19e054687eecc34d7.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/4dcd5e7eaf33cc5c593b4d11d7eee4f2630ff49766dec3f19e054687eecc34d7.jpg)

![7db1d17f4353e11c1349801f61c7574704faf4d62f8554e6a24103057bd44eef.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/7db1d17f4353e11c1349801f61c7574704faf4d62f8554e6a24103057bd44eef.jpg)

![84532917dc4c02b74408bc1c2f505efc57bdd897fa450e0a41776593e556854e.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/84532917dc4c02b74408bc1c2f505efc57bdd897fa450e0a41776593e556854e.jpg)

![9a3027f667cbde509485bb16a610c1256654b39f6ea4a045fa198cb184ae979a.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/9a3027f667cbde509485bb16a610c1256654b39f6ea4a045fa198cb184ae979a.jpg)

![eadf78774fb95196c9cd11de886f9d0f496eaa95742074eabe31bfa516f7853b.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/eadf78774fb95196c9cd11de886f9d0f496eaa95742074eabe31bfa516f7853b.jpg)

![eca0e63e93d764a92d3b774dab24a0effbe26da4da10deda701b1ff8b1fdb75d.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/eca0e63e93d764a92d3b774dab24a0effbe26da4da10deda701b1ff8b1fdb75d.jpg)

![f9ff367490f781d01f88c09bcc2a8b5ba99d1cd6b3bd5313514f05d61b682016.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/f9ff367490f781d01f88c09bcc2a8b5ba99d1cd6b3bd5313514f05d61b682016.jpg)

![fd646e27c6dee82e4821b45d3d16d65686b6ae8db58df262edb86eadc3547e7e.jpg](../nips_results/233_ModHiFi_%20Identifying%20High%20Fidelity%20predictive%20components%20for%20Model%20Modification/tables/fd646e27c6dee82e4821b45d3d16d65686b6ae8db58df262edb86eadc3547e7e.jpg)

## Discrete Spatial Diffusion: Intensity-Preserving Diffusion Modeling


### Images

![07284994c760a2325af630238c9b7522d996e152cf43ddd43306f41f09afee5a.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/07284994c760a2325af630238c9b7522d996e152cf43ddd43306f41f09afee5a.jpg)

![11f9ae8d4165eebe8da47e6e6fab07bf18060d9b2f959f9016a53ac911665c50.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/11f9ae8d4165eebe8da47e6e6fab07bf18060d9b2f959f9016a53ac911665c50.jpg)

![1687142d7705f1055cd6097b87cb6f8ab3a20dac0922e43f160681c27b4dc359.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/1687142d7705f1055cd6097b87cb6f8ab3a20dac0922e43f160681c27b4dc359.jpg)

![2b1dc98afc4bb8b335546c4f322d27ad9ea0747a0864db12b699f0c9fff699fb.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/2b1dc98afc4bb8b335546c4f322d27ad9ea0747a0864db12b699f0c9fff699fb.jpg)

![2eb6737d3d4bb958c85e5ee0e4b70651522de5b696a53a1228428b5ba9c2605b.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/2eb6737d3d4bb958c85e5ee0e4b70651522de5b696a53a1228428b5ba9c2605b.jpg)

![3ef996aa55d951b6125c0e1bb1df5023fec7d0296c52bcdb841cd2d4f1a8eab9.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/3ef996aa55d951b6125c0e1bb1df5023fec7d0296c52bcdb841cd2d4f1a8eab9.jpg)

![457176f372ec246c8680896cf98850fa7b273b151204451e86e46f7e4db8dd26.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/457176f372ec246c8680896cf98850fa7b273b151204451e86e46f7e4db8dd26.jpg)

![64a91f1dfa578e522372a26e915e02388048c31a11a4114a97d3a98d139dbc22.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/64a91f1dfa578e522372a26e915e02388048c31a11a4114a97d3a98d139dbc22.jpg)

![68bfe81f1cd69df1b0a8eaab6d766bbe3fdb4d2074f1e63bb3e7800d75b0d7f7.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/68bfe81f1cd69df1b0a8eaab6d766bbe3fdb4d2074f1e63bb3e7800d75b0d7f7.jpg)

![6cc65bcead3dda8b9ba3305693525c49b9f5268a0a67c8d9d7cc0f90c7d29988.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/6cc65bcead3dda8b9ba3305693525c49b9f5268a0a67c8d9d7cc0f90c7d29988.jpg)

![735886611c9e334f6dc03867213eeab49b6526a2513cccff59654efe9dcbabe3.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/735886611c9e334f6dc03867213eeab49b6526a2513cccff59654efe9dcbabe3.jpg)

![7d12602b65744cf8a397cbcb33366a097bb42c5b9d8cec20e91023d87d5e60ca.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/7d12602b65744cf8a397cbcb33366a097bb42c5b9d8cec20e91023d87d5e60ca.jpg)

![86785eb9fb3453f4ae8d995076e0474a810b647fb876ece39a65843a4f589a85.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/86785eb9fb3453f4ae8d995076e0474a810b647fb876ece39a65843a4f589a85.jpg)

![b4d5d5deb173804342f63ce38465c0234b90e90515d3ab53c3f507a9e5fc2cc3.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/b4d5d5deb173804342f63ce38465c0234b90e90515d3ab53c3f507a9e5fc2cc3.jpg)

![bb88b95c126b8d19228a024355f6879fe96e502cb4cb4b9b44e592acd047d24a.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/bb88b95c126b8d19228a024355f6879fe96e502cb4cb4b9b44e592acd047d24a.jpg)

![c4b6f2a4a07e762877e608f75dc41d9eaf5fd3b668fed460d5f1876a8517e770.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/c4b6f2a4a07e762877e608f75dc41d9eaf5fd3b668fed460d5f1876a8517e770.jpg)

![ce8c9b9d85cad92684b2c4bb257b8c15387e56b5a6f6048e5a704e008c202baf.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/ce8c9b9d85cad92684b2c4bb257b8c15387e56b5a6f6048e5a704e008c202baf.jpg)

![d98ef0e2d840d9a4bf860aba0694d3da5eba853891e2483d91667bc3b19aa8a2.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/d98ef0e2d840d9a4bf860aba0694d3da5eba853891e2483d91667bc3b19aa8a2.jpg)

![e10fa05e211b0464bf682d28eb1d78134a5c5a974a9fe18ff4a93a5a2af6e5d5.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/e10fa05e211b0464bf682d28eb1d78134a5c5a974a9fe18ff4a93a5a2af6e5d5.jpg)

![f79170cd33a82c9d51903089c101169c67851092785eda9fc70f1060f15dfb95.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/f79170cd33a82c9d51903089c101169c67851092785eda9fc70f1060f15dfb95.jpg)

![f7e0532c13ccfe74edf526bd770ee1d7537a0b048b739f7243a3d5dcb15e6426.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/images/f7e0532c13ccfe74edf526bd770ee1d7537a0b048b739f7243a3d5dcb15e6426.jpg)

### Tables

![6a9da969fa0ad969d7f47c945b3a14268ae42500d17083b092a49dcbf953c9b2.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/tables/6a9da969fa0ad969d7f47c945b3a14268ae42500d17083b092a49dcbf953c9b2.jpg)

![8b02e48f0f3f25f6ee1e5193f50fb835e63c1e37a945f927f20a135b53e7c86a.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/tables/8b02e48f0f3f25f6ee1e5193f50fb835e63c1e37a945f927f20a135b53e7c86a.jpg)

![a0711f4f2c03d55021a4cb7bbdb18dc9c4a8a6ddd0ca4bb7c5ca3805f7f93e5b.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/tables/a0711f4f2c03d55021a4cb7bbdb18dc9c4a8a6ddd0ca4bb7c5ca3805f7f93e5b.jpg)

![ce19d7a1085b142dd378cd6671123cadee331c6aed4863ac0a17a5a0b193ce04.jpg](../nips_results/234_Discrete%20Spatial%20Diffusion_%20Intensity-Preserving%20Diffusion%20Modeling/tables/ce19d7a1085b142dd378cd6671123cadee331c6aed4863ac0a17a5a0b193ce04.jpg)

## FP4 All the Way: Fully Quantized Training of Large Language Models


### Images

![306a0b8e260a664f375691e8a8beffd5c9989ea3052414ff26632af777756856.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/images/306a0b8e260a664f375691e8a8beffd5c9989ea3052414ff26632af777756856.jpg)

![3f1fb72af2533afeecf491f194c44f4be07f360b4956bce93600a0064264c6f5.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/images/3f1fb72af2533afeecf491f194c44f4be07f360b4956bce93600a0064264c6f5.jpg)

![4f039bdabfc176dd90d6a2bcb80fcd8b56d0833961b590b01e118dda237b6878.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/images/4f039bdabfc176dd90d6a2bcb80fcd8b56d0833961b590b01e118dda237b6878.jpg)

![8613d267b0411c29dc41861c9ab49e2d416b3c2a43632862eafcef5aa74b8c72.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/images/8613d267b0411c29dc41861c9ab49e2d416b3c2a43632862eafcef5aa74b8c72.jpg)

![8fbcf465e3a52977c5f0602e090196e49fad765adc0c4c00ea200bb686f752e9.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/images/8fbcf465e3a52977c5f0602e090196e49fad765adc0c4c00ea200bb686f752e9.jpg)

![aeff36aae73898dc029ae028e87d04f89945cb796ebf5bfde3029db2aebd1106.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/images/aeff36aae73898dc029ae028e87d04f89945cb796ebf5bfde3029db2aebd1106.jpg)

![d639da1cdf675995d9bcfd1761cf184eaeaba1e77e6129184bfc16e764359d29.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/images/d639da1cdf675995d9bcfd1761cf184eaeaba1e77e6129184bfc16e764359d29.jpg)

### Tables

![0bb365109d8175fd308ca0e60e76864ab97f9c290f60f285ad0eee9b558f288c.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/tables/0bb365109d8175fd308ca0e60e76864ab97f9c290f60f285ad0eee9b558f288c.jpg)

![622914befcae80e9ea4003f6ed6d803aa2230b42e996605e2b285cfcd843173e.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/tables/622914befcae80e9ea4003f6ed6d803aa2230b42e996605e2b285cfcd843173e.jpg)

![80251cd7ed0fb1f39a970b681410e53923143fa2e7666d57185610e554295e21.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/tables/80251cd7ed0fb1f39a970b681410e53923143fa2e7666d57185610e554295e21.jpg)

![8b36231c00861332360eb42c3edb2cd75d9f24f102cccd5cd1672e7decf7c924.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/tables/8b36231c00861332360eb42c3edb2cd75d9f24f102cccd5cd1672e7decf7c924.jpg)

![fe51a0ed7d5d1901d4ea99a81a0be6e306f4e304af486c11da3e9dbf4646c4cb.jpg](../nips_results/235_FP4%20All%20the%20Way_%20Fully%20Quantized%20Training%20of%20Large%20Language%20Models/tables/fe51a0ed7d5d1901d4ea99a81a0be6e306f4e304af486c11da3e9dbf4646c4cb.jpg)

## Object-centric 3D Motion Field for Robot Learning from Human Videos


### Images

![013252de069badb6c140790de49d530870d6ab576ff493276523dd8f3a9244bc.jpg](../nips_results/236_Object-centric%203D%20Motion%20Field%20for%20Robot%20Learning%20from%20Human%20Videos/images/013252de069badb6c140790de49d530870d6ab576ff493276523dd8f3a9244bc.jpg)

![11675be2a2bd28e6da609ae130d39c6e6a1894f7615c9735f5390827418ca55c.jpg](../nips_results/236_Object-centric%203D%20Motion%20Field%20for%20Robot%20Learning%20from%20Human%20Videos/images/11675be2a2bd28e6da609ae130d39c6e6a1894f7615c9735f5390827418ca55c.jpg)

![1e2790c7ffc286096917c561fd16961c0952e8901cef6549214edd2e56ea3707.jpg](../nips_results/236_Object-centric%203D%20Motion%20Field%20for%20Robot%20Learning%20from%20Human%20Videos/images/1e2790c7ffc286096917c561fd16961c0952e8901cef6549214edd2e56ea3707.jpg)

![6bcfc1e2015821aca8e8dd5ae3bf70d624e60158b44a51079c457fe5babc03f3.jpg](../nips_results/236_Object-centric%203D%20Motion%20Field%20for%20Robot%20Learning%20from%20Human%20Videos/images/6bcfc1e2015821aca8e8dd5ae3bf70d624e60158b44a51079c457fe5babc03f3.jpg)

![a2f774a107b5b04fa3cc04e899fedbca2ff6d06e2f7d39f5721e1666c9e79b16.jpg](../nips_results/236_Object-centric%203D%20Motion%20Field%20for%20Robot%20Learning%20from%20Human%20Videos/images/a2f774a107b5b04fa3cc04e899fedbca2ff6d06e2f7d39f5721e1666c9e79b16.jpg)

![be3e6e498eb948f772d943ffd0bd90ff65c38223cb575d5378f9676652797685.jpg](../nips_results/236_Object-centric%203D%20Motion%20Field%20for%20Robot%20Learning%20from%20Human%20Videos/images/be3e6e498eb948f772d943ffd0bd90ff65c38223cb575d5378f9676652797685.jpg)

![c49dd1b92f44cb86d2bf205a906d398a4d20014b2e5fee71e15f3f1234e32d39.jpg](../nips_results/236_Object-centric%203D%20Motion%20Field%20for%20Robot%20Learning%20from%20Human%20Videos/images/c49dd1b92f44cb86d2bf205a906d398a4d20014b2e5fee71e15f3f1234e32d39.jpg)

![f9ac3d8d6800a5afc66a3713f18013d620c32baa2a0dc9685d97f5c80c193e4b.jpg](../nips_results/236_Object-centric%203D%20Motion%20Field%20for%20Robot%20Learning%20from%20Human%20Videos/images/f9ac3d8d6800a5afc66a3713f18013d620c32baa2a0dc9685d97f5c80c193e4b.jpg)

### Tables

![2fcf2e06dadf476db8cf03c5f419f7d6a61461ac79d432501644e6b6f1a32ac8.jpg](../nips_results/236_Object-centric%203D%20Motion%20Field%20for%20Robot%20Learning%20from%20Human%20Videos/tables/2fcf2e06dadf476db8cf03c5f419f7d6a61461ac79d432501644e6b6f1a32ac8.jpg)

![8e7fe4d0c3ab167b1fd91e7c4f34cc421f8de94962a0d0c5bc51006e9a8fb8f4.jpg](../nips_results/236_Object-centric%203D%20Motion%20Field%20for%20Robot%20Learning%20from%20Human%20Videos/tables/8e7fe4d0c3ab167b1fd91e7c4f34cc421f8de94962a0d0c5bc51006e9a8fb8f4.jpg)

## SoFar: Language-Grounded Orientation Bridges Spatial Reasoning and Object Manipulation


### Images

![01ca3fc6f4c00251c1263fe2ec50e066318371da98c0d643248ecbaa8542a8fc.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/01ca3fc6f4c00251c1263fe2ec50e066318371da98c0d643248ecbaa8542a8fc.jpg)

![022e0555b2ae742e15db7939499fdc230372967fcd98ef2995e39f04f481cc90.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/022e0555b2ae742e15db7939499fdc230372967fcd98ef2995e39f04f481cc90.jpg)

![023b118463580c0e506a30a0eb4fc4851641afdfe3be96ff737b62f37459ebc5.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/023b118463580c0e506a30a0eb4fc4851641afdfe3be96ff737b62f37459ebc5.jpg)

![04c0965a7c771b0eb9ed132dbd3c63f3ddc2500da217565e3154b4d404915d3c.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/04c0965a7c771b0eb9ed132dbd3c63f3ddc2500da217565e3154b4d404915d3c.jpg)

![051a2fbe7f0f52cefe094a52523df9a8c7553c58aba6f9ada0d2735fb79e91c4.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/051a2fbe7f0f52cefe094a52523df9a8c7553c58aba6f9ada0d2735fb79e91c4.jpg)

![07ec6702240554364383f7863f7416d42b29ee7dd073ea915f77e0ead487f6d4.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/07ec6702240554364383f7863f7416d42b29ee7dd073ea915f77e0ead487f6d4.jpg)

![149646c365e2a36cee9d21fa1812731f1524f075808f741e0b90dfb8b73decbd.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/149646c365e2a36cee9d21fa1812731f1524f075808f741e0b90dfb8b73decbd.jpg)

![162414b4b6d238dceea9575887f35b714061e8648ab98b45197e43de2654a2a3.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/162414b4b6d238dceea9575887f35b714061e8648ab98b45197e43de2654a2a3.jpg)

![296c1019898495c61b75d5c9b984eb959441050244eeac23a6e49c70cc8eaf19.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/296c1019898495c61b75d5c9b984eb959441050244eeac23a6e49c70cc8eaf19.jpg)

![2aa8131a945f48ccb6b08e75d9e26ecd0947480384430dd8425401edfca1b1be.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/2aa8131a945f48ccb6b08e75d9e26ecd0947480384430dd8425401edfca1b1be.jpg)

![2cd238a09ace192ac17de3f6155a961493e9c0800df27439c7bdb005db9b8e0e.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/2cd238a09ace192ac17de3f6155a961493e9c0800df27439c7bdb005db9b8e0e.jpg)

![2f3bea787992654028968d5e3b6c8c215111156b92416740a127d5874689085d.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/2f3bea787992654028968d5e3b6c8c215111156b92416740a127d5874689085d.jpg)

![4630d9b04e7fc70466a641833bac519cc1ee7a9539a7749e976199ebb4d03409.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/4630d9b04e7fc70466a641833bac519cc1ee7a9539a7749e976199ebb4d03409.jpg)

![4e1c381c41bd4f4397371e0abf72a6cfc2d06f7dcfd0b3578afafb80e5ce2e2e.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/4e1c381c41bd4f4397371e0abf72a6cfc2d06f7dcfd0b3578afafb80e5ce2e2e.jpg)

![522df919d1d627d4b613ce10d3702f9b628f8f2a4892418660d968926df85e62.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/522df919d1d627d4b613ce10d3702f9b628f8f2a4892418660d968926df85e62.jpg)

![527f0fce074f1a80b901511e237d90d022c131d1c7092a16e466b5cc5844e7a5.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/527f0fce074f1a80b901511e237d90d022c131d1c7092a16e466b5cc5844e7a5.jpg)

![53b4dadd3f47e8670ada515e71c4f28d935c8b7986b01b16d27afd88a0e2ddc0.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/53b4dadd3f47e8670ada515e71c4f28d935c8b7986b01b16d27afd88a0e2ddc0.jpg)

![6b33a7be1a873ad759f91516e7e3cb1b2410442002a7b91025fd0ea6f7c89816.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/6b33a7be1a873ad759f91516e7e3cb1b2410442002a7b91025fd0ea6f7c89816.jpg)

![720a5db89c038c36ad18184a891955628f5c85d063d864db35a39d9429e3da12.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/720a5db89c038c36ad18184a891955628f5c85d063d864db35a39d9429e3da12.jpg)

![72557b9520165378da260eb34d67d530ca8e8210ed919d2d7eb555b897b44249.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/72557b9520165378da260eb34d67d530ca8e8210ed919d2d7eb555b897b44249.jpg)

![80064b49845655b48bbf2f0b5352df03f10770eed612c9864ae0cc34986ed626.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/80064b49845655b48bbf2f0b5352df03f10770eed612c9864ae0cc34986ed626.jpg)

![83b5414fa5f6a36b05487388e672be050a822f54e610f19b403cd58a24fb2ee7.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/83b5414fa5f6a36b05487388e672be050a822f54e610f19b403cd58a24fb2ee7.jpg)

![893c773105401d26c22888250ccbb6c71bf94ea9bdd0a92f96a6fc514e9849da.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/893c773105401d26c22888250ccbb6c71bf94ea9bdd0a92f96a6fc514e9849da.jpg)

![aacdb185d35d5da32bb370a2fcf6991f5aecddf04582cb609bb726ec7c4ccd15.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/aacdb185d35d5da32bb370a2fcf6991f5aecddf04582cb609bb726ec7c4ccd15.jpg)

![b555ad09c15a0f83c5bf2f0f368ffc3b50f4508c06d0cd1f8dc294756036c430.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/b555ad09c15a0f83c5bf2f0f368ffc3b50f4508c06d0cd1f8dc294756036c430.jpg)

![b680b17064176528abffab8663cf6db20cf4c123e57aa4b8d4a44188f74cb88f.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/b680b17064176528abffab8663cf6db20cf4c123e57aa4b8d4a44188f74cb88f.jpg)

![bfd88c137471aeaf6f0374f7bd8bc4d25c7de5faac6012e264d90ae1d2ed33e5.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/bfd88c137471aeaf6f0374f7bd8bc4d25c7de5faac6012e264d90ae1d2ed33e5.jpg)

![c99bc321bc389ffc8f8ccca8699fd338a617c187503a74bb24f1d706abeda16e.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/c99bc321bc389ffc8f8ccca8699fd338a617c187503a74bb24f1d706abeda16e.jpg)

![d873b0bc6e3fa69975d5f99d557b626320dc950e108eeb8c1834ec1d1c2ec2a3.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/d873b0bc6e3fa69975d5f99d557b626320dc950e108eeb8c1834ec1d1c2ec2a3.jpg)

![d90f504e44d6111fe4cd409e544aa1da1198752c77a3381e4f7ee71e1e11a166.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/d90f504e44d6111fe4cd409e544aa1da1198752c77a3381e4f7ee71e1e11a166.jpg)

![de1ec450c7a8af0a54cb7818e0d29c84cdb251860dc75d0e5bbc76c3412930ff.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/de1ec450c7a8af0a54cb7818e0d29c84cdb251860dc75d0e5bbc76c3412930ff.jpg)

![e08f4b78067e9ad1cb53e29ac3a39266d05f2c629830b9a91649e7ef542aff37.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/e08f4b78067e9ad1cb53e29ac3a39266d05f2c629830b9a91649e7ef542aff37.jpg)

![f273f4648c50eab9f8879f31857aacdfa71900acec37bef95c949cca4af634ff.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/f273f4648c50eab9f8879f31857aacdfa71900acec37bef95c949cca4af634ff.jpg)

![f4bed1797b2cc0ecebffeec7c537b5aec405185fa30fcf46b5db15f9cae09c51.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/images/f4bed1797b2cc0ecebffeec7c537b5aec405185fa30fcf46b5db15f9cae09c51.jpg)

### Tables

![120372a50b0ec920f3007898109e7fcda04484621bc591f75d51856f1ae82d5c.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/120372a50b0ec920f3007898109e7fcda04484621bc591f75d51856f1ae82d5c.jpg)

![20fba8384dc44e9d02fbef752ae3df5f333d9cc51c22846c2c5f7f23a95a9a73.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/20fba8384dc44e9d02fbef752ae3df5f333d9cc51c22846c2c5f7f23a95a9a73.jpg)

![2387390ff865ad362136e6f8dcdf7a2de03d9d4dc7ce892f6f4d6c8c524a3c10.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/2387390ff865ad362136e6f8dcdf7a2de03d9d4dc7ce892f6f4d6c8c524a3c10.jpg)

![452d9a3a087e8c85aaaeca5940fa58dfedb9a87075296289a5249b59b55f8c9a.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/452d9a3a087e8c85aaaeca5940fa58dfedb9a87075296289a5249b59b55f8c9a.jpg)

![4fe4eca04c384e7b2a3127d673a497cc7a2adfece9cc9eb120c027d8afd420a2.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/4fe4eca04c384e7b2a3127d673a497cc7a2adfece9cc9eb120c027d8afd420a2.jpg)

![51d5c7392916f1a911b41b9aa27dc7b0e47fd0837022ccbf67eadf7b6fe3525c.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/51d5c7392916f1a911b41b9aa27dc7b0e47fd0837022ccbf67eadf7b6fe3525c.jpg)

![53fcd73b4be67f2247a9d297d4b7512ad66b17a0c6b7d209ef3565312a7e634b.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/53fcd73b4be67f2247a9d297d4b7512ad66b17a0c6b7d209ef3565312a7e634b.jpg)

![65da3005495c519c001d893abece74440e9bfb0bcb05716a4c66d4b4af1adc84.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/65da3005495c519c001d893abece74440e9bfb0bcb05716a4c66d4b4af1adc84.jpg)

![6e9aeaeeed3d6cdd1cb2d5f55d8e3e170ec20553b79e7e191edf85647db030de.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/6e9aeaeeed3d6cdd1cb2d5f55d8e3e170ec20553b79e7e191edf85647db030de.jpg)

![722704d9f7305083e1a1e1769ea60e655292bb6ba8fac8d37c96f5a32bf15d5a.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/722704d9f7305083e1a1e1769ea60e655292bb6ba8fac8d37c96f5a32bf15d5a.jpg)

![a37b972752497e64622b560a3f9bafa77d58614eda0445451f51688a36bfde51.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/a37b972752497e64622b560a3f9bafa77d58614eda0445451f51688a36bfde51.jpg)

![a3b009eaed4eaedc2eaa74d8de318dbf13a7e802cb027e71bf9f534d2f9ed2e0.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/a3b009eaed4eaedc2eaa74d8de318dbf13a7e802cb027e71bf9f534d2f9ed2e0.jpg)

![abb22ef3fda82805e23cf7cee317a1925f84a95d7b12912bfbdb72a7fc62e451.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/abb22ef3fda82805e23cf7cee317a1925f84a95d7b12912bfbdb72a7fc62e451.jpg)

![df33d78094baca3f8e49aca648c4d3545e75112f59544a62e421624b761becbb.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/df33d78094baca3f8e49aca648c4d3545e75112f59544a62e421624b761becbb.jpg)

![dfbf8d57efb2882a5ba3268fbb5be50c8d5bcae32617ee7f52e4f0c344af92fa.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/dfbf8d57efb2882a5ba3268fbb5be50c8d5bcae32617ee7f52e4f0c344af92fa.jpg)

![eacfb6f85d99c4e116a86597db8f78fbbe1d600f4cb4ba8db6d4621845e85549.jpg](../nips_results/237_SoFar_%20Language-Grounded%20Orientation%20Bridges%20Spatial%20Reasoning%20and%20Object%20Manipulation/tables/eacfb6f85d99c4e116a86597db8f78fbbe1d600f4cb4ba8db6d4621845e85549.jpg)

## Generating Informative Samples for Risk-Averse Fine-Tuning of Downstream Tasks


### Images

![3a9bb7925a592572dea94d3d64d80a5b9c565098a98f951c0441868e40d2995e.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/images/3a9bb7925a592572dea94d3d64d80a5b9c565098a98f951c0441868e40d2995e.jpg)

![96af486a33996b76ec1ecfe67a9d34b1a7a8e40c4c70a25e15d66de9d9dfe969.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/images/96af486a33996b76ec1ecfe67a9d34b1a7a8e40c4c70a25e15d66de9d9dfe969.jpg)

![9a071baaa28a94eda0a2b5eada9896642ead43ec574d8539d9745ee1f1421755.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/images/9a071baaa28a94eda0a2b5eada9896642ead43ec574d8539d9745ee1f1421755.jpg)

![c41cf7bc821e23cfee3604c101e647833991556fcd4c031449bb526347d2b820.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/images/c41cf7bc821e23cfee3604c101e647833991556fcd4c031449bb526347d2b820.jpg)

![d2f0b5bfe745ac323de7852cbbbf2d44177f15f779c8e606ece457e1a65489eb.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/images/d2f0b5bfe745ac323de7852cbbbf2d44177f15f779c8e606ece457e1a65489eb.jpg)

![dbde23d23e885be6774361f0ac6b90988c3e91817afe52fe925031f18bd4e37c.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/images/dbde23d23e885be6774361f0ac6b90988c3e91817afe52fe925031f18bd4e37c.jpg)

### Tables

![06782057737c2c1caa8687016153b7589a6d172c30ffc5e5d5f52c41a241ae85.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/tables/06782057737c2c1caa8687016153b7589a6d172c30ffc5e5d5f52c41a241ae85.jpg)

![091585629e85b7f42ef30ea9f76590ed6eacbf7193ac682d3f62f8e36f26126b.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/tables/091585629e85b7f42ef30ea9f76590ed6eacbf7193ac682d3f62f8e36f26126b.jpg)

![6765eeed8fe18ca457267ddf90f7a2d086d6366aec352bd7803e7f3e02160c8d.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/tables/6765eeed8fe18ca457267ddf90f7a2d086d6366aec352bd7803e7f3e02160c8d.jpg)

![77c5789d74375659aeccdb462223c759e5ee6cb0dc60f938d33d83334e812221.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/tables/77c5789d74375659aeccdb462223c759e5ee6cb0dc60f938d33d83334e812221.jpg)

![8821385d6405f17a0b2dc4ae062038c68c0a397aeab4d85b8a11266c61f015e8.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/tables/8821385d6405f17a0b2dc4ae062038c68c0a397aeab4d85b8a11266c61f015e8.jpg)

![d5321e9592570bd7b86b98ad90de24c2989106998e01c6443b27da3656c2d377.jpg](../nips_results/238_Generating%20Informative%20Samples%20for%20Risk-Averse%20Fine-Tuning%20of%20Downstream%20Tasks/tables/d5321e9592570bd7b86b98ad90de24c2989106998e01c6443b27da3656c2d377.jpg)

## Purifying Shampoo: Investigating Shampoo's Heuristics by Decomposing its Preconditioner


### Images

![13fb3b09071800a73c8e518bcafcf386f18a92b9a52ca1f4ee7cd3e72921a616.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/images/13fb3b09071800a73c8e518bcafcf386f18a92b9a52ca1f4ee7cd3e72921a616.jpg)

![1c5e7ed93eaaa93f6999af95177515f92e86311948ccdbbb3551e2345ec0206a.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/images/1c5e7ed93eaaa93f6999af95177515f92e86311948ccdbbb3551e2345ec0206a.jpg)

![2eb10962160b78017130e7df4411d8c892a9989f49b8769564c28f8b52fa77ce.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/images/2eb10962160b78017130e7df4411d8c892a9989f49b8769564c28f8b52fa77ce.jpg)

![6926170a5384678c0bc93069e01ee45291f7e15978a7ec9afba35c2e8d986e8b.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/images/6926170a5384678c0bc93069e01ee45291f7e15978a7ec9afba35c2e8d986e8b.jpg)

![71bde31ebb1ae7bf920a0eb1cfab12c1974f8cd31f6d90c05e968ccb5422af5f.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/images/71bde31ebb1ae7bf920a0eb1cfab12c1974f8cd31f6d90c05e968ccb5422af5f.jpg)

![79c0375dac22b1df669cb6ef1d501e1c29f4a902ab6fd18e5267149ef7e387bc.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/images/79c0375dac22b1df669cb6ef1d501e1c29f4a902ab6fd18e5267149ef7e387bc.jpg)

![c5c72ebb3137a44b70fbcfc84d5e4fc3b564bf1ea333dad0367b577a13c4004d.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/images/c5c72ebb3137a44b70fbcfc84d5e4fc3b564bf1ea333dad0367b577a13c4004d.jpg)

![d1f999880024c9d0d9566b89e129819bdf1daafbc48e27ca451a58c44bc545bb.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/images/d1f999880024c9d0d9566b89e129819bdf1daafbc48e27ca451a58c44bc545bb.jpg)

![e1274fdbc75c16aee8109dec55f93007b4712e172ba669c35bfd9f18e4ac48f5.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/images/e1274fdbc75c16aee8109dec55f93007b4712e172ba669c35bfd9f18e4ac48f5.jpg)

![f11de3f312cf0d79b7ae28994dbcd316164eb20eafae941f8c31d79f06759425.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/images/f11de3f312cf0d79b7ae28994dbcd316164eb20eafae941f8c31d79f06759425.jpg)

![f17566b8c83fbce9109be52808c50bdcd5ba0a9c4b2d01ac2e296cda499d5690.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/images/f17566b8c83fbce9109be52808c50bdcd5ba0a9c4b2d01ac2e296cda499d5690.jpg)

### Tables

![80d03d610eb9f9e1045037f15e726e49cb17bfabb0eb427a5258a774c10dd6a6.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/tables/80d03d610eb9f9e1045037f15e726e49cb17bfabb0eb427a5258a774c10dd6a6.jpg)

![9203feac0d12b3855e9499d7c4159b589918031778b5feef9c6e2eace83dffdd.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/tables/9203feac0d12b3855e9499d7c4159b589918031778b5feef9c6e2eace83dffdd.jpg)

![a45d9ab4c66c6eeec8dd0493aa9f8b688bdd1160333f47041ae18dde2b7c8ba6.jpg](../nips_results/239_Purifying%20Shampoo_%20Investigating%20Shampoo%27s%20Heuristics%20by%20Decomposing%20its%20Preconditioner/tables/a45d9ab4c66c6eeec8dd0493aa9f8b688bdd1160333f47041ae18dde2b7c8ba6.jpg)

## Improving LLM General Preference Alignment via Optimistic Online Mirror Descent


### Images

![26b5ffb54e3b5c6ff329a62372126ed9162d17ee39c18db8ff8e1e5c30f356f7.jpg](../nips_results/240_Improving%20LLM%20General%20Preference%20Alignment%20via%20Optimistic%20Online%20Mirror%20Descent/images/26b5ffb54e3b5c6ff329a62372126ed9162d17ee39c18db8ff8e1e5c30f356f7.jpg)

### Tables

![6c61e6edbdbd0a9337b70d41d108b9b0ff432706adabcc282333d2e460656bd6.jpg](../nips_results/240_Improving%20LLM%20General%20Preference%20Alignment%20via%20Optimistic%20Online%20Mirror%20Descent/tables/6c61e6edbdbd0a9337b70d41d108b9b0ff432706adabcc282333d2e460656bd6.jpg)

![81e72ea3520c2b83302f1eb4fba151ce706ce94652e9f3f92b0d35ac00724bc0.jpg](../nips_results/240_Improving%20LLM%20General%20Preference%20Alignment%20via%20Optimistic%20Online%20Mirror%20Descent/tables/81e72ea3520c2b83302f1eb4fba151ce706ce94652e9f3f92b0d35ac00724bc0.jpg)

## 3D Equivariant Visuomotor Policy Learning via Spherical Projection


### Images

![06f86e2f6679a1fa549148acf1af35e3632356d82d107982346fdbeeee7fe593.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/06f86e2f6679a1fa549148acf1af35e3632356d82d107982346fdbeeee7fe593.jpg)

![2857dc21c4b5c9af4a1f6743eafa60560ce1fa225ec43fb36b14a6bc612689c3.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/2857dc21c4b5c9af4a1f6743eafa60560ce1fa225ec43fb36b14a6bc612689c3.jpg)

![352abb32b8bf2be3c2a1c8464198a7e6ae9d1091d1291affc28ec527f875d8f7.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/352abb32b8bf2be3c2a1c8464198a7e6ae9d1091d1291affc28ec527f875d8f7.jpg)

![45d231ecd38f1f41c048aaa6c76d8779f89732738356938ad49fd0b0cce8888f.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/45d231ecd38f1f41c048aaa6c76d8779f89732738356938ad49fd0b0cce8888f.jpg)

![58cd043b6275206365ee9e0f69459540103cd04af79f52b9b66a4254d678f022.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/58cd043b6275206365ee9e0f69459540103cd04af79f52b9b66a4254d678f022.jpg)

![6602d5d729d24c52a30ba2c1f71d7e4411b2dbaa187b8b7a08812da0528c5284.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/6602d5d729d24c52a30ba2c1f71d7e4411b2dbaa187b8b7a08812da0528c5284.jpg)

![7c58467483120b36130d41f34430a2b3ff0afedd6bedbf1beeeb07e24d170b8a.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/7c58467483120b36130d41f34430a2b3ff0afedd6bedbf1beeeb07e24d170b8a.jpg)

![8ed068432d843f32c0654027472f4cd440bc21430b89a1d69454671df6ad4f94.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/8ed068432d843f32c0654027472f4cd440bc21430b89a1d69454671df6ad4f94.jpg)

![a4e51889c0b6f1f00eb4678e3d49f2bac6a82ef20234308f9dd5f584a06b66e4.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/a4e51889c0b6f1f00eb4678e3d49f2bac6a82ef20234308f9dd5f584a06b66e4.jpg)

![c5ce11ff6c717e53a6e922b6e73939d4dc70263a56e6a6449f03568a45f57d39.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/c5ce11ff6c717e53a6e922b6e73939d4dc70263a56e6a6449f03568a45f57d39.jpg)

![c66601e12edaefe7d0f121bc0dad700c5971a5eb1431877716240d2a28161a40.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/c66601e12edaefe7d0f121bc0dad700c5971a5eb1431877716240d2a28161a40.jpg)

![c6b68d868fff74d04d241d12edab2720415caa92a97e2f1721b96e0d7fa59ea0.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/c6b68d868fff74d04d241d12edab2720415caa92a97e2f1721b96e0d7fa59ea0.jpg)

![e98ba4462bad5a364307578e0f99b5ab24fd91204baa006c8a6467f68ba8e4a9.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/images/e98ba4462bad5a364307578e0f99b5ab24fd91204baa006c8a6467f68ba8e4a9.jpg)

### Tables

![90333fb5bc0e98bff8a54dd164fb462c5f841ddf9e0a05d83be9ea64791e24d0.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/tables/90333fb5bc0e98bff8a54dd164fb462c5f841ddf9e0a05d83be9ea64791e24d0.jpg)

![917360527df3caaa3ac3ce1431fff4d6f3f802a91429fc5ab3125dced78ed753.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/tables/917360527df3caaa3ac3ce1431fff4d6f3f802a91429fc5ab3125dced78ed753.jpg)

![936071e0b636daa1ff479931773549b2fde494a62b8212a9e3f894973a0b75de.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/tables/936071e0b636daa1ff479931773549b2fde494a62b8212a9e3f894973a0b75de.jpg)

![ac804dbbd88b0a3739826759661a114355b0fa9f9cbfd0f24d49d39662a30fec.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/tables/ac804dbbd88b0a3739826759661a114355b0fa9f9cbfd0f24d49d39662a30fec.jpg)

![b19eb3d234fc1515fe08926148583c57de152cc7369f82ffffacd86837947550.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/tables/b19eb3d234fc1515fe08926148583c57de152cc7369f82ffffacd86837947550.jpg)

![c1738e6d03b11734c38083b5911fc02bfd6cc4f18f347b57114bf783e7f62736.jpg](../nips_results/241_3D%20Equivariant%20Visuomotor%20Policy%20Learning%20via%20Spherical%20Projection/tables/c1738e6d03b11734c38083b5911fc02bfd6cc4f18f347b57114bf783e7f62736.jpg)

## Not All Data are Good Labels: On the Self-supervised Labeling for Time Series Forecasting


### Images

![0ee31b3520f99953dde8fa4d48ddbdb3d6318523062c89b2ec35757c47922906.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/0ee31b3520f99953dde8fa4d48ddbdb3d6318523062c89b2ec35757c47922906.jpg)

![1a826f3447c836dbcf35a3a1af1b656a15f5eb74bae8b503f6d341def3ba66b0.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/1a826f3447c836dbcf35a3a1af1b656a15f5eb74bae8b503f6d341def3ba66b0.jpg)

![1aae1ab3b442fe4ab8eb8a8e8a3ee773050529d8b9af93f129a9d4c2d124ce86.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/1aae1ab3b442fe4ab8eb8a8e8a3ee773050529d8b9af93f129a9d4c2d124ce86.jpg)

![28decd0e444d26c31fb4d8c4bf984e7eaa681e917bf17294e34d6cae42067796.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/28decd0e444d26c31fb4d8c4bf984e7eaa681e917bf17294e34d6cae42067796.jpg)

![2ab886353a7fd6f8af860d52abf4aabca6d661c6bf49ab91d7ae8d3eb7eb9c25.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/2ab886353a7fd6f8af860d52abf4aabca6d661c6bf49ab91d7ae8d3eb7eb9c25.jpg)

![391f8cb68eb5b1de6e85a73f7006671a24746b57aa88e87cb5a777f92f863346.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/391f8cb68eb5b1de6e85a73f7006671a24746b57aa88e87cb5a777f92f863346.jpg)

![5508a8367099a58eac5627edd21e23c65407545024b09379d7ae153201c85f82.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/5508a8367099a58eac5627edd21e23c65407545024b09379d7ae153201c85f82.jpg)

![68b3c60728d3eae9fc85cab2521e88f4b4877b8771e37bacc1b3eb2a14d755ac.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/68b3c60728d3eae9fc85cab2521e88f4b4877b8771e37bacc1b3eb2a14d755ac.jpg)

![6fb6000ed93a87acdf90f8f4e5d3bdff131730fe1d5b446599b01585d222e998.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/6fb6000ed93a87acdf90f8f4e5d3bdff131730fe1d5b446599b01585d222e998.jpg)

![7b79fb35353f32f217a6003bab090deb486de28f8aa02914d5897d03984d371e.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/7b79fb35353f32f217a6003bab090deb486de28f8aa02914d5897d03984d371e.jpg)

![8c1796494cbd89a9c20760d9f63685ec4b3364c0b7c95802f493a31a613dc1c7.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/8c1796494cbd89a9c20760d9f63685ec4b3364c0b7c95802f493a31a613dc1c7.jpg)

![9523a98f8ea16a5c9bcc16adb78d3754a4a8194105e30fdee82394183571abb1.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/9523a98f8ea16a5c9bcc16adb78d3754a4a8194105e30fdee82394183571abb1.jpg)

![a19249a2374c8f8ea4bb204486aed864d912a98874d4bc1aef22b60d7729aab5.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/a19249a2374c8f8ea4bb204486aed864d912a98874d4bc1aef22b60d7729aab5.jpg)

![a1e11b31616312869c81deef12da54e59b77ac31ae1b9e897a1122fef3c7ccea.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/a1e11b31616312869c81deef12da54e59b77ac31ae1b9e897a1122fef3c7ccea.jpg)

![b2a9b62d9677f447756c2d24ec9177e62644d4a38c4b129d88a0c657a90e7e87.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/b2a9b62d9677f447756c2d24ec9177e62644d4a38c4b129d88a0c657a90e7e87.jpg)

![d5ed0f7113240634482bf9b90a6d333527180bac8cc8f2492fc5cbee06a664e2.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/d5ed0f7113240634482bf9b90a6d333527180bac8cc8f2492fc5cbee06a664e2.jpg)

![d65a6164e32161d07e68ec4c7f513d727de841ee0d6b71351810d9fb01012444.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/d65a6164e32161d07e68ec4c7f513d727de841ee0d6b71351810d9fb01012444.jpg)

![df75cd7ba4d494df3233318e7788c8539f70ade289ac30aa8bdf70c6ccd9351c.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/images/df75cd7ba4d494df3233318e7788c8539f70ade289ac30aa8bdf70c6ccd9351c.jpg)

### Tables

![27a26dbfee30d90d8d425c3e3873da2c4dbe05666942de8bbf56582123be94b1.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/tables/27a26dbfee30d90d8d425c3e3873da2c4dbe05666942de8bbf56582123be94b1.jpg)

![3ccc32e6957106dec9c6d1e0101e53d9f412bb7ea749e627ff465e07395d687e.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/tables/3ccc32e6957106dec9c6d1e0101e53d9f412bb7ea749e627ff465e07395d687e.jpg)

![3f8c62e554ea7b50747f0827d8ea49723b81c9d4c374f300cf650d32907cb703.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/tables/3f8c62e554ea7b50747f0827d8ea49723b81c9d4c374f300cf650d32907cb703.jpg)

![40d334a1a2a5f0a212a9457dbba7eab84f5ab6563412768857276e4e4fe3f6b8.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/tables/40d334a1a2a5f0a212a9457dbba7eab84f5ab6563412768857276e4e4fe3f6b8.jpg)

![41cbfb4474d0ac7d4c6ebb18efd87162b2f2df8e97a30cf929a0946adb3cdedc.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/tables/41cbfb4474d0ac7d4c6ebb18efd87162b2f2df8e97a30cf929a0946adb3cdedc.jpg)

![5c0f303a317a3ced6b6430aa706252b6c941695842f4855c44dba024d8304323.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/tables/5c0f303a317a3ced6b6430aa706252b6c941695842f4855c44dba024d8304323.jpg)

![5ef60eb6579ed590d409df4df1c5e14bdaf4c18ead783e0174b77598ec36fd85.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/tables/5ef60eb6579ed590d409df4df1c5e14bdaf4c18ead783e0174b77598ec36fd85.jpg)

![704322906941a9e000efb7183123367a497c85a61b90293ff0e776f16c877fc5.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/tables/704322906941a9e000efb7183123367a497c85a61b90293ff0e776f16c877fc5.jpg)

![a27203bac8620579263e4ba8005e620af38ad7b1ecc80b2dfb2b7dcad3f2128f.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/tables/a27203bac8620579263e4ba8005e620af38ad7b1ecc80b2dfb2b7dcad3f2128f.jpg)

![bea905def24bec1e1c3abe8c21224986e6abedeb30eff701b597a9f653dfe827.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/tables/bea905def24bec1e1c3abe8c21224986e6abedeb30eff701b597a9f653dfe827.jpg)

![eaa2abe352c0bac7e01af8c3f2f7fcdbedd4ca813d9c711ae721eefffd92d765.jpg](../nips_results/242_Not%20All%20Data%20are%20Good%20Labels_%20On%20the%20Self-supervised%20Labeling%20for%20Time%20Series%20Forecasting/tables/eaa2abe352c0bac7e01af8c3f2f7fcdbedd4ca813d9c711ae721eefffd92d765.jpg)

## AI-Researcher: Autonomous Scientific Innovation


### Images

![01fcdf093908fc75909d7d45755740a2a5bd6dfe668a47bc11fb892c0e1cdca8.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/images/01fcdf093908fc75909d7d45755740a2a5bd6dfe668a47bc11fb892c0e1cdca8.jpg)

![38a9806c0ebbe0521e036d3dafa2afb3798dbf78f42e285d567f8d18e6e6a842.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/images/38a9806c0ebbe0521e036d3dafa2afb3798dbf78f42e285d567f8d18e6e6a842.jpg)

![544d28904cd3380a5f4dbe664222c1e49340105c3aa56df0ca9391dabe378a4e.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/images/544d28904cd3380a5f4dbe664222c1e49340105c3aa56df0ca9391dabe378a4e.jpg)

![833a793feaa3efe0977ce44234990f3d13f62f98c4cfa0e708e1202e9112ae42.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/images/833a793feaa3efe0977ce44234990f3d13f62f98c4cfa0e708e1202e9112ae42.jpg)

![9b66b63586bd5eeeb06e3fa9909a96fc5edc678ce2e96dd9cb66125129a7c7c6.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/images/9b66b63586bd5eeeb06e3fa9909a96fc5edc678ce2e96dd9cb66125129a7c7c6.jpg)

![c1aa5d2f8f548245177d856038938d41b3a41057c4337d0bb32408487dc76be9.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/images/c1aa5d2f8f548245177d856038938d41b3a41057c4337d0bb32408487dc76be9.jpg)

![d4f37d74fdf3bc58bdbd247a3f833f3e22e5505752f0694a1aa9bff0efb419b0.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/images/d4f37d74fdf3bc58bdbd247a3f833f3e22e5505752f0694a1aa9bff0efb419b0.jpg)

![da7f951c8587d1921d7395ac585729ec005161696a69067a37e6f2a25215be86.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/images/da7f951c8587d1921d7395ac585729ec005161696a69067a37e6f2a25215be86.jpg)

![e5a6d9f5134a2e76b3c3be0122b4465246ad5a7777fbad66efe374fe0feda97a.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/images/e5a6d9f5134a2e76b3c3be0122b4465246ad5a7777fbad66efe374fe0feda97a.jpg)

![f2acf61dab42ce06ea2c517222c77b0dbccea69d0abda6a1c4eb3001211d90ce.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/images/f2acf61dab42ce06ea2c517222c77b0dbccea69d0abda6a1c4eb3001211d90ce.jpg)

### Tables

![15589cd739963ad0e37eae41b89ea41b5d6b2b3626b140df1c5e2118c26879f0.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/tables/15589cd739963ad0e37eae41b89ea41b5d6b2b3626b140df1c5e2118c26879f0.jpg)

![32202d22f6522d2fb1d4c3f1c5f4dba9b2492f1fa196a64ba8650c625eae7c6a.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/tables/32202d22f6522d2fb1d4c3f1c5f4dba9b2492f1fa196a64ba8650c625eae7c6a.jpg)

![40157b62c5eb669e8184c97c093b259a2fff86b65421ee255716a6b3a97ddc13.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/tables/40157b62c5eb669e8184c97c093b259a2fff86b65421ee255716a6b3a97ddc13.jpg)

![5a64db3cfccc4f853f0f98455d1787e2e01a0c026ccee9c30a20e06c2695b816.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/tables/5a64db3cfccc4f853f0f98455d1787e2e01a0c026ccee9c30a20e06c2695b816.jpg)

![93e7b0fac42c15d718da2a4edaee960ee01a86af0e73f9bb63d02bea2e7b4e21.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/tables/93e7b0fac42c15d718da2a4edaee960ee01a86af0e73f9bb63d02bea2e7b4e21.jpg)

![a53e363490e54d929cd6beaf7e82dc871eef625aeda93083662ed39b4d36bed2.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/tables/a53e363490e54d929cd6beaf7e82dc871eef625aeda93083662ed39b4d36bed2.jpg)

![b283697f3b42c96ddbe8f6e2077d76b621cf6567737a5281fd5d98732749f847.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/tables/b283697f3b42c96ddbe8f6e2077d76b621cf6567737a5281fd5d98732749f847.jpg)

![cf11c027df03b02714b027e2f15884c59e1df5d061b0391b9cd4f7dd8787ecd7.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/tables/cf11c027df03b02714b027e2f15884c59e1df5d061b0391b9cd4f7dd8787ecd7.jpg)

![fea90b8285097c9f639cbc17678ce31461890e3213a20a25779078de94d5ae67.jpg](../nips_results/243_AI-Researcher_%20Autonomous%20Scientific%20Innovation/tables/fea90b8285097c9f639cbc17678ce31461890e3213a20a25779078de94d5ae67.jpg)

## ConTextTab: A Semantics-Aware Tabular In-Context Learner


### Images

![0601bedf999e8ad6b908521928697752803564149e901a16cd4aceaa3cc1212b.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/0601bedf999e8ad6b908521928697752803564149e901a16cd4aceaa3cc1212b.jpg)

![0da45d8d3665e2e919d53360c0b1952304e35ca57e018e35e7990566c632dfd9.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/0da45d8d3665e2e919d53360c0b1952304e35ca57e018e35e7990566c632dfd9.jpg)

![1f15125a0c4f0dffe0a8a2e5cf7d1b209263fca5d70368131d873def8713d3d4.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/1f15125a0c4f0dffe0a8a2e5cf7d1b209263fca5d70368131d873def8713d3d4.jpg)

![311ff10873b9535664f3505fa8a19f577b06e4c46825f7c63fbfa8fba051efd2.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/311ff10873b9535664f3505fa8a19f577b06e4c46825f7c63fbfa8fba051efd2.jpg)

![34b75be9daa2237ff2e1622128f4d9cca7f66ad6b217f9ef7439ce03d8ca3df0.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/34b75be9daa2237ff2e1622128f4d9cca7f66ad6b217f9ef7439ce03d8ca3df0.jpg)

![36ff7a609109ddaadcd511973f354598c0624b094e6b13f8b75947fc7fc46f0e.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/36ff7a609109ddaadcd511973f354598c0624b094e6b13f8b75947fc7fc46f0e.jpg)

![39c62c6888c3090b3e186e6f902292185f4963732cafb4cbde8dc447e617b80d.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/39c62c6888c3090b3e186e6f902292185f4963732cafb4cbde8dc447e617b80d.jpg)

![39c75bc0a477f19aae0c399eb2cbaa12aaa306cd7662dbbf5d89a970190c54ab.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/39c75bc0a477f19aae0c399eb2cbaa12aaa306cd7662dbbf5d89a970190c54ab.jpg)

![498117617262bf437eb09327daea04e4d1f5fc65593f2e577d306008bae5ff82.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/498117617262bf437eb09327daea04e4d1f5fc65593f2e577d306008bae5ff82.jpg)

![583f677aaf21b57de6286ed85db136dc374abcc30598056504e2d298982ea1e7.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/583f677aaf21b57de6286ed85db136dc374abcc30598056504e2d298982ea1e7.jpg)

![8ed558bb538bad6710e72dbeacbd4804909fb06d330f95efc58c1fd2305dfab3.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/8ed558bb538bad6710e72dbeacbd4804909fb06d330f95efc58c1fd2305dfab3.jpg)

![c14407258c04f93f50e942956c86fdfa2bbf1a547861288047da8e65ee3c3b70.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/c14407258c04f93f50e942956c86fdfa2bbf1a547861288047da8e65ee3c3b70.jpg)

![cde65db1534c271749fdfaa2d5704fef0278e2af801399db83587af06f3e6a9c.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/cde65db1534c271749fdfaa2d5704fef0278e2af801399db83587af06f3e6a9c.jpg)

![debd27d14c170a5c6dc2281bed43991ba3d4eaba3db35131f248c3cd8aa089b3.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/images/debd27d14c170a5c6dc2281bed43991ba3d4eaba3db35131f248c3cd8aa089b3.jpg)

### Tables

![0fe176b2170b4df558e818e31ca9eb0ef7fc065b673dd084ba2e0dfbf3b0973a.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/tables/0fe176b2170b4df558e818e31ca9eb0ef7fc065b673dd084ba2e0dfbf3b0973a.jpg)

![1dec602623da794a1bc935d474102aba4240173a6685376f4d67d3815d4a93c5.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/tables/1dec602623da794a1bc935d474102aba4240173a6685376f4d67d3815d4a93c5.jpg)

![258d12be18452f9f83400a6c1addc476b7c9df623ca16ba626824139cd639ca4.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/tables/258d12be18452f9f83400a6c1addc476b7c9df623ca16ba626824139cd639ca4.jpg)

![610adf04815b0c8ea2707941632adb94e5877c10d88ab8f6621a39d10b33632d.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/tables/610adf04815b0c8ea2707941632adb94e5877c10d88ab8f6621a39d10b33632d.jpg)

![631d1211ae9752ae0928bdc0e4c15f5060aaf3be5692ed56008eb2b51fc6f136.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/tables/631d1211ae9752ae0928bdc0e4c15f5060aaf3be5692ed56008eb2b51fc6f136.jpg)

![919e4f7f9a8fa2d7a210fd84152806fc666f82811b7424896a74ee264324fdf0.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/tables/919e4f7f9a8fa2d7a210fd84152806fc666f82811b7424896a74ee264324fdf0.jpg)

![933b255e6dc86d4d0fa1f9b8e056c869468300df0c44329f7d59cab3fe9ae585.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/tables/933b255e6dc86d4d0fa1f9b8e056c869468300df0c44329f7d59cab3fe9ae585.jpg)

![9ddb9920a4ddedab907f1221aeda390d660af25a50d2ecf966fb35c3bf983bb3.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/tables/9ddb9920a4ddedab907f1221aeda390d660af25a50d2ecf966fb35c3bf983bb3.jpg)

![bb5deb51163f8af771da3e285562158c1c2226f05640e40987222c39a8458cbf.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/tables/bb5deb51163f8af771da3e285562158c1c2226f05640e40987222c39a8458cbf.jpg)

![f190f1084b34a092a317bf89c713e96e1ca212ea93407083c430061a06673201.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/tables/f190f1084b34a092a317bf89c713e96e1ca212ea93407083c430061a06673201.jpg)

![f91c276b6d55fa4fe66e5555a7e0c3c4151dad0c98e88e71066f3d00f7dd17e0.jpg](../nips_results/244_ConTextTab_%20A%20Semantics-Aware%20Tabular%20In-Context%20Learner/tables/f91c276b6d55fa4fe66e5555a7e0c3c4151dad0c98e88e71066f3d00f7dd17e0.jpg)

## Right Question is Already Half the Answer: Fully Unsupervised LLM Reasoning Incentivization


### Images

![4a6ee937c430a2193ffcabdbf654977c0821accaa0adc04fc8d40bdcbdcda101.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/images/4a6ee937c430a2193ffcabdbf654977c0821accaa0adc04fc8d40bdcbdcda101.jpg)

![55de00f3e6ce52f5e4eca5f53852c7bc28aa775a46bf298f55c3eb1c4ed248f6.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/images/55de00f3e6ce52f5e4eca5f53852c7bc28aa775a46bf298f55c3eb1c4ed248f6.jpg)

![6ddb2567669d6eea49fa631c12f837b4984ff095adc73daab6d17e4f749ccfa9.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/images/6ddb2567669d6eea49fa631c12f837b4984ff095adc73daab6d17e4f749ccfa9.jpg)

![b003ec9d962152b2fd40cf823a41923e5779dda531b0ac03e8b6fe99f57a1dfe.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/images/b003ec9d962152b2fd40cf823a41923e5779dda531b0ac03e8b6fe99f57a1dfe.jpg)

![e3fcee30d4215ac2ed8a8e499c412cede2d469be5fc7eabfec1f5c7c0f71c49a.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/images/e3fcee30d4215ac2ed8a8e499c412cede2d469be5fc7eabfec1f5c7c0f71c49a.jpg)

![ead8aaaf33283211f72440fe236074fe3f7b13e5361c65b6a9f1c626a0e622d1.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/images/ead8aaaf33283211f72440fe236074fe3f7b13e5361c65b6a9f1c626a0e622d1.jpg)

### Tables

![07f969ec03bdb3eb0efa1b6d9778f1dcacdb3dd9258d8fcee425b7e87bdf685c.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/tables/07f969ec03bdb3eb0efa1b6d9778f1dcacdb3dd9258d8fcee425b7e87bdf685c.jpg)

![1cd80cdd7ef02be4ed27bd29380da263392e9042bf9646071f7df6ffbcd56cf4.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/tables/1cd80cdd7ef02be4ed27bd29380da263392e9042bf9646071f7df6ffbcd56cf4.jpg)

![208d17adde3ae04b5ddcc2278c2560da8cd5998b94eae17bc66fa33a70cd6e43.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/tables/208d17adde3ae04b5ddcc2278c2560da8cd5998b94eae17bc66fa33a70cd6e43.jpg)

![3a613743a2585e4f36de73faaaeac71a77218bed8dd95b25e3e8e0281238dde2.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/tables/3a613743a2585e4f36de73faaaeac71a77218bed8dd95b25e3e8e0281238dde2.jpg)

![4dee6ad5137fae007758017aee72463e872a2efa9552efe494e44700af10e036.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/tables/4dee6ad5137fae007758017aee72463e872a2efa9552efe494e44700af10e036.jpg)

![615f9c7e90c1947ec5e8cd6610db1912080dd1cb02ff90004712944121f82f73.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/tables/615f9c7e90c1947ec5e8cd6610db1912080dd1cb02ff90004712944121f82f73.jpg)

![b14d4906c9c30b09e8c2bc0fd6f13098be98a3ff9141337573b496b92c752b5c.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/tables/b14d4906c9c30b09e8c2bc0fd6f13098be98a3ff9141337573b496b92c752b5c.jpg)

![b1ff3dbf9aeaea11813ec1f5154e879063d4caa3699decb51e126ea0a9a5562a.jpg](../nips_results/245_Right%20Question%20is%20Already%20Half%20the%20Answer_%20Fully%20Unsupervised%20LLM%20Reasoning%20Incentivization/tables/b1ff3dbf9aeaea11813ec1f5154e879063d4caa3699decb51e126ea0a9a5562a.jpg)

## Integration Matters for Learning PDEs with Backwards SDEs


### Images

![1236b1164f006737959951c869af3a296c3898988d2910d91429d1cb74037526.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/images/1236b1164f006737959951c869af3a296c3898988d2910d91429d1cb74037526.jpg)

![2dae846fe9f3fb118a5dd1f40ae369f804ff27413f95fee15cfa20966d65449f.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/images/2dae846fe9f3fb118a5dd1f40ae369f804ff27413f95fee15cfa20966d65449f.jpg)

![3cc526d7281a19e0d32cf9dc1877c87bfca6d2258026db1cd5008b88b5413e24.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/images/3cc526d7281a19e0d32cf9dc1877c87bfca6d2258026db1cd5008b88b5413e24.jpg)

![5cbdbc6dd8843be2c8be95852a1fb6a12deaadcf82e8f2a943d0e5d1f08fd0f3.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/images/5cbdbc6dd8843be2c8be95852a1fb6a12deaadcf82e8f2a943d0e5d1f08fd0f3.jpg)

![7274fd3209385fac945f91487013805c660227633a2fbe03f54947075cb677db.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/images/7274fd3209385fac945f91487013805c660227633a2fbe03f54947075cb677db.jpg)

![87ae3b3427b18638251505a45ba7342a45e7ea9ff02c481fb1d3546371d8d108.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/images/87ae3b3427b18638251505a45ba7342a45e7ea9ff02c481fb1d3546371d8d108.jpg)

![d4041e6c3c4f6f8560f8275e22734c934d5f169e7aa50b481f43fbb504783620.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/images/d4041e6c3c4f6f8560f8275e22734c934d5f169e7aa50b481f43fbb504783620.jpg)

![e5584b1c10437847fff5a01224914884e846e5899d8716973547cf44a0707f73.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/images/e5584b1c10437847fff5a01224914884e846e5899d8716973547cf44a0707f73.jpg)

![f41b4ad208d53de2bcdd492edec8a25f49ca6591e9f2ce354ad47088bb91b51f.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/images/f41b4ad208d53de2bcdd492edec8a25f49ca6591e9f2ce354ad47088bb91b51f.jpg)

![fc0b332a4d7517a2b39bb60291f6860e71b39b8dc32acc479b969059e8550a0d.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/images/fc0b332a4d7517a2b39bb60291f6860e71b39b8dc32acc479b969059e8550a0d.jpg)

### Tables

![1ae2809757ff8acb8ce2b80c3548758500f8f7a1e25def4d8f756f5bb765c570.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/tables/1ae2809757ff8acb8ce2b80c3548758500f8f7a1e25def4d8f756f5bb765c570.jpg)

![63846a83f9254a39b85cc1675d4374032973d22fbd6c3e478d56505ede48edc4.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/tables/63846a83f9254a39b85cc1675d4374032973d22fbd6c3e478d56505ede48edc4.jpg)

![6d16675ebe836ee8ba8cc9fcc6f72cd7e270a8ec254cd9c29b0dc0c32f306135.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/tables/6d16675ebe836ee8ba8cc9fcc6f72cd7e270a8ec254cd9c29b0dc0c32f306135.jpg)

![7b3f9b59babb8614b52db1d7e39c660ea03a2894302b2844ca01c516804b96ea.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/tables/7b3f9b59babb8614b52db1d7e39c660ea03a2894302b2844ca01c516804b96ea.jpg)

![7b69cd6111e5738c2d1dc839dfd928a65740f62fc9abf303d8b4a0f85a7c92ea.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/tables/7b69cd6111e5738c2d1dc839dfd928a65740f62fc9abf303d8b4a0f85a7c92ea.jpg)

![f3b1bc6e9d872ba9a9edf00995c7475e5b2a37dba57b6a3ff38aa9a16dbb041b.jpg](../nips_results/246_Integration%20Matters%20for%20Learning%20PDEs%20with%20Backwards%20SDEs/tables/f3b1bc6e9d872ba9a9edf00995c7475e5b2a37dba57b6a3ff38aa9a16dbb041b.jpg)

## KARMA: Leveraging Multi-Agent LLMs for Automated Knowledge Graph Enrichment


### Images

![191ece7477a477e25c3740b1641f0935d35882cc70a1cc1390719988fa46905a.jpg](../nips_results/247_KARMA_%20Leveraging%20Multi-Agent%20LLMs%20for%20Automated%20Knowledge%20Graph%20Enrichment/images/191ece7477a477e25c3740b1641f0935d35882cc70a1cc1390719988fa46905a.jpg)

![84f7363b5c92a21b871e20d457dfe0f2384fcd40c110d26592bf7088c3169d3d.jpg](../nips_results/247_KARMA_%20Leveraging%20Multi-Agent%20LLMs%20for%20Automated%20Knowledge%20Graph%20Enrichment/images/84f7363b5c92a21b871e20d457dfe0f2384fcd40c110d26592bf7088c3169d3d.jpg)

![8bbf7afd1e8899e60320950e213a76cc757f11d92e13a08b3af4a49e9240f2a6.jpg](../nips_results/247_KARMA_%20Leveraging%20Multi-Agent%20LLMs%20for%20Automated%20Knowledge%20Graph%20Enrichment/images/8bbf7afd1e8899e60320950e213a76cc757f11d92e13a08b3af4a49e9240f2a6.jpg)

![94bfd3d2df8459f67f9f46299485fe2017a31998a924fff02d050ffc3e67f1f4.jpg](../nips_results/247_KARMA_%20Leveraging%20Multi-Agent%20LLMs%20for%20Automated%20Knowledge%20Graph%20Enrichment/images/94bfd3d2df8459f67f9f46299485fe2017a31998a924fff02d050ffc3e67f1f4.jpg)

![c05ae3565b651351a9eb8b18f92890ba256ddb84c466330f6c8824950349ba88.jpg](../nips_results/247_KARMA_%20Leveraging%20Multi-Agent%20LLMs%20for%20Automated%20Knowledge%20Graph%20Enrichment/images/c05ae3565b651351a9eb8b18f92890ba256ddb84c466330f6c8824950349ba88.jpg)

![c428979cc84b8b5579139e00cc1b4a52dcf71bf93860e52c4ff4c2f5eea1675c.jpg](../nips_results/247_KARMA_%20Leveraging%20Multi-Agent%20LLMs%20for%20Automated%20Knowledge%20Graph%20Enrichment/images/c428979cc84b8b5579139e00cc1b4a52dcf71bf93860e52c4ff4c2f5eea1675c.jpg)

![d74b5719d3727102216a5e5de9e61a71e6310ce29a527c882503bd530f3d8c9f.jpg](../nips_results/247_KARMA_%20Leveraging%20Multi-Agent%20LLMs%20for%20Automated%20Knowledge%20Graph%20Enrichment/images/d74b5719d3727102216a5e5de9e61a71e6310ce29a527c882503bd530f3d8c9f.jpg)

### Tables

![1057962a55fac89403f47a6873c0856ac31dd98614f9287440dd286dab806f40.jpg](../nips_results/247_KARMA_%20Leveraging%20Multi-Agent%20LLMs%20for%20Automated%20Knowledge%20Graph%20Enrichment/tables/1057962a55fac89403f47a6873c0856ac31dd98614f9287440dd286dab806f40.jpg)

![746b675d4debdd5dd7c3fdac2b054ba2486e26862e0a84173d76b4aa5951dce4.jpg](../nips_results/247_KARMA_%20Leveraging%20Multi-Agent%20LLMs%20for%20Automated%20Knowledge%20Graph%20Enrichment/tables/746b675d4debdd5dd7c3fdac2b054ba2486e26862e0a84173d76b4aa5951dce4.jpg)

## T-REGS: Minimum Spanning Tree Regularization for Self-Supervised Learning


### Images

![0eb65892272d569f9101d65b6b402ef9ceef030ffd509190429f1792597b50b8.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/images/0eb65892272d569f9101d65b6b402ef9ceef030ffd509190429f1792597b50b8.jpg)

![1339cfa9456cb1e9abca6649c22e70fa492e7833f371c0abf2db6c042984cb70.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/images/1339cfa9456cb1e9abca6649c22e70fa492e7833f371c0abf2db6c042984cb70.jpg)

![1837c89f2c502c6483752538c91b01f9a6abf61880d24548d238957217246152.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/images/1837c89f2c502c6483752538c91b01f9a6abf61880d24548d238957217246152.jpg)

![4e649e9369741a2fca4275f5801f5173d713d5b1c91335ffa3fd04f40bcfeb17.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/images/4e649e9369741a2fca4275f5801f5173d713d5b1c91335ffa3fd04f40bcfeb17.jpg)

![5083728fc56d6ae5c290e26fdbcce5d272b0a2281d6cadbc3f0760a3e48f30a9.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/images/5083728fc56d6ae5c290e26fdbcce5d272b0a2281d6cadbc3f0760a3e48f30a9.jpg)

![9fe10f48890865511f970dcb23b8541eac1caf8f89bb00fb95237d67687bba5a.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/images/9fe10f48890865511f970dcb23b8541eac1caf8f89bb00fb95237d67687bba5a.jpg)

![d6a36ef7eda7462fa8a8fd60b4faff11a23c5d9a225e0b8db64060d7c15f48a0.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/images/d6a36ef7eda7462fa8a8fd60b4faff11a23c5d9a225e0b8db64060d7c15f48a0.jpg)

![d8e093037ffecc11136fa96dde581812dfe39bd99c6bca30b126280a1f0e228c.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/images/d8e093037ffecc11136fa96dde581812dfe39bd99c6bca30b126280a1f0e228c.jpg)

### Tables

![41eb23bcfefe51ff40b1c8b4012b6230b2f9be7c036a15b4bb620233c75ad58f.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/tables/41eb23bcfefe51ff40b1c8b4012b6230b2f9be7c036a15b4bb620233c75ad58f.jpg)

![41ecf90aacc2b231d2e5ee95a42ccaff22a847c6b5bd854f9af090cd3203fdc8.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/tables/41ecf90aacc2b231d2e5ee95a42ccaff22a847c6b5bd854f9af090cd3203fdc8.jpg)

![6be3bae35819bee9e1e3940b7c6ec3f0f5bcb7be2d258ed059847a9850a18d8f.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/tables/6be3bae35819bee9e1e3940b7c6ec3f0f5bcb7be2d258ed059847a9850a18d8f.jpg)

![704dc2a67e783ef8523fcf12d1d47ff3bacee4390a3931e4d7504f943ddb72b4.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/tables/704dc2a67e783ef8523fcf12d1d47ff3bacee4390a3931e4d7504f943ddb72b4.jpg)

![9aa79f675f245cdcfed997b195621bcffbc5ee5c44b84e45ccf70adab45e15bf.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/tables/9aa79f675f245cdcfed997b195621bcffbc5ee5c44b84e45ccf70adab45e15bf.jpg)

![a3695534420522d2c65bba422ba1d16125a98f7e1d1d6d7ed4de27a956b26b8b.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/tables/a3695534420522d2c65bba422ba1d16125a98f7e1d1d6d7ed4de27a956b26b8b.jpg)

![c718498087cdc166ef0bf5d70f71ea9cb4922229ddc326172877f186b0ed5dbe.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/tables/c718498087cdc166ef0bf5d70f71ea9cb4922229ddc326172877f186b0ed5dbe.jpg)

![c8827c1f480d72228a6e7e326bcab066693bb281af91388764bb35604a0004e6.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/tables/c8827c1f480d72228a6e7e326bcab066693bb281af91388764bb35604a0004e6.jpg)

![d1af04723a35b4622ac79f93ff65f5178193c220ad0eac29b3c0d266f615307d.jpg](../nips_results/248_T-REGS_%20Minimum%20Spanning%20Tree%20Regularization%20for%20Self-Supervised%20Learning/tables/d1af04723a35b4622ac79f93ff65f5178193c220ad0eac29b3c0d266f615307d.jpg)

## DisMo: Disentangled Motion Representations for Open-World Motion Transfer


### Images

![25d1efc3fda6218fdc329e81824c6f7b75af619d799c3684a63750912f25baa0.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/25d1efc3fda6218fdc329e81824c6f7b75af619d799c3684a63750912f25baa0.jpg)

![331f591809c248abda781109bd72da4e75c8059845272eb50c01d91c663c3403.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/331f591809c248abda781109bd72da4e75c8059845272eb50c01d91c663c3403.jpg)

![36df00557f5ce29a5446e1ece2a9af427ce606680048dbc2200d874ac88ecec5.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/36df00557f5ce29a5446e1ece2a9af427ce606680048dbc2200d874ac88ecec5.jpg)

![3782f3b5a1d7b318de48f37e19ff95448b76d49909263d8b7d97306a8acf7fec.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/3782f3b5a1d7b318de48f37e19ff95448b76d49909263d8b7d97306a8acf7fec.jpg)

![39e49c8b86d91dc80d35e51bdbd9cb3c67be313c6ff80b210ca478b97f614991.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/39e49c8b86d91dc80d35e51bdbd9cb3c67be313c6ff80b210ca478b97f614991.jpg)

![419e32752972bacdebbd2d1d3d9c2127cc65f02ad02428e813f9441679f24ec1.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/419e32752972bacdebbd2d1d3d9c2127cc65f02ad02428e813f9441679f24ec1.jpg)

![4ade0b2b36c3366a602bef73af0334ff1a4933ec2443e6879a0882cb946961ef.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/4ade0b2b36c3366a602bef73af0334ff1a4933ec2443e6879a0882cb946961ef.jpg)

![4d7264c48fffafa9f73bd2eba732b0f55bc67e194a44560b2df9d7a42370b6ef.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/4d7264c48fffafa9f73bd2eba732b0f55bc67e194a44560b2df9d7a42370b6ef.jpg)

![644091e3779675eb3ab0a89daade156d7a9ba0a3286dbd4ed135b87305e68e16.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/644091e3779675eb3ab0a89daade156d7a9ba0a3286dbd4ed135b87305e68e16.jpg)

![850a10df6ba2fcdf709d6a40314f521a71833e605ef4921ea02c04dad7bc19e5.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/850a10df6ba2fcdf709d6a40314f521a71833e605ef4921ea02c04dad7bc19e5.jpg)

![879164b1a459d88855462e05e8175a492f418860ec3777d1c94a3737ce7568c3.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/879164b1a459d88855462e05e8175a492f418860ec3777d1c94a3737ce7568c3.jpg)

![88620d959e470b9b976e237ab10a766788173a5eacba94d4dcda7d9ec7fea1b1.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/88620d959e470b9b976e237ab10a766788173a5eacba94d4dcda7d9ec7fea1b1.jpg)

![8ce881d485f7369e7a572639e1874ab73a379981079d0b1ec0dfb8c880dcdcb2.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/8ce881d485f7369e7a572639e1874ab73a379981079d0b1ec0dfb8c880dcdcb2.jpg)

![8ed87ec50334d2333970bb2d2301c3d5295421c06211796919418cebbbff4189.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/8ed87ec50334d2333970bb2d2301c3d5295421c06211796919418cebbbff4189.jpg)

![b5401fa7af9a3dd845a7ba8ea806fcb17f21b17133c45e8a7cc1321d92b5dfb7.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/b5401fa7af9a3dd845a7ba8ea806fcb17f21b17133c45e8a7cc1321d92b5dfb7.jpg)

![b626150493aed8d26066bbe48ecc350bc15baba303310b6a97c3bdf01a941110.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/b626150493aed8d26066bbe48ecc350bc15baba303310b6a97c3bdf01a941110.jpg)

![ea444a14cebd5581a9393db25ee9df39c4087ff28057ce8650abff8c220c93ee.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/ea444a14cebd5581a9393db25ee9df39c4087ff28057ce8650abff8c220c93ee.jpg)

![fd40e67541d9f6f09ec86a25e2451ac5c7d91bccd99a88a2e348c5ca3c40fcd6.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/images/fd40e67541d9f6f09ec86a25e2451ac5c7d91bccd99a88a2e348c5ca3c40fcd6.jpg)

### Tables

![27a1b77dcb97623e0feb39d80d69c5e7a3fdc337a2114a7695d712ecead9a301.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/27a1b77dcb97623e0feb39d80d69c5e7a3fdc337a2114a7695d712ecead9a301.jpg)

![3cac9e951fddddf2e00af95569bf6901f1879a74f82e9664c383f53b0df5f6b8.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/3cac9e951fddddf2e00af95569bf6901f1879a74f82e9664c383f53b0df5f6b8.jpg)

![46c05e726a97e42eb9e48defa0a1b55209b779e8dd72d34bafbc234e759eefba.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/46c05e726a97e42eb9e48defa0a1b55209b779e8dd72d34bafbc234e759eefba.jpg)

![4c9e92211619a824c6fd9a7c4e71309ab50b80ed90d454baa38921f5290b55f0.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/4c9e92211619a824c6fd9a7c4e71309ab50b80ed90d454baa38921f5290b55f0.jpg)

![70f1689c32866554faf5cfdb9feed228bb950591198e3976607d27eb71ea1ade.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/70f1689c32866554faf5cfdb9feed228bb950591198e3976607d27eb71ea1ade.jpg)

![a0142a66dbd29d90b2c8410ac666ffc1800897a7432f6a0338f2b16f8299b150.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/a0142a66dbd29d90b2c8410ac666ffc1800897a7432f6a0338f2b16f8299b150.jpg)

![a05c60eea229b4950f9a65b968cdad08a67ca8c42158b59be4e9882e434b43c4.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/a05c60eea229b4950f9a65b968cdad08a67ca8c42158b59be4e9882e434b43c4.jpg)

![a1c4e5edd930f8c496476fe72196de5cb935884f6c133523f2dd01d5950ed90f.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/a1c4e5edd930f8c496476fe72196de5cb935884f6c133523f2dd01d5950ed90f.jpg)

![b3cc63694291cebe88f6c2675234de7dce5375b4db9b6fac0cd1764efbe010b4.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/b3cc63694291cebe88f6c2675234de7dce5375b4db9b6fac0cd1764efbe010b4.jpg)

![c30369a4f874ab2f97b9e1a9ff7695917bffe41060d17a2fcb63ea4b2532e5dd.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/c30369a4f874ab2f97b9e1a9ff7695917bffe41060d17a2fcb63ea4b2532e5dd.jpg)

![e9dc7435a2f21788c49318f5043f131010332cf95f616f34a2c1ea309577c0e5.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/e9dc7435a2f21788c49318f5043f131010332cf95f616f34a2c1ea309577c0e5.jpg)

![f7758f5432a5c5a9185d360f814af81b046963cafa77a25acdb811df5a96ffba.jpg](../nips_results/249_DisMo_%20Disentangled%20Motion%20Representations%20for%20Open-World%20Motion%20Transfer/tables/f7758f5432a5c5a9185d360f814af81b046963cafa77a25acdb811df5a96ffba.jpg)

## Improving Bilinear RNN with Closed-loop Control


### Images

![29634c566756e75a88b224d686978e204e1d5113e9ec01f116dff4a9c0ef2124.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/images/29634c566756e75a88b224d686978e204e1d5113e9ec01f116dff4a9c0ef2124.jpg)

![346edb980fe2eeef4e3740146417099c45c18677da35edb5d244e90a18dd2b08.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/images/346edb980fe2eeef4e3740146417099c45c18677da35edb5d244e90a18dd2b08.jpg)

![8080ef63bf7c9b7ec2279975a9a2903a8cef193e2beb01f36cd401bc8bfdfcca.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/images/8080ef63bf7c9b7ec2279975a9a2903a8cef193e2beb01f36cd401bc8bfdfcca.jpg)

![bed868f6ba48f954f932338e90ccc06bfe2645c01dac2ed26b968e0f90e61741.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/images/bed868f6ba48f954f932338e90ccc06bfe2645c01dac2ed26b968e0f90e61741.jpg)

![c45aeb2104d3565221e3062d9d71abcb6d14bbe386aa690eafcef0a4e93d9928.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/images/c45aeb2104d3565221e3062d9d71abcb6d14bbe386aa690eafcef0a4e93d9928.jpg)

### Tables

![0652c73d75fbb2ff599e380e7055eab55c75379305777a642d2649bc3cefeeb5.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/tables/0652c73d75fbb2ff599e380e7055eab55c75379305777a642d2649bc3cefeeb5.jpg)

![2f08cbdfce1832b18ef9a867e8d2ea24e15b6a9fab27913742b9371d8f4d4b90.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/tables/2f08cbdfce1832b18ef9a867e8d2ea24e15b6a9fab27913742b9371d8f4d4b90.jpg)

![68899c834efb92421d28b3e1dfd28c179ba10da22c5a1699248f2ac8a99ec42f.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/tables/68899c834efb92421d28b3e1dfd28c179ba10da22c5a1699248f2ac8a99ec42f.jpg)

![6be1007fb0b16fd818122b360ecb85bb5f2dd66f00ac42a9817847798a6ee5fd.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/tables/6be1007fb0b16fd818122b360ecb85bb5f2dd66f00ac42a9817847798a6ee5fd.jpg)

![b0be5ca4173ef0365149b8f24b76aaf47ddd7b5cc1d86a46677cbd41ce0c09a1.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/tables/b0be5ca4173ef0365149b8f24b76aaf47ddd7b5cc1d86a46677cbd41ce0c09a1.jpg)

![bccfaab68bb4be3ff372cb546581124d76289df16994d01d11d478002a0ed6bf.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/tables/bccfaab68bb4be3ff372cb546581124d76289df16994d01d11d478002a0ed6bf.jpg)

![cb284dbcfe243a6751c1eccacedfa9ecebe755b632c831fdbbf345061a1da676.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/tables/cb284dbcfe243a6751c1eccacedfa9ecebe755b632c831fdbbf345061a1da676.jpg)

![e6d41b9d45934dbd1055ac50eff5cde6c2a231f3c6524176f7bd7c83804f4ed6.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/tables/e6d41b9d45934dbd1055ac50eff5cde6c2a231f3c6524176f7bd7c83804f4ed6.jpg)

![e81de7a73904ca0ca766844f4f5b585455edddc802ae09af2691d039f746d22b.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/tables/e81de7a73904ca0ca766844f4f5b585455edddc802ae09af2691d039f746d22b.jpg)

![ed902851f8a9f0f91e81ca363062031c3a7a969d700f41e15602c3f20ae72593.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/tables/ed902851f8a9f0f91e81ca363062031c3a7a969d700f41e15602c3f20ae72593.jpg)

![f6ed4881d856ab13bb1af22433b8ccb797315d61a9d5bb9845279a5804943f67.jpg](../nips_results/250_Improving%20Bilinear%20RNN%20with%20Closed-loop%20Control/tables/f6ed4881d856ab13bb1af22433b8ccb797315d61a9d5bb9845279a5804943f67.jpg)

## Generalized Top-k Mallows Model for Ranked Choices


### Images

![03e02642849ede85c32b5cd7298fa83b451759d69e9b3c53ac09b76d8cf3e538.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/images/03e02642849ede85c32b5cd7298fa83b451759d69e9b3c53ac09b76d8cf3e538.jpg)

![2c306241e6168a9ed88d3d98dfa8446fb1c4801e44e66304bd894736f37d8956.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/images/2c306241e6168a9ed88d3d98dfa8446fb1c4801e44e66304bd894736f37d8956.jpg)

![4440405c32ba88a9394a7b46bc7db77b4ae2234a6b4ecacfc9c7db2065f9721b.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/images/4440405c32ba88a9394a7b46bc7db77b4ae2234a6b4ecacfc9c7db2065f9721b.jpg)

![6b6087d91bfc39aa42ebad237c3291455a60ab33ae6226f274c430efd4578d5c.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/images/6b6087d91bfc39aa42ebad237c3291455a60ab33ae6226f274c430efd4578d5c.jpg)

![f178869b75015a1b6a61dd9e8007ff01f23158bfdaf43d69acac4936452850f9.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/images/f178869b75015a1b6a61dd9e8007ff01f23158bfdaf43d69acac4936452850f9.jpg)

### Tables

![371f34641facc3806792c6d606a14ba49a9786698691d0243b12685c0c62bb44.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/tables/371f34641facc3806792c6d606a14ba49a9786698691d0243b12685c0c62bb44.jpg)

![57535cd5889fa83c24268d1c0b66913b91ca5579b39c037fb0bb63b8e1339961.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/tables/57535cd5889fa83c24268d1c0b66913b91ca5579b39c037fb0bb63b8e1339961.jpg)

![5c0e93ec1a9b7746cff4c8b56c95ba5a990a89b6ca8e0594ad8dab84da695965.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/tables/5c0e93ec1a9b7746cff4c8b56c95ba5a990a89b6ca8e0594ad8dab84da695965.jpg)

![702bc49c213b3fd944a3011e293daca7d249ac655c8e129fb538690462d4086e.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/tables/702bc49c213b3fd944a3011e293daca7d249ac655c8e129fb538690462d4086e.jpg)

![9358ec3d80dd7f80dabca2a084f2cc72c47ecf1234fd2669ddbad62002abfbd5.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/tables/9358ec3d80dd7f80dabca2a084f2cc72c47ecf1234fd2669ddbad62002abfbd5.jpg)

![97eb88e04dd0e5c6f8bea49e81f7214142a08a1fd1783bca7b828da43f492c77.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/tables/97eb88e04dd0e5c6f8bea49e81f7214142a08a1fd1783bca7b828da43f492c77.jpg)

![cabbd7c7a80474de42a10888cecf479f5f8fdfff552bc561fa9ee3938662555c.jpg](../nips_results/251_Generalized%20Top-k%20Mallows%20Model%20for%20Ranked%20Choices/tables/cabbd7c7a80474de42a10888cecf479f5f8fdfff552bc561fa9ee3938662555c.jpg)

## AceSearcher: Bootstrapping Reasoning and Search for LLMs via Reinforced Self-Play


### Images

![0af6fe69875dd19b71dece0e513f8342e255292d8a4682ebfab0ac577adb02d0.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/images/0af6fe69875dd19b71dece0e513f8342e255292d8a4682ebfab0ac577adb02d0.jpg)

![5b38df436d81076216ac1cf119781f85b3479e763ba516202ec3477848a00078.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/images/5b38df436d81076216ac1cf119781f85b3479e763ba516202ec3477848a00078.jpg)

![62791c51ca463121ab440475fc60c9120232eedd1f71ac4e84751ecd7c6c388f.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/images/62791c51ca463121ab440475fc60c9120232eedd1f71ac4e84751ecd7c6c388f.jpg)

![6e1a1a37643596eff23c922e373cf748afcefb2297ece5f7fa94289321efa90b.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/images/6e1a1a37643596eff23c922e373cf748afcefb2297ece5f7fa94289321efa90b.jpg)

![6ff4682346807f986a96cb939077d630a934e63f8280462c413dad18a07b24d6.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/images/6ff4682346807f986a96cb939077d630a934e63f8280462c413dad18a07b24d6.jpg)

![c0637694bb398a34463725e87de67a4d40509d0d6a5be78ee40ed5544999e25a.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/images/c0637694bb398a34463725e87de67a4d40509d0d6a5be78ee40ed5544999e25a.jpg)

![ce209da2fa6d0f84da1c78f7735ad86a38512c0e66358dc66bab4f7e5d89dbd7.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/images/ce209da2fa6d0f84da1c78f7735ad86a38512c0e66358dc66bab4f7e5d89dbd7.jpg)

### Tables

![0857141f497d217d33b1c8fe570c86623e59900ea877a3bf36e3ecd229dbe553.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/tables/0857141f497d217d33b1c8fe570c86623e59900ea877a3bf36e3ecd229dbe553.jpg)

![1db05dcf70bbbc60613545dd8735cda98607d28aa76cdcfb8b44fed7676252b5.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/tables/1db05dcf70bbbc60613545dd8735cda98607d28aa76cdcfb8b44fed7676252b5.jpg)

![867ec7c0e27c3051385063a3a7b39cd440abc2b4c9f425327c6cd5f6de494bcb.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/tables/867ec7c0e27c3051385063a3a7b39cd440abc2b4c9f425327c6cd5f6de494bcb.jpg)

![9752e3ef861e349734313535860c4b1c37a9444c2027b356b9ffe36bdf486532.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/tables/9752e3ef861e349734313535860c4b1c37a9444c2027b356b9ffe36bdf486532.jpg)

![a1e3a9d8e3af8592acf54abbc5f16a645a553cdcec7b494999c24e033f7e39ad.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/tables/a1e3a9d8e3af8592acf54abbc5f16a645a553cdcec7b494999c24e033f7e39ad.jpg)

![cfa5459110a7f76e3ab6c128c302e2ddc1ffd6012966fc5143b76340978023c0.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/tables/cfa5459110a7f76e3ab6c128c302e2ddc1ffd6012966fc5143b76340978023c0.jpg)

![d34564bc1906f37707acde45c93dcd7fd5c00901501952d9fb77aa0fc8723a27.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/tables/d34564bc1906f37707acde45c93dcd7fd5c00901501952d9fb77aa0fc8723a27.jpg)

![d9394eb91e502b33970939dc7aa8255129cc37fa265cbc74571b38ab1bb8c00e.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/tables/d9394eb91e502b33970939dc7aa8255129cc37fa265cbc74571b38ab1bb8c00e.jpg)

![f527a1fd35e08330e9171ccba25ba0681620a56857b60f23e386d2d686e33021.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/tables/f527a1fd35e08330e9171ccba25ba0681620a56857b60f23e386d2d686e33021.jpg)

![f68fabdc364baf1f0c9da973ca9cbc3a0c021d338f2cb00c9bdb33132e9752ee.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/tables/f68fabdc364baf1f0c9da973ca9cbc3a0c021d338f2cb00c9bdb33132e9752ee.jpg)

![fc3d9cbe07a73b3889faf459fa9f3cb10528ccc0d38d082fd7c41d24ffe34a2d.jpg](../nips_results/252_AceSearcher_%20Bootstrapping%20Reasoning%20and%20Search%20for%20LLMs%20via%20Reinforced%20Self-Play/tables/fc3d9cbe07a73b3889faf459fa9f3cb10528ccc0d38d082fd7c41d24ffe34a2d.jpg)

## Robust Neural Rendering in the Wild with Asymmetric Dual 3D Gaussian Splatting

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
