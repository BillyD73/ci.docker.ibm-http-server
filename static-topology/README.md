# Creating a static topology of Liberty profile servers under Docker

It is possible to create a static topology consisting of WebSphere
Application Server Liberty Profile servers running within Docker
containers with an external web server load balancing across them. A
[script](gen-plugin-cfg) is provided that assists in obtaining the web
server plug-in configuration for a Liberty profile server running
under Docker.

The script testMerge.sh can be used to test all of the static topology scripts.
It required no arguments so just clone the repository locally and 
run the script.