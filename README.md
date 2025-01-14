# App Dataset Analysis

## Overview

This project analyzes app and user review datasets to extract insights and provide actionable recommendations for app developers, marketers, and product managers. The analysis includes:
- Category exploration
- Ratings distribution
- App size analysis
- Top-performing apps by installs
- Price distribution for paid apps
- Sentiment analysis of user reviews
- Interactive visualizations

## Datasets

1. Apps Dataset (apps_cleaned.csv)

Contains information about various apps, including their category, ratings, size, installs, type (free or paid), and pricing.

### Key Features: 

- App: Name of the app.    
- category: App category (e.g., ART_AND_DESIGN, GAME, etc.).

- Rating: Average user rating for the app.

- Reviews: Total number of reviews for the app.

- Size: App size in MB.

- Installs: Total install count.

- Type: Free or Paid.

- Price: Price for paid apps.

2. User Reviews Dataset (user_reviews_cleaned.csv)

Contains processed user reviews and their associated sentiment analysis.

### Key Features: 

- App: Name of the app.

- Translated_Review: Processed text of user reviews.

- Sentiment: Sentiment of the review (Positive, Negative, Neutral).

- Sentiment_Polarity: Score ranging from -1 (negative) to 1 (positive).

## Visualizations

The analysis includes both static and interactive visualizations:

- Category Distribution: Bar chart showing the number of apps per category.

![image](https://github.com/user-attachments/assets/e68f6865-2d20-4001-a151-d03aca4bbfca)


- Ratings Distribution: Histogram of app ratings.

![image](https://github.com/user-attachments/assets/72599f19-09f8-4571-bfd9-8dc9887db59e)

- Size Distribution: Boxplot of app sizes (MB).

![image](https://github.com/user-attachments/assets/c3f35b53-9f1d-452e-981c-81e68cd2396c)

- Top 10 Apps by Installs: Horizontal bar chart of install counts.

![image](https://github.com/user-attachments/assets/ad42154f-c08d-44ad-8065-a877a41a556d)

- Price Distribution: Boxplot of prices for paid apps.

![image](https://github.com/user-attachments/assets/6e3946c1-a1da-4b6a-968d-1879ba58ad1e)

- Sentiment Distribution: Pie chart of review sentiments.

![image](https://github.com/user-attachments/assets/6d7132f8-abe5-4bc9-b5df-cb84398d430a)

- Interactive Visualization: Scatter plot of app ratings vs. installs, segmented by size and category.

![image](https://github.com/user-attachments/assets/8bc282fd-2cc7-41f0-9d2c-40ac940f0f06)

## Key Insights

### Category Exploration

- Most apps are in the FAMILY category (1,512 apps), followed by GAME (832 apps).

- LIFESTYLE and PERSONALIZATION categories have fewer apps, indicating potential niches.

### Ratings Distribution

Average rating: 4.16.

75% of apps are rated 4.0 or higher, demonstrating strong user satisfaction.

### App Size Analysis

- Average size: 21.75 MB, with most apps under 31 MB.

- Larger apps may face adoption challenges in markets with limited device storage.

### Top Apps by Installs

- Apps like Google News and Subway Surfers have over 1 billion installs.

- High install counts correlate with strong brand recognition.

### Price Distribution

- Average price for paid apps: $15.24, with most priced between $0.99 and $4.99.

- Premium apps priced up to $400 cater to niche audiences.

### Sentiment Analysis

- Positive sentiment dominates (19,015 reviews), followed by Negative (6,321) and Neutral (4,356).

- Negative reviews highlight areas for improvement, with an average polarity of -0.26.

## Recommendations

### For Developers:

- Focus on underrepresented categories like LIFESTYLE and PERSONALIZATION.

- Optimize app size to cater to users with limited storage.

- Regularly analyze user feedback to maintain high ratings and address common complaints.

### For Marketers:

- Highlight high ratings and positive user reviews in promotional campaigns.

- Use competitive pricing strategies for paid apps or consider freemium models.

### For Product Managers:

- Analyze top apps for best practices in acquisition and retention.

- Use sentiment analysis to identify features that resonate well with users and improve less popular ones.

