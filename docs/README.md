<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-13
- 运行时间：2026-06-13 21:49:24 UTC
- 运行状态：成功
- 本次总论文数：44
- 精读区：30
- 速读区：14

### 今日简报（AI）
今日聚焦LLM推理效率，解析两项高分研究：推理感知的KV缓存共享与自信早期退出、稀疏门控微型线性专家。最值得关注的方向是KV缓存优化与模型稀疏化，前者通过共享和早退减少多步推理延迟，后者以极简线性层实现高效门控。建议普通读者优先研读《RKSC》与《Sparsely gated tiny linear experts》，并留意速读中关于NPU性能分级与LoRA缓存压缩的实用分析。
- 详情：[/202606/13/README](/202606/13/README)

### 精读区论文标签
1. [RKSC: Reasoning-Aware KV Cache Sharing and Confident Early Exit for Multi-Step LLM Inference](/202606/13/2606.09937v1-rksc-reasoning-aware-kv-cache-sharing-and-confident-early-exit-for-multi-step-llm-inference)  
   标签：评分：10.0/10、query:eli
   evidence：多步推理中的KV缓存共享与早停
2. [Sparsely gated tiny linear experts](/202606/13/2606.07414v1-sparsely-gated-tiny-linear-experts)  
   标签：评分：9.0/10、query:eli
   evidence：用稀疏门控线性神经元替换Transformer前馈层以提升计算效率
3. [Attention at the Theoretical Minimum: A Mathematics of Arrays Framework for Memory-Optimal Transformer Kernels](/202606/13/2606.07713v1-attention-at-the-theoretical-minimum-a-mathematics-of-arrays-framework-for-memory-optimal-transformer-kernels)  
   标签：评分：9.0/10、query:llm-kernel
   evidence：高效Transformer的FlashAttention机制
4. [Seeing is Believing: Aligning Prompt Rewriting with Visual Anchors for Text-to-Image Generation](/202606/13/2606.08492v1-seeing-is-believing-aligning-prompt-rewriting-with-visual-anchors-for-text-to-image-generation)  
   标签：评分：9.0/10、query:mg
   evidence：利用视觉锚点增强文本到图像生成的提示
5. [Look Less, Reason More: Block-wise Attention Skipping for Efficient Multimodal LLMs](/202606/13/2606.08511v1-look-less-reason-more-block-wise-attention-skipping-for-efficient-multimodal-llms)  
   标签：评分：9.0/10、query:eli
   evidence：LLM加速；块级注意力跳跃实现高效多模态LLM推理
6. [APEX4: Efficient Pure W4A4 LLM Inference via Intra-SM Compute Rebalancing](/202606/13/2606.08761v1-apex4-efficient-pure-w4a4-llm-inference-via-intra-sm-compute-rebalancing)  
   标签：评分：9.0/10、query:compression
   evidence：系统研究SM内计算平衡以实现W4A4 LLM推理
7. [PALUTE: Processing-In-Memory Acceleration via Lookup Table for Edge LLM Inference](/202606/13/2606.08891v1-palute-processing-in-memory-acceleration-via-lookup-table-for-edge-llm-inference)  
   标签：评分：9.0/10、query:eli
   evidence：面向边缘LLM推理的存内查找表加速器
8. [Fairness-Aware and Latency-Controllable Scheduling for Chunked-Prefill LLM Serving](/202606/13/2606.09061v1-fairness-aware-and-latency-controllable-scheduling-for-chunked-prefill-llm-serving)  
   标签：评分：9.0/10、query:eli
   evidence：面向LLM服务的延迟可控调度
9. [FlashMemory-DeepSeek-V4: Lightning Index Ultra-Long Context via Lookahead Sparse Attention](/202606/13/2606.09079v1-flashmemory-deepseek-v4-lightning-index-ultra-long-context-via-lookahead-sparse-attention)  
   标签：评分：9.0/10、query:eli
   evidence：通过前瞻稀疏注意力进行KV缓存优化
