# COMPUTER NETWORKING

# What is Data Communication? 
Data Communication refers to transmission of data from one devices to another devices Through Transmission medium (it can be either wired or wireless) is called Data Communication or exchange information efficiently and accurately across distances, whether between computers,servers, sensors, or other devices. 

## Key Components of Data Communication: 
##### 1. Sender: The device that sends the data (e.g., computer, smartphone). 
##### 2. Receiver: The device that receives the data. 
##### 3. Message: The actual data (text, audio, video, etc.). 
##### 4. Transmission Medium: The physical path (like cables or air) through which the message travels. 
##### 5. Protocol: A set of rules that govern the communication (e.g., TCP/IP). 

## Types of Data Communication: 
##### 1. Simplex: Data flows in one direction only (e.g., keyboard to computer). 
##### 2. Half-Duplex: Data flows in both directions, but only one direction at a time (e.g., walkie-talkie). 
##### 3. Full-Duplex: Data flows in both directions simultaneously (e.g., phone calls). 

# What is a Network? 
A Network is system in which two or more devices are connected and share their resources and exchange of data. These devices connect through either wired (like Ethernet cables) or wireless (like Wi-Fi or Bluetooth) communication channels. 

## Top Benefits of a Network 
<b> Resource Sharing </b> : Devices on a network can share printers, scanners, storage drives, and internet connections. 

<b>Easy Communication</b> : Networks enable emails, chats, video calls, and instant messaging between users in real time 

<b>Data Backup and Recovery</b> : Central servers can be configured to automatically back up files, reducing data loss risk. 

<b>Security and Access Control</b> : Networks allow user authentication, permissions, and firewalls to protect data. 

<b>Remote Access </b>: With technologies like VPNs and cloud computing, users can access the network remotely.

# Network Classification 
Networks can be classified based on: 
1. Geographical Area (Size and Distance) 
2. Connection Type (Wired or Wireless) 
3. Network Architecture (How it’s built)
    
## 1. By Geographical Area 
<b>a. A Personal Area Network (PAN)</b> is the smallest type of computer network. It connects all the devices in very smaller geographical area, usually within a range of about 10 meters (like inside a room). 

<b>b. A Local Area Network (LAN)</b>  is a network that connects computers and devices within a small geographical area, like a home, office, or building. It allows devices to communicate, share resources (like files, printers), and access the internet through a common connection. 

<b>c. A Campus Area Network (CAN)</b> is a network that connects multiple local area networks (LANs) within a limited geographic area, like a university campus, corporate campus, or large business complex. 

<b>d. A Metropolitan Area Network</b> is a network that covers a larger geographic area than a LAN or CAN, typically spanning a city or metropolitan area. Covers a city or a large campus area (tens of kilometers) 

<b>e. A Wide Area Network is a network</b> that covers a very large geographical area, often spanning cities, countries, or even continents. It connects multiple smaller networks such as LANs, CANs, or MANs. 

![Screenshot 2025-05-29 230950](https://github.com/user-attachments/assets/b041a0db-fcf7-4fd5-9700-06bc0d6170ec)


## 2. Connection Type (Wired or Wireless) 
### What is Transmission Media? 
Transmission media refers to the physical pathway or channel through which data signals travel from the sender to the receiver in a communication system. It connects the transmitting device to the receiving device and allows the transmission of information such as data, voice, or video. 
#### 1. Guided Media (Wired) : Data signals are transmitted through a physical conductor. 
a.) Coaxial Cable


A coaxial cable is a type of cable used to carry electrical signals, like TV or internet signals. It’s designed so the signal can travel clearly without getting disturbed by outside noise. It contains a copper wire at the center, which is covered by an insulating plastic layer. Around this, there is an aluminum (or metal) shield called the coaxial wire, which protects the signal from external noise and interference. 

b.) STP (Shielded Twisted Pair) / UTP (Unshielded Twisted Pair) : 

UTP cable is a type of network cable with pairs of wires twisted together It does not have extra shielding around the wires. STP cable is similar to UTP but has extra shielding (a metallic foil or braid) around the twisted wire pairs.

c.) Fiber Optics 

Fiber optics is a technology that uses very thin strands of glass or plastic fibers to transmit data as pulses of light .fiber optic cables carry information using light signals, which allows data to travel much faster and over longer distances without losing quality. 

