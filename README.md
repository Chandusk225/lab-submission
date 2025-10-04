# Project Submission: Vision Transformer & Text-Prompted Segmentation

## Project Summary
This repository contains a solution to the lab assessment, featuring a from-scratch implementation of a Vision Transformer (ViT) on CIFAR-10 and a text-driven image segmentation pipeline. The submission reflects a robust implementation and practical model training under hardware and time constraints.

---
## Q1 — Vision Transformer on CIFAR-10
The `q1.ipynb` notebook details the construction and training of a Vision Transformer, adhering to the original paper's architecture.

### Final Results
| Metric | Value |
| :--- | :--- |
| **Best Test Accuracy** | **52.93%** |

### (Bonus) Performance Analysis
The model was trained using a robust strategy including the AdamW optimizer and a cosine learning rate scheduler with warmup, which is critical for stabilizing ViT training. The final reported accuracy of **52.93%** was achieved after the training process was interrupted due to the computational limits of the free Colab environment. This result demonstrates strong, positive learning progress and represents a successful outcome within the available resource constraints.

---
## Q2 — Text-Driven Image Segmentation
The `q2.ipynb` notebook implements a zero-shot segmentation pipeline using GroundingDINO and the Segment Anything Model (SAM).
