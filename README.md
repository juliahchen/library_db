# Library Management System Database Project

## Project Description

This project will create a simple library management database system which includes basic functions needed by a library user. The project will focus on the following functions:

1. Search the library for a book by title or author
2. Check out a book from the library
3. Display currently checked out books for a user
4. Allow users to give books a rating
5. Display related books when returning a book
6. Report on “Top Books” of the library
7. View previously borrowed books for users
8. Allow user to delete account

Additional details:

- Database will be populated with an initial store of various books and tags. The csv files were downloaded from a Github project, goodbooks-10k (https://github.com/zygmuntz/goodbooks-10k/tree/master), where the data was originally sourced from GoodReads. I have cleaned and reduced the data to a more manageable size for this project.
- There will only be one copy of each book available to borrow.
- Database will be populated with an initial list of users.
- Users are allowed to check out multiple books if their account is in good standing.
- On return of a book, if late, the user account will be updated to only allow 1 book out at a time until user account is in better standing. Better standing may be earned after 5 non-late borrowed books.
- On return, user may give a rating of the book 1-5.
- Search function will use a simple string search on title and author attributes.
- Related books will use the current books tags to search for books with similar tags.
- When user deletes their account the system will verify they have no books currently checked out before deleting.

Jupyter Notebook: library.ipnb

Project Report: LibraryDatabaseProject_JuliaChen.pdf

YouTube Project Walkthrough: https://youtu.be/8OmMKeU2d1A
