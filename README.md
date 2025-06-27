# Task-4 Firewall-Configuration

## Objective:
To configure a basic firewall using UFW (Uncomplicated Firewall) on Kali Linux. The goal was to demonstrate control over inbound traffic using simple firewall rules.

## 🛠 Tools Used:
- UFW (Firewall interface for iptables)
- Kali Linux (Virtual Machine)

## Steps Performed:

1. Installed and enabled UFW
2. Checked the initial firewall status
3. Denied access to port 23 (Telnet)
4. Allowed access to port 22 (SSH)
5. Verified firewall rules using `ufw status verbose`
6. Deleted the Telnet deny rule to demonstrate rule removal

## Screenshots:
- `firewall_block.png`: Shows UFW rule denying Telnet (port 23)
- `firewall_allow.png`: Shows rule allowing SSH (port 22)
- `firewall_remove.png`: Shows deletion of port 23 deny rule

## Outcome:
Successfully learned how to add, view, and remove firewall rules using UFW. This task demonstrated how firewalls can restrict unnecessary services and reduce attack surface.
