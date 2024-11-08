# Bridge-Deterioration-Predictive-Model

## Overview

The **Bridge-Deterioration-Predictive-Model** is a data science project developed for the Statistics for AI and Data Science coursework. The objective is to predict the current condition of bridges using key variables such as age, average daily traffic, percentage of truck traffic, material, and design. By applying linear regression modeling, this project evaluates the impact of these factors on bridge deterioration, providing insights to support maintenance and infrastructure management decisions.

## Objectives

- **Predict Bridge Condition:** Assess how well selected variables can forecast the current condition of bridges.
- **Identify Influential Factors:** Determine which variables most significantly affect bridge deterioration.

## Key Variables

- **Predictors:**
  - **Age** (derived from the year built)
  - **Average Daily Traffic** (`AverageDaily`)
  - **Percentage of Trucks** (`Trucks_percent`)
  - **Material** (`Material`)
  - **Design** (`Design`)
  
- **Target:**
  - **Current Condition** (combined from Deck, Superstructure, and Substructure ratings)

## Key Findings

- **Age** is the most significant predictor, negatively impacting bridge condition with a -61.4% change over its range.
- **Material** plays a crucial role, with Timber and Steel materials associated with poorer conditions compared to Concrete.
- **Average Daily Traffic** and **Percentage of Trucks** have minimal impact on bridge condition.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

## Conclusion

The analysis revealed that while age and material are significant predictors of bridge condition, other variables such as average daily traffic and percentage of truck traffic have minimal impact. The regression model achieved an R-squared value of 0.474, indicating that the selected predictors explain 47.4% of the variability in bridge condition. Future work could explore additional variables or more complex models to improve predictive performance.
