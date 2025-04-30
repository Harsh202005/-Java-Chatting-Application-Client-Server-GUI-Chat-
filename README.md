🔨 Java Chatting Application 💬 (Client-Server GUI Chat)

A desktop-based chatting application developed in Java using Swing for GUI and Socket programming for real-time communication between a Server and a Client.

📌 Features

Real-time messaging using TCP Sockets

Interactive GUI built with Java Swing

Basic server-client text communication

Message timestamp display

Rich message panel formatting

Scrollable message area

Custom profile icons for client and server

Graceful GUI window controls

📁 Project Structure

Server.java — Handles client connections and receives/sends messages

Client.java — Connects to the server and communicates back

icons/ — Contains images used in GUI (e.g., back button, profile picture, video/phone icons)

💠 Technologies Used

Java SE (Swing, AWT, Sockets, Threads)

Java IO & Networking (java.net, java.io)

Simple multithreaded model for chat flow

🧪 How to Run

Compile and run Server.java first.

Then run Client.java (on the same or different machine using IP).

Use 127.0.0.1 for local testing, or replace with real IP on LAN.

Enter and send messages using the GUI text field.

Make sure both classes are in the same package chatting.application and that the icons/ directory is in your classpath/resource folder.

🚀 Future Enhancements

File transfer support

Voice/video chat

Group chats and user authentication

Message history storage
