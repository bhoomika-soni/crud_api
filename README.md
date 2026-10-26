# To-Do CRUD API

## About the Project
A simple REST API built using Node.js and Express.js to manage to-do tasks. It supports creating, reading, updating, and deleting tasks.

## Technologies Used
- Node.js
- Express.js
- Swagger UI
- Swagger JSDoc

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/bhoomika-soni/crud_api.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todo-crud-api
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Run the Project

Start the server:

```bash
node server.js
```

The API will run at:

`http://localhost:3000`

## Swagger Documentation

Open the following URL in your browser after starting the server:

`http://localhost:3000/api-docs`

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | /tasks | Create a task |
| GET | /tasks | Get all tasks |
| GET | /tasks/:id | Get a task by ID |
| PUT | /tasks/:id | Update a task |
| DELETE | /tasks/:id | Delete a task |

## Storage
Tasks are stored in memory and reset whenever the server restarts.
