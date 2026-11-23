# NETWORKING COMMANDS – KALI LINUX LAB NOTES

## 1. Introduction
Networking commands are used to check network connectivity, view IP addresses, monitor network connections, and trace the path between devices. In Kali Linux, these commands help users understand network configuration and troubleshoot network-related problems.

## 2. ifconfig – Network Interface Configuration
**Purpose:** Displays information about network interfaces, including IP address, netmask, MAC address, and interface status.

**Command:**
ifconfig

**Observation:** The command displays available network interfaces, their IP addresses, and network configuration details.

## 3. ping – Network Connectivity Testing
**Purpose:** Checks whether a target device or server is reachable over the network.

**Command:**
ping -c 4 8.8.8.8

**Observation:** The command sends four ICMP packets to the destination IP address and displays the response time and packet loss information. Successful replies indicate connectivity to the destination.

## 4. netstat – Network Statistics
**Purpose:** Displays active network connections, listening ports, and network statistics.

**Command:**
sudo netstat -tulnp

**Observation:** The command displays TCP and UDP ports, listening services, local addresses, and process information where available.

## 5. traceroute – Network Route Tracing
**Purpose:** Identifies the path taken by packets to reach a destination network.

**Command:**
traceroute google.com

**Observation:** The command displays intermediate routers (hops) between the Kali Linux system and the destination, along with response times.

## 6. ip addr – IP Address Information
**Purpose:** Displays IP addresses and network interface information.

**Command:**
ip addr

**Observation:** The command displays network interfaces, assigned IPv4 and IPv6 addresses, and interface status.

## 7. Conclusion
The networking commands were practised successfully in Kali Linux. These commands help identify network configurations, test connectivity, inspect listening ports, and analyse network paths. They are essential for basic network troubleshooting and cybersecurity practical activities.
