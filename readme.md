#PDO - TP
Pour tous les TP, il faudra respecter ces règles :
- Respecter le modèle MVC
- Nommer ses variables, fonctions, bases, tables et champs en anglais  
- Soigner son CSS
- Avoir un HTML valide
- Utiliser Netbeans et Xdebug
- Chaque TP doit avoir son propore VHOST
- Utiliser des classes serait un plus




##TP 1
Créer un base avec une table permettant d'enregistrer un utilisateur. Un utilisateur est défini comme tel :
- Nom - 50 caractères max
- Prénom - 50 caractères max
- Date de naissance - Date
- Adresse - Texte
- Code Postal - 5 caractères max
- Numéro de téléphone - 10 caractères max
- Service - entier

Créer une table Service :
- Nom du service - 50 caractères max
- Description - 100 caractères max

Remplir la table Service avec ces informations :

Nom du service   |   Description
------           |    ---
Maintenance      |   Les spécialistes du Hardware
Web Developer    |   Pour eux tout est code
Web Designer     |   Y a que le CSS dans la vie
Reférenceur      |   Regarde les Serps Google du matin au soir et du soir au matin

Faire une page index permettant de lister les utilisateurs en affichant ces données :
- Son nom et son prénom
- Son âge
- Son adresse complète
- Son numéro de téléphone
- Son service

Sur cette page on doit pouvoir filtrer les services via une liste déroulante et donc n'afficher que ceux choisi.  
On doit aussi pourvoir supprimer un utilisateur via un bouton.  

Faire une autre page permettant d'ajouter un utilisateur. On doit s'assurer que les données saisies par l'utilisateur sont celle attendues.  
**Attention au piratage !!**
