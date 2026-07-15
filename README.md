# QuickCart – End-to-End Business Analysis Case Study

## Overview

QuickCart is a fictional e-commerce platform created to demonstrate the complete Business Analysis lifecycle for a SaaS-based online retail business.

Rather than focusing only on dashboards or documentation, this project follows a structured consulting approach—from understanding business problems to proposing data-driven solutions and translating them into functional requirements.

The case study simulates the work of a Business Analyst collaborating with stakeholders to improve customer experience, operational efficiency, and business performance.

---

#  Project Flow

This repository follows the same approach a Business Analyst would follow during a real project.

```text
Business Discovery
        ↓
Business Analysis
        ↓
Requirements Engineering
        ↓
Solution Design
        ↓
Technical Validation
        ↓
Testing
        ↓
Business Recommendations & Roadmap
```

Each phase builds upon the previous one, simulating an end-to-end Business Analysis engagement.

---

# Project Progress

| Phase |
|--------|
| 🟡 Business Discovery *(In Progress)* |
| 🟡 Business Analysis *(In Progress)* |
| ⚪ Requirements Engineering |
| ⚪ Solution Design |
| ⚪ Technical Validation |
| ⚪ Testing |
| ⚪ Business Recommendations & Roadmap |

---

#  Repository Structure

```text
📦 QuickCart
│
├── 📁 01_Business_Discovery
│      ├── 📄 Business_Context.md
│      ├── 📄 Business_Objectives.md
│      ├── 📄 Stakeholder_Analysis.md
│      ├── 📄 Business_Problems.md
│      ├── 📄 Business_Capability_Map.md
│      ├── 📄 Current_State_(As-Is)_Process.md
│      └── 📄 Success_Criteria.md
│
├── 📁 02_Business_Analysis
│      ├── 📄 Problem_Validation.md
│      ├── 📄 KPI_Framework.md
│      ├── 📄 Root_Cause_Analysis.md
│      ├── 📄 Gap_Analysis.md
│      ├── 📄 Business_Impact_Analysis.md
│      └── 📄 Prioritization_(MoSCoW).md
│
├── 📁 03_Requirements_Engineering
│      ├── 📄 Business_Requirements_Document_(BRD).md
│      ├── 📄 Functional_Requirements_Document_(FRD).md
│      ├── 📄 User_Stories.md
│      ├── 📄 Acceptance_Criteria.md
│      ├── 📄 Use_Cases.md
│      └── 📄 Requirement_Traceability_Matrix_(RTM).md
│
├── 📁 04_Solution_Design
│      ├── 📄 BPMN_Diagrams.md
│      ├── 📄 User_Flow.md
│      ├── 📄 Wireframes.md
│      ├── 📄 API_Requirements.md
│      └── 📄 Solution_Architecture.md
│
├── 📁 05_Technical_Validation
│      ├── 📄 Database_Design.md
│      ├── 📄 ER_Diagram.md
│      ├── 📄 SQL_Analysis.md
│      ├── 📄 Dashboard_Design.md
│      └── 📄 KPI_Validation.md
│
├── 📁 06_Testing
│      ├── 📄 User_Acceptance_Testing_(UAT).md
│      ├── 📄 Test_Cases.md
│      ├── 📄 Defect_Log.md
│      └── 📄 Requirement_Traceability_Matrix_(RTM).md
│
├── 📁 07_Business_Recommendations_&_Roadmap
│      ├── 📄 Business_Recommendations.md
│      ├── 📄 Implementation_Roadmap.md
│      ├── 📄 Expected_Business_Impact.md
│      └── 📄 Lessons_Learned.md
│
├── 📁 Assets
│      ├── Images
│      ├── Wireframes
│      ├── Dashboard
│      ├── BPMN_Diagrams
│      └── Screenshots
│
└── 📄 README.md
```

---

#  Business Analysis Journey

