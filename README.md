**Project Title:** Using WebGoat to Test Web Applications for SQL Injection Vulnerabilities
**Project Overview:** This project demonstrates practical testing of web application vulnerabilities using OWASP WebGoat, a deliberately insecure web application maintained by OWASP.The focus of this project is on identifying, exploiting, and understanding SQL Injection (SQLi) vulnerabilities and their impact on web applications.
**Objectives:** Understand SQL and its command types (DML, DDL, DCL),
            Perform SQL Injection attacks in a controlled environment,
            Exploit string-based and numeric SQL injection vulnerabilities,
            Modify database records and schema,
            Understand the impact of SQLi on the CIA Triad,
            Learn prevention techniques for SQL Injection
**Types of SQL Commands used:** DML (Data Manipulation Language) =>  SELECT – Retrieve data, INSERT – Add new records, UPDATE – Modify existing records, DELETE – Remove records
                                DDL (Data Definition Language) => CREATE – Create database/tables, ALTER – Modify table structure, DROP – Delete tables/databases
                                DCL (Data Control Language) => GRANT – Provide access permissions, REVOKE – Remove access permissions
**SQL Injection:** SQL Injection (SQLi) is a web security vulnerability that allows attackers to manipulate database queries by injecting malicious SQL code into input fields.
**Consequences of SQL Injection:** Loss of Confidentiality, Loss of Integrity, Loss of Availability, Privilege Escalation, Authentication Bypass
**Practical Tasks Performed:** 
Task 1: Retrieve Employee Department => Retrieved department of Bob Franco, Result: Bob works in Marketing

Task 2: Modify Employee Department => Changed Tobi Barnett’s department to Sales

Task 3: Modify Database Schema => Added new column phone varchar(20) to employees table

Task 4: Grant Privileges => Granted rights to unauthorized_user

Task 5: String SQL Injection => Used ' OR '1'='1 to retrieve all user records

Task 6: Numeric SQL Injection => Used 0 OR 1=1 to retrieve complete table data

Task 7: Retrieve All Employees => Used authentication bypass to extract full employee data

Task 8: Modify Salary => Updated salary using query chaining

Task 9: Delete Logs => Dropped access_log table to remove evidence
**Tools Used:** OWASP WebGoat, SQL Queries, Local Web Application Environment
**Key Learnings:** Real-world impact of SQL Injection vulnerabilities, How improper input validation leads to database compromise, Importance of secure coding practices, Practical understanding of database exploitation
