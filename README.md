# 🔐 Cybersecurity Lab Environment Setup

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Virtualbox%20v7.2.22-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.3-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Linkedin-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
   <img src="https://img.shields.io/badge/Sayid Ahmed%20Mohamed%20Ali-C00000?style=flat-square" />


## 📌 Project Overview
This project is the starting point for my upcoming cybersecurity labs and hands-on projects.

The main goal of Week 1 was to set up and configure a virtual cybersecurity environment using Oracle **VirtualBox and Kali Linux**.

This lab gives me a safe environment to practice cybersecurity concepts, explore networking, learn security tools, and prepare for future penetration-testing activities.

## 🎯 Objectives

The main objectives of this project are to:

* Install and configure 7-Zip
* Install Oracle VirtualBox
* Create a VirtualBox NAT Network
* Download and import Kali Linux
* Connect Kali Linux to the lab network
* Configure and verify Kali Linux networking
* Create a clean Virtual Machine snapshot
* Document the complete lab setup
* Prepare the environment for future cybersecurity projects
* 
## 🛡️ Purpose of the Lab
The purpose of this lab is to create a safe and controlled environment where I can learn cybersecurity concepts and gain practical experience.

I will use this environment for future hands-on activities, including:

* Network reconnaissance

* Network scanning

* Vulnerability assessment

* Packet analysis

* Practicing cybersecurity tools

* SOC-related exercises

* Hands-on cybersecurity labs

* Authorized penetration testing

> ⚠️ **Important:**
> This laboratory is intended for educational purposes and authorized security testing only. Security tools must only be used against systems that I own or have explicit permission to test.
>
> ## ⚙️ Lab Configuration

| 🧩 Component       | ⚙️ Configuration   |
| ------------------ | ------------------  |
| 🖥️ Host OS         | Windows 11         |
| 🧠 Host RAM        | 16 GB               |
| ⚡ Processor       | Intel Core i7      |
| 🧰 Hypervisor      | VirtualBox 7.2.22  |
| 🐉 Security OS     | Kali Linux 2026.3  |
| 🧠 Kali RAM        | 2048 MB            |
| 🌐 Virtual Network | NAT Network        |
| 📡 Network Address | 10.0.0.0/24        |
| 🐧 Kali IP Address | 10.0.0.2/24        |
| 🚪 Default Gateway | 10.0.0.1           |
| 🌍 DNS Server      | 8.8.8.8            |
| 🔮 Future VM Range | 10.0.0.2–10.0.0.99 |

# 🪜 Lab Setup Procedure

## Step 1 – Install 7-Zip

I installed **7-Zip** to extract the Kali Linux virtual-machine package, which may be distributed as a .7z archive.
# SCREENSHOTS

<img width="1908" height="977" alt="2" src="Download & install 7-zip.png">

# Step 2 – Install Oracle VirtualBox

I installed **Oracle VirtualBox** on my Windows machine to create and manage virtual machines for my cybersecurity lab, and the installation was completed successfully, making it ready for the next setup steps.

<img width="1908" height="977" alt="2" src="Download & install Virtualbox.png">

# Step 3 – Create NAT Network

I created a dedicated **NAT Network** in VirtualBox using the network range **10.0.0.0/24** to provide a controlled networking environment for my cybersecurity lab and allow me to connect additional virtual machines for future hands-on projects.

<img width="1908" height="977" alt="2" src="Configure the network settings.png">

# Step 4 – Install and Import Kali Linux

I downloaded and imported **Kali Linux** into Oracle VirtualBox and connected it to my lab’s NAT Network, creating a safe environment for hands-on cybersecurity practice.

**Kali Linux provides tools for:**

* Network analysis
* Security testing
* Vulnerability assessment
* Digital forensics
* Penetration testing
* Cybersecurity learning and practice

**Result**: Kali Linux was successfully imported into VirtualBox and connected to my lab network, ready for future cybersecurity exercises and practical projects.

