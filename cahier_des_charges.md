# Plan du Cahier des charges

Dans une volonté d’agrandissement et de modernisation, la Bibliothèque Universitaire d’Orsay (le soumissionnaire), décide de proposer à ses utilisateurs, en plus des livres et manuels scolaires, des CD, des DVD et divers contenus. C’est dans ce cadre que, en tant que prestataire, nous a été confié la mission suivante : 
##### « La réalisation d’un site internet accessible à tous, qui permettra une exposition facile et directe de toutes les oeuvres dont dispose la médiathèque, ainsi qu’une gestion simple, efficace et rapide de la part des gérants. » 
Pour cela, nous avons établi avec les responsables, par l’intermédiaire et sous la direction de monsieur ‘Burkhart Wolff’, la liste des fonctionnalités désirées. Ce document présente donc toutes les fonctionnalités et vise à détailler les attentes de ce site internet au sein de la Bibliothèque Universitaire d'Orsay (BU d'Orsay).

Pour cela, nous veillerons à bien définir les besoins auxquels doit pouvoir répondre le site, ainsi que les contraintes qui devront être respectée par ce dernier. Tout ceci permettra de mettre en place les solutions nécessaires par la suite. 

### 1. Objectifs et contexte du produit

#### Objectifs : 

Le but de ce projet est la réalisation d'un site internet permettant la mise en place et la gestion d'une médiathèque. Celui-ci donnera la possibilité aux utilisateurs d'emprunter différents types d'œuvres, tels que des films, des CD audio, ou encore des livres, tout en permettant aux gestionnaires de gérer la médiathèque le plus rapidement et efficacement possible.

Nous allons, dans un premier temps, chercher à définir les points que ce site internet vise à améliorer ou faciliter. 
Il faut répondre aux besoins de deux types de personnes : les gestionnaires s'occupant de l'organisation de la médiathèque et les utilisateurs de celle-ci qui pourront consulter et emprunter des oeuvres. 

- Les Gestionnaires : Nous cherchons, dans ce cas, à sortir du cadre d'une petite médiathèque ayant une organisation traditionnelle, c'est-à-dire avec un(e) bibliothècaire qui connait tous les rayons par cœur et se charge de replacer les livres dans leurs rayons, notes toutes les sorties dans des registres et relance par courrier postal les visiteurs réfractaires. Ce site internet doit permettre une gestion simple de toutes ces actions peut importe leurs échelles, la taille de la médiathèque ou encore le nombre de personnel présent.

- Les Utilisateurs : Ce site doit aussi pouvoir permettre de faciliter la recherche et l'emprunt des médias par l'utilisateur. En effet, donner la possibilité à l'utilisateur de ne pas fouiller toutes les étagères pour trouver ce qu'il souhaite, mais plutôt de faire une recherche sur le site pour savoir si le média désiré existe, s'il est dans le catalogue de la médiathèque et s'il en reste encore des copies disponibles à l'emprunt. 

Nous devons également offrir au public de la médiathèque un site internet rapide, fiable et simple d'utilisation pour leur permettre de trouver une œuvre et de l'emprunter tout en proposant aux gestionnaires de gérer efficacement les contenus de la médiathèque, le suivi des emprunts et la mise en avant des œuvres disponibles.

Pour identifier les solutions à mettre en place pour répondre à toutes les fonctionnalités des gérants et du public, nous allons répondre aux questions suivantes : 

###### a) A qui le produit rend-il service ?

Le produit rend service aux :
- Visiteurs (sans compte)
- Utilisateurs (avec compte)
- Gestionnaires
- Administrateurs


###### b) Sur quoi agit-il ?

Ce site internet, pour permettre l'emprunt de média aux utilisateurs ainsi que la gestion de la médiathèque par les employés, va principalement s'appuyer sur la gestion d'une base de données. 

###### c) Dans quel but ?

- Visiteurs : 
	- rechercher une œuvre de la médiathèque selon des critères
		> Rechercher par type de média (Audio, Livre, Film, ...), par titre, par auteur, etc...
	- visualiser les informations générales d'un média
		> Proposer un aperçu de l'œuvre, accompagné d'un descriptif et du nom de l'auteur, mais également proposer la publication et la visualisation de commentaires sur l'œuvre ainsi que son emplacement physique au sein de la médiathèque (pour ne pas avoir à fouiller tous les rayons).

- Utilisateurs : 
	- se connecter à son compte utilisateur
	- rechercher une œuvre de la médiathèque selon des critères
	- visualiser les informations générales d'un média
	- réserver et emprunter un média
		> En visualisant et choisissant les dates durant lesquelles il est disponible. Cette réservation permettra aux utilisateurs de visualiser, sur un sélecteur de date, les dates durant lesquelles l'œuvre est disponible pour pouvoir choisir sa date d'emprunt.
	- visualiser/modifier ses informations personnelles
		> Donner uniquement la possibilité de changer certaines informations telles que l'adresse e-mail ou encore le numéro de téléphone, pour permettre aux gestionnaires de contacter l'utilisateurs en cas de retard lors du retour d'une œuvre.  
	- effectuer éventuellement un payement 
		> Base de données avec semblants de dépôt d'argent dans un premier temps. L'utilisateur pourrait créditer son compte en déposant sa caution en ligne. (optionnel : véritable payement avec, par exemple, PayPal)

