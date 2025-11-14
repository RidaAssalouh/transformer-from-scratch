# Transformer Text Classifier (IMDB Sentiment)

This project implements a **Transformer-based text classifier** in PyTorch, trained on the IMDB movie reviews dataset.  

---

## Features

- **Transformer implemented from scratch** with multi-head self-attention and feed-forward blocks, inspired by [Vaswani et al., 2017](https://arxiv.org/abs/1706.03762).
- Optional use of **pretrained BERT embeddings** as an initilization of the embeddings for improved performance.
- Training and evaluation pipeline on the IMDB dataset (`datasets` library).
- Metrics include **Accuracy**, **F1 score**, and **Confusion Matrix**.
- Supports GPU training if available.

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/RidaAssalouh/transformer-from-scratch.git
cd transformer-from-scratch
