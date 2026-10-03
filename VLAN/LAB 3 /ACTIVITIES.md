# Activities 

1. I replaced the ROAS configuration on R1-SW2 with a point-to-point Layer 3 connection.
    Using the IP addresses given in the network diagram,  I configured a default route on SW2, with R1's G0/0 interface as the next hop.

2. I configured SVIs on SW2, one for each VLAN.
     Assigned the last usable IP address of each subnet to the appropriate SVI.

3. Then, tested inter-VLAN connectivity by pinging between VLANs.

4. Also, tested connectivity to the Internet by pinging 1.1.1.1
    (Note; Routes have already been configured on R1 and the Internet router)
