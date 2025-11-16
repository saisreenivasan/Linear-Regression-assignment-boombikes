```markdown
# Linear Regression Assignment

This repository contains a Jupyter Notebook for a Linear Regression assignment, including model implementation, analysis, and detailed answers to subjective questions.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Assignment Questions](#assignment-questions)
- [Results](#results)

## Project Overview

This project demonstrates the application of **Ordinary Least Squares (OLS) Linear Regression** to analyze and predict bike-sharing demand. The notebook covers:
- Data preprocessing and feature engineering
- Model building and evaluation
- Statistical analysis and interpretation of results
- Answers to assignment-based subjective questions

## Features

- Data cleaning and exploratory data analysis
- Creation of dummy variables for categorical features
- Model training using OLS regression
- Diagnostic checks for regression assumptions
- Feature importance analysis
- Detailed explanations for assignment questions

## Dataset

The dataset contains daily records of bike-sharing demand from US based boom bikes and associated features such as weather, season, temperature, humidity, windspeed, and holidays.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/saisreenivasan/Linear-Regression-assignment-boombikes.git
   cd Linear-Regression-assignment-boombikes
   ```

## Usage

1. Open the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
2. Run the notebook cells in order to:
   - Load and preprocess the data
   - Build and evaluate the linear regression model
   - Review answers to the assignment questions

## Assignment Questions

The notebook includes answers to the following subjective questions:
- Effect of categorical variables on bike demand
- Importance of `drop_first=True` in dummy variable creation
- Correlation analysis using pair-plots
- Validation of linear regression assumptions
- Identification of top contributing features

## Results

- **Model Performance:**  
  - Training R²: **0.827**
  - Test R²: **0.806**
- **Top Features:**  
  - Temperature (`temp`)
  - Year (`yr`)
  - Weather situation (`weathersit_light_snow_rain`)
- **Assumption Checks:**  
  - Residuals, normality, homoscedasticity, and multicollinearity diagnostics included

