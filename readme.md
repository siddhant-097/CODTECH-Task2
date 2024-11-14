Name: Siddhant Chaudhary <br>
Company: CODTECH IT SOLUTIONS<br>
ID:CT08DS8773<br>
Domain:Web Devolopment<br>
Duration:OCTOBER 15th,2024 to NOVEMBER 15th,2024 <br>
Mentor: Neela Santhosh Kumar
<br>

# Todo List Application 
## overview
This Todo List application allows users to manage their tasks efficiently. Users can add new tasks, set due dates, mark tasks as completed, edit tasks, delete individual tasks, and clear all tasks. The application also supports filtering tasks by their status (all, pending, completed). The user interface is built with HTML, CSS (including Tailwind CSS and DaisyUI), and JavaScript, with tasks stored in localStorage.

## Features
Add Tasks: Users can add tasks with optional due dates.
Edit Tasks: Users can edit existing tasks.
Delete Tasks: Users can delete individual tasks or clear all tasks.
Toggle Task Status: Users can mark tasks as completed or pending.
Filter Tasks: Users can filter tasks by their status (all, pending, completed).
Responsive Design: The application is designed to be responsive and works on different screen sizes.
LocalStorage: Tasks are stored in localStorage, allowing persistence across browser sessions.

## Technologies Used
HTML
CSS
Tailwind CSS
DaisyUI
JavaScript
Boxicons
File Structure
index.html: Contains the structure of the application.
style.css: Contains the custom styles for the application.
script.js: Contains the logic for managing and displaying tasks.

## How to Use
Adding a Task:

Enter a task in the input field.
Optionally, set a due date using the date picker.
Click the add button (plus icon) to add the task to the list.
Editing a Task:

Click the edit button (pencil icon) next to the task you want to edit.
Modify the task in the input field.
Click the check button to save the changes.
Deleting a Task:

Click the delete button (trash icon) next to the task you want to delete.
Toggling Task Status:

Click the check button next to the task to mark it as completed or pending.
Clearing All Tasks:

Click the "Delete All" button to clear all tasks from the list.
Filtering Tasks:

Click the filter button and select the desired filter (All, Pending, Completed) to display tasks based on their status.

## Code Overview
HTML
The index.html file includes the structure of the application with sections for the header, input fields, filter options, and the task list.
CSS
The style.css file contains custom styles to enhance the appearance of the application.
Uses Tailwind CSS and DaisyUI for additional styling and components.
JavaScript
The script.js file contains the logic for task management.
Classes:
TodoItemFormatter: Formats task details (task name, due date, status).
TodoManager: Manages tasks (add, edit, delete, toggle status, filter, save to localStorage).
UIManager: Manages the user interface and interactions (event listeners, display tasks, show alerts).
## Author
Developed by Ansh Singhal.
