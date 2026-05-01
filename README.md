# Telco Customer Churn Analysis

## Project Overview
This project focuses on analyzing customer churn behavior in a telecom company. The goal was to identify key drivers of churn and provide actionable insights that can help improve customer retention.

## Objective
To explore customer data, understand churn patterns, and determine which customer segments are most likely to leave.

## Tools Used
- Excel → Initial data review
- Power BI → Data cleaning, transformation, and dashboard creation

## Dataset
- Source: Udemy Course (Satyajit Pattnaik)
- Total Records: 7,043 customers

## Data Cleaning
- The dataset was mostly clean.
- Missing values in Total Charges were filled using the average value (2833)
- No major inconsistencies or duplicates were found

## Dashboard Structure
The report consists of 3 pages:
### 1. Overview Page
- Key KPIs (Total Customers, Total Charges, Avg Monthly Charges)
- Customer distribution by:
-- Gender
-- Contract type
-- Payment method
-- Internet service
-- Overall churn rate
### 2. Drivers Page
Focused on identifying key churn drivers:
- Contract type vs churn
- Payment method vs churn
- Internet service vs churn
- Tech support vs churn
### 3. Segments Page
- Deeper breakdown of churn across:
- Senior citizens
- Streaming services
- Multiple lines
- Other customer segments

## Key Insights
### 1. Overall Churn
- Churn rate: 27%
#### Indicates moderate but important customer loss

### 2. Contract Type (Strongest Driver)
- Month-to-month customers → ~40% churn
- Long-term contracts → <20% churn
#### Customers with low commitment are more likely to leave

### 3. Internet Service
- Fiber optic users → ~42% churn (highest)
- DSL / No internet → <20%
#### High usage does not guarantee retention

### 4. Payment Method
- Electronic check → ~40% churn
- Other methods → <20%
#### Payment behavior reflects customer engagement

### 5. Tech Support
- Customers without tech support churn significantly more
#### Support plays a key role in retention

### 6. Demographics
- Gender → No impact
- Senior citizens → Higher churn (~41%) but smaller segment
#### Behavior matters more than demographics

## Key Takeaway
Customer churn is primarily driven by:
1. Low commitment (contract type)
2. Service experience (internet & support)
3. Customer behavior (payment method)

## Recommendations
1. Encourage long-term contracts with incentives
2. Investigate fiber optic customer experience
3. Promote automatic payment methods
4. Improve customer support accessibility
5. Focus retention efforts on high-risk segments

## Dashboard
<img width="1064" height="596" alt="Page one 1" src="https://github.com/user-attachments/assets/09937b03-7e5f-4fe5-856b-5412047c50a8" />

<img width="1066" height="597" alt="Page two 2" src="https://github.com/user-attachments/assets/6faa00be-ea22-4918-9223-252a4d5a9030" />

<img width="1066" height="596" alt="Page three 3" src="https://github.com/user-attachments/assets/81332143-10e8-4700-b755-16c81f2474c0" />

### Live Dashboard
[view Telco-Customer Churn report in power BI](https://app.powerbi.com/links/wqry_qDra1?ctid=a36e1a13-c829-4154-8635-f2516711db50&pbi_source=linkShare)
