# Principles of Data Analytics

This project demonstrates fundamental data analytics principles using the Iris dataset. It includes tasks such as loading datasets, exploring their structure, summarizing key statistics, visualizing relationships, and performing basic machine learning tasks.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Tasks Overview](#tasks-overview)
- [How to Run](#how-to-run)
- [Results](#results)
- [Sample Visualizations](#sample-visualizations)
- [Acknowledgments](#acknowledgments)

## Introduction
The Iris dataset is a classic dataset in machine learning and statistics. It contains measurements of sepal length, sepal width, petal length, and petal width for three species of iris flowers: Setosa, Versicolor, and Virginica. This project uses the dataset to demonstrate data exploration, visualization, and analysis techniques.

## Technologies Used
- **Python 3.x**
- Libraries:
  - `scikit-learn` for dataset loading and machine learning tools.
  - `numpy` for numerical operations.
  - `matplotlib` for data visualization.
  - `seaborn` for advanced visualizations.
  - `pandas` for data manipulation.

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
- Create histograms for each feature to observe their distributions.

### Task 5: Investigate Relationships
- Create scatter plots to visualize relationships between pairs of features.
- Color-code the scatter plots based on the target classes.

### Task 6: Analyze Relationships
- Use `numpy.polyfit` to calculate and add regression lines to the scatter plots.

### Task 7: Analyze Class Distributions
- Create box plots to compare the distributions of petal lengths across the three classes.

### Task 8: Compute Correlations
- Calculate the correlation coefficients between the features.
- Display the results as a heatmap using `seaborn`.

### Task 9: Fit a Simple Linear Regression
- Calculate the coefficient of determination ($R^2$) for two selected features.
- Annotate the scatter plot with the $R^2$ value.

### Task 10: Too Many Features
- Use `seaborn` to create a `pairplot` of the dataset.
- Explain the insights gained from the pairplot.

## How to Run
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/principles_of_data_analytics.git

2. Navigate to the project directory:
```bash
   cd principles_of_data_analytics   
   ```

3. Install the required dependencies:
```bash
   pip install -r requirements.txt 
   ```

4. Open the Jupyter Notebook:
```bash
   jupyter notebook tasks.ipynb
   ```

## Results
The project provides insights into the Iris dataset, including:

-Statistical summaries of each feature.
-Visualizations of feature distributions and relationships.
-Correlation analysis and regression modeling.

## Sample Visualizations

-Histograms of feature distributions.
-Scatter plots with regression lines.
-Heatmaps of feature correlations.
-Pairplots showing relationships between all features.

## Acknowledgments
The Iris dataset is publicly available and widely used for educational purposes.
Libraries like `scikit-learn`, `numpy`, `matplotlib`, and `seaborn` were instrumental in this project.

Feel free to explore the notebook and adapt the code for your own data analysis projects!