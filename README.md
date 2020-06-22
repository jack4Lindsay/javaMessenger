# networking
A server and client program written in Java where you can send messages back and forth.

+ Make sure you can run .jar programs from your command line, there is no GUI set up for these just yet! +

For the server.jar,

Running this in your cmd with "java -jar server.jar" will tell you that
the server socket has been created, and that it is open for connections.
It will stay this way until it receives a connection.

For the client.jar,

Running this with the command "java -jar client.jar" will prompt you with
the number of digits in the IP address you wish to connect to. For example,
the IP address 192.168.0.1 would have 8 digits, 1,9,2,1,6,8,0 and 1. then,
you will be prompted to enter the full IP address, in which case from our
previous example you will input 192.168.0.1. 

As long as the server.jar program is running on the computer that has 
the IP address 192.168.0.1, then they will connect, and the server will 
start the conversation. Pressing enter sends the messages, while sending 
TAB switches the typer and sending ` cancels the conversation \ 
connection altogether.
