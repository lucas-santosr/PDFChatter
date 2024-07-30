# Basic Level PDF Chatter

## Overview

This project is a basic level PDF chatter that allows you to interact with your PDF documents. The tool uses Langchain and Pinecone for vector storage, making it a great starting point for anyone looking to explore the capabilities of these tools.

## Features

- Load PDFs from a directory using `PyPDFDirectoryLoader`.
- Split text using `RecursiveCharacterTextSplitter`.
- Embed text using `HuggingFaceEmbeddings`.
- Utilize `HuggingFaceHub` for language models.
- Store and retrieve vectors using `Pinecone`.
- Create an interactive chat interface using `ChatHuggingFace` and `RetrievalQA`.

## Technologies Used

- [Langchain](https://github.com/hwchase17/langchain)
  - `PyPDFDirectoryLoader`
  - `RecursiveCharacterTextSplitter`
  - `HuggingFaceEmbeddings`
  - `HuggingFaceHub`
  - `RetrievalQA`
  - `PromptTemplate`
- [Pinecone](https://www.pinecone.io/)
  - Vector storage and retrieval
- [HuggingFace](https://huggingface.co/)
  - `HuggingFaceEndpoint`
  - `ChatHuggingFace`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/pdf-chatter.git
    cd pdf-chatter
    ```

## Usage

1. Place your PDF files in a directory of your choice or the default Pdfs directory.
2. Run the cells in jupyter notebook and play around. Make sure to add your hugging face and pinecone API before use.

## Acknowledgements

A huge thank you to the documentation provided by Langchain and Pinecone. Their comprehensive guides were invaluable in bringing this project to life.
