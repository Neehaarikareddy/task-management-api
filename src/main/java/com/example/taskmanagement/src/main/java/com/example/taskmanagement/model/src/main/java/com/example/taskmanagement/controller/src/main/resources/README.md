# Task Management API

A simple Spring Boot REST API project for managing tasks.

## Features

- Create a new task
- Get all tasks
- Get task by ID
- Update task
- Delete task

## Technologies Used

- Java 17
- Spring Boot
- Maven
- REST API

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | /api/tasks | Get all tasks |
| GET | /api/tasks/{id} | Get task by ID |
| POST | /api/tasks | Create new task |
| PUT | /api/tasks/{id} | Update task |
| DELETE | /api/tasks/{id} | Delete task |

## Sample POST Request

```json
{
  "title": "Complete Spring Boot project",
  "description": "Create task management API and push to GitHub",
  "status": "IN_PROGRESS"
}
