# 🔐 Strengthening Security for Willy Wonka Industries  

## 📌 Overview  
Willy Wonka Industries faced multiple security threats, including **ransomware attacks, phishing incidents, unpatched systems, and weak access controls**. I developed a **comprehensive security strategy** to mitigate these risks and enhance the overall cybersecurity posture.  

## 🛠 Key Contributions  

- 🚀 **Implemented an integrated security stack** using **IPS, IDS, and EDR** technologies to protect against network intrusions and endpoint threats.  
- 🔍 **Conducted security assessments**, identified vulnerabilities, and enforced **vulnerability management** best practices.  
- 🛡 **Deployed Data Loss Prevention (DLP) policies** with **Microsoft Purview** to protect sensitive customer and employee data.  
- ⚡ **Implemented SOAR tools** for **automated incident response**, improving security operations and disaster recovery planning.  
- 🔐 **Enhanced access security** using **Cisco Duo Advantage MFA** and **strong password policies** to prevent unauthorized access.  
- 🌐 **Deployed Web Application Firewall (WAF)** (Cloudflare/Azure AWS) to mitigate **SQL injection, XSS, and other web-based attacks**.  
- 🔥 **Strengthened network security** with **Palo Alto Next-Gen Firewall** for smarter traffic filtering and detection of anomalous behavior.  
- 🏴‍☠️ **Reduced phishing and social engineering risks** through **mandatory employee security training** and email security improvements.  

---

## 🛠 Tools & Technologies Used  

| Category                     | Tools & Technologies |
|------------------------------|----------------------|
| 🔍 SIEM & Monitoring         | Splunk, Splunk UBA  |
| 🛡 EDR & Endpoint Security   | Microsoft Defender, CrowdStrike Falcon |
| 🔄 SOAR & Automation         | Palo Alto Cortex XSOAR |
| 📧 Email Security            | Mimecast |
| 🌐 Web Security              | Cloudflare WAF, Palo Alto NGFW, Snort (IDS/IPS) |
| 🔥 Firewall & VPN            | Palo Alto, Cisco ASA, NordLayer VPN |
| 📜 Compliance & DLP          | Microsoft Purview DLP |
| 🔑 Authentication & IAM      | Cisco Duo MFA, Strong Password Policies |
| 👨‍🏫 Security Awareness      | Phishing Simulations, Employee Training |
| 🚀 Incident Response & Recovery | SIEM, Backup & DR Strategy |

---

## ⚙️ Sample Configurations  

### 🚀 Snort IPS Rule for Network Intrusion Detection  
```bash
alert tcp any any -> 192.168.1.100 80 (msg:"Possible Web Exploit"; content:"GET"; nocase; sid:10001; rev:1;)
```

🔥 Deploying Palo Alto Firewall Policies
```bash
set security policies from-zone untrusted to-zone trusted policy Block_Malicious_traffic match source any destination any application any service any action deny
commit
```

🔑 Enforcing MFA with Cisco Duo
```bash
duo auth proxy start
duo user add --username <user> --email <user@example.com>
duo user enable-mfa --user <user>
```

📌 Key Takeaways

✅ Integrated multiple security layers to protect web applications, network infrastructure, and endpoint devices.
✅ Reduced security risks by implementing DLP, MFA, WAF, and Next-Gen Firewalls.
✅ Automated threat detection & incident response with SIEM, SOAR, and endpoint security tools.
✅ Enhanced employee security awareness to mitigate phishing and social engineering attacks.

⸻

🎤 Presentation & Impact

I delivered a technical presentation on the security improvements, showcasing the impact on Willy Wonka Industries’ cybersecurity resilience.

⸻

💬 Have Questions?

Feel free to reach out or open an issue! 🚀🔐
