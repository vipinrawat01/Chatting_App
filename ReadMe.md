# Chatting App

A real-time chat application built with Node.js and Socket.io, designed for seamless communication between users. The app allows users to send and receive messages instantly in a secure and interactive environment.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Backend Details](#backend-details)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The **Chatting App** is a real-time communication platform that allows users to chat with each other instantly. It uses Socket.io to provide real-time bidirectional communication and is built using Node.js for the backend and vanilla JavaScript for the frontend.

## Features

- **Real-Time Messaging**: Send and receive messages instantly.
- **User Interface**: Simple and responsive design for easy interaction.
- **Socket.io Integration**: Real-time communication using Socket.io for event-based messaging.
- **Message History**: Keeps track of all messages in the current session.
- **Private Chat**: Allows users to send private messages to others.

## Installation

### Prerequisites

- Node.js
- npm (Node package manager)

### Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/YourGitHubUsername/ChattingApp.git
    cd ChattingApp
    ```

2. Install the required Node.js packages:
    ```sh
    npm install
    ```

3. Run the server:
    ```sh
    node index.js
    ```

4. Open your browser and navigate to `http://localhost:3000` to start using the chat app.

## Usage

1. Open the chat app in your browser by going to `http://localhost:3000`.
2. Enter a username and join the chat room.
3. Start sending messages and communicate in real-time with other users connected to the app.

## How It Works

The app uses Socket.io for real-time communication between clients and the server:

1. **Connection**: When a user enters the chat room, the client connects to the server using Socket.io.
2. **Message Handling**: When a user sends a message, it is emitted to the server via Socket.io, which then broadcasts the message to all connected users.
3. **Private Messages**: Private messages can be sent between users by specifying the target recipient’s username.
4. **User Disconnect**: When a user disconnects, the server handles the disconnection and updates the active user list.

## Backend Details

The backend is built with Node.js and uses Socket.io for real-time communication:

- `index.js`: Main server file handling Socket.io events and message broadcasting.
- `public/index.html`: Frontend HTML page that connects to the server and handles user interface.
- `public/script.js`: JavaScript file that manages the client-side interactions, such as sending and receiving messages.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit changes (`git commit -am 'Add your feature'`).
4. Push the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Vipin Rawat - [GitHub](https://github.com/vipinrawat01)

Feel free to reach out for questions or suggestions!