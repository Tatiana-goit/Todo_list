# Todo_list

**FRONTEND**

Creating a user interface: designing a page for creating a to-do list, including components:

	Todo Wrapper
		Title
		Todo Input + Button Add
		Todo List
			Todo Item
				Checkbox
				Text
				Button Edit
				Button Delete
				

Actions:
	Delete todo List

	Add todo List

	Add a task

	Сomplete a task

	Delete a task

	Edit a task



**BACKEND**

{
	id: v4(),
	name,
	complete: (false/true)
}

HTTP methods:

	GET - get ToDo list (200 (OK), 404 (Not Found),400 (Bad Request))

	POST - add a task to ToDo list (201 (Created), 404 (Not Found), 409 (Conflict))

	PUT - edit a task in ToDo list (200 (OK), 204 (No Content), 404 (Not Found))

	DELETE - delete a task from ToDo list (200 (OK), 204 (No Content), 404 (Not Found)


	
	
GET/todolists/:id 
	
POST/todolists

DELETE/todolists/:id 



GET/todolists/:id/items/:id

POST/todolists/:id/items/:id

PUT/todolists/:id/items/:id

DELETE/todolists/:id/items/:id


	
