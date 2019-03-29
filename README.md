# AWS infrestructure Template

![Alt text](images/usac.PNG?raw=true "Logo de usac")





In this repository we have a template to create a IT infrastructure in the amazon cloud. 
  - Network infraestructure
  - Security infraestructure 
  - Aplication infraestructure

# Network
  - VPC
  - Parameters
  - Output
  - Security Groups
  - Security Groups ouputs

## VPC
Amazon Virtual Private Cloud (Amazon VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. We have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways. 
AWS leave us use use both IPv4 and IPv6 in your VPC for secure and easy access to resources and applications.


## VPC 
To this template we use a the next Parameters   

- CIDR Block: IP range in CIDR notation (10.10.0.0/16) : with this we can to take many subnets in our virutal private cloud. 

## Outputs
> 1 Private subnets in 1 availability zone.
> 1 Public subnets in 1 availability zone.
> 1 Internet gateway and its attachment.
> 1 Nat gateways and its attachment.
> Route tables and associations.
> 1 Elastic IPs for the NAT gateway.
> Necessary access control list for each subnet.

![Alt text](images/template.PNG?raw=true "VPC template")

# Security Group
The security groups is a mechanis that AWS give us to define the rules and politics about how we managements the access and output of our cloud. 
AWS security groups and cloud security. AWS security groups (SGs) are associated with EC2 instances and provide security at the protocol and port access level. Each security group – working much the same way as a firewall – contains a set of rules that filter traffic coming into and out of an EC2 instance.