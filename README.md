# Welcome to Group 4's repository

## About
This our mini project for SC1015.


Files:
- [EDA](https://github.com/ShahrulXXXX/SC1015_project/blob/main/Exploratory_Data_Analysis.ipynb)
- [ML](https://github.com/ShahrulXXXX/SC1015_project/blob/main/machineLearning_1015.ipynb)

# Contributors
- [@ShahrulXXXX](https://github.com/ShahrulXXXX)
- [@BrandonChongWenJun](https://github.com/BrandonChongWenJun)
- [@Olive3Jadon](https://github.com/olive3jadon)

# Problem Definition
- Are we able to predict whether an employee will leave the company based on the data provided in their employee yearly survey

# Exploratory Data Analysis
Key insights:

- Employees who travel frequently are likely to leave
- Male employees are likely to leave
- Single employees are likely to leave
- Employees with low income are more likely to leave
- Employees who work overtime are more likely to leave

Odd insights:

- Those who performed average are more likely to stay while those with a lower or higher than average performance rating are more likely to leave

Mutual Information (Independent variables with a score of 0):

- EducationField
- Gender
- YearsSinceLastPromotion
- RelationshipSatisfaction

# Models Used
1. DecisionTreeClassifier
2. Random Forest
3. Multi-layer Perceptron (NEURAL NETWORK)

# Conclusion

Out of the tree machine learning models, Multi-layer Perceptron was able to achieve the highest accuracy in predicting whether an employee will leave the company. Followed by Random forest Classification and then DecisionTreeClassifier. 

Upon performing feature ranking, variables such as PerformanceRating, OverTime, JoiningYear, MonthlyIncome, YearsAtCompany are important in determining the accuracy of the models. 

Upsampling of response variable was important to prevent class imbalance. 

# Project Learnings
- Neural network
- GitHub
- Upsampling to handle imbalanced datasets
- Mutual information
- Video editing
- Encoding categorical variables (ordinal and nominal)
