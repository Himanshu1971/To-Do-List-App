# Todo List App

This is a simple Todo List web application that allows users to add, edit, toggle, and delete tasks. The application uses `localStorage` to persist tasks across page reloads.

## Features

- **Add Task:** Users can add a new task to the list by typing in the input field and pressing the "Add Task" button or pressing the "Enter" key.
- **Edit Task:** Users can edit an existing task by clicking on the task text, which will turn into an input field for editing.
- **Toggle Task Completion:** Users can mark a task as completed by checking the checkbox next to the task. Completed tasks are styled with a strikethrough.
- **Delete All Tasks:** Users can delete all tasks by pressing the "Delete All Tasks" button.
- **Persistent Storage:** The app uses `localStorage` to save tasks, ensuring they persist across page reloads and browser restarts.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Himanshu1971/todo-list-app.git
    ```
   
2. **Navigate to the project directory:**
    ```sh
    cd todo-list-app
    ```

3. **Open `index.html` in your preferred browser:**
    ```sh
    open index.html
    ```
   Or simply double-click the `index.html` file to open it in your default web browser.

## Usage

1. **Add a Task:**
    - Type a task in the input field and press the "Add Task" button or press the "Enter" key.
    - The task will appear in the list below the input field.

2. **Edit a Task:**
    - Click on the task text you want to edit.
    - The task text will turn into an input field.
    - Edit the text and click outside the input field to save the changes.

3. **Toggle Task Completion:**
    - Click the checkbox next to the task to mark it as completed or not completed.
    - Completed tasks will have a strikethrough style.

4. **Delete All Tasks:**
    - Press the "Delete All Tasks" button to remove all tasks from the list.

## File Structure

- `index.html`: The main HTML file that contains the structure of the Todo List app.
- `README.md`: This file, providing information about the project.
- `style.css`: The CSS file for styling the app.

## Code Overview

The core JavaScript code is contained within the `<script>` tag in the `index.html` file. Here's an overview of the main functions:

- `addTask()`: Adds a new task to the list and saves it to `localStorage`.
- `displayTasks()`: Renders the tasks on the screen.
- `editTask(index)`: Allows editing of a task.
- `toggleTask(index)`: Toggles the completion state of a task.
- `deleteAllTasks()`: Deletes all tasks.
- `saveToLocalStorage()`: Saves the tasks to `localStorage`.


