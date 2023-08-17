# Semester_Project
SEIDU YAKUBU

UEB3243322

IT C

This code represents a simple GPA (Grade Point Average) and CGPA (Cumulative Grade Point Average) calculator application in C++. Users can interact with the program through a console-based menu to perform GPA and CGPA calculations. Below is a breakdown of the different components and functionalities of the code:

1. Main Function (`main`):
   - The main function displays a menu with four options: calculating GPA, calculating CGPA, understanding the calculation method, and exiting the application.
   - It uses a loop with a label (`sub`) and a switch-case structure to handle user input and execute corresponding functions.

2. Function: `calculateGPA`:
   - This function calculates the GPA based on the user's input.
   - Users provide the number of subjects, the credit hours for each subject, and the corresponding points.
   - It calculates the weighted sum of credit hours and points, then divides by the total credit hours to determine the GPA.
   - The function also provides options to recalculate GPA, go back to the main menu, or exit the application.

3. Function: `calculateCGPA`:
   - This function calculates the CGPA based on the user's input.
   - Users input the GPA for each semester, and the function calculates the average to determine the CGPA.
   - Similar to the GPA function, it provides options to recalculate CGPA, go back to the main menu, or exit the application.

4. Function: `method`:
   - This function simply explains the methods used to calculate GPA and CGPA.
   - It describes the mathematical formulas for calculating GPA and CGPA.
   - Users can choose to go back to the main menu or exit the application.

5. Menu and User Interaction:
   - The code uses `system("cls")` to clear the console screen for a cleaner display.
   - The menu allows users to select options by entering a corresponding number.
   - If an invalid option is entered, the program provides an error message and loops back to the input prompt using a label (`sub`).
   - Each of the calculation functions provides an option to calculate again, return to the main menu, or exit the application.

6. Exiting the Application:
   - The `exit(EXIT_SUCCESS)` statement is used to gracefully exit the application with a successful status.

7. Understanding the Calculation:
   - The explanation of GPA and CGPA calculation methods is provided to help users understand the underlying principles.

This code allows users to perform GPA and CGPA calculations and provides an explanation of the calculation methods. However, it's important to note that the use of `goto` statements for control flow and repeated function calls (e.g., `main()`) within the program is generally considered poor practice and can lead to complex and difficult-to-maintain code. Using structured control flow and modular design would be more advisable in a real-world application.
