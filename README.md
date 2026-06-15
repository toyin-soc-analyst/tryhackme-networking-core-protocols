# tryhackme-networking-core-protocols
Hands-on TryHackMe lab covering WHOIS, HTTP, FTP, POP3, IMAP, and Telnet with practical protocol analysis, file retrieval, and email investigation exercises.
Networking Core Protocols – TryHackMe
Overview

This room provided practical experience interacting directly with core networking protocols and services commonly encountered in cybersecurity investigations and SOC environments.

The exercises included working with:

WHOIS
HTTP
FTP
POP3
IMAP
Telnet

The objective was to understand how these protocols function, how clients communicate with servers, and how information can be manually retrieved and analyzed.

Skills Practiced
WHOIS Enumeration

Performed domain registration lookups and analyzed registrar information, registration dates, ownership details, and domain metadata.

Screenshot 1

HTTP Protocol Analysis

Connected to a web server and manually examined HTTP response headers and HTML content to identify hidden information within a webpage.

Screenshot 2

FTP File Retrieval

Connected to an FTP server, enumerated available files, downloaded a target file, and verified its contents.

Screenshot 3

POP3 Email Retrieval

Authenticated to a POP3 mailbox and retrieved email messages manually through Telnet.

Located and extracted a flag from an email message.

Screenshot 4

IMAP Mailbox Interaction

Authenticated to an IMAP mailbox and used IMAP commands to browse and retrieve email content.

Practiced mailbox selection and message retrieval using FETCH commands.

Screenshot 5

Key Concepts Learned
Domain registration reconnaissance
HTTP request and response structure
FTP authentication and file transfer
POP3 mailbox access and message retrieval
IMAP mailbox management and email retrieval
Telnet-based protocol interaction
Manual service enumeration
Client-server communication fundamentals
Flags Retrieved
HTTP
THM{TELNET-HTTP}
FTP
THM{FAST-FTP}
POP3
THM{TELNET_RETR_EMAIL}
Tools Used
Telnet
FTP Client
WHOIS
POP3
IMAP
Linux Command Line
Outcome

Successfully completed all room objectives and gained practical experience with the core protocols frequently encountered in network analysis, incident response, phishing investigations, and SOC operations.

Platform: TryHackMe
Room: Networking Core Protocols
Status: Completed ✅
Points Earned: 88
