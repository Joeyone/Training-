# DVWA Training Lab – Offensive Web Security Practice

This repository is created **for training and learning purposes only**, using the **Damn Vulnerable Web Application (DVWA)** platform.

The goal of this project is to provide a **structured, repeatable playground** for understanding common web vulnerabilities, how attackers exploit them, and how defenders should detect and mitigate them in real environments.

> ⚠️ **Legal & Ethical Notice**
>
> This project is intended **strictly for educational use in a controlled lab environment**.
> Do **NOT** use these techniques on systems you do not own or have explicit permission to test.

---

## 🎯 Objectives

- Understand **common web application vulnerabilities**
- Practice **hands-on exploitation** in a safe lab
- Learn **attacker mindset** to improve defensive controls
- Familiarize with **tools, payloads, and wordlists**
- Build muscle memory for **real-world pentesting workflows**

---

## 🧪 Lab Environment

- Platform: **DVWA (Damn Vulnerable Web Application)**
- Deployment:
  - Docker / VM / Local LAMP stack
- Security Levels Tested:
  - Low
  - Medium
  - High (limited)
- Browser:
  - Firefox / Chromium
- Attacker Machine:
  - Kali Linux

---

## 🔓 Vulnerabilities Covered

This lab focuses on the following DVWA modules:

- SQL Injection (GET & POST)
- Command Injection
- File Inclusion (LFI / RFI)
- File Upload
- Brute Force
- Cross-Site Scripting (XSS – Reflected & Stored)
- CSRF
- Authentication weaknesses

Each vulnerability includes:
- Attack explanation
- Commands or payloads used
- Notes on why it works
- Defensive insight

---

## 🛠 Tools Used

Common tools used throughout this training:

- `curl`
- `sqlmap`
- `hydra`
- `wfuzz`
- `ffuf`
- Burp Suite
- Browser DevTools

No automated exploitation without understanding the **manual logic first**.

---

## 📁 Repository Structure

