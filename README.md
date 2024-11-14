# ProjetTP_GitKraken

# Question 2
Ouvrir GitKraken : Lancez l'application GitKraken sur votre ordinateur.

Nouvel espace de travail : Depuis la page d'accueil, cliquez sur l'icône ‘+’ ou sur File > Init Repo pour créer un nouveau dépôt.

Choisir l’emplacement : Une fois l’option de création de dépôt sélectionnée, une fenêtre s'ouvre pour spécifier l’emplacement où le dépôt sera créé. Vous pouvez choisir un dossier local ou un emplacement spécifique sur votre disque.

Nommer le dépôt : ProjetTP_GitKraken   Dans le champ dédié, entrez un nom pour le dépôt. Cela va créer un dossier avec ce nom, qui contiendra tous les fichiers Git associés.
# Question 3
Les branches permettent de :

    Travailler en parallèle : On peut développer une nouvelle fonctionnalité sans modifier la version principale du code.
    Protéger le code principal : Les branches isolent le code en cours de modification ou de test pour éviter les erreurs dans la version stable.
    Collaborer facilement : Plusieurs personnes peuvent travailler sur différentes fonctionnalités en même temps, sans se gêner.

Créer une branche feature à partir de main avec GitKraken

    Ouvrez GitKraken et assurez-vous d’être sur la branche main.
    Faire Clique droit sur create New Branch 
    Entrez le nom de la nouvelle branche, par exemple feature.
    Validez en cliquant sur Create Branch.


# Question 4
    Assurez-vous d’être sur la branche feature : Dans GitKraken, vérifiez que la branche feature est bien sélectionnée en haut de l’interface.
    Modifier le fichier README.md : Ouvrez le fichier README.md dans votre éditeur de texte préféré, ajoutez une ligne de votre choix, puis enregistrez les modifications.
    Vérifier les changements : Retournez dans GitKraken. Vous verrez que le fichier README.md est listé dans les modifications non commit (non validées).
    Sélectionner les changements : Cliquez sur le fichier README.md dans la liste des modifications pour l’ajouter au commit.
Faire un commit :

    Dans le panneau de droite, entrez un message de commit descriptif, comme “Ajout d’une ligne dans README.md”.
    Cliquez sur Commit changes pour valider les modifications sur la branche feature. 
    
# Question 5
Pousser (ou push) une branche vers le dépôt distant est essentiel car cela permet de :

    Partager le travail avec les autres : Les autres membres de l’équipe peuvent accéder aux modifications, suivre le développement et travailler en parallèle.
    Sauvegarder les modifications : Les changements sont sauvegardés de manière centralisée, ce qui protège contre la perte de données locales.
    Préparer l’intégration : Le code peut être révisé et intégré plus facilement, notamment grâce aux pull requests.

Pousser la branche feature vers le dépôt distant avec GitKraken

    Vérifiez que vous êtes sur la branche feature : Assurez-vous que feature est sélectionnée en haut de l’interface GitKraken.

    Pousser la branche :
        Cliquez sur le bouton Push en haut de la fenêtre.
        GitKraken vous demandera si vous souhaitez pousser la branche feature vers le dépôt distant. Confirmez en cliquant sur Push.

    Vérifiez la réussite de l’opération : GitKraken vous affichera un message de confirmation si le push a bien été effectué.    
