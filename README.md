# TASK-3-MULTITHREADED-CHAT-APPLICATION
**COMPANY** : CODTECH IT SOLUTIONS

**NAME** :ROHIT KISHOR PAWAR

**INTERN ID** : CT08HJD

**DOMAIN** : JAVA PROGRAMMING

**BATCH DURATION** : December 30th,2024 to January 30th,2025

**MENTOR NAME** : NEELA SANTHOSH

**DESCRIPTION** :

Creating a client-server chat application using Java sockets and multithreading is an excellent way to understand network programming and concurrency in Java. This task involves setting up a server that can handle multiple clients simultaneously, allowing them to communicate in real-time. Here's a detailed description of how to achieve this:

**Overview**
The chat application consists of two main components:

Server: Listens for incoming client connections and manages communication between clients.

Client: Connects to the server and allows users to send and receive messages.

**Server Implementation**
The server uses Java sockets to listen for incoming connections on a specified port. When a new client connects, the server creates a new thread to handle communication with that client. This approach ensures that the server can handle multiple clients simultaneously without blocking.

**Key Components**:
ServerSocket: Listens for incoming client connections.

Socket: Represents a connection between the server and a client.

ClientHandler: A class that implements Runnable and handles communication with a single client. Each client handler runs in its own thread.


**Client Implementation**
The client connects to the server using a socket and allows the user to send and receive messages. The client runs two threads: one for reading user input and sending messages to the server, and another for listening to incoming messages from the server.

**Key Components**:
Socket: Connects to the server.

BufferedReader: Reads input from the user and the server.

PrintWriter: Sends messages to the server.

The ChatServer class listens for incoming client connections on a specified port.

When a new client connects, a ClientHandler thread is created to handle communication with that client.

The broadcastMessage method sends messages to all connected clients except the sender.

The ClientHandler class handles reading messages from the client and broadcasting them to other clients.

The ChatClient class connects to the server using the server's address and port.

It creates a thread to listen for incoming messages from the server and print them to the console.

The main thread reads user input from the console and sends it to the server.

**Running the Application**
Start the Server:

Run the ChatServer class. The server will start and listen for incoming connections.

Start the Clients:

Run the ChatClient class in multiple instances (in different terminal windows or IDE instances). Each client will connect to the server and allow users to send and receive messages.

This application demonstrates the use of Java sockets and multithreading to create a functional chat application with a server and multiple clients communicating in real-time. If you have any more questions or need further assistance, feel free to ask!


**OUTPUT** :
https://github.com/rohitpawar0011/TASK-3-MULTITHREADED-CHAT-APPLICATION/issues/1#issue-2797676852
