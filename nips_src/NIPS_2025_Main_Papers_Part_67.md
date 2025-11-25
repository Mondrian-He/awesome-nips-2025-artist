# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 67 of 130

## 目录 (Table of Contents)

1. [DeblurDiff: Real-Word Image Deblurring with Generative Diffusion Models](#DeblurDiff-Real-Word-Image-Deblurring-with-Generative-Diffusion-Models)
2. [REVE: A Foundation Model for EEG - Adapting to Any Setup with Large-Scale Pretraining on 25,000 Subjects](#REVE-A-Foundation-Model-for-EEG-Adapting-to-Any-Setup-with-Large-Scale-Pretraining-on-25000-Subjects)
3. [Breaking the Frozen Subspace: Importance Sampling for Low-Rank Optimization in LLM Pretraining](#Breaking-the-Frozen-Subspace-Importance-Sampling-for-Low-Rank-Optimization-in-LLM-Pretraining)
4. [Make Information Diffusion Explainable: LLM-based Causal Framework for Diffusion Prediction](#Make-Information-Diffusion-Explainable-LLM-based-Causal-Framework-for-Diffusion-Prediction)
5. [Causal Discovery over Clusters of Variables in Markovian Systems](#Causal-Discovery-over-Clusters-of-Variables-in-Markovian-Systems)
6. [FLAME: Fast Long-context Adaptive Memory for Event-based Vision](#FLAME-Fast-Long-context-Adaptive-Memory-for-Event-based-Vision)
7. [Diffusion-Driven Progressive Target Manipulation for Source-Free Domain Adaptation](#Diffusion-Driven-Progressive-Target-Manipulation-for-Source-Free-Domain-Adaptation)
8. [Towards Understanding Transformers in Learning Random Walks](#Towards-Understanding-Transformers-in-Learning-Random-Walks)
9. [Optimal Spectral Transitions in High-Dimensional Multi-Index Models](#Optimal-Spectral-Transitions-in-High-Dimensional-Multi-Index-Models)
10. [Direct3D-S2: Gigascale 3D Generation Made Easy with Spatial Sparse Attention](#Direct3D-S2-Gigascale-3D-Generation-Made-Easy-with-Spatial-Sparse-Attention)
11. [CoDA: Coordinated Diffusion Noise Optimization for Whole-Body Manipulation of Articulated Objects](#CoDA-Coordinated-Diffusion-Noise-Optimization-for-Whole-Body-Manipulation-of-Articulated-Objects)
12. [Harnessing the Computation Redundancy in ViTs to Boost Adversarial Transferability](#Harnessing-the-Computation-Redundancy-in-ViTs-to-Boost-Adversarial-Transferability)
13. [Cost-Sensitive Freeze-thaw Bayesian Optimization for Efficient Hyperparameter Tuning](#Cost-Sensitive-Freeze-thaw-Bayesian-Optimization-for-Efficient-Hyperparameter-Tuning)
14. [MRO: Enhancing Reasoning in Diffusion Language Models via Multi-Reward Optimization](#MRO-Enhancing-Reasoning-in-Diffusion-Language-Models-via-Multi-Reward-Optimization)
15. [Seeing through Uncertainty: Robust Task-Oriented Optimization in Visual Navigation](#Seeing-through-Uncertainty-Robust-Task-Oriented-Optimization-in-Visual-Navigation)
16. [SynBrain: Enhancing Visual-to-fMRI Synthesis via Probabilistic Representation Learning](#SynBrain-Enhancing-Visual-to-fMRI-Synthesis-via-Probabilistic-Representation-Learning)
17. [PT-MoE: An Efficient Finetuning Framework for Integrating Mixture-of-Experts into Prompt Tuning](#PT-MoE-An-Efficient-Finetuning-Framework-for-Integrating-Mixture-of-Experts-into-Prompt-Tuning)
18. [PointMapPolicy: Structured Point Cloud Processing for Multi-Modal Imitation Learning](#PointMapPolicy-Structured-Point-Cloud-Processing-for-Multi-Modal-Imitation-Learning)
19. [How to Learn a Star: Binary Classification with Starshaped Polyhedral Sets](#How-to-Learn-a-Star-Binary-Classification-with-Starshaped-Polyhedral-Sets)
20. [GLSim: Detecting Object Hallucinations in LVLMs via Global-Local Similarity](#GLSim-Detecting-Object-Hallucinations-in-LVLMs-via-Global-Local-Similarity)
21. [Uncertainty Quantification for Deep Regression using Contextualised Normalizing Flows](#Uncertainty-Quantification-for-Deep-Regression-using-Contextualised-Normalizing-Flows)
22. [Optimality and NP-Hardness of Transformers in Learning  Markovian Dynamical Functions](#Optimality-and-NP-Hardness-of-Transformers-in-Learning-Markovian-Dynamical-Functions)
23. [Learning to Solve Complex Problems via Dataset Decomposition](#Learning-to-Solve-Complex-Problems-via-Dataset-Decomposition)
24. [Flexible inference for animal learning rules using neural networks](#Flexible-inference-for-animal-learning-rules-using-neural-networks)
25. [SeRL: Self-play Reinforcement Learning for Large Language Models with Limited Data](#SeRL-Self-play-Reinforcement-Learning-for-Large-Language-Models-with-Limited-Data)
26. [The Emergence of Abstract Thought in Large Language Models Beyond Any Language](#The-Emergence-of-Abstract-Thought-in-Large-Language-Models-Beyond-Any-Language)
27. [Speculate Deep and Accurate: Lossless and Training-Free Acceleration for Offloaded LLMs via Substitute Speculative Decoding](#Speculate-Deep-and-Accurate-Lossless-and-Training-Free-Acceleration-for-Offloaded-LLMs-via-Substitute-Speculative-Decoding)
28. [Proximalized Preference Optimization for Diverse Feedback Types: A Decomposed Perspective on DPO](#Proximalized-Preference-Optimization-for-Diverse-Feedback-Types-A-Decomposed-Perspective-on-DPO)
29. [Few-Shot Learning from Gigapixel Images via Hierarchical Vision-Language Alignment and Modeling](#Few-Shot-Learning-from-Gigapixel-Images-via-Hierarchical-Vision-Language-Alignment-and-Modeling)
30. [PaTH Attention: Position Encoding via Accumulating Householder Transformations](#PaTH-Attention-Position-Encoding-via-Accumulating-Householder-Transformations)
31. [ShortListing Model: A Streamlined Simplex Diffusion for Discrete Variable Generation](#ShortListing-Model-A-Streamlined-Simplex-Diffusion-for-Discrete-Variable-Generation)
32. [DiffBreak: Is Diffusion-Based Purification Robust?](#DiffBreak-Is-Diffusion-Based-Purification-Robust)
33. [Generative Model Inversion Through the Lens of the Manifold Hypothesis](#Generative-Model-Inversion-Through-the-Lens-of-the-Manifold-Hypothesis)
34. [Energy Landscape-Aware Vision Transformers: Layerwise Dynamics and Adaptive Task-Specific Training via Hopfield States](#Energy-Landscape-Aware-Vision-Transformers-Layerwise-Dynamics-and-Adaptive-Task-Specific-Training-via-Hopfield-States)
35. [Modeling Cell Dynamics and Interactions with Unbalanced Mean Field Schrödinger Bridge](#Modeling-Cell-Dynamics-and-Interactions-with-Unbalanced-Mean-Field-Schrödinger-Bridge)
36. [GOATex: Geometry & Occlusion-Aware Texturing](#GOATex-Geometry-Occlusion-Aware-Texturing)
37. [Understand Before You Generate: Self-Guided Training for Autoregressive Image Generation](#Understand-Before-You-Generate-Self-Guided-Training-for-Autoregressive-Image-Generation)
38. [Structure-Aware Spectral Sparsification via Uniform Edge Sampling](#Structure-Aware-Spectral-Sparsification-via-Uniform-Edge-Sampling)
39. [SceneDecorator: Towards Scene-Oriented Story Generation with Scene Planning and Scene Consistency](#SceneDecorator-Towards-Scene-Oriented-Story-Generation-with-Scene-Planning-and-Scene-Consistency)
40. [Joint Relational Database Generation via Graph-Conditional Diffusion Models](#Joint-Relational-Database-Generation-via-Graph-Conditional-Diffusion-Models)
41. [Is Your Diffusion Model Actually Denoising?](#Is-Your-Diffusion-Model-Actually-Denoising)

---


## DeblurDiff: Real-Word Image Deblurring with Generative Diffusion Models

### Images

![0505ca0b1875f27cb92ccb524f45084008df2a9fbecb4ec9dcd0c0866134b445.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/0505ca0b1875f27cb92ccb524f45084008df2a9fbecb4ec9dcd0c0866134b445.jpg)

![077b2f46416808c4afe31f12cdd77459737029accaeb35ac06ae52ccde856edd.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/077b2f46416808c4afe31f12cdd77459737029accaeb35ac06ae52ccde856edd.jpg)

![1301a424cbbbe388209cf02bf1ab32be9812e3ba96014df8c111aa094370cccc.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/1301a424cbbbe388209cf02bf1ab32be9812e3ba96014df8c111aa094370cccc.jpg)

![1e5951a166aade32b2ff5b46e5e414ae606a220bafa1c6729317a8f61d7f1354.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/1e5951a166aade32b2ff5b46e5e414ae606a220bafa1c6729317a8f61d7f1354.jpg)

![253a3af87d7ecaa34965497994441de3173794ce6a8fe8c8a4b1ab828ceac7b4.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/253a3af87d7ecaa34965497994441de3173794ce6a8fe8c8a4b1ab828ceac7b4.jpg)

![2654a426343d25db2adc5f78150a8a2e4d4e93f5573ba3d271e5576ca75d8965.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/2654a426343d25db2adc5f78150a8a2e4d4e93f5573ba3d271e5576ca75d8965.jpg)

![38fad5e83d11837c868b131d9ef30ab0b823729fbfeb8d083eee9b384ae90876.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/38fad5e83d11837c868b131d9ef30ab0b823729fbfeb8d083eee9b384ae90876.jpg)

![3d13c122ddf45f57ffb236cc723e7f7038c83f7dd71a8ff2e159a1d3b78bee73.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/3d13c122ddf45f57ffb236cc723e7f7038c83f7dd71a8ff2e159a1d3b78bee73.jpg)

![422b63bfc07161e043d89f742d3f3f8df5f975f1bc988d501954979685d48a7e.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/422b63bfc07161e043d89f742d3f3f8df5f975f1bc988d501954979685d48a7e.jpg)

![42ece82e91a744473e1347685e6eed43bc8d86686179123b84a1f25b61bfd24c.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/42ece82e91a744473e1347685e6eed43bc8d86686179123b84a1f25b61bfd24c.jpg)

![53e467e763635d2315b6ec67513fb0f3865bed5043eb56b3f62f1abd7cec2adf.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/53e467e763635d2315b6ec67513fb0f3865bed5043eb56b3f62f1abd7cec2adf.jpg)

![6ae22c1efc0c428ee4e09a33736fa9feef25957752acf0203c557dceda086f59.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/6ae22c1efc0c428ee4e09a33736fa9feef25957752acf0203c557dceda086f59.jpg)

![6ea82982d187737afb9d305c8e647fc085ae3d1447ec9c77eb8283997e9564b5.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/6ea82982d187737afb9d305c8e647fc085ae3d1447ec9c77eb8283997e9564b5.jpg)

![72833145d4f6b484a08c5250b90cc9899b5a0c7ca37260644a97855939d212b5.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/72833145d4f6b484a08c5250b90cc9899b5a0c7ca37260644a97855939d212b5.jpg)

![a8544a5786d7ec6015a2a4bd6d1242ba0c2425a11d2b824e514ea72f3ba13fe6.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/a8544a5786d7ec6015a2a4bd6d1242ba0c2425a11d2b824e514ea72f3ba13fe6.jpg)

![bb4888e29facd4d7cb7508b4e5dd19555811861f838036bb2149cd56beba0e33.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/bb4888e29facd4d7cb7508b4e5dd19555811861f838036bb2149cd56beba0e33.jpg)

![c168e7d8911722a3642f3315b4ba61317e048ae5cd755512121f827468aa4a32.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/c168e7d8911722a3642f3315b4ba61317e048ae5cd755512121f827468aa4a32.jpg)

![cbcf79a659865ffad31a4c7daea6927942c4a4bf1e77b9b68bf3b24e2719fe8a.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/cbcf79a659865ffad31a4c7daea6927942c4a4bf1e77b9b68bf3b24e2719fe8a.jpg)

![d2fd08284b3f725cee1813fdcd694bd4534a24cfb3b65aa99b14f0196c025a6f.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/d2fd08284b3f725cee1813fdcd694bd4534a24cfb3b65aa99b14f0196c025a6f.jpg)

![d3d6949f03c38bae1724167246b84caee4719ad4b09eaf6b9e159dc340c83e1e.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/d3d6949f03c38bae1724167246b84caee4719ad4b09eaf6b9e159dc340c83e1e.jpg)

![e6419629d3efa68bcc7c68e7665d9af0b587f2ab17a0890655a2ee8ad1ef76c6.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/images/e6419629d3efa68bcc7c68e7665d9af0b587f2ab17a0890655a2ee8ad1ef76c6.jpg)

### Tables

![01b594a40e8295da0873cad5a516389bb41ae6508bbd7e956e80946b6bc690f4.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/tables/01b594a40e8295da0873cad5a516389bb41ae6508bbd7e956e80946b6bc690f4.jpg)

![1c4b3f4931b5c7e86901f55d8a47c895dfc421012cd0c43b4a0f888622d65f98.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/tables/1c4b3f4931b5c7e86901f55d8a47c895dfc421012cd0c43b4a0f888622d65f98.jpg)

![2e645227725b60ae35956295a60ec3a2c5329c96fb65c33666642ddf31cf3923.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/tables/2e645227725b60ae35956295a60ec3a2c5329c96fb65c33666642ddf31cf3923.jpg)

![7a381b13ddc89ebc14f843e94d4ca2df5b4aa15a727ad1bf6c2f84fe2e68278c.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/tables/7a381b13ddc89ebc14f843e94d4ca2df5b4aa15a727ad1bf6c2f84fe2e68278c.jpg)

![df1601ac941a2912b0ed7945eca25bbab07c55edcbd7f007a07bc68443b2fcd9.jpg](../nips_results/2742_Online%20Mixture%20of%20Experts_%20No-Regret%20Learning%20for%20Optimal%20Collective%20Decision-Making/tables/df1601ac941a2912b0ed7945eca25bbab07c55edcbd7f007a07bc68443b2fcd9.jpg)

## DeblurDiff: Real-Word Image Deblurring with Generative Diffusion Models


### Images

![1402625fab0d32d9d55de96a4c46365dabed0a534513ac05307441f7030cb40b.jpg](../nips_results/2743_DeblurDiff_%20Real-Word%20Image%20Deblurring%20with%20Generative%20Diffusion%20Models/images/1402625fab0d32d9d55de96a4c46365dabed0a534513ac05307441f7030cb40b.jpg)

![17d7cd1264decefe12cc177ca01bd09c6960ed16227ea79d8008ac264b54f535.jpg](../nips_results/2743_DeblurDiff_%20Real-Word%20Image%20Deblurring%20with%20Generative%20Diffusion%20Models/images/17d7cd1264decefe12cc177ca01bd09c6960ed16227ea79d8008ac264b54f535.jpg)

![515f5bd228ba5908a4da9abb38f7085c79aaaabf3a5240bc0ec92174ae4c8dcf.jpg](../nips_results/2743_DeblurDiff_%20Real-Word%20Image%20Deblurring%20with%20Generative%20Diffusion%20Models/images/515f5bd228ba5908a4da9abb38f7085c79aaaabf3a5240bc0ec92174ae4c8dcf.jpg)

![5763b753339cac4376ca9be7dcb8f22c640639b4d37452bda671be8d3ba61224.jpg](../nips_results/2743_DeblurDiff_%20Real-Word%20Image%20Deblurring%20with%20Generative%20Diffusion%20Models/images/5763b753339cac4376ca9be7dcb8f22c640639b4d37452bda671be8d3ba61224.jpg)

![8cb5375132c04618eccb90490d99ceb5e90da36461fac9e0485e724a7037e2ee.jpg](../nips_results/2743_DeblurDiff_%20Real-Word%20Image%20Deblurring%20with%20Generative%20Diffusion%20Models/images/8cb5375132c04618eccb90490d99ceb5e90da36461fac9e0485e724a7037e2ee.jpg)

![ad2c0818362b74d8fcb03ef55135523cdf887d48bd355c3fd51e547e4ebec8a8.jpg](../nips_results/2743_DeblurDiff_%20Real-Word%20Image%20Deblurring%20with%20Generative%20Diffusion%20Models/images/ad2c0818362b74d8fcb03ef55135523cdf887d48bd355c3fd51e547e4ebec8a8.jpg)

![cf23cc061ee5e29d8e12c153dd7f15a3942dbdfaa1b11cf7d00b830b3ff6ea7f.jpg](../nips_results/2743_DeblurDiff_%20Real-Word%20Image%20Deblurring%20with%20Generative%20Diffusion%20Models/images/cf23cc061ee5e29d8e12c153dd7f15a3942dbdfaa1b11cf7d00b830b3ff6ea7f.jpg)

![d9d22cf489296c459e44aa8bf8700786a2d8cebb9de77e336941ba2777b46d06.jpg](../nips_results/2743_DeblurDiff_%20Real-Word%20Image%20Deblurring%20with%20Generative%20Diffusion%20Models/images/d9d22cf489296c459e44aa8bf8700786a2d8cebb9de77e336941ba2777b46d06.jpg)

### Tables

![b0aba74596ecc2332c2b3252a957fad70c79002280b3017f73a7de9bf313a894.jpg](../nips_results/2743_DeblurDiff_%20Real-Word%20Image%20Deblurring%20with%20Generative%20Diffusion%20Models/tables/b0aba74596ecc2332c2b3252a957fad70c79002280b3017f73a7de9bf313a894.jpg)

![d873af5040162f78a29dbdf8685edce5e5496bd4708ef2c61187df024d0c2d6b.jpg](../nips_results/2743_DeblurDiff_%20Real-Word%20Image%20Deblurring%20with%20Generative%20Diffusion%20Models/tables/d873af5040162f78a29dbdf8685edce5e5496bd4708ef2c61187df024d0c2d6b.jpg)

## REVE: A Foundation Model for EEG - Adapting to Any Setup with Large-Scale Pretraining on 25,000 Subjects


### Images

![37b76c4bea26d2b6fd179fb53e1a51365a1f08abc467ad65fc1a55c3865bf947.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/images/37b76c4bea26d2b6fd179fb53e1a51365a1f08abc467ad65fc1a55c3865bf947.jpg)

### Tables

![05aa4fac716bb0d71f815216fbe05400578db17fbb6aade04975b1f592113e20.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/05aa4fac716bb0d71f815216fbe05400578db17fbb6aade04975b1f592113e20.jpg)

![05fb7942df49e766784a125bc2c481b2b51ee78e50b84115765506b967e282fd.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/05fb7942df49e766784a125bc2c481b2b51ee78e50b84115765506b967e282fd.jpg)

![0e84a532fb1aef8b2becfb51665674e6fd4a5ccb0b40cbae33255bd2cd0e62d5.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/0e84a532fb1aef8b2becfb51665674e6fd4a5ccb0b40cbae33255bd2cd0e62d5.jpg)

![12552cb5ef345e0ac97a7928a8f115b9ebb3604d5e1b6ae0c426ef0a09d02886.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/12552cb5ef345e0ac97a7928a8f115b9ebb3604d5e1b6ae0c426ef0a09d02886.jpg)

![27eb8472fefada19c675a97ace96c3e607095f9510157c208d95416a6174d0f2.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/27eb8472fefada19c675a97ace96c3e607095f9510157c208d95416a6174d0f2.jpg)

![2f06b766b5de3f8a824e5374f424e79c6fdcf52a0e38f6af2359be3ac38bb783.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/2f06b766b5de3f8a824e5374f424e79c6fdcf52a0e38f6af2359be3ac38bb783.jpg)

![3686c0c16a8b67d758961e2756fedadbac355f3eed6034e0a53e85544dd47d90.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/3686c0c16a8b67d758961e2756fedadbac355f3eed6034e0a53e85544dd47d90.jpg)

![3cc7d2c847f365f514a84b2655d34d645d2b843ff34802c9a737fd3b3b9889c1.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/3cc7d2c847f365f514a84b2655d34d645d2b843ff34802c9a737fd3b3b9889c1.jpg)

![520b989793cf8970a52ccc1e7ea87bec7b9a2caa2f1c5fd8a14962637f4f7d81.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/520b989793cf8970a52ccc1e7ea87bec7b9a2caa2f1c5fd8a14962637f4f7d81.jpg)

![6267a4d84f562e33cd1dd72f13f5b8d798bb8db3ddd4b7972ef794011201beb7.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/6267a4d84f562e33cd1dd72f13f5b8d798bb8db3ddd4b7972ef794011201beb7.jpg)

![632ec6d528fd3e6126da8a8f31be8c502559c52a2b4115becc32d1ac1454165b.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/632ec6d528fd3e6126da8a8f31be8c502559c52a2b4115becc32d1ac1454165b.jpg)

![652c7df152f41858c0815b7e84ae18941af28597613d021e26c35789ad9eb771.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/652c7df152f41858c0815b7e84ae18941af28597613d021e26c35789ad9eb771.jpg)

![8554065ab83fc6ea168fbc8284b46aef3d31dff730366fe3ff0a6e7516afff2e.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/8554065ab83fc6ea168fbc8284b46aef3d31dff730366fe3ff0a6e7516afff2e.jpg)

![8896af55ea6ef5325bf7ae7b8003c4c52841184a26f94fb1eed95729ea343780.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/8896af55ea6ef5325bf7ae7b8003c4c52841184a26f94fb1eed95729ea343780.jpg)

![a3765e9b1c12777fc6c71f97ebe64b598b4304ac8895550cde3909894bc4020f.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/a3765e9b1c12777fc6c71f97ebe64b598b4304ac8895550cde3909894bc4020f.jpg)

![adda279081f7d1f014806a453c541dd5cc9cc9d80297bb81bd3763bda50aff94.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/adda279081f7d1f014806a453c541dd5cc9cc9d80297bb81bd3763bda50aff94.jpg)

![b9526b68119adc45ec2d3d918b7ad6d7f165dbf350e7411ebe5375853e2523cf.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/b9526b68119adc45ec2d3d918b7ad6d7f165dbf350e7411ebe5375853e2523cf.jpg)

![c4bdf8a564220a54226cbb30df96ba8834db8038b73d9c3ea9cf8a2282dd9306.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/c4bdf8a564220a54226cbb30df96ba8834db8038b73d9c3ea9cf8a2282dd9306.jpg)

![e14faf6e899fb154a6e33f7bff1972d2cb9ddac808516ffb3f62007a9f54e531.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/e14faf6e899fb154a6e33f7bff1972d2cb9ddac808516ffb3f62007a9f54e531.jpg)

![f3928ebec5149e9b7be807c6d7eede6e151f52eae65feb5c6eaa809ecdcea218.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/f3928ebec5149e9b7be807c6d7eede6e151f52eae65feb5c6eaa809ecdcea218.jpg)

![fc2f6f7b220dd556518204f2d9e7b232fcb895539512ea9382058989d4283d94.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/fc2f6f7b220dd556518204f2d9e7b232fcb895539512ea9382058989d4283d94.jpg)

![fe785f01944ba6cf32bf16c1a68150d60fb99b867d41c51f5816141caf64f09b.jpg](../nips_results/2744_REVE_%20A%20Foundation%20Model%20for%20EEG%20-%20Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subj/tables/fe785f01944ba6cf32bf16c1a68150d60fb99b867d41c51f5816141caf64f09b.jpg)

## Breaking the Frozen Subspace: Importance Sampling for Low-Rank Optimization in LLM Pretraining


### Images

![0206d530ffad74f6d41e57553c362029beb8afc18be5eb7fe8faf22b1ce20af3.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/0206d530ffad74f6d41e57553c362029beb8afc18be5eb7fe8faf22b1ce20af3.jpg)

![029a04214951aa19347ad1f27a390beda535bf39b76940e21f6410e018ec91be.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/029a04214951aa19347ad1f27a390beda535bf39b76940e21f6410e018ec91be.jpg)

![04e5e1433a9a8099524f8350eabbe4911cd72fbcf173aac1a77d52460735bb7c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/04e5e1433a9a8099524f8350eabbe4911cd72fbcf173aac1a77d52460735bb7c.jpg)

![053dc04947a69092bb01db9cf40356b7994fd0fe582da7467e7bd2f3b928d277.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/053dc04947a69092bb01db9cf40356b7994fd0fe582da7467e7bd2f3b928d277.jpg)

![07fd4d56f2974637449168e21b68dd9982009c66c5db4a4349f771d142dc7369.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/07fd4d56f2974637449168e21b68dd9982009c66c5db4a4349f771d142dc7369.jpg)

![0bc90460af194fb068a193632198e598e949cea6292a87007ad67fed42475502.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/0bc90460af194fb068a193632198e598e949cea6292a87007ad67fed42475502.jpg)

![0c18057c70341e095ec6b74e9fcd8f750f12eada2720aed94e07e4068414d642.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/0c18057c70341e095ec6b74e9fcd8f750f12eada2720aed94e07e4068414d642.jpg)

![0d1adeead092e0a59437c4edef17b66bd567f7db10d6d0c46d8d93e9a77804a2.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/0d1adeead092e0a59437c4edef17b66bd567f7db10d6d0c46d8d93e9a77804a2.jpg)

![0d4949e1f04185011459c6417b36bdc0c081ac016cce486e5f24a3e6aa5c0ab8.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/0d4949e1f04185011459c6417b36bdc0c081ac016cce486e5f24a3e6aa5c0ab8.jpg)

![0d9327ed8c7d37ce3825eb343a84f87eda9e4ffeaf3d5e755f956f18c3af65e0.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/0d9327ed8c7d37ce3825eb343a84f87eda9e4ffeaf3d5e755f956f18c3af65e0.jpg)

![0e400a2628177b2a9fc898ea8c5e9d5769e26b4d35a028effce26b01df1ac565.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/0e400a2628177b2a9fc898ea8c5e9d5769e26b4d35a028effce26b01df1ac565.jpg)

![0e9c25b8db78f86dd7baefee9ee01f73afc2a6879717714e4bc78c48f28e8a32.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/0e9c25b8db78f86dd7baefee9ee01f73afc2a6879717714e4bc78c48f28e8a32.jpg)

![0f5188910f9de48e544e1e5ea9fa48f99e2f723fc61dec8c05bddf243fa2e17d.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/0f5188910f9de48e544e1e5ea9fa48f99e2f723fc61dec8c05bddf243fa2e17d.jpg)

![0fb2d6f51f957888fcd84718cc4798e6b3459b0c0f6239f46dccab9e25c06677.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/0fb2d6f51f957888fcd84718cc4798e6b3459b0c0f6239f46dccab9e25c06677.jpg)

![10b7d0fa5ab8ce35eb6cabdf1b146e505a723a40c35c8c946e307af4abb18335.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/10b7d0fa5ab8ce35eb6cabdf1b146e505a723a40c35c8c946e307af4abb18335.jpg)

![15c4ee819d622da3de2e39807fa826cdbe076cd3c218645c42e9cf185539a3b9.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/15c4ee819d622da3de2e39807fa826cdbe076cd3c218645c42e9cf185539a3b9.jpg)

![1898b904ae98c80b55d4c3e5f268ceb2694d0d3117c0adf7f5c57a5785415ffa.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/1898b904ae98c80b55d4c3e5f268ceb2694d0d3117c0adf7f5c57a5785415ffa.jpg)

![18e260146e00d96dd2749b6fd6e7ef051995edbc4ef951f1e9d73556135d22a1.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/18e260146e00d96dd2749b6fd6e7ef051995edbc4ef951f1e9d73556135d22a1.jpg)

![1c5852d96dab7df708c06175333bd34e7befe239beec4b30b98bfcc8493b6738.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/1c5852d96dab7df708c06175333bd34e7befe239beec4b30b98bfcc8493b6738.jpg)

![1cc163e4c6e90c7d49e4106fc7bfaa7f7e720acaf0954d70a98f99b5d633e089.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/1cc163e4c6e90c7d49e4106fc7bfaa7f7e720acaf0954d70a98f99b5d633e089.jpg)

![208db76a0e72c4106bdfe2ef26b2a60dd5bb017a63222b9ad4a4d71fa5981a41.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/208db76a0e72c4106bdfe2ef26b2a60dd5bb017a63222b9ad4a4d71fa5981a41.jpg)

![2227f8599b72290c12df403938fd4b5a1fd518bf960a7905ce2df4327432ab5b.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/2227f8599b72290c12df403938fd4b5a1fd518bf960a7905ce2df4327432ab5b.jpg)

![2409236f72f1f58d4f56788ed22fe9fa3cc44c21519393d3cdb586ed22faef37.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/2409236f72f1f58d4f56788ed22fe9fa3cc44c21519393d3cdb586ed22faef37.jpg)

![25068fa8cddbccb50d97b692946aca3fdf73c501daca3e512f0cd1acbe46a120.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/25068fa8cddbccb50d97b692946aca3fdf73c501daca3e512f0cd1acbe46a120.jpg)

![285ca427237d5c4e40a41209128ef49c3d62b149e529d3cf30a9e5d5faca51d9.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/285ca427237d5c4e40a41209128ef49c3d62b149e529d3cf30a9e5d5faca51d9.jpg)

![2913779cf59fa2b8d2ae10a2b31c06cb8349a9e73088495db3d267bec755e5b7.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/2913779cf59fa2b8d2ae10a2b31c06cb8349a9e73088495db3d267bec755e5b7.jpg)

![29bb4512e685566106cec55667863d70f0a3f844e31daa99b8fc279419915d95.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/29bb4512e685566106cec55667863d70f0a3f844e31daa99b8fc279419915d95.jpg)

![29c7ff02f546b84bbe83cbaf49af3ec28071c63506a8987f1b0c868638ca9c46.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/29c7ff02f546b84bbe83cbaf49af3ec28071c63506a8987f1b0c868638ca9c46.jpg)

![2e4bf9adcae79157c784cbd88bd0809ec4a54ea6820f48c2827ae583a04cf4ef.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/2e4bf9adcae79157c784cbd88bd0809ec4a54ea6820f48c2827ae583a04cf4ef.jpg)

![2f5632bab400835cd6a3d7f5270eb79218e95e62bd6e621da99e80eb28ea80e7.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/2f5632bab400835cd6a3d7f5270eb79218e95e62bd6e621da99e80eb28ea80e7.jpg)

![2faecf9ef0be5cab794e053e37745c6534ea35511682f005ab8ad5dbb5b78b7c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/2faecf9ef0be5cab794e053e37745c6534ea35511682f005ab8ad5dbb5b78b7c.jpg)

![30a15b33462c25fbc6d0494f5eab8bca70610c4a298174c7b327eeab3835fe88.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/30a15b33462c25fbc6d0494f5eab8bca70610c4a298174c7b327eeab3835fe88.jpg)

![34438c11593593af29d6e4c410d000d15c73fe30eb62fd498a5da7eb8e119779.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/34438c11593593af29d6e4c410d000d15c73fe30eb62fd498a5da7eb8e119779.jpg)

![34c45d684cc6872f48c1ebcc603a8ad3c7cefa0e1ad86059da228596d038ee92.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/34c45d684cc6872f48c1ebcc603a8ad3c7cefa0e1ad86059da228596d038ee92.jpg)

![3578cd1b0a954b6db913dd2f6ff5ba0b0b8099863c42e9db17b1cf777b912057.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/3578cd1b0a954b6db913dd2f6ff5ba0b0b8099863c42e9db17b1cf777b912057.jpg)

![370550c7c2824b643de0b9c27566ae4877756775d6922b415a011bb3180c6732.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/370550c7c2824b643de0b9c27566ae4877756775d6922b415a011bb3180c6732.jpg)

![37116c39c9256c562a17955f15b68790653f731f64f3a415f9fb5c01b6e6677e.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/37116c39c9256c562a17955f15b68790653f731f64f3a415f9fb5c01b6e6677e.jpg)

![3766ef82c070528bf6070fdb2b11b254bb3c5601c38428913e77e94e1696b4e0.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/3766ef82c070528bf6070fdb2b11b254bb3c5601c38428913e77e94e1696b4e0.jpg)

![37b8cc151ba839fae28acf7208eb9b41aa7cf0b4897872f4a1445b5e1bf05070.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/37b8cc151ba839fae28acf7208eb9b41aa7cf0b4897872f4a1445b5e1bf05070.jpg)

![3856e5b5d18a96a83dd4afe81413d96bee56ed83a5f3b7959abb08d875817473.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/3856e5b5d18a96a83dd4afe81413d96bee56ed83a5f3b7959abb08d875817473.jpg)

![3860dd10c5a39dfac4c2fe5870a06ec8ef4f0bf0bb28d7582e8dcb6f941da019.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/3860dd10c5a39dfac4c2fe5870a06ec8ef4f0bf0bb28d7582e8dcb6f941da019.jpg)

![3d74995be9802afc6416334f2d159d13558a76dd2cc027b074d2009e3cc60cc2.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/3d74995be9802afc6416334f2d159d13558a76dd2cc027b074d2009e3cc60cc2.jpg)

![3dfa95b2d5af020bf1adaf7a46e0b8685d88f765a5b058dc297a43736b577ded.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/3dfa95b2d5af020bf1adaf7a46e0b8685d88f765a5b058dc297a43736b577ded.jpg)

![416a565b475354fc7e930373ff6f5d5bb3666fc7264176af4b76ca5896c3feef.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/416a565b475354fc7e930373ff6f5d5bb3666fc7264176af4b76ca5896c3feef.jpg)

![4210c5b78c0de128d0dd9fc3ea7ba2bac398dd79562562f9016a2a6539d91bbf.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/4210c5b78c0de128d0dd9fc3ea7ba2bac398dd79562562f9016a2a6539d91bbf.jpg)

![4438d73dbbe36863b386af84297716cd61e6aa56e1c395c72c5c2d25574f4926.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/4438d73dbbe36863b386af84297716cd61e6aa56e1c395c72c5c2d25574f4926.jpg)

![467acef4171703f91bde5c9f406dc18e68a7141ed652acb077f7fea617a2905a.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/467acef4171703f91bde5c9f406dc18e68a7141ed652acb077f7fea617a2905a.jpg)

![4855b85a57e8612defc5bea0c9f32089afac61e97712dc17993e61d7d051b41c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/4855b85a57e8612defc5bea0c9f32089afac61e97712dc17993e61d7d051b41c.jpg)

![48805950344fb0de606013973d999647b74ccbd7ff5c231a5d0787121c1c9e86.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/48805950344fb0de606013973d999647b74ccbd7ff5c231a5d0787121c1c9e86.jpg)

![4971415f6ffdbac02e571f1be570fe9a2772211d646fc8cb742140b664c8b849.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/4971415f6ffdbac02e571f1be570fe9a2772211d646fc8cb742140b664c8b849.jpg)

![498cf9cb5ea7abd6d800981fffc694e31ea50720ef9eac078d921f550b4d7d8f.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/498cf9cb5ea7abd6d800981fffc694e31ea50720ef9eac078d921f550b4d7d8f.jpg)

![4a147e9ed73d811bf8e467b62bbe79a2431df574b257fbfcfdd1759c9c206ebc.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/4a147e9ed73d811bf8e467b62bbe79a2431df574b257fbfcfdd1759c9c206ebc.jpg)

![4ad0ae544be27c2071b7bd59c1897f653f278df572d62cb931973641554a55f0.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/4ad0ae544be27c2071b7bd59c1897f653f278df572d62cb931973641554a55f0.jpg)

![4b3eab601de05dc4287b4fb59129794074172311bd7bdf661ca9c11563990026.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/4b3eab601de05dc4287b4fb59129794074172311bd7bdf661ca9c11563990026.jpg)

![4c669c47459bbb07dda45709a54ab1e5e4fd8f3c7226b87c8adcdaa3efb8b4f4.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/4c669c47459bbb07dda45709a54ab1e5e4fd8f3c7226b87c8adcdaa3efb8b4f4.jpg)

![5073b6c51c1c7b30014544178266c010569ea43b5659065061623bac387a2dcf.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/5073b6c51c1c7b30014544178266c010569ea43b5659065061623bac387a2dcf.jpg)

![516f2462f911fbfd2acae409ffa548ddc13ffa7962ed049fee1355fe6c12ac3e.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/516f2462f911fbfd2acae409ffa548ddc13ffa7962ed049fee1355fe6c12ac3e.jpg)

![517a799402f44e6e7eca0106d3db83d2a84bc6fd7f50eef64dc73d2e4bbdaef7.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/517a799402f44e6e7eca0106d3db83d2a84bc6fd7f50eef64dc73d2e4bbdaef7.jpg)

![53cffbab70c5085a2e78e6c2aa547a8d7172000bfcf67f73d77e3d5943d9b6f7.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/53cffbab70c5085a2e78e6c2aa547a8d7172000bfcf67f73d77e3d5943d9b6f7.jpg)

![5a47606058ac669cb87a326973469c70d9b1071e97df9fe075c6bca8a1e8456a.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/5a47606058ac669cb87a326973469c70d9b1071e97df9fe075c6bca8a1e8456a.jpg)

![5be31dd9993121f7b07171a5caa196a13001a7cb413c9b3c3477218ad633020c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/5be31dd9993121f7b07171a5caa196a13001a7cb413c9b3c3477218ad633020c.jpg)

![5cddf3e6addf7a890e711c4b7c5d3338430c90e874201d77d98d1fe21bf07576.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/5cddf3e6addf7a890e711c4b7c5d3338430c90e874201d77d98d1fe21bf07576.jpg)

![5e4f0a5188cca7163bf1f9e3f22ad5c525fea399d8487334974b3c32a46aec5f.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/5e4f0a5188cca7163bf1f9e3f22ad5c525fea399d8487334974b3c32a46aec5f.jpg)

![5eb3218b297d9e0592bd6f6a31d3fb65a77ae02d0d3bfc904441f7d338b1e101.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/5eb3218b297d9e0592bd6f6a31d3fb65a77ae02d0d3bfc904441f7d338b1e101.jpg)

![6098eb77882b391dbfd5ed5406fbf526a8246d05bf080cc2744215b23de217c9.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/6098eb77882b391dbfd5ed5406fbf526a8246d05bf080cc2744215b23de217c9.jpg)

![60a05853f1af74d5451d6c1b729b41e112b32228d589dfb1835de839b34e004f.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/60a05853f1af74d5451d6c1b729b41e112b32228d589dfb1835de839b34e004f.jpg)

![6104a7363f3a982d8eb1cf0bc0705aa9a50d41e01a4910011f850554fd992c47.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/6104a7363f3a982d8eb1cf0bc0705aa9a50d41e01a4910011f850554fd992c47.jpg)

![6151dcd4a23437cead339b5ccc1666ccacdc312aa132664b26c78e061b46ea4e.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/6151dcd4a23437cead339b5ccc1666ccacdc312aa132664b26c78e061b46ea4e.jpg)

![68ddfe362bfaef8f61ecb591265cae4355e51682da366e94172973f2b67d52b0.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/68ddfe362bfaef8f61ecb591265cae4355e51682da366e94172973f2b67d52b0.jpg)

![694e9298bca061ec6021e47672b599c477b12c37f9c2f1aca37b388af0280377.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/694e9298bca061ec6021e47672b599c477b12c37f9c2f1aca37b388af0280377.jpg)

![6a494bf2fef5b1ec8719280d6604de68e19096451ef63079caf3ac4e426f51e7.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/6a494bf2fef5b1ec8719280d6604de68e19096451ef63079caf3ac4e426f51e7.jpg)

![6a707ce546a87167bf9aaea71e319636c69ee3b0df2abdcb4fd8e730a1512691.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/6a707ce546a87167bf9aaea71e319636c69ee3b0df2abdcb4fd8e730a1512691.jpg)

![6f4ca558165449c3e2b2acaea08d723065c452e5ecd694d9dd4a6f47bfad9877.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/6f4ca558165449c3e2b2acaea08d723065c452e5ecd694d9dd4a6f47bfad9877.jpg)

![6fb951745a880da1e218880802d43e474a388f0b18f5f8ff3bf2a83d3b60d2c7.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/6fb951745a880da1e218880802d43e474a388f0b18f5f8ff3bf2a83d3b60d2c7.jpg)

![734034a63c3914904a6c53c424a3d69587b48bb3716fb7eab4f049989c2ce540.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/734034a63c3914904a6c53c424a3d69587b48bb3716fb7eab4f049989c2ce540.jpg)

![73537e32f9a59a72263bee74bad5771dc70b15aba297179a064e67a87ff7d343.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/73537e32f9a59a72263bee74bad5771dc70b15aba297179a064e67a87ff7d343.jpg)

![7381c1cb4113888326f65e0f5c70ccd119ea650b7005e3a4c53d9413a1ab78c5.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/7381c1cb4113888326f65e0f5c70ccd119ea650b7005e3a4c53d9413a1ab78c5.jpg)

![739056c382f4e942c6483b3f8104b9162ee64821f4dce88a0c316168230d5d1e.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/739056c382f4e942c6483b3f8104b9162ee64821f4dce88a0c316168230d5d1e.jpg)

![76e10499006754b7362afeb56473209c1d4d4688f92c1ecf1080bcd996c137bc.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/76e10499006754b7362afeb56473209c1d4d4688f92c1ecf1080bcd996c137bc.jpg)

![7745fc8661c08802de0ec2240d2ce623194e2fc4c955af354bb378ad104c990a.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/7745fc8661c08802de0ec2240d2ce623194e2fc4c955af354bb378ad104c990a.jpg)

![778355e1f0b7e09abca7524c2112d3e49c5cfd5227596b9377897c684c240b21.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/778355e1f0b7e09abca7524c2112d3e49c5cfd5227596b9377897c684c240b21.jpg)

![77efc8effffe67b4215dc561a10c14162ccc4c964501d208b0d118794ba5e7c5.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/77efc8effffe67b4215dc561a10c14162ccc4c964501d208b0d118794ba5e7c5.jpg)

![78e8d21e0519b8fb39f1e0b17bd58cd65932d6de59ce56be88d87f326b848c30.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/78e8d21e0519b8fb39f1e0b17bd58cd65932d6de59ce56be88d87f326b848c30.jpg)

![790469dfb95fad9f641cdbb54206d1d8833ce418ddedfa69c49ec6584c83c4da.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/790469dfb95fad9f641cdbb54206d1d8833ce418ddedfa69c49ec6584c83c4da.jpg)

![7912920b50daa85eb21b9720eb69d305dd04ff91e77eef823ed2c1005d7c56af.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/7912920b50daa85eb21b9720eb69d305dd04ff91e77eef823ed2c1005d7c56af.jpg)

![7c3ec889571bc85e5b039bd32d3e52f03bf6ba03925002aa8fc6948f14213e4b.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/7c3ec889571bc85e5b039bd32d3e52f03bf6ba03925002aa8fc6948f14213e4b.jpg)

![7ea6cd769ae5ec6ec896cb2a07d516084e3bbda0a82d5068924262ac5882f436.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/7ea6cd769ae5ec6ec896cb2a07d516084e3bbda0a82d5068924262ac5882f436.jpg)

![7eab66b0a22bc6174aab93bddf86842b12eb6f287a9ea6a9994ebf2e0240883d.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/7eab66b0a22bc6174aab93bddf86842b12eb6f287a9ea6a9994ebf2e0240883d.jpg)

![7fb66e99d29d1a073f3334799af9aeb8ad9d4a1031f051fdf850b0db309c50b4.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/7fb66e99d29d1a073f3334799af9aeb8ad9d4a1031f051fdf850b0db309c50b4.jpg)

![85267c215151f4b2475f979817a53e8731a1ec47ce03ef1ff6403d3ec2fbe124.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/85267c215151f4b2475f979817a53e8731a1ec47ce03ef1ff6403d3ec2fbe124.jpg)

![86c359a6adee7c04680c45a96cff23ea19f5f29977960f39ab60d9af83ee8676.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/86c359a6adee7c04680c45a96cff23ea19f5f29977960f39ab60d9af83ee8676.jpg)

![87356adee3374b8b90af49d40fe7b4fce5add69068a54c3145f047d82446cd4f.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/87356adee3374b8b90af49d40fe7b4fce5add69068a54c3145f047d82446cd4f.jpg)

![886f7d8f3f88fc6904e82a1d5e2cc243fc662d05aacfa7b7ed6ad947d7ecaf29.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/886f7d8f3f88fc6904e82a1d5e2cc243fc662d05aacfa7b7ed6ad947d7ecaf29.jpg)

![89127702dabb255afdb6bbebecbc74a1eb12f9be725c104ca6fb9cb588138278.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/89127702dabb255afdb6bbebecbc74a1eb12f9be725c104ca6fb9cb588138278.jpg)

![90bf742ae9c17966fe6f22845cfeda56104b84e3628d27fcc6fb58b5f723654c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/90bf742ae9c17966fe6f22845cfeda56104b84e3628d27fcc6fb58b5f723654c.jpg)

![92a408d08412e4006a8b404f02881a15b478baed25b8f66af4cc677e7eb17376.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/92a408d08412e4006a8b404f02881a15b478baed25b8f66af4cc677e7eb17376.jpg)

![959662db316c061590e4d3126bb215c3b6bbd64c7168b0fdbc388336387401c4.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/959662db316c061590e4d3126bb215c3b6bbd64c7168b0fdbc388336387401c4.jpg)

![98f7076dbb1cd801e0923319fd8b308a56614b55fe442b60d90ffdab5b953eee.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/98f7076dbb1cd801e0923319fd8b308a56614b55fe442b60d90ffdab5b953eee.jpg)

![9ae4e2f1b5c00eaad7827430a668b294ec89866622d71426509aa959e59ba612.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/9ae4e2f1b5c00eaad7827430a668b294ec89866622d71426509aa959e59ba612.jpg)

![9b36c0a09ecfd6b18ba23d650304cf513f4c7c4ab51c173c8d979fc70ca9b20c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/9b36c0a09ecfd6b18ba23d650304cf513f4c7c4ab51c173c8d979fc70ca9b20c.jpg)

![9ee6bb1d689bf8488c81c44216422edd0a4e68472fc9c7d5f8803ec5493c8e0b.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/9ee6bb1d689bf8488c81c44216422edd0a4e68472fc9c7d5f8803ec5493c8e0b.jpg)

![9f6a4e4bdd86b57eb44f8f6475fe0ac880a14fb918319358456dc122c0ae712a.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/9f6a4e4bdd86b57eb44f8f6475fe0ac880a14fb918319358456dc122c0ae712a.jpg)

![9f93f927179630c29874bc8e39acfb62ef4113e8ff74255fbb65aad14ec52a7d.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/9f93f927179630c29874bc8e39acfb62ef4113e8ff74255fbb65aad14ec52a7d.jpg)

![a113af41f1a9b33447ca1ae526f129ab648027747ce84b78e24442b9f87266ac.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/a113af41f1a9b33447ca1ae526f129ab648027747ce84b78e24442b9f87266ac.jpg)

![a3e10b1092a47316a25779f2fa7b4aa2c3b6be02e3628606b291a00b4276f9fe.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/a3e10b1092a47316a25779f2fa7b4aa2c3b6be02e3628606b291a00b4276f9fe.jpg)

![a45185d457df06ed55378bbd06a642f3344cb9816e2225a270b1917a3aa41127.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/a45185d457df06ed55378bbd06a642f3344cb9816e2225a270b1917a3aa41127.jpg)

![a474031a6d5e018bc13573238739bcda73a547572c2f662b676b18da7c197f28.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/a474031a6d5e018bc13573238739bcda73a547572c2f662b676b18da7c197f28.jpg)

![a9942d19cd58743e602af9203ccae6dbc577d68a757fc8940c64c82ff69dc8fd.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/a9942d19cd58743e602af9203ccae6dbc577d68a757fc8940c64c82ff69dc8fd.jpg)

![ab22e575675b6bf6ae640cfcbb8a0a13773494a2916f2e841b5c4225ae2d1260.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/ab22e575675b6bf6ae640cfcbb8a0a13773494a2916f2e841b5c4225ae2d1260.jpg)

![ac50162f4373a08caef2222b9ec29b045ba92416cceb88393121eaf806a702c7.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/ac50162f4373a08caef2222b9ec29b045ba92416cceb88393121eaf806a702c7.jpg)

![ad6f2e55027c2bc052cf5e971edc1b5f9748850b68385c72bcb24bdf3ac383c0.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/ad6f2e55027c2bc052cf5e971edc1b5f9748850b68385c72bcb24bdf3ac383c0.jpg)

![ada6d360dfe3d391d524baccbbee1b3d00ed56455bc965a84544913ed8d8aee3.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/ada6d360dfe3d391d524baccbbee1b3d00ed56455bc965a84544913ed8d8aee3.jpg)

![adcf9cdd2b061b89e6ec7c2354b3c0e520e70b4ffa68205e5d740deafe92ef63.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/adcf9cdd2b061b89e6ec7c2354b3c0e520e70b4ffa68205e5d740deafe92ef63.jpg)

![aeb12846ece7a457f60930942c94b56fec1b1a7fe4ed48322eed22dd1eca106c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/aeb12846ece7a457f60930942c94b56fec1b1a7fe4ed48322eed22dd1eca106c.jpg)

![aebd149209a4e9e3c35f0486d25755e68ec12917301f936a504b483c7371b39c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/aebd149209a4e9e3c35f0486d25755e68ec12917301f936a504b483c7371b39c.jpg)

![b03c314785dd5d7226042c804d4003e6aab169f91a95c69c4d3b8771b3fdd4a2.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/b03c314785dd5d7226042c804d4003e6aab169f91a95c69c4d3b8771b3fdd4a2.jpg)

![b096a91457409c865eed852161f7a73a6df35d998a2e1c9d6d56fc2199cc00ff.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/b096a91457409c865eed852161f7a73a6df35d998a2e1c9d6d56fc2199cc00ff.jpg)

![b10a43d329cf57b135855596572100c6890573d7fb80bfee9ae16ded77f5820b.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/b10a43d329cf57b135855596572100c6890573d7fb80bfee9ae16ded77f5820b.jpg)

![b1829ae93d703d2c41c36170a60747a016e216f7d1aaa76bb23eb333fb44f791.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/b1829ae93d703d2c41c36170a60747a016e216f7d1aaa76bb23eb333fb44f791.jpg)

![b1d5ca67c373593ed3eb485da7845e0917bd97811ce3577392834a7ed9f859eb.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/b1d5ca67c373593ed3eb485da7845e0917bd97811ce3577392834a7ed9f859eb.jpg)

![b1f791d72c0b050f7f05c1b5ac2407a907c8f66130061443be82f2c74c886981.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/b1f791d72c0b050f7f05c1b5ac2407a907c8f66130061443be82f2c74c886981.jpg)

![b7952a7d4b4fc452f0c814cbe6cfcff7db55312d32396da8b69b9d0b2049e3b7.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/b7952a7d4b4fc452f0c814cbe6cfcff7db55312d32396da8b69b9d0b2049e3b7.jpg)

![b9e40a465452715560096557f43bf73cf71d923d75a5b1f9f98ee8aeff6312af.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/b9e40a465452715560096557f43bf73cf71d923d75a5b1f9f98ee8aeff6312af.jpg)

![baa9f79906ed06f0e52d0384515f3aef432c26a096fd181514a4542f69aab928.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/baa9f79906ed06f0e52d0384515f3aef432c26a096fd181514a4542f69aab928.jpg)

![bda308c650d5fe8a09b073325e71f9700aee5c3e989e188da330ff331a8b5f64.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/bda308c650d5fe8a09b073325e71f9700aee5c3e989e188da330ff331a8b5f64.jpg)

![bdd7adfce0100db5a95ebec6763c7cf51012b30c901d1aa47a884ef8598265e4.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/bdd7adfce0100db5a95ebec6763c7cf51012b30c901d1aa47a884ef8598265e4.jpg)

![bdd8bf37655684d772e9ee8359a69a5eb385ce15bf23e131cf8659b2c383a062.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/bdd8bf37655684d772e9ee8359a69a5eb385ce15bf23e131cf8659b2c383a062.jpg)

![bef12da37872a2ccd54a87a412ffebdc10b1f42030a83fbaa5277af64a91d99f.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/bef12da37872a2ccd54a87a412ffebdc10b1f42030a83fbaa5277af64a91d99f.jpg)

![c24ee4d2adece4e931162aa7269c48a12938a8212840f3ebde84c3f7f636d158.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/c24ee4d2adece4e931162aa7269c48a12938a8212840f3ebde84c3f7f636d158.jpg)

![c2dfa9873c6a8ee48b1672936a544504474ade281b83308677584ac62d4cc8fb.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/c2dfa9873c6a8ee48b1672936a544504474ade281b83308677584ac62d4cc8fb.jpg)

![c508ff622e1db87b9d9d53f8383a1afd6b7dfeaff95019bef37a652412f7261c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/c508ff622e1db87b9d9d53f8383a1afd6b7dfeaff95019bef37a652412f7261c.jpg)

![c5b939065b922c8499f93da15697bc4b35e7709f939744f7e6b3eef6d404c43a.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/c5b939065b922c8499f93da15697bc4b35e7709f939744f7e6b3eef6d404c43a.jpg)

![c75179a20fa70ec9fa27f06c415f87ed5be8eee2831f4cfcb93ee851fd137e64.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/c75179a20fa70ec9fa27f06c415f87ed5be8eee2831f4cfcb93ee851fd137e64.jpg)

![c7b7c1d0fbb04eaf96d7136505779db047d23a603d78c92aa2024bcb4a39e37c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/c7b7c1d0fbb04eaf96d7136505779db047d23a603d78c92aa2024bcb4a39e37c.jpg)

![c8f8af3a40295b8e9b37a66ab7b030d3acb6b6649b8c6350ebb1840d27b42b1f.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/c8f8af3a40295b8e9b37a66ab7b030d3acb6b6649b8c6350ebb1840d27b42b1f.jpg)

![ca8eaccb77472b7149a4a60d5345890185a2a90a798c40c629c21c71f62bd7dc.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/ca8eaccb77472b7149a4a60d5345890185a2a90a798c40c629c21c71f62bd7dc.jpg)

![cb708c9326e330c1f3d4bd80b1fdb754a9acc466a4212fdeaf66cdeb39106a34.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/cb708c9326e330c1f3d4bd80b1fdb754a9acc466a4212fdeaf66cdeb39106a34.jpg)

![ce1aeb75cd9e39eb1806b86927c0b234572046c989827a5f3a85a43808f7bc1c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/ce1aeb75cd9e39eb1806b86927c0b234572046c989827a5f3a85a43808f7bc1c.jpg)

![d02712c7e2520b84186081af1c4ed4001d82261e36bc6e6b4aa2f954dfc00102.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/d02712c7e2520b84186081af1c4ed4001d82261e36bc6e6b4aa2f954dfc00102.jpg)

![d114cb78734aadb1224230960fdf3c1f2dda5eca2cac070563948763bce8f4c2.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/d114cb78734aadb1224230960fdf3c1f2dda5eca2cac070563948763bce8f4c2.jpg)

![d175df078fd83398f8dbb0234b91f8bf1de13d9f05d4206560113ecd7c872c41.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/d175df078fd83398f8dbb0234b91f8bf1de13d9f05d4206560113ecd7c872c41.jpg)

![d2e1b816fb1544ff8eb8eaa0537a9134354fca677856e7edbcb0eef083b3ba09.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/d2e1b816fb1544ff8eb8eaa0537a9134354fca677856e7edbcb0eef083b3ba09.jpg)

![d626572cdf738c00f63b33643e83c02c8f1bdbb97e48777f02350968798f50e3.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/d626572cdf738c00f63b33643e83c02c8f1bdbb97e48777f02350968798f50e3.jpg)

![d6482a7eef899773ef06afe8b8af46a5b319ed296ea713a18379bf92daa6ab06.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/d6482a7eef899773ef06afe8b8af46a5b319ed296ea713a18379bf92daa6ab06.jpg)

![dac385e7cce9e8d7452d9c5ffa56cf78b0d776001b86c43e4bffaf1df5e658c4.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/dac385e7cce9e8d7452d9c5ffa56cf78b0d776001b86c43e4bffaf1df5e658c4.jpg)

![db0cf5af32e4ee894c2da8d90907e4180d7a37591017753b3cef195e9bea048f.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/db0cf5af32e4ee894c2da8d90907e4180d7a37591017753b3cef195e9bea048f.jpg)

![db4dca27e655d36066f824dfee2e6658648b74c324d7086535a89dab85cc5335.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/db4dca27e655d36066f824dfee2e6658648b74c324d7086535a89dab85cc5335.jpg)

![dbc186a6bad8cc1ad19113c2e3b1c5e2ee343942cd63888b1e8c270c745953d6.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/dbc186a6bad8cc1ad19113c2e3b1c5e2ee343942cd63888b1e8c270c745953d6.jpg)

![dcf830e0b77fe8bec6aa7243f51d7c65864e98c25d1843147d2f5a49d747aa26.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/dcf830e0b77fe8bec6aa7243f51d7c65864e98c25d1843147d2f5a49d747aa26.jpg)

![df5cf65618613e51bc9c3145d6b3e79a78ed9d9e019cd78170d60608b6b0b948.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/df5cf65618613e51bc9c3145d6b3e79a78ed9d9e019cd78170d60608b6b0b948.jpg)

![e0b6c6fd31ba33cf65cf6fa59fa5e88db72e8e69e3b9f2281742720e3990405e.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/e0b6c6fd31ba33cf65cf6fa59fa5e88db72e8e69e3b9f2281742720e3990405e.jpg)

![e1774398397794b0461cc44f8d70bfbefda7eacc942180cbc05b31e6a468dab8.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/e1774398397794b0461cc44f8d70bfbefda7eacc942180cbc05b31e6a468dab8.jpg)

![e253ba509f2593e04f9b67909ea212c602641dc2e44075293de84a6c74c92fd1.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/e253ba509f2593e04f9b67909ea212c602641dc2e44075293de84a6c74c92fd1.jpg)

![e36ee390354e5e276c6d17c20b493d53f541ab9c591fa9c281ee92f89f796b2c.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/e36ee390354e5e276c6d17c20b493d53f541ab9c591fa9c281ee92f89f796b2c.jpg)

![e4598c58fb15d9db6101f602203420ca659baffc7b7d570ab38214f3d7f6c030.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/e4598c58fb15d9db6101f602203420ca659baffc7b7d570ab38214f3d7f6c030.jpg)

![e7e5b9025c78fe34dec744b11e90a0b36180d961d8d7a5bbd4cb47f2726d675f.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/e7e5b9025c78fe34dec744b11e90a0b36180d961d8d7a5bbd4cb47f2726d675f.jpg)

![e906a2e772dfa24bdee676fe4662049847f098fda488526d95d06bda50ec2e37.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/e906a2e772dfa24bdee676fe4662049847f098fda488526d95d06bda50ec2e37.jpg)

![e917aa4e7765198a8013a4b91dffb2f83163ad1499d7de2526b5564834857af9.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/e917aa4e7765198a8013a4b91dffb2f83163ad1499d7de2526b5564834857af9.jpg)

![ed3799c5740f7bfb87106321d0744f2e71adee30b5b76ac939f926bd44b15016.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/ed3799c5740f7bfb87106321d0744f2e71adee30b5b76ac939f926bd44b15016.jpg)

![f04537767d1868c7c142960ec21f4f9f97453e19a0596d362030ac2ec3ead087.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/f04537767d1868c7c142960ec21f4f9f97453e19a0596d362030ac2ec3ead087.jpg)

![f097475debb8cef0ea37b979728ad25b8612aa1a4990ce647fd48008eda23293.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/f097475debb8cef0ea37b979728ad25b8612aa1a4990ce647fd48008eda23293.jpg)

![f38780e35f4835b65f9f20b70c80d84a59214ca0a4fd44cfdcc0481bb4f01205.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/f38780e35f4835b65f9f20b70c80d84a59214ca0a4fd44cfdcc0481bb4f01205.jpg)

![f440257ca21d5de55cd3a29165f29ebeb3e068db3327b857d22bdf4b60882a4f.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/f440257ca21d5de55cd3a29165f29ebeb3e068db3327b857d22bdf4b60882a4f.jpg)

![f5562267a3cbf942d9a6fe56e6f4963c8f686f46728f9e81259723ae984f7a3f.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/f5562267a3cbf942d9a6fe56e6f4963c8f686f46728f9e81259723ae984f7a3f.jpg)

![f7588e6392da6a27eba6e6278398fc0c427a8703a1254774f1b95455322dbdda.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/f7588e6392da6a27eba6e6278398fc0c427a8703a1254774f1b95455322dbdda.jpg)

![f7c881a3cdd466a2ce75e9931c08ab95775e92aa1de94bf5a8c2fb24244c4db2.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/f7c881a3cdd466a2ce75e9931c08ab95775e92aa1de94bf5a8c2fb24244c4db2.jpg)

![f7cd7a441f373ff3a4bbeec011be8ab21b765f6ea5d7106f9a299eee420225e8.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/f7cd7a441f373ff3a4bbeec011be8ab21b765f6ea5d7106f9a299eee420225e8.jpg)

![f86f21e9bc69d41b1aefd3b65c7c64cded716bae2509df2d45cc6cd333ce00e2.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/f86f21e9bc69d41b1aefd3b65c7c64cded716bae2509df2d45cc6cd333ce00e2.jpg)

![f8794eba0d2d1cc6e5b0625e818e6b2589e861db1a283d0dedd19b55966fadec.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/f8794eba0d2d1cc6e5b0625e818e6b2589e861db1a283d0dedd19b55966fadec.jpg)

![f94bc4f3b214720e93bd7bf7f89de71e0abcf5db227892e8c3ddf8d22a0f1f32.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/images/f94bc4f3b214720e93bd7bf7f89de71e0abcf5db227892e8c3ddf8d22a0f1f32.jpg)

### Tables

![4b50de16be29c8c485b180ff123a51c3a9ea8976b127370579ef6626e19d6117.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/tables/4b50de16be29c8c485b180ff123a51c3a9ea8976b127370579ef6626e19d6117.jpg)

![4db73195b3d5d807f44a111d88dd2e7ecc1669cfe2673d058877acc7d8ee6d02.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/tables/4db73195b3d5d807f44a111d88dd2e7ecc1669cfe2673d058877acc7d8ee6d02.jpg)

![6350b66f63ea619f2660f00718826515c5a5c16dc410c8084e2e65c425725a8a.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/tables/6350b66f63ea619f2660f00718826515c5a5c16dc410c8084e2e65c425725a8a.jpg)

![8a37ea5c058b61edd5d075a29c7aa3bf74921d175a75d45710922a051df674a6.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/tables/8a37ea5c058b61edd5d075a29c7aa3bf74921d175a75d45710922a051df674a6.jpg)

![d1cba152e74dc96b06b3d9e31a33c167746df622d9609e7c2145b08e7fe5e00f.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/tables/d1cba152e74dc96b06b3d9e31a33c167746df622d9609e7c2145b08e7fe5e00f.jpg)

![fa9cc641c564e8d92976a7f8b3dbefe165f68cc4645d6b5b13b894034ddb77ed.jpg](../nips_results/2745_Breaking%20the%20Frozen%20Subspace_%20Importance%20Sampling%20for%20Low-Rank%20Optimization%20in%20LLM%20Pretraining/tables/fa9cc641c564e8d92976a7f8b3dbefe165f68cc4645d6b5b13b894034ddb77ed.jpg)

## Make Information Diffusion Explainable: LLM-based Causal Framework for Diffusion Prediction


### Images

![11f451795231ca8c36fae0566d39f39c493ca564b5cb53eaa993e332ff96a9e4.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/11f451795231ca8c36fae0566d39f39c493ca564b5cb53eaa993e332ff96a9e4.jpg)

![1afea0ecc1ce932007d4bfd6f3480954c97c7d218f5009a7f1b68a5d70ab919d.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/1afea0ecc1ce932007d4bfd6f3480954c97c7d218f5009a7f1b68a5d70ab919d.jpg)

![2fdf94be0b7b3efb35f142f46c132179f4ad8d063ba6e67d7ac3a09b66240c61.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/2fdf94be0b7b3efb35f142f46c132179f4ad8d063ba6e67d7ac3a09b66240c61.jpg)

![41ef650a9d36e4c2aeb39ba7306c1715d5cd2910c65841c9db642472e0a0300f.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/41ef650a9d36e4c2aeb39ba7306c1715d5cd2910c65841c9db642472e0a0300f.jpg)

![457ca724f78757fc075c4df3590feca9a2cd409dd5b26273274af48fbd7d7baa.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/457ca724f78757fc075c4df3590feca9a2cd409dd5b26273274af48fbd7d7baa.jpg)

![48a18f7507db6eba841d845ab34ffaaee89e347e581eaf7379e0461565939d1b.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/48a18f7507db6eba841d845ab34ffaaee89e347e581eaf7379e0461565939d1b.jpg)

![60a4b71bb6f9008b65d83e415e0a2574e897848ec382d6703a6dfff9945e371d.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/60a4b71bb6f9008b65d83e415e0a2574e897848ec382d6703a6dfff9945e371d.jpg)

![81d7591838f16416d2b29e443c7af325b0a65fe93c538a20b651f417a6219908.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/81d7591838f16416d2b29e443c7af325b0a65fe93c538a20b651f417a6219908.jpg)

![89c850a6c57910002a261a3859864d3840485f2623930635ac2decc7c2ad8a80.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/89c850a6c57910002a261a3859864d3840485f2623930635ac2decc7c2ad8a80.jpg)

![b17116fc37c8e79002dd1959f9fe3440d86e204b850ab0a6adb5aed6b7335219.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/b17116fc37c8e79002dd1959f9fe3440d86e204b850ab0a6adb5aed6b7335219.jpg)

![c88aaadaaa0b74444a521600e820c7bc84a8a1000ede80323f1d5e8b98819c8e.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/c88aaadaaa0b74444a521600e820c7bc84a8a1000ede80323f1d5e8b98819c8e.jpg)

![db3d6fb8f47db6dc384329d1b8b268aacc93e434ae07e004ad2e979e5669a0d2.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/db3d6fb8f47db6dc384329d1b8b268aacc93e434ae07e004ad2e979e5669a0d2.jpg)

![fecf5550a6c89e3570eda7235d092ce0139a61baa090556efbfa183996c35bb1.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/images/fecf5550a6c89e3570eda7235d092ce0139a61baa090556efbfa183996c35bb1.jpg)

### Tables

![58a4659869ad49b0f03aeaa30bf82b19c34aa97a78c9f21f8fa7cf902fe75965.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/tables/58a4659869ad49b0f03aeaa30bf82b19c34aa97a78c9f21f8fa7cf902fe75965.jpg)

![8907d576deadfb19bc1697137bfe082418ffb694c27ca55265fe1d73e9d074fe.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/tables/8907d576deadfb19bc1697137bfe082418ffb694c27ca55265fe1d73e9d074fe.jpg)

![aa4b7e270177a8c1fc6d3f89526e75a925a41a5568907a81612e1a674f081028.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/tables/aa4b7e270177a8c1fc6d3f89526e75a925a41a5568907a81612e1a674f081028.jpg)

![bed47162fb9f0210413a2a74b9b5fda7b601d302fd7791ab985ad39da8e797e8.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/tables/bed47162fb9f0210413a2a74b9b5fda7b601d302fd7791ab985ad39da8e797e8.jpg)

![ddcfbc4ca25e5fe023b1346ea506873f838b18544fef2fb3ed4ba75c185c5c25.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/tables/ddcfbc4ca25e5fe023b1346ea506873f838b18544fef2fb3ed4ba75c185c5c25.jpg)

![ef8702bb7bce54b9c12541f4a7a499f84c869bbbbfd1545a2691a9e813cec10d.jpg](../nips_results/2746_Make%20Information%20Diffusion%20Explainable_%20LLM-based%20Causal%20Framework%20for%20Diffusion%20Prediction/tables/ef8702bb7bce54b9c12541f4a7a499f84c869bbbbfd1545a2691a9e813cec10d.jpg)

## Causal Discovery over Clusters of Variables in Markovian Systems


### Images

![19bd72251f7b6121ca395d56d8f1cd663d816bcff7a8c5a4dce38fd6534513de.jpg](../nips_results/2747_Causal%20Discovery%20over%20Clusters%20of%20Variables%20in%20Markovian%20Systems/images/19bd72251f7b6121ca395d56d8f1cd663d816bcff7a8c5a4dce38fd6534513de.jpg)

![3223aae97dd1c97e21ab455f22cd03b6cee37cf30724f42bbbda93cb5d882665.jpg](../nips_results/2747_Causal%20Discovery%20over%20Clusters%20of%20Variables%20in%20Markovian%20Systems/images/3223aae97dd1c97e21ab455f22cd03b6cee37cf30724f42bbbda93cb5d882665.jpg)

![3818ca224765e9b7318db1337d1e42469788a03b353212e601a6e367eb85c17a.jpg](../nips_results/2747_Causal%20Discovery%20over%20Clusters%20of%20Variables%20in%20Markovian%20Systems/images/3818ca224765e9b7318db1337d1e42469788a03b353212e601a6e367eb85c17a.jpg)

![75dff0c4134974ba26ab19ace2b2a121e4bd08384ff99c5a1d666be5c91b451b.jpg](../nips_results/2747_Causal%20Discovery%20over%20Clusters%20of%20Variables%20in%20Markovian%20Systems/images/75dff0c4134974ba26ab19ace2b2a121e4bd08384ff99c5a1d666be5c91b451b.jpg)

![796d1404eb720a551638a41400e3f2ee4e381859e4c04452e52ffd61c0585aeb.jpg](../nips_results/2747_Causal%20Discovery%20over%20Clusters%20of%20Variables%20in%20Markovian%20Systems/images/796d1404eb720a551638a41400e3f2ee4e381859e4c04452e52ffd61c0585aeb.jpg)

![95f0daeddb92e6caa531fa26fa17fc14d2c689531b5b61927a54a6565e8e03e4.jpg](../nips_results/2747_Causal%20Discovery%20over%20Clusters%20of%20Variables%20in%20Markovian%20Systems/images/95f0daeddb92e6caa531fa26fa17fc14d2c689531b5b61927a54a6565e8e03e4.jpg)

![d7191cd162711bd1171411d2fd3932224dd9760c21f8c1764c91e57fde20382b.jpg](../nips_results/2747_Causal%20Discovery%20over%20Clusters%20of%20Variables%20in%20Markovian%20Systems/images/d7191cd162711bd1171411d2fd3932224dd9760c21f8c1764c91e57fde20382b.jpg)

![dcb5e3be04cd32886667f6094dd9ec6cc7798535b40ed47e8e1f1a83546c8bb4.jpg](../nips_results/2747_Causal%20Discovery%20over%20Clusters%20of%20Variables%20in%20Markovian%20Systems/images/dcb5e3be04cd32886667f6094dd9ec6cc7798535b40ed47e8e1f1a83546c8bb4.jpg)

![ff232a2ce47989b726516811835d7213e7dfbc5f85352df24bd3c17cee5a20cb.jpg](../nips_results/2747_Causal%20Discovery%20over%20Clusters%20of%20Variables%20in%20Markovian%20Systems/images/ff232a2ce47989b726516811835d7213e7dfbc5f85352df24bd3c17cee5a20cb.jpg)

## FLAME: Fast Long-context Adaptive Memory for Event-based Vision


### Images

![0d2cdd0625105984490c68f4c2d04f6af20a22494c71902a23dd74441c569f5e.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/images/0d2cdd0625105984490c68f4c2d04f6af20a22494c71902a23dd74441c569f5e.jpg)

![2c0743fb71311b6880438e6e9e0ef0006f22ca78dc3d83bb46a250427d5e8c04.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/images/2c0743fb71311b6880438e6e9e0ef0006f22ca78dc3d83bb46a250427d5e8c04.jpg)

![4e7833ce060884d1b37631c19b1f6c80be3a8cd92a42923a312787b8100a2b2b.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/images/4e7833ce060884d1b37631c19b1f6c80be3a8cd92a42923a312787b8100a2b2b.jpg)

![b18992743343cdc6203bfaf84b0b174b05b5f67f8aaf58bef7a8fa32e24e2254.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/images/b18992743343cdc6203bfaf84b0b174b05b5f67f8aaf58bef7a8fa32e24e2254.jpg)

![ee14cd181bf76d15ecb47342b89ce8fb1ac7d10ca3c89e0930e411348c38c339.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/images/ee14cd181bf76d15ecb47342b89ce8fb1ac7d10ca3c89e0930e411348c38c339.jpg)

### Tables

![0b06a106baf9c4220562a0544af46d37f2a1295956b8d61d462ae4297d4719f7.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/0b06a106baf9c4220562a0544af46d37f2a1295956b8d61d462ae4297d4719f7.jpg)

![2b1d15a76ebf17da86313dfd0d10ac5c17f21031d2d0567ad3553c5f6f8aa97e.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/2b1d15a76ebf17da86313dfd0d10ac5c17f21031d2d0567ad3553c5f6f8aa97e.jpg)

![388f9ba263282896eec3a6ae95ee01fe4bfa7be19dfd7cc6dce8f07dc0de3b74.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/388f9ba263282896eec3a6ae95ee01fe4bfa7be19dfd7cc6dce8f07dc0de3b74.jpg)

![794221fdcfa455253db64abf99b4e80e312a55a73266b83ecae8009074b2dcbb.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/794221fdcfa455253db64abf99b4e80e312a55a73266b83ecae8009074b2dcbb.jpg)

![7b00602a168780edb32b17f6342dc54493acd2f0bed8e17792bcfc13dac97940.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/7b00602a168780edb32b17f6342dc54493acd2f0bed8e17792bcfc13dac97940.jpg)

![8566024f9b8bde0ef9803cf263a2c38eb525b5e22e14e3f2c63e42788de7b0eb.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/8566024f9b8bde0ef9803cf263a2c38eb525b5e22e14e3f2c63e42788de7b0eb.jpg)

![8dddef23fcc3e2e3496d46fa4ae3d8b0ab2ac487a1e5cb9e7cbbdb6079f6ed92.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/8dddef23fcc3e2e3496d46fa4ae3d8b0ab2ac487a1e5cb9e7cbbdb6079f6ed92.jpg)

![9661d50eb6ff2725267545cd4370e1e86af11e05143ad62a661c9802a034c7ba.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/9661d50eb6ff2725267545cd4370e1e86af11e05143ad62a661c9802a034c7ba.jpg)

![b97588afa50071619358d7fbf53de2a72a724c3afb7a489cd666b845c1089e00.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/b97588afa50071619358d7fbf53de2a72a724c3afb7a489cd666b845c1089e00.jpg)

![d5beba828c32c9174582efdfa16d510dbb73da112f6fbef8760ec5bc4acb9d6a.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/d5beba828c32c9174582efdfa16d510dbb73da112f6fbef8760ec5bc4acb9d6a.jpg)

![e1b71c6845995472380fe8512187856989d9ea5068de96b35512f75aebf9e582.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/e1b71c6845995472380fe8512187856989d9ea5068de96b35512f75aebf9e582.jpg)

![f1e68eee63eaf0f5dfd9c4ecc37c1f99eb454af9e1e14dedd1ed92dff82d52dd.jpg](../nips_results/2748_FLAME_%20Fast%20Long-context%20Adaptive%20Memory%20for%20Event-based%20Vision/tables/f1e68eee63eaf0f5dfd9c4ecc37c1f99eb454af9e1e14dedd1ed92dff82d52dd.jpg)

## Diffusion-Driven Progressive Target Manipulation for Source-Free Domain Adaptation


### Images

![353fd28ded80d494bc6991de376ed4091df0a5a40e0a21753b1ec11ae2aa9453.jpg](../nips_results/2749_Diffusion-Driven%20Progressive%20Target%20Manipulation%20for%20Source-Free%20Domain%20Adaptation/images/353fd28ded80d494bc6991de376ed4091df0a5a40e0a21753b1ec11ae2aa9453.jpg)

![3b307baffab969f690baff8aa3fdac768161ad273fcf8ecf70cf4b462b634fe4.jpg](../nips_results/2749_Diffusion-Driven%20Progressive%20Target%20Manipulation%20for%20Source-Free%20Domain%20Adaptation/images/3b307baffab969f690baff8aa3fdac768161ad273fcf8ecf70cf4b462b634fe4.jpg)

![6406eab350c7c7728c97aebbdd4dca0f6ea0dadc2bd04fe2a6302221a290f1c3.jpg](../nips_results/2749_Diffusion-Driven%20Progressive%20Target%20Manipulation%20for%20Source-Free%20Domain%20Adaptation/images/6406eab350c7c7728c97aebbdd4dca0f6ea0dadc2bd04fe2a6302221a290f1c3.jpg)

### Tables

![077d31036a688d9f83dfcbe6580dbc23965615ee1274f8635970cce13298c8a8.jpg](../nips_results/2749_Diffusion-Driven%20Progressive%20Target%20Manipulation%20for%20Source-Free%20Domain%20Adaptation/tables/077d31036a688d9f83dfcbe6580dbc23965615ee1274f8635970cce13298c8a8.jpg)

![31df3c290932e35eb874cd465a2c8f01346024864ef70bc2529f4b6989610ec4.jpg](../nips_results/2749_Diffusion-Driven%20Progressive%20Target%20Manipulation%20for%20Source-Free%20Domain%20Adaptation/tables/31df3c290932e35eb874cd465a2c8f01346024864ef70bc2529f4b6989610ec4.jpg)

![4aa8d6150f4f96de3be5eb5637f92b3b9cddfaa342b3dd02f66e9339b383eb69.jpg](../nips_results/2749_Diffusion-Driven%20Progressive%20Target%20Manipulation%20for%20Source-Free%20Domain%20Adaptation/tables/4aa8d6150f4f96de3be5eb5637f92b3b9cddfaa342b3dd02f66e9339b383eb69.jpg)

![7b44be7078955572ea99d3ae4537746e593b4b104a981d88e93c4b52e8df8fd6.jpg](../nips_results/2749_Diffusion-Driven%20Progressive%20Target%20Manipulation%20for%20Source-Free%20Domain%20Adaptation/tables/7b44be7078955572ea99d3ae4537746e593b4b104a981d88e93c4b52e8df8fd6.jpg)

![a85bf932aca1a4e217dc56639e7e770b06c1077ed468ddb63f79017b591f248f.jpg](../nips_results/2749_Diffusion-Driven%20Progressive%20Target%20Manipulation%20for%20Source-Free%20Domain%20Adaptation/tables/a85bf932aca1a4e217dc56639e7e770b06c1077ed468ddb63f79017b591f248f.jpg)

![f72e7b373c3388d37d109c5e794bfa31e293151e3222a3a6e09e3d35a0d6f93b.jpg](../nips_results/2749_Diffusion-Driven%20Progressive%20Target%20Manipulation%20for%20Source-Free%20Domain%20Adaptation/tables/f72e7b373c3388d37d109c5e794bfa31e293151e3222a3a6e09e3d35a0d6f93b.jpg)

## Towards Understanding Transformers in Learning Random Walks


### Images

![0517900f97ab192fbeff665d70d161c5ee3eb1faed7b2221c556d59f0a7ee2f4.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/0517900f97ab192fbeff665d70d161c5ee3eb1faed7b2221c556d59f0a7ee2f4.jpg)

![1faff693554165859ba345293a8ca7c9a3b300591c424ba0351248a795260948.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/1faff693554165859ba345293a8ca7c9a3b300591c424ba0351248a795260948.jpg)

![339c6cbb753dd3871cfb6fe0a1afba85106fed0e79bce98d533a4f25e07db3c5.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/339c6cbb753dd3871cfb6fe0a1afba85106fed0e79bce98d533a4f25e07db3c5.jpg)

![4f30fcf868c5e204cbf768aa536b9f3ad912e5ada5e9c128bcbcff78cd9c7f10.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/4f30fcf868c5e204cbf768aa536b9f3ad912e5ada5e9c128bcbcff78cd9c7f10.jpg)

![58190261e6c5cb6315e98ce8c0185777fa69ce313a5b69a9f14415bba42ea983.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/58190261e6c5cb6315e98ce8c0185777fa69ce313a5b69a9f14415bba42ea983.jpg)

![84ef62c9837efa2a075eb0b5ee043ced66334a0897ffb2220f9916f3c9a8816e.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/84ef62c9837efa2a075eb0b5ee043ced66334a0897ffb2220f9916f3c9a8816e.jpg)

![a86a9406141eedc368842d9d55d7dee8d0205f0700f65aa040792ddfc1a2475a.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/a86a9406141eedc368842d9d55d7dee8d0205f0700f65aa040792ddfc1a2475a.jpg)

![b0b0977e47d75df2d62a5e668c8534dd8cd206bd0a79d80df9a2097e63511994.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/b0b0977e47d75df2d62a5e668c8534dd8cd206bd0a79d80df9a2097e63511994.jpg)

![b42ac66aa354455bfb33188f9d61ed454e99d897c567c49c0cea659e5d9abb7d.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/b42ac66aa354455bfb33188f9d61ed454e99d897c567c49c0cea659e5d9abb7d.jpg)

![b458e4e98da5d8cfd8be8b3508236ffb05fa6cc372d23e71b580ef40b549d72a.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/b458e4e98da5d8cfd8be8b3508236ffb05fa6cc372d23e71b580ef40b549d72a.jpg)

![d1388632cadffa5b7679a3688c3e8aa31e250c936610c8ba4713fdd90373f7ff.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/d1388632cadffa5b7679a3688c3e8aa31e250c936610c8ba4713fdd90373f7ff.jpg)

![e1a5bd1fa49b24dbe7387f9e34eda546c6103f42f337f3c6ce484a4f3e480ed2.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/e1a5bd1fa49b24dbe7387f9e34eda546c6103f42f337f3c6ce484a4f3e480ed2.jpg)

![fdb37a6598fb4c0b4b00aa578639db81452e66836b4425da44137d8c001f12b2.jpg](../nips_results/2750_Towards%20Understanding%20Transformers%20in%20Learning%20Random%20Walks/images/fdb37a6598fb4c0b4b00aa578639db81452e66836b4425da44137d8c001f12b2.jpg)

## Optimal Spectral Transitions in High-Dimensional Multi-Index Models


### Images

![10c4a4c962f830a806024ac2a823f3c828529ff2cdf8f0dfba885313c5a701fa.jpg](../nips_results/2751_Optimal%20Spectral%20Transitions%20in%20High-Dimensional%20Multi-Index%20Models/images/10c4a4c962f830a806024ac2a823f3c828529ff2cdf8f0dfba885313c5a701fa.jpg)

![4e754ccf9137f422be8c0b0bfdad37146d8b1f1d165965f2419bae01d11486f1.jpg](../nips_results/2751_Optimal%20Spectral%20Transitions%20in%20High-Dimensional%20Multi-Index%20Models/images/4e754ccf9137f422be8c0b0bfdad37146d8b1f1d165965f2419bae01d11486f1.jpg)

![633fee038516dac181ed3639f6ecbb95deadc92c9255d1b92a1c0701010dedf3.jpg](../nips_results/2751_Optimal%20Spectral%20Transitions%20in%20High-Dimensional%20Multi-Index%20Models/images/633fee038516dac181ed3639f6ecbb95deadc92c9255d1b92a1c0701010dedf3.jpg)

![81f60aadfb3099682a2b3ffc2124e6e8f9649dc2a4fad3892898d850261e24e4.jpg](../nips_results/2751_Optimal%20Spectral%20Transitions%20in%20High-Dimensional%20Multi-Index%20Models/images/81f60aadfb3099682a2b3ffc2124e6e8f9649dc2a4fad3892898d850261e24e4.jpg)

![e0bfb457e593e67795ffd8dad1e52698cf168089b96aa311a724cc2f7ba408c1.jpg](../nips_results/2751_Optimal%20Spectral%20Transitions%20in%20High-Dimensional%20Multi-Index%20Models/images/e0bfb457e593e67795ffd8dad1e52698cf168089b96aa311a724cc2f7ba408c1.jpg)

![e68cc8e39ae418a6795b40ce308b6e4b77890f6a47b740b4d9b461b512436c24.jpg](../nips_results/2751_Optimal%20Spectral%20Transitions%20in%20High-Dimensional%20Multi-Index%20Models/images/e68cc8e39ae418a6795b40ce308b6e4b77890f6a47b740b4d9b461b512436c24.jpg)

![fa600792717b23351e764d32e0f99d2e216918fbade47844d0bec940c3c515b6.jpg](../nips_results/2751_Optimal%20Spectral%20Transitions%20in%20High-Dimensional%20Multi-Index%20Models/images/fa600792717b23351e764d32e0f99d2e216918fbade47844d0bec940c3c515b6.jpg)

## Direct3D-S2: Gigascale 3D Generation Made Easy with Spatial Sparse Attention


### Images

![0ca892ba69099bea55596502d9fe774ac6884b04d89d790aca61db976615a693.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/0ca892ba69099bea55596502d9fe774ac6884b04d89d790aca61db976615a693.jpg)

![3347c3ca9fa9f92c985e95f7d5e42e9f116964db3b9eb3a27b4dd9df3e01f942.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/3347c3ca9fa9f92c985e95f7d5e42e9f116964db3b9eb3a27b4dd9df3e01f942.jpg)

![40ab8ae1e932e758ef1ff76adb222c90c139177eb5d8edc5ecfe6e7da64335f8.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/40ab8ae1e932e758ef1ff76adb222c90c139177eb5d8edc5ecfe6e7da64335f8.jpg)

![5035514414c05746377c2f495f4813d0e1c065ecdc17332195c76e3bf40cead4.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/5035514414c05746377c2f495f4813d0e1c065ecdc17332195c76e3bf40cead4.jpg)

![566b6df3f7c72fd84a03efd01df33a08f555f7bfaa8c67a2fa3a34a02c1b7753.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/566b6df3f7c72fd84a03efd01df33a08f555f7bfaa8c67a2fa3a34a02c1b7753.jpg)

![5fe4360e996bc235ee588e53048fca7e9bf6c3cfba3ecfcec53f64959f5f1ddc.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/5fe4360e996bc235ee588e53048fca7e9bf6c3cfba3ecfcec53f64959f5f1ddc.jpg)

![6aac1845a1448b48d35b2e5f7db66dafbe797f2f7ac57877fc2a74944d640124.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/6aac1845a1448b48d35b2e5f7db66dafbe797f2f7ac57877fc2a74944d640124.jpg)

![755cf46a5e6805495b61e29ae039b1e14e39d99180206c600d24c455b3c8ac52.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/755cf46a5e6805495b61e29ae039b1e14e39d99180206c600d24c455b3c8ac52.jpg)

![8c5a9328bb89b3930f5969cba4da064febe35e396bb56ed3d301fc03dda0ab38.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/8c5a9328bb89b3930f5969cba4da064febe35e396bb56ed3d301fc03dda0ab38.jpg)

![ae292686ccb6ddd4e467f60761292fdbf986751b87e168d700a9defbd545c759.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/ae292686ccb6ddd4e467f60761292fdbf986751b87e168d700a9defbd545c759.jpg)

![b1fb71f6c519afe0db52682b44c40d38054292a455af36af0d428cd3868f0a17.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/b1fb71f6c519afe0db52682b44c40d38054292a455af36af0d428cd3868f0a17.jpg)

![b20279c70910451158d33e42882226a143d193c9ac225c3ab57041862b4747b0.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/b20279c70910451158d33e42882226a143d193c9ac225c3ab57041862b4747b0.jpg)

![e3584961fecdf01fdba07cf7923dec3363fdf435651b3cc574625d659afe63c3.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/images/e3584961fecdf01fdba07cf7923dec3363fdf435651b3cc574625d659afe63c3.jpg)

### Tables

![008c3cc907d3625eaae0f7e2e430133b202ae1a9f5f67f7fa69ae85feda7cc14.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/tables/008c3cc907d3625eaae0f7e2e430133b202ae1a9f5f67f7fa69ae85feda7cc14.jpg)

![088f9a26632e0fc91126f3e14a55ee86bb269e86c00bdfa7e049dce5cc86d396.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/tables/088f9a26632e0fc91126f3e14a55ee86bb269e86c00bdfa7e049dce5cc86d396.jpg)

![2deb65384c17d556992f5eca41785f2a57450858ffbe4f5dcdcc5229b3cfe1c9.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/tables/2deb65384c17d556992f5eca41785f2a57450858ffbe4f5dcdcc5229b3cfe1c9.jpg)

![82a3daa4e7de57ca772416e9b525c27970d365f166403098af277a37ab914101.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/tables/82a3daa4e7de57ca772416e9b525c27970d365f166403098af277a37ab914101.jpg)

![a3e862bd8a4f6090431a3e48161b0abe9b021857c50b7498f52b4cb417b2c7ae.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/tables/a3e862bd8a4f6090431a3e48161b0abe9b021857c50b7498f52b4cb417b2c7ae.jpg)

![eea0929ebea68c187d397c58cdf945fa547fa85d0da8d06375ee1f869355ea1f.jpg](../nips_results/2752_Direct3D-S2_%20Gigascale%203D%20Generation%20Made%20Easy%20with%20Spatial%20Sparse%20Attention/tables/eea0929ebea68c187d397c58cdf945fa547fa85d0da8d06375ee1f869355ea1f.jpg)

## CoDA: Coordinated Diffusion Noise Optimization for Whole-Body Manipulation of Articulated Objects


### Images

![3c458f8ad447cf58db16f1d5563f93d460ca92bdd1559ce09ec529b9d288b117.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/images/3c458f8ad447cf58db16f1d5563f93d460ca92bdd1559ce09ec529b9d288b117.jpg)

![45f8fc11a5da7251e64e241c2adaec28b053f69200676fe9f28870cac7c2aab2.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/images/45f8fc11a5da7251e64e241c2adaec28b053f69200676fe9f28870cac7c2aab2.jpg)

![7166100272eedf21e6b0532d77cbd867f9738d385b7d6ac5c30d33ca735829af.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/images/7166100272eedf21e6b0532d77cbd867f9738d385b7d6ac5c30d33ca735829af.jpg)

![94cb659ea41995578bd8e2bae680bc0976b9f479753420ca8a0940cc0e4b9e34.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/images/94cb659ea41995578bd8e2bae680bc0976b9f479753420ca8a0940cc0e4b9e34.jpg)

![a7a4e9a4e25c78b0e7634cd62f74369f8a347cff4b7e9038662baca7b086f0da.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/images/a7a4e9a4e25c78b0e7634cd62f74369f8a347cff4b7e9038662baca7b086f0da.jpg)

![e40b9d541358bc286a3899f497f27fcb375374de405b92b42cf4469c463c57e0.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/images/e40b9d541358bc286a3899f497f27fcb375374de405b92b42cf4469c463c57e0.jpg)

### Tables

![1328d7b710df63f43521014b0a7dddab7e279fa0fc047630cff5363941406971.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/tables/1328d7b710df63f43521014b0a7dddab7e279fa0fc047630cff5363941406971.jpg)

![560c0d904e17803cb367fefcc72a8a868b9ea38d0898966c4102a770c729959d.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/tables/560c0d904e17803cb367fefcc72a8a868b9ea38d0898966c4102a770c729959d.jpg)

![8000a038f425b5013ddbbca1c4a456f747c65681a247f9ffb97153429e5e8b8f.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/tables/8000a038f425b5013ddbbca1c4a456f747c65681a247f9ffb97153429e5e8b8f.jpg)

![95e791d863aa1aa3f2d7dc863267d66d57ed7cd61b9ba50efcd6298a066b734d.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/tables/95e791d863aa1aa3f2d7dc863267d66d57ed7cd61b9ba50efcd6298a066b734d.jpg)

![9de6f144b3d5ceba410430584582bd406cb4928a5a09ee6b52410a6edc203b0e.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/tables/9de6f144b3d5ceba410430584582bd406cb4928a5a09ee6b52410a6edc203b0e.jpg)

![f8bd1176f341c5d9304cdd2120edb28b2b9b918f0cfca6b769a2a72b5d3c1c39.jpg](../nips_results/2753_CoDA_%20Coordinated%20Diffusion%20Noise%20Optimization%20for%20Whole-Body%20Manipulation%20of%20Articulated%20Objects/tables/f8bd1176f341c5d9304cdd2120edb28b2b9b918f0cfca6b769a2a72b5d3c1c39.jpg)

## Harnessing the Computation Redundancy in ViTs to Boost Adversarial Transferability


### Images

![12d90efaea62b869649e1df6c3a557d7166fe1daf0794644a8a6461d84b1c1dd.jpg](../nips_results/2754_Harnessing%20the%20Computation%20Redundancy%20in%20ViTs%20to%20Boost%20Adversarial%20Transferability/images/12d90efaea62b869649e1df6c3a557d7166fe1daf0794644a8a6461d84b1c1dd.jpg)

![1e0e4e365791106508c43695487e8a78d5e7b32f7b784d4f9555efdc2a914f58.jpg](../nips_results/2754_Harnessing%20the%20Computation%20Redundancy%20in%20ViTs%20to%20Boost%20Adversarial%20Transferability/images/1e0e4e365791106508c43695487e8a78d5e7b32f7b784d4f9555efdc2a914f58.jpg)

![1fb233901ac17df9f5c0a54c69dd95d0933a729685ec33de2dd65480ccc82a1e.jpg](../nips_results/2754_Harnessing%20the%20Computation%20Redundancy%20in%20ViTs%20to%20Boost%20Adversarial%20Transferability/images/1fb233901ac17df9f5c0a54c69dd95d0933a729685ec33de2dd65480ccc82a1e.jpg)

![56376b78a1714611001c3062c9cfa26dee8414fb34e510ec3bb49253d1b2fc92.jpg](../nips_results/2754_Harnessing%20the%20Computation%20Redundancy%20in%20ViTs%20to%20Boost%20Adversarial%20Transferability/images/56376b78a1714611001c3062c9cfa26dee8414fb34e510ec3bb49253d1b2fc92.jpg)

![6367b66cb39dbe9f49f1ff7f11a3343d0cfc1f38dcd0217f5f11711f70272c65.jpg](../nips_results/2754_Harnessing%20the%20Computation%20Redundancy%20in%20ViTs%20to%20Boost%20Adversarial%20Transferability/images/6367b66cb39dbe9f49f1ff7f11a3343d0cfc1f38dcd0217f5f11711f70272c65.jpg)

![7d13df7e6c60dca1725587cbb9741217b90abd6d59e1771a7e010ac55abc93d2.jpg](../nips_results/2754_Harnessing%20the%20Computation%20Redundancy%20in%20ViTs%20to%20Boost%20Adversarial%20Transferability/images/7d13df7e6c60dca1725587cbb9741217b90abd6d59e1771a7e010ac55abc93d2.jpg)

![a5397bc7c44433258b67ab2cb361164514276ab0e4eb1378db0d9ae5c89839f8.jpg](../nips_results/2754_Harnessing%20the%20Computation%20Redundancy%20in%20ViTs%20to%20Boost%20Adversarial%20Transferability/images/a5397bc7c44433258b67ab2cb361164514276ab0e4eb1378db0d9ae5c89839f8.jpg)

### Tables

![944aaaa90aa22a6d09e8155d371810db2d0c22c4bfb3ea49f98e176ad73101c9.jpg](../nips_results/2754_Harnessing%20the%20Computation%20Redundancy%20in%20ViTs%20to%20Boost%20Adversarial%20Transferability/tables/944aaaa90aa22a6d09e8155d371810db2d0c22c4bfb3ea49f98e176ad73101c9.jpg)

![da317b7739b2f4749abb9424fc7814e8cc729332c21bb2e9be6071f322a1cbd5.jpg](../nips_results/2754_Harnessing%20the%20Computation%20Redundancy%20in%20ViTs%20to%20Boost%20Adversarial%20Transferability/tables/da317b7739b2f4749abb9424fc7814e8cc729332c21bb2e9be6071f322a1cbd5.jpg)

## Cost-Sensitive Freeze-thaw Bayesian Optimization for Efficient Hyperparameter Tuning


### Images

![02ca9450ebd35e02a1cbd92fa1e154cf8c7880b75a4c6e5b10734a24688855d1.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/02ca9450ebd35e02a1cbd92fa1e154cf8c7880b75a4c6e5b10734a24688855d1.jpg)

![1a541b678144ca220babde5298b305a1bc746fed489533e13233b96b99f04f0a.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/1a541b678144ca220babde5298b305a1bc746fed489533e13233b96b99f04f0a.jpg)

![2dcb0167b126c3499ea00680bc97c4357f8b74337414a7791f6080b6035af7fb.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/2dcb0167b126c3499ea00680bc97c4357f8b74337414a7791f6080b6035af7fb.jpg)

![312efd5f5a6d5b90a932ceeaab08128dceb01ab9ac7709dbc441eb3f780fe7ce.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/312efd5f5a6d5b90a932ceeaab08128dceb01ab9ac7709dbc441eb3f780fe7ce.jpg)

![436fa00345c4256cb79fbd48ef9e5ce260ab9d4d67db2a4da11d338a4b02463c.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/436fa00345c4256cb79fbd48ef9e5ce260ab9d4d67db2a4da11d338a4b02463c.jpg)

![4760741612169c1ec6c7462b6f29927bd0d01b6a4e45b59d9f22d975d6b5481e.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/4760741612169c1ec6c7462b6f29927bd0d01b6a4e45b59d9f22d975d6b5481e.jpg)

![4c24d7b94699d505a0f50a7f8a0808190fd2f6b8d994ce1e46c363911db44285.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/4c24d7b94699d505a0f50a7f8a0808190fd2f6b8d994ce1e46c363911db44285.jpg)

![62db0916f3c718ae6e64ec175b762a26e3bf61095427b519e3780f599adf5156.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/62db0916f3c718ae6e64ec175b762a26e3bf61095427b519e3780f599adf5156.jpg)

![6f0434bda8ce61500d6a31b3518362725caefc27800528415620870580bf9be3.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/6f0434bda8ce61500d6a31b3518362725caefc27800528415620870580bf9be3.jpg)

![700117d914997e795ba2d5ec8941c77b55c94b88903c4779e5ad211bf65218b9.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/700117d914997e795ba2d5ec8941c77b55c94b88903c4779e5ad211bf65218b9.jpg)

![75c362b8a0b701f868e1840578154887eb869f9d1faa3c7d6ca5c281ee4aef71.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/75c362b8a0b701f868e1840578154887eb869f9d1faa3c7d6ca5c281ee4aef71.jpg)

![8ad5ba2cc3f500510a0d2318fd1747fb9f4d00b16b5544710aa9f08cb8dbeed3.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/8ad5ba2cc3f500510a0d2318fd1747fb9f4d00b16b5544710aa9f08cb8dbeed3.jpg)

![9bb19ffb7e2db9731ba0f918209a2f5db9feab19410a7b7248cfb815d7691ff4.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/9bb19ffb7e2db9731ba0f918209a2f5db9feab19410a7b7248cfb815d7691ff4.jpg)

![9d6380e3c760131d3475d38a0a2aa4ac9bea7db9fc65e9987b32079120ff31a6.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/9d6380e3c760131d3475d38a0a2aa4ac9bea7db9fc65e9987b32079120ff31a6.jpg)

![a3d7805a7c62494a7b05b569df952de2d763b9dbd3b72c5e1659b2d9a371daa8.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/a3d7805a7c62494a7b05b569df952de2d763b9dbd3b72c5e1659b2d9a371daa8.jpg)

![a3e9c2f9e85b6237c0421167a01ae6a269b34065dcfc7f0e491fd2d116206cd9.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/a3e9c2f9e85b6237c0421167a01ae6a269b34065dcfc7f0e491fd2d116206cd9.jpg)

![a707d8eee16f8f561531dd1d79619ad843c274394ce116d6f710fef17c16248d.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/a707d8eee16f8f561531dd1d79619ad843c274394ce116d6f710fef17c16248d.jpg)

![b92d96e029d217ccc1bd9f47eb3f652067a0e36029a7629bd1396c07022cbba7.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/b92d96e029d217ccc1bd9f47eb3f652067a0e36029a7629bd1396c07022cbba7.jpg)

![c666e9201515039c751a9911ae7fb89944dba452893989bd47148efcaaeebec2.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/c666e9201515039c751a9911ae7fb89944dba452893989bd47148efcaaeebec2.jpg)

![ca684d9bb8340bf372ed7901c200c2e68eac3dff05bb772700032b05053b1bb8.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/ca684d9bb8340bf372ed7901c200c2e68eac3dff05bb772700032b05053b1bb8.jpg)

![e4edc0fadad871dd59d860c3646e70da82a2b0a722689491b07d6448b9fd2af7.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/e4edc0fadad871dd59d860c3646e70da82a2b0a722689491b07d6448b9fd2af7.jpg)

![e8964bbda0d5875689dca18d9453e32b14e7dc315ea002c95f3cfbc41749fceb.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/images/e8964bbda0d5875689dca18d9453e32b14e7dc315ea002c95f3cfbc41749fceb.jpg)

### Tables

![007f4a57263a8bb7e8082208f0006709069a450a0c76224aa32fb6d97759a2c9.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/tables/007f4a57263a8bb7e8082208f0006709069a450a0c76224aa32fb6d97759a2c9.jpg)

![281f44e9ad1edaf712fef0423863e4bedf33950964995b64419faf70c9c0798d.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/tables/281f44e9ad1edaf712fef0423863e4bedf33950964995b64419faf70c9c0798d.jpg)

![5eda2d7b40569279707054443127129684cf9b9c25b485699ed8d820b820046b.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/tables/5eda2d7b40569279707054443127129684cf9b9c25b485699ed8d820b820046b.jpg)

![8328f51de063e5d091cd9e22b782e852100fdb152ecd172a8289ef8960462d53.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/tables/8328f51de063e5d091cd9e22b782e852100fdb152ecd172a8289ef8960462d53.jpg)

![9964fa35c7de868eae13e2b4ac0070429c3ea960493d38d048b1182f726ef74f.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/tables/9964fa35c7de868eae13e2b4ac0070429c3ea960493d38d048b1182f726ef74f.jpg)

![acfc9904d445e3818d3cfedfc51f5c82ba3156c5e50df3654199fd418c5e6724.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/tables/acfc9904d445e3818d3cfedfc51f5c82ba3156c5e50df3654199fd418c5e6724.jpg)

![c7f9031aac375eecd460c39757bc72dafc2dd99e993ae5d97cb9984f027cd857.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/tables/c7f9031aac375eecd460c39757bc72dafc2dd99e993ae5d97cb9984f027cd857.jpg)

![d48a368c3dd1180b45432e7df408f2a3820eb985fea8d25d59ae0e9a371d2fca.jpg](../nips_results/2755_Cost-Sensitive%20Freeze-thaw%20Bayesian%20Optimization%20for%20Efficient%20Hyperparameter%20Tuning/tables/d48a368c3dd1180b45432e7df408f2a3820eb985fea8d25d59ae0e9a371d2fca.jpg)

## MRO: Enhancing Reasoning in Diffusion Language Models via Multi-Reward Optimization


### Images

![3ea8c390513e10a3f28cc78012ebd1747780f8e3d3ef554aa8dd265235211ba3.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/images/3ea8c390513e10a3f28cc78012ebd1747780f8e3d3ef554aa8dd265235211ba3.jpg)

![56bcf10d14ba90fd410c1b2b1de6e7ca84a818a980b2981d89ee5785643c8b2c.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/images/56bcf10d14ba90fd410c1b2b1de6e7ca84a818a980b2981d89ee5785643c8b2c.jpg)

![6857691cabc4f9a2c9a00752cc27ed2a2b34388a3e6727cc48df2771c48675f5.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/images/6857691cabc4f9a2c9a00752cc27ed2a2b34388a3e6727cc48df2771c48675f5.jpg)

![812c25b05aafc128bf7508f8964964e63454ef3ef58071c2c9069cb32cd53709.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/images/812c25b05aafc128bf7508f8964964e63454ef3ef58071c2c9069cb32cd53709.jpg)

![c5e21e7e46c6a5ad9cd16d8719a4f1b426e880f08ce082acb1eca45a7087940f.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/images/c5e21e7e46c6a5ad9cd16d8719a4f1b426e880f08ce082acb1eca45a7087940f.jpg)

![c86792df96b1cbd409aba37dc086062f4fb17a9d7e0f9a233b35bea0dfb0d6aa.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/images/c86792df96b1cbd409aba37dc086062f4fb17a9d7e0f9a233b35bea0dfb0d6aa.jpg)

![cf76e3460e1dc96d697ec223859fcb126a5cc35ae8943a84d2caa75ce3b719ef.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/images/cf76e3460e1dc96d697ec223859fcb126a5cc35ae8943a84d2caa75ce3b719ef.jpg)

![dbaa0d22236a3254bcc1c27efa6b1318bdef376ebdba9037723006e8723dcc57.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/images/dbaa0d22236a3254bcc1c27efa6b1318bdef376ebdba9037723006e8723dcc57.jpg)

### Tables

![0e47e22f5f9a3077013d85b4fd3b779dda41655d7020108fecaab3ee74e8b34b.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/tables/0e47e22f5f9a3077013d85b4fd3b779dda41655d7020108fecaab3ee74e8b34b.jpg)

![17de3d982caf4bd59a49b0f5d257dd81db6eff56d27fac47f235617df987dc39.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/tables/17de3d982caf4bd59a49b0f5d257dd81db6eff56d27fac47f235617df987dc39.jpg)

![2255b72a795803ca259616357034eb40cb82fefcb633bae4080b01b4e672ea3c.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/tables/2255b72a795803ca259616357034eb40cb82fefcb633bae4080b01b4e672ea3c.jpg)

![3144f2d6893914fb79b8255c763e45816bdf12d2f11cfdb5b02409c2e9f9d717.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/tables/3144f2d6893914fb79b8255c763e45816bdf12d2f11cfdb5b02409c2e9f9d717.jpg)

![334b9f16aebfb02948566c2005bf1dbb4272d30e96eafe108a161f8414c645f0.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/tables/334b9f16aebfb02948566c2005bf1dbb4272d30e96eafe108a161f8414c645f0.jpg)

![79897e90c9b7af7784808b425c310201481bb642764d4cb45d4729ff4b81b466.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/tables/79897e90c9b7af7784808b425c310201481bb642764d4cb45d4729ff4b81b466.jpg)

![7cb5e99d14ff223cd2a854d4c86505624fc951838948439abe09a8b0123d610f.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/tables/7cb5e99d14ff223cd2a854d4c86505624fc951838948439abe09a8b0123d610f.jpg)

![9c3355bff61c3b749c27f86e7f7c7324487846f5864a320246566f30e47b587d.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/tables/9c3355bff61c3b749c27f86e7f7c7324487846f5864a320246566f30e47b587d.jpg)

![a811d645e11fbb8514d224527034b5d3c1c8da9b3793c488c982b6f10823eac5.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/tables/a811d645e11fbb8514d224527034b5d3c1c8da9b3793c488c982b6f10823eac5.jpg)

![ac7c038b55634d39ae1c5ee3a05c463314c3eb621f01117b7f087969f6911135.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/tables/ac7c038b55634d39ae1c5ee3a05c463314c3eb621f01117b7f087969f6911135.jpg)

![b4180e2fc0c853300964174b9f06cc5bafdf5508f2ca1dde9e77add98e421d3a.jpg](../nips_results/2756_MRO_%20Enhancing%20Reasoning%20in%20Diffusion%20Language%20Models%20via%20Multi-Reward%20Optimization/tables/b4180e2fc0c853300964174b9f06cc5bafdf5508f2ca1dde9e77add98e421d3a.jpg)

## Seeing through Uncertainty: Robust Task-Oriented Optimization in Visual Navigation


### Images

![0aa382f70f07e77525855334ffa55dc0bb5362820c8fc787b384cf3e2b36e9a6.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/images/0aa382f70f07e77525855334ffa55dc0bb5362820c8fc787b384cf3e2b36e9a6.jpg)

![81187324fd96dccf1143af50617255f78713b2fb70d0f484280918d13aedb086.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/images/81187324fd96dccf1143af50617255f78713b2fb70d0f484280918d13aedb086.jpg)

![9785de7d1cbc46d52ac565a4b7d58e32ab61a60b7f89c7f109cbd772dc83ffba.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/images/9785de7d1cbc46d52ac565a4b7d58e32ab61a60b7f89c7f109cbd772dc83ffba.jpg)

![ce96797afb0f6718192c868f727c62f2720902fd730954243774693291df1777.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/images/ce96797afb0f6718192c868f727c62f2720902fd730954243774693291df1777.jpg)

![db7a982b51d172956ac3850dff5f3228c09cab17652b5ee8d3638c4daa2c5e12.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/images/db7a982b51d172956ac3850dff5f3228c09cab17652b5ee8d3638c4daa2c5e12.jpg)

![fc1da625098208d3f77e1e328835293892af28ba5c67b570fde48f3c351c882e.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/images/fc1da625098208d3f77e1e328835293892af28ba5c67b570fde48f3c351c882e.jpg)

### Tables

![079aedf0c111ae62b0642b0299f13917b7c6b961385ae36f2b210d7a019ac909.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/tables/079aedf0c111ae62b0642b0299f13917b7c6b961385ae36f2b210d7a019ac909.jpg)

![14424c9deb60a918654bfdfc2c77fe59fdf75163cc61a2ca351155e3d0ae6709.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/tables/14424c9deb60a918654bfdfc2c77fe59fdf75163cc61a2ca351155e3d0ae6709.jpg)

![1f8ed0e3687bfc46c07aa9fc1e7147a99886464e3e3aa877857f04f54a79d8f5.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/tables/1f8ed0e3687bfc46c07aa9fc1e7147a99886464e3e3aa877857f04f54a79d8f5.jpg)

![66d8ccd034666268c3ea94591e7f8e8087ce29ca20bf470c7608a7f46d9c0b09.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/tables/66d8ccd034666268c3ea94591e7f8e8087ce29ca20bf470c7608a7f46d9c0b09.jpg)

![afbf0914d4a2a89bc0dcc35e498d93c422ec770f45ce1f2cb908b0faad4816ba.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/tables/afbf0914d4a2a89bc0dcc35e498d93c422ec770f45ce1f2cb908b0faad4816ba.jpg)

![b256a0ebcd9b52be888200277e9d7e60490d0ffa986e9dc80ed68ce8cfa1af17.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/tables/b256a0ebcd9b52be888200277e9d7e60490d0ffa986e9dc80ed68ce8cfa1af17.jpg)

![b565ea5e8103bf9368eabd45e0dd80c10735cb801d8a2ebb09e36660215fb667.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/tables/b565ea5e8103bf9368eabd45e0dd80c10735cb801d8a2ebb09e36660215fb667.jpg)

![bf1a740efee8f59e62cddc3c302aabc4c131c925aa86bf1b725f16818d83be94.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/tables/bf1a740efee8f59e62cddc3c302aabc4c131c925aa86bf1b725f16818d83be94.jpg)

![c20e86d8893d367ccb30474af7cf9d9cb59a7b8a6cbfaf2fdc3538fc02bd51fa.jpg](../nips_results/2757_Seeing%20through%20Uncertainty_%20Robust%20Task-Oriented%20Optimization%20in%20Visual%20Navigation/tables/c20e86d8893d367ccb30474af7cf9d9cb59a7b8a6cbfaf2fdc3538fc02bd51fa.jpg)

## SynBrain: Enhancing Visual-to-fMRI Synthesis via Probabilistic Representation Learning


### Images

![05de034af24f7906108695d947fcf9907cb22fd7162cbb54d806c32700533248.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/images/05de034af24f7906108695d947fcf9907cb22fd7162cbb54d806c32700533248.jpg)

![26fdbee15da0c23982b19b8b51ef0a54804381aafa67b9d0d26423d1dd5eb778.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/images/26fdbee15da0c23982b19b8b51ef0a54804381aafa67b9d0d26423d1dd5eb778.jpg)

![30080306dccff59800fe6e0f7d4355343dc558c108626a41753c90b19e4d13fa.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/images/30080306dccff59800fe6e0f7d4355343dc558c108626a41753c90b19e4d13fa.jpg)

![336a1b166d69ef225e210b8b3cbff065645a912b9bbc819d3933ee49d12a0ca0.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/images/336a1b166d69ef225e210b8b3cbff065645a912b9bbc819d3933ee49d12a0ca0.jpg)

![431a4a375ac2d15ca0e064cb7fa5d508e1ec88266529f85ed6d1351588152829.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/images/431a4a375ac2d15ca0e064cb7fa5d508e1ec88266529f85ed6d1351588152829.jpg)

![ad83d600ab91ffbb1f32796756cd7cb383cd66d9d10c1d4a7338cce630b8b6de.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/images/ad83d600ab91ffbb1f32796756cd7cb383cd66d9d10c1d4a7338cce630b8b6de.jpg)

![bc05efcd52050f6a03dc8227d660cde182db01fc90c063963edf8e716d8f9df5.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/images/bc05efcd52050f6a03dc8227d660cde182db01fc90c063963edf8e716d8f9df5.jpg)

![e712fdd4acc8c53dc639cbb60ea336869e6d19719966eac5c799f1090e9f9dff.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/images/e712fdd4acc8c53dc639cbb60ea336869e6d19719966eac5c799f1090e9f9dff.jpg)

![e86cb2d1b055f1008fc96a3896c4f7e44a7a6f32452412741d3d9c0c17715154.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/images/e86cb2d1b055f1008fc96a3896c4f7e44a7a6f32452412741d3d9c0c17715154.jpg)

### Tables

![084756cb4fe241f55e2f849555a4560cf58926d1494c5d292ff46da52cb9edad.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/084756cb4fe241f55e2f849555a4560cf58926d1494c5d292ff46da52cb9edad.jpg)

![11a1e855531cfbe2e2515744bf0646f948bd2362e55d5176eca7f4a6904d8e75.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/11a1e855531cfbe2e2515744bf0646f948bd2362e55d5176eca7f4a6904d8e75.jpg)

![200674c1c197ff12e0b503c3c171d3858373e19cdaaa7a5332ce2de8d6b581ab.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/200674c1c197ff12e0b503c3c171d3858373e19cdaaa7a5332ce2de8d6b581ab.jpg)

![270a37e36b6435dcffe069cb17b1286d8d4a84ef7991d239a59c3f7329ecded9.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/270a37e36b6435dcffe069cb17b1286d8d4a84ef7991d239a59c3f7329ecded9.jpg)

![2a33f9a82f05d4db0469d63e0a1ad31e1ad82ba9686ea63976ab007701c70573.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/2a33f9a82f05d4db0469d63e0a1ad31e1ad82ba9686ea63976ab007701c70573.jpg)

![2dba974352fe7e1d72aabd20d3042d9b652611a53c707a47c81d572ec040d947.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/2dba974352fe7e1d72aabd20d3042d9b652611a53c707a47c81d572ec040d947.jpg)

![2ee500c5b02f3da604a14cde6564cc845c86a959eaddc0d006cb3b9014c74a15.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/2ee500c5b02f3da604a14cde6564cc845c86a959eaddc0d006cb3b9014c74a15.jpg)

![348d5bdd9060d19c14bad8289d5a956e1c12eb9019b9704afe707ed87cfc43d0.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/348d5bdd9060d19c14bad8289d5a956e1c12eb9019b9704afe707ed87cfc43d0.jpg)

![3bf429e0214e2a6405b3b654dd523059f6877db5a0fa20314b409270832c0d0b.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/3bf429e0214e2a6405b3b654dd523059f6877db5a0fa20314b409270832c0d0b.jpg)

![4966bea1fd7e31e8e75c4fec95133cd92abbce98df06ca9f48fd1a6de57f4843.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/4966bea1fd7e31e8e75c4fec95133cd92abbce98df06ca9f48fd1a6de57f4843.jpg)

![6b9bdff898cfcffa54083a192971d0828e63e4ff056b3cf2c44be13ae3bcfdc2.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/6b9bdff898cfcffa54083a192971d0828e63e4ff056b3cf2c44be13ae3bcfdc2.jpg)

![8c31729eede4b4c4e718116118f462134d1944afed1eb6744e06e5815034970f.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/8c31729eede4b4c4e718116118f462134d1944afed1eb6744e06e5815034970f.jpg)

![ee1e20c7ec561b0cd7bb13a140b630d06793495c6294929a295f3574419e53a3.jpg](../nips_results/2758_SynBrain_%20Enhancing%20Visual-to-fMRI%20Synthesis%20via%20Probabilistic%20Representation%20Learning/tables/ee1e20c7ec561b0cd7bb13a140b630d06793495c6294929a295f3574419e53a3.jpg)

## PT-MoE: An Efficient Finetuning Framework for Integrating Mixture-of-Experts into Prompt Tuning


### Images

![0076c727bbf8cf1bb33f1e6291540c057fd9e5bf6fef9334fd136bc6214c6373.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/images/0076c727bbf8cf1bb33f1e6291540c057fd9e5bf6fef9334fd136bc6214c6373.jpg)

![4d5459fc6827e29e31add1a4e8d0bc73977d22313a055a8b2b8a82c87586dd17.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/images/4d5459fc6827e29e31add1a4e8d0bc73977d22313a055a8b2b8a82c87586dd17.jpg)

![71a904d77c1ea7c8b2dab0ac8f67ad09830527c5cfeaf47176098851f373ce2b.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/images/71a904d77c1ea7c8b2dab0ac8f67ad09830527c5cfeaf47176098851f373ce2b.jpg)

![d339c6879d7ad0f683af85060dcab2cf7d77639bee5bb4aa364257fa675650a0.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/images/d339c6879d7ad0f683af85060dcab2cf7d77639bee5bb4aa364257fa675650a0.jpg)

### Tables

![3a687b11a7c399a5c4db8c82b65e23c85fa029c0dc561fb9c04ccb02fa80e8e3.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/tables/3a687b11a7c399a5c4db8c82b65e23c85fa029c0dc561fb9c04ccb02fa80e8e3.jpg)

![404aef910d46b39a8b5df7669399f389c416edbdc1fc94bc363025fbb03534bb.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/tables/404aef910d46b39a8b5df7669399f389c416edbdc1fc94bc363025fbb03534bb.jpg)

![5be7446bd090ef4cb444e4ebb7731bea5a76b10213c9395cd9e545408a048fb0.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/tables/5be7446bd090ef4cb444e4ebb7731bea5a76b10213c9395cd9e545408a048fb0.jpg)

![688dd14473bf53e9d4de3e8b9408475c4f1b591dd84b87b0dc06ff95489598e1.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/tables/688dd14473bf53e9d4de3e8b9408475c4f1b591dd84b87b0dc06ff95489598e1.jpg)

![73a10bb4147c8d089deffedb2280202903a7a217e4149828127c63599f3d9a68.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/tables/73a10bb4147c8d089deffedb2280202903a7a217e4149828127c63599f3d9a68.jpg)

![7aa916ba48b76f5cc9a7f4c6cb62e862172cc8fe94d37d20647a46eac2d9c05a.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/tables/7aa916ba48b76f5cc9a7f4c6cb62e862172cc8fe94d37d20647a46eac2d9c05a.jpg)

![90e9cf300fc9e91aae3cd64ad5d47e3dad58ea0192d12ff4a92081de27c04cbd.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/tables/90e9cf300fc9e91aae3cd64ad5d47e3dad58ea0192d12ff4a92081de27c04cbd.jpg)

![95872d4661b3a5563a5330dbb332dc277bd1ef9489601ba91bd2e51fdf1ba407.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/tables/95872d4661b3a5563a5330dbb332dc277bd1ef9489601ba91bd2e51fdf1ba407.jpg)

![d2a828dc0968828a4a1ab4d222e69a4423f4acf420d16980d61086cd5312e75e.jpg](../nips_results/2759_PT-MoE_%20An%20Efficient%20Finetuning%20Framework%20for%20Integrating%20Mixture-of-Experts%20into%20Prompt%20Tuning/tables/d2a828dc0968828a4a1ab4d222e69a4423f4acf420d16980d61086cd5312e75e.jpg)

## PointMapPolicy: Structured Point Cloud Processing for Multi-Modal Imitation Learning


### Images

![075baa0f83ec6c27cb078119aea2cf78e433d9489f21336d0ae4d8c328337e53.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/075baa0f83ec6c27cb078119aea2cf78e433d9489f21336d0ae4d8c328337e53.jpg)

![0af27383a4f0b092c95349db7735e90e5ca2379f10635b18eef750abaa88a2b6.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/0af27383a4f0b092c95349db7735e90e5ca2379f10635b18eef750abaa88a2b6.jpg)

![1e906c104ed9c41f2f4bbdb8ff96d8f91510b34350c6f7f52a69e7cd19d82481.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/1e906c104ed9c41f2f4bbdb8ff96d8f91510b34350c6f7f52a69e7cd19d82481.jpg)

![2c5ada1dde07cff777ba984dc0884ac00030e7ce3d9f717ec70ece3bb6d48f9b.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/2c5ada1dde07cff777ba984dc0884ac00030e7ce3d9f717ec70ece3bb6d48f9b.jpg)

![4a02a5ab935fead2f45855d2f5a9b3d40653976a4ff81ae04c60b2d6a7b232ac.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/4a02a5ab935fead2f45855d2f5a9b3d40653976a4ff81ae04c60b2d6a7b232ac.jpg)

![68c482cf1633ef7bb13a7f8eb166af1299c566af203ac76c32fe2120fed9697c.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/68c482cf1633ef7bb13a7f8eb166af1299c566af203ac76c32fe2120fed9697c.jpg)

![896747fb16a25ba551cbdd064d50aeebc48ad48cff3d62783e52c8d9d29308df.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/896747fb16a25ba551cbdd064d50aeebc48ad48cff3d62783e52c8d9d29308df.jpg)

![bf4f5e064cc107e1ae5328d53d4f6beabb580af5ba3fa6969862616d7997201a.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/bf4f5e064cc107e1ae5328d53d4f6beabb580af5ba3fa6969862616d7997201a.jpg)

![c06912fdb5d215feb0f3388daf86a7beab9ed2dcbdb59e0b0cbb61d05f85f49a.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/c06912fdb5d215feb0f3388daf86a7beab9ed2dcbdb59e0b0cbb61d05f85f49a.jpg)

![c703e2d814c68601c6a865ea29c1ad240a8efb9b50509dc5b0ae4eeed585407c.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/c703e2d814c68601c6a865ea29c1ad240a8efb9b50509dc5b0ae4eeed585407c.jpg)

![d6c0012b53ac3ff60f0f7856425e54ef91f27566067119cee1cec1b8052cf92d.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/d6c0012b53ac3ff60f0f7856425e54ef91f27566067119cee1cec1b8052cf92d.jpg)

![e3f1aa97a133183fa450b51b2aa7aace28709f0d36d92b1ec3ee3369fb200c10.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/e3f1aa97a133183fa450b51b2aa7aace28709f0d36d92b1ec3ee3369fb200c10.jpg)

![f8a38976a6e030cfc73fdd41d0f63e323fb21a5b3de2cb859e2d9186cf705978.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/images/f8a38976a6e030cfc73fdd41d0f63e323fb21a5b3de2cb859e2d9186cf705978.jpg)

### Tables

![1f01897f2410616124da5a62ef1cd525abe3284ee0204c057400099e97e887ce.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/tables/1f01897f2410616124da5a62ef1cd525abe3284ee0204c057400099e97e887ce.jpg)

![3fe4e689589778ac3659950e64102e0967a2dc0ee5aaf53fd9ff5c6b126604a0.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/tables/3fe4e689589778ac3659950e64102e0967a2dc0ee5aaf53fd9ff5c6b126604a0.jpg)

![bb2177cb8e944c3430d14c5778b49e83989c88768253be714fdcffcae1abba61.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/tables/bb2177cb8e944c3430d14c5778b49e83989c88768253be714fdcffcae1abba61.jpg)

![c6a266d313900dd7c01eb69a5d495607884dd146f353e5fc430160cca5dea1f9.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/tables/c6a266d313900dd7c01eb69a5d495607884dd146f353e5fc430160cca5dea1f9.jpg)

![e69f8e448bea07ae56e4c22f19ff81697f17c29a1bd3b6628148352ad9dd2a45.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/tables/e69f8e448bea07ae56e4c22f19ff81697f17c29a1bd3b6628148352ad9dd2a45.jpg)

![ea86dfee8e8a5f0f31c144df482355ae14aa8b3c53f6ee310fe46edc811bbe99.jpg](../nips_results/2760_PointMapPolicy_%20Structured%20Point%20Cloud%20Processing%20for%20Multi-Modal%20Imitation%20Learning/tables/ea86dfee8e8a5f0f31c144df482355ae14aa8b3c53f6ee310fe46edc811bbe99.jpg)

## How to Learn a Star: Binary Classification with Starshaped Polyhedral Sets


### Images

![08145ce21d7975ceec9406fd7b4b129f7d2561f5f4a2516039fe12be2435dd8c.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/08145ce21d7975ceec9406fd7b4b129f7d2561f5f4a2516039fe12be2435dd8c.jpg)

![11539244f74a5dbb8f6c5763bc024bc652c6d2bf0af12f1eb39ec30c4b2313c0.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/11539244f74a5dbb8f6c5763bc024bc652c6d2bf0af12f1eb39ec30c4b2313c0.jpg)

![1f45236276448cbf4af5c7e6d2cfe64901780eb910d02a2770a199010103d95d.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/1f45236276448cbf4af5c7e6d2cfe64901780eb910d02a2770a199010103d95d.jpg)

![229f37da75675c34e5c5b25e1f7e4452510d78d6787e46ed0266751b7cab96a3.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/229f37da75675c34e5c5b25e1f7e4452510d78d6787e46ed0266751b7cab96a3.jpg)

![32a5a32e6b39f390ca04d399fffec8fe43c1a68efe7c697e09ed096c52419bf4.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/32a5a32e6b39f390ca04d399fffec8fe43c1a68efe7c697e09ed096c52419bf4.jpg)

![38f1e9df5a7abc409249fd348a4fd11cb58ee58060468e6cb9aa9eba8161d909.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/38f1e9df5a7abc409249fd348a4fd11cb58ee58060468e6cb9aa9eba8161d909.jpg)

![69bbdc3ca0df7ef5f904614f17e3d1d910ed7aa25c6e6d3db42d7a758b9e4785.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/69bbdc3ca0df7ef5f904614f17e3d1d910ed7aa25c6e6d3db42d7a758b9e4785.jpg)

![75392e852fa163476f2c9eedc7872ba560b51551746263c76e4be0adc7aff9f9.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/75392e852fa163476f2c9eedc7872ba560b51551746263c76e4be0adc7aff9f9.jpg)

![7d92ca0a66736c130130553b167f7e01317838582f501107b722ed9c241914d5.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/7d92ca0a66736c130130553b167f7e01317838582f501107b722ed9c241914d5.jpg)

![87cc28721d95ec8d24b08d54459278c1488e63d5230cea0f2b99396d8f2fd692.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/87cc28721d95ec8d24b08d54459278c1488e63d5230cea0f2b99396d8f2fd692.jpg)

![9c3d8b6b9ee19459d98c63b5c58bf9a23d5059f939f9e2b319cbfa7e61d4dace.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/9c3d8b6b9ee19459d98c63b5c58bf9a23d5059f939f9e2b319cbfa7e61d4dace.jpg)

![ad3a87694343cfb8a3ffe8f685016ae654f7551464876004805956c6302cb2dd.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/ad3a87694343cfb8a3ffe8f685016ae654f7551464876004805956c6302cb2dd.jpg)

![ef3eb153b0b665ac691b323dd609c25bdce30a3713013ceb6661f4aa9862232f.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/images/ef3eb153b0b665ac691b323dd609c25bdce30a3713013ceb6661f4aa9862232f.jpg)

### Tables

![e47b00c825d9ed7a7edf39ead7a502b35e5f7d600e674f5f4064a96f60f232e4.jpg](../nips_results/2761_How%20to%20Learn%20a%20Star_%20Binary%20Classification%20with%20Starshaped%20Polyhedral%20Sets/tables/e47b00c825d9ed7a7edf39ead7a502b35e5f7d600e674f5f4064a96f60f232e4.jpg)

## GLSim: Detecting Object Hallucinations in LVLMs via Global-Local Similarity


### Images

![05650a87cd89cdf70ab6a6b2b6e1d16d6bdac7104319aecace7881f3f5eb6610.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/05650a87cd89cdf70ab6a6b2b6e1d16d6bdac7104319aecace7881f3f5eb6610.jpg)

![0ae88b31a2b9ef0304b219e73cc65227b50d33777449ce024c0205364f0355c9.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/0ae88b31a2b9ef0304b219e73cc65227b50d33777449ce024c0205364f0355c9.jpg)

![0f8b0d319b944f4eb8a780d40048b6cde7df8dbabffffce565c5a0b7cc565c4c.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/0f8b0d319b944f4eb8a780d40048b6cde7df8dbabffffce565c5a0b7cc565c4c.jpg)

![1d4ee603e85fdffd4f9da1c2e98d22e56c4a852899d5c690a0486c25b163e297.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/1d4ee603e85fdffd4f9da1c2e98d22e56c4a852899d5c690a0486c25b163e297.jpg)

![2f673b954234039ff5ad415afb2319bcbd3a247546bcd7ed3ee4e0dcd29e6b8d.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/2f673b954234039ff5ad415afb2319bcbd3a247546bcd7ed3ee4e0dcd29e6b8d.jpg)

![35a6be147a49b14fb88fa992f1e30202ea4a4444b7ef32ce6abcebb650127bc9.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/35a6be147a49b14fb88fa992f1e30202ea4a4444b7ef32ce6abcebb650127bc9.jpg)

![38a52e2d25bc47ffa8f68a52ea7caae67a8daff064d5fcea8c92e496745700e4.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/38a52e2d25bc47ffa8f68a52ea7caae67a8daff064d5fcea8c92e496745700e4.jpg)

![4387d14667a8d086900a3dc1e9e2c083f0f860944710d72dfa893872379541b4.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/4387d14667a8d086900a3dc1e9e2c083f0f860944710d72dfa893872379541b4.jpg)

![6fc550a4de17d5cbdd1850ba3d55df62828366e67f9d44017ee2684fe32c7e8f.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/6fc550a4de17d5cbdd1850ba3d55df62828366e67f9d44017ee2684fe32c7e8f.jpg)

![7354697fddd3d671397c08b82a0da6806658b700c834dd8c50a9e52f66fdc6ff.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/7354697fddd3d671397c08b82a0da6806658b700c834dd8c50a9e52f66fdc6ff.jpg)

![861302f9b95a0c3e1dd149e617ce7663038ab17b407bf07dcff182b02c10613f.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/861302f9b95a0c3e1dd149e617ce7663038ab17b407bf07dcff182b02c10613f.jpg)

![997bf7e6f8170d9f937c57f9bb18f3798bc6c872fb81ae7e7edeb5e1387a9959.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/997bf7e6f8170d9f937c57f9bb18f3798bc6c872fb81ae7e7edeb5e1387a9959.jpg)

![cd780973064a065ef3cf40bf7d8d960e29d43f6e7ad2886602863e1727f07ff6.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/images/cd780973064a065ef3cf40bf7d8d960e29d43f6e7ad2886602863e1727f07ff6.jpg)

### Tables

![25d6865f2dba6f6ab4471c9af14198a215e7dd1c17b59535d89db2212eea3e96.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/25d6865f2dba6f6ab4471c9af14198a215e7dd1c17b59535d89db2212eea3e96.jpg)

![42cd65a5e8cac357b641594ac63d29a2d33c4828c65d97c8007445245b199bac.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/42cd65a5e8cac357b641594ac63d29a2d33c4828c65d97c8007445245b199bac.jpg)

![7c419147ce0c22b798cf4df98449b7d56c236b2161706bba8b1ee4b785188038.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/7c419147ce0c22b798cf4df98449b7d56c236b2161706bba8b1ee4b785188038.jpg)

![88c30f8f1d426f56885b40bfeaaeaec041d9b276a9b5334f04db067dac1039cf.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/88c30f8f1d426f56885b40bfeaaeaec041d9b276a9b5334f04db067dac1039cf.jpg)

![8d7fc63e9771a77c688a3db3fdef7a4570257dae685d969999806e59bdab4e98.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/8d7fc63e9771a77c688a3db3fdef7a4570257dae685d969999806e59bdab4e98.jpg)

![aa3e592b3a572d354f88bf95de052acfd81e8607453adbde6641a54e8c1f6d0a.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/aa3e592b3a572d354f88bf95de052acfd81e8607453adbde6641a54e8c1f6d0a.jpg)

![c41985dde18e472b6ad65e4ed59bb580bf155ac377eefefd358181e2c26c1621.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/c41985dde18e472b6ad65e4ed59bb580bf155ac377eefefd358181e2c26c1621.jpg)

![d948112a695ba86c077c4a563ce1b102da54407c4f3d129f5c3c1c33ff0561a3.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/d948112a695ba86c077c4a563ce1b102da54407c4f3d129f5c3c1c33ff0561a3.jpg)

![e3d0d2f123363507c105b26739af84459ef7389f66b9f93b550e31587a278570.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/e3d0d2f123363507c105b26739af84459ef7389f66b9f93b550e31587a278570.jpg)

![f3e02fc1cc89708f939ad32a1aa6586e0d2cfac396c869480e2d5e4219861a22.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/f3e02fc1cc89708f939ad32a1aa6586e0d2cfac396c869480e2d5e4219861a22.jpg)

![f441080e145ba1bb8f86880819bb121a4d12409a147df7452bd501a5470d356e.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/f441080e145ba1bb8f86880819bb121a4d12409a147df7452bd501a5470d356e.jpg)

![fb89928cc5369656dc74db9d5b368cfed907a574873ea20c823f3a787a6e142b.jpg](../nips_results/2762_GLSim_%20Detecting%20Object%20Hallucinations%20in%20LVLMs%20via%20Global-Local%20Similarity/tables/fb89928cc5369656dc74db9d5b368cfed907a574873ea20c823f3a787a6e142b.jpg)

## Uncertainty Quantification for Deep Regression using Contextualised Normalizing Flows


### Images

![1f1b2b9103f045259f606e2f24fb21a2153d9b3fe9bdbfbef85d221652b39048.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/images/1f1b2b9103f045259f606e2f24fb21a2153d9b3fe9bdbfbef85d221652b39048.jpg)

![368f8d0b9e0d0ba02691f7d62d16e8062b3000f72ac3bbb66356db1b6030848d.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/images/368f8d0b9e0d0ba02691f7d62d16e8062b3000f72ac3bbb66356db1b6030848d.jpg)

![6e2cae97efca8ccafcf3bb0e532da0387adfbf403c2822e44cff48626c5bd5ce.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/images/6e2cae97efca8ccafcf3bb0e532da0387adfbf403c2822e44cff48626c5bd5ce.jpg)

![90a1cc3a66757e16133002964c0de129af8d788961b7a88f61af8756413c9c4d.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/images/90a1cc3a66757e16133002964c0de129af8d788961b7a88f61af8756413c9c4d.jpg)

![912c5dd3fb1e562f78e945859318f57d29dbaeda03f55352f2a9186a69bd334e.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/images/912c5dd3fb1e562f78e945859318f57d29dbaeda03f55352f2a9186a69bd334e.jpg)

![ab356e1e5df84b36b569a56f2774597abe7c651e5a2fb74c0cae9e950704a55f.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/images/ab356e1e5df84b36b569a56f2774597abe7c651e5a2fb74c0cae9e950704a55f.jpg)

![f0d918b7f058463e2a02d82a7cfd51ab003a38b42015ca035332252877cd4f99.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/images/f0d918b7f058463e2a02d82a7cfd51ab003a38b42015ca035332252877cd4f99.jpg)

![f1965e6e6aaeb130a7482207ee901fd880cfe57bb8f83ba11c898b99203f95d3.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/images/f1965e6e6aaeb130a7482207ee901fd880cfe57bb8f83ba11c898b99203f95d3.jpg)

### Tables

![00bdab0e4f1b560ac6ac03948eef1a944954cd3e87e8165c4045f446dd6e015f.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/tables/00bdab0e4f1b560ac6ac03948eef1a944954cd3e87e8165c4045f446dd6e015f.jpg)

![8af4a5b5eeea188a53c38c8660b06e73fa4e0b1539cf1eb299a484f7fb5064b1.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/tables/8af4a5b5eeea188a53c38c8660b06e73fa4e0b1539cf1eb299a484f7fb5064b1.jpg)

![b5930a8ea5962bb5e3d651b25938cbdcb25a61d1886d823abfc1a6e0fad118aa.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/tables/b5930a8ea5962bb5e3d651b25938cbdcb25a61d1886d823abfc1a6e0fad118aa.jpg)

![c26af0e40acbfb76f949c4ce9682f5fcd2ac8143864a7a31f82763151be8821e.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/tables/c26af0e40acbfb76f949c4ce9682f5fcd2ac8143864a7a31f82763151be8821e.jpg)

![ef61f9411d1a487958ddc4214267b9f6278a3b97a44c6a5a6b9f8e81d98166c5.jpg](../nips_results/2763_Uncertainty%20Quantification%20for%20Deep%20Regression%20using%20Contextualised%20Normalizing%20Flows/tables/ef61f9411d1a487958ddc4214267b9f6278a3b97a44c6a5a6b9f8e81d98166c5.jpg)

## Optimality and NP-Hardness of Transformers in Learning  Markovian Dynamical Functions


### Images

![180de8313d901943d682443b1ec077ae9a767b26a523487a76b826d97209fe92.jpg](../nips_results/2764_Optimality%20and%20NP-Hardness%20of%20Transformers%20in%20Learning%20%20Markovian%20Dynamical%20Functions/images/180de8313d901943d682443b1ec077ae9a767b26a523487a76b826d97209fe92.jpg)

![42405d55c6cb9f5b265a44d666ceca641f53ec10e721b9cf959a582679b91ce6.jpg](../nips_results/2764_Optimality%20and%20NP-Hardness%20of%20Transformers%20in%20Learning%20%20Markovian%20Dynamical%20Functions/images/42405d55c6cb9f5b265a44d666ceca641f53ec10e721b9cf959a582679b91ce6.jpg)

![5b36ce1e7bed710e41374a29afe96f25746b9b662d83494c01d7db08486ea3e2.jpg](../nips_results/2764_Optimality%20and%20NP-Hardness%20of%20Transformers%20in%20Learning%20%20Markovian%20Dynamical%20Functions/images/5b36ce1e7bed710e41374a29afe96f25746b9b662d83494c01d7db08486ea3e2.jpg)

![67b5670c433151bb20e615728c2b29ae832b95b884ce84ff88c46db56ef9ba7b.jpg](../nips_results/2764_Optimality%20and%20NP-Hardness%20of%20Transformers%20in%20Learning%20%20Markovian%20Dynamical%20Functions/images/67b5670c433151bb20e615728c2b29ae832b95b884ce84ff88c46db56ef9ba7b.jpg)

![8609cb5a3165e6c39946e5ddb60a50ff706b7bbcb83528b185143675bd9a650f.jpg](../nips_results/2764_Optimality%20and%20NP-Hardness%20of%20Transformers%20in%20Learning%20%20Markovian%20Dynamical%20Functions/images/8609cb5a3165e6c39946e5ddb60a50ff706b7bbcb83528b185143675bd9a650f.jpg)

![b7d5656d151746d749cba15e8b7d0a6d4e5a288d42c938a2335a59aa79621cf3.jpg](../nips_results/2764_Optimality%20and%20NP-Hardness%20of%20Transformers%20in%20Learning%20%20Markovian%20Dynamical%20Functions/images/b7d5656d151746d749cba15e8b7d0a6d4e5a288d42c938a2335a59aa79621cf3.jpg)

![c5d5fc92dc96822b220bb3abc5afcabcaf5747b451198a3fc6013b74bee55e13.jpg](../nips_results/2764_Optimality%20and%20NP-Hardness%20of%20Transformers%20in%20Learning%20%20Markovian%20Dynamical%20Functions/images/c5d5fc92dc96822b220bb3abc5afcabcaf5747b451198a3fc6013b74bee55e13.jpg)

![c5f90b47eb0a9aeb7881e86ab301269bb9344238e67d9b1701bab63cd999d528.jpg](../nips_results/2764_Optimality%20and%20NP-Hardness%20of%20Transformers%20in%20Learning%20%20Markovian%20Dynamical%20Functions/images/c5f90b47eb0a9aeb7881e86ab301269bb9344238e67d9b1701bab63cd999d528.jpg)

![d05c34a1822929459265994ce2f46c158e07da2a666a07ce217fd95dd1508808.jpg](../nips_results/2764_Optimality%20and%20NP-Hardness%20of%20Transformers%20in%20Learning%20%20Markovian%20Dynamical%20Functions/images/d05c34a1822929459265994ce2f46c158e07da2a666a07ce217fd95dd1508808.jpg)

![ecf58a21f3d45f9374c2d58bbd7a8f555a4340d4bd69b9f1542f03f97894cf6e.jpg](../nips_results/2764_Optimality%20and%20NP-Hardness%20of%20Transformers%20in%20Learning%20%20Markovian%20Dynamical%20Functions/images/ecf58a21f3d45f9374c2d58bbd7a8f555a4340d4bd69b9f1542f03f97894cf6e.jpg)

## Learning to Solve Complex Problems via Dataset Decomposition


### Images

![2d53b4ec2133ea34ed567a84fe26bc704a0c9be5d91ddec520d78ec8ed1a2042.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/images/2d53b4ec2133ea34ed567a84fe26bc704a0c9be5d91ddec520d78ec8ed1a2042.jpg)

![d8101c73c847bee0843b7f4284e8fe30a37483709a55f3773b28843d5bd7fe05.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/images/d8101c73c847bee0843b7f4284e8fe30a37483709a55f3773b28843d5bd7fe05.jpg)

![dba8e3a337c6e669dfcd8d2a26dfff66140d96c632989044a0610874d9d3b049.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/images/dba8e3a337c6e669dfcd8d2a26dfff66140d96c632989044a0610874d9d3b049.jpg)

![f76d87f2c76bf54e345672fd5a2da2b7384cc6a7620effa5bc5adb4b51642b0e.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/images/f76d87f2c76bf54e345672fd5a2da2b7384cc6a7620effa5bc5adb4b51642b0e.jpg)

### Tables

![1f8065aa1a5c4b0df8af993f96ec78c1ba507a772e6d8ae935757400e82f6846.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/tables/1f8065aa1a5c4b0df8af993f96ec78c1ba507a772e6d8ae935757400e82f6846.jpg)

![2020f2367b8348e59993e4d0a145807761efb505cc370a2c39706dfed8ca959a.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/tables/2020f2367b8348e59993e4d0a145807761efb505cc370a2c39706dfed8ca959a.jpg)

![2c4566c319cf7d8a7f82078fb641f5f3e423f7717c9c035d1d5ac9cf2ffe69c7.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/tables/2c4566c319cf7d8a7f82078fb641f5f3e423f7717c9c035d1d5ac9cf2ffe69c7.jpg)

![3e0b02f78d0d5f90ad42f690f52015d69c50e4dedc596dcaf74f324e44515dd6.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/tables/3e0b02f78d0d5f90ad42f690f52015d69c50e4dedc596dcaf74f324e44515dd6.jpg)

![4f1c24ed245e754de37d8785809bf2aef9032bb2b710f1c5432dec472bc68c04.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/tables/4f1c24ed245e754de37d8785809bf2aef9032bb2b710f1c5432dec472bc68c04.jpg)

![672fb5c256078f369ac2eca870482306ce2e89be776c345ca68b7dc1d01a0151.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/tables/672fb5c256078f369ac2eca870482306ce2e89be776c345ca68b7dc1d01a0151.jpg)

![712a9f69c554fe0542c22dea1f06a87d52cf065b63566b7703053e2f96631240.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/tables/712a9f69c554fe0542c22dea1f06a87d52cf065b63566b7703053e2f96631240.jpg)

![80f239da17757545a72bca85438e54d725e8c748f1e32aa965cbd89f0dde3061.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/tables/80f239da17757545a72bca85438e54d725e8c748f1e32aa965cbd89f0dde3061.jpg)

![92882701e084359e3d8c0a81cf897c0b2762b10bd0bb272043827d287f4b9f43.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/tables/92882701e084359e3d8c0a81cf897c0b2762b10bd0bb272043827d287f4b9f43.jpg)

![eed50e42450564698446246f77714d548ca7c5bb09c8d7c1b1a5b8631e7ecc70.jpg](../nips_results/2765_Learning%20to%20Solve%20Complex%20Problems%20via%20Dataset%20Decomposition/tables/eed50e42450564698446246f77714d548ca7c5bb09c8d7c1b1a5b8631e7ecc70.jpg)

## Flexible inference for animal learning rules using neural networks


### Images

![255645e887f94927f61175de0cfa00191fa6a6d6a88feddb8b9d7eb53ce407af.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/255645e887f94927f61175de0cfa00191fa6a6d6a88feddb8b9d7eb53ce407af.jpg)

![3936966e4652b2435a3cac562faa17f50ce67395495db50b059d00932dc0f58b.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/3936966e4652b2435a3cac562faa17f50ce67395495db50b059d00932dc0f58b.jpg)

![424e590f5bbb2a4e5a0444892d7400c8f80568b56e55430ca4e2fb1495e996fb.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/424e590f5bbb2a4e5a0444892d7400c8f80568b56e55430ca4e2fb1495e996fb.jpg)

![453b5225ccc129586290dc152208fb8eb4daed4852329563103d8d928841090d.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/453b5225ccc129586290dc152208fb8eb4daed4852329563103d8d928841090d.jpg)

![4dc669f8947809a769b8d629042ac985355f1c7b9d63a8bc75a067180c9b62d5.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/4dc669f8947809a769b8d629042ac985355f1c7b9d63a8bc75a067180c9b62d5.jpg)

![562ebd7cdd9b766f50877702b325cebc212d2a2517b0b028dd53a35a5e3d4b07.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/562ebd7cdd9b766f50877702b325cebc212d2a2517b0b028dd53a35a5e3d4b07.jpg)

![6ea71cbcd8b82c60728394aaeddb40467862d4cdeac78c3cb9e80468e987c515.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/6ea71cbcd8b82c60728394aaeddb40467862d4cdeac78c3cb9e80468e987c515.jpg)

![78d0846205232cafe30cd9261e93522e9d9113906a0e731d580e015ae997a501.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/78d0846205232cafe30cd9261e93522e9d9113906a0e731d580e015ae997a501.jpg)

![8960b6e7bcd6938388256b670387ab4197917ddfd042493a1d881cede9c63ccd.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/8960b6e7bcd6938388256b670387ab4197917ddfd042493a1d881cede9c63ccd.jpg)

![95b33e04fcfa651bc2a6657ad9c0a83b9f59f3432c3ca0f4e0594ec6a43b2eb5.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/95b33e04fcfa651bc2a6657ad9c0a83b9f59f3432c3ca0f4e0594ec6a43b2eb5.jpg)

![9a6e576ba49f0441d4d6245419d139ea3fdf918433dd4ca9f97b21b9b950637b.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/9a6e576ba49f0441d4d6245419d139ea3fdf918433dd4ca9f97b21b9b950637b.jpg)

![a1629b0d54cd14228779ee130af66ca063ac13899c367de88aed661e632b80c8.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/a1629b0d54cd14228779ee130af66ca063ac13899c367de88aed661e632b80c8.jpg)

![b13b73b29d6c2d170cd8616960b8dc471e9d3ccfde710aa0376f85988e134678.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/b13b73b29d6c2d170cd8616960b8dc471e9d3ccfde710aa0376f85988e134678.jpg)

![b436aed2bed3898bbf2b0c0a83f73d3a6597fbc87f88064b218cfa63f061c372.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/b436aed2bed3898bbf2b0c0a83f73d3a6597fbc87f88064b218cfa63f061c372.jpg)

![bc46d99d01ad19c171ad1b0cb1f17901acc5d277abf45e476e50f9865249cef2.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/bc46d99d01ad19c171ad1b0cb1f17901acc5d277abf45e476e50f9865249cef2.jpg)

![beffe53703fdb389eaad623302d714fab74f25ed6e36ae972110d8e41969e6f7.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/beffe53703fdb389eaad623302d714fab74f25ed6e36ae972110d8e41969e6f7.jpg)

![e5e9b65e14a43bf06dc256ff5bccabc74cf2cdb40c967e2e832dd80d79dbadea.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/e5e9b65e14a43bf06dc256ff5bccabc74cf2cdb40c967e2e832dd80d79dbadea.jpg)

![fca3a80e41930aecf1b91b3204c19e8dd2da1e4211acadb7d767c0bc90752790.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/images/fca3a80e41930aecf1b91b3204c19e8dd2da1e4211acadb7d767c0bc90752790.jpg)

### Tables

![32203fbd12f8254efa761c9b8c79861cc08aff3066c6b9234bed2fd75813559e.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/tables/32203fbd12f8254efa761c9b8c79861cc08aff3066c6b9234bed2fd75813559e.jpg)

![42ca29c35c2e4de4413b905feb76067c5d289feb215ac77ae70ab619e88d266a.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/tables/42ca29c35c2e4de4413b905feb76067c5d289feb215ac77ae70ab619e88d266a.jpg)

![6a5d218e0286f818d7c973c150760913bd2d9c05ac7352f8e61b84a59ee6e0f7.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/tables/6a5d218e0286f818d7c973c150760913bd2d9c05ac7352f8e61b84a59ee6e0f7.jpg)

![857d99d960e8ee3b9d938f2406ecf9a469038d9b9cbbfb45c80f242199b2f690.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/tables/857d99d960e8ee3b9d938f2406ecf9a469038d9b9cbbfb45c80f242199b2f690.jpg)

![a9edb96900be7a1df1b9e3badc04d4776ccb17f98ac03f15327cefce5b39a518.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/tables/a9edb96900be7a1df1b9e3badc04d4776ccb17f98ac03f15327cefce5b39a518.jpg)

![d4bf606d61fd3fa2b689d667f0d8b3305afb9b8f1d60b3c864132cbcc21b2ca5.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/tables/d4bf606d61fd3fa2b689d667f0d8b3305afb9b8f1d60b3c864132cbcc21b2ca5.jpg)

![e1fa9758983c94d3dfa9b059b0c6a7c1648343f04413a9860b792b6e7344b45e.jpg](../nips_results/2766_Flexible%20inference%20for%20animal%20learning%20rules%20using%20neural%20networks/tables/e1fa9758983c94d3dfa9b059b0c6a7c1648343f04413a9860b792b6e7344b45e.jpg)

## SeRL: Self-play Reinforcement Learning for Large Language Models with Limited Data


### Images

![029b1d564d5c2e3f9e0b87e1f51741e01b19c2b52d4605e30c8c9a3ac789847a.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/images/029b1d564d5c2e3f9e0b87e1f51741e01b19c2b52d4605e30c8c9a3ac789847a.jpg)

![35f187deb426f3dd23a0b9460922b7eacbe37b71b2968cbcdfe59a886f2ff5b2.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/images/35f187deb426f3dd23a0b9460922b7eacbe37b71b2968cbcdfe59a886f2ff5b2.jpg)

![3c2168e36fc45f0c114ad2feee670e0add014d772fcc3c17e4cfa1bbce824043.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/images/3c2168e36fc45f0c114ad2feee670e0add014d772fcc3c17e4cfa1bbce824043.jpg)

![509d44cedd32af6bc5bc776b3f71303956675ad46520e25962ce28b6d0da7e55.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/images/509d44cedd32af6bc5bc776b3f71303956675ad46520e25962ce28b6d0da7e55.jpg)

![9094a382abb3b970940aa6a2e6322d44fd972b6ee36af0209a5ea3899d58690f.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/images/9094a382abb3b970940aa6a2e6322d44fd972b6ee36af0209a5ea3899d58690f.jpg)

![abc2231fddc98809a4e57afb31d7f51ea57e122a2e9d56db37991bf7c8d9a965.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/images/abc2231fddc98809a4e57afb31d7f51ea57e122a2e9d56db37991bf7c8d9a965.jpg)

![ae854abc02bd9d67fd7a8870944a2ea2a21dc4cc085b1317ac2b687f03e0ec43.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/images/ae854abc02bd9d67fd7a8870944a2ea2a21dc4cc085b1317ac2b687f03e0ec43.jpg)

![b76563e7e4d86808704a562f8cba189cd55d905f8dd64ab33eed3c6907d0731c.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/images/b76563e7e4d86808704a562f8cba189cd55d905f8dd64ab33eed3c6907d0731c.jpg)

![be7ff26036c6814ec34620dcf2f0a4bddbf53c6c0e371c0fcb5682495c71816d.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/images/be7ff26036c6814ec34620dcf2f0a4bddbf53c6c0e371c0fcb5682495c71816d.jpg)

![c015acd2c91a43fcd5a4aca491c3b07e1d2f02fd4d0c772115ba2c3c157c297b.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/images/c015acd2c91a43fcd5a4aca491c3b07e1d2f02fd4d0c772115ba2c3c157c297b.jpg)

![db7275c8791c09fa1833f4ee67c712cbb1cbb25fe489cbf9a60c94954e1c4078.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/images/db7275c8791c09fa1833f4ee67c712cbb1cbb25fe489cbf9a60c94954e1c4078.jpg)

### Tables

![06ee966b29700e16e7e9c46aa5dfed73ab504fe808f2419d1c648672b1ec3972.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/06ee966b29700e16e7e9c46aa5dfed73ab504fe808f2419d1c648672b1ec3972.jpg)

![1d58778f8d95e8b266dd4de056d51dee52e77ed7bca823d729c25981686af642.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/1d58778f8d95e8b266dd4de056d51dee52e77ed7bca823d729c25981686af642.jpg)

![1f33b49b77a7188dd93569be221a3c399411fda41369778d77921836bee09e9c.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/1f33b49b77a7188dd93569be221a3c399411fda41369778d77921836bee09e9c.jpg)

![69126f3520ca6fd0eadf462d3ce026b09a656413f6adfcb80338af60becd5a90.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/69126f3520ca6fd0eadf462d3ce026b09a656413f6adfcb80338af60becd5a90.jpg)

![6aba59162bb34daf2257778604b192c73aecc47c380df5f4ddb5ac02bbce0f1a.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/6aba59162bb34daf2257778604b192c73aecc47c380df5f4ddb5ac02bbce0f1a.jpg)

![6ff41fa6183b3de7d46a3be134d4deea41f75d0a454e7b99298ba901fd752f03.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/6ff41fa6183b3de7d46a3be134d4deea41f75d0a454e7b99298ba901fd752f03.jpg)

![91f5e8201a4509a30efd1613c1ff6cf23e2763e838b111fa189041bb4ce1984e.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/91f5e8201a4509a30efd1613c1ff6cf23e2763e838b111fa189041bb4ce1984e.jpg)

![a22967fca19f25323acdaa88b172d72a65cd6ab32a2a3c508e3d07b8ec2e338c.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/a22967fca19f25323acdaa88b172d72a65cd6ab32a2a3c508e3d07b8ec2e338c.jpg)

![cf3c52ab28fb99551c38b565254d1c61089c61c06cb81c48e2844d99d239f384.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/cf3c52ab28fb99551c38b565254d1c61089c61c06cb81c48e2844d99d239f384.jpg)

![d197f8a9aa99d309e7fce4da83a7c875d88159585661d6ac0939770334bed61b.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/d197f8a9aa99d309e7fce4da83a7c875d88159585661d6ac0939770334bed61b.jpg)

![d2158e6d8fdac3c086c7ae78bb136c5fdb45f784a90900e91d2fc2bade8ba664.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/d2158e6d8fdac3c086c7ae78bb136c5fdb45f784a90900e91d2fc2bade8ba664.jpg)

![eade351621136c0dcb289d12ba2db26df750aa56dbdce7085ca84e2a4df7510e.jpg](../nips_results/2767_SeRL_%20Self-play%20Reinforcement%20Learning%20for%20Large%20Language%20Models%20with%20Limited%20Data/tables/eade351621136c0dcb289d12ba2db26df750aa56dbdce7085ca84e2a4df7510e.jpg)

## The Emergence of Abstract Thought in Large Language Models Beyond Any Language


### Images

![512438e9af7171c98047b41b751884ffb691fc38b57e5e6bdbb74f52c30f56f3.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/images/512438e9af7171c98047b41b751884ffb691fc38b57e5e6bdbb74f52c30f56f3.jpg)

![9b60ee06f35fc52973ec75cbd05866baf32e3e3c8862a960428eb4f3eb776578.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/images/9b60ee06f35fc52973ec75cbd05866baf32e3e3c8862a960428eb4f3eb776578.jpg)

![a98fe27d16f2dc4247ed760c6926e1a9bccfd640b77a91d083e64fff1c43e587.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/images/a98fe27d16f2dc4247ed760c6926e1a9bccfd640b77a91d083e64fff1c43e587.jpg)

![ada111da34a3e6955f0ecc3ec7d03e07b9fbfdaba8002998fae1650ad4fe66d1.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/images/ada111da34a3e6955f0ecc3ec7d03e07b9fbfdaba8002998fae1650ad4fe66d1.jpg)

![b60aa0b19d33cdcb6c1a53098487e9621aadf78bdf5289f3f63dedda2d30ecdf.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/images/b60aa0b19d33cdcb6c1a53098487e9621aadf78bdf5289f3f63dedda2d30ecdf.jpg)

![efb8c77e93dd54bd8175804b46713ecbc28ca746be6399e7dcedac2fc4b7a93a.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/images/efb8c77e93dd54bd8175804b46713ecbc28ca746be6399e7dcedac2fc4b7a93a.jpg)

![f2ff0faf0afdfdd2d24e3140deaac622eac1fa67e9a81a092be24ec0aad3a5c3.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/images/f2ff0faf0afdfdd2d24e3140deaac622eac1fa67e9a81a092be24ec0aad3a5c3.jpg)

### Tables

![0b14ee2d6507c607e371dad8b7260bc3fe7b810452a5709c1a0f8cd9c19d2f7f.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/0b14ee2d6507c607e371dad8b7260bc3fe7b810452a5709c1a0f8cd9c19d2f7f.jpg)

![0c6d50eca127bee12d1b3649dda0cdf9905cf7bcdafe1d536e120c0cec63d065.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/0c6d50eca127bee12d1b3649dda0cdf9905cf7bcdafe1d536e120c0cec63d065.jpg)

![10803d3bc679f8e59725c5adc6f45356983a50b67793f21036c9ea93eaa1a51e.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/10803d3bc679f8e59725c5adc6f45356983a50b67793f21036c9ea93eaa1a51e.jpg)

![154b7de4de2e1c0c003b32f4206f943f4db3072ead8f8826f54046056fee1793.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/154b7de4de2e1c0c003b32f4206f943f4db3072ead8f8826f54046056fee1793.jpg)

![4dae1a43ae987f9f405de2ce26afc1e0542a2377f08eb1f97beefeea1f615fd4.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/4dae1a43ae987f9f405de2ce26afc1e0542a2377f08eb1f97beefeea1f615fd4.jpg)

![8747be73ec6cf358d76c574c847679d4f05d3bed5f4613612776afa3518c13d0.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/8747be73ec6cf358d76c574c847679d4f05d3bed5f4613612776afa3518c13d0.jpg)

![880dd59c313533e1c357b94b67e1396da4d676efb88e5a5b7c193776682b889c.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/880dd59c313533e1c357b94b67e1396da4d676efb88e5a5b7c193776682b889c.jpg)

![a8d51ed6af4e09492a97c63a6841913b0ffd9d8e466e404d079a16a985ae29d6.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/a8d51ed6af4e09492a97c63a6841913b0ffd9d8e466e404d079a16a985ae29d6.jpg)

![b51b5ab2630e31a06df7ceef949a8ad4037223466c1e55815d30f63a33378241.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/b51b5ab2630e31a06df7ceef949a8ad4037223466c1e55815d30f63a33378241.jpg)

![b8d84187b3a0f268e6a61983ee0b36c744e6c2dadcec2ce93ceec449dec474c8.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/b8d84187b3a0f268e6a61983ee0b36c744e6c2dadcec2ce93ceec449dec474c8.jpg)

![c5a9972a8657e82fea23e429e265109ab0cf147cea92f7618541bd2f36f2869b.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/c5a9972a8657e82fea23e429e265109ab0cf147cea92f7618541bd2f36f2869b.jpg)

![c89194ce5845de8983076e03c07683bc22d9949b6049e0b452a4dd6f970b0fc3.jpg](../nips_results/2768_The%20Emergence%20of%20Abstract%20Thought%20in%20Large%20Language%20Models%20Beyond%20Any%20Language/tables/c89194ce5845de8983076e03c07683bc22d9949b6049e0b452a4dd6f970b0fc3.jpg)

## Speculate Deep and Accurate: Lossless and Training-Free Acceleration for Offloaded LLMs via Substitute Speculative Decoding


### Images

![2967a49290e2637ea09102a7d8c4befa10f61e611e02bc5b53d0b75f60fcb49d.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/images/2967a49290e2637ea09102a7d8c4befa10f61e611e02bc5b53d0b75f60fcb49d.jpg)

![368f52af605e493bcce5a8fac2a3e6bbe3953f363d52c6be3e58bff7684d1a97.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/images/368f52af605e493bcce5a8fac2a3e6bbe3953f363d52c6be3e58bff7684d1a97.jpg)

![5facb9e763ed81d077abb5b74766e2091299812131de4b2582f45057b73b80f0.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/images/5facb9e763ed81d077abb5b74766e2091299812131de4b2582f45057b73b80f0.jpg)

![682da1ecb46a5b83140260c5b08fb70428d1671126402de3fc357acfe71e887c.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/images/682da1ecb46a5b83140260c5b08fb70428d1671126402de3fc357acfe71e887c.jpg)

![c0d34d1f58cfbbaccbb8e9b401dbdfe0d64a4160fcbe610b47d1a1d9032b2c42.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/images/c0d34d1f58cfbbaccbb8e9b401dbdfe0d64a4160fcbe610b47d1a1d9032b2c42.jpg)

![ca8fed298b82ac03e106917a30a51ebcb084c059cb45b78aa5c79123eef1f2b5.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/images/ca8fed298b82ac03e106917a30a51ebcb084c059cb45b78aa5c79123eef1f2b5.jpg)

### Tables

![2186402bc69bc01b43b7d86e214e6749c3ae92f448adee66eb3222508b4dcc56.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/tables/2186402bc69bc01b43b7d86e214e6749c3ae92f448adee66eb3222508b4dcc56.jpg)

![3605abb10f63cee241a95b58b97d5a5f6286da35c8c2ec9ef5c9012338056113.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/tables/3605abb10f63cee241a95b58b97d5a5f6286da35c8c2ec9ef5c9012338056113.jpg)

![384e193080319386b37713bc6f7665ef2df990be51b059d722d58250098f9ded.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/tables/384e193080319386b37713bc6f7665ef2df990be51b059d722d58250098f9ded.jpg)

![82f8852c2b42bb931923b7650d602b9501e4c74cea6a0b02f398bac5ee32877e.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/tables/82f8852c2b42bb931923b7650d602b9501e4c74cea6a0b02f398bac5ee32877e.jpg)

![b8c1b4f5d04a4ecc89ed87cfd9358ed31bbc61ef96906b90a53bbd9f1b55b14d.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/tables/b8c1b4f5d04a4ecc89ed87cfd9358ed31bbc61ef96906b90a53bbd9f1b55b14d.jpg)

![bc29a1607bdef86241bfa14b35b96924bb77bdb8c4322160499b6c8921854560.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/tables/bc29a1607bdef86241bfa14b35b96924bb77bdb8c4322160499b6c8921854560.jpg)

![e78e9ae48980cc722920bdf96dd5c34e707995b47ab7a902c1734eaeb745a261.jpg](../nips_results/2769_Speculate%20Deep%20and%20Accurate_%20Lossless%20and%20Training-Free%20Acceleration%20for%20Offloaded%20LLMs%20via%20Substitu/tables/e78e9ae48980cc722920bdf96dd5c34e707995b47ab7a902c1734eaeb745a261.jpg)

## Proximalized Preference Optimization for Diverse Feedback Types: A Decomposed Perspective on DPO


### Images

![20a7d0c1050d1674c3e8ec99084c9122a9170c83ca5915f7808291466fd20e9a.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/images/20a7d0c1050d1674c3e8ec99084c9122a9170c83ca5915f7808291466fd20e9a.jpg)

![67418444b9f7c9c0995ff1542d2724d72115aabe9a88c4f1555ecbd43be02eac.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/images/67418444b9f7c9c0995ff1542d2724d72115aabe9a88c4f1555ecbd43be02eac.jpg)

![828885f0877569102a90f3dd0f8cba6effd95ef44d2b13407bfc6df7547438d7.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/images/828885f0877569102a90f3dd0f8cba6effd95ef44d2b13407bfc6df7547438d7.jpg)

![8f8f1655bbaf6c0300646f16015f014fe143eb65720833a3556bbcf97f33030c.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/images/8f8f1655bbaf6c0300646f16015f014fe143eb65720833a3556bbcf97f33030c.jpg)

![c0444eb40b174cb3321440e35e97b96c55292b9bc300ea211ff1b032fd8ae7ac.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/images/c0444eb40b174cb3321440e35e97b96c55292b9bc300ea211ff1b032fd8ae7ac.jpg)

![ebc77c9aaa8af92011b1df614518bd018c95ae9f807ae415b65341419aabe93d.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/images/ebc77c9aaa8af92011b1df614518bd018c95ae9f807ae415b65341419aabe93d.jpg)

### Tables

![41b8ae88f0eeaa2034f486c5e80e85bb8885d31d86253765b408424bad9f5068.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/tables/41b8ae88f0eeaa2034f486c5e80e85bb8885d31d86253765b408424bad9f5068.jpg)

![51fd693b53d842de1f8449a4b08fde6b7c81f500bc9840ef20245a3b9c6ccc03.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/tables/51fd693b53d842de1f8449a4b08fde6b7c81f500bc9840ef20245a3b9c6ccc03.jpg)

![65477f7c19acca9ce4a5ffe619ffe71faa98277c11ed23af1f9349fab48e3ca8.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/tables/65477f7c19acca9ce4a5ffe619ffe71faa98277c11ed23af1f9349fab48e3ca8.jpg)

![7f656fc9c63efe92315a7a239cf704858f4e3afdd586c8f18434c477e8b03426.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/tables/7f656fc9c63efe92315a7a239cf704858f4e3afdd586c8f18434c477e8b03426.jpg)

![8e92b31057318d872739e57b08e14736b7ac4f78925a2f55d8cee395bd80173d.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/tables/8e92b31057318d872739e57b08e14736b7ac4f78925a2f55d8cee395bd80173d.jpg)

![e8d19d88878dce44f628b1af5d44b7a9d645023840e5120fa7f081426508da9f.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/tables/e8d19d88878dce44f628b1af5d44b7a9d645023840e5120fa7f081426508da9f.jpg)

![ec2371d21b95388de56637b6494ddbe696642152d6f8ad33d9c1c48efafccec6.jpg](../nips_results/2770_Proximalized%20Preference%20Optimization%20for%20Diverse%20Feedback%20Types_%20A%20Decomposed%20Perspective%20on%20DPO/tables/ec2371d21b95388de56637b6494ddbe696642152d6f8ad33d9c1c48efafccec6.jpg)

## Few-Shot Learning from Gigapixel Images via Hierarchical Vision-Language Alignment and Modeling


### Images

![0636a19ebc3100fc40b414873373eed2fb27fb471fba51013a4e58c9fa48ccb0.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/images/0636a19ebc3100fc40b414873373eed2fb27fb471fba51013a4e58c9fa48ccb0.jpg)

![2eb9fd3570ecd97eadc4a77ebbfc15ddac9a5b66af292fa802fc08c5f7a8d72a.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/images/2eb9fd3570ecd97eadc4a77ebbfc15ddac9a5b66af292fa802fc08c5f7a8d72a.jpg)

![368083b508a4077188a5bb12cc36fdd3cdf6b717247df22f1c30e92377d264f1.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/images/368083b508a4077188a5bb12cc36fdd3cdf6b717247df22f1c30e92377d264f1.jpg)

![53105881e25ee1263f0eed1c714c5ae5ca611fdda9bd8c54432ca0354f17e779.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/images/53105881e25ee1263f0eed1c714c5ae5ca611fdda9bd8c54432ca0354f17e779.jpg)

![a959d596787dec0e72d41d00176065d85f9a3bfc88bd9d81a0286637a4e4f898.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/images/a959d596787dec0e72d41d00176065d85f9a3bfc88bd9d81a0286637a4e4f898.jpg)

![b07aba82a6539c6c1a5aded62745501ee6ec34027df7f22238b11a0cff3a4e13.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/images/b07aba82a6539c6c1a5aded62745501ee6ec34027df7f22238b11a0cff3a4e13.jpg)

![be8fadf4f8dffad36fd2d88b1e5c97fd36b5b9dcad4ee5b882bfe4582123f962.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/images/be8fadf4f8dffad36fd2d88b1e5c97fd36b5b9dcad4ee5b882bfe4582123f962.jpg)

![c65303b36396c461c04cb732c1c5bf2e40fa3d853e77646e002c34dcd93ab705.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/images/c65303b36396c461c04cb732c1c5bf2e40fa3d853e77646e002c34dcd93ab705.jpg)

### Tables

![17f0f0f15b9697c066cdda822949791a2b6ddb2df70f008cc66c4f4161b531ff.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/17f0f0f15b9697c066cdda822949791a2b6ddb2df70f008cc66c4f4161b531ff.jpg)

![1eaa9bce7701ca97ba7476ae6c209c6e3e29c8844f136789fbbd01f49872cf00.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/1eaa9bce7701ca97ba7476ae6c209c6e3e29c8844f136789fbbd01f49872cf00.jpg)

![23b97c71e4eaf4455a65bd57fc29eeaa7a1fae9137724544fba0a6d70a274d29.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/23b97c71e4eaf4455a65bd57fc29eeaa7a1fae9137724544fba0a6d70a274d29.jpg)

![25f06824c4420091c94a431bf5d73575a77552538d8a2f9615af0c574f4a0250.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/25f06824c4420091c94a431bf5d73575a77552538d8a2f9615af0c574f4a0250.jpg)

![2eeddc9b47488df7719380a577d5d9719733ae63b9b45c2058cb104168ae831f.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/2eeddc9b47488df7719380a577d5d9719733ae63b9b45c2058cb104168ae831f.jpg)

![2fb7463d8a2cb5bef35009a1a6859b986c9b785df5ff02855a22f4e41591ebed.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/2fb7463d8a2cb5bef35009a1a6859b986c9b785df5ff02855a22f4e41591ebed.jpg)

![33e41ff8eb3aa63d25ddbcc2ab81d15383043db12d56e5ef575526f78c12a006.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/33e41ff8eb3aa63d25ddbcc2ab81d15383043db12d56e5ef575526f78c12a006.jpg)

![5a81f00e305e9ad7055a67f89e09ec2a4cf261a3ceeab1cc1175e57b17d43946.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/5a81f00e305e9ad7055a67f89e09ec2a4cf261a3ceeab1cc1175e57b17d43946.jpg)

![6f68b40db628c99f2565cea3f3c8896ddd17c89effdd90af82a6c7c77ad8affb.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/6f68b40db628c99f2565cea3f3c8896ddd17c89effdd90af82a6c7c77ad8affb.jpg)

![7954fd900b430e5439207e92feecd0247c5c827e3c651a928d17cb3b47998083.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/7954fd900b430e5439207e92feecd0247c5c827e3c651a928d17cb3b47998083.jpg)

![8d9e18879eabcb746b485231284c61628ee0bf9ed23d04a221ed609b408dfc43.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/8d9e18879eabcb746b485231284c61628ee0bf9ed23d04a221ed609b408dfc43.jpg)

![8e385acc4cea1f7b7341fe18e49f8e3944f813e5e7f035ca143509be99535eaa.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/8e385acc4cea1f7b7341fe18e49f8e3944f813e5e7f035ca143509be99535eaa.jpg)

![a619cd8ba463c96c252801e630299e2175b09e0c6d0040956760e41ebdf70981.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/a619cd8ba463c96c252801e630299e2175b09e0c6d0040956760e41ebdf70981.jpg)

![aeea41f893eb784db95ea7ebc8781458655c06a8465b768fff72675ed9a55301.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/aeea41f893eb784db95ea7ebc8781458655c06a8465b768fff72675ed9a55301.jpg)

![bce07f4d874c0dee37c210d37bb1c3b62e06fa7100710d49d89e6c1cbccf489c.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/bce07f4d874c0dee37c210d37bb1c3b62e06fa7100710d49d89e6c1cbccf489c.jpg)

![beefc40b1389ac209736be5a070a9e257fb2c24883ac2732ff8778365b3b82b8.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/beefc40b1389ac209736be5a070a9e257fb2c24883ac2732ff8778365b3b82b8.jpg)

![e7adf520514e406b73598227348e022bd9145e25123626183abd40edc635fb55.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/e7adf520514e406b73598227348e022bd9145e25123626183abd40edc635fb55.jpg)

![facef454535ebb73abd134078fba9b3ae79bfc100c2e64b2b3648e0a9e2c6c66.jpg](../nips_results/2771_Few-Shot%20Learning%20from%20Gigapixel%20Images%20via%20Hierarchical%20Vision-Language%20Alignment%20and%20Modeling/tables/facef454535ebb73abd134078fba9b3ae79bfc100c2e64b2b3648e0a9e2c6c66.jpg)

## PaTH Attention: Position Encoding via Accumulating Householder Transformations


### Images

![38dd14c1f2a8e947b139b4754f093974123e5fe4029ae962960cfed3375b0030.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/images/38dd14c1f2a8e947b139b4754f093974123e5fe4029ae962960cfed3375b0030.jpg)

![3d2ea4416c102708cd11dd15dd2ea3fece8344e1b0d273b2970386500c3a31b4.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/images/3d2ea4416c102708cd11dd15dd2ea3fece8344e1b0d273b2970386500c3a31b4.jpg)

![5c7e79bb3855f5497e24abe68698486cb2de2252ba8e638ad4daa73e9db9e55e.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/images/5c7e79bb3855f5497e24abe68698486cb2de2252ba8e638ad4daa73e9db9e55e.jpg)

![7ea75b65323b6074326bddf7f35e4035c97a3f38d9f7efc5f07bd9bdbc62f7d4.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/images/7ea75b65323b6074326bddf7f35e4035c97a3f38d9f7efc5f07bd9bdbc62f7d4.jpg)

![a8bcd460402ed1960754a324b7e70397009482de6d990903227ad8ca010b457c.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/images/a8bcd460402ed1960754a324b7e70397009482de6d990903227ad8ca010b457c.jpg)

![b6bddee655ab04ad7a8929f34f3f1dd1e4a64eb85b92b9e01c5a2fb79bbeacd4.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/images/b6bddee655ab04ad7a8929f34f3f1dd1e4a64eb85b92b9e01c5a2fb79bbeacd4.jpg)

### Tables

![007bc08c9edc27039841b39ef56e414d9a876bf14536e39b7abbd91fde4b11c9.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/tables/007bc08c9edc27039841b39ef56e414d9a876bf14536e39b7abbd91fde4b11c9.jpg)

![5bed71d5a5b8922131693aaf052e9e4bc746a864a5386c908bdac73f02471201.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/tables/5bed71d5a5b8922131693aaf052e9e4bc746a864a5386c908bdac73f02471201.jpg)

![74c6a7bda3b80e9383cde65e6ecd095f90197fa0edf3394a97d8d0257fc939bf.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/tables/74c6a7bda3b80e9383cde65e6ecd095f90197fa0edf3394a97d8d0257fc939bf.jpg)

![ad80d06489005ac791f5350e29c55438f92277201b94a33630caf52160525408.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/tables/ad80d06489005ac791f5350e29c55438f92277201b94a33630caf52160525408.jpg)

![dc384487ec64d1b04255a84329dfd68e274b9eaae2ff134d81adaabf10bb8a41.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/tables/dc384487ec64d1b04255a84329dfd68e274b9eaae2ff134d81adaabf10bb8a41.jpg)

![e5b668416163bce52b1a2ea906e914af9206e4d0966ae5ef8a4ee4d91f0e0e66.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/tables/e5b668416163bce52b1a2ea906e914af9206e4d0966ae5ef8a4ee4d91f0e0e66.jpg)

![ff3d2512366669e60093e4ac7f38539b9e9e2800e354f203d9dfc96b07cb8885.jpg](../nips_results/2772_PaTH%20Attention_%20Position%20Encoding%20via%20Accumulating%20Householder%20Transformations/tables/ff3d2512366669e60093e4ac7f38539b9e9e2800e354f203d9dfc96b07cb8885.jpg)

## ShortListing Model: A Streamlined Simplex Diffusion for Discrete Variable Generation


### Images

![03f664fd0b84ceb4264cd48fbdac48c8c0b03419434df7a5ec907cd3be1e3dfe.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/images/03f664fd0b84ceb4264cd48fbdac48c8c0b03419434df7a5ec907cd3be1e3dfe.jpg)

![5277f22520f829eb9a07cbbd21cb71e92f593b805c46232ff7e18071d90246ca.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/images/5277f22520f829eb9a07cbbd21cb71e92f593b805c46232ff7e18071d90246ca.jpg)

![63235ad625c199389bf7acaa965e2b69b4dff772243884514706abd2f8ddc8ab.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/images/63235ad625c199389bf7acaa965e2b69b4dff772243884514706abd2f8ddc8ab.jpg)

![85eabe3a30504532f3b1411e09643e35ad39097b8a3ca31afc1d25e9c1e2156c.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/images/85eabe3a30504532f3b1411e09643e35ad39097b8a3ca31afc1d25e9c1e2156c.jpg)

![af571cfa8cba3aa9b3b3a4ffe2a528a5e85247ebd7f440cf471e5b284cff0247.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/images/af571cfa8cba3aa9b3b3a4ffe2a528a5e85247ebd7f440cf471e5b284cff0247.jpg)

![b6eaae5ca6e6463f729d10156c917746a518c7e0f3deef3bcd4134620b809442.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/images/b6eaae5ca6e6463f729d10156c917746a518c7e0f3deef3bcd4134620b809442.jpg)

![bc9565f6423c3cd3314d66c85a2b86410e9ed87b371e85fb9b401cb47db2ac03.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/images/bc9565f6423c3cd3314d66c85a2b86410e9ed87b371e85fb9b401cb47db2ac03.jpg)

![e2b178b584d774534316731daecccb91bd2d2e0754ee1bd05d11ef94cc57f5db.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/images/e2b178b584d774534316731daecccb91bd2d2e0754ee1bd05d11ef94cc57f5db.jpg)

### Tables

![048777c811938094681a1f7605b956766ef9674b1f5868913c5f13393e77a5f7.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/tables/048777c811938094681a1f7605b956766ef9674b1f5868913c5f13393e77a5f7.jpg)

![076abb6bd47e50936eb605aa111a71afb5f54875b459720bef1df40b389ec011.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/tables/076abb6bd47e50936eb605aa111a71afb5f54875b459720bef1df40b389ec011.jpg)

![365090dfadbfde88e19e5f1b6d973615a56f4ffb6b2c6b0356aabb45c03149d0.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/tables/365090dfadbfde88e19e5f1b6d973615a56f4ffb6b2c6b0356aabb45c03149d0.jpg)

![6c116bb60c24f43eb7445a045dd3c51672820d65bd16d4891bd18691998a2ec0.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/tables/6c116bb60c24f43eb7445a045dd3c51672820d65bd16d4891bd18691998a2ec0.jpg)

![8c34b9799f9f06b11241fdd3368c58fb669b9a915f99d7cc09e6e8435f4c465c.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/tables/8c34b9799f9f06b11241fdd3368c58fb669b9a915f99d7cc09e6e8435f4c465c.jpg)

![93c7c72fa6f36909380ddaefddfd657874b97f653cf460503eb74dae34862c33.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/tables/93c7c72fa6f36909380ddaefddfd657874b97f653cf460503eb74dae34862c33.jpg)

![bbd75eb1e6ac23e6e10424ad2c6858e04e6eeb747abc4a5654ade72a60515ba8.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/tables/bbd75eb1e6ac23e6e10424ad2c6858e04e6eeb747abc4a5654ade72a60515ba8.jpg)

![ed14981c988022e1ea54df75fa56b378aee73eecd8b507b951058954cc60121d.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/tables/ed14981c988022e1ea54df75fa56b378aee73eecd8b507b951058954cc60121d.jpg)

![fb4cc04882e1ccbf98e41bdb21357a6b06f0c4f9b26bbae06a11fe94e695f0fd.jpg](../nips_results/2773_ShortListing%20Model_%20A%20Streamlined%20Simplex%20Diffusion%20for%20Discrete%20Variable%20Generation/tables/fb4cc04882e1ccbf98e41bdb21357a6b06f0c4f9b26bbae06a11fe94e695f0fd.jpg)

## DiffBreak: Is Diffusion-Based Purification Robust?


### Images

![076e13c706b5b0e6993a59c3426b3d3366ad8e6e4fc83b6aafe298122f980d79.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/076e13c706b5b0e6993a59c3426b3d3366ad8e6e4fc83b6aafe298122f980d79.jpg)

![0a9fcda51adacd4129d0aa45c523483b8c0682b3dd5fc1cd265752e9180dbe9a.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/0a9fcda51adacd4129d0aa45c523483b8c0682b3dd5fc1cd265752e9180dbe9a.jpg)

![0aebc0f01212fd6fe1ca9490c1fe6af2da3810fd9f7c649e51cf77f34e3f34bd.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/0aebc0f01212fd6fe1ca9490c1fe6af2da3810fd9f7c649e51cf77f34e3f34bd.jpg)

![1bece8eb2fe6dc9d5e80da4e573293908579eef49c06785e64b9d21b64a6df80.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/1bece8eb2fe6dc9d5e80da4e573293908579eef49c06785e64b9d21b64a6df80.jpg)

![25dcc1e1174715f1923e0e67a84fd799ed758655f04ea709ca6cee8c61557f51.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/25dcc1e1174715f1923e0e67a84fd799ed758655f04ea709ca6cee8c61557f51.jpg)

![36882a6da3142b9e797322a34a7ac66be15c8b8fb6aa09cf53de32f773e19ccf.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/36882a6da3142b9e797322a34a7ac66be15c8b8fb6aa09cf53de32f773e19ccf.jpg)

![3c853426f8725a182237b57721c73766527d15f3a58295058f451369bc4defbe.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/3c853426f8725a182237b57721c73766527d15f3a58295058f451369bc4defbe.jpg)

![44851a17d1ef3852904faa549486735c7b0f1f8ac4c3ec68cbc6c0505fe10d66.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/44851a17d1ef3852904faa549486735c7b0f1f8ac4c3ec68cbc6c0505fe10d66.jpg)

![548b1b54e3845999a1917146ac5b9a4480c02e8d5ac3db51d750b831626a271c.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/548b1b54e3845999a1917146ac5b9a4480c02e8d5ac3db51d750b831626a271c.jpg)

![5b3e5b635b6f6e12bce4ed211d332588f9b3af25ada0d30cb99bac8a2b31d433.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/5b3e5b635b6f6e12bce4ed211d332588f9b3af25ada0d30cb99bac8a2b31d433.jpg)

![680d39b3d3ed7e624ddb9c8e60fab3267116a73bc9c10e5163803d0d3a69e63c.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/680d39b3d3ed7e624ddb9c8e60fab3267116a73bc9c10e5163803d0d3a69e63c.jpg)

![7268ba0973a6eb76cff9015522ec0e243ddf4df497c3a174b758af5be4680bb1.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/7268ba0973a6eb76cff9015522ec0e243ddf4df497c3a174b758af5be4680bb1.jpg)

![84514f6b4fc1a66e924c07ffe8122c6633bc9f5205e9c0d9818daa926e1ebe06.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/84514f6b4fc1a66e924c07ffe8122c6633bc9f5205e9c0d9818daa926e1ebe06.jpg)

![858e7b12fb7424f4e90d7969c02505fd3479f3d99937a024b087f13466387e96.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/858e7b12fb7424f4e90d7969c02505fd3479f3d99937a024b087f13466387e96.jpg)

![bfea28b78f8ab9d04a44434335bc8a537af27b81bd61e6073a18a5ca1319fdd5.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/bfea28b78f8ab9d04a44434335bc8a537af27b81bd61e6073a18a5ca1319fdd5.jpg)

![c5c0463b449a63ee918a54f507aef217e2749a771de7aad5f21d76f1903b8f07.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/c5c0463b449a63ee918a54f507aef217e2749a771de7aad5f21d76f1903b8f07.jpg)

![cabd8cfb1b3a6ec09863ce468ea4b990e8f1d21d75fc62e601cb12a4fec70981.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/cabd8cfb1b3a6ec09863ce468ea4b990e8f1d21d75fc62e601cb12a4fec70981.jpg)

![cdfcae896417c0ca064c4bbc1c7100c0759c3a93dcb59e13d1f8ed8625350ce1.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/cdfcae896417c0ca064c4bbc1c7100c0759c3a93dcb59e13d1f8ed8625350ce1.jpg)

![e1dc31bd2ca161bd09478aab86e2aeb60ce746d1a7b229b3df39fdda51c90155.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/e1dc31bd2ca161bd09478aab86e2aeb60ce746d1a7b229b3df39fdda51c90155.jpg)

![f889db60e4fadeaae3d22e177e11a2d4567455a2ba57b7ea35ea7976ceb15f85.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/images/f889db60e4fadeaae3d22e177e11a2d4567455a2ba57b7ea35ea7976ceb15f85.jpg)

### Tables

![16a5a86d8b8c59c3ac431afe22b1bccdfe0a4a190eb1870efe94b70c0ee65087.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/tables/16a5a86d8b8c59c3ac431afe22b1bccdfe0a4a190eb1870efe94b70c0ee65087.jpg)

![4310f1be0625734a4cf643afdfb96322af8852a060416a83c1ab0cbcae694992.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/tables/4310f1be0625734a4cf643afdfb96322af8852a060416a83c1ab0cbcae694992.jpg)

![660d7c0dffeca4125b8a6301ef7030d6ff50303ae43cecdb8c829412aa8df705.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/tables/660d7c0dffeca4125b8a6301ef7030d6ff50303ae43cecdb8c829412aa8df705.jpg)

![cfa7bdc9319f48a75a28317e2dff54ac6c646781c01f2828f49b2c52fe59d4a8.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/tables/cfa7bdc9319f48a75a28317e2dff54ac6c646781c01f2828f49b2c52fe59d4a8.jpg)

![d9f131b06a497a3d2bec1ae8e873e143d0da7d5843ff2938195b9752a6522d8f.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/tables/d9f131b06a497a3d2bec1ae8e873e143d0da7d5843ff2938195b9752a6522d8f.jpg)

![eb28d61c635d1ef36e167b767dab8e3fa6d7814f83657bfa52c346343be7d6ad.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/tables/eb28d61c635d1ef36e167b767dab8e3fa6d7814f83657bfa52c346343be7d6ad.jpg)

![eb6de7de4cb377ae4b3535c5c15131f9c36fb9bc129f62fb2b42801770ee6964.jpg](../nips_results/2774_DiffBreak_%20Is%20Diffusion-Based%20Purification%20Robust_/tables/eb6de7de4cb377ae4b3535c5c15131f9c36fb9bc129f62fb2b42801770ee6964.jpg)

## Generative Model Inversion Through the Lens of the Manifold Hypothesis


### Images

![0c46f5c7392ade44608350d083c7bfecc56009ab90481f42b6622413b8c4cb2c.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/0c46f5c7392ade44608350d083c7bfecc56009ab90481f42b6622413b8c4cb2c.jpg)

![1776e08095cfa5b702e4504bf52caed8f9a5c0789e25080cbef517a9ebf328fe.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/1776e08095cfa5b702e4504bf52caed8f9a5c0789e25080cbef517a9ebf328fe.jpg)

![376b94b5c4ff35159f9147c0c8395bd64651f1ed6bf51db4ddf982f31926e4c1.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/376b94b5c4ff35159f9147c0c8395bd64651f1ed6bf51db4ddf982f31926e4c1.jpg)

![3b91628070e5138100d036fd157cf14f57ee169f3bea592a4b8c07286ba82261.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/3b91628070e5138100d036fd157cf14f57ee169f3bea592a4b8c07286ba82261.jpg)

![41b6c6f61005373f1f0569e21f38e3b4cd4bc28a05d204db3de5ecd3b1a330bd.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/41b6c6f61005373f1f0569e21f38e3b4cd4bc28a05d204db3de5ecd3b1a330bd.jpg)

![4af1e06efb0871ab38ee0a97f9ec9147be806f010ea29eac21f22745c1f3df1d.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/4af1e06efb0871ab38ee0a97f9ec9147be806f010ea29eac21f22745c1f3df1d.jpg)

![4da5c82f4d0df0c7f7243faa4fb92284dd1af14fd04c36d435fce8a5cadaa61d.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/4da5c82f4d0df0c7f7243faa4fb92284dd1af14fd04c36d435fce8a5cadaa61d.jpg)

![55d270a800658bc97797e043853a14c643d283e3421cdbeac41f2de734fca85f.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/55d270a800658bc97797e043853a14c643d283e3421cdbeac41f2de734fca85f.jpg)

![71cdc804330cda45eb9d3d21846d916ede3d70b4e26ba604407779141b00272f.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/71cdc804330cda45eb9d3d21846d916ede3d70b4e26ba604407779141b00272f.jpg)

![87d94ba34f6b6b2431bec2bdfc0b5ce947a2eb9506c078375ac283fb58e2d313.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/87d94ba34f6b6b2431bec2bdfc0b5ce947a2eb9506c078375ac283fb58e2d313.jpg)

![9502ad01e5f89e9f61b0e70035d51a67d520f351764c826bc17a24398ef9fb8e.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/9502ad01e5f89e9f61b0e70035d51a67d520f351764c826bc17a24398ef9fb8e.jpg)

![9756b85281e9de8c4abd4b1972c182f40234e2cd4ac97aec46582b6c9adc5d51.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/9756b85281e9de8c4abd4b1972c182f40234e2cd4ac97aec46582b6c9adc5d51.jpg)

![9fa207ff402c7859438c71033fd4a253e193aad7f8829e20bd44fa77e85a9ed1.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/9fa207ff402c7859438c71033fd4a253e193aad7f8829e20bd44fa77e85a9ed1.jpg)

![ba7da1cff6ec9388e58744dfb3008ccba1190f5949c2807e80af4eeecd492dab.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/ba7da1cff6ec9388e58744dfb3008ccba1190f5949c2807e80af4eeecd492dab.jpg)

![cb4dcc333005e2ac46ba4fd57e95f4a7e1851d61a690c016ab92171953acc8c5.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/cb4dcc333005e2ac46ba4fd57e95f4a7e1851d61a690c016ab92171953acc8c5.jpg)

![cd9813674942d2fe2c6c6b0426837bbfb1adcf4ebc862b30f09267b9f281e90e.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/cd9813674942d2fe2c6c6b0426837bbfb1adcf4ebc862b30f09267b9f281e90e.jpg)

![df44f5641ccf5ddb8599ac73a80031405e31e870c2d6424f2bb327ef6a5a08e7.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/df44f5641ccf5ddb8599ac73a80031405e31e870c2d6424f2bb327ef6a5a08e7.jpg)

![e892f22e45038cc1e3dac3238975af9125bc6e0f33f5831bc025b4397c4da3c7.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/e892f22e45038cc1e3dac3238975af9125bc6e0f33f5831bc025b4397c4da3c7.jpg)

![f5b40a1632e14e5b5175dc1507d1a856ea97338cd1cf2ceb56a114b4a8bb9ac5.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/f5b40a1632e14e5b5175dc1507d1a856ea97338cd1cf2ceb56a114b4a8bb9ac5.jpg)

![f9c82eee555b6a2f4fef595644b401d016f575260f149c2fbbec273ad5603217.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/f9c82eee555b6a2f4fef595644b401d016f575260f149c2fbbec273ad5603217.jpg)

![fbb120dd64b47d7d3ea0a3fca1c45cf80cc072eb407bc3c506ca52f1f5ecbb28.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/images/fbb120dd64b47d7d3ea0a3fca1c45cf80cc072eb407bc3c506ca52f1f5ecbb28.jpg)

### Tables

![0394e71b37e02f6f47827d8ea1c6da494b13031b6c3f728ea6a196f56cbe02f1.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/0394e71b37e02f6f47827d8ea1c6da494b13031b6c3f728ea6a196f56cbe02f1.jpg)

![211aad4465a3759223bcaf3fe4e85947893f5ce96369086904f77f86b85073c8.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/211aad4465a3759223bcaf3fe4e85947893f5ce96369086904f77f86b85073c8.jpg)

![2b8a8de4f36f86d6b309a3f6873cc417cc3eb0c28f89d41865b2bbc2403370d7.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/2b8a8de4f36f86d6b309a3f6873cc417cc3eb0c28f89d41865b2bbc2403370d7.jpg)

![34cfb99006c04556d37e4dbb796180f33ae49272d0686424865fdcf2c9ddf190.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/34cfb99006c04556d37e4dbb796180f33ae49272d0686424865fdcf2c9ddf190.jpg)

![35f2da9ee4b077c9fb90feaf912d3060b10fb5bfa2ef647d11bfb8598696094d.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/35f2da9ee4b077c9fb90feaf912d3060b10fb5bfa2ef647d11bfb8598696094d.jpg)

![4525c2b204ad89d6413edcd6266bb1411640bc93db6afd7d232a320806f69483.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/4525c2b204ad89d6413edcd6266bb1411640bc93db6afd7d232a320806f69483.jpg)

![52a53c13e05f77d221caec31c3c939385d953edef59a5ebbf7b0063850cfd5af.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/52a53c13e05f77d221caec31c3c939385d953edef59a5ebbf7b0063850cfd5af.jpg)

![5c8f29315df06ba48574a6c00627df1db73e680ee3a88e06f7d9ccef0c9a00e3.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/5c8f29315df06ba48574a6c00627df1db73e680ee3a88e06f7d9ccef0c9a00e3.jpg)

![71e7af095057e8856f9d133b8c2f718e854e41831210efbd07dcffe889fea53a.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/71e7af095057e8856f9d133b8c2f718e854e41831210efbd07dcffe889fea53a.jpg)

![a87532b84fdaad36bcd7da01df1b7aef25949f283e24199ad89badfb15d55275.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/a87532b84fdaad36bcd7da01df1b7aef25949f283e24199ad89badfb15d55275.jpg)

![c938f9b03ea59dfcc6bdba2bba3cef757ec3d80d1f2429e98d431c83d29300fd.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/c938f9b03ea59dfcc6bdba2bba3cef757ec3d80d1f2429e98d431c83d29300fd.jpg)

![f0fa3ab96fd0d42510a851cb26a69a37924d9cfddd44cab36bc9a9dc7e086661.jpg](../nips_results/2775_Generative%20Model%20Inversion%20Through%20the%20Lens%20of%20the%20Manifold%20Hypothesis/tables/f0fa3ab96fd0d42510a851cb26a69a37924d9cfddd44cab36bc9a9dc7e086661.jpg)

## Energy Landscape-Aware Vision Transformers: Layerwise Dynamics and Adaptive Task-Specific Training via Hopfield States


### Images

![77f7be03cc78710e05dac92f5024d745ed9bf3a1402cc65d9348cb55ebeb8749.jpg](../nips_results/2776_Energy%20Landscape-Aware%20Vision%20Transformers_%20Layerwise%20Dynamics%20and%20Adaptive%20Task-Specific%20Training%20v/images/77f7be03cc78710e05dac92f5024d745ed9bf3a1402cc65d9348cb55ebeb8749.jpg)

![ec5863de65ed845430951acb88feb40b0e560a62b90e243088eddb1180c511d2.jpg](../nips_results/2776_Energy%20Landscape-Aware%20Vision%20Transformers_%20Layerwise%20Dynamics%20and%20Adaptive%20Task-Specific%20Training%20v/images/ec5863de65ed845430951acb88feb40b0e560a62b90e243088eddb1180c511d2.jpg)

### Tables

![1dc7361bb22f7fd362b67f7d54931cc8047e1d792a3846adc5efd4d3417a504e.jpg](../nips_results/2776_Energy%20Landscape-Aware%20Vision%20Transformers_%20Layerwise%20Dynamics%20and%20Adaptive%20Task-Specific%20Training%20v/tables/1dc7361bb22f7fd362b67f7d54931cc8047e1d792a3846adc5efd4d3417a504e.jpg)

![35d98e015fe3f25e95aef349ce27a2db73ac4552a36ef0257ef461ce69081fcf.jpg](../nips_results/2776_Energy%20Landscape-Aware%20Vision%20Transformers_%20Layerwise%20Dynamics%20and%20Adaptive%20Task-Specific%20Training%20v/tables/35d98e015fe3f25e95aef349ce27a2db73ac4552a36ef0257ef461ce69081fcf.jpg)

![8d908ed409940d391620ef5fa9660dd90fd3fb7e3d627072d91e640e3521544c.jpg](../nips_results/2776_Energy%20Landscape-Aware%20Vision%20Transformers_%20Layerwise%20Dynamics%20and%20Adaptive%20Task-Specific%20Training%20v/tables/8d908ed409940d391620ef5fa9660dd90fd3fb7e3d627072d91e640e3521544c.jpg)

## Modeling Cell Dynamics and Interactions with Unbalanced Mean Field Schrödinger Bridge


### Images

![459f43b109b53e9a07f909ff6cb7374252ab5403cdf4bdc6235cb0a3f23116aa.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/images/459f43b109b53e9a07f909ff6cb7374252ab5403cdf4bdc6235cb0a3f23116aa.jpg)

![78bad2f6a0554ccf8d29ba6eae52d4d35fcc22fcd747c1455b3fd52a91e5ff44.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/images/78bad2f6a0554ccf8d29ba6eae52d4d35fcc22fcd747c1455b3fd52a91e5ff44.jpg)

![876532954a91080ed7da5a723d84f5713af88a244753b7137563db71eb13ba59.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/images/876532954a91080ed7da5a723d84f5713af88a244753b7137563db71eb13ba59.jpg)

![9030f5ff8279b34dfb8569ab759d9bb1c0eaeec43c9c326dde578678242ce073.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/images/9030f5ff8279b34dfb8569ab759d9bb1c0eaeec43c9c326dde578678242ce073.jpg)

![a3d6c926db7856a8de41e36140b9eb318316730c1742751d303bbc7cc27351ba.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/images/a3d6c926db7856a8de41e36140b9eb318316730c1742751d303bbc7cc27351ba.jpg)

![af94407e8548a1ab6d66ddddb08d8d0e23c40e5aee0c940a270fc5e4a01635ee.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/images/af94407e8548a1ab6d66ddddb08d8d0e23c40e5aee0c940a270fc5e4a01635ee.jpg)

![d838cb06d07799251f4995df1edd43808619a15414743767e5075a44ee5d4dd5.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/images/d838cb06d07799251f4995df1edd43808619a15414743767e5075a44ee5d4dd5.jpg)

![dd7513024e9afc33daa4a0def2d85e83dedd98d15ec9eedeb04216a9dfe6a61d.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/images/dd7513024e9afc33daa4a0def2d85e83dedd98d15ec9eedeb04216a9dfe6a61d.jpg)

![e0356ddc403fa275c28d192fb3c96d2338aacaf7b30a9f0ade841036771080bb.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/images/e0356ddc403fa275c28d192fb3c96d2338aacaf7b30a9f0ade841036771080bb.jpg)

### Tables

![19a7574e78f5c25b87f25855bdf5edb637505dad6d1873f5cb0a1dc0417858a2.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/19a7574e78f5c25b87f25855bdf5edb637505dad6d1873f5cb0a1dc0417858a2.jpg)

![24c82f294aefff3de762ad22c6859e085510b4000357d4c8883674ad05dd0838.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/24c82f294aefff3de762ad22c6859e085510b4000357d4c8883674ad05dd0838.jpg)

![266093578c480caf1fbb421b6652a0bfd9088ea202bd1e6fa9d8950c2c7c6ab3.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/266093578c480caf1fbb421b6652a0bfd9088ea202bd1e6fa9d8950c2c7c6ab3.jpg)

![2919517413724b69594843234d10bd11e4502bc1c45960e0b4ab00c251d7cb45.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/2919517413724b69594843234d10bd11e4502bc1c45960e0b4ab00c251d7cb45.jpg)

![34be6e7610aca3a642b32e4cb98db909ab3125e8f8455f02b7000e52eb871567.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/34be6e7610aca3a642b32e4cb98db909ab3125e8f8455f02b7000e52eb871567.jpg)

![397bcd5e3bf4cc77b9958e6b3dd7158316e2121b7823d35274aa7a8d897aabef.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/397bcd5e3bf4cc77b9958e6b3dd7158316e2121b7823d35274aa7a8d897aabef.jpg)

![43b82019a3fcd4471b401f02d84407258a5cfea6134b9007c1baaec51d2677b9.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/43b82019a3fcd4471b401f02d84407258a5cfea6134b9007c1baaec51d2677b9.jpg)

![441de9f9e68f9820ddfca00fab5ed0567dbc851f528e23e287aa9f3557d6dd6f.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/441de9f9e68f9820ddfca00fab5ed0567dbc851f528e23e287aa9f3557d6dd6f.jpg)

![50b10248ae49eac2da186627a2bd5f3da659326b236a1e82b3ad2171e8607ed2.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/50b10248ae49eac2da186627a2bd5f3da659326b236a1e82b3ad2171e8607ed2.jpg)

![5b082eb5e3f09b29a2d7795bf600e9715dab70060e77b8388de0f4cf8e0ab669.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/5b082eb5e3f09b29a2d7795bf600e9715dab70060e77b8388de0f4cf8e0ab669.jpg)

![761c6da52ce42fec28da0d69fcf30d4d0b774300fb6f0e8ea441d31f9b82380a.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/761c6da52ce42fec28da0d69fcf30d4d0b774300fb6f0e8ea441d31f9b82380a.jpg)

![77edb4538d432b10cbdc24431f7c167ee99b6ec46be52ed6e3027ec76447d1f5.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/77edb4538d432b10cbdc24431f7c167ee99b6ec46be52ed6e3027ec76447d1f5.jpg)

![a5262832c05ce901df5e98acf1a23c0a7c59f5ab54685628c8e11e9c9eda3169.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/a5262832c05ce901df5e98acf1a23c0a7c59f5ab54685628c8e11e9c9eda3169.jpg)

![b1b1e0ec938a9895617ffd67e7bf5bddf0122dcc80ee07f29ffae0febe3b9e59.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/b1b1e0ec938a9895617ffd67e7bf5bddf0122dcc80ee07f29ffae0febe3b9e59.jpg)

![c635c92f0c136f1478e4309b01c482a345510f9fc7cd34c4619de322a50e3329.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/c635c92f0c136f1478e4309b01c482a345510f9fc7cd34c4619de322a50e3329.jpg)

![d10899a90126beb2545b1afba803bfb27f9009b26a3fc81852c0a088b11fd4c9.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/d10899a90126beb2545b1afba803bfb27f9009b26a3fc81852c0a088b11fd4c9.jpg)

![d6b52521214e07e5813b8f6c305ddd42ec5140c07a9b76412eaa502c19343363.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/d6b52521214e07e5813b8f6c305ddd42ec5140c07a9b76412eaa502c19343363.jpg)

![d7f111b9662d7f415ec81492163e076ded703a0b606569b44bf53461652dcb06.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/d7f111b9662d7f415ec81492163e076ded703a0b606569b44bf53461652dcb06.jpg)

![dd39bd18592bafcafed3dfc1a7228218398987900c025355dfce9c9a128eac6f.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/dd39bd18592bafcafed3dfc1a7228218398987900c025355dfce9c9a128eac6f.jpg)

![e3cac8fdca52f9271608dd609dbee5401613249c1bfc9e57f734f58b33e9f06a.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/e3cac8fdca52f9271608dd609dbee5401613249c1bfc9e57f734f58b33e9f06a.jpg)

![ea7724ac2bb0764b00b5a3e2e2f74afe5913946053681d020ca8d726b3be7f57.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/ea7724ac2bb0764b00b5a3e2e2f74afe5913946053681d020ca8d726b3be7f57.jpg)

![f8da088e5585e35aa18161c972d073a2ac2143a06c2b026636f36e8a90208b18.jpg](../nips_results/2777_Modeling%20Cell%20Dynamics%20and%20Interactions%20with%20Unbalanced%20Mean%20Field%20Schr%C3%B6dinger%20Bridge/tables/f8da088e5585e35aa18161c972d073a2ac2143a06c2b026636f36e8a90208b18.jpg)

## GOATex: Geometry & Occlusion-Aware Texturing


### Images

![17983aedb5e85e158f46dbbb9f493f2ac6e306bd6273077d95293d10490e1ce0.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/17983aedb5e85e158f46dbbb9f493f2ac6e306bd6273077d95293d10490e1ce0.jpg)

![17a741dffcd6aceb0f02ad268cc3a8f8b605ada23b4d096f783d7fa927378b4a.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/17a741dffcd6aceb0f02ad268cc3a8f8b605ada23b4d096f783d7fa927378b4a.jpg)

![1f7add1cd24290def6685b1806073dacbf1894d51561503eb07288cf502f2eec.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/1f7add1cd24290def6685b1806073dacbf1894d51561503eb07288cf502f2eec.jpg)

![2671ca2d32342f7d5f545d15479abb143f808b5d2328416b0603cec8c20f2abc.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/2671ca2d32342f7d5f545d15479abb143f808b5d2328416b0603cec8c20f2abc.jpg)

![2968ffe93a010f32789728ddaded8b3cd1e410448dfbb6d032f7f9de9ad8ca53.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/2968ffe93a010f32789728ddaded8b3cd1e410448dfbb6d032f7f9de9ad8ca53.jpg)

![35ce4ab43d4490bddacd03ab38e5cf3c0b4ff2f612a378193a9734848d7ef66c.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/35ce4ab43d4490bddacd03ab38e5cf3c0b4ff2f612a378193a9734848d7ef66c.jpg)

![4abd0c59f12260f6e508ed63d3498faf6e01564c6bdbc151140fe36fca07ef52.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/4abd0c59f12260f6e508ed63d3498faf6e01564c6bdbc151140fe36fca07ef52.jpg)

![4b8a32d39ea5bac4b4c0163917120b0abd5049bc1cd46d1a2df65be3667c34c5.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/4b8a32d39ea5bac4b4c0163917120b0abd5049bc1cd46d1a2df65be3667c34c5.jpg)

![633eb3e7f5345d34c805b209c58e698fa00eb562701744658cc91413e87a2e9b.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/633eb3e7f5345d34c805b209c58e698fa00eb562701744658cc91413e87a2e9b.jpg)

![786f25bb638c07b74969ccfd520e8030e338cde6b3ede08b34b3ec524a396062.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/786f25bb638c07b74969ccfd520e8030e338cde6b3ede08b34b3ec524a396062.jpg)

![796ae6c5a9a6ba44c9aadf4aa2a44c22f4f17a38893f76d66cfc2e9aacd48947.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/796ae6c5a9a6ba44c9aadf4aa2a44c22f4f17a38893f76d66cfc2e9aacd48947.jpg)

![7bd2472b577e81bb72c8e4af399cbe54ad64c8c8c3072a9951317d1eda604a0f.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/7bd2472b577e81bb72c8e4af399cbe54ad64c8c8c3072a9951317d1eda604a0f.jpg)

![7d3b2e00c075c1b69cb1c01827c0e1aff2f385ebb67dd4b60c97a7d2a6d3b306.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/7d3b2e00c075c1b69cb1c01827c0e1aff2f385ebb67dd4b60c97a7d2a6d3b306.jpg)

![8688962c94d8b737bf87ffc4e8625eba25b1baca943e0ef1453f844470e2aa74.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/8688962c94d8b737bf87ffc4e8625eba25b1baca943e0ef1453f844470e2aa74.jpg)

![8c7fd05feb87b59548b563af818f464b3de6476d3114b760fc0902799e68a0bf.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/8c7fd05feb87b59548b563af818f464b3de6476d3114b760fc0902799e68a0bf.jpg)

![959d4318a450272e9f5d017ff5a65c532ab42a498ba548770f426e34a14db5b7.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/959d4318a450272e9f5d017ff5a65c532ab42a498ba548770f426e34a14db5b7.jpg)

![993022c432cdfac5ba96094e69205f1bd871309635645d131461547898b508b0.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/993022c432cdfac5ba96094e69205f1bd871309635645d131461547898b508b0.jpg)

![9e623696b6ace804e84d8d033432a911ad95fecb3cfe7c4e91b5b1c53e0b36f1.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/9e623696b6ace804e84d8d033432a911ad95fecb3cfe7c4e91b5b1c53e0b36f1.jpg)

![9ff179dcb45a7202ac213b6006c4ed353cd087070c3a755b5129aa33a9c649dd.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/9ff179dcb45a7202ac213b6006c4ed353cd087070c3a755b5129aa33a9c649dd.jpg)

![a42ba62748e1c766126dc675148c5b2848ab248c39dd76b8345b05b2a73eabd3.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/a42ba62748e1c766126dc675148c5b2848ab248c39dd76b8345b05b2a73eabd3.jpg)

![bd6dcfb40d79b72ad3f5720a273ba581f9377ed50a17d57ee56b1ec79207f3a8.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/bd6dcfb40d79b72ad3f5720a273ba581f9377ed50a17d57ee56b1ec79207f3a8.jpg)

![cd00d376b745441a9ba70bd7bb24aa9af66f57630f999bfba33fe21b7dff5911.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/cd00d376b745441a9ba70bd7bb24aa9af66f57630f999bfba33fe21b7dff5911.jpg)

![ed79a634d66ee2c76130385f9f38358e095fa1a281db7d90c69d2642301038fa.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/ed79a634d66ee2c76130385f9f38358e095fa1a281db7d90c69d2642301038fa.jpg)

![fd2bed712ca71752b37957461883fe753720fb81e6297bbb875dcc643b1235c0.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/images/fd2bed712ca71752b37957461883fe753720fb81e6297bbb875dcc643b1235c0.jpg)

### Tables

![563fdab851026ba7c44c03a4d165dd81f88281aef8fce41eaa33313346976acd.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/tables/563fdab851026ba7c44c03a4d165dd81f88281aef8fce41eaa33313346976acd.jpg)

![5bc5a8978d46cc1bcb001d5a0f895f7253b68d11d70c34d17d060d7559410f21.jpg](../nips_results/2778_GOATex_%20Geometry%20%26%20Occlusion-Aware%20Texturing/tables/5bc5a8978d46cc1bcb001d5a0f895f7253b68d11d70c34d17d060d7559410f21.jpg)

## Understand Before You Generate: Self-Guided Training for Autoregressive Image Generation


### Images

![034a6b9396e5ab2cd9035a550c600400cf4f94b7a6f039c3d43b70c0e95a16e7.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/images/034a6b9396e5ab2cd9035a550c600400cf4f94b7a6f039c3d43b70c0e95a16e7.jpg)

![8270a0d60113e8463997f16e650026e6e35973f08a4f32477d96ada037de02b4.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/images/8270a0d60113e8463997f16e650026e6e35973f08a4f32477d96ada037de02b4.jpg)

![8621bfc6deb19649e6201a99f8210c2bfec29e1878e161b0ce30bb0880dda81c.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/images/8621bfc6deb19649e6201a99f8210c2bfec29e1878e161b0ce30bb0880dda81c.jpg)

![981abe5456a97a11fef93a455622c11afdaf8c0e7d2c00b52b7b7635a8779f7c.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/images/981abe5456a97a11fef93a455622c11afdaf8c0e7d2c00b52b7b7635a8779f7c.jpg)

![c4b3318e33b264f2b383866f5c753670ff1bc102968d64481d9e3b769fb7aa13.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/images/c4b3318e33b264f2b383866f5c753670ff1bc102968d64481d9e3b769fb7aa13.jpg)

![f3194300340727244a2baf74dda357c55b9dfdea02ed2ec58eef2b0d81830b98.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/images/f3194300340727244a2baf74dda357c55b9dfdea02ed2ec58eef2b0d81830b98.jpg)

![ff21d0f9683124ea3dd4d77737b1593c381cdb1e4b25089f6b88bfb3992bfbed.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/images/ff21d0f9683124ea3dd4d77737b1593c381cdb1e4b25089f6b88bfb3992bfbed.jpg)

### Tables

![10e8fb78e6d6764f3931f7af0a95e7f8079ec2c1256f5857717bb00aed81f854.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/tables/10e8fb78e6d6764f3931f7af0a95e7f8079ec2c1256f5857717bb00aed81f854.jpg)

![14203bd069ff4282b3d7062c2115251fb46da4a498147908b2505517ced7255b.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/tables/14203bd069ff4282b3d7062c2115251fb46da4a498147908b2505517ced7255b.jpg)

![76d9acab392f96a403b53ad06fea1d5c6e9e4409efecdcc4e9c44eb534c21d4e.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/tables/76d9acab392f96a403b53ad06fea1d5c6e9e4409efecdcc4e9c44eb534c21d4e.jpg)

![a46866b5686156841092d1111a2264840a9977b1a94ce3b78f8e68d53fcadc80.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/tables/a46866b5686156841092d1111a2264840a9977b1a94ce3b78f8e68d53fcadc80.jpg)

![b4da8f842dc8c809652624a9580c6b4e8d8fef687e5171e019a0ac60245509db.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/tables/b4da8f842dc8c809652624a9580c6b4e8d8fef687e5171e019a0ac60245509db.jpg)

![ee4123283ecea9f088f78d7012d72d9566447fe8e587fee366df9683b8f7a540.jpg](../nips_results/2779_Understand%20Before%20You%20Generate_%20Self-Guided%20Training%20for%20Autoregressive%20Image%20Generation/tables/ee4123283ecea9f088f78d7012d72d9566447fe8e587fee366df9683b8f7a540.jpg)

## Structure-Aware Spectral Sparsification via Uniform Edge Sampling


### Images

![1958510f596eb60d462bb3302d0a6194bc1d5cb0b4686897b986df59cdfa4877.jpg](../nips_results/2780_Structure-Aware%20Spectral%20Sparsification%20via%20Uniform%20Edge%20Sampling/images/1958510f596eb60d462bb3302d0a6194bc1d5cb0b4686897b986df59cdfa4877.jpg)

![74e6c48329775a3f037e4c136e958c420a187c5c6d6604871286a494a3f915bd.jpg](../nips_results/2780_Structure-Aware%20Spectral%20Sparsification%20via%20Uniform%20Edge%20Sampling/images/74e6c48329775a3f037e4c136e958c420a187c5c6d6604871286a494a3f915bd.jpg)

![b002cd2c2cba360361206c3cdce08b413b1d6f3726f917a6f1e66f689ca9b81e.jpg](../nips_results/2780_Structure-Aware%20Spectral%20Sparsification%20via%20Uniform%20Edge%20Sampling/images/b002cd2c2cba360361206c3cdce08b413b1d6f3726f917a6f1e66f689ca9b81e.jpg)

![e392c7274b606d3d14d602b48a85e2ca09cac082ea19906a8c8ae965a474dbd9.jpg](../nips_results/2780_Structure-Aware%20Spectral%20Sparsification%20via%20Uniform%20Edge%20Sampling/images/e392c7274b606d3d14d602b48a85e2ca09cac082ea19906a8c8ae965a474dbd9.jpg)

## SceneDecorator: Towards Scene-Oriented Story Generation with Scene Planning and Scene Consistency


### Images

![1606aa53243f50957ae046eb8f7ee2207dab5d406a1920184e3dc6ed915941fe.jpg](../nips_results/2781_SceneDecorator_%20Towards%20Scene-Oriented%20Story%20Generation%20with%20Scene%20Planning%20and%20Scene%20Consistency/images/1606aa53243f50957ae046eb8f7ee2207dab5d406a1920184e3dc6ed915941fe.jpg)

![4bea760993f735a888b5583bccbe9686402625417f37dd2f45cece5b160ad6be.jpg](../nips_results/2781_SceneDecorator_%20Towards%20Scene-Oriented%20Story%20Generation%20with%20Scene%20Planning%20and%20Scene%20Consistency/images/4bea760993f735a888b5583bccbe9686402625417f37dd2f45cece5b160ad6be.jpg)

### Tables

![5b0b408a4459c06069cf0e0c973e6dfa022b57b47d103d9c58edd1b6e1eb166e.jpg](../nips_results/2781_SceneDecorator_%20Towards%20Scene-Oriented%20Story%20Generation%20with%20Scene%20Planning%20and%20Scene%20Consistency/tables/5b0b408a4459c06069cf0e0c973e6dfa022b57b47d103d9c58edd1b6e1eb166e.jpg)

![89247f2716833f0f0df8308e4b75708d8fbbf9df0ab5ba318311de41764ae0b8.jpg](../nips_results/2781_SceneDecorator_%20Towards%20Scene-Oriented%20Story%20Generation%20with%20Scene%20Planning%20and%20Scene%20Consistency/tables/89247f2716833f0f0df8308e4b75708d8fbbf9df0ab5ba318311de41764ae0b8.jpg)

![e2c99676b9d5bf16e05e12b6688cf63c7fda920227586eaf56f5fc43a7935f1f.jpg](../nips_results/2781_SceneDecorator_%20Towards%20Scene-Oriented%20Story%20Generation%20with%20Scene%20Planning%20and%20Scene%20Consistency/tables/e2c99676b9d5bf16e05e12b6688cf63c7fda920227586eaf56f5fc43a7935f1f.jpg)

![e344ef9125f9d144d5a2ba41817ea2b55e1b8621b9008aaae145c5f05d4943d3.jpg](../nips_results/2781_SceneDecorator_%20Towards%20Scene-Oriented%20Story%20Generation%20with%20Scene%20Planning%20and%20Scene%20Consistency/tables/e344ef9125f9d144d5a2ba41817ea2b55e1b8621b9008aaae145c5f05d4943d3.jpg)

![f84abcdf30cc0243f839e884a7da46a35e36fdaa09d52f4a7e7653382d5c623c.jpg](../nips_results/2781_SceneDecorator_%20Towards%20Scene-Oriented%20Story%20Generation%20with%20Scene%20Planning%20and%20Scene%20Consistency/tables/f84abcdf30cc0243f839e884a7da46a35e36fdaa09d52f4a7e7653382d5c623c.jpg)

## Joint Relational Database Generation via Graph-Conditional Diffusion Models


### Images

![87933dd395f7bbe57515f8fc5f6bae85e52c03bd967377ad48ef4f48e040c00c.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/images/87933dd395f7bbe57515f8fc5f6bae85e52c03bd967377ad48ef4f48e040c00c.jpg)

![a705e931b13fd730ffb3befef649b4cbb063a00e7ad4080e103a2d73c559035d.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/images/a705e931b13fd730ffb3befef649b4cbb063a00e7ad4080e103a2d73c559035d.jpg)

### Tables

![14d3deb22494a16a18e8f1d19c4c22ac0b1b283f5b3a67ed6cb14424147d4dca.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/tables/14d3deb22494a16a18e8f1d19c4c22ac0b1b283f5b3a67ed6cb14424147d4dca.jpg)

![4e4e94f232a49aeb35cbc2b278d7c51fc9cc6a113c747ad81adf13f7ce5c5aa7.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/tables/4e4e94f232a49aeb35cbc2b278d7c51fc9cc6a113c747ad81adf13f7ce5c5aa7.jpg)

![520d1245c2fe7488ce04ea4d36a35263a367691eed07af4a0a441f52397bf745.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/tables/520d1245c2fe7488ce04ea4d36a35263a367691eed07af4a0a441f52397bf745.jpg)

![63bec413afa133bdf531df0db5586044c7d89d243442f6dfd43085f9793b5886.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/tables/63bec413afa133bdf531df0db5586044c7d89d243442f6dfd43085f9793b5886.jpg)

![7c8daba52237c9fa698daecaf80cbf3539b40b8144e4dd21e55e4ca05e8c1b50.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/tables/7c8daba52237c9fa698daecaf80cbf3539b40b8144e4dd21e55e4ca05e8c1b50.jpg)

![8559f28a26a3ee244bda2f673da0a6d080912b91cd860178cb0fdc35825a4ef2.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/tables/8559f28a26a3ee244bda2f673da0a6d080912b91cd860178cb0fdc35825a4ef2.jpg)

![b67aa6d42f4e4541dcd66252f1f2e16be2aa50a79183b6ceca8e02a24dc5b6b5.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/tables/b67aa6d42f4e4541dcd66252f1f2e16be2aa50a79183b6ceca8e02a24dc5b6b5.jpg)

![bd0251eabf15e4200f190e9f0952562da319816123e2af496b5a81e1e029e35d.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/tables/bd0251eabf15e4200f190e9f0952562da319816123e2af496b5a81e1e029e35d.jpg)

![efc40141ebd5f3d4b53fa133c4401ce32f3f415252b1943499fd4bf2343e1cfe.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/tables/efc40141ebd5f3d4b53fa133c4401ce32f3f415252b1943499fd4bf2343e1cfe.jpg)

![fb80b7db9eb11711e11cfdaaafe0c858bafd5b4dd5b654ab00bd9fa7da89ee5b.jpg](../nips_results/2782_Joint%20Relational%20Database%20Generation%20via%20Graph-Conditional%20Diffusion%20Models/tables/fb80b7db9eb11711e11cfdaaafe0c858bafd5b4dd5b654ab00bd9fa7da89ee5b.jpg)

## Is Your Diffusion Model Actually Denoising?

### Images

![0c2c370fd69678aa57e350fd3c7d7d51aa8f518b18b75368a455d253995baf46.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/0c2c370fd69678aa57e350fd3c7d7d51aa8f518b18b75368a455d253995baf46.jpg)

![13d6036d7a292e37ba86f212dec6aa73fe6314c75a20ec690b374b4dcde03f56.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/13d6036d7a292e37ba86f212dec6aa73fe6314c75a20ec690b374b4dcde03f56.jpg)

![2169b5fb57a54d829616dd2bd3738e9e225755f82b6eec43e577a1a19ca0b592.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/2169b5fb57a54d829616dd2bd3738e9e225755f82b6eec43e577a1a19ca0b592.jpg)

![36f5adacbd00bd50ed16cf9ad05437ee7e1ebbf66d42ec446c604d76e9b4fd8a.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/36f5adacbd00bd50ed16cf9ad05437ee7e1ebbf66d42ec446c604d76e9b4fd8a.jpg)

![4be24e3c339c6aabbbaf5233adb0b4e037396da4f3f77ab9cd7f2676a329f8bf.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/4be24e3c339c6aabbbaf5233adb0b4e037396da4f3f77ab9cd7f2676a329f8bf.jpg)

![6c759ead3041844f831863abffd5b737cb94c985af72a32145d05084c29c03ba.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/6c759ead3041844f831863abffd5b737cb94c985af72a32145d05084c29c03ba.jpg)

![6e8c2b2cf412e2dc10fd14c089c91daad7e31673cf9d0eff9a3ec4df390b041d.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/6e8c2b2cf412e2dc10fd14c089c91daad7e31673cf9d0eff9a3ec4df390b041d.jpg)

![83cbd4a5757cf0f7a0262f73eadf267f03115ac713e286b98372283d0f31d8f1.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/83cbd4a5757cf0f7a0262f73eadf267f03115ac713e286b98372283d0f31d8f1.jpg)

![918a9866bdce1a39227acfa1c815eac02e3879f256c54ae9591309e7fb940a03.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/918a9866bdce1a39227acfa1c815eac02e3879f256c54ae9591309e7fb940a03.jpg)

![a168cbdc87c82afcb37b7c430cb1eb45f88a5acb7b81e823938c194afb262ef4.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/a168cbdc87c82afcb37b7c430cb1eb45f88a5acb7b81e823938c194afb262ef4.jpg)

![b8c51c92dd4d0a55e9418aeca801f67eded5d8c18122700d9a37cb3e21e875bc.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/b8c51c92dd4d0a55e9418aeca801f67eded5d8c18122700d9a37cb3e21e875bc.jpg)

![bba873ebbbec411188f20d986529ac8cd8d0118a9d1548393439e62f59e5e6ee.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/bba873ebbbec411188f20d986529ac8cd8d0118a9d1548393439e62f59e5e6ee.jpg)

![e150e34d4fad625d569241fe6d471df4f7c21442d8e86f1c05bb91373be78ba9.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/e150e34d4fad625d569241fe6d471df4f7c21442d8e86f1c05bb91373be78ba9.jpg)

![e19606a94147c0a856d458d7a2c7a692615be68d6822ef90aa81a486a61dfb23.jpg](../nips_results/2783_Is%20Your%20Diffusion%20Model%20Actually%20Denoising_/images/e19606a94147c0a856d458d7a2c7a692615be68d6822ef90aa81a486a61dfb23.jpg)
