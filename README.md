# 🔎 LangChain + Streamlit Chatbot with Web Search

An interactive AI chatbot powered by LangChain, Groq's LLaMA3-8b model, and Streamlit. The chatbot can perform web searches using DuckDuckGo, Wikipedia, and arXiv, with real-time reasoning display.

## 🌐 Live Demo

Try asking questions like:
- "What is machine learning?"
- "Find recent papers on quantum computing"
- "Tell me about Alan Turing from Wikipedia"

The agent will automatically select and use the most appropriate tools to find and summarize information.

## 🚀 Features

- **Web Search Integration**:
  - 🔍 DuckDuckGo for general web search
  - 📚 Wikipedia for encyclopedic knowledge
  - 📄 arXiv for academic papers
- **AI Backend**:
  - 🧠 Powered by Groq's LLaMA3-8b via `ChatGroq`
  - 🤖 Uses LangChain's zero-shot-react agent for tool selection
- **Interactive Interface**:
  - 📟 Real-time streaming with `StreamlitCallbackHandler`
  - 💬 Full chat interface with message history

## 🛠️ Setup & Installation

### Prerequisites
- Python 3.8+
- Groq API key (free tier available)

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/langchain-search-agent
cd langchain-search-agent