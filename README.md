<div align="center">

# 👨🏽‍💻 PASSWORD CRACKING REPORT

**USING JOHN THE RIPPER & NETWORKWALK TOOLS**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/John%20The%20Ripper-404040?style=flat-square&labelColor=C00000&logo=logoColor=white" />
  <img src="https://img.shields.io/badge/windows os-404040?style=flat-square&labelColor=C00000&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Academy-NetworkWalks-404040?style=flat-square&labelColor=C00000" />  
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <div align="center">
<img src="https://img.shields.io/badge/👨🏽‍💻Pentester-Dickson%20Kenneth%20Chigozie-404040?style=flat-square&labelColor=C00000" />
</p>

---

<div align="center">
Wk3-PM1-PM2 | CYBERSECURITY |  NETWORKWALKS 
</p>
  
</div> 
<p align="left">
🔎 Project Overview 
</p>

</div> 
<p align="left">
  
| **Field** | **Detail** |
|---|---|
| **Pentester** | **Dickson Kenneth Chigozie** |
| **Program/Batch** | Networkwalks-B084 |
| **Date** | 21<sup>th</sup> November, 2026 |
| **Modules completed** | Wk3-PM1 (Password Cracking with JTR)<br>Wk3-PM2 (Password Cracking with NW Tools) |
| **Target** | Networkwalks (PDF Folders) |
| **Permission secured from client?** | Yes (Authorized✅) |


---

# ⚒️ Tools Used: 

- John The Ripper (JTR)
- Johnny (GUI)
- Encrypted PDF Files
- PDF Hash Extractor (Online Hash Crack)
- Networkwalks Hash calculator
- Networkwalks Password Cracker

----

# 🛡️ Liability Disclaimer

The activities documented in this report were conducted strictly on systems and devices for which prior written authorization was obtained. The contents of this document are intended strictly for educational and research purposes. The author, instructor, and Networkwalks assume no liability for the misuse or misapplication of this knowledge; all subsequent actions taken by the reader are their sole responsibility. Unauthorized system access constitutes a criminal offense in most jurisdictions, regardless of whether data or systems are damaged, and can result in severe legal penalties, significant fines, career impact (employment termination), and a permanent criminal record. 
> ⚠️ **Note: Authorization must be Secured from Networkwalks before performing Pentesting**

---

# 🧩 Introduction

This report is part of my Cybersecurity and Ethical Hacking internship program for week 3 at Networkwalks Academy. This practical exercise focused on recovering the password of protected PDF files, PDF Hash Extraction, and the importance of using strong passwords for protection. It is essentially divided into several aspects, namely:

```text

- Wk3-Project Module 1 - Focuses on Password Cracking with John The Ripper (JTR) 
- Wk3-Project Module 2 - Focuses on Password Cracking with Tools Provided by Networkwalks
```

---

# 1️⃣  Wk3-PM 1: Password Cracking with JTR John and JTR Johnny

---

# 🏁 Background 

``` text
John the Ripper (JTR) is a popular password cracking tool used by security professionals to test how strong 
passwords are. It started as a tool for Unix systems but now works on Windows, Linux, and Mac. It can 
check many types of password hashes and also unlock password protected files like PDF, ZIP, and Office 
documents. 
Johnny is the graphical version of John the Ripper. It gives a simple point and click screen, so beginners can 
use JTR without typing long commands. Both tools are widely used in security testing and learning labs to 
understand password safety. 
In this lab task I used JTR John and JTR Johnny to recover the password of a protected PDF file. This 
exercise helped me learn how password cracking works and why it is important to use strong passwords for 
protection.
```
---

---

# 🎯 Task 1

Crack the password of attached PDF file ```(My Locked PDF1.pdf)``` using ```JTR John and JTR Johnny tools``` on your Windows PC.

---

## Step 1.1: Download and Install John and Johnny

John The Ripper and Johnny (GUI) were both downloaded and installed

<img width="702" height="387" alt="johnny interferface" src="https://github.com/user-attachments/assets/ec22628b-ba56-4f26-8853-b3c63ce5c4c6" />

---

## Step 1.2: Obtain the PDF file

The PDF file to be cracked, that is, My Locked PDF1.pdf, was provided by the instructor at Networkwalks

---

## Step 1.3: Extract the PDF Hash

The PDF file (My Locked PDF1.pdf) was uploaded the PDF Hash Extractor (OnlineHashCrack), processed, and its Hash was subsequently obtained 

<img width="1256" height="627" alt="hash extractor" src="https://github.com/user-attachments/assets/d9d3ea96-54c9-4a06-bc05-35d9da1003c6" />

> 💡 **Note: Encryption is a two-way function; what is encrypted can be decrypted with the proper key. Hashing, however, is 
a one-way function that scrambles plain text to produce a unique message digest, as shown in above.**

---

## Step 1.4: Create the Hash File

The extracted hash was saved into a text file on my Notepad and named:

```text
Hash1.txt
```
<img width="1202" height="711" alt="image" src="https://github.com/user-attachments/assets/aa98d117-2632-4460-9067-35ca00be91c3" />

---

## Step 1.5: Initiate Password Recovery Process

The hash saved in the text file ```Hash1.txt``` was loaded into Johnny. And by clicking on ```start new attack```, the password recovery process was initiated for the PDF file (My Locked PDF1.pdf) to be cracked.

