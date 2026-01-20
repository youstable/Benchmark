# 🚀 Enterprise grade linux server testing script 2026 updated with Uplink, Disk, Network, and other hardware health

[![ShellCheck](https://img.shields.io/badge/ShellCheck-Passed-brightgreen?style=for-the-badge&logo=gnu-bash)](https://www.shellcheck.net/)
[![Bash](https://img.shields.io/badge/Bash-4%2B-blue?style=for-the-badge&logo=gnu-bash)](https://www.gnu.org/software/bash/)
[![Website](https://img.shields.io/badge/Author-rajeshchauhan.me-purple?style=for-the-badge)](https://rajeshchauhan.me)

---

## 🔍 Overview

**YouStable Benchmark Suite** is a **production-grade Linux server benchmarking script** built for **DevOps engineers, system administrators, and hosting providers** who need **fast, reliable, and repeatable infrastructure diagnostics**.

The script delivers **accurate CPU, Memory, Disk I/O, Network Speed, OS, and Virtualization metrics** with minimal dependencies and enterprise-safe execution.

Designed for:
- VPS & Dedicated Server benchmarking
- Cloud infrastructure audits
- Hosting performance validation
- Pre-migration and post-deployment checks

---

## ⚙️ Features

- ✅ CPU model, cores, frequency, cache
- ✅ RAM & swap usage analysis
- ✅ Accurate disk capacity calculation (byte-level)
- ✅ Disk I/O benchmarking
  - Uses `fio` automatically if available
  - Falls back to `dd` for universal compatibility
- ✅ Global network speed tests (Ookla Speedtest CLI)
- ✅ OS, kernel, architecture detection
- ✅ Virtualization detection (KVM, Docker, LXC, OpenVZ, Dedicated)
- ✅ Public IP, ISP & geo lookup
- ✅ Clean, branded terminal output
- ✅ Safe execution with auto-cleanup

---

## 🏆 Why YouStable Benchmark Suite?

| Capability | Business Value |
|----------|----------------|
| **Production-safe bash** | No partial execution or silent failures |
| **Minimal dependencies** | Runs on almost any Linux server |
| **Accurate benchmarks** | No misleading disk or memory stats |
| **Hosting-ready branding** | Ideal for audits & client reports |
| **Automation-friendly** | Can be embedded in CI/CD pipelines |

---

## 📦 Requirements

- `bash`
- `curl` or `wget`
- Core Linux utilities (`free`, `df`, `awk`)
- Optional (auto-detected):
  - `fio` (recommended for enterprise I/O testing)

✔ Supported platforms:
- Ubuntu / Debian
- CentOS / AlmaLinux / Rocky Linux
- CloudLinux
- VPS, Dedicated Servers, Cloud Instances
- Docker & LXC containers

---

## ⚡ Quick Start

### Run via `curl`
```bash
curl -fsSL https://raw.githubusercontent.com/youstable/Benchmark/main/bench.sh | bash


