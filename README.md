This project was the final project of programming fundamentals course presented by Gaza Sky Geeks

Final Project
Full Task
Create Course Class with the following features
● course_id (generated incrementally)
● course_name
● course_level(A-B-C)
Create Student Class with this attributes:
● student_name
● student_id (generated incrementally)
● studnet_level(A-B-C)
● student_courses (List of Courses)
● method to add new course to student courses
○ the method should check if student_class as same as
course_class
● method to display student_details
○ name
○ class
○ courses which enrolled
Main Page
1. Add New Student
○ ask user to enter student name
○ ask user to select level(A-B-C)
i. if the input not one of (A-B-C) ask user to select
class again
○ print student saved successfully
2 . Remove Student
● ask user to enter student id
○ check if the user exist in the system :
■ if exist delete student
● print delete done successful
■ if not >> print user not exist
3. Edit Student
● ask user to enter student id
○ check if the user exist in the system :
■ if exist
● ask user to enter new name
● ask user to select new level
■ if not exist >> print user not exist
4. Display all students
5 . Create new Course
● ask user to enter class name
● ask user to select course_level (A-B-C)
6 . Add Course to student
● ask user to enter student number
○ check if student exist or not
○ if exist
■ enter course id
■ check if course is exist
● if exist add course to student
course list
● if not print >> course not exist
