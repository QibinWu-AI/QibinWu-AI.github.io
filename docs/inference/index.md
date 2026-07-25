---
layout: default
title: 推理加速
nav_order: 5
parent: 论文笔记
has_children: true
permalink: /docs/inference/
---

# ⚡ 推理加速

大模型推理优化与部署技术的研究论文解析。

包括：推测解码、量化、KV 缓存优化、投机解码、蒸馏、服务系统优化等。

---

## 已解析论文

### [DSpark - 置信度调度推测解码](dspark/)
DeepSeek 联合北大提出的推理加速框架，通过半自回归生成 + 置信度调度验证，在真实高并发服务中实现 60%-85% 提速。

---

## 相关关键词

`Speculative Decoding` `Quantization` `KV Cache` `Distillation` `Serving` `GPTQ` `AWQ`
