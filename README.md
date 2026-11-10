# devsec-mini-audit
A lightweight Python CLI utility to audit HTTP security headers and generate executive reports.

**Get the official release package and future updates on Gumroad: 
Link Gumroad copy and paste on your research browsers: (https://vivaumberto.gumroad.com/l/ypdlyp?_gl=1*iquss6*_ga*NDY2NTYzMDk3LjE3OTM1NzU4MTQ.*_ga_6LJN6D94N6*czE3OTQyNzA1NDQkbzQkZzEkdDE3OTQyNzE0MTQkajI4JGwwJGgw) .**

# DevSec Mini-Audit CLI 🐍🔒
**Version: 1.1 (Patch Update)**

[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A lightweight, enterprise-grade Python command-line utility designed to audit HTTP security headers, analyze response status codes, and instantly generate clean, professional HTML executive reports with compliance scoring.

---

## ⚡ Key Features

- **Automated Compliance Score:** Automatically calculates an overall security percentage and assigns a visual grade (Grade A, B, or C).
- **Comprehensive 10-Point Audit:** Checks critical HTTP defense headers:
  - Strict-Transport-Security (HSTS)
  - Content-Security-Policy (CSP)
  - X-Frame-Options (Clickjacking protection)
  - X-Content-Type-Options
  - Referrer-Policy & Permissions-Policy
  - X-XSS-Protection, CORP, COOP, and Server header obfuscation.
- **HTTP Status Diagnostics:** Automatically inspects the HTTP response status code (e.g., 200 OK, 301, 403) with clear textual descriptions.
- **Executive HTML Reports:** Generates a modern, responsive `security_report.html` dashboard complete with *"Why it matters"* educational tooltips for each check.
- **Zero Heavy Dependencies:** Runs purely on Python 3.x and standard `requests`.

## Requirements
- Python 3.x installed on your system.

## Dependency Installation
Open your terminal inside the project directory and run:
```bash or powershell
pip install requests


How to use: Run the script from your terminal passing the target URL as an argument: python scanner.py [https://yourdomain.com](https://yourdomain.com)
