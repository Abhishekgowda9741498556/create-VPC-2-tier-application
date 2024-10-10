# create-VPC-2-tier-application


The VPC has public subnets and private subnets in two availability zones.
Each public subnet contains a NAT gateway and a load balancer node.
The servers run in the private subnets, are launched and terminated by using an auto scaling group, and receive traffic from the load balancer.
The servers can connect to the internet by using the NAT gateway.
