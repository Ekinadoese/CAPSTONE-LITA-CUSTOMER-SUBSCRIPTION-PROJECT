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

## ANALYSIS AND INSIGHTS

### EXCEL

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

This regional pattern reflects customer segmentation. Marketing strategies can be tailored to target each region based on their preferences. For example, campaigns promoting premium services can focus on the South, while Basic-to-Standard upgrades can target the North and East. North, East, and West regions show no significant engagement with Premium plans. Hence, There’s an opportunity to introduce special offers or trials to encourage higher-tier adoption in these regions. Understanding why Premium plans are underutilized in these areas can also guide future strategies.

**FINDINGS FROM TOTAL REVENUE PER REGION**

![image](https://github.com/user-attachments/assets/472af644-1195-4152-99de-c44a135ca28f)

**TOTAL REVENUE**

- 2022 Revenue: 40,538,438
- 2023 Revenue: 27,001,737
- Grand Total:  67,540,175
  
REGIONAL PERFORMANCE

**The East region** is the top performer, with revenue slightly below 17 million. This indicates a strong customer base with high engagement. Marketing efforts here are yielding good returns, and there may be an opportunity to introduce premium offerings or bundled services to increase revenue further.

**The South region** follows closely behind the East, contributing significant revenue. This aligns with earlier findings showing that the Premium subscription plan is most popular in this region. The South can continue to be a focus for premium service promotions and loyalty programs to sustain and grow its contribution.

**The North and West regions** generate the least revenue, with the North contributing the lowest amount. The North may require additional focus on customer acquisition campaigns or product incentives to drive subscription uptake. Similarly, the West could benefit from repositioning its subscription offerings or exploring cross-sell opportunities to existing customers.

While the East and South regions are driving most of the revenue, the North and West regions show limited performance. A targeted approach could help balance revenue streams.

**FINDINGS FROM REVENUE GENERATED IN EACH REGION PER YEAR**

![image](https://github.com/user-attachments/assets/751a770d-ade4-4caf-899c-ddbd7fcf591f)

2022 contributed 60% of total revenue, while 2023 dropped to 40%. There’s a noticeable decline in revenue between the two years, which could indicate lower customer engagement, reduced subscriptions, or external market challenges.

**RENEWED SUBSCRIPTION INPUT WITHIN THE FOCAL YEAR (2022-2023):**

Total Revenue: 23,720,255

Basic Plan Revenue: 16,967,285

East Region: 10,242,555

North Region: 6,724,730

Standard Plan (West Region): 6,752,970

The East region is a key driver for the Basic plan revenue in 2022, but it did not grow into 2023. Both North and East regions maintain a steady performance, but without any noticeable increase between the years. West region’s Standard plan revenue (6.75M) remains constant across the years, showing a stable but non-growing base.

**CANCELLED SUBSCRIPTION INPUT WITHIN THE FOCAL YEAR (2022-2023):**

Total Revenue: 16,818,183

Basic Plan (North Region): 3,365,221

Premium Plan (South Region): 10,126,800

Standard Plan (West Region): 3,326,162

Premium Plan in the South region drives the majority of the Cancelled subscription revenue. This segment remains unchanged in 2023 with identical revenue, which may indicate that the customer base is consistent, but growth opportunities may be limited.
Basic plan in the North region remains stable, generating the same revenue across 2022 and 2023, highlighting a lack of churn but also no expansion.

**YEAR OVER YEAR TREND (2022 - 2023)**

Several segments remained unchanged in revenue from 2022 to 2023. This suggests no net new customers or reduced customer acquisition efforts in these regions and plans.

The Premium plan in South is a key revenue driver, but it didn’t grow between 2022 and 2023. There’s an opportunity to retain and upsell existing customers while expanding premium offerings.

East and North regions generate significant revenue through Basic plans but lack growth. These regions may benefit from targeted marketing to drive subscription upgrades or cross-sell Standard/Premium plans.

The West region maintains stable performance across both Standard and Basic plans. This is good, but it indicates a need for innovation or new campaigns to drive growth.

All regions (East, North, South, and West) show consistent revenue contributions across 2022 and 2023.

**FINDINGS FROM PERCENTAGE RETENTION AND TERMINATION**

![image](https://github.com/user-attachments/assets/b89323b9-7123-46a0-b0cf-fcdf9492c33e)


**HIGHER RETENTION RATE FOR BASIC**

Basic plans show a high retention rate based on more FALSE values. Customers likely find the Basic plan affordable and sustainable, leading to fewer cancellations. However, this could also reflect customers sticking to lower-tier services rather than upgrading.

**HIGHER TERMINATION RATE FOR PREMIUM**

Premium subscriptions have more TRUE (canceled) values, indicating higher termination rates. This suggests that customers may find the premium offerings too costly or not meeting their expectations. Churn management efforts, such as offering discounts or personalized customer engagement, could help retain high-value customers.

**BALANCED RATE FOR STANDARD**

Standard plans appear to have a moderate balance between TRUE and FALSE, indicating mixed retention trends. Some customers may view the Standard plan as a good compromise between cost and value, while others may either downgrade to Basic or upgrade to Premium. Keeping the Standard plan differentiated and competitive can help stabilize churn.

### SQL

### RETRIEVING DATA FROM SQL USING QUERIES

Data loaded into SQL were retrieved to gain meaningful insight into customer trend and regional performance by writing corresponding queries. The below are all queries used to extract data

`*SELECT * FROM [CUSTOMER DATA CSV]*`

**TOTAL NUMBER OF CUSTOMERS FROM EACH REGION**

NORTH

`*SELECT COUNT(CUSTOMERNAME) AS TOTAL_NORTHERN_CUSTOMERS 
FROM [dbo].[CUSTOMER DATA CSV] 
WHERE [REGION] = 'NORTH'*`

-  TOTAL_NORTHERN_CUSTOMERS  8433

SOUTH

`*SELECT COUNT(CUSTOMERNAME) AS TOTAL_SOUTHERN_CUSTOMERS 
FROM [dbo].[CUSTOMER DATA CSV] 
WHERE [REGION] = 'SOUTH'*`

- TOTAL_SOUTHERN_CUSTOMERS  8446

EAST

`*SELECT COUNT(CUSTOMERNAME) AS TOTAL_EASTERN_CUSTOMERS 
FROM [dbo].[CUSTOMER DATA CSV] 
WHERE [REGION] = 'EAST'*`

- TOTAL_EASTERN_CUSTOMERS  8488

WEST

`*SELECT COUNT(CUSTOMERNAME) AS TOTAL_WESTERN_CUSTOMERS 
FROM [dbo].[CUSTOMER DATA CSV] 
WHERE [REGION] = 'WEST'*`

- TOTAL_WESTERN_CUSTOMERS  8420


**MOST POPULAR SUBSCRIPTION TYPE**

`*SELECT [SubscriptionType], COUNT(REGION) AS MOST_POPULAR_SUBSCRIPTION_TYPE 
FROM [dbo].[CUSTOMER DATA CSV]
GROUP BY [SubscriptionType]
ORDER BY 2 DESC*`

- Basic 	16921

**CUSTOMERS WITH SUBSCRIPTION LESS THAN 6 MONTHS**

`*SELECT [CUSTOMERNAME], COUNT(CustomerID) AS SUB_LESS_6_MONTHS
FROM [dbo].[CUSTOMER DATA CSV]
WHERE [SUBSCRIPTION_PERIOD] < 183
GROUP BY [CUSTOMERNAME]
ORDER BY 2 DESC*`

-  NIL 

**AVERAGE SUBSCRIPTION DURATION FOR ALL CUSTOMERS**

`*SELECT AVG(SUBSCRIPTION_PERIOD) AS AVG_SUB
FROM [dbo].[CUSTOMER DATA CSV]*`

- 365

**CUSTOMERS WITH SUBSCRIPTION LONGER THAN 12 MONTHS**

`*SELECT [CUSTOMERNAME], COUNT(CustomerID) AS SUB_ABOVE_12_MONTHS
FROM [dbo].[CUSTOMER DATA CSV]
WHERE [SUBSCRIPTION_PERIOD] > 366
GROUP BY [CUSTOMERNAME]
ORDER BY 2 DESC*`

- NIL

**TOTAL REVENUE BY SUBSCRIPTION TYPE**

`*SELECT [SubscriptionType], SUM(Revenue) AS TOTAL_REVENUE_BY_SUBSCRIPTION_TYPE 
FROM [dbo].[CUSTOMER DATA CSV]
GROUP BY [SubscriptionType]
ORDER BY 2 DESC*`

- Basic	33776735
- Premium	16899064
- Standard	16864376

**TOP 3 REGION BY SUBSCRIPTION CANCELLATION**

`*SELECT TOP 3 [Region], COUNT(Canceled) AS TOP_3_CANCELLATION 
FROM [dbo].[CUSTOMER DATA CSV]
WHERE [Canceled] = 'TRUE'
GROUP BY [Region]
ORDER BY 2 DESC*`

- North	5067
- South	5064
- West	5044

**TOTAL NUMBER OF ACTIVE SUBSCRIPTION**

`*SELECT COUNT(canceled) AS TOTAL_ACTIVE_SUB
from [dbo].[CUSTOMER DATA CSV]
WHERE [Canceled] = 'FAlse'*`

- 18612

**TOTAL NUMBER OF CANCELED SUBSCRIPTION**

`*SELECT COUNT(canceled) AS TOTAL_ACTIVE_SUB
from [dbo].[CUSTOMER DATA CSV]
WHERE [Canceled] = 'TRUE'*`

-  15175

### SUMMARY OF SQL QUERIES

![image](https://github.com/user-attachments/assets/648639a3-dd67-402d-9dc5-0d047f9421e7)


**FINDINGS FROM THE DATA RETRIEVED FROM SQL QUERIES**

### CUSTOMER DISTRIBUTION BY REGION 

East has the highest number of customers with 8,488, followed closely by South (8,446). North (8,433) and West (8,420) have slightly fewer customers, suggesting a more even customer distribution across all regions. Although customer numbers are distributed relatively evenly, the East region seems to be a key area of focus for customer engagement.

### MOST POPULAR SUBSCRIPTION TYPE

Basic subscription is the most popular type with 16,921 customers. This suggests that customers are primarily opting for affordable entry-level subscriptions, which may indicate price sensitivity. It could also signal that customers are testing the service before upgrading.

### SUBSCRIPTION DURATION

No customers have a subscription period of less than 6 months or more than 12 months. The absence of short-term and long-term subscriptions implies that customers tend to stay for an average duration of 1 year (365 days). This might suggest that subscription plans are aligned with annual billing cycles, and customers are likely canceling or renewing annually.

### REVENUE CONTRIBUTION BY SUBSCRIPTION TYPE

Basic subscription contributes 33,776,735 of revenue, followed by Premium (16,899,064) and Standard (16,864,376). Despite being the most affordable, Basic plans generate the highest revenue. This indicates that high customer volume is compensating for the lower price point. Premium and Standard plans have nearly equal revenue, suggesting a well-balanced demand for higher-tier subscriptions.

### TOP 3 REGIONS BY SUBSCRIPTION CANCELLATION

North leads with 5,067 cancellations, closely followed by South (5,064) and West (5,044). Cancellations are concentrated in these three regions, potentially signaling satisfaction issues or regional challenges that may need attention. Customer retention strategies should focus more on these areas to reduce churn.

### RENEWED SUBSCRIPTION AGAINST CANCELLED SUBSCRIPTION

18,612 active subscriptions and 15,175 canceled subscriptions were recorded. This reflects a 44.9% churn rate (15,175 / (18,612 + 15,175)), which indicates a relatively high turnover. Customer retention efforts could focus on incentivizing renewals, especially in regions with higher cancellation rates.

### KEY NOTES

**Balanced Customer Distribution:** All four regions show relatively even customer distribution, with a slight edge for the East.

**Price Sensitivity:** The dominance of the Basic plan suggests that customers prioritize affordability.

**High Churn Rate:** Nearly 45% of subscriptions end in cancellations, which highlights the need for stronger customer retention strategies.

**Stable Subscription Durations:** The absence of subscriptions shorter than 6 months or longer than 12 months hints at an annual subscription trend.


## CONCLUSION

An in-depth analysis of the subscription data has surfaced key insights into customer behavior, regional dynamics, and revenue patterns, enabling us to derive actionable business strategies.

- **Regional Customer Distribution:**

Customers are evenly distributed across all regions, with the East showing a marginally higher number of subscribers. This uniform distribution indicates broad market penetration, though East could serve as a focal point for regional growth initiatives.

- **Subscription Type Preference and Revenue Contribution:**

The Basic subscription is overwhelmingly popular, not only attracting the most customers but also generating the highest revenue. This suggests a price-sensitive customer base and highlights the effectiveness of the Basic plan in driving volume. However, revenue from Premium and Standard plans is nearly identical, indicating stable demand across higher tiers, which represents a strong upsell opportunity.

- **Churn and Retention Challenges:**

With a churn rate of around 45%, a significant portion of customers are canceling their subscriptions, especially in the North, South, and West regions. This high cancellation rate underscores the need for targeted retention efforts. Addressing this churn, particularly in these regions, could stabilize and potentially grow the customer base, reducing acquisition costs over time.
Customer Subscription Duration:

Customers typically maintain subscriptions for around one year, with no substantial variation toward shorter or longer terms. This points to an annual cycle preference, which aligns with a common billing period, making the case for retention programs that encourage renewals near the one-year mark.

## RECOMMENDATION

**Retention Programs:** There should be a focus on reducing churn in North, South, and West regions through targeted campaigns.

**Upsell Opportunities:** Basic plan customers should be encouraged to upgrade to higher tiers, as Premium and Standard plans generate comparable revenue.

**Customer Feedback:** There is a need to Gather insights from canceled customers through survey to identify pain points and improve service offerings. Analyze customer behavior in regions with flat growth (West and North) to identify barriers to expansion. Use this insight to design new subscription tiers or incentives.

**Regional Promotions:** Since East has the most customers, it is important to leverage this region for pilot campaigns or referral incentives

**Customer Loyalty Programs:** Customers retention in South can be achieved with incentives.

**Reposition Standard Plans:** It is important to strengthen the appeal of Standard plans in regions where they are underperforming (North, East, and South).

**Market Premium Plans Beyond South:** Promotional strategies can be explored to introduce Premium offerings in other regions.

**Focus on Growth in the North and West:** These regions need new marketing strategies to boost subscriptions and revenue.
- *North:* Introduce lower-cost trials or discounts to attract new customers.
- *West:* Promote upgrades to higher-tier plans and explore why customer engagement may be stagnant.

**Retain and Expand in the East and South:** These regions already perform well, but offering new product bundles or premium services could further increase profitability. Focus marketing efforts in South and East regions to promote Premium subscriptions and increase revenue beyond current levels.

**Optimize Regional Campaigns:** Tailoring campaigns to reflect each region’s preferences will ensure better engagement and more balanced revenue growth across all regions.

**Retained customers:** This customer segment provide an opportunity to upsell or cross-sell higher-tier plans. Launch customer loyalty programs for Basic and Standard plans to prevent churn and upsell into Premium offerings.

**Customers with canceled subscriptions:** This customer segment require re-engagement campaigns (e.g., personalized discounts, limited-time offers). This could reduce churn and drive renewals.

## VISUALIZATION

### FIGURES AT A GLANCE

### SUMMARY

![BI FIG SUMMARY](https://github.com/user-attachments/assets/0ff83ba8-8100-4e3a-a4b4-d7822e3f18ba)

### SUMMARY BY REGION

- **NORTH**

  ![NORTH BI FIG](https://github.com/user-attachments/assets/4ae2d39a-b9ef-4bdd-bd2f-5d92bff68b2b)

- **SOUTH**
  
  ![SOUTH BI FIG](https://github.com/user-attachments/assets/192ca856-b7af-4a39-8b41-47fad1616066)

- **EAST**

  ![EAST BI FIG](https://github.com/user-attachments/assets/0ad3093c-2592-44cf-9ce8-c1c5f04bfbcc)

- **WEST**

![WEST BI FIG](https://github.com/user-attachments/assets/e540a72d-582a-45a5-b6a1-ba79afa67563)

### SUMMARY BY PRODUCTS

- **BASIC**

  ![BASIC BI SUMMARY](https://github.com/user-attachments/assets/6ab69909-ad49-45f6-a10e-ee2689fc8254)

- **STANDARD**
  
  ![STANDARD BI SUMMARY](https://github.com/user-attachments/assets/a2b816fd-b8c7-4cb7-a04c-202096ba64f5)

- **PREMIUM**

![PREMIUM BI SUMMARY](https://github.com/user-attachments/assets/611f9079-ff0d-47f8-b20a-441140e87f57)

### STATISTICS

![BI STATS VISUAL](https://github.com/user-attachments/assets/813b17d4-d480-435d-925c-07748186b02b)

### 2022 STATISTICS

![BI STATS VISUAL](https://github.com/user-attachments/assets/ee704cc4-eb26-44fd-a460-e368dfe3b9b2)

### 2023 STATISTICS

![BI 2023-STAT](https://github.com/user-attachments/assets/7b5eebd6-5472-4fbd-bfb3-42e3e845f1d4)

### YEAR OVER YEAR TRENDS

![BI MONTH SUMMARY](https://github.com/user-attachments/assets/c43d8a78-f4e2-4cdd-a89b-89486074f636)

### MONTHLY SUBSCRIPTION PER REGION

- **NORTH**

  ![BI NORTH MONTH SUMMARY](https://github.com/user-attachments/assets/faf4a3df-3fff-442a-99f5-971233dff8de)

- **SOUTH**

  ![BI SOUTH MONTH SUMMARY](https://github.com/user-attachments/assets/3616e359-11d8-4143-93bf-f3ea4f8e9f68)

- **EAST**

  ![BI EAST MONTH SUMMARY](https://github.com/user-attachments/assets/cc0bd476-81fa-4441-9289-114f763bffa9)

- **WEST**

![BI WEST MONTH SUMMARY](https://github.com/user-attachments/assets/33a7f467-0e12-4966-96f0-ecce438dbe9b)

### MONTHLY SUBSCRIPTION PER PRODUCT

- **BASIC**

![BI BASIC MONTH SUMMARY](https://github.com/user-attachments/assets/df6c8b68-0a3a-449d-994b-2ee328e7ce6f)

- **STANDARD**

![BI STANDARD MONTH SUMMARY](https://github.com/user-attachments/assets/8d2cf1a4-6d5c-4c57-a847-6dc68afdad53)

- **PREMIUM**

![BI PREMIUM MONTH SUMMARY](https://github.com/user-attachments/assets/bb3a3ad9-4d20-41c1-816e-c8605eb1c7a3)


