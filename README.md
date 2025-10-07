# Capstone-Project
## 📘 Project Description
1. Introduction:
This project aims to analyze and evaluate the performance of digital marketing campaigns by applying linear regression modeling. It focuses on identifying the key factors that influence sales conversion and assessing the effectiveness of marketing activities under three main factors:
- Engagement
- Conversion
- Spending

2. Data sources:
The data from public dataset from Kaggle (Link:

| Variable                | Description                                                                                          |
| ----------------------- | ---------------------------------------------------------------------------------------------------- |
| **ad_id**               | A unique identifier assigned to each advertisement.                                                  |
| **xyzcampaignid**       | Identifier representing the campaign managed by company XYZ.                                         |
| **fbcampaignid**        | Identifier used by Facebook to track each campaign’s performance.                                    |
| **age**                 | Age group of the audience that the ad was displayed to.                                              |
| **gender**              | Gender of the audience viewing the ad.                                                               |
| **interest**            | A coded category representing user interests based on their Facebook profile.                        |
| **impressions**         | The total number of times the ad was shown to users.                                                 |
| **clicks**              | The number of times users clicked on the advertisement.                                              |
| **spent**               | The amount (in USD) spent by XYZ to display the ad on Facebook.                                      |
| **total_conversion**    | The total number of people who expressed interest or inquired about the product after seeing the ad. |
| **approved_conversion** | The number of users who made a purchase after viewing the ad.                                        |


## 🔍 Project Scope
1. Exploratory Data Analysis (EDA)
   - Analyze and visualize campaign data to understand trends and digital performance.
   - Identify relationships among engagement, spending, and conversion metrics.
2. Model Building
   - Build and evaluate a linear regression model to determine which factors most strongly influence customer conversion.
   - Use the model to assess the effectiveness of marketing campaigns and provide actionable insights.

## 🎯 Objectives
- Objective 1: Determine key factors that influence customer conversion rates.
- Objective 2: Evaluate the digital effectiveness of each campaign to guide future marketing strategies.

## 👥 Target Audience
This analysis is designed for:
- Digital Marketing Teams / Marketing Analysts
- Performance Marketing Managers
- Marketing Executives and Decision Makers
- Other relevant business stakeholders

## 💻 Technologies Used
- Programming Language: Python
- Libraries: pandas, numpy, matplotlib.pyplot, seaborn, statsmodels.api, sklearn.model_selection

## Limitations
**1. Lack of timeframe information:**   

It is not possible to accurately assess their performance over time or account for variations due to seasonal factors (e.g., New Year, Christmas). To maintain consistency and comparability, this analysis assumes that all three campaigns were executed concurrently over a standardized period of three months.

**2. Lack of financial data (revenue, other costs (e.g. operational cost, HR cost,...):**

This can limit the thorough analysis on performance metrics such as customers acquisition cost (CAC), or understand the profitability. Hence, this analysis focuses solely on digital marketing effectiveness. Specifically, it evaluates the cost of acquiring customers through ad spending and identifies which campaign demonstrates the most cost-effective performance.


