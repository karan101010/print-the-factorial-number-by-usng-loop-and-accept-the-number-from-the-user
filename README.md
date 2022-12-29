
#Write a python program to print the factorial of a given number and value accept from the user.
num=int(input("Enter the  number whose factorial you want :\n"))
f=1
for i in range(1,num+1):
    f=f*i
    print("Factorial is",f)
