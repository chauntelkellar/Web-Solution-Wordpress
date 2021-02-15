# Welcome to Web Solution with Wordpress 👋
 
In this project I will prepare storage infrastructure on two Linux servers and implement a basic web solution using wordpress. First I configure storage subsystem for Web and Database servers based on Linux OS. The focus of this part is to gain practical experience of working with disks, partitions and volumes in Linux. Second I install WordPress and connect it to a remote MySQL database server.  This is to exercise skills of deploying Web and DB tiers of a Web solution.

### Three-tier Architecture 
Generally web or mobile solutions are implemented base on what is called the Three-tier architecture 

Three-tier Architecture is a client-server software architecture pattern that is compreisded of 3 separate layers. 

1. Presentation Layer (PL): This is the user interface such as the client server or browser on your laptop.

2. Business Layer (BL): This is the backend program that implements business logic. Application or Webserver

3. Data Access or Management Layer (DAL): This is the layer for computer data storage and data access. Database Server or File System Server such as FTP server, or NFS Server

#### My Three-tier Setup
1. A Laptop or PC to serve as a client
2. An EC2 Linux Server as a web server for wordpress
3. An EC2 Linux server as a database (DB) server

> [Checkout the project notes](Project-Notes.md)
