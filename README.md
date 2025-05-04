# Java Group Chat

This is a basic group chat application built using Java sockets. It allows multiple clients to connect to a server and exchange messages in real-time.

## Features

- Multi-client chat using TCP sockets
- Each client handled in a separate thread
- Broadcasts messages to all connected users (except sender)
- Graceful disconnection handling

## Technologies

- Java (Plain Java SE)
- Sockets
- Multi-threading (Runnable and Threads)

## Project Structure

- `Server.java` - Responsible for accepting clients and starting threads for each client
- `ClientHandler.java` - Handles communication with each individual client
- `Client.java` - Connects to the server and sends/receives messages