```text
Business Context
        ↓
Business Objectives
        ↓
Stakeholder Analysis
        ↓
Business Problems
        ↓
Problem Validation
        ↓
Root Cause Analysis
        ↓
Business Impact Analysis
        ↓
Business Capability Mapping
        ↓
Requirements Gathering
        ↓
Business Requirements Document (BRD)
        ↓
Functional Requirements Document (FRD)
        ↓
User Stories
        ↓
Acceptance Criteria
        ↓
BPMN
        ↓
User Flow
        ↓
Wireframes
        ↓
API Requirements
        ↓
Database Design
        ↓
SQL Analysis
        ↓
Power BI Dashboard
        ↓
User Acceptance Testing (UAT)
        ↓
Business Recommendations
        ↓
Implementation Roadmap
```

---

#  Skills Demonstrated

- Business Analysis
- Requirement Gathering
- Stakeholder Management
- Business Process Analysis
- Root Cause Analysis
- Gap Analysis
- Business Impact Analysis
- KPI Definition
- Business Documentation (BRD & FRD)
- User Stories
- Acceptance Criteria
- BPMN
- User Flow Design
- Wireframing (Figma)
- API Analysis
- SQL
- Database Design
- Power BI
- Dashboard Design
- User Acceptance Testing (UAT)
- Requirement Traceability Matrix (RTM)
- Business Strategy & Problem Solving

---

# 01_Business_Discovery

## Business Context

QuickCart is a SaaS-based quick-commerce platform designed to provide customers with a seamless online shopping experience by enabling them to browse products, place orders, make secure payments, and receive deliveries within a short time frame.

As the business expanded across multiple locations, the increase in customers, orders, products, and delivery operations introduced several operational and customer experience challenges. These challenges began affecting key business metrics such as customer retention, order cancellations, stock availability, delivery performance, and overall customer satisfaction.

The leadership team lacked a centralized view of operational performance, making it difficult to identify bottlenecks, monitor key business metrics, and take timely, data-driven decisions. Different teams operated with limited visibility into critical business information, resulting in reactive decision-making instead of proactive problem resolution.

To address these challenges, QuickCart initiated this Business Analysis project to understand the existing business processes, identify operational inefficiencies, validate business problems using data, define business and functional requirements, and recommend scalable business solutions that improve operational efficiency, customer experience, and overall business performance.

This project simulates the role of a Business Analyst working closely with business stakeholders to bridge the gap between business needs and technology solutions while ensuring that every recommendation aligns with the organization's strategic objectives.

---

## Business Objectives

The primary objective of this Business Analysis engagement is to identify the operational and customer experience challenges affecting QuickCart's business performance and recommend data-driven solutions that improve operational efficiency, customer satisfaction, and long-term business growth.

### Customer Objectives

- Improve Customer Retention Rate
- Increase Repeat Purchase Rate
- Improve Customer Satisfaction (CSAT)
- Reduce Customer Churn Rate
- Improve the overall customer shopping experience

---

### Operational Objectives

- Reduce Order Cancellation Rate
- Reduce Stock-out Rate
- Improve Inventory Management
- Reduce Average Delivery Time
- Improve Order Fulfillment Rate
- Improve operational visibility through centralized KPI reporting

---

### Product Objectives

- Improve Product Search Experience
- Enhance Product Recommendation Accuracy
- Simplify the Checkout Experience
- Improve Payment Success Rate
- Reduce Cart Abandonment Rate

---

### Business Objectives

- Increase Revenue
- Increase Average Order Value (AOV)
- Improve Customer Lifetime Value (CLV)
- Improve Operational Efficiency
- Enable Data-Driven Decision Making
- Strengthen QuickCart's competitive position within the quick-commerce market

---

## Success Metrics

The success of this project will be measured through improvements in the following Key Performance Indicators (KPIs):

- Customer Retention Rate
- Customer Churn Rate
- Repeat Purchase Rate
- Order Cancellation Rate
- Stock-out Rate
- Average Delivery Time
- Checkout Conversion Rate
- Cart Abandonment Rate
- Customer Satisfaction (CSAT)
- Customer Lifetime Value (CLV)
- Revenue Growth

