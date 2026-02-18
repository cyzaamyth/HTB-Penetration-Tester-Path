# HTB-Penetration-Tester-Path
Bash (Bourne Again Shell) - Aside from bash there are also other shells, including but not limited to Zsh, Tcsh, Ksh, Fish shell, etc.
 - Reverse shell- Initiates a connection back to a "listener" on our attack box.
 - Bind shell	- "Binds" to a specific port on the target host and waits for a connection from our attack box.
 - Web shell -	Runs operating system commands via the web browser, typically not interactive or semi-interactive. It can also be used to run single commands (i.e., leveraging a file upload vulnerability and uploading a PHP script to run a single command.

**What is a Port?**

A port can be thought of as a window or door on a house (the house being a remote system), if a window or door is left open or not locked correctly, we can often gain unauthorized access to a home.

**There are two categories of ports, Transmission Control Protocol (TCP), and User Datagram Protocol (UDP).**

**TCP** is connection-oriented, meaning that a connection between a client and a server must be established before data can be sent. The server must be in a listening state awaiting connection requests from clients.

**UDP** utilizes a connectionless communication model. There is no "handshake" and therefore introduces a certain amount of unreliability since there is no guarantee of data delivery.

https://web.archive.org/web/20240315102711/https://packetlife.net/media/library/23/common-ports.pdf
