#                STUDY NOTES

## Comptia Troublshoot methodology
1. Identify Problem
2. Establish a Therory of cause
3. Test therory to determine cause
4. Establish a plan of action to resolve.
5. Implement solution
6. Verify system functionality
7. Document findings/actions
## Type of Cloud Models
- **Community Cloud** = a collaborative effort in which infrastructure is hared between several organizations, its a hybrid form of a private cloud.
- **Public Cloud** = contains services by 3rd party over public internet/available to whoever wants to purchase or use.
- **Private CLoud** = Contains services offered over the internet or a private internal network, only to select users instead of the general public.
- **Hybrid Cloud** = Uses a mix of on-premise, private cloud, and 3rd party public cloud services w/ orchestration between platforms, usually involves a connection from an on-premise data cetner to a public cloud.
## Approved Emergency Change Management Process
1. Make the change
2. Document the requester
3. Document all network changes
## System Administrator wants us to verify external ip addresses can't collect software versoning from servers on the network
- we should analyze our packet captures, wireshark can show us the info about a packet.
## Wi-Fi Protected (WPS) 
( WPS ) - allows user to configure a wireless network w/o typing in a passphrase, users can configure by pressing buttons or by entering a short pin
- **evil twin attack** = would not allow the tehcnician to log into the admin area of the device to see the connected devices.
- **ARP Poisnioning** = consists of abusing the weaknesses in the ARP to corrupt the MAP to IP mapping of other devices on the network, this would not affect the humber of devices connected to the AP, though, only the switching of their traffic once they connect.
- **botnet** = is a collection of internet-connected devices infected by malware that allow hackers to control them. 
    - There is no evidence that the users laptop or smartphone are infected w/ malware, even if one was infected , its unlikely they both would be infected with the same malware since laptops and smartphones run different operating systems.
## RSSI Issues
- received signal strength indication ( RSSI ) is an estimated measure of the power level that a radio frequency client device is receiving from a wireless access point. If the RSSI is -90 to -100 dB, this indicates an extremely weak connection and insufficient wireless coverage in which the area the device is operating

## SSID
- Service Set Identifier ( SSID ) is a natural language name used to identify a wireless network. Manually configuring a wireless network and incorrect SSID is entered, the device will be unable to connect to the network
## Encryption Protocols
- Are used to protect WEP. WPA. and WPA2 wireless networks. 
- **WEP** wireless networks utilizes the RC4 encripytion protocol.
- **WPA** wireless networks utilize the TKIP encryption protocol.
- **WPA2** wireless network utlizies the AES encryption protocol, but they can also support the TKIP encryption.
- If the wrong encryption protocol is used, the wireless client and the wireless ap will be unable to communicate
## Passphrase
- passphrase in a wireless network serves as the password or network security key. If the incorrect passphrase was entered, you will receive an error such as " Network security key mismatch" and the wireless device will be unable to communicate w/ wireless AP's.

## Parabolic antennas
- 5 dB will not be sufficent for an outdoor wireless conection over the distance presented in this scenaro, which was an entire building.
## Bare-metal virtualization Environment
- The bottom layer is a phyiscal hardware in this environment. Its what sits beneath the hypervisor and controls access to guest operating systems. The bare-metal approach doesn't have a host operating system. 
- A **hypervisor** is a program used to run and manage one or more virtual machines on a computer. A hosting operatoring system is an operating system that is running the hipervisor. A host operating system is an operating system that is running the hypervisor.
## Microwave Radio Links
- Microwave radio links require a direct line of sight (LoS) between the antennas to maintain a strong and effective link. These line-of-sight microwave link uses highly directional transmitter and receiver antennas to communicate via a narrowly focused radio beam.
- **Latency** = is the time delay between a packet is sent and received. While latency will increase with an obstructed microwave line of sight link, latency is an effect of this issue and not the cause of the issue.(which is interference)
- **Throttling** = is the intentional slowing or speeding of an internet service by an ISP to regulate network traffic and minimize bandwidth congestion.
- **Split-Horizon** = is a form of route advertisement that prohibits a router from advertising back a route to the same interface from which it learned it. This does not affect the issues experienced w/ a microwave line. 
    - Throttling slows down the speed, latency slows down the speed  even further, split horizon prevents loops, so interference can cause drops in connections in many situations.
