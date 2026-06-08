# 🗺️ Cyber Defence Frameworks (TryHackMe)

Ce dépôt documente ma progression et les compétences acquises dans le module **Cyber Defence Frameworks** de TryHackMe. J'y ai appris à modéliser le comportement des attaquants et à utiliser les référentiels de l'industrie pour structurer la détection, le triage et la réponse aux incidents.

---

## 📋 Présentation du Module
L'objectif de cette formation est de maîtriser les frameworks défensifs majeurs afin d'anticiper les actions adverses et d'élever le coût d'une attaque pour les cybercriminels.

### 🚀 Modèles & Frameworks Étudiés

#### 1. Pyramid of Pain
* **Concepts :** Classification des indicateurs de compromission (IoC) selon la difficulté (la "douleur") que leur modification impose à un attaquant.
* **Niveaux :** Des éléments faciles à changer (Hashes de fichiers, adresses IP, noms de domaine) jusqu'aux plus complexes à modifier (TTPs - Tactiques, Techniques et Procédures).
* **Application :** Se concentrer sur la détection des comportements (TTPs) plutôt que sur de simples indicateurs statiques.

#### 2. Cyber Kill Chain (Lockheed Martin)
* **Concepts :** Modélisation d'une cyberattaque cyber en 7 phases linéaires (Reconnaissance, Weaponization, Delivery, Exploitation, Installation, Command & Control, Actions on Objectives).
* **Objectif :** Identifier et briser la chaîne d'attaque le plus tôt possible pour stopper l'intrusion.

#### 3. Unified Kill Chain
* **Concepts :** Une version étendue et plus moderne de la Kill Chain classique (combinant Lockheed Martin et MITRE), regroupant 18 phases tactiques adaptées aux infrastructures modernes et aux menaces persistantes (APT).

#### 4. MITRE ATT&CK
* **Concepts :** Base de connaissances mondiale documentant les tactiques et techniques réelles des cyberattaquants.
* **Pratique :** Utilisation de la matrice pour cartographier la couverture des détections du SOC et corréler les alertes avec des comportements d'attaquants connus (Threat Intelligence).

#### 5. Salles Pratiques & Challenges (`Summit` & `Eviction`)
* **Summit :** Simulation de Threat Hunting consistant à traquer un adversaire et à bloquer ses actions en remontant les niveaux de la *Pyramid of Pain*.
* **Eviction :** Scénario pratique de réponse à incident visant à identifier, contenir et éjecter complètement une menace persistante du réseau.

---

## 🛡️ Compétences Méthodologiques Validées
* **Modélisation de la Menace :** Capacité à contextualiser une alerte au sein d'une phase précise d'une attaque.
* **Threat Hunting :** Recherche proactive basée sur les TTPs (Tactiques, Techniques et Procédures) des attaquants.
* **Durcissement de la Détection :** Alignement des règles du SIEM avec le framework MITRE ATT&CK.

---
*Formation complétée sur [TryHackMe](https://tryhackme.com/)*
