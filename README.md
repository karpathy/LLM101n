# LLM101n: Let's build a Storyteller

![LLM101n header image](llm101n.jpg)

>  What I cannot create, I do not understand. -Richard Feynman

In this course we will build a Storyteller AI Large Language Model (LLM). Hand in hand, you'll be able create, refine and illustrate little [stories](https://huggingface.co/datasets/roneneldan/TinyStories) with the AI. We are going to build everything end-to-end from basics to a functioning web app similar to ChatGPT, from scratch in Python, C and CUDA, and with minimal computer science prerequisits. By the end you should have a relatively deep understanding of AI, LLMs, and deep learning more generally.

**Syllabus**

- [Chapter 01](bigram/README.md) **Bigram Language Model** (language modeling)
- [Chapter 02](micrograd/README.md) **Micrograd** (machine learning, backpropagation)
- [Chapter 03](mlp/README.md) **N-gram model** (multi-layer perceptron, matmul, gelu)
- [Chapter 04](attention/README.md) **Attention** (attention, softmax, positional encoder)
- [Chapter 05](transformer/README.md) **Transformer** (transformer, residual, layernorm, GPT-2)
- [Chapter 06](tokenization/README.md) **Tokenization** (minBPE, byte pair encoding)
- [Chapter 07](optimization/README.md) **Optimization** (initialization, optimization, AdamW)
- [Chapter 08](device/README.md) **Need for Speed I: Device** (device, CPU, GPU, ...)
- [Chapter 09](precision/README.md) **Need for Speed II: Precision** (mixed precision training, fp16, bf16, fp8, ...)
- [Chapter 10](distributed/README.md) **Need for Speed III: Distributed** (distributed optimization, DDP, ZeRO)
- [Chapter 11](datasets/README.md) **Datasets** (datasets, data loading, synthetic data generation)
- [Chapter 12](inference/README.md) **Inference I: kv-cache** (kv-cache)
- [Chapter 13](quantization/README.md) **Inference II: Quantization** (quantization)
- [Chapter 14](sft/README.md) **Finetuning I: SFT** (supervised finetuning SFT, PEFT, LoRA, chat)
- [Chapter 15](rl/README.md) **Finetuning II: RL** (reinforcement learning, RLHF, PPO, DPO)
- [Chapter 16](deployment/README.md) **Deployment** (API, web app)
- [Chapter 17](multimodal/README.md) **Multimodal** (VQVAE, diffusion transformer)

**Appendix**

Further topics to work into the progression above:

- Programming languages: Assembly, C, Python
- Data types: Integer, Float, String (ASCII, Unicode, UTF-8)
- Tensor: shapes, views, strides, contiguous, ...
- Deep Learning frameowrks: PyTorch, JAX
- Neural Net Architecture: GPT (1,2,3,4), Llama (RoPE, RMSNorm, GQA), MoE, ...
- Multimodal: Images, Audio, Video, VQVAE, VQGAN, diffusion

---

**Update June 25.** To clarify, the course will take some time to build. There is no specific timeline. Thank you for your interest but please do not submit Issues/PRs.
