<div class="github-widget" data-repo="n2cholas/awesome-jax"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint ignore double-link-->

<!--lint ignore double-link-->
[JAX](https://github.com/google/jax) 带来自动微分和 [XLA compiler](https://www.tensorflow.org/xla) 一起通过一个 [NumPy](https://numpy.org/)- 用于在 GPU 和 TPU 等加速器上进行高性能机器学习研究的 API.
<!--lint enable double-link-->

这是一个很棒的 JAX 库、项目和其他资源的精选列表. 欢迎投稿！



<a name="libraries" />

## Libraries

- 神经网络库
    - [Flax](https://raw.githubusercontent.com/google/flax) - 以灵活性和清晰度为中心. <img src="https://img.shields.io/github/stars/google/flax?style=social" align="center">
    - [Haiku](https://raw.githubusercontent.com/deepmind/dm-haiku) - 专注于简单，由 DeepMind 的 Sonnet 的作者创建. <img src="https://img.shields.io/github/stars/deepmind/dm-haiku?style=social" align="center">
    - [Objax](https://raw.githubusercontent.com/google/objax) - 具有类似于 PyTorch 的面向对象设计. <img src="https://img.shields.io/github/stars/google/objax?style=social" align="center">
    - [Elegy](https://poets-ai.github.io/elegy/)  - JAX 中用于深度学习的高级 API. 支持 Flax、Haiku 和 Optax. <img src="https://img.shields.io/github/stars/poets-ai/elegy?style=social" align="center">
    - [Trax](https://raw.githubusercontent.com/google/trax) - “包括电池”深度学习库，专注于为常见工作负载提供解决方案. <img src="https://img.shields.io/github/stars/google/trax?style=social" align="center">
    - [Jraph](https://raw.githubusercontent.com/deepmind/jraph) - 轻量级图神经网络库. <img src="https://img.shields.io/github/stars/deepmind/jraph?style=social" align="center">
    - [Neural Tangents](https://raw.githubusercontent.com/google/neural-tangents) - 用于指定有限和_infinite_宽度的神经网络的高级API. <img src="https://img.shields.io/github/stars/google/neural-tangents?style=social" align="center">
    - [HuggingFace](https://raw.githubusercontent.com/huggingface/transformers) - 用于各种自然语言任务（Flax）的预训练变形金刚生态系统. <img src="https://img.shields.io/github/stars/huggingface/transformers?style=social" align="center">
    - [Equinox](https://raw.githubusercontent.com/patrick-kidger/equinox) - 可调用的 PyTrees 和过滤的 JIT/grad 转换 =&gt; JAX 中的神经网络. <img src="https://img.shields.io/github/stars/patrick-kidger/equinox?style=social" align="center">
- [NumPyro](https://raw.githubusercontent.com/pyro-ppl/numpyro) - 基于 Pyro 库的概率编程. <img src="https://img.shields.io/github/stars/pyro-ppl/numpyro?style=social" align="center">
- [Chex](https://raw.githubusercontent.com/deepmind/chex) - 编写和测试可靠 JAX 代码的实用程序. <img src="https://img.shields.io/github/stars/deepmind/chex?style=social" align="center">
- [Optax](https://raw.githubusercontent.com/deepmind/optax) - 梯度处理和优化库. <img src="https://img.shields.io/github/stars/deepmind/optax?style=social" align="center">
- [RLax](https://raw.githubusercontent.com/deepmind/rlax) - 用于实施强化学习代理的库. <img src="https://img.shields.io/github/stars/deepmind/rlax?style=social" align="center">
- [JAX, M.D.](https://raw.githubusercontent.com/google/jax-md) - 加速的微分分子动力学. <img src="https://img.shields.io/github/stars/google/jax-md?style=social" align="center">
- [Coax](https://raw.githubusercontent.com/coax-dev/coax) - 将 RL 论文转化为代码，这是一种简单的方法. <img src="https://img.shields.io/github/stars/coax-dev/coax?style=social" align="center">
- [Distrax](https://raw.githubusercontent.com/deepmind/distrax) - 重新实现 TensorFlow Probability，包含概率分布和双射. <img src="https://img.shields.io/github/stars/deepmind/distrax?style=social" align="center">
- [cvxpylayers](https://raw.githubusercontent.com/cvxgrp/cvxpylayers) - 构建可微的凸优化层. <img src="https://img.shields.io/github/stars/cvxgrp/cvxpylayers?style=social" align="center">
- [TensorLy](https://raw.githubusercontent.com/tensorly/tensorly) - 张量学习变得简单. <img src="https://img.shields.io/github/stars/tensorly/tensorly?style=social" align="center">
- [NetKet](https://raw.githubusercontent.com/netket/netket) - 量子物理学的机器学习工具箱. <img src="https://img.shields.io/github/stars/netket/netket?style=social" align="center">

<a name="new-libraries" />

### New Libraries

本节包含制作精良且有用的库，但尚未经过大量用户群的实战测试.

- 神经网络库
    - [FedJAX](https://raw.githubusercontent.com/google/fedjax) - 基于 Optax 和 Haiku 的 JAX 中的联合学习. <img src="https://img.shields.io/github/stars/google/fedjax?style=social" align="center">
    - [Equivariant MLP](https://raw.githubusercontent.com/mfinzi/equivariant-MLP) - 构建等变神经网络层. <img src="https://img.shields.io/github/stars/mfinzi/equivariant-MLP?style=social" align="center">
    - [jax-resnet](https://raw.githubusercontent.com/n2cholas/jax-resnet/) - Flax 中 ResNet 变体的实现和检查点. <img src="https://img.shields.io/github/stars/n2cholas/jax-resnet?style=social" align="center">
    - [Parallax](https://raw.githubusercontent.com/srush/parallax) - JAX 的不可变 Torch 模块. <img src="https://img.shields.io/github/stars/srush/parallax?style=social" align="center">
- [jax-unirep](https://raw.githubusercontent.com/ElArkk/jax-unirep) - 图书馆实施 [UniRep model](https://www.nature.com/articles/s41592-019-0598-1) 用于蛋白质机器学习应用. <img src="https://img.shields.io/github/stars/ElArkk/jax-unirep?style=social" align="center">
- [jax-flows](https://raw.githubusercontent.com/ChrisWaites/jax-flows) - 规范 JAX 中的流程. <img src="https://img.shields.io/github/stars/ChrisWaites/jax-flows?style=social" align="center">
- [sklearn-jax-kernels](https://raw.githubusercontent.com/ExpectationMax/sklearn-jax-kernels) - 使用 JAX 的“scikit-learn”内核矩阵. <img src="https://img.shields.io/github/stars/ExpectationMax/sklearn-jax-kernels?style=social" align="center">
- [jax-cosmo](https://raw.githubusercontent.com/DifferentiableUniverseInitiative/jax_cosmo) - 可微的宇宙学图书馆. <img src="https://img.shields.io/github/stars/DifferentiableUniverseInitiative/jax_cosmo?style=social" align="center">
- [efax](https://raw.githubusercontent.com/NeilGirdhar/efax) - JAX 中的指数族. <img src="https://img.shields.io/github/stars/NeilGirdhar/efax?style=social" align="center">
- [mpi4jax](https://raw.githubusercontent.com/PhilipVinc/mpi4jax) - 将 MPI 操作与 CPU 和 GPU 上的 Jax 代码相结合. <img src="https://img.shields.io/github/stars/PhilipVinc/mpi4jax?style=social" align="center">
- [imax](https://raw.githubusercontent.com/4rtemi5/imax) - 图像增强和转换. <img src="https://img.shields.io/github/stars/4rtemi5/imax?style=social" align="center">
- [FlaxVision](https://raw.githubusercontent.com/rolandgvc/flaxvision) - TorchVision 的亚麻版本. <img src="https://img.shields.io/github/stars/rolandgvc/flaxvision?style=social" align="center">
- [Oryx](https://github.com/tensorflow/probability/tree/master/spinoffs/oryx) - 基于程序转换的概率编程语言.
- [Optimal Transport Tools](https://github.com/google-research/ott) - 捆绑实用程序以解决最佳运输问题的工具箱.
- [delta PV](https://raw.githubusercontent.com/romanodev/deltapv) - 具有自动微分功能的光伏模拟器. <img src="https://img.shields.io/github/stars/romanodev/deltapv?style=social" align="center">
- [jaxlie](https://raw.githubusercontent.com/brentyi/jaxlie) - 用于刚体变换和优化的李理论库. <img src="https://img.shields.io/github/stars/brentyi/jaxlie?style=social" align="center">
- [BRAX](https://raw.githubusercontent.com/google/brax) - 可微分物理引擎模拟环境以及学习算法来训练这些环境的代理. <img src="https://img.shields.io/github/stars/google/brax?style=social" align="center">
- [flaxmodels](https://raw.githubusercontent.com/matthias-wright/flaxmodels) - Jax/Flax 的预训练模型. <img src="https://img.shields.io/github/stars/matthias-wright/flaxmodels?style=social" align="center">
- [CR.Sparse](https://raw.githubusercontent.com/carnotresearch/cr-sparse) - 用于稀疏表示和压缩感知的 XLA 加速算法. <img src="https://img.shields.io/github/stars/carnotresearch/cr-sparse?style=social" align="center">
- [exojax](https://raw.githubusercontent.com/HajimeKawahara/exojax) - 与 JAX 兼容的系外行星/褐矮星的自动可微分光谱建模. <img src="https://img.shields.io/github/stars/HajimeKawahara/exojax?style=social" align="center">
- [JAXopt](https://raw.githubusercontent.com/google/jaxopt) - JAX 中的硬件加速 (GPU/TPU)、可批处理和可微优化器. <img src="https://img.shields.io/github/stars/google/jaxopt?style=social" align="center">
- [PIX](https://raw.githubusercontent.com/deepmind/dm_pix) - PIX is an image processing library in JAX, for JAX. <img src="https://img.shields.io/github/stars/deepmind/dm_pix?style=social" align="center">
- [bayex](https://raw.githubusercontent.com/alonfnt/bayex) - 由 JAX 提供支持的贝叶斯优化. <img src="https://img.shields.io/github/stars/alonfnt/bayex?style=social" align="center">
- [JaxDF](https://raw.githubusercontent.com/ucl-bug/jaxdf) - 具有任意离散化的可微分模拟器框架. <img src="https://img.shields.io/github/stars/ucl-bug/jaxdf?style=social" align="center">
- [tree-math](https://raw.githubusercontent.com/google/tree-math) - 将对数组进行操作的函数转换为对 PyTree 进行操作的函数. <img src="https://img.shields.io/github/stars/google/tree-math?style=social" align="center">
- [jax-models](https://raw.githubusercontent.com/DarshanDeshpande/jax-models) - 最初没有代码或使用 JAX 以外的框架编写的代码的研究论文的实现. <img src="https://img.shields.io/github/stars/DarshanDeshpande/jax-modelsa?style=social" align="center">
- [PGMax](https://raw.githubusercontent.com/vicariousinc/PGMax) - 用于构建离散概率图形模型 (PGM) 并通过 JAX 在它们上运行推理推理的框架. <img src="https://img.shields.io/github/stars/vicariousinc/pgmax?style=social" align="center">
- [EvoJAX](https://raw.githubusercontent.com/google/evojax) - 硬件加速的神经进化 <img src="https://img.shields.io/github/stars/google/evojax?style=social" align="center">
- [evosax](https://raw.githubusercontent.com/RobertTLange/evosax) - 基于 JAX 的进化策略 <img src="https://img.shields.io/github/stars/RobertTLange/evosax?style=social" align="center">
- [SymJAX](https://raw.githubusercontent.com/SymJAX/SymJAX) - 符号 CPU/GPU/TPU 编程. <img src="https://img.shields.io/github/stars/SymJAX/SymJAX?style=social" align="center">
- [mcx](https://raw.githubusercontent.com/rlouf/mcx) - 表达和编译概率程序以进行性能推理. <img src="https://img.shields.io/github/stars/rlouf/mcx?style=social" align="center">
- [Einshape](https://raw.githubusercontent.com/deepmind/einshape) - 用于 JAX 和其他框架的基于 DSL 的重塑库. <img src="https://img.shields.io/github/stars/deepmind/einshape?style=social" align="center">
- [ALX](https://github.com/google-research/google-research/tree/master/alx) - 使用交替最小二乘法进行分布式矩阵分解的开源库，更多信息见 [_ALX: Large Scale Matrix Factorization on TPUs_](https://arxiv.org/abs/2112.02194).
- [Diffrax](https://raw.githubusercontent.com/patrick-kidger/diffrax) - JAX 中的数值微分方程求解器. <img src="https://img.shields.io/github/stars/patrick-kidger/diffrax?style=social" align="center">
- [tinygp](https://raw.githubusercontent.com/dfm/tinygp) - JAX 中最小的高斯过程库. <img src="https://img.shields.io/github/stars/dfm/tinygp?style=social" align="center">

<a name="models-and-projects" />

## Models and Projects

### JAX

- [Fourier Feature Networks](https://github.com/tancik/fourier-feature-networks) - 正式实施 [_Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains_](https://people.eecs.berkeley.edu/~bmild/fourfeat).
- [kalman-jax](https://github.com/AaltoML/kalman-jax) - 使用迭代卡尔曼滤波和平滑的马尔可夫（即时间）高斯过程的近似推断.
- [GPJax](https://github.com/thomaspinder/GPJax) - JAX 中的高斯过程.
- [jaxns](https://github.com/Joshuaalbert/jaxns) - JAX 中的嵌套采样.
- [Amortized Bayesian Optimization](https://github.com/google-research/google-research/tree/master/amortized_bo) - 相关代码 [_Amortized Bayesian Optimization over Discrete Spaces_](http://www.auai.org/uai2020/proceedings/329_main_paper.pdf).
- [Accurate Quantized Training](https://github.com/google-research/google-research/tree/master/aqt) - 用于在 JAX 和 Flax 中运行和分析神经网络量化实验的工具和库.
- [BNN-HMC](https://github.com/google-research/google-research/tree/master/bnn_hmc) - 论文的实施 [_What Are Bayesian Neural Network Posteriors Really Like?_](https://arxiv.org/abs/2104.14421).
- [JAX-DFT](https://github.com/google-research/google-research/tree/master/jax_dft) - JAX 中的一维密度泛函理论 (DFT)，实现 [_Kohn-Sham equations as regularizer: building prior knowledge into machine-learned physics_](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.126.036401).
- [Robust Loss](https://github.com/google-research/google-research/tree/master/robust_loss_jax) - 论文的参考代码 [_A General and Adaptive Robust Loss Function_](https://arxiv.org/abs/1701.03077).
- [Symbolic Functionals](https://github.com/google-research/google-research/tree/master/symbolic_functionals) - 示范来自 [_Evolving symbolic density functionals_](https://arxiv.org/abs/2203.02540).
- [TriMap](https://github.com/google-research/google-research/tree/master/trimap) - 官方 JAX 实现 [_TriMap: Large-scale Dimensionality Reduction Using Triplets_](https://arxiv.org/abs/1910.00204).

### Flax

- [Performer](https://github.com/google-research/google-research/tree/master/performer/fast_attention/jax) - Performer（通过 FAVOR+ 的线性变压器）架构的 Flax 实现.
- [JaxNeRF](https://github.com/google-research/google-research/tree/master/jaxnerf) - 实施 [_NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis_](http://www.matthewtancik.com/nerf) 支持多设备 GPU/TPU.
- [mip-NeRF](https://github.com/google/mipnerf) - 正式实施 [_Mip-NeRF: A Multiscale Representation for Anti-Aliasing Neural Radiance Fields_](https://jonbarron.info/mipnerf).
- [RegNeRF](https://github.com/google-research/google-research/tree/master/regnerf) - 正式实施 [_RegNeRF: Regularizing Neural Radiance Fields for View Synthesis from Sparse Inputs_](https://m-niemeyer.github.io/regnerf/).
- [Big Transfer (BiT)](https://github.com/google-research/big_transfer) - 实施 [_Big Transfer (BiT): General Visual Representation Learning_](https://arxiv.org/abs/1912.11370).
- [JAX RL](https://github.com/ikostrikov/jax-rl) - 强化学习算法的实现.
- [gMLP](https://github.com/SauravMaheshkar/gMLP) - 实施 [_Pay Attention to MLPs_](https://arxiv.org/abs/2105.08050).
- [MLP Mixer](https://github.com/SauravMaheshkar/MLP-Mixer) - 最低限度的实施 [_MLP-Mixer: An all-MLP Architecture for Vision_](https://arxiv.org/abs/2105.01601).
- [Distributed Shampoo](https://github.com/google-research/google-research/tree/master/scalable_shampoo) - 实施 [_Second Order Optimization Made Practical_](https://arxiv.org/abs/2002.09018).
- [NesT](https://github.com/google-research/nested-transformer) - 正式实施 [_Aggregating Nested Transformers_](https://arxiv.org/abs/2105.12723).
- [XMC-GAN](https://github.com/google-research/xmcgan_image_generation) - 正式实施 [_Cross-Modal Contrastive Learning for Text-to-Image Generation_](https://arxiv.org/abs/2101.04702).
- [FNet](https://github.com/google-research/google-research/tree/master/f_net) - 正式实施 [_FNet: Mixing Tokens with Fourier Transforms_](https://arxiv.org/abs/2105.03824).
- [GFSA](https://github.com/google-research/google-research/tree/master/gfsa) - 正式实施 [_Learning Graph Structure With A Finite-State Automaton Layer_](https://arxiv.org/abs/2007.04929).
- [IPA-GNN](https://github.com/google-research/google-research/tree/master/ipagnn) - 正式实施 [_Learning to Execute Programs with Instruction Pointer Attention Graph Neural Networks_](https://arxiv.org/abs/2010.12621).
- [Flax Models](https://github.com/google-research/google-research/tree/master/flax_models) - 在 Flax 中实现的模型和方法的集合.
- [Protein LM](https://github.com/google-research/google-research/tree/master/protein_lm) - 实现蛋白质的 BERT 和自回归模型，如中所述 [_Biological Structure 和 Function Emerge from Scaling Unsupervised Learning to 250 Million Protein Sequences_](https://www.biorxiv.org/content/10.1101/622803v1.full) 和 [_ProGen: Language Modeling for Protein Generation_](https://www.biorxiv.org/content/10.1101/2020.03.07.982272v2).
- [Slot Attention](https://github.com/google-research/google-research/tree/master/ptopk_patch_selection) - 参考实现 [_Differentiable Patch Selection for Image Recognition_](https://arxiv.org/abs/2104.03059).
- [Vision Transformer](https://github.com/google-research/vision_transformer) - 正式实施 [_An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale_](https://arxiv.org/abs/2010.11929).
- [FID computation](https://github.com/matthias-wright/jax-fid) - 港口 [mseitzer/pytorch-fid](https://github.com/mseitzer/pytorch-fid) 到亚麻.
- [ARDM](https://github.com/google-research/google-research/tree/master/autoregressive_diffusion) - 正式实施 [_Autoregressive Diffusion Models_](https://arxiv.org/abs/2110.02037).
- [D3PM](https://github.com/google-research/google-research/tree/master/d3pm) - 正式实施 [_Structured Denoising Diffusion Models in Discrete State-Spaces_](https://arxiv.org/abs/2107.03006).
- [Gumbel-max Causal Mechanisms](https://github.com/google-research/google-research/tree/master/gumbel_max_causal_gadgets) - 代码 [_Learning Generalized Gumbel-max Causal Mechanisms_](https://arxiv.org/abs/2111.06888), 有额外的代码 [GuyLor/gumbel_max_causal_gadgets_part2](https://github.com/GuyLor/gumbel_max_causal_gadgets_part2).
- [Latent Programmer](https://github.com/google-research/google-research/tree/master/latent_programmer) - ICML 2021 论文的代码 [_Latent Programmer: Discrete Latent Codes for Program Synthesis_](https://arxiv.org/abs/2012.00377).
- [SNeRG](https://github.com/google-research/google-research/tree/master/snerg) - 正式实施 [_Baking Neural Radiance Fields for Real-Time View Synthesis_](https://phog.github.io/snerg).
- [Spin-weighted Spherical CNNs](https://github.com/google-research/google-research/tree/master/spin_spherical_cnns) - 适应 [_Spin-Weighted Spherical CNNs_](https://arxiv.org/abs/2006.10731).
- [VDVAE](https://github.com/google-research/google-research/tree/master/vdvae_flax) - 适应 [_Very Deep VAEs Generalize Autoregressive Models and Can Outperform Them on Images_](https://arxiv.org/abs/2011.10650)，原始代码在 [openai/vdvae](https://github.com/openai/vdvae).
- [MUSIQ](https://github.com/google-research/google-research/tree/master/musiq) - ICCV 2021 论文的检查点和模型推理代码 [_MUSIQ: Multi-scale Image Quality Transformer_](https://arxiv.org/abs/2108.05997)
- [AQuaDem](https://github.com/google-research/google-research/tree/master/aquadem) - 正式实施 [_Continuous Control with Action Quantization from Demonstrations_](https://arxiv.org/abs/2110.10149).
- [Combiner](https://github.com/google-research/google-research/tree/master/combiner) - 正式实施 [_Combiner: Full Attention Transformer with Sparse Computation Cost_](https://arxiv.org/abs/2107.05768).
- [Dreamfields](https://github.com/google-research/google-research/tree/master/dreamfields) - ICLR 2022 论文的正式实施 [_Progressive Distillation for Fast Sampling of Diffusion Models_](https://ajayj.com/dreamfields).
- [GIFT](https://github.com/google-research/google-research/tree/master/gift) - 正式实施 [_Gradual Domain Adaptation in the Wild:When Intermediate Distributions are Absent_](https://arxiv.org/abs/2106.06080).
- [Light Field Neural Rendering](https://github.com/google-research/google-research/tree/master/light_field_neural_rendering) - 正式实施 [_Light Field Neural Rendering_](https://arxiv.org/abs/2112.09687).

### Haiku

- [AlphaFold](https://github.com/deepmind/alphafold) - AlphaFold v2.0 推理管道的实现，见 [_Highly accurate protein structure prediction with AlphaFold_](https://www.nature.com/articles/s41586-021-03819-2).
- [Adversarial Robustness](https://github.com/deepmind/deepmind-research/tree/master/adversarial_robustness) - 参考代码 [_Uncovering the Limits of Adversarial Training against Norm-Bounded Adversarial Examples_](https://arxiv.org/abs/2010.03593) 和 [_Fixing Data Augmentation to Improve Adversarial Robustness_](https://arxiv.org/abs/2103.01946).
- [Bootstrap Your Own Latent](https://github.com/deepmind/deepmind-research/tree/master/byol) - 论文的实施 [_Bootstrap your own latent: A new approach to self-supervised Learning_](https://arxiv.org/abs/2006.07733).
- [Gated Linear Networks](https://github.com/deepmind/deepmind-research/tree/master/gated_linear_networks) - GLN 是一系列无反向传播的神经网络.
- [Glassy Dynamics](https://github.com/deepmind/deepmind-research/tree/master/glassy_dynamics) - 论文的开源实现 [_Unveiling the predictive power of static structure in glassy systems_](https://www.nature.com/articles/s41567-020-0842-8).
- [MMV](https://github.com/deepmind/deepmind-research/tree/master/mmv) - 模型的代码 [_Self-Supervised MultiModal Versatile Networks_](https://arxiv.org/abs/2006.16228).
- [Normalizer-Free Networks](https://github.com/deepmind/deepmind-research/tree/master/nfnets) - 官方俳句实施 [_NFNets_](https://arxiv.org/abs/2102.06171).
- [NuX](https://github.com/Information-Fusion-Lab-Umass/NuX) - 使用 JAX 规范化流程.
- [OGB-LSC](https://github.com/deepmind/deepmind-research/tree/master/ogb_lsc) - 这个存储库包含 DeepMind 对 [PCQM4M-LSC](https://ogb.stanford.edu/kddcup2021/pcqm4m/) （量子化学）和 [MAG240M-LSC](https://ogb.stanford.edu/kddcup2021/mag240m/) （学术图）
的轨道 [OGB Large-Scale Challenge](https://ogb.stanford.edu/kddcup2021/) (OGB-LSC).
- [Persistent Evolution Strategies](https://github.com/google-research/google-research/tree/master/persistent_es) - 用于论文的代码 [_Unbiased Gradient Estimation in Unrolled Computation Graphs with Persistent Evolution Strategies_](http://proceedings.mlr.press/v139/vicol21a.html).
- [Two Player Auction Learning](https://github.com/degregat/two-player-auctions) - 论文的JAX实现 [_Auction learning as a two-player game_](https://arxiv.org/abs/2006.05684).
- [WikiGraphs](https://github.com/deepmind/deepmind-research/tree/master/wikigraphs) - 重现结果的基线代码 [_WikiGraphs: A Wikipedia Text - Knowledge Graph Paired Datase_](https://aclanthology.org/2021.textgraphs-1.7).

### Trax

- [Reformer](https://github.com/google/trax/tree/master/trax/models/reformer) - 实施改革者（高效变压器）架构.


<a name="videos" />

## Videos

- [NeurIPS 2020: JAX Ecosystem Meetup](https://www.youtube.com/watch?v=iDxJxIyzSiM) - JAX，它在 DeepMind 中的使用，以及工程师、科学家和 JAX 核心团队之间的讨论.
- [Introduction to JAX](https://youtu.be/0mVmRHMaOJ4) - 在 JAX 中从头开始的简单神经网络.
- [JAX: Accelerated Machine Learning Research | SciPy 2020 | VanderPlas](https://youtu.be/z-WSrQDXkuM) - JAX 的核心设计，它如何为新研究提供动力，以及如何开始使用它.
- [Bayesian Programming with JAX + NumPyro — Andy Kitchen](https://youtu.be/CecuWGpoztw) - 介绍使用 NumPyro 进行贝叶斯建模.
- [JAX: Accelerated machine-learning research via composable function transformations in Python | NeurIPS 2019 | Skye Wanderman-Milne](https://slideslive.com/38923687/jax-accelerated-machinelearning-research-via-composable-function-transformations-in-python) - JAX 介绍演示 [_Program Transformations for Machine Learning_](https://program-transformations.github.io) 作坊.
- [JAX on Cloud TPUs | NeurIPS 2020 | Skye Wanderman-Milne and James Bradbury](https://drive.google.com/file/d/1jKxefZT1xJDUxMman6qrQVed7vWI0MIn/edit) - 演示 TPU 主机访问.
- [Deep Implicit Layers - Neural ODEs, Deep Equilibirum Models, and Beyond | NeurIPS 2020](https://slideslive.com/38935810/deep-implicit-layers-neural-odes-equilibrium-models-and-beyond) - 由 Zico Kolter、David Duvenaud 和 Matt Johnson 使用 Colab 笔记本创建的教程 [_Deep Implicit Layers_](http://implicit-layers-tutorial.org).
- [Solving y=mx+b with Jax on a TPU Pod slice - Mat Kelcey](http://matpalm.com/blog/ymxb_pod_slice/) - 包含 Colab 笔记本的四部分 YouTube 教程系列，从 Jax 基础知识开始，然后在 v3-32 TPU Pod 切片上使用数据并行方法进行训练.
- [JAX, Flax & Transformers 🤗](https://github.com/huggingface/transformers/blob/9160d81c98854df44b1d543ce5d65a6aa28444a2/examples/research_projects/jax-projects/README.md#talks) - 3 天围绕 JAX / Flax、Transformers、大规模语言建模和其他重要主题的讲座.

<a name="papers" />

## Papers

本节包含专注于 JAX 的论文（例如基于 JAX 的库白皮书、对 JAX 的研究等）. 在 JAX 中实现的论文列在 [Models/Projects](#projects) 部分.

<!--lint ignore awesome-list-item-->
- [__Compiling machine learning programs via high-level tracing__. Roy Frostig, Matthew James Johnson, Chris Leary. _MLSys 2018_.](https://mlsys.org/Conferences/doc/2018/146.pdf) - 描述 JAX 早期版本的白皮书，详细说明如何跟踪和编译计算.
- [__JAX, M.D.: A Framework for Differentiable Physics__. Samuel S. Schoenholz, Ekin D. Cubuk. _NeurIPS 2020_.](https://arxiv.org/abs/1912.04232) - 引入 JAX, MD，一个可微分物理库，其中包括模拟环境、交互势、神经网络等.
- [__Enabling Fast Differentially Private SGD via Just-in-Time Compilation and Vectorization__. Pranav Subramani, Nicholas Vadivelu, Gautam Kamath. _arXiv 2020_.](https://arxiv.org/abs/2010.09063) - 使用 JAX 的 JIT 和 VMAP 来实现比现有库更快的差分私有.
<!--lint enable awesome-list-item-->

<a name="tutorials-and-blog-posts" />

## Tutorials and Blog Posts

- [Using JAX to accelerate our research by David Budden and Matteo Hessel](https://deepmind.com/blog/article/using-jax-to-accelerate-our-research) - 描述 JAX 的状态和 DeepMind 的 JAX 生态系统.
- [Getting started with JAX (MLPs, CNNs & RNNs) by Robert Lange](https://roberttlange.github.io/posts/2020/03/blog-post-10/) - 使用基本的 JAX 运算符从头开始构建神经网络.
- [Tutorial: image classification with JAX and Flax Linen by 8bitmp3](https://github.com/8bitmp3/JAX-Flax-Tutorial-Image-Classification-with-Linen) - 学习如何使用 Flax 的 Linen API 创建一个简单的卷积网络，并训练它识别手写数字.
- [Plugging Into JAX by Nick Doiron](https://medium.com/swlh/plugging-into-jax-16c120ec3302) - 在 Kaggle 花卉分类挑战中比较 Flax、Haiku 和 Objax.
- [Meta-Learning in 50 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/02/maml-jax.html) - JAX 和元学习简介.
- [Normalizing Flows in 100 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/07/nf-jax.html) - 简洁的实现 [RealNVP](https://arxiv.org/abs/1605.08803).
- [Differentiable Path Tracing on the GPU/TPU by Eric Jang](https://blog.evjang.com/2019/11/jaxpt.html) - 实现路径跟踪的教程.
- [Ensemble networks by Mat Kelcey](http://matpalm.com/blog/ensemble_nets) - 集成网络是一种将模型集成表示为单个逻辑模型的方法.
- [Out of distribution (OOD) detection by Mat Kelcey](http://matpalm.com/blog/ood_using_focal_loss) - 实现不同的OOD检测方法.
- [Understanding Autodiff with JAX by Srihari Radhakrishna](https://www.radx.in/jax.html) - 了解 autodiff 如何使用 JAX 工作.
- [From PyTorch to JAX: towards neural net frameworks that purify stateful code by Sabrina J. Mielke](https://sjmielke.com/jax-purify.htm) - 展示如何从类似 PyTorch 的编码风格转变为更实用的编码风格.
- [Extending JAX with custom C++ and CUDA code by Dan Foreman-Mackey](https://github.com/dfm/extending-jax) - 演示在 JAX 中提供自定义操作所需的基础设施的教程.
- [Evolving Neural Networks in JAX by Robert Tjarko Lange](https://roberttlange.github.io/posts/2021/02/cma-es-jax/) - 探索 JAX 如何为下一代可扩展的神经进化算法提供动力.
- [Exploring hyperparameter meta-loss landscapes with JAX by Luke Metz](http://lukemetz.com/exploring-hyperparameter-meta-loss-landscapes-with-jax/) - 演示如何使用 JAX 使用 SGD 和 Momentum 执行内部损失优化，使用梯度进行外部损失优化，以及使用进化策略执行外部损失优化.
- [Deterministic ADVI in JAX by Martin Ingram](https://martiningram.github.io/deterministic-advi/) - 使用 JAX 轻松、干净地实现自动微分变分推理 (ADVI).
- [Evolved channel selection by Mat Kelcey](http://matpalm.com/blog/evolved_channel_selection/) - 训练一个对不同分辨率的不同输入通道组合具有鲁棒性的分类模型，然后使用遗传算法来确定特定损失的最佳组合.
- [Introduction to JAX by Kevin Murphy](https://colab.research.google.com/github/probml/probml-notebooks/blob/main/notebooks/jax_intro.ipynb) - Colab，它介绍了语言的各个方面并将它们应用于简单的 ML 问题.
- [Writing an MCMC sampler in JAX by Jeremie Coullon](https://www.jeremiecoullon.com/2020/11/10/mcmcjax3ways/) - 关于在 JAX 中编写 MCMC 采样器的不同方法以及速度基准的教程.
- [How to add a progress bar to JAX scans and loops by Jeremie Coullon](https://www.jeremiecoullon.com/2021/01/29/jax_progress_bar/) - 关于如何使用 `host_callback` 模块向 JAX 中的已编译循环添加进度条的教程.
- [Get started with JAX by Aleksa Gordić](https://github.com/gordicaleksa/get-started-with-JAX) - 从零 JAX 知识到在 Haiku 中构建神经网络的一系列笔记本和视频.

<a name="community" />

## Community

- [JAX GitHub Discussions](https://github.com/google/jax/discussions)
- [Reddit](https://www.reddit.com/r/JAX/)

## Contributing

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/n2cholas/awesome-jax/blob/master/contributing.md) 第一的.
