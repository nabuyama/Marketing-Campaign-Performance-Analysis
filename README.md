# Marketing-Campaign-Performance-Analysis
Segmentation and performance analysis of a 9,134-customer insurance marketing campaign dataset, identifying high-response segments, channel effectiveness, and strategic growth opportunities using Power BI and DAX.

**Project overview:**
This project analyzes a synthetic marketing campaign dataset of 9,134 insurance customers across five Western U.S. states (California, Oregon, Arizona, Nevada, and Washington).
The objective was to evaluate campaign performance, identify high-response customer segments, assess channel effectiveness, and provide strategic recommendations to optimize future marketing efforts.

**Tool Used**: Power BI

**Dataset:** Provided as part of a structured analytics mentorship program for educational purposes.

## Analytical questions:
The analysis addressed four themes:

**a)	Campaign Performance**
  - What was the overall response rate?
  - Which states and channels performed best?
  - How did response vary across demographic and product categories?

**b)	Customer Value**
- Did high-value customers (high CLV, multiple policies, high income) respond positively?

**c)	Retention & Risk**
- How did tenure influence response?
- What was the response behavior of customers with recent claims?
- How did customers with open complaints respond?

**d)	Product & Offer Fit**
- Which renewal offers drove higher engagement?
- Which vehicle and policy types showed stronger response patterns?

## Dataset overview
The dataset contains 9,134 customer records with variables including:

•	Customer Lifetime Value (CLV)
•	Income
•	State
•	Employment Status
•	Gender
•	Education
•	Location Code (Urban/Suburban/Rural)
•	Monthly Premium
•	Months Since Policy Inception (Tenure)
•	Months Since Last Claim
•	Number of Open Complaints
•	Number of Policies
•	Policy Type & Policy
•	Renew Offer Type
•	Vehicle Class & Size
•	Response (Target Variable: Yes/No)

## Data Preparation
The dataset was clean with no missing values or duplicates. Created new columns to support segmentation:
- Income Groups
- Tenure Groups
- Complaint Categories
- Claim-recency Categories
- Custom sort columns for meaningful visualization

Developed reusable DAX measures for KPI tracking and segment comparison.

## Key Insights
**1.	The Retired Segment Outperforms:**

Retired customers recorded a 72.34% response rate, significantly higher than any other demographic group.

**2.	Agents Drive Conversions:**

Human-led sales through Agents achieved a 19.15% conversion rate, significantly higher than web or call center channels.

**3.	Premium Vehicle Owners Engage More:**

Owners of Sports Cars (21.6%) and Luxury SUVs (19.2%) are the most likely to accept new offers.

**4.	The Complaint Paradox**:

Customers with three or more open complaints had a higher response rate (16.90%) than those with no complaints (14.64%), suggesting strong brand stickiness despite dissatisfaction.

**5.	Policy Value Gap:**

Single-policy holders responded more (15.87%) but have a 63% lower CLV than multiple-policy holders.

## Recommendations
1.	Prioritize agent-led engagement for high-value and complex product segments.
2.	Reallocate budget toward California, the strongest-performing region.
3.	Develop targeted campaigns for the Retired segment.
4.	Launch cross-sell incentives for single-policy holders.
5.	Implement structured service-recovery outreach for customers with complaints to prevent churn and leverage their engagement.

## Dashboard Preview
### Performance & Demographics
![Performance & Demographics](images/Performance-demographics.jpg)

### Performance and Product Characteristics
![Performance & Product Characteristics](images/Performance-productcharacteristics.jpg)

### Customer Value Analysis
![Customer Value Analysis](images/Customer-Value-Analysis.jpg)

### Churn Risk
![Churn Risk](images/Churn-risk.jpg)

### Claims Risk
![Claims Risk](images/Claims-risk.jpg)
