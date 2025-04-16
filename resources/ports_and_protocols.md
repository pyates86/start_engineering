# Network Ports and their associated Protocols

Below is a list of the top 30 network ports and their associated protocols, along with brief explanations of their uses. These ports are commonly used in networking, security, and system administration, and they are often prioritized in network monitoring and firewall configurations.

## Port 20 \- FTP (File Transfer Protocol, Data)  
**Use**: Transfers file data between client and server in FTP sessions (unencrypted).  

## Port 21 \- FTP (File Transfer Protocol, Control)  
**Use**: Manages FTP session commands (e.g., authentication, file listing) for file transfers.  

## Port 22 \- SSH (Secure Shell) / SCP / SFTP**  
**Use**: Provides secure remote access for command-line management and secure file transfers.  

## Port 23 \- Telnet**  
**Use**: Enables remote access to devices for command-line management (unencrypted, less secure than SSH).  

## Port 25 \- SMTP (Simple Mail Transfer Protocol  
**Use**: Sends emails from clients to servers or between servers (unencrypted unless paired with TLS).  

## Port 53 \- DNS (Domain Name System  
**Use**: Resolves domain names to IP addresses for internet navigation (uses UDP or TCP).  

## Port 80 \- HTTP (Hypertext Transfer Protocol  
**Use**: Transfers unencrypted web pages and data for web browsing.  

## Port 110 \- POP3 (Post Office Protocol v3  
**Use**: Retrieves emails from a server, typically deleting them after download (unencrypted unless secured).  

## Port 123 \- NTP (Network Time Protocol  
**Use**: Synchronizes system clocks across networks for accurate timekeeping (uses UDP).  

## Port 137 \- NetBIOS (Name Service  
**Use**: Resolves names in Windows networks for file and printer sharing (part of NetBIOS over TCP/IP).  

## Port 138 \- NetBIOS (Datagram Service  
**Use**: Handles connectionless data exchange in Windows networks (e.g., broadcasts).  

## Port 139 \- NetBIOS (Session Service  
**Use**: Manages connection-oriented communication for Windows file and printer sharing.  

## Port 143 \- IMAP (Internet Message Access Protocol  
**Use**: Retrieves emails while keeping them on the server for multi-device access.  

## Port 161 \- SNMP (Simple Network Management Protocol  
**Use**: Monitors and manages network devices (e.g., routers, switches) using UDP.  

## Port 162 \- SNMPTRAP (SNMP Trap  
**Use**: Sends alerts from network devices to management systems about issues or events (UDP).  

## Port 389 \- LDAP (Lightweight Directory Access Protocol  
**Use**: Accesses and manages directory services, such as user authentication in Active Directory.  

## Port 443 \- HTTPS (HTTP Secure  
**Use**: Transfers encrypted web data using SSL/TLS (e.g., secure websites).  

## Port 445 \- SMB (Server Message Block  
**Use**: Enables file and printer sharing, primarily in Windows networks.  

## Port 465 \- SMTPS (SMTP Secure  
**Use**: Sends encrypted emails using SSL/TLS (legacy, often replaced by STARTTLS on port 587).  

## Port 514 \- Syslog**  
**Use**: Collects and sends system log messages for monitoring and troubleshooting (uses UDP).  

## Port 587 \- SMTP (Submission  
**Use**: Submits emails from clients to servers, often with STARTTLS encryption.  

## Port 636 \- LDAPS (LDAP Secure  
**Use**: Provides encrypted access to directory services using SSL/TLS.  

## Port 993 \- IMAPS (IMAP Secure  
**Use**: Retrieves emails securely over SSL/TLS, keeping them on the server.  

## Port 995 \- POP3S (POP3 Secure  
**Use**: Retrieves emails securely over SSL/TLS, typically deleting them from the server.  

## Port 1433 \- MSSQL (Microsoft SQL Server  
**Use**: Connects to Microsoft SQL Server databases for data queries and management.  

## Port 1812 \- RADIUS (Authentication  
**Use**: Authenticates users in network access control (e.g., VPNs, Wi-Fi) using UDP.  

## Port 1813 \- RADIUS (Accounting  
**Use**: Tracks user activity and resource usage for billing or monitoring (UDP).  

## Port 3306 \- MySQL**  
**Use**: Connects to MySQL databases for data storage and retrieval.  

## Port 3389 \- RDP (Remote Desktop Protocol  
**Use**: Provides remote desktop access to Windows systems with a graphical interface.  

## Port 8080 \- HTTP (Alternate  
**Use**: Serves web content, often used for proxy servers, testing, or secondary web applications.

## Notes:

* These ports are critical for network services and are frequent targets for cyberattacks, so they’re often secured or restricted by firewalls.  
* Some protocols (e.g., FTP, Telnet, SMTP) are unencrypted by default but have secure alternatives (e.g., SFTP, SSH, SMTPS).  
* Ports can use TCP (connection-oriented) or UDP (connectionless), depending on the protocol.

