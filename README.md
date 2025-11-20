# The-Movie-Study
Database Source: Kaggle

Project: Investigate a Dataset - [tmdb_movies]

Table of Contents

Introduction
Data Wrangling
Exploratory Data Analysis
Conclusions
Introduction

Dataset Description

This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters. There are some odd characters in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is. The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

Question(s) for Analysis

What factors best predict profit_adj (revenue_adj − budget_adj): budget_adj, genre, runtime, popularity, or cast size?
Which production companies produce the most profitable movies on average?
What is the distribution of ROI and how many movies are loss-making versus profitable?

Data Cleaning

Remove duplicates
Handle missing values
Convert data types as needed
Standardize text data
Remove outliers as needed
Rename columns for clarity
Print out a few lines of the claened dataframe

Research Question 1: What factors best predict profit_adj (revenue_adj − budget_adj): budget_adj, genre, runtime, popularity, or cast size?

<img width="866" height="783" alt="image" src="https://github.com/user-attachments/assets/6fdf94ae-a3cd-4274-8f97-4b0ecbcb93aa" />

The budget distribution shows that most movies have a budget below $50 million, with a long tail extending to higher budgets. This indicates that while a few movies have very high budgets, the majority are produced with more modest financial resources. The mean budget is higher than the median, suggesting that a few high-budget films are skewing the average upwards.

<img width="850" height="547" alt="image" src="https://github.com/user-attachments/assets/255c3201-76f4-41dd-a746-27e3f3bc70a7" />
