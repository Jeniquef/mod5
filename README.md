# Pymaceuticals Inc.

## Overview
This project analyzes the effectiveness of various drug regimens in reducing tumor volume in mice over a 40-day study period. The primary goal is to identify the most effective treatments and explore correlations between tumor volume, drug regimens, and other factors such as mouse weight.


## Key Findings
- **Capomulin and Ramicane** were identified as the most effective treatments in reducing tumor volume.
- Tumor volume for mouse S1-85 (Capomulin regimen) decreased significantly from 45 mm³ to approximately 25 mm³ over the 40-day period.
- There is a positive correlation between a mouse's weight and its initial tumor volume, suggesting that heavier mice tend to develop larger tumors.


Ensure the following data files are available:
1. `Mouse_metadata.csv`
2. `Study_results.csv`


**Data Cleaning:**
   - Duplicate rows are identified and removed based on `Mouse ID` and `Timepoint`.
   - The resulting DataFrame contains unique entries for analysis.

 **Data Validation:**
   - The total number of unique mice is confirmed before and after cleaning.

## Analysis
### 1. **Summary Statistics**
   - Generated a summary table for each drug regimen, including:
     - Mean, Median, Variance, Standard Deviation, and SEM of tumor volume.

### 2. **Bar and Pie Charts**
   - **Bar Chart:**
     - Visualized the total number of Mouse ID/Timepoints for each drug regimen.
   - **Pie Chart:**
     - Illustrated the distribution of male vs. female mice.

### 3. **Quartiles, Outliers, and Boxplots**
   - Calculated the interquartile range (IQR) and identified outliers for tumor volume in four drug regimens:
     - Capomulin, Ramicane, Infubinol, and Ceftamin.
   - Created box plots to show the distribution of tumor volumes for each treatment.


### 4. **Line and Scatter Plots**
   - **Line Plot:**
     - Visualized tumor volume over time for a single mouse (S185) treated with Capomulin.
   - **Scatter Plot:**
     - Plotted mouse weight vs. average tumor volume for the Capomulin regimen.

### 5. **Correlation and Regression**
   - Calculated the correlation coefficient (ρ = 0.84) and performed a linear regression analysis for mouse weight and average tumor volume (Capomulin regimen).
   - Visualized the regression line and scatter plot to demonstrate the relationship.


## Conclusion
The analysis highlights Capomulin and Ramicane as the most promising drug regimens in reducing tumor volume. Additionally, mouse weight serves as an important predictive factor for tumor size, providing insights for future studies.



