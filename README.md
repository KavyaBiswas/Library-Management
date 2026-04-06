# Library-Management
A GUI-based Library Management System developed using Python, Tkinter, and SQLite that streamlines book management operations such as adding, deleting, issuing, returning, and tracking availability.


Library Management System (Python + Tkinter + SQLite)
A simple and user-friendly Library Management System built using Python, Tkinter (GUI), and SQLite database. This application helps manage book records efficiently with features like adding, deleting, issuing, returning, and viewing books.


🚀 Features
➕ Add new books to the library
❌ Delete existing books
📖 View all available books
📤 Issue books to students
📥 Return issued books
💾 Persistent storage using SQLite database


🛠️ Tech Stack
Programming Language: Python
GUI Framework: Tkinter
Database: SQLite3



📂 Project Structure

Library-Management/
│
├── main.py              # Main dashboard
├── AddBook.py           # Add book functionality
├── DeleteBook.py        # Delete book functionality
├── IssueBook.py         # Issue book module
├── ReturnBook.py        # Return book module
├── ViewBooks.py         # Display all books
├── library.db           # SQLite database
└── README.md            # Project documentation



⚙️ Installation & Setup
Clone the repository:

git clone https://KavyaBiswas/Library-Management.git
Navigate to the project folder:

cd Library-Management
Run the main file:

python main.py


🧠 How It Works
The system uses SQLite to store book and issue records.
GUI is built using Tkinter, making it easy to use.
Each operation (Add, Delete, Issue, Return) is handled in separate modules.
Book status is automatically updated (avail / issued).



🗄️ Database Schema
📘 Books Table
Field              Type
bid                TEXT
title              TEXT
author             TEXT
status             TEXT
📕 Issued Books Table
Field              Type
bid                TEXT
issueto            TEXT



Future Enhancements
🔍 Search functionality
👤 User authentication system
📊 Dashboard analytics
📅 Due date & fine calculation
🌐 Web-based version



⚠️ Known Issues
SQL queries are not parameterized (can be improved for security)
UI can be enhanced for better user experience


🙌 Contribution
Contributions are welcome!
Feel free to fork this repository and submit a pull request.

📄 License
This project is open-source and available under the MIT License.

👩‍💻 Author
Kavya Biswas
B.Tech CSE (Data Science)
