# TCP_Sync

The zip file "TCP_Sync.zip" has the project and source files of a C# application that opens a TCP communication between a client and a server hosts. 

The objective of this project is to provide a "template" for a simple and synchronous TCP connection which allows: an understanding of the steps in a TCP connection and test its data transfer capacities under .NET Framework. The code also has a lot of tips for better understanding and modifying.

To use the application it is necessary to open two instances. One instance must run as client while the other must be running at the same time as server. Both instances may be running in the same Operating System (by running its executable file twice) or in different ones.

To use the application:

*) open an instace of the application and, inside the console, type "1" to set this first instance as a TCP Server;
*) there is no need to choose a name (or and alias) for this server if you want to allow TCP connections from any one of its Network Interface;
*) then, choose any (available) port you want for this connection or just press "ENTER" to let the application use its default value;
*) take a note of the IP address and the PORT defined in the Server, because you need to supply these information in the client instance;
*) open a second instace of the application (in the same host where the first instance is running or in another host connected in the same physical network/switch and configured within the same subnet address);
*) inside the console of the second instance, type "2" to set this instance as a TCP Client;
*) type the Server IP address showed in the console of the first instance;
*) type the Server Port showed in the console of the first instance;
*) let both instance exchange data (client initiates sending random data to server, then server sends back the same data that it received from client);
*) statistics and exceptions will be shown in the console of both instances.

This project was written for .NET Framework, Version=v4.6.1 .

Vinicius Calil 2018/11/14.

