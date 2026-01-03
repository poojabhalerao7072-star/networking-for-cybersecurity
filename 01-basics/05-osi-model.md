# OSI Model (Open Systems Interconnection)

## What is OSI Model?

The **OSI (Open Systems Interconnection) Model** is a **7-layer conceptual framework** used to understand how data is transmitted from one device to another over a network.  
It standardizes communication functions so that different systems and vendors can communicate effectively.
In cybersecurity, the OSI model helps identify **where attacks occur** and **which security controls should be applied**.

![image alt](https://github.com/poojabhalerao7072-star/networking-for-cybersecurity/blob/06217e0c071aa9a63f6ebfd2991a53ccf7750254/01-basics/osi-model-slide1.png)

## OSI Model Layers and Their Main Functions

### 7️⃣ Application Layer
**Main Function:**
- Provides network services directly to end users and applications

**Examples:**
- Web browsing, email, file transfer

**Protocols:**
- HTTP, HTTPS, FTP, SMTP, DNS


### 6️⃣ Presentation Layer
**Main Function:**
- Translates data into a readable format
- Handles **encryption, decryption, and compression**

**Examples:**
- SSL/TLS encryption
- Data formatting (ASCII, Unicode)


### 5️⃣ Session Layer
**Main Function:**
- Establishes, manages, and terminates communication sessions between devices

**Examples:**
- Session authentication
- Session checkpoints and recovery


### 4️⃣ Transport Layer
**Main Function:**
- Ensures reliable data delivery
- Performs **segmentation, flow control, and error control**

**Protocols:**
- TCP (reliable)
- UDP (fast, unreliable)


### 3️⃣ Network Layer
**Main Function:**
- Handles logical addressing and routing of data packets
- Determines the best path for data transmission

**Protocols:**
- IP, ICMP

**Devices:**
- Routers


### 2️⃣ Data Link Layer
**Main Function:**
- Provides node-to-node data transfer
- Uses **MAC addresses**
- Detects and corrects errors from the physical layer

**Devices:**
- Switches, bridges


### 1️⃣ Physical Layer
**Main Function:**
- Transmits raw binary data (0s and 1s)
- Defines cables, connectors, voltages, and transmission media

**Examples:**
- Ethernet cables
- Fiber optic cables


## Easy Memory Trick

**All People Seem To Need Data Processing**  
(Application → Physical)

---

## Why the OSI Model is Important

- Helps understand network communication clearly
- Useful for troubleshooting network issues
- Forms the foundation for cybersecurity concepts
