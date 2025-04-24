# [Midterm Lab Task 3-1 - Using MYSQL Clause](https://github.com/user-attachments/files/19895253/Finals.Lab.Task.3-1.-.Manarang.docx)

## Step by Step Process
- **Step 1: Create the Database**
  - Open your MySQL environment (like MySQL Workbench or phpMyAdmin).
  - Create a new database by typing the command:
    - `CREATE DATABASE online_courseDB;`
  - This command sets up the main storage space for your online course data.

- **Step 2: Select the Database**
  - Choose or switch to the newly created database to start working in it:
    - `USE online_courseDB;`
  - This ensures all tables and queries will be applied to the correct database.

- **Step 3: Load Initial Data**
  - Download the `onlineCourse.l` file provided in the instructions.
  - Run or import this file into the MySQL environment.
    - It will automatically:
      - Create a table called `courses`.
      - Add 20 course records into the table.
  - Make sure the table has the following fields:
    - `id`: auto-incremented primary key.
    - `course_name`: VARCHAR, not null.
    - `category`: VARCHAR, not null.
    - `enrollment_limit`: INTEGER, not null.
    - `students_enrolled`: INTEGER, not null.

- **Step 4: Perform SQL Tasks in Order**

  - **Task 1: List Courses Below Capacity**
    - Find and display all courses where the number of enrolled students is less than the enrollment limit.
    - SQL Concept: `SELECT` with `WHERE` condition.

  - **Task 2: Group by Category**
    - Group the courses by their category and show the total number of enrolled students per category.
    - SQL Concepts: `GROUP BY` and `SUM()` function.

  - **Task 3: Show Fully Enrolled Courses**
    - Display courses where the number of students enrolled equals the enrollment limit.
    - SQL Concept: Equality condition in `WHERE`.

  - **Task 4: Total Students in All Courses**
    - Calculate and display the total number of students enrolled across all 20 courses.
    - SQL Concept: Aggregation using `SUM()`.

  - **Task 5: Sort Courses by Enrollment**
    - Display all courses ordered by the number of students enrolled, from lowest to highest.
    - SQL Concept: `ORDER BY` with ascending sort.

- **Final Step: Review Results**
  - Check that each query produces the expected output.
  - Verify correct field names and data consistency.

# Screenshots
## Query Statements
### 1. Task 1
- ![Image](https://github.com/user-attachments/assets/692184a7-0b93-4f43-bbc5-a55b6864bb61)
### 2. Task 2
- ![Image](https://github.com/user-attachments/assets/d9d3b6ed-2d92-4d3e-9ecf-dffe924905c0)
### 3. Task 3
- ![Image](https://github.com/user-attachments/assets/fc137d62-b971-45e8-855e-ce731bd824eb)
### 4. Task 4
- ![Image](https://github.com/user-attachments/assets/fc8e9309-32c2-46bd-a695-10e213696c43)
### 5. Task 5
- ![Image](https://github.com/user-attachments/assets/925b7c20-6077-474a-8a09-7006b1fdb2a2)

## Table Structure
1. Task 1
- ![Image](https://github.com/user-attachments/assets/311f5c59-25a2-4a42-ac8c-cfb17d885643)
2. Task 2
- ![Image](https://github.com/user-attachments/assets/3423ef5d-1f25-4312-9f86-8ebfac82f667)
3. Task 3 
- ![Image](https://github.com/user-attachments/assets/e175b54c-4402-4d68-a2f9-32856194e40c)
4. Task 4
- ![Image](https://github.com/user-attachments/assets/c23f0143-9075-45eb-8b23-2fd17b489233)
5. Task 5
- ![Image](https://github.com/user-attachments/assets/39a78a7e-74de-44e6-947c-f7583fc0d248)
