# Homework-6

CIDM 2315 Homework 6
(10 points)
Homework Grading Rubric:
The grader will run the whole program first. If there are errors, students will lose half points on this assignment. Then the grader will check each question in detail.
Unanswered questions will lose the corresponding points
The minimum homework grade is 0 points
Upload the code of your work to GitHub then submit the GitHub Link of the file to WTClass. Please do not submit the code files to WTClass directly.
The instruction for submitting homework can be found on WTClass – Lecture- Student Guide - Using GitHub to Submit Homework


Q1: Implement the Professor and Student classes based on the UML class diagram (6 points):
Hint: attributes with  “-” should be defined as private variables or properties

Professor
profName: string
classTeach: string
salary: double
SetSalary(double salary_amount):void
GetSalary(): double


	
Student
studentName: string
classEnroll: string
studentGrade: double
SetGrade(double newGrade): void
GetGrade(): double


Then, in the Main method of the Program class, 
- Create 2 new professors
The first professor is called “Alice”, she teaches “Java”, her salary is 9000;
The second professor is called “Bob”, he teaches “Math”, his salary is 8000;
- Create 2 new students
The first student is called “Lisa”, she enrolls “Java”, and the grade is 90;
The second student is called “Tom”, he enrolls “Math”, and the grade is 80;

Q2: Follow the instruction to print results (4 points):
Print name, class, salary of each professor;
Print name, class, grade of each student;
Calculate the difference of two professors’ salary.
Calculate the total grade of two students.
Sample output: 


Put the code of all classes into a single code file called Homework6.cs and upload this file to GitHub, then submit the GitHub link of Homework6.cs to WTClass

