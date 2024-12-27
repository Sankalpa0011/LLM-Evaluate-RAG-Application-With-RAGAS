
# LLM Evaluate RAG Application With RAGAS

This repository contains a Jupyter notebook that demonstrates how to evaluate a Retrieval-Augmented Generation (RAG) application using the RAGAS (RAG Assessment) framework. The notebook is designed to help you understand the process of setting up a RAG model, loading and processing documents, creating a vector store, and evaluating the performance of the RAG application.

## Notebook Overview

The notebook is divided into several sections:

1. **Install Necessary Libraries**: Install the required Python packages.
2. **Initialize OpenAI LLM**: Set up the OpenAI language model.
3. **Initialize Embedding Model**: Initialize the embedding model for vector representations.
4. **Load PDF Document**: Load and process a PDF document.
5. **Split Documents into Chunks**: Split the document into smaller chunks for processing.
6. **Create Vector Store and Retriever**: Create a vector store from the document chunks and set up a retriever.
7. **Define Prompt Template**: Define the template for generating responses using the RAG model.
8. **Create Retrieval-Augmented Generation (RAG) Chain**: Set up the RAG chain for generating responses.
9. **Invoke RAG Chain with Example Questions**: Test the RAG chain with example questions.
10. **Evaluate RAG Application**: Evaluate the performance of the RAG application using test data.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: `ragas`, `langchain`, `langchain-chroma`, `langchain-openai`, `langchain-community`, `datasets`, `pypdf`

## Setup Instructions

1. Clone the repository:
   ```sh
   git clone https://github.com/Sankalpa0011/LLM-Evaluate-RAG-Application-With-RAGAS.git
   cd LLM-Evaluate-RAG-Application-With-RAGAS
Install the required Python packages:

pip install -r requirements.txt
Open the Jupyter notebook:

jupyter notebook LLM_Evaluate_RAG_Application_With_RAGAS.ipynb
Follow the instructions in the notebook to execute each cell and understand the process.

Usage
Evaluating RAG Application: The notebook provides a step-by-step guide to evaluate a RAG application. You can use the provided example questions to test the RAG chain and assess its performance.
Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.
