# System Behavior (Use Cases)

## Primary Actors
- End User / Task Owner: creates, updates, and manages tasks.

## Use Cases
1. Create a Task
2. View Tasks
3. Update a Task
4. Delete a Task
5. Mark Task as Complete
6. (Optional) Assign Tasks

## Secondary Actors
- **External I/O System:** Fake Task API ([https://jsonplaceholder.typicode.com/todos](https://jsonplaceholder.typicode.com/todos))
- **System Clock:** manages due dates and reminders
- **Random ID Generator Library:** assigns unique task IDs ([https://www.uuidgenerator.net](https://www.uuidgenerator.net))
