Name: Yanwei Su
ID:101209998

The code provides getAllStudents(), addStudent(), updateStudentEmail(), deleteStudent().
getAllStudents() -- get all information from students
addStudent() -- add a new students
updateStudentEmail() -- update students' email by students' id
deleteStudent() -- delete students' information by students' id

Files:
DB.txt -- Query SQL for creating students table
Assigment4.sql -- Database for store students table
A4JDBC.zip -- Code
postgresql-42.7.0.jar -- JDBC's jar

How to use:
1.Download these files.
2.Create a database called Assigment4.
3.Import Assigment4.sql into it.
4.Unzip A4JDBC.zip.
5.Open A4JDBC using a compiler such as IDEA
6.If you don't have lib, you need to import postgresql-42.7.0.jar first.
7.Then compile the file and run it.

Notice:
YouTube: https://youtu.be/tPTNnFn1-wo
1.The examples in the video about update() and delete() are not detailed. You could use the code to test if you need.
2.The test cases provided in the code have already been used. So it needs to be modified appropriately. For example, add a new student. I have deleted student who id is 4. So id will be 1,2,3,5 to show. Test update() and delete() need to change input value.
3.You could also create a new database (the name of the database must be Assigment4 or change the URL of the code), create a new students table using the contents of the DB.txt file, and insert the data provided by the professor for testing.

Thank you.


