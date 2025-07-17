# Medical Data Visualizer

This project analyzes medical examination data and visualizes key health metrics to identify patterns related to cardiovascular disease. It is part of the [FreeCodeCamp Data Analysis with Python Projects](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/medical-data-visualizer/).

## Dataset

The dataset used is `medical_examination.csv`, which includes patient health metrics such as height, weight, cholesterol, glucose levels, blood pressure, and lifestyle factors (e.g., smoking, alcohol consumption, physical activity).

## Objectives

- Add a new column `overweight` based on BMI calculation.
- Normalize `cholesterol` and `gluc` columns.
- Visualize categorical data by comparing healthy vs unhealthy conditions.
- Generate a heatmap to show correlation between features.

## Features

### Categorical Plot
Displays the count of each feature (cholesterol, glucose, smoking, alcohol use, physical activity, and overweight) separated by presence or absence of cardiovascular disease.

Output: `catplot.png`

### Heatmap
Shows the correlation matrix between features after cleaning the dataset (removing incorrect or outlier values).

Output: `heatmap.png`
