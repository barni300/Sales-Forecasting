# Sales-Forecasting

# Machine Learning Sales Forecasting for Inventory Planning

## Overview  
This project leverages **historical daily sales data (2020–2025)** to build a **365-day sales forecast**.  
The main objective is to support **inventory and purchasing planning**, ensuring the client orders the right amount of goods at the right time.  

The analysis highlights two key patterns in the data:  
- A **strong upward growth trend** in sales.  
- A **clear seasonal spike** during the **November/December holiday period**.  

---

## Key Deliverables & Analysis  

### 1. Exploratory Data Analysis (EDA)  
- Time series plots to visualize long-term growth.  
- Seasonal heatmaps to confirm yearly demand cycles.  
- Decomposition analysis to separate **trend, seasonality, and residuals**.  

### 2. Forecasting Models Compared  
- **Facebook Prophet**  
  - Captures long-term growth.  
  - Provides **confidence intervals** (expected min/max).  
- **Exponential Smoothing (Holt-Winters)**  
  - Serves as a robust baseline.  
  - Accurately models **yearly seasonal spikes**.  

### 3. Actionable Output  
- Predictions exported into **Excel files**:  
  - **Daily forecast** (next 365 days).  
  - **Monthly summary** (aggregated for easier purchasing decisions).  

---

## Tools & Libraries  

- **Python**  
- **Pandas** → data cleaning & preparation  
- **Matplotlib / Seaborn** → visualization  
- **Prophet** → machine learning time series forecasting  
- **Statsmodels (Exponential Smoothing)** → classical forecasting  
- **Jupyter Notebook** → interactive analysis  

---

## Business Value  
This project demonstrates how **machine learning + classical forecasting** can provide **actionable insights for real-world inventory management**, helping businesses:  
- Anticipate demand.  
- Reduce overstock/stockouts.  
- Plan purchases with data-driven confidence.  

---

## Project Structure  
- data/ # Raw and processed sales data
- notebooks/ # Jupyter notebooks with analysis & modeling
- forecasts/ # Output Excel files (daily & monthly forecasts)
- README.md # Project documentation
