# 🧠 AI Research Assistant

This project is an autonomous research assistant built using [LangChain](https://www.langchain.com/), [Anthropic Claude](https://www.anthropic.com/), and various research tools like Wikipedia and DuckDuckGo. It takes a user query, gathers relevant data from multiple sources, and outputs a structured summary — optionally saving it to a local text file.

## 🔍 Features

- 🦙 Uses **Claude 3 Opus** to reason through research queries
- 📚 Gathers information via **Wikipedia** and **DuckDuckGo**
- 🧾 Outputs structured results using **Pydantic**
- 💾 Saves research results to a local file with timestamps
- 🛠 Modular tool-based architecture (easily extensible)

## 🚀 Quickstart

### 1. Clone the repository
```bash
git clone https://github.com/your-username/ai-research-assistant.git
cd ai-research-assistant


python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows
pip install -r requirements.txt


ANTHROPIC_API_KEY=your_claude_api_key_here

python main.py
