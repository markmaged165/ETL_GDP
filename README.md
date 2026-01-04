# ETL_GDP

Extract, Transform, and Load GDP data into a structured database for analysis and visualization.

---

## 📌 Project Overview
This project demonstrates a simple **ETL (Extract, Transform, Load)** pipeline using Python and Pandas.  
The goal is to:
- **Extract** GDP data from raw sources (CSV, web scraping, or APIs).
- **Transform** the data by cleaning, normalizing, and converting values into consistent formats.
- **Load** the cleaned dataset into a relational database (e.g., SQLite, PostgreSQL) for querying and analysis.

---

## ⚙️ Features
- Data cleaning: remove commas, convert GDP values to numeric format.
- Transformation: convert GDP from millions → billions for readability.
- Database integration: load data into SQL tables using Pandas `to_sql`.
- Query support: run SQL queries directly on the transformed dataset.
- Modular functions for each ETL step.

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, SQLAlchemy, SQLite3)
- **Jupyter Notebook / Google Colab**
- **SQL Databases** (SQLite by default, extensible to PostgreSQL/MySQL)

---

## 📂 Project Structure
TL_GDP/
│── README.md                # Project documentation
│── scripts/                # Python helper functions
│── data/                   # Raw and cleaned datasets

