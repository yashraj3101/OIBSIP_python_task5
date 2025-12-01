💬 Browser-Based Chat Application (Python + Tkinter + Sockets)
📘 Project Overview

This is a real-time chat application built using Python sockets and a Tkinter GUI.
It allows multiple users to join a common chat room and communicate instantly through a server–client architecture.

The app supports:

Real-time text messaging

GUI-based client using Tkinter

Socket-based server handling multiple clients

Username login

Colored message formatting

File upload UI option

Emoji support (via emoji library)

This project is a great introduction to networking, threading, and GUI development in Python.

1. Server Starts

Listens on 127.0.0.1:1489

Accepts multiple clients

Sends join notifications to all users

2. Client Connects

Enters a username

Connects to server via socket

Sends and receives messages in separate threads

3. Messaging

Every message is formatted as:
username ~ message

Server broadcasts it to all connected clients
