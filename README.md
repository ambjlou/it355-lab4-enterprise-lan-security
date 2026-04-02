\# IT355 Lab 4: Enterprise LAN Security \& Shellshock Analysis



\## 📌 Project Overview

This repository contains a comprehensive security assessment of an enterprise LAN environment. The core focus of this project was the identification, exploitation, and remediation of the \*\*Shellshock (CVE-2014-6271)\*\* vulnerability within a Linux-based web server.



\## 🛠️ Tech Stack \& Tools

\- \*\*Environment:\*\* Fedora Linux (Server), Windows (Host/Client)

\- \*\*Networking:\*\* Cisco Packet Tracer (IT/OT Segmentation), NAT, Routing Protocols

\- \*\*Services:\*\* Apache HTTP Server (httpd), GNU Bash

\- \*\*Security:\*\* Firewalld, Shellshock Exploitation via CGI scripts

\- \*\*Documentation:\*\* Markdown, Engineering Logs



\## 🚀 Key Learning Objectives

\* \*\*Network Segmentation:\*\* Configured IT and OT routers to isolate critical infrastructure from general corporate traffic.

\* \*\*Vulnerability Analysis:\*\* Conducted a root-cause analysis of the Shellshock vulnerability in Bash.

\* \*\*Incident Response:\*\* Developed a remediation plan including patching, firewall hardening, and intrusion prevention.

\* \*\*Evidence Management:\*\* Utilized Git/GitHub for version control and professional documentation of engineering logs.



\## 📂 Repository Structure

\* `Lab-04-Enterprise-LAN-Security.md`: Detailed engineering log and step-by-step lab walkthrough.

\* `/images`: Screenshots of network topology, ping tests, and exploitation evidence.



\## 🛡️ Remediation Summary

The security posture of the environment was improved by:

1\. Updating outdated Bash packages to patched versions.

2\. Implementing strict Access Control Lists (ACLs) on the OT-Router.

3\. Configuring Apache to restrict execution permissions on sensitive CGI directories.



\---

\*This project was completed as part of the IT355 curriculum.\*



