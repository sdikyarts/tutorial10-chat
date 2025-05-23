## Experiment 2.1
![Server](img/server_base.png)
![Three Clients](img/clients_base.png)

We can see in the first image that we have successfully started our chat server using Rust, which is now listening on port 2000 and actively accepting new connections from clients on the local machine (127.0.0.1) at different port numbers. Each time a client connects, the server logs the connection and, as clients send messages like "I am client 01", "I am client 02", and "I am client 03", the server receives and broadcasts these messages to all connected clients. In the second image, we observe three separate terminal windows, each running a client instance. Each client receives a welcome message from the server and then displays the broadcasted messages from all clients, including their own, showing that the chat system is working as intended. This demonstrates that our server is correctly handling multiple simultaneous client connections, receiving their messages, and broadcasting them to all participants in real time, allowing us to have a group chat experience.

