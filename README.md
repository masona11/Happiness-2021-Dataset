# Happiness-2021-Dataset

## Analysis and Linear Regression Model

This repository contains the code and analysis for exploring the World Happiness Report dataset and building a linear regression model to predict happiness scores based on various factors.

## Introduction

In this project, we aim to analyze the World Happiness Report dataset and explore the factors that contribute to happiness across different countries. The dataset contains information about various indicators such as GDP per capita, social support, health life expectancy, freedom to make life choices, generosity, and perception of corruption. By analyzing this data, we can gain insights into the relationships between these factors and overall happiness.

## Dataset

The dataset used for this analysis is the World Happiness Report dataset for the year 2021. It is available in the CSV format and can be found [here](/kaggle/input/world-happiness-report-2021/world-happiness-report-2021.csv). The dataset provides information on happiness scores and various factors contributing to happiness for different countries.

## Files

- `Happiness 2021 Dataset Analysis_Linear Regression Model.ipynb`: Jupyter Notebook containing the code for data preparation, exploratory data analysis, and linear regression model.
- `README.md`: This file, providing an overview of the project and instructions for running the notebook.

## Data Preparation

To start our analysis, we first need to load and prepare the dataset. We read the dataset from the provided CSV file and select the relevant columns for our analysis. We also handle missing values, rename columns for clarity, and create a copy of the selected columns.

## Exploratory Data Analysis

After data preparation, we perform exploratory data analysis (EDA) to gain initial insights into the data. This includes calculating summary statistics, visualizing the distribution of variables through histograms, and creating scatter plots to explore relationships between variables.

## Linear Regression Model

We build a linear regression model to predict happiness scores based on selected factors. The model uses logged GDP per capita, social support, health life expectancy, freedom to make life choices, generosity, and perception of corruption as predictors. We assess the model's performance and interpret the coefficients and statistical significance of the predictors.

## Conclusion

Through this analysis, we gain insights into the factors influencing happiness across different countries. The linear regression model provides a means to predict happiness scores based on selected factors. Policymakers and researchers interested in understanding and promoting happiness can leverage these insights to inform decision-making processes.

Please refer to the `Happiness 2021 Dataset Analysis_Linear Regression Model.ipynb` file for the detailed code and analysis.

