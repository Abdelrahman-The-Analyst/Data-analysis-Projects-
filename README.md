Project Overview This project involves an end-to-end data analysis of a healthcare organization's community camps. The goal was to understand patient behavior, identify high-performing camp categories, and uncover geographical and demographic insights to improve attendance rates.

🛠 Tech Stack Language: SQL (MySQL)

Concepts: Data Cleaning, Joins, Subqueries, CTEs, Window Functions, and Exploratory Data Analysis (EDA).

📂 Database Schema The analysis was performed on 5 main tables:

Train: Registration details.

Health Camp Detail: Metadata about camp types and dates.

Patient Profile: Demographic info (Age, Income, Education, City).

Attendance Tables (1st, 2nd, 3rd): Records of actual attendance across different camp formats.

📊 Key Insights (The "Executive Summary") 1️⃣ Success Rates by Category Category 3 camps achieved the highest conversion rate (56.34%).

Category 1 showed significant data gaps initially but was recovered and analyzed to show a steady baseline.

2️⃣ The Ideal Patient Profile Location: City B is the most engaged geographical segment.

Behavior: Patients who register 7–30 days before the event have the highest attendance probability compared to "Last Minute" or "Early Bird" registrants.

3️⃣ Patient Loyalty A strong core of "Super-Users" was identified—patients who attended all 3 types of camps. Some patients attended more than 8 events in total, suggesting high trust in the healthcare provider.

4️⃣ Data Quality Issues Identified a critical issue where over 5,000 records lacked City_Type data. This insight led to a recommendation for improving the CRM data entry process.

🚀 How to Run the Analysis Import the .csv datasets into your MySQL Workbench.

Run the Cleaning_and_Joins.sql to prepare the master view.

Execute the Analysis_Queries.sql to generate the KPIs.

💡 Recommendations Strategic Shift: Focus marketing spend on City B and Category 3 camp formats.

Retention: Launch a loyalty program for the identified "Super-User" segment.

Data Governance: Make "City Type" a mandatory field in the registration portal.
