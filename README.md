# Autonomous Research Assistant using OpenRouter AI

This project is an intelligent assistant that helps automate literature reviews.

You just give it a research topic, and it will:
- Search relevant papers from ArXiv
- Summarize each one using an AI model via OpenRouter (`qwen/qwen3-coder:free`)
- Generate a clean, structured report
- Save everything as a PDF

Perfect for students, researchers, and anyone exploring a topic deeply.

---

## 🚀 What It Does

- Takes a research topic as input
- Searches top academic papers from ArXiv
- Summarizes the abstracts using an AI model
- Creates a structured literature review
- Outputs a readable PDF you can download

---

## 📁 Files

- `autonomous_research_assistant_openrouter.ipynb`: The main notebook
- `README.md`: This file

---

## 📦 Requirements

You can run this in **Google Colab** (no setup needed), or locally with:

```bash
pip install arxiv fpdf requests
