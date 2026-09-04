# Medical-VQA-Assistant

# ⚕️ Medical VQA Assistant (Gemma-4 Vision)

An end-to-end multimodal AI fine-tuned on the VQA-RAD dataset for medical image analysis. 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Himanshu-tewatia0/Medical-VQA-Assistant/blob/main/gemma_4.ipynb)
*(Click to run the complete Gradio UI on a Free Google T4 GPU)*

## 🎥 Live Video Demo
Watch the AI bypass safety filters and analyze the X-Ray in real-time:
[Click here to watch the Video Demo](https://github.com/Himanshu-tewatia0/Medical-VQA-Assistant/raw/main/Medical_VQA_Demo.mp4)

## 🧠 Technical Highlights
* **Base Model:** Gemma-4 (4.5B Parameters)
* **Dataset:** VQA-RAD (Medical Visual Question Answering)
* **Fine-Tuning:** QLoRA (Quantized Low-Rank Adaptation)
* **Overcoming Alignment Tax:** Successfully bypassed the base model's strict RLHF safety filters (which typically refuse clinical diagnostics) using Forced Prefix Injection and Greedy Decoding.

## 🚀 Model Weights
The quantized LoRA adapters are open-sourced and hosted on Hugging Face:
👉 [gemma-4-medical-lora](https://huggingface.co/himanshutewatia771/gemma-4-medical-lora)

---
**Disclaimer:** *This is a research prototype designed to demonstrate agentic workflows and multimodal fine-tuning. Not intended for actual clinical diagnosis.*
