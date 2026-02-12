# [Wifi-Attack]

[![Python Version](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Status Proyek](https://img.shields.io/badge/Status-Aktif-brightgreen.svg)]()

## Description
Tools ini di ciptakan untuk menyerang jaringan dengan mengirim packets yang sangat besar agar jaringan WIFI menjadi lag dan berbasis Python untuk Termux, dilengkapi fitur pemindaian klien. Dikembangkan untuk pembelajaran keamanan siber.

## Disclaimer
⚠️ **Peringatan & Tanggung Jawab Hukum**
Alat ini dibuat **hanya untuk tujuan edukasi dan pengujian keamanan pada jaringan yang Anda miliki atau miliki izin tertulis untuk diuji**. Penyalahgunaan alat ini untuk menyerang jaringan tanpa izin adalah tindakan ILEGAL. Pengembang tidak bertanggung jawab atas segala kerusakan atau pelanggaran hukum yang disebabkan oleh pengguna alat ini.

## 🖼️ Screenshot
| Tampilan |
| :---: |
| ![Screenshot UI](images/screenshots.png) |
| *Tempilan Sederhana Tools* |

## Support 
- Termux

## 🛠️ Installation

### 📋 Requirements:
- 🐍 **Python 3.x** (Download from [python.org](https://www.python.org/))
- 💻 **A terminal** (Command Prompt, Termux, PowerShell, Linux shell)

### 🚀 Steps:

1. **Instalasi**
   ```bash
   pkg update -y && pkg upgrade -y
   pkg install python -y
   pkg install python2 -y
   pkg install python3 -y
   pkg install git -y
   pkg install python-pip -y
   ```

2. **Clone the repository:**
   ```bash
   git clone https://github.com/NextTools-Py/Wifi-Attack.git
   cd Wifi-Attack
   
   ```

3. **Install required libraries:**
   ```bash
   pip install colorama requests
   pip3 install colorama requests
   ```
   - 🌈 **colorama:** For colorful console magic.
   - 🌐 **requests:** For HTTP attack power.


3. **Run the tool:**
   ```bash
   python3 Wifi-Attack.py
   ```

---
