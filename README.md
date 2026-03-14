# Java Chat Messenger with Log Facility

## 📌 Overview

Java Chat Messenger is a simple **client-server chat application** developed using **Java Socket Programming**.
The application enables real-time communication between a client and a server over a TCP connection.

It also includes a **chat logging feature**, which records all exchanged messages into a log file for future reference.

This project demonstrates fundamental concepts of **Java networking, I/O streams, and client-server architecture**.

---

## 🚀 Features

* Real-time communication between client and server
* TCP-based socket communication
* Console-based chat interface
* Automatic message logging to file
* Simple and lightweight architecture
* Easy to extend for multi-client systems

---

## 🛠 Technologies Used

* **Java**
* **Socket Programming**
* **Java IO Streams**
* **File Handling (FileWriter & BufferedWriter)**

---

## 📂 Project Structure

```
Java-Chat-Messenger-With-Log-Facility
│
├── src
│   └── chatmessenger
│        ├── Client.java
│        └── Server.java
│
├── logs
│   └── chat_log.txt
│
├── docs
│   └── project_overview.md
│
├── README.md
└── .gitignore
```

---

## ⚙️ How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/Java-Chat-Messenger-With-Log-Facility.git
```

### 2️⃣ Navigate to Source Directory

```
cd Java-Chat-Messenger-With-Log-Facility/src/chatmessenger
```

### 3️⃣ Compile the Program

```
javac Server.java
javac Client.java
```

### 4️⃣ Run the Server

```
java Server
```

### 5️⃣ Run the Client (in another terminal)

```
java Client
```

---

## 💬 How the Application Works

1. The **Server** starts and waits for a client connection on port `2100`.
2. The **Client** connects to the server using a socket.
3. Messages are exchanged between client and server through input/output streams.
4. The server stores each message in **chat_log.txt**.
5. Communication continues until the client terminates the session.

---

## 📝 Chat Log Example

Example content stored in the log file:

```
Client : Hello
Server : Hi
Client : How are you?
Server : I am fine
```

The log file helps maintain a record of all chat communication.

---

## 📸 Example Console Interaction

**Server**

```
Server application is running...
Server is waiting for the client at port number 2100
Connection established with the Client...
Client says : Hello
Enter message for client :
Hi
```

**Client**

```
Client application is running...
Connection established with the Server...
Hello
Server says : Hi
```

---

## 🔮 Possible Future Enhancements

* Support for **multiple clients**
* **Graphical user interface** using Java Swing
* **Timestamped message logging**
* **Encrypted communication**
* Message history retrieval

---

## 👨‍💻 Author

**Sahil Rajaram Thorat**
Java Backend Developer (Fresher)
Pune, Maharashtra, India

GitHub: https://github.com/SahilThorat11

---

## 📄 License

This project is licensed under the MIT License.
