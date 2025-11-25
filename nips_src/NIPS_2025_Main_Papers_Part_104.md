# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 104 of 130

## 目录 (Table of Contents)

1. [On Minimax Estimation of Parameters in Softmax-Contaminated Mixture of Experts](#On-Minimax-Estimation-of-Parameters-in-Softmax-Contaminated-Mixture-of-Experts)
2. [Differentiation Through Black-Box Quadratic Programming Solvers](#Differentiation-Through-Black-Box-Quadratic-Programming-Solvers)
3. [$\boldsymbol{\lambda}$-Orthogonality Regularization for Compatible Representation Learning](#boldsymbollambda-Orthogonality-Regularization-for-Compatible-Representation-Learning)
4. [Statistical Analysis of the Sinkhorn Iterations for Two-Sample Schr\"{o}dinger Bridge Estimation](#Statistical-Analysis-of-the-Sinkhorn-Iterations-for-Two-Sample-Schrodinger-Bridge-Estimation)
5. [Frequency-Aware Token Reduction for Efficient Vision Transformer](#Frequency-Aware-Token-Reduction-for-Efficient-Vision-Transformer)
6. [LLM at Network Edge: A Layer-wise Efficient Federated Fine-tuning Approach](#LLM-at-Network-Edge-A-Layer-wise-Efficient-Federated-Fine-tuning-Approach)
7. [Machine Unlearning under Overparameterization](#Machine-Unlearning-under-Overparameterization)
8. [R2R: Efficiently Navigating Divergent Reasoning Paths with Small-Large Model Token Routing](#R2R-Efficiently-Navigating-Divergent-Reasoning-Paths-with-Small-Large-Model-Token-Routing)
9. [WALL-E: World Alignment by NeuroSymbolic Learning improves World Model-based LLM Agents](#WALL-E-World-Alignment-by-NeuroSymbolic-Learning-improves-World-Model-based-LLM-Agents)
10. [Gaussian Regression-Driven Tensorized Incomplete Multi-View Clustering with Dual Manifold Regularization](#Gaussian-Regression-Driven-Tensorized-Incomplete-Multi-View-Clustering-with-Dual-Manifold-Regularization)
11. [Fair Matroid Selection](#Fair-Matroid-Selection)
12. [Dependency Matters: Enhancing LLM Reasoning with Explicit Knowledge Grounding](#Dependency-Matters-Enhancing-LLM-Reasoning-with-Explicit-Knowledge-Grounding)
13. [Schrödinger Bridge Matching for Tree-Structured Costs and Entropic Wasserstein Barycentres](#Schrödinger-Bridge-Matching-for-Tree-Structured-Costs-and-Entropic-Wasserstein-Barycentres)
14. [Quantifying Elicitation of Latent Capabilities in Language Models](#Quantifying-Elicitation-of-Latent-Capabilities-in-Language-Models)
15. [Guiding LLM Decision-Making with Fairness Reward Models](#Guiding-LLM-Decision-Making-with-Fairness-Reward-Models)
16. [DOVE: Efficient One-Step Diffusion Model for Real-World Video Super-Resolution](#DOVE-Efficient-One-Step-Diffusion-Model-for-Real-World-Video-Super-Resolution)
17. [Nabla-R2D3: Effective and Efficient 3D Diffusion Alignment with 2D Rewards](#Nabla-R2D3-Effective-and-Efficient-3D-Diffusion-Alignment-with-2D-Rewards)
18. [How to build a consistency model: Learning flow maps via self-distillation](#How-to-build-a-consistency-model-Learning-flow-maps-via-self-distillation)
19. [SPACE: SPike-Aware Consistency Enhancement for Test-Time Adaptation in Spiking Neural Networks](#SPACE-SPike-Aware-Consistency-Enhancement-for-Test-Time-Adaptation-in-Spiking-Neural-Networks)
20. [FedEL: Federated Elastic Learning for Heterogeneous Devices](#FedEL-Federated-Elastic-Learning-for-Heterogeneous-Devices)
21. [Cooperative Bargaining Games Without Utilities: Mediated Solutions from Direction Oracles](#Cooperative-Bargaining-Games-Without-Utilities-Mediated-Solutions-from-Direction-Oracles)
22. [Time-Embedded Algorithm Unrolling for Computational MRI](#Time-Embedded-Algorithm-Unrolling-for-Computational-MRI)
23. [Noise Hypernetworks: Amortizing Test-Time Compute in Diffusion Models](#Noise-Hypernetworks-Amortizing-Test-Time-Compute-in-Diffusion-Models)
24. [Vector Database Watermarking](#Vector-Database-Watermarking)
25. [Neural Collapse under Gradient Flow on Shallow ReLU Networks for Orthogonally Separable Data](#Neural-Collapse-under-Gradient-Flow-on-Shallow-ReLU-Networks-for-Orthogonally-Separable-Data)
26. [Sparse Autoencoders Learn Monosemantic Features in Vision-Language Models](#Sparse-Autoencoders-Learn-Monosemantic-Features-in-Vision-Language-Models)
27. [PBR-SR: Mesh PBR Texture Super Resolution from 2D Image Priors](#PBR-SR-Mesh-PBR-Texture-Super-Resolution-from-2D-Image-Priors)
28. [Assignments for Congestion-Averse Agents: Seeking Competitive and Envy-Free Solutions](#Assignments-for-Congestion-Averse-Agents-Seeking-Competitive-and-Envy-Free-Solutions)
29. [Router-R1: Teaching LLMs Multi-Round Routing and Aggregation via Reinforcement Learning](#Router-R1-Teaching-LLMs-Multi-Round-Routing-and-Aggregation-via-Reinforcement-Learning)
30. [Are Language Models Efficient Reasoners? A Perspective from Logic Programming](#Are-Language-Models-Efficient-Reasoners-A-Perspective-from-Logic-Programming)
31. [FreqExit: Enabling Early-Exit Inference for Visual Autoregressive Models via Frequency-Aware Guidance](#FreqExit-Enabling-Early-Exit-Inference-for-Visual-Autoregressive-Models-via-Frequency-Aware-Guidance)
32. [StreamBridge: Turning Your Offline Video Large Language Model into a Proactive Streaming Assistant](#StreamBridge-Turning-Your-Offline-Video-Large-Language-Model-into-a-Proactive-Streaming-Assistant)
33. [Balancing Positive and Negative Classification Error Rates in Positive-Unlabeled Learning](#Balancing-Positive-and-Negative-Classification-Error-Rates-in-Positive-Unlabeled-Learning)
34. [Lookahead Routing for Large Language Models](#Lookahead-Routing-for-Large-Language-Models)
35. [What Do Latent Action Models Actually Learn?](#What-Do-Latent-Action-Models-Actually-Learn)
36. [RelationAdapter: Learning and Transferring Visual Relation with Diffusion Transformers](#RelationAdapter-Learning-and-Transferring-Visual-Relation-with-Diffusion-Transformers)
37. [Discovering Data Structures: Nearest Neighbor Search and Beyond](#Discovering-Data-Structures-Nearest-Neighbor-Search-and-Beyond)
38. [Monoculture or Multiplicity: Which Is It?](#Monoculture-or-Multiplicity-Which-Is-It)
39. [Automaton Constrained Q-Learning](#Automaton-Constrained-Q-Learning)
40. [MVSMamba: Multi-View Stereo with State Space Model](#MVSMamba-Multi-View-Stereo-with-State-Space-Model)
41. [SUMO: Subspace-Aware Moment-Orthogonalization for Accelerating Memory-Efficient LLM Training](#SUMO-Subspace-Aware-Moment-Orthogonalization-for-Accelerating-Memory-Efficient-LLM-Training)

---


## On Minimax Estimation of Parameters in Softmax-Contaminated Mixture of Experts

### Images

![074cc064aa959ba9be7c51ec08209f559c5666984d805ef36f39cf8e1d8e0586.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/images/074cc064aa959ba9be7c51ec08209f559c5666984d805ef36f39cf8e1d8e0586.jpg)

![3bb630cb61f5a12c48d54c3944caa188cef29c99b9139bde821d13dfb48b8cbd.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/images/3bb630cb61f5a12c48d54c3944caa188cef29c99b9139bde821d13dfb48b8cbd.jpg)

![978533498514902913d3337f0db35ac59c2cbfd724acf24e2894d35ba4b2268b.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/images/978533498514902913d3337f0db35ac59c2cbfd724acf24e2894d35ba4b2268b.jpg)

![b028ea866fc054dc349143aa7ad1d0a650be1bb8407be6942973494a441ee617.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/images/b028ea866fc054dc349143aa7ad1d0a650be1bb8407be6942973494a441ee617.jpg)

![e597218d026d23d974cf6001f7725687d71e58fa3bfc2e35e88ddfdc70880a3e.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/images/e597218d026d23d974cf6001f7725687d71e58fa3bfc2e35e88ddfdc70880a3e.jpg)

### Tables

![305822978fd8cf21a4ec32d779677bed846c5d06bff6935f48ac9cd873230a4a.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/305822978fd8cf21a4ec32d779677bed846c5d06bff6935f48ac9cd873230a4a.jpg)

![462a6c0927fb6b829bb78e01ecc271c8d21324c06391cc0fa363e591e6621375.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/462a6c0927fb6b829bb78e01ecc271c8d21324c06391cc0fa363e591e6621375.jpg)

![4e543d7c678f64d8cb00c5c54290877cbb75452b076c0cb3b263e4c65c36bb00.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/4e543d7c678f64d8cb00c5c54290877cbb75452b076c0cb3b263e4c65c36bb00.jpg)

![7e7fb9967f60b66fad95e0f7667613b4fe847eb0d3b897efc9e9789ba1c9420f.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/7e7fb9967f60b66fad95e0f7667613b4fe847eb0d3b897efc9e9789ba1c9420f.jpg)

![bc708ec327183facf20a74e2bf8f09ecc7b7198ade982e1c0c12e69955a9cd5c.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/bc708ec327183facf20a74e2bf8f09ecc7b7198ade982e1c0c12e69955a9cd5c.jpg)

![c930f88401250cf44652b4b0ac16a331d6ff103bd58f5a59781ecc71d3e83a67.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/c930f88401250cf44652b4b0ac16a331d6ff103bd58f5a59781ecc71d3e83a67.jpg)

![cbc9b7b989b4d7b207eac0417ff7d4b8ba903e5060bae33883c0534cf84c7f19.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/cbc9b7b989b4d7b207eac0417ff7d4b8ba903e5060bae33883c0534cf84c7f19.jpg)

![d8553d51b1f1d48ddfc5baac33cb9f2db69d91bac5f28d26b989fb91fe190199.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/d8553d51b1f1d48ddfc5baac33cb9f2db69d91bac5f28d26b989fb91fe190199.jpg)

![d8b26f7a227a9de8f25d20c978087714e8f632820479d2ab5624ac7151b0b77a.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/d8b26f7a227a9de8f25d20c978087714e8f632820479d2ab5624ac7151b0b77a.jpg)

![d8e49e995cad2a904760df81719d21a43d7f962f82879c6372f92bb825d687c5.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/d8e49e995cad2a904760df81719d21a43d7f962f82879c6372f92bb825d687c5.jpg)

![e42bd3539c969e0614bb5bb84a90bd8e701cddf204d63cf7c3955505dacceefd.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/e42bd3539c969e0614bb5bb84a90bd8e701cddf204d63cf7c3955505dacceefd.jpg)

![fe111de371e3a249b088a4540f7c957ea07291dd5e246281e25bbe5b0c167b6a.jpg](../nips_results/4268_Universal%20Cross-Tokenizer%20Distillation%20via%20Approximate%20Likelihood%20Matching/tables/fe111de371e3a249b088a4540f7c957ea07291dd5e246281e25bbe5b0c167b6a.jpg)

## On Minimax Estimation of Parameters in Softmax-Contaminated Mixture of Experts


### Images

![1e6d173a5dc3521842670a23b8aee13ef0b3ae3a9c8907e7d1abd615430bafc4.jpg](../nips_results/4269_On%20Minimax%20Estimation%20of%20Parameters%20in%20Softmax-Contaminated%20Mixture%20of%20Experts/images/1e6d173a5dc3521842670a23b8aee13ef0b3ae3a9c8907e7d1abd615430bafc4.jpg)

![44c956cee67cc2e33a7485ce05b30148f10cbc196a084d40aa095b3d08c27ecd.jpg](../nips_results/4269_On%20Minimax%20Estimation%20of%20Parameters%20in%20Softmax-Contaminated%20Mixture%20of%20Experts/images/44c956cee67cc2e33a7485ce05b30148f10cbc196a084d40aa095b3d08c27ecd.jpg)

### Tables

![1607af1d448ff2e23f20b101cf80f04d4c38473d9f2964582b797c9ebd2010c7.jpg](../nips_results/4269_On%20Minimax%20Estimation%20of%20Parameters%20in%20Softmax-Contaminated%20Mixture%20of%20Experts/tables/1607af1d448ff2e23f20b101cf80f04d4c38473d9f2964582b797c9ebd2010c7.jpg)

![b04a5099902e92bd646a190c6305c06521643997eefd278a611d39a5713c40e7.jpg](../nips_results/4269_On%20Minimax%20Estimation%20of%20Parameters%20in%20Softmax-Contaminated%20Mixture%20of%20Experts/tables/b04a5099902e92bd646a190c6305c06521643997eefd278a611d39a5713c40e7.jpg)

## Differentiation Through Black-Box Quadratic Programming Solvers


### Images

![0cdc1008cd028ce678e148c2d7ce8b74ebcdf67e08c6dc93cf7ecc1e23de6222.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/images/0cdc1008cd028ce678e148c2d7ce8b74ebcdf67e08c6dc93cf7ecc1e23de6222.jpg)

![28d4cf0e67dbc1f2eff5764c2fb6c075c60911dbb2b8362097653b7c1f31d1de.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/images/28d4cf0e67dbc1f2eff5764c2fb6c075c60911dbb2b8362097653b7c1f31d1de.jpg)

![4d06ad55dad218bc3e002e25e4d4801f8bf3d109fd46dbe2ab9f4c21819f779b.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/images/4d06ad55dad218bc3e002e25e4d4801f8bf3d109fd46dbe2ab9f4c21819f779b.jpg)

![5ffdbe3cc7bf3b93227aacb5491bc7300ad6f650915b6f8944e33c441e6d47a9.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/images/5ffdbe3cc7bf3b93227aacb5491bc7300ad6f650915b6f8944e33c441e6d47a9.jpg)

![6bf054ecea87b86307a49bf1d756f11d4e9474c718a9f99c9247aca5e74ff37e.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/images/6bf054ecea87b86307a49bf1d756f11d4e9474c718a9f99c9247aca5e74ff37e.jpg)

![94f1a1f47dbc9abd5f7e5ef919cbbf54eb558ac4808708d9cca19b4f61fc1fa1.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/images/94f1a1f47dbc9abd5f7e5ef919cbbf54eb558ac4808708d9cca19b4f61fc1fa1.jpg)

![a69a8aa5d1394fd5c748550e8f7fc8af1298f939112e2b9431081435a46ef24b.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/images/a69a8aa5d1394fd5c748550e8f7fc8af1298f939112e2b9431081435a46ef24b.jpg)

![bd2740ec2780eaa84860f27f8bb92748ae196ee89362aa8bf3fae2120f11be2d.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/images/bd2740ec2780eaa84860f27f8bb92748ae196ee89362aa8bf3fae2120f11be2d.jpg)

![daf2e05f48b33e968712cc9267a2a51c296adce31eadff85415446aca4529491.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/images/daf2e05f48b33e968712cc9267a2a51c296adce31eadff85415446aca4529491.jpg)

![fc5f24c40d782fe8807d4a6065568a5d00cc31a52052b8c55fb14f462fc46a20.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/images/fc5f24c40d782fe8807d4a6065568a5d00cc31a52052b8c55fb14f462fc46a20.jpg)

### Tables

![0495a54243befa9b2ec641166ec09b728d41bb25e3e97cf1092851f242630a81.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/tables/0495a54243befa9b2ec641166ec09b728d41bb25e3e97cf1092851f242630a81.jpg)

![2b31c2b337d78252a73157c7c9ca85388718787bd2f48c4cf2153cff0b411e24.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/tables/2b31c2b337d78252a73157c7c9ca85388718787bd2f48c4cf2153cff0b411e24.jpg)

![58994301536932112d28b76ec0670cacbb68182a0f097338907723f9edad7e0b.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/tables/58994301536932112d28b76ec0670cacbb68182a0f097338907723f9edad7e0b.jpg)

![5b80453daca47709c548df1c2a04a18937591eac1769ee879a064d368b944167.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/tables/5b80453daca47709c548df1c2a04a18937591eac1769ee879a064d368b944167.jpg)

![75d14e5bf5b47a6cee1f6ede3b76bdf067bcee854b60dde01eeed5d52b0347d9.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/tables/75d14e5bf5b47a6cee1f6ede3b76bdf067bcee854b60dde01eeed5d52b0347d9.jpg)

![987bb0c68b6cfcb38af79de2b520ceaf8051053e3e47795ff10b811c1f1f0fa4.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/tables/987bb0c68b6cfcb38af79de2b520ceaf8051053e3e47795ff10b811c1f1f0fa4.jpg)

![c4ef4df72786e4af76c5da34058b0c481315352364d979c8da82ab36de6f41f8.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/tables/c4ef4df72786e4af76c5da34058b0c481315352364d979c8da82ab36de6f41f8.jpg)

![d3231cc2b66ec370878d7c2f7341d4fccbad94e3b307ec71dafdc2acd374b7d0.jpg](../nips_results/4270_Differentiation%20Through%20Black-Box%20Quadratic%20Programming%20Solvers/tables/d3231cc2b66ec370878d7c2f7341d4fccbad94e3b307ec71dafdc2acd374b7d0.jpg)

## $\boldsymbol{\lambda}$-Orthogonality Regularization for Compatible Representation Learning


### Images

![2fe7f59a7fc7128527a2d29c457365db9914f9b3ad06d4442d956bad1e5cb788.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/images/2fe7f59a7fc7128527a2d29c457365db9914f9b3ad06d4442d956bad1e5cb788.jpg)

![50e1f12c1479a6d6f4e8488ad788fc329bbcdab167c8e1fa440e7abca91faf6b.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/images/50e1f12c1479a6d6f4e8488ad788fc329bbcdab167c8e1fa440e7abca91faf6b.jpg)

![743301d73dbea38d47dac679626524b9bb938f74b8f9a046db43d76284fec9b7.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/images/743301d73dbea38d47dac679626524b9bb938f74b8f9a046db43d76284fec9b7.jpg)

![9a9fddb5b04e1c461f8ef1c93b945f75313cbf10bf233ca9814de08c71b2149a.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/images/9a9fddb5b04e1c461f8ef1c93b945f75313cbf10bf233ca9814de08c71b2149a.jpg)

![a83f4a99d9201b596f7eae01648549dc75c82b63dd3b597d6bbca4d058d81898.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/images/a83f4a99d9201b596f7eae01648549dc75c82b63dd3b597d6bbca4d058d81898.jpg)

![c82b8a804688f04b940cc24b4110c904de997b91e20508cc4e76c0b4e480e804.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/images/c82b8a804688f04b940cc24b4110c904de997b91e20508cc4e76c0b4e480e804.jpg)

### Tables

![0080efeb1397813196ce0a25fa675266f2539f2f06cb8481bbefc40e8d38943f.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/0080efeb1397813196ce0a25fa675266f2539f2f06cb8481bbefc40e8d38943f.jpg)

![0ccf5c046ec4c9b1cc5bda7d19b97d746c16c1e6152dee5ce02e0a7cb7039b77.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/0ccf5c046ec4c9b1cc5bda7d19b97d746c16c1e6152dee5ce02e0a7cb7039b77.jpg)

![1212557101cbe9dbba00d8fba5346e0aa7a1d21fbcf4b49564d2bbf8bd113305.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/1212557101cbe9dbba00d8fba5346e0aa7a1d21fbcf4b49564d2bbf8bd113305.jpg)

![13868f2654c3ab49f6509e3a37a35fe48dfd7ea6705457a81824a66ff8a79878.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/13868f2654c3ab49f6509e3a37a35fe48dfd7ea6705457a81824a66ff8a79878.jpg)

![3ca89fdcfbea82c0e1272b70fdeb907294bec4f7a6ef21d4ee3a4caa52040ddf.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/3ca89fdcfbea82c0e1272b70fdeb907294bec4f7a6ef21d4ee3a4caa52040ddf.jpg)

![3ec1dc9af40ffb3c8f2c108c2bcc6b40c0d97cc39c5747e1d8ca8f8bb6d85938.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/3ec1dc9af40ffb3c8f2c108c2bcc6b40c0d97cc39c5747e1d8ca8f8bb6d85938.jpg)

![485118776d50c5bac92881199c20e7e8f2385d73acfd219bacd25004ddfe5724.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/485118776d50c5bac92881199c20e7e8f2385d73acfd219bacd25004ddfe5724.jpg)

![89a3280097931cb8affd683ebb625798635a1051418cf0f36e297cf51677809b.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/89a3280097931cb8affd683ebb625798635a1051418cf0f36e297cf51677809b.jpg)

![8ef6eb17e374abdec4c4dc998b72c351a8549faa5d472df6280183fdd06c15e8.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/8ef6eb17e374abdec4c4dc998b72c351a8549faa5d472df6280183fdd06c15e8.jpg)

![92808bc5ba9177ab188b27b115879380800dfd2f734b1dcef98db0783c1f8389.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/92808bc5ba9177ab188b27b115879380800dfd2f734b1dcef98db0783c1f8389.jpg)

![9d11402bde712acc1bbe59804ab812efb07e7e7fc865026114e574238089c218.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/9d11402bde712acc1bbe59804ab812efb07e7e7fc865026114e574238089c218.jpg)

![a3581e4d93e7b2226e681b0fb870774ff9ade9f0c6889e96e540240a79778296.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/a3581e4d93e7b2226e681b0fb870774ff9ade9f0c6889e96e540240a79778296.jpg)

![a9a0b076b072e5bbbd47707103d022b093f5b5498a539ba7f693cafc07f26376.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/a9a0b076b072e5bbbd47707103d022b093f5b5498a539ba7f693cafc07f26376.jpg)

![c9565b8ee49b3a42436c1b2dbc850895d521824a77e4c40e45e9d41cf8a6ac9f.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/c9565b8ee49b3a42436c1b2dbc850895d521824a77e4c40e45e9d41cf8a6ac9f.jpg)

![d358bf310edf20fcb0373e7732fdb06555b32628f0d53ccf88739b528a9fefbd.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/d358bf310edf20fcb0373e7732fdb06555b32628f0d53ccf88739b528a9fefbd.jpg)

![faede93b269703a929fe54ea5122f0ec17f6b7286cd2326e3953341136aa0268.jpg](../nips_results/4271_%24_boldsymbol%7B_lambda%7D%24-Orthogonality%20Regularization%20for%20Compatible%20Representation%20Learning/tables/faede93b269703a929fe54ea5122f0ec17f6b7286cd2326e3953341136aa0268.jpg)

## Statistical Analysis of the Sinkhorn Iterations for Two-Sample Schr\"{o}dinger Bridge Estimation


### Images

![3d991a7ac6627a45932fec24f82470d8264a0c4aab4ce7e8002fd8da6e38ad9a.jpg](../nips_results/4272_Statistical%20Analysis%20of%20the%20Sinkhorn%20Iterations%20for%20Two-Sample%20Schr__%7Bo%7Ddinger%20Bridge%20Estimation/images/3d991a7ac6627a45932fec24f82470d8264a0c4aab4ce7e8002fd8da6e38ad9a.jpg)

![8fe4a65e9e08d6ed0bf0965798eecb38c944481cc4166018ec8fb3e0a79a75cb.jpg](../nips_results/4272_Statistical%20Analysis%20of%20the%20Sinkhorn%20Iterations%20for%20Two-Sample%20Schr__%7Bo%7Ddinger%20Bridge%20Estimation/images/8fe4a65e9e08d6ed0bf0965798eecb38c944481cc4166018ec8fb3e0a79a75cb.jpg)

![a7455e23dc8a24cf65b9c62cbe3e78ecfd5894e456530959143c3d70b64ee9cd.jpg](../nips_results/4272_Statistical%20Analysis%20of%20the%20Sinkhorn%20Iterations%20for%20Two-Sample%20Schr__%7Bo%7Ddinger%20Bridge%20Estimation/images/a7455e23dc8a24cf65b9c62cbe3e78ecfd5894e456530959143c3d70b64ee9cd.jpg)

### Tables

![164f2796a00ac3faefad32b54533eb948b7efc4cc3cf3d5b44891a00021191ff.jpg](../nips_results/4272_Statistical%20Analysis%20of%20the%20Sinkhorn%20Iterations%20for%20Two-Sample%20Schr__%7Bo%7Ddinger%20Bridge%20Estimation/tables/164f2796a00ac3faefad32b54533eb948b7efc4cc3cf3d5b44891a00021191ff.jpg)

![e2889f8c449f80159ccba75e3623309154578fa4b1c1000d07637516e0a84fa4.jpg](../nips_results/4272_Statistical%20Analysis%20of%20the%20Sinkhorn%20Iterations%20for%20Two-Sample%20Schr__%7Bo%7Ddinger%20Bridge%20Estimation/tables/e2889f8c449f80159ccba75e3623309154578fa4b1c1000d07637516e0a84fa4.jpg)

## Frequency-Aware Token Reduction for Efficient Vision Transformer


### Images

![3dec34cb11c1d74d213ba948cc43a598140d06823b6a27d05964bd05b72f3e23.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/images/3dec34cb11c1d74d213ba948cc43a598140d06823b6a27d05964bd05b72f3e23.jpg)

![4ddbaf81cd3915dfe526b331689fa716bdb9a980ab26b5714a96c5f1ca3eec46.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/images/4ddbaf81cd3915dfe526b331689fa716bdb9a980ab26b5714a96c5f1ca3eec46.jpg)

![560eac44575e7297715e3d0bdc190e0218fe5b019364097ffcf6ef2370fc0daf.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/images/560eac44575e7297715e3d0bdc190e0218fe5b019364097ffcf6ef2370fc0daf.jpg)

![913a8e9412573f3114cdbf2b777070c7bd982b3625a59a2759b137a4d05177c3.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/images/913a8e9412573f3114cdbf2b777070c7bd982b3625a59a2759b137a4d05177c3.jpg)

![c4ad96d12b0d063652e7c775716f346cce4676eb378cb1b897898555b57178d6.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/images/c4ad96d12b0d063652e7c775716f346cce4676eb378cb1b897898555b57178d6.jpg)

![eb04ec31e6929a9fe2e0b020c013fe9dbdcd8b74fd170b4f58bc565cbba62953.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/images/eb04ec31e6929a9fe2e0b020c013fe9dbdcd8b74fd170b4f58bc565cbba62953.jpg)

![f65bf04e7c529abe8ecf471b9712a927bd0faabdcab676cb0db48fe389ddd7c6.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/images/f65bf04e7c529abe8ecf471b9712a927bd0faabdcab676cb0db48fe389ddd7c6.jpg)

### Tables

![8600e32c78ab786977a60fd2fe5216e4924c614dec546708099ca2dc25c9da3e.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/tables/8600e32c78ab786977a60fd2fe5216e4924c614dec546708099ca2dc25c9da3e.jpg)

![93e0c62731174e5d60e14c78b3ee4b1815c9d8976d0ef6eecc594417f3fa7fb0.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/tables/93e0c62731174e5d60e14c78b3ee4b1815c9d8976d0ef6eecc594417f3fa7fb0.jpg)

![ad17af0f97e1c2b315f9ed245b89f871b4b7f8e43fb2a60d75577eac71176256.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/tables/ad17af0f97e1c2b315f9ed245b89f871b4b7f8e43fb2a60d75577eac71176256.jpg)

![b5b17cc9b95c1f5853f31a39150827e1b1b740de9bf26f2eda0773a2fb4a8574.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/tables/b5b17cc9b95c1f5853f31a39150827e1b1b740de9bf26f2eda0773a2fb4a8574.jpg)

![be3bd53a2d9f9dfa197f2fa2aac430be3452fdf66d3ab5b1fdc41a088cebcc3f.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/tables/be3bd53a2d9f9dfa197f2fa2aac430be3452fdf66d3ab5b1fdc41a088cebcc3f.jpg)

![ce6e2f93c093e0393d961353bbdbf7ce8e43760437875868d19e04246dbe9b30.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/tables/ce6e2f93c093e0393d961353bbdbf7ce8e43760437875868d19e04246dbe9b30.jpg)

![d6f9d564e39614644fad33ce9f927f8d8cd86a3b849514709c82a0dec4c1105b.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/tables/d6f9d564e39614644fad33ce9f927f8d8cd86a3b849514709c82a0dec4c1105b.jpg)

![da7d6d8737d73808df77ae618e499bf2309b416198a6616cd26ce5e365e3bbcc.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/tables/da7d6d8737d73808df77ae618e499bf2309b416198a6616cd26ce5e365e3bbcc.jpg)

![e9c543e4650c400d983985f849bbf8aced1f1db102991a064392e725bdbb873c.jpg](../nips_results/4274_Frequency-Aware%20Token%20Reduction%20for%20Efficient%20Vision%20Transformer/tables/e9c543e4650c400d983985f849bbf8aced1f1db102991a064392e725bdbb873c.jpg)

## LLM at Network Edge: A Layer-wise Efficient Federated Fine-tuning Approach


### Images

![1c5f6fbaf0e8c1ea392afd371ed2f9b9961b3e8657bc0d17e45cba479846e530.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/images/1c5f6fbaf0e8c1ea392afd371ed2f9b9961b3e8657bc0d17e45cba479846e530.jpg)

![2c790b497e67ad77c70e57da815cd1a4c029a4e7314aa5bdf8fa62d4af91f6e7.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/images/2c790b497e67ad77c70e57da815cd1a4c029a4e7314aa5bdf8fa62d4af91f6e7.jpg)

![5b07728d1d7149dec4631257a8c9b47a1c16eb34f601d42829c01d1feca18963.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/images/5b07728d1d7149dec4631257a8c9b47a1c16eb34f601d42829c01d1feca18963.jpg)

![69853239c0694a0db412ebd7b95b83cfa681e9b42f914a864080b3924b34d738.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/images/69853239c0694a0db412ebd7b95b83cfa681e9b42f914a864080b3924b34d738.jpg)

![88928889147c364c91f75b037b5a64705019b07520adf4b1883cca0c768245b7.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/images/88928889147c364c91f75b037b5a64705019b07520adf4b1883cca0c768245b7.jpg)

![ab373244fdb54477cda8c439acce04299215adb7e6754522fe8784053bed0482.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/images/ab373244fdb54477cda8c439acce04299215adb7e6754522fe8784053bed0482.jpg)

![cacc3d931293cfb7bb487180702f03ce7eaaa361cce9835f5a5460eeb1bc3305.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/images/cacc3d931293cfb7bb487180702f03ce7eaaa361cce9835f5a5460eeb1bc3305.jpg)

![f576f7d995178415a698e35d9fcea5341345311f2a2d3891b0ee16b87b0f703e.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/images/f576f7d995178415a698e35d9fcea5341345311f2a2d3891b0ee16b87b0f703e.jpg)

### Tables

![0a959c60700f6b310e2a25d17e66921a5a3c9b7f77adc908e5e211d928508bdd.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/tables/0a959c60700f6b310e2a25d17e66921a5a3c9b7f77adc908e5e211d928508bdd.jpg)

![4888047eebdfab56266b7b9806424f5307713abc57e773d78377beb67b314eec.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/tables/4888047eebdfab56266b7b9806424f5307713abc57e773d78377beb67b314eec.jpg)

![6f9fd507d8d1f44e952446ae524b5ba88087174e05dd01589b31dfa384960657.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/tables/6f9fd507d8d1f44e952446ae524b5ba88087174e05dd01589b31dfa384960657.jpg)

![8a281173faf70cce1e95c25d05413de881caddc3f77e494a4524e102d1e2eac0.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/tables/8a281173faf70cce1e95c25d05413de881caddc3f77e494a4524e102d1e2eac0.jpg)

![9a4d2c71102debc32a282c61f106ba2e0d12e240856b36aca0d10e1005ad59f9.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/tables/9a4d2c71102debc32a282c61f106ba2e0d12e240856b36aca0d10e1005ad59f9.jpg)

![c68242c87e9b7d8710453134e86988eeab5227f52a4336e9991f6d7c66c0c51b.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/tables/c68242c87e9b7d8710453134e86988eeab5227f52a4336e9991f6d7c66c0c51b.jpg)

![f4fc47c86af4d0c9c32dc9b3e75a0b227d80d3becdf770f72f68a9ca3dd5e803.jpg](../nips_results/4275_LLM%20at%20Network%20Edge_%20A%20Layer-wise%20Efficient%20Federated%20Fine-tuning%20Approach/tables/f4fc47c86af4d0c9c32dc9b3e75a0b227d80d3becdf770f72f68a9ca3dd5e803.jpg)

## Machine Unlearning under Overparameterization


### Images

![0e441412d3b21db55bbeba67eac573526e052928b09b31828ec82edeb1fc6b03.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/0e441412d3b21db55bbeba67eac573526e052928b09b31828ec82edeb1fc6b03.jpg)

![10fdd0f7a001612cd907d48da64157dd050fedef7a3fc91e54c832ca6521da18.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/10fdd0f7a001612cd907d48da64157dd050fedef7a3fc91e54c832ca6521da18.jpg)

![2fe2637936c99fc9de1b463516d56b33552022925c72419819195ef338ae4396.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/2fe2637936c99fc9de1b463516d56b33552022925c72419819195ef338ae4396.jpg)

![379d7e7650d668d997ab10b549d1ef277855045b917546b06d992b607c195d0e.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/379d7e7650d668d997ab10b549d1ef277855045b917546b06d992b607c195d0e.jpg)

![3ac8e96f6044631235c8ff05851e0fb89fabf17e753b589516d3a2e8eb2a0bea.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/3ac8e96f6044631235c8ff05851e0fb89fabf17e753b589516d3a2e8eb2a0bea.jpg)

![4c26b4f395363ac2e50a559796805765c3f3833171d58ade44776b30010a5600.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/4c26b4f395363ac2e50a559796805765c3f3833171d58ade44776b30010a5600.jpg)

![532c2109072abcaa8db4017d7d80696e75d425de210638b16e8ac2401a0c6833.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/532c2109072abcaa8db4017d7d80696e75d425de210638b16e8ac2401a0c6833.jpg)

![7703c20c7cef7859d89621b67531d32193cfcfa7cbc1f793280839ca0f01f45e.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/7703c20c7cef7859d89621b67531d32193cfcfa7cbc1f793280839ca0f01f45e.jpg)

![880d0c4b44813b68ad6f2a135f0c07897bae1c3295381941ec216808394dacc9.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/880d0c4b44813b68ad6f2a135f0c07897bae1c3295381941ec216808394dacc9.jpg)

![8e185181ed3a2f3dcc9b1cad684d179261166ef670155a7d9d2bae8904f59637.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/8e185181ed3a2f3dcc9b1cad684d179261166ef670155a7d9d2bae8904f59637.jpg)

![b6bef881cdc6d087b6a396fa263cb70312cb8068332ee9c07ce11e51f7c8cc6d.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/b6bef881cdc6d087b6a396fa263cb70312cb8068332ee9c07ce11e51f7c8cc6d.jpg)

![ca55295a99a2c6660edc22b9046297b93a4bdc69491c07381750b93c8a67f587.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/ca55295a99a2c6660edc22b9046297b93a4bdc69491c07381750b93c8a67f587.jpg)

![d1232317b45053cb4066b82fdf17bbc826442327a27dd03170a1930f47a79a20.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/d1232317b45053cb4066b82fdf17bbc826442327a27dd03170a1930f47a79a20.jpg)

![db8ddd478fea7a6378cbc7f69f8343981d2d5cdf6541022534ac05396ff4f00c.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/images/db8ddd478fea7a6378cbc7f69f8343981d2d5cdf6541022534ac05396ff4f00c.jpg)

### Tables

![03999f54230694443e13310961b6fcc8832cdfd382e52a3b01f3e1b88f3831c5.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/03999f54230694443e13310961b6fcc8832cdfd382e52a3b01f3e1b88f3831c5.jpg)

![111554f7fa4ed35b4497cb61ed185258bc68f42e232b4116056bcdf0f9746b73.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/111554f7fa4ed35b4497cb61ed185258bc68f42e232b4116056bcdf0f9746b73.jpg)

![18cc39ac09a1339a62dfdf8fe076583ca5f113be0b2550f1861ba6b50e630994.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/18cc39ac09a1339a62dfdf8fe076583ca5f113be0b2550f1861ba6b50e630994.jpg)

![257d55d9f7309ad32ba68d806f95ec9b416286373faf99722bb0bbb5abc5a6e3.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/257d55d9f7309ad32ba68d806f95ec9b416286373faf99722bb0bbb5abc5a6e3.jpg)

![275be35375065dbf9a29974c90c14febee935bd86e47dba9624d0f57dd271636.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/275be35375065dbf9a29974c90c14febee935bd86e47dba9624d0f57dd271636.jpg)

![34ea3c5696e421e9e233ac9935475277434888d0152a3f98cfb64cd6299acb24.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/34ea3c5696e421e9e233ac9935475277434888d0152a3f98cfb64cd6299acb24.jpg)

![3507a51e10f58840290e1bad3236f0766b4bd8eb11f9daab104ef21e421dcc9b.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/3507a51e10f58840290e1bad3236f0766b4bd8eb11f9daab104ef21e421dcc9b.jpg)

![3f452822cf5d1b361ad75b37ff38a0fd3ade5c9a2b247f112aa2c5f7cfb9f8fc.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/3f452822cf5d1b361ad75b37ff38a0fd3ade5c9a2b247f112aa2c5f7cfb9f8fc.jpg)

![6da0135b8d690727ed169ce59b57764bc05cb1b04d4d88294caf8fb702fb507c.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/6da0135b8d690727ed169ce59b57764bc05cb1b04d4d88294caf8fb702fb507c.jpg)

![8935ed7c56a4b0fba49a45cd86905a7a1f2f767b8319daf698c837a9c2c0f6ff.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/8935ed7c56a4b0fba49a45cd86905a7a1f2f767b8319daf698c837a9c2c0f6ff.jpg)

![8e01d4628c4ed60138cd553163eeb354fbe414c369a10bfb850d6bd09093f5e7.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/8e01d4628c4ed60138cd553163eeb354fbe414c369a10bfb850d6bd09093f5e7.jpg)

![9838f2ca79f4ae8388183988fd562335c0f9cc0f7d2ef138eedc3bdf26e0ed3e.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/9838f2ca79f4ae8388183988fd562335c0f9cc0f7d2ef138eedc3bdf26e0ed3e.jpg)

![998ae5157644edacfd1583d345474ee2dde2dd7793472abe02d96c60869b4ca7.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/998ae5157644edacfd1583d345474ee2dde2dd7793472abe02d96c60869b4ca7.jpg)

![9ac074576fe96435cf31be2d217d959dd69e0169eec3fc956fad8ef26ad1463b.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/9ac074576fe96435cf31be2d217d959dd69e0169eec3fc956fad8ef26ad1463b.jpg)

![aba17aa1389fc7c7fe853ef66cc4df1c5eb72138ed8a03dc58b294d85b6dd64f.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/aba17aa1389fc7c7fe853ef66cc4df1c5eb72138ed8a03dc58b294d85b6dd64f.jpg)

![c0e1eae34fea8030b067f456de8453d18d779129f39c1976ac284db1eed1cec7.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/c0e1eae34fea8030b067f456de8453d18d779129f39c1976ac284db1eed1cec7.jpg)

![d8f4da0d9b937486a93ac4424892c2617c69af9a7b986da1024dbb17a77e598d.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/d8f4da0d9b937486a93ac4424892c2617c69af9a7b986da1024dbb17a77e598d.jpg)

![e53fddfdb5c8c989d6451c690f0b7321c433a2daf34d3af48f3858138ae94d15.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/e53fddfdb5c8c989d6451c690f0b7321c433a2daf34d3af48f3858138ae94d15.jpg)

![e5a17e5511ab6b3c36e00eb5fcc86c40b4ff1d19bd7ad138deb246f0c134ba4c.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/e5a17e5511ab6b3c36e00eb5fcc86c40b4ff1d19bd7ad138deb246f0c134ba4c.jpg)

![e5cfe063848a7ce1024c873d20a576854dd650c45bacebc0aa4e9d05af75030c.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/e5cfe063848a7ce1024c873d20a576854dd650c45bacebc0aa4e9d05af75030c.jpg)

![f067461f3e3336f314eed6ea2a33872498348a60d60a6519cb766e4c961dec4d.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/f067461f3e3336f314eed6ea2a33872498348a60d60a6519cb766e4c961dec4d.jpg)

![f7a1b54bad30e061690e2a2341ad65b1e1bf10e81877699a332c1938b62eb69b.jpg](../nips_results/4276_Machine%20Unlearning%20under%20Overparameterization/tables/f7a1b54bad30e061690e2a2341ad65b1e1bf10e81877699a332c1938b62eb69b.jpg)

## R2R: Efficiently Navigating Divergent Reasoning Paths with Small-Large Model Token Routing


### Images

![017fe362579024fa60de01e8ea6dc7668a6dda071c98d0b3779542be9f9ab73e.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/images/017fe362579024fa60de01e8ea6dc7668a6dda071c98d0b3779542be9f9ab73e.jpg)

![209d9ef2d5ed16443aae24e634ecc6c0d7ecf5633869759b016ee4669a0a06ca.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/images/209d9ef2d5ed16443aae24e634ecc6c0d7ecf5633869759b016ee4669a0a06ca.jpg)

![5a1cee4cce8e3781c6229a107fee59364aab61377efe29b3d22deee6b0a0dd42.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/images/5a1cee4cce8e3781c6229a107fee59364aab61377efe29b3d22deee6b0a0dd42.jpg)

![5d0575c6078006199b553bfa026a727af722473c8d00cb5595bee12114e97ea9.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/images/5d0575c6078006199b553bfa026a727af722473c8d00cb5595bee12114e97ea9.jpg)

![69a528c7a87b3df8a4a398942df4eea797830909b5c8dadb9e6146698125ae22.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/images/69a528c7a87b3df8a4a398942df4eea797830909b5c8dadb9e6146698125ae22.jpg)

![6f9280f056e9ae9158b2dcaa6b321a5be298fc97d1d94c166e9bd24f15269fff.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/images/6f9280f056e9ae9158b2dcaa6b321a5be298fc97d1d94c166e9bd24f15269fff.jpg)

![81f651d3943ab1c2a9405727295ad8eacc382b6247108236ffabdb7a3854adbc.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/images/81f651d3943ab1c2a9405727295ad8eacc382b6247108236ffabdb7a3854adbc.jpg)

![86ceef9b13150abcb0eeb6e4c2f12e36f6722693173442686859c08a102fab43.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/images/86ceef9b13150abcb0eeb6e4c2f12e36f6722693173442686859c08a102fab43.jpg)

![9fb120b810197dace5a16646f0d2ff06a9c8e6a762671d1eafc34347178e3705.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/images/9fb120b810197dace5a16646f0d2ff06a9c8e6a762671d1eafc34347178e3705.jpg)

![c119b0969ea1fb14693e850c6f93ad8fe2b61d20d2b8507b46a91a9899f10630.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/images/c119b0969ea1fb14693e850c6f93ad8fe2b61d20d2b8507b46a91a9899f10630.jpg)

![d090369eabd710434db469fccbc884ab15fe9433837b217cab6febf8b306b60b.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/images/d090369eabd710434db469fccbc884ab15fe9433837b217cab6febf8b306b60b.jpg)

### Tables

![002c4038b9299ad01b0c67a79d0ca10a278ab96075caa2c650b1cdfd78b5b4cd.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/002c4038b9299ad01b0c67a79d0ca10a278ab96075caa2c650b1cdfd78b5b4cd.jpg)

![1dc01b0c13203cf66e24ecd44bc732abb19a563819883e18c5bc94dc739d4aba.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/1dc01b0c13203cf66e24ecd44bc732abb19a563819883e18c5bc94dc739d4aba.jpg)

![348da84bab80b15beede4139452126f86335f873f92de4c3b1b7b7f959823243.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/348da84bab80b15beede4139452126f86335f873f92de4c3b1b7b7f959823243.jpg)

![3e8ecba809f0e6f9667efd0d378d1bb33d77f30532cf1bf6168e4019294ff8a2.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/3e8ecba809f0e6f9667efd0d378d1bb33d77f30532cf1bf6168e4019294ff8a2.jpg)

![5363bb8a6ac58a82861819a96556e06f4fa496b00d314bf2f69b066878d08bce.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/5363bb8a6ac58a82861819a96556e06f4fa496b00d314bf2f69b066878d08bce.jpg)

![5887ac7b0c72937a05e0eda0da7a69d690425d6cd03739b8cb30b95522346a73.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/5887ac7b0c72937a05e0eda0da7a69d690425d6cd03739b8cb30b95522346a73.jpg)

![7076f097a46228f6653e17daa548e6cbb556dccef90e83dd9be961e7bb0c4158.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/7076f097a46228f6653e17daa548e6cbb556dccef90e83dd9be961e7bb0c4158.jpg)

![7b6d6c9af86112d15250abd207f8f54b7957c4da305f88355d6a1b96d2ba9a80.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/7b6d6c9af86112d15250abd207f8f54b7957c4da305f88355d6a1b96d2ba9a80.jpg)

![91024bc6527a9100602311fed6eab4b80417bb6e70477b48672fe016d830f6d8.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/91024bc6527a9100602311fed6eab4b80417bb6e70477b48672fe016d830f6d8.jpg)

![92bae551d15abba7bc6a1b3dbd555b1d85cee23c64ddbc28093a534cb0bca705.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/92bae551d15abba7bc6a1b3dbd555b1d85cee23c64ddbc28093a534cb0bca705.jpg)

![9fd20b86f88a95626e3b81066ed1d44fffe8befda261efebab10d814a4b59131.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/9fd20b86f88a95626e3b81066ed1d44fffe8befda261efebab10d814a4b59131.jpg)

![a9911c544cbf8972ccd2f3f8ee7608bf2190ed82f6c5749ca5bb441bebbea1c7.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/a9911c544cbf8972ccd2f3f8ee7608bf2190ed82f6c5749ca5bb441bebbea1c7.jpg)

![aa380fea1467b19039d3bad5e3e0469a6bcbef2a0a0185f21204992612403d18.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/aa380fea1467b19039d3bad5e3e0469a6bcbef2a0a0185f21204992612403d18.jpg)

![c470205c7e83e429edec138132868dbd5b07d0347af71823bf318ee7241d696c.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/c470205c7e83e429edec138132868dbd5b07d0347af71823bf318ee7241d696c.jpg)

![ccbbb791e8d7532738fb8db42add883bd6009d1946e7966c38042e06ee7e1fff.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/ccbbb791e8d7532738fb8db42add883bd6009d1946e7966c38042e06ee7e1fff.jpg)

![e8073cbbbfd3a6aafc9cf3eb99a24feab89c9d07a62f36da52974d2484208708.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/e8073cbbbfd3a6aafc9cf3eb99a24feab89c9d07a62f36da52974d2484208708.jpg)

![ec24d02e7d8e949c0e912805a2f30ba2668098151a8191ba2cc35c7ae9735e61.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/ec24d02e7d8e949c0e912805a2f30ba2668098151a8191ba2cc35c7ae9735e61.jpg)

![f5a2048f8313c617aee515cc321d70348a18b444a90ba7e3bca53f8b311b401b.jpg](../nips_results/4277_R2R_%20Efficiently%20Navigating%20Divergent%20Reasoning%20Paths%20with%20Small-Large%20Model%20Token%20Routing/tables/f5a2048f8313c617aee515cc321d70348a18b444a90ba7e3bca53f8b311b401b.jpg)

## WALL-E: World Alignment by NeuroSymbolic Learning improves World Model-based LLM Agents


### Images

![00bd31141fd48af33e06eb09141ad4bb763f9de6dcccd6dc424c4f31201bbb55.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/images/00bd31141fd48af33e06eb09141ad4bb763f9de6dcccd6dc424c4f31201bbb55.jpg)

![2cffd2696a4f5263d5226a090ebf54f17c7e95372976b1132a14f18289725853.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/images/2cffd2696a4f5263d5226a090ebf54f17c7e95372976b1132a14f18289725853.jpg)

![59d91928d91e73bf1485629606aa470d3ef3bb7d5a440481873255b58a4f0466.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/images/59d91928d91e73bf1485629606aa470d3ef3bb7d5a440481873255b58a4f0466.jpg)

![5eb459d9148335679b40beb2d8dff91ae66cc94b6d092e62d95eaec9b40ede4a.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/images/5eb459d9148335679b40beb2d8dff91ae66cc94b6d092e62d95eaec9b40ede4a.jpg)

![81e8a03d6766efa98bedfc59240a6a6d93f13d913bfac9d0bd7be2d0a28f23bc.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/images/81e8a03d6766efa98bedfc59240a6a6d93f13d913bfac9d0bd7be2d0a28f23bc.jpg)

![abdc5a12aef823af9ea138e6c10800ec09aaf6516e49c767d64c24791fa76f67.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/images/abdc5a12aef823af9ea138e6c10800ec09aaf6516e49c767d64c24791fa76f67.jpg)

![cbaead2608480815aed5d5e50c7942ce50a34e3e891a8a8fd4d1df3352f97821.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/images/cbaead2608480815aed5d5e50c7942ce50a34e3e891a8a8fd4d1df3352f97821.jpg)

![cc625717cdb7f2df861bccdf2cd6faf3ef44b220e28c618a2b20555f60b8bf23.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/images/cc625717cdb7f2df861bccdf2cd6faf3ef44b220e28c618a2b20555f60b8bf23.jpg)

### Tables

![0529901162c95b0baa76aec298bc72e21083acb43113f5df4b20f4f8b3c68c7f.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/tables/0529901162c95b0baa76aec298bc72e21083acb43113f5df4b20f4f8b3c68c7f.jpg)

![0cd4fefe649df82c6dc96eb853425d8790860eebc09ad994f281e21ff0679928.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/tables/0cd4fefe649df82c6dc96eb853425d8790860eebc09ad994f281e21ff0679928.jpg)

![173ae392dd461e1d72f91db4d3b9df2cb7bc8996a89336f0b2d0134cf64388de.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/tables/173ae392dd461e1d72f91db4d3b9df2cb7bc8996a89336f0b2d0134cf64388de.jpg)

![207e921a2fbc360a56ec3727f59b7a804c30a504bf8a07438000f5afac37ce4f.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/tables/207e921a2fbc360a56ec3727f59b7a804c30a504bf8a07438000f5afac37ce4f.jpg)

![22bc0df503dcc7d90347570bf4bcc7021c35518e69a25f4cefc37fb09d75a631.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/tables/22bc0df503dcc7d90347570bf4bcc7021c35518e69a25f4cefc37fb09d75a631.jpg)

![582060c9f26ba546a8f234d3888810f49a2ece0a05e20c3bd0f7fc1b8f5e2475.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/tables/582060c9f26ba546a8f234d3888810f49a2ece0a05e20c3bd0f7fc1b8f5e2475.jpg)

![8134b2783661ff49b93b2ec2a50df95abba1e0f2b90cd17bcaea625c5c6039ef.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/tables/8134b2783661ff49b93b2ec2a50df95abba1e0f2b90cd17bcaea625c5c6039ef.jpg)

![ceedd33c4c25170ebd3e26023ae622e1ba02bf36e3a743e17aef381c5cb26064.jpg](../nips_results/4278_WALL-E_%20World%20Alignment%20by%20NeuroSymbolic%20Learning%20improves%20World%20Model-based%20LLM%20Agents/tables/ceedd33c4c25170ebd3e26023ae622e1ba02bf36e3a743e17aef381c5cb26064.jpg)

## Gaussian Regression-Driven Tensorized Incomplete Multi-View Clustering with Dual Manifold Regularization


### Images

![171e15d317bfb722b540a55d5eafaddb563448fb58b673b86e6a9c16e9c0babc.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/images/171e15d317bfb722b540a55d5eafaddb563448fb58b673b86e6a9c16e9c0babc.jpg)

![3c35e4a360f4018f0ca24b4a8911c01ee9cc5961c0e3caac794cabd8a60c2549.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/images/3c35e4a360f4018f0ca24b4a8911c01ee9cc5961c0e3caac794cabd8a60c2549.jpg)

![4cbde68300aa5d40d6f94248e49ceaea1c074767dde8d6a0e8d5cda17feb0fd9.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/images/4cbde68300aa5d40d6f94248e49ceaea1c074767dde8d6a0e8d5cda17feb0fd9.jpg)

![5e7d19fe5d262525fe8f2ab39fa978046d44363cfb020888da14a19ea132ae30.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/images/5e7d19fe5d262525fe8f2ab39fa978046d44363cfb020888da14a19ea132ae30.jpg)

![72cb7f6c368f344814c36fc99c6f112c44d05ab4f7a4d884561ff3364532c52c.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/images/72cb7f6c368f344814c36fc99c6f112c44d05ab4f7a4d884561ff3364532c52c.jpg)

![8445c871fc91449a674142cd01a733a49d99d150a0c80d46789eed610e2a3a5f.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/images/8445c871fc91449a674142cd01a733a49d99d150a0c80d46789eed610e2a3a5f.jpg)

![849c043469df558484591cc613489fdda3b39d0fb2fca89d3fd48888f9f0a356.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/images/849c043469df558484591cc613489fdda3b39d0fb2fca89d3fd48888f9f0a356.jpg)

![ab3701375cccb6573590a5d79cebbd0c6f76ca4c5ad58416cecb9d2bdd0d3e85.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/images/ab3701375cccb6573590a5d79cebbd0c6f76ca4c5ad58416cecb9d2bdd0d3e85.jpg)

![b1c68c02f2fe4b5adfed600d1c5692ab5e44c269312ef7073c54095c2a352ce7.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/images/b1c68c02f2fe4b5adfed600d1c5692ab5e44c269312ef7073c54095c2a352ce7.jpg)

### Tables

![2bfc508f1ff5a58da664edabe3248f0c8e086fe16c65f770864befefeb839a56.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/tables/2bfc508f1ff5a58da664edabe3248f0c8e086fe16c65f770864befefeb839a56.jpg)

![567007cfe8a4ddc8d2330109a0251f6acc7326136d8603ae0a253be598189ccc.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/tables/567007cfe8a4ddc8d2330109a0251f6acc7326136d8603ae0a253be598189ccc.jpg)

![e243207bbcd4354e1158fae3dd4ddf4fb8dead728fe617579924f646aff06adc.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/tables/e243207bbcd4354e1158fae3dd4ddf4fb8dead728fe617579924f646aff06adc.jpg)

![e7d85abe4b11c07f6d70913ab7fe5544e14addf4b24e7b7419e6bd778cfcc24e.jpg](../nips_results/4279_Gaussian%20Regression-Driven%20Tensorized%20Incomplete%20Multi-View%20Clustering%20with%20Dual%20Manifold%20Regulariza/tables/e7d85abe4b11c07f6d70913ab7fe5544e14addf4b24e7b7419e6bd778cfcc24e.jpg)

## Fair Matroid Selection


### Tables

![3696ddcce28aecd48c6921edb83b34d16c25b1f70621d6fbd63c89588f5d8e9c.jpg](../nips_results/4280_Fair%20Matroid%20Selection/tables/3696ddcce28aecd48c6921edb83b34d16c25b1f70621d6fbd63c89588f5d8e9c.jpg)

## Dependency Matters: Enhancing LLM Reasoning with Explicit Knowledge Grounding


### Images

![053f707cd9cb6005e12437cb069993f65376345ee12b444c4ce84114f8a79f35.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/images/053f707cd9cb6005e12437cb069993f65376345ee12b444c4ce84114f8a79f35.jpg)

![44c6845d79bd4b6901a4e56e1f37a27238753b908b1e4d5d4c2318ad0de25cda.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/images/44c6845d79bd4b6901a4e56e1f37a27238753b908b1e4d5d4c2318ad0de25cda.jpg)

![47a28733573e26d684ce713ab74bb4ac32fa268ecb940063ebc31259a81a8a6e.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/images/47a28733573e26d684ce713ab74bb4ac32fa268ecb940063ebc31259a81a8a6e.jpg)

![600ef70068b7544fa5bdd9728f97975e3c8b93880c14061ad7283b89a95b05dc.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/images/600ef70068b7544fa5bdd9728f97975e3c8b93880c14061ad7283b89a95b05dc.jpg)

![6a7a5f6b508504838f3849cc558c64bf51a11bacf0989fc9a7f1a18a52df7f52.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/images/6a7a5f6b508504838f3849cc558c64bf51a11bacf0989fc9a7f1a18a52df7f52.jpg)

![8081d83312a05f90c2b544fa9822611cd654103608bbeed5283f29ed796a32aa.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/images/8081d83312a05f90c2b544fa9822611cd654103608bbeed5283f29ed796a32aa.jpg)

![93ffa9d77ba421f8f33da756b82d69e26d450e149b0ee3b6063da8dd06a5572c.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/images/93ffa9d77ba421f8f33da756b82d69e26d450e149b0ee3b6063da8dd06a5572c.jpg)

![9dc7bed9eb27c27c9abda9013341f16116510f4d3c568a8cc0440d2b3ba29c0d.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/images/9dc7bed9eb27c27c9abda9013341f16116510f4d3c568a8cc0440d2b3ba29c0d.jpg)

![d4b6b1c1f81add3c16003e44f86fff772d88414f058641f9db04be0471b70de1.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/images/d4b6b1c1f81add3c16003e44f86fff772d88414f058641f9db04be0471b70de1.jpg)

### Tables

![25665f160e5abf2eefc59af25c0604998b106c808237b6859e029e4e0ebf4679.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/25665f160e5abf2eefc59af25c0604998b106c808237b6859e029e4e0ebf4679.jpg)

![259d2821cc690ba412a45299331708d3f84084cdd41eeca1b0fe4a51f7d8e072.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/259d2821cc690ba412a45299331708d3f84084cdd41eeca1b0fe4a51f7d8e072.jpg)

![36123368c2d6c587c332d2c29a77bc4faa7cb6456346137f61ae8df63b732b17.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/36123368c2d6c587c332d2c29a77bc4faa7cb6456346137f61ae8df63b732b17.jpg)

![39ad5ddd8e37fba581bfe78c2e9ad8a2cf9ede355a8e021e9b875febac6568a9.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/39ad5ddd8e37fba581bfe78c2e9ad8a2cf9ede355a8e021e9b875febac6568a9.jpg)

![3f6a6b32f18805c58466be24487b31d429c621546e98facdeaa706aafe4d0044.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/3f6a6b32f18805c58466be24487b31d429c621546e98facdeaa706aafe4d0044.jpg)

![4e75dedf64375224527a6f4a90d2bb8543937cdf3e79edac5206bfd16b1ebfb8.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/4e75dedf64375224527a6f4a90d2bb8543937cdf3e79edac5206bfd16b1ebfb8.jpg)

![5571ee14c30f1244e183642b13b4b5c221ad8beff270af2a783d772335058a67.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/5571ee14c30f1244e183642b13b4b5c221ad8beff270af2a783d772335058a67.jpg)

![6fb20c858242e2940ed4458d251f8f2bf46198aadf03e53b3252ab0306d97ed8.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/6fb20c858242e2940ed4458d251f8f2bf46198aadf03e53b3252ab0306d97ed8.jpg)

![6fd3b6c024a93af182ae3c117a36ae4a61183e29f28362dba0b9b4a904d889dd.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/6fd3b6c024a93af182ae3c117a36ae4a61183e29f28362dba0b9b4a904d889dd.jpg)

![7e44725c8b2c8857d275ed075854d8c05ebbab8e11b6a004baf7b5bea1ea501b.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/7e44725c8b2c8857d275ed075854d8c05ebbab8e11b6a004baf7b5bea1ea501b.jpg)

![ccbd8a66057d55aadfa12b85ba4015b8cb0177828ae1c1aa792e017f74258d0b.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/ccbd8a66057d55aadfa12b85ba4015b8cb0177828ae1c1aa792e017f74258d0b.jpg)

![cde2be0b9bb39da07b7fac241159f445b3ac080273fbc3ed7297c568dc8280de.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/cde2be0b9bb39da07b7fac241159f445b3ac080273fbc3ed7297c568dc8280de.jpg)

![cfa71f8cac295a0c0452e42307fe301a0d4084b10861ffb6ac39e5997199152f.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/cfa71f8cac295a0c0452e42307fe301a0d4084b10861ffb6ac39e5997199152f.jpg)

![d5d35378b453bc3a479a3914e93714a1b88759542ac395887ec91777ac5aaf3c.jpg](../nips_results/4281_Dependency%20Matters_%20Enhancing%20LLM%20Reasoning%20with%20Explicit%20Knowledge%20Grounding/tables/d5d35378b453bc3a479a3914e93714a1b88759542ac395887ec91777ac5aaf3c.jpg)

## Schrödinger Bridge Matching for Tree-Structured Costs and Entropic Wasserstein Barycentres


### Images

![0722414781b17dfd73e163079723914729401d15d7955756f3a0709e816f4598.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/images/0722414781b17dfd73e163079723914729401d15d7955756f3a0709e816f4598.jpg)

![0c60ef6b9d06001a29bcd0fd6ffdd07edb3e7cb9b2bb65fee92d87473d2b6f1a.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/images/0c60ef6b9d06001a29bcd0fd6ffdd07edb3e7cb9b2bb65fee92d87473d2b6f1a.jpg)

![0ca78d2a3e0a27b15086e5a66ad2548f0893e1ea5a2e313873b2b6bdb9b3427f.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/images/0ca78d2a3e0a27b15086e5a66ad2548f0893e1ea5a2e313873b2b6bdb9b3427f.jpg)

![2c5d70289e07842445a8185943c5eee4ccfb30e6ffd8bb7aa6df4342aa38870c.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/images/2c5d70289e07842445a8185943c5eee4ccfb30e6ffd8bb7aa6df4342aa38870c.jpg)

![4407464fbaa2f395ed8f5f4d387841d949a0cf4b9384ab285162050cf156c61a.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/images/4407464fbaa2f395ed8f5f4d387841d949a0cf4b9384ab285162050cf156c61a.jpg)

![715c378909da6a736304c3ba54d6d70a8079f7da9287dc02d753e8cd61344cca.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/images/715c378909da6a736304c3ba54d6d70a8079f7da9287dc02d753e8cd61344cca.jpg)

![a36e6abfbbbcc36f149658a96e04dffbdc4e7027b052c9c27ec20c2428a4fcf2.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/images/a36e6abfbbbcc36f149658a96e04dffbdc4e7027b052c9c27ec20c2428a4fcf2.jpg)

![a3c35b4c46704d6e8caca6e01790a39527221c5e6af16e7a9cbdfb7e910ef0b8.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/images/a3c35b4c46704d6e8caca6e01790a39527221c5e6af16e7a9cbdfb7e910ef0b8.jpg)

![b1ebc060763f914a5c0bf6fac62d32302ff8aa43725e4f3529f2922b8994ac6a.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/images/b1ebc060763f914a5c0bf6fac62d32302ff8aa43725e4f3529f2922b8994ac6a.jpg)

![bfd03f48ecd961234a61d78816bf96a29404be5d408315b92a551b88f9dfc1ee.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/images/bfd03f48ecd961234a61d78816bf96a29404be5d408315b92a551b88f9dfc1ee.jpg)

![e770e3e4433ce50d3c53ba6631136526dbdbb824ea2f53a406064f870718cdf9.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/images/e770e3e4433ce50d3c53ba6631136526dbdbb824ea2f53a406064f870718cdf9.jpg)

### Tables

![159c1dabfcc2dcbcbdf0bde0f724f8d156768be982d81dc9166ee3a6f2fedbab.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/tables/159c1dabfcc2dcbcbdf0bde0f724f8d156768be982d81dc9166ee3a6f2fedbab.jpg)

![24566ac0ce1b90d09244a09a31f145f47ea50b5af6e89ac34a77536cfd8d9d67.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/tables/24566ac0ce1b90d09244a09a31f145f47ea50b5af6e89ac34a77536cfd8d9d67.jpg)

![2f98c3c037afba96031acc184f213184f0e32406302bddbde0a5efd4b0470854.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/tables/2f98c3c037afba96031acc184f213184f0e32406302bddbde0a5efd4b0470854.jpg)

![42851686b973083a50cc8877099c58e8f4ff0584e2b0caa93441342b63454a33.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/tables/42851686b973083a50cc8877099c58e8f4ff0584e2b0caa93441342b63454a33.jpg)

![66360e0370ba17fe388a1d753dbd6c5b92b20b1da7903d046e02a152ea9cacfc.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/tables/66360e0370ba17fe388a1d753dbd6c5b92b20b1da7903d046e02a152ea9cacfc.jpg)

![6c17188a8dc7f8697308bb00087ea0ab56f9ca2ec5106f6de1b4b202912fc9f8.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/tables/6c17188a8dc7f8697308bb00087ea0ab56f9ca2ec5106f6de1b4b202912fc9f8.jpg)

![6db5d74bb089839fb9f37fdd67c0c83e9f03169efc7a07b52dfeb31f9a1bdac6.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/tables/6db5d74bb089839fb9f37fdd67c0c83e9f03169efc7a07b52dfeb31f9a1bdac6.jpg)

![a42991c3b2c65334b73c125d4362cf4de43b9cd6be37dfcb30c4a9dc216a1ac9.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/tables/a42991c3b2c65334b73c125d4362cf4de43b9cd6be37dfcb30c4a9dc216a1ac9.jpg)

![c8cf062b953cfa7d045192b8e5dc4f5750abbf5de337289a6b18a3fc55692f87.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/tables/c8cf062b953cfa7d045192b8e5dc4f5750abbf5de337289a6b18a3fc55692f87.jpg)

![d51875b4dde19cbe3ea47bce8644d1a238b1c953e64d383310ba90ae48fe1afd.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/tables/d51875b4dde19cbe3ea47bce8644d1a238b1c953e64d383310ba90ae48fe1afd.jpg)

![d8a946a8faef4db79b0f50be05cdba83ff8f97f7baa5c4090359b92d3211c90f.jpg](../nips_results/4282_Schr%C3%B6dinger%20Bridge%20Matching%20for%20Tree-Structured%20Costs%20and%20Entropic%20Wasserstein%20Barycentres/tables/d8a946a8faef4db79b0f50be05cdba83ff8f97f7baa5c4090359b92d3211c90f.jpg)

## Quantifying Elicitation of Latent Capabilities in Language Models


### Images

![02d699377f1608bd4c43bed7058f45f9d36bfe36771a38563c032b5f3e6d3dfc.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/02d699377f1608bd4c43bed7058f45f9d36bfe36771a38563c032b5f3e6d3dfc.jpg)

![0c8a82b80f1e86b20386d80954e10e32baece8583819e5696209fefde9ba1afa.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/0c8a82b80f1e86b20386d80954e10e32baece8583819e5696209fefde9ba1afa.jpg)

![2052448feb14e580a77e1f40c2463c1860887e821f26a31098804e010fdf389e.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/2052448feb14e580a77e1f40c2463c1860887e821f26a31098804e010fdf389e.jpg)

![2ec5f8c81fad45daf5f094137098edf490efc6601db66417d9a1c60f2032385d.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/2ec5f8c81fad45daf5f094137098edf490efc6601db66417d9a1c60f2032385d.jpg)

![31d85e6dd264f4ac1d03bf60282379076decbda068269ce582532038c1f1a4a5.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/31d85e6dd264f4ac1d03bf60282379076decbda068269ce582532038c1f1a4a5.jpg)

![3d70cd657b67f2ad647b79efbd15d0deb7cfa83006868666e98f3147bd56b9e8.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/3d70cd657b67f2ad647b79efbd15d0deb7cfa83006868666e98f3147bd56b9e8.jpg)

![3f360e885dec0b791e1fc06e3e075aea23dd16c9dc361ce825ef314dcba0e9c6.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/3f360e885dec0b791e1fc06e3e075aea23dd16c9dc361ce825ef314dcba0e9c6.jpg)

![59ba6319cc73cd5c039a3c52abe3ea5f2baf3fa8e143dbc45b3f3f101486b7e7.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/59ba6319cc73cd5c039a3c52abe3ea5f2baf3fa8e143dbc45b3f3f101486b7e7.jpg)

![616513fd75d0ae93f085dbab24dc3ea5a6dd23fa9233b383e576ff7af057b3f7.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/616513fd75d0ae93f085dbab24dc3ea5a6dd23fa9233b383e576ff7af057b3f7.jpg)

![623e92cf150b8e0d167aa8c6eb6060b09bc5463f0e66a7f581e69fa77d85a172.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/623e92cf150b8e0d167aa8c6eb6060b09bc5463f0e66a7f581e69fa77d85a172.jpg)

![a4c0ecd88279722902f0aabbdb93f8358904f2b549bc17f45701ee4d06010048.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/a4c0ecd88279722902f0aabbdb93f8358904f2b549bc17f45701ee4d06010048.jpg)

![c66926f7120fdad7fe9bbeed555ded31c12119ff954cb21472627b6775b6338d.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/c66926f7120fdad7fe9bbeed555ded31c12119ff954cb21472627b6775b6338d.jpg)

![c8bf3a83428b3f14bf80caf099bbf96934bc2d9c51e1cd1e6c510c7c1dc8082a.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/c8bf3a83428b3f14bf80caf099bbf96934bc2d9c51e1cd1e6c510c7c1dc8082a.jpg)

![c981ef869e5d4f5ea14f2578136c10a6aef365de3d5f9b0802ee37206183a339.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/c981ef869e5d4f5ea14f2578136c10a6aef365de3d5f9b0802ee37206183a339.jpg)

![e086696af7906528652eda1176fbf4a1d0346156eeda1447e3bc3793d34df631.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/e086696af7906528652eda1176fbf4a1d0346156eeda1447e3bc3793d34df631.jpg)

![e7f296ee4f90361f9a73df5a81db03bc4cf9be277b0f1380df49f89996932888.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/images/e7f296ee4f90361f9a73df5a81db03bc4cf9be277b0f1380df49f89996932888.jpg)

### Tables

![00163d0f3221e3aaf44a740ddb91a58ae38377a027677781891271668910dee6.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/tables/00163d0f3221e3aaf44a740ddb91a58ae38377a027677781891271668910dee6.jpg)

![8d1df87d9c2a004b0b76d58685499846244bae03ab8d6ae651d97e0f9f80eccf.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/tables/8d1df87d9c2a004b0b76d58685499846244bae03ab8d6ae651d97e0f9f80eccf.jpg)

![9e5bae489fd0d2297049a88a6546aa2ef05f1e05e7af8b7bc9c403e4db7510c7.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/tables/9e5bae489fd0d2297049a88a6546aa2ef05f1e05e7af8b7bc9c403e4db7510c7.jpg)

![c3f7b3187697f92e732678cdda507b7b80963902d9d443fc6f7e75fa88701909.jpg](../nips_results/4283_Quantifying%20Elicitation%20of%20Latent%20Capabilities%20in%20Language%20Models/tables/c3f7b3187697f92e732678cdda507b7b80963902d9d443fc6f7e75fa88701909.jpg)

## Guiding LLM Decision-Making with Fairness Reward Models


### Images

![0d1916148181227f4b8dd9f4f01d9a47b371b4896ff19684fb9c044d0e9847f0.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/0d1916148181227f4b8dd9f4f01d9a47b371b4896ff19684fb9c044d0e9847f0.jpg)

![11a6a5f48722753e43055b7a4a6d5162fe7214d894ae93e1e276dcd1328d071c.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/11a6a5f48722753e43055b7a4a6d5162fe7214d894ae93e1e276dcd1328d071c.jpg)

![14796c10d72511f6ba52ab59e54ea1e4b7de16c1d97d9705ef048f9821072ddb.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/14796c10d72511f6ba52ab59e54ea1e4b7de16c1d97d9705ef048f9821072ddb.jpg)

![3c3e26345e2b4689281a2812791622d182584aec79e7e697fb75525727a84262.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/3c3e26345e2b4689281a2812791622d182584aec79e7e697fb75525727a84262.jpg)

![4e1568332b68b042fa26cffaa5fdd6c5dc4349395045f9e849648e29d22d6518.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/4e1568332b68b042fa26cffaa5fdd6c5dc4349395045f9e849648e29d22d6518.jpg)

![4fe4ae83d41058fc0695804fe9675352e78bb334da95fef07dc77a344b249981.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/4fe4ae83d41058fc0695804fe9675352e78bb334da95fef07dc77a344b249981.jpg)

![543ee8dc9b1389ab683f29f2455e0ab558e062c35cf1bae5e65911cb0f258923.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/543ee8dc9b1389ab683f29f2455e0ab558e062c35cf1bae5e65911cb0f258923.jpg)

![567cd2b9e5bb5620d25c9fd7289e176386a1d84d2f00faeb3230b5ae07061cbd.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/567cd2b9e5bb5620d25c9fd7289e176386a1d84d2f00faeb3230b5ae07061cbd.jpg)

![7b3d234a3bd58d94e67cb650ebc68d29e5a5b07c7f9e8141bef98db82e221928.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/7b3d234a3bd58d94e67cb650ebc68d29e5a5b07c7f9e8141bef98db82e221928.jpg)

![9a5ed3ddfdb395700382e4d68bc04e8d4bef753d1a463be831cb010a070b23f3.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/9a5ed3ddfdb395700382e4d68bc04e8d4bef753d1a463be831cb010a070b23f3.jpg)

![9bc304832d440f3918bfc23d0eae1441a1517700fffb8f512b1ffc6b45998df7.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/9bc304832d440f3918bfc23d0eae1441a1517700fffb8f512b1ffc6b45998df7.jpg)

![a1387670ad2724f80773425a16e4e05e99c6f08e17e45824063d6aba2a3cfed2.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/a1387670ad2724f80773425a16e4e05e99c6f08e17e45824063d6aba2a3cfed2.jpg)

![c864cdf7435e59acc68d55536a1fe5262628f36330782493622048fa3da4966d.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/c864cdf7435e59acc68d55536a1fe5262628f36330782493622048fa3da4966d.jpg)

![db3478fe6cba8590a4eb495e4879d2ae75aca64a597a6aa47aa3d305ea855e9a.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/db3478fe6cba8590a4eb495e4879d2ae75aca64a597a6aa47aa3d305ea855e9a.jpg)

![eac9d798fcd4fb8c03a0cdb33cb10e0d25bc620d09b8b6ba25b2ce0778d8e185.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/eac9d798fcd4fb8c03a0cdb33cb10e0d25bc620d09b8b6ba25b2ce0778d8e185.jpg)

![ffab237f9be126fe57d49a776b4362d48bbd71bb92f53547be6952579529b274.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/images/ffab237f9be126fe57d49a776b4362d48bbd71bb92f53547be6952579529b274.jpg)

### Tables

![0bebfb294b937f39f154b2044a3aff8fafc1d9a3611fca7becf3c2cc8fe289ca.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/tables/0bebfb294b937f39f154b2044a3aff8fafc1d9a3611fca7becf3c2cc8fe289ca.jpg)

![38d1a94e60f31b7d0dc68c33c65b33009ef072e8d92f2d30925626695d6bf594.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/tables/38d1a94e60f31b7d0dc68c33c65b33009ef072e8d92f2d30925626695d6bf594.jpg)

![67605d28b526ca563958179e1f46be3d144465beadb60a81bae7702fbe64897d.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/tables/67605d28b526ca563958179e1f46be3d144465beadb60a81bae7702fbe64897d.jpg)

![a4ecd70f8dc557e64350970fb9b7f2fdb74d97fd03cd4abdd891ccab9ac07cd9.jpg](../nips_results/4284_Guiding%20LLM%20Decision-Making%20with%20Fairness%20Reward%20Models/tables/a4ecd70f8dc557e64350970fb9b7f2fdb74d97fd03cd4abdd891ccab9ac07cd9.jpg)

## DOVE: Efficient One-Step Diffusion Model for Real-World Video Super-Resolution


### Images

![52b61065bb4a938fb70210beadaad10167780d09254d4fd19c9d2cb897e137c5.jpg](../nips_results/4285_DOVE_%20Efficient%20One-Step%20Diffusion%20Model%20for%20Real-World%20Video%20Super-Resolution/images/52b61065bb4a938fb70210beadaad10167780d09254d4fd19c9d2cb897e137c5.jpg)

![5eb5608697230ccce71b318a30a4a90bc5a5a1b50580df4c054ef92a708c1322.jpg](../nips_results/4285_DOVE_%20Efficient%20One-Step%20Diffusion%20Model%20for%20Real-World%20Video%20Super-Resolution/images/5eb5608697230ccce71b318a30a4a90bc5a5a1b50580df4c054ef92a708c1322.jpg)

![db9ff50cebf7e3cfae49b67a883ca0b380b34b91af2ad3b78ab4649deaac3acb.jpg](../nips_results/4285_DOVE_%20Efficient%20One-Step%20Diffusion%20Model%20for%20Real-World%20Video%20Super-Resolution/images/db9ff50cebf7e3cfae49b67a883ca0b380b34b91af2ad3b78ab4649deaac3acb.jpg)

![e567c846c81456c21953fddec5e79fa5cf1350a71f3a98bf7d1adfa40f71b796.jpg](../nips_results/4285_DOVE_%20Efficient%20One-Step%20Diffusion%20Model%20for%20Real-World%20Video%20Super-Resolution/images/e567c846c81456c21953fddec5e79fa5cf1350a71f3a98bf7d1adfa40f71b796.jpg)

![fe1835cc222dfcb841c7dc7ecd7f53adc18c87f5e44f0ff6b746576ba8b9ecd1.jpg](../nips_results/4285_DOVE_%20Efficient%20One-Step%20Diffusion%20Model%20for%20Real-World%20Video%20Super-Resolution/images/fe1835cc222dfcb841c7dc7ecd7f53adc18c87f5e44f0ff6b746576ba8b9ecd1.jpg)

### Tables

![065f0feba31a102f4d5448768b686393bca2c8424d8962c12589e89bdf8ff3a5.jpg](../nips_results/4285_DOVE_%20Efficient%20One-Step%20Diffusion%20Model%20for%20Real-World%20Video%20Super-Resolution/tables/065f0feba31a102f4d5448768b686393bca2c8424d8962c12589e89bdf8ff3a5.jpg)

![0b40f4295b438d4a1bd6005d7e74c91f5a5b0cf5c8e43a5c93d8763ca835d149.jpg](../nips_results/4285_DOVE_%20Efficient%20One-Step%20Diffusion%20Model%20for%20Real-World%20Video%20Super-Resolution/tables/0b40f4295b438d4a1bd6005d7e74c91f5a5b0cf5c8e43a5c93d8763ca835d149.jpg)

![327ee78a12be45de675985130072d2e1fd2886de3c74f45df05a664a484eb940.jpg](../nips_results/4285_DOVE_%20Efficient%20One-Step%20Diffusion%20Model%20for%20Real-World%20Video%20Super-Resolution/tables/327ee78a12be45de675985130072d2e1fd2886de3c74f45df05a664a484eb940.jpg)

![568ffecb9fec71ff4d5dad9225257511d2475b79fd472c8f256a2985fad1baad.jpg](../nips_results/4285_DOVE_%20Efficient%20One-Step%20Diffusion%20Model%20for%20Real-World%20Video%20Super-Resolution/tables/568ffecb9fec71ff4d5dad9225257511d2475b79fd472c8f256a2985fad1baad.jpg)

![61535212084ab0cd1f26b628207658a5b54ae49bc37abc2015035f55056694ee.jpg](../nips_results/4285_DOVE_%20Efficient%20One-Step%20Diffusion%20Model%20for%20Real-World%20Video%20Super-Resolution/tables/61535212084ab0cd1f26b628207658a5b54ae49bc37abc2015035f55056694ee.jpg)

![8d62741bdf73d214279853e02b58cc14a41851bcd2ba87ce44078438d9ca0812.jpg](../nips_results/4285_DOVE_%20Efficient%20One-Step%20Diffusion%20Model%20for%20Real-World%20Video%20Super-Resolution/tables/8d62741bdf73d214279853e02b58cc14a41851bcd2ba87ce44078438d9ca0812.jpg)

## Nabla-R2D3: Effective and Efficient 3D Diffusion Alignment with 2D Rewards


### Images

![0697b6a0329ac93080b0ab9e73f835ba0e9dc0d276bea7bc90bdadfab7a96684.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/0697b6a0329ac93080b0ab9e73f835ba0e9dc0d276bea7bc90bdadfab7a96684.jpg)

![07e1d2120171915b67426d7db64000088b3c29c46ad4cfbab13f16e81543acf3.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/07e1d2120171915b67426d7db64000088b3c29c46ad4cfbab13f16e81543acf3.jpg)

![0997eef5e15d088564213cfe05fbd7daf6a7e2758557f1b94bd67dee0d9c4416.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/0997eef5e15d088564213cfe05fbd7daf6a7e2758557f1b94bd67dee0d9c4416.jpg)

![21770e596bc94c0e7ab4227220483238cc1882cc19345fbd1497974537cc871e.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/21770e596bc94c0e7ab4227220483238cc1882cc19345fbd1497974537cc871e.jpg)

![25e6f778222a727c0aa4d1f059214fc83c9ac953480dee775d4f4b2494053044.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/25e6f778222a727c0aa4d1f059214fc83c9ac953480dee775d4f4b2494053044.jpg)

![26e7785cdac1ed4d7c4cfc1362f3a5c398990ed8b4514db0bc64fec0f1019ba3.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/26e7785cdac1ed4d7c4cfc1362f3a5c398990ed8b4514db0bc64fec0f1019ba3.jpg)

![3fab8a1c684af92f02f5664017c407b5525e22cc53735043420c17250e438cc6.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/3fab8a1c684af92f02f5664017c407b5525e22cc53735043420c17250e438cc6.jpg)

![464b6a38ce3e181e6e1d51dffe85babce995d5eccbf0c89ad3b25e98e2d02328.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/464b6a38ce3e181e6e1d51dffe85babce995d5eccbf0c89ad3b25e98e2d02328.jpg)

![60443920c3fe2cf6dccf60fd313b8b3e8baf19155a77d596432fee6632dea313.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/60443920c3fe2cf6dccf60fd313b8b3e8baf19155a77d596432fee6632dea313.jpg)

![68b01191b297568f6a0b6ae43ec15f470048919611503301ed64b6637edfa160.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/68b01191b297568f6a0b6ae43ec15f470048919611503301ed64b6637edfa160.jpg)

![69a33fa74a233ebcf0c1511bf121363fc13194b99da5035f2873889db5098ff7.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/69a33fa74a233ebcf0c1511bf121363fc13194b99da5035f2873889db5098ff7.jpg)

![7ab338252654f17e6ba1fc4e1d6867a715d0fa93bb69388b9ed2175db62c8bc9.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/7ab338252654f17e6ba1fc4e1d6867a715d0fa93bb69388b9ed2175db62c8bc9.jpg)

![7b6d0d38af17e3a01a207f13a49e3d16e2172ddcc340de8762c933d2b6659190.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/7b6d0d38af17e3a01a207f13a49e3d16e2172ddcc340de8762c933d2b6659190.jpg)

![7f503a828ea5e577ad5a8550a871bdf0256fa0cb16a77ae8c4855cab511d2066.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/7f503a828ea5e577ad5a8550a871bdf0256fa0cb16a77ae8c4855cab511d2066.jpg)

![80054ee2ecaf6d3645d1989ba79e7fe9a9e957e65cda5bf481116b76ed677630.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/80054ee2ecaf6d3645d1989ba79e7fe9a9e957e65cda5bf481116b76ed677630.jpg)

![836c34d56d2f61dc53b46015e5e561be5925ec2e31d6c08786e37ca48bd0fbd9.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/836c34d56d2f61dc53b46015e5e561be5925ec2e31d6c08786e37ca48bd0fbd9.jpg)

![998bd4196976477f71233ca4f8030d6245982861868ce3d39a8cade9a64d70a0.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/998bd4196976477f71233ca4f8030d6245982861868ce3d39a8cade9a64d70a0.jpg)

![a0bec5d23081ed398adedbe6ab44e6499f831ba5f517aaa25ca7fe562476ccb6.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/a0bec5d23081ed398adedbe6ab44e6499f831ba5f517aaa25ca7fe562476ccb6.jpg)

![a102c4d8158ee07af06ff759f18782f1c32b852284fa5f31478ff471638baeca.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/a102c4d8158ee07af06ff759f18782f1c32b852284fa5f31478ff471638baeca.jpg)

![a33abe8a14a855f179a07e6c9de97a867b664391e4ffa172b4e3a52b36e33857.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/a33abe8a14a855f179a07e6c9de97a867b664391e4ffa172b4e3a52b36e33857.jpg)

![a4f76767aa175682153e1bf87e900a28f46f4b9f9febc5d54914d8d8de90e034.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/a4f76767aa175682153e1bf87e900a28f46f4b9f9febc5d54914d8d8de90e034.jpg)

![a661d51b5d19409c7ccdc6d257e11d1e331b2d49fc1bba57316d193af25e346b.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/a661d51b5d19409c7ccdc6d257e11d1e331b2d49fc1bba57316d193af25e346b.jpg)

![aecb2595051332d909de3e420db5d8a49dc41bdfb7e304c3d2c7ef753784e7d8.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/aecb2595051332d909de3e420db5d8a49dc41bdfb7e304c3d2c7ef753784e7d8.jpg)

![b28fbe356391f5cc3068a52c88dbb0d24d64bdbd68312f74cc018f9a8b220965.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/b28fbe356391f5cc3068a52c88dbb0d24d64bdbd68312f74cc018f9a8b220965.jpg)

![dec07ceaa5929e09be69e90de36b11b291ad4056b92b07483ae1caea611d5bec.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/dec07ceaa5929e09be69e90de36b11b291ad4056b92b07483ae1caea611d5bec.jpg)

![fa0cac8ed2d89492fe7b0d8a9e274da5d06d861f92265b601aa71e514f3f98f4.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/fa0cac8ed2d89492fe7b0d8a9e274da5d06d861f92265b601aa71e514f3f98f4.jpg)

![ff4c578d9c143090c82d88dc71144f2b6aad7871d62af9a909a473c267a3029a.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/images/ff4c578d9c143090c82d88dc71144f2b6aad7871d62af9a909a473c267a3029a.jpg)

### Tables

![511f58357d942276c088f8e284c6f1cb9f06f0bb9a1bcc1888c3a4fcf4d9e047.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/tables/511f58357d942276c088f8e284c6f1cb9f06f0bb9a1bcc1888c3a4fcf4d9e047.jpg)

![91c98eb94fb822cee1eb36e7afc2f04bd5cbd76e346cb8093c5b63c3a7c8ebd2.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/tables/91c98eb94fb822cee1eb36e7afc2f04bd5cbd76e346cb8093c5b63c3a7c8ebd2.jpg)

![9545db21da2ecb06cc6bc8f81a699771f20fa5af186df7b59acd7fe0445ba8c0.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/tables/9545db21da2ecb06cc6bc8f81a699771f20fa5af186df7b59acd7fe0445ba8c0.jpg)

![9fc311c9d91dfe5ccc0f5df204f3a8816bf3bd836b3ded153db4a89cd394bc13.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/tables/9fc311c9d91dfe5ccc0f5df204f3a8816bf3bd836b3ded153db4a89cd394bc13.jpg)

![d95127230b0ec64771a0f721a40769be7644f385fca8a546d01f79872ce6ada7.jpg](../nips_results/4286_Nabla-R2D3_%20Effective%20and%20Efficient%203D%20Diffusion%20Alignment%20with%202D%20Rewards/tables/d95127230b0ec64771a0f721a40769be7644f385fca8a546d01f79872ce6ada7.jpg)

## How to build a consistency model: Learning flow maps via self-distillation


### Images

![3a64966c5ec70a7bac11413cf1a81e47c41e721f7286a86715372851a7a51d24.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/images/3a64966c5ec70a7bac11413cf1a81e47c41e721f7286a86715372851a7a51d24.jpg)

![41cb25172d952d759d7e01a2787d3fac10d2812bc2b76b0effe0eb0c3d194d5b.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/images/41cb25172d952d759d7e01a2787d3fac10d2812bc2b76b0effe0eb0c3d194d5b.jpg)

![429390e5fb5cfce6f1c2524ae01cd9ccdd0848e39677ddc232cd28d0d334e3c4.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/images/429390e5fb5cfce6f1c2524ae01cd9ccdd0848e39677ddc232cd28d0d334e3c4.jpg)

![655b1f7fed6d8f17f2569d411aa18405da9191b6acb915998d4dd6faad41a79f.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/images/655b1f7fed6d8f17f2569d411aa18405da9191b6acb915998d4dd6faad41a79f.jpg)

![6ceae18e9248673be25784f9cac9fab71b88cd657aae09895d774d5ff3eb7f61.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/images/6ceae18e9248673be25784f9cac9fab71b88cd657aae09895d774d5ff3eb7f61.jpg)

![c0dc991de15f0661c738ba96f9b5b3eafa3e49ee26d7d53988e58b8c253a042e.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/images/c0dc991de15f0661c738ba96f9b5b3eafa3e49ee26d7d53988e58b8c253a042e.jpg)

### Tables

![238e072a28f2585da6d52682285a2907b3504bca580490d8ee549e533e9f458e.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/tables/238e072a28f2585da6d52682285a2907b3504bca580490d8ee549e533e9f458e.jpg)

![2802cd5d2c3b1dc3237c2df515fb521ef703cdc8206246107c791894f9984857.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/tables/2802cd5d2c3b1dc3237c2df515fb521ef703cdc8206246107c791894f9984857.jpg)

![6c09ab59793c724602b40fd3ea42bb899f195e910eadb8f767ca110706cc81a8.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/tables/6c09ab59793c724602b40fd3ea42bb899f195e910eadb8f767ca110706cc81a8.jpg)

![71e520015c8a6b9550e5739b6450a61f0aed5bd59ab1f12d52c01c53f1a7393d.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/tables/71e520015c8a6b9550e5739b6450a61f0aed5bd59ab1f12d52c01c53f1a7393d.jpg)

![9ab9cf66de92177165022b71310efe26d2a2cf9685bad6b1fd3a1c449c3a7b71.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/tables/9ab9cf66de92177165022b71310efe26d2a2cf9685bad6b1fd3a1c449c3a7b71.jpg)

![a21e444d8bd96389b3d98d6e01e2e18ab437c55ed57e43b2fadfe07eb8b9e97f.jpg](../nips_results/4287_How%20to%20build%20a%20consistency%20model_%20Learning%20flow%20maps%20via%20self-distillation/tables/a21e444d8bd96389b3d98d6e01e2e18ab437c55ed57e43b2fadfe07eb8b9e97f.jpg)

## SPACE: SPike-Aware Consistency Enhancement for Test-Time Adaptation in Spiking Neural Networks


### Images

![10f8cccc4bdb7875caaa393afe6301a98a223e6d5ffeec44ae9dcfb24052ce1b.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/images/10f8cccc4bdb7875caaa393afe6301a98a223e6d5ffeec44ae9dcfb24052ce1b.jpg)

![1af67c3fe064c22003b9af4d0d1677283e6735e767b8d5b1348278f367ae9fff.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/images/1af67c3fe064c22003b9af4d0d1677283e6735e767b8d5b1348278f367ae9fff.jpg)

![d26bf5a1ecadd502d4d7dfd720bef3d18bbce32d624e353fa7d467a7b4300813.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/images/d26bf5a1ecadd502d4d7dfd720bef3d18bbce32d624e353fa7d467a7b4300813.jpg)

### Tables

![01586639de22136186af58486d521068aa0d84698290b3cd32b76e3cc91c11f6.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/01586639de22136186af58486d521068aa0d84698290b3cd32b76e3cc91c11f6.jpg)

![14220a28f99ddf1319f36276645d6cb8c868226f4ed064d9e747d9dd52bee2e6.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/14220a28f99ddf1319f36276645d6cb8c868226f4ed064d9e747d9dd52bee2e6.jpg)

![47fd0f79aa7c0fcce8aa31c567ca313491651829dc8c62e76c8fc510567f70b0.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/47fd0f79aa7c0fcce8aa31c567ca313491651829dc8c62e76c8fc510567f70b0.jpg)

![644810a8e4d6904a9e746ef2bc0710b29514539582ce020d4340e9cc42d70a76.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/644810a8e4d6904a9e746ef2bc0710b29514539582ce020d4340e9cc42d70a76.jpg)

![64a53c33dfff39c5bf9beefc4d841db3ba0bb270389e4a8097a95f6bcd6772df.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/64a53c33dfff39c5bf9beefc4d841db3ba0bb270389e4a8097a95f6bcd6772df.jpg)

![6dbda3a48044b85661b5ddcf5ee4b1d38ca51e077d00ea9537f3f081cce951e8.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/6dbda3a48044b85661b5ddcf5ee4b1d38ca51e077d00ea9537f3f081cce951e8.jpg)

![6e5c1b9956400b9162280123c8a3eaeb571a64699f9ceb136cf5db91eae98ed5.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/6e5c1b9956400b9162280123c8a3eaeb571a64699f9ceb136cf5db91eae98ed5.jpg)

![7a228c778a3e7cbd1fe99c33d2d9b31c029b523448c8a6c2e3ad8d27ad53f9f5.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/7a228c778a3e7cbd1fe99c33d2d9b31c029b523448c8a6c2e3ad8d27ad53f9f5.jpg)

![7db32d5e01550961542efcfd2f869f26d9ac3090c45fdfaf61beb46b0b86163d.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/7db32d5e01550961542efcfd2f869f26d9ac3090c45fdfaf61beb46b0b86163d.jpg)

![8752da7512eb31333b46d506f55779ffc66864593755f73417187df9f82eaab2.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/8752da7512eb31333b46d506f55779ffc66864593755f73417187df9f82eaab2.jpg)

![a34bd7966c9e1bd71dfb1484a3df902ee402f6299fee10c4d88f1f2b8688c2e3.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/a34bd7966c9e1bd71dfb1484a3df902ee402f6299fee10c4d88f1f2b8688c2e3.jpg)

![b20c9575eae639ded6b5bed223e9e4b17b0537bc63716e781fcd67b2ce91607a.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/b20c9575eae639ded6b5bed223e9e4b17b0537bc63716e781fcd67b2ce91607a.jpg)

![f7124e7c35b0112b1004a5f2e6f2f0273fd3fafb87c355de9cd45d43d2c70f43.jpg](../nips_results/4288_SPACE_%20SPike-Aware%20Consistency%20Enhancement%20for%20Test-Time%20Adaptation%20in%20Spiking%20Neural%20Networks/tables/f7124e7c35b0112b1004a5f2e6f2f0273fd3fafb87c355de9cd45d43d2c70f43.jpg)

## FedEL: Federated Elastic Learning for Heterogeneous Devices


### Images

![0517b21b354aa3b1d351ecd873b9c6e8f2f2f45803ddc07f91a660acdf2f6486.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/0517b21b354aa3b1d351ecd873b9c6e8f2f2f45803ddc07f91a660acdf2f6486.jpg)

![113488e8aeb3a44f8551c405711d2f63107cfcef5a7c55c8af67208400301e47.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/113488e8aeb3a44f8551c405711d2f63107cfcef5a7c55c8af67208400301e47.jpg)

![24ec9b46b30c3e88b1872f9d25dea3a6493ddab8fa8963538b4d43177ab2b0f7.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/24ec9b46b30c3e88b1872f9d25dea3a6493ddab8fa8963538b4d43177ab2b0f7.jpg)

![29d1ec48678386a6f67d7451f9cb2e78a1b8b2a0b7f731076466156e597d4921.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/29d1ec48678386a6f67d7451f9cb2e78a1b8b2a0b7f731076466156e597d4921.jpg)

![44246e631cef8eb41a7955b963530969c44c16f4aa7e1aef3c802886242e61e5.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/44246e631cef8eb41a7955b963530969c44c16f4aa7e1aef3c802886242e61e5.jpg)

![6386e9aa5cb408a7d9c4c57312ea2d65aa00d8365bc09dff820364ed3d18571b.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/6386e9aa5cb408a7d9c4c57312ea2d65aa00d8365bc09dff820364ed3d18571b.jpg)

![64d028a11f839c90306517979090364733e1f5158874234b49d973826a2523e8.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/64d028a11f839c90306517979090364733e1f5158874234b49d973826a2523e8.jpg)

![69f804ecaa0cb6b60b3e8073f8dc06a42980c8e9e66685b51b7e529f06ec23f4.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/69f804ecaa0cb6b60b3e8073f8dc06a42980c8e9e66685b51b7e529f06ec23f4.jpg)

![6ef971bef6b8ed9c0df55cfb9771485db01fa9a1c31a2a95ef0cb6b49a19b8e5.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/6ef971bef6b8ed9c0df55cfb9771485db01fa9a1c31a2a95ef0cb6b49a19b8e5.jpg)

![73debeb87244c4e0008d908632d83b4a62de2f460087fab93a3a665ed2884b32.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/73debeb87244c4e0008d908632d83b4a62de2f460087fab93a3a665ed2884b32.jpg)

![763ff9e2ede12a048237438490ad8f7f7d709a0aba874a7d0b608f359b3aec8a.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/763ff9e2ede12a048237438490ad8f7f7d709a0aba874a7d0b608f359b3aec8a.jpg)

![86ae4d3951f0e2a0662468d54cf7817c5d870e5a4c46218c49a1cc92e6ebf795.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/86ae4d3951f0e2a0662468d54cf7817c5d870e5a4c46218c49a1cc92e6ebf795.jpg)

![8a366fab8fa6f5dfd3dcf4cca6eebec7c3b9d4af35eb12bc1169f3424a7d0cdd.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/8a366fab8fa6f5dfd3dcf4cca6eebec7c3b9d4af35eb12bc1169f3424a7d0cdd.jpg)

![8e648579318763b6927b5e033ca0874b22778fff8f604fc00b21714310f86e30.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/8e648579318763b6927b5e033ca0874b22778fff8f604fc00b21714310f86e30.jpg)

![b1e71b0441ba90379909c61190166ca8a82636772e1b6b565e2fa3549099d371.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/b1e71b0441ba90379909c61190166ca8a82636772e1b6b565e2fa3549099d371.jpg)

![b5d20c333de1e543ff53ead241b53ef38a8a16258caf0404d5f8ee65b1239b6c.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/b5d20c333de1e543ff53ead241b53ef38a8a16258caf0404d5f8ee65b1239b6c.jpg)

![c6fe075f2567f19c13da5085d4c3a4c82bb9f9fc6fb524715b9e90d2064f727f.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/c6fe075f2567f19c13da5085d4c3a4c82bb9f9fc6fb524715b9e90d2064f727f.jpg)

![d305773833b27eaa5800ecf34c513e6f0132a7422e855d419dfcd926b4d70097.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/d305773833b27eaa5800ecf34c513e6f0132a7422e855d419dfcd926b4d70097.jpg)

![ddf4a008a18b423b8b7c73c6276186f4aa0410c5059732444fbd7370851b76ed.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/images/ddf4a008a18b423b8b7c73c6276186f4aa0410c5059732444fbd7370851b76ed.jpg)

### Tables

![3fe986b2de97885f4f2c83cf07f4c35881dca49d6ee5dd5c043ed148fa183bdc.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/tables/3fe986b2de97885f4f2c83cf07f4c35881dca49d6ee5dd5c043ed148fa183bdc.jpg)

![4a1cdc90499ad7e2fad6330763ea14da62a2d2e22fcab71d4eaad3525d839972.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/tables/4a1cdc90499ad7e2fad6330763ea14da62a2d2e22fcab71d4eaad3525d839972.jpg)

![5aaa7fb93048295ee28e2e072f61ebeb4b1cf766ce86e093af6f93728741882e.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/tables/5aaa7fb93048295ee28e2e072f61ebeb4b1cf766ce86e093af6f93728741882e.jpg)

![5d54eeaa4d6ad70e64993a4c5ffaa84a3d120b1699df1dfc8e22bc1704dafee2.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/tables/5d54eeaa4d6ad70e64993a4c5ffaa84a3d120b1699df1dfc8e22bc1704dafee2.jpg)

![c793de01a91d13ce685dba3d13aff0fd5b318e454a8d8e2d4cd1d480f396cdd8.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/tables/c793de01a91d13ce685dba3d13aff0fd5b318e454a8d8e2d4cd1d480f396cdd8.jpg)

![d5fed04e793374152c8a8e660a350cfbd73d6ae95be123430c176239622932ad.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/tables/d5fed04e793374152c8a8e660a350cfbd73d6ae95be123430c176239622932ad.jpg)

![df37ca5b22025dbc9a5e485e17405c29d9adf84bfc95f8aa7a2d39e06a4975c2.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/tables/df37ca5b22025dbc9a5e485e17405c29d9adf84bfc95f8aa7a2d39e06a4975c2.jpg)

![fb00d61180f46784a7692cddb3f032f07f838c6d340bdfb1402065067a2c7f75.jpg](../nips_results/4289_FedEL_%20Federated%20Elastic%20Learning%20for%20Heterogeneous%20Devices/tables/fb00d61180f46784a7692cddb3f032f07f838c6d340bdfb1402065067a2c7f75.jpg)

## Cooperative Bargaining Games Without Utilities: Mediated Solutions from Direction Oracles


### Images

![435ea88d8f3670dfc889a85ea382555ce2de281d1cd6ab3244bcc957a62f119f.jpg](../nips_results/4290_Cooperative%20Bargaining%20Games%20Without%20Utilities_%20Mediated%20Solutions%20from%20Direction%20Oracles/images/435ea88d8f3670dfc889a85ea382555ce2de281d1cd6ab3244bcc957a62f119f.jpg)

![6dd364ba9c900de78e95a9342d4b98876719dd1279633fc667acd0480fba61a6.jpg](../nips_results/4290_Cooperative%20Bargaining%20Games%20Without%20Utilities_%20Mediated%20Solutions%20from%20Direction%20Oracles/images/6dd364ba9c900de78e95a9342d4b98876719dd1279633fc667acd0480fba61a6.jpg)

![81925d585dd0ea13be6c65d032d90163490573b441665747ccd1c9e8efed2cd3.jpg](../nips_results/4290_Cooperative%20Bargaining%20Games%20Without%20Utilities_%20Mediated%20Solutions%20from%20Direction%20Oracles/images/81925d585dd0ea13be6c65d032d90163490573b441665747ccd1c9e8efed2cd3.jpg)

![e1a9652f37ef1a331c39d0bf9ed52ea067f44a9841e0aa1cb0606bb900e52420.jpg](../nips_results/4290_Cooperative%20Bargaining%20Games%20Without%20Utilities_%20Mediated%20Solutions%20from%20Direction%20Oracles/images/e1a9652f37ef1a331c39d0bf9ed52ea067f44a9841e0aa1cb0606bb900e52420.jpg)

![f270fa19ed271d75db99b7afb31bf122bb8779fa5a68826f060f32aa5676daf8.jpg](../nips_results/4290_Cooperative%20Bargaining%20Games%20Without%20Utilities_%20Mediated%20Solutions%20from%20Direction%20Oracles/images/f270fa19ed271d75db99b7afb31bf122bb8779fa5a68826f060f32aa5676daf8.jpg)

## Time-Embedded Algorithm Unrolling for Computational MRI


### Images

![1a78cc17959b511681dce5e944121d66c867e8f662981666d1105a9dfcb1f091.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/1a78cc17959b511681dce5e944121d66c867e8f662981666d1105a9dfcb1f091.jpg)

![27c8766d439567488d65ec73914375a9bc217c97f8f0dc211454facef4e75e92.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/27c8766d439567488d65ec73914375a9bc217c97f8f0dc211454facef4e75e92.jpg)

![32a1acf666526e7184fd06e81e76f8ed47596c6b185c400a9bc537a8ba990dc0.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/32a1acf666526e7184fd06e81e76f8ed47596c6b185c400a9bc537a8ba990dc0.jpg)

![37804192d70b20f5bc216871a88e3080de833184e71be78bf58180a12ab1a324.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/37804192d70b20f5bc216871a88e3080de833184e71be78bf58180a12ab1a324.jpg)

![58b77adc1239e296a2851faf9193f895ec38091fb735acc2c766f2f488cae735.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/58b77adc1239e296a2851faf9193f895ec38091fb735acc2c766f2f488cae735.jpg)

![6205a16fa25c95e3b9707427a8a2b449e954d767577509ff607775baa8f08b67.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/6205a16fa25c95e3b9707427a8a2b449e954d767577509ff607775baa8f08b67.jpg)

![6abe26a55385f31e131b029c4972b550f7fffc68d3f4e2f3a3ebf5fa8eefade1.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/6abe26a55385f31e131b029c4972b550f7fffc68d3f4e2f3a3ebf5fa8eefade1.jpg)

![9bd43b615e63974d11c615a2d4535add43baafbf943ee63cf01f56dc876ba764.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/9bd43b615e63974d11c615a2d4535add43baafbf943ee63cf01f56dc876ba764.jpg)

![bfbd3a4bb7de326c96fce7fa3c1cb319f447891428f31c12009f253ea4300d0d.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/bfbd3a4bb7de326c96fce7fa3c1cb319f447891428f31c12009f253ea4300d0d.jpg)

![e0e973d07c680b52b2d1fd33c389f939b4a0837f1d0197c6ca174454db843ef5.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/e0e973d07c680b52b2d1fd33c389f939b4a0837f1d0197c6ca174454db843ef5.jpg)

![ea186855a3b272b64f2c97907169e2c7b9e169022e26cab1aaeb824a34bf0412.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/ea186855a3b272b64f2c97907169e2c7b9e169022e26cab1aaeb824a34bf0412.jpg)

![ea3584b90e85f04e07f12c1ea12f78c911991bcc9547ba0b190c2eb5c6fe5635.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/ea3584b90e85f04e07f12c1ea12f78c911991bcc9547ba0b190c2eb5c6fe5635.jpg)

![fc62e44c92a839d910d665f2c9b94c6f28fb44f8deac17ceac58cd93ec6609e0.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/images/fc62e44c92a839d910d665f2c9b94c6f28fb44f8deac17ceac58cd93ec6609e0.jpg)

### Tables

![211ef48823998e05460bbf32f1abc5cb6ac2b172221db6cd1c38eb884e2df6cd.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/tables/211ef48823998e05460bbf32f1abc5cb6ac2b172221db6cd1c38eb884e2df6cd.jpg)

![23a099e8a626fdfc85ddd123acd73c9dec8c717fa1e8acb702be1c80e71d00c3.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/tables/23a099e8a626fdfc85ddd123acd73c9dec8c717fa1e8acb702be1c80e71d00c3.jpg)

![32826c5841e4e77c9648680a55cacd4e324b357c3ae81e26fceaeadbb949da2c.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/tables/32826c5841e4e77c9648680a55cacd4e324b357c3ae81e26fceaeadbb949da2c.jpg)

![4968ca1e53374d49cb2779c8d25685afff1c141f784c4135e120817f0ee853e8.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/tables/4968ca1e53374d49cb2779c8d25685afff1c141f784c4135e120817f0ee853e8.jpg)

![5ce19f8be1880016d879fab84354cd1e22eee10c6fd302af930a888b3a8aa87f.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/tables/5ce19f8be1880016d879fab84354cd1e22eee10c6fd302af930a888b3a8aa87f.jpg)

![926c068538d7ed77b01af52d8723cdf26ccf3a92cc82d6b22a3a2b6673c609f8.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/tables/926c068538d7ed77b01af52d8723cdf26ccf3a92cc82d6b22a3a2b6673c609f8.jpg)

![9f490c1ee65ce36e41e03f52053b72d38a19af3013641f790fa39a2800319b72.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/tables/9f490c1ee65ce36e41e03f52053b72d38a19af3013641f790fa39a2800319b72.jpg)

![b4758526468ddf585d7554a61761eec45517a249c02551b83dafa2432990573b.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/tables/b4758526468ddf585d7554a61761eec45517a249c02551b83dafa2432990573b.jpg)

![c42005c3ed02caa44d701ea35923969fd10c0ca4940e82db6fcd6d89b2a8c7e4.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/tables/c42005c3ed02caa44d701ea35923969fd10c0ca4940e82db6fcd6d89b2a8c7e4.jpg)

![d60ee2ebb7e0189607b2090b3366ea7eaf0fd9d00a64263500ab44548eb71e8f.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/tables/d60ee2ebb7e0189607b2090b3366ea7eaf0fd9d00a64263500ab44548eb71e8f.jpg)

![ec53bbac44450e0a3eb7030d72be749043b830bdf3cdca3f7ae0c291e9d8fdc9.jpg](../nips_results/4291_Time-Embedded%20Algorithm%20Unrolling%20for%20Computational%20MRI/tables/ec53bbac44450e0a3eb7030d72be749043b830bdf3cdca3f7ae0c291e9d8fdc9.jpg)

## Noise Hypernetworks: Amortizing Test-Time Compute in Diffusion Models


### Images

![125cd90872b3afc0b476da0773d9b9fe1ba7a19fb42ee77ea83652018ffe815f.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/images/125cd90872b3afc0b476da0773d9b9fe1ba7a19fb42ee77ea83652018ffe815f.jpg)

![4655349013937233c1a6179a3cf9fa74bf923bea909328d846988a11eb36c1a1.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/images/4655349013937233c1a6179a3cf9fa74bf923bea909328d846988a11eb36c1a1.jpg)

![74e26e658340ad8d90a53349606d4083a6dba7a8d5df2e5536f7b0aefcd2ee50.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/images/74e26e658340ad8d90a53349606d4083a6dba7a8d5df2e5536f7b0aefcd2ee50.jpg)

![80b2cb34e7a46357462259b9e8f670783bcad53b49391099802b43950fe50ad0.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/images/80b2cb34e7a46357462259b9e8f670783bcad53b49391099802b43950fe50ad0.jpg)

![91f07362702658bbb7824536e62ffbc41f77c0fa0d02b8e5cf78f068b8722e49.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/images/91f07362702658bbb7824536e62ffbc41f77c0fa0d02b8e5cf78f068b8722e49.jpg)

![ccede6cb2302f57b454e237777aa07fb54af7c904fa7c3a19621ce93306d7c3d.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/images/ccede6cb2302f57b454e237777aa07fb54af7c904fa7c3a19621ce93306d7c3d.jpg)

![db80946df79e3b294954340849aead933c0c52471761f6774b46b8a51f3c7bb4.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/images/db80946df79e3b294954340849aead933c0c52471761f6774b46b8a51f3c7bb4.jpg)

![dcc66b25aee8a9268089b44b97b5bb936aa317af5de47fb53fb3cb5b98c644d7.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/images/dcc66b25aee8a9268089b44b97b5bb936aa317af5de47fb53fb3cb5b98c644d7.jpg)

### Tables

![0bc35a8ef9c2f44286f0b9be8351d4405f9300021123bbfacae375fa3a14ff02.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/tables/0bc35a8ef9c2f44286f0b9be8351d4405f9300021123bbfacae375fa3a14ff02.jpg)

![47edc7f5c9514b55582efd4a3c6d546396e7bb3eedea6a6e53e046256116a95f.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/tables/47edc7f5c9514b55582efd4a3c6d546396e7bb3eedea6a6e53e046256116a95f.jpg)

![4b94b6f1dfc72f9577e6a095fa86d064d08f69069fb265fde8d0e3a62a4221ec.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/tables/4b94b6f1dfc72f9577e6a095fa86d064d08f69069fb265fde8d0e3a62a4221ec.jpg)

![8ec77af40e264be56a0ce38959731a737ef7ae26107ce66166e3af21d10505b3.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/tables/8ec77af40e264be56a0ce38959731a737ef7ae26107ce66166e3af21d10505b3.jpg)

![913d5283ec13bda0b6ac225d6d7f039dcb80ee39860ca837e83278c337a5a660.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/tables/913d5283ec13bda0b6ac225d6d7f039dcb80ee39860ca837e83278c337a5a660.jpg)

![9d14e031a6298b55f2bd8ef13a30b5c822d1099a3745d124b7c747f37a927a52.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/tables/9d14e031a6298b55f2bd8ef13a30b5c822d1099a3745d124b7c747f37a927a52.jpg)

![a3898b0ff4b909ca95ae33b635a823c223586682ecfd894029bfa225d0ff9ba4.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/tables/a3898b0ff4b909ca95ae33b635a823c223586682ecfd894029bfa225d0ff9ba4.jpg)

![aa89eddeb8b951d52df35ca174cf948846d4788e1de0e744616e72a0f081e347.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/tables/aa89eddeb8b951d52df35ca174cf948846d4788e1de0e744616e72a0f081e347.jpg)

![b1e8d0c1b8265acc9e2e3cbdbb7dfddb054d348771023d5a64bb9169d1ab3eca.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/tables/b1e8d0c1b8265acc9e2e3cbdbb7dfddb054d348771023d5a64bb9169d1ab3eca.jpg)

![c3bad72a61fd4fe79989ee10abb02484c5464921210d3659702bb0b086f844ce.jpg](../nips_results/4292_Noise%20Hypernetworks_%20Amortizing%20Test-Time%20Compute%20in%20Diffusion%20Models/tables/c3bad72a61fd4fe79989ee10abb02484c5464921210d3659702bb0b086f844ce.jpg)

## Vector Database Watermarking


### Images

![1ccc8409e3e8bb1aca4730700724baeff7f0abbed7b9ecba9717769bfdf65568.jpg](../nips_results/4293_Vector%20Database%20Watermarking/images/1ccc8409e3e8bb1aca4730700724baeff7f0abbed7b9ecba9717769bfdf65568.jpg)

![262a63af28fc4331007811ee7154bc9e544cee301f79ccd1a1ccf00a2376913f.jpg](../nips_results/4293_Vector%20Database%20Watermarking/images/262a63af28fc4331007811ee7154bc9e544cee301f79ccd1a1ccf00a2376913f.jpg)

![31f1c090c11436b1ff392de65337702eb03d20b5aad7aa0b94784987ef02f648.jpg](../nips_results/4293_Vector%20Database%20Watermarking/images/31f1c090c11436b1ff392de65337702eb03d20b5aad7aa0b94784987ef02f648.jpg)

![6d1bfb7fbb7b8ab50125a5a6fb7426487cd98eefd25e22e75c83c1efa2de62dd.jpg](../nips_results/4293_Vector%20Database%20Watermarking/images/6d1bfb7fbb7b8ab50125a5a6fb7426487cd98eefd25e22e75c83c1efa2de62dd.jpg)

![840a3bddc46638ee7d9676d4bdeb95c4f5b60826b311fd25e1eac2854dc2475d.jpg](../nips_results/4293_Vector%20Database%20Watermarking/images/840a3bddc46638ee7d9676d4bdeb95c4f5b60826b311fd25e1eac2854dc2475d.jpg)

![905fccc8128a19f41447197c72331abf92dc3a21fb529c96ab0141b490390cf2.jpg](../nips_results/4293_Vector%20Database%20Watermarking/images/905fccc8128a19f41447197c72331abf92dc3a21fb529c96ab0141b490390cf2.jpg)

![c4970f4a7ba60c6d090ebecb102404df00e50810a4a0ab60fed9895038cdbe0a.jpg](../nips_results/4293_Vector%20Database%20Watermarking/images/c4970f4a7ba60c6d090ebecb102404df00e50810a4a0ab60fed9895038cdbe0a.jpg)

![d0ee30a0a08cc597f794cb805a79c6919c689ef96df3ee7689432352fe5829f5.jpg](../nips_results/4293_Vector%20Database%20Watermarking/images/d0ee30a0a08cc597f794cb805a79c6919c689ef96df3ee7689432352fe5829f5.jpg)

![e97574c3b3ea22f51a5ccb99fa939918ed51d9842d9961de6b5e0a38d5947547.jpg](../nips_results/4293_Vector%20Database%20Watermarking/images/e97574c3b3ea22f51a5ccb99fa939918ed51d9842d9961de6b5e0a38d5947547.jpg)

![eacf80deb62509ea278ff16dcd632f6135e9b99f357749d406709b26397b6876.jpg](../nips_results/4293_Vector%20Database%20Watermarking/images/eacf80deb62509ea278ff16dcd632f6135e9b99f357749d406709b26397b6876.jpg)

### Tables

![0918ad16a66403c9ae9e6d388b541a61580bdacc02bfff8e91a9e66210dfb539.jpg](../nips_results/4293_Vector%20Database%20Watermarking/tables/0918ad16a66403c9ae9e6d388b541a61580bdacc02bfff8e91a9e66210dfb539.jpg)

![14dd861a588ee6267b7af01ad57b4c894d212eddd8e3c258d28af14459012123.jpg](../nips_results/4293_Vector%20Database%20Watermarking/tables/14dd861a588ee6267b7af01ad57b4c894d212eddd8e3c258d28af14459012123.jpg)

![71565a027667044ea7cdfd15c1c5696286fd3fac53d8fe6b2c4cdd735cf80f6c.jpg](../nips_results/4293_Vector%20Database%20Watermarking/tables/71565a027667044ea7cdfd15c1c5696286fd3fac53d8fe6b2c4cdd735cf80f6c.jpg)

![a7457368eceebe2425b12f0fcf555785ac4dedddfac670f74b33dd542d94bf79.jpg](../nips_results/4293_Vector%20Database%20Watermarking/tables/a7457368eceebe2425b12f0fcf555785ac4dedddfac670f74b33dd542d94bf79.jpg)

![ac6159875fd4923d2c5ca4187b936d3a0035c2d21a8ed639061189626413e1aa.jpg](../nips_results/4293_Vector%20Database%20Watermarking/tables/ac6159875fd4923d2c5ca4187b936d3a0035c2d21a8ed639061189626413e1aa.jpg)

![bf299cda45537266d5ed6c28dcce9903db1d66e0985f5ab7203d96dfd4c9aed4.jpg](../nips_results/4293_Vector%20Database%20Watermarking/tables/bf299cda45537266d5ed6c28dcce9903db1d66e0985f5ab7203d96dfd4c9aed4.jpg)

![e39687f3e3d04c162bf03c24bb9a1e2c96a3f9bbac0bedad664b7bc8d77375ed.jpg](../nips_results/4293_Vector%20Database%20Watermarking/tables/e39687f3e3d04c162bf03c24bb9a1e2c96a3f9bbac0bedad664b7bc8d77375ed.jpg)

![ee19b0e9775b169bfe8f863bc5b8a184364a2736174377e0ddb35a79efd911b9.jpg](../nips_results/4293_Vector%20Database%20Watermarking/tables/ee19b0e9775b169bfe8f863bc5b8a184364a2736174377e0ddb35a79efd911b9.jpg)

![f157242c2d8eb5a057ebd9c81f5410927ab7a821dfc0b3de90606067c4ea543b.jpg](../nips_results/4293_Vector%20Database%20Watermarking/tables/f157242c2d8eb5a057ebd9c81f5410927ab7a821dfc0b3de90606067c4ea543b.jpg)

## Neural Collapse under Gradient Flow on Shallow ReLU Networks for Orthogonally Separable Data


### Images

![1723ca1054f33a97327deaba404cd17e83b8bfd328b6847e7e5e0c0a6ddc6586.jpg](../nips_results/4294_Neural%20Collapse%20under%20Gradient%20Flow%20on%20Shallow%20ReLU%20Networks%20for%20Orthogonally%20Separable%20Data/images/1723ca1054f33a97327deaba404cd17e83b8bfd328b6847e7e5e0c0a6ddc6586.jpg)

![29c18a93a81191c4617f22cd785c2a6f4b4ec0a9facf5eaf25395a1bdfbc31fc.jpg](../nips_results/4294_Neural%20Collapse%20under%20Gradient%20Flow%20on%20Shallow%20ReLU%20Networks%20for%20Orthogonally%20Separable%20Data/images/29c18a93a81191c4617f22cd785c2a6f4b4ec0a9facf5eaf25395a1bdfbc31fc.jpg)

![3b753ddba8a2499048c010620ee3cf7ee97a930987d99e420d54adc64741b766.jpg](../nips_results/4294_Neural%20Collapse%20under%20Gradient%20Flow%20on%20Shallow%20ReLU%20Networks%20for%20Orthogonally%20Separable%20Data/images/3b753ddba8a2499048c010620ee3cf7ee97a930987d99e420d54adc64741b766.jpg)

![cb3758bcab3cb3a8c39622dd84765cc7dacc57ee94862489d2cb608ee8c3f37d.jpg](../nips_results/4294_Neural%20Collapse%20under%20Gradient%20Flow%20on%20Shallow%20ReLU%20Networks%20for%20Orthogonally%20Separable%20Data/images/cb3758bcab3cb3a8c39622dd84765cc7dacc57ee94862489d2cb608ee8c3f37d.jpg)

![df1d90498b48f7d6a9758af1a8a7600856743195e44990a1649d4aa9db85f2a7.jpg](../nips_results/4294_Neural%20Collapse%20under%20Gradient%20Flow%20on%20Shallow%20ReLU%20Networks%20for%20Orthogonally%20Separable%20Data/images/df1d90498b48f7d6a9758af1a8a7600856743195e44990a1649d4aa9db85f2a7.jpg)

## Sparse Autoencoders Learn Monosemantic Features in Vision-Language Models


### Images

![00db0ef81a4ed3b1927f65a50629fa9816ec38d2bcc02b9a4712957108f962fd.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/00db0ef81a4ed3b1927f65a50629fa9816ec38d2bcc02b9a4712957108f962fd.jpg)

![0276bad929ea4509ce24912190c72bb026762e7429f8253953e6a9c892e267ad.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/0276bad929ea4509ce24912190c72bb026762e7429f8253953e6a9c892e267ad.jpg)

![0662b705cc4056a415b2a0445fd876c2e9161fabaaa082bd6255da6c98fdede6.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/0662b705cc4056a415b2a0445fd876c2e9161fabaaa082bd6255da6c98fdede6.jpg)

![259cbfdbc05e9f27e6c55ac4168d6f94d71ee057e73dcc9fcf5ddb8d01103420.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/259cbfdbc05e9f27e6c55ac4168d6f94d71ee057e73dcc9fcf5ddb8d01103420.jpg)

![29c5b825c8e82cef23ea4c0a35c4e8d492a82104833bee2ac8eebba19943a6bb.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/29c5b825c8e82cef23ea4c0a35c4e8d492a82104833bee2ac8eebba19943a6bb.jpg)

![2d818451fdf1a455836db5e58ab909e34e46da9a52f291a398760231390419bc.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/2d818451fdf1a455836db5e58ab909e34e46da9a52f291a398760231390419bc.jpg)

![47b5a34c0b5b697c4028c801f2652e24190d92fa1c7464cab179415621b8d3ce.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/47b5a34c0b5b697c4028c801f2652e24190d92fa1c7464cab179415621b8d3ce.jpg)

![4e41d2ef1e678b87d2b0cb4fc253788ad5fb2dbd2634925732daa613b234d030.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/4e41d2ef1e678b87d2b0cb4fc253788ad5fb2dbd2634925732daa613b234d030.jpg)

![59d902562f6658200014c3b681c7e7e2dbc186d123158500bd61fc7e1dfed89c.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/59d902562f6658200014c3b681c7e7e2dbc186d123158500bd61fc7e1dfed89c.jpg)

![625d702b26145b0838f9b878aee75ed2c0f6317e745afd36f5697cf55c399fec.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/625d702b26145b0838f9b878aee75ed2c0f6317e745afd36f5697cf55c399fec.jpg)

![84a121ab98f6e63820c2aa881f0d6cf6ddba19e5d5380ccca92bc708fd33450d.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/84a121ab98f6e63820c2aa881f0d6cf6ddba19e5d5380ccca92bc708fd33450d.jpg)

![862d3db8970a7aa4fa99991eaf741d2608f898104152102f4f3c06ecbb6a276e.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/862d3db8970a7aa4fa99991eaf741d2608f898104152102f4f3c06ecbb6a276e.jpg)

![896dd7968a405262900e3d3ae690cc75cc98a14cf586cd47d4ea896742891606.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/896dd7968a405262900e3d3ae690cc75cc98a14cf586cd47d4ea896742891606.jpg)

![968d088023d78d373853d1986b080287078e1d6dcd5e8539651f3a270aa24bca.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/968d088023d78d373853d1986b080287078e1d6dcd5e8539651f3a270aa24bca.jpg)

![bb5ab4411ed553daf3f8339bdecdee592395fa9ddc05aa988b50238d15651fb6.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/bb5ab4411ed553daf3f8339bdecdee592395fa9ddc05aa988b50238d15651fb6.jpg)

![dc11e93e29d049967ac5f9c79172308164422c3ea2442e87df903a5e9bc8f163.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/dc11e93e29d049967ac5f9c79172308164422c3ea2442e87df903a5e9bc8f163.jpg)

![e248093d71107e1a3d5dc85965b0c662ba45ca54ed9eca2018441f0b73c2dbd3.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/e248093d71107e1a3d5dc85965b0c662ba45ca54ed9eca2018441f0b73c2dbd3.jpg)

![e9843d383a76865a929618b9810d0ac0ac9b40275cdc5fac248acc23309102b7.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/e9843d383a76865a929618b9810d0ac0ac9b40275cdc5fac248acc23309102b7.jpg)

![ed1be23a910e2b50cf963e21647e2eff938204b3ce00d071653b1b84f2d96416.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/images/ed1be23a910e2b50cf963e21647e2eff938204b3ce00d071653b1b84f2d96416.jpg)

### Tables

![04753ff6a66e100d6bbe8fbd65fe6fa35cd619a5d2cb2366b2ff3241e75d1e68.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/04753ff6a66e100d6bbe8fbd65fe6fa35cd619a5d2cb2366b2ff3241e75d1e68.jpg)

![3071506c34125b5def00a28418f75dfbddfe1138a8d41e86584bf2dc6205eadf.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/3071506c34125b5def00a28418f75dfbddfe1138a8d41e86584bf2dc6205eadf.jpg)

![3ef25ea917e1baf087c4fada3ca3f83f087fafb6567c860dbff80c11e1e07794.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/3ef25ea917e1baf087c4fada3ca3f83f087fafb6567c860dbff80c11e1e07794.jpg)

![44f0a9beb4809295a088b37093125b498526b78f5e1444a1afa5ed4628998c35.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/44f0a9beb4809295a088b37093125b498526b78f5e1444a1afa5ed4628998c35.jpg)

![5bfabb268623af03d218151201fe140d83b5b4614e44e8262f8c239fb319c232.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/5bfabb268623af03d218151201fe140d83b5b4614e44e8262f8c239fb319c232.jpg)

![73a2524cb11612bec1ab35d297b39a938c4660b04886e9f14f68b0b313270b77.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/73a2524cb11612bec1ab35d297b39a938c4660b04886e9f14f68b0b313270b77.jpg)

![8ef1064f07298a3ca42c1df74bf30adb759dd782deeeb6c37dcfa466bb7fcc82.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/8ef1064f07298a3ca42c1df74bf30adb759dd782deeeb6c37dcfa466bb7fcc82.jpg)

![936a11c01c6bf9c2ea6db927447ffdde4c0ed6118f7c4d6dd5afc97832d07323.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/936a11c01c6bf9c2ea6db927447ffdde4c0ed6118f7c4d6dd5afc97832d07323.jpg)

![968d324f39b65dfedc79573dfde976e432e0b49ee7771805b2b22e7cfa8cf3ce.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/968d324f39b65dfedc79573dfde976e432e0b49ee7771805b2b22e7cfa8cf3ce.jpg)

![9c297e4b6743e26f1327804c49d3c380d97f562dd6afd56a7eaef6ef945ae723.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/9c297e4b6743e26f1327804c49d3c380d97f562dd6afd56a7eaef6ef945ae723.jpg)

![a5d43f078d26d23b94e322e41eb34f6b3bce42e59a7ea68136468d3ab6a8b2cf.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/a5d43f078d26d23b94e322e41eb34f6b3bce42e59a7ea68136468d3ab6a8b2cf.jpg)

![a72f347dd5d1b7072a6cee66aea2be663030d4e0c1e674f3d4f1e92bc622b868.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/a72f347dd5d1b7072a6cee66aea2be663030d4e0c1e674f3d4f1e92bc622b868.jpg)

![a776dc743128ed6bd2b4ae18fd8c375512b67d9872dab9c33871e680872952c2.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/a776dc743128ed6bd2b4ae18fd8c375512b67d9872dab9c33871e680872952c2.jpg)

![bcc3d7b0c0f402e2d29ee067b205ab78a31d116a7fda076c01ce85bba5778b65.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/bcc3d7b0c0f402e2d29ee067b205ab78a31d116a7fda076c01ce85bba5778b65.jpg)

![e56d0b4c6b8f0e6cd5edd2f0828d34a71430d449399db425b5fce011d744c987.jpg](../nips_results/4295_Sparse%20Autoencoders%20Learn%20Monosemantic%20Features%20in%20Vision-Language%20Models/tables/e56d0b4c6b8f0e6cd5edd2f0828d34a71430d449399db425b5fce011d744c987.jpg)

## PBR-SR: Mesh PBR Texture Super Resolution from 2D Image Priors


### Images

![0c4ce932cfda138f8f3cf27dd031ee3d9ea966f35e305c9684358a9d6680b21d.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/images/0c4ce932cfda138f8f3cf27dd031ee3d9ea966f35e305c9684358a9d6680b21d.jpg)

![6a84bf104fb14f88dc8ea20ec2729d12a88e79761f76d07dab71a98a9290ed13.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/images/6a84bf104fb14f88dc8ea20ec2729d12a88e79761f76d07dab71a98a9290ed13.jpg)

![739f459bc61416bb8bcdac38097f45aaea9ba9f8910b69224d8d3aee0c795ee6.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/images/739f459bc61416bb8bcdac38097f45aaea9ba9f8910b69224d8d3aee0c795ee6.jpg)

![8591637a7fa694f48ae69e5f05b438c7fb6bfeaaa398f8966e898181301d01d8.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/images/8591637a7fa694f48ae69e5f05b438c7fb6bfeaaa398f8966e898181301d01d8.jpg)

![abc87df774cd35fb601a4ddd79d07e14a32e60b6b7a66aebd072c087b326e57f.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/images/abc87df774cd35fb601a4ddd79d07e14a32e60b6b7a66aebd072c087b326e57f.jpg)

![b5486cf9512faeb8037eaf22a0f5e46d81000526189912b228e6ddce0c8f6e27.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/images/b5486cf9512faeb8037eaf22a0f5e46d81000526189912b228e6ddce0c8f6e27.jpg)

![cf7a709c6d18eca55b66cc54d1d5d64ace8460adfa33eb86c2f2508fb4bc712c.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/images/cf7a709c6d18eca55b66cc54d1d5d64ace8460adfa33eb86c2f2508fb4bc712c.jpg)

![f74b1fd2f94de8d54bf589c8276663c890ef07fd7a95f9d38eaf141bcb2fe6fb.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/images/f74b1fd2f94de8d54bf589c8276663c890ef07fd7a95f9d38eaf141bcb2fe6fb.jpg)

### Tables

![1bffa871052d2d031bfa003987de51c1a34bbd075b531e3f87c24f9b93793214.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/tables/1bffa871052d2d031bfa003987de51c1a34bbd075b531e3f87c24f9b93793214.jpg)

![56b55fc4a707cb70f71ebac0337dbab9f2752115f926d6a43437f3a38cebca72.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/tables/56b55fc4a707cb70f71ebac0337dbab9f2752115f926d6a43437f3a38cebca72.jpg)

![6eaba2807b88053895c46732b72e6db57c4d5baaeb3afc0dd804b6c33c571da1.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/tables/6eaba2807b88053895c46732b72e6db57c4d5baaeb3afc0dd804b6c33c571da1.jpg)

![9c34a8098fc14cb005c22f8ca8ca0c2668bfe740623c3737b0dee5a2f80ac850.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/tables/9c34a8098fc14cb005c22f8ca8ca0c2668bfe740623c3737b0dee5a2f80ac850.jpg)

![9dbdf1d5b1f0af457bd039df8697314bc10e5b247fb4f823ed313c90884d3c4e.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/tables/9dbdf1d5b1f0af457bd039df8697314bc10e5b247fb4f823ed313c90884d3c4e.jpg)

![a3378bfd811eaf1b4825765fae072abdca30ec36350bc887b1b925c66c73feb1.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/tables/a3378bfd811eaf1b4825765fae072abdca30ec36350bc887b1b925c66c73feb1.jpg)

![b09bf0d71e55fe533fb144edf4942e006cc3db65b272925e0604385b4e978320.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/tables/b09bf0d71e55fe533fb144edf4942e006cc3db65b272925e0604385b4e978320.jpg)

![b64ccefe0e53e6eb019bb50cfe9dc506dcb10fae3033309c4f67271bf6976078.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/tables/b64ccefe0e53e6eb019bb50cfe9dc506dcb10fae3033309c4f67271bf6976078.jpg)

![ba2272ed02c45787b6510b37066d4decf60db759b2ab6e679f0006e44b14efcf.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/tables/ba2272ed02c45787b6510b37066d4decf60db759b2ab6e679f0006e44b14efcf.jpg)

![bdf43033fa684bb30c00d73765a43bec162259aa389155bac8e5ec167375b43c.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/tables/bdf43033fa684bb30c00d73765a43bec162259aa389155bac8e5ec167375b43c.jpg)

![ff02861ec7e35427fea97b458636b315796f0b4df4fc7ff27afc82aa0aff69ce.jpg](../nips_results/4296_PBR-SR_%20Mesh%20PBR%20Texture%20Super%20Resolution%20from%202D%20Image%20Priors/tables/ff02861ec7e35427fea97b458636b315796f0b4df4fc7ff27afc82aa0aff69ce.jpg)

## Assignments for Congestion-Averse Agents: Seeking Competitive and Envy-Free Solutions


### Images

![064aa8241e954d054c5e34ea418343717357772c72daa012658cd59ee82101cf.jpg](../nips_results/4297_Assignments%20for%20Congestion-Averse%20Agents_%20Seeking%20Competitive%20and%20Envy-Free%20Solutions/images/064aa8241e954d054c5e34ea418343717357772c72daa012658cd59ee82101cf.jpg)

![17cf313476b99012d771f6527bb6de6850e8edac391a93384cc660cd894e75a3.jpg](../nips_results/4297_Assignments%20for%20Congestion-Averse%20Agents_%20Seeking%20Competitive%20and%20Envy-Free%20Solutions/images/17cf313476b99012d771f6527bb6de6850e8edac391a93384cc660cd894e75a3.jpg)

![b9f92c0699944081f7f0b76fb76163456f159ee7aa7ea418ff0176fc56eaa0a6.jpg](../nips_results/4297_Assignments%20for%20Congestion-Averse%20Agents_%20Seeking%20Competitive%20and%20Envy-Free%20Solutions/images/b9f92c0699944081f7f0b76fb76163456f159ee7aa7ea418ff0176fc56eaa0a6.jpg)

![bbd8f01bcc7c35a3a4e45b4edf0767382abc626c14e0fb0c45ef2e05c4b5dba5.jpg](../nips_results/4297_Assignments%20for%20Congestion-Averse%20Agents_%20Seeking%20Competitive%20and%20Envy-Free%20Solutions/images/bbd8f01bcc7c35a3a4e45b4edf0767382abc626c14e0fb0c45ef2e05c4b5dba5.jpg)

### Tables

![01acb7aa64705a090bda2bf5b5dae94e431f35f5685bd99d04c3c5b196a422a9.jpg](../nips_results/4297_Assignments%20for%20Congestion-Averse%20Agents_%20Seeking%20Competitive%20and%20Envy-Free%20Solutions/tables/01acb7aa64705a090bda2bf5b5dae94e431f35f5685bd99d04c3c5b196a422a9.jpg)

![565cb047959119b92ec713cdb94bf16626213094eb52d6e620a0510f0c05e8e8.jpg](../nips_results/4297_Assignments%20for%20Congestion-Averse%20Agents_%20Seeking%20Competitive%20and%20Envy-Free%20Solutions/tables/565cb047959119b92ec713cdb94bf16626213094eb52d6e620a0510f0c05e8e8.jpg)

![5664b4dde37ac0aeb5cc041e8b7a5a9e78d0fb68efa762d1474de15bcc9720b0.jpg](../nips_results/4297_Assignments%20for%20Congestion-Averse%20Agents_%20Seeking%20Competitive%20and%20Envy-Free%20Solutions/tables/5664b4dde37ac0aeb5cc041e8b7a5a9e78d0fb68efa762d1474de15bcc9720b0.jpg)

![cf8340b46e0e7fd7370e6b9512564c418cfde6aa0d35159cdad798e826b4aa58.jpg](../nips_results/4297_Assignments%20for%20Congestion-Averse%20Agents_%20Seeking%20Competitive%20and%20Envy-Free%20Solutions/tables/cf8340b46e0e7fd7370e6b9512564c418cfde6aa0d35159cdad798e826b4aa58.jpg)

## Router-R1: Teaching LLMs Multi-Round Routing and Aggregation via Reinforcement Learning


### Images

![05c8e4a32c85e98995cf737ba92d1abc7da06fd11902811f86d1c89320c65ddf.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/images/05c8e4a32c85e98995cf737ba92d1abc7da06fd11902811f86d1c89320c65ddf.jpg)

![23117b4b3e4cd28d67655c2439b8b97a79a4e9aa3a91d87c25c8a10159da682d.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/images/23117b4b3e4cd28d67655c2439b8b97a79a4e9aa3a91d87c25c8a10159da682d.jpg)

![4eb9c52d298dfef1b1ab8fabc4177cfb92e52eabbb8afd1026ceb28e61ac0428.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/images/4eb9c52d298dfef1b1ab8fabc4177cfb92e52eabbb8afd1026ceb28e61ac0428.jpg)

![e197ffa0cc3302d78f1c52d8330ebb19a280edd7b0b881556b1cbd280b7caf0d.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/images/e197ffa0cc3302d78f1c52d8330ebb19a280edd7b0b881556b1cbd280b7caf0d.jpg)

### Tables

![02550941711baa7e5411e3dc87b86dfa45a6e4ff84e44480485ce9bd8f266f4d.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/tables/02550941711baa7e5411e3dc87b86dfa45a6e4ff84e44480485ce9bd8f266f4d.jpg)

![288a612677bf5f79f7c42eda91a045d2955289c725ebd5e1367be9d5dae77721.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/tables/288a612677bf5f79f7c42eda91a045d2955289c725ebd5e1367be9d5dae77721.jpg)

![5a776df380e6ab723a1d15a2b9b42cac2500e2ecb69e494179afb6813e874d6f.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/tables/5a776df380e6ab723a1d15a2b9b42cac2500e2ecb69e494179afb6813e874d6f.jpg)

![693443d915929a068bf151c3749efa7fc6858f144f07e5af47c88dcbb09b542b.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/tables/693443d915929a068bf151c3749efa7fc6858f144f07e5af47c88dcbb09b542b.jpg)

![7ba71124734149c361b594fcba96e2de856620471cb40fa531e1dbbbb5efd0cd.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/tables/7ba71124734149c361b594fcba96e2de856620471cb40fa531e1dbbbb5efd0cd.jpg)

![7eb9da4eea02bf8dc9cc91fac32887ef9576b20e1e9fb22403c045fc7d22fc2d.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/tables/7eb9da4eea02bf8dc9cc91fac32887ef9576b20e1e9fb22403c045fc7d22fc2d.jpg)

![dff5673e570fe12695e96ab46bb1aff37bc7a662f97a4a06bc7fc6521e3cbdb1.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/tables/dff5673e570fe12695e96ab46bb1aff37bc7a662f97a4a06bc7fc6521e3cbdb1.jpg)

![f25134b2b8ce1fbb4c685371e25f81bccc27b155cc2c8151eeb932e385b5d021.jpg](../nips_results/4298_Router-R1_%20Teaching%20LLMs%20Multi-Round%20Routing%20and%20Aggregation%20via%20Reinforcement%20Learning/tables/f25134b2b8ce1fbb4c685371e25f81bccc27b155cc2c8151eeb932e385b5d021.jpg)

## Are Language Models Efficient Reasoners? A Perspective from Logic Programming


### Images

![6b5d84923e3f0de5e646c9e79c1f2399d26ec03df4bcf119c58ffcd3c833e71e.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/images/6b5d84923e3f0de5e646c9e79c1f2399d26ec03df4bcf119c58ffcd3c833e71e.jpg)

![9cc62161d200f8f84a732eb9b29ae893b4b3ceb8f05874fed4dc7453e486d49a.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/images/9cc62161d200f8f84a732eb9b29ae893b4b3ceb8f05874fed4dc7453e486d49a.jpg)

![a631170932534854fc098d88ada5662f5b6607736a397bfe3332c0b10b65dd52.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/images/a631170932534854fc098d88ada5662f5b6607736a397bfe3332c0b10b65dd52.jpg)

![b7ab03eafdab5e0636553c668c976b369789af6da0530444ead895783008120c.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/images/b7ab03eafdab5e0636553c668c976b369789af6da0530444ead895783008120c.jpg)

![bf3e67944e00b7d5fd5ffcd2e7237ccd3fc37901fe60ebef5e8316df363af67f.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/images/bf3e67944e00b7d5fd5ffcd2e7237ccd3fc37901fe60ebef5e8316df363af67f.jpg)

![d53049e7ebcc180ee57f3d0099b4c44a5729d01798ffb32ef3523ad4f782f547.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/images/d53049e7ebcc180ee57f3d0099b4c44a5729d01798ffb32ef3523ad4f782f547.jpg)

### Tables

![3026cb214347cbd875cade9d65ec33a770851d99baa9ff85be751da45503ae05.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/tables/3026cb214347cbd875cade9d65ec33a770851d99baa9ff85be751da45503ae05.jpg)

![4ebaea4995b9713bf8dea8d882e26f747b190f7c27b2167cde9fd929d6664219.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/tables/4ebaea4995b9713bf8dea8d882e26f747b190f7c27b2167cde9fd929d6664219.jpg)

![8d2b1501a6152f8b7caf126a481cbb6cadc6205d2ce503639eb6a00347476b06.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/tables/8d2b1501a6152f8b7caf126a481cbb6cadc6205d2ce503639eb6a00347476b06.jpg)

![8f302e13e2d47f6bb8c07f21996c45dede5b0df2d4185f9ad7839cd5f62a31a7.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/tables/8f302e13e2d47f6bb8c07f21996c45dede5b0df2d4185f9ad7839cd5f62a31a7.jpg)

![bad4ea06f0fcad2bfa6f11c5c9308bc637d736a5a0582cc9f40128a4b630eb3a.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/tables/bad4ea06f0fcad2bfa6f11c5c9308bc637d736a5a0582cc9f40128a4b630eb3a.jpg)

![d78c027cc9bfbf6f334c47fbd75722944ad452dc77bb719cd0de2c6b0065dc9d.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/tables/d78c027cc9bfbf6f334c47fbd75722944ad452dc77bb719cd0de2c6b0065dc9d.jpg)

![ef18cc0191c23dd96e585ecc0b051a55a8bbf81660f97bcc908300d5810591cc.jpg](../nips_results/4299_Are%20Language%20Models%20Efficient%20Reasoners_%20A%20Perspective%20from%20Logic%20Programming/tables/ef18cc0191c23dd96e585ecc0b051a55a8bbf81660f97bcc908300d5810591cc.jpg)

## FreqExit: Enabling Early-Exit Inference for Visual Autoregressive Models via Frequency-Aware Guidance


### Images

![4708fab488ee4e234a396342a3142d0fad955fd5acfbf3169a07cba7f9c14007.jpg](../nips_results/4300_FreqExit_%20Enabling%20Early-Exit%20Inference%20for%20Visual%20Autoregressive%20Models%20via%20Frequency-Aware%20Guidanc/images/4708fab488ee4e234a396342a3142d0fad955fd5acfbf3169a07cba7f9c14007.jpg)

![613ca1adb2f09a3c34000b2ff5c5e533c6fba56823863a31a04b30904c4830ab.jpg](../nips_results/4300_FreqExit_%20Enabling%20Early-Exit%20Inference%20for%20Visual%20Autoregressive%20Models%20via%20Frequency-Aware%20Guidanc/images/613ca1adb2f09a3c34000b2ff5c5e533c6fba56823863a31a04b30904c4830ab.jpg)

![8178bd269619ff0fd8114b6d7731b988158d704fb3037d124535d518721f580b.jpg](../nips_results/4300_FreqExit_%20Enabling%20Early-Exit%20Inference%20for%20Visual%20Autoregressive%20Models%20via%20Frequency-Aware%20Guidanc/images/8178bd269619ff0fd8114b6d7731b988158d704fb3037d124535d518721f580b.jpg)

![8b8582ccc73944fa299a6b803e42367fed1982bf1e32f7b2fcbf0d1be7877885.jpg](../nips_results/4300_FreqExit_%20Enabling%20Early-Exit%20Inference%20for%20Visual%20Autoregressive%20Models%20via%20Frequency-Aware%20Guidanc/images/8b8582ccc73944fa299a6b803e42367fed1982bf1e32f7b2fcbf0d1be7877885.jpg)

![950b67628957cceb03c936d2f036667d1be46f048989ac09c0502b8db51c2f9c.jpg](../nips_results/4300_FreqExit_%20Enabling%20Early-Exit%20Inference%20for%20Visual%20Autoregressive%20Models%20via%20Frequency-Aware%20Guidanc/images/950b67628957cceb03c936d2f036667d1be46f048989ac09c0502b8db51c2f9c.jpg)

### Tables

![121a9b8ef1d3cedfb6ef8c8806863560d29e7076f421c091c309a2c1969fe43d.jpg](../nips_results/4300_FreqExit_%20Enabling%20Early-Exit%20Inference%20for%20Visual%20Autoregressive%20Models%20via%20Frequency-Aware%20Guidanc/tables/121a9b8ef1d3cedfb6ef8c8806863560d29e7076f421c091c309a2c1969fe43d.jpg)

![28b76794488a452592f15b3068d9c5fde9d00c3e47c801e6a6444340f83a000f.jpg](../nips_results/4300_FreqExit_%20Enabling%20Early-Exit%20Inference%20for%20Visual%20Autoregressive%20Models%20via%20Frequency-Aware%20Guidanc/tables/28b76794488a452592f15b3068d9c5fde9d00c3e47c801e6a6444340f83a000f.jpg)

![982d3707334d7ad45d2f714a2da420812a3c35e06e8cdd306f5906e527b97137.jpg](../nips_results/4300_FreqExit_%20Enabling%20Early-Exit%20Inference%20for%20Visual%20Autoregressive%20Models%20via%20Frequency-Aware%20Guidanc/tables/982d3707334d7ad45d2f714a2da420812a3c35e06e8cdd306f5906e527b97137.jpg)

![f9435943bdb471ec1efb82e348ae8a4e804825be3a950df4aadba48ec5b41b95.jpg](../nips_results/4300_FreqExit_%20Enabling%20Early-Exit%20Inference%20for%20Visual%20Autoregressive%20Models%20via%20Frequency-Aware%20Guidanc/tables/f9435943bdb471ec1efb82e348ae8a4e804825be3a950df4aadba48ec5b41b95.jpg)

## StreamBridge: Turning Your Offline Video Large Language Model into a Proactive Streaming Assistant


### Images

![0c473dbe50ee8f4caf2dbeb6d8431bf57e63917da81b05cffb9c696e4a221e72.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/images/0c473dbe50ee8f4caf2dbeb6d8431bf57e63917da81b05cffb9c696e4a221e72.jpg)

![a9498d389c91f3361176526003ca25f04af608abbae99ebf3d0059607c3d1aa6.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/images/a9498d389c91f3361176526003ca25f04af608abbae99ebf3d0059607c3d1aa6.jpg)

![c3809021a6caf2c93a176161efc8202f9736ef696e18d754354f7954c47e003c.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/images/c3809021a6caf2c93a176161efc8202f9736ef696e18d754354f7954c47e003c.jpg)

![cc02752deb61e8cb8260cd1c631120717da6ed0e4a3cf4143b41f66604b007a9.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/images/cc02752deb61e8cb8260cd1c631120717da6ed0e4a3cf4143b41f66604b007a9.jpg)

![dd5034742405e26fa2a8f174aafd71e619753959748037f975bf181635f75acf.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/images/dd5034742405e26fa2a8f174aafd71e619753959748037f975bf181635f75acf.jpg)

### Tables

![9592378e9c9723ecc08b696f69d510197d0f5ae2ff0a71bf53a364187126e4fd.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/tables/9592378e9c9723ecc08b696f69d510197d0f5ae2ff0a71bf53a364187126e4fd.jpg)

![9c2598dc2496a282c1973f96999cd24ebb12dd9b634f47acd7bd830a429a2019.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/tables/9c2598dc2496a282c1973f96999cd24ebb12dd9b634f47acd7bd830a429a2019.jpg)

![b52ee41e20c579444e08426a8bc5bfe3f074e0170bb87c1a0b0bab5a77096eb9.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/tables/b52ee41e20c579444e08426a8bc5bfe3f074e0170bb87c1a0b0bab5a77096eb9.jpg)

![c684cf5478f48fbf7419ba329dd2fef4d14f7bf631a9177a928dde43ad47d6b6.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/tables/c684cf5478f48fbf7419ba329dd2fef4d14f7bf631a9177a928dde43ad47d6b6.jpg)

![d5a8cad1ba19363bd4bb39b1d9ea51dc4388b22c7eb9c87ec5e3cccf18a8d5bc.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/tables/d5a8cad1ba19363bd4bb39b1d9ea51dc4388b22c7eb9c87ec5e3cccf18a8d5bc.jpg)

![d8eb9a844f60ae02dffb6ccb0dc0733e527e6a9c4de37fd3a49117dde587c65f.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/tables/d8eb9a844f60ae02dffb6ccb0dc0733e527e6a9c4de37fd3a49117dde587c65f.jpg)

![d9b8666f324912c2f13732ea5f9d066969f9ffa48decc7ae46036fb55ea9f86c.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/tables/d9b8666f324912c2f13732ea5f9d066969f9ffa48decc7ae46036fb55ea9f86c.jpg)

![e5991950cf188a6834ee2b11f20f78c7f751ec0fd6b02ed38d12d44293e02192.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/tables/e5991950cf188a6834ee2b11f20f78c7f751ec0fd6b02ed38d12d44293e02192.jpg)

![f118839c77075646b48016372d0c53d4503dda3e5b454bfba29d29a5e509afd3.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/tables/f118839c77075646b48016372d0c53d4503dda3e5b454bfba29d29a5e509afd3.jpg)

![fdd74d509b34fc07f31c9c02336b8012438f0b79aee775afabeb8837f5247ad2.jpg](../nips_results/4301_StreamBridge_%20Turning%20Your%20Offline%20Video%20Large%20Language%20Model%20into%20a%20Proactive%20Streaming%20Assistant/tables/fdd74d509b34fc07f31c9c02336b8012438f0b79aee775afabeb8837f5247ad2.jpg)

## Balancing Positive and Negative Classification Error Rates in Positive-Unlabeled Learning


### Images

![2aa899dcbfaf428211eb9f53155fff20aa445bd6fcac56b2799bc0e2a0360a4f.jpg](../nips_results/4302_Balancing%20Positive%20and%20Negative%20Classification%20Error%20Rates%20in%20Positive-Unlabeled%20Learning/images/2aa899dcbfaf428211eb9f53155fff20aa445bd6fcac56b2799bc0e2a0360a4f.jpg)

![41626212ef45ca71e186a40fc7a502d9ec720616d62e532d7d86e7b284442349.jpg](../nips_results/4302_Balancing%20Positive%20and%20Negative%20Classification%20Error%20Rates%20in%20Positive-Unlabeled%20Learning/images/41626212ef45ca71e186a40fc7a502d9ec720616d62e532d7d86e7b284442349.jpg)

![8d8d306ede819ccc420fdad3eaafc92840cb6e89de276f9756e35d62a2b87d56.jpg](../nips_results/4302_Balancing%20Positive%20and%20Negative%20Classification%20Error%20Rates%20in%20Positive-Unlabeled%20Learning/images/8d8d306ede819ccc420fdad3eaafc92840cb6e89de276f9756e35d62a2b87d56.jpg)

![8db2ad07df49ca12a7a11f3aac4ce9631219ccef7134cf68efcc100e7df118b2.jpg](../nips_results/4302_Balancing%20Positive%20and%20Negative%20Classification%20Error%20Rates%20in%20Positive-Unlabeled%20Learning/images/8db2ad07df49ca12a7a11f3aac4ce9631219ccef7134cf68efcc100e7df118b2.jpg)

![e8e3214087dadbcd8a6ecc8467ca1825f6a18dbd65c25f52bd1072f936b31c09.jpg](../nips_results/4302_Balancing%20Positive%20and%20Negative%20Classification%20Error%20Rates%20in%20Positive-Unlabeled%20Learning/images/e8e3214087dadbcd8a6ecc8467ca1825f6a18dbd65c25f52bd1072f936b31c09.jpg)

### Tables

![284f4ab5f826c6e6af101fd221a8b2d21fc2a53450c8b0389e28baf87aa2f0c0.jpg](../nips_results/4302_Balancing%20Positive%20and%20Negative%20Classification%20Error%20Rates%20in%20Positive-Unlabeled%20Learning/tables/284f4ab5f826c6e6af101fd221a8b2d21fc2a53450c8b0389e28baf87aa2f0c0.jpg)

![28eb5687cde3c0e19a1e55bd46216d6ec04b1ed5229d716c48bab4886b3f0d97.jpg](../nips_results/4302_Balancing%20Positive%20and%20Negative%20Classification%20Error%20Rates%20in%20Positive-Unlabeled%20Learning/tables/28eb5687cde3c0e19a1e55bd46216d6ec04b1ed5229d716c48bab4886b3f0d97.jpg)

![4138fa5b87ed3ebbcd2834d1623e2cfa0723abbc908f33d8041fbbba630d57ca.jpg](../nips_results/4302_Balancing%20Positive%20and%20Negative%20Classification%20Error%20Rates%20in%20Positive-Unlabeled%20Learning/tables/4138fa5b87ed3ebbcd2834d1623e2cfa0723abbc908f33d8041fbbba630d57ca.jpg)

![74f118f193eadddf4fe998d641d5fb731caee1f8bc2998fa97500e8a6a3d3175.jpg](../nips_results/4302_Balancing%20Positive%20and%20Negative%20Classification%20Error%20Rates%20in%20Positive-Unlabeled%20Learning/tables/74f118f193eadddf4fe998d641d5fb731caee1f8bc2998fa97500e8a6a3d3175.jpg)

![c26016566abdf66cfb773f1f97bcf477eb04e269ada30de5db49550d800816af.jpg](../nips_results/4302_Balancing%20Positive%20and%20Negative%20Classification%20Error%20Rates%20in%20Positive-Unlabeled%20Learning/tables/c26016566abdf66cfb773f1f97bcf477eb04e269ada30de5db49550d800816af.jpg)

## Lookahead Routing for Large Language Models


### Images

![1fe40da20276230f9a2a73e093caec8e3f488bbb2e6e05f1c978265fd711a1e2.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/images/1fe40da20276230f9a2a73e093caec8e3f488bbb2e6e05f1c978265fd711a1e2.jpg)

![594be117db26d98032d44884cea1400634a15698518dd4661c1f1b876b6007fd.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/images/594be117db26d98032d44884cea1400634a15698518dd4661c1f1b876b6007fd.jpg)

![76e004bcb908038235a5084407280f744c1dcfb5635ad22a87bf9fa4066f5dbd.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/images/76e004bcb908038235a5084407280f744c1dcfb5635ad22a87bf9fa4066f5dbd.jpg)

![7ff3360e5c9d0f29271886a1966dbcdd82a8bbffa0c293c3a290f0dd6852d227.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/images/7ff3360e5c9d0f29271886a1966dbcdd82a8bbffa0c293c3a290f0dd6852d227.jpg)

![df43b4f73f7eb1ac989875716fc9663a472807f3e94f10897a71ba6786e57296.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/images/df43b4f73f7eb1ac989875716fc9663a472807f3e94f10897a71ba6786e57296.jpg)

![e65b1a2897a9b0d4e2202d4ac93363130acd99eec8ff8feef7a97ebb6885711e.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/images/e65b1a2897a9b0d4e2202d4ac93363130acd99eec8ff8feef7a97ebb6885711e.jpg)

### Tables

![5dec5ef9fa0bfccaedceaa01971c4ec490ca43875949471507a19ca228dc6a1e.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/tables/5dec5ef9fa0bfccaedceaa01971c4ec490ca43875949471507a19ca228dc6a1e.jpg)

![6db395060d89c1427c9c7eb76eb410c7a7bdea7733355971c4378b45eeb181c8.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/tables/6db395060d89c1427c9c7eb76eb410c7a7bdea7733355971c4378b45eeb181c8.jpg)

![96a21c4eff2bdee0921d6175b4c8ba8f805b6fce9a6b0478ddaa045f3c2bcd0d.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/tables/96a21c4eff2bdee0921d6175b4c8ba8f805b6fce9a6b0478ddaa045f3c2bcd0d.jpg)

![a59c8b4c4f881fdf1265070a1dae11fa7b6becf9111fc2c749ebe45c8eb1740f.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/tables/a59c8b4c4f881fdf1265070a1dae11fa7b6becf9111fc2c749ebe45c8eb1740f.jpg)

![ca28a602cb9bd343d5511a1e57990a33cd3b304c79a2579a3cb66542b5d35b21.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/tables/ca28a602cb9bd343d5511a1e57990a33cd3b304c79a2579a3cb66542b5d35b21.jpg)

![cae80da8b93963cc8f3895e00832651b30c8d31272a9ac83993299f3bc853cbe.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/tables/cae80da8b93963cc8f3895e00832651b30c8d31272a9ac83993299f3bc853cbe.jpg)

![d8f34f9fc591c8319d9478c1fab432bc7a2c08380977659da85e9c1235ff0117.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/tables/d8f34f9fc591c8319d9478c1fab432bc7a2c08380977659da85e9c1235ff0117.jpg)

![d90edc8d8f9473d799182aecdb040560ee00ce5e979b1d4b7349bddc0d78314a.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/tables/d90edc8d8f9473d799182aecdb040560ee00ce5e979b1d4b7349bddc0d78314a.jpg)

![ef6988924814917bba3f7e8de0bfb106f8fec10ff52a4d0c78f53eb19140298e.jpg](../nips_results/4303_Lookahead%20Routing%20for%20Large%20Language%20Models/tables/ef6988924814917bba3f7e8de0bfb106f8fec10ff52a4d0c78f53eb19140298e.jpg)

## What Do Latent Action Models Actually Learn?


### Images

![4491246fe48469ff9def345b5a9a494a90b81d93020a77d93a4f7bacffb368cb.jpg](../nips_results/4304_What%20Do%20Latent%20Action%20Models%20Actually%20Learn_/images/4491246fe48469ff9def345b5a9a494a90b81d93020a77d93a4f7bacffb368cb.jpg)

![5d4b6bc29e4fb2d65fc0268856e302ff10ae57a8e7bc1a8565dd06147848445a.jpg](../nips_results/4304_What%20Do%20Latent%20Action%20Models%20Actually%20Learn_/images/5d4b6bc29e4fb2d65fc0268856e302ff10ae57a8e7bc1a8565dd06147848445a.jpg)

![d146d848fce51e6994d4aa1895c65f0c3d45dec9c3f041b1a36fa0a84b49452e.jpg](../nips_results/4304_What%20Do%20Latent%20Action%20Models%20Actually%20Learn_/images/d146d848fce51e6994d4aa1895c65f0c3d45dec9c3f041b1a36fa0a84b49452e.jpg)

![f0c9740edbf6c4cce59cd1510477511311d8b5d964817db5aec140fc3253ab53.jpg](../nips_results/4304_What%20Do%20Latent%20Action%20Models%20Actually%20Learn_/images/f0c9740edbf6c4cce59cd1510477511311d8b5d964817db5aec140fc3253ab53.jpg)

### Tables

![fab3a2f95ff1f6374139282d90e150faca9e2f7759ab114969a13392e280f15c.jpg](../nips_results/4304_What%20Do%20Latent%20Action%20Models%20Actually%20Learn_/tables/fab3a2f95ff1f6374139282d90e150faca9e2f7759ab114969a13392e280f15c.jpg)

## RelationAdapter: Learning and Transferring Visual Relation with Diffusion Transformers


### Images

![0674e434e62f98cc5e5f610654e8216c3f0a43081e6473931d309f67d527103d.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/0674e434e62f98cc5e5f610654e8216c3f0a43081e6473931d309f67d527103d.jpg)

![0a7bb37e4b0cee5d8f3506ffed8529741798e07e7faa9da45a04c61409fe886d.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/0a7bb37e4b0cee5d8f3506ffed8529741798e07e7faa9da45a04c61409fe886d.jpg)

![160922a09ece546fecc9133bcd51d9a76e2fdf9fa5492aead445d35c9ba00534.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/160922a09ece546fecc9133bcd51d9a76e2fdf9fa5492aead445d35c9ba00534.jpg)

![21b0a79489077f574755bb3501dbeaabaf93b8f93f3c5325831c94db2ba712b2.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/21b0a79489077f574755bb3501dbeaabaf93b8f93f3c5325831c94db2ba712b2.jpg)

![36fa41ee59042898a2d6539bfd60e4142d9be3f9ef49c19df82206240cc51ed4.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/36fa41ee59042898a2d6539bfd60e4142d9be3f9ef49c19df82206240cc51ed4.jpg)

![3bfc40817b8aa316ec5c8e5d349a6fc585e043ed184cd0337a83d018a6adaa0b.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/3bfc40817b8aa316ec5c8e5d349a6fc585e043ed184cd0337a83d018a6adaa0b.jpg)

![4bbefe0fc92aa62630b7fdeb793d41707c99c3858ad974477021aeae6be39f3c.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/4bbefe0fc92aa62630b7fdeb793d41707c99c3858ad974477021aeae6be39f3c.jpg)

![64d2a9680e63bad4c3c778045b833f4b5861d42da0f4228c66c8a9e68a8e9302.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/64d2a9680e63bad4c3c778045b833f4b5861d42da0f4228c66c8a9e68a8e9302.jpg)

![7e2fbd54910d8284d5e9f89b721ffa2141bbde63357d4837bd48a7aa8e423a50.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/7e2fbd54910d8284d5e9f89b721ffa2141bbde63357d4837bd48a7aa8e423a50.jpg)

![af8bebc380db4b6e9e9066cbb62527549ada5cb854fbe7ce31f9177ee06455fb.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/af8bebc380db4b6e9e9066cbb62527549ada5cb854fbe7ce31f9177ee06455fb.jpg)

![c7e79ccb212d77de711db2c7d18bee91de5313060f40058e381d9037c2001577.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/c7e79ccb212d77de711db2c7d18bee91de5313060f40058e381d9037c2001577.jpg)

![e6abd99aa188eea823bd964358f726ec94f55c53b7532be2a0d2ff4854e409cc.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/e6abd99aa188eea823bd964358f726ec94f55c53b7532be2a0d2ff4854e409cc.jpg)

![ec200a2add7b5502ec841db7d5afea5f65f5d4e20c2921ff9e79e204d44a2375.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/images/ec200a2add7b5502ec841db7d5afea5f65f5d4e20c2921ff9e79e204d44a2375.jpg)

### Tables

![0800bdaf4b3bba2bc743f206aa13fb4d960e0d86cff3ba451b2a36848c3356a2.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/tables/0800bdaf4b3bba2bc743f206aa13fb4d960e0d86cff3ba451b2a36848c3356a2.jpg)

![12152c4087321e3d005de70b82ea72afdf1a14ede4c6b92818ade3d28b64c803.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/tables/12152c4087321e3d005de70b82ea72afdf1a14ede4c6b92818ade3d28b64c803.jpg)

![15d0846c34ab75632a26857d650ffaab8aa744fc69e1adf61da1e1ed7d7f6680.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/tables/15d0846c34ab75632a26857d650ffaab8aa744fc69e1adf61da1e1ed7d7f6680.jpg)

![942d49fe18928174d0d212defaf376152a21ed52995dda5ca16ee31cbb7c878a.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/tables/942d49fe18928174d0d212defaf376152a21ed52995dda5ca16ee31cbb7c878a.jpg)

![975e108bdcdf1385806536936c40e6dc32f7caf1921644f4a9af578a6716e3ba.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/tables/975e108bdcdf1385806536936c40e6dc32f7caf1921644f4a9af578a6716e3ba.jpg)

![a15de39ba39d53687a327d10e2de10c987d4ce0400b52e52ec299aeef76b6feb.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/tables/a15de39ba39d53687a327d10e2de10c987d4ce0400b52e52ec299aeef76b6feb.jpg)

![ab495642342e5a3c84247bbddb633472c8770a8fab4bc2eff5a6a4763c3b3b2e.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/tables/ab495642342e5a3c84247bbddb633472c8770a8fab4bc2eff5a6a4763c3b3b2e.jpg)

![b5521c01763d6c42b7d916ae1b562eaf9b2848a2b3f751fb89a07ec7a22f6bac.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/tables/b5521c01763d6c42b7d916ae1b562eaf9b2848a2b3f751fb89a07ec7a22f6bac.jpg)

![d80cd200adf43839b243aecf01d3009e69c35c3c10782f794644715ab985d853.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/tables/d80cd200adf43839b243aecf01d3009e69c35c3c10782f794644715ab985d853.jpg)

![f503ff223be1f42663c6e838234db59298baf210d854103727ec8a883e4c32d0.jpg](../nips_results/4305_RelationAdapter_%20Learning%20and%20Transferring%20Visual%20Relation%20with%20Diffusion%20Transformers/tables/f503ff223be1f42663c6e838234db59298baf210d854103727ec8a883e4c32d0.jpg)

## Discovering Data Structures: Nearest Neighbor Search and Beyond


### Images

![004b43bd43eccf9fd2d6f33b2b319772e9e1db598aace7baa7483285bacfffb3.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/004b43bd43eccf9fd2d6f33b2b319772e9e1db598aace7baa7483285bacfffb3.jpg)

![00acea5e8183b9281471bb20633c1ff42a67d2f9ee7d305175af5e079876aaaf.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/00acea5e8183b9281471bb20633c1ff42a67d2f9ee7d305175af5e079876aaaf.jpg)

![0e2730de904662eb9a9d27d7ffca64e9373e02bf668183cca4c4d91bfd8e8aa1.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/0e2730de904662eb9a9d27d7ffca64e9373e02bf668183cca4c4d91bfd8e8aa1.jpg)

![10e6baf5e503c7bf58609dcbad53fa65ea2dda20932461392215ab868a932c99.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/10e6baf5e503c7bf58609dcbad53fa65ea2dda20932461392215ab868a932c99.jpg)

![18aabb140ba480a65aa468f9b389d91cfe6caf6642cc6f4d190884a5e0004651.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/18aabb140ba480a65aa468f9b389d91cfe6caf6642cc6f4d190884a5e0004651.jpg)

![1dcbc33772658db09ff7a80dff63dad831da8079bf315d9ddb6467a16a485cca.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/1dcbc33772658db09ff7a80dff63dad831da8079bf315d9ddb6467a16a485cca.jpg)

![303c340c34606e0d3b0e80444eeab0d120c7e71a0d5951b62b33baf8ccffd95e.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/303c340c34606e0d3b0e80444eeab0d120c7e71a0d5951b62b33baf8ccffd95e.jpg)

![331df6d874d8d5d8abdaf73a10bd9572e8ee41390d76cc2c313fba288466cc86.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/331df6d874d8d5d8abdaf73a10bd9572e8ee41390d76cc2c313fba288466cc86.jpg)

![36e1f9b0d28bb02c8dc699990b199ab5ecc46db382df01389a4e11e56f56e520.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/36e1f9b0d28bb02c8dc699990b199ab5ecc46db382df01389a4e11e56f56e520.jpg)

![40765398bf8a58926c296857eff6052d62e4a1ce98e301ae4e148bb59f9c8b46.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/40765398bf8a58926c296857eff6052d62e4a1ce98e301ae4e148bb59f9c8b46.jpg)

![47190b68e60b662bd7ba34df9501721b8d2a6f6f2401a634a5fdf20df7746e1e.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/47190b68e60b662bd7ba34df9501721b8d2a6f6f2401a634a5fdf20df7746e1e.jpg)

![51c4a4128ba351e72a4f381471b45b92e638a1c1bf37c5c5b7136f850d2b9f87.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/51c4a4128ba351e72a4f381471b45b92e638a1c1bf37c5c5b7136f850d2b9f87.jpg)

![600c3ad7021cd8e1e3e0a1de7fc288d50523a13b32d591d22736199307ea883d.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/600c3ad7021cd8e1e3e0a1de7fc288d50523a13b32d591d22736199307ea883d.jpg)

![6ad29d9b624b84bbfafb18a5c45c11d0cd13bc0ac2e206c87679a133aa8c7e58.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/6ad29d9b624b84bbfafb18a5c45c11d0cd13bc0ac2e206c87679a133aa8c7e58.jpg)

![6df1c10b23b027505eee45425414bf2cae57df34c733139368d0f7ad1516fcc2.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/6df1c10b23b027505eee45425414bf2cae57df34c733139368d0f7ad1516fcc2.jpg)

![80502b1c01426da3cc278d97a0472fc44b48801e4b3b91abdb16fd85dab3e009.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/80502b1c01426da3cc278d97a0472fc44b48801e4b3b91abdb16fd85dab3e009.jpg)

![906d82e45984e6c7a98d26fe6cfc3f945b8c3d9e53ca33a9380bbdfb4bf2eb65.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/906d82e45984e6c7a98d26fe6cfc3f945b8c3d9e53ca33a9380bbdfb4bf2eb65.jpg)

![94c45740a1942ce2c887b2fb08e447b6eb31b33bb44f0482cba31752609f9787.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/94c45740a1942ce2c887b2fb08e447b6eb31b33bb44f0482cba31752609f9787.jpg)

![a996c70a760188d833b61b4355641d63aaf872ab42ea09b8b6c66bc84de6612b.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/a996c70a760188d833b61b4355641d63aaf872ab42ea09b8b6c66bc84de6612b.jpg)

![aea1127a2ca82f98663e6e4a4e7365d3c4b4c1b0ee88dee846a78ab39207e893.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/aea1127a2ca82f98663e6e4a4e7365d3c4b4c1b0ee88dee846a78ab39207e893.jpg)

![b14550444de434cea30aca2a01d5c7e79045f1514657d0b24a35daf4f95d54e9.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/b14550444de434cea30aca2a01d5c7e79045f1514657d0b24a35daf4f95d54e9.jpg)

![c1ad9555906252da699c56510314d354b8cf37f4ff4219e6cf68cf2a203489f2.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/c1ad9555906252da699c56510314d354b8cf37f4ff4219e6cf68cf2a203489f2.jpg)

![c3b8a13116004bf5db95e66a699f5457bd6d3dfe5a5e4a404dbb94436fc09910.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/c3b8a13116004bf5db95e66a699f5457bd6d3dfe5a5e4a404dbb94436fc09910.jpg)

![ce9d6a1a6261a5aff406351abffef1d636a0f0ecd71d83b3147a8099af8b014a.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/ce9d6a1a6261a5aff406351abffef1d636a0f0ecd71d83b3147a8099af8b014a.jpg)

![d646667fc26978c69b16716d79407948ffdd8bd22831aa2d9d1b9eb9f9c0dc35.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/d646667fc26978c69b16716d79407948ffdd8bd22831aa2d9d1b9eb9f9c0dc35.jpg)

![edf1175e838e9543881f414af65c14142f864370bb9ddf4946d264d934f577ea.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/edf1175e838e9543881f414af65c14142f864370bb9ddf4946d264d934f577ea.jpg)

![f062b459ad1954a4d48f20d7551188ea4dc8406914900f53b50330316e35aa50.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/images/f062b459ad1954a4d48f20d7551188ea4dc8406914900f53b50330316e35aa50.jpg)

### Tables

![11a4992786a2c4e3bca16f6cc27cf478024b910b3c8ff66705f68c765e5fcff4.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/tables/11a4992786a2c4e3bca16f6cc27cf478024b910b3c8ff66705f68c765e5fcff4.jpg)

![37ffa420179337872d69b44839f9c590f4bcefe9c7ca5c436eb322215ebe8af9.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/tables/37ffa420179337872d69b44839f9c590f4bcefe9c7ca5c436eb322215ebe8af9.jpg)

![606c1042019dff47d1cae2ebb572aae54f8a65b72caf77b7d8d28de558e688c3.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/tables/606c1042019dff47d1cae2ebb572aae54f8a65b72caf77b7d8d28de558e688c3.jpg)

![b54315e34eeae86819a8480acacb19022146922eca9669d129f9bd4701329806.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/tables/b54315e34eeae86819a8480acacb19022146922eca9669d129f9bd4701329806.jpg)

![ba310b7d704173b1cf23fb289123b3ace26b4ca19397caf3f919cb67be0fe3b2.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/tables/ba310b7d704173b1cf23fb289123b3ace26b4ca19397caf3f919cb67be0fe3b2.jpg)

![ba3d5c050cd9dc0ffb81a76c7e63c0cdb929dc6059d76ec8bd24ffba46f397cc.jpg](../nips_results/4306_Discovering%20Data%20Structures_%20Nearest%20Neighbor%20Search%20and%20Beyond/tables/ba3d5c050cd9dc0ffb81a76c7e63c0cdb929dc6059d76ec8bd24ffba46f397cc.jpg)

## Monoculture or Multiplicity: Which Is It?


### Images

![008c76621a1724274b4b4b7cc907569a64c4635723d33acb8509ff6a23dbf577.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/008c76621a1724274b4b4b7cc907569a64c4635723d33acb8509ff6a23dbf577.jpg)

![0a53636bd9e2f509d5425f4746f25c9c08ee4dca0bb84c16236458cd8e57b752.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/0a53636bd9e2f509d5425f4746f25c9c08ee4dca0bb84c16236458cd8e57b752.jpg)

![0cb75e302872dd2e90d8f96f1ad1affc63af9ee4ca4ba71e7d5ef54decdad6fd.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/0cb75e302872dd2e90d8f96f1ad1affc63af9ee4ca4ba71e7d5ef54decdad6fd.jpg)

![0db698e436b1ee645b64e428b1ab97381fe8f58751370d48f7d6382c672209bd.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/0db698e436b1ee645b64e428b1ab97381fe8f58751370d48f7d6382c672209bd.jpg)

![1c27901fc31e6a89645e80dd5300f5e72b3cef2ad38b1f16c085e3080fb97b66.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/1c27901fc31e6a89645e80dd5300f5e72b3cef2ad38b1f16c085e3080fb97b66.jpg)

![21cb5924fdd93bc134e630b1020d0eba5fd32429b7781f19945f9f6936209b39.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/21cb5924fdd93bc134e630b1020d0eba5fd32429b7781f19945f9f6936209b39.jpg)

![24102b88f1378981837a7a9f5608378191f1fed5cb402e4f5766c98c4a9d432f.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/24102b88f1378981837a7a9f5608378191f1fed5cb402e4f5766c98c4a9d432f.jpg)

![3480b6a7e0c53ad4c8bd576c1acae142f936b791b2adcc63c9b595a2f29476b1.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/3480b6a7e0c53ad4c8bd576c1acae142f936b791b2adcc63c9b595a2f29476b1.jpg)

![3693eaa1c42cad07ef741888bd11b23f89007f2736ce60b96671ebaff50caa6a.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/3693eaa1c42cad07ef741888bd11b23f89007f2736ce60b96671ebaff50caa6a.jpg)

![442449980277cc763c0d56ff360ea4b68f9c9ef08efc47b3a7efa1280f2bd7cb.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/442449980277cc763c0d56ff360ea4b68f9c9ef08efc47b3a7efa1280f2bd7cb.jpg)

![4ed3c1c873f157d85de721e2d0949558da0dccb3b459630d11e51350b78548f9.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/4ed3c1c873f157d85de721e2d0949558da0dccb3b459630d11e51350b78548f9.jpg)

![516e48a4507936ad5a8a641348ab2a0ef84336dfe40129a6b58d1b01b56be16c.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/516e48a4507936ad5a8a641348ab2a0ef84336dfe40129a6b58d1b01b56be16c.jpg)

![53cdb1def663e2e2d45a699d49df7e426d7b03489103d202ca884546baef86b2.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/53cdb1def663e2e2d45a699d49df7e426d7b03489103d202ca884546baef86b2.jpg)

![559ae46217701ba020d5eaa464474f9e4c9c88b4b95b2603eb5a5c9eaca0a6d3.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/559ae46217701ba020d5eaa464474f9e4c9c88b4b95b2603eb5a5c9eaca0a6d3.jpg)

![5dd54e4ee6fbfbc7031709aebdb1b4c92eab40bfaf12d9f27c14600e5713f7a6.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/5dd54e4ee6fbfbc7031709aebdb1b4c92eab40bfaf12d9f27c14600e5713f7a6.jpg)

![66564c44642238befd6acafa8538925473545f45e9a23d3cb649c9be9521e0f1.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/66564c44642238befd6acafa8538925473545f45e9a23d3cb649c9be9521e0f1.jpg)

![688a930c47d37d0d09bbac1ee21dea4f30e3c5a7254a3df12ab6c7b6d1f936ec.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/688a930c47d37d0d09bbac1ee21dea4f30e3c5a7254a3df12ab6c7b6d1f936ec.jpg)

![68d3e48982aa478344eac48d91c0c47aa2c41a068264f53e1cd97f45c95dd12b.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/68d3e48982aa478344eac48d91c0c47aa2c41a068264f53e1cd97f45c95dd12b.jpg)

![7bad398f90b26e2ece7dd54dc3bae6c5c894834b7b96eb1c10ebd2bb1f7a70e8.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/7bad398f90b26e2ece7dd54dc3bae6c5c894834b7b96eb1c10ebd2bb1f7a70e8.jpg)

![89e05bd82162580d7247a753962c6877bd187130f04d25127ee3b87a9e53fea7.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/89e05bd82162580d7247a753962c6877bd187130f04d25127ee3b87a9e53fea7.jpg)

![8faa6ea5773d8ca623a46ccd179e897fc8987568e336e49da1c6c4dc97dcc00d.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/8faa6ea5773d8ca623a46ccd179e897fc8987568e336e49da1c6c4dc97dcc00d.jpg)

![93bc85b29e59cd6749531162de8c83e2751df26e9e50221ff9d9563f8007a717.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/93bc85b29e59cd6749531162de8c83e2751df26e9e50221ff9d9563f8007a717.jpg)

![970de430961a6ef9b9c4e7840d3005131fdba7f900f379ba94fa64016c4b6d48.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/970de430961a6ef9b9c4e7840d3005131fdba7f900f379ba94fa64016c4b6d48.jpg)

![a0a6ed7fc0bb5324f54191b742f6b38c515ea358bc48f4d96c6cbaeae609d90b.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/a0a6ed7fc0bb5324f54191b742f6b38c515ea358bc48f4d96c6cbaeae609d90b.jpg)

![a28be7d27503acad725cfb1865e32b848b1c7b516de223dd261e7a3a0317162c.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/a28be7d27503acad725cfb1865e32b848b1c7b516de223dd261e7a3a0317162c.jpg)

![a3042e21a9e28e408dc56def980c9c2be9721ea6baf53f484dbfc400b2d23793.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/a3042e21a9e28e408dc56def980c9c2be9721ea6baf53f484dbfc400b2d23793.jpg)

![aa42be0f0ddb689ad8ea4bc4636a260d542dc88a302665b7362f98419e39b3b9.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/aa42be0f0ddb689ad8ea4bc4636a260d542dc88a302665b7362f98419e39b3b9.jpg)

![bf19b5f2f66f22ee8d67d8f51efcba9d77a2da1978f7e2fca3c2f8af66a632a3.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/bf19b5f2f66f22ee8d67d8f51efcba9d77a2da1978f7e2fca3c2f8af66a632a3.jpg)

![c24ba6956008238094ce20f824795219800dd94b4a868dd6638f03156c687fe0.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/c24ba6956008238094ce20f824795219800dd94b4a868dd6638f03156c687fe0.jpg)

![c888476ffc312c06f2abf087db777796d2f4f176982b7538bd018f7d31fb37bf.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/c888476ffc312c06f2abf087db777796d2f4f176982b7538bd018f7d31fb37bf.jpg)

![ce5cfb12f7b51447643bd389eaf8bdf9f1ec38d5f4ecb3bd3c380aed904f5ef0.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/ce5cfb12f7b51447643bd389eaf8bdf9f1ec38d5f4ecb3bd3c380aed904f5ef0.jpg)

![e4ff5c3161a0aabbb4545b2a91edf435892d42c0818a001dfd734544b816db38.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/e4ff5c3161a0aabbb4545b2a91edf435892d42c0818a001dfd734544b816db38.jpg)

![f5a23beeaa6b731c0f2f30e478ec1fdb2dd1559b4a254a0a52eb2aa37d954495.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/images/f5a23beeaa6b731c0f2f30e478ec1fdb2dd1559b4a254a0a52eb2aa37d954495.jpg)

### Tables

![0ab1e03f066d906883b29e656700b1e236918cddab0d09a23c46c8e6ab09124f.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/0ab1e03f066d906883b29e656700b1e236918cddab0d09a23c46c8e6ab09124f.jpg)

![0b69193c830ab97dc3c8fa24d5875c73d92898fa88a4a9fdb20d3cf683032a86.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/0b69193c830ab97dc3c8fa24d5875c73d92898fa88a4a9fdb20d3cf683032a86.jpg)

![33333bfc182194e751ffdf874183bf4e71e05e661b3eb59fce2bf45c10d84c31.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/33333bfc182194e751ffdf874183bf4e71e05e661b3eb59fce2bf45c10d84c31.jpg)

![376d0d643bcc86de3e38051df9033ad8543bd24afce0936bceca95dbff01d52f.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/376d0d643bcc86de3e38051df9033ad8543bd24afce0936bceca95dbff01d52f.jpg)

![3970307870cda2c2642cd2164e8ef92b89b1dd197ee8693c5a266cfa01f0dc03.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/3970307870cda2c2642cd2164e8ef92b89b1dd197ee8693c5a266cfa01f0dc03.jpg)

![537f7c33450ea99db5ca98330e3a3c38939013a3cf48060177159ae02f3d15f6.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/537f7c33450ea99db5ca98330e3a3c38939013a3cf48060177159ae02f3d15f6.jpg)

![8c448eb4243e558589459d47f6f8bbdecd6e926a514da673191cd5dbaa661f98.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/8c448eb4243e558589459d47f6f8bbdecd6e926a514da673191cd5dbaa661f98.jpg)

![a120be047fa73ddb38ad8df8dd3b1362b54206efc3a7a74a59ca1b894c08f4c7.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/a120be047fa73ddb38ad8df8dd3b1362b54206efc3a7a74a59ca1b894c08f4c7.jpg)

![bc94b5a3072cc0d56bd1dc3f5994f7a5006f878f07f0a20c7a4700d4517e08f5.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/bc94b5a3072cc0d56bd1dc3f5994f7a5006f878f07f0a20c7a4700d4517e08f5.jpg)

![c7f92ec4201ca6715998d245f7763885faba6c19801caded754982fd487d3a14.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/c7f92ec4201ca6715998d245f7763885faba6c19801caded754982fd487d3a14.jpg)

![d67e2e5f1ec85ac01e3d10334272e6256970e2459c5fb352b551e10ec9b9d5c8.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/d67e2e5f1ec85ac01e3d10334272e6256970e2459c5fb352b551e10ec9b9d5c8.jpg)

![fc81580600f19af0796a36fa1ff2ea669b7d039e06d42518bc73e410b60aa5d3.jpg](../nips_results/4307_Monoculture%20or%20Multiplicity_%20Which%20Is%20It_/tables/fc81580600f19af0796a36fa1ff2ea669b7d039e06d42518bc73e410b60aa5d3.jpg)

## Automaton Constrained Q-Learning


### Images

![0996b4347dc01736241e749590d0795d18978e8cdc68a11472b958580365fb23.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/images/0996b4347dc01736241e749590d0795d18978e8cdc68a11472b958580365fb23.jpg)

![0c96606fb9d5c0986041f916a565b57b5a582dc2e18267d469f579ffc66be235.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/images/0c96606fb9d5c0986041f916a565b57b5a582dc2e18267d469f579ffc66be235.jpg)

![2a899443fa07078b5b48983aeb29e63f41c2a29b7817cd2598b1dc8fbd511d7e.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/images/2a899443fa07078b5b48983aeb29e63f41c2a29b7817cd2598b1dc8fbd511d7e.jpg)

![45e12aa876e12b63d0bf17657f2d424e7a8fe891f20db1e6fdba3000a69d5043.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/images/45e12aa876e12b63d0bf17657f2d424e7a8fe891f20db1e6fdba3000a69d5043.jpg)

![4df72f5e3d249ed2a5e065e0e56015b8fc4fc04236576ab24b8e973977d81b86.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/images/4df72f5e3d249ed2a5e065e0e56015b8fc4fc04236576ab24b8e973977d81b86.jpg)

![bcdae1bc29a0eb246fe21473ba77a27175299ef57483c82109b1509b054a6451.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/images/bcdae1bc29a0eb246fe21473ba77a27175299ef57483c82109b1509b054a6451.jpg)

![c4c756b3840711f8602f1c0dcdd7682076105f3f155c6eff9c2a6c6af8d50f14.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/images/c4c756b3840711f8602f1c0dcdd7682076105f3f155c6eff9c2a6c6af8d50f14.jpg)

![d1c749cf44e91b9ce4e014f5b43e031d65f72b129227939d6e6b2822da4c845c.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/images/d1c749cf44e91b9ce4e014f5b43e031d65f72b129227939d6e6b2822da4c845c.jpg)

![d37c9bc57093ddc74dd3b4eb620ab970cbdf26f72b900f2b847488f80e4fa1c6.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/images/d37c9bc57093ddc74dd3b4eb620ab970cbdf26f72b900f2b847488f80e4fa1c6.jpg)

### Tables

![443f2266c2e84d850e5d751dc9e9d30f1aec2f0aba2cb9fa4a53d8209cb4b6a8.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/tables/443f2266c2e84d850e5d751dc9e9d30f1aec2f0aba2cb9fa4a53d8209cb4b6a8.jpg)

![5bda960e21b4dcf9c92f3d39c22d9ec3c8493ac42884e90844c76d7d76903098.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/tables/5bda960e21b4dcf9c92f3d39c22d9ec3c8493ac42884e90844c76d7d76903098.jpg)

![93605d1da4c502be1f339dc16de7ece3507e05574d974453814bf8c1d45ad4f3.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/tables/93605d1da4c502be1f339dc16de7ece3507e05574d974453814bf8c1d45ad4f3.jpg)

![9546148ba9d107081d5c4c69c40cb1223ac7a8ee13b6de55c9e26e6d1c987fb1.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/tables/9546148ba9d107081d5c4c69c40cb1223ac7a8ee13b6de55c9e26e6d1c987fb1.jpg)

![adac4ace46544d261fea48a805c3032f395862b5e6397fcda8f14dfe1ae489c4.jpg](../nips_results/4308_Automaton%20Constrained%20Q-Learning/tables/adac4ace46544d261fea48a805c3032f395862b5e6397fcda8f14dfe1ae489c4.jpg)

## MVSMamba: Multi-View Stereo with State Space Model


### Images

![2f2b3f9f0b5560409d072044bf62b44ad8fc40ad45a3ab7865e4c8df4747bf53.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/images/2f2b3f9f0b5560409d072044bf62b44ad8fc40ad45a3ab7865e4c8df4747bf53.jpg)

![4058c51fed3fe15166c54ee3fc250e57ccd47bb7eb97ccaec4ef1be2f29c03dd.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/images/4058c51fed3fe15166c54ee3fc250e57ccd47bb7eb97ccaec4ef1be2f29c03dd.jpg)

![6454e98917f72ae7a600a10c8e035612c9d53781f2826ba0cc4ec480f232cd44.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/images/6454e98917f72ae7a600a10c8e035612c9d53781f2826ba0cc4ec480f232cd44.jpg)

![898b7c7f2030da55f79053d9121f0d2c684908daf0c153405602fc999361cea5.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/images/898b7c7f2030da55f79053d9121f0d2c684908daf0c153405602fc999361cea5.jpg)

![9e023f48c0ec8d57c89dd1a65d4f622b43ef82b7237afabab3584b3533790443.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/images/9e023f48c0ec8d57c89dd1a65d4f622b43ef82b7237afabab3584b3533790443.jpg)

![b70631a046fb3446f209ec40ceaa25f6fe88e28569206287544bc2d851736c18.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/images/b70631a046fb3446f209ec40ceaa25f6fe88e28569206287544bc2d851736c18.jpg)

![cd05c15a1b682075b1c29fa924459a97c0d73a5599034e357942db6d8e8c3d96.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/images/cd05c15a1b682075b1c29fa924459a97c0d73a5599034e357942db6d8e8c3d96.jpg)

![f6f6ed40b8c77718e5b2ace4868fa1556c4a2ba98e0e9a2e8492c08de116da09.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/images/f6f6ed40b8c77718e5b2ace4868fa1556c4a2ba98e0e9a2e8492c08de116da09.jpg)

### Tables

![001f2e278ae434c7e36cedf1e461a989a2e545cefe13fe9fec312511493e0aef.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/001f2e278ae434c7e36cedf1e461a989a2e545cefe13fe9fec312511493e0aef.jpg)

![062f8a7a72da5c3f5dc9efa0f4e221d3095fbda23fdeafe90980ec344bf9b3c0.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/062f8a7a72da5c3f5dc9efa0f4e221d3095fbda23fdeafe90980ec344bf9b3c0.jpg)

![2a97098e304f931735ad6d1f036bfb7ab0e273dcf6588ea789a6db8523ab5c1f.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/2a97098e304f931735ad6d1f036bfb7ab0e273dcf6588ea789a6db8523ab5c1f.jpg)

![42c756aa941a80050faaf4f7e22fbd056d7572f58c62f147c2883087158d6337.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/42c756aa941a80050faaf4f7e22fbd056d7572f58c62f147c2883087158d6337.jpg)

![43f258e54147ec7f7735c5addc14107c7af0c983770e5a4d9618d124d30b0956.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/43f258e54147ec7f7735c5addc14107c7af0c983770e5a4d9618d124d30b0956.jpg)

![51cc93c58f0ec743d9f27ba498b222705ab398ae6240b83b8771d5d0e987a6d7.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/51cc93c58f0ec743d9f27ba498b222705ab398ae6240b83b8771d5d0e987a6d7.jpg)

![8de9931de7634bf82015264a7dabb0eba77b53b6f45f9b38ff646ef6632caee4.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/8de9931de7634bf82015264a7dabb0eba77b53b6f45f9b38ff646ef6632caee4.jpg)

![95ce5a60701671c35983ae472f1f24eae9506d3c1abd0981dc55eb639efd97c8.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/95ce5a60701671c35983ae472f1f24eae9506d3c1abd0981dc55eb639efd97c8.jpg)

![9c836d0f4aa1c20a6fbfaf82c5d838201afb87249e2a9776512db6cb6146f2c2.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/9c836d0f4aa1c20a6fbfaf82c5d838201afb87249e2a9776512db6cb6146f2c2.jpg)

![a2b244f470df33073a4f1ebd49c687ed45a144700bcdd17fb152e25659fbc283.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/a2b244f470df33073a4f1ebd49c687ed45a144700bcdd17fb152e25659fbc283.jpg)

![aaccc7344a4dfc8ea0907463ce2960479de6ea8f3e0912040323665e92ee45eb.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/aaccc7344a4dfc8ea0907463ce2960479de6ea8f3e0912040323665e92ee45eb.jpg)

![c2520cd5136bd9f44b5a45e37e1690c438bc774f764e523d6dc8780f20227c9c.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/c2520cd5136bd9f44b5a45e37e1690c438bc774f764e523d6dc8780f20227c9c.jpg)

![cf7f36930539ec1e1838e3e8dcc05e06c8e1141a06daf747dec65401a823cbda.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/cf7f36930539ec1e1838e3e8dcc05e06c8e1141a06daf747dec65401a823cbda.jpg)

![dc82c37a12ac3fed23c82b16ef6149c848e03d2a434ff7358ceaf525ac7e2118.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/dc82c37a12ac3fed23c82b16ef6149c848e03d2a434ff7358ceaf525ac7e2118.jpg)

![e60ae757e68299756191a70d74f211f267142125a28de0accd21227823bd4025.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/e60ae757e68299756191a70d74f211f267142125a28de0accd21227823bd4025.jpg)

![fcb28b80eba67ed263049e8dd998e2f9a43ab5cb3e797538298694ab05b5c47a.jpg](../nips_results/4309_MVSMamba_%20Multi-View%20Stereo%20with%20State%20Space%20Model/tables/fcb28b80eba67ed263049e8dd998e2f9a43ab5cb3e797538298694ab05b5c47a.jpg)

## SUMO: Subspace-Aware Moment-Orthogonalization for Accelerating Memory-Efficient LLM Training

### Images

![09ae5fa05766ec5b618e55fc60b3331843d20df1ee3a60c7b5e05658a22b2765.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/images/09ae5fa05766ec5b618e55fc60b3331843d20df1ee3a60c7b5e05658a22b2765.jpg)

![49e082a0b0ebbf4412bba1c004b71bd4aff0df523c4aa3ba979e7e3d2392184d.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/images/49e082a0b0ebbf4412bba1c004b71bd4aff0df523c4aa3ba979e7e3d2392184d.jpg)

![ded76963716a65eba534c677ca00f3900c123ffcdb2c808d9fc16ecb38fd945e.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/images/ded76963716a65eba534c677ca00f3900c123ffcdb2c808d9fc16ecb38fd945e.jpg)

### Tables

![03996588d2809256e2331d909918c953a19e3bd0d8ac53df7fa86b92a8fb6806.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/tables/03996588d2809256e2331d909918c953a19e3bd0d8ac53df7fa86b92a8fb6806.jpg)

![053c9a39fb8f0f3054c1679d9c4a72fea4182b358c8819f9b09a68f9b2e2e5f7.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/tables/053c9a39fb8f0f3054c1679d9c4a72fea4182b358c8819f9b09a68f9b2e2e5f7.jpg)

![33fd7f5fa94973ab04ecbc85b180c176982f224de4c8ba43181cff722d02bb83.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/tables/33fd7f5fa94973ab04ecbc85b180c176982f224de4c8ba43181cff722d02bb83.jpg)

![3f625d446f6c1c9a578c01984edebc2cc0204452fbedc011a82d064ab5a1d84f.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/tables/3f625d446f6c1c9a578c01984edebc2cc0204452fbedc011a82d064ab5a1d84f.jpg)

![562f92d79641a4ab84e146ecb581182eff630fb812d1324cceb73042d7c30edd.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/tables/562f92d79641a4ab84e146ecb581182eff630fb812d1324cceb73042d7c30edd.jpg)

![5cff99c10f87c2746c1a06bc4eae75ee655f1a6dfe9277b25bab942573335c71.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/tables/5cff99c10f87c2746c1a06bc4eae75ee655f1a6dfe9277b25bab942573335c71.jpg)

![7e9ede8e9610ba2a8073311b40f5b4448f71e86f77e77afd101d039137c3edb7.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/tables/7e9ede8e9610ba2a8073311b40f5b4448f71e86f77e77afd101d039137c3edb7.jpg)

![9cfbe946e6a5c0e7e99fe464c90465475998505694976f08c4e85aac05a6b92c.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/tables/9cfbe946e6a5c0e7e99fe464c90465475998505694976f08c4e85aac05a6b92c.jpg)

![c55d312b5d8ad972211b06df239602a04aef16159994060e2d3f9ef5530a71c5.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/tables/c55d312b5d8ad972211b06df239602a04aef16159994060e2d3f9ef5530a71c5.jpg)

![cf28d7831c79d461494fda166fdb9c7edcc57e4e62c73a8f401dfbb02fabe44d.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/tables/cf28d7831c79d461494fda166fdb9c7edcc57e4e62c73a8f401dfbb02fabe44d.jpg)

![e5367e1733349b440a21a8f7b949aaf0469482a0d836517447500235910d93df.jpg](../nips_results/4310_SUMO_%20Subspace-Aware%20Moment-Orthogonalization%20for%20Accelerating%20Memory-Efficient%20LLM%20Training/tables/e5367e1733349b440a21a8f7b949aaf0469482a0d836517447500235910d93df.jpg)
