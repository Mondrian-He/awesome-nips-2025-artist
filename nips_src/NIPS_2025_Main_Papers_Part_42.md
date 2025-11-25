# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 42 of 130

## 目录 (Table of Contents)

1. [Adaptive Latent-Space Constraints in Personalized Federated Learning](#Adaptive-Latent-Space-Constraints-in-Personalized-Federated-Learning)
2. [Kernel Learning with Adversarial Features: Numerical Efficiency and Adaptive Regularization](#Kernel-Learning-with-Adversarial-Features-Numerical-Efficiency-and-Adaptive-Regularization)
3. [Beyond Masked and Unmasked: Discrete Diffusion Models via Partial Masking](#Beyond-Masked-and-Unmasked-Discrete-Diffusion-Models-via-Partial-Masking)
4. [Training-Free Guidance Beyond Differentiability: Scalable Path Steering with Tree Search in Diffusion and Flow Models](#Training-Free-Guidance-Beyond-Differentiability-Scalable-Path-Steering-with-Tree-Search-in-Diffusion-and-Flow-Models)
5. [On Hierarchies of Fairness Notions in Cake Cutting: From Proportionality to Super Envy-Freeness](#On-Hierarchies-of-Fairness-Notions-in-Cake-Cutting-From-Proportionality-to-Super-Envy-Freeness)
6. [Frame In-N-Out: Unbounded Controllable Image-to-Video Generation](#Frame-In-N-Out-Unbounded-Controllable-Image-to-Video-Generation)
7. [Efficiently Scaling LLM Reasoning Programs with Certaindex](#Efficiently-Scaling-LLM-Reasoning-Programs-with-Certaindex)
8. [G-Net: A Provably Easy Construction of High-Accuracy Random Binary Neural Networks](#G-Net-A-Provably-Easy-Construction-of-High-Accuracy-Random-Binary-Neural-Networks)
9. [STNet: Spectral Transformation Network for Solving Operator Eigenvalue Problem](#STNet-Spectral-Transformation-Network-for-Solving-Operator-Eigenvalue-Problem)
10. [Imbalances in Neurosymbolic Learning: Characterization and Mitigating Strategies](#Imbalances-in-Neurosymbolic-Learning-Characterization-and-Mitigating-Strategies)
11. [An Effective Levelling Paradigm for Unlabeled Scenarios](#An-Effective-Levelling-Paradigm-for-Unlabeled-Scenarios)
12. [Truth over Tricks: Measuring and Mitigating Shortcut Learning in Misinformation Detection](#Truth-over-Tricks-Measuring-and-Mitigating-Shortcut-Learning-in-Misinformation-Detection)
13. [Representational Difference Explanations](#Representational-Difference-Explanations)
14. [Stratify or Die: Rethinking Data Splits in Image Segmentation](#Stratify-or-Die-Rethinking-Data-Splits-in-Image-Segmentation)
15. [Quantifying Uncertainty in Error Consistency: Towards Reliable Behavioral Comparison of Classifiers](#Quantifying-Uncertainty-in-Error-Consistency-Towards-Reliable-Behavioral-Comparison-of-Classifiers)
16. [SPAZER: Spatial-Semantic Progressive Reasoning Agent for Zero-shot 3D Visual Grounding](#SPAZER-Spatial-Semantic-Progressive-Reasoning-Agent-for-Zero-shot-3D-Visual-Grounding)
17. [Rotary Masked Autoencoders are Versatile Learners](#Rotary-Masked-Autoencoders-are-Versatile-Learners)
18. [NavBench: Probing Multimodal Large Language Models for Embodied Navigation](#NavBench-Probing-Multimodal-Large-Language-Models-for-Embodied-Navigation)
19. [Diff-ICMH: Harmonizing Machine and Human Vision in Image Compression with Generative Prior](#Diff-ICMH-Harmonizing-Machine-and-Human-Vision-in-Image-Compression-with-Generative-Prior)
20. [Nested Learning: The Illusion of Deep Learning Architectures](#Nested-Learning-The-Illusion-of-Deep-Learning-Architectures)
21. [On Local Limits of Sparse Random Graphs: Color Convergence and the Refined Configuration Model](#On-Local-Limits-of-Sparse-Random-Graphs-Color-Convergence-and-the-Refined-Configuration-Model)
22. [Language Models (Mostly) Know When to Stop Reading](#Language-Models-Mostly-Know-When-to-Stop-Reading)
23. [Towards Generalizable 3D Human Pose Estimation via Ensembles on Flat Loss Landscapes](#Towards-Generalizable-3D-Human-Pose-Estimation-via-Ensembles-on-Flat-Loss-Landscapes)
24. [Statistical inference for Linear Stochastic Approximation with Markovian Noise](#Statistical-inference-for-Linear-Stochastic-Approximation-with-Markovian-Noise)
25. [AdaptGrad: Adaptive Sampling to Reduce Noise](#AdaptGrad-Adaptive-Sampling-to-Reduce-Noise)
26. [Compositional Reasoning with Transformers, RNNs, and Chain of Thought](#Compositional-Reasoning-with-Transformers-RNNs-and-Chain-of-Thought)
27. [OSTAR: Optimized Statistical Text-classifier with Adversarial Resistance](#OSTAR-Optimized-Statistical-Text-classifier-with-Adversarial-Resistance)
28. [Sparta Alignment: Collectively Aligning Multiple Language Models through Combat](#Sparta-Alignment-Collectively-Aligning-Multiple-Language-Models-through-Combat)
29. [Vision Function Layer in Multimodal LLMs](#Vision-Function-Layer-in-Multimodal-LLMs)
30. [VarFlow: Proper Scoring-Rule Diffusion Distillation via Energy Matching](#VarFlow-Proper-Scoring-Rule-Diffusion-Distillation-via-Energy-Matching)
31. [Evolutionary Reasoning Does Not Arise in Standard Usage of Protein Language Models](#Evolutionary-Reasoning-Does-Not-Arise-in-Standard-Usage-of-Protein-Language-Models)
32. [Breaking the Compression Ceiling: Data-Free Pipeline for Ultra-Efficient Delta Compression](#Breaking-the-Compression-Ceiling-Data-Free-Pipeline-for-Ultra-Efficient-Delta-Compression)
33. [Bridging Time and Linguistics: LLMs as Time Series Analyzer through Symbolization and Segmentation](#Bridging-Time-and-Linguistics-LLMs-as-Time-Series-Analyzer-through-Symbolization-and-Segmentation)
34. [C-SafeGen: Certified Safe LLM Generation with Claim-Based Streaming Guardrails](#C-SafeGen-Certified-Safe-LLM-Generation-with-Claim-Based-Streaming-Guardrails)
35. [Unveiling Environmental Sensitivity of Individual Gains in Influence Maximization](#Unveiling-Environmental-Sensitivity-of-Individual-Gains-in-Influence-Maximization)
36. [Multivariate Latent Recalibration for Conditional Normalizing Flows](#Multivariate-Latent-Recalibration-for-Conditional-Normalizing-Flows)
37. [Dynamics of Spontaneous Topic Changes in Next Token Prediction with Self-Attention](#Dynamics-of-Spontaneous-Topic-Changes-in-Next-Token-Prediction-with-Self-Attention)
38. [Identifying Macro Causal Effects in C-DMGs over DMGs](#Identifying-Macro-Causal-Effects-in-C-DMGs-over-DMGs)
39. [Learning Temporal 3D Semantic Scene Completion via Optical Flow Guidance](#Learning-Temporal-3D-Semantic-Scene-Completion-via-Optical-Flow-Guidance)
40. [Learning to Watermark: A Selective Watermarking Framework for Large Language Models via Multi-Objective Optimization](#Learning-to-Watermark-A-Selective-Watermarking-Framework-for-Large-Language-Models-via-Multi-Objective-Optimization)
41. [Walking the Schrödinger Bridge: A Direct Trajectory for Text-to-3D Generation](#Walking-the-Schrödinger-Bridge-A-Direct-Trajectory-for-Text-to-3D-Generation)

---


## Adaptive Latent-Space Constraints in Personalized Federated Learning

### Images

![2278b52912e3042416954c406436751bc65caae4ea24f930bdbe995c68c2ac44.jpg](../nips_results/1705_Factor%20Decorrelation%20Enhanced%20Data%20Removal%20from%20Deep%20Predictive%20Models/images/2278b52912e3042416954c406436751bc65caae4ea24f930bdbe995c68c2ac44.jpg)

![25844cc48f3c72ba7e359405700c2fad2df5535075e62831d3bbd3641bbfadac.jpg](../nips_results/1705_Factor%20Decorrelation%20Enhanced%20Data%20Removal%20from%20Deep%20Predictive%20Models/images/25844cc48f3c72ba7e359405700c2fad2df5535075e62831d3bbd3641bbfadac.jpg)

![33829da743401de424229833f431cf796e224996d3c2d37ba8654271a6636621.jpg](../nips_results/1705_Factor%20Decorrelation%20Enhanced%20Data%20Removal%20from%20Deep%20Predictive%20Models/images/33829da743401de424229833f431cf796e224996d3c2d37ba8654271a6636621.jpg)

![60b1f4bd87e194efe67f12df565c2a56048e9d2e8010370dad46078b7d838a40.jpg](../nips_results/1705_Factor%20Decorrelation%20Enhanced%20Data%20Removal%20from%20Deep%20Predictive%20Models/images/60b1f4bd87e194efe67f12df565c2a56048e9d2e8010370dad46078b7d838a40.jpg)

![8c46f7d08239a8793a8324d1198119186095231f5134a29512d415afa3b655f4.jpg](../nips_results/1705_Factor%20Decorrelation%20Enhanced%20Data%20Removal%20from%20Deep%20Predictive%20Models/images/8c46f7d08239a8793a8324d1198119186095231f5134a29512d415afa3b655f4.jpg)

![9edafbd2aa23ba43f8ef1e432f263c00f85274fc06a40f576794eff47b49b3d0.jpg](../nips_results/1705_Factor%20Decorrelation%20Enhanced%20Data%20Removal%20from%20Deep%20Predictive%20Models/images/9edafbd2aa23ba43f8ef1e432f263c00f85274fc06a40f576794eff47b49b3d0.jpg)

### Tables

![11fce890a8e4245fddda70d4068628d6cb5b3928e3fa7385227e5b0b24aee654.jpg](../nips_results/1705_Factor%20Decorrelation%20Enhanced%20Data%20Removal%20from%20Deep%20Predictive%20Models/tables/11fce890a8e4245fddda70d4068628d6cb5b3928e3fa7385227e5b0b24aee654.jpg)

![2dd1a87c9db8b06500692c048bbf48d273580e4bcf119b9fd09dd0dd194e4645.jpg](../nips_results/1705_Factor%20Decorrelation%20Enhanced%20Data%20Removal%20from%20Deep%20Predictive%20Models/tables/2dd1a87c9db8b06500692c048bbf48d273580e4bcf119b9fd09dd0dd194e4645.jpg)

![47b7a7eff7124f04a65f089f0bebbd2823fb8d3887a14da46f7b9ef167151951.jpg](../nips_results/1705_Factor%20Decorrelation%20Enhanced%20Data%20Removal%20from%20Deep%20Predictive%20Models/tables/47b7a7eff7124f04a65f089f0bebbd2823fb8d3887a14da46f7b9ef167151951.jpg)

![5d97da63d1ba6c4d17c54157474c89eb68866eaa4cd1eeabd8842adb816e1d1e.jpg](../nips_results/1705_Factor%20Decorrelation%20Enhanced%20Data%20Removal%20from%20Deep%20Predictive%20Models/tables/5d97da63d1ba6c4d17c54157474c89eb68866eaa4cd1eeabd8842adb816e1d1e.jpg)

![a68220be4933c2a4dc315fbca379f55a1a4e807e111fdce0c7d6468bcd008f06.jpg](../nips_results/1705_Factor%20Decorrelation%20Enhanced%20Data%20Removal%20from%20Deep%20Predictive%20Models/tables/a68220be4933c2a4dc315fbca379f55a1a4e807e111fdce0c7d6468bcd008f06.jpg)

## Adaptive Latent-Space Constraints in Personalized Federated Learning


### Images

![932623fcd7451304ef67d29e64760ce9fe96bf64364a005cd8a49cc144af886d.jpg](../nips_results/1706_Adaptive%20Latent-Space%20Constraints%20in%20Personalized%20Federated%20Learning/images/932623fcd7451304ef67d29e64760ce9fe96bf64364a005cd8a49cc144af886d.jpg)

![a197c35f098f4181c540e850dbd7f711f0423975df165abebfb82c7439defc2f.jpg](../nips_results/1706_Adaptive%20Latent-Space%20Constraints%20in%20Personalized%20Federated%20Learning/images/a197c35f098f4181c540e850dbd7f711f0423975df165abebfb82c7439defc2f.jpg)

![f5f335babee2022ea73f039aca372b8ccc772b3f641fc51cfd9e79646b6cec27.jpg](../nips_results/1706_Adaptive%20Latent-Space%20Constraints%20in%20Personalized%20Federated%20Learning/images/f5f335babee2022ea73f039aca372b8ccc772b3f641fc51cfd9e79646b6cec27.jpg)

### Tables

![572326185c2a27052031a635c2548e2319989cfb9f463081c87552132f58c3ba.jpg](../nips_results/1706_Adaptive%20Latent-Space%20Constraints%20in%20Personalized%20Federated%20Learning/tables/572326185c2a27052031a635c2548e2319989cfb9f463081c87552132f58c3ba.jpg)

![8558ff9b33d202ba9d5cde10f67381edb3eb6e0f1a1bb8f6a95e325735ce3c8f.jpg](../nips_results/1706_Adaptive%20Latent-Space%20Constraints%20in%20Personalized%20Federated%20Learning/tables/8558ff9b33d202ba9d5cde10f67381edb3eb6e0f1a1bb8f6a95e325735ce3c8f.jpg)

![8850edc53e9fe39ae1021219b5c50b15c772b2f64c277980a1bfaf8a1c6459de.jpg](../nips_results/1706_Adaptive%20Latent-Space%20Constraints%20in%20Personalized%20Federated%20Learning/tables/8850edc53e9fe39ae1021219b5c50b15c772b2f64c277980a1bfaf8a1c6459de.jpg)

![a8af4560c4f392d11df08a158dc34438031ac2cf4c2107b203085d8585b96747.jpg](../nips_results/1706_Adaptive%20Latent-Space%20Constraints%20in%20Personalized%20Federated%20Learning/tables/a8af4560c4f392d11df08a158dc34438031ac2cf4c2107b203085d8585b96747.jpg)

![c426f26afa54aa8c9f9671c747681990c2330ef31cf6a8c0da7f136822f666ab.jpg](../nips_results/1706_Adaptive%20Latent-Space%20Constraints%20in%20Personalized%20Federated%20Learning/tables/c426f26afa54aa8c9f9671c747681990c2330ef31cf6a8c0da7f136822f666ab.jpg)

![d96d31fcb0f392e51391524ce8302103de25ab044beb01c1ec5c0dd6130a087b.jpg](../nips_results/1706_Adaptive%20Latent-Space%20Constraints%20in%20Personalized%20Federated%20Learning/tables/d96d31fcb0f392e51391524ce8302103de25ab044beb01c1ec5c0dd6130a087b.jpg)

## Kernel Learning with Adversarial Features: Numerical Efficiency and Adaptive Regularization


### Images

![52791d48972f8c170d1c2465bef8105e6cd4ced7d4c93df4812cbd38c75f971f.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/images/52791d48972f8c170d1c2465bef8105e6cd4ced7d4c93df4812cbd38c75f971f.jpg)

![5dac86b942e52201e62625399380dcbb1f3272633e712d1632266cdb642f626a.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/images/5dac86b942e52201e62625399380dcbb1f3272633e712d1632266cdb642f626a.jpg)

![6d1874cca4bbec1dc8be397bcf56ea686e8b2fc0ccd4340c9c4e83a0ee46f632.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/images/6d1874cca4bbec1dc8be397bcf56ea686e8b2fc0ccd4340c9c4e83a0ee46f632.jpg)

![7db4afeb506b706f058ba4b773d3eaf74e45bda9466ce6cfd9600d6bc138acdc.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/images/7db4afeb506b706f058ba4b773d3eaf74e45bda9466ce6cfd9600d6bc138acdc.jpg)

![91eb5aaaec79563be3b94370ad00f89277410e069a346cf7db77766aebd626e0.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/images/91eb5aaaec79563be3b94370ad00f89277410e069a346cf7db77766aebd626e0.jpg)

![ec71f79d59669a20033596a922f262a51169b2687e4dc9afbe6a0361f1d2d4b3.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/images/ec71f79d59669a20033596a922f262a51169b2687e4dc9afbe6a0361f1d2d4b3.jpg)

### Tables

![17465e621688896d2bf1c947946fd44618b1e2fca6656b9803bdca7cb484023f.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/tables/17465e621688896d2bf1c947946fd44618b1e2fca6656b9803bdca7cb484023f.jpg)

![32e5dea71a9823f8ad08b4623af9526016536973f9b7c04ef33a58c6cf6c4ce4.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/tables/32e5dea71a9823f8ad08b4623af9526016536973f9b7c04ef33a58c6cf6c4ce4.jpg)

![63910a5b56981df7ed573b21a6dbfd94a4d8f79bcde3cc28802a8f97dc6ca989.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/tables/63910a5b56981df7ed573b21a6dbfd94a4d8f79bcde3cc28802a8f97dc6ca989.jpg)

![760c237fd784b7bdf763850a3194547d13000ebf595721d0815d91a97591e287.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/tables/760c237fd784b7bdf763850a3194547d13000ebf595721d0815d91a97591e287.jpg)

![a5d2165982d9071cf165dbf1ec25dfed7fde400a880927339391d616c692d7b1.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/tables/a5d2165982d9071cf165dbf1ec25dfed7fde400a880927339391d616c692d7b1.jpg)

![b420e3d0161cc7ffc37f4135ea5f3afc7b4bbff546bd5dc1280c8bdde0d7b50e.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/tables/b420e3d0161cc7ffc37f4135ea5f3afc7b4bbff546bd5dc1280c8bdde0d7b50e.jpg)

![e4a41e3a0b0ed6293d747963c6ef2072b21388fa8b262cf57cd83b25f863465b.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/tables/e4a41e3a0b0ed6293d747963c6ef2072b21388fa8b262cf57cd83b25f863465b.jpg)

![fce85706229241f73920442397b75935eb6d9052f77215ecf9f9ce3d503809e9.jpg](../nips_results/1707_Kernel%20Learning%20with%20Adversarial%20Features_%20Numerical%20Efficiency%20and%20Adaptive%20Regularization/tables/fce85706229241f73920442397b75935eb6d9052f77215ecf9f9ce3d503809e9.jpg)

## Beyond Masked and Unmasked: Discrete Diffusion Models via Partial Masking


### Images

![10444375ea0a1900d600eda2e6cc515b145d396f88d9b805c504b95b3703b93f.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/10444375ea0a1900d600eda2e6cc515b145d396f88d9b805c504b95b3703b93f.jpg)

![19c48c955bbabe69f2f4948ea622ca7ede14e78c397270c652d45954d9d5f0ac.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/19c48c955bbabe69f2f4948ea622ca7ede14e78c397270c652d45954d9d5f0ac.jpg)

![1e263b8e1bfea80c75be8ef0e9a135fd877ba0fd06eff6ecc03d0b75873499d2.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/1e263b8e1bfea80c75be8ef0e9a135fd877ba0fd06eff6ecc03d0b75873499d2.jpg)

![1e2a0238bb9c47354701de1c27e8381f83b4be74d3ed67cf4ce5969c21fd3fab.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/1e2a0238bb9c47354701de1c27e8381f83b4be74d3ed67cf4ce5969c21fd3fab.jpg)

![2a4be25cb91d0ac5ff432a86326dd67400adc2dfcb3f0a7e8fa4b9e4fb3824d6.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/2a4be25cb91d0ac5ff432a86326dd67400adc2dfcb3f0a7e8fa4b9e4fb3824d6.jpg)

![2af91f7a31d7891956ce7af7cde2e55b4353911abfdeaa9ebd0288fbb075ce61.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/2af91f7a31d7891956ce7af7cde2e55b4353911abfdeaa9ebd0288fbb075ce61.jpg)

![346499331a8fbaee969a472502a4ec774f066bc9ff9abde0ce3d1cb128689dba.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/346499331a8fbaee969a472502a4ec774f066bc9ff9abde0ce3d1cb128689dba.jpg)

![35856e9fb94f0306bf5133a8c0e3104540141f93bad0ea296c6f221c71d1db36.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/35856e9fb94f0306bf5133a8c0e3104540141f93bad0ea296c6f221c71d1db36.jpg)

![3b2f704149faf94f77cf7095ebbeac27439a22fd12c60eb4e5e696a10bc49f1b.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/3b2f704149faf94f77cf7095ebbeac27439a22fd12c60eb4e5e696a10bc49f1b.jpg)

![56a526d5cfc6181dc21825fc6df6903c2843943a00110197e346843d1eeefe41.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/56a526d5cfc6181dc21825fc6df6903c2843943a00110197e346843d1eeefe41.jpg)

![8cc6d94c5202f4574497557f2719c3ffd2555a82259fe9f10120792c5fc2e237.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/8cc6d94c5202f4574497557f2719c3ffd2555a82259fe9f10120792c5fc2e237.jpg)

![8e815cc48c2492379de98f7bfcd2b0d8f19fe96ce27e564fbb73974c9e6dfacd.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/8e815cc48c2492379de98f7bfcd2b0d8f19fe96ce27e564fbb73974c9e6dfacd.jpg)

![9700b9e9c63945cde9655007bd4756e368b28ada1a615b4424d47cafb13de4b7.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/9700b9e9c63945cde9655007bd4756e368b28ada1a615b4424d47cafb13de4b7.jpg)

![981d160c5e26d92e7e04edcb7f2abac06c04b3459e184132440f7f699a6899ef.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/981d160c5e26d92e7e04edcb7f2abac06c04b3459e184132440f7f699a6899ef.jpg)

![9e76dd7a1fc9dca0162b8ac12aa96ebf94b65018ce5763e8d96709b311ed3caf.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/9e76dd7a1fc9dca0162b8ac12aa96ebf94b65018ce5763e8d96709b311ed3caf.jpg)

![aa86e41897f4e3ff7827460d1db3d259fab941f2a76665bc6640d1f59302bd80.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/aa86e41897f4e3ff7827460d1db3d259fab941f2a76665bc6640d1f59302bd80.jpg)

![b105a49f066de767f442112dacd73ce20a660ee1c0cfdb2bdd85bb24630c2e8a.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/b105a49f066de767f442112dacd73ce20a660ee1c0cfdb2bdd85bb24630c2e8a.jpg)

![bcfc7bfc03fc62f16eafb1181d893675d42132505066a414c2b5cc066ddb7503.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/bcfc7bfc03fc62f16eafb1181d893675d42132505066a414c2b5cc066ddb7503.jpg)

![be6b1d591cbcd226db1bcee884031bac346a2d52bb63723d5c01c10eff5bb02b.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/be6b1d591cbcd226db1bcee884031bac346a2d52bb63723d5c01c10eff5bb02b.jpg)

![c3f328bef51c89a27f9618a381731b2e53e6a1b7f703c1251557199573e68139.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/c3f328bef51c89a27f9618a381731b2e53e6a1b7f703c1251557199573e68139.jpg)

![c51f631712dc6771ec546e2688b0c7539b6aa8d427a34c6c7173fa4e564420a2.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/c51f631712dc6771ec546e2688b0c7539b6aa8d427a34c6c7173fa4e564420a2.jpg)

![cd30c45e4564ef4b7768f950108a80a633fc2a3cfbaccb33b114c4d0f0e024d1.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/cd30c45e4564ef4b7768f950108a80a633fc2a3cfbaccb33b114c4d0f0e024d1.jpg)

![d57d39dbb6d0e5458c7c3f8c75f2a8c0a358c9815a108cb063ca3e62a556901e.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/d57d39dbb6d0e5458c7c3f8c75f2a8c0a358c9815a108cb063ca3e62a556901e.jpg)

![e566e0fbb6de5aa2034d5f1a25a320b0ee80a49453b4f8099cd18ed590a75aec.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/e566e0fbb6de5aa2034d5f1a25a320b0ee80a49453b4f8099cd18ed590a75aec.jpg)

![eceabdfd3e26ff7fd7fe9eb6c429fb5154f6ebed5ad62011dacf48bb2f31d487.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/eceabdfd3e26ff7fd7fe9eb6c429fb5154f6ebed5ad62011dacf48bb2f31d487.jpg)

![f41c99e329e174938c20795b9496a15d8cb4e64e3c52904dcf0a0f18f125906a.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/f41c99e329e174938c20795b9496a15d8cb4e64e3c52904dcf0a0f18f125906a.jpg)

![f95cae8013007e5e497e41101b2fcbfad1fbf63a59783e2dc8b2b5a8e40997cd.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/images/f95cae8013007e5e497e41101b2fcbfad1fbf63a59783e2dc8b2b5a8e40997cd.jpg)

### Tables

![1b1a4679a67c63272b5a0021713350bd4a3e1880bc6e44718af54c95a9006d83.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/tables/1b1a4679a67c63272b5a0021713350bd4a3e1880bc6e44718af54c95a9006d83.jpg)

![282a70eb2c55f2501c90eb2534b1aa75be34ca86673de70584e788c6b829c8c8.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/tables/282a70eb2c55f2501c90eb2534b1aa75be34ca86673de70584e788c6b829c8c8.jpg)

![2e9f04d38dd44582687c3156be9bf90342b677ecf1f68a73335c75150026aed1.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/tables/2e9f04d38dd44582687c3156be9bf90342b677ecf1f68a73335c75150026aed1.jpg)

![38a65ec55dd447805bbfd0f9ee2e3c1ec137329d4f930834bbe573f66d89909f.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/tables/38a65ec55dd447805bbfd0f9ee2e3c1ec137329d4f930834bbe573f66d89909f.jpg)

![6e22685ae5c190509f516658ebab8f97d021166aec10d2dc0632f2a475867a5c.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/tables/6e22685ae5c190509f516658ebab8f97d021166aec10d2dc0632f2a475867a5c.jpg)

![6ea70b0e402e1f8b8c24062924476a5b3769909872602f0bd41435bbb0ed3807.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/tables/6ea70b0e402e1f8b8c24062924476a5b3769909872602f0bd41435bbb0ed3807.jpg)

![71a2e8c12609ed5b35c39bd3237c1274c5dc254428146f55e7e37d1aeb0603e3.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/tables/71a2e8c12609ed5b35c39bd3237c1274c5dc254428146f55e7e37d1aeb0603e3.jpg)

![94d79c8b341e127609ad88692056f68177623e082b629c9348f900c0cb68733c.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/tables/94d79c8b341e127609ad88692056f68177623e082b629c9348f900c0cb68733c.jpg)

![a0cedbdfafb8441a2ab5c8e28010297b40b83937188f24b3f3021eab6d2105a7.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/tables/a0cedbdfafb8441a2ab5c8e28010297b40b83937188f24b3f3021eab6d2105a7.jpg)

![c7453c066d4f47a44508aa5915ae377f2fbabeaa96b6727475af705c90837328.jpg](../nips_results/1708_Beyond%20Masked%20and%20Unmasked_%20Discrete%20Diffusion%20Models%20via%20Partial%20Masking/tables/c7453c066d4f47a44508aa5915ae377f2fbabeaa96b6727475af705c90837328.jpg)

## Training-Free Guidance Beyond Differentiability: Scalable Path Steering with Tree Search in Diffusion and Flow Models


### Images

![0f5ae6cc5216d20d1bff3743cfd107dcad20b5eb2fc3df63aabcb8fe7a41f328.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/images/0f5ae6cc5216d20d1bff3743cfd107dcad20b5eb2fc3df63aabcb8fe7a41f328.jpg)

![326e5d4febcd864e12036e06e8522e22de4700fd5b0526dcc3440f64556d76a6.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/images/326e5d4febcd864e12036e06e8522e22de4700fd5b0526dcc3440f64556d76a6.jpg)

![3433372e2a9da4c4fce77bcd650dddfeae0a2a539b33df24a51b307a60823d37.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/images/3433372e2a9da4c4fce77bcd650dddfeae0a2a539b33df24a51b307a60823d37.jpg)

![3bb2af66c4564374b3b2c6b6bf40a3ae7995c89f58945fab1461f6d3e96bf4ef.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/images/3bb2af66c4564374b3b2c6b6bf40a3ae7995c89f58945fab1461f6d3e96bf4ef.jpg)

![67d571b0f4c53d11a68800cd0dd7b7bbcb189b148de96333eea45c92842b6170.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/images/67d571b0f4c53d11a68800cd0dd7b7bbcb189b148de96333eea45c92842b6170.jpg)

![81c8406427d3feb62145aa2bb81403c217ae9bd082bec238d944eab19319f139.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/images/81c8406427d3feb62145aa2bb81403c217ae9bd082bec238d944eab19319f139.jpg)

![82e223f69751934339bbc5bf557849c156f1dde99be53119565ed911fbd10d4c.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/images/82e223f69751934339bbc5bf557849c156f1dde99be53119565ed911fbd10d4c.jpg)

![9ef1769ec8c32debf45efaf4b141409f41871dcecd4fe483a96f306065f14edb.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/images/9ef1769ec8c32debf45efaf4b141409f41871dcecd4fe483a96f306065f14edb.jpg)

![b56d761175f394dc0eeeee25f06d3bcf71c5448e27c287f16837e5fc306be268.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/images/b56d761175f394dc0eeeee25f06d3bcf71c5448e27c287f16837e5fc306be268.jpg)

![b8f2a6ec2d70e3346081e3ea45c573b85e796a1dd284a5376e76c7c3508a9a6e.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/images/b8f2a6ec2d70e3346081e3ea45c573b85e796a1dd284a5376e76c7c3508a9a6e.jpg)

![d17efb3e2f675744046304010310b6dd6a5777abecac762763bf9285cadda4dc.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/images/d17efb3e2f675744046304010310b6dd6a5777abecac762763bf9285cadda4dc.jpg)

### Tables

![0bf754a1ff4c4c1fde4053802d10697688afd4d07ac44cf462979e4f1209c658.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/0bf754a1ff4c4c1fde4053802d10697688afd4d07ac44cf462979e4f1209c658.jpg)

![1c56eda60beb89ecfcdf6bf4e798f3231d0019b5a03cdf1911e2481156912401.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/1c56eda60beb89ecfcdf6bf4e798f3231d0019b5a03cdf1911e2481156912401.jpg)

![23aadc323095c67846405cdbb19c4cd48b3b75a15d134858fba233423de74c93.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/23aadc323095c67846405cdbb19c4cd48b3b75a15d134858fba233423de74c93.jpg)

![28db6209e32cf81c7fea384b2ab29f6bdd49c79ffcfa1e852b6b5707e898c1bb.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/28db6209e32cf81c7fea384b2ab29f6bdd49c79ffcfa1e852b6b5707e898c1bb.jpg)

![2f9168b092ea3f8879ad9e1b1db2616032c920bcffbf1cee8b42ef6b8aea398a.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/2f9168b092ea3f8879ad9e1b1db2616032c920bcffbf1cee8b42ef6b8aea398a.jpg)

![3daa1af2e5afa10aef87005eb5b56f586e2dcee6677c57029c6d2ae24c3768bb.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/3daa1af2e5afa10aef87005eb5b56f586e2dcee6677c57029c6d2ae24c3768bb.jpg)

![4619bdea1547b99beb733ff1baeb064b38a47816254dfab57dac61b78436629e.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/4619bdea1547b99beb733ff1baeb064b38a47816254dfab57dac61b78436629e.jpg)

![62be243cb3778b5eee346e7020b9d4807de084bc6c0213d25672ea9c9ead7eaa.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/62be243cb3778b5eee346e7020b9d4807de084bc6c0213d25672ea9c9ead7eaa.jpg)

![62e926e022560bcd42976d7d382098791010deeeb0c60fa6587a6208a9c03469.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/62e926e022560bcd42976d7d382098791010deeeb0c60fa6587a6208a9c03469.jpg)

![751b72eb272a24558fcc4d9f9a6560747c8de214a5bd0c8cc4a75a015bf51efe.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/751b72eb272a24558fcc4d9f9a6560747c8de214a5bd0c8cc4a75a015bf51efe.jpg)

![7551629f5cd44d3e6d78b75429bc1ecb0964272ed47c7a22b8be0e8bfa1709f4.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/7551629f5cd44d3e6d78b75429bc1ecb0964272ed47c7a22b8be0e8bfa1709f4.jpg)

![8104e2e53610b266df3dc4f817cebe3fb56ad25e966832cd2c92d5ddff794b2e.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/8104e2e53610b266df3dc4f817cebe3fb56ad25e966832cd2c92d5ddff794b2e.jpg)

![8530cf9abe145574e744e6183f24d202ca9198679d7cd774bda9c886a7d27a05.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/8530cf9abe145574e744e6183f24d202ca9198679d7cd774bda9c886a7d27a05.jpg)

![8b41df7b890abca05b7c4f96073440e72e0fb0e5dc276368c81a541b5469e2d6.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/8b41df7b890abca05b7c4f96073440e72e0fb0e5dc276368c81a541b5469e2d6.jpg)

![a9c4a783c01684aa46296c8cf3ccf68abbd697d178272626c6a689fe0a9c70d8.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/a9c4a783c01684aa46296c8cf3ccf68abbd697d178272626c6a689fe0a9c70d8.jpg)

![afe325e2ae070a5ead74d19e688ea2f4b54f6adc3cf03346f400f04d9b37a5e4.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/afe325e2ae070a5ead74d19e688ea2f4b54f6adc3cf03346f400f04d9b37a5e4.jpg)

![b0e17363aa1ed2b0f4227eca05e59d40533074fe719b0841d542288500fd6d01.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/b0e17363aa1ed2b0f4227eca05e59d40533074fe719b0841d542288500fd6d01.jpg)

![bb44d3bc82db7f06c13b3c850c88f4e95044353c2af1126e66b93a6fd3bdd992.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/bb44d3bc82db7f06c13b3c850c88f4e95044353c2af1126e66b93a6fd3bdd992.jpg)

![d80fc76f3434fdf54ce2557ca3fabb637f534a7f2c9aedbaadf2828a2a7a01b0.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/d80fc76f3434fdf54ce2557ca3fabb637f534a7f2c9aedbaadf2828a2a7a01b0.jpg)

![df363dcafcbdbe04618180658c65a665f9b20a3c6039143c172c85fea993afe2.jpg](../nips_results/1709_Training-Free%20Guidance%20Beyond%20Differentiability_%20Scalable%20Path%20Steering%20with%20Tree%20Search%20in%20Diffusio/tables/df363dcafcbdbe04618180658c65a665f9b20a3c6039143c172c85fea993afe2.jpg)

## On Hierarchies of Fairness Notions in Cake Cutting: From Proportionality to Super Envy-Freeness


### Images

![5963b2b649dd1a1c8d6553d4d3772e7ed42be4254054a8f808d43724da8017ef.jpg](../nips_results/1710_On%20Hierarchies%20of%20Fairness%20Notions%20in%20Cake%20Cutting_%20From%20Proportionality%20to%20Super%20Envy-Freeness/images/5963b2b649dd1a1c8d6553d4d3772e7ed42be4254054a8f808d43724da8017ef.jpg)

## Frame In-N-Out: Unbounded Controllable Image-to-Video Generation


### Images

![014e76836e61447893f7f94e9365e3c4d3095b367ab00d54f588844f453f8176.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/014e76836e61447893f7f94e9365e3c4d3095b367ab00d54f588844f453f8176.jpg)

![0cc6895481260f17cc0b5f7aef6d1e53f78ce7df061980d3c9bc015013c0d989.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/0cc6895481260f17cc0b5f7aef6d1e53f78ce7df061980d3c9bc015013c0d989.jpg)

![1528fca7e734bae37cb5db80a4dff854b67503c1bd9ae5cac859c68cb0ff4afb.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/1528fca7e734bae37cb5db80a4dff854b67503c1bd9ae5cac859c68cb0ff4afb.jpg)

![186f27ded928ab732429985472e6467de149982a0acfce848308d74d2143000e.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/186f27ded928ab732429985472e6467de149982a0acfce848308d74d2143000e.jpg)

![1be72100429a311f9d44c3c994eee9c3992f140b55293abdf6a7921ac375bcb0.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/1be72100429a311f9d44c3c994eee9c3992f140b55293abdf6a7921ac375bcb0.jpg)

![218d24ba75d1acd57f506a567e6545c7b37a9c681aeab3c905710a51cfb1a902.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/218d24ba75d1acd57f506a567e6545c7b37a9c681aeab3c905710a51cfb1a902.jpg)

![21cdcb157dc977e88586676bd7a17287ebdaeb608a5a5f40c511e00a640bff8b.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/21cdcb157dc977e88586676bd7a17287ebdaeb608a5a5f40c511e00a640bff8b.jpg)

![2bd1c6d4f0bc3680b0c306fe14244def88fbdcb86b37a8de23f052a9f024bc9b.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/2bd1c6d4f0bc3680b0c306fe14244def88fbdcb86b37a8de23f052a9f024bc9b.jpg)

![2f0c61b63d6417d1a2ebf8eee1a584fc3aab7d5b48308704e97ab822349871fb.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/2f0c61b63d6417d1a2ebf8eee1a584fc3aab7d5b48308704e97ab822349871fb.jpg)

![2feb8671f91e5bc0c54774f27238936a9e21257347d37aff1c7ab73b7a9e718b.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/2feb8671f91e5bc0c54774f27238936a9e21257347d37aff1c7ab73b7a9e718b.jpg)

![34c467e0f925ade51a4b899834d86e64a41802935645e8c4d8b5669ac6329476.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/34c467e0f925ade51a4b899834d86e64a41802935645e8c4d8b5669ac6329476.jpg)

![505803a1e96473aa44c72fdfc293fe0cf6ef0d6579adae6d71579204a71f18eb.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/505803a1e96473aa44c72fdfc293fe0cf6ef0d6579adae6d71579204a71f18eb.jpg)

![50f84d59f64201e743abb1cd497716cc85fb5289770311f9608b8c28d3fec8d3.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/50f84d59f64201e743abb1cd497716cc85fb5289770311f9608b8c28d3fec8d3.jpg)

![58630ee074433014ae45796438919fa47eaf3ee472538a46b64222bf0b5d5fb0.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/58630ee074433014ae45796438919fa47eaf3ee472538a46b64222bf0b5d5fb0.jpg)

![5e15277a19ac7b01be22e1b49a96b5f6e69a5570a75e2f33902d1a8195ac8a04.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/5e15277a19ac7b01be22e1b49a96b5f6e69a5570a75e2f33902d1a8195ac8a04.jpg)

![5f5945e37b6eb9af042e17051440dc4253adfebf6ccdb10d7a8b38ded57ebe2e.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/5f5945e37b6eb9af042e17051440dc4253adfebf6ccdb10d7a8b38ded57ebe2e.jpg)

![761f15cde48037db9a01eb54f217071a9b6db720799d5d26ba5e58b79318a7bc.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/761f15cde48037db9a01eb54f217071a9b6db720799d5d26ba5e58b79318a7bc.jpg)

![81e6ae09cd391cc0dc2d60837cf93172979a8f354abbe07ff0ae7b0fd2155737.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/81e6ae09cd391cc0dc2d60837cf93172979a8f354abbe07ff0ae7b0fd2155737.jpg)

![8b000dc9ed7d7aeb7c745a64fa4a6ed43df456ae9d0aa003080bf7b7537ebb39.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/8b000dc9ed7d7aeb7c745a64fa4a6ed43df456ae9d0aa003080bf7b7537ebb39.jpg)

![8d094fef790273f07049b68a0687144ffde454935a5b7e8d6db71eaa6edb7c44.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/8d094fef790273f07049b68a0687144ffde454935a5b7e8d6db71eaa6edb7c44.jpg)

![a26291d997f4d6563f52e7baa38e82ee6a4fcaf15bdca892456554a2b7bf5ede.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/a26291d997f4d6563f52e7baa38e82ee6a4fcaf15bdca892456554a2b7bf5ede.jpg)

![a5c8ac13510d4125b60d968e15f5c97968c354e89bbcc9b51500110f23a63151.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/a5c8ac13510d4125b60d968e15f5c97968c354e89bbcc9b51500110f23a63151.jpg)

![b0a3cfbbf681a25160d809bb29b2c24a29e93c145df60cba7ffa97dadbfd5eaa.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/b0a3cfbbf681a25160d809bb29b2c24a29e93c145df60cba7ffa97dadbfd5eaa.jpg)

![b19574352bed6442f4d9d47d35056b0524c714fa174d8cdfcfc99ccc48adc630.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/b19574352bed6442f4d9d47d35056b0524c714fa174d8cdfcfc99ccc48adc630.jpg)

![bbd2106e063e5e7ba58b2561266b1e17c5beb5771cfcba39bd49722c8e7fc55d.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/bbd2106e063e5e7ba58b2561266b1e17c5beb5771cfcba39bd49722c8e7fc55d.jpg)

![c2005007b6f808796dc85f571ebface89090c8c791d360bfb1ea5e300320458b.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/c2005007b6f808796dc85f571ebface89090c8c791d360bfb1ea5e300320458b.jpg)

![d0d4f0f43f85e19a8aa85bcb9759874c20d3fe7faa0edee256735f92597cf070.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/d0d4f0f43f85e19a8aa85bcb9759874c20d3fe7faa0edee256735f92597cf070.jpg)

![f8ff32a851fb23d07963db3716954a9c44cb0badef05aba2ac8631e0b6e27736.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/images/f8ff32a851fb23d07963db3716954a9c44cb0badef05aba2ac8631e0b6e27736.jpg)

### Tables

![1719e164ff72eb017fab80800f829610331231b5783e0e31a4a34d67d2758abf.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/tables/1719e164ff72eb017fab80800f829610331231b5783e0e31a4a34d67d2758abf.jpg)

![230a9a4262dc4624a9bc49698a53bf7d2cabc9462718c89bfa968def8e494508.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/tables/230a9a4262dc4624a9bc49698a53bf7d2cabc9462718c89bfa968def8e494508.jpg)

![b88a20c4f68e51ad3ac198853dff9df78eb452b1f5fd0da1e71d1c9ece2e43fd.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/tables/b88a20c4f68e51ad3ac198853dff9df78eb452b1f5fd0da1e71d1c9ece2e43fd.jpg)

![d39fcde92c00fff83ad59d7e1b519a06c23cb56b440b70f3e85496bacf78c6b9.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/tables/d39fcde92c00fff83ad59d7e1b519a06c23cb56b440b70f3e85496bacf78c6b9.jpg)

![deaaea39d2c948ae9b2b5faf31065b32f62b6b6e3254577b79df592127014114.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/tables/deaaea39d2c948ae9b2b5faf31065b32f62b6b6e3254577b79df592127014114.jpg)

![f5d6f0b829e226b0825e5cb586519332b6c75d88dadd6522c5b80c792c45c160.jpg](../nips_results/1711_Frame%20In-N-Out_%20Unbounded%20Controllable%20Image-to-Video%20Generation/tables/f5d6f0b829e226b0825e5cb586519332b6c75d88dadd6522c5b80c792c45c160.jpg)

## Efficiently Scaling LLM Reasoning Programs with Certaindex


### Images

![039d26c7a34b07236bc61d242a67274cf6f747e599913fbc7132d5973d493d5a.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/039d26c7a34b07236bc61d242a67274cf6f747e599913fbc7132d5973d493d5a.jpg)

![0e794c54e73ce670557b6a6911d2b97bd5215b72c346a8657023421cd4803b16.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/0e794c54e73ce670557b6a6911d2b97bd5215b72c346a8657023421cd4803b16.jpg)

![1049ee9cb4e9d1ba80cb382da7d0ca0a112ef100ed0c47ec9be88f1e3860a6a0.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/1049ee9cb4e9d1ba80cb382da7d0ca0a112ef100ed0c47ec9be88f1e3860a6a0.jpg)

![1dc2ed8ecf776bfa8f86e4235c0a65c3eb08d10993e62e5e590da97bcee217bb.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/1dc2ed8ecf776bfa8f86e4235c0a65c3eb08d10993e62e5e590da97bcee217bb.jpg)

![266512c6a58e37579a40a8fa33cac471a53e80128e7f8261033480a90291cdb2.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/266512c6a58e37579a40a8fa33cac471a53e80128e7f8261033480a90291cdb2.jpg)

![26750d70995d8832ed0475142e279f7283acdf3b969f6773df803cdb607645a0.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/26750d70995d8832ed0475142e279f7283acdf3b969f6773df803cdb607645a0.jpg)

![362e4bcf2d5ed19415f969382e61e4d2954f7abad6ded7fdb39057bcc8f36bc6.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/362e4bcf2d5ed19415f969382e61e4d2954f7abad6ded7fdb39057bcc8f36bc6.jpg)

![42e3497bca7b0bf4be26adc07b4229ca026786ccb7ce088d0bafe5a4978f9444.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/42e3497bca7b0bf4be26adc07b4229ca026786ccb7ce088d0bafe5a4978f9444.jpg)

![6dc2e2b97c49195ab4d0ca924af0453bbae45402a9b19a273c49b285b3d1f254.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/6dc2e2b97c49195ab4d0ca924af0453bbae45402a9b19a273c49b285b3d1f254.jpg)

![769b6dec0b400bb72ee69d4b2a18adb7f8d8d252eb1d63c437c7e01a06a7178d.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/769b6dec0b400bb72ee69d4b2a18adb7f8d8d252eb1d63c437c7e01a06a7178d.jpg)

![7dabc056c10bbde7d82e57773daac346dabe3c7064d9769663c2fcf51a378a96.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/7dabc056c10bbde7d82e57773daac346dabe3c7064d9769663c2fcf51a378a96.jpg)

![9b6275b847c444421f804c65d02509eeec9c287827a39543268b065032df0efe.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/9b6275b847c444421f804c65d02509eeec9c287827a39543268b065032df0efe.jpg)

![a479ed67b85bd5e3a7e7148780d87e15a01ed653cfb83bb231b7d7331585f5b4.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/a479ed67b85bd5e3a7e7148780d87e15a01ed653cfb83bb231b7d7331585f5b4.jpg)

![af47b1ec9deddea18c92f1ef767f1ecfbd3e906de6e2653d1da963c9e81542a1.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/af47b1ec9deddea18c92f1ef767f1ecfbd3e906de6e2653d1da963c9e81542a1.jpg)

![b7be5ed9dbdbca485007c5f12209d4e1ebad813c7dd7e3033726658d744db076.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/b7be5ed9dbdbca485007c5f12209d4e1ebad813c7dd7e3033726658d744db076.jpg)

![ce94eb070f06307fcebf457790816ff5b6a0cfb1514ea9b5a672b0fffb6d2f7d.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/ce94eb070f06307fcebf457790816ff5b6a0cfb1514ea9b5a672b0fffb6d2f7d.jpg)

![da57317164fc044b56c10e4d26933f267f55bf092a898f12ab281cb6846f6566.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/da57317164fc044b56c10e4d26933f267f55bf092a898f12ab281cb6846f6566.jpg)

![e83f731ee7397cec402efed7b075a49530572e6b9b5f058dff65e33b7e0a7540.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/e83f731ee7397cec402efed7b075a49530572e6b9b5f058dff65e33b7e0a7540.jpg)

![f1a9d12fed2416f6600c8239b97e930f5bffbbd61545ac42d9ab72787c9ec9c1.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/f1a9d12fed2416f6600c8239b97e930f5bffbbd61545ac42d9ab72787c9ec9c1.jpg)

![fb31865ae68d91f60631cc3301d02934e0e6b0d4a52ab9a71e3b90ca8c030414.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/fb31865ae68d91f60631cc3301d02934e0e6b0d4a52ab9a71e3b90ca8c030414.jpg)

![ffad0bb4b5c5791cd7e0067be54a6aeb6e586dfc5a5cfd40a95c4b70db2d9e97.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/images/ffad0bb4b5c5791cd7e0067be54a6aeb6e586dfc5a5cfd40a95c4b70db2d9e97.jpg)

### Tables

![1ba2d90c518d503497de83a01d602e427c9de027abd1915bb861d357df0ec97a.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/tables/1ba2d90c518d503497de83a01d602e427c9de027abd1915bb861d357df0ec97a.jpg)

![3030077ea0ef9d48ce221d87002b4c764027778d9a0c9ea72f854e8bb8e16c5a.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/tables/3030077ea0ef9d48ce221d87002b4c764027778d9a0c9ea72f854e8bb8e16c5a.jpg)

![6b15416a209083e17bbdff8ea34495d1c48d86d2aae6e320ae1f3b5b986d470a.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/tables/6b15416a209083e17bbdff8ea34495d1c48d86d2aae6e320ae1f3b5b986d470a.jpg)

![87bbb6cba6700c88ee3e16cd85c976054ac99b830158b73a563ce951ae91c8df.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/tables/87bbb6cba6700c88ee3e16cd85c976054ac99b830158b73a563ce951ae91c8df.jpg)

![a571c7901f3add75018e383f92da5094179bb0bf159066a3005e0b182dadeee9.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/tables/a571c7901f3add75018e383f92da5094179bb0bf159066a3005e0b182dadeee9.jpg)

![abe467505ed22c353cee4a4329acce0394387b7a3256eb02394984f61d1375df.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/tables/abe467505ed22c353cee4a4329acce0394387b7a3256eb02394984f61d1375df.jpg)

![cdc0fbabbe8f357a8d14b2588bb29e6023b9b952df40a2c1728a2e9d0d97b79c.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/tables/cdc0fbabbe8f357a8d14b2588bb29e6023b9b952df40a2c1728a2e9d0d97b79c.jpg)

![ef1a23c076876877312a7db83031cf3ba9b58f24dd3a75c2776d51c9642e5988.jpg](../nips_results/1712_Efficiently%20Scaling%20LLM%20Reasoning%20Programs%20with%20Certaindex/tables/ef1a23c076876877312a7db83031cf3ba9b58f24dd3a75c2776d51c9642e5988.jpg)

## G-Net: A Provably Easy Construction of High-Accuracy Random Binary Neural Networks


### Images

![105286d9084e32b4b9e1e72e48ee6e7f44ca8315d4097cdc28d228f688a17a72.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/images/105286d9084e32b4b9e1e72e48ee6e7f44ca8315d4097cdc28d228f688a17a72.jpg)

![26b3027750b0374ac2cef1275a434374d014c1198ad842b41739bcf87285aa37.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/images/26b3027750b0374ac2cef1275a434374d014c1198ad842b41739bcf87285aa37.jpg)

![2c278865a383b9addbe2348a8d41165c9d9994c2431acc7036f620334f148eed.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/images/2c278865a383b9addbe2348a8d41165c9d9994c2431acc7036f620334f148eed.jpg)

![316fe569f97c38994ed9bd13be61f2443ae2954bdf72f45f49552dee8cece782.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/images/316fe569f97c38994ed9bd13be61f2443ae2954bdf72f45f49552dee8cece782.jpg)

![4eb6e4badd1f265fc477a2ecafaa616c6b012f9732703eaefb21bf6242f7a8a3.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/images/4eb6e4badd1f265fc477a2ecafaa616c6b012f9732703eaefb21bf6242f7a8a3.jpg)

![55181159feca11c3d460d1980ca9a610b39de9e512def4263a373120b00231e2.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/images/55181159feca11c3d460d1980ca9a610b39de9e512def4263a373120b00231e2.jpg)

![669f68a6c68efde19083928d782b7948d89a557bb1d6637aacf0022182da5d27.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/images/669f68a6c68efde19083928d782b7948d89a557bb1d6637aacf0022182da5d27.jpg)

![7b62b60f5d50e4a3895621e8c63be07fc212ddda3384b8daa3fa7e088dee005f.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/images/7b62b60f5d50e4a3895621e8c63be07fc212ddda3384b8daa3fa7e088dee005f.jpg)

![b8e131a69496132a79a25d901f51e6d8fad5329460e72b039ad8b3daaed68ac8.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/images/b8e131a69496132a79a25d901f51e6d8fad5329460e72b039ad8b3daaed68ac8.jpg)

![c718d83ebe72d57a577dbb537a29848cc83427e5cb3e2f31d6b79a44948c79ed.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/images/c718d83ebe72d57a577dbb537a29848cc83427e5cb3e2f31d6b79a44948c79ed.jpg)

![f47f2c8636fc4275b906c7c6a2b7a8df13ddba70c14deeaa0459688080ff7a8b.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/images/f47f2c8636fc4275b906c7c6a2b7a8df13ddba70c14deeaa0459688080ff7a8b.jpg)

### Tables

![412ee1018ca7f992b24b541622a52b6172d541f732bb66c8032cccec2940ff6d.jpg](../nips_results/1713_G-Net_%20A%20Provably%20Easy%20Construction%20of%20High-Accuracy%20Random%20Binary%20Neural%20Networks/tables/412ee1018ca7f992b24b541622a52b6172d541f732bb66c8032cccec2940ff6d.jpg)

## STNet: Spectral Transformation Network for Solving Operator Eigenvalue Problem


### Images

![428ea44d5ac0f93565e0013e2b1fc7552e24a4126369ee0fc84dadebdb51c8a0.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/images/428ea44d5ac0f93565e0013e2b1fc7552e24a4126369ee0fc84dadebdb51c8a0.jpg)

![a4e9f9b2deb4b220701cfaa0a3cf1ccfdda70335b423af3baf97872344c0711e.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/images/a4e9f9b2deb4b220701cfaa0a3cf1ccfdda70335b423af3baf97872344c0711e.jpg)

![ea969a3adc472e241a6dfc0f6d1d3cb04824440a013d826a1518b59f55bdecaa.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/images/ea969a3adc472e241a6dfc0f6d1d3cb04824440a013d826a1518b59f55bdecaa.jpg)

### Tables

![050a731972383e76d84a193b6ac538c66feacc1580c75904858b1b1e551178f9.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/050a731972383e76d84a193b6ac538c66feacc1580c75904858b1b1e551178f9.jpg)

![4d85c341a22c8b793c76e06b2812158e0ed5e6dc02051f78786dbb090fffbf02.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/4d85c341a22c8b793c76e06b2812158e0ed5e6dc02051f78786dbb090fffbf02.jpg)

![5419f79b76021da6a380abb4ab2798c9ac05ca3312004d34b8b0577413da8cbf.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/5419f79b76021da6a380abb4ab2798c9ac05ca3312004d34b8b0577413da8cbf.jpg)

![54d88e460ce336761fc010ca52e5155c0df8ed152ddaf8e1627cabeb711cf618.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/54d88e460ce336761fc010ca52e5155c0df8ed152ddaf8e1627cabeb711cf618.jpg)

![5dc3e3ae25d6f79c25ed4c17aba1c856437d080038cbf98f3fa1fc79ca544c43.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/5dc3e3ae25d6f79c25ed4c17aba1c856437d080038cbf98f3fa1fc79ca544c43.jpg)

![73ba7a8d9cf8da359277d3186735485822adfb344a09aceb50902863b29565df.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/73ba7a8d9cf8da359277d3186735485822adfb344a09aceb50902863b29565df.jpg)

![78ccee940380689e0cc1942364fad3c5a3e6a1add6fbbdc83ac069a27356d6dc.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/78ccee940380689e0cc1942364fad3c5a3e6a1add6fbbdc83ac069a27356d6dc.jpg)

![7e9026f75fddf219a2bdc5f53d273ee707fa8bb4a23d6bd5ccfc78069dddf92d.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/7e9026f75fddf219a2bdc5f53d273ee707fa8bb4a23d6bd5ccfc78069dddf92d.jpg)

![84b6c7d3236259f9803fce3d532e5bdeb06eda9bdd8b0291378b67098a396bf7.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/84b6c7d3236259f9803fce3d532e5bdeb06eda9bdd8b0291378b67098a396bf7.jpg)

![bb3b8f8dcd118e03e5aa7460e480c8ab14e67cb2c86f433b84d06a571a62ac12.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/bb3b8f8dcd118e03e5aa7460e480c8ab14e67cb2c86f433b84d06a571a62ac12.jpg)

![e4d465d4866e1d08b334899a11a1efb9960c87f972c07bed1a7259e5a36d1b82.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/e4d465d4866e1d08b334899a11a1efb9960c87f972c07bed1a7259e5a36d1b82.jpg)

![e5c65ceb24aebb557994dce209cf310951467e3b7767f6c42188512f2dbfcabc.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/e5c65ceb24aebb557994dce209cf310951467e3b7767f6c42188512f2dbfcabc.jpg)

![e6a750c5435111587eb392bc652f7924455f270ec813c17be640380b7fecdd12.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/e6a750c5435111587eb392bc652f7924455f270ec813c17be640380b7fecdd12.jpg)

![f31ae77d811a273daec12f7eacf29cb788de45e6fc11cf4068549107267dd6ae.jpg](../nips_results/1714_STNet_%20Spectral%20Transformation%20Network%20for%20Solving%20Operator%20Eigenvalue%20Problem/tables/f31ae77d811a273daec12f7eacf29cb788de45e6fc11cf4068549107267dd6ae.jpg)

## Imbalances in Neurosymbolic Learning: Characterization and Mitigating Strategies


### Images

![09473de8e12da5f2a2c7f7f22f05cac24008ef6346442c1ac7a171e7171e7c31.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/images/09473de8e12da5f2a2c7f7f22f05cac24008ef6346442c1ac7a171e7171e7c31.jpg)

![0b6faa1cb165b912eed555026514ffeedd91bc5034966f70f2cd5854d8aa68f7.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/images/0b6faa1cb165b912eed555026514ffeedd91bc5034966f70f2cd5854d8aa68f7.jpg)

![14ac8620e52210abcd63278db62e9ea7705143f1dbedb6de3ce06fd7084e259a.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/images/14ac8620e52210abcd63278db62e9ea7705143f1dbedb6de3ce06fd7084e259a.jpg)

![97ae1b5e3672815939534a60cfd208ea7024f63c3880e8431a2a6f1e266c6685.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/images/97ae1b5e3672815939534a60cfd208ea7024f63c3880e8431a2a6f1e266c6685.jpg)

![bf7273e64231439614561fc3760163d6fef54c18b06e4405e9277f4dbf62215e.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/images/bf7273e64231439614561fc3760163d6fef54c18b06e4405e9277f4dbf62215e.jpg)

![c3c2d05ecb22d32d97e668f15bfc0bbd74d49ea9426c8970e797460c31deea30.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/images/c3c2d05ecb22d32d97e668f15bfc0bbd74d49ea9426c8970e797460c31deea30.jpg)

![d3a12b2b0ad99dea6dfea502a805d4b591dc3ae9c0b18525aa93c88f661860fd.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/images/d3a12b2b0ad99dea6dfea502a805d4b591dc3ae9c0b18525aa93c88f661860fd.jpg)

![e2ec37581bb8649721f78ad1bd718a73ca12d00ff9aebdaf97a9f4332fd4cb0c.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/images/e2ec37581bb8649721f78ad1bd718a73ca12d00ff9aebdaf97a9f4332fd4cb0c.jpg)

![fdbea97cc21ffe6c998b0ff8c8bcdc1e49b0b53c385eb629aabec10b92de816b.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/images/fdbea97cc21ffe6c998b0ff8c8bcdc1e49b0b53c385eb629aabec10b92de816b.jpg)

### Tables

![2fb182f1b9553f27e686fbebc4a17af71de17a16c3e43b608f5cf430c4bf9b8b.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/tables/2fb182f1b9553f27e686fbebc4a17af71de17a16c3e43b608f5cf430c4bf9b8b.jpg)

![3358a368cb23373eff2b4d3a87f135dc1302f09f43295e6cf48e7de9734768f7.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/tables/3358a368cb23373eff2b4d3a87f135dc1302f09f43295e6cf48e7de9734768f7.jpg)

![366244d060e8d4b59cb563e5d4b23cf2bb5015d1d5690c4ba983a0cc704980bd.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/tables/366244d060e8d4b59cb563e5d4b23cf2bb5015d1d5690c4ba983a0cc704980bd.jpg)

![3da0f09800826274336336fb59ee3f97abc03a3a6b67d421afd0a8f6bd93abd7.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/tables/3da0f09800826274336336fb59ee3f97abc03a3a6b67d421afd0a8f6bd93abd7.jpg)

![4abd672909d32fdb7548c864084b0fe9eab8dc5ddc0741285ec5b934e7ce7345.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/tables/4abd672909d32fdb7548c864084b0fe9eab8dc5ddc0741285ec5b934e7ce7345.jpg)

![764fc493f579447a9836919fcf4b1b00b340f86f113d728e6b6bfae168617dd6.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/tables/764fc493f579447a9836919fcf4b1b00b340f86f113d728e6b6bfae168617dd6.jpg)

![8d6b6f6a4e2dcbddd7ed8f680d35549c09ed41e66565aaecf7622331510b6250.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/tables/8d6b6f6a4e2dcbddd7ed8f680d35549c09ed41e66565aaecf7622331510b6250.jpg)

![f32b5e995f88578e63bece6d53ebdec33b893fbeaf701669e94eed6aa4118d86.jpg](../nips_results/1715_Imbalances%20in%20Neurosymbolic%20Learning_%20Characterization%20and%20Mitigating%20Strategies/tables/f32b5e995f88578e63bece6d53ebdec33b893fbeaf701669e94eed6aa4118d86.jpg)

## An Effective Levelling Paradigm for Unlabeled Scenarios


### Images

![61b10ff8596d3f3546b86fed64c00aec0026e1d92cda9191a188748c049d2569.jpg](../nips_results/1716_An%20Effective%20Levelling%20Paradigm%20for%20Unlabeled%20Scenarios/images/61b10ff8596d3f3546b86fed64c00aec0026e1d92cda9191a188748c049d2569.jpg)

![f83d8de7d6ee1bf7780b423b63d44e6c02567e2a13ff62045a25b3b78fb1a439.jpg](../nips_results/1716_An%20Effective%20Levelling%20Paradigm%20for%20Unlabeled%20Scenarios/images/f83d8de7d6ee1bf7780b423b63d44e6c02567e2a13ff62045a25b3b78fb1a439.jpg)

### Tables

![01b087df533e630fee7c778ce25d9121f6c6084f28b9ef6d9582a6791a7d7fde.jpg](../nips_results/1716_An%20Effective%20Levelling%20Paradigm%20for%20Unlabeled%20Scenarios/tables/01b087df533e630fee7c778ce25d9121f6c6084f28b9ef6d9582a6791a7d7fde.jpg)

![0337caf7873ebd34af3f6f23b3e97b48a9a7bc6e4bf72f571cb74df74662e0ce.jpg](../nips_results/1716_An%20Effective%20Levelling%20Paradigm%20for%20Unlabeled%20Scenarios/tables/0337caf7873ebd34af3f6f23b3e97b48a9a7bc6e4bf72f571cb74df74662e0ce.jpg)

![196fdb2ca7373f7beecbe91e2c635d54222786355f92eaf6c307b15b95a97347.jpg](../nips_results/1716_An%20Effective%20Levelling%20Paradigm%20for%20Unlabeled%20Scenarios/tables/196fdb2ca7373f7beecbe91e2c635d54222786355f92eaf6c307b15b95a97347.jpg)

![4b05047ad176d95dc44433dfabffa0dc336b00e881fbaae50be834d5a7cb43d6.jpg](../nips_results/1716_An%20Effective%20Levelling%20Paradigm%20for%20Unlabeled%20Scenarios/tables/4b05047ad176d95dc44433dfabffa0dc336b00e881fbaae50be834d5a7cb43d6.jpg)

![9f107031694bd0afc72fe963ed63ac24ca2fc6cbdce5bbf1ce20ae89656fbd40.jpg](../nips_results/1716_An%20Effective%20Levelling%20Paradigm%20for%20Unlabeled%20Scenarios/tables/9f107031694bd0afc72fe963ed63ac24ca2fc6cbdce5bbf1ce20ae89656fbd40.jpg)

![d510ff3d6d73d8958f4499bec452ed244fc21f865f9a49e1a49fedecb8453332.jpg](../nips_results/1716_An%20Effective%20Levelling%20Paradigm%20for%20Unlabeled%20Scenarios/tables/d510ff3d6d73d8958f4499bec452ed244fc21f865f9a49e1a49fedecb8453332.jpg)

![f4afc4b35a9b2c1a2cc5bf9d236d77e79dcb6028ae72ab21d880734b384bc55b.jpg](../nips_results/1716_An%20Effective%20Levelling%20Paradigm%20for%20Unlabeled%20Scenarios/tables/f4afc4b35a9b2c1a2cc5bf9d236d77e79dcb6028ae72ab21d880734b384bc55b.jpg)

## Truth over Tricks: Measuring and Mitigating Shortcut Learning in Misinformation Detection


### Images

![133c1881ec429e06da10e128f44e826e6b8b4edc518bc6e07eda1fab6d64a0eb.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/133c1881ec429e06da10e128f44e826e6b8b4edc518bc6e07eda1fab6d64a0eb.jpg)

![3238acf26f9d32109fae31a1981fee1278c12cd35fa890a47d3b137f340d5516.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/3238acf26f9d32109fae31a1981fee1278c12cd35fa890a47d3b137f340d5516.jpg)

![34944935b640ecd22942457e9f20ef2b7e3fdb971156f9880643a048cef099f5.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/34944935b640ecd22942457e9f20ef2b7e3fdb971156f9880643a048cef099f5.jpg)

![36ba418952b409493a74b0dc74ade14ce8c1133c80e2f1189eb96e016570b94e.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/36ba418952b409493a74b0dc74ade14ce8c1133c80e2f1189eb96e016570b94e.jpg)

![5827ac51e8dd48d1e281a0590a0f6cdd75d32c678d134c7609a78e75a1972944.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/5827ac51e8dd48d1e281a0590a0f6cdd75d32c678d134c7609a78e75a1972944.jpg)

![61bc1f3d38cf73d25beecbcc621a402d91af897a6b193aa078b6a2db9900f36e.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/61bc1f3d38cf73d25beecbcc621a402d91af897a6b193aa078b6a2db9900f36e.jpg)

![667323cc59b6c662c8d6ec6d13c2a6166d74041239167a1d8b5b647dce5c2526.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/667323cc59b6c662c8d6ec6d13c2a6166d74041239167a1d8b5b647dce5c2526.jpg)

![81003ff1cc3e3373ab944ccca06101a45dad6f9d1d65083cba2c596a939a8cee.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/81003ff1cc3e3373ab944ccca06101a45dad6f9d1d65083cba2c596a939a8cee.jpg)

![8ac59f3a3017874ab8b89fa4b7975b02093423669d311bbfeef62ba45fd62db5.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/8ac59f3a3017874ab8b89fa4b7975b02093423669d311bbfeef62ba45fd62db5.jpg)

![ab68ca9a1385032bebcef35117e5f5ad8c24cd708fab43b2ad794615f5362d3c.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/ab68ca9a1385032bebcef35117e5f5ad8c24cd708fab43b2ad794615f5362d3c.jpg)

![bfe845af172e2e2cb365190f36cd0c6e66b2ddac3477ef6ae268cadb1cf452dc.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/bfe845af172e2e2cb365190f36cd0c6e66b2ddac3477ef6ae268cadb1cf452dc.jpg)

![c1587ca098461abc48f2e55c848b845693dc8ad59bcd8719136fc304daeb75c6.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/c1587ca098461abc48f2e55c848b845693dc8ad59bcd8719136fc304daeb75c6.jpg)

![d47dd31733d8eb241f276b09805114815353229d58e8554682e127d995d94528.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/d47dd31733d8eb241f276b09805114815353229d58e8554682e127d995d94528.jpg)

![f5eeefa7ef71c5bed5f2d930763b94c9682eac4c76f221d1ef090ee91e96601e.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/f5eeefa7ef71c5bed5f2d930763b94c9682eac4c76f221d1ef090ee91e96601e.jpg)

![fb2a8b687724764c07ceb470c4b12590fe945bad49bac3464a2a39a953fbed9d.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/images/fb2a8b687724764c07ceb470c4b12590fe945bad49bac3464a2a39a953fbed9d.jpg)

### Tables

![00a265ef10c93a9ff1a52cd6abb53e3c4f947364c8d0d2cc3f61f1e4e7ddeb76.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/00a265ef10c93a9ff1a52cd6abb53e3c4f947364c8d0d2cc3f61f1e4e7ddeb76.jpg)

![019340a08dd191c05af9713e804a673e5479921fc840892828e107baa3da0d4c.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/019340a08dd191c05af9713e804a673e5479921fc840892828e107baa3da0d4c.jpg)

![091b4acf727d91250e6ccaac023f90958a9658b86120aed4a6d71f932987222f.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/091b4acf727d91250e6ccaac023f90958a9658b86120aed4a6d71f932987222f.jpg)

![192c39345380e0491fc9c311368e31d75743a90ff1ce336be657a867e3213346.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/192c39345380e0491fc9c311368e31d75743a90ff1ce336be657a867e3213346.jpg)

![1bc4e47002628f1ae0cd78b352e39939176d15f634c8be7ae06c51b96ce9891d.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/1bc4e47002628f1ae0cd78b352e39939176d15f634c8be7ae06c51b96ce9891d.jpg)

![1fe75a88157732f54f9b40a4ae882e8116856a18540e15d3bb3f5ed2b15977c2.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/1fe75a88157732f54f9b40a4ae882e8116856a18540e15d3bb3f5ed2b15977c2.jpg)

![224b50d3f205002ab05fbcd10b8152722192ffbe2b1d98a40b8f23f12d2fe713.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/224b50d3f205002ab05fbcd10b8152722192ffbe2b1d98a40b8f23f12d2fe713.jpg)

![278408cc36123ad0ec6e169fea9b1f3d8a707d23b89e8997aa608bcf504ac639.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/278408cc36123ad0ec6e169fea9b1f3d8a707d23b89e8997aa608bcf504ac639.jpg)

![2da6eb677223ab66ab1f2d9a00210791f5b68a5fc327621bdc9b9b474c8e97fc.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/2da6eb677223ab66ab1f2d9a00210791f5b68a5fc327621bdc9b9b474c8e97fc.jpg)

![347f006cfbc817e1688fcf7c082025f735dc723e02c055b4dff62cde8a1b29a2.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/347f006cfbc817e1688fcf7c082025f735dc723e02c055b4dff62cde8a1b29a2.jpg)

![3de164d7374fda49f43ee3237e983d5d648eaa026db4a5b848e51a265667593b.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/3de164d7374fda49f43ee3237e983d5d648eaa026db4a5b848e51a265667593b.jpg)

![463f6f7cee16292e8910591f46dfffa49523355a0a4f9076d1821d7e5aea2786.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/463f6f7cee16292e8910591f46dfffa49523355a0a4f9076d1821d7e5aea2786.jpg)

![515846b07a865a3d035a450d252acaa5f3a1df8323c5c7275a8b6c252480255c.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/515846b07a865a3d035a450d252acaa5f3a1df8323c5c7275a8b6c252480255c.jpg)

![586c129b5144b147ea9c65df7b2e7568c6b8af89d7b028b8dd7f724eea37a3da.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/586c129b5144b147ea9c65df7b2e7568c6b8af89d7b028b8dd7f724eea37a3da.jpg)

![5b2bedc549445d031b75faacabd7ab146a1bf86a12e8788e59e3fb8f09647d7f.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/5b2bedc549445d031b75faacabd7ab146a1bf86a12e8788e59e3fb8f09647d7f.jpg)

![80052ce295eb6cf5ad3a7570259b1def51f21fd9f513ec54ae860c6066d6b773.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/80052ce295eb6cf5ad3a7570259b1def51f21fd9f513ec54ae860c6066d6b773.jpg)

![8fee3e569980684693ab8e90cbee8d90794e986c3e5810f7b178b7100e07ba3f.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/8fee3e569980684693ab8e90cbee8d90794e986c3e5810f7b178b7100e07ba3f.jpg)

![91b2dee8d15259cd6ca1de0c7877fb2320a43459e245cae20ab5ec446f90a6f1.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/91b2dee8d15259cd6ca1de0c7877fb2320a43459e245cae20ab5ec446f90a6f1.jpg)

![96ad66c685f29d43e8fb81f305b60a8e03083dea990f84b692084f489652d64f.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/96ad66c685f29d43e8fb81f305b60a8e03083dea990f84b692084f489652d64f.jpg)

![9dc3b91498aa6c385caaa3ae84b804fe4e9b756835e60c589f86386fe09496ec.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/9dc3b91498aa6c385caaa3ae84b804fe4e9b756835e60c589f86386fe09496ec.jpg)

![c3c770baec75fb2be217fa14ecd59daf93896610c6bd048120fc280c3bc66c4a.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/c3c770baec75fb2be217fa14ecd59daf93896610c6bd048120fc280c3bc66c4a.jpg)

![d0610f30f33cd43f4d951294f0b775d0069917d97bf4c294faf2058f3d0599dc.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/d0610f30f33cd43f4d951294f0b775d0069917d97bf4c294faf2058f3d0599dc.jpg)

![dda0941f1e4801b4ab543e04406dff0cb378abf69a96be59b7bfbaaae0847384.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/dda0941f1e4801b4ab543e04406dff0cb378abf69a96be59b7bfbaaae0847384.jpg)

![df5cd3966ae682cf56327e9e8197840acef56b4ed4a35bcb191ad49efa77ad3f.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/df5cd3966ae682cf56327e9e8197840acef56b4ed4a35bcb191ad49efa77ad3f.jpg)

![edb9e365b0a18b28de82ba21981a14358ec52cd08a44491fab0e3081a381a315.jpg](../nips_results/1717_Truth%20over%20Tricks_%20Measuring%20and%20Mitigating%20Shortcut%20Learning%20in%20Misinformation%20Detection/tables/edb9e365b0a18b28de82ba21981a14358ec52cd08a44491fab0e3081a381a315.jpg)

## Representational Difference Explanations


### Images

![09ec62d323ccec2dc39dcd3787890249f444f0aac4dd89cd0dfdfd2b5a44e81e.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/09ec62d323ccec2dc39dcd3787890249f444f0aac4dd89cd0dfdfd2b5a44e81e.jpg)

![3cd094eb2620e6911e2556edaa249062894826045ee05d2c888f0b99f6478cc5.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/3cd094eb2620e6911e2556edaa249062894826045ee05d2c888f0b99f6478cc5.jpg)

![46fa1091fab0574b13b03847d40bc7b51b80f85bd0547c1fe5d839b962dc25d7.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/46fa1091fab0574b13b03847d40bc7b51b80f85bd0547c1fe5d839b962dc25d7.jpg)

![4a5c8ed12d093b3e05b3326fbb7ad7def8387ed58e81b5387efc5996308a1d6f.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/4a5c8ed12d093b3e05b3326fbb7ad7def8387ed58e81b5387efc5996308a1d6f.jpg)

![54635a60ed2323ef8d748ce34d0085fad8dec726064390c74c6e8c26064fbe7b.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/54635a60ed2323ef8d748ce34d0085fad8dec726064390c74c6e8c26064fbe7b.jpg)

![6129917d2bddb399dfb74873ec07094864286c941d3e92fc93d97d0284834f52.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/6129917d2bddb399dfb74873ec07094864286c941d3e92fc93d97d0284834f52.jpg)

![67f386629e0fcabacb63508e3d6552c61d9989cad0252f66e32646200407e38f.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/67f386629e0fcabacb63508e3d6552c61d9989cad0252f66e32646200407e38f.jpg)

![745b60645a4938ba19e2b842968e3c0e305a2b901c4c14a1733de66814e7643b.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/745b60645a4938ba19e2b842968e3c0e305a2b901c4c14a1733de66814e7643b.jpg)

![7d8fae5ac952e844caf9e9cbbc9e5ac0729ddf69d9350a8d8eae3e42d99b9ac3.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/7d8fae5ac952e844caf9e9cbbc9e5ac0729ddf69d9350a8d8eae3e42d99b9ac3.jpg)

![7ede556e3ca730f9284de1fec7401b79f2f1d5d6b2aab8681f4093e24c5f6f74.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/7ede556e3ca730f9284de1fec7401b79f2f1d5d6b2aab8681f4093e24c5f6f74.jpg)

![853358c534d356787e1d66be805cd6a78ac8a40db8c0d63ef164ff002d2acabb.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/853358c534d356787e1d66be805cd6a78ac8a40db8c0d63ef164ff002d2acabb.jpg)

![90d1f8f612df375fcac2cedbe4498001f98e13bd7c981f07bc7903715c0b4d62.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/90d1f8f612df375fcac2cedbe4498001f98e13bd7c981f07bc7903715c0b4d62.jpg)

![96551141d30c788b736368b63d59aed305cad54aad0975a918ab89adb7514775.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/96551141d30c788b736368b63d59aed305cad54aad0975a918ab89adb7514775.jpg)

![a75e7debfdefa1ad221bd09ed7a6ca920933f76485e3256573ecdf495a5fce39.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/a75e7debfdefa1ad221bd09ed7a6ca920933f76485e3256573ecdf495a5fce39.jpg)

![bdbcfd095cdb4620c841ce886d6d95c209b809955a6fa1d9b782c6c348c00449.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/bdbcfd095cdb4620c841ce886d6d95c209b809955a6fa1d9b782c6c348c00449.jpg)

![bef004bb731a7e2daa25a84578b53b09823f0996e3b3979f6c5cc3d652e05824.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/bef004bb731a7e2daa25a84578b53b09823f0996e3b3979f6c5cc3d652e05824.jpg)

![c104d009dfe140db70e99ac9ecbbf7a790a0ab95f15788f25fb76f7a763cfe5f.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/c104d009dfe140db70e99ac9ecbbf7a790a0ab95f15788f25fb76f7a763cfe5f.jpg)

![c14a2c6470365b2b350a7a0c081da6e77bdf2e56134b05c6de0e44d887da8a93.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/c14a2c6470365b2b350a7a0c081da6e77bdf2e56134b05c6de0e44d887da8a93.jpg)

![ca03d016f580fd95b425924fd51fcff08850bc08f195d9322a89dde8b9171bd0.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/ca03d016f580fd95b425924fd51fcff08850bc08f195d9322a89dde8b9171bd0.jpg)

![d622fa7ddcd861d30e37376ee1cc45b4852b06e66f6298beab31df5a9d08d8e0.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/d622fa7ddcd861d30e37376ee1cc45b4852b06e66f6298beab31df5a9d08d8e0.jpg)

![f7eff45774ef749196cd88b470f71457df9b4216af4a92eb99844b9bec992904.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/f7eff45774ef749196cd88b470f71457df9b4216af4a92eb99844b9bec992904.jpg)

![f9e4caa5523c07f56b0aa1a45000c56dff02c6789b52195fa342cab0347be1f5.jpg](../nips_results/1718_Representational%20Difference%20Explanations/images/f9e4caa5523c07f56b0aa1a45000c56dff02c6789b52195fa342cab0347be1f5.jpg)

### Tables

![0bd9c0f38ede65800a3ff7ebc7b3cecaa25fb309e0e098e4c40d7d6147151ea9.jpg](../nips_results/1718_Representational%20Difference%20Explanations/tables/0bd9c0f38ede65800a3ff7ebc7b3cecaa25fb309e0e098e4c40d7d6147151ea9.jpg)

![1d94ec219251ab451134a0c56b56a7992a2001eea10a31ac578b0d2c0586e4d6.jpg](../nips_results/1718_Representational%20Difference%20Explanations/tables/1d94ec219251ab451134a0c56b56a7992a2001eea10a31ac578b0d2c0586e4d6.jpg)

![4358a3a17f666c2967e495fd9d3fa88f7ee08f312db861fb4efa54644546ad6c.jpg](../nips_results/1718_Representational%20Difference%20Explanations/tables/4358a3a17f666c2967e495fd9d3fa88f7ee08f312db861fb4efa54644546ad6c.jpg)

![5491b4161ab7467a286f08af6fcdf6efdf22a311b837855d1a577ef6ce8c5c41.jpg](../nips_results/1718_Representational%20Difference%20Explanations/tables/5491b4161ab7467a286f08af6fcdf6efdf22a311b837855d1a577ef6ce8c5c41.jpg)

![5c9fe9604682f0f787e69e1edb6c8656d0a8785f8d38a7c897d73d8bea2a837e.jpg](../nips_results/1718_Representational%20Difference%20Explanations/tables/5c9fe9604682f0f787e69e1edb6c8656d0a8785f8d38a7c897d73d8bea2a837e.jpg)

![6775c39358f7f8dc1a284b21ffa567f7a136b164d7a90197d3319fec2c6d5015.jpg](../nips_results/1718_Representational%20Difference%20Explanations/tables/6775c39358f7f8dc1a284b21ffa567f7a136b164d7a90197d3319fec2c6d5015.jpg)

![6b6c6e2843d4da0d76510fe98369577de2dc877bb95b0b28dee5a3cee70a33b2.jpg](../nips_results/1718_Representational%20Difference%20Explanations/tables/6b6c6e2843d4da0d76510fe98369577de2dc877bb95b0b28dee5a3cee70a33b2.jpg)

![7391a81dfbf7fee685521302992c39ef87c8405ce91399f705bafd8d5e2ec751.jpg](../nips_results/1718_Representational%20Difference%20Explanations/tables/7391a81dfbf7fee685521302992c39ef87c8405ce91399f705bafd8d5e2ec751.jpg)

![aded57a071e13a9627db7420cf84f3743c504f2d3336bb4361c2b37d0511e877.jpg](../nips_results/1718_Representational%20Difference%20Explanations/tables/aded57a071e13a9627db7420cf84f3743c504f2d3336bb4361c2b37d0511e877.jpg)

![cffce2b2ad1aa8e796790763db8720c65b105f5dc39b7e953792c7d1049901d0.jpg](../nips_results/1718_Representational%20Difference%20Explanations/tables/cffce2b2ad1aa8e796790763db8720c65b105f5dc39b7e953792c7d1049901d0.jpg)

![e693df6bebe30b20757856174e18b59463d1599077e06efd479a95d15f17ae2d.jpg](../nips_results/1718_Representational%20Difference%20Explanations/tables/e693df6bebe30b20757856174e18b59463d1599077e06efd479a95d15f17ae2d.jpg)

## Stratify or Die: Rethinking Data Splits in Image Segmentation


### Images

![0b14c2b1be411903f0e1c986aad88872c9f37e553b8ae0669eb31d0d8d328043.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/images/0b14c2b1be411903f0e1c986aad88872c9f37e553b8ae0669eb31d0d8d328043.jpg)

![2884e48ad6c5b56c792d35050fea79c65d8425887d2bd05da58e3e6d32f09a35.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/images/2884e48ad6c5b56c792d35050fea79c65d8425887d2bd05da58e3e6d32f09a35.jpg)

![2da143b7dd864fb96e52d2b8e35b15d2c53c35709599455613bee8e6f8f15acd.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/images/2da143b7dd864fb96e52d2b8e35b15d2c53c35709599455613bee8e6f8f15acd.jpg)

![5d2fcae3f4824794454b9299411e2690bb7bfd9866cdd6dfaff2241e99dc763e.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/images/5d2fcae3f4824794454b9299411e2690bb7bfd9866cdd6dfaff2241e99dc763e.jpg)

![a8c26e4fc88b5523f35adc06ecd4f7d3354a72845698268d4e02a840a21b560c.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/images/a8c26e4fc88b5523f35adc06ecd4f7d3354a72845698268d4e02a840a21b560c.jpg)

![dffc5aed8fe80b95faaf8ecfa9bbdcf281e0788c7c99397d0701b213209a8236.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/images/dffc5aed8fe80b95faaf8ecfa9bbdcf281e0788c7c99397d0701b213209a8236.jpg)

![ec6ec0dd807de42d0df4647c734191d2ef13e94a43511d495f456fdf4fde123f.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/images/ec6ec0dd807de42d0df4647c734191d2ef13e94a43511d495f456fdf4fde123f.jpg)

![edf11f42939070450c1dc9e91834bdab0631765848dbf2dcee8b460d9ceea5cd.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/images/edf11f42939070450c1dc9e91834bdab0631765848dbf2dcee8b460d9ceea5cd.jpg)

![f512acd7fecb473cc27248f09b8889fb65129ca95470d214ae004fe2d02d8c42.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/images/f512acd7fecb473cc27248f09b8889fb65129ca95470d214ae004fe2d02d8c42.jpg)

### Tables

![1f5f2764946277a2496b6b3727036246a6edc68ae217e0f790c737b1249301b7.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/tables/1f5f2764946277a2496b6b3727036246a6edc68ae217e0f790c737b1249301b7.jpg)

![7afa10987d6810a50062bd71dc1714b8eebab3c36b63db67c8d57104ae55f66d.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/tables/7afa10987d6810a50062bd71dc1714b8eebab3c36b63db67c8d57104ae55f66d.jpg)

![984e8918d219a6a3d66d36a2c8fa853a3cd525b447ddbd36d213005bddf5ee81.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/tables/984e8918d219a6a3d66d36a2c8fa853a3cd525b447ddbd36d213005bddf5ee81.jpg)

![a6dbfbccb851fa3d52ef9dadd754c0050125c26420be07e172e62435791515a5.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/tables/a6dbfbccb851fa3d52ef9dadd754c0050125c26420be07e172e62435791515a5.jpg)

![c2b060a7211934448be3fa5ef9480cba8cc0f6a0f2e9888435bc0c4610708dc8.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/tables/c2b060a7211934448be3fa5ef9480cba8cc0f6a0f2e9888435bc0c4610708dc8.jpg)

![d06dafa594bd3ad5182ee50dc1f15668efec6c3c0fc75da221c6fc6d7bce8112.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/tables/d06dafa594bd3ad5182ee50dc1f15668efec6c3c0fc75da221c6fc6d7bce8112.jpg)

![d7d1a95985059b0ea400c0e22ed69fb62eb7cae6273ecbd6bac5c9491d8c9ac1.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/tables/d7d1a95985059b0ea400c0e22ed69fb62eb7cae6273ecbd6bac5c9491d8c9ac1.jpg)

![daf16c1392fc8791e9c01fcc507e613c0194d675ea93b3ed835c814b13f456fb.jpg](../nips_results/1719_Stratify%20or%20Die_%20Rethinking%20Data%20Splits%20in%20Image%20Segmentation/tables/daf16c1392fc8791e9c01fcc507e613c0194d675ea93b3ed835c814b13f456fb.jpg)

## Quantifying Uncertainty in Error Consistency: Towards Reliable Behavioral Comparison of Classifiers


### Images

![084e42816d8c152e6df39988268e2b94b91f580e93ef46109c3899722a8a0638.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/084e42816d8c152e6df39988268e2b94b91f580e93ef46109c3899722a8a0638.jpg)

![19556c8d41feb7a94794b6290b3ce85cf43aff0eb93225f33327c2ab72471de1.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/19556c8d41feb7a94794b6290b3ce85cf43aff0eb93225f33327c2ab72471de1.jpg)

![2c7b4386ff48f08551cfdc173184264a8ca5671375e1b863c53b7e2284487b6c.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/2c7b4386ff48f08551cfdc173184264a8ca5671375e1b863c53b7e2284487b6c.jpg)

![39128964f12d2faff97d7e1b8b433cd34ea577e0c4a84a0f9c09372b3352d50d.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/39128964f12d2faff97d7e1b8b433cd34ea577e0c4a84a0f9c09372b3352d50d.jpg)

![3e3a173253d581b24f15623365af91eb23cee314cb401d3f9b909d60ea5827ca.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/3e3a173253d581b24f15623365af91eb23cee314cb401d3f9b909d60ea5827ca.jpg)

![4b552cd1af5779a5833ff629321aed94d41572d8878cc06537f41527bd0bb19d.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/4b552cd1af5779a5833ff629321aed94d41572d8878cc06537f41527bd0bb19d.jpg)

![5cb8435d8c2888356515745105238b26efa830de497c93e7ee226f149594f29a.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/5cb8435d8c2888356515745105238b26efa830de497c93e7ee226f149594f29a.jpg)

![5ebb38d528b750ac1b4014bf286f1bc5a671009b855420c9a9bd1f5d1dcf49af.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/5ebb38d528b750ac1b4014bf286f1bc5a671009b855420c9a9bd1f5d1dcf49af.jpg)

![634a244331f42203b7d9c31d0d28a40de3efdf89cd3d7e0e04d832c22d336252.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/634a244331f42203b7d9c31d0d28a40de3efdf89cd3d7e0e04d832c22d336252.jpg)

![8b20993acd29283e123c65248c64882fcac9cfad5a72fef35b4295ecd736f8ba.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/8b20993acd29283e123c65248c64882fcac9cfad5a72fef35b4295ecd736f8ba.jpg)

![9220d1ceb9b81681decdf1664e7215bc923daf40365cd612e109d10090e515d1.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/9220d1ceb9b81681decdf1664e7215bc923daf40365cd612e109d10090e515d1.jpg)

![bba2bbf0dffe6f484f292f1ea469616e4b1ae77f570829df2ca29f5b8804b27a.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/bba2bbf0dffe6f484f292f1ea469616e4b1ae77f570829df2ca29f5b8804b27a.jpg)

![df7d77801cb4ac7edac64d7afcd7d3bfa3f3436ecad5725e25ecbc557553afe8.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/df7d77801cb4ac7edac64d7afcd7d3bfa3f3436ecad5725e25ecbc557553afe8.jpg)

![e6f8157a850a6478873ee8fdda8988bedcacad6019c5130579a2fbfc5809c705.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/images/e6f8157a850a6478873ee8fdda8988bedcacad6019c5130579a2fbfc5809c705.jpg)

### Tables

![0c17102dee6e21402120d6f8f2cb406bb505ae479fb4a2e80ec2083157f5ab22.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/tables/0c17102dee6e21402120d6f8f2cb406bb505ae479fb4a2e80ec2083157f5ab22.jpg)

![1a3185aaa9adeeb8df243ce10d036f74c88f855d766dec3ff3534263ca17426e.jpg](../nips_results/1720_Quantifying%20Uncertainty%20in%20Error%20Consistency_%20Towards%20Reliable%20Behavioral%20Comparison%20of%20Classifiers/tables/1a3185aaa9adeeb8df243ce10d036f74c88f855d766dec3ff3534263ca17426e.jpg)

## SPAZER: Spatial-Semantic Progressive Reasoning Agent for Zero-shot 3D Visual Grounding


### Images

![0d9c46f4ecf2a549d11fbf34842c95135a1f207053e538d16a93b1bde08ca39e.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/0d9c46f4ecf2a549d11fbf34842c95135a1f207053e538d16a93b1bde08ca39e.jpg)

![17d7f7c4cd1969ad816bb34e78474af264b4c9b24681b2ae7cf4346922db6e05.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/17d7f7c4cd1969ad816bb34e78474af264b4c9b24681b2ae7cf4346922db6e05.jpg)

![1def87055c58ef20d2684bea52ac6fcd7d0302f366daa77767bfc5884190a34e.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/1def87055c58ef20d2684bea52ac6fcd7d0302f366daa77767bfc5884190a34e.jpg)

![3cdb9256601c4f9e033d7fb119f2c9ad19890b9e1fa9c8adfcca85f861657881.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/3cdb9256601c4f9e033d7fb119f2c9ad19890b9e1fa9c8adfcca85f861657881.jpg)

![430bf4a46deb11e4c65475fddad54fc97d7100a4b0368a6879f0b0842877b6a2.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/430bf4a46deb11e4c65475fddad54fc97d7100a4b0368a6879f0b0842877b6a2.jpg)

![6098f4bf74304eba45d8f718aff6f1d287a7ad3a8d62ab3110096f06a93b8f2b.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/6098f4bf74304eba45d8f718aff6f1d287a7ad3a8d62ab3110096f06a93b8f2b.jpg)

![81b47c93bd0d672acbe0264cee5a17f33d3e3758d90414595185129feb6276a3.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/81b47c93bd0d672acbe0264cee5a17f33d3e3758d90414595185129feb6276a3.jpg)

![8353f9662449a7bda46c83de298f3a8b405dd2311d0bedd678bd91bb9122039a.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/8353f9662449a7bda46c83de298f3a8b405dd2311d0bedd678bd91bb9122039a.jpg)

![a99ae3c37bc0de32e1602ec7851c8fb16e2e3ce46fba7db2b9bcd027eaa150aa.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/a99ae3c37bc0de32e1602ec7851c8fb16e2e3ce46fba7db2b9bcd027eaa150aa.jpg)

![b508b1c15886d4f9ce053e9e8cb0d82c2276bd53f4d44a9d13c42cac3a439b67.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/b508b1c15886d4f9ce053e9e8cb0d82c2276bd53f4d44a9d13c42cac3a439b67.jpg)

![ce8e494ec131a5bd58015c25ed8d4940063d668431c61b2de968fc92acfea243.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/ce8e494ec131a5bd58015c25ed8d4940063d668431c61b2de968fc92acfea243.jpg)

![e6966ee06eb91b675c496dd82a4faf6a528757f720e78a24805c5337e22c7afd.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/images/e6966ee06eb91b675c496dd82a4faf6a528757f720e78a24805c5337e22c7afd.jpg)

### Tables

![1282ab82276e16d7b75d41b0e4d06a478452f2d706d352cebfddcd34362bea7d.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/tables/1282ab82276e16d7b75d41b0e4d06a478452f2d706d352cebfddcd34362bea7d.jpg)

![21701da1213b9863da00e712464f3f21e8a85d38cc45a7bb50f3484a316870ce.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/tables/21701da1213b9863da00e712464f3f21e8a85d38cc45a7bb50f3484a316870ce.jpg)

![2f14dffb64f8fa1d2076d1b6c3f6e63a1bfca67b2c430fc94a60f1bd200eb6ab.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/tables/2f14dffb64f8fa1d2076d1b6c3f6e63a1bfca67b2c430fc94a60f1bd200eb6ab.jpg)

![3eef6d7244b7f36729d4d18150d6553e29ffba05065660e167b985c915a42af7.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/tables/3eef6d7244b7f36729d4d18150d6553e29ffba05065660e167b985c915a42af7.jpg)

![52eb0c4dc1768bedf14996675ae2778f0d33a68eea507c498ba5fb2959793cd1.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/tables/52eb0c4dc1768bedf14996675ae2778f0d33a68eea507c498ba5fb2959793cd1.jpg)

![891df308d33b75544a727bb8f09f6ee0ffc1872806072b6d5eacba5fffd70eda.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/tables/891df308d33b75544a727bb8f09f6ee0ffc1872806072b6d5eacba5fffd70eda.jpg)

![acd92c426f0985f2d2fc0fe77a6a18aa9a1787d6e82236870588441e9917bdac.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/tables/acd92c426f0985f2d2fc0fe77a6a18aa9a1787d6e82236870588441e9917bdac.jpg)

![c82b06d4a53ac3407cb9677c9239c934cfceccfc1ee007be72d82f6c14b21bf6.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/tables/c82b06d4a53ac3407cb9677c9239c934cfceccfc1ee007be72d82f6c14b21bf6.jpg)

![ceec17cb12f97eb3ba3b81439008112e9160a40f84098773ba84a528eb8253bd.jpg](../nips_results/1721_SPAZER_%20Spatial-Semantic%20Progressive%20Reasoning%20Agent%20for%20Zero-shot%203D%20Visual%20Grounding/tables/ceec17cb12f97eb3ba3b81439008112e9160a40f84098773ba84a528eb8253bd.jpg)

## Rotary Masked Autoencoders are Versatile Learners


### Images

![b62022d49dd929d55d6c6dc63735691d14686cebadcee10ecc39d40720112a47.jpg](../nips_results/1722_Rotary%20Masked%20Autoencoders%20are%20Versatile%20Learners/images/b62022d49dd929d55d6c6dc63735691d14686cebadcee10ecc39d40720112a47.jpg)

### Tables

![0f37268444f10a3293216603cb486389f1ace6bc1f94bb108eed22c6d1be6ddc.jpg](../nips_results/1722_Rotary%20Masked%20Autoencoders%20are%20Versatile%20Learners/tables/0f37268444f10a3293216603cb486389f1ace6bc1f94bb108eed22c6d1be6ddc.jpg)

![35345e947e107ac5067fa6e2dd5e9bec60f3316209b8b1c6e4655231e2286708.jpg](../nips_results/1722_Rotary%20Masked%20Autoencoders%20are%20Versatile%20Learners/tables/35345e947e107ac5067fa6e2dd5e9bec60f3316209b8b1c6e4655231e2286708.jpg)

![4a34fd1bdba3ced63ab6d775a3b8d802aa6ddb67eb9fe392e6a7fe6c30d05ded.jpg](../nips_results/1722_Rotary%20Masked%20Autoencoders%20are%20Versatile%20Learners/tables/4a34fd1bdba3ced63ab6d775a3b8d802aa6ddb67eb9fe392e6a7fe6c30d05ded.jpg)

![5854ca582de91c944154b874c2700c3e4b552751a2771b754b74945c8c9a2648.jpg](../nips_results/1722_Rotary%20Masked%20Autoencoders%20are%20Versatile%20Learners/tables/5854ca582de91c944154b874c2700c3e4b552751a2771b754b74945c8c9a2648.jpg)

![841ab75899c75095df57bdc2ac6b97bd347ff4d84f519b0d3486e3342fe8284b.jpg](../nips_results/1722_Rotary%20Masked%20Autoencoders%20are%20Versatile%20Learners/tables/841ab75899c75095df57bdc2ac6b97bd347ff4d84f519b0d3486e3342fe8284b.jpg)

![e7ae5b2d7b82b3dbc6003aeafd8be0f4086278b7beffa38f31a09dc530e54724.jpg](../nips_results/1722_Rotary%20Masked%20Autoencoders%20are%20Versatile%20Learners/tables/e7ae5b2d7b82b3dbc6003aeafd8be0f4086278b7beffa38f31a09dc530e54724.jpg)

![f3d4f265c4ca08d33e569919733c352b74b4e3df09fa01bc8fc7a23ba04a9ece.jpg](../nips_results/1722_Rotary%20Masked%20Autoencoders%20are%20Versatile%20Learners/tables/f3d4f265c4ca08d33e569919733c352b74b4e3df09fa01bc8fc7a23ba04a9ece.jpg)

![fd7b1820650ee43bd10d188fb142532a5fbb2712c69cfc90728331332d2477dd.jpg](../nips_results/1722_Rotary%20Masked%20Autoencoders%20are%20Versatile%20Learners/tables/fd7b1820650ee43bd10d188fb142532a5fbb2712c69cfc90728331332d2477dd.jpg)

## NavBench: Probing Multimodal Large Language Models for Embodied Navigation


### Images

![0aff382087c5950ba86625686a9eac618a55df4d0b3ed2800525711bd6b32cf9.jpg](../nips_results/1723_NavBench_%20Probing%20Multimodal%20Large%20Language%20Models%20for%20Embodied%20Navigation/images/0aff382087c5950ba86625686a9eac618a55df4d0b3ed2800525711bd6b32cf9.jpg)

![261385314659dd1741cc14e694961b8f59071e5a501163bdbf523ee6faaaa338.jpg](../nips_results/1723_NavBench_%20Probing%20Multimodal%20Large%20Language%20Models%20for%20Embodied%20Navigation/images/261385314659dd1741cc14e694961b8f59071e5a501163bdbf523ee6faaaa338.jpg)

![5f3226c8c4d06a109741d7e34a7f36afab9d5faf10533d82797f44128bbd87a2.jpg](../nips_results/1723_NavBench_%20Probing%20Multimodal%20Large%20Language%20Models%20for%20Embodied%20Navigation/images/5f3226c8c4d06a109741d7e34a7f36afab9d5faf10533d82797f44128bbd87a2.jpg)

![86737a8ce8560161c8c40058f958368a8eb73a3a2229b67a7ce699833648d483.jpg](../nips_results/1723_NavBench_%20Probing%20Multimodal%20Large%20Language%20Models%20for%20Embodied%20Navigation/images/86737a8ce8560161c8c40058f958368a8eb73a3a2229b67a7ce699833648d483.jpg)

![b05e739f61e56843f69be1ba06f8cf2cd5c37b0e1cc6b555ca799d869b5a21d3.jpg](../nips_results/1723_NavBench_%20Probing%20Multimodal%20Large%20Language%20Models%20for%20Embodied%20Navigation/images/b05e739f61e56843f69be1ba06f8cf2cd5c37b0e1cc6b555ca799d869b5a21d3.jpg)

![b2718cc0d0d887613546571ce548923878c3fc990564c8c7a29b0d68f460297b.jpg](../nips_results/1723_NavBench_%20Probing%20Multimodal%20Large%20Language%20Models%20for%20Embodied%20Navigation/images/b2718cc0d0d887613546571ce548923878c3fc990564c8c7a29b0d68f460297b.jpg)

![f6e0b1207558c3c6903fc180ff4f31a375db93ecbf073eb93bc3c457f85b406d.jpg](../nips_results/1723_NavBench_%20Probing%20Multimodal%20Large%20Language%20Models%20for%20Embodied%20Navigation/images/f6e0b1207558c3c6903fc180ff4f31a375db93ecbf073eb93bc3c457f85b406d.jpg)

![fe2ea0b5a3b62b65ebbcfe4123303ecf8c4e0f09238547515135bed158aa4439.jpg](../nips_results/1723_NavBench_%20Probing%20Multimodal%20Large%20Language%20Models%20for%20Embodied%20Navigation/images/fe2ea0b5a3b62b65ebbcfe4123303ecf8c4e0f09238547515135bed158aa4439.jpg)

### Tables

![045992310ee85a1ac6057face6e2f1496c05efa239bf63ae17e236b2c3f6c8e3.jpg](../nips_results/1723_NavBench_%20Probing%20Multimodal%20Large%20Language%20Models%20for%20Embodied%20Navigation/tables/045992310ee85a1ac6057face6e2f1496c05efa239bf63ae17e236b2c3f6c8e3.jpg)

![a769fafe8a391fcb54686eedbc7f5ee8473cd3362b3f2c8455acb273bbe5a27a.jpg](../nips_results/1723_NavBench_%20Probing%20Multimodal%20Large%20Language%20Models%20for%20Embodied%20Navigation/tables/a769fafe8a391fcb54686eedbc7f5ee8473cd3362b3f2c8455acb273bbe5a27a.jpg)

![c7a86ccb9a3a0c1aee90cf26e05970b8d5ddead13cecf44e4bbf25500cd9f444.jpg](../nips_results/1723_NavBench_%20Probing%20Multimodal%20Large%20Language%20Models%20for%20Embodied%20Navigation/tables/c7a86ccb9a3a0c1aee90cf26e05970b8d5ddead13cecf44e4bbf25500cd9f444.jpg)

## Diff-ICMH: Harmonizing Machine and Human Vision in Image Compression with Generative Prior


### Images

![22c79104fdfe2097c188f5a8b3d9714983aab909914173b115ed65b813a3c9de.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/22c79104fdfe2097c188f5a8b3d9714983aab909914173b115ed65b813a3c9de.jpg)

![245053205c66f4347996e4e25a29aec2b8fc9ee84a8c7e4af897d8071c466279.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/245053205c66f4347996e4e25a29aec2b8fc9ee84a8c7e4af897d8071c466279.jpg)

![267ed6d6bb2913023f98859a3fc8f003c69849b3ddf47b0a2919970f67a6aba5.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/267ed6d6bb2913023f98859a3fc8f003c69849b3ddf47b0a2919970f67a6aba5.jpg)

![362e7cc6c6e92468c2cccb58bf07d715394ccfbf8b2686831faea28425612d27.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/362e7cc6c6e92468c2cccb58bf07d715394ccfbf8b2686831faea28425612d27.jpg)

![4ca1d905d39c7c4c91f1cafe9a04e6e2b5535bf1239a08405410918bccf36d1a.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/4ca1d905d39c7c4c91f1cafe9a04e6e2b5535bf1239a08405410918bccf36d1a.jpg)

![4dc44c70e48617496d6baf9920713b2edb682e5d75a7502b868f3335105bc1bd.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/4dc44c70e48617496d6baf9920713b2edb682e5d75a7502b868f3335105bc1bd.jpg)

![5c840f222cf19477ebd0d634d0c956609b58156a1dd541e3505927c2b11cd593.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/5c840f222cf19477ebd0d634d0c956609b58156a1dd541e3505927c2b11cd593.jpg)

![6a04661dc5b38229a462957f04054a3531f7962c53d1e4be4cbf79cf8595310b.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/6a04661dc5b38229a462957f04054a3531f7962c53d1e4be4cbf79cf8595310b.jpg)

![7ce5088662a0faa70fa1a0bd295ef310cb276f81a38bd40dca6d6782eff02482.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/7ce5088662a0faa70fa1a0bd295ef310cb276f81a38bd40dca6d6782eff02482.jpg)

![7df083328520badf24466c03faa0e38e17f332a1b14a5e4f10cf1e98b712fee6.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/7df083328520badf24466c03faa0e38e17f332a1b14a5e4f10cf1e98b712fee6.jpg)

![aee4d8ff4ce2fe8b6acd3739cf5589b81409b2d4572e34d014a9962a886492b7.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/aee4d8ff4ce2fe8b6acd3739cf5589b81409b2d4572e34d014a9962a886492b7.jpg)

![de59285142b48a7a8b616652443d499ed599f8b4c3a8fac430ce406f5c2cd104.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/de59285142b48a7a8b616652443d499ed599f8b4c3a8fac430ce406f5c2cd104.jpg)

![eca0ba4a74ce181fb43d08d14fc53e02eea3469fc106e0f62b241570b1a2f7fc.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/images/eca0ba4a74ce181fb43d08d14fc53e02eea3469fc106e0f62b241570b1a2f7fc.jpg)

### Tables

![b7b2a929474f7957e4b465b551dad443c52c4559fb3aac6835adbeb33df241c6.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/tables/b7b2a929474f7957e4b465b551dad443c52c4559fb3aac6835adbeb33df241c6.jpg)

![fcf92a21ad6d6956357d7c051f54f192000fbf4a607a14726bd81d3f44a9c1ff.jpg](../nips_results/1724_Diff-ICMH_%20Harmonizing%20Machine%20and%20Human%20Vision%20in%20Image%20Compression%20with%20Generative%20Prior/tables/fcf92a21ad6d6956357d7c051f54f192000fbf4a607a14726bd81d3f44a9c1ff.jpg)

## Nested Learning: The Illusion of Deep Learning Architectures


### Images

![109cf9ff8de6674b17b2752024ccc6ac082dfd362a7a626c4e8ae84ea14b5bbf.jpg](../nips_results/1725_Nested%20Learning_%20The%20Illusion%20of%20Deep%20Learning%20Architectures/images/109cf9ff8de6674b17b2752024ccc6ac082dfd362a7a626c4e8ae84ea14b5bbf.jpg)

![7b8edee6945be0eb0adb154a3e8a8c4dea752df596ac0ac3a71edbedd0008043.jpg](../nips_results/1725_Nested%20Learning_%20The%20Illusion%20of%20Deep%20Learning%20Architectures/images/7b8edee6945be0eb0adb154a3e8a8c4dea752df596ac0ac3a71edbedd0008043.jpg)

![b5c6888dccffcf9c49fe36f2e8cc609ffbd6ddb218603aa4457eb7373ee35b68.jpg](../nips_results/1725_Nested%20Learning_%20The%20Illusion%20of%20Deep%20Learning%20Architectures/images/b5c6888dccffcf9c49fe36f2e8cc609ffbd6ddb218603aa4457eb7373ee35b68.jpg)

### Tables

![a8002eed9305b56817a797e5bbaee6daea07989775f6c3a215d136d5db327380.jpg](../nips_results/1725_Nested%20Learning_%20The%20Illusion%20of%20Deep%20Learning%20Architectures/tables/a8002eed9305b56817a797e5bbaee6daea07989775f6c3a215d136d5db327380.jpg)

## On Local Limits of Sparse Random Graphs: Color Convergence and the Refined Configuration Model


### Images

![2648bf348b1ae2c0c0b1aad1cc4e83a9eae871be2cba26ede5dfab99aad4428c.jpg](../nips_results/1726_On%20Local%20Limits%20of%20Sparse%20Random%20Graphs_%20Color%20Convergence%20and%20the%20Refined%20Configuration%20Model/images/2648bf348b1ae2c0c0b1aad1cc4e83a9eae871be2cba26ede5dfab99aad4428c.jpg)

![377ed64fb98fde9be4cc624f956d3f9556e5a12938dc7df1354d190d9efe9714.jpg](../nips_results/1726_On%20Local%20Limits%20of%20Sparse%20Random%20Graphs_%20Color%20Convergence%20and%20the%20Refined%20Configuration%20Model/images/377ed64fb98fde9be4cc624f956d3f9556e5a12938dc7df1354d190d9efe9714.jpg)

![aebdbecb52c2ed495c820365e9e2e2e75cb75c0bb1de5f22dd0cf43389e72bfa.jpg](../nips_results/1726_On%20Local%20Limits%20of%20Sparse%20Random%20Graphs_%20Color%20Convergence%20and%20the%20Refined%20Configuration%20Model/images/aebdbecb52c2ed495c820365e9e2e2e75cb75c0bb1de5f22dd0cf43389e72bfa.jpg)

![f41d41ff5aa73350a3652899a1e7a0ba3c5f10697c9adee608367166dcc35e79.jpg](../nips_results/1726_On%20Local%20Limits%20of%20Sparse%20Random%20Graphs_%20Color%20Convergence%20and%20the%20Refined%20Configuration%20Model/images/f41d41ff5aa73350a3652899a1e7a0ba3c5f10697c9adee608367166dcc35e79.jpg)

## Language Models (Mostly) Know When to Stop Reading


### Images

![0fd75335842117538c5e1686061e00143d1365a1538e481cd3bb02fbdcc76345.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/images/0fd75335842117538c5e1686061e00143d1365a1538e481cd3bb02fbdcc76345.jpg)

![1846ab2d5900b89d69407829c4eb57d9ab55f7606df090a5b6a5b97e40882edd.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/images/1846ab2d5900b89d69407829c4eb57d9ab55f7606df090a5b6a5b97e40882edd.jpg)

![2ea01f2aced469b794b4dce3e75768d2fdcfc1f512d7350480d354359b08337c.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/images/2ea01f2aced469b794b4dce3e75768d2fdcfc1f512d7350480d354359b08337c.jpg)

![34adcb34b4a736f5727eb55224227db2ca4bff3c34eb61f3541b2298a530d7bb.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/images/34adcb34b4a736f5727eb55224227db2ca4bff3c34eb61f3541b2298a530d7bb.jpg)

![b252a2e99ccb23456fbc58ce70162cb668447667465c2e0e0e20e310c3469122.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/images/b252a2e99ccb23456fbc58ce70162cb668447667465c2e0e0e20e310c3469122.jpg)

![b4d6d4d3ffc1026dc9b4e148b8398d05821fad7d6dcf5ccc893af82ae9c41bdb.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/images/b4d6d4d3ffc1026dc9b4e148b8398d05821fad7d6dcf5ccc893af82ae9c41bdb.jpg)

![b703f5651fe3b47f3cef3b8596c96a7d16010b3eace2dcfaaea83c523c621855.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/images/b703f5651fe3b47f3cef3b8596c96a7d16010b3eace2dcfaaea83c523c621855.jpg)

![bd1904a8b141b66176900f7a0c0241e7a594b5950fbb7b96bfad93a1454c24b9.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/images/bd1904a8b141b66176900f7a0c0241e7a594b5950fbb7b96bfad93a1454c24b9.jpg)

![cebf9dc71f1fd7771b7b24bd0463ab11c90a1c2619e46ee2fe7772abfc2031db.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/images/cebf9dc71f1fd7771b7b24bd0463ab11c90a1c2619e46ee2fe7772abfc2031db.jpg)

![dc46872b6bca1952623a6e3bfc3c491d95c895df95fc46023075f63fe6936175.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/images/dc46872b6bca1952623a6e3bfc3c491d95c895df95fc46023075f63fe6936175.jpg)

![fa7e39b0c6e43e33aaebf1d0c3aea4fe6b86fafdd9ed1f849e1c595d9b20730c.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/images/fa7e39b0c6e43e33aaebf1d0c3aea4fe6b86fafdd9ed1f849e1c595d9b20730c.jpg)

### Tables

![20ddb4ef5ae6ba990b7c0b4e6071cdc4e561f6042bbb9977713cbc8d0f5330e5.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/tables/20ddb4ef5ae6ba990b7c0b4e6071cdc4e561f6042bbb9977713cbc8d0f5330e5.jpg)

![50cb326b50a41e243f636e02cdf98073f7bfa1bdce0d714af1055bc29a02b74e.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/tables/50cb326b50a41e243f636e02cdf98073f7bfa1bdce0d714af1055bc29a02b74e.jpg)

![6a3bf37631999c183d677cd73e5a7daab3028128b677e84200d324611a9e8127.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/tables/6a3bf37631999c183d677cd73e5a7daab3028128b677e84200d324611a9e8127.jpg)

![70ea9d9cd37c5be7c989fa3e8c0a52dbba444a8b1dd0f21485e861d43be693d6.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/tables/70ea9d9cd37c5be7c989fa3e8c0a52dbba444a8b1dd0f21485e861d43be693d6.jpg)

![913c23e0d33cff3b7f2585cabcf99873d6e9bdc83ace2007f9485a709af62dc0.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/tables/913c23e0d33cff3b7f2585cabcf99873d6e9bdc83ace2007f9485a709af62dc0.jpg)

![be1f6228e94997440ebbb5dc7640db6196f23c5d001192ca32d9240dd61b7493.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/tables/be1f6228e94997440ebbb5dc7640db6196f23c5d001192ca32d9240dd61b7493.jpg)

![c39e68cb7e8a6480ba7e7921dbb21d819dba42b402b92886b2253e08c1914a9c.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/tables/c39e68cb7e8a6480ba7e7921dbb21d819dba42b402b92886b2253e08c1914a9c.jpg)

![cbccd9e446f03c6e4ecd94127287d81740a14c669775288ed4b818f522cea710.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/tables/cbccd9e446f03c6e4ecd94127287d81740a14c669775288ed4b818f522cea710.jpg)

![cc407571e09c2af26f8a8b0e8f53e8dcd03e9dfd2b9efdabe5c074df354a2fc3.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/tables/cc407571e09c2af26f8a8b0e8f53e8dcd03e9dfd2b9efdabe5c074df354a2fc3.jpg)

![e0b1599e1caf6174536df3518c5524c2e822cde7223d9b5d66a0d50a729c5933.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/tables/e0b1599e1caf6174536df3518c5524c2e822cde7223d9b5d66a0d50a729c5933.jpg)

![e0d594a070b88cbcf4072224cdf29d8c1e102481f84f1d7de066162351ef885b.jpg](../nips_results/1727_Language%20Models%20%28Mostly) Know When to Stop Reading/tables/e0d594a070b88cbcf4072224cdf29d8c1e102481f84f1d7de066162351ef885b.jpg)

## Towards Generalizable 3D Human Pose Estimation via Ensembles on Flat Loss Landscapes


### Images

![4ed708bfa0b6b8c3085b094da1a8eb81b6476891fb4b8cfacbc9d7739f6dc6f3.jpg](../nips_results/1728_Towards%20Generalizable%203D%20Human%20Pose%20Estimation%20via%20Ensembles%20on%20Flat%20Loss%20Landscapes/images/4ed708bfa0b6b8c3085b094da1a8eb81b6476891fb4b8cfacbc9d7739f6dc6f3.jpg)

![7c96b1ad3b0f1503c9f95ffdd0509afe07cda99d033dd7392692f5c19bb052ae.jpg](../nips_results/1728_Towards%20Generalizable%203D%20Human%20Pose%20Estimation%20via%20Ensembles%20on%20Flat%20Loss%20Landscapes/images/7c96b1ad3b0f1503c9f95ffdd0509afe07cda99d033dd7392692f5c19bb052ae.jpg)

![a1b02cda35558172572e9ac420e6ea22abc1188deba6654c7e3f002ea16bfd6b.jpg](../nips_results/1728_Towards%20Generalizable%203D%20Human%20Pose%20Estimation%20via%20Ensembles%20on%20Flat%20Loss%20Landscapes/images/a1b02cda35558172572e9ac420e6ea22abc1188deba6654c7e3f002ea16bfd6b.jpg)

![aac8d007dcdd44d4a821d560a6dd56859cc7191d92de8bf4655d4f49a69f22fb.jpg](../nips_results/1728_Towards%20Generalizable%203D%20Human%20Pose%20Estimation%20via%20Ensembles%20on%20Flat%20Loss%20Landscapes/images/aac8d007dcdd44d4a821d560a6dd56859cc7191d92de8bf4655d4f49a69f22fb.jpg)

![bad538335b183a6ec63c2d6a2566d4e5392a00af34e1cf3542910ff00fe9f38e.jpg](../nips_results/1728_Towards%20Generalizable%203D%20Human%20Pose%20Estimation%20via%20Ensembles%20on%20Flat%20Loss%20Landscapes/images/bad538335b183a6ec63c2d6a2566d4e5392a00af34e1cf3542910ff00fe9f38e.jpg)

![cbbbb7e8ed49d1ca1c34809990619a2271b7ff029ccdb4b92a4d94f3857d1921.jpg](../nips_results/1728_Towards%20Generalizable%203D%20Human%20Pose%20Estimation%20via%20Ensembles%20on%20Flat%20Loss%20Landscapes/images/cbbbb7e8ed49d1ca1c34809990619a2271b7ff029ccdb4b92a4d94f3857d1921.jpg)

![e0a15787c18224d7bcf5126692ff5b8196b932787307e745d226ab3c2e692b2d.jpg](../nips_results/1728_Towards%20Generalizable%203D%20Human%20Pose%20Estimation%20via%20Ensembles%20on%20Flat%20Loss%20Landscapes/images/e0a15787c18224d7bcf5126692ff5b8196b932787307e745d226ab3c2e692b2d.jpg)

### Tables

![04bbf57470942104283dbd731b510c64d4812956817eeab8320f132adec592c5.jpg](../nips_results/1728_Towards%20Generalizable%203D%20Human%20Pose%20Estimation%20via%20Ensembles%20on%20Flat%20Loss%20Landscapes/tables/04bbf57470942104283dbd731b510c64d4812956817eeab8320f132adec592c5.jpg)

![5aa9079ba1fff78df26f629ba5ebfc7d43d00f92a9b7954f22e97ad4002467da.jpg](../nips_results/1728_Towards%20Generalizable%203D%20Human%20Pose%20Estimation%20via%20Ensembles%20on%20Flat%20Loss%20Landscapes/tables/5aa9079ba1fff78df26f629ba5ebfc7d43d00f92a9b7954f22e97ad4002467da.jpg)

![76475dff5ca8a6a67dae20aaaa89e01d8a9dfa84367597c62302b0965b15cbb3.jpg](../nips_results/1728_Towards%20Generalizable%203D%20Human%20Pose%20Estimation%20via%20Ensembles%20on%20Flat%20Loss%20Landscapes/tables/76475dff5ca8a6a67dae20aaaa89e01d8a9dfa84367597c62302b0965b15cbb3.jpg)

![ab3197419248fc3ae34b56e6ee152a2e79b16a4763d286c990fb31c43718edf4.jpg](../nips_results/1728_Towards%20Generalizable%203D%20Human%20Pose%20Estimation%20via%20Ensembles%20on%20Flat%20Loss%20Landscapes/tables/ab3197419248fc3ae34b56e6ee152a2e79b16a4763d286c990fb31c43718edf4.jpg)

## Statistical inference for Linear Stochastic Approximation with Markovian Noise


### Tables

![b1c1f94b73302c3b12c1d272653a0f9258a8c37e97f10d15be88a419062ba873.jpg](../nips_results/1729_Statistical%20inference%20for%20Linear%20Stochastic%20Approximation%20with%20Markovian%20Noise/tables/b1c1f94b73302c3b12c1d272653a0f9258a8c37e97f10d15be88a419062ba873.jpg)

## AdaptGrad: Adaptive Sampling to Reduce Noise


### Images

![10f95440079c3c47e0a342f0312ac8d96c16b729b5e5df64cab66de6d478b4bd.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/10f95440079c3c47e0a342f0312ac8d96c16b729b5e5df64cab66de6d478b4bd.jpg)

![18130962489c39e762e5faa9ac0baf327cb112f84e311c52b1ff4a96d54fbd39.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/18130962489c39e762e5faa9ac0baf327cb112f84e311c52b1ff4a96d54fbd39.jpg)

![36f0c2a9fb4f7b7ec17b1e34f348cdf532abc0a809dd5b6ebba67b52b703a070.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/36f0c2a9fb4f7b7ec17b1e34f348cdf532abc0a809dd5b6ebba67b52b703a070.jpg)

![3799ff32c3eaf86e635a00f1b579591d7e9dd203274f694188b9caf9038ae5a3.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/3799ff32c3eaf86e635a00f1b579591d7e9dd203274f694188b9caf9038ae5a3.jpg)

![3b1715bd7f602445921587bb5087445ab6c572f0e4dcd72820baa7ff6d32ccb5.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/3b1715bd7f602445921587bb5087445ab6c572f0e4dcd72820baa7ff6d32ccb5.jpg)

![43882d79119925db266baaab5a653c9bc704186bdba5ca7bb094e635f869085e.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/43882d79119925db266baaab5a653c9bc704186bdba5ca7bb094e635f869085e.jpg)

![4552466c9ab418250a9d2ae755ccc408dae08d84087249184665b823966f808c.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/4552466c9ab418250a9d2ae755ccc408dae08d84087249184665b823966f808c.jpg)

![66dbe9bb8b1d25e1bad6ab164e1d5a47e81b4fb3a788dfe428cc5ead36f5d204.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/66dbe9bb8b1d25e1bad6ab164e1d5a47e81b4fb3a788dfe428cc5ead36f5d204.jpg)

![6ec09bbae749fb4f6cfbb072028e8fa9c20af15a54110b9ee5a6c1ecafbe0a8c.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/6ec09bbae749fb4f6cfbb072028e8fa9c20af15a54110b9ee5a6c1ecafbe0a8c.jpg)

![729707b212a2f94b217beceb2a9505c6f55af7f3bcbf8cce5d63c8a8b18df5e5.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/729707b212a2f94b217beceb2a9505c6f55af7f3bcbf8cce5d63c8a8b18df5e5.jpg)

![8ec292857b24b254e55c9644b1839fe863f21aec7f75106e3057e7ff23c023b8.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/8ec292857b24b254e55c9644b1839fe863f21aec7f75106e3057e7ff23c023b8.jpg)

![982ccf9d5ee3f61343768429ef57b9a3b204ba8a2767e5bf0081226e2aa7be28.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/982ccf9d5ee3f61343768429ef57b9a3b204ba8a2767e5bf0081226e2aa7be28.jpg)

![9c85ac37a6777ec4bc369bb40a1cb1a3f04966035409c49e2e2d40f28e63fbcb.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/9c85ac37a6777ec4bc369bb40a1cb1a3f04966035409c49e2e2d40f28e63fbcb.jpg)

![9e4c640e950b476e77513ddcd70d42e9cfb31eb4e963c589e82814f88bdba2b8.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/9e4c640e950b476e77513ddcd70d42e9cfb31eb4e963c589e82814f88bdba2b8.jpg)

![a8f6cb68003b678d4c567b2c4d3dd7f021e126f5e806e069d8285839c06d4db5.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/a8f6cb68003b678d4c567b2c4d3dd7f021e126f5e806e069d8285839c06d4db5.jpg)

![b3cab82d1e926288c507f74b9a64770b3253bb2871d5fb815a111ed7f706d5d2.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/b3cab82d1e926288c507f74b9a64770b3253bb2871d5fb815a111ed7f706d5d2.jpg)

![df2cfb245601bd0838dd4a5738241c571710c3c2c607b6c82b886627d16aae98.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/images/df2cfb245601bd0838dd4a5738241c571710c3c2c607b6c82b886627d16aae98.jpg)

### Tables

![08866da384b5e00f784dcbc58546a547b995a8535371397adfa9b0ed4db568b3.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/tables/08866da384b5e00f784dcbc58546a547b995a8535371397adfa9b0ed4db568b3.jpg)

![0f5212b288038e850d04288629fbbc4dc72443e09a1cb573d8dd7f5079c82912.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/tables/0f5212b288038e850d04288629fbbc4dc72443e09a1cb573d8dd7f5079c82912.jpg)

![331075a80b13e6b72378ce9d9120ccbd282152ec53ffc15fe8270ab041799b54.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/tables/331075a80b13e6b72378ce9d9120ccbd282152ec53ffc15fe8270ab041799b54.jpg)

![37850dc55d5d97247f986eb3fc27694743bb45dae32fc06576c89384c7123e68.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/tables/37850dc55d5d97247f986eb3fc27694743bb45dae32fc06576c89384c7123e68.jpg)

![4f5e25b931aa4dd9a2b2274ffb877b4dd64e2330dd692cc8d669c8d4fff59eeb.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/tables/4f5e25b931aa4dd9a2b2274ffb877b4dd64e2330dd692cc8d669c8d4fff59eeb.jpg)

![533232be26cab2134ce90dd87a871369d2adcf8c019f5d3aae92eb6b4d3bdacb.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/tables/533232be26cab2134ce90dd87a871369d2adcf8c019f5d3aae92eb6b4d3bdacb.jpg)

![819f639563bf613777ffa8fdb957662b98052378ace8a6da265bed231b185192.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/tables/819f639563bf613777ffa8fdb957662b98052378ace8a6da265bed231b185192.jpg)

![9d746dc0b0c4249459f63c2dbde0d91ca36c4ce477e14561493890ef23d8f7af.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/tables/9d746dc0b0c4249459f63c2dbde0d91ca36c4ce477e14561493890ef23d8f7af.jpg)

![a435350ff5e2d9f2d22e16623dec540f9c436e3ff1049a3d3e9f1d08393cd97b.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/tables/a435350ff5e2d9f2d22e16623dec540f9c436e3ff1049a3d3e9f1d08393cd97b.jpg)

![bb849390a44193815109617d42d749436ead7d0effbda4e9ecef90d2ae00d514.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/tables/bb849390a44193815109617d42d749436ead7d0effbda4e9ecef90d2ae00d514.jpg)

![d8fc5e7d5bb16e1f1f86542bb1cad0bcf13b647051b5f3afc96a6ff851d9d535.jpg](../nips_results/1730_AdaptGrad_%20Adaptive%20Sampling%20to%20Reduce%20Noise/tables/d8fc5e7d5bb16e1f1f86542bb1cad0bcf13b647051b5f3afc96a6ff851d9d535.jpg)

## Compositional Reasoning with Transformers, RNNs, and Chain of Thought


### Images

![2c9fe94a69b3a782c4a484bc6eb62b4fc4c3834079fd22bfaf1445abac8c78d3.jpg](../nips_results/1731_Compositional%20Reasoning%20with%20Transformers%2C%20RNNs%2C%20and%20Chain%20of%20Thought/images/2c9fe94a69b3a782c4a484bc6eb62b4fc4c3834079fd22bfaf1445abac8c78d3.jpg)

![7ba7a36646bac08138bf2f7f1ab233e799d061108220bf93f2a3d662f181cebd.jpg](../nips_results/1731_Compositional%20Reasoning%20with%20Transformers%2C%20RNNs%2C%20and%20Chain%20of%20Thought/images/7ba7a36646bac08138bf2f7f1ab233e799d061108220bf93f2a3d662f181cebd.jpg)

![ee0672d00c725081331ba6bf97a48682e958c5fa802b82c3fd67e16bd1f1c6c5.jpg](../nips_results/1731_Compositional%20Reasoning%20with%20Transformers%2C%20RNNs%2C%20and%20Chain%20of%20Thought/images/ee0672d00c725081331ba6bf97a48682e958c5fa802b82c3fd67e16bd1f1c6c5.jpg)

### Tables

![80d0a1dda92bd3b40b80debd8fc46ad89035cb7a97bcf4fa506a4f85a1135393.jpg](../nips_results/1731_Compositional%20Reasoning%20with%20Transformers%2C%20RNNs%2C%20and%20Chain%20of%20Thought/tables/80d0a1dda92bd3b40b80debd8fc46ad89035cb7a97bcf4fa506a4f85a1135393.jpg)

## OSTAR: Optimized Statistical Text-classifier with Adversarial Resistance


### Images

![03ea1843103bb577bd952eab684839c299ad930ae79ea154f94795e44ef164ce.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/images/03ea1843103bb577bd952eab684839c299ad930ae79ea154f94795e44ef164ce.jpg)

![06652ee65ebd7c7db02e793db1de3a6a059dc3b53282a246acc61d786aed1b3e.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/images/06652ee65ebd7c7db02e793db1de3a6a059dc3b53282a246acc61d786aed1b3e.jpg)

![10ccb153ead2ac0082dfed80017e6388a3179e45b8ef8dbb09e72d5813d419e4.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/images/10ccb153ead2ac0082dfed80017e6388a3179e45b8ef8dbb09e72d5813d419e4.jpg)

![16c119ed7afb59331e5fc0ed44a0bb992749a4cabc17804dd8dd7098f1df015d.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/images/16c119ed7afb59331e5fc0ed44a0bb992749a4cabc17804dd8dd7098f1df015d.jpg)

![2a025b1d93feef7b61c907c6620046fe6e57f5d0fdbd0759b8349e83b6e12520.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/images/2a025b1d93feef7b61c907c6620046fe6e57f5d0fdbd0759b8349e83b6e12520.jpg)

![3e3ad12fcd9694c130338c0a6b5c8956df78f3d44f0dcc6e89866ea310d9efa4.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/images/3e3ad12fcd9694c130338c0a6b5c8956df78f3d44f0dcc6e89866ea310d9efa4.jpg)

![572ecca0d972b63f2cf353f0f1444bd3f4586994b8e42a4825c961d0eabf28f5.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/images/572ecca0d972b63f2cf353f0f1444bd3f4586994b8e42a4825c961d0eabf28f5.jpg)

![bd6f249d403fb7e7811daaaca56e70a5ac2fc78dafe4a49e4ee3baefc2e793cd.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/images/bd6f249d403fb7e7811daaaca56e70a5ac2fc78dafe4a49e4ee3baefc2e793cd.jpg)

![c703f3754e909ff2120d33948dea6f69f7b852fc27b12d917cb0b7e4984d6e19.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/images/c703f3754e909ff2120d33948dea6f69f7b852fc27b12d917cb0b7e4984d6e19.jpg)

### Tables

![1885d55bcc23b394294d2ecf55f00ed4c3018894b452a520aef9b8acc5f76819.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/tables/1885d55bcc23b394294d2ecf55f00ed4c3018894b452a520aef9b8acc5f76819.jpg)

![457ed65390a8acc6d7b31772c0b0da80642b002fd5cb9ccd19c80687049994dd.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/tables/457ed65390a8acc6d7b31772c0b0da80642b002fd5cb9ccd19c80687049994dd.jpg)

![4ee22e305d85afcbae132ccc927fd34669a6064da3a9a5c4104a716a478a3631.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/tables/4ee22e305d85afcbae132ccc927fd34669a6064da3a9a5c4104a716a478a3631.jpg)

![7e17484cc2a4aff1ddbf5eda73929d46cd756d2356ce0782c254ccc65f523076.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/tables/7e17484cc2a4aff1ddbf5eda73929d46cd756d2356ce0782c254ccc65f523076.jpg)

![c81741d41be044d083956638ef0217e020772de1e525f271453e3b30bf68df6f.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/tables/c81741d41be044d083956638ef0217e020772de1e525f271453e3b30bf68df6f.jpg)

![c8ff7cbcc40a974dd882e2a39181a14122b4f791c35a2987267bae5b1062167b.jpg](../nips_results/1732_OSTAR_%20Optimized%20Statistical%20Text-classifier%20with%20Adversarial%20Resistance/tables/c8ff7cbcc40a974dd882e2a39181a14122b4f791c35a2987267bae5b1062167b.jpg)

## Sparta Alignment: Collectively Aligning Multiple Language Models through Combat


### Images

![0b4f856d5ddb4fe43bdea0d0f65c9347293af74bb1a96ddd35f1aaa1663fc527.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/images/0b4f856d5ddb4fe43bdea0d0f65c9347293af74bb1a96ddd35f1aaa1663fc527.jpg)

![4abbbae8ce37382e204ff427e9ca6282b6bc6b1230c0e593877cf274c3681ea9.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/images/4abbbae8ce37382e204ff427e9ca6282b6bc6b1230c0e593877cf274c3681ea9.jpg)

![77a500eceb1ed06b9deeeaa3b402398cd2aa59dde0e950f11ee566be968d0aba.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/images/77a500eceb1ed06b9deeeaa3b402398cd2aa59dde0e950f11ee566be968d0aba.jpg)

![81ceb155ea7b8cca36d8a93a5ba2eb046c2d8ce53a6dfcdc71043bcbe2063560.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/images/81ceb155ea7b8cca36d8a93a5ba2eb046c2d8ce53a6dfcdc71043bcbe2063560.jpg)

![946c1a08ffe79a8632607719f12fa8cd2e29108fc29bfdd5d33a68792a4e3287.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/images/946c1a08ffe79a8632607719f12fa8cd2e29108fc29bfdd5d33a68792a4e3287.jpg)

![ae0ccb6838908f86979c4c4cfda4498022c47b6858696cae4bce81ba4c59ecfe.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/images/ae0ccb6838908f86979c4c4cfda4498022c47b6858696cae4bce81ba4c59ecfe.jpg)

![b583fa8cf8ca6aa3d262305800a93555f1c3c39a8335ab46edf93bda52b9d4fa.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/images/b583fa8cf8ca6aa3d262305800a93555f1c3c39a8335ab46edf93bda52b9d4fa.jpg)

![ed2b367240c51b471bf40c0106b265f34e3bdf81deae4df69ce25b6dce619db9.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/images/ed2b367240c51b471bf40c0106b265f34e3bdf81deae4df69ce25b6dce619db9.jpg)

### Tables

![288f20af47d5a40e690cbcec1c2efb2d3a61a8f41fae53cc4f3c873717cb905a.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/tables/288f20af47d5a40e690cbcec1c2efb2d3a61a8f41fae53cc4f3c873717cb905a.jpg)

![292296dfe413c7b6d17b60f5361b8cf342761d99fc8158cd9a1a7b52d8597df2.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/tables/292296dfe413c7b6d17b60f5361b8cf342761d99fc8158cd9a1a7b52d8597df2.jpg)

![2ccc0fd5c962e99c244b04aedb1587d8e9edfc48428723b2aae0e82397a95b38.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/tables/2ccc0fd5c962e99c244b04aedb1587d8e9edfc48428723b2aae0e82397a95b38.jpg)

![765f300e189b32af7d3eb4567122b158233f352021817060d4eee549870b20be.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/tables/765f300e189b32af7d3eb4567122b158233f352021817060d4eee549870b20be.jpg)

![8e5fcaf87276d872f74ada143ac4bde506ef77bc3c2c9b73260c6de4d30f9481.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/tables/8e5fcaf87276d872f74ada143ac4bde506ef77bc3c2c9b73260c6de4d30f9481.jpg)

![9adc775c0533126099ccf4d392352d2f6196581f619e1d77eb39909178e937d8.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/tables/9adc775c0533126099ccf4d392352d2f6196581f619e1d77eb39909178e937d8.jpg)

![d2cbb0b2191dc0ab55a0df280da360ca4f7fbdfb47f19d2bd2496082d47499e8.jpg](../nips_results/1733_Sparta%20Alignment_%20Collectively%20Aligning%20Multiple%20Language%20Models%20through%20Combat/tables/d2cbb0b2191dc0ab55a0df280da360ca4f7fbdfb47f19d2bd2496082d47499e8.jpg)

## Vision Function Layer in Multimodal LLMs


### Images

![2a7da735cadd659772fdabebb1fb71a3dee43411a17ce86d6c6a2f15907e26a3.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/images/2a7da735cadd659772fdabebb1fb71a3dee43411a17ce86d6c6a2f15907e26a3.jpg)

![336bb36d7c0c0e0809643772dec91bd81a70c0a403f3b2945f6f6baac339d025.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/images/336bb36d7c0c0e0809643772dec91bd81a70c0a403f3b2945f6f6baac339d025.jpg)

![37c6992c9614762966486b4d1a1bd24670385371f9cae5947cf5d20ad0ded19e.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/images/37c6992c9614762966486b4d1a1bd24670385371f9cae5947cf5d20ad0ded19e.jpg)

![557c4af4faca46cfe0f7e80b6678a0171251a0472d99e534ab30a62f3895fac1.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/images/557c4af4faca46cfe0f7e80b6678a0171251a0472d99e534ab30a62f3895fac1.jpg)

![7d96e3d7b988d37fa2b27a1d76dd91992ce4f40f234a1461792436575e0452b5.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/images/7d96e3d7b988d37fa2b27a1d76dd91992ce4f40f234a1461792436575e0452b5.jpg)

![912b725e4bb1f155c2495c9d3d35b66834bb0987fd5ace0785589135dada49bf.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/images/912b725e4bb1f155c2495c9d3d35b66834bb0987fd5ace0785589135dada49bf.jpg)

![a8d563a48efe5b220986b8725a2d894e42ea912d5bf51634546be1aa393755ff.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/images/a8d563a48efe5b220986b8725a2d894e42ea912d5bf51634546be1aa393755ff.jpg)

### Tables

![3ba834f5b049a9b9fbbe4bfabc19368f9d8b6d49b671bb7effdf970051ba4bac.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/tables/3ba834f5b049a9b9fbbe4bfabc19368f9d8b6d49b671bb7effdf970051ba4bac.jpg)

![3bfc8f486a05f4d970f11ed713ecc469671c3f34c7ae189eda47f229c9e9e9c9.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/tables/3bfc8f486a05f4d970f11ed713ecc469671c3f34c7ae189eda47f229c9e9e9c9.jpg)

![78a6388da086c27dd4c24fc88da8b33264e9975af056cd49a0abf2defa93d98b.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/tables/78a6388da086c27dd4c24fc88da8b33264e9975af056cd49a0abf2defa93d98b.jpg)

![89f87b2f22c6510a1094e8ff9b97ac0552a889ced8bdca8b86488bb20cefa562.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/tables/89f87b2f22c6510a1094e8ff9b97ac0552a889ced8bdca8b86488bb20cefa562.jpg)

![8e6d9e9373677671a8ac1323fb344eb2e4e91a2bc704bd914944f273c1bfd1a6.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/tables/8e6d9e9373677671a8ac1323fb344eb2e4e91a2bc704bd914944f273c1bfd1a6.jpg)

![b755965138f3c76833a7b6a01048c2870d5dc55d47aeede67d4314c2c2eacbd8.jpg](../nips_results/1734_Vision%20Function%20Layer%20in%20Multimodal%20LLMs/tables/b755965138f3c76833a7b6a01048c2870d5dc55d47aeede67d4314c2c2eacbd8.jpg)

## VarFlow: Proper Scoring-Rule Diffusion Distillation via Energy Matching


### Images

![1ef2287235d977e1844f38196d25a3a8f2b74c2c9b875394f35548519ff728bc.jpg](../nips_results/1735_VarFlow_%20Proper%20Scoring-Rule%20Diffusion%20Distillation%20via%20Energy%20Matching/images/1ef2287235d977e1844f38196d25a3a8f2b74c2c9b875394f35548519ff728bc.jpg)

![81caad376ae1c7b3b3ae2e100dfc9d57d1fc59c3b21d0133f6bf6656ace8ab68.jpg](../nips_results/1735_VarFlow_%20Proper%20Scoring-Rule%20Diffusion%20Distillation%20via%20Energy%20Matching/images/81caad376ae1c7b3b3ae2e100dfc9d57d1fc59c3b21d0133f6bf6656ace8ab68.jpg)

### Tables

![0cdb8746c355c569f3a5005de382c46bf468380b0dcaa5d242bcefc727032fdd.jpg](../nips_results/1735_VarFlow_%20Proper%20Scoring-Rule%20Diffusion%20Distillation%20via%20Energy%20Matching/tables/0cdb8746c355c569f3a5005de382c46bf468380b0dcaa5d242bcefc727032fdd.jpg)

![121f4b4d2a3e2f412416e0c5e776660eba99b6d68b5fcd0452d5fd67b20dd222.jpg](../nips_results/1735_VarFlow_%20Proper%20Scoring-Rule%20Diffusion%20Distillation%20via%20Energy%20Matching/tables/121f4b4d2a3e2f412416e0c5e776660eba99b6d68b5fcd0452d5fd67b20dd222.jpg)

![bf5ad49432a2adf6562bf43b9c422342e83cf0b584abc7e88891367c9f80cae4.jpg](../nips_results/1735_VarFlow_%20Proper%20Scoring-Rule%20Diffusion%20Distillation%20via%20Energy%20Matching/tables/bf5ad49432a2adf6562bf43b9c422342e83cf0b584abc7e88891367c9f80cae4.jpg)

![e07b49bb73006a2ee27c4cb882d4bbd63097c1a0d02d2fb7bb1734f6c2005509.jpg](../nips_results/1735_VarFlow_%20Proper%20Scoring-Rule%20Diffusion%20Distillation%20via%20Energy%20Matching/tables/e07b49bb73006a2ee27c4cb882d4bbd63097c1a0d02d2fb7bb1734f6c2005509.jpg)

## Evolutionary Reasoning Does Not Arise in Standard Usage of Protein Language Models


### Images

![4745c9e9d1de8d4bd72f55088af9092029d3381398273364d45ac0b82c9bc689.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/images/4745c9e9d1de8d4bd72f55088af9092029d3381398273364d45ac0b82c9bc689.jpg)

![72e46a51ee26f32faf79e8490f0dc9d361594628e18c7c74ac1f376a996d236c.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/images/72e46a51ee26f32faf79e8490f0dc9d361594628e18c7c74ac1f376a996d236c.jpg)

![9e08ac89c3c21630e6da1a071e4cfb5595d25487286ecdad11ed9d06997c7a40.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/images/9e08ac89c3c21630e6da1a071e4cfb5595d25487286ecdad11ed9d06997c7a40.jpg)

![9e88c207ab83ed1ce26074f8277dd4c95d7646eaacff754e93d2b4bbca8909c1.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/images/9e88c207ab83ed1ce26074f8277dd4c95d7646eaacff754e93d2b4bbca8909c1.jpg)

![f2a65b2eb011bb2652dd4624d5dd06c6cca5ba629f931758428ef3e6022cd539.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/images/f2a65b2eb011bb2652dd4624d5dd06c6cca5ba629f931758428ef3e6022cd539.jpg)

### Tables

![010ff9a95d948eb8e0bbeb58cd48b472eba0fd1615b0d30efd6f40a01e2e3a60.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/tables/010ff9a95d948eb8e0bbeb58cd48b472eba0fd1615b0d30efd6f40a01e2e3a60.jpg)

![3e45d5d919b001980cd215a601921ba15aab0a60d09921b7ac845d1c866d7087.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/tables/3e45d5d919b001980cd215a601921ba15aab0a60d09921b7ac845d1c866d7087.jpg)

![52620d15e114c7c179ce2baf4aa4d6e25a1bdba907aea1c6447d83fbe1d6a852.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/tables/52620d15e114c7c179ce2baf4aa4d6e25a1bdba907aea1c6447d83fbe1d6a852.jpg)

![6b76ac69fd2d5ea9586aa1aa2570ed8835746622e9917f8aef5fa8ec5c28b177.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/tables/6b76ac69fd2d5ea9586aa1aa2570ed8835746622e9917f8aef5fa8ec5c28b177.jpg)

![9568cd1f695e3ba1df8d1e5425ce730767189b9504e373794328380b665ce955.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/tables/9568cd1f695e3ba1df8d1e5425ce730767189b9504e373794328380b665ce955.jpg)

![c9d30f254e8db1b9d07d386fc43e96d0905aea79b5d821b8cb6f47441b4a50ab.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/tables/c9d30f254e8db1b9d07d386fc43e96d0905aea79b5d821b8cb6f47441b4a50ab.jpg)

![c9f0838e8064a72358b3624ce73ef54d51ebbb51d2dce1c769c80970cac1c9d4.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/tables/c9f0838e8064a72358b3624ce73ef54d51ebbb51d2dce1c769c80970cac1c9d4.jpg)

![cbd58c8be23b91e219832141c196b77e4720e7f84e588ae28fcc57aa5874115b.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/tables/cbd58c8be23b91e219832141c196b77e4720e7f84e588ae28fcc57aa5874115b.jpg)

![cea7327c62fbf82bd7391321ef66560e86f4989e2b7d163b35e1f0d1f394e0c8.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/tables/cea7327c62fbf82bd7391321ef66560e86f4989e2b7d163b35e1f0d1f394e0c8.jpg)

![dfdf057f44924e2b1b1be4fdc45c076c5cc21540ad6563c08e06bc6d2d27cbfc.jpg](../nips_results/1736_Evolutionary%20Reasoning%20Does%20Not%20Arise%20in%20Standard%20Usage%20of%20Protein%20Language%20Models/tables/dfdf057f44924e2b1b1be4fdc45c076c5cc21540ad6563c08e06bc6d2d27cbfc.jpg)

## Breaking the Compression Ceiling: Data-Free Pipeline for Ultra-Efficient Delta Compression


### Images

![006558f31e412824ca7d9e91ed9f30e0a449cd89bd7361df3777afa590eaf8f1.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/images/006558f31e412824ca7d9e91ed9f30e0a449cd89bd7361df3777afa590eaf8f1.jpg)

![8b404e4d4edfcb5300d39a0a03b4b6c0d975e5f5b5880e73bd60088b7dbfab34.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/images/8b404e4d4edfcb5300d39a0a03b4b6c0d975e5f5b5880e73bd60088b7dbfab34.jpg)

![8b7566511fb0a5ce2120df750d985f0848816faefd0efb9592f4f3259113dbbf.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/images/8b7566511fb0a5ce2120df750d985f0848816faefd0efb9592f4f3259113dbbf.jpg)

![90d96143765dbc479af9321894c4227dd8c6e8ba6dfa5d90439d25ad8c26020c.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/images/90d96143765dbc479af9321894c4227dd8c6e8ba6dfa5d90439d25ad8c26020c.jpg)

![c6b8006e1c2a6bf0b8469e58261829de881e3ae3179b0fb12bde377a81597a33.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/images/c6b8006e1c2a6bf0b8469e58261829de881e3ae3179b0fb12bde377a81597a33.jpg)

![fa55af4af8936a1d3c99b786327c8ec4bb7edeee26d33066f5e561c84cb67820.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/images/fa55af4af8936a1d3c99b786327c8ec4bb7edeee26d33066f5e561c84cb67820.jpg)

### Tables

![1145410da39e2fc6cf1b4cc8d220a849458d91e410742db83db953e9b9c0126c.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/1145410da39e2fc6cf1b4cc8d220a849458d91e410742db83db953e9b9c0126c.jpg)

![12b74913d1d7b209dd80588da0c90c872f553298899a4496bdc9589719588dc3.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/12b74913d1d7b209dd80588da0c90c872f553298899a4496bdc9589719588dc3.jpg)

![2c0a0e2b82b86c9f36635da55d0fe129a8ef4c7202cad37746c642e783bbcbc5.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/2c0a0e2b82b86c9f36635da55d0fe129a8ef4c7202cad37746c642e783bbcbc5.jpg)

![33f13559447d8b55904b54bece3e02be7b09ca323a98ecfe61054d6858741629.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/33f13559447d8b55904b54bece3e02be7b09ca323a98ecfe61054d6858741629.jpg)

![4bce390a6a09c56d08f327bbd73ba92e61ff3b6ad7baa6ac00cee5ea8400aaf8.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/4bce390a6a09c56d08f327bbd73ba92e61ff3b6ad7baa6ac00cee5ea8400aaf8.jpg)

![59928119ee6932d0aaaaf6384fde590a7778c5f68ea22934ace0c0a9d5208aa7.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/59928119ee6932d0aaaaf6384fde590a7778c5f68ea22934ace0c0a9d5208aa7.jpg)

![63d3bdd037a7ffaebb2d797b7f3577c2a974ab088facecd737534fb9f98076e9.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/63d3bdd037a7ffaebb2d797b7f3577c2a974ab088facecd737534fb9f98076e9.jpg)

![644272907d0f03c28a56c876da2a1514c40603d601f4ac2659656d1209bf26b1.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/644272907d0f03c28a56c876da2a1514c40603d601f4ac2659656d1209bf26b1.jpg)

![6798f97971f22856b9fbc3a4f68e902ca52a8c2a7b2381fc6b7b40b6c3a77cec.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/6798f97971f22856b9fbc3a4f68e902ca52a8c2a7b2381fc6b7b40b6c3a77cec.jpg)

![7317f559fe6055cd08ca129ba8a06833929619c72267b936ab95ccdaaaf18328.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/7317f559fe6055cd08ca129ba8a06833929619c72267b936ab95ccdaaaf18328.jpg)

![a83ad288dfc00de43ef22a88c81edb4723c8a4a14d3011d3681ab1c1a3d98202.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/a83ad288dfc00de43ef22a88c81edb4723c8a4a14d3011d3681ab1c1a3d98202.jpg)

![caa7785b1a8378c8776b90ef1051c656244e96a56eb078918cbf99ae4414cbab.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/caa7785b1a8378c8776b90ef1051c656244e96a56eb078918cbf99ae4414cbab.jpg)

![dad6a670c1a4beff218f5392e7a2eda3b4d07fea6e9c02a5e2059775e75275bc.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/dad6a670c1a4beff218f5392e7a2eda3b4d07fea6e9c02a5e2059775e75275bc.jpg)

![fa433b795de897ea2588e64f73b2a3f36fdbe5beebe5fbf5e46a8127ca5db397.jpg](../nips_results/1737_Breaking%20the%20Compression%20Ceiling_%20Data-Free%20Pipeline%20for%20Ultra-Efficient%20Delta%20Compression/tables/fa433b795de897ea2588e64f73b2a3f36fdbe5beebe5fbf5e46a8127ca5db397.jpg)

## Bridging Time and Linguistics: LLMs as Time Series Analyzer through Symbolization and Segmentation


### Images

![21d999d618f444093538b6ad553f1677012ddc0f84fe2e3e678d8db217454b3c.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/21d999d618f444093538b6ad553f1677012ddc0f84fe2e3e678d8db217454b3c.jpg)

![33f3072b4d24b9c97903c26a6313158c4bd4d2eb4356937c1df72b294f49bd7b.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/33f3072b4d24b9c97903c26a6313158c4bd4d2eb4356937c1df72b294f49bd7b.jpg)

![35494686c86b9467ae41170772bddfdfcfc34b89ee6b798b933a64ca1fc045ca.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/35494686c86b9467ae41170772bddfdfcfc34b89ee6b798b933a64ca1fc045ca.jpg)

![39751cf1096b2005b2633f4b6de7ddd875cc0095f03b90c70eb1a753eb1f546e.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/39751cf1096b2005b2633f4b6de7ddd875cc0095f03b90c70eb1a753eb1f546e.jpg)

![58707b323f418f213dce7dc5b72ed4cc937ddd0c72f43b368b2f221401ad5723.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/58707b323f418f213dce7dc5b72ed4cc937ddd0c72f43b368b2f221401ad5723.jpg)

![6826f875009b06d5164374dc4888bd70a7fbb6184328e8bc8c7bb1e81aa76be5.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/6826f875009b06d5164374dc4888bd70a7fbb6184328e8bc8c7bb1e81aa76be5.jpg)

![6d0d443c36a2603ac02a4e22a68676e68276851db24000b31cb44dfe0a34a59f.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/6d0d443c36a2603ac02a4e22a68676e68276851db24000b31cb44dfe0a34a59f.jpg)

![71b03d2caa9b97e08037eac2793d849a8c494d394ef5ee8016db6b5e971185c8.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/71b03d2caa9b97e08037eac2793d849a8c494d394ef5ee8016db6b5e971185c8.jpg)

![7398dc183085278e2e69d277189800b6d7c4df47acec070b218d549ac7cf12b2.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/7398dc183085278e2e69d277189800b6d7c4df47acec070b218d549ac7cf12b2.jpg)

![7dd0a2b7b9df9de180b93d409a1d46539e4f89d94c22b4ee3cf65667dd7699fc.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/7dd0a2b7b9df9de180b93d409a1d46539e4f89d94c22b4ee3cf65667dd7699fc.jpg)

![8de97cbf35eaf0d4fcb744a8f57f54fa41805414f494dc057d5ddd09a4f21017.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/8de97cbf35eaf0d4fcb744a8f57f54fa41805414f494dc057d5ddd09a4f21017.jpg)

![c2c22c0f811e239fd432e119d1371c7ab986482012d3727e3f6812bd0312566b.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/c2c22c0f811e239fd432e119d1371c7ab986482012d3727e3f6812bd0312566b.jpg)

![c357e746c61f8c1b20d493272c62b9b3cf23b99894b39745b1c6f845ec67792b.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/c357e746c61f8c1b20d493272c62b9b3cf23b99894b39745b1c6f845ec67792b.jpg)

![e258b8ca9b7090e5248c57970c602f2e0fd4f706c2f764a4a5dfe815f1576ee0.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/e258b8ca9b7090e5248c57970c602f2e0fd4f706c2f764a4a5dfe815f1576ee0.jpg)

![f7fb6947c1c72e1514c8902ce899f8cf6cb6107fac942f5d1edce3182f438ba1.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/images/f7fb6947c1c72e1514c8902ce899f8cf6cb6107fac942f5d1edce3182f438ba1.jpg)

### Tables

![0365dce1d4057341b79b6f8dad147467a8334bbdcb3d797e8b0a777633a6104e.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/0365dce1d4057341b79b6f8dad147467a8334bbdcb3d797e8b0a777633a6104e.jpg)

![1eab21e746bb39cf9ee4d30df860eb71b475704114a5b14dee732a924cdf1b7d.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/1eab21e746bb39cf9ee4d30df860eb71b475704114a5b14dee732a924cdf1b7d.jpg)

![2918ed27f9300d6f1d69a55143a1586eb9585ad640861cf8215c1a77196f5517.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/2918ed27f9300d6f1d69a55143a1586eb9585ad640861cf8215c1a77196f5517.jpg)

![2a96658d06ed10965ddfdd019dc5dfae5156f30b811009a9ac8e3662404d6541.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/2a96658d06ed10965ddfdd019dc5dfae5156f30b811009a9ac8e3662404d6541.jpg)

![3dff67980e0dfeeb25987749bd1fdc740a0c530db0dacc52f186ce538a4ae29e.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/3dff67980e0dfeeb25987749bd1fdc740a0c530db0dacc52f186ce538a4ae29e.jpg)

![40f805b7f2520e9622abb6915d60662e4c469b130444d8a2cb671de72aa140ce.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/40f805b7f2520e9622abb6915d60662e4c469b130444d8a2cb671de72aa140ce.jpg)

![6c7044b1026b2f5b6e8241b6a577e2c2e64579bfaa39f4cc5df5e265ce1d65b8.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/6c7044b1026b2f5b6e8241b6a577e2c2e64579bfaa39f4cc5df5e265ce1d65b8.jpg)

![6e1d2bc17fca070b7b23b872279d056359ef6d4cee987ff696f9cdb1ac74f9ca.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/6e1d2bc17fca070b7b23b872279d056359ef6d4cee987ff696f9cdb1ac74f9ca.jpg)

![7af928f67057d26ddda7c2f64263c2069b558982b19ee3dc6308d58662c9baa2.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/7af928f67057d26ddda7c2f64263c2069b558982b19ee3dc6308d58662c9baa2.jpg)

![841cbaa33e9e45bb13a4ec239473750966ec0fefc03b5fe8f7d7a092dc3fd11a.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/841cbaa33e9e45bb13a4ec239473750966ec0fefc03b5fe8f7d7a092dc3fd11a.jpg)

![982fa28786abba8a2ac64a82faeb34c6511baca731a137a7b28151d9eb2140da.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/982fa28786abba8a2ac64a82faeb34c6511baca731a137a7b28151d9eb2140da.jpg)

![ab0ce3c799e35fa98da7ceb550fa30debf3941f3f68e4bf6540cfeb7eb4ecfa8.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/ab0ce3c799e35fa98da7ceb550fa30debf3941f3f68e4bf6540cfeb7eb4ecfa8.jpg)

![ae68c5b67e7530e6817ac0d59e522e5e8354e38e43a086215cd818d9b5400b31.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/ae68c5b67e7530e6817ac0d59e522e5e8354e38e43a086215cd818d9b5400b31.jpg)

![c7a3a3d50fbd201096f62bde48abe19cf53f9c8aae423a1f387e1eb5a40a3a23.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/c7a3a3d50fbd201096f62bde48abe19cf53f9c8aae423a1f387e1eb5a40a3a23.jpg)

![f548cd27c58fc717f9852527885cb4254ad1750c616839def64d4cc8e1976ce4.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/f548cd27c58fc717f9852527885cb4254ad1750c616839def64d4cc8e1976ce4.jpg)

![f7f2620ba73615b71bbfdc8f153d41dbd5970eb2b1ed1bbc4343dd238838a0f0.jpg](../nips_results/1738_Bridging%20Time%20and%20Linguistics_%20LLMs%20as%20Time%20Series%20Analyzer%20through%20Symbolization%20and%20Segmentation/tables/f7f2620ba73615b71bbfdc8f153d41dbd5970eb2b1ed1bbc4343dd238838a0f0.jpg)

## C-SafeGen: Certified Safe LLM Generation with Claim-Based Streaming Guardrails


### Images

![71cb3469bd83e3f541ba06281032e356212b458aec0dc29fcde511a74cd556b1.jpg](../nips_results/1739_C-SafeGen_%20Certified%20Safe%20LLM%20Generation%20with%20Claim-Based%20Streaming%20Guardrails/images/71cb3469bd83e3f541ba06281032e356212b458aec0dc29fcde511a74cd556b1.jpg)

![7cd0d48c1bd10778de9a8201ba209a00012697751748c1e6b99b49c88a217cac.jpg](../nips_results/1739_C-SafeGen_%20Certified%20Safe%20LLM%20Generation%20with%20Claim-Based%20Streaming%20Guardrails/images/7cd0d48c1bd10778de9a8201ba209a00012697751748c1e6b99b49c88a217cac.jpg)

![8700f927fe16ce55f9bec34557c85360a291d8ccf5c2c714afe2a71a510bf3f1.jpg](../nips_results/1739_C-SafeGen_%20Certified%20Safe%20LLM%20Generation%20with%20Claim-Based%20Streaming%20Guardrails/images/8700f927fe16ce55f9bec34557c85360a291d8ccf5c2c714afe2a71a510bf3f1.jpg)

![98bd369b1eac4043e85e3f81c757af5b085a46b3ac0daf41ca8cffcc0cf1bfc5.jpg](../nips_results/1739_C-SafeGen_%20Certified%20Safe%20LLM%20Generation%20with%20Claim-Based%20Streaming%20Guardrails/images/98bd369b1eac4043e85e3f81c757af5b085a46b3ac0daf41ca8cffcc0cf1bfc5.jpg)

![a06491eff576a51a82bf59a0681278a43e8d8f802c3f7d3a78ab64bc770abd88.jpg](../nips_results/1739_C-SafeGen_%20Certified%20Safe%20LLM%20Generation%20with%20Claim-Based%20Streaming%20Guardrails/images/a06491eff576a51a82bf59a0681278a43e8d8f802c3f7d3a78ab64bc770abd88.jpg)

![bc2a3cc5a1ad1340b54928c504a0c09a88736a077789cee264af8be45ddf11dc.jpg](../nips_results/1739_C-SafeGen_%20Certified%20Safe%20LLM%20Generation%20with%20Claim-Based%20Streaming%20Guardrails/images/bc2a3cc5a1ad1340b54928c504a0c09a88736a077789cee264af8be45ddf11dc.jpg)

![f8526961573f1e6d72a716ad1398cf6de5c9b9ad7663b3c93201679e22bff79c.jpg](../nips_results/1739_C-SafeGen_%20Certified%20Safe%20LLM%20Generation%20with%20Claim-Based%20Streaming%20Guardrails/images/f8526961573f1e6d72a716ad1398cf6de5c9b9ad7663b3c93201679e22bff79c.jpg)

### Tables

![16f617eef8419c5b50750bd2279bda24e40e9ac6ce2b4444445df5e91fc19c3a.jpg](../nips_results/1739_C-SafeGen_%20Certified%20Safe%20LLM%20Generation%20with%20Claim-Based%20Streaming%20Guardrails/tables/16f617eef8419c5b50750bd2279bda24e40e9ac6ce2b4444445df5e91fc19c3a.jpg)

## Unveiling Environmental Sensitivity of Individual Gains in Influence Maximization


### Images

![3ee2c78f92dd352f3cb06d0206fda5ceee27c5c850016fbd86ec28c48c23020a.jpg](../nips_results/1740_Unveiling%20Environmental%20Sensitivity%20of%20Individual%20Gains%20in%20Influence%20Maximization/images/3ee2c78f92dd352f3cb06d0206fda5ceee27c5c850016fbd86ec28c48c23020a.jpg)

![6251651d69bb1b82a4cb15518ba1ef6abb306bdd514b62b173d725ce5b6f56e7.jpg](../nips_results/1740_Unveiling%20Environmental%20Sensitivity%20of%20Individual%20Gains%20in%20Influence%20Maximization/images/6251651d69bb1b82a4cb15518ba1ef6abb306bdd514b62b173d725ce5b6f56e7.jpg)

![8b5e6f7ab4d22d61c3e194b9c0738e5a51ea316e5a58e9ad713d374d4e7c4165.jpg](../nips_results/1740_Unveiling%20Environmental%20Sensitivity%20of%20Individual%20Gains%20in%20Influence%20Maximization/images/8b5e6f7ab4d22d61c3e194b9c0738e5a51ea316e5a58e9ad713d374d4e7c4165.jpg)

![a86e4d0c9a66c065684e8eeb479bcb2ce718bf1dccf34e42a811edc5121b3764.jpg](../nips_results/1740_Unveiling%20Environmental%20Sensitivity%20of%20Individual%20Gains%20in%20Influence%20Maximization/images/a86e4d0c9a66c065684e8eeb479bcb2ce718bf1dccf34e42a811edc5121b3764.jpg)

![b2850b40c265b0bfa26d0bade352431b461cf3bbe7c7a596e4df5ab475ab70ee.jpg](../nips_results/1740_Unveiling%20Environmental%20Sensitivity%20of%20Individual%20Gains%20in%20Influence%20Maximization/images/b2850b40c265b0bfa26d0bade352431b461cf3bbe7c7a596e4df5ab475ab70ee.jpg)

![e08a8182cbc8e490f239e4354fc9340f84f58351615f11e258ef04d79eccd916.jpg](../nips_results/1740_Unveiling%20Environmental%20Sensitivity%20of%20Individual%20Gains%20in%20Influence%20Maximization/images/e08a8182cbc8e490f239e4354fc9340f84f58351615f11e258ef04d79eccd916.jpg)

### Tables

![402a78af4a253d21a7974e1c1002b573288a1b33adbbed6c13410cf044a49855.jpg](../nips_results/1740_Unveiling%20Environmental%20Sensitivity%20of%20Individual%20Gains%20in%20Influence%20Maximization/tables/402a78af4a253d21a7974e1c1002b573288a1b33adbbed6c13410cf044a49855.jpg)

![5a11de6ba1f9bd72657e97b00c8990c6d48fcadc6bfc604cb6dcaa471df91998.jpg](../nips_results/1740_Unveiling%20Environmental%20Sensitivity%20of%20Individual%20Gains%20in%20Influence%20Maximization/tables/5a11de6ba1f9bd72657e97b00c8990c6d48fcadc6bfc604cb6dcaa471df91998.jpg)

![78a663ccb66a0cc38e9f40f746c54ab4ace6e8b9ed01f1b9fcd5ce4f86b5938f.jpg](../nips_results/1740_Unveiling%20Environmental%20Sensitivity%20of%20Individual%20Gains%20in%20Influence%20Maximization/tables/78a663ccb66a0cc38e9f40f746c54ab4ace6e8b9ed01f1b9fcd5ce4f86b5938f.jpg)

![7a85ee23a98c523b52c6e170344a326ba6c50706fa2b905d04faada05facff16.jpg](../nips_results/1740_Unveiling%20Environmental%20Sensitivity%20of%20Individual%20Gains%20in%20Influence%20Maximization/tables/7a85ee23a98c523b52c6e170344a326ba6c50706fa2b905d04faada05facff16.jpg)

![c606ca43bfe51db358f8a11f3167bcdc73cc84b20de971cd6512661eeac43ce2.jpg](../nips_results/1740_Unveiling%20Environmental%20Sensitivity%20of%20Individual%20Gains%20in%20Influence%20Maximization/tables/c606ca43bfe51db358f8a11f3167bcdc73cc84b20de971cd6512661eeac43ce2.jpg)

## Multivariate Latent Recalibration for Conditional Normalizing Flows


### Images

![0645c3cd56fc5f5edfc211039942b6ac79a2fea023458a9061f4b4a38ea175bf.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/0645c3cd56fc5f5edfc211039942b6ac79a2fea023458a9061f4b4a38ea175bf.jpg)

![0b379dbe13f8e307f1ac05ee6cf407041399bbcc822d637f495e3fc759105ccc.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/0b379dbe13f8e307f1ac05ee6cf407041399bbcc822d637f495e3fc759105ccc.jpg)

![19ae0730cc368a2785cdaa7e81aaedd555b95162fd35979f329287d7351836b0.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/19ae0730cc368a2785cdaa7e81aaedd555b95162fd35979f329287d7351836b0.jpg)

![1f07a0ead34d89d06182c0a57d94a1a2feb4d306e752528d9491917269851b4f.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/1f07a0ead34d89d06182c0a57d94a1a2feb4d306e752528d9491917269851b4f.jpg)

![210dddf4437c15bf3555c37122b526a22ecffe03616500a812262d723a9f1927.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/210dddf4437c15bf3555c37122b526a22ecffe03616500a812262d723a9f1927.jpg)

![34ed165a3ce05e0b59a7596afec23d4ea97c314a329210aa43efd1c329b0a69a.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/34ed165a3ce05e0b59a7596afec23d4ea97c314a329210aa43efd1c329b0a69a.jpg)

![6575c381cb665e128bef0d776349c37a1bb096ab1b0688e697df8f09da3d97f3.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/6575c381cb665e128bef0d776349c37a1bb096ab1b0688e697df8f09da3d97f3.jpg)

![7dec0efe6fb3592f0766f447404e04cc9514d797097ae734bdadc6ad92081d1c.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/7dec0efe6fb3592f0766f447404e04cc9514d797097ae734bdadc6ad92081d1c.jpg)

![874eb6267a23982fa0055c6ed8cb8ef92f7fb8b34bf7aef9b7a11e1986d24654.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/874eb6267a23982fa0055c6ed8cb8ef92f7fb8b34bf7aef9b7a11e1986d24654.jpg)

![9a4054c808e5097386467aa79482ec310f776ec1128d5aa35b7f6377d3a82496.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/9a4054c808e5097386467aa79482ec310f776ec1128d5aa35b7f6377d3a82496.jpg)

![cff39da0e177cd4bde602608ccf05db61992aeeb93fc1acd441bf4d600d09f47.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/cff39da0e177cd4bde602608ccf05db61992aeeb93fc1acd441bf4d600d09f47.jpg)

![d58a92dca1085c69605b25f5219f8cd7bec50f4e843086c83913d2f443c94e2d.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/d58a92dca1085c69605b25f5219f8cd7bec50f4e843086c83913d2f443c94e2d.jpg)

![d5e54543d591b6a602a24717d066eaeda2a798312f6ecb584d0e74ffeb5eaffe.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/d5e54543d591b6a602a24717d066eaeda2a798312f6ecb584d0e74ffeb5eaffe.jpg)

![e0fef5d645be674eb38a12664e525922c0316a48e914c68572db984aea3b5fe3.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/e0fef5d645be674eb38a12664e525922c0316a48e914c68572db984aea3b5fe3.jpg)

![f88fa4e292a00594abd03012a8c51a163c8a152280f5387a2af55542479dc9e3.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/images/f88fa4e292a00594abd03012a8c51a163c8a152280f5387a2af55542479dc9e3.jpg)

### Tables

![057e39734ae252537045599e46bbaa59cbc0fa3b53f12c7da539ed5130ab5043.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/057e39734ae252537045599e46bbaa59cbc0fa3b53f12c7da539ed5130ab5043.jpg)

![273d3e8e64ef17b0f3e88a6fb05014c80af4d295912b64ff34a6f6b34c1a98cc.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/273d3e8e64ef17b0f3e88a6fb05014c80af4d295912b64ff34a6f6b34c1a98cc.jpg)

![3fc993547aba8b45ffb55efb01d3c855cdb286c9eb9b8b26a91c10a411d91231.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/3fc993547aba8b45ffb55efb01d3c855cdb286c9eb9b8b26a91c10a411d91231.jpg)

![4096acad2ea623cdd708ac3917b878ee058d4317145edfe57de23570db50afce.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/4096acad2ea623cdd708ac3917b878ee058d4317145edfe57de23570db50afce.jpg)

![46b6d0d30c67df74732a16d64421bbc8150c1adcc2637559aa0cd738cea81d0f.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/46b6d0d30c67df74732a16d64421bbc8150c1adcc2637559aa0cd738cea81d0f.jpg)

![4d2fa82dbaf1fe70da6168d91bf9f7211132c674fffbe3df37af6de1349fc27f.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/4d2fa82dbaf1fe70da6168d91bf9f7211132c674fffbe3df37af6de1349fc27f.jpg)

![5b331f96b015f025646691d4ad99bc16be057d58dd246bddc1e8e2e26957b5b6.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/5b331f96b015f025646691d4ad99bc16be057d58dd246bddc1e8e2e26957b5b6.jpg)

![6aef872f800d7f8732749796a71649fbc23d055f102511d578ad56948cbf32e1.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/6aef872f800d7f8732749796a71649fbc23d055f102511d578ad56948cbf32e1.jpg)

![7cfaf6ad50eadfb6c577b7a26befe14a434338d423b3fec3c4e4198f2414d9f4.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/7cfaf6ad50eadfb6c577b7a26befe14a434338d423b3fec3c4e4198f2414d9f4.jpg)

![8c89481f7a6bfc025ee36a0f3b7980365a7c6996768eb02bcd5ed6cafd676da5.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/8c89481f7a6bfc025ee36a0f3b7980365a7c6996768eb02bcd5ed6cafd676da5.jpg)

![9c349d894fdb973d1e5a21b4c6126c4fd8a3522dafd165545bcd2fe2ab6a8ff8.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/9c349d894fdb973d1e5a21b4c6126c4fd8a3522dafd165545bcd2fe2ab6a8ff8.jpg)

![b2f7d65f41ea3ac295c29bec91de9a18bd97e764b1768f7c7d3c8e1ee390e452.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/b2f7d65f41ea3ac295c29bec91de9a18bd97e764b1768f7c7d3c8e1ee390e452.jpg)

![c455a0b436c7b71a76add94bcbefa6dfae3048d22fbe42571654acedea932c95.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/c455a0b436c7b71a76add94bcbefa6dfae3048d22fbe42571654acedea932c95.jpg)

![cb4f2be4e390e9c4140aa869623514b2bd068a6919a4df9903f9486ee9395505.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/cb4f2be4e390e9c4140aa869623514b2bd068a6919a4df9903f9486ee9395505.jpg)

![d16924eff1b7e769116d63062747cfd710445bb2b9647ed90c3c5484447c823b.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/d16924eff1b7e769116d63062747cfd710445bb2b9647ed90c3c5484447c823b.jpg)

![e2161fce89bc0cb9b96493d44e32220eae4f5b353927c4419c1f4890bb2f7b5b.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/e2161fce89bc0cb9b96493d44e32220eae4f5b353927c4419c1f4890bb2f7b5b.jpg)

![ed1f8ab5a6f37703de081b52f9adde3936e3055d85fc6ebdc063a442a4a0053a.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/ed1f8ab5a6f37703de081b52f9adde3936e3055d85fc6ebdc063a442a4a0053a.jpg)

![f3e2f972665ed8fb15c75d221b01437cb2ed48dabdfd0280dbeb058000b2d394.jpg](../nips_results/1741_Multivariate%20Latent%20Recalibration%20for%20Conditional%20Normalizing%20Flows/tables/f3e2f972665ed8fb15c75d221b01437cb2ed48dabdfd0280dbeb058000b2d394.jpg)

## Dynamics of Spontaneous Topic Changes in Next Token Prediction with Self-Attention


### Images

![2f8569de92e229589e9a6e6b13ab0910b3c00cdf72aa05974556c924add72be4.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/images/2f8569de92e229589e9a6e6b13ab0910b3c00cdf72aa05974556c924add72be4.jpg)

![37a3c509ab71c9af6a01edf0ba529e90c067133d9ba5a37309f0b3bfda0735d3.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/images/37a3c509ab71c9af6a01edf0ba529e90c067133d9ba5a37309f0b3bfda0735d3.jpg)

![5d8db8a95e468a97c4706260b23c3e30769548d6bc489751fe345a8f0447385a.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/images/5d8db8a95e468a97c4706260b23c3e30769548d6bc489751fe345a8f0447385a.jpg)

![81c62f67ab193654489a4d6ac6dab1deb2e4b83ef8f1f466373179678c90f889.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/images/81c62f67ab193654489a4d6ac6dab1deb2e4b83ef8f1f466373179678c90f889.jpg)

![8f93a07f1acb6d2fb5d4c2e1629aa9ae6020947af8e2c0f7b11dee963cebb874.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/images/8f93a07f1acb6d2fb5d4c2e1629aa9ae6020947af8e2c0f7b11dee963cebb874.jpg)

![935cf5b0b4d68aeafac4ddf1b8370e574ca41d5fe7dee41488481af753f800bd.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/images/935cf5b0b4d68aeafac4ddf1b8370e574ca41d5fe7dee41488481af753f800bd.jpg)

![b76917295067fd8a6833f0625eb9b3232cb8503fc7304f90cf3df95ed0bbba7f.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/images/b76917295067fd8a6833f0625eb9b3232cb8503fc7304f90cf3df95ed0bbba7f.jpg)

![ce8614c6fed00c05b09d18ba6fba4ceea9e348008c44a4d45885bb80f49eb556.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/images/ce8614c6fed00c05b09d18ba6fba4ceea9e348008c44a4d45885bb80f49eb556.jpg)

![d63a4df62c9e176dc6a0f4b3fc260114592b9fe8aeb6fd23bf121f911aafcf73.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/images/d63a4df62c9e176dc6a0f4b3fc260114592b9fe8aeb6fd23bf121f911aafcf73.jpg)

![dfe814b8c636690221e623f5e0dccdf23bd472f99523e906c1f91329ad2750e9.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/images/dfe814b8c636690221e623f5e0dccdf23bd472f99523e906c1f91329ad2750e9.jpg)

![e210e6d7c3da329bf8ded3a61c939dfbabf6704ae37b8d10c49dd8a269692c12.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/images/e210e6d7c3da329bf8ded3a61c939dfbabf6704ae37b8d10c49dd8a269692c12.jpg)

### Tables

![205addbfd9f195548c6a82414b0fc7a010f41c9a0c64b9ca34dfac0d33259901.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/tables/205addbfd9f195548c6a82414b0fc7a010f41c9a0c64b9ca34dfac0d33259901.jpg)

![9370762d983e61a932c584fc3028a82a603846b5b8b443c997945e0a2c9f9f5e.jpg](../nips_results/1742_Dynamics%20of%20Spontaneous%20Topic%20Changes%20in%20Next%20Token%20Prediction%20with%20Self-Attention/tables/9370762d983e61a932c584fc3028a82a603846b5b8b443c997945e0a2c9f9f5e.jpg)

## Identifying Macro Causal Effects in C-DMGs over DMGs


### Images

![038b824257e231f45397235d5acc932e310109c12deb01a48f67cae247c9016c.jpg](../nips_results/1743_Identifying%20Macro%20Causal%20Effects%20in%20C-DMGs%20over%20DMGs/images/038b824257e231f45397235d5acc932e310109c12deb01a48f67cae247c9016c.jpg)

![14ef00abf9219fad65c00802c1b3df1396acfb05c084273e465f5f86f467b898.jpg](../nips_results/1743_Identifying%20Macro%20Causal%20Effects%20in%20C-DMGs%20over%20DMGs/images/14ef00abf9219fad65c00802c1b3df1396acfb05c084273e465f5f86f467b898.jpg)

![19cf5bfc9d460b795d7a9403bb13d37cb4e36b273f19cd9ec126f0566a6efa39.jpg](../nips_results/1743_Identifying%20Macro%20Causal%20Effects%20in%20C-DMGs%20over%20DMGs/images/19cf5bfc9d460b795d7a9403bb13d37cb4e36b273f19cd9ec126f0566a6efa39.jpg)

![6d2772a86f4b78e228385410fe2d12c53a740789b8e7e88dd9c6239a701f5dc2.jpg](../nips_results/1743_Identifying%20Macro%20Causal%20Effects%20in%20C-DMGs%20over%20DMGs/images/6d2772a86f4b78e228385410fe2d12c53a740789b8e7e88dd9c6239a701f5dc2.jpg)

## Learning Temporal 3D Semantic Scene Completion via Optical Flow Guidance


### Images

![0fe6462abce53f1f999db4699aa838016bfbb39feb8de35acade600bc4c535b3.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/images/0fe6462abce53f1f999db4699aa838016bfbb39feb8de35acade600bc4c535b3.jpg)

![382c29ef3578f1dd9557764978517119ca395ce678f9d156b73924eb807d8c66.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/images/382c29ef3578f1dd9557764978517119ca395ce678f9d156b73924eb807d8c66.jpg)

![38ffc72614d0547e4a37fdbc7593fe1d60c3d83f8d402eb539a89c9faeaf7482.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/images/38ffc72614d0547e4a37fdbc7593fe1d60c3d83f8d402eb539a89c9faeaf7482.jpg)

![43f906e35f4c50279418973e980bfa1c9712fd41019c925a1de121c3d5cf375d.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/images/43f906e35f4c50279418973e980bfa1c9712fd41019c925a1de121c3d5cf375d.jpg)

![58c992f849ce58186c3cb6c460e8a484979aa4556ad011166774bc5d139a325c.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/images/58c992f849ce58186c3cb6c460e8a484979aa4556ad011166774bc5d139a325c.jpg)

![63fcd17f527563c1fb7131c85d5e718de8d6a6060dd1334a2c3d04ff446f3987.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/images/63fcd17f527563c1fb7131c85d5e718de8d6a6060dd1334a2c3d04ff446f3987.jpg)

![9837286efdff662b0639e98c17eecbd2866520ed92c34d448c4fa8bbd652eba2.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/images/9837286efdff662b0639e98c17eecbd2866520ed92c34d448c4fa8bbd652eba2.jpg)

![a5a381d78252e3395f6940c4c76bd4d369bdbf921499a0e9d0db8eae6eb359b1.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/images/a5a381d78252e3395f6940c4c76bd4d369bdbf921499a0e9d0db8eae6eb359b1.jpg)

![d9833079b2fe4965835730d5e814cba7bafd8af228d4fcc0f2b858f1078c00cc.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/images/d9833079b2fe4965835730d5e814cba7bafd8af228d4fcc0f2b858f1078c00cc.jpg)

![fb5288b9f78d666264a9b3bec253dd926377e6d480c5daf6f5fc46bc173c4fcb.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/images/fb5288b9f78d666264a9b3bec253dd926377e6d480c5daf6f5fc46bc173c4fcb.jpg)

### Tables

![16ae3f1d45fb521927243198c36b4e84807b404b6c19f8068366a9d3c6ab030f.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/16ae3f1d45fb521927243198c36b4e84807b404b6c19f8068366a9d3c6ab030f.jpg)

![18c614202113787a817a96bcca655b3f412f7aee3d63b0946b350db1ba5e235e.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/18c614202113787a817a96bcca655b3f412f7aee3d63b0946b350db1ba5e235e.jpg)

![1a6c70779f23f39a70e80da08b72d521a993ec12145a9321323e7728fc549816.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/1a6c70779f23f39a70e80da08b72d521a993ec12145a9321323e7728fc549816.jpg)

![1ffdfd3a8bf64efccb7ba438a41f72847ba37e9cc335fa5928eb583392c4318c.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/1ffdfd3a8bf64efccb7ba438a41f72847ba37e9cc335fa5928eb583392c4318c.jpg)

![330c9f59d705157a36771c7e7cea654fe1eaae7dcf676e2d82f493bdbbddca27.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/330c9f59d705157a36771c7e7cea654fe1eaae7dcf676e2d82f493bdbbddca27.jpg)

![426aef9c994ac82c78068eba76de3a9d334877caa3dd6f21e4a9a1319e91f0f3.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/426aef9c994ac82c78068eba76de3a9d334877caa3dd6f21e4a9a1319e91f0f3.jpg)

![53f7586fa59fc395d2a5f1c0fa12bf553e00dff291973c2e1d3659208831955d.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/53f7586fa59fc395d2a5f1c0fa12bf553e00dff291973c2e1d3659208831955d.jpg)

![6a8a84fc5f8e386b9dcbd5322801c07619323099ed0b3a31e40a2f7f21952b15.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/6a8a84fc5f8e386b9dcbd5322801c07619323099ed0b3a31e40a2f7f21952b15.jpg)

![7194e0c7f74ebe2591740822a4d101043345f1614060eec4f17ccfb8c56131a7.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/7194e0c7f74ebe2591740822a4d101043345f1614060eec4f17ccfb8c56131a7.jpg)

![87f7b26780153d35e39323a70d86fc930a038b9b5f682384823dac00cdb6701b.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/87f7b26780153d35e39323a70d86fc930a038b9b5f682384823dac00cdb6701b.jpg)

![a00c2caaf5820a0aef88aea88ef11a2184f352714f9bcc879c124fe8096d2187.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/a00c2caaf5820a0aef88aea88ef11a2184f352714f9bcc879c124fe8096d2187.jpg)

![b4699adfb377ee9c638f0f33af2fcfff96fe2dd6c0a7bbb5a92dfe5c6dbfe190.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/b4699adfb377ee9c638f0f33af2fcfff96fe2dd6c0a7bbb5a92dfe5c6dbfe190.jpg)

![c6f0bef932ea555201679130f788a123389560b45acdbdb9722d1379c3b5fb58.jpg](../nips_results/1744_Learning%20Temporal%203D%20Semantic%20Scene%20Completion%20via%20Optical%20Flow%20Guidance/tables/c6f0bef932ea555201679130f788a123389560b45acdbdb9722d1379c3b5fb58.jpg)

## Learning to Watermark: A Selective Watermarking Framework for Large Language Models via Multi-Objective Optimization


### Images

![325d93eb05bf998f37e27d0f07a457f919b59ef9d127d1b40adaeab302188a1b.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/images/325d93eb05bf998f37e27d0f07a457f919b59ef9d127d1b40adaeab302188a1b.jpg)

![57ddb4187ae20b750b8236c1713cb032b7c2228cf565a3a613d42f462619ec38.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/images/57ddb4187ae20b750b8236c1713cb032b7c2228cf565a3a613d42f462619ec38.jpg)

![86b1ac1c3ec51d421ca8817d9668e4333c0641d6962827f3b23ba9347b1f4522.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/images/86b1ac1c3ec51d421ca8817d9668e4333c0641d6962827f3b23ba9347b1f4522.jpg)

![8a1b349d533cea7c2919106f36c8e287be3158bdde47c30da8676401bd186fe1.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/images/8a1b349d533cea7c2919106f36c8e287be3158bdde47c30da8676401bd186fe1.jpg)

![97e13ca41b42626571ebddd5e23022edfb20461264513e8cdc9489ed812dc686.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/images/97e13ca41b42626571ebddd5e23022edfb20461264513e8cdc9489ed812dc686.jpg)

![b66a4a87c4a65f1ad2975f1311148b5332de98be4c2e8eee87f94ffcce1e2a1d.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/images/b66a4a87c4a65f1ad2975f1311148b5332de98be4c2e8eee87f94ffcce1e2a1d.jpg)

![b6f1222fa77c973ef43c44d020acb5e17e941308403a1f93d0ccb5ca33c3484e.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/images/b6f1222fa77c973ef43c44d020acb5e17e941308403a1f93d0ccb5ca33c3484e.jpg)

![ba11f37a21629c7e8d00e2acc4f381bc160c176041eadddd48b882da2b3ac790.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/images/ba11f37a21629c7e8d00e2acc4f381bc160c176041eadddd48b882da2b3ac790.jpg)

![e77148af8095fde05d96787d1fdf04cfd333aedd38d4a5abad6f7b2ea5a805ce.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/images/e77148af8095fde05d96787d1fdf04cfd333aedd38d4a5abad6f7b2ea5a805ce.jpg)

![f3d24863611c4c8f4cd61351a1051b9b6c492facd9da259b9a35c878311af64a.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/images/f3d24863611c4c8f4cd61351a1051b9b6c492facd9da259b9a35c878311af64a.jpg)

![fb3db5ddc293bb2953a46bab96c8a8f92fb3197d93c4e446576a73308e66eccf.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/images/fb3db5ddc293bb2953a46bab96c8a8f92fb3197d93c4e446576a73308e66eccf.jpg)

### Tables

![4c2eb5c3c7d372e36aaa9c301d8a8055904bd1d592525ec30319d3318f1603c6.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/tables/4c2eb5c3c7d372e36aaa9c301d8a8055904bd1d592525ec30319d3318f1603c6.jpg)

![5aa06336fc0f68a83a54ef56766784f47f7f34e30ef8146ca2236050c43086fc.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/tables/5aa06336fc0f68a83a54ef56766784f47f7f34e30ef8146ca2236050c43086fc.jpg)

![f1d8ded43d25b03457d21f5497476b9f1a7c54b5d5a3d059a28842cb2088ca72.jpg](../nips_results/1745_Learning%20to%20Watermark_%20A%20Selective%20Watermarking%20Framework%20for%20Large%20Language%20Models%20via%20Multi-Object/tables/f1d8ded43d25b03457d21f5497476b9f1a7c54b5d5a3d059a28842cb2088ca72.jpg)

## Walking the Schrödinger Bridge: A Direct Trajectory for Text-to-3D Generation

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
