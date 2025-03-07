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

---

### 🚦 Quick Start

### 1. Install Dependencies

```bash
pip install gradio openai anthropic google-generativeai python-dotenv execjs
