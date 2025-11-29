This project performs Retrieval-Augmented Generation (RAG) over multiple company PDF documents.
It loads and processes multiple PDFs, embeds them with semantic embeddings, stores them in a FAISS vector database, and generates contextual answers using FLAN-T5 based on retrieved document chunks.

Key Features :

Load and process multiple PDF files, 
Automatic text splitting using RecursiveCharacterTextSplitter, 
Vector search powered by FAISS, 
Embeddings using all-MiniLM-L6-v2, 
LLM response generation using FLAN-T5, 
Retrieves top-k relevant document chunks based on similarity


Library	used :


langchain	- Document pipeline & text processing, 
langchain_community	- PDF loader and FAISS vector store, 
faiss-cpu	- Vector similarity search, 
sentence-transformers -	Embeddings, 
pypdf	- PDF reading support, 
transformers	- Model inference, 
glob	- Multi-PDF file collection
