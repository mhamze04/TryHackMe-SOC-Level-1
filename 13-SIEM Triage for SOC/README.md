# 🔍 SIEM Triage for SOC (TryHackMe)

Ce dépôt documente ma progression et les compétences acquises dans le module **SIEM Triage for SOC** de TryHackMe. J'y ai appris à exploiter la puissance des SIEM pour détecter les signaux faibles d'attaques, investiguer des alertes réelles et corréler des logs multi-sources afin de reconstruire la chronologie exacte d'un incident.

---

## 📋 Présentation du Module
L'objectif de cette formation est de maîtriser le triage opérationnel au sein des deux SIEM leaders du marché (Splunk et Elastic Stack) à travers des scénarios de compromission réels.

### 🚀 Salles & Compétences Pratiques

#### 1. Log Analysis with SIEM
* **Concepts :** Compréhension de la manière dont les solutions SIEM agrègent et normalisent les données pour détecter les comportements malveillants.
* **Techniques :** Corrélation de logs provenant de sources hétérogènes (firewalls, serveurs web, endpoints) pour identifier des anomalies comportementales.

#### 2. Alert Triage With Splunk
* **Pratique :** Utilisation intensive du langage **SPL** (Splunk Processing Language) pour filtrer le bruit et isoler les activités suspectes.
* **Compétences :** Triage efficace des alertes de sécurité, pivotement entre différents types de logs et extraction d'indicateurs de compromission (IoCs).

#### 3. Alert Triage With Elastic
* **Pratique :** Triage d'alertes via Kibana en utilisant le langage de requête **KQL** (Kibana Query Language).
* **Compétences :** Analyse approfondie de logs systèmes et applicatifs pour repérer des menaces persistantes et comprendre le vecteur d'une intrusion.

#### 4. Challenge Pratique : `ItsyBitsy`
* **Scénario :** Investigation d'un incident réel en s'appuyant sur l'écosystème **ELK** (Elasticsearch/Kibana).
* **Objectifs atteints :** Analyse de connexions réseau suspectes, identification de requêtes de type Command & Control (C2) et découverte d'une exfiltration de données.

#### 5. Challenge Pratique : `Benign`
* **Scénario :** Enquête forensique avancée sur un hôte suspecté d'être compromis.
* **Objectifs atteints :** Différenciation fine entre les activités légitimes de l'entreprise (fichiers/processus bénins) et les techniques de dissimulation utilisées par un attaquant pour maintenir son accès.

---

## 🛠️ Compétences Techniques Validées
* **Triage Opérationnel :** Capacité à qualifier rapidement une alerte SIEM en Vrai Positif (TP) ou Faux Positif (FP).
* **Langages de Requêtes :** Requêtage avancé en SPL (Splunk) et KQL (Elastic).
* **Reconstruction d'Incidents :** Corrélation chronologique (Timeline) pour reconstituer le scénario complet d'une compromission.

---
*Formation complétée sur [TryHackMe](https://tryhackme.com)*
