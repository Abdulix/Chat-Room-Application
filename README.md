
# Chat Room Application

It's a simple chat room where client and server side are designed in such a way that many clients can connect to the server having the same port 
.The server is going to be a concurrent server, which means it can handle multiple clients
using threads. Each client is handled by a separate thread, which helps the server to
handle multiple clients. There will be mainly a server file for keeping all the records
and user files. Every user that joins the chatroom will be shown on the server. Sockets are used in it to connect the user to the server. A socket is bound to a port number so that the TCP layer can
identify the application that which data is destined to be sent. An endpoint includes a
combination of an IP address and a port number. The server will keep a record of all
the chat data and login details of the users. 



### Instructions

- Fork this repository
- Clone your forked repository
- Add your scripts
- Commit and push
- Create a pull request
- Star this repository
- Wait for pull request to merge
- Celebrate your first step into the open source world and contribute more


### Deployment

To run this project, you will to need execute step by step instructions on Ubuntu.

So, First we need to compile Makefile of the project by using following command:

```bash
make Makefile all
```

Then after compiling Makefile, run the following command on the same terminal:

```bash
./server #port_number   
```

You can choose any four digit port number.
That terminal will be your server.

Then open multiple terminals and run the following command:

```bash
`./client #server_port_number`
```

Choose the same server port for client side.

Now, you can enjoy chatting with your many friends or clients.
It will show text messages with names, date and time. For better user experience it has different colors for everyone.


