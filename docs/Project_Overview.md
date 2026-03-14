# Project Overview – Java Chat Messenger with Log Facility

## Introduction

Java Chat Messenger is a simple client-server communication application developed using Java Socket Programming.
The application allows two-way communication between a client and server over a network connection.

## Objective

The objective of this project is to demonstrate the implementation of networking concepts in Java such as sockets, streams, and client-server architecture.

## System Architecture

Client → Socket Connection → Server

The client sends messages to the server using TCP communication.
The server receives the message, displays it on the console, logs the message into a file, and sends a response back to the client.

## Key Components

### Client

* Establishes connection with the server
* Sends messages to the server
* Receives responses from the server

### Server

* Listens for incoming client connections
* Accepts client requests
* Handles message exchange
* Stores communication logs

## Logging Mechanism

The server maintains a log file (`chat_log.txt`) where all chat messages are recorded.
This is implemented using Java File Handling with `FileWriter` and `BufferedWriter`.

Example Log Entry:

Client : Hello
Server : Hi

## Technologies Used

* Java
* Socket Programming
* Java IO Streams
* TCP Networking

## Possible Enhancements

* Multi-client support
* Graphical user interface using Java Swing
* Timestamped message logs
* Secure communication using encryption

---

# 📂 Final Project Structure

```
Java-Chat-Messenger-With-Log-Facility
│
├── src
│   └── chatmessenger
│        ├── Client.java
│        └── Server.java
│
├── logs
│   └── .gitkeep
│
├── docs
│   └── project_overview.md
│
├── README.md
└── .gitignore
```