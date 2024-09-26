# Insurance Pricing Forecasting Model
Predictive supervised learning regression models (Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Gradient Boosting Regressor) for estimating health insurance charges using historical data on insurance charges and related demographic and health factors. Applications include assisting insurance companies in optimizing premium structures and helps individuals understand the variables influencing their insurance costs.

### Data Dictionary
| Column Name     | Data Type             | Description                                                       | Variable Type             |
|-----------------|-----------------------|-------------------------------------------------------------------|---------------------------|
| age             | Integer               | Age of the individual in years                                    | Numerical                 |
| sex             | String                | Gender of the individual (e.g., male, female)                     | Categorical               |
| bmi             | Float                 | Body Mass Index (BMI) of the individual, indicating body fat level | Numerical                 |
| children        | Integer               | Number of dependent children                                      | Numerical                 |
| smoker          | String                | Indicates whether the individual is a smoker (yes/no)             | Categorical               |
| region          | String                | Geographic region where the individual resides (e.g., southwest, southeast) | Categorical         |
| charges         | Float                 | Medical charges incurred by the individual                        | Numerical                 |
