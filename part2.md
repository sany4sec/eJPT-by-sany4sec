**About Me:**

My name is Md. Rabius Sany. I am a Cybersecurity Enthusiast, a Computer Science student, and ranked in the Top 2% on TryHackMe. I started my journey into cybersecurity in 2023, and ever since, I have been deeply passionate about learning more in this ever-evolving field. Recently, I successfully passed the eJPT certification exam in just 13 hours with a 94% score! This article is part one of my two-part series detailing my experience.

**Series Overview:**

- **Part 1:** Passing eJPT in 13 Hours with a 94% Score! My Exam Day Experience & Structure.
- **Part 2:** How I Prepared for eJPT and My Top Tips to Pass.

This is the second part. I hope you find it useful.

---

**Table of Contents:**

1. Pre-eJPT Preparation
2. eJPT Exam Preparation
3. Tools You Have to Master
4. Practice on Some TryHackMe Rooms
5. What to Do During the Exam

---

### 1. Pre-eJPT Preparation

Before you attempt the eJPT exam or training, you should have a solid understanding of computer fundamentals, Linux, and networking. I will provide some resources where you can learn these fundamentals. If you already have knowledge of these topics, you can revise them or skip this section.

- **Linux:** Linux for Hackers (Free)
- **Networking:** Free Networking Course

---

### 2. eJPT Exam Preparation

This is the section we have all been waiting for. When you purchase an eJPT voucher, you will receive a three-month training program along with it. The training is sufficient for this certification, but for proper preparation, I have some additional advice:

#### 1. Note-Taking

Taking notes is a must. You should document everything you learn. I recommend using the **CherryTree** note-taking app because it is offline and performs efficiently.

- If you're using CherryTree, make sure to back up your notes regularly. Since it is stored locally, if your system crashes, you will lose all your notes.
- Here is a great GitHub notes repository: [eJPTv2 Notes](https://github.com/neilmadhava/EJPTv2-Notes.git)

#### 2. Complete the Full Training

The **"Penetration Tester Student"** course that comes with the eJPT voucher is enough for the certification. It covers everything a junior penetration tester needs to know, including penetration testing trends and methodologies. Each section comes with a practical lab environment where you get hands-on experience.

- If you cannot complete the training, that’s okay! You can follow the **Jr Penetration Tester Path** on TryHackMe instead: [Jr Penetration Tester Path](https://tryhackme.com/path/outline/jrpenetrationtester)

#### 3. Master All Enumeration Techniques

Enumeration is key! Most of the questions in the exam are enumeration-based. Take detailed notes on each enumeration technique so that you can use them in the exam. Some important protocols you should focus on:

- FTP
- SSH
- HTTP/HTTPS
- WebDAV
- RDP
- SMB
- WinRM
- MySQL

#### 4. Brute-Forcing Techniques

Brute-forcing is a critical skill for passing the exam. Familiarize yourself with brute-forcing tools such as:

- Hydra
- Burp Suite Intruder
- Metasploit login brute-force modules
- WPScan brute-force
- Login page brute-forcing

#### 5. Hash Cracking

You will encounter situations where you need to crack NTLM, SHA512, MD5, or other hashes. You must master these tools:

- **John the Ripper**
- **Hashcat**
- **Online Hash Cracking Tools:**
  - [CrackStation](https://crackstation.net/)
  - [Hashes Identifier](https://hashes.com/en/tools/hash_identifier)
  - [MD5 Hashing](https://md5hashing.net/)

#### 6. Getting Access with Shells

You should have a clear understanding of how **reverse/bind shells** work and how to modify them to include your IP and port. Some useful resources:

- [Pentest Monkey](https://pentestmonkey.net/)
- [Reverse Shell Generator](https://www.revshells.com/)
- `/usr/share/webshell/`
- `Msfvenom`

#### 7. Privilege Escalation

You must be familiar with **both Windows and Linux privilege escalation techniques**. Key resources:

- [Linux Privilege Escalation](https://github.com/Ignitetechnologies/Linux-Privilege-Escalation.git)
- [Windows Privilege Escalation](https://github.com/neilmadhava/EJPTv2-Notes/blob/main/Post-Exploitation/win-privesc.md)
- [GTFObins](https://gtfobins.github.io/)

#### 8. Internal Network Pentesting

In the eJPT exam, you will be asked questions related to internal network machines. Learn:

- How to find internal networks after gaining access to a machine.
- How to add **autoroute** with Meterpreter.
- How to perform **port forwarding** to scan the internal network with Nmap.

#### 9. Transferring Files

To pass the eJPT exam, you **must** know how to transfer files between targets. Learn:

- How to transfer files to **Windows** targets.
- How to transfer files to **Linux** targets.

#### 10. Web Enumeration and Attacks

The eJPT exam includes basic web attacks. You should be familiar with:

- **Web enumeration**
- **Directory brute-force attacks**
- **Modifying the /etc/hosts file**
- **Login brute-force**
- **Using Burp Suite, ZAP Proxy, sqlmap, Nikto, WPScan, etc.**

---

### 3. Tools You Must Master

Here are some essential tools for passing the eJPT exam:

1. **Nmap** – A powerful scanning tool.
2. **Metasploit Framework** – Used in various penetration testing phases.
3. **Meterpreter & Msfvenom** – Used for shell access.
4. **FTP, SSH, SMBClient, xfreerdp** – Essential for remote access.
5. **Hydra** – Used for brute-forcing login credentials.
6. **John the Ripper & Hashcat** – Used for cracking hashes.
7. **WPScan** – Used for WordPress enumeration.
8. **Nikto** – A web vulnerability scanner.
9. **Dirb, Dirbuster, Gobuster** – Used for finding hidden directories.
10. **CrackMapExec, PsExec** – Used for gaining system access.

---

### 4. Practice on TryHackMe Rooms

After completing the eJPT course, practice free CTF challenges on TryHackMe before attempting the exam. Some recommended rooms:

- [Basic Pentesting](https://tryhackme.com/room/basicpentestingjt)
- [RootMe](https://tryhackme.com/room/rrootme)
- [EasyCTF](https://tryhackme.com/room/easyctf)
- [Ignite](https://tryhackme.com/room/ignite)
- [Startup](https://tryhackme.com/room/startup)

For a full list, refer to the original document.

---

### 5. What to Do During the Exam

During the exam, follow structured steps for efficient completion. This includes performing **host discovery, aggressive scans, mapping questions to machines, targeted enumeration, brute-forcing credentials, privilege escalation, and internal network pentesting**.

By following this guide, you will be well-prepared to pass the eJPT exam.

**Thank you for reading!**

This is Rabius Sany, signing out.

