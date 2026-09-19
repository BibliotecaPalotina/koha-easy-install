<div align="right">
  <a href="README.md">English</a> | <strong>Português (Brasil)</strong>
</div>

# 📚 Koha Easy Install - Suíte Avançada de Gestão (v3.0)

[![Koha ILS](https://img.shields.io/badge/Koha-ILS-2563eb?style=flat-square&logo=koha)](https://koha-community.org/)
[![Ubuntu Supported](https://img.shields.io/badge/Ubuntu-22.04%20%7C%2024.04-E95420?style=flat-square&logo=ubuntu)](#)
[![Debian Supported](https://img.shields.io/badge/Debian-11%20%7C%2012-D70A53?style=flat-square&logo=debian)](#)
[![Bash Script](https://img.shields.io/badge/Script-Bash-4EAA25?style=flat-square&logo=gnu-bash)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

Uma suíte de administração **"Production-Grade"** completa, interativa e autossuficiente para implantação, manutenção, otimização de desempenho e automação de backups do sistema de bibliotecas **Koha ILS**.

Desenvolvida para bibliotecários e administradores de TI, esta ferramenta transforma procedimentos avançados de terminal e infraestrutura Linux em um **Painel de Controle Visual (TUI)** intuitivo, seguro e à prova de falhas.

---

## ⚡ Início Rápido (Quick Start)

Execute o comando atômico em linha única abaixo como `root` (ou com `sudo`) para efetuar o download seguro do script, aplicar permissões de execução e iniciar o painel interativo:

```bash
sudo curl -fsSL "[https://raw.githubusercontent.com/BibliotecaPalotina/koha-easy-install/refs/heads/main/installer](https://raw.githubusercontent.com/BibliotecaPalotina/koha-easy-install/refs/heads/main/installer)" -o /usr/local/bin/options.sh && sudo chmod +x /usr/local/bin/options.sh && sudo options.sh
