# Titanic Data Analysis: Survival Probability

This project analyzes the famous Titanic dataset to explore the factors that influenced passenger survival during the disaster. The analysis focuses on understanding the probability of survival based on various passenger attributes such as sex, passenger class (status), age, and more.

## Project Description

The goal of this project is to perform exploratory data analysis (EDA) and potentially build a simple model to investigate the relationships between passenger characteristics and their survival outcome. By visualizing and analyzing the data, we aim to uncover patterns and insights into who was more likely to survive.

## Features

* **Data Loading and Exploration:** Loading the dataset using pandas and performing initial data inspection.
* **Data Cleaning and Preprocessing:** Handling missing values and preparing the data for analysis.
* **Exploratory Data Analysis (EDA):**
    * Visualizing survival rates based on different categorical features (e.g., Sex, Pclass, Embarked).
    * Analyzing the distribution of numerical features (e.g., Age, Fare) in relation to survival.
    * Exploring correlations between features.
* **Survival Probability Analysis:** Specifically investigating how factors like sex, passenger class, and other attributes correlate with the likelihood of survival.
* *(Optional - depending on your notebook content):* Simple model building or feature engineering.

## Libraries Used

The following Python libraries were used in this project:

* **pandas:** For data manipulation and analysis.
* **numpy:** For numerical operations.
* **matplotlib:** For creating static, interactive, and animated visualizations.
* **seaborn:** A high-level interface for drawing attractive and informative statistical graphics, built on matplotlib.
* **sklearn:** For machine learning tasks.

## How to Run

1.  Clone this repository to your local machine.
2.  Make sure you have Python and the necessary libraries installed. You can install them using pip:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  Navigate to the project directory.
4.  Open the Jupyter Notebook `Analiza_danych_titanica.ipynb` using Jupyter Notebook or JupyterLab:
    ```bash
    jupyter notebook Analiza_danych_titanica.ipynb
    ```
    or
    ```bash
    jupyter lab Analiza_danych_titanica.ipynb
    ```
5.  Run the cells in the notebook sequentially to execute the analysis.

## Data

The analysis is based on the following files:

* `train.csv`: The training data containing passenger information and survival outcomes.
* `test.csv`: The test data containing passenger information (without survival outcomes).
* `gender_submission.csv`: A sample submission file (often used in Kaggle competitions).

These files are standard datasets for the Titanic survival prediction problem, commonly found on platforms like Kaggle.
