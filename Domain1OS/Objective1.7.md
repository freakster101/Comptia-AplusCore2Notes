# Given a scenario, configure Microsoft Windows networking features on a client/desktop

# Domain Joined vs. Workgroup

## Shared Resources
Allows users to access shared files, folders, and devices across a network.  
Example: Employees accessing a shared company folder.

## Printers
Network printers can be shared among multiple users and systems.  
Example: Office staff printing to one shared printer.

## File Servers
Centralized servers used to store and manage files for network users.  
Example: Company documents stored on a Windows Server file server.

## Mapped Drives
Assigns a drive letter to a shared network folder for easier access.  
Example: Mapping `Z:` drive to a shared office folder.

# Local OS Firewall Settings

## Application Restrictions and Exceptions
Controls which applications are allowed through the firewall.  
Example: Allowing Zoom through Windows Defender Firewall.

## Configuration
Customizes firewall profiles and security rules.  
Example: Blocking inbound connections on public Wi-Fi.

# Client Network Configuration

## Internet Protocol (IP) Addressing Scheme
Defines how devices receive and use IP addresses on a network.  
Example: A PC using IP address `192.168.1.10`.

## Domain Name System (DNS) Settings
Converts domain names into IP addresses for network communication.  
Example: Using Google DNS `8.8.8.8`.

## Subnet Mask
Separates the network portion and host portion of an IP address.  
Example: `255.255.255.0` used in small office networks.

## Gateway
The router address used to reach other networks or the internet.  
Example: Default gateway `192.168.1.1`.

## Static vs. Dynamic
Static IPs are manually assigned while dynamic IPs are automatically assigned by DHCP.  
Example: Servers often use static IPs while laptops use DHCP.

# Establish Network Connections

## Virtual Private Network (VPN)
Creates a secure encrypted connection over the internet.  
Example: Employee connecting securely to office resources from home.

## Wireless
Connects devices using Wi-Fi instead of cables.  
Example: Laptop connected to home Wi-Fi.

## Wired
Connects devices using Ethernet cables for stable networking.  
Example: Desktop PC connected using Cat6 cable.

## Wireless Wide Area Network (WWAN)/Cellular Network
Uses mobile carrier networks for internet access.  
Example: Laptop using 5G mobile hotspot connectivity.

# Proxy Settings
Uses an intermediary server between a client and the internet.  
Example: Company proxy filtering employee web traffic.

# Public Network vs. Private Network

## Public Network
More restrictive network profile designed for untrusted locations.  
Example: Airport Wi-Fi configured as Public.

## Private Network
Less restrictive profile intended for trusted home or office networks.  
Example: Home Wi-Fi configured as Private.

# File Explorer Navigation – Network Paths
Uses UNC paths to access shared network resources.  
Example: `\\Server01\SharedFiles`

# Metered Connections and Limitations
Limits background data usage on networks with restricted bandwidth.  
Example: Setting mobile hotspot connection as metered to reduce Windows updates.
