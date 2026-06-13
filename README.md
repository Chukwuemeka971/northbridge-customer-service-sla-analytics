## NorthBridge Customer Service Ticket & SLA Optimisation System

## Project Overview

The NorthBridge Healthcare IT Support Analytics Dashboard is an enterprise Business Intelligence solution designed to provide visibility into customer support operations, SLA performance, workforce utilisation, escalation risk, and future demand planning.

The solution transforms operational support data into actionable insights that help management improve service delivery, optimise resource allocation, reduce operational risk, and support strategic decision-making.

Built using Power BI and Snowflake, the project demonstrates how analytics can be used to improve customer support performance through KPI monitoring, operational reporting, workforce analysis, and forecasting.

---

## Business Problem

NorthBridge Healthcare Services manages customer support requests across multiple regions, contract tiers, service categories, and support teams.

Leadership required a reporting solution capable of answering critical operational questions:

- Which services generate the highest support demand?
- What factors are driving SLA breaches and escalations?
- Are support resources being utilised effectively?
- Which hubs and teams carry the highest workload?
- How can future support demand be forecast and planned?

Without a centralised analytics solution, identifying performance risks and improvement opportunities was challenging.

---

## Project Delivery Model

This project was delivered through a collaboration between Data Engineering Consultants, Data Analytics Consultants, and NorthBridge operational stakeholders.

### Data Engineering Team

The Data Engineering team owned all upstream data activities, including:

- Data ingestion
- Pipeline development
- Data quality validation
- Snowflake data warehouse management
- Creation of analyst-ready reporting tables

The final output was a curated Snowflake reporting schema designed for analytics consumption.

### Data Analytics Team

The Data Analytics team owned all downstream analytical activities, including:

- Power BI semantic modelling
- KPI framework development
- DAX measure creation
- Dashboard development
- SLA analytics
- Workforce analytics
- Forecasting and trend analysis
- Executive reporting

### Operational Stakeholders

Operational leaders, team leads, and assistant team leads provided business requirements, KPI definitions, operational context, and validation of analytical outputs.

---

## My Role – Data Analyst

As the Data Analyst on the project, I was responsible for transforming curated operational data into actionable business intelligence.

### Key Responsibilities

#### Data Modelling

- Built the Power BI semantic model using a star schema design.
- Established relationships between fact and dimension tables.
- Optimised the model for SLA, workload, and forecasting analysis.

#### KPI Development

Developed and validated core business metrics including:

- Total Tickets
- Active Backlog
- SLA Compliance %
- Resolution Rate %
- Escalation Rate %
- Average First Response Time
- Average Resolution Time
- Capacity Utilisation %
- Ticket Growth YoY

#### Dashboard Development

Designed and developed five analytical dashboards:

1. Executive Overview
2. Operational Drilling
3. SLA Risk Monitoring
4. Workload & Capacity
5. Forecasting & Planning

#### Business Analysis

- Identified operational demand drivers.
- Analysed SLA breach patterns.
- Evaluated escalation risks.
- Assessed workforce utilisation.
- Produced business recommendations.

#### Forecasting

Developed forecasting models to project:

- Ticket demand
- SLA breach volume
- Backlog trends

#### Executive Storytelling

Translated analytical findings into actionable insights and recommendations for operational stakeholders.

---

## Tools & Technologies

- Power BI
- DAX
- Power Query
- Snowflake
- Excel
- Data Modelling
- Forecasting & Trend Analysis

---

# Data Source

The dataset used for this project was sourced from curated reporting tables within a Snowflake data warehouse.

As this project was delivered as part of a collaborative engagement, the underlying source data and Snowflake objects are proprietary and cannot be shared publicly.

The Power BI solution was developed using analyst-ready reporting tables provided by the Data Engineering team.

---

## Data Model

The reporting solution uses a star schema architecture to support scalable and efficient analytics.

### Fact Table

- Tickets

### Dimension Tables

- Date
- Agents
- Clients
- Priority Levels
- Ticket Categories
- Ticket Audit Log
- Escalation Log
- SLA Definition

>![](./Project%20Images/data%20model.png)

---

# 📊 Dashboard Architecture

The solution consists of five integrated analytical dashboards.

---

## 1️⃣ Executive Overview

### Purpose

Provide leadership with a high-level view of service performance.

### KPIs

- Total Tickets
- Active Backlog
- SLA Compliance %
- Resolution Rate %
- Escalation Rate %
- Average First Response Time
- Average Resolution Time

### Business Question

How effectively is the customer support operation performing?

> ![](./Project%20Images/Executive%20Overview.png)

---

## 2️⃣ Operational Drilling

### Purpose

Analyse customer demand patterns and operational workload.

### Analysis Areas

- Ticket Volume by Category
- Ticket Volume by Region
- Ticket Volume by Client Type
- Ticket Volume by Status
- Ticket Volume by Channel

### Business Question

Where is demand originating and which services generate the highest workload?

> ![](./Project%20Images/Operational%20Drilling.png)

---

## 3️⃣ SLA Risk Monitoring

### Purpose

Monitor service risk, SLA failures, and escalation drivers.

