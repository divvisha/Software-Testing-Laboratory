# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 16/08/2024                                                                    
### REGISTER NUMBER : 212221040044

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.

### Program:
i). do...whhile
~~~
def display():
    start=input("Enter first number: ")
    end=input("Enter last number: ")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=' ')
            if start<end:
                start=start+1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()
~~~
ii). while...do
~~~
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
    start=int(start)
    end=int(end)
    while start<=end:
        print(start)
        start+=1
else:
    print("Enter a valid positive number.")
~~~
iii). if...else
~~~
def compare():
    a=input("Enter a value for A: ")
    b=input("Enter a value for B: ")
    try:
        a=int(a)
        b=int(b)
        if a>b:
            print("A is greater than")
        elif a<b:
            print("B is greater than")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.") 
compare()
~~~
iv). switch
~~~
def switch():
    switcher={
    0:"even",
    1:"odd"
    }

    n=input('Enter a value for N: ') 
    try:
        n=int(n)
        print(switcher[n%2])
    except ValueError:
        print("Enter a valid number.")
switch() 
~~~
v). for
~~~
def iterate():
    string=input("Enter a string: ") 
    for i in string:
        print(ord(i),end=" ")
iterate() 
~~~

### Output:
i). do...while
![Screenshot 2024-11-04 190336](https://github.com/user-attachments/assets/975fe389-940f-4988-9e90-94cdf0690c91)

ii). while...do
![Screenshot 2024-11-04 191104](https://github.com/user-attachments/assets/2952ce70-6aff-4678-aeea-acc428fd75a4)

iii). if...else
![Screenshot 2024-11-04 191349](https://github.com/user-attachments/assets/947bae06-7ac0-4cf6-8790-88db839ed1bb)

iv). switch
![image](https://github.com/user-attachments/assets/2efcf59c-1c3b-4333-8154-25fcfa96f7ab)

v). for
![image](https://github.com/user-attachments/assets/1d51edbf-6bfd-4b72-9520-8f179443bc9e)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