10. [FlashMemory-DeepSeek-V4: Lightning Index Ultra-Long Context via Lookahead Sparse Attention](/202606/13/2606.09079v2-flashmemory-deepseek-v4-lightning-index-ultra-long-context-via-lookahead-sparse-attention)  
   标签：评分：9.0/10、query:eli
   evidence：基于前瞻稀疏注意力的KV缓存优化，支持超长上下文
11. [From Rigid to Dynamic: Entropy-Guided Adaptive Inference for Long-Context LLMs](/202606/13/2606.09508v1-from-rigid-to-dynamic-entropy-guided-adaptive-inference-for-long-context-llms)  
   标签：评分：9.0/10、query:eli
   evidence：基于熵引导的长上下文LLM自适应推理与KV缓存压缩
12. [TUDSR: Twice Upsampling-Diffusion for Higher Super-Resolution](/202606/13/2606.09608v1-tudsr-twice-upsampling-diffusion-for-higher-super-resolution)  
   标签：评分：9.0/10、query:mg
   evidence：基于扩散的两次上采样实现超越原生分辨率的图像超分辨率
13. [Trainable Smooth-Rotation Transforms with Learned Channel Scales for LLM Quantization](/202606/13/2606.09927v1-trainable-smooth-rotation-transforms-with-learned-channel-scales-for-llm-quantization)  
   标签：评分：9.0/10、query:compression
   evidence：后训练量化结合平滑旋转变换用于大语言模型
14. [UniSVQ: 2-bit Unified Scalar-Vector Quantization](/202606/13/2606.10520v1-unisvq-2-bit-unified-scalar-vector-quantization)  
   标签：评分：9.0/10、query:compression
   evidence：大语言模型2位统一标量-向量量化
15. [Prefilling-dLLM: Predictive Prefilling for Long-Context Inference in Diffusion Language Models](/202606/13/2606.10537v1-prefilling-dllm-predictive-prefilling-for-long-context-inference-in-diffusion-language-models)  
   标签：评分：9.0/10、query:eli
   evidence：提出前缀KV缓存和稀疏预填充策略，加速长上下文推理
16. [STEDiff: Strengthening Text Embedding for Text-to-Image Alignment in Diffusion Model](/202606/13/2606.10653v1-stediff-strengthening-text-embedding-for-text-to-image-alignment-in-diffusion-model)  
   标签：评分：9.0/10、query:mg
   evidence：扩散模型中无需训练的文本嵌入增强用于文本到图像对齐
17. [K-Forcing: Joint Next-K-Token Decoding via Push-Forward Language Modeling](/202606/13/2606.10820v1-k-forcing-joint-next-k-token-decoding-via-push-forward-language-modeling)  
   标签：评分：9.0/10、query:eli
   evidence：联合下k令牌解码加速LLM推理
18. [K-Forcing: Joint Next-K-Token Decoding via Push-Forward Language Modeling](/202606/13/2606.10820v2-k-forcing-joint-next-k-token-decoding-via-push-forward-language-modeling)  
   标签：评分：9.0/10、query:eli
   evidence：提出联合多令牌解码方法加速推理，类似投机解码思路
19. [Optimal Post-Training Quantization Scales and Where to Find Them](/202606/13/2606.10890v1-optimal-post-training-quantization-scales-and-where-to-find-them)  
   标签：评分：9.0/10、query:compression
   evidence：大语言模型后训练量化
20. [CLP: Collocation-Length Prediction for Zero-Loss Adaptive Multi-Token Inference](/202606/13/2606.10935v1-clp-collocation-length-prediction-for-zero-loss-adaptive-multi-token-inference)  
   标签：评分：9.0/10、query:eli
   evidence：多令牌预测用于投机解码
21. [Express Language Modeling](/202606/13/2606.10944v1-express-language-modeling)  
   标签：评分：9.0/10、query:llm-kernel
   evidence：高效的I/O感知Triton实现，比FlashAttention 2提速
