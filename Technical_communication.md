# Technical Paper on OSI layer
## Introduction
The OSI (Open Systems Interconnection) model is a conceptual networking framework developed by ISO to standardize communication between different computer systems. It divides the communication process into seven independent layers, each with specific responsibilities. These layers help design, troubleshoot, and understand network communication in a clear and modular manner.
# The 7 Layers of OSI Model
## 1. Physical Layer
### 
* Handles the transmission of raw bits over a physical medium.

  *  Bit rate control

   * Physical topology

**Devices/Protocols:**

Ethernet cables, Hubs, Repeaters, RJ45

## 2. Data Link Layer

* Error detection & correction

* Flow control

* LLC (Logical Link Control)

* MAC (Media Access Control)

**Devices/Protocols:**

Switches, Bridges, ARP, PPP

## 3. Network Layer

* Responsible for routing packets across networks.

* Logical addressing (IP address)

* Packet fragmentation

**Devices/Protocols:**

Routers, IP, ICMP, OSPF, BGP

## 4. Transport Layer
* End-to-end communication, reliability, and error recovery.

* Flow control

* Error control


**Protocols:**

TCP, UDP

## 5. Session Layer

* Manages sessions between two communicating devices.

* Synchronization

* Dialog control

**Examples:**

NetBIOS, RPC

## 6. Presentation Layer

* Translates data between application and network formats.

* Data encryption/decryption

* Serialization
  
**Examples:**

SSL/TLS, JPEG, PNG, MPEG

## 7. Application Layer

* Provides network services directly to end users and applications.

* User interface

* Network services

* Resource sharing

**Protocols/Examples:**

* HTTP, HTTPS, FTP, DNS, SMTP, POP3, DHCP

## Use Cases of OSI Model

* Network troubleshooting (ping, traceroute work at specific layers)

* Designing network architecture

* Security implementations (firewalls operate at layers 3 & 4)

## Resources
 GeeksforGeeks – OSI Model Explained

* https://www.geeksforgeeks.org/layers-of-osi-model/

Tutorialspoint – OSI Layer Basics

* https://www.tutorialspoint.com/data_communication_computer_network/osi_model.htm
