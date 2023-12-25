# 并行计算与加速
## 基础知识

* CUDA并行计算教程：Intro to Parallel Programming
* https://www.youtube.com/watch?v=F620ommtjqk&list=PLAwxTw4SYaPnFKojVQrmyOGFCqHTxfdv2

* B站教程：https://www.bilibili.com/video/BV1kx411m7Fk

* 一些CUDA的书：
* cuda by example
* Professional Cuda C programming

* 英伟达GPU通信库：https://github.com/NVIDIA/nccl

* cutlass快速矩阵乘法库：https://github.com/NVIDIA/cutlass

* CUBLAS矩阵乘法计算库：https://developer.nvidia.com/cublas


### 并行计算框架论文

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

一些其他的应用：https://github.com/NVIDIA/FasterTransformer









