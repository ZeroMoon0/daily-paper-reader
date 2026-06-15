<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-15
- 运行时间：2026-06-15 23:21:48 UTC
- 运行状态：成功
- 本次总论文数：28
- 精读区：14
- 速读区：14

### 今日简报（AI）
今日日报聚焦LLM剪枝基准和视频时间编辑两大前沿突破。最值得关注《Beyond FLOPs》提出基于GEMM的剪枝加速基准和《Making Time Editable》实现视频扩散模型的时间控制。建议优先精读这两篇，速读可选KV压缩与视觉自回归模型优化。
- 详情：[/202606/15/README](/202606/15/README)

### 精读区论文标签
1. [Beyond FLOPs: Benchmarking Real Inference Acceleration of LLM Pruning under a GEMM-Centric Taxonomy](/202606/15/2606.09080v1-beyond-flops-benchmarking-real-inference-acceleration-of-llm-pruning-under-a-gemm-centric-taxonomy)  
   标签：评分：9.0/10、query:compression
   evidence：LLM剪枝，推理加速基准测试，以GEMM为中心的分类法
2. [Making Time Editable in Video Diffusion Transformers](/202606/15/2606.10183v1-making-time-editable-in-video-diffusion-transformers)  
   标签：评分：9.0/10、query:mg
   evidence：带时间编辑的视频扩散Transformer
3. [FoA-SR: Faithful or Aesthetic? Profile-Aware Preference Optimization for Real-World Image Super-Resolution](/202606/15/2606.10275v1-foa-sr-faithful-or-aesthetic-profile-aware-preference-optimization-for-real-world-image-super-resolution)  
   标签：评分：9.0/10、query:mg
   evidence：基于扩散模型和轮廓感知偏好优化的真实世界图像超分辨率
4. [Exploring the Design Space of Reward Backpropagation for Flow Matching](/202606/15/2606.11075v1-exploring-the-design-space-of-reward-backpropagation-for-flow-matching)  
   标签：评分：9.0/10、query:mg
   evidence：文本到图像生成中的流匹配模型对齐
5. [Piper: A Programmable Distributed Training System](/202606/15/2606.11169v1-piper-a-programmable-distributed-training-system)  
   标签：评分：9.0/10、query:llm-kernel
   evidence：可编程的大模型分布式训练系统，支持多种并行策略
6. [DynamicPTQ: Mitigating Activation Quantization Collapse via Residual-Stream Dynamics](/202606/15/2606.12487v1-dynamicptq-mitigating-activation-quantization-collapse-via-residual-stream-dynamics)  
   标签：评分：9.0/10、query:compression
   evidence：面向大语言模型的后训练量化，通过残差流动态解决激活量化崩溃问题
7. [Multi-Bitwidth Quantization for LLMs Using Additive Codebooks](/202606/15/2606.12876v1-multi-bitwidth-quantization-for-llms-using-additive-codebooks)  
   标签：评分：9.0/10、query:compression
   evidence：大语言模型多比特宽度后训练量化
8. [TWLA: Achieving Ternary Weights and Low-Bit Activations for LLMs via Post-Training Quantization](/202606/15/2606.13054v2-twla-achieving-ternary-weights-and-low-bit-activations-for-llms-via-post-training-quantization)  
   标签：评分：9.0/10、query:compression
   evidence：面向大语言模型的三值权重和低比特激活后训练量化
9. [MiniMax Sparse Attention](/202606/15/2606.13392v1-minimax-sparse-attention)  
   标签：评分：9.0/10、query:eli
   evidence：基于KV块的块稀疏注意力，减少KV缓存使用和计算量
10. [MiniMax Sparse Attention](/202606/15/2606.13392v2-minimax-sparse-attention)  
   标签：评分：9.0/10、query:eli
   evidence：基于KV块的块稀疏注意力，减少KV缓存使用和计算量
11. [Efficient On-Device Diffusion LLM Inference with Mobile NPU](/202606/15/2606.13740v1-efficient-on-device-diffusion-llm-inference-with-mobile-npu)  
   标签：评分：9.0/10、query:eli
   evidence：设备端扩散LLM推理，移动NPU，低延迟
12. [FoleyGenEx: Unified Video-to-Audio Generation with Multi-Modal Control, Temporal Alignment, and Semantic Precision](/202606/15/2606.14049v1-foleygenex-unified-video-to-audio-generation-with-multi-modal-control-temporal-alignment-and-semantic-precision)  
   标签：评分：9.0/10、query:mg
   evidence：统一视频到音频生成框架
13. [Improving Lunar Topography with Deep Learning Schrödinger Bridges](/202606/15/2606.14638v1-improving-lunar-topography-with-deep-learning-schrdinger-bridges)  
   标签：评分：9.0/10、query:mg
   evidence：扩散模型用于月球地形超分辨率
14. [RepFusion: Leveraging Multimodal Priors for Denoising in Representation Space](/202606/15/2606.14700v1-repfusion-leveraging-multimodal-priors-for-denoising-in-representation-space)  
   标签：评分：9.0/10、query:mg
   evidence：利用多模态大模型先验进行文本到图像扩散生成

