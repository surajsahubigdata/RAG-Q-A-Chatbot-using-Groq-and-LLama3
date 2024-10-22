# RAG Document Q&A With Groq And Llama3

## Overview
This project implements a Retrieval-Augmented Generation (RAG) model to answer questions based on the content of research papers. Utilizing Langchain, Groq, and Llama3, the application allows users to query uploaded PDF documents and receive contextually relevant answers.

## Features
+ **Document Embedding**: Users can load and embed documents, which are stored in a vector database for efficient retrieval.
+ **Contextual Q&A**: The application provides answers based solely on the content of the uploaded research papers.
+ **Similarity Search**: Users can view documents that are contextually relevant to their queries.

## Technologies Used
+ **Streamlit**: For building the web application interface.
+ **Langchain**: For managing the document loading, embeddings, and retrieval processes.
+ **Groq API**: To facilitate the use of Groq's capabilities for language models.
+ **Llama3**: A powerful language model used for generating answers to user queries.
+ **FAISS**: For managing the vector database of embedded documents.

## Installation
+ Clone the repository:
    Inline `code`

    git clone <repository-url>
    cd <repository-name>
