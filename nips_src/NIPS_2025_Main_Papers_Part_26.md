# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 26 of 130

## 目录 (Table of Contents)

1. [ProSpero: Active Learning for Robust Protein Design Beyond Wild-Type Neighborhoods](#ProSpero-Active-Learning-for-Robust-Protein-Design-Beyond-Wild-Type-Neighborhoods)
2. [RoME: Domain-Robust Mixture-of-Experts for MILP Solution Prediction across Domains](#RoME-Domain-Robust-Mixture-of-Experts-for-MILP-Solution-Prediction-across-Domains)
3. [Moment- and Power-Spectrum-Based Gaussianity Regularization for Text-to-Image Models](#Moment-and-Power-Spectrum-Based-Gaussianity-Regularization-for-Text-to-Image-Models)
4. [Distance Adaptive Beam Search for Provably Accurate Graph-Based Nearest Neighbor Search](#Distance-Adaptive-Beam-Search-for-Provably-Accurate-Graph-Based-Nearest-Neighbor-Search)
5. [Active Target Discovery under Uninformative Priors: The Power of Permanent and Transient Memory](#Active-Target-Discovery-under-Uninformative-Priors-The-Power-of-Permanent-and-Transient-Memory)
6. [S-GRPO: Early Exit via Reinforcement Learning in Reasoning Models](#S-GRPO-Early-Exit-via-Reinforcement-Learning-in-Reasoning-Models)
7. [FastDINOv2: Frequency Based Curriculum Learning Improves Robustness and Training Speed](#FastDINOv2-Frequency-Based-Curriculum-Learning-Improves-Robustness-and-Training-Speed)
8. [Active Seriation: Efficient Ordering Recovery with Statistical Guarantees](#Active-Seriation-Efficient-Ordering-Recovery-with-Statistical-Guarantees)
9. [MESS+: Dynamically Learned Inference-Time LLM Routing in Model Zoos with Service Level Guarantees](#MESS-Dynamically-Learned-Inference-Time-LLM-Routing-in-Model-Zoos-with-Service-Level-Guarantees)
10. [Mixture of Noise for Pre-Trained Model-Based Class-Incremental Learning](#Mixture-of-Noise-for-Pre-Trained-Model-Based-Class-Incremental-Learning)
11. [Segment Anything Model Meets Semi-supervised Medical Image Segmentation: A Novel Perspective](#Segment-Anything-Model-Meets-Semi-supervised-Medical-Image-Segmentation-A-Novel-Perspective)
12. [TaDiCodec: Text-aware Diffusion Speech Tokenizer for Speech Language Modeling](#TaDiCodec-Text-aware-Diffusion-Speech-Tokenizer-for-Speech-Language-Modeling)
13. [Salient Concept-Aware Generative Data Augmentation](#Salient-Concept-Aware-Generative-Data-Augmentation)
14. [The Mirage of Performance Gains: Why Contrastive Decoding Fails to Mitigate Object Hallucinations in MLLMs?](#The-Mirage-of-Performance-Gains-Why-Contrastive-Decoding-Fails-to-Mitigate-Object-Hallucinations-in-MLLMs)
15. [UnCLe: Towards Scalable Dynamic Causal Discovery in Non-linear Temporal Systems](#UnCLe-Towards-Scalable-Dynamic-Causal-Discovery-in-Non-linear-Temporal-Systems)
16. [Regression Trees Know Calculus](#Regression-Trees-Know-Calculus)
17. [Model-Informed Flows for Bayesian Inference](#Model-Informed-Flows-for-Bayesian-Inference)
18. [Towards 3D Objectness Learning in an Open World](#Towards-3D-Objectness-Learning-in-an-Open-World)
19. [SpecReason: Fast and Accurate Inference-Time Compute via Speculative Reasoning](#SpecReason-Fast-and-Accurate-Inference-Time-Compute-via-Speculative-Reasoning)
20. [Solving Inverse Problems with FLAIR](#Solving-Inverse-Problems-with-FLAIR)
21. [CLIPTTA: Robust Contrastive Vision-Language Test-Time Adaptation](#CLIPTTA-Robust-Contrastive-Vision-Language-Test-Time-Adaptation)
22. [Venus-MAXWELL: Efficient Learning of Protein-Mutation Stability Landscapes using Protein Language Models](#Venus-MAXWELL-Efficient-Learning-of-Protein-Mutation-Stability-Landscapes-using-Protein-Language-Models)
23. [Principled Model Routing for Unknown Mixtures of Source Domains](#Principled-Model-Routing-for-Unknown-Mixtures-of-Source-Domains)
24. [Latent Harmony: Synergistic Unified UHD Image Restoration via Latent Space Regularization and Controllable Refinement](#Latent-Harmony-Synergistic-Unified-UHD-Image-Restoration-via-Latent-Space-Regularization-and-Controllable-Refinement)
25. [SpaceServe: Spatial Multiplexing of Complementary Encoders and Decoders for Multimodal LLMs](#SpaceServe-Spatial-Multiplexing-of-Complementary-Encoders-and-Decoders-for-Multimodal-LLMs)
26. [Lyapunov-Stable Adaptive Control for Multimodal Concept Drift](#Lyapunov-Stable-Adaptive-Control-for-Multimodal-Concept-Drift)
27. [Beyond Higher Rank: Token-wise Input-Output Projections for Efficient Low-Rank Adaptation](#Beyond-Higher-Rank-Token-wise-Input-Output-Projections-for-Efficient-Low-Rank-Adaptation)
28. [Large Stepsizes Accelerate Gradient Descent for Regularized Logistic Regression](#Large-Stepsizes-Accelerate-Gradient-Descent-for-Regularized-Logistic-Regression)
29. [Preference-Based Dynamic Ranking Structure Recognition](#Preference-Based-Dynamic-Ranking-Structure-Recognition)
30. [Multivariate Time Series Anomaly Detection with Idempotent Reconstruction](#Multivariate-Time-Series-Anomaly-Detection-with-Idempotent-Reconstruction)
31. [Understanding Bias Terms in Neural Representations](#Understanding-Bias-Terms-in-Neural-Representations)
32. [Adversarial Graph Fusion for Incomplete Multi-view Semi-supervised Learning with Tensorial Imputation](#Adversarial-Graph-Fusion-for-Incomplete-Multi-view-Semi-supervised-Learning-with-Tensorial-Imputation)
33. [Document Summarization with Conformal Importance Guarantees](#Document-Summarization-with-Conformal-Importance-Guarantees)
34. [Reasoning Models Sometimes Output Illegible Chains of Thought](#Reasoning-Models-Sometimes-Output-Illegible-Chains-of-Thought)
35. [Prot2Text-V2: Protein Function Prediction with Multimodal Contrastive Alignment](#Prot2Text-V2-Protein-Function-Prediction-with-Multimodal-Contrastive-Alignment)
36. [Normalize Filters! Classical Wisdom for Deep Vision](#Normalize-Filters-Classical-Wisdom-for-Deep-Vision)
37. [STRIDER: Navigation via Instruction-Aligned Structural Decision Space Optimization](#STRIDER-Navigation-via-Instruction-Aligned-Structural-Decision-Space-Optimization)
38. [Connectome-Based Modelling Reveals Orientation Maps in the Drosophila Optic Lobe](#Connectome-Based-Modelling-Reveals-Orientation-Maps-in-the-Drosophila-Optic-Lobe)
39. [Efficient Utility-Preserving Machine Unlearning with Implicit Gradient Surgery](#Efficient-Utility-Preserving-Machine-Unlearning-with-Implicit-Gradient-Surgery)
40. [HOComp: Interaction-Aware Human-Object Composition](#HOComp-Interaction-Aware-Human-Object-Composition)
41. [Differentially Private High-dimensional Variable Selection via Integer Programming](#Differentially-Private-High-dimensional-Variable-Selection-via-Integer-Programming)

---


## ProSpero: Active Learning for Robust Protein Design Beyond Wild-Type Neighborhoods

### Images

![0a042c5a170f7ebeb88525dd5377964b9c067c48366f33f76698d4734e9a9a24.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/images/0a042c5a170f7ebeb88525dd5377964b9c067c48366f33f76698d4734e9a9a24.jpg)

![2efca8a573d4b7a6d933e9d633ed3f91da051e00ac9eced32f6597dc5fe47e3e.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/images/2efca8a573d4b7a6d933e9d633ed3f91da051e00ac9eced32f6597dc5fe47e3e.jpg)

![71ebd4cd22efa383f8c1f572a69c513b8463605244df4dd4a89b292fd48129b3.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/images/71ebd4cd22efa383f8c1f572a69c513b8463605244df4dd4a89b292fd48129b3.jpg)

![982b40972862819a8da0d05971da56f309833acdac2db0aaa304651b4d5e05b1.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/images/982b40972862819a8da0d05971da56f309833acdac2db0aaa304651b4d5e05b1.jpg)

![98bbe89c0e3dbca1a045f179cce42547e639b04cf7f228ac2efe6ddcd8a3cb86.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/images/98bbe89c0e3dbca1a045f179cce42547e639b04cf7f228ac2efe6ddcd8a3cb86.jpg)

![d136c936bfcd569a56d7a4f3052497cd1009d47a1cbf2356188adc744a465b71.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/images/d136c936bfcd569a56d7a4f3052497cd1009d47a1cbf2356188adc744a465b71.jpg)

![d4c02c5ce59b82832107727ad7868ceae640d599d08bb8d4b6cf2b7bfaa8739f.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/images/d4c02c5ce59b82832107727ad7868ceae640d599d08bb8d4b6cf2b7bfaa8739f.jpg)

![eabbe6b4b55cd0ced867cb366655118f9111923893cc201c79a23b3f5566b7ea.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/images/eabbe6b4b55cd0ced867cb366655118f9111923893cc201c79a23b3f5566b7ea.jpg)

### Tables

![3e28a232d14528d3b465ea6e3878e1a405b25912aa0235f96f2af5a4e0673712.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/tables/3e28a232d14528d3b465ea6e3878e1a405b25912aa0235f96f2af5a4e0673712.jpg)

![6e52161df34895d99923e71bc9e3f466b8decf1f9633d264f417824a23c5f6ad.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/tables/6e52161df34895d99923e71bc9e3f466b8decf1f9633d264f417824a23c5f6ad.jpg)

![8726ca7bb6ee67b01765e190be5bf039e66c076c3d0d25531cc8646dfa99aef1.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/tables/8726ca7bb6ee67b01765e190be5bf039e66c076c3d0d25531cc8646dfa99aef1.jpg)

![9ac52f5bc349994ea9bddea3e0c9fe753f2316751a90c42ad3752909dc8c074d.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/tables/9ac52f5bc349994ea9bddea3e0c9fe753f2316751a90c42ad3752909dc8c074d.jpg)

![9d86ac207f28ede536fac3cb0068dcc28b4381bb742552e986ff7311c8286e33.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/tables/9d86ac207f28ede536fac3cb0068dcc28b4381bb742552e986ff7311c8286e33.jpg)

![d251a3cdfbb6fe80c20e4fdb3c646e7953247e5a22f349f6dd8930257e8d7ba8.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/tables/d251a3cdfbb6fe80c20e4fdb3c646e7953247e5a22f349f6dd8930257e8d7ba8.jpg)

![df132748ae21ae0cd21cfd9296c94c4bc03a49295a7c931514127a43e6777275.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/tables/df132748ae21ae0cd21cfd9296c94c4bc03a49295a7c931514127a43e6777275.jpg)

![fa3dda12276eec5097444999fd53136888e47febe3758cc81d033a5cb5aa3fa4.jpg](../nips_results/1044_Multi-scale%20Temporal%20Prediction%20via%20Incremental%20Generation%20and%20Multi-agent%20Collaboration/tables/fa3dda12276eec5097444999fd53136888e47febe3758cc81d033a5cb5aa3fa4.jpg)

## ProSpero: Active Learning for Robust Protein Design Beyond Wild-Type Neighborhoods


### Images

![61f5c24a6c1e9de72401c77cd214966a557d04bf5835ff8abcafb4e4853e7b62.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/images/61f5c24a6c1e9de72401c77cd214966a557d04bf5835ff8abcafb4e4853e7b62.jpg)

![7ba5c55b71c58f639132f662992e0a38078e35572cb01205a93761242e4a106a.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/images/7ba5c55b71c58f639132f662992e0a38078e35572cb01205a93761242e4a106a.jpg)

![b6aca834a685c6b429e1a853964b259b6c872645f3f1c5f50fff30313dba13c4.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/images/b6aca834a685c6b429e1a853964b259b6c872645f3f1c5f50fff30313dba13c4.jpg)

![fdbfb5df0bdaf27b4c75ba0027ae4a3c3123c4e02ac071efe336822b046e8900.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/images/fdbfb5df0bdaf27b4c75ba0027ae4a3c3123c4e02ac071efe336822b046e8900.jpg)

### Tables

![0cf038e83587fa927ead6664b34d26710f8da6ad4266ac5fb9917720cb764257.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/0cf038e83587fa927ead6664b34d26710f8da6ad4266ac5fb9917720cb764257.jpg)

![0d96c9241d498742799dd50277a0ac5265d06715eaeb9dc2807f65f406c86a75.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/0d96c9241d498742799dd50277a0ac5265d06715eaeb9dc2807f65f406c86a75.jpg)

![0db2722ab3cb7638c1523ef66cfd2a0cbdfa0f7beb64dd9550b731a0d9d385cb.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/0db2722ab3cb7638c1523ef66cfd2a0cbdfa0f7beb64dd9550b731a0d9d385cb.jpg)

![2198afeabbf797b2489c991fe21fdd8f4781b05cf6f6f35b11ac1037e32c4d92.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/2198afeabbf797b2489c991fe21fdd8f4781b05cf6f6f35b11ac1037e32c4d92.jpg)

![45ab9000de59a40e66b590a363cc078212f1fd37b4859faa2af264fd10cd692c.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/45ab9000de59a40e66b590a363cc078212f1fd37b4859faa2af264fd10cd692c.jpg)

![4cee4a4f45027bc17e47af7b4f59d3776ea185531505f59aba8f928ee0d7a74a.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/4cee4a4f45027bc17e47af7b4f59d3776ea185531505f59aba8f928ee0d7a74a.jpg)

![4ec3c785e43dc4661e5388f01f4063e1e3843f3eb54b30ea91b6382bddb9056b.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/4ec3c785e43dc4661e5388f01f4063e1e3843f3eb54b30ea91b6382bddb9056b.jpg)

![65e99427661387cb274536a68e32e19f8cc59e29752791f052c3962f3d6c7d43.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/65e99427661387cb274536a68e32e19f8cc59e29752791f052c3962f3d6c7d43.jpg)

![6b055f803583633ff26010d270d0aa818e23b226f730c1a5fbc7270ef2873e12.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/6b055f803583633ff26010d270d0aa818e23b226f730c1a5fbc7270ef2873e12.jpg)

![7706cb08a2d3088177affc05571e9013fe27c533df2eaa4399acc5721cf00a1f.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/7706cb08a2d3088177affc05571e9013fe27c533df2eaa4399acc5721cf00a1f.jpg)

![8a9c167186a4d08a56a5f5605ff88c3d7e1de4c2f65c6cd2049e10671180cfa6.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/8a9c167186a4d08a56a5f5605ff88c3d7e1de4c2f65c6cd2049e10671180cfa6.jpg)

![967bb83a70e7eb7978462ce9f87e79e34a640a57376a49b9ae3b403b4a1248e5.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/967bb83a70e7eb7978462ce9f87e79e34a640a57376a49b9ae3b403b4a1248e5.jpg)

![9c643b6fe15934afd96fea6a4ffbfb6f484d5cc665562f5fb2ca6eb76a1b4468.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/9c643b6fe15934afd96fea6a4ffbfb6f484d5cc665562f5fb2ca6eb76a1b4468.jpg)

![a46e3e642e55e3ba2888cb9d8115d0d7507cfe52a9d32e1a94d74d1d114182e4.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/a46e3e642e55e3ba2888cb9d8115d0d7507cfe52a9d32e1a94d74d1d114182e4.jpg)

![a77cc5891a4b376a9f9b11657e431f67ebd0694b08c2de1479efe9e5af3667dc.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/a77cc5891a4b376a9f9b11657e431f67ebd0694b08c2de1479efe9e5af3667dc.jpg)

![d1934590b08ec8cefbcc68abe34ff79d7e51d7e7fbfb7a5ce9a54dc4bc9807db.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/d1934590b08ec8cefbcc68abe34ff79d7e51d7e7fbfb7a5ce9a54dc4bc9807db.jpg)

![d6819066a8474a978674b607763acf6b6915d3db63ff900a8be3731e5aac2bbc.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/d6819066a8474a978674b607763acf6b6915d3db63ff900a8be3731e5aac2bbc.jpg)

![e2f8a22fb1d79b5e386adcb7d91d78f5283c330ef598196626a06035fb31163a.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/e2f8a22fb1d79b5e386adcb7d91d78f5283c330ef598196626a06035fb31163a.jpg)

![ff89e3d745dadf36e46efefac8903a35477ae5bd00f9c99e876962c2df555a33.jpg](../nips_results/1045_ProSpero_%20Active%20Learning%20for%20Robust%20Protein%20Design%20Beyond%20Wild-Type%20Neighborhoods/tables/ff89e3d745dadf36e46efefac8903a35477ae5bd00f9c99e876962c2df555a33.jpg)

## RoME: Domain-Robust Mixture-of-Experts for MILP Solution Prediction across Domains


### Images

![1812b6b9a5781c29b92ae4af67dbf482284eaff6736feb1e19e7d62079450f68.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/images/1812b6b9a5781c29b92ae4af67dbf482284eaff6736feb1e19e7d62079450f68.jpg)

![26403372a41413d2c3af5b0fbd09867f8e9e1e7e9cab2f8db0be509dabbbb632.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/images/26403372a41413d2c3af5b0fbd09867f8e9e1e7e9cab2f8db0be509dabbbb632.jpg)

![2e92a611cb1de963e281299f22330d56703835a728c43f39519b9b954cfc4e7e.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/images/2e92a611cb1de963e281299f22330d56703835a728c43f39519b9b954cfc4e7e.jpg)

![6283f64c919d1552803bc562bc9bdcdca0d448b254fefd272432de73bccf7793.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/images/6283f64c919d1552803bc562bc9bdcdca0d448b254fefd272432de73bccf7793.jpg)

![b4c0803bbb63b8d44a0bb44d544355f315d2eca56d11564c24af21784def0b7c.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/images/b4c0803bbb63b8d44a0bb44d544355f315d2eca56d11564c24af21784def0b7c.jpg)

![d6c25608a68ebffb3e0488160c67a1d3097d0d52023284c22437ec975728ac09.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/images/d6c25608a68ebffb3e0488160c67a1d3097d0d52023284c22437ec975728ac09.jpg)

### Tables

![037ba71aa198cfcae21933bc96f4ad89f6a70eb005b77f158c37774fef7d039e.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/037ba71aa198cfcae21933bc96f4ad89f6a70eb005b77f158c37774fef7d039e.jpg)

![128d9660c8edbf75a732869f14c389c679e1d3bd0365572fc447cb20feda0493.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/128d9660c8edbf75a732869f14c389c679e1d3bd0365572fc447cb20feda0493.jpg)

![1aa630048d55970b6bd8cc3d85b9227bdf9014abb33c3b44b027c08cafe873d9.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/1aa630048d55970b6bd8cc3d85b9227bdf9014abb33c3b44b027c08cafe873d9.jpg)

![2f63a6c7d6c5b78ee693c571531bd408502d1a561563079a974683e5b0c03797.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/2f63a6c7d6c5b78ee693c571531bd408502d1a561563079a974683e5b0c03797.jpg)

![35756084cfb03522373b09ba5ec16cd85ff43a931eff58fe0d214d6926a96fdb.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/35756084cfb03522373b09ba5ec16cd85ff43a931eff58fe0d214d6926a96fdb.jpg)

![4ad485fed96476b6506b566ab73b1c0b7b47bded3d19a2bc9efa9c15d5cc5803.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/4ad485fed96476b6506b566ab73b1c0b7b47bded3d19a2bc9efa9c15d5cc5803.jpg)

![8c60679da050ed4fde4a03d97b916eea7c58f85be37c6fc11ca0ee6803b6207e.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/8c60679da050ed4fde4a03d97b916eea7c58f85be37c6fc11ca0ee6803b6207e.jpg)

![9ce654136fcb9939ac00abbac62273b6a87adabd127e7f057f6a0c9666acd9e2.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/9ce654136fcb9939ac00abbac62273b6a87adabd127e7f057f6a0c9666acd9e2.jpg)

![a59469b1676b1f1e343a1e853a9d52b5f24ae73f15a7f74659ff886459400278.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/a59469b1676b1f1e343a1e853a9d52b5f24ae73f15a7f74659ff886459400278.jpg)

![b687d3a30fc6b66ca8a7db76b53afa4caba8f2cac790a0e8e8b4cc3e17efe41a.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/b687d3a30fc6b66ca8a7db76b53afa4caba8f2cac790a0e8e8b4cc3e17efe41a.jpg)

![c7f4bc87f79693f480208b9736ba46e75ba3060e6f43f3b5dc3529760f416fbd.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/c7f4bc87f79693f480208b9736ba46e75ba3060e6f43f3b5dc3529760f416fbd.jpg)

![d90a8db43bfeb53aba65e860a0d6fb39e3d4a37be5fc3558f3ea49b06b46c81a.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/d90a8db43bfeb53aba65e860a0d6fb39e3d4a37be5fc3558f3ea49b06b46c81a.jpg)

![e6b713d02f65a5ed70dbb851810acde03896a3d592663e17b479321b41e310a5.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/e6b713d02f65a5ed70dbb851810acde03896a3d592663e17b479321b41e310a5.jpg)

![f7fbe3c2cd9983eb882b957cf145c1a1f6421cdaad78e64c35e90fc81e5f8bcd.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/f7fbe3c2cd9983eb882b957cf145c1a1f6421cdaad78e64c35e90fc81e5f8bcd.jpg)

![f85fa69b03f90b4a55cc9627b89094cf18da3c161cfedf96ec597e5e1cc48034.jpg](../nips_results/1046_RoME_%20Domain-Robust%20Mixture-of-Experts%20for%20MILP%20Solution%20Prediction%20across%20Domains/tables/f85fa69b03f90b4a55cc9627b89094cf18da3c161cfedf96ec597e5e1cc48034.jpg)

## Moment- and Power-Spectrum-Based Gaussianity Regularization for Text-to-Image Models


### Images

![1745b2b3bb754ecf039b2f0a1411d0a3da3eca6055ee5bba4a0a5079712aba0f.jpg](../nips_results/1047_Moment-%20and%20Power-Spectrum-Based%20Gaussianity%20Regularization%20for%20Text-to-Image%20Models/images/1745b2b3bb754ecf039b2f0a1411d0a3da3eca6055ee5bba4a0a5079712aba0f.jpg)

![2866f43195c9946bfb7dab4f4d121d717cab285b3f39cdf3ed70c4c09c42b246.jpg](../nips_results/1047_Moment-%20and%20Power-Spectrum-Based%20Gaussianity%20Regularization%20for%20Text-to-Image%20Models/images/2866f43195c9946bfb7dab4f4d121d717cab285b3f39cdf3ed70c4c09c42b246.jpg)

![ade1ea14c16b5dc4f48860d9712c1cb943bb735446beec71ec32f32bcaace96b.jpg](../nips_results/1047_Moment-%20and%20Power-Spectrum-Based%20Gaussianity%20Regularization%20for%20Text-to-Image%20Models/images/ade1ea14c16b5dc4f48860d9712c1cb943bb735446beec71ec32f32bcaace96b.jpg)

![cc8ccb6be2caadca1af3438d8453cbf9e352023acc748585e10672a71a5af59d.jpg](../nips_results/1047_Moment-%20and%20Power-Spectrum-Based%20Gaussianity%20Regularization%20for%20Text-to-Image%20Models/images/cc8ccb6be2caadca1af3438d8453cbf9e352023acc748585e10672a71a5af59d.jpg)

![ea2e6a766c5e1f2d362c2a45b2fff632205eeb7e8aa800827766af0626a1f9af.jpg](../nips_results/1047_Moment-%20and%20Power-Spectrum-Based%20Gaussianity%20Regularization%20for%20Text-to-Image%20Models/images/ea2e6a766c5e1f2d362c2a45b2fff632205eeb7e8aa800827766af0626a1f9af.jpg)

![fc93b454063279f36391394c5345866320349bc3a83ec3e1616f22d147d57bc8.jpg](../nips_results/1047_Moment-%20and%20Power-Spectrum-Based%20Gaussianity%20Regularization%20for%20Text-to-Image%20Models/images/fc93b454063279f36391394c5345866320349bc3a83ec3e1616f22d147d57bc8.jpg)

### Tables

![98b7f53e04dac5fa87932fea874b8c2db977cc44c587c7a7c397d93b01cb7213.jpg](../nips_results/1047_Moment-%20and%20Power-Spectrum-Based%20Gaussianity%20Regularization%20for%20Text-to-Image%20Models/tables/98b7f53e04dac5fa87932fea874b8c2db977cc44c587c7a7c397d93b01cb7213.jpg)

![b5fa52de0cbeadeee405dd9806b05e66ad2c2a3242393ab373380ce3d7fe38f7.jpg](../nips_results/1047_Moment-%20and%20Power-Spectrum-Based%20Gaussianity%20Regularization%20for%20Text-to-Image%20Models/tables/b5fa52de0cbeadeee405dd9806b05e66ad2c2a3242393ab373380ce3d7fe38f7.jpg)

![bc094dfddf9d424c7795837bfed84f37bc0fe2cb784d3e4af17fa05ef61ea6f0.jpg](../nips_results/1047_Moment-%20and%20Power-Spectrum-Based%20Gaussianity%20Regularization%20for%20Text-to-Image%20Models/tables/bc094dfddf9d424c7795837bfed84f37bc0fe2cb784d3e4af17fa05ef61ea6f0.jpg)

![c7cd963a3191c97c57e02a3eaaa92ed2cbf42c34491bfc4ab4a899ffbbfb5792.jpg](../nips_results/1047_Moment-%20and%20Power-Spectrum-Based%20Gaussianity%20Regularization%20for%20Text-to-Image%20Models/tables/c7cd963a3191c97c57e02a3eaaa92ed2cbf42c34491bfc4ab4a899ffbbfb5792.jpg)

![ed9998a7877f661012927688bb2022e5139e707a975bbb7c34e1b95bae7615db.jpg](../nips_results/1047_Moment-%20and%20Power-Spectrum-Based%20Gaussianity%20Regularization%20for%20Text-to-Image%20Models/tables/ed9998a7877f661012927688bb2022e5139e707a975bbb7c34e1b95bae7615db.jpg)

## Distance Adaptive Beam Search for Provably Accurate Graph-Based Nearest Neighbor Search


### Images

![0716d899c5af3d3948dd5770416cedfc3783f8301321e75bfa722de42413a6cd.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/images/0716d899c5af3d3948dd5770416cedfc3783f8301321e75bfa722de42413a6cd.jpg)

![1020dd18dae270a3269a7786ac7ea7a893a9f52aa2b9a1c5f2ef064ea461ae68.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/images/1020dd18dae270a3269a7786ac7ea7a893a9f52aa2b9a1c5f2ef064ea461ae68.jpg)

![14b67f96c8913473412adb10364116d029980f67e266dfa9ef082604f576c512.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/images/14b67f96c8913473412adb10364116d029980f67e266dfa9ef082604f576c512.jpg)

![224500c194b3b42235dc8cc0fb92d8144f4c1c5c3d81ae84970981949c3fc7ac.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/images/224500c194b3b42235dc8cc0fb92d8144f4c1c5c3d81ae84970981949c3fc7ac.jpg)

![4d7534c4d7dabc575f9be92bf9501376cb04177b81d073916b6bee5469339905.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/images/4d7534c4d7dabc575f9be92bf9501376cb04177b81d073916b6bee5469339905.jpg)

![5085281db59b1cb307fda94b543da10dcb3571c8b29033e8099b05314b4531ca.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/images/5085281db59b1cb307fda94b543da10dcb3571c8b29033e8099b05314b4531ca.jpg)

![85eff3fad21018e8d1dd3bc8548d8cebd84c0a76094cd78e243d671d5407d805.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/images/85eff3fad21018e8d1dd3bc8548d8cebd84c0a76094cd78e243d671d5407d805.jpg)

![d4f6361cff44f1e587b3da68f0629da4e4408ebaf2e99a5847fdb8c98d3a3bc3.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/images/d4f6361cff44f1e587b3da68f0629da4e4408ebaf2e99a5847fdb8c98d3a3bc3.jpg)

![d6f23de90c4fdf3d12e50ac1c807a313cbd7f54fa510528ac0ddb1bae12c8b2c.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/images/d6f23de90c4fdf3d12e50ac1c807a313cbd7f54fa510528ac0ddb1bae12c8b2c.jpg)

![ee547e4f38d0b31d3a087348fe08c0c32c6c8fb7b3cbc6f23540e339eebcf42d.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/images/ee547e4f38d0b31d3a087348fe08c0c32c6c8fb7b3cbc6f23540e339eebcf42d.jpg)

### Tables

![4cfe306be467375790eb570323e6120664de232f1972565be46247d9c425ac63.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/tables/4cfe306be467375790eb570323e6120664de232f1972565be46247d9c425ac63.jpg)

![7d6ed836f56bacee7cf7ea65c47ad1e2aec959678aad0060a8fd40b79eb22d31.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/tables/7d6ed836f56bacee7cf7ea65c47ad1e2aec959678aad0060a8fd40b79eb22d31.jpg)

![86438c17ba337289acd55c30eb4583f967980e70acdd3b39f97fcda76ba0b8dc.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/tables/86438c17ba337289acd55c30eb4583f967980e70acdd3b39f97fcda76ba0b8dc.jpg)

![d29002e95ae38d3206f40fb246453403bc203ea464556349ee7738efc5401abc.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/tables/d29002e95ae38d3206f40fb246453403bc203ea464556349ee7738efc5401abc.jpg)

![dd9021d1b02ab6eaeeaf8d68ae40963fa30650b232bc5f820533e23aa685f70b.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/tables/dd9021d1b02ab6eaeeaf8d68ae40963fa30650b232bc5f820533e23aa685f70b.jpg)

![e011502c2ffc7e2a593cd1a7446e18919bfb685243e8c32ab2d0f1c891bf2812.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/tables/e011502c2ffc7e2a593cd1a7446e18919bfb685243e8c32ab2d0f1c891bf2812.jpg)

![e75b5d1ffd75f7471fd0d6f6c5dfc294ff9b02260e034f882ac90290fef2cdef.jpg](../nips_results/1048_Distance%20Adaptive%20Beam%20Search%20for%20Provably%20Accurate%20Graph-Based%20Nearest%20Neighbor%20Search/tables/e75b5d1ffd75f7471fd0d6f6c5dfc294ff9b02260e034f882ac90290fef2cdef.jpg)

## Active Target Discovery under Uninformative Priors: The Power of Permanent and Transient Memory


### Images

![005e24f29c6040857d398b61ba55ef8435080ceb14bce939b737c6a88ff68eb1.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/005e24f29c6040857d398b61ba55ef8435080ceb14bce939b737c6a88ff68eb1.jpg)

![0df3013cc57316a4c8572680d4d6f9f0a2cddf08108eda9fbd87bf73c8230a29.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/0df3013cc57316a4c8572680d4d6f9f0a2cddf08108eda9fbd87bf73c8230a29.jpg)

![1b26b425db263c0b1cdff254d87cb76fdf3012fd2dc2acb219232bad6c3c8a42.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/1b26b425db263c0b1cdff254d87cb76fdf3012fd2dc2acb219232bad6c3c8a42.jpg)

![27ce18bf4bc32834de5459416c350c377d6e898a583ae5bb446127cbacbfff45.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/27ce18bf4bc32834de5459416c350c377d6e898a583ae5bb446127cbacbfff45.jpg)

![2aa3d5661ec5f33a8443b95ef6690856c1542369834418c6ac25230caf9a4193.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/2aa3d5661ec5f33a8443b95ef6690856c1542369834418c6ac25230caf9a4193.jpg)

![2d97b9ff3d6c8d751481597ea0837848aca412fd31aee3c6df684c8cd51dc829.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/2d97b9ff3d6c8d751481597ea0837848aca412fd31aee3c6df684c8cd51dc829.jpg)

![67491e8707d50214974895406eaa45d4858bc92758be57af110374d5c7b89986.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/67491e8707d50214974895406eaa45d4858bc92758be57af110374d5c7b89986.jpg)

![6beaec36872f851c59eb02d74e52c6650958db66fdeed3921be6b7e522874b09.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/6beaec36872f851c59eb02d74e52c6650958db66fdeed3921be6b7e522874b09.jpg)

![85f4ac7c428a236c98dd45586dd41591e777e09428cc0d8c39dfac6aa656042e.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/85f4ac7c428a236c98dd45586dd41591e777e09428cc0d8c39dfac6aa656042e.jpg)

![89867fe04cdae8a1985f15f406ea5b0e28ea7643407f59dfcd4cebcd74598f76.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/89867fe04cdae8a1985f15f406ea5b0e28ea7643407f59dfcd4cebcd74598f76.jpg)

![9771b0cd3f25f6cfad5eebf8327730dc8b70cbb4fe12e5d2d2c44edea94bf18e.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/9771b0cd3f25f6cfad5eebf8327730dc8b70cbb4fe12e5d2d2c44edea94bf18e.jpg)

![9b109ba4e9a6f0d6629826fd8704f1f2a1133738a89fdeef4e9545bfb8a93922.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/9b109ba4e9a6f0d6629826fd8704f1f2a1133738a89fdeef4e9545bfb8a93922.jpg)

![a24461bffdc4255724cba0f3377e397291aa7ffba2b331b3f47e960340cefa9a.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/a24461bffdc4255724cba0f3377e397291aa7ffba2b331b3f47e960340cefa9a.jpg)

![a3117d9a3d434dc50bea278e9cfb8bd2a6861b1870d2d83e245f645402b72634.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/a3117d9a3d434dc50bea278e9cfb8bd2a6861b1870d2d83e245f645402b72634.jpg)

![a9ade13e7fd8dc96e4f09211058c8c813b7c31cc048f87e11fb63e1208b4e7d8.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/a9ade13e7fd8dc96e4f09211058c8c813b7c31cc048f87e11fb63e1208b4e7d8.jpg)

![acb7769a5d9b08b98bbe34e3aaab21cd79367aab27cd8142ae555a75d2ff9da9.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/acb7769a5d9b08b98bbe34e3aaab21cd79367aab27cd8142ae555a75d2ff9da9.jpg)

![b2fee7134c7453bbacee773ae724bd196ea285a1e0003e603edf9bcb65442776.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/b2fee7134c7453bbacee773ae724bd196ea285a1e0003e603edf9bcb65442776.jpg)

![b67108561cf92f80c53fbe3a175b870f6ba3d1aa857f64754d2813d91fb54e30.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/b67108561cf92f80c53fbe3a175b870f6ba3d1aa857f64754d2813d91fb54e30.jpg)

![d9721d67559b993f2374b9bea2d50e5c4f6e7aca7a3a94e036c3a002c89a3efc.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/d9721d67559b993f2374b9bea2d50e5c4f6e7aca7a3a94e036c3a002c89a3efc.jpg)

![dd0c7371a47ad47c826b31084feb40a1e7ecbd9cb636bf9d37af146acc20536c.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/dd0c7371a47ad47c826b31084feb40a1e7ecbd9cb636bf9d37af146acc20536c.jpg)

![de50939b1c30b597359cecfea5ae609684e44fb60e0ba9f3404dcf262c1fbde1.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/de50939b1c30b597359cecfea5ae609684e44fb60e0ba9f3404dcf262c1fbde1.jpg)

![f77a70b1e8b0d2a69b37fc86b35189f5b11e8abeb3f81a91d57d552995751adf.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/f77a70b1e8b0d2a69b37fc86b35189f5b11e8abeb3f81a91d57d552995751adf.jpg)

![f7ce59482f15f660633dd5f6262ea13b4b809db01bc70e328ad11b51bab5cd7c.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/images/f7ce59482f15f660633dd5f6262ea13b4b809db01bc70e328ad11b51bab5cd7c.jpg)

### Tables

![158bf65c85b118702c80d7ed8f858ebb5241ae93c847a467eca84545513215b1.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/158bf65c85b118702c80d7ed8f858ebb5241ae93c847a467eca84545513215b1.jpg)

![1faa258ff362d0ccb094caf3edcaee5bdfafa4128c314333a03f408396076909.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/1faa258ff362d0ccb094caf3edcaee5bdfafa4128c314333a03f408396076909.jpg)

![37f3c462455a5ce27a2e7365ee051c6d5d289841649c31ed0f21da4279d59e4a.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/37f3c462455a5ce27a2e7365ee051c6d5d289841649c31ed0f21da4279d59e4a.jpg)

![3d680484fe154dcaa025dd4feb55c50a002ffb8a4e5635dff3095987747aa4b7.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/3d680484fe154dcaa025dd4feb55c50a002ffb8a4e5635dff3095987747aa4b7.jpg)

![7a6b5f18fa407e39ff1b2ad5462ec36e7efffa844f3f15f3fdfaeb9da5b28980.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/7a6b5f18fa407e39ff1b2ad5462ec36e7efffa844f3f15f3fdfaeb9da5b28980.jpg)

![96bf0079ade193cdc4e0b9d41194ceeeb8af7ba50c664f0cbd2ca2a93ccf5955.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/96bf0079ade193cdc4e0b9d41194ceeeb8af7ba50c664f0cbd2ca2a93ccf5955.jpg)

![a874a961ecd35b62db9d1d31318f209253ecbb3d3f8a127c56bb77872b66df63.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/a874a961ecd35b62db9d1d31318f209253ecbb3d3f8a127c56bb77872b66df63.jpg)

![ae43d3b915c7c3ebccb9d8485bb5a09f86303118fc49f94e71bb8ee4fa347369.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/ae43d3b915c7c3ebccb9d8485bb5a09f86303118fc49f94e71bb8ee4fa347369.jpg)

![bbf03b262a56459af61e7f218d30344d2298547c5e63aa387622bf348f50ec70.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/bbf03b262a56459af61e7f218d30344d2298547c5e63aa387622bf348f50ec70.jpg)

![c5ad216f27b26dc5fe2e7704bafa5129d91e5a7a779aa614e03c05b97825007e.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/c5ad216f27b26dc5fe2e7704bafa5129d91e5a7a779aa614e03c05b97825007e.jpg)

![e761a1b5774dd930a9e5cd3dcd38f671988db936c9792c0e4335c5439e2f7d30.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/e761a1b5774dd930a9e5cd3dcd38f671988db936c9792c0e4335c5439e2f7d30.jpg)

![e7b387bb2d8b4a694fd7781ef57d1aea1c36a0e47a1832c0adf4c97d3c44bd12.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/e7b387bb2d8b4a694fd7781ef57d1aea1c36a0e47a1832c0adf4c97d3c44bd12.jpg)

![fb1cc1c8acd4b78403148ccd7df73e9d47c7e9d232f2deaf367ac03ff662cbc5.jpg](../nips_results/1049_Active%20Target%20Discovery%20under%20Uninformative%20Priors_%20The%20Power%20of%20Permanent%20and%20Transient%20Memory/tables/fb1cc1c8acd4b78403148ccd7df73e9d47c7e9d232f2deaf367ac03ff662cbc5.jpg)

## S-GRPO: Early Exit via Reinforcement Learning in Reasoning Models


### Images

![27400e3e50146c7e76ca4e01620e7c5200de326e0cd11d42fcbd150677c30f38.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/images/27400e3e50146c7e76ca4e01620e7c5200de326e0cd11d42fcbd150677c30f38.jpg)

![670c4dd3d5a5e9944d6ba664dad802ce35dfa094da8fb88630ea77187d852aa7.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/images/670c4dd3d5a5e9944d6ba664dad802ce35dfa094da8fb88630ea77187d852aa7.jpg)

![690393abb86d6d2b81a8eef7e7696c2ae86c175282e91fc2b6ca23d4c255e546.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/images/690393abb86d6d2b81a8eef7e7696c2ae86c175282e91fc2b6ca23d4c255e546.jpg)

![8bc80680e1761a8677f7269c38bf26720fe581ab751401560736a4cb862e74d0.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/images/8bc80680e1761a8677f7269c38bf26720fe581ab751401560736a4cb862e74d0.jpg)

![98929c419221fa773b53d3e6373d89bde90cf44cec49f6e3be59faa3d498a8da.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/images/98929c419221fa773b53d3e6373d89bde90cf44cec49f6e3be59faa3d498a8da.jpg)

![bb1915cc711123fb364aa418cc3ea19d7b759f0f57d26aaba44dc0e5b5ef05ff.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/images/bb1915cc711123fb364aa418cc3ea19d7b759f0f57d26aaba44dc0e5b5ef05ff.jpg)

![e0bb13f5fca50396de68cfc19151eaba916a1e238983f1fa9dafa2a3552c1115.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/images/e0bb13f5fca50396de68cfc19151eaba916a1e238983f1fa9dafa2a3552c1115.jpg)

### Tables

![2735adbc0937b511f07ec005dfcdd781a4e4bc2b34fa7194f3009e964c3a865d.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/tables/2735adbc0937b511f07ec005dfcdd781a4e4bc2b34fa7194f3009e964c3a865d.jpg)

![39e03090d67930a13bf9503f7ba85a57e5b38727f6f02c492ccf34d13d5bde54.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/tables/39e03090d67930a13bf9503f7ba85a57e5b38727f6f02c492ccf34d13d5bde54.jpg)

![777eb76dd036a2a26aad156faff706fb22b3b6078d44367db11ab8dfc6030e11.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/tables/777eb76dd036a2a26aad156faff706fb22b3b6078d44367db11ab8dfc6030e11.jpg)

![933808832d722d59e07eda94fe88e30b736829da99c171ae26ec60e5587d3b09.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/tables/933808832d722d59e07eda94fe88e30b736829da99c171ae26ec60e5587d3b09.jpg)

![b3cf75d21955a6965779b648b2026174f9423a376b7c54db998c6b2ded3b0464.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/tables/b3cf75d21955a6965779b648b2026174f9423a376b7c54db998c6b2ded3b0464.jpg)

![b54cf6c549ac910853b288da91c1b59dd47487a1c912726c183905309b958b06.jpg](../nips_results/1050_S-GRPO_%20Early%20Exit%20via%20Reinforcement%20Learning%20in%20Reasoning%20Models/tables/b54cf6c549ac910853b288da91c1b59dd47487a1c912726c183905309b958b06.jpg)

## FastDINOv2: Frequency Based Curriculum Learning Improves Robustness and Training Speed


### Images

![11b918fc90bc5d49528466b6d9eaa4528d8063ca1e0869de056e1d9ad3999863.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/images/11b918fc90bc5d49528466b6d9eaa4528d8063ca1e0869de056e1d9ad3999863.jpg)

![6860e7ac95d4d0754544788b09622798595d0cb444198884281ef88be6893f9a.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/images/6860e7ac95d4d0754544788b09622798595d0cb444198884281ef88be6893f9a.jpg)

![6b3f0a8219c338cb02184bdc6e65d50c1f00178f06b01724977b672863d98000.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/images/6b3f0a8219c338cb02184bdc6e65d50c1f00178f06b01724977b672863d98000.jpg)

![78bcdf65794e23a4007871a6d65e08c47439f43ffe726189992498c06ac4d6e3.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/images/78bcdf65794e23a4007871a6d65e08c47439f43ffe726189992498c06ac4d6e3.jpg)

![f2a92a4953d8eba695be301565570994f63fbb2a66b2fff5d49ea39dd0ca18b9.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/images/f2a92a4953d8eba695be301565570994f63fbb2a66b2fff5d49ea39dd0ca18b9.jpg)

### Tables

![39d1c3371dec213c3b126f9a329ce8fdecefb18640fecb6bf2d93fa007575584.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/39d1c3371dec213c3b126f9a329ce8fdecefb18640fecb6bf2d93fa007575584.jpg)

![43d4e4b7b5450d027cc16aa1859c1eb23fab7587fd122bb0e313bf6d7f184881.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/43d4e4b7b5450d027cc16aa1859c1eb23fab7587fd122bb0e313bf6d7f184881.jpg)

![4413b0372c45e1eaf7e237b75244a21786833a46c787bd5cc9e308ab8ae7ddf4.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/4413b0372c45e1eaf7e237b75244a21786833a46c787bd5cc9e308ab8ae7ddf4.jpg)

![4b9bb77830bbf45b45688d2250deea3a02b1239564f167673f47396bfae2214b.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/4b9bb77830bbf45b45688d2250deea3a02b1239564f167673f47396bfae2214b.jpg)

![5168a6af74f81d55d4ce2f77634bf1502ae12b1fe18ac27d464c5726cca039c5.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/5168a6af74f81d55d4ce2f77634bf1502ae12b1fe18ac27d464c5726cca039c5.jpg)

![80b5a2743b63698a7aac8a040dcee74431090b11dc2955e4f6a0bba170d3ff0e.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/80b5a2743b63698a7aac8a040dcee74431090b11dc2955e4f6a0bba170d3ff0e.jpg)

![82641f61ce3d15515b12146793216c2ed6d0e4963c51aa0b17ba14146cad5186.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/82641f61ce3d15515b12146793216c2ed6d0e4963c51aa0b17ba14146cad5186.jpg)

![b65183bb0fdb0853b47814bbd565211a85df79e5a3f8150d24bcfa633804c6c2.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/b65183bb0fdb0853b47814bbd565211a85df79e5a3f8150d24bcfa633804c6c2.jpg)

![ec2df0350bf4ef39569b6213449c8595fda6001ed76c5cdef97d2e129b6d2d16.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/ec2df0350bf4ef39569b6213449c8595fda6001ed76c5cdef97d2e129b6d2d16.jpg)

![f151330a0ea74ee95ebc1649a754f6862267f25d602db33ff897a97f9040c2e6.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/f151330a0ea74ee95ebc1649a754f6862267f25d602db33ff897a97f9040c2e6.jpg)

![f19841b0c97f87ca42e8624153dee942ff747983455e481ae53f64685fdfb5e8.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/f19841b0c97f87ca42e8624153dee942ff747983455e481ae53f64685fdfb5e8.jpg)

![f532369454fccdc0c76f7d4005b7dcd61e18ff274f3bbd7b72bf4fff71ccbc63.jpg](../nips_results/1051_FastDINOv2_%20Frequency%20Based%20Curriculum%20Learning%20Improves%20Robustness%20and%20Training%20Speed/tables/f532369454fccdc0c76f7d4005b7dcd61e18ff274f3bbd7b72bf4fff71ccbc63.jpg)

## Active Seriation: Efficient Ordering Recovery with Statistical Guarantees


### Images

![7337dee7efc8ae1cb14212dc292ecbf5cc7f959facdda20419329b551a4e1ff8.jpg](../nips_results/1052_Active%20Seriation_%20Efficient%20Ordering%20Recovery%20with%20Statistical%20Guarantees/images/7337dee7efc8ae1cb14212dc292ecbf5cc7f959facdda20419329b551a4e1ff8.jpg)

## MESS+: Dynamically Learned Inference-Time LLM Routing in Model Zoos with Service Level Guarantees


### Images

![4d9db983ff4f948cbd5a58c986dbffcfced2b2197e47f67353e1271716fb4109.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/images/4d9db983ff4f948cbd5a58c986dbffcfced2b2197e47f67353e1271716fb4109.jpg)

![74c11ce2b9b1d289694c5f68774d9443d82bc873aba05a0ef1937369e6095afb.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/images/74c11ce2b9b1d289694c5f68774d9443d82bc873aba05a0ef1937369e6095afb.jpg)

![934e87ff8d3224824dfe338e7521695e3dbeda7ed9978e3caee8c6e411896174.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/images/934e87ff8d3224824dfe338e7521695e3dbeda7ed9978e3caee8c6e411896174.jpg)

![96f43bcadc6f7b506df79da2bcc75f0cc593023f175505ed79ea2a9db3437bd0.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/images/96f43bcadc6f7b506df79da2bcc75f0cc593023f175505ed79ea2a9db3437bd0.jpg)

![d0b1d942887827fe754d1c893e98183df6a6756c9a53e94559835ca0116b6ec8.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/images/d0b1d942887827fe754d1c893e98183df6a6756c9a53e94559835ca0116b6ec8.jpg)

![e0802c9855b368356d6a21a9a2f5b11cfc5565c21acbf76fd12c18e2d7d5d187.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/images/e0802c9855b368356d6a21a9a2f5b11cfc5565c21acbf76fd12c18e2d7d5d187.jpg)

### Tables

![1b8e96bf3a1738b461af226dd10e476bf7cc4211666a5ab80ca4cc41fc6d97c9.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/1b8e96bf3a1738b461af226dd10e476bf7cc4211666a5ab80ca4cc41fc6d97c9.jpg)

![2dedb7ef4d7bec409f1813d5906aef37ece1c0a94859fde2624038bf035c16ba.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/2dedb7ef4d7bec409f1813d5906aef37ece1c0a94859fde2624038bf035c16ba.jpg)

![3c8ef856fe3abbb7e5738f51e4470a283ba1e1c8b6ed3ee3cddb773781372b98.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/3c8ef856fe3abbb7e5738f51e4470a283ba1e1c8b6ed3ee3cddb773781372b98.jpg)

![4af2780f4c9eb1b4a6a9109874dceb6075d8cfe486f3072a6f61cef2b854fbd2.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/4af2780f4c9eb1b4a6a9109874dceb6075d8cfe486f3072a6f61cef2b854fbd2.jpg)

![53b34cf3bdb6428429e08877de3621b5604ca061ab9d8d0f91196294b61c21a2.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/53b34cf3bdb6428429e08877de3621b5604ca061ab9d8d0f91196294b61c21a2.jpg)

![59d75ed20419537ef5ab69ab08bf934331224b871e2071e9eb45399a22c3ff93.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/59d75ed20419537ef5ab69ab08bf934331224b871e2071e9eb45399a22c3ff93.jpg)

![62db6cc8da45a64718841196b5c90d09ddfe9357cf3153302ce71ff2d2f9638c.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/62db6cc8da45a64718841196b5c90d09ddfe9357cf3153302ce71ff2d2f9638c.jpg)

![8396d23df83ee5e2186a29697024c2a8d909e60cc943da7d9cd1d85e7ba5670a.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/8396d23df83ee5e2186a29697024c2a8d909e60cc943da7d9cd1d85e7ba5670a.jpg)

![8399233c5e8606d5bf5f291781645f3ef24f86604de006b1c7e9ff2e6975a78b.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/8399233c5e8606d5bf5f291781645f3ef24f86604de006b1c7e9ff2e6975a78b.jpg)

![92edd98b4844f4d4ea57d876c61663de7c891f7a65b794228f806f376a7d488b.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/92edd98b4844f4d4ea57d876c61663de7c891f7a65b794228f806f376a7d488b.jpg)

![a72129e69f3554318a7b69d9327e12bb1f2946cb8a04a1dc94eec0ad2cb22755.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/a72129e69f3554318a7b69d9327e12bb1f2946cb8a04a1dc94eec0ad2cb22755.jpg)

![c0a5b689b61ad3ba6d2f157d370cd86075122ada3da7c4f8a4f77e1173b80e0a.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/c0a5b689b61ad3ba6d2f157d370cd86075122ada3da7c4f8a4f77e1173b80e0a.jpg)

![d9f6d2320ce9cba9a410dd3655fe0ff9412f6554c7b5aeb02528214808124f2c.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/d9f6d2320ce9cba9a410dd3655fe0ff9412f6554c7b5aeb02528214808124f2c.jpg)

![e9fdc1f6335a199d2aea5675bdc486aeaaa09cc86de2b8ec810a34598f497de4.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/e9fdc1f6335a199d2aea5675bdc486aeaaa09cc86de2b8ec810a34598f497de4.jpg)

![f298d7110fff34db42f1a515eed30801db51a69eb00bfe7948780393bef55e63.jpg](../nips_results/1053_MESS%2B_%20Dynamically%20Learned%20Inference-Time%20LLM%20Routing%20in%20Model%20Zoos%20with%20Service%20Level%20Guarantees/tables/f298d7110fff34db42f1a515eed30801db51a69eb00bfe7948780393bef55e63.jpg)

## Mixture of Noise for Pre-Trained Model-Based Class-Incremental Learning


### Images

![0b2cde4268084f7fd9c6a15310dcd4598cc05b4735fa4a462d2e3f84e5c77cdf.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/0b2cde4268084f7fd9c6a15310dcd4598cc05b4735fa4a462d2e3f84e5c77cdf.jpg)

![175b93fe8f09952b813d33a053ecddae5a1509bf35ac7fbcac955b49ca76b75d.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/175b93fe8f09952b813d33a053ecddae5a1509bf35ac7fbcac955b49ca76b75d.jpg)

![27a49f2952b9959487ee8926d21715c1fe22c820b11ae4ab85d58c707be34a10.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/27a49f2952b9959487ee8926d21715c1fe22c820b11ae4ab85d58c707be34a10.jpg)

![2c0e546bae65eca87e1d9f5bd0f1d0fc2b45433ea837127b04b1101be451f6b4.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/2c0e546bae65eca87e1d9f5bd0f1d0fc2b45433ea837127b04b1101be451f6b4.jpg)

![432399741ccca37502295fb3710fb554c6d5f367dfff0f24f8af38c306fdd516.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/432399741ccca37502295fb3710fb554c6d5f367dfff0f24f8af38c306fdd516.jpg)

![5ec5b9b33d680f9babefaf2def18f832cf0cf80d1ad63f5582ffa42c5f8094c5.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/5ec5b9b33d680f9babefaf2def18f832cf0cf80d1ad63f5582ffa42c5f8094c5.jpg)

![5fa4038df580248bd38a45243ea3178499208b24607c121c6b9b645a66d60959.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/5fa4038df580248bd38a45243ea3178499208b24607c121c6b9b645a66d60959.jpg)

![68fd35093a9814a4b41a5b92a4c57f1b77f7b620a0776a9891f7109238cc66a2.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/68fd35093a9814a4b41a5b92a4c57f1b77f7b620a0776a9891f7109238cc66a2.jpg)

![696c59ba57d5ee02f4a1f146e81bb70d1f6f2c0e8fb47b7849f0b5b159e7fc3e.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/696c59ba57d5ee02f4a1f146e81bb70d1f6f2c0e8fb47b7849f0b5b159e7fc3e.jpg)

![729f808f9dbf3bb24be2e0d18aaeb4ce6e63991cd46a2163cc63c3bba6f9d7f4.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/729f808f9dbf3bb24be2e0d18aaeb4ce6e63991cd46a2163cc63c3bba6f9d7f4.jpg)

![79d17145d9a380b96ffd2d8a08496432dd4df2170b8bb208846309b29f0345f8.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/79d17145d9a380b96ffd2d8a08496432dd4df2170b8bb208846309b29f0345f8.jpg)

![87659a09be8a3340089fb876867908a517cdd421248fd2e00721b37a6bb4bf3d.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/87659a09be8a3340089fb876867908a517cdd421248fd2e00721b37a6bb4bf3d.jpg)

![88f8c825e0c167069f4e2f031cfe8294dfd51381d68264ae05f24865e2b9a620.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/88f8c825e0c167069f4e2f031cfe8294dfd51381d68264ae05f24865e2b9a620.jpg)

![96e5e61525ba08c2d4cef48194eda24b89bf653b686887b46574b4b98e4b618c.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/96e5e61525ba08c2d4cef48194eda24b89bf653b686887b46574b4b98e4b618c.jpg)

![9c21b4a435e8aacbbbcf274096e00f5ce852650d32716c8fe336da0ab3c57444.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/9c21b4a435e8aacbbbcf274096e00f5ce852650d32716c8fe336da0ab3c57444.jpg)

![a9250a5fb1a22e28e572b1e93f8bcdf62d22f99152b82652683a914006806c97.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/a9250a5fb1a22e28e572b1e93f8bcdf62d22f99152b82652683a914006806c97.jpg)

![cb348bf865f1b22827bf59fd437c1626c4ce03441c86804b938821696fc8320c.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/cb348bf865f1b22827bf59fd437c1626c4ce03441c86804b938821696fc8320c.jpg)

![d054354acac454347114d211fc2261a7e8f01d1d53e293b69a5ea9197dd44ce8.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/d054354acac454347114d211fc2261a7e8f01d1d53e293b69a5ea9197dd44ce8.jpg)

![e8eeb0b1d302888cef98928ba0e46e630320714e88985bcbf6ec5cebe1f3a0ed.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/e8eeb0b1d302888cef98928ba0e46e630320714e88985bcbf6ec5cebe1f3a0ed.jpg)

![fdee002d3813959890697f9006dc9947be64aac13c1854f76e3ab3328f0e35ba.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/fdee002d3813959890697f9006dc9947be64aac13c1854f76e3ab3328f0e35ba.jpg)

![feb68212ffa9fdba64ac72a9ab751ef3e33be565c4deb6162ccae860e36ffe5a.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/images/feb68212ffa9fdba64ac72a9ab751ef3e33be565c4deb6162ccae860e36ffe5a.jpg)

### Tables

![4b71ccd2fc4da37f24ec8baeee81c8b9be19e2f91b988fbc087f8370a242f7af.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/tables/4b71ccd2fc4da37f24ec8baeee81c8b9be19e2f91b988fbc087f8370a242f7af.jpg)

![5036c8349f727cfad3a2ec7f64eafb4e1e4408dfb6768691590d6918726dd6d4.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/tables/5036c8349f727cfad3a2ec7f64eafb4e1e4408dfb6768691590d6918726dd6d4.jpg)

![930779c1b2482e65c3f1e2220d3026e0679177e60d618391c9a6723faac35a51.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/tables/930779c1b2482e65c3f1e2220d3026e0679177e60d618391c9a6723faac35a51.jpg)

![a45dceee45047440ac961baf0df07f8549c5c2f17378a901bfa3ccba10ca03c5.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/tables/a45dceee45047440ac961baf0df07f8549c5c2f17378a901bfa3ccba10ca03c5.jpg)

![baa22b35b7aca695af18cc1459847708cb30d3f51986c47063c5707c00bf745c.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/tables/baa22b35b7aca695af18cc1459847708cb30d3f51986c47063c5707c00bf745c.jpg)

![e678117d0797e307d84de2e91d653e32964549c4b48e49f59186cdb84efdd5f8.jpg](../nips_results/1054_Mixture%20of%20Noise%20for%20Pre-Trained%20Model-Based%20Class-Incremental%20Learning/tables/e678117d0797e307d84de2e91d653e32964549c4b48e49f59186cdb84efdd5f8.jpg)

## Segment Anything Model Meets Semi-supervised Medical Image Segmentation: A Novel Perspective


### Images

![09860b1047df2176525159d7d10d8895123bcce819187a8968748b7e5e87e6bd.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/images/09860b1047df2176525159d7d10d8895123bcce819187a8968748b7e5e87e6bd.jpg)

![22a2ac7668727bd736046df671c3bf638a879568af52c945835e4e0111d61887.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/images/22a2ac7668727bd736046df671c3bf638a879568af52c945835e4e0111d61887.jpg)

![7832cfcb308a181741ef5d7d91a11534b182191324737dd23549c1328da2c869.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/images/7832cfcb308a181741ef5d7d91a11534b182191324737dd23549c1328da2c869.jpg)

![b866c09c41feda2ff49d33038bade72cae173799e4824b04494fa7d403646f40.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/images/b866c09c41feda2ff49d33038bade72cae173799e4824b04494fa7d403646f40.jpg)

![df3f1e9d876dc46353fbdcba246f2921ddb70ec9f605d89f5c5d425d8deb114a.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/images/df3f1e9d876dc46353fbdcba246f2921ddb70ec9f605d89f5c5d425d8deb114a.jpg)

### Tables

![045fd438eec944594ac51d8fae5abe23f4fc5cd4edfcb5aa7faf665e35f7251e.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/tables/045fd438eec944594ac51d8fae5abe23f4fc5cd4edfcb5aa7faf665e35f7251e.jpg)

![4301ba01e939b11024122298edbadb40754eadadc1d5787903f81ab1aac98333.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/tables/4301ba01e939b11024122298edbadb40754eadadc1d5787903f81ab1aac98333.jpg)

![6ebf856966664b0811a000a33e6a212ae8ee58442e08ba08f6189ffddbd152be.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/tables/6ebf856966664b0811a000a33e6a212ae8ee58442e08ba08f6189ffddbd152be.jpg)

![92f1ae33375ec82926fff5f12a37904a213561746458ce2be351484fe940eac7.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/tables/92f1ae33375ec82926fff5f12a37904a213561746458ce2be351484fe940eac7.jpg)

![bf2d19e9b673e7383521fd3ec2aaa94971adb2c8dd822d2a671edfceb238caff.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/tables/bf2d19e9b673e7383521fd3ec2aaa94971adb2c8dd822d2a671edfceb238caff.jpg)

![c0de82ec521856f2722ae5725cfec067c2078e569c976e38beebdbfe1d587fa7.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/tables/c0de82ec521856f2722ae5725cfec067c2078e569c976e38beebdbfe1d587fa7.jpg)

![ede7927e816203caa499f21fdb082935ab9d11bd0ad580644a75afc31fc2333c.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/tables/ede7927e816203caa499f21fdb082935ab9d11bd0ad580644a75afc31fc2333c.jpg)

![fa5ec04b7c1bdea8a56ffd87522a402444898459c5074c25821c5bfed7c5fd01.jpg](../nips_results/1055_Segment%20Anything%20Model%20Meets%20Semi-supervised%20Medical%20Image%20Segmentation_%20A%20Novel%20Perspective/tables/fa5ec04b7c1bdea8a56ffd87522a402444898459c5074c25821c5bfed7c5fd01.jpg)

## TaDiCodec: Text-aware Diffusion Speech Tokenizer for Speech Language Modeling


### Images

![472b5c3321a006d6bacf4840e0c3c4672ab20d1f90884efedc9ddabd99707758.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/images/472b5c3321a006d6bacf4840e0c3c4672ab20d1f90884efedc9ddabd99707758.jpg)

![830c56677afc5fbc44b28fb0670f1dafe05df5dec11f0f267723ce68bea0055c.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/images/830c56677afc5fbc44b28fb0670f1dafe05df5dec11f0f267723ce68bea0055c.jpg)

![a0fea016f8093a19fbc22f7c0402d10a6f4d63ceb5f05d0a0a28a0654a3f4022.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/images/a0fea016f8093a19fbc22f7c0402d10a6f4d63ceb5f05d0a0a28a0654a3f4022.jpg)

![e9f63cc5c04e1cefba2fdb84250e3b711776201dd2d8f05ef9d6807b41dcd323.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/images/e9f63cc5c04e1cefba2fdb84250e3b711776201dd2d8f05ef9d6807b41dcd323.jpg)

![eb6ded38ef80aa5bde2ab58d5cf37cda5293eb9232f3cdf7606c66390c6fbabd.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/images/eb6ded38ef80aa5bde2ab58d5cf37cda5293eb9232f3cdf7606c66390c6fbabd.jpg)

### Tables

![27bc7492b89914b3b33f4309f443ad258235a0997c930cfd4d41968386ba228f.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/tables/27bc7492b89914b3b33f4309f443ad258235a0997c930cfd4d41968386ba228f.jpg)

![6f81863394686b6f53361db9822ca15b2c70fd62f751f43fddfd47d26ed66d55.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/tables/6f81863394686b6f53361db9822ca15b2c70fd62f751f43fddfd47d26ed66d55.jpg)

![725cf5a5e379262a8df340fdf3300c7e4280194a61a12fd8bf22d410097ad7ff.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/tables/725cf5a5e379262a8df340fdf3300c7e4280194a61a12fd8bf22d410097ad7ff.jpg)

![9943dbdf854959822c3b20abfb1419d8331975b2375570f0600b2b59ec66adf9.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/tables/9943dbdf854959822c3b20abfb1419d8331975b2375570f0600b2b59ec66adf9.jpg)

![d33e54cbaac39c21b0ec7fb876b244561ded01d0c5719f669e4aa1f6a9eb4412.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/tables/d33e54cbaac39c21b0ec7fb876b244561ded01d0c5719f669e4aa1f6a9eb4412.jpg)

![f9fc2da1bf552017d50f56f423d6796d68e41742693bc5224ca0b5ba8b9214a7.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/tables/f9fc2da1bf552017d50f56f423d6796d68e41742693bc5224ca0b5ba8b9214a7.jpg)

![fe501869e5d78520ec25afdbda599211458df2cb520eee1aefa7cd596fc77903.jpg](../nips_results/1056_TaDiCodec_%20Text-aware%20Diffusion%20Speech%20Tokenizer%20for%20Speech%20Language%20Modeling/tables/fe501869e5d78520ec25afdbda599211458df2cb520eee1aefa7cd596fc77903.jpg)

## Salient Concept-Aware Generative Data Augmentation


### Images

![0058b943b551cb3a62742170c7468804a5c44b03a3c520410b0aa5a3930bb71d.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/images/0058b943b551cb3a62742170c7468804a5c44b03a3c520410b0aa5a3930bb71d.jpg)

![210377e9f2f241a652a86630f84df0c2459a1b93be440fe74985bb9d03124f83.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/images/210377e9f2f241a652a86630f84df0c2459a1b93be440fe74985bb9d03124f83.jpg)

![9ca06e20f4646f7b2941bd645edf9093a6fbaa39cbc3e2476359f03e609f7e5a.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/images/9ca06e20f4646f7b2941bd645edf9093a6fbaa39cbc3e2476359f03e609f7e5a.jpg)

![be9b4e9830bee448395d24edec94694c26aeeb246cf89f59f16d4e4a317adbfb.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/images/be9b4e9830bee448395d24edec94694c26aeeb246cf89f59f16d4e4a317adbfb.jpg)

### Tables

![08f3d2adc52517b0d8d4d3b2d9c606e452717bf94f0d532302a86700a0bc070f.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/08f3d2adc52517b0d8d4d3b2d9c606e452717bf94f0d532302a86700a0bc070f.jpg)

![326d846e9b35768fa212c508812a4879dc6531648de6db939a4218c0cad49402.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/326d846e9b35768fa212c508812a4879dc6531648de6db939a4218c0cad49402.jpg)

![34bec5b9ff992bbb1ae9c62d2adcd2f9e35148ca46a28a0c384e33be0f83602e.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/34bec5b9ff992bbb1ae9c62d2adcd2f9e35148ca46a28a0c384e33be0f83602e.jpg)

![41cf6ce23cf41978664a9af9c2ab0c0c8b93725070fd6e89a06cbba22b1cb200.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/41cf6ce23cf41978664a9af9c2ab0c0c8b93725070fd6e89a06cbba22b1cb200.jpg)

![4451f9727f500ac84540863ec401360a0acb39513d85bf456c5c351f8fdb390c.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/4451f9727f500ac84540863ec401360a0acb39513d85bf456c5c351f8fdb390c.jpg)

![53e1a048e79bc31fc9b35fec664333fe6bef046a28897910ce099e7ea96e6d1e.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/53e1a048e79bc31fc9b35fec664333fe6bef046a28897910ce099e7ea96e6d1e.jpg)

![8950f00fd4dace4d0ce02426971b4ecf313f4dc59f9345423f1451a8d6a1cb90.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/8950f00fd4dace4d0ce02426971b4ecf313f4dc59f9345423f1451a8d6a1cb90.jpg)

![8ef86ba6fe8ab0605d8a78c563488c558d539f8ce9d6523db2d934028c7e11d3.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/8ef86ba6fe8ab0605d8a78c563488c558d539f8ce9d6523db2d934028c7e11d3.jpg)

![96a1d5b3151b4e9e7790bac474513a687b3f21d9a7ed74f9d2e2dbd3c411873f.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/96a1d5b3151b4e9e7790bac474513a687b3f21d9a7ed74f9d2e2dbd3c411873f.jpg)

![b76e8ddd3e1c07a3b4a8f82a4412c8add94677580d28a20acae211902edd392b.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/b76e8ddd3e1c07a3b4a8f82a4412c8add94677580d28a20acae211902edd392b.jpg)

![cae2ef05dd65e39a932e51d0efb8379802bc8cc89173cbefd8e3b405c9e5421d.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/cae2ef05dd65e39a932e51d0efb8379802bc8cc89173cbefd8e3b405c9e5421d.jpg)

![cee08f554e019c4dc812b16692293b541d9a6c9a9703c43b154b45c6c29ca3c1.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/cee08f554e019c4dc812b16692293b541d9a6c9a9703c43b154b45c6c29ca3c1.jpg)

![d148c3962601375f154ddb7f552d5c5a2dc68d691b2faa9e924ac0b68f172506.jpg](../nips_results/1057_Salient%20Concept-Aware%20Generative%20Data%20Augmentation/tables/d148c3962601375f154ddb7f552d5c5a2dc68d691b2faa9e924ac0b68f172506.jpg)

## The Mirage of Performance Gains: Why Contrastive Decoding Fails to Mitigate Object Hallucinations in MLLMs?


### Images

![3500924d8d48346197ef7dc16941816b5c258136420fe206478cc43bfae48d48.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/images/3500924d8d48346197ef7dc16941816b5c258136420fe206478cc43bfae48d48.jpg)

![414950c3ead54ed592ff62cf28c83154e3b2feefaf4128e2e1dd53e8bd7ea19a.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/images/414950c3ead54ed592ff62cf28c83154e3b2feefaf4128e2e1dd53e8bd7ea19a.jpg)

![44598cc523d90ec3fd1ba4df2b90df9df4eea53192b6c2b65baaa8ebc200c58c.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/images/44598cc523d90ec3fd1ba4df2b90df9df4eea53192b6c2b65baaa8ebc200c58c.jpg)

![d0b4d5d77434e75287f006a2749c7562ed56b1c78b26007898289efaaa7dca12.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/images/d0b4d5d77434e75287f006a2749c7562ed56b1c78b26007898289efaaa7dca12.jpg)

![d428e69912f931d67cf61fbf85f129364871ccf3ba97f10a9abb93eff521e65e.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/images/d428e69912f931d67cf61fbf85f129364871ccf3ba97f10a9abb93eff521e65e.jpg)

![da2cfa822df9d5ac45e54fbf298a2c22bc05bfa5c16f0ccc46ea677389275e4c.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/images/da2cfa822df9d5ac45e54fbf298a2c22bc05bfa5c16f0ccc46ea677389275e4c.jpg)

![e4c5d2cb9c850a177da506fec2a35df4fa8360dd75a12d9453e664e1ea2c0f76.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/images/e4c5d2cb9c850a177da506fec2a35df4fa8360dd75a12d9453e664e1ea2c0f76.jpg)

### Tables

![017c340a980f6045c4b86e5e215ecf431ee6e2825ada06251279cc42c97d830c.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/tables/017c340a980f6045c4b86e5e215ecf431ee6e2825ada06251279cc42c97d830c.jpg)

![5509c2d7201f3669ea70c25315001f4db901aacf477a5d5e2dc74ba7733cdde1.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/tables/5509c2d7201f3669ea70c25315001f4db901aacf477a5d5e2dc74ba7733cdde1.jpg)

![5995edf187b76fe79f41492474bb7d7031b13349aea0602d181d0eb360b0f84b.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/tables/5995edf187b76fe79f41492474bb7d7031b13349aea0602d181d0eb360b0f84b.jpg)

![73bdd1c302113bb70d8132639cb2e6074c2210c89105572edfd08cd4c566fb62.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/tables/73bdd1c302113bb70d8132639cb2e6074c2210c89105572edfd08cd4c566fb62.jpg)

![9f6fb114c01f6eda29dcfaab738f3eb6b4e4a6e7bab09f9df81b95530dc09241.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/tables/9f6fb114c01f6eda29dcfaab738f3eb6b4e4a6e7bab09f9df81b95530dc09241.jpg)

![be203e939b0ecc5c52a5e8fe10b47317abfb7f7266d482f1ca03550d058d535d.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/tables/be203e939b0ecc5c52a5e8fe10b47317abfb7f7266d482f1ca03550d058d535d.jpg)

![d32d9c961cd5202ad697a7acfd61996e3fd1ede60969f0a85fb69dce7b4821c3.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/tables/d32d9c961cd5202ad697a7acfd61996e3fd1ede60969f0a85fb69dce7b4821c3.jpg)

![d6922a580a60bc462b5c45e756f04f8322055b83f8f481f6cf147e27ba061c11.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/tables/d6922a580a60bc462b5c45e756f04f8322055b83f8f481f6cf147e27ba061c11.jpg)

![e4830995c776a5de4f43aa73a287e71a83c97e64cc4a1c9a190003edb624058e.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/tables/e4830995c776a5de4f43aa73a287e71a83c97e64cc4a1c9a190003edb624058e.jpg)

![ec67f0f1895c8d4e6d90bb5cb1f1ff5206e094cb22caa0262834beb784771a96.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/tables/ec67f0f1895c8d4e6d90bb5cb1f1ff5206e094cb22caa0262834beb784771a96.jpg)

![f6f2274475dec84d843fa0697ff653cd5c79c3fb71dd90266cb66fc74ad3f9da.jpg](../nips_results/1058_The%20Mirage%20of%20Performance%20Gains_%20Why%20Contrastive%20Decoding%20Fails%20to%20Mitigate%20Object%20Hallucinations%20in/tables/f6f2274475dec84d843fa0697ff653cd5c79c3fb71dd90266cb66fc74ad3f9da.jpg)

## UnCLe: Towards Scalable Dynamic Causal Discovery in Non-linear Temporal Systems


### Images

![06351f770201127091d7001bce64a7e03eaee9f5e68c9333d6bce6a0536929ae.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/06351f770201127091d7001bce64a7e03eaee9f5e68c9333d6bce6a0536929ae.jpg)

![3ce37a181d9413006f2600e2846fb342f02518f1f7ffb20d74ef3aceb25513a3.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/3ce37a181d9413006f2600e2846fb342f02518f1f7ffb20d74ef3aceb25513a3.jpg)

![50b7081d67d1761f0caac06b75716eb5d2aff1cc1b5c5f84a6c4a0f308ca57d0.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/50b7081d67d1761f0caac06b75716eb5d2aff1cc1b5c5f84a6c4a0f308ca57d0.jpg)

![51c681c60f34bdc2ca2803e229bcf9ea94359015516c2e041cae505a8c443ff1.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/51c681c60f34bdc2ca2803e229bcf9ea94359015516c2e041cae505a8c443ff1.jpg)

![573da204f5820291c3cca0c2402e709e8bce2d5420d15b4e0d39a9ae4236ce5a.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/573da204f5820291c3cca0c2402e709e8bce2d5420d15b4e0d39a9ae4236ce5a.jpg)

![656adf488e8868ebc9c0b20c3a5a227cbdbcac5195f35508e5ae2704a1f3f85f.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/656adf488e8868ebc9c0b20c3a5a227cbdbcac5195f35508e5ae2704a1f3f85f.jpg)

![6b3156648d6884ef344cd621b3e314947c001627eb087d641fead14b48cfc5fe.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/6b3156648d6884ef344cd621b3e314947c001627eb087d641fead14b48cfc5fe.jpg)

![72f62ec6f4e5bb3594788ed13262a541ef032f2d3db39a46268ca4574e137589.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/72f62ec6f4e5bb3594788ed13262a541ef032f2d3db39a46268ca4574e137589.jpg)

![9394d09fdbf548273a04bb290b1f00814f91d0e9e1f5e39455c98c5329b79155.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/9394d09fdbf548273a04bb290b1f00814f91d0e9e1f5e39455c98c5329b79155.jpg)

![a7c926a333565b54ecd9f582a7c148bba64154238c7945544116446c5c4c8fa4.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/a7c926a333565b54ecd9f582a7c148bba64154238c7945544116446c5c4c8fa4.jpg)

![b447bfc252a81c4b1506997706d4bd57843cc8707acfe39fcadc8133fe4393ca.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/b447bfc252a81c4b1506997706d4bd57843cc8707acfe39fcadc8133fe4393ca.jpg)

![b545730bea29222d259f719d99da89b91e8524ebb1996ec3265ee91f7db6c6e5.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/b545730bea29222d259f719d99da89b91e8524ebb1996ec3265ee91f7db6c6e5.jpg)

![c99520093d8af6e5fc0a9e7c5e5641fa380ba5471af27071ee365f7a88611c72.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/c99520093d8af6e5fc0a9e7c5e5641fa380ba5471af27071ee365f7a88611c72.jpg)

![de6bb2b301eca09aa9c1e6b13f51546bf6bc3e1976620c75d87411322d5f88d4.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/de6bb2b301eca09aa9c1e6b13f51546bf6bc3e1976620c75d87411322d5f88d4.jpg)

![e04de7e7647caf373cd68ab24337cdd9f9bee38907cb02eaa1fb37a2517f1aab.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/images/e04de7e7647caf373cd68ab24337cdd9f9bee38907cb02eaa1fb37a2517f1aab.jpg)

### Tables

![05ebf26857282c1df37d3cf271308394450c6df1063dde2acda218b5793aa46d.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/05ebf26857282c1df37d3cf271308394450c6df1063dde2acda218b5793aa46d.jpg)

![05f1b051338eace3bfdac36475ec778f059a798fa1781ea9c02bdb2c1f24a3a7.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/05f1b051338eace3bfdac36475ec778f059a798fa1781ea9c02bdb2c1f24a3a7.jpg)

![0767b28a0c4ec25dafa1bb92bec50d7925c2b54ff754370761fec9c2e8fa1343.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/0767b28a0c4ec25dafa1bb92bec50d7925c2b54ff754370761fec9c2e8fa1343.jpg)

![1558b8512fbfa6a2924458cd78db36ea3b147c6ffba310af67f7fb2e2e437edf.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/1558b8512fbfa6a2924458cd78db36ea3b147c6ffba310af67f7fb2e2e437edf.jpg)

![18113dad0efc4fa217ae262687b31f7462144a509fbc0ac2d4a1d873ae9ddf32.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/18113dad0efc4fa217ae262687b31f7462144a509fbc0ac2d4a1d873ae9ddf32.jpg)

![4f4440843fd91d06713a3be0c52054524b736bc11e1eac4b02c1f0d0ed7a8c62.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/4f4440843fd91d06713a3be0c52054524b736bc11e1eac4b02c1f0d0ed7a8c62.jpg)

![6165d1568862ce8c09583f08e2c801993bf21ccc0999b30685823d513c3bf26a.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/6165d1568862ce8c09583f08e2c801993bf21ccc0999b30685823d513c3bf26a.jpg)

![74f9805a2b223afdd6d29a2f0aa954b6b676b2e2639e2492d7644564d4d6e339.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/74f9805a2b223afdd6d29a2f0aa954b6b676b2e2639e2492d7644564d4d6e339.jpg)

![91353277f2b12798b4149a191b9a27a51669376bfb49ad9783b7db6942d7c2cf.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/91353277f2b12798b4149a191b9a27a51669376bfb49ad9783b7db6942d7c2cf.jpg)

![ac7e439abd7298e8f5c22a09f9dfa821d9e8e772562f031865414d16ce0cdd8f.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/ac7e439abd7298e8f5c22a09f9dfa821d9e8e772562f031865414d16ce0cdd8f.jpg)

![bf50b52fc5b9029e6013cf09afa35e8b5635c12fc195f442a5fd683754301332.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/bf50b52fc5b9029e6013cf09afa35e8b5635c12fc195f442a5fd683754301332.jpg)

![f2bac041c66c8dc4b4f26d39dc4dc2dc59102e73533c035b5d61a339049dbed0.jpg](../nips_results/1059_UnCLe_%20Towards%20Scalable%20Dynamic%20Causal%20Discovery%20in%20Non-linear%20Temporal%20Systems/tables/f2bac041c66c8dc4b4f26d39dc4dc2dc59102e73533c035b5d61a339049dbed0.jpg)

## Regression Trees Know Calculus


### Images

![01f87849e78855bee9c79ad3e13fe6ad1bc661b522a72717feba3e07df5dc883.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/01f87849e78855bee9c79ad3e13fe6ad1bc661b522a72717feba3e07df5dc883.jpg)

![0387360787ac1750378c6419468d172267cdc3afc0767f07f7aded830b52fb93.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/0387360787ac1750378c6419468d172267cdc3afc0767f07f7aded830b52fb93.jpg)

![06d3426b2b31783039c3d6fe72de22e4520ed35dd48574a1d445cafa72a92f46.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/06d3426b2b31783039c3d6fe72de22e4520ed35dd48574a1d445cafa72a92f46.jpg)

![2094f8fbc1128d3e96158e6bc38d3527a39250006d6882ec21820a895d799fdf.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/2094f8fbc1128d3e96158e6bc38d3527a39250006d6882ec21820a895d799fdf.jpg)

![30b2ce33de90ea9d04028643e900fab0c59851447ba5cefce56c7195262dd2ee.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/30b2ce33de90ea9d04028643e900fab0c59851447ba5cefce56c7195262dd2ee.jpg)

![339711d2ce253331fd77cef47c721a20095a7b2c15999af31cd0dcb256b8df94.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/339711d2ce253331fd77cef47c721a20095a7b2c15999af31cd0dcb256b8df94.jpg)

![5c79e3f7759434f419c24ebc6ffd3088ab0eeeb1704012fc7511eb50f149497d.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/5c79e3f7759434f419c24ebc6ffd3088ab0eeeb1704012fc7511eb50f149497d.jpg)

![99947af2adc76e91731b44e4a5b2b972d671041f1a1e7f7acbe47f99b300a3e2.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/99947af2adc76e91731b44e4a5b2b972d671041f1a1e7f7acbe47f99b300a3e2.jpg)

![a02a32bfd911e27f61d70765c6c0152614fad186c278eae68eb6f25b05b15094.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/a02a32bfd911e27f61d70765c6c0152614fad186c278eae68eb6f25b05b15094.jpg)

![a7a7eaba29590c8618f6c2c0d0430ca412737fae8f7836dbc8629d770bbabe45.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/a7a7eaba29590c8618f6c2c0d0430ca412737fae8f7836dbc8629d770bbabe45.jpg)

![b92c6c569a2a32f1efd7a847a1cb3a83c45aa198f1a7bf0d767d00ec6f8471db.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/b92c6c569a2a32f1efd7a847a1cb3a83c45aa198f1a7bf0d767d00ec6f8471db.jpg)

![b9cde5e6b7679cc5f86ebd43e545580e4be3d41ad7566ec29e24098fb550048d.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/b9cde5e6b7679cc5f86ebd43e545580e4be3d41ad7566ec29e24098fb550048d.jpg)

![e48ed9a2791652cd304e147aa40f4afdfc7b7a52ecf29e8841ef121edb36e0cd.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/images/e48ed9a2791652cd304e147aa40f4afdfc7b7a52ecf29e8841ef121edb36e0cd.jpg)

### Tables

![8c72c45a38d90b2a6f23db3c87736422abd3ee310a87cbc88aa5ed163f6dacf0.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/tables/8c72c45a38d90b2a6f23db3c87736422abd3ee310a87cbc88aa5ed163f6dacf0.jpg)

![9cd5e902fa8a5f2adf2d189fc65bba512d8e9097997c2b01acf96a64a3922c40.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/tables/9cd5e902fa8a5f2adf2d189fc65bba512d8e9097997c2b01acf96a64a3922c40.jpg)

![dfb03ba9ddca98a76b384e6045b4e4830aff67d19cdb4bf126fce9f5c817d708.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/tables/dfb03ba9ddca98a76b384e6045b4e4830aff67d19cdb4bf126fce9f5c817d708.jpg)

![f0bc9458aacef45c0ba163241a1a13401193eb215e38f6d83099e8def4a04f6b.jpg](../nips_results/1060_Regression%20Trees%20Know%20Calculus/tables/f0bc9458aacef45c0ba163241a1a13401193eb215e38f6d83099e8def4a04f6b.jpg)

## Model-Informed Flows for Bayesian Inference


### Images

![9bf3e8df7b4d25f6b0ef2981754e386cb42bef8ead37c887085e386903d9bdc3.jpg](../nips_results/1061_Model-Informed%20Flows%20for%20Bayesian%20Inference/images/9bf3e8df7b4d25f6b0ef2981754e386cb42bef8ead37c887085e386903d9bdc3.jpg)

![d4e1526580ac301cc7b1417026b9a80b53bdf6ab1c9e401567a75e5d73247445.jpg](../nips_results/1061_Model-Informed%20Flows%20for%20Bayesian%20Inference/images/d4e1526580ac301cc7b1417026b9a80b53bdf6ab1c9e401567a75e5d73247445.jpg)

### Tables

![17c60da281c44dca5c0a767bd167026e374710a5a3ea13f6801ee0fa5e2c0c58.jpg](../nips_results/1061_Model-Informed%20Flows%20for%20Bayesian%20Inference/tables/17c60da281c44dca5c0a767bd167026e374710a5a3ea13f6801ee0fa5e2c0c58.jpg)

![1b91ffb92e484cc3bb0f84370789c9f098e05ecc4613eaa9f234cc1a577ba33c.jpg](../nips_results/1061_Model-Informed%20Flows%20for%20Bayesian%20Inference/tables/1b91ffb92e484cc3bb0f84370789c9f098e05ecc4613eaa9f234cc1a577ba33c.jpg)

![6f7f65fb2156e35b12d12d2592ef45f1af39a735f0249515cc7aa563aac7bce9.jpg](../nips_results/1061_Model-Informed%20Flows%20for%20Bayesian%20Inference/tables/6f7f65fb2156e35b12d12d2592ef45f1af39a735f0249515cc7aa563aac7bce9.jpg)

![7527a17ca3e46e32b5c3b7a0719500f3a4886c9e193e4deb1c7d5b6cb51fcbcd.jpg](../nips_results/1061_Model-Informed%20Flows%20for%20Bayesian%20Inference/tables/7527a17ca3e46e32b5c3b7a0719500f3a4886c9e193e4deb1c7d5b6cb51fcbcd.jpg)

![b2389511e6539ddc4ada71bbfb7f092d1024318c84706ddbc8a3758259334d50.jpg](../nips_results/1061_Model-Informed%20Flows%20for%20Bayesian%20Inference/tables/b2389511e6539ddc4ada71bbfb7f092d1024318c84706ddbc8a3758259334d50.jpg)

![c18fd3a0d73d740c0342c6b128558ea825c72b45d89fa469e8b82f47c0cb4a82.jpg](../nips_results/1061_Model-Informed%20Flows%20for%20Bayesian%20Inference/tables/c18fd3a0d73d740c0342c6b128558ea825c72b45d89fa469e8b82f47c0cb4a82.jpg)

![d707c28be0593a161554891fb7d95b8f4d4f85215195d41e2a543c85fa837e8f.jpg](../nips_results/1061_Model-Informed%20Flows%20for%20Bayesian%20Inference/tables/d707c28be0593a161554891fb7d95b8f4d4f85215195d41e2a543c85fa837e8f.jpg)

## Towards 3D Objectness Learning in an Open World


### Images

![0e766aabb9fa3cbf2840341bfb2771e21d0ea088abf30e100cf5c8b81129687d.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/images/0e766aabb9fa3cbf2840341bfb2771e21d0ea088abf30e100cf5c8b81129687d.jpg)

![267dd9a1d886ebb9d1c62751b02c02ee3a9d66c6d7b8d520e0f327589cded1e7.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/images/267dd9a1d886ebb9d1c62751b02c02ee3a9d66c6d7b8d520e0f327589cded1e7.jpg)

![2f51090830c80de3d6b0b545c1c12b411c72fa18c689449a496236a767b48f3a.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/images/2f51090830c80de3d6b0b545c1c12b411c72fa18c689449a496236a767b48f3a.jpg)

![4c0a4f18c18a738ba1397155786a8ce7997f1046085ec3ba0499e0f7b72382bc.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/images/4c0a4f18c18a738ba1397155786a8ce7997f1046085ec3ba0499e0f7b72382bc.jpg)

![7e9861b6ab1d999da54bd5674d17763fc13ceb2b305b9352bb32ee18d08fc500.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/images/7e9861b6ab1d999da54bd5674d17763fc13ceb2b305b9352bb32ee18d08fc500.jpg)

![aeebf737b9c60d2007c07f6402618dc31147daca8faafe3cb96bcb27a27d47e2.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/images/aeebf737b9c60d2007c07f6402618dc31147daca8faafe3cb96bcb27a27d47e2.jpg)

![b64f5f6618caf7c4115f1aca65b5403afd291ea387a9f8847fa80d9a024b1fa6.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/images/b64f5f6618caf7c4115f1aca65b5403afd291ea387a9f8847fa80d9a024b1fa6.jpg)

### Tables

![0a3dd035a4b33cfef988cde38e4280146eeb0af5c786cd4d2072290bd299b637.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/tables/0a3dd035a4b33cfef988cde38e4280146eeb0af5c786cd4d2072290bd299b637.jpg)

![26a84db5be88b997e3a6eb3a2c68c9781362cf20b011ed1feec0f9559c93b853.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/tables/26a84db5be88b997e3a6eb3a2c68c9781362cf20b011ed1feec0f9559c93b853.jpg)

![27c45b9a2e2866816d5c78d2cb9d08b5e36bee545af5ceb769a32d71deec24db.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/tables/27c45b9a2e2866816d5c78d2cb9d08b5e36bee545af5ceb769a32d71deec24db.jpg)

![3bef2944d8fc62e53af5f4431dda2341fb84b4e0b5dc3d930cad253910ff2f77.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/tables/3bef2944d8fc62e53af5f4431dda2341fb84b4e0b5dc3d930cad253910ff2f77.jpg)

![8d3002c2f72504afa9d3c70de9f4334a69004fa2c5df6627cc6235654b23c7b7.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/tables/8d3002c2f72504afa9d3c70de9f4334a69004fa2c5df6627cc6235654b23c7b7.jpg)

![934f7f80bd12c00a70a3cffa335774240faeff9e5a07503805c1c64975539ec7.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/tables/934f7f80bd12c00a70a3cffa335774240faeff9e5a07503805c1c64975539ec7.jpg)

![9c4ebd739f885f8620a052cd16ac2319292b42abfbe5603809d927b912443bb5.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/tables/9c4ebd739f885f8620a052cd16ac2319292b42abfbe5603809d927b912443bb5.jpg)

![9e6986601df9f5bb2ce9347adc5995606cae7e37f3aa4cdf9875d5e89758bd47.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/tables/9e6986601df9f5bb2ce9347adc5995606cae7e37f3aa4cdf9875d5e89758bd47.jpg)

![9e932056260aacbced02b142f37ec4b2a95f0dfc517368515dab5951b1fa8f18.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/tables/9e932056260aacbced02b142f37ec4b2a95f0dfc517368515dab5951b1fa8f18.jpg)

![a91caa601c5ff2ffc45ffce20667ccfda89c13163aa2ac40001d8a581cdfe547.jpg](../nips_results/1062_Towards%203D%20Objectness%20Learning%20in%20an%20Open%20World/tables/a91caa601c5ff2ffc45ffce20667ccfda89c13163aa2ac40001d8a581cdfe547.jpg)

## SpecReason: Fast and Accurate Inference-Time Compute via Speculative Reasoning


### Images

![094a3e36edcf3a2dfb6f2c0e4d63831859c5a3c144370a5b5705e4b078d9d336.jpg](../nips_results/1063_SpecReason_%20Fast%20and%20Accurate%20Inference-Time%20Compute%20via%20Speculative%20Reasoning/images/094a3e36edcf3a2dfb6f2c0e4d63831859c5a3c144370a5b5705e4b078d9d336.jpg)

![3e6ab9f568f5496e252f8475edd58c5128e6820e38c54e336e59967c32bb6e4a.jpg](../nips_results/1063_SpecReason_%20Fast%20and%20Accurate%20Inference-Time%20Compute%20via%20Speculative%20Reasoning/images/3e6ab9f568f5496e252f8475edd58c5128e6820e38c54e336e59967c32bb6e4a.jpg)

![506202ff4b8c1842c9498f6f708eba1a68e9d0151abf51e45ff466c1e63d72cd.jpg](../nips_results/1063_SpecReason_%20Fast%20and%20Accurate%20Inference-Time%20Compute%20via%20Speculative%20Reasoning/images/506202ff4b8c1842c9498f6f708eba1a68e9d0151abf51e45ff466c1e63d72cd.jpg)

![8be8b8890195b5b0b88b6703b834f7a8f61c306886c4f62bc398f44fc5e3777e.jpg](../nips_results/1063_SpecReason_%20Fast%20and%20Accurate%20Inference-Time%20Compute%20via%20Speculative%20Reasoning/images/8be8b8890195b5b0b88b6703b834f7a8f61c306886c4f62bc398f44fc5e3777e.jpg)

![a05705ed864992173306f65ec6538a7aa08447320ff80e96ca0fd8276eceb249.jpg](../nips_results/1063_SpecReason_%20Fast%20and%20Accurate%20Inference-Time%20Compute%20via%20Speculative%20Reasoning/images/a05705ed864992173306f65ec6538a7aa08447320ff80e96ca0fd8276eceb249.jpg)

![a31927fea32ca656a28c5627b3ef71c7c68137466f122adbad1bfe61276a791b.jpg](../nips_results/1063_SpecReason_%20Fast%20and%20Accurate%20Inference-Time%20Compute%20via%20Speculative%20Reasoning/images/a31927fea32ca656a28c5627b3ef71c7c68137466f122adbad1bfe61276a791b.jpg)

![bc55a4433ceefa19b699563dbb80a3d6ea97672b57fdb4db26dd363544375d59.jpg](../nips_results/1063_SpecReason_%20Fast%20and%20Accurate%20Inference-Time%20Compute%20via%20Speculative%20Reasoning/images/bc55a4433ceefa19b699563dbb80a3d6ea97672b57fdb4db26dd363544375d59.jpg)

![e9044af60059a220ef70f0f1e8cab204a30a2392978f95d6299b7e3659c8ddbb.jpg](../nips_results/1063_SpecReason_%20Fast%20and%20Accurate%20Inference-Time%20Compute%20via%20Speculative%20Reasoning/images/e9044af60059a220ef70f0f1e8cab204a30a2392978f95d6299b7e3659c8ddbb.jpg)

![eb7a3755436569ece703f45ec9d2a4a477613c7bc7965e21eb47b296f1268d1b.jpg](../nips_results/1063_SpecReason_%20Fast%20and%20Accurate%20Inference-Time%20Compute%20via%20Speculative%20Reasoning/images/eb7a3755436569ece703f45ec9d2a4a477613c7bc7965e21eb47b296f1268d1b.jpg)

![eca810b7bc1673a38cf57c861d3c0673862848497b658305c1c52cd69fb58dae.jpg](../nips_results/1063_SpecReason_%20Fast%20and%20Accurate%20Inference-Time%20Compute%20via%20Speculative%20Reasoning/images/eca810b7bc1673a38cf57c861d3c0673862848497b658305c1c52cd69fb58dae.jpg)

## Solving Inverse Problems with FLAIR


### Images

![0d906ccaa077cc13f5f58b6c11c34acf0c06846f03753242e71a9f89184ffe55.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/0d906ccaa077cc13f5f58b6c11c34acf0c06846f03753242e71a9f89184ffe55.jpg)

![0e0b7e4305a94df883c9a6db06c365bba4de5457ce14a03fa2f95aed9b8c25bc.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/0e0b7e4305a94df883c9a6db06c365bba4de5457ce14a03fa2f95aed9b8c25bc.jpg)

![1cad91255667eb1a1b68f6afca0abb7a0c46d9464dff44227cac8d9cd770ca77.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/1cad91255667eb1a1b68f6afca0abb7a0c46d9464dff44227cac8d9cd770ca77.jpg)

![347d82f71c0ded1ef6003797dcd33cb5ce93800bcc4cbc79d11c1f1da9ccfa6c.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/347d82f71c0ded1ef6003797dcd33cb5ce93800bcc4cbc79d11c1f1da9ccfa6c.jpg)

![38dafa497bb50fbaea6545963e77d087951b06c02851b170a6f30ad1db904d3a.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/38dafa497bb50fbaea6545963e77d087951b06c02851b170a6f30ad1db904d3a.jpg)

![39cf70dafe5396f5c4d926fff9f67b439181eb61790d842739cd6d0a067c5b1b.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/39cf70dafe5396f5c4d926fff9f67b439181eb61790d842739cd6d0a067c5b1b.jpg)

![814b47b259ef6eca5e20c41dfb2cbde58cf06110b531eb54cb832f5a5e23f53c.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/814b47b259ef6eca5e20c41dfb2cbde58cf06110b531eb54cb832f5a5e23f53c.jpg)

![85b7f8bc2772973a5fe4899978ea97fbf504751b77ba8d945287009c81930af5.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/85b7f8bc2772973a5fe4899978ea97fbf504751b77ba8d945287009c81930af5.jpg)

![8ace7042a0465752521c709c56df0d9427e9d0ac316f05dca6c9d4a43f405d3b.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/8ace7042a0465752521c709c56df0d9427e9d0ac316f05dca6c9d4a43f405d3b.jpg)

![8e06a6ae56fb5821f216dd46c22e84c086ad04a3ee49390e5ce00cba4ef10901.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/8e06a6ae56fb5821f216dd46c22e84c086ad04a3ee49390e5ce00cba4ef10901.jpg)

![a67ceecc3296f816de0b8dd838154c545b985c985b56c0ba2db17207a04c9e5b.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/a67ceecc3296f816de0b8dd838154c545b985c985b56c0ba2db17207a04c9e5b.jpg)

![b7bf76f3625575448d2b9717a8c11393f1b64b61f839372c8f46a14e9adbe9bb.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/b7bf76f3625575448d2b9717a8c11393f1b64b61f839372c8f46a14e9adbe9bb.jpg)

![cb4e27206202c741dfee557967ff2f95d25c37aa629eb2f4c8dced28f23da991.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/cb4e27206202c741dfee557967ff2f95d25c37aa629eb2f4c8dced28f23da991.jpg)

![d1ca376ef11a54c9ad362f223ec0577ecd7e08403823ff4b5974089547c462e2.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/d1ca376ef11a54c9ad362f223ec0577ecd7e08403823ff4b5974089547c462e2.jpg)

![d495f868f35c164a7a6d02519a04a7070a046542b983107bf59cb1c691c563e0.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/d495f868f35c164a7a6d02519a04a7070a046542b983107bf59cb1c691c563e0.jpg)

![e483cf932bee77fbc0ca846ccbd4985f2608eba85d419805f919b27a7d7aea6d.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/images/e483cf932bee77fbc0ca846ccbd4985f2608eba85d419805f919b27a7d7aea6d.jpg)

### Tables

![0322d4ab71543089d2cf1f163f8090102fb10a1bc8fc7ee9ee99381999970c3b.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/0322d4ab71543089d2cf1f163f8090102fb10a1bc8fc7ee9ee99381999970c3b.jpg)

![2317e32458b5db7212f598a204ee8363d5b527f847d00578411aae18bec9cabd.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/2317e32458b5db7212f598a204ee8363d5b527f847d00578411aae18bec9cabd.jpg)

![2ee6c6ca0e9a584626508fdd689ab465e47bd4d2fd9c6097bdd36f66cea8489d.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/2ee6c6ca0e9a584626508fdd689ab465e47bd4d2fd9c6097bdd36f66cea8489d.jpg)

![33a310f50e4a24f3fa78b159bc0aae915f8f1427059d96c03494f65f507fa411.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/33a310f50e4a24f3fa78b159bc0aae915f8f1427059d96c03494f65f507fa411.jpg)

![3e7027d0c1baa0e394447e302927664fcb451143ea6e0accca4c90e637d71577.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/3e7027d0c1baa0e394447e302927664fcb451143ea6e0accca4c90e637d71577.jpg)

![6d4593f9c3fd659e34b3caca3204dda24717744d52c8a62307589a9ee3b69aa7.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/6d4593f9c3fd659e34b3caca3204dda24717744d52c8a62307589a9ee3b69aa7.jpg)

![7447bcbb6e9f1098ec2c232b60cfc957dfd2d926945bed797aaf5109ac7a6d07.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/7447bcbb6e9f1098ec2c232b60cfc957dfd2d926945bed797aaf5109ac7a6d07.jpg)

![776b5307de83756fef1d3d2b19d2c6a2fb3dec7706466438df7d660d9939ebdf.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/776b5307de83756fef1d3d2b19d2c6a2fb3dec7706466438df7d660d9939ebdf.jpg)

![783bb7cec8729cb90e7c169ee42d05748cf31adac0b30f5ea893b8ae1aed8bea.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/783bb7cec8729cb90e7c169ee42d05748cf31adac0b30f5ea893b8ae1aed8bea.jpg)

![a4f34547b24c8db664166967237bf752d0f45a94e2608644642399ff2e099261.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/a4f34547b24c8db664166967237bf752d0f45a94e2608644642399ff2e099261.jpg)

![a69166e103a44e613d15630fe496a0beaaf3ebe269c51adff61fda111d478213.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/a69166e103a44e613d15630fe496a0beaaf3ebe269c51adff61fda111d478213.jpg)

![aba31d6c9644fc3860a391d3d36539a136c8f9e5baf3e312b819d1ae95d02180.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/aba31d6c9644fc3860a391d3d36539a136c8f9e5baf3e312b819d1ae95d02180.jpg)

![b8b8fc04c1c1b1c39d74b799b60b5c006c6af7fb4c862355ea0da58bd12f160f.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/b8b8fc04c1c1b1c39d74b799b60b5c006c6af7fb4c862355ea0da58bd12f160f.jpg)

![badea16250be27ea21986a65ea6d88b2dc795309bb0035886d1d8f21ad6ef61b.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/badea16250be27ea21986a65ea6d88b2dc795309bb0035886d1d8f21ad6ef61b.jpg)

![c04ebb3f4170b7f488d446e407759f000dc61175bf7e4629ab3424f584ee3484.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/c04ebb3f4170b7f488d446e407759f000dc61175bf7e4629ab3424f584ee3484.jpg)

![dd41e861623658b64f96df647bd80ec53a6b55e084f790ecb1b90c4d7acb763f.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/dd41e861623658b64f96df647bd80ec53a6b55e084f790ecb1b90c4d7acb763f.jpg)

![e0002ebe948e58c25be94341de76e907f7c484e8103b87a00e3c955033d2dcf9.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/e0002ebe948e58c25be94341de76e907f7c484e8103b87a00e3c955033d2dcf9.jpg)

![e2d832845c0dc037d5bbd4b35306e01dcd22b4aa94cb19d08c9add0e49446c1f.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/e2d832845c0dc037d5bbd4b35306e01dcd22b4aa94cb19d08c9add0e49446c1f.jpg)

![e6ae2d159d58fea37e47f89c00d30971f1ff21afd3b8ddffd37543dcb8b04634.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/e6ae2d159d58fea37e47f89c00d30971f1ff21afd3b8ddffd37543dcb8b04634.jpg)

![ec3507e989a518f3a2e227fb777563fc88c7dc88358bb5b1d999cab828a2c80b.jpg](../nips_results/1064_Solving%20Inverse%20Problems%20with%20FLAIR/tables/ec3507e989a518f3a2e227fb777563fc88c7dc88358bb5b1d999cab828a2c80b.jpg)

## CLIPTTA: Robust Contrastive Vision-Language Test-Time Adaptation


### Images

![29bb7604e1b4037094addd278ececf6d18bc99567c61f7efd2ce007c6515ac50.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/images/29bb7604e1b4037094addd278ececf6d18bc99567c61f7efd2ce007c6515ac50.jpg)

![2d6d9facfd6cc2cd1a4a47d6fba0a543be7e61c28476ba2894395a610b65f877.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/images/2d6d9facfd6cc2cd1a4a47d6fba0a543be7e61c28476ba2894395a610b65f877.jpg)

![332e6ae671e66cd3b4605eb58c31081184240c7da3900a865079ba0740cd3728.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/images/332e6ae671e66cd3b4605eb58c31081184240c7da3900a865079ba0740cd3728.jpg)

![3e07681efae4d328069ce90c781ffacd90b0fff1e325086b8c21dfd474b5170f.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/images/3e07681efae4d328069ce90c781ffacd90b0fff1e325086b8c21dfd474b5170f.jpg)

![7dabcf9d9ff5bf996f7a2641672ed842295f612ebb3a6b091edfa233cbcd551d.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/images/7dabcf9d9ff5bf996f7a2641672ed842295f612ebb3a6b091edfa233cbcd551d.jpg)

![8b355a310c7c71c1ea741fb1c9e54826d818c7fca5d61ffe5fd1ff99d0b66067.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/images/8b355a310c7c71c1ea741fb1c9e54826d818c7fca5d61ffe5fd1ff99d0b66067.jpg)

![bf9742f5b4b402848f7a350e82f3961c7e35017e08ca37103fe27c2df4b2eb74.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/images/bf9742f5b4b402848f7a350e82f3961c7e35017e08ca37103fe27c2df4b2eb74.jpg)

### Tables

![067ab42b86c23d6a7b2da8cd9d055b486743c74296e5550a2b63f8e91743fd81.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/067ab42b86c23d6a7b2da8cd9d055b486743c74296e5550a2b63f8e91743fd81.jpg)

![11ac04a7ada3964ec58905e730342768eab3efb4a1568a3786c1a15bc6bf38eb.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/11ac04a7ada3964ec58905e730342768eab3efb4a1568a3786c1a15bc6bf38eb.jpg)

![1d1ec029b726da074b7ae53f29daf0589850a1b2724eb2e3291014c836b429be.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/1d1ec029b726da074b7ae53f29daf0589850a1b2724eb2e3291014c836b429be.jpg)

![31c8ca6727e43532c39aa04d2abb97604df0480ab383efe3a0030e8660ffa17b.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/31c8ca6727e43532c39aa04d2abb97604df0480ab383efe3a0030e8660ffa17b.jpg)

![3de09f0e4a7374761f13640832c9d9db15e5c6693b3401065aa9b05324380399.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/3de09f0e4a7374761f13640832c9d9db15e5c6693b3401065aa9b05324380399.jpg)

![46992f09e376baac52c209282a9df4154e2b48563c83e94398449c67722c4097.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/46992f09e376baac52c209282a9df4154e2b48563c83e94398449c67722c4097.jpg)

![4bbc48796cc8ad1fbe0cd344cc9279efccc63cf500d0d08f53277b7e67ae6d45.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/4bbc48796cc8ad1fbe0cd344cc9279efccc63cf500d0d08f53277b7e67ae6d45.jpg)

![5766c8f0abb7dd8da81ebab814b7f6b1fc64d9d7f8fd6136d8bc08b00d567507.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/5766c8f0abb7dd8da81ebab814b7f6b1fc64d9d7f8fd6136d8bc08b00d567507.jpg)

![685a2254b56f9ceae6c9833d59a52540372b6451f5735c84844f7536571cd03c.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/685a2254b56f9ceae6c9833d59a52540372b6451f5735c84844f7536571cd03c.jpg)

![6a8b7f3b1e367ae6f09102ba1b0c10859c4d675834ad906fa2e604ec957528ff.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/6a8b7f3b1e367ae6f09102ba1b0c10859c4d675834ad906fa2e604ec957528ff.jpg)

![704ca03b5deb3c9127f23981dca0250bcaccf88dde6a4a540d96723438898b73.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/704ca03b5deb3c9127f23981dca0250bcaccf88dde6a4a540d96723438898b73.jpg)

![91beefbf68a7f5a46f68caca5c61779bd45c4c49e417c46e89b3ee208320dd1d.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/91beefbf68a7f5a46f68caca5c61779bd45c4c49e417c46e89b3ee208320dd1d.jpg)

![95beda7917d5b727d2cf0a7a835255990753df1dbc3e83a48d6ad232d8763bb3.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/95beda7917d5b727d2cf0a7a835255990753df1dbc3e83a48d6ad232d8763bb3.jpg)

![966f8818af40a0c41a50413f5b00705e901a6c3f959653a8de49a8509987dd89.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/966f8818af40a0c41a50413f5b00705e901a6c3f959653a8de49a8509987dd89.jpg)

![af7a237a8102c30183644118dfb6926da51131a33d6410f61c97a95cae697231.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/af7a237a8102c30183644118dfb6926da51131a33d6410f61c97a95cae697231.jpg)

![c6b7d4212bef3efcbb71d4d74c8cf3f0f1e0eb40eeeabc3929871d1724ee0859.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/c6b7d4212bef3efcbb71d4d74c8cf3f0f1e0eb40eeeabc3929871d1724ee0859.jpg)

![dac68d2d50fc9a75c6ed7b08be3327429c39bd8e044fed0bcb01296d0ee39ef7.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/dac68d2d50fc9a75c6ed7b08be3327429c39bd8e044fed0bcb01296d0ee39ef7.jpg)

![dbfd57c474c4e2ca1459bfa2bddbd33d5584eddfb0a7c70945fbc85ee91e1a56.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/dbfd57c474c4e2ca1459bfa2bddbd33d5584eddfb0a7c70945fbc85ee91e1a56.jpg)

![e14ba21864171874dcf8701bff520414603b3bc6fc8877cb1c49659cdcb0fbf1.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/e14ba21864171874dcf8701bff520414603b3bc6fc8877cb1c49659cdcb0fbf1.jpg)

![ef86e07467de8342a85edbb263042329c630fca91cc47bb28f593bff1a296f01.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/ef86e07467de8342a85edbb263042329c630fca91cc47bb28f593bff1a296f01.jpg)

![efa29d1c463da0d0f96077e6a979268ce6c45707fe5766bc2bc02b65a721cdf8.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/efa29d1c463da0d0f96077e6a979268ce6c45707fe5766bc2bc02b65a721cdf8.jpg)

![f8fde173032cd4552efad0a67b21600672d2c171f092ec67785dcb520882c340.jpg](../nips_results/1065_CLIPTTA_%20Robust%20Contrastive%20Vision-Language%20Test-Time%20Adaptation/tables/f8fde173032cd4552efad0a67b21600672d2c171f092ec67785dcb520882c340.jpg)

## Venus-MAXWELL: Efficient Learning of Protein-Mutation Stability Landscapes using Protein Language Models


### Images

![0e529aa81e396c041b8b544918912f1845a5bd75e1cdd9dcff1070e23542310a.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/images/0e529aa81e396c041b8b544918912f1845a5bd75e1cdd9dcff1070e23542310a.jpg)

![6fd82376ea8468701cef391ea3187e5edb1e994a1481d6b88cbb4148edfb8e08.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/images/6fd82376ea8468701cef391ea3187e5edb1e994a1481d6b88cbb4148edfb8e08.jpg)

![d27a886d3c14c2a6a15303d7613aa5783cfce137fff0dc6bd0f6178bfabf0a25.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/images/d27a886d3c14c2a6a15303d7613aa5783cfce137fff0dc6bd0f6178bfabf0a25.jpg)

![d5367cd8e891a0ae95e90c9d4b3f298fef72cc9794141904da96941bdf3a1872.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/images/d5367cd8e891a0ae95e90c9d4b3f298fef72cc9794141904da96941bdf3a1872.jpg)

![e00a369b170df10ee7660004c465287bacfc19dcd7f211f2d70b1f027fe61837.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/images/e00a369b170df10ee7660004c465287bacfc19dcd7f211f2d70b1f027fe61837.jpg)

![f51b145f29a01cfeb33acbdd1875834e3dd1a2b5f82fecc07f032aa9b28dcd42.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/images/f51b145f29a01cfeb33acbdd1875834e3dd1a2b5f82fecc07f032aa9b28dcd42.jpg)

### Tables

![213c1445bf8500f74443ef84b22b458e5b4f5819c50f612da205a27d4b412c7a.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/tables/213c1445bf8500f74443ef84b22b458e5b4f5819c50f612da205a27d4b412c7a.jpg)

![2b19dda6fb8c75ca7bc48a5e9616c42e01ccb46d186391f54c4bbab785b4889d.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/tables/2b19dda6fb8c75ca7bc48a5e9616c42e01ccb46d186391f54c4bbab785b4889d.jpg)

![31fb8d81eec47e7dfa99712aee9d4939a04ad5c0b8221ccb6ce6ed99af3117cf.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/tables/31fb8d81eec47e7dfa99712aee9d4939a04ad5c0b8221ccb6ce6ed99af3117cf.jpg)

![3eafdbca93de98cbee8ae4eab4e4d2c0e310aba52d73d7f47ce9c2cc590ce80a.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/tables/3eafdbca93de98cbee8ae4eab4e4d2c0e310aba52d73d7f47ce9c2cc590ce80a.jpg)

![43bf364bd6fb4efe68b9de2f54258fb74507cef5bb7a73cdc798a288d884866e.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/tables/43bf364bd6fb4efe68b9de2f54258fb74507cef5bb7a73cdc798a288d884866e.jpg)

![46afb8155ba09030a07d893a4774537dc11e4858a23aeb4bf8bcd96c1f7fee0f.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/tables/46afb8155ba09030a07d893a4774537dc11e4858a23aeb4bf8bcd96c1f7fee0f.jpg)

![6a6201f9f29f29d72746d36644ab7ad4f1cbc86138fe7fc9c5e10642560f3db6.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/tables/6a6201f9f29f29d72746d36644ab7ad4f1cbc86138fe7fc9c5e10642560f3db6.jpg)

![7e0420825a6348195180aaca9f9eb6205b901227f43be3ce829068da7f361e9d.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/tables/7e0420825a6348195180aaca9f9eb6205b901227f43be3ce829068da7f361e9d.jpg)

![c3c720cebd51ce3ad62597ec52bae9ac2f537526d47643fd51a62eeedc3b04c0.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/tables/c3c720cebd51ce3ad62597ec52bae9ac2f537526d47643fd51a62eeedc3b04c0.jpg)

![e127729613e709c701c32478b73fb193c6b1876e1e710aebe87c7c2c71b5b97a.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/tables/e127729613e709c701c32478b73fb193c6b1876e1e710aebe87c7c2c71b5b97a.jpg)

![fd01f308ce50163eac7d8b4815826759665503748fd9b0b483a10ea48e5ea903.jpg](../nips_results/1066_Venus-MAXWELL_%20Efficient%20Learning%20of%20Protein-Mutation%20Stability%20Landscapes%20using%20Protein%20Language%20Mo/tables/fd01f308ce50163eac7d8b4815826759665503748fd9b0b483a10ea48e5ea903.jpg)

## Principled Model Routing for Unknown Mixtures of Source Domains


### Images

![225fb7ae3d29ff75211b1d08784770a45d1bed266314b87ff725f8e7880df397.jpg](../nips_results/1067_Principled%20Model%20Routing%20for%20Unknown%20Mixtures%20of%20Source%20Domains/images/225fb7ae3d29ff75211b1d08784770a45d1bed266314b87ff725f8e7880df397.jpg)

![35cc8a53e39b979f93e71752fc424372922d5b2949d9a23e91f37910cafc9aa3.jpg](../nips_results/1067_Principled%20Model%20Routing%20for%20Unknown%20Mixtures%20of%20Source%20Domains/images/35cc8a53e39b979f93e71752fc424372922d5b2949d9a23e91f37910cafc9aa3.jpg)

![4cfad76727482121fb7f804f8add207cc3e2d832f79227f1ae2f02a260eb1c4b.jpg](../nips_results/1067_Principled%20Model%20Routing%20for%20Unknown%20Mixtures%20of%20Source%20Domains/images/4cfad76727482121fb7f804f8add207cc3e2d832f79227f1ae2f02a260eb1c4b.jpg)

![707f1c6d575f8c0aa4871ec15fb25b8c1669bc645352cb8c71b77f1ba4534f49.jpg](../nips_results/1067_Principled%20Model%20Routing%20for%20Unknown%20Mixtures%20of%20Source%20Domains/images/707f1c6d575f8c0aa4871ec15fb25b8c1669bc645352cb8c71b77f1ba4534f49.jpg)

![822cb50929c3291d2feabce328c00a876deb42f48716863df70762e90dd39b42.jpg](../nips_results/1067_Principled%20Model%20Routing%20for%20Unknown%20Mixtures%20of%20Source%20Domains/images/822cb50929c3291d2feabce328c00a876deb42f48716863df70762e90dd39b42.jpg)

### Tables

![0cb36d69b2667d31606f882cbfaaff4edac31a9be861aa2583fc7cde9b5e7569.jpg](../nips_results/1067_Principled%20Model%20Routing%20for%20Unknown%20Mixtures%20of%20Source%20Domains/tables/0cb36d69b2667d31606f882cbfaaff4edac31a9be861aa2583fc7cde9b5e7569.jpg)

![f3e8c99599a261f179935c0fc8a2884099548493f7be72126fe65e31925d1ccc.jpg](../nips_results/1067_Principled%20Model%20Routing%20for%20Unknown%20Mixtures%20of%20Source%20Domains/tables/f3e8c99599a261f179935c0fc8a2884099548493f7be72126fe65e31925d1ccc.jpg)

## Latent Harmony: Synergistic Unified UHD Image Restoration via Latent Space Regularization and Controllable Refinement


### Images

![1d6ed5065bb070bc1d41744c83c46d2d37179850068b53f05425c5bae8ff2626.jpg](../nips_results/1068_Latent%20Harmony_%20Synergistic%20Unified%20UHD%20Image%20Restoration%20via%20Latent%20Space%20Regularization%20and%20Contro/images/1d6ed5065bb070bc1d41744c83c46d2d37179850068b53f05425c5bae8ff2626.jpg)

![5f215b34d0f4b4b23bc954647a1c955707e1694814063f0aa950e2dfaa6e2516.jpg](../nips_results/1068_Latent%20Harmony_%20Synergistic%20Unified%20UHD%20Image%20Restoration%20via%20Latent%20Space%20Regularization%20and%20Contro/images/5f215b34d0f4b4b23bc954647a1c955707e1694814063f0aa950e2dfaa6e2516.jpg)

![a44dd4d6eec618b4ff279a4f265704b1749ed1d4f8b8c83f9b86874ccbbe62a7.jpg](../nips_results/1068_Latent%20Harmony_%20Synergistic%20Unified%20UHD%20Image%20Restoration%20via%20Latent%20Space%20Regularization%20and%20Contro/images/a44dd4d6eec618b4ff279a4f265704b1749ed1d4f8b8c83f9b86874ccbbe62a7.jpg)

![f29a9c4920d29d01ee8f2228ae26dca921c05d234dcbcb4eb5b645deb25b74c2.jpg](../nips_results/1068_Latent%20Harmony_%20Synergistic%20Unified%20UHD%20Image%20Restoration%20via%20Latent%20Space%20Regularization%20and%20Contro/images/f29a9c4920d29d01ee8f2228ae26dca921c05d234dcbcb4eb5b645deb25b74c2.jpg)

### Tables

![1dcea35f94d4b55339287a317826c6701ce9a5101eb365c5f9c80ba3643a6d90.jpg](../nips_results/1068_Latent%20Harmony_%20Synergistic%20Unified%20UHD%20Image%20Restoration%20via%20Latent%20Space%20Regularization%20and%20Contro/tables/1dcea35f94d4b55339287a317826c6701ce9a5101eb365c5f9c80ba3643a6d90.jpg)

![22fb8ee1647b545304841f37734519229b05610d29ad6001a593888463914395.jpg](../nips_results/1068_Latent%20Harmony_%20Synergistic%20Unified%20UHD%20Image%20Restoration%20via%20Latent%20Space%20Regularization%20and%20Contro/tables/22fb8ee1647b545304841f37734519229b05610d29ad6001a593888463914395.jpg)

![398baa7d598d7eb68093a29e55fa5f73d1ef45f9c7a8e480f723fb14df8d16e9.jpg](../nips_results/1068_Latent%20Harmony_%20Synergistic%20Unified%20UHD%20Image%20Restoration%20via%20Latent%20Space%20Regularization%20and%20Contro/tables/398baa7d598d7eb68093a29e55fa5f73d1ef45f9c7a8e480f723fb14df8d16e9.jpg)

![61b8d475a6bc7bb6f3abea0e733a7c9c47df212c5c477e7cd12fa1cf9a60cd85.jpg](../nips_results/1068_Latent%20Harmony_%20Synergistic%20Unified%20UHD%20Image%20Restoration%20via%20Latent%20Space%20Regularization%20and%20Contro/tables/61b8d475a6bc7bb6f3abea0e733a7c9c47df212c5c477e7cd12fa1cf9a60cd85.jpg)

![86233ac18ee6d5c035f71edbfe5ed9ba53bf4a395832874f1d141283c09e3c8d.jpg](../nips_results/1068_Latent%20Harmony_%20Synergistic%20Unified%20UHD%20Image%20Restoration%20via%20Latent%20Space%20Regularization%20and%20Contro/tables/86233ac18ee6d5c035f71edbfe5ed9ba53bf4a395832874f1d141283c09e3c8d.jpg)

![8afee34c487d6af7db0f3741eb2bf8e34a839a3610ac2d5520f0ed72b613c5fa.jpg](../nips_results/1068_Latent%20Harmony_%20Synergistic%20Unified%20UHD%20Image%20Restoration%20via%20Latent%20Space%20Regularization%20and%20Contro/tables/8afee34c487d6af7db0f3741eb2bf8e34a839a3610ac2d5520f0ed72b613c5fa.jpg)

## SpaceServe: Spatial Multiplexing of Complementary Encoders and Decoders for Multimodal LLMs


### Images

![268de42d3c9a4c0e4f3d6c7f6c8d62c3bf2ade99d84de1dc80702b15432c9a5b.jpg](../nips_results/1069_SpaceServe_%20Spatial%20Multiplexing%20of%20Complementary%20Encoders%20and%20Decoders%20for%20Multimodal%20LLMs/images/268de42d3c9a4c0e4f3d6c7f6c8d62c3bf2ade99d84de1dc80702b15432c9a5b.jpg)

![4cc46ce8ab7fc62040e3b7aebe63f044996d86379c126673e8b60e86ad855b3c.jpg](../nips_results/1069_SpaceServe_%20Spatial%20Multiplexing%20of%20Complementary%20Encoders%20and%20Decoders%20for%20Multimodal%20LLMs/images/4cc46ce8ab7fc62040e3b7aebe63f044996d86379c126673e8b60e86ad855b3c.jpg)

![87b5b1f3812f2d894cf699fb371e248e8c6aa7c10027d3812c23d4370e0e0df3.jpg](../nips_results/1069_SpaceServe_%20Spatial%20Multiplexing%20of%20Complementary%20Encoders%20and%20Decoders%20for%20Multimodal%20LLMs/images/87b5b1f3812f2d894cf699fb371e248e8c6aa7c10027d3812c23d4370e0e0df3.jpg)

![96afaf4714c1b17b368348ab607a004edc733a8dc1433162ca76423e9b93cfd7.jpg](../nips_results/1069_SpaceServe_%20Spatial%20Multiplexing%20of%20Complementary%20Encoders%20and%20Decoders%20for%20Multimodal%20LLMs/images/96afaf4714c1b17b368348ab607a004edc733a8dc1433162ca76423e9b93cfd7.jpg)

![fe8d74b9bba4e8dacb40f7bfac2e261e282a4e864c32044c5c8b9a88201935ec.jpg](../nips_results/1069_SpaceServe_%20Spatial%20Multiplexing%20of%20Complementary%20Encoders%20and%20Decoders%20for%20Multimodal%20LLMs/images/fe8d74b9bba4e8dacb40f7bfac2e261e282a4e864c32044c5c8b9a88201935ec.jpg)

### Tables

![10f33c2c17646efb420d71c5c1a5c9ee228270463cdaecb0601b6c640802e3ed.jpg](../nips_results/1069_SpaceServe_%20Spatial%20Multiplexing%20of%20Complementary%20Encoders%20and%20Decoders%20for%20Multimodal%20LLMs/tables/10f33c2c17646efb420d71c5c1a5c9ee228270463cdaecb0601b6c640802e3ed.jpg)

![87de953fe995103742a03d81083965abeec7fbfb6c691465a8320d1ec5d9be4c.jpg](../nips_results/1069_SpaceServe_%20Spatial%20Multiplexing%20of%20Complementary%20Encoders%20and%20Decoders%20for%20Multimodal%20LLMs/tables/87de953fe995103742a03d81083965abeec7fbfb6c691465a8320d1ec5d9be4c.jpg)

![8b70e4adbf16b38a4c9cd489406dc3260b5132434be10059cc4b4b36832bede8.jpg](../nips_results/1069_SpaceServe_%20Spatial%20Multiplexing%20of%20Complementary%20Encoders%20and%20Decoders%20for%20Multimodal%20LLMs/tables/8b70e4adbf16b38a4c9cd489406dc3260b5132434be10059cc4b4b36832bede8.jpg)

![ea583f6529519ef1a70cffcb2b306a26a458c1dbcde0fca599cf40c199aadbaf.jpg](../nips_results/1069_SpaceServe_%20Spatial%20Multiplexing%20of%20Complementary%20Encoders%20and%20Decoders%20for%20Multimodal%20LLMs/tables/ea583f6529519ef1a70cffcb2b306a26a458c1dbcde0fca599cf40c199aadbaf.jpg)

## Lyapunov-Stable Adaptive Control for Multimodal Concept Drift


### Images

![19590c1ee784982ed3099497005a814424c475be9f10afdb44c1a9ac27036778.jpg](../nips_results/1070_Lyapunov-Stable%20Adaptive%20Control%20for%20Multimodal%20Concept%20Drift/images/19590c1ee784982ed3099497005a814424c475be9f10afdb44c1a9ac27036778.jpg)

![253874884cecb0cdc9c5af74a4f5d458a5d229d0bf9253191e560cfb8a081852.jpg](../nips_results/1070_Lyapunov-Stable%20Adaptive%20Control%20for%20Multimodal%20Concept%20Drift/images/253874884cecb0cdc9c5af74a4f5d458a5d229d0bf9253191e560cfb8a081852.jpg)

![53e91c93ed7d9f8136afed5e9907471a3d1b9867e9ff97515adc2261893f4a4c.jpg](../nips_results/1070_Lyapunov-Stable%20Adaptive%20Control%20for%20Multimodal%20Concept%20Drift/images/53e91c93ed7d9f8136afed5e9907471a3d1b9867e9ff97515adc2261893f4a4c.jpg)

![6c9e76699b36e4230ab6e6733bfe38d8ac6bc4a5e0e9d6251f5eff5322a47932.jpg](../nips_results/1070_Lyapunov-Stable%20Adaptive%20Control%20for%20Multimodal%20Concept%20Drift/images/6c9e76699b36e4230ab6e6733bfe38d8ac6bc4a5e0e9d6251f5eff5322a47932.jpg)

![8be76ec181984b977c94f08c724329ba2e9ad858fe0fd882152444a9e7cc9f2e.jpg](../nips_results/1070_Lyapunov-Stable%20Adaptive%20Control%20for%20Multimodal%20Concept%20Drift/images/8be76ec181984b977c94f08c724329ba2e9ad858fe0fd882152444a9e7cc9f2e.jpg)

![a1491560437706d7ce60ffd056a42a217624303a572006ba001a87155b4a4939.jpg](../nips_results/1070_Lyapunov-Stable%20Adaptive%20Control%20for%20Multimodal%20Concept%20Drift/images/a1491560437706d7ce60ffd056a42a217624303a572006ba001a87155b4a4939.jpg)

![bb0cab7a2c112c1ba5b1d6e2b771358b211d225babde1e3e55d00a6cddcf8535.jpg](../nips_results/1070_Lyapunov-Stable%20Adaptive%20Control%20for%20Multimodal%20Concept%20Drift/images/bb0cab7a2c112c1ba5b1d6e2b771358b211d225babde1e3e55d00a6cddcf8535.jpg)

![ea48bdc5f240392aa6e9545e025c47bcda5bf34f3191665f779e62448a01637a.jpg](../nips_results/1070_Lyapunov-Stable%20Adaptive%20Control%20for%20Multimodal%20Concept%20Drift/images/ea48bdc5f240392aa6e9545e025c47bcda5bf34f3191665f779e62448a01637a.jpg)

### Tables

![741cba8a8e7b32171a716e3679a6ec7a06355c43f5a6fc0a35bd3da5022de15c.jpg](../nips_results/1070_Lyapunov-Stable%20Adaptive%20Control%20for%20Multimodal%20Concept%20Drift/tables/741cba8a8e7b32171a716e3679a6ec7a06355c43f5a6fc0a35bd3da5022de15c.jpg)

## Beyond Higher Rank: Token-wise Input-Output Projections for Efficient Low-Rank Adaptation


### Images

![11a534fd7ca9961938da43683328638b01177b3a52dfddbaf988f1c603f5fc4c.jpg](../nips_results/1071_Beyond%20Higher%20Rank_%20Token-wise%20Input-Output%20Projections%20for%20Efficient%20Low-Rank%20Adaptation/images/11a534fd7ca9961938da43683328638b01177b3a52dfddbaf988f1c603f5fc4c.jpg)

![ec70da28ea034f1fa520c9bbae99d0c3781b2bae33f24b0e762cea27de47407d.jpg](../nips_results/1071_Beyond%20Higher%20Rank_%20Token-wise%20Input-Output%20Projections%20for%20Efficient%20Low-Rank%20Adaptation/images/ec70da28ea034f1fa520c9bbae99d0c3781b2bae33f24b0e762cea27de47407d.jpg)

### Tables

![2a5bf13ae5b771269c45f198f10ef8a790e8940a8667306f7d0c785eb8c2a228.jpg](../nips_results/1071_Beyond%20Higher%20Rank_%20Token-wise%20Input-Output%20Projections%20for%20Efficient%20Low-Rank%20Adaptation/tables/2a5bf13ae5b771269c45f198f10ef8a790e8940a8667306f7d0c785eb8c2a228.jpg)

![3f045c4c79b096d8de76aa1d548d261424fe7314469f5852022a92a9bdaa709c.jpg](../nips_results/1071_Beyond%20Higher%20Rank_%20Token-wise%20Input-Output%20Projections%20for%20Efficient%20Low-Rank%20Adaptation/tables/3f045c4c79b096d8de76aa1d548d261424fe7314469f5852022a92a9bdaa709c.jpg)

![40ccc362de6a59cc22c3daf617cf523d1ecbc17109a221aa442bd19366b79287.jpg](../nips_results/1071_Beyond%20Higher%20Rank_%20Token-wise%20Input-Output%20Projections%20for%20Efficient%20Low-Rank%20Adaptation/tables/40ccc362de6a59cc22c3daf617cf523d1ecbc17109a221aa442bd19366b79287.jpg)

![b6e655044cb01056610a63ee962912ea32413e5d72aa3dea1f73173a8f6794a0.jpg](../nips_results/1071_Beyond%20Higher%20Rank_%20Token-wise%20Input-Output%20Projections%20for%20Efficient%20Low-Rank%20Adaptation/tables/b6e655044cb01056610a63ee962912ea32413e5d72aa3dea1f73173a8f6794a0.jpg)

![bc56c663b49343460b2e96a9ecd7ab7093870da9bc492c8505a1fdb02060371e.jpg](../nips_results/1071_Beyond%20Higher%20Rank_%20Token-wise%20Input-Output%20Projections%20for%20Efficient%20Low-Rank%20Adaptation/tables/bc56c663b49343460b2e96a9ecd7ab7093870da9bc492c8505a1fdb02060371e.jpg)

![db621ffc9c5da7bb3e37e79d5bd23aa83c60f151c2a7bcb37e9a6b373bcfab0b.jpg](../nips_results/1071_Beyond%20Higher%20Rank_%20Token-wise%20Input-Output%20Projections%20for%20Efficient%20Low-Rank%20Adaptation/tables/db621ffc9c5da7bb3e37e79d5bd23aa83c60f151c2a7bcb37e9a6b373bcfab0b.jpg)

![ddd53323fb12f167c078e75a3f3c358e57a983ff1e228c5f4cdcaf0435ae973f.jpg](../nips_results/1071_Beyond%20Higher%20Rank_%20Token-wise%20Input-Output%20Projections%20for%20Efficient%20Low-Rank%20Adaptation/tables/ddd53323fb12f167c078e75a3f3c358e57a983ff1e228c5f4cdcaf0435ae973f.jpg)

![ff82ddabcf313bdee5f2f3333068530b995e4fc704d1f9b6e1732dccd8f46e1e.jpg](../nips_results/1071_Beyond%20Higher%20Rank_%20Token-wise%20Input-Output%20Projections%20for%20Efficient%20Low-Rank%20Adaptation/tables/ff82ddabcf313bdee5f2f3333068530b995e4fc704d1f9b6e1732dccd8f46e1e.jpg)

## Large Stepsizes Accelerate Gradient Descent for Regularized Logistic Regression


### Images

![6195bc2f3c2abd8963d7199f727d323c8d20f516cb3e7962b0937e9eb97a3345.jpg](../nips_results/1072_Large%20Stepsizes%20Accelerate%20Gradient%20Descent%20for%20Regularized%20Logistic%20Regression/images/6195bc2f3c2abd8963d7199f727d323c8d20f516cb3e7962b0937e9eb97a3345.jpg)

![b133d6495cc911a1fc770953f03823ac49f38b436db7d5f9aea40839ef444b56.jpg](../nips_results/1072_Large%20Stepsizes%20Accelerate%20Gradient%20Descent%20for%20Regularized%20Logistic%20Regression/images/b133d6495cc911a1fc770953f03823ac49f38b436db7d5f9aea40839ef444b56.jpg)

![f3d045dac43cc8b7bd9c0ae856798cc193849231d022b77d89957b7229a64819.jpg](../nips_results/1072_Large%20Stepsizes%20Accelerate%20Gradient%20Descent%20for%20Regularized%20Logistic%20Regression/images/f3d045dac43cc8b7bd9c0ae856798cc193849231d022b77d89957b7229a64819.jpg)

### Tables

![0ad7f861a008ce742499a668b41cc0a50e14c84bebf2406bd8e2375bdbc7d5df.jpg](../nips_results/1072_Large%20Stepsizes%20Accelerate%20Gradient%20Descent%20for%20Regularized%20Logistic%20Regression/tables/0ad7f861a008ce742499a668b41cc0a50e14c84bebf2406bd8e2375bdbc7d5df.jpg)

## Preference-Based Dynamic Ranking Structure Recognition


### Images

![490b8a7d8d0b2aefae88a410c2df69febbe80fd31241de0ad5e7d17f24592b91.jpg](../nips_results/1073_Preference-Based%20Dynamic%20Ranking%20Structure%20Recognition/images/490b8a7d8d0b2aefae88a410c2df69febbe80fd31241de0ad5e7d17f24592b91.jpg)

![4b1a8531f3da4479eb65c61391e3c849f558dd48aebbb7a8b5f1922d4e558360.jpg](../nips_results/1073_Preference-Based%20Dynamic%20Ranking%20Structure%20Recognition/images/4b1a8531f3da4479eb65c61391e3c849f558dd48aebbb7a8b5f1922d4e558360.jpg)

![7e379509f1808065f0ffcf626dfb9b8fb4bd87a2b9389ad6d2531b82c46109c9.jpg](../nips_results/1073_Preference-Based%20Dynamic%20Ranking%20Structure%20Recognition/images/7e379509f1808065f0ffcf626dfb9b8fb4bd87a2b9389ad6d2531b82c46109c9.jpg)

![8cc08bbe64dbba92dd9c6c33303a7b11f691eb0430822d855d3a8494de4c0749.jpg](../nips_results/1073_Preference-Based%20Dynamic%20Ranking%20Structure%20Recognition/images/8cc08bbe64dbba92dd9c6c33303a7b11f691eb0430822d855d3a8494de4c0749.jpg)

![b6139de3a42037098248f90daf6d21eb6b59033de4d95570180ab7dd263f7732.jpg](../nips_results/1073_Preference-Based%20Dynamic%20Ranking%20Structure%20Recognition/images/b6139de3a42037098248f90daf6d21eb6b59033de4d95570180ab7dd263f7732.jpg)

![ee857cdd835346e59a79a220318cfae52480bbf2dde5c78e0295c51cb5c9d591.jpg](../nips_results/1073_Preference-Based%20Dynamic%20Ranking%20Structure%20Recognition/images/ee857cdd835346e59a79a220318cfae52480bbf2dde5c78e0295c51cb5c9d591.jpg)

### Tables

![30904816ba3576606352867bd9aaf23a337d9f6c72e09960ad94f2639daa6fc6.jpg](../nips_results/1073_Preference-Based%20Dynamic%20Ranking%20Structure%20Recognition/tables/30904816ba3576606352867bd9aaf23a337d9f6c72e09960ad94f2639daa6fc6.jpg)

![3d67b28087c4565baf38bba7f96755225abd72187867ee6a29e57004daa328f5.jpg](../nips_results/1073_Preference-Based%20Dynamic%20Ranking%20Structure%20Recognition/tables/3d67b28087c4565baf38bba7f96755225abd72187867ee6a29e57004daa328f5.jpg)

![86db07c17e3deac7d59d286f806dabc012b3fede4de24d47624a133dbad25af6.jpg](../nips_results/1073_Preference-Based%20Dynamic%20Ranking%20Structure%20Recognition/tables/86db07c17e3deac7d59d286f806dabc012b3fede4de24d47624a133dbad25af6.jpg)

![c0f671edb05c8f77036dbb5fc8a701c2d3ae8eda5b02feeff04c7e22c9736dc3.jpg](../nips_results/1073_Preference-Based%20Dynamic%20Ranking%20Structure%20Recognition/tables/c0f671edb05c8f77036dbb5fc8a701c2d3ae8eda5b02feeff04c7e22c9736dc3.jpg)

![f682fa6d38261fff4e848f9d35b91e5a674079c904b155c4a427e7170f9cce90.jpg](../nips_results/1073_Preference-Based%20Dynamic%20Ranking%20Structure%20Recognition/tables/f682fa6d38261fff4e848f9d35b91e5a674079c904b155c4a427e7170f9cce90.jpg)

## Multivariate Time Series Anomaly Detection with Idempotent Reconstruction


### Images

![0076129d21ab44bce54995fe3a21dd392d74fba0870d83363291df106828c497.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/0076129d21ab44bce54995fe3a21dd392d74fba0870d83363291df106828c497.jpg)

![0198f5faf4c3b917a9be61f1da3600461f32a1c07267c1107f550269de391ad1.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/0198f5faf4c3b917a9be61f1da3600461f32a1c07267c1107f550269de391ad1.jpg)

![0840163f5b2a47b965694da6bd144a639e61c262ea49819c3d305f3abdfca3c9.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/0840163f5b2a47b965694da6bd144a639e61c262ea49819c3d305f3abdfca3c9.jpg)

![13475b3dc33e6b40a1ca489a9ea856700baca58cf23690fde83ab83eabc74aa1.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/13475b3dc33e6b40a1ca489a9ea856700baca58cf23690fde83ab83eabc74aa1.jpg)

![1cb34092e4d694067d1ce2e28d187d453b5277ad6d9b4850ab99a3d7ea74b6b3.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/1cb34092e4d694067d1ce2e28d187d453b5277ad6d9b4850ab99a3d7ea74b6b3.jpg)

![294c23838ce599f1e84e2f9c4413ff690cd0fd6b0f87860cdabbe61657c411e7.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/294c23838ce599f1e84e2f9c4413ff690cd0fd6b0f87860cdabbe61657c411e7.jpg)

![2c80540af0a4879d22f540184b190cfaa577ef5a549a98c3008be98606c36093.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/2c80540af0a4879d22f540184b190cfaa577ef5a549a98c3008be98606c36093.jpg)

![2e2c796c991272dd3eccf949742863246734573f756be1b05a73de864aa7e33f.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/2e2c796c991272dd3eccf949742863246734573f756be1b05a73de864aa7e33f.jpg)

![4410b61f1235a3166e3e573f07499e667d7e2598759f49ed783186ad55dcfff7.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/4410b61f1235a3166e3e573f07499e667d7e2598759f49ed783186ad55dcfff7.jpg)

![522df154a596349dc0832a15021cf9323965dfbcdd6f8d9d24449f98924a85f6.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/522df154a596349dc0832a15021cf9323965dfbcdd6f8d9d24449f98924a85f6.jpg)

![531de900ec3265688d276c4bf6f5f06dba11592e93f21a3d831b90e91c6e0cf8.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/531de900ec3265688d276c4bf6f5f06dba11592e93f21a3d831b90e91c6e0cf8.jpg)

![5ade56b5eee97b1816c7c814246ad2cc97cee4f9aaa92be209901200f7ebc98b.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/5ade56b5eee97b1816c7c814246ad2cc97cee4f9aaa92be209901200f7ebc98b.jpg)

![638c128722bca468c3c91f7ac8d9375c2f5f9538c593db99ecb416a0c86aa30f.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/638c128722bca468c3c91f7ac8d9375c2f5f9538c593db99ecb416a0c86aa30f.jpg)

![6608aa97c42d830b2070013b39dbc135e459a0b6b6beb5fc6cd5dc39c8a6e6a9.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/6608aa97c42d830b2070013b39dbc135e459a0b6b6beb5fc6cd5dc39c8a6e6a9.jpg)

![74eb58158861f3ea3467ef5d5a144dc240a5adfcb9f600ff8ccc99bbb37e29cb.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/74eb58158861f3ea3467ef5d5a144dc240a5adfcb9f600ff8ccc99bbb37e29cb.jpg)

![7c634e42053e25a2690646c00ad82351f58bd84fb7760bd39bd857a3fcbfde4c.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/7c634e42053e25a2690646c00ad82351f58bd84fb7760bd39bd857a3fcbfde4c.jpg)

![7d0c273b1d711f408af882b2f07684c3a9b3b43adae681ab833439bd6c800c95.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/7d0c273b1d711f408af882b2f07684c3a9b3b43adae681ab833439bd6c800c95.jpg)

![96b44a514ec27bf82bbbc946d84e90c9e24326b511ce8e30915bb211fe08eeef.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/96b44a514ec27bf82bbbc946d84e90c9e24326b511ce8e30915bb211fe08eeef.jpg)

![98aefeb870ca9ea5fb819f356a6d54c7d71f2e26e040906830d779d87a8ec29a.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/98aefeb870ca9ea5fb819f356a6d54c7d71f2e26e040906830d779d87a8ec29a.jpg)

![9c9cca14d543fa7ba6dd79c853d0c6685d1b0b23dab9092bbd320cc47c741057.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/9c9cca14d543fa7ba6dd79c853d0c6685d1b0b23dab9092bbd320cc47c741057.jpg)

![a733f8db9c2fd49e2f257ac8d77f307b3b796862afd3cbeeb22ba756a69c1297.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/a733f8db9c2fd49e2f257ac8d77f307b3b796862afd3cbeeb22ba756a69c1297.jpg)

![a7c1ebb5b6c5361099abbb29935bd27dd10aa9c42611576ba397ccd7883de7cc.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/a7c1ebb5b6c5361099abbb29935bd27dd10aa9c42611576ba397ccd7883de7cc.jpg)

![ac0b88674b554c377e2a694ba347a06c2614e7a52bc4bed0d64cdab5d44e6f35.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/ac0b88674b554c377e2a694ba347a06c2614e7a52bc4bed0d64cdab5d44e6f35.jpg)

![ad60762d8e7ece24333edf4d0f159887d2ce709be919410f9e2825a1f2ae5631.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/ad60762d8e7ece24333edf4d0f159887d2ce709be919410f9e2825a1f2ae5631.jpg)

![b16daea3e127fc63aaa8173e75055bd0aa6dae1641f6469cc55f0dc6b78a0a14.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/b16daea3e127fc63aaa8173e75055bd0aa6dae1641f6469cc55f0dc6b78a0a14.jpg)

![bfc301fcb44833f13ebf85d25c803267f03e71a4225ccda2daf0e093274b5137.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/bfc301fcb44833f13ebf85d25c803267f03e71a4225ccda2daf0e093274b5137.jpg)

![ceb14441344c7f07d7c1016dd3db36f921da92a43f666029ed7d3757b7be2570.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/ceb14441344c7f07d7c1016dd3db36f921da92a43f666029ed7d3757b7be2570.jpg)

![d308d1b534d700a56afd3790b0c87e615506ea3b45684af31e9667d8e3eb09de.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/d308d1b534d700a56afd3790b0c87e615506ea3b45684af31e9667d8e3eb09de.jpg)

![d6884ed19d91b5cacd6c9294ea75e51d58fa6eaa38edab6e798b34c3c479140a.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/images/d6884ed19d91b5cacd6c9294ea75e51d58fa6eaa38edab6e798b34c3c479140a.jpg)

### Tables

![026e01e39c3895cce97d53e588749772e36bccbfe35d9912ca9be27262ea5263.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/026e01e39c3895cce97d53e588749772e36bccbfe35d9912ca9be27262ea5263.jpg)

![0a1f6e31f85a44ebd5c2a734acaa4c98639bc2afecf69a7d98a2f3838850b3f1.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/0a1f6e31f85a44ebd5c2a734acaa4c98639bc2afecf69a7d98a2f3838850b3f1.jpg)

![10c0f37db44ab05468fa7c576090c1f96e39143d8221a40181c631ee632a9370.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/10c0f37db44ab05468fa7c576090c1f96e39143d8221a40181c631ee632a9370.jpg)

![12a5d98450574b1b74d233a61d28f53c0d7a08b9f9694ad2b574261177165f83.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/12a5d98450574b1b74d233a61d28f53c0d7a08b9f9694ad2b574261177165f83.jpg)

![3d345ebd8f74475d6487e85961a331193e91cf59c2b815ba5fd05705b0ee7bc9.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/3d345ebd8f74475d6487e85961a331193e91cf59c2b815ba5fd05705b0ee7bc9.jpg)

![448401f278a75699ef823b4d29e01a0b777763a0f4bf3243635f02426280dec1.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/448401f278a75699ef823b4d29e01a0b777763a0f4bf3243635f02426280dec1.jpg)

![491f792a8623b4d63d2bfba4a5a08f5cb9de407840b6bf995b671397de89c5f2.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/491f792a8623b4d63d2bfba4a5a08f5cb9de407840b6bf995b671397de89c5f2.jpg)

![565e803b12b7f5f33285a861c9f6a65de8ac7bd108525bbbcf411b05e5519b7b.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/565e803b12b7f5f33285a861c9f6a65de8ac7bd108525bbbcf411b05e5519b7b.jpg)

![7c15a6f3ac7eb51f8015ee51e8933ece2e54d04b330b4e7d881e81a0d37f3f7c.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/7c15a6f3ac7eb51f8015ee51e8933ece2e54d04b330b4e7d881e81a0d37f3f7c.jpg)

![8d3cf31e90c9db2837d288dbe23519cd51efa403cde38ec40cae6eb18f4b5591.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/8d3cf31e90c9db2837d288dbe23519cd51efa403cde38ec40cae6eb18f4b5591.jpg)

![93a3e48101baa146c859b58ecfbc3d8276cfe8ef3227312cc7ac0112312c1014.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/93a3e48101baa146c859b58ecfbc3d8276cfe8ef3227312cc7ac0112312c1014.jpg)

![a7d84b554b221ec351087501c25a2c38c02bfbbb23ef2391d355feb1e4c139ee.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/a7d84b554b221ec351087501c25a2c38c02bfbbb23ef2391d355feb1e4c139ee.jpg)

![adf28da8c896b45035a0dbe2fe1a07a8848fce12b434a167065eb157361fc59c.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/adf28da8c896b45035a0dbe2fe1a07a8848fce12b434a167065eb157361fc59c.jpg)

![c6443bfb65b81a80c649105358f24d6353af41b84c557fcf408da79926674b67.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/c6443bfb65b81a80c649105358f24d6353af41b84c557fcf408da79926674b67.jpg)

![d7979fa962e4e0c74b1c1dc110b4441f64a380a6c232e1fedb79b87141f61392.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/d7979fa962e4e0c74b1c1dc110b4441f64a380a6c232e1fedb79b87141f61392.jpg)

![e0149a6f7ec054b6c59ada636cca5e3790c49d1f25a2080de37047e0914914c7.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/e0149a6f7ec054b6c59ada636cca5e3790c49d1f25a2080de37047e0914914c7.jpg)

![e0f2aaccf6702f43a2709108d269157fccc048b24bf557ff86fd53df747c2a8b.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/e0f2aaccf6702f43a2709108d269157fccc048b24bf557ff86fd53df747c2a8b.jpg)

![ef4bea8b54d921d978ada56a9a354b521f542c69210048b4d36aaeae7b000f2b.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/ef4bea8b54d921d978ada56a9a354b521f542c69210048b4d36aaeae7b000f2b.jpg)

![efa1f71da07e26b3cd90a8d72d927f706bc7799f50b5dec50a97d5ae74c143cd.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/efa1f71da07e26b3cd90a8d72d927f706bc7799f50b5dec50a97d5ae74c143cd.jpg)

![f16c27a14992edb8dca6bda70bb7e5e9dd7862dd92f77565a26304917a25515e.jpg](../nips_results/1074_Multivariate%20Time%20Series%20Anomaly%20Detection%20with%20Idempotent%20Reconstruction/tables/f16c27a14992edb8dca6bda70bb7e5e9dd7862dd92f77565a26304917a25515e.jpg)

## Understanding Bias Terms in Neural Representations


### Images

![2c163e8e6f77337b5a2eb2e2a31fb5c85a51ef3dd1132020a21abd9fc41baafa.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/images/2c163e8e6f77337b5a2eb2e2a31fb5c85a51ef3dd1132020a21abd9fc41baafa.jpg)

![c27840221f991953d1a84586601ff99107646821b44a98eaac3720ad22c7fa7e.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/images/c27840221f991953d1a84586601ff99107646821b44a98eaac3720ad22c7fa7e.jpg)

![c6095ace67fc726f3265a2c5a51cde1f871342c5794108d272e30c7c62a59105.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/images/c6095ace67fc726f3265a2c5a51cde1f871342c5794108d272e30c7c62a59105.jpg)

![e82046348ea279dab21224dcd32eb5b48eabd85848feeaed781d5c8c9d3e918e.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/images/e82046348ea279dab21224dcd32eb5b48eabd85848feeaed781d5c8c9d3e918e.jpg)

![f708866401b42ffb974a156035cd8b95824d5ddba9bbe8680580a619081b55c0.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/images/f708866401b42ffb974a156035cd8b95824d5ddba9bbe8680580a619081b55c0.jpg)

### Tables

![22da4e8164a9a271cd7df92c20b700de449aca49a5daad0b8c2d24f05aab6008.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/tables/22da4e8164a9a271cd7df92c20b700de449aca49a5daad0b8c2d24f05aab6008.jpg)

![23f1dfd5782b7b6b647df304c2efd8a93aaaba3018911481ff44ac6f4755d677.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/tables/23f1dfd5782b7b6b647df304c2efd8a93aaaba3018911481ff44ac6f4755d677.jpg)

![2d2bbf808491058fcd2f14005259020789e6eb353cdeadca0b71f5682e9f7e04.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/tables/2d2bbf808491058fcd2f14005259020789e6eb353cdeadca0b71f5682e9f7e04.jpg)

![2df1218f016e18f462e38fd0d18a6cbc537c02207a43ca992e377ec2cc327b64.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/tables/2df1218f016e18f462e38fd0d18a6cbc537c02207a43ca992e377ec2cc327b64.jpg)

![62bcb5870b336ac9e00d3a0faa491e55564db2c3ba733cd3dcdcb7895ae154bf.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/tables/62bcb5870b336ac9e00d3a0faa491e55564db2c3ba733cd3dcdcb7895ae154bf.jpg)

![8baf1b77d832fe6ef11a64b19d2ddf77fec9ed521aefb755adacd908ca512ae5.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/tables/8baf1b77d832fe6ef11a64b19d2ddf77fec9ed521aefb755adacd908ca512ae5.jpg)

![97706313f5ef62673406cd0176aae7e0444b288c6ca90683d9c5a9abad5e96f8.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/tables/97706313f5ef62673406cd0176aae7e0444b288c6ca90683d9c5a9abad5e96f8.jpg)

![bcc8b4a4a9ab353c8b1e1226b843519220f8cfb7dc0c953bee3998fb9c7db672.jpg](../nips_results/1075_Understanding%20Bias%20Terms%20in%20Neural%20Representations/tables/bcc8b4a4a9ab353c8b1e1226b843519220f8cfb7dc0c953bee3998fb9c7db672.jpg)

## Adversarial Graph Fusion for Incomplete Multi-view Semi-supervised Learning with Tensorial Imputation


### Images

![01412f36453015fd6d9572a3960a2a56dd9f9986cc995e31f30b8e88a55e8436.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/01412f36453015fd6d9572a3960a2a56dd9f9986cc995e31f30b8e88a55e8436.jpg)

![0e3903aa7f54793331787afddf4ba2babe9e9ae46e0a8ac9864ffeb9f416a34e.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/0e3903aa7f54793331787afddf4ba2babe9e9ae46e0a8ac9864ffeb9f416a34e.jpg)

![150baad51374676e80cd54012ad6a69d9812a57faa644d8afb6f3fb3d730a241.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/150baad51374676e80cd54012ad6a69d9812a57faa644d8afb6f3fb3d730a241.jpg)

![5307d63ac2b67b8d163b8a91ce8370a38f0fe473ca0fc354249bde5f96139129.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/5307d63ac2b67b8d163b8a91ce8370a38f0fe473ca0fc354249bde5f96139129.jpg)

![55af613478283aa048ca7d7a678f4743ac089fccaf51c65818102ee7f7ab6d35.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/55af613478283aa048ca7d7a678f4743ac089fccaf51c65818102ee7f7ab6d35.jpg)

![6d5b21b64ccd62ce10e9020c443acc102c6b1c89027be65224ac12cd0cb2f533.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/6d5b21b64ccd62ce10e9020c443acc102c6b1c89027be65224ac12cd0cb2f533.jpg)

![85133031994aebd589225cf52dde3f3574ad13a7f034bb703d2faebd1afd54e8.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/85133031994aebd589225cf52dde3f3574ad13a7f034bb703d2faebd1afd54e8.jpg)

![88d776f13f52b4e9b89a4602a0c9322eed50038b127c8cae7322473082701c1b.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/88d776f13f52b4e9b89a4602a0c9322eed50038b127c8cae7322473082701c1b.jpg)

![8d8eb6963c1f37e95f6f652e0b6832b5486ec0dece6668dc72b5965b478b081f.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/8d8eb6963c1f37e95f6f652e0b6832b5486ec0dece6668dc72b5965b478b081f.jpg)

![96ec58db20cfe91912d06f93161948eb1a85684600bf0e147700298025b6d4ff.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/96ec58db20cfe91912d06f93161948eb1a85684600bf0e147700298025b6d4ff.jpg)

![abb21a75ca1e8d714c792f061977bb7dcae271499fc2b2d24122dd239c045ab9.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/abb21a75ca1e8d714c792f061977bb7dcae271499fc2b2d24122dd239c045ab9.jpg)

![c2444348ed595aff5cad6dfc1f0139fe0a068799f4b7d411fbdaca5ce60c0bab.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/c2444348ed595aff5cad6dfc1f0139fe0a068799f4b7d411fbdaca5ce60c0bab.jpg)

![ceea00f593e76f668262cf788791e7741421c4fdbc31cc1d5a7f027c64861ed3.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/ceea00f593e76f668262cf788791e7741421c4fdbc31cc1d5a7f027c64861ed3.jpg)

![cf86d6a4a70e032ff6cc2a264f8895f35049535711d3c0827d82f5f5ad5ddb39.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/cf86d6a4a70e032ff6cc2a264f8895f35049535711d3c0827d82f5f5ad5ddb39.jpg)

![de72fb8bf7d20a19e667d592fcccf47fd3a07652804873f3cea315236c12b9a1.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/images/de72fb8bf7d20a19e667d592fcccf47fd3a07652804873f3cea315236c12b9a1.jpg)

### Tables

![2c1b92546e009acf32d3ac93a2d71317d93f5888f41907de5b4150da3f016e95.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/2c1b92546e009acf32d3ac93a2d71317d93f5888f41907de5b4150da3f016e95.jpg)

![6183c96fe23faa6273c80c7ecb341f78eb3188deb25fe3232dfff50559c94c79.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/6183c96fe23faa6273c80c7ecb341f78eb3188deb25fe3232dfff50559c94c79.jpg)

![62a41fd8f19bc269f6e6417e279391b980b3b11fd8683be46cbd232255065be9.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/62a41fd8f19bc269f6e6417e279391b980b3b11fd8683be46cbd232255065be9.jpg)

![679ffacabaa6cbc308c9cb59391cd548188c7915cd56c99fb4473a65117a518c.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/679ffacabaa6cbc308c9cb59391cd548188c7915cd56c99fb4473a65117a518c.jpg)

![69d58d09814f63bd707b1de9512bc7602c9b5c412953dee03661c64e46b161a0.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/69d58d09814f63bd707b1de9512bc7602c9b5c412953dee03661c64e46b161a0.jpg)

![7e461e1ea72c057d14b1ea739fd215b9f1ca7aa4f6f89263a7f1d30b0986bfb7.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/7e461e1ea72c057d14b1ea739fd215b9f1ca7aa4f6f89263a7f1d30b0986bfb7.jpg)

![86e4de66ed9982ce1b72bc419d7d0ff191c1a8d1ef73b6bf0d97b60a284e6ad7.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/86e4de66ed9982ce1b72bc419d7d0ff191c1a8d1ef73b6bf0d97b60a284e6ad7.jpg)

![9633c361c40a0e7ff1ac07914a16ce30d9828756d3d50c9356cb2571542e2343.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/9633c361c40a0e7ff1ac07914a16ce30d9828756d3d50c9356cb2571542e2343.jpg)

![a49ec53a3239c71947e77307fff317f606f46d4a7a315d57dcbedc1c86cda8a1.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/a49ec53a3239c71947e77307fff317f606f46d4a7a315d57dcbedc1c86cda8a1.jpg)

![a7bc4a4cad29087d77b65cc84384d39557838bb8c5103f1ec5901848fae63cce.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/a7bc4a4cad29087d77b65cc84384d39557838bb8c5103f1ec5901848fae63cce.jpg)

![b0282d3897110ad04104b30ca284d9dde64c3df0cc981e22bbc96b43f9e8cfec.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/b0282d3897110ad04104b30ca284d9dde64c3df0cc981e22bbc96b43f9e8cfec.jpg)

![b24832968e7e773e6ebf6e9583c334ebb6c28728ff257e1aeae4446317debaf8.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/b24832968e7e773e6ebf6e9583c334ebb6c28728ff257e1aeae4446317debaf8.jpg)

![cd730e221de1124f34cfe73643fb830c0899455ceea55d3ed71a5fd857109237.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/cd730e221de1124f34cfe73643fb830c0899455ceea55d3ed71a5fd857109237.jpg)

![e98234ae96d3e3ea70b3f02f4116b33de812c61b7d676727024a1b3a4d0381ae.jpg](../nips_results/1076_Adversarial%20Graph%20Fusion%20for%20Incomplete%20Multi-view%20Semi-supervised%20Learning%20with%20Tensorial%20Imputatio/tables/e98234ae96d3e3ea70b3f02f4116b33de812c61b7d676727024a1b3a4d0381ae.jpg)

## Document Summarization with Conformal Importance Guarantees


### Images

![092edd6b402a1da0a3871614f2afeabe8403be97d8ce8a5b1126062a67532565.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/092edd6b402a1da0a3871614f2afeabe8403be97d8ce8a5b1126062a67532565.jpg)

![0975607d19991a982a738ee87de2af59d8b40cf598b24b4e2cf5f18d83488a14.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/0975607d19991a982a738ee87de2af59d8b40cf598b24b4e2cf5f18d83488a14.jpg)

![0adabf5f1bed8fb019b7c5aadcf7c89cb71c64d318132f1f374fa55cecc1c2f8.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/0adabf5f1bed8fb019b7c5aadcf7c89cb71c64d318132f1f374fa55cecc1c2f8.jpg)

![18f645a03601aa1343683ea30878e82df6a600428fef73fd23e1cfabf87efb2e.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/18f645a03601aa1343683ea30878e82df6a600428fef73fd23e1cfabf87efb2e.jpg)

![2844104496011a16ffed27270b9927842e54c1f639309450a28f11d8bbede413.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/2844104496011a16ffed27270b9927842e54c1f639309450a28f11d8bbede413.jpg)

![48bf7b00233d1b5ed0a9d82deb67707230afaec1b0623fbb488021a9fa8abf73.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/48bf7b00233d1b5ed0a9d82deb67707230afaec1b0623fbb488021a9fa8abf73.jpg)

![4cb214117efc17fed48b6985be90112e6969ae413a0e31f240aecad3e61b3a45.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/4cb214117efc17fed48b6985be90112e6969ae413a0e31f240aecad3e61b3a45.jpg)

![5cf6e04fb01b06b493a5a28a420698dac5f755fe5b5bf36a9ed59963ab185e0c.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/5cf6e04fb01b06b493a5a28a420698dac5f755fe5b5bf36a9ed59963ab185e0c.jpg)

![75e85d4e2e15d2578fa27bd91f75797d2c76d9fe7b054b6064cb474283244929.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/75e85d4e2e15d2578fa27bd91f75797d2c76d9fe7b054b6064cb474283244929.jpg)

![981c5a85989c665d205d72ccc930a19006a26853678ffdcf652db46237d914c5.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/981c5a85989c665d205d72ccc930a19006a26853678ffdcf652db46237d914c5.jpg)

![a4238901724afd82cef0576a73997569f4e53c80a984c8ffe028769624339ef5.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/a4238901724afd82cef0576a73997569f4e53c80a984c8ffe028769624339ef5.jpg)

![ab95646eef48c386c27f39125625db067c88279f214528e8ea96f8439bf99419.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/ab95646eef48c386c27f39125625db067c88279f214528e8ea96f8439bf99419.jpg)

![ad05715f7bc8e5d04cbd49956c5f10bd3058f4f4340b06ea82b809a65ea9db4a.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/ad05715f7bc8e5d04cbd49956c5f10bd3058f4f4340b06ea82b809a65ea9db4a.jpg)

![d5056d1303e5179a86abe240969e646cb9188ad4d3d7915626de25e424c8bc0c.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/d5056d1303e5179a86abe240969e646cb9188ad4d3d7915626de25e424c8bc0c.jpg)

![d615eb7c79af0ab2e8cb595507cdf8251fa36bd8d9f8ccb01ca064d8204a3984.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/d615eb7c79af0ab2e8cb595507cdf8251fa36bd8d9f8ccb01ca064d8204a3984.jpg)

![d7408ccb791b110d3cec79928d9ce75942425af41a590975fd7675dad05c76b3.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/d7408ccb791b110d3cec79928d9ce75942425af41a590975fd7675dad05c76b3.jpg)

![d7fb275baf9cd257ae0ec9c5cc3e590344d1aaecbcb17c544314d4e893d9d7c2.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/d7fb275baf9cd257ae0ec9c5cc3e590344d1aaecbcb17c544314d4e893d9d7c2.jpg)

![e219661a5353e9509bf5ebadc5ed17d7e99faafc0fb2b69f8c9786f336fef8f9.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/e219661a5353e9509bf5ebadc5ed17d7e99faafc0fb2b69f8c9786f336fef8f9.jpg)

![e6b40b28a1874fac97a41ac1f2195e423fc7dba6acdeb41bc06bdc51a2d68216.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/e6b40b28a1874fac97a41ac1f2195e423fc7dba6acdeb41bc06bdc51a2d68216.jpg)

![f3c0d878e2cc2d203bc91444ae7d25c0b92c8e2b1c81ecdb1392b25ca46cd8fb.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/f3c0d878e2cc2d203bc91444ae7d25c0b92c8e2b1c81ecdb1392b25ca46cd8fb.jpg)

![fc52d2da5c20e37e12335aa14ffe8ca8bbc058d33a159af988cbb121e3411e92.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/fc52d2da5c20e37e12335aa14ffe8ca8bbc058d33a159af988cbb121e3411e92.jpg)

![fe2f42e8d52d114944e0e513cdeeadabdd86fdf78bf24b9cdb35bce7646fbfa0.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/images/fe2f42e8d52d114944e0e513cdeeadabdd86fdf78bf24b9cdb35bce7646fbfa0.jpg)

### Tables

![2bb4129a3b4a2e009342fba2e06ef586e03f801be59a0c189db7ed710433508f.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/2bb4129a3b4a2e009342fba2e06ef586e03f801be59a0c189db7ed710433508f.jpg)

![3790ac1079b30182f97c28ed7475e61c6647e86ef0b543d8630d5fa0ce60cde6.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/3790ac1079b30182f97c28ed7475e61c6647e86ef0b543d8630d5fa0ce60cde6.jpg)

![3fe85d5b5a8f8a43de14919a528b6339079d168e572d56e7f701c67511ffca8f.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/3fe85d5b5a8f8a43de14919a528b6339079d168e572d56e7f701c67511ffca8f.jpg)

![4d733f9285862aed37a5f7a7c620588cc628f147f0fe432aede76787b197a5d5.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/4d733f9285862aed37a5f7a7c620588cc628f147f0fe432aede76787b197a5d5.jpg)

![5bf57c25fd6527e1dcdd064d613376e60d07e368dba47b0df999147065c8a968.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/5bf57c25fd6527e1dcdd064d613376e60d07e368dba47b0df999147065c8a968.jpg)

![62410d5a194d8e69e7736866bb9b0ecf77d9f39a95a89fbdb175183277ab06f4.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/62410d5a194d8e69e7736866bb9b0ecf77d9f39a95a89fbdb175183277ab06f4.jpg)

![8f345562ab87d2f96ca62e15c4311a767500167d0af84a6b20449dd9f8cc3aa6.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/8f345562ab87d2f96ca62e15c4311a767500167d0af84a6b20449dd9f8cc3aa6.jpg)

![a05e2e24a58fb27167d86934cab978d97797c86981c4f3e656a7fa8d17cb55c0.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/a05e2e24a58fb27167d86934cab978d97797c86981c4f3e656a7fa8d17cb55c0.jpg)

![bba000f44a0a789bfdb2cd9116f37b4562dbbdfda8d1156c5347d41f85721503.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/bba000f44a0a789bfdb2cd9116f37b4562dbbdfda8d1156c5347d41f85721503.jpg)

![c8c954b1842beab04b979a84d69ae07dba3818e52f51980d8345ffb958370463.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/c8c954b1842beab04b979a84d69ae07dba3818e52f51980d8345ffb958370463.jpg)

![d7305bc491bb2489e25f270358970d4f6e4e9b7d1bb811a0645e6f333652ba8c.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/d7305bc491bb2489e25f270358970d4f6e4e9b7d1bb811a0645e6f333652ba8c.jpg)

![dd89cbbe55ec9db981a09b29e9af94f7c4de600b9161e935181e96d2f4a6ead3.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/dd89cbbe55ec9db981a09b29e9af94f7c4de600b9161e935181e96d2f4a6ead3.jpg)

![fa595d9575977afea57e501dd8c0188d06c7dffebd429c7b1b053ad30fd6dde1.jpg](../nips_results/1077_Document%20Summarization%20with%20Conformal%20Importance%20Guarantees/tables/fa595d9575977afea57e501dd8c0188d06c7dffebd429c7b1b053ad30fd6dde1.jpg)

## Reasoning Models Sometimes Output Illegible Chains of Thought


### Images

![02627cf4d439d42480a35325f0053c8f266903c287da92e529cd729efabeeda2.jpg](../nips_results/1078_Reasoning%20Models%20Sometimes%20Output%20Illegible%20Chains%20of%20Thought/images/02627cf4d439d42480a35325f0053c8f266903c287da92e529cd729efabeeda2.jpg)

![2850fc06cf8e0686ef3791f3a59fed78d98274f2a6529abe7006954058da92cb.jpg](../nips_results/1078_Reasoning%20Models%20Sometimes%20Output%20Illegible%20Chains%20of%20Thought/images/2850fc06cf8e0686ef3791f3a59fed78d98274f2a6529abe7006954058da92cb.jpg)

![6d9a33c8a963b3a6721713049a300f958025c1f73dbb3a61ad8f9caf21f596d6.jpg](../nips_results/1078_Reasoning%20Models%20Sometimes%20Output%20Illegible%20Chains%20of%20Thought/images/6d9a33c8a963b3a6721713049a300f958025c1f73dbb3a61ad8f9caf21f596d6.jpg)

![80882fc811df9da393d43e48f2cdfd187ec2f6b93c028696ce37eeaa76997f51.jpg](../nips_results/1078_Reasoning%20Models%20Sometimes%20Output%20Illegible%20Chains%20of%20Thought/images/80882fc811df9da393d43e48f2cdfd187ec2f6b93c028696ce37eeaa76997f51.jpg)

![aa7e319aa8ecd19abdd67a59bc70d6d9454bd00df51130e2393f6a173c282bc1.jpg](../nips_results/1078_Reasoning%20Models%20Sometimes%20Output%20Illegible%20Chains%20of%20Thought/images/aa7e319aa8ecd19abdd67a59bc70d6d9454bd00df51130e2393f6a173c282bc1.jpg)

![bb3e82a6e3d1f6d672bcc1706e2dd1973984cbded75275e4f83fb04249832233.jpg](../nips_results/1078_Reasoning%20Models%20Sometimes%20Output%20Illegible%20Chains%20of%20Thought/images/bb3e82a6e3d1f6d672bcc1706e2dd1973984cbded75275e4f83fb04249832233.jpg)

![db9f08e32245ac5a0cf6c2bc77592641025f0c5c8a1cc54378cd16b97e0bfc8d.jpg](../nips_results/1078_Reasoning%20Models%20Sometimes%20Output%20Illegible%20Chains%20of%20Thought/images/db9f08e32245ac5a0cf6c2bc77592641025f0c5c8a1cc54378cd16b97e0bfc8d.jpg)

![fbb8180d3b7ca7ee1de6af82f5d37c081d1ad6f67e8bfac628172695c5cc10d7.jpg](../nips_results/1078_Reasoning%20Models%20Sometimes%20Output%20Illegible%20Chains%20of%20Thought/images/fbb8180d3b7ca7ee1de6af82f5d37c081d1ad6f67e8bfac628172695c5cc10d7.jpg)

### Tables

![a2ed9ef2466b288c422259b871f2c30cfc0c7d3639b81d0fdcb89680ffacdf27.jpg](../nips_results/1078_Reasoning%20Models%20Sometimes%20Output%20Illegible%20Chains%20of%20Thought/tables/a2ed9ef2466b288c422259b871f2c30cfc0c7d3639b81d0fdcb89680ffacdf27.jpg)

![dca4388ad46c7b138367ce8d9c9a1fae44eb843f84b223e612a390c5a6074342.jpg](../nips_results/1078_Reasoning%20Models%20Sometimes%20Output%20Illegible%20Chains%20of%20Thought/tables/dca4388ad46c7b138367ce8d9c9a1fae44eb843f84b223e612a390c5a6074342.jpg)

## Prot2Text-V2: Protein Function Prediction with Multimodal Contrastive Alignment


### Images

![1c221cb793bab7c3ee7aba1ccde8de499d09740bfe263b23dd9b44dd6d420dac.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/images/1c221cb793bab7c3ee7aba1ccde8de499d09740bfe263b23dd9b44dd6d420dac.jpg)

![1dda7d37eb5c29fd01c26cb9834dfffec0281a93e99d8187776e6769b5eddf4b.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/images/1dda7d37eb5c29fd01c26cb9834dfffec0281a93e99d8187776e6769b5eddf4b.jpg)

![28e97f6f2fc3f2826d5d29e354999ffb0ea89f8377cba793e61b100652fd7232.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/images/28e97f6f2fc3f2826d5d29e354999ffb0ea89f8377cba793e61b100652fd7232.jpg)

![2ae971542f37e65f4afeb5d804329647ef1311c74177487406177995895c80db.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/images/2ae971542f37e65f4afeb5d804329647ef1311c74177487406177995895c80db.jpg)

![4e2836a981c6c8a9e236adad07b9053dcf4957d271605fb5ce4cdd9ba0f3e26c.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/images/4e2836a981c6c8a9e236adad07b9053dcf4957d271605fb5ce4cdd9ba0f3e26c.jpg)

![6b931869cd82b25011f2f33d67fcaf0a441b1789a22de88c655716a11293bdff.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/images/6b931869cd82b25011f2f33d67fcaf0a441b1789a22de88c655716a11293bdff.jpg)

![7cd2e77d1eccdc470ebe16eca6a302c41c6bca463cb77c406c0fa2b537b2e6b2.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/images/7cd2e77d1eccdc470ebe16eca6a302c41c6bca463cb77c406c0fa2b537b2e6b2.jpg)

![95be631028286af222a66f6ce6f3cfc056521c787c1566cc176b81b9cf8efa97.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/images/95be631028286af222a66f6ce6f3cfc056521c787c1566cc176b81b9cf8efa97.jpg)

![bcdd22951cbd7e450c417a29c0a677f6b990ba606fbeaf8c0bb6a61591ade93f.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/images/bcdd22951cbd7e450c417a29c0a677f6b990ba606fbeaf8c0bb6a61591ade93f.jpg)

![bd92b4727b7071d0447f71ceece64e7480fb428c37ef162918d8be97cecd352f.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/images/bd92b4727b7071d0447f71ceece64e7480fb428c37ef162918d8be97cecd352f.jpg)

### Tables

![161597858fb98fe210c7916fd13a9a6f77790b5ddaf7485c2be119a7a7bffdc5.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/tables/161597858fb98fe210c7916fd13a9a6f77790b5ddaf7485c2be119a7a7bffdc5.jpg)

![1e25c8888a4836f6538de73a0a2cac604adac1822a17730cc48c0de4f64160eb.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/tables/1e25c8888a4836f6538de73a0a2cac604adac1822a17730cc48c0de4f64160eb.jpg)

![3b988e82033121f10ea07325a9fa5d7f9d27b0d62c6c11580a99238e4312f8d0.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/tables/3b988e82033121f10ea07325a9fa5d7f9d27b0d62c6c11580a99238e4312f8d0.jpg)

![68ecb76566db3542a9322e2e233a460e599493028aa7dd79815ab264b64fad60.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/tables/68ecb76566db3542a9322e2e233a460e599493028aa7dd79815ab264b64fad60.jpg)

![784803e3538d788f5d70da5e83ea11dbacd13a23639dd27908832df7c06d82a3.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/tables/784803e3538d788f5d70da5e83ea11dbacd13a23639dd27908832df7c06d82a3.jpg)

![cc8018e3408acc9ed477a2e5c5d5313ceaba49bdf7b0c26c1294100b5842296a.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/tables/cc8018e3408acc9ed477a2e5c5d5313ceaba49bdf7b0c26c1294100b5842296a.jpg)

![d59a9fba86f70ce2ca72034fdfb71ccbebfc0b7c68aaa414234d7663fb32197d.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/tables/d59a9fba86f70ce2ca72034fdfb71ccbebfc0b7c68aaa414234d7663fb32197d.jpg)

![d709242c6ecf1e6459b494e1a3d22d1ea0040bd86dd85062559cc4b8a67cc685.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/tables/d709242c6ecf1e6459b494e1a3d22d1ea0040bd86dd85062559cc4b8a67cc685.jpg)

![fa981861018dc7565ea414c6c07a66109ea85f5f143ac3f7fcc2847ba3f318b2.jpg](../nips_results/1079_Prot2Text-V2_%20Protein%20Function%20Prediction%20with%20Multimodal%20Contrastive%20Alignment/tables/fa981861018dc7565ea414c6c07a66109ea85f5f143ac3f7fcc2847ba3f318b2.jpg)

## Normalize Filters! Classical Wisdom for Deep Vision


### Images

![29f2100136da6a7cd10f4603ba928b290669a1a7b0fea9f07f8c872004cb669c.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/29f2100136da6a7cd10f4603ba928b290669a1a7b0fea9f07f8c872004cb669c.jpg)

![3230e917995db357cfc9e90fce59810a2d39faec33784deff3f97a0db89edd47.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/3230e917995db357cfc9e90fce59810a2d39faec33784deff3f97a0db89edd47.jpg)

![46af75470bd3fe42756ce3c0934050e673588352cc318fb7f7fde3a8405c7f19.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/46af75470bd3fe42756ce3c0934050e673588352cc318fb7f7fde3a8405c7f19.jpg)

![500575d009f85c7b442a09e32e39bfd4a5aa1278f7da4e872e6765d8cb6f0a5e.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/500575d009f85c7b442a09e32e39bfd4a5aa1278f7da4e872e6765d8cb6f0a5e.jpg)

![5a1c0e5effbf44aa5912167d90a57e26b6dc8b765c2c65c8563501c80ffc1e75.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/5a1c0e5effbf44aa5912167d90a57e26b6dc8b765c2c65c8563501c80ffc1e75.jpg)

![60e1a320140bc600d72fad04f1a9c141ac6178968a411100b0d070b23c648c4b.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/60e1a320140bc600d72fad04f1a9c141ac6178968a411100b0d070b23c648c4b.jpg)

![7543431be35fea2a010d818a0e2b6340018c4cdd6c6b1c2d307b5d4e8670ddc6.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/7543431be35fea2a010d818a0e2b6340018c4cdd6c6b1c2d307b5d4e8670ddc6.jpg)

![847d692ce9166a67dc71110c846725816cc81077038dca14a41d4f157bb6b527.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/847d692ce9166a67dc71110c846725816cc81077038dca14a41d4f157bb6b527.jpg)

![8f8f89024c65a5b9775b339b24a17caaffcf22c8d0c19e03fc9714d0fe249d7b.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/8f8f89024c65a5b9775b339b24a17caaffcf22c8d0c19e03fc9714d0fe249d7b.jpg)

![9b7f7bb9bf2b01ed361d75d98ec1c3ec5a0006d179f5fd7ed5592fc7374008de.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/9b7f7bb9bf2b01ed361d75d98ec1c3ec5a0006d179f5fd7ed5592fc7374008de.jpg)

![a0aea6c901a1065d56900bc57365035cbd0073d7bb0443cc6966928d09ae1b47.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/a0aea6c901a1065d56900bc57365035cbd0073d7bb0443cc6966928d09ae1b47.jpg)

![a8f9a65f7915d34e52e55163750ffc2e6b9143d4f07ced021f596d51b9e93d0b.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/a8f9a65f7915d34e52e55163750ffc2e6b9143d4f07ced021f596d51b9e93d0b.jpg)

![b1ace95abcaa8156bf642b9b5e3d35b5661df3fe5f34106bdd8ede659c6e23eb.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/b1ace95abcaa8156bf642b9b5e3d35b5661df3fe5f34106bdd8ede659c6e23eb.jpg)

![bcf22a6a6d0c21f678c19a8dc37f3f44362a271a88b4eb83fc6708734f640c79.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/bcf22a6a6d0c21f678c19a8dc37f3f44362a271a88b4eb83fc6708734f640c79.jpg)

![c86cbe5ce7be941a7ed2c9ceb0dda262812eaff7f999f2250a5a4174e530e87c.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/c86cbe5ce7be941a7ed2c9ceb0dda262812eaff7f999f2250a5a4174e530e87c.jpg)

![d9354d1c2a18f2a95ecfa5e5401f0bea7656a381c54675990c79cfa35a08de85.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/d9354d1c2a18f2a95ecfa5e5401f0bea7656a381c54675990c79cfa35a08de85.jpg)

![dc75339a9bcc6b12e28990966b71594f6711ebfc85fe2e43470dd1da0971a529.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/images/dc75339a9bcc6b12e28990966b71594f6711ebfc85fe2e43470dd1da0971a529.jpg)

### Tables

![4ddb92d5aa7796ba13c106ab9c540f7b5c995ac349806516c1afebb141211430.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/4ddb92d5aa7796ba13c106ab9c540f7b5c995ac349806516c1afebb141211430.jpg)

![58fa5b5f5c05e693c8fd5b1927be50163eeb5b5be74ca726b08e40d6c6fc211d.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/58fa5b5f5c05e693c8fd5b1927be50163eeb5b5be74ca726b08e40d6c6fc211d.jpg)

![603c24c34013a7eb5e8e509652db8bb90766c50cef995412eeeeb742571c9220.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/603c24c34013a7eb5e8e509652db8bb90766c50cef995412eeeeb742571c9220.jpg)

![67438596c97b7b93436a02854df1eee6078f6eb1081e53cec558b72a883a147a.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/67438596c97b7b93436a02854df1eee6078f6eb1081e53cec558b72a883a147a.jpg)

![7c9f30ac45efc75f98dfaba322bd72febc5fff95345c3bcce98ae2eea63ef385.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/7c9f30ac45efc75f98dfaba322bd72febc5fff95345c3bcce98ae2eea63ef385.jpg)

![8b6f2c05ad9783c3a5405b4e1e3f4ced1913a8cb230f9668446be07d9a26e1cf.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/8b6f2c05ad9783c3a5405b4e1e3f4ced1913a8cb230f9668446be07d9a26e1cf.jpg)

![8f5003c525fe02181202723c435b6f4a413073939cbc73ba232913d9d6fe95c8.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/8f5003c525fe02181202723c435b6f4a413073939cbc73ba232913d9d6fe95c8.jpg)

![8fe74c957f39c1979d8c36ac6c9d87d1a3f1f40811be5613b4f3df8085b7e73f.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/8fe74c957f39c1979d8c36ac6c9d87d1a3f1f40811be5613b4f3df8085b7e73f.jpg)

![a270a638c3275f3122c66e3edc0ebc817de6b3b74624cd1c1f73faaf6abef497.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/a270a638c3275f3122c66e3edc0ebc817de6b3b74624cd1c1f73faaf6abef497.jpg)

![a8794598a2427bedb0a5aba2dd3e167a33bcafaa46d8648faa0c8fe40b7bef71.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/a8794598a2427bedb0a5aba2dd3e167a33bcafaa46d8648faa0c8fe40b7bef71.jpg)

![cbb4ad665dd74831d968a5a112de1b8388e81eaaf7bcb58796bf41ab17e5c284.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/cbb4ad665dd74831d968a5a112de1b8388e81eaaf7bcb58796bf41ab17e5c284.jpg)

![cda4832f7141370361fea254524a8edd49d14a71031366cfdd528c3eeeca8135.jpg](../nips_results/1080_Normalize%20Filters%21%20Classical%20Wisdom%20for%20Deep%20Vision/tables/cda4832f7141370361fea254524a8edd49d14a71031366cfdd528c3eeeca8135.jpg)

## STRIDER: Navigation via Instruction-Aligned Structural Decision Space Optimization


### Images

![04ba17a8a9c23907bd47e2c7bc2c05b4c67a5b217b80fcc9151c6a50fd49ce87.jpg](../nips_results/1081_STRIDER_%20Navigation%20via%20Instruction-Aligned%20Structural%20Decision%20Space%20Optimization/images/04ba17a8a9c23907bd47e2c7bc2c05b4c67a5b217b80fcc9151c6a50fd49ce87.jpg)

![9871117286c9ba7c4fdc6757e15822887ecf0152c72bf4fc06391b4601c75b39.jpg](../nips_results/1081_STRIDER_%20Navigation%20via%20Instruction-Aligned%20Structural%20Decision%20Space%20Optimization/images/9871117286c9ba7c4fdc6757e15822887ecf0152c72bf4fc06391b4601c75b39.jpg)

![a0a4715b5137165d592727c35514c5e5d9febddc45d88bb9f1a26e6b4850a121.jpg](../nips_results/1081_STRIDER_%20Navigation%20via%20Instruction-Aligned%20Structural%20Decision%20Space%20Optimization/images/a0a4715b5137165d592727c35514c5e5d9febddc45d88bb9f1a26e6b4850a121.jpg)

![c566ca225b6791fdfb6317a7b314470b11ec37dfa36fcba435fb934945e6a67d.jpg](../nips_results/1081_STRIDER_%20Navigation%20via%20Instruction-Aligned%20Structural%20Decision%20Space%20Optimization/images/c566ca225b6791fdfb6317a7b314470b11ec37dfa36fcba435fb934945e6a67d.jpg)

![e9c53cde3e6c0e40913be379f3dc53c6d53da4f035d0a647d0f238c93909454c.jpg](../nips_results/1081_STRIDER_%20Navigation%20via%20Instruction-Aligned%20Structural%20Decision%20Space%20Optimization/images/e9c53cde3e6c0e40913be379f3dc53c6d53da4f035d0a647d0f238c93909454c.jpg)

### Tables

![33456f5b487cd020c6f936543119936cf154a10e30f2f8e84ab8d4e6d23c31fa.jpg](../nips_results/1081_STRIDER_%20Navigation%20via%20Instruction-Aligned%20Structural%20Decision%20Space%20Optimization/tables/33456f5b487cd020c6f936543119936cf154a10e30f2f8e84ab8d4e6d23c31fa.jpg)

![906a525acfa478f46004d7f09ce1dfae9dab28823bfe3999669b57d435bb2a6d.jpg](../nips_results/1081_STRIDER_%20Navigation%20via%20Instruction-Aligned%20Structural%20Decision%20Space%20Optimization/tables/906a525acfa478f46004d7f09ce1dfae9dab28823bfe3999669b57d435bb2a6d.jpg)

![9e492969247588f80624cd2ceffda3884e1633d945012dade6d9f02df1b69cd8.jpg](../nips_results/1081_STRIDER_%20Navigation%20via%20Instruction-Aligned%20Structural%20Decision%20Space%20Optimization/tables/9e492969247588f80624cd2ceffda3884e1633d945012dade6d9f02df1b69cd8.jpg)

![e9fd90b0325494bf48b9b41453d3261acc22ffeb786d189671f2f55497cff176.jpg](../nips_results/1081_STRIDER_%20Navigation%20via%20Instruction-Aligned%20Structural%20Decision%20Space%20Optimization/tables/e9fd90b0325494bf48b9b41453d3261acc22ffeb786d189671f2f55497cff176.jpg)

![ef7d171a9fbeca6a34903ddc304126ce383e4c273402819f684fc000e07080e7.jpg](../nips_results/1081_STRIDER_%20Navigation%20via%20Instruction-Aligned%20Structural%20Decision%20Space%20Optimization/tables/ef7d171a9fbeca6a34903ddc304126ce383e4c273402819f684fc000e07080e7.jpg)

## Connectome-Based Modelling Reveals Orientation Maps in the Drosophila Optic Lobe


### Images

![183ca7045e2c132220c91f52c77d81761f001f05599ff3087ebf54e87a5d2615.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/images/183ca7045e2c132220c91f52c77d81761f001f05599ff3087ebf54e87a5d2615.jpg)

![34258a52f91fc3dc7d3c215fa77f79c17f12714bdb4c5348c7047bda54163059.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/images/34258a52f91fc3dc7d3c215fa77f79c17f12714bdb4c5348c7047bda54163059.jpg)

![3d4ffe82b14f38a2ed0aee915048f13a398626132a089c3b5de4778bfd81c294.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/images/3d4ffe82b14f38a2ed0aee915048f13a398626132a089c3b5de4778bfd81c294.jpg)

![40ff298f5dac2bae121e339e4710911fb25eb04d5c7fd14d2de7712e0ffabaf9.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/images/40ff298f5dac2bae121e339e4710911fb25eb04d5c7fd14d2de7712e0ffabaf9.jpg)

![7230438e7d0371a431f29e8e469adc60f83332886b95e91892ab2243a5b21ed1.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/images/7230438e7d0371a431f29e8e469adc60f83332886b95e91892ab2243a5b21ed1.jpg)

![77b4b6da790caab52dd3e3eb2fcf1c8577b4cac8bedac6324c80724ca832994f.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/images/77b4b6da790caab52dd3e3eb2fcf1c8577b4cac8bedac6324c80724ca832994f.jpg)

![8476a8c72fd8a6f69527704f6ee01ecb76072485db18c583ba29efd11b375735.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/images/8476a8c72fd8a6f69527704f6ee01ecb76072485db18c583ba29efd11b375735.jpg)

![8f382741d21a5e239021b18d50844fbb3d01ff94b4b54e7c6f18355fecd0ebaa.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/images/8f382741d21a5e239021b18d50844fbb3d01ff94b4b54e7c6f18355fecd0ebaa.jpg)

![92116061280e215f90140c967a8e8447933cba9e77cc6589e6427c8aff842ddc.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/images/92116061280e215f90140c967a8e8447933cba9e77cc6589e6427c8aff842ddc.jpg)

![a4917c4944f084cd7f70ae2ce49bd1063d0ff56ca2e339fb95760d74ca110585.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/images/a4917c4944f084cd7f70ae2ce49bd1063d0ff56ca2e339fb95760d74ca110585.jpg)

![be73e878adac85cd8a57e056dcdcebf683c0bfe78847d3b7a6c6908cf8f53ca8.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/images/be73e878adac85cd8a57e056dcdcebf683c0bfe78847d3b7a6c6908cf8f53ca8.jpg)

### Tables

![fb3fc25f7804ac418d71cd0ec2e46abe790791650e3d34f5bf7ac587ebc2cd6b.jpg](../nips_results/1082_Connectome-Based%20Modelling%20Reveals%20Orientation%20Maps%20in%20the%20Drosophila%20Optic%20Lobe/tables/fb3fc25f7804ac418d71cd0ec2e46abe790791650e3d34f5bf7ac587ebc2cd6b.jpg)

## Efficient Utility-Preserving Machine Unlearning with Implicit Gradient Surgery


### Images

![166e2faa7a43aefdbeeff2bbcb4d2886d72be981e5f420e99eb5eeff9037efa4.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/images/166e2faa7a43aefdbeeff2bbcb4d2886d72be981e5f420e99eb5eeff9037efa4.jpg)

![2c72aa5b7e5413432cd34039bf7e483debf2d562ccc2049b60001fcdaff8cf41.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/images/2c72aa5b7e5413432cd34039bf7e483debf2d562ccc2049b60001fcdaff8cf41.jpg)

![447348cec5ff52706e672cac11379500fc476d7ce46e74b63ebcb5abc8fa2bc4.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/images/447348cec5ff52706e672cac11379500fc476d7ce46e74b63ebcb5abc8fa2bc4.jpg)

![5a754ca8dd6dc59b70c45b8a01497ba47c0cd37de439bf8cdb62d3459d092dc5.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/images/5a754ca8dd6dc59b70c45b8a01497ba47c0cd37de439bf8cdb62d3459d092dc5.jpg)

![90074bdb22ce9caaff349169ec6424e7d313148af174f362ae2e6dbb1a024425.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/images/90074bdb22ce9caaff349169ec6424e7d313148af174f362ae2e6dbb1a024425.jpg)

![a5d66d1f70fec5ca71b4cea2f452dcc690419df83e46f7a81cb8994076eb8004.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/images/a5d66d1f70fec5ca71b4cea2f452dcc690419df83e46f7a81cb8994076eb8004.jpg)

![f508a081efa9b8fbe497e69f7201c1556d6b229f42ab532d3ed6508573c0a6d9.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/images/f508a081efa9b8fbe497e69f7201c1556d6b229f42ab532d3ed6508573c0a6d9.jpg)

### Tables

![03a9260b7d71e16f71fcd906c7e205d10a757aad09108d3e78dbff337daf5b46.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/03a9260b7d71e16f71fcd906c7e205d10a757aad09108d3e78dbff337daf5b46.jpg)

![05a15b0ecdc29aaafa4bcf06af4da712bf47cdda66ce3772ec3c9fb2bf563b04.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/05a15b0ecdc29aaafa4bcf06af4da712bf47cdda66ce3772ec3c9fb2bf563b04.jpg)

![0fed5397427ec0285884031fcffc932312698f78b7896d677e887a28b33fe16a.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/0fed5397427ec0285884031fcffc932312698f78b7896d677e887a28b33fe16a.jpg)

![1866e40e3345ef7ea17733efa30db048dd78d6e84e1b2c220abefca87f14afb2.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/1866e40e3345ef7ea17733efa30db048dd78d6e84e1b2c220abefca87f14afb2.jpg)

![1cf402c8fe459aef4428e6fcd80198863eb6ce5ab5c068124fb58db67250218a.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/1cf402c8fe459aef4428e6fcd80198863eb6ce5ab5c068124fb58db67250218a.jpg)

![21d96e9752a962fbbc76abd0b0000e0ce32d0bd97531b30032fe1c3948afe50f.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/21d96e9752a962fbbc76abd0b0000e0ce32d0bd97531b30032fe1c3948afe50f.jpg)

![473ec04900c1986f6803c54d333271ebc64319ff1d5b61b047d458a451808426.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/473ec04900c1986f6803c54d333271ebc64319ff1d5b61b047d458a451808426.jpg)

![651c24cbccfaad9bb00923566e40fa95b5deba4c429f51965b46ac85fea21e7a.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/651c24cbccfaad9bb00923566e40fa95b5deba4c429f51965b46ac85fea21e7a.jpg)

![7a9ef79ce0e9e0b23465d71dec35f88a41e5a0c3065d84e778cedfc52ec762f2.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/7a9ef79ce0e9e0b23465d71dec35f88a41e5a0c3065d84e778cedfc52ec762f2.jpg)

![81f73e8f3cfe176caa4cf5c8622f9821202ba5cda0438de4d5c8e037cd82181b.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/81f73e8f3cfe176caa4cf5c8622f9821202ba5cda0438de4d5c8e037cd82181b.jpg)

![827309842936d2df6d999e01bb9841efaf83862078ffaf261d080337163ae6e5.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/827309842936d2df6d999e01bb9841efaf83862078ffaf261d080337163ae6e5.jpg)

![a61e079579d65c7dce46e9c4c54d115b2e28f3f04bdce6c0cb9a752b490b9265.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/a61e079579d65c7dce46e9c4c54d115b2e28f3f04bdce6c0cb9a752b490b9265.jpg)

![c75e42d5c43f77019d06fe51026c86219797914d700363da0655404793cdebb4.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/c75e42d5c43f77019d06fe51026c86219797914d700363da0655404793cdebb4.jpg)

![d1c0141e0e837d5154453a089122d8acbb28cd87b238a1772f2e3cb502a64243.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/d1c0141e0e837d5154453a089122d8acbb28cd87b238a1772f2e3cb502a64243.jpg)

![f4b5324e47e7e53a9dcb9c18cc54a82e730bddeacca070ac048a9a0585a16bad.jpg](../nips_results/1083_Efficient%20Utility-Preserving%20Machine%20Unlearning%20with%20Implicit%20Gradient%20Surgery/tables/f4b5324e47e7e53a9dcb9c18cc54a82e730bddeacca070ac048a9a0585a16bad.jpg)

## HOComp: Interaction-Aware Human-Object Composition


### Images

![000ef40b64a401b5c3047b90fdeb1954608219f3a897492784e8af7a6897d01f.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/000ef40b64a401b5c3047b90fdeb1954608219f3a897492784e8af7a6897d01f.jpg)

![00ff41503ab2e5e62737cfeb11351cb011dda70ef1cd9075a6eeb5497329cb81.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/00ff41503ab2e5e62737cfeb11351cb011dda70ef1cd9075a6eeb5497329cb81.jpg)

![1c804cafd521ee781bdf3974202dccfbcc6f4bd4ac1c739ead53ae9cde131247.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/1c804cafd521ee781bdf3974202dccfbcc6f4bd4ac1c739ead53ae9cde131247.jpg)

![2f1423a220dacd3d61b4c76d56f9f8c2ac800a2defe1ab9116ed9cf5171e5e1f.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/2f1423a220dacd3d61b4c76d56f9f8c2ac800a2defe1ab9116ed9cf5171e5e1f.jpg)

![327f416b8bdfb79e773c6635e037bbe9ccd38f0eeaa4e9f2c07e1aa989cc1bc1.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/327f416b8bdfb79e773c6635e037bbe9ccd38f0eeaa4e9f2c07e1aa989cc1bc1.jpg)

![3809b2805db52fb07b67d24d5dacce3e66da631d7b9637d815c1c2815ebb87ee.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/3809b2805db52fb07b67d24d5dacce3e66da631d7b9637d815c1c2815ebb87ee.jpg)

![4664829439224a35e03d163a3deeeccd3861be0cca5da1d78d3fb59254c4cc6d.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/4664829439224a35e03d163a3deeeccd3861be0cca5da1d78d3fb59254c4cc6d.jpg)

![4f74e94d1ebea1aba7c28653013b6fc084e26bec36aef6bf8d29c4b44ac5abc2.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/4f74e94d1ebea1aba7c28653013b6fc084e26bec36aef6bf8d29c4b44ac5abc2.jpg)

![54557e4ca8301554edad75eb8d406a158249989b1752d813f4450b81c1f61436.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/54557e4ca8301554edad75eb8d406a158249989b1752d813f4450b81c1f61436.jpg)

![658c8fbf58e3b6f398b6eb4a4061c1ef7bc7bdc1307e4f75fafb82c91faf9b85.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/658c8fbf58e3b6f398b6eb4a4061c1ef7bc7bdc1307e4f75fafb82c91faf9b85.jpg)

![7357d6d3e860f16ac848ddb9086feda396b62a19990f75c591720ec2de130312.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/7357d6d3e860f16ac848ddb9086feda396b62a19990f75c591720ec2de130312.jpg)

![75460ccc5615f48e5013380dacdf246dc89ee8ec052de62fd38a960cbf01ed26.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/75460ccc5615f48e5013380dacdf246dc89ee8ec052de62fd38a960cbf01ed26.jpg)

![797d9dc809367f40f0517e86e4ef7852580684c7b7d8d3f7f962c12a778626a7.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/797d9dc809367f40f0517e86e4ef7852580684c7b7d8d3f7f962c12a778626a7.jpg)

![99769826865334b617664b44e10b32837d2be27a06537539e97dcd5755d05329.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/99769826865334b617664b44e10b32837d2be27a06537539e97dcd5755d05329.jpg)

![b7e80cd8947153bdab31eac910e0d24cbf78d9dc4f5f5941d7d5adf5064db9e0.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/b7e80cd8947153bdab31eac910e0d24cbf78d9dc4f5f5941d7d5adf5064db9e0.jpg)

![c99bb9bddfa58d03ff8613dbfabf6d2d7e4608db462a1556e77f23778c1c91b6.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/c99bb9bddfa58d03ff8613dbfabf6d2d7e4608db462a1556e77f23778c1c91b6.jpg)

![ce5efb63e13155b1beb38c9d01443ef056fa67745b4838cbb9d8c16572519443.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/ce5efb63e13155b1beb38c9d01443ef056fa67745b4838cbb9d8c16572519443.jpg)

![e2888c0509f4cc4fbe94d4af46d98cecc68c45c30936b15c95fc462a8a588c38.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/e2888c0509f4cc4fbe94d4af46d98cecc68c45c30936b15c95fc462a8a588c38.jpg)

![e2c97eba054f7cf5b44aad9b8cf3c765678d615a142d34ef735394e76fc67265.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/e2c97eba054f7cf5b44aad9b8cf3c765678d615a142d34ef735394e76fc67265.jpg)

![e3194940eb3de2cd138e3cb909ce5d8e8650d336e34680e30a944f72e4e5f2a7.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/e3194940eb3de2cd138e3cb909ce5d8e8650d336e34680e30a944f72e4e5f2a7.jpg)

![e4c68193488479c9f046fef9c3ba57f1202c85f39501195c1ee163849ada47ca.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/e4c68193488479c9f046fef9c3ba57f1202c85f39501195c1ee163849ada47ca.jpg)

![f5450a3cf5f3f133543bb41257d5cd241e4d5704df2de3db7e83332aca57a46c.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/images/f5450a3cf5f3f133543bb41257d5cd241e4d5704df2de3db7e83332aca57a46c.jpg)

### Tables

![0bfe3a183ba396a6e8c329c317fc6a98018d61039caa2c7463ca11101aa186c0.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/0bfe3a183ba396a6e8c329c317fc6a98018d61039caa2c7463ca11101aa186c0.jpg)

![0ce36ffd03add00fa11cae76e60470ab47f42e5a3f5595d598fba7eb0fc0764d.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/0ce36ffd03add00fa11cae76e60470ab47f42e5a3f5595d598fba7eb0fc0764d.jpg)

![16c544b0e2d5c7664e48a27c51943959f561e7dc047e494dac1c93f2d3ee6575.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/16c544b0e2d5c7664e48a27c51943959f561e7dc047e494dac1c93f2d3ee6575.jpg)

![1c06d5098525c10d2f9f0e49b7aaf7ca1cb3c917d7ac8db5dd065e9bcf7008fd.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/1c06d5098525c10d2f9f0e49b7aaf7ca1cb3c917d7ac8db5dd065e9bcf7008fd.jpg)

![24b584c8a5a275489081f3ba87fe85e272cc1516c0ef468ef43b161ebac51626.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/24b584c8a5a275489081f3ba87fe85e272cc1516c0ef468ef43b161ebac51626.jpg)

![26930f275d1bcb1d06a1946bdc6e3c2a75930a180ae153905358b8773dbc4646.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/26930f275d1bcb1d06a1946bdc6e3c2a75930a180ae153905358b8773dbc4646.jpg)

![35058158f1ec356ea5fe15395012194fb3c7473e8ce1ef626619b677c66bfe98.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/35058158f1ec356ea5fe15395012194fb3c7473e8ce1ef626619b677c66bfe98.jpg)

![49d6256a0c63c9fc5d2c055db7c6ca00522f496111644e6bc7d7008166376d97.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/49d6256a0c63c9fc5d2c055db7c6ca00522f496111644e6bc7d7008166376d97.jpg)

![506b9b3a23c7ddeb7d254d6ce10269354c698e53c469a078e8f3989370f427c3.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/506b9b3a23c7ddeb7d254d6ce10269354c698e53c469a078e8f3989370f427c3.jpg)

![56d366086620287c8bfe8c090bea1257e871e9c603c4d98db8095628fdf549e9.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/56d366086620287c8bfe8c090bea1257e871e9c603c4d98db8095628fdf549e9.jpg)

![6c58271a49202db3a1e280f04e313484786fd26e4b2c8514e367d5359fce21c2.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/6c58271a49202db3a1e280f04e313484786fd26e4b2c8514e367d5359fce21c2.jpg)

![78574c95529c3a853a1329a4b5320ac59a837096faefd5f5cea5a1f67594b588.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/78574c95529c3a853a1329a4b5320ac59a837096faefd5f5cea5a1f67594b588.jpg)

![79dde1a681c554916778501b582d271249f5cc801729aa5da03d8cecce2cc3c5.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/79dde1a681c554916778501b582d271249f5cc801729aa5da03d8cecce2cc3c5.jpg)

![95d2eeea4277dddea09e83b1be7f521e57953199cd889797eb92e74596a7d25b.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/95d2eeea4277dddea09e83b1be7f521e57953199cd889797eb92e74596a7d25b.jpg)

![a0993f457cee72b053a77325b14ef3d59575064d7b9afe1f1bea052da1a372dc.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/a0993f457cee72b053a77325b14ef3d59575064d7b9afe1f1bea052da1a372dc.jpg)

![b978d215015f747548f4c766d0dc4ff29dec11af4fb260aa57769349a385786e.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/b978d215015f747548f4c766d0dc4ff29dec11af4fb260aa57769349a385786e.jpg)

![c7b1418c422c5a122d003a0f2657c1c53788fb97e38242420e307e97a13276ad.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/c7b1418c422c5a122d003a0f2657c1c53788fb97e38242420e307e97a13276ad.jpg)

![d7d35fe449ceb9fb06938b00b99d64c63b281670c909f3571eb7c879e65871c3.jpg](../nips_results/1084_HOComp_%20Interaction-Aware%20Human-Object%20Composition/tables/d7d35fe449ceb9fb06938b00b99d64c63b281670c909f3571eb7c879e65871c3.jpg)

## Differentially Private High-dimensional Variable Selection via Integer Programming

### Images

![15b1bac1e35563a45093430b108005cd7bc36a4196cf483530dd6cf995b9c936.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/15b1bac1e35563a45093430b108005cd7bc36a4196cf483530dd6cf995b9c936.jpg)

![1736db11fee8adee715dba10390d526ebf5b50b0f645898a6d939e17d1003c16.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/1736db11fee8adee715dba10390d526ebf5b50b0f645898a6d939e17d1003c16.jpg)

![18a54ca20875a1ceffae2f5c14c3046c647207a3cac2866a50d999ce265e78b1.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/18a54ca20875a1ceffae2f5c14c3046c647207a3cac2866a50d999ce265e78b1.jpg)

![19c34767a50b96cbd14fa5e8a9a7e8ed51d92b0bed9df3b8a3b2485edc6e2581.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/19c34767a50b96cbd14fa5e8a9a7e8ed51d92b0bed9df3b8a3b2485edc6e2581.jpg)

![29cc9e9fba7415d0ce3f701b02f0ea0939d534a3aab16f07a0dd932f478fc0a2.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/29cc9e9fba7415d0ce3f701b02f0ea0939d534a3aab16f07a0dd932f478fc0a2.jpg)

![51ff2794c95ca457829f31758699a5f0cf710c70a6537899dd04717b22f94d97.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/51ff2794c95ca457829f31758699a5f0cf710c70a6537899dd04717b22f94d97.jpg)

![6ec755d2d8c229f76a52a70b9958310e107e7fab1d4c7acf3ce6775068d07bbf.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/6ec755d2d8c229f76a52a70b9958310e107e7fab1d4c7acf3ce6775068d07bbf.jpg)

![7d02f2516db7fa25c979d000c73df045cf0a0c4c82b4e66f358679ad7a149c0e.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/7d02f2516db7fa25c979d000c73df045cf0a0c4c82b4e66f358679ad7a149c0e.jpg)

![9209ab61ba83578e50b894d4b43dd7639e8e34fa63dcece360ea3b4900ef7e3a.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/9209ab61ba83578e50b894d4b43dd7639e8e34fa63dcece360ea3b4900ef7e3a.jpg)

![992e4a8d7ab18dc7b006fadc6ed371e36443044e8a165aed8873d499a06f499b.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/992e4a8d7ab18dc7b006fadc6ed371e36443044e8a165aed8873d499a06f499b.jpg)

![aa0dfa513843f4d21b5432f0705d326ed0a1c57566fa2894efe1b17779163fd3.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/aa0dfa513843f4d21b5432f0705d326ed0a1c57566fa2894efe1b17779163fd3.jpg)

![b050d006275a9c5de6c0e33cf0620d82d6213e45c43bea1084e068f29f59c432.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/b050d006275a9c5de6c0e33cf0620d82d6213e45c43bea1084e068f29f59c432.jpg)

![bb72b52340db00d3a3b790287c00b6f1890980da4487329964d0ebc221d445e1.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/bb72b52340db00d3a3b790287c00b6f1890980da4487329964d0ebc221d445e1.jpg)

![ff51cac9e7ae896a7ade58ea9038ac67260a54506124050ef7c0bc674eea8d92.jpg](../nips_results/1085_Differentially%20Private%20High-dimensional%20Variable%20Selection%20via%20Integer%20Programming/images/ff51cac9e7ae896a7ade58ea9038ac67260a54506124050ef7c0bc674eea8d92.jpg)
