to run the code 
1) first compile it
2) run the server code ./a.out 127.0.0.1 8080 s  (ip port mode).
3) run the client code ./a.out 127.0.0.1 8080 c  (ip of server port number of server and mode of running)
4) run 2 clients using step 3
5) Type the name of client when it asks "What is your name?" for both the clients say ALice(client1) and Bob(client2)
6) to communicate between the clients type in client1(Alice) terminal Bob hey. <client2 name> <message>. Dont write MESG in front of it. it is hard coded.
7) Type EXIT to exit both the clients. All the client connected to the server will EXIT.

client1_client2.txt generated will contain the chats between Alice and Bob.
You dont need to create client1_client2.txt manually. code will create it.






