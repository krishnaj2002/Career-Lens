# Career-Lens
help users analyze their resumes against job descriptions and generate ATS reports with skill matching, score analysis, and gap detection — automating a major part of the recruitment and candidate evaluation process.
# 💼 Career Lens  
### Get detailed resume insights with ATS compatibility and skill analysis  

Career Lens is an intelligent **ATS Resume Analyzer** that compares resumes with job descriptions to generate detailed **ATS scores**, **skill match analysis**, and **gap insights** — helping candidates and recruiters make smarter hiring decisions.

---

## 🚀 Features

- 📤 **Resume Upload (PDF/DOCX)** – Upload resumes easily for parsing and analysis.  
- 🧾 **Job Description Input** – Paste the complete job description to analyze compatibility.  
- 📊 **ATS Score Calculation** – Get an ATS optimization score with improvement recommendations.  
- 🧩 **Skill Matching Analysis** – See matched and missing technical/soft skills using charts.  
- ⚙️ **Experience & Education Alignment** – Understand JD vs. resume alignment with clear gap reports.  
- 🧠 **Comprehensive PDF Report** – Automatically generates a downloadable ATS analysis report.

---

## 🧠 Tech Stack

### **Backend (Developed by: You)**
- 🐍 **Python**
  - `pandas`, `numpy` – Data processing and score calculations  
  - `nltk` / `spacy` – Text analysis and keyword extraction  
  - `PyPDF2`, `pdfminer.six` – Resume text extraction  
  - `difflib` / `fuzzywuzzy` – Similarity matching  
  - `matplotlib` / `plotly` – Visualizations and charts  
  - `reportlab` – Automated PDF report generation  

### **Frontend (AI-Designed)**
- 🌐 Built with a clean **React / HTML interface**
- 📦 Drag & Drop upload area
- 🎨 Minimal and responsive design  

---

## 📂 Project Structure
CareerLens/
│
├── backend/
│ ├── ats_analysis.py # Main Python backend logic
│ ├── jd_parser.py # Job description processing
│ ├── resume_extractor.py # Resume text extraction
│ ├── skill_matcher.py # Skill and keyword comparison logic
│ ├── score_calculator.py # ATS and alignment scoring
│ ├── report_generator.py # Generates PDF analysis report
│ └── requirements.txt # Python dependencies
│
├── frontend/
│ ├── index.html # Main UI (AI-generated)
│ ├── style.css # Stylesheet
│ ├── app.js # Frontend logic for uploading & calling backend API
│ ├── assets/ # Icons, logos, and screenshots
│
├── output_reports/
│ ├── sample_report.pdf # Example ATS report output
│
├── README.md # Project documentation
└── .gitignore # To ignore unnecessary files (venv, cache, etc.)


---

## ⚙️ Installation and Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/<yourusername>/CareerLens.git
cd CareerLens
2️⃣ Backend Setup
cd backend
pip install -r requirements.txt

3️⃣ Run the Backend
python ats_analysis.py


(You can use Flask/FastAPI if you want to serve it as an API.)

4️⃣ Run the Frontend

Open index.html in your browser
or serve it using:

python -m http.server

📘 Example Usage

Upload your resume (PDF/DOCX).

Paste the job description.

Click “Analyze Resume”.

View the analysis report showing:

ATS Score

Skill Matches

Gaps and Recommendations

Download the generated report (PDF).

📈 Sample Output
Metric	Score
ATS Optimization Score	90%
Overall Match Score	85%
Technical Skills Match	100%
Soft Skills Match	25%
🧩 Future Enhancements

🔍 Integrate Machine Learning (BERT/SBERT) for semantic text similarity.

📊 Add interactive dashboards using Streamlit or Dash.

💬 Add feedback system to suggest missing skills.

☁️ Deploy using Streamlit Cloud / Render / AWS Lambda.

👨‍💻 Developers

Backend Developer: Krishna Jadhav
Co-Developer / Analyst: Anushka Suralkar
Role: SY-MBA, Business Analytics Students

🏫 Institution

Sanjivani University — School of Management
Department: MBA – Business Analytics

📜 License

This project is licensed under the MIT License – feel free to modify and use it with attribution.

🖼️ Preview




⭐ If you like this project, give it a star!


---

## 🧱 **Files You Should Upload to GitHub**

### 1️⃣ **Backend Folder**
- `ats_analysis.py`
- `resume_extractor.py`
- `jd_parser.py`
- `skill_matcher.py`
- `score_calculator.py`
- `report_generator.py`
- `requirements.txt`

### 2️⃣ **Frontend Folder**
- `index.html`
- `style.css`
- `app.js`
- `assets/` (logo, screenshots, icons)

### 3️⃣ **Reports Folder**
- `output_reports/sample_report.pdf`

### 4️⃣ **Documentation**
- `README.md`
- `.gitignore` (include `/__pycache__/`, `/venv/`, `.DS_Store`, etc.)

---

Would you like me to also generate a **`requirements.txt`** file (based on your likely Python libraries) so you can directly include it in your backend folder?  
It’ll make your repo fully ready for cloning and testing.