## Misconfigured Devices
- A **firewall** = is an integral part of creating a screened subnet, if configured correctly, it can regulate exactly what traffic and users are allowed to access the server. This is different from a ccontent filter because a content filter denies traffic to a user based on content, but not access to a server. If the firewall ruleset was not configured to allow external users to access the application remotely, the default condition is to "deny by default". 
- **Content Filtering** = is the use of a program to screen and/or exclude access to web pages or emails demmed objectionable. 
- **DHCP** = uses port 67 and is a network management protocol used on Internet Protocol ( IP ) networks for automatically assigning IP addresses and other communication parameters to devices connected to the network using a client-server architecture.
- **DNS** = uses port 53, is a hierarchical and decentralized naming system for computers,services, or other resources connected to the internet or a private network.

## POTS Line
- POTS, plain old telephone service
- An analog modem is a device that converts the computer's digital pulses to tones that can be carried over analog telephone lines and vice versa. 
- DSL is the other type of Internet connection that uses an RJ-11 connection to a phone line. 
- A DOCSIS modem is a cable modem and would require a coaxial cable with an F-type connector. 
An access point is a wireless device that connects to an existing network using twisted pair copper cables and an RJ-45 connector. 
- A multilayer switch can use either twisted pair copper cables using an RJ-45 connector or a fiber optic cable using an MTRJ, ST, SC, or LC connector.
## WAN Circuit
- The WAN interface is currently untagged and is being assigned to the default VLAN (VLAN 1). If there are numerous devices in the default VLAN, the VLAN may be overloaded or oversubscribed leading to a reduction in the network performance. To solve this issue, you would assign the WAN interface to a VLAN w/ less traffic or to its own VLAN. By adding an
- 802.1q tag (VLAN Tag) to the interface, you can assign it to its own individual VLAN and eliminate potential overloading or oversubscription issues. 
- The interface is already set to full duplex ( fdx) and is operating in full-duplex ( fdx), therefore, the issue is not a duplexing mismatch.
- The configuration shows the interface is already using a GigabitEthernet, so you dont need to replace the transceiver w/ a 1000Base-T module, also the phyiscaly layer is working properly and a link is established shown by the output "gigabitethernet 1/1 is up, showing the current transceiver is functioning properly at 1Gbps.
- While issuing the shutdown command and then re-enabling the interface could clear any errors, based on the interface status show we have no idications that errors are being detected or reported.
## Media Converter
- a media converter is a layer 1 device that changes one type of physical network connection to another. In this case, we are converting signle-mode fiber (SMF) cable to Cat6a ( ethernet) cable.
## Security Appliances into 1 Device
- **UTM** = Unified Threat Management, appliance enforces a variety of security-related measures, combining the work of a firewall, malware scanner, and intrusion dectection/prevention. A UTM centralizes the threat management service, providing simpler configuration and reporting than isolated applications spread across several servers or devices.
- **IDS** = Intrusion Dection System, is a device or software application that monitors a network or system for malicious activy or policy violations. Any malicious activity or violation is typically reported to an administrator or collected centrally using a security information and event management system. IDS can only log these issues and not stop them 
- **IPS** = Instrusion prevenetion system (IPS) conducts the same functions as an IDS but can also block or take actions against malicious events. 
- **Syslog** = is a server that collects diagnostic and monitoring datafrom the hosts and network devices across a given network.
## Wireless Technologies
- Modulation is a process of varying one or more properties of a periodic waveform, called the carrier signal, w/ a separate signal called the modulation signal that typically contains information to be transmitted. WiFi can use different digital modulation schemes for data transmission. Common types of modulation include 
- **OFDM** = Orthogonal frequency-division multiplexing
- **QAM** = Quadrature Amplitude Modulation
- **PSK** = Quadrature Phase-shift keying.
- Frequency is the number of occurrences of a repeating event per unit of time. Wireless networks utilize three different frequency bands: 2.4 GHz, 5 GHz, and 6 GHz. 
- Interference occurs when t wo radios are transmitting or receving on the same frequencies. 
- Spectrum refers to the range of frequencies used by a radio transmitter or receiver, such as the 2.4GHz spectrum which includes frequencies from 2.412 GHz to 2.472 GHz in the U.S.

