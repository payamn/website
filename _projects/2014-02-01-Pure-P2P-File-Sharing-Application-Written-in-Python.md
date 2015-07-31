---
layout:     project
title:     Pure P2P File Sharing Application Written in Python 
date:       Spring 2014
code:  
doc:        
demo:
best:       true
---
In this application each peer can add other peers IP or search the Network to find peers, and when a peer finds another one, they will send their peer list to each other. Each peer can ask for a file using, file name or file hash. In this application file hash is required since peer can get a file concurrently from more than one person, and peers can resume the file they are downloading recently.