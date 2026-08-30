# Motor Imagery BCI: CSP and CSSP from Scratch
<img width="1200" height="720" alt="motor imagery bci" src="https://github.com/user-attachments/assets/d0cbe377-9036-490a-a987-a51b57f4627f" />


**From-scratch Python implementations of Common Spatial Pattern (CSP) and Common Spatio-Spectral Pattern (CSSP) for EEG-based Motor Imagery Brain-Computer Interfaces (MI-BCI).**
---
**Author:** Mohammad Norizadeh Cherloo  
Educator & Researcher in Machine Learning, Biomedical Signal Processing, and Brain-Computer Interfaces

[![Website](https://img.shields.io/badge/Website-onlinebme.com-blue)](https://onlinebme.com/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-green)](https://scholar.google.com/citations?user=fIKpYm8AAAAJ)
[![YouTube](https://img.shields.io/badge/YouTube-@Mrcherloo-red)](https://www.youtube.com/@Mrcherloo)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/mohammad-norizadeh-cherloo/)
---

## Overview
<img width="1200" height="445" alt="csp-and-eeg-signal" src="https://github.com/user-attachments/assets/cf4eeafb-78ed-4494-a2f7-8811e6757d17" />

This repository contains **from-scratch implementations of classical EEG signal processing and machine learning methods for Motor Imagery BCI**.

The current projects implement:

* **Common Spatial Pattern (CSP)**
* **Common Spatio-Spectral Pattern (CSSP)**
* **Support Vector Machine (SVM)** for classification

The implementations are designed to expose the mathematical and computational steps of the algorithms rather than relying on specialized BCI libraries.

---

## Projects

### 1. Common Spatial Pattern (CSP) + SVM

CSP is a widely used spatial filtering method for **motor imagery EEG classification**. It learns spatial filters that maximize the variance difference between two EEG classes.

👉 **[Open CSP + SVM Code](project01_CSP_SVM.ipynb)**

---

### 2. Common Spatio-Spectral Pattern (CSSP) + SVM

CSSP extends CSP by incorporating spectral information into the spatial filtering framework for **motor imagery EEG classification**.

👉 **[Open CSSP + SVM Code](project02_CSSP_SVM.ipynb)**

---

## Dataset

The implementations use the **BCI Competition III – Dataset IVa**, a benchmark dataset for EEG-based motor imagery BCI research.

* [Dataset IVa — Official Description](https://www.bbci.de/competition/iii/desc_IVa.html)
* [Dataset IVa — Download](https://www.bbci.de/competition/iii/#data_set_iva)

Place the downloaded dataset in:

```text
dataset/
```

---

## Repository Structure

```text
Motor-Imagery-BCI/
│
├── dataset/
│
├── project01_CSP_SVM.ipynb
├── project02_CSSP_SVM.ipynb
└── README.md
```

---

## Requirements

```bash
pip install numpy scipy scikit-learn matplotlib
```

The notebooks can be opened and executed using **Jupyter Notebook, JupyterLab, or Google Colab**.

---

## Related Research

This repository is related to my research on **motor imagery EEG classification, spatial filtering, and brain-computer interfaces**.

**Ensemble Regularized Common Spatio-Spectral Pattern (Ensemble RCSSP) Model for Motor Imagery-Based EEG Signal Classification**

*Computers in Biology and Medicine, 2021.*

[Read the paper](https://doi.org/10.1016/j.compbiomed.2021.104546)

---

## Full Video Course

For a detailed, project-based treatment of **EEG signal processing for Motor Imagery BCI**, including **CSP, FBCSP, spatial filtering, feature extraction, classification, and practical implementations on real BCI Competition datasets**, see:

**→ [OnlineBME – Motor Imagery-based BCI](https://onlinebme.com/product/brain-computer-interface-package-motorimagery/)**

---

**If you find the repository useful, consider ⭐ starring it.**
