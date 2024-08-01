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