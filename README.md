# 🩺 Hypertension Research Assistant (RAG-based)

A lightweight semantic search and question-answering system built using **Sentence Transformers** for understanding and recommending research papers related to **Hypertension**.

This system enables:
- 🔍 **Semantic retrieval** of medical research papers.
- 🧠 **Context-aware Q&A** from relevant documents.
- ⚡ Fast, local execution without the need for heavy LLMs.

## 💡 How It Works

1. **Document Preprocessing:** PDF research papers are parsed and chunked.
2. **Embedding Generation:** Text chunks are embedded using `sentence-transformers`.
3. **Semantic Search:** Given a user query, relevant chunks are retrieved based on cosine similarity.
4. **Answering:** Relevant content is returned to assist hypertension-related research queries.
