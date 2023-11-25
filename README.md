# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm: 
### Step 1: 
Define a function.
### Step 2:
Get the two numbers from the user.
### Step 3: 
Compare the two values, to find the smaller number.
### Step 4: 
Use for() and if() loop to find the GCD of the two numbers.
### Step 5:
print the result
### Step 6:
End the program
## Program:
```
def gcd():
    num1=int(input())
    num2=int(input())
    if num1>num2:
        min=num2
    else:
        min=num1
    for i in range(1,min+1):
        if(num1%i==0 and num2%i==0):
             gcd=i
    print("GCD of two numbers is:",gcd) 
```

## Output:
![GCD](https://github.com/guru14789/GCD-of-two-numbers/assets/151705853/4ccd311e-4e77-493d-a8c4-db62cbd1e196)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
