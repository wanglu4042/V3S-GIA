# V3S-GIA
A VAE-Based Three-Stage Gradient Inversion Attack for Practical Federated Learning without Task-Specific Priors
# V3S-GIA: A Plug-and-Play VAE-based Three-Stage Gradient Inversion Attack Framework

**[Anonymous Submission for ACM CCS 2026]**

This repository contains the official PyTorch implementation of **V3S-GIA**, a novel gradient inversion attack framework.

> **Note to Reviewers:** This repository is anonymized for the peer-review process. All personal information and affiliations have been removed.

## 📋 Requirements & Dependencies

The code is tested on **Python 3.10** with **PyTorch 2.1.0**.
We recommend using a high-end NVIDIA GPU (e.g., A100/A800 or RTX 30/40 series) for reproduction, though it supports any CUDA-enabled device.

* **OS:** Linux (Recommended) or Windows 10/11
* **CUDA Version:** 12.1 (Default) / 11.8 (Compatible)
* **Python:** 3.10
* **Key Libraries:** `diffusers`, `transformers`, `insightface`, `lpips`

## 🛠️ Installation

We provide automated scripts for one-click environment setup on both Linux and Windows.

### 1. Clone the Repository
```bash
git clone <ANONYMOUS_REPO_URL>
cd V3S_GIA
