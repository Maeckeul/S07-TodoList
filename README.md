# TodoList - saison 7

On veut mettre en place un petit site de gestion de nos tâches.

## Description

Le nom du projet est _TodoList_.

C'est un petit site permettant de gérer ses tâches, quel que soit leur sujet.

Il ne contient qu'_une seule et unique page_ permettant de réaliser toutes les actions nécessaires.  
Cette page va lister toutes les tâches déjà saisies, ainsi que leurs catégories respectives. Seules les tâches actives (non archivées) sont affichées par défaut.

Pour chaque tâche, on pourra :

- modifier son nom
- la marquer comme "complète" (== terminée)
- la marquer comme "incomplète" (== en cours de réalisation)
- l'archiver
- la supprimer (si et seulement si elle est déjà archivée)

Un formulaire en bas de la liste permettra d'ajouter facilement une nouvelle tâche en renseignant son nom, et la catégorie liée.

En haut du site, on pourra filtrer la liste des tâches de la façon suivante :

- toutes / complétées / non complétées
- catégorie

Ces 2 filtres doivent se cumuler et permettre ainsi de lister, par exemple, toutes les tâches complétées d'une catégorie, ou bien les tâches archivées toutes catégories confondues.

On pourra aussi accéder spécifiquement aux tâches archivées grâce à un lien en haut de page.

### :warning: Précisions techniques

- chaque action sur le site se fera **sans jamais recharger la page**
- le site devra s'adapter à tous les écrans, donc : **_Responsive Design_**

## Fichiers techniques

- [User stories](docs/user_stories.md)
- [Product backlog](docs/product_backlog.md)
- [Wireframe](docs/wireframe.png)

## Organisation

L'organisation est horizontale. Des rôles sont définis.  
Quel que soit son rôle, « on » ne donne d'ordre à personne.  
Chacun assume son rôle et s'occupe de sa partie, de ses responsabilités.  
Chacun communique et se coordonne avec les autres.

### Rôle : _Product Owner_

Fiche récap : https://github.com/O-clock-Alumni/fiches-recap/blob/master/gestion-projet/methode-scrum.md#product-owner

Guillaume Rejalot tiendra le rôle de _Product Owner_ 🤠.  

Le _Product Owner_ est l'unique rédacteur du _Product Backlog_.  
Le _Product Owner_ peut aider les développeurs pour clarifier certaines fonctionnalités, répondre aux questions sur le projet.  
Il est dépositaire de la vision.

### Rôle : _Scrum Master_

Fiche récap : https://github.com/O-clock-Alumni/fiches-recap/blob/master/gestion-projet/methode-scrum.md#scrum-master

Guillaume Sylvestre tiendra le rôle de _Scrum Master_  😎

Le _Scrum Master_ est une aide, un support aux autres membres de l'équipe.  
Il s'assure que tout le monde suive bien la méthodologie _Scrum_.  
Il anime notamment les réunions _Daily Scrum_ et la constitution du _Sprint Backlog_.

### Rôle : _Developer_

Fiche récap : https://github.com/O-clock-Alumni/fiches-recap/blob/master/gestion-projet/methode-scrum.md#%C3%A9quipe

Le prof _et_ les étudiants ont le rôle de _Developer_ :muscle:

Lors du _Sprint Planning_, les développeurs sont les seuls à décider quels éléments du _Product Backlog_ sont à intégrer au _Sprint Backlog_. Pour cela, ils prennent en compte l'importance de chaque élément pour essayer de les réaliser en priorité.  
Lors du _Sprint Planning_, les développeurs peuvent utiliser le _Planning Poker_ ([fiche récap](https://github.com/O-clock-Alumni/fiches-recap/blob/master/gestion-projet/methode-scrum.md#planning-poker)) pour déterminer l'effort (la difficulté, la complexité) pour chaque élément du _Product Backlog_ (il n'est pas nécessaire de passer sur toutes les user stories).

### Sprints

Chaque _Sprint_ va durer une "saison", soit 8 jours.

À la fin de chaque _Sprint_ sera livré un _Incrément_ du projet, contenant les fonctionnalités mises en place (issues du _Sprint Backlog_).

> Dans le cadre de la saison, on va réaliser un, et un seul, _Sprint_. Mais c'est déjà l'occasion d'implémenter pas mal de choses !

### Daily Scrum

À chaque début de journée, les _Developers_ organisent un _Daily Scrum_ "lite" (léger) afin de savoir :

- ce que chacun a fait la veille
- ce que chacun compte faire aujourd'hui
- si quelque chose nous bloque, quoi exactement

## Versions du projet

Le logiciel de versionning pour ce projet sera _Git_.

Chaque fonctionnalité sera codée dans une branche séparée.  
Lorsque la fonctionnalité est terminée, une _Pull Request_, avec 3 à 4 reviewers parmi les _Developers_, sera créée afin de garantir la qualité du code. Une fois validée, la _Pull Request_ pourra être fusionnée dans la branche `master`.

## Documentation

La documentation technique devra être rédigée **en anglais**.
