# Aerofit - Customer Profiling and Probability Analysis

## Project Overview
Aerofit, a leading brand in fitness equipment, aims to enhance its customer recommendations by understanding the characteristics of customers who purchase specific treadmill models. This project performs descriptive statistics and probability analysis on the dataset collected from Aerofit customers. By analyzing customer demographics and behaviors, this study helps identify key factors influencing product choices, offering valuable insights for marketing and sales strategies.

## Business Problem
The market research team at Aerofit wants to identify characteristics that define the target audience for each type of treadmill offered by the company (KP281, KP481, KP781). The goal is to offer better recommendations to new customers and optimize the product marketing strategy. This project includes:
- **Descriptive Analytics**: Identifying customer profiles for each treadmill.
- **Probability Analysis**: Computing marginal and conditional probabilities to uncover insights that impact the business.

## Dataset Description
The dataset includes customer information gathered over the last three months from customers who purchased treadmills from Aerofit stores. The features include:
- **Product Purchased**: KP281, KP481, KP781
- **Age**: Age of the customer
- **Gender**: Male or Female
- **Education**: Education level in years
- **MaritalStatus**: Single or Partnered
- **Usage**: Average number of times the customer plans to use the treadmill per week
- **Income**: Annual income in $
- **Fitness**: Self-rated fitness on a 1-5 scale
- **Miles**: Average number of miles the customer expects to walk/run per week

## Project Objectives
1. **Data Exploration**:
   - Import and explore the dataset to understand the structure, types of attributes, and any missing data.
   - Detect outliers and analyze distributions using methods like boxplots and histograms.
  
2. **Univariate & Bivariate Analysis**:
   - **Univariate**: Use countplots, histograms, and distplots to analyze individual variables.
   - **Bivariate**: Analyze relationships between variables (e.g., age vs product purchased) using boxplots, pairplots, and heatmaps.
  
3. **Contingency Tables**:
   - Create two-way contingency tables to calculate marginal and conditional probabilities.
   - Derive actionable business insights based on the analysis.

4. **Correlation Analysis**:
   - Explore correlations between continuous variables using heatmaps and pairplots.

5. **Business Insights and Recommendations**:
   - Provide data-driven recommendations on customer segmentation and marketing strategies based on customer profiles and product preferences.
     
## Tools & Technologies
- Python
- Pandas for data manipulation
- Matplotlib & Seaborn for data visualization
- Jupyter Notebook for analysis and presentation of results

## Insights & Recommendations
Based on the analysis, the following key business insights can be derived:
- Marginal and conditional probabilities reveal which demographic factors most influence the purchase of specific treadmill models.
- Profiling customers based on age, gender, income, and fitness can assist in tailoring marketing campaigns.
- Correlation between customer usage patterns and product preferences can inform product development and customer recommendations.

### Conclusion
This project aims to provide actionable business recommendations by profiling customers and identifying the factors influencing the purchase of different treadmill models. By using data-driven insights, Aerofit can enhance its marketing strategy and improve customer satisfaction.