- Gestionnaire :
	- se connecter en tant que gestionnaire 
		> Pour avoir accès à plus d'options sur le site que les visiteurs et utilisateurs
	- effectuer certaines fonctionnalités disponibles pour les utilisateurs
		> Le gestionnaire pourra, par exemple, effectuer la recherche d'une œuvre selon des critères ou encore visualiser les informations d'un média. Mais contrairement aux utilisateurs, il ne pourra pas utiliser son compte de gestionnaire pour effectuer des réservations ou emprunts, et devra, pour cela, se créer son propre compte utilisateur.
	- créer un compte utilisateur et gérer les comptes
		> Le gestionnaire devant vérifier l'identité du futur utilisateur, il faudra fournir des documents d'identités ou faire une inscription sur place si on ne peut pas prouver son identité en ligne.
		> Il peut également supprimer des comptes utilisateurs si besoin et créditer leur caution lorsqu'un utilisateur la dépose sur place.
	- ajouter/modifier/supprimer une œuvre et ses informations générales
	- ajouter/éditer/supprimer des articles sur une page d'actualité
		> La page d'accueil du site internet proposera la lecture de différents articles, et la visualisation de certaines nouveautés ou la suggestion d'œuvre de la médiathèque.
	- visualiser les statistiques
		> S'il y a trop de retards ou de vols dans une catégorie, le gestionnaire pourra décider l'arrêt de l'achat de cette catégorie de produit.
	- optionnel : créer un type de média (Audio-CD, Film-DVD, ...)
	- optionnel : configurer les mails de rappels (fin de réservation, délais de retour dépassé, annonce de sanction)

- Administrateur :
	- créer les comptes des gestionnaires et les supprimer si besoin
	
- Système : 
	- sécuriser les mots de passe
		> Sécuriser et crypter les mots de passe dans la base de données pour que même les gestionnaires n'y aient pas accès
	- envoyer un e-mail automatiquement à l'utilisateur si la date de retour est dépassée
		> Dans le cas où un utilisateur ne rend pas un média avant la date de retour définie au moment de l'emprunt, celui-ci doit recevoir un mail du système(donc automatiquement) l'informant qu'il est en retard et des modalités qui suivront(amendes).
	- ajouter des pénalités aux utilisateurs s'ils ne respectent pas la date de retour
		> Le système doit pouvoir prélever sa caution (ou une partie de celle-ci) à un utilisateur lorsqu'il ne respecte pas les dates de retours définies au moment de l'emprunt.
	- décréditer la caution des utilisateurs
		> Le système doit automatiquement pouvoir appliquer les mesures annoncées dans le mail de relance, à savoir décréditer la caution de l'utilisateur (en fonction du média non rendu).
	- vérifier si la caution de l'utilisateur est suffisante pour emprunter un média
		> Vérifier à chaque demande d'emprunt d'une oeuvre que la caution de l'utilisateur soit assez élevée pour pouvoir la rembourser s'il ne la rend pas. Refuser la demande d'emprunt si l'utilisateur n'a pas une caution suffisante (défini en fonction du média). Proposer à l'utilisateur de recharger sa caution dans ce cas
	- établir des statistiques sur les retards ou les vols
		> Enregistrer le nom et caractéristiques des médias qui sont le plus rendus en retard ou non-rendus, et établir des statistiques selon différents critères : leurs placements dans la médiathèque (par rangée ou étagère par exemple), leurs types (CD ou livre par exemple) ou leurs prix.

### 2. Contraintes

Toutes les fonctionnalités qui viennent d'être identifiées soulèvent les différentes contraintes suivantes qui devront être respectées : 

- De sécurité : 
	- sécurité des données de la BD
		> Empêcher toutes requêtes vers la base de données, sécuriser les champs de formulaire INPUT pour éviter l'insertion de requêtes SQL, ...
	- sécurité de l'application
		> Ne pas pouvoir accéder au code
	- sécurité des mots de passe
		> Sécuriser et crypter les mots de passes dans la base de données pour que même les gestionnaires n'y aient pas accès
- Matérielles : 
	- multiplateforme car site internet utilisant un navigateur web. 
		> Utilisation des technologies web modernes donc compatibilité avec les dernières versions de Chrome, Firefox, Opera, Vivaldi et Microsoft Edge (compatibilité non garantie sur Internet Explorer)
	- site internet adapté le plus possible aux différents supports
		> Adapté pour les ordinateurs, les tablettes et les téléphones portables
