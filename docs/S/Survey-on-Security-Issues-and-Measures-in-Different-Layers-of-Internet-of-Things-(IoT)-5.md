---
layout: default
title: 5. Protective Measures for different Layer of IoT Structure  
parent: § Survey on Security Issues and Measures in Different Layers of Internet of Things (IoT) 
grand_parent: S
nav_order: 50 
---
<style>
.dont-break-out {
  /* These are technically the same, but use both */
  overflow-wrap: break-word;
  word-wrap: break-word;

     -ms-word-break: break-all;
  /* This is the dangerous one in WebKit, as it breaks things wherever */
  word-break: break-all;
  /* Instead use this non-standard one: */
  word-break: break-word;
}

.youtube-container {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%;
}
.youtube-video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

</style>

<div class="dont-break-out" markdown="1">

1. TOC
{:toc}

## 5. Protective Measures for different Layer of IoT Structure
In IoT, multiple physical Devices, technologies and companies have been involved, to transmit a lot of data through the smart sensors. It has been recognized that four interconnected and interactive components such as people, object, hardware and software are communicated over public and entrusted network, hence there may be a possibility of loss of private data in case of unauthorized manipulation of hardware and software.

**i. In Perception layer,** the temperature sensors, sound sensors, vibration sensors, pressure sensors are different types of controlling modules and also acts as collecting module to gather and interchange data in between them for which IoT is designed. The security issues can be raised in perception layer by the detecting a faulty node or abnormal sensor node. This can be happened when a cyber-attacker physically attacked, to destroy or disabled the sensor node. To avoid degradation of service in perception layer, it needs to detect the damage node and the take needful actions. Chen et al. [32], intended a localized fault detection algorithm to discover the faulty nodes in WSN.

Da Silva et al. [33], intended a decentralized intrusion detection system model for the WSN. Wang et al. [34] derived the intrusion detection probability in both homogeneous and heterogeneous WSN. Another way to protect the perception layer is the use of key exchange algorithm and cryptographic algorithm. Public key algorithm has used for node authentication and can be better secured the entire network as compare to key exchange algorithm [35].

According to Gaubatz et al. [36], Rabin’s scheme, NtruEncrypt, and elliptic curve cryptography are three low-power public key encryption algorithms used for WSNs. Key management includes secret key generation, distribution, storage, updating, and destruction. But presently, internet applications like Internet Engineering Task Force (IETF) and Institute of Electrical and Electronics Engineers (IEEE) developed by some standardize bodies were used to solve all the security and communication related problems in internet network. These applications provide a protocol stack for the different layer of IoT, i.e. the standardized body IEEE 802.15.4 which is a group of Wireless Personal Area Networks (WPANs), emphasis for the secure communication between low resources like power, memory & bandwidth, with constrained environment devices. Hence it secures perception layer and the logical medium access layer (MAC) [16] [17].

**ii. In Network layer,** for IoT devices in WSN the data packets are transmitting to the transport layer by the help of the IPv6 protocol over low power wireless personal area networks (6LoWPAN) to enable IPSec communication with IPv6 nodes. Hence it is not necessary to modify existing end points on internet to communicate securely with WSN, which results the actual E2E security implementation without need of a trustworthy gateway. This IPv6 is controlled by Internet engineering task forces (IETE) application and defines many open standard protocols like UDP, TCP & HTTP. IPv6 can be helped in the packet encapsulation, packet fragmentation, header compression & reassembly the fragmented packets to recreate the original IPv6 packets. Raza et al. [37] intended an E2E secure communication between IP enabled sensor networks and the traditional Internet proposed an E2E secure communication between IP enabled sensor networks and the traditional Internet [16] [17].

**iii. In transport Layer,** two protocols are used i.e. UDP and TCP. UDP is lighter and much faster than TCP, so it is mostly used by the IOT scenarios. UDP is a connection oriented protocol and guarantee on the packet delivery. Header size of TCP is much greater than UDP. CoAP is higher level IoT protocol uses UDP in its application layer instead TCP [38]. As a consequence, regarding users, server and trusted third party must be addressed and ensure the IoT security trusted technologies which include device integrity, tamper_ resistant modules and trusted execution environments.

To ensure security in IoT, the main focus should be on confidentiality, integrity, authentication and availability of data. Confidentiality refers to secure information from unauthorized persons, parties or system during transmission of data packets [39]. Encryption is the common approach, which ensures the data confidentiality through encode and decode process as well as prevent unauthorized access of network generated data e.g. Domain specific information such as user identity, positions.

Transmitting data via a network with integrity ensures its accuracy and consistency. In this context, the use of sensor values or control orders to prevent data change by unauthorized users or systems during transmission of data over the network [40]. To prevent information alteration via message injection, message reply, and message delay on the network, integrity plays an important role which denies information change. Integrity violation can be a major reason for some security issues such as Modified data which may damage the control systems and facility which includes Communication and security system, lighting, heating and hydro systems [5].

The availability of the system resources ensures that the authorized individual can access them without being denied access to those resources. According to the term "availability of services", only authenticated real-time objects have access to the necessary resources whenneeded. An individual's life can be put at risk if they aren't available when they need to be when it's most important to be [21].

When a system, user or item is authentic, the system’s internal principle can be mapped to this identity. In case of Device Authentication, the Forged data flow in the network could be prevented by ensuring device authentication before getting into network which results to keep away the malicious device from IoT environment. The Cryptographic hash algorithm can be used to validate the integrity and authentication of software on various devices of the IoT network when it comes to Safe Booting. The WH and NH cryptographic algorithm can be implemented on end device of network instead of hash algorithm as these devices posses very low computing power. Moving on to Web Firewall Application, Web firewall application should use to protect the IoT environment by identifying a possible attacker. It's also important to secure the security, authenticity, confidentiality and stability of the IoT environment by using anti-virus and anti-spyware software [15].

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/S/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-(IoT)-1/">
1. Introduction</a></li><li> <a href="/docs/S/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-(IoT)-2/">
2. Overviews and Backgrounds IoT</a></li><li> <a href="/docs/S/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-(IoT)-3/">
3. Applications of IoT in various fields</a></li><li> <a href="/docs/S/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-(IoT)-4/">
4. Security, Privacy and Challenges in IoT Layers</a></li><li> <a href="/docs/S/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-(IoT)-5/">
5. Protective Measures for different Layer of IoT Structure</a></li><li> <a href="/docs/S/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-(IoT)-6/">
6. Conclusion</a></li><li> <a href="/docs/S/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-(IoT)-7/">
References</a></li></ul>
***

</div>
