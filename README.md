# WEB-HW-07
First step:
Implement your SQLAlchemy models for the following tables:

Students table;
Groups table;
Teachers table;
Subjects table with the teacher who teaches the subject;
Table where each student has grades for subjects with the date when the grade was received.
Second step:
Use alembic to create migrations in the database.

Third step:
Write a script seed.py and fill the resulting database with random data (~30-50 students, 3 groups, 5-8 subjects, 3-5 teachers, up to 20 grades for each student for all subjects). Use the Faker package for filling. Use the SQLAlchemy session mechanism when filling the data.

Fourth step:
Perform the following queries on the resulting database:

Find 5 students with the highest average grade for all subjects.
Find a student with the highest average grade for a specific subject.
Find the average grade in groups for a specific subject.
Find the average grade in the class (for the entire grades table).
Find the courses taught by a specific teacher.
Find the list of students in a specific group.
Find the grades of students in a separate group for a specific subject.
Find the average grade given by a specific teacher for their subjects.
Find the list of courses attended by a specific student.
Find the list of courses taught by a specific teacher to a specific student.
To execute these queries, create a separate file my_select.py, where there will be 10 functions from select_1 to select_10. The function should return the result similar to the previous homework. Use the SQLAlchemy session mechanism when querying the data.
