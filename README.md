# TaskFlow - Task Manager

A responsive browser-based task board built with semantic HTML, CSS and vanilla JavaScript.

## Live demo
https://aditya-taskflow-standalone.vercel.app

## Features
- Create, complete and delete tasks
- Set a priority label (High, Normal or Low)
- Filter All, Active and Completed tasks
- Persist tasks in browser localStorage
- Responsive layout for desktop and mobile
- Accessible input labels and task-status feedback

## Run locally
Open `index.html` in a modern browser. No build step or dependencies are required.

## Technical notes
- The interface uses DOM event handling and browser localStorage.
- User-provided task text is rendered with `textContent`, not HTML injection.
- Data stays in the current browser. It is not synced to a server.
- This is a front-end portfolio demo; it does not include authentication or a backend.
