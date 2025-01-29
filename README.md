# Java Chatting Application

## 📌 Overview
This is a real-time **Chatting Application** built using Java. It allows multiple users to communicate over a network using a client-server architecture. The application is designed with **Java Sockets** for message exchange and a simple GUI for user interaction.

## 🚀 Features
- **Multi-User Chat:** Supports multiple clients connecting to a central server.
- **Client-Server Communication:** Uses TCP/IP sockets for reliable data transfer.
- **User-Friendly Interface:** Developed using Java Swing or JavaFX.
- **Message Handling:** Server relays messages between connected users.
- **Cross-Platform:** Runs on Windows, macOS, and Linux.

## 🛠️ Technologies Used
- **Java** - Core programming language.
- **Java Sockets (TCP/IP)** - For networking and real-time messaging.
- **Java Swing / JavaFX** - For building the graphical user interface (GUI).
- **NetBeans IDE** - Development environment.
- **Apache Ant (`build.xml`)** - For building and running the project.

## 📂 Project Structure
```
chatting-application-master/
│── Chatting Application/
│   │── src/chatting/application/
│   │   │── Client.java
│   │   │── Server.java
│   │   │── MessageHandler.java
│   │── nbproject/ (NetBeans project files)
│   │── build.xml (Apache Ant build script)
│   │── manifest.mf (Java Manifest file)
│── .gitignore
│── README.md
```

## 🚀 How to Run
1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/chatting-application.git
   cd chatting-application
   ```
2. **Compile the project using NetBeans or Apache Ant:**
   - If using NetBeans, open the project and run it.
   - If using the command line:
     ```sh
     javac -d bin src/chatting/application/*.java
     java -cp bin chatting.application.Server
     java -cp bin chatting.application.Client
     ```
3. **Start the Server:**
   - Run `Server.java` to start listening for client connections.
4. **Run the Clients:**
   - Execute `Client.java` multiple times to simulate multiple users.
5. **Start Chatting!**

## 📌 Future Enhancements
- User authentication (login system)
- Encrypted messaging
- File sharing support
- Improved UI with JavaFX

## 🤝 Contribution
Feel free to contribute! Fork the repo, make changes, and submit a pull request.

## 📄 License
This project is open-source and available under the MIT License.
