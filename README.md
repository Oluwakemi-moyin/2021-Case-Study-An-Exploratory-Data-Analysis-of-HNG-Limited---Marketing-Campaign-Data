# 2021-Case-Study-An-Exploratory-Data-Analysis-of-HNG-Limited---Marketing-Campaign-Data

Tools used: Python.

### Introduction

### Overview

- The dataset contains key columns like; Campaign_ID, Company, Company_Type, Target_Audience, Duration, Channel_Used, Conversion_Rate, Acquisition_Cost, ROI, Location, Date, Clicks, Impressions, Engagement_Score, Customer_Segment.

- Data types :The data types available- object,float64, Date(had to convert to datetime64 using Python) and int64

- Dataset size: The dataset has a total count of 3,000,009 and 15 Columns with count of 200,006 inclusive of Headers for each Column.


### Analysis Objective

Perform exploratory data analysis (EDA) on HNG Limited Marketing Campaign dataset to understand the dataset better and uncover key insights that can guide strategic decision-making. 

### Key Metrics;

- Cost per Click(CPC)

- Click Through Rate(CTR)

- ROI

- Conversion Rate

- Campaign performance across diff channels

### Insights

● Email Marketing channel drives the highest Conversion rate of 2,697.38 followed by Google adswith 2,681.24

● Facebook Marketing channel has the lowest total Conversionrate of 2,625.27

● Email Marketing channel brought in the highest ROI of 167,876.95

● Facebook Channel brought in the lowest ROI of 164,712.81

### Key observations

● Los Angeles has the highest Click through rate(CTR) of 10.000601

● Miami has the lowest CTR of 9.964758

● Campaign_ID 122375 has the highest CTR of 99.20239282

● Campaign_ID 44685 has the lowest CTR of 1.0054293

● Men 18-24 has the highest CTR of 565563.5104

● Women 35-44 has the lowest CTR of 557,928.1631

● Foodies segment have the highest CTR of 568,619.9628

● Fashionistas has the lowest CTR of 556,200.5961

● Google ads has the highest Cost per click with value 108,039,487.6 USD

● Facebook has the lowest cpc with value 105,448,579.3 USD

### Recommendations

● Tailor future campaigns to the unique needs and preferences of  each segment(focus more on Men 18-24) to increase conversion rates.

● Shift budget towards the most effective channels(e.g.Email and Google ads) and reallocate from underperforming ones(e.g. Facebook)

● Leverage Customer Feedback and Insights from surveys, reviews, personal interactions,etc

### Actionable Insights 
- Given the success of email marketing, future campaigns should prioritize personalized email strategies for the Men 18-24 age group, while experimenting with additional social media platforms to boost engagement.
- The spend trend is both increasing and decreasing.It was at its lowest in February 2021 but thereafter increased the following month. It was at an all high in August 2021 followed by January 2021 which had 
the highest ROI. More analysis needs to be done on why spends were that low in February.
- Higher spending leads to higher Conversion rate and ROI e.g. Email marketing channel
- Priority should be given to Foodies segment as it has the highest CTR and ROI

## Conclusion

Based on these findings, I recommend a shift in focus towards optimizing email strategies while exploring new social media channels. Future analyses should consider seasonality to refine targeting efforts. By implementing these recommendations, we expect to improve future campaign outcomes.
