📊 Netflix Customer Churn Analysis – Exploratory Data Analysis (EDA)
📌 Project Overview

Customer churn is a critical challenge for subscription-based platforms like Netflix.
This project focuses on Exploratory Data Analysis (EDA) to understand user behavior, identify churn patterns, and extract actionable business insights from Netflix customer data.

The analysis helps answer key questions such as:

Why do users churn?

Which users are more loyal?

What factors influence engagement and churn?

📂 Dataset Description

The dataset contains anonymized Netflix customer information, including:

Demographics: Age

Usage Behavior: Watch hours, last login days

Subscription Details: Subscription type, monthly fee

Preferences: Favorite genre, device used

Account Details: Number of profiles, payment method

Target Variable: churn (0 = Active, 1 = Churned)

🛠️ Tools & Technologies Used

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Jupyter Notebook

🔍 Key EDA Steps Performed
1️⃣ Data Understanding & Cleaning

Checked dataset shape and structure

Handled missing values and duplicates

Verified data types of all columns

2️⃣ Univariate Analysis

Distribution of age, watch hours, last login days

Count plots for subscription type, device, and genres

3️⃣ Bivariate & Multivariate Analysis

Churn analysis by:

Device type

Subscription type

Favorite genre

Payment method

Relationship between:

Watch hours and churn

Last login days and churn

Subscription type and engagement

4️⃣ Correlation Analysis

Identified features strongly correlated with churn

Visualized correlations using heatmaps

📈 Key Insights & Findings

⏱ Last login days is one of the strongest indicators of churn

📉 Users with low watch hours are more likely to churn

📱 Mobile users churn more compared to TV users

💎 Premium subscribers show higher engagement and lower churn

🎭 Drama lovers are more loyal compared to other genre preferences

🚨 Churn rate spikes significantly after 30+ days of inactivity

🎯 Business Recommendations

Based on the analysis, Netflix can reduce churn by:

Sending re-engagement notifications before 30 days of inactivity

Improving mobile viewing experience

Offering discounts or trials to high-risk users

Promoting content aligned with users’ favorite genres

Encouraging plan upgrades for highly engaged users

📁 Project Structure
├── EDA_ON_Netflix_Data.ipynb
├── netflix_customer_churn.csv
├── README.md

🚀 Future Work

Build churn prediction models (Logistic Regression, Random Forest)

Perform feature importance analysis

Create Power BI / Tableau dashboards

Deploy churn insights into a recommendation system

👤 Author

Mohammad Sufiyan
Aspiring Data Analyst | Python | SQL | Data Visualization

⭐ Conclusion

This EDA provides a strong foundation for understanding Netflix customer behavior and churn drivers.
The insights derived can directly support data-driven decision making and customer retention strategies.
