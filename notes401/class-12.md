# Socket.io

## Web Sockets
1. What is a Web Socket?
- A Web socket is a communications protocol that sets up communication channels over a single TCP connection. The protocols enable interaction between a browser and a server with lower overhead because once the connection is made, it is kept open. Websocket enables streams of messages on top of TCP.

2. Describe the Web Socket request/response handshake and what happens once the connection is established.
- Handshake starts with an HTTP request/response to establish a connection
  - Client request
    ```
    GET /chat HTTP/1.1
    Host: server.example.com
    Upgrade: websocket
    Connection: Upgrade
    Sec-WebSocket-Key: x3JJHMbDL1EzLkh9GBhXDw==
    Sec-WebSocket-Protocol: chat, superchat
    Sec-WebSocket-Version: 13
    Origin: http://example.com
    ```
    - Server Response
    ```
    HTTP/1.1 101 Switching Protocols
    Upgrade: websocket
    Connection: Upgrade
    Sec-WebSocket-Accept: HSmrc0sMlYUkAGmm5OPpG2HaGWk=
    Sec-WebSocket-Protocol: chat
    ``
    - Once connection is established, the client and server can send WebSocket data back and forth

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
- request

## Socket.io Tutorial
1. What does the event handler io.on() do?
- The event handler for io.on creates a new socket whenever somebody connects connect

2. Describe some possible proof of life or proof that the code works as expected
- You can connect to the port with a web browser and see the messages in the browser
- You could also create a client that connects to the port in the terminal
- The server needs to be running before anything can connect to it

3. What does socket.emit() do?
- Clients can emit events using the emit method on the socket object. If the socket object on the server is listening for these events, the event handler will fire when the events are emitted.

## Socket.io vs Web Sockets
1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
- WebSocket is a communication protocol while Socket.IO is a library that enables this communication protocol

2. When would you use Socket.IO?
- Socket.io helps broadcasting to multiple sockets, so if there are a lot of clients connected, Socket.io can emit to all or just some of the sockets connected.
- When real-time communication is required between multiple clients

3. When would you use WebSockets?
- WebSockets still provide real-time communication, but it is not event-based like Socket.IO and doesn't connect multiple clients. If you only needed to open communication between two clients, you could use web sockets.

## OSI Model Explained
1. What are a couple of key takeaways from this video?
- Everything we were doing before this was at the the upper levels. We started at the very top, with making applications that run in the browser. We moved further down osi model by making APIs, and now we are moving even further down the model by making sockets and TCP connections.

## TCP Handshakes Explained
1. Translate the gist of this video to a non-technical friend
- A three way handshake is like making a phone call to another computer. The client calls the server. The server answers the call and acknowledges the the client. The client acknowledges that that the server has joined the call. Then the two have an open line of communication. 

## Things I want to learn more about

### Links
[Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

[Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)

[Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

[OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

[TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

[Socket.io Documentation](https://socket.io/docs/v4/)

[Socket.io Server API](https://socket.io/docs/v4/server-api)

[Socket.io Client API](https://socket.io/docs/v4/client-api)

[Socket IO Client Tool]()https://amritb.github.io/socketio-client-tool/