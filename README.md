# Real-Estate-Market-Analysis-And-Prediction-SQL-And-Python-Project

## Overview

This project explores **USA real estate market trends** using **SQL (SQLite)** and **Python (Pandas, Matplotlib, Seaborn)**. The analysis uncovers how factors like **location, number of bedrooms, garage size, pools, build year, and distance to the city center** affect home prices.

The goal is not just to explore — but to predict:  
**Which homes are undervalued and likely to grow in future market value?**

---

##  Project Objectives

- Identify key drivers of house prices
- Uncover market trends based on home features
- Visualize insights for investors & analysts
- Predict **growth potential** of individual homes

---

## Project Links
**Kaggle Notebook:** [View Full Project with Code & Charts](https://www.kaggle.com/code/abusufianorg/real-estate-insights-sql-python)

![Image](https://github.com/user-attachments/assets/a1a29157-ea59-4728-9c01-a132e3ff712f)

---

## Key Analyses & Insights

1. **Top 10 Most Expensive Houses**
2. **Average Price by Bedroom Count**
3. **Price Trend Over Build Year**
4. **3D Surface: Distance to Center vs Price**
5. **Garage Size vs Price**
6. **Pool vs No Pool — Price Impact**
7. **Feature Correlation Heatmap**
8. **Price Distribution Histogram**
9. **Top 10 Houses by Location Score**
10. **Decade-wise House Construction Trend**
11. **Growth Potential Score** – *Predicting which houses will likely appreciate*

---

##  Predicting Growth Potential

To go beyond standard EDA, we built a custom **Growth Potential Score** using:

- High Location Score  
- Presence of Garden / Pool 
- Garage Size 
- Low Price per Square Foot   


Growth_Score = (Location_Score * 0.4)
             + (20 if Garden)
             + (15 if Pool)
             + (Garage_Size * 0.1)
             - (Relative Price per SqFt)

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| `SQLite` | SQL querying for data slicing & aggregation |
| `Python` | Analysis, modeling, and visualization |
| `Pandas` | Data wrangling |
| `Matplotlib` & `Seaborn` | Charts & statistical graphics |
| `Kaggle Notebook` | Project execution & storytelling |

---

## Insight: Homes with strong location and good features — but currently undervalued — show the highest potential ROI.

---

## Project Structure
real-estate-analysis/
├── Row data/
│   └── usa_real_estate.csv

├── notebook/
│   └── USA-real-estate-insights-sql-python.ipynb

├── outputs/
│   └── visualizations.png

├── README.md

└── requirements.txt

---

## Final Reflection
This project combined SQL logic with Python storytelling to answer real questions that buyers, sellers, and investors care about.

> Data doesn't lie. And in real estate — price ≠ size, it's about features, feel, and foundation.

