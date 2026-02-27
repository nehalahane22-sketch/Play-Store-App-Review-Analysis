# Play-Store-App-Review-Analysis
📱 Google Play Store App Analysis & User Review Insights
📌 Project Overview

This project performs comprehensive Exploratory Data Analysis (EDA) on Google Play Store applications and user reviews to uncover trends in app performance, user engagement, ratings, pricing models, and sentiment patterns.

The analysis combines app-level data with user review data to generate business insights that can help improve app strategy, monetization, and user satisfaction.

🎯 Business Objectives

Analyze app categories and distribution patterns

Identify factors influencing app ratings

Study relationship between installs, price, and ratings

Examine free vs paid app performance

Analyze user sentiment trends from reviews

Provide data-driven recommendations for app growth and optimization

📂 Dataset Description
1️⃣ Play Store Data

Contains metadata about applications including:

App Name

Category

Rating

Reviews

Installs

Type (Free/Paid)

Price

Content Rating

Genres

Last Updated

Android Version

2️⃣ User Reviews Data

Contains:

App Name

User Review

Sentiment (Positive / Negative / Neutral)

Sentiment Polarity

Sentiment Subjectivity

🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

Removed duplicate applications

Handled missing values in rating and review fields

Cleaned special characters from Installs column

Converted Price and Reviews columns into numeric format

Standardized categorical variables

Merged Play Store data with User Reviews dataset

Converted date fields into datetime format

📊 Exploratory Data Analysis
1️⃣ App Distribution Analysis

Most popular app categories

Category-wise rating distribution

Content rating breakdown

2️⃣ Ratings & Install Analysis

Relationship between number of installs and ratings

Impact of reviews on app ratings

High-install vs high-rating comparison

3️⃣ Pricing Analysis

Free vs Paid app distribution

Price range impact on ratings

Revenue opportunity patterns

4️⃣ Sentiment Analysis

Distribution of Positive, Negative, and Neutral reviews

Sentiment polarity trends

App categories with highest positive sentiment

5️⃣ Correlation Analysis

Correlation between:

Reviews & Installs

Rating & Reviews

Price & Rating

🔍 Key Insights

📈 Free apps dominate the marketplace in terms of installs

⭐ Apps with higher review counts tend to maintain stable ratings

💰 Paid apps are fewer but may have niche loyal user bases

🧠 Sentiment analysis reveals strong alignment between polarity score and rating

📊 Certain categories consistently receive higher engagement

💡 Business Recommendations

Focus on user review management to improve ratings

Encourage feedback from high-install user base

Optimize pricing strategy based on category competition

Use sentiment analysis for early issue detection

Invest in high-growth categories for better ROI

🛠 Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook
