# CAPSTONE-LITA-CUSTOMER-SUBSCRIPTION-PROJECT
This repository is prepared to analyze customer subscription data to gain insights into revenue, subscription plans, regional distribution, customer behavior, and trends over time.

## TABLE OF CONTENT
- [PROJECT TITLE](PROJECT-TITLE)
- [PROPOSED INSIGHT](PROPOSED-INSIGHT)
- [DATA SOURCES](DATA-SOURCES)
- [TOOLS USED](TOOLS-USED)
- [DATA CLEANING AND PREPARATION](DATA-CLEANING-AND-PREPARATION)
- [ANALYSIS AND INSIGHTS](ANALYSIS-AND-INSIGHTS)
- [CONCLUSION](CONCLUSION)
- [RECOMMENDATION](RECOMMENDATION)
- [VISUALIZATION](VISUALIZATION)

## PROJECT TITLE

## **CUSTOMER SUBSCRIPTION DATA ANALYSIS FROM CAPSTONE** 

This project focuses on analyzing subscription data to uncover valuable insights into revenue performance across different plans, regions, and years. It analyzed customer subscription data to gain insights into revenue, subscription plans, regional distribution, customer behavior, and trends over time.

## PROPOSED INSIGHT

The primary objective of this analysis is to identify patterns in customer subscriptions, highlight areas of stability or decline, and recommend strategies for growth. By evaluating the performance of Basic, Standard, and Premium plans across multiple regions which include East, North, West, and South, and tracking trends over 2022 and 2023, the project provides a comprehensive view of how subscription plans are contributing to overall business performance.

Through this analysis, we aim to answer key business questions:

- Which subscription plans generate the highest revenue?
- How do different regions perform in terms of subscriptions and revenue growth?
- Are there signs of revenue decline or stagnation that need to be addressed?
- Which subscription type is most popular?
- What is customer's demand trend across regions?

This project showcases skills in data cleaning, SQL querying, and data visualization using tools like Power BI SQL and Microsoft Excel. 

It also includes recommendations based on the insights uncovered to assist stakeholders in making data-driven decisions.

The analysis and findings are documented in interactive dashboards, reports, and visualizations to ensure clarity and impact. This project demonstrates proficiency in transforming raw subscription data into actionable insights, making it a valuable addition to any business intelligence portfolio.

## DATA SOURCES

The data used for this project was provided by the admin of the Ladies in Tech Initiative as part of a prerequisite project for advancing my analytical journey and fulfilling certification and mentorship requirements.

## TOOLS USED

This project leverages a range of powerful tools to efficiently collect, clean, analyze, and visualize sales data:

- **Microsoft Excel**: Used for initial data exploration, cleaning, and transformation, ensuring data consistency and accuracy.
- **SQL**: Employed for querying and managing data from relational databases, facilitating data extraction and transformation.
- **Power BI**: Utilized to build interactive dashboards and visualizations, providing insights through dynamic reports.

These tools collectively enabled seamless data management and visualization, ensuring accurate reporting and informed decision-making.

## DATA CLEANING AND PREPARATION

The data cleaning process for the sales analysis project involved several key steps to ensure the dataset was accurate, consistent, and ready for analysis:

- Data Collection: The initial dataset was received from the Ladies in Tech Initiative, ensuring all relevant sales information was included.
- Data Inspection: A thorough review of the dataset was conducted to identify any discrepancies, missing values, or outliers that could affect the analysis.
- Standardization: Data formats were standardized, including date formats and categorical values, to ensure uniformity across the dataset.
- Duplicate Removal: Duplicate entries were identified and removed to avoid skewed analysis results.
- Data Validation: Final checks were performed to confirm the accuracy of data entries and to ensure that all values fell within expected ranges.
- Data Loading: Data was loaded into analytics tools for analysis

By following these steps, the dataset was cleaned and optimized for accurate analysis, leading to reliable insights and actionable recommendations.

Data cleaning and preparation process carried out on the data include:

### Excel ###

- Performing an initial exploration of the customer subscription data,
- Using pivot tables to analyze customer data to find subscription patterns.
- Calculate the average subscription duration
- identify the most popular subscription types
- identify termination and renewal rate
- Creating a dashboard to visualize results
  
### SQL ###

- Loading the dataset into SQL Server environment to write and validate queries.
- Writing queries to extract key insights based on the following questions.
  
     *retrieve the total number of customers from each region.*
  
     *find the most popular subscription type by the number of customers.*
  
     *find customers who canceled their subscription within 6 months.*
  
     *calculate the average subscription duration for all customers*
  
     *find customers with subscriptions longer than 12 months*
  
     *calculate total revenue by subscription type.*
  
     *find the top 3 regions by subscription cancellations.*
  
     *find the total number of active and canceled subscriptions*
  
  ### Power BI ###
  
