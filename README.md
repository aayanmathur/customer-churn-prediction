#  Customer Churn Analysis & Prediction

> A comprehensive machine learning project that predicts customer churn with 80%+ accuracy, enabling proactive retention strategies and significant revenue protection.


##  Project Overview

This project addresses a critical business challenge in the telecommunications industry: **customer churn**. By leveraging machine learning, we predict which customers are likely to cancel their service, enabling companies to take proactive retention measures.

###  Key Achievements
- **80.1% Prediction Accuracy** with Random Forest model
- **84.2% ROC-AUC Score** indicating excellent model discrimination
- **Clear Business Insights** with actionable recommendations
- **Revenue Impact Analysis** showing potential savings of hundreds of thousands in annual revenue

##  Business Impact

### Current Situation
- **26.5% Churn Rate** across 7,043 customers
- **Significant Revenue Loss** from customer attrition
- **Reactive Approach** to customer retention

### Solution Value
- **Proactive Identification** of at-risk customers
- **Targeted Retention Campaigns** for high-risk segments  
- **20% Churn Prevention** through model-guided interventions
- **Substantial ROI** from revenue retention

##  Key Findings

###  Highest Risk Factors
1. **Month-to-month contracts**: 42.7% churn rate
2. **New customers (0-1 year)**: 47.7% churn rate  
3. **Electronic check payment**: 45.3% churn rate
4. **Fiber optic service**: 41.9% churn rate

###  Business Insights
- Contract length is the strongest predictor of churn
- Customer tenure significantly impacts retention
- Payment method reveals customer commitment levels
- Service quality issues may exist with fiber optic offerings

##  Technical Implementation

### Machine Learning Models
- **Random Forest Classifier**: Primary model (80.1% accuracy)
- **Logistic Regression**: Interpretable baseline (79.6% accuracy)
- **Feature Engineering**: Created 5+ new predictive features
- **Cross-validation**: Robust model evaluation

### Feature Engineering
```python
# Key engineered features
- CustomerValue (MonthlyCharges × tenure)
- AvgChargesPerMonth (TotalCharges / tenure)
- ServiceCount (number of additional services)
- IsHighValue (top 25% by monthly charges)
- IsLongTerm (tenure >= 24 months)
```

### Model Performance
| Model | Accuracy | ROC-AUC | Precision | Use Case |
|-------|----------|---------|-----------|----------|
| Random Forest | 80.1% | 84.2% | High | Production deployment |
| Logistic Regression | 79.6% | 84.0% | High | Business interpretation |

##  Analysis Workflow

### Step 1: Data Exploration
- Dataset overview and quality assessment
- Missing value analysis
- Initial churn rate calculation

### Step 2: Business Understanding  
- Churn impact quantification
- Revenue loss analysis
- Feature categorization

### Step 3: Data Cleaning & EDA
- Data type corrections
- Categorical encoding
- Churn driver identification

### Step 4: Feature Engineering & Modeling
- Advanced feature creation
- Model training and comparison
- Performance evaluation

### Step 5: Business Recommendations
- Actionable insights generation
- Implementation roadmap
- ROI analysis
