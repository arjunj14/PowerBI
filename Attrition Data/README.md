# Employee Attrition - Power BI Report

This repository contains a Power BI report that visualizes insights from the Employee Attrition Prediction Dataset, which includes demographic, job-related, and performance metrics for 10,000 employees. The report helps analyze key factors contributing to employee turnover.

## Dataset Description

The dataset consists of 26 features, including:

* **Employee Demographics:** Age, Gender, Marital Status
* **Job Information:** Department, Job Role, Job Level, Monthly Income, Hourly Rate
* **Work Experience:** Years at Company, Years in Current Role, Years Since Last Promotion
* **Performance Metrics:** Work-Life Balance, Job Satisfaction, Performance Rating, Training Hours Last Year
* **Work Conditions:** Overtime, Project Count, Absenteeism, Work Hours Per Week
* **Employee Relationships:** Work Environment Satisfaction, Relationship with Manager, Job Involvement
* **Historical Data:** Distance From Home, Number of Companies Worked
* **Target Column:** Attrition (Yes/No)

## Preview
### Dashboard Overview
![Attrition Visualization](<Attrition Visualization.png>)

## Power BI Visualizations

The report utilizes the following visualizations:

**Filters (Slicers):**

* Attrition (Yes/No)
* Overtime (Yes/No)
* Gender (Male/Female)

**Table Visualization:**

* Salary Range: Categorized into Below 10,000 / 10,000-15,000 / Above 15,000

**KPI Cards:**

* Average Ratings (Scale 1-5):
    * Job Involvement
    * Job Satisfaction
    * Work Environment Satisfaction
    * Performance Rating
    * Work-Life Balance
    * Relationship with Manager
* Employee Count & Attrition Count

**Stacked Bar Charts (Using Field Parameters):**

* Attrition by:
    * Home Distance (in km)
    * Number of Companies Worked At
    * Project Count
    * Absenteeism
* Attrition by:
    * Work Hours Per Week
    * Hourly Rate
* Attrition by:
    * Years at Company
    * Years in Current Role
    * Years Since Last Promotion
    * Training Hours Last Year

**Donut Chart (Using Field Parameters):**

* Attrition by:
    * Department
    * Job Role
    * Marital Status

## How to Use

1. Download the Power BI report file [.pbix](<HR analytics.pbix>).
2. Open it using Microsoft Power BI Desktop.
3. Interact with the visualizations using slicers and field parameters to analyze different attrition trends.

## Key Insights & Business Impact

The report helps to:

* Identify key departments and job roles with high attrition.
* Analyze the impact of salary, work-life balance, and overtime on attrition.
* Determine how experience factors like promotions, tenure, and training hours influence turnover.
* Provide actionable insights to HR teams for improving retention strategies.

# Employee Attrition Prediction Dataset

This dataset is available on Kaggle: [Employee Attrition Prediction Dataset](https://www.kaggle.com/datasets/ziya07/employee-attrition-prediction-dataset)

or you can download it from [.Csv file](employee_attrition_dataset_10000.csv)

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

This project is licensed under the [MIT LICENSE](LICENSE).

## Author

[arjunj] - Power BI Developer & Data Analyst