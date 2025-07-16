# QueryDoc – AI-Powered PDF Q&A

QueryDoc is an AI-powered document analysis tool built with Streamlit and LangChain. It uses Retrieval-Augmented Generation (RAG) techniques and Google's Gemini model to answer questions about your uploaded PDFs.

## Features
- Upload and analyze multiple PDF files
- Ask questions and get context-aware answers
- Uses FAISS for fast document retrieval
- Powered by Google's Gemini AI

## Getting Started

### 1. Clone the Repository
```sh
# If you haven't already, clone your project
# git clone <your-repo-url>
cd QueryDoc
```

### 2. Set Up a Virtual Environment (Recommended)
```sh
# Create a virtual environment named 'venv'
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
# source venv/bin/activate
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

### 4. Run QueryDoc with Streamlit
```sh
streamlit run RAGBOT.py
```

- The app will open in your browser (usually at http://localhost:8501).
- Enter your own Google API key, or use the default provided in the app.
- Upload your PDF files and start asking questions!

## File Structure
```
QueryDoc/
├── RAGBOT.py           # Main Streamlit app
├── DocExtractor.ipynb  # Jupyter notebook for PDF extraction (optional)
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
├── ...                 # Your PDF files and outputs
```

## Notes
- Python 3.8+ is recommended.
- For best results, use your own Google Generative AI API key.
- All dependencies are listed in requirements.txt.

## License
MIT License
