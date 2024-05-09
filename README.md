# Code-n-Collab - Online Collaborative Code Editor

Welcome to the collaborative code editor - Code-n-Colab ! This project allows multiple users to simultaneously collaborate, edit and run code in real-time with integrated compilaer within a web-based environment. It also shows stats such as CPU run time and Memory used by the code.

## Features

- Real-time code editing: Changes made by one user are immediately visible to all other users in the same editing session.
- Syntax highlighting: Code is automatically formatted and color-coded to improve readability and comprehension.
- User management: The system handles user joining and leaving with editing sessions seamlessly.
- Persistent editor contents: User contributions are saved persistently, ensuring that no data is lost even after a page refresh.

## Demo

[![Watch the video](https://img.youtube.com/vi/yIZB7ypqpD0/0.jpg)]

## Technologies Used

- **Node.js**: Powers the backend server responsible for managing user connections and handling code synchronization.
- **Express.js**: Provides a robust framework for building web applications, facilitating routing and middleware functionality.
- **Socket.io**: Enables real-time bidirectional communication between clients and the server, essential for synchronizing code edits.
- **CodeMirror**: A versatile text editor library that supports syntax highlighting and other code editing features.
- **Tailwind**: The frontend components are developed using these standard web technologies - Tailwind, to create an intuitive user interface and enhance user experience.

## Note: Create the API key from:

https://rapidapi.com/Glavier/api/online-code-compiler
and edit it in .env file under server.

## Future scope 📈

- [ ] Add audio chat
- [ ] Collaborative drawing board like jamboard
- [ ] Sharing code through other platforms like Slack, Discord etc.
- [ ] Integrating better code formatting and styling in code editor
- [ ] Convert website to Desktop app
- [ ] Adding unit and integration tests