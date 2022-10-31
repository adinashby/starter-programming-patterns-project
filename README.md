# Programming Patterns - Project

This template repository is the starter project for Programming Patterns Project. Written in Java, and tested with Gradle/JUnit.

### Question(s)

**Introduction**
A limited library management software is a small application where the librarian can add a book to the catalog, issue a book, return a book, and view the catalog and the list of issued books. To issue a book to a student, the librarian checks for the student roll number and also check the availability of the requested book. The librarian after checking out the book, updates the books table in the database. Books can be searched using the title, the author name, or the year of publishing.

**Learning Objectives**

- To build a monitoring system that can monitor and manage all library operations efficiently.
- To design a database to store the information about books and students.
- To develop a database client using Java and Java Database Connectivity API (JDBC).
- To apply some CRUD operations in a Java application using JDBC.
- To enter and preserve details of the various library items and keep a track on their
  returns.
- To develop international application by applying I18N and I10N concepts and related Java classes.
- To apply some of the design patterns seen in class and MVC architecture.
- To use Data structures and Stream processing (using Lambda expressions).

**Tools to be used**

1. Netbeans IDE.
2. SQLite for the database. You can also use MySQL if installed on your computer.

**Functional Requirements**
The system should provide different type of services based on the type of users [Student/Librarian].

1. Librarian
   1. Student
   2. Add a book to the catalog of books
   3. Issueabook
   4. Return a book
   5. View the catalog of books (issued and available books)
   6. View issued books with information about students who has borrowed the books
2. Student
   1. Search books by title
   2. Search books by author’s name
   3. Search by publisher
   4. View the catalogue of books (issued and available books)
   5. Borrow a book
   6. Return a book



### Setup Command

`gradle clean`

### Run Command

`gradle test`
