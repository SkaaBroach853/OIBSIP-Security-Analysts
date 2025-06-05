# Network Security Threats Report

## 📌 Objective

This report explores some of the most common and dangerous network security threats — **Denial of Service (DoS) attacks**, **Man-in-the-Middle (MITM) attacks**, and **spoofing**. It aims to explain how these threats work, their impact, real-world examples, and how to mitigate them.

---

## 1. Denial of Service (DoS) Attacks

### 🛠️ How It Works
A **Denial of Service (DoS)** attack attempts to make a machine or network resource unavailable to users by overwhelming it with traffic or triggering system crashes. A **Distributed Denial of Service (DDoS)** attack amplifies this using multiple compromised systems.

### 💥 Impact
- Service unavailability  
- Revenue loss for businesses  
- Damage to reputation  
- Resource exhaustion

### 🧠 Real-World Example
- **GitHub DDoS Attack (2018)**: GitHub was hit with a **1.35 Tbps** traffic surge—the largest DDoS attack recorded at the time—using **memcached servers** to amplify traffic.

### 🛡️ Mitigation Measures
- Use **rate limiting** and **firewalls**  
- Employ **anti-DDoS services** (e.g., Cloudflare, AWS Shield)  
- Configure **traffic filtering** and **anomaly detection systems**  
- Utilize **load balancers** and **redundant network infrastructure**

---

## 2. Man-in-the-Middle (MITM) Attacks

### 🛠️ How It Works
In a **MITM attack**, an attacker intercepts and potentially alters communication between two parties without their knowledge. It typically involves:
- **Eavesdropping** on data transmission  
- **Session hijacking**  
- **SSL stripping** (downgrading HTTPS to HTTP)

### 💥 Impact
- Sensitive data leakage (passwords, credit card info)  
- Unauthorized access to user accounts  
- Identity theft

### 🧠 Real-World Example
- **Superfish Incident (2015)**: Lenovo laptops shipped with adware (Superfish) that used a self-signed root certificate to intercept HTTPS traffic, enabling MITM attacks.

### 🛡️ Mitigation Measures
- Use **end-to-end encryption** (TLS/SSL)  
- Avoid public Wi-Fi or use a **VPN**  
- Implement **certificate pinning**  
- Educate users to recognize phishing and SSL certificate warnings

---

## 3. Spoofing Attacks

### 🛠️ How It Works
**Spoofing** involves impersonating another system, device, or user to gain unauthorized access or mislead users. Types include:
- **IP Spoofing**: Faking the source IP address  
- **Email Spoofing**: Forging the "From" field in emails  
- **DNS Spoofing**: Redirecting users to malicious websites

### 💥 Impact
- Malware delivery  
- Phishing and social engineering  
- Loss of trust and data breaches

### 🧠 Real-World Example
- **Sony Pictures Hack (2014)**: Attackers used DNS spoofing to redirect internal users to malicious sites, eventually exfiltrating terabytes of sensitive data.

### 🛡️ Mitigation Measures
- Implement **packet filtering** and **IP validation**  
- Use **email authentication standards** (SPF, DKIM, DMARC)  
- Deploy **DNSSEC** to secure DNS communications  
- Monitor traffic for anomalies

---

## ✅ Conclusion

Understanding and defending against network security threats like **DoS**, **MITM**, and **spoofing** is crucial in today’s connected world. By applying technical controls, staying informed, and following best practices, organizations can drastically reduce their risk exposure.

---

## 📚 References

- OWASP: [https://owasp.org](https://owasp.org)  
- Cloudflare Learning Center: [https://www.cloudflare.com/learning/](https://www.cloudflare.com/learning/)  
- Kaspersky Threats Guide: [https://www.kaspersky.com/resource-center/threats](https://www.kaspersky.com/resource-center/threats)  
- GitHub Blog (DDoS incident): [https://github.blog/2018-03-01-ddos-incident-report/](https://github.blog/2018-03-01-ddos-incident-report/)
