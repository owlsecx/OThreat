# 🛡️ OThreat

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-ODefense%20%2F%20Threat%20Intelligence-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-requests-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v2.0-cyan?style=flat-square"/>
</p>

> **OThreat** is a malicious URL checker that queries **VirusTotal** and **URLScan.io** to determine the reputation and threat level of any URL. It provides unified verdicts, detailed detection statistics, and full reporting.

---

## 📌 Overview

OThreat combines two major threat intelligence platforms to give you fast and reliable URL reputation checks. It supports single URL analysis, batch processing, and configurable polling for URLScan.io results.

**⚠️ LEGAL NOTICE**: For educational and authorized security analysis only. Never scan URLs without explicit permission.

---

## 🖥️ Modules

| # | Module                  | Description |
|---|-------------------------|-------------|
| **[1]** | **Check URL**               | Full check using VirusTotal + URLScan.io |
| **[2]** | **Batch Check**             | Analyze multiple URLs from a text file |
| **[3]** | **VT Only**                 | VirusTotal lookup only (fast) |
| **[4]** | **URLScan Only**            | Submit and poll URLScan.io |
| **[5]** | **Last Results**            | View the most recent scan report |
| **[6]** | **Settings**                | Configure API keys, polling, output path |

---

## 📊 Key Features

- **Unified Verdict**: MALICIOUS / SUSPICIOUS / CLEAN / UNKNOWN
- **VirusTotal Integration**: Malicious detections, categories, last analysis date
- **URLScan.io Integration**: Score, community verdict, screenshot, report link
- **Batch Processing**: Check many URLs at once with CSV summary
- **Detailed Reporting**: JSON export with full metadata
- **Configurable Polling**: Adjustable interval and max attempts for URLScan
- **Clear Visual Output**: Color-coded verdicts and risk indicators

---

## ⚙️ Requirements

- **Linux or Windows**
- **requests** library (`pip install requests`)
- **API Keys**:
  - VirusTotal (free tier available)
  - URLScan.io (free account)

---

## 🚀 Usage

```bash
./OThreat

📁 Output

Terminal Display — Color-coded verdict and detailed breakdown
JSON Reports — Saved to ounified_results/ with timestamp
Batch CSV — Summary of all URLs in a batch scan
Last Results — Quick access to the most recent scan


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED THREAT INTELLIGENCE USE ONLY
