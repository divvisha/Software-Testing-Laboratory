# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:  20/08/2024                                                                         
### REGISTER NUMBER : 212221040044

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.

### Program:
### i.)do…while:
~~~
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display() 
~~~
### ii.) while…do
~~~
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")
~~~
### iii.) switch
~~~
def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch() 
~~~
### iv.) if-else
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
        print(“Enter a valid number.”) 
~~~
### v.) for
~~~
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
~~~

### Output:
### i.) do...while
![Screenshot 2024-10-04 110314](https://github.com/user-attachments/assets/e01bfc86-f693-4132-8560-5203f48c5642)
### ii.) while...do
![Screenshot 2024-10-04 110453](https://github.com/user-attachments/assets/fbc0f480-4a3c-4d4a-ba0c-f28d4266b0fe)
### iii.) switch
![Screenshot 2024-10-04 110628](https://github.com/user-attachments/assets/990c734e-dccc-446b-88b2-46f9443b4e90)
### iv.) if-else
![Screenshot 2024-10-04 110817](https://github.com/user-attachments/assets/9d441b31-e88b-4e94-98f9-23c4792593e2)
### v.) for
![Screenshot 2024-10-04 102135](https://github.com/user-attachments/assets/d175f458-e8a6-4888-bb6f-4405f768e89f)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