22. [Mean Flow Distillation: Robust and Stable Distillation for Flow Matching Models](/202606/13/2606.11155v1-mean-flow-distillation-robust-and-stable-distillation-for-flow-matching-models)  
   标签：评分：9.0/10、query:mg
   evidence：面向流匹配模型的均值流蒸馏方法
23. [ReasonAlloc: Hierarchical Decoding-Time KV Cache Budget Allocation for Reasoning Models](/202606/13/2606.11164v1-reasonalloc-hierarchical-decoding-time-kv-cache-budget-allocation-for-reasoning-models)  
   标签：评分：9.0/10、query:eli
   evidence：面向LLM推理的层次化解码时KV缓存预算分配
24. [SPEAR: A System for Post-Quantization Error-Adaptive Recovery Enabling Efficient Low-Bit LLM Serving](/202606/13/2606.11244v1-spear-a-system-for-post-quantization-error-adaptive-recovery-enabling-efficient-low-bit-llm-serving)  
   标签：评分：9.0/10、query:compression
   evidence：面向低比特LLM服务的后量化误差自适应恢复
25. [Teaching Diffusion to Speculate Left-to-Right](/202606/13/2606.11552v1-teaching-diffusion-to-speculate-left-to-right)  
   标签：评分：9.0/10、query:eli
   evidence：利用扩散语言模型作为投机解码的草稿模型
26. [A Comprehensive Ecosystem for Open-Domain Customized Video Generation](/202606/13/2606.11783v1-a-comprehensive-ecosystem-for-open-domain-customized-video-generation)  
   标签：评分：9.0/10、query:mg
   evidence：基于扩散Transformer的文本生成视频
27. [Plan-and-Verify Video Reward Reasoning with Spatio-Temporal Scene Graph Grounding](/202606/13/2606.11838v1-plan-and-verify-video-reward-reasoning-with-spatio-temporal-scene-graph-grounding)  
   标签：评分：9.0/10、query:mg
   evidence：使用时空场景图的计划与验证视频奖励模型用于文本到视频对齐
28. [SpecLoR: Spectral Lookahead Rectification for Motion-Coherent Text-to-Video Generation](/202606/13/2606.11969v1-speclor-spectral-lookahead-rectification-for-motion-coherent-text-to-video-generation)  
   标签：评分：9.0/10、query:mg
   evidence：文本到视频生成，使用流匹配和前瞻校正
29. [VIA-SD: Verification via Intra-Model Routing for Speculative Decoding](/202606/13/2606.12243v1-via-sd-verification-via-intra-model-routing-for-speculative-decoding)  
   标签：评分：9.0/10、query:eli
   evidence：基于模型内路由验证的投机解码
30. [Holding the FP8 Quality Ceiling at 8-Bit Weights and Activations: INT8 and GGUF Post-Training Quantization of Ideogram 4.0 for Consumer GPUs](/202606/13/2606.12280v1-holding-the-fp8-quality-ceiling-at-8-bit-weights-and-activations-int8-and-gguf-post-training-quantization-of-ideogram-40-for-consumer-gpus)  
   标签：评分：9.0/10、query:mg
   evidence：文本到图像生成使用扩散Transformer和流匹配；对Ideogram 4.0进行后训练量化

### 速读区论文标签
1. [When NPUs Are Not Always Faster: A Stage-Level Analysis of Mobile LLM Inference](/202606/13/2605.27435v1-when-npus-are-not-always-faster-a-stage-level-analysis-of-mobile-llm-inference)  
   标签：评分：8.0/10、query:eli
   evidence：首次对异构SoC上的移动LLM推理进行系统性阶段级分析，揭示性能反转，指导低延迟部署。
2. [Threshold-Based Exclusive Batching for LLM Inference](/202606/13/2606.00516v1-threshold-based-exclusive-batching-for-llm-inference)  
   标签：评分：8.0/10、query:eli
   evidence：分析批处理中预填充-解码干扰，提出基于阈值独占批处理以提升吞吐量
