# template-depot-git
## Template de Projet Développement logiciel et dépôt Git — BTS CIEL

[![Utiliser ce template](https://img.shields.io/badge/GitHub-Use%20this%20template-brightgreen?logo=github)](https://github.com/boudjelaba/template-depot-git/generate)

## Description
Ce template sert d'exemple pour les étudiants souhaitant créer un dépôt GitHub pour leurs projets en développement logiciel. Il montre une structure de base avec des fichiers essentiels (HTML, CSS, JS, Python) et des bonnes pratiques pour organiser un dépôt.

## Prérequis
Avant de commencer, assurez-vous d’avoir les éléments suivants installés :
- [Git](https://git-scm.com/) pour gérer le contrôle de version (pour travailler en local et pousser les modifications vers Github).
- [Python](https://www.python.org/downloads/) pour exécuter des scripts Python (si nécessaire).

---

### Informations sur le dépôt

[![GitHub Stars](https://img.shields.io/github/stars/Axel-G-prog/template-depot-git-axel.svg)](https://github.com/Axel-G-prog/template-depot-git-axel)
[![GitHub Forks](https://img.shields.io/github/forks/Axel-G-prog/template-depot-git-axel.svg)](https://github.com/Axel-G-prog/template-depot-git-axel/network/members)
[![GitHub Watchers](https://img.shields.io/github/watchers/Axel-G-prog/template-depot-git-axel.svg)](https://github.com/Axel-G-prog/template-depot-git-axel)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Créé le](https://img.shields.io/github/created-at/Axel-G-prog/template-depot-git-axel?label=Créé%20le)
![Dernier commit](https://img.shields.io/github/last-commit/Axel-G-prog/template-depot-git-axel?label=Dernier%20commit)
[![Status](https://img.shields.io/badge/Status-En%20développement-yellow.svg)]()
![Taille du repo](https://img.shields.io/github/repo-size/Axel-G-prog/template-depot-git-axel?label=Taille%20du%20repo)
![GitHub code size](https://img.shields.io/github/languages/code-size/Axel-G-prog/template-depot-git-axel)
![GitHub language count](https://img.shields.io/github/languages/count/Axel-G-prog/template-depot-git-axel)
![GitHub file count](https://img.shields.io/github/directory-file-count/Axel-G-prog/template-depot-git-axel)
[![GitHub Issues](https://img.shields.io/github/issues/Axel-G-prog/template-depot-git-axel.svg)](https://github.com/Axel-G-prog/template-depot-git-axel/issues)
[![Version](https://img.shields.io/badge/version-1.0.7-green.svg)](https://github.com/Axel-G-prog/template-depot-git-axel)
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](https://github.com/Axel-G-prog/template-depot-git-axel/blob/main/CONTRIBUTORS.md)
<img src="https://img.shields.io/badge/Raspberry%20Pi-5-red?logo=raspberrypi" alt="Raspberry Pi">


---

### Informations sur le projet

[![github](https://img.shields.io/badge/GitHub-black?logo=github&logoColor=white)]()
[![GIT](https://img.shields.io/badge/GIT-E44C30?logo=git&logoColor=white)]()
[![Markdown](https://img.shields.io/badge/Markdown-191970?logo=markdown&logoColor=white)](https://www.markdownguide.org/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)]()
[![mac os](https://img.shields.io/badge/mac%20os-000000?logo=apple&logoColor=white)]()
[![windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)]()

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript)
[![HTML & CSS](https://img.shields.io/badge/HTML%20%26%20CSS-yellow?logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web)

---

## Table des matières

<!-- TOC START -->
- [Template de Projet Développement logiciel et dépôt Git — BTS CIEL](#template-de-projet-développement-logiciel-et-dépôt-git--bts-ciel)
  - [Description](#description)
  - [Prérequis](#prérequis)
    - [Informations sur le dépôt](#informations-sur-le-dépôt)
    - [Informations sur le projet](#informations-sur-le-projet)
  - [Table des matières](#table-des-matières)
  - [Objectifs](#objectifs)
  - [Structure du template GitHub](#structure-du-template-github)
  - [Comment utiliser ce template](#comment-utiliser-ce-template)
  - [À faire](#à-faire)
  - [Commandes utiles](#commandes-utiles)
  - [Bonnes pratiques](#bonnes-pratiques)
  - [Contribution](#contribution)
    - [Création du dépôt GitHub](#création-du-dépôt-github)
  - [Bonnes pratiques](#bonnes-pratiques-1)
  - [Feuille de route](#feuille-de-route)
  - [Automatisation du sommaire](#automatisation-du-sommaire)
    - [Utilisation](#utilisation)
  - [Licence](#licence)
  - [Auteurs](#auteurs)
<!-- TOC END -->

---

## Objectifs

- la gestion de projet collaboratif,
- Prendre en main Git et GitHub,
- l’organisation d’un dépôt Git/GitHub propre,
- comprendre l'importance du versionnement
- la structuration d’un code source réutilisable,
- la documentation et le suivi de projet.

---

## Structure du template GitHub

```plaintext
📁 template-depot-git/
├── README.md        # Fichier de description du projet
├── .gitignore       # Fichiers à ignorer dans Git
├── CONTRIBUTING.md  # Guide de contribution
├── LICENSE          # Licence du projet
├── assets/          # Contient les fichiers statiques et les scripts (images, CSS, JS, etc.)
│   ├── logo.png
│   ├── css/
│   │  └── style.css
│   └── js/
│      └── script.js
├── scripts/         # Scripts et outils divers
│   └── generate_toc.py
└── index.html       # Page d'accueil du projet
```

## Comment utiliser ce template

1. Cliquez sur **"Use this template"** en haut à droite de la page GitHub.
2. Créez un nouveau dépôt à partir de ce template.
3. Clonez votre nouveau dépôt sur votre machine :
   ```bash
   git clone <url-de-votre-nouveau-depot>
   ```
4. Créez une branche de développement :
   ```bash
   git checkout -b dev
   ```
5. Ajoutez ou modifiez des fichiers :
   * **index.html** : Modifiez le code HTML pour refléter votre projet.
   * **style.css** : Adaptez le style CSS à vos besoins.
   * **script.js** : Ajoutez votre logique JavaScript.
6. Enregistrez vos modifications :
   ```bash
   git add .
   git commit -m "Ajout de mes modifications"
   git push origin dev
   ```
7. Créez une Pull Request sur GitHub pour proposer vos changements.
8. Exécutez les scripts :
   Vous pouvez exécuter `generate_toc.py` de cette manière pour générer une table des matières automatiquement :
   ```bash
   python scripts/generate_toc.py
   ```

**Si vous n'avez pas de compte Github**

Pour utiliser ce template, commencez par cloner le dépôt Git sur votre machine locale :

```bash
git clone https://github.com/boudjelaba/template-depot-git.git
```



## À faire

- [ ] Forkez ce dépôt
- [ ] Créez une branche `dev`
- [ ] Ajoutez un nouveau fichier HTML ou modifiez celui existant
- [ ] Poussez vos changements
- [ ] Créez une Pull Request

## Commandes utiles

```bash
git clone <url>
git checkout -b nom-de-branche
git add .
git commit -m "mon message"
git push origin nom-de-branche
```

## Bonnes pratiques

- Travaillez toujours sur une branche dédiée (ex : `dev`, `feature/ma-fonctionnalite`)
- Décrivez clairement vos commits et Pull Requests
- Relisez le code avant de fusionner
  
---
Ce template est conçu pour faciliter la collaboration et l’apprentissage autour de Git et GitHub.

---

## Contribution

Si vous souhaitez contribuer à ce projet, veuillez lire le fichier [CONTRIBUTING.md](CONTRIBUTING.md) pour connaître les bonnes pratiques et les étapes à suivre.


### Création du dépôt GitHub

Initialiser le dépôt et le publier sur GitHub :

```bash
git init
git add .
git commit -m "Initial commit"
gh repo create mon_projet --public --source=. --remote=origin
git push -u origin main
```

---

## Bonnes pratiques

- **Ne jamais versionner les mots de passe ou secrets** : utilisez des fichiers d’exemple (`db.sample.php`).
- **Nettoyez régulièrement les fichiers temporaires**.
- **Protégez les dossiers sensibles avec `.htaccess`**.
- **Utilisez le script de déploiement pour éviter d’exposer des fichiers inutiles ou sensibles en production**.

---

## Feuille de route

- [x] Créer un nouveau dépôt Git
- [x] Créer une issue
- [ ] Support Multi-plateforme
    - [ ] MacOS
    - [ ] Linux
- [ ] Autre
---

<details><summary><b>Dates à retenir</b></summary>

1. Début du projet : Date 1
2. Fiches recettes : Date 2
3. Rapport et présentation : Date 3

</details>

<br>

---

## Automatisation du sommaire

### Utilisation

1. Enregistrer le fichier sous `generate_toc.py` dans le même dossier que le `readme.md`. (voir fichier joint)
2. Lancer-le avec :

```bash
python generate_toc.py
```

3. S'assurer d’avoir dans le `readme.md` une section avec les balises :

```bash
<!-- TOC START -->
<!-- TOC END -->
```

---
## Badges 

### 🌐 Réseaux & Outils

![Ethernet](https://img.shields.io/badge/-Ethernet-228B22?style=for-the-badge&logo=ethernet)
![Wi-Fi](https://img.shields.io/badge/-Wi--Fi-1C86EE?style=for-the-badge&logo=wi-fi)
![TCP/IP](https://img.shields.io/badge/-TCP/IP-4169E1?style=for-the-badge&logo=protocolsio)
![DNS](https://img.shields.io/badge/-DNS-8A2BE2?style=for-the-badge&logo=cloudflare)
![DHCP](https://img.shields.io/badge/-DHCP-9932CC?style=for-the-badge&logo=serverless)
![VPN](https://img.shields.io/badge/-VPN-00CED1?style=for-the-badge&logo=openvpn)
![OpenVPN](https://img.shields.io/badge/-OpenVPN-FB8C00?style=for-the-badge&logo=openvpn)
![WireGuard](https://img.shields.io/badge/-WireGuard-88171A?style=for-the-badge&logo=wireguard)
![Firewall](https://img.shields.io/badge/-Firewall-B22222?style=for-the-badge&logo=firefox)
![pfSense](https://img.shields.io/badge/-pfSense-223344?style=for-the-badge&logo=pfsense)
![Cisco](https://img.shields.io/badge/-Cisco-1BA0D7?style=for-the-badge&logo=cisco)
![Mikrotik](https://img.shields.io/badge/-Mikrotik-444444?style=for-the-badge&logo=mikrotik)
![Ubiquiti](https://img.shields.io/badge/-Ubiquiti-055574?style=for-the-badge&logo=ubiquiti)
![Nmap](https://img.shields.io/badge/-Nmap-214478?style=for-the-badge&logo=nmap)
![Wireshark](https://img.shields.io/badge/-Wireshark-0077AA?style=for-the-badge&logo=wireshark)
![SNMP](https://img.shields.io/badge/-SNMP-4B0082?style=for-the-badge&logo=snmp)
![IPv6](https://img.shields.io/badge/-IPv6-008000?style=for-the-badge&logo=internet-explorer)
![Netcat](https://img.shields.io/badge/-Netcat-708090?style=for-the-badge&logo=gnu-bash)
![NetworkManager](https://img.shields.io/badge/-NetworkManager-A52A2A?style=for-the-badge&logo=linux)
![Zabbix](https://img.shields.io/badge/-Zabbix-DC3522?style=for-the-badge&logo=zabbix)
![ARP](https://img.shields.io/badge/-ARP-556B2F?style=for-the-badge&logo=protocolsio)
![ICMP](https://img.shields.io/badge/-ICMP-4682B4?style=for-the-badge&logo=gnu-bash)
![BGP](https://img.shields.io/badge/-BGP-DC143C?style=for-the-badge&logo=cisco)
![OSPF](https://img.shields.io/badge/-OSPF-DAA520?style=for-the-badge&logo=networkx)
![VLAN](https://img.shields.io/badge/-VLAN-7B68EE?style=for-the-badge&logo=ubiquiti)
![NAT](https://img.shields.io/badge/-NAT-2E8B57?style=for-the-badge&logo=linux)
![Subnetting](https://img.shields.io/badge/-Subnetting-8FBC8F?style=for-the-badge&logo=internet-computer)
![Routing](https://img.shields.io/badge/-Routing-5F9EA0?style=for-the-badge&logo=router)
![Netstat](https://img.shields.io/badge/-Netstat-808080?style=for-the-badge&logo=gnubash)
![Traceroute](https://img.shields.io/badge/-Traceroute-2F4F4F?style=for-the-badge&logo=gnubash)
![iptables](https://img.shields.io/badge/-iptables-B22222?style=for-the-badge&logo=linux)
![fail2ban](https://img.shields.io/badge/-fail2ban-8B0000?style=for-the-badge&logo=protonvpn)
![Suricata](https://img.shields.io/badge/-Suricata-FF4500?style=for-the-badge&logo=suricata)
![Snort](https://img.shields.io/badge/-Snort-FF69B4?style=for-the-badge&logo=palo-alto-networks)
![Nagios](https://img.shields.io/badge/-Nagios-000000?style=for-the-badge&logo=nagios)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=for-the-badge&logo=prometheus)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=for-the-badge&logo=grafana)
![Netlify](https://img.shields.io/badge/-Netlify-00C7B7?style=for-the-badge&logo=netlify)
![Portainer](https://img.shields.io/badge/-Portainer-13BEF9?style=for-the-badge&logo=portainer)
![Ansible](https://img.shields.io/badge/-Ansible-EE0000?style=for-the-badge&logo=ansible)
![LAN](https://img.shields.io/badge/-LAN-228B22?style=for-the-badge&logo=networkx)
![WAN](https://img.shields.io/badge/-WAN-2E8B57?style=for-the-badge&logo=internet-computer)
![MAN](https://img.shields.io/badge/-MAN-4682B4?style=for-the-badge&logo=internet-computer)
![DMZ](https://img.shields.io/badge/-DMZ-B8860B?style=for-the-badge&logo=networkx)
![MAC Addressing](https://img.shields.io/badge/-MAC_Addressing-DAA520?style=for-the-badge&logo=wireshark)
![Packet Sniffing](https://img.shields.io/badge/-Packet_Sniffing-8B008B?style=for-the-badge&logo=wireshark)
![Deep Packet Inspection](https://img.shields.io/badge/-Deep_Packet_Inspection-9932CC?style=for-the-badge&logo=suricata)
![NetFlow](https://img.shields.io/badge/-NetFlow-708090?style=for-the-badge&logo=cisco)
![sFlow](https://img.shields.io/badge/-sFlow-556B2F?style=for-the-badge&logo=cisco)
![Spanning Tree](https://img.shields.io/badge/-Spanning_Tree-6A5ACD?style=for-the-badge&logo=networkx)
![RADIUS](https://img.shields.io/badge/-RADIUS-191970?style=for-the-badge&logo=openvpn)
![802.1X](https://img.shields.io/badge/-802.1X-483D8B?style=for-the-badge&logo=ubiquiti)
![MPLS](https://img.shields.io/badge/-MPLS-4B0082?style=for-the-badge&logo=cisco)
![QoS](https://img.shields.io/badge/-QoS-8B0000?style=for-the-badge&logo=networkx)
![Packet Filtering](https://img.shields.io/badge/-Packet_Filtering-5F9EA0?style=for-the-badge&logo=linux)
![IPSec](https://img.shields.io/badge/-IPSec-00CED1?style=for-the-badge&logo=openvpn)
![GRE Tunnel](https://img.shields.io/badge/-GRE_Tunnel-2F4F4F?style=for-the-badge&logo=linux)
![Reverse Proxy](https://img.shields.io/badge/-Reverse_Proxy-7B68EE?style=for-the-badge&logo=nginx)
![Load Balancing](https://img.shields.io/badge/-Load_Balancing-20B2AA?style=for-the-badge&logo=haproxy)
![Zero Trust](https://img.shields.io/badge/-Zero_Trust_Model-DC143C?style=for-the-badge&logo=protonvpn)


---

## 💻 Langages & Dev

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=for-the-badge&logo=java&logoColor=white)
![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Ruby](https://img.shields.io/badge/-Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
![C#](https://img.shields.io/badge/-C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node-dot-js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/-Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=for-the-badge&logo=flask&logoColor=white) 
![Spring](https://img.shields.io/badge/-Spring-6DB33F?style=for-the-badge\&logo=spring\&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)



---

## 🔧 IoT / Embedded

![Espressif](https://img.shields.io/badge/-Espressif-FF4B00?style=for-the-badge&logo=espressif&logoColor=white)
![ESP32](https://img.shields.io/badge/-ESP32-32C832?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)


---

## Licence

Ce projet est sous la licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

## Auteurs

- <r>&copy;</r> K.B.
- <o>&reg;</o> Carnus
- <g>Date :</g> 01/09/2025
