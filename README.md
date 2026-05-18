# Uber Eats Bangalore: Restaurant Intelligence & Decision Support System

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)

## 🚀 Live Demo

You can view the live application here: [Uber Eats Bangalore Restaurant Intelligence System](https://uber-eats-bangalore-restaurant-intelligence.streamlit.app/)

## 📌 Project Overview
This project is a **Data Engineering and Business Intelligence** solution designed to analyze the Uber Eats restaurant marketplace in Bangalore. It functions as a **Decision Support System (DSS)** that helps stakeholders make data-driven choices regarding location strategy, pricing, and feature adoption.

Unlike standard dashboards, this system mirrors internal corporate tools by providing **precise tabular insights** through a Streamlit interface, driven entirely by optimized **SQL queries**.

---

## 🛠️ Tech Stack
* **Language:** Python (Pandas, NumPy)
* **Database:** MySQL
* **Dashboard:** Streamlit
* **Analytics:** Advanced SQL (Joins, Aggregations, Case Logic)

---

## 🚀 System Architecture

### 1. Data Pipeline (Python & Pandas)
* **Cleaning:** Handled missing values, removed duplicates, and standardized costs/ratings.
* **Transformation:** Feature engineering for pricing segments and rating categories.
* **Ingestion:** Migrated cleaned CSV and JSON (order data) into a structured SQL database.

### 2. Analytics Layer (SQL)
* All business logic is executed via **cursor-based SQL queries**.
* Uses `GROUP BY`, `HAVING`, and `CASE WHEN` for dynamic data segmentation.

### 3. User Interface (Streamlit)
* **Dashboard Page:** Features dynamic SQL-based filters to retrieve specific datasets.
* **Q&A Page:** A dedicated module answering 10+ predefined business questions with structured tabular outputs.

---

## 📂 Project Structure
```text
├── data/               # Raw and cleaned datasets (CSV/JSON)
├── scripts/            # Python scripts for cleaning & SQL migration
├── app.py              # Main Streamlit application
├── requirements.txt    # List of required Python libraries
├── .gitignore          # Files excluded from version control
└── README.md           # Project documentation
