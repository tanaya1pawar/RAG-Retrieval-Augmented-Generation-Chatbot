# Fragrances International - Customer Service RAG Chatbot

An intelligent Retrieval-Augmented Generation (RAG) customer service chatbot built for an online perfume company, **Fragrances International**. The chatbot uses local open-source embeddings, a vector database, and a Hugging Face language model to accurately answer customer queries based strictly on provided company documentation.

## Features

* **Retrieval-Augmented Generation (RAG):** Grounds the model's responses in specific company data (FAQs, shipping times, product offerings) to reduce hallucinations.
* **Vector Search:** Powered by **ChromaDB** and **Sentence Transformers** (`all-MiniLM-L6-v2`) for fast and relevant semantic search.
* **Local/Hugging Face Integration:** Utilizes the `meta-llama/Llama-2-7b-chat-hf` model via Hugging Face pipelines.
* **LangChain Framework:** Leverages LangChain components for document loading, splitting, prompting, and QA retrieval chains.

---

## Project Structure

```text
chatbot_project/
│
├── data.csv              # Knowledge base containing company Q&A details
├── app.py                # Main application script executing the RAG pipeline
├── requirements.txt      # List of required Python packages
└── README.md             # Project documentation# RAG-Retrieval-Augmented-Generation-Chatbot
project is a RAG (Retrieval-Augmented Generation) Chatbot built using LangChain, ChromaDB, Hugging Face (meta-llama/Llama-2-7b-chat-hf), and local embeddings (sentence-transformers/all-MiniLM-L6-v2) for an online perfume store named Fragrances International.
