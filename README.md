# 🔍 SalesLens — RFM Segmentation Engine

> Transform raw sales data into actionable customer intelligence — instantly.

![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

---

## 📌 Overview

**SalesLens** is an end-to-end customer segmentation tool built on **RFM Analysis**
(Recency, Frequency, Monetary). Upload any sales CSV and instantly discover:

- 🏆 Who your **Champions** are
- 💛 Who your **Loyal Customers** are
- ⚠️ Who is **At Risk** of churning
- ❌ Who is already **Lost**

---

## 🚀 Live Demo

🔗 **Try it here →** [your-streamlit-url.streamlit.app](https://your-streamlit-url.streamlit.app)

---

## 📸 Screenshots

| Dashboard Overview | Customer Segments |
|---|---|
| ![Overview](screenshots/dashboard_overview.png) | ![Segments](screenshots/customer_segments.png) |

---

## 🧠 What is RFM Analysis?

| Metric | Description |
|---|---|
| **R — Recency** | How recently did the customer purchase? |
| **F — Frequency** | How often do they purchase? |
| **M — Monetary** | How much do they spend in total? |

Each customer is scored 1–4 on each metric and grouped into segments
that help businesses **prioritize marketing efforts** and **reduce churn**.

---

## 📂 Project Structure
```
SalesLens-RFM-Segmentation-Engine/
│
├── dataset/
│   ├── raw/                        # Original CSV files
│   └── processed/                  # Cleaned data
│
├── report/
│   └── SalesLens_RFM_Dashboard.pbix
│
├── screenshots/
│   ├── dashboard_overview.png
│   └── customer_segments.png
│
├── app/
│   ├── app.py                      # Streamlit web app
│   ├── rfm_engine.py               # RFM calculation logic
│   └── requirements.txt
│
├── docs/
│   └── data_dictionary.md
│
├── .gitignore
└── README.md
```

---

## ⚙️ How to Run Locally
```bash
# 1. Clone the repo
git clone https://github.com/YOUR_USERNAME/SalesLens-RFM-Segmentation-Engine.git
cd SalesLens-RFM-Segmentation-Engine

# 2. Install dependencies
pip install -r app/requirements.txt

# 3. Run the app
streamlit run app/app.py
```

---

## 📊 CSV Format Expected

Your CSV should have at least these 3 columns (names can vary — you map them in the app):

| Column | Description | Example |
|---|---|---|
| Customer ID | Unique customer identifier | C1001 |
| Order Date | Date of purchase | 2024-03-15 |
| Sales Amount | Revenue per transaction | 250.00 |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Power BI** | Interactive dashboard & visualization |
| **Python** | RFM calculation logic |
| **Streamlit** | Live web app for CSV upload |
| **Pandas** | Data processing |
| **Plotly** | Charts & graphs |

---

## 📈 Key Insights Delivered

- 📊 Customer distribution across RFM segments
- 🔁 Repeat purchase patterns
- 💰 Revenue contribution by segment
- 📉 Churn risk identification

---

## ⭐ If you found this useful, give it a star!

---

*Made with ❤️ and a lot of data*
