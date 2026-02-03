# Customer Churn Analysis - Telco Dataset

## 📊 Project Overview
This Tableau dashboard analyzes customer churn patterns for a telecommunications company using the Telco Customer Churn dataset from Kaggle. The analysis identifies key drivers of customer attrition and provides actionable insights to improve retention rates.

## 🎯 Business Problem
Telecom companies face significant customer churn, impacting revenue and growth. This analysis helps answer:
- Why are customers leaving?
- Which customer segments are most at risk?
- What actions can reduce churn by 20%?
- How does churn impact monthly recurring revenue (MRR)?

## 📁 Dataset Information
**Source:** [Telco Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
**Records:** 7,043 customers
**Time Period:** Recent customer data with up to 72 months tenure

**Key Variables:**
- Demographics: Gender, SeniorCitizen, Partner, Dependents
- Services: PhoneService, InternetService, OnlineSecurity, StreamingTV, etc.
- Account: Contract type, PaymentMethod, PaperlessBilling
- Financial: MonthlyCharges, TotalCharges
- Target: Churn (Yes/No)

## 🛠️ Tools Used
- **Tableau Desktop/Public** - Dashboard creation and visualization
- **Microsoft Excel** - Initial data cleaning and exploration
- **Git/GitHub** - Version control and project documentation

## 📈 Dashboard Components

### 1. **KPI Overview**
- Total Customers: 7,043
- Overall Churn Rate: 26.5%
- Average Monthly Charge: $64.76
- Average Tenure: 32.4 months

### 2. **Demographic Analysis**
- Churn by Gender and Senior Citizen status
- Comparative retention patterns

### 3. **Contract Impact**
- Donut chart showing churn distribution by contract type
- Month-to-month contracts show 43% churn vs 3% for two-year contracts

### 4. **Tenure Analysis**
- Line chart: Churn pattern over customer lifetime
- Bar chart: Churn rate by tenure groups (0-12, 13-24, 25-36, 37-48, 49+ months)

### 5. **Service Analysis**
- Heatmap: Churn rates by Internet Service and Contract type
- Fiber optic customers show highest churn despite higher payments

### 6. **Financial Impact**
- Treemap: Lost revenue by service type and contract
- Monthly revenue at risk: ~$139,000

### 7. **Customer Lifetime Value**
- Box plot: CLV distribution by customer type (Short/Medium/Long-term)
- Long-term customers show 3x higher lifetime value

### 8. **Retention Drivers**
- Analysis of tech services impact on retention
- Customers with tech support churn 50% less

## 🔍 Key Insights

### **Critical Findings:**
1. **Contract Type is #1 Churn Driver**
   - Month-to-month: 43% churn rate
   - One-year: 11% churn rate  
   - Two-year: 3% churn rate

2. **Early Churn is Concentrated**
   - 45% of churn happens in first 6 months
   - 70% of churn happens within first year

3. **High-Value, High-Risk Segment**
   - Fiber optic customers pay 34% more but churn 41% more
   - Electronic check users churn 2x more than automatic payment users

4. **Protective Factors**
   - Tech support reduces churn by 50%
   - Online security reduces churn by 40%

=
## 🔧 Setup Instructions

### **Quick Start:**
1. **View Online:** https://public.tableau.com/app/profile/aayush.karki/viz/CustomerRetentionChurnAnalysis_17700337141630/Dashboard1