🚦 Note: The cracking process might take some time depending on:
```text
i. Your computer speed
ii. The password complexity
```

---

## Step 1.6: Get the Recovered Password

The password was successfully cracked by Johnny to be ```"good-luck"```.

<img width="1267" height="680" alt="image" src="https://github.com/user-attachments/assets/c7b32b7d-99a2-48e8-8008-885324da54aa" />

---

## Step 1.7: Verify the Recovered Password

The recovered password was used to open the PDF file ```My Locked PDF1.pdf```.

<img width="1265" height="650" alt="image" src="https://github.com/user-attachments/assets/b05c7588-fa32-45c9-a45a-0308fb5eaa5c" />

---

---

# 2️⃣  Wk3-PM 2: Password Cracking with Networkwalks Hash Calculator and Networkwalks Password Cracker

---

# 🏁 Background

```text
Password cracking is the process of recovering a password from stored data or a protected file. Security 
professionals use it to test how strong a password is and to show why weak passwords are risky. If a 
password is short or common, it can be found quickly, which proves the need for strong passwords. 
Many files like PDF, ZIP, and Office documents can be locked with a password. When a file is locked, its 
password is stored in the form of a hash. A hash is a scrambled value that represents the password. To 
recover the password, we first take out this hash from the file, and then run it through a cracking tool that 
tries different words until it finds a match. 
In this lab you will use two free online tools made by Networkwalks. First you will use the Hash Calculator 
to take the hash out of a locked PDF file. Then you will use the Password Cracker to find the real password 
from that hash. Both tools run in your web browser, so you do not need to install anything. 
This lab helps you understand how password cracking works step by step and why strong passwords are 
important for protection.
```

---

# 🎯 Task 2

Crack the password of attached PDF file ```(My Locked PDF1 For NW Tools.pdf)``` using ```Networkwalks Hash Calculator``` and ```Networkwalks Password Cracker``` tools on your Windows PC browser.

---

## Step 2.1: Networkwalks Hash Calculator

The Networkwalks Hash Calculator was opened in my web browser and the locked PDF file was Uploaded to the Hash Calculator. 

The tool read the file and gave me a hash value that starts with ```$pdf$```.

<img width="1257" height="635" alt="image" src="https://github.com/user-attachments/assets/03728a33-6ebe-4144-98c3-2cb2ba00f37d" />

> 🚦 **Note: The full hash value was copied**

---

## Step 2.2: Networkwalks Password Cracker

The Networkwalks Password Cracker was opened in my web browser, and the hash value I previously copied was pasted into it.

<img width="1247" height="632" alt="image" src="https://github.com/user-attachments/assets/854ab502-d23c-4e1a-af81-cac7f208ae05" />

---

The attack was subsequently started by clicking ```start cracking```. The tool will try different passwords until it finds a match, and the cracked password will be displayed on the screen.

<img width="1251" height="632" alt="image" src="https://github.com/user-attachments/assets/5c118437-5f9b-4c2a-973e-e50f7b9678f8" />

> 🚦 **Note: The time taken depends on how simple or complex the password is.**

---

## Step 2.2: Open the Locked PDF file and Enter the Cracked Password

I opened the locked PDF file and entered the cracked password which I just discovered. 

That is, ```password1``` (which I have just cracked): 


<img width="1257" height="637" alt="image" src="https://github.com/user-attachments/assets/f695cab8-939d-4e38-b1e8-3ca7d4d7790e" />

---

## Step 2.2: PDF file Opens

The PDF file opens, and my lab is completed. 

<img width="1252" height="627" alt="image" src="https://github.com/user-attachments/assets/a0a25e41-ad8c-41f8-b593-5e0210d16349" />

---

---

# 🛡️ Conclusion

During week 3 of my Cybersecurity & Ethical Hacking internship at Networkwalks Academy, I gained hands-on practical experience by completing lab/practical exercises focused on **password cracking, hash analysis, hash extraction, and password security.

The first module provided hands-on experience with John the Ripper and Johnny.

The second module provided practical experience with the Networkwalks Hash Calculator and Networkwalks Password Cracker, demonstrating a browser-based approach to the same general password cracking processs.

---

# 👌Recommendations

### I. Use strong and unique Passwords:

Use long and hard to predict passwords and never re-use them across systems; a password manager can generate and store them securely.

### II. Multi-factor authentication:

Enable MFA wherever supported to add a layer of protection beyond the password.

### V. Protect Stored Credentials

Secure password hashes and credential databases against unauthorized access.

---

## 📌 Project Information

| **Project Details** | **Information** |
|---|---|
| 1️⃣ **Program Name** | Cybersecurity & Ethical Hacking Program at Networkwalks              |
| 2️⃣ **Week**         | 03                                                                   |
| 3️⃣ **Project:**     | Psssword Cracking with John the Ripper & Networkwalks Tool           |
| 4️⃣ **Repository:**  | GitHub                                                               |

---

<div align="center">
  
# 👤 Author

</div>

<div align="center">
  
**Ukwueze Uchenna Collins**

**Cybersecurity Intern | Networkwalks | Batch B084**

LinkedIn: www.linkedin.com/in/uchenna-u-6b4377367

</div>

---











