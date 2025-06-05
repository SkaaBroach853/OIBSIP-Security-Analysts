# OIBSIP - Security Analysts Internship Tasks

## 📌 Task 1: Basic Network Scanning with Nmap

**Objective:**  
Perform a basic network scan to identify open ports and services using Nmap.

**Tools Used:**  
- Nmap

**Steps Followed:**
1. Installed Nmap on the local system.
2. Performed a scan using:
3. Identified open ports and running services.
4. Documented the findings in `nmap_scan_results.txt`.

**Sample Output (from scan):**

| Port  | State | Service       | Version                    |
|-------|-------|----------------|-----------------------------|
| 135   | open  | msrpc         | Microsoft Windows RPC       |
| 445   | open  | microsoft-ds  | SMB                         |
| 5357  | open  | http          | Microsoft HTTPAPI httpd 2.0 |
| 16992 | open  | http          | Intel AMT HTTP Admin        |

**Significance of Ports:**
- **135**: Used for RPC communication in Windows.
- **445**: SMB for file sharing and printing.
- **5357**: Web services for device discovery.
- **16992**: Intel Active Management Technology access.

📁 Files:
- `nmap_scan_results.txt`
- Screenshots inside `/screenshots/` folder

---

## 📌 Task 4: Research on Common Network Security Threats

**Objective:**  
Understand and explain threats like DoS, MITM, and IP Spoofing.

### 1. Denial of Service (DoS)
- **How it works**: Overloads systems with traffic.
- **Impact**: System crashes, downtime.
- **Prevention**: Use firewalls, rate limiting.

### 2. Man-in-the-Middle (MITM)
- **How it works**: Intercepts communication between two devices.
- **Impact**: Data theft, unauthorized access.
- **Prevention**: Encrypt traffic using SSL/TLS, use VPNs.

### 3. IP Spoofing
- **How it works**: Faking IP address to gain unauthorized access.
- **Impact**: Bypass authentication, launch further attacks.
- **Prevention**: Packet filtering, authentication protocols.

**Real-world Example:**  
GitHub was hit by a 1.35 Tbps DDoS attack in 2018.

📁 File: `network_security_threats_report.md`

---

## 📌 Task 5: Research on Social Engineering Attacks

**Objective:**  
Explore how attackers exploit human psychology to gain access.

### Common Types:
- **Phishing**: Fake emails or messages to steal credentials.
- **Pretexting**: Creating a false scenario to gather sensitive info.
- **Baiting**: Tempting users with free offers or USBs that contain malware.

**Examples:**
- Phishing email impersonating Google Docs.
- USB drops in parking lots to infect machines.

**Preventive Measures:**
- Security awareness training.
- Strong email filters and antivirus.
- Never plug unknown USBs.

📁 File: `social_engineering_report.md`

---

## 📌 Task 6: Report on Importance of Patch Management

**Objective:**  
Explain why applying updates (patches) is vital in cybersecurity.

### Why It Matters:
- Fixes known vulnerabilities.
- Protects against malware and exploits.
- Ensures regulatory compliance.

### Risks of Not Patching:
- Data breaches (e.g., Equifax in 2017).
- System crashes.
- Unauthorized access.

### Best Practices:
- Regularly check for updates.
- Test patches before deploying.
- Use automated patch management tools.

📁 File: `patch_management_report.md`

---

## ✅ Internship Task Completion Status

| Task No. | Title                                | Status |
|----------|--------------------------------------|--------|
| 1        | Nmap Network Scan                    | ✅     |
| 4        | Network Security Threats Report      | ✅     |
| 5        | Social Engineering Report            | ✅     |
| 6        | Patch Management Report              | ✅     |

---

## 🔗 Author

- **Name:** Aaditya Devadiga 
- **Internship:** OIBSIP - Security Analyst  
- **GitHub:** [SkaaBroach853
](https://github.com/SkaaBroach853
)

---

