# Cybersecurity Incident Report

## Scenario
As a security analyst at a travel agency, I was alerted by the monitoring system about an issue with our web server. Employees who access the company’s website to check for sales and vacation packages for customers reported connection timeout errors. After investigating, I discovered a large number of incoming TCP SYN requests from an unfamiliar IP address. The influx of traffic overwhelmed our web server, causing it to become unresponsive.

---

## Section 1: Identifying the Type of Attack
The connection timeout error may be caused by a **SYN Flood Attack**. This is indicated by:
- Logs showing an unusually high volume of TCP SYN requests from an unknown IP address.
- The web server becoming overwhelmed by these requests, causing a denial of service.

---

## Section 2: Attack Explanation

**How the Attack Affects Website Functionality**

When a user attempts to visit the website, a **three-way handshake** occurs to establish a TCP connection. This handshake consists of:
1. **SYN**: The client sends a SYN packet to the server to request a connection.
2. **SYN-ACK**: The server replies with a SYN-ACK packet, acknowledging the request.
3. **ACK**: The client responds with an ACK packet, completing the connection.

In a **SYN Flood Attack**, the attacker sends numerous SYN packets without completing the handshake, which:
- Keeps the server engaged in handling incomplete connections.
- Prevents legitimate users from establishing connections, effectively denying them access to the website.

**Log Analysis and Server Impact**

The logs indicate an abnormal volume of incoming SYN requests, which the server struggled to process, ultimately causing it to become unresponsive. This suggests that the server’s resources were exhausted by the attack, resulting in service interruptions.

---

## Section 3: Immediate Actions Taken

1. **Server Taken Offline**: The web server was temporarily taken offline to allow it to recover and return to normal operations.
2. **Firewall Configuration**: A rule was implemented to block the IP address responsible for the malicious traffic.
3. **Next Steps**: The firewall block is only a temporary solution, as the attacker could potentially spoof other IP addresses. Further steps will be discussed with management to prevent future occurrences.

---

## Conclusion
A SYN Flood Attack was identified as the root cause of the website’s downtime. By temporarily blocking the attacker's IP and taking the server offline, we restored the system’s functionality. Further measures are recommended to safeguard against potential attacks of a similar nature.

