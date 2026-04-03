# sql_project

# 🎓 University Database System

## About this project
This is a simple university database I built using MySQL to understand how real systems manage data like students, courses, departments, and instructors.

Instead of just writing queries, I tried to design it like an actual system — with proper relationships, constraints, and structured data.

## What’s inside

The database includes:

- Students with their basic details and program
- Programs linked to departments  
- Courses with credits
- Instructors with workload info

To handle real-world relationships, I also created:
- student_course → which student is taking which course  
- program_course → which course belongs to which program  
- instructor_teaches → which instructor teaches what  

## What I focused on

While building this, I mainly worked on:

- Designing tables in a structured way  
- Connecting them using foreign keys  
- Avoiding duplicate or invalid data using constraints  
- Writing queries that actually make sense in real use  

## Things I implemented

- Primary keys and foreign keys  
- NOT NULL and CHECK constraints  
- Joins (inner, left, right)  
- Subqueries  
- Aggregate functions like count and max  

I also explored some advanced concepts:

- Views to simplify queries  
- Triggers to prevent wrong data (like invalid credits)  
- Stored procedures  
- Transactions (commit, rollback, savepoint)  
- Basic user access control  

## How to use

1. Open MySQL or any SQL tool  
2. Run the schema file first  
3. Then run the data file  
4. Try out the queries  

## Why I made this

I wanted to go beyond basic SQL and actually understand how databases are designed in real systems. This project helped me connect theory with practical implementation.

## Future improvements

- Add indexing for better performance  
- Connect it with a frontend  
- Build a small dashboard on top of it  

## Author
Himanshu Yadav  
BTech Cybersecurity
