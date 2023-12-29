#   A simple event-loop echo client-server model.

An event-loop-based echo server implemented in C, showcasing the utilization of I/O multiplexing through the select() system call and non-blocking I/O via fcntl() in a Linux environment. The server efficiently handles concurrent connections by utilizing an event-driven architecture, allowing it to process multiple clients concurrently. This architecture enables the server to efficiently echo back incoming data from connected clients while ensuring responsiveness and preventing potential denial-of-service scenarios through non-blocking I/O operations
