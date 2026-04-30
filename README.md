# Fashion_RAG_Chatbot
A Retrieval-Augmented Generation (RAG) chatbot that answers questions from fashion PDF documents using LlamaIndex, Mistral-7B, HuggingFace embeddings, and Gradio.

This project is a Retrieval-Augmented Generation (RAG) based chatbot that enables users to ask questions about a fashion-related PDF document and receive context-aware answers.

The system processes the document, converts it into embeddings, retrieves the most relevant sections, and generates accurate responses using a local Large Language Model.

---

## 🚀 Features

- 📄 PDF document ingestion and processing  
- 🔍 Semantic search using vector embeddings  
- 🤖 Context-aware response generation using LLM  
- 🧠 Uses Mistral-7B (local LLM via LlamaCPP)  
- 💬 Interactive chatbot interface with Gradio  
- ⚡ Efficient chunking and retrieval using LlamaIndex  

---

## 🛠️ Tech Stack

- Python  
- LlamaIndex  
- Mistral-7B (GGUF via LlamaCPP)  
- HuggingFace Sentence Transformers  
- LangChain (embeddings integration)  
- Gradio (UI)  
- PyTorch  

---

## ⚙️ How It Works

1. Loads and reads the PDF document  
2. Splits text into smaller chunks  
3. Converts text into embeddings  
4. Stores embeddings in a vector index  
5. Retrieves relevant chunks based on user query  
6. Generates answers using a local LLM  

---

## 🎯 Use Case

- Document-based question answering  
- Knowledge extraction from PDFs  
- AI-powered assistants for domain-specific data  

---

## 📌 Future Improvements

- Add support for multiple PDFs  
- Integrate external vector databases (e.g., Qdrant)  
- Deploy as a web application  
- Improve UI/UX design  

---

## 👩‍💻 Author

Dona Liza Saji  
Master’s in AI & ML | Aspiring AI Engineer
