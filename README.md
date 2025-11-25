# Project-by-25BCE10859-fall2025
This Project contains python code for a personal expense tracker, which helps in keeping record of currency spent by the user in a given session.
It makes use of 3 functions that are defined in the file.
Input is required at 3 separate stages depending on the choice of the user in what they want to do with the program.
It continues in a loop until the user chooses to exit by simply entering the proper command during the first input stage.
It has defined error checking operations that notify the user if invalid input has been given.

To use this program, you will first have to enter the code in a suitable software and run it. Then:

1- The program will welcome you to the expense tracker and ask you for an input between "1", "2", and "3" depending on what you wish to do with the program among the options given on screen.

2- Upon entering input "1", it will ask you what category you want to enter more expenses, or new expenses into. Here, you may input a new category for which to track expenses, or the name of an older category, and the expenses will be added to the it. The casing of letters is irrelevant as the code contains an in-file robust way to generalise lower and upper case inputs.

3- After this, the program will ask you for the amount you want added to the expenses of the category. You have to simply enter the desired amount. Float point numbers will be rounded off to two digits. Then, you will be notified of these expenses being added and sent back to step 1

4- If your choice of input in step 1 was "2", the program will display all currently added expenses to you. These will be displayed according to specific categories, and there will also be a total amount that will account for everything. If you haven't entered any expenses yet, the program will notify you of the same. After this, you are once again looped back to step 1.

5- If your choice of input in step 1 was "3", then the program will exit the expense tracking loop and display a simply "Thank you message" to signify the end of the operation.
