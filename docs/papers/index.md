---
layout: default
title: 论文解析
nav_order: 1
has_children: true
permalink: /docs/papers/
---

# 📖 论文解析

大语言模型前沿论文的通俗解析与技术笔记。

每篇解析包含：核心问题、技术方案、通俗类比、实验结果和局限性分析。

---

## 已解析论文

### [DSpark - 置信度调度推测解码](dspark/)
DeepSeek 联合北大提出的推理加速框架，通过半自回归生成 + 置信度调度验证，在真实高并发服务中实现 60%-85% 提速。

### [位置编码演进史](positional-encoding/)
从绝对位置编码到 RoPE、ALiBi、CoPE 的五代演进，以及 DeepSeek MLA 的解耦 RoPE 创新。
