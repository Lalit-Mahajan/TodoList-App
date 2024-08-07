
# `Todo List App 🗂️`

This is a simple Todo List application built with React. It allows users to add, update, mark as complete, and delete tasks. The application uses state management to handle the task list and ensures a user-friendly interface.


## `Features`

- Add new tasks 🎯 ➕
- Mark tasks as completed ✅
- Update existing tasks ✏️ ✔️
- Delete tasks 🗑️
- User-friendly UI 🎨

## `System Design`
 
 ```
  src/
      components/
          AddTaskForm.js
          ToDo.js
          UpdateForm.js
    App.css
    App.js
    index.js
  ```


## `Components Overview`

```
  1.AddTaskForm.js
    -Input field for task description.
    -Button to submit the new task.
  2.ToDo.js
    -Checkbox to mark tasks as done.
    -Buttons to update or delete tasks.
    -Handles task state changes and interactions.
  3.UpdateForm.js
    -Input field pre-populated with the current task description.
    -Button to submit the updated task.
    -Button to cancel the updated task.

```
## `Application Files Overview`

```
1.App.css
    Purpose:
          -Contains the styling for the application.
    Key Features:
                -CSS rules for layout, task list, forms, and buttons.
                -Emoji usage: 🎨 (styling).
                -Ensures a clean and user-friendly UI.
2.App.js
    Purpose: 
           -The main application component that integrates all other components.
    Key Features:
                -Handles the logic for adding, updating, and deleting tasks.
                -Passes necessary props and handlers to child components.   
3.index.js
      Purpose: 
             -Entry point of the React application.
      Key Features:
                  -Renders the App component into the DOM.
                  -Typically includes setup for React, ReactDOM, and any necessary providers.                

```
## `Technologies Used`

- HTML
- CSS
- ReactJS


## `How to set up and run the application.`

In the project directory, you can run:


```bash
  npm install
```
```bash
  npm start
```

