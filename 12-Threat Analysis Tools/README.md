# 🕵️ Threat Analysis Tools (TryHackMe)

Ce dépôt documente ma progression et les compétences acquises dans le module **Threat Analysis Tools** de TryHackMe. J'y ai appris à exploiter le renseignement sur la menace (Cyber Threat Intelligence) pour détecter, enrichir et contextualiser les données d'incidents afin de renforcer les capacités de détection du SOC.

---

## 📋 Présentation du Module
L'objectif de cette formation est de maîtriser les outils et les flux d'analyse de la Threat Intel pour identifier l'empreinte des adversaires à partir de différents artefacts (fichiers, hashes, adresses IP et noms de domaine).

### 🚀 Salles & Compétences Pratiques

#### 1. Intro to Cyber Threat Intel (CTI)
* **Concepts :** Définition et types de Threat Intelligence (Stratégique, Tactique, Opérationnelle, Technique).
* **Frameworks :** Introduction aux standards d'échange et de partage de données de menaces comme **STIX** (Structured Threat Information Expression) et **TAXII** (Trusted Automated Exchange of Intelligence Information).

#### 2. File and Hash Threat Intel
* **Concepts :** Enrichissement et analyse d'artefacts basés sur des fichiers.
* **Pratique :** Utilisation des bases de connaissances mondiales pour identifier la réputation des fichiers via leurs empreintes cryptographiques (Hashes MD5, SHA1, SHA256) afin de l'associer à des groupes de menaces connus ou des campagnes de malwares.

#### 3. IP and Domain Threat Intel
* **Concepts :** Analyse et enrichissement d'indicateurs réseau à l'aide de sources de renseignement ouvertes (OSINT).
* **Pratique :** Évaluation de la réputation des adresses IP et des noms de domaine (recherche de Typosquatting, serveurs de Command & Control connus, ou historique de spam/malware) à l'aide d'outils de Threat Intel.

#### 4. Challenge Pratique : `Invite Only`
* **Scénario :** Investigation concrète basée sur l'extraction d'indices à partir d'un ensemble d'artefacts suspects signalés.
* **Objectifs atteints :** Extraction, corrélation et distillation de données brutes pour générer de la Threat Intelligence exploitable et actionnable par le SOC.

---

## 🛠️ Boîte à Outils & Concepts CTI
* **Standards :** STIX / TAXII, indicateurs techniques.
* **Enrichissement d'artefacts :** Réputation IP/Domaine, pivots de Hashes.
* **OSINT & Threat Intel Platforms :** Analyse de flux et exploitation de données de menaces ouvertes.

---
*Formation complétée sur [TryHackMe](https://tryhackme.com)*
