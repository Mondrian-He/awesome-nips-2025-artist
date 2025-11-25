# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 123 of 130

## 目录 (Table of Contents)

1. [Inference with correlated priors using sisters cells](#Inference-with-correlated-priors-using-sisters-cells)
2. [A Finite Sample Analysis of Distributional TD Learning with Linear Function Approximation](#A-Finite-Sample-Analysis-of-Distributional-TD-Learning-with-Linear-Function-Approximation)
3. [RePO: Understanding Preference Learning Through ReLU-Based Optimization](#RePO-Understanding-Preference-Learning-Through-ReLU-Based-Optimization)
4. [Synergy over Discrepancy: A Partition-Based Approach to Multi-Domain LLM Fine-Tuning](#Synergy-over-Discrepancy-A-Partition-Based-Approach-to-Multi-Domain-LLM-Fine-Tuning)
5. [R-KV: Redundancy-aware KV Cache Compression for Reasoning Models](#R-KV-Redundancy-aware-KV-Cache-Compression-for-Reasoning-Models)
6. [FairDICE: Fairness-Driven Offline Multi-Objective Reinforcement Learning](#FairDICE-Fairness-Driven-Offline-Multi-Objective-Reinforcement-Learning)
7. [Online Inverse Linear Optimization: Efficient Logarithmic-Regret Algorithm, Robustness to Suboptimality, and Lower Bound](#Online-Inverse-Linear-Optimization-Efficient-Logarithmic-Regret-Algorithm-Robustness-to-Suboptimality-and-Lower-Bound)
8. [Bridging Scales: Spectral Theory Reveals How Local Connectivity Rules Sculpt Global Neural Dynamics in Spatially Extended Networks](#Bridging-Scales-Spectral-Theory-Reveals-How-Local-Connectivity-Rules-Sculpt-Global-Neural-Dynamics-in-Spatially-Extended-Networks)
9. [Spectral Learning for Infinite-Horizon Average-Reward POMDPs](#Spectral-Learning-for-Infinite-Horizon-Average-Reward-POMDPs)
10. [Information Retrieval Induced Safety Degradation in AI Agents](#Information-Retrieval-Induced-Safety-Degradation-in-AI-Agents)
11. [Denoising Trajectory Biases for Zero-Shot AI-Generated Image Detection](#Denoising-Trajectory-Biases-for-Zero-Shot-AI-Generated-Image-Detection)
12. [Large language models can learn and generalize steganographic chain-of-thought under process supervision](#Large-language-models-can-learn-and-generalize-steganographic-chain-of-thought-under-process-supervision)
13. [Cognitive Predictive Processing: A Human-inspired Framework for Adaptive Exploration in Open-World Reinforcement Learning](#Cognitive-Predictive-Processing-A-Human-inspired-Framework-for-Adaptive-Exploration-in-Open-World-Reinforcement-Learning)
14. [See&Trek: Training-Free Spatial Prompting for Multimodal Large Language Model](#SeeTrek-Training-Free-Spatial-Prompting-for-Multimodal-Large-Language-Model)
15. [CovMatch: Cross-Covariance Guided Multimodal Dataset Distillation with Trainable Text Encoder](#CovMatch-Cross-Covariance-Guided-Multimodal-Dataset-Distillation-with-Trainable-Text-Encoder)
16. [Conformal Inference under High-Dimensional Covariate Shifts via Likelihood-Ratio Regularization](#Conformal-Inference-under-High-Dimensional-Covariate-Shifts-via-Likelihood-Ratio-Regularization)
17. [Improving Formal Reasoning of Transformer with State Stack](#Improving-Formal-Reasoning-of-Transformer-with-State-Stack)
18. [FP64 is All You Need: Rethinking Failure Modes in Physics-Informed Neural Networks](#FP64-is-All-You-Need-Rethinking-Failure-Modes-in-Physics-Informed-Neural-Networks)
19. [$\textit{HiMaCon:}$ Discovering Hierarchical Manipulation Concepts from Unlabeled Multi-Modal Data](#textitHiMaCon-Discovering-Hierarchical-Manipulation-Concepts-from-Unlabeled-Multi-Modal-Data)
20. [Bivariate Matrix-valued Linear Regression (BMLR): Finite-sample performance under Identifiability and Sparsity Assumptions](#Bivariate-Matrix-valued-Linear-Regression-BMLR-Finite-sample-performance-under-Identifiability-and-Sparsity-Assumptions)
21. [DAPO: An Open-Source LLM Reinforcement Learning System at Scale](#DAPO-An-Open-Source-LLM-Reinforcement-Learning-System-at-Scale)
22. [Conditional Panoramic Image Generation via Masked Autoregressive Modeling](#Conditional-Panoramic-Image-Generation-via-Masked-Autoregressive-Modeling)
23. [See through the Dark: Learning Illumination-affined Representations for Nighttime Occupancy Prediction](#See-through-the-Dark-Learning-Illumination-affined-Representations-for-Nighttime-Occupancy-Prediction)
24. [DeepVideo-R1: Video Reinforcement Fine-Tuning via Difficulty-aware Regressive GRPO](#DeepVideo-R1-Video-Reinforcement-Fine-Tuning-via-Difficulty-aware-Regressive-GRPO)
25. [Additive Models Explained: A Computational Complexity Approach](#Additive-Models-Explained-A-Computational-Complexity-Approach)
26. [GTR-Loc: Geospatial Text Regularization Assisted Outdoor LiDAR Localization](#GTR-Loc-Geospatial-Text-Regularization-Assisted-Outdoor-LiDAR-Localization)
27. [Understanding Generalization in Physics Informed Models through Affine Variety Dimensions](#Understanding-Generalization-in-Physics-Informed-Models-through-Affine-Variety-Dimensions)
28. [Bootstrapping Hierarchical Autoregressive Formal Reasoner with Chain-of-Proxy-Autoformalization](#Bootstrapping-Hierarchical-Autoregressive-Formal-Reasoner-with-Chain-of-Proxy-Autoformalization)
29. [Path-specific effects for pulse-oximetry guided decisions in critical care](#Path-specific-effects-for-pulse-oximetry-guided-decisions-in-critical-care)
30. [Eyes Wide Open: Ego Proactive Video-LLM for Streaming Video](#Eyes-Wide-Open-Ego-Proactive-Video-LLM-for-Streaming-Video)
31. [Zero-Shot Detection of LLM-Generated Text via Implicit Reward Model](#Zero-Shot-Detection-of-LLM-Generated-Text-via-Implicit-Reward-Model)
32. [Understanding outer learning rates in Local SGD](#Understanding-outer-learning-rates-in-Local-SGD)
33. [Rendering-Aware Reinforcement Learning for Vector Graphics Generation](#Rendering-Aware-Reinforcement-Learning-for-Vector-Graphics-Generation)
34. [Transformer Key-Value Memories Are Nearly as Interpretable as Sparse Autoencoders](#Transformer-Key-Value-Memories-Are-Nearly-as-Interpretable-as-Sparse-Autoencoders)
35. [DOTA: Distributional Test-time Adaptation of Vision-Language Models](#DOTA-Distributional-Test-time-Adaptation-of-Vision-Language-Models)
36. [Beyond Single-Task: Robust Multi-Task Length Generalization for LLMs](#Beyond-Single-Task-Robust-Multi-Task-Length-Generalization-for-LLMs)
37. [Beyond Least Squares: Uniform Approximation and the Hidden Cost of Misspecification](#Beyond-Least-Squares-Uniform-Approximation-and-the-Hidden-Cost-of-Misspecification)
38. [Data Efficient Adaptation in Large Language Models via Continuous Low-Rank Fine-Tuning](#Data-Efficient-Adaptation-in-Large-Language-Models-via-Continuous-Low-Rank-Fine-Tuning)
39. [Unsupervised Trajectory Optimization for 3D Registration in Serial Section Electron Microscopy using Neural ODEs](#Unsupervised-Trajectory-Optimization-for-3D-Registration-in-Serial-Section-Electron-Microscopy-using-Neural-ODEs)
40. [Reasoning as an Adaptive Defense for Safety](#Reasoning-as-an-Adaptive-Defense-for-Safety)
41. [CoUn: Empowering Machine Unlearning via Contrastive Learning](#CoUn-Empowering-Machine-Unlearning-via-Contrastive-Learning)

---


## Inference with correlated priors using sisters cells

### Images

![1aefad38edec0d37ef106c84f8228d9b8915b75e8559d82641d35541aae30369.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/images/1aefad38edec0d37ef106c84f8228d9b8915b75e8559d82641d35541aae30369.jpg)

![44597596c6a3b8ed3cdd67cce9645ea6eebef240b369ac429d0eeb616dc2abcd.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/images/44597596c6a3b8ed3cdd67cce9645ea6eebef240b369ac429d0eeb616dc2abcd.jpg)

![4b11ecb799e9dd36bdbf29cccd4a6f1a1b0add0d6b4c05e2cdcfb17bdbade019.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/images/4b11ecb799e9dd36bdbf29cccd4a6f1a1b0add0d6b4c05e2cdcfb17bdbade019.jpg)

![6b128596dfe57036b47bf9ddeba9c4979a5e46db560984020ac786fffd5b8ab7.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/images/6b128596dfe57036b47bf9ddeba9c4979a5e46db560984020ac786fffd5b8ab7.jpg)

![8e4ae4bbfbb3e1aeb517ec29e92976f2004df852ff296be980cf8bf4cf3693aa.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/images/8e4ae4bbfbb3e1aeb517ec29e92976f2004df852ff296be980cf8bf4cf3693aa.jpg)

![cc3175797a61a3773da269d62371523f563801d5a122f851e2eac480a1e82663.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/images/cc3175797a61a3773da269d62371523f563801d5a122f851e2eac480a1e82663.jpg)

![d4755d781f18c791fbd4af987a2544dff589c81d896881302198892402ea2195.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/images/d4755d781f18c791fbd4af987a2544dff589c81d896881302198892402ea2195.jpg)

![fa05059022dd0c9a03e48546c1b2e8bb4067bcb681fc33a168ea6aecbbd1baa1.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/images/fa05059022dd0c9a03e48546c1b2e8bb4067bcb681fc33a168ea6aecbbd1baa1.jpg)

### Tables

![05c959837bf3c8dba7321be943b32aa3674be2fe50c7a3e58b45bfcefc34e76a.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/tables/05c959837bf3c8dba7321be943b32aa3674be2fe50c7a3e58b45bfcefc34e76a.jpg)

![0f01ed99417b541f035f3a5b1b3aadf82873f2c31737c6e2fa7df9048fab10a8.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/tables/0f01ed99417b541f035f3a5b1b3aadf82873f2c31737c6e2fa7df9048fab10a8.jpg)

![2dddbe17e68c5925bcd049f070cb83bb10fa47260a911885d033838de5dd8ba2.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/tables/2dddbe17e68c5925bcd049f070cb83bb10fa47260a911885d033838de5dd8ba2.jpg)

![6760b000005851079a1441e59df9e3f83f592646682e2f0a443c04b7a9012dc5.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/tables/6760b000005851079a1441e59df9e3f83f592646682e2f0a443c04b7a9012dc5.jpg)

![d52f40fa4eea06ac48badc3b00217f6ad1cab2bfbc337b4e443bc08e57668d82.jpg](../nips_results/5058_Improve%20Temporal%20Reasoning%20in%20Multimodal%20Large%20Language%20Models%20via%20Video%20Contrastive%20Decoding/tables/d52f40fa4eea06ac48badc3b00217f6ad1cab2bfbc337b4e443bc08e57668d82.jpg)

## Inference with correlated priors using sisters cells


### Images

![1e0b572e9af3beb0f0afa2cae2d8b0bb903b83eca6063d1ffcbd02161eb7be0b.jpg](../nips_results/5059_Inference%20with%20correlated%20priors%20using%20sisters%20cells/images/1e0b572e9af3beb0f0afa2cae2d8b0bb903b83eca6063d1ffcbd02161eb7be0b.jpg)

![3bbd9dc3270558e2505118664baa017e07666b90ae31ea48d12471ffce16ea38.jpg](../nips_results/5059_Inference%20with%20correlated%20priors%20using%20sisters%20cells/images/3bbd9dc3270558e2505118664baa017e07666b90ae31ea48d12471ffce16ea38.jpg)

![823d443946953cc8ccf9db951166ed43947b167b5716e37aeabadbc7c40fc364.jpg](../nips_results/5059_Inference%20with%20correlated%20priors%20using%20sisters%20cells/images/823d443946953cc8ccf9db951166ed43947b167b5716e37aeabadbc7c40fc364.jpg)

![9174decc2a770d9c3e35bf9b9fcd6c73e302ccb9233991efd519e8f9f04551b8.jpg](../nips_results/5059_Inference%20with%20correlated%20priors%20using%20sisters%20cells/images/9174decc2a770d9c3e35bf9b9fcd6c73e302ccb9233991efd519e8f9f04551b8.jpg)

### Tables

![4032339fd6bec75fc6d3020d125604882b1acf7b92073ae32b862097493bed86.jpg](../nips_results/5059_Inference%20with%20correlated%20priors%20using%20sisters%20cells/tables/4032339fd6bec75fc6d3020d125604882b1acf7b92073ae32b862097493bed86.jpg)

## A Finite Sample Analysis of Distributional TD Learning with Linear Function Approximation


### Images

![19d00b7df5172fb7d47c972d1aa5489d1f6b0ae3b1ef8de02924e33c3dfc038c.jpg](../nips_results/5060_A%20Finite%20Sample%20Analysis%20of%20Distributional%20TD%20Learning%20with%20Linear%20Function%20Approximation/images/19d00b7df5172fb7d47c972d1aa5489d1f6b0ae3b1ef8de02924e33c3dfc038c.jpg)

![1dfdd58549bfb17f3de84b450419e6855022985d47815c3f6e4957e98306653c.jpg](../nips_results/5060_A%20Finite%20Sample%20Analysis%20of%20Distributional%20TD%20Learning%20with%20Linear%20Function%20Approximation/images/1dfdd58549bfb17f3de84b450419e6855022985d47815c3f6e4957e98306653c.jpg)

![7fea16d3a5293cbc84ddda90a4d05b1392be15313364838325e4595ab589832e.jpg](../nips_results/5060_A%20Finite%20Sample%20Analysis%20of%20Distributional%20TD%20Learning%20with%20Linear%20Function%20Approximation/images/7fea16d3a5293cbc84ddda90a4d05b1392be15313364838325e4595ab589832e.jpg)

![942d201598ecef5bb35caeb910718b7a707af04a2cc149739ecc0f41c71a47c1.jpg](../nips_results/5060_A%20Finite%20Sample%20Analysis%20of%20Distributional%20TD%20Learning%20with%20Linear%20Function%20Approximation/images/942d201598ecef5bb35caeb910718b7a707af04a2cc149739ecc0f41c71a47c1.jpg)

![ee6e58c675d6d6713aaebd77632b7bdc2267e803d9b98de36f14bfabeae19117.jpg](../nips_results/5060_A%20Finite%20Sample%20Analysis%20of%20Distributional%20TD%20Learning%20with%20Linear%20Function%20Approximation/images/ee6e58c675d6d6713aaebd77632b7bdc2267e803d9b98de36f14bfabeae19117.jpg)

![f6d550a78c3a282f77b18811fcb703ddff90eaea526e96f0fc8921d84f033dbb.jpg](../nips_results/5060_A%20Finite%20Sample%20Analysis%20of%20Distributional%20TD%20Learning%20with%20Linear%20Function%20Approximation/images/f6d550a78c3a282f77b18811fcb703ddff90eaea526e96f0fc8921d84f033dbb.jpg)

### Tables

![1a32e6c69b25a2ef70ada9c1d5ba5d1b4f219df2ea08d4253d62bee8ec89658b.jpg](../nips_results/5060_A%20Finite%20Sample%20Analysis%20of%20Distributional%20TD%20Learning%20with%20Linear%20Function%20Approximation/tables/1a32e6c69b25a2ef70ada9c1d5ba5d1b4f219df2ea08d4253d62bee8ec89658b.jpg)

![9ad8476e29b8a333b2b372d881ddbdc9e8b4658cc248c0aada605fd89461ceee.jpg](../nips_results/5060_A%20Finite%20Sample%20Analysis%20of%20Distributional%20TD%20Learning%20with%20Linear%20Function%20Approximation/tables/9ad8476e29b8a333b2b372d881ddbdc9e8b4658cc248c0aada605fd89461ceee.jpg)

![d4073441adf2b5caa4b38c3fe124d7de9a6edb976690929d3929aa8549bed2da.jpg](../nips_results/5060_A%20Finite%20Sample%20Analysis%20of%20Distributional%20TD%20Learning%20with%20Linear%20Function%20Approximation/tables/d4073441adf2b5caa4b38c3fe124d7de9a6edb976690929d3929aa8549bed2da.jpg)

![f4267c21dc4e8dada2a49d1d4c34a6b6338011d7da1e5d9272c17c87c1446e16.jpg](../nips_results/5060_A%20Finite%20Sample%20Analysis%20of%20Distributional%20TD%20Learning%20with%20Linear%20Function%20Approximation/tables/f4267c21dc4e8dada2a49d1d4c34a6b6338011d7da1e5d9272c17c87c1446e16.jpg)

## RePO: Understanding Preference Learning Through ReLU-Based Optimization


### Images

![0da36f274f9e6acb9604d2c218867fb70687579a9902ec6f26bdcf6a866e3127.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/images/0da36f274f9e6acb9604d2c218867fb70687579a9902ec6f26bdcf6a866e3127.jpg)

![0dcc5dff3ea5214d2bda6c94d76fca5568c436d7fa6848d16bc2b00d9231469b.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/images/0dcc5dff3ea5214d2bda6c94d76fca5568c436d7fa6848d16bc2b00d9231469b.jpg)

![13025989154ccd50c22e4c82a4283fa2446ea9bb422e9fb9643a2b08270e01fe.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/images/13025989154ccd50c22e4c82a4283fa2446ea9bb422e9fb9643a2b08270e01fe.jpg)

![21108d041f846fe2b427d296d1700c9f89bfeb2ade5a0fa24aea28828f1835ab.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/images/21108d041f846fe2b427d296d1700c9f89bfeb2ade5a0fa24aea28828f1835ab.jpg)

![25ddcc83bc8323c506c53b940c87f4fc15582801405a30cd9832c5a1df4cf797.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/images/25ddcc83bc8323c506c53b940c87f4fc15582801405a30cd9832c5a1df4cf797.jpg)

![2a529a3a68095a00b80c533c76566e066f3f653dbd79f5a5bb8a2c58f4fa56af.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/images/2a529a3a68095a00b80c533c76566e066f3f653dbd79f5a5bb8a2c58f4fa56af.jpg)

![3b5b8deae297ce097336684dbdc7ffea786a055114a3e55d7a1aa1b3faf2086e.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/images/3b5b8deae297ce097336684dbdc7ffea786a055114a3e55d7a1aa1b3faf2086e.jpg)

![782db20a416d78ca04d712032299ccddc7fb7c96cec55e886c404129b96f7786.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/images/782db20a416d78ca04d712032299ccddc7fb7c96cec55e886c404129b96f7786.jpg)

![ac33813be96b4ae1148798adfbf4b4d1b0bb104661508536a76f1739427d36e8.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/images/ac33813be96b4ae1148798adfbf4b4d1b0bb104661508536a76f1739427d36e8.jpg)

### Tables

![1ac601bcaac5b7bd87282cc1b87792e9ea24808e27dcf00241639eb3046dd687.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/tables/1ac601bcaac5b7bd87282cc1b87792e9ea24808e27dcf00241639eb3046dd687.jpg)

![46fd0747b8b781275e2cda56759a53e75193d2cf837b0540398fbdcfadf5d80a.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/tables/46fd0747b8b781275e2cda56759a53e75193d2cf837b0540398fbdcfadf5d80a.jpg)

![48ebac58bd9da9ca1cb6391fbf6f938019f9af992d572f56ca5d6836d3c12eb3.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/tables/48ebac58bd9da9ca1cb6391fbf6f938019f9af992d572f56ca5d6836d3c12eb3.jpg)

![51a1f0e8b600b7155e5732f5f9807cd043949c5ad252e1109adaa3fa837a8604.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/tables/51a1f0e8b600b7155e5732f5f9807cd043949c5ad252e1109adaa3fa837a8604.jpg)

![5a6a7e2c7af7f10b05032613f2ad704a401c55e11c0f1af828683f81bd1331ec.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/tables/5a6a7e2c7af7f10b05032613f2ad704a401c55e11c0f1af828683f81bd1331ec.jpg)

![63aa77a305b370ee958535726ab2bcdb0962a31436bb687d3fb5209ff5ef9df7.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/tables/63aa77a305b370ee958535726ab2bcdb0962a31436bb687d3fb5209ff5ef9df7.jpg)

![b49a2f818d571263f72ea707a225eb03166568d4707824a425233c3c2356dc9d.jpg](../nips_results/5061_RePO_%20Understanding%20Preference%20Learning%20Through%20ReLU-Based%20Optimization/tables/b49a2f818d571263f72ea707a225eb03166568d4707824a425233c3c2356dc9d.jpg)

## Synergy over Discrepancy: A Partition-Based Approach to Multi-Domain LLM Fine-Tuning


### Images

![08c74f09fd63576489d2ae8afff17e4e5a1a92c977a8555428995601168526b2.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/images/08c74f09fd63576489d2ae8afff17e4e5a1a92c977a8555428995601168526b2.jpg)

![111dd921d5922aedf15892a4ed5f3006e6452421660b32d258992cbeae97bc7f.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/images/111dd921d5922aedf15892a4ed5f3006e6452421660b32d258992cbeae97bc7f.jpg)

![d3ffb9b7184b401d84c30ec65e3994f81556e906fc4e972a3432ee568c1662db.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/images/d3ffb9b7184b401d84c30ec65e3994f81556e906fc4e972a3432ee568c1662db.jpg)

### Tables

![075df92379f52b27e265187565c29a014d93511bfe34a2d6998d24528a96ad31.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/075df92379f52b27e265187565c29a014d93511bfe34a2d6998d24528a96ad31.jpg)

![15c26de2707886c06a0f41877574a2beeaa3afec73139a02a9e58bb0d899b19a.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/15c26de2707886c06a0f41877574a2beeaa3afec73139a02a9e58bb0d899b19a.jpg)

![15d4b2dbfe389cecbfe676fe923a0b13286a5fda681bb4504193f5e92e22503c.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/15d4b2dbfe389cecbfe676fe923a0b13286a5fda681bb4504193f5e92e22503c.jpg)

![34b6c9a0f9219f8583f04a9537054db62912daee5345dd376690167b45bd8c54.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/34b6c9a0f9219f8583f04a9537054db62912daee5345dd376690167b45bd8c54.jpg)

![441368852f7f652d0a3836ccf3e4f9cce54f5f95cbbedaf8b7d683d327bed453.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/441368852f7f652d0a3836ccf3e4f9cce54f5f95cbbedaf8b7d683d327bed453.jpg)

![4796b0073a7439d9fddd780551494f675a494d06993b51ad66d738eaf1b8a7ca.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/4796b0073a7439d9fddd780551494f675a494d06993b51ad66d738eaf1b8a7ca.jpg)

![59e2ddd1f94b4dcbb4049f811977f468c45e864a63fe77185f373ad1a4a1f136.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/59e2ddd1f94b4dcbb4049f811977f468c45e864a63fe77185f373ad1a4a1f136.jpg)

![82d6edb2057e050f1acd9878519f8617d7f8b610da81d2ba4940dc4bbd047f5f.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/82d6edb2057e050f1acd9878519f8617d7f8b610da81d2ba4940dc4bbd047f5f.jpg)

![84f522ceb40ab84d23f234d8e3e2faaa85b14d5f9c28e960a3d967b1e0889b7b.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/84f522ceb40ab84d23f234d8e3e2faaa85b14d5f9c28e960a3d967b1e0889b7b.jpg)

![853261d53473ff4e09e40649c4694882f7f7153a87c4393690f6c85704147902.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/853261d53473ff4e09e40649c4694882f7f7153a87c4393690f6c85704147902.jpg)

![8aadb6c574825eb2e6a9d6c9782a49c5789ee183ebc4cf298bc65b0558630f5a.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/8aadb6c574825eb2e6a9d6c9782a49c5789ee183ebc4cf298bc65b0558630f5a.jpg)

![8cee44486b6c34e118a099dee0fb136fe79371eab40286fd36bbf0ac9a74ba0b.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/8cee44486b6c34e118a099dee0fb136fe79371eab40286fd36bbf0ac9a74ba0b.jpg)

![8df070d943db0adbd04ec877243f1a85f2a0ca65c99266db89b31e97ca6e50be.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/8df070d943db0adbd04ec877243f1a85f2a0ca65c99266db89b31e97ca6e50be.jpg)

![a15d06cfc182ae09efb7bdd98ed4abe150922b4b80008e09251600c2bcb6f7a3.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/a15d06cfc182ae09efb7bdd98ed4abe150922b4b80008e09251600c2bcb6f7a3.jpg)

![a5a6374e4d307fb409e0f1dff14cec5c969b4f98e0fa54cd66d1609b5c47d516.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/a5a6374e4d307fb409e0f1dff14cec5c969b4f98e0fa54cd66d1609b5c47d516.jpg)

![a7e12a12f9a7404e304c5fb921009deeffdcdaad80fa9a1953c1e50873c9a03d.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/a7e12a12f9a7404e304c5fb921009deeffdcdaad80fa9a1953c1e50873c9a03d.jpg)

![ca9f8e44df2bdbbd1b9696a55534ab1c574edd59702237212da23cc325fc9c0d.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/ca9f8e44df2bdbbd1b9696a55534ab1c574edd59702237212da23cc325fc9c0d.jpg)

![ce9743383cfbf37b7cfebb4a26a4f431dfb631388e7100b3d2368a263bc39e6e.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/ce9743383cfbf37b7cfebb4a26a4f431dfb631388e7100b3d2368a263bc39e6e.jpg)

![d3fce31c1e7164b62cfebe359bf4d1475d230480c264325a51ae1f98394fc7a0.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/d3fce31c1e7164b62cfebe359bf4d1475d230480c264325a51ae1f98394fc7a0.jpg)

![d55da129de8362a5b84a05cea9fb14e1ae310c40f8cc5ae37a1bb2d89fcf0464.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/d55da129de8362a5b84a05cea9fb14e1ae310c40f8cc5ae37a1bb2d89fcf0464.jpg)

![ffece60f8f4823eb539b0fe0233d79e368de58d0363b42d5ec3f8506f7e5980f.jpg](../nips_results/5062_Synergy%20over%20Discrepancy_%20A%20Partition-Based%20Approach%20to%20Multi-Domain%20LLM%20Fine-Tuning/tables/ffece60f8f4823eb539b0fe0233d79e368de58d0363b42d5ec3f8506f7e5980f.jpg)

## R-KV: Redundancy-aware KV Cache Compression for Reasoning Models


### Images

![66f030bc0bd8738bcfec4ebd720ae2fc0e2b6d793a5b2e0226afee7cbccccd01.jpg](../nips_results/5063_R-KV_%20Redundancy-aware%20KV%20Cache%20Compression%20for%20Reasoning%20Models/images/66f030bc0bd8738bcfec4ebd720ae2fc0e2b6d793a5b2e0226afee7cbccccd01.jpg)

![6f24c916c02583c0977c30f5d55a5abc98aa9fbd859de65969769692e33386cc.jpg](../nips_results/5063_R-KV_%20Redundancy-aware%20KV%20Cache%20Compression%20for%20Reasoning%20Models/images/6f24c916c02583c0977c30f5d55a5abc98aa9fbd859de65969769692e33386cc.jpg)

![86866e848f164719f489fbb393286cc98a3cf9a861105e44cf28662382884bf8.jpg](../nips_results/5063_R-KV_%20Redundancy-aware%20KV%20Cache%20Compression%20for%20Reasoning%20Models/images/86866e848f164719f489fbb393286cc98a3cf9a861105e44cf28662382884bf8.jpg)

![8839657a200cee956112e8e132e84cf80c80c97c90c9ee072a867d104dc5cd52.jpg](../nips_results/5063_R-KV_%20Redundancy-aware%20KV%20Cache%20Compression%20for%20Reasoning%20Models/images/8839657a200cee956112e8e132e84cf80c80c97c90c9ee072a867d104dc5cd52.jpg)

![de3c430f53a92993717cca983a2314c006549a524114e8e304f5ccac175cadd3.jpg](../nips_results/5063_R-KV_%20Redundancy-aware%20KV%20Cache%20Compression%20for%20Reasoning%20Models/images/de3c430f53a92993717cca983a2314c006549a524114e8e304f5ccac175cadd3.jpg)

![f534679339c26bf6ae4bc97e6c2eb1c26c6758bd2dd9f4cc5718c37d82d2d449.jpg](../nips_results/5063_R-KV_%20Redundancy-aware%20KV%20Cache%20Compression%20for%20Reasoning%20Models/images/f534679339c26bf6ae4bc97e6c2eb1c26c6758bd2dd9f4cc5718c37d82d2d449.jpg)

### Tables

![300ecefc083c1cd9091130bd3a99bdc03f6200385cdcc865dfc19126ac3a2f73.jpg](../nips_results/5063_R-KV_%20Redundancy-aware%20KV%20Cache%20Compression%20for%20Reasoning%20Models/tables/300ecefc083c1cd9091130bd3a99bdc03f6200385cdcc865dfc19126ac3a2f73.jpg)

![7521d391b2d7e5d80d960f3ce82c9e0be50752337c481df494352816c6939acc.jpg](../nips_results/5063_R-KV_%20Redundancy-aware%20KV%20Cache%20Compression%20for%20Reasoning%20Models/tables/7521d391b2d7e5d80d960f3ce82c9e0be50752337c481df494352816c6939acc.jpg)

![b7996f320beb00fc5fe3102c0041ab7b437760e7d1b6c6e18767683bea69b2ec.jpg](../nips_results/5063_R-KV_%20Redundancy-aware%20KV%20Cache%20Compression%20for%20Reasoning%20Models/tables/b7996f320beb00fc5fe3102c0041ab7b437760e7d1b6c6e18767683bea69b2ec.jpg)

## FairDICE: Fairness-Driven Offline Multi-Objective Reinforcement Learning


### Images

![0e420e2496cf8683b48979e20740708440a901fda7502560739bac94f8d75586.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/images/0e420e2496cf8683b48979e20740708440a901fda7502560739bac94f8d75586.jpg)

![44c04760b0aa556dd2c5fa5439fcde9f4b5033adec6ca9c59a5580ede9b666cf.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/images/44c04760b0aa556dd2c5fa5439fcde9f4b5033adec6ca9c59a5580ede9b666cf.jpg)

![5098210731c027fe682d9fa48c0fae3b9b164951cc99b2f2e2022dc357c40126.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/images/5098210731c027fe682d9fa48c0fae3b9b164951cc99b2f2e2022dc357c40126.jpg)

![523a05e5ad1df5ac013ce995471f0fff8147cae1f705a1c0bafcc340f408db88.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/images/523a05e5ad1df5ac013ce995471f0fff8147cae1f705a1c0bafcc340f408db88.jpg)

![6541b512f3cd14a5f6a43af2a30e661b1bba4db017a30f526783d0ea684f90de.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/images/6541b512f3cd14a5f6a43af2a30e661b1bba4db017a30f526783d0ea684f90de.jpg)

![ab2df09f7cc3362a3fee7c37eb14ec4c12827a3fde4d4e267a6ba1b79effdd02.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/images/ab2df09f7cc3362a3fee7c37eb14ec4c12827a3fde4d4e267a6ba1b79effdd02.jpg)

![b3aa0b276869b2f57a35dcfe63fec5afb2f287a7a5443bd9df5265d1c96c2ece.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/images/b3aa0b276869b2f57a35dcfe63fec5afb2f287a7a5443bd9df5265d1c96c2ece.jpg)

![c4b454494eb8b3eb7355d47d8c98f89b9eed65e5fa83b4e3a47e43126014a3c5.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/images/c4b454494eb8b3eb7355d47d8c98f89b9eed65e5fa83b4e3a47e43126014a3c5.jpg)

### Tables

![30a15159dcb11000fddb5fb3b81c4dce49ca2ed6700ac599a6c8f3106b71df12.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/tables/30a15159dcb11000fddb5fb3b81c4dce49ca2ed6700ac599a6c8f3106b71df12.jpg)

![4bf82774a4809b1550e9476b8e38cdff1e09c2364462b62739d5a440208b7271.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/tables/4bf82774a4809b1550e9476b8e38cdff1e09c2364462b62739d5a440208b7271.jpg)

![5711b4cc6b197d2084bed2c5ea103a84c5e9f39c4dc56afef5be3d20f90a88a1.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/tables/5711b4cc6b197d2084bed2c5ea103a84c5e9f39c4dc56afef5be3d20f90a88a1.jpg)

![df357a1711527675c6116576819745243db8fc0eef4337e212909b3839cd18c0.jpg](../nips_results/5064_FairDICE_%20Fairness-Driven%20Offline%20Multi-Objective%20Reinforcement%20Learning/tables/df357a1711527675c6116576819745243db8fc0eef4337e212909b3839cd18c0.jpg)

## Online Inverse Linear Optimization: Efficient Logarithmic-Regret Algorithm, Robustness to Suboptimality, and Lower Bound


### Images

![1e201be52cd50d218bf46edc1096583f0af7c7d748a0a0eaa4cb8bd67ccbfc60.jpg](../nips_results/5065_Online%20Inverse%20Linear%20Optimization_%20Efficient%20Logarithmic-Regret%20Algorithm%2C%20Robustness%20to%20Suboptimal/images/1e201be52cd50d218bf46edc1096583f0af7c7d748a0a0eaa4cb8bd67ccbfc60.jpg)

![2e2f5fba3b9812e15b3e8ed4c7a4fee10793b72bfda41be2eefd357bd4c3eacd.jpg](../nips_results/5065_Online%20Inverse%20Linear%20Optimization_%20Efficient%20Logarithmic-Regret%20Algorithm%2C%20Robustness%20to%20Suboptimal/images/2e2f5fba3b9812e15b3e8ed4c7a4fee10793b72bfda41be2eefd357bd4c3eacd.jpg)

### Tables

![02f1817d635903b9918e28da7ebd54934f6202a0203732005543faf008dc9f4a.jpg](../nips_results/5065_Online%20Inverse%20Linear%20Optimization_%20Efficient%20Logarithmic-Regret%20Algorithm%2C%20Robustness%20to%20Suboptimal/tables/02f1817d635903b9918e28da7ebd54934f6202a0203732005543faf008dc9f4a.jpg)

![4ae6f0c5589bcbfc4838942574c0a8017cdc28d47b349ee0297f3f111c2fba86.jpg](../nips_results/5065_Online%20Inverse%20Linear%20Optimization_%20Efficient%20Logarithmic-Regret%20Algorithm%2C%20Robustness%20to%20Suboptimal/tables/4ae6f0c5589bcbfc4838942574c0a8017cdc28d47b349ee0297f3f111c2fba86.jpg)

## Bridging Scales: Spectral Theory Reveals How Local Connectivity Rules Sculpt Global Neural Dynamics in Spatially Extended Networks


### Images

![0d70d7039cf8c953cd9813a5f4a779fe4ac4a2925827acef9de7cfcb406def93.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/0d70d7039cf8c953cd9813a5f4a779fe4ac4a2925827acef9de7cfcb406def93.jpg)

![1d52fd3e987b9c60171f783cfa87475e5fc35aa8e958ecbeba63b5392d094b97.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/1d52fd3e987b9c60171f783cfa87475e5fc35aa8e958ecbeba63b5392d094b97.jpg)

![2004be0367a08de53ff7af85524b75ddccf42a7d9b78e100a87665ea12a802a8.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/2004be0367a08de53ff7af85524b75ddccf42a7d9b78e100a87665ea12a802a8.jpg)

![20645c625ab014e049e928192292b6287a74687634b1e0019ae8f1d02999f240.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/20645c625ab014e049e928192292b6287a74687634b1e0019ae8f1d02999f240.jpg)

![4639b717f6aeaa88d2dfb57badf9dc150707cf3d1793715a2e9a91aefbd5ce7e.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/4639b717f6aeaa88d2dfb57badf9dc150707cf3d1793715a2e9a91aefbd5ce7e.jpg)

![5bd1609f6d34eb23307f926fc88621a1d7d5ac525693e2d3fa040222f92d3864.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/5bd1609f6d34eb23307f926fc88621a1d7d5ac525693e2d3fa040222f92d3864.jpg)

![8afb25a817d9c0f1dfc9d20781db6e04b76568af961189ce7c6a020a099f762b.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/8afb25a817d9c0f1dfc9d20781db6e04b76568af961189ce7c6a020a099f762b.jpg)

![97d4feca0f930ffb60e128bf157ecc07eecae097aaec45f9990478237fe3bf88.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/97d4feca0f930ffb60e128bf157ecc07eecae097aaec45f9990478237fe3bf88.jpg)

![a2a45cfafbde1101c76a60222fb8a5b733825db99575c1b6f4fbb05b3d51466a.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/a2a45cfafbde1101c76a60222fb8a5b733825db99575c1b6f4fbb05b3d51466a.jpg)

![bcaa968f1136cb05a8d067e9eab35816d8b650d2358408208c78400ba3425635.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/bcaa968f1136cb05a8d067e9eab35816d8b650d2358408208c78400ba3425635.jpg)

![edb9e8a0b7fe730293635b7f5e1240b3094300835f5a3e7f03f7f4b378a6872e.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/edb9e8a0b7fe730293635b7f5e1240b3094300835f5a3e7f03f7f4b378a6872e.jpg)

![f91fa021cb4ff239fac89cb1793d91d67058ee4970e934ad5020e41ffff5532b.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/images/f91fa021cb4ff239fac89cb1793d91d67058ee4970e934ad5020e41ffff5532b.jpg)

### Tables

![9910d33236fee036e00ba1d5218f55dc0db3f16ecd2d130c69d0ba4b6202aca0.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/tables/9910d33236fee036e00ba1d5218f55dc0db3f16ecd2d130c69d0ba4b6202aca0.jpg)

![b490efa128f0e6b0888998337b15d8f3c757ce925dc41721decea9164743599d.jpg](../nips_results/5066_Bridging%20Scales_%20Spectral%20Theory%20Reveals%20How%20Local%20Connectivity%20Rules%20Sculpt%20Global%20Neural%20Dynamics%20/tables/b490efa128f0e6b0888998337b15d8f3c757ce925dc41721decea9164743599d.jpg)

## Spectral Learning for Infinite-Horizon Average-Reward POMDPs


### Images

![53aa32d0dd5974e21612ab00491f1f3ac8ca8f24cef3b29f893587057424f72d.jpg](../nips_results/5067_Spectral%20Learning%20for%20Infinite-Horizon%20Average-Reward%20POMDPs/images/53aa32d0dd5974e21612ab00491f1f3ac8ca8f24cef3b29f893587057424f72d.jpg)

![75109d4386c6e4ed420d330c519c6b516a7e997497cf781f049ec36db6d31fc2.jpg](../nips_results/5067_Spectral%20Learning%20for%20Infinite-Horizon%20Average-Reward%20POMDPs/images/75109d4386c6e4ed420d330c519c6b516a7e997497cf781f049ec36db6d31fc2.jpg)

![85008284002673c26695f6c7c22579abdd84be5348048f22490482bbe0f15557.jpg](../nips_results/5067_Spectral%20Learning%20for%20Infinite-Horizon%20Average-Reward%20POMDPs/images/85008284002673c26695f6c7c22579abdd84be5348048f22490482bbe0f15557.jpg)

![d896e663baa7e1acb457ecf5620676819a7f0da8e43a08de1556985b52b64bb2.jpg](../nips_results/5067_Spectral%20Learning%20for%20Infinite-Horizon%20Average-Reward%20POMDPs/images/d896e663baa7e1acb457ecf5620676819a7f0da8e43a08de1556985b52b64bb2.jpg)

### Tables

![b317694dbcc510f5f1e182b543e34e39ff86dc43f17262b41a90ae6943716f50.jpg](../nips_results/5067_Spectral%20Learning%20for%20Infinite-Horizon%20Average-Reward%20POMDPs/tables/b317694dbcc510f5f1e182b543e34e39ff86dc43f17262b41a90ae6943716f50.jpg)

## Information Retrieval Induced Safety Degradation in AI Agents


### Images

![01aaca868ad11d5b204a2e4ffa95fc27350b4ed133c8246b9220daf73c6a7b18.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/images/01aaca868ad11d5b204a2e4ffa95fc27350b4ed133c8246b9220daf73c6a7b18.jpg)

![0880f8846d93d18083db72dda542f692a74e23fa65df7e77631553f81214cb56.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/images/0880f8846d93d18083db72dda542f692a74e23fa65df7e77631553f81214cb56.jpg)

![30e7d3c87ccc659fe069d53731b2a494fc4b17f8f4e90f61ee86cfa7ffbe0ea6.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/images/30e7d3c87ccc659fe069d53731b2a494fc4b17f8f4e90f61ee86cfa7ffbe0ea6.jpg)

![334f16c42f430b2fb411998f77667b42a07e8e7511a1997cb672545d0f6db755.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/images/334f16c42f430b2fb411998f77667b42a07e8e7511a1997cb672545d0f6db755.jpg)

![4690e519149b046aff35300c3efc4770452e921b4fad0080638c83051d0a60a7.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/images/4690e519149b046aff35300c3efc4770452e921b4fad0080638c83051d0a60a7.jpg)

![578fef98e624ec8a704ac249bd08cece8c1396efe778dabd5a13cf90d22d52b4.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/images/578fef98e624ec8a704ac249bd08cece8c1396efe778dabd5a13cf90d22d52b4.jpg)

![6fce0095f7214d77b2c17ccf81c7d135b73320ba84b9ebda179840cd6891f961.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/images/6fce0095f7214d77b2c17ccf81c7d135b73320ba84b9ebda179840cd6891f961.jpg)

![a8fe0589f815bc944fa614fad25204fd78e68613437b6c87ab9cf6dceb4069d6.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/images/a8fe0589f815bc944fa614fad25204fd78e68613437b6c87ab9cf6dceb4069d6.jpg)

### Tables

![0137a949265051276706179be36749cde813223ce4f0fd00d1deae675ae58b48.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/0137a949265051276706179be36749cde813223ce4f0fd00d1deae675ae58b48.jpg)

![113f28c8c07900667cd62b5233e2b75e0e72d832a1391705a6c5215e020b02c6.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/113f28c8c07900667cd62b5233e2b75e0e72d832a1391705a6c5215e020b02c6.jpg)

![11f6890f97229170876230bacedcafbe2390f2426b2dc26a923c4a2211e9bd1a.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/11f6890f97229170876230bacedcafbe2390f2426b2dc26a923c4a2211e9bd1a.jpg)

![279c2c3576dcfcf0bb9401fe51e130636554ce88d39c5c622ad6f9b55afc0464.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/279c2c3576dcfcf0bb9401fe51e130636554ce88d39c5c622ad6f9b55afc0464.jpg)

![2856cb11187c47f16d26fc02afa2546563fa31e11235bf2600325aad564b5017.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/2856cb11187c47f16d26fc02afa2546563fa31e11235bf2600325aad564b5017.jpg)

![34c0b7ba3b3fe2f386f0aabb0ba10d0d4939d8a2008ff888461d17c55733d4a9.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/34c0b7ba3b3fe2f386f0aabb0ba10d0d4939d8a2008ff888461d17c55733d4a9.jpg)

![5836ebf7e2ae4265ddb2511b1e08bdac38555607d1c1e2e8c10f1aa57ed39f12.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/5836ebf7e2ae4265ddb2511b1e08bdac38555607d1c1e2e8c10f1aa57ed39f12.jpg)

![5a2164189f1127fefcd2e647d59e6c4b4f74ee924ec3241dbac76744293d32d9.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/5a2164189f1127fefcd2e647d59e6c4b4f74ee924ec3241dbac76744293d32d9.jpg)

![65848e46849fb33b13d2ac17e99d753134b8539d2c5bc1d0833b407819a8d09f.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/65848e46849fb33b13d2ac17e99d753134b8539d2c5bc1d0833b407819a8d09f.jpg)

![66d6a0d1dd1e6e61b7f52388909a122c1ca8ed4cc921ced7da9585e4e275ebd5.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/66d6a0d1dd1e6e61b7f52388909a122c1ca8ed4cc921ced7da9585e4e275ebd5.jpg)

![6a28c4968079fcbda5c9714be04fe7b0c9489fc2b795f41c48ff01d938a9763c.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/6a28c4968079fcbda5c9714be04fe7b0c9489fc2b795f41c48ff01d938a9763c.jpg)

![94fbd3e947fecf9ef0cae90e33ea042e9f57e63165974e792c67d034fb61dfbb.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/94fbd3e947fecf9ef0cae90e33ea042e9f57e63165974e792c67d034fb61dfbb.jpg)

![ac53cd18d6b2eae8ab9d3e0da6ae8155ca4ea356488bd42400676a578ef9b305.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/ac53cd18d6b2eae8ab9d3e0da6ae8155ca4ea356488bd42400676a578ef9b305.jpg)

![df5b5054f24432667168c37264246be1b26eb5ed174e072f3efe46f7cc6f597f.jpg](../nips_results/5068_Information%20Retrieval%20Induced%20Safety%20Degradation%20in%20AI%20Agents/tables/df5b5054f24432667168c37264246be1b26eb5ed174e072f3efe46f7cc6f597f.jpg)

## Denoising Trajectory Biases for Zero-Shot AI-Generated Image Detection


### Images

![10ce555da0e4c92108e45193b86bc76ffa0e5817c60ac59b29f90a34bd6e3852.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/images/10ce555da0e4c92108e45193b86bc76ffa0e5817c60ac59b29f90a34bd6e3852.jpg)

![1226457fddc8b2d2747a934ffeab624cc57056cbd4246ad0adda84f71b0719ca.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/images/1226457fddc8b2d2747a934ffeab624cc57056cbd4246ad0adda84f71b0719ca.jpg)

![53555de94558ef159431461547f9a1a0d9ad6c0ed87019992177185cabbbe1c2.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/images/53555de94558ef159431461547f9a1a0d9ad6c0ed87019992177185cabbbe1c2.jpg)

![5c1e28a9963352e7cd953ad10cc86c30bd028949f3062bce02ad8d03a10bca59.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/images/5c1e28a9963352e7cd953ad10cc86c30bd028949f3062bce02ad8d03a10bca59.jpg)

![976dee85ec087e21c28ab1a8762b3dbc2cdc3347e647297af3e0f5bfa959dc6a.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/images/976dee85ec087e21c28ab1a8762b3dbc2cdc3347e647297af3e0f5bfa959dc6a.jpg)

![a5c79ae4876aaec2e73947eb716e6e793b964bf64b9f07b5c03392c1feae42c7.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/images/a5c79ae4876aaec2e73947eb716e6e793b964bf64b9f07b5c03392c1feae42c7.jpg)

![c1ffd42e6352380add9331fbad72c7e1262f00ac739a11d8cd366ab05feb6fb0.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/images/c1ffd42e6352380add9331fbad72c7e1262f00ac739a11d8cd366ab05feb6fb0.jpg)

![c500a161d04cf5e5e9a5beca1b4f1a05725b9973c82ae5754b822e497f79ba0a.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/images/c500a161d04cf5e5e9a5beca1b4f1a05725b9973c82ae5754b822e497f79ba0a.jpg)

![c7454b431fb654409c9899534aa4b365367a2e45e6a2a7e2a9b9ce468534e7a7.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/images/c7454b431fb654409c9899534aa4b365367a2e45e6a2a7e2a9b9ce468534e7a7.jpg)

![de2fdd8ff1be80e71769f6cec3effb3498a54980b6da28b6b8927c97cc336bef.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/images/de2fdd8ff1be80e71769f6cec3effb3498a54980b6da28b6b8927c97cc336bef.jpg)

### Tables

![1635451fcb47373f2f302600b22390a8faaf83ebedb8ae351565001dfcf93080.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/tables/1635451fcb47373f2f302600b22390a8faaf83ebedb8ae351565001dfcf93080.jpg)

![20c9a2f930374e2c48b19e1d6c534611ad26b8943925244026d2126d493d5dd9.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/tables/20c9a2f930374e2c48b19e1d6c534611ad26b8943925244026d2126d493d5dd9.jpg)

![450c5d11b89d6eebe4667f10ae50ce2240f754dff810d7b0646c67c04d2d4e0b.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/tables/450c5d11b89d6eebe4667f10ae50ce2240f754dff810d7b0646c67c04d2d4e0b.jpg)

![6997d14b261d72bf43e113055362c1b4b1c28737cf9cb238ce0b3f15cac253bc.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/tables/6997d14b261d72bf43e113055362c1b4b1c28737cf9cb238ce0b3f15cac253bc.jpg)

![d01df7cfa38bab8b322f27958555c31dd599c88f1ec3818c699e911d8b9b9215.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/tables/d01df7cfa38bab8b322f27958555c31dd599c88f1ec3818c699e911d8b9b9215.jpg)

![e2a1eb217be63134ed597d8eff88b56ef0ed55a665575ef311a0c9dadce415ed.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/tables/e2a1eb217be63134ed597d8eff88b56ef0ed55a665575ef311a0c9dadce415ed.jpg)

![ff31c428dc2bd53c0692f158238fd94d46c222fa2ba5a68a861fd902356acf79.jpg](../nips_results/5069_Denoising%20Trajectory%20Biases%20for%20Zero-Shot%20AI-Generated%20Image%20Detection/tables/ff31c428dc2bd53c0692f158238fd94d46c222fa2ba5a68a861fd902356acf79.jpg)

## Large language models can learn and generalize steganographic chain-of-thought under process supervision


### Images

![0be2828674eea9ea22a1ebb79c217de4434df8c2a819501a6f821f22958f03cc.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/images/0be2828674eea9ea22a1ebb79c217de4434df8c2a819501a6f821f22958f03cc.jpg)

![22753d3bd923ab805cb198f4695bc71e5b77fc6e10a247a8410690360a092586.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/images/22753d3bd923ab805cb198f4695bc71e5b77fc6e10a247a8410690360a092586.jpg)

![26b50cf56fa55cb1560b555f42922dc52cc635af178535cc8608605e504b1ed3.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/images/26b50cf56fa55cb1560b555f42922dc52cc635af178535cc8608605e504b1ed3.jpg)

![39116f63eff2b9b8803418277ed38abd307d6038341f93c9a4bc3465ed423d50.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/images/39116f63eff2b9b8803418277ed38abd307d6038341f93c9a4bc3465ed423d50.jpg)

![f99e6558cbbc1726c8d0b05e2725c226b2c797ab651485e923c0367cfc40d0b6.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/images/f99e6558cbbc1726c8d0b05e2725c226b2c797ab651485e923c0367cfc40d0b6.jpg)

### Tables

![02b1dadbc87fd2e28d63d9024d6ebfd6d8ac8bf62745be2a2ba6c3afc752ee89.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/tables/02b1dadbc87fd2e28d63d9024d6ebfd6d8ac8bf62745be2a2ba6c3afc752ee89.jpg)

![42e59a64a40c91f53e016bdf0a5c2d8a37180478cdbb5a26a74d0750f5ca9a81.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/tables/42e59a64a40c91f53e016bdf0a5c2d8a37180478cdbb5a26a74d0750f5ca9a81.jpg)

![4b6aa8518cb9c5d0fde6391ebbd9ae4c0759039f5b16546e8c9452af21da3537.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/tables/4b6aa8518cb9c5d0fde6391ebbd9ae4c0759039f5b16546e8c9452af21da3537.jpg)

![5697e8b465a545786f3b1b48e6494c7d764405d66a1cf5d0862c92556f92d1fd.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/tables/5697e8b465a545786f3b1b48e6494c7d764405d66a1cf5d0862c92556f92d1fd.jpg)

![65ab85e9b09db11eec82d238524ff499ed9668fe92fc241ba22402578913c3c6.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/tables/65ab85e9b09db11eec82d238524ff499ed9668fe92fc241ba22402578913c3c6.jpg)

![949e64fa3fb224e807625aa5541b540bd40c2cb4fd740ac350827ff46806aa86.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/tables/949e64fa3fb224e807625aa5541b540bd40c2cb4fd740ac350827ff46806aa86.jpg)

![b91b7741a257aa26d98551b6027a7ff87ea92ed472c9f8560dcae64f711340e0.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/tables/b91b7741a257aa26d98551b6027a7ff87ea92ed472c9f8560dcae64f711340e0.jpg)

![de037a70e0a58f9a2dae068ed2ed89235d95aa9eb73e4b57ffc4fc62b444a354.jpg](../nips_results/5070_Large%20language%20models%20can%20learn%20and%20generalize%20steganographic%20chain-of-thought%20under%20process%20supervi/tables/de037a70e0a58f9a2dae068ed2ed89235d95aa9eb73e4b57ffc4fc62b444a354.jpg)

## Cognitive Predictive Processing: A Human-inspired Framework for Adaptive Exploration in Open-World Reinforcement Learning


### Images

![1b622dbc5685007066b49f2c73c8f3cc82e4348fe3185a52e90b042acb8e6d9e.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/images/1b622dbc5685007066b49f2c73c8f3cc82e4348fe3185a52e90b042acb8e6d9e.jpg)

![2085ddec906b489f2f8274401c8b1ecbb6eaa85445a83866d1855d879ae33ccb.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/images/2085ddec906b489f2f8274401c8b1ecbb6eaa85445a83866d1855d879ae33ccb.jpg)

![7a378df1ce6b62e7092f87d7a16a7bcc92df531ac823ce11a9dd38288fc04fd2.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/images/7a378df1ce6b62e7092f87d7a16a7bcc92df531ac823ce11a9dd38288fc04fd2.jpg)

![7d9ad4f163bc82fa97cac8e3d4bb543ad4aafb0082aeca2817bc2d8ee02f16fa.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/images/7d9ad4f163bc82fa97cac8e3d4bb543ad4aafb0082aeca2817bc2d8ee02f16fa.jpg)

![9e4b5a03ff006419cb65555ea22b4b51ae3003206656abba2d8851e3b796edd4.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/images/9e4b5a03ff006419cb65555ea22b4b51ae3003206656abba2d8851e3b796edd4.jpg)

![ecb26bbd5b72c0cce7d7f70a50b6b90dd8f382c82fe0b8f69c7bbbc9b3693150.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/images/ecb26bbd5b72c0cce7d7f70a50b6b90dd8f382c82fe0b8f69c7bbbc9b3693150.jpg)

![f429f37a2bcbf83725632c6126dfbf4dfda79f4161378b74ec1cb8b5c8af0b58.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/images/f429f37a2bcbf83725632c6126dfbf4dfda79f4161378b74ec1cb8b5c8af0b58.jpg)

### Tables

![002e0f163236bd05041bd47ad1f425f3b557fee15b92eb64a18fad758fb3b496.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/tables/002e0f163236bd05041bd47ad1f425f3b557fee15b92eb64a18fad758fb3b496.jpg)

![19cac4d44c5355e33bd966c23baf04b6b5768df519914484565dcd75095ef223.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/tables/19cac4d44c5355e33bd966c23baf04b6b5768df519914484565dcd75095ef223.jpg)

![1dd4ba65a40916b8afc1b64103afcf5dcde7dfccf9e8282053938ca1127b2307.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/tables/1dd4ba65a40916b8afc1b64103afcf5dcde7dfccf9e8282053938ca1127b2307.jpg)

![a8f25a4aee0ffc4bf8f470e6dcff9a45aa8baeba2a1eac4352e95e0f5bdbde89.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/tables/a8f25a4aee0ffc4bf8f470e6dcff9a45aa8baeba2a1eac4352e95e0f5bdbde89.jpg)

![e9fd97254a1ed3aeebaf35551e3bb3ee3003ad0901de28e8bdda070caa50a6a1.jpg](../nips_results/5071_Cognitive%20Predictive%20Processing_%20A%20Human-inspired%20Framework%20for%20Adaptive%20Exploration%20in%20Open-World%20R/tables/e9fd97254a1ed3aeebaf35551e3bb3ee3003ad0901de28e8bdda070caa50a6a1.jpg)

## See&Trek: Training-Free Spatial Prompting for Multimodal Large Language Model


### Images

![2ef855b0f7e00be08bc8debf1d3f296aded12b8fa16c75464e875cede3f2e8ed.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/images/2ef855b0f7e00be08bc8debf1d3f296aded12b8fa16c75464e875cede3f2e8ed.jpg)

![2febfa42bf8e8206966079d04899520f3fa7053eb7926cc9d3026ddb5c0fb7f1.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/images/2febfa42bf8e8206966079d04899520f3fa7053eb7926cc9d3026ddb5c0fb7f1.jpg)

![43d203a1455b5ed8bb98821cd28f0eca943714900d0aa5241f2ee67ea87428cf.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/images/43d203a1455b5ed8bb98821cd28f0eca943714900d0aa5241f2ee67ea87428cf.jpg)

![78fcf81970daad1273dde5f25fdccd6dd227f8cf78c2c4efd3ce0c857de0e270.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/images/78fcf81970daad1273dde5f25fdccd6dd227f8cf78c2c4efd3ce0c857de0e270.jpg)

![86dab051e7ce5b9c220ca4eeb707708f125fe3355b5e1ff2c4a1c7cba2afb5a5.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/images/86dab051e7ce5b9c220ca4eeb707708f125fe3355b5e1ff2c4a1c7cba2afb5a5.jpg)

![912334fb7208b56c9aecdcab75608fb5b981e23a4b4d740f1d44299ece21edf0.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/images/912334fb7208b56c9aecdcab75608fb5b981e23a4b4d740f1d44299ece21edf0.jpg)

![a29e1347beec4e0a6b863ff97707320fc1459fb77097928650fad8f6667ae779.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/images/a29e1347beec4e0a6b863ff97707320fc1459fb77097928650fad8f6667ae779.jpg)

![a46851727c871e06a58ee0246ccdc36f6960e1c0dfcf4ddf485cdaa7983e5006.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/images/a46851727c871e06a58ee0246ccdc36f6960e1c0dfcf4ddf485cdaa7983e5006.jpg)

![bd5f481a2d6de81e193df223e3d0115f8d61de7357d5f2e3477749d0b1f7e825.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/images/bd5f481a2d6de81e193df223e3d0115f8d61de7357d5f2e3477749d0b1f7e825.jpg)

![f0301f8a0280bea2ed8982a31b2d6f3e841e3ded5b81dbf901ab7cd90c660eac.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/images/f0301f8a0280bea2ed8982a31b2d6f3e841e3ded5b81dbf901ab7cd90c660eac.jpg)

### Tables

![10c8f7fdcbe32cc02637d5643b3d75137ea7afd60753acf0aba9310ae23cd6ec.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/10c8f7fdcbe32cc02637d5643b3d75137ea7afd60753acf0aba9310ae23cd6ec.jpg)

![14142b52f4e05e2722289760673c1306ad8a2cb7857e8fd0f1707dfac9a953c8.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/14142b52f4e05e2722289760673c1306ad8a2cb7857e8fd0f1707dfac9a953c8.jpg)

![27badcad98a80e671ab3578038a9e29f654a3bda896f9ff1ce04e81854f311f0.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/27badcad98a80e671ab3578038a9e29f654a3bda896f9ff1ce04e81854f311f0.jpg)

![2fb480cb77bb5727dae76df37065f72831618b962b8bc9b40284bbf1fab35229.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/2fb480cb77bb5727dae76df37065f72831618b962b8bc9b40284bbf1fab35229.jpg)

![34171171d6f919e7fad8528061005d1d038815572b9fcfd1b539aa6e3452f533.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/34171171d6f919e7fad8528061005d1d038815572b9fcfd1b539aa6e3452f533.jpg)

![394ba0a40970367a2857d53ab6d73a4a4d233c8be2caf12bd8a0aaa8d75fb29e.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/394ba0a40970367a2857d53ab6d73a4a4d233c8be2caf12bd8a0aaa8d75fb29e.jpg)

![45d458959a345bc9c817c0f78c5091e5e4b3449fc46bb2a2bce2d07294a0cb1d.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/45d458959a345bc9c817c0f78c5091e5e4b3449fc46bb2a2bce2d07294a0cb1d.jpg)

![4bad0bcdebe17371dafcc5ed5825fad617aac661eb68178806c7efef5556e71a.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/4bad0bcdebe17371dafcc5ed5825fad617aac661eb68178806c7efef5556e71a.jpg)

![708a79866bddc9f95ebfcacf48264df305b5ce61bd762b8c5c1acdbb4a599c51.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/708a79866bddc9f95ebfcacf48264df305b5ce61bd762b8c5c1acdbb4a599c51.jpg)

![71e668e4fc6bb575f721ba58540c8453dc389ae06ddce9b17ae09a3864081eaa.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/71e668e4fc6bb575f721ba58540c8453dc389ae06ddce9b17ae09a3864081eaa.jpg)

![8866e4f63e63a0167cd996c17c4fd5b0087abfe199c400d18d7e6ce7ebc8a378.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/8866e4f63e63a0167cd996c17c4fd5b0087abfe199c400d18d7e6ce7ebc8a378.jpg)

![887f00bdceec6294b2149223e7e27d3c2163fd373505b3505aa0d4db223e6734.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/887f00bdceec6294b2149223e7e27d3c2163fd373505b3505aa0d4db223e6734.jpg)

![8ab33ed5756c0da2b94f6451a3ea7ea39b91d387ed8c81514e6e9171a25fd42b.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/8ab33ed5756c0da2b94f6451a3ea7ea39b91d387ed8c81514e6e9171a25fd42b.jpg)

![b3ee676b83f42c5079528fd38f8d78e916f91e7e669b8a31c6b4bfe46764ead3.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/b3ee676b83f42c5079528fd38f8d78e916f91e7e669b8a31c6b4bfe46764ead3.jpg)

![b532faa61f90cd57c1e8b1e322fe114ae0dee3bd55afb190fa70085fd18c306a.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/b532faa61f90cd57c1e8b1e322fe114ae0dee3bd55afb190fa70085fd18c306a.jpg)

![ce7dd393b0b53f41f1435e2c8e237c3cb402d5f3fe4ba3286d54997c34b032c5.jpg](../nips_results/5072_See%26Trek_%20Training-Free%20Spatial%20Prompting%20for%20Multimodal%20Large%20Language%20Model/tables/ce7dd393b0b53f41f1435e2c8e237c3cb402d5f3fe4ba3286d54997c34b032c5.jpg)

## CovMatch: Cross-Covariance Guided Multimodal Dataset Distillation with Trainable Text Encoder


### Images

![0e2f149f3afccfe397879c043ce9f002928eb27da1ffe516e2a76a3167f4dc0c.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/images/0e2f149f3afccfe397879c043ce9f002928eb27da1ffe516e2a76a3167f4dc0c.jpg)

![1a3eb5b9dfdb20afcd0d9c1ca1d07a7e2999bcc861c7b5d0b9c1fd76778fdefa.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/images/1a3eb5b9dfdb20afcd0d9c1ca1d07a7e2999bcc861c7b5d0b9c1fd76778fdefa.jpg)

![25a70f7fb2f19863aa1afdce281072311a5b11c16faeeace4b886c640d6e218c.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/images/25a70f7fb2f19863aa1afdce281072311a5b11c16faeeace4b886c640d6e218c.jpg)

![29132acc579908cc71b7934559164876474c00cb1b458fc388ff30ca6f9a71a5.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/images/29132acc579908cc71b7934559164876474c00cb1b458fc388ff30ca6f9a71a5.jpg)

![3b6f02df212b59f4a21d23db8c15b3e5731abee7e4dd57590b471e44e338a504.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/images/3b6f02df212b59f4a21d23db8c15b3e5731abee7e4dd57590b471e44e338a504.jpg)

![8bb330c1e947071bbf0631824c45b82b19be27bcd0ae29438d39ebbe4788514e.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/images/8bb330c1e947071bbf0631824c45b82b19be27bcd0ae29438d39ebbe4788514e.jpg)

![8c61b45d5721b8f6a96f26d8f7e4b2b316a6b0f98c79f50cbb1386ebec36a8ca.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/images/8c61b45d5721b8f6a96f26d8f7e4b2b316a6b0f98c79f50cbb1386ebec36a8ca.jpg)

![c5d09b9c9f59d5cbd5b21055fbd5ab256a75b48444f6f41512190a4a939f7fd3.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/images/c5d09b9c9f59d5cbd5b21055fbd5ab256a75b48444f6f41512190a4a939f7fd3.jpg)

![cd42a84ac7b8949f5ed0c9734b89e7190761542ce899c5f4a36c392c955babf0.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/images/cd42a84ac7b8949f5ed0c9734b89e7190761542ce899c5f4a36c392c955babf0.jpg)

![f3caf09fbae3530330dbc478bcdcdebb234cd23a34c98642964e26c4f298f2fc.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/images/f3caf09fbae3530330dbc478bcdcdebb234cd23a34c98642964e26c4f298f2fc.jpg)

### Tables

![1088db7878727ffef41cefd5267bb1b9ae1525def8c1f9004dc27a3000630e22.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/1088db7878727ffef41cefd5267bb1b9ae1525def8c1f9004dc27a3000630e22.jpg)

![38eaa77fbcca03063030e3f9543236d706fe9cd2a24ce7b0ae5a0ae8ca6c5bf6.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/38eaa77fbcca03063030e3f9543236d706fe9cd2a24ce7b0ae5a0ae8ca6c5bf6.jpg)

![42e71abfeaa9cf05c224a38feb7c5c1263e488c616ea194e2153b4159ffc6859.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/42e71abfeaa9cf05c224a38feb7c5c1263e488c616ea194e2153b4159ffc6859.jpg)

![792d2c35376bcaceef4dbc1c18cc147fca935cd48f6f746c37ed9b001b4d066a.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/792d2c35376bcaceef4dbc1c18cc147fca935cd48f6f746c37ed9b001b4d066a.jpg)

![7aac79ecec20eb8607edbdf9144840b1426d672056793a8a6ba38fa2eee07d4b.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/7aac79ecec20eb8607edbdf9144840b1426d672056793a8a6ba38fa2eee07d4b.jpg)

![8181713a9ed577fdcde62494b5f49c0d57aeeaa6b8eb9fe6aed68fc33859fdf1.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/8181713a9ed577fdcde62494b5f49c0d57aeeaa6b8eb9fe6aed68fc33859fdf1.jpg)

![a014cd95e7b51de95e7c6609222ad597ba9c193abb382e9b761586e235ad66d4.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/a014cd95e7b51de95e7c6609222ad597ba9c193abb382e9b761586e235ad66d4.jpg)

![a70e4dd79160e24eaa4bedca9aa3c23c63fe25f593013271197fbac28b0c8f47.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/a70e4dd79160e24eaa4bedca9aa3c23c63fe25f593013271197fbac28b0c8f47.jpg)

![aed1a88c900d7998e0a08016f0fb778524f7e97fe7ac4869ad69baa02a64783c.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/aed1a88c900d7998e0a08016f0fb778524f7e97fe7ac4869ad69baa02a64783c.jpg)

![cdc9f3dd6c78a19442a75027cf9c52e9ca58167ce645201a59e2de8228a1db24.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/cdc9f3dd6c78a19442a75027cf9c52e9ca58167ce645201a59e2de8228a1db24.jpg)

![d0356e6afd29b6cec7b62c1bf41c4853d58891acd5e61bbbde88454c3f8a94a5.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/d0356e6afd29b6cec7b62c1bf41c4853d58891acd5e61bbbde88454c3f8a94a5.jpg)

![e2934455e938ff750fb3f9cb7456c5e3c0b547f102be00d7d7e11ad7f70a3719.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/e2934455e938ff750fb3f9cb7456c5e3c0b547f102be00d7d7e11ad7f70a3719.jpg)

![e339dcd0d208d26492928969fcc4608def7f5179e8f0e63f2c1d57e0b9a91d99.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/e339dcd0d208d26492928969fcc4608def7f5179e8f0e63f2c1d57e0b9a91d99.jpg)

![e66716d3263a6c342296ea99b55a4363a2f27e1626a19f1342285ac8a83b203d.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/e66716d3263a6c342296ea99b55a4363a2f27e1626a19f1342285ac8a83b203d.jpg)

![fc843eeb11dddbd455a23ea94be7350e283f71ee7f7a2b5dd458ac4178bc8b66.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/fc843eeb11dddbd455a23ea94be7350e283f71ee7f7a2b5dd458ac4178bc8b66.jpg)

![ff62f25e89c3a318d6ccda88827cf9d0ae9c045835fd88f4a675ea8894c88b64.jpg](../nips_results/5073_CovMatch_%20Cross-Covariance%20Guided%20Multimodal%20Dataset%20Distillation%20with%20Trainable%20Text%20Encoder/tables/ff62f25e89c3a318d6ccda88827cf9d0ae9c045835fd88f4a675ea8894c88b64.jpg)

## Conformal Inference under High-Dimensional Covariate Shifts via Likelihood-Ratio Regularization


### Images

![3d88fc266a90e84f12563e9de42f4966f701f00b24a44a70b72380a24dcb6727.jpg](../nips_results/5074_Conformal%20Inference%20under%20High-Dimensional%20Covariate%20Shifts%20via%20Likelihood-Ratio%20Regularization/images/3d88fc266a90e84f12563e9de42f4966f701f00b24a44a70b72380a24dcb6727.jpg)

![5f2e69dddc50ccbe3f3bdaba5ed132ccaf2838fb162c792e8edfcd09a72085c9.jpg](../nips_results/5074_Conformal%20Inference%20under%20High-Dimensional%20Covariate%20Shifts%20via%20Likelihood-Ratio%20Regularization/images/5f2e69dddc50ccbe3f3bdaba5ed132ccaf2838fb162c792e8edfcd09a72085c9.jpg)

![c2cd94a36314bef28d07fecda8d90c39986903c7d3202526dc47829ae84462e4.jpg](../nips_results/5074_Conformal%20Inference%20under%20High-Dimensional%20Covariate%20Shifts%20via%20Likelihood-Ratio%20Regularization/images/c2cd94a36314bef28d07fecda8d90c39986903c7d3202526dc47829ae84462e4.jpg)

![f320ad8c39db3785bfbe81133fb2fd10b615ae3177d3137c843ba831fa49cd27.jpg](../nips_results/5074_Conformal%20Inference%20under%20High-Dimensional%20Covariate%20Shifts%20via%20Likelihood-Ratio%20Regularization/images/f320ad8c39db3785bfbe81133fb2fd10b615ae3177d3137c843ba831fa49cd27.jpg)

### Tables

![821d2f0bbd8f5e70a62922146c6047898295bd678f59b68d2b62f98e77a1cf02.jpg](../nips_results/5074_Conformal%20Inference%20under%20High-Dimensional%20Covariate%20Shifts%20via%20Likelihood-Ratio%20Regularization/tables/821d2f0bbd8f5e70a62922146c6047898295bd678f59b68d2b62f98e77a1cf02.jpg)

## Improving Formal Reasoning of Transformer with State Stack


### Images

![6f0e6692b07e590cfc6d280935760511d876c968f833d63a7a7907d11c42b498.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/images/6f0e6692b07e590cfc6d280935760511d876c968f833d63a7a7907d11c42b498.jpg)

![706e0e42a60f1ca188771a68412e31ed79518b04b0375f832698352d3d6043df.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/images/706e0e42a60f1ca188771a68412e31ed79518b04b0375f832698352d3d6043df.jpg)

![bee57caea55c17a910bc8a95d929ca01f1c9cd89f0788ea545f170f5be29b309.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/images/bee57caea55c17a910bc8a95d929ca01f1c9cd89f0788ea545f170f5be29b309.jpg)

![e599e8679b561b0ff347b78513ca503d84916b851a6ede955637b85bf099fa74.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/images/e599e8679b561b0ff347b78513ca503d84916b851a6ede955637b85bf099fa74.jpg)

![f6346b8ddc68e360ee00e5e19f6dfe3f5659840982bd73263889ad4cdfbfa0fc.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/images/f6346b8ddc68e360ee00e5e19f6dfe3f5659840982bd73263889ad4cdfbfa0fc.jpg)

### Tables

![0ba7420beba82e533f6b0ed7ccfe0a86c6bd7be9bb180734c9fbbd589ab94876.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/tables/0ba7420beba82e533f6b0ed7ccfe0a86c6bd7be9bb180734c9fbbd589ab94876.jpg)

![2c0f0cb0a726ee023b6dae84ff0d4ce21fdf93facf1a262bfcde3eb7955a2d6f.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/tables/2c0f0cb0a726ee023b6dae84ff0d4ce21fdf93facf1a262bfcde3eb7955a2d6f.jpg)

![5c07fd2d0aa97fc0581a07235b23cb47227d27619be6cda7c46bc52db0405568.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/tables/5c07fd2d0aa97fc0581a07235b23cb47227d27619be6cda7c46bc52db0405568.jpg)

![6804816e7a993e3fb41f02593c94865b23a1a4f45fbb983d1eb2ee29535392ac.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/tables/6804816e7a993e3fb41f02593c94865b23a1a4f45fbb983d1eb2ee29535392ac.jpg)

![9ea0175e09fcd8d200d28e2754e9fbca1a574184c286c3a4d09c5e44101aa324.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/tables/9ea0175e09fcd8d200d28e2754e9fbca1a574184c286c3a4d09c5e44101aa324.jpg)

![f5c7f08449940dff98b77dba88bbdaaebbeb60209cd5ba952ec6b0770491eb6f.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/tables/f5c7f08449940dff98b77dba88bbdaaebbeb60209cd5ba952ec6b0770491eb6f.jpg)

![f7cf1f43478100f4a38345c9ad74128e051aac9156962708ebb6f3e43138d88b.jpg](../nips_results/5075_Improving%20Formal%20Reasoning%20of%20Transformer%20with%20State%20Stack/tables/f7cf1f43478100f4a38345c9ad74128e051aac9156962708ebb6f3e43138d88b.jpg)

## FP64 is All You Need: Rethinking Failure Modes in Physics-Informed Neural Networks


### Images

![1dab87eb6479a03fa43fcbbf2d5304de92b6837c370784fdc694deb15c2c4750.jpg](../nips_results/5076_FP64%20is%20All%20You%20Need_%20Rethinking%20Failure%20Modes%20in%20Physics-Informed%20Neural%20Networks/images/1dab87eb6479a03fa43fcbbf2d5304de92b6837c370784fdc694deb15c2c4750.jpg)

![2934b2491e7379a9a4fa2da95ba231136b3dd55d57c47a97f7f4e49844647cb7.jpg](../nips_results/5076_FP64%20is%20All%20You%20Need_%20Rethinking%20Failure%20Modes%20in%20Physics-Informed%20Neural%20Networks/images/2934b2491e7379a9a4fa2da95ba231136b3dd55d57c47a97f7f4e49844647cb7.jpg)

![44f9bb1a03c852429fa33fd1472dd983d6f34f138914a030d90429a6d132d501.jpg](../nips_results/5076_FP64%20is%20All%20You%20Need_%20Rethinking%20Failure%20Modes%20in%20Physics-Informed%20Neural%20Networks/images/44f9bb1a03c852429fa33fd1472dd983d6f34f138914a030d90429a6d132d501.jpg)

![8fd099333ee450ce7111a90432af73fb25f5a3c509f79b10805506cd6b4170c9.jpg](../nips_results/5076_FP64%20is%20All%20You%20Need_%20Rethinking%20Failure%20Modes%20in%20Physics-Informed%20Neural%20Networks/images/8fd099333ee450ce7111a90432af73fb25f5a3c509f79b10805506cd6b4170c9.jpg)

![9ae07505cba5f98e9253c78dbe155fb884833b23ba657906d64f16b9ee2853c6.jpg](../nips_results/5076_FP64%20is%20All%20You%20Need_%20Rethinking%20Failure%20Modes%20in%20Physics-Informed%20Neural%20Networks/images/9ae07505cba5f98e9253c78dbe155fb884833b23ba657906d64f16b9ee2853c6.jpg)

![c010ced7eca2394fc34f87585eb4743d061887842fe16e19c4b1871c67f7d493.jpg](../nips_results/5076_FP64%20is%20All%20You%20Need_%20Rethinking%20Failure%20Modes%20in%20Physics-Informed%20Neural%20Networks/images/c010ced7eca2394fc34f87585eb4743d061887842fe16e19c4b1871c67f7d493.jpg)

![c22574ebf30787e79159d09825e9f0b24ec6406af67a32d7490109a1c725d96c.jpg](../nips_results/5076_FP64%20is%20All%20You%20Need_%20Rethinking%20Failure%20Modes%20in%20Physics-Informed%20Neural%20Networks/images/c22574ebf30787e79159d09825e9f0b24ec6406af67a32d7490109a1c725d96c.jpg)

![d7a26f05a88b5c216765ff4760447f10fb19f271bf98bdc549e1953abe210442.jpg](../nips_results/5076_FP64%20is%20All%20You%20Need_%20Rethinking%20Failure%20Modes%20in%20Physics-Informed%20Neural%20Networks/images/d7a26f05a88b5c216765ff4760447f10fb19f271bf98bdc549e1953abe210442.jpg)

### Tables

![8ec34290b79900030747fa695acec49f554f8afa57a3f17275cc7edcebf46c65.jpg](../nips_results/5076_FP64%20is%20All%20You%20Need_%20Rethinking%20Failure%20Modes%20in%20Physics-Informed%20Neural%20Networks/tables/8ec34290b79900030747fa695acec49f554f8afa57a3f17275cc7edcebf46c65.jpg)

![f0115703fc2b71500a1962f12fa273b77bae9b252fefbaa9b872d1c9e7cc2542.jpg](../nips_results/5076_FP64%20is%20All%20You%20Need_%20Rethinking%20Failure%20Modes%20in%20Physics-Informed%20Neural%20Networks/tables/f0115703fc2b71500a1962f12fa273b77bae9b252fefbaa9b872d1c9e7cc2542.jpg)

## $\textit{HiMaCon:}$ Discovering Hierarchical Manipulation Concepts from Unlabeled Multi-Modal Data


### Images

![107128c54a0a383144bc09a953592d648a8acaffdbba711ad22920b940e9e5d2.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/107128c54a0a383144bc09a953592d648a8acaffdbba711ad22920b940e9e5d2.jpg)

![1195c0170a7ce3099d387cd750d20902c034932c958424376b1c47db77208e58.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/1195c0170a7ce3099d387cd750d20902c034932c958424376b1c47db77208e58.jpg)

![35bcda1d4679e619fd83675cc07325e296e27d93c0fdbe99c3c205c3afaa9a68.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/35bcda1d4679e619fd83675cc07325e296e27d93c0fdbe99c3c205c3afaa9a68.jpg)

![59260d74e4268b9ca9ec1fa5dc1e36df6c83f5a6960384bf5bb14b3f4b1c06fa.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/59260d74e4268b9ca9ec1fa5dc1e36df6c83f5a6960384bf5bb14b3f4b1c06fa.jpg)

![68c92545e28cb3bf66020985d2a6d0329517604d38607fda1a88c9fc73ee37e8.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/68c92545e28cb3bf66020985d2a6d0329517604d38607fda1a88c9fc73ee37e8.jpg)

![774831e2dcae9f23ddd995f8683bd259e042f81827f880e3fc89abd59dbe706f.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/774831e2dcae9f23ddd995f8683bd259e042f81827f880e3fc89abd59dbe706f.jpg)

![7c9a03731374695f4fc779c7f28ba23065feb2d7b9418d730f43ff9f435a65ea.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/7c9a03731374695f4fc779c7f28ba23065feb2d7b9418d730f43ff9f435a65ea.jpg)

![808491afbd93289bcd84e8b54d9c36dd496e88628db829365bc59077c2c415f5.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/808491afbd93289bcd84e8b54d9c36dd496e88628db829365bc59077c2c415f5.jpg)

![b4bac1d8be256e5b0b97e36d9a4269958d220dd4d550a28114c7eed87536155a.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/b4bac1d8be256e5b0b97e36d9a4269958d220dd4d550a28114c7eed87536155a.jpg)

![b51ab8a2acae15fbe89323c855a1feb3c4dc1ae573ffeaf38811f813f3741842.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/b51ab8a2acae15fbe89323c855a1feb3c4dc1ae573ffeaf38811f813f3741842.jpg)

![d9c928034a09cbba724f80ab71063c7cb632d6c9e3b389c3c6fe83f095a01ba2.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/d9c928034a09cbba724f80ab71063c7cb632d6c9e3b389c3c6fe83f095a01ba2.jpg)

![f5e40a89a853944736d43e466b40e20ff927c374233d6b159cf3f123656153aa.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/images/f5e40a89a853944736d43e466b40e20ff927c374233d6b159cf3f123656153aa.jpg)

### Tables

![5417dbabff2b5dd7a794f8181773bc3cad7cae75091a7547e5b23fc7471750cd.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/5417dbabff2b5dd7a794f8181773bc3cad7cae75091a7547e5b23fc7471750cd.jpg)

![6470464e48ac1177775014d3d774e31fb8b4559dc2928ff961fe347d114548bf.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/6470464e48ac1177775014d3d774e31fb8b4559dc2928ff961fe347d114548bf.jpg)

![6e1f36c5236c37642eb08a7f5b824842981a4fac34be1d3052bce64ec471c9e4.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/6e1f36c5236c37642eb08a7f5b824842981a4fac34be1d3052bce64ec471c9e4.jpg)

![7c814d7749df33a84e18379e9e72b859a1159c06d4e9ac8aa6d8abfa71408e3c.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/7c814d7749df33a84e18379e9e72b859a1159c06d4e9ac8aa6d8abfa71408e3c.jpg)

![7cae1988f42d1ee65dfc1b7c4b853450eeef9911fe97662056ffe6f0f71c115f.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/7cae1988f42d1ee65dfc1b7c4b853450eeef9911fe97662056ffe6f0f71c115f.jpg)

![84b287639889d26ae7c324cb09f6b16cda93b5aae2c6aa965188240d981b3f1f.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/84b287639889d26ae7c324cb09f6b16cda93b5aae2c6aa965188240d981b3f1f.jpg)

![951a649bad02354ff3fdec801338a0948922c7284c3297fdf1e52a299213a687.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/951a649bad02354ff3fdec801338a0948922c7284c3297fdf1e52a299213a687.jpg)

![afeef692532bffd3a6d478c6562b6530aa9a5c6c9707ace363e679aea6ae460a.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/afeef692532bffd3a6d478c6562b6530aa9a5c6c9707ace363e679aea6ae460a.jpg)

![b2286e2298de8892a0e1c752019074b8cca1b84ad964cff9d44054998aa67c3d.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/b2286e2298de8892a0e1c752019074b8cca1b84ad964cff9d44054998aa67c3d.jpg)

![bdf093231d5d0883bc8fc87000166cbc8fb0b635b5cc7150b164742208c88035.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/bdf093231d5d0883bc8fc87000166cbc8fb0b635b5cc7150b164742208c88035.jpg)

![d33a88f9f0b3f201fcdfac6604c41dcedfdaa53a1156bc1cf404c0f5afedb088.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/d33a88f9f0b3f201fcdfac6604c41dcedfdaa53a1156bc1cf404c0f5afedb088.jpg)

![d5b56a92b04fe352f3a4d9a9cc8d197ee00f48379415eac84138734a0c4424a0.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/d5b56a92b04fe352f3a4d9a9cc8d197ee00f48379415eac84138734a0c4424a0.jpg)

![e4a9bd6f4fd138557c0cb7eab09b8d63c642aa93d8fea6297011e47f0da34d5b.jpg](../nips_results/5077_%24_textit%7BHiMaCon_%7D%24%20Discovering%20Hierarchical%20Manipulation%20Concepts%20from%20Unlabeled%20Multi-Modal%20Data/tables/e4a9bd6f4fd138557c0cb7eab09b8d63c642aa93d8fea6297011e47f0da34d5b.jpg)

## Bivariate Matrix-valued Linear Regression (BMLR): Finite-sample performance under Identifiability and Sparsity Assumptions


### Images

![5a37ad9d0549b447bdc630894b00bbf50a190eaaad15523f0f6f0af9a5a1300d.jpg](../nips_results/5078_Bivariate%20Matrix-valued%20Linear%20Regression%20%28BMLR)_ Finite-sample performance under Identifiability an/images/5a37ad9d0549b447bdc630894b00bbf50a190eaaad15523f0f6f0af9a5a1300d.jpg)

![6e25c3d02570fe3a237a03a087bdcf540c2a306e632f856dd15ced93c6a1a35b.jpg](../nips_results/5078_Bivariate%20Matrix-valued%20Linear%20Regression%20%28BMLR)_ Finite-sample performance under Identifiability an/images/6e25c3d02570fe3a237a03a087bdcf540c2a306e632f856dd15ced93c6a1a35b.jpg)

![87c47608e75587548b7a94a895820b64059a79f4b5fbda013761e82466416c51.jpg](../nips_results/5078_Bivariate%20Matrix-valued%20Linear%20Regression%20%28BMLR)_ Finite-sample performance under Identifiability an/images/87c47608e75587548b7a94a895820b64059a79f4b5fbda013761e82466416c51.jpg)

![a134fb51f6d655b8e8dc822dd516ca73121e6dca5fc0b958b9a6aa32f6d84fb5.jpg](../nips_results/5078_Bivariate%20Matrix-valued%20Linear%20Regression%20%28BMLR)_ Finite-sample performance under Identifiability an/images/a134fb51f6d655b8e8dc822dd516ca73121e6dca5fc0b958b9a6aa32f6d84fb5.jpg)

![d52470a7c173bc68a4e26e90b76a73000a9a8409b7c306575881f5d43f1a97da.jpg](../nips_results/5078_Bivariate%20Matrix-valued%20Linear%20Regression%20%28BMLR)_ Finite-sample performance under Identifiability an/images/d52470a7c173bc68a4e26e90b76a73000a9a8409b7c306575881f5d43f1a97da.jpg)

![e81085e2759f6b027f5e16075cbb05826aa306f2b90415f606071162876625d6.jpg](../nips_results/5078_Bivariate%20Matrix-valued%20Linear%20Regression%20%28BMLR)_ Finite-sample performance under Identifiability an/images/e81085e2759f6b027f5e16075cbb05826aa306f2b90415f606071162876625d6.jpg)

### Tables

![5024b50dfe36a15a132177e75c9961fe480cb638877403804f07cb8baeeea086.jpg](../nips_results/5078_Bivariate%20Matrix-valued%20Linear%20Regression%20%28BMLR)_ Finite-sample performance under Identifiability an/tables/5024b50dfe36a15a132177e75c9961fe480cb638877403804f07cb8baeeea086.jpg)

## DAPO: An Open-Source LLM Reinforcement Learning System at Scale


### Images

![340b0811ac9920e6c9351f38a5f699a4b46eec04182f4633a2df3b4417b800b2.jpg](../nips_results/5079_DAPO_%20An%20Open-Source%20LLM%20Reinforcement%20Learning%20System%20at%20Scale/images/340b0811ac9920e6c9351f38a5f699a4b46eec04182f4633a2df3b4417b800b2.jpg)

![465173c18e7c9d28350511f6812d2ecb136d729439c19ab21e221f01c86f5455.jpg](../nips_results/5079_DAPO_%20An%20Open-Source%20LLM%20Reinforcement%20Learning%20System%20at%20Scale/images/465173c18e7c9d28350511f6812d2ecb136d729439c19ab21e221f01c86f5455.jpg)

![651107dbe1a3374ad081994be353b29e470c7c273ba4c6851042df48f10a4204.jpg](../nips_results/5079_DAPO_%20An%20Open-Source%20LLM%20Reinforcement%20Learning%20System%20at%20Scale/images/651107dbe1a3374ad081994be353b29e470c7c273ba4c6851042df48f10a4204.jpg)

![90dc1e4cd50d31b97d4173993e485abd75d296f5fca22614893561597718f72b.jpg](../nips_results/5079_DAPO_%20An%20Open-Source%20LLM%20Reinforcement%20Learning%20System%20at%20Scale/images/90dc1e4cd50d31b97d4173993e485abd75d296f5fca22614893561597718f72b.jpg)

![b84e168acecf172c27d994fca3a19c6f15664e699df6e1b8a107e0499bf27c9b.jpg](../nips_results/5079_DAPO_%20An%20Open-Source%20LLM%20Reinforcement%20Learning%20System%20at%20Scale/images/b84e168acecf172c27d994fca3a19c6f15664e699df6e1b8a107e0499bf27c9b.jpg)

![d0515fc9e1e0c81c8b388e1ef641618d24fd3aae0aa95b98c84a44c10a23cc64.jpg](../nips_results/5079_DAPO_%20An%20Open-Source%20LLM%20Reinforcement%20Learning%20System%20at%20Scale/images/d0515fc9e1e0c81c8b388e1ef641618d24fd3aae0aa95b98c84a44c10a23cc64.jpg)

![e02ba400f4eb2597aea6d1bd271313097031c37825fbc00e71a8a4ad1a00841e.jpg](../nips_results/5079_DAPO_%20An%20Open-Source%20LLM%20Reinforcement%20Learning%20System%20at%20Scale/images/e02ba400f4eb2597aea6d1bd271313097031c37825fbc00e71a8a4ad1a00841e.jpg)

### Tables

![1a5a8ce83ed31e54199269a409efacae6884642378dc02a701714888a6ef8392.jpg](../nips_results/5079_DAPO_%20An%20Open-Source%20LLM%20Reinforcement%20Learning%20System%20at%20Scale/tables/1a5a8ce83ed31e54199269a409efacae6884642378dc02a701714888a6ef8392.jpg)

![7c9121a66d4cf58e3a8d99d494c8fed0ddd7ce6d7a901f3e84c7ccc16541a70e.jpg](../nips_results/5079_DAPO_%20An%20Open-Source%20LLM%20Reinforcement%20Learning%20System%20at%20Scale/tables/7c9121a66d4cf58e3a8d99d494c8fed0ddd7ce6d7a901f3e84c7ccc16541a70e.jpg)

## Conditional Panoramic Image Generation via Masked Autoregressive Modeling


### Images

![04a93dcc1bdfcdc11ca6b07997faa0712b35d3a175e76e94c385885266901d1e.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/04a93dcc1bdfcdc11ca6b07997faa0712b35d3a175e76e94c385885266901d1e.jpg)

![2fb472283a033e0753c9e02ca60b9b7b60c9574def845201d148fd5e7b248408.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/2fb472283a033e0753c9e02ca60b9b7b60c9574def845201d148fd5e7b248408.jpg)

![3dca0982019c6b750089e78f7f295e972f9e530f0b0b6b0298d23f0a4aa2157a.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/3dca0982019c6b750089e78f7f295e972f9e530f0b0b6b0298d23f0a4aa2157a.jpg)

![3e974185b95acfacb6e9fa3771c0696210ea0e0860427cd0830ed222e785c380.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/3e974185b95acfacb6e9fa3771c0696210ea0e0860427cd0830ed222e785c380.jpg)

![436c56c521829120d8459cb86e8b6ee5016540f49d3f18aa9914a7003f992c92.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/436c56c521829120d8459cb86e8b6ee5016540f49d3f18aa9914a7003f992c92.jpg)

![441480d5149d87dcf175a17646e4537fcf2d306ae588673f23d6725fe8c9e693.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/441480d5149d87dcf175a17646e4537fcf2d306ae588673f23d6725fe8c9e693.jpg)

![54a09f0efe12667fb1cbd3a01768d80339c92bfb806927fbbe21bc68375595eb.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/54a09f0efe12667fb1cbd3a01768d80339c92bfb806927fbbe21bc68375595eb.jpg)

![769edd22f8b7bbddcb99b992232c1a6d58e2008d555d0bb483deb2c01abba051.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/769edd22f8b7bbddcb99b992232c1a6d58e2008d555d0bb483deb2c01abba051.jpg)

![8f634b8e045e4b0b0e4ffee97f6cdbeac6707616fb7c9238d24e7d950389820a.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/8f634b8e045e4b0b0e4ffee97f6cdbeac6707616fb7c9238d24e7d950389820a.jpg)

![9581eb0a05b38d7e00200c1a5ba4f53102ac4fbb2831a4ba1f4defc2b90cc08a.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/9581eb0a05b38d7e00200c1a5ba4f53102ac4fbb2831a4ba1f4defc2b90cc08a.jpg)

![a69751144770e271fa85b25d0626d0ee7d39a95babebc5857bf56448a3c00282.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/a69751144770e271fa85b25d0626d0ee7d39a95babebc5857bf56448a3c00282.jpg)

![aa0fd0f83d1030ac945ca523966bb9918798e8858181ddcbb57f7a09cbf0270a.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/aa0fd0f83d1030ac945ca523966bb9918798e8858181ddcbb57f7a09cbf0270a.jpg)

![c02c26342808353fe7e697a2048da5d71d7003059117096abcab00d1828e1b4a.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/c02c26342808353fe7e697a2048da5d71d7003059117096abcab00d1828e1b4a.jpg)

![c4e873c9de11faa659afc5c7caa10ed81a625e9927a9f0286d6b1468ba5d0c1a.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/c4e873c9de11faa659afc5c7caa10ed81a625e9927a9f0286d6b1468ba5d0c1a.jpg)

![d588104769df003c38672a10ae846923a3ad526325bd97c471294431dcd5fef6.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/d588104769df003c38672a10ae846923a3ad526325bd97c471294431dcd5fef6.jpg)

![d628d280392831270732bcce01f461c9e922778a348c59e784ed6636f0748f95.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/d628d280392831270732bcce01f461c9e922778a348c59e784ed6636f0748f95.jpg)

![f74db307d8b0b6ab6600181f07f4f76c522324438afac93b44c830452e5169a0.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/f74db307d8b0b6ab6600181f07f4f76c522324438afac93b44c830452e5169a0.jpg)

![f7c396e55623b64f8eae2b19e1892a7d37820df783605e90d239a792b4b8c2ea.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/f7c396e55623b64f8eae2b19e1892a7d37820df783605e90d239a792b4b8c2ea.jpg)

![f7ca708d764f620954ea175f805d8dbb324006769bf47efef0ab34f1bbfb4205.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/images/f7ca708d764f620954ea175f805d8dbb324006769bf47efef0ab34f1bbfb4205.jpg)

### Tables

![058a1c8658663f47b7dca56289741e351fe744295f00386e20253b9601215784.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/tables/058a1c8658663f47b7dca56289741e351fe744295f00386e20253b9601215784.jpg)

![13b622a053404e861557ff633cd058e01d58ae397540000a2c270ad8c9335e91.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/tables/13b622a053404e861557ff633cd058e01d58ae397540000a2c270ad8c9335e91.jpg)

![172286e2c7711149f146182663fe3f83787247939017411809411d4eb194c7ce.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/tables/172286e2c7711149f146182663fe3f83787247939017411809411d4eb194c7ce.jpg)

![26912e6371add2877c7b25b431cdba6c2afb51905888a3805ac7719fa33a80e0.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/tables/26912e6371add2877c7b25b431cdba6c2afb51905888a3805ac7719fa33a80e0.jpg)

![ab53ff8c4783f57ecbc6568c73a07c6c9efb7a9091a5e19587c872f49b2f7921.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/tables/ab53ff8c4783f57ecbc6568c73a07c6c9efb7a9091a5e19587c872f49b2f7921.jpg)

![b01ac6dc13f284867aebbee38d37d7b6c5f4967c73fbc2bf734b34c85899b947.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/tables/b01ac6dc13f284867aebbee38d37d7b6c5f4967c73fbc2bf734b34c85899b947.jpg)

![cc37f622ca682fc7e592541f59a597692deed9eeb61ec431ed925d653d3dd0d7.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/tables/cc37f622ca682fc7e592541f59a597692deed9eeb61ec431ed925d653d3dd0d7.jpg)

![cf2b1904d53589dae24e7dac27ef774bdaa1bedee712fdaa1d7d4a8002aa2a28.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/tables/cf2b1904d53589dae24e7dac27ef774bdaa1bedee712fdaa1d7d4a8002aa2a28.jpg)

![d4ca9bc51f9bc2724da3ed1ff7a28430aa0657510d5a1ea755108482e0102065.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/tables/d4ca9bc51f9bc2724da3ed1ff7a28430aa0657510d5a1ea755108482e0102065.jpg)

![d5a84981aaed50812013b34ed073767689d9defbdaf5a239c53b360caa8bed85.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/tables/d5a84981aaed50812013b34ed073767689d9defbdaf5a239c53b360caa8bed85.jpg)

![e4565fc5adead7b00b45db462f70f3178a5838b1727221ad7c9a9fc0a5561d3f.jpg](../nips_results/5080_Conditional%20Panoramic%20Image%20Generation%20via%20Masked%20Autoregressive%20Modeling/tables/e4565fc5adead7b00b45db462f70f3178a5838b1727221ad7c9a9fc0a5561d3f.jpg)

## See through the Dark: Learning Illumination-affined Representations for Nighttime Occupancy Prediction


### Images

![0d231a12550cea8e23ab30221449935a042e48de58786b999f17d1b935cf657c.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/images/0d231a12550cea8e23ab30221449935a042e48de58786b999f17d1b935cf657c.jpg)

![2d6a6eee3af5f5c0ea0bfb0132fae26a7e4a31e4ee8288f1c1d85a54023ce9da.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/images/2d6a6eee3af5f5c0ea0bfb0132fae26a7e4a31e4ee8288f1c1d85a54023ce9da.jpg)

![3fc7979b9586284fbfe07a625df0e8c4bd9bad51f82e4e9ce8c098e451a65f82.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/images/3fc7979b9586284fbfe07a625df0e8c4bd9bad51f82e4e9ce8c098e451a65f82.jpg)

![4130b1091140390a49c2289e87a730e5656bf84f7a8246156670a0f3a97a3f3f.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/images/4130b1091140390a49c2289e87a730e5656bf84f7a8246156670a0f3a97a3f3f.jpg)

![607ae86f0aca0b504361bdf916a1765ab41429baac5abe176406f05f5f8d9ef3.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/images/607ae86f0aca0b504361bdf916a1765ab41429baac5abe176406f05f5f8d9ef3.jpg)

![98a91aeaecd5037304315e6078911bfbc7a8575df98f37e3647d365b2483d314.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/images/98a91aeaecd5037304315e6078911bfbc7a8575df98f37e3647d365b2483d314.jpg)

![b39c68d65d3cf48314f500757766384c238cef1266adbb7ab58edce2232adeb9.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/images/b39c68d65d3cf48314f500757766384c238cef1266adbb7ab58edce2232adeb9.jpg)

![b58266b9292d7bb6fd2322392b001b61a213c1421a82d0d7b8a600daa8221c51.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/images/b58266b9292d7bb6fd2322392b001b61a213c1421a82d0d7b8a600daa8221c51.jpg)

![bbc056235fbf6bcd59cd81c04f0540cea183dfa2a0fa01b4558bab1ac625a940.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/images/bbc056235fbf6bcd59cd81c04f0540cea183dfa2a0fa01b4558bab1ac625a940.jpg)

![bec621adf749dcc5e1007b68e0c3e0735cc68f34bc219d8510f3f3d70ac4edcf.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/images/bec621adf749dcc5e1007b68e0c3e0735cc68f34bc219d8510f3f3d70ac4edcf.jpg)

![e242fe56e257418fa17d83706dcf5cfb6f50928aaccc7ad0e5184746c27b164b.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/images/e242fe56e257418fa17d83706dcf5cfb6f50928aaccc7ad0e5184746c27b164b.jpg)

### Tables

![12588a32988049f9157d6083ef32a9432a62cf3faa459beacd37b93fa30b1c7a.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/tables/12588a32988049f9157d6083ef32a9432a62cf3faa459beacd37b93fa30b1c7a.jpg)

![51b27ba2e59f2060ee242c982f9784b8d27ee1afee54518ee9d2e942658b0925.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/tables/51b27ba2e59f2060ee242c982f9784b8d27ee1afee54518ee9d2e942658b0925.jpg)

![6b3288db049cfede50bf858a49ad95b2535e4f63028ea9ca2810b95edb415825.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/tables/6b3288db049cfede50bf858a49ad95b2535e4f63028ea9ca2810b95edb415825.jpg)

![87f0d7c42a93048e01daeafee068ad691764039c3b9e4f3fbc1b06dc3ef0261b.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/tables/87f0d7c42a93048e01daeafee068ad691764039c3b9e4f3fbc1b06dc3ef0261b.jpg)

![b84add5289f237ced1aadf3d17dcae38a584ef1625a77708c8593740b3e988a2.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/tables/b84add5289f237ced1aadf3d17dcae38a584ef1625a77708c8593740b3e988a2.jpg)

![d30e60356d339abba83774e31a2121d8b2ac826c99abb720d6b3887a309dc26b.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/tables/d30e60356d339abba83774e31a2121d8b2ac826c99abb720d6b3887a309dc26b.jpg)

![ea77cab9c32f2b75044e8ce53913ba144f6ee9f1de77e0caf054ee7af3d7c5b2.jpg](../nips_results/5081_See%20through%20the%20Dark_%20Learning%20Illumination-affined%20Representations%20for%20Nighttime%20Occupancy%20Predicti/tables/ea77cab9c32f2b75044e8ce53913ba144f6ee9f1de77e0caf054ee7af3d7c5b2.jpg)

## DeepVideo-R1: Video Reinforcement Fine-Tuning via Difficulty-aware Regressive GRPO


### Images

![63d89ecac7139372a824408b95985749e78b0d7969f28bd8147953118387178e.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/images/63d89ecac7139372a824408b95985749e78b0d7969f28bd8147953118387178e.jpg)

![925c8a8d0d8cb2b40790c9383cda744a8f299563b3ac2b2e5b972b1578f72afd.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/images/925c8a8d0d8cb2b40790c9383cda744a8f299563b3ac2b2e5b972b1578f72afd.jpg)

![9acad464a6c5e593e96fe468ebe0ce6b1a0ab3dee1cedc81ea8b645f5bc3390f.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/images/9acad464a6c5e593e96fe468ebe0ce6b1a0ab3dee1cedc81ea8b645f5bc3390f.jpg)

![c9eed9b6913f971ef080a0e288ebb414e7a8cecc8d8412b940c1e2ae51576650.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/images/c9eed9b6913f971ef080a0e288ebb414e7a8cecc8d8412b940c1e2ae51576650.jpg)

![f5311d946b81d54fa05e79f133cad090fcc3b1951c74c6d56095d85588ec6be5.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/images/f5311d946b81d54fa05e79f133cad090fcc3b1951c74c6d56095d85588ec6be5.jpg)

### Tables

![079d1eafa10a83b7fa6f7a3f565ebacb520e991bafc0efed0d242569059af53e.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/tables/079d1eafa10a83b7fa6f7a3f565ebacb520e991bafc0efed0d242569059af53e.jpg)

![1698da8dd0795a76db994d3a71a51bfce6cc43618810e503acd9e2d6fd2ab9df.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/tables/1698da8dd0795a76db994d3a71a51bfce6cc43618810e503acd9e2d6fd2ab9df.jpg)

![416095c79711877967155112271da15502aaf9f28d05315ebeaa5dd36c2b46f8.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/tables/416095c79711877967155112271da15502aaf9f28d05315ebeaa5dd36c2b46f8.jpg)

![7e998d845f0dc29ba4a23100ea769b653053e9445622c326bace7dc8d24658ca.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/tables/7e998d845f0dc29ba4a23100ea769b653053e9445622c326bace7dc8d24658ca.jpg)

![8095e4112f603c277d4ecea9cc5fc2feafa7c696a1c3cab75b3ed6b8f382c265.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/tables/8095e4112f603c277d4ecea9cc5fc2feafa7c696a1c3cab75b3ed6b8f382c265.jpg)

![a7b1c62654bf1b2a0cc6e38d1210b3c72375c05027bfceb2a69efc54a98d8534.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/tables/a7b1c62654bf1b2a0cc6e38d1210b3c72375c05027bfceb2a69efc54a98d8534.jpg)

![c916ba310209d37191c4c38f2cc7ff0e82529aea2032e6634483eb28d28a569b.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/tables/c916ba310209d37191c4c38f2cc7ff0e82529aea2032e6634483eb28d28a569b.jpg)

![e24c5134c545a3d52d6fc8b88cb8f59dfb4e46deec879a5ad62f45508c06c996.jpg](../nips_results/5083_DeepVideo-R1_%20Video%20Reinforcement%20Fine-Tuning%20via%20Difficulty-aware%20Regressive%20GRPO/tables/e24c5134c545a3d52d6fc8b88cb8f59dfb4e46deec879a5ad62f45508c06c996.jpg)

## Additive Models Explained: A Computational Complexity Approach


### Tables

![6b735494785546bd84e196209132d471a30eb9bf4ccda65b462150ae57ed24fa.jpg](../nips_results/5084_Additive%20Models%20Explained_%20A%20Computational%20Complexity%20Approach/tables/6b735494785546bd84e196209132d471a30eb9bf4ccda65b462150ae57ed24fa.jpg)

![f6652e8e7eed4f4db80a3e946a7d16692158d65c3f68735352d9e07895396d1a.jpg](../nips_results/5084_Additive%20Models%20Explained_%20A%20Computational%20Complexity%20Approach/tables/f6652e8e7eed4f4db80a3e946a7d16692158d65c3f68735352d9e07895396d1a.jpg)

## GTR-Loc: Geospatial Text Regularization Assisted Outdoor LiDAR Localization


### Images

![260e0ff839b58f04986c746a1cdcfaabec06c6aedf16c315a5567b0fcb98b934.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/images/260e0ff839b58f04986c746a1cdcfaabec06c6aedf16c315a5567b0fcb98b934.jpg)

![3fdd308ccc8fec49fec168dfd4697b0bb1ca4e272fdf90f60af2d10a998b555d.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/images/3fdd308ccc8fec49fec168dfd4697b0bb1ca4e272fdf90f60af2d10a998b555d.jpg)

![41fd46522caed4a22d6f964e63114b43f73e2b5e75947ce1e8fdfbbef5431e4b.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/images/41fd46522caed4a22d6f964e63114b43f73e2b5e75947ce1e8fdfbbef5431e4b.jpg)

![9483ff7510e414596da1ad0e043a6b5145608c8e8eca0a6dcf7908745035a586.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/images/9483ff7510e414596da1ad0e043a6b5145608c8e8eca0a6dcf7908745035a586.jpg)

![dab4989563e5eb11370e6d2518cebeef1c370fb782760c6ec2027bcc97d891ca.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/images/dab4989563e5eb11370e6d2518cebeef1c370fb782760c6ec2027bcc97d891ca.jpg)

![f23fe52c2a6c1b8c77735e479f1c04d57c09d59d6d42454472be56d1be81b19a.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/images/f23fe52c2a6c1b8c77735e479f1c04d57c09d59d6d42454472be56d1be81b19a.jpg)

### Tables

![155db055745fac48387a99cd0234eb3bafa0d25eb13249f5952ecb8191603d7c.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/155db055745fac48387a99cd0234eb3bafa0d25eb13249f5952ecb8191603d7c.jpg)

![271a7152fa1f590ecb95bdf2395b2407355501fecd6ce762b7ffb15bdfc6d5c8.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/271a7152fa1f590ecb95bdf2395b2407355501fecd6ce762b7ffb15bdfc6d5c8.jpg)

![68e98faadff4ff172829a9f9fb094755d40ddd4ec812002b59a9fa80b7d6b186.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/68e98faadff4ff172829a9f9fb094755d40ddd4ec812002b59a9fa80b7d6b186.jpg)

![7c00f17316149c953949d00a7e76bf1872477514dbddb1cb8e64b97f7e540f58.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/7c00f17316149c953949d00a7e76bf1872477514dbddb1cb8e64b97f7e540f58.jpg)

![8a7f3886b5a69ed093b10dfbcf3e3124a07a28d0c20eb329baff24e8931260e3.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/8a7f3886b5a69ed093b10dfbcf3e3124a07a28d0c20eb329baff24e8931260e3.jpg)

![c115a23b7a68cd9ac041d0bdca1a18261d6464f3dd62be514534285bf9975ce9.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/c115a23b7a68cd9ac041d0bdca1a18261d6464f3dd62be514534285bf9975ce9.jpg)

![c40e4b19fe130c3131de3776bb5b361d9a639cb85c3dc4f95ecbb55d07209f34.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/c40e4b19fe130c3131de3776bb5b361d9a639cb85c3dc4f95ecbb55d07209f34.jpg)

![cc15d643e7a658b507fded62823d4d05b6e20c2c635359935e5a9cb9bbfe0349.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/cc15d643e7a658b507fded62823d4d05b6e20c2c635359935e5a9cb9bbfe0349.jpg)

![f543e4140dff824cb55da295103235ba8257bdebfe152311e46dda8ba26ba909.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/f543e4140dff824cb55da295103235ba8257bdebfe152311e46dda8ba26ba909.jpg)

![f7b0d16ac0863a5573ccb33e37b89c09ca67f9a6522b02aa7576c2949f02e59d.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/f7b0d16ac0863a5573ccb33e37b89c09ca67f9a6522b02aa7576c2949f02e59d.jpg)

![ff195896032827e4c543699a1ba71fb6f3de23f8b0b854537d051ba1fa97012e.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/ff195896032827e4c543699a1ba71fb6f3de23f8b0b854537d051ba1fa97012e.jpg)

![ffe5cfdf353d8cc5665523df8a40e73024c01bdc2f5769a82f4d5f85ebd61559.jpg](../nips_results/5085_GTR-Loc_%20Geospatial%20Text%20Regularization%20Assisted%20Outdoor%20LiDAR%20Localization/tables/ffe5cfdf353d8cc5665523df8a40e73024c01bdc2f5769a82f4d5f85ebd61559.jpg)

## Understanding Generalization in Physics Informed Models through Affine Variety Dimensions


### Images

![19f539a4cd6259e287c8550702ef0899660f627de0b9f3ff51387a88ac0f4830.jpg](../nips_results/5086_Understanding%20Generalization%20in%20Physics%20Informed%20Models%20through%20Affine%20Variety%20Dimensions/images/19f539a4cd6259e287c8550702ef0899660f627de0b9f3ff51387a88ac0f4830.jpg)

![47b5f31f0e2b177a0f859a05debe87cc90fa4933ab0ff98be5cf9c01ffc3ce30.jpg](../nips_results/5086_Understanding%20Generalization%20in%20Physics%20Informed%20Models%20through%20Affine%20Variety%20Dimensions/images/47b5f31f0e2b177a0f859a05debe87cc90fa4933ab0ff98be5cf9c01ffc3ce30.jpg)

![846ded8d8148a7a5ee41c3aab18db6240c510f72bf2c2a56f2fa36c034ba63eb.jpg](../nips_results/5086_Understanding%20Generalization%20in%20Physics%20Informed%20Models%20through%20Affine%20Variety%20Dimensions/images/846ded8d8148a7a5ee41c3aab18db6240c510f72bf2c2a56f2fa36c034ba63eb.jpg)

### Tables

![16f34fad56d1d217577dd50dc442002c5d0ffc592985a611f3a29a0cb0ca1a3c.jpg](../nips_results/5086_Understanding%20Generalization%20in%20Physics%20Informed%20Models%20through%20Affine%20Variety%20Dimensions/tables/16f34fad56d1d217577dd50dc442002c5d0ffc592985a611f3a29a0cb0ca1a3c.jpg)

![322fdb635f2794509f391c84ff2e79021d4d6adf5e65f74ad9cc76b63e57f279.jpg](../nips_results/5086_Understanding%20Generalization%20in%20Physics%20Informed%20Models%20through%20Affine%20Variety%20Dimensions/tables/322fdb635f2794509f391c84ff2e79021d4d6adf5e65f74ad9cc76b63e57f279.jpg)

![6375dac6e5602b98aa7f6ab308a858dfd242a1e313e2c96360841b57e1ea0c75.jpg](../nips_results/5086_Understanding%20Generalization%20in%20Physics%20Informed%20Models%20through%20Affine%20Variety%20Dimensions/tables/6375dac6e5602b98aa7f6ab308a858dfd242a1e313e2c96360841b57e1ea0c75.jpg)

![a7fc696833789622e0c8d45059d989fa5b32e79fcd983f689916f4d6c79eb4a3.jpg](../nips_results/5086_Understanding%20Generalization%20in%20Physics%20Informed%20Models%20through%20Affine%20Variety%20Dimensions/tables/a7fc696833789622e0c8d45059d989fa5b32e79fcd983f689916f4d6c79eb4a3.jpg)

![cbd48896849dd31cb1e5c0991f6bba798b52ae231b154f3d07084aaf3a45b2d3.jpg](../nips_results/5086_Understanding%20Generalization%20in%20Physics%20Informed%20Models%20through%20Affine%20Variety%20Dimensions/tables/cbd48896849dd31cb1e5c0991f6bba798b52ae231b154f3d07084aaf3a45b2d3.jpg)

![d9b0316b41a3dd53a1f983ea1f970fe8d28e5bbb76dd221fc276de7df842590f.jpg](../nips_results/5086_Understanding%20Generalization%20in%20Physics%20Informed%20Models%20through%20Affine%20Variety%20Dimensions/tables/d9b0316b41a3dd53a1f983ea1f970fe8d28e5bbb76dd221fc276de7df842590f.jpg)

![ffd7d4063c58316f5079444c4340d01cf18c922b176a702a27d1c77a35d55415.jpg](../nips_results/5086_Understanding%20Generalization%20in%20Physics%20Informed%20Models%20through%20Affine%20Variety%20Dimensions/tables/ffd7d4063c58316f5079444c4340d01cf18c922b176a702a27d1c77a35d55415.jpg)

## Bootstrapping Hierarchical Autoregressive Formal Reasoner with Chain-of-Proxy-Autoformalization


### Images

![1e9407624297f68c80841e541599662649c2a3a082bb617a4c01f1b40f1fe510.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/images/1e9407624297f68c80841e541599662649c2a3a082bb617a4c01f1b40f1fe510.jpg)

![5be5a73cf0d4eca267880edcc3966a3193db5cd6245ae0d62432a74441e1bba8.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/images/5be5a73cf0d4eca267880edcc3966a3193db5cd6245ae0d62432a74441e1bba8.jpg)

![ae3c39aa273899e33007bf932df31d5811ddbe368113db6ddb151f8bb7d63bf6.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/images/ae3c39aa273899e33007bf932df31d5811ddbe368113db6ddb151f8bb7d63bf6.jpg)

![e0b626c32aef60557f14025ab14e07f0d301b07fd817bb6fe619228aef9968f7.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/images/e0b626c32aef60557f14025ab14e07f0d301b07fd817bb6fe619228aef9968f7.jpg)

![eb4d429ba5c7de8689c0809ed9c869f172426b2bad1b838011f3fd4f3f042717.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/images/eb4d429ba5c7de8689c0809ed9c869f172426b2bad1b838011f3fd4f3f042717.jpg)

### Tables

![0daa25fc9c86271a2a56f57b5e66a088a574ca03a6646be19cdff3f5c1c8fa48.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/0daa25fc9c86271a2a56f57b5e66a088a574ca03a6646be19cdff3f5c1c8fa48.jpg)

![1fab9798bfd29e6a3770403c56051c0397043d45570e443bed38fd564586fdca.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/1fab9798bfd29e6a3770403c56051c0397043d45570e443bed38fd564586fdca.jpg)

![23cc1d8c5413f4b9d4f9aafff846598aa887978614807df5b6f6d7570b72008f.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/23cc1d8c5413f4b9d4f9aafff846598aa887978614807df5b6f6d7570b72008f.jpg)

![273dbdd2a8e3a49617ef59240e800d1b91cf8a291d12d944e2f744c629f0ffe1.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/273dbdd2a8e3a49617ef59240e800d1b91cf8a291d12d944e2f744c629f0ffe1.jpg)

![30ea9e0ccab2ee294d6be0e1458b36bf666e38521a1b26f2a2fa0a0bbcf36d2d.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/30ea9e0ccab2ee294d6be0e1458b36bf666e38521a1b26f2a2fa0a0bbcf36d2d.jpg)

![471bda8c4586d4ac2f7988ff8a78dccf0b0e2a5623dfa48b6afa27173fd9d1eb.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/471bda8c4586d4ac2f7988ff8a78dccf0b0e2a5623dfa48b6afa27173fd9d1eb.jpg)

![5c7f84196686eae227df30902c0a0bf92b810692f41f27038bcb418a68c75c8d.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/5c7f84196686eae227df30902c0a0bf92b810692f41f27038bcb418a68c75c8d.jpg)

![63bc3db8c36d88ff514d6227d58dfb9800bf0346f1677d760370b3b10f671e3d.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/63bc3db8c36d88ff514d6227d58dfb9800bf0346f1677d760370b3b10f671e3d.jpg)

![739e7b4a9756a38296a540b81e6a50d5e28950fd99a26ec230250959dc415a61.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/739e7b4a9756a38296a540b81e6a50d5e28950fd99a26ec230250959dc415a61.jpg)

![8338ab4ea4285a42446292101b8ca80b388e6d893ed93ab506126f748be1a8ea.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/8338ab4ea4285a42446292101b8ca80b388e6d893ed93ab506126f748be1a8ea.jpg)

![8b675dc521cad04705f1223127f1256f05b2ae69a35542c824ca93f62fdec0af.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/8b675dc521cad04705f1223127f1256f05b2ae69a35542c824ca93f62fdec0af.jpg)

![8ba323ecf77dcc993071469da5fa544aead22dfc917f325e77ca4ca560f7fc3f.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/8ba323ecf77dcc993071469da5fa544aead22dfc917f325e77ca4ca560f7fc3f.jpg)

![b7e49233ecd392271d5d0fc5c037c0fee5d0cc17c16836b2074f4b1cd6d3d0a6.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/b7e49233ecd392271d5d0fc5c037c0fee5d0cc17c16836b2074f4b1cd6d3d0a6.jpg)

![bc0d341e93f335705daec74e85d74473495409bb464d958e24f554a2f5443514.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/bc0d341e93f335705daec74e85d74473495409bb464d958e24f554a2f5443514.jpg)

![bc7a8b46f40e292f0894f32ea2d604cc42e0a81ed3578d86771e769d2b9aceca.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/bc7a8b46f40e292f0894f32ea2d604cc42e0a81ed3578d86771e769d2b9aceca.jpg)

![be768de6584701cc36c2d5e8ee6dab81dbbbcceaaa75991ab16373ce9e453cd4.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/be768de6584701cc36c2d5e8ee6dab81dbbbcceaaa75991ab16373ce9e453cd4.jpg)

![d56eff41e722883e263e5c5c61b11e4e6fde25168049585075c17f38d5d5590c.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/d56eff41e722883e263e5c5c61b11e4e6fde25168049585075c17f38d5d5590c.jpg)

![e8fcb7b51c3bb54e0e209ea9c9b7f8b0f5b894bd5d0a0a40685692dfbf6cf6ac.jpg](../nips_results/5087_Bootstrapping%20Hierarchical%20Autoregressive%20Formal%20Reasoner%20with%20Chain-of-Proxy-Autoformalization/tables/e8fcb7b51c3bb54e0e209ea9c9b7f8b0f5b894bd5d0a0a40685692dfbf6cf6ac.jpg)

## Path-specific effects for pulse-oximetry guided decisions in critical care


### Images

![144f39fa9065b7f52b9d379f933335fdeae94107ac42b1bfd78603259f36ede6.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/144f39fa9065b7f52b9d379f933335fdeae94107ac42b1bfd78603259f36ede6.jpg)

![40d6667149b710f49f66274a8a86fbae01ed8742490e4675ad43ce819922df6c.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/40d6667149b710f49f66274a8a86fbae01ed8742490e4675ad43ce819922df6c.jpg)

![467997dcc2c120a9dace36eddb888daaf475a8167b495c842361cb1c0ab3983a.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/467997dcc2c120a9dace36eddb888daaf475a8167b495c842361cb1c0ab3983a.jpg)

![62d0a2382c483830d7fcd3760d0aef899d30a25cb23990d5a703dbbbf22cff6a.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/62d0a2382c483830d7fcd3760d0aef899d30a25cb23990d5a703dbbbf22cff6a.jpg)

![69fc7840448dc111d4a9de43a44111ba5071454c4274116d6b39a8265554082e.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/69fc7840448dc111d4a9de43a44111ba5071454c4274116d6b39a8265554082e.jpg)

![749e2869ab2b7f2e9f9d40f31d04c30c96b76317b3a33f4bfcd17954de611a82.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/749e2869ab2b7f2e9f9d40f31d04c30c96b76317b3a33f4bfcd17954de611a82.jpg)

![8ac00e933a8746734c8527ece6e652be95315005fdec9ea147e2fe454ed84cd0.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/8ac00e933a8746734c8527ece6e652be95315005fdec9ea147e2fe454ed84cd0.jpg)

![9a76b15b3ad394f7d0541025e1f815db1e52f11eff401b4b3a151fba3e8cc971.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/9a76b15b3ad394f7d0541025e1f815db1e52f11eff401b4b3a151fba3e8cc971.jpg)

![b676598281181e67c757686db461137d32ee21ee130357ade635cc25c569f437.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/b676598281181e67c757686db461137d32ee21ee130357ade635cc25c569f437.jpg)

![c67dc1ecf9d1e287129d1766323c341a7ab22400ee3bcce5a44b47516ac770a6.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/c67dc1ecf9d1e287129d1766323c341a7ab22400ee3bcce5a44b47516ac770a6.jpg)

![d93898289848bd1b5ab9c8a1c2722a8e452e788b95a8564524620e45d1c452b1.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/d93898289848bd1b5ab9c8a1c2722a8e452e788b95a8564524620e45d1c452b1.jpg)

![e06b0cea9d142d01202e4c880348fcaed3c68a721b969ad252066eb4cbf4e022.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/e06b0cea9d142d01202e4c880348fcaed3c68a721b969ad252066eb4cbf4e022.jpg)

![e88a08a4e09120a09105e4a8a7c61482c752012e048a1a9edaf09fa6803aa4d5.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/e88a08a4e09120a09105e4a8a7c61482c752012e048a1a9edaf09fa6803aa4d5.jpg)

![f574f1c84f2796185ae07ad8f529a8c2cae561265880e41836275a8ce2bd848f.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/images/f574f1c84f2796185ae07ad8f529a8c2cae561265880e41836275a8ce2bd848f.jpg)

### Tables

![04b5605170a21a9751a38f8060af547d268b870be6880534c3abb797111eb2ef.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/tables/04b5605170a21a9751a38f8060af547d268b870be6880534c3abb797111eb2ef.jpg)

![07931a0f1f53fb4375492d9ead75c1f60faf9b21b2074de3f68df21012005efc.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/tables/07931a0f1f53fb4375492d9ead75c1f60faf9b21b2074de3f68df21012005efc.jpg)

![2775fe630635901acee7afc379b6de1c63f5c100677b6c11ce7ce745a22096f8.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/tables/2775fe630635901acee7afc379b6de1c63f5c100677b6c11ce7ce745a22096f8.jpg)

![829ff660756a851573fcc1f41f3c53229d9da54f606561fc2c9a131e9db02dc1.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/tables/829ff660756a851573fcc1f41f3c53229d9da54f606561fc2c9a131e9db02dc1.jpg)

![c0c0963a49563f9fb0e5071a9cf99b870db1ed30de7d828a0913936a9af18af0.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/tables/c0c0963a49563f9fb0e5071a9cf99b870db1ed30de7d828a0913936a9af18af0.jpg)

![c86ef7365cbbf00835d06c4923439c046bcb0b9b99826bad08db252800f6b2d9.jpg](../nips_results/5088_Path-specific%20effects%20for%20pulse-oximetry%20guided%20decisions%20in%20critical%20care/tables/c86ef7365cbbf00835d06c4923439c046bcb0b9b99826bad08db252800f6b2d9.jpg)

## Eyes Wide Open: Ego Proactive Video-LLM for Streaming Video


### Images

![13ec6c355e8c25c88930899bb47d7563c76de689624b7febe24883d01e8d2f5b.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/13ec6c355e8c25c88930899bb47d7563c76de689624b7febe24883d01e8d2f5b.jpg)

![1840f9f5c65e293319745e9d8eb6c12574e6450e3c5ceb94a5c9ba0193dca0c1.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/1840f9f5c65e293319745e9d8eb6c12574e6450e3c5ceb94a5c9ba0193dca0c1.jpg)

![21fc7f40776af6bcb064497ad6e3e63391c5a410fd5c10c4e64b7735556c94ce.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/21fc7f40776af6bcb064497ad6e3e63391c5a410fd5c10c4e64b7735556c94ce.jpg)

![24eb6737efd039b2b01d4b3d8e57786c5f0225093c25c11533b60cfa67570d4c.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/24eb6737efd039b2b01d4b3d8e57786c5f0225093c25c11533b60cfa67570d4c.jpg)

![25067df49df3b32617fc57b684bd40f69f9704e6864dad3c29b217accd0b5c39.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/25067df49df3b32617fc57b684bd40f69f9704e6864dad3c29b217accd0b5c39.jpg)

![2bc5cb48061f57ab36b54ca4529e5337ad7d47a54eab53b71e76abe466c42f29.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/2bc5cb48061f57ab36b54ca4529e5337ad7d47a54eab53b71e76abe466c42f29.jpg)

![322aec4158264dcd4ea2114d86de8fbcba2e83f272a2fd70ff59ebbfbfb6ef4c.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/322aec4158264dcd4ea2114d86de8fbcba2e83f272a2fd70ff59ebbfbfb6ef4c.jpg)

![324c877c4d08eb8d58685aa1aa0ff4f1c351a0e747c1d4fbcd03621b730ca6e0.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/324c877c4d08eb8d58685aa1aa0ff4f1c351a0e747c1d4fbcd03621b730ca6e0.jpg)

![38dbc433152e58e05b8b55b0242e348a07b4211f127efc4e465ba4726644de7e.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/38dbc433152e58e05b8b55b0242e348a07b4211f127efc4e465ba4726644de7e.jpg)

![3eccb172184384826f21dd3500097852fe41b6dda563271ba38c5b9565b30fe6.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/3eccb172184384826f21dd3500097852fe41b6dda563271ba38c5b9565b30fe6.jpg)

![48ce2a53367d2e69a8d789d39a8b02dbc226b7a1588c7eb0cb9d15092ea9ed3d.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/48ce2a53367d2e69a8d789d39a8b02dbc226b7a1588c7eb0cb9d15092ea9ed3d.jpg)

![6190da30423759c432430b6bcdd5406e7f863d3c2c5069a1706e8a2b2583c799.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/6190da30423759c432430b6bcdd5406e7f863d3c2c5069a1706e8a2b2583c799.jpg)

![71e48cc08c8c3d6bdcff48dccc606ad0075e33134c35d95663831dd81f792583.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/71e48cc08c8c3d6bdcff48dccc606ad0075e33134c35d95663831dd81f792583.jpg)

![73734df98a9e911f524c5b525c5a0666ac67db0826df66e07a97a1d5011bbcce.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/73734df98a9e911f524c5b525c5a0666ac67db0826df66e07a97a1d5011bbcce.jpg)

![772b22ed632a44c4029859eb6895b1230776036ce17a5ed60dbf38f42640ba25.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/772b22ed632a44c4029859eb6895b1230776036ce17a5ed60dbf38f42640ba25.jpg)

![77a0f65cca54ae500d98a60326f668b892a258629795f2b897924302185e8260.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/77a0f65cca54ae500d98a60326f668b892a258629795f2b897924302185e8260.jpg)

![7e7cdff9f2c84c1ad3b8e912b664e79d53e835a0b1c38519f85673b3909a954d.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/7e7cdff9f2c84c1ad3b8e912b664e79d53e835a0b1c38519f85673b3909a954d.jpg)

![809532264d9b42d61a138f354177f795a81f109801c0f41d0c620aed5a9b38b0.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/809532264d9b42d61a138f354177f795a81f109801c0f41d0c620aed5a9b38b0.jpg)

![864f5a4d84bfcdcbb4740f87cb9998a7760a9320f045f889f698c8b0817b6551.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/864f5a4d84bfcdcbb4740f87cb9998a7760a9320f045f889f698c8b0817b6551.jpg)

![86c31b532aaa509599d0f8e56eb812fc9cca65302795931a5f127bb997cee91e.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/86c31b532aaa509599d0f8e56eb812fc9cca65302795931a5f127bb997cee91e.jpg)

![8bef27413d158da4a515e7d691cec9d9979491ad148c1f9a536f15ccc77edaef.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/8bef27413d158da4a515e7d691cec9d9979491ad148c1f9a536f15ccc77edaef.jpg)

![a2ca1a87b230ddc90283d1f080a572a26b7c00026fdfa4fffb4017a43bc49c82.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/a2ca1a87b230ddc90283d1f080a572a26b7c00026fdfa4fffb4017a43bc49c82.jpg)

![aedf848326942d64f71e8d3ba5a8e47ff636b1135a6c36bcf858dfa38c7a6e4d.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/aedf848326942d64f71e8d3ba5a8e47ff636b1135a6c36bcf858dfa38c7a6e4d.jpg)

![b4b6d9552d59adfad3fc4c9d42c1890dd6f03212bba2a706b7dc0acfd721e567.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/b4b6d9552d59adfad3fc4c9d42c1890dd6f03212bba2a706b7dc0acfd721e567.jpg)

![b5e8e182af1c5dac54bc1f8ca320754603ea5aea0e31e169cff840c144372b53.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/b5e8e182af1c5dac54bc1f8ca320754603ea5aea0e31e169cff840c144372b53.jpg)

![c53708071afba71106443d284a67604f87f0f4195eb1f5fafeecc61236920eb5.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/c53708071afba71106443d284a67604f87f0f4195eb1f5fafeecc61236920eb5.jpg)

![cbaa281d8e6d1db6fbbca436595dd402257a0b1e640527f0f529713c0d38045b.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/cbaa281d8e6d1db6fbbca436595dd402257a0b1e640527f0f529713c0d38045b.jpg)

![cd6604d04fb6af09bbd390ac1be3ef9f2e753f1093a96b6ef456ef2e41eb41ec.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/cd6604d04fb6af09bbd390ac1be3ef9f2e753f1093a96b6ef456ef2e41eb41ec.jpg)

![d26780e2ee64b67f48f658d8405fff39143cc56cc954cc1c3ffec0a3b8e13a66.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/d26780e2ee64b67f48f658d8405fff39143cc56cc954cc1c3ffec0a3b8e13a66.jpg)

![d711269c9023821241c761d37f580d4fe7cc303a46c915aeac3fb3ce223baca3.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/d711269c9023821241c761d37f580d4fe7cc303a46c915aeac3fb3ce223baca3.jpg)

![fddaf14705ff256fb19845fc47d6969b18068465fd3c9211e753d7fc80edfe69.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/fddaf14705ff256fb19845fc47d6969b18068465fd3c9211e753d7fc80edfe69.jpg)

![ff4987137863cb3e3580e7d475314067b27b9068cf437d2d2a9fc63c883ea0c2.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/images/ff4987137863cb3e3580e7d475314067b27b9068cf437d2d2a9fc63c883ea0c2.jpg)

### Tables

![0af04e5eca375a6d0eb80f121b9caa6c1a0987cf1995e2485313df378c216553.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/tables/0af04e5eca375a6d0eb80f121b9caa6c1a0987cf1995e2485313df378c216553.jpg)

![28ae76c3563bd7e679f47fe757bb2a4c09c3c11868232ec965fc6026e8cde986.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/tables/28ae76c3563bd7e679f47fe757bb2a4c09c3c11868232ec965fc6026e8cde986.jpg)

![4bd1b4299de3deb530b00c3630914f5a50a5f4985d140a9febaa95847d5ebff3.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/tables/4bd1b4299de3deb530b00c3630914f5a50a5f4985d140a9febaa95847d5ebff3.jpg)

![4da668e50561bdd019c3146211a46a9facafb1f5720220bc26c265ad3ace0e55.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/tables/4da668e50561bdd019c3146211a46a9facafb1f5720220bc26c265ad3ace0e55.jpg)

![6570864bd990ce02fad8784682bfb3792c7589a1a0cff54b17d5209e9f5584c0.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/tables/6570864bd990ce02fad8784682bfb3792c7589a1a0cff54b17d5209e9f5584c0.jpg)

![858de4e2ca4897bf0f81b279faea507669cdb68a8a2d409849beaaf3b122aee6.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/tables/858de4e2ca4897bf0f81b279faea507669cdb68a8a2d409849beaaf3b122aee6.jpg)

![bfa6d8d54321db565b832aa1b99e8ea14bf5abc59b395a77cc434b087ea9bb5b.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/tables/bfa6d8d54321db565b832aa1b99e8ea14bf5abc59b395a77cc434b087ea9bb5b.jpg)

![db19eb8e4d3ddd8749311e5c130b97b0b391fef8001bc0cf5f876481521d0e09.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/tables/db19eb8e4d3ddd8749311e5c130b97b0b391fef8001bc0cf5f876481521d0e09.jpg)

![ec8571225d301ba106039848bda0b13693f3015054a2f47f1a54c315af36b2f2.jpg](../nips_results/5089_Eyes%20Wide%20Open_%20Ego%20Proactive%20Video-LLM%20for%20Streaming%20Video/tables/ec8571225d301ba106039848bda0b13693f3015054a2f47f1a54c315af36b2f2.jpg)

## Zero-Shot Detection of LLM-Generated Text via Implicit Reward Model


### Images

![51a606216d5eda56edce7b51fadb35bf43784da0a1f12a7a71dc7c18a26b26ae.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/images/51a606216d5eda56edce7b51fadb35bf43784da0a1f12a7a71dc7c18a26b26ae.jpg)

![d0173d9c0575acdc1e37c9d911893fd962dbaa7841226c56cfcc1dfadb0e7020.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/images/d0173d9c0575acdc1e37c9d911893fd962dbaa7841226c56cfcc1dfadb0e7020.jpg)

![e10af610737017331d818b047e09fd6f4f1db4dcbf96df9b77402da11818ef05.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/images/e10af610737017331d818b047e09fd6f4f1db4dcbf96df9b77402da11818ef05.jpg)

![ebf2fa29f4f79b00e7fe535fb3e16a3eda236d04614c34e9b12fc1c2d2cfcb14.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/images/ebf2fa29f4f79b00e7fe535fb3e16a3eda236d04614c34e9b12fc1c2d2cfcb14.jpg)

### Tables

![0d32bb92fd179d6bf41a27a41d4615f4259aa758b7d35badc14090805a8211fa.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/0d32bb92fd179d6bf41a27a41d4615f4259aa758b7d35badc14090805a8211fa.jpg)

![2a9db3d47d43f26c17e92e4e86555411ed52c54b7b45c1243bf044c5f8f05b1d.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/2a9db3d47d43f26c17e92e4e86555411ed52c54b7b45c1243bf044c5f8f05b1d.jpg)

![324d5b16530fc3cd57282818faac42c154f5198b446836b65c09362ad4efcc27.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/324d5b16530fc3cd57282818faac42c154f5198b446836b65c09362ad4efcc27.jpg)

![52809a274d678c16dee1265ea70dc48ff33c3bfdd446760f36907c4027a38874.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/52809a274d678c16dee1265ea70dc48ff33c3bfdd446760f36907c4027a38874.jpg)

![5d0d5d7decdd7698ec336088c43a17acdeaf3973fc26d6f3e4e37d8fc2fbe67a.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/5d0d5d7decdd7698ec336088c43a17acdeaf3973fc26d6f3e4e37d8fc2fbe67a.jpg)

![62879778671d73d862f8d8f5cd052f0ea207730507586daed0a287b82a5bfd2a.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/62879778671d73d862f8d8f5cd052f0ea207730507586daed0a287b82a5bfd2a.jpg)

![92d73e883447af87679634955e7f6513d760393a5cac8f491fc39577a03395c7.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/92d73e883447af87679634955e7f6513d760393a5cac8f491fc39577a03395c7.jpg)

![98c6646886ecf3593aaa2f1c91ed3f0da3332d9f41ef9741b390841e0820f674.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/98c6646886ecf3593aaa2f1c91ed3f0da3332d9f41ef9741b390841e0820f674.jpg)

![b7d6b30bf1197c80d48ee0a0e1557f0dc45beba9facea38b7382e276e5aab0e4.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/b7d6b30bf1197c80d48ee0a0e1557f0dc45beba9facea38b7382e276e5aab0e4.jpg)

![d2ea2e1687ef061b174895829a2b81f23d41cf7e42176dd4db09eb2915fcc978.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/d2ea2e1687ef061b174895829a2b81f23d41cf7e42176dd4db09eb2915fcc978.jpg)

![d55b75ae2ebb2b3be0d24e999c17158a6e25158e339574d0d5ff1d173e1f69d5.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/d55b75ae2ebb2b3be0d24e999c17158a6e25158e339574d0d5ff1d173e1f69d5.jpg)

![d5d9bdc3386b6b6dc86032ce4bed29838ea7ea23fb4a5278bac58ce4bb3a5935.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/d5d9bdc3386b6b6dc86032ce4bed29838ea7ea23fb4a5278bac58ce4bb3a5935.jpg)

![edc1c46eaf7ab03cf7e78ccae3ef84af01eef9d0d5e903cf16e409550a9e4d4e.jpg](../nips_results/5090_Zero-Shot%20Detection%20of%20LLM-Generated%20Text%20via%20Implicit%20Reward%20Model/tables/edc1c46eaf7ab03cf7e78ccae3ef84af01eef9d0d5e903cf16e409550a9e4d4e.jpg)

## Understanding outer learning rates in Local SGD


### Images

![02e5dcbdb287a46157612b1db9ba4942f5830ac0e4c0b478b6b01b3a43b8ef46.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/images/02e5dcbdb287a46157612b1db9ba4942f5830ac0e4c0b478b6b01b3a43b8ef46.jpg)

![10c1cd330dc5ba9a70ffc4a14ce396f4395d24619c5b8eda3ced57c19c6a0ecc.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/images/10c1cd330dc5ba9a70ffc4a14ce396f4395d24619c5b8eda3ced57c19c6a0ecc.jpg)

![311e307cb4c3bb14b48cc733cb8a7a6d2bd5495085c4f404ff02bf0336e6f973.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/images/311e307cb4c3bb14b48cc733cb8a7a6d2bd5495085c4f404ff02bf0336e6f973.jpg)

![45d3589769665afbd62c2af6be8c38b82c62a1b3cc6e27d1474d330debfccb4c.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/images/45d3589769665afbd62c2af6be8c38b82c62a1b3cc6e27d1474d330debfccb4c.jpg)

![7fe95c367914fac417944190f2175fb701e93d3d4657c4f9bba9b61f8c5f3b96.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/images/7fe95c367914fac417944190f2175fb701e93d3d4657c4f9bba9b61f8c5f3b96.jpg)

![ab78e8e6ca59613b4e115bf3a32139f3362e595fe9dde34017bac5a77630905a.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/images/ab78e8e6ca59613b4e115bf3a32139f3362e595fe9dde34017bac5a77630905a.jpg)

![cbe853d36c228e8c389c467fe4637c7c8b6ef9bc23cc52a3003db0880e33a40f.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/images/cbe853d36c228e8c389c467fe4637c7c8b6ef9bc23cc52a3003db0880e33a40f.jpg)

![de5824d581f37ea67a95c36f2874046c4226b2d19ae2d13cfe88d8e7347fda56.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/images/de5824d581f37ea67a95c36f2874046c4226b2d19ae2d13cfe88d8e7347fda56.jpg)

![e884216842ed60666965b7ebcf37e81311ee171e1274c8a8bb3f68a6deea403b.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/images/e884216842ed60666965b7ebcf37e81311ee171e1274c8a8bb3f68a6deea403b.jpg)

### Tables

![07e7e8bc21ec614ccfbb0c998b1650d19f9a7f6088710a28cf8a46a9f82becf7.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/tables/07e7e8bc21ec614ccfbb0c998b1650d19f9a7f6088710a28cf8a46a9f82becf7.jpg)

![3f9d80899f4959fe8aecf99e1b5a369ca6bb7ce158155d2c83cebc6d5e90ff24.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/tables/3f9d80899f4959fe8aecf99e1b5a369ca6bb7ce158155d2c83cebc6d5e90ff24.jpg)

![53f8365687db455e069695ab37ab1e5bf008d71d4f60c8924a94371d8f189f1f.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/tables/53f8365687db455e069695ab37ab1e5bf008d71d4f60c8924a94371d8f189f1f.jpg)

![6c62c0d0306815ba0ea864991ce29a053788ac4d2ea18063e26ee36011df255e.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/tables/6c62c0d0306815ba0ea864991ce29a053788ac4d2ea18063e26ee36011df255e.jpg)

![8f91759bfa18ed1b7570ed444cad375382ce968ecaaabbd1ee5f969510c897ed.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/tables/8f91759bfa18ed1b7570ed444cad375382ce968ecaaabbd1ee5f969510c897ed.jpg)

![9f3fefaad4db10ddf621e71e0a918b8ab07a538d6ac67808d625309ca36ac99c.jpg](../nips_results/5091_Understanding%20outer%20learning%20rates%20in%20Local%20SGD/tables/9f3fefaad4db10ddf621e71e0a918b8ab07a538d6ac67808d625309ca36ac99c.jpg)

## Rendering-Aware Reinforcement Learning for Vector Graphics Generation


### Images

![0eef64e3cb6e50646850329d9d773acb4a9e96c4e02b4451db7a29dd75842c4f.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/0eef64e3cb6e50646850329d9d773acb4a9e96c4e02b4451db7a29dd75842c4f.jpg)

![48a5c06123470eeae9c3b3ff5689729ad3d1e3c5938a763d0202dc795bbf9133.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/48a5c06123470eeae9c3b3ff5689729ad3d1e3c5938a763d0202dc795bbf9133.jpg)

![641223f7e715b58de8af33ed7398fc9034728e052742732f15ce11751ad3bb5a.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/641223f7e715b58de8af33ed7398fc9034728e052742732f15ce11751ad3bb5a.jpg)

![7b5e76317759f0ab5943ac964bada9d8d1b655b585660e8aaa926708ca5c9e6b.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/7b5e76317759f0ab5943ac964bada9d8d1b655b585660e8aaa926708ca5c9e6b.jpg)

![804ef7ad4e678c2c5aa4336e0e6a4b6fb4a4784f8b39c6b44c5aa8ca4afbe932.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/804ef7ad4e678c2c5aa4336e0e6a4b6fb4a4784f8b39c6b44c5aa8ca4afbe932.jpg)

![92a60b9cde34e4679fcb572f4b18c6b470ce9f7e69dd0c69bb397e453ec0e2d2.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/92a60b9cde34e4679fcb572f4b18c6b470ce9f7e69dd0c69bb397e453ec0e2d2.jpg)

![a74a7602ff2a42d5578c3889d07d59d154c78b7d00144c8a8c39c124d60b3f32.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/a74a7602ff2a42d5578c3889d07d59d154c78b7d00144c8a8c39c124d60b3f32.jpg)

![a8f4ceda7349ed5938a7b8640cdc295f5e461a3244716363885186140d2857a2.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/a8f4ceda7349ed5938a7b8640cdc295f5e461a3244716363885186140d2857a2.jpg)

![acd9f525c792fa6b1703e5ade2dbde8a6cb6286d58ae3a7c7327edd5f05e2634.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/acd9f525c792fa6b1703e5ade2dbde8a6cb6286d58ae3a7c7327edd5f05e2634.jpg)

![b16a4c95c7718ee7db7c6e7f1397552ac0dccc4140d2364b6ca06f619189da56.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/b16a4c95c7718ee7db7c6e7f1397552ac0dccc4140d2364b6ca06f619189da56.jpg)

![b1b22a41e148d321a9006b7adbd4c4573e61fd9661373c9ca77c444e411b817c.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/b1b22a41e148d321a9006b7adbd4c4573e61fd9661373c9ca77c444e411b817c.jpg)

![be0a99ee69db55420295bce602062be11a240b987a45c607892c9b9df9dc6b0e.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/be0a99ee69db55420295bce602062be11a240b987a45c607892c9b9df9dc6b0e.jpg)

![c4c7ecdd4f9e00bfacc143afe2d3d5c297ee34a0c8d48a1305f4b4cd6b3e18ea.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/c4c7ecdd4f9e00bfacc143afe2d3d5c297ee34a0c8d48a1305f4b4cd6b3e18ea.jpg)

![f38ed4f92c04f5bc4dc0d39c091b2cd6bc4f38762976c82e545aa602bf8bc7e9.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/f38ed4f92c04f5bc4dc0d39c091b2cd6bc4f38762976c82e545aa602bf8bc7e9.jpg)

![fb86d79da7da6e0ec359504b7299af14e59c192022a0f74076a62b9173a11e55.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/images/fb86d79da7da6e0ec359504b7299af14e59c192022a0f74076a62b9173a11e55.jpg)

### Tables

![8406a17db694928a0ff7d76f2efa8d1b146d678c541f80d6de1206bf9ce4cfe8.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/tables/8406a17db694928a0ff7d76f2efa8d1b146d678c541f80d6de1206bf9ce4cfe8.jpg)

![89ad48aadc9478e8360fea47e0b1e9c3f4e42853658b1bba15fda86453d5881f.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/tables/89ad48aadc9478e8360fea47e0b1e9c3f4e42853658b1bba15fda86453d5881f.jpg)

![91f725d73683d55aca1f56c2ba3f5746a8599674805ad445323cc064bf4e67e2.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/tables/91f725d73683d55aca1f56c2ba3f5746a8599674805ad445323cc064bf4e67e2.jpg)

![bb91a0686c84cc7ed7c7e088f0f258bbd1968a29f827423bfed055ef75f68a2d.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/tables/bb91a0686c84cc7ed7c7e088f0f258bbd1968a29f827423bfed055ef75f68a2d.jpg)

![dae9a3b8be989a3450fdec013dadfdf995c0e114852726edb25cfe84ba1b40d4.jpg](../nips_results/5092_Rendering-Aware%20Reinforcement%20Learning%20for%20Vector%20Graphics%20Generation/tables/dae9a3b8be989a3450fdec013dadfdf995c0e114852726edb25cfe84ba1b40d4.jpg)

## Transformer Key-Value Memories Are Nearly as Interpretable as Sparse Autoencoders


### Images

![00ce539a08c2437cf909c9e2c1d46548e8cc307b02b69e6844eaf093ff4c0c70.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/00ce539a08c2437cf909c9e2c1d46548e8cc307b02b69e6844eaf093ff4c0c70.jpg)

![0376c4df5ffbc8e6d93dc3e546e02f0ae2c1cd7e751d1a979bfaab7eac1b7ff3.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/0376c4df5ffbc8e6d93dc3e546e02f0ae2c1cd7e751d1a979bfaab7eac1b7ff3.jpg)

![08771fc4270be0258bab9b71a1afb49c59b498682a78eb4dc68fb3a178e6d559.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/08771fc4270be0258bab9b71a1afb49c59b498682a78eb4dc68fb3a178e6d559.jpg)

![0c6e604ccb75e90e112484be23b40443af713a44f4d3f31c7413ca0e43e76764.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/0c6e604ccb75e90e112484be23b40443af713a44f4d3f31c7413ca0e43e76764.jpg)

![0d98be612d478aef96360b71eca06e8a8b52d24214596342cfcba8dcdcc436ff.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/0d98be612d478aef96360b71eca06e8a8b52d24214596342cfcba8dcdcc436ff.jpg)

![0ef06a2cf2c81cb8d3f2756c3e9394ef5d59225cad592ff3c34bbb2894ec544c.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/0ef06a2cf2c81cb8d3f2756c3e9394ef5d59225cad592ff3c34bbb2894ec544c.jpg)

![10093f09b79be0a2a8da450b7b3ff1f68f775e3e8e79ba640eb2e95710fb8be4.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/10093f09b79be0a2a8da450b7b3ff1f68f775e3e8e79ba640eb2e95710fb8be4.jpg)

![124eaf0ab37793ae510ebc31cce1ed436548c0fd7204ed5e421ed57522688d0b.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/124eaf0ab37793ae510ebc31cce1ed436548c0fd7204ed5e421ed57522688d0b.jpg)

![1250035a0a7c7c595d633dcd39fd295aed707c3e4c2357150e9bba560caa8f9d.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/1250035a0a7c7c595d633dcd39fd295aed707c3e4c2357150e9bba560caa8f9d.jpg)

![1aa0c06c26f478d69b67021886592ab649a1ddf9548e49bb7a935157917a40ed.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/1aa0c06c26f478d69b67021886592ab649a1ddf9548e49bb7a935157917a40ed.jpg)

![268f1a82a7bb2d71332f428e92ad43f5879e8ab9ee949a65b42e1b625821bfcb.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/268f1a82a7bb2d71332f428e92ad43f5879e8ab9ee949a65b42e1b625821bfcb.jpg)

![28523fb9045c45eebaa57e70c1bdbc501866a7ff1b82fd1c042107431663f7a5.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/28523fb9045c45eebaa57e70c1bdbc501866a7ff1b82fd1c042107431663f7a5.jpg)

![28b2c9148adc3e395962edeb2d6c8476452cd7b58ef0044ce2cf9a34bf00186b.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/28b2c9148adc3e395962edeb2d6c8476452cd7b58ef0044ce2cf9a34bf00186b.jpg)

![3046c79cc4513ac1b3c15a97462ca471c2ca9a48c5bc0dd36db3784abbf6f2f4.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/3046c79cc4513ac1b3c15a97462ca471c2ca9a48c5bc0dd36db3784abbf6f2f4.jpg)

![304ed12243128d34a536f21617dc0de95af5117ce9ef6f44d47cee7b4bdfe998.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/304ed12243128d34a536f21617dc0de95af5117ce9ef6f44d47cee7b4bdfe998.jpg)

![37e5a181351dca41652a3c8f4e76ca0da16f30bd2785880b277fcdd1cc370ba6.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/37e5a181351dca41652a3c8f4e76ca0da16f30bd2785880b277fcdd1cc370ba6.jpg)

![380e32dfbd665dec995a1fec3d6a0d761ac89864344c2a157d6101addaf54802.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/380e32dfbd665dec995a1fec3d6a0d761ac89864344c2a157d6101addaf54802.jpg)

![401ed320c79c19468ffd0bda25d37fe87f2eebe053ae9a49ce9dd1a111365381.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/401ed320c79c19468ffd0bda25d37fe87f2eebe053ae9a49ce9dd1a111365381.jpg)

![402b934e0c6208b1de6921a106e1afac64c3d0198f0c47e6d0af4ae7f7af088f.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/402b934e0c6208b1de6921a106e1afac64c3d0198f0c47e6d0af4ae7f7af088f.jpg)

![429b6a6a1a4a20bcf20c39028356362a3b6786b6449ada19e1208f00c3537b94.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/429b6a6a1a4a20bcf20c39028356362a3b6786b6449ada19e1208f00c3537b94.jpg)

![48ec68dff6a2cdd30100e444af999e9cb2341c1d1d185bbe47c934136d943d96.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/48ec68dff6a2cdd30100e444af999e9cb2341c1d1d185bbe47c934136d943d96.jpg)

![4dd2497c4c17a65fea49ff42a705c19be7b942b9bf437009cfa372e7bd22dcd7.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/4dd2497c4c17a65fea49ff42a705c19be7b942b9bf437009cfa372e7bd22dcd7.jpg)

![514e9cff419f0ccbe5ff60c58ba73925a263bdebada0480cd1b388340f20aa1b.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/514e9cff419f0ccbe5ff60c58ba73925a263bdebada0480cd1b388340f20aa1b.jpg)

![51a4e1ad125bd6bf6b69fb6e1adcf328ff56131d80cb8e8f84c07c155c952bbb.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/51a4e1ad125bd6bf6b69fb6e1adcf328ff56131d80cb8e8f84c07c155c952bbb.jpg)

![53e08dc2305e3036728364f699ccc2226c35fcf23fe92141fa908161868594ed.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/53e08dc2305e3036728364f699ccc2226c35fcf23fe92141fa908161868594ed.jpg)

![5b5849e00be8b87bdafab28d4c4381dbccfdd2673a84e63b9726eb30071bfaac.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/5b5849e00be8b87bdafab28d4c4381dbccfdd2673a84e63b9726eb30071bfaac.jpg)

![645b7fe70cf1dd27bf19b5dc973e30b1cb42ba57b2bc21946ad0e0b908bc9d75.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/645b7fe70cf1dd27bf19b5dc973e30b1cb42ba57b2bc21946ad0e0b908bc9d75.jpg)

![66efe3ab494be0f9720d834b05d5b6960894cef4fefa9fe683bdb6674e511e5d.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/66efe3ab494be0f9720d834b05d5b6960894cef4fefa9fe683bdb6674e511e5d.jpg)

![691673718f7cc01738683ac57f2f467612535f0a3ea63ac0473a34e8934ad0ba.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/691673718f7cc01738683ac57f2f467612535f0a3ea63ac0473a34e8934ad0ba.jpg)

![76931b97d16a6ce7dfd3e814aa491089bcba87aa75424b47523f6645fc027039.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/76931b97d16a6ce7dfd3e814aa491089bcba87aa75424b47523f6645fc027039.jpg)

![7bb48143e260821ccd89e2e17fb9408df2662c33fd9f4eb011ffaf1be1b865f2.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/7bb48143e260821ccd89e2e17fb9408df2662c33fd9f4eb011ffaf1be1b865f2.jpg)

![7bc2a1f5fbc88230e4a351ba69522f810cfedcc2b94e691f8dd3ca152c126d7d.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/7bc2a1f5fbc88230e4a351ba69522f810cfedcc2b94e691f8dd3ca152c126d7d.jpg)

![7f7290b537d9517ceaba0a8cc928040e4a173dc1ed8bef80cd79044fa7f4eb36.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/7f7290b537d9517ceaba0a8cc928040e4a173dc1ed8bef80cd79044fa7f4eb36.jpg)

![84eddcdc1cc2084c1bc1cfceb3c8b18e6ca15b7033aa94bd869bac5a1e129330.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/84eddcdc1cc2084c1bc1cfceb3c8b18e6ca15b7033aa94bd869bac5a1e129330.jpg)

![93053e12b5f4346ae0712ccbcbc7dd6c429aaef6dac9d2428a4ce036ffe7d6de.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/93053e12b5f4346ae0712ccbcbc7dd6c429aaef6dac9d2428a4ce036ffe7d6de.jpg)

![93501d37765f37665429dc79000d4939d79ad91b1880ce30a3793bf587b463ae.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/93501d37765f37665429dc79000d4939d79ad91b1880ce30a3793bf587b463ae.jpg)

![9421b373cd26701a5e5e0550a75ba77044cba5df2d200f57d28cb1d092247b79.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/9421b373cd26701a5e5e0550a75ba77044cba5df2d200f57d28cb1d092247b79.jpg)

![94591ff6b64bcf2445a68f0a962a0091399caf1c2f648348681f5bd3963712e9.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/94591ff6b64bcf2445a68f0a962a0091399caf1c2f648348681f5bd3963712e9.jpg)

![999b17d441cedba327022801fc636a934521047a07e4e9c24fd9af1319cc73cd.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/999b17d441cedba327022801fc636a934521047a07e4e9c24fd9af1319cc73cd.jpg)

![9d5069286ef7ac811b2552c094389ea5a81f5fdd4de497220acadb0dffc137ed.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/9d5069286ef7ac811b2552c094389ea5a81f5fdd4de497220acadb0dffc137ed.jpg)

![a2013a22333735e7e0f7792afef4441758ec21f3746a935ec786112869044901.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/a2013a22333735e7e0f7792afef4441758ec21f3746a935ec786112869044901.jpg)

![a5cd782ad91f0a2a7d4464d68f0b74798d642c6ec601bf37809ef443b984d617.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/a5cd782ad91f0a2a7d4464d68f0b74798d642c6ec601bf37809ef443b984d617.jpg)

![a71371b75b5a324513f0439c45f63010ca4168368cf6355d08c91a7a238bd527.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/a71371b75b5a324513f0439c45f63010ca4168368cf6355d08c91a7a238bd527.jpg)

![bdc669b1e6e57065bb7f64983fa8f216a31408f46d3dd08818dae1852218f0f8.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/bdc669b1e6e57065bb7f64983fa8f216a31408f46d3dd08818dae1852218f0f8.jpg)

![cce48d58c3454b6e25cd2f1d9108182e7be27c855b939a4a80eb8abaa56af4db.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/cce48d58c3454b6e25cd2f1d9108182e7be27c855b939a4a80eb8abaa56af4db.jpg)

![cfe73c99dab9cb2425dfa55c732f5d3c52a046200e95fe9ace53d135c2ffc2b0.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/cfe73c99dab9cb2425dfa55c732f5d3c52a046200e95fe9ace53d135c2ffc2b0.jpg)

![e642f8da7e70320273ccb01f11040a84cdbe28162c399533a00d1d2f1a52061c.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/e642f8da7e70320273ccb01f11040a84cdbe28162c399533a00d1d2f1a52061c.jpg)

![e8a538e157a21f0a8c07aaf62b5b013169cce40c31969de253d043d223d2f4f1.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/e8a538e157a21f0a8c07aaf62b5b013169cce40c31969de253d043d223d2f4f1.jpg)

![e93cdd9b684c9daf3ab19097404b8b99101f1a29b2a0b173a1431117418f02e9.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/e93cdd9b684c9daf3ab19097404b8b99101f1a29b2a0b173a1431117418f02e9.jpg)

![efba13602d2871192213399f00cee8c4bb4d2341850cc510516dfd690297c148.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/efba13602d2871192213399f00cee8c4bb4d2341850cc510516dfd690297c148.jpg)

![f91dfacf24bdb59db3d7b7b844fbd98c71d24aba3489f85f881162999c5f1172.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/f91dfacf24bdb59db3d7b7b844fbd98c71d24aba3489f85f881162999c5f1172.jpg)

![fa20f2949983b638cd823d359664ad46840d98a8f8d7dccebe9b81a3744dab93.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/images/fa20f2949983b638cd823d359664ad46840d98a8f8d7dccebe9b81a3744dab93.jpg)

### Tables

![125af02b2df16929bbcbdec34cf66d2745bc1c7dbdfd17a648fb00ac536909c0.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/tables/125af02b2df16929bbcbdec34cf66d2745bc1c7dbdfd17a648fb00ac536909c0.jpg)

![5dca892d59ff9d53443f7453c92cffabfaf17564cfba1b17e4b995776307483c.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/tables/5dca892d59ff9d53443f7453c92cffabfaf17564cfba1b17e4b995776307483c.jpg)

![9bd3600bfa9830364543973775b2ef0e6581cb76058efb23748257d70704c15f.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/tables/9bd3600bfa9830364543973775b2ef0e6581cb76058efb23748257d70704c15f.jpg)

![b7ddafa1df5a72f5c18c2657dc044106ca81d65541d34106632696ea6b41f83b.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/tables/b7ddafa1df5a72f5c18c2657dc044106ca81d65541d34106632696ea6b41f83b.jpg)

![c9e30b4434a0a0002552b285e457aa4c592780697244c0e77cac72946b734a59.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/tables/c9e30b4434a0a0002552b285e457aa4c592780697244c0e77cac72946b734a59.jpg)

![d22f4083681b6d326292970fa2660f59609b2bd6b61d2f5ad1b732591348f01e.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/tables/d22f4083681b6d326292970fa2660f59609b2bd6b61d2f5ad1b732591348f01e.jpg)

![d96ccb015b5d2fa114584631bbbad0b089d4f2532b2dd2067e890662cd3c1128.jpg](../nips_results/5093_Transformer%20Key-Value%20Memories%20Are%20Nearly%20as%20Interpretable%20as%20Sparse%20Autoencoders/tables/d96ccb015b5d2fa114584631bbbad0b089d4f2532b2dd2067e890662cd3c1128.jpg)

## DOTA: Distributional Test-time Adaptation of Vision-Language Models


### Images

![029f990f6045518e30406f1d40e4958399866ee8f32173977c77df26aa9f16bc.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/images/029f990f6045518e30406f1d40e4958399866ee8f32173977c77df26aa9f16bc.jpg)

![485aec2ae68a71ebb74ea7e8dc887956fc465fdda974fe6e9f296ca9fe4dbe07.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/images/485aec2ae68a71ebb74ea7e8dc887956fc465fdda974fe6e9f296ca9fe4dbe07.jpg)

![c1aa6214687eb0af7abf78ea7280b2ccbc1cbbd005372c2d9de7301aa3a83d35.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/images/c1aa6214687eb0af7abf78ea7280b2ccbc1cbbd005372c2d9de7301aa3a83d35.jpg)

### Tables

![07aa15bf426b0229c0f6980e90721e7f5daf256bb0a30f921e71759992738083.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/07aa15bf426b0229c0f6980e90721e7f5daf256bb0a30f921e71759992738083.jpg)

![09a5c93dc3cf9dbd378e0380d241027429e44f09e1b868df9060a072f8d47a11.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/09a5c93dc3cf9dbd378e0380d241027429e44f09e1b868df9060a072f8d47a11.jpg)

![1a3198904f9af45578a3e2b4deb3c9e3667c9f84d992e346fd0178f1a07508d0.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/1a3198904f9af45578a3e2b4deb3c9e3667c9f84d992e346fd0178f1a07508d0.jpg)

![264c7bf01f21c2ada82906cf90a8b90ea562da18eebeeee4e6e409b6bcd73756.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/264c7bf01f21c2ada82906cf90a8b90ea562da18eebeeee4e6e409b6bcd73756.jpg)

![283563fbf8e22664d0cfbaa5d2fd599ff895bb9f0be7114b5f5433d8dd743596.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/283563fbf8e22664d0cfbaa5d2fd599ff895bb9f0be7114b5f5433d8dd743596.jpg)

![36350f660adb40ecd32c5586a7444b68675d13ea8b9038086214653f91a79fe1.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/36350f660adb40ecd32c5586a7444b68675d13ea8b9038086214653f91a79fe1.jpg)

![3692631cfbbb237880191ca4dbb204dbb26516df92708fa7251d6f6a9282c9bd.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/3692631cfbbb237880191ca4dbb204dbb26516df92708fa7251d6f6a9282c9bd.jpg)

![3880c091cf4714e68ce400de763296eea74577fa223ab5c72626efeb794d0ce8.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/3880c091cf4714e68ce400de763296eea74577fa223ab5c72626efeb794d0ce8.jpg)

![47fc64683ec86769299957c8d7004a083e789366f02f6ad77bd4cbc8c50ef1ab.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/47fc64683ec86769299957c8d7004a083e789366f02f6ad77bd4cbc8c50ef1ab.jpg)

![4b3624eb735222af7a6d3e163dd75037237579d4413e87f34df78872fdf8603e.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/4b3624eb735222af7a6d3e163dd75037237579d4413e87f34df78872fdf8603e.jpg)

![6c6b0a34bcf5e6d3484e0fb0a8aa61b6e0bdb0cf427e74db87b53fd9370ba612.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/6c6b0a34bcf5e6d3484e0fb0a8aa61b6e0bdb0cf427e74db87b53fd9370ba612.jpg)

![7ed74dfd5de9535b409ade6543e0f82f6095ab5025c7228a866e050fa843585b.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/7ed74dfd5de9535b409ade6543e0f82f6095ab5025c7228a866e050fa843585b.jpg)

![a63b687324d728760c5ef10669be5638d9d080179619da5ee11e5c71f9c439d0.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/a63b687324d728760c5ef10669be5638d9d080179619da5ee11e5c71f9c439d0.jpg)

![cf5d598f8a1b1ccc4c3affdb6d5bb1234dfb11c8fb44edbf2c5cb2d34be2b11e.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/cf5d598f8a1b1ccc4c3affdb6d5bb1234dfb11c8fb44edbf2c5cb2d34be2b11e.jpg)

![cfdddeb866f2e228d121afa968712c94523c551b595c5e65c9159514ec151f79.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/cfdddeb866f2e228d121afa968712c94523c551b595c5e65c9159514ec151f79.jpg)

![d5ab39048e75923e7288f4ce8fa031604d8cdcd83f0ce91e6dc5f11559ce1e1e.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/d5ab39048e75923e7288f4ce8fa031604d8cdcd83f0ce91e6dc5f11559ce1e1e.jpg)

![db69d4b4efcf97247dc77a0f40a5a703a411c5c4e28c04b2a6ada1bf29580525.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/db69d4b4efcf97247dc77a0f40a5a703a411c5c4e28c04b2a6ada1bf29580525.jpg)

![e8e57db865c5407cde64e52772c42f1bb0da27c26e1bb875e10d44325667f260.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/e8e57db865c5407cde64e52772c42f1bb0da27c26e1bb875e10d44325667f260.jpg)

![ee22dbabc0220553116297e7f707b2f8a01aa506d3c64cc4835e0f593144ce86.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/ee22dbabc0220553116297e7f707b2f8a01aa506d3c64cc4835e0f593144ce86.jpg)

![f17e4e6a65e4240343ccb8a69e64c983eb0174a5b3c861ff173a7f05def4b0c2.jpg](../nips_results/5094_DOTA_%20Distributional%20Test-time%20Adaptation%20of%20Vision-Language%20Models/tables/f17e4e6a65e4240343ccb8a69e64c983eb0174a5b3c861ff173a7f05def4b0c2.jpg)

## Beyond Single-Task: Robust Multi-Task Length Generalization for LLMs


### Images

![1549ff68aa4e69d5e4649f063ff9c0f7fdf6e83dc4594c37f362ac6dad34484e.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/1549ff68aa4e69d5e4649f063ff9c0f7fdf6e83dc4594c37f362ac6dad34484e.jpg)

![205b83f3b2fd28402a54a77821f17dce17f2ab501ca9323da995468b121bd4da.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/205b83f3b2fd28402a54a77821f17dce17f2ab501ca9323da995468b121bd4da.jpg)

![2e3e0e333db84b0826cea63b74d8d39872cb22f5cb9731adf2635a128a639c11.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/2e3e0e333db84b0826cea63b74d8d39872cb22f5cb9731adf2635a128a639c11.jpg)

![3b8d230d6388d369f62ee5bd3713b182cf10416188bf29da0dbc2936d397aab7.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/3b8d230d6388d369f62ee5bd3713b182cf10416188bf29da0dbc2936d397aab7.jpg)

![45323d4073537df40070f7a31cbea138d2ac341de0b83156f927fde57987bb88.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/45323d4073537df40070f7a31cbea138d2ac341de0b83156f927fde57987bb88.jpg)

![4977e07ea51f04cf4bc8d7f5f2a0be8540926af614d0a8dde6d696a71a3fef13.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/4977e07ea51f04cf4bc8d7f5f2a0be8540926af614d0a8dde6d696a71a3fef13.jpg)

![5134c2ecd7d041f4483a885d44f9a1a5f8fc2357b3992658fb5f066c0dac8e3c.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/5134c2ecd7d041f4483a885d44f9a1a5f8fc2357b3992658fb5f066c0dac8e3c.jpg)

![600bf270604ba5299c2ce38e0231e002075ab720e852f59bd72cbb47b4bc30ac.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/600bf270604ba5299c2ce38e0231e002075ab720e852f59bd72cbb47b4bc30ac.jpg)

![721d3d5fc7551ae11f64a838636ada73c634488ca67d3d3bbaec2b4f71c77e21.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/721d3d5fc7551ae11f64a838636ada73c634488ca67d3d3bbaec2b4f71c77e21.jpg)

![7863ccf8abcbbce19e13b71cc751f1302f92da45c8ca4bc87ac2aaee20fe420a.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/7863ccf8abcbbce19e13b71cc751f1302f92da45c8ca4bc87ac2aaee20fe420a.jpg)

![854a00d732dc52c9ad2a9d67c886bac68cd729e54bfafb8672947318fdc35e23.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/854a00d732dc52c9ad2a9d67c886bac68cd729e54bfafb8672947318fdc35e23.jpg)

![9e7dcc001d3464e084fe278c8b1eeed10c8c04f7b692dca29255a2cf33586705.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/9e7dcc001d3464e084fe278c8b1eeed10c8c04f7b692dca29255a2cf33586705.jpg)

![a942da59314964b1e3c5e22e549582cfc5aad6d799ab07b9ab1456ead8b4b052.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/a942da59314964b1e3c5e22e549582cfc5aad6d799ab07b9ab1456ead8b4b052.jpg)

![b0d88035306fb361083a4591ca9193c073c74fd5e18d3cc3d2a4045779814074.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/b0d88035306fb361083a4591ca9193c073c74fd5e18d3cc3d2a4045779814074.jpg)

![b145b34c6a6d6c39573e3e5cfc9ee0d15004c1b7aa0456a876134169828b6b5b.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/b145b34c6a6d6c39573e3e5cfc9ee0d15004c1b7aa0456a876134169828b6b5b.jpg)

![c751b44694615aced4c4a72f0078327a724ebebb8173e3947bcd2285b74ee67f.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/c751b44694615aced4c4a72f0078327a724ebebb8173e3947bcd2285b74ee67f.jpg)

![d5409c668c8754961b9c2c12b58eb1cee086973eac867a2022b3ff424025b41c.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/d5409c668c8754961b9c2c12b58eb1cee086973eac867a2022b3ff424025b41c.jpg)

![fc08ebd95b1c06cba3e521069f22c5a7a674ca2db150668105ed31af4c46a1a0.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/images/fc08ebd95b1c06cba3e521069f22c5a7a674ca2db150668105ed31af4c46a1a0.jpg)

### Tables

![1d33275aaedb8603cbfd4cc800770a1d5e6688da93eb594e2921d7be1e7a3e82.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/1d33275aaedb8603cbfd4cc800770a1d5e6688da93eb594e2921d7be1e7a3e82.jpg)

![1d3efe06f2c93357ab36c556cbac8b42b709416f386c23c331d5bbfabc98fdc2.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/1d3efe06f2c93357ab36c556cbac8b42b709416f386c23c331d5bbfabc98fdc2.jpg)

![21e310a14624b9ea3e264989e2294714e9e3476107667fa084e5c51475544f46.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/21e310a14624b9ea3e264989e2294714e9e3476107667fa084e5c51475544f46.jpg)

![22ab25f19090196e450f0bf98076d241321cd9eddba6d10a59dbe4d2ee3b4836.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/22ab25f19090196e450f0bf98076d241321cd9eddba6d10a59dbe4d2ee3b4836.jpg)

![240a074f043628a7c48bfb0ee95191021c6200da55222038e37ae68efec066c2.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/240a074f043628a7c48bfb0ee95191021c6200da55222038e37ae68efec066c2.jpg)

![25b3e5b58ecfceb3a6d1930e1d347d492bb7f4a80fcfc208595c879c12d0d4a9.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/25b3e5b58ecfceb3a6d1930e1d347d492bb7f4a80fcfc208595c879c12d0d4a9.jpg)

![2bd231041ed698123fd2b1830b5d76a983882e23b98751ffcfb11f36c8d4a801.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/2bd231041ed698123fd2b1830b5d76a983882e23b98751ffcfb11f36c8d4a801.jpg)

![3785578b60a08735667d9b7e3b1b2ac090f4425c6f36dc5a80c763ed106a71bc.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/3785578b60a08735667d9b7e3b1b2ac090f4425c6f36dc5a80c763ed106a71bc.jpg)

![4eb8fbeb288fa981e384a575d2b42907a50cfd574fea1f7c5ad5392727177bc8.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/4eb8fbeb288fa981e384a575d2b42907a50cfd574fea1f7c5ad5392727177bc8.jpg)

![4ee08fa8cce83eebc8ed8351c17c06c5634f6f6784d3102c630460d2104b7da9.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/4ee08fa8cce83eebc8ed8351c17c06c5634f6f6784d3102c630460d2104b7da9.jpg)

![551ba5e41b83bd7ffd9d88d2e0c7366cfee1f1e19a096c6bfb985ecbdcf0f00b.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/551ba5e41b83bd7ffd9d88d2e0c7366cfee1f1e19a096c6bfb985ecbdcf0f00b.jpg)

![7bacd6976135de8f19423428bdf7f04b7387bfb40f5a257fb5b819e954513789.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/7bacd6976135de8f19423428bdf7f04b7387bfb40f5a257fb5b819e954513789.jpg)

![8db01650030d246142584d09107c0168641eb43cf1344797c3192952a8857649.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/8db01650030d246142584d09107c0168641eb43cf1344797c3192952a8857649.jpg)

![91833b6ba331221e9aa857e7614a3ecdc35572d864cc903626871ac6c79d4eae.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/91833b6ba331221e9aa857e7614a3ecdc35572d864cc903626871ac6c79d4eae.jpg)

![ae6d5a79e074c16153921ca0931989b5d829e26f8c2c521e16392b03b9e261bc.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/ae6d5a79e074c16153921ca0931989b5d829e26f8c2c521e16392b03b9e261bc.jpg)

![b97646015c8967d25c89dd8ef2afcfe692d77e3ef3adeede778241236f7c780d.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/b97646015c8967d25c89dd8ef2afcfe692d77e3ef3adeede778241236f7c780d.jpg)

![c91ba94c839106bf1ec09ae72db0dc4ed3930000f29dabf25345d3034db2ff88.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/c91ba94c839106bf1ec09ae72db0dc4ed3930000f29dabf25345d3034db2ff88.jpg)

![caa782e984656e9f654b4d7b562310585c86590b12c20eb03b68556b1635e8b1.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/caa782e984656e9f654b4d7b562310585c86590b12c20eb03b68556b1635e8b1.jpg)

![cc3e84161f9e8693c2636407b494638e88271661d7af7387f91dc0e4e68148ba.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/cc3e84161f9e8693c2636407b494638e88271661d7af7387f91dc0e4e68148ba.jpg)

![d70f51315bdc5edc75e5d448ff3f47f20f26a762b3a25113849563a96a656a4f.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/d70f51315bdc5edc75e5d448ff3f47f20f26a762b3a25113849563a96a656a4f.jpg)

![e68a7475afa5cd18dc428e5fbf643356cd69868fb17e9d17b726df4eaadfef36.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/e68a7475afa5cd18dc428e5fbf643356cd69868fb17e9d17b726df4eaadfef36.jpg)

![ee61fcef68912e5f5468eae5b5907db0d623b28ee41b881acbcd94a1de438b68.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/ee61fcef68912e5f5468eae5b5907db0d623b28ee41b881acbcd94a1de438b68.jpg)

![ef0c60ce071291e9cdbeddd46d17a5ff060a1e77fbd7c788752d7f6f122ddb6e.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/ef0c60ce071291e9cdbeddd46d17a5ff060a1e77fbd7c788752d7f6f122ddb6e.jpg)

![fb9318008ca341ee236b1540819c5528c5460bc8097759bf150ef4a366eaf899.jpg](../nips_results/5095_Beyond%20Single-Task_%20Robust%20Multi-Task%20Length%20Generalization%20for%20LLMs/tables/fb9318008ca341ee236b1540819c5528c5460bc8097759bf150ef4a366eaf899.jpg)

## Beyond Least Squares: Uniform Approximation and the Hidden Cost of Misspecification


### Images

![9ba9559c6895d00c3fd913ac04672bca2079d06d46bd56229d1307295f462fd7.jpg](../nips_results/5096_Beyond%20Least%20Squares_%20Uniform%20Approximation%20and%20the%20Hidden%20Cost%20of%20Misspecification/images/9ba9559c6895d00c3fd913ac04672bca2079d06d46bd56229d1307295f462fd7.jpg)

### Tables

![4f64477c0a63d1cc58192be345a5ac034ea6ba3fbd29e78aebbd8e6e58bbd653.jpg](../nips_results/5096_Beyond%20Least%20Squares_%20Uniform%20Approximation%20and%20the%20Hidden%20Cost%20of%20Misspecification/tables/4f64477c0a63d1cc58192be345a5ac034ea6ba3fbd29e78aebbd8e6e58bbd653.jpg)

## Data Efficient Adaptation in Large Language Models via Continuous Low-Rank Fine-Tuning


### Images

![379260ce1eda5b0d464488094b27de47537e86308ecfb30a5709396c9918b85f.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/images/379260ce1eda5b0d464488094b27de47537e86308ecfb30a5709396c9918b85f.jpg)

![b157744a3bb7c73c136ff3dedf4a15e4cddf552e7aceb9c9617ce8d6c6d8c7ff.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/images/b157744a3bb7c73c136ff3dedf4a15e4cddf552e7aceb9c9617ce8d6c6d8c7ff.jpg)

### Tables

![029e32193b87555fdce37508a3a9904c22d14e38b1a6e31e167e04fe02c522a0.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/tables/029e32193b87555fdce37508a3a9904c22d14e38b1a6e31e167e04fe02c522a0.jpg)

![4320411e3cb63d0452f553971c521c6e7542596b86f287b1825ec389b42a8803.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/tables/4320411e3cb63d0452f553971c521c6e7542596b86f287b1825ec389b42a8803.jpg)

![5e6bd122616dc568f883cf1201707be09b78e7e9e4ee5e5f00bc1b6d9c3b24b9.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/tables/5e6bd122616dc568f883cf1201707be09b78e7e9e4ee5e5f00bc1b6d9c3b24b9.jpg)

![7c6b2475e3028c8190ed47e2e5720cb87601080129d3c53d9186675fc12e9e17.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/tables/7c6b2475e3028c8190ed47e2e5720cb87601080129d3c53d9186675fc12e9e17.jpg)

![949cc3b81f12cb93c6fd7ec197397dd452b101d4f54627059a1c1316b89cf581.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/tables/949cc3b81f12cb93c6fd7ec197397dd452b101d4f54627059a1c1316b89cf581.jpg)

![9504d7fb79486637bbdc37a9903364bd4dffeeda569b9ea5e61b66b0cbae1f6a.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/tables/9504d7fb79486637bbdc37a9903364bd4dffeeda569b9ea5e61b66b0cbae1f6a.jpg)

![b3445785ae92df06ab8c5e55f38d566757f7a4c44c3a1947395aec26e5a2a017.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/tables/b3445785ae92df06ab8c5e55f38d566757f7a4c44c3a1947395aec26e5a2a017.jpg)

![be31a8e97f4797533538b41fea40e77af9298807baaf4fba5dbabfefa2c397c5.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/tables/be31a8e97f4797533538b41fea40e77af9298807baaf4fba5dbabfefa2c397c5.jpg)

![c466a8f9c403977fce4077ee0708d0f5fd3fbe7f1069afe8247ff6af6c41a33d.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/tables/c466a8f9c403977fce4077ee0708d0f5fd3fbe7f1069afe8247ff6af6c41a33d.jpg)

![e4b83df622ab9a964498968c555d07a4831cc3546ab1ca9bdf0e74d5940130bf.jpg](../nips_results/5097_Data%20Efficient%20Adaptation%20in%20Large%20Language%20Models%20via%20Continuous%20Low-Rank%20Fine-Tuning/tables/e4b83df622ab9a964498968c555d07a4831cc3546ab1ca9bdf0e74d5940130bf.jpg)

## Unsupervised Trajectory Optimization for 3D Registration in Serial Section Electron Microscopy using Neural ODEs


### Images

![04a15f3b59318ddb8730312b26b1c43009959dd59e4ce2917e081e0be3295e56.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/04a15f3b59318ddb8730312b26b1c43009959dd59e4ce2917e081e0be3295e56.jpg)

![0df30ea0c486e5159d6606232011a73255912643b8d7871aec7aba157bd21cd2.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/0df30ea0c486e5159d6606232011a73255912643b8d7871aec7aba157bd21cd2.jpg)

![16375fd226d2dad914968f025031cfda21d17871a9ddee6a661c1ee9a936750a.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/16375fd226d2dad914968f025031cfda21d17871a9ddee6a661c1ee9a936750a.jpg)

![20af321f8243b7d954041ab0f5f72d0f0ec27e34022bddd82c4335a7228f0e27.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/20af321f8243b7d954041ab0f5f72d0f0ec27e34022bddd82c4335a7228f0e27.jpg)

![35909d0765afbc2fbd87105b1bc6cc30c9544b5637d3b29d30925e244000efda.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/35909d0765afbc2fbd87105b1bc6cc30c9544b5637d3b29d30925e244000efda.jpg)

![44dd37b704a26ba99d17586862b9adb82e1c0de36435addb861a1cf16460aa0b.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/44dd37b704a26ba99d17586862b9adb82e1c0de36435addb861a1cf16460aa0b.jpg)

![4fa76ea9f2f8bc4ecd474c69c9685268c4af4e76bc7b9920c0355e4e38c6309c.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/4fa76ea9f2f8bc4ecd474c69c9685268c4af4e76bc7b9920c0355e4e38c6309c.jpg)

![4ff96dc37da1dcd8c23d21e9ea9f0bfcdc06081ac2c704db3514d26465ef366b.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/4ff96dc37da1dcd8c23d21e9ea9f0bfcdc06081ac2c704db3514d26465ef366b.jpg)

![53a16cd7769e71c970160ef71d7af7cc08ae2f669fad15d71bc35a44c5102125.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/53a16cd7769e71c970160ef71d7af7cc08ae2f669fad15d71bc35a44c5102125.jpg)

![5ae3644304293bdf244b7634f39fba47541450337e85f86507a3e4d143f4e3c2.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/5ae3644304293bdf244b7634f39fba47541450337e85f86507a3e4d143f4e3c2.jpg)

![6019b7acb06db0bbafcabfc9f49bead4796340da9a43c222c09bdef7cd5d48bd.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/6019b7acb06db0bbafcabfc9f49bead4796340da9a43c222c09bdef7cd5d48bd.jpg)

![72fdd466febdd5e364808aa9f730ff46dc987a642677f40def10a60e0d0d68b6.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/72fdd466febdd5e364808aa9f730ff46dc987a642677f40def10a60e0d0d68b6.jpg)

![993623a21d409f7e74288919e6fa5dc6bb2f0f1bef1fdf05f78a1c7d4e8f8c64.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/993623a21d409f7e74288919e6fa5dc6bb2f0f1bef1fdf05f78a1c7d4e8f8c64.jpg)

![ae1b06aa7ac0c52602d2eab8dd039d0b0698bd1258895c97465849347a743754.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/ae1b06aa7ac0c52602d2eab8dd039d0b0698bd1258895c97465849347a743754.jpg)

![c85c6384aa54e61b45f0640050c2067e82316f3206da7f4cc062407ae023858f.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/c85c6384aa54e61b45f0640050c2067e82316f3206da7f4cc062407ae023858f.jpg)

![ce39132c4a54700543a5592db65406a65d08a4b6cdc2eaf1a1d2312599564ed5.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/ce39132c4a54700543a5592db65406a65d08a4b6cdc2eaf1a1d2312599564ed5.jpg)

![d1bf9ec5eae035cecb0728fe83b24d3a221163fdb40d796902a51ac1cc889ef8.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/d1bf9ec5eae035cecb0728fe83b24d3a221163fdb40d796902a51ac1cc889ef8.jpg)

![d85011d0672185dcb45491b90cca20139155e8330ef9bd2605a190d5464baf68.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/d85011d0672185dcb45491b90cca20139155e8330ef9bd2605a190d5464baf68.jpg)

![db24d053dafe96b935569dd62dcd2e67c450ff371f60fd874170c54d5f693430.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/db24d053dafe96b935569dd62dcd2e67c450ff371f60fd874170c54d5f693430.jpg)

![fcd5392576c335166d8be25df2ddd45224ab72ab021202d89ac6b5c2552aedb0.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/images/fcd5392576c335166d8be25df2ddd45224ab72ab021202d89ac6b5c2552aedb0.jpg)

### Tables

![0af8d036e39e15d95c876ef4b9adab9c76a1152549fea20e717ca05356fb1440.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/0af8d036e39e15d95c876ef4b9adab9c76a1152549fea20e717ca05356fb1440.jpg)

![105a9d77be15e80b29ecc05c53ef1e47a9561532e8d9b17ab9e56f93ea4f5d10.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/105a9d77be15e80b29ecc05c53ef1e47a9561532e8d9b17ab9e56f93ea4f5d10.jpg)

![4c587556c9b9c0038b7e907d8ccf4dfa6bda523de623ac1879b422e749f64a5a.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/4c587556c9b9c0038b7e907d8ccf4dfa6bda523de623ac1879b422e749f64a5a.jpg)

![4efd7a5b9cdc14b30c2124920738bbde9b2954d5e848e0dec6ae527afede81cf.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/4efd7a5b9cdc14b30c2124920738bbde9b2954d5e848e0dec6ae527afede81cf.jpg)

![4feaa72f26b711d2542cdcb1a92f50ad078906ccb185d3cf1602d8bcde615a46.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/4feaa72f26b711d2542cdcb1a92f50ad078906ccb185d3cf1602d8bcde615a46.jpg)

![7649101fba3b9892521b330c50294376bcc22523106c11de024c2427f64a6049.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/7649101fba3b9892521b330c50294376bcc22523106c11de024c2427f64a6049.jpg)

![7ebf6e16137f8dfd8e97773f76c293ce5bcb738dee9061fe251a406afdc9ae27.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/7ebf6e16137f8dfd8e97773f76c293ce5bcb738dee9061fe251a406afdc9ae27.jpg)

![867c2ac8e6d7a56073aee809de1b20585f1fd998c9154e856223233df8a15a4a.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/867c2ac8e6d7a56073aee809de1b20585f1fd998c9154e856223233df8a15a4a.jpg)

![922030efc1c73f2fcd2692670431c91f7d92a9483bbd3130b884bd0ab2ca7a4e.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/922030efc1c73f2fcd2692670431c91f7d92a9483bbd3130b884bd0ab2ca7a4e.jpg)

![a865a0ec0061b5b40b14e654363faee84c9fee44b38e5937fd0f534f91e072a4.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/a865a0ec0061b5b40b14e654363faee84c9fee44b38e5937fd0f534f91e072a4.jpg)

![b19645cccd2c4f53645fc1aa4980598f2325d0a3d2787ee7bfb3dd27f4b482ed.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/b19645cccd2c4f53645fc1aa4980598f2325d0a3d2787ee7bfb3dd27f4b482ed.jpg)

![b378589cdffa686cf9f4766da5c472e9176d853cbe6534f9842c1a4a8fab6028.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/b378589cdffa686cf9f4766da5c472e9176d853cbe6534f9842c1a4a8fab6028.jpg)

![bef2af1758e79fabd2ad10029924926eb65df62e12bed752bf4f7c5778d67648.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/bef2af1758e79fabd2ad10029924926eb65df62e12bed752bf4f7c5778d67648.jpg)

![c4c5385afad6b4b087180bae291cd43529bf606ce4fa1c233acb4e6c95b4c2fc.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/c4c5385afad6b4b087180bae291cd43529bf606ce4fa1c233acb4e6c95b4c2fc.jpg)

![d57c4832761da4b198552f5d74d0b869f824c6a0c21361c10ddc3eea0d0f0c18.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/d57c4832761da4b198552f5d74d0b869f824c6a0c21361c10ddc3eea0d0f0c18.jpg)

![e9b4273a9d229d70e35a7297e8f6d2e0c10da0a4705e9cf118df7c5344c79042.jpg](../nips_results/5098_Unsupervised%20Trajectory%20Optimization%20for%203D%20Registration%20in%20Serial%20Section%20Electron%20Microscopy%20using/tables/e9b4273a9d229d70e35a7297e8f6d2e0c10da0a4705e9cf118df7c5344c79042.jpg)

## Reasoning as an Adaptive Defense for Safety


### Images

![04cb984fdc36199ab1e4ff497c162a5753f28615f798cf7985f94c773b055501.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/images/04cb984fdc36199ab1e4ff497c162a5753f28615f798cf7985f94c773b055501.jpg)

![14781a50af9ab246ea4dd280af9d5ab9e664ee02d2fe60b02573caa834e33eb0.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/images/14781a50af9ab246ea4dd280af9d5ab9e664ee02d2fe60b02573caa834e33eb0.jpg)

![31cfa53dc82c8fecec2ff1c484a0e0df238ed061f65a6d167562b27f2b09736a.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/images/31cfa53dc82c8fecec2ff1c484a0e0df238ed061f65a6d167562b27f2b09736a.jpg)

![39925e6a6ef54e2962e1020a9196cdfc73ad40dad11848b04f19a573f7f7149b.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/images/39925e6a6ef54e2962e1020a9196cdfc73ad40dad11848b04f19a573f7f7149b.jpg)

![42c20b230d667f69f8577951ae8498d9b20be72fde7b5a9b2c6cd62f937e83ab.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/images/42c20b230d667f69f8577951ae8498d9b20be72fde7b5a9b2c6cd62f937e83ab.jpg)

![8024b28ab21ce46a202e22be53794242db02e391adb1dcabfc332ad180389d98.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/images/8024b28ab21ce46a202e22be53794242db02e391adb1dcabfc332ad180389d98.jpg)

![8f34b538ade75777e7d4674e37eef63db81ace2d607655f22b38ec5ffd1a79a4.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/images/8f34b538ade75777e7d4674e37eef63db81ace2d607655f22b38ec5ffd1a79a4.jpg)

![9ccba596cbfd8851ed322a17c56f4514f05293fcaac6b7e5f821f18b8a8e6cae.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/images/9ccba596cbfd8851ed322a17c56f4514f05293fcaac6b7e5f821f18b8a8e6cae.jpg)

![d8e8976bfd7eb3d621bb21eb9cbddf00bd74dd70548209847b521d7a9b2d444e.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/images/d8e8976bfd7eb3d621bb21eb9cbddf00bd74dd70548209847b521d7a9b2d444e.jpg)

![f89fc7bf6c33e342ca8da8b35fdf466805b4a46c3382fc2db015fa98dc8086a8.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/images/f89fc7bf6c33e342ca8da8b35fdf466805b4a46c3382fc2db015fa98dc8086a8.jpg)

### Tables

![03f6d21e007b60fc1377e667f3b05c0f7498f0c61ad8d3d5e973165834d2ae83.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/tables/03f6d21e007b60fc1377e667f3b05c0f7498f0c61ad8d3d5e973165834d2ae83.jpg)

![37826ea1b234ba1c4c61b6ae6134cb94384cc178727ec05a9ddf4894dc02351e.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/tables/37826ea1b234ba1c4c61b6ae6134cb94384cc178727ec05a9ddf4894dc02351e.jpg)

![5214a9917e2c4ee5c7854fd84b280f08795db1556e60ea7b4c5c9595c15610c0.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/tables/5214a9917e2c4ee5c7854fd84b280f08795db1556e60ea7b4c5c9595c15610c0.jpg)

![5f5e2c48519725d97ac7e3ae86eb36ec036fcf192e73a803ca57ea8c50ef1504.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/tables/5f5e2c48519725d97ac7e3ae86eb36ec036fcf192e73a803ca57ea8c50ef1504.jpg)

![68ceb8a893cbce346154e6ac62d13d30076331fd91e22b8b0993cf8e55d10831.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/tables/68ceb8a893cbce346154e6ac62d13d30076331fd91e22b8b0993cf8e55d10831.jpg)

![bf84f262ed02f3f4019183e7060c143841221582a4b1dc1dd1a87df64e8550c1.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/tables/bf84f262ed02f3f4019183e7060c143841221582a4b1dc1dd1a87df64e8550c1.jpg)

![c7123e77336cb0245cc8a3fe2b2a88467e63d1c17252fa85dede2039cdd5cd87.jpg](../nips_results/5099_Reasoning%20as%20an%20Adaptive%20Defense%20for%20Safety/tables/c7123e77336cb0245cc8a3fe2b2a88467e63d1c17252fa85dede2039cdd5cd87.jpg)

## CoUn: Empowering Machine Unlearning via Contrastive Learning

### Images

![16ef0da85b2436a2782b03750c69d7e75852f4e0c4346802409ea758f0cee46c.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/images/16ef0da85b2436a2782b03750c69d7e75852f4e0c4346802409ea758f0cee46c.jpg)

![5070b8e9ce497036be4ddf14827ef4eb05b6455be4ce81af74c1c895485bd56b.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/images/5070b8e9ce497036be4ddf14827ef4eb05b6455be4ce81af74c1c895485bd56b.jpg)

![54186c4a27296e274a3d3ade8a2a1eee46cac2ebeabe07d9e9b57bdf981bcc98.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/images/54186c4a27296e274a3d3ade8a2a1eee46cac2ebeabe07d9e9b57bdf981bcc98.jpg)

![5592f39d2b78d63ddf27b236532a7dd281340d6db627872bf887837ebbe5ba45.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/images/5592f39d2b78d63ddf27b236532a7dd281340d6db627872bf887837ebbe5ba45.jpg)

![570dacbce832f06d30342a38f821e93bbe9af416296a7cc8e948daa4c06a2b53.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/images/570dacbce832f06d30342a38f821e93bbe9af416296a7cc8e948daa4c06a2b53.jpg)

![6c372d241f5dadac4a5005ff58ede73af2f309765fce143e45df3708c8786542.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/images/6c372d241f5dadac4a5005ff58ede73af2f309765fce143e45df3708c8786542.jpg)

![748e0c17a9cf7dc95e36b61b8a27c278f737e8ce5d375b525025692e04bb54a8.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/images/748e0c17a9cf7dc95e36b61b8a27c278f737e8ce5d375b525025692e04bb54a8.jpg)

![79eaaa8368f76b975f7251ed064f680655df96def78323f1996259a3f63ced09.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/images/79eaaa8368f76b975f7251ed064f680655df96def78323f1996259a3f63ced09.jpg)

![c85db8468340629806d275dbf59c828918799a3f0938a17bcd9fc8408ceb9447.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/images/c85db8468340629806d275dbf59c828918799a3f0938a17bcd9fc8408ceb9447.jpg)

![d7e5c07f00300d57a640f5111d05a90972547b53b4ec997ea9ac03591815960e.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/images/d7e5c07f00300d57a640f5111d05a90972547b53b4ec997ea9ac03591815960e.jpg)

![fb9155aaa4fc7a5ec4a7765cc8e0e48d5bffa3708d00b9492c637b53712c50ae.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/images/fb9155aaa4fc7a5ec4a7765cc8e0e48d5bffa3708d00b9492c637b53712c50ae.jpg)

### Tables

![38f338349a80743dcffffa0328dff7fa4e6b91e6b5b0917c9d7b7be079862491.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/tables/38f338349a80743dcffffa0328dff7fa4e6b91e6b5b0917c9d7b7be079862491.jpg)

![5ff939067ba359fed13f3ab8f464efd662cb6ed82f94d3878ce4582b2e1bb374.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/tables/5ff939067ba359fed13f3ab8f464efd662cb6ed82f94d3878ce4582b2e1bb374.jpg)

![7a40cada6eedaf40bcad73b018cbd4385a54c260a611f1ba37593a34c276f84b.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/tables/7a40cada6eedaf40bcad73b018cbd4385a54c260a611f1ba37593a34c276f84b.jpg)

![7cce156479175a74bd731023921efe39f73bf23f387084a7ed5643406854672f.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/tables/7cce156479175a74bd731023921efe39f73bf23f387084a7ed5643406854672f.jpg)

![9535fe7aff673982e2ab014106ad0b8675c0784888bda39e0a29b74141afc371.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/tables/9535fe7aff673982e2ab014106ad0b8675c0784888bda39e0a29b74141afc371.jpg)

![977d782cd803d8dde550f90a9e397ac24c3aecfb25c4bf06aebfa3a0049e8b24.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/tables/977d782cd803d8dde550f90a9e397ac24c3aecfb25c4bf06aebfa3a0049e8b24.jpg)

![a47d06d7ff2905763870eb2e661d1b470b96e8f8468ae80e414857da3a5e02f1.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/tables/a47d06d7ff2905763870eb2e661d1b470b96e8f8468ae80e414857da3a5e02f1.jpg)

![b8d409ef848f550be9d81fda33dc3c0ee242ad2cae8f0df1487473c942879012.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/tables/b8d409ef848f550be9d81fda33dc3c0ee242ad2cae8f0df1487473c942879012.jpg)

![ca75068e16169a9b4e19c08953eea48520881a002cb9b5e91983ed82631cf970.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/tables/ca75068e16169a9b4e19c08953eea48520881a002cb9b5e91983ed82631cf970.jpg)

![d8bd52799ca01cecbdb1e42ca7e1077a939a48428e3499167d52e3f3631e15ef.jpg](../nips_results/5100_CoUn_%20Empowering%20Machine%20Unlearning%20via%20Contrastive%20Learning/tables/d8bd52799ca01cecbdb1e42ca7e1077a939a48428e3499167d52e3f3631e15ef.jpg)
