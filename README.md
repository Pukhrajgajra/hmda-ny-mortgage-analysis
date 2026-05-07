# 🏠 HMDA New York Mortgage Analysis (2022–2024)

An exploratory data analysis of Home Mortgage Disclosure Act (HMDA) data for New York State, examining racial disparities in mortgage approvals, county-level lending patterns, and the relationship between income, loan amounts, and interest rates.

---

## 📊 What This Project Covers

- **Approval vs. Denial Rates by Race/Ethnicity** — identifying disparities across racial groups
- **Top 15 Counties by Mortgage Originations** — where lending is most active in NY
- **Income vs. Loan Amount** — scatter analysis of approved applicants
- **Denial Reasons Breakdown** — most common reasons applicants are rejected
- **Avg Loan Amount & Interest Rate by Year** — trends from 2022 to 2024
- **Interactive Dashboard** — filter all visuals by year, loan type, and action taken

---

## 🗂️ Data Source

This project uses publicly available HMDA data from the **Consumer Financial Protection Bureau (CFPB)**.

👉 Download the data here: [https://ffiec.cfpb.gov/data-browser/](https://ffiec.cfpb.gov/data-browser/)

- Select **New York** as the state
- Select years **2022, 2023, 2024**
- Download as CSV and save as `HMDA_NY_2022_2024.csv`

> The data file is not included in this repo due to its size.

---

## 🚀 How to Run

1. Open the notebook in **Google Colab**
2. Upload `HMDA_NY_2022_2024.csv` to your **Google Drive**
3. Run all cells — the notebook will mount your Drive and load the file automatically

---

## 🛠️ Libraries Used

- `pandas`, `numpy` — data cleaning and analysis
- `matplotlib` — static visualizations
- `plotly` — interactive bar charts
- `ipywidgets` — interactive dashboard filters

---

## 👤 Author

**Pukhraj Gajra** — Northeastern University  
Course: ALY6110
