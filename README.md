# Marketing-Analytics
A Power BI dashboard analyzing marketing performance across campaigns, ad spend, web traffic, email, and customer feedback for a mid-size company running ads on Facebook, Google, TikTok, and a few other channels.


## Project Description
The dataset covers two years of marketing activity across 8 channels, spread across 10 related tables, orders, ad spend, web traffic, email sends, customer reviews, and lookup tables for customers, products, and campaigns. It comes as a raw export with several data quality issues: inconsistent date formats, mismatched country names, currency stored as text, and duplicate rows. Total scope is a few thousand orders, 30 campaigns across multiple countries.

## Identified Business Challenges
Marketing spend was spread across multiple channels with no clear view of which ones were actually working. This project aims to answer key questions:

- Which marketing channels deliver the best return on ad spend, and which ones are underperforming?
- How does revenue break down across product categories and regions?
- Where in the email funnel are customers dropping off, opens, clicks, or somewhere else?
- Which products and campaigns are driving the most revenue?
- How does customer sentiment (ratings, reviews) vary across product categories?
- What does the customer base look like by segment, and how many are at risk of churning?

## Tools Used
Power BI Desktop (Power Query, Data Modeling, DAX), Excel (source data)

## Links
Marketing Analytics Dashboard PBIX File
Dataset
Dashboard Screenshots

## Key Insights & Findings
- Marketing ROI & Channel Performance: Instagram Ads is the top-performing channel with a 5.61 ROAS despite a lower budget allocation. Facebook Ads absorbed the highest spend ($50K) with poor efficiency (2.27 ROAS), while Google Ads (1.55) and Referrals (1.81) consistently underperformed.
- Revenue Breakdown: The business does not rely on a single revenue driver. Revenue is evenly distributed across core product lines (Beauty: $233K, Apparel: $230K, Electronics: $225K) and regions (US leads at $185K; Australia/India lowest at $130K). 
- Email Funnel Bottleneck: The main funnel drop-off occurs at the open stage (only 26% of 1.08M emails opened), rather than downstream engagement (<5% click rate among opens).
- Customer Sentiment Disconnect: Overall ratings skew positive (3.73/5 average, 68% positive ratings). However, Beauty shows a satisfaction gap driving the highest revenue while holding the lowest rating (2.8/5).
- Customer Retention: Segments are evenly distributed, with Churned customers accounting for 13.7% of the user base, indicating low immediate churn risk.

