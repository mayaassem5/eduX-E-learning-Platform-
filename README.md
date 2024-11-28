# eduX-E-learning-Platform-
E-learning platforms aim to revolutionize the way people learn by
providing a personalized, interactive, and scalable solution for skill
development. This project brings together powerful data management
tools, data science, and modern cloud technologies to ensure a seamless
educational experience

## Our Mission
Our mission is to revolutionize how data supports e-learning. By focusing on effective customer data management, we aim to
create a system that tracks user behaviour, preferences, and engagement, allowing us to deliver highly personalized content.
Simultaneously, we empower platform administrators with detailed insights into user activities and trends.
We strive to maximize learning outcomes through data-driven decisions, turning raw data into actionable insights that enhance
both user experience and business performance.

---

## Phase 1: Data Management, SQL and Database Setup
**Database Design**
We designed a relational database using SQL Server that ensures reliable storage and retrieval of customer data, course content, and interaction history.
![image](https://github.com/user-attachments/assets/06cfc417-f63c-463a-972f-20e65fac30b8)

---

## Phase 2: Data Warehousing 
**Data Warehouse Implementation :**
  - Bus matrix
    To identify business processes and turn them into Data Marts.

  - Business Schema:
    Our data warehouse follows a dimensional model with fact tables (such as FactUserProgress) that record customer actions and dimension tables (e.g., DimUsers,  DimCourse, DimLesson) that provide detailed descriptions of each customer, course, or interaction so that we can apply CHURN analysis on it.

## Phase 2: ETL
**ETL Process with SSIS :**
  We designed and implemented an ETL (Extract, Transform, Load) process using SQL Server Integration Services (SSIS). This allowed us to extract data from the operational database and transform it into meaningful structures for analysis in the data warehouse.

## Phase 2: Python Programming
**o Python Programming :**
1- Data Load using SQL alchemy
2- Data Cleaning:
  - Checking Null Values in fact table.
  - table ‘ProgressStatus’ has 48 Null values.
  - replacing null values for status with ‘Not Started’.
3- EDA
4- extracting SQL queries for Future ML Phase:
  - User Progress Summary
  - Quiz Performance Analysis
  - Assignment Completion and Due Date Monitoring
  - Certificate Issuance Rates
  - Evaluation Score Distribution
  - User Engagement Insights
---

## Phase 3: Data Science
1- Data Analysis
2- Churn Analysis
3- ML Model:
  1- Churn Prediction Features
  2- Applied Models:
     - Logistic Regression Classifier
     - Random Forest Classifier
     - XG-Boost

---
## Phase 4: Deployment
o Inserting Data Manually :
![image](https://github.com/user-attachments/assets/f794fa72-8a7e-43a9-96d3-3060c3300995)

o Bulk Insert:
![image](https://github.com/user-attachments/assets/0681c8f2-2448-4ef7-9b29-d6360fedcb39)

---
## Future Work:
o Implementing the project completely on a cloud environment to ensure higher performance and scalability.

## Our Team:
  - Maya Assem - [LinkedIn](https://www.linkedin.com/in/maya-assem-611b4723b)
  - Fairouz Maher - [LinkedIn](https://www.linkedin.com/in/fairouz-ghazaly-76103227b/)
  - Amany Ahmed - [LinkedIn](https://www.linkedin.com/in/amany-ahmed-4ba22632b/)
  - Salma Mostafa - [LinkedIn](https://www.linkedin.com/in/sallmamostaffa/)
  - Mawada Abdelsalam - [LinkedIn](https://www.linkedin.com/in/mawada-a-salam-20a3b7274/)
