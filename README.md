# aws-project-vpc
A project in AWS cloud where we have a VPC with a private and public subnet setup

Here is what we are going to do
1) create a VPC that you can use for servers in a production environment. 
2) To improve resiliency, you deploy the servers in two Availability Zones, by using an Auto Scaling group and an Application Load Balancer. 
3) For additional security, you deploy the servers in private subnets. 
4) The servers receive requests through the load balancer. 
5) The servers can connect to the internet by using a NAT gateway. 
6) To improve resiliency, you deploy the NAT gateway in both Availability Zones.
