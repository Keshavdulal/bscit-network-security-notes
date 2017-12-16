footer: *NS-U4-WIRELESS-NW-SEC*
slidenumbers: true
autoscale: true
build-lists: true

# BSCIT
# Network Security
# Unit 5
# Wireless Network Security

---
## Unit 5
#[fit] Wireless Network Security

<!-- --- -->
<!-- ![fit](./images/17/17-key-points.png) -->

<!-- List of Images first -->
<!-- ![fit](../../commonSlideImages/) -->
<!-- ![fit](./images/17/17-key-points.png) -->
<!-- ![fit](./images/17/17.1.table.png) -->
<!-- ![fit](./images/17/17.1.png) -->
<!-- ![fit](./images/17/17.2.png) -->
<!-- ![fit](./images/17/17.2.table.png) -->
<!-- ![fit](./images/17/17.3.png) -->
<!-- ![fit](./images/17/17.3.table.png) -->
<!-- ![fit](./images/17/17.4.a.png) -->
<!-- ![fit](./images/17/17.4.b.png) -->
<!-- ![fit](./images/17/17.4.png) -->
<!-- ![fit](./images/17/17.5.png) -->
<!-- ![fit](./images/17/17.6.png) -->
<!-- ![fit](./images/17/17.7.png) -->
<!-- ![fit](./images/17/17.8.a.png) -->
<!-- ![fit](./images/17/17.8.b.png) -->
<!-- ![fit](./images/17/17.9.png) -->
<!-- ![fit](./images/17/17.10.png) -->
<!-- ![fit](./images/17/17.11.png) -->
<!-- ![fit](./images/17/17.12.png) -->
<!-- ![fit](./images/17/17.13.png) -->
<!-- ![fit](./images/17/17.14.png) -->
<!-- ![fit](./images/17/17.15.png) -->
<!-- ![fit](./images/17/17.16.png) -->
<!-- ![fit](./images/17/17.17.png) -->
<!-- ![fit](./images/17/17.18.png) -->
<!-- ![fit](./images/17/17.19.png) -->
<!-- ![fit](./images/17/17.20.png) -->
<!-- ![fit](./images/17/17.21.png) -->
<!-- ![fit](./images/17/17.22.png) -->

---
# 5 Topics
1. IEEE 802.11 Wireless LAN Overview
2. IEEE 802.11i Wireless LAN Security
3. Wireless Application Protocol Overview
4. Wireless Transport Layer Security
5. WAP End-to-End Security

---
# 1. IEEE 802.11 Wireless LAN Overview

---
# IEEE 802.11 Wireless LAN Overview (4)
1. The Wi-Fi Alliance
2. IEEE 802 Protocol Architecture
3. IEEE 802.11 Network Components and Architectural Model
4. IEEE 802.11 Service

---
# 1. The Wi-Fi Alliance
- IEEE - Institute of Electrical and Electronics Engineers
- IEEE 802 - Committee - LAN
- IEEE 802.11 - Committee - WLAN
	- Develop a protocols and transmission specifications for WLANs
- WECA - Wireless Ethernet Compatibility Alliance
	- Industry Consortium

---
![fit](./images/17/802.11.jpg)

---
# 2. IEEE 802 Protocol Architecture

<!-- ---
## Terminologies
![inline](./images/17/17.1.table.png) -->

---
![fit](./images/17/17.1.png)

---
# 2. IEEE 802 Protocol Architecture
1. Logical Link Control
2. Media Access Control
3. Physical Layer

---
# 1. Logical Link Control
- Flow Control
- Error Control

---
# 2. Media Access Control
- Assemble data into frame (MSDU -> MPDU)
- Addressing
- Error detection
- Medium access
- Specific IEEE 802.11 functions
	- Reliable data delivery
	- Wireless access control protocols

MPDU - MAC Protocol Data Unit
MSDU - MAC Service Data Unit

---
# 3.Physical Layer
- General IEEE 802 functions
	- Encoding/decoding of signals
	- Bit transmission/reception
	- Specification of Transmission medium
- Specific IEEE 802.11 functions
	- Frequency band definition
	- Wireless signal encoding

---
# MPDU Frame Format
- Header
	- MAC Control
	- Dest. MAC Address
	- Source MAC Address
- Body
	- MSCU (Mac Service Data Unit)
- Trailer
	- CRC (Cyclic Redundancy Check) /FCS(Frame Check Sequence) Field

---
# MPDU Frame Format
![inline fit](./images/17/17.2.png)

---
# 3. IEEE 802.11 Network Components and Architectural Model

