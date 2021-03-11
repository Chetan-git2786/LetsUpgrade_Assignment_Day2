
This repo consists of two programs written in python 3.0 as part of the Day-2 Assignment given by the mentor at the LetsUpgrade 5 day workshop on "DataStructures and Algorithms"


# LetsUpgrade_Assignment_Day2
Day2_Assignment


""" Q1 : # Write a Python program that takes two numbers as the input such as 'X' & 'Y'
 and  print the result of X^Y"""

X=(int(input("Enter the value of X : ")))
Y=(int(input("Enter the value of Y : ")))
#print("Enter the value of Y : ",int(input())
#Y=int(input())
Z=int(X**Y)
#int(input(Y))
print("The value of '{}' raised to the power of '{}' is : {}" .format(X,Y,Z))


''' Q2 : Write a Python program to print the numbers in the list 
           which are divisible by 3 '''
lst1=[]

for i in range(1,50):
  if i%3==0:
    lst1.append(i)
print(lst1)  

