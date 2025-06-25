# Real-Time Chat Application

A Spring Boot-based real-time chat application using WebSocket technology. This project demonstrates the implementation of live chat functionality between multiple users in a web-based environment.

---

## 💡 Features

- Real-time messaging using WebSocket (STOMP protocol)
- User-friendly chat UI (HTML + Bootstrap)
- WebSocket connection with SockJS fallback
- Simple login screen (username based)
- Join/Leave notifications
- Time-stamped chat messages
- Active user indication

---

## 🛠️ Tech Stack

- **Backend:** Java, Spring Boot, Spring WebSocket
- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Messaging Protocol:** STOMP over WebSocket
- **Build Tool:** Maven

---

## 📁 Project Structure

chat-app/
├── src/
│ ├── main/
│ │ ├── java/com/example/chatapp/
│ │ │ ├── config/ # WebSocket Configuration
│ │ │ ├── controller/ # Controller for messaging
│ │ │ ├── model/ # ChatMessage model
│ │ │ └── ChatAppApplication.java
│ │ └── resources/
│ │ ├── static/ # HTML, CSS, JS files
│ │ └── application.properties
├── pom.xml
└── README.md


---

## 🚀 How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/ARCHITADIXIT/CHAT-APP.git
2. Navigate to project
  \cd CHAT-APP

3. Build the project
  mvn clean install

4. Run the app
  mvn spring-boot:run

5. Open in browser
  http://localhost:8080

GitHub - ARCHITADIXIT

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.
---
