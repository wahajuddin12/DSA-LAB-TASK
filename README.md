# DSA-LAB-TASK
DSA LAB TASK 1
# Task 1 of palindrome.

name=str(input("Enter your name:"))

print("Name is:",name)

reverse = name[::-1]

print("Reverse name is:",reverse)

if name==reverse:
  print("Name is palindrome:")
else:
  print("Name is not palindrome:")

#TASK 2:
def isbalanced(s):
    while(len(s)!=0):
        s = s.replace('()', "")
        s = s.replace('[]', "")
        s = s.replace('{}', "")
    if(len(s)== 0):
        return True
    else:
        return False
s=input('Enter a string of brackets:')
print('Given string is balanced:',isbalanced(s))
