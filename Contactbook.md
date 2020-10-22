### Contacbook Project

#### Project Assignment

The purpose of the project is to simulate a contact book using Python. A contact book or an address book is a book/list or a database used for storing entries called contacts. Each contact entry usually consists of a few standard fields.
In this assignment, you’ll be creating a program called contactbook.py which allows the user to manage a list of contact information. The main program will allow the user to enter, edit, view, and delete the records in the
virtual address book, which should include a person’s names, email address, phone numbers, etc.

#### Requirements

1. A contact book must include these fields for a user:

* Full Name
* Address
* Phone number
* Email

Example: ```{"name": "John Doe", "address": 1234 Washington San Francisco", "number": 123456789, "email": "John@gmail.com"}```

2. A contact book must have these functionalities:

* Ability to add a contact to the contactbook
* Ability to delete contact from contacbook
* Ability to edit a contact from contactbook
* Ability to find if a contact exist in the contact book

### Getting started

You are free on how you want to store your data but there are 2 ways you can store contacts. One way is to store in memory (in an array) and the second way is to store the contact in a text file.

You are free to google answers and get help from other sources.

### Helpful resources

https://www.crashwhite.com/introcompsci/materials/assignments/activities-projects/project-addressbook.pdf

### First exmaple

```
contactbook = []

def add_contact(name, address, email, number):
  new_contact = {"name": name, "address": address, "email": email, "number": number}
  contactbook.append(new_contact)
  
# def delete_contact():


# def edit_contact():


# def find_contact():

add_contact("john", "1234 Adress", "john@gmail.com", 21356342)

print(contactbook)
```
