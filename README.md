'''write a progtram to find the smallest of two numbers using if-else condition
a=-4
b=-99'''
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
if a<b:
    small=a
else:
    small=b
print("small value is",small)

output=========
enter the value of a: -4
enter the value of b: -99
small value is -99


'''write a program to enter a character (a to z) , if the entered character is in lowercase convert into uppercase''' 
char=input("enter any character from a-z")
if char>='A' and char<='Z':
    char=char.lower()
    print("converted case of input char:",char)
else:
    char=char.upper()
    print("converted case of input char:",char)

output=========
    enter any character from a-z i
    converted case of input char: I


'''write a program to enter a character (a to z) , if the entered character is in lowercase convert into uppercase''' 
char=input("enter any character from a-z")
if char>='A' and char<='Z':
    char=char.lower()
    print("converted case of input char:",char)
else:
    char=char.upper()
    print("converted case of input char:",char)


    output=========
    enter any character from a-z S
    converted case of input char: s


'''check whether the given input is a leap yeqar for 4 years and centuries by if-else'''
year=int(input("enter year:"))
if year%4==0 or year%100==0 or year%400==0:
    print(year,"is a leap year")
else:
    print(year,"is not a leap year")


    output=======
enter year: 2023
2023 is not a leap year


'''check whether the given input is a leap yeqar for 4 years and centuries by if-else'''
year=int(input("enter year:"))
if year%4==0 or year%100==0 or year%400==0:
    print(year,"is a leap year")
else:
    print(year,"is not a leap year"

    output========
    enter year: 2024
    2024 is a leap year


