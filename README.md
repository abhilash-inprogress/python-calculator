# python-calculator
A simple calculator made with Python.
try:
  num1 = float(input("Enter first number: "))
  num2 = float(input("Enter second number: "))
  operations = input(
      "Enter the operation you want to perform (+, -, *, /,%,//): ")
  if operations == '+':
    print("The sum of the numbers is: ", num1 + num2)
  elif operations == '-':
    print("The difference of the numbers is: ", num1 - num2)
  elif operations == '*':
    print("The product of the numbers is: ", num1 * num2)
  elif operations == '/':
    print("The division of the numbers is: ", num1 / num2)
  elif operations == '%':
    print("The modulus of the numbers is: ", num1 % num2)
  elif operations == '//':
    print("The floor division of the numbers is: ", num1 // num2)
  else:
    print("R u serious?")
  print("Thanks! Come back again!!")
except:
  print("Dude see what your doing! ")
