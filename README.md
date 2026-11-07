# Python for Data Analysis: Assignments & Mini Projects

A collection of Python notebooks from my data analytics training, from core Python logic to data analysis, visualisation and a full engagement-analytics project.

## Contents

| Notebook | Topic |
|---|---|
| `Python Assignment 9 (Loops, Functions).ipynb` | `while` loop number-guessing game with 3 attempts, multiplication table with a `for` loop, BMI calculator function |
| `loan_eligibility_process_.ipynb` | Rule-based loan eligibility check on age, income, credit score and employment status, with a Premium or Standard tier |
| `Assignment_10_NumPy_and_Pandas_.ipynb` | NumPy 1D/2D arrays (temperature data), pandas Series (ranked marks) and a DataFrame of transactions: filtering, `groupby`, add/update/drop rows and columns |
| `Python_DA_Assignment_2_Data_Visualization_.ipynb` | Seaborn `taxis` dataset (6,433 trips): missing-value handling, Matplotlib charts (line, bar, pie, histogram, box) and Seaborn charts (count, scatter, heatmap, pair, violin) |
| `Module_End_Assessment_4_Python_Survey_Feedback_Analyzer_.ipynb` | Survey feedback analyzer: text cleaning, word counts for "good", "poor", "excellent", average rating, longest comment, unique words |
| `Social Media Engagement Analytics.ipynb` | End-to-end analysis of 5,000 social media posts (see below) |

## Featured Project: Social Media Engagement Analytics
Dataset: `social_media_engagement_5000.csv` (5,000 rows, 19 columns).
- **Cleaning:** 900 missing values handled (median for numeric columns, mode for categorical), no duplicates, categories standardised, likes/comments/shares capped at the 99th percentile, hashtag count extracted
- **Feature engineering:** `engagement_score` and `log_likes`
- **Analysis:** descriptive statistics, correlations, group summaries, then Matplotlib, Seaborn and interactive Plotly charts
- **Findings:**
  - Videos have the highest average engagement rate (1.12), ahead of text (1.06), image (0.90) and reel (0.78)
  - Food is the top category (1.36); travel (0.70) and fashion (0.81) lag
  - Brazil leads on engagement rate (1.54), while the USA (0.58) and India (0.66) are lowest despite high impressions
  - Age has almost no relationship with engagement (correlation about 0.01)
  - Verified accounts have a slightly higher engagement rate (1.05 vs 0.96)
  - Mobile users watch the longest (about 4,088 sec on average)
  - Sentiment has little effect: all three groups are within about 3% on likes

## Skills Demonstrated
- Python fundamentals: loops, functions, conditionals, data structures
- Data wrangling with pandas and NumPy
- Data visualisation with Matplotlib, Seaborn and Plotly
- Data cleaning, imputation and outlier handling
- Turning raw data into simple insights

## How to Run
```bash
git clone https://github.com/arjunajikumar-svg/Base-Python-Assignment-.git
pip install pandas numpy matplotlib seaborn plotly jupyter
jupyter notebook
```

