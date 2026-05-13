# Denial of Service (DoS) and Distributed Denial of Service (DDoS)

A Denial of Service (DoS) attack is an attack designed to make:
- a computer
- server
- website
- application
- or network resource

unavailable to legitimate users.

The goal is to:
- overload the target
- exhaust system resources
- disrupt normal operations

---

# 1. Denial of Service (DoS)

## Definition
A DoS attack attempts to:
- flood a target with requests
- consume resources
- prevent legitimate access

---

## Main Goal
Create a:
- denial of service condition

where real users cannot access the system.

---

## Common Targets
- Web servers
- Applications
- Routers
- Switches
- DNS servers
- Networks

---

# Example of a DoS Attack

Attacker sends:
- massive numbers of requests

to a server.

Example:
- 12 requests → normal
- 12,000 requests → may overload server

Result:
- server slows down
- crashes
- or becomes unavailable

---

# 2. SYN Flood Attack

## Definition
A SYN flood is a DoS attack targeting the TCP three-way handshake.

---

# TCP Three-Way Handshake

Normal process:
1. SYN
2. SYN-ACK
3. ACK

Connection established.

---

# How SYN Flood Works

Attacker:
- sends many SYN requests
- uses fake/spoofed IP addresses

Server:
- replies with SYN-ACK
- waits for ACK response

But:
- ACK never arrives

Result:
- server wastes resources
- connection table fills up
- legitimate users cannot connect

---

# Key Exam Point

### SYN Flood
= incomplete TCP handshakes exhaust server resources

---

# Characteristics of DoS Attacks

A DoS attack may:
- slow systems down
- crash services
- exhaust bandwidth
- consume memory/resources
- prevent normal access

---

# 3. Distributed Denial of Service (DDoS)

## Definition
A DDoS attack uses:
- hundreds
- thousands
- or millions of systems

to attack a single target simultaneously.

---

# Key Difference

| Attack Type | Number of Attackers |
|---|---|
| DoS | One attacking system |
| DDoS | Many attacking systems |

---

# Botnets

Most DDoS attacks use:
- botnets

A botnet is:
- a group of infected devices
- controlled remotely by an attacker

---

# Bots / Zombies

Compromised systems in a botnet are called:
- bots
- zombies

Most owners do not realize:
- their systems are infected
- or participating in attacks

---

# DDoS Process

1. Devices infected with malware
2. Systems become bots/zombies
3. Attacker controls botnet
4. Botnet attacks target simultaneously
5. Server overwhelmed

---

# Why DDoS Is Dangerous

DDoS attacks:
- generate massive traffic
- consume bandwidth
- overwhelm infrastructure
- are difficult to block completely

---

# 4. DNS Amplification Attack

## Definition
A DNS amplification attack is a specialized DDoS attack.

Uses:
- spoofed IP addresses
- DNS servers
- amplification techniques

---

# How DNS Amplification Works

1. Attacker spoofs victim IP address
2. Sends small DNS requests
3. DNS server sends much larger responses
4. Responses flood victim server

---

# Why It Is Called "Amplification"

Small request:
- creates large response

Result:
- attack traffic amplified dramatically

---

# Key Exam Point

### DNS Amplification
= attacker uses DNS responses to massively increase attack traffic

---

# Real-World Example

In 2018:
- GitHub suffered a massive DDoS attack

Attack traffic reached:
- 1.35 terabits per second

Result:
- GitHub offline temporarily

---

# 5. Defending Against DoS/DDoS

# Blackholing / Sinkholing

## Definition
Traffic from attacking IPs is redirected to:
- null interface
- non-existent destination

Result:
- malicious traffic discarded

---

## Limitation
Attackers may:
- switch IP addresses
- restart attack

Usually temporary mitigation only.

---

# Intrusion Prevention Systems (IPS)

IPS can:
- detect attacks
- block malicious traffic automatically

Works best against:
- small-scale attacks

---

## Limitation
Large DDoS attacks may overwhelm IPS capacity.

---

# Elastic Cloud Infrastructure

## Definition
Cloud systems automatically scale resources during attacks.

Examples:
- more bandwidth
- additional servers
- increased processing power

---

## Advantage
Can survive traffic spikes during DDoS attacks.

---

## Disadvantage
Scaling resources:
- increases operational cost
- attacker may cause expensive cloud bills

---

# DDoS Protection Providers

Specialized providers:
- Cloudflare
- Akamai

help organizations:
- absorb DDoS traffic
- filter malicious requests
- maintain availability

---

# Content Delivery Networks (CDN)

CDNs distribute content across multiple servers.

Benefits:
- load balancing
- redundancy
- DDoS resistance
- improved availability

---

# Key Exam Concepts

## DoS
= one system attacks one target

---

## DDoS
= many systems attack one target

---

## SYN Flood
= incomplete TCP handshakes

---

## Botnet
= network of infected devices

---

## Zombie/Bot
= infected system controlled remotely

---

## DNS Amplification
= small DNS requests create huge responses

---

# Fast Active Recall

## DoS
Think:
- resource exhaustion
- service unavailable

---

## DDoS
Think:
- botnet
- massive coordinated attack

---

## SYN Flood
Think:
- TCP handshake never completed

---

## Botnet
Think:
- infected zombie devices

---

## DNS Amplification
Think:
- spoofed DNS requests
- amplified responses

---

# Final Exam Takeaways

## If you see:
- one attacker flooding server

→ Think: **DoS**

---

## If you see:
- thousands of infected systems attacking simultaneously

→ Think: **DDoS**

---

## If you see:
- incomplete TCP handshakes
- SYN packets without ACK

→ Think: **SYN Flood**

---

## If you see:
- infected zombie devices
- remotely controlled systems

→ Think: **Botnet**

---

## If you see:
- spoofed DNS requests
- amplified traffic

→ Think: **DNS Amplification Attack**

---

# Ultimate Memory Shortcut

| Attack | Quick Memory |
|---|---|
| DoS | One attacker floods target |
| DDoS | Many attackers flood target |
| SYN Flood | Half-open TCP connections |
| Botnet | Army of infected devices |
| DNS Amplification | Small request → huge response |

---

# Simple Exam Memory Phrase

> DoS overwhelms one target.  
> DDoS overwhelms it with an army.
