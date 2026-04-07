# library-books-managment-system

Library Book Management System (C)

Description:
This is a simple console-based application written in C to manage library books.

Features:
- Add new books
- Display all books
- Search book by ID
- Issue book
- Return book
- Persistent storage using file (library.dat)

How to Compile:
Use any C compiler like GCC.

Command:
    gcc library.c -o library

How to Run:
    ./library

File Used:
- library.dat : Stores all book records in binary format.

Structure Used:
- Book (id, title, author, issued status)

Menu Options:
1. Add Book
2. Display Books
3. Search Book
4. Issue Book
5. Return Book
6. Exit

Notes:
- Ensure the program has permission to create/read files.
- Data is stored permanently unless the file is deleted.
