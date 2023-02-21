def isDivisibleBy2(num):
  if(num%2)==0:
    return True
  else:
      return False

print(isDivisibleBy2(10))
print(isDivisibleBy2(15))




ques2
n=int(input("Enter the digit from 0 to 9: "))
print("Entered digit is : ",end='')
if n==0:
  print("Zero")
elif n==1:
  print("One")  
elif n==2:
  print("Two") 
elif n==3:
  print("Three") 
elif n==4:
  print("Four") 
elif n==5:
  print("Five") 
elif n==6:
  print("Six") 
elif n==7:
  print("Seven") 
elif n==8:
  print("Eight") 
elif n==9:
  print("Nine") 
  
  
  QUE3
  
  n=int(input("Enter the number: "))
temp=n
rev=0
while(n>0):
  digit=n%10
  rev=rev*10+dig
  n=n//10
if(temp==rev):
    print("The number is palindrome")
else:
    print("The number is not palindrome") 
    
    
