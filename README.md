# To-Do List Application
## What I Built
A simple console-based To-Do List Manager in Python. It lets users add, remove, and view tasks, while saving them in a tasks.txt file so they don’t get lost when the program closes.
## Why I Built It
I wanted to create a lightweight app that:
* Runs in the terminal
* Covers the basics of task management (add, remove, view)
* Stores tasks in a file for persistence
* Feels simple and easy to use
## How I Built It
* Task Storage: Used a list in memory + tasks.txt for saving tasks.
* Loading & Saving: Functions load_tasks() and save_tasks() handle persistence.
* Task Management: Separate functions for adding, removing, and viewing tasks.
* User Interface: A while loop provides a simple text-based menu for user choices.
* Error Handling: Added try-except blocks for safe file handling and invalid inputs.
