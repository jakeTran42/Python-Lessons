### Homework #12

Please use an editor/intepreter to write these programs.

You can use any of the following suggested editors:

```
https://repl.it/languages/python3  (online)

https://code.visualstudio.com/ (local)
```

### Read these materials to understand the fundamnetals of Linked List vs Array Data stuctures:

Video:
https://www.youtube.com/watch?v=lC-yYCOnN8Q

Write Up:
https://dbader.org/blog/python-linked-list

Type of Strcutures:
https://www.datacamp.com/community/tutorials/data-structures-python

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

3. Write a method to return the size or count of a linked list.

Sample

```
items = singly_linked_list()
items.size()

>>> 5
```

4. The delete method traverses the list in the same way that search does, but in addition to keeping track of the current node, the delete method also remembers the last node it visited. When delete finally arrives at the node it wants to delete, it simply removes that node from the chain by “leap frogging” it. Write a function to delete an iitem from the linkedlist from a parameter that is given. If the item does not exist then return None.

Sample

```
items = singly_linked_list()
items.deleteNode("apple")
```

5. Inserting between 2 nodes. Write a method that will insert a new node after an existing node. 

Sample

```
items = singly_linked_list()
items.insertNode("Apple", "Blue")

>>Apple
>>Blue
>>Orange
>>Python
>>Hello
>>World
```



Resource:

https://www.tutorialspoint.com/python_data_structure/python_linked_lists.htm
