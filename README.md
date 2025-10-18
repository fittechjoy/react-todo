# Implementing and Testing a Todo List Component in React
## Objective:
- Learn to create, implement, and test a fully functional Todo List component in React using Jest and React Testing Library.
- This task focuses on hands-on coding and testing to ensure the component operates correctly under various scenarios.
- Create a new react app named react-todo.
 
### Task Description:
- You will build a Todo List component that allows users to add, delete, and toggle the completion status of todo items. - - This task will also include writing comprehensive tests to verify each functionality of the component.
 
### Specific API and Component Details:
#### Component Requirements:
1. TodoList should display a list of todo items fetched from a static array.
2. AddTodoForm allows users to add new todos.
3. Todos can be toggled between completed and not completed by clicking on them.
4. Todos can be deleted individually.
   
#### Step 1: Setup the Todo List Component
- Create the TodoList Component:
- Initialize the component state with a few todos for demonstration.
- Include methods for adding, toggling, and deleting todos.
 
#### Step 2: Write Tests Using Jest and React Testing Library
- Set Up Testing Environment:
- Ensure you have Jest and React Testing Library installed:
> npm install --save-dev jest @testing-library/react @testing-library/jest-dom
 
- Create a _tests_ directory in your src folder to organize your test files.
 
#### Test File Setup:
- Create a test file for the TodoList component, e.g., TodoList.test.js, in the _tests_ directory.
- Write Initial Render Test:
- verify that the TodoList component renders correctly.
- Ensure that the initial state (a few demo todos) is rendered.
- Test Adding Todos:
- Write a test to verify that a new todo can be added.
- Use fireEvent to simulate user input and form submission.
- Test Toggling Todos:
- Write a test to verify that a todo item can be toggled between completed and not completed.
- Test Deleting Todos:
- Write a test to verify that a todo item can be deleted.
- Update Scripts in package.json
- Edit the scripts section in your package.json
 
“scripts”: {
    “test”: “jest”
}
 
- Run Tests:
- Run your tests using Jest to ensure they pass:
> npm test
 
#### Well done on completing this project! Let the world hear about this milestone achieved.