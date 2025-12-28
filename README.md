# 📚 Library Management System

A **console-based Library Management System** built in **Java**, demonstrating **OOP concepts** like **inheritance, polymorphism, encapsulation**, and **file handling** for persistent storage.  

---

## ✨ Features

- **📖 Book Management**
  - Add, update, delete, and list books.
  - Maintain real-time book quantity.
  
- **👤 Member Management**
  - Register members.
  - Track borrowed books per member.

- **🔄 Borrowing & Returning**
  - Borrow available books.
  - Return borrowed books.
  - Automatic quantity updates.

- **💾 Persistent Storage**
  - Books and members are stored in `books.csv` and `members.csv`.

- **🛠 Role-based Operations**
  - **Librarian** – Full control over books.
  - **Member** – Can borrow/return books.

- **📋 User-friendly Console Menu**
  - Simple menu for easy interaction.

---

## 💻 Technologies Used

- **Java** – Object-Oriented Programming (OOP)  
- **File I/O** – CSV-based persistent storage  
- **Console Interface** – Menu-driven user experience  

---

## 🗂 Project Structure

LibraryManagementSystem/

│

├── LibrarySystem.java # Main program

├── books.csv # Book records

├── members.csv # Member records

└── README.md # Project documentation

---

## 🚀 How to Run

1. **Compile the program**
```bash
javac LibrarySystem.java
```
2. **Run the program**
```bash
java LibrarySystem
```
3. **Use the console menu** to manage books and members.

## ⚙️ Usage
| Option          | Description                                    |
| --------------- | ---------------------------------------------- |
| List Books      | View all available books                       |
| Add Book        | Add new books to the library                   |
| Register Member | Add new members                                |
| Borrow Book     | Members can borrow available books             |
| Return Book     | Members can return borrowed books              |
| Update Book     | Update book details (Librarian only)           |
| Delete Book     | Remove books from the library (Librarian only) |

## 🔮 Future Enhancements

* Allow multiple books per member

* Add search and sort functionality for books

* Implement a GUI interface using Swing or JavaFX

* Add authentication for librarian and members

* Enhance error handling for invalid inputs and malformed CSV files

## 👩‍💻 Author
**Sneha Gade**
B.Tech Student & Java Developer
