# data-base-project
The Gym Management System is a MySQL database project designed to organize and manage gym staff, trainees, and memberships.

# Project Objectives
- Organize gym information in a structured database.
- Manage staff and trainee records.
- Track membership types and expiration dates.
- Retrieve useful information using SQL queries.

# Database Structure
The database consists of four main tables:

- **Staff:** Stores staff information, including names, phone numbers, emails, and salaries.
- **Membership:** Stores membership types, durations, start dates, expiration dates, and associated staff IDs.
- **Trainee:** Stores trainee information, including names, contact details, dates of birth, height, weight, and membership IDs.
- **Interacts:** Connects staff members with trainees.

# SQL Operations
The project demonstrates several SQL operations:

- Creating and modifying database tables.
- Inserting sample records.
- Retrieving and filtering data using `SELECT` and `WHERE`.
- Calculating average and total salaries using aggregate functions.
- Counting trainees assigned to each staff member.
- Combining related data using `JOIN`.
- Using subqueries to compare trainee weights with the average weight.
- Creating a database view to display trainee and membership information.

# Technologies Used
- **Database:** MySQL

# GALYM SEL fitness.pdf
The `schema.sql` file contains all SQL statements required to create the database, define its tables and relationships, insert sample data, execute queries, and create the `trainee_membership_view`.

# Key Features
- Automatic ID generation.
- Primary and foreign key relationships.
- Data validation using constraints.
- Unique email addresses and trainee phone numbers.
- Membership date validation.
- Data analysis using SQL queries and views.

# Future Improvements
- Add membership payment tracking.
- Include trainee attendance records.
- Manage workout plans and fitness progress.
- Generate monthly membership and revenue reports.

# 👩‍💻 Team Members
* Sahar Hawsawi [linkedin profile](https://www.linkedin.com/in/sahar-hawsawi-4133aa361)
* Safaa Sobh [linkedin profile](https://www.linkedin.com/in/safaa-sobh-7b795a363)
* Layan Alshreef [linkedin profile](https://www.linkedin.com/in/layan-alshareef-909006365)
* Elham Alzahrani [linkedin profile](https://www.linkedin.com/in/elham-alzahrani-791014246)
