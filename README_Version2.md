# Node.js Real-Time Chat Application

This is a simple, scalable real-time chat application built with Node.js, Express, and Socket.io. It demonstrates the scalability of Node.js by allowing multiple users to connect and chat in real time.

## How it Demonstrates Node.js Scalability

- Uses Node.js's event-driven, non-blocking I/O model to handle many concurrent connections efficiently.
- Real-time message broadcasting is managed via a single-threaded event loop.
- Socket.io enables real-time bi-directional communication between clients and server.

## Setup & Running

1. **Install dependencies:**
    ```
    npm install express socket.io
    ```
2. **Start the server:**
    ```
    node server.js
    ```
3. **Open your browser** and go to `http://localhost:3000`. Open multiple tabs or devices to test concurrent connections.

## Performance Metrics & Scalability Tests

- Test with multiple browser tabs/devices to see all messages update in real time.
- For advanced scalability testing, use tools like Artillery or wrk to simulate many clients.

## Implementation Files

- `server.js` – Node.js server with Express and Socket.io
- `public/index.html` – Client-side chat UI

## License

MIT