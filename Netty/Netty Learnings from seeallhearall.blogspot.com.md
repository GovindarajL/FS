**References**
- http://seeallhearall.blogspot.com/2012/05/netty-tutorial-part-1-introduction-to.html
- http://seeallhearall.blogspot.com/2012/06/netty-tutorial-part-15-on-channel.html

**Important Key points from the above links**

- Socket is the combination of ip address and port number. 
- Channel in Netty represents a connection. Connection between two computers (client and server) always uses a socket. In my words *channel is the connection between netty client socket and netty server socket.*
-  Flow: Our FileStorageClient (r/w data in bytes)<-> netty client socket <-> channel <-> netty server socket <-> filestorageserver
