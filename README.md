# Airbnb Europe Price Analysis

## Project Overview
This project analyzes Airbnb listings across European cities with the goal of understanding pricing behavior and the factors that influence it. The analysis follows a complete data science workflow including exploratory data analysis (EDA), data cleaning, feature engineering, and conclusions.

---

## Dataset
- **Source:** Kaggle – Airbnb Cleaned Europe Dataset  
- **Observations:** 41714 listings  
- **Features:** Numerical and categorical variables related to price, room type,
  capacity, location, and host characteristics

---

## Methodology

### 1. Exploratory Data Analysis
- Dataset overview and structure
- Missing values and duplicate checks
- Statistical summaries of numerical features
- Visual analysis:
  - Price distribution
  - Price vs room type
  - Price vs distance from city center
  - Correlation matrix of numerical features

---

### 2. Data Cleaning
- Handling missing values:
  - Numerical features → median imputation
  - Categorical features → mode imputation
- Removal of invalid observations (non-positive prices or capacity)
- Outlier handling using the 99th percentile of price
- Removal of unnecessary columns (e.g., *Business*)

---

### 3. Feature Engineering
New features were created to enhance interpretability and analysis:
- **Price per Person**
- **Above City Average Price**
- **Distance Category** (Central / Medium / Far)
- **Value for Money** (Good Value / Expensive)

---

## Key Insights
- Entire home/apartment listings are generally more expensive than private or shared rooms
- Listings closer to city centers tend to have higher prices
- Price distributions are right-skewed with notable outliers
- Feature engineering enables fairer and more interpretable comparisons between listings

---

## Tools & Libraries
- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

---

## Conclusion
This project demonstrated the given dataset using the Airbnb homes dataset. Graphs and matrices were presented to show the difference in prices depending on different circumstances. New features were added that will affect the dataset and help to better see the features dependent on price.

---

## Author
**Sam Danielyan**