- Build a Power BI dashboard that visualizes key customer segments, 
cancellations, and subscription trends. Include slicers for interactive analysis

## EXCEL

![image](https://github.com/user-attachments/assets/bd2c2b0e-618b-414f-a5e1-97d313419c43)


**FINDINGS FROM SUBSCRIPTION TYPE SOLD PER REGION**

![image](https://github.com/user-attachments/assets/15c77851-affc-472e-9b8b-6a0558a54c5d)

BASIC PLAN (NORTH AND EAST)

There is a high demand for Basic Plans as the North and East regions show strong preference for Basic subscriptions, with the highest counts approaching 9,000 in each region. These regions likely have a large customer base with a preference for lower-tier plans, indicating potential opportunities to upsell or convert some customers to higher tiers (Standard or Premium).

PREMIUM PLAN (SOUTH)

Premium subscriptions are heavily concentrated in the South region, with nearly 9,000 sold. The South region stands out as the primary driver of high-value subscriptions, suggesting that customers here have a higher willingness to pay. Efforts to further promote loyalty or add value to Premium offerings in the South could enhance retention and revenue.

STANDARD PLAN (WEST)

The West region shows strong adoption of Standard plans, while other regions barely engage with this tier. This could imply that customers in the West prefer a balance between features and cost. However, other regions might not find Standard plans attractive, hinting at a potential need to re-evaluate or market Standard plans differently across regions.

*INSIGHT*:

This regional pattern reflects customer segmentation. Marketing strategies can be tailored to target each region based on their preferences. For example, campaigns promoting premium services can focus on the South, while Basic-to-Standard upgrades can target the North and East. North, East, and West regions show no significant engagement with Premium plans. Hence,bThere’s an opportunity to introduce special offers or trials to encourage higher-tier adoption in these regions. Understanding why Premium plans are underutilized in these areas can also guide future strategies.

**FINDINGS FROM TOTAL REVENUE PER REGION**

![image](https://github.com/user-attachments/assets/472af644-1195-4152-99de-c44a135ca28f)

REGIONAL PERFORMANCE

**The East region** is the top performer, with revenue slightly below 17 million. This indicates a strong customer base with high engagement. Marketing efforts here are yielding good returns, and there may be an opportunity to introduce premium offerings or bundled services to increase revenue further.

**The South region** follows closely behind the East, contributing significant revenue. This aligns with earlier findings showing that the Premium subscription plan is most popular in this region. The South can continue to be a focus for premium service promotions and loyalty programs to sustain and grow its contribution.

**The North and West regions** generate the least revenue, with the North contributing the lowest amount. The North may require additional focus on customer acquisition campaigns or product incentives to drive subscription uptake. Similarly, the West could benefit from repositioning its subscription offerings or exploring cross-sell opportunities to existing customers.

While the East and South regions are driving most of the revenue, the North and West regions show limited performance. A targeted approach could help balance revenue streams.

**FINDINGS FROM REVENUE GENERATED IN EACH REGION EACH YEAR**

![image](https://github.com/user-attachments/assets/751a770d-ade4-4caf-899c-ddbd7fcf591f)

All regions (East, North, South, and West) show consistent revenue contributions across 2022 and 2023. This indicates steady subscription engagement and customer retention. Revenue figures for 2023 remain strong, demonstrating continued growth and retention across all regions. This trend suggests that the current subscription model is effective, but regional-specific marketing strategies can further boost performance. If positive trends continue in 2023, a consideration for scaling marketing investments in high-performing regions (East and South) while restructuring campaigns in underperforming ones (North and West) is highly recommended.

**FINDINGS FROM PERCENTAGE RETENTION AND TERMINATION**

![image](https://github.com/user-attachments/assets/b89323b9-7123-46a0-b0cf-fcdf9492c33e)


HIGHER RETENTION RATE FOR BASIC

Basic plans show a high retention rate based on more FALSE values. Customers likely find the Basic plan affordable and sustainable, leading to fewer cancellations. However, this could also reflect customers sticking to lower-tier services rather than upgrading.

HIGHER TERMINATION RATE FOR PREMIUM

Premium subscriptions have more TRUE (canceled) values, indicating higher termination rates. This suggests that customers may find the premium offerings too costly or not meeting their expectations. Churn management efforts, such as offering discounts or personalized customer engagement, could help retain high-value customers.

BALANCED RATE FOR STANDARD

Standard plans appear to have a moderate balance between TRUE and FALSE, indicating mixed retention trends. Some customers may view the Standard plan as a good compromise between cost and value, while others may either downgrade to Basic or upgrade to Premium. Keeping the Standard plan differentiated and competitive can help stabilize churn.

## SQL

### RETRIEVING DATA FROM SQL USING QUERIES

Data loaded into SQL were retrieved to gain meaningful insight into customer trend and regional performance by writing corresponding queries. The below are all queries used to extract data

'' *SELECT * FROM [CUSTOMER DATA CSV]*

**TOTAL NUMBER OF CUSTOMERS FROM EACH REGION**

NORTH

'' *SELECT COUNT(CUSTOMERNAME) AS TOTAL_NORTHERN_CUSTOMERS 
FROM [dbo].[CUSTOMER DATA CSV] 
WHERE [REGION] = 'NORTH'*

-  TOTAL_NORTHERN_CUSTOMERS  8433

SOUTH

'' *SELECT COUNT(CUSTOMERNAME) AS TOTAL_SOUTHERN_CUSTOMERS 
FROM [dbo].[CUSTOMER DATA CSV] 
WHERE [REGION] = 'SOUTH'*

- TOTAL_SOUTHERN_CUSTOMERS  8446

EAST

'' *SELECT COUNT(CUSTOMERNAME) AS TOTAL_EASTERN_CUSTOMERS 
FROM [dbo].[CUSTOMER DATA CSV] 
WHERE [REGION] = 'EAST'*

- TOTAL_EASTERN_CUSTOMERS  8488

WEST

'' *SELECT COUNT(CUSTOMERNAME) AS TOTAL_WESTERN_CUSTOMERS 
FROM [dbo].[CUSTOMER DATA CSV] 
WHERE [REGION] = 'WEST'*

- TOTAL_WESTERN_CUSTOMERS  8420


**MOST POPULAR SUBSCRIPTION TYPE**

'' *SELECT [SubscriptionType], COUNT(REGION) AS MOST_POPULAR_SUBSCRIPTION_TYPE 
FROM [dbo].[CUSTOMER DATA CSV]
GROUP BY [SubscriptionType]
ORDER BY 2 DESC*

- Basic 	16921

**CUSTOMERS WITH SUBSCRIPTION LESS THAN 6 MONTHS**

'' *SELECT [CUSTOMERNAME], COUNT(CustomerID) AS SUB_LESS_6_MONTHS
FROM [dbo].[CUSTOMER DATA CSV]
WHERE [SUBSCRIPTION_PERIOD] < 183
GROUP BY [CUSTOMERNAME]
ORDER BY 2 DESC*

-  NIL 

**AVERAGE SUBSCRIPTION DURATION FOR ALL CUSTOMERS**

'' *SELECT AVG(SUBSCRIPTION_PERIOD) AS AVG_SUB
FROM [dbo].[CUSTOMER DATA CSV]*

- 365

**CUSTOMERS WITH SUBSCRIPTION LONGER THAN 12 MONTHS**

'' *SELECT [CUSTOMERNAME], COUNT(CustomerID) AS SUB_ABOVE_12_MONTHS
FROM [dbo].[CUSTOMER DATA CSV]
WHERE [SUBSCRIPTION_PERIOD] > 366
GROUP BY [CUSTOMERNAME]
ORDER BY 2 DESC*

- NIL

**TOTAL REVENUE BY SUBSCRIPTION TYPE**

'' *SELECT [SubscriptionType], SUM(Revenue) AS TOTAL_REVENUE_BY_SUBSCRIPTION_TYPE 
FROM [dbo].[CUSTOMER DATA CSV]
GROUP BY [SubscriptionType]
ORDER BY 2 DESC*

- Basic	33776735
- Premium	16899064
- Standard	16864376

**TOP 3 REGION BY SUBSCRIPTION CANCELLATION**

'' *SELECT TOP 3 [Region], COUNT(Canceled) AS TOP_3_CANCELLATION 
FROM [dbo].[CUSTOMER DATA CSV]
WHERE [Canceled] = 'TRUE'
GROUP BY [Region]
ORDER BY 2 DESC*

- North	5067
- South	5064
- West	5044

**TOTAL NUMBER OF ACTIVE SUBSCRIPTION**

'' *SELECT COUNT(canceled) AS TOTAL_ACTIVE_SUB
from [dbo].[CUSTOMER DATA CSV]
WHERE [Canceled] = 'FAlse'*

- 18612

**TOTAL NUMBER OF CANCELED SUBSCRIPTION**

'' *SELECT COUNT(canceled) AS TOTAL_ACTIVE_SUB
from [dbo].[CUSTOMER DATA CSV]
WHERE [Canceled] = 'TRUE'*

-  15175

### SUMMARY OF SQL QUERIES

![image](https://github.com/user-attachments/assets/648639a3-dd67-402d-9dc5-0d047f9421e7)


**FINDINGS FROM THE DATA RETRIEVED FROM SQL QUERIES**


RECOMMENDATIONS
Upsell Campaigns: Focus on converting Basic users in North and East regions to higher-tier plans.
Customer Loyalty Programs: Retain Premium customers in South with incentives.
Reposition Standard Plans: Strengthen the appeal of Standard plans in regions where they are underperforming (North, East, and South).
Market Premium Plans Beyond South: Explore promotional strategies to introduce Premium offerings in other regions.
Focus on Growth in the North and West: These regions need new marketing strategies to boost subscriptions and revenue.
Retain and Expand in the East and South: These regions already perform well, but offering new product bundles or premium services could further increase profitability.
Optimize Regional Campaigns: Tailoring campaigns to reflect each region’s preferences will ensure better engagement and more balanced revenue growth across all regions.
*North:* Introduce lower-cost trials or discounts to attract new customers.
*West:* Promote upgrades to higher-tier plans and explore why customer engagement may be stagnant.
Retained customers (FALSE) provide an opportunity to upsell or cross-sell higher-tier plans.
For customers with canceled subscriptions (TRUE), re-engagement campaigns (e.g., personalized discounts, limited-time offers) could reduce churn and drive renewals.

Key Observations:
Overall Revenue:

2022 Revenue: 40,538,438
2023 Revenue: 27,001,737
Grand Total: 67,540,175
Insight:

2022 contributed 60% of total revenue, while 2023 dropped to 40%. There’s a noticeable decline in revenue between the two years, which could indicate lower customer engagement, reduced subscriptions, or external market challenges.
Analysis of Subscription Categories:
FALSE Group (2022-2023):
Total Revenue: 23,720,255
Basic Plan Revenue: 16,967,285
East Region: 10,242,555
North Region: 6,724,730
Standard Plan (West Region): 6,752,970
Insight:

The East region is a key driver for the Basic plan revenue in 2022, but it did not grow into 2023. Both North and East regions maintain a steady performance, but without any noticeable increase between the years.
West region’s Standard plan revenue (6.75M) remains constant across the years, showing a stable but non-growing base.
TRUE Group (2022-2023):
Total Revenue: 16,818,183
Basic Plan (North Region): 3,365,221
Premium Plan (South Region): 10,126,800
Standard Plan (West Region): 3,326,162
Insight:

Premium Plan in the South region drives the majority of the TRUE category’s revenue, showing a concentration of high-value customers. This segment remains unchanged in 2023 with identical revenue, which may indicate that the customer base is consistent, but growth opportunities may be limited.
Basic plan in the North region remains stable, generating the same revenue across 2022 and 2023, highlighting a lack of churn but also no expansion.
Year-over-Year Trends (2022 vs 2023):
No growth was recorded across all the major segments and regions from 2022 to 2023. The Premium plan in the South region maintained 10.1M revenue in both years.
Standard plan in the West region stayed flat at 6.75M (FALSE) and 3.32M (TRUE) across both years.
The Basic plan in the North showed no revenue growth from 3.36M between 2022 and 2023.
Potential Issues and Opportunities:
Flat Growth Across Years:

Several segments remained unchanged in revenue from 2022 to 2023. This suggests no net new customers or reduced customer acquisition efforts in these regions and plans.
Focus on Premium Customers in South:

The Premium plan in South is a key revenue driver, but it didn’t grow between 2022 and 2023. There’s an opportunity to retain and upsell existing customers while expanding premium offerings.
Basic Plan Opportunities in East and North:

East and North regions generate significant revenue through Basic plans but lack growth. These regions may benefit from targeted marketing to drive subscription upgrades or cross-sell Standard/Premium plans.
West Region Stability:

The West region maintains stable performance across both Standard and Basic plans. This is good, but it indicates a need for innovation or new campaigns to drive growth.
Recommendations:
Targeted Growth Campaigns:

Focus marketing efforts in South and East regions to promote Premium subscriptions and increase revenue beyond current levels.
Churn Prevention & Customer Retention:

Launch customer loyalty programs for Basic and Standard plans to prevent churn and upsell into Premium offerings.
Data-Driven Insights:

Analyze customer behavior in regions with flat growth (West and North) to identify barriers to expansion. Use this insight to design new subscription tiers or incentives.
