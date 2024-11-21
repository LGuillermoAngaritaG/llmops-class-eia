# Local Examples

This directory contains standalone examples demonstrating various LLMOps concepts and implementations. Each example is self-contained and showcases different aspects of working with Large Language Models (LLMs) and AI applications.

## Examples Overview

### 1. YouTube Summarizer
A tool that leverages MLFlow and Groq LLM to create summaries of YouTube videos.

**Key Features:**
- Extracts transcripts from YouTube videos
- Processes and summarizes content using Groq LLM
- Tracks performance metrics using MLFlow
- Demonstrates MLOps practices in LLM applications

### 2. Chat with Repository
An interactive tool that enables natural language conversations about code repositories.

**Key Features:**
- Uses LangChain for document processing and LLM interactions
- Implements Cohere embeddings for semantic search
- Utilizes Chroma vector store for efficient retrieval
- Provides natural language Q&A about repository contents

### 3. Research Coding Agent
A proof-of-concept AI agent that can perform research and coding tasks.

**Key Features:**
- Implements ReAct framework from LangChain
- Integrates multiple tools:
  - Python REPL for code execution
  - Web search via DuckDuckGo
  - Custom poem generation using Groq LLM
- Demonstrates multi-step reasoning and task execution

## Setup Requirements

- Python 3.11.10 or later
- Required packages:
  - langchain
  - groq
  - cohere
  - chromadb
  - mlflow
  - jupyter

## Getting Started

1. Clone the repository
2. Navigate to the specific example directory
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Follow the README instructions in each example directory for specific setup steps

## API Keys

Some examples require API keys for external services:
- Groq API key for LLM access
- Cohere API key for embeddings
- YouTube API key for video transcript extraction

Please ensure you have the necessary API keys before running the examples.

## Contributing

Feel free to contribute by:
- Adding new examples
- Improving existing implementations
- Fixing bugs
- Enhancing documentation

## License

This project is licensed under the MIT License - see the LICENSE file for details.
