# 🔐 Write-ups TryHackMe — Yaniselbak

> Documentation de mon apprentissage en cybersécurité offensive.
> Chaque room est détaillée avec ma méthodologie, les outils utilisés et les leçons apprises.

---

## 📊 Progression

![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat&logo=tryhackme&logoColor=white)

- 🔄 Parcours : **Jr Penetration Tester** *(en cours)*
- 🏆 Rooms complétées : **6** *(mise à jour régulière)*
- 🎯 Objectif : CompTIA Security+

---

## 📁 Write-ups

| Room | Difficulté | Outils | Compréhension |
|------|-----------|--------|------|
| 🔄 Offensive Security Introduction | Easy | gobuster, terminal Linux, navigateur web | Bases du pentest web |
| 🔄 Défensive Security Introduction | Easy | 	SIEM (simulation), tableau d'alertes SOC | Rôle d'un SOC |
| 🔄 Defensive Security (2) | Easy | SIEM (simulation), outil de réputation d'IP | Analyse d'alertes |
| 🔄 Junior Security Analyst Intro |	Easy | SIEM (simulation), ticketing / escalade | Métier d'analyste SOC N1 |
| 🔄 Search Skills | Easy | Google Dorks, Shodan, Censys, VirusTotal, Have I Been Pwned, Exploit-DB, NVD (CVE), pages man | Recherche avancée & OSINT |
| 🔄 Linux | Easy | Terminal bash : ls, cd, pwd, cat, echo, whoami, find, grep | Commandes Linux de base |

---

## 🛠️ Outils découverts / utilisés

| Outil | Catégorie | Utilité | Statut |
|------|-----------|--------|------|
| `gobuster` | 🔴 Offensif | Découverte de répertoires cachés | ✅ Utilisé |
| SIEM | 🔵 Défensif | Analyse d'alertes de sécurité | ✅ Utilisé |
| VirusTotal | 🔵 Défensif | Analyse de fichiers / IP suspects | ✅ Utilisé |
| Google Dorks | 🔎 OSINT | Recherche avancée | ✅ Utilisé |
| Shodan | 🔎 OSINT | Recherche d'appareils exposés | ✅ Utilisé |
| Exploit-DB / NVD | 🔎 OSINT | Recherche de vulnérabilités (CVE) | ✅ Utilisé |
| Bash | 🐧 Système | Commandes Linux | ✅ Utilisé |
| Python | 🐍 Dév | Scripts de scan et d'analyse de logs | ✅ Utilisé |
| `nmap` | 🔴 Offensif | Scan de ports et services | 📚 En apprentissage |
| `hydra` | 🔴 Offensif | Attaque par force brute | 📚 En apprentissage |
| Burp Suite | 🔴 Offensif | Interception de requêtes web | 📚 En apprentissage |
| Metasploit | 🔴 Offensif | Exploitation de vulnérabilités | 📚 En apprentissage |
| `netcat` | 🔴 Offensif | Connexions réseau / reverse shell | 📚 En apprentissage |
---

## 📌 Structure d'un write-up

nom-de-la-room/
├── README.md       → objectif, méthodologie, commandes, leçons apprises
---

> ⚠️ Ces write-ups sont à des fins éducatives uniquement.
