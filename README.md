**User Banking Portfolio Analytics**

Financial Data Analytics Project

**📊Project Overview**
This project presents a multi-table banking portfolio analytics framework designed to evaluate customer behavior, transaction performance, credit, and operational risk in a banking ecosystem.
The objective was to transform raw customer, account, and transaction data into business intelligence insights using Power BI’s relational modeling and DAX capabilities.
AI-assisted workflows were used to support feature engineering, analytical refinement, and insight validation while maintaining financial and business logic integrity.

**🎯Objectives**
- Analyze overall portfolio performance.
- Evaluate customer spending behaviour, transaction trends, and error patterns.
- Assess operational transaction failure patterns.
- Deliver executive-level dashboard insights.

**📂Data Structure**

1️⃣ Users Table
- Client ID
- Age
- Income
- Credit Score
- Location
  
2️⃣ Cards Table
- Account ID
- Card Type
- Credit Limit
- Current Balance
- Account Status
  
3️⃣ Transactions Table
- Transaction ID
- Transaction Amount
- Merchant Category
- Errors
A relational data model was built inside Power BI using appropriate one-to-many relationships to simulate a real banking portfolio structure.

**🧠 Analytical Framework**

📌 Portfolio KPIs
- Active Customers
- Total/Average Transactions
- Average Credit Score
- Error Rate
  
📌 Operational Metrics
- Total Monthly Transactions
- Risk Distribution
- Card Contribution
- Debt-to-Income (DTI) Distribution
- Credit Score vs Income
- Online vs Swipe Transactions
  
📌 Behavioral Insights
- Spending by Income Bracket
- Spending by Gender
- Merchant Category Spending
- Age Group Spending Behavior
- Geographic Spending
- Spending based on CreditWorthiness

**🛠️ Tools & Technologies**
- Power BI (Relational Modeling, DAX Measures, KPI Engineering)
- Excel (Data Preparation & Cleaning)
- Microsoft Copilot AI-assisted analytical workflow for feature structuring and refinement

**📊 Dashboard Preview**
- Summary Overview
<img width="1281" height="717" alt="Executive Summary" src="https://github.com/user-attachments/assets/7cba7bdb-e7a7-4cef-911c-1404c1a0e30c" />
- Customer Analysis
<img width="1277" height="715" alt="Customer and Credit Analysis" src="https://github.com/user-attachments/assets/598ee6ee-cf8b-4875-a604-af4794cbabe0" />
- Transactions Behaviour
<img width="1280" height="720" alt="Transaction Behaviour" src="https://github.com/user-attachments/assets/37efe25e-669c-477f-9a40-c0911ca59882" />
- Risk Analysis
<img width="1282" height="717" alt="Risk Signals" src="https://github.com/user-attachments/assets/cff8ffac-17c4-4f3e-b9d5-aa4aa8f4e59f" />

**🔍 Key Insights/Findings**
- Out of 2000 clients, 1,131 (57%) are active, indicating moderate engagement levels and potential room for customer reactivation strategies.
- Clients spend an average of $44 per transaction, suggesting predominantly low-to-mid value retail transaction behavior.
- Middle-income clients recorded the highest transaction volumes, while high-income clients showed comparatively lower activity, potentially reflecting different banking channel preferences or asset allocation strategies.
- California recorded the highest number of transactions, highlighting regional transaction concentration and potential market dominance in that state.
- Clients aged 36-50 generated the highest transaction activity, with male clients accounting for 51% of transactions in this group suggests peak earning and/or spending lifecycle behaviour.
- 93% of clients have credit score above 600, indicating a low-to-moderate risk portfolio.
- 99% of clients have less than 4% debt-to-income ratio (DTI), showing a strong debt servicing capacity across this portfolio.
- Insufficient balance was the most common client driven transaction failure error, signaling liquidity management issues among some clients.
- Merchant category code 4829 (wire transfers and money orders) recorded the highest transaction volume, suggesting significant use of transfer services in the dataset.

**🚀 Project Value**
- Relational Data Modeling
- Business KPI Design
- Financial Portfolio Reasoning
- Risk Analysis
- Data Storytelling

📌Overall Dataset Assessment
This dataset reflects a financially stable customer base with strong credit quality and low leverage exposure. Transaction activity is concentrated among middle-income, mid-life demographic segments, with transfer-based merchant activity dominating usage patterns. Operational inefficiencies are primarily customer-liquidity driven rather than system-driven.
