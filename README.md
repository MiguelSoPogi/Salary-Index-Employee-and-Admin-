# Final Term Project for LBYEC2B
## Salary-Index-Employee-and-Admin
The project tackles monitoring the duration of work per employee and this is used to calculate the salary that they should be receiving from the admins. This program is designed to collect and create usernames and passwords of the employeees. This will also gather their employee information such as ID number, name, and position in the company. The program will also ask them for the duration of the work that they have put in, this will serve as the checkout feature for it to be more easier to track by the admins. There is also an admin feature that may be accessed and this is used to help them monitor the statistics of the employees. This is here since it is very tedious to monitor each employee one by one. While this program may benefit a lot of companies with their internal systems and to the point that it becomes more productive for the company and employees.
The objective of this project is to apply the following concepts learned from the course: 
-1D and 2D arrays must be used, in order to contain the several sets of data into an orgranized array. Due to the nature of the data present, it is also recommended to utilize the use of 2D arrays.
-Strings processing is another feature that needs to be used in the program. Since it will be used for the program to identify distinct usernames and passwords.
-For the strings and array the use of char username[20], and password[2] is used to identify the maximum number of letters for the username and password function in the program.
-File I/O should be present in the project. it is used for placing it to another file. For c, we ust the functions fprint and fscan. but in Cpp we used the term that is generally known as outfile it is still the same as the file I/O.
-For the code pointer it wasn't used that much in this program. 
-Object Oridented programming is used to call the variables inside the class structure, it a style of programming that the user has learned throughout the duration of them term. The user must be able to use the "dot" feature for example salary.name The salary signifies where the class is then then the name is sthe variable inside the certain class structure.
-For loop should also be present in this proeject. It is used for repeating the certain code or looping it and making use of the upper portion of the code that is inputted in the commands.
-Do while loop is closely similar to the while loop. It will continue with the program until a specific condition is fulfilled.

In order for the Salary Index to work, the programmer must apply the following programming concepts in the pertinent program source code line/s:
| Programming Concept  | Pertinent Program Source Code Line                                                                                                                                                                                                    |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1D and 2D arrays     | 1D Array = userData.h: lines 3-5, 15-20, and 45-59, orders.h: lines 8, and 10-15 |
| Strings, Array of Strings, and String Processing     | Strings Processor: userData.h: lines 6, and 9-17 , orders.h: lines 7, 30-33, and 35-45|
| File I/O, Pointers   | File I/O: In functions loadFiles and updateFiles <br> All functions with the employee employees parameter |


These are some sample outputs in the program:

| Sample Console Input | Expected Console Output  |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2 <br> 12 <br> password <br> Lebron <br> James <br> admin <br>  3 <br>          | Welcome!'! <br> "1. Login." <br><br> "2. Register Account." <br><br> "3. Exit Program." <br><br> Please choose an option (1-3): 2 <br>Enter ID Number: 12 <br>Enter Password: Password <br> Enter First Name: Lebron <br> Enter Last Name: James <br> Enter Positiion: admin <br> Enter Job (1 for Staff, 2 for Manager, 3 for Executive): 3 <br> Account Successfully created!<br>Redirecting back to Main Menu... |
| 1 <br> 1         | Welcome!'! <br> "1. Login." <br><br> "2. Register Account." <br><br> "3. Exit Program." <br><br> Please choose an option (1-3): 1 <br>Enter ID Number: 1 <br> ERROR: User ID does not exist! <br> Register first instead! |
| 1 <br> 12 <br> password <br>  3 <br>          | Welcome!'! <br> "1. Login." <br><br> "2. Register Account." <br><br> "3. Exit Program." <br><br> Please choose an option (1-3): 1 <br>Enter ID Number: 12 <br>Enter Password: Password <br> <br> Welcome Lebron! <br> What would you like to do? <br> 1. Display All Users <br> Display All Employees <br> 3. Display All Admins <br> 4. View an Employee's Statistics. <br> 5. Exit Admin Menu <br> Please choose an option (1-3): 1 <br>-----------------------------------------------------------------<br> User ID               Name            Hours         Salary <br>12         Lebron James             0            0.00|
| Number of terms to track: 1 <br> Number of subjects you are taking for the term: 2 <br>  | Subject: FNDSTAT <br> Grade 4.0 <br> Total Unit of the Subject: 3 <br> Subject: FNDMATH <br> Grade 4.0 <br> Total Unit of the Subject: 3 <br> <br> GPA: 4.0 <br> CGPA: 4.0 <br> Award: 1st Dean's Lister |
| Number of terms to track: 1 <br> Number of subjects you are taking for the term: 2 <br>  | Subject: FNDSTAT <br> Grade 3.0 <br> Total Unit of the Subject: 3 <br> Subject: FNDMATH <br> Grade 3.0 <br> Total Unit of the Subject: 3 <br> <br> GPA: 3.0 <br> CGPA: 3.0 <br> Award: 2nd Dean's Lister |
| Number of terms to track: 1 <br> Number of subjects you are taking for the term: 2 <br>  | Subject: FNDSTAT <br> Grade 2.0 <br> Total Unit of the Subject: 3 <br> Subject: FNDMATH <br> Grade 2.0 <br> Total Unit of the Subject: 3 <br> <br> GPA: 2.0 <br> CGPA: 2.0 <br> Award: none |



