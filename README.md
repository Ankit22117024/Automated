A powerful Streamlit application that intelligently extracts structured metadata and generates a concise summary from uploaded documents (PDF, DOCX, or TXT). It utilizes Mistral AI for summarization and KeyBERT for keyword extraction, delivering high-quality insights instantly.

🔗 Live Demo: Check it out here

🚀 Key Features
📁 Supports document uploads: PDF, DOCX, and TXT

🧠 Summarizes content in chunks using Mistral-powered LLM

🔍 Automatically extracts key metadata:

Document title

Author name

Creation or publishing date

File type

Most relevant keywords

📝 Clean, well-formatted summary output

💾 Option to download the final summary with a single click

💡 Technology Stack
Streamlit – Rapid frontend development

Mistral API – Large language model for summarization

KeyBERT – Keyword extraction using BERT

pdfplumber – PDF text parser

python-docx – Word document parser

LangChain – Text chunking and processing pipeline

🛠️ Running the App Locally
Clone the repository:

cd metadata-generation
Install dependencies:


pip install -r requirements.txt
Configure API keys:

Set up required API credentials for Mistral and any other services

Launch the app:

streamlit run app.py
Made with ❤️ by Ankit Choudhary
