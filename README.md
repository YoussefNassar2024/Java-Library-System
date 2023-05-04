Book library System
Book_library.java :
- Holds all the rules of the book class.
- Deals with the writing and manipulation of book information in the txt files
Book_temp:
- Temporary file used to help in writing to books.txt, only a temporary storage unit
Books.txt:
- Main storage file that is used to hold all of the books information, and attributes.
Driver.java:
- Main starter app. You should only run this file to start the program.
Gui.java:
- Class the holds all the gui elements, and it the parent class for book_library.
Features:
1- Add new books
2- Delete books
3- Borrow books for a certain period of days (only if returned or borrow date has passed by)
4- Return books (return books whenever and only when they are borrowed)
5- Print a table of all the books in the storage.
6- Create new id for each book and replace deleted id for the latest deleted book



Main interface

![image](https://user-images.githubusercontent.com/94936068/236205526-6bb1f186-3241-4cbf-8320-95296b9f8142.png)

Wrong input instructions

![image](https://user-images.githubusercontent.com/94936068/236205577-46a78e83-3f39-4673-8d91-b515f3fb8ea8.png)


wrong period input while trying to borrow a book with id 1

![image](https://user-images.githubusercontent.com/94936068/236205679-a052f571-6ae1-4fcf-9f1f-8ad38f4f666a.png)


Printing each book’s information(status button)

![image](https://user-images.githubusercontent.com/94936068/236205732-e19cea71-59bb-4741-b144-a4238e4dadc3.png)
