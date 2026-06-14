<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-14
- 运行时间：2026-06-14 22:03:06 UTC
- 运行状态：成功
- 本次总论文数：31
- 精读区：17
- 速读区：14

### 今日简报（AI）
今日共筛选31篇论文，精读17篇，其中两篇获满分：探讨键值状态演进的《Q-Delta》与大模型后训练量化方案《TWLA》。

最值得关注方向：大模型KV缓存高效化与低位量化推理技术，以及速读中的SLO感知调度和图像生成多样性方法。

建议普通读者优先精读两篇满分论文，速读中关注《Breaking the Lock-in》的图像生成控制技巧。
- 详情：[/202606/14/README](/202606/14/README)

### 精读区论文标签
1. [Q-Delta: Beyond Key-Value Associative State Evolution](/202606/14/2606.08804v1-q-delta-beyond-key-value-associative-state-evolution)  
   标签：评分：10.0/10、query:eli
   evidence：线性注意力中查询感知的delta规则用于KV状态演化，提升推理效率
2. [TWLA: Achieving Ternary Weights and Low-Bit Activations for LLMs via Post-Training Quantization](/202606/14/2606.13054v1-twla-achieving-ternary-weights-and-low-bit-activations-for-llms-via-post-training-quantization)  
   标签：评分：10.0/10、query:compression
   evidence：面向LLM的后训练量化，实现三值权重和4比特激活
3. [NGram-MoSE: Efficient Remote Sensing Super-Resolution via N-Gram Context and Mixture-of-Experts](/202606/14/2606.08535v1-ngram-mose-efficient-remote-sensing-super-resolution-via-n-gram-context-and-mixture-of-experts)  
   标签：评分：9.0/10、query:mg
   evidence：用于图像超分的高效Transformer
4. [Understanding Quantization-Aware Training: Gradients at Quantized Weights Bias to the Low-Loss Basin](/202606/14/2606.09012v1-understanding-quantization-aware-training-gradients-at-quantized-weights-bias-to-the-low-loss-basin)  
   标签：评分：9.0/10、query:compression
   evidence：解释极端压缩下 PTQ 失败和 QAT 恢复的几何框架
5. [Making Time Editable in Video Diffusion Transformers](/202606/14/2606.10183v1-making-time-editable-in-video-diffusion-transformers)  
   标签：评分：9.0/10、query:mg
   evidence：视频扩散Transformer的时间编辑，与基于DiT的视频生成相关
6. [PADD: Path-Aligned Decompression Distillation for Non-Router Teacher to Guide MoE Student Learning](/202606/14/2606.10369v1-padd-path-aligned-decompression-distillation-for-non-router-teacher-to-guide-moe-student-learning)  
   标签：评分：9.0/10、query:compression
   evidence：从密集教师到MoE学生的知识蒸馏，用于模型压缩
7. [SpenseGPT: Practical One-shot Pruning Enabling Sparse and Dense GEMMs for LLM Inference](/202606/14/2606.10445v1-spensegpt-practical-one-shot-pruning-enabling-sparse-and-dense-gemms-for-llm-inference)  
   标签：评分：9.0/10、query:compression
   evidence：混合稀疏-稠密剪枝方法，加速LLM推理
8. [LC-QAT: Data-Efficient 2-Bit QAT for LLMs via Linear-Constrained Vector Quantization](/202606/14/2606.10531v1-lc-qat-data-efficient-2-bit-qat-for-llms-via-linear-constrained-vector-quantization)  
   标签：评分：9.0/10、query:compression
   evidence：基于线性约束向量量化的2比特权重量化感知训练
9. [Exploring the Design Space of Reward Backpropagation for Flow Matching](/202606/14/2606.11075v1-exploring-the-design-space-of-reward-backpropagation-for-flow-matching)  
   标签：评分：9.0/10、query:mg
   evidence：用于文本到图像流匹配模型对齐的奖励反向传播
10. [Task-Aware Structured Memory for Dynamic Multi-modal In-Context Learning](/202606/14/2606.11853v1-task-aware-structured-memory-for-dynamic-multi-modal-in-context-learning)  
   标签：评分：9.0/10、query:eli
   evidence：多模态大语言模型的任务感知KV缓存压缩
11. [On Subquadratic Architectures: From Applications to Principles](/202606/14/2606.12364v1-on-subquadratic-architectures-from-applications-to-principles)  
   标签：评分：9.0/10、query:eli
   evidence：比较次二次架构用于高效LLM推理和训练
12. [DynamicPTQ: Mitigating Activation Quantization Collapse via Residual-Stream Dynamics](/202606/14/2606.12487v1-dynamicptq-mitigating-activation-quantization-collapse-via-residual-stream-dynamics)  
   标签：评分：9.0/10、query:compression
   evidence：后训练量化LLM，包含激活和KV缓存量化
13. [High-Fidelity Two-Step Image Generation via Teacher-Aligned End-to-End Distillation](/202606/14/2606.12575v1-high-fidelity-two-step-image-generation-via-teacher-aligned-end-to-end-distillation)  
   标签：评分：9.0/10、query:mg
   evidence：两步图像生成蒸馏
14. [Multi-Bitwidth Quantization for LLMs Using Additive Codebooks](/202606/14/2606.12876v1-multi-bitwidth-quantization-for-llms-using-additive-codebooks)  
   标签：评分：9.0/10、query:compression
   evidence：LLM多比特宽后训练量化
