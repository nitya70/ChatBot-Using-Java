# Chatbot Java GUI Client Server using Database

# Chatbot Java Application

A Java-based client-server chatbot application developed using the NetBeans IDE. This project demonstrates the fundamentals of socket programming, modular design (backend/frontend separation), and chatbot interaction in a GUI-based environment.

## 📂 Project Structure

Chatbot-Java/

│
├── backend/ # Core logic and data handling

├── frontend/ # GUI components for client interaction

├── chatserversocket/ # Server-client socket communication

├── build.xml # Ant build script for NetBeans

├── manifest.mf # Manifest for JAR packaging

├── README.md # Project documentation


## 💡 Features

- Basic chatbot response handling using predefined answers.
- Graphical User Interface (GUI) built with Java Swing.
- Server-client architecture using Java Sockets.
- Modular code separation (backend, frontend, server).

## 🚀 Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or above
- NetBeans IDE (recommended for GUI design and Ant build)
- Optional: Apache Ant for command-line builds

### Running the Project

1. **Using NetBeans:**
   - Open the project in NetBeans.
   - Right-click the project and choose `Run`.

2. **Using Command Line (Ant):**
   ```bash
   ant clean
   ant build
   java -cp dist/Chatbot.jar chatbot.application.client.Client


🧠 How it Works
The server handles incoming client connections and dispatches messages.

The client sends user input to the server and receives a chatbot response.

The backend includes the logic for parsing and responding to user queries.

GUI forms are designed using NetBeans and use event listeners for interactivity.

🛠️ Customization
You can modify:

Answer.java – to change or add chatbot responses.

Client.form and Client.java – to update the UI.

ChatServer.java – to extend server capabilities.

📦 Packaging
Use the provided build.xml and manifest.mf to compile and package the project into an executable JAR.
