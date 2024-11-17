# SQL-PROJECT-
HR DATABASE MANAGEMENT SYSTEM
Overview
This project demonstrates comprehensive SQL skills through an HR Database Management System that includes seven interconnected tables. It addresses diverse business queries and challenges using structured SQL commands, advanced queries, and data analysis techniques.

Key Tables:
Employees: Employee data, including names, salaries, and job roles.
Jobs: Job titles and salary ranges.
Departments: Organizational departments and their locations.
Dependents: Information about employee dependents.
Locations: Geographical data for company departments.
Countries: Countries where the company operates.
Regions: Regional classification for countries.
Features and Highlights
1. Data Querying and Analysis
Basic SELECT Queries: Extracted key data points such as employee names, job titles, and salaries.
Data Filtering: Implemented WHERE, ORDER BY, and DISTINCT clauses to filter and sort data for specific insights.
TOP N Queries: Retrieved prioritized data, such as employees with the highest salaries.
2. Data Relationships and Joins
Inner Joins: Connected tables to retrieve employee details alongside job and department information.
Left Joins: Found countries without department locations.
Self-Joins: Analyzed hierarchical reporting structures within the organization.
3. Advanced SQL Techniques
Aggregations and Grouping: Used GROUP BY and aggregate functions (SUM, AVG, COUNT) to analyze department-wise salaries and headcounts.
Subqueries: Enhanced query efficiency and clarity by embedding subqueries for filtering and data retrieval.
Case Statements: Implemented conditional logic for categorizing employees based on salary ranges.
Foreign Keys and Constraints: Enforced data integrity across tables.
4. Problem Solving and Insights
Identified employees who joined within specific timeframes.
Retrieved departments with salaries exceeding specific thresholds.
Listed employees who lacked dependents or phone numbers.
Technologies and Tools
SQL Server Management Studio (SSMS): Primary platform for database creation, data manipulation, and queries.
Structured Query Language (SQL): Utilized to build, query, and manage the relational database.


Retrieve employees earning more than $10,000 sorted by salary
Repository Structure
SQL Scripts: Contains table creation, data insertion, and solution scripts for all project tasks.
Documentation: Detailed explanation of tasks, solutions, and insights derived from the database.
Create tables.
Insert sample data.
Run queries and explore the results.
Future Enhancements
Integration with a front-end dashboard for visualizing query outputs.
Expanding the dataset with real-world HR records.
Feel free to fork this repository and contribute! 😊
