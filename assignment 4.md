# Day 3 Assignment:

# Define a function which will take a number as argument and return its factorial.

# Call the function to print factorial of any number(integer).


def factorial(num):
    factorial = 1    
    if num < 0:    
        print(" Factorial does not exist for negative numbers")    
    elif num == 0:    
        print("The factorial of 0 is 1")    
    else:    
        for i in range(1,num + 1):    
            factorial = factorial*i    
        print("The factorial of",num,"is",factorial)    


num = int(input("Enter a number: "))
factorial(num)
