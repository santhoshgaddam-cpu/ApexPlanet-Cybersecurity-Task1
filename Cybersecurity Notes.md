# Cybersecurity Notes

## 1. Introduction to Cybersecurity

Cybersecurity is the practice of protecting computers, networks, servers, applications, and data from unauthorized access, cyberattacks, damage, theft, and misuse.

It helps individuals, businesses, colleges, and organizations protect their digital information and systems.

### Objectives of Cybersecurity
- Protect sensitive information.
- Prevent unauthorized access.
- Protect computers and networks from attacks.
- Maintain data privacy and confidentiality.
- Detect and respond to security incidents.
- Reduce the risk of data loss and financial damage.

### Why Cybersecurity Is Important
- Protects personal information.
- Prevents identity theft.
- Protects bank accounts and financial transactions.
- Secures business information.
- Prevents unauthorized access to systems.
- Protects websites and applications.

---

## 2. CIA Triad

The CIA Triad is the fundamental model of information security. It consists of three main principles.

### A. Confidentiality
Confidentiality means protecting information from unauthorized people.

**Example:** Only authorized employees can access company salary records.

Methods:
- Passwords
- Encryption
- Access control
- Multi-factor authentication

### B. Integrity
Integrity means ensuring that data is accurate and has not been changed without authorization.

**Example:** A bank transaction amount should not be modified by an unauthorized person.

Methods:
- Hashing
- Digital signatures
- File integrity monitoring

### C. Availability
Availability means ensuring that systems, applications, and information are accessible to authorized users when needed.

**Example:** A banking website should be available to customers when they need to use it.

Methods:
- Backups
- System maintenance
- Redundant servers
- Disaster recovery

---

## 3. Types of Cybersecurity

### 1. Network Security
Protects computer networks from unauthorized access, attacks, and misuse.

Examples:
- Firewalls
- Network monitoring
- Intrusion detection systems
- Secure Wi-Fi

### 2. Application Security
Protects software and web applications from security vulnerabilities.

Examples:
- Secure coding
- Input validation
- Authentication
- Software updates

### 3. Information Security
Protects information from unauthorized access, modification, disclosure, or destruction.

### 4. Cloud Security
Protects data, applications, and infrastructure hosted in cloud platforms.

### 5. Endpoint Security
Protects devices such as laptops, desktops, smartphones, and servers.

### 6. Identity and Access Management (IAM)
Controls who can access systems and what actions they are allowed to perform.

### 7. Operational Security (OPSEC)
Protects sensitive information through secure procedures, policies, and daily practices.

---

## 4. Common Cyber Threats

### 1. Malware
Malware is malicious software designed to damage computers, steal information, or gain unauthorized access.

Types of malware:

- Virus – attaches to files and spreads when infected files are executed.
- Worm – spreads between systems without requiring the same user actions as a typical virus.
- Trojan – disguises itself as legitimate software.
- Spyware – secretly collects information about a user.
- Ransomware – encrypts or blocks access to data and demands payment.
- Keylogger – records keyboard input to capture information.

### 2. Phishing
Phishing is a cyberattack in which attackers use fake emails, messages, or websites to trick people into revealing sensitive information.

Examples:
- Fake bank emails.
- Fake login pages.
- Fraudulent OTP requests.
- Fake job or internship messages.

Prevention:
- Verify the sender.
- Avoid suspicious links.
- Never share OTPs.
- Check website URLs carefully.

### 3. Brute-Force Attack
A brute-force attack attempts to guess a password by trying many possible combinations.

Prevention:
- Use strong passwords.
- Implement account lockout policies.
- Use multi-factor authentication.
- Limit login attempts.

### 4. Denial-of-Service (DoS)
A DoS attack attempts to make a website, server, or network unavailable by overwhelming it with requests or other disruptive traffic.

### 5. Distributed Denial-of-Service (DDoS)
A DDoS attack uses multiple systems to overwhelm a target with traffic or requests.

Difference:

- DoS: commonly originates from one attacking system.
- DDoS: uses multiple systems or devices.

### 6. Man-in-the-Middle (MITM)
An MITM attack occurs when an attacker secretly intercepts or potentially alters communication between two parties.

Prevention:
- Use HTTPS.
- Avoid unsecured public Wi-Fi for sensitive activity.
- Use secure encryption.
- Verify network authenticity.

### 7. SQL Injection
SQL Injection occurs when an attacker manipulates database queries through unsafe application input.

Possible impacts:
- Unauthorized data access.
- Data modification.
- Data deletion.
- Authentication bypass.

