# Part 2: Diabetes Data Analysis

This section of Assignment 2 analyzes a diabetes dataset containing 768 patient observations. The dataset contains eight predictor variables and one binary response variable, `Outcome`, where 1 indicates diabetes and 0 indicates no diabetes.

For this assignment, the complete dataset of 768 observations was treated as the population.

## Tasks Completed

### A. Random Sample and Glucose Comparison
- Selected a reproducible random sample of 25 observations using a random seed of 42.
- Calculated the mean and highest Glucose values for the sample.
- Compared the sample statistics with the population statistics.
- Created a chart to visualize the comparison.

### B. BMI Percentile Comparison
- Calculated the 98th percentile of BMI for the sample.
- Calculated the 98th percentile of BMI for the population.
- Compared the sample and population values using a chart.

### C. Bootstrap Analysis of Blood Pressure
- Created 500 bootstrap samples with 150 observations in each sample.
- Used sampling with replacement.
- Calculated the mean, standard deviation, and 95th percentile of BloodPressure for each bootstrap sample.
- Averaged the bootstrap statistics and compared them with the population statistics.
- Created charts to visualize the bootstrap and population comparisons.

## Files

- `Assignment2_Part2.ipynb` - Complete Python analysis and visualizations
- `diabetes.csv` - Original diabetes dataset
