# SQL-poject
SQL scripts for database creation, queries, and analysis on  ScienceQtech Employee Database Management for Performance Review.

Project Title: ScienceQtech Employee Database Management for Performance Review

Overview:
ScienceQtech, a startup specializing in data science, has tasked its HR department with analyzing employee performance in preparation for their annual appraisal cycle. As the Junior Database Administrator, your role is to manage the employee database and extract key insights on employee performance, project assignments, and departmental ratings to support the performance mapping and compensation processes.

Objective:
The main objective is to ensure comprehensive analysis of employee records to assist in performance evaluation and salary adjustments. This includes generating reports on employee details, calculating bonuses based on performance, and ensuring employees are aligned with organizational standards. The project also focuses on optimizing database queries for performance improvements.

Tasks Performed:
1. Data Import and Database Setup:
   - Create a database named `employee`.
   - Import `emp_record_table`, `portable`, and `data_science_team` CSV datasets into the database.

2. ER Diagram Creation:
   - Develop an Entity Relationship (ER) diagram for visualizing relationships between employees and projects.

3. Data Querying:
   - Extract employee details including department information, rating-based filters, and concatenated employee names.
   - Perform advanced queries to identify employees with subordinates, list employees from specific departments, and rank employees based on experience.

4. Performance Evaluation:
   - Calculate maximum and minimum salaries per role.
   - Group employee performance ratings by department and identify maximum ratings within each department.

5. View Creation and Advanced Queries:
   - Create views and procedures to analyze employees with experience greater than 10 years and generate salary reports.
   - Use stored functions to evaluate employee profiles against organizational standards (junior, associate, senior data scientist, etc.).

6. Optimization and Performance:
   - Create an index to improve query performance, particularly for frequently accessed fields like employee names.
   - Analyze and optimize the query execution plan for efficiency.

7. Bonus Calculation and Financial Reports:
   - Calculate employee bonuses based on salary and performance ratings.
   - Generate reports for average salary distributions across different continents and countries.

Outcomes:
- Enhanced Employee Performance Evaluation: The system provides a streamlined view of employee ratings, departmental contributions, and salary adjustments based on predefined criteria.
- Cost and Performance Optimization: Indexing and query optimization reduce execution time, enhancing system performance.
- Comprehensive HR Insights: HR and management can easily identify high-performing employees, calculate bonuses, and manage project assignments for better organizational efficiency.


