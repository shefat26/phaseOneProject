# Aviation Accident Analysis

## Project Overview
This project focuses on analyzing aviation accident data to help a company make informed decisions as they expand into the aviation industry. The primary goal is to determine which aircraft are the lowest risk for the company to purchase and operate for commercial and private enterprises.

## Business Problem Statement
Your company is expanding into new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises but do not know anything about the potential risks of aircraft.

## Task
You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor.

## Questions Addressed
- **What types of flights have the highest average fatalities?**
- **What effect on safety do engines have, and how much is this affected by weather?**
- **Which makes and models have the lowest risk for commercial ventures?**

---

## Files in This Repository

### 1. `FinalWork.ipynb`
This Jupyter Notebook contains the analysis and insights derived from the aviation accident dataset. Key details:
- **Total cells**: 116  
- **Code cells**: 84  
- **Markdown cells**: 32  

The analysis includes answering key business questions, visualizations, and actionable recommendations.

### 2. `Aviation_Accident_Fixed_Database.csv`
This dataset contains detailed aviation accident records with the following columns:
- **Investigation**: Type of investigation conducted.  
- **Event_Date**: Date of the event.  
- **Severity**: Severity level of the accident.  
- **Aircraft_damage**: Level of damage sustained by the aircraft.  
- **Aircraft_Category**: Category/type of aircraft.  
- **Make**: Manufacturer of the aircraft.  
- **Model**: Specific model of the aircraft.  
- **Engines**: Number of engines.  
- **Engine_Type**: Type of engine.  
- **Purpose**: Purpose of the flight (e.g., commercial, private).  
- **Fatal**: Number of fatalities.  
- **Serious**: Number of serious injuries.  
- **Minor**: Number of minor injuries.  
- **Uninjured**: Number of uninjured individuals.  
- **Weather**: Weather conditions during the event.  
- **Event_Year**: Year of the event.  

### 3. `Aviation Accident Database Tableau Dashboards.twbx`
This Tableau workbook contains interactive dashboards created to visualize the insights from the aviation accident dataset. It includes:
- Trends in aviation accidents over time.  
- Analysis of accident severity by weather conditions.  
- Insights into aircraft makes and models with the lowest risks.  

---

## How to Use

### Jupyter Notebook
1. Open the `FinalWork.ipynb` file using Jupyter Notebook or JupyterLab to explore the analysis.
2. Install required dependencies using the package list included in the notebook.

### Dataset
Load `Aviation_Accident_Fixed_Database.csv` into your preferred data analysis tool (e.g., Python, R, Tableau) for additional exploration.

### Tableau Dashboard
Open the `Aviation Accident Database Tableau Dashboards.twbx` file in Tableau Desktop to interact with the visualizations.

---

## Key Insights
- Identified flight types with the highest average fatalities.  
- Analyzed the impact of engine type and weather on accident severity.  
- Recommended specific makes and models with low-risk profiles for purchase.  

---

## Requirements

### Software
- **Python 3.8+**  
- **Jupyter Notebook**  
- **Tableau Desktop**  

### Python Libraries
- `pandas`  
- `matplotlib`  
- `seaborn`  
- `numpy`  

---

## Conclusion
This project provides actionable insights into aviation safety, aiding decision-making for purchasing low-risk aircraft for commercial ventures. The combination of data analysis and visualization helps in addressing the business questions effectively.
