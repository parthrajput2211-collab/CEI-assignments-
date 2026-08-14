# MiniGPT — GPT-Style Language Model From Scratch

## Overview

This project implements a small GPT-style decoder-only Transformer
from scratch using PyTorch.

The objective is to understand the fundamental components of a
GPT-style language model by implementing the major components
manually and training the model on a text corpus.

## Key Concepts

- Character-Level Tokenization
- Token and Positional Embeddings
- Query, Key and Value
- Causal Self-Attention
- Multi-Head Attention
- Feed-Forward Networks
- Residual Connections
- Layer Normalization
- Transformer Blocks
- Cross-Entropy Loss
- AdamW Optimizer
- Autoregressive Text Generation

## Model Training

The model was trained from scratch using PyTorch.

### Results

| Metric | Initial | Final |
|---|---:|---:|
| Training Loss | 4.309 | 2.055 |
| Validation Loss | 4.315 | 2.093 |

The reduction in both training and validation loss demonstrates that
the model successfully learned statistical patterns from the
training corpus.

## Baseline Comparison

A simple Bigram language model was implemented as a baseline.

The Bigram model produced mostly random-looking character sequences,
while MiniGPT produced more structured text by using contextual
information through causal self-attention.

## Project Contents

- `MiniGPT_Parth_Rohilla.ipynb` — Complete project implementation
- `minigpt_config.json` — Model architecture and training configuration

## Technologies

- Python
- PyTorch
- Jupyter Notebook
- Deep Learning
- Natural Language Processing
- Transformer Architecture

## Internship

Developed as the final project for the Celebal Technologies
Data Science Internship.
