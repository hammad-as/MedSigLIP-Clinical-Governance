---
title: MedSigLIP
emoji: 🏥
colorFrom: blue
colorTo: indigo
sdk: gradio
sdk_version: "4.44.0"
app_file: app.py
python_version: "3.10"
pinned: false
---

# MedSigLIP: Clinical Diagnostic & Governance Hub

A zero-shot, multi-modal clinical diagnostic dashboard for dermatological triage.

---

### Live Demo
[Access the MedSigLIP Dashboard](https://huggingface.co/spaces/hammad301/MedSigLIP)

### Overview
This project bridges the gap between cutting-edge Vision-Language models and practical clinical auditability. Unlike standard classifiers, MedSigLIP evaluates skin lesions using semantic alignment, providing real-time diagnostic probabilities alongside an **AI Governance & Stability Index** to monitor for model drift.



### System Architecture
* **Inference Engine:** Vision-Language Alignment (SigLIP) for zero-shot semantic classification.
* **Governance Layer:** Real-time monitoring of embedding stability indices to detect potential model degradation.
* **Explainability:** Integrated clinical-grade dashboard interface designed for triage support.



### Tech Stack
* **Framework:** Python, Gradio
* **Core Logic:** Hugging Face `transformers` (Zero-Shot Image Classification)
* **Governance:** Custom embedding alignment monitoring
* **Deployment:** Hugging Face Spaces

### Disclaimer
This project is for educational and research purposes only. Clinical diagnostics should always be performed by qualified professionals.
