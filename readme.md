# Chat with Multiple PDF using Gemini

## Overview

This project is a simple web application built with Streamlit that allows users to engage in a chat conversation with multiple PDF files using the Gemini model. The application processes the PDFs, generates embeddings, and provides users with the ability to ask questions related to the content of the PDFs.

## Features

- **PDF Processing:** The application can read text content from multiple PDF files.
- **Embeddings:** Google Generative AI embeddings are used to convert text chunks into vector representations.
- **Conversational Chain:** Utilizes a conversational chain with the Gemini model for generating responses based on user questions.
- **User Interface:** The Streamlit web interface provides an easy-to-use platform for users to upload PDF files, ask questions, and receive responses.

## Getting Started

### Prerequisites

- Python 3.x
- Install required libraries: `streamlit`, `PyPDF2`, `langchain`, `langchain_google_genai`, `google`, `dotenv`
- Obtain a Google API key and set it in a `.env` file.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo