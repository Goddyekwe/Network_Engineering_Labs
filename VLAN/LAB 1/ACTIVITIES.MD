
# ACTIVITIES

1. I statically assigned the correct IP address/subnet mask on each PC, 
    then set the gateway address as the LAST USABLE address of the subnet.

2. Made three connections between R1 and SW1 and Configured one interface on R1 for each VLAN.
    I also made sure the IP addresses are the gateway address that I configured on the PCs.

3. I configured SW1's interfaces in the proper VLANs then named the VLANs (Engeering, HR, Sales)


## CONFIRM:

Ping between the PCs to check connectivity.
    Send a broadcast ping from a PC (ping the subnet broadcast address),
     and see which PCs devices receive the broadcast
      (use Packet Tracer's 'Simulation Mode' for visuals)

## Note

ENGINEERING:
Broadcast Address- 255.255.255.63

HR:
Broadcast Address- 255.255.255.127

SALES:
Broadcast Address- 255.255.255.191

click on the end-devices to see configured details.
