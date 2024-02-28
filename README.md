# 并行计算与加速

## CUDA 学习路线

https://www.youtube.com/watch?v=F620ommtjqk&list=PLAwxTw4SYaPnFKojVQrmyOGFCqHTxfdv2
cuda by example
Professional Cuda C programming
GPU编程与优化——大众高性能计算

## 基础知识

一个很好的大语言模型技术的学习网站

https://github.com/liguodongiot/llm-action

CUDA并行计算教程：Intro to Parallel Programming

https://www.youtube.com/watch?v=F620ommtjqk&list=PLAwxTw4SYaPnFKojVQrmyOGFCqHTxfdv2

B站教程：https://www.bilibili.com/video/BV1kx411m7Fk

CUDA官方教程：https://docs.nvidia.com/cuda/cuda-c-programming-guide

一些CUDA的书：

cuda by example

Professional Cuda C programming

英伟达GPU通信库：https://github.com/NVIDIA/nccl

cutlass快速矩阵乘法库：https://github.com/NVIDIA/cutlass

CUBLAS矩阵乘法计算库：https://developer.nvidia.com/cublas


### 分布式计算框架论文

分布式系统通信库

https://docs.nvidia.com/deeplearning/nccl

参数服务器（Parameter Server）逐段精读【论文精读】

https://www.bilibili.com/video/BV1YA4y197G8


Megatron LM 论文精读【论文精读】

https://www.bilibili.com/video/BV1nB4y1R7Yz

GPipe 论文精读

https://www.bilibili.com/video/BV1v34y1E7zu

Pathways 论文精读

https://www.bilibili.com/video/BV1xB4y1m7Xi

### Transformer推理加速论文

vllm:

https://github.com/vllm-project/vllm

FasterTransformer：

https://github.com/NVIDIA/FasterTransformer

flashattention:

FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness
https://arxiv.org/abs/2205.14135


### Transformer加速算法

Transformer加速包括量化，剪枝，模型蒸馏

投机推理方向的一些论文：

Speculative Decoding：Google ICML'23

Speculative Sampling：DeepMind arXiv preprint arXiv:2302.01318 2023

SpecInfer：CMU arXiv preprint arXiv:2305.09781 2023

Medusa：Princeton

LLM Accelerator：Microsoft arXiv preprint arXiv:2304.04487 2023

REST: Retrieval-Based Speculative Decoding：Peking, Princeton arXiv preprin arXiv:2311.08252 2023

Prompt lookup decoding (PLD)：https://github.com/apoorvumang/prompt-lookup-decoding

Lookahead Decoding：https://lmsys.org/blog/2023-11-21-lookahead-decoding/

一些其他的应用：

未来能投稿的会议：
计算机体系结构与系统领域顶级学术会议截止时间汇总

https://zhuanlan.zhihu.com/p/451866435






