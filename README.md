
# ROADMAP-Cybersecurity  
ROADMAP to get started in cybersecurity and CTF

## 1. Understand the Basics of How Technology Works
- Learn how websites function: HTML, CSS, JavaScript, HTTP/HTTPS protocols.  
  Resource: [Mozilla Developer Network (MDN) Web Docs](https://developer.mozilla.org/en-US/docs/Learn)  
- Understand databases and basic backend concepts.  
  Resource: [Khan Academy - Intro to Databases](https://www.khanacademy.org/computing/computer-programming/sql)  
- Study how computer networks work: IP addressing, subnetting, routing, DNS, DHCP.  
  Resource: [Cisco Networking Academy](https://www.netacad.com/courses/packet-tracer)  
- Learn key internet protocols: TCP/IP, UDP, ICMP, SMTP, FTP, SSL/TLS.  
  Resource: [Computer Networking: Principles, Protocols and Practice (Free ebook)](https://intronetworks.cs.luc.edu/current/html/index.html)  
- Understand operating system fundamentals (Windows, Linux, macOS): file systems, processes, permissions, command line.  
  Resource: [The Linux Command Line by William Shotts (Free ebook)](http://linuxcommand.org/tlcl.php)  

## 2. Build Foundational Skills
- Study basic programming and scripting: Python, Bash, PowerShell.  
  Resource: [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)  
- Learn basic Linux usage and commands; get comfortable with terminal-based work.  
  Resource: [Linux Journey](https://linuxjourney.com/)  
- Practice networking with tools like Wireshark for packet analysis.  
  Resource: [Wireshark Official Documentation and Tutorials](https://www.wireshark.org/docs/)  
- Get familiar with virtualization tools like VirtualBox or VMware to create lab environments.  
  Resource: [VirtualBox User Manual](https://www.virtualbox.org/manual/UserManual.html)  

## 3. Set Up a Lab Environment
- Install Kali Linux or Parrot OS for cybersecurity tools and practice.  
  Resource: [Kali Linux Official Documentation](https://www.kali.org/docs/)  
- Set up vulnerable machines or use online platforms for practice (Metasploitable, DVWA).  
  Resource: [Metasploitable](https://sourceforge.net/projects/metasploitable/) | [DVWA](https://github.com/digininja/DVWA)  
- Use platforms like TryHackMe, Hack The Box to do real-world labs and challenges.  
  Resource: [TryHackMe](https://tryhackme.com/) | [Hack The Box](https://www.hackthebox.com/)  

## 4. Learn Core Cybersecurity Concepts
- Understand different types of attacks: phishing, XSS, SQL injection, malware types, ransomware.  
  Resource: [OWASP Top Ten](https://owasp.org/www-project-top-ten/)  
- Study cryptography basics: symmetric/asymmetric encryption, hashing, certificates.  
  Resource: [Cryptography and Network Security by William Stallings (Book)](https://williamstallings.com/Crypto3e.html)  
- Learn about firewalls, IDS/IPS systems, VPNs, proxies.  
  Resource: [Cisco ASA Firewall Tutorials](https://www.cisco.com/c/en/us/products/security/asa-5500-series-next-generation-firewalls/index.html)  
- Know about authentication, authorization, and access control methods.  
  Resource: [Microsoft Docs - Authentication and Authorization](https://docs.microsoft.com/en-us/azure/active-directory/develop/authentication-vs-authorization)  

## 5. Master Key Security Tools and Techniques
- Network scanning with Nmap.  
  Resource: [Nmap Official Documentation](https://nmap.org/book/man.html)  
- Vulnerability assessment and exploitation basics with Metasploit.  
  Resource: [Metasploit Unleashed](https://www.offensive-security.com/metasploit-unleashed/)  
- Web application testing with Burp Suite.  
  Resource: [PortSwigger Web Security Academy](https://portswigger.net/web-security)  
- Traffic analysis with Wireshark.  
  Resource: [Wireshark Tutorial - Practical Packet Analysis (Book)](https://www.nostarch.com/packetanalysis2/)  
- Intrusion detection with Snort or Suricata.  
  Resource: [Snort User Manual](https://www.snort.org/downloads) | [Suricata Documentation](https://suricata.readthedocs.io/en/latest/)  

## 6. Gain Hands-On Experience and Certifications
- Solve Capture The Flag (CTF) challenges and real-world hacking labs.  
  Resource: [CTFtime - List of CTF Competitions](https://ctftime.org/)  
- Participate in bug bounty programs and cybersecurity communities.  
  Resource: [Bugcrowd](https://bugcrowd.com/) | [HackerOne](https://www.hackerone.com/)  
- Pursue beginner-to-intermediate certifications such as:  
  - CompTIA Security+  
    Resource: [CompTIA Security+ Official](https://www.comptia.org/certifications/security)  
  - Certified Ethical Hacker (CEH)  
    Resource: [EC-Council CEH](https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/)  
  - Offensive Security Certified Professional (OSCP) (more advanced)  
    Resource: [Offensive Security OSCP](https://www.offensive-security.com/pwk-oscp/)  

## 7. Advanced Topics and Specializations
- Incident response and digital forensics.  
  Resource: [SANS Incident Response Resources](https://www.sans.org/incident-response)  
- Malware analysis and reverse engineering.  
  Resource: [Practical Malware Analysis (Book)](https://practicalmalwareanalysis.com/)  
- Cloud security (AWS, Azure, GCP security fundamentals).  
  Resource: [AWS Security Learning](https://aws.amazon.com/security/) | [Microsoft Azure Security](https://learn.microsoft.com/en-us/azure/security/) | [Google Cloud Security](https://cloud.google.com/security)  
- Threat hunting and SOC operations.  
  Resource: [MITRE ATT&CK Framework](https://attack.mitre.org/)  
- Secure software development and DevSecOps.  
  Resource: [OWASP DevSecOps Guide](https://owasp.org/www-project-devsecops-guideline/)  

***

## CTF Domains and Their Inclusions  

| CTF Domain           | Description / What It Includes                                             | Resource Links                                        |
|----------------------|-----------------------------------------------------------------------------|------------------------------------------------------|
| Web Exploitation     | Exploit web app vulnerabilities: SQLi, XSS, CSRF, auth flaws.               | [PortSwigger Web Security Academy](https://portswigger.net/web-security) |
| Binary Exploitation  | Reverse engineering, buffer overflow, format string, heap exploits.        | [pwn.college](https://pwn.college/)                  |
| Cryptography         | Cipher cracking, encryption analysis, encoding/decoding.                   | [CryptoHack](https://cryptohack.org/)                 |
| Reverse Engineering  | Analyzing binaries, extract secrets, decompilation.                        | [OpenSecurityTraining](https://opensecuritytraining.info/) |
| Forensics            | File/network/memory analysis, hidden data recovery.                        | [Forensics Wiki](https://forensicswiki.org/wiki/Main_Page) |
| Steganography        | Hidden data in media files—images, audio, video.                         | [Steganography Online Tools](https://stylesuxx.github.io/steganography/) |
| Network Exploitation | Traffic capture, protocol exploitation, MITM attacks.                     | [Wireshark Labs](https://www.wireshark.org/docs/)    |
| Miscellaneous        | Puzzles, OSINT, scripting, unique security challenges.                    | [Root Me](https://www.root-me.org/?lang=en)          |




# For more help and guidance on your cybersecurity journey, follow the official MIT Cybersecurity and Blockchain Club (MIT CBC) on Instagram [@cbc_mitadt](https://instagram.com/cbc_mitadt) and join their [WhatsApp group](https://chat.whatsapp.com/DEBNwthm1O02tSEVCtfko7?mode=wwt). These platforms offer valuable resources, mentorship, and community support.
