# DDS_6306_Project_2
This is the repository for case study 2 for DDS 6306

__Project introduction: A data set of attrition and monthly income was provided, in order to predict attrition for a client, Frito-Lay. Another analysis was performed to identify monthly income for a set of unlabled observations.__ 

__Scope of inference, as we do not know how the data was colleceted, any predictions beyond this data set are purely extrapolation.__ 

__Executive Summary: The purpose of this analysis was to explore the top three factors leading to attrition as well as explore the top three factors leading to monthly income.__ 

__The identified factors for Attrition are as follows__ 
__1. Job Role__
__2. Distance Frome Home__
__3. Number of Companies Worked__

__Really would want to review the HR job odds ratio, odds of attriting is 8.55 e+6 times over the odds of staying.__

__The identified factors for Monthly Income are as follows__ 
__1. Total Working Years__
__2. Job Role__
__3. Job Level__ 

__The recomended model for predicting attrition is a logsitic regression model using the following predictors__ 
    __Age + DailyRate + Department + Education +__
    __EducationField + JobLevel + JobSatisfaction + MaritalStatus +__
    __YearsInCurrentRole + OverTime + JobRole + JobInvolvement +__ 
    __YearsSinceLastPromotion + EnvironmentSatisfaction + DistanceFromHome +__
    __NumCompaniesWorked + WorkLifeBalance + PerformanceRating +__
    __HourlyRate + TotalWorkingYears + YearsAtCompany + MonthlyIncome +__
    __BusinessTravel + YearsWithCurrManager + RelationshipSatisfaction +__ 
    __PercentSalaryHike + EmployeeNumber__
    
__The recommended model for predicting monthly income is a linear model using the following predictors__ 
__TotalWorkingYears + JobLevel + JobRole + MonthlyRate + Gender + EmployeeNumber__

__Video Link:__
__https://youtu.be/sJqT7rTYkPg__ 
