# Titanic Survival Analysis

## Project Overview

This project delves into the legendary Titanic dataset to explore factors influencing passenger survival. Through a series of data loading, cleaning, and exploratory data analysis (EDA) steps, we aim to uncover patterns and relationships within the data. The goal is to understand which characteristics played a significant role in determining who survived the tragic disaster.

## Dataset

The dataset used for this analysis is the classic Titanic dataset, containing information about individual passengers, including their age, sex, passenger class, fare, embarkation point, and survival status.

## Key Steps & Analysis

1.  **Data Loading**: The dataset is loaded into a pandas DataFrame for easy manipulation.
2.  **Initial Exploration**: Basic checks like `df.head()`, `df.tail()`, `df.info()`, and `df.describe()` are performed to understand the data's structure, types, and summary statistics.
3.  **Missing Value Handling**: Missing values in 'Age', 'Cabin', and 'Embarked' columns are addressed using appropriate imputation strategies (mean for 'Age', mode for 'Cabin' and 'Embarked').
4.  **Data Type Conversion**: The 'Age' column is converted to an integer type for cleaner representation.
5.  **Survival Analysis by Class & Gender**: We analyze the number of survivors based on passenger class and gender, identifying first-class survivors, and breaking them down by male and female.
6.  **Survival Analysis by Embarkation Port**: We examine the number of fatalities based on the passenger's embarkation port.
7.  **Visualizations**:
    *   **Pie Chart of Male vs. Female Survivors**: Visualizing the proportion of male and female passengers who survived.
    *   **Line Graph of Survival Rate by Age**: Illustrating how survival rates change across different age groups.
    *   **Bar Plot of Survival Rate by Passenger Class**: Comparing survival rates across the different passenger classes.

## Insights Gained

Through this analysis, we identify several key factors correlated with survival, such as:

*   **Gender**: A higher proportion of females survived compared to males.
*   **Passenger Class**: First-class passengers had a significantly higher survival rate.
*   **Age**: Survival rates varied across different age groups, with certain age brackets showing better or worse survival chances.

## Notebook Link

You can access and run this analysis directly in Google Colab:
[Titanic Survival Analysis Notebook](https://colab.research.google.com/drive/1JPXmGWVfWNo73li7IoPYjx6aNKHkwSxs?usp=sharing)

## How to Run the Notebook

1.  Click on the Colab link above.
2.  Once in Colab, go to `Runtime` -> `Run all` to execute all cells and reproduce the analysis.
