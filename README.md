# 🤖 LangChain Ollama Agent Framework

A production-ready AI agent framework built on **LangChain**, designed for seamless integration with local LLMs via **Ollama**. This framework features comprehensive tool integration, RAG capabilities, and unrestricted web exploration.

---

## 🚀 Key Capabilities

### 🔍 Advanced Information Retrieval
- **Web Search**: Selenium-based DuckDuckGo integration for high-reliability data fetching.
- **Academic Research**: Specialized arXiv integration for academic paper discovery and summarization.
- **Deep Scraping**: Intelligent content extraction using BeautifulSoup for structured data gathering.

### 🧠 RAG System
- **Vector Intelligence**: Support for Chroma and FAISS vector stores.
- **Document Processing**: native support for PDF, DOCX, Markdown, and more.
- **Semantic Search**: High-accuracy retrieval using sentence-transformer embeddings.

### 🛠️ Modular Tool Ecosystem
- **File Management**: Secure system operations for data persistence.
- **Execution Monitoring**: Custom callback handlers for detailed agent process tracking.
- **Error Resilience**: Built-in retry mechanisms and graceful degradation.

---

## 📂 Project Architecture

```bash
langchain_agent/
├── agent/                # Core agent logic & tool management
├── config/               # System & model configurations
├── interactive.py        # Professional CLI interface
└── requirements.txt      # Dependency manifest
```

---

## 🛠️ Installation & Setup

### 1. Requirements
Ensure you have **Python 3.8+** and **Ollama** installed.

### 2. Quick Start
```bash
pip install -r requirements.txt
ollama serve
ollama pull gpt-oss:20b # Or your preferred model
python interactive.py
```

---

## 📄 License

This project is licensed under the MIT License.

---

## Author & Contact

- **GitHub:** [@rouviour-german](https://github.com/rouviour-german)
- **Email:** [rouviourgermanmeetings@gmail.com](mailto:rouviourgermanmeetings@gmail.com)
- **Profile:** https://github.com/rouviour-german

