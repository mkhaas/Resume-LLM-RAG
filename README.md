## ResumeQ&A Bot with LLM RAG Techniques

This repository showcases the implementation of a Resume Question & Answer (Q&A) bot using the Retrieval-Augmented Generation (RAG) techniques of Large Language Model (LLM), along with free and open-source tools.

### Overview

Build an intelligent ResumeQ&A bot that leverages LLM's RAG techniques for enhanced question answering. This project utilizes open-source tools, including PyPDFLoader for document loading, LangChain RecursiveCharacterTextSplitter for text splitting, HuggingFaceEmbedding embeddings, and Chromadb for vector storage. The Flan T5 model available from HuggingfaceHub is employed for contextual question answering.  All this is stitch together using LangChain RetrievalQA chain for retrieving relevant information from stored vectors.

### Features

- **Document Processing:**
  - Load and preprocess resume documents using PyPDFLoader and LangChain RecursiveCharacterTextSplitter.

- **Embeddings and Vector Storage:**
  - Generate embeddings using HuggingFaceEmbeddings model_name="all-MiniLM-L6-v2"
  - Create an in-memory Chromadb for efficient vector storage.

- **Question Answering:**
  - Utilize the Flan T5 model from HuggingfaceHub for contextual question answering.
  - Implement a LangChain RetrievalQA chain for retrieving relevant information from stored vectors.

### Usage in Colab

To run the ResumeQ&A bot in a Colab environment, follow these steps:

1. Open the provided Colab notebook `ResumeLLMRAGexample.ipynb`.
2. Run the notebook cells sequentially.
3. Provide your Hugging Face API key when prompted.

### Sample Resume

For quick testing, a sample resume (`Langchain-Tester-Resume.pdf`) is included in the repository. Feel free to use this sample to observe the bot's question-answering capabilities.

### Getting Started

Follow the steps outlined in the Usage in Colab.

### License

This project is licensed under the MIT License.
