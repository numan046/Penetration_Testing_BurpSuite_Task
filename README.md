# Penetration_Testing_BurpSuite_Task

## 📄 Project Documentation

This repository contains a comprehensive penetration testing lab setup using **Burp Suite** and **DVWA (Damn Vulnerable Web Application)**. The complete project report with detailed steps, screenshots, and findings is available below.

---

## 📎 **View Full Project Report**

Click the link below to access the complete documentation:

[📥 **Download/View Project Report (docs)**](https://docs.google.com/document/d/1jBbUt6Itkhx78SotuhtBrCc7-9On0Mc8/edit?usp=sharing&ouid=113904372385578713823&rtpof=true&sd=true)

---

### 📌 **What's Inside the Report?**

| **Section** | **Description** |
|-------------|-----------------|
| **Introduction** | Overview of Burp Suite and penetration testing |
| **Setup Guide** | Step-by-step installation of Docker, DVWA, and Burp Suite |
| **Configuration** | Proxy settings, certificate installation, and browser setup |
| **Attack Demonstrations** | Brute Force, SQL Injection, and XSS attacks with screenshots |
| **MITRE ATT&CK Mapping** | Mapping attacks to MITRE framework |
| **Mitigation Strategies** | Security measures to prevent vulnerabilities |
| **Conclusion** | Summary and key takeaways |

---

### 🚀 **Quick Setup Commands**

```bash
# Install Docker
sudo apt update && sudo apt install docker.io -y

# Start Docker
sudo systemctl start docker

# Setup DVWA
mkdir dvwa-docker && cd dvwa-docker
nano docker-compose.yaml
# Add DVWA configuration

# Launch container
docker-compose up -d

# Access DVWA
http://localhost:8080
