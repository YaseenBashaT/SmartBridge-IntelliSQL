# IntelliSQL: Intelligent SQL Querying with Gemini Pro
## 👥 Team Members & Roles

**Team ID:** LTVIP2026TMIDS66076
**Team Size:** 4

### 🔹 Thammisetty Chaitanya (Team Leader)

**Role:** AI Specialist & Project Manager

* Integrated Gemini AI model
* Oversaw architecture and development workflow

### 🔹 Thippaluri Yaseen Basha

**Role:** Backend Developer & Data Engineer

* Developed SQLite database structure
* Implemented query execution pipeline

### 🔹 Ummaneni Naga Pravallika

**Role:** Frontend Developer & UI/UX Designer

* Designed Streamlit interface
* Built user-friendly dashboard features

### 🔹 Vuppala Vaishnavi

**Role:** QA Engineer & Documentation Specialist

* Tested query accuracy and sanitization
* Prepared documentation and reports

---
**Problem Statement**


**IntelliSQL** is an innovative database querying tool designed to bridge the gap between natural language and structured data. By leveraging the **Gemini 1.5 Flash model**, it enables even non-technical users to extract meaningful insights from a SQLite database simply by asking questions in plain English.

This project simplifies data access, enhances productivity, and makes database interaction more intuitive.

---

## 🚀 Features

### ✅ Text-to-SQL Translation

Converts natural language questions into accurate SQL queries using advanced LLM capabilities.

### ✅ Regex Sanitization Layer

A custom logic layer cleans AI responses so that only valid and safe SQL queries are executed.

### ✅ Interactive Dashboard

Streamlit-based professional UI with:

* Dark mode support
* Sidebar navigation
* Clean structured data tables

### ✅ Secure Configuration

Sensitive API keys are securely handled using:

* `.env` files
* `python-dotenv`

### ✅ Real-time Query Results

Instant rendering of database records in a structured, readable format.

---

## 🛠️ Technology Stack

**Frontend:**

* Streamlit

**Backend:**

* Python
* Google Generative AI SDK

**Database:**

* SQLite

**AI Model:**

* Gemini 1.5 Flash

---

## 📂 Project Structure

```
IntelliSQL/
├── .venv/                # Virtual environment
├── Project Files/        # Core application files
│   ├── .env              # API key storage
│   ├── app.py            # Streamlit UI & AI logic
│   ├── sql.py            # Database setup & seeding
│   ├── data.db           # SQLite database
│   └── requirements.txt  # Dependencies
└── README.md             # Documentation
```

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Shaik-Mohammad-Ashfaq/IntelliSQL.git
cd IntelliSQL
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv .venv
```

Activate environment:

**Windows:**

```bash
.venv\Scripts\activate
```

**Mac/Linux:**

```bash
source .venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r "Project Files/requirements.txt"
```

---

### 4️⃣ Configure API Key

Create a `.env` file inside **Project Files** folder:

```
GOOGLE_API_KEY="your_google_gemini_api_key"
```

---

### 5️⃣ Initialize Database

```bash
python "Project Files/sql.py"
```

---

### 6️⃣ Run the Application

```bash
streamlit run "Project Files/app.py"
```

---



## ⚠️ Known Issues

* Complex multi-table joins may occasionally produce inaccurate SQL if schema context is unclear.
* Requires active internet connection for Gemini API access.

---

## 🌟 Future Enhancements

* Multi-database support (MySQL/PostgreSQL)
* Query explanation feature
* Voice-based natural language queries
* Improved schema-aware prompt engineering

---

