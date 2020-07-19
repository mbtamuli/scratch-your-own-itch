# Message Broker - Work In Progress

This will be a toy implementation of a Message Broker. Build a asynchronous messaging system with a message broker (server) and client which can interact with this server based on a predetermined protocol.

## Server

* The server can connect with multiple clients simultaneously. 
* Server will send list of `queue`s to client on connection.
* Server will receive input from client and subscribe them to a `queue`.
* Server will recieve input from a subscribed client to convert it according to the rules in the `queue`.


## Client
* Client will present user with a list of `queue`s recieved from the server.
* Based on user choice, will request the server to subscribe to a `queue`.
* After being subscribed to a `queue`, ask user for input.
* 
