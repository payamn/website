---
layout:     project
title:     Client Server Program
date:     2011-08-01
code:
doc:
demo:
best:       true
image_small: /files/projects_files/2011-08-01-Client-Server-Program.png
short: Created a clinet server system

---
In this project we had to use a client and server socket connection, system call, Non-blocking function call and our program should support all Linux commands. Server always listen to special port and each client can connect to server by using this port. When a client connect to this port, server sends him the command list which it can use. Because server must be up all the time, it had to check the command list file; If this file has been changed recently, server will send it to all peers.In this project we were not allowed to use Multi-thread techniques, so it makes us some difficulties by using only Non-blocking function call.
