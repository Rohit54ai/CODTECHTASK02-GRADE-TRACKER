## PERSONAL DETAILS :
  #### Name : ROHIT PANDEY 
  #### Company : CODTECH IT SOLUTIONS
  #### ID : CT04PP2321
  #### Domain : PYTHON PROGRAMMING
  #### Duration : 15th June 2024 to 15th July 2024
  #### Mentor : SRAVANI GOUNI



## OVERVIEW OF THE PROJECT

  ### PROJECT : Student Grade Tracker
  ### OBJECTIVE :
  The objective of the project is to create a Develop a Python program to track and manage student grades.
  The program should allow the user to input grades for different subjects or assignments, calculate the
  average grade, and display the overall grade along with any additional information (such as letter grade or GPA).
 

## Input Subject Names and Grades: The program prompts the user to enter the number of subjects, then asks for each subject’s name and grade, storing them in a dictionary.
## Calculate Average Grade: It calculates the average grade by summing all the grades entered and dividing by the number of subjects.
## Determine Letter Grade: Based on the average grade, it determines a letter grade using a predefined grading scale.
## Output Results: Finally, the program prints out the grades for each subject, the average grade, and the corresponding letter grade.






##get_grades Function:
This function asks the user for the number of subjects and then, in a loop, prompts for each subject’s name and grade.
The subject names and grades are stored in a dictionary called grades, where the subject name is the key and the grade is the value.

##calculate_average Function:
This function takes the grades dictionary as input.
It calculates the average by summing all the grades from the dictionary using sum(grades.values()) and dividing by the number of subjects, which is obtained using len(grades)
.
##determine_letter_grade Function:
This function determines the letter grade based on the average grade.
It uses a series of if-elif-else statements to compare the average grade against a set grading scale and returns the corresponding letter grade.

##main Function:
This is where the program starts executing.
It calls get_grades to input grades, calculate_average to find the average, and determine_letter_grade to get the letter grade.
It then prints out all subjects with their grades, followed by the average grade and letter grade


##if name == “main”:
This line checks if this script is being run directly (not imported as a module).
If it is run directly, it will call the main function to start the program.

![Screenshot 2024-07-14 133531](https://github.com/user-attachments/assets/af7bc5d1-d689-459e-afd2-2c75014bce9c)
![Screenshot 2024-07-14 133415](https://github.com/user-attachments/assets/a7c00202-af8b-4d03-864b-02abbfb557d6)

