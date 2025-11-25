# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 21 of 130

## 目录 (Table of Contents)

1. [Sim-LLM: Optimizing LLM Inference at the Edge through Inter-Task KV Reuse](#Sim-LLM-Optimizing-LLM-Inference-at-the-Edge-through-Inter-Task-KV-Reuse)
2. [Bifrost-1: Bridging Multimodal LLMs and Diffusion Models with Patch-level CLIP Latents](#Bifrost-1-Bridging-Multimodal-LLMs-and-Diffusion-Models-with-Patch-level-CLIP-Latents)
3. [VETA-DiT: Variance-Equalized and Temporally Adaptive Quantization for Efficient 4-bit Diffusion Transformers](#VETA-DiT-Variance-Equalized-and-Temporally-Adaptive-Quantization-for-Efficient-4-bit-Diffusion-Transformers)
4. [Optimistic Query Routing in Clustering-based Approximate Maximum Inner Product Search](#Optimistic-Query-Routing-in-Clustering-based-Approximate-Maximum-Inner-Product-Search)
5. [Variational Task Vector Composition](#Variational-Task-Vector-Composition)
6. [Semantic Representation Attack against Aligned Large Language Models](#Semantic-Representation-Attack-against-Aligned-Large-Language-Models)
7. [Visual Instruction Bottleneck Tuning](#Visual-Instruction-Bottleneck-Tuning)
8. [Reinforcing Spatial Reasoning in Vision-Language Models with Interwoven Thinking and Visual Drawing](#Reinforcing-Spatial-Reasoning-in-Vision-Language-Models-with-Interwoven-Thinking-and-Visual-Drawing)
9. [Dendritic Resonate-and-Fire Neuron for Effective and Efficient Long Sequence Modeling](#Dendritic-Resonate-and-Fire-Neuron-for-Effective-and-Efficient-Long-Sequence-Modeling)
10. [Logical Expressiveness of Graph Neural Networks with Hierarchical Node Individualization](#Logical-Expressiveness-of-Graph-Neural-Networks-with-Hierarchical-Node-Individualization)
11. [Precise Information Control in Long-Form Text Generation](#Precise-Information-Control-in-Long-Form-Text-Generation)
12. [A Minimalist Example of Edge-of-Stability and Progressive Sharpening](#A-Minimalist-Example-of-Edge-of-Stability-and-Progressive-Sharpening)
13. [Sparc3D: Sparse Representation and Construction for High-Resolution 3D Shapes Modeling](#Sparc3D-Sparse-Representation-and-Construction-for-High-Resolution-3D-Shapes-Modeling)
14. [Transformers Learn Faster with Semantic Focus](#Transformers-Learn-Faster-with-Semantic-Focus)
15. [Model Inversion with Layer-Specific Modeling and Alignment for Data-Free Continual Learning](#Model-Inversion-with-Layer-Specific-Modeling-and-Alignment-for-Data-Free-Continual-Learning)
16. [Vulnerable Data-Aware Adversarial Training](#Vulnerable-Data-Aware-Adversarial-Training)
17. [Personalized Subgraph Federated Learning with Differentiable Auxiliary Projections](#Personalized-Subgraph-Federated-Learning-with-Differentiable-Auxiliary-Projections)
18. [KTAE: A Model-Free Algorithm to Key-Tokens Advantage Estimation in Mathematical Reasoning](#KTAE-A-Model-Free-Algorithm-to-Key-Tokens-Advantage-Estimation-in-Mathematical-Reasoning)
19. [MotionRAG: Motion Retrieval-Augmented Image-to-Video Generation](#MotionRAG-Motion-Retrieval-Augmented-Image-to-Video-Generation)
20. [Hierarchical Semantic-Augmented Navigation: Optimal Transport and Graph-Driven Reasoning for Vision-Language Navigation](#Hierarchical-Semantic-Augmented-Navigation-Optimal-Transport-and-Graph-Driven-Reasoning-for-Vision-Language-Navigation)
21. [DCA: Graph-Guided Deep Embedding Clustering for Brain Atlases](#DCA-Graph-Guided-Deep-Embedding-Clustering-for-Brain-Atlases)
22. [Learning Human-Object Interaction as Groups](#Learning-Human-Object-Interaction-as-Groups)
23. [Spectral Analysis of Diffusion Models with Application to Schedule Design](#Spectral-Analysis-of-Diffusion-Models-with-Application-to-Schedule-Design)
24. [Interpretable and Parameter Efficient Graph Neural Additive Models with Random Fourier Features](#Interpretable-and-Parameter-Efficient-Graph-Neural-Additive-Models-with-Random-Fourier-Features)
25. [Predictive Coding Enhances Meta-RL To Achieve Interpretable Bayes-Optimal Belief Representation Under Partial Observability](#Predictive-Coding-Enhances-Meta-RL-To-Achieve-Interpretable-Bayes-Optimal-Belief-Representation-Under-Partial-Observability)
26. [Point3R: Streaming 3D Reconstruction with Explicit Spatial Pointer Memory](#Point3R-Streaming-3D-Reconstruction-with-Explicit-Spatial-Pointer-Memory)
27. [CLAWS:Creativity detection for LLM-generated solutions using Attention Window of Sections](#CLAWSCreativity-detection-for-LLM-generated-solutions-using-Attention-Window-of-Sections)
28. [Bridging Equivariant GNNs and Spherical CNNs for Structured Physical Domains](#Bridging-Equivariant-GNNs-and-Spherical-CNNs-for-Structured-Physical-Domains)
29. [Prior-Guided Flow Matching for Target-Aware Molecule Design with Learnable Atom Number](#Prior-Guided-Flow-Matching-for-Target-Aware-Molecule-Design-with-Learnable-Atom-Number)
30. [IGD: Token Decisiveness Modeling via Information Gain in LLMs for Personalized Recommendation](#IGD-Token-Decisiveness-Modeling-via-Information-Gain-in-LLMs-for-Personalized-Recommendation)
31. [CMoB: Modality Valuation via Causal Effect for Balanced Multimodal Learning](#CMoB-Modality-Valuation-via-Causal-Effect-for-Balanced-Multimodal-Learning)
32. [JailBound: Jailbreaking Internal Safety Boundaries of Vision-Language Models](#JailBound-Jailbreaking-Internal-Safety-Boundaries-of-Vision-Language-Models)
33. [Confusion-Driven Self-Supervised Progressively Weighted Ensemble Learning for Non-Exemplar Class Incremental Learning](#Confusion-Driven-Self-Supervised-Progressively-Weighted-Ensemble-Learning-for-Non-Exemplar-Class-Incremental-Learning)
34. [Beyond the 80/20 Rule: High-Entropy Minority Tokens Drive Effective Reinforcement Learning for LLM Reasoning](#Beyond-the-8020-Rule-High-Entropy-Minority-Tokens-Drive-Effective-Reinforcement-Learning-for-LLM-Reasoning)
35. [Enforcing convex constraints in Graph Neural Networks](#Enforcing-convex-constraints-in-Graph-Neural-Networks)
36. [Segment then Splat: Unified 3D Open-Vocabulary Segmentation via Gaussian Splatting](#Segment-then-Splat-Unified-3D-Open-Vocabulary-Segmentation-via-Gaussian-Splatting)
37. [MetaDefense: Defending Fine-tuning based Jailbreak Attack Before and During Generation](#MetaDefense-Defending-Fine-tuning-based-Jailbreak-Attack-Before-and-During-Generation)
38. [Coresets for Clustering Under Stochastic Noise](#Coresets-for-Clustering-Under-Stochastic-Noise)
39. [Beyond Pairwise Connections: Extracting High-Order Functional Brain Network Structures under Global Constraints](#Beyond-Pairwise-Connections-Extracting-High-Order-Functional-Brain-Network-Structures-under-Global-Constraints)
40. [Temporal Representation Alignment: Successor Features Enable Emergent Compositionality in Robot Instruction Following](#Temporal-Representation-Alignment-Successor-Features-Enable-Emergent-Compositionality-in-Robot-Instruction-Following)
41. [Optimizing Retrieval for RAG via Reinforced Contrastive Learning](#Optimizing-Retrieval-for-RAG-via-Reinforced-Contrastive-Learning)

---


## Sim-LLM: Optimizing LLM Inference at the Edge through Inter-Task KV Reuse

### Images

![1a39a3a7ff04c917d2f3fabe2055c5242db8e2663cae6136bb96e07f2e825ca4.jpg](../nips_results/837_COALA_%20Numerically%20Stable%20and%20Efficient%20Framework%20for%20Context-Aware%20Low-Rank%20Approximation/images/1a39a3a7ff04c917d2f3fabe2055c5242db8e2663cae6136bb96e07f2e825ca4.jpg)

![72bb049ee84bafd77425722a07a6b0c5845999bf1337a53f1d9dcc8b1a3bfa96.jpg](../nips_results/837_COALA_%20Numerically%20Stable%20and%20Efficient%20Framework%20for%20Context-Aware%20Low-Rank%20Approximation/images/72bb049ee84bafd77425722a07a6b0c5845999bf1337a53f1d9dcc8b1a3bfa96.jpg)

![951f3ae15bbbb43bbee4d8a71bba03f45485e57e54f4aff0395b22bad3f9a945.jpg](../nips_results/837_COALA_%20Numerically%20Stable%20and%20Efficient%20Framework%20for%20Context-Aware%20Low-Rank%20Approximation/images/951f3ae15bbbb43bbee4d8a71bba03f45485e57e54f4aff0395b22bad3f9a945.jpg)

![a22ee3994ca5a39446d14edcb7fe4c8b0ffc4ab78b1404112d401785330fd8cf.jpg](../nips_results/837_COALA_%20Numerically%20Stable%20and%20Efficient%20Framework%20for%20Context-Aware%20Low-Rank%20Approximation/images/a22ee3994ca5a39446d14edcb7fe4c8b0ffc4ab78b1404112d401785330fd8cf.jpg)

![b4eabbb94e45375887a37dd1accda24b1ff0080a6c850d8c8c3459da817f9dfd.jpg](../nips_results/837_COALA_%20Numerically%20Stable%20and%20Efficient%20Framework%20for%20Context-Aware%20Low-Rank%20Approximation/images/b4eabbb94e45375887a37dd1accda24b1ff0080a6c850d8c8c3459da817f9dfd.jpg)

![e14f0918853c29a4c982793c8709bf70b9c6f08abb23dc084c2a4191a08455ee.jpg](../nips_results/837_COALA_%20Numerically%20Stable%20and%20Efficient%20Framework%20for%20Context-Aware%20Low-Rank%20Approximation/images/e14f0918853c29a4c982793c8709bf70b9c6f08abb23dc084c2a4191a08455ee.jpg)

### Tables

![a1303f337a8131f1d045ea29bf99447b6392df0849a1af985be265e5970a917a.jpg](../nips_results/837_COALA_%20Numerically%20Stable%20and%20Efficient%20Framework%20for%20Context-Aware%20Low-Rank%20Approximation/tables/a1303f337a8131f1d045ea29bf99447b6392df0849a1af985be265e5970a917a.jpg)

![ad9d71d6d2a96e2bc87c7c92df524785ce3d3b336605b191a4d3dfe65f6286ca.jpg](../nips_results/837_COALA_%20Numerically%20Stable%20and%20Efficient%20Framework%20for%20Context-Aware%20Low-Rank%20Approximation/tables/ad9d71d6d2a96e2bc87c7c92df524785ce3d3b336605b191a4d3dfe65f6286ca.jpg)

![b03eef1312da1a1c2088e13d76e4f568acd0a878094e7b9dd1c9f14c8bf1ec33.jpg](../nips_results/837_COALA_%20Numerically%20Stable%20and%20Efficient%20Framework%20for%20Context-Aware%20Low-Rank%20Approximation/tables/b03eef1312da1a1c2088e13d76e4f568acd0a878094e7b9dd1c9f14c8bf1ec33.jpg)

![bcd2891a3cca20a755cbf5ca79f37e659795b5b0c986bad4b4a6c3838822675d.jpg](../nips_results/837_COALA_%20Numerically%20Stable%20and%20Efficient%20Framework%20for%20Context-Aware%20Low-Rank%20Approximation/tables/bcd2891a3cca20a755cbf5ca79f37e659795b5b0c986bad4b4a6c3838822675d.jpg)

![dc00eac9a83b8a5f894344a6b480f7b48d7cd393a16e8799a005db44a16f44c0.jpg](../nips_results/837_COALA_%20Numerically%20Stable%20and%20Efficient%20Framework%20for%20Context-Aware%20Low-Rank%20Approximation/tables/dc00eac9a83b8a5f894344a6b480f7b48d7cd393a16e8799a005db44a16f44c0.jpg)

## Sim-LLM: Optimizing LLM Inference at the Edge through Inter-Task KV Reuse


### Images

![0f180ab72bc4dddb0fefd548dc1c4d84235c0b858d455b89655cf368bf70d3d0.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/0f180ab72bc4dddb0fefd548dc1c4d84235c0b858d455b89655cf368bf70d3d0.jpg)

![2ae25216238fbe01155b516aced690cffb65343dc75fb6b806dcd2c151cc66cd.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/2ae25216238fbe01155b516aced690cffb65343dc75fb6b806dcd2c151cc66cd.jpg)

![37baabccc30068b154999a8412a0177ab49b980ceda01aec6824cf857b49dc06.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/37baabccc30068b154999a8412a0177ab49b980ceda01aec6824cf857b49dc06.jpg)

![3fa64c0ee90b408654e937c4b5a3b5821fd6dd6a9985b0ebfdc390b4a164e32a.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/3fa64c0ee90b408654e937c4b5a3b5821fd6dd6a9985b0ebfdc390b4a164e32a.jpg)

![42500c6afeb822c09d3bc0454e07218bf272ade5f8619b05ec4d5b4bb8aa0200.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/42500c6afeb822c09d3bc0454e07218bf272ade5f8619b05ec4d5b4bb8aa0200.jpg)

![6ce0fcf505910345654594adaa4b3a9a0834e67b653da2b3b539671cb294b407.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/6ce0fcf505910345654594adaa4b3a9a0834e67b653da2b3b539671cb294b407.jpg)

![87ce05db49ab8c159f77da3e7116c5e3cf2ddcb2de58613cea9fb3b5d175a66d.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/87ce05db49ab8c159f77da3e7116c5e3cf2ddcb2de58613cea9fb3b5d175a66d.jpg)

![8e6e1f4fa78750eb9ccaf5960316be475028c0aa511286df10dfa691066848b6.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/8e6e1f4fa78750eb9ccaf5960316be475028c0aa511286df10dfa691066848b6.jpg)

![b368585ff765855ad9feba648e237f77f51fafdf9b0dabd57ca809cfafc66926.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/b368585ff765855ad9feba648e237f77f51fafdf9b0dabd57ca809cfafc66926.jpg)

![bd86f39330f195c7bb2a56b13da945f5a7fb6ba49538889b0b4e0bcf22f2e941.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/bd86f39330f195c7bb2a56b13da945f5a7fb6ba49538889b0b4e0bcf22f2e941.jpg)

![e063e55f41bc9d4e390574359e551a0a3de1fc9c879acfa01c8870cae0c9e205.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/e063e55f41bc9d4e390574359e551a0a3de1fc9c879acfa01c8870cae0c9e205.jpg)

![f1e96201c5fdfab1886ee37f1ad718f369ba16f24f1395bcf4f12a5394acfb76.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/images/f1e96201c5fdfab1886ee37f1ad718f369ba16f24f1395bcf4f12a5394acfb76.jpg)

### Tables

![070d85626f7891ad69bc6062c6a0dfa0e210f435aa1f778f196f7448af0b9c15.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/tables/070d85626f7891ad69bc6062c6a0dfa0e210f435aa1f778f196f7448af0b9c15.jpg)

![6bec5d9279cf6dfde498e76e5c23293393d6be45818e1bf15e53eb8b997b0e61.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/tables/6bec5d9279cf6dfde498e76e5c23293393d6be45818e1bf15e53eb8b997b0e61.jpg)

![9e504bd8986e1e7ae906d36469accf987bce8fe66a2b47cffdaa08cdb3d6f389.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/tables/9e504bd8986e1e7ae906d36469accf987bce8fe66a2b47cffdaa08cdb3d6f389.jpg)

![a0f36f02de4abbceeca037d8012b634357fed22edaa53ec02cc98f1fd1551428.jpg](../nips_results/838_Sim-LLM_%20Optimizing%20LLM%20Inference%20at%20the%20Edge%20through%20Inter-Task%20KV%20Reuse/tables/a0f36f02de4abbceeca037d8012b634357fed22edaa53ec02cc98f1fd1551428.jpg)

## Bifrost-1: Bridging Multimodal LLMs and Diffusion Models with Patch-level CLIP Latents


### Images

![0dc3fc7febe3fa3ab2d62f084625ba564f080c2a7ec5f4117bbe57fbf5741727.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/0dc3fc7febe3fa3ab2d62f084625ba564f080c2a7ec5f4117bbe57fbf5741727.jpg)

![1082bcd1ba0eaec834ac6a2be6487ac702c5243bfe0b8993889e75cae0030eca.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/1082bcd1ba0eaec834ac6a2be6487ac702c5243bfe0b8993889e75cae0030eca.jpg)

![35aae3c5cda79e5455ca11ad5e61bcd6496da57132d6947f49fb1e5c78f6d31d.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/35aae3c5cda79e5455ca11ad5e61bcd6496da57132d6947f49fb1e5c78f6d31d.jpg)

![3b30215dc7547866e0b4e42c487f6bde669cdef8b2aaa412178866d4ffa97926.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/3b30215dc7547866e0b4e42c487f6bde669cdef8b2aaa412178866d4ffa97926.jpg)

![46fc1e74f9059c30bcd5e37d0b4082e6f2b5c5e136addf2e34f42468f90c5bcf.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/46fc1e74f9059c30bcd5e37d0b4082e6f2b5c5e136addf2e34f42468f90c5bcf.jpg)

![4a9f2933e02ce4b955eb6ad00eac3d58c68b83db84845830eab0d7c9699c7757.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/4a9f2933e02ce4b955eb6ad00eac3d58c68b83db84845830eab0d7c9699c7757.jpg)

![4faf7c10c1e05f0af16b30538c04ec5f1cb47bc4b2ac0d149b9f733585fb6bc7.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/4faf7c10c1e05f0af16b30538c04ec5f1cb47bc4b2ac0d149b9f733585fb6bc7.jpg)

![5ebc66993e7ed43e30185320d584bd3b163f468fb09b5f32688650c303f7b2d3.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/5ebc66993e7ed43e30185320d584bd3b163f468fb09b5f32688650c303f7b2d3.jpg)

![69616cd2908531628aa9c7e4454a3ec726f5598eec0213c9d1334b557a5545f5.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/69616cd2908531628aa9c7e4454a3ec726f5598eec0213c9d1334b557a5545f5.jpg)

![832489caa4285352420a669ed9371fab766f1e6963e6734e0163b72f30d9ee89.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/832489caa4285352420a669ed9371fab766f1e6963e6734e0163b72f30d9ee89.jpg)

![8427238b87b03fdfb62d7b8a2d5436bac51513cb5de1b0cdc7aaff4f96d851be.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/8427238b87b03fdfb62d7b8a2d5436bac51513cb5de1b0cdc7aaff4f96d851be.jpg)

![86a7b51aeb5094395fb4fa8b859c073a0febae1682ac63d5a9f144522d2611d1.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/86a7b51aeb5094395fb4fa8b859c073a0febae1682ac63d5a9f144522d2611d1.jpg)

![98c347b8a1af7bdfd84fc80b583ed9552242e86e68072d1c5dd8e2c094d688d9.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/98c347b8a1af7bdfd84fc80b583ed9552242e86e68072d1c5dd8e2c094d688d9.jpg)

![b6e0330a291438ba426055b26033b3b27c9b86305e1686dcdd870e1735b892e3.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/b6e0330a291438ba426055b26033b3b27c9b86305e1686dcdd870e1735b892e3.jpg)

![b7c8b97519115b80ced9f54ac63e0c53ddb0e3cee2a2e20bd0745c3f796e487c.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/b7c8b97519115b80ced9f54ac63e0c53ddb0e3cee2a2e20bd0745c3f796e487c.jpg)

![c31f1848dbc6f4f7bb7efba1b213272f985d97d68797111fa038d7b9fdf53f2f.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/c31f1848dbc6f4f7bb7efba1b213272f985d97d68797111fa038d7b9fdf53f2f.jpg)

![cb82a04586fd6e72af108813aedd07e801bebdf6715f6c767f9a67ad964ade7d.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/cb82a04586fd6e72af108813aedd07e801bebdf6715f6c767f9a67ad964ade7d.jpg)

![cc5567d7e916cbe7d8bf8822c401de09da5835de36dfcec39d6549f87046adb1.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/cc5567d7e916cbe7d8bf8822c401de09da5835de36dfcec39d6549f87046adb1.jpg)

![d56bbce3b3b8e9801b2ac37c3f3743df5e1c73b8c8a1d856ceac6cbb9bf53f2f.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/d56bbce3b3b8e9801b2ac37c3f3743df5e1c73b8c8a1d856ceac6cbb9bf53f2f.jpg)

![e3049845b06de0bcebf56c29e614e1803ad54908da69f86a6546bff2f63c2261.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/e3049845b06de0bcebf56c29e614e1803ad54908da69f86a6546bff2f63c2261.jpg)

![e7ac0e6bf92ec28c957299329d69b3f9be0a26538fd5719279bc2cf896252340.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/e7ac0e6bf92ec28c957299329d69b3f9be0a26538fd5719279bc2cf896252340.jpg)

![ed454d4da7d29157e04e27d781b7d38c4b953ad54465bc57bbcf8660bb0274a8.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/ed454d4da7d29157e04e27d781b7d38c4b953ad54465bc57bbcf8660bb0274a8.jpg)

![f7eeff5e96eb9fb694acae95dabc150b8f98013198ec2789a56ee2b05bf52bfd.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/images/f7eeff5e96eb9fb694acae95dabc150b8f98013198ec2789a56ee2b05bf52bfd.jpg)

### Tables

![6e6dbc31c65216972e4b0e24f4fadf964b0f36610ab076d39283d5409674ec90.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/tables/6e6dbc31c65216972e4b0e24f4fadf964b0f36610ab076d39283d5409674ec90.jpg)

![753297def26e6d8f3bced6e8f1d3f13427b4747b267d9703ee80824e3dd56dde.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/tables/753297def26e6d8f3bced6e8f1d3f13427b4747b267d9703ee80824e3dd56dde.jpg)

![bbc71a2e9b7f16a7033ef0ab3f0de61a6b831e8d898e75ac31a13f1039fef875.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/tables/bbc71a2e9b7f16a7033ef0ab3f0de61a6b831e8d898e75ac31a13f1039fef875.jpg)

![ea69b10483ea55b799b1853a31b9dd72ac3428d89d7341f7d74cf0152a26041a.jpg](../nips_results/839_Bifrost-1_%20Bridging%20Multimodal%20LLMs%20and%20Diffusion%20Models%20with%20Patch-level%20CLIP%20Latents/tables/ea69b10483ea55b799b1853a31b9dd72ac3428d89d7341f7d74cf0152a26041a.jpg)

## VETA-DiT: Variance-Equalized and Temporally Adaptive Quantization for Efficient 4-bit Diffusion Transformers


### Images

![130138ac2638a414a96b0eded31991c320c5d98ebc5c9c276e82cf55cab017f0.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/130138ac2638a414a96b0eded31991c320c5d98ebc5c9c276e82cf55cab017f0.jpg)

![21212ef58d54548aef799c77b4c31ba703fd632f002b4e03f8ba6611c7026722.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/21212ef58d54548aef799c77b4c31ba703fd632f002b4e03f8ba6611c7026722.jpg)

![2365780145b2d19a1ab1862cadb768aecf9c2b785a06339f5e1e6ed699a523e4.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/2365780145b2d19a1ab1862cadb768aecf9c2b785a06339f5e1e6ed699a523e4.jpg)

![2495192f1326b07ec19fe29a833886c68b3db11229eff5af36494a292b63ec87.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/2495192f1326b07ec19fe29a833886c68b3db11229eff5af36494a292b63ec87.jpg)

![397d0248fb8f77ee1e2a0811fe44b5553d291db40880dc37e72ccc89c406a39e.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/397d0248fb8f77ee1e2a0811fe44b5553d291db40880dc37e72ccc89c406a39e.jpg)

![3eb0884e205f6e2f1f813652d78b3d75456e95d026ffaa580f0de9f933324f69.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/3eb0884e205f6e2f1f813652d78b3d75456e95d026ffaa580f0de9f933324f69.jpg)

![48c0d3d3ab61b99d06363a13059a0d8ba31d5981a15437c238b3188afefec932.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/48c0d3d3ab61b99d06363a13059a0d8ba31d5981a15437c238b3188afefec932.jpg)

![508ec05849101070b507505e2435fc27afcd59c0c8ae81f11d1eae36d5a855f2.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/508ec05849101070b507505e2435fc27afcd59c0c8ae81f11d1eae36d5a855f2.jpg)

![6f2f312704d4df97afd715323f85d18fcb10d1084493e597f1982a6e7a5002b4.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/6f2f312704d4df97afd715323f85d18fcb10d1084493e597f1982a6e7a5002b4.jpg)

![824c30b2bce9af473fa6cece61cd09682c4bcbaf11524959a01b56a727bdda28.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/824c30b2bce9af473fa6cece61cd09682c4bcbaf11524959a01b56a727bdda28.jpg)

![91084b4a9c7f7b22c87ec99f39e3f64c43930a2b32957ebcd886e5ecf0ca458b.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/91084b4a9c7f7b22c87ec99f39e3f64c43930a2b32957ebcd886e5ecf0ca458b.jpg)

![978f4b299afe76a6d333e1e43ef5650101e7cb99294b5ae2589025264f50cd58.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/978f4b299afe76a6d333e1e43ef5650101e7cb99294b5ae2589025264f50cd58.jpg)

![cb956276404de4ac2138d4c5b12426bb2e273f2438a670b3724815a3f6a1ed6f.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/cb956276404de4ac2138d4c5b12426bb2e273f2438a670b3724815a3f6a1ed6f.jpg)

![cc2886399c80b43f9f4251e819c93b25c1540690a18f8cc5d5ee89c2f18e79c5.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/cc2886399c80b43f9f4251e819c93b25c1540690a18f8cc5d5ee89c2f18e79c5.jpg)

![d294ec13e4c598d512b4110543b2925d1a75abd3b7f5a2931067aa002970753a.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/d294ec13e4c598d512b4110543b2925d1a75abd3b7f5a2931067aa002970753a.jpg)

![dfc2f56b29b667861b69503208aacf572f305f090e4e211154e26d638f47f8d3.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/dfc2f56b29b667861b69503208aacf572f305f090e4e211154e26d638f47f8d3.jpg)

![eb3b174b5364f6ff30e87327b5d430efaad6612c62e018b69a697775c44c4ba1.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/eb3b174b5364f6ff30e87327b5d430efaad6612c62e018b69a697775c44c4ba1.jpg)

![f2366b9f5dc6e2c1fccbc68922f8b87cbf9fc569d549b2224439f52d3900c65a.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/f2366b9f5dc6e2c1fccbc68922f8b87cbf9fc569d549b2224439f52d3900c65a.jpg)

![f6bbfe8503ebdac3b9c7ad75425e4188b363f3c457fff7b221039160e1aff8ec.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/f6bbfe8503ebdac3b9c7ad75425e4188b363f3c457fff7b221039160e1aff8ec.jpg)

![fc6e18bdcd35dc8d34743093d2656a044f72ffe0bb7e5d4fadee2cfa9597bad0.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/images/fc6e18bdcd35dc8d34743093d2656a044f72ffe0bb7e5d4fadee2cfa9597bad0.jpg)

### Tables

![1bb7b70b947b40c354f925e961d9f2e3ee0585fba916b7560571e3bd54930a41.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/tables/1bb7b70b947b40c354f925e961d9f2e3ee0585fba916b7560571e3bd54930a41.jpg)

![1f8c174373e7747b979ae3775e0343a469bf93c9a26e9c32652f743c4b7cf387.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/tables/1f8c174373e7747b979ae3775e0343a469bf93c9a26e9c32652f743c4b7cf387.jpg)

![38d3c68846feb9c50796164ee8299e2bafbc638e964f0366aac4dc9666a65035.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/tables/38d3c68846feb9c50796164ee8299e2bafbc638e964f0366aac4dc9666a65035.jpg)

![3e56c8b99fa977633669e6db075c66a3f091be3bba0a0594dde99ffa6364ce6b.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/tables/3e56c8b99fa977633669e6db075c66a3f091be3bba0a0594dde99ffa6364ce6b.jpg)

![553dc80c8751c173ec7f0d7ed23f12543c67b4e931689d8cdc22b7394df38401.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/tables/553dc80c8751c173ec7f0d7ed23f12543c67b4e931689d8cdc22b7394df38401.jpg)

![df4eb14b3c9c6b788c8cb874b7a476bd33010d375fa10fbff003e10223fcadf0.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/tables/df4eb14b3c9c6b788c8cb874b7a476bd33010d375fa10fbff003e10223fcadf0.jpg)

![f4e83e9bd8e316c351c1ff340f4a30ad62c79c9f652a2f6f4efd3e9ff18933f7.jpg](../nips_results/840_VETA-DiT_%20Variance-Equalized%20and%20Temporally%20Adaptive%20Quantization%20for%20Efficient%204-bit%20Diffusion%20Tran/tables/f4e83e9bd8e316c351c1ff340f4a30ad62c79c9f652a2f6f4efd3e9ff18933f7.jpg)

## Optimistic Query Routing in Clustering-based Approximate Maximum Inner Product Search


### Images

![17cd9e65f303127c5140cf7a62d419209b44a42598ce11bc68f1cef643d373fe.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/17cd9e65f303127c5140cf7a62d419209b44a42598ce11bc68f1cef643d373fe.jpg)

![2172d77c3c87fa2150738fa7a61d4963893e6736a934e17be007bd0de7d6087d.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/2172d77c3c87fa2150738fa7a61d4963893e6736a934e17be007bd0de7d6087d.jpg)

![3a306db78b341742eee69dbc1ac9794321c7e61bbda3ec8c0f3bd60756ea09c8.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/3a306db78b341742eee69dbc1ac9794321c7e61bbda3ec8c0f3bd60756ea09c8.jpg)

![5a22e6ee1d8aacac05f2363639f2a4c3d967f8c0a303f6c5e731c34f61d60c4a.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/5a22e6ee1d8aacac05f2363639f2a4c3d967f8c0a303f6c5e731c34f61d60c4a.jpg)

![643c4ffb2f2d4fa11b4a85e7cc5cfd62a7c1e07e77e6d95cf1735b68ff8d714b.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/643c4ffb2f2d4fa11b4a85e7cc5cfd62a7c1e07e77e6d95cf1735b68ff8d714b.jpg)

![7c57d102878396a608dfc5983f39f6d44e87bbb60a72e7af8e8689f41527a5b0.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/7c57d102878396a608dfc5983f39f6d44e87bbb60a72e7af8e8689f41527a5b0.jpg)

![87f120182c565d127e51a110a9fe23047fad71895377082918e607e2c292cb47.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/87f120182c565d127e51a110a9fe23047fad71895377082918e607e2c292cb47.jpg)

![8c1b3622985575bce100b780219fd3d778360a4051c735c3ec87de023efc043c.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/8c1b3622985575bce100b780219fd3d778360a4051c735c3ec87de023efc043c.jpg)

![9379008a2da7f16bcd4084cf5946dcc6aec077597648e8e8b15d617a7a359f79.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/9379008a2da7f16bcd4084cf5946dcc6aec077597648e8e8b15d617a7a359f79.jpg)

![b7b496d9d1b53690e5f5e46f554e066bb388183bf8675f8cbe83a591e7d1bded.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/b7b496d9d1b53690e5f5e46f554e066bb388183bf8675f8cbe83a591e7d1bded.jpg)

![d45aff9cfaf8127f7ef0eea4a260dee89fe1ec431e3f987c5a888bd613c1a42a.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/d45aff9cfaf8127f7ef0eea4a260dee89fe1ec431e3f987c5a888bd613c1a42a.jpg)

![d6ad1d5fdfba3ea5fd1eabb608a7ebed38fdb25a7423b1d35d5a74e752379af2.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/d6ad1d5fdfba3ea5fd1eabb608a7ebed38fdb25a7423b1d35d5a74e752379af2.jpg)

![eb719a5629ce7bf51e87be33c6d75da102801803dd572a9eb63980e0b3380d5e.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/eb719a5629ce7bf51e87be33c6d75da102801803dd572a9eb63980e0b3380d5e.jpg)

![fcd4f07d5fe9b8299468d46ac8b662a9007c36a4ca7d2564d3858adff01d18f9.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/fcd4f07d5fe9b8299468d46ac8b662a9007c36a4ca7d2564d3858adff01d18f9.jpg)

![fd13363cc4d0679ac3a16e59e0bd86e15ba6a62f43b6e4cab3ad335ffbd71546.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/images/fd13363cc4d0679ac3a16e59e0bd86e15ba6a62f43b6e4cab3ad335ffbd71546.jpg)

### Tables

![428b7e052878b614abddb2874856451e34cd3dcedce8b3b1e6897d20bd9d3f7b.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/tables/428b7e052878b614abddb2874856451e34cd3dcedce8b3b1e6897d20bd9d3f7b.jpg)

![a4c1d68ffc4b70d3f03ca6519b1693db0ad46b5bcda4e2bda08fb098f0bf3a93.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/tables/a4c1d68ffc4b70d3f03ca6519b1693db0ad46b5bcda4e2bda08fb098f0bf3a93.jpg)

![cc8d997eda821f135c52515b0a04c6426c225ead218a8788e9ec0c049b8a6c8c.jpg](../nips_results/841_Optimistic%20Query%20Routing%20in%20Clustering-based%20Approximate%20Maximum%20Inner%20Product%20Search/tables/cc8d997eda821f135c52515b0a04c6426c225ead218a8788e9ec0c049b8a6c8c.jpg)

## Variational Task Vector Composition


### Images

![2aa8fbace345e970f90566128fe77de879c71380f412be343a43f8e1de4608c2.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/images/2aa8fbace345e970f90566128fe77de879c71380f412be343a43f8e1de4608c2.jpg)

![50e16955b2635bce16f6730b5a41cd084b7c5bb5088cc696f0a53e80da4f48a2.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/images/50e16955b2635bce16f6730b5a41cd084b7c5bb5088cc696f0a53e80da4f48a2.jpg)

![87191f2a192d8bd68a6bebacfe91ebc32ac6bc6a11b7aa2feb9909d9fb99c68c.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/images/87191f2a192d8bd68a6bebacfe91ebc32ac6bc6a11b7aa2feb9909d9fb99c68c.jpg)

![d05d8b34817c2ea74b2ef1b3a224a47b6406c9387391e0fc061df256bd605355.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/images/d05d8b34817c2ea74b2ef1b3a224a47b6406c9387391e0fc061df256bd605355.jpg)

![f4382b836dd474ad7c9f1bc1e5a6a5238a8467e0cd8b5efa4b2c20e851216c08.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/images/f4382b836dd474ad7c9f1bc1e5a6a5238a8467e0cd8b5efa4b2c20e851216c08.jpg)

### Tables

![5a0b499f0e6964bc6de5adaad8e81e984e01127834e42fb6845643a2150ce292.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/tables/5a0b499f0e6964bc6de5adaad8e81e984e01127834e42fb6845643a2150ce292.jpg)

![616d378bfd9f26514565b7797e5d23ecf0b6a658515fbeb1c57c6ad2c1a90d1f.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/tables/616d378bfd9f26514565b7797e5d23ecf0b6a658515fbeb1c57c6ad2c1a90d1f.jpg)

![9cefb818485ff601bc897eebc22e75ddc86a5a9c5543289ecaed91f1fcd8808b.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/tables/9cefb818485ff601bc897eebc22e75ddc86a5a9c5543289ecaed91f1fcd8808b.jpg)

![a6e538a5b0e10e85f215324e03aa9ad73820e3f75b285c767a90516c2f51ec55.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/tables/a6e538a5b0e10e85f215324e03aa9ad73820e3f75b285c767a90516c2f51ec55.jpg)

![b5c3aa7ce0c1f6ff83f1dfba8b2efccd2200c1f1722e1119af6c6007ac624779.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/tables/b5c3aa7ce0c1f6ff83f1dfba8b2efccd2200c1f1722e1119af6c6007ac624779.jpg)

![b639e2392045470a18b59dd7b6535c57e8cfe3e6cf524eb37a5d5c4eacc46226.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/tables/b639e2392045470a18b59dd7b6535c57e8cfe3e6cf524eb37a5d5c4eacc46226.jpg)

![c004dda0f2f64417fcce7121fd48805f4652e80d5875a66c2df4d44cf1f72a57.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/tables/c004dda0f2f64417fcce7121fd48805f4652e80d5875a66c2df4d44cf1f72a57.jpg)

![c55d98edacb982d8df578d19de7c61cd6828e6632cb3a4ff97a8f6343427262d.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/tables/c55d98edacb982d8df578d19de7c61cd6828e6632cb3a4ff97a8f6343427262d.jpg)

![f535b1a777636a9ba879334db0c5c1a01eb15eb268808c23fbd51c2126db19b1.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/tables/f535b1a777636a9ba879334db0c5c1a01eb15eb268808c23fbd51c2126db19b1.jpg)

![fa4dee983402f8e2fb6dc49f797e9ec3315211a09bb31c1091d4b55246319e8e.jpg](../nips_results/842_Variational%20Task%20Vector%20Composition/tables/fa4dee983402f8e2fb6dc49f797e9ec3315211a09bb31c1091d4b55246319e8e.jpg)

## Semantic Representation Attack against Aligned Large Language Models


### Images

![0c77e8a7915bd55993079e33d3c666c769036490631233f0a8f4bc3573d8cd41.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/images/0c77e8a7915bd55993079e33d3c666c769036490631233f0a8f4bc3573d8cd41.jpg)

![67c6a5861c17433accd33d9b9217281ab344a9784e09714fbe32e565aac1ea49.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/images/67c6a5861c17433accd33d9b9217281ab344a9784e09714fbe32e565aac1ea49.jpg)

![a675269add34ff2938084405231aa5c969ae9e2bbf15ad2129f9421ce2b27ef9.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/images/a675269add34ff2938084405231aa5c969ae9e2bbf15ad2129f9421ce2b27ef9.jpg)

![b3f87c7d81bf16f1726a18ddadf19c0ebe9abfbef2d191fda7a26228f2d76082.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/images/b3f87c7d81bf16f1726a18ddadf19c0ebe9abfbef2d191fda7a26228f2d76082.jpg)

### Tables

![076909d6a1980342af1d9b18998d26434ade47fc69e954b1f1d4261d56600574.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/076909d6a1980342af1d9b18998d26434ade47fc69e954b1f1d4261d56600574.jpg)

![0c68d8a662bd5200a810c41d2e7de774eac9ee8ad9f03e08136e38b450a70b24.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/0c68d8a662bd5200a810c41d2e7de774eac9ee8ad9f03e08136e38b450a70b24.jpg)

![16814c31baf0b77b8ab355525fd1364d5eb19a45b39074944088d506079be9e7.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/16814c31baf0b77b8ab355525fd1364d5eb19a45b39074944088d506079be9e7.jpg)

![245b27f1543b1cf82a75e8a5dc624a461cd1188f7e304699be6c72eb8cfa9d25.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/245b27f1543b1cf82a75e8a5dc624a461cd1188f7e304699be6c72eb8cfa9d25.jpg)

![27f2c605da6ba990ee79da130ee22f5447c14b5b6b8855acb037a1cbda925fde.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/27f2c605da6ba990ee79da130ee22f5447c14b5b6b8855acb037a1cbda925fde.jpg)

![2e93555a55468a8eb02b6ffa0565380c90786fee9e6b482ced5246506dd0ff0b.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/2e93555a55468a8eb02b6ffa0565380c90786fee9e6b482ced5246506dd0ff0b.jpg)

![306d0807c1e01fe38fb42d78816253e92effe355ebe3531271bf3a1a60eaedef.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/306d0807c1e01fe38fb42d78816253e92effe355ebe3531271bf3a1a60eaedef.jpg)

![4bcae3ff1d6c3b14c7ad295b3d1c65ae91b64ed263e051a1c4ec4d2811539831.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/4bcae3ff1d6c3b14c7ad295b3d1c65ae91b64ed263e051a1c4ec4d2811539831.jpg)

![74353c5e1b02008ab08f0f2cb8db32df0eab0d8b17cc5f9008bab328dbf2d35a.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/74353c5e1b02008ab08f0f2cb8db32df0eab0d8b17cc5f9008bab328dbf2d35a.jpg)

![80f5429141783427fe2983b303ae2bfc1e4b2ac053559b8c832e9ae06ebf66c9.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/80f5429141783427fe2983b303ae2bfc1e4b2ac053559b8c832e9ae06ebf66c9.jpg)

![9376e913f82aa258854df3293f70186233225878126c92f18160f3827385434d.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/9376e913f82aa258854df3293f70186233225878126c92f18160f3827385434d.jpg)

![cbbfff83ccf7bfeb947131f63dd84cc6f4e6f341041a3c2d15a671d481c80e7d.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/cbbfff83ccf7bfeb947131f63dd84cc6f4e6f341041a3c2d15a671d481c80e7d.jpg)

![d548d4a15bf02675f8332cb339f797e8347a815c80468128e392fe4890913a68.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/d548d4a15bf02675f8332cb339f797e8347a815c80468128e392fe4890913a68.jpg)

![e5da02dca4b788da08761ae5cfc3fb0640c2c71e9b24905df3cbe63e25dff01d.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/e5da02dca4b788da08761ae5cfc3fb0640c2c71e9b24905df3cbe63e25dff01d.jpg)

![f300f7c888d49cbf6b229ee0309f2d5ec89a456d9e60ac245341fea88e7c16fc.jpg](../nips_results/843_Semantic%20Representation%20Attack%20against%20Aligned%20Large%20Language%20Models/tables/f300f7c888d49cbf6b229ee0309f2d5ec89a456d9e60ac245341fea88e7c16fc.jpg)

## Visual Instruction Bottleneck Tuning


### Images

![05a443cd4fb65a09cac08f99ed1bcd3168aed699642c00ec483688b136bf7331.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/05a443cd4fb65a09cac08f99ed1bcd3168aed699642c00ec483688b136bf7331.jpg)

![06ee5afe2d7d68e62f3df00492f455f494bfd61dd554c4eb6b07b212d1ca77eb.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/06ee5afe2d7d68e62f3df00492f455f494bfd61dd554c4eb6b07b212d1ca77eb.jpg)

![0861af5f72a1caac866a2518d4f1a5bce32c9757e64daa869125072ec0f57eef.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/0861af5f72a1caac866a2518d4f1a5bce32c9757e64daa869125072ec0f57eef.jpg)

![1f0813713fab669249b00cc90b60abc64c617cfe6afc8bf23a64e3b482734f9f.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/1f0813713fab669249b00cc90b60abc64c617cfe6afc8bf23a64e3b482734f9f.jpg)

![23ca5ce6ddbea4746d37972dfe8092919b0ca318cb96426f0081d48aab2d73c2.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/23ca5ce6ddbea4746d37972dfe8092919b0ca318cb96426f0081d48aab2d73c2.jpg)

![27529e1b3eb6a38a24f9ee92d3b77fc15050a0471139896865eb1f3d955c37d0.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/27529e1b3eb6a38a24f9ee92d3b77fc15050a0471139896865eb1f3d955c37d0.jpg)

![2b6b0534d8a1da3fe7c18b2d08ba9da965a322881a970e32469d03f4f0e8b600.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/2b6b0534d8a1da3fe7c18b2d08ba9da965a322881a970e32469d03f4f0e8b600.jpg)

![2d3ffce1eeb50f8e8162a7434fb28be52eb9e5adcd61744333f81e5dbaf04eb0.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/2d3ffce1eeb50f8e8162a7434fb28be52eb9e5adcd61744333f81e5dbaf04eb0.jpg)

![37848bd85706dfc0bc5cd741c55ae624dcf4f3c526f23393a8b580b141662374.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/37848bd85706dfc0bc5cd741c55ae624dcf4f3c526f23393a8b580b141662374.jpg)

![6f2d13d78568c43577cb21e78d9bd61f83df1010584ab622a50f225a810b8e70.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/6f2d13d78568c43577cb21e78d9bd61f83df1010584ab622a50f225a810b8e70.jpg)

![9712bf3201ab70871b03869b94a123ee21d3880fac51b7dbd16da4d827052c67.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/9712bf3201ab70871b03869b94a123ee21d3880fac51b7dbd16da4d827052c67.jpg)

![c9794f3ff1f0384eb65decc8b0524b91b9fa354913f8520c441aee3a2c786f56.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/c9794f3ff1f0384eb65decc8b0524b91b9fa354913f8520c441aee3a2c786f56.jpg)

![df2e488d488d0bef5516d9030f8b6dbc2ae6df82bb4207f0d4c8fb15de0f2f0a.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/df2e488d488d0bef5516d9030f8b6dbc2ae6df82bb4207f0d4c8fb15de0f2f0a.jpg)

![f01304fcd276959099537caae2197af10c68a63d6f1aba57bf8db4bb73d6d240.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/f01304fcd276959099537caae2197af10c68a63d6f1aba57bf8db4bb73d6d240.jpg)

![fdae10c01b47646b065e4f6a8fa25b03f66ce61ad037a2bc99347032ee349bba.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/images/fdae10c01b47646b065e4f6a8fa25b03f66ce61ad037a2bc99347032ee349bba.jpg)

### Tables

![04b9d93d32cfbc709c004c7fe352591952d794a9a01bad7d29376935e74c5b40.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/04b9d93d32cfbc709c004c7fe352591952d794a9a01bad7d29376935e74c5b40.jpg)

![30929967a1fb93b17a42fe7fc8d5d5d9e39da5aa0473aaf42b4f955e76b1db9f.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/30929967a1fb93b17a42fe7fc8d5d5d9e39da5aa0473aaf42b4f955e76b1db9f.jpg)

![3df10d600e52d60a526ea9493d1e54a76765610c97a39e2aabdca4a8d499ce92.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/3df10d600e52d60a526ea9493d1e54a76765610c97a39e2aabdca4a8d499ce92.jpg)

![3f8cdea73749193cf126a7fdb6ede9ff83619e7a064e1a5b7dd9d8bc99d207d8.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/3f8cdea73749193cf126a7fdb6ede9ff83619e7a064e1a5b7dd9d8bc99d207d8.jpg)

![4db9b753ffb921112b163b357c1c4ba9c66192c7f65b45ecb12411b52ed48569.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/4db9b753ffb921112b163b357c1c4ba9c66192c7f65b45ecb12411b52ed48569.jpg)

![5d8327bd5ff9729dfb6c661330b262cbfd8d1ce209bfecf8bf2561f0f8f44536.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/5d8327bd5ff9729dfb6c661330b262cbfd8d1ce209bfecf8bf2561f0f8f44536.jpg)

![6f957292a447d0550e9e831c5c10ab29f93c7615728138212c43dfc1125623c9.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/6f957292a447d0550e9e831c5c10ab29f93c7615728138212c43dfc1125623c9.jpg)

![7593f226766d07522abcdc0b19d76e90bb71971241056055c01fe13add74c88f.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/7593f226766d07522abcdc0b19d76e90bb71971241056055c01fe13add74c88f.jpg)

![84988c5f9eae55a1b49c1b070ed4ee35414c8d2a4432afaec2c98c0fa461c280.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/84988c5f9eae55a1b49c1b070ed4ee35414c8d2a4432afaec2c98c0fa461c280.jpg)

![8dac6f463ab389da93a8df48096a505ab46300389dc3fbcd31cf9dccb15d3018.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/8dac6f463ab389da93a8df48096a505ab46300389dc3fbcd31cf9dccb15d3018.jpg)

![921b43c342684d2b800fd05bc0d23fd1992033af679eb77ed4730e625b3fba71.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/921b43c342684d2b800fd05bc0d23fd1992033af679eb77ed4730e625b3fba71.jpg)

![9865a7be3638bde7e2af30d73be4661b0602fea37f6ceaa371d21d009e10e3ac.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/9865a7be3638bde7e2af30d73be4661b0602fea37f6ceaa371d21d009e10e3ac.jpg)

![ac63224ad05a61a2d346dffecda668f5df2e32b29f5d0b677658ec8086455655.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/ac63224ad05a61a2d346dffecda668f5df2e32b29f5d0b677658ec8086455655.jpg)

![cb8de86a740c0c751290cb635606689f64086e2a26db9a56ea5f0f079b406ceb.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/cb8de86a740c0c751290cb635606689f64086e2a26db9a56ea5f0f079b406ceb.jpg)

![ff5f1f920d1bc770a3d66ab4af85e4e87256be952c6b0cfabe5cde3f629cd77a.jpg](../nips_results/844_Visual%20Instruction%20Bottleneck%20Tuning/tables/ff5f1f920d1bc770a3d66ab4af85e4e87256be952c6b0cfabe5cde3f629cd77a.jpg)

## Reinforcing Spatial Reasoning in Vision-Language Models with Interwoven Thinking and Visual Drawing


### Images

![0688cba62a023e316e97a1672071151b4505e1e882e2f7b042df37f057c5f825.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/0688cba62a023e316e97a1672071151b4505e1e882e2f7b042df37f057c5f825.jpg)

![170f17402c91916a0d43e7fe1b70ec870bc63218b91f50b6170b36f1c5fa4158.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/170f17402c91916a0d43e7fe1b70ec870bc63218b91f50b6170b36f1c5fa4158.jpg)

![195e7e80445c7412fc73daed6286ffbe31976c39e84a00e219b416d9202df906.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/195e7e80445c7412fc73daed6286ffbe31976c39e84a00e219b416d9202df906.jpg)

![20ea1beb96fea08db3c9b3839a39aebda11fff4e602d9f3e1b96307802531c29.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/20ea1beb96fea08db3c9b3839a39aebda11fff4e602d9f3e1b96307802531c29.jpg)

![2c5a9cb55dc4518322cd8e6116bae2a2c0ba64321599bb54efa95ed09259d4d6.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/2c5a9cb55dc4518322cd8e6116bae2a2c0ba64321599bb54efa95ed09259d4d6.jpg)

![320d3f190afccd3eb727f22584a7e93abf1bb1e6d55931cce5d024c08703dedd.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/320d3f190afccd3eb727f22584a7e93abf1bb1e6d55931cce5d024c08703dedd.jpg)

![7cb00c08238b378b4acaa669d100e863f10e1060b8f9bc5c9f6c35a9bd4d7e21.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/7cb00c08238b378b4acaa669d100e863f10e1060b8f9bc5c9f6c35a9bd4d7e21.jpg)

![8c45e8b9101f3aad19a3ad1ea92a23a9508254225b6e6ccd97b65c7cf6adfbfe.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/8c45e8b9101f3aad19a3ad1ea92a23a9508254225b6e6ccd97b65c7cf6adfbfe.jpg)

![91f3616b4550288aed783736bc1fe45a2755d67a3b70df18663c315a8f361fde.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/91f3616b4550288aed783736bc1fe45a2755d67a3b70df18663c315a8f361fde.jpg)

![a398f3574bffeb2ff7b50c5d0046bc6958194f0811e1a70488b3d4baaa1aea26.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/a398f3574bffeb2ff7b50c5d0046bc6958194f0811e1a70488b3d4baaa1aea26.jpg)

![a97239ca4c985aa9a8e97514e026900be1b7978bcba8735943532b3000d9516b.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/a97239ca4c985aa9a8e97514e026900be1b7978bcba8735943532b3000d9516b.jpg)

![b5a5ae85fa19477bc54067af6de6251f7dad6fbb596a92c0947fe52f25dcc786.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/b5a5ae85fa19477bc54067af6de6251f7dad6fbb596a92c0947fe52f25dcc786.jpg)

![c25c10f98d226b4e943e8d791209536c107e0d4d2a2559ae7849f5290f3d2f11.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/c25c10f98d226b4e943e8d791209536c107e0d4d2a2559ae7849f5290f3d2f11.jpg)

![d8414d542620ebae71ebb7b15506e4647d4a260173c46500fc08c3bc1079f872.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/d8414d542620ebae71ebb7b15506e4647d4a260173c46500fc08c3bc1079f872.jpg)

![e7a696a4bcc5951d0317ebec4a8d2db536d14288e5c09d0119a07e1e500a2e74.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/e7a696a4bcc5951d0317ebec4a8d2db536d14288e5c09d0119a07e1e500a2e74.jpg)

![eb09ea3b30a094ed446162039a420e2f93e53aa647fd57fd971464d5a1da940f.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/eb09ea3b30a094ed446162039a420e2f93e53aa647fd57fd971464d5a1da940f.jpg)

![efcdf4493894a1431eb3de512e6d92e747c2656f987031e7d3c39f6409befd6a.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/efcdf4493894a1431eb3de512e6d92e747c2656f987031e7d3c39f6409befd6a.jpg)

![fa20ddd8a443ee32dc3d66333b7e83aa11a575f95dceddfd01ee5100783b0cde.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/fa20ddd8a443ee32dc3d66333b7e83aa11a575f95dceddfd01ee5100783b0cde.jpg)

![fd4b63486bdbed1b338772540556d1b4ffb0ad720259435769331e61e29611b1.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/images/fd4b63486bdbed1b338772540556d1b4ffb0ad720259435769331e61e29611b1.jpg)

### Tables

![2d787234d67a83b02bd5259d8b9c78abd9c49f30aebf1f7a2cfc6bfb6df81c74.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/tables/2d787234d67a83b02bd5259d8b9c78abd9c49f30aebf1f7a2cfc6bfb6df81c74.jpg)

![52a89719d8606d1287e033c8c06e211b63f30c6a564f8e11a4cadda8f6b7bb66.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/tables/52a89719d8606d1287e033c8c06e211b63f30c6a564f8e11a4cadda8f6b7bb66.jpg)

![76c8515a35ed9d8c0a8cf36ad533ce9874d8943047298aa2ff6f4300dddf4812.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/tables/76c8515a35ed9d8c0a8cf36ad533ce9874d8943047298aa2ff6f4300dddf4812.jpg)

![87ffb3475da3288e39c46a50c60e2134c11bd75e1aca4803b19aa477d33f2c54.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/tables/87ffb3475da3288e39c46a50c60e2134c11bd75e1aca4803b19aa477d33f2c54.jpg)

![9316b4a43bfa004a49db203261f53d13dc5b4fce5101c06c8e64c53d7e522989.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/tables/9316b4a43bfa004a49db203261f53d13dc5b4fce5101c06c8e64c53d7e522989.jpg)

![d6eb3980468faba12f3f6c71bdc906016d60f945b798f678328efccd6c21f60e.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/tables/d6eb3980468faba12f3f6c71bdc906016d60f945b798f678328efccd6c21f60e.jpg)

![e2ce84aa4f8cbb51b506e9423a3292b815d49a2524c10a7825fcf41aa6e5d54b.jpg](../nips_results/845_Reinforcing%20Spatial%20Reasoning%20in%20Vision-Language%20Models%20with%20Interwoven%20Thinking%20and%20Visual%20Drawing/tables/e2ce84aa4f8cbb51b506e9423a3292b815d49a2524c10a7825fcf41aa6e5d54b.jpg)

## Dendritic Resonate-and-Fire Neuron for Effective and Efficient Long Sequence Modeling


### Images

![28f264b76f45729a1320cf86a5cf5b65658e4e37e27e1df6b56f47a1e6089d31.jpg](../nips_results/846_Dendritic%20Resonate-and-Fire%20Neuron%20for%20Effective%20and%20Efficient%20Long%20Sequence%20Modeling/images/28f264b76f45729a1320cf86a5cf5b65658e4e37e27e1df6b56f47a1e6089d31.jpg)

![579a311b7aa59014bab6a7285385a4d8b3abd7fc41d19606ddfd1345122137cd.jpg](../nips_results/846_Dendritic%20Resonate-and-Fire%20Neuron%20for%20Effective%20and%20Efficient%20Long%20Sequence%20Modeling/images/579a311b7aa59014bab6a7285385a4d8b3abd7fc41d19606ddfd1345122137cd.jpg)

![5d7a71d5adf880ad88d9793f86db3c17a1cbc6457956fc8d7e0d1dbb073baa0e.jpg](../nips_results/846_Dendritic%20Resonate-and-Fire%20Neuron%20for%20Effective%20and%20Efficient%20Long%20Sequence%20Modeling/images/5d7a71d5adf880ad88d9793f86db3c17a1cbc6457956fc8d7e0d1dbb073baa0e.jpg)

![a56f9d4d7739f801846247ff85ce224a375d9ade7fe3686662e7f72931cef7e7.jpg](../nips_results/846_Dendritic%20Resonate-and-Fire%20Neuron%20for%20Effective%20and%20Efficient%20Long%20Sequence%20Modeling/images/a56f9d4d7739f801846247ff85ce224a375d9ade7fe3686662e7f72931cef7e7.jpg)

### Tables

![14c001b67270a61856b88eea34684118a567bd23fd38c283e98ca0831386f693.jpg](../nips_results/846_Dendritic%20Resonate-and-Fire%20Neuron%20for%20Effective%20and%20Efficient%20Long%20Sequence%20Modeling/tables/14c001b67270a61856b88eea34684118a567bd23fd38c283e98ca0831386f693.jpg)

![38f6bb5570775904e4c74400f083aa59d81341967da40e9bcea7c632c5743308.jpg](../nips_results/846_Dendritic%20Resonate-and-Fire%20Neuron%20for%20Effective%20and%20Efficient%20Long%20Sequence%20Modeling/tables/38f6bb5570775904e4c74400f083aa59d81341967da40e9bcea7c632c5743308.jpg)

![4a5358cf5985f6757b1aa8bfe0a43636c524c31488de1b36f9d73954a11dcab0.jpg](../nips_results/846_Dendritic%20Resonate-and-Fire%20Neuron%20for%20Effective%20and%20Efficient%20Long%20Sequence%20Modeling/tables/4a5358cf5985f6757b1aa8bfe0a43636c524c31488de1b36f9d73954a11dcab0.jpg)

![66eabd15f7bc0e30d51514fedf1c5b98c08b119ec70a9d7731746cabf234794b.jpg](../nips_results/846_Dendritic%20Resonate-and-Fire%20Neuron%20for%20Effective%20and%20Efficient%20Long%20Sequence%20Modeling/tables/66eabd15f7bc0e30d51514fedf1c5b98c08b119ec70a9d7731746cabf234794b.jpg)

![73269298a8a5783a1a742c815bb47f1af640500c460a2337e1d8aad9f369e4e4.jpg](../nips_results/846_Dendritic%20Resonate-and-Fire%20Neuron%20for%20Effective%20and%20Efficient%20Long%20Sequence%20Modeling/tables/73269298a8a5783a1a742c815bb47f1af640500c460a2337e1d8aad9f369e4e4.jpg)

![8af00762b96f16e7374943698fbab833bcf92bfd4606d68e155e0d614e172d04.jpg](../nips_results/846_Dendritic%20Resonate-and-Fire%20Neuron%20for%20Effective%20and%20Efficient%20Long%20Sequence%20Modeling/tables/8af00762b96f16e7374943698fbab833bcf92bfd4606d68e155e0d614e172d04.jpg)

![d887f6ac7f9078dcab7b9e7ed21da16e24c8dbd7ab791e597f10baefd1b00aef.jpg](../nips_results/846_Dendritic%20Resonate-and-Fire%20Neuron%20for%20Effective%20and%20Efficient%20Long%20Sequence%20Modeling/tables/d887f6ac7f9078dcab7b9e7ed21da16e24c8dbd7ab791e597f10baefd1b00aef.jpg)

## Logical Expressiveness of Graph Neural Networks with Hierarchical Node Individualization


### Images

![613bd12844d492f629cb5a2da1dd2da7f29c054b0a486d174c5d6571b0e2ac84.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/images/613bd12844d492f629cb5a2da1dd2da7f29c054b0a486d174c5d6571b0e2ac84.jpg)

![848b14f9bf7dcfb1b503e11b56b6a9ad761845dd4b948f6868aa2679650712b1.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/images/848b14f9bf7dcfb1b503e11b56b6a9ad761845dd4b948f6868aa2679650712b1.jpg)

![8bb015d64a876ab045b1b3cf2c464f58ba7ec82cfd7b3d33447126c14f21e39b.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/images/8bb015d64a876ab045b1b3cf2c464f58ba7ec82cfd7b3d33447126c14f21e39b.jpg)

![a0d308c07fe308add15f0be450dc62a501fb562c0d96b21857dbf6705bb5e206.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/images/a0d308c07fe308add15f0be450dc62a501fb562c0d96b21857dbf6705bb5e206.jpg)

![c4385ffc0aaabbba775f09a20be1a0b589e0ddf7f4d86491a860db8a35c1ca45.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/images/c4385ffc0aaabbba775f09a20be1a0b589e0ddf7f4d86491a860db8a35c1ca45.jpg)

![dfec99a58033bbb51683c5f42af3bd5b0885d7d61bcf75705281bd4ebd707f91.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/images/dfec99a58033bbb51683c5f42af3bd5b0885d7d61bcf75705281bd4ebd707f91.jpg)

![e824c0f9bc00d4195de7367ffd428b81e7be5e9fe57eb7dc49ab2ffc35310fe9.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/images/e824c0f9bc00d4195de7367ffd428b81e7be5e9fe57eb7dc49ab2ffc35310fe9.jpg)

![fc3512b88719ad70b1901ccf5b4ba315be924c503f62bd4b25105abe7f356afd.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/images/fc3512b88719ad70b1901ccf5b4ba315be924c503f62bd4b25105abe7f356afd.jpg)

### Tables

![196f8801aed2dee971b5270aa1c8ce2af07f54857fe742528bef9149a5509591.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/tables/196f8801aed2dee971b5270aa1c8ce2af07f54857fe742528bef9149a5509591.jpg)

![3e25b9e949ad87d328f5b38383e18b6b59e8c334c6be8f10d0f1c717983d23b2.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/tables/3e25b9e949ad87d328f5b38383e18b6b59e8c334c6be8f10d0f1c717983d23b2.jpg)

![42f49b601e5c200141ee1fc7de2054bd7a624767e8d1b8861ed32efe00775ba2.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/tables/42f49b601e5c200141ee1fc7de2054bd7a624767e8d1b8861ed32efe00775ba2.jpg)

![68d72a024e26d7f402cd1f833f6fddf99aee101165df1ca9edde4a24df49142b.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/tables/68d72a024e26d7f402cd1f833f6fddf99aee101165df1ca9edde4a24df49142b.jpg)

![bc846ceb685a090a74488f4ddaeddc090fc188d0ffc8c0c177ac5951d589d87e.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/tables/bc846ceb685a090a74488f4ddaeddc090fc188d0ffc8c0c177ac5951d589d87e.jpg)

![f8ae16809213088c04e3386208f08d98e3cd57e2ba96c85cce2eb174eed3b512.jpg](../nips_results/847_Logical%20Expressiveness%20of%20Graph%20Neural%20Networks%20with%20Hierarchical%20Node%20Individualization/tables/f8ae16809213088c04e3386208f08d98e3cd57e2ba96c85cce2eb174eed3b512.jpg)

## Precise Information Control in Long-Form Text Generation


### Images

![0ca928472b212da3c701ac57c006b43997d4574c83064e3dbe6b44b58b7a77a8.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/images/0ca928472b212da3c701ac57c006b43997d4574c83064e3dbe6b44b58b7a77a8.jpg)

![4c7c921a0636adb71daac809d068c53cf6a0c5f474ae90ee94aaae3156f470aa.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/images/4c7c921a0636adb71daac809d068c53cf6a0c5f474ae90ee94aaae3156f470aa.jpg)

![4ec8e5b0a44063f426e901d9b20c197ba28ef29277157a4564899ca3eeae12ff.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/images/4ec8e5b0a44063f426e901d9b20c197ba28ef29277157a4564899ca3eeae12ff.jpg)

![68d44edbf4a9087befc22ce7bc87a5136d3f670082bd651698eea0caff7bb156.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/images/68d44edbf4a9087befc22ce7bc87a5136d3f670082bd651698eea0caff7bb156.jpg)

![cfd595ff4133b996c771d7e7e2b4cae625d3c41ffeb36632fbf5c388d6c8653f.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/images/cfd595ff4133b996c771d7e7e2b4cae625d3c41ffeb36632fbf5c388d6c8653f.jpg)

![e4d6ecf0e49227925ceba61593f7793badb04839811c237446d7fbe162d5943d.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/images/e4d6ecf0e49227925ceba61593f7793badb04839811c237446d7fbe162d5943d.jpg)

![e82b31a3a6ae97e30ae595883a19e5cab24588c9e0e53ab03229c04f91a36228.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/images/e82b31a3a6ae97e30ae595883a19e5cab24588c9e0e53ab03229c04f91a36228.jpg)

![ec19968097610cce783ff270a6d4b87cdbb63fe3379cd813b2b0fb0d1f7e2fdf.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/images/ec19968097610cce783ff270a6d4b87cdbb63fe3379cd813b2b0fb0d1f7e2fdf.jpg)

![f4049d3d3fdb6b1fa1962ddc081d3713bc9ffc3d0221b84d8899e8ad089a3103.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/images/f4049d3d3fdb6b1fa1962ddc081d3713bc9ffc3d0221b84d8899e8ad089a3103.jpg)

### Tables

![0cdee49fc624370b3d6c9cff25a08e4752759721002aa0339c57874601257058.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/0cdee49fc624370b3d6c9cff25a08e4752759721002aa0339c57874601257058.jpg)

![0ce9ab4833780c552a04bb329a2407ad321ca912a8f388de504d6fa146b379d4.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/0ce9ab4833780c552a04bb329a2407ad321ca912a8f388de504d6fa146b379d4.jpg)

![15df146a3dd5e0930b2c344df81186c9206ca7383c279f2f193c528185de1080.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/15df146a3dd5e0930b2c344df81186c9206ca7383c279f2f193c528185de1080.jpg)

![1b295adbcc0a17dc92e9852d7cb6e7797571ae0617590fcb65ab2bd782fbc8cd.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/1b295adbcc0a17dc92e9852d7cb6e7797571ae0617590fcb65ab2bd782fbc8cd.jpg)

![20f24b215d1df51fe247f43409057d87321f021dd4263b3832a80cdec55abb61.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/20f24b215d1df51fe247f43409057d87321f021dd4263b3832a80cdec55abb61.jpg)

![290bb17d17bee1c33bac8315233e6b9f3a2dd09b7de08df33a653cca1b6237ad.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/290bb17d17bee1c33bac8315233e6b9f3a2dd09b7de08df33a653cca1b6237ad.jpg)

![2b0a1110341e515c1fcddfd0594e054de86153f798a63ca470e68ae0b50bd7ba.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/2b0a1110341e515c1fcddfd0594e054de86153f798a63ca470e68ae0b50bd7ba.jpg)

![2c4cb94327e88e8a08f5a4a376ca2779267872325f04f362df105de0531137df.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/2c4cb94327e88e8a08f5a4a376ca2779267872325f04f362df105de0531137df.jpg)

![39f09c1cf9e24361a77331ab01cb4238ad31e35953cafac862a8d4ac33c295bf.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/39f09c1cf9e24361a77331ab01cb4238ad31e35953cafac862a8d4ac33c295bf.jpg)

![4d1fae5f23339aa3178473f95b22ad5e5ba3151ccd3c60084f48b2aae4ece6dd.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/4d1fae5f23339aa3178473f95b22ad5e5ba3151ccd3c60084f48b2aae4ece6dd.jpg)

![64f52878b2048ab30902372c9e285097c38368655fb31533507caa79afebc811.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/64f52878b2048ab30902372c9e285097c38368655fb31533507caa79afebc811.jpg)

![6bad4cf055deb6e66dd3644762a0c6f701bb6cdba4584fd5e62e0776286e2918.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/6bad4cf055deb6e66dd3644762a0c6f701bb6cdba4584fd5e62e0776286e2918.jpg)

![70618ba2488c762a493b1887d7ff768e3a441c60d4e1d6ac90bc765061142721.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/70618ba2488c762a493b1887d7ff768e3a441c60d4e1d6ac90bc765061142721.jpg)

![782d64e0cc98580ed09e19feb00f4aeeba0d20ff0542939c66fd981de237df11.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/782d64e0cc98580ed09e19feb00f4aeeba0d20ff0542939c66fd981de237df11.jpg)

![8224b0a651bc86a709ed5c5655080f23be52c8e19a09e96405c892bfd2357319.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/8224b0a651bc86a709ed5c5655080f23be52c8e19a09e96405c892bfd2357319.jpg)

![8394505e296796607b7d23adc1daf17cefb5dfc2f1c790c2962f3094267abd28.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/8394505e296796607b7d23adc1daf17cefb5dfc2f1c790c2962f3094267abd28.jpg)

![993b6b8e896ab5f1ef0009e521acbd6db9c66a325096862ad55cf8f92e3273d0.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/993b6b8e896ab5f1ef0009e521acbd6db9c66a325096862ad55cf8f92e3273d0.jpg)

![9e15a2453162c0fe2da3a703c0b8b098a91b300014929dec68cdcf471922e621.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/9e15a2453162c0fe2da3a703c0b8b098a91b300014929dec68cdcf471922e621.jpg)

![a04322314b3e46b0e888b518f4c289297b817293aad3329335f36c7a364d6e7f.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/a04322314b3e46b0e888b518f4c289297b817293aad3329335f36c7a364d6e7f.jpg)

![b6ba7b0ad2087f77ba889984160d38c614c9da7b822dbc52a5ffa7dca631c38b.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/b6ba7b0ad2087f77ba889984160d38c614c9da7b822dbc52a5ffa7dca631c38b.jpg)

![be92ad9ba74a4725fd8dde711cd1bb521e1acd716176f97d95fe4a73742d88a0.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/be92ad9ba74a4725fd8dde711cd1bb521e1acd716176f97d95fe4a73742d88a0.jpg)

![c215c2ed22f0a21d179b354e00b8771f884b77f079913502bc709e75f8c5a354.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/c215c2ed22f0a21d179b354e00b8771f884b77f079913502bc709e75f8c5a354.jpg)

![ddee17191480a22185e6e05ea3b67660da58aba1b7b35317c64449b2b641a1d0.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/ddee17191480a22185e6e05ea3b67660da58aba1b7b35317c64449b2b641a1d0.jpg)

![e10706aa66699889702953fedf2141682f4cdcbd3a97b57243953fe083fb8ce5.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/e10706aa66699889702953fedf2141682f4cdcbd3a97b57243953fe083fb8ce5.jpg)

![e5b3a0320b15c2e1906e9d4ca5e3841bfb6a696221ce72c12982dadfc70b6e43.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/e5b3a0320b15c2e1906e9d4ca5e3841bfb6a696221ce72c12982dadfc70b6e43.jpg)

![ebf4b7b479de695ba9e35a5840ef05ca482cb9616c801003cd043d712f147bef.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/ebf4b7b479de695ba9e35a5840ef05ca482cb9616c801003cd043d712f147bef.jpg)

![ed1a9cc6439d3f6418f90647bec75530ba63b55b226e2820abf28c9ac9dacf5b.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/ed1a9cc6439d3f6418f90647bec75530ba63b55b226e2820abf28c9ac9dacf5b.jpg)

![f98e3e1cd156f3368175ca2430b008a9662e148a95a84f3726f12255ccc6dd9b.jpg](../nips_results/848_Precise%20Information%20Control%20in%20Long-Form%20Text%20Generation/tables/f98e3e1cd156f3368175ca2430b008a9662e148a95a84f3726f12255ccc6dd9b.jpg)

## A Minimalist Example of Edge-of-Stability and Progressive Sharpening


### Images

![0c3d17866f832e1b792d3d40839e79dd5084ee54230f8372d457a4cd849af85e.jpg](../nips_results/849_A%20Minimalist%20Example%20of%20Edge-of-Stability%20and%20Progressive%20Sharpening/images/0c3d17866f832e1b792d3d40839e79dd5084ee54230f8372d457a4cd849af85e.jpg)

![32157a9ef565b3de3ed848ae27e346f793dc03ee5a2a95faa3b16328065e6202.jpg](../nips_results/849_A%20Minimalist%20Example%20of%20Edge-of-Stability%20and%20Progressive%20Sharpening/images/32157a9ef565b3de3ed848ae27e346f793dc03ee5a2a95faa3b16328065e6202.jpg)

![706d2f0df0c958de04f35577175ad87a443bae2501aa4390d0371f5cbbe08b64.jpg](../nips_results/849_A%20Minimalist%20Example%20of%20Edge-of-Stability%20and%20Progressive%20Sharpening/images/706d2f0df0c958de04f35577175ad87a443bae2501aa4390d0371f5cbbe08b64.jpg)

![71de615a6dc4ff096fdb54f4e7c6a4c321558e1a3041bc19f1868ec5436b9478.jpg](../nips_results/849_A%20Minimalist%20Example%20of%20Edge-of-Stability%20and%20Progressive%20Sharpening/images/71de615a6dc4ff096fdb54f4e7c6a4c321558e1a3041bc19f1868ec5436b9478.jpg)

![7972d1914bad8243eeb622efa09be35f6889a476548a3055adde2c8ab01fa5da.jpg](../nips_results/849_A%20Minimalist%20Example%20of%20Edge-of-Stability%20and%20Progressive%20Sharpening/images/7972d1914bad8243eeb622efa09be35f6889a476548a3055adde2c8ab01fa5da.jpg)

![8e62aed97fdb68cd69021acddd22700d0de1b559ae8b5d4683001df75969138c.jpg](../nips_results/849_A%20Minimalist%20Example%20of%20Edge-of-Stability%20and%20Progressive%20Sharpening/images/8e62aed97fdb68cd69021acddd22700d0de1b559ae8b5d4683001df75969138c.jpg)

![90202e0cc5cf431b30c99022ca13a0550cddce4f6fb3d4cd3d5d05c74973ce7f.jpg](../nips_results/849_A%20Minimalist%20Example%20of%20Edge-of-Stability%20and%20Progressive%20Sharpening/images/90202e0cc5cf431b30c99022ca13a0550cddce4f6fb3d4cd3d5d05c74973ce7f.jpg)

![a24e91ed2054a99924f9fabe007e8e82af55e5cd686388cd14aa7e9a40e93991.jpg](../nips_results/849_A%20Minimalist%20Example%20of%20Edge-of-Stability%20and%20Progressive%20Sharpening/images/a24e91ed2054a99924f9fabe007e8e82af55e5cd686388cd14aa7e9a40e93991.jpg)

![bd79652dffade70f73e47c9bf223d5b5699edecc07ead778685da61644dcf8ed.jpg](../nips_results/849_A%20Minimalist%20Example%20of%20Edge-of-Stability%20and%20Progressive%20Sharpening/images/bd79652dffade70f73e47c9bf223d5b5699edecc07ead778685da61644dcf8ed.jpg)

![cbc243579591bc5841c9c461a4d86a0b2dfd8fb5179a0d6f573584a66878723b.jpg](../nips_results/849_A%20Minimalist%20Example%20of%20Edge-of-Stability%20and%20Progressive%20Sharpening/images/cbc243579591bc5841c9c461a4d86a0b2dfd8fb5179a0d6f573584a66878723b.jpg)

![f780c14613f29b6d339896e588f1116c9f6e2b03c4ff8595809f99263e97f61c.jpg](../nips_results/849_A%20Minimalist%20Example%20of%20Edge-of-Stability%20and%20Progressive%20Sharpening/images/f780c14613f29b6d339896e588f1116c9f6e2b03c4ff8595809f99263e97f61c.jpg)

## Sparc3D: Sparse Representation and Construction for High-Resolution 3D Shapes Modeling


### Images

![25f5cf4ca8f6a23436dfca9ed22f16a8ef41c5427003049fa3b039db2f152328.jpg](../nips_results/850_Sparc3D_%20Sparse%20Representation%20and%20Construction%20for%20High-Resolution%203D%20Shapes%20Modeling/images/25f5cf4ca8f6a23436dfca9ed22f16a8ef41c5427003049fa3b039db2f152328.jpg)

![32ab9d122e62d7c189b3160ea23aac79e57b7df8e5ef90560e82c0fb4700be75.jpg](../nips_results/850_Sparc3D_%20Sparse%20Representation%20and%20Construction%20for%20High-Resolution%203D%20Shapes%20Modeling/images/32ab9d122e62d7c189b3160ea23aac79e57b7df8e5ef90560e82c0fb4700be75.jpg)

![c9d889bc8496d53127495d28231be4755a544f1b31c250b8d8b6feca986875a5.jpg](../nips_results/850_Sparc3D_%20Sparse%20Representation%20and%20Construction%20for%20High-Resolution%203D%20Shapes%20Modeling/images/c9d889bc8496d53127495d28231be4755a544f1b31c250b8d8b6feca986875a5.jpg)

![e65ce0c692b256ee43584e2d28bd8505749da909d45779c35d9ab94ec60980f7.jpg](../nips_results/850_Sparc3D_%20Sparse%20Representation%20and%20Construction%20for%20High-Resolution%203D%20Shapes%20Modeling/images/e65ce0c692b256ee43584e2d28bd8505749da909d45779c35d9ab94ec60980f7.jpg)

![e6a11d359014e462cdbb855afc0f925e5e41b56c908ac17e680f3112355e3570.jpg](../nips_results/850_Sparc3D_%20Sparse%20Representation%20and%20Construction%20for%20High-Resolution%203D%20Shapes%20Modeling/images/e6a11d359014e462cdbb855afc0f925e5e41b56c908ac17e680f3112355e3570.jpg)

![fc2ca18770403c5a9f43cc33d65cda7f65b33a4fc9f2510a29746d447013be07.jpg](../nips_results/850_Sparc3D_%20Sparse%20Representation%20and%20Construction%20for%20High-Resolution%203D%20Shapes%20Modeling/images/fc2ca18770403c5a9f43cc33d65cda7f65b33a4fc9f2510a29746d447013be07.jpg)

### Tables

![099aefb158406a6c2ebb443d62ae87a6c063db46d6a1e5398c02f28809127993.jpg](../nips_results/850_Sparc3D_%20Sparse%20Representation%20and%20Construction%20for%20High-Resolution%203D%20Shapes%20Modeling/tables/099aefb158406a6c2ebb443d62ae87a6c063db46d6a1e5398c02f28809127993.jpg)

![bb3aff7b2e23eb0d7783b185abee911c4da4b6ee96a76754736f0dbe59bc8b13.jpg](../nips_results/850_Sparc3D_%20Sparse%20Representation%20and%20Construction%20for%20High-Resolution%203D%20Shapes%20Modeling/tables/bb3aff7b2e23eb0d7783b185abee911c4da4b6ee96a76754736f0dbe59bc8b13.jpg)

![e238b23c7269b05e161e8208ae8ac6436bd9fe8dffb4102fe3de95cb7048b9e9.jpg](../nips_results/850_Sparc3D_%20Sparse%20Representation%20and%20Construction%20for%20High-Resolution%203D%20Shapes%20Modeling/tables/e238b23c7269b05e161e8208ae8ac6436bd9fe8dffb4102fe3de95cb7048b9e9.jpg)

## Transformers Learn Faster with Semantic Focus


### Images

![0666c5c9a446074dd02693f82f35dfdd86edb82a444de1f23ad7413e6763a8eb.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/0666c5c9a446074dd02693f82f35dfdd86edb82a444de1f23ad7413e6763a8eb.jpg)

![2adc4c0d1bf7bf9a342d0e4ebea66a1b7acd61d3538af114401e94c7be26e897.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/2adc4c0d1bf7bf9a342d0e4ebea66a1b7acd61d3538af114401e94c7be26e897.jpg)

![2f2bc77b3f2553d2f7b2baf2902ad43af377747833719000b7510b67bcec4641.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/2f2bc77b3f2553d2f7b2baf2902ad43af377747833719000b7510b67bcec4641.jpg)

![370b71c3c5b613ee2e4719c0d7713a3afd06deef6d1b288a6ec1a2d9eb318f23.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/370b71c3c5b613ee2e4719c0d7713a3afd06deef6d1b288a6ec1a2d9eb318f23.jpg)

![4314df05f7b628e93c414a717d6f4ba0990b05c979d88b1fc7d39f2957b4acc4.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/4314df05f7b628e93c414a717d6f4ba0990b05c979d88b1fc7d39f2957b4acc4.jpg)

![4371ff4cc1a03a6141ff6ed27a7f5260686edc956ce8e48be8dd6987511b3dc3.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/4371ff4cc1a03a6141ff6ed27a7f5260686edc956ce8e48be8dd6987511b3dc3.jpg)

![43e8f14f01454a034ed236a7d316809d78138f3eeae937f652103a368cb389cd.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/43e8f14f01454a034ed236a7d316809d78138f3eeae937f652103a368cb389cd.jpg)

![6cf8e1d09c1394988b8451cf64cb2b61789e6379b386b544535e471ba89de391.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/6cf8e1d09c1394988b8451cf64cb2b61789e6379b386b544535e471ba89de391.jpg)

![75477f56eb110945d37135d5e1d7e4f19c8adccde22ad56d68ef29c3999d4c08.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/75477f56eb110945d37135d5e1d7e4f19c8adccde22ad56d68ef29c3999d4c08.jpg)

![7de3b48e5c13816c7eee713cbf77f6edc59831ae178e98a1dfdc6f0cf3f9f12f.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/7de3b48e5c13816c7eee713cbf77f6edc59831ae178e98a1dfdc6f0cf3f9f12f.jpg)

![841721b5dcb42519fcfee120f44707594061bf136bc890d6d206bab71cca77c2.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/841721b5dcb42519fcfee120f44707594061bf136bc890d6d206bab71cca77c2.jpg)

![874b6b25a912a765e93f7e03b449427c3ed6980093bfb1cff27dd60da3c4fd4b.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/874b6b25a912a765e93f7e03b449427c3ed6980093bfb1cff27dd60da3c4fd4b.jpg)

![99f5c1b53a7a085026df508f3e559769f59bc0c101e0dfc53f78cfc4a9b4545e.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/99f5c1b53a7a085026df508f3e559769f59bc0c101e0dfc53f78cfc4a9b4545e.jpg)

![9e22a4d5dd844ad2ac35d0927296c0e33d60043ac3a4e3f7d36ede093613817c.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/9e22a4d5dd844ad2ac35d0927296c0e33d60043ac3a4e3f7d36ede093613817c.jpg)

![b988236e200dea6e9ad504baa5b0dea158cb0c0fc728b7f15bf962fc5ddf7615.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/b988236e200dea6e9ad504baa5b0dea158cb0c0fc728b7f15bf962fc5ddf7615.jpg)

![bf53b0185199b5c5094216f6d305891845dec77c522d0e8987083292724fb84c.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/bf53b0185199b5c5094216f6d305891845dec77c522d0e8987083292724fb84c.jpg)

![ce2b2064e74c41ae75e2471a83ac3ca30cf81332d46fffd503098864160efde2.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/ce2b2064e74c41ae75e2471a83ac3ca30cf81332d46fffd503098864160efde2.jpg)

![ce6e8ceb3f3aa28637dca20306d2b2e081d31321890837e28454dd7163302c0c.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/ce6e8ceb3f3aa28637dca20306d2b2e081d31321890837e28454dd7163302c0c.jpg)

![d4186720b56fb80f1b7eec0d24d1d3097823fe8e620f71f54d6986b50537ce8c.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/d4186720b56fb80f1b7eec0d24d1d3097823fe8e620f71f54d6986b50537ce8c.jpg)

![d574637b4a8ca2b8263002cea68e789e2ba0cd018a07ea6ec9522f32d0e94628.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/d574637b4a8ca2b8263002cea68e789e2ba0cd018a07ea6ec9522f32d0e94628.jpg)

![dabe245e1a6ea42431fda7ad3c62ef575aa037a530484f51ceb897a99a28ea76.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/dabe245e1a6ea42431fda7ad3c62ef575aa037a530484f51ceb897a99a28ea76.jpg)

![e6b47859dc8e06fe92de6a0c399879b0d347b9e025f7f8742f49216e669cae14.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/e6b47859dc8e06fe92de6a0c399879b0d347b9e025f7f8742f49216e669cae14.jpg)

![eabf7969654ba434cbfc043fd868365ebb782d1a1092ea1d80818e8dfbc95141.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/eabf7969654ba434cbfc043fd868365ebb782d1a1092ea1d80818e8dfbc95141.jpg)

![ede2e76434d5358a7f8318ce821f6626d118420e5be464c160bebe016ac06c4c.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/ede2e76434d5358a7f8318ce821f6626d118420e5be464c160bebe016ac06c4c.jpg)

![f45aede64dbe67b22d99dcd58ef905c5bf1dffd671e12a6a6cb36269eca0efbf.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/f45aede64dbe67b22d99dcd58ef905c5bf1dffd671e12a6a6cb36269eca0efbf.jpg)

![f7fdf5458125323def43cc6f978bc5245ec4896cda6e01cbf9bce0408b1fd1af.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/f7fdf5458125323def43cc6f978bc5245ec4896cda6e01cbf9bce0408b1fd1af.jpg)

![f997e80ad016bebd0582a4aa19da81467221a9d1c103fad09ecc4a171aaeefe3.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/images/f997e80ad016bebd0582a4aa19da81467221a9d1c103fad09ecc4a171aaeefe3.jpg)

### Tables

![0dc9e567c36182ef94ce6cfb29bb876bbcb74e940b3b8451c0a1977f69659d48.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/tables/0dc9e567c36182ef94ce6cfb29bb876bbcb74e940b3b8451c0a1977f69659d48.jpg)

![530c6fcbabe8fce5e203706e1a8596f465b382a12b6f9aed20a2cd835ba8593f.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/tables/530c6fcbabe8fce5e203706e1a8596f465b382a12b6f9aed20a2cd835ba8593f.jpg)

![b0a152b63020a1ef06b2faf319cbb7537a60cb7c5a91d77845fddf05f96a8d6d.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/tables/b0a152b63020a1ef06b2faf319cbb7537a60cb7c5a91d77845fddf05f96a8d6d.jpg)

![c4879a3c39e18bb728e740bf48e3ef31406f7c0ba764eb0b466e67d8d22a43d9.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/tables/c4879a3c39e18bb728e740bf48e3ef31406f7c0ba764eb0b466e67d8d22a43d9.jpg)

![cec8f3f549f420d5939cec2c3472ee56ac9dedc6c2da1248eac3b2397f27b3de.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/tables/cec8f3f549f420d5939cec2c3472ee56ac9dedc6c2da1248eac3b2397f27b3de.jpg)

![f6a7482acfd4ef929f4722cc82ca31fb9e306d70f6e29ad4cee12156cab2936f.jpg](../nips_results/851_Transformers%20Learn%20Faster%20with%20Semantic%20Focus/tables/f6a7482acfd4ef929f4722cc82ca31fb9e306d70f6e29ad4cee12156cab2936f.jpg)

## Model Inversion with Layer-Specific Modeling and Alignment for Data-Free Continual Learning


### Images

![07fc22dcc162aa6c491c3f8aa477fa1c13c2082013fd43bfa9abad162237db01.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/images/07fc22dcc162aa6c491c3f8aa477fa1c13c2082013fd43bfa9abad162237db01.jpg)

![1b31139ae86b29ebafef77e7be975f6eff39a99945048063dfbed9bef01742f6.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/images/1b31139ae86b29ebafef77e7be975f6eff39a99945048063dfbed9bef01742f6.jpg)

![1c4bbaa16a259ded5c59d51502a0b9b469147e1c7cb8a2dff9600a83a513d372.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/images/1c4bbaa16a259ded5c59d51502a0b9b469147e1c7cb8a2dff9600a83a513d372.jpg)

![22479a5300643bb316fe99f352130437793c3986cf08bb98354294988f0bacc1.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/images/22479a5300643bb316fe99f352130437793c3986cf08bb98354294988f0bacc1.jpg)

![342c17b2643f59304c226809e302994fdf775b61a286b3ec11d12eab73db5fc6.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/images/342c17b2643f59304c226809e302994fdf775b61a286b3ec11d12eab73db5fc6.jpg)

![7a99dbefcc1d5ecd06470892dbc59f90b1b22ceed0734ad73aa45bf60eede39c.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/images/7a99dbefcc1d5ecd06470892dbc59f90b1b22ceed0734ad73aa45bf60eede39c.jpg)

![a63a199ba6d1fe9e5eaa96da90c0355192801730668edf1e9a6d38ed1014b123.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/images/a63a199ba6d1fe9e5eaa96da90c0355192801730668edf1e9a6d38ed1014b123.jpg)

![ad539b0121a4e6bb6b3d17ecec8eeb851c08dc1d97839e06a199c674be2e7fd6.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/images/ad539b0121a4e6bb6b3d17ecec8eeb851c08dc1d97839e06a199c674be2e7fd6.jpg)

![cd87bb71d2add59a447c83664dbc4aaff69471a55ebb767fd5da4cf7f54460ac.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/images/cd87bb71d2add59a447c83664dbc4aaff69471a55ebb767fd5da4cf7f54460ac.jpg)

![de2117e2c560c7f45dc8bf5d97d1f82013f610a3f5943de810333f3eccc6773f.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/images/de2117e2c560c7f45dc8bf5d97d1f82013f610a3f5943de810333f3eccc6773f.jpg)

### Tables

![0fd37b177e1a970cfdb0e8e398c78990e9a53fc942e5d8b74bf3535b1c80d181.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/0fd37b177e1a970cfdb0e8e398c78990e9a53fc942e5d8b74bf3535b1c80d181.jpg)

![1c1755e4ad713dd9448aee9ec555946520495ffcfce18b96680118e6d3dc2a89.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/1c1755e4ad713dd9448aee9ec555946520495ffcfce18b96680118e6d3dc2a89.jpg)

![2b716f68a3fe4104ad9ca06aca540600145a330cd2eda9b39015ec275ace1ba4.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/2b716f68a3fe4104ad9ca06aca540600145a330cd2eda9b39015ec275ace1ba4.jpg)

![2fe3b6d0c5ae9e0875e9cec528794a41348b93ca2e9345ee54eddff138e9c73c.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/2fe3b6d0c5ae9e0875e9cec528794a41348b93ca2e9345ee54eddff138e9c73c.jpg)

![38a7ea1fcab5b73f58e60d237cf9d279a59c2ad59e4b03da33f5e3aa026a2566.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/38a7ea1fcab5b73f58e60d237cf9d279a59c2ad59e4b03da33f5e3aa026a2566.jpg)

![3dd29a234dcdacd7862128a2f1d810799c2222824f427484128d68e31e79c0b8.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/3dd29a234dcdacd7862128a2f1d810799c2222824f427484128d68e31e79c0b8.jpg)

![7416659f3a85d25e8ea44877b570807b5f27d8f119d4ab4a6e2a1b66b3a1be30.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/7416659f3a85d25e8ea44877b570807b5f27d8f119d4ab4a6e2a1b66b3a1be30.jpg)

![7fa48bc57e3cf5c5a190604533fc003ca55d983653126d8e68172cd7ff65cee7.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/7fa48bc57e3cf5c5a190604533fc003ca55d983653126d8e68172cd7ff65cee7.jpg)

![828cc996e283302df25f0b8fdb6ec7640ef04b6e069036f72334ab0ba6ab5734.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/828cc996e283302df25f0b8fdb6ec7640ef04b6e069036f72334ab0ba6ab5734.jpg)

![833b61ee6746a9e30c0d0a8c78f162f3a48be3556e0b9daae9429d8efa63303f.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/833b61ee6746a9e30c0d0a8c78f162f3a48be3556e0b9daae9429d8efa63303f.jpg)

![8d58c9565f4afa8febeb7998d961ec39d23322a562997b64e1254f47c18cddf6.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/8d58c9565f4afa8febeb7998d961ec39d23322a562997b64e1254f47c18cddf6.jpg)

![9a75da43c482d7af694f9e9f0af312f34663953892ee6d41969d632f63f714e5.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/9a75da43c482d7af694f9e9f0af312f34663953892ee6d41969d632f63f714e5.jpg)

![af58655251a62d1e37899ef273e3e0a3b26e1c91456cda340af9b34dcb6e8371.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/af58655251a62d1e37899ef273e3e0a3b26e1c91456cda340af9b34dcb6e8371.jpg)

![b8e6a2facf7719f5796f0995767ad18781ef36dae1e45b2a734138c5e7a5fdd7.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/b8e6a2facf7719f5796f0995767ad18781ef36dae1e45b2a734138c5e7a5fdd7.jpg)

![d15785e7acfd31e7647723814386ccdbbb53ad325ccaa9ea80daae33bc95b285.jpg](../nips_results/852_Model%20Inversion%20with%20Layer-Specific%20Modeling%20and%20Alignment%20for%20Data-Free%20Continual%20Learning/tables/d15785e7acfd31e7647723814386ccdbbb53ad325ccaa9ea80daae33bc95b285.jpg)

## Vulnerable Data-Aware Adversarial Training


### Images

![0570b49c0c9177ba03b915584e4b511b5af570b92af5ff0ae176b6a7458de0d3.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/images/0570b49c0c9177ba03b915584e4b511b5af570b92af5ff0ae176b6a7458de0d3.jpg)

![24eccface7ba3c06ee138f2111532c6f27a99489394908ee7a453edde00784d7.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/images/24eccface7ba3c06ee138f2111532c6f27a99489394908ee7a453edde00784d7.jpg)

![5344040ad45b7a4466d741560691e5d4185d85a16f079fe0566fb76c3208a29b.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/images/5344040ad45b7a4466d741560691e5d4185d85a16f079fe0566fb76c3208a29b.jpg)

![647d97482add255a919ffbbef4fd10b2812845f006c221067d5f5fdf438f9f67.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/images/647d97482add255a919ffbbef4fd10b2812845f006c221067d5f5fdf438f9f67.jpg)

![9d4266a8679cfc2dad4b39d2ab86f77515dddecdda8cb645077cdacf6d04a0f5.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/images/9d4266a8679cfc2dad4b39d2ab86f77515dddecdda8cb645077cdacf6d04a0f5.jpg)

![9e5f55c843d91cae1e850d1af5f2025d1193a56955abce7745f4566cb4e31081.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/images/9e5f55c843d91cae1e850d1af5f2025d1193a56955abce7745f4566cb4e31081.jpg)

![cc23de6786f979edebf15791581132664e125372c0d63104ea861d57655c4cee.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/images/cc23de6786f979edebf15791581132664e125372c0d63104ea861d57655c4cee.jpg)

![d9d0b83d43ed941ee6cdb867fcf6cd81e6eb91be8b52997b1244614b5e41ac46.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/images/d9d0b83d43ed941ee6cdb867fcf6cd81e6eb91be8b52997b1244614b5e41ac46.jpg)

![f4a27a827d1b4888983462e17676db9de1e7ad2d4fb8827d0358ff4ab77a8250.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/images/f4a27a827d1b4888983462e17676db9de1e7ad2d4fb8827d0358ff4ab77a8250.jpg)

### Tables

![005c71793c524fdf1d2970aa0dbd9e1824b070d36dfd97e3e75d35189470ce95.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/005c71793c524fdf1d2970aa0dbd9e1824b070d36dfd97e3e75d35189470ce95.jpg)

![0c8f55ea7578a1ea6d36c88d45351d049dfceec10fd7a3cf8060215f5161359b.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/0c8f55ea7578a1ea6d36c88d45351d049dfceec10fd7a3cf8060215f5161359b.jpg)

![2b0be38b2b9469617f034a39c4ac0e773f102ef5c3339f7482ce2dd784f68b15.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/2b0be38b2b9469617f034a39c4ac0e773f102ef5c3339f7482ce2dd784f68b15.jpg)

![391188ecf2824af910809bc3d7496f002e288226d4e460ff41c58aad4b9015ae.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/391188ecf2824af910809bc3d7496f002e288226d4e460ff41c58aad4b9015ae.jpg)

![546fc0c6da140fe7be0d9b5b8cd200e81bcb1f039ca60f693d29314614fac9dc.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/546fc0c6da140fe7be0d9b5b8cd200e81bcb1f039ca60f693d29314614fac9dc.jpg)

![5cf8dd339519bb31852810009494d6b4c286ba923e37798c403db9ad5a402551.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/5cf8dd339519bb31852810009494d6b4c286ba923e37798c403db9ad5a402551.jpg)

![64da17582938b48d066002666c738a3e7160028301df21c34e9778a443d715a4.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/64da17582938b48d066002666c738a3e7160028301df21c34e9778a443d715a4.jpg)

![6c1b39d36b8f790160f96705b5907734c3543366dde8e5c1d79d91ea30ba1d47.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/6c1b39d36b8f790160f96705b5907734c3543366dde8e5c1d79d91ea30ba1d47.jpg)

![73b133e5b42f73e12a832944fe108074a6b027581084b72b8a277d2e5494e622.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/73b133e5b42f73e12a832944fe108074a6b027581084b72b8a277d2e5494e622.jpg)

![77ab7c45a439958b8c0c3b44913fefa4fa73c822e62d6667ef6e4f92177b574f.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/77ab7c45a439958b8c0c3b44913fefa4fa73c822e62d6667ef6e4f92177b574f.jpg)

![8ba2bd90b7d0a4154074413612ee326bf64d2aea84854706049afa24a4cafc1e.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/8ba2bd90b7d0a4154074413612ee326bf64d2aea84854706049afa24a4cafc1e.jpg)

![94f0aec1d4ef334c3e2e4469d2cdeb9f62023f4d15452476eef9130a53043a7e.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/94f0aec1d4ef334c3e2e4469d2cdeb9f62023f4d15452476eef9130a53043a7e.jpg)

![99e074841f3c8181286772b6edd8c5244c3c68bc54c4e7c542d6d27c02555497.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/99e074841f3c8181286772b6edd8c5244c3c68bc54c4e7c542d6d27c02555497.jpg)

![9efe6c359285d04269f776aa451e81fbbd401a940ddb4789e75d3022758d4532.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/9efe6c359285d04269f776aa451e81fbbd401a940ddb4789e75d3022758d4532.jpg)

![9fa555f1b447bf9ef4097e2c551cb27337452a6041dee9aaeca4c5fa0bb9abbc.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/9fa555f1b447bf9ef4097e2c551cb27337452a6041dee9aaeca4c5fa0bb9abbc.jpg)

![b942ddd120a362071c32df17444613fc22c117025082f7c99796093dd498ccfa.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/b942ddd120a362071c32df17444613fc22c117025082f7c99796093dd498ccfa.jpg)

![d9c8c812f66615be284a5d22a06e459312b48ab6e1d8222d4fe6a40f0e03e778.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/d9c8c812f66615be284a5d22a06e459312b48ab6e1d8222d4fe6a40f0e03e778.jpg)

![e82fe209a2269018cef0b5871f94976eec1c8942b2a3df30f5d31ca72eba2bca.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/e82fe209a2269018cef0b5871f94976eec1c8942b2a3df30f5d31ca72eba2bca.jpg)

![ebbc7f05c738516143f515a59ed3284b786da4d32793141485c7978fcb7f4979.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/ebbc7f05c738516143f515a59ed3284b786da4d32793141485c7978fcb7f4979.jpg)

![edb126fa4fff318e863e49d12d3719070dd86e0706dee07da1441133d48a021c.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/edb126fa4fff318e863e49d12d3719070dd86e0706dee07da1441133d48a021c.jpg)

![eecbb04edadfc670d5e1048ed40398c4da8a06cef2ca56d4a5e887f601ef3ad5.jpg](../nips_results/853_Vulnerable%20Data-Aware%20Adversarial%20Training/tables/eecbb04edadfc670d5e1048ed40398c4da8a06cef2ca56d4a5e887f601ef3ad5.jpg)

## Personalized Subgraph Federated Learning with Differentiable Auxiliary Projections


### Images

![020f8a8ee8e3245889ea2cf7836bd8b108197497e2849b8abe9f9b38c5fb9f42.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/images/020f8a8ee8e3245889ea2cf7836bd8b108197497e2849b8abe9f9b38c5fb9f42.jpg)

![04795b6cd4c96f791d961c4cce7db23c5cc9d2fc66cd4ef6ea6c05e178cd026c.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/images/04795b6cd4c96f791d961c4cce7db23c5cc9d2fc66cd4ef6ea6c05e178cd026c.jpg)

![1bd6404ff2bab0d6bb5fe650cb31813f2b5c19befa757f44ae3c4211fc62acc7.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/images/1bd6404ff2bab0d6bb5fe650cb31813f2b5c19befa757f44ae3c4211fc62acc7.jpg)

![2f9cb5cab19626f585ac6aa3abb60d58bebd889a23dbf934f290d94a7b025d28.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/images/2f9cb5cab19626f585ac6aa3abb60d58bebd889a23dbf934f290d94a7b025d28.jpg)

![41d9515ac9f537e0b2ff96f1c4d6259cc708637471fe87138f14842a980440b6.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/images/41d9515ac9f537e0b2ff96f1c4d6259cc708637471fe87138f14842a980440b6.jpg)

![a2ed2371fa2bd435b2fe3db6c32f2f8b9c61c6aaeb7b84aec80c0cdf8fb98ae5.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/images/a2ed2371fa2bd435b2fe3db6c32f2f8b9c61c6aaeb7b84aec80c0cdf8fb98ae5.jpg)

![a4e508877ff7cd72f444803c5df2dcc41501ca63f7228930de23ff8bae2abb83.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/images/a4e508877ff7cd72f444803c5df2dcc41501ca63f7228930de23ff8bae2abb83.jpg)

![bad465f3a369e3a5234ff5e58cf0f42f5ed8db570b330261afa11ef801734dd9.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/images/bad465f3a369e3a5234ff5e58cf0f42f5ed8db570b330261afa11ef801734dd9.jpg)

### Tables

![05e345b3904d36057f7cfc59485ea7b7d1bbd13f2bce503abbdec3a753840976.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/tables/05e345b3904d36057f7cfc59485ea7b7d1bbd13f2bce503abbdec3a753840976.jpg)

![21f27a1d9dee4a6876d93cbda28c7ed27c5cbfa45da8a7284e9a8ebb478d7fa7.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/tables/21f27a1d9dee4a6876d93cbda28c7ed27c5cbfa45da8a7284e9a8ebb478d7fa7.jpg)

![2f46b84875d5c8502e2d82ec02b248fdc4e7829a15e8cc8e9dbce298789bdd29.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/tables/2f46b84875d5c8502e2d82ec02b248fdc4e7829a15e8cc8e9dbce298789bdd29.jpg)

![3c7c741fcf1475f493604df9f83663f5ff69894b8294b97e6ae45df335ff80f6.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/tables/3c7c741fcf1475f493604df9f83663f5ff69894b8294b97e6ae45df335ff80f6.jpg)

![45e67f84dab0fb7ad0f275277da83105e681d3da53a39b9114728f49929d8650.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/tables/45e67f84dab0fb7ad0f275277da83105e681d3da53a39b9114728f49929d8650.jpg)

![cbe4c45713502faead259bcbfeed867d41cba3b5792ac425a9fba0141a02f480.jpg](../nips_results/854_Personalized%20Subgraph%20Federated%20Learning%20with%20Differentiable%20Auxiliary%20Projections/tables/cbe4c45713502faead259bcbfeed867d41cba3b5792ac425a9fba0141a02f480.jpg)

## KTAE: A Model-Free Algorithm to Key-Tokens Advantage Estimation in Mathematical Reasoning


### Images

![023e550adbfe5e0385d61ed13167dc6a5249886b628680dcaccf615ce4276acb.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/images/023e550adbfe5e0385d61ed13167dc6a5249886b628680dcaccf615ce4276acb.jpg)

![36879cd2e0628702d1a0015ce12a326d063945483aaa37b178cd422cbeada93f.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/images/36879cd2e0628702d1a0015ce12a326d063945483aaa37b178cd422cbeada93f.jpg)

![36cf362fe0033728a130a5271d9b9950f6531d2cebc92e1a751a2e34545857e4.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/images/36cf362fe0033728a130a5271d9b9950f6531d2cebc92e1a751a2e34545857e4.jpg)

![3e668654c257140cf38ebd9bd638e959c536a3102071edc8f391d5329868087d.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/images/3e668654c257140cf38ebd9bd638e959c536a3102071edc8f391d5329868087d.jpg)

![7906a956e483320a2cb3fde2fc718f01891ff40a08d01b144a9e8c2fcddea03f.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/images/7906a956e483320a2cb3fde2fc718f01891ff40a08d01b144a9e8c2fcddea03f.jpg)

![9678dd0012011520251b47d965a2d9bcde72bde49c384d70ee8ab6d5c3a8a2d1.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/images/9678dd0012011520251b47d965a2d9bcde72bde49c384d70ee8ab6d5c3a8a2d1.jpg)

![9b6e78ef00aa1ecb0eb7315564b25f85277dce5ac49da53f7b99ff8e6f9aabac.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/images/9b6e78ef00aa1ecb0eb7315564b25f85277dce5ac49da53f7b99ff8e6f9aabac.jpg)

![beca06ac8794d3ecb814d7b03925298cd0c9d7ffa34be9fc20b267a7b8745156.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/images/beca06ac8794d3ecb814d7b03925298cd0c9d7ffa34be9fc20b267a7b8745156.jpg)

![d662b1186ef17b76f2b7952ee85a99190b9d36acbfb14848174fbf7c20e34083.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/images/d662b1186ef17b76f2b7952ee85a99190b9d36acbfb14848174fbf7c20e34083.jpg)

![f320ab56116b8eba02def2551d5c51bb66867b76471a09d70ee5772a2fef8446.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/images/f320ab56116b8eba02def2551d5c51bb66867b76471a09d70ee5772a2fef8446.jpg)

### Tables

![70c483308b0434cabca13ef8e4a235a960d02a7882090bda51e03cd5961fea37.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/tables/70c483308b0434cabca13ef8e4a235a960d02a7882090bda51e03cd5961fea37.jpg)

![d04443e13f56934d0f6faabe040822fe646e7e606a2e425b2a039298a835c605.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/tables/d04443e13f56934d0f6faabe040822fe646e7e606a2e425b2a039298a835c605.jpg)

![db165afec2c900bd78ebcd3c6d1fbdb8a43b3079217535e826b5b67cf2f3c293.jpg](../nips_results/855_KTAE_%20A%20Model-Free%20Algorithm%20to%20Key-Tokens%20Advantage%20Estimation%20in%20Mathematical%20Reasoning/tables/db165afec2c900bd78ebcd3c6d1fbdb8a43b3079217535e826b5b67cf2f3c293.jpg)

## MotionRAG: Motion Retrieval-Augmented Image-to-Video Generation


### Images

![1c7f6478e24f608e2cb7963b33d04dec3b7f2d45f92ac0684bea5b1c84947321.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/images/1c7f6478e24f608e2cb7963b33d04dec3b7f2d45f92ac0684bea5b1c84947321.jpg)

![537a2d3d41c7cc357186138c284cb70a452c21db3b3e43c23d1d3c6a382c0789.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/images/537a2d3d41c7cc357186138c284cb70a452c21db3b3e43c23d1d3c6a382c0789.jpg)

![5d63b7f597e368cee46e222479d262873b0bb244d9fdbc994e596b49bd7fe100.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/images/5d63b7f597e368cee46e222479d262873b0bb244d9fdbc994e596b49bd7fe100.jpg)

![b703d133c7cd9a93d8ca6917a5c277b37c195429706326b23c8b4b0d800c97bb.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/images/b703d133c7cd9a93d8ca6917a5c277b37c195429706326b23c8b4b0d800c97bb.jpg)

![bc8916f58e1871fbdf3c327e31cd704a150d60f964e47b03eced64b28195accf.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/images/bc8916f58e1871fbdf3c327e31cd704a150d60f964e47b03eced64b28195accf.jpg)

![e07d8db543756b8dba84e3afe0b7f5c97a33d8ae6cf37ae5fd234e10da64fddc.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/images/e07d8db543756b8dba84e3afe0b7f5c97a33d8ae6cf37ae5fd234e10da64fddc.jpg)

### Tables

![252b67bd145191c210b27082313e579bd978f433d6c67be26c7e8bf4189a4340.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/tables/252b67bd145191c210b27082313e579bd978f433d6c67be26c7e8bf4189a4340.jpg)

![2f509e512e28700125b379f6a2271b7c984dcc5a98ee17dee3d8f938c2921fbc.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/tables/2f509e512e28700125b379f6a2271b7c984dcc5a98ee17dee3d8f938c2921fbc.jpg)

![34e6b388538ae9c4616134f20244fda93fe62d71a6268720f3a378b8e200424e.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/tables/34e6b388538ae9c4616134f20244fda93fe62d71a6268720f3a378b8e200424e.jpg)

![56a4b91789168c48d80767e241f16407fe55c2e876ba70b455de1cb8bc3f6d1c.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/tables/56a4b91789168c48d80767e241f16407fe55c2e876ba70b455de1cb8bc3f6d1c.jpg)

![5e2801ea2501db1b1b44c7e55c1a458651737c22e5d073c89ceb2263d7fd6250.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/tables/5e2801ea2501db1b1b44c7e55c1a458651737c22e5d073c89ceb2263d7fd6250.jpg)

![6f95aa4a202f22a473b60087abca0d86760c0181bbcbeeb44fe4658aa5965cf5.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/tables/6f95aa4a202f22a473b60087abca0d86760c0181bbcbeeb44fe4658aa5965cf5.jpg)

![84be7bb79a16e7f4b5c8013749d949f303d7bc2d58c9b59621d1b0589d26f023.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/tables/84be7bb79a16e7f4b5c8013749d949f303d7bc2d58c9b59621d1b0589d26f023.jpg)

![b09b022149634cf28df49beb5ce84cc3959e0e5b895cfcd04416a7c5e8404b6f.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/tables/b09b022149634cf28df49beb5ce84cc3959e0e5b895cfcd04416a7c5e8404b6f.jpg)

![bdface27446a37447c4a9afdfb034647bbbac457a313b642fbb92ec0c828f6f2.jpg](../nips_results/856_MotionRAG_%20Motion%20Retrieval-Augmented%20Image-to-Video%20Generation/tables/bdface27446a37447c4a9afdfb034647bbbac457a313b642fbb92ec0c828f6f2.jpg)

## Hierarchical Semantic-Augmented Navigation: Optimal Transport and Graph-Driven Reasoning for Vision-Language Navigation


### Images

![6aa9f7791364a547cead2d2b8b4b674aad7b98212963f3c57de7bc0ab3814b9b.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/images/6aa9f7791364a547cead2d2b8b4b674aad7b98212963f3c57de7bc0ab3814b9b.jpg)

![85e89152019c822f73b9b1e832b709d0950436de7245f019ebf190e3054d8892.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/images/85e89152019c822f73b9b1e832b709d0950436de7245f019ebf190e3054d8892.jpg)

![9ae85ff8ac71079a9a4fcdc1a883b0bc2570ddf03c833ee3dd60c6686ef41615.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/images/9ae85ff8ac71079a9a4fcdc1a883b0bc2570ddf03c833ee3dd60c6686ef41615.jpg)

![e2fce7fcc159a0af5496b471771b0088f2ecf0f2c239b3e6ca03f7553bbf3fa6.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/images/e2fce7fcc159a0af5496b471771b0088f2ecf0f2c239b3e6ca03f7553bbf3fa6.jpg)

### Tables

![20dbf71ec038b2ca774158e48b5aa5b80c1b01a094c9791f93ad98ab29121200.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/20dbf71ec038b2ca774158e48b5aa5b80c1b01a094c9791f93ad98ab29121200.jpg)

![2191418ca7aaad5a8fce6f05ec7a728319d899e6f9adfcac0455d8df35ab3a33.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/2191418ca7aaad5a8fce6f05ec7a728319d899e6f9adfcac0455d8df35ab3a33.jpg)

![2544dcc8f9cc6102b17a1c5e02367cb9a489da43703097d69ecc953bb8016388.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/2544dcc8f9cc6102b17a1c5e02367cb9a489da43703097d69ecc953bb8016388.jpg)

![378fc4fb5e76dee64662a132686905b7e1964a25e3775b11793da983c37eac14.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/378fc4fb5e76dee64662a132686905b7e1964a25e3775b11793da983c37eac14.jpg)

![467bb436c76f1418f5d0a02233a4e6d7324fc027ab7ad5435366f74f6bdf6930.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/467bb436c76f1418f5d0a02233a4e6d7324fc027ab7ad5435366f74f6bdf6930.jpg)

![4e6ed5fa937238919bb0060205f8680ecea8b25eb5c3ebd02a1819f2e9798702.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/4e6ed5fa937238919bb0060205f8680ecea8b25eb5c3ebd02a1819f2e9798702.jpg)

![56dc0d75f87ff752b7e8d20e27414572832c166d3c8e1cc54cf06d045fccfd62.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/56dc0d75f87ff752b7e8d20e27414572832c166d3c8e1cc54cf06d045fccfd62.jpg)

![722cc7c3d238f54cf2191648c4cdc82d80438e380a38b508f0b35ddecbcbd831.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/722cc7c3d238f54cf2191648c4cdc82d80438e380a38b508f0b35ddecbcbd831.jpg)

![79a1d73df1d7ec10d2de9eefa20510be32ca0b0284831ebdc35c5586734e29d3.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/79a1d73df1d7ec10d2de9eefa20510be32ca0b0284831ebdc35c5586734e29d3.jpg)

![7c10d0a274fe1fd101c5d45d3b21d396d7a5bb04f2ca6444c1dd3da5c90041fc.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/7c10d0a274fe1fd101c5d45d3b21d396d7a5bb04f2ca6444c1dd3da5c90041fc.jpg)

![88a3bd857a933de25ab82402e44a09ad26b8ee38fdced27e6dc683b3c3e26b9a.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/88a3bd857a933de25ab82402e44a09ad26b8ee38fdced27e6dc683b3c3e26b9a.jpg)

![8f2284fb7d76236de80fd909f87d9dbeee87ce9a3b21886e56c69b1bdfd29cf6.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/8f2284fb7d76236de80fd909f87d9dbeee87ce9a3b21886e56c69b1bdfd29cf6.jpg)

![94fe4017d664f09fc02f5ce605b18a8a9462d62b773ff05d6103b72c4b48773b.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/94fe4017d664f09fc02f5ce605b18a8a9462d62b773ff05d6103b72c4b48773b.jpg)

![9bc2ff24b0477952b6a180c9fbe3a5d3d9ff5ad0d3e5fc202a290571adb8f5d5.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/9bc2ff24b0477952b6a180c9fbe3a5d3d9ff5ad0d3e5fc202a290571adb8f5d5.jpg)

![a62a86df61274ff0051b55d0f5b86d48c3f9e0a54ae349d11e1776335c18129a.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/a62a86df61274ff0051b55d0f5b86d48c3f9e0a54ae349d11e1776335c18129a.jpg)

![a75e8f831c0330e938584fb56643837a328d50798b8ea3a4a24cdc17c4d2497d.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/a75e8f831c0330e938584fb56643837a328d50798b8ea3a4a24cdc17c4d2497d.jpg)

![a8969737fadc1a0fb3a20d5a7962a305ca5fa35d9df7f9c423c1749709d472c6.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/a8969737fadc1a0fb3a20d5a7962a305ca5fa35d9df7f9c423c1749709d472c6.jpg)

![e0ea91938e644648de1f9894ed5d1c9ecb8ea2ae2631cc5fb737bf7a597280a4.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/e0ea91938e644648de1f9894ed5d1c9ecb8ea2ae2631cc5fb737bf7a597280a4.jpg)

![ff3358d9341259f3a1ad41b8ba7ab132ddcee564673c1762613d63bc20903a30.jpg](../nips_results/857_Hierarchical%20Semantic-Augmented%20Navigation_%20Optimal%20Transport%20and%20Graph-Driven%20Reasoning%20for%20Vision-/tables/ff3358d9341259f3a1ad41b8ba7ab132ddcee564673c1762613d63bc20903a30.jpg)

## DCA: Graph-Guided Deep Embedding Clustering for Brain Atlases


### Images

![06c5896606c2b858698ab636df6801d8d686ec9689078a927c8fe4fb2bfe1bc9.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/06c5896606c2b858698ab636df6801d8d686ec9689078a927c8fe4fb2bfe1bc9.jpg)

![21e013bbfd79f199f24ada217adb408e21390238271f63268ede5c280af3a7be.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/21e013bbfd79f199f24ada217adb408e21390238271f63268ede5c280af3a7be.jpg)

![38c80dfd36a5263d0dd176e0ce5112475e94606c1aa959480b9eee72aeb7c041.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/38c80dfd36a5263d0dd176e0ce5112475e94606c1aa959480b9eee72aeb7c041.jpg)

![52e7903d63fc807f5eb1259e67edb023594e1fea4093172123d3e20e868a05f0.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/52e7903d63fc807f5eb1259e67edb023594e1fea4093172123d3e20e868a05f0.jpg)

![5c5f5e034f2cdc5c1b52c8147422bef36361796b98fc998f28569270b3b73142.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/5c5f5e034f2cdc5c1b52c8147422bef36361796b98fc998f28569270b3b73142.jpg)

![6617f9740a54dd6b1cf13594ad20a07285774e2fa4d8182a5cf8df2880d15e25.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/6617f9740a54dd6b1cf13594ad20a07285774e2fa4d8182a5cf8df2880d15e25.jpg)

![7129ad7a4c5414bac5f9c0ce1241cd9bfed897fc4cf9ff05582dffadbce71cad.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/7129ad7a4c5414bac5f9c0ce1241cd9bfed897fc4cf9ff05582dffadbce71cad.jpg)

![7644934482ee544fb29fa440a1935cd3b790dd2471569ab4576b1db5b1527640.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/7644934482ee544fb29fa440a1935cd3b790dd2471569ab4576b1db5b1527640.jpg)

![9d84f6eb5bdc2c3c7acbdfa1d8a3a24188ba297d2e1b721c819cfd76be512daa.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/9d84f6eb5bdc2c3c7acbdfa1d8a3a24188ba297d2e1b721c819cfd76be512daa.jpg)

![ae13720bf0602e14947bf7b41a6f5b1ed659faf135068a08aad42956d525103f.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/ae13720bf0602e14947bf7b41a6f5b1ed659faf135068a08aad42956d525103f.jpg)

![b6d3e82384df5f5c3a1bed9e75790dec1e3430bd46a38764d34e29e2e534d17b.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/b6d3e82384df5f5c3a1bed9e75790dec1e3430bd46a38764d34e29e2e534d17b.jpg)

![cfbc92a96d3a02570b7286e62024a8fa409a67057c15461942e30268e5713caa.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/images/cfbc92a96d3a02570b7286e62024a8fa409a67057c15461942e30268e5713caa.jpg)

### Tables

![0da89b130eb527387c9d59afe5f013334ee93d72e8ce21edb7b4459e1e01891f.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/0da89b130eb527387c9d59afe5f013334ee93d72e8ce21edb7b4459e1e01891f.jpg)

![0dda3cc8924ac16a6296bf092de8c1e00eb6004481294309424d225bb26dbef8.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/0dda3cc8924ac16a6296bf092de8c1e00eb6004481294309424d225bb26dbef8.jpg)

![29a2fae1ac7bde326e3148882eb0fd8a0324cec3a5e7e12f1b41b20a44020736.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/29a2fae1ac7bde326e3148882eb0fd8a0324cec3a5e7e12f1b41b20a44020736.jpg)

![2cbff53d88688f97effa007e54128dd37405a6d1b044750175e62943a5fc66cd.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/2cbff53d88688f97effa007e54128dd37405a6d1b044750175e62943a5fc66cd.jpg)

![5eb8fc66b1d40586c660c6eaa5e6d8b938e2b993d469f63b5cbec7b1ff2d7461.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/5eb8fc66b1d40586c660c6eaa5e6d8b938e2b993d469f63b5cbec7b1ff2d7461.jpg)

![6376fb80452da61e347cd666e9074b92d281e5d3827239c0ed00ca9f3a1ad74d.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/6376fb80452da61e347cd666e9074b92d281e5d3827239c0ed00ca9f3a1ad74d.jpg)

![6deed313c82d780db2b80ad27255b2b8f7ccd394f4fc40833b897a8c88a9d301.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/6deed313c82d780db2b80ad27255b2b8f7ccd394f4fc40833b897a8c88a9d301.jpg)

![6f708afb05ac5b1fd4776bc6b36cd23e33fc709ddf0eb989302c341ad3b50645.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/6f708afb05ac5b1fd4776bc6b36cd23e33fc709ddf0eb989302c341ad3b50645.jpg)

![75044309d0f3f4b76d1ee48290a57f351afbe606bb1dceb24824c363449296b5.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/75044309d0f3f4b76d1ee48290a57f351afbe606bb1dceb24824c363449296b5.jpg)

![756102b1248046db0b4e6fcd268580f4b94788cbcf984768665b279f1f8b15d9.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/756102b1248046db0b4e6fcd268580f4b94788cbcf984768665b279f1f8b15d9.jpg)

![82eda13884d52099669fc6606158181ea8979c3734a8bc1f1875205d10032336.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/82eda13884d52099669fc6606158181ea8979c3734a8bc1f1875205d10032336.jpg)

![84a1fb67fd0def907ed6429a2431864fce8e20a2a71f03353f84fc910ffee34d.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/84a1fb67fd0def907ed6429a2431864fce8e20a2a71f03353f84fc910ffee34d.jpg)

![9f67183a135eafd7b1c116be54a746773dedd8a634c39801030b67cc79c15122.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/9f67183a135eafd7b1c116be54a746773dedd8a634c39801030b67cc79c15122.jpg)

![a88963de093727d3822efbcfb2017698fac2a01db10199f02f05d74789efce99.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/a88963de093727d3822efbcfb2017698fac2a01db10199f02f05d74789efce99.jpg)

![b3c4a77fa9353adfe6f7ed2c35c5d6ba97a738ca972298311124bb14508a1620.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/b3c4a77fa9353adfe6f7ed2c35c5d6ba97a738ca972298311124bb14508a1620.jpg)

![bcfd2c3e1dd70c9bfd2313404dffa2a7b8b99533f9c72587843c762788026719.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/bcfd2c3e1dd70c9bfd2313404dffa2a7b8b99533f9c72587843c762788026719.jpg)

![c832bff815fd89ae009b74017991e5f6be24d5e7cbee60d45a819627f3b95cc3.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/c832bff815fd89ae009b74017991e5f6be24d5e7cbee60d45a819627f3b95cc3.jpg)

![c8d6474b60bded55c07a0b62ee16fc8b5fd2f28416f4d6e695244f9dd2930f32.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/c8d6474b60bded55c07a0b62ee16fc8b5fd2f28416f4d6e695244f9dd2930f32.jpg)

![cf3a77f4794672b7b632571e51585b0da1f35da6927b31d4bbd392a65e897494.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/cf3a77f4794672b7b632571e51585b0da1f35da6927b31d4bbd392a65e897494.jpg)

![d2da1b5a486386d496fab60e9f840a66375f4de5cf118b795519b5885bed4f2c.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/d2da1b5a486386d496fab60e9f840a66375f4de5cf118b795519b5885bed4f2c.jpg)

![dba6e74263ad17f59d34e4b1395c5facb7721bf1d8ed155603a2982d68825985.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/dba6e74263ad17f59d34e4b1395c5facb7721bf1d8ed155603a2982d68825985.jpg)

![ea0799656bcaa7785f30d21c6524e54e63bbdb7630fb346c46e38e2c4b696bc1.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/ea0799656bcaa7785f30d21c6524e54e63bbdb7630fb346c46e38e2c4b696bc1.jpg)

![f0aa7ec2a8c40d18a588e76438e8ead38aa61770452c75d8a7a00134b2814a87.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/f0aa7ec2a8c40d18a588e76438e8ead38aa61770452c75d8a7a00134b2814a87.jpg)

![fab6088d6361d6f4a5d190ba75be68202efe0ef9d179b8f25aa20c9439d39433.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/fab6088d6361d6f4a5d190ba75be68202efe0ef9d179b8f25aa20c9439d39433.jpg)

![ffb688d6816ac08ab26f1410149f3efeeebcdc295e148a7e2f01199ca9a958a2.jpg](../nips_results/858_DCA_%20Graph-Guided%20Deep%20Embedding%20Clustering%20for%20Brain%20Atlases/tables/ffb688d6816ac08ab26f1410149f3efeeebcdc295e148a7e2f01199ca9a958a2.jpg)

## Learning Human-Object Interaction as Groups


### Images

![132c03c4fa2948111d1d27621880e83046e07239981df2e4a04b1dd3a53417d0.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/images/132c03c4fa2948111d1d27621880e83046e07239981df2e4a04b1dd3a53417d0.jpg)

![35e22e0ee0fda98333c9e5c0ce0f4d5b9309a3e70fe5b400743082796bced475.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/images/35e22e0ee0fda98333c9e5c0ce0f4d5b9309a3e70fe5b400743082796bced475.jpg)

![3d25ff8d3994625dafa814535c9ff3db48df092f7d14d404ae98eee07f9e5042.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/images/3d25ff8d3994625dafa814535c9ff3db48df092f7d14d404ae98eee07f9e5042.jpg)

![4d92c90aec0f4e7e0ea2a71659e48ddc0f8f4f671bc68a747b2b22222907270a.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/images/4d92c90aec0f4e7e0ea2a71659e48ddc0f8f4f671bc68a747b2b22222907270a.jpg)

![f9dfb6d4a569c571a10e203ce7838881a1a41dfea5374702a48e483606611bff.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/images/f9dfb6d4a569c571a10e203ce7838881a1a41dfea5374702a48e483606611bff.jpg)

### Tables

![1c9ec726539d6d44e1dfc191120c4208e941efc07045588061dd300a327ed55b.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/tables/1c9ec726539d6d44e1dfc191120c4208e941efc07045588061dd300a327ed55b.jpg)

![398a39dfba3a5fedd4bdc6d6786cd1545031eabededf2ab398f991533dd06a8f.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/tables/398a39dfba3a5fedd4bdc6d6786cd1545031eabededf2ab398f991533dd06a8f.jpg)

![68570aeecc91c484aa13995b1a1aa9d2f4cb0ebbfa1860e5d3b0d98b2da6effc.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/tables/68570aeecc91c484aa13995b1a1aa9d2f4cb0ebbfa1860e5d3b0d98b2da6effc.jpg)

![6d0c327dc17a4434cf0de28bfdc717d2d7ddff2647c4b94fc4cac9dc50b24a85.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/tables/6d0c327dc17a4434cf0de28bfdc717d2d7ddff2647c4b94fc4cac9dc50b24a85.jpg)

![6d0f3e5d7626158e3418297b0616934dfe5ca5d7da586341d42b6df286159ae4.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/tables/6d0f3e5d7626158e3418297b0616934dfe5ca5d7da586341d42b6df286159ae4.jpg)

![af50ae2b4e1aba787d46ea263ceacc050cc134404560885857bb4fa87e51a5c8.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/tables/af50ae2b4e1aba787d46ea263ceacc050cc134404560885857bb4fa87e51a5c8.jpg)

![c4c0ac1f4fd38896c5d62efac51eb96fe8783e61429f32c2e1230bb09ac0fb57.jpg](../nips_results/859_Learning%20Human-Object%20Interaction%20as%20Groups/tables/c4c0ac1f4fd38896c5d62efac51eb96fe8783e61429f32c2e1230bb09ac0fb57.jpg)

## Spectral Analysis of Diffusion Models with Application to Schedule Design


### Images

![00dd2cff73b4259161404ac0c702d6bbee6aded629df91df09433daaea6bcf3b.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/00dd2cff73b4259161404ac0c702d6bbee6aded629df91df09433daaea6bcf3b.jpg)

![059fa08bb361a00bab9c142ac22745a323c7a2f61bbc68d1a598dfda58da29fd.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/059fa08bb361a00bab9c142ac22745a323c7a2f61bbc68d1a598dfda58da29fd.jpg)

![0f911bf028a05680214f23d7e36fc3e49181e6eb4f39b7d428e40dd6ce85b7db.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/0f911bf028a05680214f23d7e36fc3e49181e6eb4f39b7d428e40dd6ce85b7db.jpg)

![118bdfffaab876f681b06001796b425ecbcc353e546c992846844a24603e6570.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/118bdfffaab876f681b06001796b425ecbcc353e546c992846844a24603e6570.jpg)

![11eab26c786ad15d65f73cb3b0191bd40e58c72dd240dd3b0234aaabe05850af.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/11eab26c786ad15d65f73cb3b0191bd40e58c72dd240dd3b0234aaabe05850af.jpg)

![266e17bc3d4324c773d968302bad8a0a59eb70b9606ccc675a32376f45e5df3d.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/266e17bc3d4324c773d968302bad8a0a59eb70b9606ccc675a32376f45e5df3d.jpg)

![30805a37c088c89085e095602a39665c561cc59c467b722648bb94391a812f27.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/30805a37c088c89085e095602a39665c561cc59c467b722648bb94391a812f27.jpg)

![4665d06ef47909c5e0c090e750fad34dc0349f83d48607a86d6336f745fd3b1b.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/4665d06ef47909c5e0c090e750fad34dc0349f83d48607a86d6336f745fd3b1b.jpg)

![4a25e26de6e28fadecc14ec9d61f0002faf5db3d3b5fc812cf439f2ab39b7133.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/4a25e26de6e28fadecc14ec9d61f0002faf5db3d3b5fc812cf439f2ab39b7133.jpg)

![571c5e7eb85ed16f150fd942640c2ff6cae38b0059ebd132dfc9382d0519e983.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/571c5e7eb85ed16f150fd942640c2ff6cae38b0059ebd132dfc9382d0519e983.jpg)

![618ee69ff2d12474c6282672b42f500d0733f9850d81dc6ef6360d0b6c359475.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/618ee69ff2d12474c6282672b42f500d0733f9850d81dc6ef6360d0b6c359475.jpg)

![6b2298e9e72624ccea29828c7c1d3e2dee57c97984447b82956639c457f3fc49.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/6b2298e9e72624ccea29828c7c1d3e2dee57c97984447b82956639c457f3fc49.jpg)

![93ca6d11b6d0490ae349b0183bf4d0c3029e46a601f5d839ef1611273ec5c9ac.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/93ca6d11b6d0490ae349b0183bf4d0c3029e46a601f5d839ef1611273ec5c9ac.jpg)

![970b5718a4e7069bbd5b7dd60ddfd72e38ac482e56d828eb8f6a36a2802a7be0.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/970b5718a4e7069bbd5b7dd60ddfd72e38ac482e56d828eb8f6a36a2802a7be0.jpg)

![9bd49686c7d7091a5f8d773b13bb7e0a46f250669ba9a6d398d5810e1bd27334.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/9bd49686c7d7091a5f8d773b13bb7e0a46f250669ba9a6d398d5810e1bd27334.jpg)

![9e92fe2fe4e203c502fdb75331eef55b732b801bcf0f90b11d374f6bd5f41a6e.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/9e92fe2fe4e203c502fdb75331eef55b732b801bcf0f90b11d374f6bd5f41a6e.jpg)

![a135185157e4aee0b701209cbd0cd5f5c1f2a9009d9b4eee2e7bc4f76f0bd601.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/a135185157e4aee0b701209cbd0cd5f5c1f2a9009d9b4eee2e7bc4f76f0bd601.jpg)

![a811b70a8ac054c9886b24869105559f9e8f49fada9b54fe9a11663f5e7dab03.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/a811b70a8ac054c9886b24869105559f9e8f49fada9b54fe9a11663f5e7dab03.jpg)

![a9a41e9486ba20482c688e0b5836a25f3460cc0ea3d46e401c826c666b06e81e.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/a9a41e9486ba20482c688e0b5836a25f3460cc0ea3d46e401c826c666b06e81e.jpg)

![a9c57d079bc10093e3afbf660b9cd6f9ace13dd54ed620074e104208bc38a16b.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/a9c57d079bc10093e3afbf660b9cd6f9ace13dd54ed620074e104208bc38a16b.jpg)

![ad21b5872e7603560951ca4a9cbaa56c89076fcfdffc4192688f0c922c9d615c.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/ad21b5872e7603560951ca4a9cbaa56c89076fcfdffc4192688f0c922c9d615c.jpg)

![bb8c8c4836825b8bbc4fbf5281485745e2b8e7c2f920b4dfac9d6b7f4ef23c25.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/bb8c8c4836825b8bbc4fbf5281485745e2b8e7c2f920b4dfac9d6b7f4ef23c25.jpg)

![bd9dfe5e39ace15b35f94ff46dc87eeaae86e02766754909d41720c62970254b.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/bd9dfe5e39ace15b35f94ff46dc87eeaae86e02766754909d41720c62970254b.jpg)

![c524297258415cd4c46e38c9f701434e628dbf3f7b1948222a293dceff94a4e2.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/c524297258415cd4c46e38c9f701434e628dbf3f7b1948222a293dceff94a4e2.jpg)

![cc3d9e6243cbdf33c1f1809d62f97af00d15d1c3e0454f2b77127533a17f3481.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/cc3d9e6243cbdf33c1f1809d62f97af00d15d1c3e0454f2b77127533a17f3481.jpg)

![cddf8d0d4122a0b0f2f5fc55e55112dfa4949ef0ef39e861ea1263f18b1ecceb.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/cddf8d0d4122a0b0f2f5fc55e55112dfa4949ef0ef39e861ea1263f18b1ecceb.jpg)

![e8059dc2fcdec904a972aa18e3d30e61cd8a92f6eba878e86f0fa7b8cc7b95ff.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/e8059dc2fcdec904a972aa18e3d30e61cd8a92f6eba878e86f0fa7b8cc7b95ff.jpg)

![ec2b3a392eea3f9d55c9658e4bb294ebdae3190aab93bfa0068408ba0e5fdd09.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/ec2b3a392eea3f9d55c9658e4bb294ebdae3190aab93bfa0068408ba0e5fdd09.jpg)

![f66110ec9a799fe4a02828768cf93f74cb6ced6fd1bd8de894ddb79a452ff123.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/f66110ec9a799fe4a02828768cf93f74cb6ced6fd1bd8de894ddb79a452ff123.jpg)

![f7181d56c1727f30ddad433755a07e33387e9788b0fe4a526736949097ff540a.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/f7181d56c1727f30ddad433755a07e33387e9788b0fe4a526736949097ff540a.jpg)

![fbe2d97231a5bee6bbd8d65663bdeb5630b62cdf6afa4015ed675e9d1f1c695b.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/images/fbe2d97231a5bee6bbd8d65663bdeb5630b62cdf6afa4015ed675e9d1f1c695b.jpg)

### Tables

![30c4fb990bff996e29be51cb996cbe4fe8e465744b7f2d7687abb6c5e072ad39.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/tables/30c4fb990bff996e29be51cb996cbe4fe8e465744b7f2d7687abb6c5e072ad39.jpg)

![40df0fd93b1a76cc7c681a268bc391d523991852007232cad501654723a62d4b.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/tables/40df0fd93b1a76cc7c681a268bc391d523991852007232cad501654723a62d4b.jpg)

![c2839d701e52fd55d8a410b80759e7a76bbadac61a9b985a37dbb5ad91d989d8.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/tables/c2839d701e52fd55d8a410b80759e7a76bbadac61a9b985a37dbb5ad91d989d8.jpg)

![f122c383b94ab4eafa3e7c95403bda6dd05d563df3a93e1ce1d1e4811924d72f.jpg](../nips_results/860_Spectral%20Analysis%20of%20Diffusion%20Models%20with%20Application%20to%20Schedule%20Design/tables/f122c383b94ab4eafa3e7c95403bda6dd05d563df3a93e1ce1d1e4811924d72f.jpg)

## Interpretable and Parameter Efficient Graph Neural Additive Models with Random Fourier Features


### Images

![1259d29dabec0f502cd2c00ddd417964fc90770001c6df48feb7cce7e8317a55.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/images/1259d29dabec0f502cd2c00ddd417964fc90770001c6df48feb7cce7e8317a55.jpg)

![199769e2b6ee156358c360168821caa9a73b5dd6aa2438f6807c8e26ffd116d5.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/images/199769e2b6ee156358c360168821caa9a73b5dd6aa2438f6807c8e26ffd116d5.jpg)

![22446d6cbb8c359ece63cf26c980c5b959a2405207c3638dfbe456b2e6eaffce.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/images/22446d6cbb8c359ece63cf26c980c5b959a2405207c3638dfbe456b2e6eaffce.jpg)

![3217634d632292b36b6845608ebf2f9dcd71577303d107edd35d40b3d7f5b459.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/images/3217634d632292b36b6845608ebf2f9dcd71577303d107edd35d40b3d7f5b459.jpg)

![334363a9355e873312efc31e5958d444a4d53ece0fe5d933e16a63712da319d1.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/images/334363a9355e873312efc31e5958d444a4d53ece0fe5d933e16a63712da319d1.jpg)

![665926c850f8b1a04f3d17a8dcc3c7ddc318a42cf53f33f217d6720c44147cc0.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/images/665926c850f8b1a04f3d17a8dcc3c7ddc318a42cf53f33f217d6720c44147cc0.jpg)

![82a3a38ee9e74b13a18635bd2710e0229c620efb2449c807a64bee7a54c3f936.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/images/82a3a38ee9e74b13a18635bd2710e0229c620efb2449c807a64bee7a54c3f936.jpg)

![9a65d98aa54cb887b55d4a51d76f3afe23df5f552b13b1ea5850782617772118.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/images/9a65d98aa54cb887b55d4a51d76f3afe23df5f552b13b1ea5850782617772118.jpg)

![b04bc4ec5476fcb92f267a551d68bad89b2196bdd404f0bc9e019cc49a3e38cd.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/images/b04bc4ec5476fcb92f267a551d68bad89b2196bdd404f0bc9e019cc49a3e38cd.jpg)

![ef54f717711e23eb84fbf85e377a716a2be23ac307779dfbd4368e518ed351ee.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/images/ef54f717711e23eb84fbf85e377a716a2be23ac307779dfbd4368e518ed351ee.jpg)

### Tables

![267017cf2296e49dbf9389626c503522d8b8896cb7fa636e7722cdd0939cd589.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/tables/267017cf2296e49dbf9389626c503522d8b8896cb7fa636e7722cdd0939cd589.jpg)

![49fcb3457372095e9e9435fabdfa077b8eb959ea233d671d3aef3f96e7fb59b9.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/tables/49fcb3457372095e9e9435fabdfa077b8eb959ea233d671d3aef3f96e7fb59b9.jpg)

![810365da825ee810127ab2694487c3b70c8a44336bd386d6096fa160461deb8c.jpg](../nips_results/861_Interpretable%20and%20Parameter%20Efficient%20Graph%20Neural%20Additive%20Models%20with%20Random%20Fourier%20Features/tables/810365da825ee810127ab2694487c3b70c8a44336bd386d6096fa160461deb8c.jpg)

## Predictive Coding Enhances Meta-RL To Achieve Interpretable Bayes-Optimal Belief Representation Under Partial Observability


### Images

![1304f8040d55740139ddf25adbf6e6a46b3a12d12a3059c59779962d5564545c.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/1304f8040d55740139ddf25adbf6e6a46b3a12d12a3059c59779962d5564545c.jpg)

![13a83aa07424f3010bb85d8571344f077dff5c240c1cafcb96bea75752afbe23.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/13a83aa07424f3010bb85d8571344f077dff5c240c1cafcb96bea75752afbe23.jpg)

![4ac1a241f0b24e588fd2dc2799a06ec95872ac02939bd64b022402831aef8d42.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/4ac1a241f0b24e588fd2dc2799a06ec95872ac02939bd64b022402831aef8d42.jpg)

![4f8ef27514066165cee0e7e84672fd9f994ba2d5e0e07c897cd5de12f09dadbb.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/4f8ef27514066165cee0e7e84672fd9f994ba2d5e0e07c897cd5de12f09dadbb.jpg)

![7224e9bce967acb6e8960081582856f3594da8523b90554e507d286f669e900b.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/7224e9bce967acb6e8960081582856f3594da8523b90554e507d286f669e900b.jpg)

![91cf01920d1363a30deb2f29f692747349e4cede7abca60b6985607ab28ba512.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/91cf01920d1363a30deb2f29f692747349e4cede7abca60b6985607ab28ba512.jpg)

![9cd0dc3b18c824a4f9fd858f9a693c84e2b33a78eebbdc256b750e711e5af944.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/9cd0dc3b18c824a4f9fd858f9a693c84e2b33a78eebbdc256b750e711e5af944.jpg)

![b0925156d2ca97fe5837a691e9f9287e9f36a35b78d5a5df6b129b67becb1395.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/b0925156d2ca97fe5837a691e9f9287e9f36a35b78d5a5df6b129b67becb1395.jpg)

![b161ea4ed8a81ac41cec38a6bfa89a61f4d79487f5f9820b0a9b04335ca76f43.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/b161ea4ed8a81ac41cec38a6bfa89a61f4d79487f5f9820b0a9b04335ca76f43.jpg)

![cc3f14019267a33e29a7b0804bec4c83f501e047f8eff7d738555a57862d5238.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/cc3f14019267a33e29a7b0804bec4c83f501e047f8eff7d738555a57862d5238.jpg)

![cc89b0312dfca962e378f316cec4fcce0a6aa68c2fe91011f610178fb1fecd29.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/cc89b0312dfca962e378f316cec4fcce0a6aa68c2fe91011f610178fb1fecd29.jpg)

![dba678121c009366cf792256ec837023d996aa201ba2689ce1de72d5c25e5d5d.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/dba678121c009366cf792256ec837023d996aa201ba2689ce1de72d5c25e5d5d.jpg)

![e9c223e17df4b264ce9923b6650ba11df9b6c1c37770b7fc90bda4790c9a7beb.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/images/e9c223e17df4b264ce9923b6650ba11df9b6c1c37770b7fc90bda4790c9a7beb.jpg)

### Tables

![117283c1091a1a413a5c311b3331064b236167d65bdb2244700407b088edc90a.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/tables/117283c1091a1a413a5c311b3331064b236167d65bdb2244700407b088edc90a.jpg)

![560af52255e5d8522b3fd6735e8aae5bfd54351b48b9cf429ba591668b8bcd0c.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/tables/560af52255e5d8522b3fd6735e8aae5bfd54351b48b9cf429ba591668b8bcd0c.jpg)

![ae385b028567d3481cd2e4f10a0eb5f344fc4ae3c467e1aaaa53747aeef75ddb.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/tables/ae385b028567d3481cd2e4f10a0eb5f344fc4ae3c467e1aaaa53747aeef75ddb.jpg)

![d0fc9a910bad6c8d4cb672f592297eb052aa4625afd0ad609839293ef6af92d1.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/tables/d0fc9a910bad6c8d4cb672f592297eb052aa4625afd0ad609839293ef6af92d1.jpg)

![e7d610d9b30af25da3c49ba29528b21d754ea5c265e34bba134015f4c932ec2a.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/tables/e7d610d9b30af25da3c49ba29528b21d754ea5c265e34bba134015f4c932ec2a.jpg)

![eda46bf58e24026a25324b0226131fc034a1b5eb8909f97567f3a8bff46a748c.jpg](../nips_results/862_Predictive%20Coding%20Enhances%20Meta-RL%20To%20Achieve%20Interpretable%20Bayes-Optimal%20Belief%20Representation%20Unde/tables/eda46bf58e24026a25324b0226131fc034a1b5eb8909f97567f3a8bff46a748c.jpg)

## Point3R: Streaming 3D Reconstruction with Explicit Spatial Pointer Memory


### Images

![2b6e48abbc5a4eb333314d5db7058cbe57cd52ffed99cb78ba5ff41f0ef8e36e.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/images/2b6e48abbc5a4eb333314d5db7058cbe57cd52ffed99cb78ba5ff41f0ef8e36e.jpg)

![885b39593f77eb65c7e87d2b4f8e94dfed0ad180cde09434bf9d5077d954fd83.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/images/885b39593f77eb65c7e87d2b4f8e94dfed0ad180cde09434bf9d5077d954fd83.jpg)

![b97716a2e22b26ee72ff61c0e3d3f4c690fb97bb2d04a9dca426406f57dcec2c.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/images/b97716a2e22b26ee72ff61c0e3d3f4c690fb97bb2d04a9dca426406f57dcec2c.jpg)

![d030b9f0d22134d83b76fed1033b2fe62970a1e2bfba47d1bd53ae65861f5eeb.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/images/d030b9f0d22134d83b76fed1033b2fe62970a1e2bfba47d1bd53ae65861f5eeb.jpg)

![f9f9a539b70c97151b9065240971e931fd192bf1123f9bf77930b219693b0fed.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/images/f9f9a539b70c97151b9065240971e931fd192bf1123f9bf77930b219693b0fed.jpg)

![fa81e7e023fa1e93012440e18cd4d3b24774435b73fc738b25c4e400e5373721.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/images/fa81e7e023fa1e93012440e18cd4d3b24774435b73fc738b25c4e400e5373721.jpg)

### Tables

![3ff8397b19c0dc1b558130a120e892785b3fbdc33d756060a31ec691115a655c.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/tables/3ff8397b19c0dc1b558130a120e892785b3fbdc33d756060a31ec691115a655c.jpg)

![5732f98180ac79ee5579934de59cdf40b17829d879c0b5f623dc18b0480a8ca3.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/tables/5732f98180ac79ee5579934de59cdf40b17829d879c0b5f623dc18b0480a8ca3.jpg)

![6d09209a978af0e84fc9e5f5a39f27c7cec91e5fb1fc46bf34fe0c87c52c9fa7.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/tables/6d09209a978af0e84fc9e5f5a39f27c7cec91e5fb1fc46bf34fe0c87c52c9fa7.jpg)

![834b6cebfc30e259981618ca36011dd0209be783ed77098465a77d2a23dd45e0.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/tables/834b6cebfc30e259981618ca36011dd0209be783ed77098465a77d2a23dd45e0.jpg)

![8878274d49b5962d9f4f081a7613174aaaabfc3dfe21922af6ca6f6130c6fb0d.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/tables/8878274d49b5962d9f4f081a7613174aaaabfc3dfe21922af6ca6f6130c6fb0d.jpg)

![8fba1e81deab8eecf714c38cb7d5cd3a818b4653ee7734aa72702fdc357fdeb5.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/tables/8fba1e81deab8eecf714c38cb7d5cd3a818b4653ee7734aa72702fdc357fdeb5.jpg)

![bea0621b18f25031e5504cbb662d3ca86be863c1bfd0017fed3da6aeecd1d9a8.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/tables/bea0621b18f25031e5504cbb662d3ca86be863c1bfd0017fed3da6aeecd1d9a8.jpg)

![c2ca3e751f16fb13e16e95af3deee458d9e111925c923c65425d34b93f8f262e.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/tables/c2ca3e751f16fb13e16e95af3deee458d9e111925c923c65425d34b93f8f262e.jpg)

![c3465886848e8812e67c9890755cc03084b8dc4377a5f1acb769425b14b6892f.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/tables/c3465886848e8812e67c9890755cc03084b8dc4377a5f1acb769425b14b6892f.jpg)

![c606c7c9fb3e25bd8d69fc5742020082d44db4672a3cf7056cd55d917fc1247b.jpg](../nips_results/863_Point3R_%20Streaming%203D%20Reconstruction%20with%20Explicit%20Spatial%20Pointer%20Memory/tables/c606c7c9fb3e25bd8d69fc5742020082d44db4672a3cf7056cd55d917fc1247b.jpg)

## CLAWS:Creativity detection for LLM-generated solutions using Attention Window of Sections


### Images

![080175e07f45475c0b7056598f01d507a4c1f6a1d1ccfba1eabddd0416f0d0b8.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/images/080175e07f45475c0b7056598f01d507a4c1f6a1d1ccfba1eabddd0416f0d0b8.jpg)

![14070daefc45762394393b7c383f1bb50660e7ffa9e2a6376c3e24cd9af6686e.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/images/14070daefc45762394393b7c383f1bb50660e7ffa9e2a6376c3e24cd9af6686e.jpg)

![86d6e11b003eaf720181b1fcf604b72cab861d05bbe2445f8711f51af04009ad.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/images/86d6e11b003eaf720181b1fcf604b72cab861d05bbe2445f8711f51af04009ad.jpg)

![c1c5f2724aadfbb81745e5be843c286e52cc754349a975dff74f581a20b2d9b2.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/images/c1c5f2724aadfbb81745e5be843c286e52cc754349a975dff74f581a20b2d9b2.jpg)

![f50d508147c1d50ccbf2d9e77105caac8d714644a7540349dc6bbaa7fe802ee4.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/images/f50d508147c1d50ccbf2d9e77105caac8d714644a7540349dc6bbaa7fe802ee4.jpg)

![f5d83ad2b436fe6658f2ce99be1ccd0397a0e68beb3a567568e7af137205186f.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/images/f5d83ad2b436fe6658f2ce99be1ccd0397a0e68beb3a567568e7af137205186f.jpg)

### Tables

![19db4e94373fd6c5d596f2f5caf629e54abde16a4b9f6f54fc3afd81478e8d43.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/19db4e94373fd6c5d596f2f5caf629e54abde16a4b9f6f54fc3afd81478e8d43.jpg)

![29fc602b4cab532af21b243f8a53dccbd877fd342a19d27050c5dce09f4018e1.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/29fc602b4cab532af21b243f8a53dccbd877fd342a19d27050c5dce09f4018e1.jpg)

![2b523ed5ce3afe16d76df34786ecdab404a7dc0628ad263d4f487db9c22a9ba6.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/2b523ed5ce3afe16d76df34786ecdab404a7dc0628ad263d4f487db9c22a9ba6.jpg)

![348670aa8dfb9cace40c9525b78a2b27eefb6ba82c3efa077d9a8a2520284287.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/348670aa8dfb9cace40c9525b78a2b27eefb6ba82c3efa077d9a8a2520284287.jpg)

![35cb85fb79167c902cc56e417213453fc230a4493e19a6ec7d7a138177559d0a.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/35cb85fb79167c902cc56e417213453fc230a4493e19a6ec7d7a138177559d0a.jpg)

![4b81f202dd3edbb4926a4fc56d35331354d067c4c051a74124808f70879a448b.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/4b81f202dd3edbb4926a4fc56d35331354d067c4c051a74124808f70879a448b.jpg)

![5b2be057a48ad63f86b3a8e623fc59df81678bb776e2a4c82fa6acc58dbb4700.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/5b2be057a48ad63f86b3a8e623fc59df81678bb776e2a4c82fa6acc58dbb4700.jpg)

![5c1a04d30f49a8c33d53a7dcabe38947bc7374e6d67ae67081a3447c81887faf.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/5c1a04d30f49a8c33d53a7dcabe38947bc7374e6d67ae67081a3447c81887faf.jpg)

![5dd97b3e2a3fba57188a3e70078873cf2e2905372757e8a589412d750728f141.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/5dd97b3e2a3fba57188a3e70078873cf2e2905372757e8a589412d750728f141.jpg)

![5e3c1d9234d05bd3d812027cb5d15fd80723ceaedd970dd80bb6c948746d9692.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/5e3c1d9234d05bd3d812027cb5d15fd80723ceaedd970dd80bb6c948746d9692.jpg)

![677c359e63d2ed1f6fbef3bfdc5862145aae720d772e05ef33ccf92d072311b1.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/677c359e63d2ed1f6fbef3bfdc5862145aae720d772e05ef33ccf92d072311b1.jpg)

![776a0881e7d579ab362f59330c75c43f63847531be93f9beeaba73b2a846045b.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/776a0881e7d579ab362f59330c75c43f63847531be93f9beeaba73b2a846045b.jpg)

![8dec129572d3232dd000047f2d15562d2c461e3b89c7c31498d6e82087cf502e.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/8dec129572d3232dd000047f2d15562d2c461e3b89c7c31498d6e82087cf502e.jpg)

![9bdeb689cda25491d63a40f14a225db51c212d26ae762689607b9639ba29687f.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/9bdeb689cda25491d63a40f14a225db51c212d26ae762689607b9639ba29687f.jpg)

![b602bb4d248989f3f9b22defc4dee136a7015a38cd2e182d5da29143731ec22b.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/b602bb4d248989f3f9b22defc4dee136a7015a38cd2e182d5da29143731ec22b.jpg)

![cb714ab323d829db4fe52ec65190f66ab78a384766cfd07ed3b1dc383ea88283.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/cb714ab323d829db4fe52ec65190f66ab78a384766cfd07ed3b1dc383ea88283.jpg)

![e18359893d905654577dce3895e165ecc08e444c92f73d5cc39301e21fb5e882.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/e18359893d905654577dce3895e165ecc08e444c92f73d5cc39301e21fb5e882.jpg)

![e5e8c237e5bc632d90ea36a1a635ecf8e8054dda03165a7430d442f9456f198d.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/e5e8c237e5bc632d90ea36a1a635ecf8e8054dda03165a7430d442f9456f198d.jpg)

![ed48d54c1237ffdef2ac01d4f22e7d8ca3aa7f35f22c8c293514d74bd8ff7dfe.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/ed48d54c1237ffdef2ac01d4f22e7d8ca3aa7f35f22c8c293514d74bd8ff7dfe.jpg)

![f456b94fabcfcdea8ab249ab7398264dd43f5694562d7f485601dbc85b756f88.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/f456b94fabcfcdea8ab249ab7398264dd43f5694562d7f485601dbc85b756f88.jpg)

![f60241f09e57a845687305e8894c54c4673964d4ba7299a66254f9e90669f21a.jpg](../nips_results/864_CLAWS_Creativity%20detection%20for%20LLM-generated%20solutions%20using%20Attention%20Window%20of%20Sections/tables/f60241f09e57a845687305e8894c54c4673964d4ba7299a66254f9e90669f21a.jpg)

## Bridging Equivariant GNNs and Spherical CNNs for Structured Physical Domains


### Images

![01ed64c06e07914d8c20cbaadb3aead50e126ccf8df1bbf3a8eaeee461de829d.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/01ed64c06e07914d8c20cbaadb3aead50e126ccf8df1bbf3a8eaeee461de829d.jpg)

![020793cd0f671d05cb2e178b3ef3b8f136b00811cc56924f4c2f17231d0d8f02.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/020793cd0f671d05cb2e178b3ef3b8f136b00811cc56924f4c2f17231d0d8f02.jpg)

![21c18a617e7367cca6c5c4d60031cb1d26724fa9ce4cb5200eafebef3c64ddd5.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/21c18a617e7367cca6c5c4d60031cb1d26724fa9ce4cb5200eafebef3c64ddd5.jpg)

![345197faa69c60fbb0cf0376824086bf93a0aa3465cf3027bdb0ce7952fee5c0.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/345197faa69c60fbb0cf0376824086bf93a0aa3465cf3027bdb0ce7952fee5c0.jpg)

![437942745e4db4946db148cba9901e96be4e671b111edee14ef6763deef22d40.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/437942745e4db4946db148cba9901e96be4e671b111edee14ef6763deef22d40.jpg)

![615e865a5992adf5e34b5bcf5c9b6b0aeffba64ac767117484bff57eb39af046.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/615e865a5992adf5e34b5bcf5c9b6b0aeffba64ac767117484bff57eb39af046.jpg)

![64058a24548b5fd90e2e07ee10be0cd2382c5dee7e399c8d98f2c63e2f769f0a.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/64058a24548b5fd90e2e07ee10be0cd2382c5dee7e399c8d98f2c63e2f769f0a.jpg)

![85a68bf59fcdf332b7f1c37831e3bdd07197124bb813970721b4d0d1b2d11d98.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/85a68bf59fcdf332b7f1c37831e3bdd07197124bb813970721b4d0d1b2d11d98.jpg)

![baeb0966cb3ac93459c335bcaa10ca4697fb95fa616bb046edc453259d35d214.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/baeb0966cb3ac93459c335bcaa10ca4697fb95fa616bb046edc453259d35d214.jpg)

![bffa9f099140ab3ea6e927478e3b17025979e6e8a94ae781016e500a39f4a6b9.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/bffa9f099140ab3ea6e927478e3b17025979e6e8a94ae781016e500a39f4a6b9.jpg)

![c49727f985cb466f5f65de8a24dfe6aa69d319bb6c27e1b492d2014d9a9f7427.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/c49727f985cb466f5f65de8a24dfe6aa69d319bb6c27e1b492d2014d9a9f7427.jpg)

![d65daec37fd60cc880f84808497da47cf21d50443e5d715e3cdecc1441e526f2.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/d65daec37fd60cc880f84808497da47cf21d50443e5d715e3cdecc1441e526f2.jpg)

![db763bb995f8ddc9598becd8d484ea915c72a6bab657fa0118aa9e0ab3ad7c74.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/db763bb995f8ddc9598becd8d484ea915c72a6bab657fa0118aa9e0ab3ad7c74.jpg)

![f2440078460db24c54fd80fc9163700abb811176486a1e48de7c84a456a0dd3e.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/images/f2440078460db24c54fd80fc9163700abb811176486a1e48de7c84a456a0dd3e.jpg)

### Tables

![9e299adac170bf4c8358703048322003fe306a35c01e2aa95f565915ffa2cf0d.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/tables/9e299adac170bf4c8358703048322003fe306a35c01e2aa95f565915ffa2cf0d.jpg)

![a22a8c14df0aa2099a06a6b601a675c01ffec3ba6d23f5fc9e0bf2d0e672c88b.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/tables/a22a8c14df0aa2099a06a6b601a675c01ffec3ba6d23f5fc9e0bf2d0e672c88b.jpg)

![ae5629ff1dbbbb0907347097feb2a10e5b46fe32961c2b01d2e8bbe31657d586.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/tables/ae5629ff1dbbbb0907347097feb2a10e5b46fe32961c2b01d2e8bbe31657d586.jpg)

![c3ed17e647c58e918710b6fc30ea584eabe6951ccdc96d8615601e4c213c58a6.jpg](../nips_results/865_Bridging%20Equivariant%20GNNs%20and%20Spherical%20CNNs%20for%20Structured%20Physical%20Domains/tables/c3ed17e647c58e918710b6fc30ea584eabe6951ccdc96d8615601e4c213c58a6.jpg)

## Prior-Guided Flow Matching for Target-Aware Molecule Design with Learnable Atom Number


### Images

![01d14de5ce7fd8c4e7f2abb66dd1cf5349cfbe80c0ae06ab3f478a08cc3231e1.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/images/01d14de5ce7fd8c4e7f2abb66dd1cf5349cfbe80c0ae06ab3f478a08cc3231e1.jpg)

![11cc13d522741f953e6102284790ee3bd6de1d9e67f0c7827ed39c5c1d953006.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/images/11cc13d522741f953e6102284790ee3bd6de1d9e67f0c7827ed39c5c1d953006.jpg)

![19afd376576048a6628d7c566dcf66c037108168ab3e24363542f4368076536b.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/images/19afd376576048a6628d7c566dcf66c037108168ab3e24363542f4368076536b.jpg)

![2fd82fb410d2f5679dc14da00c6108c18233f68461412c7443a2e92336b2acc3.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/images/2fd82fb410d2f5679dc14da00c6108c18233f68461412c7443a2e92336b2acc3.jpg)

![34f2344e4bcb506dd548a55a11d5c0b241e400f2022e137b136baeecb61c7268.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/images/34f2344e4bcb506dd548a55a11d5c0b241e400f2022e137b136baeecb61c7268.jpg)

![3797d053b5906977a9db35cf3eb7e8d4c248e5f40c220dd138c512df59aa7354.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/images/3797d053b5906977a9db35cf3eb7e8d4c248e5f40c220dd138c512df59aa7354.jpg)

![3e7c924cb3b701405ef5c3bccd30a071bfdbe0f66fe919d7d6883ae0667b0978.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/images/3e7c924cb3b701405ef5c3bccd30a071bfdbe0f66fe919d7d6883ae0667b0978.jpg)

![83415420e3bd05ff38b27824a980f3c92d76b234ab7a43f3534cda71f2f7983d.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/images/83415420e3bd05ff38b27824a980f3c92d76b234ab7a43f3534cda71f2f7983d.jpg)

![e446c5351bef3c603bc829bd027a4ef4b314c69f6c38ffc2fd8fb6266d14fd11.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/images/e446c5351bef3c603bc829bd027a4ef4b314c69f6c38ffc2fd8fb6266d14fd11.jpg)

![ef457a0307b4dc1c78b1f394fe5c1de5ac567acc9c098b987543987b583e59db.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/images/ef457a0307b4dc1c78b1f394fe5c1de5ac567acc9c098b987543987b583e59db.jpg)

![f356d68ccb55d4afda82e61d3b93d2df7677817f7cc1cfc8817e6064cb16af3a.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/images/f356d68ccb55d4afda82e61d3b93d2df7677817f7cc1cfc8817e6064cb16af3a.jpg)

### Tables

![0c52d13ed6ef1b2fce665dfa0ed13356af6923e900ac6756cce0f137a2e5c495.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/tables/0c52d13ed6ef1b2fce665dfa0ed13356af6923e900ac6756cce0f137a2e5c495.jpg)

![0e1cf6c8b31a0e52f0b15d9155576d2bfd0f590512a85bab8c03af6eda73c1b6.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/tables/0e1cf6c8b31a0e52f0b15d9155576d2bfd0f590512a85bab8c03af6eda73c1b6.jpg)

![0f87f3f7705e0b512196caba0ab9d4e6c326325c401b83a3e6d3a59928d1625a.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/tables/0f87f3f7705e0b512196caba0ab9d4e6c326325c401b83a3e6d3a59928d1625a.jpg)

![33cc48ba82534cabf936058dae4f13c6028fb33ffbed980bbd1c44112fa81b3a.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/tables/33cc48ba82534cabf936058dae4f13c6028fb33ffbed980bbd1c44112fa81b3a.jpg)

![58c090fe4bdece9b91087f6c2d3f195db518851d87e91a1851b355c2f444a8eb.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/tables/58c090fe4bdece9b91087f6c2d3f195db518851d87e91a1851b355c2f444a8eb.jpg)

![8568ec06c77b6742478a04b0734ea8a9062d8a88839ff26da9dbdece5d3f1f16.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/tables/8568ec06c77b6742478a04b0734ea8a9062d8a88839ff26da9dbdece5d3f1f16.jpg)

![90d73d8ba107e1642943b945b17429b145b2787ffba4b8d0d03ce3ca17f68325.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/tables/90d73d8ba107e1642943b945b17429b145b2787ffba4b8d0d03ce3ca17f68325.jpg)

![97a0bc4db1cca9667a61a42e6ae6c37ba44e2b7c25470f6947b9ca1c5b499460.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/tables/97a0bc4db1cca9667a61a42e6ae6c37ba44e2b7c25470f6947b9ca1c5b499460.jpg)

![9bfeae1ee75d65f105345fd17edf993f1145efecdca99bd403c3cccae15a249a.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/tables/9bfeae1ee75d65f105345fd17edf993f1145efecdca99bd403c3cccae15a249a.jpg)

![cfeb4deea1ddd1df28452fa46c70e90e7c1c7a82c905c5eeccebc401747f7756.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/tables/cfeb4deea1ddd1df28452fa46c70e90e7c1c7a82c905c5eeccebc401747f7756.jpg)

![ed519d59ebac54223f2e39a7ea3463e5729f6864922ab1c3cc95f6437ffa5367.jpg](../nips_results/866_Prior-Guided%20Flow%20Matching%20for%20Target-Aware%20Molecule%20Design%20with%20Learnable%20Atom%20Number/tables/ed519d59ebac54223f2e39a7ea3463e5729f6864922ab1c3cc95f6437ffa5367.jpg)

## IGD: Token Decisiveness Modeling via Information Gain in LLMs for Personalized Recommendation


### Images

![16d997f0a32e476ccd827b88bcd3832c0911bba0bbf6e9e8b72994d093a4a4a2.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/images/16d997f0a32e476ccd827b88bcd3832c0911bba0bbf6e9e8b72994d093a4a4a2.jpg)

![2f262fcdd85d0ec88fc718b91b49dd6b8b2a94bf8b0cf62bbab8216d196013aa.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/images/2f262fcdd85d0ec88fc718b91b49dd6b8b2a94bf8b0cf62bbab8216d196013aa.jpg)

![347353948887bb69551f73cf5a854551566bc1e1c1cb40a4f1e4089703ea2f84.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/images/347353948887bb69551f73cf5a854551566bc1e1c1cb40a4f1e4089703ea2f84.jpg)

![8339be4ace866d7eb9990b629a573aaa3d455df39f88ebf0e58d5afba0cdcf6d.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/images/8339be4ace866d7eb9990b629a573aaa3d455df39f88ebf0e58d5afba0cdcf6d.jpg)

![af56109d0285a1015c7b705de107c8f67d7378db867c574cea17932cea3b7b6d.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/images/af56109d0285a1015c7b705de107c8f67d7378db867c574cea17932cea3b7b6d.jpg)

![bd6bb431a80dd22ab388fe6af59c59c4be853c46425fc36eaa183a8670c2b2c3.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/images/bd6bb431a80dd22ab388fe6af59c59c4be853c46425fc36eaa183a8670c2b2c3.jpg)

![c95f9f70fcaaba539486f4a1c5d78e1ce04245cb177eca5b13dfdec8033196c2.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/images/c95f9f70fcaaba539486f4a1c5d78e1ce04245cb177eca5b13dfdec8033196c2.jpg)

![f43ca767dd636bfcd8d6c7974427aa97d8451f1c84174d70cc87942f8dfede20.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/images/f43ca767dd636bfcd8d6c7974427aa97d8451f1c84174d70cc87942f8dfede20.jpg)

### Tables

![102d3951e83f785f7a0fa0a5808d1210c5030e1f10dcc232e56e2c5e1838cc60.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/tables/102d3951e83f785f7a0fa0a5808d1210c5030e1f10dcc232e56e2c5e1838cc60.jpg)

![111708e67d39fa108338a97a0f581783ae12cd6ef93484a9ace98ec8c1ba4639.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/tables/111708e67d39fa108338a97a0f581783ae12cd6ef93484a9ace98ec8c1ba4639.jpg)

![2ce391766dce75205cf4ef1e5ef38e8836f1c479fcb7254660a8fa285cb45e4b.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/tables/2ce391766dce75205cf4ef1e5ef38e8836f1c479fcb7254660a8fa285cb45e4b.jpg)

![50e16f491f3356484e4a5c5e46fa1d9b10cd777c8f0d56ff5591ec34501bb45c.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/tables/50e16f491f3356484e4a5c5e46fa1d9b10cd777c8f0d56ff5591ec34501bb45c.jpg)

![7450b2c559d58e752f581dd5a51149053761eeb095d9749c323541443a230e6d.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/tables/7450b2c559d58e752f581dd5a51149053761eeb095d9749c323541443a230e6d.jpg)

![94b39555dc268863e8c04ab4a5816eebc641c74dd48cf869ee1565370b996b1b.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/tables/94b39555dc268863e8c04ab4a5816eebc641c74dd48cf869ee1565370b996b1b.jpg)

![97e65263e378e44c5e38913e0ce00c18f0b1b0c4fd0d6b532739083a8a689244.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/tables/97e65263e378e44c5e38913e0ce00c18f0b1b0c4fd0d6b532739083a8a689244.jpg)

![986df55329ffb1029ddd31828be3cf9123b004489ea29f78f8e036c9d961faa5.jpg](../nips_results/867_IGD_%20Token%20Decisiveness%20Modeling%20via%20Information%20Gain%20in%20LLMs%20for%20Personalized%20Recommendation/tables/986df55329ffb1029ddd31828be3cf9123b004489ea29f78f8e036c9d961faa5.jpg)

## CMoB: Modality Valuation via Causal Effect for Balanced Multimodal Learning


### Images

![864ab38f2894cdc97d6798374c61b9c25545b81ddf00035955e8495b7daf3865.jpg](../nips_results/868_CMoB_%20Modality%20Valuation%20via%20Causal%20Effect%20for%20Balanced%20Multimodal%20Learning/images/864ab38f2894cdc97d6798374c61b9c25545b81ddf00035955e8495b7daf3865.jpg)

![8ac25cec94b31cdba44d0e939e06d4cd323c3d626949735f4a41ec9ed14d15b7.jpg](../nips_results/868_CMoB_%20Modality%20Valuation%20via%20Causal%20Effect%20for%20Balanced%20Multimodal%20Learning/images/8ac25cec94b31cdba44d0e939e06d4cd323c3d626949735f4a41ec9ed14d15b7.jpg)

![b6dcb21a414b74772d6eca4e4dd4c15dd1ecf3596bb975213a54a889e32e7d7d.jpg](../nips_results/868_CMoB_%20Modality%20Valuation%20via%20Causal%20Effect%20for%20Balanced%20Multimodal%20Learning/images/b6dcb21a414b74772d6eca4e4dd4c15dd1ecf3596bb975213a54a889e32e7d7d.jpg)

![c8d6bdce34bd8c2363bbf295e4b9fc0e63f620e548b0f1286d9f2d424837a46a.jpg](../nips_results/868_CMoB_%20Modality%20Valuation%20via%20Causal%20Effect%20for%20Balanced%20Multimodal%20Learning/images/c8d6bdce34bd8c2363bbf295e4b9fc0e63f620e548b0f1286d9f2d424837a46a.jpg)

![f09483d6970edd215d05982c45ac13d8f29ae206da3ebf5ba50d465ead8bd2db.jpg](../nips_results/868_CMoB_%20Modality%20Valuation%20via%20Causal%20Effect%20for%20Balanced%20Multimodal%20Learning/images/f09483d6970edd215d05982c45ac13d8f29ae206da3ebf5ba50d465ead8bd2db.jpg)

### Tables

![0cebd1a98c5befbed6a43f93dae662a65011075134b662a09f85ed1c1b18be78.jpg](../nips_results/868_CMoB_%20Modality%20Valuation%20via%20Causal%20Effect%20for%20Balanced%20Multimodal%20Learning/tables/0cebd1a98c5befbed6a43f93dae662a65011075134b662a09f85ed1c1b18be78.jpg)

![4386aca0917a016a6ad7d12c000e9428fc2428aee1da78d499bd5c227a0a5399.jpg](../nips_results/868_CMoB_%20Modality%20Valuation%20via%20Causal%20Effect%20for%20Balanced%20Multimodal%20Learning/tables/4386aca0917a016a6ad7d12c000e9428fc2428aee1da78d499bd5c227a0a5399.jpg)

![535b1148fafa35f6dd39c2906ffa7773edcd781822fa644f91ae1bd81a12be7d.jpg](../nips_results/868_CMoB_%20Modality%20Valuation%20via%20Causal%20Effect%20for%20Balanced%20Multimodal%20Learning/tables/535b1148fafa35f6dd39c2906ffa7773edcd781822fa644f91ae1bd81a12be7d.jpg)

![8698c18bbc9a38411e8fede080eb331c6a41734ce3cd9824c7f7f201ca5553f9.jpg](../nips_results/868_CMoB_%20Modality%20Valuation%20via%20Causal%20Effect%20for%20Balanced%20Multimodal%20Learning/tables/8698c18bbc9a38411e8fede080eb331c6a41734ce3cd9824c7f7f201ca5553f9.jpg)

## JailBound: Jailbreaking Internal Safety Boundaries of Vision-Language Models


### Images

![00f7e6a7bbf1f3bd91eadf89ca9ca4c026c0e517996ce205bba5385c4645bc14.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/images/00f7e6a7bbf1f3bd91eadf89ca9ca4c026c0e517996ce205bba5385c4645bc14.jpg)

![237ba4156e8e7e39d9b4a029aefc1f97845bba0737ad3938a4e7701343adff80.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/images/237ba4156e8e7e39d9b4a029aefc1f97845bba0737ad3938a4e7701343adff80.jpg)

![3123837e673d3abc928c0eda3b7fc05ac0e7a8715bb3aede41eff662b8be7928.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/images/3123837e673d3abc928c0eda3b7fc05ac0e7a8715bb3aede41eff662b8be7928.jpg)

![4a227a72e080639149985905369048ccb5e92c2ee01bfbfff657855d78f596b5.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/images/4a227a72e080639149985905369048ccb5e92c2ee01bfbfff657855d78f596b5.jpg)

![9b4d282d81a7c276cc3ae9fb830501d77a7a5e6c02383505d2dde3cb6b2d56de.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/images/9b4d282d81a7c276cc3ae9fb830501d77a7a5e6c02383505d2dde3cb6b2d56de.jpg)

![a34ce65bcee6db2fbed46b6731fb245a8e11a7887b4c0113145e2de56a740bb1.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/images/a34ce65bcee6db2fbed46b6731fb245a8e11a7887b4c0113145e2de56a740bb1.jpg)

![e64d56261fc53a215e976c14816b6549813cea8841abdb28425d8fcca6dabd63.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/images/e64d56261fc53a215e976c14816b6549813cea8841abdb28425d8fcca6dabd63.jpg)

### Tables

![28451fde4591eccf0bdc3a973cc0a9badb9183b5604a4dc3b0261d77064359b1.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/tables/28451fde4591eccf0bdc3a973cc0a9badb9183b5604a4dc3b0261d77064359b1.jpg)

![378234bd73edbb504d79020490aaf927112af323da62d81095ef1d0b479d936d.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/tables/378234bd73edbb504d79020490aaf927112af323da62d81095ef1d0b479d936d.jpg)

![55e364f68bb9bdf8952476dd0bffc18bcac2047b65ffec7169967ca899526d9a.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/tables/55e364f68bb9bdf8952476dd0bffc18bcac2047b65ffec7169967ca899526d9a.jpg)

![746f988d1e8b848823a0d6bb5305ed49de791199b477edd32d8ce717feed27f5.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/tables/746f988d1e8b848823a0d6bb5305ed49de791199b477edd32d8ce717feed27f5.jpg)

![8c6be877ecf19042a6d0ef75d36c817dd65aff2a097039d3eee2e622aceeca40.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/tables/8c6be877ecf19042a6d0ef75d36c817dd65aff2a097039d3eee2e622aceeca40.jpg)

![ff6619edab3c30ce4aea4e2addbbb60635953ecfb988e8eac4292689f57eae60.jpg](../nips_results/869_JailBound_%20Jailbreaking%20Internal%20Safety%20Boundaries%20of%20Vision-Language%20Models/tables/ff6619edab3c30ce4aea4e2addbbb60635953ecfb988e8eac4292689f57eae60.jpg)

## Confusion-Driven Self-Supervised Progressively Weighted Ensemble Learning for Non-Exemplar Class Incremental Learning


### Images

![198eeb06ffe1ba5274225b4a027188627902cd515028f4fee038913728a3fdac.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/images/198eeb06ffe1ba5274225b4a027188627902cd515028f4fee038913728a3fdac.jpg)

![1f991ebd620a475f217f1725a9d0bb8f32788402086496e2c6e183fd6df92b9e.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/images/1f991ebd620a475f217f1725a9d0bb8f32788402086496e2c6e183fd6df92b9e.jpg)

![33e923d78e700be66fead8a87c34f0f949259aaf595e554c19ddc432c0dd1a88.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/images/33e923d78e700be66fead8a87c34f0f949259aaf595e554c19ddc432c0dd1a88.jpg)

![36e00442a32496635649b6ca6902c3d50b0da649135d42b3bcabfbbcb3dad962.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/images/36e00442a32496635649b6ca6902c3d50b0da649135d42b3bcabfbbcb3dad962.jpg)

![709b04e288c5137ade8376e4e20a174125c7b237ec0292a3964e4efbd2ff8eb1.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/images/709b04e288c5137ade8376e4e20a174125c7b237ec0292a3964e4efbd2ff8eb1.jpg)

![8c8355bf7c20aaea7634cc892b5cb4f70419dbcbfa9d9a594a42385f272eb331.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/images/8c8355bf7c20aaea7634cc892b5cb4f70419dbcbfa9d9a594a42385f272eb331.jpg)

![8eeecc4722dfbf3b4fe7045f5541e55d0ff8a0c028f59a305dfc649a7420c179.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/images/8eeecc4722dfbf3b4fe7045f5541e55d0ff8a0c028f59a305dfc649a7420c179.jpg)

![b11449e283c7b84e91f4225ed78bdfa7e9db20f12aa22b0e75c16015aa7d8272.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/images/b11449e283c7b84e91f4225ed78bdfa7e9db20f12aa22b0e75c16015aa7d8272.jpg)

![c2a4755336f825ecc49dc147f149c2941236982d0461eae238871973df2be5ab.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/images/c2a4755336f825ecc49dc147f149c2941236982d0461eae238871973df2be5ab.jpg)

![f53e6f422e99e01fe5d34f41e84695ac975bd35b10db2e9462c54ac4044a14d8.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/images/f53e6f422e99e01fe5d34f41e84695ac975bd35b10db2e9462c54ac4044a14d8.jpg)

### Tables

![220290c419ec7049ffa99a4181e30f939955185800bb557603df923f1b80a56d.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/220290c419ec7049ffa99a4181e30f939955185800bb557603df923f1b80a56d.jpg)

![325df38f83fb83597be1835a53545c265f83678575a27579c515352092d7addd.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/325df38f83fb83597be1835a53545c265f83678575a27579c515352092d7addd.jpg)

![38a8ebeadb16e7fd84047a620ed6358204702a71b408ff13ecd3400ee814a727.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/38a8ebeadb16e7fd84047a620ed6358204702a71b408ff13ecd3400ee814a727.jpg)

![6024aeb76451b59b3678323b9828f355dde1abdd0a131cfdd6ad7592971f3eef.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/6024aeb76451b59b3678323b9828f355dde1abdd0a131cfdd6ad7592971f3eef.jpg)

![6d3eed3192389182c0c00e11808cc54d62ebfa47c47ed2f2984178b1c77a9135.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/6d3eed3192389182c0c00e11808cc54d62ebfa47c47ed2f2984178b1c77a9135.jpg)

![6eef96f74a4e55c92bb79a6cd924145a361d24d752876c15306c42417f030342.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/6eef96f74a4e55c92bb79a6cd924145a361d24d752876c15306c42417f030342.jpg)

![7c77621473dbbc57ffc6970e73e7b94a95698729221ea5cc9b9991b0a4b5330d.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/7c77621473dbbc57ffc6970e73e7b94a95698729221ea5cc9b9991b0a4b5330d.jpg)

![9df542ad52bda5a4264b7bd79876712f7510d7bf3f343c571c99e83c5cedaa51.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/9df542ad52bda5a4264b7bd79876712f7510d7bf3f343c571c99e83c5cedaa51.jpg)

![a8be0859f3631e317fcda58f762d0cbcc6d1eb612350317672de6d964163f6f4.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/a8be0859f3631e317fcda58f762d0cbcc6d1eb612350317672de6d964163f6f4.jpg)

![b88dd0434e95d7fe377aebe82cafcfea60dafcd07d4d9374b22cb7559ec09a6e.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/b88dd0434e95d7fe377aebe82cafcfea60dafcd07d4d9374b22cb7559ec09a6e.jpg)

![c5436558ef8e7ae5f310fabd16c9fb2172a198d4e480c11ece74421f2f9bdf5b.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/c5436558ef8e7ae5f310fabd16c9fb2172a198d4e480c11ece74421f2f9bdf5b.jpg)

![e9a37002ec59c7ec55d5de56eaadddb35be893ea971d76552e250b368856183f.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/e9a37002ec59c7ec55d5de56eaadddb35be893ea971d76552e250b368856183f.jpg)

![f018dd6d3ee968724eeb4e97286da3a60f46656229579b7c4ad2b2c7d21af22c.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/f018dd6d3ee968724eeb4e97286da3a60f46656229579b7c4ad2b2c7d21af22c.jpg)

![ffa9fd127a4c4c6fe3a45a5a36286cc872b638a05fa9fe271b9274aa02a96e6d.jpg](../nips_results/870_Confusion-Driven%20Self-Supervised%20Progressively%20Weighted%20Ensemble%20Learning%20for%20Non-Exemplar%20Class%20Inc/tables/ffa9fd127a4c4c6fe3a45a5a36286cc872b638a05fa9fe271b9274aa02a96e6d.jpg)

## Beyond the 80/20 Rule: High-Entropy Minority Tokens Drive Effective Reinforcement Learning for LLM Reasoning


### Images

![12a65d4f3cc1a2d1885d32f1fe661c5499db0ef159f562f0c4392bdcf488ae08.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/12a65d4f3cc1a2d1885d32f1fe661c5499db0ef159f562f0c4392bdcf488ae08.jpg)

![1a4d3628388e8c1422b32a1339dbf5fa8f6b713682ed526837a8ff6103e536fa.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/1a4d3628388e8c1422b32a1339dbf5fa8f6b713682ed526837a8ff6103e536fa.jpg)

![1a892cf70658e4cec11b449cfbf21f3a22676779502257770f41806fecbfd6c3.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/1a892cf70658e4cec11b449cfbf21f3a22676779502257770f41806fecbfd6c3.jpg)

![316bb6722028c839e06925654a5e20b3f8a2cace7d287e43d5536b34e5da6c97.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/316bb6722028c839e06925654a5e20b3f8a2cace7d287e43d5536b34e5da6c97.jpg)

![37501830d612023894a9569d72d519b83e73a8c6e1262e0332ccc8b84bd54845.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/37501830d612023894a9569d72d519b83e73a8c6e1262e0332ccc8b84bd54845.jpg)

![3d088c94dbb35e9669273cc6c007668eaddea3bb8ff17a41b1fd5680f5427e82.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/3d088c94dbb35e9669273cc6c007668eaddea3bb8ff17a41b1fd5680f5427e82.jpg)

![4d953c3d23cf74aeffac488e01f2012a84f05b3e5c8e0897e1ffab3d7ec31d69.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/4d953c3d23cf74aeffac488e01f2012a84f05b3e5c8e0897e1ffab3d7ec31d69.jpg)

![8e165290253b554dc87ea0e75b5de8a3b9eec85b9dc89a2d23f07d99d198f121.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/8e165290253b554dc87ea0e75b5de8a3b9eec85b9dc89a2d23f07d99d198f121.jpg)

![93045cbbee54a4d60be97f590af5be4d4683b02282a459fd03b97f7ca38df531.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/93045cbbee54a4d60be97f590af5be4d4683b02282a459fd03b97f7ca38df531.jpg)

![9610f3847086769da741abe11c14259d23a1f62b55ce71e173466c2a42b14d21.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/9610f3847086769da741abe11c14259d23a1f62b55ce71e173466c2a42b14d21.jpg)

![a041e6cd768804561cdab11b69b7d9dd30bf1b397f40bb110f1955d3766a803b.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/a041e6cd768804561cdab11b69b7d9dd30bf1b397f40bb110f1955d3766a803b.jpg)

![a11cf23704a98680cd77bf84e6795e588efb93d5f8215f4529f7732b9c0bd188.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/a11cf23704a98680cd77bf84e6795e588efb93d5f8215f4529f7732b9c0bd188.jpg)

![a20a74dc4fc8f8c152a7fce7d4758d53655f09368f461727c668de6027962a77.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/a20a74dc4fc8f8c152a7fce7d4758d53655f09368f461727c668de6027962a77.jpg)

![c0992a11b6f825c1b3ed5aaaf38a3fa60fd38a9a91aa8bc02afff716a0e68dd0.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/c0992a11b6f825c1b3ed5aaaf38a3fa60fd38a9a91aa8bc02afff716a0e68dd0.jpg)

![d982a973670ecf7493a14ae7b0f3cef50df503f6c4c3dd71d9887d1be2494223.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/d982a973670ecf7493a14ae7b0f3cef50df503f6c4c3dd71d9887d1be2494223.jpg)

![e17e7227a0f007c6bf8f773662aa32beef3a79eab6b84a2e393982fa050f9771.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/e17e7227a0f007c6bf8f773662aa32beef3a79eab6b84a2e393982fa050f9771.jpg)

![f14a45adf2d2d9357ebdc1fea768d8b62ead4e45bbf8eddcd6f0e1e68cf12eb0.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/f14a45adf2d2d9357ebdc1fea768d8b62ead4e45bbf8eddcd6f0e1e68cf12eb0.jpg)

![f5410b300a20035032f7c0da9b7d2c822fa4339f3590e8264eb8800e95397e7e.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/images/f5410b300a20035032f7c0da9b7d2c822fa4339f3590e8264eb8800e95397e7e.jpg)

### Tables

![1f491f9aa4fdf875a8f6238412cd2ae7589746139d0f985d16a595db1c292837.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/tables/1f491f9aa4fdf875a8f6238412cd2ae7589746139d0f985d16a595db1c292837.jpg)

![e74c2294980f8aa2adf74f8885b4268b06750e65fed617fb081a3434931f1032.jpg](../nips_results/871_Beyond%20the%2080_20%20Rule_%20High-Entropy%20Minority%20Tokens%20Drive%20Effective%20Reinforcement%20Learning%20for%20LLM%20R/tables/e74c2294980f8aa2adf74f8885b4268b06750e65fed617fb081a3434931f1032.jpg)

## Enforcing convex constraints in Graph Neural Networks


### Images

![06ea31477c12c84cae8b6082b2b9db03e4dd4ac955a3f56381ca70a66099ba43.jpg](../nips_results/872_Enforcing%20convex%20constraints%20in%20Graph%20Neural%20Networks/images/06ea31477c12c84cae8b6082b2b9db03e4dd4ac955a3f56381ca70a66099ba43.jpg)

![08d5bbfb4af218c2ec6ec4119bb192f92f5b20df9c10177e55833a8a1f7bea15.jpg](../nips_results/872_Enforcing%20convex%20constraints%20in%20Graph%20Neural%20Networks/images/08d5bbfb4af218c2ec6ec4119bb192f92f5b20df9c10177e55833a8a1f7bea15.jpg)

![240f151605a49e65c2c0355b8819e3c487e93c3085b7de02f71892acbd1d8684.jpg](../nips_results/872_Enforcing%20convex%20constraints%20in%20Graph%20Neural%20Networks/images/240f151605a49e65c2c0355b8819e3c487e93c3085b7de02f71892acbd1d8684.jpg)

![529d71d87e1c8ed012b377124d4f46c278d1b8838fbbb402fa2ff02d5a9f267a.jpg](../nips_results/872_Enforcing%20convex%20constraints%20in%20Graph%20Neural%20Networks/images/529d71d87e1c8ed012b377124d4f46c278d1b8838fbbb402fa2ff02d5a9f267a.jpg)

![b496dbfa5229c6af93552a8bca86595c752a380f06721682b487d88241c23bbf.jpg](../nips_results/872_Enforcing%20convex%20constraints%20in%20Graph%20Neural%20Networks/images/b496dbfa5229c6af93552a8bca86595c752a380f06721682b487d88241c23bbf.jpg)

![b4a61ebb10b85259113145141bce1c41dc30f861f05c3ff83623ef1ccc539dfc.jpg](../nips_results/872_Enforcing%20convex%20constraints%20in%20Graph%20Neural%20Networks/images/b4a61ebb10b85259113145141bce1c41dc30f861f05c3ff83623ef1ccc539dfc.jpg)

### Tables

![417ca1b1d804c4b9790e01bb5b265d427bb564ecc3a2ff89c4fb0ffc6e4f9e07.jpg](../nips_results/872_Enforcing%20convex%20constraints%20in%20Graph%20Neural%20Networks/tables/417ca1b1d804c4b9790e01bb5b265d427bb564ecc3a2ff89c4fb0ffc6e4f9e07.jpg)

## Segment then Splat: Unified 3D Open-Vocabulary Segmentation via Gaussian Splatting


### Images

![4f040e013f73e6712d9b9985369570e35eb69a29b7bb716db4a5c86c3051ba63.jpg](../nips_results/873_Segment%20then%20Splat_%20Unified%203D%20Open-Vocabulary%20Segmentation%20via%20Gaussian%20Splatting/images/4f040e013f73e6712d9b9985369570e35eb69a29b7bb716db4a5c86c3051ba63.jpg)

![58b189b7bfd2e1df11d1efb4d700886e11ce0479f789e95bfad95145c8836ef4.jpg](../nips_results/873_Segment%20then%20Splat_%20Unified%203D%20Open-Vocabulary%20Segmentation%20via%20Gaussian%20Splatting/images/58b189b7bfd2e1df11d1efb4d700886e11ce0479f789e95bfad95145c8836ef4.jpg)

![766ae962c6e76f6d09f030d36cc8066b95fb33cab54f3520deba3ea78ae499bb.jpg](../nips_results/873_Segment%20then%20Splat_%20Unified%203D%20Open-Vocabulary%20Segmentation%20via%20Gaussian%20Splatting/images/766ae962c6e76f6d09f030d36cc8066b95fb33cab54f3520deba3ea78ae499bb.jpg)

![7aef3b725fd433b7a69f31663c9bf4371dcfe95b99e9be89e5b65b171036310b.jpg](../nips_results/873_Segment%20then%20Splat_%20Unified%203D%20Open-Vocabulary%20Segmentation%20via%20Gaussian%20Splatting/images/7aef3b725fd433b7a69f31663c9bf4371dcfe95b99e9be89e5b65b171036310b.jpg)

![a3e41cd1b1b37051288c756466a59d86279bd708a6747d0269163390552f94da.jpg](../nips_results/873_Segment%20then%20Splat_%20Unified%203D%20Open-Vocabulary%20Segmentation%20via%20Gaussian%20Splatting/images/a3e41cd1b1b37051288c756466a59d86279bd708a6747d0269163390552f94da.jpg)

![c52c88aa808e152db6e55b8fe9da81e8da98981e4e397f9f3e11747cd873a2a7.jpg](../nips_results/873_Segment%20then%20Splat_%20Unified%203D%20Open-Vocabulary%20Segmentation%20via%20Gaussian%20Splatting/images/c52c88aa808e152db6e55b8fe9da81e8da98981e4e397f9f3e11747cd873a2a7.jpg)

### Tables

![58bdadde628d6b2d2db2f0e7921ce39723fe421ba8a5f824c28359d098ae0318.jpg](../nips_results/873_Segment%20then%20Splat_%20Unified%203D%20Open-Vocabulary%20Segmentation%20via%20Gaussian%20Splatting/tables/58bdadde628d6b2d2db2f0e7921ce39723fe421ba8a5f824c28359d098ae0318.jpg)

![6474d9d10e88172ffd902f577b928028a6e4b11eeed7a010bdb1e6a1433faeda.jpg](../nips_results/873_Segment%20then%20Splat_%20Unified%203D%20Open-Vocabulary%20Segmentation%20via%20Gaussian%20Splatting/tables/6474d9d10e88172ffd902f577b928028a6e4b11eeed7a010bdb1e6a1433faeda.jpg)

![74c24c7c363a115c013a1cb7bb57630ed7d36c41a446e4b2c58b326fc02bb9a9.jpg](../nips_results/873_Segment%20then%20Splat_%20Unified%203D%20Open-Vocabulary%20Segmentation%20via%20Gaussian%20Splatting/tables/74c24c7c363a115c013a1cb7bb57630ed7d36c41a446e4b2c58b326fc02bb9a9.jpg)

![8239f2ea4e8c9f5a8c1136dbd15363f0b0be7ba58d62d0f3ce5ff6eaa9db03cc.jpg](../nips_results/873_Segment%20then%20Splat_%20Unified%203D%20Open-Vocabulary%20Segmentation%20via%20Gaussian%20Splatting/tables/8239f2ea4e8c9f5a8c1136dbd15363f0b0be7ba58d62d0f3ce5ff6eaa9db03cc.jpg)

## MetaDefense: Defending Fine-tuning based Jailbreak Attack Before and During Generation


### Images

![03dd50664e63970d56bf1c636d778cfa908cf925313bfcd318ff01d7c44ecb09.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/images/03dd50664e63970d56bf1c636d778cfa908cf925313bfcd318ff01d7c44ecb09.jpg)

![39f3e3f094e4b503116555b79a678c89ba8950ab0cde4f6dad7429045bd38bd0.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/images/39f3e3f094e4b503116555b79a678c89ba8950ab0cde4f6dad7429045bd38bd0.jpg)

![3e88ccdf26a680eb7db3c98f4bcbc2b479d6628c10d2105e36fa0393fd46143f.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/images/3e88ccdf26a680eb7db3c98f4bcbc2b479d6628c10d2105e36fa0393fd46143f.jpg)

![62bccdb5c46439d83e945085701bd804fb21cd418ce48cda46fd6fef43d20780.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/images/62bccdb5c46439d83e945085701bd804fb21cd418ce48cda46fd6fef43d20780.jpg)

![ea8147307eb4980ed7bdfc75fbafe1198824f16d532f9fec86481554fc4e6b79.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/images/ea8147307eb4980ed7bdfc75fbafe1198824f16d532f9fec86481554fc4e6b79.jpg)

### Tables

![09084264b1d7b6eafc489fd508040f257cbca19c9ab93afd399ea947b6f8168e.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/09084264b1d7b6eafc489fd508040f257cbca19c9ab93afd399ea947b6f8168e.jpg)

![0a8ae9134534a9401b60f2aec8b36cc60c0520caa9f82f1d0392d53e9792a27f.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/0a8ae9134534a9401b60f2aec8b36cc60c0520caa9f82f1d0392d53e9792a27f.jpg)

![111f255087c1cee55f6ce567cfbae3b362e1a86531545573953e75e51ec4e085.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/111f255087c1cee55f6ce567cfbae3b362e1a86531545573953e75e51ec4e085.jpg)

![3225e8d2288296de5eec47452bbd33c3378c08d506bcb2be78d5e854bda97db3.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/3225e8d2288296de5eec47452bbd33c3378c08d506bcb2be78d5e854bda97db3.jpg)

![36c52f1040415578b8d4f2dd4780f3ed9e4d02c6122ebc2b78c983d64a85c35d.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/36c52f1040415578b8d4f2dd4780f3ed9e4d02c6122ebc2b78c983d64a85c35d.jpg)

![5ac5bbc70d62089700a89cae09f91124cdda1847f3afaf9ce0453a51339d8c10.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/5ac5bbc70d62089700a89cae09f91124cdda1847f3afaf9ce0453a51339d8c10.jpg)

![6454d80a7dd15f72fd3a466ce654e1e305635a1fa805fbe406c14529f304dda0.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/6454d80a7dd15f72fd3a466ce654e1e305635a1fa805fbe406c14529f304dda0.jpg)

![66056f2e1c4240290732d8c96bec3481578227deac4336d4feec41139dc514c0.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/66056f2e1c4240290732d8c96bec3481578227deac4336d4feec41139dc514c0.jpg)

![665a98cbd981791674379838a2a093580e1cfe068747ba262fc11b090a1bbccf.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/665a98cbd981791674379838a2a093580e1cfe068747ba262fc11b090a1bbccf.jpg)

![68a997a0184e80a10534ffc2eeb671921495ded26f39722f2ae94670055b9b40.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/68a997a0184e80a10534ffc2eeb671921495ded26f39722f2ae94670055b9b40.jpg)

![71480b3f95b1e23c49ab725bff92f7f3ed1cf2a360675d7e8a0422c521ca40f5.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/71480b3f95b1e23c49ab725bff92f7f3ed1cf2a360675d7e8a0422c521ca40f5.jpg)

![77664c69a2ba45bd8ec02c3f150629cb2ab1c6bdc01f10f9345815511cade1fe.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/77664c69a2ba45bd8ec02c3f150629cb2ab1c6bdc01f10f9345815511cade1fe.jpg)

![89a054cf619c3d9c7a83c3119c85d32ab24e0a44e522ac009041997512da4cce.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/89a054cf619c3d9c7a83c3119c85d32ab24e0a44e522ac009041997512da4cce.jpg)

![9e1fdc8dcd62d4255fb5534e24acddc7e6d66d31d61b7b24bbfc87785628e2dd.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/9e1fdc8dcd62d4255fb5534e24acddc7e6d66d31d61b7b24bbfc87785628e2dd.jpg)

![b2bcefe3d206895cbdb301037cc8140ec44af7669bb5ae8ebb6650d50323997b.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/b2bcefe3d206895cbdb301037cc8140ec44af7669bb5ae8ebb6650d50323997b.jpg)

![bb216874a9ef9dd5cfe00b6262642240b7f1a6b152c5a9691c8d4dfe773ad627.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/bb216874a9ef9dd5cfe00b6262642240b7f1a6b152c5a9691c8d4dfe773ad627.jpg)

![e0bc68078a5fa67243c775af2064e55577efc24a31719b0df82d490c0c47dc01.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/e0bc68078a5fa67243c775af2064e55577efc24a31719b0df82d490c0c47dc01.jpg)

![e1c9d51966187db2f7fa778dae6554a90847ec6f087e5c0bc0b042e2780af4b9.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/e1c9d51966187db2f7fa778dae6554a90847ec6f087e5c0bc0b042e2780af4b9.jpg)

![eb9ee256006e029c0293c75c1a5132e64abe1a897744ea742aa8379a09d7ab06.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/eb9ee256006e029c0293c75c1a5132e64abe1a897744ea742aa8379a09d7ab06.jpg)

![f18d8f6a27b6ac3b4ded0831f12e4dae864525ef53ca7685fcae397f6a9dd178.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/f18d8f6a27b6ac3b4ded0831f12e4dae864525ef53ca7685fcae397f6a9dd178.jpg)

![f68b705bdb8fcf68160d9c7d83d984ca5709596ee5e0d25e64593bd09617c6e3.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/f68b705bdb8fcf68160d9c7d83d984ca5709596ee5e0d25e64593bd09617c6e3.jpg)

![f76c92043330b063ea0f117e43ef117d1ae94f3f29667dc509eb96e1d60f8f99.jpg](../nips_results/874_MetaDefense_%20Defending%20Fine-tuning%20based%20Jailbreak%20Attack%20Before%20and%20During%20Generation/tables/f76c92043330b063ea0f117e43ef117d1ae94f3f29667dc509eb96e1d60f8f99.jpg)

## Coresets for Clustering Under Stochastic Noise


### Images

![9fc791978306fc42b973a6d41dd5fb84b9859223356c9e37d9753aa757a61699.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/images/9fc791978306fc42b973a6d41dd5fb84b9859223356c9e37d9753aa757a61699.jpg)

### Tables

![17e38db89bf9edc5ea87a8afc370db07feada64b07d87da741c76999bde6ed1a.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/17e38db89bf9edc5ea87a8afc370db07feada64b07d87da741c76999bde6ed1a.jpg)

![1e1aeddbbfb114b90a5579cfd78c37e00a5f4628f06483b43cb1ba3cf343be1b.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/1e1aeddbbfb114b90a5579cfd78c37e00a5f4628f06483b43cb1ba3cf343be1b.jpg)

![2e650acb488fe835944a263c2e588486ef55ae9e9eebfd93af708c1c98ddbada.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/2e650acb488fe835944a263c2e588486ef55ae9e9eebfd93af708c1c98ddbada.jpg)

![3b0d54a9c051f4e1f30f39099d0114ce3cd47191e4284caf2f5554ad0ac7d0cf.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/3b0d54a9c051f4e1f30f39099d0114ce3cd47191e4284caf2f5554ad0ac7d0cf.jpg)

![47dff50aca03b269b58d1da6b885a7b1bf378d9de056f2f594ae333ab0a90606.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/47dff50aca03b269b58d1da6b885a7b1bf378d9de056f2f594ae333ab0a90606.jpg)

![5f476bbb7e45aa80333dff34feb45abe92d35316c9eef87e09a8c42b84cd4ee1.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/5f476bbb7e45aa80333dff34feb45abe92d35316c9eef87e09a8c42b84cd4ee1.jpg)

![629329a6d9a3b16159a9667e1fb314493dab5271ff2e904866e537e87fb6d88f.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/629329a6d9a3b16159a9667e1fb314493dab5271ff2e904866e537e87fb6d88f.jpg)

![7d8a6af59299125bb3b6c04910053080204d44be4a974d87277c27cda2a2caad.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/7d8a6af59299125bb3b6c04910053080204d44be4a974d87277c27cda2a2caad.jpg)

![81eb708b8fcae5719746a7f502268978b25d9b3e60e7344c7c6f4a67ae34960e.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/81eb708b8fcae5719746a7f502268978b25d9b3e60e7344c7c6f4a67ae34960e.jpg)

![95f8ba2691fa3740711c151d1c5d7b1980d90eaed28d5261d9f5f4b5c5f1c053.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/95f8ba2691fa3740711c151d1c5d7b1980d90eaed28d5261d9f5f4b5c5f1c053.jpg)

![a126df18191c210506740b395ac6449a7b5730200aba0e461900f49ae88aa1bd.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/a126df18191c210506740b395ac6449a7b5730200aba0e461900f49ae88aa1bd.jpg)

![acd1d0369f1379e43b3ebf1eec44827101f9298acf048595355f61e7b0c18cae.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/acd1d0369f1379e43b3ebf1eec44827101f9298acf048595355f61e7b0c18cae.jpg)

![af0b8ca4e637ff9c889931ef5cdff4fab47e76803f5d5b91186520acf6f0b28f.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/af0b8ca4e637ff9c889931ef5cdff4fab47e76803f5d5b91186520acf6f0b28f.jpg)

![b57689445655e3aa7502efba4d1a4a253cd005607b3b86c9dc6a701afda23877.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/b57689445655e3aa7502efba4d1a4a253cd005607b3b86c9dc6a701afda23877.jpg)

![b8857a25e3d11a336d02c345e3c9425cbdac06c3857235d7c981dbd8b3dd9ba1.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/b8857a25e3d11a336d02c345e3c9425cbdac06c3857235d7c981dbd8b3dd9ba1.jpg)

![ba242aee2c465a1fda837c9f38de6bbff2ebd81171fbc8e8d3ff7138deece33d.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/ba242aee2c465a1fda837c9f38de6bbff2ebd81171fbc8e8d3ff7138deece33d.jpg)

![bae01a726bf091aeda39ca9b90efc08b9316449016cf512b1c55b8a2cf06e040.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/bae01a726bf091aeda39ca9b90efc08b9316449016cf512b1c55b8a2cf06e040.jpg)

![c74c812c3fcc449f7ce56198f18fdcd60543153648de491871750d8f01144c6d.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/c74c812c3fcc449f7ce56198f18fdcd60543153648de491871750d8f01144c6d.jpg)

![d2b5dc6adc63d2668a241658e6c8e6e6ba6de77dcf60f98803dace028fc1790e.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/d2b5dc6adc63d2668a241658e6c8e6e6ba6de77dcf60f98803dace028fc1790e.jpg)

![d73d32c6f47bdf47d1131c6bc1cbcaa5c19fd5ac41ae25aa09d235ccec025fd4.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/d73d32c6f47bdf47d1131c6bc1cbcaa5c19fd5ac41ae25aa09d235ccec025fd4.jpg)

![d7f90ca7d695b10d81b9de5265e9af4d3b4bdb244d8c72d9328682e5cd55df81.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/d7f90ca7d695b10d81b9de5265e9af4d3b4bdb244d8c72d9328682e5cd55df81.jpg)

![e26829844232293f56a38f3b9f7631819c6602c3e3ddd498f747cbd14d8f1de0.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/e26829844232293f56a38f3b9f7631819c6602c3e3ddd498f747cbd14d8f1de0.jpg)

![e2b4cb6ec979747815b8f59bbf9b1d18b79c8139160367e71878a155e9b9866b.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/e2b4cb6ec979747815b8f59bbf9b1d18b79c8139160367e71878a155e9b9866b.jpg)

![ec3b148293175969fac85c2cc5f7e232e6120e95210c1ee4c3f915ee0281b67b.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/ec3b148293175969fac85c2cc5f7e232e6120e95210c1ee4c3f915ee0281b67b.jpg)

![f040bde89aa512b88d436f185f8e71dfdb05bc8842536572ec4b17fdc617ed26.jpg](../nips_results/875_Coresets%20for%20Clustering%20Under%20Stochastic%20Noise/tables/f040bde89aa512b88d436f185f8e71dfdb05bc8842536572ec4b17fdc617ed26.jpg)

## Beyond Pairwise Connections: Extracting High-Order Functional Brain Network Structures under Global Constraints


### Images

![1d4dff81a1b3755ad992aea47f74c94a2802a5984c1864271d618035bd99e82f.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/images/1d4dff81a1b3755ad992aea47f74c94a2802a5984c1864271d618035bd99e82f.jpg)

![42bc43f9bb7ac46b78f65c513ecc4b3682d820b1c1952c4f17ac32311a76174d.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/images/42bc43f9bb7ac46b78f65c513ecc4b3682d820b1c1952c4f17ac32311a76174d.jpg)

![508672c84008a5fdb3ec7980cbabd92b29ac461fadb26ee6c82ecb8fc2d91688.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/images/508672c84008a5fdb3ec7980cbabd92b29ac461fadb26ee6c82ecb8fc2d91688.jpg)

![5a3bddbe71dbdf9f6c0d526b62be5187e534d13769d072f7190cde9d882e57f4.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/images/5a3bddbe71dbdf9f6c0d526b62be5187e534d13769d072f7190cde9d882e57f4.jpg)

![610af9241e4317752a078e813b852b2a0edf9eac95f77a8bb9b1067b4a8b30b9.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/images/610af9241e4317752a078e813b852b2a0edf9eac95f77a8bb9b1067b4a8b30b9.jpg)

![63c5f3306bf46aebcf21fe9a5ba2188d746d257d0bd383fb9154d115241d3960.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/images/63c5f3306bf46aebcf21fe9a5ba2188d746d257d0bd383fb9154d115241d3960.jpg)

![6b9bcbab0416ab6523a7b971eb1e4a7dbf86233f8535a1ca3ba1ad3453d8956c.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/images/6b9bcbab0416ab6523a7b971eb1e4a7dbf86233f8535a1ca3ba1ad3453d8956c.jpg)

![7e26231d22493d03a9ce486b91eba650224ebb18de2b2088febe58d7230d3d15.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/images/7e26231d22493d03a9ce486b91eba650224ebb18de2b2088febe58d7230d3d15.jpg)

![93654bff540eede29698580f4d6514e6a28f11bfef5ba61b08b2435455013bda.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/images/93654bff540eede29698580f4d6514e6a28f11bfef5ba61b08b2435455013bda.jpg)

![bdecb8178c327c38fe961a6429cd33a55d7654b35d7f210b5efaa65bab5d4138.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/images/bdecb8178c327c38fe961a6429cd33a55d7654b35d7f210b5efaa65bab5d4138.jpg)

### Tables

![06f754fdff5eb5ae516eb3826b2b270734909b9d73831909ba8b4d81af015550.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/tables/06f754fdff5eb5ae516eb3826b2b270734909b9d73831909ba8b4d81af015550.jpg)

![34721790f9f9258e0d2159d396496668dc8d6dd509a609a9de5778670ab0fe23.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/tables/34721790f9f9258e0d2159d396496668dc8d6dd509a609a9de5778670ab0fe23.jpg)

![5671680cde4bd8c3872d79eb6c30df1f1ee94c346874cbfacb087e346a48bee7.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/tables/5671680cde4bd8c3872d79eb6c30df1f1ee94c346874cbfacb087e346a48bee7.jpg)

![8eabcea8e61916ccd4cbb1d6683ee27cd19796f09140c06ca9f585537ef55ef0.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/tables/8eabcea8e61916ccd4cbb1d6683ee27cd19796f09140c06ca9f585537ef55ef0.jpg)

![9688128fe2ebd0b617d4057fbe569605c0776be1e2e2ec822b3958a80214ca5c.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/tables/9688128fe2ebd0b617d4057fbe569605c0776be1e2e2ec822b3958a80214ca5c.jpg)

![a2ae9059fe616b7e78daed97ed4b7c4f5ef0c93f471eefafd862d2ce1409dc10.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/tables/a2ae9059fe616b7e78daed97ed4b7c4f5ef0c93f471eefafd862d2ce1409dc10.jpg)

![a502c58bccaac5fb742612788247c36d60f4ede0321abe394746513a2d9e1dfe.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/tables/a502c58bccaac5fb742612788247c36d60f4ede0321abe394746513a2d9e1dfe.jpg)

![bbdc4b32a585279a0293615c3fff1bf1daf74c128ad94a903b4cabd1765c92d0.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/tables/bbdc4b32a585279a0293615c3fff1bf1daf74c128ad94a903b4cabd1765c92d0.jpg)

![f5ba41a4e277ba8d41a4e7f1164f130f5b41384328415b69be31ab9e22535b0b.jpg](../nips_results/876_Beyond%20Pairwise%20Connections_%20Extracting%20High-Order%20Functional%20Brain%20Network%20Structures%20under%20Global%20/tables/f5ba41a4e277ba8d41a4e7f1164f130f5b41384328415b69be31ab9e22535b0b.jpg)

## Temporal Representation Alignment: Successor Features Enable Emergent Compositionality in Robot Instruction Following


### Images

![3327ea93cd9853fc8ad767c896d5501cb696ebc7d0592a1b4c6720d5f49024e9.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/images/3327ea93cd9853fc8ad767c896d5501cb696ebc7d0592a1b4c6720d5f49024e9.jpg)

![34f335c1a2d30df681d0a4d406d21d099f9498324a56b64f61072faeed3b3bf0.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/images/34f335c1a2d30df681d0a4d406d21d099f9498324a56b64f61072faeed3b3bf0.jpg)

![3d09ca339aaf5f86568d8d17e62ca08321120d4424a5d145389c132630d07a48.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/images/3d09ca339aaf5f86568d8d17e62ca08321120d4424a5d145389c132630d07a48.jpg)

![47b44d0c0be8b5457be78502c97e2fdea1f06196c2c046da68d54e523fa15262.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/images/47b44d0c0be8b5457be78502c97e2fdea1f06196c2c046da68d54e523fa15262.jpg)

![48fd4862273f1c716e9fe555dde2382b0e1435cbf22c15fcabf28a303940a733.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/images/48fd4862273f1c716e9fe555dde2382b0e1435cbf22c15fcabf28a303940a733.jpg)

![53e94f3f24b4f5ee8195ad726cd557ef69eca690ec4fb2f90c8fb2b184b01f34.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/images/53e94f3f24b4f5ee8195ad726cd557ef69eca690ec4fb2f90c8fb2b184b01f34.jpg)

![57f35eced8c7a3e1f5cd451c36209d9685ebba356d38400df0f77f0c416435d9.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/images/57f35eced8c7a3e1f5cd451c36209d9685ebba356d38400df0f77f0c416435d9.jpg)

![9c68f082888604fe79ac5258281adfd5a80523344decc37e61f2ddc8eee8a036.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/images/9c68f082888604fe79ac5258281adfd5a80523344decc37e61f2ddc8eee8a036.jpg)

![a9c321e7cd3fbe817479ef4e73af09429a165e72d87a76e02cb0e3254105ebea.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/images/a9c321e7cd3fbe817479ef4e73af09429a165e72d87a76e02cb0e3254105ebea.jpg)

### Tables

![020d57950be2a361ec031fdc5f0fe4c603d04b943589748032a6a5654fdae775.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/tables/020d57950be2a361ec031fdc5f0fe4c603d04b943589748032a6a5654fdae775.jpg)

![0ec1bb38497d2f45a82e87d0eca527ea3c0acd064bc7fea3b9db635f2951fd7a.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/tables/0ec1bb38497d2f45a82e87d0eca527ea3c0acd064bc7fea3b9db635f2951fd7a.jpg)

![4e9b26ed2e2c331dad972b8a12c195c8ecea5c35d54712f9e8fc398ec50414b3.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/tables/4e9b26ed2e2c331dad972b8a12c195c8ecea5c35d54712f9e8fc398ec50414b3.jpg)

![5720bd98a6ab2fc85d318e13adf359929d3099c0360686bd80e0a456e0e3ee65.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/tables/5720bd98a6ab2fc85d318e13adf359929d3099c0360686bd80e0a456e0e3ee65.jpg)

![776cd08f904b5fb457820d16f33cf5f2b24a3c0979e0dcadac89f490f8b79907.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/tables/776cd08f904b5fb457820d16f33cf5f2b24a3c0979e0dcadac89f490f8b79907.jpg)

![9a6eb3effe305c4c405cf787e75fe8ac1129b2d0ad7376199d5247f1a5e76eec.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/tables/9a6eb3effe305c4c405cf787e75fe8ac1129b2d0ad7376199d5247f1a5e76eec.jpg)

![cbec59f4734469b0b0c934bc4e84d9a018001c542cd79997020dd52fea9a3ef6.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/tables/cbec59f4734469b0b0c934bc4e84d9a018001c542cd79997020dd52fea9a3ef6.jpg)

![d1feff784f9c4e302cfc087c8e8e5309f976491f12d42d91de232fc9ba84c4aa.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/tables/d1feff784f9c4e302cfc087c8e8e5309f976491f12d42d91de232fc9ba84c4aa.jpg)

![da8096085fef8f59becaa3adc1d802ac17a81293b1dad72b52a16bf85e1be978.jpg](../nips_results/877_Temporal%20Representation%20Alignment_%20Successor%20Features%20Enable%20Emergent%20Compositionality%20in%20Robot%20Inst/tables/da8096085fef8f59becaa3adc1d802ac17a81293b1dad72b52a16bf85e1be978.jpg)

## Optimizing Retrieval for RAG via Reinforced Contrastive Learning

### Images

![0801245c739c76d2a0632a199b9906c8e13489b6f102e414a4844a649f93022b.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/0801245c739c76d2a0632a199b9906c8e13489b6f102e414a4844a649f93022b.jpg)

![159fd84feb73b3d0fcfe6d9be160e45eec4bffcfa485013a76d1c72d433bb5c2.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/159fd84feb73b3d0fcfe6d9be160e45eec4bffcfa485013a76d1c72d433bb5c2.jpg)

![23b011205d4c39eb697bb382c8f5852a405307a13967070c47aca6468d22afab.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/23b011205d4c39eb697bb382c8f5852a405307a13967070c47aca6468d22afab.jpg)

![2fd5bbcb237773e9fae45c7575e1521bcd6f3453368a0515ef6e6171077756d1.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/2fd5bbcb237773e9fae45c7575e1521bcd6f3453368a0515ef6e6171077756d1.jpg)

![3e5a8acaf8a15469deeae927bf28c442ce39afd0b2b91df1ccafba93e690347e.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/3e5a8acaf8a15469deeae927bf28c442ce39afd0b2b91df1ccafba93e690347e.jpg)

![40dabb33063da5abdff19d8fbaa24017bb54a04ab9a127082e13634868f11545.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/40dabb33063da5abdff19d8fbaa24017bb54a04ab9a127082e13634868f11545.jpg)

![42abc73cd89af4e47b4a6c50f896b5cc3189a82ed2619317b3eaf1cf94c73b8d.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/42abc73cd89af4e47b4a6c50f896b5cc3189a82ed2619317b3eaf1cf94c73b8d.jpg)

![6f5c6421f306311805e40769d13ac3a37690cc1c9473d7ea5f431257e0f2fed6.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/6f5c6421f306311805e40769d13ac3a37690cc1c9473d7ea5f431257e0f2fed6.jpg)

![99006e7d5f4fecd64c7460da984b4c0d72639346935310fce23f990b93693f70.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/99006e7d5f4fecd64c7460da984b4c0d72639346935310fce23f990b93693f70.jpg)

![aa76658481263de6c9648e7fae5384b166840a4ab2dd527352a0d37ee0eb2d26.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/aa76658481263de6c9648e7fae5384b166840a4ab2dd527352a0d37ee0eb2d26.jpg)

![dba4ec12fef94bb413e6fe05d45f537c5b5c61178c07969ff7d22635f4a6f3da.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/dba4ec12fef94bb413e6fe05d45f537c5b5c61178c07969ff7d22635f4a6f3da.jpg)

![eb38c1e5f585f3d7046e86564dcd0dbd71c6eda1ccb069012aaf52e8e9d88a0a.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/eb38c1e5f585f3d7046e86564dcd0dbd71c6eda1ccb069012aaf52e8e9d88a0a.jpg)

![f1e36e6f966118c7d1d05f66d3e9cc451c506926fd72c5df955110042ee231e1.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/f1e36e6f966118c7d1d05f66d3e9cc451c506926fd72c5df955110042ee231e1.jpg)

![f818218140da7493fc9793a52f3bb7a373b2e80460de958b2fff7aecfda845f0.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/images/f818218140da7493fc9793a52f3bb7a373b2e80460de958b2fff7aecfda845f0.jpg)

### Tables

![0ea9c16daf41d226faadd24234071393f121b7f3944002809276818cfce30ef5.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/tables/0ea9c16daf41d226faadd24234071393f121b7f3944002809276818cfce30ef5.jpg)

![2000cf31760b88a7e944c0897b115113a3e183cc039fb38052140a42c3da1707.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/tables/2000cf31760b88a7e944c0897b115113a3e183cc039fb38052140a42c3da1707.jpg)

![4c5e3897a157ece8ef5171ebc8a523986ada7c71f9e7c4903addb8f58012deb2.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/tables/4c5e3897a157ece8ef5171ebc8a523986ada7c71f9e7c4903addb8f58012deb2.jpg)

![89b911a98b3c2cc0882aa9de1a6c0a9da9e7c1431ce089d8d4be5b565afe1f98.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/tables/89b911a98b3c2cc0882aa9de1a6c0a9da9e7c1431ce089d8d4be5b565afe1f98.jpg)

![c2914c067e0aa49f0e75b9cd1c7cc53296eaef77c133b661a45674aa32300925.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/tables/c2914c067e0aa49f0e75b9cd1c7cc53296eaef77c133b661a45674aa32300925.jpg)

![d6d3750bb45547f9bbb785bbfceac7478527921084b35a70eb6b261d729fc50a.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/tables/d6d3750bb45547f9bbb785bbfceac7478527921084b35a70eb6b261d729fc50a.jpg)

![e3e9e692cad2b03c79e69492f0f4b05bd63b3c2cfe7db476c6a5acfe22701eb6.jpg](../nips_results/878_Optimizing%20Retrieval%20for%20RAG%20via%20Reinforced%20Contrastive%20Learning/tables/e3e9e692cad2b03c79e69492f0f4b05bd63b3c2cfe7db476c6a5acfe22701eb6.jpg)
