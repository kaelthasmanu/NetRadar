# 🔭 NetRadar 🔭

[Español](https://github.com/XDeadHackerX/NetRadar/blob/main/README.md) | [English](https://github.com/XDeadHackerX/NetRadar/blob/main/README-English.md)

> Herramienta creada por XDeadHackerX

<p align="center"><img width="120px" alt="Version" src="https://img.shields.io/badge/version-1.0-white.svg?style=for-the-badge"/></p>

[![Net-Radar-1-0-en.png](https://i.postimg.cc/QdVRPy9c/Net-Radar-1-0-en.png)](https://postimg.cc/FY5WkGxK)

---

*Good afternoon, I'm* **XDeadHackerX** *and I want to introduce you my new tool called* **NetRadar**. *This Tool is focused on* **Networking** *specifically on* **Mapping** *of* **Local Networks and Wifi Networks.** *At* **Local Network level,** *it is able to analyze all connected Devices (MAC, MAC Vendor, Operating System, Name, Device Type), all open Ports of each IP (Port, Service, Service Version, Status, Banner)*, find Servers (Name, Operating System, Service Version, Domain, Ports, etc. ) *At the level of * **Wifi Network** *we find 4 types of fully automated and very powerful scans (Aircrack-ng, Bettercap, NmCli and Wash), at the end of the scan it will generate a * **Graph** *in which it shows you a **schema** of the **Wifi Networks detected** (MAC, Distance from our Wifi Network Card, Beacons, Channel, Router Speed, Encryption, AUTH and the Wifi Network Name) and the **Devices connected** to each Network, showing you (Mac, Mac Manufacturer, Device Type and time connected to the Network). *

*As an extra,* **NetRadar** *brings a **Kit** which is able to group in a summarized and clean way very interesting information about the Computer, the Network Card and the Wifi Network Card [Options 1 and 2]*

<p align="center"><img src=https://i.postimg.cc/D0Vbpjfg/wifi1.gif width="350px"/></p>

---

## 💡 Features 💡

:ballot_box_with_check: **Network Card + Equipment Information** --> [*Public IP, Local IP, DNS, MAC, Operating System, Internet Speed Test* ]

:ballot_box_box_with_check: **Information Wifi Network Card + Utilities** --> [**Info Network Card** *(Technical Data, Interface, Drivers, Chipset, MACs, Supported Modes for the Network Card (Monitor Mode, AP, P2P-client, etc), In which Mode is the Network Card (Monitor or Managed), Data Transfer Rate, Supported Frequencies*) **Enable Monitor Mode** *(Enable Monitor Mode and Change MAC, NO NEED TO USE TOOL),* **Reset Network Card** *(Disable Monitor Mode, Set Default MAC and Restart NetworkManager)*]

:ballot_box_with_check: **Local Network Scan (One Device)** --> [**Quick Scan Ports** *(No. Ports, Status, Service of each Port, Mac, Mac Vendor), **Advanced Scan Ports** (No. Ports, Status, Service of each Port, Version of each Service, Content Information of each Port, Mac, Mac Vendor, Operating System, if it has Host Information on it), **Windows + Samba Scan** (Advanced Scan of all 65535 Ports, Enumeration of Users = In case of Power, Domain Acknowledgement = Name, SMB Acknowledgement = Permissions, Access, Class, Windows Assigned Device Name), **NetBios Scan** (Advanced Scan of all 65535 Ports, NetBios Name, Server Type/Name, Users = In case of Power)*]

:ballot_box_with_check: **Local Network Scan (Multiple Devices** --> [**Quick Scan IPs** *(IPs, MAC, Mac Vendor), **Quick Scan IPs + Ports** (IPs, No. Ports, Service of each Port, Mac, Mac Vendor Mac),**Continuous Scan IPs** (IPs, MAC, Mac Vendor, Name, KB Sent and Received), **Advanced Scan IPs Ports** (No. Ports, Status, Service of each Port, Version of each Service, Content Information of each Port, Mac, Mac Vendor, Operating System, if it has Host Information about it), **Scanning for a Specific Service** (HTTP/HTTPS, SMB, FTP, SSH, Telnet, Windows, NetBIOS)*]

:ballot_box_with_check: **Scan Wifi Networks** --> [*Option to scan with **Aircrack-ng, Bettercap, NmCli and Wash**. In the case of using Aircrack-ng when the scan is finished it creates a **Chart** in which it shows you a **schema** of the **Wifi Networks Detected** (MAC, Distance from our Wifi Network Card, Beacons, Channel, Router Speed, Encryption, AUTH and the Name of the Wifi Network) and the **Devices connected** to each Network, showing you (Mac, Mac Manufacturer, Device Type and time connected to the Network)].

:ballot_box_with_check: **Scan Devices Connected to a Wifi Network** --> [*Displays the Wifi devices connected to a Wifi Network, when the scan is finished it creates a Graph showing you a scheme of the connected devices showing the MAC of the devices, the amount of Traffic, the distance between each device and our Network Card, the lost packets, Notes and Probes.]

## 🛠 Install Tool 🛠

**0)** Install and use the Tool with **Root**

**1)** sudo apt update && apt -y full-upgrade

**2)** sudo apt-get install git

**3)** git clone https://github.com/XDeadHackerX/NetRadar

**4)** cd NetRadar

**5)** chmod 777 netradar.sh

**6)** bash netradar.sh

**7)** Choose a language

**8)** We can now enjoy the tool

## 🎲 Keep in mind 🎲

**[1]** In case you use the Tool to scan IP addresses it will work perfect except you have a VPN enabled, with the use of VPN most servers give wrong answers about their ports.

**[2]** In case you have downloaded an older version, I advise you to delete it and reinstall the tool (+requirements) to fix bugs and get improvements, which make the tool much better than previous versions.

**[3]** If inside the option ([4] Scan All Local Network Devices) in the section ([6] Search Services [HTTP, SMB, FTP, SSH,.]) you get stuck, just wait 3 minutes, this happens because of an error with one of the tools and it is dumping the wrong output to the background and the correct Information is launching it by terminal.

## 🔎 Versions 🔎

**(v1.0)** ---> Original Version.

## ⭐☕ Created by XDeadHackerX ☕⭐

**If you think this project has been useful, I would appreciate your support by giving this repository a star or inviting me for a coffee.**

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/XDeadHackerX)

Copyright © 2023, XDeadHackerX