# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 15 of 130

## 目录 (Table of Contents)

1. [Win Fast or Lose Slow: Balancing Speed and Accuracy in Latency-Sensitive Decisions of LLMs](#Win-Fast-or-Lose-Slow-Balancing-Speed-and-Accuracy-in-Latency-Sensitive-Decisions-of-LLMs)
2. [Latent Policy Barrier: Learning Robust Visuomotor Policies by Staying In-Distribution](#Latent-Policy-Barrier-Learning-Robust-Visuomotor-Policies-by-Staying-In-Distribution)
3. [BayeSQP: Bayesian Optimization through Sequential Quadratic Programming](#BayeSQP-Bayesian-Optimization-through-Sequential-Quadratic-Programming)
4. [MoESD: Unveil Speculative Decoding's Potential for Accelerating Sparse MoE](#MoESD-Unveil-Speculative-Decodings-Potential-for-Accelerating-Sparse-MoE)
5. [Conditional Representation Learning for Customized Tasks](#Conditional-Representation-Learning-for-Customized-Tasks)
6. [Differentiable Decision Tree via "ReLU+Argmin" Reformulation](#Differentiable-Decision-Tree-via-ReLUArgmin-Reformulation)
7. [TGA: True-to-Geometry Avatar Dynamic Reconstruction](#TGA-True-to-Geometry-Avatar-Dynamic-Reconstruction)
8. [GeoSVR: Taming Sparse Voxels for Geometrically Accurate Surface Reconstruction](#GeoSVR-Taming-Sparse-Voxels-for-Geometrically-Accurate-Surface-Reconstruction)
9. [Predictive Preference Learning from Human Interventions](#Predictive-Preference-Learning-from-Human-Interventions)
10. [Polyline Path Masked Attention for Vision Transformer](#Polyline-Path-Masked-Attention-for-Vision-Transformer)
11. [Temperature is All You Need for Generalization in Langevin Dynamics and other Markov Processes](#Temperature-is-All-You-Need-for-Generalization-in-Langevin-Dynamics-and-other-Markov-Processes)
12. [Abstract Rendering:  Certified Rendering Under 3D Semantic Uncertainty](#Abstract-Rendering-Certified-Rendering-Under-3D-Semantic-Uncertainty)
13. [Controlling Thinking Speed in Reasoning Models](#Controlling-Thinking-Speed-in-Reasoning-Models)
14. [Enhancing Training Data Attribution with Representational Optimization](#Enhancing-Training-Data-Attribution-with-Representational-Optimization)
15. [The Graphon Limit Hypothesis: Understanding Neural Network Pruning via Infinite Width Analysis](#The-Graphon-Limit-Hypothesis-Understanding-Neural-Network-Pruning-via-Infinite-Width-Analysis)
16. [Tensor Product Attention Is All You Need](#Tensor-Product-Attention-Is-All-You-Need)
17. [The Power of Iterative Filtering for Supervised Learning with (Heavy) Contamination](#The-Power-of-Iterative-Filtering-for-Supervised-Learning-with-Heavy-Contamination)
18. [GSRF: Complex-Valued 3D Gaussian Splatting for Efficient Radio-Frequency Data Synthesis](#GSRF-Complex-Valued-3D-Gaussian-Splatting-for-Efficient-Radio-Frequency-Data-Synthesis)
19. [Deciphering the Extremes: A Novel Approach for Pathological Long-tailed Recognition in Scientific Discovery](#Deciphering-the-Extremes-A-Novel-Approach-for-Pathological-Long-tailed-Recognition-in-Scientific-Discovery)
20. [Zero-shot Denoising via Neural Compression: Theoretical and algorithmic framework](#Zero-shot-Denoising-via-Neural-Compression-Theoretical-and-algorithmic-framework)
21. [Bits Leaked per Query: Information-Theoretic Bounds for Adversarial Attacks on LLMs](#Bits-Leaked-per-Query-Information-Theoretic-Bounds-for-Adversarial-Attacks-on-LLMs)
22. [Decomposing stimulus-specific sensory neural information via diffusion models](#Decomposing-stimulus-specific-sensory-neural-information-via-diffusion-models)
23. [The Fragile Truth of Saliency: Improving LLM Input Attribution via Attention Bias Optimization](#The-Fragile-Truth-of-Saliency-Improving-LLM-Input-Attribution-via-Attention-Bias-Optimization)
24. [Think or Not? Exploring Thinking Efficiency in Large Reasoning Models via an Information-Theoretic Lens](#Think-or-Not-Exploring-Thinking-Efficiency-in-Large-Reasoning-Models-via-an-Information-Theoretic-Lens)
25. [Convergence Rates of Constrained Expected Improvement](#Convergence-Rates-of-Constrained-Expected-Improvement)
26. [Reinforcement Learning with Imperfect Transition Predictions: A Bellman-Jensen Approach](#Reinforcement-Learning-with-Imperfect-Transition-Predictions-A-Bellman-Jensen-Approach)
27. [SegMASt3R: Geometry Grounded Segment Matching](#SegMASt3R-Geometry-Grounded-Segment-Matching)
28. [Any-stepsize Gradient Descent for Separable Data under Fenchel–Young Losses](#Any-stepsize-Gradient-Descent-for-Separable-Data-under-FenchelYoung-Losses)
29. [Searching Latent Program Spaces](#Searching-Latent-Program-Spaces)
30. [Multi-Agent Learning under Uncertainty: Recurrence vs. Concentration](#Multi-Agent-Learning-under-Uncertainty-Recurrence-vs-Concentration)
31. [QFFT, Question-Free Fine-Tuning for Adaptive Reasoning](#QFFT-Question-Free-Fine-Tuning-for-Adaptive-Reasoning)
32. [DeepDiver: Adaptive Web-Search Intensity Scaling via Reinforcement Learning](#DeepDiver-Adaptive-Web-Search-Intensity-Scaling-via-Reinforcement-Learning)
33. [IA-GGAD: Zero-shot Generalist Graph Anomaly Detection via Invariant and Affinity Learning](#IA-GGAD-Zero-shot-Generalist-Graph-Anomaly-Detection-via-Invariant-and-Affinity-Learning)
34. [Mean-Field Sampling for Cooperative Multi-Agent Reinforcement Learning](#Mean-Field-Sampling-for-Cooperative-Multi-Agent-Reinforcement-Learning)
35. [Scalable Fingerprinting of Large Language Models](#Scalable-Fingerprinting-of-Large-Language-Models)
36. [LABridge: Text–Image Latent Alignment Framework via Mean-Conditioned OU Process](#LABridge-TextImage-Latent-Alignment-Framework-via-Mean-Conditioned-OU-Process)
37. [Emergence and Evolution of Interpretable Concepts in Diffusion Models](#Emergence-and-Evolution-of-Interpretable-Concepts-in-Diffusion-Models)
38. [Dual Data Alignment Makes AI-Generated Image Detector Easier Generalizable](#Dual-Data-Alignment-Makes-AI-Generated-Image-Detector-Easier-Generalizable)
39. [An Analysis of Causal Effect Estimation using Outcome Invariant Data Augmentation](#An-Analysis-of-Causal-Effect-Estimation-using-Outcome-Invariant-Data-Augmentation)
40. [DMWM: Dual-Mind World Model with Long-Term Imagination](#DMWM-Dual-Mind-World-Model-with-Long-Term-Imagination)
41. [Selective Omniprediction and Fair Abstention](#Selective-Omniprediction-and-Fair-Abstention)

---


## Win Fast or Lose Slow: Balancing Speed and Accuracy in Latency-Sensitive Decisions of LLMs

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

## Win Fast or Lose Slow: Balancing Speed and Accuracy in Latency-Sensitive Decisions of LLMs


### Images

![8e3fac48f628975a94aeaecac74819023d62612a6d60eba766d0071c22da8776.jpg](../nips_results/591_Win%20Fast%20or%20Lose%20Slow_%20Balancing%20Speed%20and%20Accuracy%20in%20Latency-Sensitive%20Decisions%20of%20LLMs/images/8e3fac48f628975a94aeaecac74819023d62612a6d60eba766d0071c22da8776.jpg)

![bb1b892fd6f2ec27a918dd694cf3d280b8f2a0bb663cbe196f4ca64452aa80f2.jpg](../nips_results/591_Win%20Fast%20or%20Lose%20Slow_%20Balancing%20Speed%20and%20Accuracy%20in%20Latency-Sensitive%20Decisions%20of%20LLMs/images/bb1b892fd6f2ec27a918dd694cf3d280b8f2a0bb663cbe196f4ca64452aa80f2.jpg)

![bb4d8ff7f4df6601aa30111a42c50e1d01262e66bb544e6b2c0a5cf32153eb88.jpg](../nips_results/591_Win%20Fast%20or%20Lose%20Slow_%20Balancing%20Speed%20and%20Accuracy%20in%20Latency-Sensitive%20Decisions%20of%20LLMs/images/bb4d8ff7f4df6601aa30111a42c50e1d01262e66bb544e6b2c0a5cf32153eb88.jpg)

![e9544d4005de3a6f851bf8e98b0853af1d9c6b13144a8068fef8e0b583471871.jpg](../nips_results/591_Win%20Fast%20or%20Lose%20Slow_%20Balancing%20Speed%20and%20Accuracy%20in%20Latency-Sensitive%20Decisions%20of%20LLMs/images/e9544d4005de3a6f851bf8e98b0853af1d9c6b13144a8068fef8e0b583471871.jpg)

### Tables

![09b872831e746b245c0424019e84d9256fb583bff14b74556056156219fc85b8.jpg](../nips_results/591_Win%20Fast%20or%20Lose%20Slow_%20Balancing%20Speed%20and%20Accuracy%20in%20Latency-Sensitive%20Decisions%20of%20LLMs/tables/09b872831e746b245c0424019e84d9256fb583bff14b74556056156219fc85b8.jpg)

![1c297453be177bfb3331889736f0917de9255d9bb5cf6e457ab7e5fd65b97703.jpg](../nips_results/591_Win%20Fast%20or%20Lose%20Slow_%20Balancing%20Speed%20and%20Accuracy%20in%20Latency-Sensitive%20Decisions%20of%20LLMs/tables/1c297453be177bfb3331889736f0917de9255d9bb5cf6e457ab7e5fd65b97703.jpg)

![7a63bd1ebcbf8f5746ee2626fcb6d345cf16e0770d968da77cde33893f3f489f.jpg](../nips_results/591_Win%20Fast%20or%20Lose%20Slow_%20Balancing%20Speed%20and%20Accuracy%20in%20Latency-Sensitive%20Decisions%20of%20LLMs/tables/7a63bd1ebcbf8f5746ee2626fcb6d345cf16e0770d968da77cde33893f3f489f.jpg)

![7e38e7591a11ee0c1fc539d814b0168eff48da80eba9a21c5f8d30f0e8d5a0e8.jpg](../nips_results/591_Win%20Fast%20or%20Lose%20Slow_%20Balancing%20Speed%20and%20Accuracy%20in%20Latency-Sensitive%20Decisions%20of%20LLMs/tables/7e38e7591a11ee0c1fc539d814b0168eff48da80eba9a21c5f8d30f0e8d5a0e8.jpg)

![9a16f065685a6fd6da27c2357c72e7a82c2de212a4b667c1fe0a70cd7a5e1416.jpg](../nips_results/591_Win%20Fast%20or%20Lose%20Slow_%20Balancing%20Speed%20and%20Accuracy%20in%20Latency-Sensitive%20Decisions%20of%20LLMs/tables/9a16f065685a6fd6da27c2357c72e7a82c2de212a4b667c1fe0a70cd7a5e1416.jpg)

## Latent Policy Barrier: Learning Robust Visuomotor Policies by Staying In-Distribution


### Images

![154e8b660dcfa028e1aaa6d78d538f968a78bd0cffcc10827f2c6c38f382dd08.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/images/154e8b660dcfa028e1aaa6d78d538f968a78bd0cffcc10827f2c6c38f382dd08.jpg)

![20f08bb21d861c623c0039e5de263b4d755803d00f151ec1aec24e8e3a7fae1c.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/images/20f08bb21d861c623c0039e5de263b4d755803d00f151ec1aec24e8e3a7fae1c.jpg)

![25990b7a52eed973c674a555da244f0c28468dc27d8ab729ccfc1d8dc5bd91a7.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/images/25990b7a52eed973c674a555da244f0c28468dc27d8ab729ccfc1d8dc5bd91a7.jpg)

![3a07142ba91b8acfacd5d7e0478c134a0119a9e8379ae35ac9b63acb746f44d9.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/images/3a07142ba91b8acfacd5d7e0478c134a0119a9e8379ae35ac9b63acb746f44d9.jpg)

![6c1dfa260b21e23b9afa9836d00f9d61035f017709e36054d81b6884f41f5106.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/images/6c1dfa260b21e23b9afa9836d00f9d61035f017709e36054d81b6884f41f5106.jpg)

![78e58bd640f93af083f1f193803cc19d1a345138949d04f93dbcd7b740291ec8.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/images/78e58bd640f93af083f1f193803cc19d1a345138949d04f93dbcd7b740291ec8.jpg)

![83271ebd3e3cabe0e6e9ad652cbc824614286690bc3845eb5b7dd558776fe6b3.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/images/83271ebd3e3cabe0e6e9ad652cbc824614286690bc3845eb5b7dd558776fe6b3.jpg)

![c645890d12d357bb2b902b0b18555f8ddadd1583c734b11b08183e0d3f2d6a6e.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/images/c645890d12d357bb2b902b0b18555f8ddadd1583c734b11b08183e0d3f2d6a6e.jpg)

![dd2e291ff51fa6df36528c0ed5489d131b2e0b8100174d87711bfa75a4f664ce.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/images/dd2e291ff51fa6df36528c0ed5489d131b2e0b8100174d87711bfa75a4f664ce.jpg)

![eef9bee97f4cafc131271d98a88abb1d072352b0b36c7648748f0846cc62b628.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/images/eef9bee97f4cafc131271d98a88abb1d072352b0b36c7648748f0846cc62b628.jpg)

![facb4aace8e1ffea68a51880930d97e887a662a5fbee4e6ecff3581ffd235a21.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/images/facb4aace8e1ffea68a51880930d97e887a662a5fbee4e6ecff3581ffd235a21.jpg)

### Tables

![10570b041fd42b1216bf5a663c35af4adeeb8f96ce58f9029c8ef580887acbbf.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/tables/10570b041fd42b1216bf5a663c35af4adeeb8f96ce58f9029c8ef580887acbbf.jpg)

![1a1bac5b09a0f9cfeb1a9ce59aed60626df9c945845762258613672cbde5e4da.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/tables/1a1bac5b09a0f9cfeb1a9ce59aed60626df9c945845762258613672cbde5e4da.jpg)

![1d25c1953e8227db97452625b96f9eeed999168d58965d033d0e06b6bec3a0bd.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/tables/1d25c1953e8227db97452625b96f9eeed999168d58965d033d0e06b6bec3a0bd.jpg)

![2bba432df588cb15d5fc1eb58810b9334c585bb796809185c8de1c2e4925fbd4.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/tables/2bba432df588cb15d5fc1eb58810b9334c585bb796809185c8de1c2e4925fbd4.jpg)

![806200341e2a501a6d03e6728e793fecfaf508a265be1be5700fd35a83b1e323.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/tables/806200341e2a501a6d03e6728e793fecfaf508a265be1be5700fd35a83b1e323.jpg)

![de6246ffff0c7b596c50517c0f153b7858e26daf20b4f0b14d09e600b89d6688.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/tables/de6246ffff0c7b596c50517c0f153b7858e26daf20b4f0b14d09e600b89d6688.jpg)

![e4ebce79e9c6445d0076426c6828b745bd6bb700616a23ee30e07a923e49f3b1.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/tables/e4ebce79e9c6445d0076426c6828b745bd6bb700616a23ee30e07a923e49f3b1.jpg)

![f264a364fb3a8e64dcd3822ba02aeb26b0bdb8935a28ef63908ff490c2dbe3de.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/tables/f264a364fb3a8e64dcd3822ba02aeb26b0bdb8935a28ef63908ff490c2dbe3de.jpg)

![f278a59d31f37ee0a4076bbe593935523c7460a9bd65166ac350a5361c6edcb0.jpg](../nips_results/592_Latent%20Policy%20Barrier_%20Learning%20Robust%20Visuomotor%20Policies%20by%20Staying%20In-Distribution/tables/f278a59d31f37ee0a4076bbe593935523c7460a9bd65166ac350a5361c6edcb0.jpg)

## BayeSQP: Bayesian Optimization through Sequential Quadratic Programming


### Images

![3037ee275ded04570d6f124966aef362db671c68c68705f051a4d7f1f8d4d40d.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/images/3037ee275ded04570d6f124966aef362db671c68c68705f051a4d7f1f8d4d40d.jpg)

![5d6dd62b91b224fceb058f66aade541b39031a226f16c9674649a5c9b9ac07d7.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/images/5d6dd62b91b224fceb058f66aade541b39031a226f16c9674649a5c9b9ac07d7.jpg)

![5e0cc16177d4d4f9f5fee29b9f34a71253b8c71199eaa2a88791680d1b1a249a.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/images/5e0cc16177d4d4f9f5fee29b9f34a71253b8c71199eaa2a88791680d1b1a249a.jpg)

![62197cd3270b279ca4c6b2e086d58aebb3ed2126361dbf1f3ed3a22d7304032c.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/images/62197cd3270b279ca4c6b2e086d58aebb3ed2126361dbf1f3ed3a22d7304032c.jpg)

![8cf22d4f3ac2efee02c97565bd6e5c1fec101aff97cec285cccfc7fd79fba855.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/images/8cf22d4f3ac2efee02c97565bd6e5c1fec101aff97cec285cccfc7fd79fba855.jpg)

![9228a577453aa30a8acc5098c94151c369b7caeb6dc2ca314df8fe1ed0dcfccf.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/images/9228a577453aa30a8acc5098c94151c369b7caeb6dc2ca314df8fe1ed0dcfccf.jpg)

![9369d4d7fb8f5c129810bde8c0789dbd1bc134db8a0934b26ab438b9708fe556.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/images/9369d4d7fb8f5c129810bde8c0789dbd1bc134db8a0934b26ab438b9708fe556.jpg)

![9adae52674ed85514d0035df2b2e88513cae21c17f2370b22f5fb6cba95a5454.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/images/9adae52674ed85514d0035df2b2e88513cae21c17f2370b22f5fb6cba95a5454.jpg)

![d4739a5b1d27cb4fb61f3f56bf63e652abf903bf6e264798f744ddc7a1db37e5.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/images/d4739a5b1d27cb4fb61f3f56bf63e652abf903bf6e264798f744ddc7a1db37e5.jpg)

![e44911803c8acce52aac5388af70b43c6df04de0458807395f0904fd7326ff04.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/images/e44911803c8acce52aac5388af70b43c6df04de0458807395f0904fd7326ff04.jpg)

### Tables

![00747fd3a8405d8bb5ca4b5bfd38a054d878aee7710e7568fd3c5f64512d800e.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/tables/00747fd3a8405d8bb5ca4b5bfd38a054d878aee7710e7568fd3c5f64512d800e.jpg)

![16d39a51cc6835978d287e79e2428c3cec4a86eea68263aaaed47b9823230083.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/tables/16d39a51cc6835978d287e79e2428c3cec4a86eea68263aaaed47b9823230083.jpg)

![58dee6b324fe2b5e1b9eaa8b118f2ba29c495e41e8fde70fff6987774c7dbac0.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/tables/58dee6b324fe2b5e1b9eaa8b118f2ba29c495e41e8fde70fff6987774c7dbac0.jpg)

![f5ffac8cbae8dbbf61698d4c784c648b0b49feffb5dcfa7942890d578469c723.jpg](../nips_results/593_BayeSQP_%20Bayesian%20Optimization%20through%20Sequential%20Quadratic%20Programming/tables/f5ffac8cbae8dbbf61698d4c784c648b0b49feffb5dcfa7942890d578469c723.jpg)

## MoESD: Unveil Speculative Decoding's Potential for Accelerating Sparse MoE


### Images

![0463fd44cec60467cf764fa78841b8cee31e925a94765fc9107166f5dd0ccf99.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/0463fd44cec60467cf764fa78841b8cee31e925a94765fc9107166f5dd0ccf99.jpg)

![0509d3d95f106548453614a11a2e168488c6b530147da21679f8f91534f0b2ef.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/0509d3d95f106548453614a11a2e168488c6b530147da21679f8f91534f0b2ef.jpg)

![08e00331ae6190ef55b72573c7271a2f6cb739850fd96d06a1b7cdcd605fb221.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/08e00331ae6190ef55b72573c7271a2f6cb739850fd96d06a1b7cdcd605fb221.jpg)

![1af2cc3d9f3892fae1993e0acbd9d849c4b5e47e084704e54b526ef09c9902f6.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/1af2cc3d9f3892fae1993e0acbd9d849c4b5e47e084704e54b526ef09c9902f6.jpg)

![1b8dbfcae99f4cb933637fd20cebb589704b3ded3c634f744896c54cf82a103d.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/1b8dbfcae99f4cb933637fd20cebb589704b3ded3c634f744896c54cf82a103d.jpg)

![1e5454de75ee4940cec0f9ed479a3934485ac0b9d2e5501e0cdad9f885897f2d.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/1e5454de75ee4940cec0f9ed479a3934485ac0b9d2e5501e0cdad9f885897f2d.jpg)

![345e404e153421978b22976ea6f4c84b840959aa404566d382e7d3380eaf6466.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/345e404e153421978b22976ea6f4c84b840959aa404566d382e7d3380eaf6466.jpg)

![34ca8eb3bbe15fa55ef3af9588b6de2c6734933db8f4ed5f1e716a9e521c6c81.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/34ca8eb3bbe15fa55ef3af9588b6de2c6734933db8f4ed5f1e716a9e521c6c81.jpg)

![40ef984c8e820cb56f1d7defaa2f0a487913ff16a7557e96d4c59f0c103a212d.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/40ef984c8e820cb56f1d7defaa2f0a487913ff16a7557e96d4c59f0c103a212d.jpg)

![4189e0d3bc6d7523f48d104baa6635d2ea2d479f24e61e92f589c676ba472240.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/4189e0d3bc6d7523f48d104baa6635d2ea2d479f24e61e92f589c676ba472240.jpg)

![4fd6988df453ee926e5f29e94ab1a3fd0866a0c6b141363e0660e74ed2c0d463.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/4fd6988df453ee926e5f29e94ab1a3fd0866a0c6b141363e0660e74ed2c0d463.jpg)

![596cbf489c287b5fccf54f79b692ff414775b86514b8ee20787ecad274ce19d5.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/596cbf489c287b5fccf54f79b692ff414775b86514b8ee20787ecad274ce19d5.jpg)

![5fb0000d7d3db784b618d63a4ef38eb24e1f8b65778f9813cfaed5ebf5416d12.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/5fb0000d7d3db784b618d63a4ef38eb24e1f8b65778f9813cfaed5ebf5416d12.jpg)

![65e1d66f1f52fdae5773712f4fc2b9223e8accc917e1deb4bd2ea62bdbf939d0.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/65e1d66f1f52fdae5773712f4fc2b9223e8accc917e1deb4bd2ea62bdbf939d0.jpg)

![682aa1ec1fa2da5e1861d1878bad33be1d18975a5ecc5581c7683d02aef52339.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/682aa1ec1fa2da5e1861d1878bad33be1d18975a5ecc5581c7683d02aef52339.jpg)

![6fc67a9d4e7aa8af921add5a2a8eb48b6363bb0657f816e3b1075dbccd12cd96.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/6fc67a9d4e7aa8af921add5a2a8eb48b6363bb0657f816e3b1075dbccd12cd96.jpg)

![76728abd18be1cf7c422136586946fabc67012b9169f81d66a585658ca1f234e.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/76728abd18be1cf7c422136586946fabc67012b9169f81d66a585658ca1f234e.jpg)

![77f9a48d229a639492a665f243db74c4d0474c1a4cbc30f402298935687c0790.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/77f9a48d229a639492a665f243db74c4d0474c1a4cbc30f402298935687c0790.jpg)

![7aaf648677e7d7d1365b9cfa3950c19b223cfe19be7e3781021ddbc0ab0544f4.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/7aaf648677e7d7d1365b9cfa3950c19b223cfe19be7e3781021ddbc0ab0544f4.jpg)

![7d671a1f8260f9a8718f3a081b2d2d103b8ac4cce4e45a13de168513d9a0725b.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/7d671a1f8260f9a8718f3a081b2d2d103b8ac4cce4e45a13de168513d9a0725b.jpg)

![8dfc2012d271aa0036f4dae7634364e98f519092b3ad24b1866d43b6f749ba63.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/8dfc2012d271aa0036f4dae7634364e98f519092b3ad24b1866d43b6f749ba63.jpg)

![c2ea5f488eafd7c641198bfb7ea7f2d7566663bf8c7875f33ee3d7f8ae62f405.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/c2ea5f488eafd7c641198bfb7ea7f2d7566663bf8c7875f33ee3d7f8ae62f405.jpg)

![e84e231dbbabacca9ee6428a2fcf52539b997e1273fbc243ac9685002756e9bb.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/e84e231dbbabacca9ee6428a2fcf52539b997e1273fbc243ac9685002756e9bb.jpg)

![ec4ae194f48097e9c5eb9b8c9107b2049bf55cb6456dadebf7d3262911ababef.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/ec4ae194f48097e9c5eb9b8c9107b2049bf55cb6456dadebf7d3262911ababef.jpg)

![eeaf9750e3d193bb9bd15d5399e26c070cd9100205409f99c896de47c7bdf35f.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/eeaf9750e3d193bb9bd15d5399e26c070cd9100205409f99c896de47c7bdf35f.jpg)

![efdc23912c45f24762501a442dfcb95637c38ac5bb3d2bfb3b625f99c7306111.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/efdc23912c45f24762501a442dfcb95637c38ac5bb3d2bfb3b625f99c7306111.jpg)

![f384a858169f4c06e816acfdd0971e4f032dc579013cae10e7e5b3c1f83e65ec.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/f384a858169f4c06e816acfdd0971e4f032dc579013cae10e7e5b3c1f83e65ec.jpg)

![fabf312d354cb30d7c14340046706b55cf1991edd5db783342c62b450f2fff0e.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/images/fabf312d354cb30d7c14340046706b55cf1991edd5db783342c62b450f2fff0e.jpg)

### Tables

![0f84558ae87ad6d495d6d0b2ca0a6420e9e6e9c5c047845b0f2e6fb727f2fd8e.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/tables/0f84558ae87ad6d495d6d0b2ca0a6420e9e6e9c5c047845b0f2e6fb727f2fd8e.jpg)

![8adbbd7d3a054f54e4da6118bd1bb8562de3ad1af4d092c759a59150a8d471bf.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/tables/8adbbd7d3a054f54e4da6118bd1bb8562de3ad1af4d092c759a59150a8d471bf.jpg)

![fc5539a5023a3b6239e9395aec602dd7e83bcf20c7d451ab11682fff2855a65f.jpg](../nips_results/594_MoESD_%20Unveil%20Speculative%20Decoding%27s%20Potential%20for%20Accelerating%20Sparse%20MoE/tables/fc5539a5023a3b6239e9395aec602dd7e83bcf20c7d451ab11682fff2855a65f.jpg)

## Conditional Representation Learning for Customized Tasks


### Images

![0492a17d9cfa65cd17171a371e1b75845a9d8801257ce4467cd708bb0fed6f39.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/images/0492a17d9cfa65cd17171a371e1b75845a9d8801257ce4467cd708bb0fed6f39.jpg)

![0890458f2b97f3bd8a4d5f3b4d5628e38f386012354368fa95095ec870f37282.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/images/0890458f2b97f3bd8a4d5f3b4d5628e38f386012354368fa95095ec870f37282.jpg)

![53ea4be4744ca5588aa292d98a6be970c62423d85a891dd11418e4733b025a4b.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/images/53ea4be4744ca5588aa292d98a6be970c62423d85a891dd11418e4733b025a4b.jpg)

![666c22fddd72bc91d56138be0bdf7b9775346b703f41d95d56afd65b0eb8223d.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/images/666c22fddd72bc91d56138be0bdf7b9775346b703f41d95d56afd65b0eb8223d.jpg)

![6afb290733bcb96f77a90a3fea807939ef0c774d1f1fc2dfb88198ca720efc26.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/images/6afb290733bcb96f77a90a3fea807939ef0c774d1f1fc2dfb88198ca720efc26.jpg)

![8c10fb4b08a8249c732b645e91f84355c5655eb193ec567e7c3fdce7da07bf6f.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/images/8c10fb4b08a8249c732b645e91f84355c5655eb193ec567e7c3fdce7da07bf6f.jpg)

![99cf1d2fbff3abda06dea23d350877f538c18b64f8f89a98b7054201337c567d.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/images/99cf1d2fbff3abda06dea23d350877f538c18b64f8f89a98b7054201337c567d.jpg)

![ccf162a3028ab1d09cedb283613ac5da14e245661bd19f1ff94eed50c846bc7a.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/images/ccf162a3028ab1d09cedb283613ac5da14e245661bd19f1ff94eed50c846bc7a.jpg)

![d8c84bafadbdd4c8d46b3584dd31b7f3b6d903c3664d6aacb191fd934930b107.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/images/d8c84bafadbdd4c8d46b3584dd31b7f3b6d903c3664d6aacb191fd934930b107.jpg)

![f4db3cc6616e8ca591e209f2921d6a7c9b597aab1cdd11e4e47be160a3e6e546.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/images/f4db3cc6616e8ca591e209f2921d6a7c9b597aab1cdd11e4e47be160a3e6e546.jpg)

### Tables

![1352fc750154a5197f0a297e6854b031ab5533aa20c17ff8a6077505276a6d71.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/1352fc750154a5197f0a297e6854b031ab5533aa20c17ff8a6077505276a6d71.jpg)

![3765e3bb1b430e454169531e881717590633019810b1b867ebad6fdba1e01213.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/3765e3bb1b430e454169531e881717590633019810b1b867ebad6fdba1e01213.jpg)

![42c18677018fcc43e7a71520dd79c110ff271660df7bc109cb304007bfc7a2d9.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/42c18677018fcc43e7a71520dd79c110ff271660df7bc109cb304007bfc7a2d9.jpg)

![4ac6e0bf617fb075f6de832aa8640c7887a5a18c02f136f9f3d9565a755c9de4.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/4ac6e0bf617fb075f6de832aa8640c7887a5a18c02f136f9f3d9565a755c9de4.jpg)

![7afc5246e9fce35cbf3b820621dc2b643ce129024f739266497b2247917f9fc8.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/7afc5246e9fce35cbf3b820621dc2b643ce129024f739266497b2247917f9fc8.jpg)

![84f4b6b885d6f40e23fccca7a3513759929eaa69d8fcc0b8ae27d6b1f38b2bfc.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/84f4b6b885d6f40e23fccca7a3513759929eaa69d8fcc0b8ae27d6b1f38b2bfc.jpg)

![89bed7217afbb1ea2e0e9a6c2c3f2f3bb855439aed2724dbfc0f14811f2edb98.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/89bed7217afbb1ea2e0e9a6c2c3f2f3bb855439aed2724dbfc0f14811f2edb98.jpg)

![8f5667a75df67b4499fab2c4adbd4e2b07d41a9a8203d0428f4a17f8c23d7b85.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/8f5667a75df67b4499fab2c4adbd4e2b07d41a9a8203d0428f4a17f8c23d7b85.jpg)

![9250253ffb6b26d6207385199f4b91e9509dacdf4e8b5b38a6de006ceb0155bd.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/9250253ffb6b26d6207385199f4b91e9509dacdf4e8b5b38a6de006ceb0155bd.jpg)

![9d8d9b5bbdc55fd2bd55b6c46e67c872ac8c78cd77082e1250ed55b5324e35a4.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/9d8d9b5bbdc55fd2bd55b6c46e67c872ac8c78cd77082e1250ed55b5324e35a4.jpg)

![bdb843fc9a8a12da772787f999c97d746c6fd57f3941cb8b3ece21994389904a.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/bdb843fc9a8a12da772787f999c97d746c6fd57f3941cb8b3ece21994389904a.jpg)

![d163a44f1b776b4cf1564994abee97dafee93738a99b048103e75e4dd48ad4c3.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/d163a44f1b776b4cf1564994abee97dafee93738a99b048103e75e4dd48ad4c3.jpg)

![dfcf2049732c5b4a4e3b56d2dc99e7e278349a3072109229a3a78694dbadef1b.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/dfcf2049732c5b4a4e3b56d2dc99e7e278349a3072109229a3a78694dbadef1b.jpg)

![f368feec5bc52cf9e7347e23fe8094c7d6085e49998a83e0a464c6b0d6fbbfac.jpg](../nips_results/595_Conditional%20Representation%20Learning%20for%20Customized%20Tasks/tables/f368feec5bc52cf9e7347e23fe8094c7d6085e49998a83e0a464c6b0d6fbbfac.jpg)

## Differentiable Decision Tree via "ReLU+Argmin" Reformulation


### Images

![08193022c368f41275a5329ea2c535e7c1278a9a0fd215baee1a9a95878402fb.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/images/08193022c368f41275a5329ea2c535e7c1278a9a0fd215baee1a9a95878402fb.jpg)

![1c9511d7a5c0d20b0a82c91cca199c36c75c399f857cbc5d1eebbf454947b1f3.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/images/1c9511d7a5c0d20b0a82c91cca199c36c75c399f857cbc5d1eebbf454947b1f3.jpg)

![5530082026788e9b0da09be6c7db3e5218ccbc8f1e828a8545a931b31ecbe726.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/images/5530082026788e9b0da09be6c7db3e5218ccbc8f1e828a8545a931b31ecbe726.jpg)

![7548d8904a046db805bfc3e879d0e80bc9eab16fa9f706e5a249f7f0e5ff892e.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/images/7548d8904a046db805bfc3e879d0e80bc9eab16fa9f706e5a249f7f0e5ff892e.jpg)

![891da5ff69f9f060a4ffe8ce6f7927b349bc18fe14d0b34c795d0dfb2fa63b30.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/images/891da5ff69f9f060a4ffe8ce6f7927b349bc18fe14d0b34c795d0dfb2fa63b30.jpg)

![96c23e25a8b7b47a2cf9ad6193d8fd0b0dd96f9f5d7dc53e0d659ec1aee44270.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/images/96c23e25a8b7b47a2cf9ad6193d8fd0b0dd96f9f5d7dc53e0d659ec1aee44270.jpg)

![9d62718f56d837ac107d1d99efb0b118b19c70418e7ac1354d99d18f9e6c469a.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/images/9d62718f56d837ac107d1d99efb0b118b19c70418e7ac1354d99d18f9e6c469a.jpg)

### Tables

![008dd40cd715c74922d8172dd64267ef32dc9735d50010f6d4396150eb524689.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/008dd40cd715c74922d8172dd64267ef32dc9735d50010f6d4396150eb524689.jpg)

![06d69dee20187c4c41ad44306b49acdd278c81cec2aed10af927e741a749a411.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/06d69dee20187c4c41ad44306b49acdd278c81cec2aed10af927e741a749a411.jpg)

![14ed4a7a3a221ec1dfe3208ee3b072d91b14bf8855f6cacdd46013c7add3350a.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/14ed4a7a3a221ec1dfe3208ee3b072d91b14bf8855f6cacdd46013c7add3350a.jpg)

![1f09c636331c1bc15aaff20a2b82bba9d75cf1ac18df776d8b0dd35f4fd2a9c4.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/1f09c636331c1bc15aaff20a2b82bba9d75cf1ac18df776d8b0dd35f4fd2a9c4.jpg)

![3f62e3faf8f4c802fe9963e6fcc36bfe93f12d5a23dfb1158144ce6ae04011f1.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/3f62e3faf8f4c802fe9963e6fcc36bfe93f12d5a23dfb1158144ce6ae04011f1.jpg)

![4869414e7d61358d16293b562b9b040c8162372edac028bdb1a783e65425c17e.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/4869414e7d61358d16293b562b9b040c8162372edac028bdb1a783e65425c17e.jpg)

![55c5a4c7c94028cfe48520f28b0ae95c378f6592a6ffc4c84023439031f74092.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/55c5a4c7c94028cfe48520f28b0ae95c378f6592a6ffc4c84023439031f74092.jpg)

![60aba5c4b11951f2a03b760fe67d32063032707c9364eea325bcd52d296a56aa.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/60aba5c4b11951f2a03b760fe67d32063032707c9364eea325bcd52d296a56aa.jpg)

![70b43f76e053f6b5b4e9e61d8c7b07b1ef4bc8fe3fa6ca4c6e12a597d75893e5.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/70b43f76e053f6b5b4e9e61d8c7b07b1ef4bc8fe3fa6ca4c6e12a597d75893e5.jpg)

![80a9089a8d8658105df1feb9b1470f13ea9958480364b60222a1570b0d5f6bca.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/80a9089a8d8658105df1feb9b1470f13ea9958480364b60222a1570b0d5f6bca.jpg)

![a790b91989367570c477ae1124d05ff5a2ce65e75866480e2a56b2e34b8a8750.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/a790b91989367570c477ae1124d05ff5a2ce65e75866480e2a56b2e34b8a8750.jpg)

![a95793404633713fda0aac11eaa389d30dd3d057a51c11d14acd041d3785d3bd.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/a95793404633713fda0aac11eaa389d30dd3d057a51c11d14acd041d3785d3bd.jpg)

![b2519345b43fd4d855606c2a20b3c404264dca6e306ef86da81a503a7951debf.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/b2519345b43fd4d855606c2a20b3c404264dca6e306ef86da81a503a7951debf.jpg)

![b9726a91e978ab9fcff193459516c8cd95dd07558a5ba78686ce2e8c77cf195f.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/b9726a91e978ab9fcff193459516c8cd95dd07558a5ba78686ce2e8c77cf195f.jpg)

![bd2c473974fd8aeda5cb26d51eef1ddbb1c6b7cd11bbe0cb69cd94882c1a096a.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/bd2c473974fd8aeda5cb26d51eef1ddbb1c6b7cd11bbe0cb69cd94882c1a096a.jpg)

![c132489d355b906d890537297563a49d6227ce4919443dfa889a18324dca5421.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/c132489d355b906d890537297563a49d6227ce4919443dfa889a18324dca5421.jpg)

![c816ced2e6f5747e57efcbc4464fc550e1609dcb05c9b14ab27f18fff7c11d0c.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/c816ced2e6f5747e57efcbc4464fc550e1609dcb05c9b14ab27f18fff7c11d0c.jpg)

![c8d8efd5fb70bfe49810bf8349700a02b2fa325a1c548f96731023c545ee74fc.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/c8d8efd5fb70bfe49810bf8349700a02b2fa325a1c548f96731023c545ee74fc.jpg)

![cea73bf0bc38df64d1161f0f112893caa0a06f79c162a3c9c4ce3e1767f76143.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/cea73bf0bc38df64d1161f0f112893caa0a06f79c162a3c9c4ce3e1767f76143.jpg)

![d3abe2a20f4b6193f337607ee356e8799eb38f2c507847d1cf07d205a4312f4f.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/d3abe2a20f4b6193f337607ee356e8799eb38f2c507847d1cf07d205a4312f4f.jpg)

![d4194b23ab4b912967f1bf7ea4d2033a15c066a095b528c93f75a8cc22c0f303.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/d4194b23ab4b912967f1bf7ea4d2033a15c066a095b528c93f75a8cc22c0f303.jpg)

![da399639da1dab80ab398ae8f0598b5785de5f7c87352c2311ab3edf349f2ace.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/da399639da1dab80ab398ae8f0598b5785de5f7c87352c2311ab3edf349f2ace.jpg)

![e27484e61309fb9b0f6203df8af29e0fddc4d8ddc6415cddfc43c91f85742544.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/e27484e61309fb9b0f6203df8af29e0fddc4d8ddc6415cddfc43c91f85742544.jpg)

![e34ff5f34974dadc62bf752ce254bfdc87be15d8ae53412d7394523ce77d25dd.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/e34ff5f34974dadc62bf752ce254bfdc87be15d8ae53412d7394523ce77d25dd.jpg)

![e7243f5b331df60bbbc952d673c48e80cba0c2ef64b0e32c795858ab3f0dde16.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/e7243f5b331df60bbbc952d673c48e80cba0c2ef64b0e32c795858ab3f0dde16.jpg)

![fcec4926b4ce5c58a34d5247b7e832efb94ec454d325ec60e12106315c2c20df.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/fcec4926b4ce5c58a34d5247b7e832efb94ec454d325ec60e12106315c2c20df.jpg)

![fd4a130e6393a4d90641540cbc310e56cdc0ed599c3e9e59507897a8eb466d9c.jpg](../nips_results/596_Differentiable%20Decision%20Tree%20via%20_ReLU%2BArgmin_%20Reformulation/tables/fd4a130e6393a4d90641540cbc310e56cdc0ed599c3e9e59507897a8eb466d9c.jpg)

## TGA: True-to-Geometry Avatar Dynamic Reconstruction


### Images

![0279d81c3781f849731eca7f3325fd2663800962b7fee5eba0e0c5e71519965e.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/0279d81c3781f849731eca7f3325fd2663800962b7fee5eba0e0c5e71519965e.jpg)

![0fdb08a7b6a3c7b3f755a30785232f0862fdfcac33106a2719cda5a2564f568d.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/0fdb08a7b6a3c7b3f755a30785232f0862fdfcac33106a2719cda5a2564f568d.jpg)

![3a3fd07ae5e8f0268bcbc203d24fb360e05c491b9c90d1686cbec4454c72e6fa.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/3a3fd07ae5e8f0268bcbc203d24fb360e05c491b9c90d1686cbec4454c72e6fa.jpg)

![5f3cd9311c4e0aae70a21a1ac510729851991be46cf56129f1d5ab4d8d1e38e2.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/5f3cd9311c4e0aae70a21a1ac510729851991be46cf56129f1d5ab4d8d1e38e2.jpg)

![7a7bba8163b7ac126420e4b82744add241fb3efe8205b450ead2de81b6f41d63.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/7a7bba8163b7ac126420e4b82744add241fb3efe8205b450ead2de81b6f41d63.jpg)

![a5c837ca8dbf36977c7bb4d50d2572077d45751d4617c88da853fdc65adbc337.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/a5c837ca8dbf36977c7bb4d50d2572077d45751d4617c88da853fdc65adbc337.jpg)

![b46cf021cd045cdf4988df2f2e01b29ab8f839d31ec0c823313e74ff412935df.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/b46cf021cd045cdf4988df2f2e01b29ab8f839d31ec0c823313e74ff412935df.jpg)

![bb404be2bd66582ca1a7575e28a8f6f1662b9f33c81c3186fb7a6b6f2bb0c6fd.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/bb404be2bd66582ca1a7575e28a8f6f1662b9f33c81c3186fb7a6b6f2bb0c6fd.jpg)

![cef9c30b3ec260f41a6da8a4969f610f8488f0d762d7bffd609ba0a2c2a02732.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/cef9c30b3ec260f41a6da8a4969f610f8488f0d762d7bffd609ba0a2c2a02732.jpg)

![d8f83ea1b38cf4b3f50af95916c8aa71abd33996c52f48637d482f06c2d110f2.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/d8f83ea1b38cf4b3f50af95916c8aa71abd33996c52f48637d482f06c2d110f2.jpg)

![ed3bd5577d31335c18b8fee16e1fc9fbf64bc29c9dae56c0950a4cf532256bc3.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/ed3bd5577d31335c18b8fee16e1fc9fbf64bc29c9dae56c0950a4cf532256bc3.jpg)

![f12b952cd7a6a16e78b8b3a9fe7856ca55707e5686863f670756de01afdbb4fe.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/f12b952cd7a6a16e78b8b3a9fe7856ca55707e5686863f670756de01afdbb4fe.jpg)

![f231a08aec669bb2e42e16695230980eff5054dee8aae1c144b3220a26dd040a.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/f231a08aec669bb2e42e16695230980eff5054dee8aae1c144b3220a26dd040a.jpg)

![f2b6f08ea9abfc48219eb8e98e7cb96e046843da0d2ffbecd683aefe8f34c742.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/images/f2b6f08ea9abfc48219eb8e98e7cb96e046843da0d2ffbecd683aefe8f34c742.jpg)

### Tables

![0baa95ce108791b596d5605fd06e26e77e990cb2feb3403cd3a337255b669d3f.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/tables/0baa95ce108791b596d5605fd06e26e77e990cb2feb3403cd3a337255b669d3f.jpg)

![70d61081ba9c662377f8c0b1c6d19be6a6207c33a114940469a6fcf79833a01f.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/tables/70d61081ba9c662377f8c0b1c6d19be6a6207c33a114940469a6fcf79833a01f.jpg)

![742ea6d8d100566eabab61563816f5a45176ee24b381c51ea70cdd2cd5fb471e.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/tables/742ea6d8d100566eabab61563816f5a45176ee24b381c51ea70cdd2cd5fb471e.jpg)

![8592d2966c6dca5df999a5c3e992cfcf1171c7e318037c3e3727c6fc2c19fe5d.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/tables/8592d2966c6dca5df999a5c3e992cfcf1171c7e318037c3e3727c6fc2c19fe5d.jpg)

![d91df5bd287224a8683b15db7bc99d7e778064a2d6ddd58c2783b5b01ad250b6.jpg](../nips_results/597_TGA_%20True-to-Geometry%20Avatar%20Dynamic%20Reconstruction/tables/d91df5bd287224a8683b15db7bc99d7e778064a2d6ddd58c2783b5b01ad250b6.jpg)

## GeoSVR: Taming Sparse Voxels for Geometrically Accurate Surface Reconstruction


### Images

![0f8c5887eab1f01dc90a42e96932e9ab04827c69b47c8f220faf3ba6f0f0cb2d.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/0f8c5887eab1f01dc90a42e96932e9ab04827c69b47c8f220faf3ba6f0f0cb2d.jpg)

![1dee45fa0a9fdde4f8ee04fcb866b4c681f0a88c0088395208a62b29f1b82d6d.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/1dee45fa0a9fdde4f8ee04fcb866b4c681f0a88c0088395208a62b29f1b82d6d.jpg)

![2d797551d727c249589818d8ee4d770bf6c9c46e768ef8b8fe583e1324f0f1af.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/2d797551d727c249589818d8ee4d770bf6c9c46e768ef8b8fe583e1324f0f1af.jpg)

![31336b157c93fd36f4e202c2e67e3356b5dc99835b87b55278cabf6549a46e5d.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/31336b157c93fd36f4e202c2e67e3356b5dc99835b87b55278cabf6549a46e5d.jpg)

![4892f5227641b14eff90240774b017201e36f4b9cf1453cf93ff91126f332459.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/4892f5227641b14eff90240774b017201e36f4b9cf1453cf93ff91126f332459.jpg)

![4c568b81a365d55693070d775907b004151f4a051d7c89f162fdda824eca3031.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/4c568b81a365d55693070d775907b004151f4a051d7c89f162fdda824eca3031.jpg)

![56802a3fccec41b25af1b7f4d1e80f68d28271aa32a03be644db4159bbc9095e.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/56802a3fccec41b25af1b7f4d1e80f68d28271aa32a03be644db4159bbc9095e.jpg)

![8c7f2a52b9e3b1c51aa8688002ab85f7e4917224e15a306509557a466d168fb7.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/8c7f2a52b9e3b1c51aa8688002ab85f7e4917224e15a306509557a466d168fb7.jpg)

![9d4ceb063dafa36e46c6ba8f9e4feeb4df19e8ba61d552accbd5a1f6b79464bb.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/9d4ceb063dafa36e46c6ba8f9e4feeb4df19e8ba61d552accbd5a1f6b79464bb.jpg)

![d77e4fd1fafad80957420c84301b17cdf0627eed7f42bd6143c1aea9769e00bc.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/d77e4fd1fafad80957420c84301b17cdf0627eed7f42bd6143c1aea9769e00bc.jpg)

![eaeaa602fbc648cf90434281bc82f3aaba667beec5fce5378c56f0f6afabbf20.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/eaeaa602fbc648cf90434281bc82f3aaba667beec5fce5378c56f0f6afabbf20.jpg)

![efcfb867befdf4f358246bd694a0664b7fb611c165689a8e5c4629fd68cbc648.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/efcfb867befdf4f358246bd694a0664b7fb611c165689a8e5c4629fd68cbc648.jpg)

![fa89dced52f8e6eda1b042596025795d7e9e7aa4b6629c8722af2b0af4ad7695.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/images/fa89dced52f8e6eda1b042596025795d7e9e7aa4b6629c8722af2b0af4ad7695.jpg)

### Tables

![0c0788ff74b5672e3fa028c33f9696ac785209785640435f2df613ce20763901.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/tables/0c0788ff74b5672e3fa028c33f9696ac785209785640435f2df613ce20763901.jpg)

![2a27f504cfd6b7f2e6fa4e3b64b5b11949507bfbc84e1043c54fbaceb8f8708a.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/tables/2a27f504cfd6b7f2e6fa4e3b64b5b11949507bfbc84e1043c54fbaceb8f8708a.jpg)

![3be76d0de4f721fa0c567651a126042849180c1af451788d19d1a4fce236f701.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/tables/3be76d0de4f721fa0c567651a126042849180c1af451788d19d1a4fce236f701.jpg)

![42794f90ceae506a236ab058722c5502a0fb1e9c76b6c14567b09635f47927d9.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/tables/42794f90ceae506a236ab058722c5502a0fb1e9c76b6c14567b09635f47927d9.jpg)

![466ddb35208c88333695c94fbee721095da750795c11220a05e8bb7701a00b9c.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/tables/466ddb35208c88333695c94fbee721095da750795c11220a05e8bb7701a00b9c.jpg)

![6b6eaf40fb61c2c6a7a27f2c55aceb0603048d30fad7f36edf2ae20a7b94575d.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/tables/6b6eaf40fb61c2c6a7a27f2c55aceb0603048d30fad7f36edf2ae20a7b94575d.jpg)

![81123907ee6b9e11eea54c6fd792774e7c4e7b0d0209d3384658eba3de191989.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/tables/81123907ee6b9e11eea54c6fd792774e7c4e7b0d0209d3384658eba3de191989.jpg)

![cf24c477f5215c35337182497f3866254a607b0cb821c1789d3ffcc5208729ec.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/tables/cf24c477f5215c35337182497f3866254a607b0cb821c1789d3ffcc5208729ec.jpg)

![d91271f8f13337b5df40f977063b8accde53b70c51be510c4d935c4f7046922e.jpg](../nips_results/598_GeoSVR_%20Taming%20Sparse%20Voxels%20for%20Geometrically%20Accurate%20Surface%20Reconstruction/tables/d91271f8f13337b5df40f977063b8accde53b70c51be510c4d935c4f7046922e.jpg)

## Predictive Preference Learning from Human Interventions


### Images

![0d969df5feb0e62033ba6fe20ef94b4216eb9453fa8b2f89b5c4494717bb901a.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/images/0d969df5feb0e62033ba6fe20ef94b4216eb9453fa8b2f89b5c4494717bb901a.jpg)

![55e03b2385ec90e1a3f0c92a714d15e9382f54dc5e1b23b858b82ca1861a1e91.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/images/55e03b2385ec90e1a3f0c92a714d15e9382f54dc5e1b23b858b82ca1861a1e91.jpg)

![831a0ec3f1edbe25a17312a468c5b94a09e3fc89838dfebb582c05b0f0cba959.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/images/831a0ec3f1edbe25a17312a468c5b94a09e3fc89838dfebb582c05b0f0cba959.jpg)

![c03b027e1aa7ccfc9be64ef1667b76c3281b39a9350c90f774417a203eecfa6f.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/images/c03b027e1aa7ccfc9be64ef1667b76c3281b39a9350c90f774417a203eecfa6f.jpg)

![e0249dd93a15af0727b8c8691246313c3b601be7bbd334e24c1cb8dff38ab9ee.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/images/e0249dd93a15af0727b8c8691246313c3b601be7bbd334e24c1cb8dff38ab9ee.jpg)

![e0e6e8cb7451489c48c195ef26d25d2cc249a3c947d1a6b5814986ccc909b507.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/images/e0e6e8cb7451489c48c195ef26d25d2cc249a3c947d1a6b5814986ccc909b507.jpg)

![e187df5484c811532bcd8a37dc49b4da0b13ba088d3e99b1bbe1b568dedb41e5.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/images/e187df5484c811532bcd8a37dc49b4da0b13ba088d3e99b1bbe1b568dedb41e5.jpg)

![e390282fe707054ae6eefa6728dc2ef053bc37f6d7c2ea1e077079d03dd5c739.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/images/e390282fe707054ae6eefa6728dc2ef053bc37f6d7c2ea1e077079d03dd5c739.jpg)

### Tables

![385674aba6b76ce31efc6d4f0bd49768a248b8251b69a54904b1ebe44b3d96a3.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/tables/385674aba6b76ce31efc6d4f0bd49768a248b8251b69a54904b1ebe44b3d96a3.jpg)

![3a265b64a8bf86a7f7230ed70257313907673f66ada2730146c79506088b6ae1.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/tables/3a265b64a8bf86a7f7230ed70257313907673f66ada2730146c79506088b6ae1.jpg)

![46505feebeee748e40f8671f76ff070520692bea8af28ca8dacab0a6421b143b.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/tables/46505feebeee748e40f8671f76ff070520692bea8af28ca8dacab0a6421b143b.jpg)

![74487edbceab2b3a9634fd5af94d26c9284d750cca8f14afdb6d6a69a3cc7cf5.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/tables/74487edbceab2b3a9634fd5af94d26c9284d750cca8f14afdb6d6a69a3cc7cf5.jpg)

![8fed104dda9603fa5c389b4e74315fc860117857885f0ef946c1d11dec0013bd.jpg](../nips_results/599_Predictive%20Preference%20Learning%20from%20Human%20Interventions/tables/8fed104dda9603fa5c389b4e74315fc860117857885f0ef946c1d11dec0013bd.jpg)

## Polyline Path Masked Attention for Vision Transformer


### Images

![1ceb05a554e19c9b092afb2ccbe450086b3fa4b200d9f200673d5bed1dce6c30.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/1ceb05a554e19c9b092afb2ccbe450086b3fa4b200d9f200673d5bed1dce6c30.jpg)

![58beb2aef22e2f5de3d66035722cec4d84242d434be50740229f7282c36a4ac9.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/58beb2aef22e2f5de3d66035722cec4d84242d434be50740229f7282c36a4ac9.jpg)

![5919a31630cd4ce700ebab4bf583244873d334ff3fc1d3bd2276a6eb368edfb3.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/5919a31630cd4ce700ebab4bf583244873d334ff3fc1d3bd2276a6eb368edfb3.jpg)

![7416d1828596c455bac5b1dc0f9145dc750212db7f4d2689ac61a2f730e94e30.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/7416d1828596c455bac5b1dc0f9145dc750212db7f4d2689ac61a2f730e94e30.jpg)

![8e9de7d3f0b3c9c98a6055431e37cb2f26118864cd7754cb5cdbdde4fe5c9537.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/8e9de7d3f0b3c9c98a6055431e37cb2f26118864cd7754cb5cdbdde4fe5c9537.jpg)

![9b5bb42b99a7d5e8c7b3c9e8e00ef3199a92818177198703356af2d45dcd74ab.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/9b5bb42b99a7d5e8c7b3c9e8e00ef3199a92818177198703356af2d45dcd74ab.jpg)

![9c68bb5e372e3009f40b67e35fcd64f482cbaa625eaef5c645c6995bccc6dc1c.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/9c68bb5e372e3009f40b67e35fcd64f482cbaa625eaef5c645c6995bccc6dc1c.jpg)

![a98d08ba4242bf7c8f7c1f4a31cdd6b8bc180d27eaef1b4e41a51fb5ee46119b.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/a98d08ba4242bf7c8f7c1f4a31cdd6b8bc180d27eaef1b4e41a51fb5ee46119b.jpg)

![cc5bbb70f6b76e4b3f8ca6d88874df8bcc949a4bb0cc331a18bf2982ca960d91.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/cc5bbb70f6b76e4b3f8ca6d88874df8bcc949a4bb0cc331a18bf2982ca960d91.jpg)

![d775a1ec345a1e0f2d9e35c9852a65bc72f8ecdd19b885507b8b1e6ade481337.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/d775a1ec345a1e0f2d9e35c9852a65bc72f8ecdd19b885507b8b1e6ade481337.jpg)

![db8644fae4c0e3ce07f745f63de08d92a88309b7102e97535079bce0ff7e1850.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/db8644fae4c0e3ce07f745f63de08d92a88309b7102e97535079bce0ff7e1850.jpg)

![f66dd5e4d57a4a6b79d8c0546025dd3cca4413d7510104ace00c54df32a0ae67.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/images/f66dd5e4d57a4a6b79d8c0546025dd3cca4413d7510104ace00c54df32a0ae67.jpg)

### Tables

![02ad100379575f08519bb45b6ba7df4c765ce8b956c20af72a2c20198ae5d8ea.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/tables/02ad100379575f08519bb45b6ba7df4c765ce8b956c20af72a2c20198ae5d8ea.jpg)

![2621362e6b05783e2b0f9ef38f95ad9e375cf1b3516c3a8c69c33d421a796a57.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/tables/2621362e6b05783e2b0f9ef38f95ad9e375cf1b3516c3a8c69c33d421a796a57.jpg)

![511193fd4773f0d70830934672696dc595c41e3d175b781a64adb7aab556abd8.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/tables/511193fd4773f0d70830934672696dc595c41e3d175b781a64adb7aab556abd8.jpg)

![b2bdfc35d7b0d6705942baa0c6cf0ac0d93baa54fc60d44e74b5d0e0edf0d7ef.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/tables/b2bdfc35d7b0d6705942baa0c6cf0ac0d93baa54fc60d44e74b5d0e0edf0d7ef.jpg)

![b7fbeb13e91c180154ecf7a77fc3b3a634dc2ad5ae405c45116342fd481480aa.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/tables/b7fbeb13e91c180154ecf7a77fc3b3a634dc2ad5ae405c45116342fd481480aa.jpg)

![e26b354d092eec3ceb436e66dff5c3dcb0acb6c5c53f547a5cd216aec826f402.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/tables/e26b354d092eec3ceb436e66dff5c3dcb0acb6c5c53f547a5cd216aec826f402.jpg)

![ed9b149eeb77f31c40e0da6b498119e3631e40df1472016c96bb9900badb3f5d.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/tables/ed9b149eeb77f31c40e0da6b498119e3631e40df1472016c96bb9900badb3f5d.jpg)

![f8e8799a3ebd2a6f72c7ed1e20d0f1805cf498b734dc7a9762639b87ca3cac9d.jpg](../nips_results/600_Polyline%20Path%20Masked%20Attention%20for%20Vision%20Transformer/tables/f8e8799a3ebd2a6f72c7ed1e20d0f1805cf498b734dc7a9762639b87ca3cac9d.jpg)

## Temperature is All You Need for Generalization in Langevin Dynamics and other Markov Processes


### Images

![8a2da20053f21588f45026709fa3d2ccef4d6e707c88d3dbb46c7e5f6e129dd4.jpg](../nips_results/601_Temperature%20is%20All%20You%20Need%20for%20Generalization%20in%20Langevin%20Dynamics%20and%20other%20Markov%20Processes/images/8a2da20053f21588f45026709fa3d2ccef4d6e707c88d3dbb46c7e5f6e129dd4.jpg)

### Tables

![38f1bff2f1b12c2aabe1dd06fd973590fa34da3661f2ebb600b23862cd72b54c.jpg](../nips_results/601_Temperature%20is%20All%20You%20Need%20for%20Generalization%20in%20Langevin%20Dynamics%20and%20other%20Markov%20Processes/tables/38f1bff2f1b12c2aabe1dd06fd973590fa34da3661f2ebb600b23862cd72b54c.jpg)

![417837614de41b30703392a4b83f3667bea3bbfe3095cdbb8adbbc9584077998.jpg](../nips_results/601_Temperature%20is%20All%20You%20Need%20for%20Generalization%20in%20Langevin%20Dynamics%20and%20other%20Markov%20Processes/tables/417837614de41b30703392a4b83f3667bea3bbfe3095cdbb8adbbc9584077998.jpg)

![78e08d61c49aea3a55acda8c5cab8b021a691a24daf68d76990c56a827ccba91.jpg](../nips_results/601_Temperature%20is%20All%20You%20Need%20for%20Generalization%20in%20Langevin%20Dynamics%20and%20other%20Markov%20Processes/tables/78e08d61c49aea3a55acda8c5cab8b021a691a24daf68d76990c56a827ccba91.jpg)

![7edddf869f3c96a4a12cac873e5c9d2559b8f3173802b8a34754b0e19e067a48.jpg](../nips_results/601_Temperature%20is%20All%20You%20Need%20for%20Generalization%20in%20Langevin%20Dynamics%20and%20other%20Markov%20Processes/tables/7edddf869f3c96a4a12cac873e5c9d2559b8f3173802b8a34754b0e19e067a48.jpg)

![9012b77792710162ca1be4a04dff8a25946895a07b5a030865beef5cb75eaacc.jpg](../nips_results/601_Temperature%20is%20All%20You%20Need%20for%20Generalization%20in%20Langevin%20Dynamics%20and%20other%20Markov%20Processes/tables/9012b77792710162ca1be4a04dff8a25946895a07b5a030865beef5cb75eaacc.jpg)

![c8c022a3cd71273fd49eb868f34379e5eb2c45b07b7b9b838e943a36a1728583.jpg](../nips_results/601_Temperature%20is%20All%20You%20Need%20for%20Generalization%20in%20Langevin%20Dynamics%20and%20other%20Markov%20Processes/tables/c8c022a3cd71273fd49eb868f34379e5eb2c45b07b7b9b838e943a36a1728583.jpg)

![cf31c755798bebd91875bf5558bb15a53aadd664de2f975eac79f624a30de6e7.jpg](../nips_results/601_Temperature%20is%20All%20You%20Need%20for%20Generalization%20in%20Langevin%20Dynamics%20and%20other%20Markov%20Processes/tables/cf31c755798bebd91875bf5558bb15a53aadd664de2f975eac79f624a30de6e7.jpg)

![ef5e3c9a06eb916da661e9e2c74c393ff882e2b10253c597ab0cecffd03aa13a.jpg](../nips_results/601_Temperature%20is%20All%20You%20Need%20for%20Generalization%20in%20Langevin%20Dynamics%20and%20other%20Markov%20Processes/tables/ef5e3c9a06eb916da661e9e2c74c393ff882e2b10253c597ab0cecffd03aa13a.jpg)

## Abstract Rendering:  Certified Rendering Under 3D Semantic Uncertainty


### Images

![0ebf4214c55ea3a59e28487bf8a3271a77b6509d5e9eaef1fccfee82ff0bf3dc.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/images/0ebf4214c55ea3a59e28487bf8a3271a77b6509d5e9eaef1fccfee82ff0bf3dc.jpg)

![2c9c86c62ca77ac4655be9335f6ee9b78f8f5e81c5cfe7ed7aa9dc897681110a.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/images/2c9c86c62ca77ac4655be9335f6ee9b78f8f5e81c5cfe7ed7aa9dc897681110a.jpg)

![32a277961bb7efd5bf5a5e1a2d23097bbec6fca3da4b11a3eef03c7f51b8a6b9.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/images/32a277961bb7efd5bf5a5e1a2d23097bbec6fca3da4b11a3eef03c7f51b8a6b9.jpg)

![5edcaad57a799fec7c9950dffaa8c64a3898d339b66ead2b5154b8747e646c65.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/images/5edcaad57a799fec7c9950dffaa8c64a3898d339b66ead2b5154b8747e646c65.jpg)

![81a00da6bf6c7051f2ecb7182f79bb1ef5bab52661ada39b09badefcd2f90fcf.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/images/81a00da6bf6c7051f2ecb7182f79bb1ef5bab52661ada39b09badefcd2f90fcf.jpg)

![9aeefbb03e0c4d5fcae21f1331d4da1d572fefd9fce1024ac70a1e1c205ee439.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/images/9aeefbb03e0c4d5fcae21f1331d4da1d572fefd9fce1024ac70a1e1c205ee439.jpg)

![b045339aa6c9d30c5cc2d2dbaa80f6960205dd8bffbef0e69a6b69a36a854527.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/images/b045339aa6c9d30c5cc2d2dbaa80f6960205dd8bffbef0e69a6b69a36a854527.jpg)

![c51f23f3c262c8d43f6cee331896405ecfa55641536b7ed203c8b64cae436dc5.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/images/c51f23f3c262c8d43f6cee331896405ecfa55641536b7ed203c8b64cae436dc5.jpg)

![d948c02b398bfb5eb5fb9bd06cfc33bc5aa12e094bff0b72d3756d8c7c1f15c0.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/images/d948c02b398bfb5eb5fb9bd06cfc33bc5aa12e094bff0b72d3756d8c7c1f15c0.jpg)

![dbb7976feb70713f9965ecb9490ebf00685af02581fd9a34604fe41c658da1f2.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/images/dbb7976feb70713f9965ecb9490ebf00685af02581fd9a34604fe41c658da1f2.jpg)

![e1a2db344f48c2f45a3d290652c756f034a466bd6ce7b9c175611625f09c81e7.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/images/e1a2db344f48c2f45a3d290652c756f034a466bd6ce7b9c175611625f09c81e7.jpg)

### Tables

![049b2d42d8a405a2868cda406715718c39b0542be0640c0a07e01b6c0fc90558.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/tables/049b2d42d8a405a2868cda406715718c39b0542be0640c0a07e01b6c0fc90558.jpg)

![139be672ad124e76a7b1e59721be6b652f5c3ac99c7a3b17b5b49148305c357d.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/tables/139be672ad124e76a7b1e59721be6b652f5c3ac99c7a3b17b5b49148305c357d.jpg)

![5a1fe844f5e738a36b068bcbe6a63d3be93accf0dfb5ef86219207819dca53a8.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/tables/5a1fe844f5e738a36b068bcbe6a63d3be93accf0dfb5ef86219207819dca53a8.jpg)

![a97c0ea90289e42bf71d62c6390877ac5c9cf7d0b425539e44930babca9b8537.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/tables/a97c0ea90289e42bf71d62c6390877ac5c9cf7d0b425539e44930babca9b8537.jpg)

![e6d7f07a62c9e19286b73e8e6e603f6a5b055c1d22adf2e6e33180147ed207bc.jpg](../nips_results/602_Abstract%20Rendering_%20%20Certified%20Rendering%20Under%203D%20Semantic%20Uncertainty/tables/e6d7f07a62c9e19286b73e8e6e603f6a5b055c1d22adf2e6e33180147ed207bc.jpg)

## Controlling Thinking Speed in Reasoning Models


### Images

![04d565450d77442d412005dd406e2f4637cd79215a3ada28f836a961919f9d90.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/04d565450d77442d412005dd406e2f4637cd79215a3ada28f836a961919f9d90.jpg)

![35d891c741054a479e29ef37e25a3a2e89a3320f82be181097fe961fd666767c.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/35d891c741054a479e29ef37e25a3a2e89a3320f82be181097fe961fd666767c.jpg)

![3f90b4a32cbd0e76e7e6ded0a1bef8d7f227c075828be9a881fb6d8fc0c6bc7b.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/3f90b4a32cbd0e76e7e6ded0a1bef8d7f227c075828be9a881fb6d8fc0c6bc7b.jpg)

![55a2cd7ac6abea00cad7144414983e082feb5a9784f9bad4c9820761e7901d8b.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/55a2cd7ac6abea00cad7144414983e082feb5a9784f9bad4c9820761e7901d8b.jpg)

![7005d595f0bff1afc78dd929b60744e10099c9a4437d63586ccb4efd86b29617.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/7005d595f0bff1afc78dd929b60744e10099c9a4437d63586ccb4efd86b29617.jpg)

![75d6219b25f19e12598ffb27555878447f42977405526732a839fcf432f40b99.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/75d6219b25f19e12598ffb27555878447f42977405526732a839fcf432f40b99.jpg)

![882930ea80e1938adc27ca4e0a8d7fc0f437dc039897027a083d554de692040c.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/882930ea80e1938adc27ca4e0a8d7fc0f437dc039897027a083d554de692040c.jpg)

![b0741f622b4d426b810a039a0f9200f9a00e1261916084d2a51a8e2260d31e07.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/b0741f622b4d426b810a039a0f9200f9a00e1261916084d2a51a8e2260d31e07.jpg)

![cbba78905671b59c9e43d59b3734b2aaebb7f2918a7258b038a7e85a16e3fe28.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/cbba78905671b59c9e43d59b3734b2aaebb7f2918a7258b038a7e85a16e3fe28.jpg)

![d235f8f8ea2fde84883760b3d987df1dfe1a1805adb1c4934158fdf863825686.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/d235f8f8ea2fde84883760b3d987df1dfe1a1805adb1c4934158fdf863825686.jpg)

![f761e452e3657965cb73a12830b955f83c3c67c610b307dd43cdae4e895e67c8.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/f761e452e3657965cb73a12830b955f83c3c67c610b307dd43cdae4e895e67c8.jpg)

![fcf1c446c7f8ab57b08614e132533cc49a54a02bae34e17c9bb6bbb4bcd6d441.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/images/fcf1c446c7f8ab57b08614e132533cc49a54a02bae34e17c9bb6bbb4bcd6d441.jpg)

### Tables

![1c1794b866faa56cfe1cad539ad9e57213af244e82d97c2ceb90c1341f64e73d.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/1c1794b866faa56cfe1cad539ad9e57213af244e82d97c2ceb90c1341f64e73d.jpg)

![24223d913504457fc1112851a6ae093260fcff45363b2fecf58716c915650ca0.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/24223d913504457fc1112851a6ae093260fcff45363b2fecf58716c915650ca0.jpg)

![2eee71fbc17458e63683c949ea5ad294a7f86b0f3d4f92d006ed08849d332c49.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/2eee71fbc17458e63683c949ea5ad294a7f86b0f3d4f92d006ed08849d332c49.jpg)

![364957d2a9e90be83c609c336fcedbb8665acc65738a15bb597e8e7ca267f0da.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/364957d2a9e90be83c609c336fcedbb8665acc65738a15bb597e8e7ca267f0da.jpg)

![37d752f99ab5924f6d47b62cd1fafa1f646ce81b021ba5a0ba83395713628d6b.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/37d752f99ab5924f6d47b62cd1fafa1f646ce81b021ba5a0ba83395713628d6b.jpg)

![3ff9eefaa35495752cc62eaa8fadad2409ed551d6d736020f54bd1b3aa5bd063.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/3ff9eefaa35495752cc62eaa8fadad2409ed551d6d736020f54bd1b3aa5bd063.jpg)

![5646d65593750199e94ad297da642a70b02d5f9748671f1250d4fa3c5e7f0d62.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/5646d65593750199e94ad297da642a70b02d5f9748671f1250d4fa3c5e7f0d62.jpg)

![5bba357503d853439b81876056323edf976e771c861eb27c33b1703e070f4822.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/5bba357503d853439b81876056323edf976e771c861eb27c33b1703e070f4822.jpg)

![69106419278ad2d06a8ade46c1aa9a3795278309f6a0364982f050ff48883710.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/69106419278ad2d06a8ade46c1aa9a3795278309f6a0364982f050ff48883710.jpg)

![8420fbce50e1dacb8c68724e432f8b360f754cebce2013044902329c54876e08.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/8420fbce50e1dacb8c68724e432f8b360f754cebce2013044902329c54876e08.jpg)

![85c489475034335a26d829534d6f1918cb9f9292bb2b3617b50be65329f25c38.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/85c489475034335a26d829534d6f1918cb9f9292bb2b3617b50be65329f25c38.jpg)

![880cf8d09a33d62c9f69a749c1885c105a7427b16837eb0dd68875ba010a469e.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/880cf8d09a33d62c9f69a749c1885c105a7427b16837eb0dd68875ba010a469e.jpg)

![9620085319b2e27b6037fb1b9f965a2aadef99a2367ca570c594904167b4c6fc.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/9620085319b2e27b6037fb1b9f965a2aadef99a2367ca570c594904167b4c6fc.jpg)

![aeb11fd0a21b35a634d2a560d7c7881bfc1f2feb5f2cb456e5726dc45c32569b.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/aeb11fd0a21b35a634d2a560d7c7881bfc1f2feb5f2cb456e5726dc45c32569b.jpg)

![dfc93b61fb0a5e59407ff3962bf12df9e32c445e1876209d19b34b6398ff9bb5.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/dfc93b61fb0a5e59407ff3962bf12df9e32c445e1876209d19b34b6398ff9bb5.jpg)

![f708fa5f8a038f0e9ac2488e9492edc63704331a2cdbee5cd5650ca6142bec2f.jpg](../nips_results/603_Controlling%20Thinking%20Speed%20in%20Reasoning%20Models/tables/f708fa5f8a038f0e9ac2488e9492edc63704331a2cdbee5cd5650ca6142bec2f.jpg)

## Enhancing Training Data Attribution with Representational Optimization


### Images

![22ed818aad4b7ca699669ee816e9e1299f54b59e9566925d4374c3644d20deff.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/images/22ed818aad4b7ca699669ee816e9e1299f54b59e9566925d4374c3644d20deff.jpg)

![77a8508fe330e86b792a7012f246d0e6970f6c9ce2b8b41cdf88169c58d238eb.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/images/77a8508fe330e86b792a7012f246d0e6970f6c9ce2b8b41cdf88169c58d238eb.jpg)

![88b2bd0a2ee10fc65d1d6bbf94e209f88081f5fdf37b7812fca76165ccab6632.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/images/88b2bd0a2ee10fc65d1d6bbf94e209f88081f5fdf37b7812fca76165ccab6632.jpg)

![a0d517889c6eea89e5d61e103745d8d36ea1c1b2b1608ef27ded6dcd3432e906.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/images/a0d517889c6eea89e5d61e103745d8d36ea1c1b2b1608ef27ded6dcd3432e906.jpg)

![a75a73182708edb04284b0c34ada56e11054f630fee0bab945e45e6b3ad74fd2.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/images/a75a73182708edb04284b0c34ada56e11054f630fee0bab945e45e6b3ad74fd2.jpg)

![b00e079eea6125528c37315e8010c3579a52d5663e6224a4e169ccbb4ae7705a.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/images/b00e079eea6125528c37315e8010c3579a52d5663e6224a4e169ccbb4ae7705a.jpg)

![be04eb7c5a6e26f54cae155c176c48416dca1ab60dc0dabfab89f00df8474e01.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/images/be04eb7c5a6e26f54cae155c176c48416dca1ab60dc0dabfab89f00df8474e01.jpg)

![c5f224addd2c9be58a4f81a98edd10442fe8f1f2312e5dd17c90f56936aefa54.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/images/c5f224addd2c9be58a4f81a98edd10442fe8f1f2312e5dd17c90f56936aefa54.jpg)

![c83c1b62e1043d9a6bca2b512547a6454c450138998131f6fa19ef200ebcdcfa.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/images/c83c1b62e1043d9a6bca2b512547a6454c450138998131f6fa19ef200ebcdcfa.jpg)

### Tables

![13fdba5dd01201fbe8bf905fcdc70e35ef9db76f82b21e14e8e7bb13b4b4d546.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/tables/13fdba5dd01201fbe8bf905fcdc70e35ef9db76f82b21e14e8e7bb13b4b4d546.jpg)

![2206a42b2ebff92cbecc4b60a67f939cca56a1033eaac27b4da2008756943325.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/tables/2206a42b2ebff92cbecc4b60a67f939cca56a1033eaac27b4da2008756943325.jpg)

![4e41d54a6a89060643092a7b83d3137a87ea15f33f7bc638d153a0694ea379c9.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/tables/4e41d54a6a89060643092a7b83d3137a87ea15f33f7bc638d153a0694ea379c9.jpg)

![4f5c236d503e3a3d414661f11e2cdfb37f130342f13d21dfaa18fa562cc12527.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/tables/4f5c236d503e3a3d414661f11e2cdfb37f130342f13d21dfaa18fa562cc12527.jpg)

![6688289fa460ab6100e7c8f63c61232a766fdb90bc18cdfbb7bb59a1cf4546c6.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/tables/6688289fa460ab6100e7c8f63c61232a766fdb90bc18cdfbb7bb59a1cf4546c6.jpg)

![b7ba96aaf79f03d17e7feab8b2f5d90b9a8a557bf1fbc865840cb07fb38ab752.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/tables/b7ba96aaf79f03d17e7feab8b2f5d90b9a8a557bf1fbc865840cb07fb38ab752.jpg)

![c431e1b17caa24208d0b3ef181e330ed0d72f174d3c0c07e6eff99acc951413e.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/tables/c431e1b17caa24208d0b3ef181e330ed0d72f174d3c0c07e6eff99acc951413e.jpg)

![c43f04a4c4e568d49c3e9eb06788da061f35f4fd823cff70fb689d1ccc03505e.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/tables/c43f04a4c4e568d49c3e9eb06788da061f35f4fd823cff70fb689d1ccc03505e.jpg)

![f7596c633e8fba0f5dba657dabf5b5b19f889b85a2cd7114d433741b0714e25f.jpg](../nips_results/604_Enhancing%20Training%20Data%20Attribution%20with%20Representational%20Optimization/tables/f7596c633e8fba0f5dba657dabf5b5b19f889b85a2cd7114d433741b0714e25f.jpg)

## The Graphon Limit Hypothesis: Understanding Neural Network Pruning via Infinite Width Analysis


### Images

![043ffeb00cf1c1ea7b17d2af2dfed60d0032cfaecbe36603ceb6ece0c9bac9b5.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/043ffeb00cf1c1ea7b17d2af2dfed60d0032cfaecbe36603ceb6ece0c9bac9b5.jpg)

![14c18bc78a23b8708fa112eea3cab24cdf80690fbc4c053c1f9e0375cca6d31c.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/14c18bc78a23b8708fa112eea3cab24cdf80690fbc4c053c1f9e0375cca6d31c.jpg)

![2aa9c52b58cef3974b0f834f52ce95cdb50b5402df0f5f8ae957c2299c92f099.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/2aa9c52b58cef3974b0f834f52ce95cdb50b5402df0f5f8ae957c2299c92f099.jpg)

![4c0333fc006510ac110876052bde0be4cd618f9898a745ba89277cd8c2569d48.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/4c0333fc006510ac110876052bde0be4cd618f9898a745ba89277cd8c2569d48.jpg)

![5c4bd3e5570fbd114673e9bae7d16fa9208ae8176e16525d9dc5c7ceb0061041.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/5c4bd3e5570fbd114673e9bae7d16fa9208ae8176e16525d9dc5c7ceb0061041.jpg)

![6610a4d0208c79c8f47699672dea74b2e052e68f270a301d6678bf62feea24ec.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/6610a4d0208c79c8f47699672dea74b2e052e68f270a301d6678bf62feea24ec.jpg)

![6c290bf4424f43b1065aa7d49c58cacce502f683eb2047b4d7e061606eef28cd.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/6c290bf4424f43b1065aa7d49c58cacce502f683eb2047b4d7e061606eef28cd.jpg)

![a012225dc006ed0629556b96d7c8002dab5fc034023bf92e6867e46b391a5b6d.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/a012225dc006ed0629556b96d7c8002dab5fc034023bf92e6867e46b391a5b6d.jpg)

![a5442fe62ee55c3a79c3e28ae3c4a41d5bd1d6b203fea969a75cb7ee5c14f49a.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/a5442fe62ee55c3a79c3e28ae3c4a41d5bd1d6b203fea969a75cb7ee5c14f49a.jpg)

![c3f018beb3b712a251a6c9483843e7d4787eb0db3c600393a1afb9f6afa027c9.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/c3f018beb3b712a251a6c9483843e7d4787eb0db3c600393a1afb9f6afa027c9.jpg)

![c6ef9baa917adbe2e54f1ccaad8fabfebdc986563c3bd6aad655818d46a3d4fc.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/c6ef9baa917adbe2e54f1ccaad8fabfebdc986563c3bd6aad655818d46a3d4fc.jpg)

![d24f4f6f0dc00fa67cf1c145c5463e6933327e80216686e92e0a82747c1988d9.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/d24f4f6f0dc00fa67cf1c145c5463e6933327e80216686e92e0a82747c1988d9.jpg)

![e44ad26d7a6f4a5bf72ab411e391af103bed1e94018a9f15071d7f186f6e5c37.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/e44ad26d7a6f4a5bf72ab411e391af103bed1e94018a9f15071d7f186f6e5c37.jpg)

![efadc9cd4aeaeb27523b2dd58cabf340b7e24f96412d59abe24eab4c355c1642.jpg](../nips_results/605_The%20Graphon%20Limit%20Hypothesis_%20Understanding%20Neural%20Network%20Pruning%20via%20Infinite%20Width%20Analysis/images/efadc9cd4aeaeb27523b2dd58cabf340b7e24f96412d59abe24eab4c355c1642.jpg)

## Tensor Product Attention Is All You Need


### Images

![16cee0ecd589e86319b092057e75271676d1cf1155eb94edd246a6efade45403.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/images/16cee0ecd589e86319b092057e75271676d1cf1155eb94edd246a6efade45403.jpg)

![53c7a6a4ce336bbe1a86db3bb65c28ec19422a1666fc3a158455256bc2bee8ee.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/images/53c7a6a4ce336bbe1a86db3bb65c28ec19422a1666fc3a158455256bc2bee8ee.jpg)

![58983c6eb91c812aed981014386634da80f08eacdb37f4742c3f2305a9044210.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/images/58983c6eb91c812aed981014386634da80f08eacdb37f4742c3f2305a9044210.jpg)

![a83124250058c1a51aa6613be4d9b65b1529e1c2e62940ae4505050e72877558.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/images/a83124250058c1a51aa6613be4d9b65b1529e1c2e62940ae4505050e72877558.jpg)

![b9e9b3475f6b5a72b98e1ce54e6bc0cba8b1a727fa87d0fad416d9b1f1e704cf.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/images/b9e9b3475f6b5a72b98e1ce54e6bc0cba8b1a727fa87d0fad416d9b1f1e704cf.jpg)

![c34fd8658cf03a96df5ab129e44b64af4b29df87711d754c03390eb90c2cce1b.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/images/c34fd8658cf03a96df5ab129e44b64af4b29df87711d754c03390eb90c2cce1b.jpg)

![c80f174252e8f1a312c22ecdb1ee44937a83db14eec6ff02ca8340b74e1c449b.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/images/c80f174252e8f1a312c22ecdb1ee44937a83db14eec6ff02ca8340b74e1c449b.jpg)

![d6ee9030f1b9ae1a7a28ca9284c2e94b4c21d1f98dc092b23825ef366fcf6b26.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/images/d6ee9030f1b9ae1a7a28ca9284c2e94b4c21d1f98dc092b23825ef366fcf6b26.jpg)

![d723bef779ee5b0534f65adb3681e226aade276bc1dac605d33c98fb0977feb7.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/images/d723bef779ee5b0534f65adb3681e226aade276bc1dac605d33c98fb0977feb7.jpg)

![db803b8b6ff89463368a330b018dc98b9351f040cf4aeeabc28ecc6fb0403aef.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/images/db803b8b6ff89463368a330b018dc98b9351f040cf4aeeabc28ecc6fb0403aef.jpg)

![e65da64a451cb66dc5f291e2a4337da99db595911beb560cf80a404ab9e70877.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/images/e65da64a451cb66dc5f291e2a4337da99db595911beb560cf80a404ab9e70877.jpg)

### Tables

![1c1e09d33300dcac0f3a297a4214a7d17d688771a6a6f7ab8a931ff8e28ba9a4.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/1c1e09d33300dcac0f3a297a4214a7d17d688771a6a6f7ab8a931ff8e28ba9a4.jpg)

![22640f473e5f65de03628eb72379bab12c50adf30f0f84704a26f850855ad667.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/22640f473e5f65de03628eb72379bab12c50adf30f0f84704a26f850855ad667.jpg)

![2adf8a09a4a3110ebbd22190b0efd1ba289c9f8232edba852c835c0e66b84132.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/2adf8a09a4a3110ebbd22190b0efd1ba289c9f8232edba852c835c0e66b84132.jpg)

![46ce2f3b2bf5661ffe0d8deb8aabcde855fcfb82f9a3f5fc35d0aff6d4165d88.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/46ce2f3b2bf5661ffe0d8deb8aabcde855fcfb82f9a3f5fc35d0aff6d4165d88.jpg)

![488eb2d47adf637c690b8251a68bbeb324765d90931141d8341194dc5f0d246c.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/488eb2d47adf637c690b8251a68bbeb324765d90931141d8341194dc5f0d246c.jpg)

![4c36715205227339d15bd8e02bdd3f5bccd58abd58fe7bf2ba1cef9901c9b990.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/4c36715205227339d15bd8e02bdd3f5bccd58abd58fe7bf2ba1cef9901c9b990.jpg)

![4cd0524a929887e80ac7ed7cdacd71f9ecb17340c461c51953d2121a6744efa4.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/4cd0524a929887e80ac7ed7cdacd71f9ecb17340c461c51953d2121a6744efa4.jpg)

![57d1728841dc436110beeb2100f8515b48dea582ef31c87a4ac740168c92614c.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/57d1728841dc436110beeb2100f8515b48dea582ef31c87a4ac740168c92614c.jpg)

![5c6a52d9d7d3b9b03b2ceaa19a25bc91e2a29813f307e5cc49d7f82c898db073.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/5c6a52d9d7d3b9b03b2ceaa19a25bc91e2a29813f307e5cc49d7f82c898db073.jpg)

![62c19917390f8d6017b39da8a8c970f6e032b1420688f0bce05ce27f21e38771.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/62c19917390f8d6017b39da8a8c970f6e032b1420688f0bce05ce27f21e38771.jpg)

![6636a87bcd198158f0e3390cbba96950df04210e094bb8d63ed6c5cc75426c5c.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/6636a87bcd198158f0e3390cbba96950df04210e094bb8d63ed6c5cc75426c5c.jpg)

![768be3c95a960b0b395a20ec49139b12ce98fbd62eb27bc22a04adcb465df8e8.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/768be3c95a960b0b395a20ec49139b12ce98fbd62eb27bc22a04adcb465df8e8.jpg)

![847c06df9110f3c4277a1c2cc2bc2bea143cb5d3051e7442b2143163d109cd1d.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/847c06df9110f3c4277a1c2cc2bc2bea143cb5d3051e7442b2143163d109cd1d.jpg)

![869b17551d58e97ed72e95b87bd7f7589fdc7c61f95e7f7b7846ebfa3caa8819.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/869b17551d58e97ed72e95b87bd7f7589fdc7c61f95e7f7b7846ebfa3caa8819.jpg)

![8e8dd089a881e59c558e499446edd0a8a2cbe42e5272561c86468f545869b8dd.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/8e8dd089a881e59c558e499446edd0a8a2cbe42e5272561c86468f545869b8dd.jpg)

![a6cc721b617933c22dc66d8444d7fa6300c7dad68acc680eb1d7bc0139b1562f.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/a6cc721b617933c22dc66d8444d7fa6300c7dad68acc680eb1d7bc0139b1562f.jpg)

![bdafbf2418ef5af0e545f839bc7895ea701ffb51ec0890b5771f7b0e1811a063.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/bdafbf2418ef5af0e545f839bc7895ea701ffb51ec0890b5771f7b0e1811a063.jpg)

![fc95efaa8393178d4b0c4f4a3e658539ae092393a7d23dc22eefbd42d6cc1112.jpg](../nips_results/606_Tensor%20Product%20Attention%20Is%20All%20You%20Need/tables/fc95efaa8393178d4b0c4f4a3e658539ae092393a7d23dc22eefbd42d6cc1112.jpg)

## The Power of Iterative Filtering for Supervised Learning with (Heavy) Contamination


### Tables

![365cb970edebdda7fad6e29bc5aa0cc9a051389d7ab6746bbcc79c1c22942339.jpg](../nips_results/607_The%20Power%20of%20Iterative%20Filtering%20for%20Supervised%20Learning%20with%20%28Heavy) Contamination/tables/365cb970edebdda7fad6e29bc5aa0cc9a051389d7ab6746bbcc79c1c22942339.jpg)

![5909c4ba27acd09bcc9f99718f102e7b5b0618da6fac97f7cb9f272b4d2f326c.jpg](../nips_results/607_The%20Power%20of%20Iterative%20Filtering%20for%20Supervised%20Learning%20with%20%28Heavy) Contamination/tables/5909c4ba27acd09bcc9f99718f102e7b5b0618da6fac97f7cb9f272b4d2f326c.jpg)

![b90696eda7b2243bf14de019669c388b607ba299b32d96d1ea54e5355bd44157.jpg](../nips_results/607_The%20Power%20of%20Iterative%20Filtering%20for%20Supervised%20Learning%20with%20%28Heavy) Contamination/tables/b90696eda7b2243bf14de019669c388b607ba299b32d96d1ea54e5355bd44157.jpg)

![da40c4e7db8b601ff7b75a588ed8b45c5a06719c7e12999b7e7fa0909a7a6550.jpg](../nips_results/607_The%20Power%20of%20Iterative%20Filtering%20for%20Supervised%20Learning%20with%20%28Heavy) Contamination/tables/da40c4e7db8b601ff7b75a588ed8b45c5a06719c7e12999b7e7fa0909a7a6550.jpg)

## GSRF: Complex-Valued 3D Gaussian Splatting for Efficient Radio-Frequency Data Synthesis


### Images

![048d4782eafbd54fdd571bc21ceea8f141de9aa24bd7b643c8f376bf75410499.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/images/048d4782eafbd54fdd571bc21ceea8f141de9aa24bd7b643c8f376bf75410499.jpg)

![220a76161423812a193143076b47fcd9e8fc8bbf7cc0d56e0e1de2ebdd9542b7.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/images/220a76161423812a193143076b47fcd9e8fc8bbf7cc0d56e0e1de2ebdd9542b7.jpg)

![47db1d523691c1fc8bb4e87001a0b22de834a23ce44a5e0d48fcb24051aba459.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/images/47db1d523691c1fc8bb4e87001a0b22de834a23ce44a5e0d48fcb24051aba459.jpg)

![5c020ab8512b8eb01d0c31872723c35c880122034925b7c26339772e42bbf0dd.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/images/5c020ab8512b8eb01d0c31872723c35c880122034925b7c26339772e42bbf0dd.jpg)

![7a74c8e999d51dd0cbe97002129b58be0fed3c24c75468cdf33bca7ae944c175.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/images/7a74c8e999d51dd0cbe97002129b58be0fed3c24c75468cdf33bca7ae944c175.jpg)

![8279f3d092394e10b995f85bacd186363b3258c96f2194b7590fad321167f710.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/images/8279f3d092394e10b995f85bacd186363b3258c96f2194b7590fad321167f710.jpg)

![8cc2486f0da6fbf29b7b4d3acb72bf1db14979521a2ae60a3ac521378a56ec8d.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/images/8cc2486f0da6fbf29b7b4d3acb72bf1db14979521a2ae60a3ac521378a56ec8d.jpg)

![8d2c7a5b30a804483033b9558c158b95b51c91df3457b4156433d4487a0780bc.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/images/8d2c7a5b30a804483033b9558c158b95b51c91df3457b4156433d4487a0780bc.jpg)

![d2bfdfe77ba02e1d0dfa2119c2463369ce98022e9a5fa43f8551a59872a49c07.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/images/d2bfdfe77ba02e1d0dfa2119c2463369ce98022e9a5fa43f8551a59872a49c07.jpg)

![d5e8be7a34ea334002364b520fadc65bb785ed454225398c06bc955abde8ef2b.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/images/d5e8be7a34ea334002364b520fadc65bb785ed454225398c06bc955abde8ef2b.jpg)

![f64de66d97729ff586200508e25f56d0e7e148609b2ab8a7aedaa70b37019511.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/images/f64de66d97729ff586200508e25f56d0e7e148609b2ab8a7aedaa70b37019511.jpg)

### Tables

![0b50be6774d554c9fb8855153f38a9d63aa81d2c2d522f68a0a23b1165a4466c.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/tables/0b50be6774d554c9fb8855153f38a9d63aa81d2c2d522f68a0a23b1165a4466c.jpg)

![233571789a25b88911eb2f1e154adb5cbbb56c96e20a54082169ca877304cf89.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/tables/233571789a25b88911eb2f1e154adb5cbbb56c96e20a54082169ca877304cf89.jpg)

![32cb6cefe23ebe0cfc0b82f53645a6b2065dff5e4c1244918ba6047a29832e71.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/tables/32cb6cefe23ebe0cfc0b82f53645a6b2065dff5e4c1244918ba6047a29832e71.jpg)

![59f7562145838de096ef37c7ffe385a98d7d26a4ab8639fa2d0b1eb82f233cc7.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/tables/59f7562145838de096ef37c7ffe385a98d7d26a4ab8639fa2d0b1eb82f233cc7.jpg)

![a66b80e66c17a2db3e75cbf661e03e9af769443e0baaaf8f238598c4a0b87a05.jpg](../nips_results/608_GSRF_%20Complex-Valued%203D%20Gaussian%20Splatting%20for%20Efficient%20Radio-Frequency%20Data%20Synthesis/tables/a66b80e66c17a2db3e75cbf661e03e9af769443e0baaaf8f238598c4a0b87a05.jpg)

## Deciphering the Extremes: A Novel Approach for Pathological Long-tailed Recognition in Scientific Discovery


### Images

![08e8e1e06c65173411622e4d51fcdbb98bbdf12ecac99f40a8e3b93cf2dfd9b3.jpg](../nips_results/609_Deciphering%20the%20Extremes_%20A%20Novel%20Approach%20for%20Pathological%20Long-tailed%20Recognition%20in%20Scientific%20Di/images/08e8e1e06c65173411622e4d51fcdbb98bbdf12ecac99f40a8e3b93cf2dfd9b3.jpg)

![8417dc1775c5297df1036aec31ef4db0a9c08e23e09b3e92f46495a9625334f9.jpg](../nips_results/609_Deciphering%20the%20Extremes_%20A%20Novel%20Approach%20for%20Pathological%20Long-tailed%20Recognition%20in%20Scientific%20Di/images/8417dc1775c5297df1036aec31ef4db0a9c08e23e09b3e92f46495a9625334f9.jpg)

![94f49b0777c9285bc52c352aeabdc432b028a2b4e0a496fbc6d2f4d3495720d9.jpg](../nips_results/609_Deciphering%20the%20Extremes_%20A%20Novel%20Approach%20for%20Pathological%20Long-tailed%20Recognition%20in%20Scientific%20Di/images/94f49b0777c9285bc52c352aeabdc432b028a2b4e0a496fbc6d2f4d3495720d9.jpg)

![9d2e9e9d1b68acf34e05ae2e9a8d5de0a3a784b723ac5291084544d6e8d69038.jpg](../nips_results/609_Deciphering%20the%20Extremes_%20A%20Novel%20Approach%20for%20Pathological%20Long-tailed%20Recognition%20in%20Scientific%20Di/images/9d2e9e9d1b68acf34e05ae2e9a8d5de0a3a784b723ac5291084544d6e8d69038.jpg)

![db169b8f9e4097bb590e179bcb5ded2e7bdf9264b527892254646189b4ac571b.jpg](../nips_results/609_Deciphering%20the%20Extremes_%20A%20Novel%20Approach%20for%20Pathological%20Long-tailed%20Recognition%20in%20Scientific%20Di/images/db169b8f9e4097bb590e179bcb5ded2e7bdf9264b527892254646189b4ac571b.jpg)

![e0ddae0bc2b68862aaf1739dfceb8e57657f537dbb0be71ae8185aaf0da8a1cf.jpg](../nips_results/609_Deciphering%20the%20Extremes_%20A%20Novel%20Approach%20for%20Pathological%20Long-tailed%20Recognition%20in%20Scientific%20Di/images/e0ddae0bc2b68862aaf1739dfceb8e57657f537dbb0be71ae8185aaf0da8a1cf.jpg)

![eb6bf6434324988f07a6e25be047705ad4fa2b29253d82d321c356d9dcb4e387.jpg](../nips_results/609_Deciphering%20the%20Extremes_%20A%20Novel%20Approach%20for%20Pathological%20Long-tailed%20Recognition%20in%20Scientific%20Di/images/eb6bf6434324988f07a6e25be047705ad4fa2b29253d82d321c356d9dcb4e387.jpg)

### Tables

![19b24345fc62cf95bed0de5f483b9bd30fe934545c0e2327d6a884ba33441aed.jpg](../nips_results/609_Deciphering%20the%20Extremes_%20A%20Novel%20Approach%20for%20Pathological%20Long-tailed%20Recognition%20in%20Scientific%20Di/tables/19b24345fc62cf95bed0de5f483b9bd30fe934545c0e2327d6a884ba33441aed.jpg)

![6d3b7a90604e07989e74df8a0cd5e6eaa0e771d7201b4305f8f7201c12d01058.jpg](../nips_results/609_Deciphering%20the%20Extremes_%20A%20Novel%20Approach%20for%20Pathological%20Long-tailed%20Recognition%20in%20Scientific%20Di/tables/6d3b7a90604e07989e74df8a0cd5e6eaa0e771d7201b4305f8f7201c12d01058.jpg)

![91ab090a1a4561623e3e1255f7dc4faabcbea5e93285914125360be13c6274ad.jpg](../nips_results/609_Deciphering%20the%20Extremes_%20A%20Novel%20Approach%20for%20Pathological%20Long-tailed%20Recognition%20in%20Scientific%20Di/tables/91ab090a1a4561623e3e1255f7dc4faabcbea5e93285914125360be13c6274ad.jpg)

![ca144387a2cea67ef25ef875f2e2676112863608ee1018742bdbb4ce91569a1b.jpg](../nips_results/609_Deciphering%20the%20Extremes_%20A%20Novel%20Approach%20for%20Pathological%20Long-tailed%20Recognition%20in%20Scientific%20Di/tables/ca144387a2cea67ef25ef875f2e2676112863608ee1018742bdbb4ce91569a1b.jpg)

## Zero-shot Denoising via Neural Compression: Theoretical and algorithmic framework


### Images

![1c79b7a6be42602cc36209efc62e19f3b4c44b70314b3fbc4255381af84597f9.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/images/1c79b7a6be42602cc36209efc62e19f3b4c44b70314b3fbc4255381af84597f9.jpg)

![2893913a632188c8ecff37244ba6b533aa623373c40a473ad9fe0a8f685b583b.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/images/2893913a632188c8ecff37244ba6b533aa623373c40a473ad9fe0a8f685b583b.jpg)

![42fe5f40265b6511e43818c5dc3f335ef8246f39c778c49870d893f501a1195e.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/images/42fe5f40265b6511e43818c5dc3f335ef8246f39c778c49870d893f501a1195e.jpg)

![53570d4092be7b0b8ac90ba6538e185acca35472b816350c62388d518ae0da2a.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/images/53570d4092be7b0b8ac90ba6538e185acca35472b816350c62388d518ae0da2a.jpg)

![82027c693e1982884757fbe3972b9dacca5519a4ba8f6067f5109a0ec6a52892.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/images/82027c693e1982884757fbe3972b9dacca5519a4ba8f6067f5109a0ec6a52892.jpg)

![9bb7ea68a53bb781b01f392778a55cfad3d05728e225d21bce621df130e73a44.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/images/9bb7ea68a53bb781b01f392778a55cfad3d05728e225d21bce621df130e73a44.jpg)

![9e2589909c868c8e87e9ea0a9b2be9ad8820e2147478c95fc5731bc6fd742f9d.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/images/9e2589909c868c8e87e9ea0a9b2be9ad8820e2147478c95fc5731bc6fd742f9d.jpg)

![a6583f280a23a8144dd53e29e20fa3f666f54e774c93c63fca6eae40d5e52c39.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/images/a6583f280a23a8144dd53e29e20fa3f666f54e774c93c63fca6eae40d5e52c39.jpg)

![cdc8f8b0ad1fd306f0bd88339865c8df65e064008449deada5fb78a7424420c1.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/images/cdc8f8b0ad1fd306f0bd88339865c8df65e064008449deada5fb78a7424420c1.jpg)

![d0d7d5f045e7cac4b9aee170bc01b11c2e5e1d6eb7c33dbe753464d4e0268c22.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/images/d0d7d5f045e7cac4b9aee170bc01b11c2e5e1d6eb7c33dbe753464d4e0268c22.jpg)

![d942114c72a496a773e305c0c36d34e1e3704e166d8e8ae5271d17b5199cdb29.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/images/d942114c72a496a773e305c0c36d34e1e3704e166d8e8ae5271d17b5199cdb29.jpg)

### Tables

![0121753976dd2457e3f99e884c156362b132c1e259ddbb172d1ed92dbe158252.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/0121753976dd2457e3f99e884c156362b132c1e259ddbb172d1ed92dbe158252.jpg)

![08dc4f54eee93e90af8074ff4191fa62a73b54bd050954a5bb7d0114d25df21e.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/08dc4f54eee93e90af8074ff4191fa62a73b54bd050954a5bb7d0114d25df21e.jpg)

![0c0c1ac2d94d7a21252fdf0b81ec5d12a3e14df4797ebdc8e85abd97ce9ab2ff.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/0c0c1ac2d94d7a21252fdf0b81ec5d12a3e14df4797ebdc8e85abd97ce9ab2ff.jpg)

![0d8960f0a3b9d89c1a46604b7066c920b8c5c6c15c7d184a9d931407f8c93b1f.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/0d8960f0a3b9d89c1a46604b7066c920b8c5c6c15c7d184a9d931407f8c93b1f.jpg)

![1a204641a8e765c8c9c37c65f2610a07850d0c2abbe5bf0e4c2f3c4bc9564ddf.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/1a204641a8e765c8c9c37c65f2610a07850d0c2abbe5bf0e4c2f3c4bc9564ddf.jpg)

![33d20fbfcf295722fbf6db4a2b77045407e706817f20eabac4f6e913605d6e72.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/33d20fbfcf295722fbf6db4a2b77045407e706817f20eabac4f6e913605d6e72.jpg)

![43187a1ba34346b4e645cb3b2859f9f02abdfd1993120cc5c6054fc0ade5477c.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/43187a1ba34346b4e645cb3b2859f9f02abdfd1993120cc5c6054fc0ade5477c.jpg)

![49984f483d2a04e69cab0990a5937c7a3073a942df8fa17889c6b4029a7987cb.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/49984f483d2a04e69cab0990a5937c7a3073a942df8fa17889c6b4029a7987cb.jpg)

![521b93a3858c40e0f494b1b8feb0ed3565fb16e4abdd989cec3b716598fecbbf.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/521b93a3858c40e0f494b1b8feb0ed3565fb16e4abdd989cec3b716598fecbbf.jpg)

![69f16d6b45778e59f51d0e0f933a8602c474ebbe4a1cadcc22477b64b681a779.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/69f16d6b45778e59f51d0e0f933a8602c474ebbe4a1cadcc22477b64b681a779.jpg)

![6dc8ae62e2e2882f91e0e4051fb439daa1ca9ab3ebdeeee40bd90a05cc0e987a.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/6dc8ae62e2e2882f91e0e4051fb439daa1ca9ab3ebdeeee40bd90a05cc0e987a.jpg)

![9b2d9b25233f680f2cf2365fd703dd470f7cbc620a1edd487b873a7e14ee8f28.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/9b2d9b25233f680f2cf2365fd703dd470f7cbc620a1edd487b873a7e14ee8f28.jpg)

![bcd7d8dea4460c3ce0016aaa0374c8abf20af7630c55f93998234604470168fb.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/bcd7d8dea4460c3ce0016aaa0374c8abf20af7630c55f93998234604470168fb.jpg)

![e053f1ddcdb7a66eceaa80623676134b1ced0db5f54104dd6ea514b38aecb472.jpg](../nips_results/610_Zero-shot%20Denoising%20via%20Neural%20Compression_%20Theoretical%20and%20algorithmic%20framework/tables/e053f1ddcdb7a66eceaa80623676134b1ced0db5f54104dd6ea514b38aecb472.jpg)

## Bits Leaked per Query: Information-Theoretic Bounds for Adversarial Attacks on LLMs


### Images

![177c43cca57b1d2bcfa282a34b060dd7a215ed5f8949c13b582530fe82a8e60a.jpg](../nips_results/611_Bits%20Leaked%20per%20Query_%20Information-Theoretic%20Bounds%20for%20Adversarial%20Attacks%20on%20LLMs/images/177c43cca57b1d2bcfa282a34b060dd7a215ed5f8949c13b582530fe82a8e60a.jpg)

![7614c29352c37c5d30873531880096800732556bafa3152e05699bc9a74432b2.jpg](../nips_results/611_Bits%20Leaked%20per%20Query_%20Information-Theoretic%20Bounds%20for%20Adversarial%20Attacks%20on%20LLMs/images/7614c29352c37c5d30873531880096800732556bafa3152e05699bc9a74432b2.jpg)

![ff5fbc5d3635a4ccea6f00bbb57adda3a9fc16a418bcdaef133b73135b34acec.jpg](../nips_results/611_Bits%20Leaked%20per%20Query_%20Information-Theoretic%20Bounds%20for%20Adversarial%20Attacks%20on%20LLMs/images/ff5fbc5d3635a4ccea6f00bbb57adda3a9fc16a418bcdaef133b73135b34acec.jpg)

### Tables

![e6b697aab9cc5e675d38ad2c6c38b6f88c484cd173914c3467eb3cc259ae9b53.jpg](../nips_results/611_Bits%20Leaked%20per%20Query_%20Information-Theoretic%20Bounds%20for%20Adversarial%20Attacks%20on%20LLMs/tables/e6b697aab9cc5e675d38ad2c6c38b6f88c484cd173914c3467eb3cc259ae9b53.jpg)

## Decomposing stimulus-specific sensory neural information via diffusion models


### Images

![1b6409e56ed083175dbfa892de8b01d6e2ae9418fcf72dcbf792906e2bb74eba.jpg](../nips_results/612_Decomposing%20stimulus-specific%20sensory%20neural%20information%20via%20diffusion%20models/images/1b6409e56ed083175dbfa892de8b01d6e2ae9418fcf72dcbf792906e2bb74eba.jpg)

![1cc7b16260eb7d5887071774fb3471bfc4fb03ed1680cee4b0e4afbf511a04ee.jpg](../nips_results/612_Decomposing%20stimulus-specific%20sensory%20neural%20information%20via%20diffusion%20models/images/1cc7b16260eb7d5887071774fb3471bfc4fb03ed1680cee4b0e4afbf511a04ee.jpg)

![46f93b4edc36d5aa790d1cc138117fa921ead838a510636af490bb66ea85ef61.jpg](../nips_results/612_Decomposing%20stimulus-specific%20sensory%20neural%20information%20via%20diffusion%20models/images/46f93b4edc36d5aa790d1cc138117fa921ead838a510636af490bb66ea85ef61.jpg)

![57d6d1e8bc8f07c9b57cff470f1a667923202fe0198c74b5015fc73acdc65887.jpg](../nips_results/612_Decomposing%20stimulus-specific%20sensory%20neural%20information%20via%20diffusion%20models/images/57d6d1e8bc8f07c9b57cff470f1a667923202fe0198c74b5015fc73acdc65887.jpg)

![6a9a692350abab21a0dca894ae4c22873d066125369cce38d21cd89045b2929a.jpg](../nips_results/612_Decomposing%20stimulus-specific%20sensory%20neural%20information%20via%20diffusion%20models/images/6a9a692350abab21a0dca894ae4c22873d066125369cce38d21cd89045b2929a.jpg)

![8cef1e513aee3ef7a464bffb2cb2ad9555f090b1b6c7f33ae6938bfeb962e71e.jpg](../nips_results/612_Decomposing%20stimulus-specific%20sensory%20neural%20information%20via%20diffusion%20models/images/8cef1e513aee3ef7a464bffb2cb2ad9555f090b1b6c7f33ae6938bfeb962e71e.jpg)

![d0f330084cb31979145372dce51a64b126746aabadb3310747611086f90c0a48.jpg](../nips_results/612_Decomposing%20stimulus-specific%20sensory%20neural%20information%20via%20diffusion%20models/images/d0f330084cb31979145372dce51a64b126746aabadb3310747611086f90c0a48.jpg)

![d994054fd96f214e7d98ba8b910c8351eb39c3497d67ac5ae6199dcb56ad7634.jpg](../nips_results/612_Decomposing%20stimulus-specific%20sensory%20neural%20information%20via%20diffusion%20models/images/d994054fd96f214e7d98ba8b910c8351eb39c3497d67ac5ae6199dcb56ad7634.jpg)

### Tables

![1038c47d52660daf992c0cfe44a84d9edccacb3de613209243ad40cbaa3f5598.jpg](../nips_results/612_Decomposing%20stimulus-specific%20sensory%20neural%20information%20via%20diffusion%20models/tables/1038c47d52660daf992c0cfe44a84d9edccacb3de613209243ad40cbaa3f5598.jpg)

## The Fragile Truth of Saliency: Improving LLM Input Attribution via Attention Bias Optimization


### Images

![119c3494ae1b80edabbb479946f5a6fea21f0c1a9f08d3d1db9cd7d058c9411c.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/images/119c3494ae1b80edabbb479946f5a6fea21f0c1a9f08d3d1db9cd7d058c9411c.jpg)

![663f97402dbdf9e1d4ddcdc8de7fd92e1b6cdef71772d6ab2d58a262f197156c.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/images/663f97402dbdf9e1d4ddcdc8de7fd92e1b6cdef71772d6ab2d58a262f197156c.jpg)

![700a6d6f4febbb887d3064e93e4a1b37de1e391938c0ee956c226cf15925ab6a.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/images/700a6d6f4febbb887d3064e93e4a1b37de1e391938c0ee956c226cf15925ab6a.jpg)

![9025a7b12d61dc49ec80599a747c49ed3f6fe8ae1e24e60f9a6409ca07671f51.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/images/9025a7b12d61dc49ec80599a747c49ed3f6fe8ae1e24e60f9a6409ca07671f51.jpg)

![98257e763f318a608f80305396b9292d3857232fab3a464a6c94ba042a1f7ec9.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/images/98257e763f318a608f80305396b9292d3857232fab3a464a6c94ba042a1f7ec9.jpg)

![d0fad7c1fba38b48bbc3703cb695c3ed44c448eddb798726435efbaaec536849.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/images/d0fad7c1fba38b48bbc3703cb695c3ed44c448eddb798726435efbaaec536849.jpg)

![efdf4b4020050990b428fe147c204fdb80783e250c75509b239354425d95436e.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/images/efdf4b4020050990b428fe147c204fdb80783e250c75509b239354425d95436e.jpg)

### Tables

![187cb1ae547880b8580c066484ddc6b762c82cd38c0f5284fe41643704e0352e.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/tables/187cb1ae547880b8580c066484ddc6b762c82cd38c0f5284fe41643704e0352e.jpg)

![4207499d7a5b655450f1d7146544247e0b0d4972687d075c4e1d0c779b0a62de.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/tables/4207499d7a5b655450f1d7146544247e0b0d4972687d075c4e1d0c779b0a62de.jpg)

![6fa26193b589fe4b3e48c0e0ba53955cb0905c254e09b014f8b2876f1ad17580.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/tables/6fa26193b589fe4b3e48c0e0ba53955cb0905c254e09b014f8b2876f1ad17580.jpg)

![e82b26741c942dc4079385eceddfff56bdd40568acbf5966637ab85c2568db1c.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/tables/e82b26741c942dc4079385eceddfff56bdd40568acbf5966637ab85c2568db1c.jpg)

![fbc1a42aed80c16e543b4b3a9c1589c33d522cc2b747e6d50cf7b51d04ee9a7a.jpg](../nips_results/613_The%20Fragile%20Truth%20of%20Saliency_%20Improving%20LLM%20Input%20Attribution%20via%20Attention%20Bias%20Optimization/tables/fbc1a42aed80c16e543b4b3a9c1589c33d522cc2b747e6d50cf7b51d04ee9a7a.jpg)

## Think or Not? Exploring Thinking Efficiency in Large Reasoning Models via an Information-Theoretic Lens


### Images

![041006ede6fdd52100766699a3f443b958b4af3755c4e2ff78666dd72d106b5b.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/images/041006ede6fdd52100766699a3f443b958b4af3755c4e2ff78666dd72d106b5b.jpg)

![0a5d6bd2c3ad6d97ba4273d0d380e691e83331753268d5262f1650c48b98806f.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/images/0a5d6bd2c3ad6d97ba4273d0d380e691e83331753268d5262f1650c48b98806f.jpg)

![1479ffdeca0886e727f2f37aa43697fb8c687f7d27c78557e0db37c677595162.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/images/1479ffdeca0886e727f2f37aa43697fb8c687f7d27c78557e0db37c677595162.jpg)

![3f9e7155f7c8520a4cff9857799a7c2e73a7e362a022e5ae93cecec4e55d5626.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/images/3f9e7155f7c8520a4cff9857799a7c2e73a7e362a022e5ae93cecec4e55d5626.jpg)

![7bac0b894704b3fe0ae325c4933ee451a6d6a8b57b03b01f53796bee36dd9d4b.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/images/7bac0b894704b3fe0ae325c4933ee451a6d6a8b57b03b01f53796bee36dd9d4b.jpg)

![8b3cc1982a07037c045bf618af9efc36fda749dfa187135118fe0a11423ffd3c.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/images/8b3cc1982a07037c045bf618af9efc36fda749dfa187135118fe0a11423ffd3c.jpg)

![ac5d3e5c742e4d7c6e8dfbe2848cc09bccf39a78a75a57d912c720068a6616f2.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/images/ac5d3e5c742e4d7c6e8dfbe2848cc09bccf39a78a75a57d912c720068a6616f2.jpg)

![d047bdf6e8cb271b4e858f10e4e8ebecee7a6d2912c67cae51bdcbab2a914f26.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/images/d047bdf6e8cb271b4e858f10e4e8ebecee7a6d2912c67cae51bdcbab2a914f26.jpg)

![d13f626a8cac86ff1452dda7f3d6344d6fb8fd78108d7915f4c82e313b740a8a.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/images/d13f626a8cac86ff1452dda7f3d6344d6fb8fd78108d7915f4c82e313b740a8a.jpg)

### Tables

![63704baeab2ec101010fd243b92e2f90ee3073474b864c5e8617a620eac278b3.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/tables/63704baeab2ec101010fd243b92e2f90ee3073474b864c5e8617a620eac278b3.jpg)

![8cce61194004e9b460785b17de2948ffcff26b8f09764dd88ad48dffc659cbbe.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/tables/8cce61194004e9b460785b17de2948ffcff26b8f09764dd88ad48dffc659cbbe.jpg)

![fc4ea03b263484b6d6ce196eec7e68f4d764c1f9f128f94109afad6f85d481dd.jpg](../nips_results/614_Think%20or%20Not_%20Exploring%20Thinking%20Efficiency%20in%20Large%20Reasoning%20Models%20via%20an%20Information-Theoretic%20L/tables/fc4ea03b263484b6d6ce196eec7e68f4d764c1f9f128f94109afad6f85d481dd.jpg)

## Convergence Rates of Constrained Expected Improvement


### Images

![473e02e9704f9ae512961d0077f7849bd0fa20453b649d465055866ac29b7482.jpg](../nips_results/615_Convergence%20Rates%20of%20Constrained%20Expected%20Improvement/images/473e02e9704f9ae512961d0077f7849bd0fa20453b649d465055866ac29b7482.jpg)

![49330e22e4b9d2b36ff477654e5925283719da16352868323ca3e458ab8faf0b.jpg](../nips_results/615_Convergence%20Rates%20of%20Constrained%20Expected%20Improvement/images/49330e22e4b9d2b36ff477654e5925283719da16352868323ca3e458ab8faf0b.jpg)

![d56d95ee90c1fe524072b2bbf888aa7139d73f1c2f411402c1ff99535353c1a8.jpg](../nips_results/615_Convergence%20Rates%20of%20Constrained%20Expected%20Improvement/images/d56d95ee90c1fe524072b2bbf888aa7139d73f1c2f411402c1ff99535353c1a8.jpg)

![e7ca4143f406faeaadaa4b90b37743aa28cf5255ecf2e9f73e997724417c0be1.jpg](../nips_results/615_Convergence%20Rates%20of%20Constrained%20Expected%20Improvement/images/e7ca4143f406faeaadaa4b90b37743aa28cf5255ecf2e9f73e997724417c0be1.jpg)

![f61fe8d98b46a3e1bb9f4e43ced8c6ec3d48925dfa07583357f245dd5a04ed35.jpg](../nips_results/615_Convergence%20Rates%20of%20Constrained%20Expected%20Improvement/images/f61fe8d98b46a3e1bb9f4e43ced8c6ec3d48925dfa07583357f245dd5a04ed35.jpg)

### Tables

![7127813b94409d17126df24b561d2b3fa944fb71a3a8406f6223db5c1410396a.jpg](../nips_results/615_Convergence%20Rates%20of%20Constrained%20Expected%20Improvement/tables/7127813b94409d17126df24b561d2b3fa944fb71a3a8406f6223db5c1410396a.jpg)

## Reinforcement Learning with Imperfect Transition Predictions: A Bellman-Jensen Approach


### Images

![146f882d5dae2e6bc0e7dec2ed3962e19f68ed7a61d93ae8adf496b97f9919b1.jpg](../nips_results/616_Reinforcement%20Learning%20with%20Imperfect%20Transition%20Predictions_%20A%20Bellman-Jensen%20Approach/images/146f882d5dae2e6bc0e7dec2ed3962e19f68ed7a61d93ae8adf496b97f9919b1.jpg)

![16243b19b30645cb821324d62d029656d02e3c82586d1552a9fba9d956d3e6ff.jpg](../nips_results/616_Reinforcement%20Learning%20with%20Imperfect%20Transition%20Predictions_%20A%20Bellman-Jensen%20Approach/images/16243b19b30645cb821324d62d029656d02e3c82586d1552a9fba9d956d3e6ff.jpg)

![93360434687aa770b7c37e00e291c5b34f2829758a314cd590c669a8316d47dc.jpg](../nips_results/616_Reinforcement%20Learning%20with%20Imperfect%20Transition%20Predictions_%20A%20Bellman-Jensen%20Approach/images/93360434687aa770b7c37e00e291c5b34f2829758a314cd590c669a8316d47dc.jpg)

![af1fa6f193d1c7ca6c2e1f59d5c0a313c616e63e51a81048ca6bc105dc8b0186.jpg](../nips_results/616_Reinforcement%20Learning%20with%20Imperfect%20Transition%20Predictions_%20A%20Bellman-Jensen%20Approach/images/af1fa6f193d1c7ca6c2e1f59d5c0a313c616e63e51a81048ca6bc105dc8b0186.jpg)

![e80b5b47b5691b209c68bf30f57a20b6c5e2eef5a7674fc66f31d5762f4fd89a.jpg](../nips_results/616_Reinforcement%20Learning%20with%20Imperfect%20Transition%20Predictions_%20A%20Bellman-Jensen%20Approach/images/e80b5b47b5691b209c68bf30f57a20b6c5e2eef5a7674fc66f31d5762f4fd89a.jpg)

### Tables

![afbf5a975a0710fab7572bca007394af1b551ef19f53f11631e33fb40a37fa74.jpg](../nips_results/616_Reinforcement%20Learning%20with%20Imperfect%20Transition%20Predictions_%20A%20Bellman-Jensen%20Approach/tables/afbf5a975a0710fab7572bca007394af1b551ef19f53f11631e33fb40a37fa74.jpg)

## SegMASt3R: Geometry Grounded Segment Matching


### Images

![35fb1eefe3241e9909a0e6136a24931355dcd9740315d09692861b76563de07d.jpg](../nips_results/617_SegMASt3R_%20Geometry%20Grounded%20Segment%20Matching/images/35fb1eefe3241e9909a0e6136a24931355dcd9740315d09692861b76563de07d.jpg)

![969b0d7fecaa75767a918683ba794e7ffa95eff7a058e8da041ad4df33ca5be9.jpg](../nips_results/617_SegMASt3R_%20Geometry%20Grounded%20Segment%20Matching/images/969b0d7fecaa75767a918683ba794e7ffa95eff7a058e8da041ad4df33ca5be9.jpg)

![b7cf468e73aad9fbd6e672392431cb435fb2f8de05eb8b437e0a05f5b4e931d5.jpg](../nips_results/617_SegMASt3R_%20Geometry%20Grounded%20Segment%20Matching/images/b7cf468e73aad9fbd6e672392431cb435fb2f8de05eb8b437e0a05f5b4e931d5.jpg)

![fb905d11604acc56c44f0344f713f3d874349b7ffdacf23782875fd3db3fa2e4.jpg](../nips_results/617_SegMASt3R_%20Geometry%20Grounded%20Segment%20Matching/images/fb905d11604acc56c44f0344f713f3d874349b7ffdacf23782875fd3db3fa2e4.jpg)

### Tables

![61abc0aaa55b8599ac1f081812acac8b09a09c500a99d77bbd381e839b7a9d46.jpg](../nips_results/617_SegMASt3R_%20Geometry%20Grounded%20Segment%20Matching/tables/61abc0aaa55b8599ac1f081812acac8b09a09c500a99d77bbd381e839b7a9d46.jpg)

![61db6a9ebf68c97395cac60dc9e1a9ee4b61553e2d26b1029ee5fc592564997f.jpg](../nips_results/617_SegMASt3R_%20Geometry%20Grounded%20Segment%20Matching/tables/61db6a9ebf68c97395cac60dc9e1a9ee4b61553e2d26b1029ee5fc592564997f.jpg)

![7760901dd32176d9ad4e51ade2d1c3d4d06f2c84ae994a333d281184596eb6ad.jpg](../nips_results/617_SegMASt3R_%20Geometry%20Grounded%20Segment%20Matching/tables/7760901dd32176d9ad4e51ade2d1c3d4d06f2c84ae994a333d281184596eb6ad.jpg)

![86f429929ed934ae2d8627db610e9e1869983b5d7bcd7f7a613744dd9030ae4e.jpg](../nips_results/617_SegMASt3R_%20Geometry%20Grounded%20Segment%20Matching/tables/86f429929ed934ae2d8627db610e9e1869983b5d7bcd7f7a613744dd9030ae4e.jpg)

![8f9b79bf3f79fc2901ca890d30774ad22a176253bfd514564e7ef65e4bb8931d.jpg](../nips_results/617_SegMASt3R_%20Geometry%20Grounded%20Segment%20Matching/tables/8f9b79bf3f79fc2901ca890d30774ad22a176253bfd514564e7ef65e4bb8931d.jpg)

![d1899a52066efe724c18eec43b064c024f5d02cc6b79c8ed178092214e79bb93.jpg](../nips_results/617_SegMASt3R_%20Geometry%20Grounded%20Segment%20Matching/tables/d1899a52066efe724c18eec43b064c024f5d02cc6b79c8ed178092214e79bb93.jpg)

![e212db58efc84ea78f7dfcdbced653b9802d41ab884d733b3c71c0ce724bf1d6.jpg](../nips_results/617_SegMASt3R_%20Geometry%20Grounded%20Segment%20Matching/tables/e212db58efc84ea78f7dfcdbced653b9802d41ab884d733b3c71c0ce724bf1d6.jpg)

## Any-stepsize Gradient Descent for Separable Data under Fenchel–Young Losses


### Images

![318b564a353d18e38c8cfc26b30171758722bc0cfd61b0a7d60ced54da170f61.jpg](../nips_results/618_Any-stepsize%20Gradient%20Descent%20for%20Separable%20Data%20under%20Fenchel%E2%80%93Young%20Losses/images/318b564a353d18e38c8cfc26b30171758722bc0cfd61b0a7d60ced54da170f61.jpg)

![54beee0e96b6951c2ef6f70635a2b1fa5f5065da482eb55be93e98cccc302a34.jpg](../nips_results/618_Any-stepsize%20Gradient%20Descent%20for%20Separable%20Data%20under%20Fenchel%E2%80%93Young%20Losses/images/54beee0e96b6951c2ef6f70635a2b1fa5f5065da482eb55be93e98cccc302a34.jpg)

![adecc73642964b3de8388c652d1d47a829a77136c467e6ebded329ebc7000670.jpg](../nips_results/618_Any-stepsize%20Gradient%20Descent%20for%20Separable%20Data%20under%20Fenchel%E2%80%93Young%20Losses/images/adecc73642964b3de8388c652d1d47a829a77136c467e6ebded329ebc7000670.jpg)

### Tables

![9455d71e93b583de339d3765d4c501195c2d63e88da44e3d885cc7e8323fed4d.jpg](../nips_results/618_Any-stepsize%20Gradient%20Descent%20for%20Separable%20Data%20under%20Fenchel%E2%80%93Young%20Losses/tables/9455d71e93b583de339d3765d4c501195c2d63e88da44e3d885cc7e8323fed4d.jpg)

## Searching Latent Program Spaces


### Images

![00c74e2283fc7cf1109d765aa0651783898483a5e4bdffda5a5bbbf26d471843.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/00c74e2283fc7cf1109d765aa0651783898483a5e4bdffda5a5bbbf26d471843.jpg)

![0f5908279fda7f37f67586e7ba9f17eed8103dbe14eb6e3a8d05057cffc9330f.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/0f5908279fda7f37f67586e7ba9f17eed8103dbe14eb6e3a8d05057cffc9330f.jpg)

![1458aca34d2f9606ed6fb4fb2c11f5c85ac66ed9675652650e8bd85745597366.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/1458aca34d2f9606ed6fb4fb2c11f5c85ac66ed9675652650e8bd85745597366.jpg)

![2032dec45490540575a8e01ea51de78f23f8faf81e386b8b5b30a1c943c44aab.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/2032dec45490540575a8e01ea51de78f23f8faf81e386b8b5b30a1c943c44aab.jpg)

![2436239d0986d8378253acc8edaaa4d36370954d6e4a123703a7f2611e0cc17d.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/2436239d0986d8378253acc8edaaa4d36370954d6e4a123703a7f2611e0cc17d.jpg)

![24a45c88f80e826b23e661b68ac16ac9dd06458496d11aa697ffce327291c12a.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/24a45c88f80e826b23e661b68ac16ac9dd06458496d11aa697ffce327291c12a.jpg)

![252309a93594f63eab30905db21304260a7797d4e02429e7839651c7727f8d52.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/252309a93594f63eab30905db21304260a7797d4e02429e7839651c7727f8d52.jpg)

![41a73fba6e6c0f4afadbdf3e049d5ceffed1b3a2bb4b1928db2eb3634e15493d.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/41a73fba6e6c0f4afadbdf3e049d5ceffed1b3a2bb4b1928db2eb3634e15493d.jpg)

![439b15c43a1aa1c91cb634a7a06d964daa80d5ac6b84835fa22f0c0a9ef0429b.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/439b15c43a1aa1c91cb634a7a06d964daa80d5ac6b84835fa22f0c0a9ef0429b.jpg)

![65a7ef2cfdce66028748fcb9e53f7029edd2f3347aa11c385b1dd0d64e5c119d.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/65a7ef2cfdce66028748fcb9e53f7029edd2f3347aa11c385b1dd0d64e5c119d.jpg)

![6df8436df6e3ae24f2a6363702d05b334e54a8a6115a7fe8aa6c2a198b3adc1f.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/6df8436df6e3ae24f2a6363702d05b334e54a8a6115a7fe8aa6c2a198b3adc1f.jpg)

![88926987c77d8787089a8568ee2b740dc93c1856fb3d83458e39d9f8a5b23012.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/88926987c77d8787089a8568ee2b740dc93c1856fb3d83458e39d9f8a5b23012.jpg)

![8c8fe459c610d881a27699b31b62504ea30f50832ae65fff168e3e3864b56f93.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/8c8fe459c610d881a27699b31b62504ea30f50832ae65fff168e3e3864b56f93.jpg)

![9300f039af062868dc03ce6ab95795c0f2ad089eb09e74c8323cea2b5bf21a63.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/9300f039af062868dc03ce6ab95795c0f2ad089eb09e74c8323cea2b5bf21a63.jpg)

![ad3cff2e1e387bfb44bf1ff6ced3f628ed539776c530ef6c4d1a7da31521e4e0.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/ad3cff2e1e387bfb44bf1ff6ced3f628ed539776c530ef6c4d1a7da31521e4e0.jpg)

![be2e44f4622ad2d48b05cc4ef4e44b03bc600c187015e41e9f322627e6d10a04.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/be2e44f4622ad2d48b05cc4ef4e44b03bc600c187015e41e9f322627e6d10a04.jpg)

![bf40f9d467bd990abf990c23dcdb490beebe29f0090493a302829293c2688799.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/bf40f9d467bd990abf990c23dcdb490beebe29f0090493a302829293c2688799.jpg)

![d08ca87814180bff8da6ffd1de25dc4db5e57803aa5c7f6119aadb038b60c90b.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/d08ca87814180bff8da6ffd1de25dc4db5e57803aa5c7f6119aadb038b60c90b.jpg)

![e6ab11778346955e7cd9cd53dc4ac5753c5a1f16ab1fc10a7399c3e2d6cbeb42.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/e6ab11778346955e7cd9cd53dc4ac5753c5a1f16ab1fc10a7399c3e2d6cbeb42.jpg)

![e99ee03e61897c41ab654c8591ba593acff778690c3d47f3db5e264a3075b844.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/e99ee03e61897c41ab654c8591ba593acff778690c3d47f3db5e264a3075b844.jpg)

![f1d96d9c3201e45a45af0c9ec04a8d854750815fa5f4dd9ced5fedb070500e5c.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/f1d96d9c3201e45a45af0c9ec04a8d854750815fa5f4dd9ced5fedb070500e5c.jpg)

![fb65f9513e08955a7a3c8dc86c3b483f443e13e4f3009280f238d0d7a87c2b6d.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/images/fb65f9513e08955a7a3c8dc86c3b483f443e13e4f3009280f238d0d7a87c2b6d.jpg)

### Tables

![11ef8a739e9408a755540122c4ce5160df98b0b4c974872d349ef34c3482917a.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/11ef8a739e9408a755540122c4ce5160df98b0b4c974872d349ef34c3482917a.jpg)

![1d16591dc59b19ba48e718bfee36b34fee511747a1d76fafd724710c2dc885bd.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/1d16591dc59b19ba48e718bfee36b34fee511747a1d76fafd724710c2dc885bd.jpg)

![220cc8d07a320db2e20b7d3a9f14ef808ce9aa6098bcd484b721c97a3242d405.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/220cc8d07a320db2e20b7d3a9f14ef808ce9aa6098bcd484b721c97a3242d405.jpg)

![29f6ce949eca0fa56994b1cef0cfb98723ad4d2ab6c101daa7b3c168eff5445c.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/29f6ce949eca0fa56994b1cef0cfb98723ad4d2ab6c101daa7b3c168eff5445c.jpg)

![34a62b53c96a627eb4eca1d6670c2bb512e56fe9d019e4f294ae0f9dcfe73c41.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/34a62b53c96a627eb4eca1d6670c2bb512e56fe9d019e4f294ae0f9dcfe73c41.jpg)

![3933002383f0f381c7df2ed447d1ebdbdfc163bf366dabba2f36cd2f0261c341.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/3933002383f0f381c7df2ed447d1ebdbdfc163bf366dabba2f36cd2f0261c341.jpg)

![422ea7a713c9d225e08830505865be75c23135a5bd111cc96eda2a36fb834c52.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/422ea7a713c9d225e08830505865be75c23135a5bd111cc96eda2a36fb834c52.jpg)

![44c6e0d5683b2f0bc97b580383fe87ddd19e06aa19a4ff86181e7cdaec2314cc.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/44c6e0d5683b2f0bc97b580383fe87ddd19e06aa19a4ff86181e7cdaec2314cc.jpg)

![48203c78cc197f6b731ac60005edfb1f0bc22c004714e9fe5f320f9d30c48d5a.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/48203c78cc197f6b731ac60005edfb1f0bc22c004714e9fe5f320f9d30c48d5a.jpg)

![4e6a614d28b29d6ef111d018355a8125bc9963087e4cf322dbb9c524d25af9fe.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/4e6a614d28b29d6ef111d018355a8125bc9963087e4cf322dbb9c524d25af9fe.jpg)

![50fcab18296529554a6cb1fe4f28315990f8d2d91ba44a430f2ca862045d4858.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/50fcab18296529554a6cb1fe4f28315990f8d2d91ba44a430f2ca862045d4858.jpg)

![6664c465dd32eaa90f16340984b7c70c4c0bbbd5fdb4dcd10b00478aa7d5afe6.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/6664c465dd32eaa90f16340984b7c70c4c0bbbd5fdb4dcd10b00478aa7d5afe6.jpg)

![91ad980198588d2e179d3ffc97cf36e150ea88df7408e41ea437bf0a6380a0a6.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/91ad980198588d2e179d3ffc97cf36e150ea88df7408e41ea437bf0a6380a0a6.jpg)

![964d9cb713fc0531ab4c2d642d8a2134648e7e9cfadb252849ea6c3bc6477590.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/964d9cb713fc0531ab4c2d642d8a2134648e7e9cfadb252849ea6c3bc6477590.jpg)

![caa881b12bb6ec4daadc121e3e53bddc3ecaf24581a757413c452f786c788e55.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/caa881b12bb6ec4daadc121e3e53bddc3ecaf24581a757413c452f786c788e55.jpg)

![cd289317d171f319fac9e63039395090f877d689866cf971161521afce3bf75b.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/cd289317d171f319fac9e63039395090f877d689866cf971161521afce3bf75b.jpg)

![d27aa3efa1cd1a00b4f6e736e8860f6e5de9384b162ad9a1bec7dfb0d29fc2b0.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/d27aa3efa1cd1a00b4f6e736e8860f6e5de9384b162ad9a1bec7dfb0d29fc2b0.jpg)

![df8479517ad981a47f5742eea9e2b17713562c4770767c649c5e4af06093dfdc.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/df8479517ad981a47f5742eea9e2b17713562c4770767c649c5e4af06093dfdc.jpg)

![e9bb160162f52fe7ee3e046c7fc16b4c1f9ae78bcc51b75af638b95172dd61e9.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/e9bb160162f52fe7ee3e046c7fc16b4c1f9ae78bcc51b75af638b95172dd61e9.jpg)

![eaa1ca828c3ad0f8b513358641e3377532ee4e79a9751bdcd0c90556ea2d82a9.jpg](../nips_results/619_Searching%20Latent%20Program%20Spaces/tables/eaa1ca828c3ad0f8b513358641e3377532ee4e79a9751bdcd0c90556ea2d82a9.jpg)

## Multi-Agent Learning under Uncertainty: Recurrence vs. Concentration


### Images

![04a81a052e1f6661a7c25e6a8afeecbdf0acde1e51f5d529ec9fea0f81abddbd.jpg](../nips_results/620_Multi-Agent%20Learning%20under%20Uncertainty_%20Recurrence%20vs.%20Concentration/images/04a81a052e1f6661a7c25e6a8afeecbdf0acde1e51f5d529ec9fea0f81abddbd.jpg)

![3f143120b5739ae68c4275823fea8f5c725b3722a3d93295517760bea6f5b58d.jpg](../nips_results/620_Multi-Agent%20Learning%20under%20Uncertainty_%20Recurrence%20vs.%20Concentration/images/3f143120b5739ae68c4275823fea8f5c725b3722a3d93295517760bea6f5b58d.jpg)

![81948e9eb8586d256eddbc7c14fa60958e71b5dd6acb524e894c7f1d8cafb251.jpg](../nips_results/620_Multi-Agent%20Learning%20under%20Uncertainty_%20Recurrence%20vs.%20Concentration/images/81948e9eb8586d256eddbc7c14fa60958e71b5dd6acb524e894c7f1d8cafb251.jpg)

![b5964b3e4c973a7a2102079e27b3ed12dbd8b3fd79ab33e190d8786b8e6c7a75.jpg](../nips_results/620_Multi-Agent%20Learning%20under%20Uncertainty_%20Recurrence%20vs.%20Concentration/images/b5964b3e4c973a7a2102079e27b3ed12dbd8b3fd79ab33e190d8786b8e6c7a75.jpg)

![c41ba20c2280b68025ddc88c2ab35f2ab3f19f4fc16b1c0d59d286475471dd59.jpg](../nips_results/620_Multi-Agent%20Learning%20under%20Uncertainty_%20Recurrence%20vs.%20Concentration/images/c41ba20c2280b68025ddc88c2ab35f2ab3f19f4fc16b1c0d59d286475471dd59.jpg)

## QFFT, Question-Free Fine-Tuning for Adaptive Reasoning


### Images

![144545dde14efc3e8a2664acfbc7e423f779984d0599196ec863cb58b8637632.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/images/144545dde14efc3e8a2664acfbc7e423f779984d0599196ec863cb58b8637632.jpg)

![1680b87e941ee489a5f79c8c91cbea32a135ae9ea65749280102f096c7f6ca38.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/images/1680b87e941ee489a5f79c8c91cbea32a135ae9ea65749280102f096c7f6ca38.jpg)

![2eda0e3c8a3ec8b3f1bf406b913a4de28e45d8659582fe5af8758219637766e0.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/images/2eda0e3c8a3ec8b3f1bf406b913a4de28e45d8659582fe5af8758219637766e0.jpg)

![46b8594ae4e1309e40b758978806e1d469eb67fd7e3f2a340a7879284a1ca84f.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/images/46b8594ae4e1309e40b758978806e1d469eb67fd7e3f2a340a7879284a1ca84f.jpg)

![4c9cca9de566a98c6a4f3832f120bec4f087f9924d4d88702d58de4ebb1052f2.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/images/4c9cca9de566a98c6a4f3832f120bec4f087f9924d4d88702d58de4ebb1052f2.jpg)

![9e3f2ac736c6b663a7c8610527ebcb4b1b277c04eaba0ba5ef107b4fc4420b41.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/images/9e3f2ac736c6b663a7c8610527ebcb4b1b277c04eaba0ba5ef107b4fc4420b41.jpg)

![a30140eb8674185ea1b1dcba1d08f714bc7055bae911aca8a6b0b84239982742.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/images/a30140eb8674185ea1b1dcba1d08f714bc7055bae911aca8a6b0b84239982742.jpg)

![a642e73fe713a14fe870ed4737a03aa4d46d792c3d824c8a2ba6ee13a5861855.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/images/a642e73fe713a14fe870ed4737a03aa4d46d792c3d824c8a2ba6ee13a5861855.jpg)

![be2e16c568a30cd3e3e682ed05d6e9552a158b44f122f839caecf52ba4bc8d3c.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/images/be2e16c568a30cd3e3e682ed05d6e9552a158b44f122f839caecf52ba4bc8d3c.jpg)

![c236fbebeb4606da108f1541f7af0dcbf59c589713a4ea5bb8e5a00ca12705bf.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/images/c236fbebeb4606da108f1541f7af0dcbf59c589713a4ea5bb8e5a00ca12705bf.jpg)

### Tables

![00176339b72747e595c9c74afcea941809466709b7b2433e051162610e71a87a.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/tables/00176339b72747e595c9c74afcea941809466709b7b2433e051162610e71a87a.jpg)

![0a78c0d807e8d6d6a695d239f450ad798cf825371bc135d3a4c3309f60481a0d.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/tables/0a78c0d807e8d6d6a695d239f450ad798cf825371bc135d3a4c3309f60481a0d.jpg)

![3a89953901748cb34bdd657adc11e882b657c9c00ac7b5a3cdd2dcefeb068943.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/tables/3a89953901748cb34bdd657adc11e882b657c9c00ac7b5a3cdd2dcefeb068943.jpg)

![41fb19b0a03f39ca46bf88e22a7c23ca283ab24a7f9716ee6857414be6dfda3e.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/tables/41fb19b0a03f39ca46bf88e22a7c23ca283ab24a7f9716ee6857414be6dfda3e.jpg)

![45ff114f6f056cb1e65c5d871206f99e79c45941596e53545fa55422e2272eda.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/tables/45ff114f6f056cb1e65c5d871206f99e79c45941596e53545fa55422e2272eda.jpg)

![a5e8f3e2191e75b4e4e36d1d947ae15b8c0dcc27adbbc3be8a2a354fe7db59c8.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/tables/a5e8f3e2191e75b4e4e36d1d947ae15b8c0dcc27adbbc3be8a2a354fe7db59c8.jpg)

![b919bf20d0b8aedad7617a5ffeb9e6a483a2cc1fd14f1a83e482f48d3ac2b2fd.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/tables/b919bf20d0b8aedad7617a5ffeb9e6a483a2cc1fd14f1a83e482f48d3ac2b2fd.jpg)

![d0e2879362723356013a6a3562c3931a5e3f49f399b9056a144cd355ebcbe5cf.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/tables/d0e2879362723356013a6a3562c3931a5e3f49f399b9056a144cd355ebcbe5cf.jpg)

![fa9e922d57d5313700501b9e1bba8d6d930e152fa085bdb9ab33157eb3128b41.jpg](../nips_results/621_QFFT%2C%20Question-Free%20Fine-Tuning%20for%20Adaptive%20Reasoning/tables/fa9e922d57d5313700501b9e1bba8d6d930e152fa085bdb9ab33157eb3128b41.jpg)

## DeepDiver: Adaptive Web-Search Intensity Scaling via Reinforcement Learning


### Images

![1c7ff086c2c4bba33ccebc1848f611f2c94d8e46d289816fbaf4af629651cd1d.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/images/1c7ff086c2c4bba33ccebc1848f611f2c94d8e46d289816fbaf4af629651cd1d.jpg)

![51c84971675e34a6a610ebf8fe3e8535c8621de5465593799d2e708f29bca7cb.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/images/51c84971675e34a6a610ebf8fe3e8535c8621de5465593799d2e708f29bca7cb.jpg)

![72abe3a059d028a024f3f7e052bd767abc7c1df2afe69a80cfbabf481281ce22.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/images/72abe3a059d028a024f3f7e052bd767abc7c1df2afe69a80cfbabf481281ce22.jpg)

![9a7e252481f11d4044c566f804b6e683cc84e181887be97980567492851ea094.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/images/9a7e252481f11d4044c566f804b6e683cc84e181887be97980567492851ea094.jpg)

![b196ccc425306dcb2651d0c07af992607319da62269cef65569236cba7a18e29.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/images/b196ccc425306dcb2651d0c07af992607319da62269cef65569236cba7a18e29.jpg)

![dc3c670e65755b4dc15e7c0b0cf9257e85601ea6f2c9cf5c84e5e99431291ec1.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/images/dc3c670e65755b4dc15e7c0b0cf9257e85601ea6f2c9cf5c84e5e99431291ec1.jpg)

![ddda2e60de7b2ea72a1dbb985f77c5f0c33d9a12a54f7143446bf2cba4d4538e.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/images/ddda2e60de7b2ea72a1dbb985f77c5f0c33d9a12a54f7143446bf2cba4d4538e.jpg)

![e48ccd4782a17ae5dda6e056ee14861bf3f3ba95783a787cd310ff11d0a1b8fb.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/images/e48ccd4782a17ae5dda6e056ee14861bf3f3ba95783a787cd310ff11d0a1b8fb.jpg)

![eab8f2c5b4fb1f7f8676736444fe2c3a699f7a8cdcdc7bc36bec88306a42b5e6.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/images/eab8f2c5b4fb1f7f8676736444fe2c3a699f7a8cdcdc7bc36bec88306a42b5e6.jpg)

![ff1cd6b6a7059d0e2fd4354210940347d9c1655377feeb8ab8ce4fca7f3032ac.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/images/ff1cd6b6a7059d0e2fd4354210940347d9c1655377feeb8ab8ce4fca7f3032ac.jpg)

### Tables

![03d581c447902cd801a9febf3a8783b498823787eeaa881d4948990a800a2edf.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/tables/03d581c447902cd801a9febf3a8783b498823787eeaa881d4948990a800a2edf.jpg)

![1816eb3ddca5532a84c3cd3e39aa48e2ede2bc31cf688cce86460fcdb743ba2c.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/tables/1816eb3ddca5532a84c3cd3e39aa48e2ede2bc31cf688cce86460fcdb743ba2c.jpg)

![347946d7785a1adc75eec7154637d8acbe12e4e44db4f14852fc24f8320a283a.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/tables/347946d7785a1adc75eec7154637d8acbe12e4e44db4f14852fc24f8320a283a.jpg)

![3f04dd9ff4ea49454bf8a16efbc7ba461e0368ab7a8ca254d873b31a560a0509.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/tables/3f04dd9ff4ea49454bf8a16efbc7ba461e0368ab7a8ca254d873b31a560a0509.jpg)

![5a8ec7d7406bafab27b418796ad27bf9f282312f18d022d5d14f090aaf79d66b.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/tables/5a8ec7d7406bafab27b418796ad27bf9f282312f18d022d5d14f090aaf79d66b.jpg)

![6faad81611731b8ec06951109cd4b491866100d2d17f9dfd1546343db00adfcd.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/tables/6faad81611731b8ec06951109cd4b491866100d2d17f9dfd1546343db00adfcd.jpg)

![b63ca6ebeb651e40f199d81c3ce809f0fe2ef1fd5665f20f6d30f814e231585b.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/tables/b63ca6ebeb651e40f199d81c3ce809f0fe2ef1fd5665f20f6d30f814e231585b.jpg)

![d9a47facee35a9d0a9ad4b1d3f46c56df62842166674994704f53960a336ca22.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/tables/d9a47facee35a9d0a9ad4b1d3f46c56df62842166674994704f53960a336ca22.jpg)

![dc13e481904706f91b716d51252f70fddeb3cb9720c919644f9b59e42e7474fc.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/tables/dc13e481904706f91b716d51252f70fddeb3cb9720c919644f9b59e42e7474fc.jpg)

![eb2eda38c8dd853339a79c384a35ce3a31078b7bf9206e33cbd0811dcb8b23c2.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/tables/eb2eda38c8dd853339a79c384a35ce3a31078b7bf9206e33cbd0811dcb8b23c2.jpg)

![f262597be01c20cdd217aa7c44cec0da07a3419cb997dbafbaf24d7d4cb4ace1.jpg](../nips_results/622_DeepDiver_%20Adaptive%20Web-Search%20Intensity%20Scaling%20via%20Reinforcement%20Learning/tables/f262597be01c20cdd217aa7c44cec0da07a3419cb997dbafbaf24d7d4cb4ace1.jpg)

## IA-GGAD: Zero-shot Generalist Graph Anomaly Detection via Invariant and Affinity Learning


### Images

![2be0842b017b1925d07b25f0276d02ffabc8a00fe4e73cc930b0ee0096fcfd40.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/images/2be0842b017b1925d07b25f0276d02ffabc8a00fe4e73cc930b0ee0096fcfd40.jpg)

![41967974e3b46dd88a345aac90fcf33e23843d9574b2db0ee68f5cbc4996b326.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/images/41967974e3b46dd88a345aac90fcf33e23843d9574b2db0ee68f5cbc4996b326.jpg)

![957ddb55d2237c70ec0d38e0fd88f9f2eb4884e3e03e15e944d7703ed8f6fc84.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/images/957ddb55d2237c70ec0d38e0fd88f9f2eb4884e3e03e15e944d7703ed8f6fc84.jpg)

![cb054177d0d3489e10a6adcb6ae23c09e130a4894b67c08be828a4ddca21a5ad.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/images/cb054177d0d3489e10a6adcb6ae23c09e130a4894b67c08be828a4ddca21a5ad.jpg)

### Tables

![19828b67479f4df323af8838101730b91929139866480929fe33daefae03315a.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/tables/19828b67479f4df323af8838101730b91929139866480929fe33daefae03315a.jpg)

![665d4adaae8d089ff1e2511b6ab482fb3f25160d09e688f091168c68f7848da7.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/tables/665d4adaae8d089ff1e2511b6ab482fb3f25160d09e688f091168c68f7848da7.jpg)

![6b5e37341a84b9698a30b1e7cafc08a344d012338b433f16b26b7dc0b61520e2.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/tables/6b5e37341a84b9698a30b1e7cafc08a344d012338b433f16b26b7dc0b61520e2.jpg)

![e389bd5019ed0db77cd5161103c9ea7fe803d47afde3f4a1622dc3c962fde238.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/tables/e389bd5019ed0db77cd5161103c9ea7fe803d47afde3f4a1622dc3c962fde238.jpg)

![efb435205790beaaa624ac28037a857e78239b8b31143cac0f0ddea84027e9c0.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/tables/efb435205790beaaa624ac28037a857e78239b8b31143cac0f0ddea84027e9c0.jpg)

![f04abd5edeb613a3cbdec29ab570486c083428da5f38a6237b579031494e6a6d.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/tables/f04abd5edeb613a3cbdec29ab570486c083428da5f38a6237b579031494e6a6d.jpg)

![f1e882960ae561c4bf862492a73c3054506ef8bbb6bf7db5d9ce25f1912b5bd1.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/tables/f1e882960ae561c4bf862492a73c3054506ef8bbb6bf7db5d9ce25f1912b5bd1.jpg)

![f73ad471f4cb75311f70ff2a92b7fc077138ec649e119cef591b57862aadfd0b.jpg](../nips_results/623_IA-GGAD_%20Zero-shot%20Generalist%20Graph%20Anomaly%20Detection%20via%20Invariant%20and%20Affinity%20Learning/tables/f73ad471f4cb75311f70ff2a92b7fc077138ec649e119cef591b57862aadfd0b.jpg)

## Mean-Field Sampling for Cooperative Multi-Agent Reinforcement Learning


### Images

![135b3b3f65cc7420e3c3209d5ac3c0b231eb515b005baca85289e10111c0ec15.jpg](../nips_results/624_Mean-Field%20Sampling%20for%20Cooperative%20Multi-Agent%20Reinforcement%20Learning/images/135b3b3f65cc7420e3c3209d5ac3c0b231eb515b005baca85289e10111c0ec15.jpg)

![183fe1f0bc7231b92637fd50b251b988b74aeaa53a1b2564a6b8f2ee4d21e18d.jpg](../nips_results/624_Mean-Field%20Sampling%20for%20Cooperative%20Multi-Agent%20Reinforcement%20Learning/images/183fe1f0bc7231b92637fd50b251b988b74aeaa53a1b2564a6b8f2ee4d21e18d.jpg)

![d3acad0f00397f15e4ce1e917a6b6b17d2dad6a068407a302cd52611116447c9.jpg](../nips_results/624_Mean-Field%20Sampling%20for%20Cooperative%20Multi-Agent%20Reinforcement%20Learning/images/d3acad0f00397f15e4ce1e917a6b6b17d2dad6a068407a302cd52611116447c9.jpg)

![ea5d44274abe8e2053b5179c8a96f40d9e41ffb6a136fdfa2140d35df4c5cda7.jpg](../nips_results/624_Mean-Field%20Sampling%20for%20Cooperative%20Multi-Agent%20Reinforcement%20Learning/images/ea5d44274abe8e2053b5179c8a96f40d9e41ffb6a136fdfa2140d35df4c5cda7.jpg)

### Tables

![027842600c95dae1795f3befad6631878275d71e6035d655c9cefeb1c621f7b9.jpg](../nips_results/624_Mean-Field%20Sampling%20for%20Cooperative%20Multi-Agent%20Reinforcement%20Learning/tables/027842600c95dae1795f3befad6631878275d71e6035d655c9cefeb1c621f7b9.jpg)

![bc3707e1f4bf8562ac801ff2702d288834b1d2e52761c115054307cf75db73e6.jpg](../nips_results/624_Mean-Field%20Sampling%20for%20Cooperative%20Multi-Agent%20Reinforcement%20Learning/tables/bc3707e1f4bf8562ac801ff2702d288834b1d2e52761c115054307cf75db73e6.jpg)

## Scalable Fingerprinting of Large Language Models


### Images

![109fbe0ae75962467d4ecad69181af1fc3d77e78f704d6b8f2219043ec37b8d2.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/109fbe0ae75962467d4ecad69181af1fc3d77e78f704d6b8f2219043ec37b8d2.jpg)

![2b6a2020df3833465227f1452ce06c9c351c0f37d8ea2b01e282310448824c1a.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/2b6a2020df3833465227f1452ce06c9c351c0f37d8ea2b01e282310448824c1a.jpg)

![38f5301074558535e762e44061c29062592cd8e26058103cc9c8a602861d1bf2.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/38f5301074558535e762e44061c29062592cd8e26058103cc9c8a602861d1bf2.jpg)

![5fa56d9c28e72a0ac9857945e486d3ba2488f0e800b26713b2233d38da116971.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/5fa56d9c28e72a0ac9857945e486d3ba2488f0e800b26713b2233d38da116971.jpg)

![62aa2414270360ab67c28787993fef5e7e7bbb65157ad2807535d97d876342f1.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/62aa2414270360ab67c28787993fef5e7e7bbb65157ad2807535d97d876342f1.jpg)

![6e8f5494b1921283ab95e4c143a3f551ab722b0223f97ca7eed7d0d64c27072e.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/6e8f5494b1921283ab95e4c143a3f551ab722b0223f97ca7eed7d0d64c27072e.jpg)

![74071d2171f8c324b4ad894c84305def7eee427433d62eed5fcd69975f8fbf55.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/74071d2171f8c324b4ad894c84305def7eee427433d62eed5fcd69975f8fbf55.jpg)

![91705237c3b23d3303acba2fe473fd7f4a5dfb7c84e880d70c707149b9f703ab.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/91705237c3b23d3303acba2fe473fd7f4a5dfb7c84e880d70c707149b9f703ab.jpg)

![b50c84375c40376af0346a9e46d384bcaad38b57a1be014b5ae9d503967a6ab9.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/b50c84375c40376af0346a9e46d384bcaad38b57a1be014b5ae9d503967a6ab9.jpg)

![bbd30da376e118cf44b01b6207a069a4ea66441375554c8dc6efcebe13867155.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/bbd30da376e118cf44b01b6207a069a4ea66441375554c8dc6efcebe13867155.jpg)

![c1b25359023136f2089f83d499cf3dd293d90d0843be3aab40b1777a8efd43fd.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/c1b25359023136f2089f83d499cf3dd293d90d0843be3aab40b1777a8efd43fd.jpg)

![d1bdf1eb58d727217c28a6cbc585076f5e0f3ca4042beecf540c1b8805a97fd4.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/d1bdf1eb58d727217c28a6cbc585076f5e0f3ca4042beecf540c1b8805a97fd4.jpg)

![e9e84802f4f8f0bff178b61f2eb825e7be3b4637dcdc2749477a4fb1a5ef6d15.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/e9e84802f4f8f0bff178b61f2eb825e7be3b4637dcdc2749477a4fb1a5ef6d15.jpg)

![efb30ea56c843c9326067e6ab035dbff8b6b4971b781ab6a9685c19e90a43617.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/efb30ea56c843c9326067e6ab035dbff8b6b4971b781ab6a9685c19e90a43617.jpg)

![f72449e941bf817dcc506bcd45b4220e8fab038b88078f23bbbde212ddd15981.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/f72449e941bf817dcc506bcd45b4220e8fab038b88078f23bbbde212ddd15981.jpg)

![f7c8f0d57e0ee52b2dc748b23b01cf89038e2406299f2a9b7b99a3934770ae4f.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/images/f7c8f0d57e0ee52b2dc748b23b01cf89038e2406299f2a9b7b99a3934770ae4f.jpg)

### Tables

![0e4df89eddc745f03cdd9949f960ddff37469a6ecda616a55efb398ee6395c2c.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/tables/0e4df89eddc745f03cdd9949f960ddff37469a6ecda616a55efb398ee6395c2c.jpg)

![25b5f656c9696336f52cebc2b60032b11fc9ad1a4871c784596e50ecd3249866.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/tables/25b5f656c9696336f52cebc2b60032b11fc9ad1a4871c784596e50ecd3249866.jpg)

![38185074506a15b3c772d4c72bf3cc2dfe260f538eb7f520b26cdbbcda7bbf63.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/tables/38185074506a15b3c772d4c72bf3cc2dfe260f538eb7f520b26cdbbcda7bbf63.jpg)

![5403e279caf44c3862c2af986c9743d3a056fc49da20e52e434049925ed53874.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/tables/5403e279caf44c3862c2af986c9743d3a056fc49da20e52e434049925ed53874.jpg)

![bb05e48cb3bec8512c5a86459da697708776ce4861908df87ac01a26302fe11d.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/tables/bb05e48cb3bec8512c5a86459da697708776ce4861908df87ac01a26302fe11d.jpg)

![e7236010a635d1bc84a172083c14cc0cca15ab12eaa07fdad1e4e075ccea042e.jpg](../nips_results/625_Scalable%20Fingerprinting%20of%20Large%20Language%20Models/tables/e7236010a635d1bc84a172083c14cc0cca15ab12eaa07fdad1e4e075ccea042e.jpg)

## LABridge: Text–Image Latent Alignment Framework via Mean-Conditioned OU Process


### Images

![14cd08f2874ec12a5c03b0d39c3f59901473bd856a339830de97ffaa11325f10.jpg](../nips_results/626_LABridge_%20Text%E2%80%93Image%20Latent%20Alignment%20Framework%20via%20Mean-Conditioned%20OU%20Process/images/14cd08f2874ec12a5c03b0d39c3f59901473bd856a339830de97ffaa11325f10.jpg)

![4526114c022a4c90b14a058fc5a6decbabd0fa9a6354689a86efbf2a85bc740e.jpg](../nips_results/626_LABridge_%20Text%E2%80%93Image%20Latent%20Alignment%20Framework%20via%20Mean-Conditioned%20OU%20Process/images/4526114c022a4c90b14a058fc5a6decbabd0fa9a6354689a86efbf2a85bc740e.jpg)

![72cebbf531f570e31055bf1e1f81441d3bd4ae4bf324bd5383c3c27d41663102.jpg](../nips_results/626_LABridge_%20Text%E2%80%93Image%20Latent%20Alignment%20Framework%20via%20Mean-Conditioned%20OU%20Process/images/72cebbf531f570e31055bf1e1f81441d3bd4ae4bf324bd5383c3c27d41663102.jpg)

![a12633d3d828b902d509e2b167276457454877054933d2266242f4a375b33630.jpg](../nips_results/626_LABridge_%20Text%E2%80%93Image%20Latent%20Alignment%20Framework%20via%20Mean-Conditioned%20OU%20Process/images/a12633d3d828b902d509e2b167276457454877054933d2266242f4a375b33630.jpg)

![d403fe912d4447b03438739b07ca6567409542764ace21ba5996be42c4a7287d.jpg](../nips_results/626_LABridge_%20Text%E2%80%93Image%20Latent%20Alignment%20Framework%20via%20Mean-Conditioned%20OU%20Process/images/d403fe912d4447b03438739b07ca6567409542764ace21ba5996be42c4a7287d.jpg)

![ffcb961a5babc71c22ba60dfa5c83e22932362f8779de85dcf56af60596bfd06.jpg](../nips_results/626_LABridge_%20Text%E2%80%93Image%20Latent%20Alignment%20Framework%20via%20Mean-Conditioned%20OU%20Process/images/ffcb961a5babc71c22ba60dfa5c83e22932362f8779de85dcf56af60596bfd06.jpg)

### Tables

![2e9dd90a95d4ba95a140b15380aea72c7aca3b97dc19e34aa84e4a3bacda093f.jpg](../nips_results/626_LABridge_%20Text%E2%80%93Image%20Latent%20Alignment%20Framework%20via%20Mean-Conditioned%20OU%20Process/tables/2e9dd90a95d4ba95a140b15380aea72c7aca3b97dc19e34aa84e4a3bacda093f.jpg)

![c2283a147505b9333fcc8791b99aa47ddf228790edc5a49044f4e949a63ee208.jpg](../nips_results/626_LABridge_%20Text%E2%80%93Image%20Latent%20Alignment%20Framework%20via%20Mean-Conditioned%20OU%20Process/tables/c2283a147505b9333fcc8791b99aa47ddf228790edc5a49044f4e949a63ee208.jpg)

![f3f06d6216051fee38f6aadcd20beb000d0dbec92ca9b2f75880c6396c908eb3.jpg](../nips_results/626_LABridge_%20Text%E2%80%93Image%20Latent%20Alignment%20Framework%20via%20Mean-Conditioned%20OU%20Process/tables/f3f06d6216051fee38f6aadcd20beb000d0dbec92ca9b2f75880c6396c908eb3.jpg)

## Emergence and Evolution of Interpretable Concepts in Diffusion Models


### Images

![06b69cbfd59cec0d321fe1a86db427ceb3d78e75e5cb20e81a02e981c2bc47a1.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/06b69cbfd59cec0d321fe1a86db427ceb3d78e75e5cb20e81a02e981c2bc47a1.jpg)

![0706a894e96fe308a35730d5f9bf71ef3a9bc3c6b1ab6bccfcc62ab255ef7ed8.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/0706a894e96fe308a35730d5f9bf71ef3a9bc3c6b1ab6bccfcc62ab255ef7ed8.jpg)

![1b2b087c71c9dcb7ca895b93cbb76f77f72283cba5af2ffcf1b5ad392515e88d.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/1b2b087c71c9dcb7ca895b93cbb76f77f72283cba5af2ffcf1b5ad392515e88d.jpg)

![1d2821a1c8040990868b5bdfa61c69b525785dc791bea85f6d3ad255cc477572.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/1d2821a1c8040990868b5bdfa61c69b525785dc791bea85f6d3ad255cc477572.jpg)

![2ca4407e3915f34f95f99572ff1346d3f7d29153b3d311627b977370a9c0e25e.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/2ca4407e3915f34f95f99572ff1346d3f7d29153b3d311627b977370a9c0e25e.jpg)

![3bb3842ab466bd9c79994105a3d0978456a1ed5a6fe36d88e151b6840f0f5aec.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/3bb3842ab466bd9c79994105a3d0978456a1ed5a6fe36d88e151b6840f0f5aec.jpg)

![40049a1ba82528b73ef2794f787bbc1f347e94bf3ef2bfc43893c3fe56641063.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/40049a1ba82528b73ef2794f787bbc1f347e94bf3ef2bfc43893c3fe56641063.jpg)

![473dd1658ab800ddd85ca816b85a1c2d1a41ca10b04df084229d5a415d6d4cc0.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/473dd1658ab800ddd85ca816b85a1c2d1a41ca10b04df084229d5a415d6d4cc0.jpg)

![4d2759fd8020db49aabe94cafcc9b188f716accea8cddd9cd4d75586af4992ef.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/4d2759fd8020db49aabe94cafcc9b188f716accea8cddd9cd4d75586af4992ef.jpg)

![4dfe163cda7f091c6ae6c1816de08a35327f376495e03a04aad7646656648025.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/4dfe163cda7f091c6ae6c1816de08a35327f376495e03a04aad7646656648025.jpg)

![573712c9e99c599f26aa411635906e91dbb3832480390e305d18aecafc683947.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/573712c9e99c599f26aa411635906e91dbb3832480390e305d18aecafc683947.jpg)

![59f44393e9ce365741e882b981cf5d7dce20f843fbae361b4adfcea87b3fdc73.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/59f44393e9ce365741e882b981cf5d7dce20f843fbae361b4adfcea87b3fdc73.jpg)

![5d9be0bd2fd8611757dc99a388fe666ec8447edcfd5f95e8a8213d8d5e895a1b.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/5d9be0bd2fd8611757dc99a388fe666ec8447edcfd5f95e8a8213d8d5e895a1b.jpg)

![5f73670aa8616cf43498017ecc15b94d4ff6dada0566838089a35500134e207b.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/5f73670aa8616cf43498017ecc15b94d4ff6dada0566838089a35500134e207b.jpg)

![658ffad0580e814142d4330c903f308f223535bb8c8124b82d3a2e123254884a.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/658ffad0580e814142d4330c903f308f223535bb8c8124b82d3a2e123254884a.jpg)

![6dcc58d756cc455ca41a39e67e8a0477251d9b6d02d3cc66938380bd150d8e23.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/6dcc58d756cc455ca41a39e67e8a0477251d9b6d02d3cc66938380bd150d8e23.jpg)

![6fb5c31762d9f96e2c5ef85bec3e6f08669d7f7d588c2d626ecee1c8c6d6ab13.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/6fb5c31762d9f96e2c5ef85bec3e6f08669d7f7d588c2d626ecee1c8c6d6ab13.jpg)

![7629609476becee72967d840e6bed5afe6fa92dfc8d9d9fa7d4d75b9cb1b370a.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/7629609476becee72967d840e6bed5afe6fa92dfc8d9d9fa7d4d75b9cb1b370a.jpg)

![816eee7a7a86318ae000fc5699f71864070f53c686b75cecd872090dac96a150.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/816eee7a7a86318ae000fc5699f71864070f53c686b75cecd872090dac96a150.jpg)

![8648d4336b21614717d67f714ef2a6ee9c7cb5c696e766ab7fb90a89eb92ebf9.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/8648d4336b21614717d67f714ef2a6ee9c7cb5c696e766ab7fb90a89eb92ebf9.jpg)

![97c17b35d109419cc75ea41e1d07b55d37e600b2a2950fef71c63610d77e9141.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/97c17b35d109419cc75ea41e1d07b55d37e600b2a2950fef71c63610d77e9141.jpg)

![98400f93a4c47d73ba22ceb43ce882ec5e7a185d2cc5499f5887f9e1406ffb7a.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/98400f93a4c47d73ba22ceb43ce882ec5e7a185d2cc5499f5887f9e1406ffb7a.jpg)

![9b1881fb6282088a43f302be37953b66644cfe6979d37aad58290d316638cd10.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/9b1881fb6282088a43f302be37953b66644cfe6979d37aad58290d316638cd10.jpg)

![9c3ed4776ffc009651e6af1906219c7824cabd50378543e26bea2f3988dc41b3.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/9c3ed4776ffc009651e6af1906219c7824cabd50378543e26bea2f3988dc41b3.jpg)

![9f580288dbe71514a293d8abcd645042f879a58262394612967ce37d5fa46e67.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/9f580288dbe71514a293d8abcd645042f879a58262394612967ce37d5fa46e67.jpg)

![a968a92c64daccc2dab5a1143a67bba5b5070b680f7035774d5117674c267797.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/a968a92c64daccc2dab5a1143a67bba5b5070b680f7035774d5117674c267797.jpg)

![b6f2603465567701a577da1898143d67984be9a7dd8f08f28279134c0fb31657.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/b6f2603465567701a577da1898143d67984be9a7dd8f08f28279134c0fb31657.jpg)

![ba865b9ded164c4c1ed816073498c3c2f934922946a48bf75a6d9cef34819d42.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/ba865b9ded164c4c1ed816073498c3c2f934922946a48bf75a6d9cef34819d42.jpg)

![bbe293b8e52cc808f7abde87ff16cd8de5f63463c91704df105b631fb3c4bce9.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/bbe293b8e52cc808f7abde87ff16cd8de5f63463c91704df105b631fb3c4bce9.jpg)

![c0b630a1421ea4d69db47908683bb7fe40bf8faeca209a6a37b52a0b4753331b.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/c0b630a1421ea4d69db47908683bb7fe40bf8faeca209a6a37b52a0b4753331b.jpg)

![c32f72a0371e403b8dc1ac2c7b400dbede1d42dbc57734ce1621c09811c3db51.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/c32f72a0371e403b8dc1ac2c7b400dbede1d42dbc57734ce1621c09811c3db51.jpg)

![c3cfc9b12db39daea835246a93330655ad92e18eb9b9996c4a7229d4b66ab824.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/c3cfc9b12db39daea835246a93330655ad92e18eb9b9996c4a7229d4b66ab824.jpg)

![cf6c113d8d8a63f667714cbe14ef6911e03a0f1273ded597126c0126cb9568d1.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/cf6c113d8d8a63f667714cbe14ef6911e03a0f1273ded597126c0126cb9568d1.jpg)

![d998650676bcee3c743c278969c98332920af1ce6570bf0a028688661e1f70a0.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/d998650676bcee3c743c278969c98332920af1ce6570bf0a028688661e1f70a0.jpg)

![da98138db71d4d6ba082aee2463baea18cba157ed6c14011ba9d510504cadc6e.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/da98138db71d4d6ba082aee2463baea18cba157ed6c14011ba9d510504cadc6e.jpg)

![ec437aeee93ea4066ddcb969949f07fe73ede6bbabe445fc62e4b4a9095b6ee0.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/ec437aeee93ea4066ddcb969949f07fe73ede6bbabe445fc62e4b4a9095b6ee0.jpg)

![fd26d6f84e2ce8894f4348e5211a73293559e9ace21b5e34a2cd255ba3604a5f.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/images/fd26d6f84e2ce8894f4348e5211a73293559e9ace21b5e34a2cd255ba3604a5f.jpg)

### Tables

![2a2f3a1b86a2d25601c08e78789d3beba75539cd70000a2b357ea629c953ff67.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/tables/2a2f3a1b86a2d25601c08e78789d3beba75539cd70000a2b357ea629c953ff67.jpg)

![9383bdf4fa0814adda4de4112d9a66916a72ff6f1869355217c8c09d30674bab.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/tables/9383bdf4fa0814adda4de4112d9a66916a72ff6f1869355217c8c09d30674bab.jpg)

![d24fa7bb6731a802d7b4576ab235d9015564f9efd10ed1451a2f305d86159d32.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/tables/d24fa7bb6731a802d7b4576ab235d9015564f9efd10ed1451a2f305d86159d32.jpg)

![d82b572bafbd48deffc3ee78a113c8f35ff075f37d5a8da02b652d1e52c8865d.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/tables/d82b572bafbd48deffc3ee78a113c8f35ff075f37d5a8da02b652d1e52c8865d.jpg)

![e07bc4dab40b3c36b1de8a260fccfdf9e982bb2be43b9b18e8e76e86dad2c2b4.jpg](../nips_results/627_Emergence%20and%20Evolution%20of%20Interpretable%20Concepts%20in%20Diffusion%20Models/tables/e07bc4dab40b3c36b1de8a260fccfdf9e982bb2be43b9b18e8e76e86dad2c2b4.jpg)

## Dual Data Alignment Makes AI-Generated Image Detector Easier Generalizable


### Images

![0a2e083045f0e601cd1f5a0bd9cbff457edc8323fac16f77ac96c91e78cce97f.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/0a2e083045f0e601cd1f5a0bd9cbff457edc8323fac16f77ac96c91e78cce97f.jpg)

![111bb51240a0145dfd9de84ea47bbcc424fa850bc1133a319666082d35a1c1b2.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/111bb51240a0145dfd9de84ea47bbcc424fa850bc1133a319666082d35a1c1b2.jpg)

![1c3f38ee72b47baa6f36b3a85b7986cc301e1c7576c5d592845b1a5e92b16c06.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/1c3f38ee72b47baa6f36b3a85b7986cc301e1c7576c5d592845b1a5e92b16c06.jpg)

![250de64d3a781dcae2a4277785676337e7ba99f303120d1ad3d2f28c56df48f5.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/250de64d3a781dcae2a4277785676337e7ba99f303120d1ad3d2f28c56df48f5.jpg)

![25432c427b6a66f7448697ba4eeb91e88213df8238a2b6773c8a7ffcf6b2d35f.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/25432c427b6a66f7448697ba4eeb91e88213df8238a2b6773c8a7ffcf6b2d35f.jpg)

![2db70d3a7c1e216643f6a2cff45b6a434a47d8af19425312fbe8a680d53ec57b.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/2db70d3a7c1e216643f6a2cff45b6a434a47d8af19425312fbe8a680d53ec57b.jpg)

![4d55207536dd4c61182323fd98aa91aadbaf146a9318d18aae1168fa0882d016.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/4d55207536dd4c61182323fd98aa91aadbaf146a9318d18aae1168fa0882d016.jpg)

![7092e6ce9fd7810307dd36bb4074f65139a3b3f474eb9457eb189c8c95b6e25a.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/7092e6ce9fd7810307dd36bb4074f65139a3b3f474eb9457eb189c8c95b6e25a.jpg)

![872acfb6c0befdc94840d480a5a2ca37c14e2df71cfbb6c35da6798054cc87dc.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/872acfb6c0befdc94840d480a5a2ca37c14e2df71cfbb6c35da6798054cc87dc.jpg)

![a064b1508f7bb3a682868debd2cc796a17512e11d5f5b978384ff4d32e514659.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/a064b1508f7bb3a682868debd2cc796a17512e11d5f5b978384ff4d32e514659.jpg)

![be59ae7c191a31f9c2e3f34836e5fb44920c9a84a0571a292036a74d63573fa9.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/be59ae7c191a31f9c2e3f34836e5fb44920c9a84a0571a292036a74d63573fa9.jpg)

![d7fee0500bc4f9189f29cbdee60e35504ac1c5eaf15b557942d0d1b85f4afffd.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/d7fee0500bc4f9189f29cbdee60e35504ac1c5eaf15b557942d0d1b85f4afffd.jpg)

![da41bfe6226598c29ed5bd1ce84d4bf81b612449c1f9a0c2bd43e50f4b4e47c6.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/images/da41bfe6226598c29ed5bd1ce84d4bf81b612449c1f9a0c2bd43e50f4b4e47c6.jpg)

### Tables

![0c70360e59fe07fc2e150aaa8d553e3287ebdaaadfb9da24e6c94f90fb8a1528.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/0c70360e59fe07fc2e150aaa8d553e3287ebdaaadfb9da24e6c94f90fb8a1528.jpg)

![12be93fcbffcfcb60835e3e597810bb6626acf7d81415675e9c40b1cfc6c09f6.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/12be93fcbffcfcb60835e3e597810bb6626acf7d81415675e9c40b1cfc6c09f6.jpg)

![1d566582c711de40c7d64c3950b8bd48b38f17c6cf0ddc041c09f9dc7a3c0ddf.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/1d566582c711de40c7d64c3950b8bd48b38f17c6cf0ddc041c09f9dc7a3c0ddf.jpg)

![21457034a3c0ef2aee4f9b61b25c0fe078176e57e9cdf099a04cbce89c12c651.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/21457034a3c0ef2aee4f9b61b25c0fe078176e57e9cdf099a04cbce89c12c651.jpg)

![4b7ba872952d638a67cfb2f33df716ed68361c5a31cbe38d7e9572762d84e064.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/4b7ba872952d638a67cfb2f33df716ed68361c5a31cbe38d7e9572762d84e064.jpg)

![5067a7a08fb5d1848c714d58cbb0dd4a57a7f0c81fff23ba3eea0225a2fa394f.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/5067a7a08fb5d1848c714d58cbb0dd4a57a7f0c81fff23ba3eea0225a2fa394f.jpg)

![78b51252862a369db57b457d1efa913da8fc97dd073c5640e71b51d92b46d7b3.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/78b51252862a369db57b457d1efa913da8fc97dd073c5640e71b51d92b46d7b3.jpg)

![8548132167302c3d93b1f0015de6a17b6213561b450f10157d1c75a2d200ac1d.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/8548132167302c3d93b1f0015de6a17b6213561b450f10157d1c75a2d200ac1d.jpg)

![d4a02f8c9b2db60a41c6700e8ea458ce1ffe136111e5bf1c71b8c22b930f2098.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/d4a02f8c9b2db60a41c6700e8ea458ce1ffe136111e5bf1c71b8c22b930f2098.jpg)

![e019a6032a395618e866c0c394edee89c3913695a7583497d59437d4b3bcf641.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/e019a6032a395618e866c0c394edee89c3913695a7583497d59437d4b3bcf641.jpg)

![e6e34b73a8de116a7d53b8ad1a7132df7c6339661032b7c9a665c5260b7ebcf3.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/e6e34b73a8de116a7d53b8ad1a7132df7c6339661032b7c9a665c5260b7ebcf3.jpg)

![e8958e7b5d71e77f8f72aa4958a665c3fca104f67450a132cfc27d527bcf55da.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/e8958e7b5d71e77f8f72aa4958a665c3fca104f67450a132cfc27d527bcf55da.jpg)

![eca4572759e293834143d80431b03843facba3ca763a22d571c010a781442658.jpg](../nips_results/628_Dual%20Data%20Alignment%20Makes%20AI-Generated%20Image%20Detector%20Easier%20Generalizable/tables/eca4572759e293834143d80431b03843facba3ca763a22d571c010a781442658.jpg)

## An Analysis of Causal Effect Estimation using Outcome Invariant Data Augmentation


### Images

![1854261277da001b4080d5462d4ba8092b97e1728d8a928ba20438e8750aaae9.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/images/1854261277da001b4080d5462d4ba8092b97e1728d8a928ba20438e8750aaae9.jpg)

![2312e39a61951ba44f6f0ca4fedfe43a9a923c86f046173629d8c281eb46aa07.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/images/2312e39a61951ba44f6f0ca4fedfe43a9a923c86f046173629d8c281eb46aa07.jpg)

![35cf892699574cd9ab7135fa41889f908f49272233f5419734b0d6b0c994cbf2.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/images/35cf892699574cd9ab7135fa41889f908f49272233f5419734b0d6b0c994cbf2.jpg)

![4535a7dbb4cf1b6e14e986259153a9277da4b28616373efab7a871be53245a0b.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/images/4535a7dbb4cf1b6e14e986259153a9277da4b28616373efab7a871be53245a0b.jpg)

![954439d77d60dfaebddb1b436e45d0c52c4e9f062f3adf46eaebc0999e4057e7.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/images/954439d77d60dfaebddb1b436e45d0c52c4e9f062f3adf46eaebc0999e4057e7.jpg)

![ba94242554fc60e93e7d681a9f091c0d1373655041e4a05716b04738a2f72115.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/images/ba94242554fc60e93e7d681a9f091c0d1373655041e4a05716b04738a2f72115.jpg)

![c961801fac8db92cb61dec132bdd7bf595620779b7691c3cce0f13df04ec98b4.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/images/c961801fac8db92cb61dec132bdd7bf595620779b7691c3cce0f13df04ec98b4.jpg)

![ceafeec15f0329e35c464cb0cdd1557fb081d46d854595f20ea08fa786adbf6c.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/images/ceafeec15f0329e35c464cb0cdd1557fb081d46d854595f20ea08fa786adbf6c.jpg)

![de4fa969986c1a6bdf203893076e076a5f59284a8c12064eb978a559902534d6.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/images/de4fa969986c1a6bdf203893076e076a5f59284a8c12064eb978a559902534d6.jpg)

![e62b75e20f5dcab485816c4bb2da76465db739639a96933d906227f139012bd7.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/images/e62b75e20f5dcab485816c4bb2da76465db739639a96933d906227f139012bd7.jpg)

### Tables

![4032b358c7f337579224a8b5f5cab343ec43c80b46c861fe281c1b0185be61ba.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/tables/4032b358c7f337579224a8b5f5cab343ec43c80b46c861fe281c1b0185be61ba.jpg)

![510649926c0ca07222f67863220653337cb2873eff42f81c91c84a49b47a38b9.jpg](../nips_results/629_An%20Analysis%20of%20Causal%20Effect%20Estimation%20using%20Outcome%20Invariant%20Data%20Augmentation/tables/510649926c0ca07222f67863220653337cb2873eff42f81c91c84a49b47a38b9.jpg)

## DMWM: Dual-Mind World Model with Long-Term Imagination


### Images

![24794e0c6d843a58abb859539fbcd539d92d18da04ec910a86afc7b08594cee4.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/24794e0c6d843a58abb859539fbcd539d92d18da04ec910a86afc7b08594cee4.jpg)

![28843fc29fce1f4344c0a9c67d4032dabe8aa548ba1082f7af645240c3811b39.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/28843fc29fce1f4344c0a9c67d4032dabe8aa548ba1082f7af645240c3811b39.jpg)

![2d18666f71f409a88f0e440dda0679349dfb71197f4a2a4b6658a87fdabac071.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/2d18666f71f409a88f0e440dda0679349dfb71197f4a2a4b6658a87fdabac071.jpg)

![3219ae99a31d90b5373307ed0d8d04c8ca2115632e77a85857cf2d4f8a89bdfa.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/3219ae99a31d90b5373307ed0d8d04c8ca2115632e77a85857cf2d4f8a89bdfa.jpg)

![3c13e1db568265ccce54749fdd4b0df0be10e506b23ea48bdd02d69e662abcbe.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/3c13e1db568265ccce54749fdd4b0df0be10e506b23ea48bdd02d69e662abcbe.jpg)

![421db197a5317011a0455a909d6efd8852edc5c0d3279753d7fa0a3a9e0bc2f7.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/421db197a5317011a0455a909d6efd8852edc5c0d3279753d7fa0a3a9e0bc2f7.jpg)

![671467cc3e36b0ab5a9739e7cba2f59ac4ec3bf8f942387e81db7c7657857d0f.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/671467cc3e36b0ab5a9739e7cba2f59ac4ec3bf8f942387e81db7c7657857d0f.jpg)

![6bdb9bc5cdfb8f7cab8af01d732386008d92ceb475b8939995d53883bde5aeee.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/6bdb9bc5cdfb8f7cab8af01d732386008d92ceb475b8939995d53883bde5aeee.jpg)

![7be7d7b0562ee9b28f9846ac4e3254a397f1f4a55f9fd0ea6254e8b9425103f1.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/7be7d7b0562ee9b28f9846ac4e3254a397f1f4a55f9fd0ea6254e8b9425103f1.jpg)

![8bbbed1e97694501d02d71e1fd590e96c0a0283c8b6ded6cd169f0093ec68749.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/8bbbed1e97694501d02d71e1fd590e96c0a0283c8b6ded6cd169f0093ec68749.jpg)

![9da7e558cb5a62ff8cd76a77489fef3314d6207e65234d40ef6784dbd57dfd67.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/9da7e558cb5a62ff8cd76a77489fef3314d6207e65234d40ef6784dbd57dfd67.jpg)

![ac4b433039beebd328399b68170fc427ade7dbecd51ce68dad14f47a67119304.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/ac4b433039beebd328399b68170fc427ade7dbecd51ce68dad14f47a67119304.jpg)

![e6e449a268079931fbca9ca9594e044e0e77804c0d8fcb6edf6ee28957870b7f.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/images/e6e449a268079931fbca9ca9594e044e0e77804c0d8fcb6edf6ee28957870b7f.jpg)

### Tables

![1497c85047f4734b18d7f4000c2790f24b26dc4da807166e078d2628df8677ac.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/tables/1497c85047f4734b18d7f4000c2790f24b26dc4da807166e078d2628df8677ac.jpg)

![397e59abccb90dd78a40ab3880fe72828534e08cc5be890168ea059d37045c21.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/tables/397e59abccb90dd78a40ab3880fe72828534e08cc5be890168ea059d37045c21.jpg)

![3cdacc507ad26dbdf5ab79c964a8a6bd7938fbbcaa3e300c6a992a3dbb799d26.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/tables/3cdacc507ad26dbdf5ab79c964a8a6bd7938fbbcaa3e300c6a992a3dbb799d26.jpg)

![4d615bdeafbb0e1eb6204eeb21ff27b66af5d01af7f0a03324a4b462959acce3.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/tables/4d615bdeafbb0e1eb6204eeb21ff27b66af5d01af7f0a03324a4b462959acce3.jpg)

![a5eed20b0dd93931f01a864a8553eaf64228219c2d4219357b675f707c2427ce.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/tables/a5eed20b0dd93931f01a864a8553eaf64228219c2d4219357b675f707c2427ce.jpg)

![bacaee73d71c4f338a0ac53024e99acd6cc3bfee0df4d5c5d9afab3044f9ac20.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/tables/bacaee73d71c4f338a0ac53024e99acd6cc3bfee0df4d5c5d9afab3044f9ac20.jpg)

![c2c4d1efda18d62135378150cea52884c132a78d5a7050dfa3aea055316e45d0.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/tables/c2c4d1efda18d62135378150cea52884c132a78d5a7050dfa3aea055316e45d0.jpg)

![c7c72743264f59a216aa728190a89e538fcb0ceb0a1ce603b5d4653fe5caa128.jpg](../nips_results/630_DMWM_%20Dual-Mind%20World%20Model%20with%20Long-Term%20Imagination/tables/c7c72743264f59a216aa728190a89e538fcb0ceb0a1ce603b5d4653fe5caa128.jpg)

## Selective Omniprediction and Fair Abstention

### Images

![234a94d2a9f816e666d54d262f0088fce8ccee296f7d3808ec6a94e0bbc60fa2.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/images/234a94d2a9f816e666d54d262f0088fce8ccee296f7d3808ec6a94e0bbc60fa2.jpg)

![3fda1f04f078d92f63f74822650ec350642c728063a5dd42249c88b898005559.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/images/3fda1f04f078d92f63f74822650ec350642c728063a5dd42249c88b898005559.jpg)

![61f451bf2469d2f3fec4dc2a7110922ced9415bd682c511b4aa7ad6a6c95ae54.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/images/61f451bf2469d2f3fec4dc2a7110922ced9415bd682c511b4aa7ad6a6c95ae54.jpg)

![eda4e0f1b9d6974e9927f27432c5ce194087f7184e56487d27c4d27558a9a02e.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/images/eda4e0f1b9d6974e9927f27432c5ce194087f7184e56487d27c4d27558a9a02e.jpg)

### Tables

![0c24ccae07e5771e35cdaca0629f5bbfd02d6ff4f664d27ed7b6d7eb53213194.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/0c24ccae07e5771e35cdaca0629f5bbfd02d6ff4f664d27ed7b6d7eb53213194.jpg)

![166454ef8b1c50754739511538991e59052f4418bdec5ece0806eb0dfe1afa68.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/166454ef8b1c50754739511538991e59052f4418bdec5ece0806eb0dfe1afa68.jpg)

![169075379093e168bb1849bc1a94bb8c807818b605ae684a0368955b57472ca7.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/169075379093e168bb1849bc1a94bb8c807818b605ae684a0368955b57472ca7.jpg)

![19c077fe5943092ee172e37fab64d03d2c874089e8b718bfef351e65989ef919.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/19c077fe5943092ee172e37fab64d03d2c874089e8b718bfef351e65989ef919.jpg)

![3a64ec539820f3d80f7f3f84c5f2e5cae0f31351918786a3d1ead1c74d8fd54b.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/3a64ec539820f3d80f7f3f84c5f2e5cae0f31351918786a3d1ead1c74d8fd54b.jpg)

![3c0bb979639c4a6e14cf17ae973fcffdb0bc27e8fd1d20dcf92e99b97a0ad5ca.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/3c0bb979639c4a6e14cf17ae973fcffdb0bc27e8fd1d20dcf92e99b97a0ad5ca.jpg)

![51fb910c952abb5f917dd00958a5b97bcd2321ff94e7fccb2cc604fcd8a6e928.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/51fb910c952abb5f917dd00958a5b97bcd2321ff94e7fccb2cc604fcd8a6e928.jpg)

![70e997666ec93b7e3d9ca37b78eab94d274b472fada53ffea9880bf2e9b94b89.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/70e997666ec93b7e3d9ca37b78eab94d274b472fada53ffea9880bf2e9b94b89.jpg)

![718383e6adcd12f7e37925c862bc3f551d5c90871f858d8e2530b82ff23ad28b.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/718383e6adcd12f7e37925c862bc3f551d5c90871f858d8e2530b82ff23ad28b.jpg)

![7fe1471fb25e073d7221d4304ecf550231c14dd078e9e4cf856e166e063202b4.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/7fe1471fb25e073d7221d4304ecf550231c14dd078e9e4cf856e166e063202b4.jpg)

![85c1c730cb99c0d15a516f044634ebf2fdcb63053dd3e9a2eb923a5bdaf9b1c6.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/85c1c730cb99c0d15a516f044634ebf2fdcb63053dd3e9a2eb923a5bdaf9b1c6.jpg)

![95bd348edcceb1e039cae920b3cc99174b3a0550be976784c37c0c3487d4d687.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/95bd348edcceb1e039cae920b3cc99174b3a0550be976784c37c0c3487d4d687.jpg)

![994f2ade11e81dd7e72e0caaac2e81c294f589e65fd2613ae0a901e9051f1169.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/994f2ade11e81dd7e72e0caaac2e81c294f589e65fd2613ae0a901e9051f1169.jpg)

![a07d0c73d5f493f63f53c700d1f66d5078db59c3bbddfb632c9bb70ae42f021f.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/a07d0c73d5f493f63f53c700d1f66d5078db59c3bbddfb632c9bb70ae42f021f.jpg)

![a92eb9a11a41a5522f2e0a22048f3a8626bde9bc64f72d29d63a887f78d65845.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/a92eb9a11a41a5522f2e0a22048f3a8626bde9bc64f72d29d63a887f78d65845.jpg)

![a9ad0463aac6442cf387441fa9c898049ccfdc42322839cec966cd9d0c629f13.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/a9ad0463aac6442cf387441fa9c898049ccfdc42322839cec966cd9d0c629f13.jpg)

![a9d3bca448402ccc083d6d65d7f247820c6fc5e899515e8f60982ce2e4d82ba6.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/a9d3bca448402ccc083d6d65d7f247820c6fc5e899515e8f60982ce2e4d82ba6.jpg)

![b315a95a0daff867e11b3197d40bad6862be4cfc6047906a845acf493acace15.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/b315a95a0daff867e11b3197d40bad6862be4cfc6047906a845acf493acace15.jpg)

![c23753a31159f07222b65665c7b18a28d51781c74c28bbe72f11125fe9ced364.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/c23753a31159f07222b65665c7b18a28d51781c74c28bbe72f11125fe9ced364.jpg)

![c30e7912b8ded9fa5eb8a16adfbb0371c3a7433a3a790b75556f031424b0821c.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/c30e7912b8ded9fa5eb8a16adfbb0371c3a7433a3a790b75556f031424b0821c.jpg)

![c3894b1bec5d1a17f63451bae6227511750f48ce18bc2bce3148dd07eff42007.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/c3894b1bec5d1a17f63451bae6227511750f48ce18bc2bce3148dd07eff42007.jpg)

![cae1ee6c9eacebdff6422439312a0712d435d531c4425a93bac8750073ca261d.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/cae1ee6c9eacebdff6422439312a0712d435d531c4425a93bac8750073ca261d.jpg)

![e28f7de496a9f8ce324fd78a4dcfe44c5f85265241bc9a108e6c0401eb292df7.jpg](../nips_results/631_Selective%20Omniprediction%20and%20Fair%20Abstention/tables/e28f7de496a9f8ce324fd78a4dcfe44c5f85265241bc9a108e6c0401eb292df7.jpg)
