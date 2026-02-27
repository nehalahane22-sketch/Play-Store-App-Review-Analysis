GOOGLE PLAY STORE APP REVIEW ANALYSIS

Data-Driven Insights from App Metadata & User Sentiment
🔎 PROJECT OVERVIEW

This project presents a comprehensive Exploratory Data Analysis (EDA) of Google Play Store applications combined with user review sentiment analysis. The objective is to uncover patterns in app performance, ratings, installs, pricing strategies, and user feedback trends.

The analysis integrates structured app metadata with unstructured review sentiment data to derive actionable business insights that can support product strategy, monetization optimization, and user engagement improvement.

🎯 PROBLEM STATEMENT

The mobile application ecosystem is highly competitive. Understanding what drives higher ratings, more installs, and positive user sentiment is critical for app developers and business stakeholders.

This project aims to answer:

What factors influence app ratings?

How do installs and reviews correlate?

Do paid apps perform better than free apps?

How does user sentiment align with ratings?

Which app categories dominate the marketplace?

📊 DATASET DESCRIPTION

The analysis is based on two datasets:

Play Store Application Data

This dataset contains detailed metadata about applications including category, rating, number of reviews, number of installs, pricing, content rating, and last update information.

User Review Data

This dataset includes user review text along with sentiment classification, sentiment polarity, and subjectivity scores.

Both datasets were cleaned, processed, and merged to generate consolidated analytical insights.

🧹 DATA PREPROCESSING

Before performing analysis, extensive data cleaning and transformation steps were applied.

Text-based numeric fields such as installs and price were cleaned and converted into numerical formats. Missing values in rating and review-related columns were handled appropriately. Duplicate applications were removed to ensure accuracy. Date fields were converted into proper datetime format to enable time-based analysis.

The datasets were then merged using the app name as the key identifier, enabling combined metadata and sentiment evaluation.

📈 EXPLORATORY DATA ANALYSIS

The exploratory phase focused on identifying structural patterns in the dataset.

App category distribution was analyzed to determine dominant segments in the marketplace. Rating trends were evaluated to understand how user feedback varies across categories. Install patterns were studied to assess popularity distribution among applications.

A detailed pricing analysis was conducted to compare performance between free and paid applications. The relationship between reviews, installs, and ratings was examined using correlation analysis.

User sentiment analysis provided deeper insight into customer perception by evaluating polarity and sentiment distribution across different app categories.

🔍 KEY INSIGHTS

The analysis revealed that free applications dominate the platform in terms of total installs, while paid applications represent a smaller but more niche market segment.

There is a strong relationship between the number of reviews and installs, indicating that higher user engagement contributes to increased visibility.

Sentiment polarity aligns closely with rating trends, validating the importance of qualitative feedback in influencing app reputation.

Certain categories consistently achieve higher ratings and stronger user sentiment, suggesting targeted investment opportunities for developers.

💡 BUSINESS RECOMMENDATIONS

Developers should focus on improving review management strategies to maintain higher ratings and user trust.

Pricing strategy should be optimized based on category competition and user demand patterns.

Sentiment monitoring can serve as an early detection mechanism for performance issues.

High-growth categories identified through install and rating trends represent strong expansion opportunities.

🛠 TECHNOLOGY STACK

Python was used as the primary programming language for the analysis.

Data manipulation and transformation were performed using Pandas and NumPy. Visualization and pattern analysis were conducted using Matplotlib and Seaborn within a Jupyter Notebook environment.
