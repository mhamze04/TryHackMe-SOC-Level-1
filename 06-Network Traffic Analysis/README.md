# 🌐 Network Traffic Analysis

Ce dépôt documente ma progression et les compétences acquises dans le module **Analyse du trafic réseau** de TryHackMe. J'y ai appris à capturer, inspecter et analyser les flux réseaux à l'aide de Wireshark et NetworkMiner pour détecter des comportements malveillants et des anomalies.

---

## 📋 Présentation du Module
L'objectif de cette formation est de maîtriser l'analyse de paquets (Packet Analysis) et la forensique réseau afin d'identifier des attaques courantes (scans de ports, exfiltration de données, injections) directement au niveau de la couche réseau.

### 🚀 Salles & Compétences Pratiques

#### 1. Notions de base sur le trafic réseau (Network Traffic Fundamentals)
* **Concepts :** Compréhension des protocoles fondamentaux (IP, TCP, UDP, ICMP) et du modèle OSI.
* **Techniques :** Mécanismes de collecte du trafic (TAP réseau, Port Mirroring / SPAN) et importance de la visibilité réseau pour un SOC.

#### 2. Wireshark : Les bases
* **Pratique :** Prise en main de l'interface de Wireshark et ouverture de fichiers de capture (`.pcap`).
* **Compétences :** Analyse de la structure des paquets et dissection des protocoles de base (DNS, HTTP, TCP handshake).

#### 3. Wireshark : Opérations sur les paquets (Packet Operations)
* **Concepts :** Apprendre à "trouver une aiguille dans une botte de foin".
* **Pratique :** Maîtrise des filtres de display Wireshark complexes (ex: `http.request.method == "POST"` ou `tcp.flags.syn == 1`).
* **Analyse :** Utilisation des flux de coloration et reconstruction de sessions TCP complètes (*Follow TCP Stream*) pour lire les conversations en texte brut.

#### 4. Wireshark : Analyse du trafic (Traffic Analysis)
* **Concepts :** Détection des anomalies et des patterns d'attaques.
* **Pratique :** Identification de comportements suspects tels que les scans de ports, le vol d'identifiants (HTTP non sécurisé), les attaques par force brute ou les exfiltrations de données via des requêtes DNS inhabituelles.

#### 5. NetworkMiner
* **Concepts :** Outil d'analyse forensique réseau (NFAT) passif.
* **Pratique :** Extraction automatisée d'artefacts à partir de fichiers PCAP (images, fichiers transférés, identifiants, listes d'hôtes et de certificats) sans avoir à parser manuellement les paquets.

---

## 🛠️ Boîte à Outils Maîtrisée
* **Analyse de paquets :** Wireshark (Filtres avancés, Flux TCP/UDP).
* **Forensique Réseau :** NetworkMiner.
* **Protocoles Inspectés :** TCP, UDP, ICMP, DNS, HTTP, TLS.

---
*Formation complétée sur [TryHackMe](https://tryhackme.com/)*
