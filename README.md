<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0b2416,100:00ff9c&height=210&section=header&text=Ryan%20Ruis&fontSize=56&fontColor=00ff9c&animation=twinkling&fontAlignY=36&desc=Seguran%C3%A7a%20da%20Informa%C3%A7%C3%A3o%20%C2%B7%20Linux%20%C2%B7%20Python&descAlignY=58&descSize=17" alt="Ryan Ruis" width="100%"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=800&color=00FF9C&center=true&vCenter=true&width=680&lines=%24+whoami;Estudante+de+Seguran%C3%A7a+da+Informa%C3%A7%C3%A3o+%40+UNIP;Auditoria+Linux+%7C+Permiss%C3%B5es+%7C+SUID;Python+para+ferramentas+de+seguran%C3%A7a;Entender+como+quebra+%E2%86%92+saber+como+proteger" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ryan-ruis-b1a0a6277"><img src="https://img.shields.io/badge/LinkedIn-Ryan%20Ruis-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ryan.ruissilvaatitude@gmail.com"><img src="https://img.shields.io/badge/E--mail-Contato-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>
  <img src="https://img.shields.io/badge/TryHackMe-Estudando-212C42?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe"/>
  <img src="https://img.shields.io/badge/Santo%20Andr%C3%A9-SP-0d1117?style=for-the-badge&logo=googlemaps&logoColor=00ff9c" alt="Localização"/>
</p>

---

## `> whoami`

```bash
┌──(ryan㉿ruis)-[~]
└─$ cat perfil.txt

  nome      : Ryan Ruis
  formação  : Tecnólogo em Segurança da Informação — UNIP (último semestre)
  trabalho  : Suporte Técnico em plataforma SaaS (N1 → N2)
  foco      : Linux · Redes · Python para segurança · Auditoria de permissões
  mentalidade: investigar a causa raiz, não só o sintoma

└─$ cat motivacao.txt

  O suporte me ensinou a reproduzir falhas e isolar causas.
  A segurança me ensina a entender como os sistemas quebram
  e a transformar isso em proteção.
```

<table>
  <tr>
    <td align="center" width="25%">🐧<br/><b>Linux</b><br/><sub>Shell, permissões, SUID e auditoria do sistema</sub></td>
    <td align="center" width="25%">🌐<br/><b>Redes</b><br/><sub>TCP/IP, modelo OSI, endereçamento e firewall</sub></td>
    <td align="center" width="25%">🐍<br/><b>Python</b><br/><sub>Ferramentas de linha de comando para segurança</sub></td>
    <td align="center" width="25%">🔍<br/><b>Investigação</b><br/><sub>Reprodução de falhas, evidências e documentação</sub></td>
  </tr>
</table>

---

## 🛡️ Projeto em destaque

<h3 align="center">🔎 <a href="https://github.com/ryan-ruis/suid-scanner">SUID Scanner</a></h3>

<p align="center"><b>Auditoria defensiva de arquivos com permissão SUID em sistemas Linux</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-Auditoria-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Rich-CLI-8A2BE2?style=flat-square"/>
  <img src="https://img.shields.io/badge/Export-JSON-00ff9c?style=flat-square&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Licen%C3%A7a-MIT-green?style=flat-square"/>
</p>

O bit **SUID** pode fazer um programa rodar com os privilégios do dono do arquivo, muitas vezes o `root`. O SUID Scanner localiza esses arquivos e ajuda a priorizar quais merecem revisão:

- 🔍 Varredura com `find` e verificação do bit SUID via `os`/`stat`
- 🚦 Classificação heurística de risco potencial: **CRÍTICO · ALTO · MÉDIO · REVISAR**, com base em um catálogo de shells, interpretadores, editores e utilitários conhecidos
- 📋 Proprietário, grupo, permissões, impacto e recomendação para cada resultado
- 📄 Exportação do relatório em **JSON** para documentação e comparação
- 🔐 **Somente leitura**: não explora, não escala privilégios e não altera arquivos

