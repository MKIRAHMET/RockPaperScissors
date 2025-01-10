# Rock-Paper-Scissors Game - Node.js

Did you know that the game **Rock-Paper-Scissors** can be traced back to the **Han Dynasty (206 BCE - 200 CE)**? It is a classic hand game that has been enjoyed for centuries. In this project, we’ve built an online version where you can play against a Node.js HTTP server using only the core modules.

The server processes requests and compares your choice with its own. The outcome—whether you win, lose, or tie—is displayed on the page.

## Features

- **GET Request**: Displays a simple `index.html` page with a form for selecting rock, paper, or scissors.
- **POST Request**: Accepts the user's choice, compares it to the server's randomly generated choice, and sends the result (win, lose, or tie).
- **404 Handling**: If the user navigates to an undefined route, a `404.html` page is displayed.
- **Name Query**: The user can pass their name via the URL query, and the server logs this when they start playing.

## Requirements

- **Node.js**: This project uses **Node.js** for creating the server and handling HTTP requests.

