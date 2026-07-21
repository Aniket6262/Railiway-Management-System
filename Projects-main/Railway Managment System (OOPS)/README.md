# 🚆 Railway Management System

A console-based **Railway Management System** built in **C++** using **Object-Oriented Programming (OOP)** concepts. The system allows users to register/login, book and manage train tickets, order food, and maintain records — all through a simple terminal interface with file-based data storage.

> Developed as an undergraduate project.

---

## ✨ Features

- **User Authentication** — register and log in with credentials stored locally.
- **Ticket Booking** — book train tickets and generate ticket records.
- **Food Ordering** — browse and order food available on the train.
- **Record Management** — view and store booking/transaction records.
- **Persistent Storage** — all data is saved to text files, so it stays intact between sessions.

---

## 🛠️ Tech Stack

- **Language:** C++
- **Paradigm:** Object-Oriented Programming (classes, objects, encapsulation)
- **Storage:** File handling (`.txt` files)

---

## 📂 Project Structure

```
Railway Managment System (OOPS)/
├── railway.cpp      # Main source code
├── user.txt         # Stored user login credentials
├── tickets.txt      # Booked ticket details
├── records.txt      # Booking / transaction records
├── foodd.txt        # Food menu / details
└── foodr.txt        # Food order records
```

---

## 🚀 Getting Started

### Prerequisites

You'll need a C++ compiler installed, such as **g++** (part of MinGW on Windows or GCC on Linux/Mac).

### Compile & Run

Clone the repository:

```bash
git clone https://github.com/Aniket6262/Railiway-Management-System.git
```

Navigate to the project folder and compile:

```bash
g++ railway.cpp -o railway
```

Run the program:

```bash
# On Windows
railway.exe

# On Linux / Mac
./railway
```

---

## 📖 Usage

1. Launch the program.
2. Register a new account or log in with existing credentials.
3. Choose from the menu options to book tickets, order food, or view records.
4. Follow the on-screen prompts.

---

## 📝 Notes

- All data is stored in plain-text files in the project directory.
- This project was built for learning purposes to demonstrate OOP and file-handling concepts in C++.

---

## 👤 Author

**Aniket**
GitHub: [@Aniket6262](https://github.com/Aniket6262)

---

## 📄 License

This project is open for educational use. Feel free to explore and learn from it.