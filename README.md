# Enterprise_Network_Infrastructure

## 📸 Project screenshots are available in the `screenshots` folder.

## **Project Overview**

This project demonstrates the **design, implementation, configuration, and verification** of a small enterprise network using **Cisco Packet Tracer**. The network was developed using **industry-standard networking concepts** and **CCNA-level best practices** to ensure **secure, scalable, and efficient communication** between multiple departments.

The primary objective was to implement **VLAN-based network segmentation**, **dynamic routing**, **automatic IP address allocation**, and **network security policies** while maintaining reliable connectivity across all network segments.

---

## **Network Architecture**

The network consists of **two interconnected Cisco routers** connected through a **WAN serial link**. Multiple LAN segments are connected through **Cisco switches** and organized using **VLANs** to separate departmental traffic.

Dynamic routing was implemented using **OSPF** to enable automatic route exchange between routers. **DHCP services** were configured to automatically assign IP addresses to client devices, while **Access Control Lists (ACLs)** were used to control and restrict communication between selected networks.

---

## **Technologies Implemented**

- **IPv4 Addressing and Subnetting**
- **VLAN Configuration and Segmentation**
- **DHCP (Dynamic Host Configuration Protocol)**
- **OSPF Dynamic Routing Protocol**
- **Extended Access Control Lists (ACLs)**
- **Network Verification and Testing**
- **Cisco IOS Troubleshooting Techniques**

---

## **Key Features**

### **VLAN Segmentation**

Multiple VLANs were created to logically separate departmental networks and reduce broadcast traffic. Switch ports were assigned to their respective VLANs to ensure proper network isolation and improve security.

### **DHCP Configuration**

DHCP services were configured to automatically provide IP addresses, subnet masks, and default gateways to client devices. This reduced manual configuration efforts and simplified network management.

### **OSPF Dynamic Routing**

**OSPF Process ID 1** was configured to dynamically exchange routing information between routers. Neighbor relationships were established successfully, allowing all networks to learn remote routes automatically.

### **Access Control Lists (ACLs)**

Extended ACLs were implemented to enforce security policies and control traffic flow between selected network segments. Connectivity testing was performed to verify proper ACL operation.

---

## **Verification and Testing**

The network was thoroughly tested to verify successful implementation of all configured services.

Verification activities included:

- **VLAN operation and connectivity testing**
- **DHCP address allocation verification**
- **OSPF neighbor adjacency verification**
- **Routing table verification**
- **ACL functionality testing**
- **End-to-end connectivity testing**

---

## **Cisco IOS Verification Commands**

```bash
show ip interface brief
show vlan brief
show ip route
show ip ospf neighbor
show ip dhcp binding
show access-lists
```

---

## **Learning Outcomes**

This project provided practical experience in **enterprise network design and implementation**. Key concepts reinforced through this project include:

- **Enterprise Network Architecture**
- **IP Addressing and Subnetting**
- **VLAN Design and Implementation**
- **Dynamic Routing using OSPF**
- **DHCP Service Configuration**
- **Network Security using ACLs**
- **Network Verification Techniques**
- **Cisco IOS Troubleshooting Methodologies**

---

## **Conclusion**

The project successfully demonstrates the implementation of a **secure and scalable enterprise network** using **Cisco technologies**. By integrating **VLAN segmentation**, **DHCP services**, **OSPF dynamic routing**, and **ACL-based security controls**, the network provides **reliable communication**, **efficient resource management**, and **enhanced security** while following **industry networking standards and best practices**.
