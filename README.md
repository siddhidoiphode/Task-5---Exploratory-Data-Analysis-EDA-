# Task-5---Exploratory-Data-Analysis-EDA-

google colab link:
https://colab.research.google.com/drive/1nYqX-UKQHN5bd9ybwR3sRHj4C1m4gowh#scrollTo=M2ZsmwZpqSnk


✅ Titanic EDA Summary + Library Usage
Objective: Analyze Titanic data to find patterns in survival.

Dataset: Contains 891 rows and 12 columns.

Target Column: Survived (0 = No, 1 = Yes).

Used Pandas (import pandas as pd):

For loading data: read_csv()

For summarizing: .info(), .describe()

For missing values: .isnull().sum(), .fillna()

For category counts: .value_counts()

Used Matplotlib (import matplotlib.pyplot as plt):

For plotting histograms: data['Age'].hist()

For setting labels: plt.title(), plt.xlabel(), plt.ylabel()

Used Seaborn (import seaborn as sns):

For boxplots: sns.boxplot()

For barplots: sns.barplot()

For pairplot: sns.pairplot()

For heatmap: sns.heatmap(data.corr())

Insights:

Females and 1st class had higher survival rates.

Southampton was the most common embark point.

Fare and Age had outliers and trends worth noting.
