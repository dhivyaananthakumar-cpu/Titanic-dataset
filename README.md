1. Introduction

The Titanic dataset is one of the most popular datasets used in data science and machine learning. It is based on the tragic sinking of the RMS Titanic in 1912. The dataset contains information about passengers such as age, gender, ticket class, fare, and survival status.

The main objective of analyzing this dataset is to understand the factors that influenced passenger survival and to perform statistical analysis on the available data.

2. Titanic Dataset Overview

The dataset contains information about 891 passengers and includes the following important features:

PassengerId – Unique ID of passenger

Survived – Survival status (0 = No, 1 = Yes)

Pclass – Passenger class (1 = First, 2 = Second, 3 = Third)

Name – Passenger name

Sex – Gender

Age – Age of passenger

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Ticket – Ticket number

Fare – Ticket fare

Cabin – Cabin number

Embarked – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

This dataset is widely used for classification and predictive analysis.

3. Methodology

The following steps were followed in the analysis:

Step 1: Data Collection

The dataset was obtained from Kaggle.

Step 2: Data Cleaning

Checked for missing values

Filled missing age values using median

Filled embarked column using mode

Dropped cabin column due to many missing values

Step 3: Exploratory Data Analysis (EDA)

Analyzed survival count

Compared survival by gender

Compared survival by passenger class

Studied correlation between numerical variables

Step 4: Visualization

Used graphs such as:

Count plots

Bar charts

Heatmap for correlation

4. Statistical Analysis
🔹 Survival Rate

Around 38% passengers survived

Around 62% passengers did not survive

🔹 Survival by Gender

Female passengers had a much higher survival rate compared to males

“Women and children first” policy influenced survival

🔹 Survival by Passenger Class

First-class passengers had higher survival rate

Third-class passengers had the lowest survival rate

🔹 Age Factor

Younger passengers had slightly better survival chances

Missing age values were replaced using median for accuracy

🔹 Correlation

Passenger class and fare are related

Survival is strongly influenced by gender and class

5. Conclusion

From the Titanic dataset analysis, we can conclude that:

Gender was a major factor in survival.

Passenger class significantly affected survival chances.

Socioeconomic status played an important role.

Data cleaning is essential before performing analysis.

The Titanic dataset is an excellent example for learning data preprocessing, visualization, and statistical analysis in Python.

