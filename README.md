# global-boxoffice-audience-sentiment-tracker-powerbi-dashboard
📊 Global Box Office & Audience Sentiment Tracker
🌟 Project Overview
This project is an end-to-end Data Analytics solution that tracks global cinema performance and audience sentiment. It bridges the gap between raw ticket sales data and qualitative audience feedback, allowing production houses to understand not just how much they earned, but why audiences liked or disliked a film.

🛠️ Tech Stack
Data Source: CSV/Excel (Global Movie Database)

Analysis Tool: Power BI Desktop

Data Modeling: DAX (Data Analysis Expressions)

Data Cleaning: Power Query (M Language)

AI Integration: Sentiment Analysis & Forecasting

🚀 Key Features & Implementation Steps
1. Data Cleaning (Power Query)
Normalization: Handled missing values in budget and revenue columns.

Standardization: Cleaned genre tags and standardized currency across global markets.

Deduplication: Removed duplicate entries for multi-language releases.

2. Strategic Dashboarding (Power BI)
Revenue vs. Rating Correlation: A scatter plot identifying the "Sweet Spot" where high critical acclaim meets high commercial success.

Sentiment Word Map: Visualizing the most common keywords from audience reviews to identify trending themes.

Geographical Analysis: A map showing regional box office performance to identify untapped markets.

3. Business Logic (DAX)
Created calculated measures for:

ROI (Return on Investment): (Revenue - Budget) / Budget

Average Sentiment Score: Identifying positive vs. negative reception trends.

Success Ratio: Categorizing movies as "Blockbuster," "Hit," or "Flop" based on a dynamic threshold.

💡 Business Insights (The "So What?")
SLA Alerts: Used Conditional Formatting to highlight movies where the sentiment score dropped below 40%, signaling a need for a shift in marketing strategy.

Market Trends: Identified that "Suspense Thriller" genres have the highest ROI in Asian markets compared to Western markets.

Predictive Value: Used the Power BI Trend Line to forecast potential opening weekend earnings for upcoming sequels based on historical sentiment.

📂 Repository Structure
Dashboard/: Contains the .pbix file (Power BI Desktop source file).

Data/: Contains the cleaned CSV/Excel datasets.

Screenshots/: High-resolution images of the final dashboard pages.
