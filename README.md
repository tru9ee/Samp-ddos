# SAMP-DDOS - SA-MP Server DDoS Tool

[![Version](https://img.shields.io/badge/version-2.0-red.svg)](https://github.com/tru9ee/Samp-ddos)
[![Python](https://img.shields.io/badge/python-3.8+-red.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-red.svg)](https://opensource.org/licenses/MIT)

## 💀 Ultimate SA-MP DDoS Attack Tool

SAMP-DDOS is a powerful DDoS tool specifically designed to target SA-MP game servers. Capable of flooding game servers with packets to cause lag, disconnections, and complete server crashes.

## 🔥 Attack Features

- **SA-MP Query Flood** - Exploits server query protocol
- **RCON Brute Force** - Automated password attacks
- **Packet Spoofing** - Fake player connections
- **Network Saturation** - Bandwidth consumption attacks
- **Multi-threaded** - Up to 10,000 concurrent attacks
- **Telegram Bot Control** - Remote execution and monitoring

## 📋 Requirements

- Python 3.8+
- Linux (Recommended) / Windows / Android
- Active internet connection
- Target IP and Port

## 🚀 Installation

```bash
git clone https://github.com/tru9ee/Samp-ddos.git
cd Samp-ddos
pip install -r requirements.txt
python sa-mpddos.py
```

🎯 Usage

```bash
# Basic attack
python sa-mpddos.py --ip 192.168.1.1 --port 7777 --threads 500

# Advanced attack with spoofing
python sa-mpddos.py --ip example.com --port 7777 --method query --threads 1000 --spoof

# RCON brute force
python sa-mpddos.py --ip 1.2.3.4 --port 7777 --method rcon --wordlist passwords.txt
```

⚙️ Attack Parameters

Attack Type Description Effectiveness
Query Flood Overloads server query High
Player Spoof Fake connections Medium
RCON Attack Password cracking Critical
UDP Flood Bandwidth saturation Very High

⚠️ Educational Use Only

This tool is for educational and research purposes. Only use on servers you own or have explicit permission to test. Unauthorized attacks are illegal.

---

Disclaimer: Use responsibly. The developer is not responsible for misuse of this tool.

```
