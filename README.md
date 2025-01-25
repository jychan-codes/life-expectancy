# Life Expectancy Prediction

This project aims to uncover key factors affecting life expectancy using real-world data. The analysis was performed using Python and multiple regression techniques to predict life expectancy based on various socio-economic and health factors.

## Description

In this project, I cleaned and preprocessed the data by:
- Handling missing values
- Removing unnecessary or irrelevant attributes
- Conducting correlation analysis to identify which factors were most strongly related to life expectancy.

Key findings from the correlation analysis include:
- **Positive Relationship**: Schooling is positively correlated with life expectancy, indicating that higher education levels are associated with longer life expectancy.
- **Negative Relationship**: Higher rates of HIV/AIDS are linked to shorter life expectancy.

I used **multiple regression** to model life expectancy predictions. This statistical method helps predict outcomes based on several factors. It allows us to determine how each factor, like schooling or HIV/AIDS, impacts life expectancy, considering the effects of other factors.

### Statistical Significance
To identify the most influential factors, I tested their statistical significance using **p-values**:
- A **p-value** less than 0.05 indicates a statistically significant relationship.
- **Schooling** and **adult mortality** both had p-values below 0.05, meaning they are important predictors of life expectancy.

## Features

- Data cleaning and preprocessing
- Correlation analysis to identify key factors
- Multiple regression model for life expectancy prediction
- Statistical analysis using p-values to identify significant predictors

## Requirements

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Statsmoodels

## Usage

1. Open the life_expectancy_prediction.ipynb Jupyter notebook.
2. Run the cells to load, clean, and preprocess the data.
3. Perform correlation analysis and build the multiple regression model.
4. Interpret the results, including which factors are statistically significant and how they affect life expectancy.








