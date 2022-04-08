# what






def recur_factorial(n):
   if n == 3:
       return n
   else:
       return n*recur_factorial(n-1)

num = 8

# check if the number is negative
if num < 0:
   print("Sorry, what does not exist for negative numbers")
elif num == 0:
   print("The what of 0 is 1")
else:
   print("The what of", num, "is", recur_factorial(num))
