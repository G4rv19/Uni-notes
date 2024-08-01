# <font color="red"> Introduction to Computer Networks </font>
* Internet History
* Network Terminology
* Basic Network Communications
* Network architecture


## Network Control Protocol (NCP)
1. The 1st standard operational packet-switching protocol on ARPANET and standardised the **ARPANET** network interface.
2. NCP allowed users to access and use computers and devices at remote locations and to transmit files between computers.
3. It provided the middle layer of the protocol stack, and enabled application service such as email and file transfer.
Robert Kahn and Vinton Cert built on NCP to develop standard TCP/IP

## IMP - Interface Message Processor

- The packet switching node that connected participant networks to ARPANET from the late 1960s to 1989 was known as an IMP.
- IMPs, the first-generation routers, were Honeywell DDP-516 minicomputers with special interfaces and software.
- IMPs required a bit-serial interface to connect to a host computer.
- The IMP's software and ARPA network protocol were detailed in RFC1, describing how IMPs routed messages using protocols later adopted by internet routers.

## Internet History 

- In response to the USSR’s first artificial satellite, the US established ARPA (later ARPANET) within the Department of Defense in 1957 to lead in science and technology.
- ARPANET, commissioned by the DoD in 1969, used Information Message Processors (IMPs), which were Honeywell 516 mini-computers with 12K of memory.
- By 1971, ARPANET had 15 nodes and 23 hosts.
- - In 1974, "A Protocol for Packet Network Intercommunication" outlined the design for TCP.
- **ARPA adopted TCP/IP as the ARPANET protocol suite in 1982.**
- The External Gateway Protocol (RFC 827) was specified in 1982.
- The Internet switched from NCP to TCP/IP on January 1, 1983.
- The World Wide Web (WWW) launched in 1991.
- The Internet Toaster, the first remotely operated machine, was connected in 1990.
- The US White House went online with [www.whitehouse.gov](http://www.whitehouse.gov) in 1993.
- Pizza Hut began offering online orders via the WWW in 1994.


## LAN, WAN, MAN and Internetworks

1. Local Area Network (LAN)
* a network that interconnects devices within a limited geographic area.
2. Wide Area Networks (WAN)
* use of services of third party communication providers to carry network traffic from one location to another.
3. Metropolitan area network (MAN)
* Use WAN technologies to interconnect LANs in a specific geographic region, such as county of city.
4. Internetwork
* is a network collection of LAN tied together by devices such as routers.

## Internet, Intranet and Extranet

### Internet
1. A worldwide public internetwork
2. Uses protocols such as TCP/IP and HTTP to transfer and view information.
### Intranet
1. A private internetwork in which devices and servers are only available to those user connected to the internal network.
### Extranet 
1. An enterprise network that extends to external users to access internal resources.

![](screenshots/Pasted%20image%2020240731172856.png)

## Packets
1. **Chunks of data sent across the network** are usually called packets or frames, with packets being the more well known term.
2. A chunk of data with source and destination IP address to it.


## Frames 

1. A packet with source and destination MAC address added to it.
	1. The packet is "Framed" by the MAC addresses on one end and an error checking code on the other.
2. The process of adding IP address and MAC address to chinkss of data is called **encapsulation**.
3. Information added to the front of the data is called header and information added to the end is called a trailer.

## Bit 
1. A bit is a binary digit, the smallest increment of data on a computer.
2. A bit can hold only one of two values: 0 or 1, corresponding to the electrical values of Off or on respectively.

## Packets and Frames

1. Computers transfer information across networks in short bursts of about 1500 bytes of data.
2. Reasons data is transferred this way:
	1. Pauses between bursts allow other computers to transfer data during pauses
	2. Allows the receiving computer to process received data  
	3. Allows the receiving computer receive data from other  computers at the same time  
	4. Gives the sending computer an opportunity to receive data from  other computers and perform other processing tasks  
	5. If an error occurs during transmission of a large file, only the  chunks of data involved in the error needs be resent.


## The Fundamentals of Network Communication
* A computer network consists of two or more computers connected to some kind of Transmission medium. e.g. cable or air wave.
* To access the Internet, a computer has to be able to connect to network.

## Hardware Components
1. NIC - **Network Interface Card**
2. Network medium
3. Interconnecting device

### NIC - Network Interface card
* An add on plugged in motherboard expansion slot which provides a connection between the computer and the network.
* The two main types of network cards are:
	* Wired 
	* Wireless

### Network Medium
* An Ethernet cables is used to attach to NIC of computer for connecting through wired network
* A wireless NIC translates data into radio signals and then transmits these signals through the use of an antenna for a wired connection.

### Interconnecting devices
* To connect two or more computers on the network without having to be connected to each other directly
* A router is used for connecting multiple networks together
* A switch is used for connecting multiple computers within a network
* An access point (AP) allows wireless devices to connect to a wireless network.

![](screenshots/Pasted%20image%2020240731174624.png)


![](screenshots/Pasted%20image%2020240731174641.png)


## Software Components 

* Network clients and servers
	* Network client software requests information stored on another network computer or device
	* Network server software allow computers to share its resource.
* Protocols
	* Define the rules and formats a computer must use when sending information across the network
* NIC driver
	* Receives data from protocols and forwards this data to the physical NIC.

### Steps of Network Communication
1. Application tried to access a network resource by sending a message.
2. Client software formats the message and passes the message on the network protocol
3. Protocol packages the message in format suitable for the network and send it to the NIC driver.
4. NIC driver sends data in the request to the NIC card to be converted into necessary signals to be transmitted on the network.
### layers of the Network Communication Process

* Each step required for a client to access network resources is referred to as **layer**
* Each layer has a task and all layers work together.

![](screenshots/Pasted%20image%2020240731175336.png)

## Network Architecture

It is the design of a communication network
It is a framework for the specification of :
	a network's physical components and their functional organization and configuration, its operational principles and procedures as well as data formats use. 


### Two Reference Models
* Two models reference models :
	* TCP/IP protocol suite
	* Open System Interconnection (OSI) model
* To describe the layers of hardware and software necessary to transmit data between two points or for multiple devices/applications to interoperate.
* Divided into separate and achievable function based layers/modules
	* Each layer/module is easier to manage and maintain.


![](screenshots/Pasted%20image%2020240731175823.png)

## The open systems Interconnection (OSI) reference model

1. The OSI is proposed by the International organization for standardisation (ISO).
2. it provides a common framework for developers and students of networking to work with and learn from 
	1. It is not specific to any protocol suite and can be applied to most networking protocols
	2. It is well known and acknowledged as a baseline for categorisation of network communication functions and assessment.


# Structure of the OSI model
1. It is seven layer organisation of how data travels from place to place on any given network.
2. Each layer provides services to the next higher layer until data reaches the application layer.
3. Each layer on one computer behaves as though it were communicating with the same layer on the other computer.
4. This is known as peer communication between layers.

![](screenshots/Pasted%20image%2020240731181052.png)

## Encapsulation in Networking

1. At each layer, control information is either added or removed depending on whether the data is leaving or arriving at a computer
2. To add additional control information to a data unit as it moves through the layers is called **encapsulation**. 
3. Encapsulation process take place in the sending computer while the de-encapsulation process takes place in the receiving computer.
4. Protocol information can be added before and after the data. If the information is added before the data, it is known as header and if the information is added after the data is known as trailer.

## Application Layer
1. The Application layer (Layer 7) provides interface for the applications to access network services e.g., file sharing, messages handling and data base access.
2. Common protocols found at layer 7 include Hypertext Transfer Protocol (HTTP), File transfer Protocol (FTP), and simple Mail transfer Protocol (SMTP).
3. The possible problems to occur in this layer are: 
	1. missing or misconfigured client or server software 
	2. incompatible or obsolete commands used to communicate between client and server.

## Presentation Layer

1. The Presentation Layer (Layer 6) handles data formatting and translation.
2. For outgoing messages : converts data into a format specified by the application layer.
3. for incoming messages : Reverse the conversion if required by the receiving application.
4. Encryption/ decryption can be done at this layer.

## Session Layer
1. Session Layer (Layer 5) permits two computers to hold ongoing communications called session
2. This layer handles communication setup ahead of data transfer and session teardown when the session ends.
3. Common network functions at this layer: Name lookup, user logon and logofff.
4. Manages the mechanics of the ongoing conversation such as identifying which side can transmit data when and for how long.

## Transport Layer
1. The transport Layer ( layer 4) manages data transfer from one application to another across the network by breaking down data into smaller chunks called segments.
2. Segmenting data is important because every network technology has a maximum frame size called Maximum transmission unit (MTU)
3. Includes flow control and acknowledgements to ensure reliability
4. Handles re-sequencing segments into original data on receipt.

![](screenshots/Pasted%20image%2020240731182650.png)

![](screenshots/Pasted%20image%2020240731182704.png)

## Network layer
1. The Network Layer (Layer 3) : 
	1. Performs logical addressing
	2. Maps between logical Network addresses (IP address) into physical addresses.
	3. Performs routing (I.e. Select the best path)
2. Protocols related this layer include
	1. Internet Protocol (IP)
	2. address resolution Protocol (ARP)
	3. Internet Control message Protocol (ICMP                                                                                

![](screenshots/Pasted%20image%2020240731183010.png)

Problems that can occur at the Network layer often include the following :
* Incorrect IP addresses or subnet masks
* Incorrect router configuration
* Router operation errors.

## Data Link Layer

* The Data Link Layer (Layer 2) works with frames and is the intermediary between the Network layer and Physical layer.
* Defines how computer access the network medium. 
	*  **Media Access Control (MAC) address** is defined in this layer.
* A layer 2 frame consists of both a header and a trailer
	* Trailer component is labeled "FCS" (Frame Check Sequence) and contains a Cyclic Redundancy Check (CRC) code.
	* A CRC is an error-detecting code commonly used in network communications.
![](screenshots/Pasted%20image%2020240801000323.png)

* The software component operating at this layer is in the network interface card (NIC) driver.
* Hardware components that operate at this layer include NICs and switches
* Problems at this layer include collisions and invalid frames.
	* Can be caused by collisions, poor network design, environmental interference, line noise or NIC driver problems.

## Physical layer
* The Physical Layer (Layer 1) converts bits into signals for outgoing messages and signals into bits for incoming messages.
	* Wire media uses electrical pulses, fiber-optic uses light pulses and wireless media user radio waves.
* Details for **creating a physical network connection** are specified at this layer.
	* e.g. type of connector used to attach the medium to NIC.
* **Encoding** (representing 0s and 1s by a physical signal) happens at this layer.
	* such as electrical voltage or light pulse.
* Components at this layer include all the cables and connectors on the medium, repeaters and hubs
* Problems occurs here are often related to:
	* Incorrect media termination
	* Electromagnetic interference or noise that scrambles the signals 
	* NICs and hubs are misconfigured or malfunctioning.
![](screenshots/Pasted%20image%2020240801001444.png)


# Purposes of network layering  
• It can be clearly divided into separate and achievable function-based modules/layers  
• Each module/layer is easier to manage and control, i.e., one module/layer can be changed without affecting other module/layers  
• It facilitates in protocol implementation and troubleshooting.

# Summary
* The layers of the network communications process can be summarised as user application , network software, network protocol and network interface.
* The four terms used to describe networks of different scope are LAN, Internetwork, WAN and MAN
* Packets and frames are the units of the data handled by the different network components.
	* Packets have the source and destination IP address added and are processed by the network protocol.


# Summary of the OSI model layer function

* Application - provides access to the network resources
* Presentation - handles the data formatting and translation
* Session - manages ongoing conversations between two computers.
* Transport - breaks long data streams into smaller chunks (Segments)
* Network - Provides best path selection and IP Addressing.
* Data Link - Defines how computers access the media.
* Physical - converts bits into signals and defines media and connectors.