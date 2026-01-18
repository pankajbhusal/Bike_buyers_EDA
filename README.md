# Bike_buyers_EDA

# Bike Buyers Exploratory Data Analysis

## Author
Pankaj Bhusal  
Student ID: 3081563  
March 2025

---

## Project Description
This project focuses on performing an exploratory data analysis (EDA) on the Bike Buyers dataset using R and R Markdown.  
The aim of the analysis is to explore customer demographics and purchasing behaviour and to identify factors that influence whether a customer is likely to purchase a bike.

The project includes data cleaning, summary statistics, visual exploration, and correlation analysis to better understand the dataset.

---

## Dataset Information
The Bike Buyers dataset contains information about 1000 customers and includes demographic, socio-economic, and behavioural variables such as age, income, gender, marital status, number of cars, commute distance, and bike purchasing status.

---

## Data Cleaning and Preparation
Before analysis, the dataset was cleaned and prepared:
- Missing categorical values were filled using the most frequent value (mode)
- Missing numerical values were replaced using the median
- Categorical variables were converted into appropriate formats
- A cleaned version of the dataset was saved for analysis

These steps ensured the dataset was consistent and suitable for analysis.

---

## Analysis and Visualisation
The analysis includes:
- Summary statistics for both numerical and categorical variables
- Visualisations such as pie charts, bar charts, histograms, scatter plots, boxplots, and density plots
- Grouping customers into income ranges to examine purchasing patterns
- Correlation analysis to study relationships between key variables and bike purchasing behaviour

---

## Key Findings
Some important observations from the analysis include:
- Customers with higher income are more likely to purchase a bike
- Owning more cars and having more children reduces the likelihood of purchasing a bike
- Age shows a weak negative relationship with bike purchasing
- Middle-to-high income groups show higher purchase rates

---

## Files Included in This Repository
- `Bike_Buyers_Analysis.Rmd` – R Markdown file containing the analysis and code
- `Bike_Buyers_Analysis.pdf` – Final knitted report
- `bike_buyers.csv` – Original dataset
- `bike_buyers_cleaned.csv` – Cleaned dataset used for analysis
- `.gitignore` – Git ignore file

---

## How to Run the Project
1. Open `Bike_Buyers_Analysis.Rmd` in RStudio  
2. Install required R packages such as `ggplot2` and `dplyr`  
3. Click **Knit → PDF** to generate the report  

---

## Tools Used
- R
- R Markdown
- ggplot2
- dplyr
- Git and GitHub

---

## Notes
This project was completed as part of a fourth-year data analytics coursework assignment.
