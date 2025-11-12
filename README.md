# EDA-Poject-
Titanic Survival Prediction – Exploratory Data Analysis (EDA)

# 🧠 Titanic Survival Prediction – Exploratory Data Analysis (EDA)
# 📋 Project Overview
This project focuses on Exploratory Data Analysis (EDA) of the famous Titanic dataset to uncover insights about the factors influencing passenger survival.
The goal is to understand patterns, correlations, and trends in the data using Python’s data analysis and visualization libraries.

# 🎯 Objectives
Explore and clean the Titanic dataset.
Handle missing data and duplicates effectively.
Visualize and analyze relationships between different features and survival rates.
Identify key factors that influenced survival (e.g., gender, class, age, embarkation port).
Derive actionable insights through statistical and visual exploration.

# 🧰 Tools & Libraries Used
1.Programming Language: Python
2.Libraries:
pandas → Data manipulation and cleaning
numpy → Numerical computations
matplotlib → Data visualization
seaborn → Statistical data visualization
warnings → To suppress warning messages

# 🧹 Data Preprocessing Steps
1.Loaded dataset (train.csv) using pandas.
2.Checked for missing values, data types, and duplicates using .info(), .isnull(), and .duplicated().
3.Dropped irrelevant features such as Cabin due to high null percentage.
4.Imputed missing values:
Age: Replaced with the mean.
Embarked: Replaced with the most frequent port (mode).
5.Removed duplicates to ensure data consistency.

# 📊 Data Analysis & Visualization
1.Used seaborn and matplotlib to perform various visual analyses:
2.Survival Distribution: Overall survival vs. non-survival counts.
3.Gender vs. Survival: Female passengers had a much higher survival rate.
4.Passenger Class vs. Survival: Higher survival rates in 1st class; lowest in 3rd class.
5.Embarkation Port Analysis: Compared survival rates across embarkation points.
6.Age & Fare Distribution: Identified age and fare patterns using histograms, boxplots, and bar charts.
7.Correlation Insights: Explored relationships between numerical and categorical features.

Visual Techniques Used:
1.Count plots
2.Bar plots
3.Box plots
4.Pie charts
5.Distribution plots (Distplot)
6.Grouped bar charts

🔍 Key Insights
1.Gender: Females had a significantly higher survival rate than males.
2.Passenger Class: Passengers in 1st class were more likely to survive than those in lower classes.
3.Age: Younger passengers had slightly higher chances of survival.
4.Embarkation Port: Passengers who boarded from port ‘C’ had higher survival rates.
5.Fare: Higher fare correlated positively with survival probability.

# 📈 Results Summary

1.The analysis demonstrates that socio-economic status and gender were the most influential factors in survival.
2.These findings align with historical accounts that prioritized women and children in evacuation protocols.


