# ☁️ Securing WordPress on AWS EC2 – LAMP Stack Hardening Project

This project demonstrates a secure deployment of a WordPress website hosted on an AWS EC2 instance using a hardened LAMP stack. The objective was to configure, secure, monitor, and validate both the cloud infrastructure and the web application.

---

## 📦 Project Overview

- 🛠 Set up an **EC2 instance** with firewall rules, SSH key authentication, and port restrictions
- ⚙️ Configured the full **LAMP stack** (Linux, Apache, MariaDB, PHP)
- 🌐 Deployed **WordPress**, configured its database, permissions, and security settings
- 🧱 Secured the instance using **Firewalld**, **Certbot (SSL)**, and hardened Apache/MySQL configs
- 🔍 Monitored the system using **AWS CloudWatch**
- 🧪 Validated with **Nikto** and **Nmap** scans from Kali Linux VM

---

## 🔐 Security Measures

### 🔧 Infrastructure
- SSH restricted to home IP
- Firewalld zones and services configured
- SSL/TLS implemented via **Certbot** (Let’s Encrypt)

### 🔒 WordPress Security Plugins
- Wordfence Security  
- Solid Security  
- Limit Login Attempts Reloaded  
- Login Lockdown  
- UpdraftPlus (backups)  
- Akismet Anti-Spam

---

## 🧪 Testing Tools
- **Nikto:** Detected HTTP TRACE and exposed sensitive files  
- **Nmap:** Revealed open ports, admin panels, and vulnerable services  
→ Actions taken: restricted ports, disabled TRACE, tightened access

---

## 📁 Contents

- `AWS_Security_Project.pdf` — Full report including steps, screenshots, and security analysis

---

## 🧠 Lessons Learned

- Gained practical experience in cloud platform configuration, service hardening, and WordPress security
- Learned the importance of layered defense: server config, app-level plugins, firewall, and external monitoring
- Developed habits for proactive testing and audit via Kali tools

---

## 📬 Contact

- 📧 Email: snehasivaram1968@gmail.com  
- 💼 LinkedIn: [Sneha Sivaram](https://www.linkedin.com/in/sneha-sivaram-2978b61b8)
