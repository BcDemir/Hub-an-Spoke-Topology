# Project \#5

In this project I implemented Azure Hub and Spoke topology for network
traffic

![Alt text](/sc/Project.png "a title")

Step 1 Created virtual networks and subnets and, their NSGs.

Step 2 Created peering between vnet1 to vnet2 and vnet1 to vnet3. 2
virtual machines are created in subnet0 and subnet1 under vnet1

Step 3 Created load balancer and VMs added to backendpool. Turned off
VMs public ips therefore they can only be accessed through load balancer.
Opened 3389 port through load balancer. RDP connection is working
through load balancer to VM0 and VM1. Another 2 VMs created in
az104-06-rg4 and az104-06-rg5. Application gateaway initiated and vm2 and
vm3 are added to its backend pool
