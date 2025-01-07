#🖋️ AI-Powered Table Analysis & Summarization Tool
Welcome to the AI-Powered Table Analysis & Summarization Tool! This project helps you analyze tables from PDFs with ease. Upload a PDF, extract its tables, and get concise AI-generated summaries. Built with Streamlit, this application offers a seamless experience for processing complex financial data.

##🌟 Key Features
📂 Upload PDF Documents: Easily upload PDFs through an intuitive interface.
📖 Preview PDF Content: View the content of uploaded PDFs in-app.
📊 Extract Tables: Automatically detect and extract tables from uploaded PDFs.
✍️ AI Summarization: Generate clear, meaningful summaries for the extracted tables.
🧹 Cleanup: Ensures all temporary files are securely deleted post-processing.
🛠️ Installation Guide
Follow these steps to set up the project on your system:

##1️⃣ Clone the Repository
bash
Copy code
git clone https://github.com/ERAM-FATIMA/Analysing_Income_Statement_Balance_Sh-eet_Table_with_LLM.git
cd Analysing_Income_Statement_Balance_Sh-eet_Table_with_LLM
##2️⃣ Set Up a Virtual Environment (Recommended)
Create a virtual environment to isolate dependencies:

bash
Copy code
python -m venv venv
Activate the Virtual Environment:
Windows:
bash
Copy code
venv\Scripts\activate
macOS/Linux:
bash
Copy code
source venv/bin/activate
##3️⃣ Install Dependencies
Install the required Python libraries:

bash
Copy code
pip install -r requirements.txt
##🖥️ How to Use
###1️⃣ Run the Application
Start the Streamlit app using:

bash
Copy code
streamlit run app.py
###2️⃣ Upload and Process PDFs
Use the file uploader to select your PDF.
Preview the content, and the app will automatically extract tables.
Click on the summarization feature to get detailed summaries.
##📂 Project Structure
plaintext
Copy code
.
├── app.py                # Main Streamlit application
├── requirements.txt      # List of dependencies
├── utils/                # Folder containing utility scripts
│   ├── table_extraction.py  # PDF table extraction logic
│   └── summarization.py     # AI summarization functionality
├── assets/               # (Optional) Folder for icons or additional files
└── README.md             # This documentation file
##🧰 Dependencies
This project relies on the following Python libraries:

Streamlit: For creating the web interface.
Pandas: For data manipulation and table handling.
PyPDF2: For extracting tables from PDFs.
Mistralai: For AI-powered summarization (ensure proper setup).
Install them via:

bash
Copy code
pip install streamlit pandas PyPDF2 mistralai
##🌐 Useful Links
GitHub Profile: [Eram's GitHub](https://github.com/ERAM-FATIMA)
Repository: [Project Repository](https://github.com/ERAM-FATIMA/Analysing_Income_Statement_Balance_Sh-eet_Table_with_LLM)
##📧 Contact
For any inquiries, feel free to reach out to me on GitHub:
GitHub Profile

