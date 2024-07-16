# HRA Dashboard

## Overview

This project focuses on creating an interactive dashboard to analyze the Human Resources Analytics (HRA) dataset. The dashboard provides insights into employee demographics, experience, and company attributes. The primary goal is to identify key patterns and trends in the data to support HR departments in making informed decisions.

## Dataset

The dataset comprises two CSV files: `HRA_TRAIN.csv` and `HRA_TEST.csv`. The data includes information about employees, such as their demographics, educational background, work experience, and company details. 

### Columns:
- `enrollee_id`: Unique ID for each employee.
- `city`: City of employment.
- `city_development_index`: Development index of the city.
- `gender`: Gender of the employee.
- `relevent_experience`: Relevant experience of the employee.
- `enrolled_university`: Type of university enrollment (if any).
- `education_level`: Education level of the employee.
- `major_discipline`: Major discipline of study.
- `experience`: Total years of experience.
- `company_size`: Size of the company.
- `company_type`: Type of the company.
- `last_new_job`: Time since the last job change.
- `training_hours`: Training hours completed.
- `target`: Target variable indicating whether the employee is looking for a new job.

## Steps Followed

### 1. Data Loading
- Load the dataset from CSV files (`HRA_TRAIN.csv` and `HRA_TEST.csv`) using pandas.

### 2. Initial Exploration
- Explore the basic structure and content of the dataset, including checking the data types and summary statistics.

### 3. Data Cleaning
- Remove duplicate entries.
- Handle missing values by calculating the percentage of missing values for each column and visualizing them using a heatmap and bar plot.

### 4. Data Visualization
- Create interactive visualizations using Plotly to better understand the data distribution and patterns.
  - **City Distribution**: Bar plot of the top 50 cities by employee count.
  - **City Development Index Distribution**: Bar plot of the city development index.
  - **Enrolled University Distribution**: Pie chart of the types of university enrollment.
  - **Education Level Distribution**: Pie chart of the education levels.
  - **Major Discipline Distribution**: Pie chart of the major disciplines.
  - **Company Size Distribution**: Pie chart of the company sizes.

## Conclusion

The interactive dashboard created using Plotly offers valuable insights into various attributes of the HRA dataset. It helps HR departments to make data-driven decisions by providing a clear understanding of employee demographics, experience, and company characteristics.