## SNMP data transferred Confidentially
- In SNMPv3, the authPriv option ensures that communications are sent w/ authentication and privacy. This uses MD5 and SHA for authentication and DES and AES for privacy/encryption.
## Serverr Mitigation Risk
- Since the vendor stated that the new version introduced vulnerabilities in the environment, its best to downgrade the server to the older and more secure version until a patch is available.
## Password Attacks
- **Dictionary** attack is a method of breaking into a password-protected computer, network, or other IT resource by systematically entering every word in a dictionary or list file.
- **Brute-force** attacks consists of an attack submitting every possible combination for a password or pin until they crack it.
- **Password spraying** attack that attempts to access a large number of accounts (usernames) w/ a few commonly used passwords.
- **hybrid** attack merges a dictionary attack and a brute-force attack, but provides keywords from a list to use during the brute-force attack modifying the suffixes and prefixes.
## VLAN Connectivity
If the switchport is configured for 802.1q trunking instead of as an access host port, the workstation will be unable to reach the DHCP server through the port and will fall back to using an APIPA address. APIPA is not configured on the VLAN’s switch, it is configured by default on client and server devices, such as the workstation in this scenario. A small form-factor pluggable (SFP) transceiver is used on routers as a hot-pluggable network interface module, they are not used in workstations. The workstation’s OS update status is unlikely to cause the network connectivity issue, but a network interface driver might. Therefore, the most likely cause of this issue is the switchport was configured as a trunking port instead of an access port.
## Policies and Plans
- (BYOD) bring your own device polcy allows, and sometimes encourages, emplyoees to access enterprise networks and systems using personal mobile devices, such as smartphones, tablets, and laptops.
- A remote access policy is a document that outlines and defines acceptable methods of remotely connecting to the internal network.
- password policy is a set of rules created to improve computer security by motivating users to create dependable, secure passwords, and then store and utilize them properly. This codument promotes strong passwords by specifying a minimum password length, complexity requirements, requiring periodic password cahnges, and placing limits on the reuse of passwords.
- Onboarding policy = a documented policy that describes all the requirements for integrating a new employee into the company and its cultures, as well as getting that new hire all the tools and information they need to begin their job successfully.
## Common Malicious individuals to perform on-path attack
- an evil twin is the most common way to perform an on-path attack on a wireless network. An evil twin is a rogue wireless access point that masquerades as a legitimate Wi-Fi access point so that an attacker can gather personal or corporate information w/o user's knowledge. A man-in-the-middle or on-path attack consists of sitting between the connection of two parties and either observing or manipulating traffic. This could be through interfering w/ legitimate networks or creating fake networks that the attacker controls.
- ARP spoofing, session hijacking and amplified DNS attacks are not techniques specific to attacking wireless networks.
## Network Protocols/ Commands
- Route = command is used to create, view, or modify manual entries in the network routing tables of a computer or server.
- IP = command is a suite of tools used for performing network administration tasks, such as displaying the current TCP/IP network configuration, refreshing the DHCP and DNS settings, assigning an IP address, and configuring TCP/IP settings for a given interface.
- nslookup = command is used to query the domain name system (DNS) to obtain information about host addresses, mail exchanges, name servers , and related information. nslookup has an interactive and non-interactive mode
- tracert = command is used on windows devices to show details about the path that a packet takes from a host to a target and displays information about each hop in the path.

