- VPC is composed of subnetworks, or subnets, and each subnet must be configured with a private IP CIDR address

- CIDR stands for Classless Inter-domain Routing.
- The CIDR range will determine what internal IP addresses will be used by virtual machines in the subnet. 

- Internal IP addresses are only used for communication within the VPC and cannot be routed to the internet.

# Public vs. Internal IP addresses
- Public, or external IP addresses can be ephemeral or reserved.
    - They are assigned from a pool of IP addresses associated with the region.
    - If you allocate a reserved IP address but don't attach it to a virtual machine, you will be billed for the IP address.
- Private, or internal IP addresses, are allocated to VMs by a Dynamic Host Configuration Protocol (DHCP) service
    - The lease for the IPs is renewed every 24 hours.
    - The name of the virtual machine is the hostname, and the hostname will be associated with the internal IP address through a network-scoped DNS service.
