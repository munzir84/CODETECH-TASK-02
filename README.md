# CODETECH-TASK-01
Name:- Munzir Husain
Company:- CODTECH IT SOLUTIONS PVT.LTD
ID:- CT6WDS2527
Domain:- SOFTWARE DEVELOPMENT
Duration:-2 Months
Mentor:-Muzammil Ahmed

Project Goal:

Develop a web-based application that allows users to:
Create new to-do items.
Mark to-do items as completed.
Edit or delete existing to-do items.
Potentially:
Prioritize tasks (e.g., high, medium, low).
Filter tasks (e.g., show completed/incomplete).
Store tasks locally (using browser's local storage).
2. Project Structure:

HTML (index.html):
Structure the user interface:
Create an input field for entering new tasks.
Create a button to add new tasks.
Create a list (e.g., an unordered list - <ul>) to display existing tasks.
Optionally, include buttons for editing and deleting tasks.
CSS (style.css):
Style the appearance of the to-do list:
Set colors, fonts, and spacing.
Apply styles to different elements (input fields, buttons, list items).
Create visual cues for completed tasks (e.g., strikethrough, different color).
JavaScript (script.js):
Handle the application's logic:
Add Task:
Get the user's input from the input field.
Create a new list item (<li>) for the task.
Append the new list item to the existing list.
Clear the input field.
Mark as Complete:
Toggle a class or attribute on the list item to visually indicate completion.
Edit Task:
Allow the user to edit the text of an existing task.
Delete Task:
Remove the selected list item from the list.
Local Storage (Optional):
Store the list of tasks in the browser's local storage.
Retrieve stored tasks when the page loads.
3. Basic Implementation Steps:

Set up HTML structure: Create the basic HTML elements as described above.
Add basic CSS styling: Apply initial styles to make the interface visually appealing.
Implement "Add Task" functionality:
Get user input.
Create a new list item.
Append the item to the list.
(Optional) Implement "Mark as Complete" functionality:
Add a click event listener to each list item.
Toggle a class or attribute on the clicked item.
(Optional) Implement "Edit Task" functionality:
Add an edit button to each list item.
Allow the user to modify the task text.
(Optional) Implement "Delete Task" functionality:
Add a delete button to each list item.
Remove the clicked item from the list.
(Optional) Implement Local Storage:
Use JavaScript's localStorage API to store and retrieve task data.
4. Key JavaScript Concepts:

DOM Manipulation: Working with and modifying HTML elements using JavaScript.
Event Handling: Handling user interactions (e.g., button clicks).
Arrays: Storing and manipulating lists of tasks.
Local Storage: Storing data in the browser's local storage.
