Purpose:
A program finds two array indices whose values add up to a predetermined target value.

Explanation of the Code:

Function twoSum:-
This function takes two inputs:
nums: A vector containing the numbers.
target: The desired sum of two numbers.
It uses two nested loops to check all possible pairs of numbers in the array.
The outer loop picks the first number.
The inner loop picks the second number.
If the sum of the selected pair equals the target, their indices are returned as a vector.
If no such pair exists, an empty vector is returned.

Main Function:-
The program starts by asking the user to input the size of the array (n).
Then, the user is prompted to enter n elements into the array.
The target value is then entered by the user.
The twoSum function is called with the input array and target value.
If the function finds a valid pair, it prints the indices of the two numbers. Otherwise, it outputs "No solution found!".
