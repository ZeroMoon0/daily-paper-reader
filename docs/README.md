<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-22
- 运行时间：2026-06-22 23:11:47 UTC
- 运行状态：成功
- 本次总论文数：25
- 精读区：11
- 速读区：14

### 今日简报（AI）
今日聚焦稀疏注意力KV缓存系统与扩散Transformer专家分解两大创新，涵盖11篇精读与14篇速读论文。  
最值得关注的是SAC提出的基于CXL的稀疏注意力KV缓存分离架构（10分）及MoECa在扩散Transformer中的特征复用对齐与专家分解方法（9分）。  
建议优先精读这两篇高分论文，并关注速读中长上下文建模（GSS-Transformer）和潜在推理（Latent Thought Flow）等方向。
- 详情：[/202606/22/README](/202606/22/README)

### 精读区论文标签
1. [SAC: Disaggregated KV Cache System for Sparse Attention LLMs with CXL](/202606/22/2606.19746v1-sac-disaggregated-kv-cache-system-for-sparse-attention-llms-with-cxl)  
   标签：评分：10.0/10、query:eli
   evidence：面向稀疏注意力大模型的KV缓存解聚系统
2. [MoECa: Aligning Feature Reuse with Expert Decomposition in Diffusion Transformers](/202606/22/2606.15615v1-moeca-aligning-feature-reuse-with-expert-decomposition-in-diffusion-transformers)  
   标签：评分：9.0/10、query:mg
   evidence：面向扩散Transformer的专家分支级特征复用缓存
3. [ReQAT: Achieving Full-Precision Reasoning Accuracy with 4-bit Floating-Point Quantization-Aware Training](/202606/22/2606.15682v1-reqat-achieving-full-precision-reasoning-accuracy-with-4-bit-floating-point-quantization-aware-training)  
   标签：评分：9.0/10、query:compression
   evidence：面向推理模型的4位浮点量化感知训练
4. [Redirecting the Flow: Image Customization through Attention Distribution Shift](/202606/22/2606.16866v1-redirecting-the-flow-image-customization-through-attention-distribution-shift)  
   标签：评分：9.0/10、query:mg
   evidence：通过注意力分布偏移实现主题驱动的图像定制
5. [LESS Is More: Mutual-Stability Sampling for Diffusion Language Models](/202606/22/2606.16908v1-less-is-more-mutual-stability-sampling-for-diffusion-language-models)  
   标签：评分：9.0/10、query:eli
   evidence：扩散语言模型自适应采样减少推理步骤
6. [One-Step Token-to-Waveform Generation with MeanFlow in Latent Space](/202606/22/2606.18072v1-one-step-token-to-waveform-generation-with-meanflow-in-latent-space)  
   标签：评分：9.0/10、query:mg
   evidence：使用MeanFlow实现一步生成的流匹配方法
7. [Complementary Attention Head Pruning for Efficient Transformers](/202606/22/2606.19150v1-complementary-attention-head-pruning-for-efficient-transformers)  
   标签：评分：9.0/10、query:compression
   evidence：互补注意力头剪枝实现高效Transformer
8. [SafeSpec: Fast and Safe LLM via Dynamic Reflective Sampling](/202606/22/2606.19755v1-safespec-fast-and-safe-llm-via-dynamic-reflective-sampling)  
   标签：评分：9.0/10、query:eli
   evidence：投机解码加速LLM
9. [WeGenBench: A Multidimensional Diagnostic Benchmark towards Text-to-Image Model Optimization](/202606/22/2606.20100v1-wegenbench-a-multidimensional-diagnostic-benchmark-towards-text-to-image-model-optimization)  
   标签：评分：9.0/10、query:mg
   evidence：文本到图像生成基准
10. [UltraQuant: 4-bit KV Caching for Context-Heavy Agents](/202606/22/2606.20474v1-ultraquant-4-bit-kv-caching-for-context-heavy-agents)  
   标签：评分：9.0/10、query:eli
   evidence：针对上下文密集型智能体的4位KV缓存压缩
11. [SSD: Spatially Speculative Decoding Accelerates Autoregressive Image Generation](/202606/22/2606.20543v1-ssd-spatially-speculative-decoding-accelerates-autoregressive-image-generation)  
   标签：评分：9.0/10、query:eli
   evidence：空间投机解码加速自回归图像生成

