# ACTIVITIES
## DYNAMIC TRUNKING PROTOCOL (DTP)
- I configured the switchports connecting the 3 switches as 'trunk ports'.
- Disabled DTP on the ports.
- Then observed the administrative and operational mode of each interface.

  ## VLAN TRUNKING PROTOCOL (VTP)
- I configured SW1 in VTP domain CCNA. then,
    Created VLANs 10, 20, and 30 on SW1.
    Observed that SW2 and SW3 added VLANs 10, 20, and 30 with it's default state.
- I configured SW2 in VTP transparent mode.
    Added VLAN40 to SW2.
    due to this configuration I observeded that VLAN40 was not added to the VLAN database of SW1/SW3.

-  Next, I configured SW3 in VTP client mode.
    Tried to configure a new VLAN on SW3.  Which was not possible as it was now in client mode.

-  Finally, I configured all switchports connected to hosts in the correct VLAN.
    Manually configured them as access ports.
