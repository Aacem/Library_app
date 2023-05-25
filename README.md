# Library_app

Installation :
-dans la racine du dossier du projet qui est la partie 'backend' de l'application installer node avec la commande 'npm i node' 

-Maintenant, dans le dossier client qui est la partie 'frontend' du projet, installez tous les paquets et dépendances nécessaires avec la commande 'npm install'. 

Éléments nécessaires au fonctionnement de l'application :
-Avoir le wifi ou internet (car la base de données est un cluster mongodb).
-Il est recommandé d'avoir mongodbcompass pour pouvoir savoir exactement ce qui se passe dans la base de données (les documents keys.js et server.js à la racine du projet contiennent ce qui est nécessaire pour se connecter à la base de données mongodb).


Démarrage :

-utiliser la commande npm start à la racine du dossier du projet pour connecter le projet à la base de données (le wifi ou internet doit être disponible avant de faire cela).

-Utiliser à nouveau la commande npm start dans le dossier client pour pouvoir démarrer l'application sur le port 3000 (si vous voulez avoir plus d'un client qui fonctionne en même temps, il suffit d'ouvrir un autre terminal dans le même dossier client et de répéter la même chose).

Comptes :

Admin - 
         ID de l'employé : 11
         mot de passe : aacemchaer2004

Clarification si vous vérifiez le code : 

Roll_no fait référence au nom d'utilisateur et à l'identifiant de l'employé.

Problèmes connus :

-Parfois, lorsque vous appuyez sur un bouton, il ne disparaît pas tant que vous n'avez pas rafraîchi la page et si vous appuyez sur le bouton plus d'une fois, la fonction de ce bouton est exécutée plus d'une fois (ce problème ne se produit pas toujours).

-Si vous appuyez rapidement et successivement sur les boutons, les entrées risquent de ne pas être prises en compte. 

Annotations :

-Dans la section de gestion des réservations de livres, si l'administrateur appuie sur le bouton "clear", le livre sera renvoyé sans que l'utilisateur doive le renvoyer lui-même dans sa section.

