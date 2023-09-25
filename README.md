# LLM-powered PDF Chatbot 

This is a Streamlit-based PDF Chatbot powered by OpenAI's Language Models.

## Overview

This project allows you to upload a PDF file, extract text from it, and then use OpenAI's language models to answer questions about the content of the PDF.

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/shaadclt/LLM-powered-PDF-Chatbot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd LLM-powered-PDF-Chatbot
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file and set your environment variables.

   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   ```

5. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

## Usage

1. Upload a PDF file using the "Upload your PDF" button.

2. Ask questions about the PDF file using the text input field.

3. The chatbot will use OpenAI's models to answer your questions based on the PDF content.

## Embeddings and Vector Store

The PDF text is split into chunks, and embeddings are generated using OpenAI's model. These embeddings are stored in a Vector Store for efficient similarity search.

## Acknowledgments

- [Streamlit](https://streamlit.io/) for creating an easy-to-use web app framework.
- [OpenAI](https://openai.com/) for providing powerful language models.

## License

This project is licensed under the [MIT License](LICENSE).

