
# Global Mental Health Crisis

**Project Overview**

Title: The Invisible Enemy - Visualizing The Global Mental Health Crisis

Purpose:
This project aims to analyze and visualize the prevalence and trends of various mental health disorders worldwide using Tableau. The interactive dashboard allows stakeholders, policymakers, and healthcare providers to:

Identify regional mental health trends.

Compare disorder prevalence across time and geography.

Understand correlations between disorders.

Extract actionable insights for global mental health policies.

**Target Audience:**

Public health organizations (WHO, CDC)

Mental health policymakers and NGOs

Data analysts in healthcare

Researchers and scholars in mental health studies



## Issues in the Original Dataset & Cleaning Process

**Issues Found in the Raw Dataset:**

Inconsistent Data Types - Some disorder percentage columns had mixed data types (numbers & strings), causing calculation issues.

Missing Values - several disorder columns (e.g., Schizophrenia, Bipolar Disorder, Anxiety Disorders) had missing values.

Year Format Issue - The "Year" column was stored as a string instead of a numeric format.

Unnecessary Index Column - A redundant "Index" column was present in the dataset.

✅ **Data Cleaning Steps Taken**

Converted "Year" to a numeric format to allow for trend analysis.

Fixed numeric columns by converting all disorder percentages to a uniform float format.

Handled missing values using column averages for a balanced dataset.

Removed the unnecessary index column to clean the structure.

Mapped "Entity" to a Geographic Role to enable Tableau's world map visualization.

📌 The cleaned dataset is now included in this GitHub repository!




## Data Summary

**Dataset Used:**

Name: Global Mental Disorder Dataset

**Key Attributes:**

Entity - Country Name

Year - Year of data collection

Schizophrenia (%) - Percentage of population affected

Bipolar disorder (%)

Eating disorders (%)

Anxiety disorders (%)

Drug use disorders (%)

Depression (%)

Alcohol use disorders (%)

## Key Insights from the Dashboard

🌍 **1. Global Distribution of Mental Health Disorders (Map Visualization)**

Countries with high schizophrenia rates: Russia, USA, India.

Countries with high depression rates: Brazil, UK, Canada.

Mental health disorders are more prevalent in high-population regions.

📈 **2. Trends Over Time (Line Chart Visualization)**

Depression rates increased globally from 1990 to 2020.

Anxiety disorders showed a steep rise post-2005.

Schizophrenia rates remained relatively stable over time.

Drug and alcohol use disorders spiked in Western countries after 2010.

🔥 **3. Correlations Between Disorders (Heatmap Visualization)**

Strong correlation between anxiety and depression.

Bipolar disorder often coexists with schizophrenia.

Drug and alcohol abuse disorders are linked, especially in North America and Europe.

📊 **4. Country Comparisons (Bar Chart Visualization)**

Top 3 countries for Depression: USA, Brazil, UK.

Top 3 countries for Schizophrenia: Russia, India, China.

Countries with the lowest disorder rates: Some African and Middle Eastern nations.

## Dashboard Features

🔹 **Interactivity**

✅ Drop-down filter to select disorder type.

✅ Year filter to analyze trends over time.

✅ Country selection for specific regional insights.

✅ Hover tooltips with additional data.

🛠️ **Visualizations Used**

✅ Choropleth Map: Displays global disorder distribution.

✅ Line Chart: Shows mental health disorder trends over years.

✅ Heatmap: Correlation between different disorders.

✅ Bar Chart: Ranks countries based on disorder prevalence.


## Screenshots

![Dashboard](https://github.com/SrivarReddy/Srivar-AI-SA-4/blob/457f6fdce9fc1ed2d4deebc396b0553b3c842750/image_2025-02-28_233050403.png)

![Sheet1](https://github.com/SrivarReddy/Srivar-AI-SA-4/blob/f78cb47a8671ed7343487016f880a5e96cd4752d/image_2025-02-28_233253071.png)

![Sheet2](https://github.com/SrivarReddy/Srivar-AI-SA-4/blob/5de277a4de8dbd6e08e4cc4cde8ed23442145825/image_2025-02-28_233438753.png)

![Sheet3](https://github.com/SrivarReddy/Srivar-AI-SA-4/blob/3cd035e2d5074a61c898ca8469016efdf363354b/image_2025-02-28_233827667.png)

![Sheet4](https://github.com/SrivarReddy/Srivar-AI-SA-4/blob/1b2913cb6f5e0841e48d9739be71175ec27f48ba/image_2025-02-28_233945172.png)

## Conclusion & Recommendations

📌 **Key Takeaways**

Depression & Anxiety disorders are increasing globally and require immediate attention.
Alcohol and Drug use disorders are highest in developed nations due to lifestyle factors.
Countries with rising disorder rates need more mental health awareness and funding.

📌 **Future Improvements**

Incorporate socio-economic data to analyze disorder causes.
Use machine learning models for better predictive analysis.
Expand dataset with real-time mental health reports