# calculate1
def calculate():
    # Take input from the user
    operation = input("Enter the operation you would like to perform (+, -, *, /): ")
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))

    # Perform the calculation based on the operator entered
    if operation == '+':
        result = num1 + num2
        print("The answer is: ", result)
    elif operation == '-':
        result = num1 - num2
        print("The answer is: ", result)
    elif operation == '*':
        result = num1 * num2
        print("The answer is: ", result)
    elif operation == '/':
        result = num1 / num2
        print("The answer is: ", result)
    else:
        print("Invalid operator entered. Please try again.")

# Call the calculate function
calculate()