Prevention:
- Parameterized queries.
- Input validation.
- Secure database permissions.
- Avoid unsafe query construction.

### 8. Cross-Site Scripting (XSS)
XSS is a web security vulnerability that allows malicious scripts to execute in another user's browser through vulnerable web pages.

Types:
- Stored XSS
- Reflected XSS
- DOM-based XSS

Prevention:
- Output encoding.
- Input validation.
- Content Security Policy.
- Secure handling of user-generated content.

### 9. Social Engineering
Social engineering is the manipulation of people into revealing confidential information or performing unsafe actions.

Examples:
- Pretending to be technical support.
- Fake job recruiters.
- Impersonating bank employees.
- Asking for passwords or OTPs.

### 10. Insider Threat
An insider threat occurs when someone with legitimate access to an organization misuses that access, intentionally or accidentally.

---

## 5. Ethical Hacking

Ethical hacking is the authorized process of testing computers, networks, applications, and systems to identify security weaknesses before malicious attackers exploit them.

Ethical hackers must have permission to test the systems.

### Types of Hackers

**White Hat Hacker**
An authorized security professional who identifies and fixes vulnerabilities.

**Black Hat Hacker**
A malicious attacker who exploits systems for unauthorized purposes.

**Gray Hat Hacker**
A person who may discover or test vulnerabilities without authorization but is not necessarily motivated by malicious intent.

### Ethical Hacking Phases

1. Reconnaissance – gathering information about the target.
2. Scanning – identifying systems, services, and potential weaknesses.
3. Enumeration – collecting more detailed information about discovered systems.
4. Vulnerability Assessment – identifying and analyzing security weaknesses.
5. Exploitation – validating a vulnerability within the authorized scope.
6. Reporting – documenting findings, evidence, risk, and remediation.

**Important:** Only perform security testing on systems you own or have explicit permission to test.

---

## 6. Linux Basics for Cybersecurity

Linux is an open-source operating system widely used in servers, cybersecurity, cloud computing, and penetration testing.

Kali Linux is a Linux distribution designed for cybersecurity testing and security research.

### Basic Linux Commands

| Command | Description |
|---|---|
| `pwd` | Displays the current directory |
| `ls` | Lists files and directories |
| `ls -la` | Lists all files including hidden files |
| `cd` | Changes the current directory |
| `mkdir` | Creates a new directory |
| `touch` | Creates an empty file |
| `cat` | Displays file contents |
| `nano` | Opens a text editor in the terminal |
| `cp` | Copies files or directories |
| `mv` | Moves or renames files |
| `rm` | Removes files |
| `clear` | Clears the terminal screen |
| `whoami` | Displays the current username |
| `uname -a` | Displays system information |
| `ip a` | Displays network interfaces and IP addresses |
| `ping` | Tests network connectivity |
| `sudo` | Executes a command with elevated privileges |
| `man` | Opens the manual for a command |

### Linux File Permissions

Linux uses permissions to control who can read, write, or execute files.

Three permission categories:

- `u` – User/owner
- `g` – Group
- `o` – Others

Three basic permissions:

- `r` – Read
- `w` – Write
- `x` – Execute

Example:

`- rwx r-x r--`

Meaning:

- Owner: read, write, execute.
- Group: read, execute.
- Others: read only.

---

## 7. Networking Basics

Networking allows computers and devices to communicate and share information.

### IP Address
An IP address is a logical address used to identify a device on a network.

Example of IPv4:

`192.168.1.10`

### MAC Address
A MAC address is a hardware-level address assigned to a network interface, typically used for communication within a local network.

Example:

`00:1A:2B:3C:4D:5E`

### DNS
DNS (Domain Name System) translates domain names into IP addresses.

Example:

`www.google.com` → an IP address used to reach the server.

### DHCP
DHCP automatically assigns IP addresses and other network settings to devices.

### HTTP
HTTP is a protocol used for communication between web browsers and web servers.

### HTTPS
HTTPS uses TLS to protect HTTP communications through encryption and authentication.

### TCP
TCP is a connection-oriented transport protocol that provides reliable, ordered data delivery.

### UDP
UDP is a connectionless transport protocol that provides lower-overhead communication but does not guarantee delivery or ordering.

### Router
A router connects different networks and forwards packets between them.

### Switch
A switch connects devices within a local network and forwards frames using MAC addresses.

### Firewall
A firewall controls network traffic according to security rules.

---

## 8. Common Network Ports

