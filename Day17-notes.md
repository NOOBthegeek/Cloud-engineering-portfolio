Day 17 - Security Groups

My inbound rules:
- SSH (Port 22) for remote server access.
- HTTP (Port 80) for website traffic.

What I learned:
- Security Groups are virtual firewalls.
- Inbound rules control incoming traffic.
- Outbound rules control outgoing traffic.
- My EC2 instance only allows the traffic I explicitly permit.

- Linux Firewall Check

Command:
sudo systemctl status firewalld

Result:
Unit firewalld.service could not be found.

What I learned:
- Amazon Linux may not have firewalld installed.
- AWS Security Groups act as the primary firewall.
- My EC2 instance is protected by Security Group rules.
- Apache is still accessible because port 80 is allowed.
