<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0b2416,100:00ff9c&height=200&section=header&text=Ryan%20Ruis&fontSize=56&fontColor=00ff9c&animation=twinkling&fontAlignY=36&desc=Seguran%C3%A7a%20da%20Informa%C3%A7%C3%A3o%20%C2%B7%20Linux%20%C2%B7%20Python&descAlignY=58&descSize=17" alt="Ryan Ruis" width="100%"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ryan-ruis-b1a0a6277"><img src="https://img.shields.io/badge/LinkedIn-Ryan%20Ruis-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ryan.ruissilvaatitude@gmail.com"><img src="https://img.shields.io/badge/E--mail-Contato-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>
  <img src="https://img.shields.io/badge/TryHackMe-Estudando-212C42?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe"/>
  <img src="https://komarev.com/ghpvc/?username=ryan-ruis&label=VISITAS&color=00ff9c&style=for-the-badge" alt="Visitas ao perfil"/>
</p>

<p align="center">
  <img src="./assets/terminal.svg" alt="Terminal animado: whoami, execução do SUID Scanner e objetivo" width="90%"/>
</p>

---

## 📡 Reconhecimento do alvo

```console
ryan@ruis:~$ nmap -sV --script=perfil ryan-ruis

PORT      STATE     SERVICE     VERSION
22/tcp    open      linux       Bash · Shell Script · permissões · SUID
53/tcp    open      redes       TCP/IP · modelo OSI · endereçamento · serviços
80/tcp    open      python      POO · automação · ferramentas CLI com Rich
443/tcp   open      security    Seg. da Informação (UNIP) · Fortinet · Cloud
8080/tcp  open      suporte     SaaS · troubleshooting · reprodução de falhas
3306/tcp  filtered  sql         em estudo...

| perfil-info:
|   localização : Santo André - SP, Brasil
|   foco        : auditoria Linux, redes e Python para segurança
|_  status      : aberto a oportunidades

Nmap done: 1 IP address (1 host up) scanned — 5 serviços abertos, 1 em evolução
```

<table>
  <tr>
    <td align="center" width="25%">🐧<br/><b>Linux</b><br/><sub>Shell, permissões e auditoria do sistema</sub></td>
    <td align="center" width="25%">🌐<br/><b>Redes</b><br/><sub>TCP/IP, modelo OSI e firewall</sub></td>
    <td align="center" width="25%">🐍<br/><b>Python</b><br/><sub>Ferramentas de linha de comando para segurança</sub></td>
    <td align="center" width="25%">🔍<br/><b>Investigação</b><br/><sub>Reprodução de falhas, evidências e causa raiz</sub></td>
  </tr>
</table>

> O suporte técnico me ensinou a reproduzir falhas e isolar causas. A segurança da informação me ensina a entender **como os sistemas quebram**, e a transformar isso em proteção.

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

O bit **SUID** pode fazer um programa rodar com os privilégios do dono do arquivo, muitas vezes o `root`. Por isso ele é um dos primeiros pontos verificados numa auditoria de escalonamento de privilégios. O SUID Scanner localiza esses arquivos e ajuda a priorizar a revisão:

| Recurso | Como funciona |
|---|---|
| 🔍 **Varredura** | `find -perm -4000` e reconfirmação do bit SUID via `os.stat` |
| 🚦 **Classificação de risco** | Catálogo heurístico: shells, interpretadores, editores e utilitários → **CRÍTICO · ALTO · MÉDIO · REVISAR** |
| 📋 **Contexto** | Permissões, dono, grupo, impacto e recomendação para cada achado |
| 📄 **Relatório** | Exportação em JSON para documentação e comparação entre varreduras |
| 🔐 **Somente leitura** | Não explora, não escala privilégios e não altera nenhum arquivo |

---

## 🧪 Outros projetos

| Projeto | Descrição | Stack |
|---|---|---|
| 🎮 [Pokémon Terminal RPG](https://github.com/ryan-ruis/Meu-jogo-Pokemon) | RPG no terminal com orientação a objetos: herança, polimorfismo e persistência com pickle | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| 📇 [Agenda de Contatos](https://github.com/ryan-ruis/Agenda-de-Contatos-em-Python) | CRUD em Python, usado também em aulas de programação e desenvolvimento seguro | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |

<details>
<summary><b>🗺️ Roadmap: próximos alvos</b></summary>
<br/>

- [x] Ferramenta de auditoria de permissões SUID no Linux
- [ ] Scanner de portas em Python (reconhecimento de rede)
- [ ] Testes automatizados e exportação CSV no SUID Scanner
- [ ] SQL e bancos de dados aplicados à investigação
- [ ] Automação com Selenium + Excel

</details>

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

## 📈 Atividade

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ryan-ruis&bg_color=0d1117&color=00ff9c&line=00ff9c&point=58a6ff&area=true&area_color=00ff9c&hide_border=true&custom_title=Commits%20nos%20%C3%BAltimos%2031%20dias" alt="Gráfico de atividade" width="100%"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ryan-ruis/ryan-ruis/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ryan-ruis/ryan-ruis/output/github-snake.svg"/>
    <img alt="Cobrinha comendo o gráfico de contribuições" src="https://raw.githubusercontent.com/ryan-ruis/ryan-ruis/output/github-snake-dark.svg"/>
  </picture>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-aberto%20a%20oportunidades-00ff9c?style=for-the-badge&labelColor=0d1117" alt="Aberto a oportunidades"/>
</p>
<p align="center">
  <sub>Segurança da Informação · Suporte Técnico N2 · Infraestrutura · Automação</sub><br/>
  <sub><code>// Hack ético: só teste o que você tem autorização para testar.</code></sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff9c,50:0b2416,100:0d1117&height=110&section=footer" alt="footer" width="100%"/>
</p>
