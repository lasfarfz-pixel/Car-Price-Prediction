# Car Price Prediction Using Data Analytics and Machine Learning

## Project Overview

This project applies data analytics and machine learning techniques to predict automobile prices based on vehicle characteristics.

The analysis includes:

- Data Cleaning
- Missing Value Treatment
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Regression Modelling
- Classification Modelling
- Business Insights and Recommendations

---

## Dataset Features

The dataset contains information about:

- Engine Size
- Horsepower
- Fuel Type
- Body Style
- Drive Wheels
- Engine Type
- Fuel Consumption
- Vehicle Dimensions
- Vehicle Price (Target Variable)

---

## Project Workflow

### 1. Data Preprocessing

- Replaced missing values represented by '?'
- Converted variables to appropriate data types
- Removed records with missing target values
- Applied mean and mode imputation

### 2. Feature Engineering

- Created City Fuel Consumption (L/100km)
- Created Highway Fuel Consumption (L/100km)
- Binned horsepower into Low, Medium, and High categories
- Applied Min-Max normalization

### 3. Exploratory Data Analysis (EDA)

- Price distribution analysis
- Horsepower distribution analysis
- Price by body style comparison
- Correlation heatmap
- Outlier detection

### 4. Machine Learning Models

#### Regression Models

- Linear Regression
- Random Forest Regressor

#### Classification Model

- Logistic Regression

Vehicle prices were categorized into:

- Low
- Medium
- High

---

## Key Findings

- Engine size showed the strongest correlation with vehicle price.
- Curb weight and horsepower were also strong predictors.
- Random Forest achieved the best regression performance.
- Logistic Regression successfully classified vehicles into price categories with high accuracy.
- Premium vehicles tend to be larger, heavier, and more powerful.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Repository Contents

```text
car-price-prediction
│
├── FDA_Car_Price_Prediction.ipynb
├── README.md
└── images/
```
## My Analysis and Recommendations

Based on the results of this project, I believe that vehicle price is influenced by a combination of technical, performance, and design-related factors rather than a single feature.

The analysis showed that engine size, curb weight, and horsepower were the strongest predictors of price. This suggests that consumers are generally willing to pay a premium for larger, more powerful vehicles that offer higher performance.

From a business perspective, manufacturers and dealerships can use predictive analytics to support pricing decisions, market segmentation, and inventory planning. Understanding which features contribute most to vehicle value can help organizations design products that better match customer expectations and market demand.

### Recommendations

- Use machine learning models such as Random Forest to support pricing decisions, as they can capture complex relationships between vehicle characteristics and price.
- Focus on key value-driving features such as engine size, horsepower, and vehicle weight when developing premium vehicle segments.
- Combine predictive model outputs with market knowledge rather than relying solely on automated predictions.
- Collect additional variables such as vehicle age, mileage, brand reputation, maintenance history, and market demand to improve future model performance.
- Apply cross-validation and hyperparameter tuning in future work to further improve model reliability and generalisation.

### Personal Reflection

This project strengthened my understanding of the complete data analytics workflow, including data cleaning, feature engineering, exploratory data analysis, machine learning model development, and business interpretation.

One of the most valuable lessons from this project was that building a predictive model is not only about achieving high accuracy. It is equally important to understand the business context, evaluate model limitations, and communicate findings in a way that supports decision-making.

The project also demonstrated how data-driven approaches can be used to solve real-world business problems and generate actionable insights from data.
---

## Author

Lasfar fatima ezzahra
