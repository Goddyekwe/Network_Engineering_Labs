# Personal Notes

## What I Learned

This project helped me understand that selecting a network cable is not
simply about connecting two devices.

The type of device, interface, Auto-MDI/MDIX capability, and physical
distance can all influence the appropriate connection medium.

### 1. Device Type Matters

I learned the traditional distinction between:

- Same device type → Crossover
- Different device types → Straight-through

Examples:

Router → Router = Crossover

Switch → Switch = Crossover

Router → Switch = Straight-through

Switch → PC = Straight-through

### 2. Distance Matters

The project also demonstrated that physical distance affects the choice
of transmission medium.

The 3 km R1–R3 connection uses single-mode fiber, while the 250 m R3–R4
connection uses multimode fiber.

### 3. Fiber Types

Single-mode fiber is designed for longer-distance transmission.

Multimode fiber is generally used for shorter-distance applications.

### 4. Packet Tracer

Packet Tracer allows me to practice physical network design and
connectivity without requiring physical Cisco hardware.

## Questions to Investigate

- What are the maximum practical distances for different Ethernet standards?
- What are the differences between Cat5e, Cat6 and Cat6A?
- How do SFP modules determine the type of fiber that can be used?
- What is the difference between LC, SC and ST fiber connectors?
- How does Auto-MDI/MDIX work?
- What happens when the wrong cable type is selected?

## Next Steps

- Practice identifying Cisco interfaces.
- Study Ethernet standards.
- Learn more about SFP and SFP+ modules.
- Build a larger topology using VLANs and trunk links.
- Begin documenting configurations in addition to physical connectivity.
