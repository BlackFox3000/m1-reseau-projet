# m1-reseau-projet
## Auteurs :  
DIA Hamoydy et TINTORRI Floren
## Partie 1 : Configuration Réseau
### 1.1 Topologie et Adressage : 
Voir les fichiers Vagrantfile et config.sls de chaque VM.
### 1.2 Disparition de la VM2 :
Nous allons faire passer les requêtes de VM1-4 à VM3-4 via le réseau VMx-6
Pour cela nous allons permettre à VM1-6 et VM3-6 de pouvoir comprendre, convertir, recevoir et 
envoyer des requêtes en ipv 4 en ipv6. VM2-6 servira à communiquer entre VM2-6 et VM3-6

## Partie 2 : L'interface virtuelle TUN
### 2.1 Création de l'interface : 
Voir l'image creation_interface.png 
### 2.2 Configuration de l'interface : 
1. Dans le dossier partage, se trouve le fichier tunalloc.c que nous avons utilisé pour configurer le tun0.
 Malheureusement on a pas encore réussi à faire les ping demandés aux questions 3 et 4 de la partire 2.2.
