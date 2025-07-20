# 🚀 Synthetic Product Review Generator

This project generates a **synthetic dataset of product reviews** (positive/negative) using open‑source LLMs via a Gradio web interface or Google Colab.

---

## 🔧 Features

- **Customizable dataset size**: choose any number of reviews (N)  
- **Balanced sentiment**: half positive, half negative (adjustable)  
- **Multiple LLM backends**: LLaMA, Phi‑3 mini, Gemma‑2, Qwen‑2, Mixtral‑8x7B  
- **Download formats**: outputs JSON 
- **Live streaming**: watch reviews generate in real time  
- **Easy deployment**: ideal for Google Colab or local use  

---

## 📋 Prerequisites

1. **Python 3.10+**  
2. **CUDA‑capable GPU** (Linux or Windows recommended)  
3. **Hugging Face account & token**  
   ```bash
   pip install huggingface_hub
   huggingface-cli login
   ```  
4. Set your Hugging Face token:  
   ```bash
   export HUGGINGFACE_TOKEN="hf_xxxYYYzzz"
   ```  

---

## 🧩 How It Works

1. Select model, number of reviews, and product info  
2. Click **Generate**  
3. Watch the streaming output preview
4. Copy paste the Json format dataset

---

## 👀 Interface Preview

<img width="1920" height="542" alt="Screenshot 2025-07-20 at 11 17 14 AM" src="https://github.com/user-attachments/assets/d6d7b86c-88eb-498c-83c1-8aabc3df96ab" />

---


## 🧪 Notes & Tips

- Use **4‑bit/8‑bit quantization** (`bitsandbytes`) to reduce GPU usage  
- **Google Colab** is recommended for ease of setup  
- **Hugging Face token** is required to load model weights  

---

**Happy synthetic data generation!** 🎉