| Port | Protocol / Service | Purpose |
|---|---|---|
| 20/21 | FTP | File transfer |
| 22 | SSH | Secure remote access |
| 23 | Telnet | Unencrypted remote access |
| 25 | SMTP | Email sending |
| 53 | DNS | Domain name resolution |
| 80 | HTTP | Web communication |
| 110 | POP3 | Email retrieval |
| 143 | IMAP | Email access |
| 443 | HTTPS | Secure web communication |
| 3306 | MySQL | Database service |
| 3389 | RDP | Remote desktop access |

Ports identify communication endpoints for services. The service commonly associated with a port may be configured to use a different port.

---

## 9. Cryptography Basics

Cryptography is the science of protecting information by transforming it so that unauthorized people cannot easily understand or modify it.

### 1. Encryption
Encryption converts readable data (plaintext) into unreadable data (ciphertext) using an algorithm and key.

### 2. Decryption
Decryption converts ciphertext back into readable plaintext using the appropriate key.

### 3. Symmetric Encryption
Symmetric encryption uses the same secret key for encryption and decryption.

Examples:
- AES
- ChaCha20

Advantages:
- Fast.
- Efficient for large amounts of data.

Disadvantage:
- The secret key must be shared and protected securely.

### 4. Asymmetric Encryption
Asymmetric encryption uses a pair of related keys:

- Public key
- Private key

Examples:
- RSA
- ECC

The keys have different roles depending on the cryptographic operation.

### 5. Hashing
Hashing converts data into a fixed-length digest.

Examples:
- SHA-256
- SHA-3

Uses:
- Integrity verification.
- Digital signatures.
- Password storage systems (using specialized password-hashing algorithms).

Hashing is not reversible encryption.

### 6. Digital Signature
A digital signature helps verify the authenticity and integrity of digital data and can provide evidence that a signing key was used.

### 7. Multi-Factor Authentication (MFA)
MFA requires two or more different types of authentication factors.

Examples:
- Password + authenticator app.
- PIN + security key.
- Password + biometric verification.

---

## 10. Wireshark Basics

Wireshark is a network protocol analyzer used to capture and inspect network traffic.

It helps security professionals understand network communication and investigate suspicious activity.

### Uses of Wireshark
- Analyze network packets.
- Troubleshoot network issues.
- Observe protocol behavior.
- Investigate suspicious network activity.
- Understand TCP, DNS, HTTP, and other protocols.

### Important Terms

**Packet:** A unit of data transmitted across a network.

**Capture:** Recording network traffic for analysis.

**Protocol:** Rules that define how devices communicate.

**Packet Filtering:** Selecting packets of interest from captured traffic.

### Common Wireshark Filters

| Filter | Purpose |
|---|---|
| `ip` | Show IPv4 packets |
| `ipv6` | Show IPv6 packets |
| `dns` | Show DNS packets |
| `tcp` | Show TCP packets |
| `udp` | Show UDP packets |
| `http` | Show HTTP packets |
| `icmp` | Show ICMP packets |
| `ip.addr == 192.168.1.10` | Show packets involving a specific IP |
| `tcp.port == 80` | Show TCP packets using port 80 |
| `tcp.flags.syn == 1` | Show packets with the TCP SYN flag set |

Wireshark is a packet analyzer. It does not automatically prevent cyberattacks.

---

## 11. Metasploit Framework

Metasploit is a penetration-testing framework used by security professionals to test and validate vulnerabilities in authorized environments.

### Main Uses
- Security testing.
- Vulnerability validation.
- Exploit research.
- Penetration-testing practice.
- Security awareness and lab training.

### Important Terms

**Exploit:** Code or a technique used to take advantage of a vulnerability.

**Payload:** Code executed as part of an exploit or security test.

**Module:** A component of Metasploit that performs a specific function.

**Auxiliary Module:** A module used for tasks such as scanning, gathering information, or testing services.

**Vulnerability:** A weakness in a system that may be exploited.

### Metasploit Commands

| Command | Purpose |
|---|---|
| `msfconsole` | Starts the Metasploit console |
| `help` | Displays available commands |
| `search` | Searches for modules |
| `use` | Selects a module |
| `info` | Displays module information |
| `show options` | Displays module configuration options |
| `back` | Exits the current module |
| `exit` | Exits the console |

Practice only in a local lab or authorized environment.

---

## 12. Vulnerability, Threat, and Risk

### Vulnerability
A weakness in software, hardware, configuration, or process.

Example: A server running outdated software with a known security flaw.

### Threat
Something capable of causing harm to a system.

Examples:
- Cybercriminals.
- Malware.
- Malicious insiders.
- Accidental human actions.

### Risk
The possibility of harm or loss when a threat exploits a vulnerability.

