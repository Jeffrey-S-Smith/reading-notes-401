Readings: Socket.io
===================

Reading
-------

[Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

1. What is a Web Socket?

    A WebSocket is a persistent bi-directional communication channel between a client (e.g. a browser) and a backend service. In contrast with HTTP request/response connections, websockets can transport any number of protocols and provide server-to-client message delivery without polling.

2. Describe the Web Socket request/response handshake and what happens once the connection is established.

    The handshake starts with an HTTP request/response, allowing servers to handle HTTP connections as well as WebSocket connections on the same port. Once the connection is established, communication switches to a bidirectional binary protocol which does not conform to the HTTP protocol.

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a **\_\_**\_\_ from that client.

message

[Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)

1. What does the event handler `io.on()` do?

Listening to events. There are several ways to handle events that are transmitted between the server and the client.

2. Describe some possible proof of life or proof that the code works as expected

proof of concept would show whether an idea is feasible from a technology standpoint. For startups, a proof of concept would demonstrate financial viability.

3. What does socket.emit() do?

We can send the message to all the connected clients, to clients on a namespace and clients in a particular room. To broadcast an event to all the clients, we can use the io. sockets. emit method. Note − This will emit the event to ALL the connected clients (event the socket that might have fired this event).

[Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

socket-io. client is the code for the client-side implementation of socket.io. That code may be used either by a browser client or by a server process that is initiating a socket.io connection to some other server (thus playing the client-side role in a socket.io connection).

2. When would you use Socket.IO?

It enables realtime, bi-directional communication between web clients and server. It has two parts: a client-side library that runs in the browser, and a server-side library for node.

3. When would you use WebSockets?

When should WebSockets be used?
When a client needs to react quickly to a change (especially one it cannot predict), a WebSocket may be best. Consider a chat application that allows multiple users to chat in real-time. If WebSockets are used, each user can both send and receive messages in real-time

Videos
------

[OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

1. What are a couple of key takeaways from this video?

[TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

1. Translate the gist of this video to a non-technical friend

Bookmark and Review
-------------------

[Socket.io Documentation](https://socket.io/docs/)

[Socket.io Server API](https://socket.io/docs/server-api)

[Socket.io Client API](https://socket.io/docs/client-api)

[Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)

## Things I want to know more about