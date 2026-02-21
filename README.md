# Cisco-packet-tracer-Networking-Final-Lab-Project

# Network Infrastructure Implementation using VLAN, VTP, Inter-VLAN Routing & Dynamic Routing (RIP)

## Project Overview

In this project, I designed and implemented a network infrastructure using **VLAN**, **VTP**, **Inter-VLAN Routing**, **Dynamic Routing (RIP)**, along with **basic router and switch configurations**.
The goal of this project is to create a **secure, scalable, and efficiently managed network** with minimal administrative overhead.

## Technologies & Concepts Used

* VLAN (Virtual Local Area Network)
* VTP (VLAN Trunking Protocol)
* Inter-VLAN Routing
* Dynamic Routing (RIP)
* Basic Router Configuration
* Switch Configuration
* Network Connectivity Testing (Ping)

## Dynamic Routing (RIP)

Dynamic routing allows routers to automatically learn and update routing paths using routing protocols.

* The routing process is carried out through **routing protocols**
* Routers automatically decide how to **send and receive packets**
* Administrator involvement is **almost zero** after configuration
* Dynamic routing always considers **directly connected networks** of the router

### Why RIP?

* RIP is suitable for **small networks**
* Easy to configure and understand
* Supports **multi-vendor routers**
* Automatically updates routing tables when network changes occur

## 2️ VLAN (Virtual Local Area Network)

VLANs are used to logically divide a network into multiple broadcast domains.

* VLANs help **minimize internal attacks and unauthorized access**
* VLAN configuration is done **only on switches**
* By default, **VLAN 1** is enabled
* In this project, I created:

  * **VLAN 2**
  * **VLAN 3**
* Each VLAN is assigned a different network segment

###  Benefits of VLAN

* Improved security
* Reduced broadcast traffic
* Better network organization

  
## 3️⃣ VTP (VLAN Trunking Protocol)

VTP is used to distribute VLAN information automatically across switches.

* VTP provides **VLAN information** to all switches in the same domain
* It does **not** share interface-to-VLAN mapping details
* Reduces manual VLAN configuration effort

### VTP Modes Used

* **Server Mode**

  * VLANs are created manually
  * VLAN information is distributed to clients
* **Client Mode**

  * Automatically receives VLAN information from the server
  * VLAN creation is not allowed

---

## Inter-VLAN configaration 

Inter-VLAN routing enables communication between different VLANs.

* Used to allow **VLAN 2 and VLAN 3** to communicate
* Implemented using router configuration
* Ensures controlled and secure communication between VLANs

---

## Router & Switch Configuration

* Basic router configuration for:

  * IP addressing
  * Dynamic routing (RIP)
  * Inter-VLAN routing
* Switch configuration includes:

  * VLAN creation
  * Access and trunk ports
  * VTP server and client setup

---

## Network Testing

* Verified connectivity by **pinging**

  * Router to router
  * PC to PC
  * PC to router
* Successful communication confirms correct VLAN, routing, and switching configuration

##  Project Outcome

* Secure and segmented network using VLANs
* Centralized VLAN management using VTP
* Automatic route learning using RIP
* Successful inter-VLAN communication
* Reduced administrative workload
* Suitable for small to medium-sized enterprise networks

---

##  Tools Used

* Cisco Packet Tracer
