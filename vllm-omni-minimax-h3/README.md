# vLLM-Omni × MiniMax-H3

MiniMax-H3 在 vLLM-Omni 上的适配与后续演进学习笔记。

入口：

- 基线接入：[vllm-omni#5691](https://github.com/vllm-project/vllm-omni/pull/5691)
- Follow-up 看板：[vllm-omni#5700](https://github.com/vllm-project/vllm-omni/issues/5700)
- 官方仓库：[MiniMax-AI/MiniMax-H3](https://github.com/MiniMax-AI/MiniMax-H3/tree/main)、[中文 README](https://github.com/MiniMax-AI/MiniMax-H3/blob/main/README.zh-CN.md)
- Recipe：[recipes/MiniMaxAI/MiniMax-H3.md](https://github.com/vllm-project/vllm-omni/blob/main/recipes/MiniMaxAI/MiniMax-H3.md)、[vLLM Recipes 页面](https://recipes.vllm.ai/MiniMaxAI/MiniMax-H3)
- 源码：[vllm_omni/diffusion/models/minimax_h3/](https://github.com/vllm-project/vllm-omni/tree/main/vllm_omni/diffusion/models/minimax_h3)
- B 站讲解：[BV1xmuT6dE1M](https://www.bilibili.com/video/BV1xmuT6dE1M)

## 中文阅读


1. [中文 README](https://github.com/MiniMax-AI/MiniMax-H3/blob/main/README.zh-CN.md)：系统拆成 Context-IR / H3-Base / Regenerate-2K，以及 FL2VA、Ref2VA、Omni Transformer、VAE。
2. [技术博客：打破任务和模态的边界](https://www.minimaxi.com/blog/minimax-h3)：为什么不做专家模型、Contextual Omni Representation、In-context Regeneration。
3. [开源公告](https://www.minimaxi.com/news/minimax-h3-open-source)：开了什么、没开什么，权重在 Hugging Face / ModelScope。
4. [量子位：手绘即特效](https://www.qbitai.com/2026/07/464277.html)：产品能力向介绍，例子多，适合建立直觉。
5. [DataLearner：架构、权重与价格](https://www.datalearner.com/ai-models/pretrained-models/minimax-h3)：33B、AdaLN 约 13B、规格和部署信息的结构化摘要。

