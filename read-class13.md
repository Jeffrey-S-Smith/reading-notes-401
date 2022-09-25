Readings: Message Queues
========================

Reading
-------

[Socket.io Chat Example](https://socket.io/get-started/chat/)

1. Explain to a non-technical recruiter what the Chat Example (above) does.
    What is Socket.IO chat?
Socket.io is a Javascript library for web apps that allows real-time communication between clients and servers. It's built on top of the Websockets API (client) and Node.

2. What proof of life are we getting on the backend from the above app?
    If you open your network tab in your developer tools, you should see a few HTTP requests:

    [Proof of life](https://socket.io/assets/images/network-monitor-2e47dbe233100aa290595f8687a9fcba.png)

3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

[Rooms](https://socket.io/docs/v4/rooms)

1. What is a room and how might a room be useful?
    A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients:

2. How do you join a room?

```js
    io.on("connection", socket => {
  socket.join("some room");
});
```

3. how do you leave a room?
    To leave a channel you call leave in the same fashion as join.

[Namespaces](https://socket.io/docs/v4/namespaces/)

1. What is a Namespace and what does it allow you to do?
    A namespace is a declarative region that provides a scope to the identifiers (the names of types, functions, variables, etc) inside it. Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries.

2. Each namespace potentially has its own what? (hint: 3 things)

3. Discuss a possible use case for separate namespaces

Bookmark and Review
-------------------

[Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)

*

## Things I want to know more about
