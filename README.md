# 🌐 BGP Dual Homing & Traffic Engineering Lab (Multi-Vendor)

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Status](https://img.shields.io/badge/status-completed-green.svg) ![Vendor](https://img.shields.io/badge/Vendor-Cisco%20%7C%20Huawei-orange)

**Author:** [Hendri (Susilo19042004)](https://github.com/Susilo19042004)  
**Lab Environment:** EVE-NG (Cisco IOS & Huawei VRP NE40E)

## 📖 Overview
This project demonstrates a robust **Dual Homing BGP** architecture connecting a Customer Enterprise network to two different ISPs (Cisco & Huawei). The primary goal is to achieve **High Availability** and precise **Traffic Engineering** control.

Key features implemented:
* **eBGP Peering** across multi-vendor devices (Cisco IOS & Huawei VRP).
* **Inbound Traffic Control** using *AS-Path Prepending*.
* **Outbound Traffic Control** using *Weight Attribute*.
* **Security Filtering** using *Prefix-Lists* to prevent Route Leaking.

## 🗺️ Network Topology

### EVE-NG Lab Snapshot
![EVE-NG Topology](./images/topologi.png)

*(Note: If the image above does not load, please check the `images/` folder)*

### Logic Diagram
