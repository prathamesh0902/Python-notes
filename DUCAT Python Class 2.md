# Input - Output Functions

## Output



```print("Addition = ", add)

print("Addition of ", num1, " and ", num2, " is: ", add)

print("Addition of {1} and {0} is {2}".format(num1, num2, num1 + num2))

print("Addition of {} and {} is {}".format(num1, num2, num1 + num2))



print(f"Addition of {num1} and {num2} is {num1 + num2}")


print(f"Addition = {num1 + num2} \\n Subtraction = {num1 - num2} \\n Multiplication = {num1 \* num2} \\n Division ={round(num2/num1,2)}")

print("Division of {} and {} is {:.2f}".format(num1, num2, num1 / num2))
```


## Input

Input value as a string
```

df = input("Enter your age:")

df = int(input("Enter your age:"))
```


Evaluate value as an int / float
```

df = eval(input("Enter your age:"))

num3 = eval(input(f"Dear {name}, pick a number :"))
```




# Control Statements

> Control the flow of execution



Conditional Statements: if, else, elif

Loop Statements: for, while


```
if condition1 operator1 condition2:

	statement1

	statement2

statement3




n = 10

if n < 100:

	print("is less than 100")

else

	print("is greater than 100")
```




Even - Odd
```

if n % 2 == 0:

 	print("is Even")

else:

```

Predict as positive / negative, even / odd



Polindromic number

abs(): Absolute value




```
n = 25

if n < 20:

 	print("A")

elif (n >= 20 and n < 40):

 	print("B")

else:

	print("C")
```



Use: strip, .lower(), .upper()


```
while condition1 operator1 condition2:

 	statement1

 	statement2

statement3
```


While loop 
- iterates untill the condition is valid
- increment / decrement is to be adjusted manually


```
while n < 100:

	print(n, end = " ")
```




Print Numeric Tables

Prime / Non-prime


```
while

	if

		break

else

	print("Number is prime")
```


Polindromic number

Armstrong Number

Magical Number



For Loop
- iterates fixed number of times
- self increment


```
for i in range(10, 21):
```


enumerate(): access index and element values
```
list = \[2, 5, 7, 12, 15]

for i, j in enumerate(list):

for i, j, k in zip (list1, list2, list3):

for i, j in dict.items():

	print(i, j)
```






```
# Print even numbers from list of heterogenous data types
n1 = \[7878, \[74, 22], {1012: 56, 303: 88}, (10, 15, 20), {44, 55, 66}, \[90, 91]]



for i in n1:

   # Check if the element is directly an integer or float

   if type(i) == int or type(i) == float or type(i) == complex:

       if i % 2 == 0:

           print(f"Even integer: {i}")

           

   # Handle containers (lists, tuples, sets, and dictionary values)

   else:

       # If it's a dictionary, we need to check both the values

       if type(i) == dict:

           for key, val in i.items():

               if type(val) in \[int, float] and val % 2 == 0:

                   print(f"Even dict value: {val}")

       

       # If it's a list, tuple, or set, we iterate through the elements

       elif type(i) in \[list, tuple, set]:

           for item in i:

               if type(item) in \[int, float] and item % 2 == 0:

                   print(f"Even {type(i).\_\_name\_\_} item: {item}")



   print("Above are the elements of", type(i))

```



List Comprehension


```
even\_numbers = \[i for i in list if i % 2 == 0]


category = \["A" if n < 20 else "B" if n <= 40 else "C" for i in list]


dict2 = {i: i\*\*2 for i in range(2, 11)}


dict3 = {i: 'Even' if i % 2 ==0 else 'Odd' for i in list}

```




