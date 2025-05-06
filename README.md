# 19CS301-Module7
EX: 7.1 RECURSION

### Aim: 
To Write a Python Program to find the sum of all digits in a number using recursion
### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a base case for termination of the function. STEP 4: Create a recursive case to calculate the result.

STEP 5: Print the result. 

STEP 6: Stop.

### Program:
```
Reg no-212223070007
Name-Gopinath G

def sum_digits(num):
    if num < 0 or int(num) != num:
        return 0
    elif num == 0:
        return 0
    else:
        return (num % 10) + sum_digits(num//10)
num= int(input())
print(sum_digits(num))
```
### Output:
![image](https://github.com/user-attachments/assets/769a05da-cd87-4789-9d05-f0585ae6a580)


### Result: 
Thus the Python Program to find the sum of all digits in a number using recursion was executed successfully.
 

EX: 7.2 TYPES OF RECURSIONS

### Aim:
To Write a Python Program  to display first n whole numbers in reverse order using nested recursion

### Algorithm:

1. **Start**
2. Read input value `n`
3. Call function `fun(n)`
4. Inside `fun(n)`:

   * If `n == 0`:

     * Return `0`
   * Else:

     * Print `n` (with a space)
     * Call `fun(fun(n - 1))`
5. The function keeps calling itself recursively until `n` becomes `0`
6. Finally, print the returned value (which is always `0`)
7. **End**

### Program:
```
Reg no-212223070007
Name-Gopinath G

def fun(n):
    if n==0:
        return 0
    else:
        print(n, end=" ")
        return(fun(fun(n-1)))
        
n=int(input())
print(fun(n))

```
### Output:
![image](https://github.com/user-attachments/assets/37b97260-cc0e-4658-a891-256630f17977)

###Result: 
Thus the Python Program  to display first n whole numbers in reverse order using nested recursion was executed successfully.
 


EX: 7.3 TAYLOR SERIES

###Aim: 
To python program to evaluate the series using recursion by collecting the x and n values from the user.

### ALGORITHM:
STEP 1: Start.

STEP 2: Create a variable x and n.

STEP 3: Get the values of x and n from user.

STEP 4: Create a base case and recursive case to calculate the result.

STEP 5: Print the result.

STEP 6: Stop.
### Program:
```
Reg no-212223070007
Name-Gopinath G

def series(x,n):
         if n==0:
            return 1
         else:
            return x**n/n+series(x,n-1)
x = int(input())
n = int(input())
print(series(x,n))
```
### Output:
![image](https://github.com/user-attachments/assets/1d00b1a4-cecb-466f-8593-805f00d27461)

 
### Result: 
Thus the python program to evaluate the series using recursion by collecting the x and n values from the user was executed successfully .
 

EX: 7.4 Solve by recursion relation

### Aim: To Write a Python Program to find whether a string is a palindrome or not using recursion

### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a base case and recursive case to calculate the result.

STEP 4: Create a variable and get input from user.

STEP 5 : Call the function.

STEP 6: Print the result.

STEP 7: Stop.

### Program:
```
def is_palindrome(word):
      if len(word)<1:
            return True
      else:
            if word[0]==word[-1]:
                 return is_palindrome(word[1:-1])
             else:
                  return False
word = str(input())
if is_palindrome(word)==True:
        print("String is a palindrome")
else:
        print("String is not a palindrome")
```
### Output:
![image](https://github.com/user-attachments/assets/d30ef836-1901-448a-a146-dc905fdc3198)

### Result: Thus, the given program is implemented and executed successfully .
 

