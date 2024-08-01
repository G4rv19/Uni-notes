# <font color="cyan"> Network Media , NIC , Ethernet and Wifi. </font>

## <font color="Green">Outline</font>
* Network Media 
* Network Interface Cards (NICs)
* Wired Network Technology - Ethernet 
* Wireless Network Technology - Wi-Fi

![](screenshots/Pasted%20image%2020240801130549.png)


# <font color="Yellow">Network Media </font>
* 2 major categories of media include:
	* Wired media
	* Wireless media
* 2 Broad categories of cables
	* Copper wire
	* Fiber optic
* The main differences between the 2 types:
	* Composition of signals (electricity or light)
	* Speed at which signals can be sent
	* Distance the signals can effectively travel.


###  <font color="Orange">Criteria for choosing Network media</font>
* Bandwidth
* Distance
* Interference
* Ease of Installation
* Total Cost
* Mobility
* Security


#### **Network Bandwidth (data transfer rate)**
1. The amount of data that can be carried from one point to another for a given time period (usually a second)
2. Expressed in bits per sec (BPS)
3. Speeds can be measured in the millions of bits per second (megabits per sec or mbps) or billions of bits per second (gigabits per sec, or gbps)
4. MB/s and GB/s are not the similar terms to above ones.
5. 1 MBPS = 0.125 Mb/s
6. 100 MBPS = 12.5 MB/s
7. 1 GBPS = 125 Mb/s

#### Distance
1. Maximum segment Length
	1. Maximum length of cables between two network devices is called cable segment
2. Each cable type can transport data only so far before its signals begin to weaken called Attenuation.

#### Interference 
1. Physical Objects
	1. The density of the objects
	2. Concrete/ steel walls are difficult for a signal to pass through
2. Radio Frequency interference
	1. 802.11b/g use a RF range of 2.4GHz
	2. Devices that share the channel can cause noise and weaken the signals.
3. Environmental Interference 
	1. Computers, refrigerators, fans, lighting fixtures, or any other motorised devices. 
4. Electronical  Interference 
	1. Interference to electrical signals on copper media comes in the form of electromagnetic interference(EMI) and radio frequency interference (RFI)
	2. Motors , transformers , fluorescent lights and other sources of intense electrical activity can emit both EMI and RFI.
5. Weather Conditions
	1. on wireless signal integrity e.g. Lightning , fog.

#### Security
* Copper wire is susceptible to electronic eavesdropping
* Fiber-Optic media carries light signals and is not susceptible to interference or eaves dropping.


## Types of Cables

### Coaxial Cable
* Often called Coax
* It was once the predominant form of network cabling
* Inexpensive and easy to install
* Started its phase out in early 1990s
* still it is used in connecting a cable modem to the wall outlet ur cable tv or internet providers installs.

## Twisted- Pair Cables

### There are 2 types of twisted pair cables
1. Unshielded twisted pain (UTP)
2. Shielded Twisted pair (STP)

## Twisted pair cables
* It is classified by category
	* Twisted pair is currently category 1 through category 8, although categories 1, 2 and 4 are nearly obsolete.
	* Categories 5e, 6 and 7 UTP cabling are the most popular types of UTP cabling in today network.
	* Twists are necessary to improve resistance to crosstalk from wires and emi from outside.
	* Shielding can further help eliminate interference.


## Shielded Twisted pair cables
* Includes shielding to reduce crosstalk and interference
	*  Has a wire braid inside the sheath material or foil wrap
	* Best to use in electrically noisy environments or very high bandwidth applications.

### Twisted pair cable Plant components
* RJ-45 Connectors - STP and UTP uses registered Jack 45 
	* most used in patch cables, which are used to connect to hubs , switches and RJ-45 wall jack.


## Straight Through vs Crossover Cables
* Standard patch cables are called Straight Through cables 
* Crossover cables -
	* Use 568A standard on one side of the cable and 568B standard on the other side.
	* Crosses the transmit and receive wires so that transmit on one end connects to receive on the other.
	* This type of cable is often needed when u connect two devices of the same type to one another.

