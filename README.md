# Telecom Churn

This dataset contains information about US Telecom customers. Each row represents a customer. The dataset has the following variables in the columns:

- **state**: code of the US state of customer residence  
- **account length**: number of months the customer has been with the current telco provider  
- **area code**  
- **international plan**: the customer has an international plan (Yes=1)  
- **voice mail plan**: the customer has a voice-mail plan (Yes=1)  
- **number vmail messages**: number of voice-mail messages  
- **total day minutes**: total minutes of calls during the day  
- **total day calls**: total number of calls during the day  
- **total day charge**: total charge of day charge  
- **total eve minutes**: total minutes of calls during the evening  
- **total eve calls**: total number of calls during the evening  
- **total eve charge**: total charge of evening charge  
- **total night minutes**: total minutes of calls during the night  
- **total night calls**: total number of calls during the night  
- **total night charge**: total charge of night charge  
- **total intl minutes**: total minutes of international calls  
- **total intl calls**: total number of international calls  
- **total intl charge**: total charge of international charge  
- **number customer service calls**: number of calls to customer service  
- **churn**: customer changed telco provider (Yes=1)  

Telecom wants to understand what customers are more likely to churn (change provider), according to the available covariates so that it can target these customers with an ad-hoc promotional campaign.

## Tasks

1. **Build a classification model** to help Telecom in targeting the willing-to-churn customers before it is too late.  
2. **Cluster customers** according to their behavior.

# What did I practically do?

During the **Data Analysis for Business** course, I worked on a project that involved applying various data analysis techniques, including **regression**, **binary classification**, and **clustering**. The goal was to develop a meaningful analysis with practical implications, such as providing marketing insights or policy recommendations.

## **Project Development Steps**  

### **1. Dataset Selection and Exploration**  
I selected a dataset that was suitable for both a **classification** task and a potential **clustering** analysis. The dataset was examined in terms of its size, feature distribution, and missing values. I performed **data cleaning**, which included handling duplicates, missing values, and unnecessary variables. Additionally, I conducted **descriptive statistics** and visualized key relationships to gain a better understanding of the data.  

### **2. Task 1: Classification Model**  
The primary objective (Task 1) was to build a **classification model** to predict a binary outcome. I explored how this prediction could provide valuable insights for business decisions.  

#### **2.1. Initial Analysis and Feature Selection**  
Before building the full model, I investigated lower-dimensional models using a subset of key variables to identify interesting relationships.  

#### **2.2. Model Development and Evaluation**  
I split the dataset into **training and test sets** and applied various modeling techniques, including:  
- **Linear models** (AIC/BIC stepwise selection)  
- **Penalized approaches** (Ridge, Lasso, Elastic Net)  
- **Non-linear models** (k-NN, splines, GAM, tree-based algorithms)  

I compared these models using appropriate **validation techniques** and selected the best-performing model. The final model was evaluated using various **performance metrics**, and I analyzed the significance of the selected features and relationships.  

### **3. Task 2: Clustering Analysis (Optional Task)**  
As the dataset was suitable for clustering, I performed an additional analysis to segment customers based on their behavior.  

#### **3.1. Cluster Analysis Methods**  
I compared **K-Means** and **Hierarchical Clustering** to determine the best approach. The optimal number of clusters was selected using techniques such as:  
- **Within-Cluster Sum of Squares (WSS)**  
- **Silhouette Score**  
- **Gap Statistic**  

I visualized the resulting clusters in a **lower-dimensional space** and, if possible, compared them with external labels not included in the clustering process.  

### **4. Report and Code Submission**  
To document my findings, I prepared a **report** summarizing the most relevant analyses, visualizations, and conclusions. The report included:  
- Key results from the classification and clustering models  
- Comparisons between different modeling approaches  
- Practical insights derived from the analysis  

I also submitted the **R code** used for the analysis, ensuring it was well-documented for clarity.  

## **Conclusion**  
This project allowed me to apply a variety of **statistical and machine learning techniques** to solve a real-world business problem. By combining predictive modeling and clustering, I was able to provide valuable insights that could help businesses make data-driven decisions.