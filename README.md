# Salary vs Years of Experience

A machine learning project that analyzes the relationship between years of experience and salary using linear regression.

## Project Overview

This project demonstrates how years of work experience correlates with salary levels. Using a simple dataset, we perform exploratory data analysis, visualize the relationship between variables, and build a predictive model using linear regression.

## Dataset

The project uses [Salary_Data.csv](Salary_Data.csv) which contains:
- **YearsExperience**: Years of professional experience
- **Salary**: Annual salary in dollars
- **30 data points** for training and testing the model

## Files

- [Salary vs Years of Experience.ipynb](Salary%20vs%20Years%20of%20Experience.ipynb) - Main Jupyter notebook with analysis and model
- [Salary_Data.csv](Salary_Data.csv) - Dataset containing experience and salary data
- [README.md](README.md) - Project documentation

## Requirements

Install the required Python packages:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn
```

## How to Run

1. **Clone or download** this repository to your local machine

2. **Install dependencies** using the command above

3. **Open the Jupyter notebook**:
   - Launch Jupyter Notebook or use VS Code with Jupyter extension
   - Open [Salary vs Years of Experience.ipynb](Salary%20vs%20Years%20of%20Experience.ipynb)

4. **Run all cells** in order:
   - Import required libraries
   - Load and explore the dataset
   - Create visualizations
   - Build and train the linear regression model
   - Make predictions and evaluate performance

## What You'll Learn

- **Data exploration** and visualization with pandas and seaborn
- **Linear regression** implementation using scikit-learn
- **Model evaluation** techniques
- **Data visualization** best practices with matplotlib
- **Correlation analysis** between numerical variables

## Expected Output

The notebook will generate:
- Data summary and basic statistics
- Scatter plot showing salary vs experience relationship
- Linear regression line fitted to the data
- Model performance metrics
- Predictions for new experience values

## Next Steps

Try extending this project by:
- Adding more features (education, location, industry)
- Comparing different regression algorithms
- Implementing cross-validation
- Creating a web interface for predictions

## Author

Created as a learning project for understanding linear regression and data analysis fundamentals.