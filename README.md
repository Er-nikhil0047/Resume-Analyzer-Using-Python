# 🤖 AI Resume Analyzer Pro

An AI-powered Resume Analyzer built with **Python, Flask, Google Gemini 2.5, and PyMuPDF** that evaluates resumes against job descriptions, calculates match scores, identifies missing skills, and provides actionable improvement suggestions.

---

## ✨ Features

* 📄 Upload Resume in PDF format
* 🤖 AI-Powered Resume Analysis using Google Gemini 2.5
* 🎯 Resume vs Job Description Match Score
* 🔍 Missing Skills Detection
* 💡 Personalized Resume Improvement Suggestions
* ⚡ Fast PDF Text Extraction with PyMuPDF
* 🌙 Modern Glassmorphism Dark UI
* 📱 Responsive Design

---

## 📸 Preview

<img width="1918" height="977" alt="image" src="https://github.com/user-attachments/assets/2296a960-4ef1-4de1-b90b-de475d50144c" />


### Home Page

<img width="1907" height="957" alt="image" src="https://github.com/user-attachments/assets/dbb711af-098a-4515-93ae-f724186c9462" />


### Analysis Result

<img width="1918" height="981" alt="image" src="https://github.com/user-attachments/assets/4ea55175-6458-42b6-a06d-2dac12bdd621" />


---

## 🛠 Tech Stack

### Backend

* Python
* Flask

### AI Integration

* Google Gemini 2.5
* google-genai SDK

### PDF Processing

* PyMuPDF (fitz)

### Frontend

* HTML5
* CSS3
* Bootstrap

### Environment Management

* python-dotenv

---

## 📂 Project Structure

```text
Resume_Analyser_Using_Python/
│
├── static/
│   ├── css/
│   └── uploads/
│
├── templates/
│   └── index.html
│
├── main.py
├── requirements.txt
├── .env
└── README.md
```

---

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Resume-Analyzer-Using-Python.git
cd Resume-Analyzer-Using-Python
```

### 2. Create Virtual Environment

#### Windows

```cmd
python -m venv venv
venv\Scripts\activate
```

#### macOS/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the project root directory:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

Get your API key from:

https://aistudio.google.com/app/apikey

---

## ▶️ Run the Application

```bash
python main.py
```

---

## 🌐 Open in Browser

```text
http://127.0.0.1:5000
```

---

## 🎯 How It Works

1. Upload your Resume (PDF).
2. Enter the Job Description.
3. AI extracts and analyzes resume content.
4. Gemini compares the resume with the job requirements.
5. Receive:

   * Match Score
   * Missing Skills
   * Resume Strengths
   * Improvement Suggestions

---

## 📦 Requirements

```txt
Flask
google-genai
PyMuPDF
python-dotenv
markdown
```

Install all requirements:

```bash
pip install -r requirements.txt
```

---

## 🔮 Future Improvements

* ATS Score Analysis
* Multiple Resume Comparison
* Resume Keyword Optimization
* Download Analysis Report as PDF
* User Authentication
* Resume Templates Generator

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
