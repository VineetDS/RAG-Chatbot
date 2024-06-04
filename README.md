Chat with Multiple PDFs using RAG, LLM, and VectorDB

Overview
This project implements a chatbot that allows users to interact with multiple PDF documents. It uses a Retrieval-Augmented Generation (RAG) system with GooglePalm LLM and FAISS vector store for efficient document retrieval and response generation.

Features
- Extract text from multiple PDF documents.
- Split text into manageable chunks.
- Convert text chunks into numerical vectors using GooglePalm embeddings.
- Store and retrieve embeddings using FAISS vector store.
- Generate conversational responses using GooglePalm LLM.
- User-friendly interface built with Streamlit.


Chatbot Architecture:
This Image show the basic archotecture of the chatbot.
![rag-diagram](https://github.com/VineetDS/RAG-Chatbot/assets/98698202/f1177d7c-0d59-40ea-9a6e-cec531a1dff5)

Setup Instruction:
git clone https://github.com/VineetDS/RAG-Chatbot.git


Functions :-
- get_pdf_text(pdf_docs): Extracts text from PDF files.
- get_text_chunks(text): Splits text into smaller chunks.
- get_vector_store(text_chunks): Creates a vector store using Google Palm embeddings.
- get_conversational_chain(vector_store): Creates a conversational chain using the vector store.
- user_input(user_question): Takes user input and displays the conversation with the chatbot.



