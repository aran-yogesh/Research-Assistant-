# Personal Research Assistant – RAG + Query Rewriting

This repository contains a personal research assistant built using a Retrieval-Augmented Generation (RAG) pipeline. It is designed to read, understand, and answer questions from research papers (PDFs) stored locally. The assistant enhances vague or underspecified queries through dynamic rewriting and uses dense vector retrieval to surface the most relevant context before generating a detailed response using a local LLM (FLAN-T5).

 # Key Features:
	•	Document Loading: Automatically loads and parses all PDFs from a specified directory.
	•	Chunking & Embedding: Splits documents into overlapping chunks and embeds them using all-MiniLM-L6-v2.
	•	FAISS Vector Search: Enables fast and accurate retrieval of relevant document passages.
	•	Query Rewriting: Improves vague user queries using google/flan-t5-base for better information retrieval.
	•	Answer Generation: Combines retrieved context and rewritten queries to generate informative answers locally.

This system is designed for personal academic use—ideal for summarizing papers, exploring unfamiliar topics, or building foundational understanding through natural question answering.
