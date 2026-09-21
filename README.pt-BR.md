<div align="right">
  <a href="README.md">English</a> | <strong>Português (Brasil)</strong>
</div>

# 📚 Koha Easy Install & Tools - Suíte Avançada de Gestão (v3.0)

[![Koha ILS](https://img.shields.io/badge/Koha-ILS-2563eb?style=flat-square&logo=koha)](https://koha-community.org/)
[![Ubuntu Supported](https://img.shields.io/badge/Ubuntu-22.04%20%7C%2024.04%20%7C%2026.04-E95420?style=flat-square&logo=ubuntu)](#)
[![Bash Script](https://img.shields.io/badge/Script-Bash-4EAA25?style=flat-square&logo=gnu-bash)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

Uma suíte de gerenciamento completa, interativa e independente de **Padrão de Produção** para implantação, manutenção, tuning e backups automáticos do **Koha ILS**.

Criada para bibliotecários de sistemas e administradores de TI, esta suíte transforma tarefas complexas de administração Linux e manutenção do Koha em um **Painel de Controle Interativo (TUI)** intuitivo.

---

## ⚡ Instalação Rápida

Execute este comando único e atômico como root ou usando `sudo` para baixar o instalador de forma segura, definir as permissões e abrir o painel de controle interativo.

**Copie e cole todo o bloco abaixo no seu terminal:**

```bash
sudo curl -fsSL "[https://raw.githubusercontent.com/BibliotecaPalotina/koha-easy-install/refs/heads/main/installer](https://raw.githubusercontent.com/BibliotecaPalotina/koha-easy-install/refs/heads/main/installer)" -o /usr/local/bin/options.sh && sudo chmod +x /usr/local/bin/options.sh && sudo options.sh
