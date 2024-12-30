## LLM-Powered Chatbot with RAG using LangChain and Oracle Database 23c AI  

This project implements an AI-powered chatbot using Retrieval-Augmented Generation (RAG) with LangChain and Oracle Database 23c AI Vector Search. The chatbot leverages advanced natural language processing techniques to provide intelligent responses based on document retrieval and generation.

## Features
- **Document Processing Pipeline**: Utilizes PyPDF2 for PDF parsing and CharacterTextSplitter for efficient text chunking.
- **Vector Embedding**: Implements OCIGenAIEmbeddings for converting text into vector representations.
- **Similarity Search**: Integrates Oracle Vector Store (OracleVS) for fast and accurate similarity search.
- **Language Model Integration**: Leverages Cohere's LLM API for natural language understanding and response generation.
- **RAG Workflow**: Optimized Retrieval-Augmented Generation process for enhanced question-answering capabilities.
- **Environment Management**: Implements secure environment variable handling for API keys and sensitive information.
- **Database Connectivity**: Utilizes oracledb for seamless interaction with Oracle Database 23c AI.

## Installation
1. Clone the repository:
    -  git clone https://github.com/yourusername/llm-powered-chatbot.git
    -  cd llm-powered-chatbot
2. Inst'all required dependencies:
    -  pip install -r requirements.txt
3. Set up environment variables:
   - Create a `.env` file in the project root and add the following:
     ```
     ORACLE_CONNECTION_STRING=your_connection_string
     COHERE_API_KEY=your_cohere_api_key
     ```

## Usage
1. Prepare your documents by placing PDF files in the `documents` directory.
2. Run the document processing script:
   - python process_documents.py
3. Start the chatbot:
   - python chatbot.py
4. Interact with the chatbot by typing your questions in the console.

## Project Structure
llm-powered-chatbot/

├── chatbot.py

├── process_documents.py

├── requirements.txt

├── .env

├── documents/

└── README.md

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments
- LangChain for providing the framework for building LLM applications.
- Oracle for their Database 23c AI Vector Search capabilities.
- Cohere for their powerful LLM API.



