# python-Even-Odd
# Apporach-1
x = 24
if x % 24 == 0:
	print(x,"Is Even Number")
else:
	print(x, "Is Odd Number")
	y = 19
if y % 19 == 0:
	print(y,"Is Even Number")
else:
	print(y, "Is Odd Number")


 # Apporach-2
 num = int (input (“Enter any number to test whether it is odd or even: “)
if (num % 2) == 0:
              print (“The number is even”)
else:
              print (“The provided number is odd”)

  # Apporach-3
  # Using recursion function in python
  # defining the function having the one parameter as input
def evenOdd(n):	
 # if remainder is 0 then num is even
	if(n==0):
		return True
# if remainder is 1 then num is odd
	elif(n==1):
		return False
	else:
		return evenOdd(n-2)
num=33
if(evenOdd(num)):
	print(num,"num is even")
else:
	print(num,"num is odd")


  

