---
layout: default
title: 2. Overviews and Backgrounds IoT
parent: § Survey on Security Issues and Measures in Different Layers of Internet of Things (IoT) 
grand_parent: S
nav_order: 20 
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

## 2. Overviews and Backgrounds IoT
### 2.1 What is Internet of things?

In this Literature review, we discussed about the structure, various application areas, the security and privacy related issues of IoT along with some open challenges. With the help of communication technology, Radio Frequency Identification (RFID) and Wireless Sensor Networks (WSNs), the sharing of data and information take place. IoT enables to connect people and smart things or objects around us, at anytime, anyplace, with anything and anyone, most preferably using network for exchanging data with each other without involvement of human. They are “Material objects connected to material objects in internet [3] which is shown in Figure 1.

There are several IoT technologies available, involving both hardware and software. The devices used to realize the IoT are classified as hardware, while the protocols and associated programs are classified as IoT software. Radio Frequency Identification (RFID), Wireless Sensor Network (WSN), Bluetooth, Wi-Fi, Smart Phones, and other devices are some of the most common and crucial IoT gadgets. Artificial Intelligence (AI), ZigBee, Near Filed Communicators (NFC), and other software are utilized to communicate these devices [2]. The hardware devices can collect data from installed sensors and send it to servers via local digital networks or the internet.

![Figure 1: Test Scenario of IoT](https://statics.bsafes.com/images/papers/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-fig-1.png)

Figure 1: Test Scenario of IoT


![Figure 2: IoT: a symbolic interaction model with various world](https://statics.bsafes.com/images/papers/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-fig-2.png)

Figure 2: IoT: a symbolic interaction model with various world

A symbolic interaction model of IoT is fully interacted with the various world like: real physical world, digital world and virtual cyber world which is depicted in Figure 2. So these worlds are integrated with the three terms such as: thing, data, and semantic integration.

### 2.1 Evolution of Internet of Things (IoT)
The rapid development of internet commences, by connecting device to device to communicate and exchange data and information using various technologies. Then the mobile internet was introduced by connecting mobile devices to the internet and User. And finally people tried to connect physical objects or things to internet to make life more easy and comfortable, which leads to “Internet of Things” i.e. Internet of everything can refer to IoT [17].

The Internet was first introduced in 1989 by connecting device to device to exchange data and information, and since from the evolution of internet, the trend of connecting various objects to internet have become very popular and widely adapted, Then the mobile devices connected to form mobile internet [4] [23].

The main advantage of IoT is to allow infinite number of machines to be connected with each other to produce and transmit information through a large scale of wireless network using automated device and sensor, which may not be useful in case of incorrect and insufficient data processing [18]. This section begins with a discussion over essential technology of IoT, Architecture and protocol required for IoT networks which is depicted in Figure 3.

IoT based on 5 different essential technologies for the successful deployment of IoT based services and products such as
i. RFIDs: Radio Frequency identification  
ii. WSN: Wireless sensor Network  
iii. Middleware  
iv. Artificial Intelligence (AI)  
v. ZigBee  

**i. Radio Frequency Identification:** It has rendered capability to automatically identify and capture unique data using its different components such as RFID tag and RFID Reader. RFID Tag, Reader, and Antenna may be used to communicate data across systems. Tags with RFID technology can be used to transmit digital data and store data in EPC (Electronic Product Codes) format. [26]. It's similar to a smart barcode tracking system, with an exception of storing more data than a regular barcode system. Three different types of RFID tags are available, namely the active, passive and semi-passive. There is no battery in the tag and the power comes from a solar cell. An active RFID tag continuously broadcasts its own signal like a telephone and has its own power source [27]. It is basically used in the field of manufacturing, hospital laboratory equipment’s etc.

As compared to using an internal power source, a passive RFID tag is powered by the radio frequency energy that is transferred between a reader and a tag during the reading process. It is used in supply chains as well as electronic tolls and more. Batteries are used to power the microprocessor in semi-passive tags, which then communicated by sucking power from readers [16].

**ii. Wireless Sensor Networks (WSNs):** It is an infrastructure less wireless network. It has dedicated sensor attached to cooperate with RFID sensor that monitor physical environment condition and passes the data (such as Temperature, pollution level, humidity and wind) through their network to the central system [22].

**iii. Middleware:** It is software lies in between Operating system and the application running on it [8].

**iv. Artificial Intelligence (AI):**
As the name implies, artificial intelligence (AI) serves as a substitute for human intelligence. It is responsible and sensitive enough to make decisions as individuals. In this current era, people expect devices to behave like people, to respond to their words and act accordingly, to function as if they were virtual persons [28].

**v. ZigBee:**
ZigBee, like Bluetooth, is a popular short-range wireless technology that can transport data at roughly 250 Kbps and has a range of about 100 meters. It is a less expensive, less energy-consuming, and more secure wireless networking solution. It can be found in star topology, mesh topology, and tree topology [29].

### 2.2 Architecture of IoT
The structure of IoTs consists of following 4 different layers such as perception layer, Gateway and Network Layer, management service layer and Application layer.

### A. The perception layer
This layer is also called as device layer or recognition layer. It consists of various sensor networks, RFID tags, embedded systems, readers and actuator to gather information [15]. In this layer the sensor first receives data and information in analog form and converts it to its corresponding digital form. Each of these sensors recognizes the physical world, information storage (e.g. RFID tags) and information collection (e.g. sensor Network) [4].

![Figure 3: Architecture of IoT](https://statics.bsafes.com/images/papers/Survey-on-Security-Issues-and-Measures-in-Different-Layers-of-Internet-of-Things-fig-3.png)

Figure 3: Architecture of IoT

### B. Network and gateway layer
These two layers consist of physical component and network communication software. In network layer the relevant data and information, which are collected from sensor and actuator transforms to its next layer (i.e. Management Layer) through multiple communication protocols and processes the data to some extent and sends the particular information to the cloud [15]. It also provides intelligence by sending back the data received from the cloud. It should have robust network and high performance and support multiple organizations to exchange information With each other independently [3]

### C. Management Layer
In between application Layer and Network layer, it acts as an interface in a bidirectional mode. As a result, this layer is responsible for receiving large amount of raw data from different connecting devices and extracting important information from stored data as well as real-time data while guaranteeing security and privacy [6].

### D. An application layer
It is the top most layer of IoT. This layer is known as the user interface layer. It provides same type of services to all its connected devices, and responsible for delivering application specific services to the user. It acts as end user layer, where the user can access different applications on various fields such as health care, military, transportation, supply chain, agriculture, government, retail etc. [10] [14].

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
