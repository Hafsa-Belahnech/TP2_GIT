#  Gestion de Versions et Workflow Applicatif


Ce dépôt rassemble les exercices pratiques centrés sur la maîtrise du cycle de vie des fichiers, la gestion des branches et l'atomicité des commits.

## Objectifs 

L'objectif principal est de manipuler les **trois zones de Git** pour comprendre comment le code transite du disque dur vers l'historique versionné.

### 1. Architecture et Workflow (Projet Sandwich)
Mise en pratique du flux de travail standard à travers la création et la modification de fichiers (ex: `burger.txt`) :
*   **Working Directory** : Création de fichiers en mode *Untracked*.
*   **Staging Area (Index)** : Sélection précise des modifications via `git add`.
*   **Repository** : Archivage définitif avec `git commit`.
*   **Inspection** : Utilisation de `git status`, `git diff` et `git diff --cached` pour contrôler chaque état.

### 2. Atomicité des Commits (Exemple le Script Test.java et le dossier sandwich)
Application de la règle d'or **"1 modification = 1 commit"** :
*   Décomposition d'un script en plusieurs étapes logiques.
*   Enregistrement de chaque évolution fonctionnelle séparément pour un historique granulaire.
*   Validation et exécution.

### 3. Gestion Avancée des Branches et Fusion
Expérimentation sur la structure de l'historique et la collaboration :
*   **Branches** : Création de branches parallèles (`fr-main`, `master`) pour isoler les développements.
*   **Navigation** : Utilisation de `git checkout` pour voyager dans le temps (mode *Detached HEAD*).
*   **Fusion** : Réalisation de `git merge` pour unifier les travaux et création de *merge commits*.

---

## Commandes Clés Utilisées


| Commande | Action |
| :--- | :--- |
| `git status` | Vérifier l'état des fichiers (Tracked/Untracked) |
| `git log --oneline --graph` | Visualiser l'historique et la structure des branches |
| `git reset <file>` | Désindexer un fichier (retour de l'Index au Working Dir) |
| `git checkout -- <file>` | Annuler les modifications locales |
| `git push / git pull` | Synchronisation avec le dépôt distant GitHub |

---
Captures d'écran 

**Préparation de l'environement de travail avec les commandes**
<img width="1206" height="164" alt="image" src="https://github.com/user-attachments/assets/fd6d70d0-e739-482d-9256-bac275eeafdc" />
<img width="1367" height="193" alt="image" src="https://github.com/user-attachments/assets/29c3cfba-c9d0-4bdc-8f0f-bdde872e2dca" />

---
**Création du dossier**
<img width="1258" height="179" alt="image" src="https://github.com/user-attachments/assets/2cadbcba-914e-4a1e-b4af-5b8e7220f706" />
<img width="977" height="39" alt="image" src="https://github.com/user-attachments/assets/d76a31b7-8e62-468d-a261-ef6cf3a3014f" />

<img width="957" height="543" alt="image" src="https://github.com/user-attachments/assets/db93c608-f512-4bf0-b131-b2cd2fc25c60" />
<img width="847" height="184" alt="image" src="https://github.com/user-attachments/assets/219a2b21-cd61-4d8c-8a8c-914e83830fb7" />
<img width="1131" height="296" alt="image" src="https://github.com/user-attachments/assets/07429826-a398-4026-be66-fee78f1fcfbf" />
<img width="1129" height="287" alt="image" src="https://github.com/user-attachments/assets/dcd8a80a-5c56-412d-90a3-b2a2661a53b6" />
<img width="1126" height="486" alt="image" src="https://github.com/user-attachments/assets/064af713-2271-4846-8ab3-e5bce0251fb4" />
<img width="1126" height="578" alt="image" src="https://github.com/user-attachments/assets/462fe9d4-961c-496b-8944-67fdd9088863" />




<img width="609" height="132" alt="image" src="https://github.com/user-attachments/assets/6f03dbc2-cd20-4db8-a432-bd80e088e237" />









<img width="937" height="572" alt="image" src="https://github.com/user-attachments/assets/6e94a328-7b80-4a7f-9d05-889ce4399f1c" />
<img width="882" height="820" alt="image" src="https://github.com/user-attachments/assets/d5e257b8-7d5d-417f-8d3c-1551e6fbb94a" />
<img width="964" height="516" alt="image" src="https://github.com/user-attachments/assets/cd360c19-129b-44c8-9219-f8d215f9acb3" />


Copie d'un autre travail en le mettant dans ce même dépôt
<img width="1565" height="899" alt="image" src="https://github.com/user-attachments/assets/4611f5ed-5cc2-4204-ad5c-02e34a91c1cf" />

