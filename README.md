# 📚 Library Management System (Python)

## Overview
A simple **Library Management System** built in Python.  
It demonstrates basic **CRUD operations** and uses a **dictionary** to track which user has borrowed which book.

---

## ✨ Features
- **Display Books** → View all available books in the library  
- **Lend Book** → Borrow a book (saved in a dictionary with user details)  
- **Return Book** → Return borrowed books and update records  
- **Add Book** → Add new books to the collection  
- **Exit** → Quit the program gracefully  

---

## ⚙️ How It Works
- The library starts with a predefined list of books.  
- When a book is lent, it is stored in a dictionary as:

```python
self.lent_books[book] = user
