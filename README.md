<div align="center">

# 💸 Expense Tracking System

### *A full-stack expense management app — log, track, and analyse your spending with a clean Streamlit UI powered by a FastAPI backend.*

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Uvicorn](https://img.shields.io/badge/Uvicorn-4B0082?style=for-the-badge&logo=gunicorn&logoColor=white)](https://www.uvicorn.org/)

</div>

---

## 🔍 Overview

The Expense Tracking System is a streamlined full-stack application designed to make personal finance management effortless. Built with **Streamlit** on the frontend and **FastAPI** on the backend, it provides a clean, interactive interface for logging expenses, tracking spending trends, and gaining insights into financial behaviour — all with minimal setup.

---

## ✨ Features

- 📝 **Expense Logging** — Add, edit, and delete expenses with category and date tagging
- 📊 **Spending Analysis** — Visualise spending patterns across categories and time periods
- ⚡ **FastAPI Backend** — High-performance REST API with auto-generated Swagger docs at `/docs`
- 🖥️ **Streamlit Frontend** — Clean, real-time interactive UI requiring zero web development
- 🧪 **Test Coverage** — Dedicated test suite for both frontend and backend components

---

## 🏗️ Architecture

```
┌─────────────────────┐         ┌─────────────────────┐
│     Frontend        │         │      Backend         │
│   (Streamlit)       │  ─────► │    (FastAPI)         │
│                     │         │                      │
│  • Expense entry UI │  REST   │  • API endpoints     │
│  • Analytics views  │  API    │  • Business logic    │
│  • Data display     │  ◄───── │  • Swagger docs      │
└─────────────────────┘         └─────────────────────┘
                                         │
                                    (Uvicorn ASGI)
```

---

## 🛠️ Tech Stack

| Layer | Technology | Role |
|-------|-----------|------|
| **Frontend** | [Streamlit](https://streamlit.io/) | Interactive UI application |
| **Backend** | [FastAPI](https://fastapi.tiangolo.com/) | RESTful API server |
| **Server** | [Uvicorn](https://www.uvicorn.org/) | High-performance ASGI runtime |
| **Language** | Python 3.8+ | Core language |

---

## 📂 Project Structure

```
expense-tracking-system/
├── frontend/          # Streamlit UI application
├── backend/           # FastAPI server & API routes
├── tests/             # Test cases for frontend & backend
├── requirements.txt   # All project dependencies
└── README.md          # You are here!
```

---

## 🚀 Quick Start

**1. Clone the repository**

```bash
git clone https://github.com/Karthik-1221/Expense-Tracking-System.git
cd Expense-Tracking-System
```

**2. Install dependencies**

```bash
pip install -r requirements.txt
```

**3. Start the FastAPI backend**

```bash
uvicorn server.server:app --reload
```

> API will be live at `http://localhost:8000` — visit `http://localhost:8000/docs` for the interactive Swagger UI.

**4. Launch the Streamlit frontend**

```bash
streamlit run frontend/app.py
```

> App opens automatically at `http://localhost:8501`

---

## 🧪 Running Tests

```bash
pytest tests/
```

---

## 👤 Author

**Karthik Boodidha** — Data Scientist & Backend Developer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karthik-boodidha)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Karthik-1221)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF6B35?style=flat-square&logo=codeforces&logoColor=white)](https://codebasics.io/portfolio/Karthik-Boodidha)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/boodidhakarthik)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtube.com/@learndatasciencewithkarthik)

---

<div align="center">

⭐ **If this project was useful, give it a star!**

*Built with Python · FastAPI · Streamlit · Uvicorn*

</div>
