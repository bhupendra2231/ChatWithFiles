# Chat with Multiple Files using Google's Generative AI (Gemini)

This project is a Streamlit application that allows you to upload multiple files (PDFs, Word documents, and text files) and ask questions related to the content of those files. The application uses Google's Generative AI (Gemini) model to find relevant information from the uploaded files and provide detailed answers to your questions.

## Features

- Upload multiple files (PDFs, Word documents, and text files)
- Ask questions related to the content of the uploaded files
- Get detailed answers from Google's Generative AI (Gemini) model
- Efficient similarity search and clustering of text using FAISS vector store

## Prerequisites

Before running the application, make sure you have the following prerequisites installed:

- Python (version 3.10 or higher)
- Google Cloud account with the Generative AI API enabled
- API key for Google's Generative AI API

## Installation

- Clone the repository:
  git clone https://github.com/your-username/ChatWithFiles.git
- Navigate to the project directory:
- Create a virtual environment (optional but recommended):
  conda create  -p venv
- Activate the virtual environment:
  conda activate ./venv
- Install the required packages:
  conda install -r requirements.txt
- Set up your Google API key as an environment variable:
  GOOGLE_API_KEY="your_api_key"

## Usage

- Run the Streamlit application: streamlit run app.py
- The application will open in your default web browser.
- Upload the files you want to ask questions about by clicking the "Upload your files(.pdf/.txt/.docx)" button in the sidebar.
- Once the files are uploaded and processed, enter your question in the text input field.
- The application will search for relevant information from the uploaded files and provide a detailed answer using Google's Generative AI (Gemini) model.
- You can ask multiple questions and get answers based on the uploaded files.


