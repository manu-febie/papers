# W2 - Source of Evidence

#### Network Based Evidence

Traditionally, the focus of digital forensics have been locating evidence on the host hard drive. But there is a wealth of information to be obtained within the points along the flow of traffic from a compromised host to an external Command and Control server for example.

It is important that incident responders have a strong understanding of what the internal network infrastructure looks like. For example, organizations can create and maintain up to date network diagrams. The diagram has to be clear enough for responder to identify individual network components such as switches, routers or wireless access points. Sources for network based evidence can be:

- On the wire.
- In the air
- Switches
- Routers
- DHCP Server
- DNS Server
- Authentication Server
- NIDS/NIPS
- Firewalls
- Web proxies
- Application Server
- Centralized Log Server
- Modem

#### Principles of Internetworking

Combined of two words, inter and networking, Interneworking implies an association between totally different nodes or segments. It is the process of connecting different networks by using intermediary devices such as routers or gateway devices. Data communications is ensured among networks owned and operated by different entities using a common data communication and the Internet Routing Protocol.

The Open System Internconnection (OSI), has been developed by network designers in the late 1970s, to coordinate the design of networking infrastructure. The layers from top to bottom are:

7. Application
6. Presentation
5. Session
4. Transport
3. Network
2. Data Link
1. Physical

Every network analyst should be fluent in the OSI model labels. 

#### Internet Protocol Suite

> The Internet protocol suite is the conceptual model and set of communications protocols used in the Internet and similar computer networks. It is commonly known as TCP/IP because the foundational protocols in the suite are the Transmission Control Protocol and the Internet Protocol.

#### Lab Session - Creating Evidence

In preparation for this weeks first lab session of the semester, I prepared a new virtual machine inside virtualbox running Kali Linux. I customized Kali Linux to my liking so it does not interrupt my workflow.

For the first lab session we used *tshark*, basically *Wireshark* but terminal based. The objective was to capture data inside a `.pcap` file. `.pcap` file are used to determine network status, allowing analyzers to attend to problems that may have occured on the network and allowing them to study data communications.
