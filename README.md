# Capstone-Project
## 📘 Project Description
1. Introduction:
This project aims to analyze and evaluate the performance of digital marketing campaigns by applying linear regression modeling. It focuses on identifying the key factors that influence sales conversion and assessing the effectiveness of marketing activities under three main factors:
- Engagement
- Conversion
- Spending

2. Data sources:
The data chosen from public dataset from Kaggle (Link: https://www.kaggle.com/datasets/loveall/clicks-conversion-tracking)

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
- Objective 1: Determine key factors that influence conversion.
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

## 📈 Key Insights

**1. Demographic pattern**
- Campaign_a: more ads for males aged from 30-34
- Campaign_b: more ads for females aged from 30-34
- Campaign_c: more ads for males aged from 30-34
  
**2. Strategic approach of each campaign:**
- Campaign_c represents the company’s largest project, with the highest overall investment and activity level. This project may follow the **mass targeting strategies**.
- Although Campaign_b also had a high number of ads (approximately 80% of Campaign_c’s volume), its spending accounted for only about 5% of Campaign_c’s total. This indicates that Campaign_b prioritized **organic engagement and cost efficiency rather than heavy paid promotion**.
- Campaign_a operated with limited investment and smaller scale, suggesting a **niche targeting strategy** that focuses on a specific audience segment to maximize cost efficiency while maintaining solid performance.

**3. Insights**
- **Campaign_a** adopted a niche targeting strategy with optimized spending yet achieved strong performance. It engaged primarily older males (40–49 years).
- **Campaigns_b** and **campaign_c** had higher investments and broader reach, engaging mostly ages 45–49, but the 30–34 age group drove the most conversions.
- Ads associated with interest codes #16, #10, and #29 generated the highest ad engagement and conversions.

## 💡 Actionable recommendations

These recommendations are suggested for future enhancements:

**1. Refine  target audience and marketng strategies:**
- Refine audience segmentation to reduce wasted impressions and improve targeting precision.
- For niche marketing campaigns: focus on older people and implementing personalization strengthen connection with the niche group.
- For mass targeting campaigns: focus on young people 30–34 from all gender demographic as a core conversion driver.
**2. Organic and cost efficient strategy:**
- Leverage user generated content and community engagement to sustain organic growth.
- Enhance SEO and social media optimization to strengthen visibility without increasing ad spend.
**3. Align Content with Top Interests:**
- Develop ad creatives and materials around interest categories #16, #10, and #29 to maximize relevance and engagement.
