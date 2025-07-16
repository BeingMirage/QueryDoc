# QueryDoc – Intelligent document querying with RAG.

An AI-powered document analysis tool built with Streamlit and LangChain. This project uses Retrieval-Augmented Generation (RAG) techniques to process and extract meaningful insights from PDFs, leveraging Google's Gemini-Pro model.

## Features

- **Upload PDFs**: Supports multiple PDF uploads for content extraction.
- **Text Chunking**: Splits large documents into manageable chunks using `RecursiveCharacterTextSplitter`.
- **Vector Store**: Uses FAISS to store document embeddings for fast retrieval.
- **AI-Powered Q&A**: Ask questions related to uploaded documents and get context-aware responses.
- **Document Extraction Notebook**: `DocExtractor.ipynb` provides an interactive Jupyter Notebook for document text extraction and preprocessing.

## Usage

### Running RAGBOT

1. **Set up your Google API Key**:  
   - Obtain a Google Generative AI API key from [Google AI](https://ai.google.com/).
2. **Run the Streamlit app**:
   ```sh
   streamlit run RAGBOT.py
   ```
3. **Upload PDFs & Ask Questions**:
   - Upload your documents through the sidebar.
   - Once processed, ask questions related to your documents.

### Using DocExtractor

1. Open `DocExtractor.ipynb` in Jupyter Notebook:
   ```sh
   jupyter notebook DocExtractor.ipynb
   ```
2. Run each cell to extract and preprocess text from PDFs.
3. Modify text processing steps as needed for your specific use case.

## File Structure

```
📂 ragbot-doc-extractor
├── RAGBOT.py                # Streamlit-based chatbot for document analysis
├── DocExtractor.ipynb       # Jupyter Notebook for document extraction
├── requirements.txt         # Dependencies list
└── README.md                # Project documentation
```

## Dependencies

- Python 3.8+
- `streamlit`
- `PyPDF2`
- `langchain`
- `FAISS`
- `google-generativeai`
- `jupyter`
- `langchain-community`

Install dependencies using:
```sh
pip install -r RAGrequirements.txt
```

## Contributing
Feel free to open issues or submit pull requests for improvements.

## License
This project is licensed under the MIT License.

---

Enjoy exploring AI-powered document analysis! 🚀
