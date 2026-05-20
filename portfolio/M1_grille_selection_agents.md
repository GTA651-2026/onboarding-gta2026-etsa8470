# M1 — Grille de sélection et évaluation de solutions IA

> Comparez **Brex** (CFO virtuel), **Salesforce Einstein** (aide à la décision commerciale)
> et **Microsoft Copilot 365** (productivité) sur 5 critères, pour **deux contextes** :
> une PME de 50 employés et une grande entreprise de 500+ employés.
> Concluez par une **recommandation argumentée par contexte**.
>
> Exportez en PDF et déposez `M1_grille_selection_agents.pdf` dans ce dossier.
> Mettez à jour `ai-usage.md` à la racine du dépôt (obligatoire, même si « Aucun »).

---

## Contexte 1 — PME de 50 employés

_(Décrivez brièvement la PME : secteur, maturité numérique, budget IA approximatif, équipe IT.)_

| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré** _(nommez le spécialiste que l'agent remplace/augmente)_ | Directeur financier virtuel (CFO) | Analyste commercial et prévisionniste des ventes | Assistant de productivité et de rédaction |
| **2. Impact d'affaires** _(1-5 + justification en 1 phrase)_ | 4/5 — Automatise les dépenses et améliore la visibilité financière | 5/5 — Optimise les ventes et la priorisation des prospects | 4/5 — Réduit le temps de rédaction, emails et réunions |
| **3. Faisabilité PME** _(1-5 + données, compétences, intégration)_ | 2/5 — Principalement utile si déjà intégré à l’écosystème Brex | 2/5 — Dépend de Salesforce CRM et de données propres | 5/5 — Intégration native à Microsoft 365, adoption facile |
| **4. Coût estimé** _(ordre de grandeur annuel + TCO si pertinent)_ | 10 000 à 25 000 CAD/an | 20 000 à 60 000 CAD/an | ~30 USD/utilisateur/mois (~25 000 CAD/an pour 50 employés) |
| **5. Risque principal** _(et mitigation concrète)_ | Dépendance à la plateforme — mitigation : test pilote limité | Mauvaise qualité des données — mitigation : gouvernance CRM | Fuite d’information — mitigation : contrôle des accès + conformité Loi 25 |

### Recommandation pour la PME

_(2-3 phrases : quelle solution déployer en premier, et pourquoi ce choix bat les deux autres dans CE contexte.)_

Microsoft Copilot 365 est recommandé en premier. Son déploiement est rapide, son adoption
est simple et les gains de productivité sont immédiats pour l'ensemble des employés.

---

## Contexte 2 — Grande entreprise de 500+ employés

_(Décrivez brièvement : secteur, systèmes existants — ERP/CRM, contraintes de gouvernance, sponsor.)_


| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré** | CFO virtuel pour la gestion des dépenses | Analyste stratégique des ventes | Assistant de productivité organisationnelle |
| **2. Impact d'affaires** _(1-5 + justification)_ | 4/5 — Renforce le contrôle financier et la visibilité des dépenses | 5/5 — Améliore fortement les prévisions et le taux de conversion | 4/5 — Gains majeurs de productivité à l’échelle de l’organisation |
| **3. Faisabilité grande entreprise** _(1-5 + intégration systèmes, gouvernance)_ | 3/5 — Intégration possible avec ERP mais portée fonctionnelle limitée | 5/5 — Très adapté à un environnement Salesforce mature et bien gouverné | 5/5 — Déploiement standardisé avec forte intégration Microsoft 365 |
| **4. Coût estimé** _(licences + intégration + formation)_ | 50 000 à 150 000 CAD/an | 150 000 à 500 000 CAD/an (incluant intégration et formation) | ~250 000 CAD/an pour 500 utilisateurs |
| **5. Risque principal** _(et mitigation)_ | Intégration comptable complexe — mitigation : déploiement progressif avec ERP | Biais algorithmiques — mitigation : audits réguliers des modèles | Surpartage de données — mitigation : gouvernance Microsoft Purview |

### Recommandation pour la grande entreprise

_(2-3 phrases : quelle solution, et pourquoi le choix diffère — ou ne diffère pas — de la PME.)_

Salesforce Einstein est recommandé, car il génère un impact direct sur les revenus et
exploite pleinement les données CRM déjà disponibles.

---

## Synthèse — ce que la grille révèle

_(3-5 phrases : quel critère a fait basculer la décision ? Qu'est-ce que ça enseigne sur la sélection de solutions IA en général ? Préparation directe à l'Examen-cas 1.)_
Le critère déterminant est la faisabilité organisationnelle. Une solution très puissante n'est
rentable que si les données, les compétences et les systèmes sont prêts. Pour une PME, la
simplicité d'implantation prime; pour une grande entreprise, l'impact stratégique justifie des
investissements plus importants.

---

## Liste de contrôle de remise

- [ ] Les 3 agents sont comparés sur les mêmes 5 critères dans les deux contextes
- [ ] Le rôle spécialisé orchestré est nommé précisément pour chaque agent
- [ ] Les scores sont justifiés (pas juste des chiffres)
- [ ] La recommandation diffère — ou est explicitement justifiée comme identique — entre PME et grande entreprise
- [ ] Le contexte d'une organisation québécoise est pris en compte (Loi 25, marché local, talent)
- [ ] `ai-usage.md` mis à jour à la racine du dépôt

> **Crédit :** Jalon M1 — pass/fail (1,5 % du cours). Préparation directe à l'**Examen-cas 1** (S05, 25 %).
