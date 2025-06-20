# React To-Do List Application

This is a **React To-Do List** application that allows users to:
- Add new tasks.
- Mark tasks as complete/incomplete.
- Remove tasks.
- Optionally sort and filter tasks.
- Persist tasks using `localStorage`.

The project validates task input, dynamically displays tasks, and ensures a user-friendly interface.
---
## Live Demo
The Application is at [Live_Demo](https://ch-lokesh-21.github.io/celebal_week_2/)
---

![image1](https://github.com/Ch-Lokesh-21/celebal_week_2/blob/2b7f24868d8d3b581d7197556a212e4e6e5a3427/image.png)
---
![image2](https://github.com/Ch-Lokesh-21/celebal_week_2/blob/2b7f24868d8d3b581d7197556a212e4e6e5a3427/image2.png)
---
![image3](https://github.com/Ch-Lokesh-21/celebal_week_2/blob/2b7f24868d8d3b581d7197556a212e4e6e5a3427/image3.png)

---
## Features

1. **Add Tasks**: Users can add tasks with a validated text input field.
2. **Mark Completion**: Mark tasks as complete/incomplete with a single click.
3. **Remove Tasks**: Delete unwanted tasks from the list.
4. **Sorting**: Sort tasks alphabetically or by completion status.
5. **Filtering**: Filter tasks to show all, completed, or incomplete tasks.
6. **LocalStorage Integration**: Tasks are saved in `localStorage` to persist data across sessions.

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/Ch-Lokesh-21/celebal_week_2.git
    cd celebal_week_2
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the application:
    ```bash
    npm start
    ```

The application will be available at `http://localhost:3000`.

## Code Overview

### Main Components

1. **`TodoWrapper`**: The main component managing state, task addition, sorting, filtering, and localStorage integration.
2. **`TodoForm`**: Handles task input and submission.
3. **`Todo`**: Displays individual tasks with options to mark as complete or delete.
4. **`EditTodoForm`**: Enables editing of an existing task.

### State Management
- **`useState`** is used to manage the list of tasks and application controls.
- **`useEffect`** ensures tasks are loaded and updated in `localStorage`.

## Testing Guidance
To manually test:
- Open the app in a browser.
- Test each feature (add, delete, complete, sort, filter).
- Refresh to confirm data persistence via `localStorage`.
