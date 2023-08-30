# Network
A network is simply two or more computers linked together to share data, information or resources.

## Local Area Network
Typically Spans over a single floor or building

## Wide Area Network
A collection of LANs

***

# Network Devices

## Hub (Old)
Hubs perform on half duplex mode which is bad

## Switches (Generally used)
Switch perform on full duplex mode too

## Router 
Control the traffic flow in a subnet of devices

## Firewall
A barrier to our network (in most cases Private Network)

### Stateful Firewall
Maintains a table called state table, that records the current state of each connection. It compares each packet against the entries in the state table to determine if it's part of an existing and legitimate connection.

### Stateless Firewall 
Unlike stateful firewall it doesn't maintain any state table instead it filters each packet individually based on predefined set of rules.

## Server
A server is a computer that provides information to other servers

## Endpoints
Ends of network communication Web Server -> Client, both of them are considered as end points.

***

# Network Models

OSI Model (7 layered)

7. Applicaton
6. Presentation
5. Session
4. Transport
3. Network
2. Data Link 
1. Physical

TCP IP Model (4 layers or 5 layers)

- Can be considered as vendor specific
- Data gets encapsulated and decapsulated

***

# Internet Protocols

## IPv4
xxx.xxx.xxx.xxx -> 32bit address used to identify a network device

## IPv6
Improved version to connect more users when compared to IPv4
xxxx.xxxx.xxxx.xxxx.xxxx.xxxx.xxxx.xxxx -> 128bit address which servers same purpose as IPv4

2001:0db8:0000:0000:0000:ffff:0000:0001. To make it easier for humans to read and type, it can be shortened by removing the leading zeros at the beginning of each field and substituting two colons (::) for the longest consecutive zero fields. All fields must retain at least one digit. After shortening, the example address above is rendered as 2001:db8::ffff:0:1, which is much easier to type. As in IPv4, there are some addresses and ranges that are reserved for special uses:

::1 is the local loopback address, used the same as 127.0.0.1 in IPv4.
The range 2001:db8:: to 2001:db8:ffff:ffff:ffff:ffff:ffff:ffff is reserved for documentation use, just like in the examples above.
fc00:: to fdff:ffff:ffff:ffff:ffff:ffff:ffff:ffff are addresses reserved for internal network use and are not routable on the internet.

***

# Secure Ports

23 Telnet - 22 SSH
21 FTP - 22 SFTP - SSH over FTP
37 Time - 123 NTP
53 DNS - 853 DoT - DNS over TLS
80 HTTP - 443 HTTPS - SSL/TLS
143 IMAP - 993 IMAP - IMAP for SSL/TLS
445 SMB - 2049 NFS 
389 LDAP - 636 LDAPS - Secured version
