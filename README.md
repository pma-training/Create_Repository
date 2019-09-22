# How to Create a Repository
How to make a new repository using GitHub (_Français ci-dessous_)

_Video:_ [How to Create a Repository](https://www.youtube.com/watch?v=tOmto9-gOsc&list=PLaCCIQf3NY979c70cnegKx8Cmo3Wltkia&index=6&t=0s)

### Summary 
This video goes over the steps required to create a new repository in GitHub, and how to protect branches in repositories from being deleted by members. 

#### By the end of this video, you should be able to:
- Create a new repository
- Set the owner of a repository
- Name a new repository
- Give a description to a new repository
- Make a repository private (if possible)
- Initialize the repository
- Add a branch protection rule to a repository


### Definition of a repository:
A project folder that contains all project files, including documentation, and stores each file’s revision history. A repository can have multiple collaborators and be public or private.

### How Tos
#### How to Create a Repository on [GitHub](https://www.github.com):
1. Click on the “+” symbol on the top right corner of the page, and click on “New Repository”
2. Create a New Repository Page
   - Owner: If the repository is for personal use, the owner should be your personal account. If the repository is related to PMA, the owner should be a PMA organization
   - Name: Something related to the files in the repository
   - Description: A description of the files in the repository
   - Public vs. Private: PMA repositories that could potentially contain personally identifiable information should be private. Otherwise, whether a repository is public or private is up to the user’s discretion
     - If the repository is in a user account, making it private will restrict the number of potential collaborators
   - README: Initialize repositories with a README so that it is cloneable to GitKraken
3. Click on “Create Repository”

#### How to Protect a Repository on [GitHub](https://www.github.com):
1. Open the repository on [GitHub](https://www.github.com)
2. Navigate to the repository settings
3. Click on “Branches” on the left panel
4. Scroll to “Branch protection rules”
   - Select “add rule”
   - Name the rule “no delete”
   - Click “Create”
   - Enter your password 


### Glossary of terms:
| Term | Definition |
| ---- | ---------- |
| Branch | A branch is a parallel version of a repository that allows you to work freely without disrupting the master version of a file. PMA uses branches to update .do file content and prepare .do files for round specific data collection |
| Clone | A clone is a copy of a repository that is located on your computer instead of on a server, it allows you to be able to use a Git editor, such as GitKraken, to track changes without needing to be online. All changes are then synced between the repository on the server and the cloned repository. All PMA staff should clone repositories that contain .do files that they use onto their computer using GitKraken |
| Commit | A commit is a way to save a change to a file that also stores information on what changes were made, when and by who. PMA uses commits to systematically document changes to .do files |
| Organization | A workspace where teams can collaborate across many projects at once. PMA uses organizations to organize .do files by purpose and country. |
| Private Repository | A repository that can only be viewed or contributed to by their creator and specified collaborators. All PMA repositories are private so no external person can access personally identifying information stored in .do files. |
| Repository | Contains all of the project files and documentation and stores each file’s revision history. Can have multiple collaborators. PMA keeps its .do files in repositories that are organized by survey type and action |



_________________________________________________________________



# Comment créer un Repository
Comment créer un nouveau repository sur GitHub

_Vidéo:_ [Comment créer un Repository](https://www.youtube.com/watch?v=0bO7yPmjrkQ&list=PLaCCIQf3NY97bYG9q4ha8mEUlM8W7kJpE&index=6&t=0s)

### Résumé  
Cette vidéo présente les étapes requises pour créer un nouveau repository sur GitHub, et pour empêcher que les branches des repositories ne soient effacées par les membres. 

#### A la fin de la vidéo, vous devriez être en mesure de :
- Créer un nouveau repository
- Choisir le propriétaire du repository
- Nommer un nouveau repository
- Donner une description à un nouveau repository
- Rendre un repository privé (si possible)
- Initialiser le repository
- Ajouter une règle de protection de branch à un repository 


### Définition d'un repository :
Dossier d’un projet contenant tous les fichiers et documents de ce dernier, et stockant l’historique de modifications de chaque fichier. Un repository peut avoir plusieurs collaborateurs et peut être public ou privé. 

### Comment Faire
#### Comment créer un repository su [GitHub](https://www.github.com) :
1. Cliquez sur le symbole “+” en haut à droite de la page, puis cliquez sur “New Repository”
2. Créez une nouvelle page Repository 
   - « Owner » (Propriétaire) : Si le repository est à usage personnel, le propriétaire devrait être votre compte personnel. Si le repository est lié à PMA, le propriétaire devrait être une Organization PMA. 
   - « Name » (Nom) : Doit être en lien avec les fichiers du repository
   - « Description » : Description des fichiers du repository
   - Public ou Privé ? : Les repositories de PMA qui pourraient potentiellement contenir des données personnelles devraient être privés. Dans le cas contraire, la décision de rendre un repository public ou privé revient à l’utilisateur/trice. 
     - Si le repository se trouve dans un compte d’utilisateur/trice, le rendre privé restreindra le nombre de collaborateurs possibles. 
   - README : Commencer les repositories avec un README pour qu’ils soient cloneables sur GitKraken
3. Cliquez sur “Create Repository” (Créer un repository)

#### Comment protéger un repository sur [GitHub](https://www.github.com)
1. Ouvrez le repository sur www.github.com
2. Allez dans les paramètres du repository 
3. Cliquez sur “Branches” sur le panel de gauche
4. Descendez jusqu’à : “Branch protection rules” (Règles de protection de la branch)
   - Sélectionnez “add rule” (ajouter une règle)
   - Nommez la règle : “no delete” (ne pas effacer)
   - Cliquez “Create” (Créer)
   - Saisissez votre mot de passe


### Glossaire :
| Terme | Definition |
| ---- | ---------- |
| Branch | Version parallèle d’un repository permettant de travailler librement sans perturber la version master d’un fichier. PMA utilise des branches pour mettre à jour le contenu des dofiles et les préparer pour la collecte de données d’une vague d’enquête spécifique. |
| Clone | Copie d’un repository situé sur un ordinateur plutôt que sur un serveur, permettant d’utiliser un éditeur Git, comme GitKraken, pour suivre les modifications sans avoir à être en ligne. Toutes les modifications sont ensuite synchronisées entre le repository sur le serveur et le repository cloné. Tous les collaborateurs de PMA devraient cloner les repositories contenant les .do files qu’ils utilisent sur leurs ordinateurs à l’aide de GitKraken.| 
| Commit | Manière de sauvegarder une modification d’un fichier en stockant aussi des informations sur les changements qui ont été faits, quand et par qui. PMA utilise des commits pour documenter systématiquement les modifications des .do files |
| Organization | Espace de travail où les équipes peuvent collaborer sur différents projets en même temps. PMA utilise des organizations pour organiser ses .do files selon leur objectif et par pays |
| Private Repository | Un repository qui ne pouvant être visionné que par son créateur ou ses collaborateurs, ou auquel seuls son créateur et des collaborateurs spécifiés peuvent contribuer. Tous les repositories de PMA sont privés pour qu’aucune personne externe ne puisse avoir accès aux données personnelles stockées dans les .do files |
| Repository | Contient tous les fichiers et la documentation du projet, et stocke l’historique de révision de chaque fichier. Peut avoir plusieurs collaborateurs. PMA garde ses .do files dans des repositories organisés par type d’enquête et d’action |
