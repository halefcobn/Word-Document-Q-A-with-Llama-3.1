# Word-Document-Q-A-with-Llama-3.1
Word Document Q&amp;A with Llama 3.1

This project allows you to interact with Word documents using the Llama 3.1 language model. You can ask questions about the content of a Word document, and the model will provide relevant answers based on the document's text and the conversation history.

# Features

Read and extract text from Word (.docx) documents: The program reads the content of a Word document and extracts the text for analysis.
Ask questions about the document content: Users can ask questions about the document's content, and the model will provide answers.
Maintain conversation history: The program maintains the conversation history to provide context-aware responses.
Utilize the Llama 3.1 model: The project uses the Llama 3.1 language model for generating responses, ensuring high-quality and relevant answers.

# Llama 3.1 Features

Advanced Natural Language Understanding: Llama 3.1 is designed to understand and process natural language with high accuracy.
Context-Aware Responses: The model maintains the context of the conversation, allowing it to provide more accurate and relevant answers.
High-Quality Text Generation: Llama 3.1 generates coherent and contextually appropriate responses, making it suitable for a wide range of applications.
## Requirements
Python 3.7+
python-docx
langchain_ollama
langchain_core

# Installation

## Clone the repository:

Copy code:
git clone https://github.com/halefcobn/Word-Document-Q-A-with-Llama-3.1.git
cd Word-Document-Q-A-with-Llama-3.1
Create and activate a virtual environment (optional but recommended):

Copy code:
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Create a .env file in the root directory of the project.

Copy code:
from word_document_qa import WORDDocument

if __name__ == "__main__":
    word_model = WORDDocument()
    response = word_model.get_docx_response(word_file_path="path/to/your/document.docx", question="What is the document about?")
    print(response)
Run the script:

python your_script.py
