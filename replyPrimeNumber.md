# PrimeNumber
Is it a Prime Number?

y = int(input("Enter a postive integer numbet to check if it is a Prime Number :  "))
counter = 0
prime = 0
for i in range(1,y):
  if y % i == 0:
    counter += 1
    
if (y==0) or (y==1) or (counter>=3):
  print(y," is NOT a Prime Number.")
else:
  print(y," is a Prime Number.")
