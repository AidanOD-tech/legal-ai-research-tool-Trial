# Legal AI Research Tool

This Python-based tool automates legal research tasks by:
- **Searching and analysing legal PDFs that have been provided.**
- **Querying online databases** such as Cornell Law for Supreme Court case text by case name.
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
- **Scalable Design**:
  - Modular functions for potential integration with AI-driven tools like OpenAI's GPT.

---

## Getting Started

Follow these steps to set up and run the project.

### Prerequisites
- Python 3.7 or higher installed on your system.
- Required Python libraries:
  - `PyPDF2`
  - `requests`
  - `beautifulsoup4`

### Installation

1. **Clone this repository**:
   - Open a terminal or command prompt and run the following:
     ```
     git clone https://github.com/yourusername/legal-ai-research-tool.git
     cd legal-ai-research-tool
     ```

2. **Install dependencies**:
   - Install the required Python libraries using `pip`:
     ```
     pip install -r requirements.txt
     ```

3. **Run the tool**:
   - Start the program by running:
     ```
     python main.py
     ```

---

## Usage

1. **PDF Search**:
   - Run the program and upload your legal PDFs when prompted.
   - Enter a word or phrase to search.
   - The tool will return contextual matches from your PDFs.

2. **Online Case Search**:
   - Select the "Search Cornell Law" option from the menu.
   - Enter your search term (e.g., "privacy" or "surveillance").
   - View results, including relevant text and links to Cornell Law's case database.

3. **Example Usage**:
   ```
   Search Options:
   1. Search for a word or phrase in PDFs
   2. Search Cornell Law Supreme Court cases
   3. Exit
   Enter your choice (1, 2, or 3): 2
   Enter the search term for Cornell Law Supreme Court cases: privacy
   ```

   **Output**:
   ```
   Results for 'privacy' in Cornell Law:
   1. ... privacy of individuals under the Fourth Amendment ...
   2. ... constitutional right to privacy upheld in this case ...
   ```

---

## Included Files

- **PDFs**: The repository includes example legal PDFs in the `pdfs/` folder. These files can be used to test the tool. 
  - Example files:
    - `constitution.pdf`
    - `example_legal_doc.pdf`
- **Online Databases**:
  - **Cornell Law Supreme Court case search**: [Visit Cornell Law](https://www.law.cornell.edu/supremecourt/text).

### How to Use the PDFs
1. Run the program (`python main.py`).
2. When prompted to upload PDFs, you can choose files from your system or use the example PDFs provided in the `pdfs/` folder.
3. Search for words or phrases within the uploaded PDFs to see contextual matches.


---

## Future Plans

- **Integrate LLMs**:
  - Use OpenAI GPT models for summarising search results and advanced legal analysis.
- **Add More Databases**:
  - Extend support to include legal platforms like CaseText, LexisNexis and Westlaw.
- **Build a Web Interface**:
  - Develop a user-friendly web interface using Flask or Streamlit.

---

## Contributing

Contributions are welcome! Please follow these steps to contribute:
1. Fork this repository.
2. Create a new branch for your feature or bug fix:
   ```
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```
   git commit -m "Add your message here"
   ```
4. Push to your branch:
   ```
   git push origin feature/your-feature-name
   ```
5. Submit a pull request for review.

---



