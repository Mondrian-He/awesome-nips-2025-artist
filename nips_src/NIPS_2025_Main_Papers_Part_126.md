# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 126 of 130

## 目录 (Table of Contents)

1. [UniGist: Towards General and Hardware-aligned Sequence-level Long Context Compression](#UniGist-Towards-General-and-Hardware-aligned-Sequence-level-Long-Context-Compression)
2. [HCRMP: An LLM-Hinted Contextual Reinforcement Learning Framework for Autonomous Driving](#HCRMP-An-LLM-Hinted-Contextual-Reinforcement-Learning-Framework-for-Autonomous-Driving)
3. [Walking the Tightrope: Autonomous Disentangling Beneficial and Detrimental Drifts in Non-Stationary Custom-Tuning](#Walking-the-Tightrope-Autonomous-Disentangling-Beneficial-and-Detrimental-Drifts-in-Non-Stationary-Custom-Tuning)
4. [Learning Human-Like RL Agents Through Trajectory Optimization With Action Quantization](#Learning-Human-Like-RL-Agents-Through-Trajectory-Optimization-With-Action-Quantization)
5. [A Black-Box Debiasing Framework for Conditional Sampling](#A-Black-Box-Debiasing-Framework-for-Conditional-Sampling)
6. [Adaptive Quantization in Generative Flow Networks for Probabilistic Sequential Prediction](#Adaptive-Quantization-in-Generative-Flow-Networks-for-Probabilistic-Sequential-Prediction)
7. [MGE-LDM: Joint Latent Diffusion for Simultaneous Music Generation and Source Extraction](#MGE-LDM-Joint-Latent-Diffusion-for-Simultaneous-Music-Generation-and-Source-Extraction)
8. [MoGe-2: Accurate Monocular Geometry with Metric Scale and Sharp Details](#MoGe-2-Accurate-Monocular-Geometry-with-Metric-Scale-and-Sharp-Details)
9. [Limitations of Normalization in Attention](#Limitations-of-Normalization-in-Attention)
10. [CALM: Culturally Self-Aware Language Models](#CALM-Culturally-Self-Aware-Language-Models)
11. [Decentralized Dynamic Cooperation of Personalized Models for Federated Continual Learning](#Decentralized-Dynamic-Cooperation-of-Personalized-Models-for-Federated-Continual-Learning)
12. [Diffusion Transformers for Imputation: Statistical Efficiency and Uncertainty Quantification](#Diffusion-Transformers-for-Imputation-Statistical-Efficiency-and-Uncertainty-Quantification)
13. [Memory-Augmented Potential Field Theory: A Framework for Adaptive Control in Non-Convex Domains](#Memory-Augmented-Potential-Field-Theory-A-Framework-for-Adaptive-Control-in-Non-Convex-Domains)
14. [Convergence Theorems for Entropy-Regularized and Distributional Reinforcement Learning](#Convergence-Theorems-for-Entropy-Regularized-and-Distributional-Reinforcement-Learning)
15. [Gene Regulatory Network Inference in the Presence of Selection Bias and Latent Confounders](#Gene-Regulatory-Network-Inference-in-the-Presence-of-Selection-Bias-and-Latent-Confounders)
16. [DISCO: DISCrete nOise for Conditional Control in Text-to-Image Diffusion Models](#DISCO-DISCrete-nOise-for-Conditional-Control-in-Text-to-Image-Diffusion-Models)
17. [Reinforcement Learning with Backtracking Feedback](#Reinforcement-Learning-with-Backtracking-Feedback)
18. [BlurDM: A Blur Diffusion Model for Image Deblurring](#BlurDM-A-Blur-Diffusion-Model-for-Image-Deblurring)
19. [Learning a Cross-Modal Schrödinger Bridge for Visual Domain Generalization](#Learning-a-Cross-Modal-Schrödinger-Bridge-for-Visual-Domain-Generalization)
20. [Audio-Sync Video Generation with Multi-Stream Temporal Control](#Audio-Sync-Video-Generation-with-Multi-Stream-Temporal-Control)
21. [metaTextGrad: Automatically optimizing language model optimizers](#metaTextGrad-Automatically-optimizing-language-model-optimizers)
22. [GeoCAD: Local Geometry-Controllable CAD Generation with Large Language Models](#GeoCAD-Local-Geometry-Controllable-CAD-Generation-with-Large-Language-Models)
23. [Efficient $k$-Sparse Band–Limited Interpolation with Improved Approximation Ratio](#Efficient-k-Sparse-BandLimited-Interpolation-with-Improved-Approximation-Ratio)
24. [TEMPO: Temporal Multi-scale Autoregressive Generation of Protein Conformational Ensembles](#TEMPO-Temporal-Multi-scale-Autoregressive-Generation-of-Protein-Conformational-Ensembles)
25. [Machine Unlearning in 3D Generation: A Perspective-Coherent Acceleration Framework](#Machine-Unlearning-in-3D-Generation-A-Perspective-Coherent-Acceleration-Framework)
26. [Towards a Geometric Understanding of Tensor Learning via the t-Product](#Towards-a-Geometric-Understanding-of-Tensor-Learning-via-the-t-Product)
27. [SurfelSplat: Learning Efficient and Generalizable Gaussian Surfel Representations for Sparse-View Surface Reconstruction](#SurfelSplat-Learning-Efficient-and-Generalizable-Gaussian-Surfel-Representations-for-Sparse-View-Surface-Reconstruction)
28. [Gaze-VLM: Bridging Gaze and VLMs through Attention Regularization for Egocentric Understanding](#Gaze-VLM-Bridging-Gaze-and-VLMs-through-Attention-Regularization-for-Egocentric-Understanding)
29. [Learning CAD Modeling Sequences via Projection and Part Awareness](#Learning-CAD-Modeling-Sequences-via-Projection-and-Part-Awareness)
30. [CF-VLM：CounterFactual Vision-Language Fine-tuning](#CF-VLMCounterFactual-Vision-Language-Fine-tuning)
31. [DyFlow: Dynamic Workflow Framework for Agentic Reasoning](#DyFlow-Dynamic-Workflow-Framework-for-Agentic-Reasoning)
32. [H-SPLID: HSIC-based Saliency Preserving Latent Information Decomposition](#H-SPLID-HSIC-based-Saliency-Preserving-Latent-Information-Decomposition)
33. [TensorRL-QAS: Reinforcement learning with tensor networks for improved quantum architecture search](#TensorRL-QAS-Reinforcement-learning-with-tensor-networks-for-improved-quantum-architecture-search)
34. [Approximately Aligned Decoding](#Approximately-Aligned-Decoding)
35. [ComPO: Preference Alignment via Comparison Oracles](#ComPO-Preference-Alignment-via-Comparison-Oracles)
36. [Sample-Efficient Multi-Round Generative Data Augmentation for Long-Tail Instance Segmentation](#Sample-Efficient-Multi-Round-Generative-Data-Augmentation-for-Long-Tail-Instance-Segmentation)
37. [SwS: Self-aware Weakness-driven Problem Synthesis in Reinforcement Learning for LLM Reasoning](#SwS-Self-aware-Weakness-driven-Problem-Synthesis-in-Reinforcement-Learning-for-LLM-Reasoning)
38. [Latent Chain-of-Thought for Visual Reasoning](#Latent-Chain-of-Thought-for-Visual-Reasoning)
39. [Dual-Space Semantic Synergy Distillation for Continual Learning of Unlabeled Streams](#Dual-Space-Semantic-Synergy-Distillation-for-Continual-Learning-of-Unlabeled-Streams)
40. [CoVoMix2: Advancing Zero-Shot Dialogue Generation with Fully Non-Autoregressive Flow Matching](#CoVoMix2-Advancing-Zero-Shot-Dialogue-Generation-with-Fully-Non-Autoregressive-Flow-Matching)
41. [GASP: Efficient Black-Box Generation of Adversarial Suffixes for Jailbreaking LLMs](#GASP-Efficient-Black-Box-Generation-of-Adversarial-Suffixes-for-Jailbreaking-LLMs)

---


## UniGist: Towards General and Hardware-aligned Sequence-level Long Context Compression

### Images

![10ecc19dd58d28408cbd9552c15eac85dee8fa97e035a8c3391596c8235db733.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/images/10ecc19dd58d28408cbd9552c15eac85dee8fa97e035a8c3391596c8235db733.jpg)

![542f663c587fd27b02f999605a55515c60eea2a7335b20f42605bf3699bfd5fd.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/images/542f663c587fd27b02f999605a55515c60eea2a7335b20f42605bf3699bfd5fd.jpg)

![79f58c9e873d548c7e6e5707a363950efc6f01e9f59704a14247106872873b30.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/images/79f58c9e873d548c7e6e5707a363950efc6f01e9f59704a14247106872873b30.jpg)

![7d8276c2a04a1784c0326771aa6fee81f054067f8ec13c141914e36ad6e1baa5.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/images/7d8276c2a04a1784c0326771aa6fee81f054067f8ec13c141914e36ad6e1baa5.jpg)

![901edcd7fbc08677e43ae9b98a6a7f7524896a6ea9363c6f446da4eda6ac465b.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/images/901edcd7fbc08677e43ae9b98a6a7f7524896a6ea9363c6f446da4eda6ac465b.jpg)

![a6577e6428e474c6ea35b04c09a4af2ef83621b15ea656fe4ebdba8ec5be9ae6.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/images/a6577e6428e474c6ea35b04c09a4af2ef83621b15ea656fe4ebdba8ec5be9ae6.jpg)

### Tables

![40acbde513d9f8f6a64029cafc80802058f165423e63c0a484b1c59f0bb3ef1c.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/tables/40acbde513d9f8f6a64029cafc80802058f165423e63c0a484b1c59f0bb3ef1c.jpg)

![4a808275ffe8dc7067cd9392f20d93283c4f7eafd3b25fe4417512e54468cebc.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/tables/4a808275ffe8dc7067cd9392f20d93283c4f7eafd3b25fe4417512e54468cebc.jpg)

![904fb8337eeaab97cc930b73ed21b30f477a48027abf4b227cdfc68f224cf370.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/tables/904fb8337eeaab97cc930b73ed21b30f477a48027abf4b227cdfc68f224cf370.jpg)

![c668cec103cbb72e8d2cb756185ff77cf3e93d0a800565b8df745d3d244ce00d.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/tables/c668cec103cbb72e8d2cb756185ff77cf3e93d0a800565b8df745d3d244ce00d.jpg)

![d3cb72db1e0c9237d070335f48008e41f6e88e2db530558761a18adc99e14648.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/tables/d3cb72db1e0c9237d070335f48008e41f6e88e2db530558761a18adc99e14648.jpg)

![e9554dad410624e8643eafc00257f9b301ba445660a3b12275d17b92227be580.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/tables/e9554dad410624e8643eafc00257f9b301ba445660a3b12275d17b92227be580.jpg)

![f975a1fb6e8a133fb0b3dfd2cb98f9a9b1cbe63ead250626c6aa2fe7ef15aa1f.jpg](../nips_results/5182_CVGL_%20Causal%20Learning%20and%20Geometric%20Topology/tables/f975a1fb6e8a133fb0b3dfd2cb98f9a9b1cbe63ead250626c6aa2fe7ef15aa1f.jpg)

## UniGist: Towards General and Hardware-aligned Sequence-level Long Context Compression


### Images

![0f5f5da73a902f3daca4a93be7ea5157ea816ddccddaa90fa68e231a26f602a8.jpg](../nips_results/5183_UniGist_%20Towards%20General%20and%20Hardware-aligned%20Sequence-level%20Long%20Context%20Compression/images/0f5f5da73a902f3daca4a93be7ea5157ea816ddccddaa90fa68e231a26f602a8.jpg)

![39c3519650f660f0053cba49916caa0bdc39f216eae501fc7bf314ec2134c326.jpg](../nips_results/5183_UniGist_%20Towards%20General%20and%20Hardware-aligned%20Sequence-level%20Long%20Context%20Compression/images/39c3519650f660f0053cba49916caa0bdc39f216eae501fc7bf314ec2134c326.jpg)

![43517eaa3fce3a1da501b5baf94ff6c97c9684d121b01592d627d2ed9433ecc5.jpg](../nips_results/5183_UniGist_%20Towards%20General%20and%20Hardware-aligned%20Sequence-level%20Long%20Context%20Compression/images/43517eaa3fce3a1da501b5baf94ff6c97c9684d121b01592d627d2ed9433ecc5.jpg)

![69dd9dc61517bbb7387b129e719e4156bc5c5c9ce4f789053f7ea21a532f2eab.jpg](../nips_results/5183_UniGist_%20Towards%20General%20and%20Hardware-aligned%20Sequence-level%20Long%20Context%20Compression/images/69dd9dc61517bbb7387b129e719e4156bc5c5c9ce4f789053f7ea21a532f2eab.jpg)

![70a13e02e5e0c8503ba837052e2af8414fb44769c3bb61a99fd3a59195151231.jpg](../nips_results/5183_UniGist_%20Towards%20General%20and%20Hardware-aligned%20Sequence-level%20Long%20Context%20Compression/images/70a13e02e5e0c8503ba837052e2af8414fb44769c3bb61a99fd3a59195151231.jpg)

![8f6a18bf54ff09a871a8195660f203ee661d244ad39e48cb8859015869d19b25.jpg](../nips_results/5183_UniGist_%20Towards%20General%20and%20Hardware-aligned%20Sequence-level%20Long%20Context%20Compression/images/8f6a18bf54ff09a871a8195660f203ee661d244ad39e48cb8859015869d19b25.jpg)

![fba160b1049ba972ff272dfd9ee8cf538005ff9fbcd97aed33f4cecaf96431c2.jpg](../nips_results/5183_UniGist_%20Towards%20General%20and%20Hardware-aligned%20Sequence-level%20Long%20Context%20Compression/images/fba160b1049ba972ff272dfd9ee8cf538005ff9fbcd97aed33f4cecaf96431c2.jpg)

### Tables

![06e0db1ff891c5460c1407e80ec42ce7f78bb094be09fe89cf3db7532589963e.jpg](../nips_results/5183_UniGist_%20Towards%20General%20and%20Hardware-aligned%20Sequence-level%20Long%20Context%20Compression/tables/06e0db1ff891c5460c1407e80ec42ce7f78bb094be09fe89cf3db7532589963e.jpg)

![6499f3a82c6bf9e5c6b36aafb07c5938529972876329d3830ded7421bd64a769.jpg](../nips_results/5183_UniGist_%20Towards%20General%20and%20Hardware-aligned%20Sequence-level%20Long%20Context%20Compression/tables/6499f3a82c6bf9e5c6b36aafb07c5938529972876329d3830ded7421bd64a769.jpg)

![6d4069ffd182750e4c42b815dfb7726250a9b81859ee3636b82250f03f6c9d1f.jpg](../nips_results/5183_UniGist_%20Towards%20General%20and%20Hardware-aligned%20Sequence-level%20Long%20Context%20Compression/tables/6d4069ffd182750e4c42b815dfb7726250a9b81859ee3636b82250f03f6c9d1f.jpg)

![87a3da7b2d400adf8696ccbc1b871bbadb4a3a4bd58f7b0255ae82c6147aab78.jpg](../nips_results/5183_UniGist_%20Towards%20General%20and%20Hardware-aligned%20Sequence-level%20Long%20Context%20Compression/tables/87a3da7b2d400adf8696ccbc1b871bbadb4a3a4bd58f7b0255ae82c6147aab78.jpg)

## HCRMP: An LLM-Hinted Contextual Reinforcement Learning Framework for Autonomous Driving


### Images

![089e3502818c790fb9621991b869214d9909c6e71331b8580f16dc1bab1053e3.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/089e3502818c790fb9621991b869214d9909c6e71331b8580f16dc1bab1053e3.jpg)

![160e8fe6eadd38a04b98115d8aa15a180e7bf4ef1606f59b6bd60f8d085ae123.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/160e8fe6eadd38a04b98115d8aa15a180e7bf4ef1606f59b6bd60f8d085ae123.jpg)

![220a202eea93eb3e3c977b695b8a93cc72dee5c2c1133c210a9f150b00ae8552.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/220a202eea93eb3e3c977b695b8a93cc72dee5c2c1133c210a9f150b00ae8552.jpg)

![3033ae5c0d6c623d2aa4f41c49a7773a1601d5aefb68e4bbb21ac9cc9d9b5653.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/3033ae5c0d6c623d2aa4f41c49a7773a1601d5aefb68e4bbb21ac9cc9d9b5653.jpg)

![438b3760b8a9a4b5638b7cee9215624ae5f73cb56973384b0bdd0874bd7a23b4.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/438b3760b8a9a4b5638b7cee9215624ae5f73cb56973384b0bdd0874bd7a23b4.jpg)

![4f233291834daa0aab146b4368511b2176d7bedf33663f41f4601e8490d0e4f9.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/4f233291834daa0aab146b4368511b2176d7bedf33663f41f4601e8490d0e4f9.jpg)

![84ef7103ad3ed257a79a6a1aebe68f5fa3026bee597cb0bd23c4d43df52bd93d.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/84ef7103ad3ed257a79a6a1aebe68f5fa3026bee597cb0bd23c4d43df52bd93d.jpg)

![8b02e006c132dd633160a312ce2a557a68cc10bc29e5e82556c42e7d8a38ef6b.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/8b02e006c132dd633160a312ce2a557a68cc10bc29e5e82556c42e7d8a38ef6b.jpg)

![8e7d5cfff0cc49bd385ca132ae672f7b4a7c8914e0ec89fc7c7322dccf831412.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/8e7d5cfff0cc49bd385ca132ae672f7b4a7c8914e0ec89fc7c7322dccf831412.jpg)

![a1288721c2df97a9f9ee7aa5caaab74b0beb8f38b85542030fcf75a6157114d5.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/a1288721c2df97a9f9ee7aa5caaab74b0beb8f38b85542030fcf75a6157114d5.jpg)

![b60944e308fbfe6d2dd092cf3bfc6ec6a8eaa860947da391e0bfb3ef2959af01.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/b60944e308fbfe6d2dd092cf3bfc6ec6a8eaa860947da391e0bfb3ef2959af01.jpg)

![c4cf270d9a3022babec16b188831af5e1672c48723101347cbc13bcb896bdd75.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/c4cf270d9a3022babec16b188831af5e1672c48723101347cbc13bcb896bdd75.jpg)

![f3ccf76d6a2bf5688fb350b48483d8d042d89d762d9ae0e393b61a91e1d2619f.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/images/f3ccf76d6a2bf5688fb350b48483d8d042d89d762d9ae0e393b61a91e1d2619f.jpg)

### Tables

![2e04acd8be5d9ea845125fb22062cf46e2c698fd4a0563ef3fb9f4c747df4052.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/tables/2e04acd8be5d9ea845125fb22062cf46e2c698fd4a0563ef3fb9f4c747df4052.jpg)

![3b8dcb94fc98b7edcf55b37d02daf4d5d73ce582b71898f74124785d198f4e35.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/tables/3b8dcb94fc98b7edcf55b37d02daf4d5d73ce582b71898f74124785d198f4e35.jpg)

![5f6f26002315b4147bdae34070dbf3192a1707d108db488d1d074e55eb46f3c2.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/tables/5f6f26002315b4147bdae34070dbf3192a1707d108db488d1d074e55eb46f3c2.jpg)

![84ea027863248c3d6b497a7388c7c8e17b71aed5c0edc9fce89b67446e476b7f.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/tables/84ea027863248c3d6b497a7388c7c8e17b71aed5c0edc9fce89b67446e476b7f.jpg)

![9a85b4c28c2d6cdd7d40480a521740d6905335907fe13f5be1830c9c73096d8e.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/tables/9a85b4c28c2d6cdd7d40480a521740d6905335907fe13f5be1830c9c73096d8e.jpg)

![ac77ecd59e7fc0fbd749f50ee5e7e9a56e37c5ac0aec8ec9519a79efe69b1c63.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/tables/ac77ecd59e7fc0fbd749f50ee5e7e9a56e37c5ac0aec8ec9519a79efe69b1c63.jpg)

![bc7e2a36832fe860c88c74a01ded768770b58589ad1009ce470795ce4be68910.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/tables/bc7e2a36832fe860c88c74a01ded768770b58589ad1009ce470795ce4be68910.jpg)

![c1a2ae0b587a5c923aca2662d434c354dc6f96424c6d94d1d4aea0b58668cec4.jpg](../nips_results/5184_HCRMP_%20An%20LLM-Hinted%20Contextual%20Reinforcement%20Learning%20Framework%20for%20Autonomous%20Driving/tables/c1a2ae0b587a5c923aca2662d434c354dc6f96424c6d94d1d4aea0b58668cec4.jpg)

## Walking the Tightrope: Autonomous Disentangling Beneficial and Detrimental Drifts in Non-Stationary Custom-Tuning


### Images

![0b6e44a2459b3f1a6f34abc7a080fb12ad06cae72cdd7063d3f7ae6209769f43.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/images/0b6e44a2459b3f1a6f34abc7a080fb12ad06cae72cdd7063d3f7ae6209769f43.jpg)

![2d94de76108147d8c23f559f4a111106ee451d509bb5a8f62d83828748472dab.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/images/2d94de76108147d8c23f559f4a111106ee451d509bb5a8f62d83828748472dab.jpg)

![86d86432758ed4e77a5f9e5189c2c66650dc03aebbac587829c8c1a1322cd005.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/images/86d86432758ed4e77a5f9e5189c2c66650dc03aebbac587829c8c1a1322cd005.jpg)

![b3197fe2f3c2e89bf50ed01283b6c89e3d359686ccf36c3255cc217e350dbcfa.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/images/b3197fe2f3c2e89bf50ed01283b6c89e3d359686ccf36c3255cc217e350dbcfa.jpg)

![d79e88cf2bac28e595785210ed5208cde925713c576fc0fc60c646aa87343dfd.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/images/d79e88cf2bac28e595785210ed5208cde925713c576fc0fc60c646aa87343dfd.jpg)

![d832665074f2be4e478b72acfc370a26f0eeaf78e3ec0cb5b1ded6f09b64c125.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/images/d832665074f2be4e478b72acfc370a26f0eeaf78e3ec0cb5b1ded6f09b64c125.jpg)

### Tables

![42ab2fc9b1f2fd5d3b9744a4d0912431f5541ec247be0feee65a663837e603a7.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/tables/42ab2fc9b1f2fd5d3b9744a4d0912431f5541ec247be0feee65a663837e603a7.jpg)

![9141c3d248e0e3e10e1dc911e6f654f854cef03da2dad278555a5433ff8a9d6d.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/tables/9141c3d248e0e3e10e1dc911e6f654f854cef03da2dad278555a5433ff8a9d6d.jpg)

![c9b3334eaa90b48efd964469caa01b675195e5dd9b8c9b86f65d6bf8e0491e04.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/tables/c9b3334eaa90b48efd964469caa01b675195e5dd9b8c9b86f65d6bf8e0491e04.jpg)

![d82a08cd8f76f11e9e0cd934ab37ab75b95c44b6efb2a7cd75c592216b1abdc6.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/tables/d82a08cd8f76f11e9e0cd934ab37ab75b95c44b6efb2a7cd75c592216b1abdc6.jpg)

![da4b0c39b4e24ede9884b67086f5de776e392e752e1ca73f0630f7b41285fd01.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/tables/da4b0c39b4e24ede9884b67086f5de776e392e752e1ca73f0630f7b41285fd01.jpg)

![f70e09002a693a8fd80e7445d53630979f02ae6d2d52c7b050c931f1f8aec14a.jpg](../nips_results/5185_Walking%20the%20Tightrope_%20Autonomous%20Disentangling%20Beneficial%20and%20Detrimental%20Drifts%20in%20Non-Stationary%20/tables/f70e09002a693a8fd80e7445d53630979f02ae6d2d52c7b050c931f1f8aec14a.jpg)

## Learning Human-Like RL Agents Through Trajectory Optimization With Action Quantization


### Images

![03bff76d03a47b8efd635e64a4e0b79609e129e8a84603cbbad87fa643d049c7.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/03bff76d03a47b8efd635e64a4e0b79609e129e8a84603cbbad87fa643d049c7.jpg)

![284c25c5e87190cf42970ab764a8043e27bbeee9a86352531d79f982f9098780.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/284c25c5e87190cf42970ab764a8043e27bbeee9a86352531d79f982f9098780.jpg)

![4321f6df62e180eaa630697d642642772d06682056b30cd4170802ad2192ea35.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/4321f6df62e180eaa630697d642642772d06682056b30cd4170802ad2192ea35.jpg)

![47ae7d7da12d50d438e427cf3c5e2fcf9a5e4ffcd444dee518421ffb5db398d7.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/47ae7d7da12d50d438e427cf3c5e2fcf9a5e4ffcd444dee518421ffb5db398d7.jpg)

![534589a4f574f65e20cb6e24763a453fbaf3c2923141c700dd8d9aafe9c59cfd.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/534589a4f574f65e20cb6e24763a453fbaf3c2923141c700dd8d9aafe9c59cfd.jpg)

![539a53393cf41e6f312d25817f0736a6d0d7e5cee72c583a6eb5ceb5657c5f0d.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/539a53393cf41e6f312d25817f0736a6d0d7e5cee72c583a6eb5ceb5657c5f0d.jpg)

![645418c8d698a70bb46d7ba33edf9bbd55747746d4b9332c75bcc491f67291ec.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/645418c8d698a70bb46d7ba33edf9bbd55747746d4b9332c75bcc491f67291ec.jpg)

![6c42968391583a47c185aab288693ad3509f5871ca51baa907a0e19ec7078001.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/6c42968391583a47c185aab288693ad3509f5871ca51baa907a0e19ec7078001.jpg)

![9d580b5e4d1605539ef245d25c4f67af780697206337fbc5e926202b9a0e7557.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/9d580b5e4d1605539ef245d25c4f67af780697206337fbc5e926202b9a0e7557.jpg)

![a6b3c9483d591fbc426b32f8bd28d1cb7ab2b90729c26111c67435e3da469a02.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/a6b3c9483d591fbc426b32f8bd28d1cb7ab2b90729c26111c67435e3da469a02.jpg)

![b7de1d22995ea6ede20cae13eebce50a3ffeddb09a007d11282a423f78e0c2c3.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/b7de1d22995ea6ede20cae13eebce50a3ffeddb09a007d11282a423f78e0c2c3.jpg)

![c6d259b54b3a55254544cd188dbefc7d2f5dd16e6643cb7c415b66cad3649601.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/c6d259b54b3a55254544cd188dbefc7d2f5dd16e6643cb7c415b66cad3649601.jpg)

![c890e4609c81833c9e24f4bdff77493f2aeeeb26dc233d4a6c956ca0c59ae7b0.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/c890e4609c81833c9e24f4bdff77493f2aeeeb26dc233d4a6c956ca0c59ae7b0.jpg)

![f516531387f60bb5d233736bae09c3a91c64b7fe84d0124ca2620a690291273d.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/images/f516531387f60bb5d233736bae09c3a91c64b7fe84d0124ca2620a690291273d.jpg)

### Tables

![0a2dbbe549a726b41a46f471c8e5a78cf0ff624231070cc790c8600c2b38b981.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/tables/0a2dbbe549a726b41a46f471c8e5a78cf0ff624231070cc790c8600c2b38b981.jpg)

![2c3e6c9e7140b6f7518e360e25bf0c6a120b8e4949e8c493bef0e85acf39f921.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/tables/2c3e6c9e7140b6f7518e360e25bf0c6a120b8e4949e8c493bef0e85acf39f921.jpg)

![2edb72175faee6c03d28cf943edc0b2b3ad93de420ca8b0cc02af950e09036da.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/tables/2edb72175faee6c03d28cf943edc0b2b3ad93de420ca8b0cc02af950e09036da.jpg)

![7201ff01ec36c97fcc19ac0c7886cccdf365ece76a27d85521637f5c8579b8d5.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/tables/7201ff01ec36c97fcc19ac0c7886cccdf365ece76a27d85521637f5c8579b8d5.jpg)

![9b85931ec1bdf65f6f770b62eec8931cf613872e20a4696a1093cf351304a1cb.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/tables/9b85931ec1bdf65f6f770b62eec8931cf613872e20a4696a1093cf351304a1cb.jpg)

![a42582afeaefd7f25d784e03db7e1920f6ac2a437eda1da3823fc688c34d69d7.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/tables/a42582afeaefd7f25d784e03db7e1920f6ac2a437eda1da3823fc688c34d69d7.jpg)

![fd16c807cd7624a0c44b9ba9f22bd94e49bc3417f28f55617a08ed80ad005091.jpg](../nips_results/5186_Learning%20Human-Like%20RL%20Agents%20Through%20Trajectory%20Optimization%20With%20Action%20Quantization/tables/fd16c807cd7624a0c44b9ba9f22bd94e49bc3417f28f55617a08ed80ad005091.jpg)

## A Black-Box Debiasing Framework for Conditional Sampling


### Images

![82a6a3daf3a267e5ddfab561c195b553e60147d36328383508687b1ebf78d87b.jpg](../nips_results/5187_A%20Black-Box%20Debiasing%20Framework%20for%20Conditional%20Sampling/images/82a6a3daf3a267e5ddfab561c195b553e60147d36328383508687b1ebf78d87b.jpg)

![f66bbd822b472feb4b3d5e7ccb88717afc3b45886fd7b2e26701bc9c9b76a1b5.jpg](../nips_results/5187_A%20Black-Box%20Debiasing%20Framework%20for%20Conditional%20Sampling/images/f66bbd822b472feb4b3d5e7ccb88717afc3b45886fd7b2e26701bc9c9b76a1b5.jpg)

## Adaptive Quantization in Generative Flow Networks for Probabilistic Sequential Prediction


### Images

![05213dec62f0cf69e272d137d9b89b06906f1eef0b7182eba55be0c3f2200718.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/05213dec62f0cf69e272d137d9b89b06906f1eef0b7182eba55be0c3f2200718.jpg)

![08bc2eb71944dcc8731cff2ec4d8f67b6de444b4e0aab06c36527123d8815a33.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/08bc2eb71944dcc8731cff2ec4d8f67b6de444b4e0aab06c36527123d8815a33.jpg)

![0ea282836e9afa9ce2ae45564e81e79a401097749bd531c2d992fc67786eb4d2.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/0ea282836e9afa9ce2ae45564e81e79a401097749bd531c2d992fc67786eb4d2.jpg)

![0ee7b39409d59d7d1b12489ed48796a06201ab8ca5cd04316f240aff67eabdc6.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/0ee7b39409d59d7d1b12489ed48796a06201ab8ca5cd04316f240aff67eabdc6.jpg)

![112bf8b80bd58b1261e380d1db7a3b17866571f2ba159398d4745a488b10e905.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/112bf8b80bd58b1261e380d1db7a3b17866571f2ba159398d4745a488b10e905.jpg)

![17dc514dd826f9327f754ac4bfef990dcb71485d7812a05c2560259db174a2b2.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/17dc514dd826f9327f754ac4bfef990dcb71485d7812a05c2560259db174a2b2.jpg)

![29c91f60730b03b8ba4f16b08c09e562ac2a7094c59fb86d78e4b2144adbe8e4.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/29c91f60730b03b8ba4f16b08c09e562ac2a7094c59fb86d78e4b2144adbe8e4.jpg)

![32acea40d8a868ca3168eb322c17898abd3e338c9c3f4394a26ad31086973652.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/32acea40d8a868ca3168eb322c17898abd3e338c9c3f4394a26ad31086973652.jpg)

![492fe2bce6f048464cc6f7eb028aa042d6a88b7d7feec03424a163c36155b745.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/492fe2bce6f048464cc6f7eb028aa042d6a88b7d7feec03424a163c36155b745.jpg)

![49e926309a08a17c6426409afa76f36a806acef91003306d8e286e0335f22f86.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/49e926309a08a17c6426409afa76f36a806acef91003306d8e286e0335f22f86.jpg)

![4e0cd943798387d77e7c09298aaa167dd702717cba1b952a7938dbac28ab4d5e.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/4e0cd943798387d77e7c09298aaa167dd702717cba1b952a7938dbac28ab4d5e.jpg)

![5085bb23f3986ace9838773376ea7dc3c49e92a75d73575c1e422d232cbd76ee.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/5085bb23f3986ace9838773376ea7dc3c49e92a75d73575c1e422d232cbd76ee.jpg)

![570496295dc9a58b6a5dbc50114df24b176bf7307b12fa47722fdd50bdf87b3e.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/570496295dc9a58b6a5dbc50114df24b176bf7307b12fa47722fdd50bdf87b3e.jpg)

![619a880cf7961e1c1afc55cde7c9e297a2726e34e67df5dde6fb40e58682d6bb.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/619a880cf7961e1c1afc55cde7c9e297a2726e34e67df5dde6fb40e58682d6bb.jpg)

![67c830c4591c913226507ff077990371718d8e7855bf480cbdbfbd0d2f148161.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/67c830c4591c913226507ff077990371718d8e7855bf480cbdbfbd0d2f148161.jpg)

![68b31d6f9c0f81e4fc8e330cb220d4dc4b1199939c93d67448b2262701d5d433.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/68b31d6f9c0f81e4fc8e330cb220d4dc4b1199939c93d67448b2262701d5d433.jpg)

![7037249c1b6f72bd6308d1df38570e5988bc002dad03b56df788d3728ae55883.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/7037249c1b6f72bd6308d1df38570e5988bc002dad03b56df788d3728ae55883.jpg)

![7c56e46db9cf08ad509ce6036bf45ad44a7969e81c8150ca8b66698143d1a88c.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/7c56e46db9cf08ad509ce6036bf45ad44a7969e81c8150ca8b66698143d1a88c.jpg)

![885593fd4b24d71a412ae4fd11d224f012f24fb6806a43d42c081af4f44fb3a4.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/885593fd4b24d71a412ae4fd11d224f012f24fb6806a43d42c081af4f44fb3a4.jpg)

![df0dc25c393a3498be63e904964497af894a2e6da3374aad12b9d98214b26091.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/df0dc25c393a3498be63e904964497af894a2e6da3374aad12b9d98214b26091.jpg)

![e1dca4d6d3d05361db4bc7f5f6cf2909d89a3d55dfefb3cc8e3b9f88020df89f.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/e1dca4d6d3d05361db4bc7f5f6cf2909d89a3d55dfefb3cc8e3b9f88020df89f.jpg)

![ec0c3d1a24b1f7e145d5f5020585c1ddd8b07f876403e43034b5648a4cfaf505.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/ec0c3d1a24b1f7e145d5f5020585c1ddd8b07f876403e43034b5648a4cfaf505.jpg)

![ef10014b920def464cfb1501b04a8dc6e99f7c9926b74c8826e72b003f5e4a3e.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/ef10014b920def464cfb1501b04a8dc6e99f7c9926b74c8826e72b003f5e4a3e.jpg)

![f26d1f55eb3a472f4ce6cb38453d8673b3c251ef4f492535eb0c24f4b2992324.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/f26d1f55eb3a472f4ce6cb38453d8673b3c251ef4f492535eb0c24f4b2992324.jpg)

![f64ed1e7f81b3403130be489dbf61c307134a0178cb0a58fe315901c4f7a8d7c.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/images/f64ed1e7f81b3403130be489dbf61c307134a0178cb0a58fe315901c4f7a8d7c.jpg)

### Tables

![875e49db3895289966085a30f1ff5993ef873bb12556ecfd20374aff280db542.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/tables/875e49db3895289966085a30f1ff5993ef873bb12556ecfd20374aff280db542.jpg)

![bd32dda5e42b7ede9a9e9a926e22913b26cf41cfe350a2a2100b9d2b6081c181.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/tables/bd32dda5e42b7ede9a9e9a926e22913b26cf41cfe350a2a2100b9d2b6081c181.jpg)

![ce4ec3342a86d7a06cc4122c788083d35c7a72b312e3f19ba3d91bc1a0332d39.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/tables/ce4ec3342a86d7a06cc4122c788083d35c7a72b312e3f19ba3d91bc1a0332d39.jpg)

![d50457e7023006c5b0089dbfe58c4d0a86d966ab1b5c70843b45cf32656b4f9b.jpg](../nips_results/5188_Adaptive%20Quantization%20in%20Generative%20Flow%20Networks%20for%20Probabilistic%20Sequential%20Prediction/tables/d50457e7023006c5b0089dbfe58c4d0a86d966ab1b5c70843b45cf32656b4f9b.jpg)

## MGE-LDM: Joint Latent Diffusion for Simultaneous Music Generation and Source Extraction


### Images

![339094c957eb9651c7ea62549b64ad04e2e7de4b1623da718de64e22a39c7fcd.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/images/339094c957eb9651c7ea62549b64ad04e2e7de4b1623da718de64e22a39c7fcd.jpg)

![750bf61e2912046b87513f8524c74cd58e4e5f8ec7eea9705e6cf5ef52fbd45f.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/images/750bf61e2912046b87513f8524c74cd58e4e5f8ec7eea9705e6cf5ef52fbd45f.jpg)

![b3b9d00ef040914f8d4374362956c128878ce5046fc04d2f7d54b400c5213153.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/images/b3b9d00ef040914f8d4374362956c128878ce5046fc04d2f7d54b400c5213153.jpg)

![db34ec7a82ac7c70a2a050bfca95bf2315cdda4c18466bdd27b99106319d3f80.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/images/db34ec7a82ac7c70a2a050bfca95bf2315cdda4c18466bdd27b99106319d3f80.jpg)

### Tables

![05f2d185d2b2ffd99b34fe8fb1ed20a8a98eb65baab4fe0cae852ddb9c54efe4.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/tables/05f2d185d2b2ffd99b34fe8fb1ed20a8a98eb65baab4fe0cae852ddb9c54efe4.jpg)

![2c69abfecba3345117a66ef3e81418ba5a537fe54c877bb1d2df931cdddedee1.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/tables/2c69abfecba3345117a66ef3e81418ba5a537fe54c877bb1d2df931cdddedee1.jpg)

![442c4a456021798b081d141ac83502a4978b4e07b7232c50a3acb270ca1bb051.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/tables/442c4a456021798b081d141ac83502a4978b4e07b7232c50a3acb270ca1bb051.jpg)

![4a82f96c74a21dd9356c0419a01bf060122bab8f6b7094134d4062f4719e48b1.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/tables/4a82f96c74a21dd9356c0419a01bf060122bab8f6b7094134d4062f4719e48b1.jpg)

![576bdc9258174700ccd8b2d7e2bf2bfc89b68aea59bfeaca0fd3d4834e38e4e3.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/tables/576bdc9258174700ccd8b2d7e2bf2bfc89b68aea59bfeaca0fd3d4834e38e4e3.jpg)

![5c9142e4cef3395ed8e4c4cd0fb30d89818263c98c64209c85339b6ee3e7d9b8.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/tables/5c9142e4cef3395ed8e4c4cd0fb30d89818263c98c64209c85339b6ee3e7d9b8.jpg)

![73847da018a553569c5e2a7cfca617a6f5cdf7e279873046c47907f44bcf378f.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/tables/73847da018a553569c5e2a7cfca617a6f5cdf7e279873046c47907f44bcf378f.jpg)

![96f43043ced813bd5c9b861d1e769792f55bda3064d3771463a8c23dd251c6b2.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/tables/96f43043ced813bd5c9b861d1e769792f55bda3064d3771463a8c23dd251c6b2.jpg)

![ccad17cc5300cfab3066005fd889dd41f306c2e85c9de6db9db9af20cb3c6b0a.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/tables/ccad17cc5300cfab3066005fd889dd41f306c2e85c9de6db9db9af20cb3c6b0a.jpg)

![e3533d53cb42e7213acea2564738d1a6b05668f1d6a3982738f67e0f2cb0b0d8.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/tables/e3533d53cb42e7213acea2564738d1a6b05668f1d6a3982738f67e0f2cb0b0d8.jpg)

![ef295f713f190d4ff8fb645d7fa4544c3a1a40c86747ddfaff39afea0ff8a824.jpg](../nips_results/5189_MGE-LDM_%20Joint%20Latent%20Diffusion%20for%20Simultaneous%20Music%20Generation%20and%20Source%20Extraction/tables/ef295f713f190d4ff8fb645d7fa4544c3a1a40c86747ddfaff39afea0ff8a824.jpg)

## MoGe-2: Accurate Monocular Geometry with Metric Scale and Sharp Details


### Images

![15410f2ae98342539793809cc78303d8cfb827f505b127f7103b677349e20347.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/15410f2ae98342539793809cc78303d8cfb827f505b127f7103b677349e20347.jpg)

![173f1fba3f1c26fe2dd89ffcd89c2905ef8737013501b47be2499b8d7102b0aa.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/173f1fba3f1c26fe2dd89ffcd89c2905ef8737013501b47be2499b8d7102b0aa.jpg)

![3306f92eedbc835a72f51a403ddddf6ed24f5989c437d2343e5b079c45dd2724.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/3306f92eedbc835a72f51a403ddddf6ed24f5989c437d2343e5b079c45dd2724.jpg)

![3a5e7164620c3b1a99c4e3aafc4d01778a6829f3d9daf8571aa51b8f975a6acd.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/3a5e7164620c3b1a99c4e3aafc4d01778a6829f3d9daf8571aa51b8f975a6acd.jpg)

![3fdc0115cd1aecb4761212de60e9ec63a2651a2f6569aedd77a11904cc5aabec.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/3fdc0115cd1aecb4761212de60e9ec63a2651a2f6569aedd77a11904cc5aabec.jpg)

![7491cf212b634bdc911f1005de35376a3d04c97a348f2805dbc2413f617d963b.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/7491cf212b634bdc911f1005de35376a3d04c97a348f2805dbc2413f617d963b.jpg)

![9fda1a5e496fe00e0680e961d529949344f08c84b5185c7f198e6c8e608ea83b.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/9fda1a5e496fe00e0680e961d529949344f08c84b5185c7f198e6c8e608ea83b.jpg)

![a19638933ff53f659477e60e26f96d53c5bb0b45737a2cdb68a9b7e1d08d243a.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/a19638933ff53f659477e60e26f96d53c5bb0b45737a2cdb68a9b7e1d08d243a.jpg)

![a6d10dbd09088f2f02c638cacd5fe32e4437efe943648200bf18b7273b917b70.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/a6d10dbd09088f2f02c638cacd5fe32e4437efe943648200bf18b7273b917b70.jpg)

![a87884d4ecc8d1ca5c4cbfb542b7feb5facf98e7b60bb806d7303ab4414a1dec.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/a87884d4ecc8d1ca5c4cbfb542b7feb5facf98e7b60bb806d7303ab4414a1dec.jpg)

![aa6cd2b4f9758139096bbc133fbc5150851396728ecad579f6e2408a89c9247c.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/aa6cd2b4f9758139096bbc133fbc5150851396728ecad579f6e2408a89c9247c.jpg)

![e83d1f3fb2a4ee00a2095df1faf4c99c95a0151ca3641c6dda94fe3b8779cd2d.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/e83d1f3fb2a4ee00a2095df1faf4c99c95a0151ca3641c6dda94fe3b8779cd2d.jpg)

![f8de0a7757c736055c7716de2d4e469b6474b4fdc231b19376edb540482f3ae5.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/images/f8de0a7757c736055c7716de2d4e469b6474b4fdc231b19376edb540482f3ae5.jpg)

### Tables

![43ede356d733249d8a0d677d0071ae6c4cfb1b94f315ed2dc3238d61b9891567.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/tables/43ede356d733249d8a0d677d0071ae6c4cfb1b94f315ed2dc3238d61b9891567.jpg)

![608587962cb20fb40a7f39f826a32286c968cb2ce867b8ec44a28c212b6d3a55.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/tables/608587962cb20fb40a7f39f826a32286c968cb2ce867b8ec44a28c212b6d3a55.jpg)

![7102b365d333cbc24b110fc4961158ec46952fc1cbfcec9d58fc6c9ef92c50ea.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/tables/7102b365d333cbc24b110fc4961158ec46952fc1cbfcec9d58fc6c9ef92c50ea.jpg)

![768c78dc2bb27e190dc8c41ea26b5f8b5dcf3c758aaa9855eabb9c43ae4f6be1.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/tables/768c78dc2bb27e190dc8c41ea26b5f8b5dcf3c758aaa9855eabb9c43ae4f6be1.jpg)

![ab33fb86c62dcd5086cd6375f10dd06926fb0b551a84ee946a000b4ddaaa78ba.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/tables/ab33fb86c62dcd5086cd6375f10dd06926fb0b551a84ee946a000b4ddaaa78ba.jpg)

![b58e7bbbb575ed6587acc4d3a4516ca921a35c20e69596a68f6d101c7f029cfe.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/tables/b58e7bbbb575ed6587acc4d3a4516ca921a35c20e69596a68f6d101c7f029cfe.jpg)

![bd09528ff19eee2ba28857c4046c56f4f249a9963d0f78ab72039c9503083589.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/tables/bd09528ff19eee2ba28857c4046c56f4f249a9963d0f78ab72039c9503083589.jpg)

![eedafed075466ba2fcaa7a9e516cd496e656a787fd1bb482a1a4a26298ac641b.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/tables/eedafed075466ba2fcaa7a9e516cd496e656a787fd1bb482a1a4a26298ac641b.jpg)

![ff0ed092751c3b023f4b90cb8ba9ce04c0f86acac333918f699d852724e42bc5.jpg](../nips_results/5190_MoGe-2_%20Accurate%20Monocular%20Geometry%20with%20Metric%20Scale%20and%20Sharp%20Details/tables/ff0ed092751c3b023f4b90cb8ba9ce04c0f86acac333918f699d852724e42bc5.jpg)

## Limitations of Normalization in Attention


### Images

![48820e9a74eaac6825563bec88a2bdcb707987c89aed32c1a255ad3b4fe4bb54.jpg](../nips_results/5191_Limitations%20of%20Normalization%20in%20Attention/images/48820e9a74eaac6825563bec88a2bdcb707987c89aed32c1a255ad3b4fe4bb54.jpg)

![533dbd2331e0834412d220cdcd1c5d3a1e2bd00c94905d02674f7bbf993b069c.jpg](../nips_results/5191_Limitations%20of%20Normalization%20in%20Attention/images/533dbd2331e0834412d220cdcd1c5d3a1e2bd00c94905d02674f7bbf993b069c.jpg)

![c30e98fa730104987cbdf96a71d92e5c8248874b8556d2164ec0b60bd14322f2.jpg](../nips_results/5191_Limitations%20of%20Normalization%20in%20Attention/images/c30e98fa730104987cbdf96a71d92e5c8248874b8556d2164ec0b60bd14322f2.jpg)

![df39748ccd2f09f403c163a52aeb265085914132b4e09981ba24c042a8dbead6.jpg](../nips_results/5191_Limitations%20of%20Normalization%20in%20Attention/images/df39748ccd2f09f403c163a52aeb265085914132b4e09981ba24c042a8dbead6.jpg)

## CALM: Culturally Self-Aware Language Models


### Images

![151f0b4b58f222b0515a57b785bcd75e0c44680251c9a9d990925bbfde260c65.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/images/151f0b4b58f222b0515a57b785bcd75e0c44680251c9a9d990925bbfde260c65.jpg)

![2125e25118671bc2c9f15859a8862b3652c853d6941d8ae9b1985f2793b56243.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/images/2125e25118671bc2c9f15859a8862b3652c853d6941d8ae9b1985f2793b56243.jpg)

![3f0b484094f7e3e0340e646b5a7d83a603839eea9e6f5a21ccfd11e6740ccb13.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/images/3f0b484094f7e3e0340e646b5a7d83a603839eea9e6f5a21ccfd11e6740ccb13.jpg)

![88c28cef805785f1c84957792ad1348a30f006eadef2c3fa9530729ed2d9c5ee.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/images/88c28cef805785f1c84957792ad1348a30f006eadef2c3fa9530729ed2d9c5ee.jpg)

![acb4dcd095f8af75c8a1342228c28783ed96d88ce7d214cfcf37d0cb62fcbe21.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/images/acb4dcd095f8af75c8a1342228c28783ed96d88ce7d214cfcf37d0cb62fcbe21.jpg)

![c6f43c7a58b726f28fc07a16a43fc19b2d119bb9cd03286356ac570db369d138.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/images/c6f43c7a58b726f28fc07a16a43fc19b2d119bb9cd03286356ac570db369d138.jpg)

![de61e112fae021059941153838a4c305de5f97366da48d686fb28061a3d2dcdd.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/images/de61e112fae021059941153838a4c305de5f97366da48d686fb28061a3d2dcdd.jpg)

![e248bdf73b1f57a98bbc3b4fb9481c3973e1792d1b7507aeba50a37cea25225c.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/images/e248bdf73b1f57a98bbc3b4fb9481c3973e1792d1b7507aeba50a37cea25225c.jpg)

### Tables

![184c5603a1bf7fad6e1c31138d118826401194ea3471abf0685d8b670c116397.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/184c5603a1bf7fad6e1c31138d118826401194ea3471abf0685d8b670c116397.jpg)

![1f953071dd05ac341a9494e30b1442ef4ae1f07c9b3f158ab42196d6b39f51c3.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/1f953071dd05ac341a9494e30b1442ef4ae1f07c9b3f158ab42196d6b39f51c3.jpg)

![396a359cd61652dcc79b75fd5b11077671e1d7db1b487e5985e8f2cc453ea1f3.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/396a359cd61652dcc79b75fd5b11077671e1d7db1b487e5985e8f2cc453ea1f3.jpg)

![3bb8e3fdf0c1690c9cf7c556de65f0b51814dbbf95ed03e4312ccd05f20a249f.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/3bb8e3fdf0c1690c9cf7c556de65f0b51814dbbf95ed03e4312ccd05f20a249f.jpg)

![4257a2dfee4a097bb2d6aca3d02626017d6bd0682f6bbc7ffd4ee695d7b14372.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/4257a2dfee4a097bb2d6aca3d02626017d6bd0682f6bbc7ffd4ee695d7b14372.jpg)

![446175df2fdbff25d2f2db90af27efe24b3d9a311bd24ae2465467a4ef447ca0.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/446175df2fdbff25d2f2db90af27efe24b3d9a311bd24ae2465467a4ef447ca0.jpg)

![4b988979ad54539042ffd648ee23998d0d8d855a20a4ac997432c693233e2b8a.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/4b988979ad54539042ffd648ee23998d0d8d855a20a4ac997432c693233e2b8a.jpg)

![77a140c0bcbcbb36aa7b7eaaf5e06286b05ad9de60f22955fb676bac97961837.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/77a140c0bcbcbb36aa7b7eaaf5e06286b05ad9de60f22955fb676bac97961837.jpg)

![9b18b8fc93f5512727161b1f8785f54b823cc00337b22b78e4da0ef722d95387.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/9b18b8fc93f5512727161b1f8785f54b823cc00337b22b78e4da0ef722d95387.jpg)

![c9a8315530b6432b7e73a8f30768cd1ef982865db57cbd4456f7d945160e9b2e.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/c9a8315530b6432b7e73a8f30768cd1ef982865db57cbd4456f7d945160e9b2e.jpg)

![d4836a1476db418edcd3466eb48f20d8d83e2a6a6e7e1aa3b64b9712d5f9f40d.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/d4836a1476db418edcd3466eb48f20d8d83e2a6a6e7e1aa3b64b9712d5f9f40d.jpg)

![ee279b4bd82317abff038933657bc70fe7486f19f132bf6a9cd7a363bf7c9709.jpg](../nips_results/5192_CALM_%20Culturally%20Self-Aware%20Language%20Models/tables/ee279b4bd82317abff038933657bc70fe7486f19f132bf6a9cd7a363bf7c9709.jpg)

## Decentralized Dynamic Cooperation of Personalized Models for Federated Continual Learning


### Images

![22e80809faa63074db14cb83a63e17063484fa7a0ab96c0551f5d8becedb4b91.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/images/22e80809faa63074db14cb83a63e17063484fa7a0ab96c0551f5d8becedb4b91.jpg)

![338460065882208896e6383fa6fca9e93da1954e87f3f6a6cf505c21f928d587.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/images/338460065882208896e6383fa6fca9e93da1954e87f3f6a6cf505c21f928d587.jpg)

![729924d37453548ca3476e2f456e61686d945b68586d915c652a51356c94f644.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/images/729924d37453548ca3476e2f456e61686d945b68586d915c652a51356c94f644.jpg)

![950fe89672b08b0c7dff7db9e8b2dddefffcc9f2df0fc65ec2cee2812dd55668.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/images/950fe89672b08b0c7dff7db9e8b2dddefffcc9f2df0fc65ec2cee2812dd55668.jpg)

![a13620392719ae0c8344982127d927e23ff2e2de07e4bb117016f3d4a5529250.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/images/a13620392719ae0c8344982127d927e23ff2e2de07e4bb117016f3d4a5529250.jpg)

![ab0999c4b21441431f652acce760d0db2298dfc4a33b307845d0f5b35d765e26.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/images/ab0999c4b21441431f652acce760d0db2298dfc4a33b307845d0f5b35d765e26.jpg)

![c11b0fb7bac47666484b7f2e92d913220fe89affb0863474c03cc905a869cd19.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/images/c11b0fb7bac47666484b7f2e92d913220fe89affb0863474c03cc905a869cd19.jpg)

![f3ee897d151b80070e6a6299078ab68238f4c4ff68d0b7fc304574b47f1fdab2.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/images/f3ee897d151b80070e6a6299078ab68238f4c4ff68d0b7fc304574b47f1fdab2.jpg)

### Tables

![1ae4dfa881e54e267940985c57d71d0324bf2eef24423f42b398cb3bfbc45540.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/tables/1ae4dfa881e54e267940985c57d71d0324bf2eef24423f42b398cb3bfbc45540.jpg)

![3346a5479b5785b60891718511804ca7cdf0cc15f0f91e77de85561e88186d3c.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/tables/3346a5479b5785b60891718511804ca7cdf0cc15f0f91e77de85561e88186d3c.jpg)

![45fe5218d3b5f24a1c5adc9d1e1c0f5d1cdf88272332dddf11e6cea3dffdab66.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/tables/45fe5218d3b5f24a1c5adc9d1e1c0f5d1cdf88272332dddf11e6cea3dffdab66.jpg)

![8c2989000b7f4e9a1b1c3f331e71ee471d6562f780996234cf72025099509c0b.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/tables/8c2989000b7f4e9a1b1c3f331e71ee471d6562f780996234cf72025099509c0b.jpg)

![9d0355045a0325cd9b751703b8ba38d03742f784c0b652188682be0c81bbfd45.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/tables/9d0355045a0325cd9b751703b8ba38d03742f784c0b652188682be0c81bbfd45.jpg)

![a17e0406cf13228547f6db49f5450496b232c4a9a13963a802ea1364a997ef73.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/tables/a17e0406cf13228547f6db49f5450496b232c4a9a13963a802ea1364a997ef73.jpg)

![abe0ff9b958284b72b3d46321ca89c29b2b52247e044c0b5b1321b23610b8005.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/tables/abe0ff9b958284b72b3d46321ca89c29b2b52247e044c0b5b1321b23610b8005.jpg)

![e2afd6dccef4d7ac48d3ccba35642fe4c1d8f07e07737b88995bf055879ca536.jpg](../nips_results/5193_Decentralized%20Dynamic%20Cooperation%20of%20Personalized%20Models%20for%20Federated%20Continual%20Learning/tables/e2afd6dccef4d7ac48d3ccba35642fe4c1d8f07e07737b88995bf055879ca536.jpg)

## Diffusion Transformers for Imputation: Statistical Efficiency and Uncertainty Quantification


### Images

![4e838d4f9c9fb474f295a807cabd36d6a5e040e2a74aec0c5df030f4bb6ecf3f.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/images/4e838d4f9c9fb474f295a807cabd36d6a5e040e2a74aec0c5df030f4bb6ecf3f.jpg)

![62dd7ac5cbbfea283e2baf2f1d152ad2a03310e6a243238b15a8dd060955a06b.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/images/62dd7ac5cbbfea283e2baf2f1d152ad2a03310e6a243238b15a8dd060955a06b.jpg)

![6688ec20a209efa32155537ec6d3a02ff1f0beaa7f3881e8351ec3fb6bcda2b4.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/images/6688ec20a209efa32155537ec6d3a02ff1f0beaa7f3881e8351ec3fb6bcda2b4.jpg)

![db06995e1884924f1a986d59677c7f6b89c08a3eb2b8d3b947400dc8938ca721.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/images/db06995e1884924f1a986d59677c7f6b89c08a3eb2b8d3b947400dc8938ca721.jpg)

### Tables

![033e0beb712c16f7689f12d4ef20c7a53ab73871f1f79b82dfc325c756e3bdca.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/tables/033e0beb712c16f7689f12d4ef20c7a53ab73871f1f79b82dfc325c756e3bdca.jpg)

![844b67c2944f19102aae847ff259add464d2888fc5f149affce1e9d5a40ef793.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/tables/844b67c2944f19102aae847ff259add464d2888fc5f149affce1e9d5a40ef793.jpg)

![848bdb252a512007cdef6e8cef0d9c27de8a4736daeea3a7825eb51895024f00.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/tables/848bdb252a512007cdef6e8cef0d9c27de8a4736daeea3a7825eb51895024f00.jpg)

![8e8702b261205f42a439ac4f4ac3d15514f828d316b2152e948e363ace4e0157.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/tables/8e8702b261205f42a439ac4f4ac3d15514f828d316b2152e948e363ace4e0157.jpg)

![9e6783c6438f02c035a117151bfabb43744ac5d7fd4f099ec793e2822127bf6e.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/tables/9e6783c6438f02c035a117151bfabb43744ac5d7fd4f099ec793e2822127bf6e.jpg)

![bc203abd2abbf65ccdb468927b60b1abce1a2a649cbaa2b0f79ce056e5d292ed.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/tables/bc203abd2abbf65ccdb468927b60b1abce1a2a649cbaa2b0f79ce056e5d292ed.jpg)

![c10efb44a1d86d65656ac5dd034b867cd4f2dcff50ee1d8b1178bd456b63bfe5.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/tables/c10efb44a1d86d65656ac5dd034b867cd4f2dcff50ee1d8b1178bd456b63bfe5.jpg)

![d667838e93b579d31201faf18ee4a539c8c215cef6a01468de4322c12f6ff187.jpg](../nips_results/5194_Diffusion%20Transformers%20for%20Imputation_%20Statistical%20Efficiency%20and%20Uncertainty%20Quantification/tables/d667838e93b579d31201faf18ee4a539c8c215cef6a01468de4322c12f6ff187.jpg)

## Memory-Augmented Potential Field Theory: A Framework for Adaptive Control in Non-Convex Domains


### Images

![1a0ee21de781509adcb21e693dc8a13df90d0950d67fb9102ff0fa48089320fe.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/images/1a0ee21de781509adcb21e693dc8a13df90d0950d67fb9102ff0fa48089320fe.jpg)

![2b8afcc5a4769460a786d200f6b7558c86d8323e7314453626351b59cdf7eb21.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/images/2b8afcc5a4769460a786d200f6b7558c86d8323e7314453626351b59cdf7eb21.jpg)

![626b9339e653860fae3f099121d10475be3491378e85dfc03a3db67dba852517.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/images/626b9339e653860fae3f099121d10475be3491378e85dfc03a3db67dba852517.jpg)

![99833b8552fa798f49fa8c5c5205de30ef3930b10a3644cb3a8975b17e3a49cf.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/images/99833b8552fa798f49fa8c5c5205de30ef3930b10a3644cb3a8975b17e3a49cf.jpg)

![b2edbdec502d414521fa300213d19e8e23075c0b1fceee1f2819a43053bb60b0.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/images/b2edbdec502d414521fa300213d19e8e23075c0b1fceee1f2819a43053bb60b0.jpg)

![cf166f3529a342d7f7df063808e8e5e035f9115701ed15a77b05b06ab09ef65a.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/images/cf166f3529a342d7f7df063808e8e5e035f9115701ed15a77b05b06ab09ef65a.jpg)

![df75390dcb77120eebe66f26b79b2575a5bfae01e4ac54de0d44d8eb40b23bf3.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/images/df75390dcb77120eebe66f26b79b2575a5bfae01e4ac54de0d44d8eb40b23bf3.jpg)

### Tables

![13c0351bd76ef706a4e9dc3c0f6ee0814911ea25bb514dc052b71f4c4881190c.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/13c0351bd76ef706a4e9dc3c0f6ee0814911ea25bb514dc052b71f4c4881190c.jpg)

![1a118a01fa2b89781d86311890ad9dc9689c9acd6a15763bc4875c7cfae1408a.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/1a118a01fa2b89781d86311890ad9dc9689c9acd6a15763bc4875c7cfae1408a.jpg)

![236842f6101431ee6939cb87a298d9e0dd4a0d17ab8283b3b2f63993c67ada03.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/236842f6101431ee6939cb87a298d9e0dd4a0d17ab8283b3b2f63993c67ada03.jpg)

![3aa0f3b12bddabfe029d23d20542e497538c4d83d15c69c36d4240a0f3e0b148.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/3aa0f3b12bddabfe029d23d20542e497538c4d83d15c69c36d4240a0f3e0b148.jpg)

![53464e9ffc2f2c3908e835bc6375aa8c874bbc90af84dadd9af1c502d7ae19dd.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/53464e9ffc2f2c3908e835bc6375aa8c874bbc90af84dadd9af1c502d7ae19dd.jpg)

![572c2be4d5e21e4d2f9bd0cc56b7b91f831500f88089b0af97a46d81dfc744cf.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/572c2be4d5e21e4d2f9bd0cc56b7b91f831500f88089b0af97a46d81dfc744cf.jpg)

![5794bbe3e61a7eda03ab8972ff638712f4383f6d8e5068a6c0707ea4824d46a8.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/5794bbe3e61a7eda03ab8972ff638712f4383f6d8e5068a6c0707ea4824d46a8.jpg)

![5d8d34e3fe495988e8b42690381a819e8c0c756c71fcd4a226228360f6fd4755.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/5d8d34e3fe495988e8b42690381a819e8c0c756c71fcd4a226228360f6fd4755.jpg)

![62efb300365da96e74bc31986ff7fd2fb27ff6e5631aa96b6f58ecfecac2608c.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/62efb300365da96e74bc31986ff7fd2fb27ff6e5631aa96b6f58ecfecac2608c.jpg)

![795c41a7f938d90fc5c64b5fbab781f68250b36c92e12c5196a5e6303b8e56eb.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/795c41a7f938d90fc5c64b5fbab781f68250b36c92e12c5196a5e6303b8e56eb.jpg)

![9ddf04ea846e1930a8c45a601569b91ac3db5b584a7fb0db72d0fe0d4d52efc2.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/9ddf04ea846e1930a8c45a601569b91ac3db5b584a7fb0db72d0fe0d4d52efc2.jpg)

![b878c651ad17f5b3f2e1f916b6a57268a56148b9345f2b8e48f72435d8e47e78.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/b878c651ad17f5b3f2e1f916b6a57268a56148b9345f2b8e48f72435d8e47e78.jpg)

![e0d4a3603b5194c51f6b74d5ee18accf1f4f23d74ab8b474d0af731e8481b0bf.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/e0d4a3603b5194c51f6b74d5ee18accf1f4f23d74ab8b474d0af731e8481b0bf.jpg)

![e4dac4c95517afda0c3f50c173351b4c97b3ed070fb9ca0dd94412d77bcac252.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/e4dac4c95517afda0c3f50c173351b4c97b3ed070fb9ca0dd94412d77bcac252.jpg)

![f449977e065d532896557bcf5704846fd70ccfe232b4d2469429db332fd04d22.jpg](../nips_results/5195_Memory-Augmented%20Potential%20Field%20Theory_%20A%20Framework%20for%20Adaptive%20Control%20in%20Non-Convex%20Domains/tables/f449977e065d532896557bcf5704846fd70ccfe232b4d2469429db332fd04d22.jpg)

## Convergence Theorems for Entropy-Regularized and Distributional Reinforcement Learning


### Images

![2e3764bcfe8ccddc9b4b8502ca31cc12b072455af97957c0b91f1b23e39e2c2a.jpg](../nips_results/5196_Convergence%20Theorems%20for%20Entropy-Regularized%20and%20Distributional%20Reinforcement%20Learning/images/2e3764bcfe8ccddc9b4b8502ca31cc12b072455af97957c0b91f1b23e39e2c2a.jpg)

![a3fb3d6b6ab7118f8297d5cfad9312a75efdebd7983572ffa9096d61b2ff0da7.jpg](../nips_results/5196_Convergence%20Theorems%20for%20Entropy-Regularized%20and%20Distributional%20Reinforcement%20Learning/images/a3fb3d6b6ab7118f8297d5cfad9312a75efdebd7983572ffa9096d61b2ff0da7.jpg)

![b661126eb98ffc1cb6b2d61a8596e86a46b1d605306e9a74f594aaf0cb39741c.jpg](../nips_results/5196_Convergence%20Theorems%20for%20Entropy-Regularized%20and%20Distributional%20Reinforcement%20Learning/images/b661126eb98ffc1cb6b2d61a8596e86a46b1d605306e9a74f594aaf0cb39741c.jpg)

![d6b6292f38dc5f27dd881340fac9ca7f02ad2075dcfabc5b9edd10a6f2c6b36b.jpg](../nips_results/5196_Convergence%20Theorems%20for%20Entropy-Regularized%20and%20Distributional%20Reinforcement%20Learning/images/d6b6292f38dc5f27dd881340fac9ca7f02ad2075dcfabc5b9edd10a6f2c6b36b.jpg)

![dc6c0fd8e5130719e5e1a506bff6076857e5440646e3613e1880741a68da6b84.jpg](../nips_results/5196_Convergence%20Theorems%20for%20Entropy-Regularized%20and%20Distributional%20Reinforcement%20Learning/images/dc6c0fd8e5130719e5e1a506bff6076857e5440646e3613e1880741a68da6b84.jpg)

## Gene Regulatory Network Inference in the Presence of Selection Bias and Latent Confounders


### Images

![15213f5be9534db69ca656512211d55621e16c5b9a19f68c136ce89d268c9ea8.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/15213f5be9534db69ca656512211d55621e16c5b9a19f68c136ce89d268c9ea8.jpg)

![25279516697a03aaca653492d13c3da9cec2d98990eff6687e51e6768b9e69df.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/25279516697a03aaca653492d13c3da9cec2d98990eff6687e51e6768b9e69df.jpg)

![40f9329fd75040cd87b7b144878b1fac188d1f8de7a596d5e163dc4a3f0e9900.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/40f9329fd75040cd87b7b144878b1fac188d1f8de7a596d5e163dc4a3f0e9900.jpg)

![418e98fe64ca1f1db226d754c45a086736d02e9e850dd1cde607e0052566519f.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/418e98fe64ca1f1db226d754c45a086736d02e9e850dd1cde607e0052566519f.jpg)

![71d1f361fb56f8b82fc606e8306154f97431d9403d441313f8e6e48c87635144.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/71d1f361fb56f8b82fc606e8306154f97431d9403d441313f8e6e48c87635144.jpg)

![785c58ce305f92534a3963d1314633defb6f4996b8a8f1c87d20cf61c0e7ad2f.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/785c58ce305f92534a3963d1314633defb6f4996b8a8f1c87d20cf61c0e7ad2f.jpg)

![811700b25b3de8553c9b08b501504c444cfe626736604f736a3b793bf1f8931c.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/811700b25b3de8553c9b08b501504c444cfe626736604f736a3b793bf1f8931c.jpg)

![90783dd9f881b06c31b820ca93948dbdbf25a7fa7af2aceec2dfccb2fb69f978.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/90783dd9f881b06c31b820ca93948dbdbf25a7fa7af2aceec2dfccb2fb69f978.jpg)

![b0dff870c0715e3fca0e213cc861d5018ab905874855e22bb6f7f69784506e90.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/b0dff870c0715e3fca0e213cc861d5018ab905874855e22bb6f7f69784506e90.jpg)

![cf3c6551bd1c7904a22e0f0b64b431cbaa00057b4bb40349e5fd13463777fb66.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/cf3c6551bd1c7904a22e0f0b64b431cbaa00057b4bb40349e5fd13463777fb66.jpg)

![d04a5204ad3488b2acb96d03bd08a0b4bf99dc0d2de677553a93e6923b94133d.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/d04a5204ad3488b2acb96d03bd08a0b4bf99dc0d2de677553a93e6923b94133d.jpg)

![e2b1974a23ec447eb62df1e1f1232e4e53f75024d28ad97761b8df344e8a308e.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/e2b1974a23ec447eb62df1e1f1232e4e53f75024d28ad97761b8df344e8a308e.jpg)

![e99de42ac80256931b6fb6c8ba8b3d3d72b1d09f91a406a6441cf9ec15897a5a.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/e99de42ac80256931b6fb6c8ba8b3d3d72b1d09f91a406a6441cf9ec15897a5a.jpg)

![ec334f49d7f63826e95c315c23cbef002ad27a4d06d96766130a03a74e905cd2.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/images/ec334f49d7f63826e95c315c23cbef002ad27a4d06d96766130a03a74e905cd2.jpg)

### Tables

![5212f822645f04e0bbb216873f1e9b576ffb7b34d60395109b87cfaf3089b41f.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/tables/5212f822645f04e0bbb216873f1e9b576ffb7b34d60395109b87cfaf3089b41f.jpg)

![a40fb4903fab2d6ccac092f486f1c8384f3026462eb197aa5ddc096561014c13.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/tables/a40fb4903fab2d6ccac092f486f1c8384f3026462eb197aa5ddc096561014c13.jpg)

![bb2bf4292d58af28385b194a740ad51a75b71d0290f5ad64f9fff6d32d26f394.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/tables/bb2bf4292d58af28385b194a740ad51a75b71d0290f5ad64f9fff6d32d26f394.jpg)

![cd957efa2c977b1c2164c565e72d8e99a9e3636c6ea8f94903d36357c6635fbd.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/tables/cd957efa2c977b1c2164c565e72d8e99a9e3636c6ea8f94903d36357c6635fbd.jpg)

![cf91f3146be2e4c2c20571f580bab88f27da1a7ceb61976075e6bc1fdb7b2e6d.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/tables/cf91f3146be2e4c2c20571f580bab88f27da1a7ceb61976075e6bc1fdb7b2e6d.jpg)

![d34eee69c77020f1ffdc767e6acf252b418483db34d167b86e5451c6f653678e.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/tables/d34eee69c77020f1ffdc767e6acf252b418483db34d167b86e5451c6f653678e.jpg)

![d945011e5abe7850fea487cc6445ac3e82a7564ea0ad868edee232804d0a1680.jpg](../nips_results/5197_Gene%20Regulatory%20Network%20Inference%20in%20the%20Presence%20of%20Selection%20Bias%20and%20Latent%20Confounders/tables/d945011e5abe7850fea487cc6445ac3e82a7564ea0ad868edee232804d0a1680.jpg)

## DISCO: DISCrete nOise for Conditional Control in Text-to-Image Diffusion Models


### Images

![3f6630818a9163a37b1e8cd79258e22abf33a11aade1ef9a5f623eb992bf93f5.jpg](../nips_results/5198_DISCO_%20DISCrete%20nOise%20for%20Conditional%20Control%20in%20Text-to-Image%20Diffusion%20Models/images/3f6630818a9163a37b1e8cd79258e22abf33a11aade1ef9a5f623eb992bf93f5.jpg)

![7efb5398493284c94cf1e1777b6023bec5a268b661add244cb64a66f7b157014.jpg](../nips_results/5198_DISCO_%20DISCrete%20nOise%20for%20Conditional%20Control%20in%20Text-to-Image%20Diffusion%20Models/images/7efb5398493284c94cf1e1777b6023bec5a268b661add244cb64a66f7b157014.jpg)

![bfbb09a12b7024d0fdd6b5087f19cda115b3f1a985f26a1163f9991bea8c42bc.jpg](../nips_results/5198_DISCO_%20DISCrete%20nOise%20for%20Conditional%20Control%20in%20Text-to-Image%20Diffusion%20Models/images/bfbb09a12b7024d0fdd6b5087f19cda115b3f1a985f26a1163f9991bea8c42bc.jpg)

### Tables

![88177272cef08a6ea2f6c8fcfd3ba81ec20d690216bef14951192a6a445d565a.jpg](../nips_results/5198_DISCO_%20DISCrete%20nOise%20for%20Conditional%20Control%20in%20Text-to-Image%20Diffusion%20Models/tables/88177272cef08a6ea2f6c8fcfd3ba81ec20d690216bef14951192a6a445d565a.jpg)

![e3937d8eb290a19ff4651eb14963ac40ad7c36cbf3abaf819a9b4e2c5f52e71f.jpg](../nips_results/5198_DISCO_%20DISCrete%20nOise%20for%20Conditional%20Control%20in%20Text-to-Image%20Diffusion%20Models/tables/e3937d8eb290a19ff4651eb14963ac40ad7c36cbf3abaf819a9b4e2c5f52e71f.jpg)

## Reinforcement Learning with Backtracking Feedback


### Images

![868127779911a6d8f955553afcfd056e53d0a598240c1f4321719fc5dc9429d2.jpg](../nips_results/5199_Reinforcement%20Learning%20with%20Backtracking%20Feedback/images/868127779911a6d8f955553afcfd056e53d0a598240c1f4321719fc5dc9429d2.jpg)

![d17952032d43674705a37506df61f9ea705b7d0ac170efdebc0362e2e64bce04.jpg](../nips_results/5199_Reinforcement%20Learning%20with%20Backtracking%20Feedback/images/d17952032d43674705a37506df61f9ea705b7d0ac170efdebc0362e2e64bce04.jpg)

![f86fa32d3bd70a70347dccd8ddc04181ab989191f2519893d621b457596466a2.jpg](../nips_results/5199_Reinforcement%20Learning%20with%20Backtracking%20Feedback/images/f86fa32d3bd70a70347dccd8ddc04181ab989191f2519893d621b457596466a2.jpg)

### Tables

![1ef8bca705c617a277ccd6b829688655a3f1611fb5662e1242f36b44635ec754.jpg](../nips_results/5199_Reinforcement%20Learning%20with%20Backtracking%20Feedback/tables/1ef8bca705c617a277ccd6b829688655a3f1611fb5662e1242f36b44635ec754.jpg)

![7de88db19db1d9b60240f965c371c45b2a285495aa4488528dc808c42427f29e.jpg](../nips_results/5199_Reinforcement%20Learning%20with%20Backtracking%20Feedback/tables/7de88db19db1d9b60240f965c371c45b2a285495aa4488528dc808c42427f29e.jpg)

![9a87b5edde23cdb5e8c3f5eb4a975d71c8b874f0414fb33f6703dde54c9a14ea.jpg](../nips_results/5199_Reinforcement%20Learning%20with%20Backtracking%20Feedback/tables/9a87b5edde23cdb5e8c3f5eb4a975d71c8b874f0414fb33f6703dde54c9a14ea.jpg)

![a51117cace73409106bc2dbc49c79bdaebc4f4de6b90a6150f46072a34018381.jpg](../nips_results/5199_Reinforcement%20Learning%20with%20Backtracking%20Feedback/tables/a51117cace73409106bc2dbc49c79bdaebc4f4de6b90a6150f46072a34018381.jpg)

![e488c836187caf5079efaadcff5a7bf1fbdeea63900fd61e59366ee5d9d5d4dc.jpg](../nips_results/5199_Reinforcement%20Learning%20with%20Backtracking%20Feedback/tables/e488c836187caf5079efaadcff5a7bf1fbdeea63900fd61e59366ee5d9d5d4dc.jpg)

## BlurDM: A Blur Diffusion Model for Image Deblurring


### Images

![007f1127ced96c0b88ee0ec08e18c76d7281aed7be392c44097d51f2b0607066.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/007f1127ced96c0b88ee0ec08e18c76d7281aed7be392c44097d51f2b0607066.jpg)

![094fbdf4dfe6f2211c9d98549688cb7945ee8e221f17da4fb72199a20ab36864.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/094fbdf4dfe6f2211c9d98549688cb7945ee8e221f17da4fb72199a20ab36864.jpg)

![0a43e595113dd0eb940ec20a4f61c2e9503c3c88e8d5b5233c948d508290f5f7.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/0a43e595113dd0eb940ec20a4f61c2e9503c3c88e8d5b5233c948d508290f5f7.jpg)

![10d2f35a5e0e6d59d5debc8ec59759d92898374c7b572cd796a6246d30f79f95.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/10d2f35a5e0e6d59d5debc8ec59759d92898374c7b572cd796a6246d30f79f95.jpg)

![3844ae1dda645f770f9dc0aaf6f188ecbc8ed409b5b924018243e4d73bab0365.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/3844ae1dda645f770f9dc0aaf6f188ecbc8ed409b5b924018243e4d73bab0365.jpg)

![653d71fece377bf8f724709f6d9af35da20ea00e7ab5dc19bcfce237c0fbedbe.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/653d71fece377bf8f724709f6d9af35da20ea00e7ab5dc19bcfce237c0fbedbe.jpg)

![75b13af5532dde7cd87e14a01a8de5ad7da72a4cdd0d92381c7b2ebf64e289c8.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/75b13af5532dde7cd87e14a01a8de5ad7da72a4cdd0d92381c7b2ebf64e289c8.jpg)

![99c76166daff104d63d74b86491238ef261482fd05110733912de49ecb329e0f.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/99c76166daff104d63d74b86491238ef261482fd05110733912de49ecb329e0f.jpg)

![9afc054c4fac0c2ecb7ab0880c6eeb66ab7f969112aa1b7dfa06675bde2a8285.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/9afc054c4fac0c2ecb7ab0880c6eeb66ab7f969112aa1b7dfa06675bde2a8285.jpg)

![b839da4c1f287c7e886908a6d65c3abf1430f2ea00e4c6fc171f4f791c070be4.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/b839da4c1f287c7e886908a6d65c3abf1430f2ea00e4c6fc171f4f791c070be4.jpg)

![c2f090c96693b2db728c6d614f2f452bac2ba5bf41c6a5fa3b0683370e95508d.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/c2f090c96693b2db728c6d614f2f452bac2ba5bf41c6a5fa3b0683370e95508d.jpg)

![d7633623644c93a5e69db32e39bebbc80a391108f1c562c105fca97e16564381.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/d7633623644c93a5e69db32e39bebbc80a391108f1c562c105fca97e16564381.jpg)

![e2e4b81c796f89b86f4362f811e8c079f844eb1cf6c8af9daf21c6ad8cbc8f59.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/images/e2e4b81c796f89b86f4362f811e8c079f844eb1cf6c8af9daf21c6ad8cbc8f59.jpg)

### Tables

![0b7bb63654e45d8a91e42780e80f27c6a8edb63f53862d8a8b79a06af1dc013e.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/tables/0b7bb63654e45d8a91e42780e80f27c6a8edb63f53862d8a8b79a06af1dc013e.jpg)

![2dd03ce56ae296f3e25807b6ee93a02064daa000347b97c7a192d15964de967d.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/tables/2dd03ce56ae296f3e25807b6ee93a02064daa000347b97c7a192d15964de967d.jpg)

![410795179ad036c082fedb8c6c7a3aa657598b74e3ad7c78e6190d9fb475589b.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/tables/410795179ad036c082fedb8c6c7a3aa657598b74e3ad7c78e6190d9fb475589b.jpg)

![59ee07ab98bcd6414383f0e83d3e2021de30e347515d34599520526913af21c5.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/tables/59ee07ab98bcd6414383f0e83d3e2021de30e347515d34599520526913af21c5.jpg)

![6ed7bd22692020124d1645cf3fc5ea60880bab798bb0c9b638b77f469b2426ba.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/tables/6ed7bd22692020124d1645cf3fc5ea60880bab798bb0c9b638b77f469b2426ba.jpg)

![7a4590cf34fb809f0a2c6b8e4abac6c424c3f17dc0e1f4d67ba01904ebce0dfb.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/tables/7a4590cf34fb809f0a2c6b8e4abac6c424c3f17dc0e1f4d67ba01904ebce0dfb.jpg)

![ac864ceec638e81cd1e60431d750d304c16ad40fdf3a248aa4064b6446e945fb.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/tables/ac864ceec638e81cd1e60431d750d304c16ad40fdf3a248aa4064b6446e945fb.jpg)

![e80c590beb8e9d4f2ee6be9ce40283ec92fdd6ac7a66f3125d01f0eba794e863.jpg](../nips_results/5200_BlurDM_%20A%20Blur%20Diffusion%20Model%20for%20Image%20Deblurring/tables/e80c590beb8e9d4f2ee6be9ce40283ec92fdd6ac7a66f3125d01f0eba794e863.jpg)

## Learning a Cross-Modal Schrödinger Bridge for Visual Domain Generalization


### Images

![0c43df6a66aa7257a83b21402fc2b64037f901bd8db73759cbbd5409fa06f0f3.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/images/0c43df6a66aa7257a83b21402fc2b64037f901bd8db73759cbbd5409fa06f0f3.jpg)

![2be00694ab10a2d206516cd5b712184f9bdc6c36b43ee9078641ac3899d4d33e.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/images/2be00694ab10a2d206516cd5b712184f9bdc6c36b43ee9078641ac3899d4d33e.jpg)

![3fd4c83a97fc1cbeaf2f89a8a7f82787728ad2a54c44e3b3e0b3f990243e4655.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/images/3fd4c83a97fc1cbeaf2f89a8a7f82787728ad2a54c44e3b3e0b3f990243e4655.jpg)

![864371503a41b3454b34b38fe8bb4f596605e48de87de18b6f90f6c190d7d133.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/images/864371503a41b3454b34b38fe8bb4f596605e48de87de18b6f90f6c190d7d133.jpg)

![a17ff0cf748b7e80dd275be3277924d778934c142c3b37b9a9c7e0fdb4e5f93e.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/images/a17ff0cf748b7e80dd275be3277924d778934c142c3b37b9a9c7e0fdb4e5f93e.jpg)

![bcee8279a16704f834fa9fb03988fb3b6c269bf8fa635c1f7b8401c13eab1174.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/images/bcee8279a16704f834fa9fb03988fb3b6c269bf8fa635c1f7b8401c13eab1174.jpg)

### Tables

![060cb840d2ec161cb4817d18a5259ec6c43516bafd5117df8b0a470d997fb146.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/tables/060cb840d2ec161cb4817d18a5259ec6c43516bafd5117df8b0a470d997fb146.jpg)

![06c91d30f204736f971922348ccd788cd4f4afea6b5057de9dab68a55d5c8e52.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/tables/06c91d30f204736f971922348ccd788cd4f4afea6b5057de9dab68a55d5c8e52.jpg)

![15ecfcf50c8151785f2c1b1a100176844d66654fda71d96531ad221d0639f4e8.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/tables/15ecfcf50c8151785f2c1b1a100176844d66654fda71d96531ad221d0639f4e8.jpg)

![4783182937ab4b303914c600744de751b9175862d91d21785aa5ae66b04933a0.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/tables/4783182937ab4b303914c600744de751b9175862d91d21785aa5ae66b04933a0.jpg)

![599aa881e90471a50ab0d385e9d4c8a44b7fbdc1ab4a050456911075f4f56df5.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/tables/599aa881e90471a50ab0d385e9d4c8a44b7fbdc1ab4a050456911075f4f56df5.jpg)

![63ec28dbbd4ba4c2ea211d72ba9cf7430417336ce93f440520d9edcc3b6d6a84.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/tables/63ec28dbbd4ba4c2ea211d72ba9cf7430417336ce93f440520d9edcc3b6d6a84.jpg)

![8f84dbcb761e6b6fcc896b6500fbc8d806789fa6cbf3e3fde9834fd02fdddce4.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/tables/8f84dbcb761e6b6fcc896b6500fbc8d806789fa6cbf3e3fde9834fd02fdddce4.jpg)

![9eb6172d79c33365710eda8ab08e01fec88f272947a5a5878e1bb8159067e993.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/tables/9eb6172d79c33365710eda8ab08e01fec88f272947a5a5878e1bb8159067e993.jpg)

![b6b84c34c7a8950ba4dd28a6e912256f34abb2ba9b72010c2cbbd69aef72e5d9.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/tables/b6b84c34c7a8950ba4dd28a6e912256f34abb2ba9b72010c2cbbd69aef72e5d9.jpg)

![b6d0bbb99ca28e727e6ac0047f6587c600d31157e22c5bed68e6c1942958fd8d.jpg](../nips_results/5201_Learning%20a%20Cross-Modal%20Schr%C3%B6dinger%20Bridge%20for%20Visual%20Domain%20Generalization/tables/b6d0bbb99ca28e727e6ac0047f6587c600d31157e22c5bed68e6c1942958fd8d.jpg)

## Audio-Sync Video Generation with Multi-Stream Temporal Control


### Images

![159910bd2e38fb88fed5d11e711d61ad91886396f6dc80831619b52edfa8bd02.jpg](../nips_results/5202_Audio-Sync%20Video%20Generation%20with%20Multi-Stream%20Temporal%20Control/images/159910bd2e38fb88fed5d11e711d61ad91886396f6dc80831619b52edfa8bd02.jpg)

![3b470e21dde4619b75e7d6d8c8bf35caa373229d92b1da3807b70152526e786c.jpg](../nips_results/5202_Audio-Sync%20Video%20Generation%20with%20Multi-Stream%20Temporal%20Control/images/3b470e21dde4619b75e7d6d8c8bf35caa373229d92b1da3807b70152526e786c.jpg)

![531aaacfd31d4b2c09652fb762fa62869fe59ec2375e08efb57f7e3595c52494.jpg](../nips_results/5202_Audio-Sync%20Video%20Generation%20with%20Multi-Stream%20Temporal%20Control/images/531aaacfd31d4b2c09652fb762fa62869fe59ec2375e08efb57f7e3595c52494.jpg)

![695a64468b1fe7921625f5b9979530acf914f4fc79e015b6afa6ee536b1b4ee2.jpg](../nips_results/5202_Audio-Sync%20Video%20Generation%20with%20Multi-Stream%20Temporal%20Control/images/695a64468b1fe7921625f5b9979530acf914f4fc79e015b6afa6ee536b1b4ee2.jpg)

![8c9ca9ccd85cc82bf930ac34a1f67fd60f956ef29035663c12d61640ed6a8db6.jpg](../nips_results/5202_Audio-Sync%20Video%20Generation%20with%20Multi-Stream%20Temporal%20Control/images/8c9ca9ccd85cc82bf930ac34a1f67fd60f956ef29035663c12d61640ed6a8db6.jpg)

![abe9392cef2761f70a0c0c137564570601f0cf0e210b563528bbb06b640c19c6.jpg](../nips_results/5202_Audio-Sync%20Video%20Generation%20with%20Multi-Stream%20Temporal%20Control/images/abe9392cef2761f70a0c0c137564570601f0cf0e210b563528bbb06b640c19c6.jpg)

### Tables

![0c417b72ed373e5c9e4d7bd19699106cd6ba249cc0a6856b48131adb254a7160.jpg](../nips_results/5202_Audio-Sync%20Video%20Generation%20with%20Multi-Stream%20Temporal%20Control/tables/0c417b72ed373e5c9e4d7bd19699106cd6ba249cc0a6856b48131adb254a7160.jpg)

![97dc0d614fa3e8b6ea25a4a2b7064f740213856ecb1b4525c824424646f5f81d.jpg](../nips_results/5202_Audio-Sync%20Video%20Generation%20with%20Multi-Stream%20Temporal%20Control/tables/97dc0d614fa3e8b6ea25a4a2b7064f740213856ecb1b4525c824424646f5f81d.jpg)

![df6554a88a4847dfa169cbcd3e445ac2d19b75631817be1c34deb27a96a6abaa.jpg](../nips_results/5202_Audio-Sync%20Video%20Generation%20with%20Multi-Stream%20Temporal%20Control/tables/df6554a88a4847dfa169cbcd3e445ac2d19b75631817be1c34deb27a96a6abaa.jpg)

![e8c81980e09b2168aa08b3d5f6ab78f6e941b36cb6b0939ad9074e43fa50ee98.jpg](../nips_results/5202_Audio-Sync%20Video%20Generation%20with%20Multi-Stream%20Temporal%20Control/tables/e8c81980e09b2168aa08b3d5f6ab78f6e941b36cb6b0939ad9074e43fa50ee98.jpg)

## metaTextGrad: Automatically optimizing language model optimizers


### Images

![44487f520c2f8cc7a379a5e8af215d46a253d8518488d1c28c7dd6a797e29973.jpg](../nips_results/5203_metaTextGrad_%20Automatically%20optimizing%20language%20model%20optimizers/images/44487f520c2f8cc7a379a5e8af215d46a253d8518488d1c28c7dd6a797e29973.jpg)

![9db5d2b49f7aefab560057670df73df75913ad77df9dab955f7e204259386623.jpg](../nips_results/5203_metaTextGrad_%20Automatically%20optimizing%20language%20model%20optimizers/images/9db5d2b49f7aefab560057670df73df75913ad77df9dab955f7e204259386623.jpg)

### Tables

![14f3ad7de1f2f00c8ef4207900d87db89cb8347e0aa77c59b229d599af46cf4f.jpg](../nips_results/5203_metaTextGrad_%20Automatically%20optimizing%20language%20model%20optimizers/tables/14f3ad7de1f2f00c8ef4207900d87db89cb8347e0aa77c59b229d599af46cf4f.jpg)

![284d4ca6cca7120ab40c81bcc9b249fcd4bedab88b07e1ed15f1c5891bdbc95b.jpg](../nips_results/5203_metaTextGrad_%20Automatically%20optimizing%20language%20model%20optimizers/tables/284d4ca6cca7120ab40c81bcc9b249fcd4bedab88b07e1ed15f1c5891bdbc95b.jpg)

![3a899c55bf01682623f16b8dc33457cc2e65e53be02b39432fba4cb2f0b2be2c.jpg](../nips_results/5203_metaTextGrad_%20Automatically%20optimizing%20language%20model%20optimizers/tables/3a899c55bf01682623f16b8dc33457cc2e65e53be02b39432fba4cb2f0b2be2c.jpg)

![70789fcd98c4af227827979dfd86921c37c027f27e0508bbbc7af6694b8576ff.jpg](../nips_results/5203_metaTextGrad_%20Automatically%20optimizing%20language%20model%20optimizers/tables/70789fcd98c4af227827979dfd86921c37c027f27e0508bbbc7af6694b8576ff.jpg)

![934cb917c09d0b08c93632a2162c35806df46171e4a6238a34cd0a43b30a43dd.jpg](../nips_results/5203_metaTextGrad_%20Automatically%20optimizing%20language%20model%20optimizers/tables/934cb917c09d0b08c93632a2162c35806df46171e4a6238a34cd0a43b30a43dd.jpg)

![d84d8660089f6dc025205d1ac7be9b13882bdd79a8ae0f7783167f166d40a30d.jpg](../nips_results/5203_metaTextGrad_%20Automatically%20optimizing%20language%20model%20optimizers/tables/d84d8660089f6dc025205d1ac7be9b13882bdd79a8ae0f7783167f166d40a30d.jpg)

![f6b83867ba2fdbbc1df4e6aae28f5ab2dbbd868607b9f7d95aa5834a59c65084.jpg](../nips_results/5203_metaTextGrad_%20Automatically%20optimizing%20language%20model%20optimizers/tables/f6b83867ba2fdbbc1df4e6aae28f5ab2dbbd868607b9f7d95aa5834a59c65084.jpg)

## GeoCAD: Local Geometry-Controllable CAD Generation with Large Language Models


### Images

![25d9847fa8d5ce0d91dbc9ffbd1d57b06dfcce1805d26e77c969911cd82911e7.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/25d9847fa8d5ce0d91dbc9ffbd1d57b06dfcce1805d26e77c969911cd82911e7.jpg)

![3bdb240f4f99411aeb260b27f5b4d11be6850a59029ad6715c675097ee3d300a.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/3bdb240f4f99411aeb260b27f5b4d11be6850a59029ad6715c675097ee3d300a.jpg)

![4f523b1a536745f9b7515fa52ce21173c69b6f51bac7302c279786d1c77a8674.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/4f523b1a536745f9b7515fa52ce21173c69b6f51bac7302c279786d1c77a8674.jpg)

![4f77cba32dbe4140265ff122fc134fe1ce94d72e9b42a286a732b61de54373a8.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/4f77cba32dbe4140265ff122fc134fe1ce94d72e9b42a286a732b61de54373a8.jpg)

![66c32e9c3865e81d8f98264abd79cc6c15441f286e70f1c03a4ef395d0a1e6c2.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/66c32e9c3865e81d8f98264abd79cc6c15441f286e70f1c03a4ef395d0a1e6c2.jpg)

![9bd96604d7d271e306c72b1f602f5a40f69242c841503c7b071893169eb1ec2f.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/9bd96604d7d271e306c72b1f602f5a40f69242c841503c7b071893169eb1ec2f.jpg)

![b2a181da4c9fda0f4e317651fa21ed23f8ab5bd118fb0758fcc2c91c465aa5b2.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/b2a181da4c9fda0f4e317651fa21ed23f8ab5bd118fb0758fcc2c91c465aa5b2.jpg)

![b946aa36aae9f67111e97c07e9c4fa466d21583194f2d82d51ef5eac4640d05e.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/b946aa36aae9f67111e97c07e9c4fa466d21583194f2d82d51ef5eac4640d05e.jpg)

![bbd1201455263d06cb60bc08f48708ea2042bb458e9bd6ca0ee03a6b55233624.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/bbd1201455263d06cb60bc08f48708ea2042bb458e9bd6ca0ee03a6b55233624.jpg)

![c4c5b380eec1c3beb33c2b73d777e129893ba53e2a479fd9ad55d7647fd8527a.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/c4c5b380eec1c3beb33c2b73d777e129893ba53e2a479fd9ad55d7647fd8527a.jpg)

![c924bc334d2c0fb7c589d77b41ed0bb1a6f34efa3b47d98370b2b2c3db4ce4d4.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/c924bc334d2c0fb7c589d77b41ed0bb1a6f34efa3b47d98370b2b2c3db4ce4d4.jpg)

![e438030facaa672efbdd6f50e56e02179109739f5fb10d962885904e1e227622.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/images/e438030facaa672efbdd6f50e56e02179109739f5fb10d962885904e1e227622.jpg)

### Tables

![20bf9ce83d955f84b8f95f7a574a865951b3b7d62d901168eb5245fb061fcd67.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/tables/20bf9ce83d955f84b8f95f7a574a865951b3b7d62d901168eb5245fb061fcd67.jpg)

![919548dc0c456744db0968b8c4a15753f2ea59c95edc5290585f8fc3c1f7181e.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/tables/919548dc0c456744db0968b8c4a15753f2ea59c95edc5290585f8fc3c1f7181e.jpg)

![b2accb484a53de43d160d248da4cdec021b7711003d13809e50b6bcc7ec40648.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/tables/b2accb484a53de43d160d248da4cdec021b7711003d13809e50b6bcc7ec40648.jpg)

![d736f46ee6a773e5164274e50c3ebd8ce0f3ad0338055ee1886782ffb335aa36.jpg](../nips_results/5204_GeoCAD_%20Local%20Geometry-Controllable%20CAD%20Generation%20with%20Large%20Language%20Models/tables/d736f46ee6a773e5164274e50c3ebd8ce0f3ad0338055ee1886782ffb335aa36.jpg)

## Efficient $k$-Sparse Band–Limited Interpolation with Improved Approximation Ratio


### Images

![8287eecbc1ae7fd3c669889b99cf8ec60ba500b3edfc7a1cc215f6c1033d5342.jpg](../nips_results/5205_Efficient%20%24k%24-Sparse%20Band%E2%80%93Limited%20Interpolation%20with%20Improved%20Approximation%20Ratio/images/8287eecbc1ae7fd3c669889b99cf8ec60ba500b3edfc7a1cc215f6c1033d5342.jpg)

### Tables

![15b5138e0bd4ef7bde7da45e0814e16002bdd14475f6b2a4f08ec5ebf01abc46.jpg](../nips_results/5205_Efficient%20%24k%24-Sparse%20Band%E2%80%93Limited%20Interpolation%20with%20Improved%20Approximation%20Ratio/tables/15b5138e0bd4ef7bde7da45e0814e16002bdd14475f6b2a4f08ec5ebf01abc46.jpg)

![3306cef0ffed5ca85d51eb06051a6cf9e14018bd7593e1b0ddf18a05adf1a861.jpg](../nips_results/5205_Efficient%20%24k%24-Sparse%20Band%E2%80%93Limited%20Interpolation%20with%20Improved%20Approximation%20Ratio/tables/3306cef0ffed5ca85d51eb06051a6cf9e14018bd7593e1b0ddf18a05adf1a861.jpg)

![f73caa7f1840d4d91eb913358d32529bd48d7866686bc1d08706744dd3c3d19e.jpg](../nips_results/5205_Efficient%20%24k%24-Sparse%20Band%E2%80%93Limited%20Interpolation%20with%20Improved%20Approximation%20Ratio/tables/f73caa7f1840d4d91eb913358d32529bd48d7866686bc1d08706744dd3c3d19e.jpg)

## TEMPO: Temporal Multi-scale Autoregressive Generation of Protein Conformational Ensembles


### Images

![06300b04b57acf6b0be1870d26d027e2c7a6ed89f4c8f9f0cc32c35bb3ae7d4c.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/06300b04b57acf6b0be1870d26d027e2c7a6ed89f4c8f9f0cc32c35bb3ae7d4c.jpg)

![22383bec7f2d94bc65f691dcc89b9d8c88d2634abaee97c89c8e526c4b6de3b1.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/22383bec7f2d94bc65f691dcc89b9d8c88d2634abaee97c89c8e526c4b6de3b1.jpg)

![23433cf99d83e69cbcc8519f29e8952818e814e20afc88cf99499190fc0d482c.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/23433cf99d83e69cbcc8519f29e8952818e814e20afc88cf99499190fc0d482c.jpg)

![4f12a669f1bd5d4628210313ccc5858cc12c244de45fb5562b5d52d781f621ae.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/4f12a669f1bd5d4628210313ccc5858cc12c244de45fb5562b5d52d781f621ae.jpg)

![5f4ac2363e493a4fbeb66c5f783d9b28f62a4ff6ab7a2475e453a24107120c43.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/5f4ac2363e493a4fbeb66c5f783d9b28f62a4ff6ab7a2475e453a24107120c43.jpg)

![7dc7965c5f51f9e4632ccab104fb5c282735fbc901d3e87b93b7654db73494ae.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/7dc7965c5f51f9e4632ccab104fb5c282735fbc901d3e87b93b7654db73494ae.jpg)

![8c3a552c17755b8b2d60c5471310d06cbad5f20a1657446fb94eb13732ee08bc.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/8c3a552c17755b8b2d60c5471310d06cbad5f20a1657446fb94eb13732ee08bc.jpg)

![aca4045d17903862a2a61bd3a7c97c841cad31ac0f0fe162f565ec850d8498b5.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/aca4045d17903862a2a61bd3a7c97c841cad31ac0f0fe162f565ec850d8498b5.jpg)

![ade9d77da90a6c451b58e4ae6aa21cacc7c0445fb49e7c8501c8699fa11ad69b.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/ade9d77da90a6c451b58e4ae6aa21cacc7c0445fb49e7c8501c8699fa11ad69b.jpg)

![ba13f9b166d7ff4c325f27900d53bfefa5f46ebf4fbb2d3454bae48f45f4ab80.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/ba13f9b166d7ff4c325f27900d53bfefa5f46ebf4fbb2d3454bae48f45f4ab80.jpg)

![d0b0f53bd0b6dcc09f586cae93447595566afcd6f368ab9f87c189be0b248b6e.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/d0b0f53bd0b6dcc09f586cae93447595566afcd6f368ab9f87c189be0b248b6e.jpg)

![e279b9dc85873c63d9c1f4aa2b3b31eac9ad3bf3238f24d8d238fa0691c91757.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/e279b9dc85873c63d9c1f4aa2b3b31eac9ad3bf3238f24d8d238fa0691c91757.jpg)

![f9cb1f39f9f5b2fd877098e2d9a3e0c9525e4b71086195d50ce3ec3824cd3ba1.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/images/f9cb1f39f9f5b2fd877098e2d9a3e0c9525e4b71086195d50ce3ec3824cd3ba1.jpg)

### Tables

![509f173e2881343934d4996284a3fa261d3ab93a39463a0d971a2098174c2a77.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/tables/509f173e2881343934d4996284a3fa261d3ab93a39463a0d971a2098174c2a77.jpg)

![ba38f6531b38955ee1cd8dfb5aae1ee0509e065ba67e1a169851d3907e298434.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/tables/ba38f6531b38955ee1cd8dfb5aae1ee0509e065ba67e1a169851d3907e298434.jpg)

![c89fb1d78907bd580f7c2cbb36af261e013a798cffa1efce0956ed0b16392a55.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/tables/c89fb1d78907bd580f7c2cbb36af261e013a798cffa1efce0956ed0b16392a55.jpg)

![ea689c41727a33bf64c9565e48c71bf905b63cf0acdb0a68351886c027a3c69a.jpg](../nips_results/5206_TEMPO_%20Temporal%20Multi-scale%20Autoregressive%20Generation%20of%20Protein%20Conformational%20Ensembles/tables/ea689c41727a33bf64c9565e48c71bf905b63cf0acdb0a68351886c027a3c69a.jpg)

## Machine Unlearning in 3D Generation: A Perspective-Coherent Acceleration Framework


### Images

![205698e3e9fe4e7d9a728031fa986b999e8320a8aba8c998782aa43e38edeb84.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/images/205698e3e9fe4e7d9a728031fa986b999e8320a8aba8c998782aa43e38edeb84.jpg)

![32fa7e2632041a4f7635308767ad6c65bed2172dc85222ba371eb2b8476383b5.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/images/32fa7e2632041a4f7635308767ad6c65bed2172dc85222ba371eb2b8476383b5.jpg)

![414af3cfea4066bb2476007531ffcd171898e4695ee893b18f8b3dbb42b475a0.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/images/414af3cfea4066bb2476007531ffcd171898e4695ee893b18f8b3dbb42b475a0.jpg)

![735d6fcbdcaa321ccb961b5ec28f862c95f9ae47994549c72026d4a6967c16f1.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/images/735d6fcbdcaa321ccb961b5ec28f862c95f9ae47994549c72026d4a6967c16f1.jpg)

![bdac6a1921983c7c91af932c7f5992706c239d7887e3d5da963da658e336426a.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/images/bdac6a1921983c7c91af932c7f5992706c239d7887e3d5da963da658e336426a.jpg)

![ccd61ab621bfee9c9384a7f054617ae473238d1f9af7d9d831f9e0bbdf8b776b.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/images/ccd61ab621bfee9c9384a7f054617ae473238d1f9af7d9d831f9e0bbdf8b776b.jpg)

![de6c990af649266b2aa636edb06c4c061fcb9c0603e27a56de59a211955312ce.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/images/de6c990af649266b2aa636edb06c4c061fcb9c0603e27a56de59a211955312ce.jpg)

![ec15d0f304515f091f0ccf7843461c9a552f3ee378e6b405467ff9ad98f767f0.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/images/ec15d0f304515f091f0ccf7843461c9a552f3ee378e6b405467ff9ad98f767f0.jpg)

![f22ddf2dd6d07a5c530492ea356b4429e0bff5bce383a932b31c38bc082879bc.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/images/f22ddf2dd6d07a5c530492ea356b4429e0bff5bce383a932b31c38bc082879bc.jpg)

### Tables

![128c4b21a1a3395d760013a68dc1730dab68f1457beb1c5326b28aec409c6774.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/tables/128c4b21a1a3395d760013a68dc1730dab68f1457beb1c5326b28aec409c6774.jpg)

![24226433ae03f191e6faaee73d0dad9e7aa5d86d5e018cc9c97d87fc2e1f5bf2.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/tables/24226433ae03f191e6faaee73d0dad9e7aa5d86d5e018cc9c97d87fc2e1f5bf2.jpg)

![61cb959f8c8f11d27dddaf37a79201310663d203faf5cf41a6e582663d60f643.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/tables/61cb959f8c8f11d27dddaf37a79201310663d203faf5cf41a6e582663d60f643.jpg)

![6dcab0dbee8382ff340d336a75db683042298a66bf4614d10d1415ddbe418c20.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/tables/6dcab0dbee8382ff340d336a75db683042298a66bf4614d10d1415ddbe418c20.jpg)

![84808858e3db088e8620b65d2387fa7ccfcd7e6f77b85e78c3788556a55540f8.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/tables/84808858e3db088e8620b65d2387fa7ccfcd7e6f77b85e78c3788556a55540f8.jpg)

![a9f343f959d39ea595e013c2b9d7d23d2ecce09109dc7c1ef064e3c9769a66bc.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/tables/a9f343f959d39ea595e013c2b9d7d23d2ecce09109dc7c1ef064e3c9769a66bc.jpg)

![b86ce644af6d5b4af7dbb2336e24f76fa3c4ede837e8d76b2bc33c39c2b95eca.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/tables/b86ce644af6d5b4af7dbb2336e24f76fa3c4ede837e8d76b2bc33c39c2b95eca.jpg)

![cd9901ffe096d3853ab82e32ed806041f963f090712777bdfb61530017d20541.jpg](../nips_results/5207_Machine%20Unlearning%20in%203D%20Generation_%20A%20Perspective-Coherent%20Acceleration%20Framework/tables/cd9901ffe096d3853ab82e32ed806041f963f090712777bdfb61530017d20541.jpg)

## Towards a Geometric Understanding of Tensor Learning via the t-Product


### Images

![87d6fe87a2d9558d1e3490f2b39393be2dfa7dacdd487047121c1ed4d823532c.jpg](../nips_results/5208_Towards%20a%20Geometric%20Understanding%20of%20Tensor%20Learning%20via%20the%20t-Product/images/87d6fe87a2d9558d1e3490f2b39393be2dfa7dacdd487047121c1ed4d823532c.jpg)

### Tables

![2f47684ca8a4cae97c928f63f640924f489b10bfd6dcff2a1472524df8eb352d.jpg](../nips_results/5208_Towards%20a%20Geometric%20Understanding%20of%20Tensor%20Learning%20via%20the%20t-Product/tables/2f47684ca8a4cae97c928f63f640924f489b10bfd6dcff2a1472524df8eb352d.jpg)

## SurfelSplat: Learning Efficient and Generalizable Gaussian Surfel Representations for Sparse-View Surface Reconstruction


### Images

![03fd1fd1ad0fb93eb21a249791541f7b56f920cedcc5d7ab339655f06f9291d4.jpg](../nips_results/5209_SurfelSplat_%20Learning%20Efficient%20and%20Generalizable%20Gaussian%20Surfel%20Representations%20for%20Sparse-View%20Su/images/03fd1fd1ad0fb93eb21a249791541f7b56f920cedcc5d7ab339655f06f9291d4.jpg)

![1e37cae5503262178379012e23acc97b33ad8db1070e75c64dbdc8c39e4c8589.jpg](../nips_results/5209_SurfelSplat_%20Learning%20Efficient%20and%20Generalizable%20Gaussian%20Surfel%20Representations%20for%20Sparse-View%20Su/images/1e37cae5503262178379012e23acc97b33ad8db1070e75c64dbdc8c39e4c8589.jpg)

![3ccba7f20fbb7dd6d821bb901a352a781312333ee1628e74eac282fc2416fd33.jpg](../nips_results/5209_SurfelSplat_%20Learning%20Efficient%20and%20Generalizable%20Gaussian%20Surfel%20Representations%20for%20Sparse-View%20Su/images/3ccba7f20fbb7dd6d821bb901a352a781312333ee1628e74eac282fc2416fd33.jpg)

![483f69c322a37fd1115da9edb2366e50afc0fbcc74935af6e4875e519546edaa.jpg](../nips_results/5209_SurfelSplat_%20Learning%20Efficient%20and%20Generalizable%20Gaussian%20Surfel%20Representations%20for%20Sparse-View%20Su/images/483f69c322a37fd1115da9edb2366e50afc0fbcc74935af6e4875e519546edaa.jpg)

![5839599e025b981e0059cf6643d9555a6329653f26c593f0bede04ef4769c9ab.jpg](../nips_results/5209_SurfelSplat_%20Learning%20Efficient%20and%20Generalizable%20Gaussian%20Surfel%20Representations%20for%20Sparse-View%20Su/images/5839599e025b981e0059cf6643d9555a6329653f26c593f0bede04ef4769c9ab.jpg)

![8f1ef1fc187365b060d03fa05709ee170610f383d38750e92d8e236ba9a7fb6d.jpg](../nips_results/5209_SurfelSplat_%20Learning%20Efficient%20and%20Generalizable%20Gaussian%20Surfel%20Representations%20for%20Sparse-View%20Su/images/8f1ef1fc187365b060d03fa05709ee170610f383d38750e92d8e236ba9a7fb6d.jpg)

![b0ffff61fb3a18e885818979b5aabc1a04411dd136bbcb7730b004794ef550b9.jpg](../nips_results/5209_SurfelSplat_%20Learning%20Efficient%20and%20Generalizable%20Gaussian%20Surfel%20Representations%20for%20Sparse-View%20Su/images/b0ffff61fb3a18e885818979b5aabc1a04411dd136bbcb7730b004794ef550b9.jpg)

![fb2ffbf6b1689a6b7f2eabd42f5345281eb9294839a979574cf4d910ede10724.jpg](../nips_results/5209_SurfelSplat_%20Learning%20Efficient%20and%20Generalizable%20Gaussian%20Surfel%20Representations%20for%20Sparse-View%20Su/images/fb2ffbf6b1689a6b7f2eabd42f5345281eb9294839a979574cf4d910ede10724.jpg)

### Tables

![06746ea6a47bb1ac1e75e75917db015feb93959362c8c578026f062745c0db18.jpg](../nips_results/5209_SurfelSplat_%20Learning%20Efficient%20and%20Generalizable%20Gaussian%20Surfel%20Representations%20for%20Sparse-View%20Su/tables/06746ea6a47bb1ac1e75e75917db015feb93959362c8c578026f062745c0db18.jpg)

![3948fb0df3b8378c4a05d3da16f30ca81416d7dbb5ea74bdfa8201de00fbc977.jpg](../nips_results/5209_SurfelSplat_%20Learning%20Efficient%20and%20Generalizable%20Gaussian%20Surfel%20Representations%20for%20Sparse-View%20Su/tables/3948fb0df3b8378c4a05d3da16f30ca81416d7dbb5ea74bdfa8201de00fbc977.jpg)

![52529f67fab594a83a1b1bfa2689dde4bc0f89b14c9b726289719ed3d013af54.jpg](../nips_results/5209_SurfelSplat_%20Learning%20Efficient%20and%20Generalizable%20Gaussian%20Surfel%20Representations%20for%20Sparse-View%20Su/tables/52529f67fab594a83a1b1bfa2689dde4bc0f89b14c9b726289719ed3d013af54.jpg)

## Gaze-VLM: Bridging Gaze and VLMs through Attention Regularization for Egocentric Understanding


### Images

![054a9dc83d452d59c4b7b2981adb014fb025328a89195df0bf23dd4d0c59e9a1.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/054a9dc83d452d59c4b7b2981adb014fb025328a89195df0bf23dd4d0c59e9a1.jpg)

![1ac92330b03441ed04678a240f5b8c70e14a3152938d247516e52c82e99ad446.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/1ac92330b03441ed04678a240f5b8c70e14a3152938d247516e52c82e99ad446.jpg)

![23163cd5b4978ff82990dd00c91eddcb8ca0f46d12a1199af4aa8c2470e2f9eb.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/23163cd5b4978ff82990dd00c91eddcb8ca0f46d12a1199af4aa8c2470e2f9eb.jpg)

![58e8151c4305cf3ed8ac0727fabf112872308f1180bff920551d467505b3fa38.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/58e8151c4305cf3ed8ac0727fabf112872308f1180bff920551d467505b3fa38.jpg)

![5bdfc2fd5c9d1f98ec2d5eebc8c50b7f47ef59b8529dcda347ff22c06f6ba4ba.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/5bdfc2fd5c9d1f98ec2d5eebc8c50b7f47ef59b8529dcda347ff22c06f6ba4ba.jpg)

![6674d4c7e204097aa1176ba2b89cf3b6355c1fc71339bb4f28604dd66e521f65.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/6674d4c7e204097aa1176ba2b89cf3b6355c1fc71339bb4f28604dd66e521f65.jpg)

![6ff473718af92fcc547e2c8587d50ada4f2c7cc4ed1801a16434224d21f1f4f9.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/6ff473718af92fcc547e2c8587d50ada4f2c7cc4ed1801a16434224d21f1f4f9.jpg)

![9534b8301e87f85d06f5cc98af78087aafa30bba2e8072b3889a34f671f9be05.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/9534b8301e87f85d06f5cc98af78087aafa30bba2e8072b3889a34f671f9be05.jpg)

![9a78d8abc709b1345639f7a2621e045d4013f2bb987f0e0d5e4fdccd480c0925.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/9a78d8abc709b1345639f7a2621e045d4013f2bb987f0e0d5e4fdccd480c0925.jpg)

![afeb83da83f1c0a88502740a98a4b956614a35654bebdce10a57eb51863994ee.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/afeb83da83f1c0a88502740a98a4b956614a35654bebdce10a57eb51863994ee.jpg)

![b98af334b846ca550265051292bfbced5972053befec71f5536bbf66797f338f.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/b98af334b846ca550265051292bfbced5972053befec71f5536bbf66797f338f.jpg)

![ebe65d0654f077cbb95161a02b51a8331565104e4b8c2926d2df38197d6f2618.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/images/ebe65d0654f077cbb95161a02b51a8331565104e4b8c2926d2df38197d6f2618.jpg)

### Tables

![02361b033b54b795aa43a3033818210f6928d7ac28411a6cf2efbd4b1cd996c0.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/02361b033b54b795aa43a3033818210f6928d7ac28411a6cf2efbd4b1cd996c0.jpg)

![054b9caa5bad0232b7fa787871671227ca9092beab63bb0a4811a08be61b15a5.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/054b9caa5bad0232b7fa787871671227ca9092beab63bb0a4811a08be61b15a5.jpg)

![09a1d0c2b2a47cf559b7bc396f7e3a771883c070a0391d9f6eca1078562e5685.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/09a1d0c2b2a47cf559b7bc396f7e3a771883c070a0391d9f6eca1078562e5685.jpg)

![0ceb5745f84c8ec1a4b8f7d6643fe2a290c00b9e9a1615aa1029ed49a2cbe84a.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/0ceb5745f84c8ec1a4b8f7d6643fe2a290c00b9e9a1615aa1029ed49a2cbe84a.jpg)

![292cd05f58c9308852f18778e4b57f8880df20dd13458c203b0280b2dfff44e0.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/292cd05f58c9308852f18778e4b57f8880df20dd13458c203b0280b2dfff44e0.jpg)

![338d979fc515106b8967b2f1cf2fce363c22e272385744d722c54c0e05de50d4.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/338d979fc515106b8967b2f1cf2fce363c22e272385744d722c54c0e05de50d4.jpg)

![4472ea9def2ec6d4c430ed47907542079efb0a8419c82a704cfe83af13ca1e62.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/4472ea9def2ec6d4c430ed47907542079efb0a8419c82a704cfe83af13ca1e62.jpg)

![4e2bdcb50947980549dee4b99cf4a007f29a81d27443735890902fb440707580.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/4e2bdcb50947980549dee4b99cf4a007f29a81d27443735890902fb440707580.jpg)

![65bba845a46ff8550825ab665e1fb1fc11afba64c874bcd1fac23383c85f4c25.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/65bba845a46ff8550825ab665e1fb1fc11afba64c874bcd1fac23383c85f4c25.jpg)

![75cd313ab5d3050d0a653da59c4f3dd26d675151796b0f895eadb4f2ee24c461.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/75cd313ab5d3050d0a653da59c4f3dd26d675151796b0f895eadb4f2ee24c461.jpg)

![7ab284da79829194c943eb647ba4f4535a78d040f5937cd57485fe5e6eb70934.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/7ab284da79829194c943eb647ba4f4535a78d040f5937cd57485fe5e6eb70934.jpg)

![7fa9caa572b0e6cfaa9c9d04cbd80421b8040283ac8dbd9ff5b5c65a78cdbf78.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/7fa9caa572b0e6cfaa9c9d04cbd80421b8040283ac8dbd9ff5b5c65a78cdbf78.jpg)

![839694ae9c99fa79fd902dad40a60cdc5b83d711e851ed1c354b885b500e96fe.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/839694ae9c99fa79fd902dad40a60cdc5b83d711e851ed1c354b885b500e96fe.jpg)

![8dcb2e18af2662e63d098c5edf858117a4ae96351186a5f124b3c8997d926a6a.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/8dcb2e18af2662e63d098c5edf858117a4ae96351186a5f124b3c8997d926a6a.jpg)

![af1461ae4962d31b05e4cc4280f775bff1f5af7934ea73bf01938fca91a360fc.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/af1461ae4962d31b05e4cc4280f775bff1f5af7934ea73bf01938fca91a360fc.jpg)

![b3e90093964fc73d6f35f500e74f6ddf15d1090fbc83cd203130908316559900.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/b3e90093964fc73d6f35f500e74f6ddf15d1090fbc83cd203130908316559900.jpg)

![b61dc65cf29e6a8806564058f7ed1bb063556229c1f9a41d1bdf3e67ae6d6959.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/b61dc65cf29e6a8806564058f7ed1bb063556229c1f9a41d1bdf3e67ae6d6959.jpg)

![c7abd5f16358f2abfee1380efb59eced0d9b1f8a82afdffab6d45aa6e44fe135.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/c7abd5f16358f2abfee1380efb59eced0d9b1f8a82afdffab6d45aa6e44fe135.jpg)

![d33183549a0d95f7ce3bc8a3742738d613b50e2b2e4e5f896844c489b7d78b70.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/d33183549a0d95f7ce3bc8a3742738d613b50e2b2e4e5f896844c489b7d78b70.jpg)

![dfdbf21ca82fc29b59084f93d8563f09ec1501cd3c43bdd9e6020ae6d7191ac8.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/dfdbf21ca82fc29b59084f93d8563f09ec1501cd3c43bdd9e6020ae6d7191ac8.jpg)

![f1d630c31ce49f0921ae0281edcbd0a301b3d7b418fcb7bd6c7503903f907b0d.jpg](../nips_results/5210_Gaze-VLM_%20Bridging%20Gaze%20and%20VLMs%20through%20Attention%20Regularization%20for%20Egocentric%20Understanding/tables/f1d630c31ce49f0921ae0281edcbd0a301b3d7b418fcb7bd6c7503903f907b0d.jpg)

## Learning CAD Modeling Sequences via Projection and Part Awareness


### Images

![048cf95e4d560651b61d4ef204c5e61bff0507b8e941b7e0882ac1d12bb2c784.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/048cf95e4d560651b61d4ef204c5e61bff0507b8e941b7e0882ac1d12bb2c784.jpg)

![1121e58ca07142c38a1a1dc72825f83763c4da5cd8bc0dbe2258cce5fa474efe.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/1121e58ca07142c38a1a1dc72825f83763c4da5cd8bc0dbe2258cce5fa474efe.jpg)

![1f2762172cdb0d8d00e63ca2989d887847cf414a1f979b4f5f3859dbc0b4b9b8.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/1f2762172cdb0d8d00e63ca2989d887847cf414a1f979b4f5f3859dbc0b4b9b8.jpg)

![35622cda7cff7c16c9226dce45bdc6604a98f9d79220a8778ee031d8f419c61d.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/35622cda7cff7c16c9226dce45bdc6604a98f9d79220a8778ee031d8f419c61d.jpg)

![39f369231675c775f50ff651c5a083614be46830b82925a7bcfea3291c22645d.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/39f369231675c775f50ff651c5a083614be46830b82925a7bcfea3291c22645d.jpg)

![3ddf461b9fdd81cd97f9342720e40d82e75fe0ac6d4032ec173b6fea380d9e87.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/3ddf461b9fdd81cd97f9342720e40d82e75fe0ac6d4032ec173b6fea380d9e87.jpg)

![3f7eb1a63f3114f225f971df165ea7b3d8e8e52287323d2358511fffb6af6003.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/3f7eb1a63f3114f225f971df165ea7b3d8e8e52287323d2358511fffb6af6003.jpg)

![4563e6d8d8a2bd795ff63de1de403bb88082c0f1f200e9c67e48eb4493e7172d.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/4563e6d8d8a2bd795ff63de1de403bb88082c0f1f200e9c67e48eb4493e7172d.jpg)

![458391f11b28242c38c3083982075d36152da005f2dee5794418bfc649161d0e.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/458391f11b28242c38c3083982075d36152da005f2dee5794418bfc649161d0e.jpg)

![4f88b39b93b327ff4d94c7f3a78f712f08be9f7edfd3e38cf2b6826811347c4d.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/4f88b39b93b327ff4d94c7f3a78f712f08be9f7edfd3e38cf2b6826811347c4d.jpg)

![63d1aabdaf550709a0e0272064a5016887e4e70ad81514716fd8d430669be64d.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/63d1aabdaf550709a0e0272064a5016887e4e70ad81514716fd8d430669be64d.jpg)

![749c3a679828a42bff841e2cac459408ddbaf1760651be3525737ba3f4f46fd5.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/749c3a679828a42bff841e2cac459408ddbaf1760651be3525737ba3f4f46fd5.jpg)

![83f1ff2aefc1717d4702aabd6b9bbcb47e3ca154618798d8ee27c3f51629c982.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/83f1ff2aefc1717d4702aabd6b9bbcb47e3ca154618798d8ee27c3f51629c982.jpg)

![b755c64114fdefd0b624edc32a2e5f1f52edf7ef6fa78a3c446309839a29ad0b.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/b755c64114fdefd0b624edc32a2e5f1f52edf7ef6fa78a3c446309839a29ad0b.jpg)

![ca931a03c03490fbc9813761ab0266d0d5cca7692f50bdb95b2ed23867ddb8b3.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/ca931a03c03490fbc9813761ab0266d0d5cca7692f50bdb95b2ed23867ddb8b3.jpg)

![d36f385185271c25ebc9e3d269a6fff500df156954042ef9d862820fd70badea.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/d36f385185271c25ebc9e3d269a6fff500df156954042ef9d862820fd70badea.jpg)

![dc88a35973638df1088f31db66bef1dd792b981a4abc4e41a7a0d2ab78058dfe.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/dc88a35973638df1088f31db66bef1dd792b981a4abc4e41a7a0d2ab78058dfe.jpg)

![e82a3a2b2b3827a77c6a2e9454be1583e77358289012524ecf3443b8c8d83b11.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/images/e82a3a2b2b3827a77c6a2e9454be1583e77358289012524ecf3443b8c8d83b11.jpg)

### Tables

![018733e41c78da3ffd80e899e13e6c53933adfbe67350f520781d620ab85312f.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/tables/018733e41c78da3ffd80e899e13e6c53933adfbe67350f520781d620ab85312f.jpg)

![12137d7a7f4730060a8858cc7c8b402c71c736eeb0a5051c107920f3d2a95c53.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/tables/12137d7a7f4730060a8858cc7c8b402c71c736eeb0a5051c107920f3d2a95c53.jpg)

![140aeed6477804cf6cea72f57e5b0d843366d2302b82d6968442d9778554ab9d.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/tables/140aeed6477804cf6cea72f57e5b0d843366d2302b82d6968442d9778554ab9d.jpg)

![193f2d3d89cb068d49c940c4c2d25c0bc35f54c1020faca22adde0fd2d155e53.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/tables/193f2d3d89cb068d49c940c4c2d25c0bc35f54c1020faca22adde0fd2d155e53.jpg)

![a0fc9452c2048e6b540872c298845023fc8bb10c596e6581d79d15e07df8612e.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/tables/a0fc9452c2048e6b540872c298845023fc8bb10c596e6581d79d15e07df8612e.jpg)

![bd468b298d4c9a907108ae7e133a098b0cf3f3f7bcb34b37d029b4f9e2642f49.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/tables/bd468b298d4c9a907108ae7e133a098b0cf3f3f7bcb34b37d029b4f9e2642f49.jpg)

![f369f2ed868efa4e101cdde0fd2316a332b97fc9c30ac6034523b003d4651075.jpg](../nips_results/5211_Learning%20CAD%20Modeling%20Sequences%20via%20Projection%20and%20Part%20Awareness/tables/f369f2ed868efa4e101cdde0fd2316a332b97fc9c30ac6034523b003d4651075.jpg)

## CF-VLM：CounterFactual Vision-Language Fine-tuning


### Images

![0349c6f2307e64e1f59d7e88f3eb2d6947c3566e3e377d2be89610671035b349.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/0349c6f2307e64e1f59d7e88f3eb2d6947c3566e3e377d2be89610671035b349.jpg)

![066bfd2f52220fd72e2566ef13c65f7600d78c55495e09a45dc38621b4506799.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/066bfd2f52220fd72e2566ef13c65f7600d78c55495e09a45dc38621b4506799.jpg)

![0709f278a914b4b4f24adf7afa400f27b839589eabb738ba1eb5a15e3f734d95.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/0709f278a914b4b4f24adf7afa400f27b839589eabb738ba1eb5a15e3f734d95.jpg)

![07b6ffd4e3fc13fb99969435dc71e1c3f7046ae13bce72ebbe35d1f4940afb21.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/07b6ffd4e3fc13fb99969435dc71e1c3f7046ae13bce72ebbe35d1f4940afb21.jpg)

![08eda6fe2ca47b5c918e372c40873ba80113c6fef0c412044a25504243ecc198.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/08eda6fe2ca47b5c918e372c40873ba80113c6fef0c412044a25504243ecc198.jpg)

![096bc5e08a8ee9efd5899226b4987ed587d4eaea02ebd260d2009b13beeee4e7.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/096bc5e08a8ee9efd5899226b4987ed587d4eaea02ebd260d2009b13beeee4e7.jpg)

![0ecc86f7fd2db6646a8d9628d5999c08dc4f3a2fdecf27e86509cce3c94defad.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/0ecc86f7fd2db6646a8d9628d5999c08dc4f3a2fdecf27e86509cce3c94defad.jpg)

![0ff0b3f11fb114107e0da8b4d0bbdfe94f0ad7f0f037d5f82b354abd8eb677fc.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/0ff0b3f11fb114107e0da8b4d0bbdfe94f0ad7f0f037d5f82b354abd8eb677fc.jpg)

![1286e4f5fa1392cbf55e75f37de053016223a60ad325ed09e5d5a876917eeaa8.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/1286e4f5fa1392cbf55e75f37de053016223a60ad325ed09e5d5a876917eeaa8.jpg)

![13aa74f4a4c04c9d46b1c73e1b49b2fd10e215abfe369eda9775d6b1b2714354.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/13aa74f4a4c04c9d46b1c73e1b49b2fd10e215abfe369eda9775d6b1b2714354.jpg)

![148ef4639df37264163175def8b4d4d2d9755f16ebeeee7cc44e00d2cb4faa7a.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/148ef4639df37264163175def8b4d4d2d9755f16ebeeee7cc44e00d2cb4faa7a.jpg)

![16d3b38a9413b9b9a24af2194694e3e1f6350c9fb5685005d42d96bcb239d23c.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/16d3b38a9413b9b9a24af2194694e3e1f6350c9fb5685005d42d96bcb239d23c.jpg)

![17569ab1c3f780667c18e155d4d6a18dfc47cde6cef63259ed9c802e594fedd4.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/17569ab1c3f780667c18e155d4d6a18dfc47cde6cef63259ed9c802e594fedd4.jpg)

![1ff0b48cc58f89705be083bc2292e9faddfe44ec90ec3d4b12726e197cc276df.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/1ff0b48cc58f89705be083bc2292e9faddfe44ec90ec3d4b12726e197cc276df.jpg)

![2751be87b8da20181c7094abee6c3ebaa95a8629fa1a1d70fa9d393178c72da6.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/2751be87b8da20181c7094abee6c3ebaa95a8629fa1a1d70fa9d393178c72da6.jpg)

![33aa324e7ac687cf53086a95619dd32fc0777c6370b07c2fc0ffef681d7c5536.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/33aa324e7ac687cf53086a95619dd32fc0777c6370b07c2fc0ffef681d7c5536.jpg)

![36403243f8df9c93f7541092f20457b5c4f9993964406a8d67e21e8faa24250f.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/36403243f8df9c93f7541092f20457b5c4f9993964406a8d67e21e8faa24250f.jpg)

![364a20c865fbf597dfc0297269f758b19de5fe55ca6176794878a1b587704afa.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/364a20c865fbf597dfc0297269f758b19de5fe55ca6176794878a1b587704afa.jpg)

![38d8ac4ef8bf34b9c74b17eb7d4e7742886fc38cd99151f0d7678174de413563.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/38d8ac4ef8bf34b9c74b17eb7d4e7742886fc38cd99151f0d7678174de413563.jpg)

![3c2758f58beefe45e66336a1fbba9f5d0835d534b5518f1e88eb46d7faf419da.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/3c2758f58beefe45e66336a1fbba9f5d0835d534b5518f1e88eb46d7faf419da.jpg)

![3e25e79601fe8b00afde299bbd656167dc83003fad76c37d7c3013e26b3f5b35.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/3e25e79601fe8b00afde299bbd656167dc83003fad76c37d7c3013e26b3f5b35.jpg)

![3e7a31dc9d2ebe8168bc668edde3ce9867e1544bd992ebd6b8d06af0b28f9aa7.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/3e7a31dc9d2ebe8168bc668edde3ce9867e1544bd992ebd6b8d06af0b28f9aa7.jpg)

![410a4fb8eccde285e3d52299a6704092328063becd0119e9bb18250eeff7fbc3.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/410a4fb8eccde285e3d52299a6704092328063becd0119e9bb18250eeff7fbc3.jpg)

![47a354b19660cc5013c731c6feb4eaeb813bec2b6f429603ede69953feaedad6.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/47a354b19660cc5013c731c6feb4eaeb813bec2b6f429603ede69953feaedad6.jpg)

![627be4f2e5eb07c89aedb6d4b9127d7c5032a63324c4447e5dc105be68ae9229.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/627be4f2e5eb07c89aedb6d4b9127d7c5032a63324c4447e5dc105be68ae9229.jpg)

![63ca7a7c94ebd47e8e78e3b006ac927089c708031f80fc22583478b44784757d.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/63ca7a7c94ebd47e8e78e3b006ac927089c708031f80fc22583478b44784757d.jpg)

![655952cd3bac72fc35b45eaf50517ed39e83d82d0ff4bf39876ac59ff107b316.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/655952cd3bac72fc35b45eaf50517ed39e83d82d0ff4bf39876ac59ff107b316.jpg)

![65c4e52e52b0285a008e81268f1f8033aaf3d7d0aa83828981a4f73b01e4afe1.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/65c4e52e52b0285a008e81268f1f8033aaf3d7d0aa83828981a4f73b01e4afe1.jpg)

![65eaa26dccba9137a560f8b1b5b2ecdce2d1a7cf6b07178d3bc3bd9757f62d06.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/65eaa26dccba9137a560f8b1b5b2ecdce2d1a7cf6b07178d3bc3bd9757f62d06.jpg)

![6ff6906667f3448ac77c7620b42f7c34442adef2adf260774bad9ddbd7e7f4f9.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/6ff6906667f3448ac77c7620b42f7c34442adef2adf260774bad9ddbd7e7f4f9.jpg)

![7359ab88116237a703ab171b49186a4ac4c0d02ba13710c5f49b6fd3d8a8795f.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/7359ab88116237a703ab171b49186a4ac4c0d02ba13710c5f49b6fd3d8a8795f.jpg)

![77436fd107152307e2c928a178e9cb49660430008bb48ef1953c12f6f1f61d9e.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/77436fd107152307e2c928a178e9cb49660430008bb48ef1953c12f6f1f61d9e.jpg)

![7b237582503b3dbd3b0849edae92fdffa2db1129bf076b64f88dc34e0ddbdd21.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/7b237582503b3dbd3b0849edae92fdffa2db1129bf076b64f88dc34e0ddbdd21.jpg)

![7f0dc3a08478f8d65956590354944a947661b8ce8aaf2f9b0125ad499dc524c5.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/7f0dc3a08478f8d65956590354944a947661b8ce8aaf2f9b0125ad499dc524c5.jpg)

![82b1034b13fbd9893bbd25f56d987091b65c051b1e45e7d1b6f17422ecb1e837.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/82b1034b13fbd9893bbd25f56d987091b65c051b1e45e7d1b6f17422ecb1e837.jpg)

![8915ffcab59be6f82c692a67414be60501ed7b2b358c12bf349b067d836fea6d.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/8915ffcab59be6f82c692a67414be60501ed7b2b358c12bf349b067d836fea6d.jpg)

![949bb153d5079bdcf70dc73101f45436851bea7b442a1fef2d552945bcaf2eb2.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/949bb153d5079bdcf70dc73101f45436851bea7b442a1fef2d552945bcaf2eb2.jpg)

![94ca980a4591773f57e857fb249a6438950a4ec268ae5bbce31a29947ffcb2f3.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/94ca980a4591773f57e857fb249a6438950a4ec268ae5bbce31a29947ffcb2f3.jpg)

![9b0a9f0936c2d5f95402a0e838bf45ed47491e0e5359f7954baa896459aadddd.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/9b0a9f0936c2d5f95402a0e838bf45ed47491e0e5359f7954baa896459aadddd.jpg)

![9d0ddc9814ca49fe77da5a542f56cc6151ee0dc9eb17efc1d3cf559e42faa902.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/9d0ddc9814ca49fe77da5a542f56cc6151ee0dc9eb17efc1d3cf559e42faa902.jpg)

![a3e6b3b9eacb8cd18eb4314174e92dfb72fbbfff1d0270948ba7ab4b30d18366.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/a3e6b3b9eacb8cd18eb4314174e92dfb72fbbfff1d0270948ba7ab4b30d18366.jpg)

![a8e5877d2bd90e73500ed6a61267ef86215d5518d81b67c731d3fc515db58655.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/a8e5877d2bd90e73500ed6a61267ef86215d5518d81b67c731d3fc515db58655.jpg)

![a8e8d8345efedc1f0e69aa6c87152b7f5bbb09fde5d29d38dd5d4c44eb560ac9.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/a8e8d8345efedc1f0e69aa6c87152b7f5bbb09fde5d29d38dd5d4c44eb560ac9.jpg)

![a9ea00f8a31a993ddd99952b921c84d11123a7ac7a7986b5dd0b633337518607.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/a9ea00f8a31a993ddd99952b921c84d11123a7ac7a7986b5dd0b633337518607.jpg)

![b13d552d9c8808d4cc4081c9b1911f8dd5a418197f3636cf177e3d97536914b3.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/b13d552d9c8808d4cc4081c9b1911f8dd5a418197f3636cf177e3d97536914b3.jpg)

![b1f5420d1b61341f6b335141e1d6cf664143b90bc9ca3942661a953bc5808079.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/b1f5420d1b61341f6b335141e1d6cf664143b90bc9ca3942661a953bc5808079.jpg)

![b2b54725c7de08bde0f67196d959e29f64b6b44ff3e0b868e640b639f4daa799.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/b2b54725c7de08bde0f67196d959e29f64b6b44ff3e0b868e640b639f4daa799.jpg)

![b6d8b5dd2562e8542f2273961321101ff4e7e1e590aa40c700b994382e9da60d.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/b6d8b5dd2562e8542f2273961321101ff4e7e1e590aa40c700b994382e9da60d.jpg)

![b8906b4439f41084ab39bfd6f28274b96057161d59873c8eeb2df82cb37e482c.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/b8906b4439f41084ab39bfd6f28274b96057161d59873c8eeb2df82cb37e482c.jpg)

![c782139f789ab2a7708d8000c9c0466b1436c1f6e88e0c95d9748105fec6de8d.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/c782139f789ab2a7708d8000c9c0466b1436c1f6e88e0c95d9748105fec6de8d.jpg)

![d9fa3cb7762f202ea17c93026ea174ab2647653195a9144d371e04849d45e5b1.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/d9fa3cb7762f202ea17c93026ea174ab2647653195a9144d371e04849d45e5b1.jpg)

![deafb279f6c1fdb5293c2eb549ddd0bb90c5bca414249b68ff8154b430d05a97.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/deafb279f6c1fdb5293c2eb549ddd0bb90c5bca414249b68ff8154b430d05a97.jpg)

![e58d8ab53dac17e828b7c7eb4384b5586ec18de8d185dc0c97266197ff52822b.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/e58d8ab53dac17e828b7c7eb4384b5586ec18de8d185dc0c97266197ff52822b.jpg)

![e6fc7198f4d6a69db763c9b5597211545498db049f78b8e48d0c9bb389972a08.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/e6fc7198f4d6a69db763c9b5597211545498db049f78b8e48d0c9bb389972a08.jpg)

![e796093afd547dbb5244034bec7a37952accc258466f59bb8353ea6bc9731db5.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/e796093afd547dbb5244034bec7a37952accc258466f59bb8353ea6bc9731db5.jpg)

![e7ed18d32f2b5c47211cc5e83b552a6403dc8e68eedd4c8c5fd7194de186cc67.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/e7ed18d32f2b5c47211cc5e83b552a6403dc8e68eedd4c8c5fd7194de186cc67.jpg)

![ee0240cb4cf1f8f8afbaf8ba6d9ddf31f8e78bde9080cf62e03ca712d1fe38bf.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/ee0240cb4cf1f8f8afbaf8ba6d9ddf31f8e78bde9080cf62e03ca712d1fe38bf.jpg)

![ef68216382505a3a387b6b524ec9f27ce63b4ab934d7ca52c5647f22eff855e2.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/ef68216382505a3a387b6b524ec9f27ce63b4ab934d7ca52c5647f22eff855e2.jpg)

![ef840204dc594b0ccf86c3f91cfc2f8912e7280c7bd9d332d5a50a952347a899.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/ef840204dc594b0ccf86c3f91cfc2f8912e7280c7bd9d332d5a50a952347a899.jpg)

![f6faac66490a5b3bf594d8300a128c7f45c04a913a40cc0fc92efd2f6e5591b2.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/f6faac66490a5b3bf594d8300a128c7f45c04a913a40cc0fc92efd2f6e5591b2.jpg)

![fa342739f89d1c38b0936136e1548d6d5144722384ad5f500e95e49d4ec210c6.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/fa342739f89d1c38b0936136e1548d6d5144722384ad5f500e95e49d4ec210c6.jpg)

![fcc22ff3ba4ec6f5e32b1ce90396cec9655d0fef5272b476373eac4d942016a5.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/fcc22ff3ba4ec6f5e32b1ce90396cec9655d0fef5272b476373eac4d942016a5.jpg)

![fdd3e150ce6aba092fab2ca4c5345134fe6aa2e208a44bf448a0854899bb4a63.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/images/fdd3e150ce6aba092fab2ca4c5345134fe6aa2e208a44bf448a0854899bb4a63.jpg)

### Tables

![125b984503a00a90dd467f45ed0a9debc5316f09ea90070ce482e4c7e09bf870.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/tables/125b984503a00a90dd467f45ed0a9debc5316f09ea90070ce482e4c7e09bf870.jpg)

![12a646ecc66e2672cb2eaacc4a3c5245c7cbfd596c783ff9dc9658e4fa4a3b35.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/tables/12a646ecc66e2672cb2eaacc4a3c5245c7cbfd596c783ff9dc9658e4fa4a3b35.jpg)

![34d8635cd1ac33ba764ac9f8d66ac006a6861a3cd1d619eed32bc5c3c160dfa8.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/tables/34d8635cd1ac33ba764ac9f8d66ac006a6861a3cd1d619eed32bc5c3c160dfa8.jpg)

![3b06387574421847dcf76a136250157797ce978a735cde5a72d42ec002e6e647.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/tables/3b06387574421847dcf76a136250157797ce978a735cde5a72d42ec002e6e647.jpg)

![45f80ba54bc74eae3bf8f5b5fc326beb405c7d4c4a1c5e4c04fdc50c12a53b8e.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/tables/45f80ba54bc74eae3bf8f5b5fc326beb405c7d4c4a1c5e4c04fdc50c12a53b8e.jpg)

![7167311911d722fa4600ef7a5473af77fafac1f9ddbc0ce521e35859beb8b9b5.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/tables/7167311911d722fa4600ef7a5473af77fafac1f9ddbc0ce521e35859beb8b9b5.jpg)

![84f9bbaaaa57f2b5bef44c4bdd5da9234b95a5a0ee197798fdbe86e0039dd741.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/tables/84f9bbaaaa57f2b5bef44c4bdd5da9234b95a5a0ee197798fdbe86e0039dd741.jpg)

![93e8de24543e43f807a72e6785e19c793674163706640fe83f370e4e1a90b8c3.jpg](../nips_results/5212_CF-VLM%EF%BC%9ACounterFactual%20Vision-Language%20Fine-tuning/tables/93e8de24543e43f807a72e6785e19c793674163706640fe83f370e4e1a90b8c3.jpg)

## DyFlow: Dynamic Workflow Framework for Agentic Reasoning


### Images

![0193a0aae6e9f6a471c3ae258bc2568651ad89d9b8ac95310037cf3cedba6694.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/images/0193a0aae6e9f6a471c3ae258bc2568651ad89d9b8ac95310037cf3cedba6694.jpg)

![313683b6f9480c02b0dbd7c11db2b3c741c2b2e41da2852cad94f4386baae965.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/images/313683b6f9480c02b0dbd7c11db2b3c741c2b2e41da2852cad94f4386baae965.jpg)

![34c6eb95c48309cf800a5307512cf9947632063fc548b88e0aa910214082411a.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/images/34c6eb95c48309cf800a5307512cf9947632063fc548b88e0aa910214082411a.jpg)

![5a922ec389fe7b677b68fa0fb6a50ea8e9d25d22251fe3e3c9558f200ea82e2c.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/images/5a922ec389fe7b677b68fa0fb6a50ea8e9d25d22251fe3e3c9558f200ea82e2c.jpg)

![911382d11cf3d7bb50b4b4d7c6c2b328aa097a519a78b09c364f2d1d45318a01.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/images/911382d11cf3d7bb50b4b4d7c6c2b328aa097a519a78b09c364f2d1d45318a01.jpg)

![dc9e2ce1d3e9ca48881db37a388af47701fe16634b62d876b4eb9c210e852816.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/images/dc9e2ce1d3e9ca48881db37a388af47701fe16634b62d876b4eb9c210e852816.jpg)

![f897c907b1c2d945efee5860bd2de23b44131786e804a29b78343b2c4a3d39ae.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/images/f897c907b1c2d945efee5860bd2de23b44131786e804a29b78343b2c4a3d39ae.jpg)

### Tables

![128f1d9c825132a5c8f29325d373207ffb8af6deedd0d93e464a568df5607eed.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/tables/128f1d9c825132a5c8f29325d373207ffb8af6deedd0d93e464a568df5607eed.jpg)

![25695e4d919cf9a44d71449a2bd37fa43388b2dc7e9441da66aaa8d90e9e1011.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/tables/25695e4d919cf9a44d71449a2bd37fa43388b2dc7e9441da66aaa8d90e9e1011.jpg)

![30c36aad3726b2a9224d02805bd76748b9ea5acb4105840b4244061c7e12ca39.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/tables/30c36aad3726b2a9224d02805bd76748b9ea5acb4105840b4244061c7e12ca39.jpg)

![32c33a55fcf3b0b64f45009e2221ee95cb799cef47d4f8579b0faf7ffa400f01.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/tables/32c33a55fcf3b0b64f45009e2221ee95cb799cef47d4f8579b0faf7ffa400f01.jpg)

![347b37b97c8ace9445e9fd83e520d5420f7fd73fe009e2b43a99be47d96b88c4.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/tables/347b37b97c8ace9445e9fd83e520d5420f7fd73fe009e2b43a99be47d96b88c4.jpg)

![4c51f26f8898d5ac9ecc7f3725353359196dd3cb55f036d08758caf9440497f6.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/tables/4c51f26f8898d5ac9ecc7f3725353359196dd3cb55f036d08758caf9440497f6.jpg)

![7e0c3bf3d44a6b3beb08a425d821245b5473ac69ea0da5c130251fd7b06f1b37.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/tables/7e0c3bf3d44a6b3beb08a425d821245b5473ac69ea0da5c130251fd7b06f1b37.jpg)

![bdac4e049404174b4aaf22aede6aeaef53f09f7c3dcf051cc1e41a772e34163c.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/tables/bdac4e049404174b4aaf22aede6aeaef53f09f7c3dcf051cc1e41a772e34163c.jpg)

![d65079a37eb8e57c896fe6a9955f047c45e8ca843a7b04e07b346fc613a7c46b.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/tables/d65079a37eb8e57c896fe6a9955f047c45e8ca843a7b04e07b346fc613a7c46b.jpg)

![eedbb9340bb973f4136bf97a71185e9e273c59f04749106285f32e347504917a.jpg](../nips_results/5213_DyFlow_%20Dynamic%20Workflow%20Framework%20for%20Agentic%20Reasoning/tables/eedbb9340bb973f4136bf97a71185e9e273c59f04749106285f32e347504917a.jpg)

## H-SPLID: HSIC-based Saliency Preserving Latent Information Decomposition


### Images

![29726ecb6514e028543d1cb8e537d85fcf609de63025f2f59228138288d03248.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/images/29726ecb6514e028543d1cb8e537d85fcf609de63025f2f59228138288d03248.jpg)

![7d3e53b038ef7fa291f1d2f962cb3822787bcd275ab344b82cd49485630c10bd.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/images/7d3e53b038ef7fa291f1d2f962cb3822787bcd275ab344b82cd49485630c10bd.jpg)

![88f014f3a9a01a8e0944d06d5364feca3ae558bdfff4a1fac2196b5a9881c1f8.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/images/88f014f3a9a01a8e0944d06d5364feca3ae558bdfff4a1fac2196b5a9881c1f8.jpg)

![b38746ce98b9de51aa05e76a6f63c3a4ec493f6d8ff2d480e237fa741b8c6718.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/images/b38746ce98b9de51aa05e76a6f63c3a4ec493f6d8ff2d480e237fa741b8c6718.jpg)

### Tables

![091b67599fedf85a740a7d41e302458303ee18807ce7a728d85b8d86ac954e73.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/091b67599fedf85a740a7d41e302458303ee18807ce7a728d85b8d86ac954e73.jpg)

![184f9d9d2d4ce085eb1a06d9c5a3e9ae7ec7df803486362252dabf31ce36c5df.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/184f9d9d2d4ce085eb1a06d9c5a3e9ae7ec7df803486362252dabf31ce36c5df.jpg)

![20191451f64efc86301641ef91e563e1832b6561843d1be7a792f28240940fa0.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/20191451f64efc86301641ef91e563e1832b6561843d1be7a792f28240940fa0.jpg)

![25fcda60d94d0446787e78429c0e0b5048b1c6348061d2fba248fb243e87d0d9.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/25fcda60d94d0446787e78429c0e0b5048b1c6348061d2fba248fb243e87d0d9.jpg)

![429d293751a692b3fa43b6e69c7e9bc185ac05c9f9c14db6fb4b8115d0dbca54.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/429d293751a692b3fa43b6e69c7e9bc185ac05c9f9c14db6fb4b8115d0dbca54.jpg)

![46771240c9f6cab92df4e16988d99859c93daee7c1dc97df90569aa33a8248ee.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/46771240c9f6cab92df4e16988d99859c93daee7c1dc97df90569aa33a8248ee.jpg)

![5a5d52e60c255e30e2dbe29907b528252c55ce8659d638766b48d4af1ebe7fe5.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/5a5d52e60c255e30e2dbe29907b528252c55ce8659d638766b48d4af1ebe7fe5.jpg)

![621c592362541c353c09b6523eb6260216ed8f2220eeec7aa251329b982fe01c.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/621c592362541c353c09b6523eb6260216ed8f2220eeec7aa251329b982fe01c.jpg)

![684a1925ed62c1e8c8f9545f69f978d227ae09abc287b89c478137838d58e15c.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/684a1925ed62c1e8c8f9545f69f978d227ae09abc287b89c478137838d58e15c.jpg)

![6f4539455873f357976af095e7379919253a9e9ff9c9eaca8a22259f8de6a539.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/6f4539455873f357976af095e7379919253a9e9ff9c9eaca8a22259f8de6a539.jpg)

![7a8e5c789058cc955832889ed4b7fa4781f744becc3fc7c9eca6462f930ad53f.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/7a8e5c789058cc955832889ed4b7fa4781f744becc3fc7c9eca6462f930ad53f.jpg)

![801950184bece7dac9cfa723453f342268283ba0f8906a3a6ef8001206b6c24f.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/801950184bece7dac9cfa723453f342268283ba0f8906a3a6ef8001206b6c24f.jpg)

![a5874ac3cbb52f24f84443aeecad274f936e9dce22e1d6b679c9f397b78f4fc3.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/a5874ac3cbb52f24f84443aeecad274f936e9dce22e1d6b679c9f397b78f4fc3.jpg)

![a914bec9a08d401e4d1e0c3a686784b2449118dddad826eb9f06a1c328aaa4fc.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/a914bec9a08d401e4d1e0c3a686784b2449118dddad826eb9f06a1c328aaa4fc.jpg)

![dcfbd84903de25f34e6d2aae31ab6c95a78523053edc46e571ab319393e8425d.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/dcfbd84903de25f34e6d2aae31ab6c95a78523053edc46e571ab319393e8425d.jpg)

![e85104a541af2dd4dff67bb7385c8b3fecf6989acb63047a2dde757d38fca2d4.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/e85104a541af2dd4dff67bb7385c8b3fecf6989acb63047a2dde757d38fca2d4.jpg)

![f7125c171ccda78cd35e7acc8e90c4a6614f403d6ed00408e0e1836b00aa212e.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/f7125c171ccda78cd35e7acc8e90c4a6614f403d6ed00408e0e1836b00aa212e.jpg)

![fd425235be91d92f941bc68f335b8228254a91fabc6c3368cf3d075be29b11fe.jpg](../nips_results/5214_H-SPLID_%20HSIC-based%20Saliency%20Preserving%20Latent%20Information%20Decomposition/tables/fd425235be91d92f941bc68f335b8228254a91fabc6c3368cf3d075be29b11fe.jpg)

## TensorRL-QAS: Reinforcement learning with tensor networks for improved quantum architecture search


### Images

![036600911cd993a3250261db6dbc795118c144bad4274016c47c842e5d4f011d.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/images/036600911cd993a3250261db6dbc795118c144bad4274016c47c842e5d4f011d.jpg)

![05aef4f82177644b60584c217c91bc75abd23da5dafd05bd5195545c4d56a70e.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/images/05aef4f82177644b60584c217c91bc75abd23da5dafd05bd5195545c4d56a70e.jpg)

![0e0855ed3ef2472f8e3454b40f28d77f30328f06e0ca658718ac0a0f96bf933d.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/images/0e0855ed3ef2472f8e3454b40f28d77f30328f06e0ca658718ac0a0f96bf933d.jpg)

![2525953160ec746ccc84d67903ef4abff6ccda00ef66521a8dc213b4b48d0a74.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/images/2525953160ec746ccc84d67903ef4abff6ccda00ef66521a8dc213b4b48d0a74.jpg)

![2f503fbf2c84014fc963cb8b54872b7ea8d8f33a7bb666f8d7de02502ac295b6.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/images/2f503fbf2c84014fc963cb8b54872b7ea8d8f33a7bb666f8d7de02502ac295b6.jpg)

![5f9dbe8cf730951a4af8ede25fa99b599bdcc8462ea4e88fd4ab639a8cf24e61.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/images/5f9dbe8cf730951a4af8ede25fa99b599bdcc8462ea4e88fd4ab639a8cf24e61.jpg)

![83ba2b301f2e1dc77c35d1535f9371387cc83ec538539a1c1077bd8d1adb5d2d.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/images/83ba2b301f2e1dc77c35d1535f9371387cc83ec538539a1c1077bd8d1adb5d2d.jpg)

![bc70d47890e0eb288945a941224a77c8e0e436037d0f93837a5d2c971048e641.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/images/bc70d47890e0eb288945a941224a77c8e0e436037d0f93837a5d2c971048e641.jpg)

![bd28902528bb859bbfbe9132fabbff5ee735ff1ad650f2cecb2e5617af2b6f85.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/images/bd28902528bb859bbfbe9132fabbff5ee735ff1ad650f2cecb2e5617af2b6f85.jpg)

### Tables

![1e56b9b6b13b0e0cb9008cfd301505c998bc235cf976407f2023ae8299a72b3f.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/1e56b9b6b13b0e0cb9008cfd301505c998bc235cf976407f2023ae8299a72b3f.jpg)

![214dec927cdf4b4f17d0d5e00c405cfa4460048a9a228767e48823d4c71fe0de.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/214dec927cdf4b4f17d0d5e00c405cfa4460048a9a228767e48823d4c71fe0de.jpg)

![24f96c623fde7fa0807e933386d27f522ff478b72b8d219c3a58fdd94b7f666a.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/24f96c623fde7fa0807e933386d27f522ff478b72b8d219c3a58fdd94b7f666a.jpg)

![2caffa58d6fd1035316c530d55aefcc987bd3a3c564ad2726e9cb3e3d3a28e19.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/2caffa58d6fd1035316c530d55aefcc987bd3a3c564ad2726e9cb3e3d3a28e19.jpg)

![36c3af62792b79dd03afbe3ad6922fabe2daa96ee2908a540e9e21a235f61459.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/36c3af62792b79dd03afbe3ad6922fabe2daa96ee2908a540e9e21a235f61459.jpg)

![40aae4092e28fae5adc2d8a85dbed0ada252fb76f5683e99d9a8a37a3d562ca4.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/40aae4092e28fae5adc2d8a85dbed0ada252fb76f5683e99d9a8a37a3d562ca4.jpg)

![4aa89fd772330be6204b7310229020ae03922b58b68f945f961f6333dcf05804.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/4aa89fd772330be6204b7310229020ae03922b58b68f945f961f6333dcf05804.jpg)

![52c5a582899c2d6b63e18a7a7cd8bbd9818cd4cdd8a94954c51595018f41931b.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/52c5a582899c2d6b63e18a7a7cd8bbd9818cd4cdd8a94954c51595018f41931b.jpg)

![6fea1b5598dad1035a82d21127b45e7c9ae744f6eed58bafbc32ac701c554d90.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/6fea1b5598dad1035a82d21127b45e7c9ae744f6eed58bafbc32ac701c554d90.jpg)

![9bc1ab75d944d27f652f955cd473ebc799070553d97a3b72bf207feae876cf39.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/9bc1ab75d944d27f652f955cd473ebc799070553d97a3b72bf207feae876cf39.jpg)

![d6dcd7089fe2c3c0fc3407643d8f903ddbd21c354576021c04a94195cc6c8baf.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/d6dcd7089fe2c3c0fc3407643d8f903ddbd21c354576021c04a94195cc6c8baf.jpg)

![d8815431e957b40774e623dfd6ab9772e27f44311a1e2f127673d762b37d29ce.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/d8815431e957b40774e623dfd6ab9772e27f44311a1e2f127673d762b37d29ce.jpg)

![e927b47c08de0d0096c124f36abf4231baf697725bbba202cd9f91a390ec9dfe.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/e927b47c08de0d0096c124f36abf4231baf697725bbba202cd9f91a390ec9dfe.jpg)

![f970e973a38f81a6665710d09fdf39b3f61e46dc48ad8f41fc554fce78feb224.jpg](../nips_results/5215_TensorRL-QAS_%20Reinforcement%20learning%20with%20tensor%20networks%20for%20improved%20quantum%20architecture%20search/tables/f970e973a38f81a6665710d09fdf39b3f61e46dc48ad8f41fc554fce78feb224.jpg)

## Approximately Aligned Decoding


### Images

![581c3404fe0e44e36bf041950ef135394194c59c57a6852619426e7fb769cd8e.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/images/581c3404fe0e44e36bf041950ef135394194c59c57a6852619426e7fb769cd8e.jpg)

![620ac23824fb11b560665c6f7bd376346c2c106e3ae7379b957a453f7ac2e092.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/images/620ac23824fb11b560665c6f7bd376346c2c106e3ae7379b957a453f7ac2e092.jpg)

![6a78eb6239ad50ee86053f0eb7e561636e5bf9d07622bc904cad3fec402c363a.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/images/6a78eb6239ad50ee86053f0eb7e561636e5bf9d07622bc904cad3fec402c363a.jpg)

![89533146b3c62e89b59a8d120ec63a97837d401cf28dcff72c7bafe7cd8b0af1.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/images/89533146b3c62e89b59a8d120ec63a97837d401cf28dcff72c7bafe7cd8b0af1.jpg)

![8b89689107a274f7cc934575a5e748b3da0bd8a04c70e94acb49db35ce83cbcb.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/images/8b89689107a274f7cc934575a5e748b3da0bd8a04c70e94acb49db35ce83cbcb.jpg)

![f58b46f7181542e2762392affaaa9879628ab1b43728cd67de5aafc497160dfd.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/images/f58b46f7181542e2762392affaaa9879628ab1b43728cd67de5aafc497160dfd.jpg)

### Tables

![07da79c5bd541deed4363f7d8fbf27af667401b5dfeb3954da068442c4be1741.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/07da79c5bd541deed4363f7d8fbf27af667401b5dfeb3954da068442c4be1741.jpg)

![15dd73653e17c8839fc67b12e28ea5d79ec9e0f979b82f5318a270255daefb32.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/15dd73653e17c8839fc67b12e28ea5d79ec9e0f979b82f5318a270255daefb32.jpg)

![178260372f65a7231c324399233ce050d639bbbf7296e14881e9ad7d70edaea1.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/178260372f65a7231c324399233ce050d639bbbf7296e14881e9ad7d70edaea1.jpg)

![1ee4a47324bf27eb3b8ff2451ae6c2b7b8aef850d72c533fae8a428019087380.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/1ee4a47324bf27eb3b8ff2451ae6c2b7b8aef850d72c533fae8a428019087380.jpg)

![1ffa8ca85dea22feb6cb2307118e0dd8f77076be6124976136b56980e3546b9c.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/1ffa8ca85dea22feb6cb2307118e0dd8f77076be6124976136b56980e3546b9c.jpg)

![2df03ddfe279bb8ebe7c4364473194032d171db9633253adaf5c9d11f6565396.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/2df03ddfe279bb8ebe7c4364473194032d171db9633253adaf5c9d11f6565396.jpg)

![3afc0aa56d68d849d80e8961bf33abaea783ea01b627027dc07890a081d05d02.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/3afc0aa56d68d849d80e8961bf33abaea783ea01b627027dc07890a081d05d02.jpg)

![5e54343466509d8ed4c8aed0455a614b6248967fd9c96dbb93938f267b45e218.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/5e54343466509d8ed4c8aed0455a614b6248967fd9c96dbb93938f267b45e218.jpg)

![619406e9fbbcabf6ce5300c64f4d18774379f157d6294f8f1fc22dd4c5620dfa.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/619406e9fbbcabf6ce5300c64f4d18774379f157d6294f8f1fc22dd4c5620dfa.jpg)

![61a87b5eb08bf13538966f7a7eab05d642485a98197df761bd6b6e02ade5bd81.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/61a87b5eb08bf13538966f7a7eab05d642485a98197df761bd6b6e02ade5bd81.jpg)

![64df5031b4ce2c0d24020968a36e5ff2b6180c9124a0dd2abe3f6183cc8f2d23.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/64df5031b4ce2c0d24020968a36e5ff2b6180c9124a0dd2abe3f6183cc8f2d23.jpg)

![728354d70975a8160957f7d9756eef7c7684322d0856e08fa22e88cfb919c133.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/728354d70975a8160957f7d9756eef7c7684322d0856e08fa22e88cfb919c133.jpg)

![9bb004e1b57dd80d5e4dc37f9f2848d46df74007ec00396587f3f702ca051026.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/9bb004e1b57dd80d5e4dc37f9f2848d46df74007ec00396587f3f702ca051026.jpg)

![9bc33568f76dce8b78292c4a09072e19ca82f446e64fa7e889d62fecaa9264f4.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/9bc33568f76dce8b78292c4a09072e19ca82f446e64fa7e889d62fecaa9264f4.jpg)

![a2115df5114993cefe180f54cdd8d1a0618cd914bc34d271d813c3cad0cc52e7.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/a2115df5114993cefe180f54cdd8d1a0618cd914bc34d271d813c3cad0cc52e7.jpg)

![b18804a4241080fc0957a36fdb3b9cf3773c2f7b84468d763a9f1df23fea1677.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/b18804a4241080fc0957a36fdb3b9cf3773c2f7b84468d763a9f1df23fea1677.jpg)

![b2dc8fe21e809b906ddbb59d9f456940d5466d104b4afade27be9770ffbcff9f.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/b2dc8fe21e809b906ddbb59d9f456940d5466d104b4afade27be9770ffbcff9f.jpg)

![c99cdb80a27d5435c9b7e5334cc68d9b625e46ca6834960f92ab1fab6611be2e.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/c99cdb80a27d5435c9b7e5334cc68d9b625e46ca6834960f92ab1fab6611be2e.jpg)

![d1f2d9054a2ab96e8a5c9257ffec6ad861cfacc9a5cecca7a3b80a3f0f61ddfc.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/d1f2d9054a2ab96e8a5c9257ffec6ad861cfacc9a5cecca7a3b80a3f0f61ddfc.jpg)

![d44c9ea121e7ff1bc4d9afd184208acf5beddfb8441589330a246c1bfb7d04e6.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/d44c9ea121e7ff1bc4d9afd184208acf5beddfb8441589330a246c1bfb7d04e6.jpg)

![daf4e201ee6c91e3c0103235e625b70ecfac84563f5307b1ece526691d43e53e.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/daf4e201ee6c91e3c0103235e625b70ecfac84563f5307b1ece526691d43e53e.jpg)

![dfae2e3d8a7f98d969e2c9dc6fc0eef4ad316c43f6a828927af6422e1a1295d9.jpg](../nips_results/5216_Approximately%20Aligned%20Decoding/tables/dfae2e3d8a7f98d969e2c9dc6fc0eef4ad316c43f6a828927af6422e1a1295d9.jpg)

## ComPO: Preference Alignment via Comparison Oracles


### Images

![7d5583daf161b3f7f3e6d1986b7fd918baa2104a217588d236f61f0b9f68c574.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/images/7d5583daf161b3f7f3e6d1986b7fd918baa2104a217588d236f61f0b9f68c574.jpg)

![e71e6cb2f767c6c2e33fdb38d6d51c7a3de8029dbaef3956ab30157c4bf72eff.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/images/e71e6cb2f767c6c2e33fdb38d6d51c7a3de8029dbaef3956ab30157c4bf72eff.jpg)

### Tables

![03db4c271c4a84883692b5c71f8cd5193730b996a643a0e1f5d6ff207eafe9aa.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/03db4c271c4a84883692b5c71f8cd5193730b996a643a0e1f5d6ff207eafe9aa.jpg)

![090cd76ea41b1d855fe7dcc27fad7e116efc1dbf8b5bd01e285d4de2cd493046.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/090cd76ea41b1d855fe7dcc27fad7e116efc1dbf8b5bd01e285d4de2cd493046.jpg)

![237c9d1a3c09e17d17f74b6337ed968cdc7e0ab4a339b090eff9f0841412985a.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/237c9d1a3c09e17d17f74b6337ed968cdc7e0ab4a339b090eff9f0841412985a.jpg)

![392fd564b234ea190b85cc0cf54e2de95eda78bcf31bb147ae3bbfdbe94e90da.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/392fd564b234ea190b85cc0cf54e2de95eda78bcf31bb147ae3bbfdbe94e90da.jpg)

![59d51535846a87ed76990b026a9d48e65bf59c849050f2b7c9abf993b47c16a4.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/59d51535846a87ed76990b026a9d48e65bf59c849050f2b7c9abf993b47c16a4.jpg)

![5b220a3fb2c13ea3f50d09114a8dcf4f29272142f5eea1432b376cd47be8ecee.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/5b220a3fb2c13ea3f50d09114a8dcf4f29272142f5eea1432b376cd47be8ecee.jpg)

![603a9615dfeed59d784cda01c82be6b9737c81d674cb00100dc6f6f517993d1f.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/603a9615dfeed59d784cda01c82be6b9737c81d674cb00100dc6f6f517993d1f.jpg)

![60787f383a024d8440304570f53527864606bc345c40f08b7f5502c30bbc2cac.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/60787f383a024d8440304570f53527864606bc345c40f08b7f5502c30bbc2cac.jpg)

![6fbc692497560f66ed9ddb91f0c178ab8fb66d4cec78daa4d0fe3d7aed81c6b5.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/6fbc692497560f66ed9ddb91f0c178ab8fb66d4cec78daa4d0fe3d7aed81c6b5.jpg)

![71ff5c1bbc8bdfde2a0e7840fcb23956e6adf28e8f1818daf83a83944d8b7ef1.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/71ff5c1bbc8bdfde2a0e7840fcb23956e6adf28e8f1818daf83a83944d8b7ef1.jpg)

![9ebdd662931aca354c8e387bbb154c4be3720f8b96cbbc56d77dc0b1f51e06e8.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/9ebdd662931aca354c8e387bbb154c4be3720f8b96cbbc56d77dc0b1f51e06e8.jpg)

![a131cbdbda933cb38147b88ba2abdfdd2c0510e698925e6557a69f3a68848c49.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/a131cbdbda933cb38147b88ba2abdfdd2c0510e698925e6557a69f3a68848c49.jpg)

![c417a4b5f36f2dcb82d04d94352cd19e9c8f0b6759cea2f17d9319f9fff4249a.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/c417a4b5f36f2dcb82d04d94352cd19e9c8f0b6759cea2f17d9319f9fff4249a.jpg)

![d0d04e03dc19e60663856047ad52a0eabc3dd5a4bacb47ccd59ca642d5b255fd.jpg](../nips_results/5217_ComPO_%20Preference%20Alignment%20via%20Comparison%20Oracles/tables/d0d04e03dc19e60663856047ad52a0eabc3dd5a4bacb47ccd59ca642d5b255fd.jpg)

## Sample-Efficient Multi-Round Generative Data Augmentation for Long-Tail Instance Segmentation


### Images

![1aa025f6e32e5d3b03e57b40728078766ffc1744c1f915b21be6097509d903d8.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/images/1aa025f6e32e5d3b03e57b40728078766ffc1744c1f915b21be6097509d903d8.jpg)

![2db67849e7f1817d36b2e0348f06bf28321b26c9dea1e41045265ef94a49a4d4.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/images/2db67849e7f1817d36b2e0348f06bf28321b26c9dea1e41045265ef94a49a4d4.jpg)

![606d67db537eea9d447053d441460a896d8efd49bc5494b802bc89a9aa1b30e5.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/images/606d67db537eea9d447053d441460a896d8efd49bc5494b802bc89a9aa1b30e5.jpg)

![6527454f9b34cc3ef722c181a6ce00fdabef88e78047b8fe6b429285c0bd1bd5.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/images/6527454f9b34cc3ef722c181a6ce00fdabef88e78047b8fe6b429285c0bd1bd5.jpg)

![8a84d2024d05881ea517722ff69161bc7605abc0e178c4509cbfe396ca561d74.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/images/8a84d2024d05881ea517722ff69161bc7605abc0e178c4509cbfe396ca561d74.jpg)

![a153558c7904cb17c3fc904cfc576e4813a6a411d159117526af971ab7514270.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/images/a153558c7904cb17c3fc904cfc576e4813a6a411d159117526af971ab7514270.jpg)

![b8f37353622c3c9a0efe00c49d29003b892f4cfc7f5992592da777cc483d5f23.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/images/b8f37353622c3c9a0efe00c49d29003b892f4cfc7f5992592da777cc483d5f23.jpg)

### Tables

![130cada8b67c85a33b0853a1d57a2ebd5c649c12262a5c31a1bc569a7f430217.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/tables/130cada8b67c85a33b0853a1d57a2ebd5c649c12262a5c31a1bc569a7f430217.jpg)

![18a24989219e48ce6057bf8c6eae049d5bb341601a1e107f323b85c8383fa45d.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/tables/18a24989219e48ce6057bf8c6eae049d5bb341601a1e107f323b85c8383fa45d.jpg)

![246c2d1b4fb482efca8a0dc1e0919f4ea488f9293e53dfafb1a69fd8a081cf53.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/tables/246c2d1b4fb482efca8a0dc1e0919f4ea488f9293e53dfafb1a69fd8a081cf53.jpg)

![65e977b5663f734fb8fd3ffef2310035c400bd6f3414006b47a8cbb364e41aa6.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/tables/65e977b5663f734fb8fd3ffef2310035c400bd6f3414006b47a8cbb364e41aa6.jpg)

![71651ec378bbae506e7635c66e1bb555f13d0e3b48849f599ce0f42eab0c0bf0.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/tables/71651ec378bbae506e7635c66e1bb555f13d0e3b48849f599ce0f42eab0c0bf0.jpg)

![7bb3a0246daaf649378c35232c34a863b1c910acb420714df3fe29c206632c95.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/tables/7bb3a0246daaf649378c35232c34a863b1c910acb420714df3fe29c206632c95.jpg)

![7e0ccdf428508efc2a1161a22d9b8ca3a4773e22beb4f2c19843780876914b9f.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/tables/7e0ccdf428508efc2a1161a22d9b8ca3a4773e22beb4f2c19843780876914b9f.jpg)

![9b528ebd99e6f2d80a3266913f7a8b94a432313895a1edff677d893295d08d9f.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/tables/9b528ebd99e6f2d80a3266913f7a8b94a432313895a1edff677d893295d08d9f.jpg)

![b8e17fcc9d0281a753e7ad95d88ad6abe41699c30181ce87bc0b1d4a7949e03d.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/tables/b8e17fcc9d0281a753e7ad95d88ad6abe41699c30181ce87bc0b1d4a7949e03d.jpg)

![ba9280f1091a40b371afd4d6b8ae83efcbb1c3ffe95d86bde23c5bb1235b39a6.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/tables/ba9280f1091a40b371afd4d6b8ae83efcbb1c3ffe95d86bde23c5bb1235b39a6.jpg)

![ecd4bbcbe85cff3028cbbc3c5d4dabe141164a36bcf8191fc4b729f56fe7d302.jpg](../nips_results/5218_Sample-Efficient%20Multi-Round%20Generative%20Data%20Augmentation%20for%20Long-Tail%20Instance%20Segmentation/tables/ecd4bbcbe85cff3028cbbc3c5d4dabe141164a36bcf8191fc4b729f56fe7d302.jpg)

## SwS: Self-aware Weakness-driven Problem Synthesis in Reinforcement Learning for LLM Reasoning


### Images

![1b8cf29bcd6cd653e5142e8ed1eec0e7174dc3c1cd075f0e75d82305cd8ed91e.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/1b8cf29bcd6cd653e5142e8ed1eec0e7174dc3c1cd075f0e75d82305cd8ed91e.jpg)

![231a4206a2b67cdd1ef8e121dd1d9bfe7bbc838f8a675f6d17ea75be33b1da7c.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/231a4206a2b67cdd1ef8e121dd1d9bfe7bbc838f8a675f6d17ea75be33b1da7c.jpg)

![2a40855f8513e563e0d29ddeda1f5345df85b190590487bdbb2bda4ccdf6548f.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/2a40855f8513e563e0d29ddeda1f5345df85b190590487bdbb2bda4ccdf6548f.jpg)

![2c79714e47e58e15bc78283f823fde6fb260f4d208c1ebe7508be5632ccd7a90.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/2c79714e47e58e15bc78283f823fde6fb260f4d208c1ebe7508be5632ccd7a90.jpg)

![3d9e8fcb58b92d7e8345fc5053eb4725d0fc751786880e55d9a471ffefa1f961.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/3d9e8fcb58b92d7e8345fc5053eb4725d0fc751786880e55d9a471ffefa1f961.jpg)

![567dece0b1fcb571ee3fd5a43b8ce35ebbf85419b7e3e352d57db9bd388a2050.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/567dece0b1fcb571ee3fd5a43b8ce35ebbf85419b7e3e352d57db9bd388a2050.jpg)

![7a4c6090e040bd658584037cece413e561a1ad57d31aebb6b6934926c61b6761.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/7a4c6090e040bd658584037cece413e561a1ad57d31aebb6b6934926c61b6761.jpg)

![7d5fccf34c42e61cabf7919965d36727e053d71d03f0cbdcc87e6e5eb677b28c.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/7d5fccf34c42e61cabf7919965d36727e053d71d03f0cbdcc87e6e5eb677b28c.jpg)

![af1df9b3fc50b0f1a12d8a0266160568ce8f6c06dde134046c65bd8d60756f29.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/af1df9b3fc50b0f1a12d8a0266160568ce8f6c06dde134046c65bd8d60756f29.jpg)

![bc970e59b8fcf91b0ba83cbd7a51042b88ce396348da5eb9e4729d2197819442.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/bc970e59b8fcf91b0ba83cbd7a51042b88ce396348da5eb9e4729d2197819442.jpg)

![cabc7b5fc743698a48f4fae9079ecf39a951c1235823886995f16ba70d726e54.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/cabc7b5fc743698a48f4fae9079ecf39a951c1235823886995f16ba70d726e54.jpg)

![daa733fa69026ac067c57f9eccd2456fd49c4f57c39dd4450146d11ad27ab0e1.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/images/daa733fa69026ac067c57f9eccd2456fd49c4f57c39dd4450146d11ad27ab0e1.jpg)

### Tables

![27c82dce8926390d9efedcb21d2722415cee242f2d80cc031913cbc722c536a6.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/tables/27c82dce8926390d9efedcb21d2722415cee242f2d80cc031913cbc722c536a6.jpg)

![41d6236d8f9fd139033cb2e99d9fb02b0ef6a6b20a69f47cbf9d5f8d880b620c.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/tables/41d6236d8f9fd139033cb2e99d9fb02b0ef6a6b20a69f47cbf9d5f8d880b620c.jpg)

![435102a19daebc1879ed767f837eed0f427c29ed175f12afd03fac752567a8de.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/tables/435102a19daebc1879ed767f837eed0f427c29ed175f12afd03fac752567a8de.jpg)

![6156ebfe65c6e9fd84e65f27d3a27efc0b9521f0c55a353e9a4377898ad090bb.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/tables/6156ebfe65c6e9fd84e65f27d3a27efc0b9521f0c55a353e9a4377898ad090bb.jpg)

![64e1b8343a4db3a0c8bfcb0279a1c6eb55c8b0fa33b4eea27b55bc911e98ab3b.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/tables/64e1b8343a4db3a0c8bfcb0279a1c6eb55c8b0fa33b4eea27b55bc911e98ab3b.jpg)

![a809355d904905fb4710accb06bee85017549f92dfc5225cb21c98a97ce3913c.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/tables/a809355d904905fb4710accb06bee85017549f92dfc5225cb21c98a97ce3913c.jpg)

![eaf3a450165b8be91fb2ddb17192884bb6eeb0d793ad28214d746e7ce459a046.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/tables/eaf3a450165b8be91fb2ddb17192884bb6eeb0d793ad28214d746e7ce459a046.jpg)

![f663b7be3e9c17330d40612913a8bbaff73a95a2021bc28a194b5bce913a9de9.jpg](../nips_results/5219_SwS_%20Self-aware%20Weakness-driven%20Problem%20Synthesis%20in%20Reinforcement%20Learning%20for%20LLM%20Reasoning/tables/f663b7be3e9c17330d40612913a8bbaff73a95a2021bc28a194b5bce913a9de9.jpg)

## Latent Chain-of-Thought for Visual Reasoning


### Images

![0216908ea5ea08d75ead34859fe991bb4b0d0cdf8e3b2dd9ef06edcecefd13d6.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/0216908ea5ea08d75ead34859fe991bb4b0d0cdf8e3b2dd9ef06edcecefd13d6.jpg)

![110801a0fbb5e8b8f9c82fd65dd9902a2e87abe73b0758a6ee3aa8e8f1e34a94.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/110801a0fbb5e8b8f9c82fd65dd9902a2e87abe73b0758a6ee3aa8e8f1e34a94.jpg)

![218b7b91b726d33557b3eb6682a4877ddc66eaa591696607eeb3985d35f8955e.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/218b7b91b726d33557b3eb6682a4877ddc66eaa591696607eeb3985d35f8955e.jpg)

![332fcc339641bd9058894120601c7b2a75b0f12483f4ecd150e9f9e7f83ca09c.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/332fcc339641bd9058894120601c7b2a75b0f12483f4ecd150e9f9e7f83ca09c.jpg)

![3e2482fb3ba7d64af1b911ed9ff97dcc387ec3184384476c3a52d4fed0255ac1.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/3e2482fb3ba7d64af1b911ed9ff97dcc387ec3184384476c3a52d4fed0255ac1.jpg)

![50ccf7ab5b91d3dfd6800748fdfafd0d1d835e9beba54ea217bdd006597247ed.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/50ccf7ab5b91d3dfd6800748fdfafd0d1d835e9beba54ea217bdd006597247ed.jpg)

![672f232a95c93cf02c479405fb6f2d29ef947a7b83f7c04aa5f202db6e49aef1.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/672f232a95c93cf02c479405fb6f2d29ef947a7b83f7c04aa5f202db6e49aef1.jpg)

![9d29fb28aba1ac11188b7bbb44f46c6f1674cbb5d9c46ab8654f8dbd820f1623.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/9d29fb28aba1ac11188b7bbb44f46c6f1674cbb5d9c46ab8654f8dbd820f1623.jpg)

![9f12c0c941ba1811bbc7c18042579d1558338601d8f7014eb1a7355a038e00a9.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/9f12c0c941ba1811bbc7c18042579d1558338601d8f7014eb1a7355a038e00a9.jpg)

![aa2b363ba95e0b32d05aea0ecb26bbe0707f6d03727e6ecd78a69853314926ec.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/aa2b363ba95e0b32d05aea0ecb26bbe0707f6d03727e6ecd78a69853314926ec.jpg)

![bdb5842d689428099e52e4794fc0ea4f63ae3038702afac2ec9c3f8c3d266d9f.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/bdb5842d689428099e52e4794fc0ea4f63ae3038702afac2ec9c3f8c3d266d9f.jpg)

![f3e41422ea2c9c459a425e1818c5baf160a022dd633ce9cf58a5ba03be588f9f.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/images/f3e41422ea2c9c459a425e1818c5baf160a022dd633ce9cf58a5ba03be588f9f.jpg)

### Tables

![075ae2f9f80125528d6236fbb2e852a71cb0dc713b9eb4c7dc6dd2a7d4660372.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/tables/075ae2f9f80125528d6236fbb2e852a71cb0dc713b9eb4c7dc6dd2a7d4660372.jpg)

![166609b78ff822d86247f16ebfac979dee3aafae2eca34d2422d2d60d1ef6e2e.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/tables/166609b78ff822d86247f16ebfac979dee3aafae2eca34d2422d2d60d1ef6e2e.jpg)

![441295349fe9eb79c37911e1bd3537bb6f65ca4b26909e5697c1c6175b7055fa.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/tables/441295349fe9eb79c37911e1bd3537bb6f65ca4b26909e5697c1c6175b7055fa.jpg)

![4a35259db604aac3a191de645178d5cf09d6a0ea240e268a13402f710d4c3e92.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/tables/4a35259db604aac3a191de645178d5cf09d6a0ea240e268a13402f710d4c3e92.jpg)

![664c0d10aae1b8fd65b7f1ed023fb9736d68761d370d5460fa935c677cf4fbf5.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/tables/664c0d10aae1b8fd65b7f1ed023fb9736d68761d370d5460fa935c677cf4fbf5.jpg)

![66d1b3d55e5e988a8f983eb8d014949ac02d8d0eafc93cb526cf00872370bd76.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/tables/66d1b3d55e5e988a8f983eb8d014949ac02d8d0eafc93cb526cf00872370bd76.jpg)

![6a8de64d41eb031121e6ed5c5addfe498b93df55ca67cc4eaef9f9c8308663bf.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/tables/6a8de64d41eb031121e6ed5c5addfe498b93df55ca67cc4eaef9f9c8308663bf.jpg)

![6ed758745f63662ffbd61537f9e38162a280a7d301757677b01d0961143dce68.jpg](../nips_results/5220_Latent%20Chain-of-Thought%20for%20Visual%20Reasoning/tables/6ed758745f63662ffbd61537f9e38162a280a7d301757677b01d0961143dce68.jpg)

## Dual-Space Semantic Synergy Distillation for Continual Learning of Unlabeled Streams


### Images

![00a2fb165d775823657ab2e9d47eb476a7e608b9465523722f79ae9276cf88f8.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/images/00a2fb165d775823657ab2e9d47eb476a7e608b9465523722f79ae9276cf88f8.jpg)

![0ac315dc74d5f3b2979ec6281691466adcda7797583d0326a95349be6202a5c0.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/images/0ac315dc74d5f3b2979ec6281691466adcda7797583d0326a95349be6202a5c0.jpg)

![174609271b90f48240a6c9c0f5281f920c86592e5b5d600f87b30a63fe88a18a.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/images/174609271b90f48240a6c9c0f5281f920c86592e5b5d600f87b30a63fe88a18a.jpg)

![58701d29cb0a5d87b4d5658e1d336919a3cd3acecbf928e02ae556867d531374.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/images/58701d29cb0a5d87b4d5658e1d336919a3cd3acecbf928e02ae556867d531374.jpg)

![5bf3b58e102b3b52e574109b0a2cef14319198aa9ab62c22cdd7939c193d07e6.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/images/5bf3b58e102b3b52e574109b0a2cef14319198aa9ab62c22cdd7939c193d07e6.jpg)

![5de7b6497e4d49c480f97fca12ced73193ef69b5df55ea6c0bebc9216530c789.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/images/5de7b6497e4d49c480f97fca12ced73193ef69b5df55ea6c0bebc9216530c789.jpg)

![698b441cf5499d90b1d032ff63306cfdb602518d501676203b46e9109a562a53.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/images/698b441cf5499d90b1d032ff63306cfdb602518d501676203b46e9109a562a53.jpg)

### Tables

![1235ac07fa1db8d7262da91f48dfcf89a6ec8bb4cc02ea4524dd2d54932a8cfc.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/tables/1235ac07fa1db8d7262da91f48dfcf89a6ec8bb4cc02ea4524dd2d54932a8cfc.jpg)

![1f6f89bcc9f3cfd84e43eb728e82dadafbeee4ff8f974d757b5d2d1c77a275d6.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/tables/1f6f89bcc9f3cfd84e43eb728e82dadafbeee4ff8f974d757b5d2d1c77a275d6.jpg)

![6ab95a6929262685fae2c3ec217839dc15a34f6774bfcb443ffb0f884c268e78.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/tables/6ab95a6929262685fae2c3ec217839dc15a34f6774bfcb443ffb0f884c268e78.jpg)

![9d28b8909351e6d9c2407511738cc668df2757131c77a1a9de8bdb011a0b9886.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/tables/9d28b8909351e6d9c2407511738cc668df2757131c77a1a9de8bdb011a0b9886.jpg)

![cac47a5ddb791f948ff6cc7b41512e080fa9e4110a5c1512a3add2365bbb3587.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/tables/cac47a5ddb791f948ff6cc7b41512e080fa9e4110a5c1512a3add2365bbb3587.jpg)

![cd8da1426ef21cf454b448693dacdf45dcdc073b676c11b8072a85a4f089db40.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/tables/cd8da1426ef21cf454b448693dacdf45dcdc073b676c11b8072a85a4f089db40.jpg)

![dde5e39261f223b31645ca9cf2ca065447d15083574bb046b27e9d7f16faeba5.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/tables/dde5e39261f223b31645ca9cf2ca065447d15083574bb046b27e9d7f16faeba5.jpg)

![fdff0301a0a774e3258b084e0dd523c10052c1c6420a5dcb1cbb5aeea0b43202.jpg](../nips_results/5221_Dual-Space%20Semantic%20Synergy%20Distillation%20for%20Continual%20Learning%20of%20Unlabeled%20Streams/tables/fdff0301a0a774e3258b084e0dd523c10052c1c6420a5dcb1cbb5aeea0b43202.jpg)

## CoVoMix2: Advancing Zero-Shot Dialogue Generation with Fully Non-Autoregressive Flow Matching


### Images

![3f9ae2f3d3eb374048bbd968a9ba4cee1ff788794b78f48fa6c31b168f0adc61.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/images/3f9ae2f3d3eb374048bbd968a9ba4cee1ff788794b78f48fa6c31b168f0adc61.jpg)

![5a4e3032182e424f6298bb87c66cff84df14f183e81fb56c2d9c18a59dda9a5c.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/images/5a4e3032182e424f6298bb87c66cff84df14f183e81fb56c2d9c18a59dda9a5c.jpg)

![9c8a9be96d87a91c47518b7de7a5963d8b6762195cb733e57af12db4676508cc.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/images/9c8a9be96d87a91c47518b7de7a5963d8b6762195cb733e57af12db4676508cc.jpg)

![9fa124ccf8b877d0b62e07f81020f5143d9b70160f3c667f08e9c1e1c29ad6b7.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/images/9fa124ccf8b877d0b62e07f81020f5143d9b70160f3c667f08e9c1e1c29ad6b7.jpg)

![eac5477b51cf9d6d8819b8cc34f37ced80b359084d2205806397d421b44a1894.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/images/eac5477b51cf9d6d8819b8cc34f37ced80b359084d2205806397d421b44a1894.jpg)

![f547419d9f2189e373ddb5a962ecb05f70bda53d85da79c0b5e10d691fb4a504.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/images/f547419d9f2189e373ddb5a962ecb05f70bda53d85da79c0b5e10d691fb4a504.jpg)

### Tables

![137f985ec0d0ea4ee0885f8c5b5b8fc68ee0c318541b9bd9084b4c10f1e96d70.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/tables/137f985ec0d0ea4ee0885f8c5b5b8fc68ee0c318541b9bd9084b4c10f1e96d70.jpg)

![4126ecfbfd20f07d49de5b452725a01e1ba8a60596f316bf476a208ec049734e.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/tables/4126ecfbfd20f07d49de5b452725a01e1ba8a60596f316bf476a208ec049734e.jpg)

![41e2238f84ba187a7c400e98118ceeb5e8bb5078cffaf4b13a5dcedd21c80d8f.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/tables/41e2238f84ba187a7c400e98118ceeb5e8bb5078cffaf4b13a5dcedd21c80d8f.jpg)

![4d8f44c54219b77321f7a0d99722b2d63e3ba4603480b909ea0dd943b28253c5.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/tables/4d8f44c54219b77321f7a0d99722b2d63e3ba4603480b909ea0dd943b28253c5.jpg)

![5708fb3cd12e30718d8a438ba108edc4483d206e60b69ae0047186e1fd37c706.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/tables/5708fb3cd12e30718d8a438ba108edc4483d206e60b69ae0047186e1fd37c706.jpg)

![6a010a323cc99f01ef2391dac4b34cded17426637f2650afc29ba521395d67f7.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/tables/6a010a323cc99f01ef2391dac4b34cded17426637f2650afc29ba521395d67f7.jpg)

![86e52651bd62f5ef9a445dc502bbde530a3caa0d82b2e624feacbbb2c2d1e34b.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/tables/86e52651bd62f5ef9a445dc502bbde530a3caa0d82b2e624feacbbb2c2d1e34b.jpg)

![e59076b45bd2d653e481854919e922534fb0fdd0db3d9c57be8e5f01c122a838.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/tables/e59076b45bd2d653e481854919e922534fb0fdd0db3d9c57be8e5f01c122a838.jpg)

![f54c0ac1cb6776a12027ddda91e81b1b9857509808b56c560bd7d0e806279898.jpg](../nips_results/5222_CoVoMix2_%20Advancing%20Zero-Shot%20Dialogue%20Generation%20with%20Fully%20Non-Autoregressive%20Flow%20Matching/tables/f54c0ac1cb6776a12027ddda91e81b1b9857509808b56c560bd7d0e806279898.jpg)

## GASP: Efficient Black-Box Generation of Adversarial Suffixes for Jailbreaking LLMs

### Images

![03b09dbe527fbb89144b50c94a2a195b94ba62734f5e1e9ae383338b9a9722f4.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/03b09dbe527fbb89144b50c94a2a195b94ba62734f5e1e9ae383338b9a9722f4.jpg)

![0a53e7b60698a5920873659923623ab6a431046054d4b1a47207df92a0de1f23.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/0a53e7b60698a5920873659923623ab6a431046054d4b1a47207df92a0de1f23.jpg)

![27339f2679551853703a191ff7d98fcb1c15d75fa360cd24de508b720388e2cf.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/27339f2679551853703a191ff7d98fcb1c15d75fa360cd24de508b720388e2cf.jpg)

![3e0a1118f09f5428b98f65a05b24e39b6af41f6c59f3ce51513a69e246dfba06.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/3e0a1118f09f5428b98f65a05b24e39b6af41f6c59f3ce51513a69e246dfba06.jpg)

![447ca653cde642c2758c30d26e9a64c2e898b3f0c9b23f4e84f2e96c2ecefb81.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/447ca653cde642c2758c30d26e9a64c2e898b3f0c9b23f4e84f2e96c2ecefb81.jpg)

![5f346aae72b3da05ad4c43e160df6e8c99715f623aa183da0e64a064c918995f.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/5f346aae72b3da05ad4c43e160df6e8c99715f623aa183da0e64a064c918995f.jpg)

![66b8a2d92f04dc1ac8b047b759da8833a4fe1970232e5525b513d5ec2500471a.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/66b8a2d92f04dc1ac8b047b759da8833a4fe1970232e5525b513d5ec2500471a.jpg)

![8195c129c66e0c5f29ca7b80e887f3e0e5269cdeae3abf5f2fa7de896dc2d835.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/8195c129c66e0c5f29ca7b80e887f3e0e5269cdeae3abf5f2fa7de896dc2d835.jpg)

![9961a5c590c8e7042f0ad01e5b0a64bfbb962606a247a9716d7f8ec616207a2c.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/9961a5c590c8e7042f0ad01e5b0a64bfbb962606a247a9716d7f8ec616207a2c.jpg)

![cc33106258452234b0a3760766a81b86c128387368c03cb5e3c48e730f1b0ace.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/cc33106258452234b0a3760766a81b86c128387368c03cb5e3c48e730f1b0ace.jpg)

![cfb2664c0c025c7a227eced2dc95d78cae2b98840db2ef0eeaa8fee83b0932dc.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/cfb2664c0c025c7a227eced2dc95d78cae2b98840db2ef0eeaa8fee83b0932dc.jpg)

![d87293692c931da0ff8e5d0a7b96844337f54cf8cf474fb982d4a0b6b6ac251d.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/d87293692c931da0ff8e5d0a7b96844337f54cf8cf474fb982d4a0b6b6ac251d.jpg)

![fa0bc1b66e2a5dfb423b076740b606e8d30ce1c4b02e6276d2483b17e44bc14c.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/images/fa0bc1b66e2a5dfb423b076740b606e8d30ce1c4b02e6276d2483b17e44bc14c.jpg)

### Tables

![004f0119e88e9d7e208c535a794b53a0d86d666e67ffcf528d657c818ccc9216.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/tables/004f0119e88e9d7e208c535a794b53a0d86d666e67ffcf528d657c818ccc9216.jpg)

![0b3ff10a3820a2297e97659e1498a791b37b77c8301c7debb0e3c18a7aa4b73d.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/tables/0b3ff10a3820a2297e97659e1498a791b37b77c8301c7debb0e3c18a7aa4b73d.jpg)

![3d1dad5134cc982faebad370ec0c80653d42e5a53c62dead2e1b6e48ddf1a386.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/tables/3d1dad5134cc982faebad370ec0c80653d42e5a53c62dead2e1b6e48ddf1a386.jpg)

![44e0492b43e2c233bde1f0567389f8a8ec6347fe1d8b6af13c826e0e725d5c81.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/tables/44e0492b43e2c233bde1f0567389f8a8ec6347fe1d8b6af13c826e0e725d5c81.jpg)

![6d0b08e1604f55375f1225b62b1593d6f3ff4ab46e99f96d0d35e4536391af6c.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/tables/6d0b08e1604f55375f1225b62b1593d6f3ff4ab46e99f96d0d35e4536391af6c.jpg)

![7494a08049894d3ea6ee280c111a6dc03b0b54d3a7b00b257e4f0c4c7163c06d.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/tables/7494a08049894d3ea6ee280c111a6dc03b0b54d3a7b00b257e4f0c4c7163c06d.jpg)

![77e1949c8f78170d66d945b65caae14e94fcb8eb098743980e90b182fb709045.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/tables/77e1949c8f78170d66d945b65caae14e94fcb8eb098743980e90b182fb709045.jpg)

![89867459174c5ea12fa90f7a56c07a9f443343506b4122403279128ec4cc8292.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/tables/89867459174c5ea12fa90f7a56c07a9f443343506b4122403279128ec4cc8292.jpg)

![b4d5e5d1a621190173d81c2371db2d87095b921e1e17dec293d5f64e200ffcdd.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/tables/b4d5e5d1a621190173d81c2371db2d87095b921e1e17dec293d5f64e200ffcdd.jpg)

![c2eb44f3766c35e7b546d0bb640902f58fb6cd7b16c6215e2dc2d5a404cbe18a.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/tables/c2eb44f3766c35e7b546d0bb640902f58fb6cd7b16c6215e2dc2d5a404cbe18a.jpg)

![f4c82aeadad3fe1be964ecf7e210e6e11e0266e4d092423c4697fcfd2802e7ce.jpg](../nips_results/5223_GASP_%20Efficient%20Black-Box%20Generation%20of%20Adversarial%20Suffixes%20for%20Jailbreaking%20LLMs/tables/f4c82aeadad3fe1be964ecf7e210e6e11e0266e4d092423c4697fcfd2802e7ce.jpg)
