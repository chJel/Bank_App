# Bank_App
Rapport du projet :

Introduction :
Ce rapport présente les informations principales concernant l'application Bank-App. Il met l'accent sur le contexte général de l'application, ainsi que sur l'architecture du projet, tant pour le backend que pour le frontend.


Contexte général de l'application :
L'application Bank-App permet aux utilisateurs d'accéder à leurs comptes bancaires en ligne de manière pratique et sécurisée. Elle offre différentes fonctionnalités telles que la création de nouveaux comptes, la gestion des opérations financières (débits, crédits, transferts, etc.), ainsi que la consultation des informations relatives aux comptes.

Architecture du projet :
L'architecture du projet est conçue de manière à assurer une structure solide et organisée, facilitant le développement et la maintenance de l'application.

Architecture du Backend :
Le backend de l'application Bank-App est basé sur une architecture multicouche courante, utilisant le framework Spring MVC. Voici les principales couches de l'architecture :

Couche de Présentation (Presentation Layer) : Cette couche gère les requêtes HTTP provenant du frontend et les réponses correspondantes. Les contrôleurs REST sont utilisés pour traiter ces requêtes et coordonner les interactions avec les couches inférieures.

Couche de Service (Service Layer) : Cette couche contient la logique métier de l'application. Elle traite les requêtes reçues des contrôleurs REST, effectue les opérations nécessaires et retourne les résultats.

Couche d'Accès aux Données (Data Access Layer) : Cette couche est responsable de l'accès aux données persistantes, généralement une base de données. Les repositories sont utilisés pour interagir avec la base de données et effectuer les opérations CRUD.

Couche de Mappage (Mapping Layer) : Cette couche permet la conversion des objets entre les entités et les DTO (Data Transfer Objects), facilitant ainsi l'échange de données entre les différentes couches.

Architecture du Frontend :
Le frontend de l'application Bank-App est basé sur le framework Angular. Voici les principaux éléments de l'architecture :

Composants (Components) : Les composants représentent les blocs de construction de l'interface utilisateur. Chaque composant gère une partie spécifique de l'interface et interagit avec les utilisateurs.

Services : Les services sont responsables de la logique métier côté client. Ils communiquent avec le backend pour récupérer les données nécessaires et effectuer des opérations via des appels HTTP.

Templates et Directives : Les templates Angular définissent la structure de l'interface utilisateur. Les directives sont utilisées pour ajouter des fonctionnalités et interagir avec les composants.

Routing : Le mécanisme de routage d'Angular permet de gérer la navigation entre les différentes pages et vues de l'application.

HTTP : Le module HTTP d'Angular est utilisé pour effectuer des requêtes HTTP vers le backend et récupérer les données requises.

Conclusion :
Ce compte rendu a présenté une vue d'ensemble de l'application Bank-App, en mettant en évidence son contexte général ainsi que son architecture, tant pour le backend que pour le frontend. L'architecture multicouche et l'utilisation des frameworks Spring MVC et Angular ont permis de développer une application Bank-App complète, fiable et conviviale.
