# Chat-Application-with-Encryption-and-Decryption-of-Messages

Select a computer to make it a Server and Place ChatServer.java and ChatServerThread.java on it and execute the commands of ChatServer in same order as given below.
Place ChatClient.java and ChatClientThread.java on other computers and execute the commands of ChatClient in same order as given below.
Now All the Clients will be connected to each other via Server.
Now send any message from any client.
First it will be encrypted at local(same) site and the encrypted message will be passed over to Server.
Server will then again pass the same message to all the clients connected to it.
On receiving the encrypted message,all the clients will decrypt the message and will display the original message sent by previous(first) client.


command to run ChatServer:-
javac ChatServer.java;
java ChatServer [port];


command to run ChatClient:-
javac -cp '.:commons-codec-1.10.jar' ChatClient.java;
java -cp '.:commons-codec-1.10.jar' ChatClient [server ip] [server port];


PS:-All the command containing ['something'] should not be executed directly.To execute,we have to remove [] and directly write 'something' and not ['something'].
PS:-Create as many clients you want to create.