### 速读区论文标签
1. [Long-Context Modeling via GSS-Transformer Hybrid Architecture with Learnable Mixing](/202606/22/2606.16093v1-long-context-modeling-via-gss-transformer-hybrid-architecture-with-learnable-mixing)  
   标签：评分：8.0/10、query:eli
   evidence：GSS与GQA混合架构实现高效长上下文建模
2. [Latent Thought Flow: Efficient Latent Reasoning in Large Language Models](/202606/22/2606.16222v1-latent-thought-flow-efficient-latent-reasoning-in-large-language-models)  
   标签：评分：8.0/10、query:eli
   evidence：潜在推理通过避免每个想法的令牌解码来降低推理开销
3. [From Tokens to Regions: CUDA-Sensitive Instruction Tuning for GPU Kernel Generation](/202606/22/2606.16231v1-from-tokens-to-regions-cuda-sensitive-instruction-tuning-for-gpu-kernel-generation)  
   标签：评分：8.0/10、query:llm-kernel
   evidence：面向CUDA内核生成的指令微调
4. [PermaVid: Consistent Video Generation Across Edits via Disentangled Context Memory](/202606/22/2606.16449v2-permavid-consistent-video-generation-across-edits-via-disentangled-context-memory)  
   标签：评分：8.0/10、query:mg
   evidence：一致视频生成
5. [Perron--Frobenius Operator Matching for Generative Modeling](/202606/22/2606.17465v1-perron--frobenius-operator-matching-for-generative-modeling)  
   标签：评分：8.0/10、query:mg
   evidence：流匹配生成框架
6. [Fearless Concurrency on the GPU](/202606/22/2606.15991v1-fearless-concurrency-on-the-gpu)  
   标签：评分：7.0/10、query:llm-kernel
   evidence：基于Rust的安全GPU内核编写框架，用于高性能计算
7. [PermaVid: Consistent Video Generation Across Edits via Disentangled Context Memory](/202606/22/2606.16449v1-permavid-consistent-video-generation-across-edits-via-disentangled-context-memory)  
   标签：评分：7.0/10、query:mg
   evidence：基于解耦上下文记忆的一致视频生成
8. [Prefill/Decode-Aware Evaluation of LLM Inference on Emerging AI Accelerators](/202606/22/2606.17104v1-prefilldecode-aware-evaluation-of-llm-inference-on-emerging-ai-accelerators)  
   标签：评分：7.0/10、query:eli
   evidence：面向新兴AI加速器的LLM推理阶段感知评估
9. [Volterra Generative Models](/202606/22/2606.18071v1-volterra-generative-models)  
   标签：评分：7.0/10、query:mg
   evidence：路径依赖噪声扩散框架
10. [Pulse: Training Acceleration for Large Diffusion Models with Automatic Pipeline Parallelism](/202606/22/2606.19163v1-pulse-training-acceleration-for-large-diffusion-models-with-automatic-pipeline-parallelism)  
   标签：评分：7.0/10、query:mg
   evidence：Pulse使用自动流水线并行加速大规模扩散模型训练
11. [Wasserstein Convergence of ODE-Based Samplers in Decentralized Diffusion Model via Velocity Field Decomposition](/202606/22/2606.15835v1-wasserstein-convergence-of-ode-based-samplers-in-decentralized-diffusion-model-via-velocity-field-decomposition)  
   标签：评分：6.0/10、query:mg
   evidence：扩散模型收敛理论
12. [Shift-and-Sum Quantization for Visual Autoregressive Models](/202606/22/2606.16131v1-shift-and-sum-quantization-for-visual-autoregressive-models)  
   标签：评分：6.0/10、query:compression
   evidence：后训练量化
13. [Decoupling Inference from State Updates in Low-Latency Feature Engines via Probabilistic Thinning](/202606/22/2606.16981v1-decoupling-inference-from-state-updates-in-low-latency-feature-engines-via-probabilistic-thinning)  
   标签：评分：6.0/10、query:eli
   evidence：通过概率稀疏化实现低延迟推理解耦
14. [CIAN: Multi-Stage Framework for Event-Enriched Image Captioning via Retrieval-Augmented Generation](/202606/22/2606.17430v1-cian-multi-stage-framework-for-event-enriched-image-captioning-via-retrieval-augmented-generation)  
   标签：评分：6.0/10、query:mg
   evidence：通过检索增强生成实现事件增强图像描述的多阶段框架


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
