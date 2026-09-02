# End to End Customer Behavior Analysis

## 📌 The Business Problem
The goal of this project is to analyze customer shopping behavior using transactional data from 3,900 purchases across various product categories. The objective is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions and optimize marketing strategies.

## 💡 Key Insights
*   **Customer Loyalty is High:** A significant majority of the customer base (3,116 out of 3,900) falls into the "Loyal" segment, having made more than 10 previous purchases. 
*   **Age and Revenue:** The "Young Adult" demographic contributed the highest total revenue ($62,143), closely followed by "Middle-aged" customers ($59,197).
*   **Subscription Opportunity:** While non-subscribers generate more total revenue ($170,436), they make up 73% of the customer base. Converting repeat buyers (over 5 purchases), where 2,518 are currently not subscribed, presents a major growth opportunity.
*   **Shipping Preferences:** Average purchase amounts remain consistent regardless of shipping speed, with Express shipping averaging $60.48 and Standard averaging $58.46.

## 📊 Interactive Dashboard
![Customer Behavior Dashboard](dashboards/Screenshot_2026-09-02_232624.png)

## 🛠️ Tools Used
*   **Python (Pandas & SQLAlchemy):** Data cleaning, missing value imputation, and database integration.
*   **PostgreSQL:** Advanced data querying, window functions, and customer segmentation.
*   **Power BI:** Data visualization and interactive dashboard creation.

## 📂 Repository Structure
*   `/notebooks`: Jupyter notebooks containing data cleaning and EDA.
*   `/sql_queries`: SQL scripts used for answering business questions.
*   `/dashboards`: Power BI file (.pbix) and static dashboard images.
*   `/presentation`: Final client-ready PDF presentation.
