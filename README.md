# LLM-Projects
## LLM Project 1
### 🚀 AI-Powered Bank FD Rate Analyzer
 A personal project that combines AI and web scraping to extract and analyze Fixed Deposit (FD) rates from various bank websites, helping users find the best investment option.
### 🔥 How AI Powers This Project.
   Web Scraping with BeautifulSoup → Extracts text-based data from bank websites.
   AI-Powered Summarization (GPT-4o-mini) → Processes and summarizes financial insights.
   Automated Bank Comparison → AI ranks banks based on FD interest rates.
   Natural Language Processing (NLP) → Cleans and structures web data for better analysis.
### How It Works	
   The script fetches bank FD rate pages using web scraping.
   AI processes the extracted text to identify interest rates and key details.
   AI ranks and suggests the best bank for FD investments based on returns and reliability.

## LLM Project 2

This Python script sets up a web application using Gradio to allow users to interact with two AI assistants, OpenAI's GPT-4 and Anthropic's Claude, side-by-side. 

### Key Components:
- **Environment Variables**: Loaded using `dotenv`.
- **AI Client Initialization**: Instantiates clients for OpenAI and Anthropic.
- **System Message**: A predefined message that describes the assistant's purpose (updating resumes).
- **Chat Functions**: 
  - `chat_gpt`: Handles user messages for the GPT-4 model.
  - `chat_claude`: Handles user messages for the Claude model.
- **Gradio Interface**: Creates a user interface with two columns, each hosting a chat interface for one of the AI models.

### Functionality:
- Users can input messages and receive responses from both GPT-4 and Claude simultaneously, facilitating easy comparison.

## LLM Project 3
### 🚀 AI-Powered Code Converter & Executor

A simple yet powerful AI tool that **converts and optimizes code** between **Python, JavaScript, and C++**, allowing you to run and test code directly from your browser.

---

### ✨ Features

- **🔄 Multi-language Conversion**:
  - Python ↔️ JavaScript ↔️ C++
- **🤖 Advanced AI Models**:
  - GPT-4o (OpenAI)
  - Claude 3 Sonnet (Anthropic)
  - Gemini 1.5 Flash (Google)
- **▶️ Instant Code Execution**:
  - Execute both original and converted code immediately.
- **🌟 User-Friendly Web Interface**:
  - Built with **Gradio** for ease of use.

---

### ⚙️ How It Works

1. Enter your code and choose languages for conversion.
2. Select an AI model for optimal performance.
3. Receive optimized code instantly.
4. Run both input and output code directly within the app.

---

### 🛠️ Tech Stack

- **Gradio** (UI)
- **OpenAI API** (GPT-4o)
- **Anthropic API** (Claude 3)
- **Google Generative AI** (Gemini)
- **ExecJS** (JavaScript execution)
- **Subprocess & Clang++** (C++ compilation)
- **Dotenv** (Secure management of API keys)





## LLM Project 4

## Court Case RAG AI Application (RAG - Retrieval augmented generation)

## Overview
The **Court Case Retrieval-Augmented Generation (RAG) AI** application enables fast and efficient searching, retrieval, and summarization of legal court case files. By leveraging state-of-the-art natural language processing (NLP) technologies, this system delivers high-accuracy responses to legal queries. It retrieves relevant case data from a large database of court documents and generates concise summaries, making it an invaluable tool for legal professionals.

The system combines the power of **LangChain** for orchestrating the RAG pipeline, **Chroma** for vector-based document storage and retrieval, and **OpenAI’s GPT-4o-mini** model for generating responses, all presented via an intuitive user interface powered by **Gradio**.

## Key Features
- **Fast Query Processing**: Get rapid, accurate responses to complex legal queries.
- **Intelligent Document Retrieval**: Efficiently retrieves relevant legal documents for case analysis.
- **Context-Aware Summarization**: Generates coherent and concise summaries of case information.
- **User-Friendly Interface**: A simple, intuitive interface built using Gradio to allow users to interact with the application effortlessly.

## Technical Architecture
The application is powered by the following components:

- **Framework**: [LangChain](https://langchain.com) for orchestrating the Retrieval-Augmented Generation (RAG) pipeline.
- **Vector Database**: [Chroma](https://www.trychroma.com/) for efficient document storage and retrieval based on embeddings.
- **Embedding Model**: [OpenAI’s Embedding Model](https://openai.com/research/embedding) to transform legal documents into embeddings for faster search and retrieval.
- **Large Language Model (LLM)**: [GPT-4o-mini](https://openai.com) for generating high-quality responses to legal queries.
- **User Interface**: [Gradio](https://gradio.app/) for creating a responsive and user-friendly web interface.
- **Document Processing**: Chunking system with large context windows (100,000 tokens with a 20,000 token overlap) for efficient document chunking and retrieval.

## Data Processing
I Got this court cade database from Hugging Face Data Sets

The court case database is processed and stored in a way that maximizes the efficiency of the RAG pipeline:

- **Chunk Size**: Each document is divided into chunks of **100,000 tokens**.
- **Chunk Overlap**: To maintain context between chunks, a **20,000 token overlap** is used.
- **Total Chunks**: The system processes and stores **51 chunks** of documents, ensuring optimal context retrieval for query processing.


