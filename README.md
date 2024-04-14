# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
#Program to find the square root for the given number(newton's method) using function.  
#Developed by: EASWAR R   
#RegisterNumber: 212223230053   
```
def squareroot(num1,iternum):
    num2=float(num1)
    for i in range (iternum):
        num1=0.5*(num1+num2/num1)
    print("Square root of the number:",num1)
num1=int(input())
iternum=100
squareroot(num1,iternum)
```

## Output:
![image](https://github.com/EaswarR2005/Square-root-of-a-number/assets/146931525/2a2d0a6f-6fda-47c2-ae7c-709746347dfd)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
