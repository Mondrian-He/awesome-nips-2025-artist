# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 43 of 130

## 目录 (Table of Contents)

1. [Object-X: Learning to Reconstruct Multi-Modal 3D Object Representations](#Object-X-Learning-to-Reconstruct-Multi-Modal-3D-Object-Representations)
2. [Improving Video Generation with Human Feedback](#Improving-Video-Generation-with-Human-Feedback)
3. [NFIG: Multi-Scale Autoregressive Image Generation via Frequency Ordering](#NFIG-Multi-Scale-Autoregressive-Image-Generation-via-Frequency-Ordering)
4. [FlyLoRA: Boosting Task Decoupling and Parameter Efficiency via Implicit Rank-Wise Mixture-of-Experts](#FlyLoRA-Boosting-Task-Decoupling-and-Parameter-Efficiency-via-Implicit-Rank-Wise-Mixture-of-Experts)
5. [Compress & Cache: Vision token compression for efficient generation and retrieval](#Compress-Cache-Vision-token-compression-for-efficient-generation-and-retrieval)
6. [Valid Inference with Imperfect Synthetic Data](#Valid-Inference-with-Imperfect-Synthetic-Data)
7. [Active Measurement: Efficient Estimation at Scale](#Active-Measurement-Efficient-Estimation-at-Scale)
8. [Understanding Contrastive Learning via Gaussian Mixture Models](#Understanding-Contrastive-Learning-via-Gaussian-Mixture-Models)
9. [A Unified Framework for Variable Selection in Model-Based Clustering with Missing Not at Random](#A-Unified-Framework-for-Variable-Selection-in-Model-Based-Clustering-with-Missing-Not-at-Random)
10. [Keep It on a Leash: Controllable Pseudo-label Generation Towards Realistic Long-Tailed Semi-Supervised Learning](#Keep-It-on-a-Leash-Controllable-Pseudo-label-Generation-Towards-Realistic-Long-Tailed-Semi-Supervised-Learning)
11. [MoME: Mixture of Matryoshka Experts for Audio-Visual Speech Recognition](#MoME-Mixture-of-Matryoshka-Experts-for-Audio-Visual-Speech-Recognition)
12. [Reconciling Geospatial Prediction and Retrieval via Sparse Representations](#Reconciling-Geospatial-Prediction-and-Retrieval-via-Sparse-Representations)
13. [Targeted Maximum Likelihood Learning: An Optimization Perspective](#Targeted-Maximum-Likelihood-Learning-An-Optimization-Perspective)
14. [CSGO: Content-Style Composition in Text-to-Image Generation](#CSGO-Content-Style-Composition-in-Text-to-Image-Generation)
15. [Agentic Plan Caching: Test-Time Memory for Fast and Cost-Efficient LLM Agents](#Agentic-Plan-Caching-Test-Time-Memory-for-Fast-and-Cost-Efficient-LLM-Agents)
16. [ShoeFit: A New Dataset and Dual-image-stream DiT Framework for Virtual Footwear Try-On](#ShoeFit-A-New-Dataset-and-Dual-image-stream-DiT-Framework-for-Virtual-Footwear-Try-On)
17. [Generalization Bounds for Rank-sparse Neural Networks](#Generalization-Bounds-for-Rank-sparse-Neural-Networks)
18. [3DID: Direct 3D Inverse Design for Aerodynamics with Physics-Aware Optimization](#3DID-Direct-3D-Inverse-Design-for-Aerodynamics-with-Physics-Aware-Optimization)
19. [PRSformer: Disease Prediction from Million-Scale Individual Genotypes](#PRSformer-Disease-Prediction-from-Million-Scale-Individual-Genotypes)
20. [Enhancing Graph Classification Robustness with Singular Pooling](#Enhancing-Graph-Classification-Robustness-with-Singular-Pooling)
21. [The Price of Opportunity Fairness in Matroid Allocation Problems](#The-Price-of-Opportunity-Fairness-in-Matroid-Allocation-Problems)
22. [The Narrow Gate: Localized Image-Text Communication in Native Multimodal Models](#The-Narrow-Gate-Localized-Image-Text-Communication-in-Native-Multimodal-Models)
23. [EAReranker: Efficient Embedding Adequacy Assessment for Retrieval Augmented Generation](#EAReranker-Efficient-Embedding-Adequacy-Assessment-for-Retrieval-Augmented-Generation)
24. [Behavior Injection: Preparing Language Models for Reinforcement Learning](#Behavior-Injection-Preparing-Language-Models-for-Reinforcement-Learning)
25. [Functional data analysis for multivariate distributions through Wasserstein slicing](#Functional-data-analysis-for-multivariate-distributions-through-Wasserstein-slicing)
26. [Balancing Performance and Costs in Best Arm Identification](#Balancing-Performance-and-Costs-in-Best-Arm-Identification)
27. [Vertical Federated Feature Screening](#Vertical-Federated-Feature-Screening)
28. [Fair Minimum Labeling: Efficient Temporal Network Activations for Reachability and Equity](#Fair-Minimum-Labeling-Efficient-Temporal-Network-Activations-for-Reachability-and-Equity)
29. [Parameter Efficient Fine-tuning via Explained Variance Adaptation](#Parameter-Efficient-Fine-tuning-via-Explained-Variance-Adaptation)
30. [CTSketch: Compositional Tensor Sketching for Scalable Neurosymbolic Learning](#CTSketch-Compositional-Tensor-Sketching-for-Scalable-Neurosymbolic-Learning)
31. [Preference-Guided Diffusion for Multi-Objective Offline Optimization](#Preference-Guided-Diffusion-for-Multi-Objective-Offline-Optimization)
32. [From Judgment to Interference: Early Stopping LLM Harmful Outputs via Streaming Content Monitoring](#From-Judgment-to-Interference-Early-Stopping-LLM-Harmful-Outputs-via-Streaming-Content-Monitoring)
33. [A Unified Analysis of Stochastic Gradient Descent with Arbitrary Data Permutations and Beyond](#A-Unified-Analysis-of-Stochastic-Gradient-Descent-with-Arbitrary-Data-Permutations-and-Beyond)
34. [Integrating Drug Substructures and Longitudinal Electronic Health Records for Personalized Drug Recommendation](#Integrating-Drug-Substructures-and-Longitudinal-Electronic-Health-Records-for-Personalized-Drug-Recommendation)
35. [Understanding Data Influence in Reinforcement Finetuning](#Understanding-Data-Influence-in-Reinforcement-Finetuning)
36. [Uni-RL: Unifying Online and Offline RL via Implicit Value Regularization](#Uni-RL-Unifying-Online-and-Offline-RL-via-Implicit-Value-Regularization)
37. [ThinkSound: Chain-of-Thought Reasoning in Multimodal LLMs for Audio Generation and Editing](#ThinkSound-Chain-of-Thought-Reasoning-in-Multimodal-LLMs-for-Audio-Generation-and-Editing)
38. [Normalization in Attention Dynamics](#Normalization-in-Attention-Dynamics)
39. [Low-Rank Head Avatar Personalization with Registers](#Low-Rank-Head-Avatar-Personalization-with-Registers)
40. [DoDo-Code: an Efficient Levenshtein Distance Embedding-based Code for 4-ary IDS Channel](#DoDo-Code-an-Efficient-Levenshtein-Distance-Embedding-based-Code-for-4-ary-IDS-Channel)
41. [Self-Supervised Contrastive Learning is Approximately Supervised Contrastive Learning](#Self-Supervised-Contrastive-Learning-is-Approximately-Supervised-Contrastive-Learning)

---


## Object-X: Learning to Reconstruct Multi-Modal 3D Object Representations

### Images

![1623e91f4dea92bd47180d77ca4d97bd418f4c98b592d969d633c38b6788c68b.jpg](../nips_results/1746_Walking%20the%20Schr%C3%B6dinger%20Bridge_%20A%20Direct%20Trajectory%20for%20Text-to-3D%20Generation/images/1623e91f4dea92bd47180d77ca4d97bd418f4c98b592d969d633c38b6788c68b.jpg)

![2d451db5c72c324d78e509c62c6d8fd27f0eb1adb193f6e0f6d4ae3d8a4150b3.jpg](../nips_results/1746_Walking%20the%20Schr%C3%B6dinger%20Bridge_%20A%20Direct%20Trajectory%20for%20Text-to-3D%20Generation/images/2d451db5c72c324d78e509c62c6d8fd27f0eb1adb193f6e0f6d4ae3d8a4150b3.jpg)

![5ba0058d4572ac72217733498d08d946275ec9e6e24937a87a6238a7934f87eb.jpg](../nips_results/1746_Walking%20the%20Schr%C3%B6dinger%20Bridge_%20A%20Direct%20Trajectory%20for%20Text-to-3D%20Generation/images/5ba0058d4572ac72217733498d08d946275ec9e6e24937a87a6238a7934f87eb.jpg)

![ab664ae1bee94e796a5319ad0955f9eb34460834e3af050787fdd377bb65effb.jpg](../nips_results/1746_Walking%20the%20Schr%C3%B6dinger%20Bridge_%20A%20Direct%20Trajectory%20for%20Text-to-3D%20Generation/images/ab664ae1bee94e796a5319ad0955f9eb34460834e3af050787fdd377bb65effb.jpg)

![c5e5830ee9d8204cf0e4cba5c7e03ffe85f846cfc43a01f069feac96d2facf32.jpg](../nips_results/1746_Walking%20the%20Schr%C3%B6dinger%20Bridge_%20A%20Direct%20Trajectory%20for%20Text-to-3D%20Generation/images/c5e5830ee9d8204cf0e4cba5c7e03ffe85f846cfc43a01f069feac96d2facf32.jpg)

![db8ad45d43a17796ee73e6d1c89cf286804bd417d1e01acf56f710e1577e8f89.jpg](../nips_results/1746_Walking%20the%20Schr%C3%B6dinger%20Bridge_%20A%20Direct%20Trajectory%20for%20Text-to-3D%20Generation/images/db8ad45d43a17796ee73e6d1c89cf286804bd417d1e01acf56f710e1577e8f89.jpg)

### Tables

![7ec81e0776b870b02d2b61b1c3e13efcf7a8a9b0897aac115cc01f6f84b1f7cb.jpg](../nips_results/1746_Walking%20the%20Schr%C3%B6dinger%20Bridge_%20A%20Direct%20Trajectory%20for%20Text-to-3D%20Generation/tables/7ec81e0776b870b02d2b61b1c3e13efcf7a8a9b0897aac115cc01f6f84b1f7cb.jpg)

![c3ad1cbca88d8008297b6ef1d513aa9283206ed820aa6d8e565c12a4b347f08b.jpg](../nips_results/1746_Walking%20the%20Schr%C3%B6dinger%20Bridge_%20A%20Direct%20Trajectory%20for%20Text-to-3D%20Generation/tables/c3ad1cbca88d8008297b6ef1d513aa9283206ed820aa6d8e565c12a4b347f08b.jpg)

## Object-X: Learning to Reconstruct Multi-Modal 3D Object Representations


### Images

![3c25abb9f1531a5d25d816fbc558b6ba69e91d1bc5aad00ff58b78640f34a76e.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/images/3c25abb9f1531a5d25d816fbc558b6ba69e91d1bc5aad00ff58b78640f34a76e.jpg)

![4aa2afdc9134a1e396ea89d25e22bee469a0f7ff873d4ba297a37be078ddbea1.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/images/4aa2afdc9134a1e396ea89d25e22bee469a0f7ff873d4ba297a37be078ddbea1.jpg)

![5229832ceb0e3cfe4b91c48568f32b994b622946204f0e00945051c929a1c399.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/images/5229832ceb0e3cfe4b91c48568f32b994b622946204f0e00945051c929a1c399.jpg)

![791c07ce40887c6fbb1a67160ff310472a4b53d21b8623687672d88b3a6158c8.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/images/791c07ce40887c6fbb1a67160ff310472a4b53d21b8623687672d88b3a6158c8.jpg)

![95ae09f86010a53a4b19c00db60ca2d09f28b787ad833394757ee861ba6c78eb.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/images/95ae09f86010a53a4b19c00db60ca2d09f28b787ad833394757ee861ba6c78eb.jpg)

![e2db828580ec17ee13926660edbce475e7ab868fbfccdbb5076836d2b3e30347.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/images/e2db828580ec17ee13926660edbce475e7ab868fbfccdbb5076836d2b3e30347.jpg)

![eb65f83b45e68968b5a7880690e1bea9ccc34c01da498bff284030286abe17c0.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/images/eb65f83b45e68968b5a7880690e1bea9ccc34c01da498bff284030286abe17c0.jpg)

![f8bd73b75fea313d67e6452f65da76e085f322b693678dd831e2e7d200f8a1fe.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/images/f8bd73b75fea313d67e6452f65da76e085f322b693678dd831e2e7d200f8a1fe.jpg)

### Tables

![007639e3d886688bcdad96296fd81f44b98ece9fbd6420a1dc5a8bd2b82943b8.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/tables/007639e3d886688bcdad96296fd81f44b98ece9fbd6420a1dc5a8bd2b82943b8.jpg)

![11c7e5fcad803ec24a74552f79e0e2f3c9f62b3bd36b8399c1d14303c7e6f8cc.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/tables/11c7e5fcad803ec24a74552f79e0e2f3c9f62b3bd36b8399c1d14303c7e6f8cc.jpg)

![2f7dbc6f5f946907aafae32946fb5e3817e14bc73e5eed2a09cd0bb31065728f.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/tables/2f7dbc6f5f946907aafae32946fb5e3817e14bc73e5eed2a09cd0bb31065728f.jpg)

![4a4a41f3e074206ddaee604f136e567c6dd0e02a30b3ff828ab4cd31fb1922b5.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/tables/4a4a41f3e074206ddaee604f136e567c6dd0e02a30b3ff828ab4cd31fb1922b5.jpg)

![5b6ffd4ae6b4600bcf06065522c0141b3fd55730138949bb3cf28cd35f4979e3.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/tables/5b6ffd4ae6b4600bcf06065522c0141b3fd55730138949bb3cf28cd35f4979e3.jpg)

![79607bc0923ed2c429989c14048037fea96a2c597f607c4decaf579ace536fce.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/tables/79607bc0923ed2c429989c14048037fea96a2c597f607c4decaf579ace536fce.jpg)

![bae21b79332d6b073fe44947efd20a052ce5eb8849b9661eed0878d6c22fc2a6.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/tables/bae21b79332d6b073fe44947efd20a052ce5eb8849b9661eed0878d6c22fc2a6.jpg)

![c48b0432509b2632e236ec6e31c764bae95eb80f5e281a19a97a256ae436db83.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/tables/c48b0432509b2632e236ec6e31c764bae95eb80f5e281a19a97a256ae436db83.jpg)

![fe8f77d7270d26444202e0a18282e91ab7ac6b189d01b532bb13ec1d321caf42.jpg](../nips_results/1747_Object-X_%20Learning%20to%20Reconstruct%20Multi-Modal%203D%20Object%20Representations/tables/fe8f77d7270d26444202e0a18282e91ab7ac6b189d01b532bb13ec1d321caf42.jpg)

## Improving Video Generation with Human Feedback


### Images

![261c381ab63f7e793070e8975a31ca0fa0eccd9714ecbf04abe531dc728dbdb3.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/261c381ab63f7e793070e8975a31ca0fa0eccd9714ecbf04abe531dc728dbdb3.jpg)

![2daef91611216129e3bd26d22f2441477620e28824afff73433114e794ab84b4.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/2daef91611216129e3bd26d22f2441477620e28824afff73433114e794ab84b4.jpg)

![43ba7903f8457de3ac1cb917b47530633ce9934d5e129427537817647dc4453c.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/43ba7903f8457de3ac1cb917b47530633ce9934d5e129427537817647dc4453c.jpg)

![44cffb583b87b22e46389c07a72f9583a2fa0c6a59e97d9dfd0e33f66dc0868a.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/44cffb583b87b22e46389c07a72f9583a2fa0c6a59e97d9dfd0e33f66dc0868a.jpg)

![4f0c8960c81816536c35a7844725e15a0cdaf5f3f6c456e4b650de9bf0026ecb.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/4f0c8960c81816536c35a7844725e15a0cdaf5f3f6c456e4b650de9bf0026ecb.jpg)

![5f53d4bda3d24c6b5e9b3df28dfdb41b8b6a3cd65e3589802e21a8ad9c1664e7.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/5f53d4bda3d24c6b5e9b3df28dfdb41b8b6a3cd65e3589802e21a8ad9c1664e7.jpg)

![6fa3a67e21ce211bb65e7799a12daf22d78bf9e75a5b71d30535e705b1885a80.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/6fa3a67e21ce211bb65e7799a12daf22d78bf9e75a5b71d30535e705b1885a80.jpg)

![9b7f7be1e986f7bb29612514bf973b951d5d5c285add48723bcb6e4474674aa5.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/9b7f7be1e986f7bb29612514bf973b951d5d5c285add48723bcb6e4474674aa5.jpg)

![a4262a1b80e391b07824c6e42600d029b5b7095ce53be2a54791347a9aff39ea.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/a4262a1b80e391b07824c6e42600d029b5b7095ce53be2a54791347a9aff39ea.jpg)

![a89dcef472057e1d76923338d31fc9c1c068e2c57d0419685cabd10ea2be82a0.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/a89dcef472057e1d76923338d31fc9c1c068e2c57d0419685cabd10ea2be82a0.jpg)

![aca3722eece6de3accf995cd245c51db82f20811ad89ede2718ef2a7db5ff7b2.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/aca3722eece6de3accf995cd245c51db82f20811ad89ede2718ef2a7db5ff7b2.jpg)

![b7c5b3288eb1c61b6ac3202198dfcb200dd39798737e6455bc9d4987f42fd513.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/b7c5b3288eb1c61b6ac3202198dfcb200dd39798737e6455bc9d4987f42fd513.jpg)

![eefaa84e5827eaa259237f456934786b216df660b3a163bbaccb5a1189d0ad41.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/images/eefaa84e5827eaa259237f456934786b216df660b3a163bbaccb5a1189d0ad41.jpg)

### Tables

![08d787f37bd0609e67c7f180b5bfce9828ffe25e1c3756dfd082929a3a2a4413.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/08d787f37bd0609e67c7f180b5bfce9828ffe25e1c3756dfd082929a3a2a4413.jpg)

![1725dd1241895570888821cd9f85af064ec6c36f7b84a6379973494a102b5756.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/1725dd1241895570888821cd9f85af064ec6c36f7b84a6379973494a102b5756.jpg)

![2e75603174722f830d852205043e3112e79169ddb6a71c55dd97bfb17aa8f375.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/2e75603174722f830d852205043e3112e79169ddb6a71c55dd97bfb17aa8f375.jpg)

![363d4975682e85e9c7bca6e39c148fb37d0bed7415627aa6471134f4a11d4e4e.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/363d4975682e85e9c7bca6e39c148fb37d0bed7415627aa6471134f4a11d4e4e.jpg)

![3ce78cb1d5f7d3da2531c7d8900ad0cb38bebb03400780792628942d42b6385c.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/3ce78cb1d5f7d3da2531c7d8900ad0cb38bebb03400780792628942d42b6385c.jpg)

![5d03fbe0e2e7c0c9c87e351405a3568911beeb5dafe76bde82f8c5735154c384.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/5d03fbe0e2e7c0c9c87e351405a3568911beeb5dafe76bde82f8c5735154c384.jpg)

![6825a6db3cde56843ff38618e3b949e4162837c61e6586bcd0b3060f35be21a1.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/6825a6db3cde56843ff38618e3b949e4162837c61e6586bcd0b3060f35be21a1.jpg)

![87881d53f180df58efbcf556928c273706ca5bdfd0f46134370a73a586f6f72d.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/87881d53f180df58efbcf556928c273706ca5bdfd0f46134370a73a586f6f72d.jpg)

![b1675c96ebb45ac72a05ef6779adaabb80c64821b603d25a783bb3ce34f3596b.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/b1675c96ebb45ac72a05ef6779adaabb80c64821b603d25a783bb3ce34f3596b.jpg)

![c5438592fdea5d22de3c19d6e897991c5c8ea277f660862fa17c58fe7e49cb7d.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/c5438592fdea5d22de3c19d6e897991c5c8ea277f660862fa17c58fe7e49cb7d.jpg)

![dfb306b3c796665fa6d06120873226862754bce7baa2020f682d2f64da6251b2.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/dfb306b3c796665fa6d06120873226862754bce7baa2020f682d2f64da6251b2.jpg)

![e964a8313402aff28ac27f2d1b4686cfcc4688ce199f3271defc622e5faa1759.jpg](../nips_results/1748_Improving%20Video%20Generation%20with%20Human%20Feedback/tables/e964a8313402aff28ac27f2d1b4686cfcc4688ce199f3271defc622e5faa1759.jpg)

## NFIG: Multi-Scale Autoregressive Image Generation via Frequency Ordering


### Images

![23d9465848930fa1fe69c797ab7071a41d99b32994af277aab27b511ecff945c.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/images/23d9465848930fa1fe69c797ab7071a41d99b32994af277aab27b511ecff945c.jpg)

![24649e251520f136e3e75bbd16e6bef9106d0e0288924c2f6d45cc1c7a4066e8.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/images/24649e251520f136e3e75bbd16e6bef9106d0e0288924c2f6d45cc1c7a4066e8.jpg)

![76110e93a7a925436f5a871984dd47f91acb89630ac5de55cb26b53f97ee5810.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/images/76110e93a7a925436f5a871984dd47f91acb89630ac5de55cb26b53f97ee5810.jpg)

![7ad6080478abd5643b224a6f4c3dbdfd28f7088175db65971f50c9b79cf9c1f0.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/images/7ad6080478abd5643b224a6f4c3dbdfd28f7088175db65971f50c9b79cf9c1f0.jpg)

![a396ddad3558dd810343f2a2f3222131d1c9c9c1af9bc2bcf32cca7a2aed2a8f.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/images/a396ddad3558dd810343f2a2f3222131d1c9c9c1af9bc2bcf32cca7a2aed2a8f.jpg)

![cb65c890ce0fba03ad69f2dd84cdeb34f0fb37db314177f979fd86feaeba870f.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/images/cb65c890ce0fba03ad69f2dd84cdeb34f0fb37db314177f979fd86feaeba870f.jpg)

### Tables

![03a3b873bb9b005a6b3fd8e9fc00c2827783b6252b4467abd1c61b53b01752c8.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/tables/03a3b873bb9b005a6b3fd8e9fc00c2827783b6252b4467abd1c61b53b01752c8.jpg)

![066a24c6fc9fe08cf62858c679d97eda674a63e1726d4cc15478f9a091e94131.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/tables/066a24c6fc9fe08cf62858c679d97eda674a63e1726d4cc15478f9a091e94131.jpg)

![36985d6b37ee1e2fe1a3f9886dc117ffd9586c6c91c0c3c74a9c4712c841f70a.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/tables/36985d6b37ee1e2fe1a3f9886dc117ffd9586c6c91c0c3c74a9c4712c841f70a.jpg)

![69b8ffef55a4fcdaadc59f06b4379c205ea8a0933ec96b779f8a2d4713c219f1.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/tables/69b8ffef55a4fcdaadc59f06b4379c205ea8a0933ec96b779f8a2d4713c219f1.jpg)

![6b1bc7df8671d161df2267cdd0601c1100c455fe9721c07fe4c315568acae180.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/tables/6b1bc7df8671d161df2267cdd0601c1100c455fe9721c07fe4c315568acae180.jpg)

![86d3c3fa4bd62d34ad7a400a356a2bf2f99a12429126c32f39db30857b9c5bb6.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/tables/86d3c3fa4bd62d34ad7a400a356a2bf2f99a12429126c32f39db30857b9c5bb6.jpg)

![e61b491e06c36bff0c20093b0247ae01fb94461891daeb16e6b41097b5707287.jpg](../nips_results/1749_NFIG_%20Multi-Scale%20Autoregressive%20Image%20Generation%20via%20Frequency%20Ordering/tables/e61b491e06c36bff0c20093b0247ae01fb94461891daeb16e6b41097b5707287.jpg)

## FlyLoRA: Boosting Task Decoupling and Parameter Efficiency via Implicit Rank-Wise Mixture-of-Experts


### Images

![36556b74aef6aa0d32d42af415b46e3360f0264cb8ad434c8cf6b33fa2fc631b.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/images/36556b74aef6aa0d32d42af415b46e3360f0264cb8ad434c8cf6b33fa2fc631b.jpg)

![b5d822820a69b513ea210b07e574d10ead663f171f41d708e72e2d742f8d0a3b.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/images/b5d822820a69b513ea210b07e574d10ead663f171f41d708e72e2d742f8d0a3b.jpg)

![f10dc8a81996a96d89880bd069ea8ede0ae4bfdd8ad59b72a9c1e93b49a81a33.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/images/f10dc8a81996a96d89880bd069ea8ede0ae4bfdd8ad59b72a9c1e93b49a81a33.jpg)

![fe19dcdc836bdd7ae3ec3c5363b9d3b3712dcfd594ec0d21ee89cdf8eea4e07c.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/images/fe19dcdc836bdd7ae3ec3c5363b9d3b3712dcfd594ec0d21ee89cdf8eea4e07c.jpg)

### Tables

![14887590b337c1222c8a16719ef6b04ce7f0a953f98971f289a043256fd25f70.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/14887590b337c1222c8a16719ef6b04ce7f0a953f98971f289a043256fd25f70.jpg)

![3893775fd351f10eb9fc7e599c036e967e6321139327007caaec0606891baee8.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/3893775fd351f10eb9fc7e599c036e967e6321139327007caaec0606891baee8.jpg)

![3c4bd67d783282273cd2ecf4bd861ff2bc86cfbfd5da9393288be835ca1e35ad.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/3c4bd67d783282273cd2ecf4bd861ff2bc86cfbfd5da9393288be835ca1e35ad.jpg)

![57de51f9555612050fce5edbbcbb0514adfcbd8127b2ddc431568b202fc3c9bf.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/57de51f9555612050fce5edbbcbb0514adfcbd8127b2ddc431568b202fc3c9bf.jpg)

![5961c44f163bbad5079cabbc02b8f8fc6af6cc1f920ad3c8d78c7c75ae511b25.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/5961c44f163bbad5079cabbc02b8f8fc6af6cc1f920ad3c8d78c7c75ae511b25.jpg)

![597cc8cdecf4d01e139ff2104121a68e705d26ea008ebfe691164013df473530.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/597cc8cdecf4d01e139ff2104121a68e705d26ea008ebfe691164013df473530.jpg)

![5e0c7e24d425b4ef703aa2e25f82cae1a15e274853fe43d892cb2e259df4588b.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/5e0c7e24d425b4ef703aa2e25f82cae1a15e274853fe43d892cb2e259df4588b.jpg)

![6da93142b9dfb9e1c55ffd71ae2c663a9ce5bccd3a1f72ed02a57df8a03c15a6.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/6da93142b9dfb9e1c55ffd71ae2c663a9ce5bccd3a1f72ed02a57df8a03c15a6.jpg)

![7ed67bf71f42962ee7e460d78ddc35c8e7fe5c812854bf5bf31c8e904fb2968c.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/7ed67bf71f42962ee7e460d78ddc35c8e7fe5c812854bf5bf31c8e904fb2968c.jpg)

![80326c6cdfc0731f9c6c37dc098b3336f7650027c79088010da29324271bd9e2.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/80326c6cdfc0731f9c6c37dc098b3336f7650027c79088010da29324271bd9e2.jpg)

![8f4fbd0e7527881cc07107f3cd13c595cad8422300f12a90dca421179d2a216c.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/8f4fbd0e7527881cc07107f3cd13c595cad8422300f12a90dca421179d2a216c.jpg)

![91526892b1d7e9f62ccef285f3f7e6551d59d46090713c378fa76a28d35d025f.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/91526892b1d7e9f62ccef285f3f7e6551d59d46090713c378fa76a28d35d025f.jpg)

![a2257c43022436bc0b6f7e34f9d673043baade6a2ec85d72eb16f8601851a715.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/a2257c43022436bc0b6f7e34f9d673043baade6a2ec85d72eb16f8601851a715.jpg)

![a6391a93e53d83f379373d74c4f4bb48e379eadb21d1ec2134661c8ca772a150.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/a6391a93e53d83f379373d74c4f4bb48e379eadb21d1ec2134661c8ca772a150.jpg)

![b5c1f250b7f071e3b7d9810841e51153c62f48fb95724da1cddea1c7a6f73d8e.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/b5c1f250b7f071e3b7d9810841e51153c62f48fb95724da1cddea1c7a6f73d8e.jpg)

![bfea286ae1117faa3137a9740696136d50cc14377e6313120f6f36bfbe5cf09e.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/bfea286ae1117faa3137a9740696136d50cc14377e6313120f6f36bfbe5cf09e.jpg)

![c7595b840fbb576f23f54e9b403789ed0596ea7b130c4f315b041722dda6ad38.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/c7595b840fbb576f23f54e9b403789ed0596ea7b130c4f315b041722dda6ad38.jpg)

![c94f48f209780581e7bb3a1217367906eb57591a2ae081b57746c369b57136fb.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/c94f48f209780581e7bb3a1217367906eb57591a2ae081b57746c369b57136fb.jpg)

![e6dd4f9c235d2e556a5440a054afa34f85248eed9eb0c04fbf94645233b4ec78.jpg](../nips_results/1750_FlyLoRA_%20Boosting%20Task%20Decoupling%20and%20Parameter%20Efficiency%20via%20Implicit%20Rank-Wise%20Mixture-of-Experts/tables/e6dd4f9c235d2e556a5440a054afa34f85248eed9eb0c04fbf94645233b4ec78.jpg)

## Compress & Cache: Vision token compression for efficient generation and retrieval


### Images

![0f658fd6fbec9eba7a60fa5dcdf84652783888503272d75371693ee60b7b7bf9.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/images/0f658fd6fbec9eba7a60fa5dcdf84652783888503272d75371693ee60b7b7bf9.jpg)

![32da42e595c92e50a1ac4701f5f787f4b6915eaa2784839c70910c54efa0836e.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/images/32da42e595c92e50a1ac4701f5f787f4b6915eaa2784839c70910c54efa0836e.jpg)

![3b689a1fc777f3e1a7fdf282808c985a3ac1fb1503f9d26a9c8a2540cf20ceef.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/images/3b689a1fc777f3e1a7fdf282808c985a3ac1fb1503f9d26a9c8a2540cf20ceef.jpg)

![4d1f12205ce1cb8b9aab5bb19b98aa5bff173b84e65de4f069836e644bf04d61.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/images/4d1f12205ce1cb8b9aab5bb19b98aa5bff173b84e65de4f069836e644bf04d61.jpg)

![aabe610cb3df0c3ea6a976f7a3b34d83ab808c993ec4c3fcac6f36c64d60bf33.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/images/aabe610cb3df0c3ea6a976f7a3b34d83ab808c993ec4c3fcac6f36c64d60bf33.jpg)

![cf12c38963d0b47d2b79c470fc24dcbadd0e08b6bc82060886ffa09301e11059.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/images/cf12c38963d0b47d2b79c470fc24dcbadd0e08b6bc82060886ffa09301e11059.jpg)

![de8dcaa57e12077c465fa681c550c84bd5498d421dcd3d8adf35e333207c3835.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/images/de8dcaa57e12077c465fa681c550c84bd5498d421dcd3d8adf35e333207c3835.jpg)

![f720e877bf5eeaba90fa91d2cb4506b3a4ad941bba0ad3e446d3a5c6ed769d00.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/images/f720e877bf5eeaba90fa91d2cb4506b3a4ad941bba0ad3e446d3a5c6ed769d00.jpg)

### Tables

![0284e5e0570abebcc50087d451170fed6dd8815fd0b7a42ba16b409c16ca922c.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/0284e5e0570abebcc50087d451170fed6dd8815fd0b7a42ba16b409c16ca922c.jpg)

![0d010267e14196afa950874f8f5b522a774db08d639633ce76d91a3de4627896.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/0d010267e14196afa950874f8f5b522a774db08d639633ce76d91a3de4627896.jpg)

![11d907a7294c915784f18822065c1237e0bb92d037aba8ab466412263c1bb890.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/11d907a7294c915784f18822065c1237e0bb92d037aba8ab466412263c1bb890.jpg)

![156c36e5a82114438c854a02c8810b7cdc13433986256b0536e12eaba2d43881.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/156c36e5a82114438c854a02c8810b7cdc13433986256b0536e12eaba2d43881.jpg)

![2732f42603072e8d6559ad42d859c30c1b07ad11988e05e2d99819ec79cc4c37.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/2732f42603072e8d6559ad42d859c30c1b07ad11988e05e2d99819ec79cc4c37.jpg)

![2cfdccd53507627990554c4112fd1efa00d132b3884ea420ea25aafa310e559f.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/2cfdccd53507627990554c4112fd1efa00d132b3884ea420ea25aafa310e559f.jpg)

![46da52d024fbc6e71f728bf3bed288d2c5032d0cb87e262c4793fe85f87414ca.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/46da52d024fbc6e71f728bf3bed288d2c5032d0cb87e262c4793fe85f87414ca.jpg)

![50ca6658db2cbb52a24b63daaf0491bebb2e22f92cebbd38525b86767a7e7ec8.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/50ca6658db2cbb52a24b63daaf0491bebb2e22f92cebbd38525b86767a7e7ec8.jpg)

![56a1a7893925051a4197c6fb3c62f573fb25341b9862b14426efa9866d7ab741.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/56a1a7893925051a4197c6fb3c62f573fb25341b9862b14426efa9866d7ab741.jpg)

![5af1b63691f193830122b02d2bd6c9aac8bd88cd29932df85f57d1e5f09618e6.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/5af1b63691f193830122b02d2bd6c9aac8bd88cd29932df85f57d1e5f09618e6.jpg)

![62e9b7be64701b993f79ec08a98e47bd3b1232d546f8e07f65d459ad804609fc.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/62e9b7be64701b993f79ec08a98e47bd3b1232d546f8e07f65d459ad804609fc.jpg)

![7362863dfc76e19fb5282bf23050723a3c44f50c41b294612ac3bba7eb407b84.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/7362863dfc76e19fb5282bf23050723a3c44f50c41b294612ac3bba7eb407b84.jpg)

![7492d133f8e28f6addf07174d3e8603e0f78484ab4b6b68d2912c5f2f7904e25.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/7492d133f8e28f6addf07174d3e8603e0f78484ab4b6b68d2912c5f2f7904e25.jpg)

![937d74b85d6a932327e8213865b5a5e94a327cce8c9bf30392d11a80983a30fe.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/937d74b85d6a932327e8213865b5a5e94a327cce8c9bf30392d11a80983a30fe.jpg)

![99c99d775ec740dad7cf8d4bb87a41c6b3f86bd1130080106b49906c6941ddb5.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/99c99d775ec740dad7cf8d4bb87a41c6b3f86bd1130080106b49906c6941ddb5.jpg)

![9ec43c194c0ff9c816911b59a9974f459d74bd6132222c9963a99336005991ad.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/9ec43c194c0ff9c816911b59a9974f459d74bd6132222c9963a99336005991ad.jpg)

![c2f44152d4386922e3b976483fdfffa0587260e7bfcde05e4da0433d76c4f4fb.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/c2f44152d4386922e3b976483fdfffa0587260e7bfcde05e4da0433d76c4f4fb.jpg)

![e6b13008ee1fbcbf6d7bdc9047f958a9aa5d1d047c7d440bdf7c658407ca80d0.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/e6b13008ee1fbcbf6d7bdc9047f958a9aa5d1d047c7d440bdf7c658407ca80d0.jpg)

![f6a9753bfeaca4e62d19eca9fc9e811631a9cf2462a73e428ba9e39dd2cb5585.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/f6a9753bfeaca4e62d19eca9fc9e811631a9cf2462a73e428ba9e39dd2cb5585.jpg)

![f6b5c24bf5a56efa716f363e1d410399893b5cd357ab18117492b8dc3c4c3b3b.jpg](../nips_results/1751_Compress%20%26%20Cache_%20Vision%20token%20compression%20for%20efficient%20generation%20and%20retrieval/tables/f6b5c24bf5a56efa716f363e1d410399893b5cd357ab18117492b8dc3c4c3b3b.jpg)

## Valid Inference with Imperfect Synthetic Data


### Images

![370baa772ac9496f057beae644203960a49b1c70711e27587122552dcc4aaec8.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/370baa772ac9496f057beae644203960a49b1c70711e27587122552dcc4aaec8.jpg)

![39d5140bf66a4bdd5f5282d55f13ac41e2e1152fb8c063da61cc632810da246a.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/39d5140bf66a4bdd5f5282d55f13ac41e2e1152fb8c063da61cc632810da246a.jpg)

![3a6b0d1e07140b784032d3e48a51929501f2d5f5a86565de8d7afe62f22b0181.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/3a6b0d1e07140b784032d3e48a51929501f2d5f5a86565de8d7afe62f22b0181.jpg)

![3e6accde79fefdf39e1231b394dd402bc08896e55e5c25faa7965e8bc3b30459.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/3e6accde79fefdf39e1231b394dd402bc08896e55e5c25faa7965e8bc3b30459.jpg)

![5539d3d4fd6a48a365b683ee0b93549d1fe145b816f30b119ca58b8d073e7580.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/5539d3d4fd6a48a365b683ee0b93549d1fe145b816f30b119ca58b8d073e7580.jpg)

![645958ec1c5daa0951e73066220c0ef4edbc1472c0dc8f5049d6fb3c2b1f810a.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/645958ec1c5daa0951e73066220c0ef4edbc1472c0dc8f5049d6fb3c2b1f810a.jpg)

![6745702b8a0ff5673ae56c34125c01c44ab237e10b0403d846599cdb37fad353.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/6745702b8a0ff5673ae56c34125c01c44ab237e10b0403d846599cdb37fad353.jpg)

![6cfb5e2faceb573d97eee86647dd5b824d0884c74a7af4836eb81b6c679aa809.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/6cfb5e2faceb573d97eee86647dd5b824d0884c74a7af4836eb81b6c679aa809.jpg)

![70b0d14b0c411d75d9200de9b7bf765f8bc9fc323a24c2d21d7220d6b2a0d6f5.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/70b0d14b0c411d75d9200de9b7bf765f8bc9fc323a24c2d21d7220d6b2a0d6f5.jpg)

![727498f75040e908d547b1b4baacb7e21247e5d8f0af328f091b71d2b52f9d53.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/727498f75040e908d547b1b4baacb7e21247e5d8f0af328f091b71d2b52f9d53.jpg)

![79bc92785081fdee51dd6a36f407b2ee52b57110293faeddea7cafe2044120ff.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/79bc92785081fdee51dd6a36f407b2ee52b57110293faeddea7cafe2044120ff.jpg)

![897b123738c81c6c2a40b6c9036d41b5b4d3d176a655de89000fe3bed7bd0f58.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/897b123738c81c6c2a40b6c9036d41b5b4d3d176a655de89000fe3bed7bd0f58.jpg)

![8c1b495c6e8f203c60e64e1882910c479c54526c36184610fa48d6af6599fbb8.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/8c1b495c6e8f203c60e64e1882910c479c54526c36184610fa48d6af6599fbb8.jpg)

![afdbdb7a31b9d22e6e79920382edca7d1bee59c79100940e83d3c3fddfa8379a.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/afdbdb7a31b9d22e6e79920382edca7d1bee59c79100940e83d3c3fddfa8379a.jpg)

![b680a5ddf26626fbb137feda81b8940fde041ce226694d4d94498afd89e62e23.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/b680a5ddf26626fbb137feda81b8940fde041ce226694d4d94498afd89e62e23.jpg)

![fcea134576f57f03216cb14dec85cf239846bf53472acdc855e60ec18b2b29f6.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/images/fcea134576f57f03216cb14dec85cf239846bf53472acdc855e60ec18b2b29f6.jpg)

### Tables

![1838ea925726dd6b543c74d0475b51861cba0cf5eb56a21dad58bebd7af33fd6.jpg](../nips_results/1752_Valid%20Inference%20with%20Imperfect%20Synthetic%20Data/tables/1838ea925726dd6b543c74d0475b51861cba0cf5eb56a21dad58bebd7af33fd6.jpg)

## Active Measurement: Efficient Estimation at Scale


### Images

![007e89ce46dcbab629b3d363dbb2371b7fefdf01a7d6af3a3781359e33559fe5.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/007e89ce46dcbab629b3d363dbb2371b7fefdf01a7d6af3a3781359e33559fe5.jpg)

![13dadc1a628ed4e36c50090c503c0a1732b167608752e7491248238dfc532ef4.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/13dadc1a628ed4e36c50090c503c0a1732b167608752e7491248238dfc532ef4.jpg)

![32f60b56049c0339e3382262604dd3b6ac0451a3102b617816e17afea348edb5.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/32f60b56049c0339e3382262604dd3b6ac0451a3102b617816e17afea348edb5.jpg)

![395e55c69c2eca11d3b4fc7f922ed649aad34723d3a96537c9ff108757908d71.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/395e55c69c2eca11d3b4fc7f922ed649aad34723d3a96537c9ff108757908d71.jpg)

![53e3b677ab384002f7891df2f47e6938e8a77ee6e11cf9b83485d984cf7b7c2d.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/53e3b677ab384002f7891df2f47e6938e8a77ee6e11cf9b83485d984cf7b7c2d.jpg)

![5c268c4d9188e705aded6ebe51a1b003f15a1108b2c4606c1538aa494b6c7c65.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/5c268c4d9188e705aded6ebe51a1b003f15a1108b2c4606c1538aa494b6c7c65.jpg)

![5d3013d813baa62f231720d38a6499d547f4b627f2746c5b7c6155b8a0551bae.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/5d3013d813baa62f231720d38a6499d547f4b627f2746c5b7c6155b8a0551bae.jpg)

![5dc77cd6530aede0cd2717a74fc9aaf34e258835af1af2d1979fe3522a855a61.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/5dc77cd6530aede0cd2717a74fc9aaf34e258835af1af2d1979fe3522a855a61.jpg)

![820fac6f208a5642f812a1febb9e34643615d00f398afd81a5f8cb65b7ba4fb9.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/820fac6f208a5642f812a1febb9e34643615d00f398afd81a5f8cb65b7ba4fb9.jpg)

![8f2197a21f84ff8047d8a9b6a0c71908c944ec48b77a42cdccedff631e19688e.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/8f2197a21f84ff8047d8a9b6a0c71908c944ec48b77a42cdccedff631e19688e.jpg)

![920f955d8ecde88018406beb9375bae09af6bc013af16b21284539bcba8ac788.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/920f955d8ecde88018406beb9375bae09af6bc013af16b21284539bcba8ac788.jpg)

![c73ef1d673f047e363fb27b11fdc04e54d60003c7b2809cfb6d108f646d04629.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/c73ef1d673f047e363fb27b11fdc04e54d60003c7b2809cfb6d108f646d04629.jpg)

![d0e1f38a1616ff9ccdb8b979735a3542707335023f259c853a51da801836747c.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/d0e1f38a1616ff9ccdb8b979735a3542707335023f259c853a51da801836747c.jpg)

![e91a15216d9d16d6e2b00c29dfa3fd637332d12dda1ee9fd07de94b56a062d7b.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/e91a15216d9d16d6e2b00c29dfa3fd637332d12dda1ee9fd07de94b56a062d7b.jpg)

![ed1500995f04bbd6594c66a520619c639ad63a3655207085f1b3ae33f6da5d6f.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/images/ed1500995f04bbd6594c66a520619c639ad63a3655207085f1b3ae33f6da5d6f.jpg)

### Tables

![4a7e40669b77d217b84bd508c2384bf1afe50a90be3302927511e1aa52687cc5.jpg](../nips_results/1753_Active%20Measurement_%20Efficient%20Estimation%20at%20Scale/tables/4a7e40669b77d217b84bd508c2384bf1afe50a90be3302927511e1aa52687cc5.jpg)

## Understanding Contrastive Learning via Gaussian Mixture Models


### Images

![1ffcef81048507ebb3eb8f908fa618516edf1f5080be25d778c2f94cd2006b45.jpg](../nips_results/1754_Understanding%20Contrastive%20Learning%20via%20Gaussian%20Mixture%20Models/images/1ffcef81048507ebb3eb8f908fa618516edf1f5080be25d778c2f94cd2006b45.jpg)

![29326848eee9294451df2461401037db69c74a177769fae84642231c9c95be93.jpg](../nips_results/1754_Understanding%20Contrastive%20Learning%20via%20Gaussian%20Mixture%20Models/images/29326848eee9294451df2461401037db69c74a177769fae84642231c9c95be93.jpg)

![64a2768d9b6a2527de4c02ebb8174ae92b68ef2435c069bc006ea377f28b6f6e.jpg](../nips_results/1754_Understanding%20Contrastive%20Learning%20via%20Gaussian%20Mixture%20Models/images/64a2768d9b6a2527de4c02ebb8174ae92b68ef2435c069bc006ea377f28b6f6e.jpg)

![e6c6684642b91cb6d82dd3307ee5167a408d12c74b3944ce434ff695b512410f.jpg](../nips_results/1754_Understanding%20Contrastive%20Learning%20via%20Gaussian%20Mixture%20Models/images/e6c6684642b91cb6d82dd3307ee5167a408d12c74b3944ce434ff695b512410f.jpg)

### Tables

![7f15d00880579385907b9a0993acf0d66e1dc56686d7325e6efe47f55bb5a09c.jpg](../nips_results/1754_Understanding%20Contrastive%20Learning%20via%20Gaussian%20Mixture%20Models/tables/7f15d00880579385907b9a0993acf0d66e1dc56686d7325e6efe47f55bb5a09c.jpg)

![bc34de06aa5a5f52f9448e13ed8c461eda8a53da3e7a67765ce6b461062a4d2e.jpg](../nips_results/1754_Understanding%20Contrastive%20Learning%20via%20Gaussian%20Mixture%20Models/tables/bc34de06aa5a5f52f9448e13ed8c461eda8a53da3e7a67765ce6b461062a4d2e.jpg)

![e3b5c1ae73f2e3581055ee09a24256103b5a86f0d6d10915cabb65ed75e377c8.jpg](../nips_results/1754_Understanding%20Contrastive%20Learning%20via%20Gaussian%20Mixture%20Models/tables/e3b5c1ae73f2e3581055ee09a24256103b5a86f0d6d10915cabb65ed75e377c8.jpg)

## A Unified Framework for Variable Selection in Model-Based Clustering with Missing Not at Random


### Images

![05ad868764828d3b9020410aa25f699dc7856d3bab6625803bcf6f730c81c93f.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/images/05ad868764828d3b9020410aa25f699dc7856d3bab6625803bcf6f730c81c93f.jpg)

![12c21d420f77d80304a8104f8bfcff0ffd8813a35bb160662d7ed6531e58070c.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/images/12c21d420f77d80304a8104f8bfcff0ffd8813a35bb160662d7ed6531e58070c.jpg)

![1709e2cd90debdb5e389bd58747d158b6fe95d843b710570df38e85b8b0bc0fc.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/images/1709e2cd90debdb5e389bd58747d158b6fe95d843b710570df38e85b8b0bc0fc.jpg)

![79f3e72ccbd648abe88fd084cffeb576fe91cf1d8bdd57b521a80d2a17122c38.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/images/79f3e72ccbd648abe88fd084cffeb576fe91cf1d8bdd57b521a80d2a17122c38.jpg)

![80b3e4f96757321b6ec150f7c1b63c644c8f55217b4ed6a2ddc79bb2c0280902.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/images/80b3e4f96757321b6ec150f7c1b63c644c8f55217b4ed6a2ddc79bb2c0280902.jpg)

![914b05cf2c26b6ec0998e2345e6fec4cb75cd86693c218d0a1e8b8127bb7e654.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/images/914b05cf2c26b6ec0998e2345e6fec4cb75cd86693c218d0a1e8b8127bb7e654.jpg)

![9b14cb830825c60175460a1067a6b7df78d37c718ce2b1138f90f516987b36f7.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/images/9b14cb830825c60175460a1067a6b7df78d37c718ce2b1138f90f516987b36f7.jpg)

![ceea1352ff3a4fc484d27e35e17dcfc1ab8ea2d50fc210619d2fd509e3be96a2.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/images/ceea1352ff3a4fc484d27e35e17dcfc1ab8ea2d50fc210619d2fd509e3be96a2.jpg)

![d796b94f91580e6011af51062e34511cfebfe09ed765ffe5eb38c8d413375e04.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/images/d796b94f91580e6011af51062e34511cfebfe09ed765ffe5eb38c8d413375e04.jpg)

### Tables

![014a6333ae310368e29eae558c01a6748e68a5652ad8f831b7d936d4dbc16bdf.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/014a6333ae310368e29eae558c01a6748e68a5652ad8f831b7d936d4dbc16bdf.jpg)

![42ac511914a72a5e8d2de689708855b09e24a16ea293f19cfd933fccb8324866.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/42ac511914a72a5e8d2de689708855b09e24a16ea293f19cfd933fccb8324866.jpg)

![6d923d4cba6219666bbdc789f77df4e010227ee19bbd2ef57130f10ce3c5ded2.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/6d923d4cba6219666bbdc789f77df4e010227ee19bbd2ef57130f10ce3c5ded2.jpg)

![832232e361c04cbe0561cb789dfec4969d8243aa039335c5d72067132c0380e0.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/832232e361c04cbe0561cb789dfec4969d8243aa039335c5d72067132c0380e0.jpg)

![8740223b112e1af881f6a560751c33adb2206ec4cb0f2cba9e185b548b5ab687.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/8740223b112e1af881f6a560751c33adb2206ec4cb0f2cba9e185b548b5ab687.jpg)

![ad0fe68200018d8852dafc0e5cc28c6bcf78ce480427633dad4a91f58ab8ac2c.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/ad0fe68200018d8852dafc0e5cc28c6bcf78ce480427633dad4a91f58ab8ac2c.jpg)

![c113ef7f4068b0aac04646f819bd0b858a5418e82cec82bd4978d5a40583399f.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/c113ef7f4068b0aac04646f819bd0b858a5418e82cec82bd4978d5a40583399f.jpg)

![c5a334821161c15cc5993bb08daaa9c53cb56065119c896c7949db1e2d28444e.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/c5a334821161c15cc5993bb08daaa9c53cb56065119c896c7949db1e2d28444e.jpg)

![cd12b1795de559e6da624b072922875f7cd2fb6bd497a4829906f7fdbae19a9f.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/cd12b1795de559e6da624b072922875f7cd2fb6bd497a4829906f7fdbae19a9f.jpg)

![d74a893db8b895c7c8c86a0f57169ed1d3b525f0a81b93fed733750ff7b0a53c.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/d74a893db8b895c7c8c86a0f57169ed1d3b525f0a81b93fed733750ff7b0a53c.jpg)

![f780aa7b4953e79e75c6ad35eaaa2965ca66cea218011e3189637c5acd1321bb.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/f780aa7b4953e79e75c6ad35eaaa2965ca66cea218011e3189637c5acd1321bb.jpg)

![f86a84df447ec8da5fc9b589a78d3827e814c207739c78f79951ab1a1720126f.jpg](../nips_results/1755_A%20Unified%20Framework%20for%20Variable%20Selection%20in%20Model-Based%20Clustering%20with%20Missing%20Not%20at%20Random/tables/f86a84df447ec8da5fc9b589a78d3827e814c207739c78f79951ab1a1720126f.jpg)

## Keep It on a Leash: Controllable Pseudo-label Generation Towards Realistic Long-Tailed Semi-Supervised Learning


### Images

![2abb2724a826ec79b43441d69923d6ff28acc0f8566616321f9eea10369fc8b5.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/images/2abb2724a826ec79b43441d69923d6ff28acc0f8566616321f9eea10369fc8b5.jpg)

![48d60a38b70c51a4a045643c466577faae2209607ddf2090149a7eb9ac3e8436.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/images/48d60a38b70c51a4a045643c466577faae2209607ddf2090149a7eb9ac3e8436.jpg)

![51d8cfdfe37b68955b303c136ab7b54e843f5cde59b32b6a2feaba738d167e5d.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/images/51d8cfdfe37b68955b303c136ab7b54e843f5cde59b32b6a2feaba738d167e5d.jpg)

![6e4a9df589a5ad771836640c5b903ea2ea4fd4e01c3c9d4bfa6b432417e97a1f.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/images/6e4a9df589a5ad771836640c5b903ea2ea4fd4e01c3c9d4bfa6b432417e97a1f.jpg)

![9e89728d6a3d51b881e7f64ff4d1bc45db2589f856c3f07bf51602d4c5efa070.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/images/9e89728d6a3d51b881e7f64ff4d1bc45db2589f856c3f07bf51602d4c5efa070.jpg)

![dfd1fbfac96c559da517db171ee32139d809fc1817914c091d1c4258cc1f82e5.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/images/dfd1fbfac96c559da517db171ee32139d809fc1817914c091d1c4258cc1f82e5.jpg)

![f029305ec68fb2fd2a7c4104c7fec7b1f5bff712374c8145b6ed82db9c86ced8.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/images/f029305ec68fb2fd2a7c4104c7fec7b1f5bff712374c8145b6ed82db9c86ced8.jpg)

### Tables

![0f801c342446642ddd935aac9df34ef56dd811c567abb75ad302d7f1059d0962.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/0f801c342446642ddd935aac9df34ef56dd811c567abb75ad302d7f1059d0962.jpg)

![0ffc9996bf850f1d27b3b4766169986f1462f3b32da167413a724d50965b427c.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/0ffc9996bf850f1d27b3b4766169986f1462f3b32da167413a724d50965b427c.jpg)

![2da1c32cf61add06fb818864e24b24c23adf37c63b9c18b3fe98ef983c8f687d.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/2da1c32cf61add06fb818864e24b24c23adf37c63b9c18b3fe98ef983c8f687d.jpg)

![4e431b559f86151f19a0617d463d6d3097f424a312b7f5dd9f664b2d86d82aed.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/4e431b559f86151f19a0617d463d6d3097f424a312b7f5dd9f664b2d86d82aed.jpg)

![5b2c38efd23b947922a89967d4cde24f579511ea2623afda93bbb703dc0fd94d.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/5b2c38efd23b947922a89967d4cde24f579511ea2623afda93bbb703dc0fd94d.jpg)

![73c77275d99f089d979049dd7e59ebfda227325fdad21b743c20ec75d5886f49.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/73c77275d99f089d979049dd7e59ebfda227325fdad21b743c20ec75d5886f49.jpg)

![7b2cb165a5a289045b74a9a48786d3b13759b472033a5acd27f6b10583ec0126.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/7b2cb165a5a289045b74a9a48786d3b13759b472033a5acd27f6b10583ec0126.jpg)

![8001ee48e92aaccafa1d9538ec09a2d4883958bc464a89da4b06afc044c14d17.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/8001ee48e92aaccafa1d9538ec09a2d4883958bc464a89da4b06afc044c14d17.jpg)

![8c46c529c0aed8d6e4f5bb6affb7da28ab83dd79fa686a0405d63d8dd664609e.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/8c46c529c0aed8d6e4f5bb6affb7da28ab83dd79fa686a0405d63d8dd664609e.jpg)

![a894f2a93dc6351cc7fecbd674a0e6013b2f0869f0b65624ad9b15229842e632.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/a894f2a93dc6351cc7fecbd674a0e6013b2f0869f0b65624ad9b15229842e632.jpg)

![cccd34c599dd0aa5e0501e998e9c598840cb3c7ca90ab907b7cff10e9f06ae04.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/cccd34c599dd0aa5e0501e998e9c598840cb3c7ca90ab907b7cff10e9f06ae04.jpg)

![f2dfc895eccb8cf94e4dc74210b338219d00620504c7c3a5d5c13ef25096d1d2.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/f2dfc895eccb8cf94e4dc74210b338219d00620504c7c3a5d5c13ef25096d1d2.jpg)

![f7ff5193a06038d168377b52d9c8e5877646b2a090e161f2720c5d6f7181ad3d.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/f7ff5193a06038d168377b52d9c8e5877646b2a090e161f2720c5d6f7181ad3d.jpg)

![f85bb38c1a0be593f043f95b77cb2f4d6a10f1bfc5b8bd3572df2617de041285.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/f85bb38c1a0be593f043f95b77cb2f4d6a10f1bfc5b8bd3572df2617de041285.jpg)

![f87d6d54302a8828712e3f89bebbd2197786eaa7c31d398d5f2489a8bc3c2fb9.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/f87d6d54302a8828712e3f89bebbd2197786eaa7c31d398d5f2489a8bc3c2fb9.jpg)

![fc1ab0003733d0d9313289ad73f052ef6eeea4e9d791d2f4a21eaff2be6d7784.jpg](../nips_results/1756_Keep%20It%20on%20a%20Leash_%20Controllable%20Pseudo-label%20Generation%20Towards%20Realistic%20Long-Tailed%20Semi-Supervis/tables/fc1ab0003733d0d9313289ad73f052ef6eeea4e9d791d2f4a21eaff2be6d7784.jpg)

## MoME: Mixture of Matryoshka Experts for Audio-Visual Speech Recognition


### Images

![1f5a9f4725f0f05f883fd8045a71f3bc1fee85e85870d7b840f5bb5a7c7b8676.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/images/1f5a9f4725f0f05f883fd8045a71f3bc1fee85e85870d7b840f5bb5a7c7b8676.jpg)

![321f0e71a991791a1e1cf5331842fceb76850cca99b51baedb6b42f98755cc7d.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/images/321f0e71a991791a1e1cf5331842fceb76850cca99b51baedb6b42f98755cc7d.jpg)

![3d627e2183cb4ed8fa085a30acb8551571aa701c9fc45c0e28efbc47b1fa9cd3.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/images/3d627e2183cb4ed8fa085a30acb8551571aa701c9fc45c0e28efbc47b1fa9cd3.jpg)

![840e27c563995cf69c416bf4b69b8bc26fa52d5ddf126f626aaa0061d7e10dbd.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/images/840e27c563995cf69c416bf4b69b8bc26fa52d5ddf126f626aaa0061d7e10dbd.jpg)

![8804aa9d8f1db99cc56bb340e4fda058f86e242f253310cd652f2443adf9e4b9.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/images/8804aa9d8f1db99cc56bb340e4fda058f86e242f253310cd652f2443adf9e4b9.jpg)

![91c552babc8bdcfcb7ce038c3e149f708fc2a2fdb1cbb7f23f7ea681f616e02c.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/images/91c552babc8bdcfcb7ce038c3e149f708fc2a2fdb1cbb7f23f7ea681f616e02c.jpg)

![b3f967b331f513e20d864c2c30becb1881085017eb90f0123a6bc10f8da95a45.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/images/b3f967b331f513e20d864c2c30becb1881085017eb90f0123a6bc10f8da95a45.jpg)

![bc0a8d7ef71a71f4e4608cea13e7baf6bf472b4bef286212d95b8f65d9cd02c4.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/images/bc0a8d7ef71a71f4e4608cea13e7baf6bf472b4bef286212d95b8f65d9cd02c4.jpg)

![c19442afbbfef1b496d9f5e2ae4e9004108e118cca91c2111b078e63c1b586b6.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/images/c19442afbbfef1b496d9f5e2ae4e9004108e118cca91c2111b078e63c1b586b6.jpg)

### Tables

![0f7bbb646fc3d4b500f4d941662a9a9e35b35abc6736649474edb6c04a325e2e.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/tables/0f7bbb646fc3d4b500f4d941662a9a9e35b35abc6736649474edb6c04a325e2e.jpg)

![2aae2692a2ec16c5a3ed38ef54017526e4a2950ea169c96bd45da6a425a5f6e0.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/tables/2aae2692a2ec16c5a3ed38ef54017526e4a2950ea169c96bd45da6a425a5f6e0.jpg)

![4cf11a7bc3edafe87662b01c6251025ea9755dc5a904b6d9964ceb1984e3f79c.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/tables/4cf11a7bc3edafe87662b01c6251025ea9755dc5a904b6d9964ceb1984e3f79c.jpg)

![4ed45bfe3912f55cd06e0f4801958fc5048abe5c78d14dd0de3d73b5acf081ce.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/tables/4ed45bfe3912f55cd06e0f4801958fc5048abe5c78d14dd0de3d73b5acf081ce.jpg)

![9e51cabd35ff4ace141136c2921b543d148ec95b534656c369b84c2b56194356.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/tables/9e51cabd35ff4ace141136c2921b543d148ec95b534656c369b84c2b56194356.jpg)

![b59f1e2381b3c6db6940201e75a4eb3e40d85e6ae9e643ef5c3ce13123e5ffb5.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/tables/b59f1e2381b3c6db6940201e75a4eb3e40d85e6ae9e643ef5c3ce13123e5ffb5.jpg)

![c2800b236d3ebde8c473a73fb34e56677c8c2f9e48a789c2d3b87a05e4cfe08b.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/tables/c2800b236d3ebde8c473a73fb34e56677c8c2f9e48a789c2d3b87a05e4cfe08b.jpg)

![c8fac124337cdeb1836111ae8a1441cd1c6230fe548f813bd72aa361773a07ab.jpg](../nips_results/1757_MoME_%20Mixture%20of%20Matryoshka%20Experts%20for%20Audio-Visual%20Speech%20Recognition/tables/c8fac124337cdeb1836111ae8a1441cd1c6230fe548f813bd72aa361773a07ab.jpg)

## Reconciling Geospatial Prediction and Retrieval via Sparse Representations


### Images

![51ac4202f893c507c42378abbcd525498010a47a802535ee7f142141c795dfde.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/images/51ac4202f893c507c42378abbcd525498010a47a802535ee7f142141c795dfde.jpg)

![fb05656add3905c7410a4277ce66165a44616d6eb7dc52ac1fc42b777ef47c9d.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/images/fb05656add3905c7410a4277ce66165a44616d6eb7dc52ac1fc42b777ef47c9d.jpg)

### Tables

![1317d2dd5fe7c1ffb535b734f38e7555adc6a4b9dde17fd7fbb4003eaf75a631.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/1317d2dd5fe7c1ffb535b734f38e7555adc6a4b9dde17fd7fbb4003eaf75a631.jpg)

![35fce70489f5a01a6183d6cb909629e60d039b73c7cbabb3f945346fde20cbf2.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/35fce70489f5a01a6183d6cb909629e60d039b73c7cbabb3f945346fde20cbf2.jpg)

![3649e33ea60d478bf72d8f04fc7a1ec6e0c308590f46eee34b6bb19549270ca4.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/3649e33ea60d478bf72d8f04fc7a1ec6e0c308590f46eee34b6bb19549270ca4.jpg)

![3b6606b3906a640c5856eed122a0daab67214ffb1e25e51b20abcb9211dad236.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/3b6606b3906a640c5856eed122a0daab67214ffb1e25e51b20abcb9211dad236.jpg)

![4e653e89d60d3d7d19cb556be4ced57bae710dc6318331bb2b15a4d89591cbcf.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/4e653e89d60d3d7d19cb556be4ced57bae710dc6318331bb2b15a4d89591cbcf.jpg)

![4f8f8ff221bd37fed0505145c27d4181b29b01bcede6594e4341db076cafbc3b.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/4f8f8ff221bd37fed0505145c27d4181b29b01bcede6594e4341db076cafbc3b.jpg)

![57d56031daa665a805b4c5d3c9d0ced13f5ea4d733dfaf7144b38700c6236a0e.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/57d56031daa665a805b4c5d3c9d0ced13f5ea4d733dfaf7144b38700c6236a0e.jpg)

![72fd15b6cc795bb44fef8a5e762294b283c57f6069005e73209b201e2645ada0.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/72fd15b6cc795bb44fef8a5e762294b283c57f6069005e73209b201e2645ada0.jpg)

![7728f0850c745ab0c169d6d763dd7dbaf25a0724e641c52818d23ad09b62186f.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/7728f0850c745ab0c169d6d763dd7dbaf25a0724e641c52818d23ad09b62186f.jpg)

![78a1b884b8de2fa8de0be495407b388ace7f66ee7d533caa9fb1cf65d4004f0c.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/78a1b884b8de2fa8de0be495407b388ace7f66ee7d533caa9fb1cf65d4004f0c.jpg)

![986c039ce7cee65897afe80e9e21a58175cc4b48d719708f954a4a7c5886436f.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/986c039ce7cee65897afe80e9e21a58175cc4b48d719708f954a4a7c5886436f.jpg)

![ac775e82ed735fdf93b967e752087abdb6b1cbb650aa232e7306390eb2da8aab.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/ac775e82ed735fdf93b967e752087abdb6b1cbb650aa232e7306390eb2da8aab.jpg)

![c41078c6c26d4acb4c07e620cb669ec03d189edf3d1d30513fcf8aaecf9188bb.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/c41078c6c26d4acb4c07e620cb669ec03d189edf3d1d30513fcf8aaecf9188bb.jpg)

![d8fbf39b21a3fe24aafc7a4528b015b7675349927dc554a0c8456b64e42e2270.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/d8fbf39b21a3fe24aafc7a4528b015b7675349927dc554a0c8456b64e42e2270.jpg)

![e06ff5bd7a54a3a4ccbf0873984c747cf22871e453491b4303da20d72e4571e6.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/e06ff5bd7a54a3a4ccbf0873984c747cf22871e453491b4303da20d72e4571e6.jpg)

![f9141080baeff2e181a6d09527271119a9e53e7d2dc63dd64a25fa3558d4baf2.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/f9141080baeff2e181a6d09527271119a9e53e7d2dc63dd64a25fa3558d4baf2.jpg)

![fa5b6689ec785a3ddda00447a161f4720697356afed73db5383a2668c66f68f9.jpg](../nips_results/1758_Reconciling%20Geospatial%20Prediction%20and%20Retrieval%20via%20Sparse%20Representations/tables/fa5b6689ec785a3ddda00447a161f4720697356afed73db5383a2668c66f68f9.jpg)

## Targeted Maximum Likelihood Learning: An Optimization Perspective


### Images

![0910d3f973cf422a9fed42939ec83b84aaa74adb373a301fc628a8e9a31b2a88.jpg](../nips_results/1759_Targeted%20Maximum%20Likelihood%20Learning_%20An%20Optimization%20Perspective/images/0910d3f973cf422a9fed42939ec83b84aaa74adb373a301fc628a8e9a31b2a88.jpg)

![64aa1b16ed3931a22ed1d8ce2da4843fd5d9c051d822f93cc626aeee917efd07.jpg](../nips_results/1759_Targeted%20Maximum%20Likelihood%20Learning_%20An%20Optimization%20Perspective/images/64aa1b16ed3931a22ed1d8ce2da4843fd5d9c051d822f93cc626aeee917efd07.jpg)

![67547e067168d6229dcb47a533a196c83ed9b75ac9c6bbdbe0eeb6cbeb88a21c.jpg](../nips_results/1759_Targeted%20Maximum%20Likelihood%20Learning_%20An%20Optimization%20Perspective/images/67547e067168d6229dcb47a533a196c83ed9b75ac9c6bbdbe0eeb6cbeb88a21c.jpg)

![a4761bee221ad632dcb87f229208857c053d8738075efaf35e4f0856804da6e1.jpg](../nips_results/1759_Targeted%20Maximum%20Likelihood%20Learning_%20An%20Optimization%20Perspective/images/a4761bee221ad632dcb87f229208857c053d8738075efaf35e4f0856804da6e1.jpg)

## CSGO: Content-Style Composition in Text-to-Image Generation


### Images

![02ff75074b6da18aae6c14d6769cceb9f6f5d91e63107fb477989b74ff319516.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/02ff75074b6da18aae6c14d6769cceb9f6f5d91e63107fb477989b74ff319516.jpg)

![0694fdea768b16a4fa3af299769963cdb1e4b5fc6cf6d2ab48adb8e11a5dff88.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/0694fdea768b16a4fa3af299769963cdb1e4b5fc6cf6d2ab48adb8e11a5dff88.jpg)

![106c7f8f762b22d1ea17d4966da6f68b42ff22fc9dcbe0122d5d26b2c3b6077f.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/106c7f8f762b22d1ea17d4966da6f68b42ff22fc9dcbe0122d5d26b2c3b6077f.jpg)

![198e8403ff9248edffce8573c173e48893de6628e119649a550c60b64fdd0582.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/198e8403ff9248edffce8573c173e48893de6628e119649a550c60b64fdd0582.jpg)

![1cd8300fd7feee93b18ccd22853f17b842896e149e562f27a50c03a474413cba.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/1cd8300fd7feee93b18ccd22853f17b842896e149e562f27a50c03a474413cba.jpg)

![2b1824fc420c9389c0c1b3eacdb5ae16b88f20e72f8512d1bfea571e87e2bb80.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/2b1824fc420c9389c0c1b3eacdb5ae16b88f20e72f8512d1bfea571e87e2bb80.jpg)

![2e7184e760108f1ba72f5fc7acf88b488d8418684cbf7231d68a7ac8341c5673.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/2e7184e760108f1ba72f5fc7acf88b488d8418684cbf7231d68a7ac8341c5673.jpg)

![3946c2025b22ee83844314d005b52a02c09dff6dcc5258f231c3c4c36ca7584a.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/3946c2025b22ee83844314d005b52a02c09dff6dcc5258f231c3c4c36ca7584a.jpg)

![3b74750246fba02cf997f2e4f4cd7ecacad8c59c01895d5351bf548421a5112e.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/3b74750246fba02cf997f2e4f4cd7ecacad8c59c01895d5351bf548421a5112e.jpg)

![3f5c62307ec5869ab38ac7a5f3eb27872f8b40bb7215ed4a30191a1e8743c73e.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/3f5c62307ec5869ab38ac7a5f3eb27872f8b40bb7215ed4a30191a1e8743c73e.jpg)

![42786c48a403e4332f0e899b5006ee4e30a3f60256dce30ba312d2ff6a9c7821.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/42786c48a403e4332f0e899b5006ee4e30a3f60256dce30ba312d2ff6a9c7821.jpg)

![4b66191c2abc3366dc2862d6e3baad929e41dbe6aca09c98363587000a6fa78e.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/4b66191c2abc3366dc2862d6e3baad929e41dbe6aca09c98363587000a6fa78e.jpg)

![50daa008a0f60dae5c5a26630d4811493636f41f383d030f87ab30875061267e.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/50daa008a0f60dae5c5a26630d4811493636f41f383d030f87ab30875061267e.jpg)

![53d4f5e428407d40e38c695c78976664776d08c395b84affc0931306bd6d64ff.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/53d4f5e428407d40e38c695c78976664776d08c395b84affc0931306bd6d64ff.jpg)

![596cf89ae462eb9f0c2e0c68baeb5f4900faca0aa37c9c95886e6d31550e34af.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/596cf89ae462eb9f0c2e0c68baeb5f4900faca0aa37c9c95886e6d31550e34af.jpg)

![5e8c4943d30d243cdfb6b26236504cc349dc98622c8e86e12dad7a3e6d0ee54b.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/5e8c4943d30d243cdfb6b26236504cc349dc98622c8e86e12dad7a3e6d0ee54b.jpg)

![6257aaf6cd3559e4006c8e7935d16edd014d9185e60d3cc98f8b6babcc64be9a.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/6257aaf6cd3559e4006c8e7935d16edd014d9185e60d3cc98f8b6babcc64be9a.jpg)

![65770b9385d155775365eecf1810a1dbc1f6df93f2e6c8dc9dc7298b5a16baa9.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/65770b9385d155775365eecf1810a1dbc1f6df93f2e6c8dc9dc7298b5a16baa9.jpg)

![6e882003d393a50bd8742f9799a5b67c4c4ecb9a09bdea57809320e281ca4dd8.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/6e882003d393a50bd8742f9799a5b67c4c4ecb9a09bdea57809320e281ca4dd8.jpg)

![786a4f25cdb9ceb2d48c1bddb468d7326297115e46d587d982c338609bee5f92.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/786a4f25cdb9ceb2d48c1bddb468d7326297115e46d587d982c338609bee5f92.jpg)

![8999f830f235bae3c786565d2f2fb8c98156e3e355a8a18c56643defc3c4b3ca.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/8999f830f235bae3c786565d2f2fb8c98156e3e355a8a18c56643defc3c4b3ca.jpg)

![8d5609068d07ccb590d676cd60760260096eaba1b028ac6b33b9d44e9105ea49.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/8d5609068d07ccb590d676cd60760260096eaba1b028ac6b33b9d44e9105ea49.jpg)

![91523e25ac26571dbb214a47fbad948cdeb29b784e0cc16a714dddb12acccda6.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/91523e25ac26571dbb214a47fbad948cdeb29b784e0cc16a714dddb12acccda6.jpg)

![9601be3d501f461d6ed275b2c99274e17706166fac77fa1fe2be2cdb586070f4.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/9601be3d501f461d6ed275b2c99274e17706166fac77fa1fe2be2cdb586070f4.jpg)

![98b127d548f253dc0e663b35de8355eda03c1997a449c2ffaadbeb6373566f83.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/98b127d548f253dc0e663b35de8355eda03c1997a449c2ffaadbeb6373566f83.jpg)

![b8e953768340abfe64602233c5d83f8969cd2a2af8d763a128b0af538a0cf44c.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/b8e953768340abfe64602233c5d83f8969cd2a2af8d763a128b0af538a0cf44c.jpg)

![bc799dd580ec1a18d2d0768f9be980892c24608e7e5ad8e4f7977fe6b5166497.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/bc799dd580ec1a18d2d0768f9be980892c24608e7e5ad8e4f7977fe6b5166497.jpg)

![cb6b63b9ffabec2b410c8e896197b3a0f3bb523443b7a44d1a96516e649d4952.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/cb6b63b9ffabec2b410c8e896197b3a0f3bb523443b7a44d1a96516e649d4952.jpg)

![cf57548d4095e0370af4d2ef7bbfc471def7751c0dd7a226fd510408619092b7.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/cf57548d4095e0370af4d2ef7bbfc471def7751c0dd7a226fd510408619092b7.jpg)

![d1472f5e189d17c11b659c5f852c58667942b39d380228b8976288d0dc583e79.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/d1472f5e189d17c11b659c5f852c58667942b39d380228b8976288d0dc583e79.jpg)

![d427f73c4d2e946d2bf99652dc44a30d6b38ad5124c857bbb4f7138fb21f9a00.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/d427f73c4d2e946d2bf99652dc44a30d6b38ad5124c857bbb4f7138fb21f9a00.jpg)

![d72e36a813a687f8f96cdccf0011a4741dedb6d4c53916919365fe08a871a67d.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/d72e36a813a687f8f96cdccf0011a4741dedb6d4c53916919365fe08a871a67d.jpg)

![dc767e3a9b6784728e55f8d37255fd52e31941757dc53e4bc8ae27ed3b28ca72.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/dc767e3a9b6784728e55f8d37255fd52e31941757dc53e4bc8ae27ed3b28ca72.jpg)

![e8394b18b37d538c25729ab7dec7917d4f342b8e7d9ada27aabd7c4fff14945e.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/e8394b18b37d538c25729ab7dec7917d4f342b8e7d9ada27aabd7c4fff14945e.jpg)

![eb7311d81b11dec3b97b13bfb601b6a8d9cae786428f811c61a963f8d47dc20a.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/eb7311d81b11dec3b97b13bfb601b6a8d9cae786428f811c61a963f8d47dc20a.jpg)

![f372419f97160a65c6411d982a9a5e29f514962802d5acde50cdcd4dd47a54c6.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/f372419f97160a65c6411d982a9a5e29f514962802d5acde50cdcd4dd47a54c6.jpg)

![fc4ed9c4b99fa8ae8cb9dad8d31e9ec02a67a4158423485710ff0cc29acf785d.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/fc4ed9c4b99fa8ae8cb9dad8d31e9ec02a67a4158423485710ff0cc29acf785d.jpg)

![fca3ef24c75e8e4ee01c35fce3dba6a9be66248a2431f378cfe2069847d7225d.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/images/fca3ef24c75e8e4ee01c35fce3dba6a9be66248a2431f378cfe2069847d7225d.jpg)

### Tables

![27ae883fd0fce2890a83ec21c6912038c9229405a0907bc32cd762fc6c5fb0ff.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/tables/27ae883fd0fce2890a83ec21c6912038c9229405a0907bc32cd762fc6c5fb0ff.jpg)

![41a7a808a74536f8391e453a6ee62ea859cd30d5e3f78fede80673cf4a248818.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/tables/41a7a808a74536f8391e453a6ee62ea859cd30d5e3f78fede80673cf4a248818.jpg)

![d85730d1958fb98ab0177fae35bf5d68b949e559dac371e2b6a58088d4edeb9e.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/tables/d85730d1958fb98ab0177fae35bf5d68b949e559dac371e2b6a58088d4edeb9e.jpg)

![d872d93c5722f1f74a999e9002179ddfa831b026483135ef7173396cfaf43634.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/tables/d872d93c5722f1f74a999e9002179ddfa831b026483135ef7173396cfaf43634.jpg)

![da2d94ff07654ce3d016debe1b5953d4316c4683b52f8f895efa7f26ccd74f7d.jpg](../nips_results/1760_CSGO_%20Content-Style%20Composition%20in%20Text-to-Image%20Generation/tables/da2d94ff07654ce3d016debe1b5953d4316c4683b52f8f895efa7f26ccd74f7d.jpg)

## Agentic Plan Caching: Test-Time Memory for Fast and Cost-Efficient LLM Agents


### Images

![466b0e24f5b11e6401d24dca7d10807582abd8937aeab4b273dc11c9566e71cd.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/images/466b0e24f5b11e6401d24dca7d10807582abd8937aeab4b273dc11c9566e71cd.jpg)

![b6233b33d6abc0666993a138dbd472efb7e57ddc961388ed910848b4dc263c1e.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/images/b6233b33d6abc0666993a138dbd472efb7e57ddc961388ed910848b4dc263c1e.jpg)

![c7ffef44348c2ee618fe6cc252f408a3cbe5a0bc4b7c511b00b24a4f83252741.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/images/c7ffef44348c2ee618fe6cc252f408a3cbe5a0bc4b7c511b00b24a4f83252741.jpg)

![d841aca0180edcd5d642f7e65bb6d5300c01825699f8f24b117fa6540a390402.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/images/d841aca0180edcd5d642f7e65bb6d5300c01825699f8f24b117fa6540a390402.jpg)

![f77edca8d0cfa04ae1b44a74aae350ecf6b65241311b13a6ca77c8b1cac4431b.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/images/f77edca8d0cfa04ae1b44a74aae350ecf6b65241311b13a6ca77c8b1cac4431b.jpg)

### Tables

![0e8494fad3a4250d88b9ba6275789fff4729f1dae99d9c2cae9aaf1d5e57772f.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/0e8494fad3a4250d88b9ba6275789fff4729f1dae99d9c2cae9aaf1d5e57772f.jpg)

![14c5bbce0c3fe820b6db3243d91a3cd577c83ff99344f84751d9f81f47b055e3.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/14c5bbce0c3fe820b6db3243d91a3cd577c83ff99344f84751d9f81f47b055e3.jpg)

![21524374118af2f63e1af1cb62087684a0c3d8abd71361c4219c15ea1f53eba9.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/21524374118af2f63e1af1cb62087684a0c3d8abd71361c4219c15ea1f53eba9.jpg)

![2dc7efea81eb2cd9559e2a98ed13266996a7d617b7832bcf74036aa161b56167.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/2dc7efea81eb2cd9559e2a98ed13266996a7d617b7832bcf74036aa161b56167.jpg)

![36a11060d472d9df261468464018e0be1e5fec1f4ce2aa1886e792c54989be86.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/36a11060d472d9df261468464018e0be1e5fec1f4ce2aa1886e792c54989be86.jpg)

![3ba0ab26940e5a47116c8643db86f0e1645a3215e1b812c60d1e6ff06289afdb.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/3ba0ab26940e5a47116c8643db86f0e1645a3215e1b812c60d1e6ff06289afdb.jpg)

![437bfdba2130f541805793012b57196021d173fff2c44cc6dd90eda9d6467c5f.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/437bfdba2130f541805793012b57196021d173fff2c44cc6dd90eda9d6467c5f.jpg)

![4df65d351b80b4e197c443f90b10b0b8756a5937121b7d404957f92c7dc3133b.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/4df65d351b80b4e197c443f90b10b0b8756a5937121b7d404957f92c7dc3133b.jpg)

![68bab3eb8358262078cd930f4255c5de1e10e6581aef3bc60503ad97e93ad596.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/68bab3eb8358262078cd930f4255c5de1e10e6581aef3bc60503ad97e93ad596.jpg)

![70b55349da0b930fff6a9d6f7bb2568ac1e89363a935e20ff2aeea6ccd0a2e4c.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/70b55349da0b930fff6a9d6f7bb2568ac1e89363a935e20ff2aeea6ccd0a2e4c.jpg)

![89c1a773b604ecb9096e15d59562869ce761a7c85f7348a02d685b6e121040f1.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/89c1a773b604ecb9096e15d59562869ce761a7c85f7348a02d685b6e121040f1.jpg)

![c2b1fdcca7295d6023e31ab60b0b9eb62a63dc2b0bb94454eafa5633fe943ad2.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/c2b1fdcca7295d6023e31ab60b0b9eb62a63dc2b0bb94454eafa5633fe943ad2.jpg)

![c976f799b2be99979d7890a9b3a01e5e0dbd9809d6ecdfc985c5fb4a5c91b1cb.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/c976f799b2be99979d7890a9b3a01e5e0dbd9809d6ecdfc985c5fb4a5c91b1cb.jpg)

![debb9ae9246447dea63cdf82693f28b5def223d2393a9667cc464b6db4a05a51.jpg](../nips_results/1761_Agentic%20Plan%20Caching_%20Test-Time%20Memory%20for%20Fast%20and%20Cost-Efficient%20LLM%20Agents/tables/debb9ae9246447dea63cdf82693f28b5def223d2393a9667cc464b6db4a05a51.jpg)

## ShoeFit: A New Dataset and Dual-image-stream DiT Framework for Virtual Footwear Try-On


### Images

![007634b507cbd826d057fc407ff96bfcf3ca0763ee8d42e9755a170e3ae4f5f1.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/007634b507cbd826d057fc407ff96bfcf3ca0763ee8d42e9755a170e3ae4f5f1.jpg)

![099ed340fff66bd417a9e82cffac7682d4571b1a84256b836d370b45b411ece4.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/099ed340fff66bd417a9e82cffac7682d4571b1a84256b836d370b45b411ece4.jpg)

![137918ea96a633fdede7c36fe804b661e5be7a930aaa0d706efd52b9120f5503.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/137918ea96a633fdede7c36fe804b661e5be7a930aaa0d706efd52b9120f5503.jpg)

![38f1dc2674906f509c946533b7076034ff2cbb6ed1dc97a4936357aaec6cbb65.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/38f1dc2674906f509c946533b7076034ff2cbb6ed1dc97a4936357aaec6cbb65.jpg)

![4c3a2678645be2d1bed90406027557484a6224c6f2a806a87b41eec1f6850eef.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/4c3a2678645be2d1bed90406027557484a6224c6f2a806a87b41eec1f6850eef.jpg)

![75677e3bdfd31f6ccfe257818e602614fede6e5855766981f5e68426b185abba.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/75677e3bdfd31f6ccfe257818e602614fede6e5855766981f5e68426b185abba.jpg)

![8b1456fd12b2a8e17b3b3e30ec05eeae3e8b9b59352d968030654075ea0fb338.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/8b1456fd12b2a8e17b3b3e30ec05eeae3e8b9b59352d968030654075ea0fb338.jpg)

![912e94411f08408758ec036a306a906918a7c55490992ba6bc6a74f062096e2c.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/912e94411f08408758ec036a306a906918a7c55490992ba6bc6a74f062096e2c.jpg)

![93baac216e6e01bf221d955688514a77e7d6eca368d6814fc5541aa90597c6bd.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/93baac216e6e01bf221d955688514a77e7d6eca368d6814fc5541aa90597c6bd.jpg)

![9c4543ebf06e8a982a24bae61f5cda63ec1d100df5a846daec2846d78da9a0fe.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/9c4543ebf06e8a982a24bae61f5cda63ec1d100df5a846daec2846d78da9a0fe.jpg)

![a00f6c84075906b06cc62ed729ab545ec5487a6ab77dda9f798c0561f907917b.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/a00f6c84075906b06cc62ed729ab545ec5487a6ab77dda9f798c0561f907917b.jpg)

![b78010d0bf1494185149d46ca6f161d19bb127096a79d41dfdb799d79840533c.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/b78010d0bf1494185149d46ca6f161d19bb127096a79d41dfdb799d79840533c.jpg)

![d67f5e48c3919ff382a727f94aff4f21e58c3e2c7aa5969e01a4811cda5d3d60.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/d67f5e48c3919ff382a727f94aff4f21e58c3e2c7aa5969e01a4811cda5d3d60.jpg)

![ef9d5f632eff405d741c7f1c27ac66bca224e43d9c8d9ea14adb55af3a78984e.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/images/ef9d5f632eff405d741c7f1c27ac66bca224e43d9c8d9ea14adb55af3a78984e.jpg)

### Tables

![73790b4dab0758774c441706e146c971e404428f23f885c8e2a89a5fdc2a98f7.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/tables/73790b4dab0758774c441706e146c971e404428f23f885c8e2a89a5fdc2a98f7.jpg)

![879468a99963982c2ce4e86faec6957643dd02dc475b0c6d6c37e011305f9437.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/tables/879468a99963982c2ce4e86faec6957643dd02dc475b0c6d6c37e011305f9437.jpg)

![8ec311c7da03c1b7504bcd1a962d257ff3bc21dd51e5b924fb1eacec5d4edf03.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/tables/8ec311c7da03c1b7504bcd1a962d257ff3bc21dd51e5b924fb1eacec5d4edf03.jpg)

![c965c036e25177d7bc552808e209691c3cf27b34d9b4801e8157bf4db3872fcc.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/tables/c965c036e25177d7bc552808e209691c3cf27b34d9b4801e8157bf4db3872fcc.jpg)

![d38514ab01e950ab3d837c0365fc9b1a556194bf3549271f2d98ee678a25c04f.jpg](../nips_results/1762_ShoeFit_%20A%20New%20Dataset%20and%20Dual-image-stream%20DiT%20Framework%20for%20Virtual%20Footwear%20Try-On/tables/d38514ab01e950ab3d837c0365fc9b1a556194bf3549271f2d98ee678a25c04f.jpg)

## Generalization Bounds for Rank-sparse Neural Networks


### Images

![638ae68ecad497b789e35da531053809fb3b48256a3fea9399a5a15cc960d92e.jpg](../nips_results/1763_Generalization%20Bounds%20for%20Rank-sparse%20Neural%20Networks/images/638ae68ecad497b789e35da531053809fb3b48256a3fea9399a5a15cc960d92e.jpg)

![93c9ce3470e7fa9ea4a42efcee94b9a87d07c33bf18dd413ed696a9338849051.jpg](../nips_results/1763_Generalization%20Bounds%20for%20Rank-sparse%20Neural%20Networks/images/93c9ce3470e7fa9ea4a42efcee94b9a87d07c33bf18dd413ed696a9338849051.jpg)

![9b96ab92c5d53d83947b2b96f46e758b0844e9b18eeedae50d9bec2fc022d943.jpg](../nips_results/1763_Generalization%20Bounds%20for%20Rank-sparse%20Neural%20Networks/images/9b96ab92c5d53d83947b2b96f46e758b0844e9b18eeedae50d9bec2fc022d943.jpg)

![d354ce0bf2ab605282db807c104986dbcde693cf09eaf1ecbdf3d2a91caf3cd5.jpg](../nips_results/1763_Generalization%20Bounds%20for%20Rank-sparse%20Neural%20Networks/images/d354ce0bf2ab605282db807c104986dbcde693cf09eaf1ecbdf3d2a91caf3cd5.jpg)

![e67f4fd57e40defe36618c36b3b672d86312206c8d5390f87aab68a4bb915584.jpg](../nips_results/1763_Generalization%20Bounds%20for%20Rank-sparse%20Neural%20Networks/images/e67f4fd57e40defe36618c36b3b672d86312206c8d5390f87aab68a4bb915584.jpg)

### Tables

![4e3a7aa102d2e39d3662425602abe4fa95d2869355d393acc5933e84096a6807.jpg](../nips_results/1763_Generalization%20Bounds%20for%20Rank-sparse%20Neural%20Networks/tables/4e3a7aa102d2e39d3662425602abe4fa95d2869355d393acc5933e84096a6807.jpg)

![74476d5e07dd333637abc9ea1477cd6f9a3284ab189b37c85f88c5fe7731394e.jpg](../nips_results/1763_Generalization%20Bounds%20for%20Rank-sparse%20Neural%20Networks/tables/74476d5e07dd333637abc9ea1477cd6f9a3284ab189b37c85f88c5fe7731394e.jpg)

![d52f3812a7d5122548db21ffa024f573f071f9e7ca053176f71ea829ea4b29ae.jpg](../nips_results/1763_Generalization%20Bounds%20for%20Rank-sparse%20Neural%20Networks/tables/d52f3812a7d5122548db21ffa024f573f071f9e7ca053176f71ea829ea4b29ae.jpg)

## 3DID: Direct 3D Inverse Design for Aerodynamics with Physics-Aware Optimization


### Images

![00d5e54b13fdfa1da6038322f4ac949a564bad3ea998b0cf2730e2a2f0c73f6a.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/images/00d5e54b13fdfa1da6038322f4ac949a564bad3ea998b0cf2730e2a2f0c73f6a.jpg)

![1ba332f2043f2268978e1594fd5f610b44064fa916f366f659c20a0e9e62b45d.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/images/1ba332f2043f2268978e1594fd5f610b44064fa916f366f659c20a0e9e62b45d.jpg)

![30e5bae23c7dc4e137925f379fd7cdc9f053e9f958707225462450c59a1b610d.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/images/30e5bae23c7dc4e137925f379fd7cdc9f053e9f958707225462450c59a1b610d.jpg)

![38d59fdaf829728a5636f2927c723151282594c37cff08f89f8b1046c61b98c8.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/images/38d59fdaf829728a5636f2927c723151282594c37cff08f89f8b1046c61b98c8.jpg)

![4063b1a0f96556224bc9f9f24a4e25b5ad7c40b93bbb3bf99b6fdee2d1efa903.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/images/4063b1a0f96556224bc9f9f24a4e25b5ad7c40b93bbb3bf99b6fdee2d1efa903.jpg)

![61b1dbdb68c02e848e5f1ccf63ff644f1277f0eae3c1cefbe14aa74b46229336.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/images/61b1dbdb68c02e848e5f1ccf63ff644f1277f0eae3c1cefbe14aa74b46229336.jpg)

![75d9144a095e3a4b35f4cc4fcac7f119e155d8284e27aa7acbafa8fba7f3de80.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/images/75d9144a095e3a4b35f4cc4fcac7f119e155d8284e27aa7acbafa8fba7f3de80.jpg)

![9c2742bc7f6f7cd94b6e4db816bd6571e7a9b940019f6410148e6d1a6a47c567.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/images/9c2742bc7f6f7cd94b6e4db816bd6571e7a9b940019f6410148e6d1a6a47c567.jpg)

![b8e28f813ad7d372028a41029ca7123103529c8cc99a38c782e7febd69bc0724.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/images/b8e28f813ad7d372028a41029ca7123103529c8cc99a38c782e7febd69bc0724.jpg)

![cbde0e559bfc78030ff6a6d4bebe32ceb8297200a0b5d93b5bb083f9c1796f37.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/images/cbde0e559bfc78030ff6a6d4bebe32ceb8297200a0b5d93b5bb083f9c1796f37.jpg)

![e383577d5c6e8f12bd5846f6a7ef91015d4062c782c0856075d797152224be0d.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/images/e383577d5c6e8f12bd5846f6a7ef91015d4062c782c0856075d797152224be0d.jpg)

### Tables

![1290ebdde867e7b35e133fb2d356a5b09a67f6802722314a6e7d69cf2f788955.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/tables/1290ebdde867e7b35e133fb2d356a5b09a67f6802722314a6e7d69cf2f788955.jpg)

![154507a570dc856b7f0f5fffe2c67e1a760f2ae58630b772fe201628e7170df4.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/tables/154507a570dc856b7f0f5fffe2c67e1a760f2ae58630b772fe201628e7170df4.jpg)

![1efa8c93626d051078139f31cb7160eaa1b7eeadb76c4f816aa0f9158228cd4f.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/tables/1efa8c93626d051078139f31cb7160eaa1b7eeadb76c4f816aa0f9158228cd4f.jpg)

![2e5cfb2d1e3457d6a86e37beed9badf63327dcb4e232ed18a561c4a678997451.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/tables/2e5cfb2d1e3457d6a86e37beed9badf63327dcb4e232ed18a561c4a678997451.jpg)

![45d2ba82c1524a7bddf3e02813245f97d8e9f41d747078dcef072daf54e67383.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/tables/45d2ba82c1524a7bddf3e02813245f97d8e9f41d747078dcef072daf54e67383.jpg)

![d842a89edb21684f6f9c4be4ae4117db9c8e3e74d075fda3d542e109b31edab4.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/tables/d842a89edb21684f6f9c4be4ae4117db9c8e3e74d075fda3d542e109b31edab4.jpg)

![df998c91b21de25f5d0fb5562776e81234cdc148768692b3c3f128c71c729800.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/tables/df998c91b21de25f5d0fb5562776e81234cdc148768692b3c3f128c71c729800.jpg)

![f4d03bcef83565a32c731b236871c301159f63f8a25d45facec57191d2251287.jpg](../nips_results/1764_3DID_%20Direct%203D%20Inverse%20Design%20for%20Aerodynamics%20with%20Physics-Aware%20Optimization/tables/f4d03bcef83565a32c731b236871c301159f63f8a25d45facec57191d2251287.jpg)

## PRSformer: Disease Prediction from Million-Scale Individual Genotypes


### Images

![005d1799da3e0e81dca43cb785998af779db76dadd3e1f2c86c59fec3562501a.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/images/005d1799da3e0e81dca43cb785998af779db76dadd3e1f2c86c59fec3562501a.jpg)

![1cf5ea4c860cc59d6801ff5aceab9f5897d3a927c5e77caca2a4ddeeaf533ad9.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/images/1cf5ea4c860cc59d6801ff5aceab9f5897d3a927c5e77caca2a4ddeeaf533ad9.jpg)

![403a89124cd4b41be10e467c7ca1162cf01e6bb6bd9e2cd23521c8f23bfcdc2b.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/images/403a89124cd4b41be10e467c7ca1162cf01e6bb6bd9e2cd23521c8f23bfcdc2b.jpg)

![423f8af58b3a7c0969fceadc56281fb89ed6af4920a6de173f84c21deaf47835.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/images/423f8af58b3a7c0969fceadc56281fb89ed6af4920a6de173f84c21deaf47835.jpg)

![44a543b0bb06418ec8da75456e286a38c28685f294916070c89a17ff8bb13ff1.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/images/44a543b0bb06418ec8da75456e286a38c28685f294916070c89a17ff8bb13ff1.jpg)

![4b6703f6cf9068d510891fdb8d1e6aa76d20dcb4d1089f277ac290ca3d391c60.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/images/4b6703f6cf9068d510891fdb8d1e6aa76d20dcb4d1089f277ac290ca3d391c60.jpg)

![680d55570a7366b8f96da107c569b055bdaeff8e2e7b0bc5c61237c6927b2a2b.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/images/680d55570a7366b8f96da107c569b055bdaeff8e2e7b0bc5c61237c6927b2a2b.jpg)

![75d02be12dc648f0026ce814b7aaa5b2f608928a48215f58d8e70f4b1142c83f.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/images/75d02be12dc648f0026ce814b7aaa5b2f608928a48215f58d8e70f4b1142c83f.jpg)

![b30f98e6363fa05ea3f2511c08d9befa24924fa21d7dd279601927035cdfe538.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/images/b30f98e6363fa05ea3f2511c08d9befa24924fa21d7dd279601927035cdfe538.jpg)

![cf47c6b65d3e14a3693cc5e493ec44cb369274be06d638d3fd47f9d47f80e951.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/images/cf47c6b65d3e14a3693cc5e493ec44cb369274be06d638d3fd47f9d47f80e951.jpg)

![ea55799f7953e17501c04626e4c5cb319ad969e6f6c246510e2edff454c41f8f.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/images/ea55799f7953e17501c04626e4c5cb319ad969e6f6c246510e2edff454c41f8f.jpg)

### Tables

![0c1014cc9ca59475bbb0ddfbb508ec6f12a94b496fb8da3d922fe1cc5e4043a5.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/0c1014cc9ca59475bbb0ddfbb508ec6f12a94b496fb8da3d922fe1cc5e4043a5.jpg)

![2740458a8beb683dfb7c0858c3f9d646ebb8f1493498e2a2177265d20e34108a.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/2740458a8beb683dfb7c0858c3f9d646ebb8f1493498e2a2177265d20e34108a.jpg)

![2f022c410aa896d38c59f8411c9ca7410ad2cb8fc0ee8e2fa429b3bfbb63bb46.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/2f022c410aa896d38c59f8411c9ca7410ad2cb8fc0ee8e2fa429b3bfbb63bb46.jpg)

![426fb3f08432ce7ec71cafdeb136c7a82296555698597f5eb0528278f66dbf46.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/426fb3f08432ce7ec71cafdeb136c7a82296555698597f5eb0528278f66dbf46.jpg)

![4802adca726229e5f026a4979e3a79635bb84bd1abf0341fdf70c86c2effaf43.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/4802adca726229e5f026a4979e3a79635bb84bd1abf0341fdf70c86c2effaf43.jpg)

![4afb87a0751ffa9bc011bc70eed6dd0053952c2da7fe52079da0710a6b7c2a30.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/4afb87a0751ffa9bc011bc70eed6dd0053952c2da7fe52079da0710a6b7c2a30.jpg)

![77fba3cfb55fa3a9fab12d809a90958168ccaa74612fc4d59004d5111bad4021.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/77fba3cfb55fa3a9fab12d809a90958168ccaa74612fc4d59004d5111bad4021.jpg)

![7f8780700a532913e4c6bc1e25b4d3a20066de60c7d477124fc047c3e3c76669.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/7f8780700a532913e4c6bc1e25b4d3a20066de60c7d477124fc047c3e3c76669.jpg)

![8ef02c079e92d0e7179d63d35e6577a7142b79f4c4f1f28be2547533e0799260.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/8ef02c079e92d0e7179d63d35e6577a7142b79f4c4f1f28be2547533e0799260.jpg)

![a330c769e8d128faa71932de03bb0df5941c924a35dc8644506e585b4e477976.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/a330c769e8d128faa71932de03bb0df5941c924a35dc8644506e585b4e477976.jpg)

![b04cf6664d1be0956ce598d193d447cc2270c54f86ef2f56a6f928c18f5ffd70.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/b04cf6664d1be0956ce598d193d447cc2270c54f86ef2f56a6f928c18f5ffd70.jpg)

![b888f0d6bdaf1d16d9a5c6994d54bfa3abf541525b0124ab7fc4e8c80c0aeb19.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/b888f0d6bdaf1d16d9a5c6994d54bfa3abf541525b0124ab7fc4e8c80c0aeb19.jpg)

![c13c1d4ed480105b5367ee8f43f09524604c2bf69ce12bb990577e7e89b9c435.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/c13c1d4ed480105b5367ee8f43f09524604c2bf69ce12bb990577e7e89b9c435.jpg)

![c5a7cf4b7287454707daad0f1b20002037da5f0974438e8b0f4c85abbc41f06e.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/c5a7cf4b7287454707daad0f1b20002037da5f0974438e8b0f4c85abbc41f06e.jpg)

![e7ca55c1680c3e4cdcb7f03ac60e6fece16e5dfcf3a9aacb1fa7b71d4cae6524.jpg](../nips_results/1765_PRSformer_%20Disease%20Prediction%20from%20Million-Scale%20Individual%20Genotypes/tables/e7ca55c1680c3e4cdcb7f03ac60e6fece16e5dfcf3a9aacb1fa7b71d4cae6524.jpg)

## Enhancing Graph Classification Robustness with Singular Pooling


### Images

![68c51640d6d9a0bc15e276f7010b85364a597652aeec785a9d93e73f8eadcfe5.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/images/68c51640d6d9a0bc15e276f7010b85364a597652aeec785a9d93e73f8eadcfe5.jpg)

![768777c99e6a2415075277fbf2de19a6d37c0f2fe4f1497b37b7fd4dbcbe41cc.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/images/768777c99e6a2415075277fbf2de19a6d37c0f2fe4f1497b37b7fd4dbcbe41cc.jpg)

![93c577f3739ecff428ab04c41f87434abc2b62bba080e92b7ef5a19494d7e7d2.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/images/93c577f3739ecff428ab04c41f87434abc2b62bba080e92b7ef5a19494d7e7d2.jpg)

![a153c874260bfa82f6436f39590023c4321adf7189d69481f9eeb76198ba5f04.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/images/a153c874260bfa82f6436f39590023c4321adf7189d69481f9eeb76198ba5f04.jpg)

![b2ef0025246e8f764eb789822b86304e951b0e3055249e6acdcb53b4aea1708d.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/images/b2ef0025246e8f764eb789822b86304e951b0e3055249e6acdcb53b4aea1708d.jpg)

### Tables

![15c1c895751c664c071aa3b1d55163dd47062bf895f60890d65399eec13e4769.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/tables/15c1c895751c664c071aa3b1d55163dd47062bf895f60890d65399eec13e4769.jpg)

![175f210227a23c6fa145c58a9f5366362eda819544f61e9f757d42032341bbeb.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/tables/175f210227a23c6fa145c58a9f5366362eda819544f61e9f757d42032341bbeb.jpg)

![1eaa9ac183446ef323c324d9cef5035711b10f4f263d84778bc4c69174766b80.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/tables/1eaa9ac183446ef323c324d9cef5035711b10f4f263d84778bc4c69174766b80.jpg)

![3d6633d9b437e3e99ee37b1d2840beda1945a4b9956e3b33fa62df48dac3ade0.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/tables/3d6633d9b437e3e99ee37b1d2840beda1945a4b9956e3b33fa62df48dac3ade0.jpg)

![4a3cc6519ad4a25f8be0404244c451d2fe2791c8aec24d089d0076b4a2b84834.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/tables/4a3cc6519ad4a25f8be0404244c451d2fe2791c8aec24d089d0076b4a2b84834.jpg)

![5167bc00aa97e3aa9ebaa9f7fa9f5ee0f19d6939e9799b1845428ddba5746a9d.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/tables/5167bc00aa97e3aa9ebaa9f7fa9f5ee0f19d6939e9799b1845428ddba5746a9d.jpg)

![e452accf7f17de54b954d559a0f7376533b5f26a5fa156187ece73f82b83ba3a.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/tables/e452accf7f17de54b954d559a0f7376533b5f26a5fa156187ece73f82b83ba3a.jpg)

![f9c604cc2e04932f7c08d0d8d867f0a4058d12372eb06f5ed5d76fae0d3250fb.jpg](../nips_results/1766_Enhancing%20Graph%20Classification%20Robustness%20with%20Singular%20Pooling/tables/f9c604cc2e04932f7c08d0d8d867f0a4058d12372eb06f5ed5d76fae0d3250fb.jpg)

## The Price of Opportunity Fairness in Matroid Allocation Problems


### Images

![088a98e074badfb841d11db4aef09a59c8ee74a756be55450d74f4e5426d88b7.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/088a98e074badfb841d11db4aef09a59c8ee74a756be55450d74f4e5426d88b7.jpg)

![0f035fcc59fc827bbde71e63a75fe26b83095c98924bd555b0f65c6eaa2009cc.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/0f035fcc59fc827bbde71e63a75fe26b83095c98924bd555b0f65c6eaa2009cc.jpg)

![2ec442f88406396d342e0f0aabf022a96fbaa2aae38fa1613071b1eec983f60a.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/2ec442f88406396d342e0f0aabf022a96fbaa2aae38fa1613071b1eec983f60a.jpg)

![313b29936e5045f8f9f2e1b2ecd2da9befa6b94d0c91f40aa40aa049712ef4c0.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/313b29936e5045f8f9f2e1b2ecd2da9befa6b94d0c91f40aa40aa049712ef4c0.jpg)

![3363b6e0381b47b443f45807f7141438a4e79dd6850f257a94dc90ae8f0b424d.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/3363b6e0381b47b443f45807f7141438a4e79dd6850f257a94dc90ae8f0b424d.jpg)

![42d72b7358b62488b2c52f9b93201828e142fe90be187a90c17e6dcd6052f2a7.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/42d72b7358b62488b2c52f9b93201828e142fe90be187a90c17e6dcd6052f2a7.jpg)

![51f13e48035700255eb93f114fe6e1bfb58417186b99d82bc6059f2d7851ba0f.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/51f13e48035700255eb93f114fe6e1bfb58417186b99d82bc6059f2d7851ba0f.jpg)

![56f451240855e96af6021f19f01a2fb7c0b2b27d79ab16c8a8978cd1de9022c6.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/56f451240855e96af6021f19f01a2fb7c0b2b27d79ab16c8a8978cd1de9022c6.jpg)

![61f86ab9568ffcbb69d4f0007298d9850b8484aaf1b8aa6f6c4481b1176d7e11.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/61f86ab9568ffcbb69d4f0007298d9850b8484aaf1b8aa6f6c4481b1176d7e11.jpg)

![673d060ad863e934931a0bb6e9dcb83fd55c3a7617e9dcef0da6f906e349e5a8.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/673d060ad863e934931a0bb6e9dcb83fd55c3a7617e9dcef0da6f906e349e5a8.jpg)

![6eb0af3e39eb5aae25f99f9bc7c43db52d8db41496f6b3f5c8880c83d56af5cd.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/6eb0af3e39eb5aae25f99f9bc7c43db52d8db41496f6b3f5c8880c83d56af5cd.jpg)

![6f755fd33c1f4f5ad64a06b5b4f57e8360ea86802554de6de953fb0c8b0b8e37.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/6f755fd33c1f4f5ad64a06b5b4f57e8360ea86802554de6de953fb0c8b0b8e37.jpg)

![a50cb2e78ef7cd8c96eb7e2848194da9b99b12fad29e8a7d47558c7b61a516da.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/a50cb2e78ef7cd8c96eb7e2848194da9b99b12fad29e8a7d47558c7b61a516da.jpg)

![a6e24d44380c514a77de58dafc3c0504b250a4ed3212c64f99884a6ecc75c153.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/a6e24d44380c514a77de58dafc3c0504b250a4ed3212c64f99884a6ecc75c153.jpg)

![ad5bc15b9f5496671c67e90cc9d2f13454e9bb69c1dc1e81901e1ade5397206f.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/ad5bc15b9f5496671c67e90cc9d2f13454e9bb69c1dc1e81901e1ade5397206f.jpg)

![b0895109ab4726f7235500e693bea391b0d8174935bb87f8e5ba9d26b27d50cb.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/b0895109ab4726f7235500e693bea391b0d8174935bb87f8e5ba9d26b27d50cb.jpg)

![baf9546e27d288db642fea5fcd5756dae85c906c09d194488035167c2498105c.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/baf9546e27d288db642fea5fcd5756dae85c906c09d194488035167c2498105c.jpg)

![bdb4ea5c3379da43443818276c57b4d5f25c2610da2eec6516205ddb18faeff7.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/bdb4ea5c3379da43443818276c57b4d5f25c2610da2eec6516205ddb18faeff7.jpg)

![df9aef2cfc8515e7dd0d216f707b6ddd64784a2435f9fa1ff10abe9086711698.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/df9aef2cfc8515e7dd0d216f707b6ddd64784a2435f9fa1ff10abe9086711698.jpg)

![e3a1777ffa559c6c7b31a976957da8a468bc4ce354ce2729f642cd3fa176bfd6.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/e3a1777ffa559c6c7b31a976957da8a468bc4ce354ce2729f642cd3fa176bfd6.jpg)

![e5e3455d4832ad0e8f1cc0da155406221fbd501894ed05843ecea1bdd26ca8d1.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/e5e3455d4832ad0e8f1cc0da155406221fbd501894ed05843ecea1bdd26ca8d1.jpg)

![f616a26f2eb559466b91682c0a92e181e331f7134ba966bbb1277ca827256238.jpg](../nips_results/1767_The%20Price%20of%20Opportunity%20Fairness%20in%20Matroid%20Allocation%20Problems/images/f616a26f2eb559466b91682c0a92e181e331f7134ba966bbb1277ca827256238.jpg)

## The Narrow Gate: Localized Image-Text Communication in Native Multimodal Models


### Images

![2f58db1cc96734821ac1ffbb4b1af68907242a1d518b0cc29f343ba3c27d53ea.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/images/2f58db1cc96734821ac1ffbb4b1af68907242a1d518b0cc29f343ba3c27d53ea.jpg)

![736cd3125cce3f5510d5d8c17f1336f661be230936ace97f2b5a2926519f7b25.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/images/736cd3125cce3f5510d5d8c17f1336f661be230936ace97f2b5a2926519f7b25.jpg)

![92602b657bf632d2495dd7453d488fc971f37052c98ad84924f61f64313018d8.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/images/92602b657bf632d2495dd7453d488fc971f37052c98ad84924f61f64313018d8.jpg)

![a9506b8677199023749ffbce9ea7502bb05184a427147f3ec063b322de9efd6b.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/images/a9506b8677199023749ffbce9ea7502bb05184a427147f3ec063b322de9efd6b.jpg)

![b28bf1f34b7f72471551cb4f6143305cf46ace13410fbb84239f670ea2ecd79b.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/images/b28bf1f34b7f72471551cb4f6143305cf46ace13410fbb84239f670ea2ecd79b.jpg)

![bf23da2e94fa0854f57d01267020850e111bb4e97c5659f8e0fee0d3cc054cb8.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/images/bf23da2e94fa0854f57d01267020850e111bb4e97c5659f8e0fee0d3cc054cb8.jpg)

![d588ee605708e072d88b5784e587f3e7b326f65e257ef31ffc4770ea1fa132c7.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/images/d588ee605708e072d88b5784e587f3e7b326f65e257ef31ffc4770ea1fa132c7.jpg)

![f869472d5dc8ecdfb76e491e03cc6b1a146831e4095b577fc68ce1f82e9f3928.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/images/f869472d5dc8ecdfb76e491e03cc6b1a146831e4095b577fc68ce1f82e9f3928.jpg)

![fe55a7f9213ad912d8735a6e7cef3f778e8687e117f3fc2427c2218b6101209b.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/images/fe55a7f9213ad912d8735a6e7cef3f778e8687e117f3fc2427c2218b6101209b.jpg)

### Tables

![0fe04ec990287c9407f67e70e2405fb4eb6f0c6884de6ab7e8b9307aa435084a.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/tables/0fe04ec990287c9407f67e70e2405fb4eb6f0c6884de6ab7e8b9307aa435084a.jpg)

![659150eeec59aa642b7424e632d6aeb9762c9b925d7a2ee321a45fb98dbb49ce.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/tables/659150eeec59aa642b7424e632d6aeb9762c9b925d7a2ee321a45fb98dbb49ce.jpg)

![72aa365e3b4b1e2c50e4ce99337029fff75dda445b14784abfc283039f8c6a90.jpg](../nips_results/1768_The%20Narrow%20Gate_%20Localized%20Image-Text%20Communication%20in%20Native%20Multimodal%20Models/tables/72aa365e3b4b1e2c50e4ce99337029fff75dda445b14784abfc283039f8c6a90.jpg)

## EAReranker: Efficient Embedding Adequacy Assessment for Retrieval Augmented Generation


### Images

![00efab6fb0d18bdb43b4300baa2cef8266a51afee87d82586641f474857e5280.jpg](../nips_results/1769_EAReranker_%20Efficient%20Embedding%20Adequacy%20Assessment%20for%20Retrieval%20Augmented%20Generation/images/00efab6fb0d18bdb43b4300baa2cef8266a51afee87d82586641f474857e5280.jpg)

![42e51b7566e3dfef02f146dd15cd7911a724d45c7dc5d7d930c70a3b90df11b1.jpg](../nips_results/1769_EAReranker_%20Efficient%20Embedding%20Adequacy%20Assessment%20for%20Retrieval%20Augmented%20Generation/images/42e51b7566e3dfef02f146dd15cd7911a724d45c7dc5d7d930c70a3b90df11b1.jpg)

![4dd2f621ed186bcd47105e74f4ac8d3235bb56a7e07b033c10b2028c05f102a0.jpg](../nips_results/1769_EAReranker_%20Efficient%20Embedding%20Adequacy%20Assessment%20for%20Retrieval%20Augmented%20Generation/images/4dd2f621ed186bcd47105e74f4ac8d3235bb56a7e07b033c10b2028c05f102a0.jpg)

### Tables

![0113c9e27388286b6b6956809d3544a3c7bde947e2c8e3b18af78e99fff45f33.jpg](../nips_results/1769_EAReranker_%20Efficient%20Embedding%20Adequacy%20Assessment%20for%20Retrieval%20Augmented%20Generation/tables/0113c9e27388286b6b6956809d3544a3c7bde947e2c8e3b18af78e99fff45f33.jpg)

![23a04c5ba566425a2e24869762cb5c821c705f811e6b95eac0e83ac8aace8296.jpg](../nips_results/1769_EAReranker_%20Efficient%20Embedding%20Adequacy%20Assessment%20for%20Retrieval%20Augmented%20Generation/tables/23a04c5ba566425a2e24869762cb5c821c705f811e6b95eac0e83ac8aace8296.jpg)

![6df6660b713f6afe8285a767632fcc579ec26ae1848985b18b9662d916bb6ba3.jpg](../nips_results/1769_EAReranker_%20Efficient%20Embedding%20Adequacy%20Assessment%20for%20Retrieval%20Augmented%20Generation/tables/6df6660b713f6afe8285a767632fcc579ec26ae1848985b18b9662d916bb6ba3.jpg)

![7f37d55ff1ef3d85a5b6f4f8707ff54ef65cc3ee03230e265d42a635448e5418.jpg](../nips_results/1769_EAReranker_%20Efficient%20Embedding%20Adequacy%20Assessment%20for%20Retrieval%20Augmented%20Generation/tables/7f37d55ff1ef3d85a5b6f4f8707ff54ef65cc3ee03230e265d42a635448e5418.jpg)

![97e1c82d09cf149ea8ecd08bf23ef96324a383ebf099c19477be19b8c5609b00.jpg](../nips_results/1769_EAReranker_%20Efficient%20Embedding%20Adequacy%20Assessment%20for%20Retrieval%20Augmented%20Generation/tables/97e1c82d09cf149ea8ecd08bf23ef96324a383ebf099c19477be19b8c5609b00.jpg)

![cfec780a93547e24c317daa9f07dce33e9e4c1963668248507603ceea9137d1c.jpg](../nips_results/1769_EAReranker_%20Efficient%20Embedding%20Adequacy%20Assessment%20for%20Retrieval%20Augmented%20Generation/tables/cfec780a93547e24c317daa9f07dce33e9e4c1963668248507603ceea9137d1c.jpg)

![ee7338ebaeb4e82e1706ac7d757106257297ad6befed6e361acd589ab4098983.jpg](../nips_results/1769_EAReranker_%20Efficient%20Embedding%20Adequacy%20Assessment%20for%20Retrieval%20Augmented%20Generation/tables/ee7338ebaeb4e82e1706ac7d757106257297ad6befed6e361acd589ab4098983.jpg)

## Behavior Injection: Preparing Language Models for Reinforcement Learning


### Images

![01067b818c67cef882ce232d3f831ef4a8de1bee801822b7f48d47a0d9240fb5.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/images/01067b818c67cef882ce232d3f831ef4a8de1bee801822b7f48d47a0d9240fb5.jpg)

![10f54441e700dff951aa9575954c0d4c1ef90dbc9adeae0c10b14111ede0d391.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/images/10f54441e700dff951aa9575954c0d4c1ef90dbc9adeae0c10b14111ede0d391.jpg)

![321284a5ca75a3bc7344e2d9c731314b52cba27617ec289a1cf496045b18d594.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/images/321284a5ca75a3bc7344e2d9c731314b52cba27617ec289a1cf496045b18d594.jpg)

![4bf2950bf3883726615652a6bbaa32ec128e38788ec0af31a115cd49fea44fd1.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/images/4bf2950bf3883726615652a6bbaa32ec128e38788ec0af31a115cd49fea44fd1.jpg)

![67f8d1a928f66f4d4fdebcd232e3b37faa29bb581c09a771bf26c51ffe17fbdc.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/images/67f8d1a928f66f4d4fdebcd232e3b37faa29bb581c09a771bf26c51ffe17fbdc.jpg)

![713863108fd51ff2bd0be235065ff81c021f879781c9ba40e8d9301e5139d627.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/images/713863108fd51ff2bd0be235065ff81c021f879781c9ba40e8d9301e5139d627.jpg)

![8c0a9819351c22b423afcff0e626f1285dd2d3c7c08f2f559a6e422aff91e589.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/images/8c0a9819351c22b423afcff0e626f1285dd2d3c7c08f2f559a6e422aff91e589.jpg)

![bbe9ce76c09a88c21135c4b26c99f22c1ae3d8d29d6a73530c4249d681fa76aa.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/images/bbe9ce76c09a88c21135c4b26c99f22c1ae3d8d29d6a73530c4249d681fa76aa.jpg)

![bd9d047bc05f9a1a106280faf89c553cb84d905383e12a22db3aae2a2308fe38.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/images/bd9d047bc05f9a1a106280faf89c553cb84d905383e12a22db3aae2a2308fe38.jpg)

![cf442b650dc776b5abae3250821de64e9734f096b7a1aef482659c2333ac1eb4.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/images/cf442b650dc776b5abae3250821de64e9734f096b7a1aef482659c2333ac1eb4.jpg)

![f22fbde338c1d1e42405dc8a40ee1da37e61a15390a0bfbd869d03c77bf236d9.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/images/f22fbde338c1d1e42405dc8a40ee1da37e61a15390a0bfbd869d03c77bf236d9.jpg)

### Tables

![3db9200eabd5d702b8873b802b0c13180ddc7d1452337c6e94974395028daf87.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/tables/3db9200eabd5d702b8873b802b0c13180ddc7d1452337c6e94974395028daf87.jpg)

![81875c42d3c0a81fc7d26227ebebeca6ca1fcdd415ba75ba752e121ae89be0fe.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/tables/81875c42d3c0a81fc7d26227ebebeca6ca1fcdd415ba75ba752e121ae89be0fe.jpg)

![8af45c617c51ccdd7a21cc05c46a6a6fef6de043d492070b738ec7462e7d9436.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/tables/8af45c617c51ccdd7a21cc05c46a6a6fef6de043d492070b738ec7462e7d9436.jpg)

![c5387b1c43a0180a5948e8c08447b125a2e62ab02703a682f22f74abe6ac7af3.jpg](../nips_results/1770_Behavior%20Injection_%20Preparing%20Language%20Models%20for%20Reinforcement%20Learning/tables/c5387b1c43a0180a5948e8c08447b125a2e62ab02703a682f22f74abe6ac7af3.jpg)

## Functional data analysis for multivariate distributions through Wasserstein slicing


### Images

![1e86bc142d1dafbf36fd00cde2273c870c6bde6a007fe858a4a6aca6c6e6f5c0.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/1e86bc142d1dafbf36fd00cde2273c870c6bde6a007fe858a4a6aca6c6e6f5c0.jpg)

![3715d9f8b3dd2d1e57cdcdda61028c0c9c91d204434afa94d1727b40d074494e.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/3715d9f8b3dd2d1e57cdcdda61028c0c9c91d204434afa94d1727b40d074494e.jpg)

![43d77dc2a1fe14ccde27912d53510f999ebba8ebe15c4dd9be784a14aea9a8cb.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/43d77dc2a1fe14ccde27912d53510f999ebba8ebe15c4dd9be784a14aea9a8cb.jpg)

![53bfeadca2e591fd2544736c8c811d4475e2e0e3b4fb20eb1cc73b5d78e9e2ac.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/53bfeadca2e591fd2544736c8c811d4475e2e0e3b4fb20eb1cc73b5d78e9e2ac.jpg)

![787d6d14e646c11c73c373965f57067fb2bfd5c1e76c8d7d293026073c8205e5.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/787d6d14e646c11c73c373965f57067fb2bfd5c1e76c8d7d293026073c8205e5.jpg)

![91b41ed5709d8b9cd8e40db5dca1b61ef6bcd104e25dc83117ebbed7bf3f9d70.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/91b41ed5709d8b9cd8e40db5dca1b61ef6bcd104e25dc83117ebbed7bf3f9d70.jpg)

![b0e60a744634ae9e8f4b82f04cb5fbe02d82c2b3707ce67e7379326d356bd95c.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/b0e60a744634ae9e8f4b82f04cb5fbe02d82c2b3707ce67e7379326d356bd95c.jpg)

![c895b912bd5b231150c409d614ef86b8284c8383e71342c1b4aa256e831fb67f.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/c895b912bd5b231150c409d614ef86b8284c8383e71342c1b4aa256e831fb67f.jpg)

![d37d5ef3b6a35cea59a9e4ea05bf243db6e599a30a134b796f5a1412274d2324.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/d37d5ef3b6a35cea59a9e4ea05bf243db6e599a30a134b796f5a1412274d2324.jpg)

![d9a2b3a934332ee19e81d2cfe3600b2b111dcac3334d15041781a7dc25b10215.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/d9a2b3a934332ee19e81d2cfe3600b2b111dcac3334d15041781a7dc25b10215.jpg)

![e049bb6660c79ddb9dc82a65d04bed8c60d33647c5fb28891d248590d4f1c582.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/e049bb6660c79ddb9dc82a65d04bed8c60d33647c5fb28891d248590d4f1c582.jpg)

![e21fa2cf9346f72556c5f5b6222940ba942690adcdd948062e26480fde3960ba.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/e21fa2cf9346f72556c5f5b6222940ba942690adcdd948062e26480fde3960ba.jpg)

![e64ca603eaf7359ed774f79d916c7764dbc94d6506aa5b31e91177c5e1f74caa.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/e64ca603eaf7359ed774f79d916c7764dbc94d6506aa5b31e91177c5e1f74caa.jpg)

![f6fd3c3702e07d892ad0eebbe7d465c50f6a73f64d2bc5f4ddd0cb68130deb4f.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/images/f6fd3c3702e07d892ad0eebbe7d465c50f6a73f64d2bc5f4ddd0cb68130deb4f.jpg)

### Tables

![bf6688c6cc6040c1e3fdab1c2f75eb01693d299b062e6dfd666d4475cad570c6.jpg](../nips_results/1771_Functional%20data%20analysis%20for%20multivariate%20distributions%20through%20Wasserstein%20slicing/tables/bf6688c6cc6040c1e3fdab1c2f75eb01693d299b062e6dfd666d4475cad570c6.jpg)

## Balancing Performance and Costs in Best Arm Identification


### Images

![179cb537bf4a3bb61b57a436781820a5e5eb5b98bca656e4a2b95fb363c09450.jpg](../nips_results/1772_Balancing%20Performance%20and%20Costs%20in%20Best%20Arm%20Identification/images/179cb537bf4a3bb61b57a436781820a5e5eb5b98bca656e4a2b95fb363c09450.jpg)

![513dc9b14a6609200d797d070bbc8b892b16dabfabc9044f93c1ea22eeff8f77.jpg](../nips_results/1772_Balancing%20Performance%20and%20Costs%20in%20Best%20Arm%20Identification/images/513dc9b14a6609200d797d070bbc8b892b16dabfabc9044f93c1ea22eeff8f77.jpg)

![643c9ec9ecb7b4abb4e961948958b0f1bfab23419d6b1677ea814e7fae68bb7a.jpg](../nips_results/1772_Balancing%20Performance%20and%20Costs%20in%20Best%20Arm%20Identification/images/643c9ec9ecb7b4abb4e961948958b0f1bfab23419d6b1677ea814e7fae68bb7a.jpg)

![a3733c2f5a6bcf56c84ddc4cff18b51825b0a267715b23de96bdfa9dc533bbb5.jpg](../nips_results/1772_Balancing%20Performance%20and%20Costs%20in%20Best%20Arm%20Identification/images/a3733c2f5a6bcf56c84ddc4cff18b51825b0a267715b23de96bdfa9dc533bbb5.jpg)

![bb4726b39d6954b7f0fcddca07b64c77be70aea49714b69c9ab31f5598ab2169.jpg](../nips_results/1772_Balancing%20Performance%20and%20Costs%20in%20Best%20Arm%20Identification/images/bb4726b39d6954b7f0fcddca07b64c77be70aea49714b69c9ab31f5598ab2169.jpg)

## Vertical Federated Feature Screening


### Images

![b9e8365f0c9c051b6acebca4c388efc63252c76a1217d12f705466419faa747d.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/images/b9e8365f0c9c051b6acebca4c388efc63252c76a1217d12f705466419faa747d.jpg)

![cd1a40156bd0e655c19eb07fba33986f1b63a6d5f93b236b8c6c9c03ac148312.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/images/cd1a40156bd0e655c19eb07fba33986f1b63a6d5f93b236b8c6c9c03ac148312.jpg)

![e4fb8f7957d7ca9729d34e0445b6d42c0c5306cee9a809ec83b2a4b5a8b5ebda.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/images/e4fb8f7957d7ca9729d34e0445b6d42c0c5306cee9a809ec83b2a4b5a8b5ebda.jpg)

![ebd2feb734d3a887822122e3b7b4539bf14452857cc9ecd4fa19d92b0fddbe0d.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/images/ebd2feb734d3a887822122e3b7b4539bf14452857cc9ecd4fa19d92b0fddbe0d.jpg)

![f8452a97c2c2e116941113a74f9115b4d31783fb750e77d97f13977205d84d93.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/images/f8452a97c2c2e116941113a74f9115b4d31783fb750e77d97f13977205d84d93.jpg)

### Tables

![08d99985bb0a04f472c39ed6c4c37e90534c9248558795b39e1dab26056e6352.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/tables/08d99985bb0a04f472c39ed6c4c37e90534c9248558795b39e1dab26056e6352.jpg)

![3588cf902dfe999420c05aa801e7b7745800b9d88e68112c57fa4a48ebec508a.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/tables/3588cf902dfe999420c05aa801e7b7745800b9d88e68112c57fa4a48ebec508a.jpg)

![386c863edcf41e203633746099d1a60622d359eaabf5e9adc9e7f3eaa6a0d37d.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/tables/386c863edcf41e203633746099d1a60622d359eaabf5e9adc9e7f3eaa6a0d37d.jpg)

![38a597dbcdcdd365f662b68cb132705d8299b02560fcf655ba6c0fc7d7399b82.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/tables/38a597dbcdcdd365f662b68cb132705d8299b02560fcf655ba6c0fc7d7399b82.jpg)

![6e5f222163489406ef0ee6e9297f386038089bcb18f52649ad23138d31243e71.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/tables/6e5f222163489406ef0ee6e9297f386038089bcb18f52649ad23138d31243e71.jpg)

![74e54344dea366472af3d90e3bf330a70c24bd168743b80fe8eb7fd28e39457d.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/tables/74e54344dea366472af3d90e3bf330a70c24bd168743b80fe8eb7fd28e39457d.jpg)

![7654c460970137d2fe359b5db82fadd5ffccab3b96a233e702d533cdab1b3dac.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/tables/7654c460970137d2fe359b5db82fadd5ffccab3b96a233e702d533cdab1b3dac.jpg)

![8be992ffd1d2a182180fc22e7dcca5bd9230c8c57d98b5cc5da9b369fddbdde2.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/tables/8be992ffd1d2a182180fc22e7dcca5bd9230c8c57d98b5cc5da9b369fddbdde2.jpg)

![f39b46b9164e58183fce28007702ebad5495ffc2aeeca158d93e8951ab71fbea.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/tables/f39b46b9164e58183fce28007702ebad5495ffc2aeeca158d93e8951ab71fbea.jpg)

![f5160865cc17330c9f06cb4956a914f8bbd7cb4f941f43ffb030f105320b42a7.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/tables/f5160865cc17330c9f06cb4956a914f8bbd7cb4f941f43ffb030f105320b42a7.jpg)

![f746a91282f989ef75cc9bb23c676daa98a2de34aab6e77970d7f348bb56c20b.jpg](../nips_results/1773_Vertical%20Federated%20Feature%20Screening/tables/f746a91282f989ef75cc9bb23c676daa98a2de34aab6e77970d7f348bb56c20b.jpg)

## Fair Minimum Labeling: Efficient Temporal Network Activations for Reachability and Equity


### Images

![a222a594607b69286ebe003a2ddfac490afafb537711efc05ec4134842846947.jpg](../nips_results/1774_Fair%20Minimum%20Labeling_%20Efficient%20Temporal%20Network%20Activations%20for%20Reachability%20and%20Equity/images/a222a594607b69286ebe003a2ddfac490afafb537711efc05ec4134842846947.jpg)

![b8c9e78ccc21f0bdf7fcc904270b7cf04e3fb812166d4dcde9bacfa2d402f23d.jpg](../nips_results/1774_Fair%20Minimum%20Labeling_%20Efficient%20Temporal%20Network%20Activations%20for%20Reachability%20and%20Equity/images/b8c9e78ccc21f0bdf7fcc904270b7cf04e3fb812166d4dcde9bacfa2d402f23d.jpg)

### Tables

![3bf6b30c8bc49ca96c0a7556a6d33b00e825b8afdfd9a8ad221e8c331b2d1c60.jpg](../nips_results/1774_Fair%20Minimum%20Labeling_%20Efficient%20Temporal%20Network%20Activations%20for%20Reachability%20and%20Equity/tables/3bf6b30c8bc49ca96c0a7556a6d33b00e825b8afdfd9a8ad221e8c331b2d1c60.jpg)

![5654ed75e06c3d66963761603d7c2d3ea64d3051eaf3be359b4730f789f5c795.jpg](../nips_results/1774_Fair%20Minimum%20Labeling_%20Efficient%20Temporal%20Network%20Activations%20for%20Reachability%20and%20Equity/tables/5654ed75e06c3d66963761603d7c2d3ea64d3051eaf3be359b4730f789f5c795.jpg)

![aedb8826f38cbbef6c5a180516594cf634a97ec757cda98bdbc29fc63f552a02.jpg](../nips_results/1774_Fair%20Minimum%20Labeling_%20Efficient%20Temporal%20Network%20Activations%20for%20Reachability%20and%20Equity/tables/aedb8826f38cbbef6c5a180516594cf634a97ec757cda98bdbc29fc63f552a02.jpg)

![d4383be66472a7631a3b27b74c573403a153defb4348f23b8b3ca79662da61fc.jpg](../nips_results/1774_Fair%20Minimum%20Labeling_%20Efficient%20Temporal%20Network%20Activations%20for%20Reachability%20and%20Equity/tables/d4383be66472a7631a3b27b74c573403a153defb4348f23b8b3ca79662da61fc.jpg)

## Parameter Efficient Fine-tuning via Explained Variance Adaptation


### Images

![04cafef186174170453715d521cf1140fd54251fb44aa2db6f5a167126c26cff.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/04cafef186174170453715d521cf1140fd54251fb44aa2db6f5a167126c26cff.jpg)

![14b0d0c6a85f96ac519b8db7748c5e44cadef790efd6bfc74381937d8a5496ca.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/14b0d0c6a85f96ac519b8db7748c5e44cadef790efd6bfc74381937d8a5496ca.jpg)

![1afe25742e4da32a8e570e1696305ca30ce264608534d2cf971f3af25f1e4b66.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/1afe25742e4da32a8e570e1696305ca30ce264608534d2cf971f3af25f1e4b66.jpg)

![1d67f03a2a3f45cee02586f87c1f4a2c9d430381a8bf8e0f47205bda64939b4a.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/1d67f03a2a3f45cee02586f87c1f4a2c9d430381a8bf8e0f47205bda64939b4a.jpg)

![3522e4824fe2d2a9e56fca13a00ce44654aa1c90226912ca24ca659af2da2c40.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/3522e4824fe2d2a9e56fca13a00ce44654aa1c90226912ca24ca659af2da2c40.jpg)

![421b49fe9a76cc1c3d953d03b0838ca651d26c996ffc2bd031a1d43960d9dd4a.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/421b49fe9a76cc1c3d953d03b0838ca651d26c996ffc2bd031a1d43960d9dd4a.jpg)

![45ba1b8ac18a4c4650cebc2d7b95f374bab8d65822201ec3ac9fb16a6367985b.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/45ba1b8ac18a4c4650cebc2d7b95f374bab8d65822201ec3ac9fb16a6367985b.jpg)

![729503a7ff16deb192a5c40c0a1fb07a983a3c55932ca3497c4dd6c01965298f.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/729503a7ff16deb192a5c40c0a1fb07a983a3c55932ca3497c4dd6c01965298f.jpg)

![7d889f16134adb3a1cc822f8418879bb07c00b4133bb81220ef12d621ba972de.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/7d889f16134adb3a1cc822f8418879bb07c00b4133bb81220ef12d621ba972de.jpg)

![925df8a19cece69dc5a16ac755b59436e07c70b9baa18da6f7154cd7b4a1601f.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/925df8a19cece69dc5a16ac755b59436e07c70b9baa18da6f7154cd7b4a1601f.jpg)

![ae3405726406bb160c6fd007c101c683a37b19cc493fd946e8f96a6198debfb2.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/ae3405726406bb160c6fd007c101c683a37b19cc493fd946e8f96a6198debfb2.jpg)

![b56a4aecef33900325309b1dd71de0d306dcc27b291441b7521f301d986c4f0b.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/b56a4aecef33900325309b1dd71de0d306dcc27b291441b7521f301d986c4f0b.jpg)

![dfbfbd5bf0dcc1be5ff2cfcc5a90fdc910e17e80c8d63583bc84c057a3968b21.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/dfbfbd5bf0dcc1be5ff2cfcc5a90fdc910e17e80c8d63583bc84c057a3968b21.jpg)

![ec78dffc6fffdb35a964181f9692981c16fe1b74a13b43479dc5ef14dbceed26.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/ec78dffc6fffdb35a964181f9692981c16fe1b74a13b43479dc5ef14dbceed26.jpg)

![ed1602ed0c33be9caa165cfc90ac53aa3a4c35ccd5a6b7a3e100cf238eafbb82.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/images/ed1602ed0c33be9caa165cfc90ac53aa3a4c35ccd5a6b7a3e100cf238eafbb82.jpg)

### Tables

![0332dec5cadd397752779e781a388263dc0cdd728636d2cfd6f0a020e7ba003f.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/0332dec5cadd397752779e781a388263dc0cdd728636d2cfd6f0a020e7ba003f.jpg)

![07cf781af699743158a56e9a867be1f1a89667937abdeea36553dbfb5960d620.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/07cf781af699743158a56e9a867be1f1a89667937abdeea36553dbfb5960d620.jpg)

![165758cc85813af11ab7d102fe3fccb6bf992c9212357f920a744e4b0a610281.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/165758cc85813af11ab7d102fe3fccb6bf992c9212357f920a744e4b0a610281.jpg)

![1c9d4eb2a4f4ccda11dd355435d2abfbcd193c29262cceec26dcd3c3cdd20cc5.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/1c9d4eb2a4f4ccda11dd355435d2abfbcd193c29262cceec26dcd3c3cdd20cc5.jpg)

![1d8aad6380fd058b9eaf1b845b00db045b85fc1002eadfb6dc486e573151a731.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/1d8aad6380fd058b9eaf1b845b00db045b85fc1002eadfb6dc486e573151a731.jpg)

![1e5feaf43870506a5ed52096648bd1677982ede11cd1036fc388dae5fb173faf.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/1e5feaf43870506a5ed52096648bd1677982ede11cd1036fc388dae5fb173faf.jpg)

![2738df1e9ce1a06edb9f5c3f2b9f72986bbb8ab7cef123bb9f1235f0c37b00d1.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/2738df1e9ce1a06edb9f5c3f2b9f72986bbb8ab7cef123bb9f1235f0c37b00d1.jpg)

![37e3f9a76a963e7f1f2ea8d01a0187c512037922d6dd40495137dd53c9bf9116.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/37e3f9a76a963e7f1f2ea8d01a0187c512037922d6dd40495137dd53c9bf9116.jpg)

![3c10eefbc760707478a6806c798f9e80510b910808729edaf87de4d2e3609bc7.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/3c10eefbc760707478a6806c798f9e80510b910808729edaf87de4d2e3609bc7.jpg)

![763efc640e6853f83ec54b27876924c1aa6ffc6e5310ace074ac96b7fa4b0b84.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/763efc640e6853f83ec54b27876924c1aa6ffc6e5310ace074ac96b7fa4b0b84.jpg)

![7c142abecc027972058f5063d3d0a842288fdd73df540b3f035b83849d6a2694.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/7c142abecc027972058f5063d3d0a842288fdd73df540b3f035b83849d6a2694.jpg)

![7d9b87741f8ca27bc91d095c19c1e26f20610ec6ca7db3657c5e87a456e84c2e.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/7d9b87741f8ca27bc91d095c19c1e26f20610ec6ca7db3657c5e87a456e84c2e.jpg)

![933eed98d1ef833ff4a1177902788152776c5d78a874f2fb0a3649241a3cceee.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/933eed98d1ef833ff4a1177902788152776c5d78a874f2fb0a3649241a3cceee.jpg)

![9667acc6722dbedea17f3c3124dd3c021b67f599619c02b4e4667bacd4d64fda.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/9667acc6722dbedea17f3c3124dd3c021b67f599619c02b4e4667bacd4d64fda.jpg)

![9f416ec080e1e470572471431d1bf8e1449adb04c105538bee218f55610bfeb4.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/9f416ec080e1e470572471431d1bf8e1449adb04c105538bee218f55610bfeb4.jpg)

![a7b6ae61be7b11c764eb2dd7b83aa8b9e63d3526936267cc270aa55ef4cc288c.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/a7b6ae61be7b11c764eb2dd7b83aa8b9e63d3526936267cc270aa55ef4cc288c.jpg)

![b76a3822238120ee6f6f496b0bc61cdbea7f6b6f1844fbfae70895f4cf020a65.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/b76a3822238120ee6f6f496b0bc61cdbea7f6b6f1844fbfae70895f4cf020a65.jpg)

![bba005fb5e5d839c9bbae346f8cc5bd75cc59a7508fef442d6bd4e34026f6cf3.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/bba005fb5e5d839c9bbae346f8cc5bd75cc59a7508fef442d6bd4e34026f6cf3.jpg)

![bff455c04addd51a93ded1f96dc6d07f468ddd1ec878d841c11152f3a76c3926.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/bff455c04addd51a93ded1f96dc6d07f468ddd1ec878d841c11152f3a76c3926.jpg)

![c39a8a849620a7cca47dc2b4b614c0b436f5b4c9b4f36a282176894af74fbc9d.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/c39a8a849620a7cca47dc2b4b614c0b436f5b4c9b4f36a282176894af74fbc9d.jpg)

![df468a89faae586f5d8b9fc5361b959810550bc7b82bdf311ea7dcc79de74b40.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/df468a89faae586f5d8b9fc5361b959810550bc7b82bdf311ea7dcc79de74b40.jpg)

![e293d5d22977f9e7c6a272df1320e8097574afd3d4310a235a097c20bc9d5234.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/e293d5d22977f9e7c6a272df1320e8097574afd3d4310a235a097c20bc9d5234.jpg)

![eae5a1e2b0074529fcc841711779ec3bfe2c6ea069fa0eb9cad79bb5e789d57f.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/eae5a1e2b0074529fcc841711779ec3bfe2c6ea069fa0eb9cad79bb5e789d57f.jpg)

![eeb49e8d1a723519d72a85755c5ad21714822cec2d3a895648f79d2018ee76e9.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/eeb49e8d1a723519d72a85755c5ad21714822cec2d3a895648f79d2018ee76e9.jpg)

![f6f6f30b5478d86104a1b83dc6203b974fff7d458ac0aa0ef62c358516c3788f.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/f6f6f30b5478d86104a1b83dc6203b974fff7d458ac0aa0ef62c358516c3788f.jpg)

![f788ef788f2bc3b0036b86f502398f27ca191309ddb954a6b01dc57e2f0c2e2c.jpg](../nips_results/1775_Parameter%20Efficient%20Fine-tuning%20via%20Explained%20Variance%20Adaptation/tables/f788ef788f2bc3b0036b86f502398f27ca191309ddb954a6b01dc57e2f0c2e2c.jpg)

## CTSketch: Compositional Tensor Sketching for Scalable Neurosymbolic Learning


### Images

![1846ffe85e80f7d4be47593b51f436f83e951770afe829fc04a48eb4e41a82ea.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/images/1846ffe85e80f7d4be47593b51f436f83e951770afe829fc04a48eb4e41a82ea.jpg)

![4728e3076dba5b09d0f9f803295782346fda90d63689a855cd706a3941373e91.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/images/4728e3076dba5b09d0f9f803295782346fda90d63689a855cd706a3941373e91.jpg)

![b2538761dafd9a95ea6aa2e00d51cab0d1b3aa28a342313b6ca15925f32bbfa4.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/images/b2538761dafd9a95ea6aa2e00d51cab0d1b3aa28a342313b6ca15925f32bbfa4.jpg)

![b3cc2fa1117604e6fe070e35c4baeddb48a6c16fb8c96a930691bdc3b6cd68c8.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/images/b3cc2fa1117604e6fe070e35c4baeddb48a6c16fb8c96a930691bdc3b6cd68c8.jpg)

![c2fae7a22181e2742f74afdd412af3e9750a95a38750a9fb90af275acaf7f541.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/images/c2fae7a22181e2742f74afdd412af3e9750a95a38750a9fb90af275acaf7f541.jpg)

![d2690e81144e036ba7f7e44086c1b67e7ea1bf678281fd5967e9be13898e1ac0.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/images/d2690e81144e036ba7f7e44086c1b67e7ea1bf678281fd5967e9be13898e1ac0.jpg)

### Tables

![14226fc8121a403eb7cadc4254dc3ea3357e59c25293c00b2f89e0781130e684.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/tables/14226fc8121a403eb7cadc4254dc3ea3357e59c25293c00b2f89e0781130e684.jpg)

![2d789d1818522847681b0f9a38100b821969cb571a26fcbd6e1f3ed867fdc28c.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/tables/2d789d1818522847681b0f9a38100b821969cb571a26fcbd6e1f3ed867fdc28c.jpg)

![3bdc606cde61dde01ece214c68671f673b3c2127a80b82f8ff25c10d9709a2d9.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/tables/3bdc606cde61dde01ece214c68671f673b3c2127a80b82f8ff25c10d9709a2d9.jpg)

![4a9efc1de8bde7459e5a9074907ca295ce11ccc2fb64c45207f3f404badee415.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/tables/4a9efc1de8bde7459e5a9074907ca295ce11ccc2fb64c45207f3f404badee415.jpg)

![62afe47d53234e21a298d0957f04054f906e3278d2f00ca6978019e6849ad52c.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/tables/62afe47d53234e21a298d0957f04054f906e3278d2f00ca6978019e6849ad52c.jpg)

![b9f17371ed66fd0907aa622f70c653bf405a212324ccece32959713e5a826696.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/tables/b9f17371ed66fd0907aa622f70c653bf405a212324ccece32959713e5a826696.jpg)

![fb3d48655222c6a633fb81053d0556aa0acb7eeab993d2a9b3b99c300329ae38.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/tables/fb3d48655222c6a633fb81053d0556aa0acb7eeab993d2a9b3b99c300329ae38.jpg)

![ffc8ee8d7c8add2bad0944e4647b544b8c8dc2a346b2b7f7df77b881cec76b8a.jpg](../nips_results/1776_CTSketch_%20Compositional%20Tensor%20Sketching%20for%20Scalable%20Neurosymbolic%20Learning/tables/ffc8ee8d7c8add2bad0944e4647b544b8c8dc2a346b2b7f7df77b881cec76b8a.jpg)

## Preference-Guided Diffusion for Multi-Objective Offline Optimization


### Images

![04b41cbbe96fa5d0ff3d030a0b7540ca5f29fe189fcd89cf69387d51fbf47670.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/images/04b41cbbe96fa5d0ff3d030a0b7540ca5f29fe189fcd89cf69387d51fbf47670.jpg)

![ad22fff25b264485d860a1db0391b6ca4ea2e2a9b384da982c548e8ad84095ad.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/images/ad22fff25b264485d860a1db0391b6ca4ea2e2a9b384da982c548e8ad84095ad.jpg)

![d6e7af5974a2f376d6b0ec0edea262dd135742c08f595ea93aba17f184b1de0f.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/images/d6e7af5974a2f376d6b0ec0edea262dd135742c08f595ea93aba17f184b1de0f.jpg)

![e60e4790d67c4f0a3bc0ee90720a6361d56cd202203c7bd110caa76437ee4cdc.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/images/e60e4790d67c4f0a3bc0ee90720a6361d56cd202203c7bd110caa76437ee4cdc.jpg)

![fa823b5124c4be71b0ce69944efb8828c306f0d44a337c6a6082c38fc3ca5dfe.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/images/fa823b5124c4be71b0ce69944efb8828c306f0d44a337c6a6082c38fc3ca5dfe.jpg)

### Tables

![05348aeeb853706fc87cbdea5a701628763a782c7dc64dedc89da3cd3dba7263.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/05348aeeb853706fc87cbdea5a701628763a782c7dc64dedc89da3cd3dba7263.jpg)

![0bf04e6fb067bca2e3e70dc6513a69137ad6c6f051c1b4a8fb9cf665daada28c.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/0bf04e6fb067bca2e3e70dc6513a69137ad6c6f051c1b4a8fb9cf665daada28c.jpg)

![0ce8c95000550afaa8490444a338e4d08e6daa1747422469eaa0486947c73c1b.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/0ce8c95000550afaa8490444a338e4d08e6daa1747422469eaa0486947c73c1b.jpg)

![1415aef757fbd7e6304c1db43b427da1e4cc9457c04cc5be056abcabc5c129b6.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/1415aef757fbd7e6304c1db43b427da1e4cc9457c04cc5be056abcabc5c129b6.jpg)

![1b84c281a5c1677f38a83f188acdfa0aed0e139c8df27b33fa5414289dd24a5a.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/1b84c281a5c1677f38a83f188acdfa0aed0e139c8df27b33fa5414289dd24a5a.jpg)

![225f21307f806a78293e3ae2cb9185665483a5467f7868e8873194d47d03c7cf.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/225f21307f806a78293e3ae2cb9185665483a5467f7868e8873194d47d03c7cf.jpg)

![249ca8c992484161b206fc3a02b6906adc40ce9cef3b2af59fa542cbc7382eab.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/249ca8c992484161b206fc3a02b6906adc40ce9cef3b2af59fa542cbc7382eab.jpg)

![2de898624040a72b83139a52f0a3548a81cbfb498e2f386dd0a2e52016425b6b.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/2de898624040a72b83139a52f0a3548a81cbfb498e2f386dd0a2e52016425b6b.jpg)

![34e9c89bf39f3d4f96bbe5dcea47e7b95d1befdc7fa34ee8900b4b7151799149.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/34e9c89bf39f3d4f96bbe5dcea47e7b95d1befdc7fa34ee8900b4b7151799149.jpg)

![5259275753c23cbcb11cd1f931dc6006036ae7b18784bb49483b6f5edecd7bfb.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/5259275753c23cbcb11cd1f931dc6006036ae7b18784bb49483b6f5edecd7bfb.jpg)

![54f33ad1c760053dffb3887c29700fec4b1d6285752ff7160bd308b674af6a72.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/54f33ad1c760053dffb3887c29700fec4b1d6285752ff7160bd308b674af6a72.jpg)

![81f73c1b39a83a4983b0a44d015fb28923a0a0d4305ef59b9fcca0eba28cf5dc.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/81f73c1b39a83a4983b0a44d015fb28923a0a0d4305ef59b9fcca0eba28cf5dc.jpg)

![877fb1ad831d8a49fd730806e71e7141f3c870ccf404118844f86519a6e71ebf.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/877fb1ad831d8a49fd730806e71e7141f3c870ccf404118844f86519a6e71ebf.jpg)

![8e1d793f8e6c607f4b414bb0b66b7d87c61ed29902edd410b5546a9e39a83d33.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/8e1d793f8e6c607f4b414bb0b66b7d87c61ed29902edd410b5546a9e39a83d33.jpg)

![8e9c5200a821284fb5dc6f04a2a08d7e7711199d2c5a58eb34d482594efdf420.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/8e9c5200a821284fb5dc6f04a2a08d7e7711199d2c5a58eb34d482594efdf420.jpg)

![991ad821163b3244ad85bd9fb2f4be5137f3add2d7fccb5458646c9873eacdc1.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/991ad821163b3244ad85bd9fb2f4be5137f3add2d7fccb5458646c9873eacdc1.jpg)

![9ca754026f8725955d146ffcd8180b454fa9a8f5df20136900085f26fd7bd7a3.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/9ca754026f8725955d146ffcd8180b454fa9a8f5df20136900085f26fd7bd7a3.jpg)

![a56f6b354be7e76478b4636396a9de2d5438fd12aaf3883a56d2ec047301f543.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/a56f6b354be7e76478b4636396a9de2d5438fd12aaf3883a56d2ec047301f543.jpg)

![ac626f663f51e1132fd1f223eea57edc954702aba374dcf03b749680a18d7f95.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/ac626f663f51e1132fd1f223eea57edc954702aba374dcf03b749680a18d7f95.jpg)

![af73c0c31183521cd7b9a2b1a5140b20e8ec8d0df8e2a88fff91b720325452c5.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/af73c0c31183521cd7b9a2b1a5140b20e8ec8d0df8e2a88fff91b720325452c5.jpg)

![b61351cb2b1e1c89b86a99a6e179a5419096d36a1d3708b081933e35a0c65683.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/b61351cb2b1e1c89b86a99a6e179a5419096d36a1d3708b081933e35a0c65683.jpg)

![bede50d9237ad38f46fc2f61b90dd3869f1836a09adf2eab17b9ce72d0b05a97.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/bede50d9237ad38f46fc2f61b90dd3869f1836a09adf2eab17b9ce72d0b05a97.jpg)

![cd84e3c44846cb565a437484d7c5176dec1dfb47b058f4fffe8382681a39845f.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/cd84e3c44846cb565a437484d7c5176dec1dfb47b058f4fffe8382681a39845f.jpg)

![cf6a85414f90e7d97960113df1fc4474e8a28353fa3494bb2ead90dcf347aef0.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/cf6a85414f90e7d97960113df1fc4474e8a28353fa3494bb2ead90dcf347aef0.jpg)

![dd933168f19394e950ec9c1d93fd92240004b5432e7b95c291ccf98926fe18a1.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/dd933168f19394e950ec9c1d93fd92240004b5432e7b95c291ccf98926fe18a1.jpg)

![e32ec11aff25877595a3dd09e63112ac4de06f949f38f4931dcf4b7bf0c996e2.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/e32ec11aff25877595a3dd09e63112ac4de06f949f38f4931dcf4b7bf0c996e2.jpg)

![e4926965a27d4b7ffc82c20b33f900e1eb02d842f3af01f92394a00d150d72dc.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/e4926965a27d4b7ffc82c20b33f900e1eb02d842f3af01f92394a00d150d72dc.jpg)

![ec1941604b039e7f80defd91260969b94914dd5da7ad1511d98046763bfec5c1.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/ec1941604b039e7f80defd91260969b94914dd5da7ad1511d98046763bfec5c1.jpg)

![fe95e7fe569131f5d35390c587ddc24c78859dfa1404c69b0b32aa485b9df6ac.jpg](../nips_results/1777_Preference-Guided%20Diffusion%20for%20Multi-Objective%20Offline%20Optimization/tables/fe95e7fe569131f5d35390c587ddc24c78859dfa1404c69b0b32aa485b9df6ac.jpg)

## From Judgment to Interference: Early Stopping LLM Harmful Outputs via Streaming Content Monitoring


### Images

![0933fb221fc809227e7d6efa7bd85ca56560cca0ba88869f6452a0d1f357f91e.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/images/0933fb221fc809227e7d6efa7bd85ca56560cca0ba88869f6452a0d1f357f91e.jpg)

![253046470535d977fc574782d89a155641e79a44705c2ac0488c669243d4bd0e.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/images/253046470535d977fc574782d89a155641e79a44705c2ac0488c669243d4bd0e.jpg)

![4b64fd1cab9d58b54a4d48b71d120fcfa34c8e842581fac945f2a1a8ac6523e1.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/images/4b64fd1cab9d58b54a4d48b71d120fcfa34c8e842581fac945f2a1a8ac6523e1.jpg)

![56288cef923b5c552494928dfb030bf2ca4f7269b004793a61d2ce3d78c6c7be.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/images/56288cef923b5c552494928dfb030bf2ca4f7269b004793a61d2ce3d78c6c7be.jpg)

![6ae4b96621ece35408be017bc4d78100332d4870f5097dac59eaf48db7e93490.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/images/6ae4b96621ece35408be017bc4d78100332d4870f5097dac59eaf48db7e93490.jpg)

![6fd3637c9d8c9df8577e57e07cd5dec7c0a40db7d7595e127a498bb7cb870411.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/images/6fd3637c9d8c9df8577e57e07cd5dec7c0a40db7d7595e127a498bb7cb870411.jpg)

![dff0c93c528887cddd37a7624b045a2b4eec54815dc67a21291aa216470baf7e.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/images/dff0c93c528887cddd37a7624b045a2b4eec54815dc67a21291aa216470baf7e.jpg)

![f07f550efeee5d8dc0d5e8323ac6d857cd8462969a52df7d7ae8d5e4280543cc.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/images/f07f550efeee5d8dc0d5e8323ac6d857cd8462969a52df7d7ae8d5e4280543cc.jpg)

### Tables

![04ac9f36d90ce6a166556697fb217a6287d30645304a576d189074116965f25d.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/tables/04ac9f36d90ce6a166556697fb217a6287d30645304a576d189074116965f25d.jpg)

![0f6a43f012a710041e5af5dd775b94088a224386871c6c7406246e9e27a3ce1f.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/tables/0f6a43f012a710041e5af5dd775b94088a224386871c6c7406246e9e27a3ce1f.jpg)

![2045d454018dc4937e83c32794efc6e2cdda948f883ff3f76179b5315b3677df.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/tables/2045d454018dc4937e83c32794efc6e2cdda948f883ff3f76179b5315b3677df.jpg)

![402ee2177f949b7aa928bb82f9306b0797e9b9cb132813a9ddcfb778f266dc9b.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/tables/402ee2177f949b7aa928bb82f9306b0797e9b9cb132813a9ddcfb778f266dc9b.jpg)

![732cdb0d0b4140854479fe0cae243206728db8f74622688e5c71d1edf29b15e9.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/tables/732cdb0d0b4140854479fe0cae243206728db8f74622688e5c71d1edf29b15e9.jpg)

![85c83930f49bcac218affec1980125eb1cc50c739346a5b39e3a6347cd9aaeb4.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/tables/85c83930f49bcac218affec1980125eb1cc50c739346a5b39e3a6347cd9aaeb4.jpg)

![8eba08a4879fc328897ef08104d30678944c5a2e18fd1863ccc7b9369e542c63.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/tables/8eba08a4879fc328897ef08104d30678944c5a2e18fd1863ccc7b9369e542c63.jpg)

![9b1d3e71e9f72d6bd6f6356ee3e41321b4897c883e05cfc2b4b21fb5e7b8f249.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/tables/9b1d3e71e9f72d6bd6f6356ee3e41321b4897c883e05cfc2b4b21fb5e7b8f249.jpg)

![ed73019ca28f9abba8311ceddfb6f73a03ded2fbb3068dfb8c42925800158512.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/tables/ed73019ca28f9abba8311ceddfb6f73a03ded2fbb3068dfb8c42925800158512.jpg)

![f302a1551bb727b76492ce251c54dccffe891cd888cf7b672e1fc695115c956e.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/tables/f302a1551bb727b76492ce251c54dccffe891cd888cf7b672e1fc695115c956e.jpg)

![f690424cbd731cd41794c2764d9c3000d02a859e0cf065f583b83bf149c29b9a.jpg](../nips_results/1778_From%20Judgment%20to%20Interference_%20Early%20Stopping%20LLM%20Harmful%20Outputs%20via%20Streaming%20Content%20Monitoring/tables/f690424cbd731cd41794c2764d9c3000d02a859e0cf065f583b83bf149c29b9a.jpg)

## A Unified Analysis of Stochastic Gradient Descent with Arbitrary Data Permutations and Beyond


### Images

![0ccf79f15e24876bba395d277f08565ed8295846b3b4c24a3f68aad018b17823.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/images/0ccf79f15e24876bba395d277f08565ed8295846b3b4c24a3f68aad018b17823.jpg)

![4dd05a303877fd35316d5b790f78f132428e58ab1f6512866c560b35bfaa0d49.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/images/4dd05a303877fd35316d5b790f78f132428e58ab1f6512866c560b35bfaa0d49.jpg)

![5cd79aeb694a50b26bc3671f1c4481c696a95a7667556ef7cc22ddb6dee0813d.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/images/5cd79aeb694a50b26bc3671f1c4481c696a95a7667556ef7cc22ddb6dee0813d.jpg)

### Tables

![06f56ce33155ae9eed6e9ef2425e8fe812e1d15078e6d7660e3413c445af468f.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/06f56ce33155ae9eed6e9ef2425e8fe812e1d15078e6d7660e3413c445af468f.jpg)

![328590d6e747e60f24eb3cf3795efde926f0351984e5740837511b4ff80b1c56.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/328590d6e747e60f24eb3cf3795efde926f0351984e5740837511b4ff80b1c56.jpg)

![3d88099e0cff97e5aa7b313515f4d0f9d5a11f29c1f5135bf0d0b0176c6f57f2.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/3d88099e0cff97e5aa7b313515f4d0f9d5a11f29c1f5135bf0d0b0176c6f57f2.jpg)

![64f6d948e260882c88910ed32875f705b029f01f596f7b8357f1892715d0b3ac.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/64f6d948e260882c88910ed32875f705b029f01f596f7b8357f1892715d0b3ac.jpg)

![6f3614cb4f9fb3339fc58d9e2885b1de204b5a3664cdfdc2fb6e117fe04417e6.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/6f3614cb4f9fb3339fc58d9e2885b1de204b5a3664cdfdc2fb6e117fe04417e6.jpg)

![8231ae49eaf408580a62d7671db7ea49f2c090764f5b6775bb135ae7afe5bc04.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/8231ae49eaf408580a62d7671db7ea49f2c090764f5b6775bb135ae7afe5bc04.jpg)

![86e72dba1df0ad45a0f17f7c66fc90b5b8f2bac776ebf49341d93f4b91a15dd6.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/86e72dba1df0ad45a0f17f7c66fc90b5b8f2bac776ebf49341d93f4b91a15dd6.jpg)

![9e627d31fca1eb77a2d3bbf911e7a6ae6dfdee788fad796f6eb08fb5be2b8978.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/9e627d31fca1eb77a2d3bbf911e7a6ae6dfdee788fad796f6eb08fb5be2b8978.jpg)

![a1f918938b70b5ca9394e99afd653449dd617b688ab6f36a1f456b30b09e6e0a.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/a1f918938b70b5ca9394e99afd653449dd617b688ab6f36a1f456b30b09e6e0a.jpg)

![a38cf48d78ca91c9cbd2fe0c4d73eba6965cb9cde5f4fc523addaf28774ecbfd.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/a38cf48d78ca91c9cbd2fe0c4d73eba6965cb9cde5f4fc523addaf28774ecbfd.jpg)

![aff947c87c95a3390c3681f28f7820562ff473872919aa3686c2e3560300168a.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/aff947c87c95a3390c3681f28f7820562ff473872919aa3686c2e3560300168a.jpg)

![c0399a5528283baf0cd8dd0e96f4a5838cf88208d570aa91b984b29fb0931163.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/c0399a5528283baf0cd8dd0e96f4a5838cf88208d570aa91b984b29fb0931163.jpg)

![e7a6185520bb9d0ac422a575836dd40a53e887efdfc81d9d56023d5a96e3de28.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/e7a6185520bb9d0ac422a575836dd40a53e887efdfc81d9d56023d5a96e3de28.jpg)

![ec60a312871f9d39383407583ec3501a6e0dc77990ec383e2b6f2d1773d06b24.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/ec60a312871f9d39383407583ec3501a6e0dc77990ec383e2b6f2d1773d06b24.jpg)

![f0a06d5de4f3c0283c04fdbae6b3f66baaf5568cd7633c15a280f09c02512924.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/f0a06d5de4f3c0283c04fdbae6b3f66baaf5568cd7633c15a280f09c02512924.jpg)

![f33bc54e97a0719fb3573b4c0275cd72eaeb4e20f17de03b15cf34fd4b922f92.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/f33bc54e97a0719fb3573b4c0275cd72eaeb4e20f17de03b15cf34fd4b922f92.jpg)

![fe28cdcdd24e6ea50bd86f9027284787c0e460b14ab13250fbc902837508af93.jpg](../nips_results/1779_A%20Unified%20Analysis%20of%20Stochastic%20Gradient%20Descent%20with%20Arbitrary%20Data%20Permutations%20and%20Beyond/tables/fe28cdcdd24e6ea50bd86f9027284787c0e460b14ab13250fbc902837508af93.jpg)

## Integrating Drug Substructures and Longitudinal Electronic Health Records for Personalized Drug Recommendation


### Images

![1eeb1174035e4b6cd3cc2ac7a2df145bb447efc95abca9a853c3142a3463bb82.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/images/1eeb1174035e4b6cd3cc2ac7a2df145bb447efc95abca9a853c3142a3463bb82.jpg)

![3cf037b823a456976c1445778588cc5ede5b4732ed77574f26bbd592dd1ff3b0.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/images/3cf037b823a456976c1445778588cc5ede5b4732ed77574f26bbd592dd1ff3b0.jpg)

![5da6162921a94720e41ac0eb8f853a97ff32ef547c70a9cd465695466eb0ceeb.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/images/5da6162921a94720e41ac0eb8f853a97ff32ef547c70a9cd465695466eb0ceeb.jpg)

![93baa4bce87aa56fc0304f58b09568c9132e3c81ae6479aa7ddbdfaddd1bcb0d.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/images/93baa4bce87aa56fc0304f58b09568c9132e3c81ae6479aa7ddbdfaddd1bcb0d.jpg)

![c9e81a1df74a2996cdb3f5003d50e780f695b20dc45157770adf01766d6d3048.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/images/c9e81a1df74a2996cdb3f5003d50e780f695b20dc45157770adf01766d6d3048.jpg)

![edf67fd9c41a9595d9d61fcd8025447c0006c4a1195f428702bd8895798900f8.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/images/edf67fd9c41a9595d9d61fcd8025447c0006c4a1195f428702bd8895798900f8.jpg)

### Tables

![1777ed76a7e68c5d6f455a6a6341cda66ca53ed8216c7cbd6465756b24fe1120.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/tables/1777ed76a7e68c5d6f455a6a6341cda66ca53ed8216c7cbd6465756b24fe1120.jpg)

![4d02fc74b4b40196359673d89363648fff35238bc39b6a80eba7ecf2d882e621.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/tables/4d02fc74b4b40196359673d89363648fff35238bc39b6a80eba7ecf2d882e621.jpg)

![630f4f306c9d43767c84ad50a707a58fa5665dda1d6dc6cdbfb57cc55a38612e.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/tables/630f4f306c9d43767c84ad50a707a58fa5665dda1d6dc6cdbfb57cc55a38612e.jpg)

![6d1ce966f0afa0431ca0746e6de2cf92feb1be438585ca4b1d0fa3689fd96242.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/tables/6d1ce966f0afa0431ca0746e6de2cf92feb1be438585ca4b1d0fa3689fd96242.jpg)

![7d4b7fdf8bce76debc82dc0ddbc5d22c6ae626b284827e178d8ba06d9f86a328.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/tables/7d4b7fdf8bce76debc82dc0ddbc5d22c6ae626b284827e178d8ba06d9f86a328.jpg)

![83c91f2dc75b6538a313c78a21c86ce57875791a8db062b5e9e12603e4d3d44b.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/tables/83c91f2dc75b6538a313c78a21c86ce57875791a8db062b5e9e12603e4d3d44b.jpg)

![ae453273e747ddaca5d5ecf72c7ed9841a4331166cff065224856b065d8f1ced.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/tables/ae453273e747ddaca5d5ecf72c7ed9841a4331166cff065224856b065d8f1ced.jpg)

![e342e2acd3349a00bb2b1ae85c3e8d4965fae8c64e0d7c554c6aebf8c9e99e58.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/tables/e342e2acd3349a00bb2b1ae85c3e8d4965fae8c64e0d7c554c6aebf8c9e99e58.jpg)

![f118a11b5a07b703dafc68b4475c8a96b8cfe818e82bc4009511bf1e0d22b509.jpg](../nips_results/1780_Integrating%20Drug%20Substructures%20and%20Longitudinal%20Electronic%20Health%20Records%20for%20Personalized%20Drug%20Reco/tables/f118a11b5a07b703dafc68b4475c8a96b8cfe818e82bc4009511bf1e0d22b509.jpg)

## Understanding Data Influence in Reinforcement Finetuning


### Images

![67cf7603607a222108369ac9ccba2886afff43c41897056e8b3476d13658472c.jpg](../nips_results/1781_Understanding%20Data%20Influence%20in%20Reinforcement%20Finetuning/images/67cf7603607a222108369ac9ccba2886afff43c41897056e8b3476d13658472c.jpg)

![e944e844e92d45c3c7acaf78ce9f7492fb9127cf2f5d67f33192ba6a9c977459.jpg](../nips_results/1781_Understanding%20Data%20Influence%20in%20Reinforcement%20Finetuning/images/e944e844e92d45c3c7acaf78ce9f7492fb9127cf2f5d67f33192ba6a9c977459.jpg)

![ee65aafd91c25a61f2eb1ee5e15755bfad268d1eb0a36572e5bf871e4f40ed16.jpg](../nips_results/1781_Understanding%20Data%20Influence%20in%20Reinforcement%20Finetuning/images/ee65aafd91c25a61f2eb1ee5e15755bfad268d1eb0a36572e5bf871e4f40ed16.jpg)

### Tables

![b6d8f550516006f15f8bbac41b5017312c539c37b66a23cc641be1dd8f5ddfb0.jpg](../nips_results/1781_Understanding%20Data%20Influence%20in%20Reinforcement%20Finetuning/tables/b6d8f550516006f15f8bbac41b5017312c539c37b66a23cc641be1dd8f5ddfb0.jpg)

## Uni-RL: Unifying Online and Offline RL via Implicit Value Regularization


### Images

![005561a3124cb47a8329197a6fda72b920b23b68626b59ce116c56fe2426ed9f.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/images/005561a3124cb47a8329197a6fda72b920b23b68626b59ce116c56fe2426ed9f.jpg)

![4a654e1d20a8c258fcecffcafd457ece2a51fe2a62a18000cb25b260664e6a73.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/images/4a654e1d20a8c258fcecffcafd457ece2a51fe2a62a18000cb25b260664e6a73.jpg)

![5204328012cd6dff78131155c586af605e1e7d6935093bc500e3b81854f2c4bd.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/images/5204328012cd6dff78131155c586af605e1e7d6935093bc500e3b81854f2c4bd.jpg)

![6e3694845e3a5d2e62944b284293905699b2c33389afa4d32ee96cef786634bd.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/images/6e3694845e3a5d2e62944b284293905699b2c33389afa4d32ee96cef786634bd.jpg)

![7e6feb0cf4ee8a38782119908912f268830c26ca9b05176f2dfe13a07cc3e42c.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/images/7e6feb0cf4ee8a38782119908912f268830c26ca9b05176f2dfe13a07cc3e42c.jpg)

![bae2a297f2d4064a588bfb79beebb724e9465502359a5a7f4426ecff05dbf1f3.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/images/bae2a297f2d4064a588bfb79beebb724e9465502359a5a7f4426ecff05dbf1f3.jpg)

![cabbb998d59c49015a6b8f7c1f897222b167c9fc051e3dc2a94f081e71ddffc6.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/images/cabbb998d59c49015a6b8f7c1f897222b167c9fc051e3dc2a94f081e71ddffc6.jpg)

### Tables

![60efbefcc63aa5ea2a8ecdc674d3f7bf1d819c7c193f3cf486d824d0251c2d3f.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/tables/60efbefcc63aa5ea2a8ecdc674d3f7bf1d819c7c193f3cf486d824d0251c2d3f.jpg)

![7acb5240a5441cdc76c83f7bb90b9c26ba8bf84a94ac16a4a634688ede6338b7.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/tables/7acb5240a5441cdc76c83f7bb90b9c26ba8bf84a94ac16a4a634688ede6338b7.jpg)

![ac9f5e0183e7f8e3a6d512661d801e777f40659905e5f82e44af41d2f14622eb.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/tables/ac9f5e0183e7f8e3a6d512661d801e777f40659905e5f82e44af41d2f14622eb.jpg)

![dc4a220cc75feb5ed1729c1e36636a8b33ca52a60d341f6f9b675bc1cd67c986.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/tables/dc4a220cc75feb5ed1729c1e36636a8b33ca52a60d341f6f9b675bc1cd67c986.jpg)

![ee573b46c91136614b44b2c50f4d2ca0a45b7533d1e788d8ac73efa4394020a9.jpg](../nips_results/1782_Uni-RL_%20Unifying%20Online%20and%20Offline%20RL%20via%20Implicit%20Value%20Regularization/tables/ee573b46c91136614b44b2c50f4d2ca0a45b7533d1e788d8ac73efa4394020a9.jpg)

## ThinkSound: Chain-of-Thought Reasoning in Multimodal LLMs for Audio Generation and Editing


### Images

![009a590e1f2aaf540d3727a6eda6356400f940b03b3624111beb60a36bda1906.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/images/009a590e1f2aaf540d3727a6eda6356400f940b03b3624111beb60a36bda1906.jpg)

![6fdc0dd5e9151ccea53da4f4a90cc1752c1c47a885fc2a31fbc24fba390169ee.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/images/6fdc0dd5e9151ccea53da4f4a90cc1752c1c47a885fc2a31fbc24fba390169ee.jpg)

![d3bba62a72cf7ca679adfd50d13b742e2aebd4a5efa5395d57901f7abd5678b3.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/images/d3bba62a72cf7ca679adfd50d13b742e2aebd4a5efa5395d57901f7abd5678b3.jpg)

![dd5dd843fea17c27b6dafa51f0b6dc25e426bc4553ff609e79990a867148efc1.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/images/dd5dd843fea17c27b6dafa51f0b6dc25e426bc4553ff609e79990a867148efc1.jpg)

![ec8a5c198f981dfb9189aa3d0312e23a671a1044791e6152b3a20ea54484220f.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/images/ec8a5c198f981dfb9189aa3d0312e23a671a1044791e6152b3a20ea54484220f.jpg)

### Tables

![090f767ce801e31673f4a9cdea01b1682c6173d5cd54bb1c27d65f93c3d39581.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/090f767ce801e31673f4a9cdea01b1682c6173d5cd54bb1c27d65f93c3d39581.jpg)

![232b1dd6253b6a9311819afbb907b12e340864f350aa0f1d7628b68f7390d956.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/232b1dd6253b6a9311819afbb907b12e340864f350aa0f1d7628b68f7390d956.jpg)

![361d8876ad7d5765eb4354b1b7deb64ced7fe1c318c4d4ce3cc9f070570b5a15.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/361d8876ad7d5765eb4354b1b7deb64ced7fe1c318c4d4ce3cc9f070570b5a15.jpg)

![556be1f85cb5f208f439a75222f92c1b35dd37d9a5dea3231f6f009e22d94912.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/556be1f85cb5f208f439a75222f92c1b35dd37d9a5dea3231f6f009e22d94912.jpg)

![56386e0cbfa725b7d446e274d3bead4ec8c77dd046011ab7ee860449262baefb.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/56386e0cbfa725b7d446e274d3bead4ec8c77dd046011ab7ee860449262baefb.jpg)

![584412418ae3a63da847e6eea5b43a8747249e75025e7d85bdd150540607c7ec.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/584412418ae3a63da847e6eea5b43a8747249e75025e7d85bdd150540607c7ec.jpg)

![8a5ff4b6c7c71177254db9dcbf0b1f0e6fb431704e29906b067ddf08985c6a41.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/8a5ff4b6c7c71177254db9dcbf0b1f0e6fb431704e29906b067ddf08985c6a41.jpg)

![cf3158de0385394131e2a5d0b10ad8c5aa63f4bc8898e5c0cf1c664b6bed345e.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/cf3158de0385394131e2a5d0b10ad8c5aa63f4bc8898e5c0cf1c664b6bed345e.jpg)

![ee1642b9733148d5b97c48026635e5e2c17128516d77dacd0e874754401bd322.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/ee1642b9733148d5b97c48026635e5e2c17128516d77dacd0e874754401bd322.jpg)

![f07cce068bef7a2627bda61214fc181718e42ec53bda429c11c450bcabcc110e.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/f07cce068bef7a2627bda61214fc181718e42ec53bda429c11c450bcabcc110e.jpg)

![f53b5b03493cc269a2911f5f08b74f48bcbe963b4dc5768fbc6a3bc78b298e06.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/f53b5b03493cc269a2911f5f08b74f48bcbe963b4dc5768fbc6a3bc78b298e06.jpg)

![fb8d86b31f366db0d8c4a2c3c164830f202c60aec65434d6b8e1d575698293fa.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/fb8d86b31f366db0d8c4a2c3c164830f202c60aec65434d6b8e1d575698293fa.jpg)

![fd66ea0d2c28b21f280ed41c39cae0dd120ce7224553ea3647a5f8640849a7c9.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/fd66ea0d2c28b21f280ed41c39cae0dd120ce7224553ea3647a5f8640849a7c9.jpg)

![fff7a38761013edaeb3378e68a6c8613e12566a6a007190a063e2656d47495ed.jpg](../nips_results/1783_ThinkSound_%20Chain-of-Thought%20Reasoning%20in%20Multimodal%20LLMs%20for%20Audio%20Generation%20and%20Editing/tables/fff7a38761013edaeb3378e68a6c8613e12566a6a007190a063e2656d47495ed.jpg)

## Normalization in Attention Dynamics


### Images

![2366844d201af73e59a861ac3213c5bd8f6ade6babfef099edde968076e7b1d4.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/images/2366844d201af73e59a861ac3213c5bd8f6ade6babfef099edde968076e7b1d4.jpg)

![43d29dfada714013f8b5ef92cee0804195ad02213009c07959f95fefacd6f656.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/images/43d29dfada714013f8b5ef92cee0804195ad02213009c07959f95fefacd6f656.jpg)

![5d45bf6144b362d63863378bccec1d53088ba08efae120e67586605a7f414a92.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/images/5d45bf6144b362d63863378bccec1d53088ba08efae120e67586605a7f414a92.jpg)

![6ae9cc3ad6a23b6a7397029f8b69d09c586b9862beb7efd6b99e10d61b1f1229.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/images/6ae9cc3ad6a23b6a7397029f8b69d09c586b9862beb7efd6b99e10d61b1f1229.jpg)

![7ad1e6aeaa4dd19be7dfdc9e7262d336227c46e2f22e5b4934bc6937bc794ba8.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/images/7ad1e6aeaa4dd19be7dfdc9e7262d336227c46e2f22e5b4934bc6937bc794ba8.jpg)

![88f804fcdf62c1da07b19c844273abb03195f050a55ce1b9af6acf7a93655e48.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/images/88f804fcdf62c1da07b19c844273abb03195f050a55ce1b9af6acf7a93655e48.jpg)

![8e25ccca83079abdce054b39593d4e90ef52e74199810e5bd596268b52e56879.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/images/8e25ccca83079abdce054b39593d4e90ef52e74199810e5bd596268b52e56879.jpg)

![c244b4c4920c4ba0a6d57aa373137c519556389b83482301aa8b76b41d7bfa19.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/images/c244b4c4920c4ba0a6d57aa373137c519556389b83482301aa8b76b41d7bfa19.jpg)

![e88e080df2370239265992db885740353f90e36b67032626c7ae725d0cbed7be.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/images/e88e080df2370239265992db885740353f90e36b67032626c7ae725d0cbed7be.jpg)

![f3e8bb51ad1248dc307b590d7ed3606d1e2abae072bf457f65dec09deb5895cc.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/images/f3e8bb51ad1248dc307b590d7ed3606d1e2abae072bf457f65dec09deb5895cc.jpg)

![f72687a64e84daa8fdfcff5e5245ad299f06fedb325c848aea1be6f0d475023c.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/images/f72687a64e84daa8fdfcff5e5245ad299f06fedb325c848aea1be6f0d475023c.jpg)

### Tables

![0421f38aa4f1edcc42b76d062c57fd78f745c57179237ca8d60372311349bf23.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/tables/0421f38aa4f1edcc42b76d062c57fd78f745c57179237ca8d60372311349bf23.jpg)

![2c6c373519c3b693cc7318c8466d726df4ac8f8a8119fbb7c98c15c9c80022ec.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/tables/2c6c373519c3b693cc7318c8466d726df4ac8f8a8119fbb7c98c15c9c80022ec.jpg)

![40f65e3ef21af709940648b84c12954ac6e545f5780b25579e0a6e5f3121bf09.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/tables/40f65e3ef21af709940648b84c12954ac6e545f5780b25579e0a6e5f3121bf09.jpg)

![c0baa257bad466acef427781bd0604a1da5f8474d0cbd1fcdac7a481f44f3832.jpg](../nips_results/1784_Normalization%20in%20Attention%20Dynamics/tables/c0baa257bad466acef427781bd0604a1da5f8474d0cbd1fcdac7a481f44f3832.jpg)

## Low-Rank Head Avatar Personalization with Registers


### Images

![122df95545e56f460a5c0ebab695dba7ee34ef16fb3a53d5490e79bf46d6bac2.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/122df95545e56f460a5c0ebab695dba7ee34ef16fb3a53d5490e79bf46d6bac2.jpg)

![3c388023bd305150c76084a0d8cb1b3ba50f3abfadd75f459e4c9ad236f0ab2d.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/3c388023bd305150c76084a0d8cb1b3ba50f3abfadd75f459e4c9ad236f0ab2d.jpg)

![4825a8b0f8d9ded53d874f9e70aa708ce94b8c0990fc801706784d4a584a9f9f.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/4825a8b0f8d9ded53d874f9e70aa708ce94b8c0990fc801706784d4a584a9f9f.jpg)

![4fa69b6671dced74cbb76ef169042d68c26ff76a9ce2d0c3284fb075cd76b9c8.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/4fa69b6671dced74cbb76ef169042d68c26ff76a9ce2d0c3284fb075cd76b9c8.jpg)

![6be932f25454b13c4f473e052dc98af9990b6d14a212ee4023e6da314d1e0032.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/6be932f25454b13c4f473e052dc98af9990b6d14a212ee4023e6da314d1e0032.jpg)

![75f3c9ecff7a326b980bfc6cd8a1bb4c7ac77ac491e0cc78d14d1ee798420e49.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/75f3c9ecff7a326b980bfc6cd8a1bb4c7ac77ac491e0cc78d14d1ee798420e49.jpg)

![80248c26303b67e74316b3252c33bc7b0ebc965112750e2039afbcab736ed4c1.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/80248c26303b67e74316b3252c33bc7b0ebc965112750e2039afbcab736ed4c1.jpg)

![8eca1ab2c2b0a14f13b1745db16d04ee5b6a4fae8360cd6548a16b382018c905.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/8eca1ab2c2b0a14f13b1745db16d04ee5b6a4fae8360cd6548a16b382018c905.jpg)

![91dee22e4ab5f73e52661272b8893cd38ebab0f14b5aa4707014f11caba9a02f.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/91dee22e4ab5f73e52661272b8893cd38ebab0f14b5aa4707014f11caba9a02f.jpg)

![964dc0eb1830cec3853b6ecaefa50a8bb049dbf02fbfc5a03247bf7d5ba1042b.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/964dc0eb1830cec3853b6ecaefa50a8bb049dbf02fbfc5a03247bf7d5ba1042b.jpg)

![984382c89e5f6abfee7a85f2734742e220481365ca16039067c58e53bf6a5277.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/984382c89e5f6abfee7a85f2734742e220481365ca16039067c58e53bf6a5277.jpg)

![abdf358d45fff57c3b1125f443920a0bd45e20a8c8487bbe677a93a8bca367d1.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/abdf358d45fff57c3b1125f443920a0bd45e20a8c8487bbe677a93a8bca367d1.jpg)

![b28fe0793d02c63b51ce4ac0d2292dbd516ca4f71a8713bc887433dc74c42469.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/b28fe0793d02c63b51ce4ac0d2292dbd516ca4f71a8713bc887433dc74c42469.jpg)

![d1d90771ca4038065629afc9ba7bb91d8a35b1d81d5b292cb270da3c3f5d93c2.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/d1d90771ca4038065629afc9ba7bb91d8a35b1d81d5b292cb270da3c3f5d93c2.jpg)

![d5834ed778d7090bbfd488ef58dadb0de6b869d86504fc60511b7ba1a48b77e0.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/d5834ed778d7090bbfd488ef58dadb0de6b869d86504fc60511b7ba1a48b77e0.jpg)

![df889a29abf388c4692327991f6afcb864ee523922260e382f7368de997dfb73.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/df889a29abf388c4692327991f6afcb864ee523922260e382f7368de997dfb73.jpg)

![f7e2bb7e07477fa826eff125357f4dc8ec263a5f81700a6736e607d4e4382f20.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/f7e2bb7e07477fa826eff125357f4dc8ec263a5f81700a6736e607d4e4382f20.jpg)

![f85e559f931356e48c16afaaeac71bd342b7d69977ce5c478191b85f6320a37d.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/f85e559f931356e48c16afaaeac71bd342b7d69977ce5c478191b85f6320a37d.jpg)

![fd834a636e10ced9e13f63927939e2658dc7778bcc1123e91d3f9af7a9f4307a.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/images/fd834a636e10ced9e13f63927939e2658dc7778bcc1123e91d3f9af7a9f4307a.jpg)

### Tables

![0d89a532782cd2429de420b0db46eccf16ef51935c4fb4242ee925992ab121c3.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/tables/0d89a532782cd2429de420b0db46eccf16ef51935c4fb4242ee925992ab121c3.jpg)

![363eb9a6ae86ce0ac3fe2c7a372fd9c1de6a29790820fdd9288cf5bc2112a8af.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/tables/363eb9a6ae86ce0ac3fe2c7a372fd9c1de6a29790820fdd9288cf5bc2112a8af.jpg)

![434ccd560eabb80739840399f189af58bdb47b12fc2bce49801eaefc6ac93b7b.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/tables/434ccd560eabb80739840399f189af58bdb47b12fc2bce49801eaefc6ac93b7b.jpg)

![bf3c0e913577e71d4b8791c78c9880e3d0c4b43c6551e4748ae97f961a887bfe.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/tables/bf3c0e913577e71d4b8791c78c9880e3d0c4b43c6551e4748ae97f961a887bfe.jpg)

![ca84962c4730062b03fd1bd38231132a57bc2cb95adb2d42914f7c89037359c0.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/tables/ca84962c4730062b03fd1bd38231132a57bc2cb95adb2d42914f7c89037359c0.jpg)

![f52121279c8f61ada0f5bb8ad3764a1c7caec859142d0f721be27a1887cdf8ce.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/tables/f52121279c8f61ada0f5bb8ad3764a1c7caec859142d0f721be27a1887cdf8ce.jpg)

![ff060ec5283095a80b9be689f5c325356625b44d2a71134ad13a9f06faff962b.jpg](../nips_results/1785_Low-Rank%20Head%20Avatar%20Personalization%20with%20Registers/tables/ff060ec5283095a80b9be689f5c325356625b44d2a71134ad13a9f06faff962b.jpg)

## DoDo-Code: an Efficient Levenshtein Distance Embedding-based Code for 4-ary IDS Channel


### Images

![2e2be79a15b06bbd0858a1fd26dec127135dcacd2150d8cd80f47d97f5b7c5b5.jpg](../nips_results/1786_DoDo-Code_%20an%20Efficient%20Levenshtein%20Distance%20Embedding-based%20Code%20for%204-ary%20IDS%20Channel/images/2e2be79a15b06bbd0858a1fd26dec127135dcacd2150d8cd80f47d97f5b7c5b5.jpg)

![310bd8b40df6dd6f5865dea530b33220ea2f3b3641ee3ecb07bdb942db0b486a.jpg](../nips_results/1786_DoDo-Code_%20an%20Efficient%20Levenshtein%20Distance%20Embedding-based%20Code%20for%204-ary%20IDS%20Channel/images/310bd8b40df6dd6f5865dea530b33220ea2f3b3641ee3ecb07bdb942db0b486a.jpg)

![60981b38b1e853748a7478d62c955a85cf407aa84e048abb558dea83ddaacfc7.jpg](../nips_results/1786_DoDo-Code_%20an%20Efficient%20Levenshtein%20Distance%20Embedding-based%20Code%20for%204-ary%20IDS%20Channel/images/60981b38b1e853748a7478d62c955a85cf407aa84e048abb558dea83ddaacfc7.jpg)

![729f2914d91d95d9de3dec16e602f299fc5199fbcbb9d51fda44b5f250ddd648.jpg](../nips_results/1786_DoDo-Code_%20an%20Efficient%20Levenshtein%20Distance%20Embedding-based%20Code%20for%204-ary%20IDS%20Channel/images/729f2914d91d95d9de3dec16e602f299fc5199fbcbb9d51fda44b5f250ddd648.jpg)

![8e7348424922deb0d2ba0f5a5f0d74edf7b6f972264ac6a0bf91da6ac73a8e33.jpg](../nips_results/1786_DoDo-Code_%20an%20Efficient%20Levenshtein%20Distance%20Embedding-based%20Code%20for%204-ary%20IDS%20Channel/images/8e7348424922deb0d2ba0f5a5f0d74edf7b6f972264ac6a0bf91da6ac73a8e33.jpg)

### Tables

![0e3c87f99727c6bb77bd94db5bd4fa39e753211bacccc4e0208ab4568919a162.jpg](../nips_results/1786_DoDo-Code_%20an%20Efficient%20Levenshtein%20Distance%20Embedding-based%20Code%20for%204-ary%20IDS%20Channel/tables/0e3c87f99727c6bb77bd94db5bd4fa39e753211bacccc4e0208ab4568919a162.jpg)

![41008ad9f587f4a8265a8bcaf44d395a58f093d5379530da769cc3b2487c6dfc.jpg](../nips_results/1786_DoDo-Code_%20an%20Efficient%20Levenshtein%20Distance%20Embedding-based%20Code%20for%204-ary%20IDS%20Channel/tables/41008ad9f587f4a8265a8bcaf44d395a58f093d5379530da769cc3b2487c6dfc.jpg)

## Self-Supervised Contrastive Learning is Approximately Supervised Contrastive Learning

### Images

![05ed41689bc1fbb991b181cbe56b12b8ae28ecf04f531794815521b20d153d15.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/05ed41689bc1fbb991b181cbe56b12b8ae28ecf04f531794815521b20d153d15.jpg)

![23b1908da2870bb9f2f34b60bba38b28941d5e5fb3a6f6d6ec7b695ba35c5359.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/23b1908da2870bb9f2f34b60bba38b28941d5e5fb3a6f6d6ec7b695ba35c5359.jpg)

![26b238be85a440c7328a3f4363c3ff5a31fac8d5b36877045e7d0a44fbed2f4f.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/26b238be85a440c7328a3f4363c3ff5a31fac8d5b36877045e7d0a44fbed2f4f.jpg)

![406d26864b0fe95d372e3cff3d2d63e68d1a2637e55d7592aa0e1d3e81837f79.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/406d26864b0fe95d372e3cff3d2d63e68d1a2637e55d7592aa0e1d3e81837f79.jpg)

![519cdcd83c27c1012a9d7074533cc3637bff47a51eb53fb6b971c1672c0846ff.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/519cdcd83c27c1012a9d7074533cc3637bff47a51eb53fb6b971c1672c0846ff.jpg)

![5293208770227c5ceb47c33c7df8566cbdaa019cdbca61416ca04103629904d0.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/5293208770227c5ceb47c33c7df8566cbdaa019cdbca61416ca04103629904d0.jpg)

![78f82e3e69d092151edf2aab423967049faf55dbe8f24437af967cb2e23bdf4f.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/78f82e3e69d092151edf2aab423967049faf55dbe8f24437af967cb2e23bdf4f.jpg)

![7bfbad5b255627a43c339fe35564934e11e8cfb5fcb870462134fc14e41a6192.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/7bfbad5b255627a43c339fe35564934e11e8cfb5fcb870462134fc14e41a6192.jpg)

![87a78308ad938ce49f64371ee483167a991d35db504ef2e7f6940e43d373d1d4.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/87a78308ad938ce49f64371ee483167a991d35db504ef2e7f6940e43d373d1d4.jpg)

![ac6d88fe9cd0aa9bea6b513cfa9400908c50be2b6800a46fbe5a5243e422ef34.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/ac6d88fe9cd0aa9bea6b513cfa9400908c50be2b6800a46fbe5a5243e422ef34.jpg)

![b6977fa8857337d27042a0318533fdf5c6b137ffc94f1b56e4fd3ab987925bb0.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/b6977fa8857337d27042a0318533fdf5c6b137ffc94f1b56e4fd3ab987925bb0.jpg)

![e1280b09bed7d4a10dcb9446697a577c120fb19e067a528706d54cd37dc77e6c.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/e1280b09bed7d4a10dcb9446697a577c120fb19e067a528706d54cd37dc77e6c.jpg)

![e7240fe8f9e4e38d89a94552bba80bf7267b64f12048d51fdc4c9e617f776e5a.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/images/e7240fe8f9e4e38d89a94552bba80bf7267b64f12048d51fdc4c9e617f776e5a.jpg)

### Tables

![0b66d8baa009af28603ef817d2cf25daa4ca8777656ca00384d390db4f098943.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/tables/0b66d8baa009af28603ef817d2cf25daa4ca8777656ca00384d390db4f098943.jpg)

![48c6b964e8d3dc4ef786a2fc9320dabdf676503203e7fd37bff11426caf02f27.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/tables/48c6b964e8d3dc4ef786a2fc9320dabdf676503203e7fd37bff11426caf02f27.jpg)

![eaa34cd9bfa1511f1c5d7c0be32de7cee13998d5fdc74e2a8963c1b28dbe9021.jpg](../nips_results/1787_Self-Supervised%20Contrastive%20Learning%20is%20Approximately%20Supervised%20Contrastive%20Learning/tables/eaa34cd9bfa1511f1c5d7c0be32de7cee13998d5fdc74e2a8963c1b28dbe9021.jpg)
