Features:
----------------->
->Supports multiple clients connecting to the server.
->Clients can send messages to the server, which are broadcast to all connected clients.
->Uses threads to handle multiple clients simultaneously.

Files:
----------->
->ChatServer.java – Handles multiple client connections and message broadcasting.
->ChatClient.java – Connects to the server and allows users to send and receive messages.

How to Run:
------------------>
1.  To Start the Server
Compile and run the server first:

  javac ChatServer.java
  java ChatServer
  
The server will start listening on port 5000.

2. Start a Client
Open a new terminal and run the client:

  javac ChatClient.java
  java ChatClient

You can run multiple clients to simulate multiple users in the chatroom.

Technologies Used:
------------------------>
->Java
->Sockets (TCP)
->Multi-threading
