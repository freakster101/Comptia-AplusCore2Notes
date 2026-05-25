# 2.2 Configure and Apply Basic Microsoft Windows OS Security Settings

# Defender Antivirus

## Activate/Deactivate
Enables or disables built-in Windows malware protection.  
Example: Turning on Microsoft Defender Antivirus in Windows Security.

## Update Definitions
Downloads latest malware signatures to detect new threats.  
Example: Updating Defender before running a virus scan.

---

# Firewall

## Activate/Deactivate
Enables or disables Windows Firewall protection for network traffic.  
Example: Turning on Windows Defender Firewall for public networks.

## Port Security
Controls which network ports are allowed or blocked.  
Example: Blocking inbound port 23 (Telnet).

## Application Security
Controls which applications can communicate through the firewall.  
Example: Allowing Zoom through Windows Firewall.

---

# User and Groups

## Local vs. Microsoft Account
Local accounts exist only on one PC, while Microsoft accounts sync across devices and services.  
Example: Logging into Windows with Outlook/Microsoft account.

## Standard Account
User account with limited permissions for everyday tasks.  
Example: Employee account without software installation rights.

## Administrator
Account with full system control and elevated privileges.  
Example: IT admin installing drivers and software.

## Guest User
Temporary account with very limited permissions.  
Example: Visitor using shared office computer.

## Power User
Legacy Windows group with more rights than standard users but fewer than administrators.  
Example: Advanced user managing some system settings.

---

# Log-in OS Options

## Username and Password
Traditional authentication using account name and password.  
Example: Logging into Windows with credentials.

## Personal Identification Number (PIN)
Numeric login method tied to a specific device.  
Example: Windows Hello PIN login.

## Fingerprint
Biometric authentication using fingerprint scanning.  
Example: Unlocking laptop with fingerprint reader.

## Facial Recognition
Biometric login using facial recognition technology.  
Example: Windows Hello face unlock.

## Single Sign-on (SSO)
Allows one login session for multiple systems or applications.  
Example: Logging into Microsoft 365 once for Outlook and Teams.

## Passwordless/Windows Hello
Authentication without traditional passwords using biometrics or PINs.  
Example: Signing in with face recognition only.

---

# NTFS vs. Share Permissions

## NTFS Permissions
Permissions applied directly to files and folders on NTFS drives.  
Example: User allowed to read but not delete a folder.

## Share Permissions
Permissions controlling network access to shared folders.  
Example: Shared folder allowing read-only network access.

## File and Folder Attributes
Special properties controlling file behavior and visibility.  
Example: Marking a file as hidden or read-only.

## Inheritance
Child folders/files automatically receive parent permissions.  
Example: Subfolder inheriting permissions from main department folder.

---

# Run as Administrator vs. Standard User

## Run as Administrator
Temporarily launches application with elevated privileges.  
Example: Running Command Prompt as administrator.

## Standard User
Runs applications with limited permissions for safer operation.  
Example: Employee using normal account for daily work.

---

# User Account Control (UAC)

## User Account Control (UAC)
Security feature prompting users before administrative changes occur.  
Example: UAC popup asking permission to install software.

---

# BitLocker

## BitLocker
Full-disk encryption protecting entire Windows drives.  
Example: Encrypting company laptop SSD with BitLocker.

---

# BitLocker-To-Go

## BitLocker-To-Go
Encrypts removable drives like USB flash drives.  
Example: Encrypting confidential files on USB drive.

---

# Encrypting File System (EFS)

## Encrypting File System (EFS)
Encrypts individual files and folders within NTFS volumes.  
Example: Encrypting HR payroll folder only.

---

# Active Directory

## Joining Domain
Adds computer to centralized Active Directory environment.  
Example: Joining office PC to company domain.

## Assigning Log-in Script
Automatically runs scripts when users log into domain accounts.  
Example: Mapping network drives at login.

## Moving Objects within Organizational Units
Organizes users/computers into administrative containers.  
Example: Moving HR users into HR OU.

## Assigning Home Folders
Provides users with centralized personal network storage.  
Example: Employee home drive mapped as H:\.

## Applying Group Policy
Applies centralized configuration and security settings to systems/users.  
Example: Enforcing password complexity through Group Policy.

## Selecting Security Groups
Assigns permissions based on group membership.  
Example: Accounting group accessing finance folder only.
