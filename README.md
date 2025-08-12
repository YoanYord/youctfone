# 🔐 YouCTFOne – Bulgarian CTF Training Platform

Welcome to **YouCTFOne**, a Bulgarian-language Capture The Flag (CTF) platform built to help aspiring and intermediate ethical hackers sharpen their skills in a safe, legal environment.

---

# CTF Platform is live at:
(https://yoanyord.github.io/youctfone/)
---
## 📦 What’s Inside?

This project contains **two custom-made vulnerable machines** with escalating levels of difficulty. Each is designed to simulate real-world attack scenarios.

### Basic SSH Challenge (Beginner-Friendly)
- NGINX server with status page exposing SSH state.
- Access to `/backup/` directory containing a leaked private SSH key.
- Hidden root password in a local file.
- Learn how to enumerate, connect via SSH, and escalate privileges manually.

### Advanced Web & Privilege Escalation Challenge
- Web service with hidden upload form discovered through directory fuzzing.
- File upload vulnerability with host header manipulation.
- SQL Injection via captured Burp Suite request, dumped using SQLMap.
- SSH access with credentials from the DB.
- Kernel privilege escalation via **DirtyPipe** (`CVE-2022-0847`).

### Forensics Challenge (Beginner-Friendly)
- Suspicious file with mismatched extension (.zip.exe) found.
- Investigation reveals the file is actually an image with embedded hidden data..
- Participants must identify the true file type, inspect the file headers, and extract the concealed message from within.
---

## 📚 Walkthroughs (Bulgarian)

You can find full walkthroughs for both challenges in the [GitBook documentation](https://yoans-organization.gitbook.io/youones-documentation/youctfone-ctf-platforma).

---

## 🛠 Technologies Used

- 🐧 Linux-based virtual machines
- 🌐 NGINX
- 💾 MySQL (for the advanced challenge)
- 🔐 SSH
- 🔧 Custom challenge scripting (Bash/PHP)

---

## ⚠️ Legal & Ethical Notice
All challenges are created for educational purposes only. Use this platform responsibly. Do not deploy these machines on public networks or attack systems you do not own or have explicit permission to test.

---
