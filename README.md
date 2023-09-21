# calculator-code-in-python
def add(a,b):
    return a+b
def sub(a,b):
    return a-b
def mul(a,b):
    return a*b
def div(a,b):
    if b==0:
        return"cannot divide by zero"
    return a/b
print(1,"add")
print(2,"sub")
print(3,"mul")
print(4,"div")
user=int(input("enter number:"))
a=eval(input("enter num:"))
b=eval(input("enter num:"))
if user==1:
    print("addition",add(a,b))
elif user==2:
    print("subtraction",sub(a,b))
elif user==3:
    print("multiplication",mul(a,b))
elif user==4:
    print("division",div(a,b))
else:
    print("invalid")
    
    
