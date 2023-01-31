# Exercice USTS

Le but de cet exercice est de développer une application Android / iOS permettant aux utilisateurs de se voir en temps réel sur une carte via la géolocalisation du device.
Il vous faudra pour cela développer une API permettant d'accueillir les données des utilisateurs afin de les synchroniser entre tous les clients et de développer l'application associée qui permettra l'envoi et la réception de ces données de géolocalisation.

Les Framework à utiliser sont :
* **Client** : Ionic Angular (dans sa dernière version stable)
* **API** : Symfony (dans sa dernière version stable) sur un PHP 8.1

Le projet final devrait avoir un système d'authentification (email ou identifiant simple) et une carte afin de visualiser les autres utilisateurs en temps réel.

Le choix des librairies / packages utilisés vous revient, mais faites attention à la compatibilité des paquets et évitez les librairies abandonnées / dépréciées ou dans des versions incompatibles avec votre framework (particulièrement pour le client).

Si vous manquez de temps vous pouvez découper le projet en plusieurs partie :

**Première partie** :
Synchronisation simple sans authentification, vous développez un système simple d'échange des données entre le client et le serveur sans authentification (piste: utiliser les identifiants unique des devices pour associer les données à un utilisateur) et avec un simple affichage textuel des données de géolocalisation (latitude / longitude)

**Deuxième partie** :
Développement d'une carte (Google maps, Openstreetmap ...) permettant de voir les autres utilisateurs en temps réel

**Troisième partie** :
Mise en place du système d'authentification utilisateur via identifiant (email / username au choix) et mot de passe.

Au delà du fonctionnement de l'application un soin tout particulier doit être apporté à la **lisibilité** et le **maintient du code**. Prenez le temps de faire des services / components permettant une évolution efficace de l'application.
Le choix du visuel vous revient.

Bonne chance 🚀
