# 🍔 Online Food Ordering System

This is a C++ Object-Oriented Programming (OOPs) based **Online Food Ordering System**, developed as part of an experiential learning project. The application simulates an interactive console-based food ordering platform with two types of users: **Managers** and **Customers**.

---

## 💡 Features

### 👨‍💼 Manager Panel
- Add, update, delete, and display food items.
- View customer orders.
- Read customer feedback and ratings.
- View and update profile details.

### 👥 Customer Panel
- Sign up and log in securely.
- Browse available food items.
- Add items to cart and proceed with payment.
- View and manage cart contents.
- Submit ratings and feedback.
- View and update profile details.

### ⭐ Special Features
- Special Menu with seasonal dishes and chef’s specials (demonstrating **inheritance** and **polymorphism**).
- Feedback collection with rating validation.
- Branch listing using file input/output and vector usage.
- Secure login with validations (email, phone, DOB).
- Order history logging with timestamps.

---

## 📁 File Structure

- `Team_2 Online Food Ordering System.cpp` - Main project source file.
- `manager.txt` & `customer.txt` - Store registered user details.
- `foodlist.txt` - Contains menu items.
- `ratingfeedback.txt` - Stores feedback.
- `order.txt` - Logs order details with timestamps.
- `*.txt` (per customer) - Cart storage files.
- `district.txt` - Used for listing branches.

---

## 🔧 Technologies Used

- **Language:** C++
- **Concepts:** OOP (Inheritance, Polymorphism, Abstraction)
- **File Handling:** Used extensively for data persistence.
- **Regex:** Email validation.
- **Exception Handling:** For input validation.

---

## 📸 Sample Screens

> _Run the program in a C++ IDE or terminal to interact with menus and view full features._

---

## 🧠 Concepts Demonstrated

- Classes and Objects
- Inheritance (`SpecialMenu` inherits from `MenuItem`)
- Polymorphism (via virtual `display()` method)
- Friend functions and operator overloading
- File Handling (fstream for user and order management)
- Exception handling using `try-catch`
- Regex for email validation
- Basic time and date integration using `ctime`

---

## 🚀 Getting Started

1. Clone this repository or download the `.cpp` file.
2. Compile the C++ source code using any standard compiler:
   ```bash
   g++ "Team_2 Online Food Ordering System.cpp" -o foodOrderApp
   ./foodOrderApp
