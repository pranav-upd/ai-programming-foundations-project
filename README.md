# Customer Feedback Analysis Project

## Project Description

This project performs exploratory data analysis (EDA) on a customer feedback dataset to understand the key factors influencing customer satisfaction. The analysis focuses on identifying patterns, relationships, and insights using summary statistics, grouping, and correlation techniques.

## What I Built

* Reusable EDA functions for summary statistics, grouped analysis, and correlation analysis
* Data visualizations using Matplotlib and Seaborn
* Insights into customer satisfaction drivers

## Dataset Used

Customer Feedback and Satisfaction Dataset
Source: https://www.kaggle.com/datasets/jahnavipaliwal/customer-feedback-and-satisfaction

## How to Run the Project

### 1. Install Dependencies

Make sure Python is installed, then run:

```bash
pip install pandas matplotlib seaborn jupyter
```

### 2. Open the Notebook

Navigate to the project folder and run:

```bash
jupyter notebook
```

Then open:
data_workflow.ipynb

### 3. Run the Analysis

Run all cells sequentially to execute the EDA and view outputs.

## Requirements

* Python 3.x
* Jupyter Notebook
* pandas, matplotlib, seaborn

## Reflection: Data Cleaning and Bias

Data cleaning decisions can introduce or amplify bias if not handled carefully. For example, removing rows with missing values without understanding the cause may disproportionately exclude certain groups, leading to skewed results. Similarly, inconsistent handling of categorical variables (e.g., treating "Male" and "male" as separate categories) can distort group-level analysis.

In this project, the dataset was found to be clean, with no missing values or duplicate records. As a result, only minimal cleaning steps such as standardizing categorical values were applied. These steps were performed as preventive measures rather than corrective ones.

Additionally, no aggressive filtering (such as removing outliers) was performed because the initial data audit showed that all numerical values fell within reasonable ranges. This decision helps preserve the original data distribution and avoids introducing unintended bias.

Overall, cleaning steps were guided by observed data characteristics rather than assumptions, ensuring that the analysis remains as unbiased and representative as possible.


## requirements.txt

To install dependencies using a requirements file:

```bash
pip install -r requirements.txt
```

To generate the requirements file:

```bash
pip freeze > requirements.txt
```
