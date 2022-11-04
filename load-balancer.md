# Load Balancer
load balanacer is used to distribute the traffic amaong multiple targets. target is noting but target group, ip address and another load balancer.

Using a load balancer increases the high availability and scalability and also fault tolerance of the applications.

Load Balancer manage the centralize domain with the help of single DNS to access multiple target.

Load Balancer monitor the instance health check system failure, if some problem in the server in that case traffic diverted to healthy instance.

It is also used to divert the public traffic to private traffic.

## Types of load balancer 
    - Classic Load Balancer
    - Application Load Balancer
    - Network Load Balancer
    - Gateway Load Balancer

## Working Algorithm of Load Balancer
  >___`Round robin form`___ --> sequential request distribution . distribute the traffice one by one among targets.

  >___`Least connection`___ --> first checkout/search the servers whose CPU and Memony utilization is less then distribute the traffic as per less cpu an d memony utilization.

  >___`IP hash`___ --> In that type LB can manage or distribute the traffic on the server with the help of ip address.

  * To create load balancer we required target group Configuring a target group allows you to register targets such as EC2 instances. 