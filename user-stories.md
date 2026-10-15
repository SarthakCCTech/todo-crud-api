
# Todo API - User Stories

## US-01: Create Todo
As a user, I want to create a todo so that I can record my tasks.

Acceptance criteria:
- Accept title and description.
- Title is required.
- Return 201 when created.

## US-02: Get All Todos
As a user, I want to view all todos so that I can track my tasks.

Acceptance criteria:
- Return all todos.
- Return an empty list if no todos exist.
- Return 200 on success.

## US-03: Get Todo by ID
As a user, I want to view a todo by ID so that I can see its details.

Acceptance criteria:
- Return the todo if it exists.
- Return 404 if it does not exist.

## US-04: Update Todo
As a user, I want to update a todo so that I can change its details.

Acceptance criteria:
- Update title, description, and completion status.
- Return 200 on success.
- Return 404 if the todo does not exist.

## US-05: Delete Todo
As a user, I want to delete a todo so that I can remove unwanted tasks.

Acceptance criteria:
- Delete the todo using its ID.
- Return 204 on success.
- Return 404 if the todo does not exist.
