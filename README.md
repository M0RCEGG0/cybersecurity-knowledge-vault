# 🛡️ Cybersecurity Knowledge Vault

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Knowledge%20Base-red?style=for-the-badge&logo=hackthebox)
![GitHub Pages](https://img.shields.io/badge/Live%20Docs-GitHub%20Pages-blue?style=for-the-badge&logo=github)
![HTML5](https://img.shields.io/badge/HTML5-Modern%20Dark%20Theme-orange?style=for-the-badge&logo=html5)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

> 🌐 **Acesse o portal online e interativo:**  
> 👉 **[https://m0rcegg0.github.io/cybersecurity-knowledge-vault/](https://m0rcegg0.github.io/cybersecurity-knowledge-vault/)**

---

## 📖 Sobre este Repositório

O **Cybersecurity Knowledge Vault** é um portal autoral e centralizado de documentação técnica, anotações de laboratório e pesquisas práticas sobre segurança da informação, redes, testes de intrusão (pentest) e defesa cibernética.

Desenvolvido com uma interface limpa em **HTML5 e CSS3 moderno (Dark Theme técnico)**, o portal foi projetado para oferecer leitura agradável tanto no desktop quanto no mobile, servindo como uma base de consulta rápida e perene para profissionais e pesquisadores da área.

---

## 📚 Estrutura dos Módulos Disponíveis

| Módulo | Título Técnico | Principais Tópicos & Ferramentas |
| :---: | :--- | :--- |
| **01** | [Princípios Fundamentais](docs/01-principios-cyberseguranca.html) | Tríade CIA, tipos de hackers, Red/Blue Team, Zero Trust e PoLP. |
| **02** | [Redes de Computadores](docs/02-redes-computadores.html) | Modelo OSI vs. TCP/IP, Three-Way Handshake, portas fundamentais e diagnóstico. |
| **03** | [Usuários & Permissões Linux](docs/03-usuarios-linux.html) | Estrutura de `/etc/passwd` e `/etc/shadow`, auditoria de UID 0 e PoLP. |
| **04** | [SSH & Acesso Seguro](docs/04-ssh-linux.html) | Criptografia assimétrica (Ed25519), SCP/SFTP e hardening em `sshd_config`. |
| **05** | [OSINT & Fontes Abertas](docs/05-osint-ciberseguranca.html) | Google Dorks, Shodan, Exploit-DB, Maltego e mineração de metadados com FOCA. |
| **06** | [Varredura com Nmap](docs/06-varredura-nmap.html) | Descoberta de hosts, SYN Scan (`-sS`) vs. TCP Connect (`-sT`) e estados de portas. |
| **07** | [Técnicas de Enumeração](docs/07-enumeracao.html) | Banners, scripts Lua do NSE (SMB, HTTP, FTP) e enumeração de versões. |
| **08** | [Fundamentos de Pentest](docs/08-fundamentos-pentest.html) | Metodologia PTES em 5 fases, Black/Grey/White Box e métricas CVSS. |
| **09** | [Exploração com Metasploit](docs/09-exploracao-vulnerabilidades.html) | Ciclo `msfconsole`, exploração do `vsftpd 2.3.4` e geração de trojans com `msfvenom`. |
| **10** | [Força Bruta com Medusa](docs/10-brute-force-medusa.html) | Password spraying, módulos de rede, smbclient e mitigação com MFA/Fail2ban. |
| **11** | [Pós-Exploração & Pivoting](docs/11-pos-exploracao.html) | Sessões Meterpreter, elevação de privilégios (`getsystem`), Kiwi/Mimikatz e persistência. |
| **12** | [Engenharia Social](docs/12-engenharia-social.html) | Gatilhos de Cialdini, Spear-Phishing, Whaling, Vishing e testes com SET. |
| **13** | [Deep Web & Anonimização](docs/13-deepweb-anonimizacao.html) | Roteamento em cebola (Tor), relays, Tails OS, Whonix e regras estritas de OpSec. |

---

## 🛠️ Como Executar Localmente

Você pode clonar e visualizar o portal localmente sem precisar instalar servidores ou dependências:

```bash
# 1. Clone o repositório
git clone https://github.com/M0RCEGG0/cybersecurity-knowledge-vault.git

# 2. Acesse a pasta
cd cybersecurity-knowledge-vault

# 3. Abra o index.html no seu navegador favorito
# No Windows:
start index.html

# No Linux:
xdg-open index.html
```

---

## ⚖️ Aviso Ético & Legal

> Todo o conteúdo disponibilizado neste repositório destina-se exclusivamente a fins educacionais, de pesquisa acadêmica e de segurança defensiva. A realização de varreduras não autorizadas, tentativas de intrusão ou ataques contra sistemas de terceiros sem autorização prévia e expressa é crime.

---

Mantido por **[@M0RCEGG0](https://github.com/M0RCEGG0)**.
