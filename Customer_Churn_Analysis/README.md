# Customer Churn Analysis Project

A comprehensive data science project analyzing customer churn patterns and building predictive models to identify at-risk customers. This project demonstrates end-to-end data analysis, machine learning, and business intelligence capabilities.

## 🎯 Project Overview

Customer churn is a critical business metric that directly impacts revenue and growth. This project analyzes customer behavior patterns to:

- **Identify key factors** driving customer churn
- **Build predictive models** to identify at-risk customers
- **Provide actionable insights** for customer retention strategies
- **Quantify business impact** of churn on revenue

## 📊 Dataset

The analysis uses a telecommunications customer dataset with **5,000 customers** and **22 features** including:

### Customer Demographics
- Age, Gender, Senior Citizen status
- Partner and Dependents information

### Account Information  
- Tenure (months with company)
- Contract type (Month-to-month, One year, Two year)
- Payment method and billing preferences

### Services Subscribed
- Phone services and multiple lines
- Internet service type (DSL, Fiber optic, None)
- Additional services (Security, Backup, Tech Support, Streaming)

### Financial Data
- Monthly charges and total charges
- Revenue impact analysis

## 🔍 Key Findings

### Churn Rate Analysis
- **Overall churn rate: 57.4%** (2,868 out of 5,000 customers)
- **Estimated annual revenue loss: $3.0M**

### Critical Risk Factors

| Factor | High Risk Segment | Churn Rate |
|--------|------------------|------------|
| **Contract Type** | Month-to-month | 67.1% |
| **Payment Method** | Electronic check | 65.2% |
| **Customer Tenure** | 0-12 months | 71.0% |
| **Service Type** | Fiber optic | 65.8% |
| **Monthly Charges** | $91+ | 62.7% |

### Customer Risk Segmentation
- **High Risk**: 2,397 customers (47.9%) - Average risk score: 0.71
- **Medium Risk**: 2,332 customers (46.6%) - Average risk score: 0.48  
- **Low Risk**: 271 customers (5.4%) - Average risk score: 0.25

## 🤖 Machine Learning Models

### Model Performance
| Model | Accuracy | Best Features |
|-------|----------|---------------|
| **Logistic Regression** | **67.0%** ✅ | All features with scaling |
| Random Forest | 65.3% | Feature importance ranking |

### Top Predictive Features
1. **Monthly Charges** (13.94% importance)
2. **Total Charges** (13.26% importance)  
3. **Tenure Months** (11.65% importance)
4. **Age** (11.31% importance)
5. **Contract Type** (6.27% importance)

## 💼 Business Recommendations

### 1. Contract Strategy
- **Target Month-to-month customers** for contract upgrades
- Offer incentives for longer-term commitments
- Potential impact: Reduce churn from 67% to 41%

### 2. Payment Method Optimization  
- **Address Electronic check issues** (highest churn at 65%)
- Promote automatic payment methods
- Improve payment processing experience

### 3. Early Intervention Program
- **Focus on first 12 months** (71% churn rate)
- Implement comprehensive onboarding
- Regular engagement and satisfaction checks

### 4. Service Quality Improvements
- **Review Fiber optic service delivery** (66% churn rate)
- Enhance customer support for premium services
- Consider pricing adjustments for value perception

### 5. Pricing Strategy Review
- **Analyze high-charge customers** ($91+ segment at 63% churn)
- Implement value-based pricing models
- Create competitive retention packages