### Primary Objectives

- Reduce Order Cancellation Rate
- Reduce Stock-out Rate
- Improve Customer Retention
- Improve Customer Satisfaction
- Increase Repeat Purchase Rate
- Improve Operational Efficiency
- Reduce Delivery Delays
- Improve Checkout Conversion Rate
- Increase Revenue
- Improve Decision Making through Data

---

## Stakeholder Analysis

| Stakeholder | Responsibility |
|-------------|----------------|
| Customers | Purchase products, provide ratings and feedback |
| Delivery Partners | Deliver orders within SLA |
| Operations Manager | Monitor inventory and delivery operations |
| Customer Support Team | Resolve customer issues |
| Marketing Team | Customer acquisition and retention |
| Revenue Management | Revenue optimization |
| Product Manager | Product improvements |
| Inventory Manager | Stock allocation |
| Business Analyst | Requirement gathering and business analysis |

---

## Business Problems

| ID | Business Problem |
|----|------------------|
| BP-01 | Declining Customer Retention |
| BP-02 | High Stock-out Rate |
| BP-03 | High Order Cancellation Rate |
| BP-04 | Checkout / Payment Drop-offs |
| BP-05 | Delayed Deliveries |
| BP-06 | Poor Operational KPI Visibility |
| BP-07 | Complex User Interface |
| BP-08 | Product Search & Recommendation Issues |
| BP-09 | Low Repeat Purchase Rate |

---

## Business Capability Map

| Business Problem | Business Capability |
|------------------|---------------------|
| Declining Customer Retention | Customer Relationship & Loyalty Management |
| High Stock-out Rate | Inventory Management |
| High Order Cancellation | Order Management |
| Checkout / Payment Drop-off | Checkout & Payment Management |
| Delayed Deliveries | Delivery Management |
| Poor Operational KPI Visibility | Business Intelligence & Reporting |
| Complex User Interface | User Experience Management |
| Product Search & Recommendation Issues | Product Discovery & Recommendation |
| Low Repeat Purchase Rate | Customer Engagement & Loyalty |

---

## Current State (As-Is) Process

Not Started

---

## Success Criteria

Not Started

---

# 02_Business_Analysis

## Problem Validation

### Business Problem 1 – Declining Customer Retention

### Validation Metrics

- Customer Retention Rate
- Customer Churn Rate
- Repeat Purchase Rate
- Purchase Frequency
- Customer Lifetime Value (CLV)
- Days Between Orders
- Customer Satisfaction (CSAT)
- Cohort Analysis

### Stakeholder Questions

- Since when has customer retention been declining?
- Which customer segments are most affected?
- Was any new feature, pricing strategy, or campaign introduced before the decline?
- Why are loyal customers still purchasing from QuickCart?
- Which competitors are customers switching to?

---

## Root Cause Analysis

### Customer Retention

Root Causes

- Late Deliveries
- Wrong Product Deliveries
- Product Stock-outs
- Poor Customer Support Experience
- Poor Delivery Partner Experience
- Complex User Interface
- Hidden Charges and Platform Fees
- Price Difference Compared to Competitors
- No Loyalty Program
- Lack of Brand Awareness

---

### Stock-outs

Root Causes

- Incorrect Demand Forecasting
- Inventory Allocation Issues
- Supplier Delays
- Poor Inventory Visibility
- High Demand Peaks

---

### Checkout / Payment Drop-off

Root Causes

- Complex Checkout Process
- Multiple Checkout Screens
- Hidden Charges
- Payment Failures
- Limited Payment Options

---

### Delivery Delays

Root Causes

- Poor Route Planning
- Inefficient Delivery Partner Allocation
- Dark Store Delays
- Traffic Conditions
- Inventory Delays

---

## Business Impact Analysis

### Business Impact

- Reduced Customer Lifetime Value (CLV)
- Revenue Loss
- Increased Customer Churn
- Poor Customer Experience
- Operational Inefficiencies
- Brand Reputation Damage
- Increased Operational Costs
- Reduced Competitive Advantage

