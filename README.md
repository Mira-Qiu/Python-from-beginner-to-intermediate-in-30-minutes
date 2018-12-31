# Python-from-beginner-to-intermediate-in-30-minutes

## Math
```py
2**3 = 2*2*2
pow(2,2)
```

## Variable
```py
x = int(input("Ënter a number:"))
print(x+8)
```

## Modules and Functions
```py
import math
math.sqrt(81)
```

## Strings
```py
a = str(18)
"I am "+ a
```

## Sequences and Lists
```py
animals = ["dog","cat","lion","tiger"]
animals[2]     #'lion'
animals[-2]    #'lion'
```

## Slicing or Grouping
```py
example = [0,1,2,3,4,5,6,7,8,9]
example[2:8]  #[2, 3, 4, 5, 6, 7]
example[-5:-1]  #[5, 6, 7, 8]
example[:]  #[0,1,2,3,4,5,6,7,8,9]
example[:5]   #[0,1,2,3,4]
example[5:]  #[5,6,7,8,9]
example[:5]   #[0,1,2,3,4]
```

## Sequences and basic searching

```py
a =[ 0,1,2,3]
b = [4,5,6,7]
a+b
# [0, 1, 2, 3, 4, 5, 6, 7]
name ="mingming"
'k'in name
'g'in name
#True
```

## More operation and sequences and lists
```py
numbers = [21,30,23,45,67,78]
len(numbers)  #6
max(numbers)   #78
min(numbers)   #21

list("gautam")
#['g', 'a', 'u', 't', 'a', 'm']

example = list('simplebook')
example
# ['s', 'i', 'm', 'p', 'l', 'e', 'b', 'o', 'o', 'k']
example[6:] =list('nameis make')
example
# ['s', 'i', 'm', 'p', 'l', 'e', 'n', 'a', 'm', 'e', 'i', 's', 'a', 'k', 'e']
```

## Introduction to methods
```py
example =['computer','random','keyboard']
example.append('random')
example
# ['computer', 'random', 'keyboard', 'random']

numbers =[1,2,3,1,3,4,2,4,5,3]
numbers.count(1)
# 2 （1出现 2次）

numbers = example + numbers
numbers
#  ['computer', 'random', 'keyboard', 'random', 1, 2, 3, 1, 3, 4, 2, 4, 5, 3]

numbers.extend(example)
numbers
#['computer', 'random', 'keyboard', 'random', 1, 2, 3, 1, 3, 4, 2, 4, 5, 3, 'computer','random', 'keyboard', 'random']
 ```
 
 ## For loop
```py
 for item in numbers:
  print("Ï have " + item)
  
 while True:
  text = input("Enter something: ")
  if(text == "quit" ) : break
```

## User defined functions
```py
def gbp_to_usd(gbp):
  usd = gbp * 1.5
  return usd
  
usd = gbp_to_usd(5)
print(usd)

# 7.5
```

## Function parameter
```py
def  printname(name):
  print(name)  # only 1 positional argument
  
def printname(*name):
  print(name)  #can take a list of names as argument
  
def printname(name,age):
  print(name)
  print(age)
```

## Class, Objects, Metods

self： like a tempera object for this class, and gives the access variables and functions of it. So, just keep the first parameter is self when you create a method
```py
class calculator:
  def add(self,a,b):
    return a+b
  def sub(self, a,b):
    return a-b
    
clac = calculator()
result = clac.add(5,2)
print(result)
```
```py
class class1:
  var1 ="I am class1"
class class2:
  var2 ="I am class2"
class class3(class1,class2):
  var3="Ï am class3"
  
example = class3()
example.var1
example.var2
```

## Reading and writing into file
```py
file = open('g:/test.txt','w')
file.write("this is my first file")
file.close()
file.open('g:/test.txt','r')
file.read(10)
file.read()
```

