# 1.2 Given a scenario, perform OS installations and upgrades in a diverse environment.
## Boot methods
### Universal Serial Bus (USB)
Installing an OS using a bootable flash drive.
````bash
Example: Installing Windows 11 from a USB stick.
````

### Network
Booting and installing an OS through a network server.
````bash
Example: PXE boot deployment in a company office.
````

### Solid-state/flash drives
Installing or booting an OS from SSDs or flash storage devices.
````bash
Example: Ubuntu running from an NVMe SSD.
````

### Internet-based
Installing an operating system directly from the internet.
````bash
Example: ChromeOS recovery installation online.
````

### External/hot-swappable drive
Using removable drives that can be connected without shutting down the system.
````bash
Example: Booting Linux from an external USB SSD.
````

### Internal hard drive (partition)
Installing multiple operating systems on different partitions of the same drive.
````bash
Example: Windows on C: partition and Linux on another partition.
````

### Multiboot 
A system configured to choose between multiple operating systems during startup.
````bash
Example: Dual booting Windows 11 and Ubuntu.
````

## Types of installations
### Clean install
Installing an OS from scratch while removing old files and settings.
````bash
Example: Formattng a drive before installing Windows 11.
````

### Upgrade
Installing a newer os version while keeping files and Applications.
````bash
Example: Upgrading Windows 10 to Windows 11.
````

### Image deployment
Deploying a preconfigured OS image to multiple computers.
````bash
Example: IT department cloning Windows to 50 PCs.
````

### Remote network installation
Installing an OS remotely over a network connection.
````bash
Example: Installing Linux servers from a central deployment server.
`````

### Zero-touch deployment
Automated OS installation with little or no user interaction.
````bash
Example: Microsoft Autopilot configuring laptops automatically.
````

### Recovery partition
A hidden partition containing recovery tools for reparing or reinstalling the OS.
````bash
Example: Factory reset option on a  laptop.
````

### Repair installation
Reinstalling OS components without deleting personal files.
```bash
Example: Windows repair upgrade fixing corrupted system files.
````

### Other considerations 
#### Third-party drivers
Extra drivers needed for hardware not supported natively by the OS.
````bash
Example: Installing NVIDIA GPU drivers after Windows installation.
````

## Partitioning
### GUID [globally unique identifier] Partition Table (GPT)
Modern partitioning method supporting large drives and UEFI systems.
```bash
Example: Windows 11 installed on a GPT disk.
````

### Master boot record (MBR)
Older partitioning method with a 2TB drive limit.
````bash
Example: Windows 7 installed on an MBR disk.
````

## Drive format
Preparing a storage device with a file system before use.
```bash
Example: Formatting a USB drive to exFAT.
````

## Upgrade considerations
### Backup files and user preferences
Saving important data before upgrading or reinstalling the OS.
````bash
Example: Backing up documents to OneDrive before upgrading Windows.
````

### Application and driver support/backward compatibility
Checking whether software and drivers work with the new OS version.
````bash
Example: Old printer drivers not working on Windows 11.
````
### Hardware compatibility
Verifying that hardware meets OS requirements.
````bash
Example: Windows 11 requiring TPM 2.0 support.
````
## Feature updates
Major OS updates that add new features and improvements.
````bash
Example: Windows 11 yearly feature update.
````

### Product life cycle
The support period during which the vendor provides updates and patches.
````bash
Example: Windows 10 reaching end-of-support in 2025.
````