15. [MiniPIC: Flexible Position-Independent Caching in <100LOC](/202606/14/2606.13126v1-minipic-flexible-position-independent-caching-in-100loc)  
   标签：评分：9.0/10、query:eli
   evidence：灵活的位置无关缓存实现KV缓存重用
16. [Can I Buy Your KV Cache?](/202606/14/2606.13361v1-can-i-buy-your-kv-cache)  
   标签：评分：9.0/10、query:eli
   evidence：KV缓存共享跳过预填充，降低推理延迟
17. [GF-DiT: Scheduling Parallelism for Diffusion Transformer Serving](/202606/14/2606.13501v1-gf-dit-scheduling-parallelism-for-diffusion-transformer-serving)  
   标签：评分：9.0/10、query:mg
   evidence：扩散Transformer服务的并行调度

### 速读区论文标签
1. [Beyond Greedy Chunking: SLO-Aware Sliding-Window Scheduling for LLM Inference](/202606/14/2606.05933v1-beyond-greedy-chunking-slo-aware-sliding-window-scheduling-for-llm-inference)  
   标签：评分：8.0/10、query:eli
   evidence：基于SLO感知的滑动窗口调度实现低延迟LLM推理
2. [Breaking the Lock-in: Diversifying Text-to-Image Generation via Representation Modulation](/202606/14/2606.06813v1-breaking-the-lock-in-diversifying-text-to-image-generation-via-representation-modulation)  
   标签：评分：8.0/10、query:mg
   evidence：文本到图像扩散Transformer的多样性增强
3. [AsyncPatch Diffusion: spatially-flexible image generation](/202606/14/2606.07079v1-asyncpatch-diffusion-spatially-flexible-image-generation)  
   标签：评分：8.0/10、query:mg
   evidence：空间自适应的扩散图像生成
4. [Gated Bidirectional Linear Attention for Generative Retrieval](/202606/14/2606.07317v1-gated-bidirectional-linear-attention-for-generative-retrieval)  
   标签：评分：8.0/10、query:eli
   evidence：线性时间双向注意力减少编码器延迟
5. [How Much Dense Attention is Necessary? Oracle-Guided Sparse Prefill for Full/GQA Layers in Hybrid Long-Context Models](/202606/14/2606.07703v1-how-much-dense-attention-is-necessary-oracle-guided-sparse-prefill-for-fullgqa-layers-in-hybrid-long-context-models)  
   标签：评分：8.0/10、query:eli
   evidence：Oracle引导的稀疏预填充减少混合LLM中长上下文注意力成本
6. [AsyncLane: Decoupling Refinement from Advancement in Diffusion Language Model Decoding](/202606/14/2606.08411v1-asynclane-decoupling-refinement-from-advancement-in-diffusion-language-model-decoding)  
   标签：评分：7.0/10、query:eli
   evidence：通过异步通道加速扩散语言模型解码
7. [Unified Energy for Invariant and Independent Decoding in Diffusion Language Models](/202606/14/2606.09159v1-unified-energy-for-invariant-and-independent-decoding-in-diffusion-language-models)  
   标签：评分：7.0/10、query:mg
   evidence：用于文本生成的扩散语言模型
8. [Distilling Safe LLM Systems via Soft Prompts for On Device Settings](/202606/14/2606.09388v1-distilling-safe-llm-systems-via-soft-prompts-for-on-device-settings)  
   标签：评分：7.0/10、query:compression
   evidence：知识蒸馏用于大语言模型压缩
9. [A Theory on Flow Matching with Neural Networks](/202606/14/2606.10089v1-a-theory-on-flow-matching-with-neural-networks)  
   标签：评分：7.0/10、query:mg
   evidence：流匹配神经网络的理论基础
10. [Few-step Generative Models as Lossy Compression](/202606/14/2606.10450v1-few-step-generative-models-as-lossy-compression)  
   标签：评分：7.0/10、query:mg
   evidence：少步生成模型作为有损压缩编解码器
11. [Decoupling Semantics and Logic: A Training-Free Coarse-to-Fine Pipeline for Video Retrieval-Augmented Generation](/202606/14/2606.07924v1-decoupling-semantics-and-logic-a-training-free-coarse-to-fine-pipeline-for-video-retrieval-augmented-generation)  
   标签：评分：6.0/10、query:mg
   evidence：免训练视频RAG管道，多模态检索增强生成
12. [Evaluating the Representation Space of Diffusion Models via Self-Supervised Principles](/202606/14/2606.09718v1-evaluating-the-representation-space-of-diffusion-models-via-self-supervised-principles)  
   标签：评分：6.0/10、query:mg
   evidence：扩散模型表示空间的评估框架
13. [miniReranker: Efficient Multimodal Reranking through Visual Cache Reuse and Interaction Sparsity](/202606/14/2606.10759v1-minireranker-efficient-multimodal-reranking-through-visual-cache-reuse-and-interaction-sparsity)  
   标签：评分：6.0/10、query:eli
   evidence：利用视觉缓存重用和交互稀疏性提升多模态重排效率，类似KV缓存复用
14. [TileFuse: A Fused Mixed-Precision Kernel Library for Efficient Quantized LLM Inference on AMD NPUs](/202606/14/2606.11357v1-tilefuse-a-fused-mixed-precision-kernel-library-for-efficient-quantized-llm-inference-on-amd-npus)  
   标签：评分：6.0/10、query:llm-kernel
   evidence：面向NPU的融合混合精度内核库用于量化LLM推理


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
