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

    git clone https://github.com/surajsahubigdata/RAG-Q-A-Chatbot-using-Groq-and-LLama3.git

+ Create virtual environment and install the required packages:

    Inline `code`

    conda create -p venv python==3.10

    pip install -r requirements.txt

+ Create a .env file in the project root directory and add your API keys:

    Inline `code`

    GROQ_API_KEY=your_groq_api_key
    HF_TOKEN=your_hugging_face_token

## Usage

+ Run the streamlit application:

    Inline `code`

    streamlit run app.py

+ Open your web browser and navigate to http://localhost:8501
+ Upload research papers by placing them in the research_papers directory
+ Enter your query in the provided text input and click the "Document Embedding" button to prepare the vector database.
+ After embedding the documents, you can enter any query related to the content of the research papers, and the application will     provide answers along with context from the relevant documents.

## Acknowledgments
+ Langchain
+ Groq
+ Hugging Face
+ FAISS

## User Interface

![alt text](<User Interface 1.PNG>)

![alt text](<User Interface 2.PNG>)







