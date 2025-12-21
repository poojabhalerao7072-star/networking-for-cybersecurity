# Network Devices

Network devices are hardware components that help connect, manage, and secure communication between devices in a network.

## 1. Hub
- A basic networking device
- Sends data to all connected devices
- Operates at **OSI Layer 1 (Physical Layer)**

**Security Note:**
- Very insecure
- Data can be easily intercepted
- Rarely used today

## 2. Switch
- Connects devices within a LAN
- Sends data only to the intended device using MAC addresses
- Operates at **OSI Layer 2 (Data Link Layer)**

**Security Note:**
- Vulnerable to MAC flooding
- Can be protected using port security

## 3. Router
- Connects different networks
- Routes data using IP addresses
- Operates at **OSI Layer 3 (Network Layer)**

**Security Note:**
- Can be attacked via routing attacks or misconfiguration
- Needs strong passwords and firmware updates

## 4. Firewall
- A security device that monitors and filters network traffic
- Can be hardware or software based

**Security Note:**
- Protects against unauthorized access
- Essential for network security

## 5. Modem
- Converts digital data to analog signals and vice versa
- Used to connect to Internet Service Providers (ISP)

**Security Note:**
- Should be secured to prevent ISP-level attacks

## Summary Table

| Device   | OSI Layer | Purpose |
|--------|----------|---------|
| Hub | Layer 1 | Broadcasts data |
| Switch | Layer 2 | Forwards using MAC |
| Router | Layer 3 | Routes using IP |
| Firewall | Multiple | Filters traffic |
| Modem | Layer 1/2 | ISP connectivity |
