# 📉 Corporate Bankruptcy Analysis and Clustering Using R

## Project Overview
 
This project analyzes financial data from corporations to identify patterns associated with business failure and bankruptcy. Using statistical analysis and machine learning techniques in R, the project explores financial indicators such as leverage ratios, profitability, and other financial metrics to understand how companies differ between those that remain operational and those that fail.

The analysis applies exploratory data analysis, feature engineering, and clustering techniques to segment companies into groups based on financial characteristics. The goal is to detect underlying patterns that may help identify companies at higher risk of bankruptcy.

This project demonstrates an end-to-end data science workflow including data preparation, statistical analysis, machine learning modeling, visualization, and interpretation of results.

---

## Objectives

- Analyze financial indicators associated with corporate bankruptcy
- Perform exploratory data analysis on company financial data
- Engineer new variables to improve analytical insights
- Apply clustering algorithms to group companies by financial characteristics
- Compare clusters of surviving and failed companies
- Visualize patterns in financial performance over time

---

## Dataset

The dataset contains financial information from companies across multiple years, including variables related to profitability, leverage, and financial stability.

Typical variables include:

| Variable | Description |
|--------|-------------|
| Profit Margin | Measures company profitability |
| Leverage Ratio | Indicates company debt relative to equity |
| Status | Indicates whether a company is alive or failed |
| Year | Financial reporting year |
| Financial Indicators | Additional accounting and performance metrics |

These variables are used to analyze corporate financial health and identify patterns linked to bankruptcy.

---

## Methodology

### Exploratory Data Analysis (EDA)

Initial analysis explores the structure of the dataset and financial characteristics of companies. The process includes:

- Summary statistics
- Distribution analysis of financial ratios
- Correlation analysis
- Outlier detection
- Visualization of financial trends

This step provides insight into how financial indicators differ between successful and failed companies.

---

### Feature Engineering

Additional variables are created to enhance model interpretability and improve analytical insights. Feature engineering may include:

- Financial ratio transformations
- Normalization or scaling
- Derived financial indicators
- Handling missing or extreme values

These engineered variables help reveal deeper relationships in the data.

---

### Clustering Analysis

Clustering techniques are applied to group companies based on financial characteristics. This approach helps identify segments of companies that share similar financial profiles.

The clustering process includes:

- Data standardization
- Selection of relevant financial variables
- Application of clustering algorithms (e.g., K-Means)
- Visualization of clusters
- Comparison of clusters by bankruptcy status

The resulting clusters highlight differences between financially stable companies and those that failed.

---

### Visualization

Data visualizations are used extensively to interpret patterns and communicate findings. Common visualizations include:

- Scatter plots
- Cluster visualizations
- Distribution charts
- Financial ratio comparisons
- Year-based trend analysis

These visualizations make it easier to interpret complex financial relationships.

---

## Key Insights

The analysis reveals meaningful differences between companies that survive and those that fail. Financial indicators such as profitability and leverage often play a significant role in determining financial stability.

Clustering analysis helps reveal groups of companies with similar financial behaviors, providing insights into patterns that may precede bankruptcy.

Understanding these patterns can support financial risk assessment and early warning systems for corporate distress.

---

## Technologies Used

- R
- RStudio
- tidyverse
- ggplot2
- caret
- clustering algorithms (K-Means)
- statistical analysis techniques


---

## Future Improvements

Possible improvements for this project include:

- Bankruptcy prediction using logistic regression
- Random forest classification models
- Neural network prediction models
- Time-series financial risk analysis
- Feature selection and dimensionality reduction
- Advanced clustering methods

These enhancements could improve predictive capabilities and deepen financial risk insights.

---

## Author

Daniel Miranda Ruiz  
PhD Data Science | Data Analytics | Machine Learning | Financial Modeling
