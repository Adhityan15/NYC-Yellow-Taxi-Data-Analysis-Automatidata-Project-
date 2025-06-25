# NYC Yellow Taxi Data Analysis (Automatidata Project)

🚕 A Python-based data inspection project using NYC Taxi Trip Data — developed as part of the Google Data Analytics Professional Certificate (Course 2 - Get Started with Python).

---

## 📌 Project Overview

This project simulates a workplace scenario at a fictional data firm, **Automatidata**, where we prepare NYC Yellow Taxi trip data for analysis. Our goal was to inspect, organize, and summarize the dataset in preparation for exploratory data analysis (EDA) and predictive modeling.

---

## 📁 Dataset

**Name:** 2017_Yellow_Taxi_Trip_Data.csv  
**Source:** New York City Taxi & Limousine Commission (TLC)  
**Rows:** 408,294  
**Columns:** 18  
Each row represents an individual taxi trip.

---

## 🧰 Tools Used

- Python 3.x
- pandas
- NumPy
- Jupyter Notebook

---

## 🔍 Key Tasks Performed

1. **Imported and explored the dataset**
2. **Inspected column data types and null values**
3. **Sorted and analyzed key variables:**
   - `trip_distance`
   - `total_amount`
4. **Explored payment types and vendor IDs**
5. **Calculated average tip amounts based on payment method and passenger count**

---

## 🧠 Key Findings

- Some trips had **unrealistically high distance and fare values**, indicating outliers.
- Negative and zero `total_amount` values suggest **disputes or voided trips**.
- **Tip amounts** are only present for **credit card** payments.
- `trip_distance` and `total_amount` were identified as the **most important variables** for future modeling.

---

## 📌 Next Steps

- Remove or treat outliers in `trip_distance` and `total_amount`
- Handle missing values
- Prepare for visual EDA and hypothesis testing
- Build regression models to predict fares or tips

---

## 📎 Files in Repository

- `Automatidata_Project.ipynb` – Jupyter Notebook with all Python code
- `Executive_Summary.md` – Summary of insights for stakeholders
- `PACE_Strategy.md` – Project planning and reasoning steps (optional)
- `README.md` – Project documentation (this file)

---

## ✨ Author

**Adhityan R**  
Google Data Analytics Learner | Aspiring Data Scientist  

