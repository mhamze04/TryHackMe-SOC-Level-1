# 🌐 Web Security Monitoring (TryHackMe)

Ce dépôt documente ma progression et les compétences acquises dans le module **Web Security Monitoring** de TryHackMe. J'y ai appris à analyser les logs de serveurs web, le trafic réseau et les systèmes de fichiers pour détecter et neutraliser les attaques ciblant les infrastructures web.

---

## 📋 Présentation du Module
L'objectif de cette formation est de maîtriser les techniques de surveillance et de détection orientées SOC pour protéger l'écosystème web des organisations face aux menaces modernes (OWASP Top 10, Web Shells, DDoS).

### 🚀 Salles & Compétences Pratiques

#### 1. Web Security Essentials
* **Concepts :** Fonctionnement des requêtes/réponses HTTP(S), architecture des applications web et mécanismes de protection (WAF, politiques de cookies, en-têtes de sécurité).
* **Sensibilisation :** Introduction aux risques majeurs de sécurité web et aux impacts métiers associés.

#### 2. Detecting Web Attacks
* **Analyse de Logs :** Corrélation et analyse approfondie des logs de serveurs web (Apache, Nginx, IIS) à la recherche de payloads malveillants.
* **Détection :** Identification visuelle et par expressions régulières des attaques courantes du top 10 OWASP, notamment les injections SQL (SQLi), les inclusions de fichiers (LFI/RFI) et le Cross-Site Scripting (XSS).

#### 3. Detecting Web Shells
* **Concepts :** Compréhension des scripts malveillants (PHP, ASPX) téléversés par les attaquants pour obtenir un accès persistant à distance sur un serveur.
* **Pratique :** Combinaison de trois méthodes de détection clés :
    * **Analyse de logs :** Repérage des requêtes HTTP suspectes ou inhabituelles (ex: accès direct à des scripts inconnus dans des répertoires de téléversement).
    * **Analyse de fichiers :** Inspection des timestamps, détection d'obfuscation et vérification d'intégrité du code.
    * **Trafic réseau :** Identification des flux de Command & Control (C2) initiés par la Web Shell.

#### 4. Detecting Web DDoS
* **Concepts :** Mécanismes des attaques par déni de service distribué (DDoS) au niveau de la couche applicative (Layer 7).
* **Détection :** Analyse des pics brutaux de trafic, des anomalies dans la distribution des requêtes (User-Agents suspects, volumes inhabituels par IP) et stratégies de mitigation pour préserver la disponibilité des services.

---

## 🛠️ Outils & Analyse Opérationnelle
* **Log Analysis :** Parsing et filtrage de logs HTTP (Codes statuts 200, 404, 500, structures d'URI).
* **Forensique Serveur :** Détection de fichiers d'arrière-plan malveillants (Web Shell Hunting).
* **Analyse Réseau :** Surveillance des volumes de requêtes (DDoS detection).

---
*Formation complétée sur [TryHackMe](https://tryhackme.com)*
