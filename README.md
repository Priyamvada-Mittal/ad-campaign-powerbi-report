# Ad Campaign Performance Dashboard – Power BI
**Overview**
This Power BI project presents a comprehensive analysis of a digital advertising campaign across industries, regions, and platforms. It enables stakeholders to understand campaign effectiveness, optimize strategies, and make data-driven decisions. The objective is to visualize and analyze multi-channel ad campaign performance by combining business KPIs like ROI, CTR, margin, and customer value across industries and regions. The dashboard aims to support marketing teams and senior management in identifying underperforming areas and high-return segments.

**📊Dataset Information**
- Campaign_Data: Includes performance metrics like impressions, clicks, revenue, CTR, CPM, platform type, and campaign status.
- Client_Data: Contains client-level information such as CLV (Customer Lifetime Value), churn probability, region, and service model.
- Industry_ICP_Data: Maps industries to ICP (Ideal Customer Profile) types with average deal size and CTR benchmarks.
- Region_Data: Provides cost per click by region.

**📊Key Metrics** 
- Campaign Overview: ROI, net revenue, cost breakdown, CTR, CPM, and margin.
- Industry Insights: Performance analysis by campaign status, platform, service model and region.
- Regional Breakdown: Average CPC, viewability, and performance by region.
- Client Segmentation: Churn risk analysis, and CLV distribution.
- Filters: Dynamic slicers for industry, campaign status, region, platform, and bid strategy.

**🌟Key Insights and Remedy for them**
- **Insight 1:** High-value clients at high churn risk i.e. Clients in North America and Europe bring the most revenue but also have the highest risk of leaving. Some with over $250K in lifetime value are already flagged as likely to churn.
  - **Remedy 1:** Launch a proactive retention plan. Prioritize these clients for reviews, incentives, and support. Even reducing churn slightly here will protect major revenue.
- **Insight 2:** Travel campaigns have exceptional engagement and efficiency but receive limited budget. Travel has the highest CTR (1.33%) and lowest CPC ($0.45) indicating it attracts clicks cheaply and frequently. Despite this, it ranks last in revenue volume among top industries. Suggests this industry is underutilized despite having the best cost-efficiency dynamics.
  - **Remedy 2:** Allocate additional spend to Travel campaigns, especially those with >1.2% CTR and ROI >1.5. Use Travel as a testbed for creative and audience targeting innovations that could later scale to other industries.
- **Insight 3:** 24 campaigns were cancelled. Yet they achieved an average ROI of 1.97. Their average CTR (1.15%) and margin (47.5%) are quite strong — these are not failure cases. In fact, cancelled campaigns still generated over $40,000 in revenue, about 27% of total campaign revenue. This strongly suggests that many cancellations were not performance-driven.
  - **Remedy 3:** Implement a post-cancellation review process to log the reason (e.g., budget freeze, client churn, or strategy shift).Identify high-ROI cancelled campaigns and re-evaluate restarting or cloning them — particularly those with: ROI > 1.5 ,Margin > 40% and CTR > 1%


**🛠️Usage**
- Use this dashboard to:
  - Identify departments or roles with high attrition rates.
  - Investigate factors contributing to employee dissatisfaction.
  - Plan targeted retention and employee development strategies.
 
**📌Some Interesting Measures Build**
- **Cost Per Click:** CPC measures the cost efficiency of driving user actions (clicks). A high CPC indicates poor targeting, irrelevant creatives meaning we are paying more for each user action than necessary. Tracking CPC enables early identification of campaigns that are costly relative to the engagement they generate, allowing budget optimization and targeting refinements.
- **ROI(revenue/cost):** This ROI-style profit ratio allows stakeholders to instantly evaluate the financial efficiency of campaign spend. It simplifies decision-making by summarizing return performance in a single value, helping to quickly identify campaigns that are not delivering value.
- **Top Client and Number of Campaigns corresponding:** Tracking how many campaigns are tied to each client gives a sense of account importance and risk. If one client runs many campaigns, they’re likely a top priority — but if those campaigns underperform, it could also be a red flag for review or support.

**⚙️Technical Details:**
- Built with Power BI, offering intuitive, interactive visuals and detailed drill-down capabilities.
- DAX for calculated measures (e.g., ROI, margin %, conversion rate)
- Interactive visuals including bar charts, pie charts, scatter plots, parameters and detailed drill-through pages.

**📸 Dashboard Preview**

![image](https://github.com/user-attachments/assets/fd48a890-64ca-4598-9a40-19691fdfeba0)
![image](https://github.com/user-attachments/assets/6516147a-d611-4ac1-b399-e06fecda0b5d)

**💼 About Me**
I’m a Data Analyst with 5 years of experience specializing in business intelligence and Power BI development. This project demonstrates my ability to build insightful, dynamic dashboards using real-world marketing data.



