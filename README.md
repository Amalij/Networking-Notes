# Basic Networking Notes

## 1. What is a Network?
A network is a connection of two or more computers/devices that communicate with each other to share data and resources.

- Communication happens using binary data (0s and 1s)

---

## 2. What is Cisco Packet Tracer?
Cisco Packet Tracer is a network simulation tool used to design and test networks logically without physical devices.

---

## 3. Types of Networks

- LAN (Local Area Network): 
  A network within a small area such as a building (e.g., hospital, office with 20–30 computers)

- WAN (Wide Area Network): 
  A large network that covers a wide area (e.g., the Internet)

- MAN (Metropolitan Area Network): 
  Connects multiple networks within a city

- PAN (Personal Area Network): 
  Small network for personal devices (e.g., mobile, laptop at home)

- WLAN (Wireless LAN): 
  LAN that uses wireless communication (Wi-Fi)

- CAN (Campus Area Network): 
  Network across a campus (e.g., university)

---

## 4. Network Devices

### Hub
- Old device, rarely used now
- Not intelligent
- Sends data (packets) to all connected devices

  <img width="1365" height="720" alt="image" src="https://github.com/user-attachments/assets/18b8266e-0d3f-4a82-ab8a-61e77087747d" />


### Switch
- Intelligent device
- Learns MAC addresses
- Sends data only to the correct device
- Mainly used in LAN
- Uses frames
<img width="1360" height="718" alt="image" src="https://github.com/user-attachments/assets/3ae7725f-292b-43fa-8c3d-7602fc94b4cf" />

### Router
- Connects different networks
- Uses IP addresses
- Transfers data using packets

---
## ipconfig
- Used to display IP address and network details of a computer

- # Ports and Protocols  

## 1. What are Ports?
Ports are communication endpoints used by computers to send and receive data.

- Each service uses a specific port number
- Example: Web browsing, email, file transfer

---

## 2. Port Number Ranges

### 1. Well-Known Ports (0 – 1023)
- Used by system or common services
- Reserved for important protocols

Examples:
- HTTP – Port 80
- HTTPS – Port 443
- FTP – Port 21
- DNS – Port 53

---

### 2. Registered Ports (1024 – 49151)
- Used by user applications
- Not as strictly controlled as well-known ports

---

### 3. Dynamic / Private Ports (49152 – 65535)
- Temporary ports
- Used for short-term communication (client-side)

---

## 3. What are Protocols?
Protocols are rules that define how data is transmitted over a network.

Examples:
- HTTP – Used for web browsing
- HTTPS – Secure web browsing
- FTP – File transfer
- DNS – Domain name system

---

## 4. Server
A server is a computer or system that provides services to other computers (clients).

Examples:
- File server – stores files
- Web server – hosts websites
- Database server – manages data

---

## 5. DNS (Domain Name System)
DNS converts human-readable domain names into IP addresses.

Example:
google.com → 142.250.x.x (IP address)

---

## 6. Useful Command

### nslookup
Used to find the IP address of a domain name.

Example:
nslookup google.com

Output:
Displays the IP address of the website
