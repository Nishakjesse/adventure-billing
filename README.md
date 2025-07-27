# adventure-billing
print("welcome to this adventure game")
name= input("what is your name")
print("heys " + name + ",lets begin your adventure" )
choice1= float(input("what is your height in cm?"))
if choice1 >=150 :
  print("you can go up the merry go round")
  choice2 =int(input("how old are you in years?"))
  if choice2 <=12:
    print("please pay $5")
  elif choice2 <18 :
    print("please $7")  
  else:
    print("please pay $12")
else:
  print("go home to your parents")
