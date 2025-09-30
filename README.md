# Blog-Generation-Agentic-Ai-App

🚀 **Agentic AI Blog Generator** – an AI-powered application that generates complete blog posts using agentic workflows and LLMs.  
It breaks down the task into smaller stages (idea → outline → draft → polish), orchestrated with a workflow graph.

---

## 📌 Features

- Generate blog ideas, outlines, and drafts automatically.
- Multi-agent pipeline (agentic approach with LangGraph-style orchestration).
- Configurable LLM providers (OpenAI, Anthropic, or local models).
- `.env` support for easy configuration.
- Simple web/CLI entry points.

---

## 🗂️ Project Structure

.
├─ app.py # Main app (Streamlit or CLI entry)
├─ main.py # Alternate entry point (API/worker)
├─ langgraph.json # Agentic workflow definition
├─ requirements.txt # Python dependencies
├─ pyproject.toml # Project metadata
├─ _copy.env # Example environment variables
├─ src/ # Source modules (agents, utils, etc.)
└─ README.md # Project documentation


---

## ⚙️ Prerequisites

- Python **3.10+**
- `pip` (or Poetry)
- API key for your chosen LLM provider (e.g., OpenAI, Anthropic)

---

## 🚀 Quickstart

1. **Clone the repo**
   ```bash
   git clone https://github.com/shailovesingh/Blog-Generation-Agentic-Ai-App.git
   cd Blog-Generation-Agentic-Ai-App

# Create a virtual environment
python -m venv .venv
# Activate it
source .venv/bin/activate   # macOS/Linux
.venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

## Author
**Shailove Singh**
