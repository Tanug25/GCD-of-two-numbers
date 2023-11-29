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
Developed by:Tanushree.A 
RegisterNumber:  23004953
*/
```
def gcd():
    a=int(input())
    b=int(input())
    while b:
        a,b=b,a%b
    print("GCD of two numbers is:",a)

## Output:
![gcd of two number](gcd.png)
![2a](https://github.com/Tanug25/GCD-of-two-numbers/assets/138849166/203d80c3-d544-492c-b645-ca7a739afc15)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
