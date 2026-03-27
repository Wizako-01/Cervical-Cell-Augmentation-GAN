# Cervical Cell Augmentation using Conditional GAN (cDCGAN)

## Overview
This project implements a **Conditional Deep Convolutional Generative Adversarial Network (cDCGAN)** to generate synthetic cervical cytology images and address class imbalance in Pap smear datasets.

The model is trained on the SIPaKMeD single-cell dataset and generates realistic cell images conditioned on class labels, enabling dataset balancing for improved downstream classification performance.

---

## Dataset
- **Source:** SIPaKMeD (Single Cell PAP Smear Dataset)
- **Classes (5):**
  - Dyskeratotic
  - Koilocytotic
  - Metaplastic
  - Parabasal
  - Superficial-Intermediate
- **Training samples:** ~3,549 images

Dataset is downloaded via Kaggle:

```bash
kaggle datasets download -d mohaliy2016/papsinglecell
