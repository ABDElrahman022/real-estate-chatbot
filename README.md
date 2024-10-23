# RAG Real Estate Chatbot

Welcome to the **RAG Real Estate Chatbot** project. This chatbot is designed to interact with users and help them find suitable real estate options based on their needs and preferences. The chatbot is built using Retrieval-Augmented Generation (RAG) techniques to provide contextual answers from real estate documents.

## Table of Contents

- [Installation](#installation)
- [Project Structure](#project-structure)
- [Environment Setup](#environment-setup)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)
- [Team Members](#team-members)

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/ABDElrahman022/real-estate-chatbot.git
   cd real-estate-chatbot
   ```
2. **Set up a virtual environment**:

    ```bash
    conda create -n rag-realstate python==3.10.12
    conda activate rag-realstate
    ```
3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
## Project Structure
    ```bash
     RAG REAL STATE/
    │
    ├── .env                            # Environment file storing API keys
    ├── .envExample                    # Example environment file
    ├── .gitignore                     # Files to be ignored by Git
    ├── frontend.py                    # Additional frontend code (if any)
    ├── main.py                        # Main application script
    ├── README.md                      # Project documentation
    ├── real-estate-chatbot-modified.txt # Document containing real estate information
    ├── requirements.txt                # Requirements file for dependencies
    └── __pycache__/                   # Auto-generated folder for Python cache
    ```
## Environment Setup
1. Create a `.env` file in the root directory and add the following variables:
    ```bash
    PINECONE_API_KEY=your-pinecone-api-key
    HF_KEY_API=your-huggingface-api-key
    ```
2. You can refer to `.envExample` for the structure of environment variables.
## Usage
1. **Run the chatbot**:
    ```bash
    streamlit run frontend.py
    ```

2. Open your web browser and go to the local address provided by Streamlit, such as http://localhost:8501/.

3. The chatbot will greet you and ask questions about your real estate preferences. Simply interact with the chatbot to get relevant information based on your needs.

## Acknowledgements
This project uses the following frameworks and services:

- **LangChain** for orchestrating document-based context retrieval and chatbot responses.
- **Pinecone** for vector storage and retrieval.
- **Streamlit** for the interactive web-based front end.
## Team Members
- Abelrahman Mohamed
- Seif Elsayed
- Ahmed Alaa
- Mostafa Hamada
- Ahmed Saad
