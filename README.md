# PDF Text and Table Extractor

## Overview
This project extracts text and tables from a given PDF file and saves the structured data in a JSON format. It uses:
- `pdfminer.six` for text extraction
- `pdfplumber` for table extraction

## Features
- Extracts plain text from PDFs
- Extracts tables and stores them as lists
- Saves extracted data in a structured JSON file
- Easy-to-use command-line interface

## Installation
Make sure you have Python installed, then install the required dependencies:
```sh
pip install pdfminer.six pdfplumber
```

## Usage
Run the script and provide the path to a PDF file:
```sh
python script.py
```
Follow the prompt to enter the PDF file path. The extracted data will be saved as `output.json`.

## Output Format
The extracted data is stored in a JSON file with the following structure:
```json
{
    "Headers": "Extracted text from the PDF",
    "List_items": [
        ["Table Row 1, Column 1", "Table Row 1, Column 2"],
        ["Table Row 2, Column 1", "Table Row 2, Column 2"]
    ]
}
```

## Contributing
Feel free to fork this repository and make improvements. Pull requests are welcome!

## License
This project is licensed under the MIT License.

