# 📚 Book Tracker Project – Phase 3 Blog

## Introduction
=>The **Book Tracker** project is a Python-based CLI (Command Line Interface) application that allows users to manage **authors, books, and genres**.  
=>It demonstrates Object-Oriented Programming (OOP), database relationships, and interactive command-line applications.

---

## Technologies Used
- Python
- SQLite (database)
- SQLAlchemy (ORM)
- CLI (Command Line Interface)

---

## Features
- **Authors**: Add, list, and delete authors.
- **Books**: Add and list books, linked to an author and genre.
- **Genres**: Add and list genres.
- **Relationships**:  
  - Each **author** can have many **books**.  
  - Each **book** belongs to one **author** and one **genre**.

---

## Example CLI Demo

 
📚 Welcome to Book Tracker CLI
Type 'help' to see commands, 'quit' to exit.

👉 Enter a command: authors add
Author name: J.K. Rowling
✅ Author added successfully!

👉 Enter a command: books add
Book title: Harry Potter and the Sorcerer’s Stone
Select author: J.K. Rowling
Select genre: Fantasy
✅ Book added successfully!

👉 Enter a command: books list
1. Harry Potter and the Sorcerer’s Stone (Author: J.K. Rowling, Genre: Fantasy)