### 速读区论文标签
1. [HACK++: Towards More Effective Head-Aware Key-Value Compression for Efficient Visual Autoregressive Modeling](/202606/15/2606.08302v1-hack-towards-more-effective-head-aware-key-value-compression-for-efficient-visual-autoregressive-modeling)  
   标签：评分：8.0/10、query:eli
   evidence：面向视觉自回归模型的头部感知 KV 缓存压缩
2. [Q-Delta: Beyond Key-Value Associative State Evolution](/202606/15/2606.08804v1-q-delta-beyond-key-value-associative-state-evolution)  
   标签：评分：8.0/10、query:eli
   evidence：查询感知的delta规则改进线性注意力状态演化，提升KV缓存效率
3. [CSFlow: Aligning Flow Matching with Human Contrast Sensitivity](/202606/15/2606.08833v1-csflow-aligning-flow-matching-with-human-contrast-sensitivity)  
   标签：评分：8.0/10、query:mg
   evidence：将流匹配去噪步骤与人类对比敏感度对齐以改善图像生成
4. [HoliDubber: Holistic Video Dubbing for Complex Acoustic Scenes via Text-Guided Audio Synthesis](/202606/15/2606.09098v1-holidubber-holistic-video-dubbing-for-complex-acoustic-scenes-via-text-guided-audio-synthesis)  
   标签：评分：8.0/10、query:mg
   evidence：使用扩散Transformer的联合语音与音效合成实现全景视频配音
5. [Late-Layer Fusion is Enough: Dual-Path Vision Token Routing for Multimodal Large Language Models under Visual Saturation](/202606/15/2606.09131v1-late-layer-fusion-is-enough-dual-path-vision-token-routing-for-multimodal-large-language-models-under-visual-saturation)  
   标签：评分：8.0/10、query:mg
   evidence：通过视觉令牌路由解决多模态大模型推理中的计算冗余
6. [FlashCP: Load-Balanced Communication-Efficient Context Parallelism for LLM Training](/202606/15/2606.08476v1-flashcp-load-balanced-communication-efficient-context-parallelism-for-llm-training)  
   标签：评分：7.0/10、query:llm-kernel
   evidence：使用上下文并行训练大语言模型，优化KV通信
7. [BLM-SGAN: Bidirectional Language Modeling for Semantic-Spatial Text-to-Image Generation](/202606/15/2606.08847v1-blm-sgan-bidirectional-language-modeling-for-semantic-spatial-text-to-image-generation)  
   标签：评分：7.0/10、query:mg
   evidence：基于GAN的双向语言建模文本到图像生成
8. [TLDR: Compressing Audio Tokens for Efficient Autoregressive Text-to-Speech](/202606/15/2606.09019v1-tldr-compressing-audio-tokens-for-efficient-autoregressive-text-to-speech)  
   标签：评分：7.0/10、query:mg
   evidence：压缩音频令牌以实现高效自回归文本到语音
9. [LiteVSR: Lightweight Adaptation of Frozen Diffusion Transformers for Video Super-Resolution](/202606/15/2606.09250v1-litevsr-lightweight-adaptation-of-frozen-diffusion-transformers-for-video-super-resolution)  
   标签：评分：7.0/10、query:mg
   evidence：使用冻结扩散Transformer的轻量级视频超分
10. [Sigma-Branch: Hierarchical Single-Path Network Reconstruction for Dynamic Inference with Reduced Active Parameters](/202606/15/2606.09924v1-sigma-branch-hierarchical-single-path-network-reconstruction-for-dynamic-inference-with-reduced-active-parameters)  
   标签：评分：7.0/10、query:compression
   evidence：通过层次化网络重构实现动态推理，减少活跃参数，用于模型压缩
11. [Cross-Modal Knowledge Distillation without Paired Data: Theoretical Foundation and Algorithm](/202606/15/2606.10504v1-cross-modal-knowledge-distillation-without-paired-data-theoretical-foundation-and-algorithm)  
   标签：评分：6.0/10、query:compression
   evidence：无配对数据的跨模态知识蒸馏用于模型压缩
12. [Attention-Discounted Adaptive Sampler for Masked Diffusion Language Models](/202606/15/2606.10829v1-attention-discounted-adaptive-sampler-for-masked-diffusion-language-models)  
   标签：评分：6.0/10、query:mg
   evidence：面向掩码扩散语言模型的训练自由自适应采样器
13. [G-Long: Graph-Enhanced Memory Management for Efficient Long-Term Dialogue Agents](/202606/15/2606.13115v1-g-long-graph-enhanced-memory-management-for-efficient-long-term-dialogue-agents)  
   标签：评分：6.0/10、query:eli
   evidence：通过图记忆和轻量模型降低延迟
14. [Enhanced Low-Density Region Exploration in Classifier-Guided Diffusion Models Through Modified Reverse Diffusion Sampling](/202606/15/2606.13347v1-enhanced-low-density-region-exploration-in-classifier-guided-diffusion-models-through-modified-reverse-diffusion-sampling)  
   标签：评分：6.0/10、query:mg
   evidence：修改反向扩散采样以改进分类器引导扩散模型中的低密度区域探索


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
