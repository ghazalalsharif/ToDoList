# To-Do List

An individual front-end project by **Ghazal Alsharif**, built with HTML, CSS and JavaScript to practice task management and browser-based persistence.


[Try the live demo](https://ghazalalsharif.github.io/ToDoList/) · [Portfolio](https://ghazalalsharif.github.io/Portfolio-Website/)

![Task dashboard with sample data](https://ghazalalsharif.github.io/Portfolio-Website/assets/projects/todo.png)

Click **Try demo** on the sign-in page to explore without registering. Data stays in your browser. The public demo supports local task commands; general AI replies are disabled until a secure backend is configured.

## Features

- Manage tasks with priorities and deadlines.
- View tasks in a calendar and use a team-task interface.
- Explore registration, sign-in and profile screens.
- Save application data in browser localStorage.
- Local task-command assistant; the original project explored Gemini API integration.

## Run locally

Download this repository and serve its folder with a local static web server, such as the VS Code Live Server extension. Open `index.html` and use sample data. No build step is required.

## Main files

| File | Purpose |
| --- | --- |
| `index.html` | Entry and sign-in screen |
| `home.html`, `home.js` | Task dashboard |
| `team-tasks.html`, `team-tasks.js` | Team-task interface |
| `profile.html`, `profile.js` | Profile interface |
| `db.js` | Browser data storage |
| `chatbot.html`, `chatbot.js` | Chat interface |

## Project scope

This is a learning prototype. Browser storage and client-side authentication are not suitable for real accounts or sensitive information, and team screens do not constitute a deployed multi-user backend. General AI replies are disabled in the public demo. API credentials should be stored on a backend, never in published JavaScript.

## Author

[Ghazal Alsharif](https://github.com/ghazalalsharif) · [Portfolio](https://ghazalalsharif.github.io/Portfolio-Website/)
