# 📚 Library Management System (Python OOP)

## 📖 Project Overview

The **Library Management System** is a console-based application developed in **Python** using **Object-Oriented Programming (OOP)** concepts.
It helps manage library operations such as adding books, issuing books, returning books, and viewing available inventory.

This project demonstrates the practical implementation of OOP principles like **classes, objects, inheritance, encapsulation, and polymorphism**.

---

## 🚀 Features

* Add new books to the library
* Display all available books
* Issue books to students/users
* Return issued books
* Search books by title or author
* Maintain issue records
* Simple and user-friendly console interface

---

## 🛠️ Technologies Used

* **Programming Language:** Python 3.x
* **Paradigm:** Object-Oriented Programming (OOP)
* **IDE/Editor:** VS Code / PyCharm / IDLE (any)

---

## 📂 Project Structure

```
library-management/
│
├── main.py              # Entry point of the program
├── library.py           # Library class & operations
├── book.py              # Book class definition
├── user.py              # User/Student class
├── data.txt / db.json   # (Optional) Data storage
└── README.md            # Project documentation
```

---

## 🧩 OOP Concepts Implemented

### 1. Class & Objects

* `Book` → Stores book details
* `User` → Stores user details
* `Library` → Handles operations

### 2. Encapsulation

Private attributes like:

* Book availability
* User records

### 3. Inheritance (Optional)

Example:

```
User → Student / Teacher
```

### 4. Polymorphism

Different issue rules for different user types (if implemented).

---

## ▶️ How to Run the Project

1. Install Python (3.x)
2. Clone or download this repository
3. Open project folder in terminal
4. Run the program:

```bash
python main.py
```

---

## 🖥️ Sample Menu

```
1. Add Book
2. View Books
3. Issue Book
4. Return Book
5. Search Book
6. Exit
```

---

## 📌 Example Classes

### Book Class

```python
class Book:
    def __init__(self, title, author):
        self.title = title
        self.author = author
        self.is_issued = False
```

### Library Class

```python
class Library:
    def __init__(self):
        self.books = []

    def add_book(self, book):
        self.books.append(book)
```

---

## 🔮 Future Enhancements

* GUI using Tkinter / PyQt
* Database integration (MySQL / SQLite)
* Fine calculation system
* Login authentication
* Web-based system (Django/Flask)

---

## 👨‍💻 Author

**Your Name**
Python Developer / Student

---

## 📜 License

This project is for educational purposes only.
