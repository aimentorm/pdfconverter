# pdfconverter
Create an AI tool to convert pdf file into word & Powerpoint; word file to powerpoint presentation using python programming language, stable diffusion and a github repository
PDF Converter
This is a Python-based AI tool that converts PDF files into:

Word Documents (.docx)
PowerPoint Presentations (.pptx)
Built with the latest Python version, this tool is optimized for macOS and uses pip3 for package management.

Features
PDF to Word (.docx): Extracts text and saves it as a Word document.
PDF to PowerPoint (.pptx): Converts each line of text into a slide.
Supports Multiple PDF Layouts: Works with PDFs containing plain text, multiple pages, and basic formatting.
Technologies Used
Python (Latest Version)
Libraries:
PyMuPDF (fitz) - Efficient PDF text extraction
python-docx - To generate Word documents
python-pptx - To create PowerPoint presentations
Prerequisites
macOS with Python and pip3 installed.
To check your Python and pip versions, run:
bash
Copy
Edit
python3 --version
pip3 --version
Installation
Clone the Repository
bash
Copy
Edit
git clone https://github.com/aimentorm/pdfconverter.git
cd pdfconverter
Create a Virtual Environment (Recommended)
bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate
Install Required Libraries
bash
Copy
Edit
pip3 install -r requirements.txt
Required Packages in requirements.txt
Copy
Edit
pdfminer.six
python-pptx
python-docx
PyMuPDF
Usage
Run the Script
bash
Copy
Edit
python3 main.py
Provide Input When Prompted
Enter the path to the PDF file
Specify the output file names for .docx and .pptx
Example:

mathematica
Copy
Edit
Enter the path to the PDF file: /Users/username/Documents/sample.pdf
Enter the desired output .docx file name: output_document.docx
Enter the desired output .pptx file name: output_presentation.pptx
Project Structure
pgsql
Copy
Edit
pdf_converter/
├── main.py               # Main script for PDF conversion
├── requirements.txt      # Required Python libraries
└── README.md              # Project documentation
Example
plaintext
Copy
Edit
Enter the path to the PDF file: /Users/mentormaih/Documents/report.pdf
Enter the desired output .docx file name: report_output.docx
Enter the desired output .pptx file name: report_slides.pptx
Best Practices & Tips
Error Handling: The script checks if the PDF file exists before processing.
Modular Functions: Each conversion is handled by a separate function.
Cross-Platform Compatibility: While optimized for macOS, it should work on other OS with minor adjustments.
Troubleshooting
Permission Denied: Ensure the terminal has access to the folder containing the PDF.
File Not Found: Double-check the file path or place the PDF in the same folder as the script.
Contributing
Contributions are welcome! Please follow these steps:

Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a pull request
License
This project is licensed under the MIT License - see the LICENSE file for details.

