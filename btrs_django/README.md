Système de réservation de car en ligne utilisant Django en Python

Ce projet s'intitule Online Bus Reservation System . Il s'agit d'une application Web qui fournit une plate-forme en ligne permettant aux clients/passagers de la compagnie d'autobus de réserver leurs places à l'avance. L'application aide les passagers à trouver le trajet en bus prévu disponible qui correspond à la date de départ et à la destination souhaitées. L'application a été développée avec Python et Django Framework. Il a une interface utilisateur agréable avec l'aide du Bootstrap Framework . Le projet a également des caractéristiques et des fonctionnalités conviviales

À propos du système de réservation de bus en ligne

J'ai développé ce projet en utilisant les éléments suivants :

Python
Django
HTML
CSS
Javascript
jQuery
Ajax
Amorçage v5
Modèle Bootstrap de conception matérielle
Police-Génial
Ce projet de système de réservation de bus en ligne est accessible uniquement au public. Outre  le site d'administration intégré de Django , la gestion dispose de son propre site d'administration où les utilisateurs de gestion peuvent accéder et gérer toutes les données du système. Les utilisateurs administrateurs peuvent gérer la catégorie de bus, le bus, l'emplacement et la liste des horaires de trajet . Utilisateurs administrateurssont ceux qui sont chargés de mettre à jour ou de gérer la réservation ou la liste de réservation. Le passager éventuel peut simplement parcourir le système. Les passagers découvrent les différents horaires de voyage de la compagnie. Ils peuvent également trouver les trajets disponibles à la date de départ souhaitée et à leur destination. Les passagers peuvent réserver ou réserver leurs places en remplissant simplement les champs de la liste de réservation.

Caractéristiques


Côté gestion
Connexion
Page d'accueil/Tableau de bord
Affiche le résumé

Gestion des catégories

Ajouter une nouvelle catégorie
Lister toutes les catégories
Mettre à jour les détails de la catégorie
Supprimer les détails de la catégorie

Gestion de l'emplacement

Ajouter un nouvel emplacement
Répertorier tous les emplacements
Mettre à jour les détails de l'emplacement
Supprimer les détails de l'emplacement

Gestion des autobus

Ajouter un nouveau bus
Lister tous les bus
Mettre à jour les détails du bus
Supprimer les détails du bus

Gestion des horaires de voyage

Ajouter un nouveau programme de voyage
Répertorier tous les horaires de voyage
Mettre à jour les détails du programme de voyage
Supprimer les détails du programme de voyage

Gestion des réservations

Ajouter une nouvelle réservation de voyage
Répertorier toutes les réservations de voyage
Mettre à jour les détails de la réservation de voyage
Supprimer les détails de la réservation de voyage
Profil
Mettre à jour les détails du profil
Mettre à jour le mot de passe du compte
Se déconnecter

Côté public

Page d'accueil
Trouver des horaires de voyage
Lister tous les voyages à venir
Réserver ou réserver une place pour un voyage

Comment courir

Téléchargez/Installez les éléments suivants
Python ( j'ai utilisé la v3.9.1 )
Django ( j'ai utilisé la v4.0.3 )
PIP ( pour l'installation des modules Python )

Ouvrez votre fenêtre Terminal/Invite de commandes . (assurez-vous d'ajouter "python" et "pip" dans vos variables d'environnement)
Remplacez le répertoire de travail par le dossier du code source extrait. c'est à direcd C:\Users\Personal-23\Desktop\django_btrs
Exécutez les commandes suivantes :
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
Ouvrez un navigateur Web et naviguezhttp://localhost:8000/ ouhttp://127.0.0.1:8000/


Informations d'accès


Nom d'utilisateur du superutilisateur
: admin
Mot de passe : admin123