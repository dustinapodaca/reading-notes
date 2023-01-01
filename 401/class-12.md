<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 401 Reading Notes

## Class 12 Reading Notes

### Web Sockets

```
1. What is a Web Socket?
  - A Web Socket is a communication protocol that allows for a full-duplex, persistent connection between a client and server over the web.

2. Describe the Web Socket request/response handshake and what happens once the connection is established.
  - The Web Socket handshake involves an initial request/response exchange between the client and server. The client sends an HTTP request to the server, including an "Upgrade" header to indicate that it wants to establish a Web Socket connection. If the server agrees to upgrade the connection, it sends back an HTTP response with a 101 status code, indicating that the connection has been upgraded to a Web Socket. Once the handshake is complete, the client and server can exchange messages over the Web Socket connection, without the need for further request/response exchanges.

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
  - Web Sockets provide a standardized way for the server to send content to a client without first receiving a request from that client. This allows for real-time, bidirectional communication between the client and server, without the need for the client to continuously send requests to the server in order to receive updates.

```

### Socket.io Tutorial

```
1. What does the event handler io.on() do?
  - The event handler `io.on()` listens for incoming events and triggers a callback function when an event is received.
2. Describe some possible proof of life or proof that the code works as expected
  - A common way to test that the code is working as expected is to use the `console.log()` function to print messages to the console when certain events occur. For example, you could log a message when a new client connects to the server, or when a client sends a message to the server.
  - Another way to test the code is to use a visual indicator, such as displaying a message on the user interface when an event occurs. For example, you could display a notification when a new message is received from the server.
3. What does socket.emit() do?
  - The `socket.emit()` function is used to send an event from the client to the server. The function takes two arguments: the name of the event and the data to be sent with the event. The server can then listen for this event and respond accordingly.

```

### Socket.io vs. Web Sockets

```
1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
  - WebSocket is a protocol that allows for a bi-directional, full-duplex communication channel between a client and server over the Web. Socket.IO is a library that provides real-time, bidirectional communication between a client and server using WebSockets as the communication channel. Socket.IO abstracts the WebSockets API and provides additional features such as automatic reconnection and message event parsing.
2. When would you use Socket.IO?
  - Socket.IO is often used when building real-time applications such as chat applications, online games, and collaboration tools.
3. When would you use WebSockets?
  - WebSockets can be used in situations where you need a lightweight, low-latency communication channel between a client and server.

```

### OSI Model Explained

```
1. What are a couple of key takeaways from this video?
- The OSI model is a framework that describes how different communication protocols interact with each other to transmit data over a network.
- The OSI model consists of 7 layers, each with a specific role in the transmission of data.
- The layers of the OSI model can be thought of as a stack, with the physical layer at the bottom and the application layer at the top.

```

### TCP Handshake Explained

```
1. Translate the gist of this video to a non-technical friend
  - When a client wants to communicate with a server over the Internet, it needs to establish a connection with the server first. This process is called a "handshake."
  - The client sends a request to the server to establish a connection.
  - The server responds with a message acknowledging the request.
  - The client sends a final message to confirm that it is ready to start sending and receiving data.
  - Once all three messages have been exchanged, the handshake is complete and the client and server can start communicating with each other.

```
