# Systems-Programming-Course-Projects
Systems Programming assigenments with our solutions.

# Objective
* Learning how to create programs that interact with sophisticated Run-Time Environments (RTE). The key notion of the course is that programs are always created relative to another program - which we call the RTE. RTEs have a regular structure: they provide services that the programs we create exploit. In the course, we focus on 4 generic services: management of memory, management of concurrency, communication and networking, and persistent data management (file organization and database usage with SQL).

* Across these topics, we compare various RTEs: Unix and Windows Operating Systems, the Java Virtual Machine (JVM) and on occasion, Servlet containers and distributed RTEs.

* Gaining experience and exposure to good practices for mid-size programming. The course offers exposure for intensive hands-on programming in pairs. We will learn C++ as a new programming language and systematically compare it to Java. Our perspective is to explain how programming languages provide an abstraction layer above the facilities provided by the intended RTE in which programs are executed. We will focus on systematic acquisition of good programming habits: documentation of code, code metrics verification, design patterns examples, unit testing, test driven development.
* This aspect of the course is not theory driven, but instead, experience driven: we will work on 4 large programming assignments during the semester.

# Assignment 1 - File Terminal
The objective of this assignment is to design an object-oriented system and gain implementation
experience in C++ while using classes, standard data structures and unique C++ properties such
as the “Rule of 5”. will learned how to handle memory in C++ and avoid memory leaks.

# Assignment 2 - ThreadPool: Universty registration system
The goal of following assignment is to practice concurrent programming on Java 8 environment. This assignment
requires a good understanding of Java Threads, Java Synchronization, Lambdas, and Callbacks. in addition this assigenment cover the following topics/tools : Json read&parse, Maven build, Concurrent DataBases, Junit test.

# Assignment 3 - Server & Client: Online movie rental service
* In this assignment we will implement an online movie rental service
server and client. The communication between the server and the client(s) will be
performed using a text based communication protocol, which will support renting, listing
and returning of movies.
* The implementation of the server will be based on the Thread-Per-Client (TPC) and
Reactor servers taught in class. The servers, as seen in class, do not support bi-directional
message passing. Any time the server receives a message from a client it can reply back
to that specific client itself, but what if we want to send messages between clients, or
broadcast an announcment to all clients? The first part of the assignment will be to
replace some of the current interfaces with new interfaces that will allow such a case.
* We will implement the movie rental service over the User service textbased
protocol. The User Service Text-based protocol is the base protocol which will
define the message structure and base command. Given an implementation of the
protocol we can implement many user service applications. The service we will build is a
movie rental service. Since the service requires data to be saved about each user and
available movies for rental, we will implement a simple JSON text database which will be
read when the server starts and updated each time a change is made.
*we will also implement a simple terminal-like client in C++. To simplify matters,
commands will be written by keyboard and sent “as is” to the server.
