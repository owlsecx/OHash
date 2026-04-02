# 🔍 OHash

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OPassword%20%2F%20Hash%20Analysis-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-None%20(Standalone)-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OHash** is a complete hash analysis and cracking toolkit. It supports generating multiple hash types, identifying unknown hashes, dictionary attacks, brute-force with custom charsets, and hash comparison. Includes support for MD5, SHA family, Blake2, NTLM, CRC32, and bcrypt (verify only).

---

## 📌 Overview

OHash is a powerful, all-in-one tool for hash generation, identification, cracking, and analysis. It provides a clean terminal interface with colored output, real-time progress during cracking, detailed statistics, and automatic export to JSON and TXT formats. Designed for security professionals and researchers.

---

## 🖥️ Modules

| # | Module              | Description |
|---|---------------------|-------------|
| **[1]** | **Generate Hash**       | Compute multiple hash algorithms for text or file input |
| **[2]** | **Identify Hash**       | Detect hash type based on length and pattern matching |
| **[3]** | **Crack Hash**          | Dictionary attack using wordlist files |
| **[4]** | **Brute Force**         | Custom charset brute-force with configurable max length |
| **[5]** | **Compare Hashes**      | Compare two hashes or verify plaintext against a known hash |

---

## 📊 Supported Algorithms

- **Fast Hashes**: MD5, SHA1, SHA224, SHA256, SHA384, SHA512
- **Modern Hashes**: SHA3-256, SHA3-512, Blake2b, Blake2s
- **Legacy / Special**: NTLM (Windows), CRC32
- **Password Hashing**: bcrypt (generation & verification — requires optional dependency)

---

## 🔍 Key Features

- **Hash Identification**: Automatic detection using regex patterns and length
- **Dictionary Cracking**: Fast wordlist-based attacks with progress display
- **Brute Force**: Support for 7 preset charsets + custom charset with length control
- **Live Statistics**: Attempts count, speed (k/s), elapsed time
- **Export Options**: JSON (structured) and TXT (human-readable) reports
- **Safety Warnings**: Clear alerts for large brute-force combinations

---

## ⚙️ Requirements

- **Linux or Windows**
- **No Python installation needed** — runs as a standalone executable
- **Optional**: `bcrypt` support (bundled or installable)

---

## 🚀 Usage

```bash
./OHash

📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED SECURITY TESTING USE ONLY
