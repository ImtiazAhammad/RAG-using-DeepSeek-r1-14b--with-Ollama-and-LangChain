#RAG-using-DeepSeek-r1-14b--with-Ollama-and-LangChain

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
   git clone https://github.com/ImtiazAhammad/RAG-using-DeepSeek-r1-14b--with-Ollama-and-LangChain.git
   cd RAG-using-DeepSeek-r1-14b--with-Ollama-and-LangChain

2. ** Set Up a Virtual Environment: **

 ```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

**Install Dependencies:**

```pip install -r requirements.txt```

**Run the Application:**
`` streamlit run rag_with_pdf.py ``

**Access the App:**
Open your browser and navigate to _http://localhost:8501._

🖥️ Usage
Upload a PDF:

Use the file uploader to upload a PDF document.

Ask Questions:

Type your question in the chat input box.

The app will retrieve relevant context from the PDF and generate a concise answer.

🧠 How It Works
Document Loading:

PDFs are loaded using PDFPlumberLoader and split into chunks using RecursiveCharacterTextSplitter.

Embedding Generation:

Text chunks are converted into embeddings using OllamaEmbeddings.

Vector Storage:

Embeddings are stored in an in-memory vector store for fast retrieval.

Question Answering:

When a question is asked, the system retrieves the most relevant chunks and uses OllamaLLM to generate an answer.

📂 Project Structure
```
GenAI-PDF-RAG-Expert/
├── app.py                # Main Streamlit application
├── README.md             # Project documentation
├── requirements.txt      # Python dependencies
└── data/pdf/             # Directory for uploaded PDFs
```
**🤖 Models Used**
Embeddings: deepseek-r1:14b (via OllamaEmbeddings)

LLM: deepseek-r1:14b (via OllamaLLM)
