# L1 — Fiche d'opportunite agentique

> Choisissez UN des trois cas (Klarna, GitHub Copilot Enterprise, Morgan Stanley).
> Remplissez les 6 champs ci-dessous en langage executif (pas technique).
> Exportez en PDF et deposez `L1_reflexion_role_specialise.pdf` dans ce dossier.

---

## Cas choisi

_(Klarna / GitHub Copilot Enterprise / Morgan Stanley)_

GitHub Copilot Enterprise est le cas choisi

## 1. Probleme d'affaires resolu

_(En 2-3 phrases : quel probleme concret l'organisation cherchait-elle a resoudre ?)_
Les équipes de développement logiciel font face à une demande croissante de livraison de fonctionnalités dans des délais toujours plus courts, alors que le volume de code à maintenir et les révisions de code mobilisent une part disproportionnée du temps des développeurs. GitHub cherchait à absorber cette pression sans augmenter proportionnellement les effectifs.

## 2. Fonction d'affaires ciblee

_(Service client, developpement logiciel, analyse financiere, etc.)_

Développement logiciel, plus précisément les activités de production, de revue et de documentation de code au sein des équipes d’ingénierie produit.

## 3. Role specialise que l'agent orchestre

_(Nommez-le precisement : agent de service client, agent developpeur, agent analyste, etc.)_
Agent développeur : un assistant IA spécialisé qui complète, suggère et explique du code en temps réel directement dans l’environnement de travail du développeur (IDE). Il agit comme un copilote technique capable d’analyser le contexte du projet, de proposer des blocs de code complets et de répondre aux questions techniques sans quitter l’interface de développement.

## 4. Valeur creee — quantifiee avec donnees publiques

_(Chiffres concrets issus des sources du cours. Ex. : 700 agents equivalents, 55 % plus rapide, etc.)_

Selon les données publiées par GitHub et Microsoft (2023-2024), les développeurs complètent leurs tâches jusqu’à 55 % plus rapidement avec Copilot activé. Dans les entreprises adoptant Copilot Enterprise, 88 % des utilisateurs déclarent être plus productifs. Le taux d’acceptation des suggestions de code atteint 30 % en moyenne, ce qui représente environ un tiers du code produit généré par l’IA. Chez Accenture, le déploiement a permis à 50 000 développeurs d’accélérer leur cadence de livraison de manière mesurable, réduisant le temps consacré aux tâches répétitives de bas niveau.

## 5. Risque principal et mitigation concrete

_(Quel est le risque le plus important ? Quelle mesure concrete le reduit ?)_

Risque principal : intégration de code généré non conforme aux standards de sécurité ou contenant des vulnérabilités silencieuses, avec un risque de fuite de propriété intellectuelle si le code propriétaire est transmis aux modèles.
Mitigation concrète : activer les filtres de confidentialité du code (code privacy settings) pour bloquer la transmission de code interne vers les modèles publics ; imposer des revues de code systématiques sur toutes les suggestions acceptées ; déployer des outils d’analyse de sécurité statique (SAST) en aval dans le pipeline CI/CD pour détecter les vulnérabilités avant la mise en production.


## 6. Condition de succes pour votre organisation

_(Qu'est-ce qui doit etre en place pour que ce deploiement agentique fonctionne ?)_

Trois conditions sont non négociables :
(1) une gouvernance claire sur les données — définir quels référentiels de code peuvent être exposés au modèle et lesquels doivent rester isolés ;
(2) une culture de revue maintenue — les développeurs doivent traiter les suggestions comme des propositions à valider, non comme des livrables finis, ce qui nécessite une formation explicite ;
(3) une intégration dans les outils existants — Copilot Enterprise doit s’insérer dans les IDE, les pipelines CI/CD et les plateformes de revue de code déjà en place pour éviter toute friction d’adoption.


---

> **Rappel :** mettez a jour `ai-usage.md` a la racine du depot, meme si vous n'avez utilise aucun outil IA.
