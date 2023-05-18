# TodoApp
This is a simple Spring Boot application that provides a RESTful API for managing a list of todos. It allows you to perform basic CRUD operations on todos.

## Technologies Used
- Java
- Spring Boot
- Lombok
- maven

## API Endpoints
The following API endpoints are available:
- **GET /todoPackage/getAllTodos:** Get all todos in the todo list.
- **GET /todoPackage/getTodosByStatus?status=<status>:** Get todos by status (true/false).
- **GET /todoPackage/getTodoById/{id}:** Get a todo by ID.
- **POST /todoPackage/addTodo:** Add a new todo to the list.
- **DELETE /todoPackage/deleteTodoById/{id}:** Delete a todo by ID.
- **PUT /todoPackage/updateTodoById/{id}/{status}:** Update the status of a todo by ID.

## Project Summary
The Todo List API is a Spring Boot application that provides a simple and easy-to-use API for managing todos. It allows you to perform various operations on the todo list, such as adding a new todo, retrieving todos by status, getting a todo by ID, updating the status of a todo, and deleting a todo.
The application follows a layered architecture, separating the controller, service, and data access layers. The TodoController class handles HTTP requests, the TodoService class contains the business logic, and the TodoDao is responsible for accessing the data source and managing todos.
