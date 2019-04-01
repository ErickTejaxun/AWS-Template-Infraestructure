# AWS infrestructure Template

![Alt text](/images/usac.png?raw=true "Logo de usac")

Security group.
This template is to create a security group to allow to our two public subnet that are in our vpc to connecto to internet to our web server can allow to our clients connect to our server and too allow the ssh conection.

# Security group
Rules
## HTTP allow
Configure the 80 port to allow the Http to our web server.
Source port: 80
IP in allowed:
-0.0.0.0/0 : Any
IP out allowed 
-0.0.0.0/0 : Any source

## HTTPS allow
Configure the 443 port to allow the Http to our web server.
Source port: 443
IP in allowed:
-0.0.0.0/0 : Any
IP out allowed 
-0.0.0.0/0 : Any source

## SSH allow
Configure the 22 port to allow the Http to our web server.
Source port: 22
IP in allowed:
-0.0.0.0/0 : Any
IP out allowed 
-0.0.0.0/0 : Any source
