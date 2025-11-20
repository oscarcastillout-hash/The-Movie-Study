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

Both budget and revenue distributions are right-skewed, indicating that while most movies have moderate budgets and revenues, a few blockbuster films have extremely high values, significantly impacting the average.

<img width="850" height="547" alt="image" src="https://github.com/user-attachments/assets/648f85b4-4bf6-4878-a5a5-743858e7432e" />

The runtime distribution indicates that most movies have a runtime between 80 and 140 minutes, with a peak around 100-120 minutes. This suggests that filmmakers tend to favor this range for feature-length films.

<img width="850" height="547" alt="image" src="https://github.com/user-attachments/assets/b48a12a2-e3a9-4147-9fe2-76ea8101fc52" />

The genre distribution shows that certain genres, such as Drama and Comedy, are more prevalent in the dataset. This could be due to their broad appeal and versatility in storytelling, making them popular choices for filmmakers. Other genres like Horror and Science Fiction are less common, possibly reflecting niche audiences or higher production costs associated with these genres.

<img width="1002" height="547" alt="image" src="https://github.com/user-attachments/assets/9fc372e0-7dcf-40f8-ac0b-8da854cc856d" />

The popularity score distribution indicates how frequently movies are viewed or rated. A right-skewed distribution suggests that most movies have lower popularity scores, with a few movies achieving very high popularity. This pattern is common in entertainment, where a small number of blockbuster hits dominate audience attention.

<img width="850" height="547" alt="image" src="https://github.com/user-attachments/assets/811d1d1c-ef44-4c9c-807f-7944d27c76e8" />

The most profitable companies on average tend to be those with a strong track record of successful films, effective budgeting, and popular franchises. These companies likely have better resources, talent, and market strategies that contribute to higher profitability.

<img width="1606" height="1243" alt="image" src="https://github.com/user-attachments/assets/cb1e0487-3e3f-45e3-9104-9a1baeb4d3d9" />

The ROI distribution shows the profitability of movies relative to their budgets. A significant number of movies have negative ROI, indicating they lost money. However, there are also movies with very high ROI, suggesting some films are highly profitable. The distribution is likely right-skewed, reflecting a few blockbuster successes amidst many less profitable films.

<img width="859" height="547" alt="image" src="https://github.com/user-attachments/assets/c46531ec-76ca-4aa0-a346-b2c6bbe22d97" />

The scatter plot shows a positive correlation between budget and revenue, indicating that movies with higher budgets tend to generate higher revenues. However, there is considerable variability, suggesting that a large budget does not guarantee high revenue. Some low-budget movies also achieve significant revenue, highlighting the influence of other factors such as genre, marketing, and audience reception.

<img width="846" height="547" alt="image" src="https://github.com/user-attachments/assets/fd82ed7c-a710-4113-9a97-eda3f4a232e7" />

The line plot indicates trends in movie releases over the years. There may be periods of increased movie production, possibly due to industry growth, technological advancements, or changes in audience demand. Peaks in movie releases could correspond to specific events in the film industry or broader economic conditions that encourage or discourage movie production.

<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/88eb6009-e219-42cb-a82b-5e6bb39a7ce7" />







