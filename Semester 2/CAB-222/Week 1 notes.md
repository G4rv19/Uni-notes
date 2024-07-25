# <font color="red"> Introduction to Computer Networks </font>
* Internet History
* Network Terminology
* Basic Network Communications
* Network architecture


## Network Control Protocol (NCP)
1. The 1st standard operational packet-switching protocol on ARPANET and standardised the ARPANET network interface.
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
- ARPA adopted TCP/IP as the ARPANET protocol suite in 1982.
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


## Packets
1. Chunks of data sent across the network are usually called packets or frames, with packets being the more well known term.
2. A chunk of data with source and destination IP address to it.


## Frames 

1. A packet with source and destination MAC address added to it.
	1. The packet is "Framed" by the MAC addresses on one end and an error checking code on the other.
2. The process of adding IP address and MAC address to chinkss of data is called encapsulation.
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


