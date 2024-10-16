# Personal To-Do List Application
#Overview
A simple, user-friendly To-Do List application developed using Python and Tkinter. This application allows users to manage tasks effectively, including adding, viewing, editing, marking tasks as completed, and deleting tasks. It also supports task categorization and persists data using a local JSON file, allowing users to save progress between sessions.

#Features
  #Task Management:
    Add tasks with a title, description, and category (e.g., Work, Personal, Urgent).
    Edit existing tasks.
    Mark tasks as completed.
    Delete tasks.
  #Task Categorization:
    Categorize tasks for better organization.
  #Persistence:
    Save tasks to a JSON file to retain progress between sessions.
  #User Interface:
    A simple graphical interface using Tkinter for ease of use.
    
#Technology Stack
  Programming Language: Python 3.x
  Libraries: Tkinter (for the graphical user interface), JSON (for data persistence)
  
#Getting Started
#Prerequisites
  Python 3.x: Ensure that Python is installed on your system. You can download it from python.org.
  
#Usage
  Add a Task: Click on the "Add Task" button and fill in the details for the new task (title, description, category).
  Edit a Task: Select a task from the list and click "Edit Task" to modify its details.
  Mark Task as Completed: Select a task and click "Mark Completed" to update its status.
  Delete a Task: Select a task and click "Delete Task" to remove it from the list.
  Save & Exit: Click the "Save & Exit" button to save your tasks and close the application.
    The main interface consists of a listbox displaying the tasks, with buttons for managing the tasks.

#File Handling
  Saving Tasks: The tasks are saved automatically in a JSON file (tasks.json) whenever the "Save & Exit" button is clicked.
  Loading Tasks: On startup, the application loads tasks from the tasks.json file (if it exists) to display previously saved tasks.
  
#Future Enhancements
  Some potential features to improve the application include:

    Adding task due dates and reminders.
    Implementing filtering and sorting by category or completion status.
    Enhancing the user interface with custom styles and themes.
    Adding support for recurring tasks.
