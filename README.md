# Security Awareness Phishing Simulation

## Project Overview

This project was developed as part of the ApexPlanet Cybersecurity Internship Capstone Project.

The objective was to design and implement a Security Awareness Phishing Simulation in a controlled virtual lab environment. The project demonstrates how phishing awareness campaigns can be conducted safely while monitoring user interaction, collecting logs, analyzing network traffic, and performing incident response activities.

---

## Objectives

* Create a phishing awareness training webpage.
* Simulate user interaction in a controlled environment.
* Monitor user activity through web server logs.
* Capture and analyze network traffic.
* Perform incident detection and analysis.
* Demonstrate incident response procedures.
* Recommend mitigation strategies.

---

## Lab Environment

### Attacker / Awareness Server

* Kali Linux
* IP Address: 192.168.56.101

### Victim Machine

* Metasploitable 2
* IP Address: 192.168.56.102

### Network Configuration

* VirtualBox Host-Only Network

---

## Tools Used

* Apache2
* Kali Linux
* Metasploitable 2
* Tcpdump
* Wireshark
* VirtualBox

---

## Project Architecture

Metasploitable 2 (Victim/User)
|
| HTTP Request
|
Kali Linux (Awareness Server)
|
| Apache Access Logs
|
Traffic Capture (Tcpdump)
|
Packet Analysis (Wireshark)

---

## Implementation Steps

### 1. Web Server Setup

Apache2 was installed and configured on Kali Linux to host the awareness training page.

### 2. Awareness Landing Page

A training webpage was developed explaining:

* Phishing Indicators
* Suspicious Email Characteristics
* Safe Browsing Practices
* Reporting Procedures

### 3. User Simulation

Metasploitable 2 accessed the awareness page using HTTP.

### 4. Monitoring

Apache access logs recorded incoming requests.

### 5. Traffic Analysis

Tcpdump captured network traffic which was later analyzed using Wireshark.

### 6. Incident Response

Detected activities were analyzed and documented following incident response procedures.

---

## Results

* Successful deployment of awareness webpage.
* Successful user interaction simulation.
* Successful log collection.
* Successful packet capture and analysis.
* Successful incident response demonstration.

---

## Mitigation Recommendations

* Conduct regular phishing awareness training.
* Enable Multi-Factor Authentication (MFA).
* Implement secure email gateways.
* Deploy centralized log monitoring.
* Establish incident reporting procedures.

---

## Repository Structure

Security-Awareness-Phishing-Simulation/

├── README.md

├── report/

├── screenshots/

├── webpage/

├── pcaps/

└── diagrams/

---

## Author

Cybersecurity Internship Capstone Project

ApexPlanet Software Pvt. Ltd.
