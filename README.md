# Functions
#def intro(name):
    #print("Hello, good morning i am", name)


#user_name = input("Enter your name")
#intro(user_name)


#def add(a,b):
    #add = a + b
   #print(add)
    #return add

#print(add(3,4))
#print(add(10,13))

def area(l,w):
    area = l * w
    print(area)

area(4,8)

# Program make a simple calculator

# This function adds two numbers
def add(x, y):
    return x + y

# This function subtracts two numbers
def subtract(x, y):
    return x - y

# This function multiplies two numbers
def multiply(x, y):
    return x * y

# This function divides two numbers
def divide(x, y):
    return x / y

num1 = int(input("Enter Number 1 : "))
num2 = int(input("Enter Number 2 : "))

print("Sum :", add(num1, num2))
print("Difference :", subtract(num1, num2))
print("Product :", multiply(num1, num2))
print("Quotient :", divide(num1, num2))

# Factorial of a number using recursion
def recur_factorial(n):
   if n == 1:
       return n
   else:
       return n*recur_factorial(n-1)

num = int(input("Enter a number"))

# check if the number is negative
if num < 0:
   print("Sorry, factorial does not exist for negative numbers")
elif num == 0:
   print("The factorial of 0 is 1")
else:
   print("The factorial of", num, "is", recur_factorial(num))
