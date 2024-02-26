**System Flowchart**
```
  +----------------------------------+
  |          Start Application       |
  +----------------------------------+
                  |
                  V
  +----------------------------------+
  |      Display Todo List           |
  +----------------------------------+
                  |
                  V
  +----------------------------------+
  |       Add New Todo               |
  +----------------------------------+
                  |
                  V
  +----------------------------------+
  |       Edit Todo                  |
  +----------------------------------+
                  |
                  V
  +----------------------------------+
  |       Delete Todo                |
  +----------------------------------+
                  |
                  V
  +----------------------------------+
  |       End Application            |
  +----------------------------------+
```

**System Pseudocode**
```
Start Application

FUNCTION DisplayTodoList():
    // Fetch and display todo list from backend
    // Each item includes title, description, status, date created, and date updated

FUNCTION AddNewTodo():
    // Prompt user to enter title and description
    // Validate inputs
    // Add new todo item to the list

FUNCTION EditTodo():
    // Prompt user to select todo item to edit
    // Prompt user to modify title, description, and status
    // Update selected todo item

FUNCTION DeleteTodo():
    // Prompt user to select todo item to delete
    // Confirm deletion
    // Remove selected todo item from the list

DisplayTodoList()
AddNewTodo()
EditTodo()
DeleteTodo()

End Application
```