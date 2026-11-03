# Customer Churn Analysis and Customer Intelligence

## Project Overview

Customer churn analysis is the process of identifying customers who stop using a company's products or services. Understanding why customers leave helps businesses improve customer satisfaction, strengthen retention strategies, and reduce revenue loss.

This project analyses customer, subscription, and support data to understand customer churn patterns, identify potential reasons for cancellations, and explore factors that may influence customer retention.

## Objectives

- Analyse customer churn and retention rates.
- Identify subscription plans with higher churn.
- Compare churn across contract types.
- Analyse customer subscription patterns.
- Examine customer complaints and satisfaction scores.
- Understand revenue associated with churned customers.
- Present insights through data visualisations.

## Tools and Technologies

- **Python** – Data analysis and processing.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical operations.
- **SQLite** – Database management and SQL queries.
- **Matplotlib** – Data visualisation.
- **Seaborn** – Statistical data visualisation.
- **Jupyter Notebook** – Analysis environment.

## Dataset

The project uses three related datasets:

1. **Customer Data:** Customer details such as name, country, state, gender, and interests.
2. **Subscription Data:** Subscription type, plan, contract, monthly charges, cancellation details, CLTV, and churn score.
3. **Support Data:** Customer complaints, escalations, satisfaction scores, and feedback.

The supplied sample contains 21 customer records and 9 support records.

## Project Workflow

1. Import the required Python libraries.
2. Load and explore the datasets.
3. Connect to the SQLite database.
4. Perform data cleaning and preprocessing.
5. Combine related tables using SQL queries and customer IDs.
6. Calculate churn and retention metrics.
7. Analyse subscription plans and contract types.
8. Explore customer complaints and satisfaction.
9. Create visualisations to identify patterns.
10. Summarise findings and business insights.

## Key Performance Indicators (KPIs)

- Customer Churn Rate
- Customer Retention Rate
- Average Revenue Per User (ARPU)
- Customer Lifetime Value (CLTV)
- Revenue associated with churned customers
- Average Customer Satisfaction Score

## Visualisations

The project uses different visualisation techniques to explore the data, including:

- Bar charts
- Line charts
- Correlation heatmaps
- Pairplots
- Categorical plots

These visualisations help explore customer behaviour, compare subscription categories, and identify relationships between numerical variables.


## Limitations

- The dataset is relatively small, containing only 21 customer records.
- Findings are exploratory and should not be treated as statistically representative of a larger customer population.
- Correlation between variables does not establish causation.
- The project analyses the supplied churn scores; it does not train a machine learning prediction model.

## Learning Outcomes

This project provides practical exposure to:

- Data cleaning and preprocessing.
- SQL queries and relational database operations.
- Data analysis using Python.
- Exploratory Data Analysis (EDA).
- KPI calculation.
- Data visualisation.
- Interpreting data and communicating business insights.