![image](https://github.com/user-attachments/assets/47963dce-48c4-47f2-bc7b-96f418b7c75f)



#### 2. Unguided Media (Wireless) : Data signals are transmitted through the air or space without physical conductors. 
<b>Types of Unguided Media:</b> 

<b>• Radio Waves:</b> Used for broadcast radio, TV, and mobile communication. 

<b>• Microwaves:</b>Used for satellite communication and point-to-point communication. 

<b>• Infrared:</b> Used for short-range communication such as remote controls. 

<b>• Satellite Communication:</b> Uses satellites to transmit signals over very long distances 

#### 3. Network Architecture (How it’s built) 
Network architecture refers to the design and structure of a computer network. It defines how different devices like computers, servers, routers, and switches are connected and how they communicate with each other. 
##### Types of Network Architecture 
<b>A.Peer-to-Peer (P2P):</b> In a P2P architecture, all computers (called peers) are equal. Each one can act as both a client (requesting data/services) and a server (providing data/services). There's no central server. 
##### Advantages of P2P 
• Easy to set up and use, especially for small networks.

• No need for expensive central servers. 

• If one computer goes offline, others can still communicate. 

• Good for sharing files like music, videos, or documents. 

<b>B.Client-Server:</b> In a Client-Server architecture, the network has a central server that provides services or resources, and multiple clients that request and use these services.
##### Advantages of Client-Server Network 
• Centralized control makes it easier to manage and secure the network. 

• Servers can be very powerful and handle many clients at once.

• Easier to back up data because it’s stored centrally. 

• Good for businesses and large organizations.

# What is Network Topology? 
it is the structure of connection between two computer or layout in which network devices are connected to each other. Topology is selected on the basis of the number of versiuon networked in the segment, the speed in the network and the budget for thr network.
### Type of Topology 
#### 1. Bus Topology  
In Bus Topology, all devices (computers, printers, etc.) are connected to a single central cable called the bus or backbone.it is economical because it use single cable. any failure in the cable can halt the entire network. it can travel upto 500m without amplification. thye coaxial cable in this topology are restitive to external electromagnetic interferences.it also used terminator to end the signal after successful delivery.
#### Advantages 
• Simple and Easy to Install: Requires less cabling compared to other topologies. 

• Cost-Effective: Uses the least amount of cable, reducing costs. 

• Good for Small Networks: Works well with a small number of devices 

•can add more devices: we can add more devices through wire

### 2. Ring Topology 
all the devices on the network are connected to each other to form a ring. each device has reciever and transmitter that act a repeter and send signal to the next computer. in this topology signal travel in a circle, passing through each computer on the network because there are no terminated in the ring. The ring topology support coaxiaol, twisted as well as fibre optic cable. A token ring are used in this topology to pass turn one by one to each devices . common protocols used to imoplement ring topolgy are tokrn ring, fibre optic data interface. 
#### Advantages 
• Orderly Network: Data passes in one direction, reducing the chance of packet collisions. 

• High Performance: Suitable for networks with heavy traffic because each device waits its turn to transmit. 

• Equal Access: Each device has equal opportunity to transmit data. 

• Fault Detection: Faulty devices can be easier to detect with proper monitoring.

### 3. Star Topology 
All the devices are connected to each other through central concentrator(hub and switch) forming star like structure. The computer can be connected to the hub or switch using UTP, STP & optic-fibre. the cost to setup a star is high becuase each device on network will utilize an individual length of cable from the concentrator to its location. failure of sigle device doesnot halt entire netwok but failure of concentrator can halt.common protocols used in this :- ethrnet, tokenring, ARCnet & localtalk.
#### Advantages 
• Easy to manage and troubleshoot: Faults are isolated to individual connections.

• Failure of one device does not affect the entire network. 

• Scalable: Easy to add more devices. 

• Better performance: Data can be sent to multiple devices without collisions if a switch is used. 

### 4. Mesh Topology  
In Mesh Topology, every device is connected directly to every other device in the network. This means 
multiple paths exist between any two devices. 
#### Types of Mesh Topology 
<b>• Full Mesh:</b> Every device is connected to every other device. 

<b>• Partial Mesh:</b> Some devices are connected to multiple devices, but not all. 
#### Advantages 
• Very reliable: Failure of one device or connection does not affect network communication.

• Data can be transmitted simultaneously: Multiple devices can communicate at the same time. 

• Fault tolerance: Easy to detect and isolate faults. 

• High privacy and security: Data travels through dedicated paths. 

### 5. Tree Topology 
Tree Topology is a combination of Star and Bus topologies. It consists of groups of star-configured networks connected to a linear bus backbone cable. It resembles a tree structure with branches. 
#### Advantages 
• Scalable: Easy to add new nodes or branches. 

• Fault isolation: Faults in one branch do not affect the entire network. 

• Better organized: Structured and hierarchical layout. 

• Supports large networks: Can handle many devices. 

### 6. Hybrid Topology 
Hybrid Topology is a combination of two or more different types of network topologies (like star, bus, ring, mesh) integrated into a single network. It leverages the strengths and minimizes the weaknesses of the combined topologies. 
#### Advantages 
• Highly flexible: Can use the best topology suited for each part of the network. 

• Scalable: Easy to expand by adding different topologies. 

• Fault tolerance: Problems in one part do not necessarily affect the whole network. 

• Efficient: Optimizes performance by combining topologies. 
Note : -  
# What is IEEE? 
• IEEE stands for Institute of Electrical and Electronics Engineers. 

• It is a global professional association dedicated to advancing technology. 

• IEEE develops and publishes widely accepted standards for various fields including networking, electronics, power, and telecommunications. 

## Its standards 
<b>IEEE 802.3 — Ethernet :</b> It is the standard for Ethernet, the most common wired networking technology worldwide.Defines the physical layer and data link layer specifications for wired LANs.Specifies how devices format and transmit data over cables. 

<b>IEEE 802.11 (Wi-Fi):</b> Wireless networking standard used in almost all wireless devices.

<b>IEEE 802.1Q:</b> VLAN tagging standard, crucial for network segmentation. 

<b>IEEE 802.1D:</b> Spanning Tree Protocol (STP) to prevent network loops. 

# Networking Terms  
## DNS (Domain Name System) 
•The Domain Name System (DNS) is like the internet's phonebook.

•When you type a website name like www.google.com, your computer doesn't understand that directly. It sends a query to a DNS server to find the IP address (e.g., 142.250.183.206) of the server hosting the website.

•This allows users to use human-readable names instead of remembering numbers.

•DNS operates mainly over UDP on port 53.

### 🔹 Example:
<b>Typing www.facebook.com → DNS query → Returns IP address → Browser connects to that IP.</b>

## URL (Uniform Resource Locator) 
•A URL is the complete address used to access a specific resource on the internet.

•It includes multiple components: <br>
https://www.openai.com/research
|       |           |        |
|       |           |        --> Path (specific page/folder)
|       |           --> Domain name (mapped to IP)
|       --> Protocol (HTTP/HTTPS/FTP/etc.)
--> Scheme indicator

• URLs tell your browser what protocol to use and where to connect.
 
• For example, in the URL https://www.example.com/index.html: 

            • <b> https:// is the protocol that tells how to access the resource. </b>
            • <b> www.example.com is the domain name of the website.</b> 
            • <b> /index.html is the path to a specific page or file on that website. </b>

## CDMA (Code Division Multiple Access) 
• CDMA stands for Code Division Multiple Access.  

• It is a wireless communication technology used for mobile networks.

• CDMA allows multiple users to share the same frequency band simultaneously by assigning unique codes to each user’s signal. 

• This technique improves the efficiency and capacity of the network compared to older methods. 

• CDMA is widely used in 3G cellular networks to provide voice and data services GSM (Global System for Mobile Communications) 

## GSM stands for Global System for Mobile Communications. 
• It is a standard technology for mobile networks used worldwide. 

• GSM uses time division multiple access (TDMA) to allow multiple users to share the same frequency by dividing the signal into different time slots. 

• It supports voice calls, SMS (text messaging), and data services. 

• GSM is the most widely used mobile communication technology globally, especially in 2G and 3G networks. 

# Some Important Protocol  
## TCP/IP (Transmission Control Protocol/Internet Protocol) 
TCP/IP stands for Transmission Control Protocol/Internet Protocol. It is a set of communication protocols used to connect devices on the internet and most other computer networks. 

<b>• IP (Internet Protocol)</b> is responsible for addressing and routing packets of data so they can travel across networks and arrive at the correct destination. 

<b>• TCP (Transmission Control Protocol)</b> ensures reliable delivery of data by establishing a connection, checking for errors, and managing data packets in the correct order. 

## FTP (File Transfer Protocol) 
• FTP is a protocol used to transfer files between computers over a network.

• Operates on TCP port 21 (control) and 20 (data).

• Typically used for uploading websites or downloading large files.

⚠️ FTP sends data in plain text, so it’s not secure unless used with FTPS or SFTP.

• FTP allows users to upload, download, rename, delete, or move files on a remote server. 

• It is commonly used for website management, sharing files, and backup purposes. HTTP (Hypertext Transfer Protocol) 

## HTTP stands for Hypertext Transfer Protocol. 
• The protocol used by web browsers to request and display web pages.

• It operates over TCP port 80.

• Sends data in plain text.

• When you enter a website address, your browser uses HTTP to request the web page from the server. 

• HTTP defines how messages are formatted and transmitted, and how web servers and browsers should respond to commands HTTPS (Hypertext Transfer Protocol Secure)

## HTTPS stands for Hypertext Transfer Protocol Secure. 
• It is the secure version of HTTP used to transfer web pages safely over the internet.

• HTTPS encrypts the data exchanged between your browser and the website, protecting it from hackers and eavesdroppers. 

• It uses protocols like SSL/TLS to ensure privacy and data integrity. 

• Websites using HTTPS show a padlock symbol in the browser’s address bar, indicating a secure connection. 

## SMTP (Simple Mail Transfer Protocol) 
• SMTP stands for Simple Mail Transfer Protocol. 

• Operates over TCP port 443. 

• It is a protocol used to send and transfer email messages between mail servers on the internet. 

• SMTP handles the process of sending outgoing emails from your email client to the recipient’s mail server. 

• It works alongside other protocols like POP3 or IMAP, which are used to receive and manage emails. 

## POP3 (Post Office Protocol version 3) 
• POP3 stands for Post Office Protocol version 3. 

• It is a protocol used by email clients to retrieve or recieve emails from a mail server. 

• POP3 downloads the emails from the server to your device and usually deletes them from the server afterward.

## IMAP4 (Internet Message Access Protocol version 4) 
• IMAP4 stands for Internet Message Access Protocol version 4. 

• It is a protocol used by email clients to access and manage emails stored on a mail server. 

• Unlike POP3, IMAP4 allows you to view and organize your emails directly on the server without downloading them permanently. 

• This means you can access your emails from multiple devices, and changes like reading or deleting emails are synced across all devices. 

## Telnet 
• Telnet is a command-line tool that allows you to remotely log in to another computer or network device (like a router or switch).

• Works over TCP port 23.

• Sends all data, including passwords, in plain text (not secure).

• Mostly replaced by SSH (Secure Shell) in modern systems.

![Screenshot 2025-05-29 235656](https://github.com/user-attachments/assets/30d21fe3-6028-4bd3-a136-4639c86630e0)


# Networking Devices 
## Hub 
• A Hub is a basic networking device used to connect multiple computers or devices in a local area network (LAN). 

• It works by receiving data packets from one device and broadcasting them to all other connected devices. 

• Hubs operate at the physical layer (Layer 1) of the OSI model.

• They do not filter or manage any traffic — this means all devices receive all data, which can lead to collisions and reduced network efficiency. 

## Switch 
• A Switch is a networking device that connects multiple devices in a local area network (LAN). 

• Unlike a hub, a switch receives data and forwards it only to the specific device for which the data is intended. 

• Switches operate at the data link layer (Layer 2) of the OSI model. 

• They improve network efficiency by reducing data collisions and managing traffic intelligently using MAC addresses. 

## Router  
• A Router is a networking device that connects different networks together, such as your home network to the internet. 

• It forwards data packets between networks by determining the best path for the data to travel. 

• Routers operate at the network layer (Layer 3) of the OSI model. 

• They use IP addresses to route data and often provide additional features like firewall protection, DHCP, and NAT. 

• Routers are essential for directing internet traffic and enabling communication between devices on different networks. 

## Bridge 
• A Bridge is a networking device that connects two or more separate local area networks (LANs) to work as a single network. 

• It operates at the data link layer (Layer 2) of the OSI model. 

• A bridge filters traffic by inspecting MAC addresses and only forwards data to the part of the network where the destination device is located. 

• This helps reduce network traffic and improves efficiency by preventing unnecessary data 
Transmission. 

• Bridges are used to divide large networks into smaller segments to reduce collisions and improve performance. 

## Gateway 
• A Gateway is a networking device that connects two different networks that use different protocols or architectures. 

• It acts as a translator, enabling communication between networks that would otherwise be incompatible. 

• Gateways operate at multiple layers of the OSI model, depending on their function. 

• For example, a gateway can connect a company’s internal network to the internet or link two different network systems. 

• Gateways are essential for enabling data flow between different network environments. 

## Modem 
• A Modem stands for Modulator-Demodulator. 

• It is a device that converts digital data from a computer into analog signals for transmission over telephone or cable lines, and vice versa. 

• Modems allow your computer or network to connect to the internet through these analog communication lines. 

• They play a crucial role in broadband connections like DSL, cable internet, or dial-up. 

## Repeater 
• A Repeater is a networking device that amplifies and regenerates signals to extend the distance over which data can travel in a network. 

• It receives a weak or distorted signal, cleans and boosts it, then retransmits it at its original strength.

• Repeaters operate at the physical layer (Layer 1) of the OSI model. 

• They are used in networks to overcome signal loss caused by distance or interference. ADSL (Asymmetric Digital Subscriber Line) 

## ADSL (Asymmetric Digital Subscriber Line)
• ADSL stands for Asymmetric Digital Subscriber Line. 

• It is a type of DSL technology used to provide high-speed internet access over regular telephone lines. 

• "Asymmetric" means that the download speed is faster than the upload speed, which suits typical internet use like browsing and streaming. 

• ADSL allows you to use the internet and make phone calls simultaneously on the same line. 

• It is commonly used for home and small business internet connections.

# There Are Two Type of Model  
## 1. TCP/IP Model  
The TCP/IP model is the fundamental communication protocol suite for the internet and most modern networks. 

### It consists of 4 layers, each with specific roles: 
### 1. Application Layer  
The Application Layer is the topmost layer of the TCP/IP model.It provides services and interfaces for user applications to communicate over a network.
This is the layer where network-related applications like web browsers, email clients, and file transfer programs operate. 

### 2. Transport Layer 
The Transport Layer is the second layer in the TCP/IP model (just below the Application Layer). It is responsible for the reliable or unreliable delivery of data between devices over a network.
              • Breaks data into segments before transmission.
              
              • Ensures error checking, flow control, and retransmission if needed. 
              
              • Helps devices communicate reliably by managing end-to-end connections. 
### 3. Internet Layer 
The Internet Layer is the third layer in the TCP/IP model, just below the Transport Layer. It is responsible for routing data packets between devices across multiple networks and ensuring they reach the correct destination. 
                 • Logical addressing using IP addresses. 
                 • Packet routing: Choosing the best path for data to travel. 
                 • Encapsulation and Decapsulation of data into packets. 
                 • Handling error reporting and diagnostics. 
                 
### 4 . Network Access Layer (also called Link Layer or Network Interface Layer) 
The Network Access Layer is the lowest layer in the TCP/IP model. It is responsible for the physical transmission of data over the network — from one device to another on the same local network. 
          • Framing: Breaks data into frames for transmission. 
          • MAC addressing: Uses physical (hardware) addresses to identify devices. 
          • Error detection (basic, at the frame level). 
          • Manages how data is placed on the network media (like cables or wireless signals). 
          
## 2 . OSI Model  
The OSI Model standardizes how network systems communicate and interact. 
### It helps break down complex networking processes into 7 manageable layers: 
### 1. Physical Layer  
The Physical Layer is the first and lowest layer of the OSI model. It is responsible for the actual physical connection between devices, including the transmission and reception of raw bits over a physical medium (like cables, radio waves, or fiber optics) 
#### Main Purposes:
<b>1. Bit Transmission </b>
Converts data into electrical, optical, or radio signals and transmits those raw bits over the physical medium. 
<b>2. Defines Physical Characteristics </b>
o Specifies cables, connectors, voltage levels, signal timing, and data rates. 
<b>3. Transmission Medium </b>
o Supports various media like copper wires, fiber optics, wireless signals, etc. 
<b>4. Topology and Network Design </b>
o Supports physical layout like bus, star, ring topologies. 
<b>5. Synchronization of Bits </b>
o Ensures sender and receiver are synchronized to properly interpret bits. 
#### Ethernet at the Physical Layer (Layer 1) 
• The Physical Layer is responsible for transmitting raw bits (0s and 1s) over the physical medium (like cables or fiber).

• Ethernet defines the physical standards for cables, connectors, voltage levels, and signaling methods. 
### 2. Data Link Layer  
The Data Link Layer is the second layer of the OSI model. It is responsible for node to node delivery of 
data or we can say that hope to hope delivery of data . This means it ensures data is reliably 
transferred between two directly connected devices (or nodes) on the same network segment. 
#### Main Purposes:     
<b>1. Framing </b>
o Divides the stream of bits into manageable units called frames. 
<b>2. Error Detection & Correction </b>
o Detects errors that may occur in the Physical Layer and may request retransmission. 
<b>3. Flow Control </b>
o Manages the rate of data transmission between sender and receiver to avoid congestion. 
<b>4. MAC Addressing </b>
o Uses MAC (Media Access Control) addresses to identify devices on a local network.
<b>5. Media Access Control (MAC) </b>
o Determines how devices share the communication channel (important in shared networks like Ethernet).

#### What is Framing? 
Framing is the process of dividing raw data bits from the network layer into manageable units called 
frames before transmission over the physical medium. 
##### There are two types of framing: 
<b>1. Fixed-size:<b> The frame is of fixed size and there is no need to provide boundaries to the frame, the length of the frame itself acts as a delimiter.

2. Variable size: In this, there is a need to define the end of the frame as well as the beginning of the next frame to distinguish. 
1. Character/Byte Stuffing: Used when frames consist of characters 
2 . Bit stuffing: Bit stuffing is a technique used to prevent data from being interpreted as control characters by inserting extra bits into the data stream. 
##### Simple Example: 
• Suppose the data contains: 01111110 (this is the flag pattern) 

• Before sending, the sender changes it to: 0111110 0 10 (inserts a '0' after five consecutive '1's) 

• The receiver, seeing the extra '0', knows to remove it to get back the original data.

Flag: 01111110 

Frame: 01111110 0111110010 01111110  (start Flag | data | end Flag)  

#### What is Switching in Networking? 
Switching is the process of directing data packets between devices in a network. It decides the best path for data to travel from the source to the destination. 
##### Types of Switching: 
1. Circuit Switching 
o A dedicated communication path is established between sender and receiver for the entire duration of the communication. 
o Example: Traditional telephone networks. 
2. Packet Switching 
o Data is broken into small packets. Each packet is sent independently and may take different routes to reach the destination. 
o Example: The internet. 
3. Message Switching 
o Entire messages are sent to the next switch and stored until the next path is free (storeand-forward). 
o Example: Early email systems. 
##### Why is switching important? 
• It manages traffic efficiently in a network. 
• Helps connect multiple devices and enables communication. 
• Optimizes the use of network resources. 
##### Spanning Tree Protocol (STP) 
Spanning Tree Protocol (STP) is a network protocol used to prevent loops in a switched Ethernet network. It can ensure that each device has one active path between two network devices .  
##### Ethernet in the Data Link Layer 
• Ethernet operates mainly at the Data Link Layer (Layer 2) of the OSI model. 
• It defines how devices format data into frames and control access to the physical medium. 
• Ethernet frames include important fields like: 
                o Destination MAC address 
                o Source MAC address 
                o Type/Length 
                o Data payload 
                o Frame Check Sequence (FCS) for error detection 

##### What is MAC? 
MAC (Media Access Control) is a way to manage how devices share a communication channel (like a network cable or wireless frequency). It decides who talks when so data doesn’t get mixed up. 
##### Three ways devices share the network: 
1. Aloha 
    • The simplest method. 
    • Devices send data whenever they want. 
    • If two devices send at the same time, collision happens, and data is lost. 
    • Devices wait a random time and try sending again. 
    • Works well when the network is not busy. 
2. Slotted Aloha 
   • An improved version of Aloha. 
    • Time is divided into slots. 
    • Devices can only send data at the start of a time slot. 
    • This reduces collisions because devices can’t send randomly anytime. 
    • Better efficiency than pure Aloha. 
3. CSMA (Carrier Sense Multiple Access) 
    • Before sending, a device listens to the channel. 
    • If the channel is free, it sends data. 
    • If the channel is busy, it waits before trying. 
    • Reduces chances of collision compared to Aloha. 
    • Variants like CSMA/CD (Collision Detection) are used in Ethernet. 
What is Flow Control? 
• Flow Control is a way to manage the speed of data transmission between a sender and a receiver. 
• It ensures the sender doesn’t send data faster than the receiver can handle. 
• Prevents data loss caused by receiver’s buffer overflow. Common Flow Control methods: 
Stop-and-Wait  
• It's a simple flow control method. 
• The sender sends one data packet (frame) at a time. 
• Then the sender waits for the receiver to send an acknowledgment (ACK) before sending the next packet. 
Go Back N  
• It’s a flow control and error control method used in data communication. 
• The sender can send multiple frames (up to a window size) without waiting for ACKs for each one. 
• If an error or lost frame is detected, the sender goes back and resends that frame and all the frames sent after it. 
Selective Repeat 
• It’s an advanced flow and error control protocol. 
• The sender can send multiple frames (like Go-Back-N), but the receiver only asks for the specific frames that are lost or have errors. 
• The receiver accepts frames out of order and buffers them until missing frames arrive. 
What is Error Detection? 
• It’s the process of finding errors in data during transmission. 
• Errors happen because of noise or interference in the communication channel. 
• Techniques add extra bits to data to help detect if errors occurred. 
Common Error Detection Methods: 
1. Parity Check: 
o Adds a single bit (parity bit) to make the number of 1’s either even or odd. 
o If parity doesn’t match on the receiver side, an error is detected. 
2. Checksum: 
o Adds up data chunks and sends the sum with the data. 
o Receiver calculates sum again and compares to detect errors. 
3. CRC (Cyclic Redundancy Check): 
o Uses polynomial division to create a checksum for detecting errors with high accuracy. 
What is Error Correction? 
• It’s the process of fixing errors in data automatically. 
• When an error is detected, the receiver can either: 
o Ask sender to resend the data (retransmission), or 
o Use extra bits to correct the error without needing retransmission. 
Common Error Correction Methods: 
1. Automatic Repeat Request (ARQ): 
o Receiver requests retransmission if errors are detected. 
2. Forward Error Correction (FEC): 
o Extra bits added so the receiver can detect AND fix errors by itself. 
#### 3. Network Layer  
The Network Layer is the part of a computer network that decides how data travels from one 
computer to another, even if they are on different networks. 
It gives each device an IP address, chooses the best path for the data, and helps it reach the right 
destination. 
Core Functions 
1. Logical Addressing 
o Assigns addresses (usually IP addresses) so that each device can be uniquely identified 
across a network. 
2. Routing 
o Determines optimal path for data to travel from source to destination. 
o Uses routing tables and protocols like RIP, OSPF, BGP. 
3. Fragmentation and Reassembly 
o Breaks down large packets into smaller fragments suitable for transmission and 
reassembles them at the destination. 
4. Packet Forwarding 
o Forwards packets from one network to another based on destination IP address 
Key Protocols 
IP Protocol : The Internet Protocol (IP) is a set of rules that computers use to send data to each other 
across the internet or any network. It gives every device an address (called an IP address) so the data 
knows where to go. 
IP Address : IP Address stands for internet Protocol is a unique identifier assigned to each device 
connected to network that use ip for communication . It allows to locate and communicate with each 
other on network either local or global .  
Types of IP Address 
IPv4 (Internet Protocol version 4) 
• It it composed of four group of number  , each ranging from 0 to 255 , separated by period(.)  
• It is of 32 bits  
• Can support about 4.3 billion unique addresses. 
IPv6 (Internet Protocol version 6) 
• This is much long , consisting 8 group of four hexadecimal digit sepreated by colns(:)  
• It is of 128 bits  
• Can support 340 undecillion addresses (that’s 340 followed by 36 zeros!) 
1. Public IP Address : A Public IP address is assigned by your Internet Service Provider (ISP) and is 
visible on the internet. 
2. Private IP Address : A Private IP address is used inside a home or office network. It’s not visible on 
the internet. 
3. Static IP Address : A Static IP does not change. It is manually set or permanently assigned. 
4. Dynamic IP Address : A Dynamic IP is automatically assigned by a DHCP server (like your router) 
and can change over time. 
Classes of IP Address 
IP addresses are divided into different classes (A, B, C, D, E) based on the range of their first octet. 
Each class serves different purposes in networks. 
Class First Octet 
Range 
A 
B 
1 – 126 
Default Subnet 
Mask 
255.0.0.0 ( /8 ) 
128 – 191 255.255.0.0 ( /16 
) 
C 192 – 223 255.255.255.0 ( 
/24 ) 
Number of 
Networks 
128 (2^7) 
Number of Hosts 
per Network 
16,777,214 (2^24 - 
2) 
16,384 (2^14) 65,534 (2^16 - 2) 
2,097,152 
(2^21) 
D 224 – 239 Not applicable Not 
applicable 
E 
240 – 255 Not applicable Not 
applicable 
254 (2^8 - 2) 
Not applicable 
Not applicable 
Classless Addressing (CIDR - Classless Inter-Domain Routing) 
Usage 
Very large networks (e.g., big 
ISPs) 
Medium-sized networks 
(universities, large 
businesses) 
Small networks (small offices, 
home networks) 
Multicast groups 
Experimental, research use 
only 
Classless addressing is a method of allocating IP addresses and routing IP packets without being 
restricted by the traditional class-based system (Class A, B, C). It was introduced to improve the 
efficiency of IP address allocation and to slow the exhaustion of IPv4 addresses. 
Key points: 
1. Flexible IP Allocation: Instead of fixed subnet masks defined by classes (like 255.0.0.0 for 
Class A), CIDR allows variable-length subnet masks (VLSM). This means networks can be 
divided into smaller or larger blocks depending on need. 
2. Notation: CIDR uses a format like 192.168.10.0/22, where /22 indicates the number of bits 
used for the network portion of the address. This allows precise control over how many IP 
addresses are included in the subnet. 
3. Efficient Use of IPs: By allowing subnets of any size, CIDR reduces waste of IP addresses that 
happened in the classful system where networks often had too many or too few addresses. 
4. Routing Simplification: CIDR enables route aggregation (supernetting), where multiple IP 
ranges can be summarized into a single routing table entry, reducing the size of routing tables 
and improving routing efficiency. 
5. Widely Used: CIDR is now the standard for IPv4 addressing on the internet, replacing classful 
addressing completely. 
2. ARP( Address Resolution Protocol)  
ARP is a protocol used to find the MAC address of a device when you already know its IP address. 
3. Reverse Address Resolution Protocol (RARP) 
RARP is a network protocol used to find the IP address of a device when its MAC (hardware) address 
is already known. It is essentially the reverse of ARP. 
4. Internet Control Message Protocol (ICMP) 
ICMP is a network layer protocol used by network devices, like routers and hosts, to send error 
messages and operational information indicating success or failure in communication. ICMP helps in 
diagnosing network communication problems and reporting errors such as unreachable destinations, 
packet loss, or time exceeded. 
5. Internet Group Management Protocol (IGMP) 
IGMP is a communication protocol used by IPv4 hosts and adjacent routers to manage membership 
of multicast groups on a local network. 
What is Routing? 
Routing is the method used to determine how data packets travel from the source device to the 
destination device across a network. 
Types of Routing: 
Type 
Static Routing 
Description 
Manually configured routes; good for small, simple networks. 
Dynamic Routing Routes are automatically updated based on network changes using protocols. 
Default Routing A path used when no specific route is found in the routing table. 
RIP (Routing Information Protocol) 
RIP is one of the oldest dynamic routing protocols used in computer networks to help routers 
exchange routing information. 
#### 4 . Transport Layer  
The Transport Layer is responsible for end-to-end communication and data transfer between host 
systems. It ensures that data is delivered reliably, in order, and without errors. 
Main Functions of Transport Layer: 
Function 
Segmentation & 
Reassembly 
End-to-End 
Communication 
Error Detection & 
Correction 
Flow Control 
Congestion Control 
Multiplexing 
Description 
Breaks large data into smaller segments at sender; reassembles them 
at receiver. 
Ensures complete data transfer from source to destination. 
Identifies and corrects transmission errors. 
Prevents sender from overwhelming the receiver with too much data. 
Helps avoid network overload by adjusting the data flow rate. 
Allows multiple applications to use the network simultaneously. 
Segmentation (in Transport Layer) 
Segmentation is the process of breaking down large chunks of application data into smaller, 
manageable pieces called segments before transmission over a network. 
TCP (Transmission Control Protocol) 
TCP is a connection-oriented protocol used at the Transport Layer of the OSI and TCP/IP models. It 
provides reliable, ordered, and error-checked delivery of data between applications. 
Key Features of TCP: 
Feature 
Description 
Connection-Oriented Establishes a connection (3-way handshake) before data transfer begins. 
Reliable Delivery 
Guarantees that data arrives without errors and in the correct order. 
Error Detection 
Flow Control 
Congestion Control 
Sequencing 
Uses checksums to detect errors in data. 
Uses window size to avoid overwhelming the receiver. 
Prevents network congestion using algorithms like slow start. 
Each segment has a sequence number to ensure correct ordering. 
Acknowledgment (ACK) Receiver confirms successful receipt of data. 
UDP (User Datagram Protocol) 
UDP is a connectionless, lightweight transport layer protocol. It is designed for fast data 
transmission with low overhead, but it does not guarantee delivery, order, or error correction. 
Key Features of UDP: 
Feature 
Connectionless 
Description 
No connection setup; sends data without handshakes. 
Unreliable Delivery Data may be lost or arrive out of order. 
No Acknowledgment Receiver doesn’t send an ACK back to the sender. 
No Flow Control 
Can cause data overflow if receiver can't handle the speed. 
Low Overhead 
Faster than TCP, ideal for time-sensitive applications. 
UDP vs TCP Comparison: 
Feature 
UDP 
Connection Connectionless 
Reliability No guarantee 
Speed 
TCP 
Connection-oriented (3-way handshake) 
Ensures delivery and order 
Faster (no retransmission/ack) Slower due to reliability mechanisms 
Use Cases Streaming, VoIP, Gaming, DNS Browsing, Email, File Transfer 
Header Size 8 bytes 
20 bytes (minimum) 
Multiplexing and Demultiplexing 
Multiplexing is the process of combining multiple data streams from different applications or 
sources into a single stream to be sent over a network. 
Demultiplexing is the process of separating a single incoming stream into multiple streams and 
delivering each to the correct application. 
#### 5. Session Layer  
The Session Layer is responsible for establishing, managing, and terminating sessions between two 
communicating devices or applications. It ensures that communication is properly organized and 
synchronized. 
Main Functions of the Session Layer: 
Function 
Session 
Establishment 
Description 
Initiates a communication session between devices. 
Session Maintenance Keeps the session active during data transfer. 
Session Termination Closes the session when communication ends. 
Synchronization 
Inserts checkpoints (sync points) in data streams to resume from there in 
case of failure. 
Function 
Description 
Dialog Control 
Manages which side communicates at what time (half-duplex or full-duplex). 
Examples of Session Layer Protocols: 
Protocol 
Use Case 
RPC (Remote Procedure Call) Allows programs to execute code on a remote system. 
NetBIOS 
Supports communication in LANs. 
PPTP 
SMPP 
#### 6. Presentation Layer  
Used for VPN sessions. 
Used in SMS message exchange systems. 
The Presentation Layer is like the translator and formatter of the OSI model. Its main job is to ensure 
that data sent from one system can be understood by another — regardless of differences in data 
formats, encoding, or encryption. 
Main Functions of the Presentation Layer: 
Function 
Translation 
Encryption/Decryption 
Description 
Converts data between different formats (e.g., EBCDIC ↔ ASCII). 
Secures data before transmission and decrypts it at the receiver's 
end. 
Compression/Decompression Reduces data size for faster transmission and restores it on the 
other side. 
Data Formatting 
Ensures data is in a readable and usable format (e.g., JPEG, MP4, 
PDF). 
Examples of Presentation Layer Protocols/Technologies: 
Technology 
SSL/TLS 
Role 
Encrypts/decrypts web traffic (used in HTTPS) 
JPEG, MP3, MP4 Format multimedia data for transmission 
GIF, PNG 
Image formatting 
ASCII, EBCDIC Text encoding formats 
MIME 
Used for formatting email data 
#### 7. Application layer  
The Application Layer is the topmost layer of the OSI model. It directly interacts with the end-user 
and provides network services to applications (like web browsers, email clients, etc.). 
Main Functions of the Application Layer: 
Function 
Description 
User Interface Access Enables user interaction with network services (e.g., via browser or app). 
Network Services 
Provides services such as email, file transfer, remote access, etc. 
Resource Sharing 
Data Presentation 
Supports data exchange, printing, file sharing over a network. 
Sends requests down the OSI stack for formatting, encryption, etc. 
Examples of Application Layer Protocols: 
Protocol 
HTTP/HTTPS 
FTP 
SMTP 
POP3/IMAP 
DNS 
Telnet/SSH 
SNMP 
Unicast 
Term 
Multicast 
Broadcast 
Multicast Group 
Broadcast Domain 
IP Address 
Broadcast Address 
One-to-one communication where data is sent from a 
single sender to a single receiver. 
One-to-many communication where data is sent from 
one sender to multiple receivers who have joined a 
specific multicast group. 
One-to-all communication where data is sent from 
one sender to all devices in a network segment. 
A set of hosts that are interested in receiving a 
particular multicast transmission. Hosts explicitly 
join this group. 
A logical division of a network where any broadcast 
sent is received by all devices in that segment. 
A unique numerical identifier assigned to each device 
on a network. 
The special IP address used to send a packet to all 
devices in the broadcast domain (e.g., 
255.255.255.255 in IPv4). 
Use Case 
Web browsing (used in 
Chrome, Firefox, etc.) 
File transfer 
Sending emails 
Receiving emails 
Domain name 
resolution (e.g., 
google.com → IP) 
Remote login/access to 
another computer 
Network management 
and monitoring 
Meaning 
Protocol 
Use Case 
Multicast Address 
Network Segment 
Packet 
Routing 
IGMP (Internet Group 
Management Protocol) 
A special IP address (in IPv4, from 224.0.0.0 to 
239.255.255.255) used to identify multicast groups. 
A portion of a network where devices can directly 
communicate at the data link layer without a router. 
A formatted unit of data carried by a network. 
The process of selecting paths in a network along 
which to send network traffic. 
Protocol used by hosts and adjacent routers to 
establish multicast group memberships. 
 
 
 
 
