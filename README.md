# SecureShop 🛒

SecureShop is a console-based C++ shopping cart system developed as a semester project. It allows users to register, log in, browse different categories of items (Food, Clothes, and Supplies), add/remove items to/from the cart, and checkout securely. The project also demonstrates file handling, object-oriented programming, and basic data persistence in C++.

---

## 📌 Features

- ✅ **User Authentication** (Sign Up / Log In)
- 🛍 **Category-based Shopping** (Food, Clothes, Supplies)
- 🧾 **Cart Management**
  - Add items
  - Remove items
  - View total cost
- 💾 **File Handling**
  - Store user data and cart data in files
- 🧠 **Object-Oriented Design**
  - Use of classes like `User`, `Item`, `Cart`, etc.
- 🔐 Basic input validation and secure data flow

---

## 🗂 File Structure

SecureShop/
├── main.cpp
├── user.cpp
├── user.h
├── item.cpp
├── item.h
├── cart.cpp
├── cart.h
├── data/
│ ├── users.txt
│ ├── items.txt
│ └── transactions.txt
└── README.md

---

## 🛠 Tech Stack

- **Language:** C++
- **Concepts Used:**
  - Classes & Objects
  - File I/O
  - Inheritance & Polymorphism (optional)
  - Arrays and basic string manipulation

---

## 🔧 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/SecureShop.git
   Compile the code:
g++ main.cpp user.cpp item.cpp cart.cpp -o secureshop
Run the executable:

./secureshop
Make sure you have a data/ directory with required .txt files before running.
