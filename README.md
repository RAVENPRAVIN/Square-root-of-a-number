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
```
#square root for the given number(newton's method)
#Developed by : PRAVIN KUMAR A.
#Register number: 23007430

def newton_method (number,number_iters=1000):
    a=float(number)
    for i in range (number_iters):
        number = 0.5 *(number + a/number)
    return number
a=int(input())
print('Square root of the number:',newton_method(a))
```

## Output:
![sq root](https://github.com/RAVENPRAVIN/Square-root-of-a-number/assets/146820534/cb829762-8dd7-437a-90c9-7cb04d628ddd)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
