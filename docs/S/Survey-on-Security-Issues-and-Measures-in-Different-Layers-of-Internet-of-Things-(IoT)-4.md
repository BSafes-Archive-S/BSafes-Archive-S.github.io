---
layout: default
title: 4. Security, Privacy and Challenges in IoT Layers 
parent: § Survey on Security Issues and Measures in Different Layers of Internet of Things (IoT)  
grand_parent: S
nav_order: 40 
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

## 4. Security, Privacy and Challenges in IoT Layers
Due to the popularity and high acceptance of IoT, the main challenge is to provide complete security and privacy to user’s private and sensitive data. This section describes the various security challenges faced at the different layers of the IoT.

### 4.1 Security issues in the Perception Layer
In perception layer, various IoT devices are connected with each other to communicate or exchange data and information. The hardware attack is the most general attack in this layer,which are describe as follows:

#### Forged node insertion:
It's possible for an attacker to destroy IoT devices and stop data transmission between them by using a Forged Node Insertion (FNI) attack. Here, the attacker inserts an invalid node in order to gain control over a network's data stream, causingit to be unavailable [15]. 

#### Hardware Jamming: 
Attacker can obtain information relating to communication keys, routing table, cryptographic key by replacing original parts of hardware and also by capturing the gateway node [15].

#### Unauthorized access to tags: 
The device tags can be accessed and modified by unauthorized user without authorization [9]. 

#### Spoofing: 
In spoofing, attacker can make RFID system false by transmitting false and manipulated information to RFID system and making it appear as authenticate and original source [9].

### 4.2 Security issues in the Network Layer
Some security challenges in network layer are given below:

#### Denial of services: 
In DOS attack, the attacker enforces to shut down a machine or network, making it inaccessible or unavailable to the intended users by overwhelming or flooding with alots of useless traffic [14] [19]. 

#### Man in Middle Attack:
In this assault, the attacker does not need to be physically present on the network. When an attacker interrupts a communication channel, it can be observed andmanipulated [9]. 

#### Sinkhole Attack:
It is one of the most damaging routing assaults on the Internet of Things. Attackers collapse network connectivity to prevent data packets delivery to their intended destination. [9].

### 4.3 Security issues in the Network Layer Application Layer

#### Phishing Attacks:
By faking the user's authenticated identity, the attacker can gain access to sensitive and confidential data and information through an infected email or phishing website [14][15]. 

#### Virus, Worms, Spyware, Trojan horse:
As a result of an adversary infecting the system with malicious software code, a variety of events can occur such as information theft, data manipulation, denial of services, or incorrect data [15].

#### Summary of security challenges of IoT:
![Summary of security challenges of IoT:](https://statics.bsafes.com/images/papers/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-table-1.png)
![Summary of security challenges of IoT:](https://statics.bsafes.com/images/papers/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-table-2.png)


### 4.3 Intrusion Detection System (IDS)
An intrusion detection system (IDS) is a computer software or device that detects fraudulent behaviour or policy violations in a system or systems. The intrusion detection system (IDS) defines intrusion detection as "the identification of acts designed to impact trust, honesty, or available resources” [24]. Every detected action or breach is relayed to or efficiently collected by the Admin via the SIEM system. This SIEM combines all results from many sources in order to distinguish fraudulent behavior and counterfeit warning indicators from alert filters. The firewall appears to be distinct from the IDS, where both firewalls and IDS contribute to network security.

For network troubleshooting, make strategic network notes or markers. It examines the traffic flow throughout the entire sub-net and represents the congestion caused by documented sub-network attacks. The Host intrusion detection (HIDS) system is active on network access hosts [25]. This HIDS checks packets for incoming and outgoing devices and alerts your user or administrator to any unusual behavior. IDS stands for intrusion detection system, which searches for specified patterns such as network bit stream sequences or specific excellently sequences of a suspect's harmful instructions.

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
