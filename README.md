# Multi-PDF-s 📚ChatApp AI Agent 🤖

Meet MultiPDF Chat AI App! 🚀 Chat seamlessly with Multiple PDFs using Langchain, Google Gemini Pro & FAISS Vector DB with Seamless Streamlit Deployment. Get instant, Accurate responses from Awesome Google Gemini OpenSource language Model. 📚💬 Transform your PDF experience now! 🔥✨

# 📝 Description
The Multi-PDF's Chat Agent is a Streamlit-based web application designed to facilitate interactive conversations with a chatbot. The app allows users to upload multiple PDF documents, extract text information from them, and train a chatbot using this extracted content. Users can then engage in real-time conversations with the chatbot.

# How It Works:

The application follows these steps to provide responses to your questions:

PDF Loading : The app reads multiple PDF documents and extracts their text content.

Text Chunking : The extracted text is divided into smaller chunks that can be processed effectively.

Language Model : The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

Similarity Matching : When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

Response Generation : The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.

Demo 2: Chatbot Output

# 🎯 Key Features
Adaptive Chunking: Our Sliding Window Chunking technique dynamically adjusts window size and position for RAG, balancing fine-grained and coarse-grained data access based on data complexity and context.

Multi-Document Conversational QA: Supports simple and multi-hop queries across multiple documents simultaneously, breaking the single-document limitation.

File Compatibility: Supports both PDF and TXT file formats.

LLM Model Compatibility: Supports Google Gemini Pro, OpenAI GPT 3, Anthropic Claude, Llama2 and other open-source LLMs.

