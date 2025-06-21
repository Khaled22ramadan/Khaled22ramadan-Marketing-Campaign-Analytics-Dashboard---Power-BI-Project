# Khaled22ramadan-Marketing-Campaign-Analytics-Dashboard---Power-BI-Project
First freelance project

Marketing Campaign Analytics Dashboard - Power BI Project
This repository contains the files and documentation for a comprehensive marketing analytics dashboard built with Microsoft Power BI. This project was developed as my first end-to-end freelance engagement to provide a client with actionable insights into their marketing campaign performance.

► Live Demo


► Project Objective
The primary objective of this dashboard is to assess the effectiveness of various marketing campaigns to enhance future marketing strategies and optimize budget allocation. The dashboard answers critical business questions related to campaign performance, channel efficiency, customer demographics, and profitability.

► Dashboard Structure
The report is structured across three key pages for a logical and intuitive user experience:

Overview Page: Provides a high-level, at-a-glance summary of the overall marketing performance. It features main KPIs and trend lines for key metrics like Impressions, Clicks, Spend, and Conversions over time.

Campaigns Page: A dedicated deep-dive into the performance of individual campaigns and marketing channels. This page directly compares campaigns on conversion rate, profitability, and cost-efficiency.

Users Performance Page: Focuses on customer-centric analysis. It breaks down performance by key demographic segments (Age, Gender, Location) to identify the most valuable audiences.

► Key Features & Analysis
This dashboard incorporates several layers of analysis to meet the project requirements:

KPI Monitoring: Displays 10+ key performance indicators, including Total Spend, Total Revenue, Net Profit, ROAS, CPA, CPC, CTR, and Conversion Rate.

Campaign & Channel Comparison: Utilizes donut charts and a detailed performance table to visually compare the conversion rates and profitability of different campaigns and marketing channels (Email, Paid Ads, Social Media, etc.).

Profitability Analysis: Bar charts clearly visualize Total Spend vs. Total Revenue for each channel, immediately highlighting the most profitable areas of the marketing strategy.

Demographic Insights: Segmented analysis of conversions and revenue by Age, Gender, and Location to identify high-performing customer groups and guide future ad targeting.

Time-Series Analysis: Line charts track performance metrics over time, helping to identify seasonal trends and the impact of campaign launches.

► Technical Stack
Tool: Microsoft Power BI

Language: DAX (Data Analysis Expressions) for creating all calculated measures and KPIs.

► DAX Measures Showcase
The core of this analysis is built on a robust data model with powerful DAX measures. Here are a few key examples:

1. Return on Advertising Spend (ROAS): The ultimate measure of profitability.

ROAS = 
DIVIDE(
    SUM('YourTable'[Revenue_Generated]), 
    SUM('YourTable'[Total_Spend]), 
    0
)

2. Cost Per Acquisition (CPA): The core metric for cost-efficiency.

CPA = 
DIVIDE(
    SUM('YourTable'[Total_Spend]), 
    SUM('YourTable'[Conversions]), 
    0
)

3. Net Profit: A clear indicator of financial success after ad spend.

Net Profit = 
SUM('YourTable'[Revenue_Generated]) - SUM('YourTable'[Total_Spend])

4. Conversion Rate (CR): Measures the effectiveness of turning clicks into valuable actions.

Conversion Rate = 
DIVIDE(
    SUM('YourTable'[Conversions]), 
    SUM('YourTable'[Clicks]), 
    0
)

► How to Use This Repository
Clone or download this repository.

The .pbix file contains the full Power BI report. You will need Power BI Desktop installed to open it.

Once open, you can interact with all visuals, view the data model, and examine all the DAX measures created for the project.

► Contact
I'm actively seeking new freelance opportunities and full-time roles in data analytics. Let's connect!

LinkedIn: https://www.linkedin.com/in/khaled-ramadan-143610232/

Email: khaled.ramadan.ali22@gmail.com
