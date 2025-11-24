1. Project Title :
   
   Typing Speed Calculator (Python Program)

2. Overview of the Project :
   
   I have created a simple , beginner-friendly project on a “Typing Speed Calculator” using Python programming language. It checks how fast a user can type a given sentence. The program shows one random sentence,    records the time the user takes to type it, and then calculates the typing speed in characters per second. It also compares the original text with the user-typed text and counts the number of mistakes.

3. Features of the Project:

   A)	Displays a random sentence from a predefined list which ensures that the user does not have to memorise the sentence.

   B)	Records the start and end time of user typing.

   C)	Calculates typing speed (characters per second) using time() function.

   D)	Counts mistakes that is detects errors by comparing each character typed. The mismatch is counted as a mistake.

   E)	This is a project with a simple command line interface made easy for beginners .

   F)	This project uses only basic Python modules (no external installation).


4. Technologies / Tools Used :

       Technology / Tool	                                                                                    Purpose
         Python 3	                                                                                   Programming language used
         time module	                                                                                Used to calculate typing time
         random module	                                                                             Used to select a random sentence                                                                       
         Basic string operations	                                                                    For comparing characters and detecting errors
         Any code editor( VS Code / IDLE / Pycharm)                                                  For writing and running the program                               
   
                                                            
5. Steps to Install and Run the Project :
   
Step 1: Install Python
Download Python from the official website.
Install Python 3.x with default settings.

Step 2: Create the Program File
Open any editor (VS Code, IDLE, PyCharm).
Create a file named: typing_speed.py

Step 3: Paste the Code
Copy and paste the above Python code into the file.

Step 4: Run the Program
Open Command Prompt / Terminal and type:
python typing_speed.py
The program will start running.

Step 5: Follow On-Screen Instructions
Type yes to start typing test.
Type the displayed sentence.
The program calculates typing speed and detects errors.
Type no to exit.

6. Instructions for Testing

Test Case 1: Correct Typing
Type the displayed sentence exactly.
Speed should be realistic.
Errors should be 0.

Test Case 2: Wrong Typing
Change some letters intentionally.
Error count should increase a bit.

Test Case 3: Very Slow Typing
Type very slowly.
Speed should decrease.

Test Case 4: Very Fast Typing
Type very fast.
Speed should increase.

Test Case 5: Empty Input
Don’t type anything and press enter.
Speed should be very low or zero.
Error count should be high.

Test Case 6: Invalid Input
When asked “yes / no”, type any other word.
Program should show “Wrong input”.
