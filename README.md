# 🎓 Final Year Project: AI-Powered Personal Finance Tracker

A Smart, AI-driven platform for modern personal finance management — combining voice input, receipt scanning, machine learning, and predictive analytics to help users take control of their financial future.

---

## 📘 Abstract

In today's fast-paced digital world, many individuals struggle with managing their finances due to the limitations of traditional budgeting tools and manual tracking. Our project — **AI-Powered Personal Finance Tracker** — presents an intelligent, accessible, and bank-independent solution for effortless financial management.

This platform uses cutting-edge technologies like **Tesseract OCR** for extracting transaction data from receipts, **FinBERT NLP** for intelligent expense categorization, and supports **voice-based transaction logging** via the **Web Speech API** and **Stanza**. For smarter budgeting and forecasting, it integrates **Gradient Boosted Decision Trees**, **Prophet**, and **LSTM models**.

Key modules include **Group Expense Management** for shared finances, and **Celery-based Reminders** to notify users about bills. The system is built with a **Django backend** and a responsive **HTML + Tailwind CSS** frontend.

---

## 🚀 Key Features

- 🧾 **Receipt Scanning:** Extract transaction data using Tesseract OCR.
- 🗣️ **Voice Logging:** Add expenses using voice input with Web Speech API and Stanza.
- 📊 **Smart Categorization:** FinBERT classifies expenses into intelligent categories.
- 📈 **Forecasting Engine:** Uses Prophet + LSTM for financial trend prediction.
- 💰 **AI Budgeting:** Gradient Boosted Decision Trees generate budget suggestions.
- 👥 **Group Expenses:** Track and manage shared spending with others.
- ⏰ **Bill Reminders:** Scheduled reminders using Celery and Redis.
- 🖥️ **Dashboard:** Visualizes spending, forecasts, and trends for informed decisions.
- 🔐 **Authentication:** Session-based login system ensures secure access.

---

## 🛠️ Tech Stack

| Layer        | Technologies Used                                                                 |
|--------------|------------------------------------------------------------------------------------|
| Frontend     | HTML5, Tailwind CSS, JavaScript, Web Speech API                                   |
| Backend      | Python, Django, Celery, Redis, SQLite                                              |
| AI & ML      | Tesseract OCR, FinBERT (NLP), Stanza (NLP), Gradient Boosted Trees, Prophet, LSTM |                                |
| Auth         | Django Sessions                                                                    |

---

## 📂 Folder Structure (Simplified)

Final-Year-Project/
├── finance_tracker/ # Django project folder
├── templates/ # HTML templates
├── static/ # Tailwind CSS, JS, images
├── receipts/ # Uploaded receipt images
├── models/ # Trained ML models (Pickle format)
├── celery.py # Task scheduling setup
├── requirements.txt # Dependencies
└── README.md # Project documentation


---