## DO we still need a crossover cable?
* Nowadays the need for crossover cables has been eliminated with the latest technology,.
* G/Ethernet comes with automatic medium dependent interface crossover (Auto-MDIX)
* this technology detects whether u need a crossover cabe or a straight through cable and it automatically configures the network interface card acc.
* yet, we still need to use crossover cables to connect two devices of the same type.

## Summary of Twisted pair
* Most common form of wire
* comes in shielded and unshielded forms
* Relatively inexpensive
* easy to install
* carries high data rates but not the highest
* can suffer from electromagnetic noise
* Can be easily wire tapped.

# Fiber Optic Cable
*  A slender cylinder of glass fiber called the core is surrounded by a concentric layer of glass called the cladding.
* Fiber is then jacketed in a thin transparent plastic material called the buffer.
* Bits are transmitted as pulses of light instead of electricity. Information is sent in a beam of light bouncing down a glass or plastic pipe.
* High data capacity
* Immune to electrical interference
* Less attenuation 
	* it can carry signals over a much longer distance without a repeated compared to copper.
* Security
	* Difficult for eavesdropping.
* Installation Cost
	* More difficult and time consuming than copper media installation
	* Connectors and test equipment required for termination are still more expensive than copper.
* Wildlife damage to fiber-optic cables
	* Birds peck at the fiber cable jackets to use bits of nesting material
	* Beavers and mice use exposed fiber cable to sharpen their teeth
	* Ants like to eat plastic shielding
	* Sharks have been known to damage fiber cabling when laid underwater.

## Fiber optic cable types

* Single mode fiber 
	* Includes a single, small diameter fiber at the core (8 microns)
	* Generally uses laser light source
	* Spans the longest distances
	* Used in higher bandwidth applications
* Multimode Fiber (MMF)
	* Larger diameter fiber at the core ( 50 and 62.5 microns)
	* costs less than SMF
	* Use LED for light source
	* Spans shorter distances.
# Summary for Fiber Optic
* Fiber optic cable can carry the highest data rate for longest distances.
* Initial cost wise is more expensive than twisted pair and coaxial.
* But when u consider the superiority of fiber, initial costs outweighed by capacities.
* Not affected by electromagnetic noise
* Cannot be easily wiretapped.

# Serial Communications
* A serial link is a point to point link between two devices.
* Bits are transmitted sequentially over a single channel
* Parallel in theory faster than serial however suffers problems with synchronisation and higher cost.
* Original serial standard RS-232 was introduced in the 1960s Now mostly replaced by USB.

# DTE vs DCE devices
Devices that communicate over a serial interface are divided into:
* Data terminal Equipment (DTE)
	* An end instrument that converts user information into signals or reconverts received signals 
* Data Communication Equipment (DCE)
	* Typically a modem or other piece if data communications equipments.
* When connecting two DTE (such as two router in the lab) devices together without modem, you require a special type of cable called Null modem.
* Generally DCE devices provide that clock rate and the DTE device synchronises on the provided clock rate.

# Wireless Benefits
* Creates temporary connections to weird networks
* Establishes backup or contingency connectivity for existing wired networks
* Extends a network's span beyond the reach of wire based or fiber optic cabling, especially in older buildings where rewriting might be too expensive.
* Allow businesses to provide customers with wireless networking easily offering a service that gets customers in and keeps them there.
* Enables users to roam around a corporate or college campus with their machines.

## Wireless Lan components
* Network interface attaches to an antenna and an emitter rather than to a cable.
* The heart of a wireless network is the wireless access point (AP)
	* Includes an antenna and a transmitter to send and receive wireless traffic but also connects to the wired side of the network
	* Shuttles traffic back and forth between a network's wired and wireless sides
	* most small business and home networks use a device typically called a wireless router that combines the functions of an AP, a switch and a router.
	* Wireless LANs are usually attached to wired networks

## Wireless vs Wired Networking

* Speed
	* Wired ethernet is faster than wireless than WiFi. Wifi is becoming faster over recent years
* Stability 
	* Wireless is susceptible to environmental factors 
		* Radio waves can be blocked by walls and floors
		* can interfere with microwaves, cordless phones
