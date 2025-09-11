CREATE VPC

Points of consideration:
1) Try to select les ip in teh cidr range. because this is sample project, I choose this for my project : 10.0.0.0/24 (256 ips)
2) Number of AZ2
3) Number of public and private subnet, 1 each in both AZ's
4) NAT gateways, 1 in each AZ(this costs money so remember to delete it) 
5) We dont need a vpc endpoint so you can set it as none

CLICK on create vpc

![alt text](<Screenshot from 2025-09-11 23-18-57.png>)