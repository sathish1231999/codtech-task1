NAME:BURRRI SATHEESH YADAV
COMPANY:CODTECH ITSOLUTIONS
ID:CTO8O6CE
DOMAIN:PYTHON
DURATION DECEMBER TO JAN 2025
MENTOR:NEELA SANTHOSH KUMAR
Develop a Python program to track and manage student grades. The

program should allow the user to input grades for different subjects or

assignments, calculate the average grade, and display the overall

grade along with any additional information (such as letter grade or gpa)

Class Definition:

Student class is created to store student information.
_init_: Initializes the name and an empty dictionary grades to store subject-grade pairs.
add_grade: Adds a new subject and its corresponding grade to the grades dictionary.
calculate_average: Calculates the average grade by summing all grades and dividing by the number of subjects.
get_letter_grade: Determines the letter grade based on the average grade using a simple grading scale.
get_gpa: Converts the letter grade to a corresponding GPA value.
display_grades: Prints the student's name, individual subject grades, average grade, letter grade, and GPA.
Example Usage:
An instance of the Student class is created with the name "Alice".
Grades for "Math", "Science", and "English" are added using the add_grade method.
Finally, the display_grades method is called to print the student's grade information.
This program provides a basic framework for tracking a
Key Improvements:

Interactive Input: The program now allows the user to enter student name and subject-grade pairs interactively.
Input Validation: Checks for valid grade input (between 0 and 100) and provides an error message if invalid input is entered.
User-Friendly Output:
Displays grades with two decimal places for better readability.
Includes a clear message for invalid input.
Enhanced Readability: Uses docstrings to explain the purpose of each method.
if _name_ == "_main_": Block: Encapsulates the interactive input and display logic within this block, making the code more modular and reusable.
This improved version provides a more user-friendly and robust solution for tracking and managing student grades. You can further expand it by:

Adding features to handle weighted grades.
Implementing a graphical user interface (GUI) for a more intuitive user experience.
Allowing the user to save and load student data from files.
Integrating with a database for more efficient data management and sharing.
Implementing more advanced grading calculations and reporting options.


