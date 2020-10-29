### Homework #20

Please use an editor/intepreter to write these programs.

You can use any of the following suggested editors:

```
https://repl.it/languages/python3  (online)

https://code.visualstudio.com/ (local)
```


### 1. Write a function that returns

'Good' for numbers divisible by 7
'Food' for numbers divisible by 6
'Universe' for numbers divisible by 42
'Oops' for all other numbers
Only one output, divisible by 42 takes precedence

```
>>> six_by_seven(66)
'Food'
>>> six_by_seven(13)
'Oops'
>>> six_by_seven(42)
'Universe'
>>> six_by_seven(14)
'Good'
>>> six_by_seven(84)
'Universe'
>>> six_by_seven(235432)
'Oops'
```

### 2. With a given integral number n, write a program to generate a dictionary that contains (i, i*i) such that is an integral number between 1 and n (both included). and then the program should print the dictionary.
Suppose the following input is supplied to the program:

```
>>> generateDict(8)

Then, the output should be:
{1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64}
```

### 3. Write a function that returns product of all numbers of a list(array)
```
>>> product([1, 4, 21])
84
```

### 4. Write a Python program to count the most common words in an array(list) and record it in a dictionary (Or any data structure youre comfortable with).

```
Example

Given list: color_list = ["pink", "red", "blue", "blue", "red", "pink", "purple", "red", "blue", "pink", "red"]

>>> countWord(color_list)

{"pink": 3, "blue": 3, "red": 4, "purple": 1}
```
