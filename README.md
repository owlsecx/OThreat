# 🦉 OThreat

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OWeb-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OThreat** — Malicious URL Intelligence Engine ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OThreat is a malicious-URL intelligence engine that checks URL reputation against VirusTotal and URLScan.io. It submits and correlates results from both services to give a consolidated verdict, and supports batch analysis with CSV/JSON export. It is intended for authorized defensive analysis and never scans URLs without ownership or permission.

---

## ✨ Features


- URL reputation lookups via VirusTotal and URLScan.io, correlated into a single verdict
- Batch URL analysis from a list
- Threaded submission and polling for faster multi-URL runs
- Clear, colour-coded risk presentation in the terminal
- CSV and JSON export of results
- Offline --self-test for safe verification

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OThreat
./OThreat --self-test
./OThreat --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
