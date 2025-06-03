# Titanic_eda

Titanic Dataset - Exploratory Data Analysis (EDA)

Project Overview:

This project performs an Exploratory Data Analysis (EDA) on the classic Titanic dataset. The goal is to analyze the data visually and statistically to understand the factors influencing passenger survival during the Titanic disaster.

Dataset Information:

The dataset used in this project is Titanic.csv, which includes features like:

-PassengerId
-Survived (Target Variable: 0 = No, 1 = Yes)
-Pclass (Ticket class: 1st, 2nd, 3rd)
-Name, Sex, Age
-SibSp (Siblings/Spouses aboard)
-Parch (Parents/Children aboard)
-Ticket, Fare
-Cabin, Embarked (Port of Embarkation)

Tools & Libraries

-Python
-Pandas
-NumPy
-Matplotlib
-Seaborn
-Jupyter Notebook

EDA Steps:

1. Data Loading and Cleaning

-Used .info(), .describe(), .isnull().sum() to understand the structure.
-Handled missing values in Age, Cabin, and Embarked.

2. Univariate Analysis

-Plotted histograms for Age, Fare
-Count plots for categorical variables like Survived, Sex, Pclass, Embarked

3. Bivariate Analysis

-Boxplots of Age and Fare against Survived
-Countplots for Sex, Pclass, Embarked vs Survived

4. Multivariate Analysis

-Pairplot to explore interactions
-Heatmap to inspect correlation among numeric variables

Key Observations:

-Women had a much higher survival rate than men.
-First-class passengers had the highest survival rate.
-Passengers who paid higher Fare were more likely to survive.
-Younger children had relatively higher survival rates.

Output
The final notebook includes:

-Summary statistics and Observations
-Markdown file of the codes
-PDF of Observations
-Raw Titanic dataset