<img width="1908" height="977" alt="2" src="Download & import Kali Linux Virtual Machine.png ">

# Step 5 – Configure Kali Linux Network

I configured Kali Linux to connect to the laboratory network.

IP Address:
10.0.0.2/24

Gateway:
10.0.0.1

DNS:
8.8.8.8

I then verified that Kali Linux received an IP address from the configured virtual network.

 <img width="1908" height="977" alt="2" src="Setup the IP configuration of Kali Linux.png ">

 # Step 6- Create a Virtual Machine Snapshots
 
A clean snapshot of the Kali Linux virtual machine was created using Oracle VirtualBox. This provides a restore point that allows the VM to return to its original state if any unexpected changes occur during cybersecurity lab exercises.

<img width="1908" height="977" alt="2" src="Snapshots.png ">


## 🔎 Lab Verification

The Kali Linux lab environment was verified by checking the network interface configuration, testing connectivity to the NAT Network gateway and an external IP address, and confirming that the clean VM snapshot can restore the baseline configuration.
# 🔎 Lab Verification

| ✅ Test                        | 🧾 Command                      | 🎯 Expected Result              |
| ----------------------------- | ------------------------------- | ------------------------------- |
| 🌐 Check IP address           | `ip a`                          | Correct Kali IP displayed       |
| 📡 Test gateway               | `ping 10.0.0.1`                 | Successful replies              |
| 🌍 Test Internet connectivity | `ping 8.8.8.8`                  | Successful replies              |
| 🔎 Test DNS resolution        | `nslookup networkwalks.com`     | Domain resolves                 |
| 🧰 Verify Nmap                | `nmap --version`                | Nmap version displayed          |
| 🔄 Verify snapshot            | Restore snapshot and run `ip a` | Baseline configuration restored |

### Example Results

```text
IP Address:
10.0.0.2/24

Gateway:
10.0.0.1

DNS:
8.8.8.8
```

---

# 🐞 Problems Encountered & Solutions

Documenting problems and solutions is an important part of this project because troubleshooting is an essential cybersecurity and IT skill.

## Problem 1 – Network Configuration

I checked the network adapter settings in Oracle VirtualBox to ensure that the Kali Linux virtual machine was correctly connected to the NAT Network.

## Problem 2 – Maintaining a Clean Lab Environment

I created a VirtualBox snapshot after the initial setup to provide a clean recovery point in case future cybersecurity experiments change system settings or files.
# 💡 What I Learned

During Week 1, I learned how to build the foundation of a virtual cybersecurity laboratory.

### Technical Skills

1. How to install and use 7-Zip.
2. How to install Oracle VirtualBox.
3. How virtualization can be used for cybersecurity training.
4. How to create a NAT Network in VirtualBox.
5. How to import Kali Linux as a virtual machine.
6. How to connect a virtual machine to a virtual network.
7. How to check Kali Linux network configuration.
8. How to create and use VM snapshots.

## 🔐 Security & Ethical Use

This lab is intended for educational purposes and authorized security testing only.

# 🔗 Tools & Technologies

* **Windows 11** – Host Operating System
* **Oracle VirtualBox** – Virtualization Platform
* **Kali Linux** – Cybersecurity Operating System
* **7-Zip** – Archive Management
* **GitHub** – Project Documentation & Version Control

# 👤 Author

**Sayid Ahmed Mohamed Ali**

**Cybersecurity  IT Support Specialist**

**Program:** Networkwalks
**Batch:** B084
**Week:** 01

### LinkedIn

[Sayid Ahmed Mohamed Ali](https://www.linkedin.com/in/sayid-ahmed-mohamed-ali-39354414b/)

## 📌 Project Information

**Status: ✅ Completed – Week 1**
**Program Name:** Cybersecurity at Networkwalks | **Week:** 01 | **Project:** Cybersecurity & Pentesting Lab Setup | 

This project establishes a foundation for future cybersecurity labs, practical exercises, and GitHub portfolio development
