# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 110 of 130

## 目录 (Table of Contents)

1. [PhysCtrl: Generative Physics for Controllable and Physics-Grounded Video Generation](#PhysCtrl-Generative-Physics-for-Controllable-and-Physics-Grounded-Video-Generation)
2. [Same Task, Different Circuits: Disentangling Modality-Specific Mechanisms in VLMs](#Same-Task-Different-Circuits-Disentangling-Modality-Specific-Mechanisms-in-VLMs)
3. [ReinFlow: Fine-tuning Flow Matching Policy with Online Reinforcement Learning](#ReinFlow-Fine-tuning-Flow-Matching-Policy-with-Online-Reinforcement-Learning)
4. [CAM: A Constructivist View of Agentic Memory for LLM-Based Reading Comprehension](#CAM-A-Constructivist-View-of-Agentic-Memory-for-LLM-Based-Reading-Comprehension)
5. [Towards Understanding Safety Alignment: A Mechanistic Perspective from Safety Neurons](#Towards-Understanding-Safety-Alignment-A-Mechanistic-Perspective-from-Safety-Neurons)
6. [Why 1 + 1 < 1 in Visual Token Pruning: Beyond Naive Integration via Multi-Objective Balanced Covering](#Why-1-1-1-in-Visual-Token-Pruning-Beyond-Naive-Integration-via-Multi-Objective-Balanced-Covering)
7. [Competitive Advantage Attacks to Decentralized Federated Learning](#Competitive-Advantage-Attacks-to-Decentralized-Federated-Learning)
8. [Exploration from a Primal-Dual Lens: Value-Incentivized Actor-Critic Methods for Sample-Efficient Online RL](#Exploration-from-a-Primal-Dual-Lens-Value-Incentivized-Actor-Critic-Methods-for-Sample-Efficient-Online-RL)
9. [PRESCRIBE: Predicting Single-Cell Responses with Bayesian Estimation](#PRESCRIBE-Predicting-Single-Cell-Responses-with-Bayesian-Estimation)
10. [Robust Distributed Estimation: Extending Gossip Algorithms to Ranking and Trimmed Means](#Robust-Distributed-Estimation-Extending-Gossip-Algorithms-to-Ranking-and-Trimmed-Means)
11. [SPRO: Improving Image Generation via Self-Play](#SPRO-Improving-Image-Generation-via-Self-Play)
12. [Thumb on the Scale: Optimal Loss Weighting in Last Layer Retraining](#Thumb-on-the-Scale-Optimal-Loss-Weighting-in-Last-Layer-Retraining)
13. [PLEIADES: Building Temporal Kernels with Orthogonal Polynomials](#PLEIADES-Building-Temporal-Kernels-with-Orthogonal-Polynomials)
14. [Forging Time Series with Language: A Large Language Model Approach to Synthetic Data Generation](#Forging-Time-Series-with-Language-A-Large-Language-Model-Approach-to-Synthetic-Data-Generation)
15. [NaViL: Rethinking Scaling Properties of Native Multimodal Large Language Models under Data Constraints](#NaViL-Rethinking-Scaling-Properties-of-Native-Multimodal-Large-Language-Models-under-Data-Constraints)
16. [What's Producible May Not Be Reachable: Measuring the Steerability of Generative Models](#Whats-Producible-May-Not-Be-Reachable-Measuring-the-Steerability-of-Generative-Models)
17. [On the Optimality of the Median-of-Means Estimator under Adversarial Contamination](#On-the-Optimality-of-the-Median-of-Means-Estimator-under-Adversarial-Contamination)
18. [Consistently Simulating Human Personas with Multi-Turn Reinforcement Learning](#Consistently-Simulating-Human-Personas-with-Multi-Turn-Reinforcement-Learning)
19. [NoisyRollout: Reinforcing Visual Reasoning with Data Augmentation](#NoisyRollout-Reinforcing-Visual-Reasoning-with-Data-Augmentation)
20. [Can Class-Priors Help Single-Positive Multi-Label Learning?](#Can-Class-Priors-Help-Single-Positive-Multi-Label-Learning)
21. [Self-Challenging Language Model Agents](#Self-Challenging-Language-Model-Agents)
22. [GSPN-2: Efficient Parallel Sequence Modeling](#GSPN-2-Efficient-Parallel-Sequence-Modeling)
23. [A Frustratingly Simple Yet Highly Effective Attack Baseline: Over 90% Success Rate Against the Strong Black-box Models of GPT-4.5/4o/o1](#A-Frustratingly-Simple-Yet-Highly-Effective-Attack-Baseline-Over-90-Success-Rate-Against-the-Strong-Black-box-Models-of-GPT-454oo1)
24. [How Ensembles of Distilled Policies Improve Generalisation in Reinforcement Learning](#How-Ensembles-of-Distilled-Policies-Improve-Generalisation-in-Reinforcement-Learning)
25. [Tensor Decomposition Networks for Accelerating Machine Learning Force Field Computations](#Tensor-Decomposition-Networks-for-Accelerating-Machine-Learning-Force-Field-Computations)
26. [Inverse Optimization Latent Variable Models for Learning Costs Applied to Route Problems](#Inverse-Optimization-Latent-Variable-Models-for-Learning-Costs-Applied-to-Route-Problems)
27. [Smoothed Agnostic Learning of Halfspaces over the Hypercube](#Smoothed-Agnostic-Learning-of-Halfspaces-over-the-Hypercube)
28. [Self-Guided Hierarchical Exploration for Generalist Foundation Model Web Agents](#Self-Guided-Hierarchical-Exploration-for-Generalist-Foundation-Model-Web-Agents)
29. [Tightening Regret Lower and Upper Bounds in Restless Rising Bandits](#Tightening-Regret-Lower-and-Upper-Bounds-in-Restless-Rising-Bandits)
30. [MLZero: A Multi-Agent System for End-to-end Machine Learning Automation](#MLZero-A-Multi-Agent-System-for-End-to-end-Machine-Learning-Automation)
31. [Enhancing Optimizer Stability: Momentum Adaptation of The NGN Step-size](#Enhancing-Optimizer-Stability-Momentum-Adaptation-of-The-NGN-Step-size)
32. [An Adaptive Algorithm for Bilevel Optimization on Riemannian Manifolds](#An-Adaptive-Algorithm-for-Bilevel-Optimization-on-Riemannian-Manifolds)
33. [Text-to-Decision Agent: Offline Meta-Reinforcement Learning from Natural Language Supervision](#Text-to-Decision-Agent-Offline-Meta-Reinforcement-Learning-from-Natural-Language-Supervision)
34. [$i$MIND: Insightful Multi-subject Invariant Neural Decoding](#iMIND-Insightful-Multi-subject-Invariant-Neural-Decoding)
35. [Segment Policy Optimization: Effective Segment-Level Credit Assignment in RL for Large Language Models](#Segment-Policy-Optimization-Effective-Segment-Level-Credit-Assignment-in-RL-for-Large-Language-Models)
36. [HypoBootstrap: A Bootstrapping Framework for Inductive Reasoning](#HypoBootstrap-A-Bootstrapping-Framework-for-Inductive-Reasoning)
37. [LoTA-QAF: Lossless Ternary Adaptation for Quantization-Aware Fine-Tuning](#LoTA-QAF-Lossless-Ternary-Adaptation-for-Quantization-Aware-Fine-Tuning)
38. [Dual-Comb Ghost Imaging with Transformer-Based Reconstruction for Optical Fiber Endomicroscopy](#Dual-Comb-Ghost-Imaging-with-Transformer-Based-Reconstruction-for-Optical-Fiber-Endomicroscopy)
39. [Object-Centric Concept-Bottlenecks](#Object-Centric-Concept-Bottlenecks)
40. [Towards Pre-trained Graph Condensation via Optimal Transport](#Towards-Pre-trained-Graph-Condensation-via-Optimal-Transport)
41. [Secure and Confidential Certificates of Online Fairness](#Secure-and-Confidential-Certificates-of-Online-Fairness)

---


## PhysCtrl: Generative Physics for Controllable and Physics-Grounded Video Generation

### Images

![d50bd8e3253c2492120ffd69849e0f274ec3a46d2e4188cf6c152ae0f7237fd2.jpg](../nips_results/4516_GLID%24%5E2%24E_%20A%20Gradient-Free%20Lightweight%20Fine-tune%20Approach%20for%20Discrete%20Biological%20Sequence%20Design/images/d50bd8e3253c2492120ffd69849e0f274ec3a46d2e4188cf6c152ae0f7237fd2.jpg)

### Tables

![33b3e14f0c886aead1cdcaaf089c3f8287c53ecd9fae8a7d9f0f6d2d84b2f784.jpg](../nips_results/4516_GLID%24%5E2%24E_%20A%20Gradient-Free%20Lightweight%20Fine-tune%20Approach%20for%20Discrete%20Biological%20Sequence%20Design/tables/33b3e14f0c886aead1cdcaaf089c3f8287c53ecd9fae8a7d9f0f6d2d84b2f784.jpg)

![5ff278e514e8864f8b1615f82398c69b578ce0313d2941848af58e5d0164a975.jpg](../nips_results/4516_GLID%24%5E2%24E_%20A%20Gradient-Free%20Lightweight%20Fine-tune%20Approach%20for%20Discrete%20Biological%20Sequence%20Design/tables/5ff278e514e8864f8b1615f82398c69b578ce0313d2941848af58e5d0164a975.jpg)

![653a0e1ebb8c8ca7e46d63f7e86580346e347ad679d009f9d2d9acfbea004c4d.jpg](../nips_results/4516_GLID%24%5E2%24E_%20A%20Gradient-Free%20Lightweight%20Fine-tune%20Approach%20for%20Discrete%20Biological%20Sequence%20Design/tables/653a0e1ebb8c8ca7e46d63f7e86580346e347ad679d009f9d2d9acfbea004c4d.jpg)

![65a4dba0ca5401e71e6e4124baa1efdfcb9e21dde12e06c0d944421a4e6432fa.jpg](../nips_results/4516_GLID%24%5E2%24E_%20A%20Gradient-Free%20Lightweight%20Fine-tune%20Approach%20for%20Discrete%20Biological%20Sequence%20Design/tables/65a4dba0ca5401e71e6e4124baa1efdfcb9e21dde12e06c0d944421a4e6432fa.jpg)

![777f91c8f5dac4bffa8708b7011da40b7e083ca49f8aa8591e1ed26d0df48959.jpg](../nips_results/4516_GLID%24%5E2%24E_%20A%20Gradient-Free%20Lightweight%20Fine-tune%20Approach%20for%20Discrete%20Biological%20Sequence%20Design/tables/777f91c8f5dac4bffa8708b7011da40b7e083ca49f8aa8591e1ed26d0df48959.jpg)

![a2266b2063477845bc963b0e4601aa8f844ff78593209289ac6b4f9bb11d7fd2.jpg](../nips_results/4516_GLID%24%5E2%24E_%20A%20Gradient-Free%20Lightweight%20Fine-tune%20Approach%20for%20Discrete%20Biological%20Sequence%20Design/tables/a2266b2063477845bc963b0e4601aa8f844ff78593209289ac6b4f9bb11d7fd2.jpg)

![a44e0ef1b796a158b24eefc191aa0f191bc63e745d03f97fcd1bb0f124dd5060.jpg](../nips_results/4516_GLID%24%5E2%24E_%20A%20Gradient-Free%20Lightweight%20Fine-tune%20Approach%20for%20Discrete%20Biological%20Sequence%20Design/tables/a44e0ef1b796a158b24eefc191aa0f191bc63e745d03f97fcd1bb0f124dd5060.jpg)

![c70c732022bd67fe87c825adbe4739425348ae59b2a99c78647d3d6ddbd51f46.jpg](../nips_results/4516_GLID%24%5E2%24E_%20A%20Gradient-Free%20Lightweight%20Fine-tune%20Approach%20for%20Discrete%20Biological%20Sequence%20Design/tables/c70c732022bd67fe87c825adbe4739425348ae59b2a99c78647d3d6ddbd51f46.jpg)

![cbdeb6c63f9d4d68a9647341b9f278985d087a7b67caf87b23faf90728a49c96.jpg](../nips_results/4516_GLID%24%5E2%24E_%20A%20Gradient-Free%20Lightweight%20Fine-tune%20Approach%20for%20Discrete%20Biological%20Sequence%20Design/tables/cbdeb6c63f9d4d68a9647341b9f278985d087a7b67caf87b23faf90728a49c96.jpg)

![cdcc88dca10bd65571f1b9dea96e565963973168a2e5b911d68326229dc2863d.jpg](../nips_results/4516_GLID%24%5E2%24E_%20A%20Gradient-Free%20Lightweight%20Fine-tune%20Approach%20for%20Discrete%20Biological%20Sequence%20Design/tables/cdcc88dca10bd65571f1b9dea96e565963973168a2e5b911d68326229dc2863d.jpg)

## PhysCtrl: Generative Physics for Controllable and Physics-Grounded Video Generation


### Images

![2e0376bb1296dd0c6a0ad18e59ce082e6b1c2e5d9d84f85a415efb9850a57779.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/images/2e0376bb1296dd0c6a0ad18e59ce082e6b1c2e5d9d84f85a415efb9850a57779.jpg)

![34a1f038e99c88b79c5d468c6839df8bc04d16b4ee6b2d8c399f50a8b8e50200.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/images/34a1f038e99c88b79c5d468c6839df8bc04d16b4ee6b2d8c399f50a8b8e50200.jpg)

![3baf3094dcfcbf214828e9fc8a88bade41f76f3798834789218e441bf7e85fd3.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/images/3baf3094dcfcbf214828e9fc8a88bade41f76f3798834789218e441bf7e85fd3.jpg)

![4007b39b22b303460f90ac9e03cb9735760414a92c39230f3e313ba24b704b3b.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/images/4007b39b22b303460f90ac9e03cb9735760414a92c39230f3e313ba24b704b3b.jpg)

![51d3f31b6b8676ba7d1435311d58c049210b3dff373f0ce2690d3b4dbd3d4a74.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/images/51d3f31b6b8676ba7d1435311d58c049210b3dff373f0ce2690d3b4dbd3d4a74.jpg)

![9e1f958eb4ae1ce6c789cdf8bfc01ce49af9da6f1abff2b471005a28301c78f6.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/images/9e1f958eb4ae1ce6c789cdf8bfc01ce49af9da6f1abff2b471005a28301c78f6.jpg)

![b84ea52e10e61d628031206f013d214f50ed8b0bb835ea3bb837efe8af540813.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/images/b84ea52e10e61d628031206f013d214f50ed8b0bb835ea3bb837efe8af540813.jpg)

![be5ef0556c58f1867f8fccce79cb7b54ea69e42a6b7da753218e368a93410528.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/images/be5ef0556c58f1867f8fccce79cb7b54ea69e42a6b7da753218e368a93410528.jpg)

![dccd5c2b9fdcb276199b8b9e1527276d940f85fa6d9a65ada4453fb703e5bb92.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/images/dccd5c2b9fdcb276199b8b9e1527276d940f85fa6d9a65ada4453fb703e5bb92.jpg)

### Tables

![0af6aa02fd1bc1866aeda5c49511879233b88d3d32ae3bf0cb36ecdfbbcd08da.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/tables/0af6aa02fd1bc1866aeda5c49511879233b88d3d32ae3bf0cb36ecdfbbcd08da.jpg)

![9a7ce9716d592d1a92250aa71987240cccf1968f34b3ccfddb4549d40ebab9d2.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/tables/9a7ce9716d592d1a92250aa71987240cccf1968f34b3ccfddb4549d40ebab9d2.jpg)

![a0e276d1d4fd392d749fc4d3228d72ea2559db21745be4b2ef74525a10b0ab4d.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/tables/a0e276d1d4fd392d749fc4d3228d72ea2559db21745be4b2ef74525a10b0ab4d.jpg)

![e1d69595856929566c2df20ffac51d60be546aad896d8971e79bff71369a9b89.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/tables/e1d69595856929566c2df20ffac51d60be546aad896d8971e79bff71369a9b89.jpg)

![ed66cb2f4f75c158869cbb5fdd53f6a194409f853b71311d99a884c162853e2e.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/tables/ed66cb2f4f75c158869cbb5fdd53f6a194409f853b71311d99a884c162853e2e.jpg)

![f584313f8fb31f3f2ce6d8919eff3449da255c7be7a2a5f6a0c53d72d634b97c.jpg](../nips_results/4517_PhysCtrl_%20Generative%20Physics%20for%20Controllable%20and%20Physics-Grounded%20Video%20Generation/tables/f584313f8fb31f3f2ce6d8919eff3449da255c7be7a2a5f6a0c53d72d634b97c.jpg)

## Same Task, Different Circuits: Disentangling Modality-Specific Mechanisms in VLMs


### Images

![02a82c4dacd804c170400c6b1414053c963041cdba9bc65081f4bcad4ffce25f.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/02a82c4dacd804c170400c6b1414053c963041cdba9bc65081f4bcad4ffce25f.jpg)

![2f4e0baa8ccaddb7f4327dd5e7efb4ba267d5e1fcb65f804fc206ac8f4ffd266.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/2f4e0baa8ccaddb7f4327dd5e7efb4ba267d5e1fcb65f804fc206ac8f4ffd266.jpg)

![4caf878d385c713a416c8df76270841d7687f1b5f5637568ab560ab7e4fe63db.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/4caf878d385c713a416c8df76270841d7687f1b5f5637568ab560ab7e4fe63db.jpg)

![5391872af15e704ff654bb29ff52e0c71890e5b63ecf122b64f26ea290117b25.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/5391872af15e704ff654bb29ff52e0c71890e5b63ecf122b64f26ea290117b25.jpg)

![63c614cafceb5daf35493ee01f9ffc0720b9cba0ac3513ffb9e757c182af7e84.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/63c614cafceb5daf35493ee01f9ffc0720b9cba0ac3513ffb9e757c182af7e84.jpg)

![75a22214fbb10ab90069fb4d8f8c162758cafd201d1d4bd68db19859d66377c0.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/75a22214fbb10ab90069fb4d8f8c162758cafd201d1d4bd68db19859d66377c0.jpg)

![8b8e6d261555d1177f25f2e4c4d4de8ec25e3780f1c3b4606fc87fe062edfd14.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/8b8e6d261555d1177f25f2e4c4d4de8ec25e3780f1c3b4606fc87fe062edfd14.jpg)

![a849504db206dc51387c52b4eabeffa7e42fda4978d82034be7c4a9b9c82f48a.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/a849504db206dc51387c52b4eabeffa7e42fda4978d82034be7c4a9b9c82f48a.jpg)

![a8b622b71cf17ff04fcdd28f09a606eb4cccd4a6d0bc4a608b501e39cd81734d.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/a8b622b71cf17ff04fcdd28f09a606eb4cccd4a6d0bc4a608b501e39cd81734d.jpg)

![ad4175ad07cb512e17b3dedb8c71fcef8eeb66c124ae8b64a7088b9a125b3797.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/ad4175ad07cb512e17b3dedb8c71fcef8eeb66c124ae8b64a7088b9a125b3797.jpg)

![bdbb76e108a35fd8c7d2312eaf5751173e56fcc625edb1b4cb14b001dcacd0ab.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/bdbb76e108a35fd8c7d2312eaf5751173e56fcc625edb1b4cb14b001dcacd0ab.jpg)

![dad094260c34bb4d1fef6196153dd0b91d29bfde587ebbd3091eb9b6b8bc8c01.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/dad094260c34bb4d1fef6196153dd0b91d29bfde587ebbd3091eb9b6b8bc8c01.jpg)

![f273ad0c98b7e00d0408fdbac02477e1332a8cc1d51bf332565caf1b8cf8d828.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/f273ad0c98b7e00d0408fdbac02477e1332a8cc1d51bf332565caf1b8cf8d828.jpg)

![f31d5c7cd608ce7180257f2c7d737a6562e35ba2fc24e17f8b18d0e7732b0498.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/images/f31d5c7cd608ce7180257f2c7d737a6562e35ba2fc24e17f8b18d0e7732b0498.jpg)

### Tables

![06323bd8a058ac04580c0b1623030a7d554134bdae7547ff9887ba447ae4f076.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/tables/06323bd8a058ac04580c0b1623030a7d554134bdae7547ff9887ba447ae4f076.jpg)

![2b75e1d61c1c91efb277f98371243281a6bd12cf00cacd36f7becc70aaf42933.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/tables/2b75e1d61c1c91efb277f98371243281a6bd12cf00cacd36f7becc70aaf42933.jpg)

![2c341945184f0c2d8c732f9427ed9e24bf9eaac3e66080a917fd8466a3deb4b9.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/tables/2c341945184f0c2d8c732f9427ed9e24bf9eaac3e66080a917fd8466a3deb4b9.jpg)

![2fe1f2cdf055e9c18d497ad3f20c3dd4c30cc2a13b9c5009dd41b46d6830a073.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/tables/2fe1f2cdf055e9c18d497ad3f20c3dd4c30cc2a13b9c5009dd41b46d6830a073.jpg)

![309ffe4b7ef55d29b7c5666bcac7137564452985589b64909fd96fbd4f7044c6.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/tables/309ffe4b7ef55d29b7c5666bcac7137564452985589b64909fd96fbd4f7044c6.jpg)

![7f6a31da770b1638d7391c156fe5a2113e9b00ebe4935241daccfb1ccc6b0a3e.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/tables/7f6a31da770b1638d7391c156fe5a2113e9b00ebe4935241daccfb1ccc6b0a3e.jpg)

![8c19b5d818f7028f7f739c0e4ad43b1461853cf86ade5a57d8b8036ae2269d16.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/tables/8c19b5d818f7028f7f739c0e4ad43b1461853cf86ade5a57d8b8036ae2269d16.jpg)

![8d7c26e96e91c2b01e8682aff4c91d5aa20ede4139e40d69de3eaa70347214ff.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/tables/8d7c26e96e91c2b01e8682aff4c91d5aa20ede4139e40d69de3eaa70347214ff.jpg)

![c21c00cbb7475fed470a9450a4a7d68c3330d5d90ce51a6c88191bef80330edd.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/tables/c21c00cbb7475fed470a9450a4a7d68c3330d5d90ce51a6c88191bef80330edd.jpg)

![caae76545dc252fac2ba617f05b9423ac98c53008d103b651b0ddc0f429050f7.jpg](../nips_results/4518_Same%20Task%2C%20Different%20Circuits_%20Disentangling%20Modality-Specific%20Mechanisms%20in%20VLMs/tables/caae76545dc252fac2ba617f05b9423ac98c53008d103b651b0ddc0f429050f7.jpg)

## ReinFlow: Fine-tuning Flow Matching Policy with Online Reinforcement Learning


### Images

![20919d6a8db6d69f9330840036da3324c07ed36b9874cb12e61bb4cc12ba9fca.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/20919d6a8db6d69f9330840036da3324c07ed36b9874cb12e61bb4cc12ba9fca.jpg)

![329f13f30077028966fedf22d7498591a8f92516abc92c9a2ecbd89a54454ebd.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/329f13f30077028966fedf22d7498591a8f92516abc92c9a2ecbd89a54454ebd.jpg)

![37081170fb1b2cd545a151f9dac1266229817e4a40560f8c107fad576e78a3a0.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/37081170fb1b2cd545a151f9dac1266229817e4a40560f8c107fad576e78a3a0.jpg)

![590640182dfc3b59f77bbd03123edd7e1a8f1f370399a47619f00bb824b73262.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/590640182dfc3b59f77bbd03123edd7e1a8f1f370399a47619f00bb824b73262.jpg)

![72d938628a609b0ac61d1eab64c1f1eb55c5761a40cbc3e895edc605b1bf7dd9.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/72d938628a609b0ac61d1eab64c1f1eb55c5761a40cbc3e895edc605b1bf7dd9.jpg)

![8b78cc4dc0db4ffbbaf3c098efbbad06f5a3fc5c55bb4c8d466f43258d566b94.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/8b78cc4dc0db4ffbbaf3c098efbbad06f5a3fc5c55bb4c8d466f43258d566b94.jpg)

![9a5f284391b32bc5bd3d71ada89df3cb3f939d3e7fea623a5dffc144876a8f4b.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/9a5f284391b32bc5bd3d71ada89df3cb3f939d3e7fea623a5dffc144876a8f4b.jpg)

![9eadc9ad7b3bd0ca4e5fb2d3ed4485178f6c9b32fdee082ad0d44a175e85534e.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/9eadc9ad7b3bd0ca4e5fb2d3ed4485178f6c9b32fdee082ad0d44a175e85534e.jpg)

![a1c63d4b79d7ec608042c23985c33c1c20cbbc11869be08e0bee3dce51d37a29.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/a1c63d4b79d7ec608042c23985c33c1c20cbbc11869be08e0bee3dce51d37a29.jpg)

![beb0e9bcb9215b1caaa57cb6812b92d63b8fc81ad7edad2b4064d956cce7f49c.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/beb0e9bcb9215b1caaa57cb6812b92d63b8fc81ad7edad2b4064d956cce7f49c.jpg)

![f67e95a7476c2e97510de030116ebf3e4e37f99c8e07f3959798b019ac0d93c7.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/f67e95a7476c2e97510de030116ebf3e4e37f99c8e07f3959798b019ac0d93c7.jpg)

![f8c91ba85508dbbf2c8223d016717605e9d095f3fe11cc8e59edb997132e4177.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/f8c91ba85508dbbf2c8223d016717605e9d095f3fe11cc8e59edb997132e4177.jpg)

![ff4fc81a648feef6ccd40f64f043c0d076600ea30e8ada21b8b8f934fbec0460.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/images/ff4fc81a648feef6ccd40f64f043c0d076600ea30e8ada21b8b8f934fbec0460.jpg)

### Tables

![01519c3f2baad2b6b7fc1777e8263bb8df8ebb5b6ac368d2f0eda2e335bc6d5c.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/01519c3f2baad2b6b7fc1777e8263bb8df8ebb5b6ac368d2f0eda2e335bc6d5c.jpg)

![2149828bc7cbfb75243fea6a871c8a9015f60848ddaa295d192b51af82df65d4.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/2149828bc7cbfb75243fea6a871c8a9015f60848ddaa295d192b51af82df65d4.jpg)

![22540de3aaf51f200b7e54b2b97905bd304b47e080d7f443854c128c82076cff.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/22540de3aaf51f200b7e54b2b97905bd304b47e080d7f443854c128c82076cff.jpg)

![238e58ff0ac508eea16b384ab635c9b7901339de31c06dc3c46fee9f9e08593e.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/238e58ff0ac508eea16b384ab635c9b7901339de31c06dc3c46fee9f9e08593e.jpg)

![30c69d9b964737c6a05b4a9bdef63cf66edc941b57feb21d25adb481e765f91b.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/30c69d9b964737c6a05b4a9bdef63cf66edc941b57feb21d25adb481e765f91b.jpg)

![37ca7e99cb4ab284e57782f9a75d760762e8ae7cfca3b6b017a70cadd902f381.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/37ca7e99cb4ab284e57782f9a75d760762e8ae7cfca3b6b017a70cadd902f381.jpg)

![3e6d1690aa337191b69a32924c5a263a3c4599162497417712b3bf7e69f61b95.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/3e6d1690aa337191b69a32924c5a263a3c4599162497417712b3bf7e69f61b95.jpg)

![5d61d564dc9c790382a95af25cb815dc3328488439003192d74b3e3be758b322.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/5d61d564dc9c790382a95af25cb815dc3328488439003192d74b3e3be758b322.jpg)

![6be6ee5a9bc9b815b3026ff826b6b92eaf557826f8ccfd8fbf341d84b67e3502.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/6be6ee5a9bc9b815b3026ff826b6b92eaf557826f8ccfd8fbf341d84b67e3502.jpg)

![7f7f8add361750fd6b1d147e704e75bb2ef40d7e23ff72aef40b9a33c080340a.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/7f7f8add361750fd6b1d147e704e75bb2ef40d7e23ff72aef40b9a33c080340a.jpg)

![8c6dfb9bbd6e2274d58cd933d0c08950f7c89da856bbc7954474882fe2251692.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/8c6dfb9bbd6e2274d58cd933d0c08950f7c89da856bbc7954474882fe2251692.jpg)

![9ad8af4b7b0f5c11ef4276a785d9f631201888e8c7593af0915187bc27ff8c85.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/9ad8af4b7b0f5c11ef4276a785d9f631201888e8c7593af0915187bc27ff8c85.jpg)

![9e0d7b2d36c441cb7cfc1949ea85c4246b2a622560c3c21334bd15b6a6b3e4bd.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/9e0d7b2d36c441cb7cfc1949ea85c4246b2a622560c3c21334bd15b6a6b3e4bd.jpg)

![aa02758763371fe5bf6000ed0f837a8da03c433d0b63b716e6a2a80c0598d766.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/aa02758763371fe5bf6000ed0f837a8da03c433d0b63b716e6a2a80c0598d766.jpg)

![ce64fae9d42eb7366f39f3db4ded76a860c8698c83abdba8104199903df6d12c.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/ce64fae9d42eb7366f39f3db4ded76a860c8698c83abdba8104199903df6d12c.jpg)

![e43b708c2756847a6a3079074b56e3823ea6580f5bc9ebaac5e6aa238498e98d.jpg](../nips_results/4519_ReinFlow_%20Fine-tuning%20Flow%20Matching%20Policy%20with%20Online%20Reinforcement%20Learning/tables/e43b708c2756847a6a3079074b56e3823ea6580f5bc9ebaac5e6aa238498e98d.jpg)

## CAM: A Constructivist View of Agentic Memory for LLM-Based Reading Comprehension


### Images

![3fb0b2211a137e12664304502092f8db637f96f77fa3aaaad165a0a29bd8831e.jpg](../nips_results/4520_CAM_%20A%20Constructivist%20View%20of%20Agentic%20Memory%20for%20LLM-Based%20Reading%20Comprehension/images/3fb0b2211a137e12664304502092f8db637f96f77fa3aaaad165a0a29bd8831e.jpg)

![be8079c532567261968f86c545338f4ff2d975b1d75fefea9847ccbb0b72951f.jpg](../nips_results/4520_CAM_%20A%20Constructivist%20View%20of%20Agentic%20Memory%20for%20LLM-Based%20Reading%20Comprehension/images/be8079c532567261968f86c545338f4ff2d975b1d75fefea9847ccbb0b72951f.jpg)

![c1ffb5f8e63e6edfd725d7123be4b7798f53e70de078876142bad19686037a67.jpg](../nips_results/4520_CAM_%20A%20Constructivist%20View%20of%20Agentic%20Memory%20for%20LLM-Based%20Reading%20Comprehension/images/c1ffb5f8e63e6edfd725d7123be4b7798f53e70de078876142bad19686037a67.jpg)

![c983f86ffee70f5f2fb7772a684d07ce862f6f7a28502daaf27bcb67733126aa.jpg](../nips_results/4520_CAM_%20A%20Constructivist%20View%20of%20Agentic%20Memory%20for%20LLM-Based%20Reading%20Comprehension/images/c983f86ffee70f5f2fb7772a684d07ce862f6f7a28502daaf27bcb67733126aa.jpg)

### Tables

![113f4f302d5da3877ac545f389d9810cc71196ddfdc91063b886b5fe94d28f99.jpg](../nips_results/4520_CAM_%20A%20Constructivist%20View%20of%20Agentic%20Memory%20for%20LLM-Based%20Reading%20Comprehension/tables/113f4f302d5da3877ac545f389d9810cc71196ddfdc91063b886b5fe94d28f99.jpg)

![16770b86607c9b0965fcd5bf11376dc10c94e926d678564d7150e08e72222609.jpg](../nips_results/4520_CAM_%20A%20Constructivist%20View%20of%20Agentic%20Memory%20for%20LLM-Based%20Reading%20Comprehension/tables/16770b86607c9b0965fcd5bf11376dc10c94e926d678564d7150e08e72222609.jpg)

![5b36950c00743d1efc6feefb9e73164cceb65e93c886c4019bf1a04edfa955d4.jpg](../nips_results/4520_CAM_%20A%20Constructivist%20View%20of%20Agentic%20Memory%20for%20LLM-Based%20Reading%20Comprehension/tables/5b36950c00743d1efc6feefb9e73164cceb65e93c886c4019bf1a04edfa955d4.jpg)

![6586f64a41b56354d3482c63c57f1ee78f58f13c27cfa56869295edbf6908ac5.jpg](../nips_results/4520_CAM_%20A%20Constructivist%20View%20of%20Agentic%20Memory%20for%20LLM-Based%20Reading%20Comprehension/tables/6586f64a41b56354d3482c63c57f1ee78f58f13c27cfa56869295edbf6908ac5.jpg)

![a61534b02b5b4829c70e5897b874347b5ecded1f5dec6e4543068bbaeb072f55.jpg](../nips_results/4520_CAM_%20A%20Constructivist%20View%20of%20Agentic%20Memory%20for%20LLM-Based%20Reading%20Comprehension/tables/a61534b02b5b4829c70e5897b874347b5ecded1f5dec6e4543068bbaeb072f55.jpg)

![ac8adade22ecc944cc418089556d737d6fb523fcece66856d3b6ae78a80af7d0.jpg](../nips_results/4520_CAM_%20A%20Constructivist%20View%20of%20Agentic%20Memory%20for%20LLM-Based%20Reading%20Comprehension/tables/ac8adade22ecc944cc418089556d737d6fb523fcece66856d3b6ae78a80af7d0.jpg)

![d188396d86912e9d71c2b0e15b1f131965c8d3c89fbaced8d3724d0f055ad651.jpg](../nips_results/4520_CAM_%20A%20Constructivist%20View%20of%20Agentic%20Memory%20for%20LLM-Based%20Reading%20Comprehension/tables/d188396d86912e9d71c2b0e15b1f131965c8d3c89fbaced8d3724d0f055ad651.jpg)

## Towards Understanding Safety Alignment: A Mechanistic Perspective from Safety Neurons


### Images

![125dd053e1ff069c0642498062ed75a1f1b70d914a2326f1235a8d99a9b4fb40.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/images/125dd053e1ff069c0642498062ed75a1f1b70d914a2326f1235a8d99a9b4fb40.jpg)

![1eaf6d5e2be636d2729ab802a43a5d6faf618b524c3d46fdd38decf94192c5e7.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/images/1eaf6d5e2be636d2729ab802a43a5d6faf618b524c3d46fdd38decf94192c5e7.jpg)

![472c0b90faa40d5586c78e2a971e703be22a2207bebf70412874ca08292d6e02.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/images/472c0b90faa40d5586c78e2a971e703be22a2207bebf70412874ca08292d6e02.jpg)

![49ee325c331e0d06331917b2632dea6377bf33ee1b59bb565f10e993682bed17.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/images/49ee325c331e0d06331917b2632dea6377bf33ee1b59bb565f10e993682bed17.jpg)

![846b7829f4abd647080c938f2e3db468280ba099485d6b7c5abcf5551cb47183.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/images/846b7829f4abd647080c938f2e3db468280ba099485d6b7c5abcf5551cb47183.jpg)

![85eb85ebea4c53d7f07f4a73b30aec1bc6057a290d5d592f2642371b294b257b.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/images/85eb85ebea4c53d7f07f4a73b30aec1bc6057a290d5d592f2642371b294b257b.jpg)

![aa039ab187084f016c20aedd0fe0ec00f0c2e72ebaffe5c1377ba3a81497554f.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/images/aa039ab187084f016c20aedd0fe0ec00f0c2e72ebaffe5c1377ba3a81497554f.jpg)

![ada95cd47aaf515cc6886424f7a76170a31f98e442ddb36140b9c4a1ce41841a.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/images/ada95cd47aaf515cc6886424f7a76170a31f98e442ddb36140b9c4a1ce41841a.jpg)

![ca27360ffebc4544ecbb2dc4870646d64484b203e0c345da65f33135c6da71f3.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/images/ca27360ffebc4544ecbb2dc4870646d64484b203e0c345da65f33135c6da71f3.jpg)

![e9a713a474c62ff248676ff032eb94d10271719af143ea0651c5fff1c1c5330f.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/images/e9a713a474c62ff248676ff032eb94d10271719af143ea0651c5fff1c1c5330f.jpg)

![f03d70639e999bd49bca5d6d0e514ffabddca31208fe91c9dff1ce897d163fe7.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/images/f03d70639e999bd49bca5d6d0e514ffabddca31208fe91c9dff1ce897d163fe7.jpg)

### Tables

![18a9e6828dfdb7e5243607ac3e1c706bad0417a912f027c8f2ee21f2faed1eba.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/tables/18a9e6828dfdb7e5243607ac3e1c706bad0417a912f027c8f2ee21f2faed1eba.jpg)

![1fbc7037287d5adbcb42e4eac557b07b1e829a0f170604401bcc112d98549c66.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/tables/1fbc7037287d5adbcb42e4eac557b07b1e829a0f170604401bcc112d98549c66.jpg)

![42f7ceb19e3b898706f4573495b57d997701493813f1585683c329a9f67c8dcb.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/tables/42f7ceb19e3b898706f4573495b57d997701493813f1585683c329a9f67c8dcb.jpg)

![5d35b6c7c36f59831f586eddac95fd3c4f1e20a9a43b47ea1f1e953488f84157.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/tables/5d35b6c7c36f59831f586eddac95fd3c4f1e20a9a43b47ea1f1e953488f84157.jpg)

![8e8fe5c20f346cc886aa82d0764a09b30e19cad01704beb984c6c808528d900c.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/tables/8e8fe5c20f346cc886aa82d0764a09b30e19cad01704beb984c6c808528d900c.jpg)

![9508e67b1894f0ddc69e888a117fcd9e8b787b1c98ce91249e573543434a7e5c.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/tables/9508e67b1894f0ddc69e888a117fcd9e8b787b1c98ce91249e573543434a7e5c.jpg)

![beacb7596a6819e0dfed5a770995b24819fffa8df246b723332f8be93a80d59b.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/tables/beacb7596a6819e0dfed5a770995b24819fffa8df246b723332f8be93a80d59b.jpg)

![bf40d154a6728c58c032d354b3492a957b7b074eecfa11255594f41317a81841.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/tables/bf40d154a6728c58c032d354b3492a957b7b074eecfa11255594f41317a81841.jpg)

![d47ffa9859cc5576802620f5c8a7e194b882401a75407273d2a3dc76a096d714.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/tables/d47ffa9859cc5576802620f5c8a7e194b882401a75407273d2a3dc76a096d714.jpg)

![d66f66440ea44136ea41312b340f22324746c68d40e24a2bff5d49221fbae8de.jpg](../nips_results/4521_Towards%20Understanding%20Safety%20Alignment_%20A%20Mechanistic%20Perspective%20from%20Safety%20Neurons/tables/d66f66440ea44136ea41312b340f22324746c68d40e24a2bff5d49221fbae8de.jpg)

## Why 1 + 1 < 1 in Visual Token Pruning: Beyond Naive Integration via Multi-Objective Balanced Covering


### Images

![21e4bb8ea41c19e3efea3a029d8605b2104e435fe210ed50aee2ff088f2451a6.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/21e4bb8ea41c19e3efea3a029d8605b2104e435fe210ed50aee2ff088f2451a6.jpg)

![2d61aba85d34396987f3e78618c1c8fe5cd9695050c2c4ccf009420ecedd2bd8.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/2d61aba85d34396987f3e78618c1c8fe5cd9695050c2c4ccf009420ecedd2bd8.jpg)

![31c6a693cac64a9d2e8c46825a90db2a785b7fa94ac59131f916774bd63676b6.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/31c6a693cac64a9d2e8c46825a90db2a785b7fa94ac59131f916774bd63676b6.jpg)

![4599dd292ec935ccdc67e0070811a6e28b79908c1ab01cc7340484d8aefc3e32.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/4599dd292ec935ccdc67e0070811a6e28b79908c1ab01cc7340484d8aefc3e32.jpg)

![54ad36ecc2d2fdd514d5045c32696db867bbceabd4ff916cdff99cbb09a5b0af.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/54ad36ecc2d2fdd514d5045c32696db867bbceabd4ff916cdff99cbb09a5b0af.jpg)

![5acf8a2f77ce1cf1e69c5726f1f061d7bcf3c4cf6c67792bb4b1d85096084f88.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/5acf8a2f77ce1cf1e69c5726f1f061d7bcf3c4cf6c67792bb4b1d85096084f88.jpg)

![60d4bae207f0e86554ca61ef9adcb77a06259526b189e07fba9d267796dcc989.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/60d4bae207f0e86554ca61ef9adcb77a06259526b189e07fba9d267796dcc989.jpg)

![938e13c007844db9e5aa06e3bacb36b6e490b7499c0554c2fa94d43a392e5454.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/938e13c007844db9e5aa06e3bacb36b6e490b7499c0554c2fa94d43a392e5454.jpg)

![ac95fe829fe3344751af795aab1b9262625263a0da34e3070fcc60317afcc4f9.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/ac95fe829fe3344751af795aab1b9262625263a0da34e3070fcc60317afcc4f9.jpg)

![d93d6f42fdd3ae13f0b451b827d6572e0c11e99adca1abaa12d9b06f91af7213.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/d93d6f42fdd3ae13f0b451b827d6572e0c11e99adca1abaa12d9b06f91af7213.jpg)

![e847f88d29d9d4c78c9ebf91f0669c09e569e7aeecf2051001b8bea9d12c3db2.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/e847f88d29d9d4c78c9ebf91f0669c09e569e7aeecf2051001b8bea9d12c3db2.jpg)

![ea048762c0b6969f4d9b99761bbeca9241808263df6beed4833388187fad4ed2.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/ea048762c0b6969f4d9b99761bbeca9241808263df6beed4833388187fad4ed2.jpg)

![fea76b594254d168ccdad3e925142d04b6a90086eaaec9f8173305a857ba60af.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/images/fea76b594254d168ccdad3e925142d04b6a90086eaaec9f8173305a857ba60af.jpg)

### Tables

![011907f798ef7a9e6c3f077026d15fa00c368354c4f9381b2374da06a80a120e.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/tables/011907f798ef7a9e6c3f077026d15fa00c368354c4f9381b2374da06a80a120e.jpg)

![18d4bb32e9df28982fa5a585fd5a2c9f3ea2937fa721f182a6c5db91de53bc9d.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/tables/18d4bb32e9df28982fa5a585fd5a2c9f3ea2937fa721f182a6c5db91de53bc9d.jpg)

![35156e13428e2995ae82aaf0777d63b36f63dc5833e8ff35b8a304c90bedbf0b.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/tables/35156e13428e2995ae82aaf0777d63b36f63dc5833e8ff35b8a304c90bedbf0b.jpg)

![3a97f5602aa9009b08882af7a9f21961d50e12badf7aa2cb5c3f7af0cf8cadde.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/tables/3a97f5602aa9009b08882af7a9f21961d50e12badf7aa2cb5c3f7af0cf8cadde.jpg)

![4687ca49f1225e735faa558acf9e49c3f317c2946e9da70305a58a7f739d77d3.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/tables/4687ca49f1225e735faa558acf9e49c3f317c2946e9da70305a58a7f739d77d3.jpg)

![6cde2b71ba7a81a78bb57bd959570999936664fcb3ccb05a180ae7af0b26dfac.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/tables/6cde2b71ba7a81a78bb57bd959570999936664fcb3ccb05a180ae7af0b26dfac.jpg)

![cf391e51a288f3a0eb4954b66716f2c2d8742356ef6aa1328d7e2317039553ea.jpg](../nips_results/4522_Why%201%20%2B%201%20_%201%20in%20Visual%20Token%20Pruning_%20Beyond%20Naive%20Integration%20via%20Multi-Objective%20Balanced%20Coverin/tables/cf391e51a288f3a0eb4954b66716f2c2d8742356ef6aa1328d7e2317039553ea.jpg)

## Competitive Advantage Attacks to Decentralized Federated Learning


### Images

![0177af9f5430f8cd685e00867c30b3caf94be80800f9454d06e762c9d7b09d63.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/images/0177af9f5430f8cd685e00867c30b3caf94be80800f9454d06e762c9d7b09d63.jpg)

![1272ea06454fd07d281dfc644f6a75f5f613c196c8f4da268d57872574e0b4c3.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/images/1272ea06454fd07d281dfc644f6a75f5f613c196c8f4da268d57872574e0b4c3.jpg)

![48e37384a903e6352bfe006f0c3e4dc9835edebc220a5ebab2523b89817dfb81.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/images/48e37384a903e6352bfe006f0c3e4dc9835edebc220a5ebab2523b89817dfb81.jpg)

![bc7d0befa9d8e899d50dbe5391a50658210e376d94962bd185e30eab07d27786.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/images/bc7d0befa9d8e899d50dbe5391a50658210e376d94962bd185e30eab07d27786.jpg)

![ea63a9467c8d8b337474f788127d073dabb48d6b8fdaec6d585b8050c2212f9d.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/images/ea63a9467c8d8b337474f788127d073dabb48d6b8fdaec6d585b8050c2212f9d.jpg)

![ee178baf7375ecb2281a2a6c5b829f3d389d536fbb0ebd046c1590bc1b83f560.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/images/ee178baf7375ecb2281a2a6c5b829f3d389d536fbb0ebd046c1590bc1b83f560.jpg)

### Tables

![008c19e074ca0bcd14ed68710355f3bd5de131b317f64336aa6b90e0c69508ec.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/008c19e074ca0bcd14ed68710355f3bd5de131b317f64336aa6b90e0c69508ec.jpg)

![02cf41607bd36b44dd09ad933a10e048748775d0d8f54fe172052526caee57c7.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/02cf41607bd36b44dd09ad933a10e048748775d0d8f54fe172052526caee57c7.jpg)

![2049a2212ea1f7ea9916308b789ae28b6724e4da384df1ed4732601fcb8b4f1c.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/2049a2212ea1f7ea9916308b789ae28b6724e4da384df1ed4732601fcb8b4f1c.jpg)

![3d85b8ab47a10c80fcaa1929791e0928a6de59859c36d0156c44c84b56c20f94.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/3d85b8ab47a10c80fcaa1929791e0928a6de59859c36d0156c44c84b56c20f94.jpg)

![48bc81594b0b883803fafb3055464a89799d5c204fbb9fe557777682cdaf1891.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/48bc81594b0b883803fafb3055464a89799d5c204fbb9fe557777682cdaf1891.jpg)

![5880a34ae33d457c23eff0a052bb288ecb82c9a3b09a5d32146f845cb5ce6589.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/5880a34ae33d457c23eff0a052bb288ecb82c9a3b09a5d32146f845cb5ce6589.jpg)

![64d3022edf91adc3f22b23ef8524e2b9fca973c74b907307d506c7eee260848b.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/64d3022edf91adc3f22b23ef8524e2b9fca973c74b907307d506c7eee260848b.jpg)

![66078d4ccd713b2a2a4d664df8dc1ed9d73f21c158f075eebc7152856a3fac3b.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/66078d4ccd713b2a2a4d664df8dc1ed9d73f21c158f075eebc7152856a3fac3b.jpg)

![b1ab87fc75f925810a13a55f8b0194a8c76ede5112b09fa492ea0e235bf6292c.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/b1ab87fc75f925810a13a55f8b0194a8c76ede5112b09fa492ea0e235bf6292c.jpg)

![b7660ce4e7bf613349fc7e7b098bb2da0fd24b0b3b3bb786182fd52a193a828d.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/b7660ce4e7bf613349fc7e7b098bb2da0fd24b0b3b3bb786182fd52a193a828d.jpg)

![e9134cda4631ebe23a83f67fccbd0d75eaf39c07dd123af4a150024cdf771680.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/e9134cda4631ebe23a83f67fccbd0d75eaf39c07dd123af4a150024cdf771680.jpg)

![f7cdc0d6923ecc9e4ac55481db62cfbabce3ac603d3df5d5ad3550befe74556f.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/f7cdc0d6923ecc9e4ac55481db62cfbabce3ac603d3df5d5ad3550befe74556f.jpg)

![fa21f591d9789c78e5ab4f7eddfd1bf7e902f45737c323d79f050d4fb3ab0118.jpg](../nips_results/4523_Competitive%20Advantage%20Attacks%20to%20Decentralized%20Federated%20Learning/tables/fa21f591d9789c78e5ab4f7eddfd1bf7e902f45737c323d79f050d4fb3ab0118.jpg)

## Exploration from a Primal-Dual Lens: Value-Incentivized Actor-Critic Methods for Sample-Efficient Online RL


### Images

![4906d97c2e263ce3bf4314c4d9efa6f03a05d61cc166a6723da05ccdd960f5a6.jpg](../nips_results/4524_Exploration%20from%20a%20Primal-Dual%20Lens_%20Value-Incentivized%20Actor-Critic%20Methods%20for%20Sample-Efficient%20On/images/4906d97c2e263ce3bf4314c4d9efa6f03a05d61cc166a6723da05ccdd960f5a6.jpg)

![57bb903760e98944f38dbc56ebeb81862995e654c97cc63d9b771b6d25b97ccc.jpg](../nips_results/4524_Exploration%20from%20a%20Primal-Dual%20Lens_%20Value-Incentivized%20Actor-Critic%20Methods%20for%20Sample-Efficient%20On/images/57bb903760e98944f38dbc56ebeb81862995e654c97cc63d9b771b6d25b97ccc.jpg)

## PRESCRIBE: Predicting Single-Cell Responses with Bayesian Estimation


### Images

![2455fa8c59f152372c4a45e2758bcd182dc961401ebd48769d6016b382afb4fe.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/images/2455fa8c59f152372c4a45e2758bcd182dc961401ebd48769d6016b382afb4fe.jpg)

![b9aa5039e970b6fb3d5d78d17756116134d991d8254bbb832ef3981cdb53348b.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/images/b9aa5039e970b6fb3d5d78d17756116134d991d8254bbb832ef3981cdb53348b.jpg)

![be2a37f7723663359ca14782e0ec0982ffad2684a79ab621e127277b0ea3e5a7.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/images/be2a37f7723663359ca14782e0ec0982ffad2684a79ab621e127277b0ea3e5a7.jpg)

![beddf41ba6cf177ec8967ed606deecf8e3d08c23cc3733308f6ac26ce9391e4d.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/images/beddf41ba6cf177ec8967ed606deecf8e3d08c23cc3733308f6ac26ce9391e4d.jpg)

![dd48a3415b2a872e8634b7c5ff69c9257dc45c7d8d37b0be6f12b87c18b1d3b1.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/images/dd48a3415b2a872e8634b7c5ff69c9257dc45c7d8d37b0be6f12b87c18b1d3b1.jpg)

### Tables

![1dbbda00234e18f337f89f2eb2ac929b3772848470d4acf4f54f394dd80636df.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/tables/1dbbda00234e18f337f89f2eb2ac929b3772848470d4acf4f54f394dd80636df.jpg)

![3bfe232f564ab31071470a1825581888597fe49015f0fa19fe1252556767cedd.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/tables/3bfe232f564ab31071470a1825581888597fe49015f0fa19fe1252556767cedd.jpg)

![52708494f79639374d9705bd0f5fd7346aae03d92204599b817cb5fc941b5e43.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/tables/52708494f79639374d9705bd0f5fd7346aae03d92204599b817cb5fc941b5e43.jpg)

![64a20cd05fc2906590ea0511e074aa466974cebdd2243d1e4b06fbf8c4b4e725.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/tables/64a20cd05fc2906590ea0511e074aa466974cebdd2243d1e4b06fbf8c4b4e725.jpg)

![8c50ac3196c12a756e4fc63fa5ea6a6af8a8112763691f05296c28d6f61da069.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/tables/8c50ac3196c12a756e4fc63fa5ea6a6af8a8112763691f05296c28d6f61da069.jpg)

![99032d343ae7626b429c94963e0d2d423b56cb89bc43a3ac28b3389aa53a06b1.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/tables/99032d343ae7626b429c94963e0d2d423b56cb89bc43a3ac28b3389aa53a06b1.jpg)

![abc1acdd2a7aeb6d89e97d3aa527c21fef1e7035a94fbeb2df4f9ab1db466c70.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/tables/abc1acdd2a7aeb6d89e97d3aa527c21fef1e7035a94fbeb2df4f9ab1db466c70.jpg)

![fa74764e8ce775c11998226eacf396f6d0b6ccbab4750e1303009eb690443dcb.jpg](../nips_results/4525_PRESCRIBE_%20Predicting%20Single-Cell%20Responses%20with%20Bayesian%20Estimation/tables/fa74764e8ce775c11998226eacf396f6d0b6ccbab4750e1303009eb690443dcb.jpg)

## Robust Distributed Estimation: Extending Gossip Algorithms to Ranking and Trimmed Means


### Images

![373aed95f916d0254d412251c8a313618a578dc0cd7aeed7f9f3e3e163887eac.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/images/373aed95f916d0254d412251c8a313618a578dc0cd7aeed7f9f3e3e163887eac.jpg)

![5b1a2e7bbfd881143b9a4ac7a20a74cfcd61e642d3c4b691ae3a6afa10cf8af8.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/images/5b1a2e7bbfd881143b9a4ac7a20a74cfcd61e642d3c4b691ae3a6afa10cf8af8.jpg)

![6a60ac8413790c6009c01715ac00b381043686c8b012fbeee6d8651f7601e0d3.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/images/6a60ac8413790c6009c01715ac00b381043686c8b012fbeee6d8651f7601e0d3.jpg)

![7a3e4a24b5a0580ed87bd8e2859b9c626bb34f24e4fe3a32909b3ae17a5bedd9.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/images/7a3e4a24b5a0580ed87bd8e2859b9c626bb34f24e4fe3a32909b3ae17a5bedd9.jpg)

![8406d1ccc7839a452d2370381001ec674877197ac5b3905030290aa9473fc3e0.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/images/8406d1ccc7839a452d2370381001ec674877197ac5b3905030290aa9473fc3e0.jpg)

![854260eae7b9fe67a8fd92ad003c752bfe663deff16a7118ff790c6edb3c340a.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/images/854260eae7b9fe67a8fd92ad003c752bfe663deff16a7118ff790c6edb3c340a.jpg)

![d49b503ffb4f9c580829004edec650c1230a5db8eafa17a27651ab58a6a324a3.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/images/d49b503ffb4f9c580829004edec650c1230a5db8eafa17a27651ab58a6a324a3.jpg)

![e0a4d79c570e6621451d1ee323a3d32a834b9c6075c439f5904324da7fd5a0d4.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/images/e0a4d79c570e6621451d1ee323a3d32a834b9c6075c439f5904324da7fd5a0d4.jpg)

![f544b04425c6fafcac3ef86cca303ee35c38ee7d329bd54cad06b610c88f28b8.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/images/f544b04425c6fafcac3ef86cca303ee35c38ee7d329bd54cad06b610c88f28b8.jpg)

![fb0215ae6eaa07ea6e40565bd3e3df05f4b4c78dac27bca2ab8d145dce626db7.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/images/fb0215ae6eaa07ea6e40565bd3e3df05f4b4c78dac27bca2ab8d145dce626db7.jpg)

### Tables

![923abaea3f87138c32b2430cde3f39aa02d5043d1c8037d45a9d3ef1e56f016d.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/tables/923abaea3f87138c32b2430cde3f39aa02d5043d1c8037d45a9d3ef1e56f016d.jpg)

![dcd8111a6487081570d1abeb8f6e596835f3ac69cb11d3234c58e32205d52d34.jpg](../nips_results/4526_Robust%20Distributed%20Estimation_%20Extending%20Gossip%20Algorithms%20to%20Ranking%20and%20Trimmed%20Means/tables/dcd8111a6487081570d1abeb8f6e596835f3ac69cb11d3234c58e32205d52d34.jpg)

## SPRO: Improving Image Generation via Self-Play


### Images

![01ac7ad2868c24bdbd54a7ecabe1413f72cd919625a24d2489fd7b5fb168f630.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/01ac7ad2868c24bdbd54a7ecabe1413f72cd919625a24d2489fd7b5fb168f630.jpg)

![07f3d9e7f362144143a5e7e1a9745d64ad2e7bb94ec2fc0fce44f0e5af931439.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/07f3d9e7f362144143a5e7e1a9745d64ad2e7bb94ec2fc0fce44f0e5af931439.jpg)

![099803684c4c3c2b3d6d110face86091db633d7a87b5753e5eb27cee2d7fb626.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/099803684c4c3c2b3d6d110face86091db633d7a87b5753e5eb27cee2d7fb626.jpg)

![0f8c150315cce1c62a0efd05ed4eb044f61915eb99ebe05eda41f1cc34e4ba6d.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/0f8c150315cce1c62a0efd05ed4eb044f61915eb99ebe05eda41f1cc34e4ba6d.jpg)

![108acb2c55819af26fbb22527dc08fd9182efee66fef8356982beeaf7040f63b.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/108acb2c55819af26fbb22527dc08fd9182efee66fef8356982beeaf7040f63b.jpg)

![259fac4cf40ad4f8d3977d0053f557d48fb9c0a49d31e20693017b040bb3adfd.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/259fac4cf40ad4f8d3977d0053f557d48fb9c0a49d31e20693017b040bb3adfd.jpg)

![2876dcbc2a81f7d77b623c1b67767a317a9f247a07c0fd4e821c45aace7dd85c.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/2876dcbc2a81f7d77b623c1b67767a317a9f247a07c0fd4e821c45aace7dd85c.jpg)

![2f11adbc984bb47eb555752339f94c46587e365db90835d57410df7d6de76b19.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/2f11adbc984bb47eb555752339f94c46587e365db90835d57410df7d6de76b19.jpg)

![33ce3b4bc3ffa89a0d0e27022e50fccffd55a55738cf95f5c727a709db9c837c.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/33ce3b4bc3ffa89a0d0e27022e50fccffd55a55738cf95f5c727a709db9c837c.jpg)

![418914e691b4351137e912d7e2cb17bf6bb09e5f22d154952ccebd15749ea9fb.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/418914e691b4351137e912d7e2cb17bf6bb09e5f22d154952ccebd15749ea9fb.jpg)

![50c65dffee6b3a8f6e9359288b9b66886349a575b8a997c4dce7fe383169cddb.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/50c65dffee6b3a8f6e9359288b9b66886349a575b8a997c4dce7fe383169cddb.jpg)

![63ce1e15f652e9df3cb8a381d8994537eeb456c7c7bc3c9cd3d4f7c5da361a1e.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/63ce1e15f652e9df3cb8a381d8994537eeb456c7c7bc3c9cd3d4f7c5da361a1e.jpg)

![6f3cf5fd55e656bbb842e3c10894c94d42b6e3aff337a621acfadbdcb13b722d.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/6f3cf5fd55e656bbb842e3c10894c94d42b6e3aff337a621acfadbdcb13b722d.jpg)

![7553aeddc5a7ae30b1f8f09b8be0515fd4ea31492a3b2b06b5150eda4486629a.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/7553aeddc5a7ae30b1f8f09b8be0515fd4ea31492a3b2b06b5150eda4486629a.jpg)

![81fe8c3a913a7a0689f84b92a7350010eba094950ae8e2201e98b673b83ecc8c.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/81fe8c3a913a7a0689f84b92a7350010eba094950ae8e2201e98b673b83ecc8c.jpg)

![840888df50d8d285407cd2b0aa5c2eb9321183a1930e3ed50d92760f8c099e84.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/840888df50d8d285407cd2b0aa5c2eb9321183a1930e3ed50d92760f8c099e84.jpg)

![89fac9377d131a372333e93e35b66743bd7cf6fb128a7f4667f1f194e53e368e.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/89fac9377d131a372333e93e35b66743bd7cf6fb128a7f4667f1f194e53e368e.jpg)

![9259cc66866e65560657e7524ec139a93a7f1d792a9bc1d3aaa94f91d8d7191b.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/9259cc66866e65560657e7524ec139a93a7f1d792a9bc1d3aaa94f91d8d7191b.jpg)

![a22d4150dce117968d075be248d660dc751576cc8bbcbe2f100c06db32b9c3b0.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/a22d4150dce117968d075be248d660dc751576cc8bbcbe2f100c06db32b9c3b0.jpg)

![a78e4bfed1ffac5688fd1785eedc7acc8d177b58b3fbc57c9b8e0494e4360ff7.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/a78e4bfed1ffac5688fd1785eedc7acc8d177b58b3fbc57c9b8e0494e4360ff7.jpg)

![a9aa9e71e53e0a2dd0db02395bcdb83478ebf342d6ffd9fd64a8788e44086cf2.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/a9aa9e71e53e0a2dd0db02395bcdb83478ebf342d6ffd9fd64a8788e44086cf2.jpg)

![b88618f33d9f280488a1a26008151a5280f69cecf5c932371fd5fd7f836267f6.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/b88618f33d9f280488a1a26008151a5280f69cecf5c932371fd5fd7f836267f6.jpg)

![bb25a0384c1d884d560c21e8d400fd6e906e521caa3fe3ede68e0dee67bd8a4c.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/bb25a0384c1d884d560c21e8d400fd6e906e521caa3fe3ede68e0dee67bd8a4c.jpg)

![bbe9bda536df51e5311494c0855a308e89f781730541bf7eb42c75fb20b7eb26.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/bbe9bda536df51e5311494c0855a308e89f781730541bf7eb42c75fb20b7eb26.jpg)

![c04cf92c487e8e3a591c1cb16043839bc8f60e1110963ff4315529d54cbb2ae2.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/c04cf92c487e8e3a591c1cb16043839bc8f60e1110963ff4315529d54cbb2ae2.jpg)

![c383b2c3d07a5f36a4702cb66630d64823dc17253f22baa5d79f18ce855115fe.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/c383b2c3d07a5f36a4702cb66630d64823dc17253f22baa5d79f18ce855115fe.jpg)

![c4b67306f22aa49286dc6544181342747bb9a546fefd383fe509303e0ccba5d0.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/c4b67306f22aa49286dc6544181342747bb9a546fefd383fe509303e0ccba5d0.jpg)

![d4ba0d95c793aa7cef2a3041222d8f9b4b04120f92f653a12c8781c0e1b82b44.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/d4ba0d95c793aa7cef2a3041222d8f9b4b04120f92f653a12c8781c0e1b82b44.jpg)

![d605a068d64b3b381cd6c810367500d28ee47f1fbf0ba3a63727ba02476eb16c.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/d605a068d64b3b381cd6c810367500d28ee47f1fbf0ba3a63727ba02476eb16c.jpg)

![eb5944df590b7e919c5aa822b6094a2395e06c49324a0bcd27afab0751e158be.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/eb5944df590b7e919c5aa822b6094a2395e06c49324a0bcd27afab0751e158be.jpg)

![f51a351835fc6d7122bd90fd12b978d678b11ab99d192a206e9dc44a2cb99dcd.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/f51a351835fc6d7122bd90fd12b978d678b11ab99d192a206e9dc44a2cb99dcd.jpg)

![ffb78d00a45b46a1932a056d661984e811b9ceaa818b98716c7dc3c4e6bb2e0a.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/images/ffb78d00a45b46a1932a056d661984e811b9ceaa818b98716c7dc3c4e6bb2e0a.jpg)

### Tables

![006a58a1951af397c929f69052beb067fd4d0f1316ffa7a27425d7a15576a74b.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/006a58a1951af397c929f69052beb067fd4d0f1316ffa7a27425d7a15576a74b.jpg)

![08066fd513a97f402713765663436f6a66001d583f2d73fbe0af12e18b08989f.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/08066fd513a97f402713765663436f6a66001d583f2d73fbe0af12e18b08989f.jpg)

![1712c553022cac7d9838dbe13f38a4cfcb6f7b9a42e3c35e173d7a9b40806d23.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/1712c553022cac7d9838dbe13f38a4cfcb6f7b9a42e3c35e173d7a9b40806d23.jpg)

![2485eb029b2f5ef8b7bb4c552ef463df35b0c5d0c7ef8bf4fbcc435a971f102e.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/2485eb029b2f5ef8b7bb4c552ef463df35b0c5d0c7ef8bf4fbcc435a971f102e.jpg)

![274f60859093bc2913d15eabe585553adbf039e0c532e982f2c6c5754148397e.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/274f60859093bc2913d15eabe585553adbf039e0c532e982f2c6c5754148397e.jpg)

![31b993d03a99ef33a6a65fd58d57ce77f557d293a33ccb1cb697d90b8a505719.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/31b993d03a99ef33a6a65fd58d57ce77f557d293a33ccb1cb697d90b8a505719.jpg)

![3c71e7be8ac2c53c8f6bae6cc9c8d6a553cfbbc0d57cff32e808a1b4aa58a17b.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/3c71e7be8ac2c53c8f6bae6cc9c8d6a553cfbbc0d57cff32e808a1b4aa58a17b.jpg)

![51608432aa3102729ebc0f7fa9f614fc980b7802578ef04f704a0efcf7837153.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/51608432aa3102729ebc0f7fa9f614fc980b7802578ef04f704a0efcf7837153.jpg)

![6946f5e7729140de73d34cb8b4bc02816acd8b4765af6749ed849a5ccd5bb394.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/6946f5e7729140de73d34cb8b4bc02816acd8b4765af6749ed849a5ccd5bb394.jpg)

![76ab47331866cc8702d200d83b165ed87d8a6a71c0d37ce48f82be9ebddf2f27.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/76ab47331866cc8702d200d83b165ed87d8a6a71c0d37ce48f82be9ebddf2f27.jpg)

![81dd6bba169907ff02ff374ed2fc1d6d4fff7475220ae8c4d44a8c9ed7da500e.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/81dd6bba169907ff02ff374ed2fc1d6d4fff7475220ae8c4d44a8c9ed7da500e.jpg)

![863615269c15ecdb685e7b3bebbc90d53a234adc7b4a7b6174b521eb2cf60866.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/863615269c15ecdb685e7b3bebbc90d53a234adc7b4a7b6174b521eb2cf60866.jpg)

![a3e0ace284c50a2a9a043c5709fd4ad938cc6d63977690315ebf3a8ca17846bf.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/a3e0ace284c50a2a9a043c5709fd4ad938cc6d63977690315ebf3a8ca17846bf.jpg)

![a56d85b54e0417b330ec51bee4f9ab2578eef4faaa5f68dc7f1d7a756de9dc4b.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/a56d85b54e0417b330ec51bee4f9ab2578eef4faaa5f68dc7f1d7a756de9dc4b.jpg)

![a633864338f5c5a46334b9c89e78263c5e0be0abd8207b26c2d21004fc1b25f3.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/a633864338f5c5a46334b9c89e78263c5e0be0abd8207b26c2d21004fc1b25f3.jpg)

![c6579dac51cfcfe5edfcbf4e0ff550823eeb2c92d2585bd087155bb89cb73c9c.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/c6579dac51cfcfe5edfcbf4e0ff550823eeb2c92d2585bd087155bb89cb73c9c.jpg)

![ce69e0ebcdc272018d323f0c7af41aae9490055297a00d61cd3c5e09f3b7a891.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/ce69e0ebcdc272018d323f0c7af41aae9490055297a00d61cd3c5e09f3b7a891.jpg)

![dbc17d2c0a51266208d5696fcf6b2d241a0cc986d9efccd42173036547eb9f03.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/dbc17d2c0a51266208d5696fcf6b2d241a0cc986d9efccd42173036547eb9f03.jpg)

![e0d8b2039ed233aa3b7440dc7fd337ca246e85d7e15e2c100565aab025abe925.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/e0d8b2039ed233aa3b7440dc7fd337ca246e85d7e15e2c100565aab025abe925.jpg)

![ecccfa7bff638ddac7b68690caad181e6314dd00aea4122ed967033cac286252.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/ecccfa7bff638ddac7b68690caad181e6314dd00aea4122ed967033cac286252.jpg)

![f20ca286454bc948c1399859754b38fa592f39c54f7cef6295fa5c4f243ca73b.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/f20ca286454bc948c1399859754b38fa592f39c54f7cef6295fa5c4f243ca73b.jpg)

![f76e4ae3fe19a55998cc57136bc8a0a9286ab8ff937faf6e447e2b10a6f3ec16.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/f76e4ae3fe19a55998cc57136bc8a0a9286ab8ff937faf6e447e2b10a6f3ec16.jpg)

![f94f2c1f1cdf9510bf58a91898b4d4953a02bb281c3f9362e1c9a354322e5df6.jpg](../nips_results/4527_SPRO_%20Improving%20Image%20Generation%20via%20Self-Play/tables/f94f2c1f1cdf9510bf58a91898b4d4953a02bb281c3f9362e1c9a354322e5df6.jpg)

## Thumb on the Scale: Optimal Loss Weighting in Last Layer Retraining


### Images

![2447c26f388b358d56537c1439e24cbc0fd8ceaeb2450da9441fa02f2aaac5fd.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/2447c26f388b358d56537c1439e24cbc0fd8ceaeb2450da9441fa02f2aaac5fd.jpg)

![259b44e464cbb46cd93bcc67f8f3a9d54bf41b34d2ee3dc63c0644a311ebda7a.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/259b44e464cbb46cd93bcc67f8f3a9d54bf41b34d2ee3dc63c0644a311ebda7a.jpg)

![291fe88e183e354b1b82aa4feb75fa566e20fcd691003c50749a0b3ab32b249a.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/291fe88e183e354b1b82aa4feb75fa566e20fcd691003c50749a0b3ab32b249a.jpg)

![40df4f40f9f62b755a50677950ad8de546fa2bfc79e373913103f40dd2365e54.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/40df4f40f9f62b755a50677950ad8de546fa2bfc79e373913103f40dd2365e54.jpg)

![58519e65ed2874b232ff7effc2c7beab89eb3b189661138bf0a49c4e0e982c36.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/58519e65ed2874b232ff7effc2c7beab89eb3b189661138bf0a49c4e0e982c36.jpg)

![73a3450d1c02f52b9cbdb39c51d80591745e3cdd8e6fc3675048d2a4b880289a.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/73a3450d1c02f52b9cbdb39c51d80591745e3cdd8e6fc3675048d2a4b880289a.jpg)

![880a168a76527963a2a3accca47ca8858a11cbb9543b7bab7323552360f364ce.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/880a168a76527963a2a3accca47ca8858a11cbb9543b7bab7323552360f364ce.jpg)

![9f4eb9cc00986e1439f8fe3a5be7d8daef3e80e03cbcf5176879058c5e457475.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/9f4eb9cc00986e1439f8fe3a5be7d8daef3e80e03cbcf5176879058c5e457475.jpg)

![a347985579a6a265018f2535231e8817176b7cc6025bc2d5e24a57e46979b2b5.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/a347985579a6a265018f2535231e8817176b7cc6025bc2d5e24a57e46979b2b5.jpg)

![c30202616d3f1a17f82d56243181d5ecf15fa80972c9cd361ec379261b4ee32f.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/c30202616d3f1a17f82d56243181d5ecf15fa80972c9cd361ec379261b4ee32f.jpg)

![c77fb93acab28ecf2b1cd83dd55062f59b207e8bdbfe313bcf8751a93ce19043.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/c77fb93acab28ecf2b1cd83dd55062f59b207e8bdbfe313bcf8751a93ce19043.jpg)

![d483178306c1d95642f5776a95f782e5cf7738ed51af5c456071e278d5811538.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/images/d483178306c1d95642f5776a95f782e5cf7738ed51af5c456071e278d5811538.jpg)

### Tables

![6609ff884a84f70590fd1007ce08fd28eeffd4ebc48abd61be1f13de29f2dad7.jpg](../nips_results/4528_Thumb%20on%20the%20Scale_%20Optimal%20Loss%20Weighting%20in%20Last%20Layer%20Retraining/tables/6609ff884a84f70590fd1007ce08fd28eeffd4ebc48abd61be1f13de29f2dad7.jpg)

## PLEIADES: Building Temporal Kernels with Orthogonal Polynomials


### Images

![0836d30a37697aac5b9133f1c92b739813e2e14278e7638cf38a9db2014ee7b5.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/images/0836d30a37697aac5b9133f1c92b739813e2e14278e7638cf38a9db2014ee7b5.jpg)

![1787ba413704ab00d6d59cdde5ee011050330a5809d0217d1d012c581f955aad.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/images/1787ba413704ab00d6d59cdde5ee011050330a5809d0217d1d012c581f955aad.jpg)

![473e87f95e45b6e4b2a9fdf21b074c258432566f4cc7aa11031f7114b0e915f7.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/images/473e87f95e45b6e4b2a9fdf21b074c258432566f4cc7aa11031f7114b0e915f7.jpg)

### Tables

![05ccb0679db0223fe55452aa751765cfe70aa0d21c91ccdd210e6f5684b20836.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/tables/05ccb0679db0223fe55452aa751765cfe70aa0d21c91ccdd210e6f5684b20836.jpg)

![4d3453912566bbff1a095682d3f27224dbd3d6865b11a39de6fb420fb1ec120e.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/tables/4d3453912566bbff1a095682d3f27224dbd3d6865b11a39de6fb420fb1ec120e.jpg)

![550cfff79490f8addfd556507c058605d78bd2d664662b456d3684ee1d0b7853.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/tables/550cfff79490f8addfd556507c058605d78bd2d664662b456d3684ee1d0b7853.jpg)

![9edb9a379bc93fb28d51a86ea04e8c5a827a0f7954c4e3f71d62e4e9fc77e5ef.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/tables/9edb9a379bc93fb28d51a86ea04e8c5a827a0f7954c4e3f71d62e4e9fc77e5ef.jpg)

![ac96d63535f6d1b8d416614de01a7d95bb8bd6aeb6652100cf0e0812ebc391ca.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/tables/ac96d63535f6d1b8d416614de01a7d95bb8bd6aeb6652100cf0e0812ebc391ca.jpg)

![b43b516c0e9d45725a12b152395dd123a964d348d1e8aa75929c02400dcc2095.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/tables/b43b516c0e9d45725a12b152395dd123a964d348d1e8aa75929c02400dcc2095.jpg)

![dfe014d9a5a74247edf13642c21a21a81a6e4cb2c4ebf13a868ffd077d805a0b.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/tables/dfe014d9a5a74247edf13642c21a21a81a6e4cb2c4ebf13a868ffd077d805a0b.jpg)

![ec680b5a56b3a8b18156ad39415870d7306ca79d18eec92168bad3637e064d68.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/tables/ec680b5a56b3a8b18156ad39415870d7306ca79d18eec92168bad3637e064d68.jpg)

![f2f1d393537a07ceddf3ccd69ef1eda1e6d5a79cd3a6452148e45bebfb88fb3d.jpg](../nips_results/4529_PLEIADES_%20Building%20Temporal%20Kernels%20with%20Orthogonal%20Polynomials/tables/f2f1d393537a07ceddf3ccd69ef1eda1e6d5a79cd3a6452148e45bebfb88fb3d.jpg)

## Forging Time Series with Language: A Large Language Model Approach to Synthetic Data Generation


### Images

![1a36de86f6562f0d4dbbf8fb70bd3644ce0e9ae054678918692c4662c7c473b5.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/images/1a36de86f6562f0d4dbbf8fb70bd3644ce0e9ae054678918692c4662c7c473b5.jpg)

![89e2f87ce6d4e49696d7b7b25ff813a68376e9b1eddcbf4bbe1961f6eafa6f9a.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/images/89e2f87ce6d4e49696d7b7b25ff813a68376e9b1eddcbf4bbe1961f6eafa6f9a.jpg)

![c4e39bdddf2b2960997373d2f502029e9bc6b1fad7f0c0903d8b29b8ef4e4f10.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/images/c4e39bdddf2b2960997373d2f502029e9bc6b1fad7f0c0903d8b29b8ef4e4f10.jpg)

### Tables

![0d608e6c166efd383c49fcbf7ad082743939382ecee765ade2728ad0e65fcdbd.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/0d608e6c166efd383c49fcbf7ad082743939382ecee765ade2728ad0e65fcdbd.jpg)

![141a4ee4be2c582cb64cfc047e7dca9a97e9262f68cad6611cc33471a11ed8bf.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/141a4ee4be2c582cb64cfc047e7dca9a97e9262f68cad6611cc33471a11ed8bf.jpg)

![2164585b91e945ea5d939a1f96a867e662c405a60deb8ee4dfb282c54d467857.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/2164585b91e945ea5d939a1f96a867e662c405a60deb8ee4dfb282c54d467857.jpg)

![29ce09b895ffcb33f819400c4c728082f0ceb2b2a4f4010dce45c08a3588ebfd.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/29ce09b895ffcb33f819400c4c728082f0ceb2b2a4f4010dce45c08a3588ebfd.jpg)

![2df2b90cdc9ae4ca2c5de62be0c7e81b736b9e6bbaffcb4954542805aa6ccf74.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/2df2b90cdc9ae4ca2c5de62be0c7e81b736b9e6bbaffcb4954542805aa6ccf74.jpg)

![3121115e5abadb833ec01acb22fc1a6f1254d245dd5ce4778a6dc229d99f28cf.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/3121115e5abadb833ec01acb22fc1a6f1254d245dd5ce4778a6dc229d99f28cf.jpg)

![57c821e627442febde57635f4c3495122f82abda6b9203be31441591f70c537b.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/57c821e627442febde57635f4c3495122f82abda6b9203be31441591f70c537b.jpg)

![9901d185b481f57b6cf7ae2a055b28ae628708d0b56a78e49ef39ffe999f940d.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/9901d185b481f57b6cf7ae2a055b28ae628708d0b56a78e49ef39ffe999f940d.jpg)

![ab431bb436946356d0964e8a7570fc49230288295970728e4d795d6327de63a0.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/ab431bb436946356d0964e8a7570fc49230288295970728e4d795d6327de63a0.jpg)

![acc4d7cc2a6b2227b3b2ca2d7bb4ce9cedf8c46a85719cbaf279c6de59711a74.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/acc4d7cc2a6b2227b3b2ca2d7bb4ce9cedf8c46a85719cbaf279c6de59711a74.jpg)

![addb530af0fce6bfd1763475cc32a79b3081d139e888a3126fe0e0b4ca17c2ee.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/addb530af0fce6bfd1763475cc32a79b3081d139e888a3126fe0e0b4ca17c2ee.jpg)

![c281744ce53ed174075461b256d0f06c2432fe127848cb4a90cde6edda2bdbe4.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/c281744ce53ed174075461b256d0f06c2432fe127848cb4a90cde6edda2bdbe4.jpg)

![c2c389a6e6624e1479553baac063d86339ec7730f43e3f1f69bd4e10b8dbb7eb.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/c2c389a6e6624e1479553baac063d86339ec7730f43e3f1f69bd4e10b8dbb7eb.jpg)

![c4452813d5ea01457b17815c188c1deaa661329ee059aa4629493575b34bc917.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/c4452813d5ea01457b17815c188c1deaa661329ee059aa4629493575b34bc917.jpg)

![c5f298a4efab91dd870b6d27bdd72fa51c51c08b42fead2dcbb7451d2c3a11d4.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/c5f298a4efab91dd870b6d27bdd72fa51c51c08b42fead2dcbb7451d2c3a11d4.jpg)

![f1fbf6dfc27511811c0c01c48a6a8e25a3d5a55de1c2f73cbbcfff02a9fb5ee4.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/f1fbf6dfc27511811c0c01c48a6a8e25a3d5a55de1c2f73cbbcfff02a9fb5ee4.jpg)

![ff3b11525ca77585dfb68135d75f68058b45f16bfcba024bcd6ff8cc6b788d75.jpg](../nips_results/4530_Forging%20Time%20Series%20with%20Language_%20A%20Large%20Language%20Model%20Approach%20to%20Synthetic%20Data%20Generation/tables/ff3b11525ca77585dfb68135d75f68058b45f16bfcba024bcd6ff8cc6b788d75.jpg)

## NaViL: Rethinking Scaling Properties of Native Multimodal Large Language Models under Data Constraints


### Images

![0281e7d15ef936664d5ae93292b219541b67c1606a9d60e8ebed07c70a79983b.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/0281e7d15ef936664d5ae93292b219541b67c1606a9d60e8ebed07c70a79983b.jpg)

![0dce367aaaaefc6d8ce655946960bcb3e2a9e536c1597c10752253c04c229fe0.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/0dce367aaaaefc6d8ce655946960bcb3e2a9e536c1597c10752253c04c229fe0.jpg)

![29b8a6ad120c491df7fc5a587c4d155f4d2bef54ae4bf7cb3d7a2690d0047eeb.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/29b8a6ad120c491df7fc5a587c4d155f4d2bef54ae4bf7cb3d7a2690d0047eeb.jpg)

![3c1ecd90b9674b1bfff6c99bb0a68486162562c33fccbc1b962a32a92c279c17.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/3c1ecd90b9674b1bfff6c99bb0a68486162562c33fccbc1b962a32a92c279c17.jpg)

![4b9b4e72423dbdc9256bb2458808e3ff488f06ff80a56ff22b99ab5ace79df89.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/4b9b4e72423dbdc9256bb2458808e3ff488f06ff80a56ff22b99ab5ace79df89.jpg)

![56298ef29e565d03e4421178a4bca18aeca9678e25e9930ea54bbce2d09320cb.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/56298ef29e565d03e4421178a4bca18aeca9678e25e9930ea54bbce2d09320cb.jpg)

![585cb57a135d42022d4d32b257d1417cdb1002c4890530907f2d9b26a113b5e0.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/585cb57a135d42022d4d32b257d1417cdb1002c4890530907f2d9b26a113b5e0.jpg)

![7214f8c9b905115e155ef415d802134707edc181acb1ed236b866a108bf4ea02.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/7214f8c9b905115e155ef415d802134707edc181acb1ed236b866a108bf4ea02.jpg)

![7bcde37741f8b78c9bd32747db09f78824110b93a7eddf9c9bb50527dbffc5ea.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/7bcde37741f8b78c9bd32747db09f78824110b93a7eddf9c9bb50527dbffc5ea.jpg)

![8461f290c4a08d5cd7cc86a1ea6fdffdc74d5b15b76c6662cccc92749faacf08.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/8461f290c4a08d5cd7cc86a1ea6fdffdc74d5b15b76c6662cccc92749faacf08.jpg)

![a359848517486184b29385124afe9418ae21229a9bccf54b16d6eeb68d43430f.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/a359848517486184b29385124afe9418ae21229a9bccf54b16d6eeb68d43430f.jpg)

![ac50c5d0175cc98144e2c0b0d75e7bdf380da9fab0a4b9e2994907c18eb56809.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/ac50c5d0175cc98144e2c0b0d75e7bdf380da9fab0a4b9e2994907c18eb56809.jpg)

![adb3cc75792bdb14222471687a21baa10a279cbc224d8c82aeb09eded83e8d69.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/adb3cc75792bdb14222471687a21baa10a279cbc224d8c82aeb09eded83e8d69.jpg)

![b1dc9bc5ac502d363ed7723f82eebf62e5c1bbf20fb3bac9e075f9db041be47f.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/b1dc9bc5ac502d363ed7723f82eebf62e5c1bbf20fb3bac9e075f9db041be47f.jpg)

![ee63c0c757b2e82354faa31dc7f639173a5388aff6fb51a50d73a7e053af6c96.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/ee63c0c757b2e82354faa31dc7f639173a5388aff6fb51a50d73a7e053af6c96.jpg)

![f84e7f34a27e42b7bc36b12851d8267ffa290344d54d87f42f9ad0d10a872f32.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/images/f84e7f34a27e42b7bc36b12851d8267ffa290344d54d87f42f9ad0d10a872f32.jpg)

### Tables

![1ba24ce6f522915620f7728327499e1557456fe31dec5b16324e66983891ae91.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/tables/1ba24ce6f522915620f7728327499e1557456fe31dec5b16324e66983891ae91.jpg)

![3a98d04fb046e5b26d3cdb79041338306fdb5840c12edf1dd2f77cd7a0c778b4.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/tables/3a98d04fb046e5b26d3cdb79041338306fdb5840c12edf1dd2f77cd7a0c778b4.jpg)

![439ced11283a65ce5ba7c6f040a113571d6d09c98b1c148ddb60eea03edd91b6.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/tables/439ced11283a65ce5ba7c6f040a113571d6d09c98b1c148ddb60eea03edd91b6.jpg)

![82c2f8f9e578b3a536c726180f64b0ba2dc6b0b0127afd40af027cb555b63526.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/tables/82c2f8f9e578b3a536c726180f64b0ba2dc6b0b0127afd40af027cb555b63526.jpg)

![9f56399d4136b1eafcf53a1213c7a01c9035b63570f36eb72ee52ad1c24a16f0.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/tables/9f56399d4136b1eafcf53a1213c7a01c9035b63570f36eb72ee52ad1c24a16f0.jpg)

![a605419dd889376a144210174d1d41e05c836c81e87812a391439c5c9595adac.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/tables/a605419dd889376a144210174d1d41e05c836c81e87812a391439c5c9595adac.jpg)

![c079a2e9394da3e741460de648fb5710ee3af740aba2fc46663e39cca4958a80.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/tables/c079a2e9394da3e741460de648fb5710ee3af740aba2fc46663e39cca4958a80.jpg)

![d76b0419d927e1b62b11ddb624a456ccd29b8f6b2bf93f2cd28cc5de753725ac.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/tables/d76b0419d927e1b62b11ddb624a456ccd29b8f6b2bf93f2cd28cc5de753725ac.jpg)

![e08fabf66673a5b88cb3c3636c568d2535766b0cb70f0f29c23be280489ac694.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/tables/e08fabf66673a5b88cb3c3636c568d2535766b0cb70f0f29c23be280489ac694.jpg)

![e30204e388804101cab9ee41a624ac2c1280942f7faa6c5217d64f9c71852184.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/tables/e30204e388804101cab9ee41a624ac2c1280942f7faa6c5217d64f9c71852184.jpg)

![fac3dbd777e9de4ba7a8411109bc32508fe389068b2e685f5a189900cd37f2a4.jpg](../nips_results/4531_NaViL_%20Rethinking%20Scaling%20Properties%20of%20Native%20Multimodal%20Large%20Language%20Models%20under%20Data%20Constrain/tables/fac3dbd777e9de4ba7a8411109bc32508fe389068b2e685f5a189900cd37f2a4.jpg)

## What's Producible May Not Be Reachable: Measuring the Steerability of Generative Models


### Images

![08dd8f4c5d89556d7472bbe45d0c0703957eacb8381addf557bcef14007f67ac.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/08dd8f4c5d89556d7472bbe45d0c0703957eacb8381addf557bcef14007f67ac.jpg)

![1cde98f83b8a0ccae277607b1c9bfd0f3aa0fafa9cbc5ba263775f6be90fe8c7.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/1cde98f83b8a0ccae277607b1c9bfd0f3aa0fafa9cbc5ba263775f6be90fe8c7.jpg)

![35908b0376f3702aaa167f17e99ab39c3b5b5d7f75cc025de35a52e72bbd95bb.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/35908b0376f3702aaa167f17e99ab39c3b5b5d7f75cc025de35a52e72bbd95bb.jpg)

![434d3b0a9d2ad265d83c85cc0a0d53e90c27f4b7c6a218bc57fcf81b79107ce0.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/434d3b0a9d2ad265d83c85cc0a0d53e90c27f4b7c6a218bc57fcf81b79107ce0.jpg)

![49a26982adbaaa3966c1bcff64627955accc8afd95f9605fd73f1458f9bb3080.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/49a26982adbaaa3966c1bcff64627955accc8afd95f9605fd73f1458f9bb3080.jpg)

![5e5f2a3349d39f00f01272db363bd9156a118b260b1760b1aca60c8583a2c72f.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/5e5f2a3349d39f00f01272db363bd9156a118b260b1760b1aca60c8583a2c72f.jpg)

![6163991b162dea360c4e72c4f76d93fb64c9a09d3f7a8165d910afa108b1a79f.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/6163991b162dea360c4e72c4f76d93fb64c9a09d3f7a8165d910afa108b1a79f.jpg)

![656e6cc71424c84ff895e89867bd7dc5d721be06d12a7a1f398d573ce116f2ab.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/656e6cc71424c84ff895e89867bd7dc5d721be06d12a7a1f398d573ce116f2ab.jpg)

![817a9a4be0c1697b8cf8506634a668824bd6898cd91c826720db99d8c94b0349.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/817a9a4be0c1697b8cf8506634a668824bd6898cd91c826720db99d8c94b0349.jpg)

![87287df327605f727e448b679834b911b303670fa2955415b50f916266ae8530.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/87287df327605f727e448b679834b911b303670fa2955415b50f916266ae8530.jpg)

![9c042b7ab09053a7db7c577b06214f6b74cd4c83f26a70bf35ec244258469e5e.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/9c042b7ab09053a7db7c577b06214f6b74cd4c83f26a70bf35ec244258469e5e.jpg)

![a4c075638590e5bfef5ead99d0f9890d515edc069e5b4bcc3e1392156464f910.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/a4c075638590e5bfef5ead99d0f9890d515edc069e5b4bcc3e1392156464f910.jpg)

![b7987faea3de9322f54c58852821d19d45b45a56c2468978b096c2198125ec7f.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/b7987faea3de9322f54c58852821d19d45b45a56c2468978b096c2198125ec7f.jpg)

![c5fab486d7910db928b797a68bac76a8d08a363962891f2521e77f2a7caf02df.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/c5fab486d7910db928b797a68bac76a8d08a363962891f2521e77f2a7caf02df.jpg)

![c69fc8ad053425d3d0018ea393f320bfed9f8997c45f471ccbe84adc70e8e378.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/c69fc8ad053425d3d0018ea393f320bfed9f8997c45f471ccbe84adc70e8e378.jpg)

![df6364344275ff853140c59c64058a3f222c9d6fa264ddb190fe974c0b63c5df.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/df6364344275ff853140c59c64058a3f222c9d6fa264ddb190fe974c0b63c5df.jpg)

![e6d183b250f4f244fe691971c69b0c3244e62e9f9e483c2af7a2fb4550611187.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/e6d183b250f4f244fe691971c69b0c3244e62e9f9e483c2af7a2fb4550611187.jpg)

![ecaff3848f2e91d87e4a25b6fe5ad27ee70c69275cd6883d84adfc62b69930d2.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/ecaff3848f2e91d87e4a25b6fe5ad27ee70c69275cd6883d84adfc62b69930d2.jpg)

![f699b165e1cc845aa0d2501ff76dd8449df5beae97579744713ced634849a981.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/f699b165e1cc845aa0d2501ff76dd8449df5beae97579744713ced634849a981.jpg)

![f92ef5ff0c4fdad68ee72117d96f434dc07f0868592545d0ad28a93f07b62798.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/f92ef5ff0c4fdad68ee72117d96f434dc07f0868592545d0ad28a93f07b62798.jpg)

![fc250505aee31f152685c528f17ddfd8b33598554329373e077dffc802805637.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/fc250505aee31f152685c528f17ddfd8b33598554329373e077dffc802805637.jpg)

![fef8dff6eecd31e986908a3f280d005d52bbb3d0bf093dc8a12237e6d9719280.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/images/fef8dff6eecd31e986908a3f280d005d52bbb3d0bf093dc8a12237e6d9719280.jpg)

### Tables

![14bb8cd6b86201925a574972a4bae8c4da240ce9c2f5c787eeb817e957b49aa1.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/tables/14bb8cd6b86201925a574972a4bae8c4da240ce9c2f5c787eeb817e957b49aa1.jpg)

![167699594498980aa11e68fa67d71ce41eec4a94d81f33b056f7efde05e645ef.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/tables/167699594498980aa11e68fa67d71ce41eec4a94d81f33b056f7efde05e645ef.jpg)

![266fa2a05477c3d320c592cbb063997a1345fa069a194e6b68f7d78020a4d5d4.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/tables/266fa2a05477c3d320c592cbb063997a1345fa069a194e6b68f7d78020a4d5d4.jpg)

![6be622946edc01fce1934542f374c5e65eb87ed4b06a051175be2e533619c068.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/tables/6be622946edc01fce1934542f374c5e65eb87ed4b06a051175be2e533619c068.jpg)

![706bb882f0111d728c6a7df844f1dc533905fd3928528b191efe2a084752801a.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/tables/706bb882f0111d728c6a7df844f1dc533905fd3928528b191efe2a084752801a.jpg)

![b99ee49049eb7a227fb92ef254cab495b92dd68c7e3835702f7a9afd8b43ff26.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/tables/b99ee49049eb7a227fb92ef254cab495b92dd68c7e3835702f7a9afd8b43ff26.jpg)

![cd53286b1a5df61df749dbded505bcbc5cf84b1264032ce2c44b1b95a8684aa2.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/tables/cd53286b1a5df61df749dbded505bcbc5cf84b1264032ce2c44b1b95a8684aa2.jpg)

![ea5b134b49c36cef02952807491c7ce8d9419bc1dd453ac369e874060253a8e0.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/tables/ea5b134b49c36cef02952807491c7ce8d9419bc1dd453ac369e874060253a8e0.jpg)

![fe64165a55090baa483c331686b8cd548823007adfab1d78555d1bc2ace070ae.jpg](../nips_results/4532_What%27s%20Producible%20May%20Not%20Be%20Reachable_%20Measuring%20the%20Steerability%20of%20Generative%20Models/tables/fe64165a55090baa483c331686b8cd548823007adfab1d78555d1bc2ace070ae.jpg)

## On the Optimality of the Median-of-Means Estimator under Adversarial Contamination


### Images

![95f390d4eddc95b8b64648423f787ed56b443e43e3b13b8ea76414ef5de83614.jpg](../nips_results/4533_On%20the%20Optimality%20of%20the%20Median-of-Means%20Estimator%20under%20Adversarial%20Contamination/images/95f390d4eddc95b8b64648423f787ed56b443e43e3b13b8ea76414ef5de83614.jpg)

![fe474df3dd84f32d25a7b8f1a443b9392bc469d7721aa01e4fa8f13a584bd228.jpg](../nips_results/4533_On%20the%20Optimality%20of%20the%20Median-of-Means%20Estimator%20under%20Adversarial%20Contamination/images/fe474df3dd84f32d25a7b8f1a443b9392bc469d7721aa01e4fa8f13a584bd228.jpg)

### Tables

![1b65b58ec598a772370d7ca1744e057161ce762275d3b7c81c74c3c660dee2dc.jpg](../nips_results/4533_On%20the%20Optimality%20of%20the%20Median-of-Means%20Estimator%20under%20Adversarial%20Contamination/tables/1b65b58ec598a772370d7ca1744e057161ce762275d3b7c81c74c3c660dee2dc.jpg)

![92529a1d08d9b6602192fd1f64baf9025b9bd47131d8a9b9c33152092e3aa122.jpg](../nips_results/4533_On%20the%20Optimality%20of%20the%20Median-of-Means%20Estimator%20under%20Adversarial%20Contamination/tables/92529a1d08d9b6602192fd1f64baf9025b9bd47131d8a9b9c33152092e3aa122.jpg)

## Consistently Simulating Human Personas with Multi-Turn Reinforcement Learning


### Images

![0bd5e9777d3d5f4d29f50135e1c4546361cfba3dd1f17dced7f29ea479d1ab12.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/images/0bd5e9777d3d5f4d29f50135e1c4546361cfba3dd1f17dced7f29ea479d1ab12.jpg)

![3b81b1e30c24e9f4b0aeab380a2c6c55ca197edcb157e6e8f98a8dd7a516b261.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/images/3b81b1e30c24e9f4b0aeab380a2c6c55ca197edcb157e6e8f98a8dd7a516b261.jpg)

![7d1064b57a65b3ddeea662d0ce072918c8a9b4c1e28c53179516d0e555d7e4b8.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/images/7d1064b57a65b3ddeea662d0ce072918c8a9b4c1e28c53179516d0e555d7e4b8.jpg)

![b442ce6e0b8c5bb9331373fb6e6e093c9136fad04aa25b2bc3b1e8b65e14140b.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/images/b442ce6e0b8c5bb9331373fb6e6e093c9136fad04aa25b2bc3b1e8b65e14140b.jpg)

![ddb447ebd166a7bf0bfca1b430d17e92c1b37344ee69e8d03dce2907b132d547.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/images/ddb447ebd166a7bf0bfca1b430d17e92c1b37344ee69e8d03dce2907b132d547.jpg)

### Tables

![15fbd8988ac867c037ca9f6be4fc92ced0487a55490fe5700452b77a031ddd1e.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/tables/15fbd8988ac867c037ca9f6be4fc92ced0487a55490fe5700452b77a031ddd1e.jpg)

![19af968e8c06990a6a1b9ec55bdab8a6a030ce4dee62572d40f33510ac7e6da0.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/tables/19af968e8c06990a6a1b9ec55bdab8a6a030ce4dee62572d40f33510ac7e6da0.jpg)

![277931f833183de7d3d84e7756458ab0611594667b3cef29e2e3acbede0ff464.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/tables/277931f833183de7d3d84e7756458ab0611594667b3cef29e2e3acbede0ff464.jpg)

![284a367b2efa7d435dae74dc805cb2ce3c25f10c3a9e61f99ae53944d0a5ce88.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/tables/284a367b2efa7d435dae74dc805cb2ce3c25f10c3a9e61f99ae53944d0a5ce88.jpg)

![2a5f04d512eb052db428c6cfe41086494be4637734b10fb4ace7fc107bd0f991.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/tables/2a5f04d512eb052db428c6cfe41086494be4637734b10fb4ace7fc107bd0f991.jpg)

![485495af3715a381153713dc2d540ddf8ea269a55c0eb7865a925c66264fdcf2.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/tables/485495af3715a381153713dc2d540ddf8ea269a55c0eb7865a925c66264fdcf2.jpg)

![50a4f952664b90300aa7773a754e284a80ebae6cd1aabb757008f66da8ae2518.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/tables/50a4f952664b90300aa7773a754e284a80ebae6cd1aabb757008f66da8ae2518.jpg)

![78c07c619e94d4d896c64ad2339b2a0dff849f7449f4db9e38ecffe430000b4b.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/tables/78c07c619e94d4d896c64ad2339b2a0dff849f7449f4db9e38ecffe430000b4b.jpg)

![842a5f20262aa3d2a29d2c99c8924c46e857fee77f1e71cfd2c43726142bd742.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/tables/842a5f20262aa3d2a29d2c99c8924c46e857fee77f1e71cfd2c43726142bd742.jpg)

![f2303444031728d4527fc4bfbe4b0e07573c5cd03aed26c029f0692af4ccddd0.jpg](../nips_results/4534_Consistently%20Simulating%20Human%20Personas%20with%20Multi-Turn%20Reinforcement%20Learning/tables/f2303444031728d4527fc4bfbe4b0e07573c5cd03aed26c029f0692af4ccddd0.jpg)

## NoisyRollout: Reinforcing Visual Reasoning with Data Augmentation


### Images

![043293d32ec1ab058da68d97540f72ffb6bb524db963c6a3922562a119615de7.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/images/043293d32ec1ab058da68d97540f72ffb6bb524db963c6a3922562a119615de7.jpg)

![13fa2a9372822433726449203ef2a92754efe353f7127c8f61fe420383c58b8e.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/images/13fa2a9372822433726449203ef2a92754efe353f7127c8f61fe420383c58b8e.jpg)

![2856c11a74cce54765a5ed8b122da820d9384a79e477088c7f18b4b818f77fb2.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/images/2856c11a74cce54765a5ed8b122da820d9384a79e477088c7f18b4b818f77fb2.jpg)

![34d26afeefe6e72cd5abfcdd37cb145938c4ab366538c5202edfbaca51fa74db.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/images/34d26afeefe6e72cd5abfcdd37cb145938c4ab366538c5202edfbaca51fa74db.jpg)

![3e27ec9586ec4ab2fe381103a84198dffe9f4acc83bb7063d0cecd621bad2622.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/images/3e27ec9586ec4ab2fe381103a84198dffe9f4acc83bb7063d0cecd621bad2622.jpg)

![5f90139d0552e7e727d5e85f1960306e161067297304e3f01c8f8c7c831291f2.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/images/5f90139d0552e7e727d5e85f1960306e161067297304e3f01c8f8c7c831291f2.jpg)

![78845422543f0f9a5eb847af5818de7d2d266e3877e64d7b49fd3fecc99e5069.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/images/78845422543f0f9a5eb847af5818de7d2d266e3877e64d7b49fd3fecc99e5069.jpg)

![7ceaa1641ac4fdf915c9ffd4b56eefaf8f0f73a51b1c19d4c591aec103913c51.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/images/7ceaa1641ac4fdf915c9ffd4b56eefaf8f0f73a51b1c19d4c591aec103913c51.jpg)

![b86c3f6f966456218c83cca341b7eb388e3238045f28c7fd0a9e3f4e5a78fe75.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/images/b86c3f6f966456218c83cca341b7eb388e3238045f28c7fd0a9e3f4e5a78fe75.jpg)

![bfe4474370e7b1952e162b742d8de094c7e3b8dfc7b5f81abe7db3149fed6523.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/images/bfe4474370e7b1952e162b742d8de094c7e3b8dfc7b5f81abe7db3149fed6523.jpg)

![fa9b73b816f35765393022c665f9ec803824f8c65e5708bec676e141601b4992.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/images/fa9b73b816f35765393022c665f9ec803824f8c65e5708bec676e141601b4992.jpg)

### Tables

![125487490b529b1b5106076bf286fcd26789b238f218a32d72a5eb269789de4c.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/125487490b529b1b5106076bf286fcd26789b238f218a32d72a5eb269789de4c.jpg)

![23c17ee7f2484462f39c4b429f11e28fa948c19f6dc6949014d19c80bafb9b28.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/23c17ee7f2484462f39c4b429f11e28fa948c19f6dc6949014d19c80bafb9b28.jpg)

![406afd4c8a5e97b445e556415af3334b12d55f3bf126ce3f5ae8dadc128b7055.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/406afd4c8a5e97b445e556415af3334b12d55f3bf126ce3f5ae8dadc128b7055.jpg)

![527dc34feee8f54b748b4d106c1b878052df490b2484d9b39091cf3c605abb5c.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/527dc34feee8f54b748b4d106c1b878052df490b2484d9b39091cf3c605abb5c.jpg)

![57e6a52baca97d26b7ddd75f3264984e89fc764e82a40cfc301222e917d557b2.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/57e6a52baca97d26b7ddd75f3264984e89fc764e82a40cfc301222e917d557b2.jpg)

![67e54a96059cf20eb0be77ef0d49419f68c22fcf7cc6d35826445e2190c97e46.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/67e54a96059cf20eb0be77ef0d49419f68c22fcf7cc6d35826445e2190c97e46.jpg)

![7605c2d20d10b077918bc03a91a2f5a3747cf11d074a9ec6a3b42625da9ab636.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/7605c2d20d10b077918bc03a91a2f5a3747cf11d074a9ec6a3b42625da9ab636.jpg)

![9dcc8009bd2be3274ee2498b726f72b3510b2edb04b240b6666c0ef7d47b5ea3.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/9dcc8009bd2be3274ee2498b726f72b3510b2edb04b240b6666c0ef7d47b5ea3.jpg)

![a064b612586fc167dc9d275856f58cda41accbd2961ad87358f284f7a69a482c.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/a064b612586fc167dc9d275856f58cda41accbd2961ad87358f284f7a69a482c.jpg)

![c8cf7f64a814f9f7b9c5ccf607072bd55d5d98e024761564f27ec14950ab3848.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/c8cf7f64a814f9f7b9c5ccf607072bd55d5d98e024761564f27ec14950ab3848.jpg)

![ee02360cb71ebf10b82e686149583b22b63d1610b7be2776d5fd5d148624bf80.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/ee02360cb71ebf10b82e686149583b22b63d1610b7be2776d5fd5d148624bf80.jpg)

![f7f959ef2ba8b124bc0409ec48876e1806f4e162d36d9b356276fb94a90617df.jpg](../nips_results/4535_NoisyRollout_%20Reinforcing%20Visual%20Reasoning%20with%20Data%20Augmentation/tables/f7f959ef2ba8b124bc0409ec48876e1806f4e162d36d9b356276fb94a90617df.jpg)

## Can Class-Priors Help Single-Positive Multi-Label Learning?


### Images

![d6f1798b2d9f471cd4f4c722a8ca0ed8ab8b7ca6e244ebd7edfa490f01c021e3.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/images/d6f1798b2d9f471cd4f4c722a8ca0ed8ab8b7ca6e244ebd7edfa490f01c021e3.jpg)

![dac24d5f9a206229d5a71b828cd24b260b2ab56b6c15d15f8cfcfd238e4fe2db.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/images/dac24d5f9a206229d5a71b828cd24b260b2ab56b6c15d15f8cfcfd238e4fe2db.jpg)

![fcab442b77c19abaf7cce140fba5838a7e7af08735eb57f529ff7dd4a106e8f0.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/images/fcab442b77c19abaf7cce140fba5838a7e7af08735eb57f529ff7dd4a106e8f0.jpg)

### Tables

![0f8996f1b8d62ef597317cb4f219d6ce465910e99ecb214eaa655c9c30907d03.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/0f8996f1b8d62ef597317cb4f219d6ce465910e99ecb214eaa655c9c30907d03.jpg)

![17d6140e6176d318bbe1b6d3004502bb547a8e6c93ea68abf2fd7c89a42dbef0.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/17d6140e6176d318bbe1b6d3004502bb547a8e6c93ea68abf2fd7c89a42dbef0.jpg)

![3748d909bea61624b462d19b96f36db130206a5f2098549bb4586f66b31b5b37.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/3748d909bea61624b462d19b96f36db130206a5f2098549bb4586f66b31b5b37.jpg)

![5c978b6d53cddaf4ab0c85fc37490dbe8ff6e298db9e83c4653594443f3faba7.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/5c978b6d53cddaf4ab0c85fc37490dbe8ff6e298db9e83c4653594443f3faba7.jpg)

![64d920a881bfcafc4944e9b0e4ee77a75124aab67e4716dd16a6d81066bd4758.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/64d920a881bfcafc4944e9b0e4ee77a75124aab67e4716dd16a6d81066bd4758.jpg)

![73606623bcf62c357cff2cef4c22463f510ef08e38f24721ea92275ca528215e.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/73606623bcf62c357cff2cef4c22463f510ef08e38f24721ea92275ca528215e.jpg)

![940167546b0c7510ad4faa438356304aedb8bac0d8c1900241a882ec31823ecf.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/940167546b0c7510ad4faa438356304aedb8bac0d8c1900241a882ec31823ecf.jpg)

![a1cde6416c242b411ed09ee716ecac76955b8bebb4fb8a87086a528080bdbc12.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/a1cde6416c242b411ed09ee716ecac76955b8bebb4fb8a87086a528080bdbc12.jpg)

![b4fb0652a16732ddd2825dccd1f2c509691c94e3a2dc35cb390fef617319de79.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/b4fb0652a16732ddd2825dccd1f2c509691c94e3a2dc35cb390fef617319de79.jpg)

![ba9fe1b41aa735fad61e80ce4d7577cfc7b034e7b7a21615550f67fab6d4aadb.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/ba9fe1b41aa735fad61e80ce4d7577cfc7b034e7b7a21615550f67fab6d4aadb.jpg)

![cb50243dfddf1cce9d6764f42d011d0ca59bb2686bbc9af88d77dc4c42f17b39.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/cb50243dfddf1cce9d6764f42d011d0ca59bb2686bbc9af88d77dc4c42f17b39.jpg)

![de91eda6ddc37b4d5f1bd28247e516916848fce95e22d01ffa9ae3ff746ea8ba.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/de91eda6ddc37b4d5f1bd28247e516916848fce95e22d01ffa9ae3ff746ea8ba.jpg)

![fcafae19ce8ad4cf2b4b2588536907fba49151a94ed815d60acaa85c784a33d1.jpg](../nips_results/4536_Can%20Class-Priors%20Help%20Single-Positive%20Multi-Label%20Learning_/tables/fcafae19ce8ad4cf2b4b2588536907fba49151a94ed815d60acaa85c784a33d1.jpg)

## Self-Challenging Language Model Agents


### Images

![065fcd488d6e954cb20fa87a0831c79f41e456c789ea0df409039c24e0bf04dd.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/065fcd488d6e954cb20fa87a0831c79f41e456c789ea0df409039c24e0bf04dd.jpg)

![0d691f062aeb491dbbcfa775c74b1cac4bf625322af6e2bcea4f325cbf50a38a.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/0d691f062aeb491dbbcfa775c74b1cac4bf625322af6e2bcea4f325cbf50a38a.jpg)

![0da045ed68a5daaf16b279bb006087531fe26b428903edd6a668d56e8c3f0b8b.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/0da045ed68a5daaf16b279bb006087531fe26b428903edd6a668d56e8c3f0b8b.jpg)

![2b22aca136f6a7619cb028895da321775e44e7f8c86b7953668e9df2e9e32dfd.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/2b22aca136f6a7619cb028895da321775e44e7f8c86b7953668e9df2e9e32dfd.jpg)

![365eb000e531bff05812420412e07e0ce7c5a6415d5eaf844c14fbfc0e59dd83.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/365eb000e531bff05812420412e07e0ce7c5a6415d5eaf844c14fbfc0e59dd83.jpg)

![3a9fd3860b4b3ae78ac7580fb1156f59b37efabd6ca395f8e578c38b4dd93c0b.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/3a9fd3860b4b3ae78ac7580fb1156f59b37efabd6ca395f8e578c38b4dd93c0b.jpg)

![4feeb2912da974084085cfa0dbcbc2e54091657ac10ad0ec4785163124866f5d.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/4feeb2912da974084085cfa0dbcbc2e54091657ac10ad0ec4785163124866f5d.jpg)

![82dd048cc879736b113e91ad3e9cde0f72d3be91b50909b5a2145792eec12d66.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/82dd048cc879736b113e91ad3e9cde0f72d3be91b50909b5a2145792eec12d66.jpg)

![9c16a03b03d70ee4980e48a1ea2e4d32d941c2aaf7e3dd629d9c69eeb91351d3.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/9c16a03b03d70ee4980e48a1ea2e4d32d941c2aaf7e3dd629d9c69eeb91351d3.jpg)

![a67bd6e3ba3e808e61867fc12a4a90fc72b1d12f1468639ac5c70d4d50e00585.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/a67bd6e3ba3e808e61867fc12a4a90fc72b1d12f1468639ac5c70d4d50e00585.jpg)

![a7c9f9a1cbf012355c24620119790c3d84fdac065013cf6c2ccaaf2e1c85dc5a.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/a7c9f9a1cbf012355c24620119790c3d84fdac065013cf6c2ccaaf2e1c85dc5a.jpg)

![a9227341045ad2657ce74cf3d2ef883dfe06690188ce6b3664cd7a4eadcbe045.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/a9227341045ad2657ce74cf3d2ef883dfe06690188ce6b3664cd7a4eadcbe045.jpg)

![ad03f9aaa0bd1d4f80df7abab476114c4da7a3a7489e2d4522a05f9addbc5b22.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/ad03f9aaa0bd1d4f80df7abab476114c4da7a3a7489e2d4522a05f9addbc5b22.jpg)

![b482ded2b7d1b0c713aa7677b27b51020a42d095a000af5d15448ecb43227d13.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/b482ded2b7d1b0c713aa7677b27b51020a42d095a000af5d15448ecb43227d13.jpg)

![b4c63d1a7984b0c2c1c392ec313ecd4cf97915dfb1bd8d03023b7f804fda3501.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/b4c63d1a7984b0c2c1c392ec313ecd4cf97915dfb1bd8d03023b7f804fda3501.jpg)

![ba4f1500761b5f77a1e32d5fc61150441c10f841f90c65c86d09366a9d42c860.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/ba4f1500761b5f77a1e32d5fc61150441c10f841f90c65c86d09366a9d42c860.jpg)

![bd5964da60c359e60aa41d0860f968d0ccfdd044d051fe436411ba0d80b0a551.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/bd5964da60c359e60aa41d0860f968d0ccfdd044d051fe436411ba0d80b0a551.jpg)

![eb986ff04788a4a11e54f4d73fed36dde6b3f06f116d82fb5356435e3e4a159b.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/images/eb986ff04788a4a11e54f4d73fed36dde6b3f06f116d82fb5356435e3e4a159b.jpg)

### Tables

![0847eec188f1fd28caf8a05da7214135dc1aeb706607b2eeaea43a005bb27e5f.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/tables/0847eec188f1fd28caf8a05da7214135dc1aeb706607b2eeaea43a005bb27e5f.jpg)

![2d36a08735b1ba2fe6d064f725f95099d701199a48dc02d7ea55758606905ce9.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/tables/2d36a08735b1ba2fe6d064f725f95099d701199a48dc02d7ea55758606905ce9.jpg)

![4ca8e01451bbbc331ed2adff827f4e35558712fcb1018176abe0ef633ebe8d40.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/tables/4ca8e01451bbbc331ed2adff827f4e35558712fcb1018176abe0ef633ebe8d40.jpg)

![8ec06e1a304cdf6d856e05e0fb14f804a876219c9c75a0131ee29f2cb12a8bb0.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/tables/8ec06e1a304cdf6d856e05e0fb14f804a876219c9c75a0131ee29f2cb12a8bb0.jpg)

![97753d2519784b4a206a64bbb7ac29b87796a3659c974a02b9fd2b81da5cde2e.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/tables/97753d2519784b4a206a64bbb7ac29b87796a3659c974a02b9fd2b81da5cde2e.jpg)

![b4a2f09e1369a73e39d71c494af7ac6736eca3d3fefa870153083424813a802b.jpg](../nips_results/4537_Self-Challenging%20Language%20Model%20Agents/tables/b4a2f09e1369a73e39d71c494af7ac6736eca3d3fefa870153083424813a802b.jpg)

## GSPN-2: Efficient Parallel Sequence Modeling


### Images

![0e6c8bea4cd7fc3db814fa86bc4eeff7e0d38ee9209427f3ded86a531a8d148d.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/images/0e6c8bea4cd7fc3db814fa86bc4eeff7e0d38ee9209427f3ded86a531a8d148d.jpg)

![1b826f09d12bab8fade1313077b533499f08a8bf432d210920f6ba37ba47fe6a.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/images/1b826f09d12bab8fade1313077b533499f08a8bf432d210920f6ba37ba47fe6a.jpg)

![4c3eb990608c5d7cca17f239f09a7e895b6c1e330555855c1ba79c2d43e47a55.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/images/4c3eb990608c5d7cca17f239f09a7e895b6c1e330555855c1ba79c2d43e47a55.jpg)

![6778188eabe6f9ff32952838d96dcbd8a8145400755ca3cfe2200d6990ad80d9.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/images/6778188eabe6f9ff32952838d96dcbd8a8145400755ca3cfe2200d6990ad80d9.jpg)

![84d2ef6bbd49136645d26c76f3bbf51fece050a8ee6ed8217943ef18ed3abf53.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/images/84d2ef6bbd49136645d26c76f3bbf51fece050a8ee6ed8217943ef18ed3abf53.jpg)

![9773ffe06337385be5a10972deb71be7ea64561544c6c1a3d3b6373a8d3839fc.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/images/9773ffe06337385be5a10972deb71be7ea64561544c6c1a3d3b6373a8d3839fc.jpg)

![d0cc8558a189dee11ae77d413796ae8b963d0ebfa7e2a2d790174241c722dd18.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/images/d0cc8558a189dee11ae77d413796ae8b963d0ebfa7e2a2d790174241c722dd18.jpg)

![d8da94d0f3ea865d1dcc5199478181855028de56c78fa1bb7d7ddef24025c47c.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/images/d8da94d0f3ea865d1dcc5199478181855028de56c78fa1bb7d7ddef24025c47c.jpg)

![eed914cb2d766b41e0680925637228a05d509f54a75697bbafc9e9043457cd06.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/images/eed914cb2d766b41e0680925637228a05d509f54a75697bbafc9e9043457cd06.jpg)

### Tables

![25e9c6936761c6d59aee6f243d93deba51a06863f081762e4c62353dabea8544.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/tables/25e9c6936761c6d59aee6f243d93deba51a06863f081762e4c62353dabea8544.jpg)

![299587d6123467af6aa1c892f069f64edc129cb1d3250bda347aa11c765c9e5b.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/tables/299587d6123467af6aa1c892f069f64edc129cb1d3250bda347aa11c765c9e5b.jpg)

![37e12792d9945181d92556e49b9f86c3ea6f177dcdbbb93e24f8790d9ff1e170.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/tables/37e12792d9945181d92556e49b9f86c3ea6f177dcdbbb93e24f8790d9ff1e170.jpg)

![d167cf868d8671d4a8add5c2bd567a37f7b71252560505d0bd10e336acfa5fff.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/tables/d167cf868d8671d4a8add5c2bd567a37f7b71252560505d0bd10e336acfa5fff.jpg)

![e130a4d636b5aed89ae57d2706930181744001c471fd6cb8d6a6ab4e268bbd20.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/tables/e130a4d636b5aed89ae57d2706930181744001c471fd6cb8d6a6ab4e268bbd20.jpg)

![ea8d9bcb596d721863487cd465de2355c742297d359819430e9d8616ebd00718.jpg](../nips_results/4538_GSPN-2_%20Efficient%20Parallel%20Sequence%20Modeling/tables/ea8d9bcb596d721863487cd465de2355c742297d359819430e9d8616ebd00718.jpg)

## A Frustratingly Simple Yet Highly Effective Attack Baseline: Over 90% Success Rate Against the Strong Black-box Models of GPT-4.5/4o/o1


### Images

![0c513627fac544fb435a13674df3354671d468527f8d8d1d619e78ca56d3deb7.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/0c513627fac544fb435a13674df3354671d468527f8d8d1d619e78ca56d3deb7.jpg)

![18ceeaa15856546132c1a6302f0e515d30fb9cf4a81397eedefe17ef90e46463.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/18ceeaa15856546132c1a6302f0e515d30fb9cf4a81397eedefe17ef90e46463.jpg)

![1d58d118aa76347fbb3adf6ed1e7f2054fec6884d137c092323bfc421f2fd919.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/1d58d118aa76347fbb3adf6ed1e7f2054fec6884d137c092323bfc421f2fd919.jpg)

![1fdda73e1f68f95109c7acc1a024852b11e22ae493058f03fa0b5dcda8df6b54.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/1fdda73e1f68f95109c7acc1a024852b11e22ae493058f03fa0b5dcda8df6b54.jpg)

![28cd1ea552abb9f06a8111ecd144c3b36c7b9837393a8f8863f9a5ab61af7ce3.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/28cd1ea552abb9f06a8111ecd144c3b36c7b9837393a8f8863f9a5ab61af7ce3.jpg)

![362b053c8917d02ac3ebe8286f70d00dabf1135f688c923a604b243ce387b3bf.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/362b053c8917d02ac3ebe8286f70d00dabf1135f688c923a604b243ce387b3bf.jpg)

![3c96d7cbf8bf9fb93bb4b8c15c89375fa7a2ca2df5ff1416e850b5cc3f3a19ce.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/3c96d7cbf8bf9fb93bb4b8c15c89375fa7a2ca2df5ff1416e850b5cc3f3a19ce.jpg)

![3d66018783a80b97d313f972363f22962e5b0cd69aa5d9e7d2a8c1cffe04724c.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/3d66018783a80b97d313f972363f22962e5b0cd69aa5d9e7d2a8c1cffe04724c.jpg)

![4f6f1f2eb7141fcfc7536d66922dc9750d181c50cc70beafa781219ea8bd6b7c.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/4f6f1f2eb7141fcfc7536d66922dc9750d181c50cc70beafa781219ea8bd6b7c.jpg)

![57169f8d4ef3f6136d471946c5ebdc8c46da839e997a2a8f0eba3cc088682474.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/57169f8d4ef3f6136d471946c5ebdc8c46da839e997a2a8f0eba3cc088682474.jpg)

![6e4654837bb15b81986644e979467038d67e3003f401bef080db564c746ab450.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/6e4654837bb15b81986644e979467038d67e3003f401bef080db564c746ab450.jpg)

![7468bbda211f1e175261150a5dcde4633ea0df2f3872621be67e0db5d7c18a27.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/7468bbda211f1e175261150a5dcde4633ea0df2f3872621be67e0db5d7c18a27.jpg)

![7fe317addb1d686520186f13b883c21339ea2603f70a8ee01decea5b230bed53.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/7fe317addb1d686520186f13b883c21339ea2603f70a8ee01decea5b230bed53.jpg)

![814749e87ed69cc65688f6a694742cd0b7d3b2a45ec98bd9f03c983f6f686d54.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/814749e87ed69cc65688f6a694742cd0b7d3b2a45ec98bd9f03c983f6f686d54.jpg)

![8fa3f632af22bdaacb4668d1190854c075014a68325ab4ab745a63965620066c.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/8fa3f632af22bdaacb4668d1190854c075014a68325ab4ab745a63965620066c.jpg)

![909a739ddd0cf661806aa5c8f9fd4da92dce110f075d7ab07d228567d8016dfa.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/909a739ddd0cf661806aa5c8f9fd4da92dce110f075d7ab07d228567d8016dfa.jpg)

![b0428440473f722ff746f723164c54b9e6182cf997e2ec9b2b290b77dd820dc5.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/b0428440473f722ff746f723164c54b9e6182cf997e2ec9b2b290b77dd820dc5.jpg)

![b2b5534a8619806e00af4dcdc3801dfdd8efd5efd311be4c26d3b007495b19c7.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/b2b5534a8619806e00af4dcdc3801dfdd8efd5efd311be4c26d3b007495b19c7.jpg)

![bacc50e43eb4c4e6c4419e5d1780839417c2bf6dd5e1f6d4f733d7af6c55611b.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/bacc50e43eb4c4e6c4419e5d1780839417c2bf6dd5e1f6d4f733d7af6c55611b.jpg)

![c2ddfc872c3e0e90002f19a828f23c08ea0a9c9d95ea27ba741218f8d6863c76.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/c2ddfc872c3e0e90002f19a828f23c08ea0a9c9d95ea27ba741218f8d6863c76.jpg)

![c9c2ef651557d3cf92375875f606fe6e805eca9e409a2e2645dc335822b1b9de.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/c9c2ef651557d3cf92375875f606fe6e805eca9e409a2e2645dc335822b1b9de.jpg)

![de781eb597407f015f7d613b493b9cf55bb801fa8a2e7ea7dd38f73cab5763e3.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/de781eb597407f015f7d613b493b9cf55bb801fa8a2e7ea7dd38f73cab5763e3.jpg)

![f761afb7c67c2b57d8ececd6bdf0f843cf902ecb8d5d3ce5f662c4772bfd4a7f.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/f761afb7c67c2b57d8ececd6bdf0f843cf902ecb8d5d3ce5f662c4772bfd4a7f.jpg)

![f8347c57fab758fc1bda1f511f8be10d62c15327d096e0f3b1787132b7d5720e.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/images/f8347c57fab758fc1bda1f511f8be10d62c15327d096e0f3b1787132b7d5720e.jpg)

### Tables

![01e828885bb12db11576dcc41a3c17afab88b006e7b0469b0516808785ced6ed.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/01e828885bb12db11576dcc41a3c17afab88b006e7b0469b0516808785ced6ed.jpg)

![184afbb46c275f5d20f57c7f1e3ee5128733b32903fcafebc46db39c80637050.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/184afbb46c275f5d20f57c7f1e3ee5128733b32903fcafebc46db39c80637050.jpg)

![33a0f2a28cd1bb663499b6a42ac12615192fc44e5afe94cbcd686603a4a55810.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/33a0f2a28cd1bb663499b6a42ac12615192fc44e5afe94cbcd686603a4a55810.jpg)

![40a948a6936586f16300ab4709139322d1c32dfd4a679f29b5ebddbf3bae296b.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/40a948a6936586f16300ab4709139322d1c32dfd4a679f29b5ebddbf3bae296b.jpg)

![597417037d51b3ef6b05cf42f47c17eccc7765e60ae41d6c6ce4001f4ddff45e.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/597417037d51b3ef6b05cf42f47c17eccc7765e60ae41d6c6ce4001f4ddff45e.jpg)

![62099e82f30fd1d212232e6b233770864c5bab8366225cab3fca45f9d025a596.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/62099e82f30fd1d212232e6b233770864c5bab8366225cab3fca45f9d025a596.jpg)

![685c0d1c43212b107046d233636c4770349049a4eadb1a01032adcf8ac4bd1c6.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/685c0d1c43212b107046d233636c4770349049a4eadb1a01032adcf8ac4bd1c6.jpg)

![79ba621add2ce3f50961fa10541d0b511c60d5ae2a3713f34a0016411f537cec.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/79ba621add2ce3f50961fa10541d0b511c60d5ae2a3713f34a0016411f537cec.jpg)

![7cefc920fc4d404424f0d14c1ea3ce83d29f9a1887b4ac78101c81d4259765c9.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/7cefc920fc4d404424f0d14c1ea3ce83d29f9a1887b4ac78101c81d4259765c9.jpg)

![8090dd8964aa89764e6d43c15c0f0f011a69b65dc00176200dd2c0714ea3dc5a.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/8090dd8964aa89764e6d43c15c0f0f011a69b65dc00176200dd2c0714ea3dc5a.jpg)

![b727d11fe5f9d9bb752f4e89a1022e64527f72c2d893c810f1cf9c7933293f08.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/b727d11fe5f9d9bb752f4e89a1022e64527f72c2d893c810f1cf9c7933293f08.jpg)

![c19c54c2da0691774433812cec006fe01501c0ff0074992a02e9f62a6ac7c899.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/c19c54c2da0691774433812cec006fe01501c0ff0074992a02e9f62a6ac7c899.jpg)

![d070915d6e79b9f6280e25e13a6ae8ca250e40bcda31698cf49f646893785dd2.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/d070915d6e79b9f6280e25e13a6ae8ca250e40bcda31698cf49f646893785dd2.jpg)

![d1b2a9ff1d5a18afb90c0408b35976ef415b760400415e3f5b653e73da37d600.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/d1b2a9ff1d5a18afb90c0408b35976ef415b760400415e3f5b653e73da37d600.jpg)

![d31ab07b5d3cc22df86bbc41b63c7091f8b2fe3f4d5b1a30113139c7643ee92d.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/d31ab07b5d3cc22df86bbc41b63c7091f8b2fe3f4d5b1a30113139c7643ee92d.jpg)

![d537de0f2d6dfe433a0add425bb1117b13101b25c779a252615869d947e2a6f4.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/d537de0f2d6dfe433a0add425bb1117b13101b25c779a252615869d947e2a6f4.jpg)

![dd289c4e149fe1c8d1a2467a27c782473c5cbaf5833eefc315c714f4c3cc89cd.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/dd289c4e149fe1c8d1a2467a27c782473c5cbaf5833eefc315c714f4c3cc89cd.jpg)

![e1b30e89c718fa5aa65bb636110e5fa78aaf0ef43c9ce972b99b91bc47a876fa.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/e1b30e89c718fa5aa65bb636110e5fa78aaf0ef43c9ce972b99b91bc47a876fa.jpg)

![ec740ce4b8fee92d0b494c9a7587bdac70b0d523e3288658c94369e8ae1e9fd1.jpg](../nips_results/4539_A%20Frustratingly%20Simple%20Yet%20Highly%20Effective%20Attack%20Baseline_%20Over%2090%25%20Success%20Rate%20Against%20the%20Stron/tables/ec740ce4b8fee92d0b494c9a7587bdac70b0d523e3288658c94369e8ae1e9fd1.jpg)

## How Ensembles of Distilled Policies Improve Generalisation in Reinforcement Learning


### Images

![283685fca21a52cd9c2098c0e6d816bf47fdfe32a3b708ddbd9398d1c6636524.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/images/283685fca21a52cd9c2098c0e6d816bf47fdfe32a3b708ddbd9398d1c6636524.jpg)

![41ae2998272bcd48f12414717d4085e73cec8c1e7d40021922ef7e7522eb91cf.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/images/41ae2998272bcd48f12414717d4085e73cec8c1e7d40021922ef7e7522eb91cf.jpg)

![6556405ba6b59a8a21f7fee694046c462ef8f9b4d51ced223de87cb1ec83e9d6.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/images/6556405ba6b59a8a21f7fee694046c462ef8f9b4d51ced223de87cb1ec83e9d6.jpg)

![7be3bb9b8f59528d71ef2828fb28393719f319909fce85aa5f430e492317a129.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/images/7be3bb9b8f59528d71ef2828fb28393719f319909fce85aa5f430e492317a129.jpg)

![ab23de5d729d0aa1353da8a9cd0a8b948b96f9975df66921a6d24c17bab4164a.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/images/ab23de5d729d0aa1353da8a9cd0a8b948b96f9975df66921a6d24c17bab4164a.jpg)

![bc218a8460efc32440c9d54de513a887646ef0d28cd82ccf9819930ca0f40440.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/images/bc218a8460efc32440c9d54de513a887646ef0d28cd82ccf9819930ca0f40440.jpg)

### Tables

![08882c495e1ed61ccb14d0df3a65c0e9ced6793ece1bac1a085b92974a8c5d69.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/tables/08882c495e1ed61ccb14d0df3a65c0e9ced6793ece1bac1a085b92974a8c5d69.jpg)

![1a88023a9dfd740f2c0c226210b7c93d1e6283b009132f3840b7932cbddccb08.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/tables/1a88023a9dfd740f2c0c226210b7c93d1e6283b009132f3840b7932cbddccb08.jpg)

![269b6bf587be135a2d768c6d3110b72296ded440a9ae235151867c8a9d717cbb.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/tables/269b6bf587be135a2d768c6d3110b72296ded440a9ae235151867c8a9d717cbb.jpg)

![3109d28686ca8cf2f1efd4f42ece168b6c7ef789e0c3223d7a194703cc160a40.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/tables/3109d28686ca8cf2f1efd4f42ece168b6c7ef789e0c3223d7a194703cc160a40.jpg)

![3fe0d86c3168be9601f05f2b75c0bbbf916ebf9ddc9ecceb351fa61145f934f2.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/tables/3fe0d86c3168be9601f05f2b75c0bbbf916ebf9ddc9ecceb351fa61145f934f2.jpg)

![4253e6db7f0430d63272d1281fac6f35092d506daa9a1529689cf1a96111359c.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/tables/4253e6db7f0430d63272d1281fac6f35092d506daa9a1529689cf1a96111359c.jpg)

![5cad75db17d5a8e28be1fb47287ff822fc1b296970b8b31693150895f4366d63.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/tables/5cad75db17d5a8e28be1fb47287ff822fc1b296970b8b31693150895f4366d63.jpg)

![6f04ab09182eea4462f6ebe2cdd2378f00ebe736e53eadcf18c613dbed9c6874.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/tables/6f04ab09182eea4462f6ebe2cdd2378f00ebe736e53eadcf18c613dbed9c6874.jpg)

![a5c2ff82e6c24b3045689f0f64b30cc0bb308586866e24c7df7cc5ed45570ef0.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/tables/a5c2ff82e6c24b3045689f0f64b30cc0bb308586866e24c7df7cc5ed45570ef0.jpg)

![e9300edd016d0a8acd54d34c34e7a724b94c0e06b717ffb51bdfaad8cd70ee1b.jpg](../nips_results/4540_How%20Ensembles%20of%20Distilled%20Policies%20Improve%20Generalisation%20in%20Reinforcement%20Learning/tables/e9300edd016d0a8acd54d34c34e7a724b94c0e06b717ffb51bdfaad8cd70ee1b.jpg)

## Tensor Decomposition Networks for Accelerating Machine Learning Force Field Computations


### Images

![350315d316fe934802526b39bbb842ac9187cd8a4fa6036d542fb650b432122f.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/images/350315d316fe934802526b39bbb842ac9187cd8a4fa6036d542fb650b432122f.jpg)

![4c425b8f89cf033c0418ba014f8949b82cbb7c5ad440f304a76246177cb49c44.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/images/4c425b8f89cf033c0418ba014f8949b82cbb7c5ad440f304a76246177cb49c44.jpg)

![84e7767f0b9526bec21efefd96b331dd30a71a358a29810a0eb068ba64bc5dd7.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/images/84e7767f0b9526bec21efefd96b331dd30a71a358a29810a0eb068ba64bc5dd7.jpg)

### Tables

![020ca17a1ebcb4cd4298ed914c4d76439ec503019d24c3018bf5f7e3db27c24e.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/tables/020ca17a1ebcb4cd4298ed914c4d76439ec503019d24c3018bf5f7e3db27c24e.jpg)

![09693f1d4ea69e0a1a9d9ba06baffc3532fe864b8b1e49319e0724da93e64923.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/tables/09693f1d4ea69e0a1a9d9ba06baffc3532fe864b8b1e49319e0724da93e64923.jpg)

![5b17599d32f4cb4a7cde6a16f5405a535302b1ff7305e27e7edee6339dfee37b.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/tables/5b17599d32f4cb4a7cde6a16f5405a535302b1ff7305e27e7edee6339dfee37b.jpg)

![9092201e26894ef5fca0870f02bccd4555ea722f6d343be78e440318b0ec86de.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/tables/9092201e26894ef5fca0870f02bccd4555ea722f6d343be78e440318b0ec86de.jpg)

![a5f288f457380c4df01d7f4dd4f87b9ee981a93da4175cdffa4033ebdafc52dc.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/tables/a5f288f457380c4df01d7f4dd4f87b9ee981a93da4175cdffa4033ebdafc52dc.jpg)

![c5b774d36fb286b051ac6cb16ea2b7578af62f8d92a45ac388f3e40948df6f59.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/tables/c5b774d36fb286b051ac6cb16ea2b7578af62f8d92a45ac388f3e40948df6f59.jpg)

![dc80b274a552d060541c8ccc3e8386470206ba1a2eb1b2955a59aa86103547c3.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/tables/dc80b274a552d060541c8ccc3e8386470206ba1a2eb1b2955a59aa86103547c3.jpg)

![eae678f66b83d7d0689f5374c430e54665b2ac4553afe37c48c939ac38ccac78.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/tables/eae678f66b83d7d0689f5374c430e54665b2ac4553afe37c48c939ac38ccac78.jpg)

![ec43a13e49af14e31519af3ba09d9521a43265a4966f8ba59a6499044dc8fd7c.jpg](../nips_results/4541_Tensor%20Decomposition%20Networks%20for%20Accelerating%20Machine%20Learning%20Force%20Field%20Computations/tables/ec43a13e49af14e31519af3ba09d9521a43265a4966f8ba59a6499044dc8fd7c.jpg)

## Inverse Optimization Latent Variable Models for Learning Costs Applied to Route Problems


### Images

![011f7d2ace9d6471151c3d32fed30384c3b30d7a9261afac141502f6986dadee.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/011f7d2ace9d6471151c3d32fed30384c3b30d7a9261afac141502f6986dadee.jpg)

![204eb7e5013c1cb017a8f3e4706a50f8ae738366d9337525fff084dc3039fb90.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/204eb7e5013c1cb017a8f3e4706a50f8ae738366d9337525fff084dc3039fb90.jpg)

![49b5aa65d3de6cd06cbd5e82b8aef68afaf3b39c5a3f26fd3cc3d96134fcba3f.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/49b5aa65d3de6cd06cbd5e82b8aef68afaf3b39c5a3f26fd3cc3d96134fcba3f.jpg)

![4a986f60151efc22de956fb9dd87ea64226239b269843f4ebf13821e84cc06e0.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/4a986f60151efc22de956fb9dd87ea64226239b269843f4ebf13821e84cc06e0.jpg)

![712d459000a20aa5e8aa68bb6cb9566e1db4f94045753254b596c0faa9bf1591.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/712d459000a20aa5e8aa68bb6cb9566e1db4f94045753254b596c0faa9bf1591.jpg)

![7c29a6000da878dbf42c64a0467cb1267240aed57a5ac593e85eafecf95d1547.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/7c29a6000da878dbf42c64a0467cb1267240aed57a5ac593e85eafecf95d1547.jpg)

![8f0dfdcaf09984b2f4cdf935b8e2535e7ce92a94ead25978d633ef3e16637cd7.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/8f0dfdcaf09984b2f4cdf935b8e2535e7ce92a94ead25978d633ef3e16637cd7.jpg)

![a7b85ce0839a7cb00b33220a3622ac0396e4834da09e90aab5e17aef7e233acc.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/a7b85ce0839a7cb00b33220a3622ac0396e4834da09e90aab5e17aef7e233acc.jpg)

![a87f7d1ef2092bee96310c97ac36accf6cebbeb918df085fba496da4163067bd.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/a87f7d1ef2092bee96310c97ac36accf6cebbeb918df085fba496da4163067bd.jpg)

![a8a6d0e9e74fa6b8fd39283a591c653abcb4fc43aa13e6e8317ec606f17dd723.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/a8a6d0e9e74fa6b8fd39283a591c653abcb4fc43aa13e6e8317ec606f17dd723.jpg)

![b55c1b2170cf29c6695d8fb5103cc86d478863754064963ddda794f33f9c929e.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/b55c1b2170cf29c6695d8fb5103cc86d478863754064963ddda794f33f9c929e.jpg)

![c810eab3d4dfea05d7c8c94aa8500ea0ef30d6bbdbf5b5632866e5a87d692dbb.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/c810eab3d4dfea05d7c8c94aa8500ea0ef30d6bbdbf5b5632866e5a87d692dbb.jpg)

![d19b437c48ee2c4b6c308924e296c38e23633e251163a21255ec26864fe64bf7.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/d19b437c48ee2c4b6c308924e296c38e23633e251163a21255ec26864fe64bf7.jpg)

![effdad236163386c5a7e385b99fa7d935c205dede6768947bbfd494ce0276bdf.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/images/effdad236163386c5a7e385b99fa7d935c205dede6768947bbfd494ce0276bdf.jpg)

### Tables

![072008e2e670d605529f2725645bd10239deb0e670de162c9c5e063a121db65d.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/tables/072008e2e670d605529f2725645bd10239deb0e670de162c9c5e063a121db65d.jpg)

![6ef655b63b98d697b8528354ca507c1e7f79218103556763eb798a585834f657.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/tables/6ef655b63b98d697b8528354ca507c1e7f79218103556763eb798a585834f657.jpg)

![814f18d5b68b561cd2f5958d87196a53b9bf25d37eba6c63f3e6d7a0bfcf30cb.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/tables/814f18d5b68b561cd2f5958d87196a53b9bf25d37eba6c63f3e6d7a0bfcf30cb.jpg)

![b8dce9ca89c3667d412dde6f644a43cb31128b8dd09c20fb36af91a2158764cb.jpg](../nips_results/4542_Inverse%20Optimization%20Latent%20Variable%20Models%20for%20Learning%20Costs%20Applied%20to%20Route%20Problems/tables/b8dce9ca89c3667d412dde6f644a43cb31128b8dd09c20fb36af91a2158764cb.jpg)

## Smoothed Agnostic Learning of Halfspaces over the Hypercube


### Tables

![f24231cb6326d6773e1d45a026b346f054dc76a0f3a8e00e4ebbc974e39d4a23.jpg](../nips_results/4543_Smoothed%20Agnostic%20Learning%20of%20Halfspaces%20over%20the%20Hypercube/tables/f24231cb6326d6773e1d45a026b346f054dc76a0f3a8e00e4ebbc974e39d4a23.jpg)

## Self-Guided Hierarchical Exploration for Generalist Foundation Model Web Agents


### Images

![47fd643b4c1a29a91c2afbe8b343a9600fbe80efcd15fd593e818943e80b9a8d.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/images/47fd643b4c1a29a91c2afbe8b343a9600fbe80efcd15fd593e818943e80b9a8d.jpg)

![6913d0f87941d8b9699c2fe3218adaf1c657452ccf8d362e04e9248544276cff.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/images/6913d0f87941d8b9699c2fe3218adaf1c657452ccf8d362e04e9248544276cff.jpg)

![a5e91b1e2e149fda5b910342e44c09bd86a0eb424fbfdb1bb1d89e74e35d581a.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/images/a5e91b1e2e149fda5b910342e44c09bd86a0eb424fbfdb1bb1d89e74e35d581a.jpg)

![c59b8180b359f01b926e6254cad27419d31d0d017e8a52fe6ed15eb71afbb32a.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/images/c59b8180b359f01b926e6254cad27419d31d0d017e8a52fe6ed15eb71afbb32a.jpg)

![f08145b7ce5ff90281ffcb1362d8d1461b375c235dab57e6f4a9c6811e169f30.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/images/f08145b7ce5ff90281ffcb1362d8d1461b375c235dab57e6f4a9c6811e169f30.jpg)

### Tables

![0dedd186e4c14455de2a417c63c29ca5f3a56de33bac87108b48c13c35479420.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/0dedd186e4c14455de2a417c63c29ca5f3a56de33bac87108b48c13c35479420.jpg)

![1991a7eae15fecd884744150bb1050a45e0a761fb5aa77f8f5e3a4309fa40337.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/1991a7eae15fecd884744150bb1050a45e0a761fb5aa77f8f5e3a4309fa40337.jpg)

![5e23588ca52c024ad02f0c6847363567e3d0c4a101f19a6db7d89772aeae0d59.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/5e23588ca52c024ad02f0c6847363567e3d0c4a101f19a6db7d89772aeae0d59.jpg)

![6eaaeefa62558ced9b8a67db7f3008f01987e0b63f5dfcbd3b2c31ba5b077671.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/6eaaeefa62558ced9b8a67db7f3008f01987e0b63f5dfcbd3b2c31ba5b077671.jpg)

![70e7650d9e3c4431e6ef962d67d8909f432d4de423232a026bc28198d5189ea0.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/70e7650d9e3c4431e6ef962d67d8909f432d4de423232a026bc28198d5189ea0.jpg)

![773cdc334aa2f787dfbd9b747249e69d0100f89804435e37e70094f8896bdc0d.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/773cdc334aa2f787dfbd9b747249e69d0100f89804435e37e70094f8896bdc0d.jpg)

![9465729c76161e77e6321c302e0ef76b0879028f45858a0f065a727fe802894f.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/9465729c76161e77e6321c302e0ef76b0879028f45858a0f065a727fe802894f.jpg)

![98770730113262f2453c2000e860a9145263d1fd7dc7cd46de7259fdb1c87f12.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/98770730113262f2453c2000e860a9145263d1fd7dc7cd46de7259fdb1c87f12.jpg)

![a6a7701faa9d65f62d2c63290731ff9af69768a9443962f9ca740a21b181b31d.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/a6a7701faa9d65f62d2c63290731ff9af69768a9443962f9ca740a21b181b31d.jpg)

![c0a9a410ece3c76002b810e63f4c4c5984c9c8d638788a6a907fd8cd1bd17e6b.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/c0a9a410ece3c76002b810e63f4c4c5984c9c8d638788a6a907fd8cd1bd17e6b.jpg)

![d419351ca193e979b6a7ecb7260328172e42a71b96dfdea92c66395a9d25280d.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/d419351ca193e979b6a7ecb7260328172e42a71b96dfdea92c66395a9d25280d.jpg)

![f0aa06e6af52eb840368058912156a2453db3e2d97af6b6fe1acae0225fc92dc.jpg](../nips_results/4544_Self-Guided%20Hierarchical%20Exploration%20for%20Generalist%20Foundation%20Model%20Web%20Agents/tables/f0aa06e6af52eb840368058912156a2453db3e2d97af6b6fe1acae0225fc92dc.jpg)

## Tightening Regret Lower and Upper Bounds in Restless Rising Bandits


### Images

![1aa03537900c0cad0c238a90c6e3e929396773fae58956f7cf29a42484d31a00.jpg](../nips_results/4545_Tightening%20Regret%20Lower%20and%20Upper%20Bounds%20in%20Restless%20Rising%20Bandits/images/1aa03537900c0cad0c238a90c6e3e929396773fae58956f7cf29a42484d31a00.jpg)

![1b9eb5becdfb146ca5442598d81a942402abc0f305fcba8cbcb817787f9ff265.jpg](../nips_results/4545_Tightening%20Regret%20Lower%20and%20Upper%20Bounds%20in%20Restless%20Rising%20Bandits/images/1b9eb5becdfb146ca5442598d81a942402abc0f305fcba8cbcb817787f9ff265.jpg)

![261bca4836a26f1c7aff694df125e510ed4cb961278c5a2186f1234a5adcd186.jpg](../nips_results/4545_Tightening%20Regret%20Lower%20and%20Upper%20Bounds%20in%20Restless%20Rising%20Bandits/images/261bca4836a26f1c7aff694df125e510ed4cb961278c5a2186f1234a5adcd186.jpg)

![5e0f235c49e9ec918f7dcd66e027b5dab3a09b5530beb55892e5dda95bbfdf33.jpg](../nips_results/4545_Tightening%20Regret%20Lower%20and%20Upper%20Bounds%20in%20Restless%20Rising%20Bandits/images/5e0f235c49e9ec918f7dcd66e027b5dab3a09b5530beb55892e5dda95bbfdf33.jpg)

![98676bd057e3ca3e8f56fc7a621b8751f8fc7c850fd034899ec64947851d481a.jpg](../nips_results/4545_Tightening%20Regret%20Lower%20and%20Upper%20Bounds%20in%20Restless%20Rising%20Bandits/images/98676bd057e3ca3e8f56fc7a621b8751f8fc7c850fd034899ec64947851d481a.jpg)

![ba776f9c15db775ce90a3ea622d840eb6845a1b9f5e21f96168779633e3227f2.jpg](../nips_results/4545_Tightening%20Regret%20Lower%20and%20Upper%20Bounds%20in%20Restless%20Rising%20Bandits/images/ba776f9c15db775ce90a3ea622d840eb6845a1b9f5e21f96168779633e3227f2.jpg)

### Tables

![5a4851d75bf087e2a3ea88e3b43d816b750a7499508ef12b61b00374a5985601.jpg](../nips_results/4545_Tightening%20Regret%20Lower%20and%20Upper%20Bounds%20in%20Restless%20Rising%20Bandits/tables/5a4851d75bf087e2a3ea88e3b43d816b750a7499508ef12b61b00374a5985601.jpg)

## MLZero: A Multi-Agent System for End-to-end Machine Learning Automation


### Images

![326c0fc76caf3ffdf05c7d443f6c7d7ac4fae61e43ee39af6134d680e4f2e935.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/images/326c0fc76caf3ffdf05c7d443f6c7d7ac4fae61e43ee39af6134d680e4f2e935.jpg)

![3725dd39c134449a3cef9290d61a15d5a14992c0b1e4f9763de348a15b05c61d.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/images/3725dd39c134449a3cef9290d61a15d5a14992c0b1e4f9763de348a15b05c61d.jpg)

![cea4b4d3438bc01727651e98591b85f8d613e0819bd7173b24d728bd171ecb62.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/images/cea4b4d3438bc01727651e98591b85f8d613e0819bd7173b24d728bd171ecb62.jpg)

![dbd77857a5cd6b7635c115e1b9c6be72b7b7c148de0d49a5e1d0148466d5c2a8.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/images/dbd77857a5cd6b7635c115e1b9c6be72b7b7c148de0d49a5e1d0148466d5c2a8.jpg)

### Tables

![13d3c5c751c90799f34b9affebe3ddb3652856dbd713a58ac3ddbe5cf154502e.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/13d3c5c751c90799f34b9affebe3ddb3652856dbd713a58ac3ddbe5cf154502e.jpg)

![14998061917dda2dc0e033d0ed4e8c68058a0d48fe4cdff5ad1482c97cfecfc4.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/14998061917dda2dc0e033d0ed4e8c68058a0d48fe4cdff5ad1482c97cfecfc4.jpg)

![14e905539f6e45277dba7d6ba7755e75a315e9cb19eab09b021c708362bf2f9e.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/14e905539f6e45277dba7d6ba7755e75a315e9cb19eab09b021c708362bf2f9e.jpg)

![33c2d0a93645e1aebfe1605abc2162b69c1fac4cafd7d8d4e8f96c70f67bacb5.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/33c2d0a93645e1aebfe1605abc2162b69c1fac4cafd7d8d4e8f96c70f67bacb5.jpg)

![3631fc58233594c4815ec2a6aefb5a6ba7b7afc48d433c0e4a4cbd8e6c90e928.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/3631fc58233594c4815ec2a6aefb5a6ba7b7afc48d433c0e4a4cbd8e6c90e928.jpg)

![38aa9dee0e494ae1dfb25333240cfc92ca07068a8ca6368b20645a0b65ab411c.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/38aa9dee0e494ae1dfb25333240cfc92ca07068a8ca6368b20645a0b65ab411c.jpg)

![42773b3a75783d57d4c7e63338675d03ac686f679ec5bd1e5251fb75ea519cb5.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/42773b3a75783d57d4c7e63338675d03ac686f679ec5bd1e5251fb75ea519cb5.jpg)

![54471a856db3557c3f06aaf85eff00c0fdbceeb8cc30d66a338d5d4ba6a07442.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/54471a856db3557c3f06aaf85eff00c0fdbceeb8cc30d66a338d5d4ba6a07442.jpg)

![59dfe1458400bba1940957e6b3f762ac64632c1f9637f29e789b3354b8d0d1c1.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/59dfe1458400bba1940957e6b3f762ac64632c1f9637f29e789b3354b8d0d1c1.jpg)

![5bf0f3d5b1a7e8733cc85c26949d0f34a92a1be41b0c79603aff3dc74c6d67cd.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/5bf0f3d5b1a7e8733cc85c26949d0f34a92a1be41b0c79603aff3dc74c6d67cd.jpg)

![882fb9cebc99b3e0258f3f68734c9f657a295a4c42eca57e18fb4223bdad68ba.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/882fb9cebc99b3e0258f3f68734c9f657a295a4c42eca57e18fb4223bdad68ba.jpg)

![8e9cc1f23cb4b5371223ede050ecf2c634f4842286cc79347683f806c15a3501.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/8e9cc1f23cb4b5371223ede050ecf2c634f4842286cc79347683f806c15a3501.jpg)

![99472632caa997dd84916cbea1fef02fac64178560d54b7ec611e43213619098.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/99472632caa997dd84916cbea1fef02fac64178560d54b7ec611e43213619098.jpg)

![ac50b68ed5bf75bf605358b255186c9ee53474f787a408ad0199f18965c5bb11.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/ac50b68ed5bf75bf605358b255186c9ee53474f787a408ad0199f18965c5bb11.jpg)

![b630d4d01618007a63c47ed768b282403dea6e3f28b2cdefc731ba372d0aa7f2.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/b630d4d01618007a63c47ed768b282403dea6e3f28b2cdefc731ba372d0aa7f2.jpg)

![c4cf68e6db1df994f8b55050162beeac150fc4b3085c346f7a2f8abf8d2e42ca.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/c4cf68e6db1df994f8b55050162beeac150fc4b3085c346f7a2f8abf8d2e42ca.jpg)

![d1344949c6f800cbdacb7862be4cfbe95c721ee5401220dbb4b6d78db07b12f5.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/d1344949c6f800cbdacb7862be4cfbe95c721ee5401220dbb4b6d78db07b12f5.jpg)

![d43ba566dd6f82870e1747c30af4a727280c6443bb4aab4207beaae4b0198afa.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/d43ba566dd6f82870e1747c30af4a727280c6443bb4aab4207beaae4b0198afa.jpg)

![d51d2618168ea558446b34e8d8a09b1df21d38e8ca396dca8f24b2bc82828f37.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/d51d2618168ea558446b34e8d8a09b1df21d38e8ca396dca8f24b2bc82828f37.jpg)

![d55da766560ee9d9cbc20097111f0acbfbb944b14942799f228adfce9ba5d927.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/d55da766560ee9d9cbc20097111f0acbfbb944b14942799f228adfce9ba5d927.jpg)

![dbee63359a22b30a041ddc971a3f15eae9f78d8d2fe09bca6badc1ba7789eda1.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/dbee63359a22b30a041ddc971a3f15eae9f78d8d2fe09bca6badc1ba7789eda1.jpg)

![de8acf5e1b799addfc040d0fe7b5f7dc8ab76e2241989f075d367a16aa7061ff.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/de8acf5e1b799addfc040d0fe7b5f7dc8ab76e2241989f075d367a16aa7061ff.jpg)

![de9e592ecafe1f936572e9bbd2130863638a8276b9b575d949b07816e753f6d2.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/de9e592ecafe1f936572e9bbd2130863638a8276b9b575d949b07816e753f6d2.jpg)

![e38aaf4493ba622784d7b59f9d3af6b2476cf7cdd8eb90d3358baeeef143b240.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/e38aaf4493ba622784d7b59f9d3af6b2476cf7cdd8eb90d3358baeeef143b240.jpg)

![e641e060a5a6ba2278dcbddcc052b1d080ca07dd1dab8aacf8a81dcfdb542cd9.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/e641e060a5a6ba2278dcbddcc052b1d080ca07dd1dab8aacf8a81dcfdb542cd9.jpg)

![f008531dbd812c59e874a4e0f777411572ddd1a22d248a2bcccb4e8b0720e948.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/f008531dbd812c59e874a4e0f777411572ddd1a22d248a2bcccb4e8b0720e948.jpg)

![f9152e383eba1476708e592bec3596ee065f900b68ee5e8414e740ccba9b91bd.jpg](../nips_results/4546_MLZero_%20A%20Multi-Agent%20System%20for%20End-to-end%20Machine%20Learning%20Automation/tables/f9152e383eba1476708e592bec3596ee065f900b68ee5e8414e740ccba9b91bd.jpg)

## Enhancing Optimizer Stability: Momentum Adaptation of The NGN Step-size


### Images

![0674e8ecce228bb92cb8891db4b6a34580ceccc1ef00b62e8e37193d61859d87.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/0674e8ecce228bb92cb8891db4b6a34580ceccc1ef00b62e8e37193d61859d87.jpg)

![0e557749a7b8622cbbddb445ac2f27566a8c20752b74188b5dc3459482b00793.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/0e557749a7b8622cbbddb445ac2f27566a8c20752b74188b5dc3459482b00793.jpg)

![11d94dea0d15187d76331cdb03f46527d8eea66a62f6659a9cb92f047b1f2390.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/11d94dea0d15187d76331cdb03f46527d8eea66a62f6659a9cb92f047b1f2390.jpg)

![135445f1d52aef403c55d95b31d0bcace389aed3f9b18d48bf4a4d097f236c77.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/135445f1d52aef403c55d95b31d0bcace389aed3f9b18d48bf4a4d097f236c77.jpg)

![136dd7447c7b6792203eb20269a1f5c7f3c80ec5d8de8323fe0ececc79ce13de.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/136dd7447c7b6792203eb20269a1f5c7f3c80ec5d8de8323fe0ececc79ce13de.jpg)

![1801c4ec6151a7a539a6dae4b631da869d7f0532f8eabb59e03e4a7c3174fa89.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/1801c4ec6151a7a539a6dae4b631da869d7f0532f8eabb59e03e4a7c3174fa89.jpg)

![1e7283d5280b0fa7973c3bbc8259c302a7565fced4b40be0dc04458ed0f1494a.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/1e7283d5280b0fa7973c3bbc8259c302a7565fced4b40be0dc04458ed0f1494a.jpg)

![20605506b3b1c786427507f813dbee083f677f98b8334fce8eea2554a25b10a7.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/20605506b3b1c786427507f813dbee083f677f98b8334fce8eea2554a25b10a7.jpg)

![2bcf5f11134c1b90ef42aa133873d0cd2788c8191ac4a447c027d860064d5318.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/2bcf5f11134c1b90ef42aa133873d0cd2788c8191ac4a447c027d860064d5318.jpg)

![3c1b28d16474ba0f62da13f6ff3713a1b5e7d47fd31f3523dfd1b78fc11fde90.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/3c1b28d16474ba0f62da13f6ff3713a1b5e7d47fd31f3523dfd1b78fc11fde90.jpg)

![4e7c999a346cdc407be88c3da7fd5d9dc633b8fb1206a3af310c73a68ec2ea5e.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/4e7c999a346cdc407be88c3da7fd5d9dc633b8fb1206a3af310c73a68ec2ea5e.jpg)

![4f635aed3cd485889cde907286450e9fc88fa1d99f9ee61536cdfbd3753352e4.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/4f635aed3cd485889cde907286450e9fc88fa1d99f9ee61536cdfbd3753352e4.jpg)

![51f6830a700e5e831a3f5d8dee132e1f3f491f11a79979421591fb0436d6a108.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/51f6830a700e5e831a3f5d8dee132e1f3f491f11a79979421591fb0436d6a108.jpg)

![542e99bdc66fd5b40732c621b50dad6358d6475ef98f7337a2df5cea2d8743dd.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/542e99bdc66fd5b40732c621b50dad6358d6475ef98f7337a2df5cea2d8743dd.jpg)

![62e592d27540512c286f46afa3db6db010ce2a41f50aa637002331ebb3272e0d.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/62e592d27540512c286f46afa3db6db010ce2a41f50aa637002331ebb3272e0d.jpg)

![6cc58195de58bcab4e0d9892f96dcd9557e4302060ac7bc97250b15e30576b47.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/6cc58195de58bcab4e0d9892f96dcd9557e4302060ac7bc97250b15e30576b47.jpg)

![8e4deead1d82d66f5bcaf5f757525f7c544928b5f5cd8841c99724f55d372578.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/8e4deead1d82d66f5bcaf5f757525f7c544928b5f5cd8841c99724f55d372578.jpg)

![8ed4bdc16435147746e19f0e599da647025425318274ba6418b9ababba7a55e7.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/8ed4bdc16435147746e19f0e599da647025425318274ba6418b9ababba7a55e7.jpg)

![9bae365ebeebca3fc95795b2707ac11b18d0f9edc190e22d0b43e36b9c11f43a.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/9bae365ebeebca3fc95795b2707ac11b18d0f9edc190e22d0b43e36b9c11f43a.jpg)

![a00e29b534b172f3e844352b40b1994f752b9764971c4756f0176f123f11b3fd.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/a00e29b534b172f3e844352b40b1994f752b9764971c4756f0176f123f11b3fd.jpg)

![d8e00b9ff72c9f8a03eaec081ccb97a3dfa5be0e6c49ecc5776f1cb1281ec2a8.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/d8e00b9ff72c9f8a03eaec081ccb97a3dfa5be0e6c49ecc5776f1cb1281ec2a8.jpg)

![e14144774fe93451c61d9aeebf811f64aac0aa6c6bd5b796d52a424e59b2a82b.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/e14144774fe93451c61d9aeebf811f64aac0aa6c6bd5b796d52a424e59b2a82b.jpg)

![ee699041152e48f491f6404f3636c4083aadbb6a5015a15dd942a2cfd7092798.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/ee699041152e48f491f6404f3636c4083aadbb6a5015a15dd942a2cfd7092798.jpg)

![f0686533fb2de4a21053642bc9773cd2d223e352e5fb544138fdd7c78c84154f.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/f0686533fb2de4a21053642bc9773cd2d223e352e5fb544138fdd7c78c84154f.jpg)

![f3614e895a3b635f9e6a3cfd62b352a0a9a2f6debd27ec78a2f6990e3c1216fa.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/images/f3614e895a3b635f9e6a3cfd62b352a0a9a2f6debd27ec78a2f6990e3c1216fa.jpg)

### Tables

![0b66e1c2f09fbe8de16cf298ffb5132f401c6a3495a60859baf3f9965753b124.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/0b66e1c2f09fbe8de16cf298ffb5132f401c6a3495a60859baf3f9965753b124.jpg)

![0d3a8877b90655e45623b05985485628325f2faa107d7ec74871ff4adf2085ae.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/0d3a8877b90655e45623b05985485628325f2faa107d7ec74871ff4adf2085ae.jpg)

![2cbcf99be39605f330f004aa8bb1c53e75755a65f9913141d443eb06a692e8b2.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/2cbcf99be39605f330f004aa8bb1c53e75755a65f9913141d443eb06a692e8b2.jpg)

![308050a32b7e8ca77ef3d469481f14c1c1f8e33d5e17051c34e1d2fbbee3f342.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/308050a32b7e8ca77ef3d469481f14c1c1f8e33d5e17051c34e1d2fbbee3f342.jpg)

![57faa1329afaab601e7cae07d93d3fee777513fa2866a6d1962fb6564a5c17ab.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/57faa1329afaab601e7cae07d93d3fee777513fa2866a6d1962fb6564a5c17ab.jpg)

![6f0fa2af5ae6e3a5431dc7bab94bc5dcce3216f7e698ecfd9b8884311e42da3e.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/6f0fa2af5ae6e3a5431dc7bab94bc5dcce3216f7e698ecfd9b8884311e42da3e.jpg)

![7be7b39e59a0ceaaba44f7aded9461ce97a85b1c761f8d6aaf923127d815bff0.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/7be7b39e59a0ceaaba44f7aded9461ce97a85b1c761f8d6aaf923127d815bff0.jpg)

![852cc7224c8cbbb149a33704710357b7bae1221227d5046ba3d6116b9da74efb.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/852cc7224c8cbbb149a33704710357b7bae1221227d5046ba3d6116b9da74efb.jpg)

![9406704e83961c73216b081c7618003e08a347deb1cc3dc3dbf503d51634d0eb.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/9406704e83961c73216b081c7618003e08a347deb1cc3dc3dbf503d51634d0eb.jpg)

![ad9b94272447048f7a3e5acc244064354a10f87ced5f31590836b5b52e9043b7.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/ad9b94272447048f7a3e5acc244064354a10f87ced5f31590836b5b52e9043b7.jpg)

![c1e35a207e7a7f9a1bf26305f1f34114d7d7d230c4a6aea07b11485fd38e3b4f.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/c1e35a207e7a7f9a1bf26305f1f34114d7d7d230c4a6aea07b11485fd38e3b4f.jpg)

![c976099053b857e6a3d5d473aba71810d408596fa214b11cee70ee44173f3661.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/c976099053b857e6a3d5d473aba71810d408596fa214b11cee70ee44173f3661.jpg)

![e4afee9241019728724f8499c346f3284c4a02670e0fb9713a6ef1144ee03316.jpg](../nips_results/4547_Enhancing%20Optimizer%20Stability_%20Momentum%20Adaptation%20of%20The%20NGN%20Step-size/tables/e4afee9241019728724f8499c346f3284c4a02670e0fb9713a6ef1144ee03316.jpg)

## An Adaptive Algorithm for Bilevel Optimization on Riemannian Manifolds


### Images

![1a848bc43b01334d52d8cbf4fb3f2907cf7d4e4167f09b7917a491f823d7eafe.jpg](../nips_results/4548_An%20Adaptive%20Algorithm%20for%20Bilevel%20Optimization%20on%20Riemannian%20Manifolds/images/1a848bc43b01334d52d8cbf4fb3f2907cf7d4e4167f09b7917a491f823d7eafe.jpg)

![7f96d4aa30ed1fca3264b62cdfa2e27012303e12f2795b6a1eede6337274da48.jpg](../nips_results/4548_An%20Adaptive%20Algorithm%20for%20Bilevel%20Optimization%20on%20Riemannian%20Manifolds/images/7f96d4aa30ed1fca3264b62cdfa2e27012303e12f2795b6a1eede6337274da48.jpg)

![8fb8be736069c03f37644f0b92bdd07747e2f328a48f4a9a3c37f506569c2470.jpg](../nips_results/4548_An%20Adaptive%20Algorithm%20for%20Bilevel%20Optimization%20on%20Riemannian%20Manifolds/images/8fb8be736069c03f37644f0b92bdd07747e2f328a48f4a9a3c37f506569c2470.jpg)

![8fee15cfd0f790b38f3f6af31174d2c258143240fe3d80f847d603881b386d97.jpg](../nips_results/4548_An%20Adaptive%20Algorithm%20for%20Bilevel%20Optimization%20on%20Riemannian%20Manifolds/images/8fee15cfd0f790b38f3f6af31174d2c258143240fe3d80f847d603881b386d97.jpg)

![a14c37652b3c9e565a1f13bfa11d40d0fdc32c785e364f04935fe6817f8fd902.jpg](../nips_results/4548_An%20Adaptive%20Algorithm%20for%20Bilevel%20Optimization%20on%20Riemannian%20Manifolds/images/a14c37652b3c9e565a1f13bfa11d40d0fdc32c785e364f04935fe6817f8fd902.jpg)

![a6eb19556bec5cc1da071634dac850ee8bd4b827e08d7e7fa3421276188920a0.jpg](../nips_results/4548_An%20Adaptive%20Algorithm%20for%20Bilevel%20Optimization%20on%20Riemannian%20Manifolds/images/a6eb19556bec5cc1da071634dac850ee8bd4b827e08d7e7fa3421276188920a0.jpg)

### Tables

![32a34d2e4fe86e5088995345e36266392362e9c17c8f8ea4c7ec9c2efab54f3a.jpg](../nips_results/4548_An%20Adaptive%20Algorithm%20for%20Bilevel%20Optimization%20on%20Riemannian%20Manifolds/tables/32a34d2e4fe86e5088995345e36266392362e9c17c8f8ea4c7ec9c2efab54f3a.jpg)

![6b247587afde6af565473f9c86c3d47f9bcd361d578f245ac1b192d83d21dda9.jpg](../nips_results/4548_An%20Adaptive%20Algorithm%20for%20Bilevel%20Optimization%20on%20Riemannian%20Manifolds/tables/6b247587afde6af565473f9c86c3d47f9bcd361d578f245ac1b192d83d21dda9.jpg)

![abdaee75e71189d42c857826b0ebce954681e79861b3416d01b7ce942d351cf9.jpg](../nips_results/4548_An%20Adaptive%20Algorithm%20for%20Bilevel%20Optimization%20on%20Riemannian%20Manifolds/tables/abdaee75e71189d42c857826b0ebce954681e79861b3416d01b7ce942d351cf9.jpg)

## Text-to-Decision Agent: Offline Meta-Reinforcement Learning from Natural Language Supervision


### Images

![141d7deaf53f40056b9412698637b59050411fe7d7f4110e6e02306ce18774c7.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/images/141d7deaf53f40056b9412698637b59050411fe7d7f4110e6e02306ce18774c7.jpg)

![1c8157ab92e30483b888e60b167056112fc8f38990badc80e802d6138c011ab0.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/images/1c8157ab92e30483b888e60b167056112fc8f38990badc80e802d6138c011ab0.jpg)

![66257e17f0a736d4c1edfb1f51e9757506fa76f70268189a04b49da917be6512.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/images/66257e17f0a736d4c1edfb1f51e9757506fa76f70268189a04b49da917be6512.jpg)

![83e4050996214481f1a9f2f6728a9dd0d461a75965fe04ba8d9ddbc2d5595979.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/images/83e4050996214481f1a9f2f6728a9dd0d461a75965fe04ba8d9ddbc2d5595979.jpg)

![91199429cb0c159e8131898f158af955dc53141d366add87b8df0a7e970fbb8e.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/images/91199429cb0c159e8131898f158af955dc53141d366add87b8df0a7e970fbb8e.jpg)

![b9d76fb1b763b81ba819b293b2ffba5d7198d4513a6efd9545552cb8458fd783.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/images/b9d76fb1b763b81ba819b293b2ffba5d7198d4513a6efd9545552cb8458fd783.jpg)

![c2c82f5bc0b1f8e3955e63996517dce17e994ed45b152859ef869d187669ed56.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/images/c2c82f5bc0b1f8e3955e63996517dce17e994ed45b152859ef869d187669ed56.jpg)

![c7e543039efaaf9649c58e1ca69bfd1405e670733fbd16c76e87117a77264327.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/images/c7e543039efaaf9649c58e1ca69bfd1405e670733fbd16c76e87117a77264327.jpg)

### Tables

![07dbeb672ee9bd77d41e53e11c488cebd4859ea083dd5b800d964d3b55dd4a0e.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/07dbeb672ee9bd77d41e53e11c488cebd4859ea083dd5b800d964d3b55dd4a0e.jpg)

![2e4fad75dfae1cadf66d075611e6c6ad1e86efd2110721fb80fd6e37c1467f25.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/2e4fad75dfae1cadf66d075611e6c6ad1e86efd2110721fb80fd6e37c1467f25.jpg)

![52ed348eabbc93d88aefa2e4ce4bf1aaa0b9ccdbc98a08f8dc13726f421d299f.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/52ed348eabbc93d88aefa2e4ce4bf1aaa0b9ccdbc98a08f8dc13726f421d299f.jpg)

![53061b488335b90b093a3cd291423840313568f6d6a20ffbf0350ba88fab99d9.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/53061b488335b90b093a3cd291423840313568f6d6a20ffbf0350ba88fab99d9.jpg)

![5f3dbe3002d992a23dc40d77117e4c1051e2c752e6578d4baf465e529f21dcb7.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/5f3dbe3002d992a23dc40d77117e4c1051e2c752e6578d4baf465e529f21dcb7.jpg)

![657f57c3864cd5a959dbf3375039506e0fd74ed0c87ef62d48756b23899e1a55.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/657f57c3864cd5a959dbf3375039506e0fd74ed0c87ef62d48756b23899e1a55.jpg)

![6f01b1b96da78efb15636c9480b6d61840d6e2c8d9ccd58013c7a549b1550f8e.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/6f01b1b96da78efb15636c9480b6d61840d6e2c8d9ccd58013c7a549b1550f8e.jpg)

![7a495b5b12c1f469a3a7ef43a4df87d87dd45b8f33fbfba2ac2507fd3dd32979.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/7a495b5b12c1f469a3a7ef43a4df87d87dd45b8f33fbfba2ac2507fd3dd32979.jpg)

![7a760f992b6a832dde3b43e70a2ac12edc4dd63ca9f6d4071c533f42f25d6ad1.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/7a760f992b6a832dde3b43e70a2ac12edc4dd63ca9f6d4071c533f42f25d6ad1.jpg)

![81c0b8e94cf6feb7bbdf296f9cb50c5fe33ec9dde4cf5ad1d0bce58e853a974a.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/81c0b8e94cf6feb7bbdf296f9cb50c5fe33ec9dde4cf5ad1d0bce58e853a974a.jpg)

![845b749d3c2eba1a71a72510d715e2699649b5f76ae7e0440be9678acac4dc2f.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/845b749d3c2eba1a71a72510d715e2699649b5f76ae7e0440be9678acac4dc2f.jpg)

![b7c858df0f53c07ba11f4a83cbe3cc088b392285d32a06201d334d3b4986918a.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/b7c858df0f53c07ba11f4a83cbe3cc088b392285d32a06201d334d3b4986918a.jpg)

![f411d91e493901218f95a397da4af6ffe550df5c77dbb752221e43fc55078126.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/f411d91e493901218f95a397da4af6ffe550df5c77dbb752221e43fc55078126.jpg)

![fb213c74537914e3defd40e1c54ca2bb54996e5708de268b20d267ac1313a04a.jpg](../nips_results/4549_Text-to-Decision%20Agent_%20Offline%20Meta-Reinforcement%20Learning%20from%20Natural%20Language%20Supervision/tables/fb213c74537914e3defd40e1c54ca2bb54996e5708de268b20d267ac1313a04a.jpg)

## $i$MIND: Insightful Multi-subject Invariant Neural Decoding


### Images

![0494315ca8d506c1dfeb4454ff6f519c0c4395a6905ac47235cb5b2063f68800.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/0494315ca8d506c1dfeb4454ff6f519c0c4395a6905ac47235cb5b2063f68800.jpg)

![08a413ca1256c50eb7e154a344c9fdc483b0ac5c6a6b2fa58e14e839f878fc1f.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/08a413ca1256c50eb7e154a344c9fdc483b0ac5c6a6b2fa58e14e839f878fc1f.jpg)

![0ea6df577e9b10a2bde0788afecac05ec1e12a910f039759302fdc22b83fde07.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/0ea6df577e9b10a2bde0788afecac05ec1e12a910f039759302fdc22b83fde07.jpg)

![1ffa9d3707281b87d4a53608c7db9fe6a418ef0dcb822e1e6584972e2f69e61c.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/1ffa9d3707281b87d4a53608c7db9fe6a418ef0dcb822e1e6584972e2f69e61c.jpg)

![270528e5063ab3ac41c487702ab9f9e5c3d092c4938cdb05f0b4bb86afe292cd.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/270528e5063ab3ac41c487702ab9f9e5c3d092c4938cdb05f0b4bb86afe292cd.jpg)

![28b3b54fc48786d690eba2ce8a6ee6bdb5b80b0e64cdc3a07cccb7b5ee809758.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/28b3b54fc48786d690eba2ce8a6ee6bdb5b80b0e64cdc3a07cccb7b5ee809758.jpg)

![3ef99d8d507a9ad84e24934cd1843cf71cdd71fdd9b532f65bcbf1f1101435a0.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/3ef99d8d507a9ad84e24934cd1843cf71cdd71fdd9b532f65bcbf1f1101435a0.jpg)

![3f2ce02b1ab19466fcb34cc546472d4e37c683d544f4b1c114938e5fb8414f8a.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/3f2ce02b1ab19466fcb34cc546472d4e37c683d544f4b1c114938e5fb8414f8a.jpg)

![4842baea4d076bee7676c41c274814e298835e651d352a5d868e65b47680610b.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/4842baea4d076bee7676c41c274814e298835e651d352a5d868e65b47680610b.jpg)

![48846c3ccdf15c9b34a89e30d0ce948931d48d94024cbf2740c2071578ee327e.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/48846c3ccdf15c9b34a89e30d0ce948931d48d94024cbf2740c2071578ee327e.jpg)

![4c057839e24a76effc1c7c69eb5bf59c94147544ad0804246d1f35d3332d247e.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/4c057839e24a76effc1c7c69eb5bf59c94147544ad0804246d1f35d3332d247e.jpg)

![60e70cef597e236e478ca745bb1ef468b453d39778064d8d3aba06ce62c7f0e0.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/60e70cef597e236e478ca745bb1ef468b453d39778064d8d3aba06ce62c7f0e0.jpg)

![640399f049faeeb4366f34b816cc3975bb1c7aeec60db793da57e0a17ca04f2d.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/640399f049faeeb4366f34b816cc3975bb1c7aeec60db793da57e0a17ca04f2d.jpg)

![6b6037168e860a927256bbedad4f590e839b51dcb71298208440eb68dbb2e3c1.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/6b6037168e860a927256bbedad4f590e839b51dcb71298208440eb68dbb2e3c1.jpg)

![7183418c8fcef002671f91ab9f5e0b5d2b213fe143062489c2ac6dd441b07c85.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/7183418c8fcef002671f91ab9f5e0b5d2b213fe143062489c2ac6dd441b07c85.jpg)

![7f92a0bf8ce36bd125711faf05a135ebed1d306fdbeab45913c5221a69557b59.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/7f92a0bf8ce36bd125711faf05a135ebed1d306fdbeab45913c5221a69557b59.jpg)

![93bb5bdae1b225fd2a3027df144cff6ac5de401be19dd0fb25e8bdbb02437338.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/93bb5bdae1b225fd2a3027df144cff6ac5de401be19dd0fb25e8bdbb02437338.jpg)

![97f6d8624e0a37ca0f85f579f0e68d31e42918490f0d4d481c51f10801931c4e.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/97f6d8624e0a37ca0f85f579f0e68d31e42918490f0d4d481c51f10801931c4e.jpg)

![addc969ec27a294a67727978c55d6c84db06f761c4693e668f0a7ff947c4a9a3.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/addc969ec27a294a67727978c55d6c84db06f761c4693e668f0a7ff947c4a9a3.jpg)

![b0186c130288d331dc020e9095e0f7c9be90f45d404784ed9d23879527c53050.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/b0186c130288d331dc020e9095e0f7c9be90f45d404784ed9d23879527c53050.jpg)

![bdd497b26cd230d715fcf29600389a6724627735ccc58fe7c9950d4c71cf328a.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/bdd497b26cd230d715fcf29600389a6724627735ccc58fe7c9950d4c71cf328a.jpg)

![c0e42693434a18e8f0c3694bd9b3ce07d3065492b5f75adf01f0d06be2ba7d4d.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/c0e42693434a18e8f0c3694bd9b3ce07d3065492b5f75adf01f0d06be2ba7d4d.jpg)

![ce578fc68d69dd859afbf5691404ece3e9c398529655b288f5d332936762cb5c.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/ce578fc68d69dd859afbf5691404ece3e9c398529655b288f5d332936762cb5c.jpg)

![e72e34dcbdb804395520376f397f3e1e01787b5d7fa3d58cb69f17fc998d7bdf.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/e72e34dcbdb804395520376f397f3e1e01787b5d7fa3d58cb69f17fc998d7bdf.jpg)

![f813008b5d0ca4f899749a568e6bc576af39355770a1a4f49bf88f870899ab91.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/images/f813008b5d0ca4f899749a568e6bc576af39355770a1a4f49bf88f870899ab91.jpg)

### Tables

![3b3d9daab1d0c1da22717127f1ff26305089f48c11f8ef451ce30be0d8e112dd.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/tables/3b3d9daab1d0c1da22717127f1ff26305089f48c11f8ef451ce30be0d8e112dd.jpg)

![49c82c9f99655a9950454f6f69cb431b8d20091d522f91324e58f49e5e3cbec9.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/tables/49c82c9f99655a9950454f6f69cb431b8d20091d522f91324e58f49e5e3cbec9.jpg)

![62d03da82a0f45f2e2f99c2a60b51ea80e6ef34beea7c57e892141b27d3e28e7.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/tables/62d03da82a0f45f2e2f99c2a60b51ea80e6ef34beea7c57e892141b27d3e28e7.jpg)

![b394afdb25d5c11f4e58a40e38a7bb430c74f400c318c753c1b63d37e10dc877.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/tables/b394afdb25d5c11f4e58a40e38a7bb430c74f400c318c753c1b63d37e10dc877.jpg)

![d2de2ded54acfbda30bbd469685d66122af5de2184f721c5cbe0af13887f145f.jpg](../nips_results/4550_%24i%24MIND_%20Insightful%20Multi-subject%20Invariant%20Neural%20Decoding/tables/d2de2ded54acfbda30bbd469685d66122af5de2184f721c5cbe0af13887f145f.jpg)

## Segment Policy Optimization: Effective Segment-Level Credit Assignment in RL for Large Language Models


### Images

![013d92cd9dee5c589858b255a41992c542226acaf37674e41257e06e9acb0800.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/013d92cd9dee5c589858b255a41992c542226acaf37674e41257e06e9acb0800.jpg)

![48e0855f29785b81141e40c2cd79813579104be9d2e4c71b830f4221ca899a80.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/48e0855f29785b81141e40c2cd79813579104be9d2e4c71b830f4221ca899a80.jpg)

![596d243100b35d318c19f4683350c83f1967dccac82c87cd52f40dcdd27b4ae9.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/596d243100b35d318c19f4683350c83f1967dccac82c87cd52f40dcdd27b4ae9.jpg)

![7212fe132399149c62fa8ef8324b475eb8b3b3c9baa7408cb996f456db0e73bc.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/7212fe132399149c62fa8ef8324b475eb8b3b3c9baa7408cb996f456db0e73bc.jpg)

![8856f69a3048d4af340ef699c4ac26480e1367902b2e53bacaaecda8d9364caf.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/8856f69a3048d4af340ef699c4ac26480e1367902b2e53bacaaecda8d9364caf.jpg)

![a2f3c135437dc8ee8209e86e077b37a90523615f74b17149df1b8cdec8ba91d2.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/a2f3c135437dc8ee8209e86e077b37a90523615f74b17149df1b8cdec8ba91d2.jpg)

![a7c816ca543504cce7c06b4f8943e0e2bbb6e1d00248d2af5b7ac21b58cb3c06.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/a7c816ca543504cce7c06b4f8943e0e2bbb6e1d00248d2af5b7ac21b58cb3c06.jpg)

![adca874527a666a5560953a0bc589103d9f859034f041ed8a93e825de0baf73c.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/adca874527a666a5560953a0bc589103d9f859034f041ed8a93e825de0baf73c.jpg)

![c2c38414927a861c1ecd8c2150597af708c7e3eff23c6360d03d55e0a5ea7ab3.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/c2c38414927a861c1ecd8c2150597af708c7e3eff23c6360d03d55e0a5ea7ab3.jpg)

![dbc7e7e55a26caac983a0501f8e66d54e50aba3697e881e9d7c8ff032f29d9c6.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/dbc7e7e55a26caac983a0501f8e66d54e50aba3697e881e9d7c8ff032f29d9c6.jpg)

![e141d9842278b2b93a8426134bca1af388ba09f758520399b3b68a0e26e5c5f3.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/e141d9842278b2b93a8426134bca1af388ba09f758520399b3b68a0e26e5c5f3.jpg)

![e9ab8eae892e86e51b11af32f9d198a33a6c0612cbca0322c266b9c9db8e71b7.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/images/e9ab8eae892e86e51b11af32f9d198a33a6c0612cbca0322c266b9c9db8e71b7.jpg)

### Tables

![24abdaaa5faf1f42bfc35503729441179799b3dde5daac72a7df373873346e37.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/tables/24abdaaa5faf1f42bfc35503729441179799b3dde5daac72a7df373873346e37.jpg)

![25e2ca9af510cb99d7c4c75f0592f95482d90d54872f6c21313f90cf27ce6ba1.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/tables/25e2ca9af510cb99d7c4c75f0592f95482d90d54872f6c21313f90cf27ce6ba1.jpg)

![792d5916c4eefd6d2a38287b92ca935f6dbd00edbdc496da09abfdd48462dde0.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/tables/792d5916c4eefd6d2a38287b92ca935f6dbd00edbdc496da09abfdd48462dde0.jpg)

![8f74f5aa6f16708dc4646ca30e89cc0ee5fd4a8d0950f51a246c6875e63c15b9.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/tables/8f74f5aa6f16708dc4646ca30e89cc0ee5fd4a8d0950f51a246c6875e63c15b9.jpg)

![c6976f7cfce7670e7b6ab5abfb382ae7ca729323adb0381f7d1b43ae6d288e60.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/tables/c6976f7cfce7670e7b6ab5abfb382ae7ca729323adb0381f7d1b43ae6d288e60.jpg)

![fee02a1f64494f2e6f7c231076b66666793bb7b737afffde57de036d1518de4d.jpg](../nips_results/4551_Segment%20Policy%20Optimization_%20Effective%20Segment-Level%20Credit%20Assignment%20in%20RL%20for%20Large%20Language%20Mode/tables/fee02a1f64494f2e6f7c231076b66666793bb7b737afffde57de036d1518de4d.jpg)

## HypoBootstrap: A Bootstrapping Framework for Inductive Reasoning


### Images

![424dfbb181ec51118bc5bad04553646bf9b429aee828bee3ee93ca9d841f79a8.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/images/424dfbb181ec51118bc5bad04553646bf9b429aee828bee3ee93ca9d841f79a8.jpg)

![65daf872190ee950665cfd2622e07dc0e4d7da035634ba1e17ea30e9f846b6b6.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/images/65daf872190ee950665cfd2622e07dc0e4d7da035634ba1e17ea30e9f846b6b6.jpg)

![7dcd896036a6510d3aa75a8c4ce499452d3f4824b7db677ae8f7a3e80fe7ef9f.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/images/7dcd896036a6510d3aa75a8c4ce499452d3f4824b7db677ae8f7a3e80fe7ef9f.jpg)

![8885bd5b26678ae4f39322f49303761f1631ed54da750864f957db91aeb7cb7c.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/images/8885bd5b26678ae4f39322f49303761f1631ed54da750864f957db91aeb7cb7c.jpg)

![b57b2bf48b943b73df1cb63752406b132c89fd0e9ccc8e7eab3a73604516583d.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/images/b57b2bf48b943b73df1cb63752406b132c89fd0e9ccc8e7eab3a73604516583d.jpg)

### Tables

![061bfbce8cbb5098b111a1b9e09c41820bb6ecc553df7d0d7c5c4a468579e880.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/061bfbce8cbb5098b111a1b9e09c41820bb6ecc553df7d0d7c5c4a468579e880.jpg)

![0dccaa5ddaa3c4e5058ce0b1fa32ca76c927cb4637768fff640ac9a69574b194.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/0dccaa5ddaa3c4e5058ce0b1fa32ca76c927cb4637768fff640ac9a69574b194.jpg)

![0e599bf5f8ed9ac23740d805329ae0648cd3030aa9aa48146e5729cce0a06d30.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/0e599bf5f8ed9ac23740d805329ae0648cd3030aa9aa48146e5729cce0a06d30.jpg)

![1267ba08676ea703449b4c5719d54aefe3998a11d39e2e996329a7ee8219ae26.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/1267ba08676ea703449b4c5719d54aefe3998a11d39e2e996329a7ee8219ae26.jpg)

![1cc9ff4ef9d84788d73e50a1e2244146b2cc05e304d6dc2b91c55a5c6180d706.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/1cc9ff4ef9d84788d73e50a1e2244146b2cc05e304d6dc2b91c55a5c6180d706.jpg)

![332b2abbd2f54d363cbd2ce50d1edb9697badbfbe77d1996a568a61077f95fb9.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/332b2abbd2f54d363cbd2ce50d1edb9697badbfbe77d1996a568a61077f95fb9.jpg)

![363b0fde370fc98604f0cd10d1610685479f92c6f02c8eaf3d9c8f077de131cb.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/363b0fde370fc98604f0cd10d1610685479f92c6f02c8eaf3d9c8f077de131cb.jpg)

![41fde51518462264963d416abdaa70b4d6ef32f968ba1ca368d63fec04e86570.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/41fde51518462264963d416abdaa70b4d6ef32f968ba1ca368d63fec04e86570.jpg)

![44918fe5626700e16ccda9456aaf2915dc755012b5f77c34dcf029a584a03bf8.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/44918fe5626700e16ccda9456aaf2915dc755012b5f77c34dcf029a584a03bf8.jpg)

![4c265a657d30a207a6f520780bb3e580cc2769168b1f57eab29a11bba5bbc5bc.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/4c265a657d30a207a6f520780bb3e580cc2769168b1f57eab29a11bba5bbc5bc.jpg)

![9edf4a265a8d8589712355432334d545898eeb61ed33d19c8b36d258821ef7ec.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/9edf4a265a8d8589712355432334d545898eeb61ed33d19c8b36d258821ef7ec.jpg)

![b4458b4922e0fb5717b7b891b2ad7017b9a9de612b51b04f93573533c602480b.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/b4458b4922e0fb5717b7b891b2ad7017b9a9de612b51b04f93573533c602480b.jpg)

![b9e9c9d488b1b3b560690f050f629c8003b32f050cb9c856bf871b13107fafeb.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/b9e9c9d488b1b3b560690f050f629c8003b32f050cb9c856bf871b13107fafeb.jpg)

![c399c52ef598d5e4b77919018ea661298d4efa3dabd0ff917933a788432b3eba.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/c399c52ef598d5e4b77919018ea661298d4efa3dabd0ff917933a788432b3eba.jpg)

![ea09d93b6e3ddd61da28479fefdfa6fc3f40c9c04acbc4ff67ebe162845c956e.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/ea09d93b6e3ddd61da28479fefdfa6fc3f40c9c04acbc4ff67ebe162845c956e.jpg)

![f18970451bfd5b5f4fd9ffc0cc0eaac6aa88184a3d81dd786e9c8e432f698698.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/f18970451bfd5b5f4fd9ffc0cc0eaac6aa88184a3d81dd786e9c8e432f698698.jpg)

![fae52744bb1b9935c8c22fc743ecfafa6e16f155427f3e59bc8b8825eed3df71.jpg](../nips_results/4552_HypoBootstrap_%20A%20Bootstrapping%20Framework%20for%20Inductive%20Reasoning/tables/fae52744bb1b9935c8c22fc743ecfafa6e16f155427f3e59bc8b8825eed3df71.jpg)

## LoTA-QAF: Lossless Ternary Adaptation for Quantization-Aware Fine-Tuning


### Images

![0ab9aa301e1c1ceec00be2f4ce21eef8b27faf14f824dd9d5e3e1e31a2b5c372.jpg](../nips_results/4553_LoTA-QAF_%20Lossless%20Ternary%20Adaptation%20for%20Quantization-Aware%20Fine-Tuning/images/0ab9aa301e1c1ceec00be2f4ce21eef8b27faf14f824dd9d5e3e1e31a2b5c372.jpg)

![256901e504e7d9abf045d255511d06326f624058110659a785a1b93351b4b909.jpg](../nips_results/4553_LoTA-QAF_%20Lossless%20Ternary%20Adaptation%20for%20Quantization-Aware%20Fine-Tuning/images/256901e504e7d9abf045d255511d06326f624058110659a785a1b93351b4b909.jpg)

![3108abfaec4f70a7d9cb348b0185720bbf21e4a60948d3c115e0db549418c41a.jpg](../nips_results/4553_LoTA-QAF_%20Lossless%20Ternary%20Adaptation%20for%20Quantization-Aware%20Fine-Tuning/images/3108abfaec4f70a7d9cb348b0185720bbf21e4a60948d3c115e0db549418c41a.jpg)

![3dd1271d399a6291e2799d666e827e0e00e84375f5e5a7a15db2cbd652e201cd.jpg](../nips_results/4553_LoTA-QAF_%20Lossless%20Ternary%20Adaptation%20for%20Quantization-Aware%20Fine-Tuning/images/3dd1271d399a6291e2799d666e827e0e00e84375f5e5a7a15db2cbd652e201cd.jpg)

![68acc9e1d4ac8b4063ad5dc0e80ceba8e0266adb118b85ed1614304f23caff72.jpg](../nips_results/4553_LoTA-QAF_%20Lossless%20Ternary%20Adaptation%20for%20Quantization-Aware%20Fine-Tuning/images/68acc9e1d4ac8b4063ad5dc0e80ceba8e0266adb118b85ed1614304f23caff72.jpg)

![6b9ae0257d08647e671cb9baba241c127d1d3557c7617a813f7e76e0b39599d9.jpg](../nips_results/4553_LoTA-QAF_%20Lossless%20Ternary%20Adaptation%20for%20Quantization-Aware%20Fine-Tuning/images/6b9ae0257d08647e671cb9baba241c127d1d3557c7617a813f7e76e0b39599d9.jpg)

### Tables

![aadb0c9292a07f431561601fbd51e64ee2867e95d4ffde26e96749c3d48397b7.jpg](../nips_results/4553_LoTA-QAF_%20Lossless%20Ternary%20Adaptation%20for%20Quantization-Aware%20Fine-Tuning/tables/aadb0c9292a07f431561601fbd51e64ee2867e95d4ffde26e96749c3d48397b7.jpg)

![da32a2e0c1af1292982c99e13811fe85482c4fafa0e4439374ac0394596a6826.jpg](../nips_results/4553_LoTA-QAF_%20Lossless%20Ternary%20Adaptation%20for%20Quantization-Aware%20Fine-Tuning/tables/da32a2e0c1af1292982c99e13811fe85482c4fafa0e4439374ac0394596a6826.jpg)

## Dual-Comb Ghost Imaging with Transformer-Based Reconstruction for Optical Fiber Endomicroscopy


### Images

![0d9c103d89a81d917fc45cc0d9238b26c10f2822e5ac8944db9ca94f9bb347f8.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/images/0d9c103d89a81d917fc45cc0d9238b26c10f2822e5ac8944db9ca94f9bb347f8.jpg)

![16065a48590232f44995d7442ef7b95aebe652d3b0efc18466c66610e730b9f2.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/images/16065a48590232f44995d7442ef7b95aebe652d3b0efc18466c66610e730b9f2.jpg)

![225a1d3df37856f27e0a4c83d2f7c1659a0e2482221a37b9158922478530191e.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/images/225a1d3df37856f27e0a4c83d2f7c1659a0e2482221a37b9158922478530191e.jpg)

![26d9e3a261ea28732920a8569988aae84145b03ef4daca815cd19ed47384a8f3.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/images/26d9e3a261ea28732920a8569988aae84145b03ef4daca815cd19ed47384a8f3.jpg)

![3a87b7331a7537e444fa7543c3a1de80dac2476edac74b6931657d6cb8b28fdb.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/images/3a87b7331a7537e444fa7543c3a1de80dac2476edac74b6931657d6cb8b28fdb.jpg)

![6954fced5f6c827575ec597dc45c797d4427e68e8f3078d4c39efceecd322640.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/images/6954fced5f6c827575ec597dc45c797d4427e68e8f3078d4c39efceecd322640.jpg)

![992212a4bfa20041a970eb8e05fb44934780541b4c6554159ee3fac11b69ae0b.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/images/992212a4bfa20041a970eb8e05fb44934780541b4c6554159ee3fac11b69ae0b.jpg)

![9bcf5c647b29e5c041e54b773ecb28c02c2e8780b3d5577f06eb7dbee94fb093.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/images/9bcf5c647b29e5c041e54b773ecb28c02c2e8780b3d5577f06eb7dbee94fb093.jpg)

![c7e23ee1b739cb73e114a42d9db10aabd4e8f411eea2dcbee0110b18c27e9f0f.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/images/c7e23ee1b739cb73e114a42d9db10aabd4e8f411eea2dcbee0110b18c27e9f0f.jpg)

![fea5479cd852cb83c4002099098ac657b1f6a8cbe47e8a788c635c06bbd57885.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/images/fea5479cd852cb83c4002099098ac657b1f6a8cbe47e8a788c635c06bbd57885.jpg)

### Tables

![2ef3c791529b385f355b9a7e0e5c2e1d84c2a4982b20e3fb974760e7ec5a6e2c.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/tables/2ef3c791529b385f355b9a7e0e5c2e1d84c2a4982b20e3fb974760e7ec5a6e2c.jpg)

![f7ee787f605cc77807fd15c1e6e69ce19f299808f2555f8071d1026a82c47909.jpg](../nips_results/4554_Dual-Comb%20Ghost%20Imaging%20with%20Transformer-Based%20Reconstruction%20for%20Optical%20Fiber%20Endomicroscopy/tables/f7ee787f605cc77807fd15c1e6e69ce19f299808f2555f8071d1026a82c47909.jpg)

## Object-Centric Concept-Bottlenecks


### Images

![07c2e8647a9f1e015b666d31a4ac64949f2487f385111905fa76102aff63f205.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/images/07c2e8647a9f1e015b666d31a4ac64949f2487f385111905fa76102aff63f205.jpg)

![3d747a5d47911330d93bbe94d2aef9a78508126d5d0a52f597f16a168d9ba974.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/images/3d747a5d47911330d93bbe94d2aef9a78508126d5d0a52f597f16a168d9ba974.jpg)

![694fe428d0bfe6dd830b219578add6569b1d06c2badab74dcf97dcb98b13f526.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/images/694fe428d0bfe6dd830b219578add6569b1d06c2badab74dcf97dcb98b13f526.jpg)

![6bf0dba9280cbd2633f6ef4d1c942178c4520d649f74ab1803399004b95eddb9.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/images/6bf0dba9280cbd2633f6ef4d1c942178c4520d649f74ab1803399004b95eddb9.jpg)

![9f5eb9d460af7466caf386712ab981aef38cce7972855a4e6e280a4cf9880639.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/images/9f5eb9d460af7466caf386712ab981aef38cce7972855a4e6e280a4cf9880639.jpg)

![b77cc3ddb2ec58636dc3229a8c6f7175ffbeec00dc0ccad17b5d77473958d1b1.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/images/b77cc3ddb2ec58636dc3229a8c6f7175ffbeec00dc0ccad17b5d77473958d1b1.jpg)

![ddcf1b9b8cf3d75528cf157d25102cca8eb327aa8840b24c79fd70e8b560086d.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/images/ddcf1b9b8cf3d75528cf157d25102cca8eb327aa8840b24c79fd70e8b560086d.jpg)

![f60aa83b88d7de96800d200a6ed4253062cdff89873089a5bb133b6b0fb5af55.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/images/f60aa83b88d7de96800d200a6ed4253062cdff89873089a5bb133b6b0fb5af55.jpg)

![ff9ab3c17b0b1932a84aaddd81ec9d3c2594a30ea68dad620db078f7e03f335d.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/images/ff9ab3c17b0b1932a84aaddd81ec9d3c2594a30ea68dad620db078f7e03f335d.jpg)

### Tables

![06222c01de1cc10e8a3c9552ca702894407cc6671e29bf4fab053b2b7ab7c16f.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/tables/06222c01de1cc10e8a3c9552ca702894407cc6671e29bf4fab053b2b7ab7c16f.jpg)

![0f92a4bc1439e0826e775d611aefc4b74b9e060bb255a9d2120c6771dadcdce0.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/tables/0f92a4bc1439e0826e775d611aefc4b74b9e060bb255a9d2120c6771dadcdce0.jpg)

![2346ebfe88a66e041aeb8c684f16198cd6c48557a9700baa10f02dbd7c77ba46.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/tables/2346ebfe88a66e041aeb8c684f16198cd6c48557a9700baa10f02dbd7c77ba46.jpg)

![428ec7690140692003d8d37685c73207ce365947dbc86b72d0640b184cfe5f62.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/tables/428ec7690140692003d8d37685c73207ce365947dbc86b72d0640b184cfe5f62.jpg)

![49e5c0949b1a2f3c7521c9c4d731e9b204d573dcf9b5721c8fd46ce4d22059e8.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/tables/49e5c0949b1a2f3c7521c9c4d731e9b204d573dcf9b5721c8fd46ce4d22059e8.jpg)

![57722db57cf414d413bb41e1a3dcbb87530dd7ad90f5682a44f283c10a4d501b.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/tables/57722db57cf414d413bb41e1a3dcbb87530dd7ad90f5682a44f283c10a4d501b.jpg)

![8b53c502d3165f52dc9b4bb17c69ccd384bcc3c0192d52a9d872372655cb6e91.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/tables/8b53c502d3165f52dc9b4bb17c69ccd384bcc3c0192d52a9d872372655cb6e91.jpg)

![c3f0fbc779de7e0655c990525c664d42c92b6b5c9977774a66aa272513443199.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/tables/c3f0fbc779de7e0655c990525c664d42c92b6b5c9977774a66aa272513443199.jpg)

![d839c1e97e929fef0315d3e9a9d280ef00ff59ea4da68227dc8f39535817f049.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/tables/d839c1e97e929fef0315d3e9a9d280ef00ff59ea4da68227dc8f39535817f049.jpg)

![edf295bed85b89ad107f205f68be4d8e1a24d4e114401756fec31d7e247f5299.jpg](../nips_results/4555_Object-Centric%20Concept-Bottlenecks/tables/edf295bed85b89ad107f205f68be4d8e1a24d4e114401756fec31d7e247f5299.jpg)

## Towards Pre-trained Graph Condensation via Optimal Transport


### Images

![04ccf9e86892b49fb9ab585d3704360a6ca6e567cc18d3c3378e3e575bc9ffc0.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/images/04ccf9e86892b49fb9ab585d3704360a6ca6e567cc18d3c3378e3e575bc9ffc0.jpg)

![43e63b401e2072e850f41cbeaee2635f49b290d3d112514f791e35b2e3af2f8c.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/images/43e63b401e2072e850f41cbeaee2635f49b290d3d112514f791e35b2e3af2f8c.jpg)

![5226cf5c0d1471a82e25193c593cb25c0e3f360db7ce9e6564f4e21f9b797be8.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/images/5226cf5c0d1471a82e25193c593cb25c0e3f360db7ce9e6564f4e21f9b797be8.jpg)

![5c7b6b32488462109e082264ea05550029dfcb93c1d5c138ad650aa92508c34b.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/images/5c7b6b32488462109e082264ea05550029dfcb93c1d5c138ad650aa92508c34b.jpg)

![872a34856130d82219ad8f8dbb2e41375243a3c50dbde82698fd657070d59df6.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/images/872a34856130d82219ad8f8dbb2e41375243a3c50dbde82698fd657070d59df6.jpg)

![d4a650da4f9cc5129d84c85fd9a3b8e5ad9d046ac06f91268ceb2a76df737bfc.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/images/d4a650da4f9cc5129d84c85fd9a3b8e5ad9d046ac06f91268ceb2a76df737bfc.jpg)

![d4de43e306423a1d7ddfd9797b6f922c60dc9bd332e656726e7ac224b951eead.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/images/d4de43e306423a1d7ddfd9797b6f922c60dc9bd332e656726e7ac224b951eead.jpg)

![d6788c347f3426ca843d6e2f648d10453b10f3cd3b7dfe88c23d27c1cacd207e.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/images/d6788c347f3426ca843d6e2f648d10453b10f3cd3b7dfe88c23d27c1cacd207e.jpg)

![e0deac8646436cc7c9a4ca81dc5a171d899c51d4b7483de0066c44b69708672e.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/images/e0deac8646436cc7c9a4ca81dc5a171d899c51d4b7483de0066c44b69708672e.jpg)

### Tables

![0f3a547e83cfe5b2a124423d1b324d8da5e6bece0a35b38e51fc7abaf555c494.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/0f3a547e83cfe5b2a124423d1b324d8da5e6bece0a35b38e51fc7abaf555c494.jpg)

![115756448084d061b4263b34033630ab51701507ff28cb8f35305a682e53b9cf.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/115756448084d061b4263b34033630ab51701507ff28cb8f35305a682e53b9cf.jpg)

![14b63563166bfc9105f99d4f4d8c2d228a53259242a490f9452c274ce1c86ade.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/14b63563166bfc9105f99d4f4d8c2d228a53259242a490f9452c274ce1c86ade.jpg)

![2804f296456b2ac9e438108b3d41668ebf01fdba45cb703a980bd38f695b984c.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/2804f296456b2ac9e438108b3d41668ebf01fdba45cb703a980bd38f695b984c.jpg)

![572b76790a23b8134255733e1c17f796aee020ebda847adf334d40202d78b105.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/572b76790a23b8134255733e1c17f796aee020ebda847adf334d40202d78b105.jpg)

![6031748a391c35207ae405bea955a4623d22a90b7aca50b26b1b6d3298e60bae.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/6031748a391c35207ae405bea955a4623d22a90b7aca50b26b1b6d3298e60bae.jpg)

![6c35f0623b291046c1d770a9d901d6837d123979702f0f734619c0e8d29fb9d9.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/6c35f0623b291046c1d770a9d901d6837d123979702f0f734619c0e8d29fb9d9.jpg)

![7fe226a56171abb0a55a4a18240a4c6c2cbb6c2176db6915cd097f022e94c6c7.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/7fe226a56171abb0a55a4a18240a4c6c2cbb6c2176db6915cd097f022e94c6c7.jpg)

![85a83fbc94fc2f1fb4e8cdef0a9fdd6e8ce61b91d3f993711b81f66ef882c3f9.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/85a83fbc94fc2f1fb4e8cdef0a9fdd6e8ce61b91d3f993711b81f66ef882c3f9.jpg)

![bcc3461359ebc4dbc50827a6b6d6f341e4d0a50d1a0b42225d4f22aca6fb7201.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/bcc3461359ebc4dbc50827a6b6d6f341e4d0a50d1a0b42225d4f22aca6fb7201.jpg)

![c45d17142c94004fa911e174f67800fab2325655ce634f26e572275b8a4c983a.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/c45d17142c94004fa911e174f67800fab2325655ce634f26e572275b8a4c983a.jpg)

![c47a89d858d5e9c752e677fbb567e9574d7c73b68f707af55c8f6236a36124af.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/c47a89d858d5e9c752e677fbb567e9574d7c73b68f707af55c8f6236a36124af.jpg)

![d4e3c58a976c905eee3e5e09e863d21a4c6dde500bb27629719160a07ba417b9.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/d4e3c58a976c905eee3e5e09e863d21a4c6dde500bb27629719160a07ba417b9.jpg)

![ff043cd0c6e0250a4f1b5414e1686285900ff0f5bb8b4e2711c13231d45bbace.jpg](../nips_results/4556_Towards%20Pre-trained%20Graph%20Condensation%20via%20Optimal%20Transport/tables/ff043cd0c6e0250a4f1b5414e1686285900ff0f5bb8b4e2711c13231d45bbace.jpg)

## Secure and Confidential Certificates of Online Fairness

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
