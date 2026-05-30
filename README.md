# Llama4_DeepSeek_RAG

AI-powered PDF Question Answering application using Retrieval-Augmented Generation (RAG).

This project compares **Llama-4** and **DeepSeek-R1** AI models for answering questions from uploaded PDF documents.

## Features

✅ Upload PDF files  
✅ Ask questions from documents  
✅ AI-powered document understanding  
✅ Compare Llama-4 and DeepSeek-R1 responses  
✅ Fast response using Groq API  
✅ Built with Streamlit + LlamaIndex

## Technologies Used

- Python
- Streamlit
- LlamaIndex
- Groq API
- RAG (Retrieval-Augmented Generation)

## Installation

Clone the repository:

```bash
git clone <your-repo-link>
cd Llama4_DeepSeek_RAG
```

Install dependencies:

```bash
uv sync
```

Run the project:

```bash
streamlit run app.py
```

## Environment Variables

Create a `.env` file and add:

```env
GROQ_API_KEY=your_api_key
OPENAI_API_KEY=your_api_key
```

## How It Works

1. Upload a PDF file  
2. Select the AI model  
3. Ask questions about the document  
4. The system uses RAG to retrieve information and generate answers.
