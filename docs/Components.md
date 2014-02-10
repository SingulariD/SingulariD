# Backend

* Scanning file system
* Reading/Writing/Parsing of projects
* Reading/Writing code files
* Handle packages (dub)
* Compiling code
* Running and Debugging
* Parse files and provide symbol information

# Middleware

* HTTP server to serve static files
* Websocket server for communication between front- and backend
* Communication via data objects (known types in backend, JSON objects in frontend)

# Frontend

* IDE-grade code editor (maybe based on [ACE](http://ace.c9.io/))
* Control backend debugger
* Configure project
* Manage packets
* Provide debug/run output
* [Optional] provide a commandline (would instantly provide git, dub etc.)

# Optional client application

* Simple Web(kit) renderer as client 
* Disables all default web actions (selecting html elements etc.)
* Native feeling