**Simple relationship:**

Threat + Vulnerability + Impact = Security Risk (conceptually)

Risk assessments also consider likelihood, impact, and existing controls; the formula above is only a simplified way to understand risk.

---

## 13. Security Tools

### 1. Kali Linux
A Linux distribution containing tools used for penetration testing and security research.

### 2. Nmap
A network scanning tool used to discover hosts, services, and ports within an authorized scope.

### 3. Wireshark
A packet analyzer used to inspect network traffic.

### 4. Metasploit
A framework used for authorized vulnerability testing and validation.

### 5. Burp Suite
A web application security testing tool used to inspect and test HTTP/S traffic.

### 6. OWASP ZAP
A web application security testing tool used to identify potential web vulnerabilities.

### 7. John the Ripper
A password auditing tool used to assess password strength.

### 8. Linux Terminal
A command-line interface used to manage systems, run tools, and perform security tasks.

---

## 14. Password Security

A strong password helps prevent unauthorized account access.

### Characteristics of a Strong Password
- Long and unique.
- Difficult to guess.
- Not reused across websites.
- Avoids personal details.
- Preferably generated and stored using a password manager.

### Password Security Practices
- Use a unique password for every account.
- Enable MFA.
- Never share passwords.
- Avoid saving passwords in plain-text files.
- Change passwords when compromise is suspected.
- Use password managers when possible.

---

## 15. Security Best Practices

- Keep operating systems and software updated.
- Use strong, unique passwords.
- Enable MFA.
- Install trusted software only.
- Avoid suspicious email links and attachments.
- Back up important data regularly.
- Use firewalls and security software.
- Avoid connecting to unknown USB devices.
- Use HTTPS websites for sensitive activities.
- Lock your device when not in use.
- Do not share OTPs or recovery codes.
- Use secure Wi-Fi.
- Review account login activity.
- Avoid unauthorized penetration testing.

---

## 16. Incident Response

Incident response is the organized process of handling cybersecurity incidents.

### Main Phases

1. Preparation – establish tools, plans, and procedures.
2. Detection and Analysis – identify and investigate suspicious activity.
3. Containment – limit the spread or impact of an incident.
4. Eradication – remove the cause of the incident.
5. Recovery – restore systems and services safely.
6. Lessons Learned – review the incident and improve security.

Example:

If a computer is infected with malware, the organization may isolate it from the network, investigate the infection, remove the malware, restore clean data, and review how the infection occurred.

---

## 17. Cybersecurity Career Roles

### Security Analyst
Monitors systems, investigates alerts, and identifies security incidents.

### SOC Analyst
Works in a Security Operations Center to monitor security events and respond to threats.

### Penetration Tester
Tests systems for vulnerabilities within an authorized scope.

### Security Engineer
Designs, implements, and maintains security controls.

### Network Security Engineer
Protects network infrastructure and communication systems.

### Incident Responder
Investigates and handles security incidents.

### Security Auditor
Reviews security controls, policies, and compliance requirements.

---

## 18. Glossary

| Term | Meaning |
|---|---|
| Cybersecurity | Protection of digital systems and information |
| Malware | Malicious software |
| Phishing | Fraudulent communication used to trick victims |
| Firewall | Controls network traffic |
| Encryption | Protects data by transforming it into ciphertext |
| Decryption | Converts ciphertext back to readable data |
| Hashing | Creates a fixed-length digest from data |
| IP Address | Logical network address |
| MAC Address | Network interface hardware address |
| DNS | Converts domain names to IP addresses |
| VPN | Creates a protected network connection through a VPN service |
| IDS | Intrusion Detection System |
| IPS | Intrusion Prevention System |
| SOC | Security Operations Center |
| SIEM | Security Information and Event Management |
| CVE | Common Vulnerabilities and Exposures identifier |
| MFA | Multi-Factor Authentication |
| DDoS | Distributed Denial-of-Service attack |
| SSH | Secure Shell |
| TCP | Transmission Control Protocol |
| UDP | User Datagram Protocol |

---

## 19. Conclusion

Cybersecurity is an essential part of today's digital world. It protects computers, networks, applications, and personal information from cyber threats. Learning cybersecurity begins with understanding basic concepts such as the CIA Triad, networking, Linux commands, cryptography, common attacks, and security tools.

Continuous learning, practical lab experience, ethical behavior, and following security best practices help beginners develop their cybersecurity knowledge and skills.

**Ethical Rule:** Always learn and practice cybersecurity responsibly. Never access, scan, attack, or test systems without proper authorization.
