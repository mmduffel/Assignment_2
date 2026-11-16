# Part 1: Used Car Data Analysis

This section of Assignment 2 focuses on cleaning, transforming, and manipulating a used-car dataset using Python and pandas.

## Dataset

The dataset contains information about used vehicles, including vehicle characteristics such as year, mileage, kilometers driven, fuel type, transmission, engine size, power, seating capacity, and price.

The target variable is `Price`, which represents the selling price of the used vehicles in lakhs.

## Tasks Completed

### A. Missing Value Treatment
- Identified missing values in the dataset.
- Removed `New_Price` because approximately 86.06% of its values were missing.
- Removed the unnecessary `Unnamed: 0` index column.
- Imputed missing values using the median for Mileage, Engine, and Power and the mode for Seats.

### B. Removing Units
- Removed measurement units from `Mileage`, `Engine`, and `Power`.
- Converted the cleaned attributes to numerical data types.

### C. One-Hot Encoding
- Converted `Fuel_Type` and `Transmission` into numerical binary variables using one-hot encoding.

### D. Feature Engineering
- Created a new `Car_Age` feature using:

  `Car_Age = 2026 - Year`

### E. Data Manipulation
Used pandas to perform operations equivalent to:
- Select
- Filter
- Rename
- Mutate
- Arrange
- Group by
- Summarize

A `Km_Per_Year` feature was also created to estimate the average kilometers driven per year.

## Files
- `Assignment2_Part1.ipynb` - Complete Python analysis
- `train.csv` - Original used-car dataset
