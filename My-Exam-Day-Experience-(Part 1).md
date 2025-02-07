# Passing eJPT in 13 Hours with 94% Score!: My Exam Day Experience & Structure (Part 1)

### **About Me:**
My name is Md. Rabius Sany. I am a **Cybersecurity Enthusiast**, **CSE student**, and ranked in the **Top 2% on TryHackMe**. I started my journey into cybersecurity in **2023**, and ever since, I have been deeply passionate about learning more in this ever-evolving field. Recently, I successfully **passed the eJPT certification exam in just 13 hours with a 94% score!** This article is part one of my two-part series detailing my experience.

### **Series Overview:**
📌 **Part 1:** Passing eJPT in 13 Hours with 94% Score!: My Exam Day Experience & Structure  
📌 **Part 2:** [How I Prepared for eJPT and My Top Tips to Pass](https://github.com/sany4sec/eJPT-by-sany4sec/blob/main/How%20I%20Prepared%20for%20eJPT%20and%20My%20Top%20Tips%20to%20Pass.md)

Stay tuned for my next article! 🚀

---

## **Exam Day Experience**

### **⏳ The Beginning – Unexpected Delays**

🗓 **Date:** Friday, January 24, 2025  
⏰ **Morning:** I woke up at **5:30 AM** ready to start my exam, but unfortunately, there was no electricity in my area. This meant I had to wait until **11:00 AM** before I could begin the exam. 

---

## **🕒 11:30 AM - 1:00 PM: Initial Reconnaissance**

🔍 My first task was to **identify live hosts and perform a full port scan.** I used the following scanning methods:

✅ **Discovering live hosts** on the network  
✅ **Performing an all-port scan** (`-p-`) with service and OS detection (`-sV` & `-O`)

**Results:**
I found **six machines** on my subnet (excluding my own machine and the gateway):

1️⃣ **Windows Server with WordPress**  
2️⃣ **Windows Server running WebDAV**  
3️⃣ **Linux Server hosting a Drupal CMS**  
4️⃣ **FreeBSD Server**  
5️⃣ **Windows Server**  
6️⃣ **Linux Server**  

🗂 **Categorizing the Questions:**
The exam consisted of **35 questions**, and at this stage, I categorized about **20 of them** based on the detected machines. However, since I hadn’t performed full enumeration yet, I wasn’t entirely sure about the remaining **15 questions**.

---

## **🕑 1:00 PM - 2:30 PM: Enumeration & First Machine Exploitation**

🔍 I started enumerating **Machine 1** (Windows Server with WordPress). After **directory brute-forcing**, I found a **hidden directory** leading to the WordPress site.

🔑 **Accessing the Admin Panel:**
I attempted different enumeration techniques and eventually gained admin access via **brute force**. However, I couldn’t get a shell despite multiple attempts.

🕌 **Break:** At this point, I took a break for **Jummah Salah.**

---

## **🕒 2:30 PM - 4:30 PM: Machine Exploitation & Progress**

✅ **Machine 1:** I couldn't get a shell through WordPress, but I found **SSH credentials** and used them to log in. This gave me **root access**, and I completed all related questions.

✅ **Machine 2:** This was **WebDAV-related**. I used a **Metasploit HTA exploit module** to gain a shell within **30 minutes** and completed all related questions.

✅ **Machine 3:** This Linux server took me the longest—**4 hours**—as most of the questions were based on it. There were **many enumeration-related questions**. I exploited a known vulnerability to gain **root access**. However, I was unable to brute force the **Drupal login**, which caused me to lose **a few points**.

🕌 **Break for prayer and refreshments.**

---

## **🕡 6:30 PM - 9:00 PM: Wrapping Up Major Questions**

✅ I had completed **28 questions** at this point, including the **two dynamic flags** from **Machine 2 and Machine 3**.

⚡ **Surprise!**
I noticed that **Machine 4 had only one question** and **Machines 5 & 6 had no dedicated questions**. Instead, there was a single question that combined **Machines 3 and 6**.

---

## **🕚 11:30 PM - 1:00 AM: Internal Network Discovery**

🔍 **Internal Network Found!**
While working on **Machine 2**, I discovered an **internal network** with **three additional machines**. After thorough enumeration and exploitation, I managed to answer all **35 questions** by **1:00 AM.**

---

## **🤯 1:00 AM - 2:10 AM: Final Review & Confusion**

I was **confused** because I had **no access to Machines 5 & 6**, yet I had **answered all questions**. I double-checked my work multiple times but couldn't find anything missing. 

---

## **🎯 2:10 AM - Exam Submission & Result**

✅ **Final Decision:** I decided to **submit my exam**, even though I was nervous about missing Machines 5 & 6.  
🙏 **With a deep breath and trust in Allah, I clicked the submit button.**

🎉 **RESULT:** **94% Score!** **Alhamdulillah, it was a historic moment of happiness!** 🎊

---

## **🎥 Video & Social Links**
📽 **Exam Submission Video:** [Watch Here](https://youtube.com/shorts/Oes333UiQKc)  
🔗 **TryHackMe:** [My Profile](https://tryhackme.com/r/p/sany4sec)  
🔗 **LinkedIn:** [Connect with Me](https://www.linkedin.com/in/sany4sec/)  
🔗 **Twitter (X):** [Follow Me](https://x.com/sany4sec)
🔗 **Website:** [sany4sec](http://sany4sec.super.site)

---

## **💡 What’s Next?**
📌 Stay tuned for **Part 2**, where I’ll share [**how I prepared for the exam and my top tips for passing the eJPT!**](https://github.com/sany4sec/eJPT-by-sany4sec/blob/main/How%20I%20Prepared%20for%20eJPT%20and%20My%20Top%20Tips%20to%20Pass.md) 🚀  
**Thanks for reading!** 🙌

