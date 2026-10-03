# ACTIVITIES

1. I configured the switch interfaces connected to PCs as access ports in the correct VLAN.

2. Configured the connection between SW1 and SW2 as a trunk, allowing only the necessary VLANs.
    Also configure an unused VLAN (vlan 101) as the native VLAN.
    Making sure that all necessary VLANs exist on each switch

3. I configured the connection between SW2 and R1 using 'router on a stick'.
     Assigned the last usable address of each subnet to R1's subinterfaces.

4. Tested connectivity by pinging between PCs.  All PCs reached each other.
