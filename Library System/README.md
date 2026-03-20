# 📚 Library Management System

A simple **Object-Oriented Library Management System** built using Python.  
This project allows management of books, users, and book issuing/returning with basic persistent storage using pickle.

---

## 🚀 Features

- Add and manage books
- Register users
- Issue books to users
- Return books with fine calculation
- Track borrowed books with issue and return dates
- Persistent storage using `.pkl` files

---

## 🛠 Technologies Used

- Python
- OOP (Object-Oriented Programming)
- Pickle (for data storage)
- Datetime module

---

## 📂 Project Structure

library-system/
│
├── main.py              
├── books.pkl           
├── users.pkl           
├── b_books.pkl         
└── README.md           

---

## ⚙️ How It Works

### 📘 Book Management
- Books are stored in a dictionary using `book_id`
- Each book has:
  - Title
  - Author
  - Availability status

### 👤 User Management
- Users are registered with a unique `user_id`
- Each user can borrow up to **3 books**

### 🔄 Issue Book
- Checks:
  - Borrow limit
  - Duplicate borrowing
- Records:
  - Issue date
  - Expected return date

### 🔁 Return Book
- Calculates fine if returned late  
- Fine = ₹2 per day after due date

---

## ▶️ How to Run

1. Clone the repository.

2. Navigate to project folder:
cd library System

3. Run the Python file:
   Library_System.py

---

## 📌 Limitations

- No user interface (CLI/GUI)
- Book availability check is basic
- No validation for invalid IDs
- Uses pickle instead of a database
- Class design can be improved (inheritance usage)
- No concurrency handling

---

## 🚀 Future Improvements

- Add command-line interface (CLI)
- Implement GUI (Tkinter / Web App)
- Replace pickle with database (SQLite/MySQL)
- Improve error handling and validations
- Add search and filtering features
- Fix class relationships (use composition instead of inheritance)

---

## 💡 Learning Outcomes

- Understanding of OOP concepts
- Working with file handling (pickle)
- Managing real-world logic (library system)
- Handling dates and calculations in Python

---

## 📖 Author

- Your Name

---

## ⭐ Note

This project is built for learning purposes and can be extended into a full-scale application.
