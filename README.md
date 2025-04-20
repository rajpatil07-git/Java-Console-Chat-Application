# Java Console Chat Application (Client-Server)

This is a simple **Java-based chat application** that runs in the command line (CMD/Terminal). It demonstrates basic **client-server communication** using **TCP sockets**. Messages can be sent back and forth between the client and the server until the client types `gn` to terminate the session.

# Files Included

- `Server.java` – Listens for client connections and responds to messages.
- `Client.java` – Connects to the server and allows the user to send messages.
  
---

# Features

- Two-way communication between client and server
- Console-based user interaction
- Graceful exit with the command `gn`
- Built using core Java classes:
  - `Socket`, `ServerSocket`
  - `BufferedReader`, `InputStreamReader`, `PrintStream`

---

# How to Run

# 1. Compile both programs:

```bash
javac Server.java
javac Client.java
