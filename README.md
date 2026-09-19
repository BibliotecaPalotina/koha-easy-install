<div align="right">
  <strong>English</strong> | <a href="README.pt-BR.md">Português (Brasil)</a>
</div>

# 📚 Koha Easy Install - Advanced Management Suite (v3.0)

[![Koha ILS](https://img.shields.io/badge/Koha-ILS-2563eb?style=flat-square&logo=koha)](https://koha-community.org/)
[![Ubuntu Supported](https://img.shields.io/badge/Ubuntu-22.04%20%7C%2024.04-E95420?style=flat-square&logo=ubuntu)](#)
[![Bash Script](https://img.shields.io/badge/Script-Bash-4EAA25?style=flat-square&logo=gnu-bash)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

A complete, interactive, and self-contained **Production-Grade** management suite for deploying, maintaining, tuning, and automating backups for **Koha ILS**.

Designed for systems librarians and IT administrators, this suite turns complex Linux administration and Koha maintenance tasks into an intuitive **TUI (Terminal User Interface) Control Dashboard**.

---

## ⚡ Quick Start

Run this single, atomic command as root or with `sudo` to safely download the installer, set execute permissions, and launch the interactive control panel:

```bash
sudo curl -fsSL "[https://raw.githubusercontent.com/BibliotecaPalotina/koha-easy-install/refs/heads/main/installer](https://raw.githubusercontent.com/BibliotecaPalotina/koha-easy-install/refs/heads/main/installer)" -o /usr/local/bin/options.sh && sudo chmod +x /usr/local/bin/options.sh && sudo options.sh
