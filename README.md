# Hybrid Data Poisoning Detection using Modified RAG for Secure Cloud

This repository provides a framework for **detecting**, **analyzing**, and **mitigating data poisoning attacks** attacks in machine learning systems. It uses a hybrid approach combining a Modified Retrieval-Augmented Generation (RAG) model with explainable AI techniques and traditional defense strategies to secure cloud-based ML pipelines.

---

## Overview

Machine learning models are vulnerable to **data poisoning attacks** where adversaries insert harmful data during training to degrade or manipulate the model's behavior. This project addresses the issue through:

- Detection of various poisoning strategies including backdoor, watermark, and patch-based attacks
- Analytical tools powered by explainable AI to identify the impact of poisoned inputs
- A hybrid prevention mechanism using modified RAG and additional filtering defenses

---

## Features

- Support for multiple poisoning recipes:
  - Gradient Matching
  - MetaPoison (v1 to v3)
  - Watermark Injection
  - Patch Attacks
  - Bullseye Poisoning
  - Convex Polytope  Attacks
- Defense configurations integrated with victim models
- Visual plotting and evaluation tools
- Modular design for easy extension with new recipes or datasets

---

## Evaluation
Metrics: Accuracy, Precision, Recall, F1-Score
Detection of latent space anomalies
Comparison across clean, poisoned, and defended models
Visualizations: clustering, confidence plots, XAI interpretability

---
## Explainability Tools
Integrated with popular interpretability frameworks:
-SHAP
-LIME
-Attention Maps (via RAG)

Used to identify which parts of input trigger suspicion in the model.

---
## Use Cases
Securing enterprise RAG applications using LLMs
Defending cloud-based ML models from stealthy poisoning
Testing robustness of models against advanced poisoning attacks

---
## License
MIT License © 2025 Manas Patil
