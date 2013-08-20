# Node Chat Example

Chat example to showcase how to use `socket.io` with a static `express` server.

## Setup

    $ npm install

## Running the server

    $ node server.js
       info  - socket.io started
    Chat server listening at 0.0.0.0:3000

Once the server is running, open `http://localhost:3000` in your browser. As you enter your name, watch the Users list
(on the left) update. Once you press Enter or Send, the message is shared with all connected clients.
