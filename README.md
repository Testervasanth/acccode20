# balance amount
b=int(input("enter the total"))
w=int(input("enter the withdraw amount"))
if w%5==0 and w<b:
 print(b-w-0.50)
else:
 print(b)
