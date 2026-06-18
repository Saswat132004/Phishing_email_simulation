# Incident Response Report

## Incident Title

Security Awareness Phishing Simulation

---

## Incident Summary

A controlled phishing awareness exercise was conducted within a virtualized laboratory environment.

The objective was to evaluate user interaction with awareness content and demonstrate the collection and analysis of security-related evidence.

---

## Detection

### Detection Methods

* Apache Access Logs
* Tcpdump Packet Capture
* Wireshark Traffic Analysis

### Indicators Observed

* HTTP GET requests
* User access to awareness webpage
* Logged source and destination IP addresses

---

## Analysis

### Source IP

192.168.56.102

### Destination IP

192.168.56.101

### Protocol

HTTP

### Activity

User successfully accessed the phishing awareness training webpage hosted on the awareness server.

### Impact

No malicious activity occurred.

No credentials were collected.

No systems were compromised.

---

## Containment

* Activity monitored in real time.
* Logs collected and preserved.
* Network traffic captured for analysis.

---

## Eradication

No malicious artifacts were identified.

No eradication activities were required.

---

## Recovery

* Server functionality verified.
* Log integrity confirmed.
* Evidence archived.

---

## Lessons Learned

* User awareness is a critical security control.
* Logging provides valuable forensic evidence.
* Packet analysis assists in understanding user behavior.
* Security awareness exercises improve organizational readiness.

---

## Recommendations

1. Conduct periodic awareness campaigns.
2. Enable Multi-Factor Authentication.
3. Monitor web and email logs.
4. Deploy SIEM solutions.
5. Establish clear incident reporting procedures.
