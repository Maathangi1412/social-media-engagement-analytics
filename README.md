# Social Media Engagement Analytics Using Python

## Project Overview

This project analyzes a dataset containing 5,000 social media engagement records. The objective is to understand content performance, user behavior, engagement patterns, device usage, and sentiment using Python.

## Dataset

The dataset contains social media engagement information including:

- User ID and age
- Gender and country
- Post type and post category
- Likes, comments, and shares
- Watch time and impressions
- Follower count
- Verification status
- Device type
- Sentiment
- Hashtags
- Engagement rate
- Posting date and time

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Google Colab / Jupyter Notebook

## Project Tasks

### 1. Data Import and Setup
- Imported the CSV dataset using Pandas
- Checked data types
- Converted the posting date column to datetime format

### 2. Data Cleaning
- Identified and handled missing values
- Checked for duplicate records
- Corrected data types
- Standardized categorical values
- Corrected unrealistic engagement values
- Extracted hashtag counts
- Cleaned sentiment labels

### 3. Data Exploration
- Examined dataset structure using `head()`, `tail()`, `shape`, and `columns`
- Used `info()` and `dtypes`
- Generated descriptive statistics
- Analyzed categorical distributions
- Created correlation matrices
- Performed groupby analysis

### 4. Data Wrangling
Created additional features including:
- Engagement score
- Hashtag count
- Log-transformed metrics
- Date and time-related features

### 5. Statistical Analysis
Calculated:
- Mean
- Median
- Mode
- Standard deviation
- Variance
- Percentiles
- Skewness and kurtosis

for important engagement metrics.

### 6. Data Visualization
Created visualizations using Matplotlib, Seaborn, and Plotly, including:

- Likes vs impressions scatter plot
- Daily engagement trend
- Posts by category
- Gender distribution
- Age distribution
- Engagement rate box plot
- Post type count plot
- Average likes by category
- Followers vs sentiment violin plot
- Pair plot
- Correlation heatmap
- Engagement by device swarm plot
- Interactive Plotly charts

## Key Findings

- **Video posts** had the highest average engagement rate at approximately **1.12**.
- **Food** was the best-performing content category with an average engagement rate of approximately **1.36**.
- **Brazil** recorded the highest average engagement rate at approximately **1.54**.
- **Verified accounts** had a higher average engagement rate (**1.05**) than non-verified accounts (**0.95**).
- **Mobile users** had the highest average watch time at approximately **4,087.83 seconds**.
- **Negative sentiment posts** had the highest average engagement rate at approximately **1.04**.
- Posting-time analysis could not reliably identify the best time of day because all records had a posting hour of 0.

## Conclusion

The analysis demonstrates how Python can be used to clean, transform, analyze, and visualize social media engagement data. The findings indicate that content type, content category, country, verification status, device type, and sentiment are associated with differences in engagement. These insights can support data-driven social media content strategies.

## Project Files

- `social_media_engagement_5000.csv` — Original dataset
- `Social_Media_Engagement_Analytics.ipynb` — Python/Google Colab notebook
- `README.md` — Project documentation

**👩‍💻 Author**

**Maathangi**

Aspiring Data Analyst | Microsoft Excel | SQL | Power BI | Python

🔗 **GitHub:** https://github.com/Maathangi1412

🔗 **LinkedIn:** www.linkedin.com/in/maathangi-p-560266333
