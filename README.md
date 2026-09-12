# AI-Learning-Study-Assistant
# 🎓 AI Learning & Study Assistant

A lightweight, zero-API-key AI Learning Assistant built with Python, Gradio, and Scikit-Learn. It demonstrates core modern AI architecture concepts including **Retrieval-Augmented Generation (RAG)**, **Conversation Memory**, and **Task-Specific Tools** (Learning Plan Generator & Quiz Generator)—all runnable in Google Colab or locally with zero external setup required.

---

## 🚀 Features

* **💬 RAG-Powered Q&A:** Uses TF-IDF vectorization and cosine similarity to retrieve relevant study material based on user prompts.
* **🧠 Conversation Memory:** Maintains a rolling window of the last 5 user queries and answers.
* **📅 Learning Plan Generator:** Generates structured multi-day study schedules based on any input topic.
* **🧩 Automated Quiz Generator:** Creates quick self-assessment quizzes using retrieved context.
* **🌐 Web UI via Gradio:** Features a clean, tabbed web interface that can be shared instantly via a public URL.
* **⚡ Simple & Standalone:** Requires **no OpenAI/API keys**, **no local LLMs**, **no vector database setup**, and **no extra tunneling services (ngrok)**.

---

## 🛠️ Tech Stack

* **UI Framework:** [Gradio](https://www.gradio.app/)
* **Information Retrieval (RAG):** [Scikit-Learn](https://scikit-learn.org/) (`TfidfVectorizer`, `cosine_similarity`)
* **Environment:** Python 3.8+ / Google Colab

---

## 📦 Installation & Setup

### 1. Run in Google Colab (Recommended)
1. Open a new notebook in [Google Colab](https://colab.research.google.com/).
2. Paste the script content into a code cell.
3. Run the cell. Gradio will output both a local URL and a **public `.gradio.live` link**.

### 2. Run Locally

Clone the repository and install dependencies:

```bash
git clone [https://github.com/your-username/AI-Learning-Study-Assistant.git](https://github.com/your-username/AI-Learning-Study-Assistant.git)
cd AI-Learning-Study-Assistant

pip install gradio scikit-learn
python main.py
