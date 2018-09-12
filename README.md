University Questions Consolidated 

Subject : Wireless Technology

Problems 
    • Problems based on the Cell, Channels and Coverage areas. [4]

Explain in detail
    • Advantages and Disadvantages of wireless communication
    • CDMA,TDMA,FDMA
    • CDMA architecture in detail [2]
    • IEEE 802.11 MAC layer with Power Management [2] 
    • IEEE 802.11 WLAN architecture
    • Mobile IP
    • Possible attacks on WLAN and WEP. [3]
    • Bluetooth architecture [3]
    • Bluetooth protocol stack
    • Security in bluetooth
    • Piconet and Scatternet in Bluetooth
• GSM architecture [2]
GSM network architecture consists of different elements that all interact together to form the overall GSM system. These                    include elements like the base-station, controller, MSC, AuC, HLR, VLR, etc.

The GSM technical specifications define the different elements within the GSM network architecture. It defines the different elements and the ways in which they interact to enable the overall system operation to be maintained.
The GSM network architecture is now well established and with the other later cellular systems now established and other new ones being deployed, the basic GSM network architecture has been updated to interface to the network elements required by these systems.
Despite the developments of the newer systems, the basic GSM system architecture has been maintained, and the network elements described below perform the same functions as they did when the original GSM system was launched in the early 1990s.GSM network architecture elements
The GSM network architecture as defined in the GSM specifications can be grouped into four main areas:
  1.Mobile station (MS)
  2.Base-Station Subsystem (BSS)
  3.Network and Switching Subsystem (NSS)
  4.Operation and Support Subsystem (OSS)
  
The different elements of the GSM network operate together and the user is not aware of the different entities within the system.
A basic diagram of the overall GSM system architecture with these four major elements is shown below:
http://microcontrollerslab.com/wp-content/uploads/2015/07/2-GSM-architecture.jpg

Mobile station
Mobile stations (MS), mobile equipment (ME) or as they are most widely known, cell or mobile phones are the section of a GSM cellular network that the user sees and operates. In recent years their size has fallen dramatically while the level of functionality has greatly increased. A further advantage is that the time between charges has significantly increased.
There are a number of elements to the cell phone, although the two main elements are the main hardware and the SIM.
The hardware itself contains the main elements of the mobile phone including the display, case, battery, and the electronics used to generate the signal, and process the data receiver and to be transmitted. It also contains a number known as the International Mobile Equipment Identity (IMEI). This is installed in the phone at manufacture and "cannot" be changed. It is accessed by the network during registration to check whether the equipment has been reported as stolen.
The SIM or Subscriber Identity Module contains the information that provides the identity of the user to the network. It contains are variety of information including a number known as the International Mobile Subscriber Identity (IMSI).

Base Station Subsystem (BSS)
The Base Station Subsystem (BSS) section of the GSM network architecture that is fundamentally associated with communicating with the mobiles on the network. It consists of two elements:

   Base Transceiver Station (BTS):   The BTS used in a GSM network comprises the radio transmitter receivers, and their associated antennas that transmit and receive to directly communicate with the mobiles. The BTS is the defining element for each cell. The BTS communicates with the mobiles and the interface between the two is known as the Um interface with its associated protocols.
   Base Station Controller (BSC):   The BSC forms the next stage back into the GSM network. It controls a group of BTSs, and is often co-located with one of the BTSs in its group. It manages the radio resources and controls items such as handover within the group of BTSs, allocates channels and the like. It communicates with the BTSs over what is termed the Abis interface.

