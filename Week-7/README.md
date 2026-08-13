# Week 7 - Document Question Answering System using RAG

## Objective

The objective of this project is to develop a simple Retrieval-Augmented Generation (RAG) system that can answer questions from a custom document.

The system retrieves relevant information from the provided PDF document and uses a language model to generate answers based on the retrieved context.

## Technologies Used

- Python
- Google Colab
- PyMuPDF
- Sentence Transformers
- FAISS
- Cross-Encoder
- FLAN-T5
- NumPy

## RAG Pipeline

The project follows the following pipeline:

PDF Document
↓
Text Extraction
↓
Text Chunking
↓
Sentence Embeddings
↓
FAISS Vector Store
↓
Question Embedding
↓
Relevant Document Retrieval
↓
Document Reranking
↓
Context Construction
↓
FLAN-T5
↓
Generated Answer

## Dataset / Document

A custom PDF document containing Data Science and Deep Learning notes is used as the knowledge source for the RAG system.

File:

`Data_Science_Deep_Learning_Notes_for_RAG.pdf`

## Implementation

The project performs the following steps:

1. Loads and extracts text from the PDF.
2. Splits the document into overlapping text chunks.
3. Generates embeddings using Sentence Transformers.
4. Stores the embeddings in a FAISS vector index.
5. Retrieves relevant chunks based on semantic similarity.
6. Reranks the retrieved chunks using a Cross-Encoder.
7. Provides the relevant context to the FLAN-T5 language model.
8. Generates answers to user questions.
9. Tests the system using multiple questions.
10. Inspects the retrieved context to evaluate the retrieval process.

## Results

The implemented RAG system successfully retrieves relevant information from the custom PDF and generates answers using the retrieved context.

The notebook also includes multiple test questions, retrieved contexts, reranking results, generated answers, observations, limitations, and possible improvements.

## Files

- `week7_Parth_Rohilla.ipynb` - Complete executed Google Colab notebook.
- `Data_Science_Deep_Learning_Notes_for_RAG.pdf` - Custom document used as the knowledge source.

## Conclusion

This project demonstrates the implementation of a basic Retrieval-Augmented Generation system for document question answering. It shows how document retrieval, semantic embeddings, vector similarity search, reranking, and language generation can be combined to answer questions using custom documents.
