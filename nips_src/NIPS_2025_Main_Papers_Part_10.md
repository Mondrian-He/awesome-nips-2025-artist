# NIPS 2025 Main Conference Papers

**Summary:** 41 papers with extracted content:
- 📊 Total images: 54033
- 📋 Total tables: 43661
- 📄 Total files: 97694

*Note: Equations have been filtered out and are not included.*

---

# NIPS 2025 Main Papers - Part 10 of 130

## 目录 (Table of Contents)

1. [Two Heads are Better than One: Simulating Large Transformers with Small Ones](#Two-Heads-are-Better-than-One-Simulating-Large-Transformers-with-Small-Ones)
2. [FFN Fusion: Rethinking Sequential Computation in Large Language Models](#FFN-Fusion-Rethinking-Sequential-Computation-in-Large-Language-Models)
3. [Critical Batch Size Revisited: A Simple Empirical Approach to Large-Batch Language Model Training](#Critical-Batch-Size-Revisited-A-Simple-Empirical-Approach-to-Large-Batch-Language-Model-Training)
4. [Among Us: A Sandbox for Measuring and Detecting Agentic Deception](#Among-Us-A-Sandbox-for-Measuring-and-Detecting-Agentic-Deception)
5. [Activation Control for Efficiently Eliciting Long Chain-of-thought Ability of Language Models](#Activation-Control-for-Efficiently-Eliciting-Long-Chain-of-thought-Ability-of-Language-Models)
6. [CTRL-ALT-DECEIT Sabotage Evaluations for Automated AI R&D](#CTRL-ALT-DECEIT-Sabotage-Evaluations-for-Automated-AI-RD)
7. [Communication-Efficient Language Model Training Scales Reliably and Robustly: Scaling Laws for DiLoCo](#Communication-Efficient-Language-Model-Training-Scales-Reliably-and-Robustly-Scaling-Laws-for-DiLoCo)
8. [🎧MOSPA: Human Motion Generation Driven by Spatial Audio](#MOSPA-Human-Motion-Generation-Driven-by-Spatial-Audio)
9. [Is the acquisition worth the cost? Surrogate losses for   Consistent Two-stage Classifiers](#Is-the-acquisition-worth-the-cost-Surrogate-losses-for-Consistent-Two-stage-Classifiers)
10. [Broken Tokens? Your Language Model can Secretly Handle Non-Canonical Tokenizations](#Broken-Tokens-Your-Language-Model-can-Secretly-Handle-Non-Canonical-Tokenizations)
11. [InstructHOI: Context-Aware Instruction for Multi-Modal Reasoning in Human-Object Interaction Detection](#InstructHOI-Context-Aware-Instruction-for-Multi-Modal-Reasoning-in-Human-Object-Interaction-Detection)
12. [Thoughts Are All Over the Place: On the Underthinking of Long Reasoning Models](#Thoughts-Are-All-Over-the-Place-On-the-Underthinking-of-Long-Reasoning-Models)
13. [Compositional Neural Network Verification via Assume-Guarantee Reasoning](#Compositional-Neural-Network-Verification-via-Assume-Guarantee-Reasoning)
14. [Puppeteer: Rig and Animate Your 3D Models](#Puppeteer-Rig-and-Animate-Your-3D-Models)
15. [Bridging Theory and Practice in Link Representation with Graph Neural Networks](#Bridging-Theory-and-Practice-in-Link-Representation-with-Graph-Neural-Networks)
16. [Unbiased Prototype Consistency Learning for Multi-Modal and Multi-Task Object Re-Identification](#Unbiased-Prototype-Consistency-Learning-for-Multi-Modal-and-Multi-Task-Object-Re-Identification)
17. [Head Pursuit: Probing Attention Specialization in Multimodal Transformers](#Head-Pursuit-Probing-Attention-Specialization-in-Multimodal-Transformers)
18. [Sparse VideoGen2: Accelerate Video Generation with  Sparse Attention via Semantic-Aware Permutation](#Sparse-VideoGen2-Accelerate-Video-Generation-with-Sparse-Attention-via-Semantic-Aware-Permutation)
19. [Strategic Costs of Perceived Bias in Fair Selection](#Strategic-Costs-of-Perceived-Bias-in-Fair-Selection)
20. [Pass@K Policy Optimization: Solving Harder Reinforcement Learning Problems](#PassK-Policy-Optimization-Solving-Harder-Reinforcement-Learning-Problems)
21. [Language Models can Self-Improve at State-Value Estimation for Better Search](#Language-Models-can-Self-Improve-at-State-Value-Estimation-for-Better-Search)
22. [HyPINO: Multi-Physics Neural Operators via HyperPINNs and the Method of Manufactured Solutions](#HyPINO-Multi-Physics-Neural-Operators-via-HyperPINNs-and-the-Method-of-Manufactured-Solutions)
23. [An Efficient Orlicz-Sobolev Approach for Transporting Unbalanced Measures on a Graph](#An-Efficient-Orlicz-Sobolev-Approach-for-Transporting-Unbalanced-Measures-on-a-Graph)
24. [Graph–Smoothed Bayesian Black-Box Shift Estimator and Its Information Geometry](#GraphSmoothed-Bayesian-Black-Box-Shift-Estimator-and-Its-Information-Geometry)
25. [Vision Transformers with Self-Distilled Registers](#Vision-Transformers-with-Self-Distilled-Registers)
26. [Language Modeling by Language Models](#Language-Modeling-by-Language-Models)
27. [Stable Gradients for Stable Learning at Scale in Deep Reinforcement Learning](#Stable-Gradients-for-Stable-Learning-at-Scale-in-Deep-Reinforcement-Learning)
28. [LoRAShop: Training-Free Multi-Concept Image Generation and Editing with Rectified Flow Transformers](#LoRAShop-Training-Free-Multi-Concept-Image-Generation-and-Editing-with-Rectified-Flow-Transformers)
29. [Distilling LLM Agent into Small Models with Retrieval and Code Tools](#Distilling-LLM-Agent-into-Small-Models-with-Retrieval-and-Code-Tools)
30. [AdaReasoner: Adaptive Reasoning Enables More Flexible Thinking](#AdaReasoner-Adaptive-Reasoning-Enables-More-Flexible-Thinking)
31. [Shallow Diffuse: Robust and Invisible Watermarking through Low-Dim Subspaces in Diffusion Models](#Shallow-Diffuse-Robust-and-Invisible-Watermarking-through-Low-Dim-Subspaces-in-Diffusion-Models)
32. [Twilight: Adaptive Attention Sparsity with Hierarchical Top-$p$  Pruning](#Twilight-Adaptive-Attention-Sparsity-with-Hierarchical-Top-p-Pruning)
33. [Joint Hierarchical Representation Learning of Samples and Features via Informed Tree-Wasserstein Distance](#Joint-Hierarchical-Representation-Learning-of-Samples-and-Features-via-Informed-Tree-Wasserstein-Distance)
34. [Towards Reliable Code-as-Policies: A Neuro-Symbolic Framework for Embodied Task Planning](#Towards-Reliable-Code-as-Policies-A-Neuro-Symbolic-Framework-for-Embodied-Task-Planning)
35. [ROGR: Relightable 3D Objects using Generative Relighting](#ROGR-Relightable-3D-Objects-using-Generative-Relighting)
36. [Blackbox Model Provenance via Palimpsestic Membership Inference](#Blackbox-Model-Provenance-via-Palimpsestic-Membership-Inference)
37. [OCTDiff: Bridged Diffusion Model for Portable OCT Super-Resolution and Enhancement](#OCTDiff-Bridged-Diffusion-Model-for-Portable-OCT-Super-Resolution-and-Enhancement)
38. [Improved Representation Steering for Language Models](#Improved-Representation-Steering-for-Language-Models)
39. [Generative Trajectory Stitching through Diffusion Composition](#Generative-Trajectory-Stitching-through-Diffusion-Composition)
40. [LLM-Explorer: A Plug-in Reinforcement Learning Policy Exploration Enhancement Driven by Large Language Models](#LLM-Explorer-A-Plug-in-Reinforcement-Learning-Policy-Exploration-Enhancement-Driven-by-Large-Language-Models)
41. [Unveiling the Power of Multiple Gossip Steps: A Stability-Based Generalization Analysis in Decentralized Training](#Unveiling-the-Power-of-Multiple-Gossip-Steps-A-Stability-Based-Generalization-Analysis-in-Decentralized-Training)

---


## Two Heads are Better than One: Simulating Large Transformers with Small Ones

### Images

![03bcfb897dee13abb9f98c942a13a41e8c4b82d8db097c56e65b919fa597a241.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/images/03bcfb897dee13abb9f98c942a13a41e8c4b82d8db097c56e65b919fa597a241.jpg)

![5ed5c16658d216713d52e2080c27507327569c2df1f3569060917a1a551bd066.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/images/5ed5c16658d216713d52e2080c27507327569c2df1f3569060917a1a551bd066.jpg)

![b4957e80e4beb1b2ef0f9d92134ef56c9928bcb7f3fa623971ede3ab76521a29.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/images/b4957e80e4beb1b2ef0f9d92134ef56c9928bcb7f3fa623971ede3ab76521a29.jpg)

![bcae0fa260c8fbf51ba884004e83b84e2d46f5e6796d7d595998934cdd2fa67d.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/images/bcae0fa260c8fbf51ba884004e83b84e2d46f5e6796d7d595998934cdd2fa67d.jpg)

![bda2e7a951c21bb3b31195220aef6105ccc9dc3a8a5e90c53a870b0ae39202e3.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/images/bda2e7a951c21bb3b31195220aef6105ccc9dc3a8a5e90c53a870b0ae39202e3.jpg)

![c08f5cf0954b5377d7a06c81373a2efa264d0c79c83d196e475b6c7843c6715c.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/images/c08f5cf0954b5377d7a06c81373a2efa264d0c79c83d196e475b6c7843c6715c.jpg)

![cae6a7c2927df612b99727b3a7d2ef4052aed15dcbed32b4c928753c68adf471.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/images/cae6a7c2927df612b99727b3a7d2ef4052aed15dcbed32b4c928753c68adf471.jpg)

![f2852266c587e1383d6c8768c6cd5ae993a75496825a745e700784a565b52852.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/images/f2852266c587e1383d6c8768c6cd5ae993a75496825a745e700784a565b52852.jpg)

### Tables

![1cc337abc5171990add50395de9e177b5f1f4ec5e164454c9e58036a9cee6598.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/tables/1cc337abc5171990add50395de9e177b5f1f4ec5e164454c9e58036a9cee6598.jpg)

![51cd2f8e2b459bcd2bbc147fc6892d2e4170b2337682f02d8304c921e0b9ba81.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/tables/51cd2f8e2b459bcd2bbc147fc6892d2e4170b2337682f02d8304c921e0b9ba81.jpg)

![66a730701ddaae19fa85555f0908eca2943a5d6776f9fae2e306e14bd9e72c68.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/tables/66a730701ddaae19fa85555f0908eca2943a5d6776f9fae2e306e14bd9e72c68.jpg)

![6b7fbf517089697dce7aeeb396e8b90c4644004adfdaf60792e12f33572882d4.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/tables/6b7fbf517089697dce7aeeb396e8b90c4644004adfdaf60792e12f33572882d4.jpg)

![75f15dac1828b9031a52aa7632a0d2593b5626dcc6318bcd7e585857f272ce75.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/tables/75f15dac1828b9031a52aa7632a0d2593b5626dcc6318bcd7e585857f272ce75.jpg)

![c4a949715c295e3f707adb98953c2929d020d5b473cce5fe9b161eae2abe33bf.jpg](../nips_results/378_MonarchAttention_%20Zero-Shot%20Conversion%20to%20Fast%2C%20Hardware-Aware%20Structured%20Attention/tables/c4a949715c295e3f707adb98953c2929d020d5b473cce5fe9b161eae2abe33bf.jpg)

## Two Heads are Better than One: Simulating Large Transformers with Small Ones


### Images

![a241a7bf93b037560262baad6f604c35341f61394420240d8f0edd23978b4c6b.jpg](../nips_results/379_Two%20Heads%20are%20Better%20than%20One_%20Simulating%20Large%20Transformers%20with%20Small%20Ones/images/a241a7bf93b037560262baad6f604c35341f61394420240d8f0edd23978b4c6b.jpg)

## FFN Fusion: Rethinking Sequential Computation in Large Language Models


### Images

![323a868479762199825c2f76ff2a3d00b047169147692cc46920fdea69b1bddf.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/images/323a868479762199825c2f76ff2a3d00b047169147692cc46920fdea69b1bddf.jpg)

![3a680cae06018e5aa5c4037ccf55d793879c866fedf713fc2bfde44f58512db1.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/images/3a680cae06018e5aa5c4037ccf55d793879c866fedf713fc2bfde44f58512db1.jpg)

![64ce9e02e0e4beb7f415bf902419a2abe77fce3b996464bdeacd220ec6b4ff1c.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/images/64ce9e02e0e4beb7f415bf902419a2abe77fce3b996464bdeacd220ec6b4ff1c.jpg)

![841d153799afa15606a188e8df7b1fea78e01329bbff6851abff94ad8df67c46.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/images/841d153799afa15606a188e8df7b1fea78e01329bbff6851abff94ad8df67c46.jpg)

![9694ced75083bed11f3248ecccd79c657fa2db054f8da8f9b2c9f955e2e88a86.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/images/9694ced75083bed11f3248ecccd79c657fa2db054f8da8f9b2c9f955e2e88a86.jpg)

![a8d02f5c820673c0f91b6eafc38e1b5fb83041eb5182337599cac744dfc74b66.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/images/a8d02f5c820673c0f91b6eafc38e1b5fb83041eb5182337599cac744dfc74b66.jpg)

![b4eac4a46c9f36b5a791e1d9d14ae288ee92ed7be5ad39bf85ea6c9b8dac8885.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/images/b4eac4a46c9f36b5a791e1d9d14ae288ee92ed7be5ad39bf85ea6c9b8dac8885.jpg)

![b8289a99cb9f766d3fe337127f7316ad7b27737a49765ee1d618a0aeeee64814.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/images/b8289a99cb9f766d3fe337127f7316ad7b27737a49765ee1d618a0aeeee64814.jpg)

![dd83306bb6478ad864f26fe83e0a0445b4351f21f876a62248da78b55954d7b9.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/images/dd83306bb6478ad864f26fe83e0a0445b4351f21f876a62248da78b55954d7b9.jpg)

![ddc30eb771eb5ed39802f139c97ed0f35cc2c27ac8634646953def08559b2c35.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/images/ddc30eb771eb5ed39802f139c97ed0f35cc2c27ac8634646953def08559b2c35.jpg)

![e2b9501f4566466a9bb781cf6048e70da53b17d411fac8d46ccd7dadac9a84fb.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/images/e2b9501f4566466a9bb781cf6048e70da53b17d411fac8d46ccd7dadac9a84fb.jpg)

### Tables

![2e217d1c747b5e37aff7fcc2d8353b8e97c31e27255fc4758fb184c59b9e3593.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/tables/2e217d1c747b5e37aff7fcc2d8353b8e97c31e27255fc4758fb184c59b9e3593.jpg)

![60340542e6444ad89f4a97e84ef26d45c4d7640876deddcedfa445cc2639e4d8.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/tables/60340542e6444ad89f4a97e84ef26d45c4d7640876deddcedfa445cc2639e4d8.jpg)

![7bdac8c0337c1deca8291913afb9c6d06ced2ac14dc909fa7d0960a3203fedbc.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/tables/7bdac8c0337c1deca8291913afb9c6d06ced2ac14dc909fa7d0960a3203fedbc.jpg)

![7df03279256dd743b4cb6632ecc260743bda86f22be619c7af00af7193755650.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/tables/7df03279256dd743b4cb6632ecc260743bda86f22be619c7af00af7193755650.jpg)

![965b56802f6eb4a1b534f70b074814a1427a568016b944a45bc5dd70018fcbc1.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/tables/965b56802f6eb4a1b534f70b074814a1427a568016b944a45bc5dd70018fcbc1.jpg)

![dc1619f8595e8bd5752328604ab4d57690cdedca24eb0203415d998cc2192c60.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/tables/dc1619f8595e8bd5752328604ab4d57690cdedca24eb0203415d998cc2192c60.jpg)

![e30a8b49cd29529bff22c0adfbffeaf46335ef5433f8f47fddf5bff140bca7ed.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/tables/e30a8b49cd29529bff22c0adfbffeaf46335ef5433f8f47fddf5bff140bca7ed.jpg)

![f7bbfc84b293df792d4a6bdafd1d370b09505c0c16da7792a6607a46fdc53bc2.jpg](../nips_results/380_FFN%20Fusion_%20Rethinking%20Sequential%20Computation%20in%20Large%20Language%20Models/tables/f7bbfc84b293df792d4a6bdafd1d370b09505c0c16da7792a6607a46fdc53bc2.jpg)

## Critical Batch Size Revisited: A Simple Empirical Approach to Large-Batch Language Model Training


### Images

![14f04aae8c4be4cec4459f16457b0c3639cc76e30edea3d4c6c4f58e438343eb.jpg](../nips_results/381_Critical%20Batch%20Size%20Revisited_%20A%20Simple%20Empirical%20Approach%20to%20Large-Batch%20Language%20Model%20Training/images/14f04aae8c4be4cec4459f16457b0c3639cc76e30edea3d4c6c4f58e438343eb.jpg)

![158047f083170204a1afdef262415fd9ea420c4a680fa6dc0a752af79090a65e.jpg](../nips_results/381_Critical%20Batch%20Size%20Revisited_%20A%20Simple%20Empirical%20Approach%20to%20Large-Batch%20Language%20Model%20Training/images/158047f083170204a1afdef262415fd9ea420c4a680fa6dc0a752af79090a65e.jpg)

![70eab6810fc5b719df46a89926ca56c271e9a35b4507568fd1a50937d1fe8a78.jpg](../nips_results/381_Critical%20Batch%20Size%20Revisited_%20A%20Simple%20Empirical%20Approach%20to%20Large-Batch%20Language%20Model%20Training/images/70eab6810fc5b719df46a89926ca56c271e9a35b4507568fd1a50937d1fe8a78.jpg)

![79389f5994211b5946ab04dc3594460741ea73d309068084e54294675f68d4f5.jpg](../nips_results/381_Critical%20Batch%20Size%20Revisited_%20A%20Simple%20Empirical%20Approach%20to%20Large-Batch%20Language%20Model%20Training/images/79389f5994211b5946ab04dc3594460741ea73d309068084e54294675f68d4f5.jpg)

![b03f73659d6e623a6d415abece1408537d3704613d81ea7222571aaed54ded67.jpg](../nips_results/381_Critical%20Batch%20Size%20Revisited_%20A%20Simple%20Empirical%20Approach%20to%20Large-Batch%20Language%20Model%20Training/images/b03f73659d6e623a6d415abece1408537d3704613d81ea7222571aaed54ded67.jpg)

![e0bfa47c92f9d18f855a1277988679a3c8c1abb61a5c2ccea0b77b8e0ba6b62d.jpg](../nips_results/381_Critical%20Batch%20Size%20Revisited_%20A%20Simple%20Empirical%20Approach%20to%20Large-Batch%20Language%20Model%20Training/images/e0bfa47c92f9d18f855a1277988679a3c8c1abb61a5c2ccea0b77b8e0ba6b62d.jpg)

![fb2da437c30d6add6f57e9a11a02ef147e8918f1218f503ae56182b6c292ff2e.jpg](../nips_results/381_Critical%20Batch%20Size%20Revisited_%20A%20Simple%20Empirical%20Approach%20to%20Large-Batch%20Language%20Model%20Training/images/fb2da437c30d6add6f57e9a11a02ef147e8918f1218f503ae56182b6c292ff2e.jpg)

### Tables

![58c008155061ffe42b22e7c30f2b2ec1f4ac8e71e905e6d5ad31e5e568a699c2.jpg](../nips_results/381_Critical%20Batch%20Size%20Revisited_%20A%20Simple%20Empirical%20Approach%20to%20Large-Batch%20Language%20Model%20Training/tables/58c008155061ffe42b22e7c30f2b2ec1f4ac8e71e905e6d5ad31e5e568a699c2.jpg)

![c6b481f37be44e1f5904a8955decad23eeabb425c5b12332683e846a3c4ce539.jpg](../nips_results/381_Critical%20Batch%20Size%20Revisited_%20A%20Simple%20Empirical%20Approach%20to%20Large-Batch%20Language%20Model%20Training/tables/c6b481f37be44e1f5904a8955decad23eeabb425c5b12332683e846a3c4ce539.jpg)

![ded373cb9d52c9d709af31230a9c9f45d50bf2847d3032decf034eae1ce93d15.jpg](../nips_results/381_Critical%20Batch%20Size%20Revisited_%20A%20Simple%20Empirical%20Approach%20to%20Large-Batch%20Language%20Model%20Training/tables/ded373cb9d52c9d709af31230a9c9f45d50bf2847d3032decf034eae1ce93d15.jpg)

## Among Us: A Sandbox for Measuring and Detecting Agentic Deception


### Images

![0795868ff288b7213ab772f99776c2f4f92a82b7e64f932c075c936b37eb637b.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/0795868ff288b7213ab772f99776c2f4f92a82b7e64f932c075c936b37eb637b.jpg)

![08df4c724c7fbde5736609a30b419ac37d34487649a1bcefe50ab2610d07d10f.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/08df4c724c7fbde5736609a30b419ac37d34487649a1bcefe50ab2610d07d10f.jpg)

![116ed43e687b789ea5197b94cb50fca68cadf7c59a52c1e7ea3120c7a84d8202.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/116ed43e687b789ea5197b94cb50fca68cadf7c59a52c1e7ea3120c7a84d8202.jpg)

![15e9aaedc159a7277983f9cbea6202c4d393f9df9585e4783449726e5462134d.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/15e9aaedc159a7277983f9cbea6202c4d393f9df9585e4783449726e5462134d.jpg)

![5f87c5694eefcab3a375cc9c0c4a8de1cc539b2fd044c2cd6d62d47b7977e290.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/5f87c5694eefcab3a375cc9c0c4a8de1cc539b2fd044c2cd6d62d47b7977e290.jpg)

![6156f782dba2e6c27ed511665fb47e5d871feb273388f0d35981d78376341eef.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/6156f782dba2e6c27ed511665fb47e5d871feb273388f0d35981d78376341eef.jpg)

![a9cf063d6c003183076f804a63f6051513f35466d2134f3d907646d4b91d2b68.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/a9cf063d6c003183076f804a63f6051513f35466d2134f3d907646d4b91d2b68.jpg)

![ada83b0a4347d7c650da6d1c0a3c228f186f54aba9bf664a17f934b8bcfd7ed1.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/ada83b0a4347d7c650da6d1c0a3c228f186f54aba9bf664a17f934b8bcfd7ed1.jpg)

![ba0f6f49a977edf062d95458656730a98d704be494f4e160f01e9232e0b579b8.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/ba0f6f49a977edf062d95458656730a98d704be494f4e160f01e9232e0b579b8.jpg)

![cb9963ed2cb066c3c3a58ec70f98507f3fed1b768ca81ba6bfa560195bfe0fa4.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/cb9963ed2cb066c3c3a58ec70f98507f3fed1b768ca81ba6bfa560195bfe0fa4.jpg)

![df19aa9312b535002af0f11e166d28c8e1d02eb556a0c121d4cd2948cab4604f.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/df19aa9312b535002af0f11e166d28c8e1d02eb556a0c121d4cd2948cab4604f.jpg)

![e41e46e7be62987d8b170750ec23f85d61a6aa56b25cea4eb3d12c35094c79dc.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/e41e46e7be62987d8b170750ec23f85d61a6aa56b25cea4eb3d12c35094c79dc.jpg)

![fac7d576a61b2ce4f0107f7719c21f1067c5b38c27d21be87318502775911fd4.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/fac7d576a61b2ce4f0107f7719c21f1067c5b38c27d21be87318502775911fd4.jpg)

![fb91d547b363f9247d64936da656eccd141ec9090c25901260e016145e32c96b.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/images/fb91d547b363f9247d64936da656eccd141ec9090c25901260e016145e32c96b.jpg)

### Tables

![8c5fab34328874b0aa8eff38407db3daec020a66e5855ebbcf17922cfa06f442.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/tables/8c5fab34328874b0aa8eff38407db3daec020a66e5855ebbcf17922cfa06f442.jpg)

![fc1608241fb73b952e83af7f4fc6f2395b6b514680b82739d7f6dba55e90cd2c.jpg](../nips_results/382_Among%20Us_%20A%20Sandbox%20for%20Measuring%20and%20Detecting%20Agentic%20Deception/tables/fc1608241fb73b952e83af7f4fc6f2395b6b514680b82739d7f6dba55e90cd2c.jpg)

## Activation Control for Efficiently Eliciting Long Chain-of-thought Ability of Language Models


### Images

![0c3fc60276bfb4bd71bfb0a3432ec899b0f473f40f191d1140ffd69e22942477.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/images/0c3fc60276bfb4bd71bfb0a3432ec899b0f473f40f191d1140ffd69e22942477.jpg)

![2a3cce001e588006ecf97ceabc87b31b142f76d89fc19b2938cde153b94b414b.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/images/2a3cce001e588006ecf97ceabc87b31b142f76d89fc19b2938cde153b94b414b.jpg)

![2cd8fe7dedccafa32da0f92d554f0534a3c2af78756dc29d8d4923dd9972136d.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/images/2cd8fe7dedccafa32da0f92d554f0534a3c2af78756dc29d8d4923dd9972136d.jpg)

![31ca049606b2248d88c9c32704b5a558fe73cdbebc9c4b9d676d32e33826c87f.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/images/31ca049606b2248d88c9c32704b5a558fe73cdbebc9c4b9d676d32e33826c87f.jpg)

![483776249006e113267ba6a8dae25588a15eb82823706d4cab23638e44ccebc9.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/images/483776249006e113267ba6a8dae25588a15eb82823706d4cab23638e44ccebc9.jpg)

![54bb3aa4f471a3aaab832d3d1bc3f9dafc148bb62be032bb8533a137f85dc1ad.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/images/54bb3aa4f471a3aaab832d3d1bc3f9dafc148bb62be032bb8533a137f85dc1ad.jpg)

![5e7229f6dd2dc2418969a29519bc2edd1c74a38bbb1c6b9e08db508db1ee4413.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/images/5e7229f6dd2dc2418969a29519bc2edd1c74a38bbb1c6b9e08db508db1ee4413.jpg)

![eacd010aed77fdb46cd0bb40c6f7622acca5fe8eac322f4a005b00759182d1b6.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/images/eacd010aed77fdb46cd0bb40c6f7622acca5fe8eac322f4a005b00759182d1b6.jpg)

![fbb96a3f881dcc5115ce68caae164627d7537a3dc290b17ea30097e1ae05db47.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/images/fbb96a3f881dcc5115ce68caae164627d7537a3dc290b17ea30097e1ae05db47.jpg)

### Tables

![05f387c6bb3de3e65b5106e276b4be39598bea77f85bdcd60746f6fd997a2bbe.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/tables/05f387c6bb3de3e65b5106e276b4be39598bea77f85bdcd60746f6fd997a2bbe.jpg)

![083ab7a9e9ce30117f000360e34a07a7900aa8a8a6a39ab3258c4d8a0c4b9f37.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/tables/083ab7a9e9ce30117f000360e34a07a7900aa8a8a6a39ab3258c4d8a0c4b9f37.jpg)

![57a0028f77764b45052a8d226c0ba1498631aba17dfc2825c8564c7273d0313f.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/tables/57a0028f77764b45052a8d226c0ba1498631aba17dfc2825c8564c7273d0313f.jpg)

![590af20a764b8e57c5ec73c2215f9fbe3468d7517f988100905a330dd62bf34f.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/tables/590af20a764b8e57c5ec73c2215f9fbe3468d7517f988100905a330dd62bf34f.jpg)

![771f721a4cb2167277e390590de78a28ebb353ecf70d21fe931ff06e4e84e7f2.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/tables/771f721a4cb2167277e390590de78a28ebb353ecf70d21fe931ff06e4e84e7f2.jpg)

![ae410b1c9014e4e70fa615914f4fefd0ceda189bada35415ce00981af6ba3425.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/tables/ae410b1c9014e4e70fa615914f4fefd0ceda189bada35415ce00981af6ba3425.jpg)

![b529264ecf6d95b303f5733316ee9a46d63809d83978234ff5c33cac1ebd5916.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/tables/b529264ecf6d95b303f5733316ee9a46d63809d83978234ff5c33cac1ebd5916.jpg)

![e82bf247ef2709a1c121be60f5138bcd00cc348628f3e7e8a66291c89903ffe9.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/tables/e82bf247ef2709a1c121be60f5138bcd00cc348628f3e7e8a66291c89903ffe9.jpg)

![eb41f787ae570bdb212a9c64ce4226f8b925455cffb8a8dd754f37dc20c1d88a.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/tables/eb41f787ae570bdb212a9c64ce4226f8b925455cffb8a8dd754f37dc20c1d88a.jpg)

![ecda8c462231c626696bf5c4d77c7f35476e0233963f5e22edcd4b649bea3e6e.jpg](../nips_results/383_Activation%20Control%20for%20Efficiently%20Eliciting%20Long%20Chain-of-thought%20Ability%20of%20Language%20Models/tables/ecda8c462231c626696bf5c4d77c7f35476e0233963f5e22edcd4b649bea3e6e.jpg)

## CTRL-ALT-DECEIT Sabotage Evaluations for Automated AI R&D


### Images

![1a30e08a3622838beb985859a8c0f744b50ac91c8cab86952d8239b4d462b0fb.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/1a30e08a3622838beb985859a8c0f744b50ac91c8cab86952d8239b4d462b0fb.jpg)

![30006a9eb510845078d186db84e655ae74c9e56d65b9da53c23bedac7794874b.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/30006a9eb510845078d186db84e655ae74c9e56d65b9da53c23bedac7794874b.jpg)

![320f4de51dec9829e3bd5338164afea072fd70e7a85a4e0539340e34da769997.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/320f4de51dec9829e3bd5338164afea072fd70e7a85a4e0539340e34da769997.jpg)

![36674a74da58a4b8a5c9c4e43d3b7c91d9a6d4345ad9b8b334aa843742faed2e.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/36674a74da58a4b8a5c9c4e43d3b7c91d9a6d4345ad9b8b334aa843742faed2e.jpg)

![4c367373b6eb9b7750bb9a9929a1c1eec5f936c81a1836e668d499a2188ff9f0.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/4c367373b6eb9b7750bb9a9929a1c1eec5f936c81a1836e668d499a2188ff9f0.jpg)

![63b4e66a42b6c01012160ef39f421fbcf8c8a207a1e46df2e3dcd94ffb5e9e74.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/63b4e66a42b6c01012160ef39f421fbcf8c8a207a1e46df2e3dcd94ffb5e9e74.jpg)

![6c7a950fa198c17f729e85fd3745a059748dba4bf78c532a49c2d6d88212ce01.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/6c7a950fa198c17f729e85fd3745a059748dba4bf78c532a49c2d6d88212ce01.jpg)

![740f9ff783fb19e7b05a6fe242d225c7ab4e734dbbcf44c0c1a5c409a9fe9c91.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/740f9ff783fb19e7b05a6fe242d225c7ab4e734dbbcf44c0c1a5c409a9fe9c91.jpg)

![782015c7a732741f446ac967888587b651d557c90afd38de451e991eb7b7eabf.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/782015c7a732741f446ac967888587b651d557c90afd38de451e991eb7b7eabf.jpg)

![85dda0f27abe18037e783429ccecfee0e71c00970c1575fe17fae16d7ffe65ce.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/85dda0f27abe18037e783429ccecfee0e71c00970c1575fe17fae16d7ffe65ce.jpg)

![93d16ad2406d4e2add55a013b9f03d64d04294d8b81a633d3fa74e6995f69d0f.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/93d16ad2406d4e2add55a013b9f03d64d04294d8b81a633d3fa74e6995f69d0f.jpg)

![9f8557417f153475ad72517d91e49017b5935f20153a759251f58ed824b8c778.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/9f8557417f153475ad72517d91e49017b5935f20153a759251f58ed824b8c778.jpg)

![bb54d214857ea338ee40fd0c9b7ff071de16f83bb7edab3f4b65fabfda868e1f.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/bb54d214857ea338ee40fd0c9b7ff071de16f83bb7edab3f4b65fabfda868e1f.jpg)

![be9c4fb95444be3016a93539c3e577f4fb76057a46a881901ea601ae658248ec.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/be9c4fb95444be3016a93539c3e577f4fb76057a46a881901ea601ae658248ec.jpg)

![cc1730131e56e6d6ea1d1bb39a3e8a783e10c2615ca48ff9592a84a5988521c1.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/cc1730131e56e6d6ea1d1bb39a3e8a783e10c2615ca48ff9592a84a5988521c1.jpg)

![cdc10a0f8122dc04fe308a15671f04cdef2af1a7a24b5d38e64bcd0921f41e0c.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/cdc10a0f8122dc04fe308a15671f04cdef2af1a7a24b5d38e64bcd0921f41e0c.jpg)

![d1e5c45e437be5fecc3c239fa110779ed0a4c0e4e5e048281d666ae4819f4bbd.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/d1e5c45e437be5fecc3c239fa110779ed0a4c0e4e5e048281d666ae4819f4bbd.jpg)

![d2f33821328b6e92437cd7b9cbe3b10548ddcdf596418cfdbe2eb6bad6dca3f9.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/d2f33821328b6e92437cd7b9cbe3b10548ddcdf596418cfdbe2eb6bad6dca3f9.jpg)

![f14ac49cafdb2bc2f01a153008f30ec0ebc7f43b229b03515a5d885bdadbb860.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/f14ac49cafdb2bc2f01a153008f30ec0ebc7f43b229b03515a5d885bdadbb860.jpg)

![fb644523ea017d080b13191f025b29e36bdd8f5c6b5d9f67d23a5b63e9f67ba5.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/images/fb644523ea017d080b13191f025b29e36bdd8f5c6b5d9f67d23a5b63e9f67ba5.jpg)

### Tables

![11c2ac58b0b2b34a61bc841682b058d7adf52f0e9b12e0a0522202222c0902c9.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/tables/11c2ac58b0b2b34a61bc841682b058d7adf52f0e9b12e0a0522202222c0902c9.jpg)

![507b49d7709b1196b593f1a2a3e733ae69cc34990bbd48e4832179c1278a06f3.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/tables/507b49d7709b1196b593f1a2a3e733ae69cc34990bbd48e4832179c1278a06f3.jpg)

![6babdfef1dcbdf9439f8e33e3a295b257c4dab36c0b5f2959a862835ce87957e.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/tables/6babdfef1dcbdf9439f8e33e3a295b257c4dab36c0b5f2959a862835ce87957e.jpg)

![71fd628a22a8af05cb780e9ea1e5eb3dc7dc5e47c7c2b61f19df228194331d5f.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/tables/71fd628a22a8af05cb780e9ea1e5eb3dc7dc5e47c7c2b61f19df228194331d5f.jpg)

![95f1ea11b31db6367a94d9d7961c691a338fdba0d568c95308422de051d147a6.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/tables/95f1ea11b31db6367a94d9d7961c691a338fdba0d568c95308422de051d147a6.jpg)

![990f300b8428add3202bcdd97111ee9c8f6f03ef3a62cd18b02bbfda20d67f0c.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/tables/990f300b8428add3202bcdd97111ee9c8f6f03ef3a62cd18b02bbfda20d67f0c.jpg)

![9a82ac18e07a94530806cf768a1b9659d1ec572d3670e594f485db82ad6ab244.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/tables/9a82ac18e07a94530806cf768a1b9659d1ec572d3670e594f485db82ad6ab244.jpg)

![d3da452be716b4ee23dbe9badae08589482ca6d04671946c471874dfcffdf5b1.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/tables/d3da452be716b4ee23dbe9badae08589482ca6d04671946c471874dfcffdf5b1.jpg)

![d8047c203f4d46dafd66ff3c24039446dd1405459ab2bd504930609b88bef6e1.jpg](../nips_results/384_CTRL-ALT-DECEIT%20Sabotage%20Evaluations%20for%20Automated%20AI%20R%26D/tables/d8047c203f4d46dafd66ff3c24039446dd1405459ab2bd504930609b88bef6e1.jpg)

## Communication-Efficient Language Model Training Scales Reliably and Robustly: Scaling Laws for DiLoCo


### Images

![058341698d6cbfe46308297f95dd26516156da0f0dcbacaaabfdf41e60dca271.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/058341698d6cbfe46308297f95dd26516156da0f0dcbacaaabfdf41e60dca271.jpg)

![0a9f472aaa643652ff821d7c842f94c0a52d85e7fce6da7ebbf68644cd93e3c3.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/0a9f472aaa643652ff821d7c842f94c0a52d85e7fce6da7ebbf68644cd93e3c3.jpg)

![0c3f0f10433afd55d64e8227ea8ffe1371fb81e460d7d386a129028b563833d7.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/0c3f0f10433afd55d64e8227ea8ffe1371fb81e460d7d386a129028b563833d7.jpg)

![0ccef1dfd8416f531a5e1d54a821380a2acde087aa2816e6c78761439de87dbf.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/0ccef1dfd8416f531a5e1d54a821380a2acde087aa2816e6c78761439de87dbf.jpg)

![1b0140627a7fae60f536aa5f5e430077531c713d36bf81f8d5f1b97897d73fb5.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/1b0140627a7fae60f536aa5f5e430077531c713d36bf81f8d5f1b97897d73fb5.jpg)

![3036c42d2c26825ede8093fa47ba26e0dafc0b36848aae3eb63f734008ec4bed.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/3036c42d2c26825ede8093fa47ba26e0dafc0b36848aae3eb63f734008ec4bed.jpg)

![325c386c2c01878ac145643d58955fd4c433dcf1052021c103c1305c52543ea8.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/325c386c2c01878ac145643d58955fd4c433dcf1052021c103c1305c52543ea8.jpg)

![3478ca7f647482c0c37f0f4fa48b806b961ba8f879725269569720a5c15f3408.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/3478ca7f647482c0c37f0f4fa48b806b961ba8f879725269569720a5c15f3408.jpg)

![3a3ea27c653e593f174fc9b7c3db661a7b601fc596c4b89c92aabd2eeddad30f.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/3a3ea27c653e593f174fc9b7c3db661a7b601fc596c4b89c92aabd2eeddad30f.jpg)

![3fa2a45b79433a64a2c90d812d54325a22ba9f5a9a755b3d9a80932135934b6b.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/3fa2a45b79433a64a2c90d812d54325a22ba9f5a9a755b3d9a80932135934b6b.jpg)

![46c2a70ed119b3315eaa4f487c5aa7392fd524b1cb2dba2f26932c919d953041.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/46c2a70ed119b3315eaa4f487c5aa7392fd524b1cb2dba2f26932c919d953041.jpg)

![4a02325cf03ac109052793c0c05e84066bf8a03afafb1cffc69d984e251d6e83.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/4a02325cf03ac109052793c0c05e84066bf8a03afafb1cffc69d984e251d6e83.jpg)

![5754554fbc9b57d57531e8fc6920ab26362640eed12b1160f091fb4ba1b56c5c.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/5754554fbc9b57d57531e8fc6920ab26362640eed12b1160f091fb4ba1b56c5c.jpg)

![5c4d961bfce5d6bad558aa6e047d1903670c98ff8d999e9a8e72aea09d6ba9af.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/5c4d961bfce5d6bad558aa6e047d1903670c98ff8d999e9a8e72aea09d6ba9af.jpg)

![6568e371488b481cf8c84431954ac080b4bdae88d495bac8495f45e40b8304f5.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/6568e371488b481cf8c84431954ac080b4bdae88d495bac8495f45e40b8304f5.jpg)

![8348657f6ca7cac7dd9646211327a378316bdc2a1868d72a234af5b75b2a4fa1.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/8348657f6ca7cac7dd9646211327a378316bdc2a1868d72a234af5b75b2a4fa1.jpg)

![8e4eb920698c92f3854bdd54b14c89335a0d9c58930bb3fe3f10607b07821941.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/8e4eb920698c92f3854bdd54b14c89335a0d9c58930bb3fe3f10607b07821941.jpg)

![9abb56e74d0097ac088bc50b9e806eb8c0ff2a3b52686689ae15c76062cc3b42.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/9abb56e74d0097ac088bc50b9e806eb8c0ff2a3b52686689ae15c76062cc3b42.jpg)

![a0ca321189e31c0dd106b01d6f74ce49f599e72213b9d0783e9088f0ffa429dc.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/a0ca321189e31c0dd106b01d6f74ce49f599e72213b9d0783e9088f0ffa429dc.jpg)

![a5e60c7d050ef11a5000e763d5ea651d36d6d01136c866adb0bd46e6d56e9994.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/a5e60c7d050ef11a5000e763d5ea651d36d6d01136c866adb0bd46e6d56e9994.jpg)

![ab5ecc518c819fbe879d53569c4d27e209ddd00e64f8bb60a9099251968a0777.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/ab5ecc518c819fbe879d53569c4d27e209ddd00e64f8bb60a9099251968a0777.jpg)

![be0c10da9d67b7f35e3488e74ebecd524f880551995d4824093d13c7d10cca7e.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/be0c10da9d67b7f35e3488e74ebecd524f880551995d4824093d13c7d10cca7e.jpg)

![ca3208f401b7be3d10631f212305d45fbb8762f3cf2aa5e88af2f6b006af43b8.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/ca3208f401b7be3d10631f212305d45fbb8762f3cf2aa5e88af2f6b006af43b8.jpg)

![eace1c846f9df73cff9cd852e05c034c7027074c7143dd165a89b170e5f5958a.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/images/eace1c846f9df73cff9cd852e05c034c7027074c7143dd165a89b170e5f5958a.jpg)

### Tables

![172d80e5f34e08b947f660a5e4d456b4daf4cf9c1aa2b340c85128708ae23b3a.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/172d80e5f34e08b947f660a5e4d456b4daf4cf9c1aa2b340c85128708ae23b3a.jpg)

![40d51193c0847a5e8d688f113ef29c246b8b3e206fa7438d4cd7d88f4e11c62b.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/40d51193c0847a5e8d688f113ef29c246b8b3e206fa7438d4cd7d88f4e11c62b.jpg)

![5727f6df36e968b363a7f639c9778803c4f7d00d9046e79fb8eeff20bde9ff23.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/5727f6df36e968b363a7f639c9778803c4f7d00d9046e79fb8eeff20bde9ff23.jpg)

![5b2cd5a54b257f23dadde75fecb152f50e55395e6a0156f9e18d1f14836db55a.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/5b2cd5a54b257f23dadde75fecb152f50e55395e6a0156f9e18d1f14836db55a.jpg)

![5e54028eae03be305849b13274d8350355f37d084f8dd15906a6ac925adfa388.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/5e54028eae03be305849b13274d8350355f37d084f8dd15906a6ac925adfa388.jpg)

![624ee5726182c3bdc10f863c1d1fd446ac5c419065963a177ae5c8fde4531b5f.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/624ee5726182c3bdc10f863c1d1fd446ac5c419065963a177ae5c8fde4531b5f.jpg)

![675914c9a838caf262d80559a020f2a8a1ecf94dfaa707065b951c34f54d4ddb.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/675914c9a838caf262d80559a020f2a8a1ecf94dfaa707065b951c34f54d4ddb.jpg)

![8075ebaeb73902947c7741f5bde644ed442208ec2a38ddaae0b6ab35f776bf24.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/8075ebaeb73902947c7741f5bde644ed442208ec2a38ddaae0b6ab35f776bf24.jpg)

![85533663963342e052ecfab9fab9bc74a34807438fa7bb7387f32d267a44f6c5.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/85533663963342e052ecfab9fab9bc74a34807438fa7bb7387f32d267a44f6c5.jpg)

![8ca45a9b235bc26dacab9826e8176c6688f3f63ca253028e38a76344e12014e5.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/8ca45a9b235bc26dacab9826e8176c6688f3f63ca253028e38a76344e12014e5.jpg)

![9ee8b6b2b4a86caf5ad6d66e0bb2eff37f00ecc088b574372d344e8bcc1f4a6a.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/9ee8b6b2b4a86caf5ad6d66e0bb2eff37f00ecc088b574372d344e8bcc1f4a6a.jpg)

![a9263420628a45441b19df77d61e833d52c5c438590e13901eaaa810290237e8.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/a9263420628a45441b19df77d61e833d52c5c438590e13901eaaa810290237e8.jpg)

![c9efbfb2edb0a7b0176f153462873dcedabfa3136ff22779f54be6f5f7548e12.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/c9efbfb2edb0a7b0176f153462873dcedabfa3136ff22779f54be6f5f7548e12.jpg)

![e9347be44458d6b9513310947f50f0c8c6554aaffc462266052c8cf79d5cb893.jpg](../nips_results/385_Communication-Efficient%20Language%20Model%20Training%20Scales%20Reliably%20and%20Robustly_%20Scaling%20Laws%20for%20DiLoC/tables/e9347be44458d6b9513310947f50f0c8c6554aaffc462266052c8cf79d5cb893.jpg)

## 🎧MOSPA: Human Motion Generation Driven by Spatial Audio


### Images

![04bfcc043265b16e70ab84cb33ec1e519a383884b9cb0d56b0111417769fc386.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/04bfcc043265b16e70ab84cb33ec1e519a383884b9cb0d56b0111417769fc386.jpg)

![39652edb58958717fa84377bb7a30570cdf451d5c15e8c59a86e0650d104f2b9.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/39652edb58958717fa84377bb7a30570cdf451d5c15e8c59a86e0650d104f2b9.jpg)

![4be102f7f4d5460714acd11bb784dd7e11b8a632f4d7c5fd6125398ccf731ad1.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/4be102f7f4d5460714acd11bb784dd7e11b8a632f4d7c5fd6125398ccf731ad1.jpg)

![4ef3af64706b46ac003a2911e1ed9f9800b398ca23ffc288d325ffcd769937e8.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/4ef3af64706b46ac003a2911e1ed9f9800b398ca23ffc288d325ffcd769937e8.jpg)

![721f6585b0280eab01e30f255f6da7f83c0f20feda516e5e80baae35970a0b01.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/721f6585b0280eab01e30f255f6da7f83c0f20feda516e5e80baae35970a0b01.jpg)

![7b91a92c7bdc7b0e2fdb90ce1e1a44408b3890c20654bbeee5027a19d6524678.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/7b91a92c7bdc7b0e2fdb90ce1e1a44408b3890c20654bbeee5027a19d6524678.jpg)

![7ea51739f14308644fe80433f3f2ff01cf92017e45a393145b79adc852b8b20b.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/7ea51739f14308644fe80433f3f2ff01cf92017e45a393145b79adc852b8b20b.jpg)

![87d9534bfc005e4613658941e9e5e2081703bf4b9fe280c5be3e01cef31240ed.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/87d9534bfc005e4613658941e9e5e2081703bf4b9fe280c5be3e01cef31240ed.jpg)

![b3542cb9b262978ac6af6fdbb3e11f6b2fbc330abc1576ad78005badaa92bdca.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/b3542cb9b262978ac6af6fdbb3e11f6b2fbc330abc1576ad78005badaa92bdca.jpg)

![b71bf8e5727585f778c8155d23c4e242379e5544acaa66974d51776cf32a760f.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/b71bf8e5727585f778c8155d23c4e242379e5544acaa66974d51776cf32a760f.jpg)

![be04574c572a7d15fb8301a68120c1e7179e19a5927179c0d99bd1f8fd544959.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/be04574c572a7d15fb8301a68120c1e7179e19a5927179c0d99bd1f8fd544959.jpg)

![dca1ad7eca74002abaf5e58b7eec3552d3a3798fd0bdeab9f6a677f4e9133d1a.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/dca1ad7eca74002abaf5e58b7eec3552d3a3798fd0bdeab9f6a677f4e9133d1a.jpg)

![e6a787c3db16290c34f3f4a22f092529cd2c79b20821a4a36cdc9c7ca4f06552.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/e6a787c3db16290c34f3f4a22f092529cd2c79b20821a4a36cdc9c7ca4f06552.jpg)

![e90ddb2ddde15dde9cbdc326899bbfc2d988c8796a5f0bb2091ef819a5e1d899.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/e90ddb2ddde15dde9cbdc326899bbfc2d988c8796a5f0bb2091ef819a5e1d899.jpg)

![eb64ecc6cefe3f5c45b3fecb1d9a3f83ed1a72f9e67ce281f538dda5f364baac.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/images/eb64ecc6cefe3f5c45b3fecb1d9a3f83ed1a72f9e67ce281f538dda5f364baac.jpg)

### Tables

![99302029c2eedfe8e609ba71601cee1c6c00609930d5cc218892de535167aa8b.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/tables/99302029c2eedfe8e609ba71601cee1c6c00609930d5cc218892de535167aa8b.jpg)

![9ccf015b6c557ea27d104c3a7ff4361520fc85cd471c4ffa297f1c8f20562a38.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/tables/9ccf015b6c557ea27d104c3a7ff4361520fc85cd471c4ffa297f1c8f20562a38.jpg)

![a83743830d57961dc2b4a6dcfaa28c9e12a6750678276b09eff0ec36e9b25568.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/tables/a83743830d57961dc2b4a6dcfaa28c9e12a6750678276b09eff0ec36e9b25568.jpg)

![ee98be7826736087e2d12fb7c4497601a774301413426c89ad53e032ef486987.jpg](../nips_results/386_%F0%9F%8E%A7MOSPA_%20Human%20Motion%20Generation%20Driven%20by%20Spatial%20Audio/tables/ee98be7826736087e2d12fb7c4497601a774301413426c89ad53e032ef486987.jpg)

## Is the acquisition worth the cost? Surrogate losses for   Consistent Two-stage Classifiers


### Images

![00ccc280c6bd1a552b72e305677661fb8605019d0a8a1e47d1252982b2979bee.jpg](../nips_results/387_Is%20the%20acquisition%20worth%20the%20cost_%20Surrogate%20losses%20for%20%20%20Consistent%20Two-stage%20Classifiers/images/00ccc280c6bd1a552b72e305677661fb8605019d0a8a1e47d1252982b2979bee.jpg)

![1a89bb20585104dc56c636be5902ce3df652543d1c556c4e62b37131960443b8.jpg](../nips_results/387_Is%20the%20acquisition%20worth%20the%20cost_%20Surrogate%20losses%20for%20%20%20Consistent%20Two-stage%20Classifiers/images/1a89bb20585104dc56c636be5902ce3df652543d1c556c4e62b37131960443b8.jpg)

![298c09f298b48d76498eb51bf1bc68e3f408fd11e0db3cbe0b90e1c45c091961.jpg](../nips_results/387_Is%20the%20acquisition%20worth%20the%20cost_%20Surrogate%20losses%20for%20%20%20Consistent%20Two-stage%20Classifiers/images/298c09f298b48d76498eb51bf1bc68e3f408fd11e0db3cbe0b90e1c45c091961.jpg)

![bf7e79db88372cc8cfc5264ad647bb3c6dfc9a6544276036e649f194deb2dc89.jpg](../nips_results/387_Is%20the%20acquisition%20worth%20the%20cost_%20Surrogate%20losses%20for%20%20%20Consistent%20Two-stage%20Classifiers/images/bf7e79db88372cc8cfc5264ad647bb3c6dfc9a6544276036e649f194deb2dc89.jpg)

![ca57812d2aa102965554b7a3fa6b07801268d9e29894c7ce099cd89472098be8.jpg](../nips_results/387_Is%20the%20acquisition%20worth%20the%20cost_%20Surrogate%20losses%20for%20%20%20Consistent%20Two-stage%20Classifiers/images/ca57812d2aa102965554b7a3fa6b07801268d9e29894c7ce099cd89472098be8.jpg)

![d09819a6db92853c431908410bf51535637af8e19c641fd7e1c71fd8e446e5b6.jpg](../nips_results/387_Is%20the%20acquisition%20worth%20the%20cost_%20Surrogate%20losses%20for%20%20%20Consistent%20Two-stage%20Classifiers/images/d09819a6db92853c431908410bf51535637af8e19c641fd7e1c71fd8e446e5b6.jpg)

### Tables

![0e2a3b1db3de6b3be41ae2561a96d112d8704924c5a575a5198ce507e4164d4a.jpg](../nips_results/387_Is%20the%20acquisition%20worth%20the%20cost_%20Surrogate%20losses%20for%20%20%20Consistent%20Two-stage%20Classifiers/tables/0e2a3b1db3de6b3be41ae2561a96d112d8704924c5a575a5198ce507e4164d4a.jpg)

## Broken Tokens? Your Language Model can Secretly Handle Non-Canonical Tokenizations


### Images

![3c08ad241ab09360c29228e1471ae4407148a1bf19d19af006024e01d1c609d5.jpg](../nips_results/388_Broken%20Tokens_%20Your%20Language%20Model%20can%20Secretly%20Handle%20Non-Canonical%20Tokenizations/images/3c08ad241ab09360c29228e1471ae4407148a1bf19d19af006024e01d1c609d5.jpg)

![840194bd4b28530c20f098b93599fd3a8411c21136a48e29447ef25192c9d6df.jpg](../nips_results/388_Broken%20Tokens_%20Your%20Language%20Model%20can%20Secretly%20Handle%20Non-Canonical%20Tokenizations/images/840194bd4b28530c20f098b93599fd3a8411c21136a48e29447ef25192c9d6df.jpg)

![b4f99bb8c81e75dd73391fc2bd3546a9514a46e3dda7c27d85802659295c1de8.jpg](../nips_results/388_Broken%20Tokens_%20Your%20Language%20Model%20can%20Secretly%20Handle%20Non-Canonical%20Tokenizations/images/b4f99bb8c81e75dd73391fc2bd3546a9514a46e3dda7c27d85802659295c1de8.jpg)

![c86ec472df3f09a2fa354aa543ef1da900e27a50093a78c74af31add13fdd3b0.jpg](../nips_results/388_Broken%20Tokens_%20Your%20Language%20Model%20can%20Secretly%20Handle%20Non-Canonical%20Tokenizations/images/c86ec472df3f09a2fa354aa543ef1da900e27a50093a78c74af31add13fdd3b0.jpg)

### Tables

![018cb7d617f7c548aa91568fed935759f273d4d1061ba48ab2728102f5027d06.jpg](../nips_results/388_Broken%20Tokens_%20Your%20Language%20Model%20can%20Secretly%20Handle%20Non-Canonical%20Tokenizations/tables/018cb7d617f7c548aa91568fed935759f273d4d1061ba48ab2728102f5027d06.jpg)

![281d44a2da0178362fd3508260530b66c2bcad7d4db8776a227d5c74dce17e4d.jpg](../nips_results/388_Broken%20Tokens_%20Your%20Language%20Model%20can%20Secretly%20Handle%20Non-Canonical%20Tokenizations/tables/281d44a2da0178362fd3508260530b66c2bcad7d4db8776a227d5c74dce17e4d.jpg)

![4aee04270af3cb14fe0d1057f8a344705ee2507ed46497655b13e3078dfb3916.jpg](../nips_results/388_Broken%20Tokens_%20Your%20Language%20Model%20can%20Secretly%20Handle%20Non-Canonical%20Tokenizations/tables/4aee04270af3cb14fe0d1057f8a344705ee2507ed46497655b13e3078dfb3916.jpg)

![76d7526a3ec5bd28f7086cb12d11b15bad3c84d4da3b23e5c561a047df8838d7.jpg](../nips_results/388_Broken%20Tokens_%20Your%20Language%20Model%20can%20Secretly%20Handle%20Non-Canonical%20Tokenizations/tables/76d7526a3ec5bd28f7086cb12d11b15bad3c84d4da3b23e5c561a047df8838d7.jpg)

![7d4a33a72ee9a8e9ac53d7bea6fa805f635e9d67f3ea7dc7e94d52cbb585a5db.jpg](../nips_results/388_Broken%20Tokens_%20Your%20Language%20Model%20can%20Secretly%20Handle%20Non-Canonical%20Tokenizations/tables/7d4a33a72ee9a8e9ac53d7bea6fa805f635e9d67f3ea7dc7e94d52cbb585a5db.jpg)

![9764e1daa21e8dc6c7435e265f9ffdf8ff1a4ebc2fa6bc2d65a4084b14825b64.jpg](../nips_results/388_Broken%20Tokens_%20Your%20Language%20Model%20can%20Secretly%20Handle%20Non-Canonical%20Tokenizations/tables/9764e1daa21e8dc6c7435e265f9ffdf8ff1a4ebc2fa6bc2d65a4084b14825b64.jpg)

![dfa0cecd9bc2237e1f2ee2561545ac790a6b990849bfd20dd7a73b7153f7880e.jpg](../nips_results/388_Broken%20Tokens_%20Your%20Language%20Model%20can%20Secretly%20Handle%20Non-Canonical%20Tokenizations/tables/dfa0cecd9bc2237e1f2ee2561545ac790a6b990849bfd20dd7a73b7153f7880e.jpg)

## InstructHOI: Context-Aware Instruction for Multi-Modal Reasoning in Human-Object Interaction Detection


### Images

![47820d9eee3404e4e892ac2af80f4f4e6f11d7cc94613db114017ca216b9b66f.jpg](../nips_results/389_InstructHOI_%20Context-Aware%20Instruction%20for%20Multi-Modal%20Reasoning%20in%20Human-Object%20Interaction%20Detecti/images/47820d9eee3404e4e892ac2af80f4f4e6f11d7cc94613db114017ca216b9b66f.jpg)

![49b3a4855e2b95cd68118a8fa09d6d60f2a39b103eb6cfc07e3066ca6c243ec7.jpg](../nips_results/389_InstructHOI_%20Context-Aware%20Instruction%20for%20Multi-Modal%20Reasoning%20in%20Human-Object%20Interaction%20Detecti/images/49b3a4855e2b95cd68118a8fa09d6d60f2a39b103eb6cfc07e3066ca6c243ec7.jpg)

![bbe9121c37764a60a8f84d808d0da745ce4d8d576b9628d22742cc5014c16d91.jpg](../nips_results/389_InstructHOI_%20Context-Aware%20Instruction%20for%20Multi-Modal%20Reasoning%20in%20Human-Object%20Interaction%20Detecti/images/bbe9121c37764a60a8f84d808d0da745ce4d8d576b9628d22742cc5014c16d91.jpg)

### Tables

![18af8827d75959a078d0068ce6abd1c4c6dbb4fbe33cdbac0719850fabaf3086.jpg](../nips_results/389_InstructHOI_%20Context-Aware%20Instruction%20for%20Multi-Modal%20Reasoning%20in%20Human-Object%20Interaction%20Detecti/tables/18af8827d75959a078d0068ce6abd1c4c6dbb4fbe33cdbac0719850fabaf3086.jpg)

![48fa59eb2637b659afa47a7e98087ff6f649c44cd7f671fc3f16a7d4835b7f83.jpg](../nips_results/389_InstructHOI_%20Context-Aware%20Instruction%20for%20Multi-Modal%20Reasoning%20in%20Human-Object%20Interaction%20Detecti/tables/48fa59eb2637b659afa47a7e98087ff6f649c44cd7f671fc3f16a7d4835b7f83.jpg)

![a198d4f1be3f96d83a60d5e30c29b4efe36654cfcc21d7c4879b5f23960ef690.jpg](../nips_results/389_InstructHOI_%20Context-Aware%20Instruction%20for%20Multi-Modal%20Reasoning%20in%20Human-Object%20Interaction%20Detecti/tables/a198d4f1be3f96d83a60d5e30c29b4efe36654cfcc21d7c4879b5f23960ef690.jpg)

![b28e82b12277da8f38b29f7c5a03ac514a5c836cd0a7cf72a0bd57866d34c915.jpg](../nips_results/389_InstructHOI_%20Context-Aware%20Instruction%20for%20Multi-Modal%20Reasoning%20in%20Human-Object%20Interaction%20Detecti/tables/b28e82b12277da8f38b29f7c5a03ac514a5c836cd0a7cf72a0bd57866d34c915.jpg)

![d3edb718e662f1be614b3bc9a611b7a9d08e3eb060bdced69b13eb7c70e371bc.jpg](../nips_results/389_InstructHOI_%20Context-Aware%20Instruction%20for%20Multi-Modal%20Reasoning%20in%20Human-Object%20Interaction%20Detecti/tables/d3edb718e662f1be614b3bc9a611b7a9d08e3eb060bdced69b13eb7c70e371bc.jpg)

## Thoughts Are All Over the Place: On the Underthinking of Long Reasoning Models


### Images

![274947b5524808f4cd63c3f927a17ce53859fbaeb408f9df7028eab4360fcc01.jpg](../nips_results/390_Thoughts%20Are%20All%20Over%20the%20Place_%20On%20the%20Underthinking%20of%20Long%20Reasoning%20Models/images/274947b5524808f4cd63c3f927a17ce53859fbaeb408f9df7028eab4360fcc01.jpg)

![387f5940dba40e50b2d6ed53a752779159a5772efbb277230b45816b32fdd626.jpg](../nips_results/390_Thoughts%20Are%20All%20Over%20the%20Place_%20On%20the%20Underthinking%20of%20Long%20Reasoning%20Models/images/387f5940dba40e50b2d6ed53a752779159a5772efbb277230b45816b32fdd626.jpg)

![98a1aff0a2ec42a2106b4c33ba873ab432eb0b56784898ce1ba3cb84ac6dfb68.jpg](../nips_results/390_Thoughts%20Are%20All%20Over%20the%20Place_%20On%20the%20Underthinking%20of%20Long%20Reasoning%20Models/images/98a1aff0a2ec42a2106b4c33ba873ab432eb0b56784898ce1ba3cb84ac6dfb68.jpg)

![b678ef16ecf1e01c86c957e92c0cbc92927ff7a651cbca3af9a21f163a3349c3.jpg](../nips_results/390_Thoughts%20Are%20All%20Over%20the%20Place_%20On%20the%20Underthinking%20of%20Long%20Reasoning%20Models/images/b678ef16ecf1e01c86c957e92c0cbc92927ff7a651cbca3af9a21f163a3349c3.jpg)

![c3266b29da143215ddb92e776997953ea9d14849ce021de1087a5560eb2e4df7.jpg](../nips_results/390_Thoughts%20Are%20All%20Over%20the%20Place_%20On%20the%20Underthinking%20of%20Long%20Reasoning%20Models/images/c3266b29da143215ddb92e776997953ea9d14849ce021de1087a5560eb2e4df7.jpg)

### Tables

![0f91c595752bc9a5f8331addba5820059fcd0d848fff1996a4e6cb9e41430f23.jpg](../nips_results/390_Thoughts%20Are%20All%20Over%20the%20Place_%20On%20the%20Underthinking%20of%20Long%20Reasoning%20Models/tables/0f91c595752bc9a5f8331addba5820059fcd0d848fff1996a4e6cb9e41430f23.jpg)

![808a1bbfca2003f49022d5c38d698ad35a5819cea5421ba8e7256235264e6c2a.jpg](../nips_results/390_Thoughts%20Are%20All%20Over%20the%20Place_%20On%20the%20Underthinking%20of%20Long%20Reasoning%20Models/tables/808a1bbfca2003f49022d5c38d698ad35a5819cea5421ba8e7256235264e6c2a.jpg)

![ae44d9480a40a36b128fbb7b120b984d32b65cee81acf21d62d0e796db6eb6cc.jpg](../nips_results/390_Thoughts%20Are%20All%20Over%20the%20Place_%20On%20the%20Underthinking%20of%20Long%20Reasoning%20Models/tables/ae44d9480a40a36b128fbb7b120b984d32b65cee81acf21d62d0e796db6eb6cc.jpg)

![cffc94d567e543dd13e03d5ff4cf8602817a93b609ee51ae97216f8c951fbb13.jpg](../nips_results/390_Thoughts%20Are%20All%20Over%20the%20Place_%20On%20the%20Underthinking%20of%20Long%20Reasoning%20Models/tables/cffc94d567e543dd13e03d5ff4cf8602817a93b609ee51ae97216f8c951fbb13.jpg)

![d9c51f606f04b1566503775041ffb76f834eb16ff8bc7e6c06b62b94c48727ce.jpg](../nips_results/390_Thoughts%20Are%20All%20Over%20the%20Place_%20On%20the%20Underthinking%20of%20Long%20Reasoning%20Models/tables/d9c51f606f04b1566503775041ffb76f834eb16ff8bc7e6c06b62b94c48727ce.jpg)

![ef8595c27a3410608762f9769710f4d197254384adccbdbc548b7c86d0574a69.jpg](../nips_results/390_Thoughts%20Are%20All%20Over%20the%20Place_%20On%20the%20Underthinking%20of%20Long%20Reasoning%20Models/tables/ef8595c27a3410608762f9769710f4d197254384adccbdbc548b7c86d0574a69.jpg)

## Compositional Neural Network Verification via Assume-Guarantee Reasoning


### Images

![11e265e85818389e7f1a9e8f0fe53680d063ea283f01d150b7aee242004cda03.jpg](../nips_results/391_Compositional%20Neural%20Network%20Verification%20via%20Assume-Guarantee%20Reasoning/images/11e265e85818389e7f1a9e8f0fe53680d063ea283f01d150b7aee242004cda03.jpg)

![56f3376d80b2850ac61a754dab806c9d99f9e8ba325c4acaec779264f5899f77.jpg](../nips_results/391_Compositional%20Neural%20Network%20Verification%20via%20Assume-Guarantee%20Reasoning/images/56f3376d80b2850ac61a754dab806c9d99f9e8ba325c4acaec779264f5899f77.jpg)

![ad465cbb2aa5f301103928a57c0105ea4c59128c1557d5e0ed3c86449187ae80.jpg](../nips_results/391_Compositional%20Neural%20Network%20Verification%20via%20Assume-Guarantee%20Reasoning/images/ad465cbb2aa5f301103928a57c0105ea4c59128c1557d5e0ed3c86449187ae80.jpg)

![baec0b9aaf2023063b526bed7968af633c2a51bb59efb7ce60ad0afe18f0b0de.jpg](../nips_results/391_Compositional%20Neural%20Network%20Verification%20via%20Assume-Guarantee%20Reasoning/images/baec0b9aaf2023063b526bed7968af633c2a51bb59efb7ce60ad0afe18f0b0de.jpg)

![f436cd7b390b491c0688fe04422835487db80ede1c0e5aba6f9887930273d236.jpg](../nips_results/391_Compositional%20Neural%20Network%20Verification%20via%20Assume-Guarantee%20Reasoning/images/f436cd7b390b491c0688fe04422835487db80ede1c0e5aba6f9887930273d236.jpg)

### Tables

![11e52a8b6f06ec6628a3804b7875f5996dc4980e85e78545d408ee9d8c54c9fa.jpg](../nips_results/391_Compositional%20Neural%20Network%20Verification%20via%20Assume-Guarantee%20Reasoning/tables/11e52a8b6f06ec6628a3804b7875f5996dc4980e85e78545d408ee9d8c54c9fa.jpg)

![1ccfbefe0c12b85b4697c5f6bc11c5ed18b3e4d2a6b670b14c86dddc28072a33.jpg](../nips_results/391_Compositional%20Neural%20Network%20Verification%20via%20Assume-Guarantee%20Reasoning/tables/1ccfbefe0c12b85b4697c5f6bc11c5ed18b3e4d2a6b670b14c86dddc28072a33.jpg)

![7515df24deeba197466ba62213bc409c385aa3b49a43c609088692d6abf6ddb7.jpg](../nips_results/391_Compositional%20Neural%20Network%20Verification%20via%20Assume-Guarantee%20Reasoning/tables/7515df24deeba197466ba62213bc409c385aa3b49a43c609088692d6abf6ddb7.jpg)

![fb754980df1c7e1f4a2bc2091d6b1478d42225a848b72dd4f8e7d0951f656fcc.jpg](../nips_results/391_Compositional%20Neural%20Network%20Verification%20via%20Assume-Guarantee%20Reasoning/tables/fb754980df1c7e1f4a2bc2091d6b1478d42225a848b72dd4f8e7d0951f656fcc.jpg)

## Puppeteer: Rig and Animate Your 3D Models


### Images

![0a2deb60c91c0c1b33b4057c44035d8e711e2159149a00cd424dddb1f5f22817.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/0a2deb60c91c0c1b33b4057c44035d8e711e2159149a00cd424dddb1f5f22817.jpg)

![1afb37c61f76f73116b9fefb04eba1b5150e76ab17c85cfe11b128a3db82ffbe.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/1afb37c61f76f73116b9fefb04eba1b5150e76ab17c85cfe11b128a3db82ffbe.jpg)

![3510ca0ab90ed589f3a62629697e6137cee13f692c8e73bb5460fd5878a498b9.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/3510ca0ab90ed589f3a62629697e6137cee13f692c8e73bb5460fd5878a498b9.jpg)

![377148fa8a8d5c8f9363f8c8cec11b797453e8ea7959f9c53eed8e942aa21907.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/377148fa8a8d5c8f9363f8c8cec11b797453e8ea7959f9c53eed8e942aa21907.jpg)

![5268ab47b406173c9934e08b4b5b54fcb8f662ac5e9cd81b9aeedf3cf0a59bc5.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/5268ab47b406173c9934e08b4b5b54fcb8f662ac5e9cd81b9aeedf3cf0a59bc5.jpg)

![611142cbdb76773e7f29ab7de07d763cfa234da5bb2d4d60027fc42ac34643ed.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/611142cbdb76773e7f29ab7de07d763cfa234da5bb2d4d60027fc42ac34643ed.jpg)

![631153e3c17faa17aa2089fed33ea03d001df65e942cd6da912cbe86e4bd3fb0.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/631153e3c17faa17aa2089fed33ea03d001df65e942cd6da912cbe86e4bd3fb0.jpg)

![63d10f5d15193efab47eafdbd0b540d04a88b0775bc343c05af96182fed367b7.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/63d10f5d15193efab47eafdbd0b540d04a88b0775bc343c05af96182fed367b7.jpg)

![710e3ed9be4c0ff60e6ea0430bcbbd81dc6bd12fc19210ff5312c9ee31c61dc4.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/710e3ed9be4c0ff60e6ea0430bcbbd81dc6bd12fc19210ff5312c9ee31c61dc4.jpg)

![8966496b82c040f6c43c4fc8ba10f478eb1777760e17d072f80c19ac7c73a018.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/8966496b82c040f6c43c4fc8ba10f478eb1777760e17d072f80c19ac7c73a018.jpg)

![8c52ecaa4b9e4145fb6adfc5ceb5a0daa50fcc79837534ea2fa36b9b4f6dcfe1.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/8c52ecaa4b9e4145fb6adfc5ceb5a0daa50fcc79837534ea2fa36b9b4f6dcfe1.jpg)

![caa7d7a7bc3eed0ec59074a9ec332f6e46a69b1263056cc4825bc587573affd5.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/caa7d7a7bc3eed0ec59074a9ec332f6e46a69b1263056cc4825bc587573affd5.jpg)

![d4c099a68e8a14898becb6c6f3d2df004293a4db3338922db6e4101400dd9ad6.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/d4c099a68e8a14898becb6c6f3d2df004293a4db3338922db6e4101400dd9ad6.jpg)

![f6e4ffedcb8ab59293a9d9749057b8eaaf16c143319694ef25b265db8b40533f.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/images/f6e4ffedcb8ab59293a9d9749057b8eaaf16c143319694ef25b265db8b40533f.jpg)

### Tables

![46687ac472c5cf24e9c5d59451222875c9d910ddadccc7b3865521682467c485.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/tables/46687ac472c5cf24e9c5d59451222875c9d910ddadccc7b3865521682467c485.jpg)

![615805543bd20629f8822d7a8e5ec632e5ddaf54e6501a197ce00a15d4716914.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/tables/615805543bd20629f8822d7a8e5ec632e5ddaf54e6501a197ce00a15d4716914.jpg)

![7c381f3ac0b3e1cdd4ceb8ffabeadb180e72008bfe05cb9be3bedd311c3fcadb.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/tables/7c381f3ac0b3e1cdd4ceb8ffabeadb180e72008bfe05cb9be3bedd311c3fcadb.jpg)

![7dfabbf022b6718f7a1a134827b14d4a992f097b4a66ed25ca11682d4e9e5a2a.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/tables/7dfabbf022b6718f7a1a134827b14d4a992f097b4a66ed25ca11682d4e9e5a2a.jpg)

![ab9c8de113a55c10c63025fb7e71f2768c9cb12c0b1ce323b8ff3bbd7d484fc0.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/tables/ab9c8de113a55c10c63025fb7e71f2768c9cb12c0b1ce323b8ff3bbd7d484fc0.jpg)

![cd7a80e0eb987ef2f3748f618fae335203d31c47d77ac687e1991254d0c942ed.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/tables/cd7a80e0eb987ef2f3748f618fae335203d31c47d77ac687e1991254d0c942ed.jpg)

![ddd9e5e60987942b6a97ccd346b8aa08a2d287c0fe0171aa4fb2c196f5b93453.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/tables/ddd9e5e60987942b6a97ccd346b8aa08a2d287c0fe0171aa4fb2c196f5b93453.jpg)

![deb74554173666fdf98f61b01edee398bdc2cdea74728410ed58f91d2cd22216.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/tables/deb74554173666fdf98f61b01edee398bdc2cdea74728410ed58f91d2cd22216.jpg)

![e2ede4837980cc111ce51237c5300a0d3b1d6fce24c18507713602e942b75b14.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/tables/e2ede4837980cc111ce51237c5300a0d3b1d6fce24c18507713602e942b75b14.jpg)

![ec033eaf2b270865f1eb7a69787d48dd68ba23a87b0b9a03f04b8fd0cd480f54.jpg](../nips_results/392_Puppeteer_%20Rig%20and%20Animate%20Your%203D%20Models/tables/ec033eaf2b270865f1eb7a69787d48dd68ba23a87b0b9a03f04b8fd0cd480f54.jpg)

## Bridging Theory and Practice in Link Representation with Graph Neural Networks


### Images

![208a8e243c9708864dab580e96b7c98648917057d7c8340f58bc58b294e2d76e.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/images/208a8e243c9708864dab580e96b7c98648917057d7c8340f58bc58b294e2d76e.jpg)

![78096ded57ffbaf2b1049c0522146b66624d9bfb4b7f6f68842353db29a9d398.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/images/78096ded57ffbaf2b1049c0522146b66624d9bfb4b7f6f68842353db29a9d398.jpg)

### Tables

![06396c005bda25227f9235a8246d6b9f1871efaae5b58a22959494844bb97f87.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/06396c005bda25227f9235a8246d6b9f1871efaae5b58a22959494844bb97f87.jpg)

![0c8bfbfa8a328658506513460b98985dee2354148eec7d28566826f40437ac50.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/0c8bfbfa8a328658506513460b98985dee2354148eec7d28566826f40437ac50.jpg)

![0dadca31dd76ce55cdc944befe4b710da757133b7cb351155106fb4eb71f33a0.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/0dadca31dd76ce55cdc944befe4b710da757133b7cb351155106fb4eb71f33a0.jpg)

![1334cbe1b819fa16eb0bcf6d34ca026bf261be927c123471f5fb8f18d7189835.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/1334cbe1b819fa16eb0bcf6d34ca026bf261be927c123471f5fb8f18d7189835.jpg)

![170a7c6952dec190ab76de09f25fd331c3ba8f04731b706b7c6d9b97badc9d3f.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/170a7c6952dec190ab76de09f25fd331c3ba8f04731b706b7c6d9b97badc9d3f.jpg)

![3726566ef008b9f4d2f5f9996e4c65bb131998b1dedf8b9d0fe713b583190cc1.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/3726566ef008b9f4d2f5f9996e4c65bb131998b1dedf8b9d0fe713b583190cc1.jpg)

![4d5fc91d9f120dc2ea4bd0d7f95aa44456acdb472ef5913e3fa5c2dcec57eb94.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/4d5fc91d9f120dc2ea4bd0d7f95aa44456acdb472ef5913e3fa5c2dcec57eb94.jpg)

![4ea41e41f785d57123d86815300ba72e7bd43922177ab675353485072595c8c9.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/4ea41e41f785d57123d86815300ba72e7bd43922177ab675353485072595c8c9.jpg)

![55ba36a503a5171d94b1338c0716c6891ca3af78cc2b553ed1968cbbc31d6641.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/55ba36a503a5171d94b1338c0716c6891ca3af78cc2b553ed1968cbbc31d6641.jpg)

![5e7f4a4ef059bec08d9fe7569a4f5ec2a0d6a89bfae4b1dce090d39ddcf74259.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/5e7f4a4ef059bec08d9fe7569a4f5ec2a0d6a89bfae4b1dce090d39ddcf74259.jpg)

![68cd5b857a5e996bb28839d3728506df9e83ad4dde70d3aa4bf4d65ea2ef9e20.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/68cd5b857a5e996bb28839d3728506df9e83ad4dde70d3aa4bf4d65ea2ef9e20.jpg)

![7439499d54f90fc4349dc3f474a6037e9eeb00c4bea47f001d1af61b887213ba.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/7439499d54f90fc4349dc3f474a6037e9eeb00c4bea47f001d1af61b887213ba.jpg)

![8664bd1d3b3ecd46443792d2b3504edfb37a4d573f510acd0e0295ea647b439d.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/8664bd1d3b3ecd46443792d2b3504edfb37a4d573f510acd0e0295ea647b439d.jpg)

![ba185ed443284aaf7075a27137b2dd58a5ad32d68fdb317cef7b461d369835a0.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/ba185ed443284aaf7075a27137b2dd58a5ad32d68fdb317cef7b461d369835a0.jpg)

![dcf8e73e030e372af0113a31a5004303e64dddfa62f7f75fd4c62c9a6c6b5a60.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/dcf8e73e030e372af0113a31a5004303e64dddfa62f7f75fd4c62c9a6c6b5a60.jpg)

![e93248b10700b9fbc2e95275378d3eab70ea38fa53190d4f5fd28294b863f86d.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/e93248b10700b9fbc2e95275378d3eab70ea38fa53190d4f5fd28294b863f86d.jpg)

![f266e3b58152cfc97606279eb297841b1a8ee73dcd823de4b485ff13b8cb3123.jpg](../nips_results/393_Bridging%20Theory%20and%20Practice%20in%20Link%20Representation%20with%20Graph%20Neural%20Networks/tables/f266e3b58152cfc97606279eb297841b1a8ee73dcd823de4b485ff13b8cb3123.jpg)

## Unbiased Prototype Consistency Learning for Multi-Modal and Multi-Task Object Re-Identification


### Images

![0dc93cfb9487f350097af5f57ff2162af8e8e57e3ffd04ffde5149f020c948ac.jpg](../nips_results/394_Unbiased%20Prototype%20Consistency%20Learning%20for%20Multi-Modal%20and%20Multi-Task%20Object%20Re-Identification/images/0dc93cfb9487f350097af5f57ff2162af8e8e57e3ffd04ffde5149f020c948ac.jpg)

![3c72a9b7a1d390a1fd3aeba4e01d9430f94a8653cffe4b5a9ccca9d3419f0765.jpg](../nips_results/394_Unbiased%20Prototype%20Consistency%20Learning%20for%20Multi-Modal%20and%20Multi-Task%20Object%20Re-Identification/images/3c72a9b7a1d390a1fd3aeba4e01d9430f94a8653cffe4b5a9ccca9d3419f0765.jpg)

![9eea3fa8b5882ebd494ecf96d0fbd150c1dffce0525f037f3a6f7e5e66956511.jpg](../nips_results/394_Unbiased%20Prototype%20Consistency%20Learning%20for%20Multi-Modal%20and%20Multi-Task%20Object%20Re-Identification/images/9eea3fa8b5882ebd494ecf96d0fbd150c1dffce0525f037f3a6f7e5e66956511.jpg)

![d40bbfab0bf58ded40ed7bfeb11a56bed2db9124f8418097d2ff106eaee47d53.jpg](../nips_results/394_Unbiased%20Prototype%20Consistency%20Learning%20for%20Multi-Modal%20and%20Multi-Task%20Object%20Re-Identification/images/d40bbfab0bf58ded40ed7bfeb11a56bed2db9124f8418097d2ff106eaee47d53.jpg)

### Tables

![446fb89b7924c2c73c87bf5a6cb94c6c0fcab2d98924e6f08643480e0f4e76c7.jpg](../nips_results/394_Unbiased%20Prototype%20Consistency%20Learning%20for%20Multi-Modal%20and%20Multi-Task%20Object%20Re-Identification/tables/446fb89b7924c2c73c87bf5a6cb94c6c0fcab2d98924e6f08643480e0f4e76c7.jpg)

![4feff2c6afe9a693a810eefab9a0cbcd2f1240c79b7121f56599f0eafc6872fd.jpg](../nips_results/394_Unbiased%20Prototype%20Consistency%20Learning%20for%20Multi-Modal%20and%20Multi-Task%20Object%20Re-Identification/tables/4feff2c6afe9a693a810eefab9a0cbcd2f1240c79b7121f56599f0eafc6872fd.jpg)

![cb579dafe9db4ee2661f546bd37aa3ff37aa25671578ee18a7500a8fc32d31e7.jpg](../nips_results/394_Unbiased%20Prototype%20Consistency%20Learning%20for%20Multi-Modal%20and%20Multi-Task%20Object%20Re-Identification/tables/cb579dafe9db4ee2661f546bd37aa3ff37aa25671578ee18a7500a8fc32d31e7.jpg)

![f0e08d8c5286f38e792d15b3939204124831dcb78936ed81883094533b1b21a6.jpg](../nips_results/394_Unbiased%20Prototype%20Consistency%20Learning%20for%20Multi-Modal%20and%20Multi-Task%20Object%20Re-Identification/tables/f0e08d8c5286f38e792d15b3939204124831dcb78936ed81883094533b1b21a6.jpg)

## Head Pursuit: Probing Attention Specialization in Multimodal Transformers


### Images

![2b3ebba18c7403c603faf3e51ae0a6fcbceb6e52480b2f27c8c0e47c3f7a4ab8.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/images/2b3ebba18c7403c603faf3e51ae0a6fcbceb6e52480b2f27c8c0e47c3f7a4ab8.jpg)

![35f8841d9bfdf17dee7bbbddd9cd5b38fbcb712795df27d65951af6e831b51ce.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/images/35f8841d9bfdf17dee7bbbddd9cd5b38fbcb712795df27d65951af6e831b51ce.jpg)

![53fe426561bb11e8838d8f675e2b23c46c37f9e54c542596e34cc468423bd16e.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/images/53fe426561bb11e8838d8f675e2b23c46c37f9e54c542596e34cc468423bd16e.jpg)

![7fe948f33c65562b66a7ea768870564fb3883e7f48d960d2a3ddd6b3e81742c5.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/images/7fe948f33c65562b66a7ea768870564fb3883e7f48d960d2a3ddd6b3e81742c5.jpg)

![86284867fe1986078894565c8225bc5cbeebed96477433466b5430addfa920d7.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/images/86284867fe1986078894565c8225bc5cbeebed96477433466b5430addfa920d7.jpg)

![c6f0f64e4c7519f59a3bb4a2ec45bc2decaaba1c5fc315822dfbf9c2369ae7d2.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/images/c6f0f64e4c7519f59a3bb4a2ec45bc2decaaba1c5fc315822dfbf9c2369ae7d2.jpg)

![c931cf30a3a0ad6d3a3851882a15703aebcb2908edbcdedf5cf190608e8f4f01.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/images/c931cf30a3a0ad6d3a3851882a15703aebcb2908edbcdedf5cf190608e8f4f01.jpg)

![cbee8f21ae45eb93bd81b08a98d96e2c85aec459c482ebc654432166ff009a5e.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/images/cbee8f21ae45eb93bd81b08a98d96e2c85aec459c482ebc654432166ff009a5e.jpg)

![e12849c4999b1e74a87eea626b339f91b03953fd322de0bbc64e515f28ebd65c.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/images/e12849c4999b1e74a87eea626b339f91b03953fd322de0bbc64e515f28ebd65c.jpg)

![f6e64dd0ce8b5cdd6418a44d6d2dcf331d21f3937140e77ae8fa687e8cc4c328.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/images/f6e64dd0ce8b5cdd6418a44d6d2dcf331d21f3937140e77ae8fa687e8cc4c328.jpg)

![feab5c4215165f609399901b9ea70ab596f359686a85adc03dff7e81ab5b7633.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/images/feab5c4215165f609399901b9ea70ab596f359686a85adc03dff7e81ab5b7633.jpg)

### Tables

![01a0bde4a0e01de02d8fd50e3e8a0e2797f1d7771fe003dab2d5b0633e44093f.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/01a0bde4a0e01de02d8fd50e3e8a0e2797f1d7771fe003dab2d5b0633e44093f.jpg)

![0692ea08067acaaf3d604ce4191c283fe93b67085942eaccaa1c85b946d6d4e1.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/0692ea08067acaaf3d604ce4191c283fe93b67085942eaccaa1c85b946d6d4e1.jpg)

![1273c4529040b5f7e83250350f64e7f73450ccba41730994972b7dcb2b5d1ef9.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/1273c4529040b5f7e83250350f64e7f73450ccba41730994972b7dcb2b5d1ef9.jpg)

![298cda0d7ea2b1c1ee8de15be533e009f3ce246a23a8ebf3c43d1f8f92519404.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/298cda0d7ea2b1c1ee8de15be533e009f3ce246a23a8ebf3c43d1f8f92519404.jpg)

![2bd9d9ef027c078ac50cc08e41302b7dadde150694b81a409426bf17f1cd1475.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/2bd9d9ef027c078ac50cc08e41302b7dadde150694b81a409426bf17f1cd1475.jpg)

![2d39c7714e257a3a1622212da8ed6c734d25735467c1a5291ff39615d2c82d6b.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/2d39c7714e257a3a1622212da8ed6c734d25735467c1a5291ff39615d2c82d6b.jpg)

![2e0ab485e4554fb20cd43fad0dcdf76425469572e729a8b04b4e5228e130b606.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/2e0ab485e4554fb20cd43fad0dcdf76425469572e729a8b04b4e5228e130b606.jpg)

![3d4a6e53251e1744e38a7023e7bc6c1864a890b79423fbb8c030354b359fd5b6.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/3d4a6e53251e1744e38a7023e7bc6c1864a890b79423fbb8c030354b359fd5b6.jpg)

![3ecb9a17f1b28714a59cb8bc28ab9663855129b6c2c8fd6c2a9419a2604871c1.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/3ecb9a17f1b28714a59cb8bc28ab9663855129b6c2c8fd6c2a9419a2604871c1.jpg)

![61f6dea7ff97f842cc6c8dcf23edc6b596cdeca780ce6ac9214bd986c5a4e9d5.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/61f6dea7ff97f842cc6c8dcf23edc6b596cdeca780ce6ac9214bd986c5a4e9d5.jpg)

![84992043294cd3cfe06e927e84e1c21b3578ee078df6a7d6f6973cee708ec002.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/84992043294cd3cfe06e927e84e1c21b3578ee078df6a7d6f6973cee708ec002.jpg)

![9ad937f0ad9e5f9ebbf11f9f410117f9b816a4c1201bdb51ef720b4e62ab6a4f.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/9ad937f0ad9e5f9ebbf11f9f410117f9b816a4c1201bdb51ef720b4e62ab6a4f.jpg)

![aaa835c67a65b7a29aceb922f97fe3c9e01c43e4cfd2c116b132f1ef1d56407e.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/aaa835c67a65b7a29aceb922f97fe3c9e01c43e4cfd2c116b132f1ef1d56407e.jpg)

![b28631c76ca7cc287b922458fd9a75d178b59e1f4b0100e6eafe376d28f1070b.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/b28631c76ca7cc287b922458fd9a75d178b59e1f4b0100e6eafe376d28f1070b.jpg)

![d155898b0a4e20594ba8d6d85bb822b31a928b05b05192818f5b0c9160aa0ee7.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/d155898b0a4e20594ba8d6d85bb822b31a928b05b05192818f5b0c9160aa0ee7.jpg)

![e607531e2dde7a151eb3187f5bcc6e03ff48453b7f4fc1a16a06981d22506f33.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/e607531e2dde7a151eb3187f5bcc6e03ff48453b7f4fc1a16a06981d22506f33.jpg)

![efe131b25f1604ed3bda7ef5cccb04cba6c10d2d30acc0601b4cf015f52e4f3c.jpg](../nips_results/395_Head%20Pursuit_%20Probing%20Attention%20Specialization%20in%20Multimodal%20Transformers/tables/efe131b25f1604ed3bda7ef5cccb04cba6c10d2d30acc0601b4cf015f52e4f3c.jpg)

## Sparse VideoGen2: Accelerate Video Generation with  Sparse Attention via Semantic-Aware Permutation


### Images

![06b2d3c3aafcaa16a284b0728dda9f4e0b43c23ada03ddf27cdc2d1651ec46a1.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/06b2d3c3aafcaa16a284b0728dda9f4e0b43c23ada03ddf27cdc2d1651ec46a1.jpg)

![1b70be6bf289af96ae65cebdc163a4cce66686a5deb5e37ca07608b5f1150101.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/1b70be6bf289af96ae65cebdc163a4cce66686a5deb5e37ca07608b5f1150101.jpg)

![25fe970cbf50639e1e7b043b0f080bb477a9e3463369335954b2503d3fbd9113.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/25fe970cbf50639e1e7b043b0f080bb477a9e3463369335954b2503d3fbd9113.jpg)

![2db65804bab23f97cc95aa7345078054b42599e42ee5c3da154366ee711566fd.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/2db65804bab23f97cc95aa7345078054b42599e42ee5c3da154366ee711566fd.jpg)

![349c69cc876849df232dd88bc53101ba3c026e8c5ca7fb6634e265f02f50105c.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/349c69cc876849df232dd88bc53101ba3c026e8c5ca7fb6634e265f02f50105c.jpg)

![39a7cc56b6ccdeaa55fd9b765bd864407114f031f1402c8a2ff5b4e5204ff4c4.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/39a7cc56b6ccdeaa55fd9b765bd864407114f031f1402c8a2ff5b4e5204ff4c4.jpg)

![3a69d0661c6a599a7a20e7a96e625329aecf3424af8ab21fa15e5247c5d55e61.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/3a69d0661c6a599a7a20e7a96e625329aecf3424af8ab21fa15e5247c5d55e61.jpg)

![687028363afbfbfbbb13aed89a7577b38de808d4def6f679cab7fb58b7e9fc2f.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/687028363afbfbfbbb13aed89a7577b38de808d4def6f679cab7fb58b7e9fc2f.jpg)

![6a6c90ea9d4ee43d263edf4fc0ad43aa6531dd5d98578ce71f5ca8f1ecc3549e.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/6a6c90ea9d4ee43d263edf4fc0ad43aa6531dd5d98578ce71f5ca8f1ecc3549e.jpg)

![79ff569383fc8c1cfb5544cc6aced30d5397935c11724028cb31183c9a00f718.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/79ff569383fc8c1cfb5544cc6aced30d5397935c11724028cb31183c9a00f718.jpg)

![91666106a6586d7973defbc257e4b7891d825da381e06267ba29a3d07e3946b3.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/91666106a6586d7973defbc257e4b7891d825da381e06267ba29a3d07e3946b3.jpg)

![97f223fcfc2e0cf692bfc58471bb249a25a8db5be55c9602e529755f54e821cf.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/images/97f223fcfc2e0cf692bfc58471bb249a25a8db5be55c9602e529755f54e821cf.jpg)

### Tables

![3230a68a0e629618e83f84428f6dc63e4d6aa48fea43bdc3c139c4eba775e68f.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/tables/3230a68a0e629618e83f84428f6dc63e4d6aa48fea43bdc3c139c4eba775e68f.jpg)

![595314ce727fb74133b6292e9a89da86c076965a5e428493cc6953d941d997e9.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/tables/595314ce727fb74133b6292e9a89da86c076965a5e428493cc6953d941d997e9.jpg)

![5f1ab847181479fb75629d2ddc9ecfa9af3afb4695245514132801db8d17d9a3.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/tables/5f1ab847181479fb75629d2ddc9ecfa9af3afb4695245514132801db8d17d9a3.jpg)

![c7c0644f412a18ad92cebb8e42dbec08220649d3f1f52b02f4ec09baffb94eed.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/tables/c7c0644f412a18ad92cebb8e42dbec08220649d3f1f52b02f4ec09baffb94eed.jpg)

![dfce91f4fdb382eff4fd172bcc35d805716621dacfc3e1da2a4fbf7f849c72c1.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/tables/dfce91f4fdb382eff4fd172bcc35d805716621dacfc3e1da2a4fbf7f849c72c1.jpg)

![e4f20ff8c85768c8676aa0197d844a7fdb888905002035055e395c804952051f.jpg](../nips_results/396_Sparse%20VideoGen2_%20Accelerate%20Video%20Generation%20with%20%20Sparse%20Attention%20via%20Semantic-Aware%20Permutation/tables/e4f20ff8c85768c8676aa0197d844a7fdb888905002035055e395c804952051f.jpg)

## Strategic Costs of Perceived Bias in Fair Selection


### Images

![0874db08404d962edd0338f7c4586d29f06568a5a700889c1e7e85bb7f942988.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/0874db08404d962edd0338f7c4586d29f06568a5a700889c1e7e85bb7f942988.jpg)

![1c503cc77390cf195a9266254403d887e98a6d96079cce4c75157d2be16af44d.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/1c503cc77390cf195a9266254403d887e98a6d96079cce4c75157d2be16af44d.jpg)

![1f1d451d296ceddcf1d5abb73ed0c65c2c17adc15e93ed050eb2e95de814d937.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/1f1d451d296ceddcf1d5abb73ed0c65c2c17adc15e93ed050eb2e95de814d937.jpg)

![2f037e8345fb8fc6312886dcb3991a7b8de1d188572d6387a061836793fc475b.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/2f037e8345fb8fc6312886dcb3991a7b8de1d188572d6387a061836793fc475b.jpg)

![3d1809ceddf3bc481b0f91ea26ade58aaa9b9b33984d5850f6aef5eb39d4bc70.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/3d1809ceddf3bc481b0f91ea26ade58aaa9b9b33984d5850f6aef5eb39d4bc70.jpg)

![400f94075905ae811e4fd0623878450bac5b8231c6e45ead3fa7548b16ed742f.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/400f94075905ae811e4fd0623878450bac5b8231c6e45ead3fa7548b16ed742f.jpg)

![46cadf299765da7d585120c3377e5b59f785685a5cd16f2559e851fb04a5f187.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/46cadf299765da7d585120c3377e5b59f785685a5cd16f2559e851fb04a5f187.jpg)

![68f003626fbb6f71545256f7df808848640cbc61e7bd95c4b6673f9fb1b9c7e8.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/68f003626fbb6f71545256f7df808848640cbc61e7bd95c4b6673f9fb1b9c7e8.jpg)

![6a5ebf790b400628515565e1c6e16502fe67c2b0ee6528a18ebb92c31edc5913.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/6a5ebf790b400628515565e1c6e16502fe67c2b0ee6528a18ebb92c31edc5913.jpg)

![7eeaec5283ce5eee0d95e0c5af96fb4df6a70808e487f8f7b9bb4585698292eb.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/7eeaec5283ce5eee0d95e0c5af96fb4df6a70808e487f8f7b9bb4585698292eb.jpg)

![80ad9b9b82b3d224ee27111b023669a77d3db4871c1ee877bd7609e8cef88efd.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/80ad9b9b82b3d224ee27111b023669a77d3db4871c1ee877bd7609e8cef88efd.jpg)

![db632eeca34ae8d79a62e7e8d0d5a27818f08a6fb37e7b0e6dcd4bcfc952ac11.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/db632eeca34ae8d79a62e7e8d0d5a27818f08a6fb37e7b0e6dcd4bcfc952ac11.jpg)

![ee929f64c9293fa136e8de965fc91b4513ca755c2a2dc95f05f21c182dc2cbf9.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/ee929f64c9293fa136e8de965fc91b4513ca755c2a2dc95f05f21c182dc2cbf9.jpg)

![f84795be0725c78203dd7cb7c6d586332ab5668069c50dff87be97407537dc02.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/images/f84795be0725c78203dd7cb7c6d586332ab5668069c50dff87be97407537dc02.jpg)

### Tables

![67130afad1f7d86ca0cda878f3117401f939ddee8e271f6c0793308040a474d1.jpg](../nips_results/397_Strategic%20Costs%20of%20Perceived%20Bias%20in%20Fair%20Selection/tables/67130afad1f7d86ca0cda878f3117401f939ddee8e271f6c0793308040a474d1.jpg)

## Pass@K Policy Optimization: Solving Harder Reinforcement Learning Problems


### Images

![1631b23caa9f787a8a3bfab8d4adf4a620ca9d54b5493daa4b9f478b98dc8447.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/images/1631b23caa9f787a8a3bfab8d4adf4a620ca9d54b5493daa4b9f478b98dc8447.jpg)

![16403a85cf2b7aceafbaf0e043a21f32838ea0db0754ccede422deb82e04e5de.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/images/16403a85cf2b7aceafbaf0e043a21f32838ea0db0754ccede422deb82e04e5de.jpg)

![1c6ca4ae7260ecafc9523982481385ebb4842c25b8764060115f938b8faeac0d.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/images/1c6ca4ae7260ecafc9523982481385ebb4842c25b8764060115f938b8faeac0d.jpg)

![2dcd7082551bf7beb05dc9e23a27688d8e189def07ed9c22fdf5203c88ed47d1.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/images/2dcd7082551bf7beb05dc9e23a27688d8e189def07ed9c22fdf5203c88ed47d1.jpg)

![3c0300d93a136280bb66ba9ce38ff58d982d4e0558d1d94c7f33ce17ca5d2662.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/images/3c0300d93a136280bb66ba9ce38ff58d982d4e0558d1d94c7f33ce17ca5d2662.jpg)

![4666b5b85b5f8de5f0d3fa9ec77305deca15f8433959711a2d91c8d3daf6090b.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/images/4666b5b85b5f8de5f0d3fa9ec77305deca15f8433959711a2d91c8d3daf6090b.jpg)

![7bb55b92a451416e92d85733b9ab22209d7d4ff147789b65fcaf4bff04ff8225.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/images/7bb55b92a451416e92d85733b9ab22209d7d4ff147789b65fcaf4bff04ff8225.jpg)

![a671f9f77c90652c77c48f6b0aee645ad188e09f27810b75c968df34e312766f.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/images/a671f9f77c90652c77c48f6b0aee645ad188e09f27810b75c968df34e312766f.jpg)

### Tables

![25943494fdad67c3ca28beafa8a941a26b77c76e311240f790071a18a3bb488d.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/tables/25943494fdad67c3ca28beafa8a941a26b77c76e311240f790071a18a3bb488d.jpg)

![277559d3bdd217182776ea6e145c945ccbb4ad7bf1b8042c1e2c3aa891f9f36f.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/tables/277559d3bdd217182776ea6e145c945ccbb4ad7bf1b8042c1e2c3aa891f9f36f.jpg)

![40b54325b53c869e2cec014161cc309e2d5a798f090f181e71fd07fd97a5f469.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/tables/40b54325b53c869e2cec014161cc309e2d5a798f090f181e71fd07fd97a5f469.jpg)

![4b9f8f6d000f250b08eb3f5cb22403d4201150a02a1f56f6652bcacac33f38ea.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/tables/4b9f8f6d000f250b08eb3f5cb22403d4201150a02a1f56f6652bcacac33f38ea.jpg)

![8f3a547cf2e6c02bd02139f5e3b9b5681733b878687fcf4af99f8fbafdb5f2df.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/tables/8f3a547cf2e6c02bd02139f5e3b9b5681733b878687fcf4af99f8fbafdb5f2df.jpg)

![9a3cae2a23d9f637a67e2ff3a3fe58bdfda6c8b1354fc81e1908296138786c53.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/tables/9a3cae2a23d9f637a67e2ff3a3fe58bdfda6c8b1354fc81e1908296138786c53.jpg)

![9b057fb556d809bd301beb2c3260aa086719a30bfc6e7b24843fd815a3bbe26f.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/tables/9b057fb556d809bd301beb2c3260aa086719a30bfc6e7b24843fd815a3bbe26f.jpg)

![e80f4304fca095f95214a2b59bec4f5580a8ac6d76233df3acdcb3f10f807566.jpg](../nips_results/398_Pass%40K%20Policy%20Optimization_%20Solving%20Harder%20Reinforcement%20Learning%20Problems/tables/e80f4304fca095f95214a2b59bec4f5580a8ac6d76233df3acdcb3f10f807566.jpg)

## Language Models can Self-Improve at State-Value Estimation for Better Search


### Images

![05ed5f510e1b00101b0e2e22c3f77a33f6cae329e52f9bc59aa986c9da1c7f93.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/05ed5f510e1b00101b0e2e22c3f77a33f6cae329e52f9bc59aa986c9da1c7f93.jpg)

![06b971e8d31630c7f06b85134a7c46771b5ccc459250a091624bf450ae578d5e.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/06b971e8d31630c7f06b85134a7c46771b5ccc459250a091624bf450ae578d5e.jpg)

![16844e50315847ab5088eb7dc13669d2a09a0ab011e7a9830bc6ecdf7cc2b9fe.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/16844e50315847ab5088eb7dc13669d2a09a0ab011e7a9830bc6ecdf7cc2b9fe.jpg)

![1db6da543e3b2ce322c45078e7e463bd0aa29272025fe63d7821e04d11711ad5.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/1db6da543e3b2ce322c45078e7e463bd0aa29272025fe63d7821e04d11711ad5.jpg)

![283886f69628e6d76be2c64d87d4c2d4dd3c272ce1da0e450d3cbac6091c98b5.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/283886f69628e6d76be2c64d87d4c2d4dd3c272ce1da0e450d3cbac6091c98b5.jpg)

![45c9455c7ebebc8ea454ba688eb18a5d56fa861c4cc9ea993a3fa58f09ac1c5e.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/45c9455c7ebebc8ea454ba688eb18a5d56fa861c4cc9ea993a3fa58f09ac1c5e.jpg)

![4f489f1d47907ccdbcfa794e29ac110f31d274546220897baca54bdfe4e07fb3.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/4f489f1d47907ccdbcfa794e29ac110f31d274546220897baca54bdfe4e07fb3.jpg)

![9a039d21a7651c229ea224b3756ed17a394981baa9d14703a41ce424d0970a4c.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/9a039d21a7651c229ea224b3756ed17a394981baa9d14703a41ce424d0970a4c.jpg)

![bf4e1d1fc54d7e2c15d64541206de8934b554a1a6dfc487a6c963a2515fb9e98.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/bf4e1d1fc54d7e2c15d64541206de8934b554a1a6dfc487a6c963a2515fb9e98.jpg)

![dc6e9d0e650746b4c80f7faca3268c63bcb1e461b06488e4b04107e27f75c6ab.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/dc6e9d0e650746b4c80f7faca3268c63bcb1e461b06488e4b04107e27f75c6ab.jpg)

![e56a8317020b3bd8aeb2f4cd61853503e07ddbd506a68f7ab04597b54c74cd53.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/e56a8317020b3bd8aeb2f4cd61853503e07ddbd506a68f7ab04597b54c74cd53.jpg)

![eca93225bdd4bc4eff47fe1b4bcb3a6a6655aac549fb2a3ce6ddcdb9ce1f2a0e.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/images/eca93225bdd4bc4eff47fe1b4bcb3a6a6655aac549fb2a3ce6ddcdb9ce1f2a0e.jpg)

### Tables

![34152b623fc99e3b92ad73c32d8ee07a2893e8c4bef69169138cc1d6e6974e04.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/tables/34152b623fc99e3b92ad73c32d8ee07a2893e8c4bef69169138cc1d6e6974e04.jpg)

![589f0dd375847e613edb0f72d5a8533d5065394d6c589240a1ae8bc89058a5f1.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/tables/589f0dd375847e613edb0f72d5a8533d5065394d6c589240a1ae8bc89058a5f1.jpg)

![782531b2ff94a36b0bb7d74308a43ba1acb7cd8a60241edca6aaa869b0336e34.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/tables/782531b2ff94a36b0bb7d74308a43ba1acb7cd8a60241edca6aaa869b0336e34.jpg)

![9f63bd1aceb9c782fbc4e2faeec527120fe34d3745b521cb1c8c86c6b98bc1df.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/tables/9f63bd1aceb9c782fbc4e2faeec527120fe34d3745b521cb1c8c86c6b98bc1df.jpg)

![abc212b1d114d4075a2a58b9e18074e0129a0c13e7920ad88aa92e2d9f39a8e6.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/tables/abc212b1d114d4075a2a58b9e18074e0129a0c13e7920ad88aa92e2d9f39a8e6.jpg)

![d1581d1cc507632655b0e445238ea2f3fda265c282f6412dbddfc185bcc118a3.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/tables/d1581d1cc507632655b0e445238ea2f3fda265c282f6412dbddfc185bcc118a3.jpg)

![f51bb371089f5c97dcfd791149b0e30399995ed48cfc37c435bb5524e7c37f49.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/tables/f51bb371089f5c97dcfd791149b0e30399995ed48cfc37c435bb5524e7c37f49.jpg)

![f8fa7bf1ae460bf9a40120d107453428d4e0cb24537ce58283a982288474f20a.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/tables/f8fa7bf1ae460bf9a40120d107453428d4e0cb24537ce58283a982288474f20a.jpg)

![fe917db419682e1adfb97f7ffdd6bea8645a4ccd1c0906fcbf6e65cf67b319c4.jpg](../nips_results/399_Language%20Models%20can%20Self-Improve%20at%20State-Value%20Estimation%20for%20Better%20Search/tables/fe917db419682e1adfb97f7ffdd6bea8645a4ccd1c0906fcbf6e65cf67b319c4.jpg)

## HyPINO: Multi-Physics Neural Operators via HyperPINNs and the Method of Manufactured Solutions


### Images

![0be724a08d8eb1ef933ccb2a415ca4741486141b999fd561cdd0622fb540d801.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/0be724a08d8eb1ef933ccb2a415ca4741486141b999fd561cdd0622fb540d801.jpg)

![0cde6fe25143c23b87697b05695314d070f64dd3f210e76a4223e6ff3449082d.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/0cde6fe25143c23b87697b05695314d070f64dd3f210e76a4223e6ff3449082d.jpg)

![0ee62ea6fcead6190d42513c29dcceb660ce81930c3dc43ee9be2f6db9aef025.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/0ee62ea6fcead6190d42513c29dcceb660ce81930c3dc43ee9be2f6db9aef025.jpg)

![2b3bac3c974f9aaa802b176dea0b0ab25dd87a428cb91f8d2c617dd0d0708a86.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/2b3bac3c974f9aaa802b176dea0b0ab25dd87a428cb91f8d2c617dd0d0708a86.jpg)

![3da2ce8e835abdc197522ca47fb4de1168a1284958f1c773ba013bec82329459.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/3da2ce8e835abdc197522ca47fb4de1168a1284958f1c773ba013bec82329459.jpg)

![43243da57e72aad08ae45db7fae096684f910756a40c0812a405a0ca40be0ef0.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/43243da57e72aad08ae45db7fae096684f910756a40c0812a405a0ca40be0ef0.jpg)

![4cfe6c2ca8820bc6b74e6d6bfd8209735b57899980bec5c1b944ac55d3deee38.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/4cfe6c2ca8820bc6b74e6d6bfd8209735b57899980bec5c1b944ac55d3deee38.jpg)

![54e421d7fbfe1b518f1b8cb61f733a46f7c7aae2b0b3d504658dd04862d56e93.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/54e421d7fbfe1b518f1b8cb61f733a46f7c7aae2b0b3d504658dd04862d56e93.jpg)

![829435a469a600accd6c8e9286aa378b2477fe4a36972c02995bd2dd53478297.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/829435a469a600accd6c8e9286aa378b2477fe4a36972c02995bd2dd53478297.jpg)

![b80f71335a6cd2b8019e7f9afa9fdd09ee156af099a57a9a621bec70067b5db3.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/b80f71335a6cd2b8019e7f9afa9fdd09ee156af099a57a9a621bec70067b5db3.jpg)

![c8089b5b989167b657ac4588ab47b2159f8e3d0f2cac84afd89b5bdcca10ca3d.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/c8089b5b989167b657ac4588ab47b2159f8e3d0f2cac84afd89b5bdcca10ca3d.jpg)

![ccafd1cb3c93d927621f22c8fc2f2afbc4a64030fe8ad741218a7a3bae960ddf.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/ccafd1cb3c93d927621f22c8fc2f2afbc4a64030fe8ad741218a7a3bae960ddf.jpg)

![d280e675a23d926d4f9de558f7e22525c73479f0fb6d459ef34a22bf0e85ba32.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/d280e675a23d926d4f9de558f7e22525c73479f0fb6d459ef34a22bf0e85ba32.jpg)

![d74790836b5ff244dfc15ffb0c1a5e0fa483900bd13608222e056e159137e011.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/d74790836b5ff244dfc15ffb0c1a5e0fa483900bd13608222e056e159137e011.jpg)

![f64917ecde543ac7d399f8728a14509495e72a0603a527eb1be29ccd5615626b.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/images/f64917ecde543ac7d399f8728a14509495e72a0603a527eb1be29ccd5615626b.jpg)

### Tables

![8879f57853987f090b687980abef35919d4f4fff3e49cbdb8fa0599ee4f5083e.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/tables/8879f57853987f090b687980abef35919d4f4fff3e49cbdb8fa0599ee4f5083e.jpg)

![b202c8b9575314ef5487eead0950bb4e59a5ede00abb279a1a27bf1c5ff7a9ff.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/tables/b202c8b9575314ef5487eead0950bb4e59a5ede00abb279a1a27bf1c5ff7a9ff.jpg)

![b52694bd13ca2516c2c5866019b3ccdbf08c7af6385b50f6fd977fdf7927fe87.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/tables/b52694bd13ca2516c2c5866019b3ccdbf08c7af6385b50f6fd977fdf7927fe87.jpg)

![e01b236f56da8d204fa5a8c347f2f79e23701569c5dafcf2f7a7c61dcff7ab96.jpg](../nips_results/400_HyPINO_%20Multi-Physics%20Neural%20Operators%20via%20HyperPINNs%20and%20the%20Method%20of%20Manufactured%20Solutions/tables/e01b236f56da8d204fa5a8c347f2f79e23701569c5dafcf2f7a7c61dcff7ab96.jpg)

## An Efficient Orlicz-Sobolev Approach for Transporting Unbalanced Measures on a Graph


### Images

![14da749a2fc5ee475b353fe61a93332cda1a1a1b0c1a282908465ce200415e92.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/images/14da749a2fc5ee475b353fe61a93332cda1a1a1b0c1a282908465ce200415e92.jpg)

![57599d1b3cb508e5da576a6fc00808a0fe6f78a147629ae7d3238a3705402814.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/images/57599d1b3cb508e5da576a6fc00808a0fe6f78a147629ae7d3238a3705402814.jpg)

![73dc23d0d8dfe09191eb718080c63e49a065af5f09c91aea4fce3f501702b570.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/images/73dc23d0d8dfe09191eb718080c63e49a065af5f09c91aea4fce3f501702b570.jpg)

![87651a2364a38b3714ef0dd3b1a1d3a8de311f57a71278f6c7dfa7c00f868acc.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/images/87651a2364a38b3714ef0dd3b1a1d3a8de311f57a71278f6c7dfa7c00f868acc.jpg)

![afeeab6736bf2ae66268d721361f66ddeead423c4a91c1d98df846169f42f640.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/images/afeeab6736bf2ae66268d721361f66ddeead423c4a91c1d98df846169f42f640.jpg)

![e13f7dcc8e5ae69d7a9d28c56d951f058c044b6291648e8c2371be2797de6ac5.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/images/e13f7dcc8e5ae69d7a9d28c56d951f058c044b6291648e8c2371be2797de6ac5.jpg)

![fcf6351462ffdd3bd53d77c0faff4dbe4aba5122cd4b2e57b693db92d8d88c17.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/images/fcf6351462ffdd3bd53d77c0faff4dbe4aba5122cd4b2e57b693db92d8d88c17.jpg)

### Tables

![229d827e5fec855c07d1e2e1c20148765cbdd761f8a0fa4d0b48bc9316a6b4c8.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/tables/229d827e5fec855c07d1e2e1c20148765cbdd761f8a0fa4d0b48bc9316a6b4c8.jpg)

![2fbbf591a48d3d377cfbab123187572884a4734416975b25826967946cdfa71b.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/tables/2fbbf591a48d3d377cfbab123187572884a4734416975b25826967946cdfa71b.jpg)

![4f604a5d997a51e957dd0cb0d7d3fa7bba53a8e5b3f9277e54e63870af156afd.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/tables/4f604a5d997a51e957dd0cb0d7d3fa7bba53a8e5b3f9277e54e63870af156afd.jpg)

![532d5cdfa13004449e5c4b85aaf3a9c3eb776712a0ceca47490fb473c2822bd3.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/tables/532d5cdfa13004449e5c4b85aaf3a9c3eb776712a0ceca47490fb473c2822bd3.jpg)

![81ef579c0c7756692ee56d097344bad37cf117fd4b78c5b779d12825b5ab3005.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/tables/81ef579c0c7756692ee56d097344bad37cf117fd4b78c5b779d12825b5ab3005.jpg)

![cf1bc6b38bccefda889b9ba10f955b4167c35e1de66663c48db5e1db123cefd3.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/tables/cf1bc6b38bccefda889b9ba10f955b4167c35e1de66663c48db5e1db123cefd3.jpg)

![e9ea535815c5cea0bf4e5f15b2d767452f4263fc12f4699d524beb6925efd6dd.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/tables/e9ea535815c5cea0bf4e5f15b2d767452f4263fc12f4699d524beb6925efd6dd.jpg)

![f963021c597d01f44fdbdc5ef805bd5b26da950fbf44822a5105e80e510e733b.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/tables/f963021c597d01f44fdbdc5ef805bd5b26da950fbf44822a5105e80e510e733b.jpg)

![fbb676aaf3ab457c3e121cdaa7c495cdd64fd3e53822363d5fd63bfdb15f14ad.jpg](../nips_results/401_An%20Efficient%20Orlicz-Sobolev%20Approach%20for%20Transporting%20Unbalanced%20Measures%20on%20a%20Graph/tables/fbb676aaf3ab457c3e121cdaa7c495cdd64fd3e53822363d5fd63bfdb15f14ad.jpg)

## Graph–Smoothed Bayesian Black-Box Shift Estimator and Its Information Geometry


### Tables

![092d19eab6358a86356b8c634b4948af449e1695939c3d7a7f204dd0a92607e3.jpg](../nips_results/402_Graph%E2%80%93Smoothed%20Bayesian%20Black-Box%20Shift%20Estimator%20and%20Its%20Information%20Geometry/tables/092d19eab6358a86356b8c634b4948af449e1695939c3d7a7f204dd0a92607e3.jpg)

![a24a78de4dffae4ffb385126d0476d38e23cb43bdc35572e93f5507b14a8f8e4.jpg](../nips_results/402_Graph%E2%80%93Smoothed%20Bayesian%20Black-Box%20Shift%20Estimator%20and%20Its%20Information%20Geometry/tables/a24a78de4dffae4ffb385126d0476d38e23cb43bdc35572e93f5507b14a8f8e4.jpg)

![b1ac705864d1d2f048a1c9a3b11a8a21366d34cc8eae910f87f529d83c6e608e.jpg](../nips_results/402_Graph%E2%80%93Smoothed%20Bayesian%20Black-Box%20Shift%20Estimator%20and%20Its%20Information%20Geometry/tables/b1ac705864d1d2f048a1c9a3b11a8a21366d34cc8eae910f87f529d83c6e608e.jpg)

![dcabcdb056bfa48a16a61354a90a921fffdec6ec042ee45cf0e2bde16b715b97.jpg](../nips_results/402_Graph%E2%80%93Smoothed%20Bayesian%20Black-Box%20Shift%20Estimator%20and%20Its%20Information%20Geometry/tables/dcabcdb056bfa48a16a61354a90a921fffdec6ec042ee45cf0e2bde16b715b97.jpg)

## Vision Transformers with Self-Distilled Registers


### Images

![018cb46760ba50dc88119805571dd0dd3f1bf97a5e12cdb99fe9428d4005d289.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/018cb46760ba50dc88119805571dd0dd3f1bf97a5e12cdb99fe9428d4005d289.jpg)

![15c9896e704c57412811271707adfc9a0971e1f22d534f9436f8ad66d2eff77d.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/15c9896e704c57412811271707adfc9a0971e1f22d534f9436f8ad66d2eff77d.jpg)

![15f57e2efcfdd7ece7167e1094cd8722b6694e6a2e39d2aa115471a524848454.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/15f57e2efcfdd7ece7167e1094cd8722b6694e6a2e39d2aa115471a524848454.jpg)

![3293ea6f7dd98a63448c36481ad3e9fa720d5a00bce0fae2b5a759d706eaae6f.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/3293ea6f7dd98a63448c36481ad3e9fa720d5a00bce0fae2b5a759d706eaae6f.jpg)

![3614e7c579b93813f397936dbedd7c60b87b88f0d5aac9f92eb4495b22e7cad5.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/3614e7c579b93813f397936dbedd7c60b87b88f0d5aac9f92eb4495b22e7cad5.jpg)

![39834b4031d6de4a584d902dbb954785700f236bb8a7e451f41c7bc7bb46b1ef.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/39834b4031d6de4a584d902dbb954785700f236bb8a7e451f41c7bc7bb46b1ef.jpg)

![3a1109b7ff05d3e0c3458a2b96d00f431e66290760f560f0301129cfc50ffefb.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/3a1109b7ff05d3e0c3458a2b96d00f431e66290760f560f0301129cfc50ffefb.jpg)

![3ffe1d02b314311c4576a9902d7ab6041dd1ebc6b3d6a11a1a8c6f3c2fb42e04.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/3ffe1d02b314311c4576a9902d7ab6041dd1ebc6b3d6a11a1a8c6f3c2fb42e04.jpg)

![49e5f8eda34d7ab337530e3aae0fe20283f2f6667af17836a0edbf9f50b238ed.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/49e5f8eda34d7ab337530e3aae0fe20283f2f6667af17836a0edbf9f50b238ed.jpg)

![51dd404618e4e2ef29b910d1ff8245b8192d871a3aeaf263b4f6596090001513.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/51dd404618e4e2ef29b910d1ff8245b8192d871a3aeaf263b4f6596090001513.jpg)

![6b8a774208376ecddc863b1b5221cf7b5e697669de153f56f9ca76e50474ed41.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/6b8a774208376ecddc863b1b5221cf7b5e697669de153f56f9ca76e50474ed41.jpg)

![b23f09364a5af155ddef0d3ce1322a448b5b40fe15ce1f056ae1af442d36758e.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/b23f09364a5af155ddef0d3ce1322a448b5b40fe15ce1f056ae1af442d36758e.jpg)

![bf973d8f43c362a644a2761b290f5118944c07c7be4090b1ce603a7f93ed8e40.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/bf973d8f43c362a644a2761b290f5118944c07c7be4090b1ce603a7f93ed8e40.jpg)

![c1eb6acc4422b234ba2609cb10b20436aa4613104e44c588f5bb49cf01cfe5d1.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/c1eb6acc4422b234ba2609cb10b20436aa4613104e44c588f5bb49cf01cfe5d1.jpg)

![df06661bd9f0c8b25a3413300c359e6940966501e4927672ea43826acb5fd813.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/images/df06661bd9f0c8b25a3413300c359e6940966501e4927672ea43826acb5fd813.jpg)

### Tables

![0a9533f91830fe0b701438d124410f92177097ffefcfd1bfa7d980d5dc81b590.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/tables/0a9533f91830fe0b701438d124410f92177097ffefcfd1bfa7d980d5dc81b590.jpg)

![1637906213718c153dbac6b85bbb3b6ce5757123633d43c1f969785fbcd1bc56.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/tables/1637906213718c153dbac6b85bbb3b6ce5757123633d43c1f969785fbcd1bc56.jpg)

![4ce9786991bef73989f3a36d30987c77985fa741e914f9747a853d9a4d42254a.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/tables/4ce9786991bef73989f3a36d30987c77985fa741e914f9747a853d9a4d42254a.jpg)

![53eac10e2beed9b841ceb8bffc4118e68b7b59e27c71e97600590f8b3d55599e.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/tables/53eac10e2beed9b841ceb8bffc4118e68b7b59e27c71e97600590f8b3d55599e.jpg)

![69102ce4afd0f1879c083ec4f806b2a5d9ec70e0efb8030349cfeddb1d3ef854.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/tables/69102ce4afd0f1879c083ec4f806b2a5d9ec70e0efb8030349cfeddb1d3ef854.jpg)

![7b8f243642f39a107be049b04e2ea16fc6757a0da10a4b0de3da0de3f7b15fdb.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/tables/7b8f243642f39a107be049b04e2ea16fc6757a0da10a4b0de3da0de3f7b15fdb.jpg)

![7cb36c0905e04b1cd91ff0d9b6d1dd0c05b5911fc50c8d9b101bf12f7cdecf30.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/tables/7cb36c0905e04b1cd91ff0d9b6d1dd0c05b5911fc50c8d9b101bf12f7cdecf30.jpg)

![a035fcaee4298ca0a4b20270cbcc5b2b519a5303529e3773f7bd2a0b61f40161.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/tables/a035fcaee4298ca0a4b20270cbcc5b2b519a5303529e3773f7bd2a0b61f40161.jpg)

![bfcf9fc15345c79fe8e49e4476217d6527f468bc4b54276fc744107d6f70e7ae.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/tables/bfcf9fc15345c79fe8e49e4476217d6527f468bc4b54276fc744107d6f70e7ae.jpg)

![d8d0a17cdf7c875571d2d570f5876bfecfbd373b96f3a337fe2a7b6e53462167.jpg](../nips_results/403_Vision%20Transformers%20with%20Self-Distilled%20Registers/tables/d8d0a17cdf7c875571d2d570f5876bfecfbd373b96f3a337fe2a7b6e53462167.jpg)

## Language Modeling by Language Models


### Images

![058e809fa77feb9898a307781d98893602107ece9096827ae6a93dc64414abd1.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/058e809fa77feb9898a307781d98893602107ece9096827ae6a93dc64414abd1.jpg)

![0ecdd682dd16091114bf147f0207f2f03737774acfd56bbc2a443c0f8825f316.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/0ecdd682dd16091114bf147f0207f2f03737774acfd56bbc2a443c0f8825f316.jpg)

![1084cfef21dcd00e634c6513dc71793ab3db2db7ca54f8b9f4586fa4badd4dfc.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/1084cfef21dcd00e634c6513dc71793ab3db2db7ca54f8b9f4586fa4badd4dfc.jpg)

![12b6e35e90e78592f7141acaa358f596685ac698c238a78d2efa20c207e186a4.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/12b6e35e90e78592f7141acaa358f596685ac698c238a78d2efa20c207e186a4.jpg)

![1647b11942046e4ed520deee9900392da18e2bf81930978f3c70bacd820fb72a.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/1647b11942046e4ed520deee9900392da18e2bf81930978f3c70bacd820fb72a.jpg)

![18b71afc0ac72d678cbf3b37d93bbab2e1fa78aae272b09b16dbfccbf0c834c4.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/18b71afc0ac72d678cbf3b37d93bbab2e1fa78aae272b09b16dbfccbf0c834c4.jpg)

![1af3181c0e4a043596db8c4e8206e9bb149d1abf086df70a6d515cdd01ebfd6c.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/1af3181c0e4a043596db8c4e8206e9bb149d1abf086df70a6d515cdd01ebfd6c.jpg)

![2009a1006167480526aa4d51785f89fb55c089c444ef5546f659e52ce07c2950.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/2009a1006167480526aa4d51785f89fb55c089c444ef5546f659e52ce07c2950.jpg)

![24fdd08ad3f4e7135e4f5c8c687e614df39cbbe030762808fbca9e54df4fb9c3.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/24fdd08ad3f4e7135e4f5c8c687e614df39cbbe030762808fbca9e54df4fb9c3.jpg)

![27aa19608c9902cebbefc430b37e0fd32c796bfe920013c906268adafe8cdb20.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/27aa19608c9902cebbefc430b37e0fd32c796bfe920013c906268adafe8cdb20.jpg)

![298d728e18cb524d526ee817a3ef3e4ac795f51abc11d5ec44aef81572a00dbe.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/298d728e18cb524d526ee817a3ef3e4ac795f51abc11d5ec44aef81572a00dbe.jpg)

![2db051ecbb3ea379c8af8afc666f1a67af999ff162b105d316e055666270200d.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/2db051ecbb3ea379c8af8afc666f1a67af999ff162b105d316e055666270200d.jpg)

![30b52391454fb7e842b117eae1ccd437d7bf4953a3997a0bf711436445bf5534.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/30b52391454fb7e842b117eae1ccd437d7bf4953a3997a0bf711436445bf5534.jpg)

![330c7a87fef3abb5e17f710318ec83b2c0e45254f6cbacbdc7490567a205cce3.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/330c7a87fef3abb5e17f710318ec83b2c0e45254f6cbacbdc7490567a205cce3.jpg)

![3d3bbcc1b387beaf4602c2abff85b895d7244bf03c302e6e5b02cec5724ee3cc.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/3d3bbcc1b387beaf4602c2abff85b895d7244bf03c302e6e5b02cec5724ee3cc.jpg)

![3d4e878ffe4e426d5fcee7e054fb74b54419e8bd74c11cc3afb743621d69aeff.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/3d4e878ffe4e426d5fcee7e054fb74b54419e8bd74c11cc3afb743621d69aeff.jpg)

![3f074fa887df722491ed5fe3fb938dc656aabbf75e01eb6a6153a680d7548801.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/3f074fa887df722491ed5fe3fb938dc656aabbf75e01eb6a6153a680d7548801.jpg)

![3fa432147d4d7258d76c971ee50c75412f73d0eeccd8f72478dadd30dcba7c8b.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/3fa432147d4d7258d76c971ee50c75412f73d0eeccd8f72478dadd30dcba7c8b.jpg)

![407c912443c5d21f3b4aa762c8821f5b29a1ee7a93ad841637bd8baf56d2795a.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/407c912443c5d21f3b4aa762c8821f5b29a1ee7a93ad841637bd8baf56d2795a.jpg)

![410b5eee140c45affc712c33b78ff408efc9692daca9472e94558fb6de7dbaf8.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/410b5eee140c45affc712c33b78ff408efc9692daca9472e94558fb6de7dbaf8.jpg)

![45b2426bd08593b1f3543fb8506374119ad4a5e1f4ab4886aa69a5e6d7be86b4.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/45b2426bd08593b1f3543fb8506374119ad4a5e1f4ab4886aa69a5e6d7be86b4.jpg)

![57db93f4a0cbce755d4f4ee4cf2a721e9a134474aa1db7976391f5513f88aedd.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/57db93f4a0cbce755d4f4ee4cf2a721e9a134474aa1db7976391f5513f88aedd.jpg)

![5cb6ba041822adca6faa7df6acdf7f758426697131bd1fb92a072971691ab38b.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/5cb6ba041822adca6faa7df6acdf7f758426697131bd1fb92a072971691ab38b.jpg)

![6086891383c2a136e07377aa4ee55cad55d565d7d46f36073d422504636d9736.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/6086891383c2a136e07377aa4ee55cad55d565d7d46f36073d422504636d9736.jpg)

![64908b88ed4f74dc06c78241c8ad9b4aef6a2e2957115e5fe74e24bf8676ae9b.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/64908b88ed4f74dc06c78241c8ad9b4aef6a2e2957115e5fe74e24bf8676ae9b.jpg)

![6e17a8ed4f6f10d48bf3d51f134e163a5be86af98b47d7d3ea2b9f289f08c348.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/6e17a8ed4f6f10d48bf3d51f134e163a5be86af98b47d7d3ea2b9f289f08c348.jpg)

![6eb38a74b09c86a6b0d636a825bce5db0fe983ba44d95f9ee1a9786d7d1fc2c4.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/6eb38a74b09c86a6b0d636a825bce5db0fe983ba44d95f9ee1a9786d7d1fc2c4.jpg)

![7073fb7b24d71220401e20c861fd104e336d56b26d97a8ad0452a61dccc08334.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/7073fb7b24d71220401e20c861fd104e336d56b26d97a8ad0452a61dccc08334.jpg)

![7c5bda809d1c45f8e43608ec13329d8d231e6e16b7a56a43024752395d579133.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/7c5bda809d1c45f8e43608ec13329d8d231e6e16b7a56a43024752395d579133.jpg)

![7debc2ad8489de2714e88e0653c00b5220bf9030a7fa4f2b23ca39c2e0eb3f0d.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/7debc2ad8489de2714e88e0653c00b5220bf9030a7fa4f2b23ca39c2e0eb3f0d.jpg)

![7f3c154543d6003fcad6264c5dccaeca78e4eaf503e82b649c12a6ddd5bc15f2.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/7f3c154543d6003fcad6264c5dccaeca78e4eaf503e82b649c12a6ddd5bc15f2.jpg)

![8565bdfcc0e78eb8bbcd937b826acc8ccc7d16cf7431206ab68d7166336e15b4.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/8565bdfcc0e78eb8bbcd937b826acc8ccc7d16cf7431206ab68d7166336e15b4.jpg)

![89a1acacf9134766d03f7587ee5dcbdeed2fc29dbaccf5faf8411b64bd5298db.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/89a1acacf9134766d03f7587ee5dcbdeed2fc29dbaccf5faf8411b64bd5298db.jpg)

![8beb1ed703984f82523cd74e419c9e02802791650b7898d922512d5eb2c9cc6e.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/8beb1ed703984f82523cd74e419c9e02802791650b7898d922512d5eb2c9cc6e.jpg)

![8d591d9e028b8eb11b11d5cbd57ee8adcef3abc715f791e8e7fd7b2f19903f35.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/8d591d9e028b8eb11b11d5cbd57ee8adcef3abc715f791e8e7fd7b2f19903f35.jpg)

![8d6985670df48d5ac10acf111feea36ff592715459a1ab05d9dae48d13cda6cb.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/8d6985670df48d5ac10acf111feea36ff592715459a1ab05d9dae48d13cda6cb.jpg)

![941051f5bcecb7e6ca1b00ed31dc54de0ed5702c7f85c3dc45ba108681f4cddc.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/941051f5bcecb7e6ca1b00ed31dc54de0ed5702c7f85c3dc45ba108681f4cddc.jpg)

![9678997447c4e9e69839cb8f8f0d7fe4255845ceb90e908fbf1e8242de937cdf.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/9678997447c4e9e69839cb8f8f0d7fe4255845ceb90e908fbf1e8242de937cdf.jpg)

![96f8b4c2ebd9d8cfd0af2a48d179ab065f1a06f523089fc056b2bc09a9c84448.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/96f8b4c2ebd9d8cfd0af2a48d179ab065f1a06f523089fc056b2bc09a9c84448.jpg)

![9e4867ea041e70e293b32ffec08e298742b3c7726dd240e2dc8ecb773aed3edc.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/9e4867ea041e70e293b32ffec08e298742b3c7726dd240e2dc8ecb773aed3edc.jpg)

![a5e33e414c99abecef2dcdd3ba45bb55f3a6bcc4a9dcd954c639c61ddbf32645.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/a5e33e414c99abecef2dcdd3ba45bb55f3a6bcc4a9dcd954c639c61ddbf32645.jpg)

![b4359ebb7f0b83d8811987deaf77d4dfa71e876ab7ba0890ef5d9217dbdd8243.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/b4359ebb7f0b83d8811987deaf77d4dfa71e876ab7ba0890ef5d9217dbdd8243.jpg)

![b661a9b43beead8332f39ee6ca55e9ac809ec337946294dc96bdf20bafe81e83.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/b661a9b43beead8332f39ee6ca55e9ac809ec337946294dc96bdf20bafe81e83.jpg)

![b7299868534dff39fd8c81c830fcb9aadfc137c5f5da32bfa1cde61ad8675f57.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/b7299868534dff39fd8c81c830fcb9aadfc137c5f5da32bfa1cde61ad8675f57.jpg)

![bf8c4ebbef97615c0dc0e2394ae63ee920109c9b51b55421127353e5655d850d.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/bf8c4ebbef97615c0dc0e2394ae63ee920109c9b51b55421127353e5655d850d.jpg)

![c1845a47b896fa4e3a85bb7f1a518e43c43f1d88d58672a3814cb1db5dfd85bd.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/c1845a47b896fa4e3a85bb7f1a518e43c43f1d88d58672a3814cb1db5dfd85bd.jpg)

![c4424418d67c74be18c7826163ca0ef5caf61b127100402e74e2f7416a964d45.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/c4424418d67c74be18c7826163ca0ef5caf61b127100402e74e2f7416a964d45.jpg)

![c47bf2fd16b05cfcda8f34b6edf2d27e27d1cbd2df8a4b5dce10cd54040bbd5f.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/c47bf2fd16b05cfcda8f34b6edf2d27e27d1cbd2df8a4b5dce10cd54040bbd5f.jpg)

![c534c7e49afd256a8c35b2f085834320ad2d4bda368c0998808a19fab467a9f1.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/c534c7e49afd256a8c35b2f085834320ad2d4bda368c0998808a19fab467a9f1.jpg)

![cbffbd5e74c601fe45793cf87ce2aef33cd8fd37bfdbd36f803a0cd4b33358b7.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/cbffbd5e74c601fe45793cf87ce2aef33cd8fd37bfdbd36f803a0cd4b33358b7.jpg)

![cc45b6571ba34f3a6ce198b06d04bef8286f6f4b77528350702888c48d45ec8c.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/cc45b6571ba34f3a6ce198b06d04bef8286f6f4b77528350702888c48d45ec8c.jpg)

![ccfbf77e9c1d8072cd4bc32be5c240758e328495c54e7b79529330650f492208.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/ccfbf77e9c1d8072cd4bc32be5c240758e328495c54e7b79529330650f492208.jpg)

![ce3059136af7f12dc9a533f942c942ea62fa15493cca95350c3053e467fd486f.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/ce3059136af7f12dc9a533f942c942ea62fa15493cca95350c3053e467fd486f.jpg)

![d4a51f0c32c91846319695b0466928472fd5a84cb38865f204630b0559679751.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/d4a51f0c32c91846319695b0466928472fd5a84cb38865f204630b0559679751.jpg)

![dfdaedcc90aed5f1ffcaff14287cee37194a739dfa990d27b247a68df8bed669.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/dfdaedcc90aed5f1ffcaff14287cee37194a739dfa990d27b247a68df8bed669.jpg)

![e00142ce16e41fd750d616eb3a593c918353e3d6cd9b7062cbb605233fbc7a6f.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/e00142ce16e41fd750d616eb3a593c918353e3d6cd9b7062cbb605233fbc7a6f.jpg)

![e5be2d77d617aaac2bb0faa42b55f2a14511b8a15cb6bcbd8b8deca47992d03c.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/e5be2d77d617aaac2bb0faa42b55f2a14511b8a15cb6bcbd8b8deca47992d03c.jpg)

![e66b535dc269317362c370a8c90b27e03c4a088ceb73024667654484453ae798.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/e66b535dc269317362c370a8c90b27e03c4a088ceb73024667654484453ae798.jpg)

![e7886c77c87caf7e61ab0ab03120f5ed990ba71a0694dc98e2f95a0c465d882b.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/e7886c77c87caf7e61ab0ab03120f5ed990ba71a0694dc98e2f95a0c465d882b.jpg)

![eaa8687a6eeee55e9ccf518abec1de2d1402ab5a32624bd1381a2f46434df517.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/eaa8687a6eeee55e9ccf518abec1de2d1402ab5a32624bd1381a2f46434df517.jpg)

![eb73b6dd2280211045a76f6ae89ab743d79dbd9c452b5e5b6cb1dc9f240292c4.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/eb73b6dd2280211045a76f6ae89ab743d79dbd9c452b5e5b6cb1dc9f240292c4.jpg)

![ec712cd7a10208c5b773582884d4adb94279708a5908fbdf8889b782b7be3ff3.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/ec712cd7a10208c5b773582884d4adb94279708a5908fbdf8889b782b7be3ff3.jpg)

![fc45e8b07d84b9bb3a650409edc71a9b60ed289a765fe26cd3377e7a5852f258.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/fc45e8b07d84b9bb3a650409edc71a9b60ed289a765fe26cd3377e7a5852f258.jpg)

![fd6b568541a58fec383db7b8c870c0a2467bf4f9bcdd6a471ea40cf27c569a38.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/images/fd6b568541a58fec383db7b8c870c0a2467bf4f9bcdd6a471ea40cf27c569a38.jpg)

### Tables

![0f8345f988c4739877ceaa4c3607d193548aa24cc378d90bcd4dad428d44ff0c.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/0f8345f988c4739877ceaa4c3607d193548aa24cc378d90bcd4dad428d44ff0c.jpg)

![128544e9c6ced3f26ed4601f3a3b78165da760371ebd38932f67957cadaa9d65.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/128544e9c6ced3f26ed4601f3a3b78165da760371ebd38932f67957cadaa9d65.jpg)

![1f8635dfdf4846596ea00e70ea8a1345043258bf4c01e45b541b4641593e1475.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/1f8635dfdf4846596ea00e70ea8a1345043258bf4c01e45b541b4641593e1475.jpg)

![5d426502dd32479cb9ddd2f716cba1f3c6fda7a32c5c8a07f7b13d373778e5c6.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/5d426502dd32479cb9ddd2f716cba1f3c6fda7a32c5c8a07f7b13d373778e5c6.jpg)

![640d3bf6f123552c0b67d7ba8c4b643cab34c0464c103612f2f896717b5c48fb.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/640d3bf6f123552c0b67d7ba8c4b643cab34c0464c103612f2f896717b5c48fb.jpg)

![690c341bfc0e4057ac23f3b696e5e01e652ef40817875b14dcf430465c3e73d6.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/690c341bfc0e4057ac23f3b696e5e01e652ef40817875b14dcf430465c3e73d6.jpg)

![851552279ab58d21ffa733aa6fa057f12ccca070af09760b77f87979f28d77cb.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/851552279ab58d21ffa733aa6fa057f12ccca070af09760b77f87979f28d77cb.jpg)

![92a154be2422da25496dd38580519dde76aef6736cc917d11c999de5d35a7851.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/92a154be2422da25496dd38580519dde76aef6736cc917d11c999de5d35a7851.jpg)

![a8bad910768ec7dd62e6946ab2c65e2ab83a4b66619b114623179a2953cd60ab.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/a8bad910768ec7dd62e6946ab2c65e2ab83a4b66619b114623179a2953cd60ab.jpg)

![b154fc2ad3ba1f04e91c9852fd9c2a989d3331ee69bbe7b561801d63cc42982a.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/b154fc2ad3ba1f04e91c9852fd9c2a989d3331ee69bbe7b561801d63cc42982a.jpg)

![b6e262ed87250dbb41f4ff7acaae729d911fdf673fa14aa84cfa6e379d8c54fb.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/b6e262ed87250dbb41f4ff7acaae729d911fdf673fa14aa84cfa6e379d8c54fb.jpg)

![b94c499cd42cd0cc7bca827fb91a674decb90d51d540502ef0e256ec6396ca13.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/b94c499cd42cd0cc7bca827fb91a674decb90d51d540502ef0e256ec6396ca13.jpg)

![c8e00f4a2ca85bed13bbc8cd25a831c1979ac0512a5a3fd30e4e6d06ca719ee2.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/c8e00f4a2ca85bed13bbc8cd25a831c1979ac0512a5a3fd30e4e6d06ca719ee2.jpg)

![d9efb0a03d6db4caae0df54cce205dbf5abbe593fd7769b1759080b1efd5acbf.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/d9efb0a03d6db4caae0df54cce205dbf5abbe593fd7769b1759080b1efd5acbf.jpg)

![da6637bdea4972e9fd08d9a35c63a0c1c0c06f324fbbe3ab116ed56356e3d19f.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/da6637bdea4972e9fd08d9a35c63a0c1c0c06f324fbbe3ab116ed56356e3d19f.jpg)

![e844ffc282ca98a6313b37b3b2160ee56e0f948d976757e396b11d74c47ca497.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/e844ffc282ca98a6313b37b3b2160ee56e0f948d976757e396b11d74c47ca497.jpg)

![f581d6e4ea7e43239bb212a39d8137f9c521466976582c0e5a295eebf8f5eca3.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/f581d6e4ea7e43239bb212a39d8137f9c521466976582c0e5a295eebf8f5eca3.jpg)

![fb174ae7fe5b594a5f322ca1ded07bc74817e6f4cbc803881419f4bd982ac917.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/fb174ae7fe5b594a5f322ca1ded07bc74817e6f4cbc803881419f4bd982ac917.jpg)

![fc1b808b25b8010a6f37340ab685d606651c31c9fa2177d2ac38b551b70afa4e.jpg](../nips_results/404_Language%20Modeling%20by%20Language%20Models/tables/fc1b808b25b8010a6f37340ab685d606651c31c9fa2177d2ac38b551b70afa4e.jpg)

## Stable Gradients for Stable Learning at Scale in Deep Reinforcement Learning


### Images

![0bc466b052c3c92d4cc84959e7a4ee1eb12455cdd2bce3784caf7f33f716f7d9.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/0bc466b052c3c92d4cc84959e7a4ee1eb12455cdd2bce3784caf7f33f716f7d9.jpg)

![181692d57edd431f9d284c8dfa70b9fd9875588a08422ef7c5a7decb15795a48.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/181692d57edd431f9d284c8dfa70b9fd9875588a08422ef7c5a7decb15795a48.jpg)

![1e236ff162da2f3081fafa8d970ba751dd3af2fbd5f77492334a65b992e9bc65.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/1e236ff162da2f3081fafa8d970ba751dd3af2fbd5f77492334a65b992e9bc65.jpg)

![28e7ccae34d46ac77d0f561dcadc840d69935068a505a317c7530f181408bedd.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/28e7ccae34d46ac77d0f561dcadc840d69935068a505a317c7530f181408bedd.jpg)

![4a8d457769ca90a5319e0b68329737dc02a826f1352ffbc07b82e62d95ad57f9.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/4a8d457769ca90a5319e0b68329737dc02a826f1352ffbc07b82e62d95ad57f9.jpg)

![4ad0163a893623cc9dd2ed7c215a7a794707e7c0dc3653d18b1b3fa235e2b2a4.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/4ad0163a893623cc9dd2ed7c215a7a794707e7c0dc3653d18b1b3fa235e2b2a4.jpg)

![4b23515e24ceeb8c53883635c7d04eb787226fa2d255a38f9d0b1f087384d16e.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/4b23515e24ceeb8c53883635c7d04eb787226fa2d255a38f9d0b1f087384d16e.jpg)

![4f3aac3112482cc6b6eab823ed6adaf7cafeb7928a0907709037e898485a3025.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/4f3aac3112482cc6b6eab823ed6adaf7cafeb7928a0907709037e898485a3025.jpg)

![59388e83891123b659aafde1d25d4d1abd4ee89687e91385b82aafc07ea02c29.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/59388e83891123b659aafde1d25d4d1abd4ee89687e91385b82aafc07ea02c29.jpg)

![64486b110aa0dfe14956f1b1aa63348d38cdaafbe8e1024b33ff6eb6f8b9a5a7.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/64486b110aa0dfe14956f1b1aa63348d38cdaafbe8e1024b33ff6eb6f8b9a5a7.jpg)

![6477b1245283f0c88a73dbc20d13e05b49076970e9ca134f0400f3dfc86a8865.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/6477b1245283f0c88a73dbc20d13e05b49076970e9ca134f0400f3dfc86a8865.jpg)

![6b36c233adcc39175bdcf0caa9c33241a714642193da1653e056b2733fcdd48d.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/6b36c233adcc39175bdcf0caa9c33241a714642193da1653e056b2733fcdd48d.jpg)

![843418dc9b89a86ba7cd34b87dc53601d1915d76f0b4ac22fbc836c01259d670.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/843418dc9b89a86ba7cd34b87dc53601d1915d76f0b4ac22fbc836c01259d670.jpg)

![84650c2f1c75146fc97ba4232c0821d1979f4e36dc97bdc8cbab6d9aec44f199.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/84650c2f1c75146fc97ba4232c0821d1979f4e36dc97bdc8cbab6d9aec44f199.jpg)

![8f121f135a57ba541c8e5a42c514710639039dea6d7b130487053ebfbf75c2c0.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/8f121f135a57ba541c8e5a42c514710639039dea6d7b130487053ebfbf75c2c0.jpg)

![9aade409263ce3c6972f98d8cc534d8f47d739c6a1d4a03dcd5a09991dce466a.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/9aade409263ce3c6972f98d8cc534d8f47d739c6a1d4a03dcd5a09991dce466a.jpg)

![af067ba90e6ac8f0b263ba5570f18ea4cb9106d29d980f4debe440a6362820bd.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/af067ba90e6ac8f0b263ba5570f18ea4cb9106d29d980f4debe440a6362820bd.jpg)

![bb990923f1879dc1f25e780237df1cd0ad888f849758f0f67cc3e2a7812f1579.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/bb990923f1879dc1f25e780237df1cd0ad888f849758f0f67cc3e2a7812f1579.jpg)

![beb9fed62673042ec92a7c97d7350bd4d320efd52c7229fe1f8062de02901bc3.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/beb9fed62673042ec92a7c97d7350bd4d320efd52c7229fe1f8062de02901bc3.jpg)

![c68f7b5a0b901967b9c06e55a3039815d1da4be85367be7edf4049d4c880ab68.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/c68f7b5a0b901967b9c06e55a3039815d1da4be85367be7edf4049d4c880ab68.jpg)

![d0bfd30011269d4899b81e2e33c55e64ee7b991441ed281d244df19787ff7722.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/d0bfd30011269d4899b81e2e33c55e64ee7b991441ed281d244df19787ff7722.jpg)

![f460a87e033171868ac166df1f62731c4efcbf49a57163b061cf862aa4224751.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/f460a87e033171868ac166df1f62731c4efcbf49a57163b061cf862aa4224751.jpg)

![f6b2d55afed226ff0e3183468fb5f45c8191dfc0b1ddf52c82c2f81a7a07af5e.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/f6b2d55afed226ff0e3183468fb5f45c8191dfc0b1ddf52c82c2f81a7a07af5e.jpg)

![fdddd8e42179f23d3305afb869dbebfe44bf07bf1fca7e57aaa162e6f77ccb66.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/images/fdddd8e42179f23d3305afb869dbebfe44bf07bf1fca7e57aaa162e6f77ccb66.jpg)

### Tables

![35b904c3d1ae17076176f4b53fc8fefc3c79340e9bd7878c4aa373d305667607.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/35b904c3d1ae17076176f4b53fc8fefc3c79340e9bd7878c4aa373d305667607.jpg)

![368c83b374984bf4679ccc97763e9bff85ebba9f51ef3dff1c98abc55d9f746b.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/368c83b374984bf4679ccc97763e9bff85ebba9f51ef3dff1c98abc55d9f746b.jpg)

![3bb20169b35f2bea8022ec2bb0bad8f69b381e8468d319b5a09d1318845dd035.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/3bb20169b35f2bea8022ec2bb0bad8f69b381e8468d319b5a09d1318845dd035.jpg)

![3bb2336ae297ba7961343f1bc8c5ac9e06b2b343e4d3b71c7320fadf5abe5441.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/3bb2336ae297ba7961343f1bc8c5ac9e06b2b343e4d3b71c7320fadf5abe5441.jpg)

![530d773926c42273ef86f166e0db0da34003a7b1671fed505c10aaff6b0b7aa2.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/530d773926c42273ef86f166e0db0da34003a7b1671fed505c10aaff6b0b7aa2.jpg)

![533d57b50521d75e0f185cce858f61356b6cb510577e8b9989c2029627dee63e.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/533d57b50521d75e0f185cce858f61356b6cb510577e8b9989c2029627dee63e.jpg)

![68d0a22e57c4c22cfac4ef7bd7ae1ea7ff8fd10906d6410263a5b58f716eade4.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/68d0a22e57c4c22cfac4ef7bd7ae1ea7ff8fd10906d6410263a5b58f716eade4.jpg)

![8bbafb2401661230e513a4c5c8be3a5c4c794ad941a990166bb769f3bcf1c282.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/8bbafb2401661230e513a4c5c8be3a5c4c794ad941a990166bb769f3bcf1c282.jpg)

![a1a9bf10dd98782917401a097cf9e5a72f989fc2eda65c888524ee2ea500ffa8.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/a1a9bf10dd98782917401a097cf9e5a72f989fc2eda65c888524ee2ea500ffa8.jpg)

![be4fea04630459578aea2772cd5187095bdf867a52ef0d7c8d4637fff8a3c306.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/be4fea04630459578aea2772cd5187095bdf867a52ef0d7c8d4637fff8a3c306.jpg)

![ca52b2f67d25425a1c2ade7fcfdff246c416da29fe290bd2b380aa00bfc0b71b.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/ca52b2f67d25425a1c2ade7fcfdff246c416da29fe290bd2b380aa00bfc0b71b.jpg)

![d6b62053dabe68f86b8868fac12c5b7322e46c92106a68fdf416064f6577b933.jpg](../nips_results/405_Stable%20Gradients%20for%20Stable%20Learning%20at%20Scale%20in%20Deep%20Reinforcement%20Learning/tables/d6b62053dabe68f86b8868fac12c5b7322e46c92106a68fdf416064f6577b933.jpg)

## LoRAShop: Training-Free Multi-Concept Image Generation and Editing with Rectified Flow Transformers


### Images

![00c01f93deb19e746e7dc05d1be0ed2e154980cae172fb7c9afcd644bd347150.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/00c01f93deb19e746e7dc05d1be0ed2e154980cae172fb7c9afcd644bd347150.jpg)

![05c07e5fe71cfbf565c1e56305e1899572c00f8503ea6e2e6bc44bd91c98ae49.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/05c07e5fe71cfbf565c1e56305e1899572c00f8503ea6e2e6bc44bd91c98ae49.jpg)

![1fe57ba62661cef6ed2dce6b884d23f4433c2bf2d07765159bc4d2d49417e441.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/1fe57ba62661cef6ed2dce6b884d23f4433c2bf2d07765159bc4d2d49417e441.jpg)

![2e855ee4089470c7bb9bd2abb34ea2d343d0bebe5811a5f6c4044dfeb1647bc5.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/2e855ee4089470c7bb9bd2abb34ea2d343d0bebe5811a5f6c4044dfeb1647bc5.jpg)

![320142cdb69e073e698c8df75fac7806ed46c5fc343cb7459e1c8eba27d4b217.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/320142cdb69e073e698c8df75fac7806ed46c5fc343cb7459e1c8eba27d4b217.jpg)

![53477eb699f404f3078ae8945ddc7a05d1601cd12df32728a52cf785c59d0b96.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/53477eb699f404f3078ae8945ddc7a05d1601cd12df32728a52cf785c59d0b96.jpg)

![657421cae07b7f0094b5dabeb399a6204aa0e93cba073c20eceea813134e0766.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/657421cae07b7f0094b5dabeb399a6204aa0e93cba073c20eceea813134e0766.jpg)

![7773a007dbe7302dfc841dfa099c7aa46594d0f6f819bde3ce673394c8a82cb9.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/7773a007dbe7302dfc841dfa099c7aa46594d0f6f819bde3ce673394c8a82cb9.jpg)

![946c210a340f231e3ddafe8fea03fc029d2e2ac39a17a6178e58d8eb8f86b22a.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/946c210a340f231e3ddafe8fea03fc029d2e2ac39a17a6178e58d8eb8f86b22a.jpg)

![9973cde380a96ebf70e5bbda40e05485ae2e31d9eb4db76d88b7e7b2b18a938a.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/9973cde380a96ebf70e5bbda40e05485ae2e31d9eb4db76d88b7e7b2b18a938a.jpg)

![9ae65d85ad3bb20f9f269e2dffec212b7d26415d9c3b82f00d9c2209d924f82c.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/9ae65d85ad3bb20f9f269e2dffec212b7d26415d9c3b82f00d9c2209d924f82c.jpg)

![a41672f7b3ab325ed4719db8134920040ee1eafd017384583eebec597f20f9ca.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/a41672f7b3ab325ed4719db8134920040ee1eafd017384583eebec597f20f9ca.jpg)

![a4e124ef20040397d6047c55922f7cf1407615175e44e1e9c57ce90cb5ebfdaf.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/a4e124ef20040397d6047c55922f7cf1407615175e44e1e9c57ce90cb5ebfdaf.jpg)

![afb70123345a48f3d5f9ce31177423abea208a64adddc86e0c0e4c0eac239339.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/afb70123345a48f3d5f9ce31177423abea208a64adddc86e0c0e4c0eac239339.jpg)

![cbea55e7194e343203994e656f71750ec405d3e167591f63371068687c37a813.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/cbea55e7194e343203994e656f71750ec405d3e167591f63371068687c37a813.jpg)

![ff56fa60c01b58208e16cb57273e831bca5aacaf120f7585332e594494ca3cbf.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/images/ff56fa60c01b58208e16cb57273e831bca5aacaf120f7585332e594494ca3cbf.jpg)

### Tables

![0fea58e0c2f58dc46f6c3f4a3114d7f8c669783ff73dd29f21ca6f1039d70aaf.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/0fea58e0c2f58dc46f6c3f4a3114d7f8c669783ff73dd29f21ca6f1039d70aaf.jpg)

![256a78a0bb44c2222af41dee66818ccc13749393fccdb812b87cc77b9c7de51e.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/256a78a0bb44c2222af41dee66818ccc13749393fccdb812b87cc77b9c7de51e.jpg)

![7814dcf1ece65d3bc62d2cdb9824d049131f8d055913ac575cb67243b2503668.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/7814dcf1ece65d3bc62d2cdb9824d049131f8d055913ac575cb67243b2503668.jpg)

![91b4751a9d724ea49025302c750ac5ab57d53e07d8cb0af580770a5e2c5f41e1.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/91b4751a9d724ea49025302c750ac5ab57d53e07d8cb0af580770a5e2c5f41e1.jpg)

![91b8da8b33dd3c199b5425b1920af4003efb582c25982320fd03cd50f7fe955d.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/91b8da8b33dd3c199b5425b1920af4003efb582c25982320fd03cd50f7fe955d.jpg)

![a37d5f0bb2c92058e9c807c9be22f643a5586a1bbbd508b4dd325c2902bbb018.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/a37d5f0bb2c92058e9c807c9be22f643a5586a1bbbd508b4dd325c2902bbb018.jpg)

![ad1ba81d42079ddb233899ee09647d4fef9afe4661cb639b343e7b0ebd87432c.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/ad1ba81d42079ddb233899ee09647d4fef9afe4661cb639b343e7b0ebd87432c.jpg)

![afc59100bc5d0ff5e5b9c35410d9eed5f3802a4c3f5e8c36e84a1a772429bb75.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/afc59100bc5d0ff5e5b9c35410d9eed5f3802a4c3f5e8c36e84a1a772429bb75.jpg)

![cb2e28008e57eb8c6c28bf21ab81d866d800e4919d46de442615df77a5166334.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/cb2e28008e57eb8c6c28bf21ab81d866d800e4919d46de442615df77a5166334.jpg)

![d1aea9b4976dc8e13129fdcc08dee4c90d827e17327af173f0d6a4236337648b.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/d1aea9b4976dc8e13129fdcc08dee4c90d827e17327af173f0d6a4236337648b.jpg)

![d7df9ed3069847bd3ce789ffe49d879da2a56a9d6bb86a8655b5b9b85a112fa0.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/d7df9ed3069847bd3ce789ffe49d879da2a56a9d6bb86a8655b5b9b85a112fa0.jpg)

![fdd556329880881cc1a798e9d5684198e113b87129aca24a5c4b88144a1d41ab.jpg](../nips_results/406_LoRAShop_%20Training-Free%20Multi-Concept%20Image%20Generation%20and%20Editing%20with%20Rectified%20Flow%20Transformers/tables/fdd556329880881cc1a798e9d5684198e113b87129aca24a5c4b88144a1d41ab.jpg)

## Distilling LLM Agent into Small Models with Retrieval and Code Tools


### Images

![3d46101d364f4e2676f81ddfe961c788a0dd6536c1158121e810b408fc869405.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/images/3d46101d364f4e2676f81ddfe961c788a0dd6536c1158121e810b408fc869405.jpg)

![664bec40f9ccde5d00f9812726e44d42b8b83e761c46df82cbf6b4e3c7e8032c.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/images/664bec40f9ccde5d00f9812726e44d42b8b83e761c46df82cbf6b4e3c7e8032c.jpg)

![72b8f945fa0bd0a7e11f6931bbde87d39feb11818b44f9a486149418749d5aae.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/images/72b8f945fa0bd0a7e11f6931bbde87d39feb11818b44f9a486149418749d5aae.jpg)

![8384025c1d295bd52191f1d8b637e743726cec717068a5d061ed43f15ff5d7fd.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/images/8384025c1d295bd52191f1d8b637e743726cec717068a5d061ed43f15ff5d7fd.jpg)

![877d9e89500b156e35e647fe5ab9ae53c6720cc4b8ed5d1e50f95585a4c82160.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/images/877d9e89500b156e35e647fe5ab9ae53c6720cc4b8ed5d1e50f95585a4c82160.jpg)

![a5d6568bb31705f6ad8d2cb0c3467233dd7f6466e6026658393c1b052f9b0499.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/images/a5d6568bb31705f6ad8d2cb0c3467233dd7f6466e6026658393c1b052f9b0499.jpg)

![baea4cfa306c15e6803ee4e5283d5083a441d861945a641a970b7a2ad4539d0a.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/images/baea4cfa306c15e6803ee4e5283d5083a441d861945a641a970b7a2ad4539d0a.jpg)

![fefa867624e85a3976ddc9e167c05383e692d52f7497279e5e8e2cd3b5acda12.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/images/fefa867624e85a3976ddc9e167c05383e692d52f7497279e5e8e2cd3b5acda12.jpg)

### Tables

![130d95baca41403100bbf03a07a30bcf944fc8cf01fac93d64d00e6a5e05950e.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/tables/130d95baca41403100bbf03a07a30bcf944fc8cf01fac93d64d00e6a5e05950e.jpg)

![2539ad6ce46e5e5e58a749b5774355d092b8f5b4636a0eb719190518676789f1.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/tables/2539ad6ce46e5e5e58a749b5774355d092b8f5b4636a0eb719190518676789f1.jpg)

![30aebb97789e33ba03dbd9ce9067a537ec1b024f6cd62106282e683b3b9a0b5a.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/tables/30aebb97789e33ba03dbd9ce9067a537ec1b024f6cd62106282e683b3b9a0b5a.jpg)

![368ebf9df218eda8c8516a06aac8f10142a7c4fe17503aa77e8bd5a4cd340bb3.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/tables/368ebf9df218eda8c8516a06aac8f10142a7c4fe17503aa77e8bd5a4cd340bb3.jpg)

![3923f63823517218b3df6bac00bbc5d3d04641987de34f847d8fabf997bb0e32.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/tables/3923f63823517218b3df6bac00bbc5d3d04641987de34f847d8fabf997bb0e32.jpg)

![4e65aa02f0c785d079c499b05abda4fec1a5101bfc6418dafc8ff005c333d2cb.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/tables/4e65aa02f0c785d079c499b05abda4fec1a5101bfc6418dafc8ff005c333d2cb.jpg)

![5041d97a9000d354d60793720f4854d7b7870c4938590e7fbc03c04c25b5b43b.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/tables/5041d97a9000d354d60793720f4854d7b7870c4938590e7fbc03c04c25b5b43b.jpg)

![54923127e3d16a9a1ec60812ad8393537aed29d8e42647e5cf31ff7a981f10ec.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/tables/54923127e3d16a9a1ec60812ad8393537aed29d8e42647e5cf31ff7a981f10ec.jpg)

![6263d34d3b2fd929f81ec89c1b8a2daa7b581338ba7ca99e0dc864a1b689b5af.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/tables/6263d34d3b2fd929f81ec89c1b8a2daa7b581338ba7ca99e0dc864a1b689b5af.jpg)

![8c616ad28de98df4ff35f6c7e992f8b7cb6d990d97b0b5f86e233be1085aa594.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/tables/8c616ad28de98df4ff35f6c7e992f8b7cb6d990d97b0b5f86e233be1085aa594.jpg)

![eb1600313e6c703b9162e15530845e12c701c6f67f7230f597c0b4c48c5344d0.jpg](../nips_results/407_Distilling%20LLM%20Agent%20into%20Small%20Models%20with%20Retrieval%20and%20Code%20Tools/tables/eb1600313e6c703b9162e15530845e12c701c6f67f7230f597c0b4c48c5344d0.jpg)

## AdaReasoner: Adaptive Reasoning Enables More Flexible Thinking


### Images

![491f11865c8563bee5421ec593b7093ec6ea32376ae8c63ab1ff76377b7ef70b.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/images/491f11865c8563bee5421ec593b7093ec6ea32376ae8c63ab1ff76377b7ef70b.jpg)

![543d630cc73610f13704827798d7d66c2d32a49c614f1507bd2d061faf57a351.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/images/543d630cc73610f13704827798d7d66c2d32a49c614f1507bd2d061faf57a351.jpg)

![86f3b7c1a7a4acb706f6d0b61d7a3938f2e38384f374b5efc3f8e727ec4a68c0.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/images/86f3b7c1a7a4acb706f6d0b61d7a3938f2e38384f374b5efc3f8e727ec4a68c0.jpg)

![9826c07c572fb4382ded6d01006091538a3bf8137e296e95467cbd2852770c14.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/images/9826c07c572fb4382ded6d01006091538a3bf8137e296e95467cbd2852770c14.jpg)

![e2b3a5b8fdccd87ffdbb417660333bf5d137080002af7bed923b839a653cdda3.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/images/e2b3a5b8fdccd87ffdbb417660333bf5d137080002af7bed923b839a653cdda3.jpg)

![e7f0c41b73486690dc82cf60f25e441005dc095c5ec10a21a1cbb1fe6c2d9984.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/images/e7f0c41b73486690dc82cf60f25e441005dc095c5ec10a21a1cbb1fe6c2d9984.jpg)

![f37223feace0433fbbad651ef261c9df9b67f0b1e2bcdcc86e283bec812c4b74.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/images/f37223feace0433fbbad651ef261c9df9b67f0b1e2bcdcc86e283bec812c4b74.jpg)

### Tables

![01acb9fc9e939d19894c4de39cdb32f3b4dee0b4450a23236967001d75062fc9.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/tables/01acb9fc9e939d19894c4de39cdb32f3b4dee0b4450a23236967001d75062fc9.jpg)

![0af88d2ae110b94f89b3504b91f05f796beb9e1102f8355facb7bc7cb8e21faf.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/tables/0af88d2ae110b94f89b3504b91f05f796beb9e1102f8355facb7bc7cb8e21faf.jpg)

![36663f169bbb4b267439a1d3848386bc29f04f6aefc992734fc53dae87cc2b72.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/tables/36663f169bbb4b267439a1d3848386bc29f04f6aefc992734fc53dae87cc2b72.jpg)

![7139ba2ac4cb21a21aad2f39c7c7275815d00bd05d38f8651308714ed2d7f08b.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/tables/7139ba2ac4cb21a21aad2f39c7c7275815d00bd05d38f8651308714ed2d7f08b.jpg)

![7e271c8b98fd52fb42aaa5391cc0a35ff338f8166bae5ba1508b5186880b42c6.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/tables/7e271c8b98fd52fb42aaa5391cc0a35ff338f8166bae5ba1508b5186880b42c6.jpg)

![8112248cdfb2de1dd71391c3cef64ed5d662770fcd07d02d35fab73af7379e2e.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/tables/8112248cdfb2de1dd71391c3cef64ed5d662770fcd07d02d35fab73af7379e2e.jpg)

![87b7ebf171ab08bf63fb1e6a69c95ea207b087cfcb00b4f75f15583ff348aab2.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/tables/87b7ebf171ab08bf63fb1e6a69c95ea207b087cfcb00b4f75f15583ff348aab2.jpg)

![a8897c22dbbfdd80af868053965d22544285d003be1c36352edde6c7a1b6e37c.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/tables/a8897c22dbbfdd80af868053965d22544285d003be1c36352edde6c7a1b6e37c.jpg)

![ae8320eaeea3d66d279d0aa5541bdfb4213d30123e76e731f077a525b0d8d947.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/tables/ae8320eaeea3d66d279d0aa5541bdfb4213d30123e76e731f077a525b0d8d947.jpg)

![d64d57a5d16619bc44be1b4f54527855c3f63c0ffaacc73990dfb2e5caa31f9b.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/tables/d64d57a5d16619bc44be1b4f54527855c3f63c0ffaacc73990dfb2e5caa31f9b.jpg)

![d8a5af5c3fb8324f0dd78ba5aacf9d4f07cdc2c92d67be65d2e603dfe5b9be51.jpg](../nips_results/408_AdaReasoner_%20Adaptive%20Reasoning%20Enables%20More%20Flexible%20Thinking/tables/d8a5af5c3fb8324f0dd78ba5aacf9d4f07cdc2c92d67be65d2e603dfe5b9be51.jpg)

## Shallow Diffuse: Robust and Invisible Watermarking through Low-Dim Subspaces in Diffusion Models


### Images

![1eedb7b6ffa6299060c32b0fd0ffb9882ef7c71d6a9b2a8fbcbac820c0a907ea.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/images/1eedb7b6ffa6299060c32b0fd0ffb9882ef7c71d6a9b2a8fbcbac820c0a907ea.jpg)

![532b2e459d81e243f97162ea5c484e63a8adef86ecf39c253cca074f869afdf7.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/images/532b2e459d81e243f97162ea5c484e63a8adef86ecf39c253cca074f869afdf7.jpg)

![65c667068f5242a321b856aabeb7e7beba514334443fa099db8b60797ad09134.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/images/65c667068f5242a321b856aabeb7e7beba514334443fa099db8b60797ad09134.jpg)

![703f7602f642aa354858ee8cf929888d672a45001a93ac0cb937cd0f4f1b62de.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/images/703f7602f642aa354858ee8cf929888d672a45001a93ac0cb937cd0f4f1b62de.jpg)

![7b79c774a8f559067cf1939ef038ad874c7aea6dd9625772bce5e568d9721f2b.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/images/7b79c774a8f559067cf1939ef038ad874c7aea6dd9625772bce5e568d9721f2b.jpg)

![b15732a5be82adff68fd97e31b4f642fdab8583f359b8114e5d87cd669a53ee7.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/images/b15732a5be82adff68fd97e31b4f642fdab8583f359b8114e5d87cd669a53ee7.jpg)

![b7ac7004a785241d2abdf2c50a10c7b64e7bb5ca91d2dfaae068f26db8b87b4e.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/images/b7ac7004a785241d2abdf2c50a10c7b64e7bb5ca91d2dfaae068f26db8b87b4e.jpg)

### Tables

![188f271e4be688f23d9bae02948bbba877dd6630d96cca5b9bf16473b92a1e0a.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/188f271e4be688f23d9bae02948bbba877dd6630d96cca5b9bf16473b92a1e0a.jpg)

![1a937561881759ce8cc8c5e0eef91fd252a2aca69f2f40a0870dd63f94b22e92.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/1a937561881759ce8cc8c5e0eef91fd252a2aca69f2f40a0870dd63f94b22e92.jpg)

![39e93625b303f2902b7c88bca3625e030f53387efeec38358ec3246b1bac88ca.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/39e93625b303f2902b7c88bca3625e030f53387efeec38358ec3246b1bac88ca.jpg)

![475cc8b6d01173d51caa4fd0dcfeadd19f5198feeee2034f66564a5b635ccf29.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/475cc8b6d01173d51caa4fd0dcfeadd19f5198feeee2034f66564a5b635ccf29.jpg)

![6a3facc905859e04dca1d5e72af62a77d2aba417b80cb566db2a340caa19c4e9.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/6a3facc905859e04dca1d5e72af62a77d2aba417b80cb566db2a340caa19c4e9.jpg)

![725b929e6213e9cee69ace1e7399f9d91696a82887a43da6a92bac86878b7c71.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/725b929e6213e9cee69ace1e7399f9d91696a82887a43da6a92bac86878b7c71.jpg)

![78e643fe5db092a5cd4010f8989694e66d8214d32393378955a8096e25efee1c.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/78e643fe5db092a5cd4010f8989694e66d8214d32393378955a8096e25efee1c.jpg)

![8d6e138d6d7c63a7bd80efc2bf0e78a6d2735a6372b2af7adf6ad1a9041b65be.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/8d6e138d6d7c63a7bd80efc2bf0e78a6d2735a6372b2af7adf6ad1a9041b65be.jpg)

![916a58c72c0422d650c8ff3c9037e33e4529a03efa903bbe5a0e322e4837bf08.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/916a58c72c0422d650c8ff3c9037e33e4529a03efa903bbe5a0e322e4837bf08.jpg)

![9e60aa7f57247a8e2a49d8f978c971ba20592a77c074386d19de05ae79a7b9a9.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/9e60aa7f57247a8e2a49d8f978c971ba20592a77c074386d19de05ae79a7b9a9.jpg)

![cd41de036cbf2ed1d0f07e0ef14dec1a516d1b222b05ab5a6fc7dd16804b4323.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/cd41de036cbf2ed1d0f07e0ef14dec1a516d1b222b05ab5a6fc7dd16804b4323.jpg)

![dc7ef0c0295cfe19d93362847a087cca6d587e6afda991aaa022c6911ff07e8d.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/dc7ef0c0295cfe19d93362847a087cca6d587e6afda991aaa022c6911ff07e8d.jpg)

![e1bc7e8b950997350d68a14482dc01f53b9ca786101018667994ce213cf90d14.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/e1bc7e8b950997350d68a14482dc01f53b9ca786101018667994ce213cf90d14.jpg)

![ecb8d183585c052162bfc0bccd48cae97861885a0f982a794c4b514965049348.jpg](../nips_results/409_Shallow%20Diffuse_%20Robust%20and%20Invisible%20Watermarking%20through%20Low-Dim%20Subspaces%20in%20Diffusion%20Models/tables/ecb8d183585c052162bfc0bccd48cae97861885a0f982a794c4b514965049348.jpg)

## Twilight: Adaptive Attention Sparsity with Hierarchical Top-$p$  Pruning


### Images

![0211d3550ad80af370e7574f4c41c2ee50f5c23b95c6a9a42267b37f9e3db678.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/0211d3550ad80af370e7574f4c41c2ee50f5c23b95c6a9a42267b37f9e3db678.jpg)

![29dbd7091a6ff16ac83385856033684047014cc47ac59d15027ee808ae92cd4f.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/29dbd7091a6ff16ac83385856033684047014cc47ac59d15027ee808ae92cd4f.jpg)

![4460a8b5d99158ed043707df1f47683db70175f96d3a09a74d1b0552f703e20e.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/4460a8b5d99158ed043707df1f47683db70175f96d3a09a74d1b0552f703e20e.jpg)

![482208ad28d7f8a9af241b512395e8c3903d14209ffb43517663d0e3dce565b9.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/482208ad28d7f8a9af241b512395e8c3903d14209ffb43517663d0e3dce565b9.jpg)

![844c8f2eda592b3cc32036d81bc569a56b5d6ff70adb2d98faebf6b5c37d57b6.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/844c8f2eda592b3cc32036d81bc569a56b5d6ff70adb2d98faebf6b5c37d57b6.jpg)

![920058ce9b6f12f216ebb1bf8a1378e8421d43273f4ee6121de16aafa0aeb039.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/920058ce9b6f12f216ebb1bf8a1378e8421d43273f4ee6121de16aafa0aeb039.jpg)

![95b3404018975087b7f65a0df32e0c5a90ffa4694ccf504aae7b0a135afbd164.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/95b3404018975087b7f65a0df32e0c5a90ffa4694ccf504aae7b0a135afbd164.jpg)

![9cebeb9dbcc6e273420f9f48683c24bfc23727f7960d1d91afae2cc7bac6dadb.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/9cebeb9dbcc6e273420f9f48683c24bfc23727f7960d1d91afae2cc7bac6dadb.jpg)

![a786eebcdc5c03594c5b1dc0f7cc72d8dd3ef80de5a19f1dbede93f338ce92c2.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/a786eebcdc5c03594c5b1dc0f7cc72d8dd3ef80de5a19f1dbede93f338ce92c2.jpg)

![d810402ef9a34b0b2ba02d885ce7e0eef5603ddfbb4f603418a2fcbe0b3be79b.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/d810402ef9a34b0b2ba02d885ce7e0eef5603ddfbb4f603418a2fcbe0b3be79b.jpg)

![f34e89938d894f33a42270e700e1cc4d558a8d8802f5b1c024af433e0c041811.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/f34e89938d894f33a42270e700e1cc4d558a8d8802f5b1c024af433e0c041811.jpg)

![f97b6c3f54d7199b66b34bf725f3b0293f5eeceaf16b212bab879453861eb961.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/f97b6c3f54d7199b66b34bf725f3b0293f5eeceaf16b212bab879453861eb961.jpg)

![fc77cf2efde7f12c5f2e15aa37a742266a7c229c842ad981cd000752204121e5.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/images/fc77cf2efde7f12c5f2e15aa37a742266a7c229c842ad981cd000752204121e5.jpg)

### Tables

![49884a3b6e9ddd333387a6a9a8a051cbe184589cbf4e1853dc88d9c6e03ba317.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/tables/49884a3b6e9ddd333387a6a9a8a051cbe184589cbf4e1853dc88d9c6e03ba317.jpg)

![4a737632288f94097d8b153d1703389a3c3d8f4a64b77d748459da2c18739422.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/tables/4a737632288f94097d8b153d1703389a3c3d8f4a64b77d748459da2c18739422.jpg)

![bb40efd23f946bfe69586eadaf7416ef2e0c441d6584dbeb253a23ea9a985ad3.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/tables/bb40efd23f946bfe69586eadaf7416ef2e0c441d6584dbeb253a23ea9a985ad3.jpg)

![bf06742d9be75a8e770fe4153fcd323efdeb9e857b2962acbc087cd9e7579ea2.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/tables/bf06742d9be75a8e770fe4153fcd323efdeb9e857b2962acbc087cd9e7579ea2.jpg)

![e7a05484e9b5dea50092734d8c3d6f04727df1dc380c543e1c39b4e4491d6728.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/tables/e7a05484e9b5dea50092734d8c3d6f04727df1dc380c543e1c39b4e4491d6728.jpg)

![e88d00b6ea226c1ac1b33951a49c233382d9aadc1e96581cb2cc3923535621b6.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/tables/e88d00b6ea226c1ac1b33951a49c233382d9aadc1e96581cb2cc3923535621b6.jpg)

![f450cae924790d48b27a80afe052f2322cc78a8e19e31cf1d04192c853f08d18.jpg](../nips_results/410_Twilight_%20Adaptive%20Attention%20Sparsity%20with%20Hierarchical%20Top-%24p%24%20%20Pruning/tables/f450cae924790d48b27a80afe052f2322cc78a8e19e31cf1d04192c853f08d18.jpg)

## Joint Hierarchical Representation Learning of Samples and Features via Informed Tree-Wasserstein Distance


### Images

![0050f545f0135949d5192ac4cb205f6c837298d6ff17493e25a13387f9afd4d1.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/images/0050f545f0135949d5192ac4cb205f6c837298d6ff17493e25a13387f9afd4d1.jpg)

![128cfee357c0d9964a3822407b13331c020030ac9b89c26082dc60368889b61f.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/images/128cfee357c0d9964a3822407b13331c020030ac9b89c26082dc60368889b61f.jpg)

![351721e582edb1d88ae91287d14f58da8868a881187417fb46bbcd5ecd7e32ef.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/images/351721e582edb1d88ae91287d14f58da8868a881187417fb46bbcd5ecd7e32ef.jpg)

![36d5d5c666214c8fcb026a6a74179d8dc4cb327b2dc3a2ba143788682fc836d3.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/images/36d5d5c666214c8fcb026a6a74179d8dc4cb327b2dc3a2ba143788682fc836d3.jpg)

![3ca7375367bcb7f358e9f9ade57abb85bda0a72da39d605eb5bf606b91ae1654.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/images/3ca7375367bcb7f358e9f9ade57abb85bda0a72da39d605eb5bf606b91ae1654.jpg)

![452e349c27e323fa69d282e6939298df1697569b12e9ff5011704ad13338bca2.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/images/452e349c27e323fa69d282e6939298df1697569b12e9ff5011704ad13338bca2.jpg)

![52dd9d9578f491599deb0ceeefadb284a138f483575a9cab80154cb49e71fbc8.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/images/52dd9d9578f491599deb0ceeefadb284a138f483575a9cab80154cb49e71fbc8.jpg)

![5412a13989e0a7004c0b7f015ebd8a28f53ddb7dc83381e4b6a4c96ab818fc9b.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/images/5412a13989e0a7004c0b7f015ebd8a28f53ddb7dc83381e4b6a4c96ab818fc9b.jpg)

![b4438e1f6e69d8c98d3b2b7a695398b22c28e76c59321d037e817a760ec70b07.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/images/b4438e1f6e69d8c98d3b2b7a695398b22c28e76c59321d037e817a760ec70b07.jpg)

![c660268b1240860480c0e87658df6a0dccfaef771dee1cadcee478a728bed4d0.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/images/c660268b1240860480c0e87658df6a0dccfaef771dee1cadcee478a728bed4d0.jpg)

![c85eab6da931038bf2f7e60eff8fbc0d5455e1f553bf045e954ae05419bf4c16.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/images/c85eab6da931038bf2f7e60eff8fbc0d5455e1f553bf045e954ae05419bf4c16.jpg)

### Tables

![0d1f504df02d270a2e207176e1bbcf8b03d804a44cd1c321a0611571ed5a3c06.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/0d1f504df02d270a2e207176e1bbcf8b03d804a44cd1c321a0611571ed5a3c06.jpg)

![1d64a8883cafe4801692cf5b574c46a7fa193c4aec79396f4f1f145801ca06dc.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/1d64a8883cafe4801692cf5b574c46a7fa193c4aec79396f4f1f145801ca06dc.jpg)

![1f896e594725fb5590394c4ade440a0d2349cbca080c7add972fc24cea3e2eb4.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/1f896e594725fb5590394c4ade440a0d2349cbca080c7add972fc24cea3e2eb4.jpg)

![29dbe10c2c0bdf6b9d487262a6f516595ba57b02d06ea47bc0fa9fb276e63a4b.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/29dbe10c2c0bdf6b9d487262a6f516595ba57b02d06ea47bc0fa9fb276e63a4b.jpg)

![323306845368902781e71c38aa4ef25765d8d5c4eec6bd09421dbdc6ea6caf21.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/323306845368902781e71c38aa4ef25765d8d5c4eec6bd09421dbdc6ea6caf21.jpg)

![3f02ac197641a687de495b9a905864ec3e3fcaeb9e1e5272d24b72642fe7ba73.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/3f02ac197641a687de495b9a905864ec3e3fcaeb9e1e5272d24b72642fe7ba73.jpg)

![46254474dfae12debc90da2b8bd6d46612162a7e94237c032ac6f24e15269584.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/46254474dfae12debc90da2b8bd6d46612162a7e94237c032ac6f24e15269584.jpg)

![7a12057b0db94d054a411408e78faf646aec66b8f29814a185eddab493757f58.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/7a12057b0db94d054a411408e78faf646aec66b8f29814a185eddab493757f58.jpg)

![7a840303457a58203832547d21d42fc8826cc249012720b1bacca4c58b8658c2.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/7a840303457a58203832547d21d42fc8826cc249012720b1bacca4c58b8658c2.jpg)

![8a0ae694e883ab28b53ead38137cc34526068fb7b13c5868388a54a7ef02581d.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/8a0ae694e883ab28b53ead38137cc34526068fb7b13c5868388a54a7ef02581d.jpg)

![8e71245129977f706079601cb79a6f2d91b2883d5ae8107bec50e28ae6dcb048.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/8e71245129977f706079601cb79a6f2d91b2883d5ae8107bec50e28ae6dcb048.jpg)

![9cacf41d744cd38d80ec11314daf4581e2654c7373117c4e806288e32522334e.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/9cacf41d744cd38d80ec11314daf4581e2654c7373117c4e806288e32522334e.jpg)

![b741b36367e280471aa89377dd2f8f829d57bccc7491b360be52677f7f2c0209.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/b741b36367e280471aa89377dd2f8f829d57bccc7491b360be52677f7f2c0209.jpg)

![b813342b337441589dc936f3d8b642606278d7002b58f1933ad5ac0cf55290d4.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/b813342b337441589dc936f3d8b642606278d7002b58f1933ad5ac0cf55290d4.jpg)

![cf953ab4cc10cdd65dbc3679e2ca55a6070c5b7b17c319c94abb759887a0e719.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/cf953ab4cc10cdd65dbc3679e2ca55a6070c5b7b17c319c94abb759887a0e719.jpg)

![d6c56362eb2a81b4f53014ef70330c3dae5385b79f3a81afc06b62755573ea70.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/d6c56362eb2a81b4f53014ef70330c3dae5385b79f3a81afc06b62755573ea70.jpg)

![eebe99008a880d95f650064a42de647b0c34090ecac897efb597f15b36e3bbf5.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/eebe99008a880d95f650064a42de647b0c34090ecac897efb597f15b36e3bbf5.jpg)

![ef8f9a94393e5d216b564575a57033b8017eadafb8036b71c9e26f0ab6b8221a.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/ef8f9a94393e5d216b564575a57033b8017eadafb8036b71c9e26f0ab6b8221a.jpg)

![efb59083e9d917ab13cc04681a811ad3bdad0845e8ceb3b4341570aac2e69e2a.jpg](../nips_results/411_Joint%20Hierarchical%20Representation%20Learning%20of%20Samples%20and%20Features%20via%20Informed%20Tree-Wasserstein%20Dis/tables/efb59083e9d917ab13cc04681a811ad3bdad0845e8ceb3b4341570aac2e69e2a.jpg)

## Towards Reliable Code-as-Policies: A Neuro-Symbolic Framework for Embodied Task Planning


### Images

![26e95f0faae3046821003334b6c761dac03e8ca1f1e4d76a17f3830e59d3bac6.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/images/26e95f0faae3046821003334b6c761dac03e8ca1f1e4d76a17f3830e59d3bac6.jpg)

![30eff560006fbad1cea6a94c3692c50dc41acf92baf328f879d5de0d7fad7a8c.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/images/30eff560006fbad1cea6a94c3692c50dc41acf92baf328f879d5de0d7fad7a8c.jpg)

![311348edb185e8687faeb0020677bb06f4cbaf01bacb34512345cebaa20e6314.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/images/311348edb185e8687faeb0020677bb06f4cbaf01bacb34512345cebaa20e6314.jpg)

![44053c9ff203e762eff9396fd5d514158c83573597a90fdf6208a8c5e3fc1066.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/images/44053c9ff203e762eff9396fd5d514158c83573597a90fdf6208a8c5e3fc1066.jpg)

![7124792398c83b3e6140479a4238f8ee0380e8457f7c3f36e01086e2eb2818de.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/images/7124792398c83b3e6140479a4238f8ee0380e8457f7c3f36e01086e2eb2818de.jpg)

![7f399bf0c12e7788c357024a4bcb1849c86d1b46d897dbef9310315d2cb6ed67.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/images/7f399bf0c12e7788c357024a4bcb1849c86d1b46d897dbef9310315d2cb6ed67.jpg)

![b998790718e5dac0c85b246bc7e3eec32e58482ea49c8976a8bf14fd5ed135bb.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/images/b998790718e5dac0c85b246bc7e3eec32e58482ea49c8976a8bf14fd5ed135bb.jpg)

![d1f017214ea1b379639632e958b7e906f872b2fb4b9edefee62c7e6a9951e340.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/images/d1f017214ea1b379639632e958b7e906f872b2fb4b9edefee62c7e6a9951e340.jpg)

![d31d1629f813a5c738933b9a2d2f8f0dd9e4404c2590fa1c23b9c3b308f9265a.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/images/d31d1629f813a5c738933b9a2d2f8f0dd9e4404c2590fa1c23b9c3b308f9265a.jpg)

![fe0dd1cfa449df30abe4a2ab5f3e295f145cd4b23783fbbfa90aa149f95443bb.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/images/fe0dd1cfa449df30abe4a2ab5f3e295f145cd4b23783fbbfa90aa149f95443bb.jpg)

### Tables

![18452fc624566f36bb1b8f2edc18cfc3f8aad4b777f86f302947c90d6651867b.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/tables/18452fc624566f36bb1b8f2edc18cfc3f8aad4b777f86f302947c90d6651867b.jpg)

![187b94cd25845c932e3bcf6237a6a4bd0d92bda23dcd7d1aaa357185b223898f.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/tables/187b94cd25845c932e3bcf6237a6a4bd0d92bda23dcd7d1aaa357185b223898f.jpg)

![303ab96a5f17a6fc6eb067b770aa237191ccf03ad9a71fdeab35978fd167494e.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/tables/303ab96a5f17a6fc6eb067b770aa237191ccf03ad9a71fdeab35978fd167494e.jpg)

![4753151649b062d60a77b10c69ca5434c789a75720c61d6efbb5c7aa6d4c89e6.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/tables/4753151649b062d60a77b10c69ca5434c789a75720c61d6efbb5c7aa6d4c89e6.jpg)

![52fd30af097e4ae1311ee3b043d2f5426ba93c27e047f546d434ae8d086b617b.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/tables/52fd30af097e4ae1311ee3b043d2f5426ba93c27e047f546d434ae8d086b617b.jpg)

![6e8592b1a5b01ee9eddcfae2915fb3499235fe46f563c55dd1cad63ff808e765.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/tables/6e8592b1a5b01ee9eddcfae2915fb3499235fe46f563c55dd1cad63ff808e765.jpg)

![acb5a674b8199b9b57de2a047f4471b8c5f70bf3505c6d1759e40d989f565a28.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/tables/acb5a674b8199b9b57de2a047f4471b8c5f70bf3505c6d1759e40d989f565a28.jpg)

![c38cdf8b8c99444ace238e4ca1715f51f6ab6de84dcae7bd7cd9e396290407b8.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/tables/c38cdf8b8c99444ace238e4ca1715f51f6ab6de84dcae7bd7cd9e396290407b8.jpg)

![e0269b0808e752b8e12ff513125d7e6a7e185ad5339c0d89dbfcf56e47ce736a.jpg](../nips_results/412_Towards%20Reliable%20Code-as-Policies_%20A%20Neuro-Symbolic%20Framework%20for%20Embodied%20Task%20Planning/tables/e0269b0808e752b8e12ff513125d7e6a7e185ad5339c0d89dbfcf56e47ce736a.jpg)

## ROGR: Relightable 3D Objects using Generative Relighting


### Images

![167f73216856ae559a58f652ec73b816d15cd2986b5b43d0fa7b0d5779856f45.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/images/167f73216856ae559a58f652ec73b816d15cd2986b5b43d0fa7b0d5779856f45.jpg)

![2ed43fb9b87e442221987c49eb67273d04f544b5c81f0cc5b41573f162506dd4.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/images/2ed43fb9b87e442221987c49eb67273d04f544b5c81f0cc5b41573f162506dd4.jpg)

![323a7a4e2bfba7aec9ce1d9f407e3c69b12ce7f6c496bfc4ca45544512666cb7.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/images/323a7a4e2bfba7aec9ce1d9f407e3c69b12ce7f6c496bfc4ca45544512666cb7.jpg)

![35de137d6ace92d371ef76e3767e23e44a091197ac873020cd119c6506bdb3a0.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/images/35de137d6ace92d371ef76e3767e23e44a091197ac873020cd119c6506bdb3a0.jpg)

![430632ff69cbcd78d0dd1b0b2fad68944a8b1c935347da41328db77c2c69e5df.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/images/430632ff69cbcd78d0dd1b0b2fad68944a8b1c935347da41328db77c2c69e5df.jpg)

![b8a61ff06ae9843e755acaf84bf466637adc814a210c832eabfc81071c65a6e8.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/images/b8a61ff06ae9843e755acaf84bf466637adc814a210c832eabfc81071c65a6e8.jpg)

![da71cb2c1cdca7f66066bb37d1c789c6ac8b9a560de95ece8eb6e45ac188d04b.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/images/da71cb2c1cdca7f66066bb37d1c789c6ac8b9a560de95ece8eb6e45ac188d04b.jpg)

![e454adbb9f119f789ca6be0391e29232fc9a896ee85324e974b4ef3e4c390e43.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/images/e454adbb9f119f789ca6be0391e29232fc9a896ee85324e974b4ef3e4c390e43.jpg)

### Tables

![063194b85ca9595721274a412e1bcb9b45b5177ac0c535b3a8e8daab4254da26.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/tables/063194b85ca9595721274a412e1bcb9b45b5177ac0c535b3a8e8daab4254da26.jpg)

![7d9bfd0fef61d1530b9a9fc136b8c302117b66bb1883781f5c756da4740c2664.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/tables/7d9bfd0fef61d1530b9a9fc136b8c302117b66bb1883781f5c756da4740c2664.jpg)

![b097b51e60c81c3b3a22e90ab407a423ba040be32468c0c96d0a06cc7179feca.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/tables/b097b51e60c81c3b3a22e90ab407a423ba040be32468c0c96d0a06cc7179feca.jpg)

![fe7afc0ce9a7c57e49045a22371221bf48dbe852dc04c0ee37cc7034636fe478.jpg](../nips_results/413_ROGR_%20Relightable%203D%20Objects%20using%20Generative%20Relighting/tables/fe7afc0ce9a7c57e49045a22371221bf48dbe852dc04c0ee37cc7034636fe478.jpg)

## Blackbox Model Provenance via Palimpsestic Membership Inference


### Images

![17709de57a407225d51942dce02c8b37f16365f830122739310fa626ab4a71df.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/17709de57a407225d51942dce02c8b37f16365f830122739310fa626ab4a71df.jpg)

![19e77b9775641022ec349ff083f8c6f7ec7fc606db6decdc8e66d83c02eed340.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/19e77b9775641022ec349ff083f8c6f7ec7fc606db6decdc8e66d83c02eed340.jpg)

![28195ccdda1406f61787d1f74832f3db635d335bfbd5758dc37a71381679bfd5.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/28195ccdda1406f61787d1f74832f3db635d335bfbd5758dc37a71381679bfd5.jpg)

![3532c75322c62025b76046b90719e0983c2e847abc48468c500bafff4a790741.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/3532c75322c62025b76046b90719e0983c2e847abc48468c500bafff4a790741.jpg)

![44ee39d1e877b8661bbc77121726845849def968b96210f450acaffeecc1dea4.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/44ee39d1e877b8661bbc77121726845849def968b96210f450acaffeecc1dea4.jpg)

![84ace9492a09867b36bdc35e75957057135e8f3f4f76d2f06722b2fa01487767.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/84ace9492a09867b36bdc35e75957057135e8f3f4f76d2f06722b2fa01487767.jpg)

![8f60c66f3fc4628e34b367541dc12a0fc24a5de9b63d1fd22eb5264300ec5eb1.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/8f60c66f3fc4628e34b367541dc12a0fc24a5de9b63d1fd22eb5264300ec5eb1.jpg)

![9db787e6f299add3b8695a1c2d806f186c5b3cfcb183b478a47141199f26f3b4.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/9db787e6f299add3b8695a1c2d806f186c5b3cfcb183b478a47141199f26f3b4.jpg)

![a6c79d530e4453ad462ad7e72e0c074886da8031d28c8755e2d9b38b90cb93ad.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/a6c79d530e4453ad462ad7e72e0c074886da8031d28c8755e2d9b38b90cb93ad.jpg)

![a9c4cd8d6f554ae74de48344db5b9998c0e150352738a38147e6d523c752d41b.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/a9c4cd8d6f554ae74de48344db5b9998c0e150352738a38147e6d523c752d41b.jpg)

![bbd66cacbad88a85e59f637479e02a3d28821d5dedc147b06091196ddc81d4cb.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/bbd66cacbad88a85e59f637479e02a3d28821d5dedc147b06091196ddc81d4cb.jpg)

![c005ad71f2986df75638dd0e781616efa0a837e3b76a037ac01cd068217ae687.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/c005ad71f2986df75638dd0e781616efa0a837e3b76a037ac01cd068217ae687.jpg)

![c900e5f7250d495ea85e6aaaf249a5314a180423a50a7aa2fd6b8b7142b92b0d.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/c900e5f7250d495ea85e6aaaf249a5314a180423a50a7aa2fd6b8b7142b92b0d.jpg)

![cafa6bbee3f586afac7e87c3c7e7af9a7c2a0897d849fa465d4c99fb6d576ad7.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/cafa6bbee3f586afac7e87c3c7e7af9a7c2a0897d849fa465d4c99fb6d576ad7.jpg)

![ceada75b5b9ada43e08afe99a4cf668eb8ab4a9d18402fe5efa1b5924d7c7e27.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/ceada75b5b9ada43e08afe99a4cf668eb8ab4a9d18402fe5efa1b5924d7c7e27.jpg)

![e748bbe3299e98dd59434b8ecd21f5e879a6772f3cb1e6fe88ebd446370bbb08.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/e748bbe3299e98dd59434b8ecd21f5e879a6772f3cb1e6fe88ebd446370bbb08.jpg)

![f154173bb2328e9a1e5f1cdfef5dbfb27ae7d2f14f733439fcdd0c0ae9356f34.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/images/f154173bb2328e9a1e5f1cdfef5dbfb27ae7d2f14f733439fcdd0c0ae9356f34.jpg)

### Tables

![1650b7035b583c55764de772fe58f4cbde6483065444e38071e8f328f854976d.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/tables/1650b7035b583c55764de772fe58f4cbde6483065444e38071e8f328f854976d.jpg)

![18cbfe96539730a3811582ce1474e876d41546643624d6f16fcb7315313d1595.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/tables/18cbfe96539730a3811582ce1474e876d41546643624d6f16fcb7315313d1595.jpg)

![3c64f57f1978a3bb477c66a4b21e4bb62f7f53093358fb4205c29bcc37a40fa3.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/tables/3c64f57f1978a3bb477c66a4b21e4bb62f7f53093358fb4205c29bcc37a40fa3.jpg)

![3f30d255726f2c5860dd4b05cadf59ca4b28580c91c76290a9654e49988378f3.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/tables/3f30d255726f2c5860dd4b05cadf59ca4b28580c91c76290a9654e49988378f3.jpg)

![4c38c973f9ee75c782c498f7673033341d014acf21f35e9582e7c7b444ccb320.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/tables/4c38c973f9ee75c782c498f7673033341d014acf21f35e9582e7c7b444ccb320.jpg)

![5631ce0efca1894ff27a215ead38dcbfbdb33f734b15a632f7327c08317c67ae.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/tables/5631ce0efca1894ff27a215ead38dcbfbdb33f734b15a632f7327c08317c67ae.jpg)

![663043d03cb3e62d988d6d90b88e9853efa22a465c560715327498c4005e6d87.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/tables/663043d03cb3e62d988d6d90b88e9853efa22a465c560715327498c4005e6d87.jpg)

![72e40caf96b1590ae98b165819ff0853b8ee0f525eb71bfbfff609227b82c84c.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/tables/72e40caf96b1590ae98b165819ff0853b8ee0f525eb71bfbfff609227b82c84c.jpg)

![9de73d5c2af81ae3c60b69030a3f01143dcbd7d0ccbe241eccc7a0dbdce209a5.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/tables/9de73d5c2af81ae3c60b69030a3f01143dcbd7d0ccbe241eccc7a0dbdce209a5.jpg)

![f5fa770e864067c1743d56b4b2ef6312a67cd00880cf3dfbca16b95b07366c04.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/tables/f5fa770e864067c1743d56b4b2ef6312a67cd00880cf3dfbca16b95b07366c04.jpg)

![fef9921ac94d224d97c7f1a19dea64dff534d252114b824495471584aad83ad9.jpg](../nips_results/414_Blackbox%20Model%20Provenance%20via%20Palimpsestic%20Membership%20Inference/tables/fef9921ac94d224d97c7f1a19dea64dff534d252114b824495471584aad83ad9.jpg)

## OCTDiff: Bridged Diffusion Model for Portable OCT Super-Resolution and Enhancement


### Images

![00c63d5b29b67eb7c03d700d9e8ad66917989e6a357224713e49078b2b47f02c.jpg](../nips_results/415_OCTDiff_%20Bridged%20Diffusion%20Model%20for%20Portable%20OCT%20Super-Resolution%20and%20Enhancement/images/00c63d5b29b67eb7c03d700d9e8ad66917989e6a357224713e49078b2b47f02c.jpg)

![20cb558b7d6b807bed6dbb211a62ae1a94ba9e9b94be0e5204e1e1b76b3811a9.jpg](../nips_results/415_OCTDiff_%20Bridged%20Diffusion%20Model%20for%20Portable%20OCT%20Super-Resolution%20and%20Enhancement/images/20cb558b7d6b807bed6dbb211a62ae1a94ba9e9b94be0e5204e1e1b76b3811a9.jpg)

![7c5cfbb3eeea25fe2ef4855c186ca7ef78f24196c2ccf274f42296e7ca29ddd0.jpg](../nips_results/415_OCTDiff_%20Bridged%20Diffusion%20Model%20for%20Portable%20OCT%20Super-Resolution%20and%20Enhancement/images/7c5cfbb3eeea25fe2ef4855c186ca7ef78f24196c2ccf274f42296e7ca29ddd0.jpg)

![9dd220c3ed2f79828cdd89f2b0405c9a5b5ec90c95b081541f9c85c5760ad4f7.jpg](../nips_results/415_OCTDiff_%20Bridged%20Diffusion%20Model%20for%20Portable%20OCT%20Super-Resolution%20and%20Enhancement/images/9dd220c3ed2f79828cdd89f2b0405c9a5b5ec90c95b081541f9c85c5760ad4f7.jpg)

![f990d851e8fde5c5fbbe325ddf5763311b0ffc96aac6e52db850022a468a98e2.jpg](../nips_results/415_OCTDiff_%20Bridged%20Diffusion%20Model%20for%20Portable%20OCT%20Super-Resolution%20and%20Enhancement/images/f990d851e8fde5c5fbbe325ddf5763311b0ffc96aac6e52db850022a468a98e2.jpg)

### Tables

![325862ec713a02ef9ffda5e98462eabcd0bce8e36b28243742cecd1d9129213f.jpg](../nips_results/415_OCTDiff_%20Bridged%20Diffusion%20Model%20for%20Portable%20OCT%20Super-Resolution%20and%20Enhancement/tables/325862ec713a02ef9ffda5e98462eabcd0bce8e36b28243742cecd1d9129213f.jpg)

![96b698b27237ee43adbbb0bc7ec8e6179fc0305a02e542df90829e2363b552eb.jpg](../nips_results/415_OCTDiff_%20Bridged%20Diffusion%20Model%20for%20Portable%20OCT%20Super-Resolution%20and%20Enhancement/tables/96b698b27237ee43adbbb0bc7ec8e6179fc0305a02e542df90829e2363b552eb.jpg)

![a37ede546cf1851b253f15f2be3aebcbe2b5fef5818425f2479ec90102bd2f8d.jpg](../nips_results/415_OCTDiff_%20Bridged%20Diffusion%20Model%20for%20Portable%20OCT%20Super-Resolution%20and%20Enhancement/tables/a37ede546cf1851b253f15f2be3aebcbe2b5fef5818425f2479ec90102bd2f8d.jpg)

![b8a3c48ce39bb28358912064aa875ebcf214480a1e0cf2553e138cd9e4db2669.jpg](../nips_results/415_OCTDiff_%20Bridged%20Diffusion%20Model%20for%20Portable%20OCT%20Super-Resolution%20and%20Enhancement/tables/b8a3c48ce39bb28358912064aa875ebcf214480a1e0cf2553e138cd9e4db2669.jpg)

![e1b7843ac62f67c7de590c2671d11da0f22e77602c36dca47219d9396fc8c15a.jpg](../nips_results/415_OCTDiff_%20Bridged%20Diffusion%20Model%20for%20Portable%20OCT%20Super-Resolution%20and%20Enhancement/tables/e1b7843ac62f67c7de590c2671d11da0f22e77602c36dca47219d9396fc8c15a.jpg)

![f04d94bd45cf105631963ec862a1a84cd1654f3dcc78fffcc60350fc389b4480.jpg](../nips_results/415_OCTDiff_%20Bridged%20Diffusion%20Model%20for%20Portable%20OCT%20Super-Resolution%20and%20Enhancement/tables/f04d94bd45cf105631963ec862a1a84cd1654f3dcc78fffcc60350fc389b4480.jpg)

## Improved Representation Steering for Language Models


### Images

![2ad02169f23cfe1bca43c955d1fb04cc81ad95708f73b7484fe6c78a72679770.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/2ad02169f23cfe1bca43c955d1fb04cc81ad95708f73b7484fe6c78a72679770.jpg)

![3274665b3beac565e9967004559488189ae9cab2246504ddd8fadce8d332711c.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/3274665b3beac565e9967004559488189ae9cab2246504ddd8fadce8d332711c.jpg)

![32d6290d4f30e34b911f4202ef3c5bbdf6550210570f0728884a302ae3ce3ac2.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/32d6290d4f30e34b911f4202ef3c5bbdf6550210570f0728884a302ae3ce3ac2.jpg)

![365141147e0df7eeda6a0adfa76ccd4f0ab41b4358f62bf2f0e29826df5bb3e5.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/365141147e0df7eeda6a0adfa76ccd4f0ab41b4358f62bf2f0e29826df5bb3e5.jpg)

![499c3993e64d6b02a5057aac0f02f0c7dfd235c59668637554369875217a78ae.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/499c3993e64d6b02a5057aac0f02f0c7dfd235c59668637554369875217a78ae.jpg)

![4f150dcd7bbb02cbe63876b21e9c0f018db463c0ebc58f0bd7742fef7a9821ee.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/4f150dcd7bbb02cbe63876b21e9c0f018db463c0ebc58f0bd7742fef7a9821ee.jpg)

![5ca2d00cd012b1b5c7616a4e4ff3711cdd698d495032acfc5e52a6c1a6601334.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/5ca2d00cd012b1b5c7616a4e4ff3711cdd698d495032acfc5e52a6c1a6601334.jpg)

![5e114e4a05e8bcbde8a64c9cedf78bd4bb89b5c6577b42c308c1cac07918d5e0.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/5e114e4a05e8bcbde8a64c9cedf78bd4bb89b5c6577b42c308c1cac07918d5e0.jpg)

![6c071b89bc707736a4334b2f8a3683a975d997982392886b0524c7ca5c97b6c8.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/6c071b89bc707736a4334b2f8a3683a975d997982392886b0524c7ca5c97b6c8.jpg)

![7a70da766b150f3272d01aa4345164b2ecdba8f2a45ebd5f0883a97099e18fc6.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/7a70da766b150f3272d01aa4345164b2ecdba8f2a45ebd5f0883a97099e18fc6.jpg)

![8059b03e227839cad7de7ec8238c611a93d8503efd0d5b63e6c0c706483f54ca.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/8059b03e227839cad7de7ec8238c611a93d8503efd0d5b63e6c0c706483f54ca.jpg)

![81f9c376af343d7cc30839084a9a9b9a225617efdb1ba50aa5d6b741b3ad12d4.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/81f9c376af343d7cc30839084a9a9b9a225617efdb1ba50aa5d6b741b3ad12d4.jpg)

![8665a187e9a4c888e99e94f0e20116f5deeee85fa8f47f27c1d3f27f737d8d54.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/8665a187e9a4c888e99e94f0e20116f5deeee85fa8f47f27c1d3f27f737d8d54.jpg)

![8ff27a02b5281b1f434bd7db5344760113d6544f08da90a5b9546b7ed5b1d36d.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/8ff27a02b5281b1f434bd7db5344760113d6544f08da90a5b9546b7ed5b1d36d.jpg)

![a0b84ef4716da33d399299166660f88f51e81b4985ad683117b010aeb0b3b4d6.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/a0b84ef4716da33d399299166660f88f51e81b4985ad683117b010aeb0b3b4d6.jpg)

![aa398e18125ad2273631d3fc0766abf83e42fb8abf1ec62407389283318f66db.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/aa398e18125ad2273631d3fc0766abf83e42fb8abf1ec62407389283318f66db.jpg)

![abb3491706f8c2061739bbfa8863dd3b893b3a297587afe5be828b75016a10d1.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/abb3491706f8c2061739bbfa8863dd3b893b3a297587afe5be828b75016a10d1.jpg)

![ae0b3a4767a25a6d730ea7190bfff1340c564060e7c3d1d48b101f7ae92042aa.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/ae0b3a4767a25a6d730ea7190bfff1340c564060e7c3d1d48b101f7ae92042aa.jpg)

![bb8a7d149cb7243399b793849b1d370ea08964ba4d44b510f063623a2d7970ce.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/bb8a7d149cb7243399b793849b1d370ea08964ba4d44b510f063623a2d7970ce.jpg)

![c0c41816d78320ada6f8a8299ef9a93a0334f9cf39e40854f3102832e34c6f5b.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/c0c41816d78320ada6f8a8299ef9a93a0334f9cf39e40854f3102832e34c6f5b.jpg)

![caff4dd8f5a854fc2f4de873e6dbd21706d27408a112fc7fa43b7fb768bf09d7.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/caff4dd8f5a854fc2f4de873e6dbd21706d27408a112fc7fa43b7fb768bf09d7.jpg)

![e8f471cfb65f97370a3f22e963607227e99e5a6ac1f40b24ccc66f7f5bb3840e.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/e8f471cfb65f97370a3f22e963607227e99e5a6ac1f40b24ccc66f7f5bb3840e.jpg)

![eef56a39231136d26bb73111b5c7f459633006647bc9a46e39ff44cb14a3b1bb.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/eef56a39231136d26bb73111b5c7f459633006647bc9a46e39ff44cb14a3b1bb.jpg)

![f0fe0d4bed0a25ef2b584920e83e04770801fe31a84a40cd0a32806ad64a6f9c.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/f0fe0d4bed0a25ef2b584920e83e04770801fe31a84a40cd0a32806ad64a6f9c.jpg)

![f29a8600b734a373ac31fce44fb22858e979b207d7a2af27e516c27e8d5b52a8.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/images/f29a8600b734a373ac31fce44fb22858e979b207d7a2af27e516c27e8d5b52a8.jpg)

### Tables

![0919fb98ec92e3108b41795f5d557960da1851582017c7a518efe8f7d5b64307.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/0919fb98ec92e3108b41795f5d557960da1851582017c7a518efe8f7d5b64307.jpg)

![4869c0c60bdb3969e3285442c4c4c9d627968e8e51ab99af7baf7c5d312debcb.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/4869c0c60bdb3969e3285442c4c4c9d627968e8e51ab99af7baf7c5d312debcb.jpg)

![539b1cad77da2a33cb789e33fac6636c6fbab251f394d222e95a3524262bd88d.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/539b1cad77da2a33cb789e33fac6636c6fbab251f394d222e95a3524262bd88d.jpg)

![5760bcbdf7e242d0c58883d755d2889a4fe743d216d9eeca70699c9fd86703df.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/5760bcbdf7e242d0c58883d755d2889a4fe743d216d9eeca70699c9fd86703df.jpg)

![60f1fcbed7d35a083a903326e43620fcbc39f353517c7edad5bca4c3a61232be.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/60f1fcbed7d35a083a903326e43620fcbc39f353517c7edad5bca4c3a61232be.jpg)

![722483329d74b2717bbb7f6821e1dbc3eaf5af62000c9232097610769c2813c7.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/722483329d74b2717bbb7f6821e1dbc3eaf5af62000c9232097610769c2813c7.jpg)

![75b0c95cf88b21dea50429b605b8f7dc006f030f7d80387e4cea24e17e1c9711.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/75b0c95cf88b21dea50429b605b8f7dc006f030f7d80387e4cea24e17e1c9711.jpg)

![7d69997b479ad62e6d41d36b984b02418e27a59919f6ad9915e6fd3453d89363.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/7d69997b479ad62e6d41d36b984b02418e27a59919f6ad9915e6fd3453d89363.jpg)

![8c84537b5a94e633b5b67f5277c41d0edfe9860c656e20a9879f7490b08984c7.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/8c84537b5a94e633b5b67f5277c41d0edfe9860c656e20a9879f7490b08984c7.jpg)

![8c98ef0b5a17814084cc9328153711fb6473ae5e04da9544a3b4a94b1542713e.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/8c98ef0b5a17814084cc9328153711fb6473ae5e04da9544a3b4a94b1542713e.jpg)

![b04f6aff95728b4bfa2d2c3a03a83094cbf24cc469529e0829851f40987098c4.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/b04f6aff95728b4bfa2d2c3a03a83094cbf24cc469529e0829851f40987098c4.jpg)

![b1856d51fb8c801d3901b669c976108e841178a8c16fb4d59646c6b1293db2d3.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/b1856d51fb8c801d3901b669c976108e841178a8c16fb4d59646c6b1293db2d3.jpg)

![c0369fadb546efeaa7dcae3c2a76e8f6325afff78c777e0880e86030b90c944e.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/c0369fadb546efeaa7dcae3c2a76e8f6325afff78c777e0880e86030b90c944e.jpg)

![c08ef02355aba27a252bc320b123d0b10ced15d3c7eedf3fdfe61352de4794f5.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/c08ef02355aba27a252bc320b123d0b10ced15d3c7eedf3fdfe61352de4794f5.jpg)

![c940e1efc500f20c56cb89c50bf9664d9a657a10e3b0a2acc185535ec14f73b1.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/c940e1efc500f20c56cb89c50bf9664d9a657a10e3b0a2acc185535ec14f73b1.jpg)

![d6fd2f4a2f27e5c710846fcd616cd5c80e2687c46bf78ae1db2da047ba61b7f4.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/d6fd2f4a2f27e5c710846fcd616cd5c80e2687c46bf78ae1db2da047ba61b7f4.jpg)

![f76963d99ab5f8f9e7e05b7e21caf9dd963af03c8571a7d72d88d0d512ee972e.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/f76963d99ab5f8f9e7e05b7e21caf9dd963af03c8571a7d72d88d0d512ee972e.jpg)

![ff90f4df504107dfd44573c7ecffb8d423a55cf6e09f78d4602147fdffc692e2.jpg](../nips_results/416_Improved%20Representation%20Steering%20for%20Language%20Models/tables/ff90f4df504107dfd44573c7ecffb8d423a55cf6e09f78d4602147fdffc692e2.jpg)

## Generative Trajectory Stitching through Diffusion Composition


### Images

![0fb50fe26798f4d66b07660f10e0dd09c2806307875717782fde91f96f5d7f99.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/0fb50fe26798f4d66b07660f10e0dd09c2806307875717782fde91f96f5d7f99.jpg)

![17d3f36d3e544fd01f25f2623ab2231df54fa2d4a82807aedf0221f9df72a77f.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/17d3f36d3e544fd01f25f2623ab2231df54fa2d4a82807aedf0221f9df72a77f.jpg)

![1e6865a13d71366da1ae0ccb0eba61a2016a62df60ca5d1e8f971325c78a57a4.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/1e6865a13d71366da1ae0ccb0eba61a2016a62df60ca5d1e8f971325c78a57a4.jpg)

![23a974fc9568a45221003ef209db77f4d659df2347a71a8df6e38b893a82c42d.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/23a974fc9568a45221003ef209db77f4d659df2347a71a8df6e38b893a82c42d.jpg)

![4fd5e0ab466bd9f47c02d0417205065653c5d616ba47581bfd84bf9084016e86.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/4fd5e0ab466bd9f47c02d0417205065653c5d616ba47581bfd84bf9084016e86.jpg)

![7145cd8ebbc31045e97feb25a1dbc9ca1aac51b659943f2db90f2c2d944d28e9.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/7145cd8ebbc31045e97feb25a1dbc9ca1aac51b659943f2db90f2c2d944d28e9.jpg)

![85af0b02e30a1eb3091cd67296011477d86c77591263abc73230710d5ef4eb8f.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/85af0b02e30a1eb3091cd67296011477d86c77591263abc73230710d5ef4eb8f.jpg)

![8dba54e96d7b44fd659b4adc29e876a759df47aeae4f17e0d5c203308def23f4.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/8dba54e96d7b44fd659b4adc29e876a759df47aeae4f17e0d5c203308def23f4.jpg)

![906adf9980c7c3e64e2174cc478f8649d2de3aeb6ad4bf963773e96fa275713e.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/906adf9980c7c3e64e2174cc478f8649d2de3aeb6ad4bf963773e96fa275713e.jpg)

![924b62622b08a62020db38c3adc266d0958acccd9b472ad07283fe3c617943f3.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/924b62622b08a62020db38c3adc266d0958acccd9b472ad07283fe3c617943f3.jpg)

![a36c0b0ebee08279b57af15fe49250eda074b4671b0bef584f7e64521e1478b9.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/a36c0b0ebee08279b57af15fe49250eda074b4671b0bef584f7e64521e1478b9.jpg)

![c83847c6c5e2dcf637054d9ec2c16526cb08a3ac9475fbd53069cc1e1601d1d6.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/c83847c6c5e2dcf637054d9ec2c16526cb08a3ac9475fbd53069cc1e1601d1d6.jpg)

![cfea30f060e4e574c22a0495977fbcd268f48083f77c07b9ecf9fc558aa6143d.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/cfea30f060e4e574c22a0495977fbcd268f48083f77c07b9ecf9fc558aa6143d.jpg)

![ed98d517ed352e03cd27ae1fe432248bb9ad2340fd4d3a6ca0e4d588c31f0422.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/ed98d517ed352e03cd27ae1fe432248bb9ad2340fd4d3a6ca0e4d588c31f0422.jpg)

![f44679f3da5d35212a2b48da04b3dbe3128173f281438b871caab1eea1cba400.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/f44679f3da5d35212a2b48da04b3dbe3128173f281438b871caab1eea1cba400.jpg)

![fb7eb6178ea10cf1c8072f941ec1a263346d4e6495cae91359c3335b2a5fbd43.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/images/fb7eb6178ea10cf1c8072f941ec1a263346d4e6495cae91359c3335b2a5fbd43.jpg)

### Tables

![3721f05d90ecab181f488975ed34b8f4cc232bcb8f3e1e5b167751202af9a23c.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/3721f05d90ecab181f488975ed34b8f4cc232bcb8f3e1e5b167751202af9a23c.jpg)

![380fcb60ba9dd950c55944222e89d2378209f8eaf7af1b991187e215ed4e398b.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/380fcb60ba9dd950c55944222e89d2378209f8eaf7af1b991187e215ed4e398b.jpg)

![4002c557bae9b50e6a065f466b60910564f0ff3f6fd96200aca39b7fc48c8c89.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/4002c557bae9b50e6a065f466b60910564f0ff3f6fd96200aca39b7fc48c8c89.jpg)

![4e90f95df99f101626aa733d44b99ab8762f9d422e58e5e6008d907a6f0dc8c5.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/4e90f95df99f101626aa733d44b99ab8762f9d422e58e5e6008d907a6f0dc8c5.jpg)

![4f86e79abe1e57e0c6e21fa91d894affe06eda64aab5b374ea5ef850a56bb44a.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/4f86e79abe1e57e0c6e21fa91d894affe06eda64aab5b374ea5ef850a56bb44a.jpg)

![58d5913b3043c23343978b04c220ddc5048a26753d970f3b75896d1544524932.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/58d5913b3043c23343978b04c220ddc5048a26753d970f3b75896d1544524932.jpg)

![92759fd40defb288b80bddee895394a02bfa25429972eb721c0f93724af3f0d0.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/92759fd40defb288b80bddee895394a02bfa25429972eb721c0f93724af3f0d0.jpg)

![b33139cf15a6121281080684ef22ea2d97620636a82855b7e4dc34ff85223e47.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/b33139cf15a6121281080684ef22ea2d97620636a82855b7e4dc34ff85223e47.jpg)

![c02a47fd7deeb07d2887973b19440645426d81f0d1deee0325c45b1427781e59.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/c02a47fd7deeb07d2887973b19440645426d81f0d1deee0325c45b1427781e59.jpg)

![d1634ce03e39c3e9b5ab7ecd0666ff9e91a174201c8b68c48847ecbee309c407.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/d1634ce03e39c3e9b5ab7ecd0666ff9e91a174201c8b68c48847ecbee309c407.jpg)

![e11a74a034f451dcbe4799da2597ccad88e0c1fe11341abfb1f61fcea38555af.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/e11a74a034f451dcbe4799da2597ccad88e0c1fe11341abfb1f61fcea38555af.jpg)

![e19f3190f01d1285f88b1dbab40bb39a203d6e2b084acfad317789684b5e1352.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/e19f3190f01d1285f88b1dbab40bb39a203d6e2b084acfad317789684b5e1352.jpg)

![f91e2c9317ffc7f693e465a2b468a9b2edad40d5e1873254af0bd299a03a71a9.jpg](../nips_results/417_Generative%20Trajectory%20Stitching%20through%20Diffusion%20Composition/tables/f91e2c9317ffc7f693e465a2b468a9b2edad40d5e1873254af0bd299a03a71a9.jpg)

## LLM-Explorer: A Plug-in Reinforcement Learning Policy Exploration Enhancement Driven by Large Language Models


### Images

![1eeb7a14a4f267dddff77f1d7a17849296a7dd00fe530366f3318157b472bd61.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/images/1eeb7a14a4f267dddff77f1d7a17849296a7dd00fe530366f3318157b472bd61.jpg)

![23ccaf6d9e08d9ebb9ad23d3e5eb56dd5eacca4f1d4f212db6bea7c5c399e4e6.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/images/23ccaf6d9e08d9ebb9ad23d3e5eb56dd5eacca4f1d4f212db6bea7c5c399e4e6.jpg)

![2c1fecf3fd46ee609b1838661241ab2903d776748af49df263293be9f52bfd34.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/images/2c1fecf3fd46ee609b1838661241ab2903d776748af49df263293be9f52bfd34.jpg)

![34a73f3e74cabfc1adf842a384af3f814cd5dd05dd6d01a00124c74378cacb76.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/images/34a73f3e74cabfc1adf842a384af3f814cd5dd05dd6d01a00124c74378cacb76.jpg)

![4556038e33f7c7aea46953045f7cf531e14e65ab2c4ddce3c62e680c2147aebf.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/images/4556038e33f7c7aea46953045f7cf531e14e65ab2c4ddce3c62e680c2147aebf.jpg)

![7cf49c08a39eec3ec65f5e8db3816b1b158f454f767538d90d6e18dbdbf800ef.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/images/7cf49c08a39eec3ec65f5e8db3816b1b158f454f767538d90d6e18dbdbf800ef.jpg)

![e8e368450bcda80e4629e14dce4ac0f5b069c79bd37811b4e910c1c4d76c0685.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/images/e8e368450bcda80e4629e14dce4ac0f5b069c79bd37811b4e910c1c4d76c0685.jpg)

![eba440608f2e194d67a3eeb7912d1e95ebd36ebfd709d61b35cc7564947c1018.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/images/eba440608f2e194d67a3eeb7912d1e95ebd36ebfd709d61b35cc7564947c1018.jpg)

![f14c457d1365c38630d1f0b271cf0355c3f77b6f27d896f85bc9f3cc05c229ca.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/images/f14c457d1365c38630d1f0b271cf0355c3f77b6f27d896f85bc9f3cc05c229ca.jpg)

### Tables

![04aad56c8d390cf3a25b045d0208d3776fe58556df9f8541a5584d5d2fff922d.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/04aad56c8d390cf3a25b045d0208d3776fe58556df9f8541a5584d5d2fff922d.jpg)

![41952ed59a2a205756900aec4c08d6659af63943383d6133479bf4724ae5c1fb.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/41952ed59a2a205756900aec4c08d6659af63943383d6133479bf4724ae5c1fb.jpg)

![4303aa4ea865ff0daa0594c464100d14f2c1e0db5d6a55ca2bfde41ef5e739fe.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/4303aa4ea865ff0daa0594c464100d14f2c1e0db5d6a55ca2bfde41ef5e739fe.jpg)

![4452f011559cefc2d638eb1097dfa0d9c160a1dfc1a4698c31a1b0aff147c2fc.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/4452f011559cefc2d638eb1097dfa0d9c160a1dfc1a4698c31a1b0aff147c2fc.jpg)

![4bbd9e9dfd869207c9cf1a6ae218b284c9915f97e4e78c82a5ec7e8c11711241.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/4bbd9e9dfd869207c9cf1a6ae218b284c9915f97e4e78c82a5ec7e8c11711241.jpg)

![532fb3280a4ba35dfca51107578ee8044b4f4929c31dbd51904b24054a631330.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/532fb3280a4ba35dfca51107578ee8044b4f4929c31dbd51904b24054a631330.jpg)

![ab8bdff4fdd0eec5587261fcc489a027d1edd7f38f05dbeb33b824618c4733aa.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/ab8bdff4fdd0eec5587261fcc489a027d1edd7f38f05dbeb33b824618c4733aa.jpg)

![b40f820a63ef50a2ca9f9253ec80d15f3a07572835f64bc8675bb385e1924090.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/b40f820a63ef50a2ca9f9253ec80d15f3a07572835f64bc8675bb385e1924090.jpg)

![bce8b11315b8550995a326c1ef7228301aff9386e23a2c163b8a2bf0d716be03.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/bce8b11315b8550995a326c1ef7228301aff9386e23a2c163b8a2bf0d716be03.jpg)

![cfabddd1075fcc843c28aff35fc19a81673ad460b6a1bd37a58cb83cb7bc975c.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/cfabddd1075fcc843c28aff35fc19a81673ad460b6a1bd37a58cb83cb7bc975c.jpg)

![d5647c9da92222b078424198f4d4bc4b8b49d7c92f51948106e18d5469b7b513.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/d5647c9da92222b078424198f4d4bc4b8b49d7c92f51948106e18d5469b7b513.jpg)

![d7b5addbfa0431c654ca39173f5800b9563f433d86237430b5379d87168b34e1.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/d7b5addbfa0431c654ca39173f5800b9563f433d86237430b5379d87168b34e1.jpg)

![dcfda920206cb093778ad425ab482efe41043d3a2724836cd608feb17b9c8457.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/dcfda920206cb093778ad425ab482efe41043d3a2724836cd608feb17b9c8457.jpg)

![e06f0d14ba4e247131f17bde5d390d2c2f2e62414632e14b77da007692688a77.jpg](../nips_results/418_LLM-Explorer_%20A%20Plug-in%20Reinforcement%20Learning%20Policy%20Exploration%20Enhancement%20Driven%20by%20Large%20Langua/tables/e06f0d14ba4e247131f17bde5d390d2c2f2e62414632e14b77da007692688a77.jpg)

## Unveiling the Power of Multiple Gossip Steps: A Stability-Based Generalization Analysis in Decentralized Training

### Images

![0563610873014559aa35b5076e8d6dd6416441dd3a37dc144b30765b91766ab5.jpg](../nips_results/419_Unveiling%20the%20Power%20of%20Multiple%20Gossip%20Steps_%20A%20Stability-Based%20Generalization%20Analysis%20in%20Decentral/images/0563610873014559aa35b5076e8d6dd6416441dd3a37dc144b30765b91766ab5.jpg)

![39c98fd5f1994301ef4495003f0dedc133e7e95120dceeebc8bd77c36600c032.jpg](../nips_results/419_Unveiling%20the%20Power%20of%20Multiple%20Gossip%20Steps_%20A%20Stability-Based%20Generalization%20Analysis%20in%20Decentral/images/39c98fd5f1994301ef4495003f0dedc133e7e95120dceeebc8bd77c36600c032.jpg)

![76a14b70e7032465ba27c9ce7a4bd4f9f1d461e3d95485858cb6a6e28bcce002.jpg](../nips_results/419_Unveiling%20the%20Power%20of%20Multiple%20Gossip%20Steps_%20A%20Stability-Based%20Generalization%20Analysis%20in%20Decentral/images/76a14b70e7032465ba27c9ce7a4bd4f9f1d461e3d95485858cb6a6e28bcce002.jpg)

![bf21d8f11609385e4066669ed80d350f9a2c152a44f066b30e671ecf8c8f2a54.jpg](../nips_results/419_Unveiling%20the%20Power%20of%20Multiple%20Gossip%20Steps_%20A%20Stability-Based%20Generalization%20Analysis%20in%20Decentral/images/bf21d8f11609385e4066669ed80d350f9a2c152a44f066b30e671ecf8c8f2a54.jpg)

![ee025b95f00239bc661bcf35f438013831fb2e764de7741224ae905f82ce2763.jpg](../nips_results/419_Unveiling%20the%20Power%20of%20Multiple%20Gossip%20Steps_%20A%20Stability-Based%20Generalization%20Analysis%20in%20Decentral/images/ee025b95f00239bc661bcf35f438013831fb2e764de7741224ae905f82ce2763.jpg)

![f6f367c191967b0a89c780b18ef66287a6cb5cb3ded6a64c1e9cec6db91c7ff2.jpg](../nips_results/419_Unveiling%20the%20Power%20of%20Multiple%20Gossip%20Steps_%20A%20Stability-Based%20Generalization%20Analysis%20in%20Decentral/images/f6f367c191967b0a89c780b18ef66287a6cb5cb3ded6a64c1e9cec6db91c7ff2.jpg)

### Tables

![874c21013b5b661a0e7fd81ccf5433f04d772e8846b0dcdbd765a430ca65c132.jpg](../nips_results/419_Unveiling%20the%20Power%20of%20Multiple%20Gossip%20Steps_%20A%20Stability-Based%20Generalization%20Analysis%20in%20Decentral/tables/874c21013b5b661a0e7fd81ccf5433f04d772e8846b0dcdbd765a430ca65c132.jpg)
