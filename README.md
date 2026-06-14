# Enhanced Q&A Chatbot with OpenAI

A simple **Streamlit-based chatbot** built using **LangChain** and **OpenAI models**.  
This app lets users ask questions, select different OpenAI models, and get AI-powered answers in real time.

---

## 🚀 Features
- Interactive chatbot interface with **Streamlit**.
- Supports multiple OpenAI models (`gpt-4o`, `gpt-4-turbo`, `gpt-4`).
- Adjustable response parameters:
  - **Temperature** (creativity of responses).
  - **Max tokens** (length of responses).
- Environment variable support via `.env` file.
- Integrated with **LangSmith** for tracing and monitoring.

---

## 📦 Requirements
- Python 3.9+  
- Packages:
  - `streamlit`
  - `openai`
  - `langchain`
  - `langchain-openai`
  - `langchain-core`
  - `python-dotenv`

---

## 🔧 Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/QA-CHATBOT.git
   cd QA-CHATBOT


python -m venv .venv
source .venv/bin/activate   # On macOS/Linux
.venv\Scripts\activate      # On Windows


pip install -r requirements.txt


OPENAI_API_KEY=your_openai_api_key_here
LANGCHAIN_API_KEY=your_langchain_api_key_here
