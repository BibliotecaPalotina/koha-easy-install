# 📚 Koha Easy Install - Advanced Management Suite (v3.0)

[![Koha ILS](https://img.shields.io/badge/Koha-ILS-2563eb?style=flat-square&logo=koha)](https://koha-community.org/)
[![Ubuntu Supported](https://img.shields.io/badge/Ubuntu-22.04%20%7C%2024.04-E95420?style=flat-square&logo=ubuntu)](#)
[![Bash Script](https://img.shields.io/badge/Script-Bash-4EAA25?style=flat-square&logo=gnu-bash)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

Uma suíte de administração **"Production-Grade"** completa, interativa e autossuficiente para implantação, manutenção, tuning e backups automáticos do sistema de bibliotecas **Koha ILS**.

Criado para simplificar a vida de bibliotecários e administradores de TI, o script transforma tarefas complexas de infraestrutura em um **Painel de Controle Visual** acessível diretamente pelo terminal.

---

## ✨ Principais Funcionalidades

O sistema opera através do comando `sudo options.sh` e oferece mais de 20 ferramentas integradas:

- 🚀 **Instalação 100% Automatizada:** Prepara todo o ambiente LAMP (Linux, Apache, MariaDB, Perl) e configura o Koha com as melhores práticas de segurança em poucos minutos.
- ☁️ **Backups em Nuvem (Rclone):** Integração nativa e expressa com **Google Drive** e outras nuvens. Gera, compacta, valida e envia dumps SQL e registros MARC21 automaticamente.
- ⚙️ **Tuning Dinâmico de Memória:** Calcula e aplica as melhores configurações para o Plack (Workers), Memcached e MariaDB (InnoDB) com base na memória RAM disponível no servidor.
- 🔍 **Gestão de Motor de Busca:** Alterne entre os motores **Zebra** e **Elasticsearch** (com instalação e rebuild automáticos) usando apenas uma opção do menu.
- 🛡️ **Segurança e Exposição:**
  - Instalação automatizada do **Cloudflare Tunnel (Zero Trust)** para publicar o catálogo sem abrir portas no roteador.
  - Blindagem nativa com UFW (Firewall) e Fail2ban.
  - Geração de certificados SSL gratuitos (Let's Encrypt).
- 🛠️ **Arquitetura à Prova de Falhas:** Edição segura do `koha-conf.xml` via Python (não quebra a estrutura XML), captura e bypass inteligente de travas do `apt`, e atualização atômica do próprio script via GitHub.
- 🌐 **Bilíngue Automático:** A interface detecta a linguagem do SO e adapta todas as telas para Português (pt-BR/pt-PT) ou Inglês (en).

---

## 💻 Requisitos do Sistema

- **Sistema Operacional:** Ubuntu Server / Desktop (22.04 LTS ou 24.04 LTS) ou Debian 11/12. Funciona perfeitamente em Servidor Físico, VPS, VirtualBox ou WSL2 (Windows).
- **Privilégios:** Acesso de Administrador (`root` ou `sudo`).
- **Hardware Mínimo:** 2 vCPUs e 4GB de RAM (Recomendado: 8GB+ para uso fluido do Elasticsearch).

---

## ⚡ Instalação Rápida (Quick Start)

Abra o terminal do seu servidor Linux e cole os três comandos abaixo. Eles farão o download seguro do script, darão permissão de execução e iniciarão o painel:

```bash
sudo curl -fsSL "https://raw.githubusercontent.com/BibliotecaPalotina/koha-easy-install/refs/heads/main/installer" -o /usr/local/bin/options.sh && sudo chmod +x /usr/local/bin/options.sh && sudo options.sh
