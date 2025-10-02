#  NeuroCare-AI – AI-Powered Healthcare Platform

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12zhwthPZM0jmD6Jj6BEPzy6ZmY2Nm1Ii?usp=sharing)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)  

>  *“Revolutionizing healthcare with intelligence beyond the human eye.”*  

---

##  Overview
**NeuroCare-AI** is an **intelligent healthcare platform** that leverages **state-of-the-art AI** to provide **real-time medical insights**.  
This project integrates multiple AI-powered healthcare modules including **medical image analysis, report summarization, AI pharmacist, and personalized treatment planning** – all accessible in one platform.  

---

##  Features
-  **Brain Tumor Detection** → YOLOv8 model detects tumors in MRI scans with confidence scores.  
-  **Medical Report Analyzer** → Upload & chat with PDF reports using **RAG (Retrieval-Augmented Generation)**.  
-  **MediGuide AI Pharmacist** → Detect medicines via image recognition and provide dosage/side-effect details.  
-  **Health Assistant Chatbot** → 24/7 conversational AI for medical guidance and wellness queries.  
-  **Personalized Treatment Plans** → LLM-powered system generates patient-specific recommendations.  

---

## 🔗 Colab Demo
Click below to run the project in Google Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12zhwthPZM0jmD6Jj6BEPzy6ZmY2Nm1Ii?usp=sharing)  

---

## Tech Stack
- **Computer Vision**: YOLOv8 (Ultralytics), OpenCV  
- **NLP & RAG**: LangChain, Hugging Face Transformers, ChromaDB  
- **Frameworks**: PyTorch, TensorFlow, Streamlit  
- **Deployment**: Google Colab, GitHub  

---

## 📂 Repository Structure
NeuroCare-AI
┣ 📜 README.md
┣ 📜 requirements.txt
┣ 📜 brain_tumor.yaml
┣ 📂 data
┃ ┣ 📂 train
┃ ┣ 📂 valid
┃ ┗ 📂 test
┣ 📂 notebooks
┃ ┗ neurocare_ai_demo.ipynb
┣ 📂 models
┃ ┗ yolov8_brain_tumor.pt
┗ 📂 utils
┗ helper_functions.py

## Usage
Upload MRI dataset (train/valid/test).
Train YOLOv8 model on brain tumor detection.
Use RAG to analyze medical reports.
Interact with chatbot for medical queries.
Generate personalized treatment plans.

📜 License
This project is licensed under the MIT License – free to use and modify.
