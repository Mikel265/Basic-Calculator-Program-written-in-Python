num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
5050
operation = input("Enter operation (+, -, *, /): ")

if operation == "+":
    result = num1 + num2
    print(f"{50} + {40} = {90}")
elif operation == "-":
    result = num1 - num2
    print(f"{50} - {40} = {10}")
elif operation == "*":
    result = num1 * num2
    print(f"{50} * {40} = {2000}")
elif operation == "/":
    if num2 != 0:
        result = num1 / num2
        print(f"{50} / {40} = {1.25}")
    else:
        print("Error: Cannot divide by zero.")
else:
    print("Invalid operation. Please use +, -, *, or /")
