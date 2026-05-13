# Domain 2.0 Scurity
This section contains the notes from the Jason Dion on udemy CompTIA A+ Core 2 (220-1202) Section 14.

## CIA Triad
Cofidentiality Integrity and Availability
# CIA Triad

The CIA Triad is one of the most important security concepts in IT certifications such as:
- CompTIA A+
- Network+
- Security+
- CISSP
- CEH

CIA stands for:
- Confidentiality
- Integrity
- Availability

These three principles form the foundation of information security.

---

# 1. Confidentiality

## Purpose
Protect data from unauthorized access or viewing.

### Main Question
> Who is allowed to see this information?

If unauthorized users can view sensitive data, confidentiality has failed.

---

## Physical Security Controls
Examples:
- Locked doors
- Fences
- Security guards
- CCTV cameras
- Safes

---

## Electronic Security Controls
Examples:
- Encryption
- Passwords
- Firewalls
- Multi-factor authentication (MFA)

---

## Key Exam Association
### Confidentiality = Encryption

If a CompTIA question asks:
> How do we protect confidentiality?

Look for:
- Encryption
- WPA2/WPA3
- VPN
- BitLocker
- HTTPS/TLS

---

## Confidentiality Breach Example

If encrypted data is stolen but cannot be decrypted:
- Confidentiality is NOT fully compromised.

If attacker gets:
- encrypted file
- AND decryption key

→ Confidentiality is compromised.

---

# 2. Integrity

## Purpose
Ensure data remains accurate, unchanged, and trustworthy.

### Main Question
> Has the data been altered?

---

## Real-World Example

Bank account:
- Original balance = $1000
- Modified balance = $10

This is an integrity failure.

---

## Methods Used for Integrity

### Hashing
Creates a unique digital fingerprint of data.

If:
- original hash = received hash

→ file has not changed.

Examples:
- MD5
- SHA-1
- SHA-256

---

### Checksums
Used during data transmission to verify data has not changed in transit.

---

## Key Exam Association
### Integrity = Hashing

If a CompTIA question asks:
> How do we verify file integrity?

Look for:
- Hash
- SHA
- MD5
- Checksum

---

## Integrity Failure

Occurs when data is:
- modified
- corrupted
- tampered with

Either:
- at rest (stored)
- in transit (moving across network)

---

# 3. Availability

## Purpose
Ensure systems and data are accessible when needed.

### Main Question
> Can users access the system when they need it?

---

## Main Concepts
- Uptime
- Reliability
- Redundancy
- Disaster recovery
- Backups

---

## Redundancy Examples
If one system fails, another system takes over.

Examples:
- Backup server
- Backup internet connection
- Redundant switches
- RAID storage
- UPS battery backup

---

## Key Exam Association
### Availability = Redundancy + Uptime

If a CompTIA question asks:
> How do we increase availability?

Look for:
- Redundancy
- Failover
- Backup systems
- Disaster recovery

---

## Availability Failure Example

If YouTube becomes inaccessible:
- users cannot access videos

→ availability failure.

---

# CIA Triad Balance

The CIA Triad is NOT always equally balanced.

Different organizations prioritize different components.

Examples:

## Bank
- High confidentiality
- High integrity
- Moderate availability

## Public Website
- High availability
- Lower confidentiality

## Military System
- Extremely high confidentiality

---

# Security vs Operations

Organizations must balance:
- security
- usability
- operational efficiency

More security often means:
- more restrictions
- slower operations

More convenience often means:
- less security

---

# Ultimate Exam Shortcut

| CIA Component | Main Keyword |
|---|---|
| Confidentiality | Encryption |
| Integrity | Hashing |
| Availability | Redundancy / Uptime |

---

# Fast Active Recall

## Confidentiality
Protects:
- unauthorized viewing

Main tools:
- encryption
- passwords
- MFA

---

## Integrity
Protects:
- data accuracy
- trustworthiness

Main tools:
- hashing
- checksums

---

## Availability
Protects:
- uptime
- accessibility

Main tools:
- redundancy
- backups
- failover systems

---

# Final Exam Takeaway

## If you see:
- Encryption
- WPA2/WPA3
- VPN
- BitLocker

→ Think: **Confidentiality**

---

## If you see:
- Hashing
- SHA-256
- MD5
- Checksums

→ Think: **Integrity**

---

## If you see:
- Redundancy
- Uptime
- Failover
- Disaster recovery

→ Think: **Availability**
