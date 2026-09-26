# Logistics Data Analyst Internship

Projects and tasks completed during my Logistics Data Analyst Internship. Each week builds on the previous one, forming an end-to-end analytics workflow — from strategic planning through data cleaning, exploratory analysis, and predictive modeling — using a simulated logistics/supply chain scenario (**SwiftCart Logistics**, a mid-size 3PL managing warehousing and last-mile delivery).

## Repository Contents

| File | Week | Description |
|---|---|---|
| `Logistics_Strategic_Planning_Report.docx` | Week 1 | Strategic planning and data exploration — defines the logistics scenario, KPIs, and an end-to-end analytical roadmap |
| `Logistics_Data_Cleaning_Report.docx` | Week 2 | Data collection, cleaning, and preprocessing pipeline for logistics data |
| `Logistics_EDA_Visualization_Report.docx` | Week 3 | Exploratory data analysis and visualization of a simulated shipment dataset |
| `Logistics_Predictive_Modeling_Report.docx` | Week 4 | Predictive modeling (delivery time forecasting) and optimization strategies |

## Project Overview

### Week 1 — Strategic Planning and Data Exploration

Defines a logistics scenario centered on inventory management, route optimization, and supply chain integration. Identifies key logistics KPIs and lays out a 5-phase analytical roadmap, with Python pseudocode for demand forecasting, delivery-zone clustering, and route optimization.

### Week 2 — Data Collection, Cleaning, and Preprocessing

Simulates a real-world logistics dataset and documents a full preprocessing pipeline: handling missing values, removing duplicates, detecting and treating outliers using the IQR method, and normalizing/encoding features. Includes pandas and scikit-learn code for each step, with a reflection on how data quality affects downstream analytics.

### Week 3 — Advanced Data Analysis and Visualization

Generates a 5,000-record simulated shipment dataset and performs exploratory analysis using pandas, matplotlib, and seaborn. Produces six visualizations covering distributions, trends, relationships, correlations, and regional comparisons, and identifies operational patterns related to delivery performance, transportation mode, and regional bottlenecks.

### Week 4 — Predictive Modeling and Optimization

Trains and compares four regression models — Linear Regression, Decision Tree, Random Forest, and Gradient Boosting — to forecast delivery time using RMSE, MAE, R², and 5-fold cross-validation. Tunes the Gradient Boosting model using grid search and translates its feature-importance insights into three optimization strategies: dynamic delivery-window setting, a mode-shift rule for high-risk shipments, and risk-based resource allocation.

## Tools & Libraries

`Python` · `pandas` · `numpy` · `scikit-learn` · `matplotlib` · `seaborn`

## Notes

All datasets used are simulated or hypothetical, built to reflect realistic logistics data patterns for learning and demonstration purposes. Each report is a standalone Word document (`.docx`) containing methodology, Python code, visualizations, and analytical recommendations.
