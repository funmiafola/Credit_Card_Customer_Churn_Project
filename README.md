# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)



# CREDIT CARD CUSTOMER CHURN ANALYSIS & RETENTION DASHBOARD
Credit Card Customer Churn Analysis & Retention Dashboard is a comprehensive data analytics and machine-learning project designed to help financial institutions identify customers at risk of churning and take proactive retention measures. The project includes an end‑to‑end ETL pipeline, exploratory data analysis, predictive modelling, and an interactive dashboard for business stakeholders.

![alt text](image.png)





#  Dataset Content
The dataset used in this project is sourced from Kaggle, a trusted platform for open-source analytics datasets.It contains anonymised information about credit card customers, including:

Demographics (age, gender, marital status, income)

Account information (tenure, card type, credit limit)

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
Validation: I will use Boxplots to compare the "Total Transaction counts of churners vs non-churners and Feature importance 

Hypothesis 2: 
Statement: Demographic factors such as age, income, and marital status influence churn likelihood.
Validation: I will use interactive Bar Chart and Logistic Regression Coefficients

Hypothesis 3:
Statement: High credit utilisation and late payments increase churn risk.
Validation: I will use Scatter Plot of Average Utilisation Ration and Total Revolving Balance 

Hypothesis 4:
Statement : Interactive Communication tools can reduce churn risk
Validation: I will simulate "Retention Impact 



# Project Plan
1. Collection: I sourced data from Kaggle; I perform schema inspection and initial profiling 
2. Data Processing &Transformation (ETL)
3. Data Analysis
4. Interpretation
5. DashBoard Development using PowerBI and Tableau and Integrate predictve model for real-time churn scoring.



# The rationale to map the business requirements to the Data Visualisations
List your business requirements and a rationale to map them to the Data Visualisations
# Analysis techniques used
List the data analysis methods used and explain limitations or alternative approaches.
How did you structure the data analysis techniques. Justify your response.
Did the data limit you, and did you use an alternative approach to meet these challenges?
How did you use generative AI tools to help with ideation, design thinking and code optimisation?
# Ethical considerations
Were there any data privacy, bias or fairness issues with the data?
How did you overcome any legal or societal issues?
# Dashboard Design
List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
How were data insights communicated to technical and non-technical audiences?
Explain how the dashboard was designed to communicate complex data insights to different audiences.
# Unfixed Bugs
Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
Did you recognise gaps in your knowledge, and how did you address them?
If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.
# Development Roadmap
What challenges did you face, and what strategies were used to overcome these challenges?
What new skills or tools do you plan to learn next based on your project experience?
# Deployment
Heroku
The App live link is: https://YOUR_APP_NAME.herokuapp.com/
Set the runtime.txt Python version to a Heroku-20 stack currently supported version.
The project was deployed to Heroku using the following steps.
Log in to Heroku and create an App
From the Deploy tab, select GitHub as the deployment method.
Select your repository name and click Search. Once it is found, click Connect.
Select the branch you want to deploy, then click Deploy Branch.
The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
If the slug size is too large then add large files not required for the app to the .slugignore file.
# Main Data Analysis Libraries
Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.
# Credits
In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism.
You can break the credits section up into Content and Media, depending on what you have included in your project.
# Content
The text for the Home page was taken from Wikipedia Article A
Instructions on how to implement form validation on the Sign-Up page was taken from Specific YouTube Tutorial
The icons in the footer were taken from Font Awesome
# Media
The photos used on the home and sign-up page are from This Open-Source site
The images used for the gallery page were taken from this other open-source site
Acknowledgements (optional)
Thank the people who provided support through this project.