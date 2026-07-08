# Transformer Exercises

This repository contains my educational implementations of Transformer architectures and related NLP components. The goal of this project is to understand how modern Transformer-based models work by implementing and experimenting with them rather than relying entirely on high-level APIs.

## Purpose

Instead of treating Transformer models as black boxes, this repository focuses on understanding the underlying concepts through implementation, debugging, and experimentation.

Topics covered include:

* Transformer architecture
* Multi-Head Self-Attention
* Cross Attention
* Positional Encoding
* Encoder-Decoder architecture
* Attention masks (causal & padding)
* Training loops
* Checkpointing
* Tokenization experiments
* Model optimization experiments

## Repository Structure

### `from-scratch`

A low-level implementation where core Transformer components are built manually to better understand the architecture.

### `with-pytorch`

An Encoder-Decoder Transformer implemented using PyTorch modules such as `nn.MultiheadAttention`, while keeping the overall architecture faithful to the original paper.

Experiments include:

* Xavier initialization
* Noam Learning Rate Scheduler
* Gradient Clipping
* Different optimization settings
* Checkpoint system
* WikiText-2 training

### Future Projects

This repository will continue to grow with additional Transformer-related implementations, including:

* Byte Pair Encoding (BPE)
* Subword Tokenization
* Decoder-only GPT
* Beam Search
* Sampling strategies
* Vision Transformer (ViT)
* Additional NLP experiments

## Philosophy

The purpose of this repository is learning and experimentation—not building production-ready models. Every implementation is written to understand *why* each component exists and *how* it affects training.

## Technologies

* Python
* PyTorch
* Kaggle Notebooks
* Google Colab
* WikiText-2 Dataset

## References

* *Attention Is All You Need* (2017)
* Andrej Karpathy – Neural Networks: Zero to Hero
* PyTorch Documentation

---

This repository documents my journey of learning Transformer architectures from the ground up through implementation, experimentation, and continuous improvement.
