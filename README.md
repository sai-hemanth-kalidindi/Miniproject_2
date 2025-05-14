# Miniproject_2
# 🌪️ Air Turbulence and Flight Safety: A Data-Driven Visualization Project

## 📘 Course
**RPAD 676: Data Science for the Public Good – Spring 2025**  
Final Portfolio Mini-Project

---

## 🎯 Objective

This project explores patterns in air turbulence-related incidents using real-world aviation safety data. The aim is to identify risk-prone flight phases, contributing human factors (like fatigue or distraction), and trends over time that affect public flight safety. 

This analysis serves the public good by making aviation safety insights transparent and accessible to passengers, regulators, and airline operators.

---

## 📁 Dataset

- **Source:** NASA Aviation Safety Reporting System (ASRS)
- **Download Link:** [Kaggle Dataset](https://www.kaggle.com/datasets/drxc75/nasa-asrs)
- **File Format:** Parquet
- **Size:** ~97,000 reports
- **Content Includes:**
  - Date, flight phase, aircraft info, human factors, pilot narratives, incident context

---

## 🧰 Tools & Libraries

- Python 3 (Google Colab)
- `pandas` for data handling
- `matplotlib` & `seaborn` for visualizations
- `pyarrow` for Parquet file support

---

## 📊 Key Visualizations

### 1. **Turbulence by Flight Phase**
Bar chart showing which flight phases (e.g., cruise, descent) are most commonly associated with turbulence incidents.

### 2. **Human Factors in Turbulence Incidents**
Visual breakdown of fatigue, distraction, and other human contributors to turbulence-related events.

### 3. **Yearly Trend of Turbulence Reports**
A time-series plot showing how turbulence-related incident reports have changed year over year.

---

## 🔍 Insights

- **Cruise and descent phases** see the most turbulence events.
- **Fatigue and distraction** are top human factors associated with turbulence reports.
- Turbulence reports are **increasing over time**, potentially due to improved reporting or changing weather patterns.

---

## ✈️ Public Good Impact

By making air turbulence patterns visible and interpretable, this project:
- Supports better pilot and passenger awareness during vulnerable flight phases
- Encourages data-informed decision-making in aviation safety policy
- Highlights the need for improved crew support and fatigue management

---

## 🚀 How to Run

1. Download the `.parquet` files from Kaggle
2. Open the `Turbulence_Analysis.ipynb` notebook in Google Colab
3. Upload the dataset files
4. Run all cells to view insights and visualizations

---

## 🧑‍💻 Author

Sai Hemanth Varma Kalidindi 
Master’s in Business Analytics, University at Albany  
RPAD 676 – Spring 2025  


