# Project Title: 
Library Book Database
# Section: 
9-Lithium
# Group Members: 
Donina, Lim, Nucum
# Date: 
Nov 13, 2026

# Project Description: 
Summary: The program can display information about a book in a library. This serves to promote convenience and accessibility of library services.

# Components:
Class descriptions, attributes, and methods:
Our program has a library, book, aisle, and student class.
The library class represents a general storage where all the book classes and aisle classes exist. It has a "name", "list of books", and "list of aisles" attribute.
It has a "book search" and "aisle search" method.
The book class is the class that contains the attributes and information the user is looking for. The book classes exist in the library. It has a "name", "copies", "available copies", and "borrowed copies" attribute.
The aisle class is a storage smaller than the library class that book classes exist in. The aisle classes also exist in the library. It has an "id" and "list of books" attribute. It has a "book search" method.
The student class is completely independent of other classes and can "borrow" book classes. They can change the attributes of a book class. It has a "name" attribute. It has a "borrow" method.

Features:
The program will print an error message if the "book search" method doesn't find the book searched for.

Expected outputs:
The program allows you to change and can output the name of a book, number of copies total, number of copies available, number of borrowed copies at the moment, what library aisle you can find the book in, and the name of a borrower. It also will say if the book asked for isn't in the library's list of books. 

Class interactions:
- The name of a book involves a book class, its "name" attribute, and the library class, and its "list of books" attribute.
- The number of copies total involves a book class and its "copies" attribute
- The number of copies available involves a book class, its "available copies" attribute, and a student class, and its "borrow" method
- The number of copies borrowed involves a book class, its "borrowed copies" attribute, and a student class, and its "borrow" method
- The library aisle of a book involves an aisle class, its "id" attribute, and its "list of books" attribute
- The name of a borrower involves a student class and its "name" attribute
- 

# Target demographics:
Our program targets users that do not have information on a book in a library that they want to borrow. Our program allows them to find these books, if its in the library, if they can borrow it, and where they can find it.

# Class Diagram:
<img width="720" height="410" alt="image" src="https://github.com/user-attachments/assets/0a83a645-3f48-407d-ab7c-06648da02bff" />

# Goals & Objectives:
Our project will be able to function as a library database that can search for the data of a book in the library when requested.
1. Make a Class Diagram
2. Create the Book search system
3. Allow Student classes to borrow and change the "copies", "available copies", and "borrowed copies" of a Book class
4. Introduce input validation so user inputs won't break the system
