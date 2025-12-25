📝 Todo CLI Application (Go)

A simple command-line Todo application built using Go, which allows users to add tasks, list tasks, and toggle task completion.

📌 Features

Add new todo tasks
List all todo tasks in a table format
Mark tasks as completed or incomplete
Lightweight and easy to use

📦 Requirements

Go installed (version 1.20+ recommended)

🚀 How to Run the Application

From the project root directory:

 -------> go run ./

 📖 Usage Commands

🔹 List all todos

Displays all tasks in a table format.

---->go run ./ -list

🔹 Add a new todo

Adds a new task with the given title.

---->go run ./ -add "Buy groceries"

🔹 Toggle todo completion

Marks a task as completed or incomplete based on its ID.

---->go run ./ -toggle 0,1,2------

🔹 Deletion of a task

---->go run ./ -del 0,,1,2---(based on ID)


This project is intended for learning and demonstration purposes
