# python-assignment-2
def add(int num1 , int num2):
      C=num1+num2 
      print(C)
def multiply(int num1, int num2):
     D=num1*num2
     print(D)

a=int(input("enter a number :"))
b=int(input("enter a number: "))
add(a,b)
multiply(a,b)

#2nd question 
Mylist=[70,80,77,86,99]
C=avg(Mylist)
print(C)
if(avg>90):
   print("grade is A")
elif(avg>80 &&avg <90):
   print("grade is B ")
elif(avg>70 && avg<80):
   print("grade is C ")
else:
   print("Your are fail ")
