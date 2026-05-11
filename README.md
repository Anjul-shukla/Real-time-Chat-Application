Real-Time Chat Application

A real-time chat application built using Java Spring Boot, WebSocket, STOMP, and SockJS for seamless client-server communication.

🚀 Features
Real-time messaging
WebSocket-based communication
STOMP messaging protocol
SockJS fallback support
Topic-based message broadcasting
Lightweight and scalable backend structure
🛠️ Technologies Used
Java
Spring Boot
WebSocket
STOMP
SockJS
Maven
📂 Project Structure
config/ → WebSocket configuration
controller/ → Chat message handling
model/ → Message model classes
templates/ → Frontend chat UI
⚙️ How It Works
Client connects to the WebSocket endpoint /chat
Messages are sent to /app/sendMessage
Server broadcasts messages to /topic/message
All connected clients receive updates instantly
▶️ Run the Project
mvn spring-boot:run

Open in browser:

http://localhost:8080/chat
📌 Future Improvements
User authentication
Private messaging
Database integration
Message history
Online/offline status tracking
