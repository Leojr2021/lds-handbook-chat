# RAG Project

This project showcases a Retrieval-Augmented Generation (RAG) system using various tools and libraries. The goal is to enhance document processing and interaction using advanced language models and vector databases.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Dependecies

Install the required dependencies using the following commands:

-   **pip install python-dotenv==1.0.1**
-   **pip install langchain-community==0.2.3**
-   **pip install langchain-openai==0.1.8**
-   **pip install langchain==0.2.2**
-   **pip install onnxruntime==1.17.1**
-   **pip install chromadb==0.5.0**
-   **pip install openai==1.31.1**
-   **pip install tiktoken==0.7.0**
-   **pip install --quiet gradio**
-   **pip install "unstructured[md]"**


Usage
-----

Follow these steps to use the RAG system:

1.  **Set the OpenAI API Key**

    Make sure you have your OpenAI API key set in your environment. You can do this by adding the key to a `.env` file or setting it directly in the notebook.

2.  **Load the Notebook**

    Open the Jupyter notebook `Handbook_RAG.ipynb` and run the cells sequentially.

3.  **Document Loading and Processing**

    The notebook includes code to load documents, split text, and prepare data for retrieval and generation.

4.  **Run the RAG System**

    Interact with the RAG system using the provided Gradio interface for real-time querying and response generation.

Features
--------

-   **Document Loading**: Load and preprocess documents for efficient retrieval.
-   **Text Splitting**: Use recursive character text splitting for handling large documents.
-   **Embeddings and Vector Stores**: Utilize OpenAI embeddings and Chroma vector stores for efficient querying.
-   **Interactive Interface**: Use Gradio for an interactive web-based interface to interact with the RAG system.

Contributing
------------

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature`).
3.  Commit your changes (`git commit -am 'Add new feature'`).
4.  Push to the branch (`git push origin feature/your-feature`).
5.  Create a new Pull Request.

License
-------

This project is licensed under the MIT License. See the LICENSE file for more details.