## AAA on RADIUS
- AAA through RADIUS uses a server secret key ( a shared secret key). a secret key mismatch could cause login problems. a shared secret is a text string that serves as a password between hosts.
## Classless Subnets using VLSM
- in classless subnets using variable length subnet masks (VLSM), the network ID is the first IP address associated within an assigned range. In t his example, the CIDR notation is /30, so each subnet will contain 4 IP addresses. Since the IP address provided is 77.81.12.14/30, the network ID is 77.81.12.12/30, the first router is 77.81.12.13/30, the second router is 77.81.12.14/30, and the broadcast address is 77.81.12.15/30.
## Cloud resources asap
- Rapid elasticity allows uers to automatically request additional space in the cloud or other types of services. Because of the setup of cloud computing services, provisioning can be seamless for the client or user. Providers still need to allocate and de-allocate resources that are often irrelevant on the client or user's side. This feature allows a service to be scaled up w/o purchasing, installing, and configuring new hardware, unlike if you had to install more physical storage into a server or datacenter.
- Resource pooling = refers to the concept that allows a virtual environment to allocate memory and processing capacity for a VMs use.
- Metered Services = are pre-paid, a la-carte, pay-per-use, or commited offerings. A metered services like a database may charge its users based on the actual usage of the service resources on an hourly or monthly basis. For example, Dion training used the AWS lambda serverless product in some of our automation, this servicce charges us .20 cents for every 1 million requests processed.
- Measured Service = a term that IT proffessionals apply to cloud computing that references services where the cloud provider measures or monitors the provision of services for various reasons, including billing, effective use of resources, or overall predictive planning.
## WPA WPA2 WEP
- Since there was no authentication server 
- WPA personal is the most secure choice, if there was WPA2 personal were an option, it would be even more secure.
- WPA2 Enterprise requires RADIUS authentication server to be used w/ individual usernames and passwords for each client.
- MAC filter does not use a password or preshared key.
- WEP uses pre-shared key to secure a wireless network, but WPA uses a stronger encryption standard than WEP.
## Maximum amount of data measured in time an organization is willing to lose during an outage?
- RPO , recovery point objective = is the interval of time that might pass during a disruption before the quantity of data lost during that period exceeds the Business Continuity Plans maximum allowable threshold or tolerance.
- RTO , recovery time objective = the duration of time and a service level within which a business process must be restored after a disaster to avoid unacceptable consequences associated with a break in continuity.
- MTTR , mean time to repair = measures the average time it takes to repair a network device when it breaks
- MTBF , mean time between failures = measures the average time between when failures occur on a device.
## Best Options to configure the thermostat to use WPA2 encryption
- Using WPA2 encryption standard (if supported) and place any internet of things (loT) devices into a DMZ/screened subnet to segregate them from the production network. While enabling two-factor authentication on the devices website is a good practice, it will not increase the loT devices security. While disabling the wireless connectivity to the thermostat will ensure it cannot be hacked, it also will make the device ineffective for the customers normal operational needs. 
- WEP is considered a weak encyption scheme, so you should use WPA2 over WEP whenever possible. Finally, upgrading the wireless access points fireware is good for security, but it isnt specific to the loT devices secruity. Therefore, it is not one of the two best options.
## Jumbo Frames
- Jumbo frames are Ethernet frames whose MTU is greater than 1500. to increase performance, yopu should use jumbo frames only when you have a dedicated network or VLAN, and you can fongiure an MTU of 9000 on all equipment, bnecase of this, jumbo frames are most commonly used in a storage area network ( SAN).
## Network ID
- In classless subnets using variable-lnegth subnet mask (VLSM), the network ID is the first IP address associated within a assigned range. In this example, the CIDR notation is /29, so each subnet will contain 8 IP addresses, since the IP address provided is 192.168.0.123, it will be in the 192.168.0.120/29 network.
Formula = Number of IP addresses = 2^(32 - CIDR Prefix Length)
## Layer 2 address first connected switchport
- Port Security, also known as persistent MAC learning or Sticky MAC, is a security feature that enables an interface to retain dynamically learned MAC addresses when the switch is restarted or if the interface goes down and is brought back online. This security feature that can be used to prevent someone from unplugging their office computer and connecting their laptop to the network jack w/o permission since the switch port connected to the network jack would only allow the computer w/ the original MAC address to gain connectivity.
## Topologies
- a **hybrid topology** is a kind of network topology that is a combination of two or mor enetwork topologies, such as amesh, bus, and ring topology. 
A **star topology** is a network topology where each individual piece of a network is attached to a central node, such as a switch.
- A **bus topology** is a network topology in which nodes are directly connected to a common network media, such as a coaxial cable, known as the bus.
- a **ring topology** is a network topology in which each node connects to exactly two other nodes, forming a single continuous pathway for singals through each node to form a circular ring
- The WAN connections are using a ring network topology, but each office is using a star topology, therefore, the best description of this combined netowrk is a hybrid.
# Wireless Frequencies 
- **802.11g** = ( Wireless G) standard utilizes a 2.4 GHz frequency to provide wireless networking at speeds up to 54mbps.
- **802.11a** = ( Wireless A) standard utilizes a 5 GHz frequency to provide wireless networking at speeds up to 54 Mbps.
- **802.11b** = ( Wireless B) standard utilizes a 2.4GHz frequency to provide wireless networking at speeds up to 11 Mbps.
- **802.11n** ( Wireless N) standard utilizes a 2.4 GHz frequency to provide wireless networking at speeds up to 108 Mbps or a 5.0 GHz frequency to provide wireless networking at speeds up to 600 Mbps. Wireless N supports the use of multiple-input-mulitple-output ( MIMO) technology to use multiple antennas to transmit and receive data at higher speeds. Wireless N supports channel bodning by combing two 20 MHz channels into a single 40 MHz channel to provide additional bandwidth,
- **802.11ac** = ( Wireless AC or Wi-Fi 5) standard utilizes a 5 GHz frequency to provide wireless networking at theoretical speeds up to 3.5Gbps. Wireless AC uses channel bonding to create a single channel of up to 160 MHz to provide additional bandwidth. Wireless AC uses multi-user multipkl-input-multple-output (MU-MIMO) technology to use multiple antennas to transmit and receive data at higher sppeds.

