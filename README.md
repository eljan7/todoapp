#Simple Todo App

A modular Todo application built with JavaScript ES6 modules. The project focuses on clean architecture, reusable components, and form validation, allowing users to manage tasks efficiently through a dynamic interface.

#Functionality

The application allows users to create, track, and manage tasks in a simple and interactive way.

Users can:

Add new todos using a modal form
Enter a task name and optional due date
See validation feedback in real time while typing
Mark tasks as completed using a checkbox
Delete tasks from the list

Each todo item is dynamically generated from a template and includes its own event handling for completion and deletion.

After submitting a new task:

The form resets automatically
Validation errors are cleared
The submit button returns to its disabled state

#Technology

This project is built using:

JavaScript (ES6 modules) — for modular, component-based architecture
HTML5 & CSS3 — for structure and styling
UUID (via CDN) — to generate unique identifiers for each todo
Key Techniques
Object-Oriented Programming (OOP)
Todo class handles rendering and behavior of each task
FormValidator class manages validation logic
DOM Manipulation
Dynamic creation and insertion of todo elements
Event listeners for user interaction
Form Validation
Built-in browser validation API
Real-time error display
Controlled submit button state
Separation of Concerns
components/ for classes
utils/ for constants and configuration
index.js for app initialization

#Deployment

## Deployment

This project is deployed on GitHub Pages:

- [ADD LINK HERE](https://github.com/eljan7/todoapp)
