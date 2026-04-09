# Road Accident Data Analysis & Prediction  

## Project Overview  

Road accidents are a major public safety concern in India, especially in densely populated urban areas. This project performs an end-to-end data analysis and machine learning workflow to understand accident patterns, identify key causes, and predict accident trends.  

The project combines data cleaning, exploratory data analysis (EDA), visualization, and machine learning to extract meaningful insights from road accident data.  

---

## Objectives  

- Analyze accident distribution across major cities  
- Identify key causes and contributing factors of accidents  
- Perform exploratory data analysis (EDA) with insights  
- Understand accident outcomes (injuries, fatalities, etc.)  
- Build a machine learning model to analyze accident patterns  
- Derive actionable insights to improve road safety  

---

## Dataset  
  
- **Records:** ~9550 rows  
- **Features:**  
  - Million Plus Cities  
  - Cause Category  
  - Cause Subcategory  
  - Outcome of Incident  
  - Count  
- **Target Variable:** Accident Count / Severity (based on analysis)  

---

## Exploratory Data Analysis (EDA)  

### Key Insights  

- Cities like **Delhi and Chennai** report the highest number of accidents  
- Accident distribution is uneven across cities  
- Traffic violations and road conditions are major contributors  
- Most accidents result in **injuries rather than fatalities**  
- Minor and total injuries are more frequent than deaths  

EDA was supported using bar charts, pie charts, and heatmaps with business-focused interpretations.  

---

## Machine Learning Approach  

### Model Implemented  

- Random Forest Regressor  

### Key Techniques  

- Data cleaning and handling missing values  
- Feature encoding (Label Encoding)  
- Train-test split  
- Model training and evaluation  

### Model Performance  

- Random Forest effectively captured accident patterns  
- Provided reliable predictions with good accuracy  
- Helped identify key influencing factors  

---

## Feature Importance  

Key factors influencing accident trends:  

- **City (Location)** → Major impact due to traffic density  
- **Cause Subcategory** → Strong influence on accident frequency  
- **Cause Category** → Moderate impact  
- **Other factors** → Lesser contribution  

These features are critical in understanding accident risks.  

---

## Business Usage  

This project can help:  

- Government authorities improve road safety policies  
- Traffic departments identify high-risk areas  
- Urban planners enhance road infrastructure  
- Awareness campaigns target major accident causes  

---

## Limitations  

- Based on historical (static) data  
- Does not include real-time traffic or behavioral data  
- Limited features (no driver demographics or vehicle conditions)  
- Predictions support decisions but are not definitive  

---

## Tools & Technologies  

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## Repository Contents  

- `Road_accident.ipynb` → Complete analysis and model  
- `road_accident_data.csv` → Dataset used  
- `README.md` → Project documentation  

---

## Author  

**Vikas Gowda V**  
Aspiring Data Analyst / Data Scientist  

---

## Conclusion  

This project demonstrates how data analysis and machine learning can uncover patterns in road accidents and identify key risk factors. By combining EDA with predictive modeling, it provides valuable insights that can help improve road safety, optimize infrastructure, and support data-driven decision-making.
