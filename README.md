# myprogram
'''
Created on 04-Apr-2017
@author: AL1820

A) Create a program that asks the user to enter their name and their age.
Print out a message that tells them the year that they will turn 50 and
100 years old.

B)Add on to the previous program by asking the user for another number and
printing out that many copies of the previous message.
'''

name = input("enter the name")
age = int(input("enter the birth age"))
current_year = int(input("enter the current year"))
birth_year = (current_year - age)
print(name , "will be 50 year old in " , birth_year + 50)
print(name , "will be 50 year old in " , birth_year + 100)


num = int (input("enter the number"))
for i in range(num) :
    print("my name is SID")
