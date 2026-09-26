# Bookstore Sales Analysis with Python

This project was completed as part of the OpenClassrooms Data Analyst training program.

The objective was to analyze two years of online bookstore sales, evaluate commercial performance, understand customer behavior, and test relationships between customer profiles and purchasing patterns.

---

## Project Context

The analysis combines three datasets covering products, customers, and transactions. The transaction table is used as the central fact table and joined with product and customer information.

The study is split into two notebooks:

1. Business analysis and sales performance
2. Statistical analysis of customer behavior

---

## Objectives

- Clean, validate, and merge sales data
- Track revenue, orders, customers, and product performance
- Analyze monthly trends and customer concentration
- Identify atypical customer profiles
- Test relationships between age, gender, product category, purchase frequency, and basket value

---

## Tools and Technologies

- Python
- pandas and NumPy
- Matplotlib and Seaborn
- SciPy
- statsmodels
- Jupyter Notebook / Google Colab

---

## Key Results

- Revenue analyzed: approximately €12.03 million
- 687,534 products sold across 345,505 orders
- 8,600 unique customers
- Average of 2 products per order
- Four atypical high-revenue customers were isolated before the statistical tests
- Age and purchase frequency showed only a weak relationship
- Age and average basket value showed a moderate negative correlation (approximately -0.62)
- Product category distributions differed significantly by customer profile, including age and gender

---

## Statistical Methods

- Chi-square test of independence
- Pearson correlation analysis
- ANOVA
- Lorenz curve for revenue concentration
- Descriptive and temporal analysis

---

## Repository Structure

```text
01_business_analysis.ipynb
02_statistical_analysis.ipynb
project_presentation.pptx
requirements.txt
```

The notebooks contain executed outputs. To rerun them, provide the original project datasets and update the data paths used in the loading cells.

---

## Skills Developed

- Data cleaning and relational joins
- Exploratory data analysis
- Business KPI design
- Statistical hypothesis testing
- Customer and product analysis
- Data visualization and storytelling
