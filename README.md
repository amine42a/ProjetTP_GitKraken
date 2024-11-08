# ProjetTP_GitKraken
# image :git.png 

# Historique des commits : Au centre, tu vois un tableau des modifications (commits) du projet, avec un schéma qui montre comment les branches et les fusions sont reliées.

# Panneau de gauche (branches) : Ce panneau te permet de voir et de naviguer entre les branches de ton projet. C'est aussi ici que tu peux créer de nouvelles branches ou fusionner (merge) des branches.

# Détails du commit : Quand tu sélectionnes un commit, le panneau de droite te montre les fichiers modifiés et les changements précis, pour voir ce qui a été fait.

# Zone de staging et commit : En bas, tu choisis les fichiers à enregistrer (stager) et tu ajoutes un message pour expliquer tes modifications avant de les valider (commit).

# Commandes pratiques : Des boutons simples comme push, pull, et fetch permettent d’envoyer ou de recevoir des modifications, sans taper de commandes.


image :git1.png 
Name : Nom du projet (ici, "ProjetTP_GitKraken").a
Initialize in : Choix du dossier où le dépôt sera créé.
Full path : Chemin complet du dépôt (affiché automatiquement en fonction du dossier choisi).
Default branch name : Nom de la branche principale (par défaut, "main").
.gitignore Template (optional) : Permet de sélectionner un modèle .gitignore pour ignorer certains fichiers.
License (optional) : Choix d’une licence pour le projet.
Initialize with LFS : Option pour utiliser Git LFS (Large File Storage), utile pour les fichiers volumineux.
# image :git1.png 
# Name : Nom du projet (ici, "ProjetTP_GitKraken").
# Initialize in : Choix du dossier où le dépôt sera créé.
# Full path : Chemin complet du dépôt (affiché automatiquement en fonction du dossier choisi).
# Default branch name : Nom de la branche principale (par défaut, "main").
# .gitignore Template (optional) : Permet de sélectionner un modèle .gitignore pour ignorer certains fichiers.
# License (optional) : Choix d’une licence pour le projet.
# Initialize with LFS : Option pour utiliser Git LFS (Large File Storage), utile pour les fichiers volumineux.

# image :git2.png 
# Isoler les changements : Les modifications restent séparées du code de production, donc elles n’affectent pas les autres développeurs ou le projet principal.
# Faciliter les tests et la revue : On peut tester et revoir la fonctionnalité sans impact sur main.
# Gérer les versions : Une fois la feature prête et validée, elle peut être fusionnée dans main, intégrant ainsi la nouveauté de manière contrôlée et sécurisée.


# Question 5
# Sauvegarder le travail : En cas de problème sur l'ordinateur local (panne, perte de données), les changements sont sauvegardés en ligne.
# Partager avec l’équipe : D'autres développeurs peuvent accéder à la branche, voir les changements, collaborer, et fournir des retours ou faire des modifications.
# Faciliter la revue de code et le suivi : Pousser les branches permet aux équipes de suivre l'avancement de chaque fonctionnalité ou correctif et d’effectuer des revues de code.

# question 6
# Dans GitKraken, changez de branche pour passer à feature.
# Ouvrez le fichier README.md depuis GitKraken en cliquant dessus dans le panneau de fichiers.
# Apportez une autre modification dans README.md (par exemple, ajoutez une nouvelle section ou modifiez du texte).
# Une fois les modifications faites, enregistrez le fichier.
# Dans GitKraken, effectuez un commit :
# Cliquez sur Stage all changes (stager toutes les modifications).
# Ajoutez un message de commit (par exemple, “Modification de README.md dans feature”) puis cliquez sur Commit.

# Question 8:
# Combinaison de branches : Lorsqu'on fusionne une branche (par ex., feature) dans une autre (par ex., main), un commit de merge est créé si les branches ont des changements distincts. Ce commit indique le point exact où les deux branches se rejoignent.
# Conservation de l'historique : Un commit de merge conserve l'historique des deux branches, montrant à quel moment elles ont divergé et comment elles ont été réunies.

# Créer une Pull Request (PR) dans GitKraken
# Poussez la branche avec vos modifications (par exemple, feature) sur GitHub.
# Dans GitKraken, cliquez sur "Start a Pull Request" dans le panneau de droite.
# Sélectionnez la branche cible (ex. main), ajoutez un titre et une description, puis cliquez sur Créer la PR.
# Créer une Pull Request sur GitHub
# Sur GitHub, allez dans l’onglet Pull Requests > New Pull Request.
# Sélectionnez la branche source (ex. feature) et la branche cible (ex. main).
# Ajoutez un titre et une description, puis cliquez sur Create Pull Request.
