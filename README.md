# STAD68-efficient-diffusion-failure-modes
A study of failure modes in efficient diffusion models using a teacher–student framework, analyzing diversity, structural fidelity, and controllability under accelerated sampling.

# Failure Modes of Efficient Diffusion Models

This repository contains the implementation for our project:

**"Failure Modes of Efficient Diffusion Models"**

---

## Overview

This project investigates how efficiency-oriented diffusion models (e.g., Latent Consistency Models) introduce systematic failure modes when reducing inference steps.

We implement a **teacher–student framework**:
- **Teacher:** Stable Diffusion 1.5  
- **Student:** Latent Consistency Model (LCM)

We analyze model behavior across:
- inference steps
- random seeds
- guidance strength (CFG)
- prompt categories

---

## Recommended Setup

**Strongly recommended: run this notebook using Google Colab with GPU enabled**

Because diffusion models are computationally expensive. Running locally without GPU may be extremely slow or fail.

### Steps:
1. Go to: https://colab.research.google.com  
2. Upload:
3. Enable GPU:
- Runtime → Change runtime type → GPU  
4. Run all cells

---

## Optional Local Setup

If running locally:

```bash
pip install -r requirements.txt

jupyter notebook updated_stad68_final_report_coding.ipynb
