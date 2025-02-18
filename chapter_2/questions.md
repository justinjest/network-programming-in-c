# Questions

1. What is a socket?
A socket is a connection between a server and a client that enables data to be sent between the two. 
2. What is a connectionless protocol? What is a connection-oriented protocol?
Connectionless protocols send data without providing information about how much or what data is being sent. A connection oriented protocol provides context for what data is being sent
3. Is UDP connectionless or connection-oriented?
Connectionless
4. Is TCP connectionless or connection-oriented?
Connection-oriented
5. What types of apps geerally benefit from UDP?
Real time applications and streaming applications
6. What types of apps geerally benefit from TCP?
HTTP, SMTP, SSH
7. Does TCP guarantee that data will be transmitted successfully?
No, however it will confirm that the data will all be transmitted or none of it will be
8. What are some of the main differences between Berkeley sockets and Winsock sockets?
In WINSOCK sockets can be anything, while Berkeley requires them to be an integer
9. What does the bind() function do?
Bind connections the server to a port
10. What does the accept() function do?
Accept connects a client to a port
11. In a TCP connection does the client or server send application data first?
Client connects and then requests data
