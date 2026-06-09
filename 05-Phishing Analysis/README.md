# ✉️ Phishing Analysis (TryHackMe)

Ce dépôt documente ma progression et les compétences acquises dans le module **Phishing Analysis** de TryHackMe. J'y ai appris à analyser, décortiquer et bloquer les attaques par ingénierie sociale basées sur l'email, de l'examen des en-têtes bruts à la traque de campagnes malveillantes complexes.

---

## 📋 Présentation du Module
L'objectif de cette formation est de maîtriser les outils et les méthodologies d'investigation numérique nécessaires pour analyser la structure d'un email suspect et neutraliser les menaces (liens malveillants, pièces jointes infectées).

### 🚀 Salles & Compétences Pratiques

#### 1. Phishing Analysis Fundamentals
* **Concepts :** Anatomie complète d'un email. Compréhension fine des protocoles de messagerie (SMTP).
* **Analyse technique :** Décryptage des en-têtes (Headers) pour identifier l'origine réelle du message :
    * **MTA (Mail Transfer Agent) :** Analyse du parcours réseau du mail.
    * **Authentification :** Vérification des enregistrements **SPF**, **DKIM** et **DMARC** pour détecter l'usurpation d'identité (Spoofing).

#### 2. Phishing Emails in Action
* **Concepts :** Identification des indicateurs comportementaux et techniques de phishing (Urgence, fausses pages de connexion, typosquatting de domaines).
* **Analyse :** Différenciation entre le phishing de masse, le *Spear-Phishing* (ciblé) et le *Whaling* (ciblant les cadres dirigeants).

#### 3. Phishing Analysis Tools
* **Pratique :** Utilisation des outils phares de l'industrie pour analyser les artefacts en toute sécurité (bac à sable / sandbox) :
    * **Analyse de Headers :** MessageHeader (Google), MXToolbox.
    * **Analyse de Réputation & Liens :** VirusTotal, URLScan.io, Talos Intelligence.
    * **Extraction d'artefacts :** Récupération sécurisée de hashes de pièces jointes suspectes.

#### 4. Phishing Prevention
* **Concepts :** Mécanismes de défense périmétrique (Passerelles de sécurité de messagerie - SEG).
* **Techniques :** Configuration de règles de transport, blocage de domaines malveillants, et mise en place de politiques de quarantaine.

#### 5. Challenges Pratiques (`The Greenholt Phish` & `Snapped Phish-ing Line`)
* **The Greenholt Phish :** Analyse de bout en bout d'un email malveillant réel ciblant une infrastructure d'entreprise pour en extraire les IoCs.
* **Snapped Phish-ing Line :** Investigation avancée sur des emails et des URL malveillants, permettant de remonter la piste et de démanteler une campagne de phishing à grande échelle.

---

## 🛠️ Boîte à Outils Maîtrisée
* **Analyse d'en-têtes :** Analyse SMTP, vérification de la chaîne de relais (Received headers).
* **Défense Email :** SPF, DKIM, DMARC, DNS record analysis.
* **OSINT & Threat Intelligence :** VirusTotal, URLscan.io, CyberChef.

---
*Formation complétée sur [TryHackMe](https://tryhackme.com/)*
