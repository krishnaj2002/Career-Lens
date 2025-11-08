
# 💼 Career-Lens  
### AI-Powered Resume–JD ATS Analyzer

Career-Lens helps users analyze resumes against job descriptions and generate **ATS-friendly reports** with **skill matching, scoring, and gap detection**, automating major parts of the recruitment and candidate-evaluation workflow.

---

## 🚀 Features

- 📤 **Resume Upload (PDF/DOCX)** – Extracts and parses resume data  
- 🧾 **Job Description Input** – Accepts complete JD text for comparison  
- 📊 **ATS Score Calculation** – Generates optimization score + suggestions  
- 🧩 **Skill Matching Analysis** – Detects matched + missing technical & soft skills  
- ⚙️ **Experience & Education Alignment** – Highlights mismatch & gap reports  
- 🧠 **PDF Report Export** – Automated ATS analysis report  

---

## 🧠 Tech Stack

### ✅ Backend (Developed by: *You*)
- **Python**
  - `pandas`, `numpy` → Data processing & scoring  
  - `nltk` / `spacy` → NLP/keyword extraction  
  - `PyPDF2`, `pdfminer.six` → Resume parsing  
  - `difflib` / `fuzzywuzzy` → Similarity search  
  - `matplotlib` / `plotly` → Visual charts  
  - `reportlab` → PDF report generation  

### ✅ Frontend (AI-Designed)
- React / HTML  
- Drag-and-Drop upload  
- Minimal responsive UI  

---

## 📂 Project Structure

```

CareerLens/
│
├── backend/
│   ├── ats_analysis.py          # Main backend logic
│   ├── jd_parser.py             # JD processing
│   ├── resume_extractor.py      # Resume text extraction
│   ├── skill_matcher.py         # Skill/keyword matching
│   ├── score_calculator.py      # Scoring logic
│   ├── report_generator.py      # PDF generation
│   └── requirements.txt         # Dependencies
│
├── frontend/
│   ├── index.html               # Main UI
│   ├── style.css                # Styling
│   ├── app.js                   # Frontend logic
│   └── assets/                  # Icons & UI graphics
│
├── output_reports/
│   └── sample_report.pdf        # Example ATS report
│
├── README.md
└── .gitignore

````

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/<yourusername>/CareerLens.git
cd CareerLens
````

### 2️⃣ Backend Setup

```bash
cd backend
pip install -r requirements.txt
```

### 3️⃣ Run Backend

```bash
python ats_analysis.py
```

> (Flask / FastAPI recommended for API hosting)

### 4️⃣ Run Frontend

Option A → Open directly

```
frontend/index.html
```

Option B → Serve locally

```bash
python -m http.server
```

---

## 📘 Usage

1. Upload your **resume (PDF/DOCX)**
2. Paste the **job description**
3. Click **Analyze Resume**
4. View insights including:

   * ✅ ATS Score
   * ✅ Skill Matches
   * ✅ Experience / Education Fit
   * ✅ Gap Recommendations
5. Download the **PDF report**

---

## 📈 Sample Output

| Metric                 | Score |
| ---------------------- | ----- |
| ATS Optimization Score | 90%   |
| Overall Match Score    | 85%   |
| Technical Skills Match | 100%  |
| Soft Skills Match      | 25%   |

---

## 🧩 Future Enhancements

* 🔍 ML-based semantic similarity (BERT/SBERT)
* 📊 Interactive dashboards (Streamlit/Dash)
* 💬 Feedback on missing skills
* ☁️ Cloud deployment (Streamlit Cloud / Render / AWS Lambda)

---

## 👨‍💻 Developers

| Name                 | Role                   |
| -------------------- | ---------------------- |
| **Krishna Jadhav**   | Backend Developer      |
| **Anushka Suralkar** | Co-Developer / Analyst |

> SY-MBA – Business Analytics

---

## 🏫 Institution

**Sanjivani University — School of Management**
Department: *MBA – Business Analytics*

---

## 📜 License

This project is licensed under the **MIT License**.
Feel free to use and modify with proper attribution.

---

## 🗂 Recommended GitHub Files

### ✅ Backend

* `ats_analysis.py`
* `resume_extractor.py`
* `jd_parser.py`
* `skill_matcher.py`
* `score_calculator.py`
* `report_generator.py`
* `requirements.txt`

### ✅ Frontend

* `index.html`
* `style.css`
* `app.js`
* `assets/`

### ✅ Reports

* `output_reports/sample_report.pdf`

