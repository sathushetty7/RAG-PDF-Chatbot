# 📄 PDF RAG Question Answering System

A Retrieval-Augmented Generation (RAG) system that allows users to ask questions about a PDF and get answers based on its content.

## 🚀 Project Highlights

- 📄 PDF text extraction using **PyPDF**
- ✂️ Text chunking with overlapping chunks
- 🧠 Semantic embeddings using **Sentence Transformers**
- 🔍 Vector search using **FAISS**
- 📐 Cosine similarity for better retrieval
- 🤖 Answer generation using **Google FLAN-T5**
- 🔗 Complete **RAG pipeline** from document → retrieval → answer
- 🧪 Tested retrieval quality by inspecting relevant chunks
- 🛠️ Improved chunking and retrieval during development

## 🔄 RAG Pipeline

```text
PDF
 ↓
Text Extraction
 ↓
Text Chunking
 ↓
Sentence Embeddings
 ↓
FAISS + Cosine Similarity
 ↓
Relevant Chunks
 ↓
Context + Question
 ↓
FLAN-T5
 ↓
Final Answer
````

## 🧰 Technologies

* Python
* Google Colab
* PyPDF
* LangChain Text Splitters
* Sentence Transformers
* FAISS
* Hugging Face Transformers
* FLAN-T5
* PyTorch

## 📚 Dataset / Sample PDFs

The project was tested using publicly available research papers.

### Attention Is All You Need

Vaswani et al. — the research paper that introduced the **Transformer architecture**.

**PDF:** [https://arxiv.org/pdf/1706.03762](https://arxiv.org/pdf/1706.03762)

## 📌 Example Questions

```text
What is the Transformer architecture?
What is this PDF mainly about?
What is multi-head attention?
```

The system retrieves the most relevant sections of the PDF before generating the answer.

## 🎯 Key Learning

This project helped understand the core components of **RAG systems**:

* Document processing
* Text chunking
* Embeddings
* Vector databases
* Semantic similarity
* Context retrieval
* LLM-based answer generation

```
```
