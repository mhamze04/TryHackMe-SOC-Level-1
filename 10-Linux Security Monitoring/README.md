# 🐧Linux Security Monitoring (TryHackMe)

Ce dépôt documente ma progression et les compétences acquises dans le module **Surveillance de la sécurité Linux** de TryHackMe. J'y ai appris à auditer, centraliser et analyser les journaux système Linux pour détecter les tactiques, techniques et procédures (TTPs) des cyberattaquants.

---

## 📋 Présentation du Module
L'objectif de cette formation est de comprendre l'écosystème de journalisation Linux et de savoir corréler les logs d'authentification, de processus et de noyau pour identifier les compromissions de serveurs.

### 🚀 Salles & Compétences Pratiques

#### 1. Journalisation Linux pour SOC (Linux Logs)
* **Concepts :** Compréhension des mécanismes de journalisation sous Linux (`syslog`, `rsyslog`, `systemd-journald`).
* **Pratique :** Exploration des fichiers de logs stratégiques situés dans `/var/log/` :
    * `/var/log/auth.log` ou `/var/log/secure` (Tentatives d'authentification, sessions SSH, élévation `sudo`).
    * `/var/log/syslog` ou `/var/log/messages` (Événements généraux du système).
* **Outils :** Utilisation intensive des utilitaires en ligne de commande (`grep`, `awk`, `sed`, `journalctl`) pour parser et filtrer de gros volumes de logs lors du triage.

#### 2. Détection des menaces Linux 1 : Accès Initial
* **Concepts :** Repérage des méthodes courantes d'intrusion sur les systèmes Linux.
* **Analyse :** Détection des attaques par force brute SSH (multiples échecs de connexion suivis d'un succès), exploitation de services web vulnérables et exécution de scripts malveillants à distance.

#### 3. Détection des menaces Linux 2 : Post-Intrusion
* **Concepts :** Surveillance des premières actions de l'attaquant après avoir pénétré le serveur.
* **Détection :** Identification de la phase de reconnaissance système (utilisation de `whoami`, `id`, `uname -a`, scans réseau locaux) et des tentatives d'**Élévation de privilèges** (recherche de fichiers SUID mal configurés, abus de commandes `sudo` ou exploitation de failles du noyau).

#### 4. Détection des menaces Linux 3 : Persistance & Actions Finales
* **Concepts :** Traque des techniques permettant à un attaquant de maintenir son accès ou de dissimuler ses traces.
* **Pratique :** Analyse des logs système pour débusquer les mécanismes de persistance :
    * Modification des tâches chronologiques (**Cron jobs**).
    * Ajout de clés SSH non autorisées dans `.authorized_keys`.
    * Création de services systèmes malveillants (`systemd`).
    * Nettoyage de l'historique des commandes (`.bash_history`).

---

## 🛠️ Boîte à Outils & Télémétrie Maîtrisée
* **Analyse en CLI :** `journalctl`, `grep`, `awk`, inspection de `/var/log/`.
* **Forensique Linux :** Audit de configurations de sécurité (`SSHd`, privilèges `sudoers`, fichiers SUID/SGID).
* **Modélisation :** Application des tactiques MITRE ATT&CK appliquées à l'écosystème Linux.

---
*Formation complétée sur [TryHackMe](https://tryhackme.com)*