* Mobility installation and convenience
	* Eg. connecting to speakers, Wifi appliances
* Security
	* Wireless transmission can be intercepted more easier than wired transmission.

## NIC : Network interface cards 
* Attaching a computer to a network requires a NIC to create and meditate the connection between a computer and the networking medium.
* A NIC can be 
	* Built into motherboard
	* a separate adapter card that slides into one of the motherboard expansion slots

## NICs and MAC addresses
* MAC address is unique and stored in ROM on the NIC.
* 48 bit address expressed in 12 Hexadecimal digits
* Two 24 bit hexadecimal numbers
	* 24 bits are referred as the manufacturer ID (OUI)
	* the last 24 bits are the device's unique serial number, assigned to the device by the manufacturer.
* The broadcast address is ff-ff-ff-ff-ff-ff.

# Wireless NICs 
* Wireless NICs must be chosen according to type of wireless AP being used.
* Typical are 802.11ac, 802.11ax, 802.11ax-2021 or 802.11 a/b/g/n.
	* the letter a,b,g,n,ac,ax refer to the wireless networking standard the device supports
* Wireless NICs connect to network using service set identifier (SSID)
	* SSID is the name assigned to the wireless network
* You may also need to enter a security key or a username and password depending on the network's security configuration.

# NIC functions
Incoming messages :
* Receives bit signals and assembles them into frames \
* verifies the destination address
	*  If the desitnation mac address = its own MAc address or broadcast address
* Removes frame header and sends the resulting packet to the network protocol

Outgoing messages:
* Receives packets from the network kayer
* Creates frames by adding MAC address / error check
* Converts frame into bit signals suitable for the medium and transmits them


# Ethernet 

* Ethernet is used in local area networks, Metropolitan area network and wide are networks
* Introduced in 1980 and standardized in 1983 as IEEE 802.3
* Ethernet had replaced wired LAN tech and WAN technologies
* The protocol has evolved and improved over time to transfer data. The system now has three main speeds:
* 10Mbps, 100 Mbps, 1000 Mbps 
* Ethernet can support a broad range of speeds : 10 Mbps to 10Gbps
* Most NICs/ switches can operate at multiple speeds

## Ethernet Media access
* Media access method
	* Rules governing how and when the medium can be accessed for transmission
* Ethernet uses Carrier sense Multiple Access with collision detection (CSMA/ CD)
* Carrier sense : listen before send- must hear silence
* Multiple Access : If two or more stations hear silence, multiple stations may transmit at the same time.
* Collision detection : if two or more stations transmit,a collision occurs and is detected by the NIC and all the stations must retransmit.


### Ethernet Error Handling
- **Best-effort delivery**: No acknowledgement of frame delivery.
  - **Collisions**: Automatically retransmitted.
  - **Damage detection**: Frames checked using Cyclic Redundancy Check (CRC).
  - **Damaged frames**: Discarded without notification.

### Ethernet Addressing
- **MAC Address**: 48-bit physical address (12 hex digits).
- **Frame processing**: Must match NIC’s address or broadcast address (FF-FF-FF-FF-FF-FF).
- **Post-NIC processing**: Frames sent to network protocol.

### Ethernet Frames
- **Formats**: Four types based on network protocol.
- **Ethernet II**: Used by TCP/IP (dominant LAN protocol).
- **Frame size**: 64 to 1518 bytes.
  - **Components**: Destination MAC, Source MAC, Type, Data, FCS.

### Ethernet Standards
- **Naming convention**: XBaseY (e.g., 10BaseT, 100BaseTX).
  - **X**: Transmission speed.
  - **Y**: Media type (T = twisted-pair, FX = fiber optic).

#### Specific Standards:
- **10BaseT** (Obsolete):
  - **Media**: Category 3+ UTP.
  - **Pairs used**: 2 of 4.
- **100BaseTX**:
  - **Media**: Category 5+ UTP.
  - **Pairs used**: 2 of 4.
  - **Hubs**: Interconnected by switches.
- **100BaseFX**:
  - **Media**: Fiber optic.
  - **Usage**: Backbone cabling, secure client/server connections.
