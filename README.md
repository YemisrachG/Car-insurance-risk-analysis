
# 🚗 AlphaCare Insurance Solutions (ACIS) – Car Insurance Risk & Marketing Analytics

## 📌 Project Overview

This project is part of AlphaCare Insurance Solutions' (ACIS) data-driven initiative to enhance pricing strategy and customer segmentation in the South African auto insurance market. By analyzing historical car insurance claim data.

 Aim of project

- Identify **low-risk customer segments**.
- Optimize **insurance premiums** using data-driven models.
- Support targeted marketing and competitive pricing strategies.
- Discover **geographic and behavioral patterns** in insurance claims.
---
## 🧪 Methodology

### Tools & Libraries
- **Python**: Core language for analysis.
- **Pandas & NumPy**: Data manipulation.
- **Matplotlib & Seaborn**: Visualizations.
- **Scikit-learn** (upcoming): Predictive modeling.
- **Jupyter Notebook**: Interactive analysis.
- **Oracle Database / SQL**: Data storage and retrieval.

### Analytical Steps
1. **Data Summarization**
   - Computed descriptive statistics for `TotalPremium`, `TotalClaim`, etc.
   - Validated and formatted data types (e.g., dates, categorical features).

2. **Data Quality Assessment**
   - Identified and addressed missing values.
   - Ensured schema consistency.

3. **Univariate Analysis**
   - Histograms for numerical variables.
   - Bar plots for categorical variables (`CoverType`, `AutoMake`, `ZipCode`).

4. **Bivariate / Multivariate Analysis**
   - Correlation heatmaps.
   - Scatter plots of claims vs. premiums segmented by `ZipCode`.

5. **Outlier Detection**
   - Used box plots to detect and review outliers in key numerical fields.

6. **Data Visualization**
   - Created clear, insightful visuals to support data exploration and business decisions.
---
## 📊 Key Insights 

- Certain zip codes consistently show **lower claim frequencies**—potential targets for **premium discounts**.
- **Third-party only cover types** had lower average claims but higher volatility.
- Specific auto makes exhibit **higher claim rates**, which can inform risk loading strategies.
