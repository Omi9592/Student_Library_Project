# Student_Library_Project
📚 Library Management System (Python)

A simple console-based Library Management System built using Object-Oriented Programming (OOP) in Python.
Users can view available books, borrow books, and return books through a command-line menu.

🚀 Features

View all available books in the library

Borrow a book (only if available)

Return/Add a book

Real-time update of library inventory

OOP-based structure (Library & Student classes)

🧩 How It Works
Library Class

Handles:

Storing all available books

Displaying books

Borrowing logic

Returning logic

Student Class

Handles:

Asking user which book they want to borrow

Asking user which book they want to return

📂 Project Structure
/LibraryManagement
│
└── main.py

▶️ Running the Program
1. Navigate to your project folder
cd LibraryManagement

2. Run the program
python main.py

📘 Example Menu
====== Welcome to Central Library ======
Please choose an option:
1. List all the books
2. Request a book
3. Add/Return a book
4. Exit the Library

📝 Example Output
Enter a choice: 1
Books present in this library are:
 *Algorithms
 *Django
 *Clrs
 *Python Notes

Enter a choice: 2
Enter the name of the book you want to borrow: Django
You have been issued Django. Please keep it safe and return it within 30 days

🛠 Future Improvements

If you want to extend the project, here are ideas:

Save issued books into a file (inventory persistence)

Add a student database

Add timestamps for borrowing/return

Implement a fine system for late return

Create a GUI using Tkinter

Use JSON to store book data permanently
