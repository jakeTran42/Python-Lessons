# Flow Control
# Flow control

### What is flow control

In the programs we have seen till now, there has always been a series of statements faithfully executed by Python in exact top-down order. What if you wanted to change the flow of how it works? For example, you want the program to take some decisions and do different things depending on different situations, such as printing 'Good Morning' or 'Good Evening' depending on the time of the day?

This is achieved using control flow statements. There are three control flow statements in Python - ```if - else, for and while```

### The ```if``` statement

The ```if``` statement is used to check a condition: if the condition is true, we run a block of statements (called the if-block), else we process another block of statements (called the ```else```-block). The else clause is optional.

#### Example input

```python
number = 23
guess = int(input('Enter an integer : '))

if guess == number:
    # New block starts here
    print('Congratulations, you guessed it.')
    print('(but you do not win any prizes!)')
    # New block ends here
elif guess < number:
    # Another block
    print('No, it is a little higher than that')
    # You can do whatever you want in a block ...
else:
    print('No, it is a little lower than that')
    # you must have guessed > number to reach here

print('Done')
# This last statement is always executed,
# after the if statement is executed.
```

#### Example Output

```python
Enter an integer : 50
No, it is a little lower than that
Done
```

### Example diagram for flow control (How it works)

![flowchart](https://365datascience.com/wp-content/uploads/2018/07/image9-min-1.png "Logo Title Text 1")

You are also able to chain/nest these ```if-elif-else``` statement together and do multiple condition at once.
Some programs may have a code block under an “if” clause. And it could have subsequent conditional blocks.
In such a case, Python allows nesting of an if-else or if-elif-else inside another conditional clause.
Python doesn’t limit the level of nested conditions in a program. Given below is the syntax of a multi-level nested if-elif-else statement.

Like so...
```python
if Logical_Expression_1 :
    if Logical_Expression_1.1 :
        if Logical_Expression_1.1.1 :
            Indented Code Block 1.1.1
        else
            Indented Code Block
    elif Logical_Expression_1.2 :
        Indented Code Block 1.2
    else :
        Indented Code Block
elif Logical_Expression_2 :
    Indented Code Block 2
elif Logical_Expression_3 :
    Indented Code Block 3
...
else :
    Indented Code Block

```

### Resources

https://automatetheboringstuff.com/2e/chapter2/

https://python.swaroopch.com/control_flow.html

https://www.youtube.com/watch?v=n9TQZIiFiQs