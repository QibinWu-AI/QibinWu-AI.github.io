---
layout: home
title: LLM Paper Notes
nav_order: 1
description: 大语言模型论文解析与技术笔记
---

# 📚 LLM Paper Notes

大语言模型（LLM）前沿论文的通俗解析与技术笔记。

## 📂 五大栏目

| 栏目 | 内容 | 已解析 |
|------|------|--------|
| 🏗️ [模型结构](docs/model-architecture/) | 注意力机制、位置编码、MoE、架构创新 | 2 篇 |
| 🔥 [预训练](docs/pretraining/) | 预训练策略、数据工程、Scaling Laws | — |
| 🎯 [后训练](docs/post-training/) | RLHF、DPO、GRPO、对齐技术 | — |
| 🌐 [多模态](docs/multimodal/) | VLM、视觉编码器、图文对齐 | — |
| ⚡ [推理加速](docs/inference/) | 推测解码、量化、KV 缓存、服务优化 | 1 篇 |

## 📖 最新解析

- **[mHC: 流形约束超连接](docs/model-architecture/mHC/)** — 可学习的残差连接，解决 Pre/Post-Norm 跷跷板效应，支持动态层重排
- **[DSpark: 置信度调度推测解码](docs/inference/dspark/)** — DeepSeek 推理加速框架，半自回归生成 + 置信度调度验证，线上提速 60%-85%
- **[位置编码演进史](docs/model-architecture/positional-encoding/)** — 从绝对编码到 RoPE、ALiBi、CoPE 的五代演进

## 📌 关于

本站内容基于对前沿 LLM/VLM 论文的阅读与解析，力求用通俗易懂的方式讲解核心技术。

---

> 💡 每篇解析都包含：核心问题、技术方案、通俗类比、实验结果和局限性分析
