# Lab 04: Enterprise LAN Security Assessment
**Date:** April 1, 2026  
**Author:** Amber Lewis  
**Topic:** Shellshock Vulnerability Analysis & Incident Response

## 1. Network Infrastructure & Connectivity
Before testing for vulnerabilities, the network environment was mapped and connectivity was verified across the IT and OT sectors.

### Physical and Data Link Layer Verification
Initial checks focused on Layer 1 and Layer 2 connectivity to ensure the underlying infrastructure was stable.

![OSI Layer 1 Status](1.1%20osi%20layer%201.png)
*Figure 1.1: Physical layer status and connection verification.*

![IT Switch MAC Table](1.2%20mac%20table%20it.jpg)
*Figure 1.2: MAC address table for the IT sector switch.*

### Router Configuration & IP Mapping
The interfaces for the OT-Router were configured to facilitate secure communication between segments.

![OT Router Interface](1.4%20ot%20router%20interface.jpg)
*Figure 1.3: OT-Router interface status and protocol check.*

![Router Interface Configuration](1.5%20router%20interface%20config.jpg)
*Figure 1.4: Direct configuration of the router gateway interfaces.*

![OT Router IP Mapping](1.6%20ot%20router%20ip%20map.png)
*Figure 1.5: Detailed IP mapping and routing table overview.*

### Connectivity Testing
A ping test was conducted from Admin PC 01 to confirm that the network paths were reachable across routers.

![Ping Test Admin PC 01](1.7%20ping%20test%20admin%20pc%2001.jpg)
*Figure 1.6: Successful ICMP echo request from Admin PC to the target subnet.*

---

## 2. Shellshock Vulnerability & Web Security
The core of the lab focused on identifying and exploiting the Shellshock vulnerability within the web server environment.

### Exploitation Phase
Using specialized headers, the Shellshock vulnerability was triggered to demonstrate unauthorized access.

![Shellshock Exploit Part A](2.1A%20.jpg)
*Figure 2.1: Initial injection of the malicious function via HTTP headers.*

![Shellshock Exploit Part B](2.1B.jpg)
*Figure 2.2: Execution of remote commands through the bash vulnerability.*

### Verification of Secure Access
Post-remediation, the web services were tested to ensure that only authorized, secure protocols (HTTPS) were active.

![Server Configuration Check](2.2.jpg)
*Figure 2.3: Auditing server scripts and bash versions.*

![HTTPS Browser Test](2.3%20https%20browser%20test.jpg)
*Figure 2.4: Final verification showing secure browser access to the web server.*

---

## 3. Conclusion
The evidence above documents the full lifecycle of the assessment—from initial network discovery and routing configuration to the successful identification and mitigation of the Shellshock vulnerability.