**Document Processing with OpenAI's GPT-3**
This project demonstrates document processing using OpenAI's GPT-3 language model. 
It extracts text from PDFs and images, answers user queries using GPT-3, and saves the results to an Excel file.

**Features**
Extracts text from PDFs and images
Utilizes OpenAI's GPT-3 for generating answers to user queries
Concurrent processing for improved performance
Results saved to an Excel file for easy analysis

**Requirements**
Python 3.x
OpenAI API key
PyPDF2 (for PDF processing)
Tesseract OCR and pytesseract (for image processing)
pandas (for data handling)
openai (for accessing OpenAI's API)
pdfplumber (optional alternative for PDF processing)
Any necessary dependencies mentioned in the code comments

**Installation**
Clone the repository:

**bash**
Copy code
git clone https://github.com/your_username/your_repository.git
Install the required Python packages:

**bash**
Copy code
pip install -r requirements.txt
Set up your OpenAI API key by replacing 'key' with your actual API key.

**Usage**
Place your PDFs and images in the specified folder (C:/Users/Your-Name/MF).

Run the Python script:

bash
Copy code
python document_processing.py
Wait for the script to finish processing. It will extract text from documents, generate answers to user queries, and save the results to an Excel file (docqa_results.xlsx).

**Configuration**
Adjust the folder path (documents_folder) to point to your document directory.
Modify the user queries (user_queries) as needed.
Tune the temperature and max_tokens parameters for GPT-3 based on your requirements.

**Contributors**
Mohit Kumar - Creator
License
This project is licensed under the MIT License - see the LICENSE file for details.

**Acknowledgments**
OpenAI for providing access to the GPT-3 API
PyPDF2, pytesseract, pandas, and other open-source libraries used in this project
