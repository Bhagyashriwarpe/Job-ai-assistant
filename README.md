# 🤖 AI Job Assistant

An AI-powered web application that helps job seekers analyze their resumes, extract skills, find suitable job roles, identify skill gaps, get career recommendations, generate learning roadmaps, and interact with an AI chatbot.

The project uses **Google Gemini 2.5 Flash** to provide AI-powered career assistance.

---

## 📌 Project Overview

The **AI Job Assistant** analyzes a user's resume and provides personalized career-related insights using Generative AI.

Users can upload their resume in PDF format and access different AI-powered features such as resume analysis, skill extraction, job suggestions, job matching, career recommendations, skill-gap analysis, learning roadmaps, and an AI chatbot.

---

## ✨ Features

* 📄 **Resume Analysis** – Analyzes uploaded PDF resumes and provides an AI-generated summary.
* 🧠 **Skill Extraction** – Extracts technical and soft skills from resumes.
* 💼 **Job Role Suggestions** – Suggests suitable job roles based on user input.
* 🎯 **Job Matching** – Matches resume information with suitable job opportunities.
* 💡 **Career Recommendations** – Provides personalized career suggestions.
* 📊 **Skill Gap Analysis** – Identifies skills that need improvement.
* 🗺️ **Learning Roadmap** – Generates a personalized learning roadmap.
* 💬 **AI Chatbot** – Answers career-related questions using Gemini AI.

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Fetch API
* FormData

### Backend

* Python
* Flask
* Flask-CORS
* Gunicorn

### AI

* Google Gemini API
* Gemini 2.5 Flash
* Generative AI
* Large Language Model (LLM)
* Prompt Engineering
* Natural Language Processing (NLP)

### PDF Processing

* PyPDF2

### Configuration

* Python-dotenv
* Environment Variables

### Deployment

* Render

---

## 🧠 AI Concepts Used

### Generative AI

Used to generate career-related responses such as resume analysis, job suggestions, recommendations, skill gaps, and learning roadmaps.

### Large Language Model (LLM)

**Gemini 2.5 Flash** is used as the Large Language Model to understand resume content and user queries and generate meaningful responses.

### Prompt Engineering

Different prompts are used for different features, including:

* Resume analysis
* Skill extraction
* Job suggestions
* Job matching
* Career recommendations
* Skill-gap analysis
* Learning roadmap
* Chatbot

### Natural Language Processing (NLP)

Used to process resume text and user queries so that Gemini can understand the information and generate relevant responses.

---

## 💡 Core Concepts Demonstrated

### Python

* Python Programming
* Functions
* Conditional Statements
* Exception Handling
* File Handling
* Environment Variables
* Modular Programming

### Flask

* Flask Web Framework
* REST API Development
* Routing
* Request Handling
* JSON Responses
* File Upload Handling
* CORS

### Frontend

* HTML
* CSS
* JavaScript
* DOM Manipulation
* Event Handling
* Fetch API
* FormData
* Dynamic Content Rendering

### API Integration

* Frontend-Backend Integration
* REST API Communication
* Gemini API Integration
* JSON-based Data Exchange

### PDF Processing

* PDF File Upload
* PDF Text Extraction
* Resume Text Processing

---

## 📂 Project Structure

```text
Job-ai-assistant/
│
├── frontend/
│   ├── index.html
│   ├── script.js
│   └── style.css
│
├── job_ai_backend/
│   ├── app.py
│   ├── gemini_client.py
│   ├── list_models.py
│   ├── requirements.txt
│   └── .gitignore
│
└── .gitignore
```

---

## ⚙️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Bhagyashriwarpe/Job-ai-assistant.git
cd Job-ai-assistant
```

### 2. Open Backend

```bash
cd job_ai_backend
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

For Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Add Gemini API Key

Create a `.env` file inside `job_ai_backend`:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Do not upload your API key to GitHub.

### 6. Start Backend

```bash
python app.py
```

The backend runs locally on:

```text
http://localhost:5000
```

### 7. Run Frontend

Open:

```text
frontend/index.html
```

in your browser.

---

## ☁️ Deployment

The project is deployed using **Render**.

### Backend

* Platform: Render
* Environment: Python
* Install Command:

```bash
pip install -r requirements.txt
```

* Start Command:

```bash
gunicorn app:app
```

* Environment Variable:

```text
GEMINI_API_KEY
```

### Frontend

The frontend is a static HTML, CSS, and JavaScript application and can be deployed as a **Render Static Site**.

The frontend communicates with the deployed Flask backend through the backend URL configured in `script.js`.

---

## 🔐 Security

The Gemini API key is stored using an environment variable:

```env
GEMINI_API_KEY=your_gemini_api_key
```

The API key should never be hard-coded or committed to GitHub.

---

## 🎓 Key Learning Outcomes

* Python and Flask backend development
* REST API development
* Frontend-backend integration
* Gemini AI integration
* Generative AI and LLM concepts
* Prompt Engineering
* Natural Language Processing
* PDF text extraction
* JavaScript and API handling
* Environment variable management
* Deployment using Render

---

## 👩‍💻 Author

**Bhagyashri Varape**

B.Tech – Electronics and Telecommunication Engineering
