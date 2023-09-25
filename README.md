# LLM-powered PDF Chatbot 

This is a Streamlit-based PDF Chatbot powered by OpenAI's Language Models. The chatbot allows users to upload PDF files, extract text content, and ask natural language questions about the PDF content. Key project components include:

**PDF Text Extraction**: Utilized the PyPDF2 library to extract text from uploaded PDF files, enabling easy access to the document's content.

**Text Splitting**: Implemented a custom text splitter to break down the extracted text into manageable chunks for efficient processing.

**Embeddings and Vector Stores**: Generated embeddings using OpenAI's Language Models and created a Vector Store using FAISS for efficient text similarity search.

**Question Answering**: Integrated OpenAI's LLMs to provide accurate answers to user queries about the PDF content.

**Persistence**: Implemented data persistence by storing generated embeddings to accelerate future queries.

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