- **802.11ax** ( Wireless AX or Wi-Fi 6) standard utilizes 2.4 Ghz and 5.0 Ghz frequencies to provide wireless networking at theoretical speeds up to 9.6 Gbps. Wireless AX uses orthognal  frequency-division multiple access (OFDMA) to conduct multiplexing of the frequencies transmitted and received to each client to provide additional bandwidth. Wireless AX uses channel bonding to create a single cahnnel of up to 160 MHz to provide additional bandwitdh. Wireless AX uses multi-user multiple-input-mulitple-output (MU-MIMO) technology to use multiple antennas to transmit and receive data at higher speeds. Wireless AX also has a version called Wi-Fi 6E to supports the 6GHz frequency instead of the 2.4 GHz and 5.0 GHz frequencies used in Wi-Fi 6.
## OSI De/encapulsation
- Data encapsulation and de-encapsulation in a computer network is a necessary process. De-encapsulation in networking is performed at the receiver side or destination side as data moves from layer 1 to layer 7 of the OSI model. As information travels up the layers of the OSI layer, information added from the sender’s encapsulation process is removed layer by layer. Data encapsulation, on the other hand, is performed at the sender side while the data packet is transmitted from source host to destination host. This is a process through which information is added to the data as it moved from layer 7 to layer 1 of the OSI model before the data is sent over the network to the receiver. 
- Tagging is used in 802.1q to identify ethernet traffic as part of a specific VLAN. This occurs at Layer 2 of the OSI model and remains at Layer 2 of the OSI model. 
- Tunneling is the process by which VPN packets reach their intended destination. This normally occurs using the IPsec or TLS protocols and occurs at Layer 2 of the OSI model.
## Patch Testing
- Patches should always be tested first, once successfully tested, deployment to the production environment can then be accomplished.
## Debugging Conditions
- The severity levels range from zero to seven, w/ zero being the most severe and seven being the least severe. Level 0 is used for an emergency and is considered the most severe condition bevause the system has become unstable. 
- **Level 1** is used for an alert condition and means that there is a condition that should be corrected immediately.
- **Level 2** is used for a critical condition, and it means that there is a failure in the systems primary application and it requires immediate attention.
- **Level 3** is used for an error condition, and it means that something is happening to the system that is preventing the proper function.
- **Level 4** is used for warning conditions and it may indicate that an error will occur if action is not taken soon.
- **Level 5** is used for notice conditions and itm eans that the events are unusual, but they are not error conditions.
- **Level 6** is used for information conditions and it is a normal operational message that requires no action.

