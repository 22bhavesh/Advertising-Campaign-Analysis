# Ad Campaign Performance Analysis

## Project Background
This project focuses on the performance evaluation of digital ad campaigns for an online marketing company. The goal is to optimize future campaigns by analyzing audience segmentation, campaign performance, and ROI.

## Insights and recommendations are provided on the following key areas:

- Audience Segmentation Analysis
- Campaign Performance Evaluation
- ROI Analysis

The Python scripts used for data analysis can be found in the repository.

## Data Structure & Initial Checks

The dataset consists of the following key fields:

- Campaign ID: Unique identifier for each campaign.
- Age Group: Age range of the audience targeted.
- Gender: Male/Female.
- Impressions: Number of times the ad was shown.
- Clicks: Number of times the ad was clicked.
- Conversions: Number of successful actions (e.g., purchases).
- Cost: Total cost of running the campaign.
- Revenue: Total revenue generated by the campaign.

## Initial Checks Performed

Data quality verification, including missing values and outlier detection.

Data type validation for numerical and categorical fields.

Summary statistics for initial insights.

# Executive Summary

## Overview of Findings

- Audience segmentation revealed the age group 30-34 as the most cost-effective with the highest conversions.

- Campaign 916 demonstrated the best ROI, indicating its efficiency in generating returns.

- Campaign 1178, while generating the highest revenue, was less efficient with a lower ROI.

[Placeholder for visualization: Overview of campaign performance]

# Insights Deep Dive

## Audience Segmentation Analysis

- Main Insight 1: The 30-34 age group had the lowest cost per conversion (29.77) and the Highest Approved conversions (494), making it the most cost-effective target for future campaigns.

![image](https://github.com/user-attachments/assets/170d08bc-c26e-43a6-af55-8939b3fd4521)

- Main Insight 2: Females generated more clicks (23,878) but had a higher cost per conversion (68.48), suggesting the need for refined targeting strategies.

![image](https://github.com/user-attachments/assets/4bfcc0ec-4f47-4fae-a000-3bb7c06c84cf)

- Main Insight 3: Interest category 31 (likely Technology or Gaming) had the lowest cost per conversion (18.69), highlighting it as a highly responsive audience.

![image](https://github.com/user-attachments/assets/c0371ced-e993-4023-aa68-d6ebf3ae8e85)

![image](https://github.com/user-attachments/assets/1206020c-1d0c-4408-8f89-866079a5cc76)
![image](https://github.com/user-attachments/assets/740008d1-97a7-47b7-9df0-c56165cb8604)
![image](https://github.com/user-attachments/assets/c8ed7f8b-6d02-4128-89b4-e9c928421cf9)

## Campaign Performance Evaluation

- Main Insight 1: Campaign 936 had the highest conversions (183) and a moderate cost per conversion (15.81), making it a strong performer.

- Main Insight 2: Campaign 1178 had the highest impressions and clicks but showed inefficiency with a high cost per conversion (62.49).

- Main Insight 3: Campaign 916 achieved the lowest cost per conversion (6.24) and provided a good balance of cost-efficiency and performance.

![image](https://github.com/user-attachments/assets/d0e98285-d444-41b9-841d-6efa7a30eb95)
![image](https://github.com/user-attachments/assets/24f0e193-0dbc-4220-80cd-a79dd76d6669)
![image](https://github.com/user-attachments/assets/c47278a4-6c68-4202-a78d-4688ef65069b)

## ROI Analysis

- Main Insight 1: Campaign 916 achieved the highest ROI of 7915.50%, with a revenue of 12,000 against a modest spend of 149.71.

- Main Insight 2: Campaign 936 generated substantial revenue (91,500) with a solid ROI of 3062.40%.

- Main Insight 3: Campaign 1178, despite generating the highest revenue (436,000), had the lowest ROI of 700.19%, indicating inefficiency in cost utilization.

![image](https://github.com/user-attachments/assets/5889d533-bbfb-4105-85f7-f04bdeae92b0)
![image](https://github.com/user-attachments/assets/09bc4360-bf60-43ba-bb10-1237d2c10759)
![image](https://github.com/user-attachments/assets/f526ecb5-f8c4-428e-bff1-56f3c4dc6d4a)

## Recommendations
Based on the findings, the following recommendations are proposed:

- Audience Targeting: Prioritize the 30-34 age group and interest category 31 for cost-effective conversions.

- Campaign Optimization: Refine campaigns targeting females to improve conversion efficiency.

- Budget Allocation: Allocate higher budgets to campaigns like 916 and 936 that demonstrate high ROI and cost-efficiency.

- Performance Monitoring: Continuously monitor ROI and cost-per-conversion metrics to adjust strategies in real-time.

## Assumptions and Caveats

- Missing values in gender were imputed using the mode.

- Outliers in cost data were excluded to prevent skewed insights.

- Data is assumed to represent the entire campaign period accurately.

This project was conducted using Python libraries such as Pandas, Matplotlib, and Seaborn. The code and detailed analysis can be accessed in the accompanying Jupyter Notebook file.

