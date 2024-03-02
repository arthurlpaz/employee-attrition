# Analysis and Ensemble Learning: Employee Attrition and Factors

This an analysis and machine learning implementing training using the ensemble method. The method used is a stacking, where is a way of doing ensembles in which we use models to make predictions, and then use these predictions as features in new models. 

### About this dataset
This dataset offers a comprehensive and varied analysis of an organization's employees, focusing on areas such as employee attrition, personal and job-related factors, and financials.

**Features:** 
| Column Name             | Description                                                                                           |
|-------------------------|-------------------------------------------------------------------------------------------------------|
| Age                     | The age of the employee. (Numerical)                                                                  |
| Attrition               | Whether or not the employee has left the organization. (Categorical)                                   |
| BusinessTravel          | The frequency of business travel for the employee. (Categorical)                                       |
| DailyRate               | The daily rate of pay for the employee. (Numerical)                                                    |
| Department              | The department the employee works in. (Categorical)                                                    |
| DistanceFromHome        | The distance from home in miles for the employee. (Numerical)                                           |
| Education               | The level of education achieved by the employee. (Categorical)                                          |
| EducationField          | The field of study for the employee's education. (Categorical)                                          |
| EmployeeCount           | The total number of employees in the organization. (Numerical)                                          |
| EmployeeNumber          | A unique identifier for each employee profile. (Numerical)                                              |
| EnvironmentSatisfaction | The employee's satisfaction with their work environment. (Categorical)                                   |
| Gender                  | The gender of the employee. (Categorical)                                                              |
| HourlyRate              | The hourly rate of pay for the employee. (Numerical)                                                    |
| JobInvolvement          | The level of involvement required for the employee's job. (Categorical)                                 |
| JobLevel                | The job level of the employee. (Categorical)                                                            |
| JobRole                 | The role of the employee in the organization. (Categorical)                                             |
| JobSatisfaction         | The employee's satisfaction with their job. (Categorical)                                               |
| MaritalStatus           | The marital status of the employee. (Categorical)                                                       |
| MonthlyIncome           | The monthly income of the employee. (Numerical)                                                         |
| MonthlyRate             | The monthly rate of pay for the employee. (Numerical)                                                   |
| NumCompaniesWorked      | The number of companies the employee has worked for. (Numerical)                                        |
| Over18                  | Whether or not the employee is over 18. (Categorical)                                                   |
| OverTime                | Whether or not the employee works overtime. (Categorical)                                               |
| PercentSalaryHike       | The percentage of salary hike for the employee. (Numerical)                                             |
| PerformanceRating       | The performance rating of the employee. (Categorical)                                                   |
| RelationshipSatisfaction| The employee's satisfaction with their relationships. (Categorical)                                     |
| StandardHours           | The standard hours of work for the employee. (Numerical)                                                |
| StockOptionLevel        | The stock option level of the employee. (Numerical)                                                     |
| TotalWorkingYears       | The total number of years the employee has worked. (Numerical)                                          |
| TrainingTimesLastYear   | The number of times the employee was taken for training in the last year. (Numerical)                   |
| WorkLifeBalance         | The employee's perception of their work-life balance. (Categorical)                                      |
| YearsAtCompany          | The number of years the employee has been with the company. (Numerical)                                 |
| YearsInCurrentRole      | The number of years the employee has been in their current role. (Numerical)                             |
| YearsSinceLastPromotion | The number of years since the employee's last promotion. (Numerical)                                    |
| YearsWithCurrManager    | The number of years the employee has been with their current manager. (Numerical)                        |


## Technologies used
#### Analysis
- Pandas
- Numpy
- Plotly (express, graphic_objects, subplots)
- Matplolib
- Seaborn

#### Machine Learning - Scikit-Learn:
- Compose (ColumnTransformer)
- Model_Selection (train_test_split)
- Pipepine (Pipeline)
- PreProcessing (OneHotEncoder, StandardScaler)

#### Models used:
- LogisticRegression
- DecisionTree
- RandomForest
- GradientBoosting
