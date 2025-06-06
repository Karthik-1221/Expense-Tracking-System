![Copilot_20250606_230951](https://github.com/user-attachments/assets/3b6afc4c-44bb-4363-8fe1-ecfb8fd289f9)



Expense Tracking System

A streamlined and efficient Expense Management System built with Streamlit for the frontend and FastAPI for the backend. Designed to help users log, track, and analyze their spending in a clean and interactive interface.

Project Structure
 ```commandline
expense-management-system/
├── frontend/       # Streamlit frontend application
├── backend/        # FastAPI backend server
├── tests/          # Test cases for frontend and backend
├── requirements.txt # Required Python packages
└── README.md       # Project overview & setup instructions
 ```
Quick Start

## Setup Instructions

1. **Clone the repository**:
   ```bash
   https://github.com/Karthik-1221/Expense-Tracking-System.git
   cd Expense-Tracking-System
   ```
2. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
3. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
4. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```


