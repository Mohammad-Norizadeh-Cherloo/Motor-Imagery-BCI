# Motor-Imagery-BCI

**From-scratch implementation of Common Spatial Pattern (CSP) and Common Spatio-Spectral Pattern (CSSP) for Motor Imagery based Brain-Computer Interfaces**

**Author:** Mohammad Norizadeh Cherloo  
Educator & Researcher in Machine Learning, Biomedical Signal Processing, and Brain-Computer Interfaces

[![Website](https://img.shields.io/badge/Website-onlinebme.com-blue)](https://onlinebme.com/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-green)](https://scholar.google.com/citations?user=fIKpYm8AAAAJ)
---

### About Motor Imagery-based BCI

In Motor Imagery Brain-Computer Interfaces (MI-BCI), the user imagines moving a part of the body (for example left hand, right hand, foot, or tongue) without any actual movement.  

This mental task produces specific patterns in the EEG signals, mainly in the mu (8–12 Hz) and beta (13–30 Hz) frequency bands. The goal of an MI-BCI system is to detect these patterns and translate them into control commands.

One of the most important and widely used methods for feature extraction in Motor Imagery EEG is the **Common Spatial Pattern (CSP)** algorithm and its improved versions.

---

### Methods Implemented in This Repository

#### 1. Common Spatial Pattern (CSP)

CSP is a supervised spatial filtering method that finds spatial filters which maximize the variance of one class while minimizing the variance of the other class.

After applying CSP filters, the variance of the filtered signals is used as a discriminative feature for classification.

**Key idea of CSP:**
- Maximize variance of Class 1 → Minimize variance of Class 2
- Maximize variance of Class 2 → Minimize variance of Class 1

#### 2. Common Spatio-Spectral Pattern (CSSP)

CSSP is an improved version of CSP.  
While standard CSP only considers spatial information, CSSP also incorporates spectral information, which usually leads to better classification performance in Motor Imagery tasks.

---

### Contents

- `CSP_SVM.ipynb` → Implementation of CSP + SVM
- `CSSP_SVM.ipynb` → Implementation of CSSP + SVM
- `dataset/` → Place the BCI Competition III Dataset IVa here

---

### Dataset

This repository uses the **BCI Competition III - Dataset IVa**.

- Dataset description: [https://www.bbci.de/competition/iii/desc_IVa.html](https://www.bbci.de/competition/iii/desc_IVa.html)
- Download page: [https://www.bbci.de/competition/iii/#data_set_iva](https://www.bbci.de/competition/iii/#data_set_iva)

After downloading, put the `.mat` files inside the `dataset` folder.

---

### Requirements

```bash
pip install numpy scipy scikit-learn matplotlib
```

### Full Video Courses

All mathematical derivations, whiteboard explanations, and step-by-step coding sessions are available here:

**→ [OnlineBME – Motor-Imagery-based BCI Course](https://onlinebme.com/product/brain-computer-interface-package-motorimagery/)**

---

### Contact

- Website: [https://onlinebme.com](https://onlinebme.com)  
- Google Scholar: [Mohammad Norizadeh Cherloo](https://scholar.google.com/citations?user=fIKpYm8AAAAJ)  
- GitHub: [Mohammad-Norizadeh-Cherloo](https://github.com/Mohammad-Norizadeh-Cherloo)

---
