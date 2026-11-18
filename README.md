# 📝 AI-Powered Text Summarizer

An end-to-end web application that performs abstractive text summarization using a fine-tuned **T5 Transformer** model, served via a high-performance **FastAPI** backend and a clean, responsive HTML/CSS frontend.

---

## 🚀 Features
* **Abstractive Summarization:** Powered by a custom fine-tuned T5 model (`./saved_summary_model`) capable of understanding context and generating concise summaries.
* **Hardware Accelerated:** Automatically detects and leverages Apple Silicon MPS (`torch.device("mps")`), NVIDIA CUDA GPUs, or falls back to CPU efficiently.
* **Robust Text Preprocessing:** Cleans incoming payloads (strips HTML tags, normalizes whitespace and line breaks) to improve generation stability[cite: 2].
* **Modern UI:** Minimalist, user-friendly interface styled with custom CSS and asynchronous JavaScript for seamless user interaction[cite: 1].

---

## 🛠️ Tech Stack
* **Backend:** FastAPI, Pydantic, Uvicorn
* **Deep Learning & NLP:** Hugging Face Transformers, PyTorch, SentencePiece/T5 Tokenizer
* **Frontend:** HTML5, CSS3, Vanilla JavaScript, Jinja2 Templates

---

