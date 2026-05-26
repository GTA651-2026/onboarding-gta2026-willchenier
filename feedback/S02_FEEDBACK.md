# Rétroaction automatisée -- S02 (Sélectionner des solutions IA : décision, opérations, productivité)

_Générée le 2026-05-26T14:38:02+00:00 -- Run `20260526T140803Z-ec457158`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Le dépôt contient une excellente trame d'exercice mais pas de contenu évaluatif : les tableaux et sections sont vierges et le brief décisionnel n'est pas rédigé. Remplissez la grille par contexte, ajoutez vérifications chiffrées, traces de travail et une synthèse exécutive claire.

### Observations par dimension

**Model quality**
- Observation : Le document ne présente pas de schéma ni d'évaluation remplie : les tableaux pour comparer Brex, Salesforce Einstein et Copilot sont vides et servent d'instructions.
- Piste d'amélioration : Renseigner le schéma décisionnel en remplissant chaque cellule du tableau par critères (rôle, impact, faisabilité, coût, risque) avec justification chiffrée et choix de pattern de modélisation si pertinent.

**Validation quality**
- Observation : Aucune requête, test ou vérification n'est fournie : le brief contient uniquement une grille et des consignes de rendu sans checks reproductibles.
- Piste d'amélioration : Ajouter des vérifications concrètes (ex. calculs d'impact, hypothèses chiffrées, tests simples) et documenter comment reproduire ces contrôles.

**Executive justification**
- Observation : La partie 'Recommandation' est laissée vide et le texte est une consigne d'exercice plutôt qu'un brief décisionnel adressé au CEO.
- Piste d'amélioration : Rédiger une synthèse décisionnelle de 150–300 mots par contexte, avec recommandation claire, justification business et implication pour la gouvernance.

**Process trace**
- Observation : Aucune trace de commits, note d'usage IA ou journal de décision n'est incluse dans le document fourni.
- Piste d'amélioration : Fournir un journal de commits (≥3 commits incrémentaux avec messages), et une note 'ai-usage.md' précisant outils IA, rôles et validation humaine.

**Reproducibility**
- Observation : Aucun artefact exécutable, script ou instruction de reproduction n'est joint — seules des instructions de rendu PDF sont présentes.
- Piste d'amélioration : Ajouter un README et scripts/data minimaux permettant à un collègue de reproduire la grille et les calculs (chemins relatifs, données d'exemple).

_Quelques points appellent une attention particulière lors de la prochaine itération : brief_incomplet._

## 3. Déclaration d'utilisation de l'IA

> La déclaration mentionne l'outil et décrit brièvement l'usage et la vérification humaine, mais elle manque de détails essentiels. Il faut préciser la version/modèle de l'outil et documenter les limites ou erreurs observées ainsi que la méthode précise de validation humaine.

**Sujets bien couverts dans votre déclaration :**

- outils utilisés (nom + version/modèle)
- à quelle étape l'IA a été utilisée
- comment la sortie a été validée par l'humain

**Sujets à ajouter ou expliciter pour la prochaine itération :**

- limites ou erreurs observées

## 4. Pistes d'action pour la prochaine itération

- Réviser le brief en tenant compte des observations par dimension de la section 2.
- Compléter `ai-usage.md` en y ajoutant : limites ou erreurs observées.

---

## 5. Traçabilité

- **Run ID :** `20260526T140803Z-ec457158`
- **Devoir :** `S02`
- **Étudiant·e :** `willchenier`
- **Commit analysé :** `496c759`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260526T140803Z-ec457158/willchenier/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
