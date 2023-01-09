# How-many-years-you-will-live-
Python program to predict how much days left for you to see this repository.

age = input("What is your current age?")
A = int(input("How many years do you want to live ?"))
b = int(age)
d = (A*365)-(b*365)
w = (A*52)-(b*52)
m = (A*12)-(b*12)
print(f"You have {d} days, {w} weeks, and {m} months left")