---

### MoSCoW Prioritization

#### Must Have

- Improve Customer Retention
- Reduce Order Cancellations
- Reduce Stock-outs
- Improve Delivery Performance
- Improve Checkout Experience

#### Should Have

- Improve Product Recommendation Engine
- Improve Operational Dashboards
- Introduce Customer Loyalty Program

#### Could Have

- Personalized Recommendations
- Gamification
- Advanced Customer Segmentation

---

# 📊 KPI Framework

## Purpose

The KPI (Key Performance Indicator) Framework defines the business metrics used to measure the health of QuickCart's operations, customer experience, and business growth. These KPIs help stakeholders monitor business performance, identify operational bottlenecks, validate business problems, and measure the success of implemented solutions.

---

# Customer KPIs

| KPI | Business Question | Formula | Why it Matters | Target |
|------|-------------------|----------|----------------|---------|
| Customer Retention Rate | Are customers continuing to shop with us? | (Customers Retained / Total Customers) × 100 | Measures customer loyalty | Increase |
| Customer Churn Rate | How many customers are leaving? | (Lost Customers / Total Customers) × 100 | Indicates customer dissatisfaction | Decrease |
| Repeat Purchase Rate | How many customers place multiple orders? | (Repeat Customers / Total Customers) × 100 | Indicates customer loyalty | Increase |
| Customer Lifetime Value (CLV) | How much revenue does one customer generate over time? | Average Order Value × Purchase Frequency × Customer Lifespan | Measures long-term customer value | Increase |
| Days Between Orders | Are customers ordering frequently? | Difference between consecutive order dates | Indicates customer engagement | Decrease |
| Purchase Frequency | How often does a customer purchase? | Total Orders / Unique Customers | Measures engagement | Increase |
| Customer Satisfaction (CSAT) | Are customers satisfied? | Average customer rating | Measures overall experience | Increase |

---

# Order KPIs

| KPI | Business Question | Formula | Why it Matters | Target |
|------|-------------------|----------|----------------|---------|
| Total Orders | How many orders are placed? | Count of Orders | Business growth indicator | Increase |
| Order Cancellation Rate | How many orders get cancelled? | (Cancelled Orders / Total Orders) × 100 | Indicates operational issues | Decrease |
| Order Fulfillment Rate | How many orders are successfully delivered? | (Delivered Orders / Total Orders) × 100 | Measures operational efficiency | Increase |
| Average Order Value (AOV) | How much does each customer spend? | Revenue / Total Orders | Revenue indicator | Increase |
| Return Rate | How many orders are returned? | (Returned Orders / Delivered Orders) × 100 | Product & delivery quality | Decrease |

---

# Delivery KPIs

| KPI | Business Question | Formula | Why it Matters | Target |
|------|-------------------|----------|----------------|---------|
| Average Delivery Time | How long does delivery take? | Delivery Time − Order Time | Customer experience | Decrease |
| On-Time Delivery Rate | Are deliveries reaching on time? | (On-Time Deliveries / Total Deliveries) × 100 | Delivery performance | Increase |
| Late Delivery Rate | How many deliveries are delayed? | (Late Deliveries / Total Deliveries) × 100 | Identifies logistics issues | Decrease |
| SLA Compliance | Are we meeting promised delivery timelines? | (Orders Delivered Within SLA / Total Orders) × 100 | Operational performance | Increase |

---

# Inventory KPIs

| KPI | Business Question | Formula | Why it Matters | Target |
|------|-------------------|----------|----------------|---------|
| Stock-out Rate | How often are products unavailable? | (Stock-out Orders / Total Orders) × 100 | Measures inventory efficiency | Decrease |
| Product Availability | Are products available when customers need them? | Available Products / Total Products | Customer experience | Increase |
| Inventory Turnover | How efficiently is inventory utilized? | Cost of Goods Sold / Average Inventory | Inventory optimization | Increase |

---

# Product KPIs

