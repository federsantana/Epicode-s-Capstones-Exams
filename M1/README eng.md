The document "esercitazione finale Modulo 1 signor Presti Federico" focuses on the implementation of effective communication between two virtual machines, one running Kali Linux and the other Windows 10 Home, using a client-server architecture. During the exercise, the Inetsim software was used to simulate web requests and the Wireshark tool to intercept and analyze network traffic.

- The activity focused on several phases:

Configuration of static IP addresses and setup of the DNS name "epicode.internal" to facilitate communication between the machines.

Use of Inetsim to start an HTTPS service, followed by the analysis of certificate errors highlighting the importance of the HTTPS protocol for secure communications.

Use of Wireshark to trace and analyze network packets, identify the MAC addresses of the virtual machines, and compare data from HTTPS and HTTP sessions.

- Key observations include:

Differences in visibility and readability of the contents of requests, where HTTPS contents appear encrypted unlike HTTP requests.

The use of different numbers of packets and protocols during communication sessions, with particular attention to the TLS security protocol employed in HTTPS connections to ensure encrypted and secure communication.
