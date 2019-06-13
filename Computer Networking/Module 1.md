Network Applications - 

* Byte Stream Model - 
A write data and the data travels though the connection and B reads it and vice-versa. Both the server can close the connection.
The bytes received by the reciepent are in the same order as sent by the sender.
http - 
Client            -            Server
Command(get)                Sends a response
requests a page     

HTTP is documetn centric so clients request is always a name of file. It is human readable(ASCII) text.
Client Sends a Request
Server reads is , Processes it and writes a response to the connection.

The 4 Layer Internet Model - 
1. Application - 
2. Transport - 
3. Network - Deliver packet end to end
4. Link - Transfer to next link

Packet - Collection of Data
TCP - makes sure the data is recieved at the other end.
IP doesnot ensures.
UDP - No deliver gaurantees.

The Application Layer hands the GET request to the TCP layer, which provides
the service of making sure it is reliably delivered. It does this using the services
of the Network layer, which in turn uses the services of the Link Layer.
