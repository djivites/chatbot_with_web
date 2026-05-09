# End-to-End Agentic AI Chatbot

A web-based agentic AI chatbot application built with LangChain, LangGraph, and Streamlit. This project leverages agentic workflows to provide intelligent, context-aware conversational capabilities.

## Features

- **Agentic Workflows**: Powered by LangGraph for complex reasoning and state management.
- **Multiple LLM Support**: Integrated with `langchain_groq` and `langchain_openai`.
- **Retrieval Augmented Generation (RAG)**: Uses FAISS for efficient local vector search.
- **Web Search Tools**: Integrated with Tavily for real-time internet search capabilities.
- **Interactive UI**: Clean, easy-to-use web interface built using Streamlit.

## Prerequisites

Ensure you have Python installed. The project relies on the dependencies listed in `requirements.txt`.

## Installation

1. Clone the repository and navigate to the project directory:
   ```bash
   cd chatbot_with_web
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up your environment variables. You may need API keys for:
   - OpenAI (`OPENAI_API_KEY`)
   - Groq (`GROQ_API_KEY`)
   - Tavily (`TAVILY_API_KEY`)

## Usage

Run the Streamlit application using the following command:

```bash
streamlit run app.py
```

This will start the local web server and open the application in your default web browser.

## Project Structure

- `app.py`: The main entry point for the Streamlit application.
- `src/`: Contains the core logic, including LangGraph agent definitions.
- `requirements.txt`: Python package dependencies.