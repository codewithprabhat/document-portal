# Document Portal

A document analysis and chat application built with Python, LangChain, and modern AI models.

## Project Overview

This project is a document portal that enables users to upload, analyze, and chat with documents using advanced AI models. The application supports multiple document types and provides intelligent document comparison and multi-document chat capabilities.

## Technology Stack

- **Python**: 3.10
- **Environment Management**: Conda
- **LLM Model**: Groq (for chat and reasoning)
- **Embedding Model**: ChatGOT (for document embeddings)
- **Framework**: LangChain
- **Web Interface**: Streamlit
- **Vector Database**: Chroma (for document storage and retrieval)

## Project Structure

```
document-portal/
├── app.py                          # Main Flask application
├── streamlit_ui.py                 # Streamlit web interface
├── requirements.txt                # Python dependencies
├── setup.py                       # Package setup configuration
├── config/
│   └── config.yaml                # Application configuration
├── src/                           # Source code modules
│   ├── docanalysier/             # Document analysis functionality
│   ├── doccompare/               # Document comparison features
│   ├── singledocchat/           # Single document chat
│   └── multidocchat/            # Multi-document chat
├── utils/                        # Utility functions
│   └── llm_utils.py             # LLM helper functions
├── logger/                       # Logging configuration
├── exception/                     # Custom exception handling
├── prompt/                       # Prompt templates
├── static/                       # Static web assets
├── templates/                    # HTML templates
├── notebook/                     # Jupyter notebooks for experiments
│   └── experiments.ipynb        # Development and testing notebook
└── env/                         # Conda virtual environment
```

## Work Completed

### 1. Project Structure Setup
- ✅ Created modular project structure with separate components
- ✅ Set up conda virtual environment with Python 3.10
- ✅ Configured package dependencies and requirements
- ✅ Implemented proper logging and exception handling

### 2. Core Modules Development
- ✅ **Document Analysis Module** (`src/docanalysier/`): Document processing and analysis
- ✅ **Document Comparison Module** (`src/doccompare/`): Compare multiple documents
- ✅ **Single Document Chat** (`src/singledocchat/`): Chat with individual documents
- ✅ **Multi-Document Chat** (`src/multidocchat/`): Chat across multiple documents

### 3. AI Model Integration
- ✅ **Groq LLM Integration**: Configured Groq for chat and reasoning tasks
- ✅ **ChatGOT Embeddings**: Set up ChatGOT for document embedding generation
- ✅ **LangChain Integration**: Implemented LangChain framework for AI workflows

### 4. Web Interface
- ✅ **Flask Backend**: Set up Flask application for API endpoints
- ✅ **Static Assets**: Configured CSS and HTML templates

### 5. Development Environment
- ✅ **Jupyter Notebooks**: Set up experimentation environment
- ✅ **Configuration Management**: YAML-based configuration system
- ✅ **Logging System**: Comprehensive logging for debugging and monitoring

## Current Status

The project is in active development with the core structure and basic functionality implemented. The team is working on:

- Document upload and processing workflows
- Vector database integration for document storage
- Chat interface optimization
- Performance testing and optimization
- **RAG Pipeline**: Worked on the RAG pipeline implementation in Jupyter notebook

## Today's Class Work

**Added entire RAG pipeline on experiment.ipynb**

- Implemented complete RAG (Retrieval-Augmented Generation) pipeline in the experiments notebook
- Developed document processing and retrieval mechanisms
- Integrated vector embeddings for document similarity search
- Created chat interface for document interaction
- Tested and validated RAG pipeline functionality

## Getting Started

### Prerequisites
- Python 3.10
- Conda package manager
- Groq API key
- ChatGOT API credentials

### Installation

1. Clone the repository
2. Create conda environment:
   ```bash
   conda create -n document-portal python=3.10
   conda activate document-portal
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Configure environment variables:
   ```bash
   export GROQ_API_KEY="your-groq-api-key"
   export CHATGOT_API_KEY="your-chatgot-api-key"
   ```

## Contributing

This is a learning project focused on exploring document AI capabilities using modern frameworks and models.

## License

This project is for educational and learning purposes.
