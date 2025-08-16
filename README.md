# A/B Testing Performance Dashboard
## Project Overview

This project demonstrates the end-to-end process of analyzing the performance of two marketing strategies using A/B testing. The goal is to determine which approach-AD campaigns or PSA campaigns-drives higher conversions and engagement. The analysis is enhanced by a visually interactive Power BI dashboard, providing clear insights for decision-makers.

## Objective

Compare the effectiveness of AD vs PSA campaigns on user conversions.

Identify trends in user activity by day and hour.

Quantify uplift in performance for targeted campaigns.

Present actionable insights via an interactive dashboard.

## Tools & Technologies

Excel – Data storage

Power BI – Interactive dashboard development

## Dataset Description

The dataset includes key user interaction metrics:
| Column Name     | Description                                  |
| --------------- | -------------------------------------------- |
| `user_id`       | Unique identifier for each user              |
| `test_group`    | AD group (experiment) or PSA group (control) |
| `converted`     | True if the user converted, False otherwise  |
| `total_ads`     | Number of ads seen by the user               |
| `most_ads_day`  | Day user saw the most ads                    |
| `most_ads_hour` | Hour user saw the most ads                   |


## Groups Explained:

AD Group: Users shown advertisements

PSA Group: Users shown public service announcements

## Methodology

### Dashboard Creation in Power BI:

#### Key Metrics Cards: 
Total Users, Total Conversions, Conversion Rate, Average Ads per User, Uplift PSA vs AD

#### Conversion Rate by Test Group: 
Bar chart for comparison

#### Conversion Rate by Hour of Day: 
Line chart to observe hourly trends

#### Most Active Day: 
Pie chart showing user activity by day

#### Filters: 
Day of week and test group selection for dynamic analysis

## Dashboard Insights

Total Users: 588K across both campaigns

Conversion Rates: AD (2.55%) > PSA (1.79%)

Average Ads per User: 25, indicating campaign intensity

Most Active Day: Friday, suggesting potential for scheduling promotions

Hourly Trends: Conversion peaks between hours 15–19, guiding optimal ad placement

A/B Test Summary Table: Snapshot of total users, conversions, and conversion rates for quick comparisons

## Key Findings:

AD campaign has higher conversion rate (2.55%) than PSA (1.79%)

Most user activity occurs on Friday (93K users)

Peak conversions observed between hour 15–19

Negative uplift (-30%) indicates PSA underperforms compared to AD

## Conclusion

This A/B Testing project demonstrates how data-driven decision-making in marketing can improve campaign performance. Analysis and visualization reveal that AD campaigns substantially increase conversion rates, providing actionable insights for strategic marketing investment.
