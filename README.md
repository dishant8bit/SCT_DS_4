# 🚦 Road Traffic Accident Data Analysis (EDA)

## 📌 Project Overview
This project focuses on performing data cleaning and exploratory data analysis (EDA) on a road traffic accident dataset to identify patterns related to road conditions, weather, time of day, and accident locations.

The analysis aims to uncover key risk factors contributing to traffic accidents and provide actionable safety insights. This project demonstrates practical data analysis skills including data preprocessing, feature engineering, visualization, and insight generation — making it suitable for GitHub portfolios, internships, and entry-level data analyst roles.


## 🗂 Dataset Description
The dataset contains detailed records of road traffic accidents, including environmental conditions, driver information, accident severity, and location details.

### 🔑 Key Columns
- Time – Time of accident  
- Day_of_week – Day accident occurred  
- Age_band_of_driver – Driver age group  
- Sex_of_driver – Driver gender  
- Driving_experience – Experience level  
- Type_of_vehicle – Vehicle involved  
- Area_accident_occured – Accident location type  
- Road_surface_conditions – Road condition at time of accident  
- Weather_conditions – Weather during accident  
- Light_conditions – Lighting environment  
- Number_of_vehicles_involved – Vehicles in accident  
- Number_of_casualties – People injured  
- Cause_of_accident – Reported cause  
- Accident_severity – Severity level  


## 🆕 Engineered Features
- Hour – Extracted from accident time  
- Time_of_day – Categorized as Morning, Afternoon, Evening, Night  


## 🛠 Tools & Libraries Used
- Python  
- Pandas — Data manipulation and preprocessing  
- NumPy — Numerical operations  
- Matplotlib — Data visualization  
- Seaborn — Statistical visualization  
- Jupyter Notebook — Analysis environment  


## 🧹 Data Cleaning Steps
- Replaced placeholder values with proper missing values  
- Removed incomplete records from key analysis columns  
- Converted time to datetime format  
- Extracted hour from time  
- Created time-of-day categories  
- Standardized categorical values  


## 🔍 Exploratory Data Analysis (EDA)

### 🌦 Weather Impact
- Most accidents occurred during normal weather conditions  
- Rain significantly increased accident frequency  
- Extreme weather conditions showed fewer cases  

### 🛣 Road Surface Conditions
- Majority of accidents occurred on dry roads  
- Wet or damp roads were the second largest contributor  
- Flooded and snowy roads were rare  

### 🕒 Time of Day Patterns
- Afternoon recorded the highest accident frequency  
- Evening and morning followed closely  
- Night had the lowest accident occurrence  

### 📍 Accident Hotspots
- Office areas and residential areas showed high accident concentration  
- Urban zones experienced more accidents than rural areas  

### ⚠ Accident Severity Factors
- Weather and road conditions influenced severity distribution  
- Higher vehicle involvement increased casualty risk  


## 📈 Visualizations Included
- Accidents by weather condition  
- Accidents by road surface condition  
- Accidents by time of day  
- Top accident hotspot locations  
- Accident severity comparisons  
- Correlation heatmap of numerical factors  


## 💡 Key Safety Insights
- Peak traffic hours increase accident probability  
- Wet roads significantly elevate risk  
- Urban environments have higher accident concentration  
- Multi-vehicle accidents increase injury severity  


## ▶️ How to Run the Project
1. Clone the repository
git clone https://github.com/dishant8bit/SCT_DS_4.git


2. Install dependencies
pip install -r requirements.txt


3. Launch Jupyter Notebook
jupyter notebook


4. Run the analysis notebook


## 🚀 Future Improvements
- Build accident severity prediction model  
- Add interactive dashboards (Streamlit / Power BI)  
- Perform statistical hypothesis testing  
- Geospatial hotspot mapping  
- Real-time traffic risk prediction  


## 👤 Author
Dishant Kudtarkar  
Aspiring Data Analyst | Python | Data Visualization | Machine Learning

