# EDA with Red Wine Quality Dataset

This project performs Exploratory Data Analysis (EDA) on the Red Wine Quality dataset. This dataset consists of physicochemical properties and quality ratings for different variants of Portuguese "Vinho Verde" red wine. The analysis aims to uncover patterns and insights about wine quality based on various attributes.

## Table of Contents
- [Dataset Information](#dataset-information)
  - [Attribute Information](#attribute-information)
- [Project Steps](#project-steps)
- [Visualizations](#visualizations)
- [Libraries Used](#libraries-used)
- [Usage](#usage)
- [Author](#author)

## Dataset Information

The dataset contains physicochemical measurements (input variables) and quality scores (output variable) of red wine samples. Due to privacy and logistical constraints, details such as grape type, brand, or price are not available.

- **Data Type**: Classification/Regression
- **Class Balance**: Imbalanced (more normal-quality wines than excellent or poor ones)
- **Potential Tasks**:
  - Classification of wine quality
  - Regression to predict quality scores
  - Outlier detection to identify excellent or poor wines
  - Feature selection to identify relevant physicochemical attributes

### Attribute Information

**Input Variables** (from physicochemical tests):
1. Fixed Acidity
2. Volatile Acidity
3. Citric Acid
4. Residual Sugar
5. Chlorides
6. Free Sulfur Dioxide
7. Total Sulfur Dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

**Output Variable** (based on sensory data):
12. Quality (score between 0 and 10)

## Project Steps

1. **Data Loading and Initial Exploration**:
   - Importing necessary libraries
   - Loading the dataset
   - Checking dataset information, shape, and columns

2. **Data Cleaning**:
   - Identifying and handling missing values
   - Removing duplicate records to avoid redundancy in analysis

3. **Exploratory Data Analysis (EDA)**:
   - **Summary Statistics**: Generating descriptive statistics for each column
   - **Correlation Analysis**: Examining correlations between different features using a heatmap
   - **Data Visualization**:
     - Distribution of wine quality scores
     - Histograms of each feature to analyze distribution
     - Pair plots for univariate, bivariate, and multivariate analysis
     - Categorical plots and scatter plots to explore relationships between variables like alcohol, pH, and quality

## Visualizations

- **Correlation Heatmap**: Visualizes correlations between input variables and the quality score.
- **Distribution of Wine Quality**: Shows the class imbalance in quality scores.
- **Histograms**: Distribution plots for each physicochemical property.
- **Pair Plot**: Plots relationships between multiple variables.
- **Box Plot**: Box plots of alcohol content across different quality scores.
- **Scatter Plot**: Relationship between alcohol and pH, colored by quality.

## Libraries Used

- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization

## Usage

You can run this analysis by executing the code in the Jupyter Notebook or Python script. Ensure the following dependencies are installed:

```bash
pip install pandas numpy matplotlib seaborn

```

## Author
**Sujeet Nayak** 
Data Engineering
