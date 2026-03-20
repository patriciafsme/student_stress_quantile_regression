# Student Stress Analysis: A Quantile Regression Approach

## Project Overview
While standard linear regression models the conditional mean of a response variable, this project utilizes **Quantile Regression** to provide a more comprehensive view of the relationship between academic factors and student stress. By analyzing different quantiles (e.g., the 25th, 50th, and 75th percentiles), we can understand how predictors affect students with low stress levels differently from those experiencing extreme stress.

The study focuses on identifying whether variables like study hours, sleep quality, or extracurricular activities have a constant effect across the entire distribution of student well-being.

## Technical Stack
* **Language:** R
* **Methodology:** Quantile Regression (QR), Ordinary Least Squares (OLS) comparison.
* **Reporting:** Quarto (QMD), Interactive HTML, and PDF.

## Key Features & Analysis
* **Beyond the Mean:** Implementation of the `quantreg` package in R to estimate coefficients across various quantiles.
* **Comparative Analysis:** Direct comparison between OLS and Quantile Regression to highlight where the mean-based approach fails to capture the full story.
* **Statistical Visualization:** Use of "Process Plots" to show how coefficients fluctuate as we move from lower to higher quantiles.
* **In-depth Reporting:** An interactive HTML report that includes data cleaning, assumption testing, and detailed interpretation of results.

## Interactive Report
You can view the full interactive analysis here:
https://patriciafsme.github.io/student_stress_quantile_regression/student_stress_quantile_regression.html

## Repository Structure
* `student_stress_quantile_regression.html`: The full interactive report (Best for viewing).
* `quantile_regression.pdf`: A print-ready version of the analysis.
* `student_stress_quantile_regression.qmd`: The source Quarto file for reproducibility.
* `QR_data.rdata`: Directory containing the raw datasets used for the study.

 ---
*Project developed during the specialization in Statistical Consulting (UC Riverside).*
