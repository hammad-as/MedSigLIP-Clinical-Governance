MedSigLIP: Clinical Diagnostic & Governance Hub
A zero-shot, multi-modal clinical diagnostic dashboard for dermatological triage.

Live Demo
View the live application on Hugging Face Spaces

Overview
This project bridges the gap between cutting-edge Vision-Language models and practical clinical auditability. Unlike standard classifiers, MedSigLIP evaluates skin lesions using semantic alignment, providing real-time diagnostic probabilities alongside an AI Governance/Stability Index to monitor for model drift.

System Architecture
Inference Engine: Vision-Language Alignment (SigLIP) for zero-shot semantic classification.

Governance Layer: Real-time monitoring of embedding stability indices.

Explainability: Integrated saliency-based insights for clinical verification.

Tech Stack
Framework: Python, Gradio

Core Logic: Hugging Face transformers

Deployment: Hugging Face Spaces

License
This project is for educational and research purposes only. Clinical diagnostics should always be performed by qualified professionals.
