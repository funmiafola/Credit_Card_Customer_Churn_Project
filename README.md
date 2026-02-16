# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)



# CREDIT CARD CUSTOMER CHURN ANALYSIS & RETENTION DASHBOARD
Credit Card Customer Churn Analysis & Retention Dashboard is a comprehensive data analytics and machine-learning project designed to help financial institutions identify customers at risk of churning and take proactive retention measures. The project includes an end‑to‑end ETL pipeline, exploratory data analysis (EDA),Hypothesis testing,  predictive modelling, and an interactive dashboard developed in Power BI to support business decision-making.

https://app.powerbi.com/groups/me/reports/dbfa067e-f286-42ea-afad-bc1d6f983c9f/95f4177c5f762be4d905?experience=power-bi





#  Dataset Content
The dataset used in this project is sourced from Kaggle, a trusted platform for open-source analytics datasets.It contains anonymised information about credit card customers, including:

Demographics (age, gender, marital status, income)

Account information (tenure, card category, credit limit, Total Relationship Count)

Transaction behaviour (spending patterns, payment history, Credit Utilisation Ratio, Transaction Count)

Churn Indicator(Whether the customer has left the bank )(Attrition Flag: Attrited Customer(Churned), Existing Customer(Active))

# Business Requirements
The business aims to:

Identify customers likely to churn using behavioural and demographic indicators.

Understand key drivers of churn through visual analytics.

Segment customers based on churn risk and value.

Develop a predictive model to estimate churn probability.

Provide an interactive dashboard to support data‑driven retention strategies.

Recommend an interactive communication tool that can minimise churn risk.



# Hypothesis and how to validate?
Hypothesis 1: 
Statement: Customers with lower engagement (low spending, fewer transactions) are more likely to churn
Validation: The hypothesis will be tested using boxplots between churned and retained customers, supported by Mann-Whitney U statistical testing and machine learning feature importance.

Hypothesis 2: 
Statement: Demographic factors such as age, income, and marital status influence churn likelihood.
Validation: Tested using  interactive Bar Chart and Logistic Regression Coefficients analysis

Hypothesis 3:
Statement: High credit utilisation and late payments increase churn risk.
Validation: Tested using  Boxplots comparing utilisation and revolving balance between churned and retained customers,  supported by Mann-Whitney U statistical testing.


Hypothesis 4:
Statement : Interactive Communication tools can reduce churn risk
Validation: Tested by analysing contact frequency vs churn and simulating retention impact scenarios using churn probability reduction modelling.


# Project Plan
1. Data Collection:
    Dataset sourced from Kaggle;
    Schema inspection and initial profiling performed
2. Data Processing &Transformation (ETL)
    Data Cleaning
    Feature Engineering
    Remove Column
    EncodingPreparation
3. Data Analysis (EDA)
    Demographic Churn Analysis
    Behavioural Churn Analysis
    Correlation Analysis
4. Hypothesis Testing
    Statistical testing
    Distribution analysis
5. Maching Learning Modelling
    Logistic Regression
    Random Forest
    Model Evaluation
6. DashBoard Development 
    Built in PowerBI 
    Integrate predictve output churn risk scoring 



# The rationale to map the business requirements to the Data Visualisations
Business Requirement -	Visualisation
Identify churn drivers -	Feature importance charts
Understand demographics -	Age, gender, income churn charts
Behaviour monitoring-Activity & utilisation visuals
Retention strategy	 -Contact vs churn analysis
Risk targeting	-Risk segmentation chart
Executive reporting-	KPI cards#
Visuals were chosen to ensure business readability and actionable insight delivery.

# Analysis techniques used
The project utilised:
Descriptive statistics
Correlation analysis
Crosstab segmentation
Boxplots & distribution analysis
Mann-Whitney U statistical testing
Logistic Regression
Random Forest modelling

# Ethical considerations
Nothing. it was sourced from Kaggle.
# Dashboard Design
The dashboard consists of four pages:    https://app.powerbi.com/groups/me/reports/dbfa067e-f286-42ea-afad-bc1d6f983c9f/95f4177c5f762be4d905?experience=power-bi

Demographic churn visuals
2. Behavioural Analysis

Activity level
Utilisation

Spend & transaction drops
3. Retention Simulation
Contact frequency vs churn
Retention impact modelling

4. Machine Learning Insights
Feature importance
Risk segmentation
Insights were communicated using percentage visuals, segmentation charts, and business-friendly narratives for both technical and non-technical audiences.

Unfixed Bugs
# Unfixed Bugs
Minor visual alignment inconsistencies remain within Power BI
Logistic regression recall could be improved via hyperparameter tuning
Real-time API deployment not implemented
These do not affect analytical validity.

# Development Roadmap
Future improvements include:
Streamlit app deployment
Real-time scoring integration

# Deployment
The analytical dashboard was deployed locally via Power BI Desktop.
Future deployment could include:
Streamlit web application
Cloud hosting via Heroku


# Main Data Analysis Libraries
pandas → Data manipulation
numpy → Numerical operations
matplotlib / seaborn → Visualisation
scikit-learn → Machine learning
joblib → Model persistence
Power BI → Dashboard development


# Credits
Content
Kaggle dataset documentation
Academic churn modelling references
Scikit-learn official documentation
w3w website
# Media
Dashboard icons: Power BI built-in visuals

Acknowledgements (optional)
I would like to acknowledge the support of Code Institute tutors, peers, and online learning communities who contributed throughout this project.