# 🌐 Project 1 – Small Office Network using Static Routing

## 📖 Project Overview

This project simulates a small office network consisting of two departments: **Accounts** and **Delivery**. Each department is assigned its own /29 subnet and connected through a Cisco router to enable communication between both networks.

The project demonstrates fundamental networking concepts including IPv4 addressing, subnetting, router interface configuration, and end-to-end connectivity verification.

---

## 🎯 Objectives

* Design a small office network using Cisco Packet Tracer.
* Create separate subnets for each department.
* Configure router interfaces for inter-network communication.
* Assign IP addresses to all devices.
* Verify successful communication between departments.

---

## 🖥️ Network Topology

### Department 1 – Accounts

* Network: **192.168.40.0/29**
* Devices:

  * 3 PCs
  * 1 Switch
* Default Gateway:

  * **192.168.40.6**

### Department 2 – Delivery

* Network: **192.168.40.8/29**
* Devices:

  * 3 PCs
  * 1 Switch
* Default Gateway:

  * **192.168.40.14**

---

## 🛠️ Technologies Used

* Cisco Packet Tracer
* IPv4 Addressing
* Subnetting (/29)
* Router Configuration
* Static Network Design
* Basic Network Troubleshooting

---

## 📡 Devices Used

| Device       | Quantity |
| ------------ | -------: |
| Cisco Router |        1 |
| Cisco Switch |        2 |
| PCs          |        5 |
| Printer      |        1 |
---

## 🌍 IP Addressing

### Accounts Department

| Device          | Interface | IP Address      |
| ----------------| --------- | --------------- |
| PC1             | NIC       | 192.168.40.1/29 |
| PC2             | NIC       | 192.168.40.2/29 |
| printer         | NIC       | 192.168.40.3/29 |
| Router G0/0     | G0/0      | 192.168.40.6/29 |

---

### Delivery Department

| Device      | Interface | IP Address       |
| ----------- | --------- | ---------------- |
| PC1         | NIC       | 192.168.40.9/29  |
| PC2         | NIC       | 192.168.40.10/29 |
| PC3         | NIC       | 192.168.40.11/29 |
| Router G0/1 | G0/1      | 192.168.40.14/29 |

---

## ⚙️ Configuration Summary

* Configured router interfaces with appropriate gateway addresses.
* Assigned static IPv4 addresses to all PCs.
* Connected each department through dedicated access switches.
* Configured default gateways on all end devices.
* Verified successful communication between both departmental networks.

---

## ✅ Verification

Connectivity was verified using ICMP ping tests between devices located in different departments.

Successful communication confirms:

* Correct IP addressing
* Proper subnetting
* Functional router interface configuration
* End-to-end Layer 3 connectivity

---

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

* IPv4 Addressing
* Subnetting
* Cisco Router Configuration
* Switch Connectivity
* Network Design
* End-to-End Connectivity Testing
* Basic Network Troubleshooting

---

## 📌 Project Status

Completed
