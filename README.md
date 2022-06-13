# Is-It-A-Prime-Number-

num1 = 19
num2 = 10

if num1 > 1:

for i in range(2,num1):
if (num1 % i) == 0:
    print(num1,"is not a prime number")
    break
else:
    print(num1,"is a prime number")

else:
    print(num1,"is not a prime number")

if num2 > 1:
    for i in range(2,num2):
if (num2 % i) == 0:
    print(num2,"is not a prime number")
    break
else:
    print(num2,"is a prime number")

else:
    print(num2,"is not a prime number")

19 is a prime number 
10 is not a prime number
