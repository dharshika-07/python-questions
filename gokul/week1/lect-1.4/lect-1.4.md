- L1.4: A Quick Introduction to Variables
    - https://youtu.be/Yg6xzi2ie5s


1) What does the following code do?
```
a=10
print(a) =10
```

2) What does the following code do?
```
a=10
print(a)
b=20
print(b) 
10 
20
```
3) What does the following code do?
```
a=10
print(a)
b=20
print(b)
print(a+b)
print(a*b)
output
10
20
30
200
```

4) what will be the output of below code?
```
a=10
print(a)
a=a+1
print(a)\
output
10
11
```

5) what will be the output of below code?
```
a=10
print(a)
a=a+1
print(a)
a=a+1
print(a)
output 
10
11
12
```
6) what will be the output of below code?
```
a=10
print(a)
a=a+1
print(a)
a=a+1
print(a)
a=a+1
print(a)
output  
10
11
12
13
```


7) What will be the output?
```
print("Enter a number:")
n=int(input())
print(n)
print(n+1)
print(n+2)
print(n+3)
output 
5
5
6
7
8
```

8) How would you take input from Command line and print it?
#x=input()
#print(type(x))
#what will be the output if i give "gokul" in command line?
#what will be the output if i give 12.2 in command line?
#what will be the output if i give 12 in command line
output for all 3 questions
<class 'str'>

a8) What will be the output, if i give 12.2 as input?
```
n=int(input())
 print(n)
  output -ValueError: invalid literal for int() with base 10: '12.2' 
  debug  if we add integer but not in decimal it works


 2) # what will be the output?
x="hello"
print(type(x))

y="10.5"
print(type(y))
# convert y's datatype to  float


z=10.5
print(type(z))
# what is the datatype of z?

z = int(z)
print(z)
print(type(z))
# convert z to an integer


output 
<class 'str'>
<class 'str'>
<class 'float'>
10  (10 is added because z=10.5 it is in decimal but in int it should be a whole number so the z value is been  given)


3 

# predict the output
#x="10.5"
#a="21"
#b=int(a)
#y=int(x)
#print(a)
#print(type(x))
#print(type(y))
# this creates value error so when we change the code 
x = "10.5"
a="21"
b=int(a)
y = int(float(x))

print(a)
print(type(x))
print(type(y))

output 
21
<class 'str'>
<class 'int'>
<class 'int'>  
9) Take an input from command line as "GOKUL" and store it in a variable 'a' , what will be the output?
```
LINE-1
print(a*2)
```

10) Replace LINE-1 and LINE-2, so that we take input from user,  a number as input form user and we should print the square of the number as output.
```
LINE-1
LINE-2
```
