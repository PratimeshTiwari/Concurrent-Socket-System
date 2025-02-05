Concurrent Socket System

Overview

This project is a simple server-client system where multiple clients can connect to a server at the same time using TCP sockets. 
It ensures smooth communication between the server and clients with the help of multithreading.

Features

	•	Multiple Clients: The server can handle connections from multiple clients at once.
	•	Multithreading: Each client gets its own thread, so the server doesn’t block other clients.
	•	Real-time Communication: Clients can send messages to the server, and the server replies immediately.
	•	Thread Management: Server threads are managed efficiently to avoid overload.
	•	Timeout Feature: If a client takes too long to respond, the server will stop waiting.

How It Works

	1.	Server Side: The server listens for incoming client connections. For each client that connects, a new thread is created to handle that client’s requests.
	2.	Client Side: Clients send messages to the server, and the server replies instantly. Clients can send as many messages as needed.

Technologies Used

	•	Java
	•	Sockets
	•	Multithreading

How to Run

	1.	Clone the repo using git clone 
	2.	Open the project in your IDE.
	3.	Run the server class to start the server.
	4.	Run the client class to connect to the server and send messages.
