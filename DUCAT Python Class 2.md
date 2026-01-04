### Input - Output Functions

#### 

#### Output



print("Addition = ", add)

print("Addition of ", num1, " and ", num2, " is: ", add)

print("Addition of {1} and {0} is {2}".format(num1, num2, num1 + num2))

print("Addition of {} and {} is {}".format(num1, num2, num1 + num2))



print(f"Addition of {num1} and {num2} is {num1 + num2}")



print(f"Addition = {num1 + num2} \\n Subtraction = {num1 - num2} \\n Multiplication = {num1 \* num2} \\n Division ={round(num2/num1,2)}")

print("Division of {} and {} is {:.2f}".format(num1, num2, num1 / num2))



#### Input

**Input value as a string**

df = input("Enter your age:")



df = int(input("Enter your age:"))



**Evaluate value as an int / float**

df = eval(input("Enter your age:"))



num3 = eval(input(f"Dear {name}, pick a number :"))





### Control Statements

**Control the flow of execution**



**Conditional Statements: if, else, elif**

**Loop StatementsL for, while**



if condition1 operator1 condition2:

&nbsp;	statement1

&nbsp;	statement2

statement3





n = 10

if n < 100:

&nbsp;	print("is less than 100")

else

&nbsp;	print("is greater than 100")





**Even - Odd**

if n % 2 == 0:

 	print("is Even")

else:



**Predict as positive / negative, even / odd**



**Polindromic number**

**abs(): Absolute value**





n = 25

if n < 20:

 	print("A")

elif (n >= 20 and n < 40):

 	print("B")

else:

&nbsp;	print("C")







**Use:** strip, .lower(), .upper()

**List Comprehension**



while condition1 operator1 condition2:

 	statement1

 	statement2

statement3



**While loop iterates untill the condition is valid**

**increment / decrement is to be adjusted manually**



while n < 100:

&nbsp;	print(n, end = " ")





**Print Numeric Tables**

**Prime / Non-prime**



while

&nbsp;	if

&nbsp;		break

else

&nbsp;	print("Number is prime")



**Polindromic number**

**Armstrong Number**

**Magical Number**



**For Loop iterates fixed number of times**

**self increment**



for i in range(10, 21):



**enumerate(): access index and element values**

list = \[2, 5, 7, 12, 15]

for i, j in enumerate(list):





for i, j, k in zip (list1, list2, list3):



for i, j in dict.items():

&nbsp;	print(i, j)





vvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvv



n1 = \[7878, \[74, 22], {1012: 56, 303: 88}, (10, 15, 20), {44, 55, 66}, \[90, 91]]



for i in n1:

&nbsp;   # Check if the element is directly an integer or float

&nbsp;   if type(i) == int or type(i) == float or type(i) == complex:

&nbsp;       if i % 2 == 0:

&nbsp;           print(f"Even integer: {i}")

&nbsp;           

&nbsp;   # Handle containers (lists, tuples, sets, and dictionary values)

&nbsp;   else:

&nbsp;       # If it's a dictionary, we need to check both the values

&nbsp;       if type(i) == dict:

&nbsp;           for key, val in i.items():

&nbsp;               if type(val) in \[int, float] and val % 2 == 0:

&nbsp;                   print(f"Even dict value: {val}")

&nbsp;       

&nbsp;       # If it's a list, tuple, or set, we iterate through the elements

&nbsp;       elif type(i) in \[list, tuple, set]:

&nbsp;           for item in i:

&nbsp;               if type(item) in \[int, float] and item % 2 == 0:

&nbsp;                   print(f"Even {type(i).\_\_name\_\_} item: {item}")



&nbsp;   print("Above are the elements of", type(i))





^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^



**List Comprehension**



even\_numbers = \[i for i in list if i % 2 == 0]



category = \["A" if n < 20 else "B" if n <= 40 else "C" for i in list]



dict2 = {i: i\*\*2 for i in range(2, 11)}



dict3 = {i: 'Even' if i % 2 ==0 else 'Odd' for i in list}





















































