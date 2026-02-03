## Network Security Incident Analysis – SYN Flood Attack

This project presents a network security incident analysis conducted for a fictional travel agency as part of a cybersecurity training program.

### Scope
- Analysis of abnormal network traffic using packet capture data
- Identification of a Denial of Service (DoS) attack
- Evaluation of the impact on web server availability

### Key Activities
- Review of packet capture logs showing excessive TCP SYN requests
- Identification of a SYN flood attack based on traffic patterns
- Analysis of TCP three-way handshake abuse
- Documentation of the impact on server resources and availability

### Outcome
- Determination that the web server was affected by a SYN flood DoS attack
- Identification of resource exhaustion caused by half-open TCP connections

### Mitigation Actions
- Temporary isolation of the affected server
- Firewall rules applied to block malicious traffic
- Recommendation of long-term mitigations such as SYN cookies, rate limiting, and intrusion prevention systems

### Disclaimer
This is a case study conducted in a simulated environment for educational purposes only.
