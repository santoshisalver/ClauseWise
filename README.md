⚖️ ClauseWise — AI Legal Document Analyzer

ClauseWise is an AI-powered platform for analyzing legal documents with speed and accuracy. It converts dense legal text into plain English, extracts key entities, classifies documents, and enables powerful search and bulk processing. Built with a FastAPI backend and a Streamlit frontend, ClauseWise helps lawyers, businesses, and individuals quickly understand and manage contracts.

🏆 Hackathon Achievement

ClauseWise was developed as part of the Cognitive Gen-AI Hackathon 2025, where it secured 1st Position among 104 teams, along with a cash prize.  
The hackathon was organized by GNITS IEEE & IETE in collaboration with SmartBridge.

The journey began with a 3-day Bootcamp on IBM Granite and NASSCOM AI platforms, which provided the foundation for building this solution.

🚀 Core Features

AI-Powered Document Insights  
Simplify complex legal text into user-friendly language  

Document Classification  
Detect contract types (NDA, Employment, Lease, Service Agreement, etc.)  

Named Entity Recognition (NER)  
Extract parties, dates, organizations, amounts, obligations, and key legal terms  

Clause Simplification  
Translate dense clauses into plain English for easy understanding  

Keyword Search  
Instantly find clauses or terms within documents  

Enhanced Capabilities

Bulk Simplification  
Simplify multiple clauses simultaneously  

Multi-Format Support  
Process PDF, DOCX, and TXT documents  

Clause Extraction  
Break contracts into meaningful clause units for better readability  

📁 Project Structure

ClauseWise/  
├── backend/  
│   ├── main.py              # FastAPI backend  
│   ├── requirements.txt    # Backend dependencies  
│   └── ...  
├── frontend/  
│   ├── app.py              # Streamlit frontend  
│   ├── requirements.txt    # Frontend dependencies  
│   └── ...  
├── README.md               # Project documentation  
└── ...  

🛠️ Technology Stack

Backend  
- FastAPI – High-performance API framework  
- Hugging Face Transformers & PyTorch – NLP models  
- pypdf, python-docx, re – Document parsing utilities  

Frontend  
- Streamlit – Interactive UI for analysis  
- pandas – Data handling and visualization  

🔧 Installation & Setup

Prerequisites  
- Python 3.8+  
- pip  
- Git  

Clone the Repository  
git clone https://github.com/YOUR-USERNAME/ClauseWise.git  
cd ClauseWise  

Run the Backend (FastAPI)  
cd backend  
pip install -r requirements.txt  
uvicorn main:app --reload  

Run the Frontend (Streamlit)  

Open a new terminal:  
cd frontend  
pip install -r requirements.txt  
streamlit run app.py  

📖 Usage Guide

- Upload Document: Upload a PDF, DOCX, or TXT file via the Streamlit interface  
- Analyze Document: Extract entities, simplify clauses, and classify contract type  
- Search & Simplify: Use keyword search and bulk simplification  
- Download Results: Export structured outputs for reporting  

🔍 API Endpoints

POST /upload → Upload a document  
POST /simplify → Simplify legal clauses  
POST /classify → Document type classification  
POST /ner → Named Entity Recognition  
GET /health → API health check  

🎯 Key Components

Clause Simplification  
Converts legalese into plain English  

Entity Extraction (NER)  
Captures parties, dates, monetary values, obligations, and organizations  

Document Classification  
Identifies contract type (e.g., NDA, Service Agreement)  

Bulk Processing  
Simplify multiple clauses at once  

🔐 Security & Reliability

- Input validation for uploaded files  
- Error handling for corrupted/password-protected documents  
- Supports large document processing with batching  

👥 Team

This project was developed as part of a team hackathon.

Team Members:
- Salver Santoshi (https://github.com/santoshisalver)
- Priyamani Reddy
- Shivani Bagali

Original repository: https://github.com/bobbitipriyamanireddy/ClauseWise

🤝 Contributing

Fork the repository  
Create a new feature branch (git checkout -b feature/awesome-feature)  
Commit changes (git commit -m "Add awesome feature")  
Push to branch (git push origin feature/awesome-feature)  
Open a Pull Request  

📄 License

This project is licensed under the MIT License – see the LICENSE file for details.

🙏 Acknowledgments

FastAPI community  
Streamlit for an elegant frontend  
Hugging Face & PyTorch for NLP models  
IBM Granite & NASSCOM AI platforms  
SmartBridge, GNITS IEEE & IETE  
Contributors and testers  
