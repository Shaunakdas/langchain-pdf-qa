# Langchain PDF QA (Chatbot)

This repository contains a Python application that enables you to load a PDF document and ask questions about its content using natural language. The application utilizes a Language Model (LLM) to generate responses specifically related to the PDF. Please note that the LLM will not answer questions unrelated to the document.

## Functionality

The application functions by reading the PDF file and dividing its text into smaller sections that can be processed by the LLM. It utilizes OpenAI embeddings to create vector representations of these sections. The application then identifies the sections that are semantically similar to the user's question and feeds those sections to the LLM to generate a response.

The GUI of the application is created using Streamlit, and the LLM is powered by Langchain.

## Installation

To install the repository, kindly clone it and install the necessary requirements by executing the following command:

```
pip install -r requirements.txt
```

Additionally, you will need to include your OpenAI API key in the `.env` file.

## Usage

To utilize the application, run the `app.py` file using the Streamlit CLI (after installing Streamlit) by executing the following command:

```
streamlit run app.py
```

## Contributing

This repository is solely intended for educational purposes and is not open to further contributions.