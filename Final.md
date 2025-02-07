## Data Set: 
This project analyzes the Happiness Score across different countries using various socio-economic indicators. The goal is to build a Linear Regression Model that predicts the happiness score based on features such as GDP per Capita, Social Support, Healthy Life Expectancy, and Freedom to Make Life Choice

The dataset used in this project is sourced from the World Happiness Report 2019 and contains the following key columns:

Country or Region|The country or region analyzed.

Score|The happiness score (target variable).

GDP per Capita|The economic output per person.

Social Support| The extent of social connections.

Healthy Life Expectancy| The expected years of healthy living.

Freedom to Make Life Choices| The perceived freedom in decision-making.

Generosity| The measure of charitable donations.

Perceptions of Corruption| The perceived level of government corruption.

## Objective: 
This project analyzes the Happiness Score across different countries using various socio-economic indicators. The goal is to build a Linear Regression Model that predicts the happiness score based on features such as GDP per Capita, Social Support, Healthy Life Expectancy, and Freedom to Make Life Choice


## PART 1: Data Cleaning
BData Cleaning & Preprocessing

Checked for missing values and handled inconsistencies.

Converted categorical variables (e.g., Country) into numerical codes.

Applied log transformations to skewed features (e.g., GDP per Capita).

## PART 2: Exploratory Data Analysis (EDA)

Plotted boxplots to identify outliers.

Computed correlation heatmaps to analyze feature relationships.

Checked for feature interactions (e.g., GDP × Social Support).
  
## PART 3: Modeling

Implemented a Linear Regression Model using sklearn.

Splitted data into Training (75%) & Testing (25%).

Evaluated model performance using:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R-squared (R²)

Adjusted R²

Residual Analysis & Model Improvement

Plotted residual distributions to assess errors.

Identified and removed outliers.

Tested the impact of feature interactions.

# Findings
GDP per Capita and Social Support are the strongest predictors of happiness.

Feature interactions (GDP × Social Support) improved model accuracy.

Residuals were slightly skewed, indicating possible non-linearity.

R² of the final model was ~0.61, suggesting moderate predictive power.
