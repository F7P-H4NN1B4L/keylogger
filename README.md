# 🔐 Python Keylogger (Educational)

<!-- Skill Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Cybersecurity-0A0A0A?style=flat&logo=hackthebox&logoColor=green" />
  <img src="https://img.shields.io/badge/Red%20Team-8B0000?style=flat" />
  <img src="https://img.shields.io/badge/Blue%20Team-003366?style=flat" />
  <img src="https://img.shields.io/badge/Malware%20Analysis-4B0082?style=flat" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-000000?style=flat&logo=kalilinux&logoColor=white" />
</p>
---

> **⚠️ Disclaimer**
>
> This project is created **for educational purposes only**.
> It is intended to demonstrate how keylogging techniques work so developers, students, and security researchers can **understand, detect, and defend against such threats**.
>
> **Do NOT use this code on systems you do not own or have explicit permission to test.**
> The author is **not responsible for any misuse** of this project.

---

## 📌 Project Overview

This Python script demonstrates how a **basic keylogger** can be implemented using:
- Keyboard event hooks
- Timed reporting
- Secure logging concepts
- Webhook-based reporting (Discord)

The goal is to help cybersecurity learners understand **how keylogging attacks operate** so they can better **detect and mitigate them**.

---

## 🧠 Educational Objectives

- Learn how keyboard events are captured at the OS level
- Understand periodic data exfiltration methods
- Analyze how attackers format and transmit logs
- Improve detection techniques (EDR / AV / SIEM)
- Practice ethical red team analysis

---

## ⚙️ Features

- Keystroke capture using `keyboard`
- Time-based reporting system
- Discord webhook reporting
- Automatic log cleanup
- Username and timestamp tagging
- Large log handling via file upload
- ```pyinstaller --onefile --noconsole keylogger.py``` {to make the script run with no window}

---

## 🛡️ Ethical Usage

✔️ Allowed:
- Learning cybersecurity concepts
- Malware analysis labs
- Red team simulations (with permission)
- Defensive research

❌ Not allowed:
- Spying on users
- Unauthorized monitoring
- Illegal deployment

---

## 🧪 Technologies Used

- Python 3
- Keyboard event hooks
- Threading & timers
- Webhooks
- File handling
- OS interaction

---


## 🧩 Future Improvements (Educational)

- Encryption of logs
- Detection evasion analysis (defensive study)
- SIEM detection rules
- Memory-based logging research

---

## 📜 License

This project is released for **educational and research use only**.
You are responsible for complying with local laws and ethical standards.
