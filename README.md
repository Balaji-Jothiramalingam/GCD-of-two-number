# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: BALAJI J
RegisterNumber:  212221243001
*/
```
def gcd():
   a=int(input())
   b=int(input())
   while b!=0:
     a,b=b,a%b
   print("GCD of two numbers is:",a)

## Output:

![p4](https://github.com/Balaji-Jothiramalingam/GCD-of-two-number/assets/114234865/b0dd1a3b-bde2-4cae-8516-324e411db14e)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
