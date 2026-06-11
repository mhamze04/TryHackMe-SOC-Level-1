# 🛡️ Network Security Monitoring (TryHackMe)

Ce dépôt documente ma progression et les compétences acquises dans le module **Network Security Monitoring** de TryHackMe. J'y ai appris à surveiller les périmètres réseau, à analyser les logs à la recherche d'empreintes d'attaques complexes et à configurer des systèmes de détection d'intrusion (IDS).

---

## 📋 Présentation du Module
L'objectif de cette formation est de maîtriser les outils et les règles de détection permettant de repérer les tactiques réseau des adversaires, de la reconnaissance initiale à l'exfiltration finale des données.

### 🚀 Salles & Compétences Pratiques

#### 1. Network Security Essentials
* **Concepts :** Principes fondamentaux de la sécurité périmétrique (Firewalls, Proxies, architectures de zone).
* **Stratégie :** Mise en place d'une visibilité globale pour collecter la télémétrie réseau nécessaire au SOC.

#### 2. Network Discovery Detection
* **Analyse :** Compréhension des techniques d'énumération des attaquants (scans de ports verticaux/horizontaux, scans de bannières).
* **Détection :** Identification des signatures de reconnaissance réseau (patterns de requêtes SYN massives, requêtes ICMP) dans les logs et le trafic.

#### 3. Data Exfiltration Detection
* **Concepts :** Analyse des canaux détournés par les attaquants pour faire sortir des données sensibles de l'entreprise.
* **Pratique :** Détection de l'exfiltration via des protocoles légitimes mais détournés, tels que les tunnels **DNS** (requêtes TXT inhabituelles), le trafic **ICMP** (payloads suspects) ou le protocole **HTTP/HTTPS**.

#### 4. Man-in-the-Middle (MITM) Detection
* **Concepts :** Fonctionnement des attaques d'interception réseau au niveau de la couche 2 et 3.
* **Détection :** Identification des anomalies réseau trahissant une attaque MITM, notamment l'**ARP Spoofing** (analyse des tables ARP et détection des réponses ARP gratuites/non sollicitées).

#### 5. IDS Fundamentals & Snort
* **Concepts :** Principes de fonctionnement des Systèmes de Détection d'Intrusion (IDS) basés sur les signatures et les anomalies.
* **Pratique (Snort) :** * Écriture et déploiement de règles Snort personnalisées pour détecter des alertes spécifiques.
    * Analyse de trafic en temps réel et traitement de fichiers PCAP en mode hors-ligne.
    * Compréhension de la structure d'une règle Snort (Header: Action, Protocole, IP/Ports ; Options: Message, Content, SID).

---

## 🛠️ Outils & Technologies Clés
* **IDS / IPS :** Snort (Écriture de règles, analyse d'alertes).
* **Analyse de Menaces :** Détection d'ARP Spoofing, Tunnels DNS, Scans Nmap.
* **Logs Réseau :** Analyse de flux et de télémétrie réseau.

---
*Formation complétée sur [TryHackMe](https://tryhackme.com/)*
