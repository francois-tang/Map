# User Story - TP Sneakers - François TANG - M2 MIAGE FA
> **DOCUMENTATION**  

:arrow_forward: : module MaP par David CORRIAT

:arrow_forward: : écrit par François TANG

:arrow_forward: : M2 MIAGE FA - 2022-2023

----


## Story Mapping

### Version Image
<img width="1000" alt="Mapping Story" src="https://user-images.githubusercontent.com/56674425/226131804-4bdad902-8939-4fac-8272-8b0a2f1c6668.PNG">

### Version Tableau
| Site Internet |  |  |  | SAV | Programme de fidélité |  |  |  | Communication |  | THEMES |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| **Gestion front**  |  |  | **Gestion back**  | **Support**  | **Gestion des points** |  | **Gestion des cadeaux**  | **Performance du programme**  | **Réseaux sociaux** | **Mail** | **EPICS** |
| :one: - Souscrire au programme | :four: - Suivre l'évolution du statut et points | :keycap_ten: - Modifier mes informations sur le profil | :one::three: - Recevoir des alertes si le site est HS | :seven: - Contacter le support fidélité | :two: - Cumuler des points | :three: - Dépenser des points | :nine: - Recevoir le statut du livraison de la commande | :one::six: - Suivre les indicateurs | :one::two: - Accéder aux comptes réseaux sociaux et pouvoir publier | :one::one: - Envoyer des newsletters | **STORIES** |
| :six: - Demander à se désabonner du programme de fidélité  |  |  | :one::four: - Relancer les serveurs |  | :eight: - Recevoir des alertes dès un seuil franchi |  | :one::seven: - Consulter la liste des partenaires |  |  |  |  |
| :five: - Demander à intégrer les ambassadeurs |  |  | :one::five: - Effectuer des sauvegardes et revenir en arrière |  |  |  |  |  |  |  |  |

----

## User Story :one: : En tant que client, lorsque j'en ai l'envie, je peux souscrire au programme de fidélité
* Via le site internet dans la rubrique "Fidélité"


## User Story :two: : En tant que client, lorsque j'achète des produits, je dois être en mesure de gagner des points
* A 150 pts, frais de ports gratuits
* A 300 pts, 10% de réduction
* A 500 pts, invitation à un évènement privé annuel


## User Story :three: : En tant que client, lorsque j'ai atteint les seuils/paliers, je dois être en mesure de dépenser mes points afin de bénéficier des cadeaux correspondants aux seuils franchis


## User Story :four: : En tant que client, lorsque je me connecte sur le site, je peux suivre l'évolution et le statut de mon programme de fidélité
* Rappel membre depuis quand
* Rappel du statut (membre normal ou ambassadeur)
* Rappel du nombre de points
* Rappel du dernier palier atteint
* Rappel de l'historique des points déjà convertis avec leurs cadeaux associés


## User Story :five: : En tant que client, lorsque je suis très engagé envers la marque, je peux devenir ambassadeur de la marque et tester les nouveaux produits en avant-première
* Seulement pour les clients de plus d'un an.
* Via acceptation lorsque cela est proposé.


## User Story :six: : En tant que client, si je le souhaite, je peux me désabonner du programme de fidélité
* Via un bouton sur la page d'accueil du programme

## User Story :seven: : En tant que client, si je le souhaite, je peux contacter le support pour toute question relative à mon programme de fidélité
* Via un formulaire de contact et/ou un chat sur la page d'accueil du programme de fidélité


## User Story :eight: : En tant que client, lorsqu'un palier est atteint, je souhaite pouvoir être averti par mail


## User Story :nine: : En tant que client, lorsqu'une commande de cadeaux a été faite via le programme de fidélité, je souhaite pouvoir être averti par mail du statut de la livraison de la commande
* Demande faite
* Commande expédiée (même si cela est dématérialisée)
* Commande terminée


## User Story :keycap_ten: : En tant que client, je dois être en mesure de modifier mes informations me concernant sur mon profil
* Nom, prénom, adresse postale, téléphone, adresse e-mail, etc. (notamment pour l'expédition des commandes)
* Abonnement aux newsletters


## User Story :one::one: : En tant que community manager, je dois être en mesure d'envoyer des newsletters
* Aux clients qui se sont abonnés à la newsletter


## User Story :one::two: : En tant que community manager, je dois être en mesure d'accéder aux comptes sur les réseaux sociaux de la marque et pouvoir publier


## User Story :one::three: : En tant que développeur, je souhaite pouvoir être averti si la page d'accueil (URL) du programme de fidélité est hors-service
* Recevoir un mail d'alerte


## User Story :one::four: : En tant que développeur, je dois pouvoir relancer le serveur du site internet qui gère le programme de fidélité afin de rendre le service à nouveau disponible à tout moment


## User Story :one::five: : En tant que développeur, je dois pouvoir effectuer des sauvegardes afin d'effectuer un rollback à tout moment sur les données clientes

## User Story :one::six: : En tant que PMO, je dois être en mesure de suivre les indicateurs du programme de fidélité
* Taux de fidélisation des clients
* Nombre d'ambassadeurs

## User Story :one::seven: : En tant que PMO, je souhaite pouvoir consulter la liste des fournisseurs et partenaires liés au programme de fidélité
* Afin de voir les dépendances