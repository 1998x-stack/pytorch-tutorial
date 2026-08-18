# 🔥 PyTorch 深度学习实战教程

> 📘 28章 实战体系 · 交互式 HTML 课程

> **English TL;DR:** An all-Chinese 28-chapter hands-on **PyTorch** course — from framework intro and tensor basics (creation, dtype, device, broadcasting, autograd/computation graph) through your first NN (nn.Module, losses, optimizers, full training loop), data pipelines (Dataset/DataLoader, augmentation), then CNN/RNN/attention, saving-loading & checkpoints, tuning & evaluation (confusion matrix, TensorBoard), transfer learning, and mixed precision (FP16/BF16, torch.amp). Advanced: debugging pitfalls (NaN/Inf, gradient checks), performance (torch.compile/Dynamo/Inductor, cudnn.benchmark), reproducibility & experiment management, custom layers/ops/CUDA, distributed training (DDP, FSDP/ZERO), deployment/export (torch.export, ONNX, TorchServe), profiling (torch.profiler), the ecosystem (torchvision/audio/text, Lightning, HF), frontiers (torch.accelerator, FlashAttention-4, MX), ending with two hands-ons (image classification; knowledge-graph recap & learning path).

## 📖 课程简介

本课程是一条**从入门到实战的 PyTorch 主线**：先掌握张量、自动求导与第一个神经网络，走通完整训练流程与数据管线；随后深入 CNN/RNN/注意力、模型保存与迁移学习、混合精度与性能优化（torch.compile）。工程侧覆盖训练陷阱调试、可复现性与实验管理、自定义算子、分布式训练（DDP/FSDP）与模型部署导出，最后浏览 PyTorch 生态与前沿，并以图像分类实战与课程知识图谱收尾。

## 🚀 快速开始

```bash
open index.html   # macOS，纯静态即开即看
```

## 📂 项目结构

```text
pytorch-tutorial/
├── index.html / 01.html ~ 28.html / courses.json / theme.css
```

## 📖 章节分段

| 阶段 | 章节 | 核心 |
|------|------|------|
| **入门基础** | 01–04 | 框架、张量、运算/广播、自动求导 |
| **首个网络** | 05–08 | 模块/损失/优化、训练流程、数据加载 |
| **深度学习组件** | 09–11 | CNN/RNN/注意力、保存加载 |
| **训练与调优** | 12–16 | 调参、评估可视化、迁移、混合精度、调试 |
| **性能与分布式** | 17–22 | 性能优化、可复现、compile、自定义算子、DDP、FSDP |
| **部署与生态** | 23–28 | 导出部署、profiling、PyTorch 生态、前沿、实战项目 |

## ✨ 亮点

- 覆盖张量到 FSDP/部署再到 torch.compile 前沿的全链路
- 训练/可复现/性能/分布式一应俱全
- 含图像分类实战项目与系统学习路线

## 🎯 前置知识

- 适合：深度学习开发者 / 想系统掌握 PyTorch 的工程师
- 建议具备：Python 基础 + 基础深度学习概念

## ✨ 特色

- 以实战为主线、以理解底层为进阶
- 即开即用纯静态 HTML

---
*本课程由 `pytorch-tutorial/` 项目维护。*