```text
$ python3 suid_scanner.py --path /usr/bin --json relatorio.json

┏━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━┳━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━┓
┃ Caminho          ┃ Permissões ┃ Dono:Grupo ┃ Risco potencial ┃
┡━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━╇━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━┩
│ /usr/bin/exemplo │ -rwsr-xr-x │ root:root  │     REVISAR     │
└──────────────────┴────────────┴────────────┴─────────────────┘
                                         (exemplo ilustrativo)
```

---

## 🧪 Outros projetos

| Projeto | Descrição | Stack |
|---|---|---|
| 🎮 [Pokémon Terminal RPG](https://github.com/ryan-ruis/Meu-jogo-Pokemon) | RPG no terminal com orientação a objetos: herança, polimorfismo e persistência com pickle | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| 📇 [Agenda de Contatos](https://github.com/ryan-ruis/Agenda-de-Contatos-em-Python) | CRUD em Python, usado também em aulas de programação e desenvolvimento seguro | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |

### 🗺️ Próximos alvos

- [x] Ferramenta de auditoria de permissões SUID no Linux
- [ ] Scanner de portas em Python (reconhecimento de rede)
- [ ] Testes automatizados e exportação CSV no SUID Scanner
- [ ] Automação com Selenium + Excel

---

## 🧰 Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,bash,python,git,github,vscode&theme=dark" alt="Linux, Bash, Python, Git, GitHub, VS Code"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Fortinet-FortiGate-EE3124?style=for-the-badge&logo=fortinet&logoColor=white&labelColor=0d1117" alt="Fortinet"/>
  <img src="https://img.shields.io/badge/Redes-TCP%2FIP%20%C2%B7%20OSI-00ff9c?style=for-the-badge&logo=cisco&logoColor=white&labelColor=0d1117" alt="Redes"/>
  <img src="https://img.shields.io/badge/Cloud-Security-00ff9c?style=for-the-badge&logo=icloud&logoColor=white&labelColor=0d1117" alt="Cloud Security"/>
  <img src="https://img.shields.io/badge/Criptografia-Senhas-00ff9c?style=for-the-badge&logo=letsencrypt&logoColor=white&labelColor=0d1117" alt="Criptografia"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" alt="Selenium"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/OpenPyXL-217346?style=flat-square&logo=microsoftexcel&logoColor=white" alt="OpenPyXL"/>
  <img src="https://img.shields.io/badge/Rich-CLI-8A2BE2?style=flat-square" alt="Rich"/>
</p>

---

## 🎓 Formação & Certificações

| | Formação | Instituição |
|:-:|---|---|
| 🎓 | Tecnólogo em **Segurança da Informação** (último semestre) | UNIP |
| 🛡️ | **Cibersegurança com Soluções Fortinet** (60 h) | SENAI-SP |
| ☁️ | **Cibersegurança na Nuvem** (20 h) | SENAI-SP |
| 🔥 | **FortiGate 7.6 Operator** · **Technical Introduction to Cybersecurity 3.0** | Fortinet Training Institute |
| 🐧 | Linux e Shell Script para Pentesters · Fundamentos de Segurança e Pentest · Criptografia e Senhas | Solyd |
| 🐍 | Python Orientado a Objetos e Automação · Introdução ao Python e Algoritmos | Solyd |

---

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-aberto%20a%20oportunidades-00ff9c?style=for-the-badge&labelColor=0d1117" alt="Aberto a oportunidades"/>
</p>
<p align="center">
  <sub>Segurança da Informação · Suporte Técnico N2 · Infraestrutura · Automação</sub><br/>
  <sub><i>Use o conhecimento com ética: só teste o que você tem autorização para testar.</i></sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff9c,50:0b2416,100:0d1117&height=110&section=footer" alt="footer" width="100%"/>
</p>