Network Switching Subsystem (NSS)
The GSM system architecture contains a variety of different elements, and is often termed the core network. It provides the main control and interfacing for the whole mobile network. The major elements within the core network include:

   Mobile Services Switching Centre (MSC):   
   The main element within the core network area of the overall GSM network architecture is the Mobile switching Services Centre (MSC). The MSC acts like a normal switching node within a PSTN or ISDN, but also provides additional functionality to enable the requirements of a mobile user to be supported. These include registration, authentication, call location, inter-MSC handovers and call routing to a mobile subscriber. It also provides an interface to the PSTN so that calls can be routed from the mobile network to a phone connected to a landline. Interfaces to other MSCs are provided to enable calls to be made to mobiles on different networks.
    
   Home Location Register (HLR):   
   This database contains all the administrative information about each subscriber along with their last known location. In this way, the GSM network is able to route calls to the relevant base station for the MS. When a user switches on their phone, the phone registers with the network and from this it is possible to determine which BTS it communicates with so that incoming calls can be routed appropriately. Even when the phone is not active (but switched on) it re-registers periodically to ensure that the network (HLR) is aware of its latest position. There is one HLR per network, although it may be distributed across various sub-centres to for operational reasons.
   
   Visitor Location Register (VLR):   
   This contains selected information from the HLR that enables the selected services for the individual subscriber to be provided. The VLR can be implemented as a separate entity, but it is commonly realised as an integral part of the MSC, rather than a separate entity. In this way access is made faster and more convenient.
    
   Equipment Identity Register (EIR):   
   The EIR is the entity that decides whether a given mobile equipment may be allowed onto the network. Each mobile equipment has a number known as the International Mobile Equipment Identity. This number, as mentioned above, is installed in the equipment and is checked by the network during registration. Dependent upon the information held in the EIR, the mobile may be allocated one of three states - allowed onto the network, barred access, or monitored in case its problems.
    
   Authentication Centre (AuC):   
   The AuC is a protected database that contains the secret key also contained in the user's SIM card. It is used for authentication and for ciphering on the radio channel.
    
   Gateway Mobile Switching Centre (GMSC):   
   The GMSC is the point to which a ME terminating call is initially routed, without any knowledge of the MS's location. The GMSC is thus in charge of obtaining the MSRN (Mobile Station Roaming Number) from the HLR based on the MSISDN (Mobile Station ISDN number, the "directory number" of a MS) and routing the call to the correct visited MSC. The "MSC" part of the term GMSC is misleading, since the gateway operation does not require any linking to an MSC.
    
   SMS Gateway (SMS-G):   
   The SMS-G or SMS gateway is the term that is used to collectively describe the two Short Message Services Gateways defined in the GSM standards. The two gateways handle messages directed in different directions. The SMS-GMSC (Short Message Service Gateway Mobile Switching Centre) is for short messages being sent to an ME. The SMS-IWMSC (Short Message Service Inter-Working Mobile Switching Centre) is used for short messages originated with a mobile on that network. The SMS-GMSC role is similar to that of the GMSC, whereas the SMS-IWMSC provides a fixed access point to the Short Message Service Centre.

Operation and Support Subsystem (OSS)
The OSS or operation support subsystem is an element within the overall GSM network architecture that is connected to components of the NSS and the BSC. It is used to control and monitor the overall GSM network and it is also used to control the traffic load of the BSS. It must be noted that as the number of BS increases with the scaling of the subscriber population some of the maintenance tasks are transferred to the BTS, allowing savings in the cost of ownership of the system.
    
    • GSM Privacy and  Authentication
    • EDGE network architecture
    • Factors of change in economics of wireless technology [2]
    • GPRS architecture, Authentication and Encryption [2]
    • Hidden and Exposed terminal problem with solution [2]
    • WLL Architecture and two loop techniques [2]
    • WLL Architecture
    • MMDS and LMDS in WLL
    • Wireless Multiple Access Techniques
    • ZigBee [LR-WPAN] Stack architecture
    • Types of channels in GSM and compare it with CDMA
    • Evolution of the cellular highlighting 1G/2G/3G and 4G

Write Short Note on 
    • FHSS and DSSS with examples [4]
    • OFDMA 
    • OFDM 
    • MMDS
    • WLL architecture
    • Satellite Systems
    • WLAN Architecture
    • WiMAX and 802.16 Standards [3] 
    • Wireless Sensor Network [2]
    • VPN
    • Multiple Access Techniques
    • MACA
    • Handoff Stratergy 
    • Mobile IP [3]
    • Economics of Wireless network
    • Electromagnetic Spectrum
    • Frequency Reuse
    • IEEE 802.11 Standards

Compare 
    • WiMax and LTE/2GPP
    • CSMA 2000 and W-CDMA

