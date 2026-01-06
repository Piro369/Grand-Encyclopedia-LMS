# 📚 Grand Encyclopedia - Library Management System

A console-based Library Management System built in C++ featuring a visual interface, user authentication, and book inventory management.

## 🚀 Features

* **Role-Based Access Control:** Distinct menus and permissions for **Admins**, **Regular Users**, and **Guests**.
* **Book Management:** Admins can add and remove books from the database.
* **Financial System:** Users can deposit funds, view balances, and purchase books (simulated transaction).
* **File Handling:** All data (credentials, book lists, transactions) is persistent using `.txt` files.
* **Interactive UI:** Features delayed text rendering and ASCII art for a polished console experience.
* **Robust Error Handling:** Custom Exception classes for file errors and missing books.

## 🛠️ Tech Stack & Concepts Used

* **Language:** C++
* **OOP Concepts:** Inheritance, Polymorphism, Encapsulation.
* **Advanced C++:** Exception Handling (`FileException`, `BookNotFoundException`), File Streams (`fstream`), Namespaces.
* **Platform:** Windows (Uses `system("cls")` and `windows.h` dependencies).

## 📋 Prerequisites

* A C++ Compiler (G++ or MSVC).
* **Windows OS** (Note: This project uses `system("cls")` which is specific to Windows. Linux/Mac users may need to change this to `system("clear")`).

## ⚙️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/YourUsername/Grand-Encyclopedia-LMS.git

```


2. Navigate to the project directory.
3. Compile the code:
```bash
g++ RealProject.cpp -o library_app

```


4. Run the executable:
```bash
./library_app.exe

```



## 📂 Project Structure

* `RealProject.cpp`: Contains the main logic, `Library` class, and `Login` system.
* `Header.h`: Contains ASCII art, utility functions (delays), and Exception classes.
* `Books/`: Directory containing the book database files.

## 🔑 Default Credentials (for Testing)

* **Admin:**
* Username: `admin123`
* Password: `123` (Ensure `admin_credentials.txt` is set up)


* **User:**
* You can register a new user via the main menu.

---

