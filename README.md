# The Impact of Remote Work Analysis Project

*By: Ryan Cruickshank*

## Table of Contents:

1. Introduction:
   a) Problem Context
   b) Significance of the Study
   c) Executive Summary

2. Exploratory Data Findings
   a) Key Performance Indicators 1-5
   b) Visual Representations of KPIs 1-5

3. Statistical Analysis
   a) Accuracy Measure
   b) Decision Tree/Random Forest Plot
   c) Confusion Matrix

4. Discussion

5. References 

## Problem Context 
Remote work has become a defining feature of modern employment, accelerated by global events such as the COVID-19 pandemic. As organizations continue to embrace flexible work arrangements, it is crucial to evaluate the effects of remote work on employee productivity and well-being. While some studies suggest increased efficiency and work-life balance, others highlight challenges such as isolation, burnout, and difficulties in collaboration. This analysis focuses on understanding the long-term implications of remote work on employee performance and mental health, using data-driven insights to inform policies and best practices. The challenges of remote work are complex due to its connected nature with other workplace factors. Digital transformation has changed communication dynamics [[1]](#1), while work-life balance concerns have gained prominence [[2]](#2). Different industries and job roles experience varying degrees of productivity shifts [[3]](#3). Understanding these dynamics requires an analysis incorporating technology, employee engagement, and organizational policies. The ability to work remotely impacts career growth, job satisfaction, and overall well-being, necessitating a comprehensive evaluation to ensure equitable and effective remote work policies. 

## Significance of the Study 
This analysis is timely and crucial for several reasons: 

1. Remote work adoption has increased significantly, yet its long-term productivity effects remain unclear [[4]](#4).

2. Employee well-being and mental health concerns are growing, particularly regarding work-life balance and isolation [[5]](#5).
   
3. Organizations are developing hybrid work models, necessitating data-driven insights to design effective policies [[6]](#6).

4. Technological advancements in virtual collaboration tools create opportunities to enhance productivity and engagement [[7]](#7). 



## Executive Summary
Remote work has become a fundamental aspect of modern employment, driven by technological advancements and global events such as the COVID-19 pandemic. While remote work offers flexibility and potential productivity gains, it also presents challenges related to employee well-being, collaboration, and organizational effectiveness. This study examines the long-term implications of remote work on productivity and mental health, using key datasets to inform best practices and policy recommendations. By analyzing global trends and key determinants of successful remote work models, this research aims to provide data-driven insights for organizations adapting to hybrid and remote work environments.

[Read detailed backgorund information here] (Background.md)

## Key Performance Indicators (KPIs)

1. **Employee Productivity Index (EPI)**
   - Measures changes in individual and team productivity before and after transitioning to remote work.
   - Target: 10% increase in task completion rates over a year.
   - Baseline: Pre-pandemic in office productivity levels.
  
2. **Work-Life Balance Score (WLBS)**
   - Evaluates employee satisfaction regarding their ability to maintain a balance between work and personal life.
   - Target: 80% of employees report a positive work-life balance.
   - Baseline: Current industry average of 65%.
  
3. **Employee Engagement Level (EEL)**
   - Measures motivation, job satisfaction, and overall engagement using survey data and company records.
   - Target: Maintain an engagement score of at least 70.
   - Baseline: Current company-wide average.
  
4. **Stress and Burnout Rate (SBR)**
   - Tracks the percentage of employees experiencing stress, burnout, or mental health challenges due to remote work.
   - Target: Reduce burnout rates to below 15%.
   - Baseline: Industry average of 25% burnout rate.
  
5. **Retention and Turnover Rates (RTR)**
   - Compares employee retention in remote, hybrid, and in-office work environments.
   - Target: Reduce voluntary turnover by 10% annually.
   - Baseline: Current company turnover rate.

DATA FOR TERM PROJECT MILESTONE 2:

Below are the visualizations for each of my 5 Key Performance Indicators, along with an interpretation of each visualization.

KPI #1: Employee Productivity
![Image](https://github.com/user-attachments/assets/1cc24c9c-3ee7-44e6-9f8d-cd89551b37a1)

![Image](https://github.com/user-attachments/assets/70102a89-13d4-48a1-8f56-64e738f16278)

In these visualizations, it shows a survey of 20 teams and their average employee productivity level on a scale of 0-100 in a pre remote work (office) environment and a post remote work (at home) environment. The orange bar displaying pre remote and blue displaying post remote work. Out of the data collected, results show that the average productivity level out of the 20 teams is higher in an in office environment rather than at home. The second visualization for this specific KPI is to display the total average without including the teams. The results showed that the participants of the survey gave an in office productivity score of 80.42 compared to a score of 77.41 for an at home environment. This means that employees are experiencing some possible distractions or less of a work drive when working remotely.

KPI #2: Work-Life Balance (WLB)
![Image](https://github.com/user-attachments/assets/28b7e45e-c625-4564-a2bc-227f0037f705)

In this visualization, I am comparing the average pre and post remote work work-life balance scores along with work satisfaction scores. The scores are based on a 0-100 scale and are divided into the different departments within the surveyed company. The results display that out of the 5 departments, pre remote WLB scores were higher than post remote work scores. The one outlier is in the IT department, which can be explained by the type of work IT specialists do, as they can primarily complete most of their work remotely. In terms of the work satisfaction scores, the results show that every department experienced a decrease in work satisfaction, with most scores decreasing by a range of 5-10 points.

KPI #3: Employee Engagement Level (EEL)
![Image](https://github.com/user-attachments/assets/b56a1fa6-b358-491e-9592-9bd7c3ba8cd0)

In this visualization, I am comparing the average employee engagement levels and work satisfaction scores based on the different job roles within the surveyed company. The results for the EEL vary across the different job roles, with 4 of the 5 roles having a decrease in engagement. This was expected based on the other visualizations as it seems employees are experiencing distractions in the remote workplace. The one outlier is again in the IT/specialist roles, as mentioned before, they can complete most of their workload remotely. As expected, job satisfaction also decreased in the post remote workspaces. The one outlier is in management roles, as this specific surveyed company felt they manage their duties better while working remotely. 

KPI #4: Stress & Burnout Rate
![Image](https://github.com/user-attachments/assets/03335737-5860-4cff-848c-45e15c75755e)

In this visualization, I am comparing the average pre and post remote stress and burnout rates, along with comparing them to the average weekly hours worked, while sorting them by job role. The results are interesting to see the stress and burnout levels increased exponentially by scores of 12 to 16. What makes these interesting is that it shows that employees are working 2-3 less hours a week, which you would think would help with stress. But looking at the other results of project, I can understand that these values may vary depending on the distractions and home life that different employees have, and that less work hours may not mean less "busy" hours at home.  

KPI #5: Retention and Turnover Rates
![Image](https://github.com/user-attachments/assets/34416b04-3364-4299-87ed-eb3bc33e7141)

In this visualization, I am evaluating the reasons why employees left their current jobs, and whether working in office, hybrid, or fully remote made a difference. This is all compared to the average tenured months with the company. The results are varied depending on the reason for the turnover so there is not a clear pattern. That being said, hybrid workers left primarily for better opportunties and management issues, in office workers for job insecurity and salary, and remote workers for job insecurity and management issues. On the right side of the graph, the retained employees are listed, with the highest retained group being hybrid workers, followed by in office, and then remote. Which could be used to interpret that remote employees, again, are not enjoying their remote work as much as in an office setting. 


DATA FOR TERM PROJECT MILESTONE 3 

Option 1

Chosen KPI: #5 Retention and Turnover Rate

CODE:

import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.ensemble import RandomForestClassifier
from sklearn.tree import plot_tree
from sklearn.metrics import accuracy_score, confusion_matrix, classification_report

# Load the dataset
rtr_df = pd.read_csv("Retention and Turnover Rates.csv")

# Define features and target
final_features = ["Job Satisfaction Score", "Tenure Months", "Turnover Reason"]
X = rtr_df[final_features]
y = rtr_df["Retention Status"]

# Split data
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# Train Random Forest model
rf_model = RandomForestClassifier(n_estimators=100, random_state=42)
rf_model.fit(X_train, y_train)

# Cross-validation accuracy
cv_scores = cross_val_score(rf_model, X, y, cv=5)
cv_mean_accuracy = cv_scores.mean()

# Predictions
y_pred = rf_model.predict(X_test)

# Evaluate model
accuracy_rf = accuracy_score(y_test, y_pred)
conf_matrix_rf = confusion_matrix(y_test, y_pred)
class_report_rf = classification_report(y_test, y_pred)

# Plot Decision Tree from Random Forest
plt.figure(figsize=(12, 8))
plot_tree(rf_model.estimators_[0], feature_names=final_features, class_names=["Left", "Retained"], filled=True, rounded=True)
plt.show()

# Plot Confusion Matrix Heatmap
plt.figure(figsize=(5, 4))
sns.heatmap(conf_matrix_rf, annot=True, fmt="d", cmap="Blues", xticklabels=["Left", "Retained"], yticklabels=["Left", "Retained"])
plt.xlabel("Predicted Label")
plt.ylabel("True Label")
plt.title("Confusion Matrix for Random Forest Model")
plt.show()

# Print Accuracy Metrics
print(f"Cross-Validation Accuracy: {cv_mean_accuracy:.4f}")
print(f"Test Set Accuracy: {accuracy_rf:.4f}")
print("Confusion Matrix:")
print(conf_matrix_rf)
print("Classification Report:")
print(class_report_rf)

RESULTS

Accuracy Measure: 99.5% Cross Validation

Decision Tree/Random Forest Plot 

![Image](https://github.com/user-attachments/assets/9747769e-967d-45e3-9f25-daee28724b6d)

Confusion Matrix: Displayed as a heatmap

![Image](https://github.com/user-attachments/assets/412520a8-6c4a-435f-bdee-40c79474f8d3)

## Discussion
To summarize the project, I began by finding datasets and information on remote work productivity which led to my creation of my 5 KPIs. These KPIs show all factors of remote work, such as the productivity and engagement levels, the work-life balance, and the stress/burnout rates along with retention rates. These factors all outline the different aspects of remote work, and why people enjoy it or not. I then graphed these KPIs in tableau to get a visual understanding of the relationships between the KPIs. Next, I chose Option 1 for the statistical analysis, which is the Decision Tree Based Prediction Model. I chose KPI #5, retention and turnover rate. With that, I created the decision tree and a confusion matrix displayed as a heatmap.

## References 

<a id="1">[1]</a> Microsoft. (2023). *Work Trend Index: Annual Report on Hybrid Work and Productivity*. [https://www.microsoft.com/work-trend-index](https://www.microsoft.com/work-trend-index).  

<a id="2">[2]</a> U.S. Bureau of Labor Statistics. (2023). *Telework and Productivity Data*. [https://www.bls.gov/](https://www.bls.gov/).  

<a id="3">[3]</a> Kaggle. (2023). *Remote Work and Productivity Dataset*. [https://www.kaggle.com/](https://www.kaggle.com/).  

<a id="4">[4]</a> Organisation for Economic Co-operation and Development (OECD). (2023). *Telework and Productivity Database*. [https://www.oecd.org/employment/telework-productivity/](https://www.oecd.org/employment/telework-productivity/).  

<a id="5">[5]</a> Gallup. (2023). *The State of the American Workplace: Remote Work and Productivity*. [https://www.gallup.com](https://www.gallup.com).  

<a id="6">[6]</a> McKinsey & Company. (2022). *The Future of Work: Remote Work and Employee Well-being*. [https://www.mckinsey.com](https://www.mckinsey.com).  

<a id="7">[7]</a> Forrester Research. (2022). *The Future of Remote Work: Trends and Best Practices*. [https://www.forrester.com](https://www.forrester.com).

