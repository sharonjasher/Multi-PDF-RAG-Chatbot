 📄 Multi-PDF RAG Chatbot with GPT-4o

> Ask intelligent questions across multiple PDFs using GPT-4o and LangChain RAG.

![Streamlit](https://img.shields.io/badge/Streamlit-Enabled-ff4b4b?logo=streamlit&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-RAG-blue?logo=python)
![License](https://img.shields.io/github/license/yourusername/multi-pdf-rag-chatbot)

---

## 📚 Table of Contents

- 🚀 Project Overview
- ✨ Key Features
- 📺 Demo
- 🔧 Prerequisites
- ⚙️ Installation
- 💡 Usage
- 🛠 Configuration
- 🗺 Roadmap
- 🤝 Contributing
- 🪪 License
- 👤 Author
- 🙏 Acknowledgements

---

## 🚀 Project Overview

**Multi-PDF RAG Chatbot** is a lightweight, intelligent chatbot that allows users to upload multiple PDF documents and ask natural language questions based on the content. It combines the power of OpenAI's GPT-4o with LangChain and FAISS for fast, relevant, and source-backed responses.

---

## ✨ Key Features

- 📂 Upload and analyze multiple PDF files at once
- 🤖 Conversational Q&A powered by GPT-4o
- 📚 Source-aware responses using FAISS vector retrieval
- 🕒 Chat history with Q&A export as text
- 🧠 Built with LangChain’s Retrieval-Augmented Generation (RAG)

---

## 📺 Demo

(Demo GIF or video can be added here if available)

---

## 🔧 Prerequisites

- Python 3.9 or higher
- OpenAI API key
- Pip (Python package installer)

---

## ⚙️ Installation

Clone this repo and install dependencies:

```bash
git clone https://github.com/yourusername/multi-pdf-rag-chatbot.git
cd multi-pdf-rag-chatbot
pip install -r requirements.txt
```

Or install manually:

```bash
pip install streamlit langchain langchain-community openai faiss-cpu PyPDF2 python-dotenv
```

---

## 💡 Usage

Start the Streamlit app:

```bash
streamlit run rag_multi_pdf_chatbot.py
```

Upload one or more PDF files, then ask questions like:

```text
What are the main points in the introduction section?
Summarize the results discussed in these documents.

```


## 🛠 Configuration

Create a `.env` file in the root directory with your OpenAI API key:

```
OPENAI_API_KEY=your_openai_api_key_here
```

---

## 🗺 Roadmap

- [ ] Add per-PDF source tracking
- [ ] Enable follow-up conversation with memory
- [ ] Add file-type support beyond PDFs (e.g., DOCX, TXT)
- [ ] Deploy to Hugging Face Spaces or Streamlit Cloud

---

## 🤝 Contributing

Contributions are welcome!  
Please see the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 🪪 License

This project is licensed under the **MIT License** – see the LICENSE file for details.

---

## 👤 Author

**Sharon Inbarani**  
📧 jcsdigitech@gmail.com  
🔗 https://www.linkedin.com/in/sharon-inbarani-040820269/

---

## 🙏 Acknowledgements

- [LangChain](https://www.langchain.com/)
- [OpenAI](https://openai.com/)
- [Streamlit](https://streamlit.io/)
- [FAISS by Facebook AI](https://github.com/facebookresearch/faiss)
