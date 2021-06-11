[Back to Portfolio](./)

# Simple UDP Client

- **Class: CSCI 332 (Applied Networking)**
- **Grade: B**
- **Language(s): C/C++, PHP, HTML/CSS/JavaScript**
- **Source Code Repository:** [lemonase/SimpleUDPClient](https://github.com/lemonase/SimpleUDPClient)
  (Please [email me](mailto:jmdixon1@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

The goal of this project was to learn about lower level networking concepts and
data structures that many applications use under the hood.

## Running on your machine

### Cloning

Clone this repository

```sh
git clone https://github.com/lemonase/SimpleUDPClient
```

### Server

Compile and run the server

```sh
g++ Server_task1.cpp -o Server_task1.out && ./Server_task1.out
```

Enter the desired port number

### Client

Open another terminal to compile/run the client

```sh
g++ Client_task2.cpp -o Client_task2.out && ./Client_task2.out
```

Enter the server's information (IP, port and filename to send)

## Lessons

Using standard libraries in C/C++, we learned how to:

- Set up sockets for UDP
- Work with file descriptors and file streams
- Create buffers to store arbitrary data
- Send and receive data from sockets

[Back to Portfolio](./)
