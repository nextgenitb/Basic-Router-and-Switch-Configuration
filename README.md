# Basic-Router-and-Switch-Configuration
Description:
This lab guides you through the process of configuring basic network devices—routers, switches, and PCs—within a simple network. The goal is to establish connectivity between two different subnets by assigning IP addresses, configuring router interfaces, and performing connectivity tests using the ping command.

By completing this lab, you will gain practical experience in:

Configuring router interfaces for inter-subnet communication.
Assigning IP addresses and subnet masks to network devices.
Verifying connectivity between devices in different subnets using basic networking commands.
Troubleshooting basic network issues using tools such as ping and show ip interface brief.
This lab serves as an introductory exercise to networking, essential for those preparing for the CCNA 200-301 certification.

Objectives:
Set up a basic network with two subnets.
Configure IP addressing on PCs and the router.
Configure router interfaces for proper routing between subnets.
Perform basic connectivity tests (ping) to ensure network functionality.
Troubleshoot network issues using standard networking commands.
Requirements:
Cisco Packet Tracer or GNS3.
Basic knowledge of networking concepts (IP addressing, routing, subnetting).
Network Topology:
Devices:

1 Router
2 Switches
3 PCs
Connections:

Router connected to two switches, each connected to multiple PCs.
Step-by-Step Instructions:
Set up devices in Cisco Packet Tracer or GNS3:

Add a router, two switches, and three PCs.
Connect the devices using Ethernet cables.
Configure IP addressing on the PCs:

Assign appropriate IP addresses and subnet masks to each PC.
Set the default gateway for each PC to the router's corresponding interface IP.
Configure router interfaces:

Set up IP addresses on router interfaces to match the PC subnets.
Verify connectivity using the ping command to test communication between PCs within the same subnet and across different subnets.

Troubleshoot:

Check configurations if connectivity fails using the show ip interface brief command on the router and ensure devices are properly configured.
Expected Outcome:
By completing the lab, you should be able to:

Successfully configure a router for inter-subnet communication.
Validate that devices in different subnets can ping each other.
Troubleshoot common network configuration issues.
Next Steps:
Once you're comfortable with this basic setup, you can explore more advanced topics such as VLAN configuration, dynamic routing protocols (like RIP or OSPF), and security features such as access control lists (ACLs).
