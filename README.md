# Conditional-statement-

#if
a = 10
if a > 5:
    print("A is greater than 5")
    #output: A is greater than 5



#if else 
    a = 10

if a > 5:
    print("Greater")
else:
    print("Smaller")
    #output: Smaller



    #if elif else
marks = 75

if marks >= 90:
    print("Grade A")
elif marks >= 60:
    print("Grade B")
else:
    print("Grade C")
    #output: Grade B


    #nested if else
age = 20

if age >= 18:
    if age >= 21:
        print("Age is 21 or above")
    else:
        print("Age is between 18 and 20")
else:
    print("Age is below 18")
    #output: Age is between 18 and 20
