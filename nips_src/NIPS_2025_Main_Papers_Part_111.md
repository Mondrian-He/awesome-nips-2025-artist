# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 111 of 130

## 目录 (Table of Contents)

1. [CAMO: Convergence-Aware Multi-Fidelity Bayesian Optimization](#CAMO-Convergence-Aware-Multi-Fidelity-Bayesian-Optimization)
2. [Temporal-Difference Variational Continual Learning](#Temporal-Difference-Variational-Continual-Learning)
3. [Confounding Robust Deep Reinforcement Learning: A Causal Approach](#Confounding-Robust-Deep-Reinforcement-Learning-A-Causal-Approach)
4. [Unifying Text Semantics and Graph Structures for Temporal Text-attributed Graphs with Large Language Models](#Unifying-Text-Semantics-and-Graph-Structures-for-Temporal-Text-attributed-Graphs-with-Large-Language-Models)
5. [Pancakes: Consistent Multi-Protocol Image Segmentation Across Biomedical Domains](#Pancakes-Consistent-Multi-Protocol-Image-Segmentation-Across-Biomedical-Domains)
6. [CodeMerge: Codebook-Guided Model Merging for Robust Test-Time Adaptation in Autonomous Driving](#CodeMerge-Codebook-Guided-Model-Merging-for-Robust-Test-Time-Adaptation-in-Autonomous-Driving)
7. [DenoiseRotator: Enhance Pruning Robustness for LLMs via Importance Concentration](#DenoiseRotator-Enhance-Pruning-Robustness-for-LLMs-via-Importance-Concentration)
8. [Exploring the Design Space of Diffusion Bridge Models](#Exploring-the-Design-Space-of-Diffusion-Bridge-Models)
9. [MODEL SHAPLEY: Find Your Ideal Parameter Player via One Gradient Backpropagation](#MODEL-SHAPLEY-Find-Your-Ideal-Parameter-Player-via-One-Gradient-Backpropagation)
10. [From Pretraining to Pathology: How Noise Leads to Catastrophic Inheritance in Medical Models](#From-Pretraining-to-Pathology-How-Noise-Leads-to-Catastrophic-Inheritance-in-Medical-Models)
11. [From Faults to Features: Pretraining to Learn Robust Representations against Sensor Failures](#From-Faults-to-Features-Pretraining-to-Learn-Robust-Representations-against-Sensor-Failures)
12. [EgoThinker: Unveiling Egocentric Reasoning with Spatio-Temporal CoT](#EgoThinker-Unveiling-Egocentric-Reasoning-with-Spatio-Temporal-CoT)
13. [Lifelong Safety Alignment for Language Models](#Lifelong-Safety-Alignment-for-Language-Models)
14. [Fuse2Match: Training-Free Fusion of Flow, Diffusion, and Contrastive Models for Zero-Shot Semantic Matching](#Fuse2Match-Training-Free-Fusion-of-Flow-Diffusion-and-Contrastive-Models-for-Zero-Shot-Semantic-Matching)
15. [AltLoRA: Towards Better Gradient Approximation in Low-Rank Adaptation with Alternating Projections](#AltLoRA-Towards-Better-Gradient-Approximation-in-Low-Rank-Adaptation-with-Alternating-Projections)
16. [RAD: Training an End-to-End Driving Policy via Large-Scale 3DGS-based Reinforcement Learning](#RAD-Training-an-End-to-End-Driving-Policy-via-Large-Scale-3DGS-based-Reinforcement-Learning)
17. [When Models Know More Than They Can Explain: Quantifying Knowledge Transfer in Human-AI Collaboration](#When-Models-Know-More-Than-They-Can-Explain-Quantifying-Knowledge-Transfer-in-Human-AI-Collaboration)
18. [SRA-CL: Semantic Retrieval Augmented Contrastive Learning for Sequential Recommendation](#SRA-CL-Semantic-Retrieval-Augmented-Contrastive-Learning-for-Sequential-Recommendation)
19. [Eulerian Neural Network Informed by Chemical Transport for Air Quality Forecasting](#Eulerian-Neural-Network-Informed-by-Chemical-Transport-for-Air-Quality-Forecasting)
20. [Sample Complexity of Distributionally Robust Average-Reward Reinforcement Learning](#Sample-Complexity-of-Distributionally-Robust-Average-Reward-Reinforcement-Learning)
21. [Distributionally Robust Feature Selection](#Distributionally-Robust-Feature-Selection)
22. [Unveiling the Uncertainty in Embodied and Operational Carbon of Large AI Models through a Probabilistic Carbon Accounting Model](#Unveiling-the-Uncertainty-in-Embodied-and-Operational-Carbon-of-Large-AI-Models-through-a-Probabilistic-Carbon-Accounting-Model)
23. [FedRACE: A Hierarchical and Statistical Framework for Robust Federated Learning](#FedRACE-A-Hierarchical-and-Statistical-Framework-for-Robust-Federated-Learning)
24. [JanusDNA: A Powerful Bi-directional Hybrid DNA Foundation Model](#JanusDNA-A-Powerful-Bi-directional-Hybrid-DNA-Foundation-Model)
25. [OpenMMEgo: Enhancing Egocentric Understanding for LMMs with Open Weights and Data](#OpenMMEgo-Enhancing-Egocentric-Understanding-for-LMMs-with-Open-Weights-and-Data)
26. [TrajAgent: An LLM-Agent Framework for Trajectory Modeling via Large-and-Small Model Collaboration](#TrajAgent-An-LLM-Agent-Framework-for-Trajectory-Modeling-via-Large-and-Small-Model-Collaboration)
27. [Simple and Optimal Sublinear Algorithms for Mean Estimation](#Simple-and-Optimal-Sublinear-Algorithms-for-Mean-Estimation)
28. [Agnostic Continuous-Time Online Learning](#Agnostic-Continuous-Time-Online-Learning)
29. [Pattern-Guided Adaptive Prior for Structure Learning](#Pattern-Guided-Adaptive-Prior-for-Structure-Learning)
30. [Improving Reward Models with Proximal Policy Exploration for Preference-Based Reinforcement Learning](#Improving-Reward-Models-with-Proximal-Policy-Exploration-for-Preference-Based-Reinforcement-Learning)
31. [Multiplayer Federated Learning: Reaching Equilibrium with Less Communication](#Multiplayer-Federated-Learning-Reaching-Equilibrium-with-Less-Communication)
32. [Generation as Search Operator for Test-Time Scaling of Diffusion-based Combinatorial Optimization](#Generation-as-Search-Operator-for-Test-Time-Scaling-of-Diffusion-based-Combinatorial-Optimization)
33. [Improving Retrieval-Augmented Generation through Multi-Agent Reinforcement Learning](#Improving-Retrieval-Augmented-Generation-through-Multi-Agent-Reinforcement-Learning)
34. [Global Convergence for Average Reward Constrained MDPs with Primal-Dual Actor Critic Algorithm](#Global-Convergence-for-Average-Reward-Constrained-MDPs-with-Primal-Dual-Actor-Critic-Algorithm)
35. [Efficient and Generalizable Mixed-Precision Quantization via Topological Entropy](#Efficient-and-Generalizable-Mixed-Precision-Quantization-via-Topological-Entropy)
36. [Compute-Optimal Scaling for Value-Based Deep RL](#Compute-Optimal-Scaling-for-Value-Based-Deep-RL)
37. [Sloth: scaling laws for LLM skills to predict multi-benchmark performance across families](#Sloth-scaling-laws-for-LLM-skills-to-predict-multi-benchmark-performance-across-families)
38. [SGAR: Structural Generative Augmentation for 3D Human Motion Retrieval](#SGAR-Structural-Generative-Augmentation-for-3D-Human-Motion-Retrieval)
39. [Inexact Column Generation for Bayesian Network Structure Learning via Difference-of-Submodular Optimization](#Inexact-Column-Generation-for-Bayesian-Network-Structure-Learning-via-Difference-of-Submodular-Optimization)
40. [Isotropic Noise in Stochastic and Quantum Convex Optimization](#Isotropic-Noise-in-Stochastic-and-Quantum-Convex-Optimization)
41. [Hierarchical Demonstration Order Optimization for Many-shot In-Context Learning](#Hierarchical-Demonstration-Order-Optimization-for-Many-shot-In-Context-Learning)

---


## CAMO: Convergence-Aware Multi-Fidelity Bayesian Optimization

### Images

![1666cfa222f4d18a2c4266f364ae4a437d2b75ea1a2ba594bbcae528503f36a5.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/images/1666cfa222f4d18a2c4266f364ae4a437d2b75ea1a2ba594bbcae528503f36a5.jpg)

![190598e0ac4d44a6c9e7688c50d5adc9fdb0719f6a9919435d4ce0a053f2518a.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/images/190598e0ac4d44a6c9e7688c50d5adc9fdb0719f6a9919435d4ce0a053f2518a.jpg)

![46a6382b40c712edb504eac91c061aa8bdfa70cd4b79c80462f136c969043b06.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/images/46a6382b40c712edb504eac91c061aa8bdfa70cd4b79c80462f136c969043b06.jpg)

![8ac47cd778cb29c3bfa4717bf424be790d3b21a28c81682001cc60aad6deb8f1.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/images/8ac47cd778cb29c3bfa4717bf424be790d3b21a28c81682001cc60aad6deb8f1.jpg)

![bafc2b4e6b341a1614898d56706f0b5f645273c859b2acc1d25c03c679963da1.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/images/bafc2b4e6b341a1614898d56706f0b5f645273c859b2acc1d25c03c679963da1.jpg)

![eddb350c37b321d4d22e933043196ad3e2f1aed7fb41ebdccfda7a2b7ad003e8.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/images/eddb350c37b321d4d22e933043196ad3e2f1aed7fb41ebdccfda7a2b7ad003e8.jpg)

### Tables

![1222177a028d4eab3449ca6d12bc958e8b3d74c82487fae0eac968fb68dac3b7.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/tables/1222177a028d4eab3449ca6d12bc958e8b3d74c82487fae0eac968fb68dac3b7.jpg)

![52e64e645b2f8e2f6c9a40d87d82a174f8f8606669089fcb270e3d6f8f225278.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/tables/52e64e645b2f8e2f6c9a40d87d82a174f8f8606669089fcb270e3d6f8f225278.jpg)

![53f0879d6ecf98454c3d6db8ee669971cc5dddca444e1a192a22ce0426e7f10d.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/tables/53f0879d6ecf98454c3d6db8ee669971cc5dddca444e1a192a22ce0426e7f10d.jpg)

![64dc24aa8ffa90cc33e8f0f5e5e55f43baabbbda41a6788ed1b1536f10bc0b3c.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/tables/64dc24aa8ffa90cc33e8f0f5e5e55f43baabbbda41a6788ed1b1536f10bc0b3c.jpg)

![861eef01630920531e69e459461bee204ea537ebd569158824a2fe700986a714.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/tables/861eef01630920531e69e459461bee204ea537ebd569158824a2fe700986a714.jpg)

![cebc6e082e1b54b58f12e4e532e14689b0f8c43af2ca673d2dfba02f7e692d11.jpg](../nips_results/4557_Secure%20and%20Confidential%20Certificates%20of%20Online%20Fairness/tables/cebc6e082e1b54b58f12e4e532e14689b0f8c43af2ca673d2dfba02f7e692d11.jpg)

## CAMO: Convergence-Aware Multi-Fidelity Bayesian Optimization


### Images

![0355ca01836937cee5901124a9227dbb3b2ac45ba96e7730981d75d7f28cb17f.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/0355ca01836937cee5901124a9227dbb3b2ac45ba96e7730981d75d7f28cb17f.jpg)

![05a61f0dbfc2bd5c6687f77ff4ad667ee9666ef880adb64a4415c35da8a97915.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/05a61f0dbfc2bd5c6687f77ff4ad667ee9666ef880adb64a4415c35da8a97915.jpg)

![12faadf8e681df19c4309e0b65e5d17fb6bcade9255d84fdca6dadc89b07fa3e.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/12faadf8e681df19c4309e0b65e5d17fb6bcade9255d84fdca6dadc89b07fa3e.jpg)

![2d25e65074771461c69abf78360ec91904bc0c948cce79c2d369f0acd14d8b60.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/2d25e65074771461c69abf78360ec91904bc0c948cce79c2d369f0acd14d8b60.jpg)

![37ec5b8384f2c1f61e181c0b8e200a41d52ad941edbd0d4530f970bc157b3891.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/37ec5b8384f2c1f61e181c0b8e200a41d52ad941edbd0d4530f970bc157b3891.jpg)

![4a310216bad0bc8892af663a91f8137141d0910a0e65fa53eb4c29df999353c6.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/4a310216bad0bc8892af663a91f8137141d0910a0e65fa53eb4c29df999353c6.jpg)

![616f322eea7d6f19facedf21ea0a4dbb42493941f97892895621bdc950c82892.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/616f322eea7d6f19facedf21ea0a4dbb42493941f97892895621bdc950c82892.jpg)

![62f007004712f9c927dc584772d351d6f63707bc92d2b6998e3781b852a64f8f.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/62f007004712f9c927dc584772d351d6f63707bc92d2b6998e3781b852a64f8f.jpg)

![64a1d344721dd5b9b186acde2acaed914ca1c819a7dea94a8f76b22c07b5cab2.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/64a1d344721dd5b9b186acde2acaed914ca1c819a7dea94a8f76b22c07b5cab2.jpg)

![64de31e9e487dc456d60e9ee92b0e5c894fb3ea5191fecf561c704b8051a591a.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/64de31e9e487dc456d60e9ee92b0e5c894fb3ea5191fecf561c704b8051a591a.jpg)

![7088af7794e96c39e9f2260929e1511e47df6b90255b2b0dafc1babe2e75c9a9.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/7088af7794e96c39e9f2260929e1511e47df6b90255b2b0dafc1babe2e75c9a9.jpg)

![74ab93fc7a115625f2acd5e67f66af7ce9c6851d3b1f65b641a544420869f7f0.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/74ab93fc7a115625f2acd5e67f66af7ce9c6851d3b1f65b641a544420869f7f0.jpg)

![7bc5b6fb586e4a1a12302acf6568a6dc530ed9f5137212846994ad3c4363f458.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/7bc5b6fb586e4a1a12302acf6568a6dc530ed9f5137212846994ad3c4363f458.jpg)

![8c08f5a29882daaf21ff942041dc1372c0b6e200430168384796a1d1b28bf834.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/8c08f5a29882daaf21ff942041dc1372c0b6e200430168384796a1d1b28bf834.jpg)

![9a3a554e4f722f5aa0a4635b74430b34ee15f7f6131aa74039fa69470ba6fc3c.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/9a3a554e4f722f5aa0a4635b74430b34ee15f7f6131aa74039fa69470ba6fc3c.jpg)

![b05be183d64317e90802358755e01888db67a4fef594a3f1f2799cd0da1dd11c.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/b05be183d64317e90802358755e01888db67a4fef594a3f1f2799cd0da1dd11c.jpg)

![b351570df7d6790e3aed1bd8e0a86f12ee6ea028713a04a95bd0ead53f4545cd.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/b351570df7d6790e3aed1bd8e0a86f12ee6ea028713a04a95bd0ead53f4545cd.jpg)

![e8f77d3325d34292f62f0e3e661f0c3367f5e13b37a1c614a71fa01270aa7f8a.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/e8f77d3325d34292f62f0e3e661f0c3367f5e13b37a1c614a71fa01270aa7f8a.jpg)

![f87d81eb7c8f1d0a7b91b042db0d1dec34abc20950df3172b3dce231a013721a.jpg](../nips_results/4558_CAMO_%20Convergence-Aware%20Multi-Fidelity%20Bayesian%20Optimization/images/f87d81eb7c8f1d0a7b91b042db0d1dec34abc20950df3172b3dce231a013721a.jpg)

## Temporal-Difference Variational Continual Learning


### Images

![0c0a16161cd9bf6faa547e982867fee5eba7d798c9743bd2c7b43259801c4ba0.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/images/0c0a16161cd9bf6faa547e982867fee5eba7d798c9743bd2c7b43259801c4ba0.jpg)

![28619e9eb376dd8da23026ebe181837531e36e5eaa4e00e6a03f7c73060394c0.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/images/28619e9eb376dd8da23026ebe181837531e36e5eaa4e00e6a03f7c73060394c0.jpg)

![354d282aaf49719169435c7407b7433bc093492bef10bc701eac7649e8f84eca.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/images/354d282aaf49719169435c7407b7433bc093492bef10bc701eac7649e8f84eca.jpg)

![4defe6f0880143adfe1c4539c8e8d455fb40819c368884e6cc6e43f563febd73.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/images/4defe6f0880143adfe1c4539c8e8d455fb40819c368884e6cc6e43f563febd73.jpg)

![679718f5ba0b1512e857aee734265f70f34de5792c8c8d02123507a257405b2d.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/images/679718f5ba0b1512e857aee734265f70f34de5792c8c8d02123507a257405b2d.jpg)

![79cc63256c86ec6a5156d818c09f9483631bd176cc05c1512b5aec6a56fb97eb.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/images/79cc63256c86ec6a5156d818c09f9483631bd176cc05c1512b5aec6a56fb97eb.jpg)

![9f2e1fdc41a76bf0ae8018d56601a0d6f99088e3d6cef31e6200846c024faad2.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/images/9f2e1fdc41a76bf0ae8018d56601a0d6f99088e3d6cef31e6200846c024faad2.jpg)

![d447e22042ecb6794de20f075cdca92e830559ee36b7d094e8be128aaa5f3a93.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/images/d447e22042ecb6794de20f075cdca92e830559ee36b7d094e8be128aaa5f3a93.jpg)

![dd36e15c55cc8e309e017cf539e5fd093675d57656df86cb0606cf560cc23321.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/images/dd36e15c55cc8e309e017cf539e5fd093675d57656df86cb0606cf560cc23321.jpg)

![e7263b94ce6c6d9904e896e1f121f06fd6a502d389486317015fd515985bad8a.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/images/e7263b94ce6c6d9904e896e1f121f06fd6a502d389486317015fd515985bad8a.jpg)

![eb00f780aab995a8cdf4ff42cb45813b4ec169248fc6d4ff50383a166249ec39.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/images/eb00f780aab995a8cdf4ff42cb45813b4ec169248fc6d4ff50383a166249ec39.jpg)

### Tables

![25cd24c205a92071137d77c40fc17e7bec4b46c7fb20483ab8c2ff0b4634873d.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/tables/25cd24c205a92071137d77c40fc17e7bec4b46c7fb20483ab8c2ff0b4634873d.jpg)

![442ad5d9ca7a6373e63dfcd1e746d899e2d7e5c3c4c90ac7ae92e8721d05dc6f.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/tables/442ad5d9ca7a6373e63dfcd1e746d899e2d7e5c3c4c90ac7ae92e8721d05dc6f.jpg)

![85378988e46b46cc170fec92cd42bf9f77fda24777d5c0e3174ac6666004800f.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/tables/85378988e46b46cc170fec92cd42bf9f77fda24777d5c0e3174ac6666004800f.jpg)

![86949db7d31c218105ec3e14a77eb64fac29d53b11edae520161b5152624ab03.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/tables/86949db7d31c218105ec3e14a77eb64fac29d53b11edae520161b5152624ab03.jpg)

![882ebb3b22b4debbdd0f3b95821fc3e7783655ccb3490a6342fed3d011bad6bc.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/tables/882ebb3b22b4debbdd0f3b95821fc3e7783655ccb3490a6342fed3d011bad6bc.jpg)

![a8337939098838ee85e1cfdccdfc2b226cf12f692f88c9bb956374b79275bd43.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/tables/a8337939098838ee85e1cfdccdfc2b226cf12f692f88c9bb956374b79275bd43.jpg)

![d4ca8ec7b80a6e6ceb7cab168c1b3ca364185b6df7729866cedb4d5c0b72a1cb.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/tables/d4ca8ec7b80a6e6ceb7cab168c1b3ca364185b6df7729866cedb4d5c0b72a1cb.jpg)

![db6dcfd592e21b355e751ba7f65de0f4f30e3c9efd251dfd4ed29e0bb2ffdfa0.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/tables/db6dcfd592e21b355e751ba7f65de0f4f30e3c9efd251dfd4ed29e0bb2ffdfa0.jpg)

![ded0d1498c3d38da77b112c46454b900f8c90a781799f9f4352a516391802980.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/tables/ded0d1498c3d38da77b112c46454b900f8c90a781799f9f4352a516391802980.jpg)

![e6ef65faa10a8e2a73d27a7668a7446480afa46a946527b4f850f6eef15cda4c.jpg](../nips_results/4559_Temporal-Difference%20Variational%20Continual%20Learning/tables/e6ef65faa10a8e2a73d27a7668a7446480afa46a946527b4f850f6eef15cda4c.jpg)

## Confounding Robust Deep Reinforcement Learning: A Causal Approach


### Images

![1f6ee97dd2ed6ad770c573aff5c78a2679b8b58214338ae583cbeb2e97eb590c.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/1f6ee97dd2ed6ad770c573aff5c78a2679b8b58214338ae583cbeb2e97eb590c.jpg)

![2eeb16002b913135289b043f52499baafb7f48efe1e2152aacb9423df72e13c2.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/2eeb16002b913135289b043f52499baafb7f48efe1e2152aacb9423df72e13c2.jpg)

![5a001b86978c2d89e1118d2a2097e6058c0e38f1dca678ce91730e8763e4f665.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/5a001b86978c2d89e1118d2a2097e6058c0e38f1dca678ce91730e8763e4f665.jpg)

![5dae184d7e9019d9765c2fa1ba56226f6f0202236d1af7d862145ebf85063fd0.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/5dae184d7e9019d9765c2fa1ba56226f6f0202236d1af7d862145ebf85063fd0.jpg)

![644d8706d1bc6a5d506efcea7ca983ec48e988312909e852292f3cdf17ffc891.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/644d8706d1bc6a5d506efcea7ca983ec48e988312909e852292f3cdf17ffc891.jpg)

![8bd4f857555205bc179e257ace5eaf021519ed3c8c80d36d62459982dada81e2.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/8bd4f857555205bc179e257ace5eaf021519ed3c8c80d36d62459982dada81e2.jpg)

![954bc674a4156b085d67cccc44a7ddfbc7331e115e67903b03e520c2df72912b.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/954bc674a4156b085d67cccc44a7ddfbc7331e115e67903b03e520c2df72912b.jpg)

![9b790931bc728bcb7131adf355a812fd27c24cbedf07448cc8805e57a3b46ed6.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/9b790931bc728bcb7131adf355a812fd27c24cbedf07448cc8805e57a3b46ed6.jpg)

![aeb3b6fbd5a647e97d134e33bde723bd9ffac355b3396aa51a3a889605ceb078.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/aeb3b6fbd5a647e97d134e33bde723bd9ffac355b3396aa51a3a889605ceb078.jpg)

![cb125af50d6bd1fe6a9bb2ace0f8b333a93794e4ca572b8bf6bd2b5bbc2b8f62.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/cb125af50d6bd1fe6a9bb2ace0f8b333a93794e4ca572b8bf6bd2b5bbc2b8f62.jpg)

![da387c3e88110ca0ac5b06a99fe889de2c30930089e01b423f5745db973986ae.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/da387c3e88110ca0ac5b06a99fe889de2c30930089e01b423f5745db973986ae.jpg)

![ed2fbeef2927d90db71cf957c8fdfd3a4729ce460a6bca92c7c072488943132e.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/ed2fbeef2927d90db71cf957c8fdfd3a4729ce460a6bca92c7c072488943132e.jpg)

![edbe37d5aecbf784f4bb34a9defc8ce3e134df3aa7ea0d0a0964e7f6a86a7599.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/images/edbe37d5aecbf784f4bb34a9defc8ce3e134df3aa7ea0d0a0964e7f6a86a7599.jpg)

### Tables

![3dfee1d8c777cec83de986e9249c7a60a5dd3b73e71bc0ca68cb82b228c7ae2b.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/tables/3dfee1d8c777cec83de986e9249c7a60a5dd3b73e71bc0ca68cb82b228c7ae2b.jpg)

![80fc894a2226ed66a7af4598fa021d768fa75323097c25465f7075b0e4f4426b.jpg](../nips_results/4560_Confounding%20Robust%20Deep%20Reinforcement%20Learning_%20A%20Causal%20Approach/tables/80fc894a2226ed66a7af4598fa021d768fa75323097c25465f7075b0e4f4426b.jpg)

## Unifying Text Semantics and Graph Structures for Temporal Text-attributed Graphs with Large Language Models


### Images

![2e56c6e311c059dab9133e4acb4848c058972a7f2f1406acde3a3b92d54939c1.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/2e56c6e311c059dab9133e4acb4848c058972a7f2f1406acde3a3b92d54939c1.jpg)

![34fa549ab1b12c4d71eec7a831c84befe301bebd8330398b452fd356c88d074b.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/34fa549ab1b12c4d71eec7a831c84befe301bebd8330398b452fd356c88d074b.jpg)

![3e6a6cd3ff289bd0d95f524eb9c86055bfbba87bbb277127c90b5281785a6fd4.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/3e6a6cd3ff289bd0d95f524eb9c86055bfbba87bbb277127c90b5281785a6fd4.jpg)

![4058c92e92078907528883b900cec35a165343d385c51f954432f8a8dd432072.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/4058c92e92078907528883b900cec35a165343d385c51f954432f8a8dd432072.jpg)

![56b9c876210923c37c0be00f724f68049f40a3f61a2f8d00db08f54392a2fdd9.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/56b9c876210923c37c0be00f724f68049f40a3f61a2f8d00db08f54392a2fdd9.jpg)

![7b0f37e70fc71e3a7444d49e03b8b6f0bd2401f0029dae76585eca4a544c7991.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/7b0f37e70fc71e3a7444d49e03b8b6f0bd2401f0029dae76585eca4a544c7991.jpg)

![9a2c6a1479a3062c17d129ef8b69957300143173614f29c9b07f778dcf7fafef.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/9a2c6a1479a3062c17d129ef8b69957300143173614f29c9b07f778dcf7fafef.jpg)

![9f8b1412ffe7e1186ae29d62ff79d0c5149203a40b23c14801b087c5d282ae30.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/9f8b1412ffe7e1186ae29d62ff79d0c5149203a40b23c14801b087c5d282ae30.jpg)

![b196591f6ea48ac146faa3177feb88712cb59d23cdd83874cb20d13237710a46.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/b196591f6ea48ac146faa3177feb88712cb59d23cdd83874cb20d13237710a46.jpg)

![b4226293232f2e466935d84f1a7738519770cc034b7ff8de6d491e92216fd44e.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/b4226293232f2e466935d84f1a7738519770cc034b7ff8de6d491e92216fd44e.jpg)

![c087fe73f2cd9412e59fddf0cecb801cc7d78c63d2bb919a04ebd3e1f5713f17.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/c087fe73f2cd9412e59fddf0cecb801cc7d78c63d2bb919a04ebd3e1f5713f17.jpg)

![c2cf82ccb8da7b1477be303ba66a93fd961152e1dfd0f8c36da6dc25b53f3cde.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/c2cf82ccb8da7b1477be303ba66a93fd961152e1dfd0f8c36da6dc25b53f3cde.jpg)

![c9513468d34820bddc405541a1422b645d4b5fe22770ffec74edfafaaa1e980d.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/c9513468d34820bddc405541a1422b645d4b5fe22770ffec74edfafaaa1e980d.jpg)

![d7b119351b8537594ac0c947fe9ab08441a05652b369e7feff18df477250f59f.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/d7b119351b8537594ac0c947fe9ab08441a05652b369e7feff18df477250f59f.jpg)

![d8e4a9650a72406c344e9bf9ec15957c35b32507691f3163dd7826430aec0d06.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/d8e4a9650a72406c344e9bf9ec15957c35b32507691f3163dd7826430aec0d06.jpg)

![e3e96dc1f8e7ef1499e24eb4dd3d64f00d9a489d09de7ebccb808139ac7c5b6a.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/e3e96dc1f8e7ef1499e24eb4dd3d64f00d9a489d09de7ebccb808139ac7c5b6a.jpg)

![e75218d1eac523aab0e023ab703d8d5a990dd5cd4619831a0f3cbc6eec753f9c.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/e75218d1eac523aab0e023ab703d8d5a990dd5cd4619831a0f3cbc6eec753f9c.jpg)

![f5946e78015fb7532fdc1a5fafb6cb83b3957a08fd2b244d888c9d44bacbd313.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/f5946e78015fb7532fdc1a5fafb6cb83b3957a08fd2b244d888c9d44bacbd313.jpg)

![f8aa5a3a281aba7bab711e6ba2002b902cadc276de20b958e4d1198c30c3f85b.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/f8aa5a3a281aba7bab711e6ba2002b902cadc276de20b958e4d1198c30c3f85b.jpg)

![fb2b97a91b2573a27ed120ba98c5daacbf7847d7f239551aa13500199991fcc1.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/images/fb2b97a91b2573a27ed120ba98c5daacbf7847d7f239551aa13500199991fcc1.jpg)

### Tables

![121a36c34719552e559a555fb6a5a36e380b0eded68d3e300c751bda02fcd91e.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/121a36c34719552e559a555fb6a5a36e380b0eded68d3e300c751bda02fcd91e.jpg)

![1e654d4609599100571ef2b5501438c48851f172c715ecde575b3caec975f154.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/1e654d4609599100571ef2b5501438c48851f172c715ecde575b3caec975f154.jpg)

![226fc95be848c73242caaa7e1cc481e3aab43fc03d7f2e113d6917ed9bd0910b.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/226fc95be848c73242caaa7e1cc481e3aab43fc03d7f2e113d6917ed9bd0910b.jpg)

![3d8eec88351154b39dc24c9ddcfc4ac79e2314b2f126a6b080af135cc9ec3847.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/3d8eec88351154b39dc24c9ddcfc4ac79e2314b2f126a6b080af135cc9ec3847.jpg)

![4b3de309027e7bd0e3bb59e736c4662e758cbd458c37535b41ba6a102dabedd3.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/4b3de309027e7bd0e3bb59e736c4662e758cbd458c37535b41ba6a102dabedd3.jpg)

![7abc535ba28f117474232fc181c4d5ebdd85a461bada519e5850d5f2b3a36809.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/7abc535ba28f117474232fc181c4d5ebdd85a461bada519e5850d5f2b3a36809.jpg)

![8c7ef047c2c5879da08c619703ea9a4a7b7af879cdc3d805c5f336cf7cb53fce.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/8c7ef047c2c5879da08c619703ea9a4a7b7af879cdc3d805c5f336cf7cb53fce.jpg)

![934d6cbcfb0bec9e9c5fc8becef198733f4cf9c52e33020374f5d73ac6bc5ebd.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/934d6cbcfb0bec9e9c5fc8becef198733f4cf9c52e33020374f5d73ac6bc5ebd.jpg)

![a43984683fc927b8e60c78a58b89ab3486fa052a9129e620e656bd565ca728ef.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/a43984683fc927b8e60c78a58b89ab3486fa052a9129e620e656bd565ca728ef.jpg)

![ab0038a4cb56455c0267b2e4efa650ae0b8d834e89a800938dcd8ca7d21d2ca0.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/ab0038a4cb56455c0267b2e4efa650ae0b8d834e89a800938dcd8ca7d21d2ca0.jpg)

![d3af058aa515b5eec03003c95a4961a75b52fd0d6953caf61b05dfa7df002932.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/d3af058aa515b5eec03003c95a4961a75b52fd0d6953caf61b05dfa7df002932.jpg)

![f2890afbaf573a855140c128eaa3f01381917aff371cfd6bc47a20034493aff6.jpg](../nips_results/4561_Unifying%20Text%20Semantics%20and%20Graph%20Structures%20for%20Temporal%20Text-attributed%20Graphs%20with%20Large%20Language/tables/f2890afbaf573a855140c128eaa3f01381917aff371cfd6bc47a20034493aff6.jpg)

## Pancakes: Consistent Multi-Protocol Image Segmentation Across Biomedical Domains


### Images

![02263399336327a8811f326615d769bb585868fefa44a977b267ab0dd35dcae1.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/02263399336327a8811f326615d769bb585868fefa44a977b267ab0dd35dcae1.jpg)

![09a3f606c9cf8b9e9c6f8fde12fd8bda2f307ac10b72d3ddda9429d73be5f0da.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/09a3f606c9cf8b9e9c6f8fde12fd8bda2f307ac10b72d3ddda9429d73be5f0da.jpg)

![12b3255df5f2dd6b41230c5a84d75710686ada7461c1341ffd88d0cde74a7028.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/12b3255df5f2dd6b41230c5a84d75710686ada7461c1341ffd88d0cde74a7028.jpg)

![173e03ebe4ac01077d89e6bf7bb2f6af06d4b4b95c7665634f49ac694419718b.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/173e03ebe4ac01077d89e6bf7bb2f6af06d4b4b95c7665634f49ac694419718b.jpg)

![1d530a87e98db09da9c3d0b1b09c97f87017905f0bf342cfdc52b5f046e75957.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/1d530a87e98db09da9c3d0b1b09c97f87017905f0bf342cfdc52b5f046e75957.jpg)

![29ca367ed43bb33768ed5103eee8d25c2b4d1de287c19cefb23423326511bacc.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/29ca367ed43bb33768ed5103eee8d25c2b4d1de287c19cefb23423326511bacc.jpg)

![37a56faec1e7e834f1e082ccee333ec7f4579fc5519cfac0b121608980bff6be.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/37a56faec1e7e834f1e082ccee333ec7f4579fc5519cfac0b121608980bff6be.jpg)

![57401db3b948b4108e347d263b7c862303b69b909d7afdb8ba760083405ad450.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/57401db3b948b4108e347d263b7c862303b69b909d7afdb8ba760083405ad450.jpg)

![5b287988fe5cc8238f3eaea22de9ac40f4089817e9ec8b9c1ccb7274e432c79b.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/5b287988fe5cc8238f3eaea22de9ac40f4089817e9ec8b9c1ccb7274e432c79b.jpg)

![5c20ffeed2b21147012288d6e1078a5a4d80bf8b8544d299e1fd356112264850.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/5c20ffeed2b21147012288d6e1078a5a4d80bf8b8544d299e1fd356112264850.jpg)

![5f04b741c152e722a2d9c1682f82bc7bee8296766b5a8dab3aea2402e521c0c4.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/5f04b741c152e722a2d9c1682f82bc7bee8296766b5a8dab3aea2402e521c0c4.jpg)

![860555b2ac985d1e98297f375036069d87484a731991068bcb3e798ae99b3b29.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/860555b2ac985d1e98297f375036069d87484a731991068bcb3e798ae99b3b29.jpg)

![9ace758b264d9412e00c607d4c7ad7738dbfe06506089aa9fcfbc9d62c1986ec.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/9ace758b264d9412e00c607d4c7ad7738dbfe06506089aa9fcfbc9d62c1986ec.jpg)

![c378e5b1f9ec73ee7c2479dc9a9477b7b9dfc7bafa3631189b10989b388ded09.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/c378e5b1f9ec73ee7c2479dc9a9477b7b9dfc7bafa3631189b10989b388ded09.jpg)

![cf8b1779ea47f096d618fa637d3360f78256ade348d0f885f3fcc7e59d93332c.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/cf8b1779ea47f096d618fa637d3360f78256ade348d0f885f3fcc7e59d93332c.jpg)

![d4d140845b2286bd97bc25c4ec874e1d0ed514d33a38b61858e195190361f1f2.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/d4d140845b2286bd97bc25c4ec874e1d0ed514d33a38b61858e195190361f1f2.jpg)

![de9caa3531f85dfd5772dbcb9ab9642c55779baa363dbb551638725a7a60431b.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/de9caa3531f85dfd5772dbcb9ab9642c55779baa363dbb551638725a7a60431b.jpg)

![e40abcc2fdd07f38bae88d5f5456a4f666828c93df4de7c0e5fd1f282891efc9.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/e40abcc2fdd07f38bae88d5f5456a4f666828c93df4de7c0e5fd1f282891efc9.jpg)

![eb1ea480f59d947cf591779162f8f5049b0b436961379dfba03fe111253d5c0a.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/eb1ea480f59d947cf591779162f8f5049b0b436961379dfba03fe111253d5c0a.jpg)

![ebf7e97e0534cc7355cb90fb7669cab6376653cb98d3301e8fbcfc3e204fb8bf.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/images/ebf7e97e0534cc7355cb90fb7669cab6376653cb98d3301e8fbcfc3e204fb8bf.jpg)

### Tables

![2110f23734c8e939248b4e51b7efd672e0b4a1f851b667a81dbc090184b2b858.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/tables/2110f23734c8e939248b4e51b7efd672e0b4a1f851b667a81dbc090184b2b858.jpg)

![2508b719e94b094ec434646ddef2ee04bd7e9657f70a6758dd1b9b8b3ac7b878.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/tables/2508b719e94b094ec434646ddef2ee04bd7e9657f70a6758dd1b9b8b3ac7b878.jpg)

![9d2cb644c91d70eca5d50369a70d83842b388a7b5dfb2b98d05b204ac5c77f45.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/tables/9d2cb644c91d70eca5d50369a70d83842b388a7b5dfb2b98d05b204ac5c77f45.jpg)

![b25edd33f359ed92e478ba2c0c7c83483939f49ad138c585b3cb4f5e025cf685.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/tables/b25edd33f359ed92e478ba2c0c7c83483939f49ad138c585b3cb4f5e025cf685.jpg)

![ce8db14da63268b0bcbf4b360f16c47e0c67d56bf9e138e0b39d0bd042c87e86.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/tables/ce8db14da63268b0bcbf4b360f16c47e0c67d56bf9e138e0b39d0bd042c87e86.jpg)

![d456c755bd8db019bc99ea69df2df8746e8bb09528d4fd56c4c718268a41f521.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/tables/d456c755bd8db019bc99ea69df2df8746e8bb09528d4fd56c4c718268a41f521.jpg)

![f223a4c72d20c113040537a629cad3375ca0176d7167622fed733536736925e6.jpg](../nips_results/4562_Pancakes_%20Consistent%20Multi-Protocol%20Image%20Segmentation%20Across%20Biomedical%20Domains/tables/f223a4c72d20c113040537a629cad3375ca0176d7167622fed733536736925e6.jpg)

## CodeMerge: Codebook-Guided Model Merging for Robust Test-Time Adaptation in Autonomous Driving


### Images

![18f89e8bc4ceb610a64462db3cb79c0749f228af9573ed5e89454f3cbc152589.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/images/18f89e8bc4ceb610a64462db3cb79c0749f228af9573ed5e89454f3cbc152589.jpg)

![1a445304d90e1d82ef0f9379354d52d49e3964a284a47d0c2f151c1a70358dcf.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/images/1a445304d90e1d82ef0f9379354d52d49e3964a284a47d0c2f151c1a70358dcf.jpg)

![420aa7a8740c97d96228ac9cea7ee1cdeeee32e959f1b989ed051edbe52dcbfc.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/images/420aa7a8740c97d96228ac9cea7ee1cdeeee32e959f1b989ed051edbe52dcbfc.jpg)

![ea5857124d0480ea3c772dc82cd0311d23dcf6e514451a147d0bac6c2d549af4.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/images/ea5857124d0480ea3c772dc82cd0311d23dcf6e514451a147d0bac6c2d549af4.jpg)

![ea7894d25533581e0af6c806aa564ee7a605ea464e843b55f25518e76b7f2588.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/images/ea7894d25533581e0af6c806aa564ee7a605ea464e843b55f25518e76b7f2588.jpg)

### Tables

![007141e325e195f916b4e01d1fe08702ad4fa376294ef8f6ba884e158362d194.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/007141e325e195f916b4e01d1fe08702ad4fa376294ef8f6ba884e158362d194.jpg)

![038f66d9bdb333446e4fc784b6486c6d33e813b37c2961241db31e9ace595bf7.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/038f66d9bdb333446e4fc784b6486c6d33e813b37c2961241db31e9ace595bf7.jpg)

![062a3947d8b1be82c33fb02552954cf807c473ea2db07b77e57f4255c3132443.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/062a3947d8b1be82c33fb02552954cf807c473ea2db07b77e57f4255c3132443.jpg)

![1008beeb79256e36ef22e3e9212b4a1149403eb352c1dce46a020bd308bc6e12.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/1008beeb79256e36ef22e3e9212b4a1149403eb352c1dce46a020bd308bc6e12.jpg)

![71d34803a1db047eff53602c5e3079405c4716675e762da00f507914400f747c.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/71d34803a1db047eff53602c5e3079405c4716675e762da00f507914400f747c.jpg)

![82ef67f6196770d482a973dd81f116f1c43e1b6290409a00f40c8b70cc6b707c.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/82ef67f6196770d482a973dd81f116f1c43e1b6290409a00f40c8b70cc6b707c.jpg)

![9ee2fc01791d60ca0d90783ab0016df990f4a277b9b05d09fc75673690a3f893.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/9ee2fc01791d60ca0d90783ab0016df990f4a277b9b05d09fc75673690a3f893.jpg)

![c0753872bb664dc1b50882dc617365e76f3178221e3086e76d8bc8fc2f66fb8e.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/c0753872bb664dc1b50882dc617365e76f3178221e3086e76d8bc8fc2f66fb8e.jpg)

![ceb4e44ecab93d9eb6f86ebb81b56d567a3ab4348a60f46e92572c7a4c36873a.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/ceb4e44ecab93d9eb6f86ebb81b56d567a3ab4348a60f46e92572c7a4c36873a.jpg)

![d284ceab7deb0cb054b661c1b69519c1982196033395b75b1db2cefd5f58b6fc.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/d284ceab7deb0cb054b661c1b69519c1982196033395b75b1db2cefd5f58b6fc.jpg)

![dfa3de534a2cda91b45001c79309bec1180227fcfeba5b1b84e2a5ce3b03cc69.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/dfa3de534a2cda91b45001c79309bec1180227fcfeba5b1b84e2a5ce3b03cc69.jpg)

![e3c9538c6d03f077780b2df9446def55cb9b1f7d91e3191d4d45b5832a4470d4.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/e3c9538c6d03f077780b2df9446def55cb9b1f7d91e3191d4d45b5832a4470d4.jpg)

![eeab51aff0529b7e642391141b20412cc2b43cfca1b87fa349e410b638d1d834.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/eeab51aff0529b7e642391141b20412cc2b43cfca1b87fa349e410b638d1d834.jpg)

![f81b4e1f73f71ad9639f2febf6aea9517d69ef83e8c2d2d2ace1be5490ba386c.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/f81b4e1f73f71ad9639f2febf6aea9517d69ef83e8c2d2d2ace1be5490ba386c.jpg)

![fe8913d33082d83d604ab2fdc20049e5db2b3282728ceb5df154fc1a16a27533.jpg](../nips_results/4563_CodeMerge_%20Codebook-Guided%20Model%20Merging%20for%20Robust%20Test-Time%20Adaptation%20in%20Autonomous%20Driving/tables/fe8913d33082d83d604ab2fdc20049e5db2b3282728ceb5df154fc1a16a27533.jpg)

## DenoiseRotator: Enhance Pruning Robustness for LLMs via Importance Concentration


### Images

![a63530227e0711c8651863f9ae30c3f8986724d51129b520a70f744d4fa8e3f0.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/images/a63530227e0711c8651863f9ae30c3f8986724d51129b520a70f744d4fa8e3f0.jpg)

![c5935a33c3bdc3e6a9cd083bae155868d524b4f71ab9d699f8618e79213f1415.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/images/c5935a33c3bdc3e6a9cd083bae155868d524b4f71ab9d699f8618e79213f1415.jpg)

![da21567c90ce62c4f7343f9897b3022303c4ee39849e1cfa81ef16a864bc2322.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/images/da21567c90ce62c4f7343f9897b3022303c4ee39849e1cfa81ef16a864bc2322.jpg)

### Tables

![0727f66b5d7695355835f3ea02961aa6e7d49cd3470abb4ac04a4f20dce9e662.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/0727f66b5d7695355835f3ea02961aa6e7d49cd3470abb4ac04a4f20dce9e662.jpg)

![20deb10e0e4b188214643024ed2a573380ead9556c1abaf1507ff25a7295fadd.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/20deb10e0e4b188214643024ed2a573380ead9556c1abaf1507ff25a7295fadd.jpg)

![22e09acd5e115d210483156d9a95c14ed4708db8fbd5b4877120e4cdf89ed867.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/22e09acd5e115d210483156d9a95c14ed4708db8fbd5b4877120e4cdf89ed867.jpg)

![262f810ffb39b0f1e2decbc4ddffc58dbd554b2d280f249f9b19582e501349ee.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/262f810ffb39b0f1e2decbc4ddffc58dbd554b2d280f249f9b19582e501349ee.jpg)

![391bd7e987349d1050a2c4623d46345313d60ddc6781a155ca76a676e1eec6fc.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/391bd7e987349d1050a2c4623d46345313d60ddc6781a155ca76a676e1eec6fc.jpg)

![3ca920b6fee239052c3d51a9b34bf34a1ab8e5b3dded673e3e997a2b5aa33be3.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/3ca920b6fee239052c3d51a9b34bf34a1ab8e5b3dded673e3e997a2b5aa33be3.jpg)

![47704e88e2138ea12bab3162b2e97b60dfc5dae1008525deb1804d69618204d2.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/47704e88e2138ea12bab3162b2e97b60dfc5dae1008525deb1804d69618204d2.jpg)

![4e4f787125c824dbf9588af5ac3f8d46626e8718419e007768dda727ead88d16.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/4e4f787125c824dbf9588af5ac3f8d46626e8718419e007768dda727ead88d16.jpg)

![5660c078f0e3bd4e69a2db0db83e98e380cb490816d3158d57b6dbd7cdd69875.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/5660c078f0e3bd4e69a2db0db83e98e380cb490816d3158d57b6dbd7cdd69875.jpg)

![5fa66fc6d964600dd65c91c5bbad635249c95d70a36761ea05905d020b159b4c.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/5fa66fc6d964600dd65c91c5bbad635249c95d70a36761ea05905d020b159b4c.jpg)

![69b68854ee9f81c9b25dc7f35d24a3b1945936d906de04f31cb6a0f9631f0ca1.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/69b68854ee9f81c9b25dc7f35d24a3b1945936d906de04f31cb6a0f9631f0ca1.jpg)

![6d1dcd36ee302ce60d7d8c3e27ae17039819ba9bab5749ed227510bca7d53420.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/6d1dcd36ee302ce60d7d8c3e27ae17039819ba9bab5749ed227510bca7d53420.jpg)

![797e70e3d360766c736c5fca770ac55eac8bb15fbc016f4eb7abe875101d4c7e.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/797e70e3d360766c736c5fca770ac55eac8bb15fbc016f4eb7abe875101d4c7e.jpg)

![7fbaa0a68c71c22f152359fc6945365df8f44e17a9661a6b589132469e0c6951.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/7fbaa0a68c71c22f152359fc6945365df8f44e17a9661a6b589132469e0c6951.jpg)

![8065beec1ee3df1dc31c4c5e68b0821431dda22be395b4db7d5ab535f09ea289.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/8065beec1ee3df1dc31c4c5e68b0821431dda22be395b4db7d5ab535f09ea289.jpg)

![80a60be078ac7cde546b7b294539d4d020037677c5376c4799492ca9c5a42ccb.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/80a60be078ac7cde546b7b294539d4d020037677c5376c4799492ca9c5a42ccb.jpg)

![aea8b3afcb225083e4679556334b2b033c72786ede1f4f46eeb1925f11e1e4b6.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/aea8b3afcb225083e4679556334b2b033c72786ede1f4f46eeb1925f11e1e4b6.jpg)

![c220c6314fd8f8121c1c20b24525239a3f20bc9089f4fac44e1b5d67201a56d5.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/c220c6314fd8f8121c1c20b24525239a3f20bc9089f4fac44e1b5d67201a56d5.jpg)

![d03761f23aee717a988f0c256b2760596629410545634f8d21731bb0f904e9b4.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/d03761f23aee717a988f0c256b2760596629410545634f8d21731bb0f904e9b4.jpg)

![d0e468be20e17d3f1d3531874b4afbc7094dd7a124b1562b2c4d91f508f20325.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/d0e468be20e17d3f1d3531874b4afbc7094dd7a124b1562b2c4d91f508f20325.jpg)

![d1ff1f336abf82c0bd56ccbdaad3eb673a9265aaf3c6938c33b3abf6f1e63f4b.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/d1ff1f336abf82c0bd56ccbdaad3eb673a9265aaf3c6938c33b3abf6f1e63f4b.jpg)

![d7d465a1412e20d4470f0f468e11bc08b28d78c547616218557e849d4e56d5ac.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/d7d465a1412e20d4470f0f468e11bc08b28d78c547616218557e849d4e56d5ac.jpg)

![e777773d2837c71bb5babe8c4501cd822e9460915917a2078e148cdf8c552f25.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/e777773d2837c71bb5babe8c4501cd822e9460915917a2078e148cdf8c552f25.jpg)

![ea9d310ef0a9132e4a6f410992092b2da7284c03a2d5fdc7f0af2da2f7bbefa4.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/ea9d310ef0a9132e4a6f410992092b2da7284c03a2d5fdc7f0af2da2f7bbefa4.jpg)

![f2c3cead9402aee30bef1af4d293837e989805cb1605844f62081990f4bb7940.jpg](../nips_results/4564_DenoiseRotator_%20Enhance%20Pruning%20Robustness%20for%20LLMs%20via%20Importance%20Concentration/tables/f2c3cead9402aee30bef1af4d293837e989805cb1605844f62081990f4bb7940.jpg)

## Exploring the Design Space of Diffusion Bridge Models


### Images

![0343b1fa660cfce6a52d039f727f43fb8e0c5b2798d540d35b76ec6b0b0044d8.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/0343b1fa660cfce6a52d039f727f43fb8e0c5b2798d540d35b76ec6b0b0044d8.jpg)

![040bac871ba25c4aeab5f670b63cca0f9f55e340dfc1902d46a353fbd49a77e7.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/040bac871ba25c4aeab5f670b63cca0f9f55e340dfc1902d46a353fbd49a77e7.jpg)

![078b8f2304c4e5f7aa31bf42d4085b03cc4ffc55b34b270ed596fd177a8cb21b.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/078b8f2304c4e5f7aa31bf42d4085b03cc4ffc55b34b270ed596fd177a8cb21b.jpg)

![09a14605573be29d86fe6004a4dfe6a3ae3f71bb414c68c00c9d4c840ba2146c.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/09a14605573be29d86fe6004a4dfe6a3ae3f71bb414c68c00c9d4c840ba2146c.jpg)

![22081b8a342669f26b4a495d3fac3770a8c7686e43b2816374dc3cd4d37622df.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/22081b8a342669f26b4a495d3fac3770a8c7686e43b2816374dc3cd4d37622df.jpg)

![2c6b344980b74baa3d7e63f566e8a7be0cc053788503d483abd1281e1f17d4a7.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/2c6b344980b74baa3d7e63f566e8a7be0cc053788503d483abd1281e1f17d4a7.jpg)

![3014c5a4d0806d1b8045518550470034844c25d4f5e29ba9bc0db17c6c6ef32a.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/3014c5a4d0806d1b8045518550470034844c25d4f5e29ba9bc0db17c6c6ef32a.jpg)

![3c794f4004758792ca6465ab44d4b626d2b7fc43a29e3a9acd05378b182267d3.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/3c794f4004758792ca6465ab44d4b626d2b7fc43a29e3a9acd05378b182267d3.jpg)

![4277de26a85113ea05166991fc2e4e4c559e80f145c7ed6d589927c7c9eea5d9.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/4277de26a85113ea05166991fc2e4e4c559e80f145c7ed6d589927c7c9eea5d9.jpg)

![46a85380accf6de27b5e6e0f31c6776f094725494f0ca6199776073c04d88ee5.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/46a85380accf6de27b5e6e0f31c6776f094725494f0ca6199776073c04d88ee5.jpg)

![50f9afd2a24ab4cb7a24cb673ff4f2f899dfaa784b1d51d3c348296f79876a69.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/50f9afd2a24ab4cb7a24cb673ff4f2f899dfaa784b1d51d3c348296f79876a69.jpg)

![53311d868f0bb197d887164c034e7f2f9562241e4bf4128ad93f7fbe0def7c30.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/53311d868f0bb197d887164c034e7f2f9562241e4bf4128ad93f7fbe0def7c30.jpg)

![53957d9ed42daf14aa73a7517f47629ee7785a67070be2d44f0279e64ac8c0a1.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/53957d9ed42daf14aa73a7517f47629ee7785a67070be2d44f0279e64ac8c0a1.jpg)

![693feec0d3517b3ba895335a4e796f346321dfff5a544be67d055b78161ce04d.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/693feec0d3517b3ba895335a4e796f346321dfff5a544be67d055b78161ce04d.jpg)

![696f8ac652023f741d6e9d63190faec49b9df2b5921dcd2c1660cb6ec9efa6b3.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/696f8ac652023f741d6e9d63190faec49b9df2b5921dcd2c1660cb6ec9efa6b3.jpg)

![6e70a208c1417776b1eac0bdae62b227adca4ead1a41daaff1abb5fd5c2b6c03.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/6e70a208c1417776b1eac0bdae62b227adca4ead1a41daaff1abb5fd5c2b6c03.jpg)

![72ff490d4a7ded59ceb05f0eec8e43cb42bd51eaad4db90749e5875cb5c692de.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/72ff490d4a7ded59ceb05f0eec8e43cb42bd51eaad4db90749e5875cb5c692de.jpg)

![7c2004eaca9ea2b20ff43bca11915599655ade11d007fbc171b13efad361307a.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/7c2004eaca9ea2b20ff43bca11915599655ade11d007fbc171b13efad361307a.jpg)

![9fa31de0482c1929a0d1a2921cc25214127196636fe1ef428c87b9f0eff62a5b.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/9fa31de0482c1929a0d1a2921cc25214127196636fe1ef428c87b9f0eff62a5b.jpg)

![a2b07e8160011388df0a4834be7a890131f2cf3b5127ecd33b720b58896bf812.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/a2b07e8160011388df0a4834be7a890131f2cf3b5127ecd33b720b58896bf812.jpg)

![a3a9992cfebd4d82ec72715e51e2eea8879c7e41881c1f9a0b00dfdbacddaef1.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/a3a9992cfebd4d82ec72715e51e2eea8879c7e41881c1f9a0b00dfdbacddaef1.jpg)

![b9acd96af3647c2bf9c7c90d15fc3f74df3bf36e9b352b4d89cfff3bf42d131f.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/b9acd96af3647c2bf9c7c90d15fc3f74df3bf36e9b352b4d89cfff3bf42d131f.jpg)

![db8c93dd3c9da1e3bd32bc7959a61d00c144e3725a51e7c60c8bc57772212991.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/db8c93dd3c9da1e3bd32bc7959a61d00c144e3725a51e7c60c8bc57772212991.jpg)

![dc25f6f021fec57594bd8a50564233192e761085bcdd08ae5b78f8b081f64c39.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/dc25f6f021fec57594bd8a50564233192e761085bcdd08ae5b78f8b081f64c39.jpg)

![ddd72c579fa2116200b217097c716b173bc3be00ee03a56ab712e436ae8bed27.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/images/ddd72c579fa2116200b217097c716b173bc3be00ee03a56ab712e436ae8bed27.jpg)

### Tables

![0d81ed5ea13fc58c2ebd1c33f003a0cf73d3b9e50e79e11a7083e89a68a9086b.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/tables/0d81ed5ea13fc58c2ebd1c33f003a0cf73d3b9e50e79e11a7083e89a68a9086b.jpg)

![25423096e394ac25f45f6707285337a04f3cc10c86750ce748546d40803fbb23.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/tables/25423096e394ac25f45f6707285337a04f3cc10c86750ce748546d40803fbb23.jpg)

![39be016637cd8d0b9908d16490d373cee61a1d3b4ccbf3a921477341a09bb01d.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/tables/39be016637cd8d0b9908d16490d373cee61a1d3b4ccbf3a921477341a09bb01d.jpg)

![4a701711f4fdb9924b423cb4b790f5b2eb14248db57435f4ea1603ac12d71313.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/tables/4a701711f4fdb9924b423cb4b790f5b2eb14248db57435f4ea1603ac12d71313.jpg)

![5c45204376d080b5f018f70d7840de1d5ff0b8310f24cf7836226e357bc5f46d.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/tables/5c45204376d080b5f018f70d7840de1d5ff0b8310f24cf7836226e357bc5f46d.jpg)

![9542c9fe0f105973b55812b0b79529399d4742243470ed571ae2bbbd80f56efb.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/tables/9542c9fe0f105973b55812b0b79529399d4742243470ed571ae2bbbd80f56efb.jpg)

![a11f84127a93a6a78ce9d114d4141791db6b0d9d52cf1d2518924dabb1df6c7c.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/tables/a11f84127a93a6a78ce9d114d4141791db6b0d9d52cf1d2518924dabb1df6c7c.jpg)

![b88faef7bb1edd7910884274f3887a576143a27539c5ed67775a7cbf8f82ee13.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/tables/b88faef7bb1edd7910884274f3887a576143a27539c5ed67775a7cbf8f82ee13.jpg)

![dafbf9568b50eaf1ecd880503093e18b6d36638dcf87fb59f0bb708bd26d0e7d.jpg](../nips_results/4565_Exploring%20the%20Design%20Space%20of%20Diffusion%20Bridge%20Models/tables/dafbf9568b50eaf1ecd880503093e18b6d36638dcf87fb59f0bb708bd26d0e7d.jpg)

## MODEL SHAPLEY: Find Your Ideal Parameter Player via One Gradient Backpropagation


### Images

![1475e67ccec7999ed43d33224f3099539d353e80c90d02c46b4e208bee15c73c.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/images/1475e67ccec7999ed43d33224f3099539d353e80c90d02c46b4e208bee15c73c.jpg)

![43bb9742ff7c47f460218bd8fdd4e423fce2c3592e229b8e1ef05a704988bec8.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/images/43bb9742ff7c47f460218bd8fdd4e423fce2c3592e229b8e1ef05a704988bec8.jpg)

![49aa0392ead2958174575db44b4277c5089147d7816605eddd9edcc98763cbbe.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/images/49aa0392ead2958174575db44b4277c5089147d7816605eddd9edcc98763cbbe.jpg)

![6c10c1ac7f4d241a88384e5eae9f214cf2fe89fd4ed643378a7b62998595f2aa.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/images/6c10c1ac7f4d241a88384e5eae9f214cf2fe89fd4ed643378a7b62998595f2aa.jpg)

![8b8dd73827eec01a0179bce343872d7244bbf6f5b6b558ec141457c91ec4e27b.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/images/8b8dd73827eec01a0179bce343872d7244bbf6f5b6b558ec141457c91ec4e27b.jpg)

![92981caa890243c05dd537e8e0601eb42684c7af6689309fd944733885b7cbcd.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/images/92981caa890243c05dd537e8e0601eb42684c7af6689309fd944733885b7cbcd.jpg)

### Tables

![0dfe9163f9a879bcf98242d0848b8a73c9dd0050b680303db8233e329c122cd2.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/tables/0dfe9163f9a879bcf98242d0848b8a73c9dd0050b680303db8233e329c122cd2.jpg)

![0f0b835b952f7785c1316cb00325d45ac86ef4da858ad03d74e4f4221656d849.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/tables/0f0b835b952f7785c1316cb00325d45ac86ef4da858ad03d74e4f4221656d849.jpg)

![15cf2bafde5b38d0ff254f30d3876f6aa7399164196a99336b6bbe743ba01a98.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/tables/15cf2bafde5b38d0ff254f30d3876f6aa7399164196a99336b6bbe743ba01a98.jpg)

![1e34054dbae90121fd0a63e29db58a4b605c4b064adad576a6c7d63b43169999.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/tables/1e34054dbae90121fd0a63e29db58a4b605c4b064adad576a6c7d63b43169999.jpg)

![1ff3f1891c60d3bfdb5944bf1d9dd066abb4b1b8815ad9d58d074ca61df12e2d.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/tables/1ff3f1891c60d3bfdb5944bf1d9dd066abb4b1b8815ad9d58d074ca61df12e2d.jpg)

![24b5d06015ff7e562bcaf4e19087e8ec8bc531699eb120d1989eaab1225bc24b.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/tables/24b5d06015ff7e562bcaf4e19087e8ec8bc531699eb120d1989eaab1225bc24b.jpg)

![8002791419774a6971132e909af9ae31c618a05050cb7700ae981e468df3584c.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/tables/8002791419774a6971132e909af9ae31c618a05050cb7700ae981e468df3584c.jpg)

![cc73275769e5f47b3c2e1d2ab4c409855790a948a0e25805e220eef5b917dac8.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/tables/cc73275769e5f47b3c2e1d2ab4c409855790a948a0e25805e220eef5b917dac8.jpg)

![dd676449e095d9f5642f41842418098d52facf6ccfd52d352a41dbc45bf5c30d.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/tables/dd676449e095d9f5642f41842418098d52facf6ccfd52d352a41dbc45bf5c30d.jpg)

![ebeabd08ac1b3755b7699b15f43a751b391d10bfcd7059fe5a72bb3294ce22da.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/tables/ebeabd08ac1b3755b7699b15f43a751b391d10bfcd7059fe5a72bb3294ce22da.jpg)

![f5ad728f798debff9fbd38bf9da5189c20c65901688aed960ecaf2bfcf3139fa.jpg](../nips_results/4566_MODEL%20SHAPLEY_%20Find%20Your%20Ideal%20Parameter%20Player%20via%20One%20Gradient%20Backpropagation/tables/f5ad728f798debff9fbd38bf9da5189c20c65901688aed960ecaf2bfcf3139fa.jpg)

## From Pretraining to Pathology: How Noise Leads to Catastrophic Inheritance in Medical Models


### Images

![51ecb84aa8a9738e9184893f8d91fd884bf5ff7ebd1e96d3c4a47990e6f19403.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/images/51ecb84aa8a9738e9184893f8d91fd884bf5ff7ebd1e96d3c4a47990e6f19403.jpg)

![6063b82d045eda5c8022bc3e4bd18ea349e0d7d254dce489f73b11b4f915c131.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/images/6063b82d045eda5c8022bc3e4bd18ea349e0d7d254dce489f73b11b4f915c131.jpg)

![770bb58cc830ea8088877f583212319f80d28308a7610b9efd42bc351cfd238c.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/images/770bb58cc830ea8088877f583212319f80d28308a7610b9efd42bc351cfd238c.jpg)

![791adf984f5767f9bf2dcc95e6bf07370c742b1548d80b86cf5c5147ca61d421.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/images/791adf984f5767f9bf2dcc95e6bf07370c742b1548d80b86cf5c5147ca61d421.jpg)

![7cf4cc05d9d5462e644439a8d93eb654a3e365b0f5094981ab5f3c1c8e1f2b35.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/images/7cf4cc05d9d5462e644439a8d93eb654a3e365b0f5094981ab5f3c1c8e1f2b35.jpg)

![a84d6a4e9ccbb7aeb5dfc6030749626bc48b9358b930bae76f087f42c8a046a1.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/images/a84d6a4e9ccbb7aeb5dfc6030749626bc48b9358b930bae76f087f42c8a046a1.jpg)

![cac5dcc90755f45d857b3d3a032c60af5852cd81b999ce592b8b9d4f0aa4e05f.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/images/cac5dcc90755f45d857b3d3a032c60af5852cd81b999ce592b8b9d4f0aa4e05f.jpg)

![d125eeb4a038a1b826d2700b1ed6fb409f569acf0eaf8351a4256dbfbc281116.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/images/d125eeb4a038a1b826d2700b1ed6fb409f569acf0eaf8351a4256dbfbc281116.jpg)

![ea039f0e6df5a35fe385cdba1fd093808c09fded0f17cae3b6ec3ef2f0f06a8f.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/images/ea039f0e6df5a35fe385cdba1fd093808c09fded0f17cae3b6ec3ef2f0f06a8f.jpg)

### Tables

![0f11506e66b8016566ce66509568911e94e8a5ce550b9b9b688dbb0cc9de2775.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/0f11506e66b8016566ce66509568911e94e8a5ce550b9b9b688dbb0cc9de2775.jpg)

![23518a96b05f19b38fd41d3fcdfaadbfebf983f0dc5b82e4e0a58c97d1175961.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/23518a96b05f19b38fd41d3fcdfaadbfebf983f0dc5b82e4e0a58c97d1175961.jpg)

![46c03aec4abc045cdb7df4d02192814d9abad043961d34fd3756e02c000d9be2.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/46c03aec4abc045cdb7df4d02192814d9abad043961d34fd3756e02c000d9be2.jpg)

![4ffd0b188f2aec23c892824045f75d9444fe2144aa65cd4928778cd54746fb06.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/4ffd0b188f2aec23c892824045f75d9444fe2144aa65cd4928778cd54746fb06.jpg)

![58c996d3ccd2a6e72997d9a926b88de9e79ada77b2efa1b2191b522073eca586.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/58c996d3ccd2a6e72997d9a926b88de9e79ada77b2efa1b2191b522073eca586.jpg)

![5f5498a417d8a0f0d6972a940ca2a1fbb9508d2f0c25ebe02d622f5bed876006.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/5f5498a417d8a0f0d6972a940ca2a1fbb9508d2f0c25ebe02d622f5bed876006.jpg)

![6a317b03164706579c40b5e4b1d0d745fb468a671c7ebf5b5059007f3f5c2945.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/6a317b03164706579c40b5e4b1d0d745fb468a671c7ebf5b5059007f3f5c2945.jpg)

![7ef9d64d38a5685227b6d9088eb1b9cebc0589634b66b219973c07ca879c79ef.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/7ef9d64d38a5685227b6d9088eb1b9cebc0589634b66b219973c07ca879c79ef.jpg)

![9ceb77dd8d0dc54856ec3aad6e042aa5992e75d3a5d0c5e33c22629146035f64.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/9ceb77dd8d0dc54856ec3aad6e042aa5992e75d3a5d0c5e33c22629146035f64.jpg)

![ca1a94406e2e4906eb387f44cebb082874e4a5720fa6a8c8368c0df8c5855d07.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/ca1a94406e2e4906eb387f44cebb082874e4a5720fa6a8c8368c0df8c5855d07.jpg)

![f173f9114d8acc30abdd724a864692cc8466523be5c5fffa369b2b5bfb253614.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/f173f9114d8acc30abdd724a864692cc8466523be5c5fffa369b2b5bfb253614.jpg)

![fdf12ee4a91ccc5a2cf8c53230167b66375aba206b5c3b6a8abfde09c12203b2.jpg](../nips_results/4567_From%20Pretraining%20to%20Pathology_%20How%20Noise%20Leads%20to%20Catastrophic%20Inheritance%20in%20Medical%20Models/tables/fdf12ee4a91ccc5a2cf8c53230167b66375aba206b5c3b6a8abfde09c12203b2.jpg)

## From Faults to Features: Pretraining to Learn Robust Representations against Sensor Failures


### Images

![0f07167f3d8ceab1c22c545de4aa9b15a045c022cd9388482e196e94a7395453.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/0f07167f3d8ceab1c22c545de4aa9b15a045c022cd9388482e196e94a7395453.jpg)

![1175695b29232aeeb1c16f8bd6db6627f604d0b3edf34c66dd33e235f4a8e5dd.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/1175695b29232aeeb1c16f8bd6db6627f604d0b3edf34c66dd33e235f4a8e5dd.jpg)

![13803e1ce450ab983fe3044cab48d653324f1256adce31ce2aaaf4f5b4917c4c.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/13803e1ce450ab983fe3044cab48d653324f1256adce31ce2aaaf4f5b4917c4c.jpg)

![1915b5534084ddaa00ea6fa7ff56f9540118de074c6e0aeba93999525d6be5cd.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/1915b5534084ddaa00ea6fa7ff56f9540118de074c6e0aeba93999525d6be5cd.jpg)

![1a11dda27130f53b53ea826a89680e73bb49be7a1699e27d27424fce33af7180.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/1a11dda27130f53b53ea826a89680e73bb49be7a1699e27d27424fce33af7180.jpg)

![1ae1ee8005406f15cfe38dc257a832945d60550f184d7dc67fea37223b0d97fc.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/1ae1ee8005406f15cfe38dc257a832945d60550f184d7dc67fea37223b0d97fc.jpg)

![25011bc32635eceb1ec9f5541b3f3da95b2912b0ca8b805aa5ab85f59fda90a8.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/25011bc32635eceb1ec9f5541b3f3da95b2912b0ca8b805aa5ab85f59fda90a8.jpg)

![2bbb2b34211fc321ca893d6184310eed4f986e61e5c24adb910e0698c00a92aa.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/2bbb2b34211fc321ca893d6184310eed4f986e61e5c24adb910e0698c00a92aa.jpg)

![2ca25814cdc486948a0d6b3ebb083a6a42a8f4c6c0fb9936dad7e5d0216720c5.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/2ca25814cdc486948a0d6b3ebb083a6a42a8f4c6c0fb9936dad7e5d0216720c5.jpg)

![2f4c0484b9d8d3c52dfc4c023fd20fe394e5450983b1996df0ee231d1dad324d.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/2f4c0484b9d8d3c52dfc4c023fd20fe394e5450983b1996df0ee231d1dad324d.jpg)

![384e837bb5e71645890e42aaa8826bd7ee49565af7b9689522351b56acb3f604.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/384e837bb5e71645890e42aaa8826bd7ee49565af7b9689522351b56acb3f604.jpg)

![518f889203877e3327fe2ed8df8d5a933fe3ccd4a50bfe37df0abb69a3d6eda9.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/518f889203877e3327fe2ed8df8d5a933fe3ccd4a50bfe37df0abb69a3d6eda9.jpg)

![5580e57e6bef2d99cc6dfd9d51cabeadb7c64afdf660e49de55e26247dc97767.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/5580e57e6bef2d99cc6dfd9d51cabeadb7c64afdf660e49de55e26247dc97767.jpg)

![5a2504e6781e635a0aeabe097be0a7cfde6c6238f3ee31cc5bad4587eb2f8d8c.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/5a2504e6781e635a0aeabe097be0a7cfde6c6238f3ee31cc5bad4587eb2f8d8c.jpg)

![624436b212b158e131c52c12279e27d5c63f5962dbc1b21f22bc2ce9374f9529.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/624436b212b158e131c52c12279e27d5c63f5962dbc1b21f22bc2ce9374f9529.jpg)

![6bc256adf5c660c47ebf3ac0ab04aba62410b9133ffb39c513b114d9d4681055.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/6bc256adf5c660c47ebf3ac0ab04aba62410b9133ffb39c513b114d9d4681055.jpg)

![74dcb3e6fba19244410f625c46a38b3ceeaa9aebbb47e3ce05436d6238c2438f.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/74dcb3e6fba19244410f625c46a38b3ceeaa9aebbb47e3ce05436d6238c2438f.jpg)

![75cdbf30efca40db31bf76f81e3ab1f52712b898301a504f70386a054ec2f3c4.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/75cdbf30efca40db31bf76f81e3ab1f52712b898301a504f70386a054ec2f3c4.jpg)

![81fb208fe4907f5d502d491ce5cde8964b918c737ed8ea1516a0cb6c96748a60.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/81fb208fe4907f5d502d491ce5cde8964b918c737ed8ea1516a0cb6c96748a60.jpg)

![8457dc3267f1a9ba3557814445f97082772568839368ec12b0b203a22df05bfc.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/8457dc3267f1a9ba3557814445f97082772568839368ec12b0b203a22df05bfc.jpg)

![98a35ae9f3be1962c9e16959e886421b66cb0d13486d4233b17c88abf1030a96.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/98a35ae9f3be1962c9e16959e886421b66cb0d13486d4233b17c88abf1030a96.jpg)

![a0b993f0905b9842661ba7f355f47039698d829531266ba5b4182cddb0074e8a.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/a0b993f0905b9842661ba7f355f47039698d829531266ba5b4182cddb0074e8a.jpg)

![a1e161741640785e82be313fde452d91652eb3b8adc4628923a6a099d0d7b450.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/a1e161741640785e82be313fde452d91652eb3b8adc4628923a6a099d0d7b450.jpg)

![b03fc4ff0d1444e66d77b913c9f839db4fc6ce0639723d0c7b010189f4eb8aed.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/b03fc4ff0d1444e66d77b913c9f839db4fc6ce0639723d0c7b010189f4eb8aed.jpg)

![b3ee5bc873f285399d367d63088cd6ef1a33b8e33b33381bebd2b53745ef1991.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/b3ee5bc873f285399d367d63088cd6ef1a33b8e33b33381bebd2b53745ef1991.jpg)

![c03b421f34b66b2c5e1ead33d974d11470d5d98770ab7d43ad4b0f1a3f5c2386.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/c03b421f34b66b2c5e1ead33d974d11470d5d98770ab7d43ad4b0f1a3f5c2386.jpg)

![c98511d6799e67980ce8bf5a8b4df6fdc789d6345b30306e47a2a80ef9befc65.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/c98511d6799e67980ce8bf5a8b4df6fdc789d6345b30306e47a2a80ef9befc65.jpg)

![e3c8a56799e74c1ec29c03deed56066e848ac29704b4292f528ea35792fd9652.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/e3c8a56799e74c1ec29c03deed56066e848ac29704b4292f528ea35792fd9652.jpg)

![eebf97b0b4476bf8764e9c2a9f78d250fb918bad3dd33798dbc6062a5fd1d036.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/images/eebf97b0b4476bf8764e9c2a9f78d250fb918bad3dd33798dbc6062a5fd1d036.jpg)

### Tables

![18bd797f3b3ac1ed1a557bd2d78017841b026666d0c6ba9333c4ef27204df2d3.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/tables/18bd797f3b3ac1ed1a557bd2d78017841b026666d0c6ba9333c4ef27204df2d3.jpg)

![74ce24ea6c642396ce0f6a0736998343e4be62ee777334b533c196bf12024730.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/tables/74ce24ea6c642396ce0f6a0736998343e4be62ee777334b533c196bf12024730.jpg)

![89d1cea9f45f3cb8fa59f7db7faec291aace8bf84002127e279cc4a629cff020.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/tables/89d1cea9f45f3cb8fa59f7db7faec291aace8bf84002127e279cc4a629cff020.jpg)

![a530906645dfc2b9b67e1c4e28442b0daececdecaa27ba3217f628b7f9ed471f.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/tables/a530906645dfc2b9b67e1c4e28442b0daececdecaa27ba3217f628b7f9ed471f.jpg)

![ab0a2376ab836a910fd173b4c0a8c151eea42c1a974d693a099815dbfee37cbd.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/tables/ab0a2376ab836a910fd173b4c0a8c151eea42c1a974d693a099815dbfee37cbd.jpg)

![ae9d108fadb8f05eadfe9980ab80e2161d1bf17b1bb31ef53d1d650fe4337bb3.jpg](../nips_results/4568_From%20Faults%20to%20Features_%20Pretraining%20to%20Learn%20Robust%20Representations%20against%20Sensor%20Failures/tables/ae9d108fadb8f05eadfe9980ab80e2161d1bf17b1bb31ef53d1d650fe4337bb3.jpg)

## EgoThinker: Unveiling Egocentric Reasoning with Spatio-Temporal CoT


### Images

![1fe8723c0495fda0de5ea6795a5f02463ab82e9bf4e84432de292f669f26c5e9.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/images/1fe8723c0495fda0de5ea6795a5f02463ab82e9bf4e84432de292f669f26c5e9.jpg)

![2abd2371816f97a7400b7de6fa1d85f8397e0c807b89c325ade6967a2f80e0c4.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/images/2abd2371816f97a7400b7de6fa1d85f8397e0c807b89c325ade6967a2f80e0c4.jpg)

![358562f82893a3a4be3f532399b090582b7c0314dc76e5f22b2ba92468f8cd97.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/images/358562f82893a3a4be3f532399b090582b7c0314dc76e5f22b2ba92468f8cd97.jpg)

![3e1d25fdb34b1d26cb98bbeec568b63c0ac92a4046ff05b820c8ad67c21a7699.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/images/3e1d25fdb34b1d26cb98bbeec568b63c0ac92a4046ff05b820c8ad67c21a7699.jpg)

![4aad42d9f9dce2cc73157e36f3dcbeae70de65238f7e5720bdeee21c9654cdea.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/images/4aad42d9f9dce2cc73157e36f3dcbeae70de65238f7e5720bdeee21c9654cdea.jpg)

![7179f6a58a2e4b6016bf247c0dd4ef91ea6a46fb0c53f4368746f00c4fb92c1e.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/images/7179f6a58a2e4b6016bf247c0dd4ef91ea6a46fb0c53f4368746f00c4fb92c1e.jpg)

![7a4697efd5ae40d7be0ebe9a1e39bcee81248ed8ecd2dce65c6df8a1fa0779ff.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/images/7a4697efd5ae40d7be0ebe9a1e39bcee81248ed8ecd2dce65c6df8a1fa0779ff.jpg)

![c4f4b973a0c6784c66f135f077d131ac97c1cbebc531aaec251729cc865c152f.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/images/c4f4b973a0c6784c66f135f077d131ac97c1cbebc531aaec251729cc865c152f.jpg)

![f109326d2a954e7999fadc210851ae38615be540345f98e8646a2bf102e1dcbb.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/images/f109326d2a954e7999fadc210851ae38615be540345f98e8646a2bf102e1dcbb.jpg)

### Tables

![1913e08449a29e7e382ce8f159018febbc4ade99aab19069f2c99770641dd331.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/tables/1913e08449a29e7e382ce8f159018febbc4ade99aab19069f2c99770641dd331.jpg)

![34ff6ff6a8fb44df037c2d822a83f80b07534a39ab638f2ef91cecd9eb526458.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/tables/34ff6ff6a8fb44df037c2d822a83f80b07534a39ab638f2ef91cecd9eb526458.jpg)

![46bfda27a399934b999b13a1d2a7c7816f25a495e39c05a29af4afe01ce70fe3.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/tables/46bfda27a399934b999b13a1d2a7c7816f25a495e39c05a29af4afe01ce70fe3.jpg)

![82828afa766ebd7e60a77ba17e83a4fee6885e39dfcdb2c75a516f2121a32d46.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/tables/82828afa766ebd7e60a77ba17e83a4fee6885e39dfcdb2c75a516f2121a32d46.jpg)

![86b0be77b0330c6c477745f0d512a373722dd9474c418660b0f95b93b78cb036.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/tables/86b0be77b0330c6c477745f0d512a373722dd9474c418660b0f95b93b78cb036.jpg)

![8fcb38d2811088f6d85c7a7937652703606f8a38c7310734268ab0fd3477127d.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/tables/8fcb38d2811088f6d85c7a7937652703606f8a38c7310734268ab0fd3477127d.jpg)

![9acab629395ad308c1d1a07e5ede4030901bd703bbef8690680dbbb02ba278aa.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/tables/9acab629395ad308c1d1a07e5ede4030901bd703bbef8690680dbbb02ba278aa.jpg)

![b349c3d9e94c708971c6abc82e8a81c09bde05dc247a926edc5c0b2bf2bd21d3.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/tables/b349c3d9e94c708971c6abc82e8a81c09bde05dc247a926edc5c0b2bf2bd21d3.jpg)

![d7dc4202e11f20d4b772c556c45f150dcdd5e49a9001013faf1358ac66f910d8.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/tables/d7dc4202e11f20d4b772c556c45f150dcdd5e49a9001013faf1358ac66f910d8.jpg)

![dd083daf4d5e19e8fe0e71fea71fc5521b6dc0decf49bb02a00519dcd413b493.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/tables/dd083daf4d5e19e8fe0e71fea71fc5521b6dc0decf49bb02a00519dcd413b493.jpg)

![efaf0f8186a0246e7b1b8a22370f21ce4ed85f998bbafc792f651d27609fba49.jpg](../nips_results/4569_EgoThinker_%20Unveiling%20Egocentric%20Reasoning%20with%20Spatio-Temporal%20CoT/tables/efaf0f8186a0246e7b1b8a22370f21ce4ed85f998bbafc792f651d27609fba49.jpg)

## Lifelong Safety Alignment for Language Models


### Images

![4c7dc02e1dce71c18f2a97d53ac0765034648d1ae0de197f04d62fe07648cf92.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/images/4c7dc02e1dce71c18f2a97d53ac0765034648d1ae0de197f04d62fe07648cf92.jpg)

![c85abae77edd10813a26eef7485586f411ca71b90bbece65b5e022e580aeb363.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/images/c85abae77edd10813a26eef7485586f411ca71b90bbece65b5e022e580aeb363.jpg)

### Tables

![0a9b7f4cc9aadcef09b301c20d786607ba94e1d784adc7c548872f58cf163c2b.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/0a9b7f4cc9aadcef09b301c20d786607ba94e1d784adc7c548872f58cf163c2b.jpg)

![178fcf407ca2b610065a7dfb0bd64c96fdae789183bac25721b6692f6f640d62.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/178fcf407ca2b610065a7dfb0bd64c96fdae789183bac25721b6692f6f640d62.jpg)

![26d2fc7fb188997660f85b9c227e4469abfaafa4605c0878152e51426fe7ec1d.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/26d2fc7fb188997660f85b9c227e4469abfaafa4605c0878152e51426fe7ec1d.jpg)

![3171ceb8849beb172f088128733c7d9db91b2dcd4b0dd8dffa2e47c574215c03.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/3171ceb8849beb172f088128733c7d9db91b2dcd4b0dd8dffa2e47c574215c03.jpg)

![37ee1bade0a90c143414c716cec250257707cf67ef4b77a36812dd442cd412fb.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/37ee1bade0a90c143414c716cec250257707cf67ef4b77a36812dd442cd412fb.jpg)

![7f9b503225763dea38ab687811f2678f60fd465838dad66b05c515cd924644c1.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/7f9b503225763dea38ab687811f2678f60fd465838dad66b05c515cd924644c1.jpg)

![8c4d2c7e00fda2c601b5e4942777a2b3283cf70af818fa4de2dbee022be50783.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/8c4d2c7e00fda2c601b5e4942777a2b3283cf70af818fa4de2dbee022be50783.jpg)

![9b427922ca71b749469dd5199b75010b49fec7b04ca93b5001ecfb2b22aaa05e.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/9b427922ca71b749469dd5199b75010b49fec7b04ca93b5001ecfb2b22aaa05e.jpg)

![a7b1bb603bb946a03f0209aabbdd9efb7fa5ddb23c00c6aa3a9c4a09b869cfd1.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/a7b1bb603bb946a03f0209aabbdd9efb7fa5ddb23c00c6aa3a9c4a09b869cfd1.jpg)

![c70ddf5b6cbf62088cf8924b52d394f4ee4006ebc1f0190eb4b963ad931f80fc.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/c70ddf5b6cbf62088cf8924b52d394f4ee4006ebc1f0190eb4b963ad931f80fc.jpg)

![d4fd2d886d50d8f3fc2bbb6e17521d044ec59deb42beda7bc98f448689bc8ed4.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/d4fd2d886d50d8f3fc2bbb6e17521d044ec59deb42beda7bc98f448689bc8ed4.jpg)

![dab4b7a5955d9b363da42a805030002f190cc429d34678902836c723d631d9c5.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/dab4b7a5955d9b363da42a805030002f190cc429d34678902836c723d631d9c5.jpg)

![eeb62fb38551922ec1a11097af50fb0b16b6900c8067d0396109f6c5b5ea0850.jpg](../nips_results/4570_Lifelong%20Safety%20Alignment%20for%20Language%20Models/tables/eeb62fb38551922ec1a11097af50fb0b16b6900c8067d0396109f6c5b5ea0850.jpg)

## Fuse2Match: Training-Free Fusion of Flow, Diffusion, and Contrastive Models for Zero-Shot Semantic Matching


### Images

![18ab7ed262fcbafe1ee2770fdf5450fd5bfada76ae47e8af8223d554588decf7.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/18ab7ed262fcbafe1ee2770fdf5450fd5bfada76ae47e8af8223d554588decf7.jpg)

![3672a2f19484e6d443678714c7b3ec2ee011c69234ec60fa4c1c6e4aaaf5d6b9.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/3672a2f19484e6d443678714c7b3ec2ee011c69234ec60fa4c1c6e4aaaf5d6b9.jpg)

![61f85a67e3a6f056ff4654f1660ddf6f5366835c140c118b1b9260befd17534f.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/61f85a67e3a6f056ff4654f1660ddf6f5366835c140c118b1b9260befd17534f.jpg)

![73e2d92013576f4bda300f6b9d9795414f8cc78affbe7143fc53806ee837347a.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/73e2d92013576f4bda300f6b9d9795414f8cc78affbe7143fc53806ee837347a.jpg)

![a4df688008208a7d8cda97536fa17dfa8b20578e2dc0318d57535dab1561f19e.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/a4df688008208a7d8cda97536fa17dfa8b20578e2dc0318d57535dab1561f19e.jpg)

![b0a94cea7d2f28abf4a3976f6ba7ae5fd0cce3949c7eaa3e0d201cf991e73e37.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/b0a94cea7d2f28abf4a3976f6ba7ae5fd0cce3949c7eaa3e0d201cf991e73e37.jpg)

![c4c10ca42707acf921ff7cc39f8f96658ec643c7dea9d3525303c9ab20d1f677.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/c4c10ca42707acf921ff7cc39f8f96658ec643c7dea9d3525303c9ab20d1f677.jpg)

![c65e13c8e709bf1c6350b6a17881f7a68fc411b8a64d8cc4fc02de8ec68e0b70.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/c65e13c8e709bf1c6350b6a17881f7a68fc411b8a64d8cc4fc02de8ec68e0b70.jpg)

![d0234766d29488a05738a5ba4d7bc6a6e9bb953e93d5ca224c6cc69299e1b3c5.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/d0234766d29488a05738a5ba4d7bc6a6e9bb953e93d5ca224c6cc69299e1b3c5.jpg)

![d3b135ad7d69807b9fcb2f096586e7a2c49e6fe72311aee11ce5da041dcc8fae.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/d3b135ad7d69807b9fcb2f096586e7a2c49e6fe72311aee11ce5da041dcc8fae.jpg)

![d8dc2f054bfc292269d4b54e7f3edd5566001a93be6c3a3a6f0b8f61f0f6823a.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/d8dc2f054bfc292269d4b54e7f3edd5566001a93be6c3a3a6f0b8f61f0f6823a.jpg)

![f595f48b1ce0a0fb1792b0513bbfe034c34c4995a42a555ce365501478141f9e.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/images/f595f48b1ce0a0fb1792b0513bbfe034c34c4995a42a555ce365501478141f9e.jpg)

### Tables

![19b04376b74971e1dd4b3e7a020bbddb7078718cc0f7a29edc960750cd0f29a3.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/tables/19b04376b74971e1dd4b3e7a020bbddb7078718cc0f7a29edc960750cd0f29a3.jpg)

![4bc02c7c99595bd02d3333d9b6d885a103ad797f8788996ae69f83c6cd5eb95f.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/tables/4bc02c7c99595bd02d3333d9b6d885a103ad797f8788996ae69f83c6cd5eb95f.jpg)

![5f092f54c54fce677859f5181e3751a46bdfaff9fea46057ee38f175b06cb949.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/tables/5f092f54c54fce677859f5181e3751a46bdfaff9fea46057ee38f175b06cb949.jpg)

![b40a24bc4d79997c6e0ad7ad209537e00be39a4f53a94ee9d0c39febc3bca0ec.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/tables/b40a24bc4d79997c6e0ad7ad209537e00be39a4f53a94ee9d0c39febc3bca0ec.jpg)

![eb90ab35cd855e90110c98379f55e2f6d6e47bca7029a5b7a77cfc2618f2bbf4.jpg](../nips_results/4571_Fuse2Match_%20Training-Free%20Fusion%20of%20Flow%2C%20Diffusion%2C%20and%20Contrastive%20Models%20for%20Zero-Shot%20Semantic%20M/tables/eb90ab35cd855e90110c98379f55e2f6d6e47bca7029a5b7a77cfc2618f2bbf4.jpg)

## AltLoRA: Towards Better Gradient Approximation in Low-Rank Adaptation with Alternating Projections


### Images

![40711f6cd57bd0c51c3e3816f7064074694d881898d1046267f006095ed79616.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/images/40711f6cd57bd0c51c3e3816f7064074694d881898d1046267f006095ed79616.jpg)

![a86416d534bc47c68e5140f8f26b43b92ddc9d695c8d1d435f81bab01cccb05f.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/images/a86416d534bc47c68e5140f8f26b43b92ddc9d695c8d1d435f81bab01cccb05f.jpg)

![c96d55f5698d1549f0ce7b933ebcceab2d4afb9818c9f03e5630292401b14954.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/images/c96d55f5698d1549f0ce7b933ebcceab2d4afb9818c9f03e5630292401b14954.jpg)

![d9b7d46301298892b35dbf1ad8dbacf82a7ed6434353c582f707d8ee1805ee06.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/images/d9b7d46301298892b35dbf1ad8dbacf82a7ed6434353c582f707d8ee1805ee06.jpg)

### Tables

![00c2ece1d36879bd48771a7e1dfbe5690daaee93f7e1416a94974b6e3c64ed78.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/00c2ece1d36879bd48771a7e1dfbe5690daaee93f7e1416a94974b6e3c64ed78.jpg)

![357345cddc757338025eb5f65b87c904437bf9c3a6f96ecf5125bd8f34b94ae2.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/357345cddc757338025eb5f65b87c904437bf9c3a6f96ecf5125bd8f34b94ae2.jpg)

![3ac35b680513e7d8a4cc7d187003373fa3fb66a08dc69ce7619bd22eca5e07c9.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/3ac35b680513e7d8a4cc7d187003373fa3fb66a08dc69ce7619bd22eca5e07c9.jpg)

![477873c3ccfbb6caa572e8260667374daabda4ac2ea8a1baee2d5dd33e6c6331.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/477873c3ccfbb6caa572e8260667374daabda4ac2ea8a1baee2d5dd33e6c6331.jpg)

![5a4c4686ff56a2f46518fbdc1f5b65f52c271a721ad6ce432b6260eb804115f8.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/5a4c4686ff56a2f46518fbdc1f5b65f52c271a721ad6ce432b6260eb804115f8.jpg)

![6663f669fc4146be23a981404e8d17994c55e571f98ad2848289d185b1786d99.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/6663f669fc4146be23a981404e8d17994c55e571f98ad2848289d185b1786d99.jpg)

![710ce25f496d3d3029d7d62bba6d9c327f5ffbbc7513843fb68383419d5b409c.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/710ce25f496d3d3029d7d62bba6d9c327f5ffbbc7513843fb68383419d5b409c.jpg)

![78285e9ee9a1cf4b9493cee098dc1e2f95f17b6b68a8481ca2cf0ab5d642a2b8.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/78285e9ee9a1cf4b9493cee098dc1e2f95f17b6b68a8481ca2cf0ab5d642a2b8.jpg)

![8be91a89113f22f6b0b6bbf4bbe90304a79d0e3e4dd31dcf614254aae6a83064.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/8be91a89113f22f6b0b6bbf4bbe90304a79d0e3e4dd31dcf614254aae6a83064.jpg)

![acd946a7cb0fe282e19ba1a28c8ed56d0569317607274c66c5d3dca77a11dcc0.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/acd946a7cb0fe282e19ba1a28c8ed56d0569317607274c66c5d3dca77a11dcc0.jpg)

![e2a6c0d75303b6bd24ed49aee142571bd442e6f903c0148ac21df80e787d9e14.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/e2a6c0d75303b6bd24ed49aee142571bd442e6f903c0148ac21df80e787d9e14.jpg)

![f10b75f88f8a94c28a001d44281fb4c17ee4ab80faef213c80e162ff63ab47b9.jpg](../nips_results/4572_AltLoRA_%20Towards%20Better%20Gradient%20Approximation%20in%20Low-Rank%20Adaptation%20with%20Alternating%20Projections/tables/f10b75f88f8a94c28a001d44281fb4c17ee4ab80faef213c80e162ff63ab47b9.jpg)

## RAD: Training an End-to-End Driving Policy via Large-Scale 3DGS-based Reinforcement Learning


### Images

![1e0261efec2b9fc2943486cbd988251df3c9b19ec70b45674009e32d5fbb30d5.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/images/1e0261efec2b9fc2943486cbd988251df3c9b19ec70b45674009e32d5fbb30d5.jpg)

![aeae561676f11cde2b75ca01a69e763f26ab14e00ebf34a5199a80f6f67f8b29.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/images/aeae561676f11cde2b75ca01a69e763f26ab14e00ebf34a5199a80f6f67f8b29.jpg)

![af9688f342d1a1146517e764e4f2ff5c9c7101fcf2c46b69ca7462f5c7af2362.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/images/af9688f342d1a1146517e764e4f2ff5c9c7101fcf2c46b69ca7462f5c7af2362.jpg)

![c648fe6177b0b064cb873e7c2b69c684bc46a0dac0b249d7ac3261d101712c85.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/images/c648fe6177b0b064cb873e7c2b69c684bc46a0dac0b249d7ac3261d101712c85.jpg)

![e530078680542548adaa881b25efd75e5f9916f90a9b1a3c669e2b1eb8662744.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/images/e530078680542548adaa881b25efd75e5f9916f90a9b1a3c669e2b1eb8662744.jpg)

![f1decbb9893fb44971c7d59be68e6dc005c70d84db446831930820d2e8b75a91.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/images/f1decbb9893fb44971c7d59be68e6dc005c70d84db446831930820d2e8b75a91.jpg)

![fe8c526a9d49571e3b73e7bc602747c75b8c47ae7e241fd20300ca94c628c9c8.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/images/fe8c526a9d49571e3b73e7bc602747c75b8c47ae7e241fd20300ca94c628c9c8.jpg)

### Tables

![22905bf97fd83d5dfe8e1688c05d95d2bd8e3343ee411136379d263e39096109.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/tables/22905bf97fd83d5dfe8e1688c05d95d2bd8e3343ee411136379d263e39096109.jpg)

![5a1820958ae4197d41901afdba1b5ee8b0ef583a8c84ea951e277721db993aad.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/tables/5a1820958ae4197d41901afdba1b5ee8b0ef583a8c84ea951e277721db993aad.jpg)

![943855a62d0291976dfe7665a8fc9aa2fff0b75a31451d30cf2bf4ad096fe6bc.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/tables/943855a62d0291976dfe7665a8fc9aa2fff0b75a31451d30cf2bf4ad096fe6bc.jpg)

![a3e7a93aacb93fb2c1bd9efe0b4100a93d43e54118849f96cf17d50fb3f0cd1c.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/tables/a3e7a93aacb93fb2c1bd9efe0b4100a93d43e54118849f96cf17d50fb3f0cd1c.jpg)

![c1ae3ab9396ec8ab7fedbaafd7b9b0cb791f9f790a941b0e8de5402fc806134f.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/tables/c1ae3ab9396ec8ab7fedbaafd7b9b0cb791f9f790a941b0e8de5402fc806134f.jpg)

![f03dc9457040a1b29a1415045f776962c930f377b5113d8c8c9d0de0c2819898.jpg](../nips_results/4573_RAD_%20Training%20an%20End-to-End%20Driving%20Policy%20via%20Large-Scale%203DGS-based%20Reinforcement%20Learning/tables/f03dc9457040a1b29a1415045f776962c930f377b5113d8c8c9d0de0c2819898.jpg)

## When Models Know More Than They Can Explain: Quantifying Knowledge Transfer in Human-AI Collaboration


### Images

![10f2f95b84f3fe1b56ce0f4c78081111f0188c3ac0922dcb78f848cd0845ab26.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/images/10f2f95b84f3fe1b56ce0f4c78081111f0188c3ac0922dcb78f848cd0845ab26.jpg)

![1a051b48374d9acecdbdb9833d5ac721e507e6317052a6cbe81f7ecaa69b1477.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/images/1a051b48374d9acecdbdb9833d5ac721e507e6317052a6cbe81f7ecaa69b1477.jpg)

![2b777ba5db8c3a2e636a5000fb1d94f96aeb4d7849307310f93295a6d83b90df.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/images/2b777ba5db8c3a2e636a5000fb1d94f96aeb4d7849307310f93295a6d83b90df.jpg)

![2dda2382c3ebd10fa4db48bcb185e487bca72b9cabc20acec3e9ce0fc9fbc4b0.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/images/2dda2382c3ebd10fa4db48bcb185e487bca72b9cabc20acec3e9ce0fc9fbc4b0.jpg)

![3ff0bed766c563f7d95eb5329f7836a64c2c1972863241fec9f3ecb5f57caf62.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/images/3ff0bed766c563f7d95eb5329f7836a64c2c1972863241fec9f3ecb5f57caf62.jpg)

![42d77b659a33e0bfdd9976cf6c1d737847425797266c8a5de371a0cdaf066b47.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/images/42d77b659a33e0bfdd9976cf6c1d737847425797266c8a5de371a0cdaf066b47.jpg)

![69f038e258e4bd547f7d927eae4bddcde7a84044b6fe221126b66325f0efb2a6.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/images/69f038e258e4bd547f7d927eae4bddcde7a84044b6fe221126b66325f0efb2a6.jpg)

![7bf015e5c03863b690c961b955079113c5dfa6d3d25e0a603e5970242808afc4.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/images/7bf015e5c03863b690c961b955079113c5dfa6d3d25e0a603e5970242808afc4.jpg)

![7d6aca14d7f1223e49ce7424022a9ea259e929c09e015eaa9765017c7d7098ab.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/images/7d6aca14d7f1223e49ce7424022a9ea259e929c09e015eaa9765017c7d7098ab.jpg)

![7f04f40257beef802ad88940b14ba049c27c89280dd9189f05f2ef72a86a4ca4.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/images/7f04f40257beef802ad88940b14ba049c27c89280dd9189f05f2ef72a86a4ca4.jpg)

### Tables

![2a19dea41093a1e195a85cadcebe69b887b293b94b4cd6bdb129031659283b38.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/tables/2a19dea41093a1e195a85cadcebe69b887b293b94b4cd6bdb129031659283b38.jpg)

![477ca2af1018d9f9f738fc4b76681c490d2d7c161ee63653d3a4729b86c98777.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/tables/477ca2af1018d9f9f738fc4b76681c490d2d7c161ee63653d3a4729b86c98777.jpg)

![58479a0e3b1643f3081caa1994f3ca6cfb004d68d299e447f78a932ddafee99f.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/tables/58479a0e3b1643f3081caa1994f3ca6cfb004d68d299e447f78a932ddafee99f.jpg)

![77ea07a5a5875401af690a151adbcaac0caf504be5451b8c502f481bb762dc46.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/tables/77ea07a5a5875401af690a151adbcaac0caf504be5451b8c502f481bb762dc46.jpg)

![879d2dfc72c9f8ea84dfa3c5cd1f46be6e924bdac45941557f539442a334086a.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/tables/879d2dfc72c9f8ea84dfa3c5cd1f46be6e924bdac45941557f539442a334086a.jpg)

![a0d5c0d3256d62fa255135bb84f6451b9cf37b0a79ec112e82c4ddbc8237a293.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/tables/a0d5c0d3256d62fa255135bb84f6451b9cf37b0a79ec112e82c4ddbc8237a293.jpg)

![a66341f81fcd2447b3e9cf884001fd517e8dafec27bfdbb25e805bafa19cd24c.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/tables/a66341f81fcd2447b3e9cf884001fd517e8dafec27bfdbb25e805bafa19cd24c.jpg)

![ae8982b28d15a0a2071a74ebe564a64bdc022f958eadfd3497e9299ef8907dd8.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/tables/ae8982b28d15a0a2071a74ebe564a64bdc022f958eadfd3497e9299ef8907dd8.jpg)

![b14be200604091323b0d7884b822baadd76f377a7a28825755a8b0dbd54f06c6.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/tables/b14be200604091323b0d7884b822baadd76f377a7a28825755a8b0dbd54f06c6.jpg)

![c1ff306b725bf0b67495f14ad94c273fb63c26620f159ac8c960aed0f4e23614.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/tables/c1ff306b725bf0b67495f14ad94c273fb63c26620f159ac8c960aed0f4e23614.jpg)

![f3aa885fd7072930eb7f2f243167fddcc224ef5ea9462e476b825457402ded52.jpg](../nips_results/4574_When%20Models%20Know%20More%20Than%20They%20Can%20Explain_%20Quantifying%20Knowledge%20Transfer%20in%20Human-AI%20Collaboratio/tables/f3aa885fd7072930eb7f2f243167fddcc224ef5ea9462e476b825457402ded52.jpg)

## SRA-CL: Semantic Retrieval Augmented Contrastive Learning for Sequential Recommendation


### Images

![401c9bc693220d73c5af1c3c7a3cf9433285c5ea2cea666eeda938e595782637.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/images/401c9bc693220d73c5af1c3c7a3cf9433285c5ea2cea666eeda938e595782637.jpg)

![7eb73afa4a8da587e717acac7b6d838c234dbd696b473b928ef4d0966545d5f7.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/images/7eb73afa4a8da587e717acac7b6d838c234dbd696b473b928ef4d0966545d5f7.jpg)

![97ac206ee8762d71f091ffa3254758853447323aeefaa1ff769c42a36b0f85e8.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/images/97ac206ee8762d71f091ffa3254758853447323aeefaa1ff769c42a36b0f85e8.jpg)

![e6fc086e7eac6b3577afbabde98427cb31f733b60f81d115bc2d41150ecb7e56.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/images/e6fc086e7eac6b3577afbabde98427cb31f733b60f81d115bc2d41150ecb7e56.jpg)

![f794b50cb8d62d3940cc60d1c618bcb324d1017d44b9ed131ddaca4466d069fa.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/images/f794b50cb8d62d3940cc60d1c618bcb324d1017d44b9ed131ddaca4466d069fa.jpg)

![faf47b2a5309c7158278b03e7e6ee13695bfbff11dded0f0ea050ee2fc306f5b.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/images/faf47b2a5309c7158278b03e7e6ee13695bfbff11dded0f0ea050ee2fc306f5b.jpg)

![fc6f7a2b1ddcb0eb270bf49e20c2be47ac35c0576f2f55e38f77ed5ada03e042.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/images/fc6f7a2b1ddcb0eb270bf49e20c2be47ac35c0576f2f55e38f77ed5ada03e042.jpg)

### Tables

![646b01bf18caaf02b711da02404dc79d77d6b3acc76b5bdf557c734a9c5dc57c.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/tables/646b01bf18caaf02b711da02404dc79d77d6b3acc76b5bdf557c734a9c5dc57c.jpg)

![6a8ab601d22f8e4cba425bade94f98c2d9ca1efeff6c97632898dd6f7255ff0f.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/tables/6a8ab601d22f8e4cba425bade94f98c2d9ca1efeff6c97632898dd6f7255ff0f.jpg)

![6daedbaf4960537e1c02e1a738279424a672503f45022a82eac248ef70fbbbbf.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/tables/6daedbaf4960537e1c02e1a738279424a672503f45022a82eac248ef70fbbbbf.jpg)

![81984cc0e0208f281be05e3fa0328860af74d7f99865e58ce0ae56974923e746.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/tables/81984cc0e0208f281be05e3fa0328860af74d7f99865e58ce0ae56974923e746.jpg)

![b381707d46195aed0eb834f17d5c70cc094c4e80aa5c4a810adf4bb9782870ad.jpg](../nips_results/4575_SRA-CL_%20Semantic%20Retrieval%20Augmented%20Contrastive%20Learning%20for%20Sequential%20Recommendation/tables/b381707d46195aed0eb834f17d5c70cc094c4e80aa5c4a810adf4bb9782870ad.jpg)

## Eulerian Neural Network Informed by Chemical Transport for Air Quality Forecasting


### Images

![1da32e8875bd5e5d465a469cebfa79ad275fa0c6f180b84d25d2c96c45800086.jpg](../nips_results/4576_Eulerian%20Neural%20Network%20Informed%20by%20Chemical%20Transport%20for%20Air%20Quality%20Forecasting/images/1da32e8875bd5e5d465a469cebfa79ad275fa0c6f180b84d25d2c96c45800086.jpg)

![253f88605616f33f06599e7da5a534101abfdb986169f9cc97097dd5040d9342.jpg](../nips_results/4576_Eulerian%20Neural%20Network%20Informed%20by%20Chemical%20Transport%20for%20Air%20Quality%20Forecasting/images/253f88605616f33f06599e7da5a534101abfdb986169f9cc97097dd5040d9342.jpg)

![6d2b17b149eec4034e2a88bb9b772c60159253bcdfb0c4cffd1239373260d1b1.jpg](../nips_results/4576_Eulerian%20Neural%20Network%20Informed%20by%20Chemical%20Transport%20for%20Air%20Quality%20Forecasting/images/6d2b17b149eec4034e2a88bb9b772c60159253bcdfb0c4cffd1239373260d1b1.jpg)

![863cfe818bab98ea6424aabf05b285fc74923dc02001cc85cec848832d811055.jpg](../nips_results/4576_Eulerian%20Neural%20Network%20Informed%20by%20Chemical%20Transport%20for%20Air%20Quality%20Forecasting/images/863cfe818bab98ea6424aabf05b285fc74923dc02001cc85cec848832d811055.jpg)

![a06a739b02c2813c689c234cc346e393cfc0747b6380c894e73e6583817775e3.jpg](../nips_results/4576_Eulerian%20Neural%20Network%20Informed%20by%20Chemical%20Transport%20for%20Air%20Quality%20Forecasting/images/a06a739b02c2813c689c234cc346e393cfc0747b6380c894e73e6583817775e3.jpg)

![b765049a842f1d1bbc20f95e641d27b8267bcb0cc0d97514e55b1c21a65599f1.jpg](../nips_results/4576_Eulerian%20Neural%20Network%20Informed%20by%20Chemical%20Transport%20for%20Air%20Quality%20Forecasting/images/b765049a842f1d1bbc20f95e641d27b8267bcb0cc0d97514e55b1c21a65599f1.jpg)

![c51afff785c278181e020ab4b24cc5d95896c45a1942dd15e211d12f0aeef7c5.jpg](../nips_results/4576_Eulerian%20Neural%20Network%20Informed%20by%20Chemical%20Transport%20for%20Air%20Quality%20Forecasting/images/c51afff785c278181e020ab4b24cc5d95896c45a1942dd15e211d12f0aeef7c5.jpg)

![ddbd4cc97dee161075650189ad08d3347846ed7c1c80c5b826383f3df978c3f4.jpg](../nips_results/4576_Eulerian%20Neural%20Network%20Informed%20by%20Chemical%20Transport%20for%20Air%20Quality%20Forecasting/images/ddbd4cc97dee161075650189ad08d3347846ed7c1c80c5b826383f3df978c3f4.jpg)

### Tables

![1cf9b0ca407fc2cb992e1f7089f449bef332f9b1228f26a6a9059f7d7262bfcc.jpg](../nips_results/4576_Eulerian%20Neural%20Network%20Informed%20by%20Chemical%20Transport%20for%20Air%20Quality%20Forecasting/tables/1cf9b0ca407fc2cb992e1f7089f449bef332f9b1228f26a6a9059f7d7262bfcc.jpg)

![954d775df4abe3bc315600a679cffcd82f698d750f331ea42743039eef13a83b.jpg](../nips_results/4576_Eulerian%20Neural%20Network%20Informed%20by%20Chemical%20Transport%20for%20Air%20Quality%20Forecasting/tables/954d775df4abe3bc315600a679cffcd82f698d750f331ea42743039eef13a83b.jpg)

![d8b33981e913d448b160198857df7a7516d55604402588f0d77fbe24e2b134cb.jpg](../nips_results/4576_Eulerian%20Neural%20Network%20Informed%20by%20Chemical%20Transport%20for%20Air%20Quality%20Forecasting/tables/d8b33981e913d448b160198857df7a7516d55604402588f0d77fbe24e2b134cb.jpg)

## Sample Complexity of Distributionally Robust Average-Reward Reinforcement Learning


### Images

![341313c3d88c6bf66d365d9351a41709ceae66dd264bdd4ca6f5f6c3795f0b8b.jpg](../nips_results/4577_Sample%20Complexity%20of%20Distributionally%20Robust%20Average-Reward%20Reinforcement%20Learning/images/341313c3d88c6bf66d365d9351a41709ceae66dd264bdd4ca6f5f6c3795f0b8b.jpg)

![ab8e0c02d1cfb038bc6de7a3c84cec2fa9ee493b738e2cf317eb30d4431f95fc.jpg](../nips_results/4577_Sample%20Complexity%20of%20Distributionally%20Robust%20Average-Reward%20Reinforcement%20Learning/images/ab8e0c02d1cfb038bc6de7a3c84cec2fa9ee493b738e2cf317eb30d4431f95fc.jpg)

![bafbcb75f2a5871f03ae272f7ac2f908cfd4f6840c212434122479b5fdba87d9.jpg](../nips_results/4577_Sample%20Complexity%20of%20Distributionally%20Robust%20Average-Reward%20Reinforcement%20Learning/images/bafbcb75f2a5871f03ae272f7ac2f908cfd4f6840c212434122479b5fdba87d9.jpg)

![ecf40111d5c7f29540341ec542fe0ecdeb23e4927330c9385981a62ba7a20e89.jpg](../nips_results/4577_Sample%20Complexity%20of%20Distributionally%20Robust%20Average-Reward%20Reinforcement%20Learning/images/ecf40111d5c7f29540341ec542fe0ecdeb23e4927330c9385981a62ba7a20e89.jpg)

### Tables

![064aabc64a789829e8965b477785716ab10983b9ba42616d329f9aa04e4b4fdb.jpg](../nips_results/4577_Sample%20Complexity%20of%20Distributionally%20Robust%20Average-Reward%20Reinforcement%20Learning/tables/064aabc64a789829e8965b477785716ab10983b9ba42616d329f9aa04e4b4fdb.jpg)

![4fabfa1bd8c9c4668f2a1e845578fcab33f7d5a3497c44f4826a707c4b3bf739.jpg](../nips_results/4577_Sample%20Complexity%20of%20Distributionally%20Robust%20Average-Reward%20Reinforcement%20Learning/tables/4fabfa1bd8c9c4668f2a1e845578fcab33f7d5a3497c44f4826a707c4b3bf739.jpg)

![551a8156fae6d5a46b43dcd542b6c73d5c1cf0c0e128a5a5f78bf319c399e83b.jpg](../nips_results/4577_Sample%20Complexity%20of%20Distributionally%20Robust%20Average-Reward%20Reinforcement%20Learning/tables/551a8156fae6d5a46b43dcd542b6c73d5c1cf0c0e128a5a5f78bf319c399e83b.jpg)

## Distributionally Robust Feature Selection


### Images

![041818e99cc4df0e2fe6095e7385f2d11be9d49697ef3a352737f56559898771.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/images/041818e99cc4df0e2fe6095e7385f2d11be9d49697ef3a352737f56559898771.jpg)

![0428ebb93c695650f6d01cdcd7e110fe1424c31a7809980a8950413fc22b86f4.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/images/0428ebb93c695650f6d01cdcd7e110fe1424c31a7809980a8950413fc22b86f4.jpg)

![3f26734b5a22361b678ed0e513df9a219969897cba7af5112d43d10545319c96.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/images/3f26734b5a22361b678ed0e513df9a219969897cba7af5112d43d10545319c96.jpg)

![44814b014f11ff746314589fcaab0b92d3851c14827459ae37a70ad6a516077d.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/images/44814b014f11ff746314589fcaab0b92d3851c14827459ae37a70ad6a516077d.jpg)

![86ed2909a953b4b11c83ae0476ba4417ba82379175a7ad84738b67dde2e71641.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/images/86ed2909a953b4b11c83ae0476ba4417ba82379175a7ad84738b67dde2e71641.jpg)

![8e74e1f4d73c01e5207717027b5c0153f7a745ef0c74492fb18288757aac5e50.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/images/8e74e1f4d73c01e5207717027b5c0153f7a745ef0c74492fb18288757aac5e50.jpg)

![9c789311d9c71de795513a9020febc3ae6553707e04736d346ee0de0a42cfe66.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/images/9c789311d9c71de795513a9020febc3ae6553707e04736d346ee0de0a42cfe66.jpg)

![b7fd909259ac814f311107aa934743b7df5a093e74a0f4996f10db7e35aa1d08.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/images/b7fd909259ac814f311107aa934743b7df5a093e74a0f4996f10db7e35aa1d08.jpg)

![c8b3309072ff0b2fb004bed056ee0fd1c4d071e4e8e87fee50b2635832aa498d.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/images/c8b3309072ff0b2fb004bed056ee0fd1c4d071e4e8e87fee50b2635832aa498d.jpg)

![cfbcf46d9678f9b077041bf842c682c714ca909008b3ebab2d5dddcab810ad1f.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/images/cfbcf46d9678f9b077041bf842c682c714ca909008b3ebab2d5dddcab810ad1f.jpg)

### Tables

![0cb9c890e3c760019f25075fe1264fddb6576a77646551467cc2b7d3c6a7ab41.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/tables/0cb9c890e3c760019f25075fe1264fddb6576a77646551467cc2b7d3c6a7ab41.jpg)

![3a4a9939fb6ea98704383eea1f27a4f0f0496e510218210f951cc65d1db364b5.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/tables/3a4a9939fb6ea98704383eea1f27a4f0f0496e510218210f951cc65d1db364b5.jpg)

![54553323d97495078d392b7a0d95d1e9cb450079d02f360d397dc3ab3db78609.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/tables/54553323d97495078d392b7a0d95d1e9cb450079d02f360d397dc3ab3db78609.jpg)

![5caca348b10606c55ceb986dfd4c10847aeee22b97ec56491ab89bb0117f8b54.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/tables/5caca348b10606c55ceb986dfd4c10847aeee22b97ec56491ab89bb0117f8b54.jpg)

![85ce27b4c6eb6316203064131678452557b2da3934ea57756787eabf2715c055.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/tables/85ce27b4c6eb6316203064131678452557b2da3934ea57756787eabf2715c055.jpg)

![d56a5c21bf3f94d092d8b67c619debee1019dbd43d17694f553de023dba19081.jpg](../nips_results/4578_Distributionally%20Robust%20Feature%20Selection/tables/d56a5c21bf3f94d092d8b67c619debee1019dbd43d17694f553de023dba19081.jpg)

## Unveiling the Uncertainty in Embodied and Operational Carbon of Large AI Models through a Probabilistic Carbon Accounting Model


### Images

![4cd7ba008a39f5b0466facd372a40c4d75c86c6b1ed2f5a84350c714f54ff4b7.jpg](../nips_results/4579_Unveiling%20the%20Uncertainty%20in%20Embodied%20and%20Operational%20Carbon%20of%20Large%20AI%20Models%20through%20a%20Probabilis/images/4cd7ba008a39f5b0466facd372a40c4d75c86c6b1ed2f5a84350c714f54ff4b7.jpg)

![5250d21882fd27a426157afa584b9044bf3fee95dfe182638ce02be680a21c97.jpg](../nips_results/4579_Unveiling%20the%20Uncertainty%20in%20Embodied%20and%20Operational%20Carbon%20of%20Large%20AI%20Models%20through%20a%20Probabilis/images/5250d21882fd27a426157afa584b9044bf3fee95dfe182638ce02be680a21c97.jpg)

![85bd2ec510dd3fe7d19c2a822168e31354678616a15337265f5b5858b51b52d0.jpg](../nips_results/4579_Unveiling%20the%20Uncertainty%20in%20Embodied%20and%20Operational%20Carbon%20of%20Large%20AI%20Models%20through%20a%20Probabilis/images/85bd2ec510dd3fe7d19c2a822168e31354678616a15337265f5b5858b51b52d0.jpg)

![d81f97d1ebaa7f7f41e3127f5e12f5ce907ea633ac2c9e33274fd1f573fa3e0c.jpg](../nips_results/4579_Unveiling%20the%20Uncertainty%20in%20Embodied%20and%20Operational%20Carbon%20of%20Large%20AI%20Models%20through%20a%20Probabilis/images/d81f97d1ebaa7f7f41e3127f5e12f5ce907ea633ac2c9e33274fd1f573fa3e0c.jpg)

![e4d28248e1c3a6a07b21ec6bf1ab8e41dd6f249af06587dafe111918198180ca.jpg](../nips_results/4579_Unveiling%20the%20Uncertainty%20in%20Embodied%20and%20Operational%20Carbon%20of%20Large%20AI%20Models%20through%20a%20Probabilis/images/e4d28248e1c3a6a07b21ec6bf1ab8e41dd6f249af06587dafe111918198180ca.jpg)

### Tables

![098a1c42613dc84db191f632f44a1ca3dca78d133223c2809944b8b36fe5f077.jpg](../nips_results/4579_Unveiling%20the%20Uncertainty%20in%20Embodied%20and%20Operational%20Carbon%20of%20Large%20AI%20Models%20through%20a%20Probabilis/tables/098a1c42613dc84db191f632f44a1ca3dca78d133223c2809944b8b36fe5f077.jpg)

![3afcebb6e2f5f4f472721a2b52c32bf6b98b1f34488d3f7598996e94f50e970b.jpg](../nips_results/4579_Unveiling%20the%20Uncertainty%20in%20Embodied%20and%20Operational%20Carbon%20of%20Large%20AI%20Models%20through%20a%20Probabilis/tables/3afcebb6e2f5f4f472721a2b52c32bf6b98b1f34488d3f7598996e94f50e970b.jpg)

![55b5b859107b559ef1922eae6f5f7cd2bb87499a69edd2be9e1d387045374f1e.jpg](../nips_results/4579_Unveiling%20the%20Uncertainty%20in%20Embodied%20and%20Operational%20Carbon%20of%20Large%20AI%20Models%20through%20a%20Probabilis/tables/55b5b859107b559ef1922eae6f5f7cd2bb87499a69edd2be9e1d387045374f1e.jpg)

![95c299025cda4ad54ce2cdcc3b82412f3a5760dc7004defb1bd9fbee3509e66b.jpg](../nips_results/4579_Unveiling%20the%20Uncertainty%20in%20Embodied%20and%20Operational%20Carbon%20of%20Large%20AI%20Models%20through%20a%20Probabilis/tables/95c299025cda4ad54ce2cdcc3b82412f3a5760dc7004defb1bd9fbee3509e66b.jpg)

![ce3a2682d433827aaa21b60bf5a1e6cfc53a6a2a1b33e0beb7bc34f0bd71cb1a.jpg](../nips_results/4579_Unveiling%20the%20Uncertainty%20in%20Embodied%20and%20Operational%20Carbon%20of%20Large%20AI%20Models%20through%20a%20Probabilis/tables/ce3a2682d433827aaa21b60bf5a1e6cfc53a6a2a1b33e0beb7bc34f0bd71cb1a.jpg)

![fdbabdfae1da5d92f5c4c4fe0ab421e657e6a4f2c5701a2f70bf8b9f04c5a86a.jpg](../nips_results/4579_Unveiling%20the%20Uncertainty%20in%20Embodied%20and%20Operational%20Carbon%20of%20Large%20AI%20Models%20through%20a%20Probabilis/tables/fdbabdfae1da5d92f5c4c4fe0ab421e657e6a4f2c5701a2f70bf8b9f04c5a86a.jpg)

## FedRACE: A Hierarchical and Statistical Framework for Robust Federated Learning


### Images

![740e0e01e8502dc36394c4c9386cfeae98221179e84f49a4e734d16fa8c6c9dc.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/images/740e0e01e8502dc36394c4c9386cfeae98221179e84f49a4e734d16fa8c6c9dc.jpg)

![743db4ccd0bc652f0fe2d65ec8e6a4c9e73ee64e5c8666321f18980353e1f837.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/images/743db4ccd0bc652f0fe2d65ec8e6a4c9e73ee64e5c8666321f18980353e1f837.jpg)

![77ccea7f1115bbdaa1ae70d457501f4ba3417cf867176eb8032e0d7a5a78efb0.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/images/77ccea7f1115bbdaa1ae70d457501f4ba3417cf867176eb8032e0d7a5a78efb0.jpg)

![c6ea797908420dc3e9601b32e636a48c6b978ad5f46d15d40552e2dacdc9b080.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/images/c6ea797908420dc3e9601b32e636a48c6b978ad5f46d15d40552e2dacdc9b080.jpg)

![def67134b93dcb88fd1f14a22e4609d374134e07987232b1df72e0ea664eb087.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/images/def67134b93dcb88fd1f14a22e4609d374134e07987232b1df72e0ea664eb087.jpg)

![fe7019ac228f2eae6bb29f3f2c7640dcd1f1d2346e62b9c4b03a1dba88b7f5a4.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/images/fe7019ac228f2eae6bb29f3f2c7640dcd1f1d2346e62b9c4b03a1dba88b7f5a4.jpg)

### Tables

![37504f8839cea635c0f550abe5c4245c5a3ebb63242ad21fb62ed39d58863a81.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/tables/37504f8839cea635c0f550abe5c4245c5a3ebb63242ad21fb62ed39d58863a81.jpg)

![3e0158b9eedb1eb1431aa6022836ab466d80fa3e5fed6f42289c7408106083fd.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/tables/3e0158b9eedb1eb1431aa6022836ab466d80fa3e5fed6f42289c7408106083fd.jpg)

![48d20fecebeb35ddc9b7bcd5d4379030e940403341e3d55ef5f7e15e4eeff3c9.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/tables/48d20fecebeb35ddc9b7bcd5d4379030e940403341e3d55ef5f7e15e4eeff3c9.jpg)

![4b21edc75d65a4195e8ccae6675d9943780636e6e720a13d7bfc1d1d1ac158f8.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/tables/4b21edc75d65a4195e8ccae6675d9943780636e6e720a13d7bfc1d1d1ac158f8.jpg)

![60b5ed832b817a5b2652a8b5c2fc652bb01fc70abeecb9679951d93f34b92715.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/tables/60b5ed832b817a5b2652a8b5c2fc652bb01fc70abeecb9679951d93f34b92715.jpg)

![6414c94810eabc000b2f2f65b7f01dfa9e8b75dde81d073eb0b7aa785f29425f.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/tables/6414c94810eabc000b2f2f65b7f01dfa9e8b75dde81d073eb0b7aa785f29425f.jpg)

![e90f8b7e1e8ad0a8b23f724ad343459b9222cfc0833145e7d2b39f594f138aa7.jpg](../nips_results/4580_FedRACE_%20A%20Hierarchical%20and%20Statistical%20Framework%20for%20Robust%20Federated%20Learning/tables/e90f8b7e1e8ad0a8b23f724ad343459b9222cfc0833145e7d2b39f594f138aa7.jpg)

## JanusDNA: A Powerful Bi-directional Hybrid DNA Foundation Model


### Images

![4205df76edbff3096695d1900fd32ba48e57356314def9122904c26f34f625a6.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/images/4205df76edbff3096695d1900fd32ba48e57356314def9122904c26f34f625a6.jpg)

![58161eb0548ba28f75af372a44fcdfb9eb4c9763cd09f8ed0f223ee494e52c76.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/images/58161eb0548ba28f75af372a44fcdfb9eb4c9763cd09f8ed0f223ee494e52c76.jpg)

![625b11813a6a171f51a568858c196224f52097815cf03d8648c761fa5b8b0e46.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/images/625b11813a6a171f51a568858c196224f52097815cf03d8648c761fa5b8b0e46.jpg)

![69b7ae59d8fb939d03940662098917c5423d440db6c4be0b147cfc8b66c6f9e3.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/images/69b7ae59d8fb939d03940662098917c5423d440db6c4be0b147cfc8b66c6f9e3.jpg)

![abb97367257ec7f3fadb914949d53e427f16dd143b936e1bdff2818c510647d6.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/images/abb97367257ec7f3fadb914949d53e427f16dd143b936e1bdff2818c510647d6.jpg)

### Tables

![07712188331b9c62dc1452391135de87e12783b9fe75b1140cd7786a93edfe8c.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/07712188331b9c62dc1452391135de87e12783b9fe75b1140cd7786a93edfe8c.jpg)

![25f7c0d3eab43696a9d2e6c9d4073b96c428bc67590f8dab96e640aad2911701.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/25f7c0d3eab43696a9d2e6c9d4073b96c428bc67590f8dab96e640aad2911701.jpg)

![2744248bef2e2585296f0d90a95e459ef6c66d4921d6655fbb44403a97bf3522.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/2744248bef2e2585296f0d90a95e459ef6c66d4921d6655fbb44403a97bf3522.jpg)

![64aad97562192c5ebcfdedc534bec3792a3b247bde45f9d6b1640bbba24a668c.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/64aad97562192c5ebcfdedc534bec3792a3b247bde45f9d6b1640bbba24a668c.jpg)

![76a46d583ea1495b48e024e5f9c778ddda9e978abbbe5d54d97c6e132431a824.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/76a46d583ea1495b48e024e5f9c778ddda9e978abbbe5d54d97c6e132431a824.jpg)

![88a31f9fdd18cc2527f1fd670b4d838f5c54e0f7385edada902959770065bf6b.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/88a31f9fdd18cc2527f1fd670b4d838f5c54e0f7385edada902959770065bf6b.jpg)

![8e1e223f5ef1fc723981fc2bfdcbbde25f63cebeff3f13b12ac66c6826b3b095.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/8e1e223f5ef1fc723981fc2bfdcbbde25f63cebeff3f13b12ac66c6826b3b095.jpg)

![9bf8d613d222b13e714939bdc516d649db9f43cb3fdb05b846997459977ed37f.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/9bf8d613d222b13e714939bdc516d649db9f43cb3fdb05b846997459977ed37f.jpg)

![c9739092942a97eb6d3c15529190991a441519b52528918d493866fa0153ab70.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/c9739092942a97eb6d3c15529190991a441519b52528918d493866fa0153ab70.jpg)

![c9ea767c94ad8302be07bd607977465d56660480c2e00040b56ad08072133766.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/c9ea767c94ad8302be07bd607977465d56660480c2e00040b56ad08072133766.jpg)

![cdf6c5f7e62fe359f976e9b951161a4d58c30ff60e62a9aa2b26c5ab6b811c3b.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/cdf6c5f7e62fe359f976e9b951161a4d58c30ff60e62a9aa2b26c5ab6b811c3b.jpg)

![f946375434bb5c32dd4b0f2ec9b1d082a7c4c681af47458303d96ee188a847c9.jpg](../nips_results/4581_JanusDNA_%20A%20Powerful%20Bi-directional%20Hybrid%20DNA%20Foundation%20Model/tables/f946375434bb5c32dd4b0f2ec9b1d082a7c4c681af47458303d96ee188a847c9.jpg)

## OpenMMEgo: Enhancing Egocentric Understanding for LMMs with Open Weights and Data


### Images

![07ed041ea382e8de3a63514e64f9695903a80aa5a1f82b0cadf5c43a1c82433c.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/07ed041ea382e8de3a63514e64f9695903a80aa5a1f82b0cadf5c43a1c82433c.jpg)

![21a60cfb9998ef71da95d963d332898633cfddff534f934c532e25d64a69f5ef.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/21a60cfb9998ef71da95d963d332898633cfddff534f934c532e25d64a69f5ef.jpg)

![24ea726130545c875df86bc2e6d83154b79a9fd8755539d0d351b84a5ca6a31b.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/24ea726130545c875df86bc2e6d83154b79a9fd8755539d0d351b84a5ca6a31b.jpg)

![3a9752dbf07b63c861d4cd4307cdf63a7011fe4ee9971ecba4558fe0a61f958e.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/3a9752dbf07b63c861d4cd4307cdf63a7011fe4ee9971ecba4558fe0a61f958e.jpg)

![580d7c090b42f83008bba28a4391386c53a72ac3ea1d30e23dd13814d8761093.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/580d7c090b42f83008bba28a4391386c53a72ac3ea1d30e23dd13814d8761093.jpg)

![60e5d6e017afaad5c472a2ff27351c6cd0f82f133582dca4cb446b0e93c66006.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/60e5d6e017afaad5c472a2ff27351c6cd0f82f133582dca4cb446b0e93c66006.jpg)

![75dc5aa0841c737e6b232d6d179166310fd08a0e1cc5fdabe4b7b1fece01c645.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/75dc5aa0841c737e6b232d6d179166310fd08a0e1cc5fdabe4b7b1fece01c645.jpg)

![83a8caae1c1efb9827ad61a3f048c8c27bfa51c88b74f73bb457d119cd35c273.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/83a8caae1c1efb9827ad61a3f048c8c27bfa51c88b74f73bb457d119cd35c273.jpg)

![965b8db088e38b495e1e5862b50e1cac3015f54b4985c2d5f572f833d98e0066.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/965b8db088e38b495e1e5862b50e1cac3015f54b4985c2d5f572f833d98e0066.jpg)

![a36cc709c5be39a8de1d5107d869e33c19cdd29025926d5803142b0dc923ff18.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/a36cc709c5be39a8de1d5107d869e33c19cdd29025926d5803142b0dc923ff18.jpg)

![c7eb1cacc2599d10be17b9f7af2c6ea5d9529fcb6dcec324db2e7548dc67997c.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/c7eb1cacc2599d10be17b9f7af2c6ea5d9529fcb6dcec324db2e7548dc67997c.jpg)

![d455656ab6db4c98775e5855129987a66474820983d97ed7858b989e4b716c44.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/d455656ab6db4c98775e5855129987a66474820983d97ed7858b989e4b716c44.jpg)

![db9f3e62c0e7a6c674e5794342b2ab280a21fcf234970c97ef5caf14461922d2.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/db9f3e62c0e7a6c674e5794342b2ab280a21fcf234970c97ef5caf14461922d2.jpg)

![dd5bc160a75582cc4ebdefc09da5d153f7075e7fb74176d6c1cecd49b00dd121.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/dd5bc160a75582cc4ebdefc09da5d153f7075e7fb74176d6c1cecd49b00dd121.jpg)

![e525684b6730850f02239b67003f1cfe5ae5862efbf17da2bac431a70d9e1fc6.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/e525684b6730850f02239b67003f1cfe5ae5862efbf17da2bac431a70d9e1fc6.jpg)

![fa4aa05562be4ed2eca2ce1e04a212adeab03ee854631d2c2d786d1142ec3013.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/images/fa4aa05562be4ed2eca2ce1e04a212adeab03ee854631d2c2d786d1142ec3013.jpg)

### Tables

![2e40329a69d40b2ddd73dbd1fdd982f504186f5c3b292cb162740c975094a6c6.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/tables/2e40329a69d40b2ddd73dbd1fdd982f504186f5c3b292cb162740c975094a6c6.jpg)

![52e34f7103717001da900a285fcbe2a1cf3d6a2ace4ba69ed607b2ef60f461a6.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/tables/52e34f7103717001da900a285fcbe2a1cf3d6a2ace4ba69ed607b2ef60f461a6.jpg)

![591d957c82d021ba6369225b6da2d0f17c975af5dc5bca957e83a108b7d25ab6.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/tables/591d957c82d021ba6369225b6da2d0f17c975af5dc5bca957e83a108b7d25ab6.jpg)

![624c7e5feba87304d22d7d1c8f114ecdcce9bd99613d76b3260d375893604c74.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/tables/624c7e5feba87304d22d7d1c8f114ecdcce9bd99613d76b3260d375893604c74.jpg)

![70e922971bbd66a87c4577cfd8c175dc233f829c7651adb0cb1af03e5f3554cb.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/tables/70e922971bbd66a87c4577cfd8c175dc233f829c7651adb0cb1af03e5f3554cb.jpg)

![79cc679ecb39326affdc79736fe6e9dcdd7a7d5b58cea5bd7ac6bf8753d4bd17.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/tables/79cc679ecb39326affdc79736fe6e9dcdd7a7d5b58cea5bd7ac6bf8753d4bd17.jpg)

![a294716c6e9ca610a0ed9e299b5bfc6419344a8a9cab4e7a5ca1ccc30970e7c0.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/tables/a294716c6e9ca610a0ed9e299b5bfc6419344a8a9cab4e7a5ca1ccc30970e7c0.jpg)

![addfc61c91c63683ad459ef7350974ed4f99c1deb1c58a98ca782e482cac3bbd.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/tables/addfc61c91c63683ad459ef7350974ed4f99c1deb1c58a98ca782e482cac3bbd.jpg)

![dea77a4f1b5b0db09e3241422d7eb6af0fee6d01f02fc413d4f92de2f526d8c8.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/tables/dea77a4f1b5b0db09e3241422d7eb6af0fee6d01f02fc413d4f92de2f526d8c8.jpg)

![f7087956899c597e31eac6a4b083196d2c3d506177acc60055e1c3fe679c3925.jpg](../nips_results/4582_OpenMMEgo_%20Enhancing%20Egocentric%20Understanding%20for%20LMMs%20with%20Open%20Weights%20and%20Data/tables/f7087956899c597e31eac6a4b083196d2c3d506177acc60055e1c3fe679c3925.jpg)

## TrajAgent: An LLM-Agent Framework for Trajectory Modeling via Large-and-Small Model Collaboration


### Images

![6d576d8c717ef6893976bfc2c96ee2db7609043ec06c1fe0fe54585202cba34f.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/images/6d576d8c717ef6893976bfc2c96ee2db7609043ec06c1fe0fe54585202cba34f.jpg)

![7633e9ac90873cbf5c14b43790ec0e4638c4bc7a79372d7b69d8c0c9fc8f9289.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/images/7633e9ac90873cbf5c14b43790ec0e4638c4bc7a79372d7b69d8c0c9fc8f9289.jpg)

![8aa55a87c1e10f500410b8c416b8f6e868024bbcb9252e223fe929940098a1e0.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/images/8aa55a87c1e10f500410b8c416b8f6e868024bbcb9252e223fe929940098a1e0.jpg)

![e2b80434928c69286c77be45fae19400fd10f2ef07e76414ec5b15fd0b66f074.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/images/e2b80434928c69286c77be45fae19400fd10f2ef07e76414ec5b15fd0b66f074.jpg)

![f068af467c460428bc5447460b2cca7bed352c304e92317d53910c019303c79e.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/images/f068af467c460428bc5447460b2cca7bed352c304e92317d53910c019303c79e.jpg)

### Tables

![14e3b31a147b4ccf9ae039bf3beb527724528aa7e93b1c20cf16e4df9effe85a.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/14e3b31a147b4ccf9ae039bf3beb527724528aa7e93b1c20cf16e4df9effe85a.jpg)

![432862106889dc3e2a60e713b9f5260781d5a4cabcb4ecc5072484dcc075c52a.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/432862106889dc3e2a60e713b9f5260781d5a4cabcb4ecc5072484dcc075c52a.jpg)

![520cf2cac35c48bdc1f3112b58b3c5458c2b9d0866ff07f435a97d72d99ca9b5.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/520cf2cac35c48bdc1f3112b58b3c5458c2b9d0866ff07f435a97d72d99ca9b5.jpg)

![53704cc0a8dd9ec1e0605628036c8d6a0ba001a30e769cf264068dfc87f674ea.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/53704cc0a8dd9ec1e0605628036c8d6a0ba001a30e769cf264068dfc87f674ea.jpg)

![5789aff8eeb692aa2413173dd6a104cc12142fa30f74401785614cb12f2cecc0.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/5789aff8eeb692aa2413173dd6a104cc12142fa30f74401785614cb12f2cecc0.jpg)

![784296655f086152b143cbbc07d4d3a5ebc68d1ef27a3931c14225ef87be0ec5.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/784296655f086152b143cbbc07d4d3a5ebc68d1ef27a3931c14225ef87be0ec5.jpg)

![7a4d5321bbcf1627d4e35b88aaf1dd07341af76d8ab09d0845d472c1ca6243b7.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/7a4d5321bbcf1627d4e35b88aaf1dd07341af76d8ab09d0845d472c1ca6243b7.jpg)

![7d8ecaf1a5d27de0e9e86278178c7221fadea9ff6d3ac938a0a19765702289a6.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/7d8ecaf1a5d27de0e9e86278178c7221fadea9ff6d3ac938a0a19765702289a6.jpg)

![89c35de74266dd5c469330ec22cf66ebb8f7eac1d36a6a631b9b9da9fbef8f0c.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/89c35de74266dd5c469330ec22cf66ebb8f7eac1d36a6a631b9b9da9fbef8f0c.jpg)

![905b151c441bc62735b04ee6a8afb711aaf2f0c83b8b5ed754a3316df28680e2.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/905b151c441bc62735b04ee6a8afb711aaf2f0c83b8b5ed754a3316df28680e2.jpg)

![95c14a5ff079acf401b6e11dd79dc0eaa5679eaf15b291481ee1292de8ab0baf.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/95c14a5ff079acf401b6e11dd79dc0eaa5679eaf15b291481ee1292de8ab0baf.jpg)

![a5e88821fc102fd5ca974b624e346e6068ef83b4af67c086b1f9121627dce361.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/a5e88821fc102fd5ca974b624e346e6068ef83b4af67c086b1f9121627dce361.jpg)

![bf4cb5a324a1db817dadf00ae31da2cc8d46327d7207a5b67bebddc3e2ae52d7.jpg](../nips_results/4583_TrajAgent_%20An%20LLM-Agent%20Framework%20for%20Trajectory%20Modeling%20via%20Large-and-Small%20Model%20Collaboration/tables/bf4cb5a324a1db817dadf00ae31da2cc8d46327d7207a5b67bebddc3e2ae52d7.jpg)

## Simple and Optimal Sublinear Algorithms for Mean Estimation


### Images

![030ad864075cc437d93e315b21f13a1e315f54aa5928aae2aa6e61b4f96ba1c2.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/images/030ad864075cc437d93e315b21f13a1e315f54aa5928aae2aa6e61b4f96ba1c2.jpg)

![2f3550e10b8e116c991ef0893d10beab4eb5a3aecd464ac8a9d97c8ae16c2c2a.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/images/2f3550e10b8e116c991ef0893d10beab4eb5a3aecd464ac8a9d97c8ae16c2c2a.jpg)

![37d4d1c47a662d23cc6294e191391f3b26f6c82cd245709e6d6263638724d9ba.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/images/37d4d1c47a662d23cc6294e191391f3b26f6c82cd245709e6d6263638724d9ba.jpg)

![3c92a2340f056ad586705f721b3fe337e2ccc24bc126cbe38bae71a4a9dc8b80.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/images/3c92a2340f056ad586705f721b3fe337e2ccc24bc126cbe38bae71a4a9dc8b80.jpg)

![9f1d845a2d65a6ee9c0f8831f403fdc606a3df985d6a56ca32b266e32379990c.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/images/9f1d845a2d65a6ee9c0f8831f403fdc606a3df985d6a56ca32b266e32379990c.jpg)

![9ff49da92ed7d460b1a3ccfa00c89af1323a5ad44b5364c6948b6580ec6b835d.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/images/9ff49da92ed7d460b1a3ccfa00c89af1323a5ad44b5364c6948b6580ec6b835d.jpg)

![a26292983dc066a6486b64a8a9fdbdd8c2861db475217705064bf69483c879f9.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/images/a26292983dc066a6486b64a8a9fdbdd8c2861db475217705064bf69483c879f9.jpg)

![e560ee06b1e786849b7749d0b4330f0480b6c9ea8afae45d62650a7b853be246.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/images/e560ee06b1e786849b7749d0b4330f0480b6c9ea8afae45d62650a7b853be246.jpg)

### Tables

![1fca2f018f133c4f7a954a4077ddd06ccce4ed72158ee22dfb09b773e7d335b2.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/tables/1fca2f018f133c4f7a954a4077ddd06ccce4ed72158ee22dfb09b773e7d335b2.jpg)

![7b904d5d5b523866b8b49766bf39478afd0a2f43c2bb51b2b70cb6e9826cb17b.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/tables/7b904d5d5b523866b8b49766bf39478afd0a2f43c2bb51b2b70cb6e9826cb17b.jpg)

![b5362bc7b3c779960db8b658c9fe2dc0ebf5e0c43163568a8ad0071ce8e30a82.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/tables/b5362bc7b3c779960db8b658c9fe2dc0ebf5e0c43163568a8ad0071ce8e30a82.jpg)

![d402d6a36ffbb7ef9b0e7240eb62abf42e083f8ab601891c78e47bd55f8aa1af.jpg](../nips_results/4584_Simple%20and%20Optimal%20Sublinear%20Algorithms%20for%20Mean%20Estimation/tables/d402d6a36ffbb7ef9b0e7240eb62abf42e083f8ab601891c78e47bd55f8aa1af.jpg)

## Agnostic Continuous-Time Online Learning


### Images

![7a96d468f61628e4aa0a4254595e806cd7a195fb9269c323c8b29c6e812479c6.jpg](../nips_results/4585_Agnostic%20Continuous-Time%20Online%20Learning/images/7a96d468f61628e4aa0a4254595e806cd7a195fb9269c323c8b29c6e812479c6.jpg)

![fc5ef406f94bdd44dde7d36bd9aac1398548a675870332aeb09f50247aa930c3.jpg](../nips_results/4585_Agnostic%20Continuous-Time%20Online%20Learning/images/fc5ef406f94bdd44dde7d36bd9aac1398548a675870332aeb09f50247aa930c3.jpg)

### Tables

![6dac97156c5efbe440e8c3e2b5fd0eefd6f7223c14beb08083abdbeda5a3f9bb.jpg](../nips_results/4585_Agnostic%20Continuous-Time%20Online%20Learning/tables/6dac97156c5efbe440e8c3e2b5fd0eefd6f7223c14beb08083abdbeda5a3f9bb.jpg)

## Pattern-Guided Adaptive Prior for Structure Learning


### Images

![24504821358686360e6dacd29f50aa633692dcb8d2d3122b1d59c514259f6990.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/24504821358686360e6dacd29f50aa633692dcb8d2d3122b1d59c514259f6990.jpg)

![37487fda3405520b7aa098c8113d142fdab5ef33b896961e3013a534b81ca90d.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/37487fda3405520b7aa098c8113d142fdab5ef33b896961e3013a534b81ca90d.jpg)

![3f06226d2aaa7c3cb0c8d9d4d3cda7e5328272971a0fb8544030a25a51627468.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/3f06226d2aaa7c3cb0c8d9d4d3cda7e5328272971a0fb8544030a25a51627468.jpg)

![40ea1fcc93a9371f2cd5cf1063fa8362a5c08318e53503e04045e67f9f5bef74.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/40ea1fcc93a9371f2cd5cf1063fa8362a5c08318e53503e04045e67f9f5bef74.jpg)

![66a3ac54c2e12b56629999296a83e47fe98b8f4759325d89a46bd9f7f23a13f5.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/66a3ac54c2e12b56629999296a83e47fe98b8f4759325d89a46bd9f7f23a13f5.jpg)

![7ea56c0f13abece1973fc34711a552a3858a7776b88782d3f1d7cd73a3087f58.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/7ea56c0f13abece1973fc34711a552a3858a7776b88782d3f1d7cd73a3087f58.jpg)

![86100456a304c825c0f6c086be04a0c7510fa2581782ce0c267af8ee69c98f9c.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/86100456a304c825c0f6c086be04a0c7510fa2581782ce0c267af8ee69c98f9c.jpg)

![919776380bb167a92cb414e0f6fd3eb38d88bd4f3590aa97c3b75417ca82b36a.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/919776380bb167a92cb414e0f6fd3eb38d88bd4f3590aa97c3b75417ca82b36a.jpg)

![a26c8a696aa5127ba298ba36b4bc76e8dc2729e5c11beaa3b2c35c8792970361.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/a26c8a696aa5127ba298ba36b4bc76e8dc2729e5c11beaa3b2c35c8792970361.jpg)

![a2f9626c38a1022c0dabf19aed024d471c2ad5d1c6cc964eac8589ac1e331e4a.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/a2f9626c38a1022c0dabf19aed024d471c2ad5d1c6cc964eac8589ac1e331e4a.jpg)

![a93e6c50c317b3a202fecae083e92119457d696bcb16b6e4f7fbc5f9adcb8f38.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/a93e6c50c317b3a202fecae083e92119457d696bcb16b6e4f7fbc5f9adcb8f38.jpg)

![a951ff4a12a3db1bc0aa133bdacce831d5eee0f8875e9ef8fdec73dc6be0679b.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/a951ff4a12a3db1bc0aa133bdacce831d5eee0f8875e9ef8fdec73dc6be0679b.jpg)

![a9a6e5451507ac9754382b054a493a97fab1936672540aabbdd8f2929d7df0bd.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/a9a6e5451507ac9754382b054a493a97fab1936672540aabbdd8f2929d7df0bd.jpg)

![c8147347717deab5ca9b1676532257d74fbe2d131889b52b4e1750e9d924a8b3.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/c8147347717deab5ca9b1676532257d74fbe2d131889b52b4e1750e9d924a8b3.jpg)

![db2e772e08847acf131b35e2dbe8feb3320fd7f2c6f1b078b39f6ff32bdc291f.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/db2e772e08847acf131b35e2dbe8feb3320fd7f2c6f1b078b39f6ff32bdc291f.jpg)

![e43b2e2a86eb7fcf18635bfc18be55c0834ed32a8694e4bd878e2aa08a15d3eb.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/e43b2e2a86eb7fcf18635bfc18be55c0834ed32a8694e4bd878e2aa08a15d3eb.jpg)

![eb76f08fb73c677751c6231c18111859ad51a6a45ea8fd57ca653617c8fde959.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/eb76f08fb73c677751c6231c18111859ad51a6a45ea8fd57ca653617c8fde959.jpg)

![ed5595f2bccddaf8c9a1bb285db55048ba8c64f24e70fe9ec67bb039838d016b.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/ed5595f2bccddaf8c9a1bb285db55048ba8c64f24e70fe9ec67bb039838d016b.jpg)

![f61647655c4a72b3e5e2e8165aa2f401b65fb8b52f2dc91324713844961fb182.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/images/f61647655c4a72b3e5e2e8165aa2f401b65fb8b52f2dc91324713844961fb182.jpg)

### Tables

![1af90d67eeff402c84a98b1c3f409ba83885eca93bd1065f983366a7952a61c6.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/tables/1af90d67eeff402c84a98b1c3f409ba83885eca93bd1065f983366a7952a61c6.jpg)

![278ac8a964477564af842357d92f0a6c3d697862f5fa280c286a958da1952a38.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/tables/278ac8a964477564af842357d92f0a6c3d697862f5fa280c286a958da1952a38.jpg)

![37d2ac40b52acfcf78afb337ff13c4b716d0851e8e686c7d935701d459895e94.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/tables/37d2ac40b52acfcf78afb337ff13c4b716d0851e8e686c7d935701d459895e94.jpg)

![5ae28fe4f2968bbe9760a4c9e8096e42382c5497861968816dc4c436dfa667f8.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/tables/5ae28fe4f2968bbe9760a4c9e8096e42382c5497861968816dc4c436dfa667f8.jpg)

![73395e7fd1bea3ed72c517719f8e13401321de1fdc1eeceae7297b8005d53744.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/tables/73395e7fd1bea3ed72c517719f8e13401321de1fdc1eeceae7297b8005d53744.jpg)

![8d29eeba2a76c96b80242ffd166cf1b50dc23821f21437fd62f6fde47b983afd.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/tables/8d29eeba2a76c96b80242ffd166cf1b50dc23821f21437fd62f6fde47b983afd.jpg)

![8d4871b9dbd810637405929655318912af21a3eb2bb03d85bc65d8c1d909b800.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/tables/8d4871b9dbd810637405929655318912af21a3eb2bb03d85bc65d8c1d909b800.jpg)

![a9c8758d25197751a768d4bb7c57f31723eefd1d32b0291f48f46f2a8478844d.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/tables/a9c8758d25197751a768d4bb7c57f31723eefd1d32b0291f48f46f2a8478844d.jpg)

![ac5188d6db46d24ce34e2780b5bc67c52e3863d6e2a2560a2cbeba57f2c0dec7.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/tables/ac5188d6db46d24ce34e2780b5bc67c52e3863d6e2a2560a2cbeba57f2c0dec7.jpg)

![ca5c07259610e5d742241d26b7902b72b0a8e597dfac313050879cec9ebe4c85.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/tables/ca5c07259610e5d742241d26b7902b72b0a8e597dfac313050879cec9ebe4c85.jpg)

![da0b84506373481a3720c413db2734ce81f4b69b1e0bd269e33866850684b62a.jpg](../nips_results/4586_Pattern-Guided%20Adaptive%20Prior%20for%20Structure%20Learning/tables/da0b84506373481a3720c413db2734ce81f4b69b1e0bd269e33866850684b62a.jpg)

## Improving Reward Models with Proximal Policy Exploration for Preference-Based Reinforcement Learning


### Images

![6b6c413433022f98c369918660c4af20f216bc697f662a356808ba1edb945953.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/images/6b6c413433022f98c369918660c4af20f216bc697f662a356808ba1edb945953.jpg)

![70b790e0e71ec5bf4a021f09ea2711cb8572c29032d92cef31943689cd6adede.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/images/70b790e0e71ec5bf4a021f09ea2711cb8572c29032d92cef31943689cd6adede.jpg)

![73aa6326426c50aaa7309a516480e89b06b001d566182669d239c7eff0a4d882.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/images/73aa6326426c50aaa7309a516480e89b06b001d566182669d239c7eff0a4d882.jpg)

![7f7176c9ff5ea5310773ccd6cc3218a3a0f46fb34a5b0914f672570e739b0f2e.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/images/7f7176c9ff5ea5310773ccd6cc3218a3a0f46fb34a5b0914f672570e739b0f2e.jpg)

![87f3371313a914e75a9aeba25af5cad5e8f0ac8ddf6ecb30aa7884e0d4a8b9ac.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/images/87f3371313a914e75a9aeba25af5cad5e8f0ac8ddf6ecb30aa7884e0d4a8b9ac.jpg)

![b7dff17955bfe934ada5bc382caa6cfb64c4a5b0fd4e1f3c942711a61389ad2f.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/images/b7dff17955bfe934ada5bc382caa6cfb64c4a5b0fd4e1f3c942711a61389ad2f.jpg)

![bdb07fdd94a75dcb1465b9155b027d5e197f036d0c028499e28fc08aaf8e8951.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/images/bdb07fdd94a75dcb1465b9155b027d5e197f036d0c028499e28fc08aaf8e8951.jpg)

![d4d4494e61d462e2af1f78c4c2b935c874dd69b09b362d71f974bd75fd0af512.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/images/d4d4494e61d462e2af1f78c4c2b935c874dd69b09b362d71f974bd75fd0af512.jpg)

![e68f0aad6ea41ce57c2fd11018365d4a0d8dcdec7c24e5ae36da52443edf770d.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/images/e68f0aad6ea41ce57c2fd11018365d4a0d8dcdec7c24e5ae36da52443edf770d.jpg)

![f7530533ddd96cb4564320d9a9eec26c6878bf7e7ea8f0484cce5c263dbec01e.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/images/f7530533ddd96cb4564320d9a9eec26c6878bf7e7ea8f0484cce5c263dbec01e.jpg)

### Tables

![026c19c541833835817061aaea469893c7495bfecd3c9ee1bad5de20eedba3d8.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/026c19c541833835817061aaea469893c7495bfecd3c9ee1bad5de20eedba3d8.jpg)

![162c90e98b760e1d8b09f4f080288f29d6a6bb4d83ecea765503255e1585e5d0.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/162c90e98b760e1d8b09f4f080288f29d6a6bb4d83ecea765503255e1585e5d0.jpg)

![1799599a22d53f9d0684c46050d10fe27aab2e679e018b63569c13fb9a92d897.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/1799599a22d53f9d0684c46050d10fe27aab2e679e018b63569c13fb9a92d897.jpg)

![46b7f3d70e3cc29305a1a5bbe76e893ebf07bd3ab10437e6173c0abb422bd026.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/46b7f3d70e3cc29305a1a5bbe76e893ebf07bd3ab10437e6173c0abb422bd026.jpg)

![479803a5d575c2c1de37219e6bcc1f8232801b8d20a59921a4406ec3cafdebfb.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/479803a5d575c2c1de37219e6bcc1f8232801b8d20a59921a4406ec3cafdebfb.jpg)

![5944d3bbc7e48f4ae342ba6ffb28f3a2c758650897577424156c1d2e037e5259.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/5944d3bbc7e48f4ae342ba6ffb28f3a2c758650897577424156c1d2e037e5259.jpg)

![5e1e06abd223f952bd9ee02336daeb64f9d31289da94adecb62f21caecc8c635.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/5e1e06abd223f952bd9ee02336daeb64f9d31289da94adecb62f21caecc8c635.jpg)

![621e14ad8f0b096e4cc5c8173f1f109ae2707706422275802ff24a84acee522a.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/621e14ad8f0b096e4cc5c8173f1f109ae2707706422275802ff24a84acee522a.jpg)

![6a4fe1b8a66ddc811b9226ef2a5e9f77534ec4d572b00ab79ad2d90df61fa4e8.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/6a4fe1b8a66ddc811b9226ef2a5e9f77534ec4d572b00ab79ad2d90df61fa4e8.jpg)

![7b97d0a91dea67a7156dd35b790afa5ca1786df60da092fbc8171a422994f3e3.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/7b97d0a91dea67a7156dd35b790afa5ca1786df60da092fbc8171a422994f3e3.jpg)

![7f2f2ae8ed09d2cb4ae76e135bcd462ed06b1979f336f9c1ae9952886a0942fd.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/7f2f2ae8ed09d2cb4ae76e135bcd462ed06b1979f336f9c1ae9952886a0942fd.jpg)

![9d220282619ffd3d9663333a1b4ecb14c2e8c0acdfb482aa472d3412b9152d0c.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/9d220282619ffd3d9663333a1b4ecb14c2e8c0acdfb482aa472d3412b9152d0c.jpg)

![a5d1cad9033bfaa2d389b7d5376dd108668d7a53251522605eccb65aa3a74016.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/a5d1cad9033bfaa2d389b7d5376dd108668d7a53251522605eccb65aa3a74016.jpg)

![c20b35323371e51531145bf85ab96cb83c418960c6f0130bbb0ce8ff7358a3a5.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/c20b35323371e51531145bf85ab96cb83c418960c6f0130bbb0ce8ff7358a3a5.jpg)

![c3dab8f6aa11dc84b13753a3cfe8a762280556914630ef4724b18dc0003cbc20.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/c3dab8f6aa11dc84b13753a3cfe8a762280556914630ef4724b18dc0003cbc20.jpg)

![f538d6e32e59b438b18e33df9bf176e498f61758425e1aca090a95bfc7fe3ebd.jpg](../nips_results/4587_Improving%20Reward%20Models%20with%20Proximal%20Policy%20Exploration%20for%20Preference-Based%20Reinforcement%20Learning/tables/f538d6e32e59b438b18e33df9bf176e498f61758425e1aca090a95bfc7fe3ebd.jpg)

## Multiplayer Federated Learning: Reaching Equilibrium with Less Communication


### Images

![17a2826ed1c20221482e2f7991276089f23d3987ac2a71f85e15ac2d6157d266.jpg](../nips_results/4588_Multiplayer%20Federated%20Learning_%20Reaching%20Equilibrium%20with%20Less%20Communication/images/17a2826ed1c20221482e2f7991276089f23d3987ac2a71f85e15ac2d6157d266.jpg)

![211d4c63e8523cef9b2bb75d46a975141659ff337edbc078d5c768e0ae6c03a8.jpg](../nips_results/4588_Multiplayer%20Federated%20Learning_%20Reaching%20Equilibrium%20with%20Less%20Communication/images/211d4c63e8523cef9b2bb75d46a975141659ff337edbc078d5c768e0ae6c03a8.jpg)

![63471a9406a5663282ccedd0043dc8c67f64d7f784e82e0d5e514d0ec396d337.jpg](../nips_results/4588_Multiplayer%20Federated%20Learning_%20Reaching%20Equilibrium%20with%20Less%20Communication/images/63471a9406a5663282ccedd0043dc8c67f64d7f784e82e0d5e514d0ec396d337.jpg)

![74a6afdd44e2dd19f9dd9d8f0f6a1229de1065a46e519578e81ac2ae2b243f98.jpg](../nips_results/4588_Multiplayer%20Federated%20Learning_%20Reaching%20Equilibrium%20with%20Less%20Communication/images/74a6afdd44e2dd19f9dd9d8f0f6a1229de1065a46e519578e81ac2ae2b243f98.jpg)

![7c4ea5d61bff1938c1d913b6ca305f2fd9b9fe9aeba74bb96009580b95a569fb.jpg](../nips_results/4588_Multiplayer%20Federated%20Learning_%20Reaching%20Equilibrium%20with%20Less%20Communication/images/7c4ea5d61bff1938c1d913b6ca305f2fd9b9fe9aeba74bb96009580b95a569fb.jpg)

![e404c3519e4f70d7635eead50007081b0e5dfcfbf40c44c87b430f6d3175c6a0.jpg](../nips_results/4588_Multiplayer%20Federated%20Learning_%20Reaching%20Equilibrium%20with%20Less%20Communication/images/e404c3519e4f70d7635eead50007081b0e5dfcfbf40c44c87b430f6d3175c6a0.jpg)

### Tables

![ad62906df650e5f62ae61525d4ec69548b0819104c88b387fff0db672be0bfd8.jpg](../nips_results/4588_Multiplayer%20Federated%20Learning_%20Reaching%20Equilibrium%20with%20Less%20Communication/tables/ad62906df650e5f62ae61525d4ec69548b0819104c88b387fff0db672be0bfd8.jpg)

## Generation as Search Operator for Test-Time Scaling of Diffusion-based Combinatorial Optimization


### Images

![0542caf9c8807a0472e2cf5d2d5b9987d6d6e0c1b78599ea733222a20b82874e.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/images/0542caf9c8807a0472e2cf5d2d5b9987d6d6e0c1b78599ea733222a20b82874e.jpg)

![1a8fd4f815b0a4bfe30f146a8a1a14bec50abdae86b8d7990ba07cb3954f5320.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/images/1a8fd4f815b0a4bfe30f146a8a1a14bec50abdae86b8d7990ba07cb3954f5320.jpg)

![5c0757b8bf9bddec231c65b74c2cc19a06038edeaa9e026b6707a539ad06d4a7.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/images/5c0757b8bf9bddec231c65b74c2cc19a06038edeaa9e026b6707a539ad06d4a7.jpg)

![8beb0f502e5405967307f0c638caeb784d9817c1fc4660c112cbe1a910b96ef9.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/images/8beb0f502e5405967307f0c638caeb784d9817c1fc4660c112cbe1a910b96ef9.jpg)

![9910620978033cf1ecd923e1e30efdbe146d3e7102165ae3d5469b53f320d8e0.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/images/9910620978033cf1ecd923e1e30efdbe146d3e7102165ae3d5469b53f320d8e0.jpg)

### Tables

![28d36adfc280771b98e946fc9078885fe1ac65a70fd496c0e1d5e33626754a3c.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/28d36adfc280771b98e946fc9078885fe1ac65a70fd496c0e1d5e33626754a3c.jpg)

![59b7f30001fbafb65850228ac059dbba48d5118ddaf6ab25bf2bf7ed6e8690ff.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/59b7f30001fbafb65850228ac059dbba48d5118ddaf6ab25bf2bf7ed6e8690ff.jpg)

![628c7c5131d6fd50f2c09091c18a95058917643acad6cc9a40058b5a01c783c8.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/628c7c5131d6fd50f2c09091c18a95058917643acad6cc9a40058b5a01c783c8.jpg)

![65577e2bac258963850889674d43444e20370c3f7a2c6b85d6d3f19df1964870.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/65577e2bac258963850889674d43444e20370c3f7a2c6b85d6d3f19df1964870.jpg)

![69280307d29a03c004b09fe08ff65c444da056568abf88ba91589840857216a6.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/69280307d29a03c004b09fe08ff65c444da056568abf88ba91589840857216a6.jpg)

![77910b6ea70b6dc6341ce87e1d38beee984c7fc6a514e918cff8d8c6fbfacfd1.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/77910b6ea70b6dc6341ce87e1d38beee984c7fc6a514e918cff8d8c6fbfacfd1.jpg)

![a54ce2c7f8d8827edb4c4f036143b3442141ed105d31a7dfe17db3a8748621dd.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/a54ce2c7f8d8827edb4c4f036143b3442141ed105d31a7dfe17db3a8748621dd.jpg)

![addae142ff9f52d948f7a3ee33fad186e593793961ec0d7f1a16418c86ab282b.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/addae142ff9f52d948f7a3ee33fad186e593793961ec0d7f1a16418c86ab282b.jpg)

![aed529e9963156fdf17d5d1e6f2771cd5e08acab39154005847071332e98b5e8.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/aed529e9963156fdf17d5d1e6f2771cd5e08acab39154005847071332e98b5e8.jpg)

![b3f85c45b2c526c86a121a934290de3235193731855838e36f776d44eab53f17.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/b3f85c45b2c526c86a121a934290de3235193731855838e36f776d44eab53f17.jpg)

![c216c2f1d6e67467d891da087ea2c310d5edb2f58cfcc24b0c108486cf5a4dbc.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/c216c2f1d6e67467d891da087ea2c310d5edb2f58cfcc24b0c108486cf5a4dbc.jpg)

![ec29ca77c20ae4410cfa77438980783a8e096ebeda3d2dd41089bcc5f5efe246.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/ec29ca77c20ae4410cfa77438980783a8e096ebeda3d2dd41089bcc5f5efe246.jpg)

![eef98e2b93eba37170fb2de352a212fc2cdea588cebbcd900d3e67bd50923d8a.jpg](../nips_results/4589_Generation%20as%20Search%20Operator%20for%20Test-Time%20Scaling%20of%20Diffusion-based%20Combinatorial%20Optimization/tables/eef98e2b93eba37170fb2de352a212fc2cdea588cebbcd900d3e67bd50923d8a.jpg)

## Improving Retrieval-Augmented Generation through Multi-Agent Reinforcement Learning


### Images

![24413991d882836a25aa9325529d19b8854e8abd4cb7d97446c7e2b80c194324.jpg](../nips_results/4590_Improving%20Retrieval-Augmented%20Generation%20through%20Multi-Agent%20Reinforcement%20Learning/images/24413991d882836a25aa9325529d19b8854e8abd4cb7d97446c7e2b80c194324.jpg)

![54c04d9ebd8c84598a4e41bc07add46533fda6633317671807d1a948da232ed4.jpg](../nips_results/4590_Improving%20Retrieval-Augmented%20Generation%20through%20Multi-Agent%20Reinforcement%20Learning/images/54c04d9ebd8c84598a4e41bc07add46533fda6633317671807d1a948da232ed4.jpg)

![73c8c8a21dae4d4fdcfa72ce9da3b26b37e5b62dc9932404957e52371f7b111f.jpg](../nips_results/4590_Improving%20Retrieval-Augmented%20Generation%20through%20Multi-Agent%20Reinforcement%20Learning/images/73c8c8a21dae4d4fdcfa72ce9da3b26b37e5b62dc9932404957e52371f7b111f.jpg)

![c04bd665b17bc0b043ccb5388185b33e076aa0d458f40d9770329b0c0616bfd0.jpg](../nips_results/4590_Improving%20Retrieval-Augmented%20Generation%20through%20Multi-Agent%20Reinforcement%20Learning/images/c04bd665b17bc0b043ccb5388185b33e076aa0d458f40d9770329b0c0616bfd0.jpg)

### Tables

![00f3a97d075e725fc801800573971a64a352b8f2ab0d1c562d0e8fbb7e379ca8.jpg](../nips_results/4590_Improving%20Retrieval-Augmented%20Generation%20through%20Multi-Agent%20Reinforcement%20Learning/tables/00f3a97d075e725fc801800573971a64a352b8f2ab0d1c562d0e8fbb7e379ca8.jpg)

![01ad2c26cc1deb279d450f1b2cea71f1d7ca2ecbb6a01141d14cf00babea9ff8.jpg](../nips_results/4590_Improving%20Retrieval-Augmented%20Generation%20through%20Multi-Agent%20Reinforcement%20Learning/tables/01ad2c26cc1deb279d450f1b2cea71f1d7ca2ecbb6a01141d14cf00babea9ff8.jpg)

![37fadd989330b7bf3acda69aaaa65e4027a97e2565c01db74bc22c792bf619b5.jpg](../nips_results/4590_Improving%20Retrieval-Augmented%20Generation%20through%20Multi-Agent%20Reinforcement%20Learning/tables/37fadd989330b7bf3acda69aaaa65e4027a97e2565c01db74bc22c792bf619b5.jpg)

![829ebdb153b562bbe69e893e812c01d8f7a8a37dc81bec44b588a5fb67ae0222.jpg](../nips_results/4590_Improving%20Retrieval-Augmented%20Generation%20through%20Multi-Agent%20Reinforcement%20Learning/tables/829ebdb153b562bbe69e893e812c01d8f7a8a37dc81bec44b588a5fb67ae0222.jpg)

![d0e7ae7094af130f4c3fd4dccf243aec212d0e8e3dbea2351a35ed49f05d56c3.jpg](../nips_results/4590_Improving%20Retrieval-Augmented%20Generation%20through%20Multi-Agent%20Reinforcement%20Learning/tables/d0e7ae7094af130f4c3fd4dccf243aec212d0e8e3dbea2351a35ed49f05d56c3.jpg)

## Global Convergence for Average Reward Constrained MDPs with Primal-Dual Actor Critic Algorithm


### Tables

![c3602cc00975c249f04de4696aa07ea27013eed2fdef1e6a3b346bb6fb30ef1c.jpg](../nips_results/4591_Global%20Convergence%20for%20Average%20Reward%20Constrained%20MDPs%20with%20Primal-Dual%20Actor%20Critic%20Algorithm/tables/c3602cc00975c249f04de4696aa07ea27013eed2fdef1e6a3b346bb6fb30ef1c.jpg)

## Efficient and Generalizable Mixed-Precision Quantization via Topological Entropy


### Images

![0f5e4fe1f734e6ff17b1dd08babe5edd19d2bdb4f65bcd960ddcd886ee222d78.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/0f5e4fe1f734e6ff17b1dd08babe5edd19d2bdb4f65bcd960ddcd886ee222d78.jpg)

![0fb73372b8a5c4001e939eab23e320db493476ac75414154b382c82f692f17f6.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/0fb73372b8a5c4001e939eab23e320db493476ac75414154b382c82f692f17f6.jpg)

![5e782e5eb1cddbc830386504ab914e1f6fe0e6a9e8a4282b14b25a6a9a3fdd5e.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/5e782e5eb1cddbc830386504ab914e1f6fe0e6a9e8a4282b14b25a6a9a3fdd5e.jpg)

![74c6f10523637757f3bfb691a7964ca131146b3057ebc947e1754da406b83a83.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/74c6f10523637757f3bfb691a7964ca131146b3057ebc947e1754da406b83a83.jpg)

![90d9fd30bed9d1222308ddcfc09edeee0fe4a4250150fe1cee836b214505fd72.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/90d9fd30bed9d1222308ddcfc09edeee0fe4a4250150fe1cee836b214505fd72.jpg)

![9179dac525873054dac6c59ee0a3b8f92001a0a0e8aafa6a7725f94a8fb338d3.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/9179dac525873054dac6c59ee0a3b8f92001a0a0e8aafa6a7725f94a8fb338d3.jpg)

![9ac47fabbe32578556876a30e238df79c8775dcb1c9ed8bb5707a2c158454782.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/9ac47fabbe32578556876a30e238df79c8775dcb1c9ed8bb5707a2c158454782.jpg)

![a24ea904e0a09a8deba48a0c0efdaf280dd3e1d494eb24153c2b2341f3eb2ea6.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/a24ea904e0a09a8deba48a0c0efdaf280dd3e1d494eb24153c2b2341f3eb2ea6.jpg)

![b99e04bd13441e77b0c9bd9ce27049cddf9903200b465ef9c6125161fb410712.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/b99e04bd13441e77b0c9bd9ce27049cddf9903200b465ef9c6125161fb410712.jpg)

![d68c6531dfa269678e82fc8da3fa67e57dff1145c6567322f5b8b52cfcbf4036.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/d68c6531dfa269678e82fc8da3fa67e57dff1145c6567322f5b8b52cfcbf4036.jpg)

![da040262cf2e2fb8d26274ced22041c624f51a001556b3d66ae94b7d35f34f34.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/da040262cf2e2fb8d26274ced22041c624f51a001556b3d66ae94b7d35f34f34.jpg)

![e13b468c8ac3ed6c4b3468b70b935f91e7592c77bc2ba79f0fcc5f2940904759.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/e13b468c8ac3ed6c4b3468b70b935f91e7592c77bc2ba79f0fcc5f2940904759.jpg)

![eb0bdc364cf36d7f95f4bef3325a127305e9fed6e3113b579b923c8c0a199136.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/images/eb0bdc364cf36d7f95f4bef3325a127305e9fed6e3113b579b923c8c0a199136.jpg)

### Tables

![0f3e6f9adf42909904319000ce8548b4efa01775323b7b2f12f8b866a92f57ac.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/0f3e6f9adf42909904319000ce8548b4efa01775323b7b2f12f8b866a92f57ac.jpg)

![16797aa7bfd49183d8915beb20ca1479aa51da4da9d6f3518c482d51e1079470.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/16797aa7bfd49183d8915beb20ca1479aa51da4da9d6f3518c482d51e1079470.jpg)

![2cb28e7259de50dd46503555453180ca30ec2252b50a7eaad6e4a29b329e9d96.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/2cb28e7259de50dd46503555453180ca30ec2252b50a7eaad6e4a29b329e9d96.jpg)

![63f95469281152bb7aa713ad5db3ede6d79c5f0a0878e520668113857c63a5e4.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/63f95469281152bb7aa713ad5db3ede6d79c5f0a0878e520668113857c63a5e4.jpg)

![91abb54e8c194bfa2abe6a535c738107cfe53dcbb88874e3ab2348282d02683e.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/91abb54e8c194bfa2abe6a535c738107cfe53dcbb88874e3ab2348282d02683e.jpg)

![9a4f46e8f1adcdf3487e0a0f0840dfd24ebd8859a5bc27f052399f8d8fba3fbb.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/9a4f46e8f1adcdf3487e0a0f0840dfd24ebd8859a5bc27f052399f8d8fba3fbb.jpg)

![9e2f30539f5d3b08b34fb90c045fbcf4f44c3f423d84b11b4fefd12976b5612f.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/9e2f30539f5d3b08b34fb90c045fbcf4f44c3f423d84b11b4fefd12976b5612f.jpg)

![b0eb583b72f9304206e72b55d426a2580a045428b74001dabdf1bd679505bd82.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/b0eb583b72f9304206e72b55d426a2580a045428b74001dabdf1bd679505bd82.jpg)

![c5daed359c23565331a50a36e4a751742572abbf8e7cc0b7e0f3e6f185a21115.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/c5daed359c23565331a50a36e4a751742572abbf8e7cc0b7e0f3e6f185a21115.jpg)

![d3416a532ee2ff4bd089d1f3587df030e009322792048580db41b89b6f1b0614.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/d3416a532ee2ff4bd089d1f3587df030e009322792048580db41b89b6f1b0614.jpg)

![e538ba0c8c525353dbb24d52a91951602450670c892ecefbda06639997f19043.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/e538ba0c8c525353dbb24d52a91951602450670c892ecefbda06639997f19043.jpg)

![f559e44fd8dd1a5a19f4383e794e5049e328984fe8bad6c1751cfc6b4435a23d.jpg](../nips_results/4592_Efficient%20and%20Generalizable%20Mixed-Precision%20Quantization%20via%20Topological%20Entropy/tables/f559e44fd8dd1a5a19f4383e794e5049e328984fe8bad6c1751cfc6b4435a23d.jpg)

## Compute-Optimal Scaling for Value-Based Deep RL


### Images

![03040abcf14c50c77eb9169941147f0b02ba506f294eef54f466b142d4f0920a.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/03040abcf14c50c77eb9169941147f0b02ba506f294eef54f466b142d4f0920a.jpg)

![17a2ce04a5758a3a306953dbf8e3e951c0f9daa6dcf093e2ced67ccf06024744.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/17a2ce04a5758a3a306953dbf8e3e951c0f9daa6dcf093e2ced67ccf06024744.jpg)

![205494c298729dea143165aa5bc30a1bb9b17ba792865a8684785bc0af874911.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/205494c298729dea143165aa5bc30a1bb9b17ba792865a8684785bc0af874911.jpg)

![292a330547683671349c0204d021562dd1c825f0c35a5d8b13de8b8f26a80393.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/292a330547683671349c0204d021562dd1c825f0c35a5d8b13de8b8f26a80393.jpg)

![2b217038d4107b36b64ca8bf3d3852306ca06bcfd5ecb3128069692ababa3732.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/2b217038d4107b36b64ca8bf3d3852306ca06bcfd5ecb3128069692ababa3732.jpg)

![3ea03931ef787a10c8d569e5aabf85ba00f7d4fd595baee7293e1f58f58a6547.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/3ea03931ef787a10c8d569e5aabf85ba00f7d4fd595baee7293e1f58f58a6547.jpg)

![41815ba02a52e4b810cca72aa87f10ecc4ae32ccc859c6f1cde9fd38c784f933.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/41815ba02a52e4b810cca72aa87f10ecc4ae32ccc859c6f1cde9fd38c784f933.jpg)

![558ce58a6d13ec8bf5dcd904f16085065da42c7afacd0de5103805ddd352fcf8.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/558ce58a6d13ec8bf5dcd904f16085065da42c7afacd0de5103805ddd352fcf8.jpg)

![69435c0065255cccdb8e812cd6eedc2aaab7173e186f20c49b56f178b82590e1.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/69435c0065255cccdb8e812cd6eedc2aaab7173e186f20c49b56f178b82590e1.jpg)

![6faaab6e5a40b337c5572a58bc59bfb60d6a911e263a310d3aa696ee2356348e.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/6faaab6e5a40b337c5572a58bc59bfb60d6a911e263a310d3aa696ee2356348e.jpg)

![73fea49d7531d7c7a6c8243e1f679ed2245d9b7e2e770c4c5236a15d959df581.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/73fea49d7531d7c7a6c8243e1f679ed2245d9b7e2e770c4c5236a15d959df581.jpg)

![797cdbf1e75564a47d7097210c23e7ca8be18acca8a6c4e28a591fe2a5fe8f13.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/797cdbf1e75564a47d7097210c23e7ca8be18acca8a6c4e28a591fe2a5fe8f13.jpg)

![9e34ce4d095d25e8c3c75bd49e5876ea875bc2b7dea401051521d2eba2e6668b.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/9e34ce4d095d25e8c3c75bd49e5876ea875bc2b7dea401051521d2eba2e6668b.jpg)

![a834626d5eed2f7bff9d0639a6d845d88f5a4384196f2008eb199f3a6ec37610.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/a834626d5eed2f7bff9d0639a6d845d88f5a4384196f2008eb199f3a6ec37610.jpg)

![acabfc625cb644b337e819bf6cc70a6f1f93786a27d7da39f1273476ee86233a.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/acabfc625cb644b337e819bf6cc70a6f1f93786a27d7da39f1273476ee86233a.jpg)

![afb82da138e1e710a9d5f6ad94393b8fef2776dcbb25489d68dd5735af93dd3b.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/afb82da138e1e710a9d5f6ad94393b8fef2776dcbb25489d68dd5735af93dd3b.jpg)

![b0ea806d91d42f80bed8138811b87b58f5d64f71be7a94a203eb1aec2175e974.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/b0ea806d91d42f80bed8138811b87b58f5d64f71be7a94a203eb1aec2175e974.jpg)

![b1b70d21529be37e1ae3214d4aa59cabcdd2abffda185dad25147d1f7682bdf5.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/b1b70d21529be37e1ae3214d4aa59cabcdd2abffda185dad25147d1f7682bdf5.jpg)

![b1ba16ce9b98761def47835963b0b56bc37b367c76dc39f939d76f5d7adc681d.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/b1ba16ce9b98761def47835963b0b56bc37b367c76dc39f939d76f5d7adc681d.jpg)

![d031cc686e9809103da551c9d0c729966cc0d862895829f05ef8e3fd18944ec3.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/d031cc686e9809103da551c9d0c729966cc0d862895829f05ef8e3fd18944ec3.jpg)

![d50ca86209d1d01c701114ea32d61d6d2fc4fca0cb1179c338783030cfc751f9.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/d50ca86209d1d01c701114ea32d61d6d2fc4fca0cb1179c338783030cfc751f9.jpg)

![e2225a3437d28cf29b98b1349752acfbdcb7cfd8bb0e194cb94aeec5b86f4de5.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/images/e2225a3437d28cf29b98b1349752acfbdcb7cfd8bb0e194cb94aeec5b86f4de5.jpg)

### Tables

![a582e57927e8aaa1e0a29a38d004ff98d0cb844cd679f5ab54ebffd68e836894.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/tables/a582e57927e8aaa1e0a29a38d004ff98d0cb844cd679f5ab54ebffd68e836894.jpg)

![a7f12440d3e2a5a4bbc9ab6e49c69c1873e960ac8eb88424ab5a61b7efcb1003.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/tables/a7f12440d3e2a5a4bbc9ab6e49c69c1873e960ac8eb88424ab5a61b7efcb1003.jpg)

![abae0f64d180831a850c65162a75266a8626116446e10e0df674caed8e4de7fe.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/tables/abae0f64d180831a850c65162a75266a8626116446e10e0df674caed8e4de7fe.jpg)

![bbe95564dbb39b785ac36b875692bd7b3764f2019a94efe945971dee7dbf6690.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/tables/bbe95564dbb39b785ac36b875692bd7b3764f2019a94efe945971dee7dbf6690.jpg)

![c281ced95c1eec2c619122c7e0be80c69b1496c7f1b5f7f3ab86e871dd744ed0.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/tables/c281ced95c1eec2c619122c7e0be80c69b1496c7f1b5f7f3ab86e871dd744ed0.jpg)

![db258e1287e6ba59bfa8864e6acc2e9ea02fca6978325897deaad22d5571cc7e.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/tables/db258e1287e6ba59bfa8864e6acc2e9ea02fca6978325897deaad22d5571cc7e.jpg)

![e65b9cfe924c9b5cf5500f7ca8b3e2bbaefa32b7af5df199055c901b598bb7d5.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/tables/e65b9cfe924c9b5cf5500f7ca8b3e2bbaefa32b7af5df199055c901b598bb7d5.jpg)

![e8581c3dab04a8efc2d9225d08835ea0c46fd8b32a77a65b81e415ed2212b171.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/tables/e8581c3dab04a8efc2d9225d08835ea0c46fd8b32a77a65b81e415ed2212b171.jpg)

![fde5188581a71e94cae655d37523afce7f78922408003667c909edba58831e97.jpg](../nips_results/4593_Compute-Optimal%20Scaling%20for%20Value-Based%20Deep%20RL/tables/fde5188581a71e94cae655d37523afce7f78922408003667c909edba58831e97.jpg)

## Sloth: scaling laws for LLM skills to predict multi-benchmark performance across families


### Images

![0a2d34d8306b75202393673c32a51a2b27a0261d39ada07ef504ffcfb5ac2ce0.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/0a2d34d8306b75202393673c32a51a2b27a0261d39ada07ef504ffcfb5ac2ce0.jpg)

![0d2ccfadc201643e52a1a4f475a5509adce4cd3a9836d368c6a17903d3fb36b8.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/0d2ccfadc201643e52a1a4f475a5509adce4cd3a9836d368c6a17903d3fb36b8.jpg)

![13e80cd4e35bdaae200ac341755fa5ea7d7e5882c439a34a5db339177250a5dc.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/13e80cd4e35bdaae200ac341755fa5ea7d7e5882c439a34a5db339177250a5dc.jpg)

![190d7d0b319cb9add4cecd5ce0fb1614a5bf4b957c6f3dfa13f1dbfa07bec760.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/190d7d0b319cb9add4cecd5ce0fb1614a5bf4b957c6f3dfa13f1dbfa07bec760.jpg)

![197717da7b0f5f38a3187ae38d241b19285ab5af314bd4169f73be530dde63aa.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/197717da7b0f5f38a3187ae38d241b19285ab5af314bd4169f73be530dde63aa.jpg)

![1cc7bb46182ec5e23bed68a0298bad98010e4cd5b567b741575845325a5231d0.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/1cc7bb46182ec5e23bed68a0298bad98010e4cd5b567b741575845325a5231d0.jpg)

![1f98287e2992578759a15443e21f0ad17776a31910234ad9f7f2ef16f7835cb1.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/1f98287e2992578759a15443e21f0ad17776a31910234ad9f7f2ef16f7835cb1.jpg)

![26631ce33159a1d6b2ba5d4260785c80a67a965a20ece16de5f36a89ca6f3503.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/26631ce33159a1d6b2ba5d4260785c80a67a965a20ece16de5f36a89ca6f3503.jpg)

![27281e4d2aca3b24f46694e2755565ad098d2887a96de58d2119e061ab2d84d3.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/27281e4d2aca3b24f46694e2755565ad098d2887a96de58d2119e061ab2d84d3.jpg)

![304a9af32df5e4cbe98e48c98f788e55a67064ddf1ae38fe4a906e6e2722869a.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/304a9af32df5e4cbe98e48c98f788e55a67064ddf1ae38fe4a906e6e2722869a.jpg)

![368ce04e958fbc4a8fdb6b9be084938b78295a8e9a68b3ff6cd23b1ef97aa582.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/368ce04e958fbc4a8fdb6b9be084938b78295a8e9a68b3ff6cd23b1ef97aa582.jpg)

![47b547903afd42293bec7aa55bb70feb261a6433f3bb08e1df5d70f15d789763.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/47b547903afd42293bec7aa55bb70feb261a6433f3bb08e1df5d70f15d789763.jpg)

![48e581cdb1c85735bd495baedefc1549cf23c0c89d9766afc620e7c95f5bef97.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/48e581cdb1c85735bd495baedefc1549cf23c0c89d9766afc620e7c95f5bef97.jpg)

![50672cc983bdfd1595e97976c8989006e65f3ed1f7daff5aba1fb8b9df07a00f.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/50672cc983bdfd1595e97976c8989006e65f3ed1f7daff5aba1fb8b9df07a00f.jpg)

![5712ee67392862bb9602e1fb4f0ddd38c54210d0d1ffffb6414ce75f0616070d.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/5712ee67392862bb9602e1fb4f0ddd38c54210d0d1ffffb6414ce75f0616070d.jpg)

![5d8659e5b7513463556a7ea632a47b408aa799a087c00e2396da5fcea0d53e4c.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/5d8659e5b7513463556a7ea632a47b408aa799a087c00e2396da5fcea0d53e4c.jpg)

![5f9c3a576c46fe7c8b3e1f8d75598c2c8443cbfcaad74613ad73c70378953570.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/5f9c3a576c46fe7c8b3e1f8d75598c2c8443cbfcaad74613ad73c70378953570.jpg)

![611c67020b1c3f0ff6c794574231564d3796ee876c55e38123fb0cfd5e4b0498.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/611c67020b1c3f0ff6c794574231564d3796ee876c55e38123fb0cfd5e4b0498.jpg)

![721340089b803a12b67a42f4def4a15fc7c2a1f9a82fb557dd4cb5f83057ee54.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/721340089b803a12b67a42f4def4a15fc7c2a1f9a82fb557dd4cb5f83057ee54.jpg)

![723b7e8bc1453d6d5e5b7c38e02f75365ccd447f02b1a623e8d560f6b5ed335d.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/723b7e8bc1453d6d5e5b7c38e02f75365ccd447f02b1a623e8d560f6b5ed335d.jpg)

![75e2b01fafb88c63ac10e6d6c9763963946af8633553e3bd32bca5ec8ebe34cf.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/75e2b01fafb88c63ac10e6d6c9763963946af8633553e3bd32bca5ec8ebe34cf.jpg)

![79c06b0c34cc5d14550480e8f2ba10e6e4ac9f0efce2c4d0036720f74671cb0c.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/79c06b0c34cc5d14550480e8f2ba10e6e4ac9f0efce2c4d0036720f74671cb0c.jpg)

![87bb9f3943d78484656d0f37669b7c50b06c96e72be2fec3c7eacdff6d7d847f.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/87bb9f3943d78484656d0f37669b7c50b06c96e72be2fec3c7eacdff6d7d847f.jpg)

![8b86f8a50797fdf1c162cc694b78d0623049d66e7290d25e061ee4bae0083b15.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/8b86f8a50797fdf1c162cc694b78d0623049d66e7290d25e061ee4bae0083b15.jpg)

![93d8576b41596f46280b1a9ceb7f1bff2821591ea95c14d44d0879acaeb6babb.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/93d8576b41596f46280b1a9ceb7f1bff2821591ea95c14d44d0879acaeb6babb.jpg)

![94ff34b2d6aeb6e3e5d7d61f00add9fe3314d34a79efe05db863c12c7203c708.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/94ff34b2d6aeb6e3e5d7d61f00add9fe3314d34a79efe05db863c12c7203c708.jpg)

![9b5d8be6f69238b5eb57730b0603acb9b46f730f804a1ada09357070a927ea07.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/9b5d8be6f69238b5eb57730b0603acb9b46f730f804a1ada09357070a927ea07.jpg)

![9e46d816b9abca8e4e90c190c92e9ed7ed62aac1dfa74ed0445305ba8f80f619.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/9e46d816b9abca8e4e90c190c92e9ed7ed62aac1dfa74ed0445305ba8f80f619.jpg)

![b0372856761cb5d4790106733008e58b82dc97a3ecfb8d6bad6112c8f524be7c.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/b0372856761cb5d4790106733008e58b82dc97a3ecfb8d6bad6112c8f524be7c.jpg)

![b051d394143d1ff97907194d99f64c256770ae56072f7949d3c6441319c61974.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/b051d394143d1ff97907194d99f64c256770ae56072f7949d3c6441319c61974.jpg)

![b115ed58827f5bb904f4ab80f2c1eb68e15505d47bc4c4c0551397b6180ea43c.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/b115ed58827f5bb904f4ab80f2c1eb68e15505d47bc4c4c0551397b6180ea43c.jpg)

![b39371cacd51842126a25a42dd8d8510649c2428fb2c3916bcb1a861fe55e60e.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/b39371cacd51842126a25a42dd8d8510649c2428fb2c3916bcb1a861fe55e60e.jpg)

![c6ce1446855ef5580aa860033faab1d11efd4276fc9257daf86a821e66238556.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/c6ce1446855ef5580aa860033faab1d11efd4276fc9257daf86a821e66238556.jpg)

![c701c79e10aeca301d1d239b0a2de8a19950eba9ed28cc80da5c94223c4d2ac1.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/c701c79e10aeca301d1d239b0a2de8a19950eba9ed28cc80da5c94223c4d2ac1.jpg)

![ca596d22ed620f9096ce5a0d1dec52014332fd3b09baf63b01c877e67c6e10ca.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/ca596d22ed620f9096ce5a0d1dec52014332fd3b09baf63b01c877e67c6e10ca.jpg)

![de4c27486dc219b2dc5254f063b4156b2f93cd510fdc4c216a1f9e9cd182e473.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/de4c27486dc219b2dc5254f063b4156b2f93cd510fdc4c216a1f9e9cd182e473.jpg)

![ea3944a79a67fdc4306f5649dfa79c1dbab36ce0e23e4b75f2e1258b1378aab7.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/ea3944a79a67fdc4306f5649dfa79c1dbab36ce0e23e4b75f2e1258b1378aab7.jpg)

![ea7c42e4337e91743565933dfb2bdcecb480a1d2ed19f1a8f8b6451645c592ea.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/ea7c42e4337e91743565933dfb2bdcecb480a1d2ed19f1a8f8b6451645c592ea.jpg)

![f91885dc08197a366a419120e019d3afcf28f72d7c48b32873b48a3921f97192.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/f91885dc08197a366a419120e019d3afcf28f72d7c48b32873b48a3921f97192.jpg)

![f91fd79b18e7769cfb34c0925e32f131fa0fd2acded1e40f80a27e359a420f53.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/f91fd79b18e7769cfb34c0925e32f131fa0fd2acded1e40f80a27e359a420f53.jpg)

![f9c53a763df73c2b50e30b4ff5b402787883b5ab3a5ab47139aa1708afbfa057.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/f9c53a763df73c2b50e30b4ff5b402787883b5ab3a5ab47139aa1708afbfa057.jpg)

![fdbe2122a8581e7ab88b8a2b0d32d868570873886ba5285f683c0156ea5f4ccd.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/images/fdbe2122a8581e7ab88b8a2b0d32d868570873886ba5285f683c0156ea5f4ccd.jpg)

### Tables

![2f21b2e3893a89f58e03533ac735adedea7a7223664047e28a808b7995fa7f96.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/tables/2f21b2e3893a89f58e03533ac735adedea7a7223664047e28a808b7995fa7f96.jpg)

![ac6c56710926d38f23bf0b809e913e0aee1af51642e787803bf106085dfaf530.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/tables/ac6c56710926d38f23bf0b809e913e0aee1af51642e787803bf106085dfaf530.jpg)

![ae5a6fc5b75a322d6a6c71fbe5bb82a87580c62c1c9ea8c25605943941ebfe4b.jpg](../nips_results/4594_Sloth_%20scaling%20laws%20for%20LLM%20skills%20to%20predict%20multi-benchmark%20performance%20across%20families/tables/ae5a6fc5b75a322d6a6c71fbe5bb82a87580c62c1c9ea8c25605943941ebfe4b.jpg)

## SGAR: Structural Generative Augmentation for 3D Human Motion Retrieval


### Images

![0c0eff64437de56076d2bd01501f506f8f60eb53bd17e68ba9b067d96e4c8539.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/0c0eff64437de56076d2bd01501f506f8f60eb53bd17e68ba9b067d96e4c8539.jpg)

![1ba925b94f6b02f45751dd7049a450a0e8f8d38976275a2cbf7ef02cd845989f.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/1ba925b94f6b02f45751dd7049a450a0e8f8d38976275a2cbf7ef02cd845989f.jpg)

![1d2183d4036eb2e4b41b821dbf5a92232f9329a819be201f381da6c4dc560eb1.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/1d2183d4036eb2e4b41b821dbf5a92232f9329a819be201f381da6c4dc560eb1.jpg)

![25cfb919921db9f6ec760541b68e5f64e6f3c90f7e7285af43efbd12da008fbc.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/25cfb919921db9f6ec760541b68e5f64e6f3c90f7e7285af43efbd12da008fbc.jpg)

![2e92c881ebb3902fef22f8e3c90a48ed06e3c5352ef394dd9e8a77d030a47e90.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/2e92c881ebb3902fef22f8e3c90a48ed06e3c5352ef394dd9e8a77d030a47e90.jpg)

![305306d4693accc512d6b33cdd1a0a7e4da3ed00b75990b37cb390935e11608c.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/305306d4693accc512d6b33cdd1a0a7e4da3ed00b75990b37cb390935e11608c.jpg)

![32e52d01d6cdbf66400343bb110fc8181500308c116bcf83bfa14bc0ebdce422.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/32e52d01d6cdbf66400343bb110fc8181500308c116bcf83bfa14bc0ebdce422.jpg)

![46d309b8d87fdd7e9e5a567f95f0e14032ec4da62120dc9116525393740791fd.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/46d309b8d87fdd7e9e5a567f95f0e14032ec4da62120dc9116525393740791fd.jpg)

![7865a2347754711ffe9f4f1cb981fe3dcde82864986a55ecce28ba9fa0f91fb6.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/7865a2347754711ffe9f4f1cb981fe3dcde82864986a55ecce28ba9fa0f91fb6.jpg)

![7c5f8e2c296e28c3c87325bb31af5567cf8aef004aa7d4e6289f8ecbc07db66c.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/7c5f8e2c296e28c3c87325bb31af5567cf8aef004aa7d4e6289f8ecbc07db66c.jpg)

![83cf34597790f60b2bcb1a3003c264b754e4efc7bd774d2ff269433c6bd581e1.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/83cf34597790f60b2bcb1a3003c264b754e4efc7bd774d2ff269433c6bd581e1.jpg)

![850ab30b7543852a0777b7c3e52845543181bb32fe21775192169d8abb710486.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/850ab30b7543852a0777b7c3e52845543181bb32fe21775192169d8abb710486.jpg)

![a037112a64bdacbfbacee2817e086b6106c5382e845128fc66b1a3bb4fd16e5f.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/a037112a64bdacbfbacee2817e086b6106c5382e845128fc66b1a3bb4fd16e5f.jpg)

![a3d34afc96ae7acb281c4013fc94036ed531e3829f5c3037a54783863e130fc4.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/a3d34afc96ae7acb281c4013fc94036ed531e3829f5c3037a54783863e130fc4.jpg)

![a721c44450a3b3ac90690d55225471b942e9f9d6b464849fb912acec38144316.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/a721c44450a3b3ac90690d55225471b942e9f9d6b464849fb912acec38144316.jpg)

![a76a50d9f3e10c658e78a594e35347fdb824cca8010c9ff9dfe41b26ec963fd8.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/a76a50d9f3e10c658e78a594e35347fdb824cca8010c9ff9dfe41b26ec963fd8.jpg)

![ac04341a749579ec277c6e3844ab9569208afb0c5c3e9d99f51a8e9a11ce3350.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/ac04341a749579ec277c6e3844ab9569208afb0c5c3e9d99f51a8e9a11ce3350.jpg)

![bde510dc52cdfa65cdc008c75257a25da8a606f8a5a77d55cde64b3bbd6375a1.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/bde510dc52cdfa65cdc008c75257a25da8a606f8a5a77d55cde64b3bbd6375a1.jpg)

![c17ac7a8a2e4262e3867732349cf15add8e4c8331e50eee5d694cd5275a51481.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/c17ac7a8a2e4262e3867732349cf15add8e4c8331e50eee5d694cd5275a51481.jpg)

![de349bb103e5b61037e35efe2969908c867e90df28a48352344b27f4c03dfadb.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/de349bb103e5b61037e35efe2969908c867e90df28a48352344b27f4c03dfadb.jpg)

![f880ab25fe062496bffe23f41f9a48a3258ddf633d17e54902d86e614c1df4f4.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/images/f880ab25fe062496bffe23f41f9a48a3258ddf633d17e54902d86e614c1df4f4.jpg)

### Tables

![18678b1502ffeaf8f4dd65d295ea1e13df7da98226d4e91c1468a7bf86498bd7.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/18678b1502ffeaf8f4dd65d295ea1e13df7da98226d4e91c1468a7bf86498bd7.jpg)

![34d42504f10fd66c5a68d84a19d6bfc85ce699ee8bfd6e046eff063e17675d04.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/34d42504f10fd66c5a68d84a19d6bfc85ce699ee8bfd6e046eff063e17675d04.jpg)

![4a418f06a99ff7477b47d0491bc7a6ebb95da316887c74882e75bd758cd27ea0.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/4a418f06a99ff7477b47d0491bc7a6ebb95da316887c74882e75bd758cd27ea0.jpg)

![61c737e41d8b2241c4b85ac5e520bb817e5abea8884d72cdee440297e836157d.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/61c737e41d8b2241c4b85ac5e520bb817e5abea8884d72cdee440297e836157d.jpg)

![6be18aa6db7c04ace39863b7c3bc06ddde71d27a4f0261ecb66728e1368985f1.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/6be18aa6db7c04ace39863b7c3bc06ddde71d27a4f0261ecb66728e1368985f1.jpg)

![9713b4a5a2cc2dddd26dff9f85c31d68b9135b033f326ec3b70a4e3068f0acc3.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/9713b4a5a2cc2dddd26dff9f85c31d68b9135b033f326ec3b70a4e3068f0acc3.jpg)

![a7adcca3cba1d3c960c20c559358fd72ced0d237b9700af35744fe67095f53b2.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/a7adcca3cba1d3c960c20c559358fd72ced0d237b9700af35744fe67095f53b2.jpg)

![a9a97cb4625a156c0251901783360e853dc79043dd025d85f08c3eeb47e28325.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/a9a97cb4625a156c0251901783360e853dc79043dd025d85f08c3eeb47e28325.jpg)

![ac6ad8f1299e34a76bf25b55f29a32f535e268466e070b2beaef2a804448bb34.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/ac6ad8f1299e34a76bf25b55f29a32f535e268466e070b2beaef2a804448bb34.jpg)

![babeac1aca217bb3dff074b02aac2fdd9c6a907a1b101b135ad18025bad33824.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/babeac1aca217bb3dff074b02aac2fdd9c6a907a1b101b135ad18025bad33824.jpg)

![bda2938141aa49991c045c310e48edfacbe5c3a377b543c1e7ba2fbe2c6e58de.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/bda2938141aa49991c045c310e48edfacbe5c3a377b543c1e7ba2fbe2c6e58de.jpg)

![bfe564153e4212425c5eb915027a94722a03a372e25e706c01a6754f4fe7853a.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/bfe564153e4212425c5eb915027a94722a03a372e25e706c01a6754f4fe7853a.jpg)

![e2fcc8f35cfad8dc3a52d5702127020ebfc0b5d5a4506ae55995b4ee755b401a.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/e2fcc8f35cfad8dc3a52d5702127020ebfc0b5d5a4506ae55995b4ee755b401a.jpg)

![ec14cd528e8af93d7ccb358ea60208cc960a51c252b6bee936c6bc3817abeb27.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/ec14cd528e8af93d7ccb358ea60208cc960a51c252b6bee936c6bc3817abeb27.jpg)

![f72b2f4c4cb8d2d8ea478ca75c27bf18cdae87ae0962c9cc74a2724b5b871542.jpg](../nips_results/4595_SGAR_%20Structural%20Generative%20Augmentation%20for%203D%20Human%20Motion%20Retrieval/tables/f72b2f4c4cb8d2d8ea478ca75c27bf18cdae87ae0962c9cc74a2724b5b871542.jpg)

## Inexact Column Generation for Bayesian Network Structure Learning via Difference-of-Submodular Optimization


### Tables

![409f3731dcc60cda7a0312d97037f891cf5bc3f027aacaaa34ddfb1091246ee9.jpg](../nips_results/4596_Inexact%20Column%20Generation%20for%20Bayesian%20Network%20Structure%20Learning%20via%20Difference-of-Submodular%20Optim/tables/409f3731dcc60cda7a0312d97037f891cf5bc3f027aacaaa34ddfb1091246ee9.jpg)

![40dbdd0fd95c7bf4b4f7e45b5781b457d1e62ebeb410496904150dcc299f8c68.jpg](../nips_results/4596_Inexact%20Column%20Generation%20for%20Bayesian%20Network%20Structure%20Learning%20via%20Difference-of-Submodular%20Optim/tables/40dbdd0fd95c7bf4b4f7e45b5781b457d1e62ebeb410496904150dcc299f8c68.jpg)

![6a6864b08fd81c48d1322edc2a73d033d697b8499a02655d9fd44e2a2ad5076a.jpg](../nips_results/4596_Inexact%20Column%20Generation%20for%20Bayesian%20Network%20Structure%20Learning%20via%20Difference-of-Submodular%20Optim/tables/6a6864b08fd81c48d1322edc2a73d033d697b8499a02655d9fd44e2a2ad5076a.jpg)

![76f069d63af5da4cbc8f8e35481424c702b6e0fab364a2a6a65950c45de446f2.jpg](../nips_results/4596_Inexact%20Column%20Generation%20for%20Bayesian%20Network%20Structure%20Learning%20via%20Difference-of-Submodular%20Optim/tables/76f069d63af5da4cbc8f8e35481424c702b6e0fab364a2a6a65950c45de446f2.jpg)

![77ab83f9b0b9bb62da77d80000c69a9922c8848af3c5bdcf6353070618b9b120.jpg](../nips_results/4596_Inexact%20Column%20Generation%20for%20Bayesian%20Network%20Structure%20Learning%20via%20Difference-of-Submodular%20Optim/tables/77ab83f9b0b9bb62da77d80000c69a9922c8848af3c5bdcf6353070618b9b120.jpg)

![7c6b0d7a04ef1eb6ebe450f9953c154eb00adde19fb06a81985860899834bfd6.jpg](../nips_results/4596_Inexact%20Column%20Generation%20for%20Bayesian%20Network%20Structure%20Learning%20via%20Difference-of-Submodular%20Optim/tables/7c6b0d7a04ef1eb6ebe450f9953c154eb00adde19fb06a81985860899834bfd6.jpg)

![8c50f7b845e40a6e519a1fc44d21ecc8557b719e6811ca5d9a6240dd80f2e9a2.jpg](../nips_results/4596_Inexact%20Column%20Generation%20for%20Bayesian%20Network%20Structure%20Learning%20via%20Difference-of-Submodular%20Optim/tables/8c50f7b845e40a6e519a1fc44d21ecc8557b719e6811ca5d9a6240dd80f2e9a2.jpg)

![b6031d878c1004b7ee8d2ecb2b9cbaafd2b594b2907b63b6d5eab1154c6cf7cf.jpg](../nips_results/4596_Inexact%20Column%20Generation%20for%20Bayesian%20Network%20Structure%20Learning%20via%20Difference-of-Submodular%20Optim/tables/b6031d878c1004b7ee8d2ecb2b9cbaafd2b594b2907b63b6d5eab1154c6cf7cf.jpg)

![b99f48d179d8ce1de10922b763b3b994bcb9ff1cf35d58ef512049dbfe26f928.jpg](../nips_results/4596_Inexact%20Column%20Generation%20for%20Bayesian%20Network%20Structure%20Learning%20via%20Difference-of-Submodular%20Optim/tables/b99f48d179d8ce1de10922b763b3b994bcb9ff1cf35d58ef512049dbfe26f928.jpg)

![c06b10d5166fe1c07141f92d63d306194a8aa597f78ac5ca52c7feb07926a8c3.jpg](../nips_results/4596_Inexact%20Column%20Generation%20for%20Bayesian%20Network%20Structure%20Learning%20via%20Difference-of-Submodular%20Optim/tables/c06b10d5166fe1c07141f92d63d306194a8aa597f78ac5ca52c7feb07926a8c3.jpg)

## Isotropic Noise in Stochastic and Quantum Convex Optimization


### Tables

![252c09de71e9749e76bd658a6f5f84d388a91ee976dd46fb37b9bd45ce3ddbe2.jpg](../nips_results/4597_Isotropic%20Noise%20in%20Stochastic%20and%20Quantum%20Convex%20Optimization/tables/252c09de71e9749e76bd658a6f5f84d388a91ee976dd46fb37b9bd45ce3ddbe2.jpg)

## Hierarchical Demonstration Order Optimization for Many-shot In-Context Learning

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
