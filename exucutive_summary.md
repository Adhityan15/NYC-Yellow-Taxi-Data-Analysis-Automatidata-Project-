# 📊 Executive Summary – Automatidata NYC Taxi Project

## 📝 Summary of Tasks

As part of the Automatidata team, I was tasked with preparing the New York City Yellow Taxi trip data for analysis. My work focused on importing, inspecting, and organizing the dataset so it is ready for exploratory data analysis and predictive modeling.

---

## 📈 Data Variable Assessment

- **Dataset Size:** 408,294 rows × 18 columns
- **Key Variables:** `trip_distance`, `total_amount`, `passenger_count`, `payment_type`
- **Issues Noticed:**
  - Null values in some columns
  - Outliers in `trip_distance` and `total_amount`
  - Tip amount available **only for credit card payments**
- **Data Types:** Mostly numeric, some categorical (e.g., `payment_type`, `VendorID`)

---

## 🧠 Insights Gained

- **Credit card** is the most common payment method.
- Mean tip amount varies significantly by **passenger count** for credit card users.
- Disputed/voided trips are identified by negative or zero total fares.
- `trip_distance` and `total_amount` will be critical for future fare prediction modeling.

---

## 🚀 Recommended Next Steps

1. **Data Cleaning**:
   - Handle missing and invalid values
   - Remove or treat outliers

2. **Exploratory Data Analysis (EDA)**:
   - Visualize trip trends, fare distribution, and passenger behavior

3. **Model Building**:
   - Predict `total_amount` or `tip_amount` using linear regression or decision trees

---

## 💼 Stakeholder Notes

The dataset is now structured and ready for deeper analysis. Future tasks should prioritize building visual dashboards and predictive models for trip pricing insights, ultimately helping NYC TLC optimize operations and services.

---

Prepared by: **Adhityan R**  
Role: Junior Data Analyst at Automatidata  
Date: June 2025