3. [Rethinking LoRA Memory Through the Lens of KV Cache Compression](/202606/13/2606.05698v1-rethinking-lora-memory-through-the-lens-of-kv-cache-compression)  
   标签：评分：8.0/10、query:eli
   evidence：研究LoRA内存与KV缓存压缩的交互，与KV缓存优化相关
4. [Domain-Adapted Small Language Models with Hybrid Post-Processing: Achieving Cost-Efficient, Low-Latency Multi-Label Structured Prediction via LoRA Fine-Tuning on Scarce Data](/202606/13/2606.05781v2-domain-adapted-small-language-models-with-hybrid-post-processing-achieving-cost-efficient-low-latency-multi-label-structured-prediction-via-lora-fine-tuning-on-scarce-data)  
   标签：评分：8.0/10、query:eli
   evidence：使用小语言模型+LoRA+后处理实现低延迟结构预测
5. [QCFuse: Query-Aware Cache Fusion via Compressed View for Efficient RAG Serving](/202606/13/2606.05875v1-qcfuse-query-aware-cache-fusion-via-compressed-view-for-efficient-rag-serving)  
   标签：评分：8.0/10、query:eli
   evidence：面向高效RAG服务的查询感知KV缓存融合
6. [Gated Bidirectional Linear Attention for Generative Retrieval](/202606/13/2606.07317v2-gated-bidirectional-linear-attention-for-generative-retrieval)  
   标签：评分：7.0/10、query:eli
   evidence：线性时间双向注意力减少推理延迟
7. [Sparse Subspace-to-Expert Sharing for Task-Agnostic Continual Learning](/202606/13/2606.07500v1-sparse-subspace-to-expert-sharing-for-task-agnostic-continual-learning)  
   标签：评分：7.0/10、query:compression
   evidence：面向LLM持续学习的稀疏子空间到专家共享
8. [Where the Score Lives: A Wavelet View of Diffusion](/202606/13/2606.08309v1-where-the-score-lives-a-wavelet-view-of-diffusion)  
   标签：评分：7.0/10、query:mg
   evidence：扩散模型生成任务
9. [Sparrow: Sparse Rollout for Stable and Efficient Long-context RL of Large Language Models](/202606/13/2606.08446v1-sparrow-sparse-rollout-for-stable-and-efficient-long-context-rl-of-large-language-models)  
   标签：评分：7.0/10、query:eli
   evidence：稀疏注意力加速长上下文推理
10. [Toward Compiler World Models: Learning Latent Dynamics for Efficient Tensor Program Search](/202606/13/2606.09312v1-toward-compiler-world-models-learning-latent-dynamics-for-efficient-tensor-program-search)  
   标签：评分：7.0/10、query:llm-kernel
   evidence：张量程序优化自动调度
11. [Tensorizing Engram: Sharing Latents Across N-Gram Embeddings is Beneficial in LLMs](/202606/13/2606.08347v1-tensorizing-engram-sharing-latents-across-n-gram-embeddings-is-beneficial-in-llms)  
   标签：评分：6.0/10、query:eli
   evidence：张量化n-gram内存模块用于高效令牌表示
12. [FlashCP: Load-Balanced Communication-Efficient Context Parallelism for LLM Training](/202606/13/2606.08476v1-flashcp-load-balanced-communication-efficient-context-parallelism-for-llm-training)  
   标签：评分：6.0/10、query:llm-kernel
   evidence：面向LLM训练的负载均衡通信高效上下文并行，消除冗余KV通信
13. [TRADE: Transducer-Augmented Decoder for Speech LLM](/202606/13/2606.08486v1-trade-transducer-augmented-decoder-for-speech-llm)  
   标签：评分：6.0/10、query:eli
   evidence：换能器增强解码器实现低延迟流式语音LLM推理
14. [Distilling LLM Reasoning into an Interpretable Policy Tree for Human-AI Collaboration](/202606/13/2606.08596v1-distilling-llm-reasoning-into-an-interpretable-policy-tree-for-human-ai-collaboration)  
   标签：评分：6.0/10、query:compression
   evidence：通过蒸馏LLM推理到策略树降低推理成本


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
