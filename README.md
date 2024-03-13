# Traffic Stops Discrimination Study Analysis

Welcome to our Traffic Stops Discrimination Study Analysis repository. This project dives deep into the extensive data provided by the Stanford Open Policing Project, focusing specifically on the dataset from San Diego, chosen for its rich variety and volume of data points. Our main objective is to shed light on racial and ethnic disparities in traffic stops and searches, utilizing advanced data analysis and machine learning techniques.

## Project Overview

The Stanford Open Policing Project has amassed a treasure trove of data covering traffic stops from various U.S. police departments, aiming to understand the dynamics of racial and ethnic disparities in policing. Our analysis zeroes in on the San Diego dataset, rich in both volume and the variety of recorded features, to dissect and understand these complexities.

## Dataset Details

Our chosen dataset encompasses a broad spectrum of information, including:

- Date and time of the stop
- Location
- Driver demographics (race, gender, age)
- Outcome of the stop (e.g., warning, citation, arrest)
- Details on searches conducted and contraband found

Covering data from 31 states and numerous individual departments, the Stanford Open Policing Project provides a unique lens through which to examine policing practices across the United States.

## Methodology

Our analysis pipeline is structured as follows:

1. **Data Preprocessing**: We cleaned and preprocessed the San Diego dataset, removing irrelevant columns, handling missing values, and categorizing continuous variables to facilitate our analysis.

2. **Exploratory Data Analysis (EDA)**: Leveraging libraries like Matplotlib, Seaborn, and Plotly, we conducted a thorough EDA to uncover initial insights into the dataset, focusing on patterns of traffic stops, searches, and outcomes across different demographics.

3. **Feature Engineering**: We transformed the dataset into a format suitable for machine learning, encoding categorical variables and engineering new features to improve our model's predictive capabilities.

4. **Model Building**: Using Scikit-learn, we trained several models, including Random Forest and Logistic Regression, to predict the likelihood of an arrest based on various features. We also addressed the class imbalance issue inherent in our dataset through techniques like upsampling.

5. **Model Evaluation**: We evaluated our models using metrics such as accuracy, precision, recall, and F1 score, along with confusion matrices and AIC scores, to select the best-performing model for our objective.

6. **Insights and Conclusions**: The final section of our notebook presents a detailed discussion of our findings, highlighting significant disparities in traffic stop outcomes across different races and genders.

## Tools and Libraries Used

- Python
- Pandas for data manipulation
- Matplotlib, Seaborn, and Plotly for data visualization
- Scikit-learn for machine learning
- dmba for model evaluation

## Key Findings

Our analysis uncovered significant disparities in traffic stop outcomes, particularly with respect to race and gender. Notably, we observed a higher likelihood of searches and arrests among minority groups, raising important questions about bias in policing practices.

## How to Use This Repository

1. **Exploration**: Dive into the Jupyter notebook for a detailed walkthrough of our analysis process, from data cleaning to model evaluation.

2. **Replication**: Use the provided code to replicate our analysis on your local machine. The dataset can be obtained from the Stanford Open Policing Project website.

3. **Expansion**: Adapt our methodology to analyze traffic stop data from other regions or to explore additional aspects of policing practices.

## Conclusion

This project represents a comprehensive effort to understand and highlight racial and ethnic disparities in traffic stops and searches. Through meticulous data analysis and machine learning, we've unearthed patterns that warrant further investigation and discussion among policymakers, law enforcement agencies, and the public at large.

We invite you to explore our findings, replicate our analysis, and contribute to the ongoing conversation about equity and justice in policing.
