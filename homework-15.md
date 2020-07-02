### Homework #15

Please use an editor/intepreter to write these programs.

You can use any of the following suggested editors:

```python
https://repl.it/languages/python3  (online)

https://code.visualstudio.com/ (local)
```

1. Write a Python program to find missing numbers from a list.

```python
print(missing_numbers([1,2,3,4,6,7,10]))

>>> Missing number: 5
```

2. Write a Python program to find the single number in a list that doesn't occur twice.

```python
arr = [1,4,3,2,5,3,2,4,1]
single_number(arr)

>>> 5
```

3. Write a Python program to find the largest prime factor of a given number.

```
Largest_Prime_Factor(330)

>>> 11
```

### Handling Error Practice

* Find the errors/bug and fix it so that the program can run correctly.

The FizzBuzz problem: 
For all integers between 1 and 99 (include both):

    # print fizz for multiples of 3
    
    # print buzz for multiples of 5 
    
    # print fizzbuzz for multiples of 3 and 5"

1. 

```python
def fizzbuzz(max_num):
    "This method implements FizzBuzz"
    
    # adding some redundant declarations on purpose
    # we will make our script 'tighter' in one of coming exercises
    three_mul = 'fizz'
    five_mul = 'buzz'
    num1 = 3
    num2 = 5 

    # Google for 'range in python' to see what it does
    for i in range(1,max_num):
        # % or modulo division gives you the remainder 
        if i%num1==0 and i%num2==0:
            print(i,three_mul+five_mul)
        elif i%num1=0:
            print(i,three_mul)
        elif i%num2==0:
            print(i,five_mul)
```

2. 

```python
def fizzbuzz(max_num):
    "This method implements FizzBuzz"
    
    # adding some redundant declarations on purpose
    # we will make our script 'tighter' in one of coming exercises
    three_mul = 'fizz'
    five_mul = 'buzz'
    num1 = 3
    num2 = 5 

    # Google for 'range in python' to see what it does
    for i in range(1,max_num):
        # % or modulo division gives you the remainder 
        if i%num1==0 and i%num2==0:
        print(i,three_mul+five_mul)
        elif i%num1==0:
            print(i,three_mul)
        elif i%num2==0:
            print(i,five_mul)
```

Resources:

https://realpython.com/invalid-syntax-python/

https://automatetheboringstuff.com/2e/chapter11/

https://docs.python.org/3.3/tutorial/errors.html

https://forum.freecodecamp.org/t/beginner-practice-python-by-fixing-errors/245325
