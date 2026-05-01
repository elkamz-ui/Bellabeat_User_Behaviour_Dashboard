# Bellabeat User Behavior Analysis Dashboard

## Project Overview
This project analyzes smart device fitness data to unlock new growth opportunities for Bellabeat, a high-tech manufacturer of health-focused products for women. By analyzing consumer usage of non-Bellabeat smart devices, I identified trends in activity, sleep, and consistency to provide actionable marketing recommendations.

## Tech Stack
*   **Data Cleaning:** Python (Pandas)
*   **Data Transformation:** Power Query (M Language)
*   **Data Modeling:** DAX (Power BI)
*   **Visualization:** Power BI Desktop

## Key Insights
*   **User Consistency:** Activity levels significantly drop on Sundays, suggesting an opportunity for "weekend motivation" notifications.
*   **The Sleep Gap:** There is a weak correlation between steps and sleep duration, indicating that higher physical activity doesn't always lead to longer sleep.
*   **Sedentary Habits:** 64.4% of users are either sedentary or only very active, with a lack of "moderate" consistency.

## Dashboard Preview
### 1. Overview & Key Metrics
![Dashboard Overview](/Images/BB1.png)

### 2. Activity Analysis
![Activity Analysis](/Images/BB2.png)

### 3. Sleep & Behavior Trends
![Sleep Analysis](/Images/BB3.png)
![Behavior Trends](/Images/BB4.png)

## Data Pipeline
1.  **Preprocessing:** Used Python/Pandas to handle missing values, formatting, and initial data merging.
2.  **Schema Design:** Implemented a Star Schema in Power BI for optimized performance.
3.  **Advanced DAX:** Created measures for Moving Averages, Consistency percentages, and dynamic sorting for chronological Day of Week reporting.

## How to View
*   Clone this repository.
*   Open the `.pbix` file in Power BI Desktop.
