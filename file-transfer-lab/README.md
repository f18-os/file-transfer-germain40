# Lab
`fileClient` is a TCP Client.

`fileServer` is a TCP Server which also uses fork() to handle multiple simultaneous clients. 

`framedSock` holds common code for the server and client to send and receive bytes of data.

`msg.txt` is just a text file to test if the client can send to server
