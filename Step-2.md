Create Auto Scaling group

1) Goto EC2, find aut scaling group
2) Click on create auto scaling group, in there find create launch template
    2.1) The launch template is basically informing what kind of EC2 instance you want spun up
    2.2) Its very similar to the EC2 creation template
    2.3) Select you choice of OS and the other basic info. DONT FORGET to select your VPC which you created earlier
        a) Make sure that in the subnet section you are selecting only the PRIVATE subnet
    2.4) Select the correct key vlaue pair
    2.5) Create a new security group
        a) Allow SSH connection on port 22
        b) Allow tcp connection on port 8000
3) After the launch template is created go back tot he auto scaling group creation page and find the template you created in the dropdown
4) Proceed with the options