<!-- PROJECT LOGO -->
<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/2921/2921222.png" alt="Expense Tracker Logo" width="100" height="100">
</p>

<h1 align="center">💼 Expense Tracker</h1>

<p align="center">
  <b>A Smart & Personal Expense Tracking Application — Designed and Developed by <a href="https://github.com/soniya231104">Soniya</a></b>
  <br><br>
  <a href="#overview">Overview</a> •
  <a href="#features">Features</a> •
  <a href="#usage-guide">Usage Guide</a> •
  <a href="#technical-specifications">Technical Specs</a> •
  <a href="#security-and-privacy">Security & Privacy</a>
</p>

---

## 🧩 Overview

**Expense Tracker** is a desktop application built using Python, developed to help users seamlessly log, visualize, and analyze their income and expenses. With a modern UI and robust backend, it’s crafted to assist in achieving financial clarity and freedom.

> 💡 *This project was developed as a personal portfolio application — fully self-contained and used locally.*

---

## ✨ Key Features

### 📊 Expense & Income Management
- Log transactions with amount, date, category, and comments  
- Edit or remove entries as needed  
- View summaries of income vs. expenses  

### 📈 Visual Insights
- Pie-charts and bar-plots showing expense breakdown by category  
- Trend analysis over time (daily, monthly, yearly)  
- Easy-to-interpret visuals built with matplotlib  

### 🖥️ User Interface
- Built with **tkinter** and **customtkinter** for sleek, modern design  
- Responsive layout with intuitive navigation  
- Includes background imagery and icons for UI polish  

### 🗄️ Data Persistence
- Uses a local **PostgreSQL** database (via psycopg2) for storing data securely  
- Provided `data.sql` to initialize required database schema  
- All data stays on your local machine  

---

## 🧭 Usage Guide

### 1️⃣ Installation
```bash
pip install tkinter customtkinter Pillow psycopg2 matplotlib
````

Also ensure you have a PostgreSQL server running, and create/point to the database as defined within the code (or adjust the connection settings as needed).

### 2️⃣ Running the Application

* Launch `Expense-Tracker.py`
* On first run, sign up a new user or log in
* Begin adding transactions via the user interface
* Navigate between sections to view summaries and charts

### 3️⃣ Visualizations

* Select “View Summary” to see charts
* Choose categories or date ranges for custom analyses
* Export or capture screenshot for record-keeping

---

## 🧱 Technical Specifications

| Component                 | Description                                |
| ------------------------- | ------------------------------------------ |
| **Programming Language**  | Python 3.x                                 |
| **GUI Toolkit**           | tkinter + customtkinter                    |
| **Imaging**               | PIL / Pillow (for UI images/icons)         |
| **Database Engine**       | PostgreSQL (psycopg2)                      |
| **Visualization Library** | matplotlib                                 |
| **UI Assets**             | Includes `background.jpg`, `side.png` etc. |

---

## 🔧 Project Structure

```
Expense-Tracker/
│
├── Expense-Tracker.py     # Main application script
├── data.sql               # SQL schema & initialisation
├── background.jpg         # UI background image
├── side.png               # UI side panel image/icon
├── /assets                # Additional icons/images if any
└── README.md              # This documentation
```

---

## 🚀 Example Usage Snippet

```python
# Example: adding a transaction
tracker = ExpenseTracker(db_config)
tracker.add_transaction(user_id=1,
                        amount=450.00,
                        category="Groceries",
                        date="2025-11-02",
                        comment="Weekly supplies")
```

---

## 🧠 Learning Objectives

By developing and using this project you will:

* Understand the basics of GUI application development (tkinter)
* Gain experience with relational database design and interaction (PostgreSQL)
* Learn to generate visual analytics using matplotlib
* Develop an integrated workflow from UI to persistence to analysis

---

## ⚠️ Security & Privacy

> This application is **proprietary and for personal/portfolio use only.**
> It is **not** intended for production deployment.

* All user data is stored locally — verify your own backup/security practices.
* The database credentials and config should be handled securely.
* Use strong OS-level protections for your machine if you store sensitive financial data.

---

## 💬 Author

**👩‍💻 Developed by:** [Soniya](https://github.com/soniya231104)
**📧 Contact:** [soniyaxxxxxx@gmail.com](mailto:soniyaxxxxxx@gmail.com) *(update with your real email if desired)*
**📍 Location:** India

> *Bringing clarity, simplicity, and design into personal finance tracking.*

---

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Active-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Made%20With-Python-yellow?style=for-the-badge"/>
</p>

---

<p align="center">
  <b>© 2025 Expense Tracker by Soniya</b><br>
  <i>All rights reserved. Unauthorized distribution or replication is strictly prohibited.</i>
</p>
