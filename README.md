<p align="center">
  <img src="Header2.jpg" alt="Advanced Data Mining Coursework Banner" width="100%">
</p>

<div align="center">

# Advanced Data Mining Coursework
### Graduate Coursework, Statistical Analysis & Deep Learning Research Modules

[![University](https://img.shields.io/badge/University-SBU-0D9DF8?style=flat-square&logo=academia)](https://en.sbu.ac.ir/)
[![Term](https://img.shields.io/badge/Term-Spring%202026-34C6BF?style=flat-square)]()
[![Python](https://img.shields.io/badge/Python-%3E%3D3.10-89DB76?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Deep Learning](https://img.shields.io/badge/Stack-PyTorch%20%7C%20TensorFlow-FA9138?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)
[![Maintainer](https://img.shields.io/badge/Author-Alizjahan-0F6FFA?style=flat-square&logo=github)](https://github.com/Alizjahan)

Graduate-level coursework and deep learning research implementations for Advanced Data Mining at Shahid Beheshti University.

[Course Overview](#-course-information) • [Final Project Modules](#-models-experiments--benchmarks) • [Repository Structure](#-repository--syllabus-structure) • [Environment Setup](#-environment-setup--notebooks)

</div>

---

## 📚 Course Overview

This repository contains assignments, research experiments, and reproducible benchmarks developed for the **Advanced Data Mining** graduate curriculum. It covers statistical hypothesis testing, change-aware temporal models, anomaly detection, attention mechanisms, and vision transformers.

### 👨‍🏫 Course Information
- **Course:** Advanced Data Mining
- **University:** Shahid Beheshti University (SBU)
- **Instructor:** Dr. Hadi Farahani
- **Term:** Spring 2026
- **Student / Author:** [Alireza Jahanbakhsh](https://github.com/Alizjahan)

---

## 🔬 Models, Experiments & Benchmarks

The capstone project investigates modern neural architectures across four distinct data modalities:

| Module | Architecture | Problem Domain | Dataset & Task | Key Findings & Artifacts |
| :--- | :--- | :--- | :--- | :--- |
| **Mini-Project 1** | **RNN / GRU + Attention** | Multivariate Time Series | Weather Forecasting | Change-aware regime testing, uncertainty bounds, Wilcoxon test |
| **Mini-Project 2** | **Deep Autoencoder** | Anomaly Detection | ECG Signal Analysis | Optimal reconstruction thresholding, Bootstrap CI, Mann-Whitney |
| **Mini-Project 3** | **Transformer** | Natural Language Processing | AG News Classification | Calibration via temperature scaling, McNemar test, attention weights |
| **Mini-Project 4** | **Vision Transformer (ViT)** | Computer Vision | Plant Disease Classification | ViT unfreezing ablation, GradCAM vs Attention maps comparison |

Each mini-project folder includes:
- Fully reproducible Jupyter Notebook (`.ipynb`)
- Formal technical research report (`report.pdf`)
- Tabular results, statistical tests, and publication-ready figures (`results/`)
- Domain-specific dependencies (`requirements.txt`)

---

## 📂 Repository & Syllabus Structure

```text
advanced-data-mining-coursework/
├── Header2.jpg
├── README.md
├── assignments/                             # Graduate-level coursework assignments
└── final-project/
    ├── Project-Handbook.pdf
    ├── mini-project-01-rnn/                 # Multivariate Weather Forecasting (GRU & Attention)
    ├── mini-project-02-autoencoder/         # ECG Anomaly Detection (Deep Autoencoders)
    ├── mini-project-03-transformer/         # AG News Text Classification (Transformer vs CNN)
    └── mini-project-04-vit/                 # Plant Disease Classification (ViT vs ResNet)
```

---

## 🚀 Environment Setup & Notebooks

Each project provides its own isolated `requirements.txt`. To run any of the notebooks locally:

```bash
# Clone repository
git clone https://github.com/Alizjahan/advanced-data-mining-coursework.git
cd advanced-data-mining-coursework

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install requirements for target module (e.g. ViT)
pip install -r final-project/mini-project-04-vit/requirements.txt
```

---

## 👥 Contributors & Credits

- **Author & Researcher:** [Alireza Jahanbakhsh](https://github.com/Alizjahan)
- **Supervising Instructor:** Dr. Hadi Farahani
- **Institution:** Shahid Beheshti University (SBU)

---

## 📄 License & Academic Integrity

This repository is shared for educational and research reference under the **MIT License**.