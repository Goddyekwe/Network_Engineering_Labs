# Interfaces and Cables

## Overview

This Cisco Packet Tracer project focuses on identifying and selecting the
appropriate network interfaces and cable types for connecting different
network devices.

The topology contains routers, switches, PCs, and a server connected using
different physical media. The project demonstrates the selection of
appropriate copper and fiber-optic cables based on the type of devices,
connection, and physical distance.

## Objectives

- Identify appropriate cable types for different network connections.
- Understand the difference between straight-through and crossover Ethernet cables.
- Understand when fiber-optic connections are appropriate.
- Differentiate between single-mode and multimode fiber.
- Connect routers, switches, PCs, and servers using appropriate physical media.
- Consider physical distance when selecting network cable types.
- Practice identifying the appropriate interfaces on Cisco network devices.
- Verify that all physical connections are correctly established in Cisco Packet Tracer.

---

## Topology

![Network Topology](topology.png)

The topology consists of two interconnected network sections connected
through multiple routers.

### Devices

- 4 Routers
- 8 Switches
- 3 PCs
- 1 Server

### Network Devices

| Device | Type |
|---|---|
| R1 | Router |
| R2 | Router |
| R3 | Router |
| R4 | Router |
| SW1–SW8 | Switches |
| PC1–PC3 | PCs |
| SRV1 | Server |

---

## Physical Connections

The project contains the following connections:

### Router-to-Router

| Connection | Distance | Cable/Media |
|---|---:|---|
| R1–R2 | 50 m | Copper Crossover |
| R1–R3 | 3 km | Single-Mode Fiber |
| R3–R4 | 250 m | Multimode Fiber |

### Router-to-Switch

| Connection | Cable/Media |
|---|---|
| R2–SW1 | Copper Straight-Through |
| R2–SW2 | Copper Straight-Through |
| R4–SW5 | Copper Straight-Through |
| R4–SW6 | Copper Straight-Through |

### Switch-to-Switch

| Connection | Cable/Media |
|---|---|
| SW1–SW2 | Copper Crossover |
| SW1–SW3 | Copper Crossover |
| SW2–SW4 | Copper Crossover |
| SW5–SW6 | Copper Crossover |
| SW5–SW7 | Copper Crossover |
| SW6–SW8 | Copper Crossover |

### End Device Connections

| Connection | Cable/Media |
|---|---|
| SW3–PC1 | Copper Straight-Through |
| SW4–PC2 | Copper Straight-Through |
| SW7–PC3 | Copper Straight-Through |
| SW8–SRV1 | Copper Straight-Through |

---

## Cable Selection Principles

### Copper Straight-Through

Straight-through Ethernet cables are traditionally used to connect
different types of Ethernet devices.

Examples in this project include:

- Router → Switch
- Switch → PC
- Switch → Server

Examples:

```text
R2 ─── SW1
R2 ─── SW2
SW3 ── PC1
SW4 ── PC2
SW7 ── PC3
SW8 ── SRV1
