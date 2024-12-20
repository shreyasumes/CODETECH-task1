 def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y != 0:
        return x / y
    else:
        return "Error! Division by zero."

def calculator():
    print("Welcome to the Basic Calculator!")
    
    # Get user input
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    
    # Choose operation
    print("Choose an operation:")
    print("1. Addition (+)")
    print("2. Subtraction (-)")
    print("3. Multiplication (*)")
    print("4. Division (/)")
    
    operation = input("Enter operation (1/2/3/4): ")
    
    # Perform calculation
    if operation == '1':
        print(f"The result is: {add(num1, num2)}")
    elif operation == '2':
        print(f"The result is: {subtract(num1, num2)}")
    elif operation == '3':
        print(f"The result is: {multiply(num1, num2)}")
    elif operation == '4':
        print(f"The result is: {divide(num1, num2)}")
    else:
        print("Invalid operation. Please try again.")

# Run the calculator
calculator()
[11:13 AM, 12/20/2024] Shreyas Chinnu: task1
