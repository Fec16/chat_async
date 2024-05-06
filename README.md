## Reflection

**2.1. Original code**

Server Side <br>
![Server 1](assets/images/server1.jpg) 

Client Side 1 <br>
![Client 1](assets/images/client1.jpg) 

Client Side 2 <br>
![Client 2](assets/images/client2.jpg) 

Client Side 3 <br>
![Client 3](assets/images/client3.jpg) 

Once the server is up and running, and each client is connected. From the picture above, it is shown that every client and the server receive chat broadcasts from each client. 

Whenever a client types a message in the command line, that string is sent to the server, which then continues to broadcast it to all connected clients.


**2.2. Modifying port**

![Server Side with same port](assets/images/server_same_port.jpg) 
![Client Side with same port](assets/images/client_same_port.jpg) 

When the client and server share the same port (8080). The application will run smoothly like before, as seen in the image. <br>

![Server Side with different port](assets/images/server_different_port.jpg) 
![Client Side with different port](assets/images/client_different_port.jpg) 

However if we only change one port, let's say the server port becomes 8080 while the client port remains 2000. An error then will occur on the client side because according to the client, the port doesn't have a connection and the program will crash when run, as shown in the image. <br>

**2.3. Small Changes**