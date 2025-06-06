# Security Regression Framework

This repository contains a Python-based framework for security regression testing.

## 🎯 Purpose

Ensure previously fixed vulnerabilities (XSS, JWT bypass, SQLi, etc.) remain mitigated across new code changes or deployments.

## ✅ Features

- Automated tests for common web app vulns
- Reproducible payloads and expected outputs
- GitHub Actions CI integration
- Easily extendable to custom test cases or new CVE classes

## 🚀 Usage

```bash
pip install -r requirements.txt
pytest tests/
