# Data-Analysis-Project-1

# Bellabeat Fitness Data Analysis

## Project Overview
This project analyzes Fitbit smart device usage data to identify trends in user activity, sedentary behavior, and fitness goal achievement. The insights are used to inform marketing strategies for Bellabeat, a health-focused wearable technology company.

---

## Business Task
Analyze smart device usage data to understand how consumers use fitness trackers and how these insights can guide Bellabeat’s marketing strategy.

---

## Dataset
- Source: Fitbit Fitness Tracker Data (Kaggle)
- Time period: March–May 2016
- Data type: Daily activity tracking data

---

## Tools Used
- Excel
  - Data cleaning
  - PivotTables
  - Data visualization

---

## Data Cleaning & Preparation
- Selected relevant daily-level dataset (`dailyActivity_merged`)
- Combined multiple time periods into a single dataset
- Removed duplicate records based on user ID and date
- Checked for missing values using filtering methods
- Created new features:
  - **Weekday** (derived from date)
  - **Active Minutes** (sum of lightly, fairly, and very active minutes)
- Excluded minute-level and hourly datasets due to excessive granularity

---

## Key Findings

### 1. Low consistency in meeting activity goals
- Only **31% of tracked days** reached the 10,000-step goal  
- Indicates most users do not consistently meet recommended activity levels

### 2. High sedentary behavior
- Average active minutes: **218 minutes/day**  
- Average sedentary minutes: **~993 minutes/day**  
- Users spend the majority of their day inactive

### 3. Activity varies by day of week
- Highest activity observed on **Saturday**
- Lowest activity observed on **Sunday**
- Suggests inconsistent weekly activity patterns

### 4. Moderate relationship between steps and calories
- Correlation ≈ **0.59**
- More steps generally lead to more calories burned, but other factors also contribute

---

## Recommendations (Bellabeat Leaf)

Based on the insights, the following strategies are recommended for the **Bellabeat Leaf** product:

- Promote **personalized daily activity goals** instead of a fixed 10,000-step target
- Introduce **inactivity reminders** to reduce prolonged sedentary behavior
- Launch **weekend activity challenges** to encourage consistent engagement
- Emphasize **small, achievable lifestyle changes** in marketing messaging

---

## Limitations
- Dataset is not specific to Bellabeat users
- Sample size is limited and may not represent all user groups
- Data does not include demographic segmentation relevant to Bellabeat’s target audience

---

## Visualizations
Charts created in Excel include:
- Average steps by day of week
- Active vs sedentary minutes
- Steps vs calories correlation
- Percentage of users reaching 10,000 steps

(Screenshots can be found in the `/images` folder)

---

## 📌 Conclusion
This analysis shows that while users engage with fitness tracking devices, most struggle to maintain consistent activity levels. Bellabeat can leverage these insights to position its products as tools that support sustainable, everyday wellness habits rather than rigid fitness goals.
