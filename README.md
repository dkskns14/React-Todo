Todo App Documentation

Introduction
Todo App using React.js for the frontend and Django for the backend. The Todo App allows users to manage their tasks by adding, editing, and marking them as completed.

Prerequisites
Before starting, ensure you have the following installed on your machine:
1.	Node.js and npm (Node Package Manager)
2.	Python (with pip)
3.	Django (ensure it's installed in your Python environment)
4.	Django REST framework

Frontend Setup (React.js)

1.	Create a new React.js project:
2.	create-react-app Todo-app-frontend   cd Todo-app-frontend
Clear out unnecessary files from the src folder (e.g., App.css, logo.svg, setupTests.js)
Install required dependencies:

npm install axios
Create a new folder called components inside the src folder. This is where we'll put our React components.

Create the following components:
•	Todo List: Renders the list of tasks.
•	Todo Item: Renders individual tasks with options to mark as completed and delete.
•	Add Todo Form: Provides a form to add new tasks.

Set up the component hierarchy and implement functionality to fetch tasks from the backend using Axios.
Implement functionality to add, update, and delete tasks. Use Axios to communicate with the backend API.

Adding New Tasks:
•	Create an input field and a submit button in the AddTodo component to allow users to add new tasks.
•	When the user submits the form, create a new task object with a unique id, the entered text, and completed: false.

 Marking Tasks as Completed:
•	In the TodoItem component, display each task with a checkbox.
•	When a user clicks the checkbox, update the completed property of the corresponding task in the state to true or false.
•	Use CSS to style completed tasks differently (e.g., line-through).

6. Deleting Tasks (Optional):
•	Add a delete button next to each task in the TodoItem component.
•	When the user clicks the delete button, remove the corresponding task from the todos.



