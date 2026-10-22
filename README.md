# vlm-lab

A hands-on repository for Vision Language Model (VLM) pretraining, fine-tuning, evaluation, and multimodal application experiments.

---

## 📌 Overview

`vlm-lab` is a structured workspace for building, fine-tuning, and benchmarking Vision Language Models. It covers everything from building small VLMs from scratch to fine-tuning modern open weights (SmolVLM, Qwen2-VL, SigLIP) on free-tier compute environments like Google Colab and Kaggle.

---

## 🗂 Project Structure

- **01_pretraining:** Small VLM training from scratch (NanoVLM / SmolVLM) & loss tracking
- **02_finetuning:** SFT, PEFT/QLoRA, and preference alignment (DPO/MPO)
- **03_benchmarking:** Latency, TTFT, and throughput metrics
- **04_applications:** Document AI, Video-RAG pipelines, and agentic workflows

---

## 🚀 Quickstart

### Environment Setup

1. Clone your repository from GitHub and navigate into the project directory:
   `gh repo clone vlm-lab`
2. Install dependencies:
   `pip install torch torchvision transformers datasets accelerate bitsandbytes matplotlib pandas`

---

## 📊 Pretraining Progress (Chapter 3 - Small VLM)

Includes custom pretraining metrics and loss visualization for NanoVLM training over 5,000 steps:

![Training Loss](01_pretraining/vlm_training_loss.png)

---

## 📄 License & References

- Exercises and experiments inspired by Hugging Face VLM research and open-source models (`SmolVLM`, `Qwen-VL`, `SigLIP`).
- Released under the MIT License.
