---
layout: default
title: 模型结构
nav_order: 1
parent: 论文笔记
has_children: true
permalink: /docs/model-architecture/
---

# 🏗️ 模型结构

Transformer 架构设计与核心组件的研究论文解析。

包括：注意力机制、位置编码、MoE（混合专家）、上下文长度扩展、模型架构创新等。

---

## 已解析论文

### [位置编码演进史](positional-encoding/)
从绝对位置编码到 RoPE、ALiBi、CoPE 的五代演进，以及 DeepSeek MLA 的解耦 RoPE 创新。

### [mHC - 流形约束超连接](mHC/)
通过扩展隐藏状态空间，将静态残差连接转变为可学习的矩阵运算，彻底解决 Pre/Post-Norm 的"跷跷板效应"，支持动态层重排与流形约束的稳定性保障。

---

## 相关关键词

`Attention` `RoPE` `ALiBi` `CoPE` `MoE` `MLA` `GQA` `Context Extension` `Hyper-Connections` `Residual`
