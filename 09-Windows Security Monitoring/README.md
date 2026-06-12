# 🪟 Windows Security Monitoring (TryHackMe)

Ce dépôt documente ma progression et les compétences acquises dans le module **Surveillance de la sécurité Windows** de TryHackMe. J'y ai appris à auditer, analyser et exploiter la journalisation Windows pour traquer et détecter des attaques complexes à chaque étape du cycle de vie d'une intrusion.

---

## 📋 Présentation du Module
L'objectif de cette formation est de maîtriser les mécanismes de surveillance internes de l'écosystème Windows (Event Logs, Sysmon) afin d'identifier les comportements malveillants, de l'accès initial au maintien de la persistance.

### 🚀 Salles & Compétences Pratiques

#### 1. Journalisation Windows pour SOC (Windows Event Logs)
* **Concepts :** Architecture du service de journalisation Windows. Compréhension des principaux journaux : Application, Système, Sécurité et Journaux analytiques/débogage.
* **Pratique :** Utilisation d'outils comme l'**Observateur d'événements (Event Viewer)** et **PowerShell (Get-WinEvent)** pour filtrer efficacement des milliers de logs.
* **IDs d'événements critiques maîtrisés :**
    * `4624` (Ouverture de session réussie) / `4625` (Échec d'ouverture de session).
    * `4688` (Création de processus) / `7045` (Création d'un nouveau service).

#### 2. Détection des menaces Windows 1 : Accès Initial
* **Concepts :** Repérage des tactiques utilisées par les attaquants pour s'introduire dans l'infrastructure Windows.
* **Détection :** Analyse des tentatives d'accès initial, comme l'exploitation de services exposés, le phishing menant à l'exécution de macros ou de scripts malveillants, et l'analyse de la télémétrie **Sysmon** (notamment l'Event ID `1` pour la création de processus).

#### 3. Détection des menaces Windows 2 : Post-Intrusion
* **Concepts :** Traque des premières actions d'un attaquant fraîchement introduit dans le système.
* **Analyse :** Détection des techniques d'**Élévation de privilèges** (UAC Bypass, exploitation de vulnérabilités locales), d'**Énumération/Reconnaissance** (utilisation de `whoami`, `net user`, `nltest`) et de mouvements latéraux.

#### 4. Détection des menaces Windows 3 : Persistance
* **Concepts :** Identification des mécanismes discrets configurés par les attaquants pour maintenir leur accès, même après un redémarrage du système.
* **Pratique :** Chasse aux anomalies dans les composants Windows détournés, tels que les **Tâches planifiées (Scheduled Tasks)**, les clés de registre de démarrage (**Run/RunOnce**), la création de services malveillants ou la manipulation de comptes locaux/Active Directory.

---

## 🛠️ Boîte à Outils & Télémétrie Maîtrisée
* **Outils d'analyse :** Event Viewer, PowerShell, Sysinternals Suite (Sysmon).
* **Analyse Forensic Windows :** Parsing de structures d'Event IDs pour reconstruire la chronologie d'un incident.
* **Framework :** Alignement direct avec la matrice MITRE ATT&CK (Initial Access, Privilege Escalation, Discovery, Persistence).

---
*Formation complétée sur [TryHackMe](https://tryhackme.com)*
