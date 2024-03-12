# masterTask
## Description
Application simple permettant de gérer des tâches dans un environnement serveur-client utilisant une BD et un API.
Me permet de prendre tout ce que j'ai appris dans les dernières années et les assemblers dans un seul projet.  

## Conception
L'application doit pouvoir effectuer:
- Ajout, modification, supprimer et afficher des tâches (classe tâche?) ( )
- Interface GUI pour les clients (Python:tkinter, java:javafx ?) ( )
- Serveur lié à une BD (MySql,PostgreSQL,Oracle ?) ( )
- RESTful API entre les clients et le serveur(Python:Flask, java:springBoot ?) ( )
- Interraction serveur-client grâce au protocol HTTP ( )
<img src="https://github.com/Thevaulthunter0/masterTask/assets/119818660/ae8cc0b2-be65-44c3-afdd-6b27604a5efc" width="450" height="400">

V1  
![classeTâches drawio](https://github.com/Thevaulthunter0/masterTask/assets/119818660/95855aa4-9f25-4e7a-b0a2-e0febadad827)

### Optionnel
Au moment de la conception, voici des fonctionnalités qui serait intéressante d'ajouter dans le futur. Je suis conscient que certaines de ces fonctionnalité pourrait demander une refonte de plusieurs systèmes si je ne les prends pas en compte dès le départ.
- Authentification
- Assignation
- Ajouter des sous-tâches pour afficher un % de la tâche.
- Ecrire et lire fichier excel
- Envoie email à certaines date

## Étape d'implémentation
1. Créer le GUI et ces fonctionnalités
2. Créer la base de données
3. Créer le serveur devant répondre à l'API(HTTP) et intéragissant avec la BD
4. Créer le client devant utiliser l'API(HTTP)
5. Tester
6. Deployer(essaie sur plusieurs ordinateurs distant, hebergement serveur a voir)

## Log
2024-03-12 : Commencement du projet, trouver idée et technologie utilisée.
