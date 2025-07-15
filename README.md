# 🛡️ Cybersecurity Homelab Project - Inspired by myDFIR

Welcome to my ongoing Cybersecurity Homelab project, inspired by the myDFIR YouTube series. This repository documents my journey building a fully functional homelab environment for security research, hands-on training, and tool experimentation.

> 📌 Current Progress: Part 2 of 3 completed  
> 🔧 Part 3: Pending (will resume after addressing potential troubleshooting)

---

## 📸 Screenshots

Images of each major step are included in the `/images/` folder and referenced below for visual tracking.

---

## 🗂️ Table of Contents

1. [Overview](#overview)
2. [Goals](#goals)
3. [Setup Prerequisites](#setup-prerequisites)
4. [Step-by-Step Progress](#step-by-step-progress)
   - [Step 1: Host OS Preparation](#step-1-host-os-preparation)
   - [Step 2: Virtualization Software Installation](#step-2-virtualization-software-installation)
   - [Step 3: Virtual Network Configuration](#step-3-virtual-network-configuration)
   - [Step 4: Installing and Configuring VMs](#step-4-installing-and-configuring-vms)
   - [Step 5: Initial Tool Deployment](#step-5-initial-tool-deployment)
5. [Next Steps](#next-steps)
6. [Troubleshooting](#troubleshooting)
7. [Credits](#credits)

---

## 🧱 Step-by-Step Progress

### ✅ Step 1: Host OS Preparation

- Verified system resources (RAM, CPU virtualization enabled)
- Installed required drivers and updates
- Screenshot: -

### ✅ Step 2: Virtualization Software Installation

- Installed [VirtualBox/VMware] and created base VM templates
- Enabled networking features (Internal Network) for testing purposes
- Screenshot: -

### ✅ Step 3: Virtual Network Configuration

- Configured virtual switches and interfaces
- Created isolated lab network (non-routable from host)
- Screenshot: `images/Kali Specs.png` `images/Windows Specs.png`

### ✅ Step 4: Installing and Configuring VMs

- Created and installed Kali Linux, and Windows 10 VMs
- Took VM snapshots after configuration
- Screenshot: `images/Baseline Kali`

---

## ⏭️ Next Steps

- Move on to part 3 of the myDFIR series

## 🛠️ Troubleshooting

### ❌ VM Internet Access Issues

Currently troubleshooting NAT and Bridged Adapter settings to allow internet access from all VMs before isolating the environment.

---

## 🙏 Credits

- YouTube Channel: [myDFIR](https://www.youtube.com/@myDFIR)
- Tools: Kali Linux, Windows 10, VirtualBox

---

## 📌 Notes

This project is a personal learning experience and is not meant for production use. Feedback, pull requests, or issue reports are welcome.
