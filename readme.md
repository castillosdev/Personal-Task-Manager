###Personal Task Manager

This is a simple web-based task manager that allows users to add, remove, and filter tasks. It is built using HTML, CSS, and JavaScript, and utilizes the Alpine.js library for reactive functionality.

The task manager displays two input fields for task title and description, and a button to add a new task. The user can filter tasks based on their completion status (All, Active, or Completed) using three buttons at the top of the task list. Each task is displayed with a checkbox, title, description, and a remove button. The state of the tasks is saved to the user's local storage using the localStorage API, and is loaded when the page is reloaded.

The code uses a JavaScript function called taskManager() to create an object that contains the task data and methods for manipulating it. This object is then bound to the HTML using the x-data attribute, allowing for dynamic updates to the task list based on user input.