- **Level 7** is used for debugging conditions and is just information that is useful to developers as they are debugging their networks and applications.
## Internet Protocol
- **Private IP** = an IP address reserved for internal use behind a router or other network address translation ( NAT) devices, apart from the public. Private IP addresses provide an entirely separate set of addresses that still allow access to a network w/o taking up a public IP address space.
- **APIPA** , Automatic Private IP Addressing = is a feature in operating systems (such as windows) that enables computers to automatically self-configure an IP address and subnet mask when their DHCP server isnt reachable.
- **Classless IP** = addressing solutions allow for the use of subnets that are samller than the classful subnets associated w/ Class A, Class B, Class C networks.
- **Teredo** = is a transition technology that gives full IPv6 connectibity for IPv6-capable hosts that are on the IPv4 Internet but have no native connection to an IPv6 network.
## Network tool Commands
- **telnet** = command is used to open a command-line interface on a remote computer or server. Telnet operates in plain text mode and should never be used over an untrusted or public network, while it would be better for Scott to use SSH for security reasons, telnet is still the best answer based on the options presented in this question.
- **Nmap**, or Network Mapper, is a cross-platform, open-source tool used to scan IP addresses and ports on a target network, and to detect running services, applications, or operating systems on that networks clients, servers, and devices.
- **TFTP**, Trivial file transfer protcool = serer is used to send or receive files over a TCP/IP network. TFTP servers are commonly used to transfer firmware images and configuration files to network appliances like routers, switches, firewalls, and VoIP devices.
- **IP** = command is a suite of tools used for performing network administration tasks, such as displaying the current TCP/IP network configuration, refreshing the DHCP and DNS Settings, assigning an IP address, and configuring TCP/IP settings for a given interface.
## Future prevention issues
- to prevent the service pack issues, make sure to validate them in a test/lab environemnt first before going ahead and applying a new service pack in your production environment. While using an automated patching server is a good idea, no patches should be deplyed before being tested in a lab first.
## Windows-Based Network
- **NetBIOS** = stores a local cached name table in the LMHOSTS file on each client. If the entry in the client file is pointing to the wrong IP, this could cause the connectibitiy issues described. Therefor the sys admin should enter the "nbstat -R" command to purge and reload the cached name table from the LMHOST file on their windows workstation.
- **nslookup** = command is used to query the DNS to obtain information about host addresses, mail exchanges, nameservers, and related information. the nslookup command has an interactive and non-interactive mode.
- **ipconfig** = command is used on windows to display the current TCP/IP network configuration and refresh the DHCP and DNS settings on a given host.
- **Route** = command is used to create, view, or mdify manual entries in the network routing tables of a computer or server.
## 1st Device to configure when connecting VPN 
- you should FIRST configure the firewall since the firewall is installed at the networks external boundary (perimiter). By allowing the VPN connection through the firewall, the two networks can be connected and function as a single intranet (internal network). After configuring the firewall, you will need to verify the router is properly configured to route traffic between the two sites using the site-to-site VPN connection. A modem modulates and demodulates electrical signals sent through phone lines, coaxial cables, or other types of wiring. a layer 2 switch is a type of network switch or device that works on the data link layer (OSI Layer 2) and utilizes MAC address to determine the path through where the frames are to be forwarded. It uses hardware-based switching techniques to connect and transmit data in a local area network ( LAN).
## SAN I/O Optimimaztion
- **Network Diagram** = is a visual representation of network architectuire. It maps out the structure of a network w/ a variety of different symbols and line connections, this info will be important when deploying a Storage Area Network (SAN) on the enterprise network.
- **Baseline** = is a process for studying the network at regular intervals to ensure that the network is working as designed.
- **Asset management** = used to record and track an asset throughout its life cycle, from procurement to disposal.
- **Access to Datacenter** = will only be required if the vendors support technician will be physically working in the datacenter and not perforiming a remote installation.
## Increase Server availability
- The BEST recommendation would be to install a redundant power supply in the server. 
- Adding a second UPS ( Uninterruptible Power Supply ) to a generator will not solve this issue, either, because generators also require scheduled maintenance and downtimes. 
- Finally, adding a surge protector won't provide power when you need to power off a UPS for a battery placement.
## Technology to improve 802.11n vs 802.11ac
- One way 802.11n and 802.11ac networks achieve superior throughput and speeds are by using multiple-input multiple-output ( MIMO) and multi-user MIMO(MU-MIMO), respectively. MIMO uses multiple antennas for transmission and reception, which results in higher speeds than 802.11n and 802.11g networks, which can only support up to 54 of throughput. Wireless N and Wireless AC networks also utilize the 5 GHz frequency band, allowing them to achieve speeds greater than 54 Mbps. WPA2 is a wireless encryption standard and can be used w/ Wireless G, N, AC, or AX. Using WPA2 does not increase the speed of the wireless network. 
- Power over Ethernet (POE) is a technology that lets network cables carry electrical power. POE is defined in the IEEE 802.3af. PoE does not affect the speed of a wireless network. 
- Lightweight Access Point Protocol (LWAPP) is  the name of a protocol that can control multiple Wi-Fi wireless access points at once. This can reduce the amount of time spent on configuring, monitoring, or troubleshooting a large network. LWAPP does not affect the speed of a wireless network
## Port 80 to internal server over Port 81
- Port Forwarding = an application of network address translation ( NAT ) that redirects a communication request from one address and port number combiniation to another while the packets are traversing a network gateway, such as router or firewall.
- PAT , Port Address Translation = type of a dynamic NAT that can map multiple private IP addresses to a single public IP address by using port forwarding.
- Static NAT , Network Address Translation = is a one-to-one mapping of a private IP address to a public IP Address.
- Dynamic NAT = can be defined as a mapping a private ip to a public ip address from a group of public IP addresses known as the NAT pool. Dynamic NAT establishes a one-to-one mapping between a private IP address to a public IP address.
- Dynamic DNS ( DDNS) = is a method of automatically updating a name server in the DNS, often in real-time, w/ the active DDNS configuration of its configured hostnames, addresses, or other information.
- Since the question focused on the relationsjip between port 80 at the gateway or public IP address being mapped to port 81 on the internet server, this is an example of port forwarding that can be configured on the gateway or firewall of this network.
## Network Cabling Diagrams
- **Physical Network Diagram** = is used to show the actual physical arrangement of the components that make up the network, including cables and hardware.
- **Logical Network Diagram** = is used to illustrate the flow of data across a network and is used to show how devices communicate w/ eachother. These logical diagrams usually include the subnets, network objects and devices, routing protocols, and domains, voice gateways, traffic flow, and network segments in a given network.
- **Wiring Diagram** = are used to clearly label which cables are connected which ports. the more in-depth wiring diagrams will include a floorplan or rack diagram, so you can see how the cables are run in the phyiscal environment.
-**Wireless Site Survery** = is the process of planning and designing a wireless network to provide a wireless solution that will deliver the required wireless coverage, data rates, network capacity, roaming capabilitiy, and quality of service (QoS). The site survey report will contain a floorplan of the areas surveyed w/ the wireless coverage areas and signal strengths notated on it.
## Seperate BOYD vs Corporate owned device
- **VLAN** = is a type of network segmentation configured in your network switches that prevents communications between different VLANs w/o using a router. This allows two virtually separated networks to exist on one phyiscal network and separates the two virtual networks data. 
- **VPN** , Virtual private network = is a remote access capability to connect a trusted device over an untrusted network back to the corporate network. A VPN would not create the desired effect.
- **WPA2** = is a type of wireless encryption, it will not create two different segmented networks on the same physical hardware.
- **MAC filtering** = is used to allow or deny a device from connecting to a network, but it will not create two network segments, as desired.
## Criminal/government investigation
- Data Transport = transports data
- first responder = first person to arrive on the scene.
- ecnryption = method of putting data into a tunnel so that it is completely secure.
- eDiscovery = term that refers to the process of evidence collection through digital forensics. eDiscovery is conducted during an incident response.
## Two ways to Authenticate in person network
- Network Access Control (NAC) = is used to identify an endpoints characteristics when conducting network authentication.
- GPS location = of the device will provide the longitude and latitude of the user, which could be compared against the GPS coordinates of the building.
- Port Secuirty = enables an administrator to configure individual switch ports to allow only a specified number of source MAC addresses to communicate using a given switchport, this would not help to locate the individual based on their location, though.
- Geo-IP = Geolocation and country lookup of a host based on its IP address, would identify the country of origin of the user, but not whether they are within the buildings confines. Geo-IP is also easily tricked if the user logs in over a VPN connection.
## Maintain WAN connection on downsite
- GBP ( Border Gateway Protocol ) = is a standardized exterior gateway protocol designed to exchange routing and reachability information between autonomous systems (AS) on the internet. the protocol is often classified as a path vector protocol but is somestimes also classed as a distance-vector routing protocol.
- OSPF ( Open Shortest Path First ) = is a link-state routing protocol that was developed for IP networks and is based on the shortest path first (SPF) algorithm. OSPF is an interior gateway protocol (IGP), therefore it will not help be able to reroute the organizations WAN connections.
- VRRP ( Virtual Router Redundancy Protocol) = is a computer networking protocol that provides for automatic assignment of available internet protocol routers to participating hosts. This increases the availability and reliability of routing paths via automatic default gateway selections on an IP subnetwork. VRRP is used for your internal clients and will not affect the routing of traffic between WANs or autonomous systems
- Load Balacning = refers to the process of distributing a set of tasks over a set of resources, w/ the aim of making their overall processing more efficient. Load balacing can optimize the response time and avoid unevenly overloading some compute nodes while other compute nodes are left idle. a load balancer would work at one site, but would not allow routing of the WAN connections at all the other sites since they rely on autonomous systems and BGP is used to route traffic between autonomous systems.
## Log Management Tools
- Using an event management tool will allow the administrator to clear the event logs and move them from the server to a centralized database if needed. This will prevent the logs from filling up on the server w/o having to delete them permanently from the logging environment.
## Client-Server
- a client-server network model utilizes specific devices (servers) to provide services to requesters (clients). A server is a specialized computer that runs a networking operating system. A client is any device that requests services over a network, such as a desktop, laptop, tablet, or internet of things device. a peer-to-peer network model does not differentiate between the clients and the servers, and every node can become a client and a server when requesting and responding to service requests.
- Peer-to-peer = network model does not differentiate between the clients and the serverrs, and every node can become a client and a server when requesting and responding to service requests.
- Hub and spoke - topoligy is a network topolgy where a central device (the hub) is connected to mutliple other devices ( the spokes)
- Point-to-point = connection provides a path from one communcation endpoint to another.
## Topology
- **Mesh** = connects every node directly to every other node, this creates a highly efficient and redundant network, but its expensive to build and maintain
- **Star** = connects all of the other nodes to a central node, usually a switch or hub. star topology is the most popular network topology in a use on a LAN
- **Ring** = connects every device to exactly two other neighboring devices to form a circle, messages in a ring topology travel in one direction and usually rely on a token to control the flow of information
- **Bus** = uses a single cable which connects all the included nodes and the main cable actsd as a backbone for the netire network.