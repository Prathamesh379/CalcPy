# CalcPy
This My First Github Repository 
<br>
Author - Prathamesh Deshmukh
Explanation for code : -
<br>
1. `lines` function: This function simply prints a line of dashes, the length of which is determined by the `some_number` parameter passed to it.

2. The code asks the user for two numbers, `num1` and `num2`, and then displays a line of dashes.

3. There's a `while` loop that keeps running indefinitely (`while True`), unless it's explicitly broken. Inside this loop:

   a. The user is prompted to select an operation (addition, subtraction, multiplication, or division) by entering a number corresponding to each operation.
   
   b. The selected operation is stored in the `operation` variable.
   
   c. The code checks which operation was selected using `if`, `elif`, and `else` statements. Depending on the operation selected, it performs the corresponding calculation (`+`, `-`, `*`, or `/`) on `num1` and `num2` and stores the result in `num3`.
   
   d. The result of the operation is printed along with another line of dashes using the `lines` function.
   
   e. If the user enters an invalid operation (a number other than 1, 2, 3, or 4), it prompts the user to enter a valid operation and continues the loop.
   
   f. If there's any error during the execution of the code (for example, if the user enters a non-integer value), it ignores the error and continues the loop.

So, in simple words, this code creates a basic calculator that allows the user to perform addition, subtraction, multiplication, and division on two numbers. It keeps running until the user chooses to exit by selecting a valid operation.
