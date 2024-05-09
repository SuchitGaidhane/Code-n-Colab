# Code-n-Collab - Online Collaborative Code Editor

Welcome to the collaborative code editor - Code-n-Colab ! This project allows multiple users to simultaneously collaborate, edit and run code in real-time with integrated compilaer within a web-based environment. It also shows stats such as CPU run time and Memory used by the code.

## Features

- Real-time code editing: Changes made by one user are immediately visible to all other users in the same editing session.
- Syntax highlighting: Code is automatically formatted and color-coded to improve readability and comprehension.
- User management: The system handles user joining and leaving with editing sessions seamlessly.
- Persistent editor contents: User contributions are saved persistently, ensuring that no data is lost even after a page refresh.

## ScreenShots
![Login_Page](https://github.com/SuchitGaidhane/Code-n-Colab/assets/131668852/092d9b53-367c-4198-8355-5041fff50b3f)
![InnerPage](https://github.com/SuchitGaidhane/Code-n-Colab/assets/131668852/f7563a28-3512-471e-9b2f-9265424da2c9)
![InnerPage2](https://github.com/SuchitGaidhane/Code-n-Colab/assets/131668852/650ca240-aba9-4361-b435-47e47fd3f79e)
![Collab_Proj](https://github.com/SuchitGaidhane/Code-n-Colab/assets/131668852/e52e3df3-62f3-499a-80d0-74989f620a16)


## Technologies Used

- **Node.js**: Powers the backend server responsible for managing user connections and handling code synchronization.
- **Express.js**: Provides a robust framework for building web applications, facilitating routing and middleware functionality.
- **Socket.io**: Enables real-time bidirectional communication between clients and the server, essential for synchronizing code edits.
- **CodeMirror**: A versatile text editor library that supports syntax highlighting and other code editing features.
- **Tailwind**: The frontend components are developed using these standard web technologies - Tailwind, to create an intuitive user interface and enhance user experience.

## Note: Create the API key from:

https://rapidapi.com/Glavier/api/online-code-compiler


and edit it in .env file under client and copy and paste .env it in the server.

## Installation ⬇️

1. Clone the project
  ```sh
    git clone https://github.com/SuchitGaidhane/Code-n-Colab
  ```

2. Navigate to the **```server```** folder from project root by
  ```sh
  cd server
  ```
  
 * Install all npm packages
    ```sh
    npm i
    ```
 * Run local dev server
    ```sh
    npm run dev
    ```
3. Navigate to the **```client```** folder from project root by
  ```sh
  cd client
  ```
  
 * Install all npm packages
    ```sh
    npm i
    ```
 * Run local dev server
    ```sh
    npm run dev
    ```
4. Open http://localhost:5173/ and the project will open

## Future scope 📈

- [ ] Add audio chat
- [ ] Collaborative drawing board like jamboard
- [ ] Sharing code through other platforms like Slack, Discord etc.
- [ ] Integrating better code formatting and styling in code editor
- [ ] Convert website to Desktop app
- [ ] Adding unit and integration tests
