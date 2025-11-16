# FIFA Player Statistical Analysis 

## Overview
This project analyzes a comprehensive dataset of **18,207 FIFA players**, containing attributes such as demographics, performance ratings, skill metrics, wages, physical attributes, and player market value. The goal is to apply **advanced statistical techniques** to uncover meaningful insights about player performance, valuation, demographic patterns, and skill relationships.

The project demonstrates detailed statistical analysis including distribution study, outlier detection, hypothesis testing, correlation, confidence intervals, and validation of the **Central Limit Theorem**.

---

## Objectives
The objective is to extract actionable insights by applying both **exploratory data analysis (EDA)** and **statistical methods** to evaluate:

- Outliers in player wages  
- Distribution of player potential (normality checks, skewness, fitting)  
- Comparison between Normal and Student’s t-distributions  
- Standardization and comparison with the standard normal distribution  
- Confidence intervals for Potential, Wage, and Weight  
- Central Limit Theorem validation using sample means  
- Correlation between Potential and Wage  
- Age distribution across playing positions  
- Top nationalities represented in the dataset  
- Skill ratings influencing Overall and Potential  
- Physical attributes differences across positions (ANOVA)  
- Wage variation across clubs  
- Potential growth analysis (Potential − Overall)  
- Hypothesis testing on International Reputation vs. Wage  

One notable insight: **Players with higher potential earn significantly higher wages**, showing strong market alignment with future performance capacity.

---

## About the Data
The dataset contains detailed player information sourced from a football simulation game.  
Each row represents one professional football player.

- **Rows:** 18,207  
- **Columns:**  Multiple performance, demographic, financial, and physical metrics  
- **File Used:** `Game.xlsx`  
- **Sheet Name:** `Game_data`

---

## Data Information

### **Key Columns**
- **ID** – Unique player ID  
- **Name** – Player’s full name  
- **Age** – Age of the player  
- **Nationality** – Country of origin  
- **Overall** – Current performance rating  
- **Potential** – Maximum achievable performance  
- **Club** – Club currently signed to  
- **Wage** – Weekly wage (e.g., €200K, €1M)  
- **Value** – Estimated market value  
- **Weight** – Weight in lbs  
- **Height** – Player height  
- **Position** – Playing position (ST, GK, CM, LW, RW, etc.)  
- **Skill Attributes** – Passing, Dribbling, Shooting, etc.  
- **Contract Information** – Duration and transfer status  

---

## Cleaning Steps Performed
- Converted **Wage** values from text (e.g., “€200K”, “€1M”) to numeric  
- Extracted numeric values from **Weight** (e.g., “150lbs”)  
- Standardized column formats  
- Removed or treated missing values  
- Converted text-based numeric fields into appropriate numeric types  
- Cleaned skill and physical attributes for consistent processing  

---

## Impurities Removed
- Inconsistent financial formats resolved  
- Weight and Wage standardized into numeric values  
- Removed irrelevant characters from numerical columns  
- Fixed formatting inconsistencies in height, weight, and financial fields  
- Dropped or imputed missing/irrelevant values  

---

## Insights

- **Wage Outliers:** Only a small cluster of elite players dominate top wage brackets  
- **Potential Distribution:** Near-normal with slight left skew  
- **Correlation:** Strong positive correlation between Potential and Wage  
- **Age by Position:** Goalkeepers tend to be older; forwards are typically younger  
- **Top Nationalities:** Reflect strong football nations dominating professional leagues  
- **Skill Influence:** Finishing, Dribbling, and Passing strongly affect Overall and Potential  
- **Club-Level Wages:** High-wage clubs align with high-performance squads  
- **Potential Growth:** Younger players, especially forwards, show higher development capacity  
- **Hypothesis Result:** Players with higher International Reputation earn significantly more  

---

## Tools & Libraries Used
- **Python** – Core programming  
- **Pandas** – Data preprocessing & manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib & Seaborn** – Visualization  
- **SciPy** – Statistical distributions & hypothesis testing  
- **Jupyter Notebook** – Analysis environment  

