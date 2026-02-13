# US Online Community: Customer Behavior & Engagement Analysis
**Strategic Tenure-Based Segmentation and Review Sentiment Visualization using R**

## 📌 Project Overview
This project performs a comprehensive analysis of user engagement within a US-based online community. By utilising **R programming**, I segmented the user base into three distinct cohorts— **Veteran, Intermediate, and New**—to identify how community loyalty correlates with review behavior and rating patterns.

The analysis focuses on uncovering the relationship between a user's length of membership and their propensity to contribute high-quality feedback to the platform.

## 🎯 Project Objectives
The primary goal was to transform raw community data into actionable insights regarding user lifecycle management:

**Logic-Based Grouping**: Categorized users into three cohorts based on their "Member Since" date:
-  Veteran: Joined before 2017.
-  Intermediate: Joined between 2017–2022.
-  New: Joined after 2022.

**Quantitative Analytics**: Calculated critical engagement KPIs for each segment, including:
-  Total number of users per group.
-  Average review stars (sentiment).
-  Average number of reviews per user (engagement density).


**Data Visualisation**: Produced high-impact visuals to compare sentiment (Average Stars) across the different user groups to identify trends in community satisfaction.

## 🛠 Technologies Used
**Language**: R Programming. <br />
**Data Manipulation**: tidyverse (specifically dplyr and tidyr). <br />
**Visualisation**: ggplot2 for professional-grade statistical graphics. <br />
**Environment**: RStudio. <br />

## 🚀 How to Run the Project
**1. Clone the Repository:** <br />
To run this analysis locally, use the following commands in your terminal: <br />
git clone https://github.com/damian2551/Data-Science-and-Analysis_Customer-Engagement/tree/master  <br />

**2. Install Required Packages:** <br />
Open RStudio and run: <br />
install.packages(c("tidyverse", "ggplot2", "lubridate"))

**3. Execute the Script:** <br />
Run the analysis script to generate the summary tables and visualisations. <br />

## 📊 Impact & Insights
This analysis provides a blueprint for community managers to understand their "power users" (Veterans) versus those in the "onboarding phase" (New users).
- **Engagement Tracking**: By calculating reviews per user, the system identifies which group drives the most content.  <br />
- **Sentiment Benchmarking**: Visualizing average stars across groups helps detect if newer users are having a significantly different experience than long-term members.  <br />
- **Strategic Alignment**: These insights mirror my previous successes in optimizing budget allocation by 20% and improving reporting accuracy by 14% through rigorous data auditing.

## 🔮 Future Improvements
- **Predictive Modeling**: Implement a Supervised Learning model (Decision Tree or Regression) to predict user churn, similar to my 93% accurate Kidney Disease project.
- **Natural Language Processing (NLP)**: Use R's tidytext package to perform sentiment analysis on the actual review text for deeper qualitative insights.
- **Interactive Deployment**: Transform the static R script into an interactive Shiny Web Application for real-time stakeholder reporting.

## 👤 About the Author
**Damian Nguyen**  Data Professional | Master of Information and Communications Technology (Data Analytics, Cloud Computing)  <br />
- **Location**: Sydney, Australia. <br />
- **LinkedIn**: https://www.linkedin.com/in/damian205051/ <br />
