# Application Symfony 

Il s'agit d'une application développée dans le cadre d'une recherche de travail.
J'ai eu l'idée de faire une bibliotèque pour une gestion de livres. 

A travers ce projet, j'ai appris à :
- Démarrer un projet sous Symfony
- Utiliser les outils en ligne de commande
- Respecter l'architecture MVC
- Utiliser un ORM
- Gérer un modèle objet
- Organiser les templates
- Utiliser le moteur de template Twig
- Gérer des formulaires objets
- Gérer la sécurité de manière simple
- Utiliser les fixtures

L’application permet de :

- Afficher la liste des livres contenus dans le catalogue ainsi que leur statut (disponible ou prêté)

- Ajouter un livre au catalogue

- Pouvoir trier les livres selon leur catégorie grâce à un dropdown (par exemple : roman, poésie, aventure…). Quand l’utilisateur clique par exemple sur roman, la page n’affiche que les livres de la catégorie roman.

- Pouvoir accéder à la fiche descriptive de chaque livre enregistré en BDD

- Pouvoir modifier la statut de chaque livre de disponible à prêté et de prêté à disponible. Quand un livre est prêté le/la bibliothécaire indique le numéro d’identification unique de l’utilisateur afin de savoir qui a emprunté quoi. Quand on revient sur la fiche descriptive du livre celle-ci indique maintenant les informations du livre ainsi que celles de l’utilisateur qui l’a emprunté.

- Afficher la liste de tous les utilisateurs enregistrés dans le système ainsi que leurs informations personnelles et les livres qu’ils ont éventuellement empruntés quand on clique sur leur fiche personnelle.

Pour rappel, voici une liste non exhaustive des informations utiles à connaître à propos d’un livre : titre, auteur, résumé, date de parution, catégorie. Bien entendu on peut en rajouter d’autres.

Spécifications techniques :
- Framework Symfony 5, dernière version maintenue ( c'est quasiment la même que la 4 au final il y'a pas beaucoup de différences )
- Sécurité gérée sans bundle
- Crud réalisé sans l'outil Doctrine de génération du CRUD
- Utilisation d'un framework CSS pour le front, idéalement Bootstrap 4




