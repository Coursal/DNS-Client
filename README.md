# DNS-Client
A simple DNS client that sends a hostname to a server and manages its response.

Basically, this simplistic DNS client sends a UDP packet with a hostname given by user and waits for the response from the server for 3 seconds at most. If the server has sent "-1", the hostname doesn't exist.

### Execution
* `java DNS_Client <DNS_server_IP_address (default: 127.0.0.1)> <port_number (default: 8888)>`
* `java DNS_Client`

### Output example
![](examples/example_1.png)

![](examples/example_2.png)


Tied with sister project [DNS-Server](https://github.com/Coursal/DNS-Server).

Tested on NetBeans 8.2.
