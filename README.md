# chat-application
 * COMPANY * : CODTECH IT SOLUTIONS
 * NAME * : Sankar R
 * INTERN ID * : CT04DN408
 * DOMAIN * : FULL STACK WEB DEVELOPMENT
 * DURATION * : 4 WEEKS
 * MENTOR * : NEELA SANTHOSH

 * DESCRIPTION * :
                  In the modern digital world, real-time communication is an essential feature of various web-based platforms, especially in social networking, customer support systems, and collaborative tools. This project aims to develop a Real-Time Chat Application that enables users to communicate instantly over the web using WebSocket or Socket.IO, providing seamless two-way communication between clients and the server.
Objective:
The main objective of this project is to build a fully functional, live chat application with both frontend and backend integration that supports real-time data exchange. This application ensures that any message sent by one user is instantly delivered to all connected users without the need to refresh the page or perform additional server requests. By utilizing WebSocket or Socket.IO technology, this application offers efficient, event-driven communication between the client and the server, reducing latency and providing a smooth user experience.
Features of the Application:
User Interface (Frontend):
A simple and interactive user interface designed using HTML, CSS, and JavaScript.
Displays a list of online users and active chat rooms.
Provides an input box for typing messages and a send button to deliver the message.
Shows real-time messages from other users without page reload.
Backend Server (Backend):
Developed using Node.js with Express.js framework.
Utilizes Socket.IO or WebSocket API to establish and maintain a real-time connection between the server and multiple clients.
Manages multiple chat rooms and broadcasts messages to connected users.
Handles user connections, disconnections, and message transfers efficintly.
Real-Time Communication:
Implements bidirectional communication that allows data to be sent and received in real-time.
Automatically updates all users’ chat windows whenever a new message is sent by any user.
Maintains the state of user activity (online or offline).
Additional Functionalities:
Notification alerts when a new user joins or leaves the chat room.
Display of message timestamps.
Simple error handling for connection failures or message delivery issues.
Technologies Used
Frontend
Framework: Vite (React + TypeScript)
Styling: Tailwind CSS
Backend
Server: Node.js
Framework: Express
Real-time Communication: Socket.IO
Cross-Origin Resource Sharing: CORS
Working of the Application:
When a user opens the chat application, the client establishes a Socket.IO connection with the server.
The server listens for events like user joining, sending messages, and disconnecting.
Once a message is sent from the client, it is captured by the server and immediately broadcasted to all connected clients.
All users in the chat room receive the new message in real-time, enhancing user interactivity.
The server handles the connection lifecycle, including new connections and disconnections.
Advantages of Using Socket.IO:
Low Latency: Provides near-instant communication.
Reduced Server Load: Unlike HTTP polling, WebSocket maintains a single open connection for constant data flow.
Scalability: Suitable for applications with a high number of concurrent users.
Ease of Use: Socket.IO simplifies event-based real-time communication handling.
Conclusion:
This real-time chat application demonstrates the power of real-time web technologies to provide instant communication between multiple users. By integrating Socket.IO with Node.js and Express.js, the application achieves efficient and scalable message delivery, making it an excellent base for building advanced communication platforms such as customer support systems, group chat applications, or live collaborative tools. This project also enhances understanding of full-stack development, real-time event handling, and client-server architecture.


* OUTPUT * :

![Image](https://github.com/user-attachments/assets/46b2)033c-42e3-4088-8ccb-496fdb085ee1
  
