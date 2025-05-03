# 19CS301 Module8

## EXPT NO.8a Program to find Find the simple interest

### Aim: To Find the simple interest by getting the principal, rate and time value from the user simple interest = (principal*rate*time)/100 [Note: Time must be in year so convert 9 months to year format]

### Algorithm:
1.Read principal p, rate r, and time t (accept fractions like 9/12).

2.Define function simpleInterest(p, t, r) to return (p * r * t)/100.

3.Call the function with input values.

4.Display the result.

### Program:
```
## Reg no:212223020018
## Name: Mohamed Jafin S
p=int(input())
r=float(input())
t=eval(input())
def simpleInterest(p,t,r):
    return (p*r*t)/100
```
### Output:
![image](https://github.com/user-attachments/assets/8c94c86c-6bb6-4aa0-ab52-2a7a005baf2f)

### Result: 
Thus, the given program is implemented and executed successfully .

## EXPTNo.8b program to display elements from a list, present at odd index positions

### Aim: To Write a python program to display elements from a list, present at odd index positions

### Algorithm:

STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a list and a variable a.

STEP 4: Get the input of a from user.

STEP 5 : Using loop get the inputs and append in list.

STEP 6: Using another loop print the elements in the odd index position of the list. 

STEP 7: Stop.

### Program:
```
## Reg no:212223020018
## Name: Mohamed Jafin S
arr = []

n=int(input())

for i in range(n):
    arr.insert(i, int(input()))
for i in range(n):
    if i%2!=0:
        print(arr[i],end=" ")
```
### Output:
![image](https://github.com/user-attachments/assets/e6bdeef3-21aa-47fc-b410-7aa06fc779bd)

### Result:
Thus, the given program is implemented and executed successfully .
 

## EXPT NO>8C Write a program that has a dictionary of names of students and their marks in five subjects. Create another dictionary from this dictionary that has the name of the students and their total marks. Find out the topper and the score.

### Aim: To Write a program that has a dictionary of names of students and their marks in five subjects.

### Algorithm:
1.Accept a dictionary with student names and list of 5 subject marks.

2.Create a new dictionary to store total marks using sum().

3.Loop through totals to find the maximum value and corresponding student.

4.Print the total marks and topper.

### Program:
```
## Reg no: 212223020018
## Name:Mohamed Jafin S
marks=eval(input())
total=0
total_marks=marks.copy()
for key,val in marks.items():
    total=sum(val)
    total_marks[key]=total
print(total_marks)
max=0
topper=''
for key,val in total_marks.items():
    if val>max:
        max=val
        topper=key
print("Topper is: ",topper,"with marks = ",max)
```

### Output:
![image](https://github.com/user-attachments/assets/f5d62fa3-0c07-4c52-9847-0b2eeaaa51ae)
 
### Result:
Thus, the given program is implemented and executed successfully .
 

## EX: 8.d program to square all the even numbers and cube all odd numbers from a list of integers

### Aim: To Develop a python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list.

### Algorithm:

STEP 1: Start.

STEP 2: Create a variable f and l for upper and lower limit of list. STEP 3: Get the value of f and l from user.

STEP 4: Create a list.

STEP 5 : Get the input from user and append in the list. STEP 6: Create a lambda function to calculate the result. STEP 7: Print the result.

STEP 8 : Stop.

### Program:
```
## Reg no:212223020018
## Name:Mohamed Jafin S
cube = lambda x: x**2 if x%2==0 else x**3
def fun(f,l):
     l1=[]
     for i in range(f,l+1):
           l1.append(i)
      return l1
f,l = int(input()),int(input())

```
### Output:
![image](https://github.com/user-attachments/assets/0e8098a3-6593-439f-8f4e-08aaa5bee552)

### Result: 
Thus, the given program is implemented and executed successfully .

## EX: 8.e

### Aim: Write a python program to read and  then print the integer variable.men_stepped_on_the_moon= print()

### Algorithm:
1.Prompt the user to input an integer.

2.Convert the input to an integer using int().

3.Print the integer value.

### Program:
```
## Reg no:212223020018
## Name:Mohamed Jafin S
men_stepped_on_the_moon=int(input())

print(men_stepped_on_the_moon)

```
### Output:
![image](https://github.com/user-attachments/assets/6a7b1179-37d2-4170-b0a9-fa726d10ba2f)

### Result: 
Thus, the given program is implemented and executed successfully .
 
 
