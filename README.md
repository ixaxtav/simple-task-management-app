# Task Management Application

This HTML and JavaScript app is a Task Management Application. It allows users to add tasks with a title, description, and deadline, and stores those tasks locally using the browser's localStorage API.

The app consists of a form where users can enter task details such as title, description, and deadline. When the user submits the form, the `addTask` function is triggered. It validates the input fields, creates a task object, and stores it in the browser's localStorage.

The app also provides functionality to delete tasks. Each task in the task list is displayed with its name, deadline, and description. The delete button allows users to remove a task from the list and localStorage.

On page load, the `renderTasks` function retrieves tasks from localStorage, sorts them based on the deadline, and dynamically generates HTML elements to display the tasks in the task list section.

Overall, this app provides a simple interface for managing tasks by allowing users to add new tasks, view existing tasks, and delete tasks if needed.

### DEMO:
 https://ixaxtav.github.io/simple-task-management-app/
