# AI Image Generator – Ultra HD Realistic
A multi-user AI image generator built with Stable Diffusion, Gradio, and PyTorch, capable of producing ultra HD realistic images from text prompts.

https://github.com/user-attachments/assets/e9b597cc-a8fb-4161-916f-d73a03406e5d


[![Hugging Face Spaces](https://img.shields.io/badge/🤗-Hugging%20Face%20Space-yellow)](https://huggingface.co/spaces/your-username/your-space-name)
[![GitHub license](https://img.shields.io/github/license/your-username/AI-Image-Generator)](LICENSE)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)

Generate stunning, ultra‑HD realistic images from text prompts using **Stable Diffusion v1.5** with a two‑stage refinement process (Text‑to‑Image → Image‑to‑Image → Enhancement → Upscaling).

---

## ✨ Features

- **Dual pipeline** – Text‑to‑Image + Image‑to‑Image refinement for higher quality.
- **Automatic contrast, sharpness & brightness enhancement**.
- **Final 2048×2048 upscaling** (using `PIL.LANCZOS`).
- **GPU accelerated** – uses CUDA if available, otherwise CPU.
- **Interactive Gradio UI** – simple web interface with image preview and download.
- **Unique filename** – each output is saved with a random UUID.

---

## 🛠️ Tech Stack

- **Python** 3.10+
- **PyTorch** (with CUDA support)
- **Diffusers** (Hugging Face)
- **Stable Diffusion v1.5** (runwayml/stable-diffusion-v1-5)
- **Gradio** (Web UI)
- **PIL** (image enhancement & upscaling)

---

## 🚀 Live Demo on Hugging Face Spaces

> **Note:** You need a **Hugging Face token** to download the model.  
> The Space will automatically use the token you set in the secrets.

👉 [Click here to try the live demo](https://huggingface.co/spaces/your-username/your-space-name) *(replace with your actual Space URL after deployment)*

---

## 📦 Local Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/AI-Image-Generator.git
cd AI-Image-Generator




