<p align="center">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow">
  <img src="https://img.shields.io/badge/Colab-Compatible-yellow?logo=googlecolab">
  <img src="https://img.shields.io/badge/License-MIT-blue">
  <img src="https://img.shields.io/badge/Status-Reproduction%20Project-brightgreen">
</p>

# 🧠 Attention Is All You Need — Transformer Reproduction (v6)


**Author:** Koichi Kamachi, CPA  
**Repository:** [attention-transformer-reproduction](https://github.com/koichikamachi/attention-transformer-reproduction)  
**Date:** October 2025  
**Framework:** TensorFlow 2.x / Google Colab  

---

## 📘 Overview
This notebook reconstructs the Transformer architecture proposed in  
*“Attention Is All You Need” (Vaswani et al., 2017)*  
from scratch, using a step-by-step educational approach.

Each functional block (F0–F8) and training phase (T1–T5)  
is clearly separated to show how **embedding, positional encoding, attention, and inference**  
interact within the model.

---

## 🧩 Notebook Contents
- **F0:** Environment setup and safe restart cell  
- **F1–F3:** Tokenization and corpus preparation (SentencePiece)  
- **F4–F5:** Embedding and positional encoding  
- **F6–F8:** Self-attention, feed-forward, projection, and output layers  
- **T1–T5:** Training, optimizer, loss/accuracy functions, saving weights, and inference  

Each section corresponds directly to the original *Attention Is All You Need* paper structure.

---

## 🧠 Learning Objectives
- Understand the full data flow inside the Transformer model  
- Visualize Q/K/V matrices and self-attention weights  
- Experiment with bilingual datasets (Japanese–English)  
- Observe loss and accuracy evolution across epochs  

---

## ⚙️ Environment Setup
Run the notebook on **Google Colab**.

```bash
# Required libraries
!pip install tensorflow sentencepiece matplotlib
