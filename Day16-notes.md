Day 16 - Networking Basics

Private IP: 172.31.40.80
Public IP: 16.171.8.62

What I learned:
- Private IPs are used inside AWS networks.
- Public IPs allow internet access.
- The loopback address 127.0.0.1 is used by the server itself.
- My EC2 network interface is ens5.

- Ports I found:

22 - SSH (remote server access)
80 - HTTP (website hosting)

What I learned:
- A port is like a door to a service.
- SSH uses port 22.
- Web servers commonly use port 80.
- The ss -tuln command shows which services are listening.

- Internet Connectivity Test

Command:
ping google.com

Results:
- 30 packets sent
- 30 packets received
- 0% packet loss
- Average response time: about 4 ms

What I learned:
- ping tests network connectivity.
- DNS translated google.com into an IP address.
- 0% packet loss means the connection is healthy.
- Low latency means fast communication.

- DNS Test

Command:
nslookup google.com

Results:
- AWS DNS Server: 172.31.0.2
- google.com resolved to 172.217.20.174
- IPv6 address was also returned

What I learned:
- DNS converts domain names into IP addresses.
- AWS provides an internal DNS server.
- Websites can have both IPv4 and IPv6 addresses.
