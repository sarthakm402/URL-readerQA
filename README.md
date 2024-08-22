# LangChain Flask Application with ChatGoogleGenerativeAI

This Flask application demonstrates how to integrate LangChain with the `ChatGoogleGenerativeAI` model to answer user queries based on content fetched from a URL. The app uses `UnstructuredURLLoader` to load content, processes the text using `RecursiveCharacterTextSplitter`, and generates responses with `LLMChain`.

## Features

- **Fetch Content from URL**: Retrieves and processes content from a given URL.
- **Text Chunking**: Divides content into manageable chunks using customizable separators.
- **Generate Responses**: Uses `ChatGoogleGenerativeAI` to provide answers based on the processed content.

## Prerequisites

- Python 3.7 or later
- Flask
- LangChain
- Transformers library
- `langchain_google_genai` library

1. **Clone the Repository**

   ```bash
   git clone https://github.com/sarthakm402/URL-readerQA.git



2. Create a requirements.txt file with the following content:


- Flask
- LangChain
- Transformers
- API

## Usage
- Start the Flask Application

  ```sh
  python app.py
  ```
- Access the Application

   Open your web browser and navigate to http://127.0.0.1:5000(local host).

- Submit Your Query

   URL: Enter the URL of the content you want to analyze.
   Text: Enter the query related to the content.
   Click "Submit" to get the generated response based on the   content from the URL.

## Error Handling
- Initialization Errors: If there’s an issue initializing the ChatGoogleGenerativeAI model, an error message is returned.\

- Response Generation Errors: If there’s an error during response generation, an error message is returned.

## Contributing

We welcome contributions to improve the project. To contribute:

- Fork the repository.

- Create a new branch for your changes.

- Submit a pull request with a detailed description of your changes.
