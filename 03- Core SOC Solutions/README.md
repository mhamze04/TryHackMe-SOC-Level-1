# 🛠️ Core SOC Solutions (TryHackMe)

Ce dépôt regroupe mes notes et les compétences acquises durant le module **Core SOC Solutions** de TryHackMe. J'y ai étudié et manipulé les trois technologies piliers d'un centre d'opérations de sécurité moderne : le **SIEM**, l'**EDR** et le **SOAR**.

---

## 📋 Présentation du Module
L'objectif de cette formation est de comprendre le rôle, le fonctionnement et l'intégration des solutions de sécurité indispensables à l'analyste SOC pour centraliser les logs, surveiller les endpoints et automatiser la réponse.

### 🚀 Outils & Concepts Maîtrisés

#### 1. Introduction to EDR (Endpoint Detection and Response)
* **Concepts :** Différence entre un antivirus traditionnel (EPP) et un EDR. Surveillance continue des comportements sur les hôtes.
* **Fonctionnalités :** Collecte de télémétrie en temps réel, isolation d'hôtes suspectés, et traque de menaces (Threat Hunting).

#### 2. Introduction to SIEM (Security Information and Event Management)
* **Concepts :** Centralisation, normalisation et corrélation des logs provenant de l'ensemble de l'infrastructure.
* **Rôle :** Permettre aux analystes d'avoir une visibilité à 360° et de générer des alertes basées sur des règles logiques.

#### 3. Splunk: The Basics
* **Pratique :** Utilisation du langage **SPL** (Splunk Processing Language) pour requêter les bases de données de logs.
* **Compétences :** Filtrage de données, recherche d'indicateurs de compromission (IoC) et création de tableaux de bord pour l'investigation.

#### 4. Elastic Stack: The Basics (ELK)
* **Pratique :** Navigation dans l'écosystème Elastic (Elasticsearch, Logstash, Kibana).
* **Compétences :** Utilisation de **KQL** (Kibana Query Language) et Lucene pour analyser et visualiser les données de sécurité.

#### 5. Introduction to SOAR (Security Orchestration, Automation, and Response)
* **Concepts :** Orchestration d'outils hétérogènes et automatisation des tâches répétitives via des **Playbooks** (ex: scan automatique d'une IP sur VirusTotal dès qu'une alerte SIEM se déclenche).
* **Bénéfice :** Réduction drastique du **MTTR** (Mean Time to Respond) et de la fatigue des alertes pour les analystes.

---

## 🧰 Stack Technique Opérationnelle
* **SIEM / Log Management :** Splunk, Elastic Stack (Kibana).
* **Langages de Requête :** SPL, KQL.
* **Concepts DefSec :** Télémétrie Endpoint, Pipelines d'automatisation (Playbooks).

---
*Formation complétée sur [TryHackMe](https://tryhackme.com/)*
