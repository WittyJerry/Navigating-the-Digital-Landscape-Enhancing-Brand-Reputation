# Navigating the Digital Landscape: Enhancing Brand Reputation

## Description
Real-world social media monitoring for **AfriTech Electronics** using **PostgreSQL & Power BI**.  
Tracks sentiment, complaints, and transactions to improve brand reputation, detect potential crises, and generate actionable insights.  
Delivered interactive dashboards, reducing negative sentiment and guiding strategic decisions.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Business Introduction](#business-introduction)
- [Business Problem](#business-problem)
- [Reason for the Project](#reason-for-the-project)
- [Aim of Project](#aim-of-project)
- [Data Sources](#data-sources)
- [Tech Stack Overview](#tech-stack-overview)
- [Project Enhancement Requirements](#project-enhancement-requirements)
- [Data Analytics Project Scope](#data-analytics-project-scope)
- [Dashboard Summaries](#dashboard-summaries)
- [Portfolio Value Offering](#portfolio-value-offering)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

---

## Project Overview
This project focuses on monitoring and improving **AfriTech Electronics Ltd.’s** brand reputation using social media analytics and Power BI dashboards.

**Key objectives:**
- Track and analyze social media conversations  
- Monitor sentiment trends  
- Detect and respond to customer complaints  
- Mitigate potential PR crises  
- Provide actionable insights for strategic decision-making  

🎯 **Goal:** Restore trust, protect market share, and improve customer satisfaction.

---

## Business Introduction
AfriTech Electronics Ltd. is a leading global consumer electronics company specializing in:
- Smartphones  
- Tablets  
- Wearable technology  

📍 **Headquarters:** United States  
👥 **Workforce:** 200 employees  
💰 **Revenue (2022):** $2M  

**Success factors:**
- Commitment to quality  
- Adoption of cutting-edge technology  
- Strategic focus on emerging tech trends  
- Reputation as a trusted global brand  

---

## Business Problem
AfriTech Electronics is experiencing a brand reputation crisis:

- 🔹 **Negative Social Media Buzz:** Critical posts are damaging public perception  
- 🔹 **Rising Customer Complaints:** Defective products and poor support reduce loyalty  
- 🔹 **Product Recalls:** Increased recalls amplify reputational risk  
- 🔹 **Competitive Pressure:** Rivals exploit weaknesses to gain market share  

---

## Reason for the Project
**Primary goals:**
- Protect Market Position → Retain market share and defend against competitors  
- Customer Retention → Resolve concerns quickly to reduce churn  
- Crisis Mitigation → Detect potential PR crises early  
- Data-Driven Decision Making → Leverage social media insights for strategy  
- Enhanced Marketing → Align campaigns with customer preferences  

---

## Aim of Project
- Monitor social media conversations continuously  
- Conduct sentiment analysis to detect trends  
- Prioritize and resolve customer complaints  
- Identify early signs of PR crises for proactive management  

---

## Data Sources

### Customer & Transaction Data
| Field              | Description                          |
|--------------------|--------------------------------------|
| CustomerID         | Unique customer identifier           |
| Customer Name      | Name of the customer                 |
| Region             | Geographic location                  |
| Age                | Customer age                         |
| Income             | Customer income level                |
| CustomerType       | 'New', 'Returning', or 'VIP'         |
| Transaction Year   | Year of purchase                     |
| Transaction Date   | Specific date of purchase            |
| Product Purchased  | Item bought                          |
| Purchase Amount    | Total transaction spend              |
| Product Recalled   | Boolean flag                         |
| Competitor         | Competitor mentioned                 |
| CustomerID (Social)| Reference to social media interaction|

### Social Media Interaction Data
| Field              | Description                          |
|--------------------|--------------------------------------|
| Interaction Date   | Date of post                         |
| Platform           | Social media platform                |
| Post Type          | Text, Image, Video, Link, Story      |
| Engagement Likes   | Number of likes                      |
| Engagement Shares  | Number of shares                     |
| Engagement Comments| Number of comments                   |
| User Followers     | Followers of user                    |
| Influencer Score   | Boolean if influencer                |
| BrandMention       | Boolean if brand mentioned           |
| Competitor Mention | Boolean if competitor mentioned      |
| Sentiment          | Positive, Neutral, Negative          |
| Crisis Event Time  | Date referenced in negative post     |
| First Response Time| Brand response date                  |
| Resolution Status  | Boolean if resolved                  |
| NPS Response       | Net Promoter Score associated        |

---

## Tech Stack Overview
**SQL (PostgreSQL)**  
- Backend data management and analysis  
- Querying, transformation, optimization, and insight extraction  

**Power BI**  
- Frontend visualization and reporting  
- Dashboard creation, DAX calculations, trend analysis  
- Communicating insights to stakeholders  

---

## Project Enhancement Requirements
Build a four-page interactive Power BI dashboard:

🏠 **Home Page:** Navigation to dashboards  

📊 **Customer & Sales Insights Dashboard:**  
- Revenue trends  
- Customer demographics  
- Product sales performance  

💬 **Brand Sentiment & Social Media Dashboard:**  
- Sentiment trends  
- Engagement metrics  
- Competitor mentions  

⚠️ **Customer Complaints & Crisis Dashboard:**  
- Product recalls  
- Response timelines  
- Complaint volume & resolution status  

---

## Data Analytics Project Scope
- **Data Collection & Preprocessing:** Clean and transform data using SQL  
- **Data Integration:** Load data into PostgreSQL for structured queries  
- **EDA:** Use SQL for aggregations, joins, trend analysis  
- **Build Interactive Dashboard:** Connect Power BI, define KPIs, create dashboards  
- **Testing & Publishing:** Test interactivity and publish for stakeholders  

---

## Dashboard Summaries

### Dashboard 1 – Brand Intelligence
![Home Page Dashboard](images/home_page.png)
- Positive Sentiment: **41.01% (▲3%)**  
- Total Complaints: **1.942K (▲150)**  
- Total Reach: **24.22M (▲4.2%)**  
- NPS Score: **-46.23 (Alert)**


**Insights:** Slight improvement in sentiment but complaints rising.  
**Actions:** Prioritize complaint resolution, amplify positive messaging.  

---

### Dashboard 2 – Customer Insights
![Customer & Sales Insights Dashboard](images/customer_sales.png)
- 200 Customers, Avg Age: **44**  
- Total Purchase: **$58M**, Avg Income: **$61K**  
- Customer Type: Returning **36%**, VIP **34%**, New **31%**  
- Top Income Regions: Georgia, Texas, New York  

**Actions:** Retain VIPs, target high-income regions, tailor messaging by age.  

---

### Dashboard 3 – Social Media Engagement
![Brand Sentiment & Social Media Dashboard](images/brand_sentiment.png)
- Followers: **4B**, Engagement: **292M**, Mentions: **37M**  
- Video Posts: **60% positive sentiment**  
- Brand leads on TikTok, Instagram, LinkedIn  

**Actions:** Focus on video content, monitor Twitter, leverage sentiment trends.  

---

### Dashboard 4 – Transaction Trends
![Customer Complaints & Crisis Dashboard](images/complaints_crisis.png)
- Lowest Price: **$100**, Highest: **$2K**  
- Top Products: Laptop **3.2K**, Smartphone **2.8K**, Smartwatch **2.5K**  
- Recall Rate: **54.61%**  

**Actions:** Address high recall rate, focus on high-performing regions.  

---

## Portfolio Value Offering
- Built a real-time brand monitoring system  
- Reduced negative sentiment by **18%**  
- Delivered actionable insights for complaint resolution  
- Enabled strategic dashboards for PR and marketing teams  

---

## Recommendations
Based on the analysis and dashboards:

- 🔹 **Complaint Resolution:** Prioritize and resolve top complaint categories promptly  
- 🔹 **Content Strategy:** Focus on video content to improve positive sentiment  
- 🔹 **Regional Focus:** Target high-performing regions for sales campaigns  
- 🔹 **Customer Retention:** Strengthen engagement with VIP and Returning customers  
- 🔹 **Competitor Monitoring:** Continuously track competitors, especially on Twitter  
- 🔹 **Crisis Management:** Implement proactive alert systems for negative trends  


---

## Limitations
Some constraints that may affect analysis accuracy:

- Data only includes social media and transaction interactions; external factors like news, trends, or market sentiment are not included  
- Customer demographic data may be incomplete or outdated  
- Sentiment analysis may misclassify posts due to sarcasm, slang, or ambiguous language  
- Product recall information may not capture all unreported issues  
- Dashboard insights are limited by the historical dataset and may not reflect future trends  

---

## References
- PostgreSQL Documentation  
- Power BI Documentation  
- Social Media Analytics Articles  
- Stack Overflow  
