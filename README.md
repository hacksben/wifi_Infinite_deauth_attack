# WiFi Infinite Deauth Attack

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python)
![Linux](https://img.shields.io/badge/OS-Linux-1793D1?style=for-the-badge&logo=linux)
![Wireless](https://img.shields.io/badge/Mode-Monitor-FF6B6B?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Research%20%2F%20Authorized%20Testing-orange?style=for-the-badge)

</div>

A research-oriented Wi-Fi deauthentication framework designed for authorized wireless security testing, controlled lab environments, and defensive analysis. The project automates interface preparation, network discovery, client detection, and deauthentication workflows in a structured, repeatable manner.

This repository demonstrates a practical approach to wireless traffic disruption simulations in a controlled environment, with strong emphasis on ethical use, responsible testing, and clear operational boundaries.

---

## ✨ Project Overview

`wifi_Infinite_deauth_attack` is a Python-based wireless testing utility focused on:

- monitoring and scanning nearby Wi-Fi networks
- identifying access points and connected clients
- switching the wireless interface into monitor mode
- simulating managed deauthentication events against selected clients
- collecting telemetry and activity information in a structured workflow

The project is intended for use in authorized network security research, lab-based wireless assessments, and defensive validation scenarios.

---

## 🧠 What the Tool Does

The workflow is designed to automate several stages of a wireless assessment:

### 1. Interface Initialization
- validates the wireless adapter
- checks privileges and environment requirements
- prepares the interface for packet monitoring and inspection

### 2. Wireless Scanning
- scans nearby SSIDs and AP metadata
- captures network details such as BSSID and channel information
- prepares a target list for follow-up analysis

### 3. Client Discovery
- identifies devices currently associated with nearby access points
- gathers information about client activity and wireless relationships

### 4. Deauthentication Simulation
- sends deauthentication frames against selected client targets
- evaluates device response and connection resilience
- supports stress-testing and controlled network disruption analysis

---

## 🏗️ Architecture

```text
wifi_Infinite_deauth_attack/
├── wifi_debug.py              # Core attack orchestration and scanning logic
├── README.md                 # Project documentation
├── README.txt                # Supporting reference notes
├── screenshots/              # Visual project output and UI captures
└── docs/                     # Additional notes or assets
```

The project uses a lightweight Python-based control loop with external wireless tooling commonly used in Linux-based wireless testing environments.

---

## 🔧 Technical Stack

- Python 3.x
- Linux-based wireless tools
- Monitor mode interface handling
- Packet-level network interaction
- Automated Wi-Fi scanning and control flow

Typical underlying components used in this workflow include:

- `iw` / `iwconfig`
- `airodump-ng`
- `aireplay-ng`
- `airmon-ng`
- Linux wireless interfaces

---

## 📸 Screenshots

<div align="center">

<img width="1920" height="1080" alt="WiFi deauth screenshot 1" src="https://github.com/user-attachments/assets/264b2acc-ba4a-4ed4-acdd-5c48d387b3ed" />

<img width="1920" height="1080" alt="WiFi deauth screenshot 2" src="https://github.com/user-attachments/assets/c3ce457d-5b98-4686-86f0-ee030bbac76c" />

<img width="1920" height="1080" alt="WiFi deauth screenshot 3" src="https://github.com/user-attachments/assets/7289ed01-7ac7-4709-b7b9-390d945b96e6" />

</div>

---

## ⚠️ Ethical and Legal Notice

This project is intended strictly for:

- authorized penetration testing
- educational research
- controlled lab environments
- defensive wireless validation
- security awareness exercises

This project must not be used for:

- unauthorized wireless attacks
- malicious disruption of third-party networks
- privacy violations
- abusive or illegal network interference

Any testing must be performed only with explicit permission and in full compliance with applicable laws, organizational policies, and ethical standards.

---

## 🛡️ Security Use Philosophy

The value of this project is in understanding how wireless disruption attacks work in order to:

- improve defensive monitoring
- validate detection capabilities
- assess wireless resilience
- support lab-based security training

It should be treated as a research and defensive assessment tool, not as a malicious automation framework.

---

## 🚀 Usage Notes

This repository contains a Python-based implementation intended for Linux wireless test environments with the proper tools installed and the required privileges.

Typical workflow:

1. prepare the wireless interface
2. switch the adapter into monitor mode
3. scan for nearby APs and clients
4. select targets in a controlled environment
5. execute deauthentication simulation under authorization
6. analyze network behavior and impact

---

## 🧾 Author

**MANDEEP PARMAR**

Cybersecurity Researcher | Wireless Security Research | Authorized Security Testing

- GitHub: https://github.com/hacksben
- LinkedIn: https://www.linkedin.com/in/mandeep-parmar-b73a54381
- Email: sparmar28332@gmail.com

---

## 📌 Summary

`wifi_Infinite_deauth_attack` is a focused wireless research project designed to demonstrate the mechanics of deauthentication workflows in a controlled, ethical environment. Its purpose is not misuse, but understanding, defense, and responsible security evaluation.

---

<div align="center">

<strong>Built for ethical research, defensive analysis, and authorized security testing.</strong>

</div>