---
# 3. IEEE 802.11 Network Components and Architectural Model
- BSS - Basic Service Set
- DS - Distribution System
- AP - Access Point
- IBSS - Independent BSS
- ESS - Extended Service Set

---
![fit](./images/17/17.3.png)

---
**Basic service set (BSS)**
The smallest building block of a wireless LAN, which consists of wireless stations executing the same MAC protocol and competing for access to the same shared wireless medium.

A BSS may be isolated, or it may connect to a backbone **Distribution system (DS)** through an access point (AP).The AP functions as a bridge and a relay point.

When all the stations in the BSS are mobile stations that communicate directly with one another (not using an AP), the BSS is called an independent BSS (IBSS). An IBSS is typically an ad hoc network.

---
# IEEE 802.11 Service

---
# IEEE 802.11 Service
- Services that needs to be provided by the wireless LAN to achieve the functionality equivalent to that which is inherent to wired LAN.

---
![fit](./images/17/17.2.table.png)

---
# Categeorization of Service
- Based on Provider
	- DS - Distribution System
	- SS - Service Station
- Based on the Nature of Service
	- LAN Access
	- MSDU Delivery

---
- Distribution of Messages within a DS
- Association related services
	- 3 Transition types
		- No Transition
		- BSS Transition
		- ESS Transition
	- 3 Services
		- Association
		- Reassociation
		- Disassociation

---
![fit](./images/17/17.3.table.png)

---
![fit](./images/17/17.4.a.png)

---
![fit](./images/17/17.4.b.png)

---
![fit](./images/17/17.4.png)

---
![fit](./images/17/17.5.png)

---
![fit](./images/17/17.6.png)

---
![fit](./images/17/17.7.png)

---
![fit](./images/17/17.8.a.png)

---
![fit](./images/17/17.8.b.png)

---
![fit](./images/17/17.9.png)

---
![fit](./images/17/17.10.png)

---
![fit](./images/17/17.11.png)

---
#[fit] WAP
#[fit] Wireless Application Protocol

---
# History
- Introduced in 1999
- Used widely in early 2000s
- By 2010 use of WAP Declined

---
# WAP Key points
- WAP used WML (wireless markup language)

---
# WAP Protocol Stack
Wireless Application Environment (WAE)
Wireless Session Protocol (WSP)
Wireless Transaction Protocol (WTP)
Wireless Transport Layer Security (WTLS)
Wireless Datagram Protocol (WDP)

<!-- WAP is designed in a layered fashion, so that it can be extensible, flexible, and scalable. As a result, the WAP protocol stack is divided into five layers:

Application Layer

Wireless Application Environment (WAE). This layer is of most interest to content developers because it contains among other things, device specifications, and the content development programming languages, WML, and WMLScript.

Session Layer

Wireless Session Protocol (WSP). Unlike HTTP, WSP has been designed by the WAP Forum to provide fast connection suspension and reconnection.

Transaction Layer

Wireless Transaction Protocol (WTP). The WTP runs on top of a datagram service, such as User Datagram Protocol (UDP) and is part of the standard suite of TCP/IP protocols used to provide a simplified protocol suitable for low bandwidth wireless stations.

Security Layer

Wireless Transport Layer Security (WTLS). WTLS incorporates security features that are based upon the established Transport Layer Security (TLS) protocol standard. It includes data integrity checks, privacy, service denial, and authentication services.

Transport Layer

Wireless Datagram Protocol (WDP). The WDP allows WAP to be bearer-independent by adapting the transport layer of the underlying bearer. The WDP presents a consistent data format to the higher layers of the WAP protocol stack, thereby offering the advantage of bearer independence to application developers.

Each of these layers provides a well-defined interface to the layer above it. This means that the internal workings of any layer are transparent or invisible to the layers above it. The layered architecture allows other applications and services to utilise the features provided by the WAP-stack as well. This makes it possible to use the WAP-stack for services and applications that currently are not specified by WAP. -->

---
![fit](./images/17/17.12.png)

<!-- --- -->
<!-- ![fit](./images/17/17.13.png) -->

---
![fit](./images/17/17.14.png)

<!-- ---
![fit](./images/17/17.15.png)

---
![fit](./images/17/17.16.png)

---
![fit](./images/17/17.17.png)

---
![fit](./images/17/17.18.png) -->

---
![fit](./images/17/17.19.png)

---
![fit](./images/17/17.20.png)

<!-- ---
![fit](./images/17/17.21.png)

---
![fit](./images/17/17.22.png) -->