| KPI | Business Question | Formula | Why it Matters | Target |
|------|-------------------|----------|----------------|---------|
| Best-Selling Products | Which products generate the most sales? | Based on quantity sold | Product planning | Monitor |
| Worst-Performing Products | Which products underperform? | Based on lowest sales | Product optimization | Monitor |
| Category Performance | Which product categories perform best? | Revenue by category | Portfolio optimization | Monitor |
| Product Search Success Rate | Are customers finding the products they need? | Successful Searches / Total Searches | Search effectiveness | Increase |

---

# Checkout & Payment KPIs

| KPI | Business Question | Formula | Why it Matters | Target |
|------|-------------------|----------|----------------|---------|
| Checkout Conversion Rate | Are customers completing checkout? | Completed Orders / Checkout Initiated | Funnel performance | Increase |
| Cart Abandonment Rate | How many customers leave without purchasing? | Abandoned Carts / Created Carts | Identifies friction | Decrease |
| Payment Success Rate | Are payments completing successfully? | Successful Payments / Payment Attempts | Payment reliability | Increase |

---

# Customer Support KPIs

| KPI | Business Question | Formula | Why it Matters | Target |
|------|-------------------|----------|----------------|---------|
| Complaint Rate | How many customers raise complaints? | Complaints / Total Orders | Service quality | Decrease |
| Average Resolution Time | How quickly are issues resolved? | Total Resolution Time / Total Complaints | Support efficiency | Decrease |
| First Contact Resolution (FCR) | Are issues resolved in the first interaction? | First Contact Resolved / Total Cases | Customer satisfaction | Increase |

---

# Business KPIs

| KPI | Business Question | Formula | Why it Matters | Target |
|------|-------------------|----------|----------------|---------|
| Revenue | How much revenue is generated? | Sum of Order Value | Overall business growth | Increase |
| Gross Merchandise Value (GMV) | What is the total value of products sold? | Sum of Product Prices | Business scale | Increase |
| Conversion Rate | How many visitors become customers? | Orders / Visitors | Measures business growth | Increase |
| Market Share | How competitive is QuickCart? | Company Sales / Market Sales | Competitive performance | Increase |

---

# KPI Ownership

| Stakeholder | KPIs Owned |
|--------------|------------|
| Product Manager | Conversion Rate, Retention Rate, Churn Rate, AOV |
| Operations Manager | Cancellation Rate, Delivery Time, SLA Compliance, Stock-out Rate |
| Inventory Manager | Inventory Turnover, Product Availability |
| Customer Support Manager | Complaint Rate, Resolution Time, CSAT |
| Marketing Manager | Conversion Rate, Repeat Purchase Rate, CLV |
| Leadership Team | Revenue, GMV, Market Share |

---

# Success Criteria

The project will be considered successful if the following business outcomes are achieved:

- Increase Customer Retention Rate
- Reduce Customer Churn Rate
- Increase Repeat Purchase Rate
- Reduce Stock-out Rate
- Reduce Order Cancellation Rate
- Improve Checkout Conversion Rate
- Reduce Cart Abandonment Rate
- Reduce Average Delivery Time
- Improve Customer Satisfaction (CSAT)
- Increase Revenue and Customer Lifetime Value (CLV)

---

## Gap Analysis

Not Started

---

# 03_Requirements_Engineering

- Business Requirements Document (BRD)
- Functional Requirements Document (FRD)
- User Stories
- Acceptance Criteria
- Use Cases
- Requirement Traceability Matrix (RTM)

---

# 04_Solution_Design

- BPMN Diagrams
- User Flow
- Wireframes (Figma)
- API Requirements
- Solution Architecture

---

# 05_Technical_Validation

- Database Design
- ER Diagram
- SQL Analysis
- Power BI Dashboard
- KPI Validation

---

# 06_Testing

- User Acceptance Testing (UAT)
- Test Cases
- Defect Log
- Requirement Traceability Matrix (RTM)

---

# 07_Business_Recommendations_&_Roadmap

- Business Recommendations
- Implementation Roadmap
- Expected Business Impact
- Lessons Learned
