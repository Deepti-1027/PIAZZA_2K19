# PIAZZA_2K19
### Distributed Key-Value Store
Multiple clients will be communicating with a single co-ordinating server in a json message format and send the data through sockets using TCP.
<\br>
Each key will be stored using 2-Phase commit Protocol in two key-value server, the first of them will be selected using consistent hashing, while the second will be placed in the successor of the first one.
there will be atleast two key-value servers (which is also known as slave server) in the system.
