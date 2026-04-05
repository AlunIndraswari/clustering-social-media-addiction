# A Behavioral Persona Approach to Social Media Addiction
## Project Overview
This project applies data science techniques to understand the nuanced relationship between social media usage and productivity. Instead of treating addiction as a monolithic category, we use clustering to identify distinct behavioral "personas" based on real-world usage patterns.

## Objectives
* Identify Personas: Use K-Means clustering to discover unique behavioral groups.
* Analyze Inhibitors: Quantify how notifications and lack of sleep act as primary productivity inhibitors.
* Actionable Insights: Provide tailored recommendations for each identified persona rather than generic advice.

## Dataset
The analysis is performed on a dataset containing around 6,000 entries with the following features:
* Daily Screen Time & Social Media Hours
* Study & Sleep Hours
* Notifications per Day
* Focus & Productivity Scores
* Addiction Level (Low, Medium, High)

## Methodology
* Data Cleaning: Handled missing values (approx. 2% of the dataset) and ensured data integrity.
* Exploratory Data Analysis (EDA): Visualized distributions of screen time, productivity, and addiction levels to understand the baseline trends.
* Unsupervised Learning: Implemented K-Means Clustering to segment users based on behavioral patterns.
* Statistical Validation: Performed T-Tests to confirm that the identified personas (e.g., Persona 0 vs. Persona 2) are significantly different from one another.

## Key Findings & Personas
The model identifies specific groups, such as:
* The Passively Distracted: Users who may not have the highest screen time but are significantly impacted by frequent notifications.
* Productive Users: Users who maintain high focus scores despite moderate social media use.
(Additional personas and specific T-Test results can be found within the notebook).

## Tech Stack
Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 📈 Actionable Recommendations
The project concludes with specific interventions for different user types, such as notification management for the "Passively Distracted" and sleep hygiene improvements for high-addiction clusters.

## How to Use
* Ensure you have the dataset in this kaggle [dataset](https://www.kaggle.com/datasets/asifxzaman/social-media-addiction-vs-productivity-dataset)
* Install the required libraries:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```
Open and run clustering-persona-approach-to-socmed-addiction.ipynb to view the full analysis and results.
