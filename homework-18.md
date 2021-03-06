### Homework #18

Please use an editor/intepreter to write these programs.

You can use any of the following suggested editors:

```
https://repl.it/languages/python3  (online)

https://code.visualstudio.com/ (local)
```

### Read these materials to understand the fundamentals of Linked List vs Array Data structures:

Video:

https://www.youtube.com/watch?v=lC-yYCOnN8Q

Write Up:

1. https://realpython.com/linked-lists-python/
2. https://dbader.org/blog/python-linked-list
3. https://stackabuse.com/linked-lists-in-detail-with-python-examples-single-linked-lists/

Type of Structures:

https://www.datacamp.com/community/tutorials/data-structures-python

### Homework

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

# Advantages of Array

Easier to use and access
Faster access to the elements

# Disadvantage of Array

Fixed size - the size of the array is static

One block allocation - if you don't have enough memory to provide a single block (but you have sufficient scattered memory blocks) to allocate the space for the array then you'll need to defragment and other similar stuff to first create a free block of that size. So you may like to term it as improper utilization of memory

Complex position-based insertion - if you want to insert an element at a position already covered by some other element then you got to shift right by one position all the elements to the right of that position. This will vacate the position for you to insert the new element at the desired position. The more elements you have to the right of the desired position, the more expensive the process will be


# Advantage of Linked list

Flexibility - insert at (or delete from) any position in contant time

No single allocation of memory needed - fragmented memory can be put to a better use

Dynamic allocation - the size is not required to be known in advance

# Disadvantage of Link List

Complex to use and access - relatively complex as compared to arrays

No constant time access to the elements - simply because it doesn't involve the simple arithmetic used by arrays to compute the memory address, so relatively inefficient as compared to arrays


Starter Code:

```
class Node:
  # function
  def __init__(self, data=None):
    self.data = data
    self.next = None

class LinkedList:
  def __init__(self):
    self.head = None
    # self.tail = None
  
  def prepend(self, data):
    """ Insert an element to beginning of list"""
    
    if self.head ==  None:
      self.head = Node(data=data, next=self.head)
  
  def append(self, data):
    """ Insert element to end of list """
    
    # If Linked list doesnt have any data, append data to head
    if self.head == None:
      self.head = Node(data=data)
      return
    # If linked list already have data, loop through list until find the end of list and then append data
    current = self.head
    while current.next:
      current = current.next
    current.next = Node(data=data)

  def search(self, item):
    # Loop through Link List
    # if Item == Data return true
    # if end of list , return false
    pass

  
  def display(self):
    """ print out the elements inside linked list """
    
    current = self.head
    while current is not None:
      print(current.data, end="|")
      current = current.next

myList = LinkedList()

myList.append("Boston")
myList.append("New York")
myList.append("SF")


myList.display()
```



Resource:

https://www.tutorialspoint.com/python_data_structure/python_linked_lists.htm
