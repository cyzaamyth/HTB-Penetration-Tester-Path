**Bash (Bourne Again Shell)** - Aside from bash there are also other shells, including but not limited to Zsh, Tcsh, Ksh, Fish shell, etc.
 - Reverse shell- Initiates a connection back to a "listener" on our attack box.
 - Bind shell	- "Binds" to a specific port on the target host and waits for a connection from our attack box.
 - Web shell -	Runs operating system commands via the web browser, typically not interactive or semi-interactive. It can also be used to run single commands (i.e., leveraging a file upload vulnerability and uploading a PHP script to run a single command.

**What is a Port?**

A port can be thought of as a window or door on a house (the house being a remote system), if a window or door is left open or not locked correctly, we can often gain unauthorized access to a home.

**There are two categories of ports, Transmission Control Protocol (TCP), and User Datagram Protocol (UDP).**

**TCP** is connection-oriented, meaning that a connection between a client and a server must be established before data can be sent. The server must be in a listening state awaiting connection requests from clients.

**UDP** utilizes a connectionless communication model. There is no "handshake" and therefore introduces a certain amount of unreliability since there is no guarantee of data delivery.

https://web.archive.org/web/20240315102711/https://packetlife.net/media/library/23/common-ports.pdf

https://nullsec.us/top-1-000-tcp-and-udp-ports-nmap-default/

**What is a Web Server?**

A web server is an application that runs on the back-end server, which handles all of the HTTP traffic from the client-side browser, routes it to the requests destination pages, and finally responds to the client-side browser. Web servers usually run on TCP ports 80 or 443, and are responsible for connecting end-users to various parts of the web application, in addition to handling their various responses

**Secure Shell (SSH)** is a network protocol that runs on port 22 by default and provides users such as system administrators a secure way to access a computer remotely. SSH can be configured with password authentication or passwordless using public-key authentication using an SSH public/private key pair. SSH can be used to remotely access systems on the same network, over the internet, facilitate connections to resources in other networks using port forwarding/proxying, and upload/download files to and from remote systems.