### Analysis Areas

- SLA Compliance
- SLA Breaches
- Escalation Rate
- SLA Breaches by Category
- SLA Breaches by Contract Tier
- Escalation Analysis
- SLA Risk Heatmap

### Business Question

Which services, customers, and processes create the highest SLA risk?

> ![](./Project%20Images/SLA%20Risk%20Monitoring.png)

---

## 4️⃣ Workload & Capacity

### Purpose

Assess workforce utilisation and workload distribution.

### Analysis Areas

- Active Agents
- Capacity Utilisation
- Hub Capacity Utilisation
- Workload by Hub
- Agent Workload Ranking
- Workload Heatmap by Hub

### Business Question

Is workforce capacity being utilised effectively?

> ![](./Project%20Images/Workload%20&%20Capacity.png)

---

## 5️⃣ Forecasting & Planning

### Purpose

Support future workforce and operational planning.

### Analysis Areas

- Ticket Volume Forecast
- Projected SLA Breach Volume
- Projected Backlog Volume
- Ticket Growth 

### Business Question

What level of support demand should NorthBridge expect in the future?

> ![](./Project%20Images/Forecasting%20&%20Planning.png)

---

# 🔍 Key Business Insights

## Appointment Change Requests Drive Demand

Appointment Change requests generated the highest ticket volume and represented the largest source of operational workload.

### Business Impact

High-volume administrative requests consume valuable support capacity and contribute significantly to operational workload.

---

## SLA Risk Is Concentrated

Appointment Change, Billing Issue, and Insurance Query tickets account for the majority of SLA breaches.

### Business Impact

A small number of service categories generate a disproportionate share of operational risk.

---

## Escalations Are Primarily Operational

SLA Risk is the leading escalation driver, while more than half of escalations require manual intervention.

### Business Impact

Manual processes increase operational effort, delay resolution times, and reduce service efficiency.

---

## Workforce Capacity Exists but Workload Distribution Is Uneven

NorthBridge operates with 114 active agents and an overall capacity utilisation of approximately 60%.

Manchester operates at 72% utilisation while Leeds operates at 46%.

Agent workload analysis revealed utilisation levels ranging from below 10% to over 400%.

### Business Impact

The primary workforce challenge is workload allocation rather than workforce size.

---

## Manchester Carries the Highest Workload

Manchester processed 594 tickets, significantly more than any other hub.

Appointment Change and Billing Issue tickets contribute heavily to workload concentration.

### Business Impact

Demand is concentrated within specific locations and service categories, creating opportunities for targeted optimisation.

---

## Future Demand Remains Stable

Forecasting indicates relatively stable ticket demand, manageable backlog levels, and no significant upward demand trend.

### Business Impact

Future improvements can be achieved through operational efficiency rather than workforce expansion.

---

## Strategic Recommendations

## 1. Reduce Avoidable Demand

Implement self-service appointment scheduling and automate routine customer requests.

### Expected Benefits

- Reduced ticket volume
- Lower operational workload
- Improved customer experience

---

## 2. Improve SLA Performance

Prioritise Appointment Change, Billing Issue, and Insurance Query processes for targeted improvement initiatives.

### Expected Benefits

- Higher SLA compliance
- Reduced breach volumes
- Improved customer satisfaction

---

## 3. Increase Automation

Automate escalation workflows and reduce reliance on manual escalation processes.

### Expected Benefits

- Faster resolution times
- Reduced manual effort
- Improved operational consistency

---

## 4. Improve Workload Allocation

Implement intelligent ticket routing and workload balancing across hubs and support teams.

### Expected Benefits

- Improved productivity
- Better capacity utilisation
- Reduced workload concentration
- Lower burnout risk

---

## 5. Strengthen Proactive Monitoring

Introduce SLA early-warning alerts and continuous performance monitoring.

### Expected Benefits

- Reduced SLA breaches
- Faster management intervention
- Improved service reliability

---

## Expected Business Value

Implementation of these recommendations is expected to deliver:

- Improved SLA Compliance
- Reduced SLA Breaches
- Lower Escalation Rates
- Better Workforce Utilisation
- Improved Customer Satisfaction
- Increased Operational Efficiency
- Better Resource Allocation
- Improved Strategic Planning

---

## Skills Demonstrated

### Business Intelligence

- KPI Development
- Executive Reporting
- Operational Analytics
- Data Storytelling

### Power BI

- Data Modelling
- DAX Development
- Power Query
- Dashboard Design
- Forecasting

### Analytics

- SLA Analytics
- Workforce Analytics
- Capacity Planning
- Demand Analysis
- Trend Analysis
- Forecasting

---

## Key Takeaway

This project demonstrates how data analytics can be used to improve operational decision-making within a customer support environment.

The analysis revealed that NorthBridge has sufficient workforce capacity to meet demand. The greatest opportunities for improvement lie in reducing avoidable demand, improving SLA performance in high-risk service categories, increasing automation, and optimising workload allocation across support hubs and teams.

By focusing on these areas, NorthBridge can improve customer experience, reduce operational risk, and achieve sustainable service improvements without significant workforce expansion.