# 🌍 Multilingual Translator using mBART-50 (LLM-powered)

This project demonstrates a real-time multilingual translation system powered by a **Large Language Model (LLM)** — Facebook AI's **mBART-50**. It supports **50+ languages** and enables flexible translation between any language pair using a Gradio-based web interface.

---

## 🧠 About the LLM: mBART-50

- **mBART-50** is a **large transformer-based encoder-decoder model** trained on multilingual corpora.
- It supports **many-to-many translation** (not just English-centric).
- Pretrained by **Facebook AI**, fine-tuned on 50+ languages.
- LLMs like mBART are capable of **cross-lingual understanding and generation** using context-aware attention mechanisms.
- We use the public model:  
  [`facebook/mbart-large-50-many-to-many-mmt`](https://huggingface.co/facebook/mbart-large-50-many-to-many-mmt)

---

## 🚀 Features

- 🔤 Translate between English, Kannada, Hindi, Tamil, Telugu, French, German, Spanish, and more
- 🌐 Based on a multilingual LLM (mBART-50)
- 💬 Interactive web interface using **Gradio**
- ⚙️ Controlled decoding with language tokens and `forced_bos_token_id`

---

## 🛠️ Setup

Install dependencies:
```bash
pip install -r requirements.txt
