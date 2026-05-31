print("Welcome to my calculator")
print("*" * 15," calculator ", "*" * 15)
   

while True :
  print("select an action")
  print("|+,-,/,*,exit|") 
  operation = input("select an action 1,2,3,4,5\n")

  if operation == "5":
        print("Goodbue")  
        break

  num1 = float(input("choose the first number"))
  num2 = float(input("choose the second number"))

 
  if operation == "1" :
       print(F"result:{num1} + {num2} = {num1 + num2}")
 
  elif operation == "2":
     print(F"result:{num1} - {num2} = {num1 - num2}")

  elif operation == "3":
    if num2 == 0:
         print("Error: division by zero!")
    else:
         print(F"result: {num1} / {num2} = {num1 / num2}")  

  elif operation == "4":
    print(F"result: {num1} * {num2} = {num1 * num2}")

  else:
        print("Invalid operation! Select  1-5")
    
  print()  
