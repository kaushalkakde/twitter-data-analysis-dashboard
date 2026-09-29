# Twitter Data Analysis Dashboard

## Project Overview

This project analyzes Twitter data to understand engagement patterns, content categories, and activity over time using Python, SQL, and Power BI.

## Tools Used

- Python
- Pandas
- Matplotlib
- SQL
- Power BI
- GitHub

## Dataset

The project uses a public Twitter dataset containing tweet information such as:

- Tweet text
- Likes
- Retweets
- Replies
- Quotes
- Tweet category
- Creation date

## Project Workflow

### 1. Python Analysis

The dataset was cleaned and analyzed using Python and Pandas.

Analysis included:

- Data quality checks
- Missing-value analysis
- Engagement calculation
- Top tweets by engagement
- Category-level engagement analysis
- Tweet activity over time

Notebook:

`notebooks/Twitter_Data_Analysis.ipynb`

### 2. SQL Analysis

SQL queries were created to analyze:

- Total tweets
- Total engagement
- Top tweets
- Engagement by category
- Tweets by year

SQL file:

`sql/twitter_analysis.sql`

### 3. Power BI Dashboard

An interactive Power BI dashboard was created with:

- Total Tweets
- Total Engagement
- Average Engagement
- Average Engagement by Category
- Top Tweets by Engagement

Power BI file:

`powerbi/Twitter_Analytics_Dashboard.pbix`

## Key Insights

- Identified the tweets with the highest total engagement.
- Compared engagement across different tweet categories.
- Calculated overall and average tweet engagement.
- Created visualizations to communicate engagement patterns.

## Project Structure

```text
twitter-data-analysis-dashboard/
│
├── data/
├── notebooks/
│   └── Twitter_Data_Analysis.ipynb
├── sql/
│   └── twitter_analysis.sql
├── powerbi/
│   └── Twitter_Analytics_Dashboard.pbix
├── README.md
├── LICENSE
└── .gitignore
![Twitter Analytics Dashboard](Twitter_Analytics_Dashboard.png)
