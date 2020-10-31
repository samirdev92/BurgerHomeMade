Git challenge 

1 - Préparation de l’environnement

👉 Créez un nouveau projet nommé « gitbegin » dans le répertoire « lacapsule ».

👉 Initialisez Git dans le répertoire  « gitbegin ».



👉 Créez un fichier index.html et style.css.



👉 Dans votre IDE, créez un squelette du fichier HTML.

👉 Mettez en place la liaison entre le fichier HTML et CSS.

👉 Ecrivez la phrase « Burger Home Made » et centrez-la au milieu de l’écran via le positionnement Flexbox.

👉 Regardez le rendu sur le navigateur.

👉 Si tout est OK, il faut réaliser le 1er commit en mettant en commentaire « project init ».



👉 Le commit sera visible dans le journal de bord de Git via la commande git status.

2 - Modifier un projet avec les branches

👉 Créez une branche nommée « backgroundColor ».



👉 Basculez sur cette branche et apportez les modifications nécessaires pour mettre une couleur de fond.




👉 Regardez le rendu sur le navigateur.

👉 Si tout est OK, réalisez un commit avec le message suivant : « add background color ».




A ce moment précis, deux versions du projet sont disponibles:

Version 1: la page sans couleur de fond.
Version 2: la page avec couleur de fond.

Où sont-elles ? Sur chaque branche du projet:

La version 1 se trouve sur la branche d’origine appelée master.
La version 2 sur la branche nouvellement créée « backgroundColor ».

À tout moment, on peut basculer d’une branche à une autre.


👉 Utilisez la commande pour revenir sur la branche master.



👉 Regardez le rendu sur un navigateur.

👉 Retournez de nouveau sur la branche « backgroundColor ».



👉 Regardez le rendu sur un navigateur.


L’avantage des branches?

Rendre les modifications indépendantes les unes des autres. Si, finalement, la modification de la couleur de fond ne convient plus? Pas de soucis. Il suffit de supprimer la branche « backgroundColor » et de revenir sur la branche master pour retrouver le projet d’origine.


👉 Fusionnez les branches.
👉 Si le développement d’une branche est OK, il faudra alors rapatrier son contenu sur la branche master (branche qui correspond au projet définitif).

Revenez sur la branche master.



👉 Utilisez les commandes permettant de récupérer le contenu de la branche « background color ».



👉 Supprimez la branche « backgroundColor».



👉 Regardez le rendu sur un navigateur.

👉 Consultez également l’historique des commits avec la commande git status. Les 2 commits sont maintenant visibles sur la branche principale.

 Dépôt distant avec Github

👉 Créez un compte sur Github.

👉 Créez un dépôt distant nommé « burger project ».

👉 Déposez le projet sur le dépôt distant.



👉 Si l’opération s’est bien déroulée, le code du projet devrait être visible sur la page du dépôt Github (rafraîchissez la page pour voir le contenu à jour).