- **1000BaseT** ("Gigabit Ethernet"):
  - **Media**: Category 5+ UTP.
  - **Pairs used**: All 4.
- **10GBaseT**:
  - **Media**: Category 6A/7 UTP.
  - **Mode**: Full-duplex.
  - **Usage**: Network servers.

### Additional Ethernet Standards
- **100BaseT4** (Obsolete): Uses all four pairs in UTP Category 3.
- **1000BaseLX**:
  - **Media**: Fiber-optic.
  - **Laser**: Long wavelength.
  - **Max distance**: 5000 meters.
- **1000BaseSX**:
  - **Media**: Fiber-optic.
  - **Laser**: Short wavelength.
- **1000BaseCX**:
  - **Media**: Specially shielded copper ("twinax" cables).
- **10 Gigabit Ethernet (IEEE 802.3ae)**:
  - **Media**: Fiber-optic.
  - **Max distance**: 40 km.
  - **Varieties**: 10GBaseSR, 10GBaseLR, 10GBaseER, etc.
- **40/100 Gigabit Ethernet**:
  - **Media**: Primarily fiber-optic.
  - **Copper**: Special assemblies for short distances.

### Overview
- **802.11 Wi-Fi**: Also known as Wireless Fidelity (Wi-Fi).
- **Hotspots**: Public Wi-Fi networks.
- **Medium**: Airwaves instead of cables; extension of Ethernet.

### Wi-Fi Modes of Operation
- **Infrastructure Mode**: Uses a central access point (AP).
- **Ad Hoc Mode**:
  - No central device.
  - Data travels directly between devices (peer-to-peer).

### Wi-Fi Channels and Frequencies
- **Frequencies**:
  - **2.4 GHz**: 2.412-2.484 GHz, 14 channels, 5 MHz apart.
  - **5.0 GHz**: 4.915-5.825 GHz, 42 channels, various bandwidths (10, 20, 40, 80, 160 MHz).

### IEEE 802.11 Wi-Fi Standards
- **Wi-Fi 6e (802.11ax-2021)**: 600–9608 Mbit/s, 2021, 2.4/5/6 GHz.
- **Wi-Fi 6 (802.11ax)**: 600–9608 Mbit/s, 2019, 2.4/5 GHz.
- **Wi-Fi 5 (802.11ac)**: 433–3460 Mbit/s, 2014, 5 GHz.
- **Wi-Fi 4 (802.11n)**: 72–600 Mbit/s, 2009, 2.4/5 GHz.
- **Wi-Fi 3 (802.11g)**: 3–54 Mbit/s, 2003, 2.4 GHz.
- **Wi-Fi 2 (802.11a)**: 1.5 to 54 Mbit/s, 1999, 5 GHz.
- **Wi-Fi 1 (802.11b)**: 1 to 11 Mbit/s, 1999, 2.4 GHz.

### 2.4 GHz vs. 5 GHz
- **2.4 GHz**:
  - **Advantages**: Larger coverage, better penetration through solid objects.
  - **Disadvantages**: Lower data rate, more interference, more devices using it.
- **5 GHz**:
  - **Advantages**: Higher data rate, less interference, fewer devices.
  - **Disadvantages**: Smaller coverage, less penetration through solid objects.

### Wi-Fi Access Methods and Operation
- **Access Method**: 
  - **CSMA/CA**: Carrier sense multiple access with collision avoidance.
  - **RTS/CTS**: Optional use of request-to-send/clear-to-send packets for collision avoidance.

### CSMA/CA Protocol Steps
1. **Check Media**: Sender checks if the media is free.
2. **RTS Packet**: Optionally, sender sends RTS packet to AP.
3. **CTS Packet**: AP replies with CTS packet.
4. **Transmission**: Sender transmits while monitoring for other RTS signals.
5. **Collision Handling**: If a collision is detected, sender retries after a random delay.

### Wi-Fi Security
- **Range**: Wi-Fi signals can travel several hundred feet, detectable by outside devices.
- **Encryption Protocols**: Protect network data.
  - **Types**: WEP, WPA, WPA2, WPA3.
  - **Device Compatibility**: Not all devices support all protocols; older devices may only support WEP/WPA.
