# Tornado-websockets

http://www.tornadoweb.org/en/stable/websocket.html

Tornado is an asynchronous network library and specializes in dealing with event driven networking. Since it can naturally hold tens of thousands of open connections concurrently, a server can take advantage of this and handle a lot of WebSocket connections within a single node. WebSocket is a protocol that provides full-duplex communication channels over a single TCP connection. As it is an open socket, this technique makes a web connection stateful and facilitates real-time data transfer to and from the server. The server, keeping the states of the clients, makes it easy to implement real-time chat applications or web games based on WebSockets.

WebSockets are designed to be implemented in web browsers and servers, and is currently supported in all of the major web browsers. A connection is opened once and messages can travel back and forth multiple times before the connection is closed.
