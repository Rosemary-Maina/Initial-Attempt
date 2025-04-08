# Initial-Attempt
# Dynamic List Manager

## Objective
This is a simple React application that dynamically allows users to add items to a list using an input field and a button. The design closely follows a provided reference image and uses a clean, modern UI.

## Features
- Users can enter text into an input field.
- Items can be added to a list by clicking the "Add Item" button.
- The input field is cleared after adding an item.
- The list displays each item within a lightly shaded and bordered container.
- Empty submissions are not added to the list.

## Requirements
- Display an empty list on initial load.
- Include an input field for entering text.
- Add a button labeled *"Add Item"*.
- On button click:
  - Add the input field's content to the list.
  - Clear the input field.
- Do not add items when the input field is empty.
- Match the styling to the provided design reference.

## Styling Guidelines
- Minimal and modern design.
- Styled input field and button.
- List items shown inside a bordered and lightly shaded container.
- Polished and professional overall look.

## Expected Behavior

### Initial State
- The list is empty.
- The input field is empty.

### User Action 1
- User types *"First Item"*.
- Clicks *"Add Item"*.
- List displays:
  - First Item

### User Action 2
- User types *"Second Item"*.
- Clicks *"Add Item"*.
- List displays:
  - First Item
  - Second Item

## How to Run
1. Clone the repository.
2. Run npm install to install dependencies.
3. Run npm start to launch the app.
4. Open your browser at http://localhost:3000.

## Submission Guidelines
- Upload the complete React project to a public GitHub repository.
- Ensure the application runs without errors.
- Follow best practices for component structure and state management.
- Submit the GitHub repository link after completion.

---

Happy Coding!
