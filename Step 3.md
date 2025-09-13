EC2 server and bastions host

1) After the Auto scaling groups are created, you should see the EC2 servers coming up
2) You will notice that they do not have a public ip address as we wanted then in the private subnet
3) You cannot login directly to the ec2 instance in the private subnet, so now we create a bastion host
    3.1) Create an EC2 instance called bastion host.
    3.2) Make sure its in the same VPC and in the PUBLIC subnet
4) Login to the bastion host and from the bastion host login to the private ec2 instance

The bastion host is a good way to connect to private ec2 instance.
And to ssh into the bastion you need to have a key-value pair. That is how security is controlled.