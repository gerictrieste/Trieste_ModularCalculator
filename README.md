# Trieste_ModularCalculator

num1 = float(input("Enter 1st number... ")) # asks for user's numbers
num2 = float(input("Enter 2nd number... "))

operation = int(input("Pick an operation 1-addi. 2-subt. 3-mult. 4-divi.")) # asks for the needed operation

#these define the function for the operations
def addition(x, y): 
    result = x + y
    return result

def subtraction(x, y):
    result = x - y
    return result

def multiplication(x, y):
    result = x * y
    return result
    
def division(x, y):
    result = x / y
    return result

# checks for the operation wanted and if it is valid
if operation == 1:
    print(addition(num1, num2))
elif operation == 2:
    print(subtraction(num1, num2))
elif operation == 3:
    print(multiplication(num1, num2))
elif operation == 4:
    print(division(num1, num2))
else:
    print("Invalid operation")
