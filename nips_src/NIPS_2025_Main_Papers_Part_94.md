# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 94 of 130

## 目录 (Table of Contents)

1. [Self-Adapting Language Models](#Self-Adapting-Language-Models)
2. [Reparameterized LLM Training via Orthogonal Equivalence Transformation](#Reparameterized-LLM-Training-via-Orthogonal-Equivalence-Transformation)
3. [You Can Trust Your Clustering Model: A Parameter-free Self-Boosting Plug-in for Deep Clustering](#You-Can-Trust-Your-Clustering-Model-A-Parameter-free-Self-Boosting-Plug-in-for-Deep-Clustering)
4. [CGS-GAN: 3D Consistent Gaussian Splatting GANs for High Resolution Human Head Synthesis](#CGS-GAN-3D-Consistent-Gaussian-Splatting-GANs-for-High-Resolution-Human-Head-Synthesis)
5. [Quantum Visual Fields with Neural Amplitude Encoding](#Quantum-Visual-Fields-with-Neural-Amplitude-Encoding)
6. [ReMindRAG: Low-Cost LLM-Guided Knowledge Graph Traversal for Efficient RAG](#ReMindRAG-Low-Cost-LLM-Guided-Knowledge-Graph-Traversal-for-Efficient-RAG)
7. [xLSTM-Mixer: Multivariate Time Series Forecasting by Mixing via Scalar Memories](#xLSTM-Mixer-Multivariate-Time-Series-Forecasting-by-Mixing-via-Scalar-Memories)
8. [SMARTraj$^2$: A Stable Multi-City Adaptive Method for Multi-View Spatio-Temporal Trajectory Representation Learning](#SMARTraj2-A-Stable-Multi-City-Adaptive-Method-for-Multi-View-Spatio-Temporal-Trajectory-Representation-Learning)
9. [TopER: Topological Embeddings in Graph Representation Learning](#TopER-Topological-Embeddings-in-Graph-Representation-Learning)
10. [Geometry of Decision Making in Language Models](#Geometry-of-Decision-Making-in-Language-Models)
11. [LayerIF: Estimating Layer Quality for Large Language Models using Influence Functions](#LayerIF-Estimating-Layer-Quality-for-Large-Language-Models-using-Influence-Functions)
12. [Amortized Sampling with Transferable Normalizing Flows](#Amortized-Sampling-with-Transferable-Normalizing-Flows)
13. [BridgePure: Limited Protection Leakage Can Break Black-Box Data Protection](#BridgePure-Limited-Protection-Leakage-Can-Break-Black-Box-Data-Protection)
14. [SPC: Evolving Self-Play Critic via Adversarial Games for LLM Reasoning](#SPC-Evolving-Self-Play-Critic-via-Adversarial-Games-for-LLM-Reasoning)
15. [Unsupervised Learning for Optimal Transport plan prediction between unbalanced graphs](#Unsupervised-Learning-for-Optimal-Transport-plan-prediction-between-unbalanced-graphs)
16. [Simplicity Prevails: Rethinking Negative Preference Optimization for LLM Unlearning](#Simplicity-Prevails-Rethinking-Negative-Preference-Optimization-for-LLM-Unlearning)
17. [OmniConsistency: Learning Style-Agnostic Consistency from Paired Stylization Data](#OmniConsistency-Learning-Style-Agnostic-Consistency-from-Paired-Stylization-Data)
18. [High-order Interactions Modeling for Interpretable Multi-Agent Q-Learning](#High-order-Interactions-Modeling-for-Interpretable-Multi-Agent-Q-Learning)
19. [Quantum Speedups for Minimax Optimization and Beyond](#Quantum-Speedups-for-Minimax-Optimization-and-Beyond)
20. [Graph-based Symbolic Regression with Invariance and Constraint Encoding](#Graph-based-Symbolic-Regression-with-Invariance-and-Constraint-Encoding)
21. [Harnessing Feature Resonance under Arbitrary Target Alignment for Out-of-Distribution Node Detection](#Harnessing-Feature-Resonance-under-Arbitrary-Target-Alignment-for-Out-of-Distribution-Node-Detection)
22. [Cost-Efficient LLM Training with Lifetime-Aware Tensor Offloading via GPUDirect Storage](#Cost-Efficient-LLM-Training-with-Lifetime-Aware-Tensor-Offloading-via-GPUDirect-Storage)
23. [Constrained Best Arm Identification](#Constrained-Best-Arm-Identification)
24. [Generalizable Hand-Object Modeling from Monocular RGB Images via 3D Gaussians](#Generalizable-Hand-Object-Modeling-from-Monocular-RGB-Images-via-3D-Gaussians)
25. [FerretNet: Efficient Synthetic Image Detection via Local Pixel Dependencies](#FerretNet-Efficient-Synthetic-Image-Detection-via-Local-Pixel-Dependencies)
26. [Towards Multiscale Graph-based Protein Learning with Geometric Secondary Structural Motifs](#Towards-Multiscale-Graph-based-Protein-Learning-with-Geometric-Secondary-Structural-Motifs)
27. [FracFace: Breaking The Visual Clues—Fractal-Based Privacy-Preserving Face Recognition](#FracFace-Breaking-The-Visual-CluesFractal-Based-Privacy-Preserving-Face-Recognition)
28. [GRAPE: Optimize Data Mixture for Group Robust Multi-target Adaptive Pretraining](#GRAPE-Optimize-Data-Mixture-for-Group-Robust-Multi-target-Adaptive-Pretraining)
29. [RL Tango: Reinforcing Generator and Verifier Together for Language Reasoning](#RL-Tango-Reinforcing-Generator-and-Verifier-Together-for-Language-Reasoning)
30. [Stab-SGD: Noise-Adaptivity in Smooth Optimization with Stability Ratios](#Stab-SGD-Noise-Adaptivity-in-Smooth-Optimization-with-Stability-Ratios)
31. [What Really is a Member? Discrediting Membership Inference via Poisoning](#What-Really-is-a-Member-Discrediting-Membership-Inference-via-Poisoning)
32. [Brain-Informed Fine-Tuning for Improved Multilingual Understanding in Language Models](#Brain-Informed-Fine-Tuning-for-Improved-Multilingual-Understanding-in-Language-Models)
33. [MoleBridge: Synthetic Space Projecting with Discrete Markov Bridges](#MoleBridge-Synthetic-Space-Projecting-with-Discrete-Markov-Bridges)
34. [Generative Modeling of Full-Atom Protein Conformations using Latent Diffusion on Graph Embeddings](#Generative-Modeling-of-Full-Atom-Protein-Conformations-using-Latent-Diffusion-on-Graph-Embeddings)
35. [Feature Unlearning: Theoretical Foundations and Practical Applications with Shuffling](#Feature-Unlearning-Theoretical-Foundations-and-Practical-Applications-with-Shuffling)
36. [Unified all-atom molecule generation with neural fields](#Unified-all-atom-molecule-generation-with-neural-fields)
37. [Contrastive Learning with Data Misalignment: Feature Purity, Training Dynamics and Theoretical Generalization Guarantees](#Contrastive-Learning-with-Data-Misalignment-Feature-Purity-Training-Dynamics-and-Theoretical-Generalization-Guarantees)
38. [Covering Multiple Objectives with a Small Set of Solutions Using Bayesian Optimization](#Covering-Multiple-Objectives-with-a-Small-Set-of-Solutions-Using-Bayesian-Optimization)
39. [StegoZip: Enhancing Linguistic Steganography Payload in Practice with Large Language Models](#StegoZip-Enhancing-Linguistic-Steganography-Payload-in-Practice-with-Large-Language-Models)
40. [Scalable Policy-Based RL Algorithms for POMDPs](#Scalable-Policy-Based-RL-Algorithms-for-POMDPs)
41. [Decreasing Entropic Regularization Averaged Gradient for Semi-Discrete Optimal Transport](#Decreasing-Entropic-Regularization-Averaged-Gradient-for-Semi-Discrete-Optimal-Transport)

---


## Self-Adapting Language Models

### Images

![2d7662235fc48988c58a1088994634586955e530ba48c4f949733b47f051d7d9.jpg](../nips_results/3853_The%20Cost%20of%20Robustness_%20Tighter%20Bounds%20on%20Parameter%20Complexity%20for%20Robust%20Memorization%20in%20ReLU%20Nets/images/2d7662235fc48988c58a1088994634586955e530ba48c4f949733b47f051d7d9.jpg)

![4f1dfee03168340f2cae775cad14e5837e36f5135c2efe0385bfb56002700e90.jpg](../nips_results/3853_The%20Cost%20of%20Robustness_%20Tighter%20Bounds%20on%20Parameter%20Complexity%20for%20Robust%20Memorization%20in%20ReLU%20Nets/images/4f1dfee03168340f2cae775cad14e5837e36f5135c2efe0385bfb56002700e90.jpg)

![ba5728a09bb86b2fa342c8ff7f376a1364e003df9a55925a65d92c82c60c91a2.jpg](../nips_results/3853_The%20Cost%20of%20Robustness_%20Tighter%20Bounds%20on%20Parameter%20Complexity%20for%20Robust%20Memorization%20in%20ReLU%20Nets/images/ba5728a09bb86b2fa342c8ff7f376a1364e003df9a55925a65d92c82c60c91a2.jpg)

![d18f18fac81814c6303520aee87c6cacb7b1453874b149ccbc629b93779bb9cd.jpg](../nips_results/3853_The%20Cost%20of%20Robustness_%20Tighter%20Bounds%20on%20Parameter%20Complexity%20for%20Robust%20Memorization%20in%20ReLU%20Nets/images/d18f18fac81814c6303520aee87c6cacb7b1453874b149ccbc629b93779bb9cd.jpg)

![d32d9391b65df1c10fa547e1fbf74aeb866bd59bb665c8da145d291140abf7bd.jpg](../nips_results/3853_The%20Cost%20of%20Robustness_%20Tighter%20Bounds%20on%20Parameter%20Complexity%20for%20Robust%20Memorization%20in%20ReLU%20Nets/images/d32d9391b65df1c10fa547e1fbf74aeb866bd59bb665c8da145d291140abf7bd.jpg)

![df215bdfb0cd1ff89a237c1c71420c2c7d2b05604119f3c7eda097db05607752.jpg](../nips_results/3853_The%20Cost%20of%20Robustness_%20Tighter%20Bounds%20on%20Parameter%20Complexity%20for%20Robust%20Memorization%20in%20ReLU%20Nets/images/df215bdfb0cd1ff89a237c1c71420c2c7d2b05604119f3c7eda097db05607752.jpg)

![ed5e1c0d71916b78a457c3a640506019bba92a74f0434bd713109def5b333723.jpg](../nips_results/3853_The%20Cost%20of%20Robustness_%20Tighter%20Bounds%20on%20Parameter%20Complexity%20for%20Robust%20Memorization%20in%20ReLU%20Nets/images/ed5e1c0d71916b78a457c3a640506019bba92a74f0434bd713109def5b333723.jpg)

![f15cca9b4f60d1df8542520843546c2d140bb84a13201dbb73150c1e32bca60a.jpg](../nips_results/3853_The%20Cost%20of%20Robustness_%20Tighter%20Bounds%20on%20Parameter%20Complexity%20for%20Robust%20Memorization%20in%20ReLU%20Nets/images/f15cca9b4f60d1df8542520843546c2d140bb84a13201dbb73150c1e32bca60a.jpg)

![f2dda56c93ae81a5f222ecaf7d6b17e7e3cbe2a745f2f19a00d26973bc276be7.jpg](../nips_results/3853_The%20Cost%20of%20Robustness_%20Tighter%20Bounds%20on%20Parameter%20Complexity%20for%20Robust%20Memorization%20in%20ReLU%20Nets/images/f2dda56c93ae81a5f222ecaf7d6b17e7e3cbe2a745f2f19a00d26973bc276be7.jpg)

![f32adacad539c5986f24af7403b7f4ace04f7461b2e405c1eee08df4b0390a64.jpg](../nips_results/3853_The%20Cost%20of%20Robustness_%20Tighter%20Bounds%20on%20Parameter%20Complexity%20for%20Robust%20Memorization%20in%20ReLU%20Nets/images/f32adacad539c5986f24af7403b7f4ace04f7461b2e405c1eee08df4b0390a64.jpg)

### Tables

![2ec595167971654b2476bd08b7716c7bf3004996a76a0e5a50fc3ddd8931f27e.jpg](../nips_results/3853_The%20Cost%20of%20Robustness_%20Tighter%20Bounds%20on%20Parameter%20Complexity%20for%20Robust%20Memorization%20in%20ReLU%20Nets/tables/2ec595167971654b2476bd08b7716c7bf3004996a76a0e5a50fc3ddd8931f27e.jpg)

## Self-Adapting Language Models


### Images

![0920bc25b8a0333e379f0ab7f7e42325bfbb5d77737dd15e866688b477a4d586.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/images/0920bc25b8a0333e379f0ab7f7e42325bfbb5d77737dd15e866688b477a4d586.jpg)

![1763f61c8605575b22f8edf2018ac55053f9440361d0cbf4e71959a1fbb44ac5.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/images/1763f61c8605575b22f8edf2018ac55053f9440361d0cbf4e71959a1fbb44ac5.jpg)

![39e28e43d12ab0ea312bd2d609c00ba0747a78e41b4d7069009fb26c7f7b311e.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/images/39e28e43d12ab0ea312bd2d609c00ba0747a78e41b4d7069009fb26c7f7b311e.jpg)

![5942353fd2a2c68561bd7a83e9261f17223c3ca136348aeca775a1ba56bd12f6.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/images/5942353fd2a2c68561bd7a83e9261f17223c3ca136348aeca775a1ba56bd12f6.jpg)

![8a26f70fdf8290b4b467ab149f8ff515e5d607a4eac1b68cc17c7f290b35f83f.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/images/8a26f70fdf8290b4b467ab149f8ff515e5d607a4eac1b68cc17c7f290b35f83f.jpg)

![b39fcfdbb74306896c32c39c1fadec99a9d88fb88fb35f6de9680d3cf9269a51.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/images/b39fcfdbb74306896c32c39c1fadec99a9d88fb88fb35f6de9680d3cf9269a51.jpg)

![fee9bf317f598df06200f811c961aab967e09d7fcc6e33fa477fb8f4df261faf.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/images/fee9bf317f598df06200f811c961aab967e09d7fcc6e33fa477fb8f4df261faf.jpg)

### Tables

![12edf5d77052ce45ec4c0753bb6948f8a8324387b319c2ff9e3e6458a7d97b0f.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/12edf5d77052ce45ec4c0753bb6948f8a8324387b319c2ff9e3e6458a7d97b0f.jpg)

![27a76de0d5530affd6d829b7d846ec4be22c2b6bf40a3dec0f0b4d905a211d68.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/27a76de0d5530affd6d829b7d846ec4be22c2b6bf40a3dec0f0b4d905a211d68.jpg)

![50f45443bc82ca18937d31733f31a0b55baf4f950eb5383c4c70d8c0cc2dc336.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/50f45443bc82ca18937d31733f31a0b55baf4f950eb5383c4c70d8c0cc2dc336.jpg)

![526f90b3f09e91c989761c3988fcfd8f4c0b8db6cf4eec3602645278571939ca.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/526f90b3f09e91c989761c3988fcfd8f4c0b8db6cf4eec3602645278571939ca.jpg)

![5386ce6561b17da1ff0e5d611892b0c7c74255990d74dbbf03967be59a2b85e2.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/5386ce6561b17da1ff0e5d611892b0c7c74255990d74dbbf03967be59a2b85e2.jpg)

![6a7eefc3841741bcdb51243233e3f66bf9b0fff4346ff1b1e940fb56c0ba0721.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/6a7eefc3841741bcdb51243233e3f66bf9b0fff4346ff1b1e940fb56c0ba0721.jpg)

![9b32d33353d1a80106e251403febed137fbac05e1cf128446ae3c0288e911980.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/9b32d33353d1a80106e251403febed137fbac05e1cf128446ae3c0288e911980.jpg)

![b2c47874971d17b0463cdefa64d774696363928ccc2c2bc87895cdff7893bda5.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/b2c47874971d17b0463cdefa64d774696363928ccc2c2bc87895cdff7893bda5.jpg)

![bb9c73393f0172a10bab6e9560a4c0b1a9d87df32f9b8d2d6100b99c7c713b78.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/bb9c73393f0172a10bab6e9560a4c0b1a9d87df32f9b8d2d6100b99c7c713b78.jpg)

![ce51d8352bb131350a116910b3462e28b996e1c5420600b22b6516620170584b.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/ce51d8352bb131350a116910b3462e28b996e1c5420600b22b6516620170584b.jpg)

![ce9c9529e70db29790bcb4504947079b895fecadb10059d2136be72b39b0e863.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/ce9c9529e70db29790bcb4504947079b895fecadb10059d2136be72b39b0e863.jpg)

![d9523907c13227e585ed8b36436d0f79aae4df1c6f08d586c5810168ae87665f.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/d9523907c13227e585ed8b36436d0f79aae4df1c6f08d586c5810168ae87665f.jpg)

![ea3075f1c9c742c666367597feef4e05b86f126a212226bfad7ddb9e04f2f802.jpg](../nips_results/3854_Self-Adapting%20Language%20Models/tables/ea3075f1c9c742c666367597feef4e05b86f126a212226bfad7ddb9e04f2f802.jpg)

## Reparameterized LLM Training via Orthogonal Equivalence Transformation


### Images

![1431ce39faf1120baee6609ab494546789de966c39be279ea1e00036c8e12503.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/1431ce39faf1120baee6609ab494546789de966c39be279ea1e00036c8e12503.jpg)

![1e6bb4f1c1b86d1a5a681b5511c230fb7acebfa22c8b1090830bce4a8be07fc4.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/1e6bb4f1c1b86d1a5a681b5511c230fb7acebfa22c8b1090830bce4a8be07fc4.jpg)

![26f33b71e02568fd206475812deb5863e962ec08a20d4aded9157362c0976f28.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/26f33b71e02568fd206475812deb5863e962ec08a20d4aded9157362c0976f28.jpg)

![3762c4539d6807414b63d0278f473b2afea2976000f8854eb1fc73ab37573f79.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/3762c4539d6807414b63d0278f473b2afea2976000f8854eb1fc73ab37573f79.jpg)

![3f30f5c95549bcd50b7e31fa12e2a5994452fce420befeeb3ad17e157daec124.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/3f30f5c95549bcd50b7e31fa12e2a5994452fce420befeeb3ad17e157daec124.jpg)

![477d69d57ceed2356eb838ed74044716c23dbdc377721d363aea6357346b3575.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/477d69d57ceed2356eb838ed74044716c23dbdc377721d363aea6357346b3575.jpg)

![53fab42f44fd1b71803105f0a281b207c63ca0e005d896e78aeb937e0ef5abbd.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/53fab42f44fd1b71803105f0a281b207c63ca0e005d896e78aeb937e0ef5abbd.jpg)

![577fe5f1d041b330901d95aa00ade5c68cee76eb4d4a6bb12417f263ac7d5d7e.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/577fe5f1d041b330901d95aa00ade5c68cee76eb4d4a6bb12417f263ac7d5d7e.jpg)

![665c83a63b18175ff1adf40906462e210b25019027bcbf117463fa0e55240c19.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/665c83a63b18175ff1adf40906462e210b25019027bcbf117463fa0e55240c19.jpg)

![6f30b05ee3c94611f62a58565c14a1e18ef2e15fa6a3477d0343f9e8b0447892.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/6f30b05ee3c94611f62a58565c14a1e18ef2e15fa6a3477d0343f9e8b0447892.jpg)

![744fd5905bab8d222020edb6f5b1b90517efb39f678d0b24e75690bc4f70eb9e.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/744fd5905bab8d222020edb6f5b1b90517efb39f678d0b24e75690bc4f70eb9e.jpg)

![789e43e1026fb44e8211a6f6818bbc8c2e286d2bdf9d2af26c257392aa850e49.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/789e43e1026fb44e8211a6f6818bbc8c2e286d2bdf9d2af26c257392aa850e49.jpg)

![88560412c355b4532a4c8c0d226e32ab33ccbafbf288e9b3ba415ae2584345e2.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/88560412c355b4532a4c8c0d226e32ab33ccbafbf288e9b3ba415ae2584345e2.jpg)

![9b6bfd80670bbae8e5d8b136fd6315aec5a67a89ca2bbb514d36d53dd012e645.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/9b6bfd80670bbae8e5d8b136fd6315aec5a67a89ca2bbb514d36d53dd012e645.jpg)

![9f2e6b6402fef9d8dbc860d731445edbad17a2b1c6c38f9c34c88d33bc8da40a.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/9f2e6b6402fef9d8dbc860d731445edbad17a2b1c6c38f9c34c88d33bc8da40a.jpg)

![a69841e613ff2693a8fdd26e473e65d4092edc016bd9e608eb1de59ffb7628e4.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/a69841e613ff2693a8fdd26e473e65d4092edc016bd9e608eb1de59ffb7628e4.jpg)

![b5e3fb230aef57941d1d2d2a899c8ad556f5da50dd446aa8d65f4e1a69e273d4.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/b5e3fb230aef57941d1d2d2a899c8ad556f5da50dd446aa8d65f4e1a69e273d4.jpg)

![ba67fc178195915652e8a4baa1bb766614d5d67be04e9b289bcaff90a643522a.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/ba67fc178195915652e8a4baa1bb766614d5d67be04e9b289bcaff90a643522a.jpg)

![c726089faa44d815272c54d381df8294f514d2457e74e930ec244340b4100ca5.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/c726089faa44d815272c54d381df8294f514d2457e74e930ec244340b4100ca5.jpg)

![db1c72da04fb2e3e90e87b920dd36a88fc70a5b81a509b861636e802d5f6e06d.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/db1c72da04fb2e3e90e87b920dd36a88fc70a5b81a509b861636e802d5f6e06d.jpg)

![de543804844d6b7a8c85353934dbe8ce0bd74e3d1eeb2c9ac6109528f38a6086.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/de543804844d6b7a8c85353934dbe8ce0bd74e3d1eeb2c9ac6109528f38a6086.jpg)

![eb34d2df836a47649b6ceb271854043f0ada6f7ca740227dfc06a842ed395788.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/eb34d2df836a47649b6ceb271854043f0ada6f7ca740227dfc06a842ed395788.jpg)

![f1a2d4dd8db9f710524f427fca2411ee26f904c38c5c06958fba88a48b6f5368.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/f1a2d4dd8db9f710524f427fca2411ee26f904c38c5c06958fba88a48b6f5368.jpg)

![f69a4402da072e06a639809a231b26c96cf7e7dc2171ff3e95c5a4c5b5ec5fdb.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/f69a4402da072e06a639809a231b26c96cf7e7dc2171ff3e95c5a4c5b5ec5fdb.jpg)

![f9339b99aa20611b7c524645af9a7a32b132070ea972850f57c6362e497f9e12.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/f9339b99aa20611b7c524645af9a7a32b132070ea972850f57c6362e497f9e12.jpg)

![fda902aad8422b69b9175d659fcc98239e12d215ce57953cb02c2bb929063603.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/images/fda902aad8422b69b9175d659fcc98239e12d215ce57953cb02c2bb929063603.jpg)

### Tables

![2522795897307dfe41cf28d5a836cb84411a6ffc84c3fd2a86a047b34e13e498.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/2522795897307dfe41cf28d5a836cb84411a6ffc84c3fd2a86a047b34e13e498.jpg)

![6c3f08547708e87c0fd67cfda699482a2a065aa5e795357641c2e79e2d54eb17.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/6c3f08547708e87c0fd67cfda699482a2a065aa5e795357641c2e79e2d54eb17.jpg)

![97cad5fe82f0da40a4abea9fca0d9f7f5b615d81bd8389063cd502722b44d217.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/97cad5fe82f0da40a4abea9fca0d9f7f5b615d81bd8389063cd502722b44d217.jpg)

![9b95ec8deaed4fd14d25c49ee5c97fc78c6db71ca6db5f6bbd3a43a23c0dd75d.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/9b95ec8deaed4fd14d25c49ee5c97fc78c6db71ca6db5f6bbd3a43a23c0dd75d.jpg)

![aa704ef0525bebf1677f5115cffda93bd19bb0691e69902653d31dd577c713a2.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/aa704ef0525bebf1677f5115cffda93bd19bb0691e69902653d31dd577c713a2.jpg)

![ba86cb482fd3e882a567a692f67337e62137841d85d1ffd8d675952d3c2293f9.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/ba86cb482fd3e882a567a692f67337e62137841d85d1ffd8d675952d3c2293f9.jpg)

![bd9b9b331f99d849a7d492a443ffd6c6af3711257370b89e460cef1931b51f70.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/bd9b9b331f99d849a7d492a443ffd6c6af3711257370b89e460cef1931b51f70.jpg)

![cde25fdebe2630f884e86a5881c7a2b3b2de6e6c90274bac2340b3336417df1b.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/cde25fdebe2630f884e86a5881c7a2b3b2de6e6c90274bac2340b3336417df1b.jpg)

![e14947311b5b1eb6696d58fa672f1da7ab84ec94c1eb163523e3931055d164ed.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/e14947311b5b1eb6696d58fa672f1da7ab84ec94c1eb163523e3931055d164ed.jpg)

![e183e8e2ec60d0a175028dcd29be7b0f61001dec83b28438c3e676f8fd6f5a6c.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/e183e8e2ec60d0a175028dcd29be7b0f61001dec83b28438c3e676f8fd6f5a6c.jpg)

![ebc3f7e1895659cc0caedae5365feac96f5c847f91116115cad0da0ffb0cb341.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/ebc3f7e1895659cc0caedae5365feac96f5c847f91116115cad0da0ffb0cb341.jpg)

![f16aec51b2105fb67a68ad1944b4ddb56213bc36e46088dbc073faf1c70897b2.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/f16aec51b2105fb67a68ad1944b4ddb56213bc36e46088dbc073faf1c70897b2.jpg)

![f54a1887e29adea73e54cc8bf323ad94cad854d6e0f37fa26d33fc00be8774a4.jpg](../nips_results/3855_Reparameterized%20LLM%20Training%20via%20Orthogonal%20Equivalence%20Transformation/tables/f54a1887e29adea73e54cc8bf323ad94cad854d6e0f37fa26d33fc00be8774a4.jpg)

## You Can Trust Your Clustering Model: A Parameter-free Self-Boosting Plug-in for Deep Clustering


### Images

![23af66c568c7d12deb56f04e201c68562ad1dce88557efa11500659dfcf9f581.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/images/23af66c568c7d12deb56f04e201c68562ad1dce88557efa11500659dfcf9f581.jpg)

![3779c270b338b9e447587d02c0ec1dcf0ed548e2111c8fd1783fa4a2ccd69f20.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/images/3779c270b338b9e447587d02c0ec1dcf0ed548e2111c8fd1783fa4a2ccd69f20.jpg)

![3ad70ff44c40d369edbd34bd9f12b5840d9bc8bb35b5245e6e8a122313f532db.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/images/3ad70ff44c40d369edbd34bd9f12b5840d9bc8bb35b5245e6e8a122313f532db.jpg)

![4db3b6329070f626705c1368a3e5f5cfb4f9631458dbf44f50e0d00a167aac27.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/images/4db3b6329070f626705c1368a3e5f5cfb4f9631458dbf44f50e0d00a167aac27.jpg)

![52daeb8b1847e7840b30654e2b37c0b982d596f06e5e585207009faf7154e626.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/images/52daeb8b1847e7840b30654e2b37c0b982d596f06e5e585207009faf7154e626.jpg)

![5b2515f7c737a6233febca4f59ea6afbb3ad6bc4307221a97148dbb053702738.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/images/5b2515f7c737a6233febca4f59ea6afbb3ad6bc4307221a97148dbb053702738.jpg)

![5d2f5385e453cba23ba54963228448a77252ceb22a1abe0d49cc0920252d1c42.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/images/5d2f5385e453cba23ba54963228448a77252ceb22a1abe0d49cc0920252d1c42.jpg)

![82fcd72870ec0dd2a533a4ebf31174e5593267ded627fd6a8021089520fb64d5.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/images/82fcd72870ec0dd2a533a4ebf31174e5593267ded627fd6a8021089520fb64d5.jpg)

![87023a871169a4f6a42b7f951e9236a331baf6ed3fc413666cf7a5e5802badbb.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/images/87023a871169a4f6a42b7f951e9236a331baf6ed3fc413666cf7a5e5802badbb.jpg)

![9e76dac6efb5256a74c7e0d025cca959019dea77da8dc69c4296558d9667d12c.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/images/9e76dac6efb5256a74c7e0d025cca959019dea77da8dc69c4296558d9667d12c.jpg)

![be076f9dd736b3ca4948307d7db134312addfb013cecece5da9c26b7400792cd.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/images/be076f9dd736b3ca4948307d7db134312addfb013cecece5da9c26b7400792cd.jpg)

### Tables

![01c5d48bd8a0b72a3975b830e8c1973c0053f69c017f2fbf66d1e4117d86a7ef.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/01c5d48bd8a0b72a3975b830e8c1973c0053f69c017f2fbf66d1e4117d86a7ef.jpg)

![04176896b9cc340b73483a419a204e30799e6b0a2f02de5e1b4265332ac4a884.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/04176896b9cc340b73483a419a204e30799e6b0a2f02de5e1b4265332ac4a884.jpg)

![116d2561355a8c6494f5ec8a9b724a0d6f2070c0677ad13879000e935693e57e.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/116d2561355a8c6494f5ec8a9b724a0d6f2070c0677ad13879000e935693e57e.jpg)

![18a23527fd0db4734aae87d3cbeddf23d981c2ca8fc0e6e3237df64e7a0c7fde.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/18a23527fd0db4734aae87d3cbeddf23d981c2ca8fc0e6e3237df64e7a0c7fde.jpg)

![1bd2dbd7f3bd07d3cf5bb9d6c2e58d6149febded8b5e6206b8ccca40b7eb9917.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/1bd2dbd7f3bd07d3cf5bb9d6c2e58d6149febded8b5e6206b8ccca40b7eb9917.jpg)

![221f8e68f0f4a04936c66a31776f0c68ab1122889209af01c0255da289d0d981.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/221f8e68f0f4a04936c66a31776f0c68ab1122889209af01c0255da289d0d981.jpg)

![249b9d8f1bff35a45c2dd290494bf4b7dfbc149179a46dc83cce6b5ff47f8399.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/249b9d8f1bff35a45c2dd290494bf4b7dfbc149179a46dc83cce6b5ff47f8399.jpg)

![3a4a9088baeeb43ef231e20f67a435e7ae4015ef7d72a6d34865d4a4e30edbaf.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/3a4a9088baeeb43ef231e20f67a435e7ae4015ef7d72a6d34865d4a4e30edbaf.jpg)

![3c4ae7f685d2b29af43cc21ddd2b3606dab9e7be2f6494c50503096ab6ce9cd2.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/3c4ae7f685d2b29af43cc21ddd2b3606dab9e7be2f6494c50503096ab6ce9cd2.jpg)

![4d756f075bad7da5de1f8d96d60cdc66ae3d668ede89364c91d9ff154708cff5.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/4d756f075bad7da5de1f8d96d60cdc66ae3d668ede89364c91d9ff154708cff5.jpg)

![5a86980696b3c0537632d5f07c098c73ce6040345a6ee9427087cfb8d97df8c4.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/5a86980696b3c0537632d5f07c098c73ce6040345a6ee9427087cfb8d97df8c4.jpg)

![690012393f4ef7741ddcbfcc90c5ac824ebc1a34216531c28c90ded9f968727c.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/690012393f4ef7741ddcbfcc90c5ac824ebc1a34216531c28c90ded9f968727c.jpg)

![70e0e02afd7147a55065165653acab0af65b7627cd07097c54fc6ecc367f3707.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/70e0e02afd7147a55065165653acab0af65b7627cd07097c54fc6ecc367f3707.jpg)

![83acb981f1f20ebde3c4544674d2d8e1f85da372a8bf5ba3170cd5472cd488be.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/83acb981f1f20ebde3c4544674d2d8e1f85da372a8bf5ba3170cd5472cd488be.jpg)

![88a6b90a0f6de3648b8ac0d950d049f21ca9aef0c62258e994a3ce74e3e7ce84.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/88a6b90a0f6de3648b8ac0d950d049f21ca9aef0c62258e994a3ce74e3e7ce84.jpg)

![9bad69492c62892abb5444a3ae725e54bf5d9923145dc28aad5cbe9e1866afcb.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/9bad69492c62892abb5444a3ae725e54bf5d9923145dc28aad5cbe9e1866afcb.jpg)

![a47ebe442784fd4bd016bf91dc22fcdeb287fb6149896f3d7ffe19b3f8ce18b2.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/a47ebe442784fd4bd016bf91dc22fcdeb287fb6149896f3d7ffe19b3f8ce18b2.jpg)

![d6d568654c7edccacb08812139841f3fcef8734ab5eeffdb1a28c168962f6227.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/d6d568654c7edccacb08812139841f3fcef8734ab5eeffdb1a28c168962f6227.jpg)

![ec10c219694faef79c0ffcab79df9bcbdb1a3e73ddd2a2be3b2d236f06302a5d.jpg](../nips_results/3856_You%20Can%20Trust%20Your%20Clustering%20Model_%20A%20Parameter-free%20Self-Boosting%20Plug-in%20for%20Deep%20Clustering/tables/ec10c219694faef79c0ffcab79df9bcbdb1a3e73ddd2a2be3b2d236f06302a5d.jpg)

## CGS-GAN: 3D Consistent Gaussian Splatting GANs for High Resolution Human Head Synthesis


### Images

![04496142e52aaa28042cee182cf580da7d0e337909559345374a6d8d6e767107.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/04496142e52aaa28042cee182cf580da7d0e337909559345374a6d8d6e767107.jpg)

![088977a2deaa856a7a03c1b900ca645d374aa0b1a3b624f6a2fccd2ec2089967.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/088977a2deaa856a7a03c1b900ca645d374aa0b1a3b624f6a2fccd2ec2089967.jpg)

![0bf395d21901be85ae8ba1a7c536ba06ed173fb7b1e9a63534345da7b4edb045.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/0bf395d21901be85ae8ba1a7c536ba06ed173fb7b1e9a63534345da7b4edb045.jpg)

![0c734061e5511d52859a494fc86edbd94d55ba4a5e9f560daaace93e4aa5a1db.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/0c734061e5511d52859a494fc86edbd94d55ba4a5e9f560daaace93e4aa5a1db.jpg)

![14f3ae46b9bcfa8e2fd707004fd124bdff1d5c24833c899525aff1e4b7a8d6af.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/14f3ae46b9bcfa8e2fd707004fd124bdff1d5c24833c899525aff1e4b7a8d6af.jpg)

![196eb771b5bfe59531b61166b23a784485a6ef39323a733cd6478d44fbca9456.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/196eb771b5bfe59531b61166b23a784485a6ef39323a733cd6478d44fbca9456.jpg)

![1c35df3dbaaca494c0c0803d5f30b25b8bcd8cda8133c0f4db6738c2e6a5f8b2.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/1c35df3dbaaca494c0c0803d5f30b25b8bcd8cda8133c0f4db6738c2e6a5f8b2.jpg)

![1e515be01860cea22bb60d44ce5841adffd4602a32630d758f9433ac3eecadef.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/1e515be01860cea22bb60d44ce5841adffd4602a32630d758f9433ac3eecadef.jpg)

![1edd5efb09cf58c95c39f1b7dab58911cd650f0495b31d12148bf584b9fc3159.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/1edd5efb09cf58c95c39f1b7dab58911cd650f0495b31d12148bf584b9fc3159.jpg)

![3d4783966f410b19e8638e6aa286d7cdcfea4d39c64730869f97241ada4cf355.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/3d4783966f410b19e8638e6aa286d7cdcfea4d39c64730869f97241ada4cf355.jpg)

![3ded2a124180b2815764960c951dbc2cded102ce9cca4523531d9c207a9c52b4.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/3ded2a124180b2815764960c951dbc2cded102ce9cca4523531d9c207a9c52b4.jpg)

![43fff771005c2d5aa162587e8e31b49cb65016aba7ebbf8f64f5a9f2ec54e718.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/43fff771005c2d5aa162587e8e31b49cb65016aba7ebbf8f64f5a9f2ec54e718.jpg)

![49107bdc368f80893a6065328c1f6ebbf54b755fc522bd24667da1d0545ec87e.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/49107bdc368f80893a6065328c1f6ebbf54b755fc522bd24667da1d0545ec87e.jpg)

![654e624ca78bc3e8002095ef0be2d05091cffaac75795aeee37b244fcaecdbce.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/654e624ca78bc3e8002095ef0be2d05091cffaac75795aeee37b244fcaecdbce.jpg)

![6b6b196703d50d55e96be15564f310a2d2303eebb790b9d7b616e1e7acac5570.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/6b6b196703d50d55e96be15564f310a2d2303eebb790b9d7b616e1e7acac5570.jpg)

![8a14d06dd8a81f44ae587d16c9a84624814ab9a53fc3b51d8840cff1b6dbe192.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/8a14d06dd8a81f44ae587d16c9a84624814ab9a53fc3b51d8840cff1b6dbe192.jpg)

![e43521fb23ab56eae23a48487ecee97595446a1b24a54dc0cc459bdbc5f8eea7.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/e43521fb23ab56eae23a48487ecee97595446a1b24a54dc0cc459bdbc5f8eea7.jpg)

![e8a69573a9e155c4093c5e87632d350b997978b6acaeea2102af405cb5e717ce.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/e8a69573a9e155c4093c5e87632d350b997978b6acaeea2102af405cb5e717ce.jpg)

![f7f02a973ad85dbd9e6086b125723fc0e149a797f413c3b05c8df45d4afadae0.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/images/f7f02a973ad85dbd9e6086b125723fc0e149a797f413c3b05c8df45d4afadae0.jpg)

### Tables

![1c291484874f287b6c816d07493dd81940b23ffe6084a7f1c674a10bbeaffc41.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/tables/1c291484874f287b6c816d07493dd81940b23ffe6084a7f1c674a10bbeaffc41.jpg)

![1cca6d048ac49c580555c5af6b1c7500fcb4dfa66a1738ae5d6eb1a8c26245b2.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/tables/1cca6d048ac49c580555c5af6b1c7500fcb4dfa66a1738ae5d6eb1a8c26245b2.jpg)

![3013113bd5f77f4a6af88ee7edd79959a9e32675d53cb2a949fced84c1d30c40.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/tables/3013113bd5f77f4a6af88ee7edd79959a9e32675d53cb2a949fced84c1d30c40.jpg)

![d026e6a1e166b6c9dd52dad7c72c7175815b9bb2731b9ae9454639f9e53d02c9.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/tables/d026e6a1e166b6c9dd52dad7c72c7175815b9bb2731b9ae9454639f9e53d02c9.jpg)

![e1678690af0f6b2fdc1f590b88694c8337865ffab5a00fd8dadcbed24da80b0c.jpg](../nips_results/3857_CGS-GAN_%203D%20Consistent%20Gaussian%20Splatting%20GANs%20for%20High%20Resolution%20Human%20Head%20Synthesis/tables/e1678690af0f6b2fdc1f590b88694c8337865ffab5a00fd8dadcbed24da80b0c.jpg)

## Quantum Visual Fields with Neural Amplitude Encoding


### Images

![0512ff18d6e2fcb02c07c4e129be425597f2c6a5eec99843e1722f13d324f64f.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/0512ff18d6e2fcb02c07c4e129be425597f2c6a5eec99843e1722f13d324f64f.jpg)

![0e2e9ebf8ba47d05600272a0c3a67228895de52e03845ee3869595375abe239f.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/0e2e9ebf8ba47d05600272a0c3a67228895de52e03845ee3869595375abe239f.jpg)

![1012ffb08196286a3ce25cf0f825502a7141978d2170e78698a27b6012030873.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/1012ffb08196286a3ce25cf0f825502a7141978d2170e78698a27b6012030873.jpg)

![48924df54cc8c88ee3914d6fb73bbf63361ac1624f39ca547d24bf3efa398fb0.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/48924df54cc8c88ee3914d6fb73bbf63361ac1624f39ca547d24bf3efa398fb0.jpg)

![58786361ec01bd0f8fa40f744883b5f1d89bc43e444be092ca7003a41de18dff.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/58786361ec01bd0f8fa40f744883b5f1d89bc43e444be092ca7003a41de18dff.jpg)

![6353fc1a2c2d361a1f2da530d4a30efbf6fa05148328d08c7100ab8f456788ae.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/6353fc1a2c2d361a1f2da530d4a30efbf6fa05148328d08c7100ab8f456788ae.jpg)

![7f3ed67d131a27fa0f49da2558489d9f826a9542929943d8363d7c8b9004331e.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/7f3ed67d131a27fa0f49da2558489d9f826a9542929943d8363d7c8b9004331e.jpg)

![803859f3a1fea7b87fdc6ac7eb09cdd2d97ac9fe36796cb6d9b7f31d28dbfcbf.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/803859f3a1fea7b87fdc6ac7eb09cdd2d97ac9fe36796cb6d9b7f31d28dbfcbf.jpg)

![81d761ce52b57700918ca154b0bb3ca13f570063a00271a2f1de515a74fea913.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/81d761ce52b57700918ca154b0bb3ca13f570063a00271a2f1de515a74fea913.jpg)

![8c83dae5cda968d2e8e31952ad2527eea7a4e7363574816f8abd883cfd3d327b.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/8c83dae5cda968d2e8e31952ad2527eea7a4e7363574816f8abd883cfd3d327b.jpg)

![9225f97f8a912fb5a3b48a7247f863b3e7e1eb2c8c51c8f86f725d8d16d56a0a.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/9225f97f8a912fb5a3b48a7247f863b3e7e1eb2c8c51c8f86f725d8d16d56a0a.jpg)

![b444dd1aa601bdd5795049fb46054c4fe4c06f2ad4720df3aadefa4b21f42710.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/b444dd1aa601bdd5795049fb46054c4fe4c06f2ad4720df3aadefa4b21f42710.jpg)

![c97129c926b081ea6aeb3367597b9553df16c542ede43cd629b3f8fd5f5725c5.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/c97129c926b081ea6aeb3367597b9553df16c542ede43cd629b3f8fd5f5725c5.jpg)

![edc25d6682a0920ba61d8fca9ce5360e1925efb30d7a7e7d9bf11cf061e1b479.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/edc25d6682a0920ba61d8fca9ce5360e1925efb30d7a7e7d9bf11cf061e1b479.jpg)

![f0bd77abf1335fa110eec014a411419c4c9d7c3581b0984fa79f61e3cda8fee8.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/images/f0bd77abf1335fa110eec014a411419c4c9d7c3581b0984fa79f61e3cda8fee8.jpg)

### Tables

![4bdac0e61569bddcf98fc93a02da3da3a10f68c67cee1f16f54cf5190eef8894.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/tables/4bdac0e61569bddcf98fc93a02da3da3a10f68c67cee1f16f54cf5190eef8894.jpg)

![dc0b3939bc169a4dd0ebd3646898e2d1982f695e2a16a23b8cd877ee0742551a.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/tables/dc0b3939bc169a4dd0ebd3646898e2d1982f695e2a16a23b8cd877ee0742551a.jpg)

![dd46bc425bb53f1b76c5ecc31dc2e1798ecfda183a06bc5ea2a217b965bc2f84.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/tables/dd46bc425bb53f1b76c5ecc31dc2e1798ecfda183a06bc5ea2a217b965bc2f84.jpg)

![e6217efd3beef732311abf784e9582cebb668b2f2c1f08b9fbfebe089a50b85b.jpg](../nips_results/3858_Quantum%20Visual%20Fields%20with%20Neural%20Amplitude%20Encoding/tables/e6217efd3beef732311abf784e9582cebb668b2f2c1f08b9fbfebe089a50b85b.jpg)

## ReMindRAG: Low-Cost LLM-Guided Knowledge Graph Traversal for Efficient RAG


### Images

![0282657adbc250b2b306d9ffd002e1f75173e3fc8f6745fa89514ac7f9b83335.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/0282657adbc250b2b306d9ffd002e1f75173e3fc8f6745fa89514ac7f9b83335.jpg)

![140592b28f0f6fc7c53c99939c90f512ca2e2bc2f202346cd56b020d959a275d.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/140592b28f0f6fc7c53c99939c90f512ca2e2bc2f202346cd56b020d959a275d.jpg)

![1f18f1198162887856a1382b73a6777a57a58da3308b4b2ae93ed2143eb7190c.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/1f18f1198162887856a1382b73a6777a57a58da3308b4b2ae93ed2143eb7190c.jpg)

![67a371953c1121da33dfb2adc91344a85ce0d7686e1eccbe726a6aa398fe1862.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/67a371953c1121da33dfb2adc91344a85ce0d7686e1eccbe726a6aa398fe1862.jpg)

![9032ed54bd84a2d31b3c01c7406e50f3539586e75110590131765ce42f4b46c6.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/9032ed54bd84a2d31b3c01c7406e50f3539586e75110590131765ce42f4b46c6.jpg)

![923340ab55756ba8830d0f4924cbc60b624083a05700192ff52c796cd788d8fa.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/923340ab55756ba8830d0f4924cbc60b624083a05700192ff52c796cd788d8fa.jpg)

![9b9749e87f71bba0e915bfab0fb25b6161904c74806bfa2783f6c37229bf5730.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/9b9749e87f71bba0e915bfab0fb25b6161904c74806bfa2783f6c37229bf5730.jpg)

![ab94829357f86ab2b7e5bacb91997ce44a6386c44a04daa01a5f12eb5be718a9.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/ab94829357f86ab2b7e5bacb91997ce44a6386c44a04daa01a5f12eb5be718a9.jpg)

![b5f9efc9baa854006188cb121abc6b24d36d4a7a57d47ae8cc12e4f60cd214ed.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/b5f9efc9baa854006188cb121abc6b24d36d4a7a57d47ae8cc12e4f60cd214ed.jpg)

![cc8f50a0139f750efe08eee35ae0cbdfecb74c8a6c811db319799ccc54323acc.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/cc8f50a0139f750efe08eee35ae0cbdfecb74c8a6c811db319799ccc54323acc.jpg)

![cd8261bcb73b9571d9a635c737649dd48d5bab4c09f15a82ce65dc93ef9bc4eb.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/cd8261bcb73b9571d9a635c737649dd48d5bab4c09f15a82ce65dc93ef9bc4eb.jpg)

![e5e8a9fa020d8b005439eae4a9b336dca206cfc3c555fce0e0ca0445686ea26c.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/e5e8a9fa020d8b005439eae4a9b336dca206cfc3c555fce0e0ca0445686ea26c.jpg)

![f66010bd59b3e536d300e58a9603557ddde7ddbe20ef298d464c2f72edf0cbbf.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/images/f66010bd59b3e536d300e58a9603557ddde7ddbe20ef298d464c2f72edf0cbbf.jpg)

### Tables

![09a1d2cd047bc5444e41e2f677c89f631b541174a14084a3aca0586e4653a962.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/09a1d2cd047bc5444e41e2f677c89f631b541174a14084a3aca0586e4653a962.jpg)

![102591932d87017c4d829e11f089928fa132ecb51f4007138fc3bb856b9d4cd7.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/102591932d87017c4d829e11f089928fa132ecb51f4007138fc3bb856b9d4cd7.jpg)

![10bd7e32a0cbfd9e79ed779135e5ba3cbfc8472e93f4a69af68765f4f6ac93d8.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/10bd7e32a0cbfd9e79ed779135e5ba3cbfc8472e93f4a69af68765f4f6ac93d8.jpg)

![13651a10876cd39f09cb80a21b5076416c31b61f381cb0fda9718b695c58c558.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/13651a10876cd39f09cb80a21b5076416c31b61f381cb0fda9718b695c58c558.jpg)

![21f2aa43179d75e4aea79abe7b0a4376d6a09d76b3a025dba22cc6aab799dd61.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/21f2aa43179d75e4aea79abe7b0a4376d6a09d76b3a025dba22cc6aab799dd61.jpg)

![22adf6aab8b0b11bb47a7b88f30f13af2f65c42b504eebaca0db2b4c89639f0f.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/22adf6aab8b0b11bb47a7b88f30f13af2f65c42b504eebaca0db2b4c89639f0f.jpg)

![3c30d304a3be6c89873902c1c5232b292683d399f731066c0cd78c0f77779cdf.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/3c30d304a3be6c89873902c1c5232b292683d399f731066c0cd78c0f77779cdf.jpg)

![44997c41e8b58bdefcd00a993d2b7340315b8ef997c294f46f09e44162215c7a.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/44997c41e8b58bdefcd00a993d2b7340315b8ef997c294f46f09e44162215c7a.jpg)

![5523183bd2a15b184ec46f8bb0bd1b029c62a5fe7cd9868935a2aa846861d6c2.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/5523183bd2a15b184ec46f8bb0bd1b029c62a5fe7cd9868935a2aa846861d6c2.jpg)

![69891e9389ec9b8ddc74d809448951620f88c4edfd331a26aaf012a22a50624c.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/69891e9389ec9b8ddc74d809448951620f88c4edfd331a26aaf012a22a50624c.jpg)

![6a1efb61d799b3bb57e951c6e8e98c8d4049fc9e6ac121fb69e097f40c4ae0a9.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/6a1efb61d799b3bb57e951c6e8e98c8d4049fc9e6ac121fb69e097f40c4ae0a9.jpg)

![90b4133ac477a28a03ff85742c203547f1c5098c6a3209ac901dfbade0eece21.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/90b4133ac477a28a03ff85742c203547f1c5098c6a3209ac901dfbade0eece21.jpg)

![991e293cdb31a3558880ff5bcc4fc10c3b243bede67b76ecfb02aad5b6655724.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/991e293cdb31a3558880ff5bcc4fc10c3b243bede67b76ecfb02aad5b6655724.jpg)

![addad888b727bd8cd58fd5cb97a9c04e1753e26833365af3001af110da1bbdb4.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/addad888b727bd8cd58fd5cb97a9c04e1753e26833365af3001af110da1bbdb4.jpg)

![c5bcd6efafab2ef51975cc332ad2b2524704dc95c0bfedd7cd1e25c6dd196d45.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/c5bcd6efafab2ef51975cc332ad2b2524704dc95c0bfedd7cd1e25c6dd196d45.jpg)

![d945eb12fbbeb4c600a68f1ce117ff5bbf2d64bf32c6c2634733d572a267cffa.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/d945eb12fbbeb4c600a68f1ce117ff5bbf2d64bf32c6c2634733d572a267cffa.jpg)

![da5fbb5276a17d7d00eef4d70add49b9f61bf291c1b6e7b671b9e4be670fd24b.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/da5fbb5276a17d7d00eef4d70add49b9f61bf291c1b6e7b671b9e4be670fd24b.jpg)

![e6ccdddcd919861cf972f7468360c75032777b58e48e20dc545b5417ed891d79.jpg](../nips_results/3859_ReMindRAG_%20Low-Cost%20LLM-Guided%20Knowledge%20Graph%20Traversal%20for%20Efficient%20RAG/tables/e6ccdddcd919861cf972f7468360c75032777b58e48e20dc545b5417ed891d79.jpg)

## xLSTM-Mixer: Multivariate Time Series Forecasting by Mixing via Scalar Memories


### Images

![103e3a4ce72e15f512f559db7279f1eb335ac71ed42d7b319e9bb491897d6f5e.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/images/103e3a4ce72e15f512f559db7279f1eb335ac71ed42d7b319e9bb491897d6f5e.jpg)

![7b69c26f744cb5c09a9fca5e13d6ce9b64211b420a89cb3d6e5e93747f6deee8.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/images/7b69c26f744cb5c09a9fca5e13d6ce9b64211b420a89cb3d6e5e93747f6deee8.jpg)

![8847a12384ac362d27073edbf491c9b36ec9a6eba6159e03b791007b6e0d6973.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/images/8847a12384ac362d27073edbf491c9b36ec9a6eba6159e03b791007b6e0d6973.jpg)

![8b1082aa01504e2bc982b553e2a66837be1b81b6718765e4385b52ded58d5bf0.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/images/8b1082aa01504e2bc982b553e2a66837be1b81b6718765e4385b52ded58d5bf0.jpg)

![a9a1e98bc5585edead47311f6efefa5e7ede6699cfe4a0d72588aa8a57ccb86d.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/images/a9a1e98bc5585edead47311f6efefa5e7ede6699cfe4a0d72588aa8a57ccb86d.jpg)

![ab8d64bdc3eafc8d98314a31bdce1911e9426c71ecd71462f893730ed454bdb9.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/images/ab8d64bdc3eafc8d98314a31bdce1911e9426c71ecd71462f893730ed454bdb9.jpg)

![b4395f56ad483def380cbc1898424ee653e033a82273016c21f943c2e7e1c150.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/images/b4395f56ad483def380cbc1898424ee653e033a82273016c21f943c2e7e1c150.jpg)

![df8fbd4ff094987e20dd394c195c77b5cede9d95a2b17d14355d607e64003aa8.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/images/df8fbd4ff094987e20dd394c195c77b5cede9d95a2b17d14355d607e64003aa8.jpg)

### Tables

![057759597c0e72fb6c3eab9013967d067deff8abeb39bb09c7f0cad0cbec94ca.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/057759597c0e72fb6c3eab9013967d067deff8abeb39bb09c7f0cad0cbec94ca.jpg)

![0b25b639586f6207e5e4a41ff41c45ea95f9a145e1de770ded989d87bf08c8a1.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/0b25b639586f6207e5e4a41ff41c45ea95f9a145e1de770ded989d87bf08c8a1.jpg)

![2c55b3fdb247dab306a06fb86118568dc51328c04c6eda586ba040cea098f8eb.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/2c55b3fdb247dab306a06fb86118568dc51328c04c6eda586ba040cea098f8eb.jpg)

![2f14c6ceaf257c9462cc02d4bd98d691c3329a61d19d8b17ac9e8b7d479925e2.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/2f14c6ceaf257c9462cc02d4bd98d691c3329a61d19d8b17ac9e8b7d479925e2.jpg)

![44ace7908d8dc0f72609e4c717c3183881067a7a050d0ea32e0d94f3b2dbf01d.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/44ace7908d8dc0f72609e4c717c3183881067a7a050d0ea32e0d94f3b2dbf01d.jpg)

![4ee9fde2cf22c1df49ca1ea0b2fe15f4b0d83e2f15cefb310ef5ca402b97be13.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/4ee9fde2cf22c1df49ca1ea0b2fe15f4b0d83e2f15cefb310ef5ca402b97be13.jpg)

![721e6c17d3862573ea355df49b0240576439bd8ed11314f472ca3e3fc7effc06.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/721e6c17d3862573ea355df49b0240576439bd8ed11314f472ca3e3fc7effc06.jpg)

![769c1089f443041eac782e72c6efcb818c1226da754556fd1627e4ddaa788dca.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/769c1089f443041eac782e72c6efcb818c1226da754556fd1627e4ddaa788dca.jpg)

![774ff56b569b120855d494602c3378d4327aeca793a799138890c1be1c076cad.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/774ff56b569b120855d494602c3378d4327aeca793a799138890c1be1c076cad.jpg)

![7d4b713992e5f498ac3b75841a5643d21455254b582d1f50a38bcd2181d5af47.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/7d4b713992e5f498ac3b75841a5643d21455254b582d1f50a38bcd2181d5af47.jpg)

![7f531687ae2dd9e71b472f3acc18259e619455e940cb5d37535e829f545f3569.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/7f531687ae2dd9e71b472f3acc18259e619455e940cb5d37535e829f545f3569.jpg)

![a82d82a1c39a220e0c553daf5bf63b931de82fa854ed3d663f548c10afe9882b.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/a82d82a1c39a220e0c553daf5bf63b931de82fa854ed3d663f548c10afe9882b.jpg)

![b592b10734c65e2d6d956c5c8fee5ea90aeb546b212e23421f3d681df13ac001.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/b592b10734c65e2d6d956c5c8fee5ea90aeb546b212e23421f3d681df13ac001.jpg)

![c18cf129c02b7a6b4fcdddf05dce2fce04bbf71da3008b8275b22192f28f6ecb.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/c18cf129c02b7a6b4fcdddf05dce2fce04bbf71da3008b8275b22192f28f6ecb.jpg)

![ffde3d58bdca0e3ee06834662f034c3bad984ef14a087073e082c50cf85353d9.jpg](../nips_results/3860_xLSTM-Mixer_%20Multivariate%20Time%20Series%20Forecasting%20by%20Mixing%20via%20Scalar%20Memories/tables/ffde3d58bdca0e3ee06834662f034c3bad984ef14a087073e082c50cf85353d9.jpg)

## SMARTraj$^2$: A Stable Multi-City Adaptive Method for Multi-View Spatio-Temporal Trajectory Representation Learning


### Images

![0af3b9b13aaea321287c966cc43a8b318a97e51a3937fda8c17ef8b6b52ae76d.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/images/0af3b9b13aaea321287c966cc43a8b318a97e51a3937fda8c17ef8b6b52ae76d.jpg)

![38cadfff9eadca628b4d19c185a42c058b96acceae265814a3a2c11cd9132c84.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/images/38cadfff9eadca628b4d19c185a42c058b96acceae265814a3a2c11cd9132c84.jpg)

![47489688a66e863ddd49d2cc18d726ab53f190be5490427f16dd48e01b834eaa.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/images/47489688a66e863ddd49d2cc18d726ab53f190be5490427f16dd48e01b834eaa.jpg)

![475c48c191286a666ade43e3b298924ae852ccf25239de8da522b66e9def26c9.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/images/475c48c191286a666ade43e3b298924ae852ccf25239de8da522b66e9def26c9.jpg)

![6694b03f994b7838fc25024837d07d43c5e2dded1234a8c1f935e230d11242de.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/images/6694b03f994b7838fc25024837d07d43c5e2dded1234a8c1f935e230d11242de.jpg)

![6cd0ea2fdc20f2caa4cdbdbb8656a708c3b9eec120f569d773bb7626bfae13d6.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/images/6cd0ea2fdc20f2caa4cdbdbb8656a708c3b9eec120f569d773bb7626bfae13d6.jpg)

### Tables

![146d1f88757d9fbd0f83a21a28dc1c5359c7edca491802014cf0d33bc6f174e0.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/tables/146d1f88757d9fbd0f83a21a28dc1c5359c7edca491802014cf0d33bc6f174e0.jpg)

![196acf9b153a3d6e7269d62841f9703b632f1ec2f594269132cf5929591d4f5e.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/tables/196acf9b153a3d6e7269d62841f9703b632f1ec2f594269132cf5929591d4f5e.jpg)

![278750ddc98574b0352dde0c7485830306cf6f9a55667ca41a1b245a4d10aab1.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/tables/278750ddc98574b0352dde0c7485830306cf6f9a55667ca41a1b245a4d10aab1.jpg)

![40983c56886c7152d0b3c545a4e83421fcd6d51357acfa181920e8637e0fcf6d.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/tables/40983c56886c7152d0b3c545a4e83421fcd6d51357acfa181920e8637e0fcf6d.jpg)

![4d18962d6f0485eb8a56a1ba0445f32d7237c2fc24e69a23f4eee33c37518190.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/tables/4d18962d6f0485eb8a56a1ba0445f32d7237c2fc24e69a23f4eee33c37518190.jpg)

![51de41ce3da7799da6470004aca9fcf85192047d6e5b4d040f1c239bfa56f839.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/tables/51de41ce3da7799da6470004aca9fcf85192047d6e5b4d040f1c239bfa56f839.jpg)

![a586efa6feeb632b72f76f802f938c560b9df3a8410b86fcf0271d7b1a0b7ee9.jpg](../nips_results/3861_SMARTraj%24%5E2%24_%20A%20Stable%20Multi-City%20Adaptive%20Method%20for%20Multi-View%20Spatio-Temporal%20Trajectory%20Represen/tables/a586efa6feeb632b72f76f802f938c560b9df3a8410b86fcf0271d7b1a0b7ee9.jpg)

## TopER: Topological Embeddings in Graph Representation Learning


### Images

![0ab11e7e1d61685c9fae8f815790beb8fb23a683c604e42db1922d13e1da0be6.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/images/0ab11e7e1d61685c9fae8f815790beb8fb23a683c604e42db1922d13e1da0be6.jpg)

![2fd15b724f5597e3964e50c12c2b887a3d0972a1cf2388200b2835cb076fcd7c.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/images/2fd15b724f5597e3964e50c12c2b887a3d0972a1cf2388200b2835cb076fcd7c.jpg)

![5f6620f3f5c0bb7208f6cc130d3c88bad202dc5ff2914aa7b15f936f0ae2d763.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/images/5f6620f3f5c0bb7208f6cc130d3c88bad202dc5ff2914aa7b15f936f0ae2d763.jpg)

![749d2d88385d399658458c60ef4e9a9d5195a83650dd6d118334ffc78972c77e.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/images/749d2d88385d399658458c60ef4e9a9d5195a83650dd6d118334ffc78972c77e.jpg)

![8857d2174623ee1bd7e1fd91c71c4f41407fc125c8fa15c29f0919a5fc43a303.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/images/8857d2174623ee1bd7e1fd91c71c4f41407fc125c8fa15c29f0919a5fc43a303.jpg)

![8f99ffd569de8a663725cd088c4c93751f037e99474dd6fb861b87d71df29e2e.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/images/8f99ffd569de8a663725cd088c4c93751f037e99474dd6fb861b87d71df29e2e.jpg)

![b108efdb1e1ea906bb7c57e164f6474be26ab1f991af6de619e9f3408ce57758.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/images/b108efdb1e1ea906bb7c57e164f6474be26ab1f991af6de619e9f3408ce57758.jpg)

![b771db738d2fc381dea60468a2179b5fe12fdb1fef40766eee162b75e2a55071.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/images/b771db738d2fc381dea60468a2179b5fe12fdb1fef40766eee162b75e2a55071.jpg)

![ce9eec0a69bce2859e3b5fbf237f7c1820f3f8117ecf18d6af2bc7c38ec1a9ac.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/images/ce9eec0a69bce2859e3b5fbf237f7c1820f3f8117ecf18d6af2bc7c38ec1a9ac.jpg)

![dca6f1b2f4a45a5ae7fc3c0103d98d571f4703f3ea58ca72ed3ce4effe47932f.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/images/dca6f1b2f4a45a5ae7fc3c0103d98d571f4703f3ea58ca72ed3ce4effe47932f.jpg)

### Tables

![1a0c8b06bd3a68649cb3dccf61d3d15bf81f99c35fd80e0fe2a11578975802d2.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/1a0c8b06bd3a68649cb3dccf61d3d15bf81f99c35fd80e0fe2a11578975802d2.jpg)

![3a5ebe4c21ea1dd27eb479e175b5b60f269fb37fe9917e223e1cb901cc60707a.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/3a5ebe4c21ea1dd27eb479e175b5b60f269fb37fe9917e223e1cb901cc60707a.jpg)

![3aafd174a3fde6d331d6a5ad7f0ff9f0c489b40ba22e7b5f099a34c7ac84f8f3.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/3aafd174a3fde6d331d6a5ad7f0ff9f0c489b40ba22e7b5f099a34c7ac84f8f3.jpg)

![43570b6dff127523d55707245fae75951366b5346e4fe7a3b6d96298cf826467.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/43570b6dff127523d55707245fae75951366b5346e4fe7a3b6d96298cf826467.jpg)

![470b250e6b10984914464703dd6892a5ccb1ec26201f93007bd700630678240a.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/470b250e6b10984914464703dd6892a5ccb1ec26201f93007bd700630678240a.jpg)

![5217255eb4c74b706d201179d81622b2c6bf447ee0514a3fe57223a41c2dbd72.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/5217255eb4c74b706d201179d81622b2c6bf447ee0514a3fe57223a41c2dbd72.jpg)

![7ec4681083080bcdd02132a500359419fbdbff159d0ea0553b2391a241e787c5.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/7ec4681083080bcdd02132a500359419fbdbff159d0ea0553b2391a241e787c5.jpg)

![7f7f85494c6a42eaa027867fa3f298a723138bf1a8997925781ab489997102c6.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/7f7f85494c6a42eaa027867fa3f298a723138bf1a8997925781ab489997102c6.jpg)

![80e0637558de743595404c2a1b77be20e5ebda65f3796c9017299afb02709ec2.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/80e0637558de743595404c2a1b77be20e5ebda65f3796c9017299afb02709ec2.jpg)

![86102020ccb169aa767582f8a6a559b21a00b769a7ea60f24d1e0eac93478da5.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/86102020ccb169aa767582f8a6a559b21a00b769a7ea60f24d1e0eac93478da5.jpg)

![8b37c7c3c7fc9bca3045a7027bb0adebc2c0a78b13680d1edfc2a6f274f3b292.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/8b37c7c3c7fc9bca3045a7027bb0adebc2c0a78b13680d1edfc2a6f274f3b292.jpg)

![a8463d68c413e0e0fde9f78854477d144e9962dcfd507e27ae992f5e866d80ab.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/a8463d68c413e0e0fde9f78854477d144e9962dcfd507e27ae992f5e866d80ab.jpg)

![b08058f738ba561db0d966aff84c3cf95509923186615efb1de910d5dffe2540.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/b08058f738ba561db0d966aff84c3cf95509923186615efb1de910d5dffe2540.jpg)

![bbe45d2284b8cfdefb9051fabadf11e368f9cb422e03870803d460d9c100298f.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/bbe45d2284b8cfdefb9051fabadf11e368f9cb422e03870803d460d9c100298f.jpg)

![c04c7db9cbf846e1270cb13b4b55c1cb963e3065ffad6e7f8f425f5feb8a7887.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/c04c7db9cbf846e1270cb13b4b55c1cb963e3065ffad6e7f8f425f5feb8a7887.jpg)

![e84a4f259e12a04a63179398996e285c1359ec5dac8cf7b2317191ee987b276b.jpg](../nips_results/3862_TopER_%20Topological%20Embeddings%20in%20Graph%20Representation%20Learning/tables/e84a4f259e12a04a63179398996e285c1359ec5dac8cf7b2317191ee987b276b.jpg)

## Geometry of Decision Making in Language Models


### Images

![0032ea9ab9c88877cce5231f390bb0b1658431791a84d173da33c6574b2a5032.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/0032ea9ab9c88877cce5231f390bb0b1658431791a84d173da33c6574b2a5032.jpg)

![08deb8941468fab4fbc37c1955a4a59c9689fa28eae92e26946f61ea68ac67b6.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/08deb8941468fab4fbc37c1955a4a59c9689fa28eae92e26946f61ea68ac67b6.jpg)

![0ab43a179a98241296521f973d53a5b46a2bc770baa425e753c5b1a74529953d.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/0ab43a179a98241296521f973d53a5b46a2bc770baa425e753c5b1a74529953d.jpg)

![0c038fdbb040d2b3aea9af9a1c397bb71bd49812bc155c9b02205d512dc49e4a.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/0c038fdbb040d2b3aea9af9a1c397bb71bd49812bc155c9b02205d512dc49e4a.jpg)

![0cabc5bccbb4690f0f7905a31b5a7af4998c383aa99ab8d02904df540f5e7ba6.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/0cabc5bccbb4690f0f7905a31b5a7af4998c383aa99ab8d02904df540f5e7ba6.jpg)

![0d020bd8567f6e4f242b15e818dbcdc9d7f1dde1808faa30247327a12c1c27a9.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/0d020bd8567f6e4f242b15e818dbcdc9d7f1dde1808faa30247327a12c1c27a9.jpg)

![2be712f956d3cc601e86b7d1cb02f52f9c59edc08acc9bb6f73a8449b6437a55.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/2be712f956d3cc601e86b7d1cb02f52f9c59edc08acc9bb6f73a8449b6437a55.jpg)

![355a4bd18953d7f949cc0060baaaa57d43ca0d30ea959ec077ced54084894c5c.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/355a4bd18953d7f949cc0060baaaa57d43ca0d30ea959ec077ced54084894c5c.jpg)

![3597e64746ca1a8a19118e275091c0c359c88cba1b730e9df32d1664059df1d3.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/3597e64746ca1a8a19118e275091c0c359c88cba1b730e9df32d1664059df1d3.jpg)

![363d181cccfbcb6bcf2722ed71a96fffff3abf829926ecf5174e4dedb5a7d6ee.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/363d181cccfbcb6bcf2722ed71a96fffff3abf829926ecf5174e4dedb5a7d6ee.jpg)

![44d5ae7b15333f5bbce9a1add3d05e18a2ee0bb9a5e868ddda735d87c9a8e4be.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/44d5ae7b15333f5bbce9a1add3d05e18a2ee0bb9a5e868ddda735d87c9a8e4be.jpg)

![58f2e86d238e51346be824b95c51d01f8a17334973179d78fa505b659efa8b5a.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/58f2e86d238e51346be824b95c51d01f8a17334973179d78fa505b659efa8b5a.jpg)

![5910fd00d1a0b39f851d7d571ef32dbedad75ffe0111529d5a08e34bdf734abe.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/5910fd00d1a0b39f851d7d571ef32dbedad75ffe0111529d5a08e34bdf734abe.jpg)

![5db06ce5609c278afb4eb24fa32ca06bae384327b794468a8dc87d9cb5e54f9a.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/5db06ce5609c278afb4eb24fa32ca06bae384327b794468a8dc87d9cb5e54f9a.jpg)

![6221be30631b7f6f3239ef743ffe254472b36475503c019d4e2f560ad9dc6232.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/6221be30631b7f6f3239ef743ffe254472b36475503c019d4e2f560ad9dc6232.jpg)

![6749874840e417ca51ed9ba6958bcb19bc16d9d45d9bb1fdf7918373c52ddbbc.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/6749874840e417ca51ed9ba6958bcb19bc16d9d45d9bb1fdf7918373c52ddbbc.jpg)

![70e489b6a14272b2adad03d811e59f7db7fc6c8bad94b60c719fa940d9201561.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/70e489b6a14272b2adad03d811e59f7db7fc6c8bad94b60c719fa940d9201561.jpg)

![7523c5b01b9c967388a9d33b37a2208b84c17035d448b9ff45afcd8d2c80fa5c.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/7523c5b01b9c967388a9d33b37a2208b84c17035d448b9ff45afcd8d2c80fa5c.jpg)

![89cf32dabf112b27415fce9f64f70e72f2ab95325e5b47a2d4cdebb163063148.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/89cf32dabf112b27415fce9f64f70e72f2ab95325e5b47a2d4cdebb163063148.jpg)

![91951d8a70e02c845ec21e3a572581681a4aecb4b8038d476efe1c912748b374.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/91951d8a70e02c845ec21e3a572581681a4aecb4b8038d476efe1c912748b374.jpg)

![9d338320c7ac7d6aa091af83d1e9e0d619799bdb95ffb01855eb9ac79e3f1f14.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/9d338320c7ac7d6aa091af83d1e9e0d619799bdb95ffb01855eb9ac79e3f1f14.jpg)

![ae262caf8ee3a3b795108529488bcc5b57652689ece91a3b0c425a196c3e1295.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/ae262caf8ee3a3b795108529488bcc5b57652689ece91a3b0c425a196c3e1295.jpg)

![b1470129122115b46608d2378d1cfd6930ce2c5fa7dba551d73b60ef360e55b5.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/b1470129122115b46608d2378d1cfd6930ce2c5fa7dba551d73b60ef360e55b5.jpg)

![b8aecd9e4802b5b544639f99467255a2ce815fa586b2601e4c6e78cb904311c2.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/b8aecd9e4802b5b544639f99467255a2ce815fa586b2601e4c6e78cb904311c2.jpg)

![b94129a3199065918a1730f96cf112dfb969681e7b817d01d472a8f33d4e1f79.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/b94129a3199065918a1730f96cf112dfb969681e7b817d01d472a8f33d4e1f79.jpg)

![b969f3a3e02851752a00f50563de2a8fc393f4f8ef35aaa59c52ba783283028d.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/b969f3a3e02851752a00f50563de2a8fc393f4f8ef35aaa59c52ba783283028d.jpg)

![bbda718c882efee5c9d2ac181beb90cbf72c5b05cf18fb57124bbc353370e460.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/bbda718c882efee5c9d2ac181beb90cbf72c5b05cf18fb57124bbc353370e460.jpg)

![c20b5d314f857395604f5245cbb614cf4eec053ccfa49b35795dd223493d5d54.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/c20b5d314f857395604f5245cbb614cf4eec053ccfa49b35795dd223493d5d54.jpg)

![e9f1c6ac4741109abd97fe9eb508d6d01afff713d8147ee7ca1723d5342bab9b.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/e9f1c6ac4741109abd97fe9eb508d6d01afff713d8147ee7ca1723d5342bab9b.jpg)

![ee7efc0f4968f06dc79a0751571beeba8b846bcc120814027761b9b1a41d1167.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/ee7efc0f4968f06dc79a0751571beeba8b846bcc120814027761b9b1a41d1167.jpg)

![ef758472159ac7b68c8801519e67e7d920f6b39fc5fd0c6cc99764aa900be094.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/images/ef758472159ac7b68c8801519e67e7d920f6b39fc5fd0c6cc99764aa900be094.jpg)

### Tables

![24200829512a5ee0baa4f094e8f561b365cb86ff470263fee0a50943000bb543.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/tables/24200829512a5ee0baa4f094e8f561b365cb86ff470263fee0a50943000bb543.jpg)

![343a5d364b9c6873212d7b0d4aa2fca72f679ee977cbb85ab618435bcb592ad3.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/tables/343a5d364b9c6873212d7b0d4aa2fca72f679ee977cbb85ab618435bcb592ad3.jpg)

![6168954ddedb36427a2d9c694f3abf11d878b4add01489c2d6b74c3e7725c88c.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/tables/6168954ddedb36427a2d9c694f3abf11d878b4add01489c2d6b74c3e7725c88c.jpg)

![8a0a072c364dd71ef7e3023090dc15fe703c1be3f4eeca299d929a42609918df.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/tables/8a0a072c364dd71ef7e3023090dc15fe703c1be3f4eeca299d929a42609918df.jpg)

![94a933221574bb49cbc00f5d66e8eb4eb67dcd64ab40e3e8ba6d23f9850b348c.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/tables/94a933221574bb49cbc00f5d66e8eb4eb67dcd64ab40e3e8ba6d23f9850b348c.jpg)

![aa2f762144367a2537f94a9fac838c6562204c59e45d22c6364e4865576812c3.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/tables/aa2f762144367a2537f94a9fac838c6562204c59e45d22c6364e4865576812c3.jpg)

![b5551bea1ddb54b713da18eb87a6e190f070cee621adf377c2e422b70e8241f6.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/tables/b5551bea1ddb54b713da18eb87a6e190f070cee621adf377c2e422b70e8241f6.jpg)

![bbfb08da0c0e26bc427b0b3c63ec73d63f9f9a33baae12377b1d42c27f909624.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/tables/bbfb08da0c0e26bc427b0b3c63ec73d63f9f9a33baae12377b1d42c27f909624.jpg)

![c268ff17ce54f9369fd9d41505011d16d52f9860c0e1c6882c2690ec8d250228.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/tables/c268ff17ce54f9369fd9d41505011d16d52f9860c0e1c6882c2690ec8d250228.jpg)

![d81fe9e33a82340ffc40ceb9d2111f54c86145d4da9c45745d302bc51a8710b5.jpg](../nips_results/3863_Geometry%20of%20Decision%20Making%20in%20Language%20Models/tables/d81fe9e33a82340ffc40ceb9d2111f54c86145d4da9c45745d302bc51a8710b5.jpg)

## LayerIF: Estimating Layer Quality for Large Language Models using Influence Functions


### Images

![6f1fff2fa9dc021044355abfb625f768b1353f1767867e0254b0443e57310bf5.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/images/6f1fff2fa9dc021044355abfb625f768b1353f1767867e0254b0443e57310bf5.jpg)

![997dc6f38ab953f0c57775ff846e0c4a71ee1087dcfb4e4127e1ab63b691eef9.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/images/997dc6f38ab953f0c57775ff846e0c4a71ee1087dcfb4e4127e1ab63b691eef9.jpg)

![a3af06eedb9f606836e15024380fa08e73438cb684da0619e7e87ff7c5be276a.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/images/a3af06eedb9f606836e15024380fa08e73438cb684da0619e7e87ff7c5be276a.jpg)

![b17e70790c651198a10bdd4fa47981ee42257cfbac7733462e36149eff0ad455.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/images/b17e70790c651198a10bdd4fa47981ee42257cfbac7733462e36149eff0ad455.jpg)

### Tables

![25f2d188d37c6d125005521e413a70b56c0003007e4a56f5a28b9e7725d27cf1.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/25f2d188d37c6d125005521e413a70b56c0003007e4a56f5a28b9e7725d27cf1.jpg)

![2c454ad6c812281ca0b048eca80ec749c5f6ab63242a2136bca867c2f4451af1.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/2c454ad6c812281ca0b048eca80ec749c5f6ab63242a2136bca867c2f4451af1.jpg)

![46423fb9c98619a3e49cf2210d92fb3076d6e7cdfe62d6dfe86b22ac50069294.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/46423fb9c98619a3e49cf2210d92fb3076d6e7cdfe62d6dfe86b22ac50069294.jpg)

![4a5d0d9d3a01ef9ea880601105829aac62b28e7a9ac410c8e394fd1bca40f09c.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/4a5d0d9d3a01ef9ea880601105829aac62b28e7a9ac410c8e394fd1bca40f09c.jpg)

![544a4e3be0c5f8eeca387dd7fe199a6130325a44e73ebb16e0416a53027d6328.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/544a4e3be0c5f8eeca387dd7fe199a6130325a44e73ebb16e0416a53027d6328.jpg)

![69861de3cb08a8e9b14b9627b0d84c73fbef984adbdd6d0ffe2ea830a97b7ee3.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/69861de3cb08a8e9b14b9627b0d84c73fbef984adbdd6d0ffe2ea830a97b7ee3.jpg)

![6eeb6df63bd50b33114f5e8b34c4ea254c076a4aaf7e16a03b6f548ac5bebfb8.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/6eeb6df63bd50b33114f5e8b34c4ea254c076a4aaf7e16a03b6f548ac5bebfb8.jpg)

![8e59dc097944eb7ed8270bb03ee05bab99959a3b36a208706a68c73d4f697986.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/8e59dc097944eb7ed8270bb03ee05bab99959a3b36a208706a68c73d4f697986.jpg)

![916d4868e430a0a2337d083c254abdef0e6fc46dcedbed629b0593e19ac70fb0.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/916d4868e430a0a2337d083c254abdef0e6fc46dcedbed629b0593e19ac70fb0.jpg)

![b424035ed29e2ff7fa7595ff86a3221256eaebc2e66f29959ae95bcca3f6385f.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/b424035ed29e2ff7fa7595ff86a3221256eaebc2e66f29959ae95bcca3f6385f.jpg)

![d53f5d39dcd201d1de6d43b39ce8f2e761ffa1d28f12ae06aff34b10e580b1a9.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/d53f5d39dcd201d1de6d43b39ce8f2e761ffa1d28f12ae06aff34b10e580b1a9.jpg)

![f695741b0f31743f64cc12b4199733930248f57f2271ad9b2b8e4606be91ee97.jpg](../nips_results/3864_LayerIF_%20Estimating%20Layer%20Quality%20for%20Large%20Language%20Models%20using%20Influence%20Functions/tables/f695741b0f31743f64cc12b4199733930248f57f2271ad9b2b8e4606be91ee97.jpg)

## Amortized Sampling with Transferable Normalizing Flows


### Images

![15ad1c92981f2fb285a95bdcee257fe025ac240e9c418ab1594ea2c2f0d0424d.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/15ad1c92981f2fb285a95bdcee257fe025ac240e9c418ab1594ea2c2f0d0424d.jpg)

![2483f486e83e63df61b56d6e2686c04414947f6d22fa61e4bec37fc904c76d10.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/2483f486e83e63df61b56d6e2686c04414947f6d22fa61e4bec37fc904c76d10.jpg)

![337ed5186797ac3ea85fc8132608a4aa02ef26b451b7d780c6c107a1ee98a99d.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/337ed5186797ac3ea85fc8132608a4aa02ef26b451b7d780c6c107a1ee98a99d.jpg)

![4c4487db93d5e279d6dc4c275464f467c79e490f1b3aa577e78729c19961a605.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/4c4487db93d5e279d6dc4c275464f467c79e490f1b3aa577e78729c19961a605.jpg)

![4f632a55c5aa175b3ea2f31af1e5b9be3ea06d026b73363656f47767c099a4ed.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/4f632a55c5aa175b3ea2f31af1e5b9be3ea06d026b73363656f47767c099a4ed.jpg)

![6fed602f6744a4ebd150fe7d163823007965c6f668403e1b8694ac20c899c11c.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/6fed602f6744a4ebd150fe7d163823007965c6f668403e1b8694ac20c899c11c.jpg)

![7ba088faa235e4302df8c3389c80fc5205e0072b492b1bf532380eb128ef62f6.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/7ba088faa235e4302df8c3389c80fc5205e0072b492b1bf532380eb128ef62f6.jpg)

![a124d4bb7c07701cb5b8434bfe4ef8689becf01ea745d694a800a36b8f5a5d17.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/a124d4bb7c07701cb5b8434bfe4ef8689becf01ea745d694a800a36b8f5a5d17.jpg)

![a2675c715941eda91529abdf4c2322960337e2da1d5025e52c00f69b2574cd46.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/a2675c715941eda91529abdf4c2322960337e2da1d5025e52c00f69b2574cd46.jpg)

![ab5fd05b09461da5d41a5f4c3e5b3f459fccbda10467856ee7e71712dc75aef9.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/ab5fd05b09461da5d41a5f4c3e5b3f459fccbda10467856ee7e71712dc75aef9.jpg)

![ca6e3c56dc9cdb07966284c1ba67b4f2ab8f27c4043f99d63758240d15199d35.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/ca6e3c56dc9cdb07966284c1ba67b4f2ab8f27c4043f99d63758240d15199d35.jpg)

![dcce2bab079900954374cc75b0081848c195e4cd17f549ad14cd3ad90b5c184a.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/images/dcce2bab079900954374cc75b0081848c195e4cd17f549ad14cd3ad90b5c184a.jpg)

### Tables

![0b5e347c71340ac82d5cf6d040cb9a622701bf5106ff0bbc8fc465dcdd67807a.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/0b5e347c71340ac82d5cf6d040cb9a622701bf5106ff0bbc8fc465dcdd67807a.jpg)

![2190d0bc9c3b21c2388dec0dcdf674854754d16f3669a0abfca44da0fa2e72ee.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/2190d0bc9c3b21c2388dec0dcdf674854754d16f3669a0abfca44da0fa2e72ee.jpg)

![2c2523f3d4654c89a50dbb353af9c3e16b5475d474e5a61cfdaa01bd713504e2.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/2c2523f3d4654c89a50dbb353af9c3e16b5475d474e5a61cfdaa01bd713504e2.jpg)

![37f3240275aef2ce46dab3f9e444fee6853ddb46048b73d2dd2916e67ecda25b.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/37f3240275aef2ce46dab3f9e444fee6853ddb46048b73d2dd2916e67ecda25b.jpg)

![45f7032ba8c9303cab9db3e750ab9b6fed0fee48276de6d7464c80d2e145f190.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/45f7032ba8c9303cab9db3e750ab9b6fed0fee48276de6d7464c80d2e145f190.jpg)

![4bb69e1c2d6b71affc1b3efbe15a2571042f89bd7e0b59d59d43fbc194e34ca4.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/4bb69e1c2d6b71affc1b3efbe15a2571042f89bd7e0b59d59d43fbc194e34ca4.jpg)

![702dc1d03fa9781e5902dddf47df3724ca30a42dd5e7241f32112e9135848bd2.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/702dc1d03fa9781e5902dddf47df3724ca30a42dd5e7241f32112e9135848bd2.jpg)

![81f99b0553cbd28b5148224466220ad60bc2d95a29c1ff3ecbd0a9ac709bb2dd.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/81f99b0553cbd28b5148224466220ad60bc2d95a29c1ff3ecbd0a9ac709bb2dd.jpg)

![9700de026d86bec2f3238f19f15f4b512785e07a98609e5b27c0fde17771a9ec.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/9700de026d86bec2f3238f19f15f4b512785e07a98609e5b27c0fde17771a9ec.jpg)

![cd7f4221c9bb3c3c0e6e68bc18bb36626eee5085db5412508b7dd181cee0a183.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/cd7f4221c9bb3c3c0e6e68bc18bb36626eee5085db5412508b7dd181cee0a183.jpg)

![d1eda3756d07d0b1742da561450a3efeb6a8bf054b21464c1f3e898dff38d693.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/d1eda3756d07d0b1742da561450a3efeb6a8bf054b21464c1f3e898dff38d693.jpg)

![eee5d9a2f3eb6d0e6d41ad570423b24341b1952b7d9dc3f1eb444d04f45dff7a.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/eee5d9a2f3eb6d0e6d41ad570423b24341b1952b7d9dc3f1eb444d04f45dff7a.jpg)

![f4b31bc1ef55a635cb635887c15af3d78bb1ca87cbfe028e2b95272f98006d08.jpg](../nips_results/3865_Amortized%20Sampling%20with%20Transferable%20Normalizing%20Flows/tables/f4b31bc1ef55a635cb635887c15af3d78bb1ca87cbfe028e2b95272f98006d08.jpg)

## BridgePure: Limited Protection Leakage Can Break Black-Box Data Protection


### Images

![06b00087041bb75c2a304360b227aa02f36b28c8e1c1c04a02756b46d10dbf37.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/06b00087041bb75c2a304360b227aa02f36b28c8e1c1c04a02756b46d10dbf37.jpg)

![0ad5df74ebd1bbbdd9f3ff2bcf009f520c44735098a0d5d13264b56ba3808475.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/0ad5df74ebd1bbbdd9f3ff2bcf009f520c44735098a0d5d13264b56ba3808475.jpg)

![16912f6a98bbebddecb7056edbc918afe832067691d2bb07365e6cd520914ce1.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/16912f6a98bbebddecb7056edbc918afe832067691d2bb07365e6cd520914ce1.jpg)

![5217e7009635f06cc3e8fd41a2db4d5b433af37df788969d9c17000b277bd117.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/5217e7009635f06cc3e8fd41a2db4d5b433af37df788969d9c17000b277bd117.jpg)

![70bbfcd15bde7af25921cf2a68799c056865e467c16b5295b22fe639198fdf7f.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/70bbfcd15bde7af25921cf2a68799c056865e467c16b5295b22fe639198fdf7f.jpg)

![73f6f56c9718888885d42365ddeb845893e9f1dcc2021f3dc9c226858b3ce742.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/73f6f56c9718888885d42365ddeb845893e9f1dcc2021f3dc9c226858b3ce742.jpg)

![9adb64a7a514d54254d6cb16cf342535095f4f0d93cb4190f1d639557c6f51d5.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/9adb64a7a514d54254d6cb16cf342535095f4f0d93cb4190f1d639557c6f51d5.jpg)

![9af3162ca1162d032e32692da7780664d19939170497cac880727adcf901fa04.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/9af3162ca1162d032e32692da7780664d19939170497cac880727adcf901fa04.jpg)

![9b1a4f713553ba6dc69a812921557f547791f2b3faa6c5d75423bbb70af2daa6.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/9b1a4f713553ba6dc69a812921557f547791f2b3faa6c5d75423bbb70af2daa6.jpg)

![ab6f930053de4963a3c017c423e9695e0b9c0c43d34d3c5c9fcdc1a47521a469.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/ab6f930053de4963a3c017c423e9695e0b9c0c43d34d3c5c9fcdc1a47521a469.jpg)

![b2819a4e7ea1db3960d0e15909c6f527fea3c1b62d6209cff46ce8f9b05c1d34.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/b2819a4e7ea1db3960d0e15909c6f527fea3c1b62d6209cff46ce8f9b05c1d34.jpg)

![b71dac38f9d289083e4728cd94edc8f78106b12274bc2d3afb3fbe79ccfb78ed.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/b71dac38f9d289083e4728cd94edc8f78106b12274bc2d3afb3fbe79ccfb78ed.jpg)

![bc58455965bd80c269cebe266bc4e489e30658a20182020de95b4199659800d7.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/bc58455965bd80c269cebe266bc4e489e30658a20182020de95b4199659800d7.jpg)

![d327657659f2ea9a04123bce15b53ef1aeb8b1f668c9b36ae14fbccc74a33d28.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/d327657659f2ea9a04123bce15b53ef1aeb8b1f668c9b36ae14fbccc74a33d28.jpg)

![de1ff273156db677ac9ed80ed915d12b5f25c1a700e210578d167ba5a98132fd.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/de1ff273156db677ac9ed80ed915d12b5f25c1a700e210578d167ba5a98132fd.jpg)

![e6d4544949f1ec4666fa283d91cbd2d459c2da7e39cfbe6c396b89af159925c7.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/e6d4544949f1ec4666fa283d91cbd2d459c2da7e39cfbe6c396b89af159925c7.jpg)

![ee08f2c7397e4e6d75116e6242aca5e4bd4a8fc2ebe7b817b19af0df8287ad11.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/images/ee08f2c7397e4e6d75116e6242aca5e4bd4a8fc2ebe7b817b19af0df8287ad11.jpg)

### Tables

![1f8e941c88f4ce694d79a3937857b86c137cfb14df162c51b1acf5ca4b9149e8.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/tables/1f8e941c88f4ce694d79a3937857b86c137cfb14df162c51b1acf5ca4b9149e8.jpg)

![70c217fe75cc1f2494ac888a74b0d39695d074e8802b0a35760ee8c1a140d4db.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/tables/70c217fe75cc1f2494ac888a74b0d39695d074e8802b0a35760ee8c1a140d4db.jpg)

![942e59abc75772c6d8286a11411b148d94f4d508d3e07fd20601e4a395abb683.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/tables/942e59abc75772c6d8286a11411b148d94f4d508d3e07fd20601e4a395abb683.jpg)

![b1cfd0f0a83badfe33558626f10ae9c9d5fd2bbed193b34e8a07f9b7376ce9e5.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/tables/b1cfd0f0a83badfe33558626f10ae9c9d5fd2bbed193b34e8a07f9b7376ce9e5.jpg)

![d7627e935142c84868c2177e8d8426181dd9edca996ef4947d8a6fd35423219d.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/tables/d7627e935142c84868c2177e8d8426181dd9edca996ef4947d8a6fd35423219d.jpg)

![f2a563bfc719b8327c47bed6e90270c3f0b1a32d2930e21f1c9bb1bc677f1306.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/tables/f2a563bfc719b8327c47bed6e90270c3f0b1a32d2930e21f1c9bb1bc677f1306.jpg)

![f5f52136b0ffb4371293eaeab09d26ae63356cfa3685b9a3e6a247fc9e5ad064.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/tables/f5f52136b0ffb4371293eaeab09d26ae63356cfa3685b9a3e6a247fc9e5ad064.jpg)

![fb26ffd7cb1ff6e660e5c55e0ed6fd90352ce3a2f8137d768bfec686da64e744.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/tables/fb26ffd7cb1ff6e660e5c55e0ed6fd90352ce3a2f8137d768bfec686da64e744.jpg)

![fe2206c5949c17c4f65fafc2592798a068404b7436bfdd90b133943f071f2dcb.jpg](../nips_results/3866_BridgePure_%20Limited%20Protection%20Leakage%20Can%20Break%20Black-Box%20Data%20Protection/tables/fe2206c5949c17c4f65fafc2592798a068404b7436bfdd90b133943f071f2dcb.jpg)

## SPC: Evolving Self-Play Critic via Adversarial Games for LLM Reasoning


### Images

![07eb4c1cf06815a721dca577ead77575d5dc71b919f85b15e0f60fa719fa3a80.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/images/07eb4c1cf06815a721dca577ead77575d5dc71b919f85b15e0f60fa719fa3a80.jpg)

![1648af9881ff52e6a3971f1624fa1f3cb8ac70e0afe0532276d9e76985da058d.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/images/1648af9881ff52e6a3971f1624fa1f3cb8ac70e0afe0532276d9e76985da058d.jpg)

![31b9ddc52ebf2158088403915515e055ed508d305d1fd0393e2d9753ad1bdb99.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/images/31b9ddc52ebf2158088403915515e055ed508d305d1fd0393e2d9753ad1bdb99.jpg)

![410244f6bfe32fb173a9b2a682e9e637826f70cf86c4f52c3b897fba8142e0ed.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/images/410244f6bfe32fb173a9b2a682e9e637826f70cf86c4f52c3b897fba8142e0ed.jpg)

![5db40407bf098281b6683dc79d171a9cd8c2056a0732065b5b71493a1b1f178c.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/images/5db40407bf098281b6683dc79d171a9cd8c2056a0732065b5b71493a1b1f178c.jpg)

![6fb19fd749474f8799836b006a4187caafc7ab718c0cd4c632bf335d35c6104e.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/images/6fb19fd749474f8799836b006a4187caafc7ab718c0cd4c632bf335d35c6104e.jpg)

![7deed55cd7a315bd243a040ec4415262ccd0f43199a299a8a6f497ba85bef2d3.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/images/7deed55cd7a315bd243a040ec4415262ccd0f43199a299a8a6f497ba85bef2d3.jpg)

![7f10b331f7d0af4c8058c34fe96f4edc91a568072f5ff8b456e4bf83dd472c9b.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/images/7f10b331f7d0af4c8058c34fe96f4edc91a568072f5ff8b456e4bf83dd472c9b.jpg)

![b60d8b004615027062208e4c2633b6a448e9ad646f22909987935da79c08a4d8.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/images/b60d8b004615027062208e4c2633b6a448e9ad646f22909987935da79c08a4d8.jpg)

### Tables

![67846c47150d6543e406e44ae85c791723900293ac5d0a2e19602d6f368f1923.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/tables/67846c47150d6543e406e44ae85c791723900293ac5d0a2e19602d6f368f1923.jpg)

![f1f0fadec68b18033159213f7ce4b8d59ad07b1be5594f096b413359feb2ec5b.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/tables/f1f0fadec68b18033159213f7ce4b8d59ad07b1be5594f096b413359feb2ec5b.jpg)

![f68b2cf80f3a137db88110c0d24530aa30446e92800778e21d9d887ad7324e76.jpg](../nips_results/3867_SPC_%20Evolving%20Self-Play%20Critic%20via%20Adversarial%20Games%20for%20LLM%20Reasoning/tables/f68b2cf80f3a137db88110c0d24530aa30446e92800778e21d9d887ad7324e76.jpg)

## Unsupervised Learning for Optimal Transport plan prediction between unbalanced graphs


### Images

![1277a08519dc1c90938f6cba6ce70262ab4b6bc56b75b0873563222b8adab870.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/images/1277a08519dc1c90938f6cba6ce70262ab4b6bc56b75b0873563222b8adab870.jpg)

![18feba3b3ecb2eca52a1900ac6f73e18a375b28e8c14fb81aff2e530680b749b.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/images/18feba3b3ecb2eca52a1900ac6f73e18a375b28e8c14fb81aff2e530680b749b.jpg)

![1f4da93ab98886919eb6e57852b5f6287b2800679b5d020c59db9e7c5e1e4496.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/images/1f4da93ab98886919eb6e57852b5f6287b2800679b5d020c59db9e7c5e1e4496.jpg)

![21decd5e3e8d9bf00425792fc1375a93bd59504fbd91226e00d1c1fef0899b4f.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/images/21decd5e3e8d9bf00425792fc1375a93bd59504fbd91226e00d1c1fef0899b4f.jpg)

![224df753d6d408129db7dec5f5e1cf862624691cd59e9bdcd84d3659e2e2431a.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/images/224df753d6d408129db7dec5f5e1cf862624691cd59e9bdcd84d3659e2e2431a.jpg)

![4ae5c51c07c4a651850d87b5a3e8d8e92689e8d0f3b4bcd7b5dc2aab2a547ae5.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/images/4ae5c51c07c4a651850d87b5a3e8d8e92689e8d0f3b4bcd7b5dc2aab2a547ae5.jpg)

![84b50eca49075c7e3e1eecc9876c64f672846acaa15ad52068e4b9e1e907bef0.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/images/84b50eca49075c7e3e1eecc9876c64f672846acaa15ad52068e4b9e1e907bef0.jpg)

![8fa9a91e734e737a2ec59de11a83e7d98fcbbb2a1939bfda7dff5145884395ab.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/images/8fa9a91e734e737a2ec59de11a83e7d98fcbbb2a1939bfda7dff5145884395ab.jpg)

![e565359515f1cf331bad76718a890b7ec359e786708578b772b2d3ab0ae7549f.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/images/e565359515f1cf331bad76718a890b7ec359e786708578b772b2d3ab0ae7549f.jpg)

![e626c6be60d83c462945974f9ca0ad34eac2d6020c64fb2ce8cf68b1b3cf1873.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/images/e626c6be60d83c462945974f9ca0ad34eac2d6020c64fb2ce8cf68b1b3cf1873.jpg)

![fca85b23a4fe5f7ed5783ddce71b104e14c1e7afc3271f192012b7697f5a250c.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/images/fca85b23a4fe5f7ed5783ddce71b104e14c1e7afc3271f192012b7697f5a250c.jpg)

### Tables

![5ceb256b9e6c3a2b64490b6235d18d2d1607bcfd4794c9cb2c45a73646f13f2f.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/tables/5ceb256b9e6c3a2b64490b6235d18d2d1607bcfd4794c9cb2c45a73646f13f2f.jpg)

![6b6956bc36b588f27c6db14b30178332b3d9617de32f2a4546bc0bb9d2d356b1.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/tables/6b6956bc36b588f27c6db14b30178332b3d9617de32f2a4546bc0bb9d2d356b1.jpg)

![975cf9b284a4afaa48ec6b4b698b0a096af81b8ee8c78ca89c3b74173fc5ce49.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/tables/975cf9b284a4afaa48ec6b4b698b0a096af81b8ee8c78ca89c3b74173fc5ce49.jpg)

![aa8c9da718bbed1fbc39294a0bfcc01b16f8f266995c4e1dade702d2c947d722.jpg](../nips_results/3868_Unsupervised%20Learning%20for%20Optimal%20Transport%20plan%20prediction%20between%20unbalanced%20graphs/tables/aa8c9da718bbed1fbc39294a0bfcc01b16f8f266995c4e1dade702d2c947d722.jpg)

## Simplicity Prevails: Rethinking Negative Preference Optimization for LLM Unlearning


### Images

![0dc99ce18abd584575bb5e7dd0d1ba57dc3ff66f321b5c4620ea737e1b6b75a9.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/images/0dc99ce18abd584575bb5e7dd0d1ba57dc3ff66f321b5c4620ea737e1b6b75a9.jpg)

![162c7f945956810f195dca8d074dce38f83b86df02ed7e9cebd3dc4c588cee77.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/images/162c7f945956810f195dca8d074dce38f83b86df02ed7e9cebd3dc4c588cee77.jpg)

![27831c3927a0e44413849e7c523977e39b443696f9bbc0d6e09d53145080c4f6.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/images/27831c3927a0e44413849e7c523977e39b443696f9bbc0d6e09d53145080c4f6.jpg)

![2e0a25b6faf3a45ae3876c79eaa0fcbe05b4b4e54233f8bc409618262f42e923.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/images/2e0a25b6faf3a45ae3876c79eaa0fcbe05b4b4e54233f8bc409618262f42e923.jpg)

![3556a6bdd3c4626348b1bc8f140f0836a0744afd44525ffefb4215f42b8be311.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/images/3556a6bdd3c4626348b1bc8f140f0836a0744afd44525ffefb4215f42b8be311.jpg)

![3f8b399a877370cdaa14ea3a3df5685dc83e08d6aa7eadc859844db5757ead6c.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/images/3f8b399a877370cdaa14ea3a3df5685dc83e08d6aa7eadc859844db5757ead6c.jpg)

![558b0d70578390be63ea9123db1a931ba5f8d942ff029c70977460fe42264ae3.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/images/558b0d70578390be63ea9123db1a931ba5f8d942ff029c70977460fe42264ae3.jpg)

![9b4eb320872ad6ffdbb667dea000603d5aa5f31fb00f8aa49e5a260f2c7178bc.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/images/9b4eb320872ad6ffdbb667dea000603d5aa5f31fb00f8aa49e5a260f2c7178bc.jpg)

![b2d7400bff0f5feadadbcdc372364d191bf05d576f4fb5b22c4d22a81f0e8b2c.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/images/b2d7400bff0f5feadadbcdc372364d191bf05d576f4fb5b22c4d22a81f0e8b2c.jpg)

![b7f8bf2c249c8ee979edadc383406d2277f8297cbdf17c5e307df6793adf4e73.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/images/b7f8bf2c249c8ee979edadc383406d2277f8297cbdf17c5e307df6793adf4e73.jpg)

![c4ac958e169a2df2192dad15a8b84c657e63d39fe45d60ab7acfb03e5005e0a7.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/images/c4ac958e169a2df2192dad15a8b84c657e63d39fe45d60ab7acfb03e5005e0a7.jpg)

### Tables

![30228ca7060828086d37b9feee17065c558b6f5844ec479dd407f9d22197feaa.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/tables/30228ca7060828086d37b9feee17065c558b6f5844ec479dd407f9d22197feaa.jpg)

![40d2e43915a8108b3b5b108240c6b1a33d3d58adbb1bb409c9fad1cfa7434657.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/tables/40d2e43915a8108b3b5b108240c6b1a33d3d58adbb1bb409c9fad1cfa7434657.jpg)

![6d3169f3c74cb51ce382ff4da2cc3eb7f50f7c8443da00b03b39d42a2f2c6133.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/tables/6d3169f3c74cb51ce382ff4da2cc3eb7f50f7c8443da00b03b39d42a2f2c6133.jpg)

![8a75a3a7696ecd4b13f6672d69d90aa1cb167bf7ba97b9fc41b7a3f29bb5e9b5.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/tables/8a75a3a7696ecd4b13f6672d69d90aa1cb167bf7ba97b9fc41b7a3f29bb5e9b5.jpg)

![91eaae60cebbdb3ef326b95fd310934f2c297bd56ec9494c37656307f81115c7.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/tables/91eaae60cebbdb3ef326b95fd310934f2c297bd56ec9494c37656307f81115c7.jpg)

![9d9df990467b7764ca1fe22757bb4f9fc16dd37751617c28de9efd8b6c44a82a.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/tables/9d9df990467b7764ca1fe22757bb4f9fc16dd37751617c28de9efd8b6c44a82a.jpg)

![a2fc9f1f54d211c0be4818f8a70d7dae927605643a5e85fffc5160cd48e49d44.jpg](../nips_results/3869_Simplicity%20Prevails_%20Rethinking%20Negative%20Preference%20Optimization%20for%20LLM%20Unlearning/tables/a2fc9f1f54d211c0be4818f8a70d7dae927605643a5e85fffc5160cd48e49d44.jpg)

## OmniConsistency: Learning Style-Agnostic Consistency from Paired Stylization Data


### Images

![016f06f6f48b1b9c8cb540db072cbacfc14d94e1f59ae00d978593e28b4629e0.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/images/016f06f6f48b1b9c8cb540db072cbacfc14d94e1f59ae00d978593e28b4629e0.jpg)

![06120e7c300675a10b789abd4cfdf8984dfe9ef7a69e895c085560d2b2078b35.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/images/06120e7c300675a10b789abd4cfdf8984dfe9ef7a69e895c085560d2b2078b35.jpg)

![2ed7b0b61eddcbd926dd87a6f8c215a78cb61a2218b057e1b9870dc7eaa07894.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/images/2ed7b0b61eddcbd926dd87a6f8c215a78cb61a2218b057e1b9870dc7eaa07894.jpg)

![3558eb3f2f9f6ec0a65af024b1debaebb2864f4e8ec0c46a2bf17f93678a9bcf.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/images/3558eb3f2f9f6ec0a65af024b1debaebb2864f4e8ec0c46a2bf17f93678a9bcf.jpg)

![48ced9febf28230054f6a1a6f1c49e3bdbbcb47963bfd5c1f531752ae5fdc2ca.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/images/48ced9febf28230054f6a1a6f1c49e3bdbbcb47963bfd5c1f531752ae5fdc2ca.jpg)

![5c7f6a7ad89007faec3aadc7b43591953f7aa238aed3b3dd55640b8fbee0c2e1.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/images/5c7f6a7ad89007faec3aadc7b43591953f7aa238aed3b3dd55640b8fbee0c2e1.jpg)

![6675caa006696ad0d8c44e0502f1fed7accc67854b1b36ecde03f8ed91eeb9a3.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/images/6675caa006696ad0d8c44e0502f1fed7accc67854b1b36ecde03f8ed91eeb9a3.jpg)

![766112acd31ad44b09e21f009a6d2b3aaeba7aa86b710d8dca42348c1e326d31.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/images/766112acd31ad44b09e21f009a6d2b3aaeba7aa86b710d8dca42348c1e326d31.jpg)

![ddefefa3ea20625f2100482e337bf9dabc750a120651182773728678b664f3e0.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/images/ddefefa3ea20625f2100482e337bf9dabc750a120651182773728678b664f3e0.jpg)

![fb71b8c219c078860d0c9b0f09d59e541e114c470d85ac38d7f0d23b58dfd772.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/images/fb71b8c219c078860d0c9b0f09d59e541e114c470d85ac38d7f0d23b58dfd772.jpg)

![fe29c271f9274308b145f3ca4c41f6573083004c2330338c48d6019941dfa222.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/images/fe29c271f9274308b145f3ca4c41f6573083004c2330338c48d6019941dfa222.jpg)

### Tables

![6deefad2e102b9d1ee66fcb84212ffbd2aaaec1147702bd6cfc7ea010aa578e9.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/tables/6deefad2e102b9d1ee66fcb84212ffbd2aaaec1147702bd6cfc7ea010aa578e9.jpg)

![e0bdfb9250cffcbba26ba9ed316a0d4a1abbb351b755d7be9240623c174b969f.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/tables/e0bdfb9250cffcbba26ba9ed316a0d4a1abbb351b755d7be9240623c174b969f.jpg)

![f3507f10560ac69c0815e39a3a6fb4f7a7c680ed2ce53ff4c47dc179770d8cde.jpg](../nips_results/3870_OmniConsistency_%20Learning%20Style-Agnostic%20Consistency%20from%20Paired%20Stylization%20Data/tables/f3507f10560ac69c0815e39a3a6fb4f7a7c680ed2ce53ff4c47dc179770d8cde.jpg)

## High-order Interactions Modeling for Interpretable Multi-Agent Q-Learning


### Images

![06487f1e61abb532878b884dd5230beae901e9c73a1e56f2a80968cf3fe5d27e.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/06487f1e61abb532878b884dd5230beae901e9c73a1e56f2a80968cf3fe5d27e.jpg)

![06a36ce98f613e07ee200c922fe2f9d229299556b34b4621d9c60151eb43683b.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/06a36ce98f613e07ee200c922fe2f9d229299556b34b4621d9c60151eb43683b.jpg)

![09e9de1251288758db75f196a94509e8c229ca545ceada657cd150f262fc2379.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/09e9de1251288758db75f196a94509e8c229ca545ceada657cd150f262fc2379.jpg)

![14cc42e33fa6c1a1f112051af9ec8068defe26aa0225f5abf447454036a0f532.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/14cc42e33fa6c1a1f112051af9ec8068defe26aa0225f5abf447454036a0f532.jpg)

![2eb489fe0ad9ab3fa3e5c3b9b2a7245648cb701d0b13b8ad3dc1e1e5bfec16e7.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/2eb489fe0ad9ab3fa3e5c3b9b2a7245648cb701d0b13b8ad3dc1e1e5bfec16e7.jpg)

![333a0c9a75141e7a849e9d0dbf2d406b6d0948c7aeaf2d33aeaec100a7254383.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/333a0c9a75141e7a849e9d0dbf2d406b6d0948c7aeaf2d33aeaec100a7254383.jpg)

![373e9fbdd9e2b0d6fad6743205c44130d9c675f4c342c2ea2ccadbb59c389501.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/373e9fbdd9e2b0d6fad6743205c44130d9c675f4c342c2ea2ccadbb59c389501.jpg)

![3ed6ac7863796d7e298bd377ff5e9ce2ffd2614881ec93d7c950b3a24f130672.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/3ed6ac7863796d7e298bd377ff5e9ce2ffd2614881ec93d7c950b3a24f130672.jpg)

![6b93a9e45ca7d825bbf85c70b3f6b1dadac639f911a59327678717be51c39742.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/6b93a9e45ca7d825bbf85c70b3f6b1dadac639f911a59327678717be51c39742.jpg)

![7ee4b4f446ca53188d66dab96301e490762a3f055907162a339cb4d36c64d3f7.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/7ee4b4f446ca53188d66dab96301e490762a3f055907162a339cb4d36c64d3f7.jpg)

![934b6660f55104914d57df5ecb8a47dad1e8ef8d07e0313cc437ce94853a7767.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/934b6660f55104914d57df5ecb8a47dad1e8ef8d07e0313cc437ce94853a7767.jpg)

![be1bf160b1381950ae89d815e9894e8691dcbfc91c8ab610bd55bfac1eefa6bc.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/be1bf160b1381950ae89d815e9894e8691dcbfc91c8ab610bd55bfac1eefa6bc.jpg)

![cb495e325a0f9146ca8c541011b07a1ad7b525d1fe99c997e6f4b10942710ea4.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/cb495e325a0f9146ca8c541011b07a1ad7b525d1fe99c997e6f4b10942710ea4.jpg)

![fbcebc2902cdefe376b18b43dc10bf2dd9c124a6cef786230dc9ef5cd2998571.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/images/fbcebc2902cdefe376b18b43dc10bf2dd9c124a6cef786230dc9ef5cd2998571.jpg)

### Tables

![44e489dc00770a143fee28b23e7671d218cc4585bd3b32f29811b3dae237251a.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/tables/44e489dc00770a143fee28b23e7671d218cc4585bd3b32f29811b3dae237251a.jpg)

![8873939e3990fefdc64738fb2eebfb72762ec490e2d7cb8e7cab5b2c3132bb2e.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/tables/8873939e3990fefdc64738fb2eebfb72762ec490e2d7cb8e7cab5b2c3132bb2e.jpg)

![b2951e7e5567607ed32d5390299785e04b6a3bdf71016d6791e1f9924d7447bb.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/tables/b2951e7e5567607ed32d5390299785e04b6a3bdf71016d6791e1f9924d7447bb.jpg)

![c07c352c68c44e254356a1d194bee1a093adbfda7cacb2a77ddc9dd2077f67f0.jpg](../nips_results/3871_High-order%20Interactions%20Modeling%20for%20Interpretable%20Multi-Agent%20Q-Learning/tables/c07c352c68c44e254356a1d194bee1a093adbfda7cacb2a77ddc9dd2077f67f0.jpg)

## Quantum Speedups for Minimax Optimization and Beyond


### Tables

![b328bccf898e6dafbff0a29877e4c08b22ba77bb2dd4876c0f06b4bbdbbdde7d.jpg](../nips_results/3872_Quantum%20Speedups%20for%20Minimax%20Optimization%20and%20Beyond/tables/b328bccf898e6dafbff0a29877e4c08b22ba77bb2dd4876c0f06b4bbdbbdde7d.jpg)

![ef2ec5834ee1182a83bec831743e80e56b7985ec5ba86756f652088fec583a33.jpg](../nips_results/3872_Quantum%20Speedups%20for%20Minimax%20Optimization%20and%20Beyond/tables/ef2ec5834ee1182a83bec831743e80e56b7985ec5ba86756f652088fec583a33.jpg)

![f3c1524f567d619e184a09020f1ccef6cf219bea013706b53f854e771dccc0eb.jpg](../nips_results/3872_Quantum%20Speedups%20for%20Minimax%20Optimization%20and%20Beyond/tables/f3c1524f567d619e184a09020f1ccef6cf219bea013706b53f854e771dccc0eb.jpg)

## Graph-based Symbolic Regression with Invariance and Constraint Encoding


### Images

![3cba6ca6c437d60321ebda409b0ae02b4647b78a5255fed8aaf6644adf049cb5.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/images/3cba6ca6c437d60321ebda409b0ae02b4647b78a5255fed8aaf6644adf049cb5.jpg)

![4d1e398a52ee3a7d693927c80fe0fbf9082f6d40d9363d0d5d7b77ae8292f45e.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/images/4d1e398a52ee3a7d693927c80fe0fbf9082f6d40d9363d0d5d7b77ae8292f45e.jpg)

![61d946c54ba5307e7e092ab5dad0c57638b0e92c808a13b10f4ffee54616c82b.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/images/61d946c54ba5307e7e092ab5dad0c57638b0e92c808a13b10f4ffee54616c82b.jpg)

![6428e88ca9e81068a74dada93cd76c1a6f4487b3e9567367c6cb99ce9c9be0ad.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/images/6428e88ca9e81068a74dada93cd76c1a6f4487b3e9567367c6cb99ce9c9be0ad.jpg)

![6de54d4a72febaceb062df3b6f0c2af95fa9f3e05fd4921fb91173378999d9a8.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/images/6de54d4a72febaceb062df3b6f0c2af95fa9f3e05fd4921fb91173378999d9a8.jpg)

![9d2cc67e147fd42098196373b972c44abff601b48e9c1ef7315be64a84aca084.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/images/9d2cc67e147fd42098196373b972c44abff601b48e9c1ef7315be64a84aca084.jpg)

![d43064d650086b834eb3199d5bbcaa0e5a880e65961d11c443c556a02da0c7d5.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/images/d43064d650086b834eb3199d5bbcaa0e5a880e65961d11c443c556a02da0c7d5.jpg)

### Tables

![025ccb8422dedbd8980dabe06eb9c455f72619a1be28ee040efa80ae0c9af8a2.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/tables/025ccb8422dedbd8980dabe06eb9c455f72619a1be28ee040efa80ae0c9af8a2.jpg)

![6888b030aa8d483e650ace3c6934dde05785677d2a58f6b2c164932799adce82.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/tables/6888b030aa8d483e650ace3c6934dde05785677d2a58f6b2c164932799adce82.jpg)

![8acb4f6b01c675032fd57f10529feb0ff598a6ce333acc66f607258c05e92a2c.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/tables/8acb4f6b01c675032fd57f10529feb0ff598a6ce333acc66f607258c05e92a2c.jpg)

![9b562d22f38ef29acedce7db3d404a43d4c17113f0d650937fd5376d9ddb0933.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/tables/9b562d22f38ef29acedce7db3d404a43d4c17113f0d650937fd5376d9ddb0933.jpg)

![e12797dfd04e936c04f5eca05e4edbc78ec960aaf1fd821ce2563b424ac423fd.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/tables/e12797dfd04e936c04f5eca05e4edbc78ec960aaf1fd821ce2563b424ac423fd.jpg)

![eb3866b937f993bf9f6db5d58689018b7c39964ed6fdceac44552a97f1c2e91c.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/tables/eb3866b937f993bf9f6db5d58689018b7c39964ed6fdceac44552a97f1c2e91c.jpg)

![ec34650e06cc868c3390d6242e7f8d971fb26337bf76c316dac870d995c088fa.jpg](../nips_results/3873_Graph-based%20Symbolic%20Regression%20with%20Invariance%20and%20Constraint%20Encoding/tables/ec34650e06cc868c3390d6242e7f8d971fb26337bf76c316dac870d995c088fa.jpg)

## Harnessing Feature Resonance under Arbitrary Target Alignment for Out-of-Distribution Node Detection


### Images

![028ee6c6caea813f328fda47e1174a4904ed1233c50e7c6aae3005b79fd167a7.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/images/028ee6c6caea813f328fda47e1174a4904ed1233c50e7c6aae3005b79fd167a7.jpg)

![4b75d657a983923bc5059cf963c4fb3e32a33d6701f96c5468013dc97fa28935.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/images/4b75d657a983923bc5059cf963c4fb3e32a33d6701f96c5468013dc97fa28935.jpg)

![787762e77a07ef789f0f766d807756943f4de3e4766e327c8a50dccd7907c9d2.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/images/787762e77a07ef789f0f766d807756943f4de3e4766e327c8a50dccd7907c9d2.jpg)

![7c4c89df8036d4d7d4a36839efd4eb0a4cfb722164cb165a2978b96d00266a3c.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/images/7c4c89df8036d4d7d4a36839efd4eb0a4cfb722164cb165a2978b96d00266a3c.jpg)

![7dc2cdcfa2a2b020b09c4dafe618532a874bacf51e288d7a814cc00fae0b3cb7.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/images/7dc2cdcfa2a2b020b09c4dafe618532a874bacf51e288d7a814cc00fae0b3cb7.jpg)

![93bcb767d143f33fe75189cd9d4607ca9a5734b9b2fddae5cbe9810691b6730a.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/images/93bcb767d143f33fe75189cd9d4607ca9a5734b9b2fddae5cbe9810691b6730a.jpg)

![b6808fe4345418f35fb80b2ce484a3793f2f3e5b80623ee70c4076a8be43bd89.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/images/b6808fe4345418f35fb80b2ce484a3793f2f3e5b80623ee70c4076a8be43bd89.jpg)

### Tables

![355a0952be581991b31518df3bd5725278fbfae866f7e9e2fb57c1b0f23e2290.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/355a0952be581991b31518df3bd5725278fbfae866f7e9e2fb57c1b0f23e2290.jpg)

![394ff7e970c9571f757843fee3ef1ddb507756db9453c47a505c497e16b26159.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/394ff7e970c9571f757843fee3ef1ddb507756db9453c47a505c497e16b26159.jpg)

![3cbda2ac19bcd2ec2eea89cfb43884f873a6b1dbe01921aba95af85b3dc0ee3b.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/3cbda2ac19bcd2ec2eea89cfb43884f873a6b1dbe01921aba95af85b3dc0ee3b.jpg)

![498f50dfb855d3c221b7cb0f1c673e08364dd44110060a205913846383bd3382.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/498f50dfb855d3c221b7cb0f1c673e08364dd44110060a205913846383bd3382.jpg)

![51386afbe9ccb6e402323487a29f1dd861d7e9698f59ca704b1159e4b36bd21a.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/51386afbe9ccb6e402323487a29f1dd861d7e9698f59ca704b1159e4b36bd21a.jpg)

![5639238605197b61b95114eeda3decbc6867b81cfb26e636140ec446c4999e63.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/5639238605197b61b95114eeda3decbc6867b81cfb26e636140ec446c4999e63.jpg)

![77024bd7a95064d781bd22b3cab204c9b375ffd04727e4c7de0b4d5da4fdd45e.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/77024bd7a95064d781bd22b3cab204c9b375ffd04727e4c7de0b4d5da4fdd45e.jpg)

![8ad1e98eb027b9b772e6fa0336510a194ac8b3a22e082e007e84709f7bf207f7.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/8ad1e98eb027b9b772e6fa0336510a194ac8b3a22e082e007e84709f7bf207f7.jpg)

![940c9ec3f47e125664a6a3912c4b558d1e2857e1e6722f9c9228807fcbe951c8.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/940c9ec3f47e125664a6a3912c4b558d1e2857e1e6722f9c9228807fcbe951c8.jpg)

![9dcd0a331af535d2cf43ba8c1809849fb8c80e3759138d75ecdb16a6e8b40cdd.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/9dcd0a331af535d2cf43ba8c1809849fb8c80e3759138d75ecdb16a6e8b40cdd.jpg)

![a27469e1ca6e0d9eb384252c3924e61ad5209caac44fd2bd0bd3bbfa49a260ea.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/a27469e1ca6e0d9eb384252c3924e61ad5209caac44fd2bd0bd3bbfa49a260ea.jpg)

![a32a4536c248e7150acf9c351079acad3b20f7d2d17bdfa267d1ed46806f1ca4.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/a32a4536c248e7150acf9c351079acad3b20f7d2d17bdfa267d1ed46806f1ca4.jpg)

![b4c68f4f575a60973a3978c612f62b3227d652870d81e6e38e04c11ddae87f57.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/b4c68f4f575a60973a3978c612f62b3227d652870d81e6e38e04c11ddae87f57.jpg)

![d1479b9e1ed22d2e7205c52ece4d8151b4423699641148462dddb064de5965a0.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/d1479b9e1ed22d2e7205c52ece4d8151b4423699641148462dddb064de5965a0.jpg)

![e8f9e0fc31cbef9f885c8d45b607249259d40811260c31515e14d33aa266010b.jpg](../nips_results/3874_Harnessing%20Feature%20Resonance%20under%20Arbitrary%20Target%20Alignment%20for%20Out-of-Distribution%20Node%20Detection/tables/e8f9e0fc31cbef9f885c8d45b607249259d40811260c31515e14d33aa266010b.jpg)

## Cost-Efficient LLM Training with Lifetime-Aware Tensor Offloading via GPUDirect Storage


### Images

![0fe5cbdafbd9fd00fc34852ec06b571cfe3aa35f03ac013d1ac79e864c354538.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/0fe5cbdafbd9fd00fc34852ec06b571cfe3aa35f03ac013d1ac79e864c354538.jpg)

![11dea5bab215c783c1c80215fcb19da7514373b5ea892994cb70cbe6f285e6a7.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/11dea5bab215c783c1c80215fcb19da7514373b5ea892994cb70cbe6f285e6a7.jpg)

![15c2111204c2cc66a1f6681f0405e6936d71e12859b5eec4017f96e0c3857586.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/15c2111204c2cc66a1f6681f0405e6936d71e12859b5eec4017f96e0c3857586.jpg)

![1aaa59820d20ce442c300e4f6ad4d60cf474fd063640f732ad03ef667d94cb94.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/1aaa59820d20ce442c300e4f6ad4d60cf474fd063640f732ad03ef667d94cb94.jpg)

![230028d0387aaa307db85cf3c2e3690c45bdef2ed2fc8d3cf44a526bf49d4807.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/230028d0387aaa307db85cf3c2e3690c45bdef2ed2fc8d3cf44a526bf49d4807.jpg)

![2dd909c050bf116ddb87cbbd8b28d974045198b0b467ca09a944e83e2f540b07.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/2dd909c050bf116ddb87cbbd8b28d974045198b0b467ca09a944e83e2f540b07.jpg)

![56a7ef33e82147c8e74562be750ff304e5e00fa30290666e74b2b1ece6b1af9d.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/56a7ef33e82147c8e74562be750ff304e5e00fa30290666e74b2b1ece6b1af9d.jpg)

![7bdbc2117d5aa929169ebb9e240e5d18cba63b4008729ca4879df85c37fc5705.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/7bdbc2117d5aa929169ebb9e240e5d18cba63b4008729ca4879df85c37fc5705.jpg)

![bcf960bcdf3df5510bd2e20bab269d99dabd1a68dff07c978b9585a885219c17.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/bcf960bcdf3df5510bd2e20bab269d99dabd1a68dff07c978b9585a885219c17.jpg)

![c50312a25029bf6e55dd507d30fe26b487a12aa777c983e19bd02579177f9097.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/c50312a25029bf6e55dd507d30fe26b487a12aa777c983e19bd02579177f9097.jpg)

![cd31836e124bbed9a8cfe476e21c24e6b166d0bae655dedc342ae93e02cfe507.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/cd31836e124bbed9a8cfe476e21c24e6b166d0bae655dedc342ae93e02cfe507.jpg)

![d2dd10340257533259c62a28bd27be8e9ccf74c07e5e621576fee311b739149e.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/images/d2dd10340257533259c62a28bd27be8e9ccf74c07e5e621576fee311b739149e.jpg)

### Tables

![3b08be58d97b04d65a40267c488d4a7cf1ef4cba2b9d635d6262bcf6445891c4.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/tables/3b08be58d97b04d65a40267c488d4a7cf1ef4cba2b9d635d6262bcf6445891c4.jpg)

![4287ab47b0df93d91033efa81648b5b7adde4197ecb955c9ad6f85d40ec52e71.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/tables/4287ab47b0df93d91033efa81648b5b7adde4197ecb955c9ad6f85d40ec52e71.jpg)

![730debf49ffe1d0ebd18eeeb23407af4ae58c7dcdbd570fc2ea7c2393a3a3a1b.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/tables/730debf49ffe1d0ebd18eeeb23407af4ae58c7dcdbd570fc2ea7c2393a3a3a1b.jpg)

![ca615fc128fad963c6e8b039d2eed1a8f7ede7d837f042c9738804f2e683300b.jpg](../nips_results/3875_Cost-Efficient%20LLM%20Training%20with%20Lifetime-Aware%20Tensor%20Offloading%20via%20GPUDirect%20Storage/tables/ca615fc128fad963c6e8b039d2eed1a8f7ede7d837f042c9738804f2e683300b.jpg)

## Constrained Best Arm Identification


### Images

![7969ccca4d41613b948670c0a5b7b3db3ed6d9d20303b82f50e3fa4bf001b95a.jpg](../nips_results/3876_Constrained%20Best%20Arm%20Identification/images/7969ccca4d41613b948670c0a5b7b3db3ed6d9d20303b82f50e3fa4bf001b95a.jpg)

![7cb4c38d73513f6a2afbd5e229d36d9bd81ee34adb29bb598f8098db98637e30.jpg](../nips_results/3876_Constrained%20Best%20Arm%20Identification/images/7cb4c38d73513f6a2afbd5e229d36d9bd81ee34adb29bb598f8098db98637e30.jpg)

![bf5ec643e66806fcb99fd0be2bd75b72787ad0c6fc5a3ee5313edcecec2b05bb.jpg](../nips_results/3876_Constrained%20Best%20Arm%20Identification/images/bf5ec643e66806fcb99fd0be2bd75b72787ad0c6fc5a3ee5313edcecec2b05bb.jpg)

### Tables

![2d3371551cb39224601342ef0c3895a3999fbef9ee9dad3d73a80cc240756af7.jpg](../nips_results/3876_Constrained%20Best%20Arm%20Identification/tables/2d3371551cb39224601342ef0c3895a3999fbef9ee9dad3d73a80cc240756af7.jpg)

![a941fce3f6b6513882eaa8f4510d7f81b6684ffd7a00db8aad4f9ac7a20b5414.jpg](../nips_results/3876_Constrained%20Best%20Arm%20Identification/tables/a941fce3f6b6513882eaa8f4510d7f81b6684ffd7a00db8aad4f9ac7a20b5414.jpg)

## Generalizable Hand-Object Modeling from Monocular RGB Images via 3D Gaussians


### Images

![02a5e0ad935c5943bc87d5bf1f4804f15aff21e196352f39dcadbdc1e5b2954f.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/images/02a5e0ad935c5943bc87d5bf1f4804f15aff21e196352f39dcadbdc1e5b2954f.jpg)

![167ffcbb8a583b4f1b0588cb6b3f9ac597c033f079d750f71b40740ed4f43793.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/images/167ffcbb8a583b4f1b0588cb6b3f9ac597c033f079d750f71b40740ed4f43793.jpg)

![2cd7d50881657401b0e907ac8063fa20aa3f6f2a30ca6e827f83655fd16c5b54.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/images/2cd7d50881657401b0e907ac8063fa20aa3f6f2a30ca6e827f83655fd16c5b54.jpg)

![375edec62f3fd15af3ef941a24a6f9071077ef1c3f938185decb15b63ad8167c.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/images/375edec62f3fd15af3ef941a24a6f9071077ef1c3f938185decb15b63ad8167c.jpg)

![80edf708942ffe2e19fbf7a2841cd23b7eac44e8b1a68ae5b559d0261b3e390a.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/images/80edf708942ffe2e19fbf7a2841cd23b7eac44e8b1a68ae5b559d0261b3e390a.jpg)

![bc0c00143c22e722c1f068a031be631b67c4a97ecda42abd606dc4b405892bd8.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/images/bc0c00143c22e722c1f068a031be631b67c4a97ecda42abd606dc4b405892bd8.jpg)

![ca1f66c54e30bc250fe747c008ff40d96fc1de12f6180dcff24fbfedcdecec29.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/images/ca1f66c54e30bc250fe747c008ff40d96fc1de12f6180dcff24fbfedcdecec29.jpg)

### Tables

![1b8018cc11e68e326f1fc3c5c191deeaf9abb710a5f09cdc69b5ba373f93a564.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/tables/1b8018cc11e68e326f1fc3c5c191deeaf9abb710a5f09cdc69b5ba373f93a564.jpg)

![1e0ca848e9f6f77bfabe479f2863ebbf244a92c9129bcfcea27d64cdbe9d99f6.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/tables/1e0ca848e9f6f77bfabe479f2863ebbf244a92c9129bcfcea27d64cdbe9d99f6.jpg)

![65fff070eb8b414abdd198b3c7b9fa4a3f7367d6d97b877fa2479848b6f13e63.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/tables/65fff070eb8b414abdd198b3c7b9fa4a3f7367d6d97b877fa2479848b6f13e63.jpg)

![72b24bec13902a7ac7570358fc4153ef97c8b6c7fabe68758e9437d47d970ac6.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/tables/72b24bec13902a7ac7570358fc4153ef97c8b6c7fabe68758e9437d47d970ac6.jpg)

![9ea3259e1763953619adb31cac2d042e3183327fe87a6175f154f9e6c767fd73.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/tables/9ea3259e1763953619adb31cac2d042e3183327fe87a6175f154f9e6c767fd73.jpg)

![a0be000689526847679c09025eae1e484805fbd279e2065dee863ade6200d9f6.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/tables/a0be000689526847679c09025eae1e484805fbd279e2065dee863ade6200d9f6.jpg)

![ec9f4173ced029342c7a8b5deaaba8887d8316768d46425064e498296ae51956.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/tables/ec9f4173ced029342c7a8b5deaaba8887d8316768d46425064e498296ae51956.jpg)

![f2bb9011258bddb2c46b3614fd06e2e51d207e28deee2637a3ef7ee1892a7b84.jpg](../nips_results/3877_Generalizable%20Hand-Object%20Modeling%20from%20Monocular%20RGB%20Images%20via%203D%20Gaussians/tables/f2bb9011258bddb2c46b3614fd06e2e51d207e28deee2637a3ef7ee1892a7b84.jpg)

## FerretNet: Efficient Synthetic Image Detection via Local Pixel Dependencies


### Images

![0caac5d4dc6e0e3aa4bb62b670b3861b7eb93ba561a09a72a7628d850374c670.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/0caac5d4dc6e0e3aa4bb62b670b3861b7eb93ba561a09a72a7628d850374c670.jpg)

![1b7da7f62651a6a8eb31dff8be71dee93d3a61dde67f4be1826b5c74db60081e.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/1b7da7f62651a6a8eb31dff8be71dee93d3a61dde67f4be1826b5c74db60081e.jpg)

![2dca08c8d107862e4137da19443a04618eaef7dab2bdf48470a39bf587215381.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/2dca08c8d107862e4137da19443a04618eaef7dab2bdf48470a39bf587215381.jpg)

![51eb709220312e0920a01c2a4348e3ce2a672a6c32c7a336e6e13dee2f1d6584.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/51eb709220312e0920a01c2a4348e3ce2a672a6c32c7a336e6e13dee2f1d6584.jpg)

![5d7f85c0c8d39d9cc9a1bac69ffa75fe44a53f8b19dd5ad762d60683b9e184c3.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/5d7f85c0c8d39d9cc9a1bac69ffa75fe44a53f8b19dd5ad762d60683b9e184c3.jpg)

![653bbf57a05759daf9d13ad304fd6d159ec71428f10bb5ea25b605e98e891ba0.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/653bbf57a05759daf9d13ad304fd6d159ec71428f10bb5ea25b605e98e891ba0.jpg)

![7741425234738bcb32fe7357c888a6be8fd6f18e4487e50873be8cd2924a2841.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/7741425234738bcb32fe7357c888a6be8fd6f18e4487e50873be8cd2924a2841.jpg)

![a7c8d7e7f26170a3817cc57709d22f505739d53c1b81cfdfbd9f872a285990e8.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/a7c8d7e7f26170a3817cc57709d22f505739d53c1b81cfdfbd9f872a285990e8.jpg)

![b35756858851b5eef4819ed59338db34c5be3944d22ef19113193424dbfb11e6.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/b35756858851b5eef4819ed59338db34c5be3944d22ef19113193424dbfb11e6.jpg)

![baa0d9bbe26e46412210685494e18e93f20506dd6b98b8487d4b7a0f2fa27097.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/baa0d9bbe26e46412210685494e18e93f20506dd6b98b8487d4b7a0f2fa27097.jpg)

![cfb51f1c626f0504712d053b7ca491d7bb8ed0c58997484551a39b3607e2944b.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/cfb51f1c626f0504712d053b7ca491d7bb8ed0c58997484551a39b3607e2944b.jpg)

![d9381b9ec3fe9caf7ee9f45a71c7098ce07473556e9c7bdad43895627b9a05d9.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/images/d9381b9ec3fe9caf7ee9f45a71c7098ce07473556e9c7bdad43895627b9a05d9.jpg)

### Tables

![06b6d2a67079303bacbc42a4f6adc9dc0c13b1635aaa6f482c4c63c0ca8b25e0.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/tables/06b6d2a67079303bacbc42a4f6adc9dc0c13b1635aaa6f482c4c63c0ca8b25e0.jpg)

![15b49e7aa724bccf5bd181d8fa36c5e057ff4c2a485b796220a567176d2509bf.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/tables/15b49e7aa724bccf5bd181d8fa36c5e057ff4c2a485b796220a567176d2509bf.jpg)

![1f8171f353f9e83fea714538f8b6ac670f776c4f7eb19f5123e1fde66a6010ea.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/tables/1f8171f353f9e83fea714538f8b6ac670f776c4f7eb19f5123e1fde66a6010ea.jpg)

![52265d92b0f82a9acc1962aa9119643499a8a4fe76f031759074d02d8c65597c.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/tables/52265d92b0f82a9acc1962aa9119643499a8a4fe76f031759074d02d8c65597c.jpg)

![650af3aaf282dec26a43dbbfe0bb19d6359b76b1aa4cba85f825d4d6aa35a760.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/tables/650af3aaf282dec26a43dbbfe0bb19d6359b76b1aa4cba85f825d4d6aa35a760.jpg)

![6ebe074e0ded0d7306aa27d5e4eb5e55c8a341909cd7026967b32055ceb45f87.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/tables/6ebe074e0ded0d7306aa27d5e4eb5e55c8a341909cd7026967b32055ceb45f87.jpg)

![a9db823b0c60412af38732f6d0ec885b3365e7dc167b2fbb371bd7dbe87da4b9.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/tables/a9db823b0c60412af38732f6d0ec885b3365e7dc167b2fbb371bd7dbe87da4b9.jpg)

![d9dc22b83e4c0033c5e1f7a4065fd835a101583418119b5454d3f9618b370526.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/tables/d9dc22b83e4c0033c5e1f7a4065fd835a101583418119b5454d3f9618b370526.jpg)

![df61da255121123ab1c590b1fb8359ab0881f254641975757003ffadf1580ac3.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/tables/df61da255121123ab1c590b1fb8359ab0881f254641975757003ffadf1580ac3.jpg)

![eebad368cb0a4b29404981af9a5d27d404394cdc947f208076aed6549a3ff6ea.jpg](../nips_results/3878_FerretNet_%20Efficient%20Synthetic%20Image%20Detection%20via%20Local%20Pixel%20Dependencies/tables/eebad368cb0a4b29404981af9a5d27d404394cdc947f208076aed6549a3ff6ea.jpg)

## Towards Multiscale Graph-based Protein Learning with Geometric Secondary Structural Motifs


### Images

![611892e96e7cb38db03e691e852fbf7898b23524e1bb26260aea068a8a371c95.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/images/611892e96e7cb38db03e691e852fbf7898b23524e1bb26260aea068a8a371c95.jpg)

![974ca4e45c9eba2d614e1776db23823706ff7d1da2ce89cea5b3161b0b2b3447.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/images/974ca4e45c9eba2d614e1776db23823706ff7d1da2ce89cea5b3161b0b2b3447.jpg)

![b29a6cdb442071578d89ea63bad727a5a7465dba6e94a65383bec6446f442cbd.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/images/b29a6cdb442071578d89ea63bad727a5a7465dba6e94a65383bec6446f442cbd.jpg)

![b9a77ad404f1a237c2b7e95e4c294618669d056e9b77614a62bd37d3aa66d188.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/images/b9a77ad404f1a237c2b7e95e4c294618669d056e9b77614a62bd37d3aa66d188.jpg)

![c014de7c3f888313e53681447966c161d8464540b087032bb55cc9f098177acc.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/images/c014de7c3f888313e53681447966c161d8464540b087032bb55cc9f098177acc.jpg)

### Tables

![2b878445ce1c086a35145e05264bbc06f75d4e1c14438f0775757827a86912ea.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/tables/2b878445ce1c086a35145e05264bbc06f75d4e1c14438f0775757827a86912ea.jpg)

![4f18335b613314fb3ae02a51c366f3945639e7df02ff1f33ddeca48ef0122b96.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/tables/4f18335b613314fb3ae02a51c366f3945639e7df02ff1f33ddeca48ef0122b96.jpg)

![6aca0c99111ddd4a6f15c73fc596bea6740229146c4852df46bd40d35762c63d.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/tables/6aca0c99111ddd4a6f15c73fc596bea6740229146c4852df46bd40d35762c63d.jpg)

![8ad0e7b3ab96d574e8d336144e97ee4f5c054e382033b5eb067b5958ac9aa1fd.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/tables/8ad0e7b3ab96d574e8d336144e97ee4f5c054e382033b5eb067b5958ac9aa1fd.jpg)

![8d80821ab9ec52d0baabfef60913e07b77d20a46e86e38a7beea44981bc14d42.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/tables/8d80821ab9ec52d0baabfef60913e07b77d20a46e86e38a7beea44981bc14d42.jpg)

![a294114170097d91f3d8636f741f3b6de59e9a15a8410563aeb98d6b2414e655.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/tables/a294114170097d91f3d8636f741f3b6de59e9a15a8410563aeb98d6b2414e655.jpg)

![aefdd247c9fda45546e6bdd67235c5ad6273b9e1378918a36431f312eddcaa74.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/tables/aefdd247c9fda45546e6bdd67235c5ad6273b9e1378918a36431f312eddcaa74.jpg)

![bc998b74cfeb25dfe1b4cb6139fdf83b03ba872c0008d466940a45955e286269.jpg](../nips_results/3879_Towards%20Multiscale%20Graph-based%20Protein%20Learning%20with%20Geometric%20Secondary%20Structural%20Motifs/tables/bc998b74cfeb25dfe1b4cb6139fdf83b03ba872c0008d466940a45955e286269.jpg)

## FracFace: Breaking The Visual Clues—Fractal-Based Privacy-Preserving Face Recognition


### Images

![1a803676b1257a5349ab27403adb097d18251663a4c7ddfb373659e699182864.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/images/1a803676b1257a5349ab27403adb097d18251663a4c7ddfb373659e699182864.jpg)

![4dba8986fa7f34dd75de994e44dc8807808d2b0b0d1e38b329286a57aa07ca95.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/images/4dba8986fa7f34dd75de994e44dc8807808d2b0b0d1e38b329286a57aa07ca95.jpg)

![8f6843efd27ff08ed19c1d3f96a8b9be277806270bfdcc27610668d10b15d296.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/images/8f6843efd27ff08ed19c1d3f96a8b9be277806270bfdcc27610668d10b15d296.jpg)

![901effe562f5a8669e42666966759ca9498f5034aa1772a8c0f5cbf10fcb8d59.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/images/901effe562f5a8669e42666966759ca9498f5034aa1772a8c0f5cbf10fcb8d59.jpg)

![969f460fada70f1f156a0c442edb9905c3bc4b096fede55fa16e6fd3851d8f57.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/images/969f460fada70f1f156a0c442edb9905c3bc4b096fede55fa16e6fd3851d8f57.jpg)

![9faed1cf3db53627ef9d0d3ccd71be4744248513ba278ea882e86683bc141ace.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/images/9faed1cf3db53627ef9d0d3ccd71be4744248513ba278ea882e86683bc141ace.jpg)

![bafd0cc30edfd2330b17f90a92747810afc38b69b39151a2c85acad2f6cdc697.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/images/bafd0cc30edfd2330b17f90a92747810afc38b69b39151a2c85acad2f6cdc697.jpg)

![dbdb970fad2fe1e92ce6b9b5b5e76d9ce0f2528e28c628c6bbda3d7c409407d8.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/images/dbdb970fad2fe1e92ce6b9b5b5e76d9ce0f2528e28c628c6bbda3d7c409407d8.jpg)

![deaede5bf19b20a27886e770f67d50507fb5b861f9ee02d9ae7df800f2d5002c.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/images/deaede5bf19b20a27886e770f67d50507fb5b861f9ee02d9ae7df800f2d5002c.jpg)

![eab059e8d7447644fcc206394b0ba5f465cf4c0105663ac9daadfa13c0de7615.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/images/eab059e8d7447644fcc206394b0ba5f465cf4c0105663ac9daadfa13c0de7615.jpg)

### Tables

![088ba71810b890bfcaf7ac500726588558c8adc4b0b60beca83ad825718df0cd.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/tables/088ba71810b890bfcaf7ac500726588558c8adc4b0b60beca83ad825718df0cd.jpg)

![2cfc5a6eb6259b1d358272c631d309cf89c0e9464f6d823616391a78bc940d83.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/tables/2cfc5a6eb6259b1d358272c631d309cf89c0e9464f6d823616391a78bc940d83.jpg)

![b6e3dffb79a423184eb862e90f63a0df3a445d83188a119b81267a502db5f461.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/tables/b6e3dffb79a423184eb862e90f63a0df3a445d83188a119b81267a502db5f461.jpg)

![e048a56922f22dce5af66a70c465ffa8290da0b465567f5e2e245211896808dc.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/tables/e048a56922f22dce5af66a70c465ffa8290da0b465567f5e2e245211896808dc.jpg)

![f9dc5c0ac11c65e72a47b3b933dc46d7c6af08bdf1331904cb87d7c958d8fdf9.jpg](../nips_results/3880_FracFace_%20Breaking%20The%20Visual%20Clues%E2%80%94Fractal-Based%20Privacy-Preserving%20Face%20Recognition/tables/f9dc5c0ac11c65e72a47b3b933dc46d7c6af08bdf1331904cb87d7c958d8fdf9.jpg)

## GRAPE: Optimize Data Mixture for Group Robust Multi-target Adaptive Pretraining


### Images

![12afde4b5c71a7a952507ee8f3b7d853a3838bc256b98d6cd6944bafb8a9f426.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/12afde4b5c71a7a952507ee8f3b7d853a3838bc256b98d6cd6944bafb8a9f426.jpg)

![13427a77eed8d20b3c268da71055a92b3661d24b9c619e7662cb7815f00d0e7d.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/13427a77eed8d20b3c268da71055a92b3661d24b9c619e7662cb7815f00d0e7d.jpg)

![1c8fe0e8b1f82e2ce2fc2e485d3e124831462c81ed508d422252dceb4c4cb524.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/1c8fe0e8b1f82e2ce2fc2e485d3e124831462c81ed508d422252dceb4c4cb524.jpg)

![252ae71085c40a10600ee8955d03b730d17263efa315fe3d87aa0748d62d5515.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/252ae71085c40a10600ee8955d03b730d17263efa315fe3d87aa0748d62d5515.jpg)

![38e2591d5758958c99a4b14a3dbe43a7ec0eabc2ca38630bb511af1dd5652789.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/38e2591d5758958c99a4b14a3dbe43a7ec0eabc2ca38630bb511af1dd5652789.jpg)

![3b25c10646756a1737ceebf8852d739e190c8220bad0905c4dc42dd2cc50616c.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/3b25c10646756a1737ceebf8852d739e190c8220bad0905c4dc42dd2cc50616c.jpg)

![3dcd418c96fcb18d1e3f70015d4d21020198ee8dc3b90b3b6eaaf815ad38dfb7.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/3dcd418c96fcb18d1e3f70015d4d21020198ee8dc3b90b3b6eaaf815ad38dfb7.jpg)

![4976bc7d5f9e58cc1009f4f3e0bae30d65da0c4087c50d9602e702dd32216fcd.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/4976bc7d5f9e58cc1009f4f3e0bae30d65da0c4087c50d9602e702dd32216fcd.jpg)

![514b1a378e217a539cb23e916814ed67d86e9381dc9be08e5c86e5d6be35e6b7.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/514b1a378e217a539cb23e916814ed67d86e9381dc9be08e5c86e5d6be35e6b7.jpg)

![520abc17752d5d7567526c3319dff0d5fadcc4ad0f003ee614553cc6359f899d.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/520abc17752d5d7567526c3319dff0d5fadcc4ad0f003ee614553cc6359f899d.jpg)

![54441b8522f4747a73e1e5a23f336a839ce8958dfa54c11a57e87bf8cac16d1d.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/54441b8522f4747a73e1e5a23f336a839ce8958dfa54c11a57e87bf8cac16d1d.jpg)

![66bd7c7501310543e99b7ed447fca8a1df90d11c7c524e2bc92657f1975d2d59.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/66bd7c7501310543e99b7ed447fca8a1df90d11c7c524e2bc92657f1975d2d59.jpg)

![6f9fc22fff8706590f32e23f261cc08576908da1dfdeb0b61c0cd4e3fb4c46f5.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/6f9fc22fff8706590f32e23f261cc08576908da1dfdeb0b61c0cd4e3fb4c46f5.jpg)

![8013efa49d55781c264d1f5843086460363ea23f8830c21dbe26dd4c60997d64.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/8013efa49d55781c264d1f5843086460363ea23f8830c21dbe26dd4c60997d64.jpg)

![83dd0bd34195e2c3db8fdbfcb0b3a30e0f4aad58a9ba2c5ed7a41f6f320a24ab.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/83dd0bd34195e2c3db8fdbfcb0b3a30e0f4aad58a9ba2c5ed7a41f6f320a24ab.jpg)

![8d8bc6af51e77b9d2d32f4c57deaea7abfc81fc8080bcdda0492e063f854a687.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/8d8bc6af51e77b9d2d32f4c57deaea7abfc81fc8080bcdda0492e063f854a687.jpg)

![8f770bf391eb5d6fb9486a3255606081bc753a30648585e4cb1f16ce8a530b63.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/8f770bf391eb5d6fb9486a3255606081bc753a30648585e4cb1f16ce8a530b63.jpg)

![8fcec91c024793a7ca696394681dfc89e7d0414a1ff803d5c03c6cd71298f179.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/8fcec91c024793a7ca696394681dfc89e7d0414a1ff803d5c03c6cd71298f179.jpg)

![91190a2fb4763a898573954be2aca5594f11306ddadbda4b115a0fd8fc1adb32.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/91190a2fb4763a898573954be2aca5594f11306ddadbda4b115a0fd8fc1adb32.jpg)

![9266bb5d502c29c0dc8265ff4c5577f645137243f92602b10d2b816b56915734.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/9266bb5d502c29c0dc8265ff4c5577f645137243f92602b10d2b816b56915734.jpg)

![a07f49157078c1d332a8883f3f09fa7c63d8c7b08b146de6f282126e64e3ff74.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/a07f49157078c1d332a8883f3f09fa7c63d8c7b08b146de6f282126e64e3ff74.jpg)

![b09ee7560fc733a0b2e9b2d9968bc290a3b07044d13973ec38ef1e0eaaad3c50.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/b09ee7560fc733a0b2e9b2d9968bc290a3b07044d13973ec38ef1e0eaaad3c50.jpg)

![b9eb7c8eb97ef224bc7f2e8ce4cafbac886a7d4e523d57824556a219eee05760.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/b9eb7c8eb97ef224bc7f2e8ce4cafbac886a7d4e523d57824556a219eee05760.jpg)

![c0f457b8b28a204b17e307498c25ed93f7599d7f0e44077303f99948d4b47652.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/c0f457b8b28a204b17e307498c25ed93f7599d7f0e44077303f99948d4b47652.jpg)

![c750a399fa524af19bd1c48801d9a7c0d74ac1a502a3acf57081fede94df8a30.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/c750a399fa524af19bd1c48801d9a7c0d74ac1a502a3acf57081fede94df8a30.jpg)

![ce42c74da5e20c1865ee0357255fd866cfaae0a5d5d6d27a1c3008770f235cdb.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/ce42c74da5e20c1865ee0357255fd866cfaae0a5d5d6d27a1c3008770f235cdb.jpg)

![d996d18581856bfc55ae452a68eab6cf34663b7effd02d98ed8d08ebcd4e83e2.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/d996d18581856bfc55ae452a68eab6cf34663b7effd02d98ed8d08ebcd4e83e2.jpg)

![def27b9f726152966394cea6164aca46dc74d8fbfff42f0f7ad3939d54bbfa8a.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/def27b9f726152966394cea6164aca46dc74d8fbfff42f0f7ad3939d54bbfa8a.jpg)

![e8451b4de5c89c6c4e6f5a7e7031ed45aa4a548803c65e724e942cfe8ccb67c8.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/e8451b4de5c89c6c4e6f5a7e7031ed45aa4a548803c65e724e942cfe8ccb67c8.jpg)

![eb61ae31d6aff8af7358686ac0c54a6416ab5bc8eb217f76b5313f5e2a0519ed.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/eb61ae31d6aff8af7358686ac0c54a6416ab5bc8eb217f76b5313f5e2a0519ed.jpg)

![f0996114c0132ba1170958b24cc3fddff543c71efc51b09d641ce59495a887e6.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/f0996114c0132ba1170958b24cc3fddff543c71efc51b09d641ce59495a887e6.jpg)

![f3704709e4c916ab08e61c62f29cc45ea15011d3410159c6aa530673b65e4311.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/images/f3704709e4c916ab08e61c62f29cc45ea15011d3410159c6aa530673b65e4311.jpg)

### Tables

![68cd5c1b66e58d713ecaf624e4b0c96e41baa8d3406bf17f050ea07e250850f4.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/tables/68cd5c1b66e58d713ecaf624e4b0c96e41baa8d3406bf17f050ea07e250850f4.jpg)

![6d3172e94ec6abc3b3129f5e46d149507f8ad6fbc04fb51a8f9346b00cb58d7c.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/tables/6d3172e94ec6abc3b3129f5e46d149507f8ad6fbc04fb51a8f9346b00cb58d7c.jpg)

![79b876836fde8cc28a2451710ff45fdda8b7f0ea87d1329495d8a7c4da813980.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/tables/79b876836fde8cc28a2451710ff45fdda8b7f0ea87d1329495d8a7c4da813980.jpg)

![80180be25546f1a264f5ec15e0337aa779a3d18fe49cdf09e662ad328dd484dd.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/tables/80180be25546f1a264f5ec15e0337aa779a3d18fe49cdf09e662ad328dd484dd.jpg)

![c92ee25de30cc8599f134ff28ddaa2ad1c68c3ca31bb6942a2af04505dea11de.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/tables/c92ee25de30cc8599f134ff28ddaa2ad1c68c3ca31bb6942a2af04505dea11de.jpg)

![d3722e58079650760e92735f8a4ef1a5f29c7112e77ccd4bf954df2206b12293.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/tables/d3722e58079650760e92735f8a4ef1a5f29c7112e77ccd4bf954df2206b12293.jpg)

![d6402537018e3ff854856611ebce0a3bb87e359a3b1f3cb0380cc1d43f4ff3e9.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/tables/d6402537018e3ff854856611ebce0a3bb87e359a3b1f3cb0380cc1d43f4ff3e9.jpg)

![e1e2fabc6aa671928774754d2e03924c0b37c28d6f88d554699b4641f7fb53fd.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/tables/e1e2fabc6aa671928774754d2e03924c0b37c28d6f88d554699b4641f7fb53fd.jpg)

![e92b3bf9406cd89e0607367da3ee0b4e85e006c0763e1c40257c1d35ec5920c7.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/tables/e92b3bf9406cd89e0607367da3ee0b4e85e006c0763e1c40257c1d35ec5920c7.jpg)

![f2e06c8966964edb48d50cae3667ec56988f354b712f1e51342959ca8b4b17d3.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/tables/f2e06c8966964edb48d50cae3667ec56988f354b712f1e51342959ca8b4b17d3.jpg)

![f7b886ba2214107723d6ce1992856153ce0eae9786c514b2c82e90bbe79f5257.jpg](../nips_results/3881_GRAPE_%20Optimize%20Data%20Mixture%20for%20Group%20Robust%20Multi-target%20Adaptive%20Pretraining/tables/f7b886ba2214107723d6ce1992856153ce0eae9786c514b2c82e90bbe79f5257.jpg)

## RL Tango: Reinforcing Generator and Verifier Together for Language Reasoning


### Images

![0163bd37b0fc18def8677d162d3979eb1173137a6db4d4196a0b1f6f975db6a0.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/images/0163bd37b0fc18def8677d162d3979eb1173137a6db4d4196a0b1f6f975db6a0.jpg)

![8e20f8f429aab42600449c86e7bde35334e9f65c0cd04198bf6c9edc3639caa2.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/images/8e20f8f429aab42600449c86e7bde35334e9f65c0cd04198bf6c9edc3639caa2.jpg)

![9ffc616f849b6192002c8855a8988a3fe69f546f979db3f52669bfbef103bcf9.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/images/9ffc616f849b6192002c8855a8988a3fe69f546f979db3f52669bfbef103bcf9.jpg)

![b657bb9ae261e4b15d1cf5a7a4310c88f1bee5bd74909904e7342b560eb4ca45.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/images/b657bb9ae261e4b15d1cf5a7a4310c88f1bee5bd74909904e7342b560eb4ca45.jpg)

![c9deb0e8f6222afdfa74190436d51dae05301c325fb5298e25bcc7296cba5b3f.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/images/c9deb0e8f6222afdfa74190436d51dae05301c325fb5298e25bcc7296cba5b3f.jpg)

![cb84ab863aace2bc1ad4f8ba14e16fdf70b2f697132791bba37eb6ffc4d33e89.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/images/cb84ab863aace2bc1ad4f8ba14e16fdf70b2f697132791bba37eb6ffc4d33e89.jpg)

![d4679e34b5aaa0a9122d720e1e61221b1fd505c25e803ffaf7f86243846f768f.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/images/d4679e34b5aaa0a9122d720e1e61221b1fd505c25e803ffaf7f86243846f768f.jpg)

### Tables

![4fb5ea965d0ca7be6b1b6509109e071d7dfbe99357fce1e58d8ceb001fbd98c2.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/tables/4fb5ea965d0ca7be6b1b6509109e071d7dfbe99357fce1e58d8ceb001fbd98c2.jpg)

![715c82143c4657cafc376e5acf2e3bb0644319da5094b7d72677929e4dd56e8d.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/tables/715c82143c4657cafc376e5acf2e3bb0644319da5094b7d72677929e4dd56e8d.jpg)

![c1549d15218b99c6347f33a7281b65980220b07e93fd41e1216432a4140c980b.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/tables/c1549d15218b99c6347f33a7281b65980220b07e93fd41e1216432a4140c980b.jpg)

![c2bce7c300da41728615bfc989b1d72aaba4fb093c121ba1c33bcd451800520b.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/tables/c2bce7c300da41728615bfc989b1d72aaba4fb093c121ba1c33bcd451800520b.jpg)

![fac9db334569f9fad5be17542928da061599f00bd3d4ec7eb1f3f9fae67beb42.jpg](../nips_results/3882_RL%20Tango_%20Reinforcing%20Generator%20and%20Verifier%20Together%20for%20Language%20Reasoning/tables/fac9db334569f9fad5be17542928da061599f00bd3d4ec7eb1f3f9fae67beb42.jpg)

## Stab-SGD: Noise-Adaptivity in Smooth Optimization with Stability Ratios


### Images

![057372749d8e9afb3ed3677ea89dd2185f5aed6175e22e2661ac903e75355c61.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/057372749d8e9afb3ed3677ea89dd2185f5aed6175e22e2661ac903e75355c61.jpg)

![090936033513536b04c32827926eff3dc794219ff7b99dc76f3925401ae40070.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/090936033513536b04c32827926eff3dc794219ff7b99dc76f3925401ae40070.jpg)

![0b2b33dcb0803930dfe6d99a981e9ed9fd702809b5f89b3389b062e5ec72c135.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/0b2b33dcb0803930dfe6d99a981e9ed9fd702809b5f89b3389b062e5ec72c135.jpg)

![0f8c3eb20254fe4e7f1e436e5336446617b550c3b1c2b361a809c81ecedfe76f.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/0f8c3eb20254fe4e7f1e436e5336446617b550c3b1c2b361a809c81ecedfe76f.jpg)

![182a6c1bf717e52f089435b3fbfeb0815ef44f5e79d65875c05e7a56fc5bc3f0.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/182a6c1bf717e52f089435b3fbfeb0815ef44f5e79d65875c05e7a56fc5bc3f0.jpg)

![2343dc8e0f52078d40da34e56534be7322bf4bda386d933fa694359c79a7fd41.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/2343dc8e0f52078d40da34e56534be7322bf4bda386d933fa694359c79a7fd41.jpg)

![2466b0eba5a422d9e4b7838648e35fe566646c6065a04eca88170c81c8bc142f.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/2466b0eba5a422d9e4b7838648e35fe566646c6065a04eca88170c81c8bc142f.jpg)

![2a4e305e926671c8f73dd34a7ba6219b864e229aebb506e3840e3e603ee44dee.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/2a4e305e926671c8f73dd34a7ba6219b864e229aebb506e3840e3e603ee44dee.jpg)

![2ec6fa3b5ee5986160ed93916db8371e5602bda6c7b06368e14e29990f38d4aa.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/2ec6fa3b5ee5986160ed93916db8371e5602bda6c7b06368e14e29990f38d4aa.jpg)

![36110637a9f42a2e97fe42b51b16fbc6256834731438f0b747a1f30b97b8f127.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/36110637a9f42a2e97fe42b51b16fbc6256834731438f0b747a1f30b97b8f127.jpg)

![438c19430ac2a98c9bca25920ac06b15bdc955485f0e73dcecbbd61ab04fee08.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/438c19430ac2a98c9bca25920ac06b15bdc955485f0e73dcecbbd61ab04fee08.jpg)

![4497e711f0bf857dd2005252ca5780eac79df24846e77973114cec2e3a313a2d.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/4497e711f0bf857dd2005252ca5780eac79df24846e77973114cec2e3a313a2d.jpg)

![4811f1fa2e459740c3d6a8a80dd99dff788bab7b81fba24cfd5070898b47795b.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/4811f1fa2e459740c3d6a8a80dd99dff788bab7b81fba24cfd5070898b47795b.jpg)

![51d5cb8f22d7e7c773d82cca89e4e93ee5082327fd677140408fed65cfd44dd3.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/51d5cb8f22d7e7c773d82cca89e4e93ee5082327fd677140408fed65cfd44dd3.jpg)

![68b207ab09a9ac6185306a95049f608cc65ccf2d2a6c76fcd8abe14509a1586c.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/68b207ab09a9ac6185306a95049f608cc65ccf2d2a6c76fcd8abe14509a1586c.jpg)

![6caacc5803e14975c045d921905bf859381646356bc753f87f3300d0deebb66e.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/6caacc5803e14975c045d921905bf859381646356bc753f87f3300d0deebb66e.jpg)

![714d6804098243a740e82c85cc22d59eec6ce7beb17d04273c32bdc5a727aa84.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/714d6804098243a740e82c85cc22d59eec6ce7beb17d04273c32bdc5a727aa84.jpg)

![aca686076f0f5a05cbc084f0e7e550f631f3dc839867f0ba91717f7a55dd2f1a.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/aca686076f0f5a05cbc084f0e7e550f631f3dc839867f0ba91717f7a55dd2f1a.jpg)

![b305abbf918b5b205e3fb279ab5f856e06e68cace3637ffd3b4af9f760d4df06.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/b305abbf918b5b205e3fb279ab5f856e06e68cace3637ffd3b4af9f760d4df06.jpg)

![bfdac58e8c8ee309b7de91240355c8359d4e608bec6e6cee12ca658f6dfa2c97.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/bfdac58e8c8ee309b7de91240355c8359d4e608bec6e6cee12ca658f6dfa2c97.jpg)

![e51c4a122e55e1e2ac41ba05a832bf7cd526fc60e27392451ca0320562f0a4ea.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/e51c4a122e55e1e2ac41ba05a832bf7cd526fc60e27392451ca0320562f0a4ea.jpg)

![f0c0cec0e5a42f9ff62caf36578be05f6a2d80e412a25b88294e8c81984259f8.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/images/f0c0cec0e5a42f9ff62caf36578be05f6a2d80e412a25b88294e8c81984259f8.jpg)

### Tables

![e3bb8342c576e3dbf9f6c87462700571bb20fe125f91a6b68ffe55a5d80743f1.jpg](../nips_results/3883_Stab-SGD_%20Noise-Adaptivity%20in%20Smooth%20Optimization%20with%20Stability%20Ratios/tables/e3bb8342c576e3dbf9f6c87462700571bb20fe125f91a6b68ffe55a5d80743f1.jpg)

## What Really is a Member? Discrediting Membership Inference via Poisoning


### Images

![641684ac5a6de0f05336e846efec23d595d1941440127e69fbdf8b371a2be03d.jpg](../nips_results/3884_What%20Really%20is%20a%20Member_%20Discrediting%20Membership%20Inference%20via%20Poisoning/images/641684ac5a6de0f05336e846efec23d595d1941440127e69fbdf8b371a2be03d.jpg)

![8cc459cfb0f110e523df110fe471922b0e9ebc595b65318acca22c81fc7519ed.jpg](../nips_results/3884_What%20Really%20is%20a%20Member_%20Discrediting%20Membership%20Inference%20via%20Poisoning/images/8cc459cfb0f110e523df110fe471922b0e9ebc595b65318acca22c81fc7519ed.jpg)

![ecee026dd34ee2760eef19e626236d75fcfe5c3205cbcc9d14a3e59ecf3587fc.jpg](../nips_results/3884_What%20Really%20is%20a%20Member_%20Discrediting%20Membership%20Inference%20via%20Poisoning/images/ecee026dd34ee2760eef19e626236d75fcfe5c3205cbcc9d14a3e59ecf3587fc.jpg)

### Tables

![4153e9707e038bfbd9d451b92f26ac01ffbd02777e11303f3250de85456a4b62.jpg](../nips_results/3884_What%20Really%20is%20a%20Member_%20Discrediting%20Membership%20Inference%20via%20Poisoning/tables/4153e9707e038bfbd9d451b92f26ac01ffbd02777e11303f3250de85456a4b62.jpg)

![582fbbf21f14ba37813bf5f871bfd7ba513e4583a26452ed1844e796dd264f90.jpg](../nips_results/3884_What%20Really%20is%20a%20Member_%20Discrediting%20Membership%20Inference%20via%20Poisoning/tables/582fbbf21f14ba37813bf5f871bfd7ba513e4583a26452ed1844e796dd264f90.jpg)

![5b9412757eb5cf8da09ca087802653fc53ec2125867d3eb4d663756b0f6a50f9.jpg](../nips_results/3884_What%20Really%20is%20a%20Member_%20Discrediting%20Membership%20Inference%20via%20Poisoning/tables/5b9412757eb5cf8da09ca087802653fc53ec2125867d3eb4d663756b0f6a50f9.jpg)

![5dbb9279c545cb6a58c4927f18217d777b65579863d9604d8a775aa7aa7c5237.jpg](../nips_results/3884_What%20Really%20is%20a%20Member_%20Discrediting%20Membership%20Inference%20via%20Poisoning/tables/5dbb9279c545cb6a58c4927f18217d777b65579863d9604d8a775aa7aa7c5237.jpg)

![6734029d8033ceaf9c0f207231f56dedc28a475662bd9c83fd4961ded58b17e2.jpg](../nips_results/3884_What%20Really%20is%20a%20Member_%20Discrediting%20Membership%20Inference%20via%20Poisoning/tables/6734029d8033ceaf9c0f207231f56dedc28a475662bd9c83fd4961ded58b17e2.jpg)

![a92d70096551f1ca05d4c03436829b3d94f0af72d55a56ec8bb3c360e800696d.jpg](../nips_results/3884_What%20Really%20is%20a%20Member_%20Discrediting%20Membership%20Inference%20via%20Poisoning/tables/a92d70096551f1ca05d4c03436829b3d94f0af72d55a56ec8bb3c360e800696d.jpg)

![bdd3d19ebe93386b6f576e674ed0aa5871da2c8be3124beb83de4deb38a0bc29.jpg](../nips_results/3884_What%20Really%20is%20a%20Member_%20Discrediting%20Membership%20Inference%20via%20Poisoning/tables/bdd3d19ebe93386b6f576e674ed0aa5871da2c8be3124beb83de4deb38a0bc29.jpg)

![fe6393dfd59c3bcda855f895f42a177d33d7e06b49618b751afc08a72d9e0cd8.jpg](../nips_results/3884_What%20Really%20is%20a%20Member_%20Discrediting%20Membership%20Inference%20via%20Poisoning/tables/fe6393dfd59c3bcda855f895f42a177d33d7e06b49618b751afc08a72d9e0cd8.jpg)

## Brain-Informed Fine-Tuning for Improved Multilingual Understanding in Language Models


### Images

![38c35290446833bf22b94bf7f36efc20650126628f5717c1ab39fd1ab31b22a8.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/images/38c35290446833bf22b94bf7f36efc20650126628f5717c1ab39fd1ab31b22a8.jpg)

![3e6586ce881634d7fbacc0bfe0b58c09be84c3539f2d110a72f2d5e48b6d3930.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/images/3e6586ce881634d7fbacc0bfe0b58c09be84c3539f2d110a72f2d5e48b6d3930.jpg)

![bb30d2b154e1f21dc8aad4e96ea5ac5496f6ecdaae2a7285ab44b37950d64e8b.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/images/bb30d2b154e1f21dc8aad4e96ea5ac5496f6ecdaae2a7285ab44b37950d64e8b.jpg)

![c23efa2f2d896031b09c30ab72422d0415070ff63f997789c024b9f841036739.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/images/c23efa2f2d896031b09c30ab72422d0415070ff63f997789c024b9f841036739.jpg)

![d8a94865f2f8a6dceadfd43881a2586703e82cc481ca02654f8e72d549a16d62.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/images/d8a94865f2f8a6dceadfd43881a2586703e82cc481ca02654f8e72d549a16d62.jpg)

![ee83a0e54823717c2bfdedb05d7da65b61ed7db1d7b159066739e7162761820e.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/images/ee83a0e54823717c2bfdedb05d7da65b61ed7db1d7b159066739e7162761820e.jpg)

### Tables

![03c12f09578f64bd7cb24a3bedb2411bc1d2aea5b3a3766bc7a7269a35c9d31b.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/03c12f09578f64bd7cb24a3bedb2411bc1d2aea5b3a3766bc7a7269a35c9d31b.jpg)

![39e979eeb564947724bd4950060a3461edb55eb2f8732de9606f1c9ea530af59.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/39e979eeb564947724bd4950060a3461edb55eb2f8732de9606f1c9ea530af59.jpg)

![3f4337f27e18ad7fac1704f92dde12a57dc3ea82fca4bdf5b262fd05e3d8fb5b.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/3f4337f27e18ad7fac1704f92dde12a57dc3ea82fca4bdf5b262fd05e3d8fb5b.jpg)

![4caf53a05d63ceff8212a3265f1714c768349798656542e77f467279f33e881e.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/4caf53a05d63ceff8212a3265f1714c768349798656542e77f467279f33e881e.jpg)

![5b2399621df6e393d3051e8167123f0eebb49d3af746e1b0c9495b075c8b17c1.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/5b2399621df6e393d3051e8167123f0eebb49d3af746e1b0c9495b075c8b17c1.jpg)

![60839fffe0c4a1c613ea4226b6d2c817955b0592a53c2230c151b3f0b0ae9f77.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/60839fffe0c4a1c613ea4226b6d2c817955b0592a53c2230c151b3f0b0ae9f77.jpg)

![67ad4e2e9a1dd48c0381c2ba583e511d4f05195d2b9aa266629845eef4c9b98c.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/67ad4e2e9a1dd48c0381c2ba583e511d4f05195d2b9aa266629845eef4c9b98c.jpg)

![68e924c12fe948e828f7cddde9cf4968b13b3efdf48a232529ba27fdab506a1e.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/68e924c12fe948e828f7cddde9cf4968b13b3efdf48a232529ba27fdab506a1e.jpg)

![6946801a9c310712815b43cc2b0bf0f99574f87d7a6ac3ab2565523ed1704f39.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/6946801a9c310712815b43cc2b0bf0f99574f87d7a6ac3ab2565523ed1704f39.jpg)

![716b040c4702ac8f85fd4c400c024654a582e0e5e49a5ebc3dcf1a27270ce378.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/716b040c4702ac8f85fd4c400c024654a582e0e5e49a5ebc3dcf1a27270ce378.jpg)

![792f210f44e27733c6c62dbea9720db83c723c42581007af065e0c2da4dba8ce.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/792f210f44e27733c6c62dbea9720db83c723c42581007af065e0c2da4dba8ce.jpg)

![7946e395c910b65e56733c946dec9d73e612a9cc8d1ebf0231a4faaaf76fbd2c.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/7946e395c910b65e56733c946dec9d73e612a9cc8d1ebf0231a4faaaf76fbd2c.jpg)

![8d0d202113b4a07338aad788446f68ff71010a646fc730e30eb2c38116a9a6b9.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/8d0d202113b4a07338aad788446f68ff71010a646fc730e30eb2c38116a9a6b9.jpg)

![90aef69c2558af8140643d31b7c8c78703984ccfd81df46c9c0528a7ee9bda2d.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/90aef69c2558af8140643d31b7c8c78703984ccfd81df46c9c0528a7ee9bda2d.jpg)

![934a09c5369ee290f838b1b4c14dedd3b654f6c1feb92f91b679cffb42d9bf11.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/934a09c5369ee290f838b1b4c14dedd3b654f6c1feb92f91b679cffb42d9bf11.jpg)

![9758a326efaabe99fdb2a4a22bced0beb74d69195514343968a5ae9c5ef8f3f2.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/9758a326efaabe99fdb2a4a22bced0beb74d69195514343968a5ae9c5ef8f3f2.jpg)

![99264e6e38137cf865cf4977fdd7386876d46f8e5974f52b645e293825277fe2.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/99264e6e38137cf865cf4977fdd7386876d46f8e5974f52b645e293825277fe2.jpg)

![9ea69b34a45c21cb408fd064c63116d1e6f282af54b1e12796948c66e1c6ebde.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/9ea69b34a45c21cb408fd064c63116d1e6f282af54b1e12796948c66e1c6ebde.jpg)

![aa77e5c55d5a4229b4a3189873c8e8186c9ec1c9b4cd0fbdc0b419f2d2bd9174.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/aa77e5c55d5a4229b4a3189873c8e8186c9ec1c9b4cd0fbdc0b419f2d2bd9174.jpg)

![af5b8f16540564c0b04ca3645ebceb9dfa5df2455acaf9bf92e2edec2572ce52.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/af5b8f16540564c0b04ca3645ebceb9dfa5df2455acaf9bf92e2edec2572ce52.jpg)

![b933c3351dce450b88083ebe77c7bd748ac610e5632f526f4ed665ce2d0d30c7.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/b933c3351dce450b88083ebe77c7bd748ac610e5632f526f4ed665ce2d0d30c7.jpg)

![bf3bcaec2217be9b1966a501990b140a2ded47f81d7033141c1de03b9c0be01a.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/bf3bcaec2217be9b1966a501990b140a2ded47f81d7033141c1de03b9c0be01a.jpg)

![c8b7e29ec1afa0fc27a7be92ba6b7f28a0ab3394ec802804f428102995d3c81f.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/c8b7e29ec1afa0fc27a7be92ba6b7f28a0ab3394ec802804f428102995d3c81f.jpg)

![e1c9c17ba65b147892495dff8ef60a17d39540973bca89ef04fe1cf86103099e.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/e1c9c17ba65b147892495dff8ef60a17d39540973bca89ef04fe1cf86103099e.jpg)

![e47bf43d9fd5808f485836cbcdd6004fb2b8b37030cab689bd1815b1854d3ab8.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/e47bf43d9fd5808f485836cbcdd6004fb2b8b37030cab689bd1815b1854d3ab8.jpg)

![f17794b80491abbd130acd5168df3f09eb36fd6b590f987721ace7598c8fac83.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/f17794b80491abbd130acd5168df3f09eb36fd6b590f987721ace7598c8fac83.jpg)

![faeb2724be1d70d55d4f2b1e1c98eb3a6edbc84d815e01a9db3ca21016e8814e.jpg](../nips_results/3885_Brain-Informed%20Fine-Tuning%20for%20Improved%20Multilingual%20Understanding%20in%20Language%20Models/tables/faeb2724be1d70d55d4f2b1e1c98eb3a6edbc84d815e01a9db3ca21016e8814e.jpg)

## MoleBridge: Synthetic Space Projecting with Discrete Markov Bridges


### Images

![1aeb73e6a3a8ef0f0829abab0588224a9b7d80c8259f67c8ee8965494b1dbf0b.jpg](../nips_results/3886_MoleBridge_%20Synthetic%20Space%20Projecting%20with%20Discrete%20Markov%20Bridges/images/1aeb73e6a3a8ef0f0829abab0588224a9b7d80c8259f67c8ee8965494b1dbf0b.jpg)

![60acb411948a2a019ec64d04e2250d96c6136b4c0cedf2e1a64bb4f1c5be7a00.jpg](../nips_results/3886_MoleBridge_%20Synthetic%20Space%20Projecting%20with%20Discrete%20Markov%20Bridges/images/60acb411948a2a019ec64d04e2250d96c6136b4c0cedf2e1a64bb4f1c5be7a00.jpg)

![b96174557300c678138987bf26b07e28b991b3e0e791185d318fbe7967322cb6.jpg](../nips_results/3886_MoleBridge_%20Synthetic%20Space%20Projecting%20with%20Discrete%20Markov%20Bridges/images/b96174557300c678138987bf26b07e28b991b3e0e791185d318fbe7967322cb6.jpg)

![babe4c9089f40558d06e6f6e8860f44cba621bccd11606eef79589f75aaf93cb.jpg](../nips_results/3886_MoleBridge_%20Synthetic%20Space%20Projecting%20with%20Discrete%20Markov%20Bridges/images/babe4c9089f40558d06e6f6e8860f44cba621bccd11606eef79589f75aaf93cb.jpg)

### Tables

![45472ecf8d6505a92a12cbe73507f9cd9c8fd1a17f6ba5dc6957b2bacbafdf98.jpg](../nips_results/3886_MoleBridge_%20Synthetic%20Space%20Projecting%20with%20Discrete%20Markov%20Bridges/tables/45472ecf8d6505a92a12cbe73507f9cd9c8fd1a17f6ba5dc6957b2bacbafdf98.jpg)

![6662d4c9960e7e220702fc1f7f0ccb723c856e5a60158499256a264f20897761.jpg](../nips_results/3886_MoleBridge_%20Synthetic%20Space%20Projecting%20with%20Discrete%20Markov%20Bridges/tables/6662d4c9960e7e220702fc1f7f0ccb723c856e5a60158499256a264f20897761.jpg)

![66e2920969e82949fc31f947b17fd583ef40fa349430ff19a772c0b46de54518.jpg](../nips_results/3886_MoleBridge_%20Synthetic%20Space%20Projecting%20with%20Discrete%20Markov%20Bridges/tables/66e2920969e82949fc31f947b17fd583ef40fa349430ff19a772c0b46de54518.jpg)

![a4675d74cf90256bf7369ed50e98c81570d6f5a300693befcc2c1073252c56bc.jpg](../nips_results/3886_MoleBridge_%20Synthetic%20Space%20Projecting%20with%20Discrete%20Markov%20Bridges/tables/a4675d74cf90256bf7369ed50e98c81570d6f5a300693befcc2c1073252c56bc.jpg)

![ed431c484dbca6da935fcc70fe8d94f80dd7ef36dd59a522ecf35e4c59322d52.jpg](../nips_results/3886_MoleBridge_%20Synthetic%20Space%20Projecting%20with%20Discrete%20Markov%20Bridges/tables/ed431c484dbca6da935fcc70fe8d94f80dd7ef36dd59a522ecf35e4c59322d52.jpg)

## Generative Modeling of Full-Atom Protein Conformations using Latent Diffusion on Graph Embeddings


### Images

![225ad2564ba828b2cc2718bd26a5851a81f06cadfe59f687331a237952c3973a.jpg](../nips_results/3887_Generative%20Modeling%20of%20Full-Atom%20Protein%20Conformations%20using%20Latent%20Diffusion%20on%20Graph%20Embeddings/images/225ad2564ba828b2cc2718bd26a5851a81f06cadfe59f687331a237952c3973a.jpg)

![2e3719536d9758aa38e2dbb6033c6bde50e8ee23e025cf627152db489cebc0f1.jpg](../nips_results/3887_Generative%20Modeling%20of%20Full-Atom%20Protein%20Conformations%20using%20Latent%20Diffusion%20on%20Graph%20Embeddings/images/2e3719536d9758aa38e2dbb6033c6bde50e8ee23e025cf627152db489cebc0f1.jpg)

![6f10eb0bf80f55368ee8796b4a9c8a4f32a2212275e5528a246aa6a2a6c7c51f.jpg](../nips_results/3887_Generative%20Modeling%20of%20Full-Atom%20Protein%20Conformations%20using%20Latent%20Diffusion%20on%20Graph%20Embeddings/images/6f10eb0bf80f55368ee8796b4a9c8a4f32a2212275e5528a246aa6a2a6c7c51f.jpg)

![86dfaba527f4cbd8acfb3c8da5542c3c83d96f48d3afeb964be17276f1d99ba1.jpg](../nips_results/3887_Generative%20Modeling%20of%20Full-Atom%20Protein%20Conformations%20using%20Latent%20Diffusion%20on%20Graph%20Embeddings/images/86dfaba527f4cbd8acfb3c8da5542c3c83d96f48d3afeb964be17276f1d99ba1.jpg)

![b91b9f3bb97375b9571bff2be930673e9c94d8c34fb8672cc34dd7169a7c66ae.jpg](../nips_results/3887_Generative%20Modeling%20of%20Full-Atom%20Protein%20Conformations%20using%20Latent%20Diffusion%20on%20Graph%20Embeddings/images/b91b9f3bb97375b9571bff2be930673e9c94d8c34fb8672cc34dd7169a7c66ae.jpg)

![c570e24c5193fd03d8c49dee48d1637d892fd4c30330aa8152e6d12b792d4e1f.jpg](../nips_results/3887_Generative%20Modeling%20of%20Full-Atom%20Protein%20Conformations%20using%20Latent%20Diffusion%20on%20Graph%20Embeddings/images/c570e24c5193fd03d8c49dee48d1637d892fd4c30330aa8152e6d12b792d4e1f.jpg)

### Tables

![89a1a58971854c2c8034ff0b3dc94d683f9f14c83795e9540c078b1906bdbb09.jpg](../nips_results/3887_Generative%20Modeling%20of%20Full-Atom%20Protein%20Conformations%20using%20Latent%20Diffusion%20on%20Graph%20Embeddings/tables/89a1a58971854c2c8034ff0b3dc94d683f9f14c83795e9540c078b1906bdbb09.jpg)

![8e5da70d396e34eacf38b797155dacaf7731c73923949cc34366543159850e6e.jpg](../nips_results/3887_Generative%20Modeling%20of%20Full-Atom%20Protein%20Conformations%20using%20Latent%20Diffusion%20on%20Graph%20Embeddings/tables/8e5da70d396e34eacf38b797155dacaf7731c73923949cc34366543159850e6e.jpg)

![9f01de09ccd102a4b35d9a869fd59aff28b8523aa00e8534178f067a630a9a19.jpg](../nips_results/3887_Generative%20Modeling%20of%20Full-Atom%20Protein%20Conformations%20using%20Latent%20Diffusion%20on%20Graph%20Embeddings/tables/9f01de09ccd102a4b35d9a869fd59aff28b8523aa00e8534178f067a630a9a19.jpg)

![e18e84a52bacb4547194563fc38c58e4c77e2efd16c3c2d6375b69d87e0ff86b.jpg](../nips_results/3887_Generative%20Modeling%20of%20Full-Atom%20Protein%20Conformations%20using%20Latent%20Diffusion%20on%20Graph%20Embeddings/tables/e18e84a52bacb4547194563fc38c58e4c77e2efd16c3c2d6375b69d87e0ff86b.jpg)

## Feature Unlearning: Theoretical Foundations and Practical Applications with Shuffling


### Images

![1cbca8454bf0ee77d0efab8f3c1a51387ce14001ba83dadf55b93e9bb6e4fb42.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/1cbca8454bf0ee77d0efab8f3c1a51387ce14001ba83dadf55b93e9bb6e4fb42.jpg)

![2521d694048a97955a0e2f5d5e0528aff5502d40dbc7c65b4ae7aed342752c15.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/2521d694048a97955a0e2f5d5e0528aff5502d40dbc7c65b4ae7aed342752c15.jpg)

![263abbeb4dd9a2c4c35b1bebc89148e32f2e0cedcd04d7ea153b959442b5caa0.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/263abbeb4dd9a2c4c35b1bebc89148e32f2e0cedcd04d7ea153b959442b5caa0.jpg)

![3147abc9b9520fd32e4900ca6a145b70a412f580abb6c710a599de668f9bab23.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/3147abc9b9520fd32e4900ca6a145b70a412f580abb6c710a599de668f9bab23.jpg)

![336f3fc1c87bf58d57c0fdf02e483b3fe2ae67afd8f467a6e4c1e1515599278b.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/336f3fc1c87bf58d57c0fdf02e483b3fe2ae67afd8f467a6e4c1e1515599278b.jpg)

![490e3b0919eb1090f431fb2c126d1fcf0568685d8970044bdf64c31d149a68ef.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/490e3b0919eb1090f431fb2c126d1fcf0568685d8970044bdf64c31d149a68ef.jpg)

![5493195d8ccfb24090b60ebb0904e80afba490722530b9266c4623bca1066d8f.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/5493195d8ccfb24090b60ebb0904e80afba490722530b9266c4623bca1066d8f.jpg)

![5532952ce771c138e7109d66950b4c7b5a430204e88204d8afd87c7f55400d10.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/5532952ce771c138e7109d66950b4c7b5a430204e88204d8afd87c7f55400d10.jpg)

![5962b47e430b29b3312df0caf642a30700345d99be3800b76aa8d2555406c209.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/5962b47e430b29b3312df0caf642a30700345d99be3800b76aa8d2555406c209.jpg)

![6140df3220df4e75d9234af61caee827f1b45b759274e2252b6b974442fdf9c6.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/6140df3220df4e75d9234af61caee827f1b45b759274e2252b6b974442fdf9c6.jpg)

![67e1c38e81f819eb5706d5f6813e88c98e87309c29e35bd8056772f17300d6ed.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/67e1c38e81f819eb5706d5f6813e88c98e87309c29e35bd8056772f17300d6ed.jpg)

![785c0f8b5be2b7bf4e6818f2557f84a9d1df5c038a060832df4b6c853fa7f72f.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/785c0f8b5be2b7bf4e6818f2557f84a9d1df5c038a060832df4b6c853fa7f72f.jpg)

![7a94b4d53ed80fa767162c64e1b7e169b4d72a27e43a35dc1fb32c0c62627c7f.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/7a94b4d53ed80fa767162c64e1b7e169b4d72a27e43a35dc1fb32c0c62627c7f.jpg)

![892a0797f8e9be208c8be6b6f42314513e04a8753d9be99a13b6e75b02100f7c.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/892a0797f8e9be208c8be6b6f42314513e04a8753d9be99a13b6e75b02100f7c.jpg)

![8dcc3f3d4231fb3cf62a455f83f5037011444b6bdba05b0158348c4f2523d01f.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/8dcc3f3d4231fb3cf62a455f83f5037011444b6bdba05b0158348c4f2523d01f.jpg)

![9baf92339d86d10f98ca072210bc9e22c52723e1f96a2fb0b825d1d4e067bf51.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/9baf92339d86d10f98ca072210bc9e22c52723e1f96a2fb0b825d1d4e067bf51.jpg)

![a9551ce71e651230d0e53788e43c42ebaeb173d03f1f0c57fd45cebb3aabf726.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/a9551ce71e651230d0e53788e43c42ebaeb173d03f1f0c57fd45cebb3aabf726.jpg)

![aec8f84af7c6c9508c32fa1b256a91c778b8606341dd4b10c25fbfebc7061dd4.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/aec8f84af7c6c9508c32fa1b256a91c778b8606341dd4b10c25fbfebc7061dd4.jpg)

![afb6edfa4458363b972e5b011d75b6b960ab0616cc61fd5fbddc8e93ec49f292.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/afb6edfa4458363b972e5b011d75b6b960ab0616cc61fd5fbddc8e93ec49f292.jpg)

![b17b4f656a82306b3c0ceb62446305b2de861705be61959d74754f7827647203.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/b17b4f656a82306b3c0ceb62446305b2de861705be61959d74754f7827647203.jpg)

![b2b45a39eb363f0aef9a787f1c1f6951cffd4edbbc9caaa3bf8b618e7a479fc1.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/b2b45a39eb363f0aef9a787f1c1f6951cffd4edbbc9caaa3bf8b618e7a479fc1.jpg)

![b73e14a242a3bb4d426ba1924b36c3e7747f78addb0ccb56cd3837b84261dc8e.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/b73e14a242a3bb4d426ba1924b36c3e7747f78addb0ccb56cd3837b84261dc8e.jpg)

![b96003769e4aba3eabfea330072e1d9cfbe2bdcba9986d8d112cef48bb5c9c10.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/b96003769e4aba3eabfea330072e1d9cfbe2bdcba9986d8d112cef48bb5c9c10.jpg)

![c69dc92e6d7a6673b410d0a7bec5217032e66ef17dfe6334594406a948fdd065.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/c69dc92e6d7a6673b410d0a7bec5217032e66ef17dfe6334594406a948fdd065.jpg)

![c6da5082493c4ddf2e31dc75925e60ab64ebc76f36461fd2b5ed3a708b20b977.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/c6da5082493c4ddf2e31dc75925e60ab64ebc76f36461fd2b5ed3a708b20b977.jpg)

![ca50be53de452a1ce130aa19d618013ae11197d7983ce0d88c1c1eb4731d3646.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/ca50be53de452a1ce130aa19d618013ae11197d7983ce0d88c1c1eb4731d3646.jpg)

![d2bc0a3507bac91e59a485af77bcd1c83e9a149053cd6d1322eba5506d7168c3.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/d2bc0a3507bac91e59a485af77bcd1c83e9a149053cd6d1322eba5506d7168c3.jpg)

![e67d1bd7ccb416814cf6b54806e780277212aae73946350df72629217bfe7c6c.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/e67d1bd7ccb416814cf6b54806e780277212aae73946350df72629217bfe7c6c.jpg)

![e9fae1eda36ab54491bde040c4a69a2d53efb38f89cfcd462c930195b60ff53e.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/e9fae1eda36ab54491bde040c4a69a2d53efb38f89cfcd462c930195b60ff53e.jpg)

![f7431fceb61d77eb02c4cdc5d8263f2d75420f5f2cda47947d5948e487299e69.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/images/f7431fceb61d77eb02c4cdc5d8263f2d75420f5f2cda47947d5948e487299e69.jpg)

### Tables

![00649cabf7126a71c0bfc84bae4ef386ed530fc15fd02e81eab52a928e1d76c2.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/00649cabf7126a71c0bfc84bae4ef386ed530fc15fd02e81eab52a928e1d76c2.jpg)

![31e41b8bf0e200d44028ce737473150ce33bdc95a269e010068735cb98d10862.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/31e41b8bf0e200d44028ce737473150ce33bdc95a269e010068735cb98d10862.jpg)

![34e7d8df14f41063c5c53c7d79b420c28648df6162552fb907c839cd9d25f37a.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/34e7d8df14f41063c5c53c7d79b420c28648df6162552fb907c839cd9d25f37a.jpg)

![381f64d3890c48914e20462ca0c10ed374da3810775d3292f4cb0e749f52b1af.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/381f64d3890c48914e20462ca0c10ed374da3810775d3292f4cb0e749f52b1af.jpg)

![4347c344167f47ab20688db478bc2dbea2d26259c309ec33e6411a44fc232365.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/4347c344167f47ab20688db478bc2dbea2d26259c309ec33e6411a44fc232365.jpg)

![4a117a7ac682e3cdb74d0bca68480bde10c27cce3fbc0fbfd1b5d78fb0935e41.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/4a117a7ac682e3cdb74d0bca68480bde10c27cce3fbc0fbfd1b5d78fb0935e41.jpg)

![4ee3b63f935913722b05cb2895e8b9bd335655c5a84fb35dffe38e2947a10ab8.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/4ee3b63f935913722b05cb2895e8b9bd335655c5a84fb35dffe38e2947a10ab8.jpg)

![51656b6fb2ee73dc1243c7dd5c5ea9ea20451f4b81a2612312ad3ef054149009.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/51656b6fb2ee73dc1243c7dd5c5ea9ea20451f4b81a2612312ad3ef054149009.jpg)

![77acc6d5bc719d5052d01f2c99ee75ddda54fca6ed5d1a2c2bd77bc73f4a8ce4.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/77acc6d5bc719d5052d01f2c99ee75ddda54fca6ed5d1a2c2bd77bc73f4a8ce4.jpg)

![a728083ac7175de7842402fd74b8d426bcacd89c0cbbbd29a370605c445b888e.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/a728083ac7175de7842402fd74b8d426bcacd89c0cbbbd29a370605c445b888e.jpg)

![cff96a723b577f3dba43ceb511e1a7b56992432f6ee96157b58c6cd6d838d410.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/cff96a723b577f3dba43ceb511e1a7b56992432f6ee96157b58c6cd6d838d410.jpg)

![d4d14c0bd5e6acc28062ae03d2c167dee37392182c468ac572bab44a307ddb29.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/d4d14c0bd5e6acc28062ae03d2c167dee37392182c468ac572bab44a307ddb29.jpg)

![f65ce93c0c4489ce280a0b024848dfe812b82461520f1310f67125f46b73c0e5.jpg](../nips_results/3888_Feature%20Unlearning_%20Theoretical%20Foundations%20and%20Practical%20Applications%20with%20Shuffling/tables/f65ce93c0c4489ce280a0b024848dfe812b82461520f1310f67125f46b73c0e5.jpg)

## Unified all-atom molecule generation with neural fields


### Images

![08cd6d97eb80eeee64bdb7abc1fc2e6927bea41a2bb81a917c9236890772eb63.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/08cd6d97eb80eeee64bdb7abc1fc2e6927bea41a2bb81a917c9236890772eb63.jpg)

![1a2f736f87a8228cdf0a1b7418d395b7bf9bdbd1747bc12a429b52725e70eba9.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/1a2f736f87a8228cdf0a1b7418d395b7bf9bdbd1747bc12a429b52725e70eba9.jpg)

![4c89b65d69bbbbe9089d9af679733d7c2b2fc08f0633b15f29a44edfb15dc87c.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/4c89b65d69bbbbe9089d9af679733d7c2b2fc08f0633b15f29a44edfb15dc87c.jpg)

![6248c327bbf0b1a40b7bd3321ccc112d865b79ebef94bd6d1064cc8658113d74.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/6248c327bbf0b1a40b7bd3321ccc112d865b79ebef94bd6d1064cc8658113d74.jpg)

![9698d4a79d57911f469115cb1eaece347e9d39b6984ae3b9a1b5dab12f4195fd.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/9698d4a79d57911f469115cb1eaece347e9d39b6984ae3b9a1b5dab12f4195fd.jpg)

![a7d9767c3bbb40e13c3b2e44a918fcc637c4882a13b29d4e1bf68778e1443cf0.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/a7d9767c3bbb40e13c3b2e44a918fcc637c4882a13b29d4e1bf68778e1443cf0.jpg)

![abf56f62e56cea0ee7960316148ee2542e26840fc99933ceb2d20f79b0603469.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/abf56f62e56cea0ee7960316148ee2542e26840fc99933ceb2d20f79b0603469.jpg)

![b1b22b05a430edaa48d49a3db84181863664a8036b6b4778e542b288ee417051.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/b1b22b05a430edaa48d49a3db84181863664a8036b6b4778e542b288ee417051.jpg)

![db9f173ea3fec7c032abe4f9f42392ab663348fe67bdd39eacaaf1b1700b9dab.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/db9f173ea3fec7c032abe4f9f42392ab663348fe67bdd39eacaaf1b1700b9dab.jpg)

![dbe17d386e9fd162bac6539b3c767e49ac5cb7769b56697311eb1732ff0ccd56.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/dbe17d386e9fd162bac6539b3c767e49ac5cb7769b56697311eb1732ff0ccd56.jpg)

![dd46568077b0edb67575120c3a423cc2de92bfca3a6544d407ec5e9321b87325.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/dd46568077b0edb67575120c3a423cc2de92bfca3a6544d407ec5e9321b87325.jpg)

![e06151459f6ac21b9023ed712bb32ec6ca398ecbaf0084c397aab7219cbfeaa6.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/e06151459f6ac21b9023ed712bb32ec6ca398ecbaf0084c397aab7219cbfeaa6.jpg)

![f4cd732fe7c0dd9ee6747b726c1e800d744087f419fd35501db9655071235855.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/images/f4cd732fe7c0dd9ee6747b726c1e800d744087f419fd35501db9655071235855.jpg)

### Tables

![056b1412842d86ce43eb57a0c322c2e02f20ebdfe8aadf3d09bce868a003d6cb.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/tables/056b1412842d86ce43eb57a0c322c2e02f20ebdfe8aadf3d09bce868a003d6cb.jpg)

![240b3f53941ef8268b4e95a221032f856ef66e8f8ee0215a8a9d0fb972dfa93b.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/tables/240b3f53941ef8268b4e95a221032f856ef66e8f8ee0215a8a9d0fb972dfa93b.jpg)

![7c0fa83ab0ab8714adabf10d0ee07213794d4e468b511a95578922fee2aae2ed.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/tables/7c0fa83ab0ab8714adabf10d0ee07213794d4e468b511a95578922fee2aae2ed.jpg)

![805bd2845408e2873295cb0f335809f8ab7168ea6bc8a6cba854f2af62699595.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/tables/805bd2845408e2873295cb0f335809f8ab7168ea6bc8a6cba854f2af62699595.jpg)

![83e4d186fc474b0ed739d0595615d2d92068654d466ac4f2e38adb5cded99292.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/tables/83e4d186fc474b0ed739d0595615d2d92068654d466ac4f2e38adb5cded99292.jpg)

![8f07b3e3d0c98ecff94dc4f386184120fd328f14a4be881a8d9022fe942f223b.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/tables/8f07b3e3d0c98ecff94dc4f386184120fd328f14a4be881a8d9022fe942f223b.jpg)

![c03d471a08c3ead4c0158860f5ee949b85575bf1cf447ee6e8b751fcd2fbfe14.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/tables/c03d471a08c3ead4c0158860f5ee949b85575bf1cf447ee6e8b751fcd2fbfe14.jpg)

![c26c00701d4285fcf203212e345c178235f585f14200f6bf811d930ff52011d1.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/tables/c26c00701d4285fcf203212e345c178235f585f14200f6bf811d930ff52011d1.jpg)

![c85cab2d818049744529c31422209606d585a8755bb2dce6f5cdc72d97de7153.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/tables/c85cab2d818049744529c31422209606d585a8755bb2dce6f5cdc72d97de7153.jpg)

![d4e331e07caf1542d35c8610e71011720c2f08e453364977949747c96dbd9f18.jpg](../nips_results/3889_Unified%20all-atom%20molecule%20generation%20with%20neural%20fields/tables/d4e331e07caf1542d35c8610e71011720c2f08e453364977949747c96dbd9f18.jpg)

## Contrastive Learning with Data Misalignment: Feature Purity, Training Dynamics and Theoretical Generalization Guarantees


### Images

![39ef3f2cb126816431099d1a0179147b8ab6b753b756126f1558fa1465c6e4c1.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/images/39ef3f2cb126816431099d1a0179147b8ab6b753b756126f1558fa1465c6e4c1.jpg)

![44caca4d56e88f3905a6eb3ec86721591f738247918aac8576f27d7ac8f426b2.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/images/44caca4d56e88f3905a6eb3ec86721591f738247918aac8576f27d7ac8f426b2.jpg)

![b66704a8221585077a4ae9035eabe18dbf15d82024742fc3864deb1f49adb30f.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/images/b66704a8221585077a4ae9035eabe18dbf15d82024742fc3864deb1f49adb30f.jpg)

![bd2f0a59471cabc0d56def1c740881486bcdbe56b197bcf84331238b5f1e889a.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/images/bd2f0a59471cabc0d56def1c740881486bcdbe56b197bcf84331238b5f1e889a.jpg)

![d022874692e1dbcaf57cf227d44fb6ba8fcfa1e519ffa43e7a3172f576dcaf40.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/images/d022874692e1dbcaf57cf227d44fb6ba8fcfa1e519ffa43e7a3172f576dcaf40.jpg)

![d9529a076dc400a8ca947b37a2f8232affe1723c78f8327eff6d1d9fdd281d4b.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/images/d9529a076dc400a8ca947b37a2f8232affe1723c78f8327eff6d1d9fdd281d4b.jpg)

![d9d90ffae4a208a32465770aa5e65242df63243248044dcd2fe5640393c9fa29.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/images/d9d90ffae4a208a32465770aa5e65242df63243248044dcd2fe5640393c9fa29.jpg)

![ef3b84b668387210c627162e20f0b0bc23b8386a63d4cd8fca5071e30d24127c.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/images/ef3b84b668387210c627162e20f0b0bc23b8386a63d4cd8fca5071e30d24127c.jpg)

### Tables

![05366c9b625fac96fc1ab86413a0be3b81cb30456c7577b0009d591a28223a6f.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/tables/05366c9b625fac96fc1ab86413a0be3b81cb30456c7577b0009d591a28223a6f.jpg)

![2e3f13da7dbc5f799113236902cfa2611a69c4533cdcf575f9dcf505820d07d8.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/tables/2e3f13da7dbc5f799113236902cfa2611a69c4533cdcf575f9dcf505820d07d8.jpg)

![61a43405a9232cd57d69f526a86ae33d44a52590d12f7a2823fd8317c8c8fffb.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/tables/61a43405a9232cd57d69f526a86ae33d44a52590d12f7a2823fd8317c8c8fffb.jpg)

![b06e63640c0edcde109e6ae3d03012948bd05c5a0aac34f5cc2c5215f0714ee5.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/tables/b06e63640c0edcde109e6ae3d03012948bd05c5a0aac34f5cc2c5215f0714ee5.jpg)

![dd3bdf4ef672beb6188dd7610c9844cbc428424067086eb9b4dccf414886a2cf.jpg](../nips_results/3890_Contrastive%20Learning%20with%20Data%20Misalignment_%20Feature%20Purity%2C%20Training%20Dynamics%20and%20Theoretical%20Gener/tables/dd3bdf4ef672beb6188dd7610c9844cbc428424067086eb9b4dccf414886a2cf.jpg)

## Covering Multiple Objectives with a Small Set of Solutions Using Bayesian Optimization


### Images

![1451646a77ec57eb028d9cbd1db03d656438c6e8d6b0087f29ae0bc252e0a527.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/1451646a77ec57eb028d9cbd1db03d656438c6e8d6b0087f29ae0bc252e0a527.jpg)

![20bef264f158d86a413d1fef1400d3f521390d2f245d152634707090b19e53e1.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/20bef264f158d86a413d1fef1400d3f521390d2f245d152634707090b19e53e1.jpg)

![22cbcd680254320e8317cbda6303a11e1925de671ba5485feb9d27fd5771d55b.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/22cbcd680254320e8317cbda6303a11e1925de671ba5485feb9d27fd5771d55b.jpg)

![28fe176143fa181ddfbd20d15ff1c57c1e9674e74f1df42cc38e0312b8808eaf.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/28fe176143fa181ddfbd20d15ff1c57c1e9674e74f1df42cc38e0312b8808eaf.jpg)

![2a9152ea41281edaa9a32bc0ef08c87784e1c111f5f005269af0be6d15b4e260.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/2a9152ea41281edaa9a32bc0ef08c87784e1c111f5f005269af0be6d15b4e260.jpg)

![2eff3e186de087c526ec9a9f14ede382e9620066e9e3f128121253bc8893d13b.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/2eff3e186de087c526ec9a9f14ede382e9620066e9e3f128121253bc8893d13b.jpg)

![784786ea84901eb0123814d8dee0bc14e5fc0ef082ed8e1546d66b86bcfeea3d.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/784786ea84901eb0123814d8dee0bc14e5fc0ef082ed8e1546d66b86bcfeea3d.jpg)

![78538d739abe81e9712091a239c061da00fcacf5057abce6127d2ac73e20b364.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/78538d739abe81e9712091a239c061da00fcacf5057abce6127d2ac73e20b364.jpg)

![7dee3abdfab2f9911f7b1cb20bb6c9c73941f0d42eadbd0e8a826b63b347c7e4.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/7dee3abdfab2f9911f7b1cb20bb6c9c73941f0d42eadbd0e8a826b63b347c7e4.jpg)

![9330031475d0d6ebcd65d8966b03177e4e178c538b8057fc05284f9762bc2d00.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/9330031475d0d6ebcd65d8966b03177e4e178c538b8057fc05284f9762bc2d00.jpg)

![c435b743878fbe8c8b2b95f87f8900226bc759ed5e3423220d577ba5d48dc74f.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/c435b743878fbe8c8b2b95f87f8900226bc759ed5e3423220d577ba5d48dc74f.jpg)

![d030d20192edb17a5843b71d290e359929d211f414a3c8b0035448410861a7c9.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/d030d20192edb17a5843b71d290e359929d211f414a3c8b0035448410861a7c9.jpg)

![e45c465b70831368eb78a394b320c1c829a0b5ebbce5eea30be462c06d1d50a8.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/e45c465b70831368eb78a394b320c1c829a0b5ebbce5eea30be462c06d1d50a8.jpg)

![e50154d81e6257ca4b1f952e39ebb63472096426f61201d0aa0045c83f9b24ca.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/e50154d81e6257ca4b1f952e39ebb63472096426f61201d0aa0045c83f9b24ca.jpg)

![eb1e8c36818a033cfe561b5ffcf0fb3acde277ff764a290d84d290bfba2a4f56.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/images/eb1e8c36818a033cfe561b5ffcf0fb3acde277ff764a290d84d290bfba2a4f56.jpg)

### Tables

![4a84e5ac98b1a31eb0fa769812ba1eeb33d597520d16252854cdf93d62a19970.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/tables/4a84e5ac98b1a31eb0fa769812ba1eeb33d597520d16252854cdf93d62a19970.jpg)

![7228624b864d40214b8582b519ddc4b5f180c0ed6f3c3d3a103ebd3770216f08.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/tables/7228624b864d40214b8582b519ddc4b5f180c0ed6f3c3d3a103ebd3770216f08.jpg)

![945aa757b3ec8e5383e7a8980fe5a08383b646c2c9702bea83c6505a2744baae.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/tables/945aa757b3ec8e5383e7a8980fe5a08383b646c2c9702bea83c6505a2744baae.jpg)

![99500d9570008dea62908c88600a24edb0b3ad5667910afa89611031231c5f1c.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/tables/99500d9570008dea62908c88600a24edb0b3ad5667910afa89611031231c5f1c.jpg)

![ba77f1e42d1cd933c72c5f030d116af1a386701a58f3433dc0cf01bfb032c763.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/tables/ba77f1e42d1cd933c72c5f030d116af1a386701a58f3433dc0cf01bfb032c763.jpg)

![dc0ed9b0b031bd723edcfd48947f6b8505d1b5c7b932adbbc56bf2cc80eceacf.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/tables/dc0ed9b0b031bd723edcfd48947f6b8505d1b5c7b932adbbc56bf2cc80eceacf.jpg)

![de1658ce2c48186fb8c41f90e1317d873c598fcc5bbb2dcf36eb52d080c8db46.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/tables/de1658ce2c48186fb8c41f90e1317d873c598fcc5bbb2dcf36eb52d080c8db46.jpg)

![e21ec887c68b91e8286031c80a507d4d077e0a0f787d0152e1268a0abc00dcde.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/tables/e21ec887c68b91e8286031c80a507d4d077e0a0f787d0152e1268a0abc00dcde.jpg)

![f9c02c01391f6b5ba9a42e9e693197a43a0b569c1754e966734fc2a699918fd9.jpg](../nips_results/3891_Covering%20Multiple%20Objectives%20with%20a%20Small%20Set%20of%20Solutions%20Using%20Bayesian%20Optimization/tables/f9c02c01391f6b5ba9a42e9e693197a43a0b569c1754e966734fc2a699918fd9.jpg)

## StegoZip: Enhancing Linguistic Steganography Payload in Practice with Large Language Models


### Images

![0c5914712fddf392d0489ec0258ca594080f624ffd98ed1e9a5b503916d5b5fc.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/images/0c5914712fddf392d0489ec0258ca594080f624ffd98ed1e9a5b503916d5b5fc.jpg)

![0ceb58fc01583ed0c9c23f60b0faf87c96db7c123cc853e8ac97427a07507300.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/images/0ceb58fc01583ed0c9c23f60b0faf87c96db7c123cc853e8ac97427a07507300.jpg)

![2162c8a185a06222fb96b0be466972196c807d5eca63149ef83d118951fc5d33.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/images/2162c8a185a06222fb96b0be466972196c807d5eca63149ef83d118951fc5d33.jpg)

![21f903824546d593f8b8d45767abeb307a537033119dcc69fa6128800dc29670.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/images/21f903824546d593f8b8d45767abeb307a537033119dcc69fa6128800dc29670.jpg)

![ad3df73acecf2a6df16fd70245e582b9506be3ac4a036689c7029bd023be9084.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/images/ad3df73acecf2a6df16fd70245e582b9506be3ac4a036689c7029bd023be9084.jpg)

![b639709e01f9ee8eaf766c35eb37a9cb7c340c47c72affaf6aaa3fdda567c260.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/images/b639709e01f9ee8eaf766c35eb37a9cb7c340c47c72affaf6aaa3fdda567c260.jpg)

![f690823b0aeaa8cc3c52412684242888ead0660cdb88956c7f8ddb71a1687a4c.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/images/f690823b0aeaa8cc3c52412684242888ead0660cdb88956c7f8ddb71a1687a4c.jpg)

![fc895c4958e16c15b75a304c5957a5e5517f4fb1c923f9a2f8a7d230963c507f.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/images/fc895c4958e16c15b75a304c5957a5e5517f4fb1c923f9a2f8a7d230963c507f.jpg)

### Tables

![0e807d1644f29e990bc7d84baf1b903a7c26c3a6f44ef292be911776bbc34471.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/tables/0e807d1644f29e990bc7d84baf1b903a7c26c3a6f44ef292be911776bbc34471.jpg)

![6db9cbe6899b7f4c8378f6630ff29292f908551c9b1153109fb782d0a27093e3.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/tables/6db9cbe6899b7f4c8378f6630ff29292f908551c9b1153109fb782d0a27093e3.jpg)

![7781bb3b245cf2e305be58ad708b6c7b988fc7f346ff8b1db246049348074378.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/tables/7781bb3b245cf2e305be58ad708b6c7b988fc7f346ff8b1db246049348074378.jpg)

![87df16c29fdc5893c6a21f9705145688e955cba81bf37316e3079028d1764361.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/tables/87df16c29fdc5893c6a21f9705145688e955cba81bf37316e3079028d1764361.jpg)

![dee6a22b390292d96809bb223162399305c152d27afff82c748aec0ba28bfe11.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/tables/dee6a22b390292d96809bb223162399305c152d27afff82c748aec0ba28bfe11.jpg)

![e551f67a6dfbb09674815f970dd5815fec0b7dfc81d621cf1066070b01156a78.jpg](../nips_results/3892_StegoZip_%20Enhancing%20Linguistic%20Steganography%20Payload%20in%20Practice%20with%20Large%20Language%20Models/tables/e551f67a6dfbb09674815f970dd5815fec0b7dfc81d621cf1066070b01156a78.jpg)

## Scalable Policy-Based RL Algorithms for POMDPs


### Images

![9d2bd2d526a348fd04168cd3d85a6b7139098610a1b8e0f5eddc43d48ef4fde3.jpg](../nips_results/3893_Scalable%20Policy-Based%20RL%20Algorithms%20for%20POMDPs/images/9d2bd2d526a348fd04168cd3d85a6b7139098610a1b8e0f5eddc43d48ef4fde3.jpg)

![a5f9583b2028fd6ef41876e4bfb3708257e8285dfc2fd5261fffa23b3aa17cde.jpg](../nips_results/3893_Scalable%20Policy-Based%20RL%20Algorithms%20for%20POMDPs/images/a5f9583b2028fd6ef41876e4bfb3708257e8285dfc2fd5261fffa23b3aa17cde.jpg)

![e4f1efc09c9300116d1f1f1bb14c625a39dea5daf82a623bd9b9d5209d8d3b0d.jpg](../nips_results/3893_Scalable%20Policy-Based%20RL%20Algorithms%20for%20POMDPs/images/e4f1efc09c9300116d1f1f1bb14c625a39dea5daf82a623bd9b9d5209d8d3b0d.jpg)

### Tables

![3508c54cc05489e1fb2d9f3c47d886f827c0f6cf51ea25c196bd3390cc810047.jpg](../nips_results/3893_Scalable%20Policy-Based%20RL%20Algorithms%20for%20POMDPs/tables/3508c54cc05489e1fb2d9f3c47d886f827c0f6cf51ea25c196bd3390cc810047.jpg)

![7e1b5e7e2e10f1d3f46683fe59f8330a4051976ee4421637596ae50bda112077.jpg](../nips_results/3893_Scalable%20Policy-Based%20RL%20Algorithms%20for%20POMDPs/tables/7e1b5e7e2e10f1d3f46683fe59f8330a4051976ee4421637596ae50bda112077.jpg)

![9b18d442dc77d58c3088ba6a6f27c4ed92000e47bbcdea9cbf5bd2116d33b5f2.jpg](../nips_results/3893_Scalable%20Policy-Based%20RL%20Algorithms%20for%20POMDPs/tables/9b18d442dc77d58c3088ba6a6f27c4ed92000e47bbcdea9cbf5bd2116d33b5f2.jpg)

## Decreasing Entropic Regularization Averaged Gradient for Semi-Discrete Optimal Transport

### Images

![0039543ae357567fa26cd8ebc0a22e8bdc7dfbb071c376dbd2622a368ee8860d.jpg](../nips_results/3894_Decreasing%20Entropic%20Regularization%20Averaged%20Gradient%20for%20Semi-Discrete%20Optimal%20Transport/images/0039543ae357567fa26cd8ebc0a22e8bdc7dfbb071c376dbd2622a368ee8860d.jpg)

![2c113f157c3276df60bb556dd68c5c02a95f53f51baeaaf73629c1b97ddd251c.jpg](../nips_results/3894_Decreasing%20Entropic%20Regularization%20Averaged%20Gradient%20for%20Semi-Discrete%20Optimal%20Transport/images/2c113f157c3276df60bb556dd68c5c02a95f53f51baeaaf73629c1b97ddd251c.jpg)

![4cf684e63260cfea6e6f6a7e91483099a4534d2265015e4d51bbc67267d07821.jpg](../nips_results/3894_Decreasing%20Entropic%20Regularization%20Averaged%20Gradient%20for%20Semi-Discrete%20Optimal%20Transport/images/4cf684e63260cfea6e6f6a7e91483099a4534d2265015e4d51bbc67267d07821.jpg)

![6bb8d15feac41ed07d48b260264f4d9a99ca87d746f635b496cdf54dc644a751.jpg](../nips_results/3894_Decreasing%20Entropic%20Regularization%20Averaged%20Gradient%20for%20Semi-Discrete%20Optimal%20Transport/images/6bb8d15feac41ed07d48b260264f4d9a99ca87d746f635b496cdf54dc644a751.jpg)

![96a31b81a5cf4e5797d0e01dbe586176769e8f4874e902a9f5990133e9fb4f15.jpg](../nips_results/3894_Decreasing%20Entropic%20Regularization%20Averaged%20Gradient%20for%20Semi-Discrete%20Optimal%20Transport/images/96a31b81a5cf4e5797d0e01dbe586176769e8f4874e902a9f5990133e9fb4f15.jpg)

![bba80603561af7b9bf6f9dec75a4ee91381269e64558e5bf623e8efe5a3cd7b0.jpg](../nips_results/3894_Decreasing%20Entropic%20Regularization%20Averaged%20Gradient%20for%20Semi-Discrete%20Optimal%20Transport/images/bba80603561af7b9bf6f9dec75a4ee91381269e64558e5bf623e8efe5a3cd7b0.jpg)

![c1fd8c873160f4cfb03cedbe124e4e51c238866e07871f77b60d319d9399e466.jpg](../nips_results/3894_Decreasing%20Entropic%20Regularization%20Averaged%20Gradient%20for%20Semi-Discrete%20Optimal%20Transport/images/c1fd8c873160f4cfb03cedbe124e4e51c238866e07871f77b60d319d9399e466.jpg)

![d89087fbaa3056359dbfe4f6210fe243f0b7f08cd80c784ffabe0d34b6b97481.jpg](../nips_results/3894_Decreasing%20Entropic%20Regularization%20Averaged%20Gradient%20for%20Semi-Discrete%20Optimal%20Transport/images/d89087fbaa3056359dbfe4f6210fe243f0b7f08cd80c784ffabe0d34b6b97481.jpg)

![d970df4017d33e9674bf4d7395d0432a1a498d714bf2667adf3d03cf07b523ef.jpg](../nips_results/3894_Decreasing%20Entropic%20Regularization%20Averaged%20Gradient%20for%20Semi-Discrete%20Optimal%20Transport/images/d970df4017d33e9674bf4d7395d0432a1a498d714bf2667adf3d03cf07b523ef.jpg)
