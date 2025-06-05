# 🛡️ Task 1: Basic Network Scanning with Nmap

## 🎯 Objective

This task demonstrates how to use **Nmap** to perform a basic network scan to discover open ports and running services on a local machine (localhost).

---

## 🧰 Tools Used

- **Nmap v7.97**
- **Command Prompt (Windows 10)**
- **Target IP**: `127.0.0.1` (localhost)

---

## 📦 What’s Included in This Repo

| File Name              | Description                                       |
|------------------------|---------------------------------------------------|
| `nmap_scan_results.txt` | Raw output of the Nmap scan                      |
| `screenshot.png`        | Screenshot of the scan in Command Prompt         |
| `README.md`             | This file, explaining each step and the results  |

---

## 🧪 Steps Followed

### ✅ Step 1: Install Nmap

- Download from: [https://nmap.org/download.html](https://nmap.org/download.html)
- Install it by following on-screen instructions.
- Verify installation by opening Command Prompt and typing:
```bash
nmap --version
```
---
### ✅ Step 2: Run Nmap Scan
Command used:

```bash
nmap -sV 127.0.0.1
```
- sV: Enables service/version detection.

- 127.0.0.1: Target IP (your own machine).

This command checks for open TCP ports and identifies what services are running on those ports.
---
### ✅ Step 3: Save Scan Results
To save the output to a file:

```bash
nmap -sV 127.0.0.1 > nmap_scan_results.txt
```
This creates a .txt file with the full scan output.
---
### ✅ Step 4: Analyze the Output

#### 📋 Summary of Detected Open Ports

| Port      | State | Service       | Version                                |
|-----------|-------|---------------|----------------------------------------|
| 135/tcp   | open  | msrpc         | Microsoft Windows RPC                  |
| 445/tcp   | open  | microsoft-ds  | SMB (Server Message Block)             |
| 5357/tcp  | open  | http          | Microsoft HTTPAPI httpd 2.0 (UPnP)     |
| 16992/tcp | open  | http          | Intel AMT - Remote Mgmt HTTP Admin     |
### 🔍 What These Ports Mean
#### 1. 135/tcp (msrpc):

- Used for Windows Remote Procedure Call.
- Commonly used for network communication between Windows systems.
#### 2. 445/tcp (microsoft-ds):
- Used for SMB (file/printer sharing on Windows).
- Often targeted in ransomware and exploits.
#### 3. 5357/tcp (http - HTTPAPI):
- Web services discovery (UPnP).
- Can reveal information about the system.
#### 4. 16992/tcp (Intel AMT HTTP):
- Port for Intel Active Management Technology.
- Critical for enterprise-level remote administration.
- Must be secured or disabled if unused.
---
### 🖼️ Screenshot
![8f738e01-c582-4742-8e49-feb55ac1c3f9](https://github.com/user-attachments/assets/349d3807-ed65-47cc-8ff8-2606678b53b6)

---
![0eb0f401-7130-440d-a57f-89043c70bda1](https://github.com/user-attachments/assets/e7861272-883b-4687-8bb5-161488f2ea9b)

---
<img width="960" alt="Screenshot 2025-06-05 131408" src="https://github.com/user-attachments/assets/6551ee97-d37b-4f43-9cbd-4e6575d47c4f" />

---
### 🧠 Key Takeaways
- Nmap is a powerful tool for identifying open ports and services.

- Service detection (-sV) gives deeper insight into what is running behind the ports.

- Always scan your system to detect vulnerabilities before attackers do.

### 🔗 Useful Links
- 📘 [Nmap Official Documentation](https://nmap.org/book/man.html)

- 📄 [Nmap Commands Cheat Sheet](https://nmap.org/man/en/)

- 🔐 [Cybersecurity Basics by OWASP](https://owasp.org/)

### 🙋 Author
- 👤 Aaditya Devadiga
- 📍 Cybersecurity Intern
- 🔗 [LinkedIn](https://www.linkedin.com/in/aaditya-devadiga-0ba539329)
