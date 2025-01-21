# Legal AI Research Tool

This Python-based tool automates legal research tasks by:
- **Searching and analyzing legal PDFs.**
- **Querying online databases** such as Cornell Law for Supreme Court case text.
- **Providing modular design** for integration with advanced AI technologies like Large Language Models (LLMs).

## Features
- **PDF Search**:
  - Upload multiple PDFs.
  - Search for words or phrases within the documents.
  - Extract relevant context around matches.
- **Online Case Search**:
  - Query Cornell Law's Supreme Court case database for text matching your search term.
- **Contextual Results**:
  - Extract and display matches with context for easy legal analysis.

---

## Getting Started

Follow these steps to set up and run the project in Python.

### Prerequisites
- Python 3.7 or higher installed on your system.
- Required Python libraries:
  - `PyPDF2`
  - `requests`
  - `beautifulsoup4`

### Installation

1. **Download the Repository**:
   - Save all the project files, including the `main.py` file, the `requirements.txt` file, and the `pdfs/` folder.

2. **Install Dependencies**:
   - Open a Python environment (e.g., Jupyter Notebook, Anaconda, or a terminal with Python).
   - Install the required libraries by running this Python command:
     ```python
     import os
     os.system('pip install -r requirements.txt')
     ```

3. **Run the Program**:
   - Run the main script in Python:
     ```python
     import main
     ```

---

## Usage

### 1. PDF Search:
- When running the program, you will be prompted to upload your legal PDFs.
- Enter a word or phrase to search.
- The tool will return contextual matches from your PDFs.

### 2. Online Case Search:
- Select the "Search Cornell Law" option from the menu.
- Enter your search term (e.g., "privacy" or "surveillance").
- The program will fetch results from Cornell Law's Supreme Court database.

### Example Search:
```python
Search Options:
1. Search for a word or phrase in PDFs
2. Search Cornell Law Supreme Court cases
3. Exit
Enter your choice (1, 2, or 3): 2
Enter the search term for Cornell Law Supreme Court cases: privacy
```

**Output:**
```python
Results for 'privacy' in Cornell Law:
1. ... privacy of individuals under the Fourth Amendment ...
2. ... constitutional right to privacy upheld in this case ...
```

---

## Included Files

- **PDFs**: Example legal documents are included in the `pdfs/` folder for testing purposes:
  - `constitution.pdf`
  - `FISA.pdf`

- **Online Databases**:
  - **Cornell Law Supreme Court case search**: [Visit Cornell Law](https://www.law.cornell.edu/supremecourt/text).

---

## Contributing

Contributions are welcome! If you'd like to contribute:
1. Download the repository files.
2. Add your modifications to the `main.py` script.
3. Share your improvements.

