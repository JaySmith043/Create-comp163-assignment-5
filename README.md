# Create-comp163-assignment-5

Loop Practice Challenges

This project contains three Python coding challenges, each demonstrating the use of different loop structures (while, for, and nested for loops).

-Challenge 1: Collatz Conjecture (Number Sequence Generator)

Why I chose a while loop:
The number of steps required to reach 1 is unknown. A while loop is ideal for situations where the number of iterations is not fixed in advance. The loop runs as long as current_number != 1.

How the solution works:

Take a positive integer from the user.

If the number is even, divide it by 2.

If the number is odd, multiply it by 3 and add 1.

Print each number in the sequence until 1 is reached.

Count and display the total number of steps.

-Challenge 2: Prime Number Checker

Why I chose a for loop:
The divisors to test are known in advance: from 2 up to n-1. A for loop is the best choice when the iteration range is fixed.

How the solution works:

Take an integer greater than 1 from the user.

Print which divisors will be tested.

Loop through the range 2 to n-1.

If any number divides evenly into n, declare it not prime and show the divisor.

If no divisor is found, declare the number prime.

-Challenge 3: Multiplication Table Grid

Why I chose nested for loops:
The multiplication table is a two-dimensional structure (rows × columns). Nested loops are the natural way to generate this kind of grid.

How the solution works:

Print the header row with numbers 1–10.

Use the outer loop to go through row numbers 1–10.

Inside each row, use the inner loop to multiply the row number by column numbers 1–10.

Format the results so that the table columns line up neatly.

-AI Assistance

ChatGPT.

I used it for guidance on  clarifying loop choices and structuring this README.

All final code was reviewed, tested, and understood by me.

-This project demonstrates how different loop types are chosen based on problem requirements:

while → unknown number of iterations.

for → fixed, known range of iterations.

nested loops → structured, multi-dimensional output.
