🚕 NYC Yellow Taxi Data Analysis — Automatidata Project
A comprehensive Python-based data science project analyzing NYC Yellow Taxi trip data. Developed as part of the Google Data Analytics Professional Certificate (Course 2), this project simulates a real-world scenario at the fictional data firm Automatidata, where we transform raw trip data into actionable insights through cleaning, exploration, hypothesis testing, and predictive modeling.

📌 Project Objectives
Inspect and clean raw taxi trip data for quality and consistency

Perform exploratory data analysis (EDA) to uncover patterns and anomalies

Conduct hypothesis testing to validate assumptions

Build regression models to predict fare amounts and tip behavior

Communicate findings through visualizations and stakeholder-ready summaries

📁 Dataset Overview
Attribute	Description
Name	2017_Yellow_Taxi_Trip_Data.csv
Source	NYC Taxi & Limousine Commission (TLC)
Rows	408,294 taxi trips
Columns	18 features including timestamps, fares, tips, and trip metrics
🧰 Tools & Technologies
Python 3.x

pandas – Data manipulation

NumPy – Numerical operations

matplotlib & seaborn – Data visualization

scikit-learn – Regression modeling

Jupyter Notebook – Interactive development

🔍 Workflow Summary
1. 📥 Data Import & Initial Exploration
Loaded CSV data using pandas

Inspected structure, column types, and sample records

2. 🧹 Data Cleaning
Identified and removed outliers in trip_distance and total_amount

Handled missing values and inconsistent entries

Converted datetime columns for time-based analysis

3. 📊 Exploratory Data Analysis (EDA)
Distribution plots for trip_distance, fare_amount, and tip_amount

Correlation heatmaps to identify key relationships

Grouped analysis by payment_type, passenger_count, and vendor_id

4. 📐 Hypothesis Testing
T-tests to compare average tips between payment types

ANOVA to assess fare variation across passenger counts

Chi-square tests for categorical relationships (e.g., payment type vs vendor)

5. 📈 Regression Modeling
Built multiple linear regression models to predict:

total_amount based on trip metrics

tip_amount based on payment type and passenger count

Evaluated models using R², RMSE, and residual plots

6. 📊 Visualization & Communication
Created bar charts, boxplots, and scatter plots to support findings

Summarized insights in stakeholder-friendly markdown reports

🧠 Key Insights
Outliers in distance and fare values skewed averages and required removal

Credit card payments consistently yielded higher tips

Trip distance and fare amount showed strong linear correlation

Passenger count had minimal impact on fare prediction

Regression models achieved R² > 0.85, indicating strong predictive power

🔮 Future Enhancements
Integrate geospatial analysis using pickup/dropoff coordinates

Apply clustering to identify trip patterns by time and location

Deploy models via Flask or Streamlit for interactive dashboards

Compare Yellow Taxi data with Uber/Lyft datasets for competitive insights


✨ Author
Adhityan R 
