print("привествую в своем калькуляторе")
print("*" * 15," calculator ", "*" * 15)
   

while True :
  print("Выберите действие")
  print("|+,-,/,*,выйти|") 
  operation = input("выберите действие 1,2,3,4,5\n")

  if operation == "5":
        print("пока")  
        break

  num1 = float(input("введите первое число"))
  num2 = float(input("введите второе число"))

 
  if operation == "1" :
       print(F"результат:{num1} + {num2} = {num1 + num2}")
 
  elif operation == "2":
     print(F"результат:{num1} - {num2} = {num1 - num2}")

  elif operation == "3":
    if num2 == 0:
         print("Ошибка: деление на ноль!")
    else:
         print(F"результат: {num1} / {num2} = {num1 / num2}")  

  elif operation == "4":
    print(F"результат: {num1} * {num2} = {num1 * num2}")

  else:
        print("Неверная операция! Выберите 1-5")
    
  print()  
