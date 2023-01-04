# Todo_list

**FRONTEND**

Creating a user interface: designing a page for creating a to-do list, including components:
	Todo Wrapper
		Title
		Todo Input + Button Add
		Todo List
			Todo Item
				Add
				Text
				Edit
				Delete

Actions:
	Adding a task
	Сompleted task
	Deleting a task
	Editing a task


**BACKEND**

{
	id: v4(),
	name,
	complete: (false/true)
}

HTTP methods:

	GET - get ToDo list (200 (OK), 404 (Not Found),400 (Bad Request))

	POST - add a task to ToDo list (201 (Created), 404 (Not Found), 409 (Conflict))

	PATCH - edit a task in ToDo list (200 (OK), 204 (No Content), 404 (Not Found))

	DELETE - delete a task from ToDo list (200 (OK), 204 (No Content), 404 (Not Found)

	
