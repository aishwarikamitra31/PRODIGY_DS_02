) Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.
Introduction
The Titanic dataset contains information about the passengers aboard the ill-fated RMS Titanic. The dataset includes various features such as passenger class, age, gender, and survival status. This analysis aims to clean the data and perform exploratory data analysis to uncover relationships and trends.

Data Cleaning
Upon inspection, the dataset had missing values in the 'Age', 'Embarked', and 'Cabin' columns. The 'Age' column had missing values filled with the median age, 'Embarked' with the mode, and 'Cabin' with 'Unknown'. Unnecessary columns such as 'PassengerId', 'Name', and 'Ticket' were dropped.

Exploratory Data Analysis
Survival Rate by Gender
The plot shows that females had a significantly higher survival rate than males. This could be due to the "women and children first" policy during the evacuation.

Age Distribution of Survivors vs. Non-Survivors
The age distribution plot indicates that younger passengers had a higher survival rate compared to older passengers. This trend is consistent across different age groups.

Survival Rate by Passenger Class
The plot reveals that passengers in the first class had a higher survival rate than those in the second and third classes. This trend reflects the prioritization of higher-class passengers during the evacuation.

Heatmap of Correlation between Variables
The heatmap shows the correlation between various features. There is a notable positive correlation between 'Fare' and 'Pclass', indicating that higher fares were associated with higher passenger classes. 'Survived' is negatively correlated with 'Pclass', confirming that higher-class passengers had a better chance of survival.

Conclusion
The exploratory data analysis of the Titanic dataset reveals significant insights into the survival patterns based on gender, age, and passenger class. Females and younger passengers had higher survival rates, and first-class passengers were more likely to survive compared to those in lower classes. These findings highlight the importance of socio-economic status and demographic factors in the survival outcomes of the Titanic disaster.

This analysis provides a comprehensive understanding of the dataset and can serve as a foundation for further predictive modeling and hypothesis testing.





