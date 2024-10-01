# Todo List Application
## Project Description
- The Todo List application is a JavaScript-based user interface that communicates with an external API to manage tasks and task operations. The application allows users to create, edit, delete, and update tasks and operations related to tasks. Data is fetched and saved using HTTP requests to the API.

## Technologies
- HTML, CSS, JavaScript: User interface.
- Fetch API: Communication with the external API.
- Bootstrap: CSS library for styling the interface.
- API: https://todo-api.coderslab.pl.

## Features
- Task List (tasks):
  - Display a list of tasks.
  - Create a new task.
  - Delete a task.
  - Close a task (change status to "closed").
- Task Operations (operations):
  - Display operations assigned to a task.
  - Add a new operation to a task.
  - Update the time spent on an operation.
  - Delete an operation from a task.

## Requirements
- A browser that supports ES6 (ECMAScript 2015) and Fetch API.

## API Requirements
- Authorization: The Authorization header with your API key is required.
- Content-Type: For POST and PUT requests, the Content-Type: application/json header is required.

## Notes
- If an error occurs while communicating with the API, check the browser console and the "Network" tab in the developer tools to diagnose the issue.
- Make sure your API key is correct and working.

## License
- The project is available under the MIT License.
