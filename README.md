# STUDENT_DBMS_SYSTEM


1. Student Database Management System: The code implements a basic Student Database Management System. It allows users to perform CRUD (Create, Read, Update, Delete) operations on student records stored in a binary file named "users.txt."

2. File Handling: The program uses `FILE` pointers for file handling. It attempts to open the "users.txt" file and creates it if it doesn't exist. It reads and writes student records to/from the file using binary file read (`fread`) and write (`fwrite`) operations.

3. Main Menu Interface: The program presents a user-friendly menu with options such as adding new student records, listing all existing records, modifying records based on the last name, deleting records based on the last name, and exiting the program.

4. Data Storage: Student information is stored in a structure named `student`, which contains fields for first name, last name, course, and section. Each student record in the file has a fixed size, and the program uses file pointers to navigate and perform operations on the records stored in the "users.txt" file.
