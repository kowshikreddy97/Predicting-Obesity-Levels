1. Introduction
   
Overview of the project:
The purpose of this project is to perform a comprehensive regression analysis to assess obesity levels in individuals as a function of various demographic, dietary, and lifestyle parameters. By analyzing the relationships between predictors and the target variable (obesity levels), this project aims to build reliable regression models to estimate obesity levels, providing valuable insights into public health and nutrition management.

Objectives:
Understanding relationships: Examine how demographic, dietary, and lifestyle factors, such as age, gender, family history of overweight, eating habits, physical activity, and others, influence obesity levels.

Developing predictive models: Create and evaluate regression models to accurately predict obesity levels across categories such as normal weight, overweight, and obesity types.

Providing actionable insights: Identify key factors contributing to obesity to inform public health interventions and personalized recommendations for improved health outcomes.

Research Questions:
What are the most significant predictors of obesity levels in individuals based on demographic, dietary, and lifestyle factors?
How do different regression models (e.g., linear regression, polynomial regression and regularization) perform in predicting obesity levels?
Can the results inform strategies for public health initiatives and personalized recommendations to manage and prevent obesity?

2. Dataset Selection and Description
Source of the Dataset:
The dataset used in this project is the Obesity Levels Dataset, sourced from UC Irvine Machine Learning Repository which contains information collected from individuals in Mexico, Peru, and Colombia. This dataset captures various demographic, dietary, and lifestyle parameters along with the obesity levels of individuals. It is a publicly available dataset containing 2,111 observations and 17 variables, with 16 independent variables (features) and 1 dependent variable (target).

Dataset Link: https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition

Description of Variables:
1. Features:

Gender: Gender of the individual (categorical: Male/Female).
Age: Age of the individual, measured in years (continuous).
Height: Height of the individual, measured in meters (continuous).
Weight: Weight of the individual, measured in kilograms (continuous).
family_history_with_overweight: Indicates if a family member has a history of being overweight (binary: Yes/No).
FAVC (Frequent Consumption of High-Caloric Food): Indicates if the individual frequently consumes high-caloric food (binary: Yes/No).
FCVC (Frequency of Vegetable Consumption): Number of times vegetables are consumed in meals daily (integer).
NCP (Number of Meals Per Day): Average number of main meals consumed daily (continuous).
CAEC (Consumption of Food Between Meals): Frequency of consuming food between meals (categorical: No/Sometimes/Frequently/Always).
SMOKE: Indicates if the individual smokes (binary: Yes/No).
CH2O (Daily Water Intake): Average daily water consumption, measured in liters (continuous).
SCC (Calorie Monitoring): Indicates if the individual monitors their calorie intake (binary: Yes/No).
FAF (Physical Activity Frequency): Frequency of physical activity per week (continuous).
TUE (Time Using Technology): Average daily time spent using technological devices, measured in hours (integer).
CALC (Alcohol Consumption): Frequency of alcohol consumption (categorical: No/Sometimes/Frequently/Always).
MTRANS (Mode of Transportation): The primary mode of transportation used by the individual (categorical: Walking/Public Transportation/Automobile/Bike/Motorbike).

2. Target:

NObeyesdad (Obesity Level): Obesity level of the individual, categorized as: Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, Obesity Type III

These variables provide a comprehensive view of the individual’s demographic profile, dietary habits, physical activity, and lifestyle factors, enabling the analysis and modeling of obesity levels.
