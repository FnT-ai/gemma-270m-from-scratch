# Building a 270M-Parameter Gemma-Style Language Model from Scratch

A complete PyTorch implementation of a 270M-parameter decoder-only transformer inspired by the Gemma architecture. This project demonstrates the complete workflow for developing a small language model, including data preprocessing, tokenizer preparation, transformer implementation, training, evaluation, and inference.

---

## Project Overview

This repository documents the implementation of a Gemma-style decoder-only language model developed from scratch using PyTorch. The project explores the complete lifecycle of training a modern transformer-based language model while maintaining modular, reproducible, and scalable code.

---

## Features

- Decoder-only Transformer Architecture
- Rotary Positional Embeddings (RoPE)
- RMSNorm
- Multi-Head Self Attention
- Feed Forward Network (MLP)
- Byte Pair Encoding (BPE) Tokenizer
- Mixed Precision Training
- Gradient Accumulation
- Checkpoint Saving
- Model Evaluation
- Text Generation

---

## Project Structure

```
gemma-270m-from-scratch/
│
├── notebooks/
├── src/
├── configs/
├── docs/
├── checkpoints/
├── assets/
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Technology Stack

- Python
- PyTorch
- Hugging Face Tokenizers
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Training Pipeline

1. Dataset Preparation
2. Tokenizer Training
3. Data Encoding
4. Transformer Construction
5. Forward Propagation
6. Loss Computation
7. Backpropagation
8. Optimization
9. Checkpoint Saving
10. Evaluation
11. Text Generation

---

## Future Improvements

- Flash Attention
- Distributed Training
- LoRA Fine-tuning
- Quantization
- Model Parallelism
- Larger Context Windows

---

## License

MIT License
