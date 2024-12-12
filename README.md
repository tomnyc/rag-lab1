# Introduction to Retrieval Augmented Generation

This repository will introduce you to Retrieval Augmented Generation (RAG) with
easy to use examples that you can build upon. The examples use Python with
Jupyter Notebooks and CSV files. The vector database uses the Qdrant database
which can run in-memory.

## Setup your environment

This example has been run in Google Colab.


Here is a summary of what this repository will use:

1. [Qdrant](https://github.com/qdrant/qdrant) for the vector database. We will use an in-memory database for the examples
2. [OpenAI's Python API](https://pypi.org/project/openai/) to connect to the LLM after retrieving the vectors response from Qdrant
3. Sentence Transformers to create the embeddings with minimal effort

