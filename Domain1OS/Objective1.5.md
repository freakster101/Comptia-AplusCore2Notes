# 1.4 Given a scenario, use the appropriate Microsoft command-line tools.
## Navigation
### cd
Changes the current directory in Command Prompt.
````bash
Example: cd Documents moves into the Documents folder.
````

### dir
Displays files and folders inside the current directory.
````bash
Example: dir lists all files in the folder.
````

## Network
### ipconfig
Displays IP configuration information for network adapters.
````bash
Example: ipconfig /all shows IP address, DNS, and MAC address.
````
### ping
Tests network connectivity between devices.
````bash
Example: ping google.com checks internet connectivity.
````

### netstat
Displays active network connections and listening ports
````bash
Examples: netstat -an shows open ports and connections.
````

### nslookup
Queries DNS servers to find domain IP addresses.
````bash
Example: nslookup openai.com finds the IP of OpenAI's website.
````

### net use
Connects to or manages shared network resources.
````bash
Example: net use Z: \\server\Files maps a network drive.
````
### tracert
Shows the route packets take to reach a destination.
````bash
Example: tracert google.com traces network hops.
````

### pathping
Combines ping and tracert to analyze packet loss and latency.
````bash
Example: pathping 8.8.8.8 checks network reliability.
````

## Disk management
### chkdsk
Scans and repairs disk file system errors.
````bash
Example: chkdsk C: /f fixes drive errors.
````
### format
Erases and prepares a drive with a new file system.
````bash
Example: format D: formats the D drive.
````

### diskpart
Advanced disk partition management command-line tool.
````bash
Example: Using diskpart to create a new partion.
````

##  File management
### md
Creates a new directory or folder.
````bash
Example: md Backup creates a folder named Backup.
````

### rmdir
Deletes an empty directory or folder
````bash
Example: rmdir OldFiles removes the OldFiles folder.
````

### robocopy
Copies files and folders with advanced synchronization features.
````bash 
Example: robocopy C:\data D:\Backup /MIR mirrors files to backup storage.
````

## Informational
### hostname
Displays the computer's name on the network.
````bash
Example: hostname shows the PC name.
````

### net user
Displays or manages user accounts on the system.
````bash
Example: net user lists local user accounts.
````
### winver
Shows the installed Windows version information.
````bash
Example: winver opens the windows version window.
````

### whoami
Displays the currently logged-in user account.
````bash
Example: whoami shows the active username.
`````

### [command name] /?
Displays help information for a command.
````bash
Example: ipconfig /? shows ipconfig option.
````

## OS management
− gpupdate
Refreshes Group Policy settings immediately.
````bash
Example: gpupdate /force applies new policies instantly.
````

### gpresult
Displays applied Group Policy information for a user or computer.
````bash
Example: gpresult /r shows active group policies.
````

− sfc
Scans and repairs corrupted Windows system files.
````bash
Example: sfc /scannow repairs damaged system files.
````
