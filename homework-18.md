### Homework #12

Please use an editor/intepreter to write these programs.

You can use any of the following suggested editors:

```
https://repl.it/languages/python3  (online)

https://code.visualstudio.com/ (local)
```

1. Write a Python program to create a singly linked list, append some items and iterate through the list.

Sample output:

```
items = singly_linked_list()
items.append_item('Apple')
items.append_item('Orange')
items.append_item('Python')
items.append_item('Hello')
items.append_item('World')

for val in items.iterate_item():
    print(val)

>>Apple
>>Orange
>>Python
>>Hello
>>World
```

2. Write a Python program to search a specific item in a singly linked list and return true if the item is found otherwise return false.

Sample output:

```
items = singly_linked_list()
items.append_item('Apple')
items.append_item('Orange')
items.append_item('Python')
items.append_item('Hello')
items.append_item('World')

if items.search_item('Grapes'):
    print("True")
else:
    print("False")
    
>> False
```

Resource:

https://www.tutorialspoint.com/python_data_structure/python_linked_lists.htm
