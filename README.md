## Crisis Aversion Analysis Project

### Overview
This project focuses on the comprehensive analysis of economic indicators and COVID-19 data, combining various statistical and machine learning techniques to draw meaningful insights. The analysis spans multiple stages, including data cleaning, exploratory analysis, descriptive statistics, diagnostic modeling, predictive analysis, and prescriptive recommendations. The aim is to understand the relationships between economic indicators such as GDP, GDP per capita, and the Human Capital Index, and to predict outcomes based on these indicators.

### Features
- **Data Cleaning & Preprocessing:** 
  - Collected and cleaned COVID-19 and economic data, ensuring the datasets were free of missing values and properly formatted for analysis.
  
- **Exploratory & Descriptive Analysis:**
  - Visualized the distribution of key economic indicators across different countries using pie charts, bar charts, and correlation matrices.
  - Implemented SVM classification to distinguish high GDP countries and evaluated model performance using ROC curves.

- **Diagnostic Analysis:**
  - Conducted cluster analysis to group countries based on GDP and GDP per capita.
  - Identified outliers and performed correlation analysis between different economic variables.

- **Predictive Modeling:**
  - Developed predictive models using Support Vector Machines (SVM) to classify countries based on economic indicators.
  - Evaluated model accuracy using metrics like ROC curves and AUC scores.

- **Prescriptive Analysis:**
  - Performed hypothesis testing and regression analysis to understand the relationships between economic indicators.
  - Provided recommendations for economic policy based on the analysis results, focusing on improving GDP and GDP per capita.

### Technologies Used
- **R Programming Language**
- **Libraries:** `readr`, `dplyr`, `ggplot2`, `cluster`, `caret`, `e1071`, `ROCR`, `lmtest`, `reshape2`, `pROC`

### How to Run
1. Clone the repository.
2. Install the necessary R libraries.
3. Run the scripts in the specified order to reproduce the analysis.

### Conclusion
This project offers a deep dive into economic and COVID-19 data, using advanced data analysis techniques to uncover patterns and relationships that can inform economic policies and decision-making. It demonstrates the power of combining data science with economic analysis to derive actionable insights.

---
