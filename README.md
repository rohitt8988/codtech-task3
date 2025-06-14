# codtech-task3
# 🛡️ Penetration Testing Toolkit (Python Based)

A powerful and modular Python-based toolkit designed for penetration testers, ethical hackers, and cybersecurity researchers. This toolkit aims to streamline common offensive security tasks by offering a collection of extensible tools and utilities for information gathering, vulnerability scanning, exploitation, and post-exploitation.

---

## ✒️ Author

**Rohit Patel**  
Intern at **CodTech**

---

## ⚙️ Features

- 🔍 **Information Gathering**
  - Port scanner (TCP/UDP)
  - Banner grabbing
  - WHOIS & DNS lookup
- 🔓 **Vulnerability Scanning**
  - Basic CVE checks
  - Service-specific scriptable scanners
- 🚪 **Exploitation Modules**
  - Brute force tools (SSH, FTP, etc.)
  - Web vulnerability testers (XSS, SQLi)
- 🧬 **Post-Exploitation**
  - Reverse shell generators
  - Persistence techniques
- 🔄 **Modular Architecture**
  - Easily add or remove tools via plugins
  - Supports CLI argument parsing and logging

---

## 🐍 Built With

- Python 3.x
- `socket`, `subprocess`, `requests`, `argparse`
- Optional: `nmap`, `paramiko`, `scapy`

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.x installed:

```bash
python3 --version
