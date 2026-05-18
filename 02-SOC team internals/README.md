# 🛡️ SOC Team Internals (TryHackMe)

Ce dépôt documente ma progression dans le module **SOC Team Internals**. J'y ai acquis les compétences essentielles d'un analyste SOC pour trier, classifier et escalader les alertes dans des environnements réels.

---

## 📋 Aperçu du Module
Ce module se concentre sur les rouages internes d'une équipe SOC et sur la méthodologie systématique de réponse aux incidents.

### 🚀 Labs & Compétences Clés

#### 1. SOC L1 Alert Triage
* **Objectif :** Développer une approche systématique pour traiter les alertes sans se laisser submerger.
* **Pratique :** Analyse de faux positifs vs vrais positifs. 
* **Étude de cas :** Analyse technique d'une campagne de phishing (détection via échecs SPF/DKIM).

#### 2. SOC L1 Alert Reporting
* **Objectif :** Apprendre à signaler, escalader et communiquer efficacement.
* **Compétences :** Rédaction de résumés d'incidents exploitables et compréhension des seuils d'escalade vers le niveau L2.

#### 3. SOC Workbooks and Lookups
* **Objectif :** Utiliser les ressources de l'entreprise pour simplifier le triage.
* **Concepts :**
    * **Lookups :** Identification rapide des assets et des identités (Qui ? Quoi ? Où ?).
    * **Workbooks :** Suivi de procédures standardisées (SOP) pour garantir la qualité de l'analyse.
    * **Architecture :** Interprétation de diagrammes réseau pour évaluer l'impact (zones DMZ).

#### 4. SOC Metrics and Objectives
* **Objectif :** Mesurer et améliorer l'efficacité du SOC.
* **Indicateurs Clés (KPIs) :**
    * **MTTD (Mean Time to Detect) :** Temps de détection.
    * **MTTR (Mean Time to Respond) :** Temps de remédiation.
    * **SLA (Service Level Agreement) :** Respect des engagements de temps de réponse.

---

## 🔍 Focus Technique : Investigation d'une intrusion
Dans ce module, j'ai notamment analysé une alerte de type **Domain Discovery** :
- **Vecteur :** Exploitation d'un serveur Web (`w3wp.exe`).
- **Artefact malveillant :** Détection d'un shell inversé (`revshell.exe`).
- **Action de l'attaquant :** Tentative d'énumération du groupe "Domain Admins".
- **Résultat :** Alerte qualifiée en **True Positive** avec demande de confinement immédiat de la machine.

---

## 🛠️ Stack & Méthodologie
* **Analyse de Logs :** Windows Event Logs, Email Headers.
* **Framework :** Alignement avec la phase de Reconnaissance/Discovery de MITRE ATT&CK.
* **Outils :** SIEM Dashboard, Asset Inventory, Network Topology Maps.

---
*Formation complétée sur [TryHackMe](https://tryhackme.com/)*
