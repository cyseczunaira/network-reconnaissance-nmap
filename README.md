# 🔍 Network Reconnaissance with Nmap

## 📖 Project Overview

This project demonstrates the fundamentals of network reconnaissance in a safe virtual lab environment.

The objective was to learn how to discover hosts, identify open ports, detect running services, and perform operating system detection using Nmap.

---

## 🎯 Objectives

- Build a cybersecurity home lab
- Verify network connectivity
- Perform basic network reconnaissance
- Identify open TCP ports
- Detect service versions
- Identify the operating system

---

## 🖥️ Lab Environment

| Component | Details |
|----------|---------|
| Attacker Machine | Kali Linux |
| Target Machine | Metasploitable 2 |
| Virtualization | Oracle VirtualBox |
| Network | Host-Only Adapter |

---

## 🛠️ Tools Used

- Kali Linux
- Nmap
- VirtualBox
- Metasploitable 2

---

## 📝 Commands Used

### Check Connectivity

```bash
ping -c 4 192.168.56.102
```

### Basic Port Scan

```bash
nmap 192.168.56.102
```

### Service Version Detection

```bash
nmap -sV 192.168.56.102
```

### Operating System Detection

```bash
sudo nmap -O 192.168.56.102
```

---

## 📊 Results

The reconnaissance process successfully:

- Verified connectivity between the attacker and target machines.
- Identified multiple open TCP ports.
- Detected services running on those ports.
- Performed operating system fingerprinting using Nmap.

---

## 📚 Skills Learned

- Linux
- Kali Linux
- VirtualBox
- Nmap
- Network Reconnaissance
- Port Scanning
- Service Enumeration
- Operating System Detection

---

## ⚠️ Disclaimer

This project was conducted in an isolated virtual lab environment for educational purposes only. No unauthorized systems were scanned or tested.
