# Market Basket Analysis & Customer Behavior Analytics using Python – Amazon

## 1. Project Overview

This project simulates a real-world business scenario where you are hired as a Customer Insights Analyst at Amazon. The leadership team seeks data-driven insights into customer purchasing behavior, product affinities, recommendation effectiveness, and satisfaction trends to optimize personalization, marketing strategies, and inventory planning 

C6_Project_Market Basket Analys…

.

The primary focus is to:

Understand which products/categories are frequently purchased together (cross-selling opportunities).

Analyze customer demographics and behavioral trends.

Segment customers based on buying patterns and satisfaction.

Evaluate recommendation systems and review impact.

Provide actionable business insights supported by data analysis and visualizations.

## 2. Business Objective

The core objective is to build a Customer Purchasing Behavior and Product Recommendation Report using Python-based data analytics techniques 

C6_Project_Market Basket Analys…

.

The analysis should:

Clean and prepare transaction/survey data.

Apply Market Basket Analysis and association rule mining.

Perform customer segmentation using clustering techniques.

Evaluate recommendation effectiveness.

Generate insights for:

Personalized promotions

Inventory optimization

Customer retention strategies

Revenue enhancement

## 3. Dataset Description

The dataset used is Amazon Customer Behaviour Survey, containing customer-level responses about online shopping habits 

C6_Project_Market Basket Analys…

.

Key Data Dimensions:
### A. Demographics

Age

Gender

### B. Purchase Behavior

Purchase Frequency

Purchase Categories

Browsing Frequency

Add to Cart Behavior

Cart Completion Frequency

Cart Abandonment Factors

Save for Later Frequency

### C. Product Search Behavior

Product_Search_Method

Search_Result_Exploration

### D. Reviews & Recommendations

Customer_Reviews_Importance (1–5 scale)

Review_Reliability

Review_Helpfulness

Review_Left (Yes/No)

Personalized_Recommendation_Frequency

Recommendation_Helpfulness

### E. Satisfaction & Rating Metrics

Rating_Accuracy (1–5 scale)

Shopping_Satisfaction (1–5 scale)

### F. Service Feedback

Service_Appreciation

Improvement_Areas

The dataset contains structured survey responses, requiring preprocessing before analysis.

## 4. Technical Tasks & Analytical Workflow
### Task 1: Data Cleaning & Preparation (10 Marks)

Data preprocessing ensures analytical accuracy. The following operations are required 

C6_Project_Market Basket Analys…

:

Remove duplicate and inconsistent survey responses.

Standardize categorical fields (e.g., frequency levels, gender labels).

Handle missing values in search methods and other columns.

Rename duplicate/misformatted columns (e.g., trailing spaces in Rating_Accuracy).

Convert rating columns to numeric types.

Outcome: Clean, structured dataset ready for analysis.

### Task 2: Descriptive Behavioral Analysis (20 Marks)

This stage focuses on exploratory data analysis (EDA):

Demographic distribution (age groups, gender ratio).

Purchase frequency trends.

Most popular product categories.

Most common browsing/search methods.

Major cart abandonment reasons.

Mean/median of:

Shopping satisfaction

Recommendation helpfulness

Rating accuracy

Visualizations (bar charts, pie charts, distribution plots) summarize patterns.

Outcome: Baseline behavioral insights and trend identification.

### Task 3: Customer Segmentation & Profiling (20 Marks)

This stage moves into analytical modeling.

#### A. Rule-Based Segmentation

Create defined customer groups such as:

Frequent Buyers → High frequency + high satisfaction

Occasional Shoppers → Moderate frequency

At-Risk Customers → Low satisfaction or high cart abandonment

#### B. Clustering (K-Means)

Apply clustering algorithms to group customers based on:

Purchase frequency

Satisfaction levels

Review engagement

Recommendation interaction

Analyze demographic and behavioral differences between clusters.

Outcome: Customer personas for targeted marketing strategies.

### Task 4: Recommendation & Review Analysis (10 Marks)

This section evaluates Amazon’s recommendation ecosystem:

Correlation between recommendation helpfulness and satisfaction.

Impact of review reliability on rating accuracy.

Trends in personalized recommendation engagement.

Trust level in Amazon’s recommendation engine.

Outcome: Data-backed improvement strategies for recommendation algorithms.

### Task 5: Visualization & Reporting (10 Marks)

Create a structured analytical dashboard/report including:

Purchase category distribution

Browsing frequency trends

Satisfaction distribution

Correlation heatmaps

Recommendation vs satisfaction relationship

The final report must be visually appealing and insight-driven 

C6_Project_Market Basket Analys…

.

### Task 6: Video Presentation (20 Marks)

Deliver a 5-minute analytical presentation explaining:

Key behavioral drivers

Revenue risks (e.g., cart abandonment)

Segmentation logic

Strategic recommendations

The video must:

Be original

Not AI-scripted

Use charts from analysis as evidence 

C6_Project_Market Basket Analys…

## 5. Analytical Techniques Used

The project integrates multiple analytical domains:

### ✔ Data Cleaning & Preprocessing

Pandas, NumPy, missing value treatment, feature engineering.

### ✔ Exploratory Data Analysis

Descriptive statistics, visualization libraries (Matplotlib, Seaborn).

### ✔ Market Basket Analysis

Association Rule Mining

Support, Confidence, Lift

Product affinity identification

### ✔ Customer Segmentation

K-Means Clustering

Behavioral grouping

Profile-based classification

### ✔ Correlation & Statistical Analysis

Pearson correlation

Cross-tab analysis

Trend identification

## 6. Business Impact & Strategic Value

This project helps Amazon leadership:

### 1. Improve Cross-Selling

Identify product bundles frequently purchased together.

### 2. Enhance Personalization

Segment-based recommendations improve CTR and conversion.

### 3. Reduce Cart Abandonment

Analyze abandonment factors to reduce revenue leakage.

### 4. Strengthen Review Trust

Understand how review reliability affects satisfaction.

### 5. Optimize Inventory

Demand prediction based on category popularity and frequency trends.

## 7. Deliverables

As per submission guidelines 

C6_Project_Market Basket Analys…

:

Python code file

Insight summary PDF

5-minute video presentation

Zipped folder submission

Evaluation is based on:

Analytical depth

Visualization quality

Insight clarity

Recommendation feasibility

Adherence to instructions

## 8. Project Complexity Level

This is an intermediate-to-advanced data analytics project because it combines:

Data preprocessing

Behavioral analytics

Clustering techniques

Association rule mining

Business strategy interpretation

It bridges data science, business analytics, and marketing intelligence.

## 9. Final Summary

This project demonstrates how structured survey data can be transformed into actionable business intelligence through:

Market Basket Analysis

Customer Segmentation

Behavioral Trend Analysis

Recommendation System Evaluation

It replicates real-world e-commerce analytics challenges and delivers strategic, measurable, and data-backed recommendations for improving customer experience and revenue growth.
