Author: Nick House
Language: Python
Class: CS-4200 Python for Scientific Computing and Data Science
Project: Final Coding Project

# DataScience_Python_FinalCode
Final Coding for Test for Python for Scientific Computing and Data Science

This project solves the issues as layed out in the following requirements


1. Follow the instructions carefully, using the exact identifier names provided in the description. Implement a class called Student. Include code in the class definition to keep track of how many Student objects are created. Each Student object has an attribute named score. The __init__ method of Student takes a random integer between 1 and NSCORES (where NSCORES is a predetermined constant), both inclusive, as its argument and computes the score by calling a function f on that integer (the function f(x) simply returns the double of its input argument x). A method get() returns the score.

Next, create a list (call it stulist) of a random number (no more than NSTUDENTS, where NSTUDENTS is a predetermined constant) of Student instances (objects) (do not use append()). Now, use a single statement to print the number of Student objects created (not by printing stulist's length). Next, use a single statement to print the average of the scores of the Students in stulist (not by explicit sum / length). Your program should NOT contain any for loop or any for clause or any explicit list comprehension or any if statement. Use 5 and 10 for NSCORES and NSTUDENTS, respectively. Do not create any named list other than stulist. Use numpy's random, not python's own random. Show the code and a single run in Jupyter Notebook. Please do not include any scratch (debugging) or redundant code. Do not include code for exception handling.

2. In the following, the phrase "random value" is to be taken to mean a uniform random floating-point number between 0 and 1, to be obtained by an appropriate call to the random number generator (not chosen arbitrarily by hand). Write a SINGLE statement (in each case) to implement each of the following tasks (apart from the initial import and setting up of the random number generator at the very beginning, if needed). Vectorized operation (and broadcasting) must be used; do not use loops or if statements. Please show the six statements along with the corresponding execution results in six consecutive cells (do not change the order of the parts). 

   a. Create a 2-dimensional numpy array X (3 rows and 4 columns) of random values. 
   b. To each column of X, add the square of a vector of three random values (the same vector is added to the individual columns of X; this vector is part of the single statement        and does not have its own name). Call the result Z. 
   c. Divide each row of Z by the max element in that row. Call the result P. 
   d. Next, for each element of P, replace it with 0.3 if it is less than 0.5. 
   e. Print True if the index of the column with the highest column-sum in P is the same as the index of the row with the smallest row-sum, False otherwise. 
   f. Print in reverse the array of the column-wise minimum values of P.
