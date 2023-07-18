# TodoApp
a simple todo app build with html css and javascript


![image](https://github.com/AlkaloidWells/TodoApp/assets/55930366/75e7d532-12fe-43d5-a7d8-f536d6f78479)


# App View 

![image](https://github.com/AlkaloidWells/TodoApp/assets/55930366/963e3cba-015c-4943-ac0a-7c86ec7ebe6f)

Overall Architecture
The Todo app follows a simple architecture, where the front-end (HTML, CSS, and
JavaScript) handles the user interface, user interactions, and manages the tasks data.
The front-end communicates directly with the user's browser.
The app uses a client-side approach, where tasks are stored in the JavaScript `tasks`
array, and the UI is dynamically updated based on the changes to this array. The
tasks data is not persisted, and there is no separate back-end or database implemented
in this example.
The app follows a modular structure with functions that handle specific tasks, such
as adding tasks, updating completion status, removing tasks, and updating the
productivity score. These functions are called in response to user actions and ensure
the UI is updated accordingly.
Key Functions:
- `createTaskObject(name, activity, state, dateline)`: Creates a new task object with
the provided details and returns it.
- `addTask(event)`: Handles the form submission event to add a new task. Retrieves
input values, creates a task object, adds it to the tasks array, and updates the UI.
- `renderTasks()`: Renders the tasks in the task lists based on the tasks array. Creates
list items for each task, including checkboxes, labels, and buttons, and appends them
to the appropriate list (incomplete or completed).
- `toggleTaskCompletion(event)`: Handles the change event of checkboxes to toggle
the completion status of a task. Updates the tasks array, re-renders the task lists, and
updates the productivity score.
- `removeTask(event)`: Handles the click event of the remove buttons to remove a
task from the tasks array. Updates the task lists and productivity score.
- `updateProductivityScore()`: Calculates the productivity score based on the
number of completed tasks and updates the productivity score element in the UI.
- `resetForm()`: Resets the form inputs to their initial state.
- Event Listeners: Sets up event listeners for form submission, task completion toggling, and task removal. Calls the appropriate functions based on the user actions.
HTML (index.html)
The `index.html` file serves as the entry point for the Todo app. It defines the structure of the web page and contains the necessary elements to interact with the application.
Deployment:
The application was deployed on my local host
Key



