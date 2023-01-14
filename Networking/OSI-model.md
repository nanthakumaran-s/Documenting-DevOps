# OSI Model

**Open Systems Interconnection Model** commenly refered as OSI Model is a framework used to describe the function of networking. The OSI Model splits the functionality into **7 layers** each with a specific purpose and a set of protocols to acheive the purpose

## Layers:
**Physical, Data Link, Network, Transport, Session, Presentation, and Application**

### Layer 7: Application layer
It enables users to access the network. It provides support for services such as email, file transfer, etc,. 

#### Protocols: 

- HTTP (Hyper Text Transfer Protocol)
- SMTP (Simple Mail Transfer Protocol)
- DNS (Domain Name System)
- FTP (File Transfer Protocol)
- TELNET (Teletype Network)
- SSH (Secure Shell)

> Process to Process Communication

### Layer 6: Presentation Layer
This layer is responsible for converting the data provided by the application layer into machine understanable binaries. **Translation** of data takes place in this layer. This layer also takes care **Compression & Encryption**

### Layer 5: Session Layer
As the name suggests, this layer is responsible for maintaining the session for transporting the data. It opens, maintains and terminates session for communicating systems

### Layer 4: Transport Layer
This layer will segment the data received by the upper layers and make them into segments. Each segment contains information about the **source and destination port numbers** and the **sequence number** (to reassemble the segments at the receiver end). **Flow Control & Error Control** are managed in this layer. 

#### Protocols: 

- TCP (Transmission Control Protocol)
- UDP (User Datagram Protocol)

> End to End Communication

### Layer 3: Network Layer
It is responsible for source-to-destination delivery of the data packets. Each segment received from the transport layer is assigned with the **source and destination IP address**. This data packets are then routed to the destination via the different network. The network is chosen in order to achieve fast delivery. The addressing done in this layer is known as **Logical Addressing**

#### Protocols: 

- IP (Internet Protocol)

> Host to Host Communication

### Layer 2: Data Link Layer
The data packet is received from the network layer and **physical address/MAC address** of the sender and reciever is assigned to the packet and now it is termed as **Frame**

> Node to Node Communication

### Layer 1: Physical Layer
This is the hardware section of the OSI Model where medium for transmission of data is involved. The medium can be wired or wireless. This will transmit data in **bits (0 or 1)**. This bits are then converted into electrical signals that can be transmitted over the medium.

> Node to Node Communication

