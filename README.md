# Principles of Data Analytics

This project focuses on exploring and analyzing datasets using Python. It includes tasks such as loading datasets, exploring their structure, and summarizing key statistics.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Tasks Overview](#tasks-overview)
- [How to Run](#how-to-run)
- [Results](#results)
- [Sample Visualizations](#sample-visualizations)
- [Acknowledgments](#acknowledgments)

## Introduction
This project uses the Iris dataset from the `sklearn.datasets` module to demonstrate basic data analytics principles. The tasks include:
- Loading the dataset.
- Exploring its structure (e.g., shape, feature names, and target classes).
- Summarizing the data with statistical measures like mean, median, and standard deviation.
- Visualizing relationships between features using scatter plots and regression lines.

The goal is to provide a foundational understanding of data exploration and analysis techniques.

## Technologies Used
- **Python 3.x**
- Libraries:
  - `scikit-learn` for dataset loading and machine learning tools.
  - `numpy` for numerical operations.
  - `matplotlib` for data visualization.

## Tasks Overview
### Task 1: Source the Data Set
- Import the `sklearn.datasets` module.
- Load the Iris dataset using the `load_iris()` function.

### Task 2: Explore the Data Structure
- Print the shape of the dataset to understand its dimensions.
- Display the first and last 5 rows of the data to preview the dataset.
- Print the feature names and target classes to understand the dataset's structure.

### Task 3: Summarize the Data
- Calculate and display the following statistics for each feature:
  - Mean
  - Minimum
  - Maximum
  - Standard Deviation
  - Median

### Task 4: Visualize Features
- Create line plots for each feature to observe trends and distributions.

### Task 5: Investigate Relationships
- Create scatter plots to visualize relationships between pairs of features.
- Color-code the scatter plots based on the target classes.

### Task 6: Analyze Relationships
- Use `numpy.polyfit` to calculate and add regression lines to the scatter plots.

### Task 7: Analyze Class Distributions
- Create box plots to compare the distributions of petal lengths across the three classes.

## How to Run
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/principles_of_data_analytics.git

  ## Navigate to the project directory:
  ```bash
  cd principles_of_data_analytics```

  ## Install the required dependencies
  ```bash
  pip install -r requirements.txt```

  ## Open the Jupyter Notebook:
  ```bash
  jupyter notebook tasks.ipynb```
