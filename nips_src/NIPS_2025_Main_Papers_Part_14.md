# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 14 of 130

## 目录 (Table of Contents)

1. [Towards Multi-Table Learning: A Novel Paradigm for Complementarity Quantification and Integration](#Towards-Multi-Table-Learning-A-Novel-Paradigm-for-Complementarity-Quantification-and-Integration)
2. [Flattening Hierarchies with Policy Bootstrapping](#Flattening-Hierarchies-with-Policy-Bootstrapping)
3. [Fixed-Point RNNs: Interpolating from Diagonal to Dense](#Fixed-Point-RNNs-Interpolating-from-Diagonal-to-Dense)
4. [Proxy-SPEX: Sample-Efficient Interpretability via Sparse Feature Interactions in LLMs](#Proxy-SPEX-Sample-Efficient-Interpretability-via-Sparse-Feature-Interactions-in-LLMs)
5. [Angles Don’t Lie: Unlocking Training‑Efficient RL Through the Model’s Own Signals](#Angles-Dont-Lie-Unlocking-TrainingEfficient-RL-Through-the-Models-Own-Signals)
6. [Instance-Optimality for Private KL Distribution Estimation](#Instance-Optimality-for-Private-KL-Distribution-Estimation)
7. [Flow Density Control: Generative Optimization Beyond Entropy-Regularized Fine-Tuning](#Flow-Density-Control-Generative-Optimization-Beyond-Entropy-Regularized-Fine-Tuning)
8. [DNAEdit: Direct Noise Alignment for Text-Guided Rectified Flow Editing](#DNAEdit-Direct-Noise-Alignment-for-Text-Guided-Rectified-Flow-Editing)
9. [Diffusion Generative Modeling on Lie Group Representations](#Diffusion-Generative-Modeling-on-Lie-Group-Representations)
10. [Ctrl-DNA: Controllable Cell-Type-Specific Regulatory DNA Design via Constrained RL](#Ctrl-DNA-Controllable-Cell-Type-Specific-Regulatory-DNA-Design-via-Constrained-RL)
11. [HM3: Hierarchical Multi-Objective Model Merging for Pretrained Models](#HM3-Hierarchical-Multi-Objective-Model-Merging-for-Pretrained-Models)
12. [SageAttention3: Microscaling FP4 Attention for Inference and An Exploration of 8-Bit Training](#SageAttention3-Microscaling-FP4-Attention-for-Inference-and-An-Exploration-of-8-Bit-Training)
13. [Fast Monte Carlo Tree Diffusion: 100× Speedup via Parallel and Sparse Planning](#Fast-Monte-Carlo-Tree-Diffusion-100-Speedup-via-Parallel-and-Sparse-Planning)
14. [Transstratal Adversarial Attack: Compromising Multi-Layered Defenses in Text-to-Image Models](#Transstratal-Adversarial-Attack-Compromising-Multi-Layered-Defenses-in-Text-to-Image-Models)
15. [Frame Context Packing and Drift Prevention in Next-Frame-Prediction Video Diffusion Models](#Frame-Context-Packing-and-Drift-Prevention-in-Next-Frame-Prediction-Video-Diffusion-Models)
16. [Multi-agent Markov Entanglement](#Multi-agent-Markov-Entanglement)
17. [On the sample complexity of semi-supervised multi-objective learning](#On-the-sample-complexity-of-semi-supervised-multi-objective-learning)
18. [LODGE: Level-of-Detail Large-Scale Gaussian Splatting with Efficient Rendering](#LODGE-Level-of-Detail-Large-Scale-Gaussian-Splatting-with-Efficient-Rendering)
19. [Quantum speedup of non-linear Monte Carlo problems](#Quantum-speedup-of-non-linear-Monte-Carlo-problems)
20. [On Transferring Transferability: Towards a Theory for Size Generalization](#On-Transferring-Transferability-Towards-a-Theory-for-Size-Generalization)
21. [BevSplat: Resolving Height Ambiguity via Feature-Based Gaussian Primitives for Weakly-Supervised Cross-View Localization](#BevSplat-Resolving-Height-Ambiguity-via-Feature-Based-Gaussian-Primitives-for-Weakly-Supervised-Cross-View-Localization)
22. [Error Broadcast and Decorrelation as a Potential Artificial and Natural Learning Mechanism](#Error-Broadcast-and-Decorrelation-as-a-Potential-Artificial-and-Natural-Learning-Mechanism)
23. [Two‑Stage Learning of Stabilizing Neural Controllers via Zubov Sampling and Iterative Domain Expansion](#TwoStage-Learning-of-Stabilizing-Neural-Controllers-via-Zubov-Sampling-and-Iterative-Domain-Expansion)
24. [AlphaZero Neural Scaling and Zipf's Law: a Tale of Board Games and Power Laws](#AlphaZero-Neural-Scaling-and-Zipfs-Law-a-Tale-of-Board-Games-and-Power-Laws)
25. [Adaptive 3D Reconstruction via Diffusion Priors and Forward Curvature-Matching Likelihood Updates](#Adaptive-3D-Reconstruction-via-Diffusion-Priors-and-Forward-Curvature-Matching-Likelihood-Updates)
26. [Stable Part Diffusion 4D: Multi-View RGB and Kinematic Parts Video Generation](#Stable-Part-Diffusion-4D-Multi-View-RGB-and-Kinematic-Parts-Video-Generation)
27. [Chain-of-Zoom: Extreme Super-Resolution via Scale Autoregression and Preference Alignment](#Chain-of-Zoom-Extreme-Super-Resolution-via-Scale-Autoregression-and-Preference-Alignment)
28. [Characterizing control between interacting subsystems with deep Jacobian estimation](#Characterizing-control-between-interacting-subsystems-with-deep-Jacobian-estimation)
29. [Fast and Fluent Diffusion Language Models via Convolutional Decoding and Rejective Fine-tuning](#Fast-and-Fluent-Diffusion-Language-Models-via-Convolutional-Decoding-and-Rejective-Fine-tuning)
30. [Physics-Driven Spatiotemporal Modeling for AI-Generated Video Detection](#Physics-Driven-Spatiotemporal-Modeling-for-AI-Generated-Video-Detection)
31. [Stable Minima of ReLU Neural Networks Suffer from the Curse of Dimensionality: The Neural Shattering Phenomenon](#Stable-Minima-of-ReLU-Neural-Networks-Suffer-from-the-Curse-of-Dimensionality-The-Neural-Shattering-Phenomenon)
32. [Structured Linear CDEs: Maximally Expressive and Parallel-in-Time Sequence Models](#Structured-Linear-CDEs-Maximally-Expressive-and-Parallel-in-Time-Sequence-Models)
33. [Hybrid-Balance GFlowNet for Solving Vehicle Routing Problems](#Hybrid-Balance-GFlowNet-for-Solving-Vehicle-Routing-Problems)
34. [A Principled Path to Fitted Distributional Evaluation](#A-Principled-Path-to-Fitted-Distributional-Evaluation)
35. [SIU3R: Simultaneous Scene Understanding and 3D Reconstruction Beyond Feature Alignment](#SIU3R-Simultaneous-Scene-Understanding-and-3D-Reconstruction-Beyond-Feature-Alignment)
36. [SORTeD Rashomon Sets of Sparse Decision Trees: Anytime Enumeration](#SORTeD-Rashomon-Sets-of-Sparse-Decision-Trees-Anytime-Enumeration)
37. [ElliCE: Efficient and Provably Robust Algorithmic Recourse via the Rashomon Sets](#ElliCE-Efficient-and-Provably-Robust-Algorithmic-Recourse-via-the-Rashomon-Sets)
38. [Web-Shepherd: Advancing PRMs for Reinforcing Web Agents](#Web-Shepherd-Advancing-PRMs-for-Reinforcing-Web-Agents)
39. [SimWorld: An Open-ended Simulator for Agents in Physical and Social Worlds](#SimWorld-An-Open-ended-Simulator-for-Agents-in-Physical-and-Social-Worlds)
40. [A learnability analysis on neuro-symbolic learning](#A-learnability-analysis-on-neuro-symbolic-learning)
41. [Audio Flamingo 3: Advancing Audio Intelligence with Fully Open Large Audio Language Models](#Audio-Flamingo-3-Advancing-Audio-Intelligence-with-Fully-Open-Large-Audio-Language-Models)

---


## Towards Multi-Table Learning: A Novel Paradigm for Complementarity Quantification and Integration

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

## Towards Multi-Table Learning: A Novel Paradigm for Complementarity Quantification and Integration


### Images

![65625dec940a02bdd37bf66126b65435bb82dfe0b050acf9548b1d5f3d005362.jpg](../nips_results/546_Towards%20Multi-Table%20Learning_%20A%20Novel%20Paradigm%20for%20Complementarity%20Quantification%20and%20Integration/images/65625dec940a02bdd37bf66126b65435bb82dfe0b050acf9548b1d5f3d005362.jpg)

![8e87bd3293a142fd65f94eb4a32477391a6d43c888a31cd3fb36e18300516c1d.jpg](../nips_results/546_Towards%20Multi-Table%20Learning_%20A%20Novel%20Paradigm%20for%20Complementarity%20Quantification%20and%20Integration/images/8e87bd3293a142fd65f94eb4a32477391a6d43c888a31cd3fb36e18300516c1d.jpg)

### Tables

![04f30638284230443387b80b90607411746c31c70f47afca942d5c388193af0c.jpg](../nips_results/546_Towards%20Multi-Table%20Learning_%20A%20Novel%20Paradigm%20for%20Complementarity%20Quantification%20and%20Integration/tables/04f30638284230443387b80b90607411746c31c70f47afca942d5c388193af0c.jpg)

![80b700e75595690efcc6b8aa9ac82e915f66739df0f61bf7451d28f54164425d.jpg](../nips_results/546_Towards%20Multi-Table%20Learning_%20A%20Novel%20Paradigm%20for%20Complementarity%20Quantification%20and%20Integration/tables/80b700e75595690efcc6b8aa9ac82e915f66739df0f61bf7451d28f54164425d.jpg)

![81ccfe5d0a279e10bbc5a8a5d09ddce37aa25436307b3308ce3071b278014ba9.jpg](../nips_results/546_Towards%20Multi-Table%20Learning_%20A%20Novel%20Paradigm%20for%20Complementarity%20Quantification%20and%20Integration/tables/81ccfe5d0a279e10bbc5a8a5d09ddce37aa25436307b3308ce3071b278014ba9.jpg)

![835f98da1d421cab07053aaacb9587aaefe101a0911c3938c936f65888363f73.jpg](../nips_results/546_Towards%20Multi-Table%20Learning_%20A%20Novel%20Paradigm%20for%20Complementarity%20Quantification%20and%20Integration/tables/835f98da1d421cab07053aaacb9587aaefe101a0911c3938c936f65888363f73.jpg)

![a975cfaf3fbdb81f19be83ab9a77f619c6d3c0ce24121aabbecbf1f569824206.jpg](../nips_results/546_Towards%20Multi-Table%20Learning_%20A%20Novel%20Paradigm%20for%20Complementarity%20Quantification%20and%20Integration/tables/a975cfaf3fbdb81f19be83ab9a77f619c6d3c0ce24121aabbecbf1f569824206.jpg)

![ceec2737d73de1b1e155aed706f0e815fc2a85ec043c902db7a15c576cc45d2a.jpg](../nips_results/546_Towards%20Multi-Table%20Learning_%20A%20Novel%20Paradigm%20for%20Complementarity%20Quantification%20and%20Integration/tables/ceec2737d73de1b1e155aed706f0e815fc2a85ec043c902db7a15c576cc45d2a.jpg)

![d8abf9ed0a86d304f33651a43df04ed4074a5ad976b24327f1c416b61605be97.jpg](../nips_results/546_Towards%20Multi-Table%20Learning_%20A%20Novel%20Paradigm%20for%20Complementarity%20Quantification%20and%20Integration/tables/d8abf9ed0a86d304f33651a43df04ed4074a5ad976b24327f1c416b61605be97.jpg)

![f59ba4cb987be7d850f2792966dab3c0247124e89e18f499452ff957f228f461.jpg](../nips_results/546_Towards%20Multi-Table%20Learning_%20A%20Novel%20Paradigm%20for%20Complementarity%20Quantification%20and%20Integration/tables/f59ba4cb987be7d850f2792966dab3c0247124e89e18f499452ff957f228f461.jpg)

![f5a70cbb25acb065ea31ebb344b4c4adc3a8b5d5676c8189eb6d5d8a51abf524.jpg](../nips_results/546_Towards%20Multi-Table%20Learning_%20A%20Novel%20Paradigm%20for%20Complementarity%20Quantification%20and%20Integration/tables/f5a70cbb25acb065ea31ebb344b4c4adc3a8b5d5676c8189eb6d5d8a51abf524.jpg)

## Flattening Hierarchies with Policy Bootstrapping


### Images

![24bd99113db5d9046a5e700d927587a487acfe79952b92568a8203dc041b16f2.jpg](../nips_results/547_Flattening%20Hierarchies%20with%20Policy%20Bootstrapping/images/24bd99113db5d9046a5e700d927587a487acfe79952b92568a8203dc041b16f2.jpg)

![2ce760fd9aee9037d123df663f2f024cc24d88fac9604b94949f85dac9814a8b.jpg](../nips_results/547_Flattening%20Hierarchies%20with%20Policy%20Bootstrapping/images/2ce760fd9aee9037d123df663f2f024cc24d88fac9604b94949f85dac9814a8b.jpg)

![3122b798519fcb26e19316540f7306742ed8a276d2ce6728b62a4c26df3f7d73.jpg](../nips_results/547_Flattening%20Hierarchies%20with%20Policy%20Bootstrapping/images/3122b798519fcb26e19316540f7306742ed8a276d2ce6728b62a4c26df3f7d73.jpg)

![8191e1aa04fe61292f6e303e0411e965e86baa80d0ed4ef9314277c0f8646bfa.jpg](../nips_results/547_Flattening%20Hierarchies%20with%20Policy%20Bootstrapping/images/8191e1aa04fe61292f6e303e0411e965e86baa80d0ed4ef9314277c0f8646bfa.jpg)

![8b9889f20e1c9faa2b2107f6060cefead5c87053c75b8b30fc305caea392e418.jpg](../nips_results/547_Flattening%20Hierarchies%20with%20Policy%20Bootstrapping/images/8b9889f20e1c9faa2b2107f6060cefead5c87053c75b8b30fc305caea392e418.jpg)

![b68fef4cd8d230d0c281fffc53ed3aaac06ca901d3527ef58a20a293b3a0a400.jpg](../nips_results/547_Flattening%20Hierarchies%20with%20Policy%20Bootstrapping/images/b68fef4cd8d230d0c281fffc53ed3aaac06ca901d3527ef58a20a293b3a0a400.jpg)

![d63e81e703676b073b00db28e8d74d79620ad61d11d24deae725ebab60fe6dab.jpg](../nips_results/547_Flattening%20Hierarchies%20with%20Policy%20Bootstrapping/images/d63e81e703676b073b00db28e8d74d79620ad61d11d24deae725ebab60fe6dab.jpg)

![ff7211152eaf267f4690639415ef9c721097514dd3e4cd11ee9e8e9f90519671.jpg](../nips_results/547_Flattening%20Hierarchies%20with%20Policy%20Bootstrapping/images/ff7211152eaf267f4690639415ef9c721097514dd3e4cd11ee9e8e9f90519671.jpg)

### Tables

![5feb4493dd89407d843e2d259e873082ec5fffea0c4e6c1d16a054e9d58130dc.jpg](../nips_results/547_Flattening%20Hierarchies%20with%20Policy%20Bootstrapping/tables/5feb4493dd89407d843e2d259e873082ec5fffea0c4e6c1d16a054e9d58130dc.jpg)

![6126017e37ad04a9db731e9e5533e600985a89974c4d06c7d9d0f0f89ad17a08.jpg](../nips_results/547_Flattening%20Hierarchies%20with%20Policy%20Bootstrapping/tables/6126017e37ad04a9db731e9e5533e600985a89974c4d06c7d9d0f0f89ad17a08.jpg)

![ca0591c3b090955fb94443f183617c2a10b95b10b726eb71420ba8c649d77cfa.jpg](../nips_results/547_Flattening%20Hierarchies%20with%20Policy%20Bootstrapping/tables/ca0591c3b090955fb94443f183617c2a10b95b10b726eb71420ba8c649d77cfa.jpg)

## Fixed-Point RNNs: Interpolating from Diagonal to Dense


### Images

![06792e7c0135f57fb739a9e0671d90ca4a2e57fbe556eda5675cd4f193adecc3.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/06792e7c0135f57fb739a9e0671d90ca4a2e57fbe556eda5675cd4f193adecc3.jpg)

![089037f051bca4ebbfbed74b0396dfaab1d54df92ba227441301134ee602363c.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/089037f051bca4ebbfbed74b0396dfaab1d54df92ba227441301134ee602363c.jpg)

![08c6881549835e290db2e7131bb7650dd5f97b27938cee957a3fc91ede41b88f.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/08c6881549835e290db2e7131bb7650dd5f97b27938cee957a3fc91ede41b88f.jpg)

![631783bab2dcd5dd3eaa16a33d5d321777f63bda11be1fbb498520dbb41ca7a7.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/631783bab2dcd5dd3eaa16a33d5d321777f63bda11be1fbb498520dbb41ca7a7.jpg)

![657b0494bb39cefac5313cc0c6f9738b7d2d1235e55532b952bbaa9053148173.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/657b0494bb39cefac5313cc0c6f9738b7d2d1235e55532b952bbaa9053148173.jpg)

![65aac69ef197e52204c391ec70259ff24cf332a8dc4aaeed0eb7c8f24f622ce8.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/65aac69ef197e52204c391ec70259ff24cf332a8dc4aaeed0eb7c8f24f622ce8.jpg)

![7ad6f393fe65f2471a546605edcf75f69eaf8d09bde6313ad46577c32b94282b.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/7ad6f393fe65f2471a546605edcf75f69eaf8d09bde6313ad46577c32b94282b.jpg)

![7b13d6e3ee8099a8458d57fe494df7182ff2024d10fc9ad8e3b21580056a554a.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/7b13d6e3ee8099a8458d57fe494df7182ff2024d10fc9ad8e3b21580056a554a.jpg)

![8d7dc9d894ca5ff0590fc41d240c10938571c1e8fefe660aeaa61f839a773446.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/8d7dc9d894ca5ff0590fc41d240c10938571c1e8fefe660aeaa61f839a773446.jpg)

![c8a24149c7ecef9bfdfb596d3088b5c16975483c8dc0b34029dc570d48faea6c.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/c8a24149c7ecef9bfdfb596d3088b5c16975483c8dc0b34029dc570d48faea6c.jpg)

![ccef63198edbe94f4b90ae65d392e259b1376afb890e0652c499cb0303baafca.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/ccef63198edbe94f4b90ae65d392e259b1376afb890e0652c499cb0303baafca.jpg)

![da20a90573f87c5727724c15c9e0d7d6f724685afb249b785eb27df8de6619e4.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/da20a90573f87c5727724c15c9e0d7d6f724685afb249b785eb27df8de6619e4.jpg)

![dbbd2561d878479c5bcc2977bfcc0119c7cbcaea5772daa5898cee511e089de6.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/images/dbbd2561d878479c5bcc2977bfcc0119c7cbcaea5772daa5898cee511e089de6.jpg)

### Tables

![169c152845c836e6b8a3d6cbe5c2fa40ec66615e6bce69c825d29f6a040841e4.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/tables/169c152845c836e6b8a3d6cbe5c2fa40ec66615e6bce69c825d29f6a040841e4.jpg)

![4afc7b1754cd9d797e0f29d3e74775b5afa55cd5ea4afb2133452cde5aac74fb.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/tables/4afc7b1754cd9d797e0f29d3e74775b5afa55cd5ea4afb2133452cde5aac74fb.jpg)

![a2f515ec97cf05edd22b56200d57c0d73d9459aab7a3e65f56b922b1c22f0335.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/tables/a2f515ec97cf05edd22b56200d57c0d73d9459aab7a3e65f56b922b1c22f0335.jpg)

![cf7609111bfcfde286191f311b58a9d20b0010df04e97be8c19bd33132a6fc67.jpg](../nips_results/548_Fixed-Point%20RNNs_%20Interpolating%20from%20Diagonal%20to%20Dense/tables/cf7609111bfcfde286191f311b58a9d20b0010df04e97be8c19bd33132a6fc67.jpg)

## Proxy-SPEX: Sample-Efficient Interpretability via Sparse Feature Interactions in LLMs


### Images

![0c27d6ff107b63296769bf27cd469d99dbd5884700fa8fce01e4e52405e12d2c.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/0c27d6ff107b63296769bf27cd469d99dbd5884700fa8fce01e4e52405e12d2c.jpg)

![0c4826234127d465df831855583388968b6806540e281ef02b6dd472a8375788.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/0c4826234127d465df831855583388968b6806540e281ef02b6dd472a8375788.jpg)

![15cac5fba0adef8f0c01663eb41ed07466c0c0a6c67e3c4b9be65f91511bca93.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/15cac5fba0adef8f0c01663eb41ed07466c0c0a6c67e3c4b9be65f91511bca93.jpg)

![1d9eab61238b040d629e3fb94027bbf86935620296a64c62c937152fff64a559.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/1d9eab61238b040d629e3fb94027bbf86935620296a64c62c937152fff64a559.jpg)

![241abc17612ead7059916448c39a841a381bbea5d747f7dc9666c83f4b2f76ec.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/241abc17612ead7059916448c39a841a381bbea5d747f7dc9666c83f4b2f76ec.jpg)

![27cbfe0708cf3e407a2958893ceaf68febf55d836f735717070857b9f91f1ae0.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/27cbfe0708cf3e407a2958893ceaf68febf55d836f735717070857b9f91f1ae0.jpg)

![3d07da56881eab759185a39b347bebbdba8da6ea8a98d34fad6234ccbdf5a38b.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/3d07da56881eab759185a39b347bebbdba8da6ea8a98d34fad6234ccbdf5a38b.jpg)

![41c78cc55b02d5a520573c8cd81e90df0d23d49f2e282d8716d604a032847052.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/41c78cc55b02d5a520573c8cd81e90df0d23d49f2e282d8716d604a032847052.jpg)

![4d29c57b825e016dd90bfe46f9a3980807b232f6f824a4334a6a44e174b70b45.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/4d29c57b825e016dd90bfe46f9a3980807b232f6f824a4334a6a44e174b70b45.jpg)

![628b2128fc5a027a2d2cb2c83f6a9df70f59c174966e2b5ad9c53aaa01c7f373.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/628b2128fc5a027a2d2cb2c83f6a9df70f59c174966e2b5ad9c53aaa01c7f373.jpg)

![801b7475d9899b2e0c609ea96cb382c6d533bfd536d2b8b66648b7d852bb4a15.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/801b7475d9899b2e0c609ea96cb382c6d533bfd536d2b8b66648b7d852bb4a15.jpg)

![9fdf73b3bc51e43dda80435e378d5fefda53a825d30a28b158bd716f004d7a15.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/9fdf73b3bc51e43dda80435e378d5fefda53a825d30a28b158bd716f004d7a15.jpg)

![ac1c58a9d6a17ee25f5f7aa7b3f7f0e139b24811c2091daa0ffda94d56d57340.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/ac1c58a9d6a17ee25f5f7aa7b3f7f0e139b24811c2091daa0ffda94d56d57340.jpg)

![bf238a078a60be1abd591ba4d9d51e7ece6d0b611dddba86644f69e30f3c893a.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/bf238a078a60be1abd591ba4d9d51e7ece6d0b611dddba86644f69e30f3c893a.jpg)

![c35415b59e96fb8a07d28879a721713c8954bba1d289cda8e4f919266ce3470c.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/c35415b59e96fb8a07d28879a721713c8954bba1d289cda8e4f919266ce3470c.jpg)

![d94f7bb9c311a9a3333963468f2aa8d579949e947c69b551e82f9d69e25a5884.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/d94f7bb9c311a9a3333963468f2aa8d579949e947c69b551e82f9d69e25a5884.jpg)

![f5ebe31f40035e49d4db7b7f89364de8f97ebc7fa891ed0c4e80446ca7412014.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/images/f5ebe31f40035e49d4db7b7f89364de8f97ebc7fa891ed0c4e80446ca7412014.jpg)

### Tables

![32db65d5f5c8ee9ecb0b098bbdb5a91dadac05c798993d56e259ea98750a23b4.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/tables/32db65d5f5c8ee9ecb0b098bbdb5a91dadac05c798993d56e259ea98750a23b4.jpg)

![62c33d22861460b5f36c4e09f0d3facef07e8ac1f851932df68478fcdff24224.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/tables/62c33d22861460b5f36c4e09f0d3facef07e8ac1f851932df68478fcdff24224.jpg)

![7e1116a490cd02bc9b54b36c689aa8c24ae45ee86977a016d898e7e3678289af.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/tables/7e1116a490cd02bc9b54b36c689aa8c24ae45ee86977a016d898e7e3678289af.jpg)

![a20824279caf3aad07fcecfe609f447d1ef46ab1939d66b90786896c49087849.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/tables/a20824279caf3aad07fcecfe609f447d1ef46ab1939d66b90786896c49087849.jpg)

![f905043c8aeded47cd75d5d9d01607a1048ffdc4908e7e3594d523daaaa1dbf0.jpg](../nips_results/549_Proxy-SPEX_%20Sample-Efficient%20Interpretability%20via%20Sparse%20Feature%20Interactions%20in%20LLMs/tables/f905043c8aeded47cd75d5d9d01607a1048ffdc4908e7e3594d523daaaa1dbf0.jpg)

## Angles Don’t Lie: Unlocking Training‑Efficient RL Through the Model’s Own Signals


### Images

![0aba3321d814f29c69b5ecc8ddee68726ec8443dc7d08c3475f09caee1d058f1.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/0aba3321d814f29c69b5ecc8ddee68726ec8443dc7d08c3475f09caee1d058f1.jpg)

![1ef65ad474299390a2f892dc7ef1b97160d304d8c770415de8dc27712e3d6453.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/1ef65ad474299390a2f892dc7ef1b97160d304d8c770415de8dc27712e3d6453.jpg)

![21c9d4dd47b64ff46d1a62afc5c8801522ca6707293357915e4412a2163ba843.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/21c9d4dd47b64ff46d1a62afc5c8801522ca6707293357915e4412a2163ba843.jpg)

![2de15910d10952f68887c5fae43bdc4b150fd62342092541c77c524af3115347.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/2de15910d10952f68887c5fae43bdc4b150fd62342092541c77c524af3115347.jpg)

![2efbeec90399f185e96b9ec5ccaa5f55c787bbda7a7e7f91a1d2facd445495ce.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/2efbeec90399f185e96b9ec5ccaa5f55c787bbda7a7e7f91a1d2facd445495ce.jpg)

![4376c7e28b508668b680184c5a2297d3a38ece6bbb0f0eb5eb4cae80bd259f69.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/4376c7e28b508668b680184c5a2297d3a38ece6bbb0f0eb5eb4cae80bd259f69.jpg)

![4658d74424af66231030408d69ff8a3fbb413c191ff7e89fc1997784a958b258.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/4658d74424af66231030408d69ff8a3fbb413c191ff7e89fc1997784a958b258.jpg)

![4dc25fb1e0b190e5bba1b7f7d365936eb12574e40bcc6f264a1006975bfc9e18.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/4dc25fb1e0b190e5bba1b7f7d365936eb12574e40bcc6f264a1006975bfc9e18.jpg)

![5dbc2624538537268cb9150badbd572918cb2bc14c36c3d77fe85f56765be3bf.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/5dbc2624538537268cb9150badbd572918cb2bc14c36c3d77fe85f56765be3bf.jpg)

![60924ab2bc9b6880946aa994d8de3f8a273a363f1ad0ed61e406c95490e6e2c6.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/60924ab2bc9b6880946aa994d8de3f8a273a363f1ad0ed61e406c95490e6e2c6.jpg)

![6300a22a21ec24ec73dc65b8201c7339293ee7af6e9f75dacdd80c3f1847f8d2.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/6300a22a21ec24ec73dc65b8201c7339293ee7af6e9f75dacdd80c3f1847f8d2.jpg)

![8a8a6839898b86049cfdbbca90086d8eb8e276ab41dbb757c632cd1b6eb1fc32.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/8a8a6839898b86049cfdbbca90086d8eb8e276ab41dbb757c632cd1b6eb1fc32.jpg)

![8ad396d673c620bfd6bca39b55b57eeb13ffbfacb1037b462bb9002c19b1e8d5.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/8ad396d673c620bfd6bca39b55b57eeb13ffbfacb1037b462bb9002c19b1e8d5.jpg)

![9659c7872948b004ca740fc087cfddcdc0f022f78cf23562bec602ab460fa4f0.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/9659c7872948b004ca740fc087cfddcdc0f022f78cf23562bec602ab460fa4f0.jpg)

![b3f3676c980320fcb6838c4eb241419f69322beaf63ed0884fa0d4e90d685f1b.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/b3f3676c980320fcb6838c4eb241419f69322beaf63ed0884fa0d4e90d685f1b.jpg)

![cd1acef6e53dd9f884cf88624a5e75a1385c817b662add5cef8c3a6ddd355abc.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/cd1acef6e53dd9f884cf88624a5e75a1385c817b662add5cef8c3a6ddd355abc.jpg)

![da94ff2440084ea5c5f1bcc2a160f0b9146cac6ae47d00dde47cb1bc9c36a2a9.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/da94ff2440084ea5c5f1bcc2a160f0b9146cac6ae47d00dde47cb1bc9c36a2a9.jpg)

![e063157f36c716188842364f9bb88e84c723d653fb5ddefad54837ddab2f7159.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/e063157f36c716188842364f9bb88e84c723d653fb5ddefad54837ddab2f7159.jpg)

![ea2f30872eb9925a53a6d74998553b24289aa9889e3c73c4d2207115e722b501.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/images/ea2f30872eb9925a53a6d74998553b24289aa9889e3c73c4d2207115e722b501.jpg)

### Tables

![0d36eb134803bb50c50d33dd156de22be578e3c9e65ca7f3da8572f385649ba2.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/tables/0d36eb134803bb50c50d33dd156de22be578e3c9e65ca7f3da8572f385649ba2.jpg)

![751a4775438980c0dbdb712dcc32b97186cb6df785884ff5d28e41abeec57089.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/tables/751a4775438980c0dbdb712dcc32b97186cb6df785884ff5d28e41abeec57089.jpg)

![865543baaa3dfbcf5cba90b8bd112de95061ac9a1b75cbfad3adc437442e9a3a.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/tables/865543baaa3dfbcf5cba90b8bd112de95061ac9a1b75cbfad3adc437442e9a3a.jpg)

![9745d41cf4a7fe38bae6a916046523c6c3a9300386b150a41796d1588898a1b1.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/tables/9745d41cf4a7fe38bae6a916046523c6c3a9300386b150a41796d1588898a1b1.jpg)

![ecfab2e2a622098bd2e28b0089d4ded4e7ae4b0a93b879f890eda8aabd28b0ab.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/tables/ecfab2e2a622098bd2e28b0089d4ded4e7ae4b0a93b879f890eda8aabd28b0ab.jpg)

![f5c75c0dac742e1e40803422962373ca6c8897f67ea8b23b1f72057310ef4f88.jpg](../nips_results/550_Angles%20Don%E2%80%99t%20Lie_%20Unlocking%20Training%E2%80%91Efficient%20RL%20Through%20the%20Model%E2%80%99s%20Own%20Signals/tables/f5c75c0dac742e1e40803422962373ca6c8897f67ea8b23b1f72057310ef4f88.jpg)

## Instance-Optimality for Private KL Distribution Estimation


### Images

![170f8928b305805aa3b9ce828a899b4896f979de9687ee26102a50d82596d5bc.jpg](../nips_results/552_Instance-Optimality%20for%20Private%20KL%20Distribution%20Estimation/images/170f8928b305805aa3b9ce828a899b4896f979de9687ee26102a50d82596d5bc.jpg)

![20bac6a160e6acfc84cf0d3124737174059473173675470a69d69715f8f48569.jpg](../nips_results/552_Instance-Optimality%20for%20Private%20KL%20Distribution%20Estimation/images/20bac6a160e6acfc84cf0d3124737174059473173675470a69d69715f8f48569.jpg)

![57e2546638b9b2deb8a74233b334b1b01d2d6fa13e599a8d867989e91a81ee07.jpg](../nips_results/552_Instance-Optimality%20for%20Private%20KL%20Distribution%20Estimation/images/57e2546638b9b2deb8a74233b334b1b01d2d6fa13e599a8d867989e91a81ee07.jpg)

![8eedb8dd7bea13fd479c347c4b82743f6b4d135995620fc189cd8ffd78ea4edc.jpg](../nips_results/552_Instance-Optimality%20for%20Private%20KL%20Distribution%20Estimation/images/8eedb8dd7bea13fd479c347c4b82743f6b4d135995620fc189cd8ffd78ea4edc.jpg)

![cd20e7c91d5059c53d87c922e4a3260d1dadae1c8a312e2d098e4bc6f6f6bb7f.jpg](../nips_results/552_Instance-Optimality%20for%20Private%20KL%20Distribution%20Estimation/images/cd20e7c91d5059c53d87c922e4a3260d1dadae1c8a312e2d098e4bc6f6f6bb7f.jpg)

![d45bb58613bbea2996d327c2c7f6a05e67f0bad17fbf95047bc211cc257b54c2.jpg](../nips_results/552_Instance-Optimality%20for%20Private%20KL%20Distribution%20Estimation/images/d45bb58613bbea2996d327c2c7f6a05e67f0bad17fbf95047bc211cc257b54c2.jpg)

### Tables

![30ae6a80db522a1633662768e4ff4fd9d9eaf91fd0aa52802a58160b189681a7.jpg](../nips_results/552_Instance-Optimality%20for%20Private%20KL%20Distribution%20Estimation/tables/30ae6a80db522a1633662768e4ff4fd9d9eaf91fd0aa52802a58160b189681a7.jpg)

![b3963b330d023f9866a2dbe6bf20258f2b334a2f83ef369cd9f9f56bb0563307.jpg](../nips_results/552_Instance-Optimality%20for%20Private%20KL%20Distribution%20Estimation/tables/b3963b330d023f9866a2dbe6bf20258f2b334a2f83ef369cd9f9f56bb0563307.jpg)

![b7091fb10952d04ba46bf46c53a281363de776a0ae0a0a6dccde24e4c330f3c4.jpg](../nips_results/552_Instance-Optimality%20for%20Private%20KL%20Distribution%20Estimation/tables/b7091fb10952d04ba46bf46c53a281363de776a0ae0a0a6dccde24e4c330f3c4.jpg)

![d33c6c96f3068d9251ffef4486196fe3e944d62343c25acf4232c4564f4d48ae.jpg](../nips_results/552_Instance-Optimality%20for%20Private%20KL%20Distribution%20Estimation/tables/d33c6c96f3068d9251ffef4486196fe3e944d62343c25acf4232c4564f4d48ae.jpg)

![fd0eb762d752a535e11effb86103924bd2f67f5573c9e27d621b3c7e80588025.jpg](../nips_results/552_Instance-Optimality%20for%20Private%20KL%20Distribution%20Estimation/tables/fd0eb762d752a535e11effb86103924bd2f67f5573c9e27d621b3c7e80588025.jpg)

## Flow Density Control: Generative Optimization Beyond Entropy-Regularized Fine-Tuning


### Images

![59738986b2f7b91a31c9c3167fbec869bba442211b75fbfcd4629813627cdd78.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/images/59738986b2f7b91a31c9c3167fbec869bba442211b75fbfcd4629813627cdd78.jpg)

![8bb5eb0839b52c7bc307042fd1d14146ee9962c0bf59f0e33fc36b215f4f9e84.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/images/8bb5eb0839b52c7bc307042fd1d14146ee9962c0bf59f0e33fc36b215f4f9e84.jpg)

![c1bf8604219164f04ac06d51aa484a7712cdb3f687e04d17a80ee701235411bf.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/images/c1bf8604219164f04ac06d51aa484a7712cdb3f687e04d17a80ee701235411bf.jpg)

### Tables

![010f97decbd35e9831b81f73b68e2d874851440c8293703697d026b045b155a1.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/tables/010f97decbd35e9831b81f73b68e2d874851440c8293703697d026b045b155a1.jpg)

![207335d6c6c5c281da71690513073159a134e363c0614aefdf4fbec3cfa70e3d.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/tables/207335d6c6c5c281da71690513073159a134e363c0614aefdf4fbec3cfa70e3d.jpg)

![41167a2391f4828f8dd83ed3f3601dab2c54361a36e0a6b8fe9d09636248eafd.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/tables/41167a2391f4828f8dd83ed3f3601dab2c54361a36e0a6b8fe9d09636248eafd.jpg)

![867f6cf438bdbfe98886171e0d73cfcaf481218571981b78827aed88ee2650cc.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/tables/867f6cf438bdbfe98886171e0d73cfcaf481218571981b78827aed88ee2650cc.jpg)

![89655befb77a4e9794c57972931844ec76879c4d3ce1a79095081548715dc8a5.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/tables/89655befb77a4e9794c57972931844ec76879c4d3ce1a79095081548715dc8a5.jpg)

![bb82b37a91bdd9a21f06893123e132ef36a870286e4cf19a5dce9ce8c22367f5.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/tables/bb82b37a91bdd9a21f06893123e132ef36a870286e4cf19a5dce9ce8c22367f5.jpg)

![d56f0048323f106cdac1fb9517cd44678b3dd02f6000351c3dcf2626b26a3a38.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/tables/d56f0048323f106cdac1fb9517cd44678b3dd02f6000351c3dcf2626b26a3a38.jpg)

![f08423631f6871846871881afcd475b522280280be77910dec155bf61d0791bf.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/tables/f08423631f6871846871881afcd475b522280280be77910dec155bf61d0791bf.jpg)

![f7213881b74faf3176e4995e1b0d89832d74b610b58dcfb23d50eb09c95896d0.jpg](../nips_results/553_Flow%20Density%20Control_%20Generative%20Optimization%20Beyond%20Entropy-Regularized%20Fine-Tuning/tables/f7213881b74faf3176e4995e1b0d89832d74b610b58dcfb23d50eb09c95896d0.jpg)

## DNAEdit: Direct Noise Alignment for Text-Guided Rectified Flow Editing


### Images

![0111853af5da43e6f6d040fa79c3bd80d5397d60ed609191bd01767e66811182.jpg](../nips_results/554_DNAEdit_%20Direct%20Noise%20Alignment%20for%20Text-Guided%20Rectified%20Flow%20Editing/images/0111853af5da43e6f6d040fa79c3bd80d5397d60ed609191bd01767e66811182.jpg)

![0cc89bbd825b3252151929c586bbcac04ddc902d1302e85eb5d341c935a18874.jpg](../nips_results/554_DNAEdit_%20Direct%20Noise%20Alignment%20for%20Text-Guided%20Rectified%20Flow%20Editing/images/0cc89bbd825b3252151929c586bbcac04ddc902d1302e85eb5d341c935a18874.jpg)

![731661d2e2d13a5e77f139c6f410cd2f6bffcaadd2e675447fc632020e9fe3f1.jpg](../nips_results/554_DNAEdit_%20Direct%20Noise%20Alignment%20for%20Text-Guided%20Rectified%20Flow%20Editing/images/731661d2e2d13a5e77f139c6f410cd2f6bffcaadd2e675447fc632020e9fe3f1.jpg)

![976e9681636d888921a750476206bf305c234a3f3504ca7f0c02baf5f178499b.jpg](../nips_results/554_DNAEdit_%20Direct%20Noise%20Alignment%20for%20Text-Guided%20Rectified%20Flow%20Editing/images/976e9681636d888921a750476206bf305c234a3f3504ca7f0c02baf5f178499b.jpg)

![b6771330d7959dbf8df40a4ab46ef6ade87291a6a106e689641a385921a32d3b.jpg](../nips_results/554_DNAEdit_%20Direct%20Noise%20Alignment%20for%20Text-Guided%20Rectified%20Flow%20Editing/images/b6771330d7959dbf8df40a4ab46ef6ade87291a6a106e689641a385921a32d3b.jpg)

### Tables

![2a7aa1e4c11b0f2df2b916450ea44bfe40a4ea2a309cd44e58611e8b2fac709f.jpg](../nips_results/554_DNAEdit_%20Direct%20Noise%20Alignment%20for%20Text-Guided%20Rectified%20Flow%20Editing/tables/2a7aa1e4c11b0f2df2b916450ea44bfe40a4ea2a309cd44e58611e8b2fac709f.jpg)

![56ab946c02cb6c9c756037760121ac6ab7f9b03aba132a4eb6ed429c4fbd29c1.jpg](../nips_results/554_DNAEdit_%20Direct%20Noise%20Alignment%20for%20Text-Guided%20Rectified%20Flow%20Editing/tables/56ab946c02cb6c9c756037760121ac6ab7f9b03aba132a4eb6ed429c4fbd29c1.jpg)

![5a3114764c4d8387a6f387c8d81fbb1526021f481debc0e0ce95ccd9ea46a66a.jpg](../nips_results/554_DNAEdit_%20Direct%20Noise%20Alignment%20for%20Text-Guided%20Rectified%20Flow%20Editing/tables/5a3114764c4d8387a6f387c8d81fbb1526021f481debc0e0ce95ccd9ea46a66a.jpg)

![6ab097e51424dc88a964249e1d2ffe1fc8e5d01ff84a6fb22d1ea87a4ab5ffcf.jpg](../nips_results/554_DNAEdit_%20Direct%20Noise%20Alignment%20for%20Text-Guided%20Rectified%20Flow%20Editing/tables/6ab097e51424dc88a964249e1d2ffe1fc8e5d01ff84a6fb22d1ea87a4ab5ffcf.jpg)

![6ee71d49282d2722a8cae764025aadd32460c8cabdd0546ee91491d16ab5fc4c.jpg](../nips_results/554_DNAEdit_%20Direct%20Noise%20Alignment%20for%20Text-Guided%20Rectified%20Flow%20Editing/tables/6ee71d49282d2722a8cae764025aadd32460c8cabdd0546ee91491d16ab5fc4c.jpg)

![934bdd59f6e0e81bc720cc5d95f8d8afba54e5bcc842c56d125c151994fc1343.jpg](../nips_results/554_DNAEdit_%20Direct%20Noise%20Alignment%20for%20Text-Guided%20Rectified%20Flow%20Editing/tables/934bdd59f6e0e81bc720cc5d95f8d8afba54e5bcc842c56d125c151994fc1343.jpg)

## Diffusion Generative Modeling on Lie Group Representations


### Images

![2ca8b3aa173778edce51c90ef84861fa46fca8e9073fd8e97dda0d6f2a37fe42.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/images/2ca8b3aa173778edce51c90ef84861fa46fca8e9073fd8e97dda0d6f2a37fe42.jpg)

![31d4474176b16143b2a7ec1bd151a8e7055479e8c5738a9ec9ac4dff177c9b61.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/images/31d4474176b16143b2a7ec1bd151a8e7055479e8c5738a9ec9ac4dff177c9b61.jpg)

![4282585e18f2cad903a6e95a4679a55a5d39cf825ec22ad02b7f2af157752404.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/images/4282585e18f2cad903a6e95a4679a55a5d39cf825ec22ad02b7f2af157752404.jpg)

![5270bac01bb2a4d17f512cf3fcac34d749931fdf4b59b8d69d4d490c2060d27c.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/images/5270bac01bb2a4d17f512cf3fcac34d749931fdf4b59b8d69d4d490c2060d27c.jpg)

![ae3b0104d054b5cdfdfaa74213b088f69458a9fb512d6b098aeb576417de79ee.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/images/ae3b0104d054b5cdfdfaa74213b088f69458a9fb512d6b098aeb576417de79ee.jpg)

![b8c9b23b863949928838aee455c26f45dee54e9c700f8a83148a45efa9622308.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/images/b8c9b23b863949928838aee455c26f45dee54e9c700f8a83148a45efa9622308.jpg)

![ba1d6662b235c84d764d009a81107045eb1b7382fe1d5900e3198eda38d7abcb.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/images/ba1d6662b235c84d764d009a81107045eb1b7382fe1d5900e3198eda38d7abcb.jpg)

![c08d631fabe03e0168d8ba031f3300dfb49b5e2e1c56e444840a538029117024.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/images/c08d631fabe03e0168d8ba031f3300dfb49b5e2e1c56e444840a538029117024.jpg)

![c7e66066afa899b144ff858172ae67b66392ee9eaeebfa6f7104aeaef23239e1.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/images/c7e66066afa899b144ff858172ae67b66392ee9eaeebfa6f7104aeaef23239e1.jpg)

![e968b338660e3bc7349fb8af8bf34a225fb0fcde5929b36b1636cd0d6332ac48.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/images/e968b338660e3bc7349fb8af8bf34a225fb0fcde5929b36b1636cd0d6332ac48.jpg)

### Tables

![3f36cd25376e8b2046d484513045b1c90f18d1a94b520a879b50d201da82b4e8.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/tables/3f36cd25376e8b2046d484513045b1c90f18d1a94b520a879b50d201da82b4e8.jpg)

![57f65a8692e5dbaa2098328ad867dd927e47f176542a3ccf380005a9a50d5d36.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/tables/57f65a8692e5dbaa2098328ad867dd927e47f176542a3ccf380005a9a50d5d36.jpg)

![cac2d6dc55a123f51aebc2d7d83bbf188c922d32848d12132b75fd1a88f15dfc.jpg](../nips_results/555_Diffusion%20Generative%20Modeling%20on%20Lie%20Group%20Representations/tables/cac2d6dc55a123f51aebc2d7d83bbf188c922d32848d12132b75fd1a88f15dfc.jpg)

## Ctrl-DNA: Controllable Cell-Type-Specific Regulatory DNA Design via Constrained RL


### Images

![77dedb6009d96a7a95ffd44a891ae36778a7c4ae6c0f92cb2c37f64e40a4f70c.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/images/77dedb6009d96a7a95ffd44a891ae36778a7c4ae6c0f92cb2c37f64e40a4f70c.jpg)

![8bb714954a72bf2042822a34da52defb31345073c3f4cd70a3557ec58a8033f7.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/images/8bb714954a72bf2042822a34da52defb31345073c3f4cd70a3557ec58a8033f7.jpg)

![f3fcbf348e34de6bff2ea76ffcdc21f7c4479b2d2862fb395804f99644a6a73f.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/images/f3fcbf348e34de6bff2ea76ffcdc21f7c4479b2d2862fb395804f99644a6a73f.jpg)

![f5fd429d293f7c07b5a772a076f891bf73077d1c7408758b3589c1f883523750.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/images/f5fd429d293f7c07b5a772a076f891bf73077d1c7408758b3589c1f883523750.jpg)

### Tables

![1259fc77127d1854f6338d13e7f9a5ddab2354307c9df6715be86a0ac36d9fcb.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/1259fc77127d1854f6338d13e7f9a5ddab2354307c9df6715be86a0ac36d9fcb.jpg)

![14f21c7a33eee142eacac13aae247debcd1681f612b167518c8d5e1e15559907.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/14f21c7a33eee142eacac13aae247debcd1681f612b167518c8d5e1e15559907.jpg)

![32d26a1559f540f555ba7d82a07d130fbaa78c4a1fde936ae32d4f90dd31c337.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/32d26a1559f540f555ba7d82a07d130fbaa78c4a1fde936ae32d4f90dd31c337.jpg)

![353c3d207df8da0e75e691eeee6d9490c1b2557cd43bbfe60b5c1409c2da641d.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/353c3d207df8da0e75e691eeee6d9490c1b2557cd43bbfe60b5c1409c2da641d.jpg)

![384bc4ab29823ded730e6797383d0a407c868c2f7bb139156134073aaac9fde4.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/384bc4ab29823ded730e6797383d0a407c868c2f7bb139156134073aaac9fde4.jpg)

![3e2f774e79ec41d4ff4d146379edd36191ad008a1901061932683603b1c53783.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/3e2f774e79ec41d4ff4d146379edd36191ad008a1901061932683603b1c53783.jpg)

![6cb6a35c7f382552d59bd52eda73637a6ae3e73238de2c09dbc51bf2ef442e5a.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/6cb6a35c7f382552d59bd52eda73637a6ae3e73238de2c09dbc51bf2ef442e5a.jpg)

![87d4b6af3ec14063287f97bf6704a0ff1f2a2ecc8e02c2a38a047809dd5ebcab.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/87d4b6af3ec14063287f97bf6704a0ff1f2a2ecc8e02c2a38a047809dd5ebcab.jpg)

![a7d31bfa49c0cf3669c1c57ed1ca12355bf4058792e544edd218557bce595be0.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/a7d31bfa49c0cf3669c1c57ed1ca12355bf4058792e544edd218557bce595be0.jpg)

![a95f26fa8ae72fae45b50272069091af8c34e475ece5ec3d709a03e17d258f38.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/a95f26fa8ae72fae45b50272069091af8c34e475ece5ec3d709a03e17d258f38.jpg)

![b103d7e8d8b08d7b70ed649e686b586e2f05e2bf16b2a287fa1ccba87f46b6ee.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/b103d7e8d8b08d7b70ed649e686b586e2f05e2bf16b2a287fa1ccba87f46b6ee.jpg)

![eb1556df65b6a0acf2187169cb2779dee7a89b9a8138a7ac681033582cfd1684.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/eb1556df65b6a0acf2187169cb2779dee7a89b9a8138a7ac681033582cfd1684.jpg)

![ecc70053d00044eca3374def4da0263b682f3e036ca76f6b23848b9e0fa8aed4.jpg](../nips_results/556_Ctrl-DNA_%20Controllable%20Cell-Type-Specific%20Regulatory%20DNA%20Design%20via%20Constrained%20RL/tables/ecc70053d00044eca3374def4da0263b682f3e036ca76f6b23848b9e0fa8aed4.jpg)

## HM3: Hierarchical Multi-Objective Model Merging for Pretrained Models


### Images

![24ab9f434b0148660e55ff16abf6590abbbed8043bd2d080d1df67db97e2248f.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/images/24ab9f434b0148660e55ff16abf6590abbbed8043bd2d080d1df67db97e2248f.jpg)

![4938ca4a8e01d7646676959bc2bed3e7eb8a24931c8246321c8fd2a61ac4b879.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/images/4938ca4a8e01d7646676959bc2bed3e7eb8a24931c8246321c8fd2a61ac4b879.jpg)

![675788c43e1288245b3a2c7ecf2917eaebb43cfe511e9115bb12a5bbdf0a0c7d.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/images/675788c43e1288245b3a2c7ecf2917eaebb43cfe511e9115bb12a5bbdf0a0c7d.jpg)

![77f59e8f2cdb85a05ff60e957bffe907b2f611ca6c8a7064cf995e21b8a5d6ca.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/images/77f59e8f2cdb85a05ff60e957bffe907b2f611ca6c8a7064cf995e21b8a5d6ca.jpg)

![ba39c4e19803d754f72ddf4e23c4637c9a0d825ffcaa0a190d64473d05b3ea70.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/images/ba39c4e19803d754f72ddf4e23c4637c9a0d825ffcaa0a190d64473d05b3ea70.jpg)

![e7737a1aad72e4958c616c1f48ffa882feeb876bd62aebe4ddfe79837e01c54f.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/images/e7737a1aad72e4958c616c1f48ffa882feeb876bd62aebe4ddfe79837e01c54f.jpg)

### Tables

![18809513bc41a17aa3e7bb1aed0e72223e0c797b5a48bce69fb87d4a87393fa6.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/tables/18809513bc41a17aa3e7bb1aed0e72223e0c797b5a48bce69fb87d4a87393fa6.jpg)

![1ea04b882eb9d38e98371b6b81e094034e7b0887371f74d811c4eb60b0c5b948.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/tables/1ea04b882eb9d38e98371b6b81e094034e7b0887371f74d811c4eb60b0c5b948.jpg)

![3f3e98e14ee833e917c66e295c01f79feeb344c644f03e25aea4926e3cf5aabe.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/tables/3f3e98e14ee833e917c66e295c01f79feeb344c644f03e25aea4926e3cf5aabe.jpg)

![42f9b0b9ab320852774332866d3920272aa777a055460940b9c37e4ced015953.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/tables/42f9b0b9ab320852774332866d3920272aa777a055460940b9c37e4ced015953.jpg)

![7bb07e13c3453aad7b617967389bcdcc6acc9c9ab0527712402052c045339e04.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/tables/7bb07e13c3453aad7b617967389bcdcc6acc9c9ab0527712402052c045339e04.jpg)

![a10f8218ac5cf408d25980d48165884d64f1f0a42db59ae7ecb60f01baec32c6.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/tables/a10f8218ac5cf408d25980d48165884d64f1f0a42db59ae7ecb60f01baec32c6.jpg)

![ca1d87c2c887c9975eaac9f692d3f3de28f0870e60f882dee374525f83e4a5ae.jpg](../nips_results/557_HM3_%20Hierarchical%20Multi-Objective%20Model%20Merging%20for%20Pretrained%20Models/tables/ca1d87c2c887c9975eaac9f692d3f3de28f0870e60f882dee374525f83e4a5ae.jpg)

## SageAttention3: Microscaling FP4 Attention for Inference and An Exploration of 8-Bit Training


### Images

![13dfd23e70198e0c842f7356bf71de07ed69f61c00711fec8dd34b8780b354d7.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/13dfd23e70198e0c842f7356bf71de07ed69f61c00711fec8dd34b8780b354d7.jpg)

![3b12cba39c183c809789b9b35d2e1ae3171a327e1132b6289eb981943e94a48f.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/3b12cba39c183c809789b9b35d2e1ae3171a327e1132b6289eb981943e94a48f.jpg)

![47f9c233088ce659af63dbb4d34dddd62d7a5c8fac700291a9b8b56d1a54f325.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/47f9c233088ce659af63dbb4d34dddd62d7a5c8fac700291a9b8b56d1a54f325.jpg)

![47fa84ef76f0de9f994c09d6c9fafe103fd50eb46f9ab9dc1b69e82153d3d692.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/47fa84ef76f0de9f994c09d6c9fafe103fd50eb46f9ab9dc1b69e82153d3d692.jpg)

![5800f40cb5ceb253f9ffad4a846333f47dc97800fb7565834897b59b5e343559.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/5800f40cb5ceb253f9ffad4a846333f47dc97800fb7565834897b59b5e343559.jpg)

![59f192af926709dba36e7ae5a3a2e47afdcc0abc2d16440d5ad46a6ec9e2b5d9.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/59f192af926709dba36e7ae5a3a2e47afdcc0abc2d16440d5ad46a6ec9e2b5d9.jpg)

![62ce965e7c977c3c3dbe9aec4a160f1dec73fcd4c33968392f6718c1291b0bb1.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/62ce965e7c977c3c3dbe9aec4a160f1dec73fcd4c33968392f6718c1291b0bb1.jpg)

![7c85b1d690650eeb0976de2c167cf19e8233247703f7f1c2b21de326cc645df4.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/7c85b1d690650eeb0976de2c167cf19e8233247703f7f1c2b21de326cc645df4.jpg)

![7f674a706c3ccb966b53485807601813012b839a295c0bbd8fdc0877cdd55dd5.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/7f674a706c3ccb966b53485807601813012b839a295c0bbd8fdc0877cdd55dd5.jpg)

![8f398317ab886aabafd21968d85fc74885befe71f0c3f68becde8ddff33d09c7.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/8f398317ab886aabafd21968d85fc74885befe71f0c3f68becde8ddff33d09c7.jpg)

![99328bedc77aa3a024849bd7e4f734c785210bfb35181d74dd89fc8637d32831.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/99328bedc77aa3a024849bd7e4f734c785210bfb35181d74dd89fc8637d32831.jpg)

![9d4a832adcd7770bd9be8e97d827c2a085fe5c250ca6ae8f2a329bd10a1c8f45.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/9d4a832adcd7770bd9be8e97d827c2a085fe5c250ca6ae8f2a329bd10a1c8f45.jpg)

![b30fb91b66ab590340708bd6b87231e020f0cd192e506e3e6781283e00ef0fb1.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/b30fb91b66ab590340708bd6b87231e020f0cd192e506e3e6781283e00ef0fb1.jpg)

![b752ab50af4ff721bcd3c725764aabd3dc1f4b0156f3bd922ba3bf513bab753b.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/b752ab50af4ff721bcd3c725764aabd3dc1f4b0156f3bd922ba3bf513bab753b.jpg)

![cbb9456577689e2bd66d189d1f1c7c56d3829c701bbec6fe2a08f798f2f0a7b0.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/cbb9456577689e2bd66d189d1f1c7c56d3829c701bbec6fe2a08f798f2f0a7b0.jpg)

![cedef174cc5186726f5e9ca8354e514d404da0535b023842d6f7f8783da7e47a.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/cedef174cc5186726f5e9ca8354e514d404da0535b023842d6f7f8783da7e47a.jpg)

![d73006a9dda7d09bf9b8c97a9c9f59a9fc02314f1e151dc07ee7af64c8c5e2d2.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/d73006a9dda7d09bf9b8c97a9c9f59a9fc02314f1e151dc07ee7af64c8c5e2d2.jpg)

![dce48312ca57c7a22af63349d0bc9a6a5031e39cd0753956a4ed2225f6c13434.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/dce48312ca57c7a22af63349d0bc9a6a5031e39cd0753956a4ed2225f6c13434.jpg)

![e3cc0f712356156f21a9ce225c40c7ca2adab9cf4030d87095f63ac84c4d4843.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/e3cc0f712356156f21a9ce225c40c7ca2adab9cf4030d87095f63ac84c4d4843.jpg)

![f95a655f217038bdf2da7a6376d365b918f367d26325ffb407a127363b87c535.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/images/f95a655f217038bdf2da7a6376d365b918f367d26325ffb407a127363b87c535.jpg)

### Tables

![081272f68857afebce1e340b1777486cb3cf4940c7baf8cd9f20f6c9e46def6b.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/081272f68857afebce1e340b1777486cb3cf4940c7baf8cd9f20f6c9e46def6b.jpg)

![2e37dcb0d091bb8a1d40ab2fbc3fce756aeb97cc43b7975da08dcd62643eb815.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/2e37dcb0d091bb8a1d40ab2fbc3fce756aeb97cc43b7975da08dcd62643eb815.jpg)

![363c12fa8524a5e587d9f0a2a52c75fcb04b95d7d3ed36400885e16ecf12104a.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/363c12fa8524a5e587d9f0a2a52c75fcb04b95d7d3ed36400885e16ecf12104a.jpg)

![5453dd626a75407732bf975ca026cfde65f84bc6cd9192318879ba7cabfd41f5.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/5453dd626a75407732bf975ca026cfde65f84bc6cd9192318879ba7cabfd41f5.jpg)

![59698d640b0407e38784c8edd2877f1ad762428d762cc11469191b1332b900fe.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/59698d640b0407e38784c8edd2877f1ad762428d762cc11469191b1332b900fe.jpg)

![5b97e2e1379d19bd7be54f1b9482abee88fbb151ba99bb55d0d9777eff6d1998.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/5b97e2e1379d19bd7be54f1b9482abee88fbb151ba99bb55d0d9777eff6d1998.jpg)

![5f702b6608c99551a299b218da73bc551eabe250ba95d2b5d82fa898c65769bc.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/5f702b6608c99551a299b218da73bc551eabe250ba95d2b5d82fa898c65769bc.jpg)

![689ad158c4d0e1b7607f3e85e87765e25df1c38e99854f248a0fd12929ced496.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/689ad158c4d0e1b7607f3e85e87765e25df1c38e99854f248a0fd12929ced496.jpg)

![6a685be3f93a55d998ae7b8b2799667da5df0d203dbf3f4185570105dd7434d1.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/6a685be3f93a55d998ae7b8b2799667da5df0d203dbf3f4185570105dd7434d1.jpg)

![6c221e53f81b884fa6b5285ff807a94ca877b2c53457a16ee0f7a8b7d2ad8c3e.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/6c221e53f81b884fa6b5285ff807a94ca877b2c53457a16ee0f7a8b7d2ad8c3e.jpg)

![6c22417a07c49b9c7a9bf55a8be75784860f0931452e10128f9034d67e348f0c.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/6c22417a07c49b9c7a9bf55a8be75784860f0931452e10128f9034d67e348f0c.jpg)

![84487380b480fc615edf891405678246e9f92bff51c46f303f1b7fdbe6f1931d.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/84487380b480fc615edf891405678246e9f92bff51c46f303f1b7fdbe6f1931d.jpg)

![8fe4564ab814ee5e60ba6ea1e99bde020fdbc9123d2e7a1d44362a653270457d.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/8fe4564ab814ee5e60ba6ea1e99bde020fdbc9123d2e7a1d44362a653270457d.jpg)

![926db262af155126ec59ce456fde5fa784e695eb782d317b6038c15997b64e56.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/926db262af155126ec59ce456fde5fa784e695eb782d317b6038c15997b64e56.jpg)

![930d13a1622f703397372450315abbed3ab7a17254a162b6b848a12c6ba8f745.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/930d13a1622f703397372450315abbed3ab7a17254a162b6b848a12c6ba8f745.jpg)

![a10ed77bc50f1b6f6213033b36fa8be08042cd76d9e0b6a8aa901f8049463290.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/a10ed77bc50f1b6f6213033b36fa8be08042cd76d9e0b6a8aa901f8049463290.jpg)

![a216efa09b3f75ccae77816960fc8f07e7adf4bd143e4798a734a710cc65c543.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/a216efa09b3f75ccae77816960fc8f07e7adf4bd143e4798a734a710cc65c543.jpg)

![a4b1af3d00206299aa4d9da24263b966e6a3524cb9a33dd7d60c23a7f1d71d2d.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/a4b1af3d00206299aa4d9da24263b966e6a3524cb9a33dd7d60c23a7f1d71d2d.jpg)

![a67fe69b7e643573ebfa3e79c2a0adca001120f8403a1d0f81955f50aa551fa2.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/a67fe69b7e643573ebfa3e79c2a0adca001120f8403a1d0f81955f50aa551fa2.jpg)

![ad7b733790f450407d20bb39b6c32d4efa794c15d304f505091dbc48a417ff3c.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/ad7b733790f450407d20bb39b6c32d4efa794c15d304f505091dbc48a417ff3c.jpg)

![b42cc941634330b0da5f53f74d6c577c40f070349ec2850ca5ac27d86f94b7ab.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/b42cc941634330b0da5f53f74d6c577c40f070349ec2850ca5ac27d86f94b7ab.jpg)

![c6abe71205ae9a903888657e7c6257819af83cfc5b9d8f4339077ff05f447a1e.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/c6abe71205ae9a903888657e7c6257819af83cfc5b9d8f4339077ff05f447a1e.jpg)

![ce02a3bcd5b94d61fdb43da745844780fa3ecf7d3096869787445a1835c76d27.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/ce02a3bcd5b94d61fdb43da745844780fa3ecf7d3096869787445a1835c76d27.jpg)

![cf327eab3337eb17fed2587502c248bc69fa5f4b4686f679fa85db58cf6b91c1.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/cf327eab3337eb17fed2587502c248bc69fa5f4b4686f679fa85db58cf6b91c1.jpg)

![ee1ef33dd1e2c5cfaf6684d96ab4afc2d044dc4b44fb071897699e24ceb8b849.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/ee1ef33dd1e2c5cfaf6684d96ab4afc2d044dc4b44fb071897699e24ceb8b849.jpg)

![fff067f9888e0dd1e87ff693bca9291818aba3a5d2afead4443b34bcc3226ced.jpg](../nips_results/558_SageAttention3_%20Microscaling%20FP4%20Attention%20for%20Inference%20and%20An%20Exploration%20of%208-Bit%20Training/tables/fff067f9888e0dd1e87ff693bca9291818aba3a5d2afead4443b34bcc3226ced.jpg)

## Fast Monte Carlo Tree Diffusion: 100× Speedup via Parallel and Sparse Planning


### Images

![19d9ec2f786a63229134b2d1ac0d7bfe78641f880d684421e25555f9fa2ac366.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/images/19d9ec2f786a63229134b2d1ac0d7bfe78641f880d684421e25555f9fa2ac366.jpg)

![2247730662f1ceea03272f48ce9306de5edeb1eec8cef44e6958789d78c5e3fc.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/images/2247730662f1ceea03272f48ce9306de5edeb1eec8cef44e6958789d78c5e3fc.jpg)

![350703c64a0bd6999e91b0e179e86079175999ee317b83b5b7c4cb8f95cc8a48.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/images/350703c64a0bd6999e91b0e179e86079175999ee317b83b5b7c4cb8f95cc8a48.jpg)

![89b9036fbf83d4408404eee2263785868fd6578eed4218497ee42dfcfbcfa920.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/images/89b9036fbf83d4408404eee2263785868fd6578eed4218497ee42dfcfbcfa920.jpg)

![970d5a30de6bec5bc1e0523943922cf0c0d4ff0a9e88a38b7fe01156f02cba19.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/images/970d5a30de6bec5bc1e0523943922cf0c0d4ff0a9e88a38b7fe01156f02cba19.jpg)

![bb672f61ffe5f5aa0876f3c345e09d1d249a3ab6206754e8250332c21a8cdf93.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/images/bb672f61ffe5f5aa0876f3c345e09d1d249a3ab6206754e8250332c21a8cdf93.jpg)

### Tables

![02b2a40abdfc97056aeb1a47c96d25eef3ab5b3bfd45ec531c96f0ace4e5621e.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/tables/02b2a40abdfc97056aeb1a47c96d25eef3ab5b3bfd45ec531c96f0ace4e5621e.jpg)

![075091a0e6366171d5e37e88d8f7381748fb3d3d49deacd79bcafa53df397c01.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/tables/075091a0e6366171d5e37e88d8f7381748fb3d3d49deacd79bcafa53df397c01.jpg)

![279b747671fd0c3b8191a8f47b93a9a1cf507b30a332bd65ff062017c28aa730.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/tables/279b747671fd0c3b8191a8f47b93a9a1cf507b30a332bd65ff062017c28aa730.jpg)

![3f1f9fd1240b8cf937fd9c6b136724c64a8c78f92a7b7d5920ce4dcbef6f7d0c.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/tables/3f1f9fd1240b8cf937fd9c6b136724c64a8c78f92a7b7d5920ce4dcbef6f7d0c.jpg)

![4416d21033cb363edceba940a107890312f3ec927fedea7abba211d8b8eeeab6.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/tables/4416d21033cb363edceba940a107890312f3ec927fedea7abba211d8b8eeeab6.jpg)

![cda4e44cfe0fd661558c1f53358ddf47c2d77003a928dd92d7db5a6c9e074139.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/tables/cda4e44cfe0fd661558c1f53358ddf47c2d77003a928dd92d7db5a6c9e074139.jpg)

![d9dc33ca31ab175103d7f1fe841adf424bd42a621baa03247e0effc6d6e0d31f.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/tables/d9dc33ca31ab175103d7f1fe841adf424bd42a621baa03247e0effc6d6e0d31f.jpg)

![e4b81194ecd4d0188f531c07e7c91bd8cf6d66ca415b17266c4d9d9968041224.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/tables/e4b81194ecd4d0188f531c07e7c91bd8cf6d66ca415b17266c4d9d9968041224.jpg)

![ef0331814e127acfa2f4fd42551fe4349111fe9b98a9931896d2f6510632bd22.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/tables/ef0331814e127acfa2f4fd42551fe4349111fe9b98a9931896d2f6510632bd22.jpg)

![f4923fd9e6c26083903e5823a1ac20e9097ee22460f326af21fa55ff7f3ef871.jpg](../nips_results/559_Fast%20Monte%20Carlo%20Tree%20Diffusion_%20100%C3%97%20Speedup%20via%20Parallel%20and%20Sparse%20Planning/tables/f4923fd9e6c26083903e5823a1ac20e9097ee22460f326af21fa55ff7f3ef871.jpg)

## Transstratal Adversarial Attack: Compromising Multi-Layered Defenses in Text-to-Image Models


### Images

![195d153a593c77f0fb027d56ea3d437dc74dc2ed2d0b7c0d1206c734e789e193.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/images/195d153a593c77f0fb027d56ea3d437dc74dc2ed2d0b7c0d1206c734e789e193.jpg)

![58e15d67bad7c4b6db997d805445dc8767a8b48809718986a6732506483fcaeb.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/images/58e15d67bad7c4b6db997d805445dc8767a8b48809718986a6732506483fcaeb.jpg)

![8551790255c854271a5b0c7e2ac7e53612fc7f9c9f62f94bcb7018ff3a36627d.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/images/8551790255c854271a5b0c7e2ac7e53612fc7f9c9f62f94bcb7018ff3a36627d.jpg)

![982215409297e914a2d017e296ae15fbbe7db7005e107d1f516c3f7f5f73da1e.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/images/982215409297e914a2d017e296ae15fbbe7db7005e107d1f516c3f7f5f73da1e.jpg)

![9fb0e0de5edf8f29bc9c0b7f1a34419913dcda47a7e4e20045ef9dd146f4b3e9.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/images/9fb0e0de5edf8f29bc9c0b7f1a34419913dcda47a7e4e20045ef9dd146f4b3e9.jpg)

![ae405835244ed7a35a1c670a7da8f3609945f94ca6ca9a44f3865c7f09e8d54d.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/images/ae405835244ed7a35a1c670a7da8f3609945f94ca6ca9a44f3865c7f09e8d54d.jpg)

![f377d371dbe982a394be4edb15b60c8f81603d92c854900b4184782555f5c139.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/images/f377d371dbe982a394be4edb15b60c8f81603d92c854900b4184782555f5c139.jpg)

![f7a3441751488faa091cf51cfdd2049ff9cecfb7990d9a582d193b3b7d9fbee5.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/images/f7a3441751488faa091cf51cfdd2049ff9cecfb7990d9a582d193b3b7d9fbee5.jpg)

![fa37030095ea5a2b733c41830c02583adeb863dc5d4352f92961075d1b9f4e70.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/images/fa37030095ea5a2b733c41830c02583adeb863dc5d4352f92961075d1b9f4e70.jpg)

### Tables

![00791fab804db28c6a856dd793653f84714244437caccb924b464aad8b94b68a.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/00791fab804db28c6a856dd793653f84714244437caccb924b464aad8b94b68a.jpg)

![062c334e671e7d98a1caef1be78f07cd3e160318f44463778d333a1ad330ee65.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/062c334e671e7d98a1caef1be78f07cd3e160318f44463778d333a1ad330ee65.jpg)

![1b818b22d1e926b308846e5da3e5b08ac650a212def08bfd3fb9288782749e8f.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/1b818b22d1e926b308846e5da3e5b08ac650a212def08bfd3fb9288782749e8f.jpg)

![5a0877308c22ea23f8d35192130157876dd0b38916c79ac50b37c629b84b29c2.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/5a0877308c22ea23f8d35192130157876dd0b38916c79ac50b37c629b84b29c2.jpg)

![69af05ab2cdb5de1c7b633ac35b1715aad783517869c82215d26dda8fb697a22.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/69af05ab2cdb5de1c7b633ac35b1715aad783517869c82215d26dda8fb697a22.jpg)

![819e8c9f311e6372cdd682f058e76a4750c3e9eaf2a45a7927bc397ceabfd228.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/819e8c9f311e6372cdd682f058e76a4750c3e9eaf2a45a7927bc397ceabfd228.jpg)

![a2109aaa99ac4cf7577c08e1107241bba24413eb11fccb490a73ab18a1a232d9.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/a2109aaa99ac4cf7577c08e1107241bba24413eb11fccb490a73ab18a1a232d9.jpg)

![a88d25b03e38f08c0f6b14b2400eba1ae0a0a977f3373733145990751031e136.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/a88d25b03e38f08c0f6b14b2400eba1ae0a0a977f3373733145990751031e136.jpg)

![b85c9e1e78a485a4419ad7b703e3e5d64d63288fb0158aac1c22ac476a6714ec.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/b85c9e1e78a485a4419ad7b703e3e5d64d63288fb0158aac1c22ac476a6714ec.jpg)

![c7c0447de4664fd6834363dcdc4d8235074e67d4c8315d9683a5ac19999dd466.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/c7c0447de4664fd6834363dcdc4d8235074e67d4c8315d9683a5ac19999dd466.jpg)

![d1f5a193b6d560e6d825f37417410c05b8e4f0ebc9d1edc6b1e398a42fb97d90.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/d1f5a193b6d560e6d825f37417410c05b8e4f0ebc9d1edc6b1e398a42fb97d90.jpg)

![d98bc346dc0af245981ed0b601011117078135a0e3f36ec7fd4f48abce69135f.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/d98bc346dc0af245981ed0b601011117078135a0e3f36ec7fd4f48abce69135f.jpg)

![e04c0070ee19683ea57695a7b2d1875692d80080747b218925564e699fa6cc9e.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/e04c0070ee19683ea57695a7b2d1875692d80080747b218925564e699fa6cc9e.jpg)

![ee86df27a34a8431f13964f5152a020b1ae185ed246be434ea5260365329659a.jpg](../nips_results/560_Transstratal%20Adversarial%20Attack_%20Compromising%20Multi-Layered%20Defenses%20in%20Text-to-Image%20Models/tables/ee86df27a34a8431f13964f5152a020b1ae185ed246be434ea5260365329659a.jpg)

## Frame Context Packing and Drift Prevention in Next-Frame-Prediction Video Diffusion Models


### Images

![621edb1d0d870943503804ae86b29a0494ab5c6fcb04b343d964dac2097cf1f9.jpg](../nips_results/561_Frame%20Context%20Packing%20and%20Drift%20Prevention%20in%20Next-Frame-Prediction%20Video%20Diffusion%20Models/images/621edb1d0d870943503804ae86b29a0494ab5c6fcb04b343d964dac2097cf1f9.jpg)

![a230efb15886153f9cf841cdf0240b3c85741dc4ffdfce437ffcec8af590f3d3.jpg](../nips_results/561_Frame%20Context%20Packing%20and%20Drift%20Prevention%20in%20Next-Frame-Prediction%20Video%20Diffusion%20Models/images/a230efb15886153f9cf841cdf0240b3c85741dc4ffdfce437ffcec8af590f3d3.jpg)

### Tables

![acf24fb9e0ce86aff8ac5412233b5dc9255615f76d586601452ba59a71d304c5.jpg](../nips_results/561_Frame%20Context%20Packing%20and%20Drift%20Prevention%20in%20Next-Frame-Prediction%20Video%20Diffusion%20Models/tables/acf24fb9e0ce86aff8ac5412233b5dc9255615f76d586601452ba59a71d304c5.jpg)

![f5bd0fee43a4e0c1d02b1f996e668c876177f32f8c98e00004046d1d64011211.jpg](../nips_results/561_Frame%20Context%20Packing%20and%20Drift%20Prevention%20in%20Next-Frame-Prediction%20Video%20Diffusion%20Models/tables/f5bd0fee43a4e0c1d02b1f996e668c876177f32f8c98e00004046d1d64011211.jpg)

## Multi-agent Markov Entanglement


### Images

![0d3d7fb588e5f57a6b493f849b3c7727f5ba2c82b13001777dfd33a506de653d.jpg](../nips_results/562_Multi-agent%20Markov%20Entanglement/images/0d3d7fb588e5f57a6b493f849b3c7727f5ba2c82b13001777dfd33a506de653d.jpg)

![306702f05ff8ff4835559e512c6bae0b8b18a2a13a4d3344970bc3b1d50b27f9.jpg](../nips_results/562_Multi-agent%20Markov%20Entanglement/images/306702f05ff8ff4835559e512c6bae0b8b18a2a13a4d3344970bc3b1d50b27f9.jpg)

![509e01b9f12c458209e8cca7447ffc09050db94b0c9afb06e507cc34960deda1.jpg](../nips_results/562_Multi-agent%20Markov%20Entanglement/images/509e01b9f12c458209e8cca7447ffc09050db94b0c9afb06e507cc34960deda1.jpg)

### Tables

![d54b93e55a35cdb2987b7122e139327ae508fd1ed0f92fc130161c77dab73261.jpg](../nips_results/562_Multi-agent%20Markov%20Entanglement/tables/d54b93e55a35cdb2987b7122e139327ae508fd1ed0f92fc130161c77dab73261.jpg)

## On the sample complexity of semi-supervised multi-objective learning


### Images

![9062b52408da10f5fb55b72947d1d7c4ffa25cecf446de20b535b6d90ac072d9.jpg](../nips_results/563_On%20the%20sample%20complexity%20of%20semi-supervised%20multi-objective%20learning/images/9062b52408da10f5fb55b72947d1d7c4ffa25cecf446de20b535b6d90ac072d9.jpg)

![9083e098ee841ce857a18cf9739b3ea1faefff4d8ecd4e2ea16c0c4828b8887c.jpg](../nips_results/563_On%20the%20sample%20complexity%20of%20semi-supervised%20multi-objective%20learning/images/9083e098ee841ce857a18cf9739b3ea1faefff4d8ecd4e2ea16c0c4828b8887c.jpg)

![96f2575a0a5ec73f05101ac8bed7a4232e4727b5a9f58dba40b2c24450f9beab.jpg](../nips_results/563_On%20the%20sample%20complexity%20of%20semi-supervised%20multi-objective%20learning/images/96f2575a0a5ec73f05101ac8bed7a4232e4727b5a9f58dba40b2c24450f9beab.jpg)

![c59b9d0c80ede475423fd2e3c59b8849e5ce149f096c4d3d15127b5139579fd7.jpg](../nips_results/563_On%20the%20sample%20complexity%20of%20semi-supervised%20multi-objective%20learning/images/c59b9d0c80ede475423fd2e3c59b8849e5ce149f096c4d3d15127b5139579fd7.jpg)

![f73ee3ca2270c1a99a7970125584118c7e38e58b1290a7b0b9a3d9c4f85537bf.jpg](../nips_results/563_On%20the%20sample%20complexity%20of%20semi-supervised%20multi-objective%20learning/images/f73ee3ca2270c1a99a7970125584118c7e38e58b1290a7b0b9a3d9c4f85537bf.jpg)

### Tables

![07c10c3cfe870b5a5135a26f4ef3248e12f646bed508b6c1c21233e391f6c0f7.jpg](../nips_results/563_On%20the%20sample%20complexity%20of%20semi-supervised%20multi-objective%20learning/tables/07c10c3cfe870b5a5135a26f4ef3248e12f646bed508b6c1c21233e391f6c0f7.jpg)

![870b0767700cd4ed6f28159962b153fa3e8600f91ddb15a7300ab7ee3d34e49a.jpg](../nips_results/563_On%20the%20sample%20complexity%20of%20semi-supervised%20multi-objective%20learning/tables/870b0767700cd4ed6f28159962b153fa3e8600f91ddb15a7300ab7ee3d34e49a.jpg)

## LODGE: Level-of-Detail Large-Scale Gaussian Splatting with Efficient Rendering


### Images

![63319f4e91a07f89ce9f2324318c874baf7c3cad7af5d54960376ba1f2273190.jpg](../nips_results/564_LODGE_%20Level-of-Detail%20Large-Scale%20Gaussian%20Splatting%20with%20Efficient%20Rendering/images/63319f4e91a07f89ce9f2324318c874baf7c3cad7af5d54960376ba1f2273190.jpg)

![9458e38e744821934b8fa85775db08f5ff5d8e1533e714948cce83046ddbc584.jpg](../nips_results/564_LODGE_%20Level-of-Detail%20Large-Scale%20Gaussian%20Splatting%20with%20Efficient%20Rendering/images/9458e38e744821934b8fa85775db08f5ff5d8e1533e714948cce83046ddbc584.jpg)

![b159d04d55026ef54802b33449925e35f58c1afbc6646df91218f81f08bb49e3.jpg](../nips_results/564_LODGE_%20Level-of-Detail%20Large-Scale%20Gaussian%20Splatting%20with%20Efficient%20Rendering/images/b159d04d55026ef54802b33449925e35f58c1afbc6646df91218f81f08bb49e3.jpg)

![b1b8f8dad33712faaa768751bb16144b84c48eaccd9dcc2eabac360bd9f83c28.jpg](../nips_results/564_LODGE_%20Level-of-Detail%20Large-Scale%20Gaussian%20Splatting%20with%20Efficient%20Rendering/images/b1b8f8dad33712faaa768751bb16144b84c48eaccd9dcc2eabac360bd9f83c28.jpg)

![ee75e7270031a55bec3f69f39222f0c15ae3daec9e2227d5ad80c030fcccc42a.jpg](../nips_results/564_LODGE_%20Level-of-Detail%20Large-Scale%20Gaussian%20Splatting%20with%20Efficient%20Rendering/images/ee75e7270031a55bec3f69f39222f0c15ae3daec9e2227d5ad80c030fcccc42a.jpg)

![fb6415d53118a68fa323776a70ea2faf054dbed64016b61c4c657dad594a319d.jpg](../nips_results/564_LODGE_%20Level-of-Detail%20Large-Scale%20Gaussian%20Splatting%20with%20Efficient%20Rendering/images/fb6415d53118a68fa323776a70ea2faf054dbed64016b61c4c657dad594a319d.jpg)

![fdcbbbf6409037f1aaebd5746f7b38fc71ea78ee9a06c6b7745a25b18faa0805.jpg](../nips_results/564_LODGE_%20Level-of-Detail%20Large-Scale%20Gaussian%20Splatting%20with%20Efficient%20Rendering/images/fdcbbbf6409037f1aaebd5746f7b38fc71ea78ee9a06c6b7745a25b18faa0805.jpg)

### Tables

![ab2b26075ec0e5c844e43a5258b27bc6ec593643e40e2aa41234723902871681.jpg](../nips_results/564_LODGE_%20Level-of-Detail%20Large-Scale%20Gaussian%20Splatting%20with%20Efficient%20Rendering/tables/ab2b26075ec0e5c844e43a5258b27bc6ec593643e40e2aa41234723902871681.jpg)

![b39a17aae4fb7b9dda2ef1eb9df39172bbd0c080d7c8dd338d7c6b1edd534ffb.jpg](../nips_results/564_LODGE_%20Level-of-Detail%20Large-Scale%20Gaussian%20Splatting%20with%20Efficient%20Rendering/tables/b39a17aae4fb7b9dda2ef1eb9df39172bbd0c080d7c8dd338d7c6b1edd534ffb.jpg)

![e31e3a01e6c8861e96e0689037bd05351aebacf79a9ffc5b4ec3c5eab7837a91.jpg](../nips_results/564_LODGE_%20Level-of-Detail%20Large-Scale%20Gaussian%20Splatting%20with%20Efficient%20Rendering/tables/e31e3a01e6c8861e96e0689037bd05351aebacf79a9ffc5b4ec3c5eab7837a91.jpg)

![f78d6783e2fba7ec99d5d0f06557c60772a8882a5ca91d9d25d1ee7562347fe5.jpg](../nips_results/564_LODGE_%20Level-of-Detail%20Large-Scale%20Gaussian%20Splatting%20with%20Efficient%20Rendering/tables/f78d6783e2fba7ec99d5d0f06557c60772a8882a5ca91d9d25d1ee7562347fe5.jpg)

## Quantum speedup of non-linear Monte Carlo problems


### Tables

![1e58a1b7c1298564aa307ce0a787bfa81c9ba8b6480cf0eb2c395a66f420f7b1.jpg](../nips_results/565_Quantum%20speedup%20of%20non-linear%20Monte%20Carlo%20problems/tables/1e58a1b7c1298564aa307ce0a787bfa81c9ba8b6480cf0eb2c395a66f420f7b1.jpg)

![391b6588406e41a2bffe9542a68f3b76eae1b8a5b9488d97a933c55e33f6b7c3.jpg](../nips_results/565_Quantum%20speedup%20of%20non-linear%20Monte%20Carlo%20problems/tables/391b6588406e41a2bffe9542a68f3b76eae1b8a5b9488d97a933c55e33f6b7c3.jpg)

![440db5fadba1b57adb0d4275ae4cc426f6892e5994bd07238467da2284f32214.jpg](../nips_results/565_Quantum%20speedup%20of%20non-linear%20Monte%20Carlo%20problems/tables/440db5fadba1b57adb0d4275ae4cc426f6892e5994bd07238467da2284f32214.jpg)

## On Transferring Transferability: Towards a Theory for Size Generalization


### Images

![06f387daa3ea3f7afb87598b492930dfd9d890e10bd7bd7e55f4488a6e95ec06.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/images/06f387daa3ea3f7afb87598b492930dfd9d890e10bd7bd7e55f4488a6e95ec06.jpg)

![4a6b27ca70adf4000349b520a514e0c7a5056ee67b94deb23e14668a41c0b9dd.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/images/4a6b27ca70adf4000349b520a514e0c7a5056ee67b94deb23e14668a41c0b9dd.jpg)

![6683c22c312a9ba480cb590ae63cd3e676bf20efa7a4955a4bff6b2c00c98c56.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/images/6683c22c312a9ba480cb590ae63cd3e676bf20efa7a4955a4bff6b2c00c98c56.jpg)

![689c7c4ae4ab9a912fa76eefd715ef1aa882ee0908a17f5cbfb9f370d884101e.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/images/689c7c4ae4ab9a912fa76eefd715ef1aa882ee0908a17f5cbfb9f370d884101e.jpg)

![7592dbd6a0d715c14c470bb6510c49c84dfbe9a1ec4665b5330ae2964dbd2415.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/images/7592dbd6a0d715c14c470bb6510c49c84dfbe9a1ec4665b5330ae2964dbd2415.jpg)

![819f9fc0f31927260e1e95fb4c2cb3cfd99e2f2af42268d1330557c038966b13.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/images/819f9fc0f31927260e1e95fb4c2cb3cfd99e2f2af42268d1330557c038966b13.jpg)

![a7020021d2dfa3056fd09c17137821d9ad7ad0e9b806874e83c8366cdd51b791.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/images/a7020021d2dfa3056fd09c17137821d9ad7ad0e9b806874e83c8366cdd51b791.jpg)

![ae8d68356b9d025643fa06d3fedbf043c80e3df011f392424b7669decad891cc.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/images/ae8d68356b9d025643fa06d3fedbf043c80e3df011f392424b7669decad891cc.jpg)

![f5f8dbcd479684b05b0614c24c65b6a0fe937ddf111136a81b2f1dfaed5e7443.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/images/f5f8dbcd479684b05b0614c24c65b6a0fe937ddf111136a81b2f1dfaed5e7443.jpg)

![ff7d638bd4d6c55d2802d9b6ca4a68ca99bb4e9176eb2b2d75d64b98bc2fa62a.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/images/ff7d638bd4d6c55d2802d9b6ca4a68ca99bb4e9176eb2b2d75d64b98bc2fa62a.jpg)

### Tables

![b4042dc51d2f2fc16af971e57c80b2be7ce97fa00319e9bc0e12882cb75c1ff8.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/tables/b4042dc51d2f2fc16af971e57c80b2be7ce97fa00319e9bc0e12882cb75c1ff8.jpg)

![fa2cb0afcad5dd524e177975db703af5604e226e77e19b6fd5948fc327ca53f0.jpg](../nips_results/566_On%20Transferring%20Transferability_%20Towards%20a%20Theory%20for%20Size%20Generalization/tables/fa2cb0afcad5dd524e177975db703af5604e226e77e19b6fd5948fc327ca53f0.jpg)

## BevSplat: Resolving Height Ambiguity via Feature-Based Gaussian Primitives for Weakly-Supervised Cross-View Localization


### Images

![1ee00d1fb32b875ff223daf9fa9d4376e432dfa3023effaa2b7499ee52366c90.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/images/1ee00d1fb32b875ff223daf9fa9d4376e432dfa3023effaa2b7499ee52366c90.jpg)

![293b367eeba3bfca55c48504a3e04f1ff94291c1aeda0bae13d849191e6f7084.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/images/293b367eeba3bfca55c48504a3e04f1ff94291c1aeda0bae13d849191e6f7084.jpg)

![2c7af1c9628a977d8a047407f10c860a7968b023e7b41db5c72ff50e4a74dfe4.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/images/2c7af1c9628a977d8a047407f10c860a7968b023e7b41db5c72ff50e4a74dfe4.jpg)

![57abb97f7c282463ba5af50bd69dc1a83bc64c743c348da755af8798e763daba.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/images/57abb97f7c282463ba5af50bd69dc1a83bc64c743c348da755af8798e763daba.jpg)

![5faac362a553db7951c466ede63b5c41f104ab64b2e090dd72e1fd8c303504ad.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/images/5faac362a553db7951c466ede63b5c41f104ab64b2e090dd72e1fd8c303504ad.jpg)

![608a34204064f3637ecdd43a16756118b643732c358d8cb4f58d478f78923845.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/images/608a34204064f3637ecdd43a16756118b643732c358d8cb4f58d478f78923845.jpg)

![67b29e9366d4efc6a11533af1c6143a59a959068c5a09e800e4640ec4624c700.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/images/67b29e9366d4efc6a11533af1c6143a59a959068c5a09e800e4640ec4624c700.jpg)

![a8331d7a8730d2f09ad6fc49f9b8a2d75ad13192be31bd73dcb2c815b8158115.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/images/a8331d7a8730d2f09ad6fc49f9b8a2d75ad13192be31bd73dcb2c815b8158115.jpg)

![b6a672b339b70be19bd1dfbd0f3ba714300a1170f22e5d645452e160febd98fc.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/images/b6a672b339b70be19bd1dfbd0f3ba714300a1170f22e5d645452e160febd98fc.jpg)

![cf63aad45580ec8ab8a93b7a5b93b77e39e6378a3c6cd80400c53bbecf00bea3.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/images/cf63aad45580ec8ab8a93b7a5b93b77e39e6378a3c6cd80400c53bbecf00bea3.jpg)

### Tables

![1bda27fc5f51c80e89c0d0f371f743686e4615740341d62548f93d5f263bf8ce.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/1bda27fc5f51c80e89c0d0f371f743686e4615740341d62548f93d5f263bf8ce.jpg)

![22ed3318e05a6cf6713568d58aa6b0b6152c1a1396177de84c384e896fca88b9.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/22ed3318e05a6cf6713568d58aa6b0b6152c1a1396177de84c384e896fca88b9.jpg)

![2738bfef453fbb99abcd892007dae1aa5f8a3958ffcc80f551b275995c594750.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/2738bfef453fbb99abcd892007dae1aa5f8a3958ffcc80f551b275995c594750.jpg)

![2a52cc84de84c11fb5ad75cfd033d76ef4694c3bcf5cac017e2bed453971fca9.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/2a52cc84de84c11fb5ad75cfd033d76ef4694c3bcf5cac017e2bed453971fca9.jpg)

![3381a224d7a8ae661b1efcf348b75f14a76703be4ec47e1e06881f91cf9ee085.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/3381a224d7a8ae661b1efcf348b75f14a76703be4ec47e1e06881f91cf9ee085.jpg)

![3d72b995f48a4bdbdf2d7645886f29fe55d8203ef0ced5bf8061bc36a4207f17.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/3d72b995f48a4bdbdf2d7645886f29fe55d8203ef0ced5bf8061bc36a4207f17.jpg)

![6214ce7c5722ac4f48c532899779e347622bbaff836aba2e3ab73d4e92202c3d.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/6214ce7c5722ac4f48c532899779e347622bbaff836aba2e3ab73d4e92202c3d.jpg)

![90bd66a5399838b9edcfaad36ad0bc73d6f1b28648883e24f246a839e3786656.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/90bd66a5399838b9edcfaad36ad0bc73d6f1b28648883e24f246a839e3786656.jpg)

![a90007093331adab5c5effbf78b3b54191ef68f333d2bc8373bad4564f9d91b0.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/a90007093331adab5c5effbf78b3b54191ef68f333d2bc8373bad4564f9d91b0.jpg)

![ad9c40d5450067ae9147124208da0b421b8752416ab898e441b0e23d4b0d1d87.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/ad9c40d5450067ae9147124208da0b421b8752416ab898e441b0e23d4b0d1d87.jpg)

![cf7db6703a6d4326af17263caa424ccca1be9e8427390a2bf026ca1bc2740320.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/cf7db6703a6d4326af17263caa424ccca1be9e8427390a2bf026ca1bc2740320.jpg)

![da6b7cd2824cf96850f64239faeece20c9f65c2a394af52b735227151772c78d.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/da6b7cd2824cf96850f64239faeece20c9f65c2a394af52b735227151772c78d.jpg)

![e2aa875e09267a6561463a4c846c1f0a20ca63289850180cea619e800bfbc02e.jpg](../nips_results/567_BevSplat_%20Resolving%20Height%20Ambiguity%20via%20Feature-Based%20Gaussian%20Primitives%20for%20Weakly-Supervised%20Cro/tables/e2aa875e09267a6561463a4c846c1f0a20ca63289850180cea619e800bfbc02e.jpg)

## Error Broadcast and Decorrelation as a Potential Artificial and Natural Learning Mechanism


### Images

![21185116e1182928911420a9d7a63ac1d5137aea013738715ed83df4ba065bc7.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/21185116e1182928911420a9d7a63ac1d5137aea013738715ed83df4ba065bc7.jpg)

![21b9db7ea9632440894cbade24427ebe3440c49466eac21e3f07b66a3533913f.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/21b9db7ea9632440894cbade24427ebe3440c49466eac21e3f07b66a3533913f.jpg)

![38e6e8a76bb531e3f25116e6f173f2876008b1b4e5ceb3a5b27f90fbabaae4d3.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/38e6e8a76bb531e3f25116e6f173f2876008b1b4e5ceb3a5b27f90fbabaae4d3.jpg)

![44323e3b363bf60b5a07fd71141e996b43e76e4a49cf34fb7a1e14c69d8962a1.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/44323e3b363bf60b5a07fd71141e996b43e76e4a49cf34fb7a1e14c69d8962a1.jpg)

![559595550432f432ebb2e1691544423e4524f8a414bcc4316bb0cc36eb469521.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/559595550432f432ebb2e1691544423e4524f8a414bcc4316bb0cc36eb469521.jpg)

![5ce461ae5c74a2eda259cc5fe5c9877251d514dad28fc027bf451e3b6d3e46c7.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/5ce461ae5c74a2eda259cc5fe5c9877251d514dad28fc027bf451e3b6d3e46c7.jpg)

![769b23b02efb35daa4149023c136dfd2eece6339acd9b449be60eb4a7a390653.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/769b23b02efb35daa4149023c136dfd2eece6339acd9b449be60eb4a7a390653.jpg)

![96b091e1da7761033529a7b03a6971856b962e9a45cd0fd493e43ab8e82a5b0c.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/96b091e1da7761033529a7b03a6971856b962e9a45cd0fd493e43ab8e82a5b0c.jpg)

![9f3a2ad5e25d479a84020bc69bc4c2f0d220dc3c2847258dcffd72c3d3849066.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/9f3a2ad5e25d479a84020bc69bc4c2f0d220dc3c2847258dcffd72c3d3849066.jpg)

![cd6bb25da814ecf6d7a5705d44316c290cba4ac8a2887f4c4b72a466fae6970a.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/cd6bb25da814ecf6d7a5705d44316c290cba4ac8a2887f4c4b72a466fae6970a.jpg)

![d342099e451a7f8a9ea7c1fa7d414e11768dab2d22a7deb3e6fd9727982f8e2d.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/d342099e451a7f8a9ea7c1fa7d414e11768dab2d22a7deb3e6fd9727982f8e2d.jpg)

![e697ba9c86aa84bae75e3867a5c40acd760ef30ec06e3680919e73640a1720ca.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/images/e697ba9c86aa84bae75e3867a5c40acd760ef30ec06e3680919e73640a1720ca.jpg)

### Tables

![142c43509d999b99f0dc28cee8a6e169a1845b9c85bc5ae69188d06ada8c5466.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/142c43509d999b99f0dc28cee8a6e169a1845b9c85bc5ae69188d06ada8c5466.jpg)

![1fbe57735933ef22379b9df5298a5ce9fb715d0085200bd2d48864408869954f.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/1fbe57735933ef22379b9df5298a5ce9fb715d0085200bd2d48864408869954f.jpg)

![366f8c8e09f313aebc8cec45b647703f5c1845101b62789e8fb45c74a124f51b.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/366f8c8e09f313aebc8cec45b647703f5c1845101b62789e8fb45c74a124f51b.jpg)

![3ba25f9a5d7c3e49317e1a38406b0ca4d5f9fe7f8c61b2a263a4c624195637d9.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/3ba25f9a5d7c3e49317e1a38406b0ca4d5f9fe7f8c61b2a263a4c624195637d9.jpg)

![42d2b7c8b2610bec0fda6ca5501a983dc13cfbeb467bca0da7450d4422894744.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/42d2b7c8b2610bec0fda6ca5501a983dc13cfbeb467bca0da7450d4422894744.jpg)

![49df9f08fe6896e9534d021f28c1d13bce34310e58315f97f5d7a78246234694.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/49df9f08fe6896e9534d021f28c1d13bce34310e58315f97f5d7a78246234694.jpg)

![6330e446589c866e5668d4de03fd4bcdfb44f5e32909737a39789c0ba4eb58b7.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/6330e446589c866e5668d4de03fd4bcdfb44f5e32909737a39789c0ba4eb58b7.jpg)

![6c629f9c04173ee691932c89bc3f507f9ef7ee5c10d0dfa9d452493273f62fa5.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/6c629f9c04173ee691932c89bc3f507f9ef7ee5c10d0dfa9d452493273f62fa5.jpg)

![6fd223145c0c08ab563cb067d074b11079d6dcac2f4a333cd2de6da3e69c8e93.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/6fd223145c0c08ab563cb067d074b11079d6dcac2f4a333cd2de6da3e69c8e93.jpg)

![8161271fdc559381608dbf59ae2a9b58c68cbbaa50d06cddcc6b73c6fdc2a3ef.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/8161271fdc559381608dbf59ae2a9b58c68cbbaa50d06cddcc6b73c6fdc2a3ef.jpg)

![85072f46eb1226eaf74de035a9a9cf6f59062c60db7c31d0726d1754aaae0064.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/85072f46eb1226eaf74de035a9a9cf6f59062c60db7c31d0726d1754aaae0064.jpg)

![88f73d4ac3e490a9244aeb6fc2a5f63c6296342d5a93649fe1660d6fc99bdacf.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/88f73d4ac3e490a9244aeb6fc2a5f63c6296342d5a93649fe1660d6fc99bdacf.jpg)

![941fb4c2f0032899cde0fc91c022567401ebd336c165bc95ce8157cc8daf2f56.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/941fb4c2f0032899cde0fc91c022567401ebd336c165bc95ce8157cc8daf2f56.jpg)

![9d784751f18eca1195edbbe7c665db77ef31ee5a21adcd807bd85b7a038500ea.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/9d784751f18eca1195edbbe7c665db77ef31ee5a21adcd807bd85b7a038500ea.jpg)

![a74385a19a8e6d482a924c826b1ba3d93e1bc31e6a78cd03facc6cfad7927275.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/a74385a19a8e6d482a924c826b1ba3d93e1bc31e6a78cd03facc6cfad7927275.jpg)

![a75bb3b707d189f095a078caeaff136d9f490bcdacebe9464cba4bdb75f295eb.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/a75bb3b707d189f095a078caeaff136d9f490bcdacebe9464cba4bdb75f295eb.jpg)

![aa94692dbc5502e0a880cfd240c1e19d38e755a4811e13ff052fd5cadb868bf3.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/aa94692dbc5502e0a880cfd240c1e19d38e755a4811e13ff052fd5cadb868bf3.jpg)

![b8bff57ceffd2bf119c7f4e79e9be31d796383039793fb43731d8d61d2ff0330.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/b8bff57ceffd2bf119c7f4e79e9be31d796383039793fb43731d8d61d2ff0330.jpg)

![c1b8ff2f25569376baddeb7bc738772a24139b5c084685bd4fae426b5846c169.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/c1b8ff2f25569376baddeb7bc738772a24139b5c084685bd4fae426b5846c169.jpg)

![d1b031c75a1b77b9a55cd29161f43e5c7402cf6cec928afeabd51af1d9eca9cd.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/d1b031c75a1b77b9a55cd29161f43e5c7402cf6cec928afeabd51af1d9eca9cd.jpg)

![ec2d88b53ae8df2d7470ba7193211e5dd33ca01ce8740b79f86e2d0aafcc25ad.jpg](../nips_results/569_Error%20Broadcast%20and%20Decorrelation%20as%20a%20Potential%20Artificial%20and%20Natural%20Learning%20Mechanism/tables/ec2d88b53ae8df2d7470ba7193211e5dd33ca01ce8740b79f86e2d0aafcc25ad.jpg)

## Two‑Stage Learning of Stabilizing Neural Controllers via Zubov Sampling and Iterative Domain Expansion


### Images

![1723e8a76f68c9cdc936b0ce6eeb5bf9aedd28d3d6508545bb51377edb89ba92.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/images/1723e8a76f68c9cdc936b0ce6eeb5bf9aedd28d3d6508545bb51377edb89ba92.jpg)

![2171a384870c7dcb739f9f2e48311ef9d299e29ccb41ed14ae7095fe630820d2.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/images/2171a384870c7dcb739f9f2e48311ef9d299e29ccb41ed14ae7095fe630820d2.jpg)

![2fb01edac9fcd8741b7d58e65a6ca0805fd8ab7965d722220563510b41e872b0.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/images/2fb01edac9fcd8741b7d58e65a6ca0805fd8ab7965d722220563510b41e872b0.jpg)

![58e990f580a8233a5be5a93af17d06875c6ce2033bc1f321a9d1989adf7bde03.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/images/58e990f580a8233a5be5a93af17d06875c6ce2033bc1f321a9d1989adf7bde03.jpg)

![ba2683f36a792a6002825173914c7bbb4b65b0f3c25a19d9afa4673f437008e6.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/images/ba2683f36a792a6002825173914c7bbb4b65b0f3c25a19d9afa4673f437008e6.jpg)

![e0febd543be8b88abf6beb61665ded6db5ad8db73281727850e7c46ec08debb9.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/images/e0febd543be8b88abf6beb61665ded6db5ad8db73281727850e7c46ec08debb9.jpg)

![ef976984e658835d870e4657b2436c7d1fa60fee64d2827173716505e2b022d1.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/images/ef976984e658835d870e4657b2436c7d1fa60fee64d2827173716505e2b022d1.jpg)

### Tables

![05ac86083e1c8ed0d9bc1b3c16438162ad80e95c3be287b2103fb0a4329bd49a.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/tables/05ac86083e1c8ed0d9bc1b3c16438162ad80e95c3be287b2103fb0a4329bd49a.jpg)

![3040fe62909d02a47e03c5b965abc7eb4f6c38051c7b78fa6893d5a1867cc2af.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/tables/3040fe62909d02a47e03c5b965abc7eb4f6c38051c7b78fa6893d5a1867cc2af.jpg)

![470d3e603af095d9a9e102c3dd370627bbc3998889e633f1b2a0f0009e3fead9.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/tables/470d3e603af095d9a9e102c3dd370627bbc3998889e633f1b2a0f0009e3fead9.jpg)

![49920f365f8713409d7a22191cf48ec5ef124388cbe887d0d2395b86b67681ca.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/tables/49920f365f8713409d7a22191cf48ec5ef124388cbe887d0d2395b86b67681ca.jpg)

![6169a92726e7cd5e430b786c86e0d2beea0e612ee1b6611dc34137eeb02cf616.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/tables/6169a92726e7cd5e430b786c86e0d2beea0e612ee1b6611dc34137eeb02cf616.jpg)

![87e69544e202641b6d7cda0c69b4f98a777d32871b77db2dee08d2852254ebd4.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/tables/87e69544e202641b6d7cda0c69b4f98a777d32871b77db2dee08d2852254ebd4.jpg)

![8d3d4ab60d849f5470edd24a02428a34563f3226b350d12b111ea83146498ef0.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/tables/8d3d4ab60d849f5470edd24a02428a34563f3226b350d12b111ea83146498ef0.jpg)

![e053e07d284a209c088470af08070572092c986476bbc724e1ff400d2bf2f7ed.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/tables/e053e07d284a209c088470af08070572092c986476bbc724e1ff400d2bf2f7ed.jpg)

![e9530ad593c9d1f74d9e8d63f0c10a1accabb4da7abe111dd330e2024b651c25.jpg](../nips_results/570_Two%E2%80%91Stage%20Learning%20of%20Stabilizing%20Neural%20Controllers%20via%20Zubov%20Sampling%20and%20Iterative%20Domain%20Expansi/tables/e9530ad593c9d1f74d9e8d63f0c10a1accabb4da7abe111dd330e2024b651c25.jpg)

## AlphaZero Neural Scaling and Zipf's Law: a Tale of Board Games and Power Laws


### Images

![2a7e90dc4548a0a334145eddc5064666b46cfd9ba4ef11e4b20ab217a6eb609a.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/2a7e90dc4548a0a334145eddc5064666b46cfd9ba4ef11e4b20ab217a6eb609a.jpg)

![3040ddecdc33fdd48a3af80f1e93dc36590d33ff31930f6f731d3b9eaf638487.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/3040ddecdc33fdd48a3af80f1e93dc36590d33ff31930f6f731d3b9eaf638487.jpg)

![31cc1b16fa7f26442c797a6bbc7683de4ead5888d56e4edc45464de7358e312c.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/31cc1b16fa7f26442c797a6bbc7683de4ead5888d56e4edc45464de7358e312c.jpg)

![37636cf154d3e53dcccb7eb84a79ff79139a0c1c295be6830931b86b74ccd5e9.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/37636cf154d3e53dcccb7eb84a79ff79139a0c1c295be6830931b86b74ccd5e9.jpg)

![3fc897da021f0fafe1de25f6176e44c25d962f8f8cfea0b78e77fb3245eb05f7.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/3fc897da021f0fafe1de25f6176e44c25d962f8f8cfea0b78e77fb3245eb05f7.jpg)

![5ca3a8872b352b49fb92193408af87542632bfbe33c2cbd5f117b941894afbad.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/5ca3a8872b352b49fb92193408af87542632bfbe33c2cbd5f117b941894afbad.jpg)

![5d575762272f36d474f02a2ac49752ef8639d4fca8e80edad0d9ba6b466d3467.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/5d575762272f36d474f02a2ac49752ef8639d4fca8e80edad0d9ba6b466d3467.jpg)

![673c9d9784037377b5409d2e1f7d33ba9b27009d0eb8c95a2b711f2c4ac50709.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/673c9d9784037377b5409d2e1f7d33ba9b27009d0eb8c95a2b711f2c4ac50709.jpg)

![69972a3764190c6188594472d51722d4c4893ed3ec8fa93f5f89a8d5b612bd71.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/69972a3764190c6188594472d51722d4c4893ed3ec8fa93f5f89a8d5b612bd71.jpg)

![6db674853fef43038a87b9232f5c68b30a804e9cc900379a009fc324ec4fc341.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/6db674853fef43038a87b9232f5c68b30a804e9cc900379a009fc324ec4fc341.jpg)

![87f551161f1509e20a0dfd1de9f2082b8b1a06bcfa702245462557206459dc63.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/87f551161f1509e20a0dfd1de9f2082b8b1a06bcfa702245462557206459dc63.jpg)

![93396345badb9dee24dc151fe44840874593787557acf8f42bc368ce9efec6e9.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/93396345badb9dee24dc151fe44840874593787557acf8f42bc368ce9efec6e9.jpg)

![aa64ea2b0e2acd430ccbac72917970f4bec5940bd4691a2e9c5fbd4e9edef57b.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/aa64ea2b0e2acd430ccbac72917970f4bec5940bd4691a2e9c5fbd4e9edef57b.jpg)

![b80cf80218a48c4697605a60b33196186baa3531d64e233920c8f4d6fefa9db7.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/b80cf80218a48c4697605a60b33196186baa3531d64e233920c8f4d6fefa9db7.jpg)

![ce0b9e8ed35b42315fad4ce39f302c4bb36cd02a38f67c38dc6f8faa0a59fbca.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/ce0b9e8ed35b42315fad4ce39f302c4bb36cd02a38f67c38dc6f8faa0a59fbca.jpg)

![df6b34acb7951c74bc2ba0266da85c3616bf5c91de6e2699acaa256cb044efda.jpg](../nips_results/571_AlphaZero%20Neural%20Scaling%20and%20Zipf%27s%20Law_%20a%20Tale%20of%20Board%20Games%20and%20Power%20Laws/images/df6b34acb7951c74bc2ba0266da85c3616bf5c91de6e2699acaa256cb044efda.jpg)

## Adaptive 3D Reconstruction via Diffusion Priors and Forward Curvature-Matching Likelihood Updates


### Images

![038e514534ed0fc294be1152e867237e6be3c5c60e401d2b66a97ac43528f5d1.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/038e514534ed0fc294be1152e867237e6be3c5c60e401d2b66a97ac43528f5d1.jpg)

![0467daa817c391776227d34d6bb006c0c6a292c9ee059a133186fbebf901d929.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/0467daa817c391776227d34d6bb006c0c6a292c9ee059a133186fbebf901d929.jpg)

![2554462fa4a696f2b318b48ce07a0d24ae888d9b48dd4d39029a993f03491a13.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/2554462fa4a696f2b318b48ce07a0d24ae888d9b48dd4d39029a993f03491a13.jpg)

![34e195d3b9f5821f9d376ebf2c518b253b97eeff9c157588f607b3b845f371f2.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/34e195d3b9f5821f9d376ebf2c518b253b97eeff9c157588f607b3b845f371f2.jpg)

![3e509871de786c792de989fd71c4366f2a11251bd6037288104dbb117cd6b41d.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/3e509871de786c792de989fd71c4366f2a11251bd6037288104dbb117cd6b41d.jpg)

![45770ac8ac22d3752dbc42357a3e562eed23de4206a88a07513088e09325a558.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/45770ac8ac22d3752dbc42357a3e562eed23de4206a88a07513088e09325a558.jpg)

![4d6269c4542f9b1ca5518df94c5efeb685fa821d706955a5cafad59bcfd02bab.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/4d6269c4542f9b1ca5518df94c5efeb685fa821d706955a5cafad59bcfd02bab.jpg)

![4ed73f75e4cd3b006d57c64275753c5666630c54f447a4b055cd99068266f65f.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/4ed73f75e4cd3b006d57c64275753c5666630c54f447a4b055cd99068266f65f.jpg)

![6921ace5381fe55ad38871da627d9dc4c5a09f3e85ec8bf43d72884342e66e54.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/6921ace5381fe55ad38871da627d9dc4c5a09f3e85ec8bf43d72884342e66e54.jpg)

![72e59a0b045735901c73fb2b442c40c20f8fd4a7ccd775b5b28c62a6afa87fb1.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/72e59a0b045735901c73fb2b442c40c20f8fd4a7ccd775b5b28c62a6afa87fb1.jpg)

![746b6596cdf74ec60b677993b2e699b4171b07d6486e2883870fcea7e20c98c2.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/746b6596cdf74ec60b677993b2e699b4171b07d6486e2883870fcea7e20c98c2.jpg)

![75ebdf975d52dcf09f56debd0d1a39d28a4ec71e92c92eae4b4a6b6e74111fd4.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/75ebdf975d52dcf09f56debd0d1a39d28a4ec71e92c92eae4b4a6b6e74111fd4.jpg)

![7d33e76d9b7f21e8e2af8535d466801a307a8b35df7d5813895d4c83002c7ccc.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/7d33e76d9b7f21e8e2af8535d466801a307a8b35df7d5813895d4c83002c7ccc.jpg)

![a032cc56c6ab79be4c6ec7e00db2c7145834b9ae83f88520bf3de0ea9dd39eaa.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/a032cc56c6ab79be4c6ec7e00db2c7145834b9ae83f88520bf3de0ea9dd39eaa.jpg)

![a96bc02ec68d6b3d47ef166a85965d419e0c0a49fc89da9402a7b87b93351998.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/a96bc02ec68d6b3d47ef166a85965d419e0c0a49fc89da9402a7b87b93351998.jpg)

![aa1dc2bc9fa16d8fe8cea7676a7e4d58f89d3eaa3357fc4b4570bce446d31bb0.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/aa1dc2bc9fa16d8fe8cea7676a7e4d58f89d3eaa3357fc4b4570bce446d31bb0.jpg)

![b1f8669ace501ac03ea6a9a0a9ab7233d9834c15c3dcd1afd7d9de4b241cb84d.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/b1f8669ace501ac03ea6a9a0a9ab7233d9834c15c3dcd1afd7d9de4b241cb84d.jpg)

![b20480a2d24744dde1cf67c8c72f039ccb0a3a75687a82e26805446f8e0e433c.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/b20480a2d24744dde1cf67c8c72f039ccb0a3a75687a82e26805446f8e0e433c.jpg)

![c12d217ca607c4d206f5a09159650a447c3b2179b5d67a0df0f93ed413a5825e.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/c12d217ca607c4d206f5a09159650a447c3b2179b5d67a0df0f93ed413a5825e.jpg)

![d3cb0020324a32f38c1ce7cfe7e47b068927971f9aabd8813b090f270562fbdc.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/d3cb0020324a32f38c1ce7cfe7e47b068927971f9aabd8813b090f270562fbdc.jpg)

![f800e1a692010ea6b4c09c64196dfaf73d1ff9c406a0e2fef3ee2422dfaadda1.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/images/f800e1a692010ea6b4c09c64196dfaf73d1ff9c406a0e2fef3ee2422dfaadda1.jpg)

### Tables

![03922bb72563de9f182195154e884cfa75d442500ed392f533f8655a7540893f.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/tables/03922bb72563de9f182195154e884cfa75d442500ed392f533f8655a7540893f.jpg)

![5f7e5dd62c607309d6d3ed440fa343e418e3ba267d9aaff3a56c7bd57332da9c.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/tables/5f7e5dd62c607309d6d3ed440fa343e418e3ba267d9aaff3a56c7bd57332da9c.jpg)

![62e2be96ae9d7b3343ef256e481604a3450e641f20f2fd2b63c614aa357a929c.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/tables/62e2be96ae9d7b3343ef256e481604a3450e641f20f2fd2b63c614aa357a929c.jpg)

![76d62e99b0c197e7c28cdced6013c8605d3c0731f1a581d45c8c0d83d8a470a1.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/tables/76d62e99b0c197e7c28cdced6013c8605d3c0731f1a581d45c8c0d83d8a470a1.jpg)

![82ed9eb54fa7afa6668d488e2452c778385773de83f41ef56f75b839cff5ca8c.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/tables/82ed9eb54fa7afa6668d488e2452c778385773de83f41ef56f75b839cff5ca8c.jpg)

![ba8b33daee5eebcb1aa4a98c985a046681f968c07c3ca8149e3b463e758284be.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/tables/ba8b33daee5eebcb1aa4a98c985a046681f968c07c3ca8149e3b463e758284be.jpg)

![da0550a4cb4de9e01863faa10248976fbf7e8c1b1266536b61d81a80fb61dd89.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/tables/da0550a4cb4de9e01863faa10248976fbf7e8c1b1266536b61d81a80fb61dd89.jpg)

![ec0f8c5b4b0ce3af198ea65b050b14bd84349d1ba5f30012b12a9a16faf98688.jpg](../nips_results/572_Adaptive%203D%20Reconstruction%20via%20Diffusion%20Priors%20and%20Forward%20Curvature-Matching%20Likelihood%20Updates/tables/ec0f8c5b4b0ce3af198ea65b050b14bd84349d1ba5f30012b12a9a16faf98688.jpg)

## Stable Part Diffusion 4D: Multi-View RGB and Kinematic Parts Video Generation


### Images

![3af4ce88f4c6d374f57228b10794b03d70cf2dbca2670134b66cbf695f727b80.jpg](../nips_results/574_Stable%20Part%20Diffusion%204D_%20Multi-View%20RGB%20and%20Kinematic%20Parts%20Video%20Generation/images/3af4ce88f4c6d374f57228b10794b03d70cf2dbca2670134b66cbf695f727b80.jpg)

![835c30442253101ceb49c5d89e2901893449249754bcf8edd8213de125cb3ed2.jpg](../nips_results/574_Stable%20Part%20Diffusion%204D_%20Multi-View%20RGB%20and%20Kinematic%20Parts%20Video%20Generation/images/835c30442253101ceb49c5d89e2901893449249754bcf8edd8213de125cb3ed2.jpg)

![8771d535bef952a625217283cb8dc1f452e589b66d6ca697f6b9887138033840.jpg](../nips_results/574_Stable%20Part%20Diffusion%204D_%20Multi-View%20RGB%20and%20Kinematic%20Parts%20Video%20Generation/images/8771d535bef952a625217283cb8dc1f452e589b66d6ca697f6b9887138033840.jpg)

![c2c816fec31adf06ac12573a3366f14f9d5de7a378b5f2d7b0aadb8f8e9c3d36.jpg](../nips_results/574_Stable%20Part%20Diffusion%204D_%20Multi-View%20RGB%20and%20Kinematic%20Parts%20Video%20Generation/images/c2c816fec31adf06ac12573a3366f14f9d5de7a378b5f2d7b0aadb8f8e9c3d36.jpg)

![d2dd66fbf1108f4d535be68cbed147c6ece4b90b15dd3877b1214709e8a09537.jpg](../nips_results/574_Stable%20Part%20Diffusion%204D_%20Multi-View%20RGB%20and%20Kinematic%20Parts%20Video%20Generation/images/d2dd66fbf1108f4d535be68cbed147c6ece4b90b15dd3877b1214709e8a09537.jpg)

![e0896edeadd3b6341794566a1e5f27b9b61f91d0db832026cb44a705d25e03be.jpg](../nips_results/574_Stable%20Part%20Diffusion%204D_%20Multi-View%20RGB%20and%20Kinematic%20Parts%20Video%20Generation/images/e0896edeadd3b6341794566a1e5f27b9b61f91d0db832026cb44a705d25e03be.jpg)

### Tables

![05b754b51e6533bb009b32da25a49b7951ef378f55cc8d86bd80d16e721e8319.jpg](../nips_results/574_Stable%20Part%20Diffusion%204D_%20Multi-View%20RGB%20and%20Kinematic%20Parts%20Video%20Generation/tables/05b754b51e6533bb009b32da25a49b7951ef378f55cc8d86bd80d16e721e8319.jpg)

![1f831ab2533811e5e40509f7f1d966542ba0df9fb338a2139c461ed5eab5d597.jpg](../nips_results/574_Stable%20Part%20Diffusion%204D_%20Multi-View%20RGB%20and%20Kinematic%20Parts%20Video%20Generation/tables/1f831ab2533811e5e40509f7f1d966542ba0df9fb338a2139c461ed5eab5d597.jpg)

![8d67769728f974b6dedaed83b0375f2fd182835d7bf2cf2d29932e284ac19c16.jpg](../nips_results/574_Stable%20Part%20Diffusion%204D_%20Multi-View%20RGB%20and%20Kinematic%20Parts%20Video%20Generation/tables/8d67769728f974b6dedaed83b0375f2fd182835d7bf2cf2d29932e284ac19c16.jpg)

![c72ec135fe431f35c30f7cec56349e43dfd7862ae88f79d532e1d8a182bc1941.jpg](../nips_results/574_Stable%20Part%20Diffusion%204D_%20Multi-View%20RGB%20and%20Kinematic%20Parts%20Video%20Generation/tables/c72ec135fe431f35c30f7cec56349e43dfd7862ae88f79d532e1d8a182bc1941.jpg)

## Chain-of-Zoom: Extreme Super-Resolution via Scale Autoregression and Preference Alignment


### Images

![00f9637e551273bcde2e63f02c06dc3bf13bee60db2b0b6070ba9c1258667fc1.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/00f9637e551273bcde2e63f02c06dc3bf13bee60db2b0b6070ba9c1258667fc1.jpg)

![0a964b22565442f975f38667d003449f7041f22f724d719daaa9845be445c22e.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/0a964b22565442f975f38667d003449f7041f22f724d719daaa9845be445c22e.jpg)

![13e94c7f5eecf405405d7b17a8da8e55bddc6c348c8b82f9d2509e7c4aeeff5c.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/13e94c7f5eecf405405d7b17a8da8e55bddc6c348c8b82f9d2509e7c4aeeff5c.jpg)

![1b9ea1d2f5621647b5a6d5219562ef55231be71dfdb44f977de7a6ca4612379f.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/1b9ea1d2f5621647b5a6d5219562ef55231be71dfdb44f977de7a6ca4612379f.jpg)

![1eefa488360e6aa84fb28af9ea6acfd13fe325debce455fa6beb4ad2ba2a21bc.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/1eefa488360e6aa84fb28af9ea6acfd13fe325debce455fa6beb4ad2ba2a21bc.jpg)

![44f587cc2fe773945e3fd00d5e8801cc137c715697879736612b55ca8476d1f4.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/44f587cc2fe773945e3fd00d5e8801cc137c715697879736612b55ca8476d1f4.jpg)

![454589fae4f8b9bed401a2ec155dd434efa2e871f738dd65b0795e037d0f045e.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/454589fae4f8b9bed401a2ec155dd434efa2e871f738dd65b0795e037d0f045e.jpg)

![537ef59768b046d55e7e9dcbbce6249df0fbad76a587188628254a35118d66c3.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/537ef59768b046d55e7e9dcbbce6249df0fbad76a587188628254a35118d66c3.jpg)

![59e9a39f92139f5de76ff87f337222ddd103b98f7a8628f0bdbd189085f66aac.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/59e9a39f92139f5de76ff87f337222ddd103b98f7a8628f0bdbd189085f66aac.jpg)

![5eef7b86d62e7a889f4ab219be328f7a07b1a4ce7ef51775ca9c5c09ddc1b058.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/5eef7b86d62e7a889f4ab219be328f7a07b1a4ce7ef51775ca9c5c09ddc1b058.jpg)

![69f4ee3e6f12aa0712cfec327863375266d995a9f8e5b052a733f02b5fa99743.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/69f4ee3e6f12aa0712cfec327863375266d995a9f8e5b052a733f02b5fa99743.jpg)

![8dbab9989b6d99a97406329e33e08617467c333727dd7a651bddd155fda4315d.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/8dbab9989b6d99a97406329e33e08617467c333727dd7a651bddd155fda4315d.jpg)

![ab4113397f12a646e6fd45833b3136391899263b07bb969560d5c6e4c749e83d.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/ab4113397f12a646e6fd45833b3136391899263b07bb969560d5c6e4c749e83d.jpg)

![ae5797af5048ebf090aa20ba4e85227160bc56ca9e8073aabc950ab4a5b68bd1.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/ae5797af5048ebf090aa20ba4e85227160bc56ca9e8073aabc950ab4a5b68bd1.jpg)

![b08a4174d652f6f1261afc5e8de94cb8bc289a454bdf245733e48dda3f7625c5.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/b08a4174d652f6f1261afc5e8de94cb8bc289a454bdf245733e48dda3f7625c5.jpg)

![b0c0dc846d6af72f64dd21755878aee2d89defef1b62f31204ac7d445ef6741e.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/b0c0dc846d6af72f64dd21755878aee2d89defef1b62f31204ac7d445ef6741e.jpg)

![b9f9f95bc015ffa98d6376c11530b49e27817af3060fe74eebbe1505c7892c72.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/b9f9f95bc015ffa98d6376c11530b49e27817af3060fe74eebbe1505c7892c72.jpg)

![bc97b5a56e6e24619dd31e5d4ac0f7ead0ceb5dd5b7870ca154004d484295571.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/bc97b5a56e6e24619dd31e5d4ac0f7ead0ceb5dd5b7870ca154004d484295571.jpg)

![d3d0f7cfc466146230e262316f0a07b5ec11534dad72effb673a8e4b25e5b9ec.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/images/d3d0f7cfc466146230e262316f0a07b5ec11534dad72effb673a8e4b25e5b9ec.jpg)

### Tables

![52711da2795319e6e292c26822a38e00a16fd4a3eb7049135cbf280a4bdc6e9d.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/tables/52711da2795319e6e292c26822a38e00a16fd4a3eb7049135cbf280a4bdc6e9d.jpg)

![7af1c177fbee9a813d8fac476dad2917842c46bb6a882ae4ef16e602d6b6f630.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/tables/7af1c177fbee9a813d8fac476dad2917842c46bb6a882ae4ef16e602d6b6f630.jpg)

![897059295516252b12ea7a3ccb0ef5b75c6a263d1ea70527091ae485275e82d6.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/tables/897059295516252b12ea7a3ccb0ef5b75c6a263d1ea70527091ae485275e82d6.jpg)

![971b85d624eafb7be094039ce6467306349e520e799d9435c97ed7cd16da2570.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/tables/971b85d624eafb7be094039ce6467306349e520e799d9435c97ed7cd16da2570.jpg)

![9fd500d3ab388cc66e8ded92f4481f3e5adb566b2d8c052e2dd97168d5620c8b.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/tables/9fd500d3ab388cc66e8ded92f4481f3e5adb566b2d8c052e2dd97168d5620c8b.jpg)

![f1fc424e06c4cfe55a7223305c0b6f06b2d29fb3cf9ed40cbbbe213ea0467252.jpg](../nips_results/575_Chain-of-Zoom_%20Extreme%20Super-Resolution%20via%20Scale%20Autoregression%20and%20Preference%20Alignment/tables/f1fc424e06c4cfe55a7223305c0b6f06b2d29fb3cf9ed40cbbbe213ea0467252.jpg)

## Characterizing control between interacting subsystems with deep Jacobian estimation


### Images

![0ff0007426014dafbc65def3cadae27b241f73a155d4008ba3bb3fdcf3e57643.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/images/0ff0007426014dafbc65def3cadae27b241f73a155d4008ba3bb3fdcf3e57643.jpg)

![358f2e7ddc108bab0f43b76b0aa29557cedb191c3afb6f8c29f2f148a8b5cf33.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/images/358f2e7ddc108bab0f43b76b0aa29557cedb191c3afb6f8c29f2f148a8b5cf33.jpg)

![68ab477b56b61bb5546491cf7961690445a32eeb0621b0aa718e2ed30cd3fac8.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/images/68ab477b56b61bb5546491cf7961690445a32eeb0621b0aa718e2ed30cd3fac8.jpg)

![83d64a0020d3941db7633989bc51b8a26d65a90c8f1b2063c2cf785ca2cccd50.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/images/83d64a0020d3941db7633989bc51b8a26d65a90c8f1b2063c2cf785ca2cccd50.jpg)

![98939678c7c166958ade7eb8db0bdc7d52d988e18dd4c11680a74a5f2da008f4.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/images/98939678c7c166958ade7eb8db0bdc7d52d988e18dd4c11680a74a5f2da008f4.jpg)

![afb80ede6d6c7737c8bd2f389af394e3a191c171b431bba29587cbaa2b7d3f38.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/images/afb80ede6d6c7737c8bd2f389af394e3a191c171b431bba29587cbaa2b7d3f38.jpg)

![c0677098f5adf6722b2a33375f2ba5e2f2b3b7eb5e5b435a7ed7098c4e89dcf3.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/images/c0677098f5adf6722b2a33375f2ba5e2f2b3b7eb5e5b435a7ed7098c4e89dcf3.jpg)

![ce0cfe470e5ebee27252617c2ad8ce9e913d533530f6415f0acd7a67a3256e3f.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/images/ce0cfe470e5ebee27252617c2ad8ce9e913d533530f6415f0acd7a67a3256e3f.jpg)

![fdcd735458703a24e7b8272e1eeb57d603a922d759cc59ed393f868e87aa31e7.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/images/fdcd735458703a24e7b8272e1eeb57d603a922d759cc59ed393f868e87aa31e7.jpg)

### Tables

![10edb5c15c59b0f4982c46a61ee54134836336f7d04fbfa9114f37d6e5b40678.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/tables/10edb5c15c59b0f4982c46a61ee54134836336f7d04fbfa9114f37d6e5b40678.jpg)

![12b394d360105493d6c6c6c1a5781ff1dbaf8f52fac1a2e3670078e9ee4446cd.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/tables/12b394d360105493d6c6c6c1a5781ff1dbaf8f52fac1a2e3670078e9ee4446cd.jpg)

![1f77e693f9d60d0d7abdd0faccb4ca5fcddad96c0737663f03e2d39ebcbab59b.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/tables/1f77e693f9d60d0d7abdd0faccb4ca5fcddad96c0737663f03e2d39ebcbab59b.jpg)

![29e7089c78bf0e91bf100ff715ae0ad1882be3c27b954bdb2e8a155ca6cc6fe8.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/tables/29e7089c78bf0e91bf100ff715ae0ad1882be3c27b954bdb2e8a155ca6cc6fe8.jpg)

![2c0b95062363510172090e2a48da8a24763af5c8cbdd7c9ae57e1cc378644a65.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/tables/2c0b95062363510172090e2a48da8a24763af5c8cbdd7c9ae57e1cc378644a65.jpg)

![80822491a68fe14442d25553bbc62325f528711cc20165aebf420cb536722b79.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/tables/80822491a68fe14442d25553bbc62325f528711cc20165aebf420cb536722b79.jpg)

![9940ac74ae29ad5a017148e6289e5bdf2c72ccfa892b06e4d19918783408a0ca.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/tables/9940ac74ae29ad5a017148e6289e5bdf2c72ccfa892b06e4d19918783408a0ca.jpg)

![c808b002a17cde2205d8a28b9df84af5c1cffe8a5ed5b935f814aed9429732e4.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/tables/c808b002a17cde2205d8a28b9df84af5c1cffe8a5ed5b935f814aed9429732e4.jpg)

![d77b7384cf9c68a6b79f7f1f5520bce23c77341d79b6c461e935d6b67961667e.jpg](../nips_results/576_Characterizing%20control%20between%20interacting%20subsystems%20with%20deep%20Jacobian%20estimation/tables/d77b7384cf9c68a6b79f7f1f5520bce23c77341d79b6c461e935d6b67961667e.jpg)

## Fast and Fluent Diffusion Language Models via Convolutional Decoding and Rejective Fine-tuning


### Images

![01fd9a759f0d1eb2bb13c8bd50c5f7cb8524639dda63a0958391e8a5008c918a.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/01fd9a759f0d1eb2bb13c8bd50c5f7cb8524639dda63a0958391e8a5008c918a.jpg)

![1a0d549dba0ef9f6ce4cf71dd4ab82e7ad36474b87f539f583b3caa0c1c88ed9.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/1a0d549dba0ef9f6ce4cf71dd4ab82e7ad36474b87f539f583b3caa0c1c88ed9.jpg)

![1da60c78541a6b7760cfe708fbfe33b109a2b2ea970e05180c6503ed7b6cb693.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/1da60c78541a6b7760cfe708fbfe33b109a2b2ea970e05180c6503ed7b6cb693.jpg)

![27d25ddb59541eabd30cadf13a4cf510c33bd3767ad06bb8053f58088588d28a.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/27d25ddb59541eabd30cadf13a4cf510c33bd3767ad06bb8053f58088588d28a.jpg)

![3d00bbf51bbb427a22cc21f9d19b0afe3fcbdcd6c637103473143db2f1d269a8.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/3d00bbf51bbb427a22cc21f9d19b0afe3fcbdcd6c637103473143db2f1d269a8.jpg)

![3f28db77fd159ed60dcd6566e1ba94bb919ae47260236544295a4f7a28d75720.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/3f28db77fd159ed60dcd6566e1ba94bb919ae47260236544295a4f7a28d75720.jpg)

![62c9c5885487213b636fe22d63d9d952894c9eb70eb496445e6eeb8fc647fa30.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/62c9c5885487213b636fe22d63d9d952894c9eb70eb496445e6eeb8fc647fa30.jpg)

![6c935b69e56e1ff950e0cee9ba6c31f44bce8255ce7e3b5d4e2f7514c40fb4f0.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/6c935b69e56e1ff950e0cee9ba6c31f44bce8255ce7e3b5d4e2f7514c40fb4f0.jpg)

![6e9502c57903e9e14a3bb57a861dbaecaeb9cc3b3b035c561701a5b207c40169.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/6e9502c57903e9e14a3bb57a861dbaecaeb9cc3b3b035c561701a5b207c40169.jpg)

![8ce37642ae0e0f4255f3642ea6e9ff02f98b9d89ec94482f5127e953324076a6.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/8ce37642ae0e0f4255f3642ea6e9ff02f98b9d89ec94482f5127e953324076a6.jpg)

![90170718229a89efb143769998cbd7bb187b736d42dc5214090c95762da6e0d5.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/90170718229a89efb143769998cbd7bb187b736d42dc5214090c95762da6e0d5.jpg)

![94eb88e28d48d6e3413afbddcfb1aa3fa1ae8e4db14a5ec083ee99d97c852df6.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/94eb88e28d48d6e3413afbddcfb1aa3fa1ae8e4db14a5ec083ee99d97c852df6.jpg)

![a2de2e591729502cc40fdd126aebe35188611cfaf7993fad2dbeb40d683a19fb.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/a2de2e591729502cc40fdd126aebe35188611cfaf7993fad2dbeb40d683a19fb.jpg)

![bd071b04706f89952a14146bd46760ce66280222c5cde8194c96c743ffd43bc7.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/bd071b04706f89952a14146bd46760ce66280222c5cde8194c96c743ffd43bc7.jpg)

![d3966bbb609954bd120f4e28c7ff8247e0cfde59883855ac19c4ffffae2d8b8e.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/images/d3966bbb609954bd120f4e28c7ff8247e0cfde59883855ac19c4ffffae2d8b8e.jpg)

### Tables

![032ee63f44b6639f8df4a3ad0ca9043bc16be354fa4f42c642ccac7e4109ad94.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/032ee63f44b6639f8df4a3ad0ca9043bc16be354fa4f42c642ccac7e4109ad94.jpg)

![261756cb2acf9a55ee13757f3aed52601fa78dc8cb2fe44b2ec05c50d38cbc64.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/261756cb2acf9a55ee13757f3aed52601fa78dc8cb2fe44b2ec05c50d38cbc64.jpg)

![2de584f03d8850015fd9f6651453f2b50de67f055f6d7ee05d50f7bc3a584ab7.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/2de584f03d8850015fd9f6651453f2b50de67f055f6d7ee05d50f7bc3a584ab7.jpg)

![53bcb00baae5955bb3acf38443d3bdb65d3b2b94c64814c9e0f9ad1b99323609.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/53bcb00baae5955bb3acf38443d3bdb65d3b2b94c64814c9e0f9ad1b99323609.jpg)

![586376d1ce93b9a5431cd4caa2e17d7c17f9435392acc58d3008bf3559f0ca43.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/586376d1ce93b9a5431cd4caa2e17d7c17f9435392acc58d3008bf3559f0ca43.jpg)

![72d29b6c99e1d38e3720702a05a68fd556e86b0912012baa7cb7b8df9ccc0bf4.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/72d29b6c99e1d38e3720702a05a68fd556e86b0912012baa7cb7b8df9ccc0bf4.jpg)

![93f2d625012d45d0a2e4974e607bedfd7b8fbd59ec2d3df9300c7fd3a0288730.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/93f2d625012d45d0a2e4974e607bedfd7b8fbd59ec2d3df9300c7fd3a0288730.jpg)

![a8a25280f32d4689713f290ba81a194741fcd83ba36895b4d9b540c998a1b293.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/a8a25280f32d4689713f290ba81a194741fcd83ba36895b4d9b540c998a1b293.jpg)

![a951638b4b2af82ae26f1b10682be2bc4d893cfe369147a93a8d3462f114b0d1.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/a951638b4b2af82ae26f1b10682be2bc4d893cfe369147a93a8d3462f114b0d1.jpg)

![bd74d74f2d82225fdbbdb431ec260c319f422e50f2d90f7d65e7773b394f0a3b.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/bd74d74f2d82225fdbbdb431ec260c319f422e50f2d90f7d65e7773b394f0a3b.jpg)

![befb2153a97443b0caba69a84e4e7f53d663cf7f759c59c2f6476b329ebcc7fa.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/befb2153a97443b0caba69a84e4e7f53d663cf7f759c59c2f6476b329ebcc7fa.jpg)

![e6e1885dc463a748f39f02ebbbac1cb5a5d0df82ef1426cb5865ee5b86e520ef.jpg](../nips_results/577_Fast%20and%20Fluent%20Diffusion%20Language%20Models%20via%20Convolutional%20Decoding%20and%20Rejective%20Fine-tuning/tables/e6e1885dc463a748f39f02ebbbac1cb5a5d0df82ef1426cb5865ee5b86e520ef.jpg)

## Physics-Driven Spatiotemporal Modeling for AI-Generated Video Detection


### Images

![0579e75a29c54a32404fe0f2c9b9590dd720579460b170fb413bb441381499a0.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/0579e75a29c54a32404fe0f2c9b9590dd720579460b170fb413bb441381499a0.jpg)

![14a75a155c8c6550845c5655b911684641274241ed5163bb5acb210e4e5b51cd.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/14a75a155c8c6550845c5655b911684641274241ed5163bb5acb210e4e5b51cd.jpg)

![1990df61777a11c51b6aa4725d50c8994384248c74fb64f21f0180f832c62084.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/1990df61777a11c51b6aa4725d50c8994384248c74fb64f21f0180f832c62084.jpg)

![1f601ea0b51a9f6670bfe944e08b61dc331e33fc8b043ec2b9d610f84c562bbe.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/1f601ea0b51a9f6670bfe944e08b61dc331e33fc8b043ec2b9d610f84c562bbe.jpg)

![216128dc42190c894698107777368f09ae101cf215d607e578a06b081b8c6e9c.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/216128dc42190c894698107777368f09ae101cf215d607e578a06b081b8c6e9c.jpg)

![29e87d8f6be6573bd44b6899140c000b7b55f76b635723fc86dda03692f7ed4d.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/29e87d8f6be6573bd44b6899140c000b7b55f76b635723fc86dda03692f7ed4d.jpg)

![3e2d7c0c56ea333d9400d8da826b7675726e54fc69bf0beca2c69d2fb16dfe26.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/3e2d7c0c56ea333d9400d8da826b7675726e54fc69bf0beca2c69d2fb16dfe26.jpg)

![5b4c1f7ba97eb0f8db7d0585a0c6e54a04c31305bd52997bb7499f983e8a8b6b.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/5b4c1f7ba97eb0f8db7d0585a0c6e54a04c31305bd52997bb7499f983e8a8b6b.jpg)

![6d1d1fbd22c5c9e4954d1217736b1713657d89a89e69a09066852530ea05748c.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/6d1d1fbd22c5c9e4954d1217736b1713657d89a89e69a09066852530ea05748c.jpg)

![7475248547d0e7e969a46ca5de5bd61ede6609e81a602cc48834b558237aa7da.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/7475248547d0e7e969a46ca5de5bd61ede6609e81a602cc48834b558237aa7da.jpg)

![7960731d2cf65306fb2ccf2b4dc3792ed55197a1c561f04d82e6b487b2023fdf.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/7960731d2cf65306fb2ccf2b4dc3792ed55197a1c561f04d82e6b487b2023fdf.jpg)

![90d3575d164f4b4a22fd58bc640ca033ef4a298be3d8b4e4199b958e5ba58825.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/90d3575d164f4b4a22fd58bc640ca033ef4a298be3d8b4e4199b958e5ba58825.jpg)

![a716b326379730c72286f033b3fa02e6b8eb58a41f95244d038400e09a195901.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/a716b326379730c72286f033b3fa02e6b8eb58a41f95244d038400e09a195901.jpg)

![a73f008b65cc3e34ab238c5fd3ddaa3c3d6a0fa349b2f04a0f3ee8488b080067.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/a73f008b65cc3e34ab238c5fd3ddaa3c3d6a0fa349b2f04a0f3ee8488b080067.jpg)

![bb911c69b3eab2b98524d55749b1b84cb5def8b598ab80708bc99dfdd896deef.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/bb911c69b3eab2b98524d55749b1b84cb5def8b598ab80708bc99dfdd896deef.jpg)

![cb8d59015fd8d89330ce58b169df8ec9cfc37c46e0480fa1c9ae912a54379e50.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/cb8d59015fd8d89330ce58b169df8ec9cfc37c46e0480fa1c9ae912a54379e50.jpg)

![e0d142253e13a94774af857387a8241119b06480c8d4c6e7f49af28fe8954ad4.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/e0d142253e13a94774af857387a8241119b06480c8d4c6e7f49af28fe8954ad4.jpg)

![fae7301547b95921eee01a08da12060d5fc0801251a13cdbba87a6a098d38f86.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/fae7301547b95921eee01a08da12060d5fc0801251a13cdbba87a6a098d38f86.jpg)

![fcec19eff5b379c1e6ce84d892d17e1ee824c8b3724ce5da2b6cb09ab64c0c5e.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/images/fcec19eff5b379c1e6ce84d892d17e1ee824c8b3724ce5da2b6cb09ab64c0c5e.jpg)

### Tables

![18e16681c9c46717929e5dccd43ee8d3c645f127e073b067e65dc42c8593a89d.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/tables/18e16681c9c46717929e5dccd43ee8d3c645f127e073b067e65dc42c8593a89d.jpg)

![55376d32e8ea18669dfe87b9e1526dfbbd4b34368462a719cf626fcb05b78340.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/tables/55376d32e8ea18669dfe87b9e1526dfbbd4b34368462a719cf626fcb05b78340.jpg)

![582aa96a6089a760770827ac9329cd8f1a17ff8bab27aa9c3b3daaa9f926a0ee.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/tables/582aa96a6089a760770827ac9329cd8f1a17ff8bab27aa9c3b3daaa9f926a0ee.jpg)

![6a5963fbbb679e3cb91972bafa1ce3dbf54c8ddc2677397aef87205ba4096622.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/tables/6a5963fbbb679e3cb91972bafa1ce3dbf54c8ddc2677397aef87205ba4096622.jpg)

![88a761e3348fd2141cca14b631f4de437486b5eca6ca79ba4c4df4aca5781c3d.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/tables/88a761e3348fd2141cca14b631f4de437486b5eca6ca79ba4c4df4aca5781c3d.jpg)

![d2a69b4bcf4d2c7a16b205a24593b090afba847c9de2bdfa3a4ba93a78dd15e1.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/tables/d2a69b4bcf4d2c7a16b205a24593b090afba847c9de2bdfa3a4ba93a78dd15e1.jpg)

![d56f79812f23a3d93bb78fac2f36e9714d76d490f37ed0c0af587d675eeb50d7.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/tables/d56f79812f23a3d93bb78fac2f36e9714d76d490f37ed0c0af587d675eeb50d7.jpg)

![d71734a68d257cd1f871f3fc38e1e90d2e78f0953581958926611e3f863d2579.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/tables/d71734a68d257cd1f871f3fc38e1e90d2e78f0953581958926611e3f863d2579.jpg)

![ee9489adfa4303b182dea4c986e5b6c7b3fd262b5d83e601b1486f6f388e2123.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/tables/ee9489adfa4303b182dea4c986e5b6c7b3fd262b5d83e601b1486f6f388e2123.jpg)

![fd2ecf3c10ed0d2ed5d6c1a8d004f38e26036d44f16b70d3e7f44d1f3c6c4e0d.jpg](../nips_results/578_Physics-Driven%20Spatiotemporal%20Modeling%20for%20AI-Generated%20Video%20Detection/tables/fd2ecf3c10ed0d2ed5d6c1a8d004f38e26036d44f16b70d3e7f44d1f3c6c4e0d.jpg)

## Stable Minima of ReLU Neural Networks Suffer from the Curse of Dimensionality: The Neural Shattering Phenomenon


### Images

![011e8ac30e27437f223a1bb168925bb38b695bfbf89bca6c2c83afbf65a6e14a.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/011e8ac30e27437f223a1bb168925bb38b695bfbf89bca6c2c83afbf65a6e14a.jpg)

![2642f56267fa810d6ed7f3c80cc5d485a5e6bd7b5dd1c1f5648b4866a6a2b022.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/2642f56267fa810d6ed7f3c80cc5d485a5e6bd7b5dd1c1f5648b4866a6a2b022.jpg)

![536a1b2139f7bfb412da36770a0e28ae5ccaa30766b9b270a5a129690fa5e0ef.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/536a1b2139f7bfb412da36770a0e28ae5ccaa30766b9b270a5a129690fa5e0ef.jpg)

![6a8ce6f4af332e8f6e76e0599f96a2e7257ba168c27b5b1040c59c018fe2f12e.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/6a8ce6f4af332e8f6e76e0599f96a2e7257ba168c27b5b1040c59c018fe2f12e.jpg)

![6e0e258ca986709c9ce13a9d5fbc2b646917dc2671ba513b01a2f93f25ecf83d.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/6e0e258ca986709c9ce13a9d5fbc2b646917dc2671ba513b01a2f93f25ecf83d.jpg)

![8651aa17f903e38b30b54659b5a4cf64b36861d422e5e7f9d2f98f95ca6bbb92.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/8651aa17f903e38b30b54659b5a4cf64b36861d422e5e7f9d2f98f95ca6bbb92.jpg)

![881e4c1cbf9264c4ab0050ede50c6303634e6f5d7cf01d2b5d3d1d2ecf26ce03.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/881e4c1cbf9264c4ab0050ede50c6303634e6f5d7cf01d2b5d3d1d2ecf26ce03.jpg)

![8cfa24ea70d3629084925550bab00f7360172d2e543e86bb03fd8e29646b42d8.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/8cfa24ea70d3629084925550bab00f7360172d2e543e86bb03fd8e29646b42d8.jpg)

![90126549d38e4cb581e8a66f1a754613716574621abc3f77da14f3411902dfd8.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/90126549d38e4cb581e8a66f1a754613716574621abc3f77da14f3411902dfd8.jpg)

![aeb21577395051996daada8c5468ce3aad0e28601e838472aa7e0b497971d572.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/aeb21577395051996daada8c5468ce3aad0e28601e838472aa7e0b497971d572.jpg)

![b30b61ccd0d7ad80848134c900823823192682d303594d967098035bff9b0af4.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/b30b61ccd0d7ad80848134c900823823192682d303594d967098035bff9b0af4.jpg)

![b575ba76ef4916e68d6437d51d2cf5965584cc367396a2378db2b32d955247be.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/b575ba76ef4916e68d6437d51d2cf5965584cc367396a2378db2b32d955247be.jpg)

![cb833ede7ca27920ce164e73e90894b6057fd28362489156d6021cd716132cd4.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/cb833ede7ca27920ce164e73e90894b6057fd28362489156d6021cd716132cd4.jpg)

![cd71c25899e85681c0b0308afd039e245fe52e646f2fcccf210fe2b57870cfa4.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/cd71c25899e85681c0b0308afd039e245fe52e646f2fcccf210fe2b57870cfa4.jpg)

![f14640c57ef63cc129d5d38d8f8c842c3e05a8d03466e1e991f6d75e5de1c7a9.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/f14640c57ef63cc129d5d38d8f8c842c3e05a8d03466e1e991f6d75e5de1c7a9.jpg)

![f4f162c7f8eb9f492633883a645db79002c97ca9a3e5124f76d8085ca0a65090.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/f4f162c7f8eb9f492633883a645db79002c97ca9a3e5124f76d8085ca0a65090.jpg)

![f7c182af735c7ade967c72c2e82982aa98b2e59c69a672098daaf7dc89435ec4.jpg](../nips_results/579_Stable%20Minima%20of%20ReLU%20Neural%20Networks%20Suffer%20from%20the%20Curse%20of%20Dimensionality_%20The%20Neural%20Shattering/images/f7c182af735c7ade967c72c2e82982aa98b2e59c69a672098daaf7dc89435ec4.jpg)

## Structured Linear CDEs: Maximally Expressive and Parallel-in-Time Sequence Models


### Images

![035006eaaaa8ad1924d8a47bb76b4aa7584b949863f25b281121b4f3703e34b3.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/images/035006eaaaa8ad1924d8a47bb76b4aa7584b949863f25b281121b4f3703e34b3.jpg)

![2031d1233ad5f2c5c8f316d3f28661205c0398fea10b747f9766b2935e68add8.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/images/2031d1233ad5f2c5c8f316d3f28661205c0398fea10b747f9766b2935e68add8.jpg)

![2f2df9fad5275bb7ef1412e53cbf364b9a31665171d472e58d8a6d1d66ba1fe9.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/images/2f2df9fad5275bb7ef1412e53cbf364b9a31665171d472e58d8a6d1d66ba1fe9.jpg)

![5a0cff22883aeb9fa9bd8a6ad979fe488696c437fa9e7d46553531e9408434e9.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/images/5a0cff22883aeb9fa9bd8a6ad979fe488696c437fa9e7d46553531e9408434e9.jpg)

![c07291203152007ccd58763cfb3b12edc4d1cf1c4bfc00662734cbf74c4c50b7.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/images/c07291203152007ccd58763cfb3b12edc4d1cf1c4bfc00662734cbf74c4c50b7.jpg)

### Tables

![29cb452abb8e48562afa0615e1654e0fc8b8b018c0c858e1624ca076a79aeae3.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/tables/29cb452abb8e48562afa0615e1654e0fc8b8b018c0c858e1624ca076a79aeae3.jpg)

![3c337cd05017ad1cfe552cf6433d55c946687a8342339267347fd4f78d51f547.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/tables/3c337cd05017ad1cfe552cf6433d55c946687a8342339267347fd4f78d51f547.jpg)

![44341bc8e7700b94dc1b50f80bea77de009237eba613957f17bcb37a04227e33.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/tables/44341bc8e7700b94dc1b50f80bea77de009237eba613957f17bcb37a04227e33.jpg)

![4a4506939bb4a164feb8f4ec75e1f11676ea16ba3dd6b4bc1c5553d0e7fa3b16.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/tables/4a4506939bb4a164feb8f4ec75e1f11676ea16ba3dd6b4bc1c5553d0e7fa3b16.jpg)

![4d64de313d572c28cdcf8501b7461e8714034f53b288f28050cf4fbd3197148e.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/tables/4d64de313d572c28cdcf8501b7461e8714034f53b288f28050cf4fbd3197148e.jpg)

![75d24f57dc76f67eee398f549f104f139bc8edb303097fb78e6799dbbefb0e83.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/tables/75d24f57dc76f67eee398f549f104f139bc8edb303097fb78e6799dbbefb0e83.jpg)

![fc08e1bcc55a535ef62cf63bf57df155a5d1d00c27f5ddd0e85e0e525b309ce8.jpg](../nips_results/580_Structured%20Linear%20CDEs_%20Maximally%20Expressive%20and%20Parallel-in-Time%20Sequence%20Models/tables/fc08e1bcc55a535ef62cf63bf57df155a5d1d00c27f5ddd0e85e0e525b309ce8.jpg)

## Hybrid-Balance GFlowNet for Solving Vehicle Routing Problems


### Images

![593648546d2dd062a01a1151b2fd17cca748bb8b881179540a9593e7124f0037.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/images/593648546d2dd062a01a1151b2fd17cca748bb8b881179540a9593e7124f0037.jpg)

![6abadc5646409e43876fd9284a5b2d990e588ef3ac08296a7c82205c25521c2c.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/images/6abadc5646409e43876fd9284a5b2d990e588ef3ac08296a7c82205c25521c2c.jpg)

![ea5b5870643f86789ca713cc3a749d121e5bdb4abb88cce90c5fee00e2da9679.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/images/ea5b5870643f86789ca713cc3a749d121e5bdb4abb88cce90c5fee00e2da9679.jpg)

### Tables

![0df5c8dca18a8782aaafd9b3ae260b1eff10ec340bbdfb35af30c761914a3ade.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/0df5c8dca18a8782aaafd9b3ae260b1eff10ec340bbdfb35af30c761914a3ade.jpg)

![140918a7b8fff43f7a503b1d6f675b8852be40182b2f1cbf8c38600c68db78df.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/140918a7b8fff43f7a503b1d6f675b8852be40182b2f1cbf8c38600c68db78df.jpg)

![1602c2e61eddf55758e72fc6f89af0bc58bfc0d6d315d76aab42de3f013d6aca.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/1602c2e61eddf55758e72fc6f89af0bc58bfc0d6d315d76aab42de3f013d6aca.jpg)

![2e67ee55806dfa8f39d790d74d130144ee4b67e3ee2d0a342bc06d91fddc42f6.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/2e67ee55806dfa8f39d790d74d130144ee4b67e3ee2d0a342bc06d91fddc42f6.jpg)

![34c1827435306201c90b530e7a03c5f5e7ab1046b20e1590d0379d708f2a1002.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/34c1827435306201c90b530e7a03c5f5e7ab1046b20e1590d0379d708f2a1002.jpg)

![35f988fa37c3b1be68f3d40e830539fd8ee5aa63fb21fb7166d2c7d6ab0b0791.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/35f988fa37c3b1be68f3d40e830539fd8ee5aa63fb21fb7166d2c7d6ab0b0791.jpg)

![3f519bf349876ee457eec16f1c8565b3cff66a83469d2946f814f11a881e69cf.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/3f519bf349876ee457eec16f1c8565b3cff66a83469d2946f814f11a881e69cf.jpg)

![4beb5bcb033328bcdf2a7219e65e79f5c063d4b910f73e0d695889709300dad3.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/4beb5bcb033328bcdf2a7219e65e79f5c063d4b910f73e0d695889709300dad3.jpg)

![65f96b2f343049d23c5d95c104faed59d4c21d3a4d1b266a72946a5707a362b3.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/65f96b2f343049d23c5d95c104faed59d4c21d3a4d1b266a72946a5707a362b3.jpg)

![670e038a4db1bf897f10093d0710858e4825a416d8c61db14a7557043c9ba380.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/670e038a4db1bf897f10093d0710858e4825a416d8c61db14a7557043c9ba380.jpg)

![76fe59dd133f8a6dbbde65643b226f216900c692621be952a9b205452944b3ab.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/76fe59dd133f8a6dbbde65643b226f216900c692621be952a9b205452944b3ab.jpg)

![7bbb1695ddb0801bf75ee3eaa13b8e0fffccc6b2114efbd35d1c67a69dfa4f72.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/7bbb1695ddb0801bf75ee3eaa13b8e0fffccc6b2114efbd35d1c67a69dfa4f72.jpg)

![83ff3655edd88ad040b4c2515e0fa6998e80b396c203158e41d5140dddec18e8.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/83ff3655edd88ad040b4c2515e0fa6998e80b396c203158e41d5140dddec18e8.jpg)

![856f8ec646dd9c2cff2b354df47328594cc34bc4e9191b35e865b14e351c9a38.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/856f8ec646dd9c2cff2b354df47328594cc34bc4e9191b35e865b14e351c9a38.jpg)

![a1ccc840c2de1bffe65fae1056b098229b750edec39b2263c9203fa93ac8aabb.jpg](../nips_results/582_Hybrid-Balance%20GFlowNet%20for%20Solving%20Vehicle%20Routing%20Problems/tables/a1ccc840c2de1bffe65fae1056b098229b750edec39b2263c9203fa93ac8aabb.jpg)

## A Principled Path to Fitted Distributional Evaluation


### Images

![31dfcdc48118e47266534285eb6856c4659805863db43afc44874be6efb83fd5.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/images/31dfcdc48118e47266534285eb6856c4659805863db43afc44874be6efb83fd5.jpg)

![8ab4812bde99dfc124da5685ccfd6d9bf54d2f0ac8e366f66b195c6ccc919607.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/images/8ab4812bde99dfc124da5685ccfd6d9bf54d2f0ac8e366f66b195c6ccc919607.jpg)

![a58acca689f955bee7e8a97850d00478be6b668b0234a42d395d48403de7a78e.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/images/a58acca689f955bee7e8a97850d00478be6b668b0234a42d395d48403de7a78e.jpg)

![e68ffa73c5960ff4b687e02755d02c97deb81d109b2b832bac7a9f5bbbec72d2.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/images/e68ffa73c5960ff4b687e02755d02c97deb81d109b2b832bac7a9f5bbbec72d2.jpg)

![efd306e8417702d932c8b88755d38dd163fab4fa8ab8f68551cc337e80944374.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/images/efd306e8417702d932c8b88755d38dd163fab4fa8ab8f68551cc337e80944374.jpg)

### Tables

![0d0d5ecb778e9ad50fde0059b3e7161618d58463c8a21d1a9348cc2c5c74ca61.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/0d0d5ecb778e9ad50fde0059b3e7161618d58463c8a21d1a9348cc2c5c74ca61.jpg)

![1eb5e95d4693bd856f6f5f22221e81af1b3f0d555a9e35d8ab2de4c5c54ac5a1.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/1eb5e95d4693bd856f6f5f22221e81af1b3f0d555a9e35d8ab2de4c5c54ac5a1.jpg)

![253d25c285620a09493197b6e46d68015c8fa338f59cee5403170329ba8f1ada.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/253d25c285620a09493197b6e46d68015c8fa338f59cee5403170329ba8f1ada.jpg)

![2a29a606dbf63566af21ffc9113c9b2733cd6b078a5eb18d3bf5d1a6e63d2aad.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/2a29a606dbf63566af21ffc9113c9b2733cd6b078a5eb18d3bf5d1a6e63d2aad.jpg)

![31e0588f33843a05ec7d2fdd293134ee5ea36c32c2d8d8e1d2535cd24534985b.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/31e0588f33843a05ec7d2fdd293134ee5ea36c32c2d8d8e1d2535cd24534985b.jpg)

![3b1c8d261cad215944e3724e966cfa6ec4d4aab7a796da1bf30121ccb79a8685.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/3b1c8d261cad215944e3724e966cfa6ec4d4aab7a796da1bf30121ccb79a8685.jpg)

![3fadf894c01dc1dd8ad2806a6cc4d26078aa4d409a14b1a842fed9f94e8176f9.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/3fadf894c01dc1dd8ad2806a6cc4d26078aa4d409a14b1a842fed9f94e8176f9.jpg)

![403726c81b2ef46c82efbc5efe04a30eafbaf093548df8933c0279e6e2ec5c9e.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/403726c81b2ef46c82efbc5efe04a30eafbaf093548df8933c0279e6e2ec5c9e.jpg)

![587fc707dd8a02a3d7bbec8cd759db7cb733169feceb29984d58871c4aa880ae.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/587fc707dd8a02a3d7bbec8cd759db7cb733169feceb29984d58871c4aa880ae.jpg)

![63a71faecab8d392fd5eb89cc5563d9b8056381ca838f8c34f3ed7d0dae4288e.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/63a71faecab8d392fd5eb89cc5563d9b8056381ca838f8c34f3ed7d0dae4288e.jpg)

![65539577cc2735fe9714d11f339c1b6197bf5eaa634c39b423864d1a8c36ebfc.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/65539577cc2735fe9714d11f339c1b6197bf5eaa634c39b423864d1a8c36ebfc.jpg)

![67a60aae52aa4ed2430a6ccd763b8a4b5e1e97e21de8fa3abcf2d995b071c6e4.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/67a60aae52aa4ed2430a6ccd763b8a4b5e1e97e21de8fa3abcf2d995b071c6e4.jpg)

![68487226ab27283a9157ca33975abcea63114f98f344d9d1c52268f994dc2961.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/68487226ab27283a9157ca33975abcea63114f98f344d9d1c52268f994dc2961.jpg)

![754186f58160c462f6dcb55295faf70e3707f3f3db5a48cfe3655058e01382cb.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/754186f58160c462f6dcb55295faf70e3707f3f3db5a48cfe3655058e01382cb.jpg)

![7fcd365106de9f78d9821a911177bcb5be21453feb02d856249ccf9701367f9b.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/7fcd365106de9f78d9821a911177bcb5be21453feb02d856249ccf9701367f9b.jpg)

![80fa56cf5299959d14dd6d53a5de9c6a25a5e015c8d12fe5fafa4a93d925061f.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/80fa56cf5299959d14dd6d53a5de9c6a25a5e015c8d12fe5fafa4a93d925061f.jpg)

![827c1182bdc47822aeeae2a769dc36cb151ae6332e6bce7990badb594384b37b.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/827c1182bdc47822aeeae2a769dc36cb151ae6332e6bce7990badb594384b37b.jpg)

![89347f39390c9e90b17eb4586e34b856e602d80e2fce45c6b5f9496e65d4225e.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/89347f39390c9e90b17eb4586e34b856e602d80e2fce45c6b5f9496e65d4225e.jpg)

![8e2dee5632e9bf3d9e022fa9a66bef255ff999b383659fcd8f719505e634cf1c.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/8e2dee5632e9bf3d9e022fa9a66bef255ff999b383659fcd8f719505e634cf1c.jpg)

![9059de48a364e748454d0fdd9f6be418b770a3b1f82f777701c7dcaa09894bf4.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/9059de48a364e748454d0fdd9f6be418b770a3b1f82f777701c7dcaa09894bf4.jpg)

![97da710ad607572a47deeb80c6690efd721efbd1b4ee50168a453a6f68b7cb4c.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/97da710ad607572a47deeb80c6690efd721efbd1b4ee50168a453a6f68b7cb4c.jpg)

![a0934f88323998b2d58ee2de604d0aef6915f6e0d8c24b587cdb310d5a9bfcf8.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/a0934f88323998b2d58ee2de604d0aef6915f6e0d8c24b587cdb310d5a9bfcf8.jpg)

![a2f9af7973ad90b8e0a76835977338dfc9e9eb3b06ab496c3410c833f78a1a55.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/a2f9af7973ad90b8e0a76835977338dfc9e9eb3b06ab496c3410c833f78a1a55.jpg)

![b01698b785cd5556816b43c89a8814370156fe272ac4dbc503a882052357ad3d.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/b01698b785cd5556816b43c89a8814370156fe272ac4dbc503a882052357ad3d.jpg)

![c7b77e654e31ca43f5759b8b1a903a3f3fb83e060d925414816a60eca0a6e031.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/c7b77e654e31ca43f5759b8b1a903a3f3fb83e060d925414816a60eca0a6e031.jpg)

![c95bd73543bd87e00f5168a1d948c915e90fd74f219c3da5d5a34a6eef7c2b6a.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/c95bd73543bd87e00f5168a1d948c915e90fd74f219c3da5d5a34a6eef7c2b6a.jpg)

![d0f93647898fecc6dfe7dc0cc502c04c641dd82276e5d54deeb13ee1a4122e8c.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/d0f93647898fecc6dfe7dc0cc502c04c641dd82276e5d54deeb13ee1a4122e8c.jpg)

![d609a81a904e85f73014ca48758dbbb926b7c89eb716179aed9748fe1c897eff.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/d609a81a904e85f73014ca48758dbbb926b7c89eb716179aed9748fe1c897eff.jpg)

![e0f55d9c91a4f8f77f65a235d12ddb38df42f7515083521497df7c8574c0de70.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/e0f55d9c91a4f8f77f65a235d12ddb38df42f7515083521497df7c8574c0de70.jpg)

![eb445ec233693ad418d17a91dc8f72edfdcb58377c94a445120d5e071f597955.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/eb445ec233693ad418d17a91dc8f72edfdcb58377c94a445120d5e071f597955.jpg)

![ebc40137c1ba9d24670b45cd4565b6d226d09e6b53d04da9a360fa99d1a00bb5.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/ebc40137c1ba9d24670b45cd4565b6d226d09e6b53d04da9a360fa99d1a00bb5.jpg)

![ee3862aba697fd1037bab481061ce55e009977137e589a3e65c000b9cdd43789.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/ee3862aba697fd1037bab481061ce55e009977137e589a3e65c000b9cdd43789.jpg)

![f04daab7e595ceb4300c5f99aa57c0ecde2b0b0a60999b00ac4421cef46cc874.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/f04daab7e595ceb4300c5f99aa57c0ecde2b0b0a60999b00ac4421cef46cc874.jpg)

![fc1f52b293a9241abbb3dbeebf9a9db92a9b7fd31776340323e5422b925eb23d.jpg](../nips_results/583_A%20Principled%20Path%20to%20Fitted%20Distributional%20Evaluation/tables/fc1f52b293a9241abbb3dbeebf9a9db92a9b7fd31776340323e5422b925eb23d.jpg)

## SIU3R: Simultaneous Scene Understanding and 3D Reconstruction Beyond Feature Alignment


### Images

![32a98190c317527bb6863549357ecf05b3ef219b4aadeb8ca04222743e440269.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/32a98190c317527bb6863549357ecf05b3ef219b4aadeb8ca04222743e440269.jpg)

![4c8e5b102c1ccff531df695c6bd559038f4c423cb817b0133e7a96332336bd64.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/4c8e5b102c1ccff531df695c6bd559038f4c423cb817b0133e7a96332336bd64.jpg)

![4e6a5833ae5b980087c2b2a4288f152fec9b55ec42be718174ed81724ea898ac.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/4e6a5833ae5b980087c2b2a4288f152fec9b55ec42be718174ed81724ea898ac.jpg)

![4ff01ae44819279643e4cf1e99b07e1fa2de8ecb728c2d09e622cc70eb0d750e.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/4ff01ae44819279643e4cf1e99b07e1fa2de8ecb728c2d09e622cc70eb0d750e.jpg)

![5005250e3c023ad9345ee3b84cb50c99d0dff9d6feac04acf4a15947ca0d579c.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/5005250e3c023ad9345ee3b84cb50c99d0dff9d6feac04acf4a15947ca0d579c.jpg)

![54dbfda16e7f61018f440ad0e4a9e778dba2133cedb90ed34fc2772405e4fc23.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/54dbfda16e7f61018f440ad0e4a9e778dba2133cedb90ed34fc2772405e4fc23.jpg)

![6420c9516025dd31674e063862249aeed3c78ae1e11ab5c4862453fcd596a673.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/6420c9516025dd31674e063862249aeed3c78ae1e11ab5c4862453fcd596a673.jpg)

![6fea023d84950eadcc1a6f95269dbcc2250f6dd16dbc75fb37f9f8242efdd24b.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/6fea023d84950eadcc1a6f95269dbcc2250f6dd16dbc75fb37f9f8242efdd24b.jpg)

![8064ce96085716f9c43f98ce66c02c729b65b7d712f462fea72a1d173f0b4862.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/8064ce96085716f9c43f98ce66c02c729b65b7d712f462fea72a1d173f0b4862.jpg)

![83aec72a753198ffd3b284230ab3bd243318c9133441b48175fb10d752eae608.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/83aec72a753198ffd3b284230ab3bd243318c9133441b48175fb10d752eae608.jpg)

![b1de8d4556a149973607b5f9753584e6fd90ac03519487765a3bf1f8af2f5bc1.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/b1de8d4556a149973607b5f9753584e6fd90ac03519487765a3bf1f8af2f5bc1.jpg)

![b442734540ee83512078d2f8312c389f04bc6dd05be07f8f797b45a7b26788eb.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/b442734540ee83512078d2f8312c389f04bc6dd05be07f8f797b45a7b26788eb.jpg)

![d528544bbb80e3ddd25257da7f9e587e66bc112199f5aecd6a4dee19343fa92f.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/d528544bbb80e3ddd25257da7f9e587e66bc112199f5aecd6a4dee19343fa92f.jpg)

![fefaabc4807a5c06ffa3144226f84d87a5a2cb4cc9fa258ab79fbd0b2ca7e621.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/images/fefaabc4807a5c06ffa3144226f84d87a5a2cb4cc9fa258ab79fbd0b2ca7e621.jpg)

### Tables

![143c3fa68b89b02d779f14e0629e5b0dce428503f29bf360097da7ad1354cc01.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/tables/143c3fa68b89b02d779f14e0629e5b0dce428503f29bf360097da7ad1354cc01.jpg)

![70da35f5dd99e0d73ebc2aa00a8e0adf3541b3a9bd1815686f3ea37be1820277.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/tables/70da35f5dd99e0d73ebc2aa00a8e0adf3541b3a9bd1815686f3ea37be1820277.jpg)

![da39636e58d491d79d9191de253f9f4bc357159486d18764416016b91ea0d84d.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/tables/da39636e58d491d79d9191de253f9f4bc357159486d18764416016b91ea0d84d.jpg)

![e080d475b5116a41da744436eba8a27bbf8f8f86b95f3df51bd6240d0d96beaa.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/tables/e080d475b5116a41da744436eba8a27bbf8f8f86b95f3df51bd6240d0d96beaa.jpg)

![ef4682530c39f22badc9de41560a329e8f8207f462a795234bc27c55bb5faf48.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/tables/ef4682530c39f22badc9de41560a329e8f8207f462a795234bc27c55bb5faf48.jpg)

![f43e3cc5aa6785a68615f8861589960a1470c7c3dfcc3de3b466628c0b1da72e.jpg](../nips_results/584_SIU3R_%20Simultaneous%20Scene%20Understanding%20and%203D%20Reconstruction%20Beyond%20Feature%20Alignment/tables/f43e3cc5aa6785a68615f8861589960a1470c7c3dfcc3de3b466628c0b1da72e.jpg)

## SORTeD Rashomon Sets of Sparse Decision Trees: Anytime Enumeration


### Images

![1d6249b8c30f54e70065600ff94e0579de1a0e3e495c2ea97a934f6651946522.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/images/1d6249b8c30f54e70065600ff94e0579de1a0e3e495c2ea97a934f6651946522.jpg)

![2d8444d8963b790da73c01764d4b66106182bf4edcf8d78da835091ce9789aa2.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/images/2d8444d8963b790da73c01764d4b66106182bf4edcf8d78da835091ce9789aa2.jpg)

![3b4bf6d44e007b54b64445eb67f6ed2eee0c90c3ce43e87c24a6f837bfb0c7fd.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/images/3b4bf6d44e007b54b64445eb67f6ed2eee0c90c3ce43e87c24a6f837bfb0c7fd.jpg)

![510a6acf62ee18249603ece4d75a7d8052046c0e7e54d956cfb101c28c8fc646.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/images/510a6acf62ee18249603ece4d75a7d8052046c0e7e54d956cfb101c28c8fc646.jpg)

![5c69fd8a0a36cb4d6a1c308212155a7d0c57fef2c2c790844e1185459f0c786c.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/images/5c69fd8a0a36cb4d6a1c308212155a7d0c57fef2c2c790844e1185459f0c786c.jpg)

![8b6930f8f113d2bdd8fcf635ca2fd820c2bcef5ebf0607006d3f7d5d18607818.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/images/8b6930f8f113d2bdd8fcf635ca2fd820c2bcef5ebf0607006d3f7d5d18607818.jpg)

![9fa06c577d188d0e435c92c576d91b2a8e55a40828aba39b7ef6ac1496308be6.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/images/9fa06c577d188d0e435c92c576d91b2a8e55a40828aba39b7ef6ac1496308be6.jpg)

![a404bec8d664260b30ba62cf23c63de23a55dd1e1cfd34490af8242be161e466.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/images/a404bec8d664260b30ba62cf23c63de23a55dd1e1cfd34490af8242be161e466.jpg)

![a902fa9556a90b174fbc74a54ba028c2b91031a29ead799f8ddf246107a51e19.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/images/a902fa9556a90b174fbc74a54ba028c2b91031a29ead799f8ddf246107a51e19.jpg)

![d892d3c1a98cd919840f6785a621a4f434503c53d3b25bb7e62fe3969d474e4d.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/images/d892d3c1a98cd919840f6785a621a4f434503c53d3b25bb7e62fe3969d474e4d.jpg)

![d9040b620af36ee1b8ab9ec0fa4e2132044b0c4c874b0f509aed7f86c186fa4d.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/images/d9040b620af36ee1b8ab9ec0fa4e2132044b0c4c874b0f509aed7f86c186fa4d.jpg)

### Tables

![074a90037cb9ac3c294a7a5dad814ab1617b8ea437be84d3b3a4fdb4d3a2a4bc.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/074a90037cb9ac3c294a7a5dad814ab1617b8ea437be84d3b3a4fdb4d3a2a4bc.jpg)

![08d871543c19ccdb865eef59d6edf2187a9bca65bd3d6b146afa3ff29b83558a.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/08d871543c19ccdb865eef59d6edf2187a9bca65bd3d6b146afa3ff29b83558a.jpg)

![0992d295d37e0b3f13997924be36afeb08e11b3cd6ffc859cff75ad602307340.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/0992d295d37e0b3f13997924be36afeb08e11b3cd6ffc859cff75ad602307340.jpg)

![190c127e09ab9de37277199957814ba8b10de943bd4cbf0f919b5b0e4212337b.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/190c127e09ab9de37277199957814ba8b10de943bd4cbf0f919b5b0e4212337b.jpg)

![3cf1310ff398a7c2e5ccfd24d71dc0d514fa7c2ee9c48989baf05c2413aeb87a.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/3cf1310ff398a7c2e5ccfd24d71dc0d514fa7c2ee9c48989baf05c2413aeb87a.jpg)

![41bdf22ed451669f0df4b2c18a45bfdcb04a7f772c421ba299d09a1ce8e5b3ec.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/41bdf22ed451669f0df4b2c18a45bfdcb04a7f772c421ba299d09a1ce8e5b3ec.jpg)

![47f9fc442d568b56e5c920c004e44af5bdf050714db0b6211df8d8694e7b248a.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/47f9fc442d568b56e5c920c004e44af5bdf050714db0b6211df8d8694e7b248a.jpg)

![4a1117c10341782dc4aa7493682c347c5689657cc980fc49fb894c8c1743842a.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/4a1117c10341782dc4aa7493682c347c5689657cc980fc49fb894c8c1743842a.jpg)

![5ee401c270680e48ee106e6ae79541253be4feee48f2f0f478b76cb17aa225c9.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/5ee401c270680e48ee106e6ae79541253be4feee48f2f0f478b76cb17aa225c9.jpg)

![60ee83ea3a024e1e3ed0e6518a419eaf919ad8e834e6448667448947ad3db92a.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/60ee83ea3a024e1e3ed0e6518a419eaf919ad8e834e6448667448947ad3db92a.jpg)

![673924dbbfcd7020e564ae5cdd5ab69b65bf680a36c0cdf0f2995bd230f97855.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/673924dbbfcd7020e564ae5cdd5ab69b65bf680a36c0cdf0f2995bd230f97855.jpg)

![6b63174e4cd1c24cd39c0982c92a080f6f45cfc8cfc76477ddc60cc862bbf18a.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/6b63174e4cd1c24cd39c0982c92a080f6f45cfc8cfc76477ddc60cc862bbf18a.jpg)

![8445c9fba45a0a2183bb8c684d1723f609863db7cc0d00257de61915b185108c.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/8445c9fba45a0a2183bb8c684d1723f609863db7cc0d00257de61915b185108c.jpg)

![99a8a1d6677ad925513b28e88c055274066b833973c989ee42d5ab11997883da.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/99a8a1d6677ad925513b28e88c055274066b833973c989ee42d5ab11997883da.jpg)

![9b30250d550d10987b621e0e2e1adb351cd388acbb08498e3e3f41686476f7e0.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/9b30250d550d10987b621e0e2e1adb351cd388acbb08498e3e3f41686476f7e0.jpg)

![a06bc75509617756ac526c46ab6dce91150e82e949e580589ec439e2eff8ed51.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/a06bc75509617756ac526c46ab6dce91150e82e949e580589ec439e2eff8ed51.jpg)

![ba6bdb85299ce46d306b013b5b37fdf5b9964da2d8a43356d42799189d32aacc.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/ba6bdb85299ce46d306b013b5b37fdf5b9964da2d8a43356d42799189d32aacc.jpg)

![c4ae3d65428bc7d7f9f0d5d4b47c508802f67f0e16df1ce27efab3c86a44f271.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/c4ae3d65428bc7d7f9f0d5d4b47c508802f67f0e16df1ce27efab3c86a44f271.jpg)

![dd9b1315e1b1c0cd4da3bb2ea27f98a5ca246fc2af2e99b7df2a55d92c918238.jpg](../nips_results/585_SORTeD%20Rashomon%20Sets%20of%20Sparse%20Decision%20Trees_%20Anytime%20Enumeration/tables/dd9b1315e1b1c0cd4da3bb2ea27f98a5ca246fc2af2e99b7df2a55d92c918238.jpg)

## ElliCE: Efficient and Provably Robust Algorithmic Recourse via the Rashomon Sets


### Images

![4a5d0bc08094e5d7f262ee04ce39013e506e7442427cfd4c8337069402b7a9e1.jpg](../nips_results/586_ElliCE_%20Efficient%20and%20Provably%20Robust%20Algorithmic%20Recourse%20via%20the%20Rashomon%20Sets/images/4a5d0bc08094e5d7f262ee04ce39013e506e7442427cfd4c8337069402b7a9e1.jpg)

![e51a5e9d19e8ae0c9ab8593897d54592707b4e5b49dccae3bafeb1719309c126.jpg](../nips_results/586_ElliCE_%20Efficient%20and%20Provably%20Robust%20Algorithmic%20Recourse%20via%20the%20Rashomon%20Sets/images/e51a5e9d19e8ae0c9ab8593897d54592707b4e5b49dccae3bafeb1719309c126.jpg)

### Tables

![2a4f10adadfddbdf899a6c56b40722c313c62786df9d09729922e65280dcab3a.jpg](../nips_results/586_ElliCE_%20Efficient%20and%20Provably%20Robust%20Algorithmic%20Recourse%20via%20the%20Rashomon%20Sets/tables/2a4f10adadfddbdf899a6c56b40722c313c62786df9d09729922e65280dcab3a.jpg)

![acb3bfd2f14724d25f065b9524683c051c7fe6983e58b5ff1d822a88b1b5a236.jpg](../nips_results/586_ElliCE_%20Efficient%20and%20Provably%20Robust%20Algorithmic%20Recourse%20via%20the%20Rashomon%20Sets/tables/acb3bfd2f14724d25f065b9524683c051c7fe6983e58b5ff1d822a88b1b5a236.jpg)

## Web-Shepherd: Advancing PRMs for Reinforcing Web Agents


### Images

![21819e01bca9adf91841ed943cc7740c0f488761c1a4a4bf902f293a7d106f03.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/21819e01bca9adf91841ed943cc7740c0f488761c1a4a4bf902f293a7d106f03.jpg)

![2ca041c73c929b1ea19e61efec99ab7dfaf40416f8d512f9b96ebb608ab15593.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/2ca041c73c929b1ea19e61efec99ab7dfaf40416f8d512f9b96ebb608ab15593.jpg)

![41931dc0b7b0a92cc904248eb6aa4df0dbbc5cd53c2fe4e4af3eaff9818486c1.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/41931dc0b7b0a92cc904248eb6aa4df0dbbc5cd53c2fe4e4af3eaff9818486c1.jpg)

![49ce8a3f107409c6949675f2d0b33508073ef7d4c39647275655938e742d1388.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/49ce8a3f107409c6949675f2d0b33508073ef7d4c39647275655938e742d1388.jpg)

![4b087952d9409e1fbed628fbd02477fcdc54dfa0181db943f1f60a1bd171d2f0.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/4b087952d9409e1fbed628fbd02477fcdc54dfa0181db943f1f60a1bd171d2f0.jpg)

![4dc110cb1b2794e50ec3b8d3ca030c79bcd0bbe2d404ca8e18491dfb39472568.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/4dc110cb1b2794e50ec3b8d3ca030c79bcd0bbe2d404ca8e18491dfb39472568.jpg)

![56fdda0b85e4e741a1da5c1337f88bcd359be09084bba7e2e42fb57bb3f59764.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/56fdda0b85e4e741a1da5c1337f88bcd359be09084bba7e2e42fb57bb3f59764.jpg)

![7710c250ddf023d05376cd5a3e971f7388499e18af204d82508ae8cdd4fdbd23.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/7710c250ddf023d05376cd5a3e971f7388499e18af204d82508ae8cdd4fdbd23.jpg)

![83d635635df793d32bfa072856506a76f97a91a9d346ad1152f82f7dbce20b4a.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/83d635635df793d32bfa072856506a76f97a91a9d346ad1152f82f7dbce20b4a.jpg)

![8d25e0374d0d93ff7a7e75894b19e09b358b2c7b37e72783db4756bc8954eda7.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/8d25e0374d0d93ff7a7e75894b19e09b358b2c7b37e72783db4756bc8954eda7.jpg)

![8f1580541f34b661807c243f60c9f5683716e561fd4b754d30a4b425e3fcc26a.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/8f1580541f34b661807c243f60c9f5683716e561fd4b754d30a4b425e3fcc26a.jpg)

![9bc6d8d24de71adf72a7fe26121193f02730e0ce7de57b4071b8cba61ea16737.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/9bc6d8d24de71adf72a7fe26121193f02730e0ce7de57b4071b8cba61ea16737.jpg)

![ad270894a4c5aa765554e0ce6d88222cdccb794f7a550af23529ff9ba2242a67.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/ad270894a4c5aa765554e0ce6d88222cdccb794f7a550af23529ff9ba2242a67.jpg)

![bad559d4c6328e1b03c33f9d74946916e56dcb3a2d5d62dcd7bb0d37e5786984.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/bad559d4c6328e1b03c33f9d74946916e56dcb3a2d5d62dcd7bb0d37e5786984.jpg)

![c1a9a10f74815fdf63747ab4953589810619f169c9cfe210e11d664bcb700786.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/c1a9a10f74815fdf63747ab4953589810619f169c9cfe210e11d664bcb700786.jpg)

![c4b2a202b767f91f5c46fabcb3375e36ba64e7651235b2c7c91253b678df3246.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/c4b2a202b767f91f5c46fabcb3375e36ba64e7651235b2c7c91253b678df3246.jpg)

![c6ed4aceca780ae65b05dd769ca4c1745cac4f7f5f1f3178b4223b9eea08d1d5.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/c6ed4aceca780ae65b05dd769ca4c1745cac4f7f5f1f3178b4223b9eea08d1d5.jpg)

![c7e29f28f1e97f804344729e832c233d2d1c9626c81a448607be2efed1162576.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/c7e29f28f1e97f804344729e832c233d2d1c9626c81a448607be2efed1162576.jpg)

![d0890d0f4ef0d264c91c0b1230b13800c67e9f554674175250df8d0f5f1372d3.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/d0890d0f4ef0d264c91c0b1230b13800c67e9f554674175250df8d0f5f1372d3.jpg)

![d9ad5657689c1a6d4b54f5b17f7bd373555d3e26283eee997bc32b0a70b09b6c.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/d9ad5657689c1a6d4b54f5b17f7bd373555d3e26283eee997bc32b0a70b09b6c.jpg)

![e33b73470aad98ed6d5eb00a6f732d77ad0c704598e01b12a19ad557c255da3f.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/e33b73470aad98ed6d5eb00a6f732d77ad0c704598e01b12a19ad557c255da3f.jpg)

![ebc5da4e995ebe222343535e69b47bce5687eb1e1ebce8665e04637a27eb9db3.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/ebc5da4e995ebe222343535e69b47bce5687eb1e1ebce8665e04637a27eb9db3.jpg)

![ee470ba2221a3238d860bc9a358b45396770d50b8751bab2625ea1444b36b22e.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/ee470ba2221a3238d860bc9a358b45396770d50b8751bab2625ea1444b36b22e.jpg)

![f0fe3bcc712c2032ac6b132b1269fff71b5bbb9b964e6fa23e23e8a049124235.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/f0fe3bcc712c2032ac6b132b1269fff71b5bbb9b964e6fa23e23e8a049124235.jpg)

![f46441fa2453c6f366921ff9b1fdebff7f42f121ad5c273a4429ed5616787634.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/f46441fa2453c6f366921ff9b1fdebff7f42f121ad5c273a4429ed5616787634.jpg)

![f5d2c5837882c21f82514d1cc482c1798d218f4ab52f9ff878d96b64e841214f.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/f5d2c5837882c21f82514d1cc482c1798d218f4ab52f9ff878d96b64e841214f.jpg)

![ff239a1d0ace5903548de6d6dbc5b4f99f9f38d77ffc7d58023ccf146513b9f9.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/images/ff239a1d0ace5903548de6d6dbc5b4f99f9f38d77ffc7d58023ccf146513b9f9.jpg)

### Tables

![12363472e36cb22aa2fc7970a76a7fcc4a8b8e1fcc57be843fc619b67a3ca210.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/12363472e36cb22aa2fc7970a76a7fcc4a8b8e1fcc57be843fc619b67a3ca210.jpg)

![1bb200c3c09d999065b2a109a7fa8b72b306fb5a52f1df673b09a86d05d1e062.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/1bb200c3c09d999065b2a109a7fa8b72b306fb5a52f1df673b09a86d05d1e062.jpg)

![2a4539f2cf4c5f2090a1c03464758f8fc181905d31372607eb3c6ff216b3cd05.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/2a4539f2cf4c5f2090a1c03464758f8fc181905d31372607eb3c6ff216b3cd05.jpg)

![8e3b64e8ea5c2287b6d60781d33deba036cfbc8bd9803e24406821bc866148a2.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/8e3b64e8ea5c2287b6d60781d33deba036cfbc8bd9803e24406821bc866148a2.jpg)

![968b50a95b8fe880b07a0edf58c85f910b0c30a84a1a5243cfded8b67abc812c.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/968b50a95b8fe880b07a0edf58c85f910b0c30a84a1a5243cfded8b67abc812c.jpg)

![982828f42acfaab80237524cfb8d0dcec8f339932861589e6863c274ff345f72.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/982828f42acfaab80237524cfb8d0dcec8f339932861589e6863c274ff345f72.jpg)

![9d4318aef972741a02664edca09324ad02e5dde77bbb71f65f64bbb1c6de5cb7.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/9d4318aef972741a02664edca09324ad02e5dde77bbb71f65f64bbb1c6de5cb7.jpg)

![9d7532d43237838723651c7ba7473d097e99acfd176a124e171bb4f97b9679bb.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/9d7532d43237838723651c7ba7473d097e99acfd176a124e171bb4f97b9679bb.jpg)

![d2a7e4b24b04392e9e209ad9c10c0a7fdd3a6e1f1a8a2bcf661d77eff5af3352.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/d2a7e4b24b04392e9e209ad9c10c0a7fdd3a6e1f1a8a2bcf661d77eff5af3352.jpg)

![d50ff3723713af8ae2eeee5d104098dc60f9251440ab79fcc5d455a7b95c0e7d.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/d50ff3723713af8ae2eeee5d104098dc60f9251440ab79fcc5d455a7b95c0e7d.jpg)

![ebc84e18a59d64277b61c9e675d5c4f6610e4374a8295406cbedbf50d20ee83a.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/ebc84e18a59d64277b61c9e675d5c4f6610e4374a8295406cbedbf50d20ee83a.jpg)

![ec0ea0a8a69ed227bb799069fbf2be3b220a80db2618577bcef9d30a18ccbf36.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/ec0ea0a8a69ed227bb799069fbf2be3b220a80db2618577bcef9d30a18ccbf36.jpg)

![ef0da47f0b338db600cef20ff3281a43842444a492dc70fd0c3091a21f35e5de.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/ef0da47f0b338db600cef20ff3281a43842444a492dc70fd0c3091a21f35e5de.jpg)

![f35f7b0619595a97b7f5f3266adaf6ca00e116243efab7ec11ae3f01e8a4cdd6.jpg](../nips_results/587_Web-Shepherd_%20Advancing%20PRMs%20for%20Reinforcing%20Web%20Agents/tables/f35f7b0619595a97b7f5f3266adaf6ca00e116243efab7ec11ae3f01e8a4cdd6.jpg)

## SimWorld: An Open-ended Simulator for Agents in Physical and Social Worlds


### Images

![01d3dcf9d6cc8f68ca985ecf126ff7850027e8225ca2146ba04e51514280dd1a.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/01d3dcf9d6cc8f68ca985ecf126ff7850027e8225ca2146ba04e51514280dd1a.jpg)

![1038ef25d299c50540a07f9e02c9f6bc1af7c43638d9b8644a6a76cf046fca11.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/1038ef25d299c50540a07f9e02c9f6bc1af7c43638d9b8644a6a76cf046fca11.jpg)

![12868199dc1208290b4ab4f25d454ee8f13e9262c967a96bea0fbeeaa9643bb2.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/12868199dc1208290b4ab4f25d454ee8f13e9262c967a96bea0fbeeaa9643bb2.jpg)

![1b6a838fbf613d4c58faed2c3cb4716e673d1f2ad797113a41c7cc8689bdc29b.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/1b6a838fbf613d4c58faed2c3cb4716e673d1f2ad797113a41c7cc8689bdc29b.jpg)

![32c3d2662fddb74b255f662ba241f2052cbf7b5e0156347062d60c500230bf86.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/32c3d2662fddb74b255f662ba241f2052cbf7b5e0156347062d60c500230bf86.jpg)

![3446789c416c2168b987939ddda5221d4fdbac382b4cbfc864ad34bacbd30be6.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/3446789c416c2168b987939ddda5221d4fdbac382b4cbfc864ad34bacbd30be6.jpg)

![3cffde9b9b21d1f76e12ffa409c34d1dcc77e4731ffda2c1512ae9c2a36c7117.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/3cffde9b9b21d1f76e12ffa409c34d1dcc77e4731ffda2c1512ae9c2a36c7117.jpg)

![41b4da0af6d0689faa09c86b656f1be4429fdf43c4651ab890f9ae3319f130a1.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/41b4da0af6d0689faa09c86b656f1be4429fdf43c4651ab890f9ae3319f130a1.jpg)

![44cdc777efc60ae2877162c16e516ba556ca4222176b30f4046ec9e36a784162.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/44cdc777efc60ae2877162c16e516ba556ca4222176b30f4046ec9e36a784162.jpg)

![467ac5b1ee3df7893e528ad02fc5311e48ba510b3e680ba269f28bad72346bfa.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/467ac5b1ee3df7893e528ad02fc5311e48ba510b3e680ba269f28bad72346bfa.jpg)

![509f826c9850508b3d6b9880e202e9e33f0a38386abb48be5899918e85fedc4b.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/509f826c9850508b3d6b9880e202e9e33f0a38386abb48be5899918e85fedc4b.jpg)

![68ee25d08b404c4a54f41fa2b50b3953edfaa993ec3d4e7b0e6837a4261dab64.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/68ee25d08b404c4a54f41fa2b50b3953edfaa993ec3d4e7b0e6837a4261dab64.jpg)

![7e40b03840fccf87b4de332fc05466aca9ee69a44f655572819981158bb30e9a.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/7e40b03840fccf87b4de332fc05466aca9ee69a44f655572819981158bb30e9a.jpg)

![821550ce64134efd61fc69fa9bef393fb3672f0b487a98527b4f8f8c117118a2.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/821550ce64134efd61fc69fa9bef393fb3672f0b487a98527b4f8f8c117118a2.jpg)

![863a4ddf8b252c3da81ea0ee79186e83b390070784bd0ecf0e85907b02ff0e0d.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/863a4ddf8b252c3da81ea0ee79186e83b390070784bd0ecf0e85907b02ff0e0d.jpg)

![8ab0bd73da4ae6f6a141800eef4106b79cfd5b590067f028617658d0902d1263.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/8ab0bd73da4ae6f6a141800eef4106b79cfd5b590067f028617658d0902d1263.jpg)

![8bc518b9e0e43192ea4019e007f06b960790c8760e7d58cff546c258f37fd686.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/8bc518b9e0e43192ea4019e007f06b960790c8760e7d58cff546c258f37fd686.jpg)

![a62e7008330114dcbd917b00475cfff63cbb072b17a4c7d60ede6c4e36c8804e.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/a62e7008330114dcbd917b00475cfff63cbb072b17a4c7d60ede6c4e36c8804e.jpg)

![b0c548c129d4c3ba92505b451a15836be0f2b0ee6e8e1847c9130221fe59b509.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/b0c548c129d4c3ba92505b451a15836be0f2b0ee6e8e1847c9130221fe59b509.jpg)

![b16a67309ff812e7c1a4d36d8ee7ce98beedaf01f50f3cebbe94eec85f8e8531.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/b16a67309ff812e7c1a4d36d8ee7ce98beedaf01f50f3cebbe94eec85f8e8531.jpg)

![b3f37ec1572daa1c41d57a3126c5112301e1ffb72c483af0dc2ba553f8a38128.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/b3f37ec1572daa1c41d57a3126c5112301e1ffb72c483af0dc2ba553f8a38128.jpg)

![b820a0e7320ca08d717160ffa786b7b2ef94cdb160cb80723db32cd2c2a3304d.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/b820a0e7320ca08d717160ffa786b7b2ef94cdb160cb80723db32cd2c2a3304d.jpg)

![d942619c5c891660572984916585e885c51ebcd7ca2a6f6ae25cb29e95d45df7.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/d942619c5c891660572984916585e885c51ebcd7ca2a6f6ae25cb29e95d45df7.jpg)

![efc6f99ebcb94e47857a2d3302fc697b498619fe8a9413dbbcb2a849a24605ab.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/efc6f99ebcb94e47857a2d3302fc697b498619fe8a9413dbbcb2a849a24605ab.jpg)

![f00177032df0fa0d39ffaa08dd93850eed07b70099a304c64f2e405f4ceff614.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/f00177032df0fa0d39ffaa08dd93850eed07b70099a304c64f2e405f4ceff614.jpg)

![f55c006f4fa3591e97745a3db6a22aed48702230cb275d189911d8ad632e32dd.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/f55c006f4fa3591e97745a3db6a22aed48702230cb275d189911d8ad632e32dd.jpg)

![f96d27b92844820521f75879b2503d599ff11ede5b2762b4c55476e844ba489c.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/f96d27b92844820521f75879b2503d599ff11ede5b2762b4c55476e844ba489c.jpg)

![fcf64d2de80ba57232f6fd87381f36c66d0572273437c3a37e327665b151957c.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/images/fcf64d2de80ba57232f6fd87381f36c66d0572273437c3a37e327665b151957c.jpg)

### Tables

![0dfa5cae198d41bd1942832d49a6dfa0b46cbdd192819edeebfd2ba6b6aa2c60.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/tables/0dfa5cae198d41bd1942832d49a6dfa0b46cbdd192819edeebfd2ba6b6aa2c60.jpg)

![3d14617787f9c2d20ef5219a4ff79b8b9e471d2d850e628e7e10d2c250887b8e.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/tables/3d14617787f9c2d20ef5219a4ff79b8b9e471d2d850e628e7e10d2c250887b8e.jpg)

![8fed9a4eea26096eafd5d1696d5de433ba11c8297757376d0d9eb5a4974e92db.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/tables/8fed9a4eea26096eafd5d1696d5de433ba11c8297757376d0d9eb5a4974e92db.jpg)

![b434887adbc85291294f51aa9ab14f6fd139123c0622f6e9759bebd67f9354fb.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/tables/b434887adbc85291294f51aa9ab14f6fd139123c0622f6e9759bebd67f9354fb.jpg)

![be6e66d29c697248b2f3ef6235f3b054eb5a88a64d9229128cfc75b7072516fa.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/tables/be6e66d29c697248b2f3ef6235f3b054eb5a88a64d9229128cfc75b7072516fa.jpg)

![c3cf738171adc983218b15b607445919b6e295858c00464d7c5f35bcc1665b63.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/tables/c3cf738171adc983218b15b607445919b6e295858c00464d7c5f35bcc1665b63.jpg)

![cad20614dc00f88ee6c00fb5205cabfc0478781ae60d6596e97814d526edc18e.jpg](../nips_results/588_SimWorld_%20An%20Open-ended%20Simulator%20for%20Agents%20in%20Physical%20and%20Social%20Worlds/tables/cad20614dc00f88ee6c00fb5205cabfc0478781ae60d6596e97814d526edc18e.jpg)

## A learnability analysis on neuro-symbolic learning


### Images

![48384fe8f10e76e12909319383e22ea2651c394e46fa481ee30cd3b5b507e38e.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/images/48384fe8f10e76e12909319383e22ea2651c394e46fa481ee30cd3b5b507e38e.jpg)

![6a4562069c64a7afd9cba6700d29974f566dd83e09c32081facbf4e45374c34e.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/images/6a4562069c64a7afd9cba6700d29974f566dd83e09c32081facbf4e45374c34e.jpg)

![7a5dd42fb9f99450a63680aba1d64c4109419568065b6ed3115ae2aa7f660e50.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/images/7a5dd42fb9f99450a63680aba1d64c4109419568065b6ed3115ae2aa7f660e50.jpg)

![81114000c440b1510deec348c3c59f909deb8a2ee839229d31d13b32d3634c66.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/images/81114000c440b1510deec348c3c59f909deb8a2ee839229d31d13b32d3634c66.jpg)

![821db341c7b172204c977944c51b198ce9d79ea29f01b9648e01f247eead76c6.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/images/821db341c7b172204c977944c51b198ce9d79ea29f01b9648e01f247eead76c6.jpg)

![88bde67746de438022715901e467ccdab2e04324d793d4eee1f0225ce4513790.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/images/88bde67746de438022715901e467ccdab2e04324d793d4eee1f0225ce4513790.jpg)

![90a28c4ff01976cd234040f15e76e2d4c3c0f4c54ec0e9405235768deaa5cd95.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/images/90a28c4ff01976cd234040f15e76e2d4c3c0f4c54ec0e9405235768deaa5cd95.jpg)

![981e848ee41d96f80b46f1aada38a73ca5d6149a206a8e6290982ce33bc8c98e.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/images/981e848ee41d96f80b46f1aada38a73ca5d6149a206a8e6290982ce33bc8c98e.jpg)

![a3e0880942c174190174bcedbbce3d7c60996f6af48f183f1cbf0b103814eceb.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/images/a3e0880942c174190174bcedbbce3d7c60996f6af48f183f1cbf0b103814eceb.jpg)

![aa815f7fb2658ad362bb5e4baa99d0d15e1b8ae793d6c08bb8f433ad5b677007.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/images/aa815f7fb2658ad362bb5e4baa99d0d15e1b8ae793d6c08bb8f433ad5b677007.jpg)

### Tables

![13cba9298881a304eeca5e60c1ad835e913fcbdad6b16cb71c6d2138249b45fa.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/tables/13cba9298881a304eeca5e60c1ad835e913fcbdad6b16cb71c6d2138249b45fa.jpg)

![74db0764e75eeeb7f5ea5eb28451cdfaf4c1ca54cb6fd5f868c5e66611bd490d.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/tables/74db0764e75eeeb7f5ea5eb28451cdfaf4c1ca54cb6fd5f868c5e66611bd490d.jpg)

![bb44ace5678411678937d4d9216cb97ad21e1335a8c9295b3aa27f669bb22761.jpg](../nips_results/589_A%20learnability%20analysis%20on%20neuro-symbolic%20learning/tables/bb44ace5678411678937d4d9216cb97ad21e1335a8c9295b3aa27f669bb22761.jpg)

## Audio Flamingo 3: Advancing Audio Intelligence with Fully Open Large Audio Language Models

### Images

![02944a146f1b4fa354a6a77fafa85984cc93ec281d9e12c4991f2a71417df23a.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/02944a146f1b4fa354a6a77fafa85984cc93ec281d9e12c4991f2a71417df23a.jpg)

![05c61353c0c93a6ac4227d53af8957ef90826b0521002bcf60715f291aa51de1.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/05c61353c0c93a6ac4227d53af8957ef90826b0521002bcf60715f291aa51de1.jpg)

![15cc4c9b5aaa10b2e877c64a7f027edbd02f5d0f82f6b558399dfd23e7e8d065.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/15cc4c9b5aaa10b2e877c64a7f027edbd02f5d0f82f6b558399dfd23e7e8d065.jpg)

![1619854af05945a4c23e06852f9376d84e09f5c8cfab6f915ec75570537db345.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/1619854af05945a4c23e06852f9376d84e09f5c8cfab6f915ec75570537db345.jpg)

![1bf14d6bf548540f364bd9fcbd9c70fab40db21c6ca1b1cacab4702a6d81cd50.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/1bf14d6bf548540f364bd9fcbd9c70fab40db21c6ca1b1cacab4702a6d81cd50.jpg)

![2169d5f634bacf864ae697dda9f2bfc73346b459628f2e29d6cc9ef2b90bb2ca.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/2169d5f634bacf864ae697dda9f2bfc73346b459628f2e29d6cc9ef2b90bb2ca.jpg)

![2beed1342a74e5a66e989aebf4a3d4e55e51b48ae9ffbbc824d698462c28da49.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/2beed1342a74e5a66e989aebf4a3d4e55e51b48ae9ffbbc824d698462c28da49.jpg)

![36dcabe1a610d542d4153de92e9679ebff2e94936d9e870f51a09a673fd1478b.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/36dcabe1a610d542d4153de92e9679ebff2e94936d9e870f51a09a673fd1478b.jpg)

![37e48069756969e488f9bc89a08901ad37fea04c4a884e3369021932ef95a66a.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/37e48069756969e488f9bc89a08901ad37fea04c4a884e3369021932ef95a66a.jpg)

![3ef671601ac56a5c187ee93a06c6c4e1df0145126e391924d8f3e35d6b4d949f.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/3ef671601ac56a5c187ee93a06c6c4e1df0145126e391924d8f3e35d6b4d949f.jpg)

![4654ec1183be2b11de52cd2e4c2c3b153779c41ce5f6d71ad3c9b6c646d012a7.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/4654ec1183be2b11de52cd2e4c2c3b153779c41ce5f6d71ad3c9b6c646d012a7.jpg)

![4f7b2e90b65cc9f3265e0dd96f9de790134c0613f2868bf3ae2bf801066e7e5a.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/4f7b2e90b65cc9f3265e0dd96f9de790134c0613f2868bf3ae2bf801066e7e5a.jpg)

![538a4474af334f23774413519cc62ec81c21a3612d834f440c5f9b2ed263cfb4.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/538a4474af334f23774413519cc62ec81c21a3612d834f440c5f9b2ed263cfb4.jpg)

![5725b8130f0eb463ad06b3087dc46b58f69d2668a3818ae326de9d308ca94393.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/5725b8130f0eb463ad06b3087dc46b58f69d2668a3818ae326de9d308ca94393.jpg)

![5989e8856be1379b8cfe3b1a6d90bd9fcd6a2931dabf39d45b949ed6590d5199.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/5989e8856be1379b8cfe3b1a6d90bd9fcd6a2931dabf39d45b949ed6590d5199.jpg)

![5be3e70ebfcd4f0be66b74886717d0ecf653f1c4896fd94978fede9472b0465e.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/5be3e70ebfcd4f0be66b74886717d0ecf653f1c4896fd94978fede9472b0465e.jpg)

![5d5943245f27eed3c57e4686eb84755cda0fca4d59282be815ac75d7f6fdcd83.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/5d5943245f27eed3c57e4686eb84755cda0fca4d59282be815ac75d7f6fdcd83.jpg)

![5ef6d6bce7058d36800a1158cd2e8ef95d454146e0b4b9cf0affbc5fc04616a6.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/5ef6d6bce7058d36800a1158cd2e8ef95d454146e0b4b9cf0affbc5fc04616a6.jpg)

![62689769dafd2c3f7f86df0cae946f044d73836930f0a1f9e80855cd1f3b57d5.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/62689769dafd2c3f7f86df0cae946f044d73836930f0a1f9e80855cd1f3b57d5.jpg)

![6869904d40351c6db5ebefb8ef3f3d89491f3a086d6fe5c410abd96c5967dbae.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/6869904d40351c6db5ebefb8ef3f3d89491f3a086d6fe5c410abd96c5967dbae.jpg)

![698f216e2cef9de817d645f242d214e4062c8db60c0fcb611393301918eeae7d.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/698f216e2cef9de817d645f242d214e4062c8db60c0fcb611393301918eeae7d.jpg)

![6c10936f2cab14c6367d343f9cd83e8a9a40c8413289951e4befc38a9f5fd694.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/6c10936f2cab14c6367d343f9cd83e8a9a40c8413289951e4befc38a9f5fd694.jpg)

![779aa9a098f7bc036d692877d0aabf61e2f35a1f9cb611a566bcad0b3e166d76.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/779aa9a098f7bc036d692877d0aabf61e2f35a1f9cb611a566bcad0b3e166d76.jpg)

![789f2c1dfb57bd49ecdbf628ce3eda2618cb0b1f6de0defc048225e44445c2e5.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/789f2c1dfb57bd49ecdbf628ce3eda2618cb0b1f6de0defc048225e44445c2e5.jpg)

![7b568fc96ab91a922fce6b2ef82510bdb2d7f5d192ba382614691d48edbf0e6b.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/7b568fc96ab91a922fce6b2ef82510bdb2d7f5d192ba382614691d48edbf0e6b.jpg)

![8d7131ee9cb17d93c6d89a5ef20365d2e250b5aecf593700b472c94e41a26730.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/8d7131ee9cb17d93c6d89a5ef20365d2e250b5aecf593700b472c94e41a26730.jpg)

![9b1ebec202b9b30d02440073dd1c036b7a623bee85b6060e5728239850fa0200.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/9b1ebec202b9b30d02440073dd1c036b7a623bee85b6060e5728239850fa0200.jpg)

![9bb33d94b0998f710166e5d0b1b876e412edb496dfc49d6a5f8d046378ceae9a.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/9bb33d94b0998f710166e5d0b1b876e412edb496dfc49d6a5f8d046378ceae9a.jpg)

![a99b391e8783a28603afc5079221f743c060717938c3a4f75715b5f7e4788863.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/a99b391e8783a28603afc5079221f743c060717938c3a4f75715b5f7e4788863.jpg)

![ae52af059cb6d37e45ea1274260be3e5db3860af788f82522009b72eaf64971b.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/ae52af059cb6d37e45ea1274260be3e5db3860af788f82522009b72eaf64971b.jpg)

![b1bedfcfac9b5ae6438b68fad0176d6e904c6c5397c2b1077171c3d226737441.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/b1bedfcfac9b5ae6438b68fad0176d6e904c6c5397c2b1077171c3d226737441.jpg)

![b34bd4170e139438be95e94323e2dd2e0d05d7e07c6eeb018287f802f592de47.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/b34bd4170e139438be95e94323e2dd2e0d05d7e07c6eeb018287f802f592de47.jpg)

![bc4b6eb02f894655c658687aff9f885a22151a4fc973495dfead9b0d8d4e1b95.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/bc4b6eb02f894655c658687aff9f885a22151a4fc973495dfead9b0d8d4e1b95.jpg)

![bcabe2839dc3af37a7e71499f677266854eb3b83becad42314c19033c2ce2163.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/bcabe2839dc3af37a7e71499f677266854eb3b83becad42314c19033c2ce2163.jpg)

![c95ae7e2bb1a9f051e0038ff0b4e00e9436c8e3f7ae0a9dc669d6d530fe85353.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/c95ae7e2bb1a9f051e0038ff0b4e00e9436c8e3f7ae0a9dc669d6d530fe85353.jpg)

![c9d3178e78eb4e4453638188b65d853c0610f9130abb40c36c03bdee1a64cf86.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/c9d3178e78eb4e4453638188b65d853c0610f9130abb40c36c03bdee1a64cf86.jpg)

![ca9036841c06e881a57f74664c54bf7af88c6fdef1416a64e841c38a1ef6e3c5.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/ca9036841c06e881a57f74664c54bf7af88c6fdef1416a64e841c38a1ef6e3c5.jpg)

![cb66806e7663f5a020e286fe38478b440d253be58e73505454673b4d8c1f5082.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/cb66806e7663f5a020e286fe38478b440d253be58e73505454673b4d8c1f5082.jpg)

![cd010abd4c31fef5b24249d6772223e6631b83e35e3685966ce70fb91763981b.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/cd010abd4c31fef5b24249d6772223e6631b83e35e3685966ce70fb91763981b.jpg)

![cf71567a6640057f28f376328dcabea059229aa1b1b70f5493f2af85042a4bb7.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/cf71567a6640057f28f376328dcabea059229aa1b1b70f5493f2af85042a4bb7.jpg)

![db0f6040f0d73a334cc5b80c168307efd625908efcddfcdee9580eb9c29f1a6a.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/db0f6040f0d73a334cc5b80c168307efd625908efcddfcdee9580eb9c29f1a6a.jpg)

![e22d608e423003a3c351864754d9982ddbcdc6bc0a64ef9b6e8be4cf75563a06.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/e22d608e423003a3c351864754d9982ddbcdc6bc0a64ef9b6e8be4cf75563a06.jpg)

![e3d67d382e61362628769c54ecf46c80139eaf2489ec5d999656b736f0138e0a.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/e3d67d382e61362628769c54ecf46c80139eaf2489ec5d999656b736f0138e0a.jpg)

![e3ecfd906243333223346abe9b6099bbc6165dd971f872c990a01ec0c94ad142.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/e3ecfd906243333223346abe9b6099bbc6165dd971f872c990a01ec0c94ad142.jpg)

![e675a986c30c9207d3cdf89da44fbb3639948f39fd7769f29c1250c67f43b913.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/e675a986c30c9207d3cdf89da44fbb3639948f39fd7769f29c1250c67f43b913.jpg)

![e7a551c6ca47013ff70f27ecb857bde303e6e251313cd3ac4f48201013205709.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/e7a551c6ca47013ff70f27ecb857bde303e6e251313cd3ac4f48201013205709.jpg)

![ee84bb7e9de440f740996f429f3ec8367e3aa409e0f87f29c878fd2db793c24a.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/ee84bb7e9de440f740996f429f3ec8367e3aa409e0f87f29c878fd2db793c24a.jpg)

![eeb4cdeadf2ceda40eade8c54254097ee926466de59caae2b40f3e649cd61461.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/eeb4cdeadf2ceda40eade8c54254097ee926466de59caae2b40f3e649cd61461.jpg)

![ef1200cfa6e346482ce29bb067e89fb74f8c5b72a4dccd65083a464f0c6abe35.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/ef1200cfa6e346482ce29bb067e89fb74f8c5b72a4dccd65083a464f0c6abe35.jpg)

![f691e2d538383a9a1530a9d2b10014f05bd9513d516fa57846962273ed366742.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/f691e2d538383a9a1530a9d2b10014f05bd9513d516fa57846962273ed366742.jpg)

![fa7a447d1ba527422b524b438fb5983227a1e4b4f3c2480a5062329f9f008345.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/fa7a447d1ba527422b524b438fb5983227a1e4b4f3c2480a5062329f9f008345.jpg)

![ff36e781a40467e8792041f700280d7d50859822a7d16f01da6ef9acd7d88a5e.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/images/ff36e781a40467e8792041f700280d7d50859822a7d16f01da6ef9acd7d88a5e.jpg)

### Tables

![36fbb855c28a010f7e34f537a6c1a5ecbfdd4db64fa537d6e0565a8850889e62.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/36fbb855c28a010f7e34f537a6c1a5ecbfdd4db64fa537d6e0565a8850889e62.jpg)

![373adceafecda24c0ab6e37c45790c4543cad2d9bd188d60822188f91a489988.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/373adceafecda24c0ab6e37c45790c4543cad2d9bd188d60822188f91a489988.jpg)

![37eb19962473f3d174d6d57201047058794136557cfe10f805694e39323cd4d3.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/37eb19962473f3d174d6d57201047058794136557cfe10f805694e39323cd4d3.jpg)

![5d50d438e5b83c3904eb93fb044354c15ecf438c97cb361eafdac2f92b207deb.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/5d50d438e5b83c3904eb93fb044354c15ecf438c97cb361eafdac2f92b207deb.jpg)

![6bb9e4691a8a612b410bc1a41c1ea56bf9db2f29e8b6618188e5e740baaf2a4f.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/6bb9e4691a8a612b410bc1a41c1ea56bf9db2f29e8b6618188e5e740baaf2a4f.jpg)

![7382f8a47a8514f510a51de2e48d9668e241de849c14a2454aa6be8ecc875044.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/7382f8a47a8514f510a51de2e48d9668e241de849c14a2454aa6be8ecc875044.jpg)

![779961e383f1f7e3de2621e562bb211f246ad15fccdb296bc687f69c77b19eed.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/779961e383f1f7e3de2621e562bb211f246ad15fccdb296bc687f69c77b19eed.jpg)

![77abb545637054bfa05e3b42c338f4655085062fdf519fe84a14460c665bb518.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/77abb545637054bfa05e3b42c338f4655085062fdf519fe84a14460c665bb518.jpg)

![863e7656a754aa48198bf09e2ffc192734777724a9074b7646fe4401a4555be1.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/863e7656a754aa48198bf09e2ffc192734777724a9074b7646fe4401a4555be1.jpg)

![a9d1dca223961139b6bc2e3fa23a3fecd4cb97de9fed18f119af0a16be2eae03.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/a9d1dca223961139b6bc2e3fa23a3fecd4cb97de9fed18f119af0a16be2eae03.jpg)

![b5503f6d19a1c6ff25936b6396caad97be0646537e059903a44b488a110eef64.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/b5503f6d19a1c6ff25936b6396caad97be0646537e059903a44b488a110eef64.jpg)

![ea387dd32c736b9f5084182ce1b962d0a7a8ad4a6bbf6d27ade16b660f8b883d.jpg](../nips_results/590_Audio%20Flamingo%203_%20Advancing%20Audio%20Intelligence%20with%20Fully%20Open%20Large%20Audio%20Language%20Models/tables/ea387dd32c736b9f5084182ce1b962d0a7a8ad4a6bbf6d27ade16b660f8b883d.jpg)
