Level 1 Function Quiz 

### 1. What is the default return value for a function that does not return any value explicitly?

  A. None

  B. int

  C. double

  D. public

  E. null
  

### 2. Which of the following items are present in the function header?

A. function name

B. function name and parameter list

C. parameter list

D. return value


### 3. Which of the following enclose the input parameters or arguments of a function?

A. brackets

B. parentheses

C. curly braces

D. quotation marks


### 4. Which of the following keywords marks the beginning of the function block?

A. fun

B. define

C. def

D. function


### 5.  Which of the following function definition does not return any value?

A. a function that prints integers from 1 to 100.

B. a function that returns a random integer from 1 to 100.

C. a function that checks whether the current second is an integer from 1 to 100.

D. a function that converts an uppercase letter to lowercase.


### 6.  Which of the following statements correctly represent the function body in the given code snippet?
```
def f(number):
  # Missing function body
print(f(5))
```
A. return “number”

B. print(number)

C. print(“number”)

D. return number


### 7.  What is the output of the following code snippet?
```
def func(message, num = 1):
    print(message * num)
 
func('Welcome')
func('Viewers', 3)
```
A. Welcome
Viewers
B. Welcome
ViewersViewersViewers
C. Welcome

### 8.  What is the output of the following code snippet?
```
def myfunc(text, num):
    while num > 0:
        print(text)
     num = num - 1

myfunc('Hello', 4)
```
A. HelloHelloHelloHelloHello

B. HelloHelloHelloHello

C. invalid call

D. infinite loop

### 9. What is the output of the following code snippet?
```
def func(x = 1, y = 2):
    x = x + y
    y += 1
    print(x, y)
func(y = 2, x = 1)
```
A. 1 3

B. 2 3

C. The program has a runtime error because x and y are not defined.

D. 3 2

E. 3 3

### 10. What is the output of the following code snippet?
```
num = 1
def func():
    num = 3
    print(num)

func()
print(num)
```
A. 1 3

B. 3 1

C. The program has a runtime error because x is not defined.

D. 1 1

E. 3 3

### 11. Which of the following function headers is correct?
A. def f(a = 1, b):

B. def f(a = 1, b, c = 2):

C. def f(a = 1, b = 1, c = 2):

D. def f(a = 1, b = 1, c = 2, d):

### 12. What is the output of the following code snippet?
```
num = 1
def func():
    num = num + 3
    print(num)

func()
print(num)
```
A. 1 4

B. 4 1

C. The program has a runtime error because the local variable ‘num’ referenced before assignment.

D. 1 1

E. 4 4
