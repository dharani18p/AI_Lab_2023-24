# Ex.No: 5   Logic Programming – Factorial of number                                                                     
### REGISTER NUMBER : 212222220011
### AIM: 
To  write  a logic program for finding the factorial of given number using SWI-PROLOG. 
### Algorithm:
1. STEP 1: Start the program
2. STEP 2:  Write a rules for finding factorial of given program in SWI-PROLOG.
3.   a)	factorial of 0 is 1 => written as factorial(0,1).
4.   b)	factorial of number greater than 0 obtained by recursively calling the factorial    function.
5. STEP 3: Run the program  to find answer of  query.
6. STEP 4: Stop the program.

### Program:
```
factorial(0,1).
factorial(A,B) :-
 A > 0,
 C is A-1,
 factorial(C,D),
 B is A*D.

```
### Output:


![311676152-1c5efc51-ecd4-4501-8616-730d5b86d2bc](https://github.com/user-attachments/assets/ebf1b5ae-6dc9-4660-8c35-847121d50179)

### Result:
Thus the factorial of given number was found by logic programming. 
