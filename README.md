num1 = float(intput("Enter the first number : "))
num2 = float (intupt("Enter the second number : "))
print("Choose an operation: ")
print("1. Addition (+)")
print("2. Subtraction (-)")
print("3. Multiplication (*)")
print("4. Division (/)")
print("5. Modulus (%)")
print("6. Floor division (//)")
print("7. Power (**)")
oper = int(input("Enter your choise (1/2/3/4/5/6/7): "))
match oper:
case 1:
result = num1 + num2
print(f"{num1} + {num2} = {result}")
case 2:
result = num1 - num2
print(f"{num1} - {num2} = {result}")
case 3:
result = num1 * num2 
print(f"{num1} * {num2} = {result}")
case 4:
if num2 != 0:
result = num1 / num2
print(f"{num1} / {num2} = {result}")
else:
print("Error: Division by zero is not allowed!")
case 5:
result = num1 % num2
print(f"{num1} % {num2} = {result}")
case 6:
result = num1 // num2
print(f"{num1} // {num2} = {result}")
case 7:
result = num1 ** num2
print(f"{num1} ** {num2} = {result})
case _:
print("Invalid operation choice!")
# caluclater
