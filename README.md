Titanic Dataset Data Analysis (DA)

📌 Project Overview

This project performs  Data Analysis (DA) on the classic Titanic dataset to understand passenger characteristics and survival patterns.
The analysis includes data cleaning, handling missing values, statistical summaries, and visualizations to identify key factors influencing survival.

📂 Dataset

•	Source: Titanic dataset (train.csv)
•	Common fields analyzed:
•	Survived – Survival status (0 = No, 1 = Yes)
•	Pclass – Passenger class
•	Sex – Gender
•	Age – Age of passenger
•	Embarked – Port of embarkation
•	Cabin – Cabin number (dropped due to high missing values)

🛠️ Tools & Libraries Used

•	Python 3.x
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Jupyter Notebook

📊 Key Analysis Steps

1.	Data Loading
•	Imported the Titanic dataset using Pandas.

2.	Initial Exploration
•	Checked dataset shape, column names, data types, and summary statistics.

3.	Missing Value Handling
•	Filled missing Age values with the median.
•	Filled missing Embarked values using the mode.
•	Dropped the Cabin column due to excessive missing values.

4.	Survival Analysis
•	Compared survival rates by:
•	Gender
•	Passenger class

5.	Data Visualization
•	Survival count plot
•	Gender-wise survival bar chart
•	Passenger class survival bar chart
•	Age distribution by survival
•	Passenger class distribution pie chart

📈 Key Insights

•	Women had a significantly higher survival rate than men
•	First-class passengers were more likely to survive
•	Age distribution shows survival variation across age groups
•	Passenger class strongly influenced survival chances

