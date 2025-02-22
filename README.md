# GenAI-PDF-RAG-Expert

A Retrieval-Augmented Generation (RAG) system built with **LangChain**, **Ollama**, and **Streamlit** to answer questions from PDF documents. This project demonstrates expertise in Generative AI, document processing, and building AI-powered applications.

---

## 🚀 Features

- **PDF Document Processing**: Upload and process PDF files using `PDFPlumberLoader`.
- **Text Chunking**: Split documents into manageable chunks for efficient retrieval.
- **Vector Embeddings**: Use **OllamaEmbeddings** to generate embeddings for semantic search.
- **In-Memory Vector Store**: Store and retrieve document embeddings using `InMemoryVectorStore`.
- **Question Answering**: Leverage **OllamaLLM** (Deepseek model) to answer user questions based on retrieved context.
- **Streamlit UI**: Interactive web interface for uploading PDFs and asking questions.

---

## 🛠️ Tech Stack

- **LangChain**: Framework for building AI applications with LLMs.
- **Ollama**: Local LLM and embeddings provider (Deepseek model).
- **Streamlit**: Web framework for building interactive AI apps.
- **PDFPlumber**: PDF text extraction library.

---

## 📦 Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/GenAI-PDF-RAG-Expert.git
   cd GenAI-PDF-RAG-Expert