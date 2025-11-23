## Healthcare Supply Chain Analytics

A comprehensive data analytics project examining hospital inventory levels, patient demand patterns, staffing workloads, financial drivers, and supply chain inefficiencies. The goal is to uncover operational bottlenecks, assess demand variability, forecast resource needs, and support data-driven decision-making within healthcare supply chain environments.

## Project Overview

Modern U.S. healthcare systems face persistent challenges such as supply shortages, rising operational costs, staff shortages, and unpredictable patient demand. This project uses real-world-inspired datasets to explore how inventory, staffing, diagnoses, procedures, and financial metrics interact.

Through exploratory analysis, visualization, and machine learning forecasting, the project identifies risks related to stockouts, over-utilized workforce capacity, high-cost inventory, and operational inefficiencies that impact patient care and financial stability

## Objectives:

1. Analyze hospital inventory levels to detect stockout risks and overstocking.

2. Evaluate staff workload through hours worked and overtime patterns.

3. Understand patient demand through diagnoses, procedures, and stay duration.

4. Examine financial expenses across procurement, transportation, labor, and storage.

5. Develop a demand forecasting model using Gradient Boosting.

6. Provide actionable recommendations to optimize healthcare supply chain operations.

## Key Analyses & Insights
Inventory Analysis:

1. Compared Current Stock with Min Required and Max Capacity to identify shortages and overstocked items.

2. Calculated total stock value to highlight high-cost items driving financial risk.

Staffing & Workload Analysis:

1. Evaluated hours worked and overtime to detect understaffing and operational strain.

2. Analyzed average patient load per staff member across departments.

Patient Demand Patterns:

1. Mapped diagnosis categories to procedures to understand clinical resource needs.

2.  Measured patient stay durations by room type to identify capacity constraints.

Financial Breakdown:

1. Assessed spending distribution across key cost categories to locate major cost drivers.

Demand Forecasting: 

1. Trained a Gradient Boosting Regressor to predict estimated demand.

2. Evaluated model accuracy using MAE and predicted-vs-actual plots.

## Skills Demonstrated
Technical Skills

1. Python, pandas, NumPy

2. Data visualization (Matplotlib, Seaborn)

3. Machine Learning (Gradient Boosting, feature engineering)

4. Data cleaning, transformation, and encoding

5. Statistical analysis & exploratory data analysis

6. Correlation analysis and KPI development

## Why This Project Matters

Hospitals across the U.S. frequently struggle with supply shortages, workforce overload, unpredictable patient volumes, and rising costs. These challenges intensified after COVID-19, exposing long-standing weaknesses in healthcare supply chains.

This project addresses these real-world issues by:

1. Identifying stockout and waste risks

2. Revealing staffing imbalances

3. Understanding patient-driven resource consumption

4. Forecasting demand for essential items

5. Evaluating financial inefficiencies

The insights created through this analysis support better decision-making in procurement, staffing, financial planning, and operational resilience.

## Areas for Improvement and Future Work

Despite generating actionable insights, several opportunities remain to expand and strengthen the analysis:

1. Richer and More Granular Data:
   
Incorporating real-time supply chain data—such as supplier lead times, shipment tracking, and consumption logs—would allow more sophisticated modeling of bottlenecks and shortages. Access to historical patient admission data and seasonality trends would also improve forecast accuracy.

2. Integration of Predictive Inventory Models:
   
While demand forecasting was initiated, adding models such as ARIMA, LSTM networks, or probabilistic safety-stock optimization could provide more reliable predictions, especially for items with volatile usage patterns.

3. Scenario and Risk Analysis:
   
Simulating disruptions (e.g., supplier delays, surges in patient volume, emergency events) would help hospitals prepare for crises—something increasingly important given workforce shortages and supply chain instability in the U.S.

4. Cost-to-Outcome Analysis:
   
Linking financial data to patient outcomes or service levels would help quantify how inventory and staffing decisions affect both care quality and operational performance.
