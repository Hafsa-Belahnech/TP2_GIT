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
<img width="1103" height="507" alt="image" src="https://github.com/user-attachments/assets/c954ad07-79b3-421a-8508-c5a878781f42" />
<img width="1919" height="863" alt="image" src="https://github.com/user-attachments/assets/0a84757e-63ce-4229-86ce-2fcf835988d5" />
<img width="1087" height="820" alt="image" src="https://github.com/user-attachments/assets/37f046c6-925e-4e8d-ba48-ca509ab6caf1" />
<img width="954" height="822" alt="image" src="https://github.com/user-attachments/assets/d0b5a481-2ff9-48e8-b644-a3eb19b370a0" />
<img width="959" height="1004" alt="image" src="https://github.com/user-attachments/assets/6d652d34-4fe4-4040-8e7d-c39cb8245cc3" />
<img width="956" height="193" alt="image" src="https://github.com/user-attachments/assets/277745ea-6b29-4e4d-8e75-dbc54a4fc9c9" />

---

**Editeur lors du "merge"**
<img width="1591" height="629" alt="image" src="https://github.com/user-attachments/assets/1d39fb05-90a3-43cc-837d-a574cd73850a" />
<img width="956" height="165" alt="image" src="https://github.com/user-attachments/assets/ac08c466-2d86-4d82-a0b8-eaa41a04062a" />
<img width="965" height="311" alt="image" src="https://github.com/user-attachments/assets/4f6adf00-a2a3-48c9-8b51-4dc5ee6397d5" />
<img width="1039" height="196" alt="image" src="https://github.com/user-attachments/assets/ec5bee21-eff5-4921-a780-dd3babf3faea" />
<img width="944" height="77" alt="image" src="https://github.com/user-attachments/assets/aad514e4-4904-4c1c-b71e-e308024f6b4a" />
<img width="960" height="250" alt="image" src="https://github.com/user-attachments/assets/ff7a0314-0e33-4d9e-9648-00c0535b9650" />    

--- 

**Visualisation du résultat dans Github**   
<img width="594" height="562" alt="image" src="https://github.com/user-attachments/assets/95e9f0b8-2bca-4dc3-a954-26f48d4eea95" />   
<img width="954" height="308" alt="image" src="https://github.com/user-attachments/assets/3aec06f2-0d1b-4b96-9a03-d8a0d65eecc3" />
<img width="941" height="248" alt="image" src="https://github.com/user-attachments/assets/045a404e-a0e8-4a87-af00-cfd8b77a5443" />    

---

**Deuxièmme TP**   
<img width="888" height="629" alt="image" src="https://github.com/user-attachments/assets/01008738-4d62-4f21-a107-0cdda7c06fcb" />   
<img width="888" height="275" alt="image" src="https://github.com/user-attachments/assets/a4e2362b-d01b-4d3c-adc0-26590ea2f8d8" />
<img width="800" height="165" alt="image" src="https://github.com/user-attachments/assets/d6519e79-0f41-42e9-a6d3-95f4013f4766" />
<img width="960" height="406" alt="Capture d&#39;écran 2026-03-16 123547" src="https://github.com/user-attachments/assets/1cb568c1-74be-4baa-9fec-a8ce27c1d019" />
<img width="956" height="175" alt="Capture d&#39;écran 2026-03-16 123626" src="https://github.com/user-attachments/assets/885db985-ae58-450f-a35d-084be4cc3528" />    

---

**Affichage**  
<img width="937" height="428" alt="image" src="https://github.com/user-attachments/assets/cb14e6f2-0b44-4116-b676-62eb8886e39e" />    
<img width="958" height="298" alt="Capture d&#39;écran 2026-03-29 182533" src="https://github.com/user-attachments/assets/aa81ac84-73e9-4d92-a9c9-d8badb63a585" />  

---

**Fusion des branches "merge"**
<img width="882" height="667" alt="image" src="https://github.com/user-attachments/assets/98cdeedd-2988-4ec5-91ee-66bf96149cfd" />
<img width="964" height="516" alt="image" src="https://github.com/user-attachments/assets/761bb349-9492-41a8-962f-12dd43305093" />   

--- 

**Copie d'un autre dêpot dans le même repository**
<img width="951" height="981" alt="Capture d&#39;écran 2026-03-29 191142" src="https://github.com/user-attachments/assets/533b2002-3201-46b3-bc2b-4ae00ae45009" />
<img width="846" height="88" alt="image" src="https://github.com/user-attachments/assets/05d7b225-b4e7-4b1f-b44d-7195a2005421" />



