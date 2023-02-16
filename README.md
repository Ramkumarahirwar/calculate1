#def calculate():
num1=int(input("Enter the fist number:"))
num2=int(input("Enter the second number:"))
#perform the calculation based on the operator entered
operation=input("Enter the operation you would like to perform(+,-,*,/):")
if operation=='+':
   result=num1+num2
   print("The answer is:",result)
elif operation=='-':   
   result=num1-num2  
   print("The answer is:",result)
elif operation=='*': 
  result=num1*num2 
  print("The answer is:",result)
elif operation=='/':
   result=num1/num2
   print("the answer is:",result) 
else:
   print("bye" )   
