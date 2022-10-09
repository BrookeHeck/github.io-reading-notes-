# Message Queues

## Socket.io Chat Example
1. Explain to a non-technical recruiter what the Chat Example (above) does.
- The chat example is a server uses express and socket.io to allow clients to connect and communicate
- Express is used so that the client has a path to connect to through the browser
- Socket.io is used to establish a TCP connection once the client has connected
- The server listens to messages sent from clients and then broadcasts it to the other clients

2. What proof of life are we getting on the backend from the above app?
- You can see that express is working because it is console logging connected to PORT 3000
- You can see that socket.io is working because it is console logging every time a client connects.

3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
- except

## Rooms
1. What is a room and how might a room be useful?
- A room is a channel within the server that clients can connect to be separated from everyone on the server

2. How do you join a room?
- By using the join and leave methods you can join and leave rooms
- These methods take a string as an argument, the name of the room is that string. When emitting events to specific rooms, use this string

3. How do you leave a room?
- Same way as join, but use the leave method

## Namespaces
1. What is a Namespace and what does it allow you to do?
- Namespaces allow you to split the logic of your application

2. Each namespace potentially has its own what? (hint: 3 things)
- Event handlers
- Rooms
- Middlewares

3. Discuss a possible use case for separate namespaces
- You could have namespace that handles orders submitting orders and you could have another namespace for drivers looking ready for pickup messages

## Things I want to learn more about

### Links
[Socket.io Chat Example](https://socket.io/get-started/chat/)
[Rooms](https://socket.io/docs/v4/rooms)
[Namespaces](https://socket.io/docs/v4/namespaces/)
[Socket.io Emit Cheat Sheet](https://socket.io/docs/v4/emit-cheatsheet/)