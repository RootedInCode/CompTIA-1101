# 🧠 20/6/25: CompTIA A+ 1101 (Core 1) — Networking Basics


## 🔌 Common Network Ports

| Port        | Protocol | Description                                                             |
| ----------- | -------- | ----------------------------------------------------------------------- |
| TCP 20/21   | FTP      | File Transfer Protocol – transfer files between systems                 |
| TCP 22      | SSH      | Secure Shell – encrypted remote login                                   |
| TCP 23      | Telnet   | Insecure remote login – plain text, avoid use                           |
| TCP 25      | SMTP     | Simple Mail Transfer Protocol – sending emails                          |
| UDP 53      | DNS      | Domain Name System – translates domain names to IP addresses            |
| UDP 67/68   | DHCP     | Dynamic Host Configuration Protocol – assigns IP addresses dynamically  |
| TCP 80      | HTTP     | HyperText Transfer Protocol – unencrypted web browsing                  |
| TCP 443     | HTTPS    | HTTP Secure – encrypted web browsing using SSL/TLS                      |
| TCP 110     | POP3     | Post Office Protocol 3 – downloads email from server                    |
| TCP 143     | IMAP     | Internet Message Access Protocol – reads/stores email on the server     |
| TCP 445     | SMB      | Server Message Block – file/printer sharing over a network (no NetBIOS) |
| TCP 137-139 | NetBIOS  | Legacy support for Windows network file sharing                         |
| UDP 161/162 | SNMP     | Simple Network Management Protocol – monitor/manage network devices     |
| TCP/UDP 389 | LDAP     | Lightweight Directory Access Protocol – directory services (e.g., AD)   |
| TCP 3389    | RDP      | Remote Desktop Protocol – remote access to Windows systems              |
\

---

## 🛠️ Network Devices

| Device       | Description                                                             |
|--------------|-------------------------------------------------------------------------|
| Hub          | Broadcasts to all devices                                               |
| Switch(2)       | Sends only to the target MAC address(uses ARP and maintains CAM table)  |
| Router(3)       | Connects networks; routes between subnets(configue default gateway in devices)      |
| Access Point | Provides wireless connectivity              |
| Modem        | Converts analog ↔ digital (ISP connection)  |
| Firewall     | Filters traffic based on rules              |

*Unmanaged switch : no snmp , all on one vlan

---

## 🌐 TCP/IP Basics

- **IP Address**: Unique identifier on a network
- **Subnet Mask**: Splits IP into network and host
- **Default Gateway**: Path to external networks
- **MAC Address**: Physical hardware ID (burned-in)



