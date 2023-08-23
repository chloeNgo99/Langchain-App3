# LangChain PDF App

This LangChain PDF App is a simple web application that allows users to upload a PDF file and interact 
with a language model to ask questions related to the content of the PDF. The application uses Streamlit, 
a Python library for creating interactive web apps, and leverages the LangChain framework for natural 
language processing tasks.

## Getting Started

To get started with the LangChain PDF App, you'll need to set up the environment and install the required dependencies. 
Follow the steps below:

1. Install the required Python packages using the following command:

```bash
pip install -r requirements.txt
```

2. Ensure you have a valid API key from OpenAI to use their language model. Store the API key in a `.env` file in the 
root directory of the project.

## Usage

To run the LangChain PDF App, execute the following command:

```bash
streamlit run pdf_chat.py
```

The web app will launch in your browser, and you'll see a page with a file uploader prompting you to upload a PDF file. 
Once you upload a PDF, the app will extract the text content and split it into smaller chunks.

You can then interact with the language model by typing questions in the input field provided. When you submit a question, 
the app will use the language model to find the relevant information in the PDF and provide an answer.

## Features

- Upload and process PDF files.
- Interact with a language model to ask questions related to the PDF content.
- View the chat history with questions and corresponding answers.

## Note

The LangChain PDF App is a demonstration of how to use the LangChain framework for a specific task. It is a simplified 
example and can be further extended and customized based on specific use cases.

Feel free to explore and experiment with the app, and if you have any questions or suggestions, please feel free to reach out.

Happy exploring!

Chloe