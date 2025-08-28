class calculator:
  def add(self,a,b):
    return a+b

  def subtract(self,a,b):
    return a-b

  def multiply(self,a,b):
    return a*b

  def divide(self,a,b):
    if b != 0:
      return a/b
    else:
      return "error! division by 0"

  def power(self,a,b):
    return a**b


calc=calculator()

# Taking user input
a = float(input("Enter the first number (a): "))
b = float(input("Enter the second number (b): "))

# Performing calculations
print("Addition:", calc.add(a, b))
print("Subtraction:", calc.subtract(a, b))
print("Multiplication:", calc.multiply(a, b))
print("Division:", calc.divide(a, b))
print("Exponentiation:", calc.power(a, b))# Python-code-practice
